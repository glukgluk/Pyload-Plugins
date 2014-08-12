<h1>LinkCryptWS V0.03 [Crypter for pyload]</h1>
Update to V0.03 - 11.8.2014 

-------------------

<b>English</b><br>

Function:<br>
Add support for linkcrypt.ws to pyload<br>
If the Linkcrypt.ws folder is password protected, type the password to the unrar password field<br>
KeyCaptcha is actualy not supported. The most Folders haven't just this Captchas so the plugin retry it 4 times. If it didn't work, retry it. 

----------------------------
<b>Deutsch</b><br>

Funktion:<br>
Fügt den Support von Linkcrypt.ws zu pyload hinzu. <br>
Wenn ein Ordner Passwort geschützt ist, kann das Passwort über das unrar Passwortfeld mitgegeben werden. <br>
KeyCaptcha wird momentan noch nicht unterstützt. Da LinkCrypt aber meistens 3 Chapta Methoden verwendet wird es 4 mal (mit 30sec Abstand) versucht. Sollte es nicht gehen, kann ein Reload helfen.<br>
KeyCaptcha versuche ich noch einzupflegen.

------------------------
<b>Changelog</b> <br>
V0.03: Add fallback to link decryption for windows users with jse problems <br>
V0.02: Debug and rewrite the very old and bugy Version 0.01


------------------------
<b>Install:</b><br>
Downoad the file <a href="https://raw.githubusercontent.com/glukgluk/Pyload-Plugins/master/LinkCryptWS.py">LinkCryptWS.py</a><br> 
Put it in the folder ~/pyload/userplugins/crypter/<br>
Restart pyload<br>
Try it
