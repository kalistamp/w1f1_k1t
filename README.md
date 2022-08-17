
## check:

https://pentestlab.blog/2015/02/03/hirte-attack/

## Phish:

A Comprehensive Taxonomy of Wi-Fi Attacks: https://www.ru.nl/publish/pages/769526/mark_vink.pdf



bettercap -	bettercap is the Swiss army knife for network attacks and monitoring.

WiFi Pumpkin -	Framework for Rogue Wi-Fi Access Point Attack.

Airgeddon - This is a multi-use bash script for Linux systems to audit wireless networks.

Airbash - A POSIX-compliant, fully automated WPA PSK handshake capture script aimed at penetration testing.

Wifiphisher - Wifiphisher is a rogue Access Point framework for conducting red team engagements or Wi-Fi security testing.

## Sources:

* https://github.com/techge/wifi-arsenal

* https://github.com/0x90/wifi-arsenal

* https://github.com/TheWickerMan/Auto-Airodump-NG/blob/master/Auto-Airodump-NG [Tst and Take]

* https://github.com/gorvgoyl/clone-wars

* https://github.com/KasRoudra/PyPhisher

* https://github.com/AlexLynd/ESP8266-Wardriving

* https://pwnagotchi.ai/

* [Hacker_Roadmap](https://github.com/sundowndev/hacker-roadmap#globe_with_meridians-wireless-testing)

* [Wigle](https://wigle.net/)

* https://www.youtube.com/watch?v=QHo2hCzxMr0

## Wordlists:

* https://github.com/ZKAW/big_wpa_wordlist

* https://github.com/danielmiessler/SecLists/tree/master/Passwords

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

## Literature:

* https://github.com/skickar/Hope_2022_Presentation/blob/main/Cyber_Weapons_Hope.pdf

* https://miloserdov.org/?cat=2

* https://blog.elcomsoft.com/2020/03/breaking-wi-fi-passwords/#:~:text=The%20WPA%20standard%20enforces%20the,network%20of%20GPU%2Daccelerated%20computers

* https://www.trickster.dev/post/decrypting-your-own-https-traffic-with-wireshark/

* * *

KRACK is a replay attack on the Wi-Fi Protected Access protocol that secures Wi-Fi connections. It was discovered in 2016 by the Belgian researchers Mathy Vanhoef and Frank Piessens of the University of Leuven. 

* Mathy Vanhoef: https://www.mathyvanhoef.com/



