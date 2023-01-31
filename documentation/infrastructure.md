# AWS Services

## 1- AWS RDS

-Used to host the postgres database<br>
-Save or return the data given or needed by the API<br>

## 2- AWS Elastic Beanstalk

-Used to host the node application ( API )<br>
-Take requests from the frontend application and deal with it<br>
-Can communicate with the database to retrieve the data<br>
-Response with the proper data and status code to the frontend application<br>

## 3- AWS S3 Bucket

-Used to host the frontend application<br>
-The website that the user will interact with<br>
-Will be used to send requests to the API and getting response back<br>

## Circle Ci

-Used with the Github repo to trigger any change in the main branch<br>
-After any change in the repo it will start a workflow shown in Pipeline process<br>
-Main usage for it is building, testing, and deploying the project using automation.<br>
