To use (with a MacBook):

image an SD card with: sudo dd bs=1m if=~/Downloads/2022-04-04-raspios-buster-armhf-lite.img of=/dev/disk2

sudo apt update  -y &&  sudo apt-get upgrade  -y

sudo apt install git ansible -y

ansible-pull -d /home/pi/pull -i 'localhost,' -U https://github.com/Wied58/pull_recusb_from_git pull_recusb_from_git.yml 
