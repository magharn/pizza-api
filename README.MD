Pizza App

Objetive: Create a Web and a mobile app using a serverless tool


This app was built using the following technologies:

* Node.js
* Claudia.js
* Amazon AWS

Directions:
For the first time execute the following command:
> claudia create --region [AMAZON-REGION] --module-api api

For updates run the following command:
> claudia update

Testing API:
  
  Issue the following commands to test: create order scenario.
  curl -i -H "Content-Type: application/json" -X POST -d '{}' https://jtnlajadbi.execute-api.us-west-2.amazonaws.com/latest/orders
  
  curl -i -H "Content-Type: application/json" -X POST -d '{}' https://jtnlajadbi.execute-api.us-west-2.amazonaws.com/latest/orders


References: 

Visit the following link to install Claudia.js
https://claudiajs.com/tutorials/installing.html

You can see all the available regions in the official  AWS documentation
http://docs.aws.amazon.com/general/latest/gr/rande.html#lambda_region