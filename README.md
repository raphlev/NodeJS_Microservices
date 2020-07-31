# Node.js: Microservices
https://www.linkedin.com/learning/node-js-microservices

How to decompose an app with microservice

Install nodejs latest LTS
VSC with eslint plugin
postman

CH01 Get started with Microservices - Monolith app
CH02 Creating a Service Registry
- Seting up the registry
- Setting up endpoints in Express
- Registering and deregistering services
- Creating and testing the registration route
- Unregistering services
- Versioning and load balancing
- Quering the registry
- Removing expired services
CH03 Splitting up Monolith into Microservices app
- Setting up the speakers service
- Registering the speakers service
- Unregistering a servicce on shutdown
- Adding the service logic
- Using the microservice from the main app
- Cleaning up the main app
- Creating an image serving endpoint
CH04 Adding Fault Tolerance And Resilience
- What happens if a service fails
- Understanding circuit breakers
- Building a circuit breaker with Node
- Using the circuit breaker
- Using a cache to bridge outages
- Caching images
CH05 Using Queues with Node.js
- Factoring out the feedback services
- Using queues
- Setting up RabbitMQ
- Queuing feedback
- Consuming and storing feedback


How to start app:
Terminal 1:
cd .\conference-app\
npm install
npm start
Terminal 2:
cd .\service-registry\
npm install
npm start
Terminal 3:
cd .\speakers-service\
npm install
npm start