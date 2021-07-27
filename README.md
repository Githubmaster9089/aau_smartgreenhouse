# Introduction
This repository was made for controlling a Smart-Greenhouse. It also includes a part list and a 3D-Model of the casing.

# Warranty
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

# Hardware
Microcontroller: Esp32 NodeMCU
**Sensor:**
- FC-37 (Rain Sensor)
- Capacitive soil moisture sensor v1.2 (Soil moisture Sensor)
- DS18B20 (Soil temperature Sensor)
- BMP280 (Temperature, Pressure, Altitude Sensor)
- UVM30A (UV Sensor)
- ARD SEN LDR (Light intensity Sensor)

**Actuators:**
- 2 x FUNGWAN MG 996R (Servo Motor)
- 3-Wire Fan (Fan)
- 3 x 5v Relays (Relay)
- 230v Lamp (Lamp)

# Dependencies
<ESP32Servo.h>
<Adafruit_BMP280.h>
<Adafruit_Sensor.h>
<Wire.h>
<OneWire.h>
<DallasTemperature.h>
<SPI.h>
<BH1750.h>
<EspMQTTClient.h>

# Application Steps
- Build the Greenhouse-Casing
- Connect the sensor to the Micro-Controller (take a look at the datasheets to not overvolt one of the Sensors/Esp32)
- Flash software onto the Esp32 with the Arduino IDE
- Setup a Node-RED Server and import JSON

# Appendix

![ezgif com-gif-maker](https://user-images.githubusercontent.com/75416341/127112592-78f6b7f0-ea5b-4a79-b5cd-c291f216eaac.gif)

![IMG_20210727_091626](https://user-images.githubusercontent.com/75416341/127112250-a71cf4f3-a005-45c8-820c-38667a2630aa.jpg)








