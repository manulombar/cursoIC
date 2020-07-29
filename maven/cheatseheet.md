#mvn

## creacion de un nuevo proyecto java basado en plantilla (arquetipo)
mvn archetype:generate -DarchetypeArtifactId=maven-archetype-quickstart
mvn archetype:generate -DarchetypeArtifactId=maven-archetype-webapp

##Idsentificar un proyecto maven
- groupID: 
    - Empresa/Organización a cargo del desarrollo (dominio invertido)
        - Ejemplo: com.gfi
    - Que estoy desarrollando a alto nivel
        - Ejemplo: web-app-nominas
    - Se juntan con un punto: com.gfi.web-app-nominas
- artifactID: Que es nuestro proyecto
        - Ejemplo: web-services
El identificador de un proyecto es la suma de groupID + ArtefactID



# GOLES
mvn gole_name
    - compile: compilacion del proyecto
    - test-compile: compilar los test unitarios
    - test: ejecutar todas las pruebas unitarias
    - package: empaquetar el proyecto
    - clean: 
    - install: inscluye nuestro artefacto en proyecto