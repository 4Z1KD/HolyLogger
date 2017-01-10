<h1>Holyland Logger</h1>

**A super simple, one click, easy to use logging application for Holyland contest participants.**<br>

The main screen is simply a set of the required qso fields.<br>
Insert the dx station callsign, update the exchange field and hit F1 - That's it!
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger.png" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger.png?raw=true "HolyLogger Main Screen")
</a>

<h2>Log Export</h2>
**_File->Export_** generates a clean and readable ADIF format *(.adi)* log file - ready to upload to the contest website<br>
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/export.png" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/export.png?raw=true "HolyLogger Main Screen")
</a>

<h2>The Signboard</h2>
**_Tools->Signboard_** will display your callsign and grid on a clean, seperate window so it is always there for you to take a look<br>
<a href="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/Signboard.png" target="_blank">
![Alt text](https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/Signboard.png?raw=true "HolyLogger Main Screen")
</a>

<h2>QRZ.COM Subscription</h2>
To take advantage of the qrz.com xml subscription, open the *.config* file and update your user name and password.<br>

```javascript
<setting name="qrz_username" serializeAs="String">
  <value>Your_QRZ_UserName</value>
</setting>
<setting name="qrz_password" serializeAs="String">
  <value>Your_QRZ_Password</value>
</setting>
```

<h2>Omni-Rig</h2>
<a href="http://www.dxatlas.com/omnirig/" target="_blank">omnirig</a> is a COM component for transceiver/receiver CAT control.<br>
If installed, HolyLogger uses omnirig to communicate with the radio - it just sends frequency and mode requests to automatically update the frequency and mode fields in the log.

<h2>Download</h2>
<a href="https://github.com/4Z1KD/HolyLogger/archive/master.zip" target="_blank">Download HolyLogger</a>

<h2>My Holyland Square</h2>
Q: How do I figure out what is my holyland square?<br>
A: Try this <a href="https://www.iarc.org/iarc/getmysquare.html" target="_blank">online tool</a><br>

<h2>Author</h2>
Design and Code: **_Gil, 4Z1KD_**

Created: 2016-2017<br>


<script>
var list = document.getElementById("logo");
list.outerHTML = '<img src="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger%20icon.png" width="156px" style="position:absolute; top:-80px;right:10px;background:transparent"/>';
</script>
<img src="https://raw.githubusercontent.com/4Z1KD/HolyLogger/master/Images/HolyLogger%20icon.png" width="1px" style="display:none;"/>
