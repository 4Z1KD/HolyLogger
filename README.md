<h1>Holyland Log Application</h1>

**A super simple, one click, easy to use logging application for Holyland contest participants.**<br>

The main screen is simply a set of the required fields in a qso.<br>
Insert the dx station callsign, update the exchange field and hit F1 - That's it!
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger.png" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger.png?raw=true "HolyLogger Main Screen")
</a>

<h2>Log Import / Export / Send</h2>
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/File.PNG" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/File.PNG?raw=true "File toolbar menu")
</a>

**_File->Import_**<br>
If, for some reason, you did not use HolyLogger during the contest, but still want to benefit from its amazing features - mainly the score calculator and "Send Log" - you may import your log, in ADIF format *(.adi)*

**_File->Export_**<br>
Generates a clean and readable ADIF format *(.adi)* log file you can import into your favorite Log applications.<br>
You may also export to CSV format *(.csv)*.<br>

**_File->Send Log_**<br>
You may choose to upload your log file directly from HolyLogger, in this case the data is sent to the contest server and no file is generated.<br>

<h2>Visualization</h2>
You may enjoy 2 helpful extension windows - Signboard and Matrix
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/View.PNG" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/View.PNG?raw=true "View toolbar menu")
</a>

**_View->Signboard_**<br>
Will display your callsign and grid on a clean, seperate window so it is always there for you to take a look.<br>
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/Signboard.PNG" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/Signboard.PNG?raw=true "signboard")
</a>

**_View->Matrix_**<br>
Whenever a new callsign is entered, the Matrix will display a checkmark on the bands and modes you worked.<br>
It will also display a DUP! message if you have already worked this band/mode combination.<br>
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/Matrix.PNG" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/Matrix.PNG?raw=true "matrix")
</a>

*HolyLogger Tools*<br/>
<h3>Clear Log</h3>
Delete the entire log. Use it when you want to start a fresh log. HolyLogger will create a backup ADIF file if you ever want to restore your QSOs.<br/>

*Manual Mode*<br/>
Normally, HolyLogger will insert the current date and time to a new QSO but if for some reason you want to insert a bunch of QSO out of sync, it is usefull to ask the application not to update the date and time fields, and let you do that manually.<br/>

<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/Tools.PNG" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/Tools.PNG?raw=true "Tools")
</a>

<h2>QRZ.COM Subscription</h2>
**_Tools->Options->QRZ Service_**<br>To take advantage of the qrz.com xml subscription, fill in your _QRZ.COM_ credentials. It will allow HolyLogger to get information and display the name and the dxcc entity of the DX station.<br>
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/Options.PNG" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/Options.PNG?raw=true "QRZ.COM credentials")
</a>

<h2>Omni-Rig</h2>
Omni-Rig is a COM component for transceiver/receiver CAT control.<br>
If installed, HolyLogger uses omnirig to communicate with the radio - it just sends frequency and mode requests to automatically update the frequency and mode fields in the log.<br>
It is available for <a href="http://www.dxatlas.com/OmniRig/Files/OmniRig.zip" target="_blank">download</a> from <a href="http://www.dxatlas.com/omnirig/" target="_blank">dxatlas.com</a><br>
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/omnirig.png?raw=true "omnirig")

<h1>Download</h1>
A 32bit version of HolyLogger comes in 2 flavours:<br>
<a href="https://github.com/4Z1KD/HolyLogger/raw/master/HolyLogger_x86.msi" target="_blank">HolyLogger_x86.msi</a> - Microsoft Installer file<br>
<a href="https://github.com/4Z1KD/HolyLogger/raw/master/HolyLogger.zip" target="_blank">HolyLogger.zip</a> - a compressed folder (.zip file)<br>
<br>
Note:<br>
You do **NOT** need to download both files!<br>
<br>
MSI is an installer package file format used by Windows. They are used for installation, storage, and removal of programs. The files are contained in a package, which is used with the program’s client-side installer service.<br>
<br>
The ZIP file contains all the program files, compressed in a folder. Once unzipped, the EXE file inside is ready for execution.<br>

<h2>Installation</h2>
Double-Click *HolyLogger_x86.msi* and the wizard will guide you through the installation process.

If you downloaded the .zip file, just unzip it to your preffered destination e.g. Desktop or C:\ and execute *HolyLogger.exe*

Reminder:<br>
If you want QRZ.COM lookup to work, don't forget to update your credentials in the settings screen.

<h2>My Holyland Square</h2>
Q: How do I figure out what is my holyland square?<br>
A: Try this <a href="https://www.iarc.org/holysquare/" target="_blank">online tool</a> or download the .APK file (for Android users) from the <a href="https://4z1kd.github.io/HolySquare/" target="_blank">app website</a>.

<h2>Authors</h2>
Consulting and QA: **_<a href="https://www.qrz.com/db/4z5sl" target="_blank">Dan, 4Z5SL</a>_**<br>
Design and Code: **_<a href="https://www.qrz.com/db/4z1kd" target="_blank">Gil, 4Z1KD</a>_**<br>
<br>
Many others have also contributed to the quality of the application with good advice, bug hunting and feature requests. I thank you ALL!!<br>

<h2>Contribution</h2>
Found a Bug? _Don't panic!_<br>
Have a feature request? _No problem!_<br>
Drop me a line at **_4z1kd@iarc.org_** and i'll take care of that.

<h2>Donation</h2>
I will not mind if you buy me a beer on the next field day.<br>

<h2>License</h2>
The application is FREE for use by amateur radio operators.

<h3>Maintenance</h3>
Last Update: 04/11/2018<br>

<script>
var list = document.getElementById("logo");
list.outerHTML = '<img src="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger%20icon.png" width="156px" style="position:absolute; top:-80px;right:10px;background:transparent"/>';
</script>
<img src="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger%20icon.png" width="1px" style="display:none;"/>
