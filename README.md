Online Food Ordering System (OFOS) - README
1. Admin and User Credentials
To test and access various features of the Online Food Ordering System (OFOS), the following credentials can be used:

Normal User:
Username: dwid
Password: 12345
Admin User:
Username: edres
Password: 12345
2. Summary of Setup & Configuration
Step 1: Installation
Ensure that you have a web server installed, such as IIS (Internet Information Services) for Windows or any other compatible server. Ensure that ASP.NET and SQL Server are installed and properly configured. Download the OFOS project files and place them in your web server's root directory.

Step 2: Database Configuration
Open the SQL Server Management Studio. Attach the provided ofos.mdf database file to your SQL Server instance. Ensure the connection string in the web.config file points to the correct database location.

Step 3: Configuring the Application
Open the project in a suitable IDE, such as Visual Studio. Check the web.config file to ensure all the necessary settings, such as connection strings and application settings, are correct. Build the project to ensure there are no errors. Deploy the application to your web server.

Step 4: Running the Application
Once deployed, navigate to the application URL in a web browser. Log in using the provided credentials to test the application.
