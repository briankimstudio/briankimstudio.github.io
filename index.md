# Current Position

Pursuing a Ph.D. in Technology Management in National Chung Hsing University

# Research Focus

## Data Science, Machine Learning, Topic Modeling

### Topic Modeling

This study analyzes metadata of 2,296 research articles using AI-based topic modeling method for identifying under-investigated research topics. The results of this project guide policymakers and scholars to plan research direction precisely and allocate invaluable resources effectively for best possible outcome.

<p align="center">
<img src="img/topic-terms.png" width="500" >
</p>

+ Requirements
   + Web of Science Database https://webofknowledge.com/
   + R https://www.r-project.org/
   + R Packages
      + topicmodels https://cran.r-project.org/web/packages/topicmodels/index.html
      + tidyverse
      + tidytest
      + ggplot2

### Co-occurrence Analysis

This study investigates the global collaboration pattern of economic research during pandemic to adequately prepare solid research collaboration plans for scholars and policymakers.
<p align="center">
<img src="img/keyword-country.png" width="500" >
</p>
+ Requirements
   + Web of Science Database https://webofknowledge.com/
   + VOSviewer https://www.vosviewer.com
   + R https://www.r-project.org/
   + R Packages
      + bibliometrix
      + networkD3
      + htmlwidgets
      + igraph
      + tidyverse
      + ggplot2


## IoT http://hpclab.blogspot.com/

### Environmental monitoring and notification system

   This system monitors CO2 evel in realtime then send notification to mobile messengers including Line and Telegram.
<p align="center">
<img src="img/wemos_MH-Z19B_TELEGRAM_NOTIFY.PNG" width="500" >
</p>

   + Prerequisites

     - Arduino IDE
     - ESP8266 package for Arduino IDE
     - EPS8266 Sketch Data Upload
     - ESPAsyncTCP Library
     - ESPAsyncWebServer Library
     - Telegram Bot token and chat id

   + Requirements

      - Wemos D1 mini
      - MH-Z19B CO2 sensor

### Google Assistant controlled Custom LED system

   This system uses IFTTT and Adafruit MQTT to communiate with Google Assistant for controlling LED light.
<p align="center">
<img src="img/wemos_GOOGLE_ASSISTANT_title.png" width="500" >
</p>
   
   + Prerequisites

     - Arduino IDE
     - ESP8266 package for Arduino IDE
     - EPS8266 Sketch Data Upload
     - IFTTT
     - Adafruit MQTT broker
     - Adafruit_NeoPixel Library for controlling single-wire LED pixels (NeoPixel, WS2812, etc.)

   + Hardware
     - Wemos D1 mini
     - NeoPixel compatible LED stick: https://www.adafruit.com/product/1426
