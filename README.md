Squeeze-Steeze
==============

Maxrelax replacement SqueezeBox Server skin.

Extracted original skin from `/usr/share/squeezeboxserver/HTML/Default` of Logitech Squeezebox Server.

## Install Squeezebox on Debian *nix

```bash
sudo echo "deb http://debian.slimdevices.com stable main" >> /etc/apt/sources.list
sudo apt-get update
sudo apt-get install squeezeboxserver
```

### Install Squeeze-Steeze Skin

```bash
git clone https://github.com/maxrelax/squeeze-steeze.git
sudo mv squeeze-steeze /usr/share/squeezeboxserver/HTML/SqueezeSteeze
sudo service logitechmediaserver restart
```

### License

MIT
