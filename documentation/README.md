## to deploy the the backend ( udagarm-api )

1. create a database using aws rds ,, insure that you make it public
2. build udagram-api project ,, it will create Archive.zip inside www folder
3. create elastic beanstalk to deploy the backend ( node.js api )
4. upload Archive.Zip during you create elastic beanstalk
4. configure environment variables to elastic beanstalk

## to deploy the the frontend ( udagarm-frontend )

1. use aws s3 to create a bucket to deploy the frontend  
2. enable static files 
3. set permissions 
4. change the apiHost inside environment.ts to elastic beanstalk url
5. build your code
6. upload the code inside www folder to s3 bucket

## the url of deployed project
http://udagram-app-api-backend.s3-website-us-east-1.amazonaws.com/

## Githup Repo
https://github.com/daliaAhmedElsherpini/udagram.git