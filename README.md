# ProyectoIV17-18 [![Build Status](https://travis-ci.org/AntonioAlcM/ProyectoIV17-18.svg?branch=master)](https://travis-ci.org/AntonioAlcM/ProyectoIV17-18)

Como proyecto para la asignatura infraestructura virtual, he decido hacer un sistema de alertas. En este sistema tendremos un usuario que podrá crear, borrar y modificar alertas.

Cada alerta contendrá, unas geolocalización, un mensaje explicando el contenido de la alerta, un nivel de amenaza y la fecha de emisión de la alerta. Se desarrollará un sistema de búsqueda de alertas por fechas. El objetivo de este proyecto es que la gente pueda estar prevenida contra una futura catástrofe.

Servicios y herramientas que se van a usar:

1. Voy a usar una base de datos NoSQL, porque me interesa que sea escalable.
2. Voy a usar Python y el framework Flask para programar la aplicación.
3. Será desplegada en un servidor web en la nube.

## Testeo

En este proyecto vamos a utilizar la librería unittest, se ha elegido por su amplia gama de funcionalidades.

## Integración continua

Como sistema de integración continua he usado travis-ci, se ha elegido travis-ci por su fácil manejo, ademas permite instalar las dependencias requirements.txt de python de forma automática. Otra ventaja que nos aporta es la posibilidad de ejecutar los test de forma inmediata, cuando se añade nuevas funcionalidades a la clase que se esta testeando.
