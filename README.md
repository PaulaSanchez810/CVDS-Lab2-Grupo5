# CVDS-Lab2-Grupo5
# Patterns - Factory

### Cuál es su mayor utilidad
La mayor utilidad de maven es gestionar y comprimir proyectos de software, basado en un modelo de conceptos llamado (POM). Además, permite la construcción de informes, con documentación específica para un proyecto. 

### Fases de maven

Las fases componen cada ciclo de vida, generalizando las más relevantes son:
validate: Que valida que el proyecto es correcto y que está disponible toda la información necesaria
compile: Que compila el código fuente del proyecto
test: Que prueba el código compilado utilizando algún framework de pruebas unitarias. Estas pruebas no deben requerir que el código esté empaquetado o desplegado.
package: Coge el código compilado y lo empaqueta en un formato distribuible. Por ejemplo, como un JAR.
verify: Ejecuta comprobaciones de pruebas de integración para asegurarse que se cumplen los criterios de calidad
install: Instala el paquete en el repositorio local (el directorio ${user.home}/.m2) para que se pueda usar como dependencia en otros proyectos localmente
deploy: Copia el paquete final a un repositorio remoto para compartirlo con otros desarrolladores.

### Ciclo de vida de la construcción

Los ciclos de vida están compuestos por un conjunto de fases en maven, se define 3 ciclos de vida por defecto, los 3 ciclos son: 

* El ciclo de vida default, que gestiona la construcción y despliegue del proyecto.
* El ciclo de vida clean, que gestiona la limpieza del directorio del proyecto. Es decir, se encarga de eliminar todos los archivos generados en el proceso de construcción y      despliegue.
* El ciclo de vida site, que gestiona la creación de la documentación del proyecto.

### Para qué sirven los plugins

Los plugins ofrecen una funcionalidad que se conocen como objetivos, donde exiten diferentes plugyns, en los cuales algunos se encargan de gestionar la dependencia, encargos de empaquetar en un fichero jart, entre otros. Por ejemplo, estos son algunos objetivos de los plugyns:
* compiler:compile que compila el código fuente del proyecto, que está en la carpeta main/src/java
* compiler:testCompile que compila el código de las pruebas del proyecto, que está en la carpeta main/src/test

### Qué es y para qué sirve el repositorio central de maven
Maven es una herramienta que ayuda a desarrollar un proyecto basado en el entorno de una JDK, permite gestión de proyectos de software donde dan soluciones que abarcan desde compilación, distribución y documentación de proyectos. Donde proporciona una estructura estándar de proyectos, que permite la fácil reutilización de la estructura lógica. 



