# Rift Vision

## Overview
**Rift Vision** is an automatically updating overlay designed for League of Legends streamers.

![image](https://github.com/Stamp1t/rift-vision/assets/132808663/6376963c-6fcc-44e0-9ceb-38a840e523dd)

## Features
The overlay will show your current name, division, link to your op.gg, your session stats, which is wins/losses, and your session winrate.
The program will reset the stats at 6AM.

## Technologies Used
### Languages
- Python
- JavaScript
- HTML
- CSS

### Modules
- websockets
- obswebsocket

## How to Set Things up
To get started with Rift Vision, please follow these steps:

1. **Install OBSWebSocket:**
   - First, you need to download and install OBSWebSocket. It's a component that enables communication between OBS Studio and Rift Vision. You can download it [here](https://github.com/obsproject/obs-websocket/releases). If you are using windows, use the "...Windows-Installer.exe"

2. **Download Rift Vision:**
   - Next, download the Rift Vision application. You can download it [here](https://www.mediafire.com/file/26k4s2t33t7h1ng/Rift_Vision.zip/file)
   - Make sure to extract the files from the zip file to another folder.

3. **Install OBS:**
   - You will need to use OBS as your streaming software.

## Getting Started
Once you have installed OBSWebSocket, you should locate the WebSocket server settings(4.x Compat) within OBS under "Tools". Ensure that the "Enable WebSockets Server" option is checked. Then, remember your server port and set a password.

After these settings are configured in OBS:

1. Run the `Rift Vision.exe` file.
2. A settings window will open where you need to enter the following information:
   - **Riot ID:** Enter your Riot ID, e.g., Player123#EUW.
   - **Queue Type:** Select the desired queue type.
   - **Riot API Key:** Enter your Riot API key, which can be found [here](https://developer.riotgames.com/). Note that the Riot API Key must be renewed every 24 hours, which can be done on the same page using the "Regenerate API Key" option.
   - **OBS Server Port:** Enter the server port noted from the OBS settings.
   - **OBS Server Password:** Enter the password you set in OBS.
   - **Scene Name:** Enter the name of the OBS scene where you want to add the overlay.
3. After entering all the required information, click 'Save' and start the program.
4. Make sure that OBS is started whenever you start the program!

After a few seconds, the overlay should be shown in OBS. You can adjust the size and position according to your preferences.

*IMPORTANT:* You should always wait about 30 seconds after renewing your API Key and not start the program immediately. Also keep in mind to renew your API Key every 24 Hours because the Program will not work if the Key is outdated.


