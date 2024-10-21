# Strix Flotas Automation
 
Este repositorio contiene lo necesario para la ejecución de las pruebas automatizadas.
Las mismas brindan cobertura tanto al Frontend como al Backend.
Para la realización de las pruebas la herramienta utilizada es <img src="https://github.com/devicons/devicon/blob/master/icons/cypressio/cypressio-original.svg" title="Cypress" alt="CypressIO" width="40" height="40">&nbsp;.
 
---
 
### Instalación de Cypress:
 
1. Instalar **Node JS**. Ingresando en el siguiente sitio https://nodejs.org/es/, (Descargar e instalar la versión TLS).
2. Tener un editor de código. Se recomienda **Visual Studio Code**, puede descargarse desde el siguiente enlace https://code.visualstudio.com/, (Seleccionar la opción Stable Build).
3. Para instalar Cypress se recomienda utilizar "NPM", Es tan sencillo como dirigirnos a la carpeta del proyecto y ejecutar el siguiente comando:
**npm i -D cypress**
 
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original-wordmark.svg" title="NodeJS" alt="NodeJS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original.svg" title="VS Code" **alt="vscode" width="30" height="30"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/npm/npm-original-wordmark.svg" title="NPM" **alt="NPM" width="40" height="40"/>&nbsp;
</div>
 
---
 
### Lenguajes utilizados:
 
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" title="Python" **alt="Python" width="40" height="40"/>&nbsp;
</div>
<br>
 
- *Nota:* Aunque Cypress no soporta Python, se han integrado procesos externos como la conversión de archivos Avro a JSON mediante scripts de Node.js. Esto permite mantener las pruebas organizadas y facilitar la interacción con diferentes formatos de archivo sin tener que salir del entorno de pruebas de Cypress.
 
---
 
### Extensiones utilizadas:
 
1. **Cypress-plugin-api**: es un complemento para automatizar las API y proporciona la interfaz de usuario donde podemos imprimir la información sobre la llamada a la API.
- *Instalación:* ejecutar el siguiente comando desde la terminal del editor de código utilizado **npm i cypress-plugin-api**
2. **Allure**: es una herramienta flexible de reportes de prueba, para mostrar una representación detallada de lo que se ha probado y extraer el máximo de la ejecución de las pruebas.
- *Instalación:* ejecutar el siguiente comando desde la terminal del editor de código utilizado **npm i -D allure-cypress**
- *Nota:* Para el correcto funcionamiento de ésta extensión se debe tener instalado **Java** (versión 8 o superior) y su directorio se especifica en la variable de entorno **JAVA_HOME** (descargar para windows en el siguiente enlace: https://www.java.com/es/download/ie_manual.jsp) y **Allure** (requiere tener instalado **Scoop**, https://scoop.sh/. Para instalar se ejecuta el siguiente comando en la terminal **scoop install allure**)
3. **Prettier**: es una herramienta que nos permite diseñar el formato del código que se está escribiendo.
- *Instalación:* ejecutar el siguiente comando desde la terminal del editor de código utilizado **npm i -D prettier**
4. **Cross-env**: hace que pueda tener un solo comando sin preocuparse por configurar o usar la variable de entorno, asegurando que los scripts funcionen en diferentes sistemas operativos sin cambios adicionales.
- *Instalación:* ejecutar el siguiente comando desde la terminal del editor de código utilizado **npm i cross-env**
5. **Cypress-plugin-config**: permite tener una configuración centralizada para diferentes entornos (desarrollo, test, producción, etc.).
- *Instalación:* ejecutar el siguiente comando desde la terminal del editor de código utilizado **npm i cypress-plugin-config**
6. **Node-Postgres**: es una biblioteca de cliente para Node.js que facilita la interacción con bases de datos PostgreSQL.
- *Instalación:* ejecutar el siguiente comando desde la terminal del editor de código utilizado **npm i pg**
7. **AWS SDK**: es la biblioteca oficial de Amazon Web Services (AWS) para JavaScript, que permite interactuar con los diversos servicios de AWS desde sus aplicaciones, ya sea en el navegador o en entornos de servidor como Node.js. Proporciona una interfaz simple para acceder a servicios como S3, DynamoDB, Lambda, y muchos más.
- *Instalación:* ejecutar el siguiente comando desde la terminal del editor de código utilizado **npm i aws-sdk**
 
<div align="center">
    <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="60">
    <strong>_Ante alguna eventualidad consultar al equipo de QA_</strong>
    <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="60">
</div>
 
<br>
</div>
<div align="center">
  <img src="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" width="600" height="300"/>
</div>
 
