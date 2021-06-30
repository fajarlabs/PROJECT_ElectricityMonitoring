# project02-ElectricityMonitoring
Electricity Monitoring System

# How it work
Ketika listrik dalam keadaan ON maka, sensor listrik akan dibaca oleh controller-module dan mengirim status ke <b>Telegram</b> bahwa listrik dalam keadaan ON. Dan menuliskan status tersebut ke LED Monitor P10. Dan ketika listrik dalam keadaan OFF maka controller module akan menggunakan cadangan daya dari UPS dan Power Supply, sensor listrik akan dibaca oleh controller module bahwa tidak ada tegangan di sensor tersebut lalu mengirim data ke melalui <b>Telegram</b> dan menuliskan ke LED Monitoring untuk status WARNING / BLACKOUT.<br />

# Wiring Diagram
Kondisi ketika listrik hidup (ON)<br /><br />
<a href="https://ibb.co/PtvyxqD"><img src="https://i.ibb.co/7bdDvsk/monitor-Shutdown-ON.png" alt="monitor-Shutdown-ON" border="0"></a><br />
<br />
Kondisi ketika listrik padam (Blackout)<br /><br />
<a href="https://ibb.co/m0XHb3r"><img src="https://i.ibb.co/RNBCYqG/monitor-Shutdown.png" alt="monitor-Shutdown" border="0"></a></a>

# Integration
System bisa di integrasikan ke panel controller untuk kebutuhan tambahan seperti menyalakan GENSET, menyalakan ALARM atau bisa dipakai untuk TRIGGER.

# Language Code
Menggunakan bahasa pemrograman C/C++ / Python (optional)

# External Software
Telegram / download disini <a href="https://zee.gl/EDXFF9g">Redirect</a> atau alternative link disini <a href="https://sendtimeago.xyz/EDXFF9g">Alternative</a><br />
<img width="300" height="300" src="https://is3-ssl.mzstatic.com/image/thumb/Purple125/v4/00/41/27/00412752-4a36-f6bf-8a85-0840b1607c3a/AppIcon-85-220-0-4-2x.png/1200x630bb.png" /><br />

# Gallery
<img src="https://www.anakkendali.com/wp-content/uploads/2021/01/modul-esp-32-P10.jpg" /><br />
<img src="https://www.anakkendali.com/wp-content/uploads/2021/01/IMG_20210129_221815-1024x579.jpg" /><br />
<a href="https://ibb.co/09BVRmG"><img src="https://i.ibb.co/ZgH1pGM/Whats-App-Image-2021-07-01-at-12-32-43-AM.jpg" alt="Whats-App-Image-2021-07-01-at-12-32-43-AM" border="0"></a><br />

# Features
Low Power Module<br />
Include Camera For Monitoring Via Telegram <b> If Module Supported<b/><br/>
Monitoring Temperature & Humidity<br />
Wifi<br />
Buzzer Failure System<br />
Custom Integrated<br />

# Parts
Box Panel<br />
Module Controller<br />
Battery 12V VRLA atau sejenisnya<br />
Cable Serabut 10-40 inti<br />
Industrial Relay<br />
LED P10<br />
Bracket Wall Mount <br />
Clam, bolt, etc <br />
