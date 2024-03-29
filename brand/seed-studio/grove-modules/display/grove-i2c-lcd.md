---
oldwikiname: I2C_LCD
prodimagename: I2C_LCD_WIKI_1.jpg
surveyurl: 'https://www.research.net/r/I2C_LCD'
bzurl: >-
  https://www.seeedstudio.com/I2C_LCD-%28With-universal-Grove-cable%29-p-2601.html
title: I2C LCD
tags: 'grove_i2c, io_5v, plat_duino, plat_linkit'
sku: 114990279
category: Display
---

# Grove I2C LCD

![enter image description here](https://raw.githubusercontent.com/SparkingStudio/I2C_LCD/master/images/I2C_LCD_WIKI_1.jpg)

I2C\_LCD is an easy-to-use display module, It can make display easier. Using it can reduce the difficulty of make, so that makers can focus on the core of the work.

We developed the Arduino library for I2C\_LCD, user just need a few lines of the code can achieve complex graphics and text display features. It can replace the serial monitor of Arduino in some place, you can get running informations without a computer.

More than that, we also develop the dedicated picture data convert software \(bitmap converter\)now is available to support PC platform of windows, Linux, Mac OS. Through the bitmap convert software you can get your favorite picture displayed on I2C\_LCD, without the need for complex programming.

I2C\_LCD can provide you with a very convenient way of make. Enjoy yourself!

## Features

* Only 2 Arduino pins are occupied \(Use I2C interface\).
* Supports standard I2C mode \(100Kbit/s\) and fast I2C mode \(400Kbit/s\).
* Compatible with multiple communication logic levels: 2.8~5VDC.
* Arduino library supported, use a line of code to complete the display.
* Integrate 7 sizes of ASCll fonts, 5 graphics functions.
* Provide dedicated picture data convert software \(Bitmap Converter\).
* Most of the complex operation is processed by I2C\_LCD independent controller, saving user controller resources.
* Supports cursor function, can set up 16 cursor flicker frequency.
* Supports 128 level backlight lightness adjustment.
* Support 64 level screen contrast adjustment.
* Support device address modification.
* Supports 127 I2C\_LCD work in parallel.
* When debugging code, it can take the place of the serial monitor to monitor the program running state.
* Two abnormal recovery methods are provided: reset and restore the factory settings.
* Compatible with Grove interface and 4Pin-100mil interface \(under the Grove socket\).
* 4 symmetrical fixed hole design for easy user installation.
* China style unique appearance.

## Platforms Supported

## Interface Function

![enter image description here](https://raw.githubusercontent.com/SparkingStudio/I2C_LCD/master/images/I2C_LCD_Board.jpg)

## Specification

| Parameter | Value |
| :--- | :--- |
| Screen Type | Dual colour LCD |
| Screen Resolution | 128\*64 Pixels |
| Screen Active Area \(L\*W\) | 47.1\*26.5mm |
| Individual Pixel Size | 0.33\*0.33mm |
| Communication Mode | I2C\(100Kbit/s and 400Kbit/s\) |
| Controller | STM8S005KBT6 |
| Operating Frequency | 16 MHz |
| Weight | 20g |

## Electrical Characteristics

| Parameter | Min. | Typical | MNax. | Unit |
| :--- | :--- | :--- | :--- | :--- |
| Supply voltage（5V to GND） | 4.5 | 5 | 5.5 | V |
| Logic Voltage（SCL/SDA） | 2.8 | 5 | 5.5 | V |
| HBM ESD | - | 5000 | - | V |
| Temperature | -20 | 25 | 70 | ℃ |

## Getting Started

**Step 1:** Install the latest version of Arduino IDE to your computer.

**Step 2:** Download and install the I2C\_LCD library to Arduino IDE:

Open Arduino IDE, **click Sketch -&gt; Include library -&gt; Add .ZIP library**.

![enter image description here](https://raw.githubusercontent.com/SparkingStudio/I2C_LCD/master/images/I2C_LCD_InstalLib_1.jpg)

Find and select the **I2C\_LCD.zip** file you just downloaded.

![enter image description here](https://raw.githubusercontent.com/SparkingStudio/I2C_LCD/master/images/I2C_LCD_InstalLib_2.jpg)

Restart the Arduino IDE.

**Step 3:** Chose the example project which you like. \(Take "HelloWorld" project for example here.\)

**Click File &gt; Examples &gt; I2C\_LCD &gt; HelloWorld**

![enter image description here](https://raw.githubusercontent.com/SparkingStudio/I2C_LCD/master/images/I2C_LCD_InstalLib_3.jpg)

**Step 4:** Connect I2C\_LCD to your Seeeduino Vx board with Grove cable. Then connect Seeeduino Vx board to your computer.

![enter image description here](https://raw.githubusercontent.com/SparkingStudio/I2C_LCD/master/images/I2C_LCD_InstalLib_4.jpg)

**Step 5:** Select your board and serial port.

Select the board: **Click Tools &gt; Board &gt; "Arduino Duemilanove or Diecimila"\(Seeeduino V3.0 Or early version\), "Arduino Uno"\(Seeeduino Lotus or Seeeduino V4.0\)**.

![enter image description here](https://raw.githubusercontent.com/SparkingStudio/I2C_LCD/master/images/I2C_LCD_InstalLib_5.jpg)

Select the COM: **Click Tools -&gt; Serial Port -&gt; COMX\(which connected with your board.\)**

![enter image description here](https://raw.githubusercontent.com/SparkingStudio/I2C_LCD/master/images/I2C_LCD_InstalLib_6.jpg)

**Step 6:** Upload the program and **enjoy yourself!**

![enter image description here](https://raw.githubusercontent.com/SparkingStudio/I2C_LCD/master/images/I2C_LCD_InstalLib_7.jpg)

**PS:**

1. For more details about library install please refer to [http://www.arduino.cc/en/Guide/Libraries](http://www.arduino.cc/en/Guide/Liaries).
2. If you encounter other problems during the use, please refer to the User Manual for help. If you can't solve it, please contact us.

## Resources

Keeping update the latest version.

The [repository of Arduino library hosted here](https://github.com/SparkingStudio/I2C_LCD_library), if you have any good idea of the code, you can pull to us.

* [I2C\_LCD Library](https://github.com/SparkingStudio/I2C_LCD/blob/master/resources/I2C_LCD_Library.zip)
* [I2C\_LCD User Manual EN](https://github.com/SparkingStudio/I2C_LCD/blob/master/resources/I2C_LCD-UserManual_EN.zip)
* [I2C\_LCD User Manual 中文](https://github.com/SparkingStudio/I2C_LCD/blob/master/resources/I2C_LCD-UserManual_CN.zip)
* [BitmapConverter\(ForWindows\)](https://github.com/SparkingStudio/I2C_LCD/blob/master/resources/Bitmap%20Converter.rar)
* [BitmapConverter\(ForMacOS\)](https://github.com/SparkingStudio/I2C_LCD/blob/master/resources/Bitmap%20Converter.dmg)
* [BitmapConverter\(ForLinux\)](https://github.com/SparkingStudio/I2C_LCD/blob/master/resources/Bitmap%20Converter.tar.gz)
* [I2C\_LCD\_SourceFile](https://github.com/SparkingStudio/I2C_LCD/blob/master/resources/I2C_LCD12864_SourceFile.zip)

