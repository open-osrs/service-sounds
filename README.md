# service-sounds
Works as a database you can read / write NPC sounds to  
  
# Setup  
  
Import the project using gradle.  
After gradle finishes init:  
  
simply launch service.SpringBootWebApplication  
OR  
use the shadowJar gradle task, and you can use build/libs/-all jar to launch using the java -jar command, no tomcat.  
  
The following endpoints exist:  
http://localhost:8083/sounds/submit : Submits a sound to the database  
http://localhost:8083/sounds/get : Returns all currently collected sounds   
