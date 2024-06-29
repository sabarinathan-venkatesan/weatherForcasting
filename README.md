# weatherForcasting

I’ll guide you through building a weather app project using HTML, CSS, and JavaScript from scratch. If you prefer using Bootstrap, I’ve already covered that in a previous blog post on creating a Weather App in HTML, Bootstrap, and JavaScript. However, this weather project has some extra features that make it more useful.

In this weather app project, users can enter any city name to get the 5-day weather forecast or simply click on the “Use Current Location” button to get their current location’s weather details, including temperature, wind speed, humidity, and more. This project is also mobile-friendly, which means it looks great on all devices.

Steps To Create Weather App in HTML & JavaScript

To create your weather app using HTML, CSS, and JavaScript, follow these step-by-step instructions:

1.Create a folder. You can name this folder whatever you want, and inside this folder, create the mentioned files.


2.Create an index.html file. The file name must be index and its extension .html


3.Create a style.css file. The file name must be style and its extension .css


4.Create a script.js file. The file name must be script and its extension .js

------------

HTML

To start, add the  HTML codes to your index.html file. This code includes a weather app header, input, button, and unordered list (ul) that are used as a placeholder for weather details. Later, using JavaScript, we’ll replace these placeholders with actual weather details.

--------

CSS

Next, add the CSS codes to your style.css file to apply visual styling to your weather app. Now, if you load the web page in your browser, you will see the header at the top, a sidebar with input and buttons, and weather detail placeholders. You can customize this code to your liking by adjusting the color, font, size, and other CSS properties.

------------

JAVASCRIPT

Finally, add the JavaScript code to your script.js file. This script code will make your weather app functional, which means now you can get a 5-day weather forecast for any city or your current location.

------------------------------------------------------------------------------------------------------------------------------------------

Please note that your weather app is still unable to show the weather forecast for any location because you’ve not provided your OpenWeatherMap API key in the API_KEY variable. To get a free API key, sign up for an account at https://home.openweathermap.org/api_keys. Your API key may take minutes or hours to activate. You’ll get an error like “Invalid API Key” or something similar during this time.

In the code, there are two API calls. The first one fetches the geographic coordinates of the user-entered city. These coordinates are then used in the second API call to retrieve the weather forecast, which is displayed on the page. The code also includes a feature that asks for user location permission and, once granted, makes the second API call to fetch the weather forecast based on the user’s current location.

------------------------------------------------------------------------------------------------------------------------------------------

Conclusion and Final Words


In conclusion, building a weather app project allows you to apply your web development skills to a real-world application. Also, it helps you to better understand DOM manipulation, Event handling, CSS styling, APIs, and more. I hope that by following the steps in this post, you’ve successfully created your weather app using HTML, CSS, and JavaScript.


To understand this project’s code better, I recommend watching the above tutorial video, reading the code comments, and experimenting with the code. If you want to further enhance your web development skills, you should try recreating the Working Chatbot using HTML, CSS, and JavaScript.


If you encounter any difficulties while creating your weather app or your code is not working as expected, you can download the source code files for this weather app project for free by clicking the Download button. Keep in mind that after downloading the file, you’ll have to paste an “OpenWeatherMap API Key into the API_KEY variable in the script.js file.
