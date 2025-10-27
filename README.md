Torn Chain Overlay (v4)
Overview

This userscript adds a large fixed countdown timer overlay for Torn faction chains.
It uses your Torn API key to display and track the chain timer, with optional alerts, sound, and flashing.

Controls

Hotkeys

Shift + =     Increase timer size
Shift + -     Decrease timer size
Shift + C     Manual refresh (forces API update)
Shift + K     Open API key panel
Shift + V     Open alert settings
Shift + T     Test beep


On-screen buttons

+ / –       Adjust size
↻           Manual refresh
Alerts      Opens alert settings panel
Add/Edit API   Opens API key editor

Alert Settings

Open the Alerts panel to change:

Threshold:  Time when alerts begin (mm:ss, e.g. 4:30)
Beep every second:  Toggles sound alerts
Flash background:   Toggles red flashing during alert
Volume:  Adjusts beep loudness (0–100%)
Test:    Plays a sample beep


When the timer reaches the threshold, it will flash and beep every second until the next hit refreshes the timer.

Notes

The Torn API updates roughly every 30 seconds, so short delays after a hit are normal.

The script polls every 10 seconds to stay within safe limits.

All settings (size, volume, threshold, etc.) are saved automatically.

Your API key is stored locally by Tampermonkey and never shared.

Works only for users in a faction with chain access via API.

Install

Install Tampermonkey.

Create a new userscript and paste the full script.

Save it and refresh Torn.

Press Shift + K to add your Torn API key.

Author

Created by AnubisGaming
For Torn players who want a clean, visible, and configurable chain timer overlay.
