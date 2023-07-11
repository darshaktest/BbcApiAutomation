<h1> Code-Assessment-for-BBC </h1>
<h2>Behavior Driven Development Cucumber - API automation framework </h2>

 Used tools and frameworks
---------------------------------------
1. Rest-Assured
2. Maven repository 
3. Cucumber

Main features
----------------------------
1. BDD framework to test API automation.
2. Supports both REST and SOAP webservices testing. 
3. All classes and methods are implemented in Java with Maven repository to include all dependencies needed.
4. REST-Assured is used to offer a friendly DSL (Domain specific Languages) that describes a connection to an HTTP endpoint and expected results.
5. The predefined schema in that format:
[Description], [URL], [Request method: GET, POST, ...], [Headers keys], [Headers values], [Body(if needed)], [Expected status code], [Assertions]
7. REST-Assured Java API is to test REST webservices and has no direct support for SOAP webservices. However, REST-Assured can test SOAP webservices by adding xml request in the body and execute POST HTTP request.
8. The framework validates the returned status code, response body, headers and cookies. It can validate each field data type and value. If the returned response includes object of arraylist, the framework can validate its size using the keyword ".size()"
9. Can be integrated into DevOps environment to accelerate the delivery process. After each Jenkins deployment, test cases can be executed automatically and the generated XML reports can be passed to Jira to log Defects/Tests automatically. Some configurations needed in Jenkins side.
10. Solves the complexity of testing correlated APIs as any test step can use data (body value, header or cookie).


<h2>This framework contains sample code containing:</h2>
	<ul><li>1 Feature File (Scenario file)</li></ul>
	<ul><li>2 StepDifinition File </li></ul>
  <ul><li>3 TestRunner File </li></ul>
	<ul><li>Simple scenario fetching API through GET request via URL </li>
	<li>Advance scenario where parameterization has been used to fetch the data from URL and Validate the JSON request</li></ul>


 <h2>Steps to run at your system:</h2>
	<ul>
	<li>Clone the repository using "git clone <repository url>"</li>
	<li>Import project from the Clone location in local IDE by clicking on " POM.xml file "</li>
	<li>RUN Maven clean </li>
  <li>RUN Maven Install OR also run directly by Test runner file </li>
	</ul>

# Objectives:
- Perforum CRUD operation 
- Fetch JSON request through URL (GET request)
- It Can Create (POST) the new request
- It Can edit (PUT) the existing request
- Can Delete the request
- Validate JSON status code and responce time 
- Should Support Each and Every platforms.
- can be Executed within the local IDE.
