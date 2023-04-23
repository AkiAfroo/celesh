# celesh: this Code is part of the celestia Bonus Task.- please dont use it in mainnet.
* recommended to use this bash script in a fresh linux server (ubuntu)
* celesh will create a celeshfolder in your HOME directory where will save and copy some important files from your node as backup
What the script do:
![celesh-menu.png](https://i.postimg.cc/8zBFdZ8y/celesh-menu.png)
* celesh can:
- upgrade your machine
- install celestia deps
- install/upgrade/remove golang (modified version of go installer by  kerolloz)
- clone and compile celestia light node repo
- backup celestia and cel-key binaries
- create new accounts keys and backup mnenomics into a file inside celeshfolder
- 

Usage:
* First download it ```wget https://raw.githubusercontent.com/AkiAfroo/celesh/main/celesh```
* Second: `chmod +x celesh` 
* third:  `bash celesh`
* the script will try to install dialog , zip , unzip if are not installed in your system before launch the menu.
* Fresh install after menu pop up: select with mouse or moving with arrows (UP-DOWN) and select/unselect with spacebar
* options : ```2,3,4,5```
![install-options.png](https://i.postimg.cc/htC6DSm8/install-options.png)

Backup:
* you can backup your wallet >> option 6
![celesh-more-options.png](https://i.postimg.cc/RZC2x3WV/celesh-more-options.png)


Removing Mina from your system
* ~/.coda-config , keys folder and .mina-env are exclude >> option 9
![minina-remove-deps.png](https://i.postimg.cc/zG7SLBR7/minina-remove-deps.png)

Removing temp directories and coda-config
* when the daemon stuck sometimes a good option is clean tmp mina folders and ~/.coda-config folder
![minina-remove-codafolder.png](https://i.postimg.cc/QdzCnZLs/minina-remove-codafolder.png)

Notes
* the script will detect if a wallet is storage in ~/keys folder to avoid overwrite the current ones if you select option 5 my mistake.

* now after is installed run ```coda``` in your terminal or ```coda version``` to check the installation is OK.
* Have fun !
