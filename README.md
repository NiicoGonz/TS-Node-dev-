# Node con TypeScript - TS-Node-dev (preferido)

Este repositorio contiene una configuración inicial para trabajar con Node.js utilizando TypeScript y TS-Node-dev, una herramienta que facilita el desarrollo en TypeScript con reinicio automático del servidor.

## Instalación de dependencias
Para comenzar, asegúrate de tener Node.js instalado en tu sistema. Luego, ejecuta el siguiente comando para instalar TypeScript, TS-Node-dev y otras dependencias necesarias:

`npm i -D typescript @types/node ts-node-dev rimraf`


## Configuración de TypeScript
Una vez que las dependencias estén instaladas, inicializa el archivo de configuración de TypeScript. Puedes personalizar esta configuración según tus preferencias. Ejecuta el siguiente comando:

`npx tsc --init --outDir dist/ --rootDir src`

## Scripts disponibles
Hemos configurado algunos scripts útiles para facilitar el desarrollo, construcción y ejecución de la aplicación.

### Desarrollo
El script `dev` utiliza TS-Node-dev para iniciar el servidor en modo de desarrollo. Este script supervisará los cambios en tus archivos TypeScript y reiniciará automáticamente el servidor cuando sea necesario. Ejecuta:

`npm run dev`

### Construcción
El script `build` se encarga de compilar tu código TypeScript en JavaScript y limpiar el directorio de salida (`dist/`). Ejecuta:

`npm run build`

### Inicio
El script `start` construirá el proyecto y luego iniciará la aplicación Node.js. Ejecuta:

`npm start`


## Recursos adicionales
Para obtener más información sobre TS-Node-dev y sus opciones de configuración, consulta la [documentación oficial](https://www.npmjs.com/package/ts-node-dev).

¡Ahora estás listo para comenzar a desarrollar tu aplicación Node.js con TypeScript de manera eficiente y productiva! Si tienes alguna pregunta o problema, no dudes en consultar la documentación o crear un problema en este repositorio. ¡Feliz codificación!


