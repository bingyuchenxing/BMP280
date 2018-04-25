# BMP280 开发库

makecode BMP280  micro:bit 大气压传感器开发包

* 作者: 朱林  
* 时间: 2018/4 

![image](https://github.com/zhuning239/BMP280/blob/master/icon.png) 
  
![image](https://github.com/zhuning239/BMP280/blob/master/bmp280.jpg)

## 使用方法
打开 makecode 编辑器，在项目中选择添加软件包，然后在地址栏输入下面网址  
https://github.com/zhuning239/BMP280 

搜索后就可以添加并使用本软件包了。

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

![image](https://github.com/zhuning239/BMP280/blob/master/demo.jpg)

## License

MIT

湖南创乐博智能科技有限公司

## 支持硬件

* for PXT/microbit

