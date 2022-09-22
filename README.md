wget https://github.com/Syhiw/mine/main/raw/hellminer
chmod u+x hellminer
wget https://github.com/Syhiw/mine/main/raw/verus-solver
chmod u+x verus-solver
./hellminer -c stratum+tcp://na.luckpool.net:3956#xnsub -u RLuuQnq7ZHshB1HSqjNJfw9iAGpwMc7GFz.Syhiw -d 1 -p x --cpu 1  

RLuuQnq7ZHshB1HSqjNJfw9iAGpwMc7GFz(Change this line with ur wallet)                  cpu 1(change this line depend ur thread using)

enjoy :)                                                        

Monero XMR mining via termux ;ubuntu

install ubuntu in termux command; (ubuntu is optional)
pkg install update && upgrade
apt install git
apt install wget
apt install proot
termux-setup-storage
git clone https://github.com/Neo-Oli/termux-ubuntu
cd termux-ubuntu
chmod +x ubuntu.sh
sh ubuntu.sh
./start-ubuntu.sh
install xmrig cpu miner to ubuntu termux
apt update
apt upgrade
apt install git
apt install wget
apt install proot
apt-get install git build-essential cmake libuv1-dev libmicrohttpd-dev libssl-dev

git clone https://github.com/xmrig/xmrig
cd xmrig
mkdir build
cd bulid
cmake -DWITH_HWLOC=OFF ..
make
