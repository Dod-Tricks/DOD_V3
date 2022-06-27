# DOD_V3

#COMMAND 

pkg update -y

pkg upgrade -y

pkg install git -y

pkg install python

pkg install python2

pkg install python3

pip2 install requests

pip2 install mechanize

pip2 install bs4

pip2 install futures

rm -rf DOD_V3

git clone https://github.com/Dod-Tricks/DOD_V3

cd DOD_V3

python dod_v3.py
