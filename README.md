# Bikeshop
ASP.net API for a imaginary bike shop

## Why
To practice asp.net I decided to create an API for a imaginary bikeshop.

## Functionality
As for every project, there are some requirements. Since I don't want it to be to detailed, I'll create some simple high level customer requirements.

### User
- A user is able to create an account.
- A user is able to recover his/her password via her e-mail.
- A user gets a error message when her login information is wrong. 


### Customer (logged in user)
- A customer is able to buy a bike.
- A customer is able to buy parts of a bike.
- A customer is able to add items to his/her shopping cart.
- A customer can view 20 items (bike/part) per page. 
- A customer can sort pages based on either *price*, *newest* or *category*.


### Shopowner
- The owner is able to add bikes to the inventory.
- The owner is able to add bike parts to the inventory.
- The owner is able to remove bikes to the inventory.
- The owner is able to remove bikes to the inventory.
- In case somebody ordered a bike but the owner wanted to remove it, the owner can cancel the order.
- In case somebody ordered a bike but the owner wanted to remove it, the owner can cancel the order partially.
- In case somebody ordered a bike but the owner wanted to remove it, the owner can send a mail.


### Non-functional requirements
- Use of ASP.net IdentityServer for authentication.
- Scale up to 10.000 users with maximum API response time of 100 ms.

### Won't haves
- No wishlist.
- No newsletter.
- Remove account.
- Payments via real transactions.

## Prerequisites
TODO 

## Installing
TODO

## Running tests
TODO

## Deployment
TODO

## Built with
TODO