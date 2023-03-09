# python-api-challenge
An analysis of weather and geography utlizing API calls

Both of the included Jupyter Notebook files include commentary, so a lot of their contents will be self-explanatory. However, There are a few points worth noting. 

WeatherPy is an analysis of random cities that calls the OpenWeatherApp API and prints a few plots via PyPlots. VactionPy is an exercise in finding an "ideal"
vacation spot with various weather-related filters in place that also incorporates Geoapify to rack down lodging spots for the preferred locations. 

Both of the called API's require a key to use, which need to be included in a file named "api_keys.py" in the same folder. In addition, they should be in the
following format:

weather_api_key = "[your code here]"

geoapify_key = "[your code here]"

WeatherPy can be run multiple times to generate different locations, while VacationPy's variables may be altered to display new vacation spots. Neither file
can be trivially adapted for different tasks. However, with similar code that calls from different API's, theoretically they could do do basic analysis for
just about any topic. 

