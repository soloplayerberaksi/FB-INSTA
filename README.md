Copy langsung ke Termux

```bash
pkg update -y
pkg upgrade -y
pkg install python git -y
pip install rich
termux-setup-storage
cd /storage/emulated/0/
git clone https://github.com/soloplayerberaksi/FB-INSTA
cd /storage/emulated/0/FB-INSTA
python run.py
