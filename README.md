# lc0goorm

lc0 binary that can be run on goorm ( Ubuntu 18.04 LTS )

## build lc0

https://gist.github.com/hyperchessbot/c9164740c11c144ad488642b18bd1181

the repo contains the result of this build, plus a weights file

## run the binary on a different system

```
sudo apt-get update -y
sudo apt-get install libopenblas-base -y
sudo apt-get install libstdc++6 -y
sudo add-apt-repository ppa:ubuntu-toolchain-r/test 
sudo apt-get update
sudo apt-get upgrade
sudo apt-get dist-upgrade

./lc0 -w weights.pb.gz
```
