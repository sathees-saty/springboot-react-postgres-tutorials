# springboot-react-postgres-tutorials
<html>
  Download github code
  <br>
  Created new DB “testdb” in postgres 
  <br>
  import Springboot project as Maven project
  <br>
  Verify pom.xml dependencies
  <br>
  Important: in Springboot controller add @CrossOrigin 
  <br>
The @CrossOrigin annotation is a savior in such scenarios. At its core, it provides a way to overcome the same-origin policy applied by web browsers. This annotation indicates that a specific controller method, or all methods within a controller class, can be invoked by JavaScript code from a different origin. Then only API will be exposed to React.js.
<br>
update postgres connetion details in application.properties
<br>
    Run the Springboot application and test the services in postman
  <br>
  <br>
  GET: http://localhost:8080/api/tutorials
  <br>
  GET: http://localhost:8080/api/tutorials/1
  <br>
  PUT: (update) http://localhost:8080/api/tutorials/1
  <br>
  POST (insert) : http://localhost:8080/api/tutorials
  <br>
  DELETE: http://localhost:8080/api/tutorials/1
  <br>
</html>
