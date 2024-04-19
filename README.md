Bu projede (3-6s) 70A' lik değere sahip ESC, drone üzerinde kullanım için tasarlanmıştır. Projenin şematik ve PCB dizaynı yapılmıştır.

Projede olabildiğince basit, kompakt ve ekstra soğutucu blok gerektirmeden 6s 70A' lik gücünün sağlanması hedeflenmiştir. Devrenin şematiği Ltspice programı üzerinden simüle edilerek tasarlanmıştır. 
Devrede basitlik amacıyla ATMEGA88-20AU MCU tercih edilmiştir. IR2101 kullanılarak, bootstrap sürme yöntemi ile mosfetler sürülmüştür. Feedback olarak (motor konumu için) BEMF (Back Electromotive Force) yöntemi tercih edilmiştir.

PCB dizaynında yollar, Saturn PCB Designer programı ile 70A' lık ısı taşıma kapasitesi sağlayabilecek şekilde tasarlanmıştır.

TOP_LAYER 

![1](https://github.com/sezear07/ESC--3-6S--70A/assets/167361624/44e40633-330b-4db3-9d8e-5ad7723e7a4e)
LAYER_2

![LOOIJJIIO0](https://github.com/sezear07/ESC--3-6S--70A/assets/167361624/e2dfea93-3825-4e76-9233-1b67eae14500)

LAYER_3
![3_layer PNG](https://github.com/sezear07/ESC--3-6S--70A/assets/167361624/f340290d-fd0b-44f9-b9e3-5530bc18ec81)

BOTTOM_LAYER
![Bottom_Layer PNG](https://github.com/sezear07/ESC--3-6S--70A/assets/167361624/59e3c2c1-9eff-414a-99de-d23d7f4c8237)

ŞEMATİK TASARIM
![434343333](https://github.com/sezear07/ESC--3-6S--70A/assets/167361624/62a65a82-6f40-4099-b51e-80dd2fc8bf3d)

PCB 3D ÖN TARAF
![1_3D PNG](https://github.com/sezear07/ESC--3-6S--70A/assets/167361624/a18b44fc-9516-436c-988e-feb107c9662c)

PCB 3D ARKA TARAF
![2_3D](https://github.com/sezear07/ESC--3-6S--70A/assets/167361624/51c471f9-1211-4edf-9aa7-c84fb09c6ed1)
