# How its works..check this
[![asciicast](https://asciinema.org/a/575508.svg)](https://asciinema.org/a/575508)

# waiting for Mainnet, lets adjust celesh to work on Celestia (Mocha). 
# you can use this script to install and do some task in your node (check the screenshots)
* recommended to use this bash script in a fresh linux server (ubuntu/Debian) for **Light Node Only**
* celesh will create a celeshfolder in your HOME directory where will save and copy some important files from your node as backup

![celesh-menu.png](https://i.postimg.cc/DysKWKfV/celesh-menu.png)

* celesh can:
- upgrade your machine
- install celestia deps
- install/upgrade/remove golang (modified version of go installer by  kerolloz)
- clone and compile celestia light node repo
- backup your keys folder to celeshfolder in zip format
- backup celestia and cel-key binaries
- create new accounts keys and backup mnenomics into a file inside celeshfolder
- send PFB Transactions
- change RPC-ENPOINTS 
- Much More...

what celesh can't do:
- transfer keys to an external server (maybe in the future)
- increase or monitoring your server uptime (its up to you to monitoring your server)
- 

Usage:
* First download it ```wget https://raw.githubusercontent.com/AkiAfroo/celesh/mocha/celesh```
* Second: `chmod +x celesh` 
* third:  `bash celesh`
* the script will try to install dialog , zip , unzip if are not installed in your system before launch the menu.
* Fresh install after menu pop up: select with mouse or moving with arrows (UP-DOWN) and select/unselect with spacebar

![install-options.png](https://i.postimg.cc/htC6DSm8/install-options.png)
* options : ```2,3,4,5```

![celesh-more-options.png](https://i.postimg.cc/RZC2x3WV/celesh-more-options.png)

* Have fun !

# Disclaimer: Always double check your mnemonics and keys backup and always backup your keys and mnenomics manually
# if you find a bug please report it by open a issue ticket here in github (do not spam celestia Discord)
