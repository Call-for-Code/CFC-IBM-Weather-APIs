# Call for Code: IBM Environmental Intelligence Suite APIs

Weather is a natural phenomenon that cannot be controlled but can be predicted so that we can be prepared and reduce its impact by creating technological solutions.

Weather plays a significant role in climate change which affects the ecological environment like shortage of water, ecosystem degradation, soil erosion and reduction in biodiversity. It also causes natural disasters like hurricanes, flooding, droughts, earthquakes, etc.

**[Call for Code](https://developer.ibm.com/callforcode/)** invites participants to utilize **The Weather Company Data APIs** offered as **[IBM Environmental Intelligence Suite (EIS)](https://www.ibm.com/products/environmental-intelligence-suite)** to predict, prepare and build great solutions using technology. The Weather Data APIs are free for the Call for Code participants until **the end of each Global Challenge Round**.

**[IBM Environmental Intelligence Suite Weather Data APIs](https://www.ibm.com/products/environmental-intelligence-suite)** give deeper and broader insights into current and long-term forecasted conditions, seasonal and sub-seasonal forecasts, lifestyle indices, severe weather and historical weather data.

**[IBM Environmental Intelligence Suite](https://www.ibm.com/products/environmental-intelligence-suite)** provides two main API offerings;

### Standard APIs

The [Standard APIs](https://docs.google.com/document/d/14OK6NG5GRwezb6-5C1vQJoRdStrGnXUiXBDCmQP9T9s/edit) offers essential weather APIs;

- Utility APIs for location services
- Core APIs for alerts, daily, weekly, intraday, monthly and imagery forecast
- Enhanced current conditions APIs for historical and on-demand data
- Enhanced forecast APIs for 15 days, hourly, 15 minute, precipitation, snowfall and analytical forecasts
- Lifestyle indices APIs for air quality, pollen, US Flu outbreak, US tides, breathing index, driving difficulty, ski index, UV index, watering needs and many more
- Severe weather APIs for local/tropical storms, earthquakes and power disruption data
- History on-demand APIs for direct, archived, analytics historical data
- Agriculture APIs for frost, degree and watering need data

Please visit the **[Standard APIs documentation](https://docs.google.com/document/d/14OK6NG5GRwezb6-5C1vQJoRdStrGnXUiXBDCmQP9T9s/edit)** for detailed information about the APIs and their usage.

### Premium APIs

The [Premium APIs](https://docs.google.com/document/d/16TJJVFvNxqmWR1T6wmpnHuV3XZIZ0krJVcJRprs85tc/edit) are the add-on APIs for the Standard APIs and can be subscribed to if required. And they offer;

- Enhanced current condition and forecast with APIs for gridded and polygonal observations, forecast and imagery data
- Severe weather APIs with radar-derived hail, rain, ice, shear, snow visions data. - - Tropical cyclone probability and imagery data of wildfire and smoke
- History on-demand APIs with extended data
- Seasonal forecast APIs with imagery gridded and polygonal seasonal/sub-seasonal forecast
- Agriculture APIs with crop type lookup, 15 days hourly and solar energy forecast
- Renewables APIs for solar and wind forecast
- Probabilistic forecast API

Please visit the **[Premium APIs documentation](https://docs.google.com/document/d/16TJJVFvNxqmWR1T6wmpnHuV3XZIZ0krJVcJRprs85tc/edit)** for detailed information about the APIs and their usage.

### Get Started

To access and use the Weather APIs you will require an API Key as a parameter when requesting an API.

Please request an **[API key here](https://airtable.com/appH4Pgp5VwbNsunH/pag1e1VDzOkT7bxFD/form)**. Please read the terms and conditions carefully before requesting the API key, although the APIs are globally accessible they are restricted to use in some countries.

Once you have the API Key you can make a GET request to the required API.

**Example:**

Curl GET request for 3 day daily forecast API

```curl
curl -X GET "https://api.weather.com/v3/wx/forecast/daily/3day?geocode=33.74,-84.39&format=json&units=m&language=en-US&apiKey=yourApiKey" -H "accept: application/json"
```

### Join Slack

Please join **_#twc-weather-api-support_** channel in the **[Call for Code](https://callforcode.typeform.com/to/Ow3xQr?typeform-source=github.com)** slack workspace to post any questions and learn more about the APIs.
