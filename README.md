# Smart car

files description: 
1) "arduino_code.ino": is the code used to receive orders from ESP chip and move the motors.
2) "esp_code.ino": is the code used to connect to each of the android applications and python code and depending on the received data the ESP sends order to Arduino to move car.
3) "Client_final.py": is the code used to receive image from web socket server (android phone) and do image processing on the recovered image to detect lanes, and sends to the ESP chip the angel of movements.
4) "Auto_pilot_mode.": is the android application which is used to open the camera and
Creates a web socket server on the android phone, and sends the frames whenever the clients 
Requests it, up to 15 frame per second.	
5) "Carsremotecontrol": is the android application which is used to send orders to the ESP to
 control the car as a remotes control.
6) "client": is a plus android application which is used to receive images which are sent from the
"Auto_pilot_mode.rar" application to see the same images which are sent to the python code.
