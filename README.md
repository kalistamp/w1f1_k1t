
## Setup Alfa aws036acm Adapter (steps):
```
sudo apt update 
sudo apt upgrade -y 
sudo apt dist-upgrade -y 
sudo reboot now 
sudo apt update 
sudo apt install realtek-rtl88xxau-dkms 
sudo apt install dkms 
git clone https://github.com/aircrack-ng/rtl8812au 
cd rtl8812au/ 
make 
sudo make install 
lsusb 
iwconfig
```

## Sources:

* [Wigle](https://wigle.net/)

- https://www.trickster.dev/post/decrypting-your-own-https-traffic-with-wireshark/

- https://miloserdov.org/?p=2100
- https://blog.elcomsoft.com/2020/03/breaking-wi-fi-passwords/#:~:text=The%20WPA%20standard%20enforces%20the,network%20of%20GPU%2Daccelerated%20computers

- https://www.youtube.com/watch?v=QHo2hCzxMr0

## T00ls:

bettercap -	bettercap is the Swiss army knife for network attacks and monitoring.

WiFi Pumpkin -	Framework for Rogue Wi-Fi Access Point Attack.

Aircrack-ng - Aircrack-ng suite of tools for monitoring and packet injection.

Airgeddon - This is a multi-use bash script for Linux systems to audit wireless networks.

Airbash - A POSIX-compliant, fully automated WPA PSK handshake capture script aimed at penetration testing.

Wifiphisher - Wifiphisher is a rogue Access Point framework for conducting red team engagements or Wi-Fi security testing.

## Other Repositories: 

- https://github.com/0x90/wifi-arsenal

- https://github.com/TheWickerMan/Auto-Airodump-NG/blob/master/Auto-Airodump-NG [Tst and Take]

- https://github.com/gorvgoyl/clone-wars

- https://github.com/wifiphisher/extra-phishing-pages

- https://github.com/KasRoudra/PyPhisher

- https://github.com/danielmiessler/SecLists

- https://github.com/AlexLynd/ESP8266-Wardriving

- https://pwnagotchi.ai/
