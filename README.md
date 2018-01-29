# IOT-with-Geo-Location
Building an IOT project with the help of ESP8266 module connected with cloud and google assistant
STEPS FOR THE PROJECT
1. Download the ESP8266 library and install it in Arduino. Here is the link how to install ESP8266 Library https://randomnerdtutorials.com/how-to-install-esp8266-board-arduino-ide/
2. After Succesfully installing copy the code to arduino.
3. Open ubidots account and create Devices>Variables>Switch1,Switch2,Temperature,etc.
4. Copy the id in in the code.
5. Cody the Token ID from Credentials.
6. Change wifi and password in your code.
7. Run the code and open Serial Monitor to check is wifi connected successfuly.
8. Now in Ubidots add switches to dashboard and try to switch it on and off on cloud and check if serial monitor showing any changes or not.
9. If Serial monitor Shows value 1 for ON switch, hence we succefully Connected ESP8266 with Cloud.
