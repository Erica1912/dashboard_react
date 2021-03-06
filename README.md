# Dashboard React
[![React app deployement](https://github.com/Erica1912/dashboard_react/actions/workflows/node.js.yml/badge.svg)](https://github.com/Erica1912/dashboard_react/actions/workflows/node.js.yml)

Implementación una dashboard que monitorea el status de cada  servicio por día

***Instaladores***
- Instalación del proyecto React  
    ``` 
      create-react-app dashboard_react 
     
     ```

- Para el manejo de las rutas en React se instala    
  ```
    npm install react-router-dom
   
   ```

***El proyecto se encuentra organizado por:***
- asset 
- components
- hooks
- img
- views

Esto permite tener limpio el codigo y la lógica del proyecto

***Frontend React / Hooks***

- Uso de custom hooks, useState, useEffect


***Consulta de servicio***
- Se consume el servicio de [Servicio](https://us-central1-cm-devops-294019.cloudfunctions.net/status)
- En caso de tener dificultades con el cors se recomienda instalar [Plugin_Cors](https://chrome.google.com/webstore/detail/local-cors/bhachhlaofmplbfnefenmlnflolelkff?hl=en)

*Nota importante sobre el servicio*
- El servicio se encuentra construido como:

  ``` 
      objeto {} -> array [] -> objeto{}  
  
  ```
- Es necesario identificar esta estructura para posterior realizar las destructuración necesaria del servicio

***Para la actualización de la página***

- Utilizamos la función *setInterval()* dentro de archivo *FetcHook.jsx* esto permite actualizar la página cada 2 minutos


***Git Action***
- Para generar [Building](https://github.com/Erica1912/dashboard_react/actions) del dashboard uso los action de git
- Page Git, url de la publicación  [Dashboard](https://erica1912.github.io/dashboard_react/)


*Erica Ruiz*
