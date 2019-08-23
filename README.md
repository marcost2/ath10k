# ath10k
After fighting for a month and a half trying to get this WiFi chipset to work correctly in monitor mode (for the record, it would go into monitor mode but it wouldnt find or capture any packets, so injection wasnt working properly) but i remember it working with kali 2016.2, so i downloaded it, booted it and extracted the firmware for it. Replaced it and now it works! So im uploading this here if anyone has the same problem

# Installation
Just copy these files into /lib/firmware/ath10k/QCA9377/hw1.0 and replace/ delete those already there. You WILL need root privileges to do this. 
Next time you reboot it will load this old firmware and monitor mode will work correctly! I dont know if there is a regression in wifi speeds or stability, as of now there isnt. 

# Disclaimer
This was tested under Linux mint 19.2 Tina , you mileage may vary. The files uploaded here were extracted from Kali Linux 2016.2, but you are free to search trough them to find trojans. 
