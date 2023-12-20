# Wprowadzenie do modelowania komputerowego i symulacji

Dokumentacja do Zadania laboratoryjnego 5

Tytuł: Kometa

Autor: Paweł Habrzyk

Obszar studiów: Informatyka (sem. II)

## Cel projektu:

Celem projektu jest narysowanie trajektorii komety, która jest przyciągana przez siłę grawitacyjną słońca lub innego dużego obiektu posiadającego znaczącą siłę grawitacyjną.

## Opis:

Korzystamy z pierwszego prawa Keplera dotyczącego ruchu planetarnego. Obiekty, które mają niewielką masę w porównaniu do obiektów, które orbitują wokół są prowadzone przez eliptyczne ścieżki. Ponieważ, w porównaniu do słońca, komety to małe obiekty w przestrzeni, ich ruch jest niezależny od gwiazdy. Przyciąganie między tymi dwoma obiektami powoduje, że komety mają lekko paraboliczne lub hiperboliczne trajektorie. Ukończony program pokazuje trajektorię obiektu, weźmy pod uwagę kometę, na orbicie o ekscentryczności. Ekscentryczność orbity powoduje odchylenie trajektorii komet krążących wokół planety lub gwiazdy. W zależności od _e_c otrzymujemy różne wyniki:

Dla _e_c = 0 mamy orbitę kołową,

Dla 0 < _e_c < 1 mamy orbitę eliptyczną,

Dla _e_c = 1 mamy orbitę paraboliczną,

Dla _e_c > 0 mamy orbitę hiperboliczną,

Prędkość komety jest opisana przez następujące równanie:

![image](https://i.ibb.co/df2Lq5L/Zrzut-ekranu-2023-12-20-o-19-49-53.png)  
Gdzie _e_c to ekscentryczność orbity. Współrzędne _a_ i _y_ komety definiujemy przy użyciu następujących wzorów:

Dla współrzędnej x:

![image](https://i.ibb.co/gWBLrhp/Zrzut-ekranu-2023-12-20-o-19-50-04.png)

Dla współrzędnej y:

![image](https://i.ibb.co/sg7Sz8p/Zrzut-ekranu-2023-12-20-o-19-50-09.png)

## WEJŚCIE:

comet[0.9] <- zmieniamy tylko ekscentryczność bazy, na której zmienia się trajektoria

## WYJŚCIE:

 ![image](https://i.ibb.co/wYMmw6j/Zrzut-ekranu-2023-12-20-o-19-50-38.png)  ![image](https://i.ibb.co/x6MsYYK/Zrzut-ekranu-2023-12-20-o-19-51-03.png) ![image](https://i.ibb.co/VBc350S/Zrzut-ekranu-2023-12-20-o-19-51-17.png) ![image](https://i.ibb.co/51mpxV2/Zrzut-ekranu-2023-12-20-o-19-51-28.png) 


