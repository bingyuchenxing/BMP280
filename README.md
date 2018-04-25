# BMP280 开发库

makecode BMP280  micro:bit 大气压传感器开发包

作者: 朱林  
时间: 2018/4 

![](https://raw.githubusercontent.com/microbit-makecode-packages/BMP280/master/icon.png)  
  
![](https://raw.githubusercontent.com/microbit-makecode-packages/BMP280/master/bmp280.jpg)

## usage

open your microbit makecode project, in Add Package, paste  

https://github.com/microbit-makecode-packages/BMP280  

to search box then search.

## I2C Address  

- 0x76/0x77  

## API

- function pressure()  
get pressure in hpa  

- function temperature()  
return temperature in Celsius.

- function PowerOn()
turn on BMP280.

- function PowerOff()  
goto sleep mode  

- function Address(addr: BMP280_I2C_ADDRESS)  
set BMP280's I2C address. addr may be:  
  - BMP280_I2C_ADDRESS.ADDR_0x76
  - BMP280_I2C_ADDRESS.ADDR_0x77

## 案例程序

![](https://raw.githubusercontent.com/microbit-makecode-packages/BMP280/master/demo.jpg)

## License

MIT

湖南创乐博智能科技有限公司

## Supported targets

* for PXT/microbit

