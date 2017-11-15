# codeblocks_ubuntu_16  (work in progress)
Codeblock for ubuntu 16 and up, with repainting fixes.


```
git clone https://github.com/jenslody/codeblocks
  cd codeblocks/
  sudo apt-get install automake
  sudo apt-get install autoconf
  sudo apt-get install libtool
  ./bootstrap 
  sudo apt-get install wxWidget*
  sudo apt-get install glib-2.0
  sudo apt-get install libperl-dev
  sudo apt-get install libgtk2.0-dev
  sudo apt-get install hunspell
  sudo apt-get install libhuns*
  sudo apt-get install libgami*
  ./configure --with-contrib-plugins=all
  sudo echo /usr/local/lib > nano /etc/ld.so.conf.d/codeblocks.conf
  sudo ldconfig
  // run now codeblocks 
 
 
```

