Here are things I did on my Virtual Box. Saved in case I would need to install it again. **Which is highly possible.** It's kinda my notepad.

Things to install on the start:
```
sudo apt install git
sudo apt install npm

sudo apt install curl
curl -sL https://deb.nodesource.com/setup_10.x | sudo bash -
sudo apt-get install nodejs
sudo apt install net-tools
```

And after all of this I should have
```
nodejs -v
v10.16.2
npm-v
6.10.3
```

There goes Ranvier with example bundles, just as at the [tutorial](https://ranviermud.com/get_started/#installation):
```
git clone git://github.com/RanvierMUD/ranviermud
cd ranviermud
npm ci
npm run init
Y (on the prompt)
```

And as I am on VirtualBox I did [this](https://www.tecmint.com/install-virtualbox-guest-additions-in-ubuntu/), which is installing VB guest additions. *Which is nice.* Shared clipboard is ok but drag&drop seem to not work for me.

Then [this](https://gist.github.com/estorgio/1d679f962e8209f8a9232f7593683265) starts the same but it walks me through making of shared folder, which is folder on my DropBox.

For some reason - I can't install Ranvier in shared folder, but it's ok. I won't have shared folder on the physical server.
