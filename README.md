# Wytyczne dotyczące realizacji i redakcji pracy dyplomowej

**Status dokumentu:** dokument ma charakter uzupełniający i zawiera dobre praktyki, z wyjątkiem sekcji dotyczącej wykorzystania AI, która ma charakter odrębnych wytycznych.
Dokument nie zastępuje oficjalnych wytycznych wydziałowych ani uczelnianych dostępnych na [stronie wydziału ETI](https://eti.pg.edu.pl/studenci/dyplomy). W razie rozbieżności obowiązują wytyczne wydziałowe oraz regulamin uczelni.

---

## Spis treści

1. [Najważniejsze zasady w skrócie](#1-najważniejsze-zasady-w-skrócie)
2. [Organizacja pracy i komunikacja z promotorem](#2-organizacja-pracy-i-komunikacja-z-promotorem)
3. [Struktura pracy](#3-struktura-pracy)
4. [Praktyczne wskazówki inżynierskie](#4-praktyczne-wskazówki-inżynierskie)
5. [Bibliografia i cytowanie](#5-bibliografia-i-cytowanie)
6. [Kod źródłowy, załączniki i dokumentacja projektowa](#6-kod-źródłowy-załączniki-i-dokumentacja-projektowa)
7. [Zasady edytorskie](#7-zasady-edytorskie)
8. [Prawo autorskie i uczciwość akademicka](#8-prawo-autorskie-i-uczciwość-akademicka)
9. [Generatywna sztuczna inteligencja (GenAI)](#9-generatywna-sztuczna-inteligencja-genai)
10. [Zbiór uwag językowych](#10-zbiór-uwag-językowych)

---

## 1. Najważniejsze zasady w skrócie

| Obszar | Wymóg |
|---|---|
| **Samodzielność** | Praca jest wykonywana samodzielnie, w zakresie celu i zadań uzgodnionych z promotorem. Student ponosi odpowiedzialność za poprawność merytoryczną pracy, niezależnie od wykorzystanych narzędzi. |
| **Objętość** | 40–60 stron, bez dodatków. W przypadku pracy realizowanej przez dwóch autorów objętość może być większa. |
| **Streszczenie i Abstract** | Każde ze streszczeń powinno mieć co najmniej 300 słów i zawierać słowa kluczowe (*keywords*). |
| **Bibliografia** | Wskazane jest co najmniej 15 pozycji, w tym co najmniej 5 obcojęzycznych i co najmniej 10 naukowych. Zalecane jest stosowanie normy PN-ISO 690:2012. |
| **Kod** | W pracy nie zamieszcza się listingów kodu ani szczegółowych odwołań do jego treści, z wyjątkiem dodatków. Kod należy dołączyć jako osobne archiwum `.zip` w systemie Moja PG. |
| **Wkład własny** | Wkład własny studenta powinien być wyraźnie oddzielony od wykorzystanych bibliotek, gotowych modułów oraz elementów pochodzących z wcześniejszych prac. |
| **Ocena** | Realizacja pracy podlega ocenie na kolejnych etapach, w szczególności w ramach ustalonych kamieni milowych, np. pod koniec pierwszego semestru. |
| **AI** | Możliwość korzystania z narzędzi AI należy uzgodnić z promotorem. Wykorzystanie AI podlega udokumentowaniu w odpowiednim załączniku. |
| **Szablon** | Praca powinna być przygotowana z wykorzystaniem właściwego szablonu wydziałowego, w wersji LaTeX lub Word. |

---

## 2. Organizacja pracy i komunikacja z promotorem

### 2.1 Oczekiwania po 6. lub 2. semestrze

Po zakończeniu 6. lub 2. semestru student powinien dysponować wstępnym szkicem pracy, potencjalnie rozdziałem przeglądowym i udokumentowanym stanem zaawansowania projektu. 
Oczekuje się:

- spisu treści,
- wstępu,
- rozdziału przeglądowego,
- krótkiej informacji o postępach prac (zwięzły opis aktualnego etapu: co zostało wykonane, a co pozostaje do wykonania).

### 2.2 Kamienie milowe i ocena

- Kamienie milowe podlegają ocenie i są ustalane przez promotora.
- Ocena z przedmiotu „praca dyplomowa" wynika ze stanu pracy na koniec pierwszego semestru.
- Kamień milowy powinien być sprawdzalny, np.: „Działający prototyp z testami jednostkowymi i raportem z pomiarów bazowych" zamiast „Praca nad projektem".

### 2.3 Planowanie czasu

Realizacja pracy wymaga odpowiedniego rozplanowania działań w czasie. Odkładanie zasadniczej części zadań na końcowy etap utrudnia przygotowanie spójnego opracowania i zwiększa ryzyko opóźnień.

- Harmonogram powinien uwzględniać **rezerwę czasową** na modyfikacje, poprawki i usprawnienia projektu. Założenia przyjęte na początku realizacji często wymagają późniejszej weryfikacji lub zmiany.

- Należy możliwie wcześnie rozpocząć:
    - budowę lub uruchamianie stanowiska bądź urządzenia,
    - implementację i testowanie oprogramowania,
    - gromadzenie i analizę źródeł,
    - pisanie kolejnych fragmentów pracy.

- W przypadku prac inżynierskich warto wykorzystać okres wakacyjny na wykonanie części zadań, co pozwoli odciążyć późniejsze etapy realizacji pracy.

- **Ostatni miesiąc przed złożeniem pracy powinien być przeznaczony przede wszystkim na pisanie, składanie i dopracowanie dokumentacji.** 
Na tym etapie nie należy planować zasadniczych prac projektowych ani implementacyjnych.

- Proces korekty pracy może zająć **do dwóch tygodni**, zwłaszcza w przypadku kilku etapów poprawek. 
W okresach zwiększonego obciążenia promotora czas oczekiwania na sprawdzenie tekstu może się wydłużyć, dlatego należy przewidzieć odpowiedni zapas czasu.

Terminy szczegółowe, w tym dotyczące przekazania rozdziałów implementacyjnego i testowego oraz złożenia kompletnej wersji pracy, ustala się indywidualnie z promotorem, z uwzględnieniem aktualnego [kalendarza roku akademickiego WETI](https://eti.pg.edu.pl/studenci/dziekanat/kalendarz-roku-akademickiego).

### 2.4 Komunikacja z promotorem

Nie ma obowiązku regularnego składania szczegółowych raportów.
Student samodzielnie planuje i realizuje kolejne etapy pracy. **Zalecany jest jednak stały rytm spotkań z promotorem (np. co 2 tygodnie).** 
Istotne ustalenia warto zapisywać w repozytorium projektu lub w systemie Moja PG.

Kontakt z promotorem jest szczególnie wskazany, gdy:

- pojawiają się istotne trudności techniczne lub organizacyjne,

- konieczne jest skonsultowanie kierunku dalszych działań,

- przygotowano fragment pracy do weryfikacji,

- potrzebna jest decyzja dotycząca doboru metod, komponentów lub zakresu opracowania.

**Zasady przekazywania tekstu:**

- Rozdziały należy przekazywać promotorowi **kolejno**, a nie dopiero po przygotowaniu całej pracy. 
**Datę przekazania należy umieścić w nazwie pliku**, co ułatwia identyfikację kolejnych wersji.

- Pracę należy przekazywać do weryfikacji dopiero po jej uważnym przeczytaniu i usunięciu podstawowych błędów językowych, stylistycznych i formatowania. 
Weryfikacja przez promotora nie zastępuje samodzielnej korekty tekstu przez autora. 
Przekazanie nieprzygotowanego tekstu nie przyspiesza procesu weryfikacji i może go wydłużyć.

- Zmianę tematu lub opiekuna należy zgłosić możliwie wcześnie, **przed rozpoczęciem zasadniczych prac**, a nie dopiero pod koniec semestru.

## 3. Struktura pracy

### 3.1 Układ pracy

| Część | Element | Uwagi |
|---|---|---|
| **Front matter** | Strona tytułowa | Wzór pobrany z systemu Moja PG, zgodny z rodzajem pracy (np. „Projekt dyplomowy inżynierski”). Strona tytułowa nie zawiera widocznego numeru strony. |
| | Streszczenie | Min. 300 słów + słowa kluczowe. |
| | Abstract | Min. 300 słów + *keywords*. |
| | Spis treści | Wszystkie rozdziały, podrozdziały i podpunkty wraz z numerami stron. W przypadku pracy zespołowej należy wskazać autora każdej części. |
| | Wykaz oznaczeń | Symbole stosowane w pracy wraz z jednostkami i krótkim opisem. |
| | Wykaz skrótów | Skróty użyte w tekście wraz z ich rozwinięciem. |
| **Body matter** | Wstęp i cel pracy | 1–2,5 strony. |
| | Rozdziały merytoryczne | Zgodnie z zasadami opisanymi w sekcji 3.3. |
| | Zakończenie (podsumowanie) | Efekty realizacji pracy, odniesienie do założonego celu, najważniejsze wnioski oraz propozycje dalszych prac. |
| **Back matter** | Bibliografia | Zgodnie z zasadami opisanymi w sekcji 5. |
| | Załączniki / dodatki | Zgodnie z zasadami opisanymi w sekcji 6. |

**Numeracja stron jest ciągła w całej pracy.
Wyjątek stanowi strona tytułowa, na której numer strony nie jest wyświetlany.**

### 3.2 Wstęp i cel pracy (1–2,5 strony)

Rozdział pierwszy występuje we wszystkich pracach i powinien zachowywać przedstawioną poniżej strukturę.

Zaleca się przygotowanie go **po opracowaniu zasadniczej części pracy**, gdy znany jest już ostateczny zakres wykonanych prac i uzyskanych wyników.

**Wprowadzenie (tło)**

- krótkie wprowadzenie do tematu, obejmujące w zależności od specyfiki pracy m.in. trendy w danej dziedzinie, zarys historyczny, definicje podstawowych pojęć lub tło społeczne, użytkowe albo badawcze,

- jeżeli w celu pracy pojawiają się mniej oczywiste terminy techniczne, należy je krótko objaśnić we wprowadzeniu,

- w tej części nie należy zamieszczać ilustracji, zdjęć ani wykresów.

**Cel pracy**

- jasne i zwięzłe sformułowanie celu, w miarę możliwości **weryfikowalne lub mierzalne**, wraz z ewentualną **tezą** i **założeniami**,

- niedoprecyzowane ogólniki należy zastępować sformułowaniami pozwalającymi jednoznacznie ocenić stopień realizacji celu (patrz tabela w sekcji 4.1),

- w uzasadnionych przypadkach dopuszczalna jest praca, w której założony cel nie został w pełni osiągnięty. 
W takim przypadku należy szczegółowo wyjaśnić przyczyny nieosiągnięcia celu oraz przedstawić uzyskane wyniki.

**Założenia projektowe**

- założenia mogą obejmować m.in. wymagania dotyczące wykorzystania konkretnego urządzenia (np. robota z wyposażenia laboratorium), minikomputera lub określonego algorytmu (np. A* lub metody sztucznych potencjałów),

- jeżeli wybór sprzętu, komponentu lub metody wynika z decyzji podjętych dopiero na późniejszym etapie realizacji projektu, nie należy przedstawiać go jako założenia pracy.

**Podział pracy** *(tylko w pracach dwuosobowych)*

- opis podziału zadań pomiędzy autorów; zalecana jest forma opisowa, dopuszczalna jest również lista.

**Opis poszczególnych rozdziałów**

- krótki przegląd struktury pracy, wskazujący zawartość kolejnych rozdziałów, np. „W rozdziale drugim przedstawiono…” lub „Uzyskane wyniki opisano w rozdziale szóstym”.

### 3.3 Rozdziały merytoryczne

Liczba stron poszczególnych rozdziałów **nie jest odgórnie narzucona**. 
Objętość każdego rozdziału powinna wynikać z zakresu i charakteru pracy. 
W razie wątpliwości dotyczących struktury lub objętości należy skonsultować się z promotorem lub osobą prowadzącą seminarium dyplomowe inżynierskie.

**Rozdziały obowiązkowe:**

1. **Rozdział teoretyczny**

    - krótkie wprowadzenie do zagadnień omawianych w rozdziale,

    - przedstawienie modeli, algorytmów, wzorów i założeń teoretycznych wykorzystywanych w pracy; wszystkie symbole występujące we wzorach należy zdefiniować, a źródło wzoru podać lub, jeśli jest to istotne dla pracy, przedstawić jego wyprowadzenie,

    - szczegółowe omówienie zagadnień teoretycznych wynikających z zakresu pracy i przeprowadzonego przeglądu literatury,

    - podsumowanie najważniejszych zagadnień i założeń przyjętych w dalszej części pracy.

2. **Rozdział przeglądowy**

    - krótkie wprowadzenie,

    - przegląd istniejących rozwiązań przemysłowych i naukowych, z podziałem na istotne podproblemy; w tym rozdziale znajduje się zasadnicza część cytowań,

    - przegląd istniejących zbiorów danych, jeżeli są istotne dla tematyki pracy,

    - porównanie rozwiązań według jasno określonych kryteriów oraz wskazanie istniejącej luki, ograniczenia lub potrzeby uzasadniającej realizację pracy,

    - podsumowanie przeglądu i porównania, z którego wynika sposób realizacji pracy lub przyjęte założenia projektowe.

3. **Rozdział opisujący rozwiązanie**

    - krótkie wprowadzenie,

    - wymagania stawiane projektowanemu rozwiązaniu,

    - architektura rozwiązania,

    - najważniejsze decyzje projektowe wraz z ich uzasadnieniem,

    - wybór technologii, komponentów i narzędzi,

    - szczegółowe przedstawienie rozwiązania algorytmicznego lub sprzętowego, o ile nie zostało ono opisane w odrębnym rozdziale,

    - podsumowanie przyjętego rozwiązania i jego najważniejszych cech.

4. **Rozdział z testami i wynikami**

    - plan testów i metodyka pomiarów,

    - prezentacja wyników **wraz z oceną niepewności pomiarów**, jeżeli jest ona uzasadniona charakterem wykonywanych pomiarów,

    - porównanie wyników z przyjętymi kryteriami sukcesu oraz, w miarę możliwości, z rozwiązaniami przedstawionymi w rozdziale przeglądowym,

    - omówienie ograniczeń rozwiązania oraz istotnych różnic pomiędzy symulacją a działaniem systemu rzeczywistego, jeżeli występują,

    - podsumowanie wyników i ocena stopnia realizacji założonych celów.

**Rozdziały zależne od tematu pracy** (dobierane odpowiednio do charakteru projektu):

- konstrukcja mechaniczna,

- projekt układu elektronicznego,

- opracowane lub wykorzystane algorytmy, w tym model matematyczny obiektu,

- implementacja, w tym szczegóły implementacyjne oraz aspekty związane z mocą obliczeniową i zasobami systemu.

Wkład własny autora powinien być wyraźnie oddzielony od wykorzystanych gotowych bibliotek, modułów, komponentów oraz wcześniejszych prac (patrz sekcja 6.1).

> **Przykładowy układ** pracy o charakterze sprzętowym (ostateczna struktura dokumentu):
> 
> 1. Wstęp i cel pracy
> 2. Rozdział teoretyczny
> 3. Przegląd literatury i istniejących rozwiązań
> 4. Konstrukcja mechaniczna
> 5. Układ elektroniczny
> 6. Algorytmy sterowania
> 7. Oprogramowanie i implementacja
> 8. Testy i wyniki
> 9. Podsumowanie

**Zasady ogólne dla rozdziałów:**

- Każdy rozdział powinien rozpoczynać się krótkim wprowadzeniem i kończyć podsumowaniem lub płynnym przejściem do kolejnego zagadnienia.

- Struktura pracy nie powinna przypominać kryminału: kluczowe informacje nie powinny pojawiać się dopiero pod koniec pracy. 
Należy ograniczać odwołania do treści przedstawianych dopiero w kolejnych rozdziałach.
Dopuszczalne i wskazane są odwołania do elementów opisanych wcześniej.

- Wszystkie odwołania do wzorów, rysunków, tabel i źródeł powinny być przygotowane w formie hiperłączy.

- Podrozdział nie powinien być krótszy niż jedna strona. 
Nie należy tworzyć osobnego podrozdziału dla pojedynczego krótkiego akapitu.

- Nagłówek nie powinien pozostawać samotnie na dole strony. 
Nie należy również umieszczać rysunku bezpośrednio po tytule rozdziału lub podrozdziału; pomiędzy nagłówkiem a rysunkiem powinien znajdować się tekst wprowadzający.

**Zakończenie (podsumowanie)** powinno zawierać:

- najważniejsze efekty i osiągnięcia,

- odniesienie do celu i założeń pracy, w tym do przyjętych kryteriów sukcesu,

- najważniejsze wnioski,

- wskazanie elementów niezrealizowanych wraz z przyczynami,

- możliwe kierunki dalszego rozwoju lub kontynuacji prac.

### 3.4 Streszczenie i Abstract

- Każde streszczenie powinno mieć co najmniej 300 słów i być przygotowane w języku polskim oraz angielskim. 
Do obu wersji należy dołączyć odpowiednio **słowa kluczowe** i *keywords*.

- Streszczenie powinno zawierać: problem lub zagadnienie będące przedmiotem pracy, cel i zakres pracy, zastosowane metody, najważniejsze wyniki oraz wnioski.

- **Nie należy opisywać** zawartości poszczególnych rozdziałów, np. „W rozdziale drugim opisano…”.

- **Nie należy zamieszczać** nadmiernej liczby szczegółów technicznych (np. typu mikrokomputera, modelu lidaru czy rodzaju baterii), chyba że mają one istotne znaczenie dla charakteru lub wyników pracy.

- Celem streszczenia jest umożliwienie czytelnikowi szybkiej oceny tematyki, zakresu, sposobu realizacji oraz najważniejszych wyników pracy bez konieczności zapoznawania się z jej pełną treścią.

### 3.5 Spis treści, wykaz oznaczeń i skrótów

- Spis treści powinien być przejrzysty i czytelny. 
Numery stron należy wyrównać do prawej, a tytuły poszczególnych elementów odpowiednio zagnieździć. 
Spis treści powinien być generowany automatycznie. 
Należy unikać zbyt długich tytułów oraz nadmiernej fragmentaryzacji struktury pracy.

- Wykaz oznaczeń powinien zawierać symbole stosowane w pracy wraz z jednostkami i jednoznacznymi opisami. 
Symbol używany w wielu miejscach pracy należy umieścić w wykazie. 
Symbol występujący wyłącznie lokalnie, np. w jednym równaniu, nie musi być w nim uwzględniany.

- W przypadku dużej liczby oznaczeń dopuszczalne, a przy listach zajmujących więcej niż jedną stronę zalecane, jest wydzielenie osobnych wykazów symboli matematycznych i skrótów.

- Każdy skrót należy rozwinąć przy jego pierwszym użyciu w tekście. 
Wyjątek mogą stanowić skróty powszechnie znane i jednoznaczne w danym kontekście.

## 4. Praktyczne wskazówki inżynierskie

### 4.1 Jak formułować cel i kryteria sukcesu

| Element | Słaba formuła | Sprawdzalna formuła |
|---|---|---|
| Cel | „Zbadanie możliwości wykorzystania AI w robotyce” | „Zaprojektowanie i zaimplementowanie klasyfikatora X działającego na platformie Y z opóźnieniem poniżej 50 ms” |
| Kryterium sukcesu | „Dobra dokładność” | „Dokładność co najmniej 90 % na zbiorze testowym Z, wyznaczona według opisanej procedury” |
| Kamień milowy | „Praca nad projektem” | „Działający prototyp z testami jednostkowymi i raportem z pomiarów bazowych” |

### 4.2 Trzy zasady podnoszące jakość pracy technicznej

1. **Model, symulacja i rzeczywistość powinny być wyraźnie rozdzielone.** 
Wynik symulacji nie przenosi się bezpośrednio na działanie sprzętu. 
W systemie rzeczywistym występują m.in. szum, opóźnienia, błędy i konieczność kalibracji, tolerancje elementów oraz możliwość wystąpienia awarii czujników. 
W pracy obejmującej modelowanie, symulację i system rzeczywisty należy opisać wszystkie te poziomy oraz wskazać istotne różnice między nimi.

2. **Należy podawać warunki i sposób wykonania pomiarów oraz, gdy jest to uzasadnione, ich niepewność.** 
Wynik powinien być przedstawiony w sposób umożliwiający jego interpretację i porównanie z innymi wynikami. 
Należy podać m.in. liczbę powtórzeń, konfigurację stanowiska oraz istotne warunki pomiaru. 
Liczba cyfr znaczących powinna odpowiadać dokładności pomiaru, aby nie sugerować większej precyzji, niż rzeczywiście uzyskano.

3. **Rozwiązanie programowe powinno być testowane i wersjonowane.** 
Testy automatyczne należy stosować tam, gdzie jest to uzasadnione i możliwe. 
W repozytorium powinny znajdować się informacje o istotnych zmianach wersji oraz sposób uruchomienia projektu. 
Należy również opisać wykorzystane narzędzia, dane oraz konfigurację sprzętową niezbędną do odtworzenia działania rozwiązania.

### 4.3 Unikanie wypełniaczy

Nie należy sztucznie zwiększać objętości pracy treściami oczywistymi, ogólnie dostępnymi lub przejętymi bezrefleksyjnie z internetu. 
Każdy fragment pracy powinien mieć uzasadnienie merytoryczne i służyć realizacji jej celu.

- **Przykład (protokół I2C):** 
> jeżeli celem pracy jest własna, niskopoziomowa obsługa protokołu, szczegółowy opis ramek, adresowania i potwierdzeń jest uzasadniony. 
> Jeżeli protokół jest wykorzystywany za pośrednictwem gotowych bibliotek (np. Raspberry Pi ↔ Arduino), wystarczy krótkie przedstawienie sposobu jego wykorzystania, rodzaju przesyłanych danych oraz zastosowanej biblioteki.

- **Przykład (ilustracje):** 
> w pracy dotyczącej budowy urządzenia nie ma potrzeby umieszczania osobnych zdjęć każdego komponentu. 
> Zwykle wystarczą schemat elektryczny oraz zdjęcia gotowego urządzenia. 
> W przypadku płytki drukowanej warto zamieścić projekt PCB, bez dokumentowania poszczególnych etapów jej montażu, chyba że są one istotne dla realizacji lub oceny pracy.

Materiały, do których nie ma szczegółowych odwołań w tekście (np. schematy elektryczne, projekty PCB), należy przenieść do dodatków i wskazać w treści pracy ich lokalizację.

## 5. Bibliografia i cytowanie

### 5.1 Wymogi ilościowe i formalne

- **Zalecane jest wykorzystanie co najmniej 15 źródeł**, w tym **co najmniej 5 obcojęzycznych** i **co najmniej 10 naukowych**. 
Podane wartości mają charakter orientacyjny i powinny być dostosowane do tematyki oraz zakresu pracy. 
W razie wątpliwości dotyczących zakresu bibliografii należy skonsultować się z promotorem.

- Opisy bibliograficzne należy przygotować zgodnie z normą **PN-ISO 690:2012**, zachowując jednolity styl w całej pracy.

- W bibliografii należy umieszczać wyłącznie źródła, z których faktycznie korzystano i do których odwołano się w tekście. 
**Nie należy dodawać źródeł wyłącznie w celu zwiększenia liczby pozycji.** 
Każde źródło powinno zostać zapoznane przed jego wykorzystaniem i odpowiednio zweryfikowane.

- Każda pozycja wymieniona w bibliografii powinna mieć co najmniej jedno odwołanie w tekście. 
Dane bibliograficzne należy w miarę możliwości zweryfikować w oryginalnym źródle, w szczególności autorów, tytuł, rok publikacji, dane czasopisma lub wydawnictwa, numery stron oraz DOI.

- W przypadku publikacji mającej więcej niż 3 autorów dopuszczalne jest podanie pierwszego autora z dopiskiem *et al.*, zgodnie z przyjętym stylem bibliograficznym.

### 5.2 Rodzaje źródeł

| Rodzaj | Zasada |
|---|---|
| **Literatura naukowa** | Książki naukowe, artykuły naukowe, rozdziały prac zbiorowych, prace magisterskie, inżynierskie i doktorskie oraz inne recenzowane publikacje. Powinna stanowić trzon bibliografii. |
| **Dokumentacje, noty katalogowe, normy, strony WWW** | Dopuszczalne jako uzasadnione źródła techniczne, **ale nie zastępują literatury naukowej**. Strony WWW należy opisywać z podaniem autora (jeśli jest dostępny), tytułu lub krótkiego opisu, adresu URL oraz **daty dostępu**. Przed złożeniem pracy należy zweryfikować aktywność linków i w razie potrzeby zaktualizować datę dostępu. |
| **Wikipedia** | **Niewskazana jako źródło bibliograficzne.** Może być wykorzystywana pomocniczo i krytycznie, w szczególności do zapoznania się z podstawowymi pojęciami lub odnalezienia źródeł pierwotnych. W pracy należy cytować źródła pierwotne wskazane w odnośnikach, a nie sam artykuł Wikipedii. |

Źródła naukowe można wyszukiwać m.in. w [Google Scholar](https://scholar.google.com/) (dane bibliograficzne należy zawsze zweryfikować w oryginalnej publikacji), [IEEE Xplore](https://ieeexplore.ieee.org/) oraz [ScienceDirect](https://www.sciencedirect.com/). 
Dostępność pełnych tekstów z sieci uczelni można sprawdzić za pośrednictwem Biblioteki PG.

### 5.3 Przykłady opisów (ilustracja elementów wymaganych)

Poniższe przykłady mają charakter ilustracyjny i pokazują podstawowe elementy, które powinny znaleźć się w opisie danego rodzaju źródła. 
Ostateczny format wpisów wynika ze stylu bibliograficznego zastosowanego w szablonie oraz normy PN-ISO 690:2012.

**Książka** — autor (nazwisko i inicjały), tytuł, wydawca, rok wydania.

> M. Niedźwiecki, *Identification of Time-Varying Processes*, Wiley & Sons, 2000.

**Artykuł naukowy** — autorzy, tytuł artykułu, tytuł czasopisma lub materiałów konferencyjnych, tom i numer, strony lub numer artykułu, rok wydania, a w przypadku publikacji konferencyjnych również informacje o konferencji, DOI.

> S. Bennett, „Development of the PID controller”, *IEEE Control Systems Magazine*, nr 13, ss. 58–62, 1993, doi: [10.1109/37.248006](https://doi.org/10.1109/37.248006).

**Rozdział pracy zbiorowej** — autor rozdziału, tytuł rozdziału, tytuł pracy zbiorowej, redaktorzy, wydawca, rok wydania.

> A. J. Krener, *The Important State Coordinates of a Nonlinear System*, w: *Advances in Control Theory and Applications*, red. C. Bonivento et al., Springer, 2007.

**Rozprawa doktorska** — autor, tytuł pracy, informacja o charakterze pracy, uczelnia, rok.

> T. H. Eggen, *Underwater Acoustic Communication Over Doppler Spread Channels*, rozprawa doktorska, Massachusetts Institute of Technology, 1997.

**Źródło internetowe** — autor (jeśli jest dostępny), tytuł lub opis, adres URL, data dostępu.

> Przykładowy opis źródła internetowego: autor, *tytuł strony lub dokumentu*, adres URL, data dostępu.

Jeżeli komentarze lub przykłady zawarte w szablonie pracy określają inny sposób formatowania bibliografii, należy stosować format zgodny z szablonem. W przypadku rozbieżności z ogólnymi zasadami przedstawionymi w niniejszym dokumencie **obowiązuje format określony w szablonie**.


### 5.4 Cytowanie w tekście

- Odnośnik bibliograficzny należy umieszczać **przed kropką** kończącą zdanie. 
Numer odnośnika odpowiada pozycji w wykazie bibliografii.

- W LaTeX-u przed `\cite` należy wstawiać **twardą spację** (`~`):

> Algorytm został opisany w pracy~\cite{kowalski2002}.
> 
> Porównywano kilka podejść~\cite{kowalski2002,nowak2002}.

- W przypadku **cytatu dosłownego** należy zastosować cudzysłów oraz podać numer strony, z której pochodzi cytowany fragment.

- Przy odwołaniu do kilku źródeł jednocześnie należy stosować zapis zbiorczy, np. `\cite{kowalski2002,nowak2002}`, lub osobne odnośniki, zgodnie ze stylem bibliograficznym przyjętym w szablonie.

- Odwołanie bibliograficzne powinno jednoznacznie wskazywać źródło informacji. 
Należy unikać umieszczania jednego odnośnika na końcu akapitu, jeżeli nie jest jasne, które stwierdzenia w akapicie są oparte na danym źródle.


## 6. Kod źródłowy, załączniki i dokumentacja projektowa

### 6.1 Wkład własny a gotowe rozwiązania

- Wkład własny autora musi być **wyraźnie oddzielony** od wykorzystanych bibliotek, gotowych modułów, komponentów oraz rozwiązań pochodzących z wcześniejszych prac.

- Nazwy użytych bibliotek należy **wyraźnie wskazać** (np. OpenCV) oraz opisać, jaką funkcjonalność dzięki nim uzyskano. Nie ma potrzeby podawania nazw poszczególnych funkcji ani klas.

- Należy **jednoznacznie wskazać, które elementy zostały zaimplementowane samodzielnie przez autora**.

- W pracy należy podać informacje o wykorzystanym języku programowania i środowisku programistycznym. 
W pracach zawierających elementy konstrukcyjne zaleca się również wskazanie wykorzystanego oprogramowania CAD.

- W przypadku pracy zespołowej należy wskazać autorów poszczególnych rozdziałów i podrozdziałów, zgodnie z faktycznym podziałem prac.

### 6.2 Brak kodu w tekście pracy

- W głównej części pracy **nie zamieszcza się listingów ani fragmentów kodu**. 
Nie należy również odwoływać się do konkretnych funkcji, klas lub zmiennych, jeżeli nie jest to konieczne do wyjaśnienia rozwiązania.

- Algorytm lub rozwiązanie należy przedstawiać za pomocą **wzorów matematycznych, grafów, schematów i rysunków** oraz, jako uzupełnienie, opisu słownego. 
Zaleca się łączenie kilku form prezentacji.

- Opis powinien przedstawiać **istotę rozwiązania, a nie sposób jego implementacji**. 
Warstwę koncepcyjną i matematyczną należy opisywać za pomocą odpowiedniej terminologii i symboliki, bez uzależniania opisu od konkretnego języka programowania.

- Algorytmy można przedstawiać za pomocą pseudokodu z numerowanymi krokami. 
Złożoność obliczeniową należy podawać, jeżeli ma znaczenie dla analizowanego rozwiązania.

- **Wyjątek:** w pracach, w których analiza kodu lub konkretnej implementacji stanowi istotę tematu, dopuszczalne jest omówienie wybranych fragmentów kodu. 
Nie należy jednak zastępować wyjaśnienia algorytmu samym kodem.

### 6.3 Załączniki i dokumentacja elektroniczna

**Kod źródłowy i materiały dodatkowe** należy dołączyć do systemu **Moja PG jako jedno skompresowane archiwum `.zip`** o nazwie:

> `PDI_zalacznik_numer albumu`

Zawartość archiwum powinna obejmować:

- kod źródłowy wytworzony w ramach pracy,

- **README** zawierający co najmniej informacje potrzebne do uruchomienia i odtworzenia projektu,

- **konfigurację projektu oraz wersje użytych narzędzi i bibliotek**,

- **skrypty umożliwiające odtworzenie wyników**, jeżeli ich przygotowanie jest możliwe i uzasadnione,

- dane oraz inne materiały uzupełniające, wraz z informacją o ich źródłach i licencjach, jeżeli jest to wymagane,

- materiały **bez haseł, kluczy API, tokenów i innych danych uwierzytelniających**.

**Załączniki do pracy** (back matter, numerowane z wyjątkiem bibliografii) mogą obejmować:

- obliczenia, schematy ideowe i inne materiały uzupełniające,

- **instrukcję użytkownika** — opis sposobu uruchomienia i podstawowej obsługi sprzętu lub oprogramowania,

- **instrukcję programisty** — opis struktury projektu i rozmieszczenia najważniejszych elementów kodu; w tej części dopuszczalne są krótkie listingi z numerem i podpisem,

- **informację o wykorzystanych narzędziach AI** wraz z wymaganym opisem ich wykorzystania, zgodnie z zasadami przedstawionymi w sekcji 9.


## 7. Zasady edytorskie

Szablon LaTeX automatycznie ustawia większość wymagań formalnych, jednak część elementów należy sprawdzić ręcznie. 
Jeżeli komentarz lub ustawienie w szablonie różni się od ogólnych zasad przedstawionych poniżej, **obowiązuje szablon**.

### 7.1 Wymagania formalne

| Element                       | Wymóg                                                                                                                                                                  |
| ----------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Nazwa pliku pracy             | `PDI_numer albumu`                                                                                                                                                     |
| Nazwa archiwum z załącznikami | `PDI_zalacznik_numer albumu`                                                                                                                                           |
| Format strony                 | A4, orientacja pionowa                                                                                                                                                 |
| Czcionka                      | **Arial, 10 pkt**, zgodnie z Księgą Identyfikacji Wizualnej PG                                                                                                         |
| Interlinia                    | **1,5 wiersza**                                                                                                                                                        |
| Tekst i marginesy             | Tekst wyjustowany; **marginesy w odbiciu lustrzanym**                                                                                                                  |
| Numeracja stron               | Numeracja ciągła, umieszczona w stopce; numer nie jest wyświetlany na stronie tytułowej. Należy unikać nieuzasadnionych pustych stron.                                 |
| Akapity                       | Jednolity sposób formatowania akapitów w całej pracy; jednakowe wcięcia i odstępy zgodne z szablonem. Tekst nie może wychodzić poza obszar wyznaczony przez marginesy. |
| Tabele i rysunki              | Podpis tabeli umieszcza się **nad tabelą**, a podpis rysunku **pod rysunkiem**. Każdy rysunek i tabela powinny być przywołane w tekście.                               |
| Terminologia i skróty         | Termin należy zdefiniować przy pierwszym użyciu, jeżeli nie jest powszechnie znany. Skróty nazw metod, firm, technologii itp. należy rozwinąć przy pierwszym użyciu.   |

### 7.3 Symbole i wzory

**Symbole**

- Symbole wielkości fizycznych i matematycznych powinny być jednoznaczne i możliwie krótkie, zwykle jednoelementowe (pojedyncza litera, ewentualnie z indeksami). 
W zapisie matematycznym nie należy stosować nazw pochodzących bezpośrednio z kodu, np. `index`, `speed` czy `position`.

- Ten sam symbol powinien oznaczać tę samą wielkość w całej pracy. 
Wielkości powiązane należy rozróżniać za pomocą indeksów dolnych lub górnych, zwracając uwagę na możliwość pomylenia indeksu górnego z potęgą. 
> Przykładowo: punkt na obrazie *O*, jego współrzędne *O<sub>x</sub>*, *O<sub>y</sub>*; ten sam punkt wyrażony w różnych układach odniesienia: *O<sup>A</sup>*, *O<sup>B</sup>*.

- Symbole zmiennych zapisuje się **kursywą**, natomiast nazwy funkcji, operatory oraz stałe matematyczne, np. *e* i *π*, zapisuje się czcionką prostą lub zgodnie z konwencją matematyczną stosowaną w szablonie.

- **Sposób zapisu symboli powinien być spójny** w tekście, wzorach, na rysunkach i w tabelach. 
Należy zachować tę samą konwencję oznaczeń, czcionkę i styl zapisu; rozmiar należy dostosować do danego elementu.

**Wzory**

- Wzory powinny być wyśrodkowane, numerowane po prawej stronie w nawiasach okrągłych i przywoływane w tekście za pomocą `\eqref`, np. „zgodnie ze wzorem (3)”.

- Wzór jest częścią zdania i powinien kończyć się odpowiednim znakiem interpunkcyjnym, najczęściej kropką lub przecinkiem.

- Każdy symbol występujący we wzorze należy objaśnić, podając w razie potrzeby również jednostkę. 
Preferowane jest objaśnienie w toku zdania, np. „…, gdzie *s* oznacza drogę, a *t* — czas”.
Dopuszczalne jest również zastosowanie listy objaśnień pod wzorem. W całej pracy należy stosować jeden sposób.
Symboli, które zostały już jednoznacznie zdefiniowane wcześniej, nie należy bez potrzeby definiować ponownie.

- **Wyprowadzenia wzorów:** zakres szczegółowości należy uzgodnić z promotorem. 
- Zasadniczo wystarczają założenia początkowe, wynik końcowy oraz, w razie potrzeby, kluczowe etapy pośrednie. 
W przypadku zależności geometrycznych zaleca się zastosowanie rysunku poglądowego zamiast zamieszczania pełnego wyprowadzenia, jeżeli nie jest ono istotne dla celu pracy.

### 7.4 Rysunki i tabele

**Wygląd i treść**

- Rysunki i tabele powinny mieścić się w obrębie marginesów tekstu. 
Rysunki należy wyśrodkować.

- Każdy rysunek powinien mieć numer i podpis umieszczony pod nim. 
W przypadku dwóch rysunków przedstawionych obok siebie można zastosować jeden wspólny podpis oraz oznaczenia (a), (b).

- Każdy rysunek i każda tabela powinny być uzasadnione merytorycznie, przywołane w tekście i omówione. 
Nie należy umieszczać elementów pozbawionych wartości merytorycznej, np. przypadkowych zrzutów ekranu. **Zrzutów ekranu kodu nie należy zamieszczać w pracy.**

- Wykresy powinny mieć tytuł lub podpis, opisane osie wraz z **jednostkami**, wartości liczbowe na osiach oraz legendę, jeżeli jest potrzebna. 
Wykres powinien pozostać czytelny również po wydrukowaniu w skali szarości.

- Czcionka stosowana w podpisach i opisach rysunków oraz tabel powinna mieć rozmiar zbliżony do czcionki tekstu głównego i zapewniać czytelność po wydruku.

- Schematy elektryczne należy wykonywać z wykorzystaniem spójnej konwencji oznaczeń i symboli, np. zgodnej z IEC lub IEEE.

**Jakość graficzna**

- Schematy, wykresy i inne grafiki zawierające elementy geometryczne lub tekst powinny być przygotowane w **formacie wektorowym**, np. PDF, SVG lub EPS, jeżeli pozwala na to używane oprogramowanie.

- W przypadku grafiki rastrowej zalecana jest rozdzielczość **co najmniej 300 dpi**.
Fotografie mogą być stosowane w formacie rastrowym.

**Źródło rysunków i tabel**

- Rysunek lub tabela przejęte w całości albo opracowane na podstawie cudzego źródła powinny mieć w podpisie odpowiedni odnośnik, np. **„Źródło: [n]”** lub **„Opracowano na podstawie [n]”**. 
W przypadku materiałów będących w całości opracowaniem własnym nie ma potrzeby umieszczania informacji „opracowanie własne”.

- Wykorzystanie cudzego materiału wymaga odpowiedniej podstawy prawnej, np. licencji (w tym Creative Commons), zgody właściciela praw lub zastosowania prawa cytatu, zgodnie z zasadami opisanymi w sekcji 8. 
W razie wątpliwości bezpieczniejszym rozwiązaniem jest przygotowanie własnej ilustracji na podstawie informacji ze źródła i oznaczenie jej jako **„Opracowano na podstawie [n]”**.

**Sposób pisania o rysunkach**

- **Rysunkom nie należy przypisywać czynności wykonywanych przez ludzi lub autorów.** 
Zamiast „Rysunek 4.7 przedstawia uzyskane rezultaty” należy stosować formę „Na rysunku 4.7 przedstawiono uzyskane rezultaty”.

- Skrótu **„rys.”** należy używać tylko we wtrąceniu, np. „Odpowiedź skokowa układu zamkniętego (rys. 4.7) charakteryzuje się przeregulowaniem 10%”. 
Gdy odniesienie do ilustracji jest integralną częścią zdania, należy stosować pełną formę „rysunek”, np. „Na rysunku 4.7 przedstawiono…”.

- **Nie należy przypisywać sprawczości przedmiotom, tabelom, wykresom ani elementom interfejsu**, jeżeli prowadzi to do nienaturalnego lub nieprecyzyjnego opisu. 
Zalecane są konstrukcje: „Na wykresie przedstawiono…”, „W tabeli zestawiono…”, „Po kliknięciu przycisku wykonywane jest zdjęcie”, zamiast „wykres pokazuje…”, „przycisk wykonuje zdjęcie…”.


## 8. Prawo autorskie i uczciwość akademicka

Należy móc wykazać, że praca jest opracowaniem własnym, a każde wykorzystane cudze źródło, rysunek, dane lub fragment kodu zostały odpowiednio wskazane i wykorzystane zgodnie z obowiązującymi zasadami. *Niniejszy rozdział ma charakter informacyjny i nie stanowi porady prawnej. W przypadku wątpliwości należy skonsultować się z promotorem lub właściwą jednostką uczelni.*

### 8.1 Oświadczenie składane w Moja PG

Przed złożeniem pracy w systemie Moja PG student składa wymagane oświadczenia, w szczególności potwierdzając, że:

* jest świadomy odpowiedzialności prawnej i dyscyplinarnej związanej z naruszeniem praw autorskich oraz zasad uczciwości akademickiej,

* praca została opracowana samodzielnie, z zachowaniem zasad dotyczących wykorzystania cudzych materiałów,

* praca nie była wcześniej podstawą innej procedury związanej z nadaniem tytułu zawodowego,

* wykorzystane informacje, materiały i utwory pochodzące ze źródeł pisanych i elektronicznych zostały odpowiednio udokumentowane i wskazane w bibliografii lub w inny wymagany sposób,

* wykorzystanie narzędzi GenAI zostało zadeklarowane zgodnie z zasadami określonymi w rozdziale 9.

### 8.2 Zasady praktyczne

1. **Cytat a parafraza.**  
Prawo cytatu określone w art. 29 ustawy o prawie autorskim i prawach pokrewnych pozwala, w zakresie uzasadnionym m.in. celami takimi jak wyjaśnianie, polemika, analiza krytyczna lub nauczanie, przytaczać urywki rozpowszechnionych utworów, z zachowaniem wymagań wynikających z ustawy. 
Cytat powinien być wyraźnie oznaczony i opatrzony informacją o autorze oraz źródle. 
W przypadku cytatu dosłownego należy dodatkowo podać numer strony, jeżeli jest dostępny. 
Parafrazę należy napisać własnymi słowami i również opatrzyć odnośnikiem do źródła. 
**Zamiana kilku wyrazów lub zmiana kolejności zdań nie stanowi samodzielnej parafrazy.**

2. **Tłumaczenia.**  
Przetłumaczenie cudzego tekstu nie powoduje, że staje się on tekstem własnym. 
Tłumaczenie należy opatrzyć odpowiednim odnośnikiem do źródła i wyraźnie zaznaczyć jego charakter, jeżeli jest to istotne. 
Tłumaczenia mogą być również wykrywane przez narzędzia służące do wykrywania podobieństwa tekstu.

3. **Rysunki, schematy, zdjęcia i wykresy z cudzych publikacji.**  
Przed wykorzystaniem materiału należy sprawdzić warunki licencji lub inne podstawy prawne jego wykorzystania. 
W zależności od przypadku może być wymagana licencja, zgoda właściciela praw albo możliwość skorzystania z prawa cytatu. W każdym przypadku należy podać źródło w podpisie.  **Bezpieczniejszym rozwiązaniem jest przygotowanie własnej ilustracji na podstawie informacji ze źródła**, z odpowiednim oznaczeniem „Opracowano na podstawie [n]”.

4. **Licencje Creative Commons.**  
Przed wykorzystaniem materiału należy sprawdzić wszystkie warunki jego licencji. 
W szczególności:

    * **BY** — wymagane jest wskazanie autora,
    * **SA** — utwór zależny należy udostępniać na tych samych warunkach,
    * **NC** — wykorzystanie komercyjne jest niedozwolone,
    * **ND** — nie wolno rozpowszechniać utworów zależnych.

Należy sprawdzić pełne warunki konkretnej licencji, ponieważ poszczególne elementy materiału mogą podlegać dodatkowym ograniczeniom.

5. **Oprogramowanie open source.**  
Należy sprawdzić licencję każdej wykorzystanej biblioteki lub innego zewnętrznego komponentu oraz zachować informacje wymagane przez tę licencję, np. w katalogu `docs/third-party`. Licencje typu *copyleft* (np. GPL) mogą nakładać dodatkowe obowiązki dotyczące rozpowszechniania utworów zależnych. 
Licencje permisywne, takie jak MIT, BSD czy Apache 2.0, zwykle nakładają mniej ograniczeń, ale również mogą wymagać zachowania informacji o prawach autorskich i licencji. 
**Warunki należy analizować dla konkretnego sposobu wykorzystania oprogramowania.**

6. **Zbiory danych, czcionki i ikony.**  
Należy zapisać źródło oraz licencję każdego wykorzystanego zbioru danych i materiału. 
Nie należy zakładać, że materiał dostępny publicznie w internecie jest wolny od ograniczeń. 
W przypadku czcionek, ikon i grafik należy sprawdzić, czy ich licencja zezwala na wykorzystanie w pracy dyplomowej i jej publikację.

7. **Własny kod.**  
Licencję własnego kodu należy wybrać świadomie albo pozostawić repozytorium prywatne. 
Brak informacji o licencji w publicznym repozytorium nie oznacza automatycznie, że inni mogą swobodnie wykorzystywać kod. 
**Szablonu pracy nie należy umieszczać w publicznym repozytorium**, jeżeli jego licencja lub warunki udostępnienia na to nie pozwalają.

8. **Współpraca z firmą lub uczelnią zewnętrzną.**  
Przed rozpoczęciem prac należy ustalić **na piśmie**, kto posiada prawa do wyników i kodu, na jakich zasadach można je publikować oraz czy praca lub jej wyniki są objęte poufnością. 
W przypadku danych poufnych, niejawnych lub objętych ograniczeniami nie należy przekazywać ich do narzędzi GenAI.

9. **Praca zespołowa.**  
Każdy autor odpowiada za własny wkład w pracę. 
W przypadku pracy zespołowej należy jednoznacznie wskazać autorów poszczególnych rozdziałów i podrozdziałów oraz zapewnić, że podział ten odpowiada faktycznemu wkładowi autorów.


## 9. Generatywna sztuczna inteligencja (GenAI)

> **Student ponosi odpowiedzialność za poprawność merytoryczną pracy, niezależnie od wykorzystanych narzędzi.**

### 9.1 Obowiązki

- **Student musi uzgodnić z promotorem możliwość korzystania z narzędzi AI** oraz dopuszczalny zakres ich wykorzystania. Podejście poszczególnych opiekunów może się znacząco różnić. 
Domyślnie zakłada się samodzielne opracowanie i redakcję treści pracy, przy ograniczonym wykorzystaniu narzędzi AI.

- **W ramach dokumentacji pracy należy zamieścić informację o wykorzystanych narzędziach AI**, z wyszczególnieniem **miejsca wykorzystania narzędzia**, **zakresu jego ingerencji** oraz **wkładu własnego autora**, zgodnie z zasadami określonymi w obowiązujących wytycznych uczelni.

- Po złożeniu pracy w systemie Moja PG należy wskazać sekcje, w których korzystano z AI, oraz opisać stopień ingerencji narzędzia w treść końcową. 
W oświadczeniu należy wybrać właściwą opcję dotyczącą wykorzystania GenAI. 
Jeżeli obowiązujące regulacje wymagają dodatkowego zestawienia wykorzystanych narzędzi, stron lub zakresu ingerencji, należy je dołączyć zgodnie z określonym wzorem. 
W przypadku wymagającym wskazania wykorzystania narzędzia w bibliografii należy zastosować sposób określony w obowiązujących wytycznych.

- Do narzędzi GenAI **nie wolno wprowadzać danych wrażliwych, poufnych ani innych informacji objętych ograniczeniami dotyczącymi udostępniania**.

- Student powinien zachować pełną kontrolę nad treścią pracy oraz **samodzielnie zweryfikować poprawność wszystkich informacji, obliczeń, odwołań do źródeł i wyników** uzyskanych z pomocą AI.

### 9.2 Przykłady użycia

| Niedopuszczalne                                                                                                                      | Dopuszczalne pomocniczo (po uzgodnieniu z promotorem)                                                                                                                                                                             |
| ------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ❌ Generowanie całych fragmentów pracy przeznaczonych do bezpośredniego wykorzystania, w szczególności zdań, akapitów lub rozdziałów. | ✅ Korekta stylistyczna i gramatyczna własnego tekstu, z krytyczną analizą sugestii i samodzielnym wprowadzeniem zaakceptowanych zmian.                                                                                            |
| ❌ Generowanie cytowań lub opisów bibliograficznych i umieszczanie ich w pracy bez samodzielnej weryfikacji.                          | ✅ Poszukiwanie potencjalnych źródeł. Artykuł wskazany przez AI należy samodzielnie odnaleźć w wiarygodnym źródle, zapoznać się z jego treścią i dopiero wtedy wykorzystać go w pracy.                                             |
| ❌ Generowanie grafik i ilustracji przeznaczonych do bezpośredniego wykorzystania w pracy.                                            | ✅ Wskazywanie niespójności w numeracji, odwołaniach, strukturze dokumentu lub formatowaniu, z ręczną weryfikacją i korektą.                                                                                                       |
|                                                                                                                                      | ✅ Pomoc techniczna przy przygotowywaniu plików `.tex`, np. tworzenie szablonów tabel, ustawień pozycjonowania grafik czy elementów składni LaTeX-a, pod warunkiem samodzielnego zrozumienia i zweryfikowania wygenerowanego kodu. |

**Dobra praktyka:** korektę językową własnego tekstu warto przeprowadzać etapami, najlepiej zdanie po zdaniu lub na niewielkich fragmentach. 
Przydatne jest żądanie przedstawienia tekstu przed korektą, po korekcie oraz krótkiego opisu i uzasadnienia wprowadzonych zmian. 
Jednorazowe przekazywanie dużych bloków tekstu i bezrefleksyjne kopiowanie wyników zwiększa ryzyko nadmiernej, słabo zweryfikowanej ingerencji AI w treść pracy.

### 9.3 Najczęstsze problemy

- nadmiernie rozbudowane opisy zwiększające objętość pracy bez istotnej wartości merytorycznej,

- błędy rzeczowe i informacje niezgodne ze źródłami,

- brak spójności między poszczególnymi częściami pracy,

- pomijanie odwołań do rysunków, tabel, źródeł i innych rozdziałów,

- fragmenty oderwane od rzeczywistego kontekstu projektu,

- **fikcyjne odwołania do literatury**, w tym nieistniejące publikacje, błędne dane bibliograficzne lub przypisanie treści do niewłaściwego źródła.

Wszelkie treści opracowywane z pomocą AI wymagają **krytycznej analizy, samodzielnej weryfikacji i starannej redakcji**.

## 10. Zbiór uwag językowych

### 10.1 Styl i język

- Praca jest dokumentem formalnym. 
Należy unikać skrótów myślowych, niedomówień, języka przesadnie „poetyckiego” oraz nieformalnego języka mówionego.

- Zalecany jest **styl bezosobowy**, bez stosowania pierwszej osoby liczby pojedynczej i mnogiej. 
Zamiast „Wydrukowaliśmy obudowę robota” można napisać „Obudowa robota została wykonana w technologii druku 3D”. 
Z tekstu musi jednak jednoznacznie wynikać, **które elementy zostały wykonane przez autora, a które pochodzą z gotowych rozwiązań sprzętowych, programistycznych lub bibliotecznych**.

- Jedno pojęcie powinno być oznaczane konsekwentnie tym samym terminem. 
W przypadku terminów specjalistycznych należy unikać zastępowania precyzyjnego terminu synonimami wyłącznie w celu uniknięcia powtórzeń. 
W pozostałych przypadkach należy unikać nadmiernego powtarzania tych samych sformułowań w bezpośrednim sąsiedztwie.

- **Czas teraźniejszy** stosuje się do opisu praw, zjawisk, algorytmów, metod i rozwiązań o charakterze ogólnym. 
**Czas przeszły** stosuje się do opisania działań wykonanych w ramach realizacji pracy, np. przebiegu eksperymentów i przeprowadzonych pomiarów.

- Należy preferować zdania o prostej i przejrzystej konstrukcji, szczególnie w przypadku złożonych zagadnień technicznych. 
Należy unikać bardzo długich zdań zawierających wiele wtrąceń oraz konstrukcji mogących prowadzić do niejednoznaczności, np. „Żmija ukąsiła Kleopatrę i umarła”.

- Jeden akapit powinien koncentrować się na **jednej głównej myśli**. 
Należy korzystać ze sprawdzania pisowni i podstawowej kontroli gramatycznej. 
Warto również poprosić drugą osobę o przeczytanie pracy oraz przeczytać gotowy tekst w formie wydruku lub w innym układzie niż ten, w którym był redagowany.

### 10.2 Drobne uwagi

| Zagadnienie                            | Zasada                                                                                                                                                                                                                                                                                                                                                                |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **„ilość” / „liczba”**                 | „Ilość” stosuje się przede wszystkim do wielkości niepoliczalnych, np. ilość wody. „Liczba” odnosi się do elementów policzalnych, np. liczba wejść sterownika, liczba punktów pomiarowych.                                                                                                                                                                            |
| **„stwarzać”**                         | Czasownik „stwarzać” oznacza m.in. powodować powstanie określonej sytuacji lub warunków. W opisie procesu technicznego często precyzyjniejsze będą czasowniki: budować, wytwarzać, konstruować, projektować, tworzyć lub opracowywać — zależnie od kontekstu.                                                                                                         |
| **Zdania rozpoczynające się od „Aby”** | Nie ma potrzeby całkowitego unikania takich konstrukcji. Jeżeli zdanie staje się dzięki nim niejasne lub ciężkie stylistycznie, można zastosować inną konstrukcję, np. „W celu zasilenia urządzenia należy…”.                                                                                                                                                         |
| **„to”, „ten”, „tego”, „które”**       | Należy unikać nadmiernego stosowania zaimków, jeżeli utrudniają jednoznaczne wskazanie opisywanego elementu. Zamiast „Paul jest to ramię robotyczne, które potrafi…” można napisać „Paul jest ramieniem robotycznym umożliwiającym…”. Samo użycie zaimka „który/która/które” jest jednak poprawne i nie powinno być eliminowane wyłącznie ze względów stylistycznych. |
| **„położenie” / „pozycja”**            | Terminy należy stosować konsekwentnie i zgodnie z ich znaczeniem w danej dziedzinie. „Położenie” odnosi się zwykle do lokalizacji obiektu w przestrzeni, np. położenie robota. „Pozycja” może oznaczać m.in. ułożenie, stan lub ustawienie, np. pozycja startowa. W terminologii technicznej znaczenie obu słów może zależeć od kontekstu.                            |
| **Precyzja liczb**                     | Liczbę cyfr znaczących należy dostosować do dokładności pomiaru i niepewności wyniku. Nie należy podawać większej liczby cyfr, niż uzasadnia dokładność zastosowanej metody pomiarowej.                                                                                                                                                                               |
