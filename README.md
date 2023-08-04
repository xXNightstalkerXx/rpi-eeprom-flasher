# rpi-eeprom-flasher
This Repository has some bash Scripts in it that make it easier to manage the EEPROM flashing process on a Raspberry Pi with the Kali Linux Distro installed.

It's meant to flash different configs on the EEPROM like "Boot from USB" or "Boot from SD"

I'm not an expert Coder so use this Repo on your own Risk and don't blame me if you have to reinstall your Raspberry.
Also flashing the EEPROM on a different Distro than Raspbian bears some risks and might brick your Raspberry Pi!

If you find something interesting within my Scripts feel free to copy parts of it and implement it into your own code.
Also feel free to contribute to this Repository and make it better :)



----------------------------------------------------------------
INSTALLATION
-

You have 2 Options how to install this flasher:

1.) Download this Repo with Git:

    sudo git clone https://github.com/xXNightstalkerXx/rpi-eeprom-flasher.git

Clone the Git Repository

    cd rpi-eeprom-flasher

Navigate into the cloned Directory

    sudo chmod 0755 rpi-eeprom-installer

Make the rpi-eeprom-installer executable

    ./rpi-eeprom-installer

Launch the rpi-eeprom-installer</br>
The Installer does the rest of the Job for you now.

2.) Download just the rpi-eeprom-installer Script and move it on your Pi manually (SFTP or by other means):

    Navigate into the Directory you placed the rpi-eeprom-installer
    sudo chmod 0755 rpi-eeprom-installer
    The Installer does the rest of the Job for you now.
    ./rpi-eeprom-installer

----------------------------------------------------------------
HOW TO USE
-

1.) After executing the Installer you can use the following commands anywhere on your system:
  - rpi-eeprom-creator  (helps you setup a new EEPROM Image with Custom configs like SD-Boot or USB-Boot)
  - rpi-eeprom-flasher  (helps you flash an existing EEPROM Image to the EEPROM)
  - rpi-eeprom-uninstaller  (uninstalls the whole rpi-eeprom-flasher and all it's files)
  - rpi-eeprom-installer  (would install the rpi-eeprom-flasher but doesn't do much when already installed)
