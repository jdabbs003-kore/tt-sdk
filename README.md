# tt-sdk
## Teltonika SDK Setup

This project contains scripts to set up and build the Teltonika SDK. For this to work,
you need to be a non root user, in the sudoers file, on an Ubuntu 18.04 development machine. The
build step may take several hours.

The project includes three scripts:
1. setup
1. download
1. build

## setup
1. `sudo apt install -y git`
1. `cd ~`
1. `git clone https://github.com/jdabbs003-kore/tt-sdk.git`
1. `cd ./tt-sdk`
1. `sudo ./setup`

## download
1. `cd ~/tt-sdk`
1. `./download`

## build
1. `cd ~/tt-sdk`
1. `./build`
