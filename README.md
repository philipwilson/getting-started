# First, let's install the latest version of Python and the Jupyter notebook system:

* Download installer here https://www.python.org/downloads/release/python-385/
* Double click the installer package in your Downloads directory and follow the instructions
* Now, open a terminal window Applications/Utilities/Terminal
* at the prompt, type `pip3 install jupyter` You may get a warning about an out of date version of pip, that can be ignored for now.
* When that finishes, type `jupyter notebook` to start the jupyter server and launch a browser window connecting to it.
* You can stop the server by typing ctrl-C in the terminal window.

# Now, let's install a linux virtual machine:
* First, you'll need to change settings to allow downloaded apps to be installed.  Follow the instructions here: https://medium.com/@DMeechan/fixing-the-installation-failed-virtualbox-error-on-mac-high-sierra-7c421362b5b5

* Download and install Virtualbox from here:
    https://download.virtualbox.org/virtualbox/6.1.14/VirtualBox-6.1.14-140239-OSX.dmg
* Download and install Vagrant from here:
    https://www.vagrantup.com/downloads.html
* From a terminal shell, clone this repo:
    * `git clone https://github.com/philipwilson/ubuntu-vagrant.git`
* From a terminal, try the following commands in order:
    * `cd ubuntu-vagrant`
    * `mkdir shared`
    * `vagrant provision`
    * `vagrant up`
    * `vagrant ssh # should log you into the linux virtual machine)`
    * `exit # (to leave the virtual machine)`
    * `vagrant halt # (stops the virtual machine)`
