# Build & Deploy a Production-Ready Patient Management System with Microservices: Java Spring Boot AWS

## Dev setup
1. Install Java
   - Visit : https://www.oracle.com/java/technologies/downloads/#jdk21-windows
   - Download x64 MSI Installer
   - Install it
  
2. Install Docker
   - Visit : https://docs.docker.com/desktop/setup/install/windows-install/
   - Download Docker Desktop for Windows - x86_64
   - Install it

3. Install Jetbrains
   - Visit : https://www.jetbrains.com/idea/download/?section=windows
   - Download Jetbrains for Windows
   - Install the IDE
   - Open the IDE
   - Start the free trial


## Springboot 

### Architecture
- Frontend (<--> response | request)
- Controller (<--> dto)
- Service (<--> model)
- Repository (<--> query)
- DB

### Concepts
1. DTOs

## Project setup
1. Create a new Empty project
2. Inside the project create new module : Spring boot (type maven)
3. Select needed dependencies (Spring web, Spring boot devtools, Spring data jpa, PostgreSql driver, Validation)
4. Inside the module com.pm.patientservice create new package : model
5. In the model package create new java class : Patient
6. Add all the necessary (packages & fields) to make a Patient Model
7. Start the app and in the browser access localhost:4000/h2-console, fill the rigth params and creds and see the table

## data-setup
1. Copy data.sql from the repo
2. Add it to the project 
3. Login to /h2-console
4. See the data inside the Patient table