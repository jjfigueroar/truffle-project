# truffle-project
My truffle project

# Environment preparation  

/// Upgrade packages ///
sudo apt-get update && sudo apt-get -y upgrade
sudo apt-get -y install curl git vim build-essential

/// Install nodejs ///
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
sudo apt-get install -y nodejs
sudo apt-get install -y npm
sudo npm install -g express

/// Install truffle ///
sudo npm install -g truffle

/// Install testrpc ///
sudo npm install -g ethereumjs-testrpc
