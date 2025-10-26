


rm -rf ~/.wine
winecfg
wine "Ninite Discord Installer.exe"

wine "DragoMultiTOOL.exe"
apt list | grep -v installed

sudo apt update && sudo apt install discord -y


cd ~/Downloads
sudo apt install ./discord-0.0.112.deb



0
sudo apt --fix-broken install -y
