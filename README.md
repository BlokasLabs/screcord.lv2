screcord
===========

![screcord.lv2](https://github.com/brummer10/screcord.lv2/raw/master/screcord.png)

## a simple Lv2 capture plugin
- Include a mono and a stereo capture plugin.
- using libsndfile <a href="http://www.mega-nerd.com/libsndfile/">http://www.mega-nerd.com/libsndfile/</a>
- save audio stream as wav or ogg files to ~/lv2record/lv2_sessionX.wav/ogg were X is replaced by numbers


## build:
- no build dependency check, just make
- libsndfile is needed

## install:
- git submodule init
- git submodule update
- make
- make install # will install into ~/.lv2 ... AND/OR....
- sudo make install # will install into /usr/lib/lv2
