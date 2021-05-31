# Wizeline_Challenge2
Wizeline Academy - Challenge 2: Back End Test automation using Postman and Newman

**Required Libraries**

Dependencies:
  - newman
  - newman-reporter-htmlextra

To install all the dependencies open a terminal in the project folder and run:
  
    npm install
    
 
**Run Project**

To be able to execute the project successfully it is required to send by parameter to the script the access token.

    access_token='EAAAELxLPGQlZK3GLH1pwZawY0oGgvpFpZ56SqFM7ArUmnJLgm9RcN9yhBHGYnbQ'

To run the project use the npm run command:

    npm run backend-test-all -- access_token='EAAAELxLPGQlZK3GLH1pwZawY0oGgvpFpZ56SqFM7ArUmnJLgm9RcN9yhBHGYnbQ'
    
        
**Test Execution Reports**

The execution will create an HTML report in folder ./reports
  - backend-test-all will generate:
  
        Square_Payments_API-{timestamp}.html
