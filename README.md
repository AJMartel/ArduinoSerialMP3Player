# ArduinoSerialMP3Player
Playing MP3 files on a Serial MP3 Player board from Catalex (YX5300 chip)

There appear to be multiple versions of this board, the byte that controls the folder play option is different between boards. This fork corresponds to the v1.0 documentation which uses the 6'th byte to specify the folder (which works on my board). Some boards apparently follow the 1.0.1 documentation which uses the 7'th byte (both docs are included in this repository for your reference)

Buy the MP3 module on http://www.dx.com/p/uart-control-serial-mp3-music-player-module-for-arduino-avr-arm-pic-blue-silver-342439#.VfHyobPh5z0


Documentation and some Arduino code examples:

(Spanish)
http://joanruedapauweb.com/blog/index.php/2017/02/07/arduino-serial-mp3-player-yx5300-es/

(Chinese)(Catalex_YX5300_Docs.zip files)
http://pan.baidu.com/s/1hqilpB2

(English)
http://www.da-share.com/misc/catalex-mp3-board-yx5300-chip/

(French)
https://andrologiciels.wordpress.com/arduino/son-et-arduino/mp3/catalex-mp3-serie/

(Polish)
http://www.jarzebski.pl/arduino/komponenty/modul-mp3-z-ukladem-yx5300.html

(French)
https://www.carnetdumaker.net/articles/utiliser-un-lecteur-serie-de-fichiers-mp3-avec-une-carte-arduino-genuino/
