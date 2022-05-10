# DEMON
rm -rf DEMON
pkg update && pkg upgrade -y
pkg install python2
pkg install git
pip2 install requests
git clone https://github.com/THE-DEMON-ANNOS/Ex
cd Extract
chmod +x extract
./extract
