# Docker_Build

This repo is for building docker on linux

To make docker work in wsl2 you might need to do the following for it to start

(You need to switch to iptables-legacy so that Docker will work again: Run sudo update-alternatives --config iptables. Enter 1 to select iptables-legacy.
Now run sudo service docker start , and Docker will start as expected)
