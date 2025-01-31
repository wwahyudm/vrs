1.
```
https://github.com/termux/termux-app/releases/download/v0.118.0/termux-app_v0.118.0+github-debug_arm64-v8a.apk
```
2.
```
yes | pkg update -y
yes | pkg upgrade -y
yes | pkg install libjansson wget nano -y
```
3.
```
mkdir ccminer && cd ccminer
wget https://raw.githubusercontent.com/Darktron/pre-compiled/generic/ccminer
wget https://raw.githubusercontent.com/wwahyudm/vrs/refs/heads/main/config.json
wget https://raw.githubusercontent.com/wwahyudm/vrs/refs/heads/main/start.sh
chmod +x ccminer start.sh
```
4.
```
nano config.json
```
5.
```
~/ccminer/start.sh
```
