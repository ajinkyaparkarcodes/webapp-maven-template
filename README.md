
# Simple Maven Web Application

This is a minimal Java web application project generated using Maven. It uses the standard `maven-archetype-webapp` and is ready for deployment on servlet containers like Apache Tomcat.

## 🔧 Project Setup

This project was created using the following Maven archetype:

```bash
mvn archetype:generate -DgroupId=com.example -DartifactId=simple-maven-webapp -DarchetypeArtifactId=maven-archetype-webapp -DinteractiveMode=false
```

## 📦 Build & Compile

To build the project, use the following Maven commands:

```bash
mvn clean           # Cleans previous build artifacts
mvn compile         # Compiles Java source code
mvn package         # Packages code into a WAR file
```

After running these, the WAR file will be available in the `target/` directory.

## 🚀 Deploy

To run the app:
1. Copy the `target/simple-maven-webapp.war` to your Tomcat `webapps/` folder.
2. Start Tomcat.
3. Visit: [http://localhost:8080/simple-maven-webapp](http://localhost:8080/simple-maven-webapp)

