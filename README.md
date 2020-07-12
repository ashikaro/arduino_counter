# arduino_counter


Arduino & Android Timer App: 
Here android app connects with Arduino via bluetooth and has the following features:

Once you open the app:
1. We can press the connect button in order to connect the app to the BLE. The logs of the bluetooth will be shown at the bottom of the app where you can find out whether the app is connected or not.
2.  Once connected,  we are now able to start the timer with a button and it runs for a default config of 5s with red color and beep turned on.
3.  We are able to configure the color for the timer from the UI, adjust the timer duration (1 to 10s) and whether we need a beep at the end.
4. There is also a button to read the current temperature and display the value and a button to clear the timer lights.
5. Timer can be triggered from the UI or from the buttons on the Arduino board. 
6. At any point of time, the timer kicked-off in any of the ways uses the configuration from the UI.



Once you open the app:
1. The app connects to the bluetooth automatically.  There is also a button to connect to the bluetooth explicitly incase the connection gets disconnected.
2. We are able to start the pull-ups counter with a start button.  
3. Once the counter is started, if you shake the Arduino board rapidly up and rapidly down, you can hear the beep on every count. It also logs to the serial monitor in Arduino.
4. At any point of time, if you press the get count button, it displays the current count in the UI. 
5. You can press the stop button to stop the counter and if you do a immediate get, you should get a count of 0.
