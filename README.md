# Microdrone
POLISH
Status projektu: w trakcie
Projekt jest wykonywany w ramach studiów na Politechnice Łódzkiej na kierunku elektronika i telekomunikacja. Projekt ten polega na zaprojektowaniu, zbudowaniu i zaprogramowaniu mikrodrona (drona do 250 gram). Mikrodron jest zdalnie sterowany za pomocą aparatury sterującej BetaFPV LiteRadio 3 Pro, przy wykorzystaniu komunikacji ELRS 2,4 GHz. Zespół projektowy składa się z 2 osób. Waga naszego mikrodrona wyniosła 166 gram i jest to już ostateczna jego waga, wraz ze wszystkimi niezbędnymi elementami. W mikrodronie zdecydowano się wybrać kontroler lotu FC + regulator obrotów silników (ESC) SpeedyBee F405 Mini, ze względu na to, że nie tylko jest dobrej jakości i w dobrej cenie, ale także można go programować przy wykorzystaniu aplikacji mobilnej producenta SpeedyBee, co jest bardzo pomocne przy kalibracji akcelerometru przed lotem. Silniki oraz śmigła wybrano w oparciu o opinie innych użytkowników oraz analizie sprawności kilku silników, spośród których to silniki Darwin 1104 4300KV wypadły najlepiej. Przy wyborze akumulatora postawiono na sprawdzoną firmę GNB oraz uznano, że pojemność 650 mAh, będzie najlepsza w naszych założeniach o jak najmniejszej możliwej wadze oraz czasu lotu dronem. Kamera RunCam Thumb Pro została wybrana, ponieważ umożliwia nagrywanie na karcie microSD, bez konieczności transmisji na żywo, co znacznie zmniejsza zużycie akumulatora w mikrodronie.

Założenia projektu:
•	dron przeznaczony do analizy infrastruktury
•	zdalnie sterowany – nadajnik (wraz z joystkickiem do sterowania) + odbiornik RC ELRS 2.4GHz
•	waga urządzenia – do 200 g
•	dron nie będzie latać w czasie opadów deszczu i śniegu
•	możliwość latania drona w umiarkowanych warunkach wietrznych
•	dron będzie quadkopterem – z 4 silnikami bezszczotkowymi 1104 
•	zasięg mikrodrona – do 500 metrów
•	czas lotu – do 7 minut
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
•	Wspólnie z koleżanką zaprojektowaliśmy wygląd naszego mikrodrona.
•	Byłem po części odpowiedzialny za wybór komponentów do drona.
•	Wspólnie z koleżanką zbudowaliśmy mikrodrona.
•	Przylutowałem przewody silników oraz inne przewody zasilające do regulatora obrotu silników ESC.
•	Zmieniłem kierunki obrotu niektórych silników, zgodnie z zaleceniami w programie BLHeliSuite.
•	Dokonałem testu silników w programie Betaflight Configurator.
•	Wspólnie założyliśmy śmigła na silniki zgodnie z zaleceniami (3016, 3016R).
•	Przylutowałem przewody kamery oraz odbiornika do kontrolera lotu FC.
•	Zaktualizowałem wersję nadajnika w programie ExpressLRS Configurator.
•	Zaprogramowałem odpowiednio odbiornik oraz funkcje przełączników nadajnika (tryb ARM, tryb Angle, tryb Horizon).
•	Połączyłem nadajnik z odbiornikiem za pomocą komunikacji ELRS.
•	Wspólnie wykonaliśmy pierwsze (udane testy) mikrodrona w zakresie latania z wykorzystaniem trybu stabilizującego lot (tryb Angle) oraz bez tego trybu.
•	W nadajniku dodałem dodatkowe funkcje, takie jak odliczanie czasu, pozostałego do lądowania dronem.

Na obecną chwilę mikrodron bez problemu wznosi się nad ziemią, jednak wymaga jeszcze kilku usprawnień. Można nim sterować za pomocą nadajnika. Kamera działa poprawnie. Zapisuje nagrania na karcie microSD, które można obejrzeć na komputerze po podłączeniu do komputera.


ENGLISH
Project status: in progress
The project is being carried out as part of studies at the Lodz University of Technology in the field of electronics and telecommunications. This project involves designing, building and programming a microdrone (drone up to 250 grams). The microdrone is remotely controlled using the BetaFPV LiteRadio 3 Pro control unit, using ELRS 2.4 GHz communication. The project team consists of 2 people. The weight of our microdrone was 166 grams and this is its final weight, along with all the necessary elements. In the microdrone, it was decided to choose the FC flight controller + engine speed controller (ESC) SpeedyBee F405 Mini, due to the fact that it is not only of good quality and at a good price, but can also be programmed using the SpeedyBee manufacturer's mobile application, which is very helpful in calibrating the accelerometer before flight. The motors and propellers were selected based on the opinions of other users and the analysis of the efficiency of several motors, of which the Darwin 1104 4300KV motors performed best. When choosing the battery, we chose the proven GNB company and it was decided that the capacity of 650 mAh would be the best in our assumptions about the lowest possible weight and flight time of the drone. The RunCam Thumb Pro camera was chosen because it allows recording on a microSD card, without the need for live transmission, which significantly reduces the battery consumption in the microdrone.

Project assumptions:
• drone designed for infrastructure analysis
• remotely controlled - transmitter (with joystick for control) + RC receiver ELRS 2.4GHz
• device weight - up to 200 g
• drone will not fly during rain and snow
• ability to fly the drone in moderate wind conditions
• drone will be a quadcopter - with 4 brushless motors 1104
• microdrone range - up to 500 meters
• flight time - up to 7 minutes
• it will have limited autonomy - sensors for detecting obstacles

Elements used in the project:
• 1x FS135 3 inch 1104 drone frame
• 1x GNB 11.4v 650mAh 160c battery
• 1x Flight controller set + ESC SpeedyBee F405 Mini Stack
• 4x Darwin 1104 brushless motors 4300KV
• 4x Gemfan 3016 3 inch Propellers
• 1x BetaFPV LiteRadio 3 Pro ELRS Controller (Transmitter)
• 1x BETAFPV SuperD ELRS 2.4GHz Receiver
• 1x RunCam Thumb Pro Camera
• 1x ISDT Q6 Nano Battery Charger
• 1x 5.5*2.1 female DC to XT60 female connector adapter
• 1x XT60 female to XT30 male connector adapter
• 1x XT30 male connector adapter for wires
• 2x Super Magic Tape Tie (Battery Strap)

What did I do in the project?
• Together with a friend, we designed the appearance of our micro drone.
• I was partly responsible for choosing the components for the drone.
• Together with a friend, we built the micro drone.
• I soldered the motor wires and other power wires to the ESC motor speed controller.
• I changed the rotation directions of some motors, according to the recommendations in the BLHeliSuite program.
• I tested the motors in the Betaflight Configurator program.
• Together we put the propellers on the motors according to the recommendations (3016, 3016R).
• I soldered the camera and receiver wires to the FC flight controller.
• I updated the transmitter version in the ExpressLRS Configurator program.
• I programmed the receiver and the transmitter switch functions (ARM mode, Angle mode, Horizon mode) accordingly.
• I connected the transmitter to the receiver using ELRS communication.
• Together we performed the first (successful) tests of the microdrone in terms of flying using the flight stabilization mode (Angle mode) and without this mode.
• I added additional functions to the transmitter, such as counting down the time remaining until the drone lands.

At the moment, the microdrone is flying above the ground without any problems, but it still requires a few improvements. It can be controlled using a transmitter. The camera works properly. It saves recordings on a microSD card, which can be viewed on a computer after connecting to a computer.
