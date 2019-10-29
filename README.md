# Installing procedure how to build network automation lab

Prerequisites:

* VirtualBox and installed Ubuntu OS 

## Installation: 

* Clone repository:

`git clone https://github.com/bskulj/network_automation.git`

* Go to the directory

`cd network_automation`

* Create virtual environment:

`virtualenv -p python3.x virt-env`

* Activate virtual environment:

`source virt-env/bin/activate`

* Install packages:

`pip install -r requirements.txt`

* If you want to create alias for activating network_automation in virtual environment add this to .bashrc: 

`alias network_automation='cd /$PATH/network_automation && source virt-env/bin/activate'`




