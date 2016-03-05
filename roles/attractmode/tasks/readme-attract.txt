What do prepare for compile?

cd
mkdir source && cd source
curl https://codeload.github.com/mickelson/attract/tar.gz/v2.0.0-rc2
tar xzvf attract-2.0.0-rc2.tar.gz
cd attract-2.0.0-rc2/

sudo apt-get -y install libavformat-dev libavcodec-dev libswscale-dev libavutil-dev libswresample-dev libavresample-dev fontconfig libarchive-dev  libsfml-dev libopenal-dev

sudo apt-get -y install zlib1g-dev
sudo apt-get -y install libfreetype6-dev

sudo apt-get -y install libjpeg-dev
sudo apt-get -y install libglu1-mesa-dev

# build source code
make -j3 && echo make done

sudo make install
cp -r config ~/.attract


