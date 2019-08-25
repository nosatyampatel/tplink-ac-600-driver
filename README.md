# tplink-ac-600-driver
Tp-link AC 600 High Gain driver for Linux all Debian versions(ubuntu,kali,parrot...)
***********************************************************************************************************************************-----------------------------------------------------------------------------------------------------------------------------------
                                          FOLLOWING STEPS TO INSTALL DRIVERS:
                                          
                                          
                                          
                                          
                                          
                                          
                                          
                                          
1.PLUG YOUR Usb TP-link AC 600 device.
2.Copy or clone this file.
3.Unzip the file.
4.Open terminal in unziped folder.(right click and open terminal)
5.EXICUTE THESE COMMNADS: sudo apt install linux-headers-(PRESS TAB AND CHOOSE your chipset ie.amd64 or intel)
sudo apt install git
sudo apt install dkms
sudo apt install wpasupplicant
mkdir ~/src
cd ~/src
cd mt7610u_wifi_sta_v3002_dpo_20130916
sudo make clean
sudo make
sudo make install
sudo mkdir /etc/Wireless/RT2870STA
sudo cp RT2870STA.dat /etc/Wireless/RT2870STA/
reboot

******Congratulations after rebooting you can use your device*********
*******************green light started blinking***********************
