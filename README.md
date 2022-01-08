# Tomcat s2i images 


# Funcionalidades:

- Non-root
- Openshift compatible
- Jolokia Agent
- Maven 
- Gradle
- Mkdocs integracion

### Variables


| Variable | Detalle |
| ------ | ------ |
| TIMEZONE | Define la zona horaria a utilizar (America/Montevideo, America/El_salvador) |
| CUSTOM_JAVA_OPTS | Define parametros de la jvm |
| NEXUS_MIRROR_URL | Define url repositorio nexus para la descarga de dependencias |
| EXTRA_REPO | Define url repositorio git extra compila previo |
| TAG_VERSION | Variable usada en el proceso de build para definir la version |
| MVN_OPTS | Variable usada argumentos adicionales maven |
| MKDOCS_DIR | Directorio donde se encuentra mkdocs.yml - Ejemplo: documentation |
| MKDOCS_CONTEXT_PATH | Nombre del context path donde instalará la documentación. Por defecto es / - Ejemplo: documentation |



License
----

Martin vilche
