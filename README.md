# Torinstaller
Install TorBrowser On Your Kali Linux_64bit<br/>
<code>git clone https://github.com/JoyGhoshs/Torinstaller/</code><br/>
<code>cd Torinstaller</code><br/>
<code>chmod +x tor_64bit</code><br/>
<code>./tor_64bit</code><br/>
now Open The Extracted folder and goto browser after that find start-tor-browser and open it with leafpad or other text editor find this line 
<b>
if [ "`id -u`" -eq 0 ]; then
	complain "The Tor Browser Bundle should not be run as root.  Exiting."
	exit 1
fi
  </b>
and delete it<br/>
goto tor-browser_en-US and open terminal
Now type ./start-tor-browser.desktop now the tor browser will lunch
#Tuitorial
[![Watch the video](https://zdnet3.cbsistatic.com/hub/i/r/2016/08/04/a57fed16-0f30-4603-8f22-607c76db6090/resize/370xauto/bb986cb5caff70be7673a1334dff603c/screen-shot-2016-08-04-at-09-23-21.jpg)](https://youtu.be/Qv9OFS3M2to)
