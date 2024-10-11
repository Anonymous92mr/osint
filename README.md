Skip to content
Navigation Menu

Code
Issues
6
A Complete Osint Tool 🔍

lucksi.github.io/mr.holmes/
License
 GPL-3.0 license
Security policy
 Security policy
 1.7k stars
 199 forks
 33 watching
 2 Branches
 15 Tags
 Activity
Public repository
Lucksi/Mr.Holmes
Folders and files
Name	
Latest commit
Lucksi
Lucksi
last month
History
Banners
2 years ago
Configuration
3 years ago
Core
last month
Display
2 years ago
Documentation
10 months ago
GUI
last year
Icon
last year
Lang
last year
Launchers
last year
Logs
2 years ago
View all files
Repository files navigation
README
GPL-3.0 license
Security


      

🔍 Mr.Holmes
Mr.Holmes is a information gathering tool (OSINT). The main purpose is to gain information about domains,username and phone numbers with the help of public source avaiable on the internet also it use the google dorks attack for specific researchers. It also use proxies for make your requests completley anonymous and a WhoIS Api for getting more information about a domain.

❗ DISCLAIMER
This Tool is Not 100% Accurate so it can fail somtimes. Also this tool is made for educational and research purposes only, i do not assume any kind of responsibility for any imprope use of this tool.

SCREENSHOT
Screenshot





✔️ INSTALLATION LINUX/MAC:
git clone https://github.com/Lucksi/Mr.Holmes
cd Mr.Holmes
sudo apt-get update
sudo chmod +x install.sh
sudo bash install.sh

✔️ INSTALLATION LINUX/MAC (Venv Enviroment):
if you encounter some errors in the python libraries installation use this method

git clone https://github.com/Lucksi/Mr.Holmes
sudo apt-get update
cd Mr.Holmes
python3 -m venv .lib_venv
sudo chmod +x install.sh
sudo bash install.sh
source .lib_venv/bin/activate
pip3 install -r requirements.txt
python3 MrHolmes.py

✔️ INSTALLATION WINDOWS (1°WAY)
If you have git installed on your windows machine you can do the following commands:

git clone https://github.com/Lucksi/Mr.Holmes
cd Mr.Holmes
Install.cmd

✔️ INSTALLATION WINDOWS (2° WAY):
If you download the zip file of Mr.Holmes you should first unzip it and after that do the following commands:

ren Mr.Holmes-master Mr.Holmes
cd Mr.Holmes
Install.cmd

✔️ INSTALLATION TERMUX:
pkg install proot
git clone https://github.com/Lucksi/Mr.Holmes
cd Mr.Holmes
proot -0 chmod +x install_Termux.sh
./install_Termux.sh

USAGE LINUX/MAC:
cd Mr.Holmes
sudo python3 MrHolmes.py
OR:
cd Mr.Holmes
cd Launchers
Execute Launcher.sh

USAGE LINUX/MAC(Venv Enviroment):
cd Mr.Holmes
source .lib_venv/bin/activate
python3 MrHolmes.py

USAGE TERMUX/WINDOWS:
python3 MrHolmes.py

USAGE WINDOWS:
python MrHolmes.py
OR
cd Launchers
Execute Win_Launcher.exe

API KEY LINK:
https://whois.whoisxmlapi.com

SETTINGS FOLDER:
Configuration/Configuration.ini

❗ ATTENTION
DATABASE NOT AVAIABLE ON TERMUX

❗ ATTENTION ON WINDOWS
IF PYTHON AND PHP WONT INSTALL YOU HAVE TO DOWNLOAD THEM MANUALLY:


VERSIONS LIST:
https://lucksi.github.io/Mr.Holmes/Pages/versions.html

✔️ GUI DARK/LIGHT MODE:
cd GUI
cd Theme
edit Mode.json
write:Light=(Light-Mode)
write:Dark=(Dark-Mode) 
write:High-Contrast(High-Contrast-Mode)

✔️ Mode.json CODE EXAMPLE:
{
    "Color": {
        "Background": "Light"
    }
}

✔️ GUI/USERNAME/PASSWORD:
cd GUI
cd Credentials
edit Login.json
write:Status=Active/Deactive
edit Users.json
write:Username=Your Username
write:Password=Your Password

✔️ Login.json CODE EXAMPLE:
{
    "Database": {
        "Status": "Active"
    }
}

✔️ Users.json CODE EXAMPLE
{
    "Users":[
        {
            "Username": "Your Username",
            "Password": "Your Password"
        }
    ]
}

✔️ LANGUAGE SETTINGS:
cd GUI
cd Language
edit Language.json

✔️ Language.json CODE EXAMPLE:
{
    "Language": {
        "Preference": "English"
    }
}

DEFAULT USERNAME AND PASSWORD:
Username:Admin
Password:Qwerty123

AVAIABLE LANGUAGES:
Italiano 🇮🇹 
English 🏴󠁧󠁢󠁥󠁮󠁧󠁿
Français 🇫🇷

ACTUAL VERSION:
T.G.D-1.0.4

INTERACTIVE MAP HAS BEEN MADE WITH:
Leaflet: https://leafletjs.com


USERNAME ENTITIES:
The Icons on Folder: /GUI/Icon/Entities/Site_Icon have been taken from: https://www.iconfinder.com/ all credit goes to their respective creators


ENCODING:
With this version it is Possible to Encode your reports


DECODING:
With this version it is Possible to Decode your reports


HYPOTHESIS
This new version Permits to generate some "Hypothesis" on the subject in base of their numbers on varios social media including possible hobbies/interests (It may not be a 100% attendible)


EMAIL-LOOKUP:
With this new version is possible to check if an email is connected to some specific socials/services without letting the target know it.


GRAPHS:
With this new version has been added the possibility to create Graphs in order to create a schema for information scheduling.


EXAMPLE:
Screenshot


MAPS:
With this new version has been added the possibility to create Interactive Maps.


EXAMPLE:
Screenshot


DORKS:
With this new version it is possible to search Video/Sound/Images via Dorks (1) and to effectuate specific research adding date ex '1998/01/1' or date range ex '1998/01/01-2020/12/31' (2).


EXAMPLE (1):
Screenshot


EXAMPLE (2):
Screenshot


PDF:
With this new version has been added the possibility to converte your Graphs in PDF.


EXAMPLE:



AVAILBLE PDF-THEMES:
Light 🌕
Dark 🌗
High-Contrast 🌗

FILE-TRANSFER:
With this version it is Possible to Transfer your reports directly to Your Phone Via Qr-Code


FILE-TRANSFER PAGE:



🌗 DARK MODE:
Screenshot





🌕 LIGHT MODE:
Screenshot





🌗 HIGH-CONTRAST MODE:
Screenshot





STARGAZERS OVER TIME

Stargazers over time


MADE WITH ❤️ BY LUCKSI IN 🇮🇹

ORIGINAL CREATOR: LUCA GAROFALO (Lucksi)

LICENSE: GPL-3.0 License
COPYRIGHT: (C) 2021-2024 Lucksi

Releases 13
T.G.D
Latest
on Mar 21, 2023
+ 12 releases
Deployments
23
 github-pages 3 years ago
+ 22 deployments
Languages
Python
49.8%
 
PHP
22.5%
 
CSS
12.3%
 
JavaScript
10.3%
 
Shell
3.0%
 
PowerShell
1.7%
 
Other
0.4%
Footer
© 2024 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact
Manage cookies
Do not share my personal information
