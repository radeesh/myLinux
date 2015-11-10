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

#Install VLC
sudo apt-get install vlc

#Sublime Text 3
There isn’t an official PPA, but you can use webupd8's PPA.

Just try this on your terminal:

sudo add-apt-repository ppa:webupd8team/sublime-text-3

sudo apt-get update

sudo apt-get install sublime-text-installer

Also you can download the .deb file from http://www.sublimetext.com/3 and install it.

#rbenv
sudo apt-get update

sudo apt-get install git-core curl zlib1g-dev build-essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev libcurl4-openssl-dev python-software-properties libffi-dev

sudo apt-get install rbenv

apt-get install rbenv ruby-build

This command allows the rbenv install

#rbenv plugins which allows to install latest ruby version
cd
git clone git://github.com/sstephenson/rbenv.git .rbenv
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(rbenv init -)"' >> ~/.bashrc
exec $SHELL

git clone git://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build
echo 'export PATH="$HOME/.rbenv/plugins/ruby-build/bin:$PATH"' >> ~/.bashrc
exec $SHELL

git clone https://github.com/sstephenson/rbenv-gem-rehash.git ~/.rbenv/plugins/rbenv-gem-rehash


