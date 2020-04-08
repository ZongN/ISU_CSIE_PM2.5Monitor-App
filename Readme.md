# ISU_CSIE_PM2.5Monitor-App
## Introduction
This is a simple master's class topic. It is a PM2.5 IoT application. 
The architecture is to obtain data through the sensor, then upload the data to the network through IoT development board, and finally use APP to display real-time data to the user. And my part is the mobile interface.

Thank to my classmates Ciou Fang-Kuei, Jhang Jhe-Jhih, Jhao Yan-Ting, Jhu Ming-Hhong for completing this topic together.

## App
This app is programmed in *Java*, and the IDE is *Android studio*. So, if you want to open the whole project, you can open it in the *Android studio*. API of the virtual device needs to be more than 23. The interface of the APP is relatively simple, because I don't have a major in arts.:sweat:

In the top half of the screen, it's a real-time line graph, and the first combobox below is sensor options, then the value of PM2.5, air quality rating, temperature, humidity, and finally update time.

But the most important thing is the web-side has been shut down, so the app can't get data anymore. If you want to rewrite the program, I recommend that you start with the data capture part. And this is what I will do in the future.

![](https://img.shields.io/badge/Android-9.0%20Pie-brightgreen) ![](https://img.shields.io/badge/Android%20studio-3.1.3-blueviolet) ![](https://img.shields.io/badge/API-%3E23.0-ff69b4) 


## Device
| Device            | Model                           | Link |
|:-----------------:|:-------------------------------:|:----:|
| PM2.5 Sensor      | Grove – Air quality sensor v1.3 | [Here](http://wiki.seeedstudio.com/Grove-Air_Quality_Sensor_v1.3/) |
| Development Board | LinkIt™ 7697                    | [Here](http://labs.mediatek.com/en/platform/linkit-7697) |
| Mobile Phone      | Android version 9.0 Pie         | [Here](https://developer.android.com/about/versions/pie) |

## Architecture
<p align="center">
	<img src="https://github.com/ZongN/ISU_CSIE_PM2.5Monitor-App/blob/master/Architecture.png" alt="Sample"  width="35%" height="35%">
	<p align="center"></p>
</p>

### *Unzip the file before use*
