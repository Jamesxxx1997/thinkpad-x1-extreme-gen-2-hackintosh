# thinkpad-x1-extreme-gen-2-hackintosh
full clover hotpatch efi , credit to https://github.com/CrazyPegasus

## config.plist

the default config.plist is for 4K screen version. 

please change your config.plist in the zip file uploaded.

The "config 9750H with samsung RAM patches.plis" inject patches for machine with 32 gb ram single stick. You might have to edit this config if you have 2 sticks with 32gb ram respectively.

## sleep
please change "hibernatemode" and "proximitywake" value to zero , you can do this via hackintool.

## wlan
the x1 extreme gen2 and P1 gen2 has wlan whitelist , so you have to mod the bios if you want to change your wifi card ; P53 with older version of bios don't have wlan whitelist.
