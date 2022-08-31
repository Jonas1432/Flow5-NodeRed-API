# Flow5-NodeRed-API

Este repositorio contiene el flow de NodeRed para obtener la informacion climatica por API desde openweathermap.org

# Referencias 

En los siguientes enlaces puedes encontrar cursos en la plataforma de edu.codigoiot.com 

## ||Material Necesario||

- [Ubuntu 20.04](https://releases.ubuntu.com/20.04/)
- [NodeJS](https://nodejs.org/es/)
    - [NPM](https://www.npmjs.com/)
    - [NodeRed](https://nodered.org/docs/getting-started/local)
    - [Nodos Dashboard](https://flows.nodered.org/node/node-red-dashboard)
    - [OpenWeatherMap](https://home.openweathermap.org/)

## Procedimiento

1. Importan el Json del Flow-4 que consiste en recibe la información por MQTT con un broker local.
2. Implementaremos un timestamp y un HTTP request para recibir nuestra API key que contendra las variables Tem y Humidity
con sus respetivos valores.
3. Para esto necesitamos generar una cuenta en la pagina OpenWeatherMap.org
4. Finalmente generamos la [APIKey] (https://openweathermap.org/api) para poder realizar lo siguiente...

# Ejercicio

1. Buscamos nuestra ubicacion o de un lugar en particular para obtener la Temperatura y Humedad.
2. Mediante la log y lat obtenedremos estos valores del lugar, asi mismo nuestra APIKey que generamos.
3. Una vez tenemos estos datos los almacenamos en esta url para verificar que lo estamos obteniendo.
https://api.openweathermap.org/data/[2.5]/weather?lat=[18.921807]&lon=[-99.233722]&appid=[11143d6a6396f0050fce3fe79251406e]&units=metric
4. Verificar que funcione corectamente, no olvides poner la version 2.5 como se muestra en la URL.
5. Visualiza que el ejercicio se vea asi, recuerda poner Url en el componente HTTP request como se muestra aqui.
6. Por ultimo ejecuta el Flow-5 como resultado se muestra en la imagen siguiente ---->

![](https://github.com/Jonas1432/Flow5-NodeRed-API/blob/main/Ejercicio-5.png)

## [Resultado]

![](https://github.com/Jonas1432/Flow5-NodeRed-API/blob/main/Flow-5.png)

# Créditos

* Desarrollado por Jonathan Araujo
* https://github.com/Jonas1432