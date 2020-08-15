## Ejercicio de las Figuras

### Crear un proyecto con Maven
#### *Cómo se crea un proyecto maven con ayuda de los arquetipos (archetypes)*

Para crear un protecto Maven basado en arqueripo se tiene que seguir el siguiente procedimiento:

1. Seleccionar Archivo > Nuevo > Proyecto > Maven > Proyecto Maven, dar click en siguiente donde se abrira el asistente del proyetco Maven
2. Dar click en siguiente, donde se desplegia la opción de seleccionar un arquetipo.
3. Seleccionar el catálogo o o especificar un Filtro para reducir el número de arquetipos que se muestran.
4. Escribir o seleccione valores para estos campos:
  - ID de grupo
  - ID de artefacto
  - Versión
  - Paquete
5. finalmente dar en finalizar y se creará el proyecto. 

#### *Cómo ejecutar desde línea de comandos el objetivo "generate" del plugin "archetype"*
- Grupo: edu.eci.cvds
- Id del Artefacto: Patterns
- Paquete: edu.eci.cvds.patterns
- archetypeArtifactId: maven-archetype-quickstart

```
<project "edu.eci.cvds.patterns"
  <groupId>edu.eci.cvds</groupId>
  <artifactId>Patterns</artifactId>
    <build>
        <plugins>
     <plugin>
  <artifactId>maven-archetype-quickstart</artifactId>
 </project
  
```
