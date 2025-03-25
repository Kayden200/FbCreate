# Install this before running the command 
pkg update && pkg upgrade -y

pkg install python -y

pkg install git -y

pip install requests faker

# Commands
git clone https://github.com/Kayden200/FbCreate.git

cd FbCreate

python autofb.py
