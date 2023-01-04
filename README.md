# PhoneSploit Pro
#### PhoneSploit with Metasploit integration.

A hacking script written in `Python 3` to remotely exploit Android devices using `ADB` (Android Debugging Bridge).

This script can automatically __Create__, __Install__, and __Run__ payload to the target device using __Metasploit-Framework__ and __ADB__ to completely hack the Android Device in one click.

# Script Features :
* Connect device using ADB remotely
* List connected devices
* Disconnect all devices
* Access connected device shell
* Stop ADB Server
* Take screenshot and pull it to computer automatically
* List all installed apps in target device
* Download file/folder from target device
* Send file/folder from computer to target device
* Install an APK file from computer to target device
* Run an App
* Uninstall an app
* Screen Record target device screen for a specified time and automatically pull it to computer
* Restart/Reboot the target device
* __Hack Device Completely__ : Automatically create a payload using `msfvenom`, install it, and run it in target device, then automatically launch and setup __Metasploit-Framework__ to get a `meterpreter` session.

Getting a meterpreter session means the device is completely hacked using Metasploit Framework, and you can do anything with it.

# Requirements : 
* [`git`](https://git-scm.com/) : Git
* [`python3`](https://www.python.org/) : Python 3.10 or Newer
* [`adb`](https://developer.android.com/studio/command-line/adb) : Android Debugging Bridge (ADB) from `Android SDK Platform Tools`
* [`metasploit-framework`](https://www.metasploit.com/) : Metasploit-Framework (`msfvenom` and `msfconsole`)

# Run PhoneSploit Pro :

* __PhoneSploit Pro__ does not need any installation and runs directly using `python3`

#### On Linux / macOS :

Open terminal and paste the following commands : 
```
git clone https://github.com/AzeemIdrisi/PhoneSploit-Pro.git

cd PhoneSploit-Pro/

python3 phonesploitpro.py
```
#### On Windows :

Open terminal and paste the following commands : 
```
git clone https://github.com/AzeemIdrisi/PhoneSploit-Pro.git

cd PhoneSploit-Pro/
```

Copy all files from your ADB directory to PhoneSploit-Pro directory and then run :

```
python3 phonesploitpro.py
```


# Install ADB

#### ADB on Linux :

Open terminal and paste the following commands :

__Debian / Ubuntu__
```
sudo apt install adb
```

__Fedora__
```
sudo dnf install adb
```

__Arch Linux / Manjaro__
```
sudo pacman -S adb
```

#### ADB on macOS :

Open terminal and paste the following command :

```
brew install android-platform-tools
```

or Visit : https://developer.android.com/studio/releases/platform-tools.html#downloads

#### ADB on Windows :

Visit : https://developer.android.com/studio/releases/platform-tools.html#downloads


# Install Metasploit-Framework:

#### On Linux / macOS :
```
curl https://raw.githubusercontent.com/rapid7/metasploit-omnibus/master/config/templates/metasploit-framework-wrappers/msfupdate.erb > msfinstall && \
  chmod 755 msfinstall && \
  ./msfinstall
 ```
 
or Follow this link : https://docs.metasploit.com/docs/using-metasploit/getting-started/nightly-installers.html#installing-metasploit-on-linux--macos

or Visit : https://www.metasploit.com/download

#### On Windows :

Visit : https://www.metasploit.com/download

or Follow : https://docs.metasploit.com/docs/using-metasploit/getting-started/nightly-installers.html#windows-anti-virus-software-flags-the-contents-of-these-packages

# Disclaimer

* Neither the project nor its developers promote any kind of illegal activity and are not responsible for any misuse or damage caused by this program.
* This project is for the purpose of penetration testing only.
* Please do not use this tool on other people's devices without their permission.
* Do not use this tool to harm others.
* Use this project responsibly on your own devices only.
* It is the end user's responsibility to obey all applicable local, state, federal, and international laws.
