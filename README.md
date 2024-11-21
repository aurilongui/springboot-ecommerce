# Instrucciones para ejecutar el proyecto / Instructions to Run the Project

## Castellano / English

### Requisitos previos / Prerequisites
Asegúrate de tener instalados y configurados correctamente los siguientes componentes: / Ensure the following components are installed and properly configured on your system:

1. **Java 17**  
   Verifica que Java 17 o superior esté instalado. / Verify that Java 17 or higher is installed.

2. **Maven**  
   Asegúrate de tener Maven instalado y configurado. / Make sure you have Maven installed and configured.


### Ejecutar el proyecto desde un IDE (Intellij IDEA, Eclipse, etc.) / Running the Project in an IDE (IntelliJ IDEA, Eclipse, etc.)

1. **Habilitar el procesamiento de anotaciones (Lombok) / Enable Annotation Processing (Lombok)**  
   - Instala el plugin Lombok desde el gestor de plugins del IDE si aún no lo tienes instalado. / Install the Lombok plugin from your IDE's plugin manager if not already installed.
   
   - Habilita el procesamiento de anotaciones en las configuraciones del IDE. / Enable annotation processing in your IDE settings.

2. **Actualizar dependencias Maven / Update Maven Dependencies**  
   - Asegúrate de que el IDE haya detectado automáticamente el archivo pom.xml y descargue las dependencias necesarias. / Ensure the IDE detects the pom.xml file and automatically downloads the required dependencies.
   
   - Si no es así, recarga el proyecto desde el panel de Maven del IDE o selecciona manualmente la opción de actualizar dependencias. / If it doesn’t, reload the project from the Maven panel or manually select the option to update dependencies.

3. **Ejecutar la clase principal del proyecto / Run the Main Class** 
   - Localiza la clase **com.ecommerce.project.SbEcomApplication**, y selecciona "run SbEcomApplication.main()" haciendo click derecho sobre ella. / Locate the class **com.ecommerce.project.SbEcomApplication**, and select "run SbEcomApplication.main()" by right-clicking on it.
   

### Ejecutar el proyecto desde la línea de comandos / Running the Project from the Command Line

1. **Compilar el proyecto // Build the Project**
   - Ejecuta el siguiente comando para compilar y empaquetar el proyecto: / Run the following command to compile and package the project:
   ```bash
   mvn clean package
   ```

2. **Ejecutar el proyecto con Spring Boot / Run the Project with Spring Boot**
   - Inicia la aplicación usando el siguiente comando: / Start the application using the following command:
   ```bash
   mvn spring-boot:run
   ```


### Una vez iniciada la aplicación, acceder a http://localhost:8080/swagger-ui/index.html para probar los endpoints.
### Once the application has started, access http://localhost:8080/swagger-ui/index.html to test the endpoints.