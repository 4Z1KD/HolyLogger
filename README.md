<h1>Holyland Log Application</h1>

**A super simple, one click, easy to use logging application for Holyland contest participants.**<br>

The main screen is simply a set of the required fields in a qso.<br>
Insert the dx station callsign, update the exchange field and hit F1 - That's it!
<img width="1106" height="677" alt="Image" src="https://github.com/user-attachments/assets/e98a7fb3-28b7-46a5-93f0-ef517fb52896" />

<h2>Log Import / Export / Send</h2>

<img width="1106" height="677" alt="2" src="https://github.com/user-attachments/assets/72a6758e-4699-4775-a3ae-36a37163ba78" />

**_File->Import ADIF_**<br>
If for some reason, you did not use HolyLogger during the contest, but still want to benefit from its amazing features - mainly the score calculation and "Send Log" - you may import your log, in ADIF format *(.adi)*

**_File->Export ADIF/CSV_**<br>
Generates a clean and readable ADIF format *(.adi)* log file you can import into your favorite Log applications.<br>
You may also export to CSV format *(.csv)*.<br>

**_File->Send Log_**<br>
You may choose to upload your log file directly from HolyLogger, in this case the data is sent to the contest server and no file is generated.<br>

<h2>HolyLogger Tools</h2>

<img width="1106" height="677" alt="3" src="https://github.com/user-attachments/assets/b1a9218e-343d-41ef-aa26-c05eb7cedd4d" />

**_Tools->Clear Log_**<br/>
Delete the entire log. Use it when you want to start a fresh log. HolyLogger will create a backup ADIF file if you ever want to restore your QSOs.<br/>

**_Tools->Manual Mode_**<br/>
Normally, HolyLogger will insert the current date and time to a new QSO but if for some reason you want to insert a bunch of QSO out of sync, it is usefull to ask the application not to update the date and time fields, and let you do that manually.<br/>

**_Tools->Reset QSO Counter_**<br/>
The QSO Counter helps you keep track of the recenet QSOs. Every new QSO is added to the counter and the total count is presented on the status bar at the bottom of the screen. If you want to reset the counter, click this button<br/>

**_Tools->Full-Log QRZ Service_**<br/>
This option is usefull when you import a log file from an external logger. It will go through every QSO and if the name is missing, it will try to retrieve it from QRZ.COM<br/>

**_Tools->Remove Duplicates_**<br/>
A "Duplicate" is when you have 2 QSOs with the same DX station on the same band and in the same mode. This option will delete one.

<h2>QRZ.COM Subscription</h2>
**_Tools->Options->QRZ Service_**<br>To take advantage of the qrz.com xml subscription, fill in your _QRZ.COM_ credentials. It will allow HolyLogger to get information and display the name and the dxcc entity of the DX station.

<img width="566" height="493" alt="image" src="https://github.com/user-attachments/assets/de2b8749-1e79-486c-a2a4-5e2f12fcc269" />

<h2>Omni-Rig</h2>
Omni-Rig is a COM component for transceiver/receiver CAT control.<br>
If installed, HolyLogger uses omnirig to communicate with the radio - it just sends frequency and mode requests to automatically update the frequency and mode fields in the log.<br>
It is available for <a href="http://www.dxatlas.com/OmniRig/Files/OmniRig.zip" target="_blank">download</a> from <a href="http://www.dxatlas.com/omnirig/" target="_blank">dxatlas.com</a>

![image](https://user-images.githubusercontent.com/24712835/143572616-4b1507fb-4de4-415b-8867-2950a86b4e69.png)

<h1>Download</h1>
<a href="https://github.com/4Z1KD/HolyLogger/raw/master/HolyLogger_x86.msi" target="_blank">HolyLogger_x86.msi</a> - Microsoft Installer file (x86)<br>

<h2>Installation</h2>
Double-Click *HolyLogger_x86.msi* and the wizard will guide you through the installation process.

<h2>My Holyland Square</h2>
Q: How do I figure out what is my holyland square?<br>
A: Try this <a href="https://www.iarc.org/holysquare/" target="_blank">online tool</a> or download the .APK file (for Android users) from the <a href="https://4z1kd.github.io/HolySquare/" target="_blank">app website</a>.

<h2>Authors</h2>
Consulting and QA: **_<a href="https://www.qrz.com/db/4z5sl" target="_blank">Dan, 4Z5SL</a>_**<br>
Design and Code: **_<a href="https://www.qrz.com/db/4z1kd" target="_blank">Gil, 4Z1KD</a>_**<br>
<br>
Many others have also contributed to the quality of the application with a good advice, bug hunting and feature requests.<br>

<h2>License</h2>
The application is FREE for use by amateur radio operators.

<h3>Maintenance</h3>
Last Update: 04/10/2024<br>

<script>
var list = document.getElementById("logo");
list.outerHTML = '<img src="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger%20icon.png" width="156px" style="position:absolute; top:-80px;right:10px;background:transparent"/>';
</script>
<img src="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger%20icon.png" width="1px" style="display:none;"/>
