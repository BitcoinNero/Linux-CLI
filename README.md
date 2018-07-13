# Linux-Cli

## Download Beta here
https://github.com/BitcoinNero/Linux-Cli/releases/download/linux-cli/linux-cli-v1.0.0.zip

## Or Build from source
git clone https://github.com/BitcoinNero/BitcoinNero.git btcn
cd btcn
sudo apt-get install build-essential cmake pkg-config libboost-all-dev libunbound-dev libminiupnpc-dev libunwind8-dev libldns-dev libexpat1-dev libgtest-dev doxygen graphviz -y
cmake .
make

## Run Daemon or Simple Wallet
cd btcn
cd src
./bitcoinnerod
./simplewallet
