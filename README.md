# Node.js_App

#Live Application URL

The Application is deployed in https://github.com/sriker1225/Node.js_App

Click on the link to see the application

# Cloning and Running the Application in local

Clone the project into local

Install all the npm packages. Go into the project folder and type the following command to install all npm packages : 
npm install

In order to run the application Type the following command : 
npm start

The Application Runs on localhost:8000


End Point V1:

Post: http://localhost:8000/api/v1/parse

Input:

{
    "data":"JOHN0000MICHAEL0009994567"
}

Output:

{
    "statusCode": 200,
    "data": {
        "firstName": "JOHN0000",
        "lastName": "MICHAEL000",
        "clientId": "9994567"
    }
}

End Point V2:

Post: http://localhost:8000/api/v2/parse

Input:

{
    "data":"JOHN0000MICHAEL0009994567"
}

Output:

{
    "statusCode": 200,
    "data": {
        "firstName": "JOHN",
        "lastName": "MICHAEL",
        "clientId": "999-4567"
    }
}

