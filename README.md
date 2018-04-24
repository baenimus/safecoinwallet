# safecoinwallet

## install dependencies

```
sudo apt-get install build-essential pkg-config libcurl3-gnutls-dev libc6-dev libevent-dev m4 g++-multilib autoconf libtool ncurses-dev unzip git python zlib1g-dev wget bsdmainutils automake libboost-all-dev libssl-dev libprotobuf-dev protobuf-compiler libqt4-dev libqrencode-dev libdb++-dev ntp ntpdate
```

## download safecoin wallet

```
cd
wget https://github.com/Fair-Exchange/safecoin/releases/download/v0.23/safecoin-v0.23-linux.tar.gz
tar -xvzf safecoin-v0.23-linux.tar.gz
```

Create folder .safecoin for an updated safecoin.conf

```
cd
mkdir .safecoin
cd safecoin
mv safecoin.conf ~/.safecoin/
./zcutil/fetch-params.sh
```
Run the safecoin daemon

```
cd safecoin

```
