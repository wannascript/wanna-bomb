# INSTALL
pkg update

pkg install python3 python3-pip git -y

git clone https://github.com/wannascrript/wanna-bomb

cd bomb

pip3 install -r requirements.txt

python3 bomb.py
