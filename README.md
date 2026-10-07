# Wytyczne dotyczące realizacji i redakcji pracy dyplomowej
**Status dokumentu** dokument jest uzupełniający, ma charakter dobrych praktych poza sekcją dotyczącą AI. Jednakże nie zastępuje oficjalnych wytycznych wydziałowych, ani uczelnianych dostępnych na [stronie wydziału ETI](https://eti.pg.edu.pl/studenci/dyplomy). W razie rozbieżności obowiązują wytyczne wydziałowe, oraz regulamin uczelni.
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
| **Samodzielność** | Praca jest wykonywana samodzielnie, w zakresie celu i zadań uzgodnionych z promotorem. Student ponosi pełną odpowiedzialność za poprawność merytoryczną tekstu, niezależnie od użytych narzędzi. |
| **Objętość** | 40–60 stron (bez dodatków). Przy dwóch autorach praca może być dłuższa. |
| **Streszczenie i Abstract** | Każde min. 300 słów, wraz ze słowami kluczowymi (*keywords*). |
| **Bibliografia** | Min. 15 pozycji (w tym min. 5 obcojęzycznych i min. 10 naukowych), norma PN-ISO 690:2012. |
| **Kod** | Brak listingów i odwołań do kodu w pracy (poza dodatkami). Kod dołączany jako osobne archiwum `.zip` w systemie Moja PG. |
| **Wkład własny** | Wyraźnie oddzielony od bibliotek, gotowych modułów i wcześniejszych prac. |
| **Ocena** | Kamienie milowe (głównie koniec pierwszego semestru) podlegają ocenie. |
| **AI** | Możliwość korzystania z AI należy uzgodnić z promotorem; użycie dokumentuje się w załączniku. |
| **Szablon** | Praca powstaje w szablonie wydziałowym (LaTeX lub Word). |

---

## 2. Organizacja pracy i komunikacja z promotorem

### 2.1 Oczekiwania po 6./2. semestrze

Po zakończeniu 6./2. semestru student powinien dysponować wstępnym szkicem pracy, potencjalnie rozdziałem przeglądowym i udokumentowanym stanem zaawansowania projektu. Oczekuje się:
- spisu treści,
- wstępu,
- rozdziału przeglądowego,
- krótkiej informacji o postępach prac (zwięzły opis aktualnego etapu: co zostało wykonane, a co pozostaje do wykonania).

### 2.2 Kamienie milowe i ocena

- Kamienie milowe podlegają ocenie i są ustalane przez promotora.
- Ocena z przedmiotu „praca dyplomowa" wynika ze stanu pracy na koniec pierwszego semestru.
- Kamień milowy powinien być sprawdzalny, np.: „Działający prototyp z testami jednostkowymi i raportem z pomiarów bazowych" zamiast „Praca nad projektem".

### 2.3 Planowanie czasu

Realizacja pracy wymaga rozplanowania działań w czasie. Odkładanie zasadniczej części zadań na końcowy etap utrudnia przygotowanie spójnego opracowania.

- Harmonogram powinien uwzględniać **rezerwę czasową** na modyfikacje i usprawnienia projektu. Założenia przyjęte na początku często nie znajdują pełnego odzwierciedlenia w rzeczywistości.
- Należy możliwie wcześnie rozpocząć: budowę lub uruchamianie stanowiska bądź urządzenia, implementację i testowanie oprogramowania, gromadzenie źródeł oraz pisanie kolejnych fragmentów tekstu.
- Warto wykorzystać okres wakacyjny (w pracach inżynierskich) na wykonanie części zadań odciążających późniejsze etapy.
- **Ostatni miesiąc przed złożeniem pracy powinien być przeznaczony wyłącznie na pisanie.**
- Proces korekty może zająć **do dwóch tygodni**, zwłaszcza przy kilku etapach poprawek. W okresach zwiększonego obciążenia promotora czas oczekiwania na sprawdzenie tekstu może się wydłużyć, dlatego należy przewidzieć zapas czasu.

Terminy szczegółowe (rozdziały implementacyjny i testowy, złożenie pełnej pracy) ustala się indywidualnie z promotorem oraz według aktualnego [kalendarza roku akademickiego WETI](https://eti.pg.edu.pl/studenci/dziekanat/kalendarz-roku-akademickiego).

### 2.4 Komunikacja z promotorem

Nie ma obowiązku regularnego składania szczegółowych raportów; student samodzielnie planuje i prowadzi kolejne etapy pracy. **Sugerowany jest jednak stały rytm spotkań (np. co 2 tygodnie).** Ustalenia warto zapisywać w repozytorium projektu lub w Moja PG.

Kontakt jest wskazany w szczególności, gdy:

- pojawiają się istotne trudności techniczne lub organizacyjne,
- konieczne jest skonsultowanie kierunku dalszych działań,
- przygotowano fragment pracy do weryfikacji,
- potrzebna jest decyzja dotycząca doboru metod, komponentów lub zakresu opracowania.

**Zasady przekazywania tekstu:**

- Rozdziały oddaje się promotorowi **kolejno**, a nie całość naraz; **data znajduje się w nazwie pliku**.
- Pracę wysyła się do weryfikacji dopiero po uważnym przeczytaniu i usunięciu błędów językowych. Promotor nie jest korektorem podstawowych błędów. Praca przygotowana pobieżnie nie przyspiesza recenzowania, a wydłuża je.
- Zmianę tematu lub opiekuna zgłasza się przed uruchomieniem prac, a nie pod koniec semestru.

---

## 3. Struktura pracy

### 3.1 Układ pracy

| Część | Element | Uwagi |
|---|---|---|
| **Front matter** *(bez numeracji stron)* | Strona tytułowa | Wzór pobrany z Moja PG, zgodny z rodzajem pracy („Projekt dyplomowy inżynierski"). |
| | Streszczenie | Min. 300 słów + słowa kluczowe. |
| | Abstract | Min. 300 słów + *keywords*. |
| | Spis treści | Wszystkie rozdziały, podrozdziały i punkty z numerami stron. W pracy zespołowej autor każdej części. |
| | Wykaz oznaczeń | Symbole z jednostkami i krótkim opisem. |
| | Wykaz skrótów | Skróty użyte w tekście. |
| **Body matter** | Wstęp i cel pracy | 1–2,5 strony. |
| | Rozdziały merytoryczne | Patrz sekcja 3.3. |
| | Zakończenie (Podsumowanie) | Efekty, odniesienie do celu, wnioski, dalsze prace. |
| **Back matter** | Bibliografia | Patrz sekcja 5. |
| | Załączniki / dodatki | Patrz sekcja 6. |

Strona tytułowa nie ma widocznego numeru. Numeracja stron w pozostałej części jest ciągła.

### 3.2 Wstęp i cel pracy (1–2,5 strony)

Rozdział pierwszy występuje we wszystkich pracach i ma stałą strukturę. Zaleca się przygotowanie go **po** opracowaniu zasadniczej części pracy.

**Wprowadzenie (tło)**
- krótkie nawiązanie do tematu: trendy w dziedzinie, zarys historyczny, definicje pojęć, tło społeczne, użytkowe lub badawcze,
- jeśli w celu pracy pojawiają się mniej oczywiste terminy techniczne, objaśnia się je we wprowadzeniu,
- bez ilustracji, zdjęć i wykresów.

**Cel pracy**
- jasne, zwięzłe sformułowanie, **mierzalne**, wraz z ewentualną **tezą** i **założeniami**,
- niedoprecyzowane ogólniki należy zamieniać na sformułowania sprawdzalne (patrz tabela w sekcji 4.1),
- w wyjątkowych sytuacjach możliwa jest praca „negatywna" (niespełniająca założonego celu), jednak nieosiągnięcie celu musi być szczegółowo wyjaśnione.

**Założenia projektowe**
- np. wymóg użycia konkretnego urządzenia (robot z wyposażenia laboratorium), minikomputera lub algorytmu (A\*, sztuczne potencjały),
- jeżeli wybór sprzętu lub metody wynika z późniejszych decyzji projektowych, nie umieszcza się go w założeniach.

**Podział pracy** *(tylko w pracach dwuosobowych)*
- opis podziału zadań pomiędzy autorów; zalecane ujęcie opisowe, dopuszczalna lista.

**Opis poszczególnych rozdziałów**
- krótki przegląd struktury pracy, np. „W rozdziale drugim przedstawiono…", „Uzyskane wyniki opisano w rozdziale szóstym".

### 3.3 Rozdziały merytoryczne

Liczba stron poszczególnych rozdziałów **nie jest odgórnie narzucona**. W razie wątpliwości należy dopytać promotora lub osobę prowadzącą seminarium dyplomowe inżynierskie.

**Rozdziały obowiązkowe:**

1. **Rozdział teoretyczny**
   - krótkie wprowadzenie,
   - modele, algorytmy, wzory i założenia, z których korzysta praca (każdy symbol zdefiniowany, pochodzenie wzoru pokazane),
   - szczegółowo omówiony zakres teoretyczny wynikający z przeglądu,
   - podsumowanie rozdziału.
2. **Rozdział przeglądowy**
   - krótkie wprowadzenie,
   - przegląd istniejących rozwiązań przemysłowych i naukowych z podziałem na pod-problemy (tu znajduje się większość cytowań),
   - przegląd istniejących zbiorów danych (według potrzeb),
   - porównanie rozwiązań według jawnych kryteriów, wskazanie luki lub potrzeby,
   - podsumowanie porównawcze, z którego wynika sposób realizacji pracy.
2. **Rozdział opisujący rozwiązanie**
   - krótkie wprowadzenie,
   - wymagania, 
   - architektura, 
   - decyzje projektowe z uzasadnieniem, 
   - wybór technologii i elementów 
   - szczegółowe przedstawienie rozwiązania algorytmicznego lub sprzętowego (o ile nie jest zawarte w innym rozdziale),
   - podsumowanie porównawcze.
4. **Rozdział z testami i wynikami**
   - plan testów, metodyka pomiarów, wyniki **wraz z niepewnością**,
   - porównanie z kryteriami sukcesu i z rozwiązaniami z przeglądu,
   - ograniczenia oraz różnice między symulacją a systemem rzeczywistym,
   - podsumowanie.

**Rozdziały zależne od tematu pracy** (dobiera się je odpowiednio do charakteru projektu):
- konstrukcja mechaniczna,
- projekt elektroniczny,
- użyte / opracowane algorytmy (w tym model matematyczny obiektu),
- implementacja (szczegóły implementacyjne, aspekty mocy obliczeniowej).

Wkład własny jest wyraźnie oddzielony od gotowych bibliotek, modułów i wcześniejszych prac (sekcja 6.1).

**Przykładowy układ** pracy o charakterze sprzętowym (ostateczna struktura dokumentu):

1. Wstęp i cel pracy
2. Rozdział teoretyczny
3. Przegląd literatury / istniejących rozwiązań
4. Konstrukcja mechaniczna
5. Układ elektroniczny
6. Algorytmy sterowania
7. Oprogramowanie i implementacja
8. Testy i wyniki
9. Podsumowanie

**Zasady ogólne dla rozdziałów:**

- Każdy rozdział zaczyna się wprowadzeniem, a kończy podsumowaniem lub przejściem do następnego.
- Struktura nie powinna przypominać kryminału: kluczowe informacje nie mogą pojawiać się dopiero na końcu. Należy ograniczać odwołania do treści z późniejszych rozdziałów; dopuszczalne są odwołania do elementów umieszczonych wcześniej.
- Wszystkie odwołania (do wzorów, rysunków, tabel, źródeł) przygotowuje się w formie hiperłączy.
- Podrozdział nie powinien być krótszy niż jedna strona. Nie zakłada się nowego podrozdziału dla jednego krótkiego akapitu.
- Nagłówek nie może pozostać samotnie na dole strony; nie umieszcza się rysunku bezpośrednio po tytule rozdziału lub podrozdziału.

**Zakończenie (Podsumowanie)** zawiera: efekty i osiągnięcia, odniesienie do celu i założeń (w tym kryteriów sukcesu), wnioski, elementy niezrealizowane wraz z przyczynami, możliwe kierunki dalszego rozwoju.

### 3.4 Streszczenie i Abstract

- Min. 300 słów każde, w wersji polskiej i angielskiej; dodatkowo **słowa kluczowe** i *keywords*.
- Zawartość: problem do rozwiązania, cel i zakres, metody, wyniki, najważniejsze wnioski.
- **Nie opisuje się** zawartości poszczególnych rozdziałów („W rozdziale drugim opisano…").
- **Nie podaje się** nadmiernych szczegółów technicznych (typ mikrokomputera, model lidaru, rodzaj baterii), chyba że mają fundamentalne znaczenie dla tematu.
- Celem jest umożliwienie czytelnikowi oceny przydatności pracy bez czytania całości.

### 3.5 Spis treści, wykaz oznaczeń i skrótów

- Spis treści powinien być przejrzysty; numery stron wyrównane do prawej, tytuły z odpowiednimi wcięciami. Zwykle jest generowany automatycznie. Należy unikać zbyt długich tytułów oraz nadmiernej fragmentaryzacji.
- Wykaz oznaczeń: symbole z jednostkami i jednoznacznymi opisami. Symbol używany w kilku miejscach pracy umieszcza się na liście; symbol lokalny (jedno równanie) nie jest potrzebny. 
- Dopuszczalne (wskazane przy listach większych niż strona) jest wydzielenie osobnych list symboli matematycznych i skrótów.
- Każdy skrót rozwija się przy pierwszym użyciu w tekście.

---

## 4. Praktyczne wskazówki inżynierskie

### 4.1 Jak formułować cel i kryteria sukcesu

| Element | Słaba formuła | Sprawdzalna formuła |
|---|---|---|
| Cel | „Zbadanie możliwości wykorzystania AI w robotyce" | „Zaprojektowanie i zaimplementowanie klasyfikatora X działającego na platformie Y z opóźnieniem poniżej 50 ms" |
| Kryterium sukcesu | „Dobra dokładność" | „Dokładność co najmniej 90 % na zbiorze testowym Z, wyznaczona według opisanej procedury" |
| Kamień milowy | „Praca nad projektem" | „Działający prototyp z testami jednostkowymi i raportem z pomiarów bazowych" |

### 4.2 Trzy zasady podnoszące jakość pracy technicznej

1. **Model, symulacja i rzeczywistość są rozdzielone.** Wynik symulacji nie przenosi się wprost na sprzęt: dochodzą szum, opóźnienia, kalibracja, tolerancje elementów i awarie czujników. W pracy obejmującej modelowanie, symulację i system rzeczywisty należy opisać wszystkie te poziomy oraz różnice między nimi.
2. **Podaje się niepewność i warunki pomiaru.** Wynik bez liczby powtórzeń, konfiguracji stanowiska i niepewności nie jest porównywalny. Liczba cyfr znaczących powinna odpowiadać dokładności pomiaru, aby nie sugerować większej precyzji, niż uzyskano.
3. **Rozwiązanie programowe jest testowane i wersjonowane.** Testy automatyczne implementuje się tam, gdzie to możliwe. W repozytorium znajduje się opis zmian wersji i opis uruchomienia. Opisuje się też narzędzia, dane i konfigurację sprzętową.

### 4.3 Unikanie wypełniaczy

Nie należy sztucznie zwiększać objętości pracy treściami oczywistymi, ogólnie dostępnymi lub przejętymi bezrefleksyjnie z internetu. Każdy fragment musi mieć uzasadnienie merytoryczne.

- **Przykład (protokół I2C):** jeśli celem pracy jest własna, niskopoziomowa obsługa protokołu, szczegółowy opis ramek, adresowania i potwierdzeń jest uzasadniony. Jeśli protokół jest używany przez gotowe biblioteki (np. Raspberry Pi ↔ Arduino), wystarczy krótkie wskazanie jego użycia, rodzaju danych i biblioteki.
- **Przykład (ilustracje):** w pracy o budowie urządzenia nie umieszcza się osobnych zdjęć każdego komponentu. Wystarczą schemat elektryczny i zdjęcia gotowego urządzenia. Dla płytki PCB warto zamieścić projekt, bez etapów montażu.
- Materiały, do których nie odwołuje się szczegółowo w tekście (schematy elektryczne, projekty PCB), przenosi się do dodatków, wskazując w pracy ich lokalizację.

---

## 5. Bibliografia i cytowanie

### 5.1 Wymogi ilościowe i formalne

- **Min. 15 pozycji** (bez stron internetowych), w tym **min. 5 obcojęzycznych** i **min. 10 naukowych**. Jest to **sugerowana liczba pozycji**; w razie wątpliwości co do zakresu należy skonsultować się z promotorem.
- Opis zgodny z normą **PN-ISO 690:2012**, w jednolitym stylu w całej pracy.
- W wykazie umieszcza się wyłącznie źródła, z których faktycznie korzystano i do których odwołano się w tekście. Źródło należy przeczytać przed zacytowaniem.
- Pozycję z wykazu należy przywołać w tekście; wszystkie wpisy sprawdza się w oryginalnych źródłach (DOI, autorzy, rok, strony).
- Przy źródle z więcej niż 3 autorami można podać pierwszego autora z dopiskiem *et al.*

### 5.2 Rodzaje źródeł

| Rodzaj | Zasada |
|---|---|
| **Literatura naukowa** | Książki, artykuły naukowe, rozdziały prac zbiorowych, prace dyplomowe i doktorskie, inne recenzowane źródła. Stanowią trzon bibliografii. |
| **Dokumentacje, noty katalogowe, normy, strony WWW** | Dopuszczalne jako uzasadnione źródła techniczne, **ale nie zastępują literatury naukowej**. Strony WWW opisuje się autorem (jeśli jest), tytułem lub krótkim opisem, adresem URL i **datą dostępu**. Przed złożeniem pracy należy zweryfikować aktywność linków i zaktualizować datę dostępu. |
| **Wikipedia** | **Niewskazana jako źródło.** Można ją wykorzystywać pomocniczo i krytycznie; może natomiast służyć do odnalezienia źródeł pierwotnych (odnośniki na dole strony), które należy zacytować. |

Źródła należy wyszukiwać m.in. w: [Google Scholar](https://scholar.google.com/) (dane bibliograficzne zawsze sprawdzać w oryginale), [IEEE Xplore](https://ieeexplore.ieee.org), [ScienceDirect](https://www.sciencedirect.com). Dostęp do pełnych tekstów z sieci uczelni można sprawdzić w bibliotece PG.

### 5.3 Przykłady opisów (ilustracja elementów wymaganych)

**Książka** — nazwisko i inicjały autora, tytuł, wydawca, rok.
> M. Niedźwiecki, *Identification of Time-Varying Processes*, Wiley & Sons, 2000.

**Artykuł naukowy** — autorzy, tytuł, czasopismo lub konferencja, tom/numer, strony lub numer artykułu, rok, miejsce (konferencje), DOI.
> S. Bennett, „Development of the PID controller", *IEEE Control Systems Magazine*, nr 13, ss. 58–62, 1993, doi: [10.1109/37.248006](https://doi.org/10.1109/37.248006).

**Rozdział pracy zbiorowej** — autor rozdziału, tytuł rozdziału, tytuł pracy zbiorowej, redaktorzy, wydawca, rok.
> A. J. Krener, *The Important State Coordinates of a Nonlinear System*, w: *Advances in Control Theory and Applications*, red. C. Bonivento et al., Springer, 2007.

**Rozprawa doktorska** — jak książka, z informacją o charakterze pracy i uczelnią zamiast wydawcy.
> T. H. Eggen, *Underwater Acoustic Communication Over Doppler Spread Channels*, rozprawa doktorska, Massachusetts Institute of Technology, 1997.

**Źródło internetowe** — autor, tytuł/opis, URL, data dostępu.

> Ostateczny format wpisów wynika ze stylu bibliograficznego zastosowanego w szablonie i normy PN-ISO 690:2012. Jeśli komentarz w szablonie mówi coś innego niż ogólne zasady z tego dokumentu, obowiązuje szablon.

### 5.4 Cytowanie w tekście

- Odnośnik stawia się **przed kropką** kończącą zdanie; numer odpowiada pozycji w wykazie.
- W LaTeX-ie przed `\cite` wstawia się **twardą spację** (`~`):

```latex
Algorytm został opisany w pracy~\cite{kowalski2002}.
Porównywano kilka podejść~\cite{kowalski2002,nowak2002}.
```

- Przy cytacie dosłownym stosuje się cudzysłów i podaje numer strony.
- Odwołanie do kilku pozycji jednocześnie: zapis zbiorczy (`\cite{a,b}`) lub kolejne nawiasy kwadratowe.

---

## 6. Kod źródłowy, załączniki i dokumentacja projektowa

### 6.1 Wkład własny a gotowe rozwiązania

- Wkład własny musi być **wyraźnie oddzielony** od bibliotek, gotowych modułów i wcześniejszych prac.
- Nazwy użytych bibliotek należy **wyraźnie wskazać** (np. OpenCV) oraz opisać, jaką funkcjonalność dzięki nim uzyskano. Nie podaje się nazw funkcji ani klas.
- Należy **wskazać, co dokładnie autor zaimplementował samodzielnie**.
- W pracy podaje się informacje o środowisku programistycznym i języku. W pracach z elementami konstrukcyjnymi zaleca się wskazanie oprogramowania CAD.
- W pracy zespołowej wskazuje się autorów rozdziałów i podrozdziałów.

### 6.2 Brak kodu w tekście pracy

- W pracy (poza dodatkami) **nie zamieszcza się listingów, snippetów kodu ani jakichkolwiek odwołań do kodu**.
- Algorytm lub rozwiązanie przedstawia się za pomocą: **wzorów matematycznych, grafów, schematów, rysunków** oraz (jako formy najmniej czytelnej, lecz dopuszczalnej) opisu słownego. Zaleca się łączenie kilku technik jednocześnie.
- Opis ma przedstawiać istotę rozwiązania bez odwoływania się do formy implementacji: **bez nazw funkcji i zmiennych**, o ile nie jest to bezwzględnie konieczne. Warstwę koncepcyjną i matematyczną opisuje się symboliką matematyczną.
- Algorytmy można zapisywać pseudokodem z numerowanymi krokami; złożoność podaje się, gdy ma znaczenie.
- Wyjątek: prace, w których analiza kodu jest istotą tematu. Niedopuszczalne jest zastępowanie wyjaśnienia algorytmu fragmentami kodu.

### 6.3 Załączniki i dokumentacja elektroniczna

**Kod i materiały dodatkowe** dołącza się do systemu **Moja PG jako jedno skompresowane archiwum `.zip`** (nazwa: `PDI_zalacznik_numer albumu`). Zawartość archiwum:

- kod źródłowy wytworzony w ramach pracy,
- **README**,
- **konfiguracja** oraz wersje użytych narzędzi,
- **skrypty odtwarzające wyniki**,
- dane i inne materiały uzupełniające (z zapisanymi źródłami i licencjami),
- **bez haseł, kluczy API i tokenów**.

**Załączniki w pracy** (back matter, numerowane z wyjątkiem bibliografii):

- obliczenia, schematy ideowe i inne materiały uzupełniające,
- **instrukcja użytkownika** — jak uruchomić sprzęt lub oprogramowanie,
- **instrukcja programisty** — co i gdzie znajduje się w kodzie (tu dopuszczalne są krótkie listingi z numerem i podpisem),
- **lista użytego oprogramowania AI** wraz z wyszczególnieniem akapitów, udziału AI i wkładu własnego (sekcja 9).

---

## 7. Zasady edytorskie

Szablon LaTeX ustawia większość wymagań automatycznie, jednak część elementów należy sprawdzić ręcznie. Jeśli komentarz w szablonie przeczy ogólnym zasadom poniżej, obowiązuje szablon.

### 7.1 Wymagania formalne

| Element | Wymóg |
|---|---|
| Nazwa pliku pracy | `PDI_numer albumu` |
| Nazwa archiwum z załącznikami | `PDI_zalacznik_numer albumu` |
| Arkusz | A4, orientacja pionowa |
| Czcionka | **Arial, 10 pkt** (zgodnie z Księgą Identyfikacji Wizualnej PG) |
| Interlinia | **1,5 wiersza** |
| Tekst i marginesy | tekst wyjustowany, **marginesy w odbiciu lustrzanym** |
| Numeracja stron | ciągła, w stopce; bez numeru na stronie tytułowej; unikać pustych stron |
| Wcięcia akapitów | jednakowa głębokość w całej pracy; tekst nie może wychodzić poza marginesy |
| Tabele i rysunki | podpis tabeli **nad** tabelą, podpis rysunku **pod** rysunkiem; każdy element przywołany w tekście |
| Terminologia | definicja terminu przy pierwszym użyciu; żadnych skrótów metod, firm itp. bez wcześniejszego rozwinięcia |

### 7.2 Typografia polska

- **Twarda spacja** po jednoliterowych spójnikach i przyimkach (i, w, z, o, a, u) oraz między liczbą a jednostką. W LaTeX-ie znak `~` (np. `w~układzie`, `10~kHz`). Nie wolno pozostawiać na końcu wiersza samotnych „W", „Z", „Do", rozdzielać liczby od jednostki ani dzielić treści w nawiasach (np. współrzędnych punktu).
- **Przecinek dziesiętny** (3,14) w całej pracy: w tekście, wzorach, tabelach, rysunkach, wykresach i prezentacji. Przy dwóch liczbach ułamkowych w nawiasach (np. współrzędne) liczby rozdziela się **średnikiem**: *O* = (10,2; 4,2). Separatorem tysięcy jest twarda spacja. Wyjątek: rysunek z zewnętrznego źródła, którego nie można spolonizować bez naruszenia integralności.
- **Półpauza** (–) w zakresach (2–5) i jako myślnik w zdaniu; dywiz (-) tylko w wyrazach złożonych.
- **Cudzysłów** w tekście polskim: „…”; w angielskim: “…”; stylów nie miesza się.
- **Wyliczenia**: jedna konwencja interpunkcji w całej pracy.
- **Liczby z jednostkami**: wartość oddzielona od jednostki spacją (10 kg, 5 m, 3 s). Stosuje się jednostki układu SI, zapisywane prosto.
- **Wstawki angielskojęzyczne**: unikać, chyba że brak sensownego polskiego odpowiednika lub termin angielski jest bardziej utrwalony. Termin angielski wprowadza się kursywą przy pierwszym użyciu, z polskim odpowiednikiem (jeśli istnieje). Dotyczy to także prezentacji.

### 7.3 Symbole i wzory

**Symbole**
- Symbole są jednoelementowe (pojedyncze litery, ewentualnie z indeksami). Nie stosuje się w wzorach nazw pochodzących z kodu (np. „indeks" mógłby być odczytany jako iloczyn liter).
- Ten sam symbol nie oznacza różnych wielkości w różnych miejscach pracy. Wielkości powiązane rozróżnia się indeksami dolnymi lub górnymi, z uwagą na możliwą pomyłkę z potęgą. Przykład: punkt na obrazie *O*, jego współrzędne *O<sub>x</sub>*, *O<sub>y</sub>*; ten sam punkt w różnych układach: *O<sup>A</sup>*, *O<sup>B</sup>*.
- Symbole zmiennych pisze się kursywą; nazwy funkcji i stałe matematyczne (e, π) czcionką prostą.
- **Symbole w tekście, wzorach, na rysunkach i w tabelach muszą wyglądać identycznie** (czcionka, styl, rozmiar).

**Wzory**
- Wzory są wyśrodkowane, numerowane po prawej stronie w nawiasach okrągłych i przywoływane przez `\eqref` („zgodnie ze wzorem (3)”).
- Wzór jest częścią zdania: kończy się kropką lub przecinkiem.
- Każdy symbol objaśnia się po wzorze, z jednostką. Preferowane jest objaśnienie w toku zdania („…, gdzie *s* oznacza drogę, a *t* — czas"); dopuszczalna jest lista pod wzorem. W całej pracy stosuje się jeden sposób. Powtarzających się symboli nie definiuje się ponownie.
- **Wyprowadzenia**: zakres szczegółowości konsultuje się z promotorem. Zasadniczo wystarczą założenia początkowe i wynik końcowy, ewentualnie kluczowe etapy pośrednie. Dla zależności geometrycznych zaleca się rysunek poglądowy zamiast pełnego wyprowadzenia.

### 7.4 Rysunki i tabele

**Wygląd i treść**
- Rysunki i tabele mieszczą się w obrębie marginesów tekstu; rysunki są wyśrodkowane.
- Każdy rysunek ma numer i podpis pod nim. Dwa rysunki obok siebie: jeden wspólny podpis i oznaczenia a), b).
- Każdy rysunek i tabela są uzasadnione w treści: przywołane w tekście i omówione. Nie wstawia się rysunków bez wartości merytorycznej (np. przypadkowych zrzutów ekranu). **Zrzutów ekranu kodu nie wkleja się.**
- Wykresy mają tytuł (lub podpis), opisy osi z **jednostkami**, wartości liczbowe na osiach i legendę; muszą być czytelne w druku czarno-białym.
- Czcionka podpisów na rysunkach i w tabelach ma rozmiar zbliżony do tekstu głównego.
- Schematy elektryczne rysuje się w spójnej konwencji symboli (IEC lub IEEE).

**Jakość graficzna**
- Schematy i wykresy: **grafika wektorowa** (PDF, SVG, EPS). Rastry: **min. 300 dpi**. Fotografie mogą być rastrowe.

**Źródło rysunków i tabel**
- Rysunek lub tabela przejęte albo przerobione z cudzego źródła mają w podpisie odnośnik: **„Źródło: [n]”** lub **„Opracowano na podstawie [n]”**. Pozostałe są opracowaniem własnym (czego w pracy się nie zapisuje).
- Umieszczenie cudzego materiału wymaga **licencji (np. Creative Commons), zgody właściciela praw lub podstawy w prawie cytatu** (sekcja 8). Bezpieczniej narysować własną wersję i opisać ją jako „Opracowano na podstawie [n]”.

**Sposób pisania o rysunkach**
- **Rysunkowi nie przypisuje się czynności.** Zamiast „Rysunek 4.7 przedstawia uzyskane rezultaty” → „Na rysunku 4.7 przedstawiono uzyskane rezultaty”.
- Skrót **„rys.” stosuje się tylko we wtrąceniu** w nawiasie, np. „Odpowiedź skokowa układu zamkniętego (rys. 4.7) charakteryzuje się przeregulowaniem 10 %”. Gdy odniesienie jest integralną częścią zdania, stosuje się pełną formę „rysunek”.
- **Brak sprawczości przedmiotów** — dotyczy też tabel, wykresów, elementów interfejsu: „Na wykresie przedstawiono…”, „W tabeli zestawiono…”, „Po kliknięciu przycisku wykonywane jest zdjęcie” (nie: „wykres pokazuje”, „przycisk wykonuje zdjęcie”).

---

## 8. Prawo autorskie i uczciwość akademicka

Należy móc wykazać, że praca jest własna, a każde cudze źródło, rysunek, dane i fragment kodu są wskazane i wykorzystane zgodnie z prawem. *Ten fragment nie jest poradą prawną; w wątpliwościach należy zwrócić się do promotora lub jednostki prawnej uczelni.*

### 8.1 Oświadczenie składane w Moja PG

Przed umieszczeniem pracy w Moja PG student oświadcza, że:

- jest świadomy odpowiedzialności karnej za naruszenie ustawy o prawie autorskim i prawach pokrewnych, konsekwencji dyscyplinarnych (ustawa Prawo o szkolnictwie wyższym i nauce) oraz odpowiedzialności cywilnoprawnej,
- praca została opracowana samodzielnie,
- praca nie była wcześniej podstawą innej urzędowej procedury związanej z nadaniem tytułu zawodowego,
- wszystkie informacje ze źródeł pisanych i elektronicznych zostały udokumentowane w wykazie literatury, zgodnie z art. 34 ustawy o prawie autorskim i prawach pokrewnych,
- deklaruje użycie narzędzi GenAI (osobna sekcja, patrz rozdział 9).

### 8.2 Zasady praktyczne

1. **Cytat a parafraza.** Prawo cytatu (art. 29 ustawy) pozwala przytoczyć urywki rozpowszechnionych utworów w zakresie uzasadnionym analizą, wyjaśnianiem lub nauczaniem, ze wskazaniem autora i źródła. Cytat ujmuje się w cudzysłów i podaje numer strony. Parafrazę pisze się własnymi słowami i też opatruje odnośnikiem; **zamiana kilku wyrazów nie jest parafrazą**.
2. **Tłumaczenia.** Przetłumaczony cudzy tekst wymaga takiego samego odnośnika jak oryginał i nadal może zostać wykryty w antyplagiacie.
3. **Rysunki, schematy, zdjęcia i wykresy z cudzych publikacji.** Umieszcza się je tylko wtedy, gdy zezwala na to licencja (np. Creative Commons), zgoda właściciela praw albo prawo cytatu, zawsze ze źródłem w podpisie. Bezpieczniej wykonać własną wersję.
4. **Licencje Creative Commons.** **BY** — wymóg wskazania autora; **SA** — udostępnianie na tych samych warunkach; **NC** — zakaz użycia komercyjnego; **ND** — zakaz tworzenia utworów zależnych. Warunki sprawdza się przed wykorzystaniem materiału.
5. **Oprogramowanie open source.** Licencję każdej użytej biblioteki warto zapisać (np. w `docs/third-party`). Licencje typu *copyleft* (np. GPL) mogą wymagać udostępnienia własnego kodu na tych samych warunkach; licencje permisywne (MIT, BSD, Apache 2.0) zwykle wymagają zachowania informacji o prawach autorskich.
6. **Zbiory danych, czcionki, ikony.** Źródło i licencję każdego zbioru danych zapisuje się; nie należy zakładać, że dane dostępne publicznie są wolne od ograniczeń. Czcionki i grafiki muszą mieć licencję obejmującą publikację pracy.
7. **Własny kod.** Licencję repozytorium wybiera się świadomie albo pozostawia repozytorium prywatne; repozytorium bez licencji nie daje innym prawa do swobodnego użycia kodu. **Szablon pracy nie może trafić do publicznego repozytorium.**
8. **Współpraca z firmą lub uczelnią zewnętrzną.** Przed rozpoczęciem prac należy ustalić **na piśmie**, kto ma prawa do wyników i kodu, czy wolno je publikować i czy praca będzie objęta klauzulą poufności. Ustne ustalenia nie wystarczają. Do narzędzi GenAI nie wolno wprowadzać danych poufnych ani wrażliwych.
9. **Praca zespołowa.** Każdy autor odpowiada za swoje części; spis treści pokazuje, kto co napisał.

---

## 9. Generatywna sztuczna inteligencja (GenAI)

> **Student ponosi pełną odpowiedzialność za poprawność merytoryczną tekstu, niezależnie od użytych narzędzi.**

### 9.1 Obowiązki

- **Student musi uzgodnić z promotorem możliwość korzystania z AI** oraz jej dopuszczalny zakres (podejście opiekunów może się znacząco różnić). Domyślnie zakłada się samodzielną redakcję treści pracy, przy minimalnym poziomie lub bez użycia narzędzi AI.
- **Jednym z załączników pracy jest lista użytego oprogramowania AI**, z wyszczególnieniem **konkretnych akapitów**, **udziału AI** oraz **wkładu własnego**.
- Po złożeniu pracy w Moja PG wymienia się sekcje, w których korzystano z AI, i opisuje stopień ingerencji narzędzia w finalną treść. W oświadczeniu wybiera się właściwą opcję dotyczącą GenAI; regulamin odsyła do pisma okólnego Rektora PG o narzędziach GenAI, które definiuje „niski" i „wysoki" stopień ingerencji. Przy wysokiej ingerencji wypełnia się tabelę (strony i narzędzia) i dodaje wpis w bibliografii.
- Do narzędzi GenAI **nie wolno wprowadzać danych wrażliwych**.
- Należy zachować pełną kontrolę nad zawartością i zweryfikować poprawność wszystkich informacji.

### 9.2 Przykłady użycia

| Niedopuszczalne | Dopuszczalne pomocniczo (po uzgodnieniu z promotorem) |
|---|---|
| ❌ generowanie całych porcji tekstu (zdań, akapitów, rozdziałów) | ✅ korekta stylistyczna i gramatyczna własnego tekstu z krytyczną analizą sugestii i ręcznym wdrożeniem |
| ❌ generowanie cytowań i opisów bibliograficznych | ✅ poszukiwanie potencjalnych źródeł (artykuł wskazany przez AI należy samodzielnie odnaleźć w wiarygodnym serwisie, np. IEEE, przeczytać i dopiero wtedy zacytować z oryginału) |
| ❌ generowanie grafik i ilustracji do pracy | ✅ wskazywanie niespójności w numeracji i odwołaniach, z ręczną korektą |
| | ✅ w plikach `.tex`: szablony tabel, ustawienia pozycjonowania grafik, elementy składni LaTeX-a |

**Dobra praktyka:** korekta językowa zdanie po zdaniu, z prośbą o pokazanie zdania przed korektą, po korekcie oraz krótki opis zmian i ich uzasadnienie. Jednorazowa korekta dużych bloków tekstu i bezrefleksyjne kopiowanie wyników prowadzi do zbyt głębokiej, słabo zweryfikowanej ingerencji.

### 9.3 Najczęstsze problemy

- nadmiernie rozbudowane opisy, zwiększające objętość bez wartości merytorycznej,
- błędy rzeczowe i informacje niezgodne ze źródłami,
- brak spójności między częściami pracy,
- pomijanie odwołań do rysunków, tabel, źródeł i innych rozdziałów,
- fragmenty oderwane od rzeczywistego kontekstu projektu,
- **fikcyjne odwołania do literatury** (źródła, które nie istnieją).

Wszelkie treści opracowywane z pomocą AI wymagają krytycznej analizy i starannej redakcji.

---

## 10. Zbiór uwag językowych

### 10.1 Styl i język

- Praca jest dokumentem formalnym: unikać skrótów myślowych, niedomówień, języka przesadnie „poetyckiego" i nieformalnego języka mówionego.
- Styl **bezosobowy**, bez pierwszej osoby liczby pojedynczej i mnogiej. Zamiast „Wydrukowaliśmy obudowę robota” → „Obudowa robota została wykonana w technologii druku 3D”. Z tekstu musi jednoznacznie wynikać, co wykonał autor, a co pochodzi z gotowych rozwiązań sprzętowych, programistycznych lub bibliotecznych.
- Jedno pojęcie oznacza się zawsze tym samym terminem. Poza terminami specjalistycznymi należy unikać powtórzeń w bliskim sąsiedztwie.
- **Czas teraźniejszy** dla praw przyrody, algorytmów i rozwiązań ogólnych; **czas przeszły** dla wykonanych działań (np. przebieg eksperymentów).
- Zdania proste są preferowane przy trudnościach składniowych; unikać długich zdań z wieloma wtrąceniami. Unikać niejednoznaczności (np. „Żmija ukąsiła Kleopatrę i umarła”).
- Akapit ma jedną myśl przewodnią. Należy używać sprawdzania pisowni. Korektę warto zlecić drugiej osobie, a pracę przeczytać na wydruku lub w innym układzie niż ten, w którym była pisana.

### 10.2 Drobne uwagi

| Zagadnienie | Zasada |
|---|---|
| **„ilość” / „liczba”** | „ilość” — wielkości niepoliczalne (ilość wody); „liczba” — policzalne (liczba wejść sterownika, liczba punktów pomiarowych). |
| **„stwarzać”** | Oznacza tworzenie z niczego. Zamiast tego: budować, wytwarzać, konstruować, projektować, tworzyć, opracowywać. |
| **Zdania od „Aby”** | Unikać. Zamiast „Aby zasilić urządzenie, należy…” → „W celu zasilenia urządzenia należy…”. |
| **„to”, „ten”, „tego”, „które”** | Nie nadużywać. „Paul jest to ramię robotyczne, które potrafi…” → „Paul jest ramieniem robotycznym potrafiącym…”. Zaimek „które” razi, gdy występuje co drugie–trzecie zdanie. |
| **„położenie” / „pozycja”** | „położenie” — miejsce w przestrzeni opisane współrzędnymi (położenie robota); „pozycja” — stan lub ułożenie (pozycja startowa, siedząca). Ważna konsekwencja w całej pracy. |
| **Precyzja liczb** | Liczba cyfr znaczących dostosowana do dokładności pomiaru. |
