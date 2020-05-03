Add below plugin in pom.xml

  <plugin> 
        <groupId>com.microsoft.azure</groupId>  
        <artifactId>azure-webapp-maven-plugin</artifactId>  
        <version>1.7.0</version>  
  </plugin> 
  
  
  mvn azure-webapp:configure
  
  mvn azure-webapp:deploy

Hello World Rest API running on port 8080
Run cocom.rahul.demo.firstazuredemo.FirstAzureDemoApplication as a Java Application.

http://localhost:8080/hello-world
Hello World

http://localhost:5000/hello-world/Rahul
Hello World Rahul


