"setup part"

esp32 >
ftdi usb #

Rx #-->Uot
Tx #-->Uor
Gnd #-->Gnd
5V #-->5V
Gnd <-->Ios (*)

------------------------------------------------------------------------------------------------

arduino IDE install:
https://www.arduino.cc/en/software

"in arduino IDE":
file/prefences:Add URL's:'paste board link'

board link:-
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json, http://arduino.esp8266.com/stable/package_esp8266com_index.json

scetch/unclude LIbrary/addzip: 'import esp32 main zip'

"arduino file/libraries/esp32cam-main/examples/wificam":
Tools/Board/Boards Manger:esp32
Tools/Board/esp32/esp32 Dev Module(wrover Module)
Tools/speed/115200
Tools/partition schen/Huge App
Tools/port/Cmos

"File/examples/esp32/camera/cameraWebserver":
#define CAMERA_MODEL_AI_THINKER (only)


know ssid and pw wifi(cmd):
netsh wlan show profile
netsh wlan show profile [connected wifi name] key=clear

"run code"
"go seriol monitor"
"change 115200 Braud"
"remove (*)"
"restart esp32"
"copy and paste link"
---------------------------------------------------------------------------------------------------------
