<h1>Holyland Logger</h1>

**A super simple, one click, easy to use logging application for Holyland contest participants.**<br>

The main screen is simply a set of the required qso fields.<br>
Insert the dx station callsign, update the exchange field and hit F1 - That's it!
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger.png" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger.png?raw=true "HolyLogger Main Screen")
</a>

<h2>Log Export / Upload</h2>
**_File->Export_**<br>Generates a clean and readable ADIF format *(.adi)* log file you can import in your other Log applications.<br>
The generated file is ready for upload to the <a href="http://www.iarc.org/iarc/#LogUpload" target="_blank">contest website</a>.<br>

**_File->Send Log_**<br>
You may choose to upload your log file directly from HolyLogger, in this case the data is sent to the contest server and no file is generated.<br>
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/export.png" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/export.png?raw=true "HolyLogger Main Screen")
</a>

<h2>The Signboard</h2>
**_Tools->Signboard_**<br>Will display your callsign and grid on a clean, seperate window so it is always there for you to take a look.<br>
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/Signboard.png" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/Signboard.png?raw=true "HolyLogger Main Screen")
</a>

<h2>QRZ.COM Subscription</h2>
**_Tools->properties_**<br>To take advantage of the qrz.com xml subscription, fill in your _QRZ.COM_ credentials. It will allow HolyLogger to get information and display the handle and the dxcc entity of the DX station.<br>
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/qrzcom.png" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/qrzcom.png?raw=true "QRZ.COM credentials")
</a>

<h2>Omni-Rig</h2>
Omni-Rig is a COM component for transceiver/receiver CAT control.<br>
If installed, HolyLogger uses omnirig to communicate with the radio - it just sends frequency and mode requests to automatically update the frequency and mode fields in the log.<br>
It is available for <a href="http://www.dxatlas.com/OmniRig/Files/OmniRig.zip" target="_blank">download</a> from <a href="http://www.dxatlas.com/omnirig/" target="_blank">dxatlas.com</a>


<h2>Download</h2>
<a href="https://github.com/4Z1KD/HolyLogger/raw/master/HolyLogger.msi" target="_blank">Download HolyLogger</a>

<h2>Installation</h2>
Double-Click *HolyLogger.msi* and the wizard will guide you through the installation process.<br>
If you want QRZ.COM lookup to work, don't forget to update your credentials in the settings screen.

<h2>My Holyland Square</h2>
Q: How do I figure out what is my holyland square?<br>
A: Try this <a href="https://www.iarc.org/iarc/getmysquare.html" target="_blank">online tool</a><br>

<h2>Authors</h2>
Consulting and QA: **_<a href="https://www.qrz.com/db/4z5sl" target="_blank">Dan, 4Z5SL</a>_**<br>
Design and Code: **_<a href="https://www.qrz.com/db/4z1kd" target="_blank">Gil, 4Z1KD</a>_**<br>

<h2>Contributing</h2>
Found a Bug? _Don't panic!_<br>
Have a feature request? _No problem!_<br>
Drop me a line at **_gil4z1kd@gmail.com_** and i'll take care of that.

<h2>License</h2>
The application is FREE for non commercial use by Amateur Radio Operators.

<h3>Maintenance</h3>
January 2017<br>


<script>
var list = document.getElementById("logo");
list.outerHTML = '<img src="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger%20icon.png" width="156px" style="position:absolute; top:-80px;right:10px;background:transparent"/>';
</script>
<img src="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger%20icon.png" width="1px" style="display:none;"/>
