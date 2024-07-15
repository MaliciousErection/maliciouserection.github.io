---
title: Tools
---

We currently help develop the following tools:

## YayPentestMagiskModuleYay

[https://github.com/MaliciousErection/YayPentestMagiskModuleYay/releases](https://github.com/MaliciousErection/YayPentestMagiskModuleYay/releases)

A Magisk module that does the following:

* Moves user-installed root CAs into the system certificate store
	* Compatible with devices running Android 7 (Nougat) up to Android 14
	* The module will detect which version of Android your device is running
* Launches a Frida server on boot, and restarts the Frida server when the server crashes
	* NOTE: We've seen some issues with running Google Chrome while running the Frida server
	* If you want to run Google Chrome, then don't install this module until we build a better solution

## Drozer Agent Malicious Erection

[https://github.com/MaliciousErection/drozer-agent-maliciouserection/releases](https://github.com/MaliciousErection/drozer-agent-maliciouserection/releases)

A fork of the Drozer tool offered by WithSecure. This version of Drozer Agent will start the Drozer server automatically when the application starts.

Malicious Erection's founder, Ken Gannon, is an active contributor to the Drozer project.