# Tweeter

## About the Project
Full stack web application built with Node, Express, AJAX, Twilio API, jQuery, HTML5, CSS3 and PosgreSQL.

### Problem Statement

An application built to simplify online food ordering for pickup.

### Expected Usage

Desired users are restaurant owners and customers:
- Restaurant owners can register and login to see their orders. They will recieve a phone call every time an order is made online.
  - They can then either accept or decline the order.
  - Over the phone, they specify how long the order will take to prepare.
  - This triggers a notification to the customer with estimated preparation time via SMS.
  - The restaurant owner can then see the orders online, with a countdown timer based on the estimated preparation time.
  - They can mark an order as complete when the food has been prepared, which sends a notification to the customer.

- Customers can order from the restaurant menu online.
  - They are notified when the order has been accepted and how long it will take.
  - They are notified again when the food is ready.

## Getting Started
Install all dependencies (using the 'npm install' command).

Run the development web server using the 'npm start' command.

As a restaurant owner:
Visit the page: http://localhost:3000/ in your browser.

Ad a user:
(This allows the connection to Twilio to allow phonecalls and SMS text)
1. Install the google chrome extension, Forward : https://chrome.google.com/webstore/detail/forward-link-to-localhost/ghnicdmecgkdbledgnmbbnddfnjjgegp?hl=en
2. Visit the page: http://localhost:3000/ in your browser.
3. Call the chrome extension, Forward.
4. Create a tunnel.


### Dependencies
- bcrypt 1.0.2 or above
- body-parser 1.17.2 or above
- cookie-session 2.0.0-beta.2
- cookie-parser 1.4.3 or above
- dovenv 4.0.0 or above
- ejs 2.5.6 or above
- express 4.15.3 or above
- express-basic-auth 1.1.1 orabove
- morgan 1.8.2 or above
- node 5.10.x or above
- pg 7.0.2 or above
- request 2.81.0 or above
- twilio 3.5.0 or above

## In Action
//Photos here