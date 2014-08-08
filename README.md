<h1>Justpremium V0.16 [hook for pyload]</h1>
Update to V0.16 - 8.8.2014 

-------------------

<b>English</b><br>

Function:<br>
If you add multiple links and one of it is from a registered premium hoster, all links from non-premium hosters will automatically be removed.<br>

Example: <br>
A DLC with uploaded.net-, shareonline.biz- and zippyfiles.com-links is added. If you have only an uploaded.net-account, the other two hosters will be removed.<br>

Options:<br>
unblock this hosters (comma seperated): all hosters here (pyloadformat) won't be removed. E.g. use it for your favourite freehoster.<br>
Allow all freehosters and other unknown sites: If this option is activated, only links from hosters available in the pyload "Accounts" list but without account will be removed.

----------------------------
<b>Deutsch</b><br>

Funktion:<br>
Wenn mehrere Links hinzugefügt werden, und sich darunter einer von einem eingetragenem Hoster befindet, dann werden die Links von allen nicht eingetragenen Hostern entfernt.<br>

Beispiel: <br>
Ein DLC mit Uploaded, Shareonline und Zippyfiles wird hinzufügt und man einen Uploaded Account hat, werden die beiden anderen Hoster entfernt.<br>

Optionen:<br>
unblock this hosters (comma seperated): Alle hier eingetragenen Hoster (im pyloadformat) werden nie geblockt. Kann zB für einen Lieblings Freehoster genutzt werden.<br>
Allow all freehosters and other unknown sites: Ist diese Option aktiviert, werden nur die Links von Accounts, die unter "Konten" ausgewählt werden können und nicht registriert sind, entfernt, sonnst werden alle bis auf die registrierten entfernt.

------------------------
<b>Changelog</b> <br>
V0.16: Add better info log (now you see which hosters are removed)<br>
V0.15: Rewrite the whole hook<br>
V0.1: First version

------------------------
<b>Instal:</b><br>
Downoad the file <a href="https://raw.githubusercontent.com/glukgluk/JustPremium/master/JustPremium.py">JustPremium.py</a><br> 
Put it in the folder ~/pyload/userplugins/hooks/<br>
Restart pyload<br>
If it added succesfull you find the plugin on the webinterface under Config -> Plugins -> JustPremium
Activate it

