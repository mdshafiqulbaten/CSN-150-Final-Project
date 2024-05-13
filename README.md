# Cybersecurity 150 final Spring 2024

## ESP32 Beacon Spam
ESP32 creating fake Access Point

## Purpose
Creating fake Access point to confuse people and doing social engineering

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Link to Documentation Followed
- [ESP32 beacon spam](https://github.com/Tnze/esp32_beaconSpam)

## Steps I followed
1. I have installed Arduino in the desktop.
2. I have installed esp32 in the library.
3. I have selected the board AI thinker ESP32-CAM.
4. I have selected the port no. to the latest.
5. Copied the code in the arduino.
6. Upload that in the system and checked for any error.
7. Since there were no error checked the serial monitor which showed me that the packages were being sent.
8. I checked my computer wifi connection list and found those fake wifi connection list in there.
## Problems
1. When I was connecting the ESP32 with the cable , it was not finding the device. We checked and later on found that the cable was normal charging cable not the data cable. We changed the cable to the data cable and It started working.

2. Since the computer I was using was from the college, It had the firewall setting to not to accept the untrustworthy networks and that is why it was not showing the channels in that computer. When I changed the computer to a private computer, it worked.
## The screenshot of the final result
[Picture](https://github.com/mdshafiqulbaten/CSN150-Midterm-Documentation/blob/main/Screenshot%202024-03-20%20145947.png)
