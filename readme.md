## API Overview:
-A brief summary of our API is one that allows users to create users, login/logout those users, update those users, and to delete them.
## How user authentication was implemented:
-We implemented user authentication via bcrypt and the jwt libraries of node where bcrpyt hashed our user data and jwt provided the login token for the user's browser to verify their credentials.
## How project was structured via the MVC architecture:
-Our project follows the mvc architecture. In our models file we have our schemas that define how data should be structured. Our controller file handles the logic of api, specifying the routes of the server that the user uses to perform their actions. To make a comparison to JS, the controllers are like methods.
## Summary of finding when analyzing and optimizing our API performance:
-With our artillery testing we were able to find that there is a limit to the load our API can handle. 
-Alot of our API optimization happened in testing our code. We brokedown what the purpose our code was and what was needed to acheive that.
## Project challenges:
-Our main challenges were encounted when testing our code via JEST. We specifically found challenges in isolating where our code was going wrong whether that be in how we wrote our tests or in how we wrote our controllers.