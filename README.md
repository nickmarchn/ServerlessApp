# ServerlessApp
This is a serverless app project I built using the materials I got from a aws course from https://learn.cantrill.io/.
I built this out before taking my aws solutions architect certification so I could get hands on experience.
I did run into one issue along the way - wrong order of files in s3 bucket. My root folder was not in the highest level of hierarcy causing issues on my state website. 


Here are the steps I followed:
- STAGE 1 : Configure Simple Email service & SNS
- STAGE 2 : Add a email lambda function to use SES to send emails for the serverless application
- STAGE 3 : Implement and configure the state machine, the core of the application
- STAGE 4 : Implement the API Gateway, API and supporting lambda function
- STAGE 5 : Implement the static frontend application and test functionality
- STAGE 6 : Cleanup the account
