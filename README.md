# ubuntu-in-termux

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Ubuntu&size=33&duration=555&pause=1&color=97FF00&background=000000&vCenter=true&multiline=true&width=1733&height=500&lines=PRETTY_NAME%3D%22Ubuntu+22.04.5+LTS%22;NAME%3D%22Ubuntu%22;VERSION_ID%3D%2222.04%22;VERSION%3D%2222.04.5+LTS+(Jammy+Jellyfish)%22;VERSION_CODENAME%3Djammy;ID%3Dubuntu;ID_LIKE%3Ddebian;HOME_URL%3D%22https%3A%2F%2Fwww.ubuntu.com%2F%22;SUPPORT_URL%3D%22https%3A%2F%2Fhelp.ubuntu.com%2F%22;BUG_REPORT_URL%3D%22https%3A%2F%2Fbugs.launchpad.net%2Fubuntu%2F%22;PRIVACY_POLICY_URL%3D%22https%3A%2F%2Fwww.ubuntu.com%2Flegal%2Fterms-and-policies%2Fprivacy-policy%22;UBUNTU_CODENAME%3Djammy" alt="Typing SVG" /></a>

[![DISCORD](https://img.shields.io/badge/Chat-On%20Discord-738BD7.svg?style=for-the-badge)](https://discord.gg/Xaqkdeh)

## What's This?

This is a script that allows you to install Ubuntu in your termux application without a rooted device

## Updates

**• Updated to ubuntu 22.04**

## Important

**• If you have to use ubuntu in termux with a x86/i\*86 architecture or prefer ubuntu 19.10 you can use this branch -> https://github.com/MFDGaming/ubuntu-in-termux/tree/ubuntu19.10**

**• If you get an error message that says "Fatal Kernel too old" you have to uncomment the line that reads "command+=" -k 4.14.81"" (remove the # that is located in front of the line) in the "startubuntu.sh" file**

### Installation steps

```
pkg update -y && pkg upgrade -y && apt install wget proot curl git -y && git clone https://github.com/zetaxbyte/ubuntu-in-termux.git && cd ubuntu-in-termux && chmod +x ubuntu.sh && ./ubuntu.sh
```
