# Installing node on a fresh Ubuntu install

First add the the official node.js PPA to your system, then install nodejs.

```
sudo apt-get install curl python-software-properties
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install nodejs
node -v
```

The last command should output the installed node version.

TAGS : ubuntu node nodejs
DATE : 24 06 2019