### DMoney-API-Testing-Newman
Automated dmoney API using Postman where test cases are added for Login, Creating users, Searching users and performed testing for CRUD operations.
 Steps to run this project:.
 - Give the following commands by opening terminal in the project folder to create newman Report:
 ```
 npm i newman
 ```
 ```
 npx newman run .\collection\DmoneyUsers.json
```
```
npm i newman-reporter-htmlextra
```
```
node .\report.js
```
 - Read the project [Documentation](https://documenter.getpostman.com/view/21091753/2s93CHuEyq).

#### Screenshot of the report generated using newman

![report using Newman](https://user-images.githubusercontent.com/59876702/222578207-f6f954da-1780-4bfb-8bd1-009e5835e4b9.PNG)
