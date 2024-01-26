# OpenVPN Client Setup Procedure

*A walkthrough on installation and configuration of your VPN client for remote office network access.*

---
## OpenVPN Connect Download/Installation
Begin by downloading the OpenVPN Connect Client software from [here](https://openvpn.net/client/).<br>
Once the download has finished, install the client on your local machine with the downloaded installer.

Next you will need to download the **.ovpn** certificate that was sent to you from our support team onto your local machine.<br>
Make note of where you download the **.ovpn** certificate to as you will need it later.

---
## OpenVPN Client Configuration and Usage

Start the OpenVPN Connect client, you can do this by typing "openvpn" into your windows search bar to find the executable.

---
To add a new profile, lick the **"+"** at the bottom right corner of the window.<br>
![Add New Profile](/img/00_add_new_profile.png "Add new OpenVPN client profile")

---
You will then want to select the file **"File"** option as we will be importing a *.ovpn* certificate.<br>
![Select File Option](/img/01_select_file_option.png "Import profile by file")

---
You can then drag and drop the certificate file from the Windows File Explorer.<br>
Or you can select the "BROWSE" option to browse your local drive for the certificate file.<br>
![Import Certificate File](/img/02_import_certificate_file.png "Import certificate file")

---
You will then be taken to a screen showing basic profile details.<br>
Click **"CONNECT"** to finalize the client profile import and initiate the connection.<br>
![Finalize Import and Connect Client](/img/03_connect_profile.png "Finalize profile import and connect profile")

---
You will then see the following screen showing that you are connected.<br>
![Connected Status](/img/04_connected_status.png "Connected status screen")

---
If you need to reconnect; open the client software and click the slider next to the profile name to establish the connection.<br>
![Reconnect Process](/img/05_connect_to_profile.png "Connect to profile")

