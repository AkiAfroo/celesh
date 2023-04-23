# celesh: this Code is part of the celestia Bonus Task.- please dont use it in mainnet.

What the script do:
https://i.postimg.cc/8zBFdZ8y/celesh-menu.png

Usage:
* First download it ```wget https://raw.githubusercontent.com/AkiAfroo/celesh/main/celesh```
* Second: `chmod +x celesh` 
* third:  `bash celesh`
* the script will try to install dialog , zip , unzip if are not installed in your system before launch the menu.
* Fresh install after menu pop up: select with mouse or moving with arrows and using spacebar
* options : ```2,3,4,5```
(https://i.postimg.cc/htC6DSm8/install-options.png)

Backup:
* you can backup your wallet >> option 6
(https://i.postimg.cc/MKshyWR6/minina-backup.png)


Removing Mina from your system
* ~/.coda-config , keys folder and .mina-env are exclude >> option 9
(https://i.postimg.cc/zG7SLBR7/minina-remove-deps.png)

Removing temp directories and coda-config
* when the daemon stuck sometimes a good option is clean tmp mina folders and ~/.coda-config folder
(https://i.postimg.cc/QdzCnZLs/minina-remove-codafolder.png)

Notes
* the script will detect if a wallet is storage in ~/keys folder to avoid overwrite the current ones if you select option 5 my mistake.

* now after is installed run ```coda``` in your terminal or ```coda version``` to check the installation is OK.
* Have fun !
