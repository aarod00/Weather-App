index.html:
<!DOCTYPE html> which lets Visual Studio know that I am using html version 5
Next <html lang="en"> lets visual studio know that i am creating a website for english users
Inside head there contains the title "Weather App" as well as diffrent links. Links refer to weather api and my css and javascript files
Inside body is the layout for the website as well as declaring classes onto variables for the css file to add designs to
style.css:
Inside the css file I use diffrent methods to edit partiuclar parts of the webpage.
The main points are body to design the backgorund of the webpage and design the majority of the page
Using diffent class calls to design specific parts of the webpage such as colors and sizes of the displays.
script.js:
The let weather method is used to enter the apiKey id# and access the information given to us form openweather.org
In weather method I also change values to mph and fahrenheit as well as use the diffrent weather icons given to us from openweather.org 
The Search function is used in creating the search bar
The last two functions allow the user to click on or hit enter so that the location in the search bar can be searched
Finally weather.fetchWeather("Tyler"); is used to initailize the opening search as Tyler TX (Our Location)