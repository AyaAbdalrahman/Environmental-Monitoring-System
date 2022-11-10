# Environmental-Monitoring-System

Environment monitoring system in industrial area is system to monitor the pollution coming from the factory chimney and uses Wi-Fi to transfer the data to website. The main objective of the project is to monitor the pollution which comes from factories to protect the environment. It uses monitor the temperature and display on LCD, the values of humidity is displayed on LCD. A wireless System is used to Transfer these data (temperature and humidity) to remote monitoring station.

## How it works
The microcontroller ( NodeMCU ) takes the values of parameters (CO, Humidity and temperature ) from the sensors ( DHT 11 and  MQ -9 ) and sends the data by the connection between ESP 8266 and access point to our domain (aaa-envmon.000webhost.com) as HTTP post request .  then php backend code takes the data and stores it in MySQL data base. Website retrieves the data from the data base and display it to the user in a table and chart.  



