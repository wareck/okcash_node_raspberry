<p align="center">
<img src="https://raw.githubusercontent.com/wareck/okcash_node_raspberry/master/docs/images/logo.png">
</p>

----------
# Okcash full autonomous node running on Raspberry Pi ##


This script build "Okcash headless daemon node" (okcashd command line only, for best efficiency) .
This script will download/compile/configure and build all files autonomously . (it take between 1 and 2 hours)
I suggest to use Pi3 or Pi4 otherwise, it will take to much time to synchronise and never staking ...
You can use Raspbian (lite or full, better is to use lite version for efficiency/speed) or DietPi (smaller image, optimized packets)


**Note:**

***Due to the recent database increase, okcash need more power and more memory to works. At the first start, to stakes coin, okcash need enough memory to open database, check blockchain and works on files. Thats why, since april 2020, this node do not work anymore on old Raspberry Pi. I suggest to use a Raspberry Pi4 or higher with a fast sdcard, a SSD drive or a fast USB key. Actually, this software work at home on a raspberry pi4 and a kingston high speed usb key with a 8gb sdcard.***

----------
This script has been extensively tested and still works on my personal node.

Works on Raspberry OS and Dietpi 32 bits

![](https://raw.githubusercontent.com/wareck/okcash_node_raspberry/master/docs/images/software.png)


Works on Raspberry OS 64 bits

![](https://raw.githubusercontent.com/wareck/okcash_node_raspberry/master/docs/images/software2.png)

----------

**Actual softwares/libraries versions :**

**Okcash** : v8.0.2.0 (Github files)

**OpenSSL** :v3.0.2

**LibBoost** :v1.74.0

**libDB** : v4.8.30.NC

**Miniupnpc** : v2.2.3 

----------

**Software installation:**

    git clone https://github.com/wareck/okcash_node_raspberry.git
    cd okcash_node
    ./build.sh

**Extended documentations links:**

 - [lnstall-node](https://github.com/wareck/okcash_node_raspberry/blob/master/docs/install-node.md)
 - [DietPi-build](https://github.com/wareck/okcash_node_raspberry/blob/master/docs/dietpi.md)
 - [Fan-control](https://github.com/wareck/okcash_node_raspberry/blob/master/docs/fan_control.md)
 - [Led-status](https://github.com/wareck/okcash_node_raspberry/blob/master/docs/led-status.md)
 - [Usb](https://github.com/wareck/okcash_node_raspberry/blob/master/docs/usb.md)
 - [Oled LCD](https://github.com/wareck/okcash_node_raspberry/blob/master/docs/oled.md)
 - [RTC-addon](https://github.com/wareck/okcash_node_raspberry/blob/master/docs/rtc.md)

**Donate:**
 - Bitcoin : 1Pu12Wimuy6n7csyHkEjZXGXnAQzKBwSBp
 - Okcash  : PH3JcR9inEeNZD6gNoLDYwaPAFpgjmrbue
 - Litecoin: M84U8YggaJ7T5E3TcqgcoF2BCTaxBMbCvN
