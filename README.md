# CSCO-server-installer
cscoserver is a command line tool for quick, simple deployment and management of a Counter Strike: Classic Offensive Linux dedicated server.

This script is based on https://github.com/zunnu/CSGO-server-installer

This script does not yet have updater to mod. Updater will only update csgo server not the MOD.
Mod updater will be done later.

<h2>Main features</h2>
<ul>
	<li>Backup</li>
	<li>Console</li>
	<li>Details</li>
	<li>Installer (SteamCMD)</li>
	<li>Monitor (including email notification)</li>
	<li>Update (SteamCMD)</li>
	<li>Start/Stop/Restart server</li>
	<li>Announce Server Restart</li>
	<li>Announce Backup start and end</li>
  <li>Announce Server Shutdown</li>
  <li>Send msg go to server</li>
</ul>

<h2>Usage</h2>
Server restart (fast)
<code>./csgoserver restart fast</code>
This will announce 10 second countdown to restart the server.

Server restart
<code>./csgoserver restart</code>
This will announce 1 minute countdown to restart the server.

Server shutdown (fast)
<code>./csgoserver shutdown fast</code>
This will announce 10 second countdown to shutdown the server.

Send message to server
<code>./csgoserver msg Hello</code>
