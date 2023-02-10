# Automatizaci-n-UI-ecommerce-con-Selenium-Java
Automatización de UI con Java, Selenium Web Driver, POM, Gradle, Cucumber y Maven/Groovy
Este readme tiene como objetivo mostrarte cómo automatizar pruebas de interfaz de usuario (UI) utilizando Java, Selenium Web Driver, POM, Gradle/Maven y Cucumber, y cómo configurar y ejecutar estas pruebas.

Prerrequisitos
Conocimientos básicos de Java
Conocimientos básicos de programación de pruebas automatizadas
Conocimientos básicos de Selenium WebDriver
Gradle o Maven instalados en tu sistema
Conocimientos básicos de Cucumber
Configuración del entorno de desarrollo
Crea un nuevo proyecto de Gradle o Maven
Agrega las siguientes dependencias en tu archivo build.gradle (Gradle) o pom.xml (Maven):
Gradle:

csharp
Copy code
dependencies {
    testCompile group: 'junit', name: 'junit', version: '4.12'
    testCompile group: 'org.seleniumhq.selenium', name: 'selenium-java', version: '3.141.59'
    testCompile group: 'info.cukes', name: 'cucumber-java', version: '1.2.5'
    testCompile group: 'info.cukes', name: 'cucumber-junit', version: '1.2.5'
}
Maven:

php
Copy code
<dependencies>
    <dependency>
        <groupId>junit</groupId>
        <artifactId>junit</artifactId>
        <version>4.12</version>
        <scope>test</scope>
    </dependency>
    <dependency>
        <groupId>org.seleniumhq.selenium</groupId>
        <artifactId>selenium-java</artifactId>
        <version>3.141.59</version>
        <scope>test</scope>
    </dependency>
    <dependency>
        <groupId>info.cukes</groupId>
        <artifactId>cucumber-java</artifactId>
        <version>1.2.5</version>
        <scope>test</scope>
    </dependency>
    <dependency>
        <groupId>info.cukes</groupId>
        <artifactId>cucumber-junit</artifactId>
        <version>1.2.5</version>
        <scope>test</scope>
    </dependency>
</dependencies>
