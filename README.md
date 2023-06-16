# Termux_set-up
pkg update && pkg upgrade-y

pkg install git

pkg install python

rm -rf Termux_set-up

git clone https://github.com/abir5005/Termux_set-up

cd Termux_set-up

python Termux-setup_enc.py
