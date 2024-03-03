Instructions to Run:

1) Install Node JS, PostgreSQL.
    1.1) Download and install Node.js from the official website.
    1.2) Download and install PostgreSQL from the official website. You can follow the instructions on this webpage for installation and configuration of PostgreSQL. 
         [https://www.postgresqltutorial.com/postgresql-getting-started/install-postgresql/]
    1.3) Open PostgreSQL and create a database, and tables using the SQL scripts (Q1) provided in this folder.

2) Download and UnZip this Folder.
    2.1) You can download the folder from the GitHub repository.
    2.2) Use any archive tool to unzip the folder.

3) Open Terminal in Zithara Folder (In any Editor like VS code).
    3.1) Open the folder in your preferred code editor (like Visual Studio Code).
    3.2) Open the terminal or command prompt in the editor.

4) Install the necessary Node.js packages.
    4.1) Run the command "npm i" to install the packages listed in the package.json file.
    4.2) Run the command "npm install express pg" to install Express.js and pg (node-postgres).

5) Navigate to the client directory.
    5.1) Run the command "cd client".

6) Install the necessary client-side packages.
    6.1) Run the command "npm i" to install the packages listed in the package.json file.
    6.2) Run the command "npm install axios react-table" to install axios and react-table.
    6.3) Open server.js file and change the user, host, database, password, port to match your PostgreSQL configuration.

7) For Execution:
    7.1) Open two terminals in VS Code, one in the home (Zithara) folder (where server.js exists), another in the client folder.
    7.2) In the home folder terminal, run "node server.js". This will start the server. Keep this terminal running. You can check if server is connfigured successfully by going to url 
        "http://localhost:8000/customers" after running node server.js. If you see data then server is working correctly.
    7.3) In the client folder terminal, run "npm start". This will start the client-side application. It should automatically open a webpage in your default browser. If not, open a browser and 
         type: "http://localhost:3000".

8) To stop the running of application. Press CTRL+C in both client and home terminals.




Note: If you face any errors during the installation or execution process, carefully read the error message. It may indicate that you need to install additional packages or there might be an issue with the versions of the installed packages. Try to rectify these issues based on the error messages. If you're still facing issues, you may need to look up the error online or ask for help in relevant online communities.
