# Microdrone
POLISH
Status projektu: w trakcie
Projekt jest wykonywany w ramach studiów na Politechnice Łódzkiej na kierunku elektronika i telekomunikacja. Projekt ten polega na zaprojektowaniu, zbudowaniu i zaprogramowaniu mikrodrona (drona do 250 gram). Mikrodron jest zdalnie sterowany za pomocą aparatury sterującej BetaFPV LiteRadio 3 Pro, przy wykorzystaniu komunikacji ELRS 2,4 GHz. Zespół projektowy składa się z 2 osób. Waga naszego mikrodrona wyniosła 166 gram i jest to już ostateczna jego waga, wraz ze wszystkimi niezbędnymi elementami.

Założenia projektu:
•	dron przeznaczony do analizy infrastruktury
•	zdalnie sterowany – nadajnik (wraz z joystkickiem do sterowania) + odbiornik RC ELRS 2.4GHz
•	waga urządzenia – do 200 g
•	dron nie będzie latać w czasie opadów deszczu i śniegu
•	możliwość latania drona w umiarkowanych warunkach wietrznych
•	dron będzie quadkopterem – z 4 silnikami bezszczotkowymi 1104 
•	Zasięg mikrodrona – do 500 metrów
•	Czas lotu – do 7 minut
•	będzie zawierał ograniczoną autonomię – czujniki do wykrywania przeszkód

Wykorzystane elementy w projekcie:
•	1x Rama do drona FS135 3 calowa 1104
•	1x Akumulator GNB 11.4v 650mAh 160c
•	1x Zestaw kontrolera lotu + ESC SpeedyBee F405 Mini Stack
•	4x Silniki bezszczotkowe Darwin 1104 4300KV
•	4x Śmigła Gemfan 3016 3 calowe
•	1x Aparatura sterująca (nadajnik) BetaFPV LiteRadio 3 Pro ELRS
•	1x Odbiornik BETAFPV SuperD ELRS 2.4GHz
•	1x Kamera RunCam Thumb Pro
• 1x ładowarka do akumulatorów ISDT Q6 Nano
• 1x adapter złącza 5,5*2,1 female DC do XT60 female
• 1x adapter złącza XT60 female do XT30 male
• 1x adapter złącza XT30 male do przewodów
• 2x Super Magic Tape Tie (Pasek na akumulator) 



Co zrobiłem w projekcie?
•	Wspólnie z kolegą i koleżanką zaprojektowaliśmy wygląd naszego robota.
•	Testowałem czujniki do wykrywania przeszkód, taśmy aluminiowej oraz magnetycznej w celu wyboru najlepszego czujnika.
•	Wykonałem obudowę robota, dzięki czemu była możliwość zamontowania mikrokontrolera, czujników i sterownika silników.
•	Wykonałem odpowiednie otwory mocujące w obudowie, zamontowałem elementy, połączyłem je przewodami ze sobą, stworzyłem płytkę z goldpinami do rozciągniecia zasilania 5V.
•	Za pomocą programu STM32 Cube IDE napisałem program, obsługujący wszystkie czujniki, aby pojazd był w stanie odpowiednio reagować na przeszkody, nie wjeżdzać na nie, nie wyjeżdzać poza ograniczony obszar oraz wykrywać metę.
•	Byłem odpowiedzialny za estetykę i wygląd robota.
