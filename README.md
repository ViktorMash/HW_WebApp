# HW_WebApp
### Task description

To develop such web application:
The system which can reserve some resources (it can be computing resources, rooms or whatever) for a user if he or she has a right permissions for a such resource.
There are such entities:
1. Users, can belong to groups
2. Group, can contain users
3. Resource, should have its description, schedule and capacity
4. Permissions, list of allowed actions for resources, should be applied to a user or a group to allow an action on the resource

The db structure should be designed by the candidate
The api endpoints structure should be designed by the candidate
Db and framework on the choice of the candidate
The app should be containerized, with a dockerfile provided
The auth system should be provided, approach on the candidate, any of them, but should be explained and compared with other approaches on the interview
Frontend is not required, can be any method to demonstrate the work (templates usage, curl, postman, any custom frontend)

Topics to discuss on the interview:
Code style, project structure, used patterns and design principles
The db scheme, pros and cons, scalability
The api structure, what can be improved in case of many users, possibilities, pros and cons of microservices approach in case of the system grown, other ideas
Cloud deployment possibilities
Optional:
1. No sql dbs usage in the app, pros and cons
2. Migrations and releases strategy
