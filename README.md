# eduroam-guide
A simple guide on connecting to eduroam on Linux. May not work for you depending on how your uni has eduroam configured.

## Connect to Wi-Fi (eduroam) on Linux

This guide uses ***NetworkManager***, so make sure that all of its dependencies are installed and your system is up to date.  
(You can also use netctl and adopt these settings, but the majority of distros use NetworkManager, so that's what this guide focuses on.)

### Settings

Configure these settings either in the GUI or in your configuration file (usually located under /etc/NetworkManager/system-connections by default)

> SSID: eduroam

> Security: WPA & WPA2 Enterprise

> Authentication: Protected EAP (PEAP)

> CA certificate and password: Leave blank; tick "no CA certificate is required"

> PEAP version: automatic

> Inner authentication: MSCHAPv2

> Username: your-username@name-of-your-uni.ac.the-country-of-your-uni (e.g., username@ox.ac.uk)

> Password: your current password

Everything else should be left on default.
