# HackYeah2024

# Great Profit for Social: Platforma Wspierająca Współpracę Biznesu z Fundacjami

## Opis projektu

Współpraca firm z fundacjami i projektami społecznymi przynosi korzyści zarówno dla biznesu, jak i dla społeczności. Platforma **Great Profit for Social** ma na celu połączenie firm z organizacjami społecznymi poprzez inteligentne dopasowanie projektów, które pozwolą firmom na budowanie silnej marki oraz uzyskanie korzyści biznesowych, takich jak obniżenie podatków czy wzmocnienie zaangażowania pracowników.

## Korzyści dla biznesu

- **Budowanie marki**: Zaangażowanie w projekty społeczne wzmacnia wizerunek firmy, co przekłada się na większe zaufanie klientów, inwestorów oraz partnerów.
- **Korzyści finansowe**: Wspieranie projektów społecznych może przynieść biznesowi ulgę podatkową oraz inne korzyści, wynikające z lokalnych i międzynarodowych regulacji promujących działalność społeczną.

## Funkcjonalności platformy

1. **Rejestracja fundacji** i tworzenie projektu społecznego.
2. **Rejestracja firm** i wybór obszarów działania społecznego, w które chcą się zaangażować.
3. **Algorytm dopasowujący**: Dzięki technologii ElasticSearch oraz AI, firmy mogą otrzymać listę najlepiej dopasowanych projektów społecznych.
4. **Automatyczne sugestie**: AI pomaga firmom określić, w jaki sposób mogą najlepiej wesprzeć wybrany projekt, analizując ich cele i profil działalności.
5. **Posty i raporty**: Organizatorzy projektów mogą tworzyć posty i raporty z realizacji działań, wspierane przez AI, które automatycznie generuje treści podsumowujące wkład firmy.
6. **Roczne raporty**: AI przygotowuje interaktywny, coroczny raport podsumowujący działania firmy w projektach społecznych.

## Algorytm dopasowujący

Algorytm opiera się na analizie słów kluczowych z opisów projektów i działalności firm. Uwzględnia on ranking projektów i firm oraz bieżące potrzeby społeczne, sortując i dopasowując projekty według wspólnych słów kluczowych, aktualności oraz oceny. Dzięki temu nawet nowe projekty mają szansę na zaangażowanie ze strony firm.

## Zarządzanie działaniami

Dla każdego projektu, AI generuje listę sugerowanych działań, które firma może podjąć, bazując na jej dotychczasowym zaangażowaniu i możliwościach. Przykłady obejmują organizowanie warsztatów, wsparcie finansowe, czy wolontariat pracowników.


## Dlaczego Great Profit for Social?

- Automatyczne raportowanie i posty, bez potrzeby dodatkowej pracy ze strony firmy.
- Inteligentne dopasowanie projektów społecznych do celów biznesowych.
- Budowanie silnej marki oraz uzyskanie korzyści finansowych dzięki zaangażowaniu społecznemu.

Platforma **Great Profit for Social** łączy świat biznesu z potrzebami społeczeństwa, umożliwiając firmom nie tylko wspieranie wartościowych inicjatyw, ale także budowanie długotrwałego wizerunku i zysków.

# Jak uruchomić aplikację.

## Instalacja pliku `gpfs.json` na platformę Platma

Aby zaimportować plik konfiguracyjny `gpfs.json` na platformę **Platma**, wykonaj poniższe kroki:

### 1. Pobierz plik `gpfs.json`
Najpierw upewnij się, że masz pobrany plik `gpfs.json` z odpowiedniego źródła. Plik powinien zawierać niezbędne dane do konfiguracji i importu na platformie.

### 2. Zaloguj się na platformę Platma
1. Wejdź na stronę logowania platformy **Platma**.
2. Zaloguj się, używając swoich poświadczeń (login i hasło). Upewnij się, że masz odpowiednie uprawnienia do importowania plików konfiguracyjnych.

### 3. Przejdź do sekcji Workspace
1. Po zalogowaniu, w panelu głównym, znajdź i wybierz opcję **Workspace** następnie **My Apps**.
2. Wybierz opcję **Create new App**

### 4. Wybierz plik `gpfs.json` do importu
1. Kliknij przycisk **Przeglądaj** (lub **Wybierz plik**) i przejdź do lokalizacji, w której znajduje się pobrany wcześniej plik `gpfs.json`.
2. Wybierz plik i kliknij **Create app**.

### 5. Weryfikacja
1. Po zakończeniu importu, platforma powinna wyświetlić komunikat o pomyślnym zakończeniu operacji.
2. Możesz teraz przejść do odpowiedniej sekcji platformy, aby zweryfikować, czy dane z pliku zostały poprawnie zaimportowane i są aktywne.

### 6. Dalsza konfiguracja (opcjonalnie)
W niektórych przypadkach może być konieczna dalsza konfiguracja zaimportowanych danych. W zależności od specyfiki platformy **Platma**, przejdź do odpowiednich ustawień i dostosuj opcje konfiguracyjne zgodnie z potrzebami projektu.

---

### Uwagi:
- Upewnij się, że plik `gpfs.json` jest zgodny z formatem akceptowanym przez platformę **Platma**.
- W razie problemów z importem, skontaktuj się z administratorem platformy lub sprawdź dokumentację w sekcji **Pomoc**.


# 28 wrz 2024 | HackYeah 2024

## Uczestnicy:
- **Michał Szczygieł**  
  e-mail: [michal.szczygiel@wp.pl](mailto:michal.szczygiel@wp.pl)  
  tel: 508 936 231  
  [LinkedIn](https://www.linkedin.com/in/michal-szczygiel)

- **Tetiana Klimenko**  
  e-mail: [klimenko.tetiana3@gmail.com](mailto:klimenko.tetiana3@gmail.com)  
  tel: 788 202 134  
  [LinkedIn](https://www.linkedin.com/in/tetiana-klimenko/)

- **Paweł Primus**  
  e-mail: [pawelprimus@gmail.com](mailto:pawelprimus@gmail.com)  
  tel: 502 299 750  
  [LinkedIn](https://www.linkedin.com/in/pawel-primus/)

---

# Dokument techniczno-naukowy

## 1. Opis projektu i jego ważność

### Tytuł: Łączenie firm i fundacji dla wspólnych celów społecznych

### Opis:
Nasz projekt ma na celu stworzenie platformy łączącej firmy i fundacje działające na rzecz społeczności. Celem jest umożliwienie współpracy pomiędzy firmami a organizacjami non-profit poprzez wspólne realizowanie projektów społecznych.

### Problem:
Wiele fundacji, szczególnie w mniejszych miejscowościach, boryka się z ograniczeniami finansowymi i kadrowymi. Przykładem jest projekt Caritas, organizujący lekcje STEM dla dzieci z wiejskich szkół. Mimo szlachetnych intencji, brakuje im sprzętu i specjalistów do prowadzenia zajęć.

### Rozwiązanie:
Nasza platforma umożliwia firmom wsparcie takich inicjatyw, oferując zasoby materialne, finansowe, a także pomoc wolontariuszy. Firmy mogą udostępniać sprzęt, finanse oraz logistyczne wsparcie, aby wspomagać realizację projektów społecznych.

---

## 2. Uczestnicy procesu

### Tytuł: Kto bierze udział?

### Opis:
W projekcie uczestniczą trzy główne strony:

- **Fundacje**: Zakładają projekty społeczne, takie jak Caritas z projektem „Nauka STEM dla dzieci z wiosek”.
- **Firmy**: Rejestrują się na platformie, deklarując, jakie wsparcie mogą oferować (finansowe, logistyczne, wolontariackie).
- **Wolontariusze**: Pracownicy firm lub osoby spoza organizacji, które pomagają w realizacji projektów, np. prowadzą lekcje.

Platforma automatycznie łączy te grupy, umożliwiając firmom wspieranie projektów pasujących do ich profilu działalności i celów społecznych.

---

## 3. Korzyści dla biznesu

### Tytuł: Jakie korzyści z tego mają firmy?

### Opis:
Firmy zaangażowane w projekty społeczne zyskują liczne korzyści, w tym:

- **Budowanie marki**: Działania społeczne budują rozpoznawalność i pozytywny wizerunek firmy, co wpływa na zwiększenie zaufania klientów i partnerów biznesowych.
- **Korzyści podatkowe**: Firmy mogą uzyskać ulgi podatkowe za działalność charytatywną i społeczną.
- **Zwiększenie zaangażowania pracowników**: Pracownicy chętniej angażują się w projekty społeczne, co wpływa na ich lojalność wobec firmy.
- **Raporty ESG**: Platforma automatycznie generuje raporty zgodne z wymogami ESG, co ułatwia firmom raportowanie ich działań społecznych.

---

## 4. Instrukcja krok po kroku

### Tytuł: Jak działa nasza platforma?

### Opis:
1. Fundacja rejestruje się na platformie i tworzy projekt, np. lekcje STEM.
2. Firma rejestruje się, określając rodzaje wsparcia, jakie może oferować.
3. Algorytm dopasowuje firmę do projektów na podstawie słów kluczowych i preferencji.
4. Firma przegląda dostępne projekty i otrzymuje rekomendacje działań oraz wynikających z nich korzyści.
5. Firma i fundacja rozpoczynają współpracę po dopasowaniu.
6. Fundacja tworzy raport, a platforma automatycznie generuje posty i zdjęcia z wydarzeń.
7. Firma otrzymuje roczny raport o swoich działaniach społecznych, generowany przez AI.

---

## 5. Ułatwienia dla firm i fundacji

### Tytuł: Jak platforma wspiera zaangażowanie firm?

### Opis:
Platforma oferuje szereg funkcji automatyzujących procesy współpracy między firmami a fundacjami:

- **Automatyczne generowanie raportów**: Platforma automatycznie przygotowuje raporty ESG, uwalniając firmy od potrzeby samodzielnego ich tworzenia.
- **Rekomendacje projektów**: Algorytm analizuje projekty i dopasowuje je do profilu firmy, co ułatwia wybór projektów społecznych.
- **Automatyczne posty**: Fundacje mogą łatwo generować posty po zakończeniu działań, dzięki czemu firma może szybko publikować materiały promocyjne.

---

## 6. Algorytm do matchowania

### Tytuł: Jak działa algorytm dopasowujący?

### Opis:
Algorytm dobiera projekty do firm na podstawie słów kluczowych z projektów i oferty firm. Wartości projektów są wyznaczane na podstawie rankingu fundacji, pilności potrzeby w danym obszarze oraz liczby zrealizowanych projektów.

Przykład:  
Dla projektu STEM - 28.09, ranking fundacji wynosi 3.500, ranking obszaru 4.500, a liczba zrealizowanych projektów to 3. Dla firmy rankingi są obliczane na podobnych zasadach. Algorytm dopasowuje firmy do projektów według słów kluczowych, aktualności i wartości rankingowej.

---

## 7. Oferta dla biznesu

### Tytuł: Co firmy mogą zyskać?

### Opis:
Po przygotowaniu listy dostępnych projektów, system tworzy propozycje działań, które firmy mogą podjąć. AI analizuje historię działań firmy, tworząc rekomendacje, które uwzględniają wcześniejsze doświadczenia firmy w danym obszarze. Propozycje obejmują korzyści niefinansowe i finansowe.

---

## 8. Historia sukcesu firmy

### Tytuł: Jak SocialAspect pomógł firmie X?

### Opis:
Firma X dołączyła do platformy SocialAspect, angażując się w projekt wspierający naukę STEM w wiejskich szkołach. Pracownicy firmy prowadzili lekcje oraz zainwestowali w sprzęt komputerowy dla uczniów. Dzięki temu pracownicy rozwijali swoje umiejętności, a firma zwiększyła swoją rozpoznawalność, pozyskała nowych inwestorów i obniżyła koszty podatkowe. Na koniec roku firma otrzymała gotowy, interaktywny raport o swojej działalności społecznej.

---

## Certyfikacja

### Tytuł: Rola certyfikacji w Great Profit for Social

W ramach platformy **Great Profit for Social**, certyfikacja odgrywa kluczową rolę w zapewnianiu wiarygodności i rzetelności działań społecznych realizowanych przez firmy i organizacje non-profit (NGO). Proces certyfikacji jest zgodny z wytycznymi dyrektywy **ESG** (Environmental, Social, Governance), ze szczególnym naciskiem na filar "S" — odpowiedzialność społeczną.

### Jak działa certyfikacja?

Firmy angażujące się w projekty społeczne we współpracy z fundacjami na platformie mogą zdobyć certyfikaty potwierdzające ich zaangażowanie i sukcesy w realizacji celów ESG.

Certyfikaty mogą być przyznawane w różnych kategoriach, np. za:
- Długoterminowe zaangażowanie w projekty społeczne,
- Wsparcie edukacyjne (np. STEM),
- Inwestycje w rozwój lokalnych społeczności.

### Certyfikacja NGO

Fundacje realizujące projekty na platformie również mogą zdobywać certyfikaty, co zwiększa ich wiarygodność i szanse na współpracę z firmami.

---

### Znaczenie certyfikacji w procesie matchowania

Certyfikowane firmy i fundacje będą preferowane w algorytmie dopasowywania, co zwiększa szanse na sukces projektu.

---

### Podsumowanie korzyści z certyfikacji

- **Dla firm**: Zwiększenie wiarygodności i wzmocnienie marki, potwierdzenie zaangażowania w działania ESG.
- **Dla NGO**: Lepsza widoczność i wyższa pozycja w procesie matchowania, co ułatwia pozyskiwanie partnerów biznesowych.
- **Dla społeczności**: Większa przejrzystość działań firm i fundacji, co prowadzi do bardziej skutecznych i wartościowych inicjatyw społecznych.

### Certyfikacja w Great Profit for Social

Certyfikacja w platformie **Great Profit for Social** nie tylko wzmacnia wiarygodność organizacji zaangażowanych w działania społeczne, ale także pozwala firmom wyróżnić się na tle konkurencji poprzez rzeczywiste zaangażowanie w rozwój społeczny.

Proces certyfikacji bazuje na generowanych przez platformę raportach, które są automatycznie tworzone przy wsparciu sztucznej inteligencji (AI). To zautomatyzowane podejście pozwala na bezstronną i obiektywną ocenę działań firm oraz fundacji, eliminując subiektywność w ocenie.

## Kluczowe aspekty certyfikacji

- **Rzetelność i zgodność**: Certyfikacja opiera się na szczegółowej weryfikacji realizacji założeń projektów. Firmy muszą dostarczać raporty dotyczące postępów i osiągnięć w ramach działań społecznych, a także udowodnić ich zgodność z celami ESG.
- **Raportowanie i automatyczna weryfikacja**: Generowane raporty są podstawą dla oceny działań zarówno firm, jak i fundacji, co zapewnia transparentność i wiarygodność całego procesu certyfikacji.
- **Różne kategorie certyfikatów**: Certyfikaty mogą być przyznawane za różne rodzaje zaangażowania, w tym:
  - Długoterminowe zaangażowanie w projekty społeczne,
  - Wsparcie dla edukacji (np. projekty STEM),
  - Inwestycje w lokalne społeczności.
- **Preferencje w algorytmie**: Firmy i NGO, które uzyskają certyfikaty, będą preferowane w procesie dopasowywania partnerów na platformie, co zwiększy ich szanse na sukces projektu.

### Certyfikacja NGO

Organizacje non-profit (NGO) mogą także zdobywać certyfikaty za swoje projekty. Fundacje z większą liczbą certyfikatów zyskują większą widoczność na platformie i priorytet w procesie matchowania z firmami. Zwiększa to ich szanse na pozyskanie wartościowych partnerów biznesowych.

## Znaczenie certyfikacji dla biznesu i społeczeństwa

Certyfikaty ESG zdobyte przez firmy i NGO na platformie **Great Profit for Social** wpływają na poprawę ich wizerunku, budując większe zaufanie społeczne oraz wzmacniając ich pozycję rynkową. Jednocześnie, społeczeństwo zyskuje na przejrzystości działań, co skutkuje bardziej wartościowymi i efektywnymi inicjatywami społecznymi.

---

**Great Profit for Social** dostarcza narzędzi, które łączą firmy z fundacjami, wspierając ich współpracę w realizacji wspólnych celów społecznych. Proces certyfikacji, raportowanie ESG oraz wsparcie AI tworzą zautomatyzowane i przejrzyste rozwiązanie dla firm, które chcą wzmocnić swoją markę i zaangażowanie społeczne, przyczyniając się do rzeczywistego wpływu na rozwój lokalnych społeczności.