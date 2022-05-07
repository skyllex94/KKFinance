# KKFinance
Stock Portfolio Full Stack Web App wt IEX API, build wt Flask and Jinja

# Usage
You will need to get an API key from IEX (free account registration), which lets you download stock quotes via their API (application programming interface) using URLs like 
https://cloud.iexapis.com/stable/stock/nflx/quote?token=API_KEY

With the API, run the following within a CS50 IDE's terminal: $ export API_KEY=value (value is your acquired personal API KEY)

Install Flask and it's dependencies and start Flask’s built-in web server: $ flask run

# UI Overview
The web app has built-in sessions for storing data about the current user after he makes a registration. After it, it will create a new user in the users database after making a request to it.

![alt text](https://github.com/skyllex94/KKFinance/blob/main/readme-images/1.jpg?raw=true)
