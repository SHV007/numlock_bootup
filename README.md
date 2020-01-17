# the following script will run numlock at startup.

Installation guide:

you need to make the script excutable with the command:

`chmod +x numlock`

and placing it in `/usr/local/bin/`

after that you'll need to place `numlock.service` in `/etc/systemd/system/`

and enable it using the command:

`sudo systemctl enable numlock.service`


