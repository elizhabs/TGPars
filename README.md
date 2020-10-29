🧾TGPars
Telegram spamer, inviter and parser
===================================
<p align="center">
  <img src="https://i.imgur.com/pKU0iO2.png">
</p>

# Installation
* Windows:
  * Download Python 3.8 [here](https://www.python.org/downloads/release/python-38) 
  * Launch installer, click 'add python to PATH'
  * Download **TGPars**
  * Open Command Line in **TGPars directory**
  * Run command: ***python setup.py -i**`
  * Then go to [my.telegram.org] and login in your account
  * Choose API Development Tools
  * In Command Line run ***python setup.py -c***
  * Enter api_id, api_hash and phone number
  
* Termux:
  * `pkg update`
  * `pkg install python3 python3-pip git -y`
  * `git clone https://github.com/elizhabs/TGPars/`
  * `cd TGPars`
  * `python setup.py -i`
  * `Then go to [my.telegram.org] and login in your account`
  * `Choose API Development Tools`
  * `python setup.py -c`
  * `Enter api_id, api_hash and phone number`
* Linux
  * `sudo apt update`
  * `sudo apt install python3 python3-pip git -y`
  * `git clone https://github.com/elizhabs/TGPars/`
  * `cd TGPars`
  * `python setup.py -i`
  * `Then go to [my.telegram.org] and login in your account`
  * `Choose API Development Tools`
  * `In Command Line run ***python setup.py -c***`
  * `Enter api_id, api_hash and phone number`

# Usage
* Pars
  * `python pars.py`
* Invite
  * `python invite.py members.csv`
* Spam
  * `python smsbot.py members.csv`
