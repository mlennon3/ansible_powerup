# bootstrap_devstation
First, switch to TW guest!
This will download a 8gb box file!

Try:
``` $ vagrant up```
If you don't have vagrant installed, do this stuff:

```$ brew install ansible caskroom/cask/brew-cask```

```$ brew cask install vagrant virtualbox```

To run the vagrant machine the first time:

``` $ vagrant up```

You should get a new mac osx virtual machine to play with


Inside the vm, try to get it working with ansible:
``` $ cd ansible_powerup ```
``` $ ansible-playbook -i ansible/myHostsFile
ansible/devstation.yml ```

if you get the box with the usb stick, put the box in
~/.vagrant.d/boxes/
