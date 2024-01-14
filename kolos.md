### Symulacja komputerowa
Zastosowanie modelu matematycznego, z odpowiednimi wartościami parametrów
występujących w modelu, do analizy przebiegu zjawiska lub
procesu, czy też zachowania się obiektu, w warunkach
naśladujących rzeczywistość.

**Rodzaje symulacji komputerowych:**
- symulacje numeryczne - wynik otrzymujemy w postaci
wartości liczbowych lub konkretnych funkcji
- symulacje symboliczne - wynik sprowadzamy do
najprostszej postaci, ale pozostawiamy go w postaci funkcji z
symbolicznymi parametrami.
Symulacja symboliczna staje się numeryczną po podstawieniu
za parametry wartości liczbowych.

### Etapy tworzenia modelu matematycznego

1. Wprowadzamy zmienne przestrzenne i zmienną czasową,
określamy geometrią modelu.
2. Wprowadzamy jednostki (dobrze jest wykonać obliczenia na
wielkościach bezwymiarowych, a same jednostki wprowadzić
później).
3. Wprowadzamy założenia - na początek jak najprostsze.
4. Formułujemy prawo (fizyczne, techniczne, biologiczne,
ekonomiczne, empiryczne) opisujące rozważane zagadnienie.
5. Tworzymy matematyczny opis zagadnienia, na początku jak
najprostszy, nawet jeśli może prowadzić do niezadowalających
wyników.
6. Rozwiązujemy skonstruowane zagadnienie - najlepiej
”ręcznie”, ewentualnie wspomagając się komputerem. Jeśli to
możliwe, stosujemy różne metody rozwiązywania i
porównujemy wyniki.
7. Weryfikujemy model - sprawdzamy, czy wyniki są
prawdopodobne, czy rozważane zjawisko może się zachowywać
w zasymulowany sposób.

### Wyprowadzenie modelu opisującego ruch spadającego ciała 

**Proste**:

$$
\begin{cases}
y(0) = 0 \newline

y'(0) = V_0\newline

y''(t) = g
\end{cases}
$$

$$y'(t) = \int y''(t) \, dt = \int g \, dt = gt +C_1$$

$$y'(t) = gt+C_1$$
$$V_0 = gt+C_1$$
$$V_0=C_1$$
$$y'(t)=gt+V_0$$

$$y(t) = \int y'(t) \, dt = \int gt+V_0 \, dt = \frac{gt^2}{2}+V_0t+C_2$$

y(t) to odległość jaką pokonamy w czasie. Aby wiliczyć kiedy dotkniemy ziemi:

$$h = \frac{gt^2}{2}+V_0t+C_2$$

$$0 = \frac{gt^2}{2}+V_0t+C_2-h$$

$$\Delta = V_0^2+4\frac{g}{2}h$$

$$T_1 = \frac{-V_0-\sqrt{v_0^2+2gh}}{2}$$

$$T_2 = \frac{-V_0+\sqrt{v_0^2+2gh}}{2}$$

Odpowiedzą jest T_2  , czas jest nieujemny

### Modele:
**Deterministyczny:** (wszystkie dane z góry ustalone):
$$ y = f(x, t).$$ 
**Model stochastyczny:** (pojawia się element losowy):
$$y = f(x, t) + ξ(t),$$
**Model ciągły:**
$$f(x)=2x+3$$
**Model dyskretny:**
$$ $$

**Przejście ciągłe <-> dyskretne**
1. Ciągły, jednorodny obiekt dzielimy na ”kawałki”.
2. Do każdego ”kawałka” stosujemy prawo opisujące badane
zjawisko i formułujemy wzór obowiązujące w ”kawałku”.
1. Sumujemy otrzymane wzory po wszystkich ”kawałkach”.
2. Przechodzimy z sumą do granicy.

### Stabilność modelu:
Definicja stabilności modelu matematycznego odnosi się do jego zachowania w odpowiedzi na niewielkie zmiany warunków początkowych, parametrów lub warunków zewnętrznych. Model uznaje się za stabilny, jeśli małe zmiany tych czynników prowadzą jedynie do małych zmian w wynikach modelu. 
$$\varepsilon, \delta ~\frac{1}{\inf}$$ 
(^ oba są bardzo małe)
$$\forall v_1,v_2 \in \R |v_1 - v_2|<\delta \implies |f(v_1,a,b) - f(v_2,a,b)|<\varepsilon$$ 


