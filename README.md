# Oracle ANKI Integrated Cloud Demo
## Overview & Intent
#### Data Comes From Activity. Data is Getting Faster
This demo aims to showcase the possibilities of Internet of Things by tapping in to multiple stream of activities that are happening on the Anki Overdrive Race Track and turning it into a source for new data capital and orchestrating data in action.

#### IoT Connecting the Physical to Digital
Out-of-the-box Anki Overdrive Race Track game play involves smart cars controlled by smart devices paired via Bluetooth. Car data, or “telemetry” is sniffed using a Raspberry Pi that is deployed trackside on the Anki Overdrive Race Track. The Pi connects to Oracle IoT Cloud Service to stream events that are happening on the track.

#### Data Creates More Data. Data In Action
Oracle IoT Cloud Service manages the event streams and routes it to connected target systems, e.g. Oracle Database Cloud, Oracle Process Cloud, Oracle Analytics Cloud, Oracle Big Data Cloud. Data in Action is demonstrated by launching a Mini Drone or Emergency Service vehicle in case of a Car Off Track Emergency Event.

#### Integrated Services
By putting to use Oracle’s cloud technologies such as Load Balancing, API Cloud and Identity Management.. mobile services, including management and Augmented Reality are enabled. Further enhanced by adding capabilities such as Voice (using Alexa) and JS frameworks, users can interact with the cars and data like never before!

## Shopping List
* Raspberry Pi 3 Model B+
* 16GB SD Card (image to be supplied by Oracle)
* Case + Power
* Anki Overdrive Starter Kit

Also required, are:
* a large screen (depending on the event and audience)
* Wifi (Internet Connectivity)
* Laptop, or Tablet with Internet browser to “run” the demo
* Possible additional browser for the dashboards and demo screens (displayed on the large screen)
* Table top big enough to host the track. Absolute minimum is 800x1400mm. Recommend 1900x1900 (2x trestle tables), slightly elevated with a table cloth and fake grass for a slightly more professional look

## Step by Step
* Download latest Image from FTP site
ftp://ftp.opcau.com/anki/v6

For Raspberry Pi image, please download OracleAnkiPi6.1.4.img
For Virtualbox .ova image, please download OracleAnkiVM6.1.5.ova
* Pi – Burn Image to SD Card
* VM – Import Image to VirtualBox
* Configure Wifi Pi
* Configure Wifi VM
* Edit RegInfo.txt (reboot)
* Access the hosted Anki Node Drive Webpage
* Enjoy!

## Architecture
BTLE Car > Pi3B+ BTLE > Event Hub (Kafka) > OSA (Spark) > Database > Autonomous Data Warehouse > Analytics
Additionally, data is forwarded to IOT Apps
REST Services and SSL are terminated using Load Balancer, and API Cloud Service
Authentication is enabled with IDCS (device authentication via IOTCS)
Education
We have created an Oracle Anki Learning environment.
http://edu.opcau.com/

There are exercises here that use the TotalJS Flow framework to interact with the demo.
From completely beginner exercises, turning lights on and off, to complex traffic management, the possibilities are endless.

## Links
* The video [https://www.youtube.com/watch?v=QD5v7Fgh3Tk](https://www.youtube.com/watch?v=QD5v7Fgh3Tk)
* The Software [ftp.opcau.com/anki/v6](ftp://ftp.opcau.com/anki/v6)
* The code (you do not need this) [https://github.com/opcau/anki](https://github.com/opcau/anki)
* The instructions [https://opcau.github.io/anki/oracle-demo](https://opcau.github.io/anki/oracle-demo)
* The Dashboards [http://anki.opcau.com/apex/pdb1/f?p=22790:28](http://anki.opcau.com/apex/pdb1/f?p=22790:28)
* Analytics (you will need a log in) [https://analytics.opcau.com/dv/ui/home.jsp](https://analytics.opcau.com/dv/ui/home.jsp)

## Images
![Banner](https://opcau.github.io/anki/images/1604IMG_5226_Anki.jpg)
![Layout](https://opcau.github.io/anki/images/20170919_105622.jpg)
![Dashboard](https://opcau.github.io/anki/images/20180309_132711.jpg)
![Dashboard](https://opcau.github.io/anki/images/IMG_20180410_133814.jpg)

## Social Media
* [LinkedIn](https://www.linkedin.com/search/results/content/?keywords=oracle%20anki&origin=SWITCH_SEARCH_VERTICAL)
* [Twitter](https://twitter.com/search?f=tweets&vertical=default&q=oracle%20anki&src=typd)
* [Youtube](https://www.youtube.com/results?search_query=oracle+anki)
* [Photo Album](https://goo.gl/photos/Ba7dqqPfmgX37vbv6)
