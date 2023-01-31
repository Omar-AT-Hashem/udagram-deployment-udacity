# Pipeline Process

## With the help of Circle Ci we can automate the building, testing and deploying phases for our application

### Steps

--Developer update the code localy [ add new feature, fix a bug, ...etc ]<br>
--Push the changes to the github repo<br>
--Circle Ci will trigger this changes and will start the pipeline<br>
-Install Node<br>
-Install AWS Elastic Beanstalk<br>
-Install AWS CLI<br>
-install Front-End Dependencies<br>
-Install API Dependencies<br>
-Build Front-End<br>
-Build API<br>
--Wait for the user's approval to deploy the application<br>
-Update API code in Elastic Beanstalk ( Deploy The API )<br>
-Update Front-End code in S3 Bucket ( Deploy The Front-End )<br>
