# Java-api-product-customer-manger
Application is build based on the microservices architecture. There are several advantages in building an application using Microservices architecture like Services can be developed, deployed and scaled independently. • Identity Microservice - Authenticates user based on username, password and issues a JWT Bearer token which contains Claims-based identity information in it. • Product Microservice – Perform Product related data operations. • Customer Microservice - Perform Customer related data operations. • API Gateway - Acts as a center point of entry to the back-end application, Provides data aggregation and communication path to microservices.


WebApi Endpoints

The application has four API endpoints configured in the API Gateway to demonstrate the features with token based security options enabled. These routes are exposed to the client app to consume the back-end services.
End-points configured and accessible through API Gateway
1.	Route: "/user/authenticate" [HttpPost] - To authenticate user and issue a token
2.	Route: "/Products" [HttpGet] - To retrieve products information.
3.	Route: "/Customers" [HttpGet] - To retrieve customers information.
End-points implemented at the Microservice level
1.	Route: "/api/user/authenticate" [HttpPost]- To authenticate user and issue a token
2.	Route: "/api/Products" [HttpGet] - To retrieve products information.
3.	Route: "/api/Customers" [HttpGet] - To retrieve customers information.`


## Architecture:`
![``Screenshot from 2020-11-22 09-59-11](https://user-images.githubusercontent.com/31319842/99893389-be602800-2ca9-11eb-951f-639c42520d23.png)

## Authorization Service

![1](https://user-images.githubusercontent.com/31319842/99893591-9d003b80-2cab-11eb-9f06-1d5a785c775b.png)