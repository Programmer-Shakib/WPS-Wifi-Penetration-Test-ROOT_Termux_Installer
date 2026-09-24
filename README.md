# WPS-Wifi-Penetration-Test-ROOT_Termux_Installer
Run WPS-Wifi-Penetration-Test-ROOT Easily
## [WPS-Wifi-Penetration-Test-ROOT](https://github.com/Sakib-BD-PLAYX/WPS-Wifi-Penetration-Test-ROOT) installer for [Termux](https://termux.com/)
### Setup
```
curl -sSf https://raw.githubusercontent.com/Sakib-BD-PLAYX/WPS-Wifi-Penetration-Test-ROOT_Termux_Installer/master/installer.sh | bash
```
### Run
Disable Wi-Fi in the system settings and run:
```
sudo python WPS-Wifi-Penetration-Test-ROOT/wpswifi.py -i wlan0 -K
```
### How to update WPS-Wifi-Penetration-Test-ROOT
To check for updates and update, run the following command:
```
(cd WPS-Wifi-Penetration-Test-ROOT && git pull)
```
