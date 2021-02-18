

### What is Tramontana?
Tramonatana is intended as a tool for designers and creatives to use iPhones and iPads as sensors or actuators and create quick interactive prototypes of apps, interactive spaces and objects.

Tramontana is a set of libraries and a iOS and tvOS apps. [Tramontana app](https://itunes.apple.com/us/app/tramontana/id1121069555?mt=8) exposes all the features of your phone to a websocket API that can be used from the open source [javascript](https://github.com/pierdr/tramontana) or [openFrameworks](https://github.com/pierdr/ofxTramontana) library.<br/>

You can use your device as actuator from a webpage or an openframeworks sketch running on a computer or different device. It is possible to trigger over WiFi:<br/>
• flash light;<br/>
• vibration;<br/>
• changes to screen brightness and color:<br/>
• playback of video, audio or images;<br/>
<br/>
Alternatively you can use the device as a sensor reading the device:<br/>
• orientation;<br/>
• magnetometer;<br/>
• accelerometer;<br/>
• distance sensor;<br/>
• audio jack;<br/>
• changes in power source;<br/>
• touch events;<br/>



### Getting started
To get started select your preferred platform, Javascript, openFrameworks or Processing and follow the instructions on the plugin or libraries page.

#####javascript
Please refer to the javascript github page for more informations:
[javascript](https://github.com/pierdr/tramontana)

~~~~ 
			var iphone=new BFtObject();
			iphone.start('192.168.1.2');
			iphone.makeVibrate();
~~~~ 
		

#####openFrameworks
The openFrameworks plugin contains examples that show how you can use your phone as sensor or actuator. More info on the plugin page: [openFrameworks](https://github.com/pierdr/ofxTramontana)

~~~~ 
#include "ofxTramontana.h"
....
ofxTramontanaIOS iphone;
....
iphone.start("192.168.1.2");
iphone.makeVibrate();
~~~~ 

#####Processing
The processing library is currently under development.


