# Cybersecurity 150 Final Project

## Name of Project
ESP32 Packet Sniffer
## Purpose
Create an ESP32 project using the ESP32CAM.

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)
* Kali Linux Virtual Machine

## Sources
https://github.com/spacehuhn/ArduinoPcap/tree/master

https://www.youtube.com/watch?v=_GQMZg_5FPE

## Purpose
Wi-Fi sniffing allows you to capture and analyze Wi-Fi packets in the air. This can be used for various purposes, including monitoring network traffic, analyzing network performance, and detecting unauthorized access points. In this case you can use the ESP32 promiscuous mode to capture packets from nearby WiFi networks, extract information such as MAC addresses, signal strength, and data payloads, SSIDs and analyze this information using Wireshark to gain insight into network activity. This can be useful for network troubleshooting, security auditing, and optimizing Wi-Fi network performance. 




## Steps
Note your problems or errors here.  Google any error you may come across, and not what you tried (even if it does not work), and what was the final answer.

Example
1. Arduino code will not load on ESP32 Cam.
   Answer: Wifi Library was outdated
