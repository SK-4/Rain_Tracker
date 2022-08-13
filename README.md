# Rain_Tracker
Check the weather accordingly and prevents from errors using twillio API

Sends user the text message , in the morning just before we head out telling us to bring an umbrella if it's going to rain in the day . So this way we don't have to check the weather we know that our trusty application is always going to alert us via an SMS message if we need to bring an umbrella or raincoat before we leave home.

In order to create my rain alert python script , I want the script to be run every morning at 7 am to check whether for the next 12 hours will it be raining and then I'll know how to prepare for the day.

So, I found the open weather API i went through their documentation then i collected the API keys 
Now back to the python basics
collect latitude and longitude latlong.net 
make a request to the One Call API using the requests module
print out the http status code that you get 
print the response to the console
copy paste that response to JSON viewer to get hold of things we need
locate the hourly forecast for the next 48 hours

The Twillo is an API service that allows us to send text messages or phone calls or have a virtual phone number in any or  country email.
pythonanywhere to automate python scripts
