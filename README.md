# lambda-login-service
A simple login service that uses AWS lambda and DynamoDB.

Link : - https://aws.plainenglish.io/build-a-serverless-login-service-using-aws-dynamodb-and-lambda-ce7d68248743

Postman collection for Testing : - {"info":{"_postman_id":"cff83d2b-849a-4cc2-ba3b-4bf53d7772ee","name":"DynamoDB Login Service Collection","schema":"https://schema.getpostman.com/json/collection/v2.0.0/collection.json"},"item":[{"name":"Verify Token","id":"0bf7218a-57cf-4ff6-8c1d-8a77e06eaed6","request":{"method":"POST","header":[],"body":{"mode":"raw","raw":"{\n  \"username\":\"nabil13@gmail.com\",\n   \"token\": \"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6Im5hYmlsMTNAZ21haWwuY29tIiwibmFtZSI6Ik5hYmlsIE5hbGFrYXRoIiwiaWF0IjoxNjU0MTgyOTUxLCJleHAiOjE2NTQxODY1NTF9.g4-XGlx7nPIfLRy-eOCI5aRYohI0JNycIZhpeJxkANs\"\n\n}","options":{"raw":{"language":"json"}}},"url":"https://pl7kzxgsmi.execute-api.us-east-1.amazonaws.com/dev/verify"},"response":[]},{"name":"Login User","id":"aa5b119b-5ce3-46ba-8b27-922b39553bc9","request":{"method":"POST","header":[],"body":{"mode":"raw","raw":"{\n  \"username\":\"nabil13@gmail.com\",\n   \"token\": \"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6Im5hYmlsMTNAZ21haWwuY29tIiwibmFtZSI6Ik5hYmlsIE5hbGFrYXRoIiwiaWF0IjoxNjU0MTgyOTUxLCJleHAiOjE2NTQxODY1NTF9.g4-XGlx7nPIfLRy-eOCI5aRYohI0JNycIZhpeJxkANs\"\n\n}","options":{"raw":{"language":"json"}}},"url":"https://pl7kzxgsmi.execute-api.us-east-1.amazonaws.com/dev/login"},"response":[]},{"name":"Register User","id":"18abf5b0-1364-4ec1-beb4-5f95281bfc03","request":{"method":"POST","header":[],"body":{"mode":"raw","raw":"{\n  \"name\":\"nabil nalakath\",\n  \"username\":\"nabil@medium.com\",\n  \"password\":\"password\"\n}","options":{"raw":{"language":"json"}}},"url":"https://pl7kzxgsmi.execute-api.us-east-1.amazonaws.com/dev/register"},"response":[]}],"variable":[{"id":"65ffd761-8e83-45f1-8c1c-1dff23b511f7","key":"login-service-url","value":"https://pl7kzxgsmi.execute-api.us-east-1.amazonaws.com"}]}
