# Introducción
¡Hola! Si estás aquí, probablemente hayas solicitado un puesto de Full-Stack Developer en Kirana Labs, ¡bienvenido! Estás a muy pocos pasos de unirte al equipo y no podríamos estar más emocionados. Este desafío está destinado a poner a prueba tus habilidades analíticas y de programacion, y no debería llevarte más de 2 horas completarlo (aunque por lo general es mucho menos). Se puede hacer con cualquier framework con el que te sientas más cómodo.

# El reto
Crea tu propio repositorio donde desarrollarás el desafío, no hagas commit, push o PRs a este repositorio.

Este repositorio incluye un archivo CSV que necesitamos procesar y representar en una página web. El archivo CSV contiene datos de la guía telefónica sobre personas, su nombre, correo electrónico y número de teléfono, pero lamentablemente los datos *son un desastre*.

Necesitamos una plataforma en la que el usuario pueda cargar un archivo CSV con la misma estructura que el incluido en este repositorio y el sistema:

- Muestre los valores CSV en una tabla
- Elimine líneas que estén completamente duplicadas (dos líneas están completamente duplicadas si comparten exactamente los mismos datos en nombre, correo electrónico y número de teléfono)
- Resalte con color rojo las líneas que contienen valores repetidos
- Resalte con amarillo los valores que no son válidos (un correo electrónico no válido o un número de teléfono no válido [no 10 dígitos])
- Cuente el número de líneas que tienen valores duplicados y muestre el número en la plataforma encima de la tabla
- Muestre el número total de personas en la guía telefónica
- Guarde los valores únicos del CSV en una base de datos (MySQL, PostgreSQL, MongoDB, etc.)

Ya que esto es para una posición full stack, el procesamiento del archivo debe de suceder en el backend y el frontend se debe de limitar a presentar los resultados. El código debe de exponer un endpoint que reciba un archivo CSV y regrese un JSON con la información procesada. El endpoint debe de ser accesible desde la página web.

Tienes 2 horas para completar el desafío. Una vez que termines, comparte la liga de tu repositorio a juanma@kiranalabs.mx

# Colaboradores
Si tiene alguna pregunta, no dudes en comunicarse con cualquiera de los siguientes colaboradores:
- [Juan Manuel Pérez](mailto:juanma@kiranalabs.mx)

PS. You can find the english version of this challenge here: [README-en.md](/README-en.md)