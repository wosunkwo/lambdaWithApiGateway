# lambdaWithApiGateway

## Description of application:
This application use Lambda to expose our repeated-word-in-sentence functionality to the world!

## Screenshot of the app:
![alt_text](https://github.com/wosunkwo/lambdaWithApiGateway/blob/master/assests/Screen%20Shot%202019-07-11%20at%2011.50.23%20AM.png)

## How to invoke the API
your query parameter must be = "sentence" i.e. https://iv7qth009d.execute-api.us-east-2.amazonaws.com/repeatedWord?sentence=hi this is a hi sentence that i am testing

should return "hi" as the first repeated word in the sentence 

## Link to the deployed site: 
[Deployed API] (https://iv7qth009d.execute-api.us-east-2.amazonaws.com/repeatedWord)



## Feature Tasks

> A user should be able to find the first repeated word in a sentence by visiting a URL.

> That URL should use API Gateway to call a Lambda function that finds the first repeated word in a sentence.
You should use a query string parameter to pass in the sentence data.

## Code 
> [Code](https://github.com/wosunkwo/lambdaWithApiGateway/blob/master/src/main/java/lambdaWithApiGateway/Library.java)
