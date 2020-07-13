# DynamoDB CRUD operation using AWS serverless Lambda and Node js
CRUD operations using AWS lambda with DynamoDB and Node js. 

I created this API using AWS serverless application and Node js. You must create a AWS account before deploying functions

# DynamoDB functionalities
  1. Added GSI and LSI and used it for searching 
  2. Added "HASH" and "RANGE" keys for keytypes for partition the table
  
# Hosting node js API in AWS serverless lambda
useful commands to start a AWS API lambda project and deployement

(01). For npm command you have to install node.js on windows
	    https://nodejs.org/en/
	
(02). For serverless installation
	    
      npm install serverless --force -g

(03). Create a folder and move into it

	    mkdir test
	    cd test  
      
 or
      
      mkdir "folder name" && cd "folder name"
	
(04). Create a serverless project using a template( you can use the key sls instead of serverless and template instead of -t)
	    
      serverless create -t aws-nodejs 
	
(05). Open the project using visual studio code
	    
      code .
	
(06). Create a packagejs module
	    
      npm init -t

(07). Install module of A universally unique identifier (UUID)
	    
      npm install uuid
	
(08). Deploy the project
	    
      slss deploy

(09). Some times you have to provide the AWS accesskey and  secret key before deploying the project

	    serverless config credentials --provider aws --key AKIA4FLNV7SDQKdfOWEMY3 --secret u+GHe+cs3d0gdf08NEDipa/3Pg2RhVhK+fB/Mr9F 



  
