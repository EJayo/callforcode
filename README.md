# Node-RED Ocucaje Weather Alert Map
This is a small prototype to provide a solution to climate change and "water sustainability".

Our proposal is to provide an informative dashboard with the state of the climate. We aspire that in the future with more complete technology such as BigData and Machine Learning, weather forecasts can be created.

Use [The Weather Company APIs](https://weather.com/swagger-docs/call-for-code) using APIs [Daily Forecast API] (https://weather.com/swagger-docs/ui/sun/v1/sunV1DailyForecast.json):

This example flow and Node-RED Dashboard might be useful as part of a [Call for Code](https://developer.ibm.com/callforcode/) solution. The Call for Code 2020 theme is to help reverse the impact of Climate Change. How we are participating in the [2020 Call for Code](https://developer.ibm.com/callforcode/) usinga time limited TWC API key.

### Problem and Place: Ocucaje - Ica - Peru
Peru is a country with three well-marked regions, the coast, mountains and jungle. The coast of Bahia is crossed by rivers that carry water from the Andes in the mountains to the Pacific Ocean, the entire Peruvian coast is deserted with valleys on the slopes of those rivers. Our chosen place is Ocucaje, a desert place in the Ica valley.
This place lives on agriculture, the form of irrigation is similar to its ancestors, flooding the water pits that can only come once a year, that is, it only has one opportunity for the rest of the year, which is a valley surrounded desert and the average temperature is 20 °C. The current farmers work with the experience of transmission from generation to generation, for irrigation, planting, cultivation and other tasks are based on moon phases and great faith.

### Proposal
With technological advancement many tools are available and even cheap compared to past decades. For this prototype we use an [IBM API] (https://api.weather.com) to check the weather, but we would like to delve into the solution with 'personal weather station' located in strategic areas of Ocucaje due to its microclimates. This will allow data to be stored for a few years, with this information we would like to create predictive models of the climate with the use of data analytics, Internet of Things, artificial intelligence.

The initial purchase of the 'personal weather station' we want to be financed by authorities or public companies, in recent years Ocucaje has been identified as an ideal place to house a wind power plant. Another great sector in which Ocucaje has been growing is tourism, with a large cemetery of fossils and cultures that have left archaeological remains and geoglyphs, which can help to obtain sponsors.


### Prerequistes

- [Install Node-RED](https://nodered.org/docs/getting-started/) on your system or in the cloud
- This flow requires Node-RED v1.1 or higher
- Using to Node-RED default palette


## Node-RED flow in this repository:
---
### A flow that displays weather alerts for the day, location on a map, and moon phase with wind behavior.

![Ocucaje Weather Alert Panel](images_dashboard/TWC-OcucajeWeatherAlerts-dashboard.png?raw=true "Ocucaje Weather Alert Panel")

<p align="center">
  <strong>Get the Code: <a href="example_code/OcucajeWeatherAlertPanel.json">Node-RED export flow for Ocucaje Weather Alert Panel</strong></a>
</p>

![Ocucaje Weather Alert flow](images_dashboard/TWC-OcucajeWeatherAlerts-flow.png?raw=true "Ocucaje Weather Alert flow")
---

### Authors

- [Edgar Jayo](https://github.com/EJayo)
- [Maritza Lozano]
- [Giorgio Jayo]
- [Narciso Jayo]
- [A...]

___

Enjoy!  Give us [feedback](https://github.com/johnwalicki/Node-RED-Severe-Weather-Alert-Map/issues) if you have suggestions on how to improve this tutorial.

## License

This npm package is licensed under the Apache Software License, Version 2. Separate third party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses.

[Apache Software License, Version 2](http://www.apache.org/licenses/LICENSE-2.0.txt).
