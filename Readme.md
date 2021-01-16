# Xenios Project is here !!!

Coin Abbreviation: XNC

Total Sum of Coins: 108,000,000

Xenios is a business and investment-oriented cryptocurrency. 
It offers anonymous, secure and fast transactions. 
Xenios will be accepted by many businesses and enterprises globally in a short period of time, 
as it is one of the safest digital assets. 
On its stable minimum price, stacking XNC will produce wealth for all that make or accept transactions with our coin.
Xenios "Hotels & Flights" is a service that provides offers on travel and accommodation, to users that pay with XNC. 
Xenios investments add extra value to Xenios, as all their net profit will be added to the coin price. 
The quaranteed minimum price of Xenios will constantly be growing higher. 

Website: https://xenioscoin.com

Webwallet: https://wallet.xenioscoin.com

# To work with the source code please download Xenios src file (xenios-source.tar.gz)

# How do I setup Xenios Node on Ubuntu Server 18.04? (The easy way!!!)

#Use Ubuntu 18.04 LTS 64bit.

# Update your Ubuntu machine.

sudo apt-get update

sudo apt-get upgrade

# Install the required dependencies.
sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils python3 libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-test-dev libboost-thread-dev libboost-all-dev libboost-program-options-dev

sudo apt-get install libminiupnpc-dev libzmq3-dev libprotobuf-dev protobuf-compiler unzip software-properties-common

# Install Berkeley DB.

sudo add-apt-repository ppa:bitcoin/bitcoin

sudo apt-get update

sudo apt-get install libdb4.8-dev libdb4.8++-dev

# Download the linux daemon and tools

wget "https://github.com/xeniosproject/xenioscoin/raw/master/xenios-daemon-linux.tar.gz" -O xenios-daemon-linux.tar.gz

wget "https://github.com/xeniosproject/xenioscoin/raw/master/xenios-qt-linux.tar.gz" -O xenios-qt-linux.tar.gz

#Extract the tar file.

tar -xzvf xenios-daemon-linux.tar.gz

tar -xzvf xenios-qt-linux.tar.gz

#Install the daemon.

sudo mv xeniosd xenios-cli xenios-tx /usr/bin/

#Create the config file.

mkdir $HOME/.xenios

nano $HOME/.xenios/xenios.conf

#Paste the following lines in xenios.conf.

rpcuser=rpc_xenios

rpcpassword=a-very-strong-password

rpcallowip=127.0.0.1

rpcport=21351

tcpport=21352

listen=1

server=1

txindex=1

daemon=1

addnode=209.97.129.79

addnode=134.122.74.85

addnode=207.154.250.1

addnode=167.172.55.240

addnode=104.248.129.19

addnode=206.81.26.83

addnode=134.209.243.206

#Start your node with the following command.

xeniosd 




 # WALLET-DOWNLOAD  --- xenios.conf instractions

Ready compiled hnc wallets and daemons


# Windows 

Windows Wallet ---> xenios-qt-windows.zip


# Linux 

Linux Wallet  ---> xenios-qt-linux.tar.gz

Linux Daemon  ---> xenios-daemon-linux.tar.gz


# Mac

MacOs Wallet ---> xenios-qt.dmg


# xenios.conf

# Paste the following lines in xenios.conf.


rpcuser=rpc_xenioscoin

rpcpassword=Your_strong_rpc_password

rpcallowip=127.0.0.1

rpcport=21351

tcpport=21352

listen=1

server=1

daemon=1

maxconnections=64

addnode=node1.xenioscoin.com


