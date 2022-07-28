## Pipeline Process

#### 1- First i create Database in AWS RDS and store the parameter in .env file.

#### 2- Link the local application to Github Through pushing it.

#### 3- Make connection between circleCLI with Github.

#### 4- After That Pass all the enviromet variable to the enviorment variable CircleCi

#### 5- create the circlecli in the main directory of the full project.

#### 6- If the repo has been changed then Circlecli starts the CI then deployment to AWS.

#### 7- First Installing all the dependencies that's need to deploy the application in both front and back end seperately.

#### 8- Then starting the deployment of backend in the elasticbeanstalk.

#### -9 IF the previous is successful then deployment of the frontend will take place.

#### 10- IF there is any error in Pipeline in CircleCi the process stoped and also the deployment will not happen.
