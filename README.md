Installation of Osmedeus

Follow this link to see a video instruction
https://www.youtube.com/playlist?list=PLiifzv5MjIo3JqKeG5EXbSKDBlqa7v14P



Install from a base repository
NOTE that you need some essential tools like curl, wget, git, zip, tmux and login as root to start
bash <(curl -fsSL https://raw.githubusercontent.com/osmedeus/osmedeus-base/master/install.sh)



Install for MacOS (experimental)
NOTE that you need to install homebrew first.
bash <(curl -fsSL https://raw.githubusercontent.com/osmedeus/osmedeus-base/master/install-macos.sh)
Some other changes you might need to make if you're really want to use Osmedeus on MacOS



📦 Install from a build release
Make sure you login as root otherwise run sudo su first then put build-osm.zip to any folder (e.g: /opt/)

unzip -q build-osm.zip && cd build-osm
./build.sh



# verify your installation with health command
osmedeus health



Using Docker
Pull the Docker image by running docker pull j3ssie/osmedeus



Verify the installation process
Just run the command osmedeus health. If you see the content like a image below then it's mean the installation process has been success.
![image](https://user-images.githubusercontent.com/106616965/171278491-6a3405a6-ca70-4a74-b070-e73cd756d577.png)


**** All credits go to: https://docs.osmedeus.org/installation/#verify-the-installation-process ****
