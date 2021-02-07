# Hareket Sensörü ile Kanal Sinyalleri Oluşturmak
Daha önceden potansiyometreye ayarlı direnç dendiğinden bahsetmiştik. Bu devre elemanının;
* Üç bacağı olduğunu, 
* İlk ve son bacaklarına Arduino'nun Vcc (5V) ve GND pinlerinin bağlandığını, 
* Orta bacağının Arduino'nun analog girişlerinden bir tanesine (e.g., A0) bağlandığını, 
* Analogdan dijitale çevirici (Analog to Digital Converter - ADC) aracılığıyla [0-5V] aralığında sürekli (continuous) değer alabilen analog bir sinyalin, [0-1023] aralığında bir tam sayıya (integer) dönüştürülerek alındığını, 

görmüştük. Burada listelenen özellikleri Şekil 1'de görebilirsiniz.

<img src="potansiyometre.jpg" alt="Arduino ile potansiyometre arasındaki bağlantılar" width="200"/>

*Şekil 1: Arduino-potansiyometre bağlantıları.*
