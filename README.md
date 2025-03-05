# Wifi2Flipper
Allows local storage of info to Flipper Zero.

 Title: WiFi Passwords Extractor
 
 Author: Jeffrey Koopman | JKCTech
 
 Link: https://github.com/jkctech/Flipper-Zero-Scripts/blob/main/badusb/Passwords/WiFi_Passwords_Win.txt

 Title: Wait For Drive Example
 
 Author: emptythevoid
 
 Link: https://github.com/emptythevoid/flipperzero/blob/main/badusb/read-from-flipper-disk-image/wait-for-drive-example.txt

 Edited To Suit By Skrimbo_Jones
 
 This will make a file containing the active wifi network name and password of the device connected to. It will wait until you use the Mass Storage app on the 
 Flipper Zero to open a .img file with the name, "MAXUS", in the explorer. This can be edited to whatever you wish. 
 It then moves the wifi_passwords_[CURRENTUSERNAME].txt to the drive and deletes it from the system.
 
 I take no credit for this code. I only combined and tweaked it. 
 
 Please acknowledge the true creators. 
 
 ~Skrimbo_Jones
 
 NOTE You switch to the Mass Storage app once the BadUSB script reads 100%.
