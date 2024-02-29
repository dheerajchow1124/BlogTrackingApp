Procedure: 
Step 1 -: Create admininfo.cs, Empinfo.cs and Bloginfo.cs in Blog lib.  
Step 2 -: Create Asp.net core Web API in VS 2022 and Download required Dependencies. Step 3 -: Use Scaffold-DbContext to connect your DB to our project, it will automatically  create models and its DbContext file . 
Step 4 -: Run and Check if all the CRUD operations are operational in the swagger  
Step 5 -: Now Create a New Asp.Net Mvc project in the same solution explorer.  
Step 6 -: Create the controllers for admin, emp, blog and login in mvc. 
Step 7-: Enable both projects to run at the same time when the build is entered.  
Step 8 -: Create the models same as models in the Web Api 
Step 9 -: In controllers, using HTTP Client request connect the Web Api data to our MVC  
Project for CRUD operations  
Step 10 -: Create Views for the respective fields  
Step 11 -: In Shared layout, change the layout for our requirements  
Step 12 -: Assign login and logout in the _layout view  
Step 13 : And add nunit testing and add lib reference to test and perform nunit operations. 
Step 14 : Build and Run the program  
Step 15 : Check if all the functions works perfectly.  
Step16 : Publish and run the docker by using necessary commands. 
Step 17 : If all runs perfectly, then close the program.  
