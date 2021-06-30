# project02-ElectricityMonitoring
Electricity Monitoring 

# How it work
Ketika listrik dalam keadaan ON maka, sensor listrik akan dibaca oleh controller-module dan mengirim status ke <b>Telegram</b> bahwa listrik dalam keadaan ON. Dan menuliskan status tersebut ke LED Monitor P10. Dan ketika listrik dalam keadaan OFF maka controller module akan menggunakan cadangan daya dari UPS dan Power Supply, sensor listrik akan dibaca oleh controller module bahwa tidak ada tegangan di sensor tersebut lalu mengirim data ke melalui <b>Telegram</b> dan menuliskan ke LED Monitoring untuk status WARNING / BLACKOUT.<br />

# Wiring Diagram
Kondisi ketika listrik hidup (ON)<br /><br />
<a href="https://ibb.co/n77btMZ"><img src="https://i.ibb.co/ZBBV7zt/monitor-Shutdown-OFF.png" alt="monitor-Shutdown-OFF" border="0"></a><br />
<br />
Kondisi ketika listrik padam (OFF)<br /><br />
<a href="https://ibb.co/PtvyxqD"><img src="https://i.ibb.co/7bdDvsk/monitor-Shutdown-ON.png" alt="monitor-Shutdown-ON" border="0"></a>
