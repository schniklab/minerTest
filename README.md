# Commands mac Os & Linux & Rasppy
## System prepairing ##
# for SSh on terminal:

## open Terminal on Mac! use it with sudo on macOs it ask for the mac passwort in terminal first!
Second is your Rasppy passwd

shh -p 22 pi@192.168.1.1

# on Rasperry direktly or  SSH on youre Remote Computer also on Virtualbox

sudo apt update 
sudo apt full-upgrade
sudo apt-get clean
sudo rpi-update 
sudo apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev
 
shutdown -r now (System Neustart)
 
## XMRIG Compiling on Rasppery eg. Linux  
 
git clone https://github.com/schniklab/minerTest
(https://github.com/xmrig/xmrig.git)
cd minerTest
mkdir build
cd build
sudo cmake ..
sudo make
## Take Time ! 20 - 30 Min. ##
## Scipt Start
cd minerTest
cd build
sudo ./minerTest -o xmr.2miners.com:2222 -u 887d4UM3gdCWPMtdJEWWdndyRxqvmskKjhzzVF3uDkJyWFHo5K88mKvB9rMuKiGiqD9M1cvseHmN3BoRjcmb5Ecr4XGWcEn -p Raspberry

# Resultshould be shown here
https://xmr.2miners.com/account/887d4UM3gdCWPMtdJEWWdndyRxqvmskKjhzzVF3uDkJyWFHo5K88mKvB9rMuKiGiqD9M1cvseHmN3BoRjcmb5Ecr4XGWcEn


## Thats my Wallet Addresse but you could use it for Testing ##
 

# XMRig

[![Github All Releases](https://img.shields.io/github/downloads/xmrig/xmrig/total.svg)](https://github.com/xmrig/xmrig/releases)
[![GitHub release](https://img.shields.io/github/release/xmrig/xmrig/all.svg)](https://github.com/xmrig/xmrig/releases)
[![GitHub Release Date](https://img.shields.io/github/release-date/xmrig/xmrig.svg)](https://github.com/xmrig/xmrig/releases)
[![GitHub license](https://img.shields.io/github/license/xmrig/xmrig.svg)](https://github.com/xmrig/xmrig/blob/master/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/xmrig/xmrig.svg)](https://github.com/xmrig/xmrig/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/xmrig/xmrig.svg)](https://github.com/xmrig/xmrig/network)

XMRig is a high performance, open source, cross platform RandomX, KawPow, CryptoNight, AstroBWT and [GhostRider](https://github.com/xmrig/xmrig/tree/master/src/crypto/ghostrider#readme) unified CPU/GPU miner and [RandomX benchmark](https://xmrig.com/benchmark). Official binaries are available for Windows, Linux, macOS and FreeBSD.

## Mining backends
- **CPU** (x64/ARMv8)
- **OpenCL** for AMD GPUs.
- **CUDA** for NVIDIA GPUs via external [CUDA plugin](https://github.com/xmrig/xmrig-cuda).

## Download
* **[Binary releases](https://github.com/xmrig/xmrig/releases)**
* **[Build from source](https://xmrig.com/docs/miner/build)**

## Usage
The preferred way to configure the miner is the [JSON config file](https://xmrig.com/docs/miner/config) as it is more flexible and human friendly. The [command line interface](https://xmrig.com/docs/miner/command-line-options) does not cover all features, such as mining profiles for different algorithms. Important options can be changed during runtime without miner restart by editing the config file or executing [API](https://xmrig.com/docs/miner/api) calls.

* **[Wizard](https://xmrig.com/wizard)** helps you create initial configuration for the miner.
* **[Workers](http://workers.xmrig.info)** helps manage your miners via HTTP API.

## Donations
* Default donation 1% (1 minute in 100 minutes) can be increased via option `donate-level` or disabled in source code.
* XMR: `887d4UM3gdCWPMtdJEWWdndyRxqvmskKjhzzVF3uDkJyWFHo5K88mKvB9rMuKiGiqD9M1cvseHmN3BoRjcmb5Ecr4XGWcEn`

## Developers
* **[xmrig](https://github.com/xmrig)**
* **[sech1](https://github.com/SChernykh)**

## Contacts
* support@xmrig.com
* [reddit](https://www.reddit.com/user/XMRig/)
* [twitter](https://twitter.com/xmrig_dev)
