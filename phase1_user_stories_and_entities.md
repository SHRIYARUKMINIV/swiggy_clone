User Stories
Customer
•	As a customer, I want to register and log in via email, phone, or social media so that I can access and place orders easily.
•	As a customer, I want to browse and filter restaurants so that I can find food that suits my taste and location.
•	As a customer, I want to place, modify, or cancel food orders so that I have flexibility and control over my order.
•	As a customer, I want to track my delivery in real time so that I know when my food will arrive.
•	As a customer, I want to make payments using my preferred method so that the transaction is convenient.
•	As a customer, I want to access chat or call support so that my issues or complaints are quickly resolved.
•	As a customer, I want to give feedback and ratings so that I can share my experience and improve service quality.
Restaurant
•	As a restaurant, I want to manage my menu, pricing, and availability so that customers see accurate and current offerings.
•	As a restaurant, I want to process orders and update their status so that customers are informed in real-time.
•	As a restaurant, I want to access dashboards and analytics so that I can track performance and make informed decisions.
•	As a restaurant, I want to run promotions or offers so that I can attract more customers.
Delivery Partner
•	As a delivery partner, I want to receive and accept delivery assignments automatically so that I can efficiently fulfill orders.
•	As a delivery partner, I want to track delivery routes and update status so that customers stay informed.
•	As a delivery partner, I want to confirm successful deliveries so that the process is completed and recorded.
Platform Administrator
•	As a platform administrator, I want to manage users, restaurants, and delivery partners so that the platform runs smoothly.
•	As a platform administrator, I want to monitor issues and handle complaints so that service quality is maintained.
•	As a platform administrator, I want to ensure secure transactions and platform reliability so that users trust the system.
________________________________________
Entities
1.	Customer
2.	Restaurant
3.	Menu Item
4.	Order
5.	Delivery Partner
6.	Payment
7.	Platform Administrator
8.	Feedback
9.	Support Ticket
________________________________________
Entity Relationships
Entity 1	Relationship Type	Entity 2	Description
Customer	One-to-Many	Order	A customer can place multiple orders.
Restaurant	One-to-Many	Menu Item	A restaurant can have multiple menu items.
Restaurant	One-to-Many	Order	A restaurant can receive multiple orders.
Order	One-to-One	Payment	Each order has a single payment associated.
Order	One-to-One	Delivery Partner	Each order is assigned to one delivery partner.
Customer	One-to-Many	Feedback	A customer can submit multiple feedback entries.
Customer	One-to-Many	Support Ticket	A customer can raise multiple support tickets.
Platform Admin	One-to-Many	Support Ticket	Admin manages many support tickets.
Delivery Partner	One-to-Many	Order	A delivery partner can deliver multiple orders over time.
________________________________________

