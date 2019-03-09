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
