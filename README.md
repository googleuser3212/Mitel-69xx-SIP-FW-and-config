This repo contains the firmware for Mitel 69xx series IP phones, in order to convert them to SIP. 
**Prerequisites to make this work:**

 - TFTP Server

In order to make the phones register to a third party call control system, you will also need to have a config file, such as startup.cfg, and tell the phones to allow registration to third party systems. All of that will be posted here. **The firmware attached may not work with the 69xxw series IP phones (the versions that have Wi-Fi connectivity built in)**, I may post that firmware in a separate repo and link it here when I post it. 

  Included with the firmware is a guide on how to write the config files for the phones. This will be useful if you want to provision the phones using a config file. 

  I have not figured out how to configure DHCP for the phones to automatically find the TFTP. If someone knows the answer to how to do that, please let me know.
  
  The config file included will also work with the 6800 series of AASTRA/Mitel phones. I don't know if they will work with the earlier AASTRA phones. 




