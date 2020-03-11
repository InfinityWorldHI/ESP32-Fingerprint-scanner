# ESP32-Fingerprint-scanner

ESP32 with Fingerprint scanner and OLED display for the biometric attendance system.

OLED is connected to ESP32 via I2C:
  * SDA to pin22
  * SCL to pin21
  * Vcc to 3.3v
  * GND to GND
  
Fingerprint scanner is connected to ESP32 via Serial:
  * Tx to Tx2
  * Rx to Rx2
  * Vcc to 3.3v
  * GND to GND
