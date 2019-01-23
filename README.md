# x830-v2
This is the safe shutdown script for x830 v2 (not fot x830 v1.1)

NOTE:

We test this shell script base official Raspbian '2018-11-13-raspbian-stretch.img' version;

How to use?

step 1: wget https://raw.githubusercontent.com/geekworm-com/x720-script/master/x720.sh

sudo chmod +x x830-v2.sh

sudo bash x830-v2.sh

step 2: printf "%s\n" "alias x830pwr='sudo x830pwr.sh'" >> ~/.bashrc

step 3: sudo reboot
