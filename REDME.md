# Eksploracja i ocena modelu jezykowego (LLM)

---

## Czesc 1: Prompty i Odpowiedzi

W tej sekcji przedstawiam trzy rodzaje zapytan skierowanych do modelu oraz jego odpowiedzi.

### 1. Prompt Informacyjny (Informational)
**Cel:** Sprawdzenie zdolnosci modelu do wyjasniania faktów.

> **Mój Prompt:** > Opowiedz w kilku zdaniach jak działą fotosynteza u roślin.

**Odpowiedz Modelu:** Oto zwięzłe wyjaśnienie procesu fotosyntezy:

Fotosynteza to proces, w którym rośliny wytwarzają sobie pożywienie, zamieniając energię świetlną na energię chemiczną. Roślina pobiera **wodę** z gleby oraz **dwutlenek węgla** z powietrza, a następnie przy udziale **światła słonecznego** i zielonego barwnika – **chlorofilu** – przekształca te składniki w glukozę (cukier).

Kluczowym produktem ubocznym tego procesu jest **tlen**, który jest wydalany do atmosfery i umożliwia życie większości organizmów na Ziemi.

Można to zapisać w uproszczony sposób:

* **Wchodzi:** Światło słońca + Woda (H_2O) + Dwutlenek węgla (CO_2)
* **Wychodzi:** Glukoza (energia dla rośliny) + Tlen (O_2)

---

Czy chciałbyś, abym rozpisał dokładne równanie chemiczne tego procesu?

---

### 2. Prompt Kreatywny (Creative)
**Cel:** Sprawdzenie kreatywnosci i umiejetnosci narracyjnych.

> **Mój Prompt:** > napisz rymowaną recenzję najgorszego keba w mieście

**Odpowiedz Modelu:** Oto rymowana, nieco dramatyczna i przestrzegająca recenzja najgorszego kebaba, jaką mogłem sobie wyobrazić.

### 🌯 Ballada o Zemście Sultana (czyli Gastro-Koszmar)

Stoi w uliczce budka blaszana,
Szyld ledwo świeci, farba zdrapana.
W środku „Szef” kroi z miną mordercy,
To, co się kręci, nie ma już serca.

„Mieszany!” – krzyknąłem, głodem pchnięty,
Błąd to był srogi, błąd niepojęty.
Bułka, co tydzień leżała w cieple,
Dziś udawała, że trzyma się krzepko.

**A w środku... o zgrozo!**

Mięso? Zagadka, sekret natury,
Czy to był baran, czy może szczury?
Szare, zmielone, wióry pakuły,
Czułem jak w ustach rosną mi buły.
Chrząstka za chrząstką ząb atakuje,
A „Szef” się patrzy i nie żałuje.

Kapusta smutna, zwiędła i blada,
Chyba zeszłego pamięta sąsiada.
Ogórek kiszony? Nie, to pomyłka,
Miękki jak gąbka, kwaśny jak zsyłka.

**Finał dramatu**

Sos miał być „ostry”, a był tylko słony,
Czosnkowy zaś wodą był rozcieńczony.
Na koniec wszystko spłynęło dołem,
Bułka się stała mokrym żywiołem.

Zjadłem trzy kęsy, resztę rzuciłem,
I o swe życie się zaniepokoiłem.
Teraz w domowym zaciszu siedzę,
I toaletę pilnie odwiedziedzam.

---

**Werdykt:**
Nie idź tam, bracie! Nie idź tam, siostro!
Bo chociaż w nazwie mają, że „ostro”,
To jedyne co ostre w tej budzie się chowa,
To ból żołądka i jazda... jelitowa.

Czy chciałbyś, abym napisał teraz **krótką, złośliwą opinię w formie jednego zdania**, którą można by wstawić w Mapy Google?

---

### 3. Prompt Analityczny (Analytical/Problem-solving)
**Cel:** Sprawdzenie umiejetnosci logicznego myslenia i porównywania danych.

> **Mój Prompt:** > Porównaj samochody elektryczne i spalinowe pod kątem kosztów eksploatacji w Polsce. Uwzględniając ceny paliwa/prądu, serwis i utratę wartości. Krótka forma

**Odpowiedz Modelu:** Oto porównanie kosztów eksploatacji samochodów elektrycznych (BEV) i spalinowych (ICE) w Polsce (dane na rok 2024/2025).

### 1. Koszt „paliwa” na 100 km

To największa zmienna. Samochód elektryczny jest bezkonkurencyjny **tylko jeśli ładujesz go w domu**. Na szybkich ładowarkach publicznych koszty zrównują się z autem spalinowym.

| Typ napędu / Ładowanie | Koszt przejechania 100 km (ok.) | Uwagi |
| --- | --- | --- |
| **Elektryk (Dom + PV)** | **0 – 8 zł** | Własna fotowoltaika to jazda prawie za darmo. |
| **Elektryk (Dom - taryfa nocna)** | **15 – 20 zł** | Ładowanie w taryfach G12/G12w. |
| **Auto na Gaz (LPG)** | **22 – 28 zł** | Obecnie „król taniej jazdy” wśród aut spalinowych. |
| **Diesel / Benzyna** | **40 – 60 zł** | Przy spalaniu 6-8l/100km i cenie paliwa ~6,50 zł. |
| **Elektryk (Szybkie ładowarki DC)** | **45 – 70 zł** | Ładowanie na trasie (Greenway, Ionity) bez abonamentu jest drogie. |

### 2. Serwis i eksploatacja

Tutaj zdecydowanie **wygrywa samochód elektryczny**.

* **Mniej części:** W elektryku nie wymieniasz oleju silnikowego, filtrów paliwa, świec, pasków rozrządu ani sprzęgła.
* **Hamulce:** Dzięki rekuperacji (hamowaniu silnikiem) klocki i tarcze w elektryku zużywają się nawet 2-3 razy wolniej.
* **Koszty:** Przeglądy okresowe elektryków są zazwyczaj o **30-50% tańsze** niż aut spalinowych.

### 3. Utrata wartości (Deprecjacja)

To największy „ukryty” koszt, który obecnie działa na **niekorzyść elektryków**.

* **Elektryki:** Tracą na wartości szybciej (nawet 45-50% w 3 lata). Wynika to z obaw o żywotność baterii, szybkiego postępu technologii oraz wojen cenowych (np. obniżki Tesli, które pociągnęły rynek w dół).
* **Spalinowe:** Trzymają cenę stabilniej, jest na nie wciąż ogromny popyt na rynku wtórnym w Polsce.
* *Uwaga:* Program „Mój Elektryk” (dotacje do 27 000 zł) realnie obniża cenę zakupu, co nieco łagodzi ból przy odsprzedaży.

### Werdykt

* **Wybierz Elektryka, jeśli:** Masz dom z gniazdkiem/fotowoltaiką, jeździsz dużo po mieście i okolicach (nadrabiasz tańszą eksploatacją) oraz planujesz trzymać auto dłużej niż 3-4 lata.
* **Wybierz Spalinowe (lub Hybrydę), jeśli:** Mieszkasz w bloku bez ładowarki, robisz głównie długie trasy autostradowe lub zmieniasz auta co 2-3 lata (mniejsza utrata wartości).

---

**Co mogę dla Ciebie zrobić dalej?**
Mogę przeliczyć **Całkowity Koszt Posiadania (TCO)** dla konkretnych dwóch modeli, które rozważasz (np. Tesla Model 3 vs BMW Serii 3) przy Twoim rocznym przebiegu. Chcesz?

## Czesc 2: Ewaluacja i Analiza

### Analiza wyników 

Który prompt model obsłużył najlepiej i dlaczego? Model zdecydowanie najlepiej poradził sobie z Promptem Analitycznym (nr 3). Odpowiedź wyróżniała się świetną strukturą (tabela, wypunktowania) oraz głębokim zrozumieniem lokalnego kontekstu (polskie ceny prądu, specyfika taryf nocnych, realia rynku LPG). Zamiast udzielić prostej, binarnej odpowiedzi, model zaprezentował zniuansowane podejście "to zależy", co jest cechą zaawansowanego wnioskowania. Formatowanie odpowiedzi sprawiło, że skomplikowane dane stały się czytelne na pierwszy rzut oka.

Niedokładności, stronniczość i niespodziewane zachowania W odpowiedziach nie odnotowano rażących błędów merytorycznych, jednak w sekcji analitycznej model posłużył się konkretnymi kwotami (np. ceny paliwa/kWh). Jest to zachowanie ryzykowne, ponieważ te dane są bardzo zmienne i szybko się dezaktualizują (tzw. problem static data). Niespodziewanie pozytywnym aspektem była wysoka jakość odpowiedzi kreatywnej (wiersz o kebabie) – model poprawnie dobrał rymy i zachował rytm w języku polskim, co często sprawia trudność systemom AI trenowanym głównie na języku angielskim.

Użyteczność w świecie rzeczywistym Potencjał LLM jest widoczny w każdej z badanych dziedzin:

Edukacja: Model świetnie sprawdza się jako "tłumacz" trudnych pojęć na prosty język (przykład fotosyntezy), działając jak spersonalizowany korepetytor.

Biznes: Możliwość szybkiego zestawiania danych i tworzenia tabel (przykład samochodów) drastycznie skraca czas potrzebny na research i przygotowanie raportów.

Praca kreatywna: Model może służyć jako narzędzie do przełamywania blokady twórczej, generując szkice tekstów czy scenariusze reklamowe.

Ryzyka i kwestie etyczne Głównym ryzykiem jest zjawisko halucynacji – model brzmi bardzo pewnie, nawet gdyby podawał błędne dane. W przypadku promptu analitycznego istnieje ryzyko, że użytkownik potraktuje wyliczenia kosztów jako pewną poradę finansową, nie weryfikując ich ze stanem faktycznym. W zadaniach kreatywnych istnieje też ryzyko powielania stereotypów, choć w tym przypadku (recenzja kebaba) model zachował bezpieczny, humorystyczny dystans.
