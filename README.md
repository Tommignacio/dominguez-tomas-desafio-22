# Inicialización:

_Ejecutar este comando para poder comenzar a utilizar el código sin problemas._

```
npm i
```


# Comandos para ejecutar la aplicación:

_Al ejecutar los comandos de la siguiente manera se estará usando el modo FORK que seria por defecto._

* [PRODUCCION] - usando node:
```
npm start
```
* [DEVELOPMENT] - usando nodemon.
```
npm run dev
```

_Para cambiar el puerto y el modo por defecto se puede ejecutar los comandos de la siguiente manera._

```
npm <comando de ejecucion> -- -p <número del puerto> -m <ingresar "fork" o "cluster">
```


## **🚨 Tener en cuenta 🚨 📢** (Estas configuraciones evitarán ciertos errores durante el testeo)
  
_- Modificar el archivo .env de la siguiente manera:_
  - Ubicarse en "./.env.example"
  - Cambiar el nombre a ".env"
  - Modificar los datos sensibles y guardar.

_- Para crear una cuenta "admin" debe colocar admin. antes de su correo, por ejemplo:_
  ```
    admin.el_correo@mail.com
  ```

_- Para testear las respuestas via email o sms, se recomienda registrarse con una cuenta y números válidas._

_- Para registrar tantas cuentas como se crean necesarias para testear el desafio [REFORMAR PARA USAR GRAPHQL] debe ingresar a uno de mis desafios anteriores, por ejemplo: ["clase 40 - tarea"](https://github.com/JPX-0/backend-40__ParionaVenturaJulio/tree/main/desafio%20clase%2040), ejecutar la aplicación y registrar nuevas cuentas. Una vez registrado los datos puede parar la ejecución de la aplicacion "clase 40 - tarea" y ejecutar la de hoy: "clase 44 - tarea"_


## **Recomendaciones 💬** 
  * _Leer el archivo env.md para ver mas detalles a considerar._


# Entrega de desafío:
_La respuesta a las consignas la encontrará en la siguiente ruta:_
> ubicación: "./desafio.md"