# [Food Runners]() Application

Here is a microservices demo application, based on a food delivery startup called `Food Runners`. 
This is designed as a web-based application where users can search for resurants, order foods, make payments and, also rate the quality of the food as well as the delivery service. . 

## Architecture 

![Screenshot 2023-03-08 at 10 46 13](https://user-images.githubusercontent.com/29032600/223626067-7cf21481-bf9c-49d7-92e0-6aaf6dba92da.png)

The new system consists of the following microservices:
- Order service: Receives orders from customers and validates them against menu and pricing data.
- Payment service: Handles payments, refunds, and chargebacks.
- Restaurant service: Manages restaurant data and provides real-time updates on menu items and availability.
- Delivery service: Calculates delivery routes and manages the delivery of orders.
- Notification service: Sends notifications to customers about the status of their orders.
- Rating Service: Allows customers to rate the quality of the food and the delivery service. 

