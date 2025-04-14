# CamPhish
# What is CamPhish?
CamPhish is techniques to take cam shots of target's phone front camera or PC webcam. CamPhish Hosts a fake website on in built PHP server and uses ngrok & CloudFlare Tunnel to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device

A GPS location capture feature has been added.

# Features
In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam

- Festival Wishing
- Live YouTube TV
- Online Meeting [Beta]
- GPS Location Tracking
- A cleanup script has been added to remove all unnecessary files and logs.

# This Tool Tested On :
- Kali Linux
- Termux
- MacOS
- Ubuntu
- Parrot Sec OS
- Windows (WSL)
# Installing and requirements
This tool require PHP for webserver, and wget for downloading dependencies. First run following command on your terminal

```
apt-get -y install php wget unzip
```
# Installing (Kali Linux/Termux):
```
git clone https://github.com/techchipnet/CamPhish
```
```
cd CamPhish
```
```
bash camphish.sh
```
# Clean logs & unnecessary files :
```
bash cleanup.sh
```
The cam files and saved location will also be removed.
