Стисле посилання на цей переклад: [https://bit.ly/SWRplots](https://bit.ly/SWRplots)

| ![](./img/SWR_Plots_of_FPV_image_1.png) | Нижче вичитаний людьми машинний український переклад оригіналу. Для [VictoryDrones](https://www.victory-drones.com/) переклад вичитали: Faina, Max Well\!, Block. Хочете покращити переклад чи знайшли помилку? — Лишіть коментар (Ctrl+Alt+M або «Меню» \> «Вставка» \> «Коментар»). Ми теж живі люди (як і ви) і робим помилки. Роботи їх, до речі, також роблять 😉 |
| :---: | :---- |

# **Графіки КСХ для різних антен — дізнайся який канал/частота є найкращими**

![](./img/SWR_Plots_of_FPV_image_2.png)

Оптимізація кожного аспекту налаштування вашого FPV дрона є ключовим для досягнення найкращої якості відео і дальності польоту. Розуміння **коефіцієнта стоячої хвилі** (КСХ) антени 5,8 ГГц може допомогти визначити, яку частоту або канал слід використовувати для оптимальної продуктивності. Не у всіх є інструменти для вимірювання КСХ, тому я провів широкомасштабні тести на антенах, які у мене є, щоб поділитися з вами їхніми графіками КСХ. 

*Деякі посилання на цій сторінці є партнерськими. Я \[автор англомовної версії Оскар Ланг\] отримую комісію (без додаткових витрат для вас), якщо ви робите покупку після натискання одного із цих партнерських посилань. Це допомагає підтримувати безкоштовний контент для спільноти на цьому веб\-сайті. Будь ласка, прочитайте нашу [Політику партнерських посилань](https://oscarliang.com/affiliate-program-policy/) для отримання додаткової інформації.*

Зміст

[Графіки КСХ для різних антен – дізнайся який канал є найкращим](#heading=h.obnfk0q1d5l4)

[Пояснення графіків КСХ](#пояснення-графіків-ксх)

[Поради для покращення відеозв'язку на FPV](#поради-для-покращення-відеозв’язку-на-fpv)

[Антена відеопередавача VTX DarwinFPV Darwin129](#антена-відеопередавача-vtx-darwinfpv-darwin129)

[Антена DJI FPV Air Unit SMA Part 05](#антена-dji-fpv-air-unit-sma-part-05)

[Антена окулярів DJI FPV Goggles V1](#антена-окулярів-dji-fpv-goggles-v1)

[Двохдіапазоннa aнтена DJI O3 Air Unit Dual-band](#двохдіапазоннa-aнтена-dji-o3-air-unit-dual-band)

[Діпольна aнтена Fatshark Rubber Duck Dipole](#діпольна-aнтена-fatshark-rubber-duck-dipole)

[FlyfishRC Osprey 140mm](#flyfishrc-osprey-140mm)

[FlyfishRC Osprey 40mm](#flyfishrc-osprey-40mm)

[Двоxдіапазонна антена FlyfishRC Osprey Dual-band 140mm](#двоxдіапазонна-антена-flyfishrc-osprey-dual-band-140mm)

[Двоxдіапазонна антена FlyfishRC Osprey Dual-band 70mm](#двоxдіапазонна-антена-flyfishrc-osprey-dual-band-70mm)

[Flywoo Atomic](#flywoo-atomic)

[Антена Flywoo O3 Lite](#антена-flywoo-o3-lite)

[Foxeer Lollipop 4 Stubby](#foxeer-lollipop-4-stubby)

[Foxeer Lollipop 4](#foxeer-lollipop-4)

[Foxeer Lollipop 4+ SMA](#foxeer-lollipop-4+-sma)

[Foxeer Lollipop 4+ UFL](#foxeer-lollipop-4+-ufl)

[Foxeer Lollipop V1](#foxeer-lollipop-v1)

[Foxeer Lollipop V2](#foxeer-lollipop-v2)

[Foxeer Micro Lollipop](#foxeer-micro-lollipop)

[Frsky Rondo](#frsky-rondo)

[HGLRC Hammer](#hglrc-hammer)

[iFlight Albatross](#iflight-albatross)

[Діпольна aнтена ImmersionRC Rubber Duck Dipole](#діпольна-aнтена-immersionrc-rubber-duck-dipole)

[Maple Leaf Patch 8.5dBi](#maple-leaf-patch-8.5dbi)

[Maple Leaf Lollipop 2dBi](#maple-leaf-lollipop-2dbi)

[Menace Invader](#menace-invader)

[Menace PicoPatch](#menace-picopatch)

[Антена Runcam Link Air Unit](#антена-runcam-link-air-unit)

[RushFPV Cherry 2 SMA](#rushfpv-cherry-2-sma)

[RushFPV Cherry 2 UFL](#rushfpv-cherry-2-ufl)

[RushFPV Cherry V1 SMA](#rushfpv-cherry-v1-sma)

[RushFPV Cherry V1 UFL](#rushfpv-cherry-v1-ufl)

[Speedybee LHCP SMA](#speedybee-lhcp-sma)

[Speedybee RHCP SMA](#speedybee-rhcp-sma)

[Speedybee RHCP UFL](#speedybee-rhcp-ufl)

[TrueRC Singularity Long 120mm](#truerc-singularity-long-120mm)

[TrueRC Singularity Regular 62mm](#truerc-singularity-regular-62mm)

[TrueRC Singularity Short 40mm](#truerc-singularity-short-40mm)

[TrueRC Singularity Stubby LHCP](#truerc-singularity-stubby-lhcp)

[TrueRC Singularity Stubby RHCP](#truerc-singularity-stubby-rhcp)

[TrueRC Sniper II](#truerc-sniper-ii)

[TrueRC X-Air MKII](#truerc-x-air-mkii)

[TrueRC X-Air MKII DJI FPV](#truerc-x-air-mkii-dji-fpv)

[Walksnail Mini 1S Lite](#walksnail-mini-1s-lite)

[Walksnail VTX V2](#walksnail-vtx-v2)

[Walksnail Redbird](#walksnail-redbird)

[Walksnail Redbird V2](#walksnail-redbird-v2)

[Висновок](#висновок)

# **Пояснення графіків КСХ** {#пояснення-графіків-ксх}

Що таке КСХ антени: [bit.ly/LiangBestFPVAnt](https://bit.ly/LiangBestFPVAnt). Хочете виміряти КСХ антени? Перегляньте мій поглиблений посібник: [https://bit.ly/MeasureAntennaSWR](https://bit.ly/MeasureAntennaSWR)  
Антени у цьому огляді розташовані в алфавітному порядку. Маркери графіка розміщені наступним чином: 

| Маркер 2 (M2) – на частоті 5.6 ГГц,  Маркер 3 (M3) – на 5.8 ГГц (центр графіка),  Маркер 4 (M4) – на 6.0 ГГц,  Маркер 1 (M1) показує місце з найнижчим КСХ в діапазоні вимірювання від 5.4 ГГц до 6.2 ГГц.  *\[збільшене зображення кожного графіку є в [оригінальному тексті](https://oscarliang.com/fpv-antenna-swr/) [https://oscarliang.com/fpv-antenna-swr](https://oscarliang.com/fpv-antenna-swr)\]* |
| :---- |

# **Поради для покращення відеозв’язку на FPV**  {#поради-для-покращення-відеозв’язку-на-fpv}

* **Вибір правильної антени:** розгляньте антени, де КСХ є постійно низьким на всіх каналах, які ви часто використовуєте.  
* **Оптимізація каналу:** використовуйте графіки КСХ, щоб визначити, які канали найкраще підходять для вашої обраної антени.  
* **Відповідність антен приймача:**  для найкращих результатів переконайтеся, що антени для приймача мають відповідну резонансну частоту. 

## **Антена відеопередавача VTX DarwinFPV Darwin129**  {#антена-відеопередавача-vtx-darwinfpv-darwin129}

Цe антена для дронy Darwin129 7″:   
[https://oscarliang.com/darwin129/](https://oscarliang.com/darwin129/)  
![Darwinfpv Darwin129 7 Inch Drone Vtx Antenna](./img/SWR_Plots_of_FPV_image_3.png)  
![Darwinfpv Darwin129 7 Inch Drone Vtx Antenna Swr 1](./img/SWR_Plots_of_FPV_image_4.png)

## **Антена DJI FPV Air Unit SMA Part 05** {#антена-dji-fpv-air-unit-sma-part-05}

Сторінка виробу: [https://amzn.to/3Uc2mhq](https://amzn.to/3Uc2mhq)  
![Dji Fpv Air Unit Antenna Sma](./img/SWR_Plots_of_FPV_image_5.png)  
![Dji Fpv Air Unit Antenna Sma Swr 1](./img/SWR_Plots_of_FPV_image_6.png)

## **Антена окулярів DJI FPV Goggles V1**  {#антена-окулярів-dji-fpv-goggles-v1}

Антени окулярів DJI FPV Goggles V1: [https://bit.ly/LiangDJI-FPV](https://bit.ly/LiangDJI-FPV)    
![](./img/SWR_Plots_of_FPV_image_7.png)  
![Dji Fpv Goggles V1 Antenna Swr 1](./img/SWR_Plots_of_FPV_image_8.png)  
Друга антена.  
![Dji Fpv Goggles V1 Antenna Swr 2](./img/SWR_Plots_of_FPV_image_9.png)

##  **Двохдіапазоннa aнтена DJI O3 Air Unit Dual-band**  {#двохдіапазоннa-aнтена-dji-o3-air-unit-dual-band}

Стандартна антена в модулі DJI O3 Air підтримує двохдіапазонну роботу — як 5,8 ГГц, так і 2,4 ГГц, тому ось графіки для обох частот. Вимірювання були проведені для обох роз'ємів.   
![Dji O3 Air Unit Dual Band Antenna](./img/SWR_Plots_of_FPV_image_10.png)  
Антена 1, роз'єм 1\.  
![Dji O3 Air Unit Dual Band Antenna Swr 1 5.8ghz Connector 1](./img/SWR_Plots_of_FPV_image_11.png) [![Dji O3 Air Unit Dual Band Antenna Swr 1 2.4ghz Connector 1](./img/SWR_Plots_of_FPV_image_12.png)](https://oscarliang.com/wp-content/uploads/2024/04/DJI-O3-Air-Unit-Dual-band-antenna-swr-1-5.8ghz-connector-1.jpg)  
Антена 1, роз'єм 2\.  
![Dji O3 Air Unit Dual Band Antenna Swr 1 5.8ghz Connector 2](./img/SWR_Plots_of_FPV_image_13.png) [![Dji O3 Air Unit Dual Band Antenna Swr 1 2.4ghz Connector 2](./img/SWR_Plots_of_FPV_image_14.png)](https://oscarliang.com/wp-content/uploads/2024/04/DJI-O3-Air-Unit-Dual-band-antenna-swr-1-5.8ghz-connector-2.jpg)  
Антена 2, роз'єм 1\.  
![Dji O3 Air Unit Dual Band Antenna Swr 2 5.8ghz Connector 1](./img/SWR_Plots_of_FPV_image_15.png) [![Dji O3 Air Unit Dual Band Antenna Swr 2 2.4ghz Connector 1](./img/SWR_Plots_of_FPV_image_16.png)](https://oscarliang.com/wp-content/uploads/2024/04/DJI-O3-Air-Unit-Dual-band-antenna-swr-2-5.8ghz-connector-1.jpg)  
Антена 2, роз'єм 2\.  
![Dji O3 Air Unit Dual Band Antenna Swr 2 5.8ghz Connector 2](./img/SWR_Plots_of_FPV_image_17.png) [![Dji O3 Air Unit Dual Band Antenna Swr 2 2.4ghz Connector 2](./img/SWR_Plots_of_FPV_image_18.png)](https://oscarliang.com/wp-content/uploads/2024/04/DJI-O3-Air-Unit-Dual-band-antenna-swr-2-5.8ghz-connector-2.jpg)

## **Діпольна aнтена Fatshark Rubber Duck Dipole**  {#діпольна-aнтена-fatshark-rubber-duck-dipole}

![Fatshark Rubber Duck Dipole Antenna](./img/SWR_Plots_of_FPV_image_19.png)  
![Fatshark Rubber Duck Dipole Antenna Swr 1](./img/SWR_Plots_of_FPV_image_20.png)  
Друга антена.  
![Fatshark Rubber Duck Dipole Antenna Swr 2](./img/SWR_Plots_of_FPV_image_21.png)

## **FlyfishRC Osprey 140mm** {#flyfishrc-osprey-140mm}

Сторінка виробу:

* AliExpress: [https://s.click.aliexpress.com/e/\_De4RCCt](https://s.click.aliexpress.com/e/_De4RCCt)  
* Amazon: [https://amzn.to/3U8l2Pk](https://amzn.to/3U8l2Pk)

![Flyfishrc Osprey Antenna 140mm Ufl](./img/SWR_Plots_of_FPV_image_22.png)  
![Flyfishrc Osprey Antenna 140mm Ufl Swr 1](./img/SWR_Plots_of_FPV_image_23.png)  
Друга антена.  
![Flyfishrc Osprey Antenna 140mm Ufl Swr 2](./img/SWR_Plots_of_FPV_image_24.png)

## **FlyfishRC Osprey 40mm** {#flyfishrc-osprey-40mm}

Сторінка виробу:

* AliExpress: [https://s.click.aliexpress.com/e/\_De4RCCt](https://s.click.aliexpress.com/e/_De4RCCt)  
* Amazon: [https://amzn.to/3U8l2Pk](https://amzn.to/3U8l2Pk)  
* RDQ: [https://oscarliang.com/product-d023](https://oscarliang.com/product-d023)

![Flyfishrc Osprey Antenna 40mm Ufl](./img/SWR_Plots_of_FPV_image_25.png)  
![Flyfishrc Osprey Antenna 40mm Ufl Swr 1](./img/SWR_Plots_of_FPV_image_26.png)

## **Двоxдіапазонна антена FlyfishRC Osprey Dual-band 140mm** {#двоxдіапазонна-антена-flyfishrc-osprey-dual-band-140mm}

Призначенo для роботи на діапазонах 2,4 ГГц та 5,8 ГГц.   
Сторінка виробу:

* AliExpress: [https://s.click.aliexpress.com/e/\_DB82r7x](https://s.click.aliexpress.com/e/_DB82r7x)  
* RDQ: [https://oscarliang.com/product-fl8d](https://oscarliang.com/product-fl8d)

![Flyfishrc Osprey Dual Band Antenna 140mm](./img/SWR_Plots_of_FPV_image_27.png)  
роз'єм 1\.  
![Flyfishrc Osprey Dual Band Antenna 140mm Swr 1 5.8ghz Connector 1](./img/SWR_Plots_of_FPV_image_28.png) [![Flyfishrc Osprey Dual Band Antenna 140mm Swr 1 2.4ghz Connector 1](./img/SWR_Plots_of_FPV_image_29.png)](https://oscarliang.com/wp-content/uploads/2024/04/FlyfishRC-Osprey-Dual-band-antenna-140mm-swr-1-5.8ghz-connector-1.jpg)  
роз'єм 2\.  
![Flyfishrc Osprey Dual Band Antenna 140mm Swr 1 5.8ghz Connector 2](./img/SWR_Plots_of_FPV_image_30.png) [![Flyfishrc Osprey Dual Band Antenna 140mm Swr 1 2.4ghz Connector 2](./img/SWR_Plots_of_FPV_image_31.png)](https://oscarliang.com/wp-content/uploads/2024/04/FlyfishRC-Osprey-Dual-band-antenna-140mm-swr-1-5.8ghz-connector-2.jpg)

## **Двоxдіапазонна антена FlyfishRC Osprey Dual-band 70mm** {#двоxдіапазонна-антена-flyfishrc-osprey-dual-band-70mm}

Призначенo для роботи на діапазонах 2,4 ГГц та 5,8 ГГц.   
Сторінка виробу:

* AliExpress: [https://s.click.aliexpress.com/e/\_DB82r7x](https://s.click.aliexpress.com/e/_DB82r7x)  
* RDQ: [https://oscarliang.com/product-fl8d](https://oscarliang.com/product-fl8d)

![Flyfishrc Osprey Dual Band Antenna 70mm](./img/SWR_Plots_of_FPV_image_32.png)  
роз'єм 1\.  
![Flyfishrc Osprey Dual Band Antenna 70mm Swr 1 5.8ghz Connector 1](./img/SWR_Plots_of_FPV_image_33.png) [![Flyfishrc Osprey Dual Band Antenna 70mm Swr 1 2.4ghz Connector 1](./img/SWR_Plots_of_FPV_image_34.png)](https://oscarliang.com/wp-content/uploads/2024/04/FlyfishRC-Osprey-Dual-band-antenna-70mm-swr-1-5.8ghz-connector-1.jpg)  
роз'єм 2\.  
![Flyfishrc Osprey Dual Band Antenna 70mm Swr 1 5.8ghz Connector 2](./img/SWR_Plots_of_FPV_image_35.png) [![Flyfishrc Osprey Dual Band Antenna 70mm Swr 1 2.4ghz Connector 2](./img/SWR_Plots_of_FPV_image_36.png)](https://oscarliang.com/wp-content/uploads/2024/04/FlyfishRC-Osprey-Dual-band-antenna-70mm-swr-1-5.8ghz-connector-2.jpg)

## **Flywoo Atomic** {#flywoo-atomic}

Сторінка виробу: [https://oscarliang.com/product-wk1k](https://oscarliang.com/product-wk1k)  
![Flywoo Atomic Antenna](./img/SWR_Plots_of_FPV_image_37.png)  
![Flywoo Atomic Antenna Swr 1](./img/SWR_Plots_of_FPV_image_38.png)

## **Антена Flywoo O3 Lite**  {#антена-flywoo-o3-lite}

Антени Flywoo Naked O3 Lite/Ultra kit: [https://oscarliang.com/flywoo-naked-o3-lite-ultra-kit/](https://oscarliang.com/flywoo-naked-o3-lite-ultra-kit/)  
![Flywoo O3 Lite Antenna](./img/SWR_Plots_of_FPV_image_39.png)  
![Flywoo O3 Lite Antenna Swr 1](./img/SWR_Plots_of_FPV_image_40.png)  
Друга антена.  
![Flywoo O3 Lite Antenna Swr 2](./img/SWR_Plots_of_FPV_image_41.png)

## **Foxeer Lollipop 4 Stubby** {#foxeer-lollipop-4-stubby}

Сторінка виробу:

* AliExpress: [https://s.click.aliexpress.com/e/\_DdQYU2V](https://s.click.aliexpress.com/e/_DdQYU2V)  
* Amazon: [https://amzn.to/3Uc9dGP](https://amzn.to/3Uc9dGP)  
* RDQ: [https://oscarliang.com/product-g4ht](https://oscarliang.com/product-g4ht)

![Foxeer Lollipop Antenna V4 Stubby](./img/SWR_Plots_of_FPV_image_42.png)  
![Foxeer Lollipop Antenna V4 Stubby Swr 1](./img/SWR_Plots_of_FPV_image_43.png)  
Друга антена.  
![Foxeer Lollipop Antenna V4 Stubby Swr 2](./img/SWR_Plots_of_FPV_image_44.png)

## **Foxeer Lollipop 4** {#foxeer-lollipop-4}

Сторінка виробу:

* AliExpress: [https://s.click.aliexpress.com/e/\_DCYJRHJ](https://s.click.aliexpress.com/e/_DCYJRHJ)  
* Amazon: [https://amzn.to/43UdDX8](https://amzn.to/43UdDX8)  
* RDQ: [https://oscarliang.com/product-qqzo](https://oscarliang.com/product-qqzo)

![Foxeer Lollipop Antenna V4](./img/SWR_Plots_of_FPV_image_45.png)  
![Foxeer Lollipop Antenna V4 Swr 1](./img/SWR_Plots_of_FPV_image_46.png)  
Друга антена.  
![Foxeer Lollipop Antenna V4 Swr 2](./img/SWR_Plots_of_FPV_image_47.png)

## **Foxeer Lollipop 4+ SMA** {#foxeer-lollipop-4+-sma}

Сторінка виробу:

* AliExpress: [https://s.click.aliexpress.com/e/\_DdUHwh3](https://s.click.aliexpress.com/e/_DdUHwh3)  
* Amazon: [https://amzn.to/3Ucpn4a](https://amzn.to/3Ucpn4a)  
* RDQ: [https://oscarliang.com/product-xz3d](https://oscarliang.com/product-xz3d)

![Foxeer Lollipop Antenna V4 4 Plus](./img/SWR_Plots_of_FPV_image_48.png)  
![Foxeer Lollipop Antenna V4 4 Plus. Swr 1](./img/SWR_Plots_of_FPV_image_49.png)

## **Foxeer Lollipop 4+ UFL** {#foxeer-lollipop-4+-ufl}

Сторінка виробу:

* AliExpress: [https://s.click.aliexpress.com/e/\_DdUHwh3](https://s.click.aliexpress.com/e/_DdUHwh3)  
* Amazon: [https://amzn.to/3Ucpn4a](https://amzn.to/3Ucpn4a)  
* RDQ: [https://oscarliang.com/product-kd3b](https://oscarliang.com/product-kd3b)

![Foxeer Lollipop Antenna V4 4 Plus Ufl](./img/SWR_Plots_of_FPV_image_50.png)  
![Foxeer Lollipop Antenna V4 4 Plus Ufl Swr 1](./img/SWR_Plots_of_FPV_image_51.png)

## **Foxeer Lollipop V1** {#foxeer-lollipop-v1}

Більше не виробляються.  
![Foxeer Lollipop Antenna V1](./img/SWR_Plots_of_FPV_image_52.png)  
![](./img/SWR_Plots_of_FPV_image_53.png)

## **Foxeer Lollipop V2** {#foxeer-lollipop-v2}

Більше не виробляються.  
![Foxeer Lollipop Antenna V2](./img/SWR_Plots_of_FPV_image_54.png)  
![Foxeer Lollipop Antenna V2 Swr 1](./img/SWR_Plots_of_FPV_image_55.png)

## **Foxeer Micro Lollipop** {#foxeer-micro-lollipop}

Сторінка виробу:

* AliExpress: [https://s.click.aliexpress.com/e/\_DkY1mvj](https://s.click.aliexpress.com/e/_DkY1mvj)  
* Amazon: [https://amzn.to/4d42cjZ](https://amzn.to/4d42cjZ)  
* RDQ: [https://oscarliang.com/product-4ef0](https://oscarliang.com/product-4ef0)

![Foxeer Micro Lollipop Antenna](./img/SWR_Plots_of_FPV_image_56.png)  
![Foxeer Micro Lollipop Antenna Swr 1](./img/SWR_Plots_of_FPV_image_57.png)  
Друга антена.  
![Foxeer Micro Lollipop Antenna Swr 2](./img/SWR_Plots_of_FPV_image_58.png)

## **Frsky Rondo** {#frsky-rondo}

Сторінка виробу: [https://s.click.aliexpress.com/e/\_DCbl49j](https://s.click.aliexpress.com/e/_DCbl49j)  
![Frsky Rondo Antenna](./img/SWR_Plots_of_FPV_image_59.png)  
![Frsky Rondo Antenna Swr 1](./img/SWR_Plots_of_FPV_image_60.png)

## **HGLRC Hammer** {#hglrc-hammer}

Сторінка виробу: [https://s.click.aliexpress.com/e/\_Dknx8al](https://s.click.aliexpress.com/e/_Dknx8al)  
![Hglrc Hammer Antenna V1](./img/SWR_Plots_of_FPV_image_61.png)  
![Hglrc Hammer Antenna V1 Swr 1](./img/SWR_Plots_of_FPV_image_62.png)

## **iFlight Albatross** {#iflight-albatross}

Антена застосована в багатьох моделях iFlight BNF, таких як Evoque i Nazgul.  
Сторінка виробу:

* AliExpress: [https://s.click.aliexpress.com/e/\_DBi3iZj](https://s.click.aliexpress.com/e/_DBi3iZj)  
* Amazon: [https://amzn.to/3vJPbuY](https://amzn.to/3vJPbuY)  
* RDQ: [https://oscarliang.com/product-0hbc](https://oscarliang.com/product-0hbc)

![Iflight Albatross Antenna](./img/SWR_Plots_of_FPV_image_63.png)  
![Iflight Albatross Antenna Swr 1](./img/SWR_Plots_of_FPV_image_64.png)  
Друга антена.  
![Iflight Albatross Antenna Swr 2](./img/SWR_Plots_of_FPV_image_65.png)

## **Діпольна aнтена ImmersionRC Rubber Duck Dipole**  {#діпольна-aнтена-immersionrc-rubber-duck-dipole}

![Immersionrc Rubber Duck Dipole Antenna](./img/SWR_Plots_of_FPV_image_66.png)  
![Immersionrc Rubber Duck Dipole Antenna Swr 1](./img/SWR_Plots_of_FPV_image_67.png)

## **Maple Leaf Patch 8.5dBi** {#maple-leaf-patch-8.5dbi}

Сторінка виробу: [https://s.click.aliexpress.com/e/\_DDU7A25](https://s.click.aliexpress.com/e/_DDU7A25)  
![Maple Leaf Patch Antenna](./img/SWR_Plots_of_FPV_image_68.png)  
![Maple Leaf Patch Antenna Swr 1](./img/SWR_Plots_of_FPV_image_69.png)

## **Maple Leaf Lollipop 2dBi** {#maple-leaf-lollipop-2dbi}

Сторінка виробу: [https://s.click.aliexpress.com/e/\_DERjADj](https://s.click.aliexpress.com/e/_DERjADj)  
![Maple Leaf Lollipop Antenna](./img/SWR_Plots_of_FPV_image_70.png)  
![Maple Leaf Lollipop Antenna Swr 1](./img/SWR_Plots_of_FPV_image_71.png)

## **Menace Invader** {#menace-invader}

Сторінка виробу: [https://oscarliang.com/product-b07k](https://oscarliang.com/product-b07k)  
![Menace Invader Patch Antenna](./img/SWR_Plots_of_FPV_image_72.png)  
![Menace Invader Patch Antenna Swr 1](./img/SWR_Plots_of_FPV_image_73.png)  
Друга антена.  
![Menace Invader Patch Antenna Swr 2](./img/SWR_Plots_of_FPV_image_74.png)

## **Menace PicoPatch** {#menace-picopatch}

Сторінка виробу:

* GetFPV: [https://oscarliang.com/product-k6jp](https://oscarliang.com/product-k6jp)  
* RDQ: [https://oscarliang.com/product-9imj](https://oscarliang.com/product-9imj)

![Menace Picopatch Antenna](./img/SWR_Plots_of_FPV_image_75.png)  
![Menace Picopatch Antenna Swr 1](./img/SWR_Plots_of_FPV_image_76.png)

## **Антена Runcam Link Air Unit**  {#антена-runcam-link-air-unit}

Стандартна антена йде в комплекті з Runcam Link Air Unit (Caddx Vista).  
![Runcam Link Antenna](./img/SWR_Plots_of_FPV_image_77.png)  
![Runcam Link Antenna Swr 1](./img/SWR_Plots_of_FPV_image_78.png)

## **RushFPV Cherry 2 SMA** {#rushfpv-cherry-2-sma}

Сторінка виробу:

* AliExpress: [https://s.click.aliexpress.com/e/\_DmaS67R](https://s.click.aliexpress.com/e/_DmaS67R)  
* Amazon: [https://amzn.to/4aNWksO](https://amzn.to/4aNWksO)

![Rushfpv Cherry Antenna V2 Sma](./img/SWR_Plots_of_FPV_image_79.png)  
![Rushfpv Cherry Antenna V2 Sma Swr 1](./img/SWR_Plots_of_FPV_image_80.png)  
Друга антена.  
![Rushfpv Cherry Antenna V2 Sma Swr 2](./img/SWR_Plots_of_FPV_image_81.png)

## **RushFPV Cherry 2 UFL** {#rushfpv-cherry-2-ufl}

Сторінка виробу: [https://s.click.aliexpress.com/e/\_DmaS67R](https://s.click.aliexpress.com/e/_DmaS67R)  
![Rushfpv Cherry Antenna V2 Ufl](./img/SWR_Plots_of_FPV_image_82.png)  
![Rushfpv Cherry Antenna V2 Ufl Swr 1](./img/SWR_Plots_of_FPV_image_83.png)

## **RushFPV Cherry V1 SMA** {#rushfpv-cherry-v1-sma}

Сторінка виробу:

* RDQ: [https://oscarliang.com/product-m4qr](https://oscarliang.com/product-m4qr)  
* AliExpress: [https://s.click.aliexpress.com/e/\_DFpVse5](https://s.click.aliexpress.com/e/_DFpVse5)

![Rushfpv Cherry Antenna V1 Sma](./img/SWR_Plots_of_FPV_image_84.png)  
![Rushfpv Cherry Antenna V1 Sma Swr 1](./img/SWR_Plots_of_FPV_image_85.png)  
Друга антена.  
![Rushfpv Cherry Antenna V1 Sma Swr 2](./img/SWR_Plots_of_FPV_image_86.png)

## **RushFPV Cherry V1 UFL** {#rushfpv-cherry-v1-ufl}

Більше не виробляються.  
![Rushfpv Cherry Antenna V1 Ufl](./img/SWR_Plots_of_FPV_image_87.png)  
![Rushfpv Cherry Antenna V1 Ufl Swr 1](./img/SWR_Plots_of_FPV_image_88.png)

## **Speedybee LHCP SMA** {#speedybee-lhcp-sma}

Сторінка виробу:

* AliExpress: [https://s.click.aliexpress.com/e/\_DeEAFR3](https://s.click.aliexpress.com/e/_DeEAFR3)  
* Speedybee: [https://oscarliang.com/product-unay](https://oscarliang.com/product-unay)

![Speedybee 5.8ghz Antenna Lhcp Sma](./img/SWR_Plots_of_FPV_image_89.png)  
![Speedybee 5.8ghz Antenna Lhcp Sma Swr 1](./img/SWR_Plots_of_FPV_image_90.png)  
Друга антена.  
![Speedybee 5.8ghz Antenna Lhcp Sma Swr 2](./img/SWR_Plots_of_FPV_image_91.png)

## **Speedybee RHCP SMA** {#speedybee-rhcp-sma}

Сторінка виробу:

* AliExpress: [https://s.click.aliexpress.com/e/\_DeEAFR3](https://s.click.aliexpress.com/e/_DeEAFR3)  
* Speedybee: [https://oscarliang.com/product-unay](https://oscarliang.com/product-unay)

![Speedybee 5.8ghz Antenna Rhcp Sma](./img/SWR_Plots_of_FPV_image_92.png)  
![Speedybee 5.8ghz Antenna Rhcp Sma Swr 1](./img/SWR_Plots_of_FPV_image_93.png)  
Друга антена.  
![Speedybee 5.8ghz Antenna Rhcp Sma Swr 2](./img/SWR_Plots_of_FPV_image_94.png)

## **Speedybee RHCP UFL** {#speedybee-rhcp-ufl}

Сторінка виробу:

* AliExpress: [https://s.click.aliexpress.com/e/\_DeEAFR3](https://s.click.aliexpress.com/e/_DeEAFR3)  
* Speedybee: [https://oscarliang.com/product-unay](https://oscarliang.com/product-unay)

![Speedybee 5.8ghz Antenna Rhcp Ufl](./img/SWR_Plots_of_FPV_image_95.png)  
![Speedybee 5.8ghz Antenna Rhcp Ufl. Swr 1](./img/SWR_Plots_of_FPV_image_96.png)

## **TrueRC Singularity Long 120mm** {#truerc-singularity-long-120mm}

Сторінка виробу:

* GetFPV: [https://oscarliang.com/product-2q8f](https://oscarliang.com/product-2q8f)  
* Amazon: [https://amzn.to/4cOH018](https://amzn.to/4cOH018)

![Truerc Singularity Antenna Long 120mm Sma](./img/SWR_Plots_of_FPV_image_97.png)  
![Truerc Singularity Antenna Long 120mm Sma Swr 1](./img/SWR_Plots_of_FPV_image_98.png)

## **TrueRC Singularity Regular 62mm** {#truerc-singularity-regular-62mm}

Сторінка виробу:

* GetFPV: [https://oscarliang.com/product-sscm](https://oscarliang.com/product-sscm)  
* Amazon: [https://amzn.to/4cOH018](https://amzn.to/4cOH018)

![Truerc Singularity Antenna Regular 62mm Sma](./img/SWR_Plots_of_FPV_image_99.png)  
![Truerc Singularity Antenna Regular 62mm Sma Swr 1](./img/SWR_Plots_of_FPV_image_100.png)

## **TrueRC Singularity Short 40mm** {#truerc-singularity-short-40mm}

Сторінка виробу:

* RDQ: [https://oscarliang.com/product-npd0](https://oscarliang.com/product-npd0)  
* Amazon: [https://amzn.to/4cOH018](https://amzn.to/4cOH018)

![Truerc Singularity Antenna Short 40mm Ufl](./img/SWR_Plots_of_FPV_image_101.png)  
![Truerc Singularity Antenna Short 40mm Ufl Swr 1](./img/SWR_Plots_of_FPV_image_102.png)  
Друга антена.  
![Truerc Singularity Antenna Short 40mm Ufl Swr 2](./img/SWR_Plots_of_FPV_image_103.png)

## **TrueRC Singularity Stubby LHCP** {#truerc-singularity-stubby-lhcp}

Сторінка виробу:

* RDQ: [https://oscarliang.com/product-9n6w](https://oscarliang.com/product-9n6w)  
* GetFPV: [https://oscarliang.com/product-rh9l](https://oscarliang.com/product-rh9l)  
* Amazon: [https://amzn.to/4cOH018](https://amzn.to/4cOH018)

![Truerc Singularity Antenna Stubby Lhcp Rpsma](./img/SWR_Plots_of_FPV_image_104.png)  
![Truerc Singularity Antenna Stubby Lhcp Rpsma Swr 1](./img/SWR_Plots_of_FPV_image_105.png)

## **TrueRC Singularity Stubby RHCP** {#truerc-singularity-stubby-rhcp}

Сторінка виробу:

* RDQ: [https://oscarliang.com/product-90d9](https://oscarliang.com/product-90d9)  
* GetFPV: [https://oscarliang.com/product-husz](https://oscarliang.com/product-husz)  
* Amazon: [https://amzn.to/4cOH018](https://amzn.to/4cOH018)

![Truerc Singularity Antenna Stubby Rhcp Sma](./img/SWR_Plots_of_FPV_image_106.png)  
![Truerc Singularity Antenna Stubby Rhcp Sma Swr 1](./img/SWR_Plots_of_FPV_image_107.png)  
Друга антена  
![Truerc Singularity Antenna Stubby Rhcp Sma Swr 2](./img/SWR_Plots_of_FPV_image_108.png)

## **TrueRC Sniper II** {#truerc-sniper-ii}

Сторінка виробу:

* GetFPV: [https://oscarliang.com/product-oo57](https://oscarliang.com/product-oo57)  
* Amazon: [https://amzn.to/4aEAWq6](https://amzn.to/4aEAWq6)

![Truerc Sniper Ii Antenna](./img/SWR_Plots_of_FPV_image_109.png)  
![Truerc Sniper Ii Antenna Swr 1](./img/SWR_Plots_of_FPV_image_110.png)

## **TrueRC X-Air MKII** {#truerc-x-air-mkii}

Сторінка виробу:

* GetFPV: [https://oscarliang.com/product-khsf](https://oscarliang.com/product-khsf)  
* Amazon: [https://amzn.to/4arnfLz](https://amzn.to/4arnfLz)  
* RDQ: [https://oscarliang.com/product-qsct](https://oscarliang.com/product-qsct)

![Truerc X Air Mkii Antenna](./img/SWR_Plots_of_FPV_image_111.png)  
![Truerc X Air Mkii Antenna Swr 1](./img/SWR_Plots_of_FPV_image_112.png)

## **TrueRC X-Air MKII DJI FPV** {#truerc-x-air-mkii-dji-fpv}

Сторінка виробу:

* GetFPV: [https://oscarliang.com/product-d9e0](https://oscarliang.com/product-d9e0)  
* Amazon: [https://amzn.to/3vTsGDJ](https://amzn.to/3vTsGDJ)  
* RDQ: [https://oscarliang.com/product-c724](https://oscarliang.com/product-c724)

![Truerc X Air Mkii Antenna Dji Fpv](./img/SWR_Plots_of_FPV_image_113.png)  
роз'єм на кабелі   
![Truerc X Air Mkii Antenna Dji Fpv Swr 1 Cable Connector](./img/SWR_Plots_of_FPV_image_114.png)  
роз'єм на корпусі  
![Truerc X Air Mkii Antenna Dji Fpv Swr 1 Body Connector](./img/SWR_Plots_of_FPV_image_115.png)

## **Walksnail Mini 1S Lite** {#walksnail-mini-1s-lite}

Сторінка виробу: [https://oscarliang.com/product-s6ns](https://oscarliang.com/product-s6ns)  
![Walksnail Mini 1s Lite Antenna](./img/SWR_Plots_of_FPV_image_116.png)  
![Walksnail Mini 1s Lite Antenna Swr 1](./img/SWR_Plots_of_FPV_image_117.png)

## **Walksnail VTX V2** {#walksnail-vtx-v2}

Сторінка виробу: [https://oscarliang.com/product-vgtf](https://oscarliang.com/product-vgtf)  
![Walksnail Vtx V2 Antenna](./img/SWR_Plots_of_FPV_image_118.png)  
![Walksnail Vtx V2 Antenna Swr 1](./img/SWR_Plots_of_FPV_image_119.png)  
Друга антена.  
![Walksnail Vtx V2 Antenna Swr 2](./img/SWR_Plots_of_FPV_image_120.png)

## **Walksnail Redbird** {#walksnail-redbird}

Сторінка виробу: [https://oscarliang.com/product-n73v](https://oscarliang.com/product-n73v)  
![Walksnail Redbird Antenna V1](./img/SWR_Plots_of_FPV_image_121.png)  
![Walksnail Redbird Antenna V1 Swr 1](./img/SWR_Plots_of_FPV_image_122.png)  
Друга антена.  
![Walksnail Redbird Antenna V1 Swr 2](./img/SWR_Plots_of_FPV_image_123.png)

## **Walksnail Redbird V2** {#walksnail-redbird-v2}

Сторінка виробу:

* AliExpress: [https://s.click.aliexpress.com/e/\_DePvymV](https://s.click.aliexpress.com/e/_DePvymV)  
* GetFPV: [https://oscarliang.com/product-9nf0](https://oscarliang.com/product-9nf0)  
* RDQ: [https://oscarliang.com/product-3d2g](https://oscarliang.com/product-3d2g)  
* Caddx: [https://oscarliang.com/product-024k](https://oscarliang.com/product-024k)

![Walksnail Redbird Antenna V2](./img/SWR_Plots_of_FPV_image_124.png)  
![Walksnail Redbird Antenna V2 Swr 1](./img/SWR_Plots_of_FPV_image_125.png)  
Друга антена.  
![Walksnail Redbird Antenna V2 Swr 2](./img/SWR_Plots_of_FPV_image_126.png)

# **Висновок**  {#висновок}

Коефіцієнт стоячої хвилі (КСХ) відіграє ключову роль у досягненні надійного відеозв'язку FPV. Розуміючи КСХ антени, пілоти можуть приймати обґрунтовані рішення, вибираючи найбільш підходящі антени та частоти/канали для своїх польотів. Я планую продовжувати тестування різних антен та буду регулярно оновлювати цей пост. Якщо у вас є конкретна антена, яку ви хочете, щоб я протестував, повідомте мені у коментарях. Приємних польотів\! 

[image1]: ![](./img/SWR_Plots_of_FPV_image_1.png)

[image2]: ![](./img/SWR_Plots_of_FPV_image_2.png)

[image3]: ![](./img/SWR_Plots_of_FPV_image_3.png)

[image4]: ![](./img/SWR_Plots_of_FPV_image_4.png)

[image5]: ![](./img/SWR_Plots_of_FPV_image_5.png)

[image6]: ![](./img/SWR_Plots_of_FPV_image_6.png)

[image7]: ![](./img/SWR_Plots_of_FPV_image_7.png)

[image8]: ![](./img/SWR_Plots_of_FPV_image_8.png)

[image9]: ![](./img/SWR_Plots_of_FPV_image_9.png)

[image10]: ![](./img/SWR_Plots_of_FPV_image_10.png)

[image11]: ![](./img/SWR_Plots_of_FPV_image_11.png)

[image12]: ![](./img/SWR_Plots_of_FPV_image_12.png)

[image13]: ![](./img/SWR_Plots_of_FPV_image_13.png)

[image14]: ![](./img/SWR_Plots_of_FPV_image_14.png)

[image15]: ![](./img/SWR_Plots_of_FPV_image_15.png)

[image16]: ![](./img/SWR_Plots_of_FPV_image_16.png)

[image17]: ![](./img/SWR_Plots_of_FPV_image_17.png)

[image18]: ![](./img/SWR_Plots_of_FPV_image_18.png)

[image19]: ![](./img/SWR_Plots_of_FPV_image_19.png)

[image20]: ![](./img/SWR_Plots_of_FPV_image_20.png)

[image21]: ![](./img/SWR_Plots_of_FPV_image_21.png)

[image22]: ![](./img/SWR_Plots_of_FPV_image_22.png)

[image23]: ![](./img/SWR_Plots_of_FPV_image_23.png)

[image24]: ![](./img/SWR_Plots_of_FPV_image_24.png)

[image25]: ![](./img/SWR_Plots_of_FPV_image_25.png)

[image26]: ![](./img/SWR_Plots_of_FPV_image_26.png)

[image27]: ![](./img/SWR_Plots_of_FPV_image_27.png)

[image28]: ![](./img/SWR_Plots_of_FPV_image_28.png)

[image29]: ![](./img/SWR_Plots_of_FPV_image_29.png)

[image30]: ![](./img/SWR_Plots_of_FPV_image_30.png)

[image31]: ![](./img/SWR_Plots_of_FPV_image_31.png)

[image32]: ![](./img/SWR_Plots_of_FPV_image_32.png)

[image33]: ![](./img/SWR_Plots_of_FPV_image_33.png)

[image34]: ![](./img/SWR_Plots_of_FPV_image_34.png)

[image35]: ![](./img/SWR_Plots_of_FPV_image_35.png)

[image36]: ![](./img/SWR_Plots_of_FPV_image_36.png)

[image37]: ![](./img/SWR_Plots_of_FPV_image_37.png)

[image38]: ![](./img/SWR_Plots_of_FPV_image_38.png)

[image39]: ![](./img/SWR_Plots_of_FPV_image_39.png)

[image40]: ![](./img/SWR_Plots_of_FPV_image_40.png)

[image41]: ![](./img/SWR_Plots_of_FPV_image_41.png)

[image42]: ![](./img/SWR_Plots_of_FPV_image_42.png)

[image43]: ![](./img/SWR_Plots_of_FPV_image_43.png)

[image44]: ![](./img/SWR_Plots_of_FPV_image_44.png)

[image45]: ![](./img/SWR_Plots_of_FPV_image_45.png)

[image46]: ![](./img/SWR_Plots_of_FPV_image_46.png)

[image47]: ![](./img/SWR_Plots_of_FPV_image_47.png)

[image48]: ![](./img/SWR_Plots_of_FPV_image_48.png)

[image49]: ![](./img/SWR_Plots_of_FPV_image_49.png)

[image50]: ![](./img/SWR_Plots_of_FPV_image_50.png)

[image51]: ![](./img/SWR_Plots_of_FPV_image_51.png)

[image52]: ![](./img/SWR_Plots_of_FPV_image_52.png)

[image53]: ![](./img/SWR_Plots_of_FPV_image_53.png)

[image54]: ![](./img/SWR_Plots_of_FPV_image_54.png)

[image55]: ![](./img/SWR_Plots_of_FPV_image_55.png)

[image56]: ![](./img/SWR_Plots_of_FPV_image_56.png)

[image57]: ![](./img/SWR_Plots_of_FPV_image_57.png)

[image58]: ![](./img/SWR_Plots_of_FPV_image_58.png)

[image59]: ![](./img/SWR_Plots_of_FPV_image_59.png)

[image60]: ![](./img/SWR_Plots_of_FPV_image_60.png)

[image61]: ![](./img/SWR_Plots_of_FPV_image_61.png)

[image62]: ![](./img/SWR_Plots_of_FPV_image_62.png)

[image63]: ![](./img/SWR_Plots_of_FPV_image_63.png)

[image64]: ![](./img/SWR_Plots_of_FPV_image_64.png)

[image65]: ![](./img/SWR_Plots_of_FPV_image_65.png)

[image66]: ![](./img/SWR_Plots_of_FPV_image_66.png)

[image67]: ![](./img/SWR_Plots_of_FPV_image_67.png)

[image68]: ![](./img/SWR_Plots_of_FPV_image_68.png)

[image69]: ![](./img/SWR_Plots_of_FPV_image_69.png)

[image70]: ![](./img/SWR_Plots_of_FPV_image_70.png)

[image71]: ![](./img/SWR_Plots_of_FPV_image_71.png)

[image72]: ![](./img/SWR_Plots_of_FPV_image_72.png)

[image73]: ![](./img/SWR_Plots_of_FPV_image_73.png)

[image74]: ![](./img/SWR_Plots_of_FPV_image_74.png)

[image75]: ![](./img/SWR_Plots_of_FPV_image_75.png)

[image76]: ![](./img/SWR_Plots_of_FPV_image_76.png)

[image77]: ![](./img/SWR_Plots_of_FPV_image_77.png)

[image78]: ![](./img/SWR_Plots_of_FPV_image_78.png)

[image79]: ![](./img/SWR_Plots_of_FPV_image_79.png)

[image80]: ![](./img/SWR_Plots_of_FPV_image_80.png)

[image81]: ![](./img/SWR_Plots_of_FPV_image_81.png)

[image82]: ![](./img/SWR_Plots_of_FPV_image_82.png)

[image83]: ![](./img/SWR_Plots_of_FPV_image_83.png)

[image84]: ![](./img/SWR_Plots_of_FPV_image_84.png)

[image85]: ![](./img/SWR_Plots_of_FPV_image_85.png)

[image86]: ![](./img/SWR_Plots_of_FPV_image_86.png)

[image87]: ![](./img/SWR_Plots_of_FPV_image_87.png)

[image88]: ![](./img/SWR_Plots_of_FPV_image_88.png)

[image89]: ![](./img/SWR_Plots_of_FPV_image_89.png)

[image90]: ![](./img/SWR_Plots_of_FPV_image_90.png)

[image91]: ![](./img/SWR_Plots_of_FPV_image_91.png)

[image92]: ![](./img/SWR_Plots_of_FPV_image_92.png)

[image93]: ![](./img/SWR_Plots_of_FPV_image_93.png)

[image94]: ![](./img/SWR_Plots_of_FPV_image_94.png)

[image95]: ![](./img/SWR_Plots_of_FPV_image_95.png)

[image96]: ![](./img/SWR_Plots_of_FPV_image_96.png)

[image97]: ![](./img/SWR_Plots_of_FPV_image_97.png)

[image98]: ![](./img/SWR_Plots_of_FPV_image_98.png)

[image99]: ![](./img/SWR_Plots_of_FPV_image_99.png)

[image100]: ![](./img/SWR_Plots_of_FPV_image_100.png)

[image101]: ![](./img/SWR_Plots_of_FPV_image_101.png)

[image102]: ![](./img/SWR_Plots_of_FPV_image_102.png)

[image103]: ![](./img/SWR_Plots_of_FPV_image_103.png)

[image104]: ![](./img/SWR_Plots_of_FPV_image_104.png)

[image105]: ![](./img/SWR_Plots_of_FPV_image_105.png)

[image106]: ![](./img/SWR_Plots_of_FPV_image_106.png)

[image107]: ![](./img/SWR_Plots_of_FPV_image_107.png)

[image108]: ![](./img/SWR_Plots_of_FPV_image_108.png)

[image109]: ![](./img/SWR_Plots_of_FPV_image_109.png)

[image110]: ![](./img/SWR_Plots_of_FPV_image_110.png)

[image111]: ![](./img/SWR_Plots_of_FPV_image_111.png)

[image112]: ![](./img/SWR_Plots_of_FPV_image_112.png)

[image113]: ![](./img/SWR_Plots_of_FPV_image_113.png)

[image114]: ![](./img/SWR_Plots_of_FPV_image_114.png)

[image115]: ![](./img/SWR_Plots_of_FPV_image_115.png)

[image116]: ![](./img/SWR_Plots_of_FPV_image_116.png)

[image117]: ![](./img/SWR_Plots_of_FPV_image_117.png)

[image118]: ![](./img/SWR_Plots_of_FPV_image_118.png)

[image119]: ![](./img/SWR_Plots_of_FPV_image_119.png)

[image120]: ![](./img/SWR_Plots_of_FPV_image_120.png)

[image121]: ![](./img/SWR_Plots_of_FPV_image_121.png)

[image122]: ![](./img/SWR_Plots_of_FPV_image_122.png)

[image123]: ![](./img/SWR_Plots_of_FPV_image_123.png)

[image124]: ![](./img/SWR_Plots_of_FPV_image_124.png)

[image125]: ![](./img/SWR_Plots_of_FPV_image_125.png)

[image126]: ![](./img/SWR_Plots_of_FPV_image_126.png)