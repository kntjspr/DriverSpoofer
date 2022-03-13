# DriverSpoofer
DriverSpoofer is an utility that generates falsified driver data to prevent privacy-invading websites from gathering your device data without actually being detected. 

## Information
Websites nowadays can detect your system information, such as the number of microphones and webcams you have and whether you're utilizing virtual or real ones.
The issue here is that they can tell when you fake those things by inspecting the driver parameters.
When you are identified to have virtual cameras or a spoofing device installed, those websites (typically anti-fraud algorithms) they will flag your machine. 

Screenshot 1: I already spoofed OBS Virtual camera and renamed it into "Logitech Streamcam" by normal methods.
![image](https://user-images.githubusercontent.com/65537922/158051612-979f276d-b8d8-4226-a7fb-f44f6c5c0158.png)

Screenshot 2: But that spoofing method didn't work. The website still detects OBS Cam. why? It looks at your device manager parameters.
![Screenshot](https://user-images.githubusercontent.com/65537922/158051353-2d95836d-dc5c-41f5-9a8b-ea1183940aa0.png)



## Coming Soon
Work in progress. The source code and release will be published soon. 
