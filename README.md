# springboot-react-postgres-tutorials
<html>
  <h1>
Architecture of Spring Boot React CRUD example
  </h1>
  <br>
  <img src="https://github.com/sathees-saty/springboot-react-postgres-tutorials/assets/65384711/0da60ebb-6eec-4beb-a3a3-21a1bec9776d" alt="Architecture" width="1000" height="1000">
  <br>
  Download github code
  <br>
  <h1>Backend</h1>
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
<h1>Frontend</h1>
  <br>
cd D:\react-development\react-springboot-postgres\react-crud
<br>
  Run below commands to setup front end
<br>
  in root folder D:\react-development\react-springboot-postgres\
  <br>
  node -v
    <br>
npx create-react-app react-crud
  <br>
cd react-crud
    <br>
npm install axios
    <br>
npm install react-router-dom
    <br>
npm install bootstrap@4
  <br>
Update App.js and other files as required
  <br>
  run front end application using npm start
  <br>
  http://localhost:3000/tutorials
  <br>
  <img src="https://github.com/sathees-saty/springboot-react-postgres-tutorials/assets/65384711/47ec8e38-2c81-49c0-9940-8e8832c46fe6" alt="Tutorials" width="1000" height="1000">
  <br>
  
</html>
