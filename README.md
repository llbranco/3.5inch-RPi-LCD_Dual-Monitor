LCD driver for the Raspberry PI Installation<br>
====================================================

Ainda em criação, ainda não está pronto pra uso

Baseado no projeto
https://github.com/goodtft/

e nos videos:
https://www.youtube.com/watch?v=zzugiINb3Zo
https://www.youtube.com/watch?v=d2ouG1VmD88 (esse em indonésio)

no pdf
https://drive.google.com/file/d/1-m1Mom41RZn2TwUtbIGZe0G4fIGFuL4Q/view



2017-08-16
Update: <br>
  v1.6-20170824<br>
  Update xserver to support Raspbian-2017-08-16<br><br>
Update: <br>
  v1.5-20170706<br>
  Update to support Raspbian-2017-07-05,Raspbian-2017-06-21<br><br>
Update: <br>
  v1.3-20170612<br>
  fixed to support Raspbian-2017-03-02,Raspbian-2017-04-10<br><br>
Update: <br>
  v1.2-20170302<br>
  Add xserver-xorg-input-evdev_1%3a2.10.3-1_armhf.deb to support Raspbian-2017-03-02<br><br>
Update: <br>
  v1.1-20160815<br><br>
  
1.)Step1, Install Raspbian official mirror <br>
====================================================
  a)Download Raspbian official mirror:<br>
  https://www.raspberrypi.org/downloads/<br>
  b)Use“SDFormatter.exe”to Format your TF Card<br>
  c)Use“Win32DiskImager.exe” Burning mirror to TF Card<br>
     
2.) Step2, Clone my repo onto your pi<br>
====================================================
Use SSH to connect the raspberry pi, <br>
And Ensure that the raspberry pi is connected to the Internet before executing the following commands:
-----------------------------------------------------------------------------------------------------

```sudo rm -rf LCD-show```<br>
```git clone https://github.com/llbranco/3.5inch-RPi-LCD_Dual-Monitor/LCD-show.git```<br>
```chmod -R 755 LCD-show```<br>
```cd LCD-show/```<br>
  
3.)Step3, According to your LCD's type, excute:
====================================================
In case of 2.8" LCD<br>
  ```sudo ./LCD28-show```<br><br>
In case of 3.2" LCD<br>
  ```sudo ./LCD32-show```<br><br>
In case of 3.5" GPIO Display<br>
  ```sudo ./LCD35-show```<br><br>
In case of 3.5" HDMI Display-MPI3508<br>
  ```sudo ./MPI3508_480_320-show```<br>
  or<br>
  ```sudo ./MPI3508_600_400-show```<br>
  or<br>
  ```sudo ./MPI3508_720_480-show```<br>
  or<br>
  ```sudo ./MPI3508_810_540-show```<br>
  or<br>
  ```sudo ./MPI3508_960_640-show```<br><br>
In case of 3.5" DPI Display-MPI3510<br>
  ```sudo ./MPI3510-show```<br><br>
  
In case of 3.97" LCD<br>
  ```sudo ./LCD397-show```<br><br>
In case of 4.3" LCD<br>
  ```sudo ./LCD43-show```<br><br>
In case of 5" LCD<br>
  ```sudo ./LCD5-show```<br><br>
In case of 7inch(B)-800X480 RPI LCD<br>
  ```sudo ./LCD7B-show```<br><br>
In case of 7inch(C)-1024X600 RPI LCD<br>
  ```sudo ./LCD7C-show```<br><br>
If you need to switch back to the traditional HDMI display<br>
  ```sudo ./LCD-hdmi```<br><br>

Wait a few minutes,the system will restart automaticall , enjoy with your LCD.
-------------------------------------------------------------------------------

tela similar com sourcecode e bem documentado
https://github.com/INNO-MAKER/3.5inchlcd-c

tópicos interessantes sobre essa tela
http://www.lcdwiki.com/3.5inch_RPi_Display
https://github.com/juj/fbcp-ili9341
https://discussion.fedoraproject.org/t/raspberry-pi-3-5-lcd-mpi3501/72322/6
https://hub.libre.computer/t/aml-s905x-cc-le-potato-480x320-ili9486-spi-touchscreen-display/183
https://community.volumio.org/t/volumio-with-3-5-tft-touch-screen-gpio-rpi-3b/11265


<br><br>


