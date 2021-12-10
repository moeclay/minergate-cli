# minergate-cli
mining crypto with minergate account for ubuntu 64bit

# install with cli
$ wget --no-check-certificate https://download.minergate.com/xfast-ubuntu-cli/1.5

$ mv 1.5 minergate-cli

$ sudo dpkg -i minergate-cli

$ minergate-cli --user moeamarreza@gmail.com --xmr 8

# install xmrig with cli
$ wget https://github.com/xmrig/xmrig/releases/download/v6.16.2/xmrig-6.16.2-linux-static-x64.tar.gz

$ tar -xf filename

$ ./xmrig -o pool.minexmr.com:4444 -u address_wallet_xmr
