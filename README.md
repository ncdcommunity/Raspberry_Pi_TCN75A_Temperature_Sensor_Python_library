[![ TCN75A](TCN75A_I2C.png)](https://store.ncd.io/product/tcn75a-temperature-sensor-%C2%B10-5c-12-bit-with-3-address-lines-i2c-mini-module/).

#  TCN75A

The TCN75A comes with user-programmable registers that provide flexibility for temperature-sensing applications.
This Device is available from www.ncd.io 

[SKU: TCN75A]

(https://store.ncd.io/product/tcn75a-temperature-sensor-%C2%B10-5c-12-bit-with-3-address-lines-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface TCN75A temperature sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/tcn75a-temperature-sensor-%C2%B10-5c-12-bit-with-3-address-lines-i2c-mini-module/">TCN75A temperature sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python TCN75A.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
