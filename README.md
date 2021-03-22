# que5
![image](https://user-images.githubusercontent.com/81148191/111958605-aa3b0480-8aaa-11eb-88ee-9a95c04185d1.png)

#include “wifi.h”
#include “ESPA syncWebServer.h” 
#include “DHTesp.h”
#include “SoftwareSerial.h”
#include “MHZ19”
#define RX_PIN33
#define TX_PIN32
Int dhtPin=4;
DHTesp dht;
MHZ19 myMHZ19;
SoftwareSerial mySerial(RX_PIN,TX_PIN);
AsyncWebServer Server(80);
Const char*ssid= “network name”;
Const char*Password=”Password”;
Serial.begin(115200);
Wifi.begin(ssid,password);
Server.on(“/C02”,HTTP.GET,[]);
(AsynWeb serverRequest*request));
