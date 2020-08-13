API Calls we have 4 api calls for this app

logging in users type: post url : https://fullthrottle-bangalore.herokuapp.com/validatemylogin parameters: username, password response : returns a message to show if authentication and login was successful description: if account creation was successfull it will redirect to dashboard

fetching data from the database type: get parameters: none url : https://fullthrottle-bangalore.herokuapp.com/ response: json data contaning all the information in database in json format.

Creating a new User type: post url : https://fullthrottle-bangalore.herokuapp.com/save_new_user_endpoint parameters: name,tz. The system will creat a unique id on response: msg that tells whether user creation was successfull or not

Creating a new Activity method: post url : https://fullthrottle-bangalore.herokuapp.com/save_activity_endpoint parameters : member, startdate, enddate response: msg that tells whether Activity creation was successfull or not

Technologies used

javascript and ajax - for making and handling api requests without page reload
django - all backend stuff
html and bootstrap 4 - static content
Requirements to run the App Python3 and above, Django===3.0.2
