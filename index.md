---
title: Polityka prywatności – Szczytownik
lang: pl
---

# Polityka prywatności aplikacji Szczytownik

**[Polityka prywatności](./)** · [Regulamin](./terms)

---

**Wersja dokumentu:** 1.0.2  
**Data wejścia w życie:** 28 października 2026 r.  
**Wersja aplikacji, której dotyczy:** 1.0.0 i nowsze (do czasu wydania kolejnej wersji niniejszej polityki)

---

## 1. Administrator danych

Administratorem danych osobowych w rozumieniu Rozporządzenia Parlamentu Europejskiego i Rady (UE) 2016/679 z dnia 27 kwietnia 2016 r. (dalej „**RODO**") jest:

**Mateusz Smęt**  
osoba fizyczna, autor i wydawca aplikacji Szczytownik (dalej „**Aplikacja**").  
Kontakt: **matt.the.peak.coder@gmail.com**

Aplikacja jest projektem niekomercyjnym, prowadzonym hobbystycznie. Administrator nie powołał Inspektora Ochrony Danych - z wszelkimi sprawami dotyczącymi danych prosimy kontaktować się bezpośrednio na powyższy adres e-mail.

---

## 2. Najważniejsze informacje w skrócie

- Aplikacja działa **lokalnie na Twoim urządzeniu**. Nie posiada serwera ani konta użytkownika.
- Lokalizacja GPS, zdjęcia i wszystkie wspomnienia są przechowywane wyłącznie w pamięci Twojego telefonu.
- Administrator **nie otrzymuje** Twojej lokalizacji, zdjęć ani wspomnień i nie ma do nich dostępu.
- Aplikacja nie zawiera reklam, nie korzysta z zewnętrznych narzędzi analitycznych ani raportowania awarii i nie sprzedaje danych.
- Podczas wyświetlania mapy Aplikacja pobiera kafelki mapy z serwerów zewnętrznych dostawców. Dostawcy ci widzą wtedy Twój adres IP oraz fragment mapy, który oglądasz (szczegóły w sekcji 4).
- Możesz w każdej chwili usunąć wszystkie dane, odinstalowując Aplikację lub czyszcząc jej dane w ustawieniach systemu Android (Ustawienia > Aplikacje > Szczytownik > Pamięć > Wyczyść dane).
- Jeżeli zdecydujesz się wysłać zgłoszenie błędu (przycisk „Zgłoś błąd"), wiadomość trafia bezpośrednio do Administratora przez Twojego własnego klienta pocztowego. To Ty decydujesz, jakie informacje załączysz.

---

## 3. Jakie dane przetwarza Aplikacja

### 3.1. Dane lokalizacyjne (GPS)

- **Co:** szerokość i długość geograficzna, wysokość n.p.m., dokładność pomiaru, znacznik czasu.
- **Kiedy:** wyłącznie wtedy, gdy Aplikacja jest aktywna i korzysta z funkcji wymagającej lokalizacji (ekran kamery, ekran startowy, mapa, kompas, weryfikacja punktu). Aplikacja nie śledzi lokalizacji w tle.
- **Cel:** weryfikacja, czy znajdujesz się w pobliżu punktu zainteresowania (POI), wskazywanie kierunku do punktu oraz wyświetlanie aktualnej pozycji na mapie.
- **Gdzie trafia:** wyłącznie do lokalnej bazy SQLite na Twoim urządzeniu, jako część rekordu wspomnienia. Współrzędne nie są wysyłane do Administratora.
- **Podstawa prawna:** art. 6 ust. 1 lit. a) RODO (Twoja zgoda) oraz art. 6 ust. 1 lit. b) RODO (niezbędność do wykonania funkcji Aplikacji, z której korzystasz).

### 3.2. Zdjęcia

- **Co:** zdjęcia robione przez Ciebie w Aplikacji oraz zdjęcia importowane z galerii lub udostępniane do Aplikacji z innych programów. Pliki zdjęciowe mogą zawierać metadane EXIF (w tym datę, model aparatu i - jeżeli włączyłeś tę funkcję w systemie - lokalizację GPS).
- **Gdzie trafia:** Aplikacja zapisuje własną kopię zdjęcia w swojej prywatnej pamięci na lokalnym urządzeniu. Niezależnie od niej, Aplikacja może zapisać dodatkową kopię w galerii systemowej; ta opcja jest domyślnie włączona i możesz ją wyłączyć w ustawieniach Aplikacji. Kopia w galerii wymaga odpowiedniego uprawnienia systemowego.
- **Udostępnianie:** zdjęcie udostępniane z Aplikacji jest przekazaniem do wybranej przez Ciebie aplikacji wraz z jego metadanymi (w tym pozycją GPS, gdzie zostało zrobione), o ile takie istnieją.
- **Podstawa prawna:** art. 6 ust. 1 lit. b) RODO (wykonanie funkcji Aplikacji).

### 3.3. Ustawienia użytkownika

- Preferencje związane z dokładnością GPS, czasem auto-zapisu, językiem, akceptacją niniejszej polityki itp.
- Przechowywane lokalnie w bazie SQLite Aplikacji.

### 3.4. Kopia zapasowa i udostępnianie

- Aplikacja nie korzysta z automatycznej kopii zapasowej Androida/Google. Dane Aplikacji nie są automatycznie zapisywane przez Google w kopii systemowej.
- Funkcja „Eksportuj dane" tworzy plik kopii zapasowej (.pcbackup) na Twoim urządzeniu. Możesz dołączyć do niego zdjęcia albo wybrać eksport samych danych. Kopia bez zdjęć nie pozwala odzyskać plików zdjęciowych. Plik backupu nie jest szyfrowany.
- Po utworzeniu kopii Aplikacja otwiera systemowe okno udostępniania. To Ty decydujesz, czy, gdzie i komu plik zostanie przekazany (np. do chmury, komunikatora lub e-maila).
- Po przekazaniu pliku poza Aplikację Administrator nie ma wpływu na jego dalsze przetwarzanie - odpowiada za nie wybrana przez Ciebie usługa.
- Funkcja „Importuj backup" odczytuje wskazany przez Ciebie plik wyłącznie lokalnie.

### 3.5. Dane techniczne (diagnostyka)

W bieżącej wersji Aplikacja **nie korzysta** z żadnego zewnętrznego systemu raportowania błędów (np. Sentry). Dzienniki techniczne pozostają na Twoim urządzeniu i nie są nigdzie wysyłane bez Twojej wiedzy.

Zgłoszenie błędu otwiera Twój klient pocztowy z wiadomością zawierającą wersję Aplikacji, system operacyjny i wersję systemu. Możesz tę treść zmienić lub usunąć przed wysłaniem.

W przyszłych wersjach Aplikacja może wprowadzić dobrowolne raportowanie awarii. Każda taka zmiana będzie poprzedzona aktualizacją niniejszej polityki oraz prośbą o ponowną zgodę.

---

## 4. Mapy i połączenia sieciowe

Dane o punktach zainteresowania (szczyty, schroniska, jeziora itp.) są zapisane w Aplikacji i nie wymagają internetu. Podkład mapy jest natomiast pobierany z internetu w postaci kafelków (małych obrazów) z serwerów zewnętrznych dostawców:

- **OpenStreetMap** - mapa podstawowa (infrastruktura OpenStreetMap Foundation),
- **Freemap Slovakia** - mapa turystyczna,
- **Waymarked Trails** - nakładka ze szlakami pieszymi.

Przy każdym pobraniu kafelka dostawca otrzymuje w sposób nieunikniony dla działania internetu: **Twój adres IP**, informacje techniczne o urządzeniu oraz **współrzędne kafelka**, czyli przybliżony obszar mapy, który w danej chwili oglądasz. Gdy mapa jest wyśrodkowana na Twojej pozycji, obszar ten odpowiada Twojej przybliżonej lokalizacji. Aplikacja nie przekazuje dostawcom Twoich dokładnych współrzędnych GPS, imienia, adresu e-mail, zdjęć ani zapisanych wspomnień.

- Dostawcy map są odrębnymi administratorami danych i przetwarzają te informacje na podstawie własnych polityk prywatności. Administrator Aplikacji nie otrzymuje tych danych.
- Polityka OpenStreetMap Foundation: https://osmfoundation.org/wiki/Privacy_Policy
- Dane mogą być przetwarzane przez dostawców lub ich operatorów infrastruktury poza Europejskim Obszarem Gospodarczym.
- Jeżeli nie chcesz łączyć się z serwerami map, nie otwieraj widoków z mapą - pozostałe funkcje działają bez internetu.

---

## 5. Uprawnienia systemowe

Aplikacja prosi o następujące uprawnienia, a każde z nich możesz odebrać w ustawieniach systemu w dowolnym momencie:

- **Lokalizacja** - weryfikacja pozycji względem punktów oraz pokazywanie Cię na mapie,
- **Aparat** - robienie zdjęć szczytów, schronisk i jezior,
- **Zdjęcia i multimedia (w tym lokalizacja zapisana w zdjęciach)** - import zdjęć z galerii oraz opcjonalny zapis dodatkowej kopii do galerii. Własna kopia Aplikacji jest przechowywana oddzielnie.

Aplikacja nie korzysta z mikrofonu, kontaktów, kalendarza, wiadomości ani lokalizacji w tle.

---

## 6. Komu udostępniamy dane

Administrator **nie sprzedaje** i **nie udostępnia** danych osobowych osobom trzecim w sposób automatyczny.

Następujące podmioty mogą uzyskać dostęp do wybranych danych w sytuacjach opisanych poniżej:

- **Dostawcy map** - adres IP i współrzędne kafelków mapy, zgodnie z sekcją 4.
- **Wybrana przez Ciebie aplikacja nawigacyjna** (np. Mapy Google) - nazwa i współrzędne punktu docelowego, wyłącznie wtedy, gdy użyjesz przycisku nawigacji do punktu.
- **Google Play (Google Ireland Ltd.)** - identyfikator instalacji oraz statystyki anonimowe, w zakresie, w jakim Google jako dystrybutor sklepu zbiera takie dane od wszystkich aplikacji.
- **Twój klient e-mail** - treść zgłoszenia błędu, wyłącznie wtedy, gdy świadomie wyślesz zgłoszenie z Aplikacji.
- **Usługa wybrana przez Ciebie do udostępnienia kopii zapasowej** - wyłącznie wtedy, gdy sam przekażesz jej plik.

Aplikacja w obecnej wersji nie zawiera bibliotek reklamowych ani analitycznych firm trzecich.

---

## 7. Okres przechowywania

- Dane lokalne (wspomnienia, zdjęcia, ustawienia) są przechowywane do momentu, w którym je usuniesz lub odinstalujesz Aplikację. Zdjęcia zapisane w galerii systemowej oraz wyeksportowane pliki kopii zapasowej pozostają na urządzeniu także po odinstalowaniu Aplikacji - możesz je usunąć samodzielnie.
- Wiadomości e-mail wysłane do Administratora przechowywane są przez okres niezbędny do udzielenia odpowiedzi i obsługi sprawy, nie dłużej niż 12 miesięcy.

---

## 8. Twoje prawa

Zgodnie z RODO masz prawo do:

1. **dostępu** do swoich danych - wszystkie dane masz fizycznie na swoim urządzeniu;
2. **sprostowania** danych - możesz edytować lub usunąć każde wspomnienie w Aplikacji;
3. **usunięcia** („prawo do bycia zapomnianym") - odinstalowanie Aplikacji lub wyczyszczenie jej danych w ustawieniach systemu Android trwale usuwa wszystkie dane; pojedyncze wspomnienia możesz usunąć w Aplikacji;
4. **ograniczenia** przetwarzania;
5. **przenoszenia** danych - funkcja „Eksportuj dane" zapisuje Twoje wspomnienia w ustrukturyzowanym formacie nadającym się do odczytu maszynowego (archiwum ZIP z plikami JSON i zdjęciami);
6. **sprzeciwu** wobec przetwarzania;
7. **cofnięcia zgody** w dowolnym momencie, bez wpływu na zgodność z prawem przetwarzania dokonanego przed jej cofnięciem;
8. **wniesienia skargi** do organu nadzorczego - w Polsce jest nim Prezes Urzędu Ochrony Danych Osobowych, ul. Stawki 2, 00-193 Warszawa (https://uodo.gov.pl).

W każdej sprawie dotyczącej danych możesz napisać na: **matt.the.peak.coder@gmail.com**. Administrator odpowie bez zbędnej zwłoki, nie później niż w ciągu miesiąca od otrzymania żądania.

Podanie danych jest dobrowolne. Odmowa udzielenia uprawnień systemowych może ograniczyć działanie powiązanych z nimi funkcji (np. weryfikacji punktu), ale nie uniemożliwia korzystania z pozostałych części Aplikacji. Administrator nie podejmuje wobec Ciebie zautomatyzowanych decyzji ani nie profiluje użytkowników.

---

## 9. Bezpieczeństwo danych

- Aplikacja przechowuje dane wyłącznie w obrębie sandboksa systemu Android, niedostępnego dla innych aplikacji.
- Komunikacja z usługami systemowymi (lokalizacja, kamera, galeria) odbywa się wyłącznie poprzez oficjalne API systemu Android.
- Połączenia z serwerami map odbywają się przez szyfrowane połączenie HTTPS.
- Aplikacja nie wymaga tworzenia konta ani podawania hasła.

Niezależnie od powyższego, ze względu na charakter urządzeń mobilnych, zalecamy zabezpieczenie telefonu hasłem/biometrią oraz korzystanie z aktualnego oprogramowania systemowego. Plik kopii zapasowej zawiera Twoje dane w postaci niezaszyfrowanej - przechowuj go w bezpiecznym miejscu.

---

## 10. Dzieci

Aplikacja jest przeznaczona dla osób w wieku **16 lat i starszych**. Administrator nie zbiera świadomie danych dzieci poniżej tego wieku. Jeżeli jesteś rodzicem lub opiekunem i sądzisz, że dziecko korzysta z Aplikacji bez Twojej zgody, prosimy o kontakt - pomożemy usunąć dane.

---

## 11. Zmiany polityki

Każda istotna zmiana niniejszej polityki będzie sygnalizowana w Aplikacji oraz wymagała ponownej akceptacji przy następnym uruchomieniu. Drobne zmiany redakcyjne mogą być wprowadzane bez dodatkowej zgody, ale numer wersji dokumentu zostanie zaktualizowany.

Historia wersji jest dostępna w publicznym repozytorium: https://github.com/Izzy4me/szczytownik-legal

---

## 12. Kontakt

W sprawie niniejszej polityki prywatności:

**Mateusz Smęt**  
e-mail: **matt.the.peak.coder@gmail.com**

---

*Niniejszy dokument przygotowano w języku polskim jako wersji autorytatywnej. Tłumaczenia na inne języki służą wyłącznie celom informacyjnym - w razie wątpliwości wiążąca jest wersja polska.*
