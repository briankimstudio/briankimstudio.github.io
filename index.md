<p align="center">
<img src="img/Profile-small.jpg" width="150" >
</p>

### Education
+ Ph.D.(4th year) in [Technology Management 科技管理研究所](http://itm.nchu.edu.tw/) at [National Chung Hsing University 國立中興大學](https://www.nchu.edu.tw/en-index), Taiwan
+ Masters of Computer Science at [Texas A&M University 德州農工大學](https://engineering.tamu.edu/cse/index.html), USA
+ MS in Computer Science at [Korea University 韓國高麗大學](https://cs.korea.edu/en_cs/index.do), Korea

### Research Focus

+ Data Science, Topic Modeling(Machine learning-based data analysis methodology)
+ [Mobile Health Technology Adoption](https://doi.org/10.1016/j.tele.2021.101603)
+ [IoTs for Smart Life](#iots-for-smart-life)

### Publications (Within 5 years)
+ Kim, T. B., & Ho, C.-T. B. (2021). Validating the moderating role of age in multi-perspective acceptance model of wearable healthcare technology. Telematics and Informatics, 61, 101603. [https://doi.org/10.1016/j.tele.2021.101603](https://doi.org/10.1016/j.tele.2021.101603). **SSCI**(Impact Factor=**4.129**)
+ Kim, T. B., & Ho, C.-T. B. (2021). AI-based framework for discovering under-investigated topics in health information systems research. 2021 Management Concept and Application Conference, Kaohsiung, Taiwan.
+ Kim, T. B., & Ho, C.-T. B. (2021). Visual Data Exploration of Covid-19’s Impacts on Economic Research. International Conference on Information Management 2021, Taipei, Taiwan.(Accepted)

<p align="center">
<img src="img/1-3_210404_19.jpg" width="720">
</p>
<p align="center">   
Presentation at 2021 Management Concept and Application Conference, Kaohsiung, Taiwan
</p>

### Scholarships and Awards

+ Taiwan Scholarship [教育部臺灣獎學金](https://taiwanscholarship.moe.gov.tw/web/index.aspx), Ministry of Education, Taiwan, 2017~2021
+ Student Academic Publication Scholarship 國立中興大學科技管理理研所學生學術論文研究獎勵, [GITM](http://itm.nchu.edu.tw/), NCHU, 2021
+ Scholarship for attending academic conference 國立中興大學科技管理研究所學術發表獎助, [GITM](http://itm.nchu.edu.tw/), NCHU, 2021

### Reviewer for international journals

+ Industrial Management & Data Systems (SCIE,IF=3.329)

### Coursework

+ Research Methods for Technology Management 科技管理研究方法
+ Management of Technology: Theory and Practice 科技管理理論與實務
+ Internet Business Models and Strategies 電子化策略與經營模式
+ Operations Management 營運管理
+ Service Science 服務科學
+ Electronic Customer Relationship Management 電子化顧客關係管理
+ Emerging Technology and Industry Application 新興電子商務與企業應用
+ Advanced Research Topics in E-Business 高階電子化企業研究

### Foreign language skills

+ English - Professional proficiency in listening, speaking, reading, and writing
+ Chinese – Advanced ([TOCFL](https://www.sc-top.org.tw/) Level 4)
+ Korean – Native 

### Research (Within 5 years)

#### Topic Modeling

This study analyzes the metadata of 2,296 research articles using the AI-based topic modeling method for identifying under-investigated research topics. The results of this project guide policymakers and scholars to plan research direction precisely and allocate invaluable resources effectively for the best possible outcome.

<p align="center">
<img src="img/topic-terms.png" width="500" >
</p>

+ Requirements
   + [Web of Science Database](https://webofknowledge.com/)
   + [R](https://www.r-project.org/)
   + R Packages
      + [topicmodels](https://cran.r-project.org/web/packages/topicmodels/index.html)
      + tidyverse
      + tidytest
      + ggplot2

#### Knowledge Mapping

This study investigates the global collaboration pattern of economic research during the pandemic using co-occurrence analysis to adequately prepare solid research collaboration plans for scholars and policymakers.
<p align="center">
<img src="img/keyword-country.png" width="500" >
</p>

+ Requirements
   + [Web of Science Database](https://webofknowledge.com/)
   + [VOSviewer](https://www.vosviewer.com)
   + [R](https://www.r-project.org/)
   + R Packages
      + bibliometrix
      + networkD3
      + htmlwidgets
      + igraph
      + tidyverse
      + ggplot2


### [IoTs for Smart Life](https://hpclab.blogspot.com/)

#### Environmental monitoring and notification system

   This system monitors CO2 levels in real-time. Then notifications are sent to mobile messengers including Line and Telegram.
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

#### Cloud-based Voice Recognition System For Smart Home

   This system recognizes human voice to control LED light using Google Assistant. Then, commends are sent to IFTTT and Adafruit MQTT for executing pre-defined operations in ESP8266-based IoT device.
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

   + Requirements
     - Wemos D1 mini
     - [NeoPixel compatible LED stick](https://www.adafruit.com/product/1426)

[For more project...](https://hpclab.blogspot.com/)
