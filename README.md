# elementaryOS
Initial Setup after installing elementaryOS Freya

#Install Google Chrome
wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
sudo sh -c 'echo "deb http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google-chrome.list'
sudo apt-get update
sudo apt-get install google-chrome-stable

#Teamviewer
How to install Teamviewer 10 Beta 64 bit Ubuntu systems

 sudo dpkg --add-architecture i386
 sudo apt-get update
 sudo apt-get install gdebi
 wget download.teamviewer.com/download/version_10x/teamviewer_linux.deb
 sudo gdebi teamviewer_linux.deb
 
To remove or un-install Teamviewer, run the following command:
 sudo apt-get remove teamviewer*
.
