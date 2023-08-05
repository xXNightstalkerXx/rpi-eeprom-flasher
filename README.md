# rpi-eeprom-flasher
This Repository has some bash Scripts in it that make it easier to manage the EEPROM flashing process on a Raspberry Pi with the Kali Linux Distro installed.

It's meant to flash different configs on the EEPROM like "Boot from USB" or "Boot from SD"

I'm not an expert Coder so use this Repo on your own Risk and don't blame me if you have to reinstall your Raspberry.
Also flashing the EEPROM on a different Distro than Raspbian bears some risks and might brick your Raspberry Pi!

If you find something interesting within my Scripts feel free to copy parts of it and implement it into your own code.
Also feel free to contribute to this Repository and make it better :)


----------------------------------------------------------------
----------------------------------------------------------------
# INSTALLATION

    wget https://github.com/xXNightstalkerXx/rpi-eeprom-flasher/blob/main/rpi-eeprom-installer
Download the rpi-eeprom-installer file with wget

    sudo chmod 0755 rpi-eeprom-installer
To make the Script executable

    ./rpi-eeprom-installer
Launch the Script
</br>
</br>
The Installer does the rest of the Job for you now.

----------------------------------------------------------------
----------------------------------------------------------------
# HOW TO USE

    rpi-eeprom-creator
Helps you setup a new EEPROM Image with custom configs like "SD-Boot" or "USB-Boot"

    rpi-eeprom-flasher
Helps you to flash an existing Image to the EEPROM

    rpi-eeprom-uninstaller
Uninstalls the whole rpi-eeprom-flasher and all it's Files

    rpi-eeprom-installer
Would install the rpi-eeprom-flasher but doesn't do much when already installed

----------------------------------------------------------------
----------------------------------------------------------------
