# VerzeoMainProject
The Description and Details of the Main Project under Verzeo

Automation systems are being preferred over the manual mode because it reduces the use of energy. These automation systems play an essential role in making our daily life more comfortable and facilitate users from ceiling fans to washing machines and in other applications. Among all exciting applications, street lights play a vital role in our environment and also plays a critical role in providing light for safety for citizens and reducing crimes against women. In this scenario, when the street lights are in working functionality over the whole night that consumes a lot of energy and reduces the lifetime of the electrical equipment such as electric bulb etc. Especially in cities' streetlights, it is a severe power consuming factor and also the most significant energy expenses for a city. In this regard, an intelligent lighting control system can decrease street lighting costs up to 70% and increase the durability of the equipment.

An IoT based solution that will keep track of which lights are working, and how much electricity they are consuming will work the best in such a scenario. The solution should have either phase wise control or individual light wise control. A single gateway device that can upload this data to the Internet, and operate the lights at the same time, will help the supervisors immensely. A connection backbone of wireless technologies like Wi-Fi will be the most cost-effective solution. Automated ON / OFF control of individual lights will be possible at the end of the completion of the project.

Components/Applications Used:

1.	Nodemcu  
NodeMCU is a low-cost open source IoT platform. It initially included firmware which runs on the ESP8266 Wi-Fi SoC from Espressif Systems, and hardware which was based on the ESP-12 module. Since NodeMCU is open source platform, their hardware design is open for edit/modify/build.
NodeMCU Dev Kit/board consist of ESP8266 WIFI enabled chip. 
NodeMCU in the project acts as an intermediate between the cloud and the actuator and also controls the cloud.



2.	5v relay
Commonly used in switching circuits. In current trend of Home Automation projects to switch AC loads, to Control (On/Off) Heavy loads at a pre-determined time/condition. It is also used in safety circuits to disconnect the load from supply in event of failure. In the present case the relay helps in switching the AC source to the destination i.e., streetlight bulb as per the instruction given by the controller, NodeMCU which gets the information either by the LED or the internet, as specified by the user.


3.	Herokuapp
Heroku is a cloud platform as a service (PaaS) supporting several programming languages. One of the first cloud platforms, Heroku has been in development since June 2007, when it supported only the Ruby programming language, but now supports Java, Node.js, Scala, Clojure, Python, PHP, and Go. For this reason, Heroku is said to be a polyglot platform as it has features for a developer to build, run and scale applications in a similar manner across most languages. Heroku was acquired by Salesforce.com in 2010 for $212 million. Heroku has been one of the important part of the project rendering a cloud platform for exchange of data from the internet to the microcontroller and vice versa.


