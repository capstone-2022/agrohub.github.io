---

# What is our mission?
Our goal is to allow individual farmers and small organizations to grow
economically and scale as much as they can by selling their products via 
the Internet. In addition, we'd like to provide the community of Puerto Rico 
quality agricultural products.

# Current Situation
Individual Farmers can only sell at certain times, since agricultural products
require high maintenance. Also, supermarkets and other chains require a high
production-rate that individual Farmers cannot meet. Based this, a new strategy
is rising, in which a group of Farmers act as a single entity or **Organization** 
with resources like storage, refrigeration, maintenance, etc. and *buy* the products
from other individual Farmers in order to redistribute. However, the
redistribution process requires tons of effort. 

Here are some scenarios that these Organizations face that slow down the
redistribution process:

1. Determining how much a single Farmer sold is done manually by the
   **Administrator** of the Organization, a tedious process that is necessary to
   get right.

2. Scaling for more customers requires the constant use of social media apps and
   other communication services, which are time-consuming.

3. Updating the inventory is done manually by posting on social medias or other
   services like Google Forms.

# Solution Approach
Our solution is to help in this distribution process by satisfying 3 types of
users: Organizations, Farmers, and Customers.

- We should provide Organizations the following *features*:
  - Contact other individual Farmers
  - Post their products for selling
  - Automated processes for:
    - inventory 
    - individual farmer earnings
    - transactions
- We should provide Farmers the following *features*:
  - Contact Organizations
  - Keep track of their products
  - Keep track of their earnings
- We should allow Customers to:
  - Buy products
  - View products
  - Contact Organizations and/or Farmers

# Technical Description
Tech-Stack:
- ReactJS
- Spring Boot
- PostgreSQL
- Heroku

## Frontend
We use the ReactJS Framework in order to provide the Client interface for our
users. The following diagram explains the architecture for the Frontend:

![fearch](./frontend-architecture.png)

## Backend
We use the Spring Boot Framework to build the server which provides the data
stored in the PostgreSQL database. Currently, the following features are
provided:
- Login
- Registering
- Password encryption
- Authentication access
- User Role Authorization
