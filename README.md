# assignment

I used Postman for this test. From chai js framework in JavaScript. Which has 3 files
1. Includes json file
2. environment variables file
3. HTML report dashboard

You can use Docker,Postman and cli to run the tests 
1. docker: https://learning.postman.com/docs/running-collections/using-newman-cli/newman-with-docker/
2. cli  : https://www.npmjs.com/package/newman

Using Newman CLI : 
newman run Tests/assignment.postman_collection.json -e Tests/assignment.postman_environment.json -r cli,htmlextra
newman

Report Example :

https://www.npmjs.com/package/newman-reporter-htmlextra



