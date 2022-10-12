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

===================================================================================
Cara Mining Verus Dengan Qwiklabs

Site: https://www.qwiklabs.com/ 

Tempmailo: https://tempmailo.com/ 


1. Buka https://www.qwiklabs.com/ klik Gabung (Join)

2. Buka TAB Baru klik https://tempmailo.com/  untuk mendapatkan email temporary.

3. Kembali ke TAB qwiklab, isi datanya. catat email dan passwordnya

4. Buka TAB email tempmailo cek inbox untuk verifikasi akun qwiklabnya , klik Konfirmasi alamat email

5. Nanti akan di arahkan ke login page qwiklab, isikan email dan password yg tadi dibuat

6. Buka Google Cloud Essentials , klik mulai, scroll ke bawah sedikit

7. Klik pada bagian Tur Qwiklabs dan Google Cloud

8. Klik Mulai Lab 00:45:00, isi captchanya

9. Klik Open Google Console , catat user name dan pasword yg otomatis diberikan

10. Setelah masuk, isi login dan paswordnya

11. Welcome to Your New Account, klik Accept

12. Lengkapi ceklis pada bagian welcome student , agree and continue

13. Klik Activate Cloud Shell (Terminal) letaknya pada bagian pojok kanan atas, klik Continue

14. Selanjutnya kita ke bagian Mining


Mining Terminal  :

Copy pastekan perintah terminal dibawah ini :

wget https://github.com/hellcatz/luckpool/raw/master/miners/hellminer_cpu_linux.tar.gz

kemudian kita copy paste juga dibawah ini :

tar xf hellminer_cpu_linux.tar.gz

Lalu kita copy paste juga untuk perintah nya di bawah ini :

./hellminer -c stratum+tcp://eu.luckpool.net:3956#xnsub -u RX7GExSquvgUrdac9nH4TDKnZvGjyXaFth.qwiklab1 -p x --cpu 4

Jangan lupa untuk mengganti kode RX7GExSquvgUrdac9nH4TDKnZvGjyXaFth dengan kode alamat wallet Verus kalian. Atau anda juga bisa mengganti kata kata qwiklab1 dengan kata lain qwiklabtest. 

