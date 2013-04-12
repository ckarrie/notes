notes
=====

Installation von TvHeadend unter Ubuntu Linux
---------------------------------------------

Abhängigkeiten (mittes ./configure) und Installationsverlauf:

  git clone https://github.com/tvheadend/tvheadend.git
  cd tvheadend/
  sudo apt-get update
  sudo apt-get upgrade
  ./configure 
  sudo apt-get install libavcodec-dev libcurl3 libcurl-ocaml-dev
  ./configure 
  sudo apt-get install libavformat-dev 
  ./configure 
  sudo apt-get install libdvbcsa-dev 
  ./configure 
  ./configure --enable-dvbcsa
