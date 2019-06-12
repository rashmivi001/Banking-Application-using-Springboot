Steps to execute the project

1.Download OnlineBanking System.zip file
2.Import demo folder into STS
3.Go to demo->src/main/resources/ -> application.properties and change the Database username and password with your details
4.Import OnlineBankingAppDump - G1801881J into your MySQL and ensure all the tables are loaded properly
5.Create Mydb database in MySQL workbench
6.Now,update the imported project(demo) -> Right click on the project ->Maven -> Update project
7.Run the demo project by right clicking on the project -> Run as SpringBoot App
8.After successful build, Click Window -> Show View -> Other ->Boot Dashboard
9.In the Boot Dashboard, double click on the project(Demo) and the application will be launched
10.Alteratively, You can run the URL - http://localhost:8080/ in the browser


Please Find the jar file named in the zipped folder-> Sample-0.0.1-SNAPSHOT

1.Open the command prompt and run with java -jar Sample-0.0.1-SNAPSHOT.jar
2.Open the browser and type the URL - http://localhost:8080/
3.Register a new user and continue with login and other operations
4.For Admin Login 
	- username : admin
	- password - test