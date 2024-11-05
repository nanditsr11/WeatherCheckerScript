# WeatherCheckerScript
This script allow you to check the weather of your city with practically no code.

This script retrieves the current weather for Lucknow from wttr.in, a web-based weather forecast service.

# Requirements
•	Ensure curl is installed and accessible via your system's command line.

# Usage
1.	Save the following code in a .bat file (e.g., WeatherCheck.bat):

@echo off
curl wttr.in/{Your City Name}
pause

2.	Run the script by double-clicking the .bat file or executing it from the command line.

# What It Does
•	@echo off: Suppresses command output to make the script cleaner.
•	curl wttr.in/Lucknow: Uses curl to fetch the weather for Lucknow.
•	pause: Keeps the window open after fetching the weather so you can view the output.

# Customization
To check the weather in a different city, replace Lucknow with your desired city in the curl command:

curl wttr.in/<YourCity>

Enjoy a quick weather check directly from your command prompt!




