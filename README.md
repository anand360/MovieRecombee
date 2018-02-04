# MovieRecombee
Movie recommendation app using Recombee API

This app code folder is password protected due to its nature of app. If you would like to access this project code, kindly drop an email to anandkishore31@gmail.com

Angular : 5.2.0

Angular Material : 5.1.1

Node: 8.9.3

Step to run this project:
1. Install Visual studio code
2. Open this project using Visual studio code.
3. First step: IF you want to use your own Recombee API:

    a. Create an account at https://docs.recombee.com/
    
    b. Copy the db name and secretKey.
    
    c. Open the app.config.js file in Project folder (config/app.config.js)
    
    d. Replace the dbname and secret key with your own Recombee account.
    
4. If you want to load the User, Movie and rating data to Recombee Db:

    a. Go to Project folder and open server.js file
    
    b. Uncomment the lines 26-28
    
    c. Run the command : node server.js
    
5. This app is built using Angular 5 with Material Design as Front end.
6. Once Data is uploaded to Recombee DB: To Build and run the application: hit the command => npm start
