# Railwways Ticket Booking Service
Railwways Ticket Booking Rest API Service which is basically for the backend service of my application.

## General Information:

**Application Name:** Railwways

**Target Audience:** API is intended for handling the Railway Ticket Booking done by the user by using the Railway React Application.

**Purpose:** I am creating this api to handle all the service of CRUD operation done from the React application.

## Technical Details:

**Authentication:** I have handled the authentiction by using the crypto, jsonwebtoken etc library where i am registering the user and sending an email to confirm if the user is entering valid email to registering and after registeration we are logging in by using username or email with valid password and on login it generate a json web token that we store in localstorage which is valid or expires after the 24hours and when a user try to access private routes like profile or home page we use the token to authenticate if user is valid it also helps in authorization of specific user.

**End Points:** What resources and actions does your API expose? (e.g., /users, /posts, /comments, CRUD operations)

**Request Formats:** We send tokens in req.header.authorization in `Bearer ${Token}`

**Response Formats:** We get the JSON response of token while login or registering user an we can handle that in React Application.

**Error Handling:** I have also used the proper way to handle the by using the error handling.

**Rate Limiting:** I have also used the rate-limiting libraries to better handle the rate limiting.

**Documentation:** I have created an Documentation by using the Postman.

## Additional Information:

Specific Use Cases: 

Future Plans: I have plans to better handle the versioning and security also.

