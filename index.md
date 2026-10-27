---
title: Polityka prywatności – Szczytownik
lang: pl
---

# Polityka prywatności aplikacji Szczytownik

**Wersja dokumentu:** 1.0.0  
**Data wejścia w życie:** 21 kwietnia 2026 r.  
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
- Aplikacja **nie przesyła** Twoich danych osobowych ani lokalizacyjnych do Administratora ani do osób trzecich.
- Możesz w każdej chwili usunąć wszystkie dane, odinstalowując Aplikację lub korzystając z opcji „Wyczyść dane" w Ustawieniach.
- Jeżeli zdecydujesz się wysłać zgłoszenie błędu (przycisk „Zgłoś błąd"), wiadomość trafia bezpośrednio do Administratora przez Twój własny klient pocztowy. To Ty decydujesz, jakie informacje załączysz.

---

## 3. Jakie dane przetwarza Aplikacja

### 3.1. Dane lokalizacyjne (GPS)

- **Co:** szerokość i długość geograficzna, wysokość n.p.m., dokładność pomiaru, znacznik czasu.
- **Kiedy:** wyłącznie wtedy, gdy Aplikacja jest aktywna i korzysta z funkcji wymagającej lokalizacji (ekran kamery, ekran startowy, weryfikacja punktu).
- **Cel:** weryfikacja, czy znajdujesz się w pobliżu punktu zainteresowania (POI), oraz wyświetlanie aktualnej pozycji na mapie.
- **Gdzie trafia:** wyłącznie do lokalnej bazy SQLite na Twoim urządzeniu, jako część rekordu wspomnienia.
- **Podstawa prawna:** art. 6 ust. 1 lit. a) RODO (Twoja zgoda) oraz art. 6 ust. 1 lit. b) RODO (niezbędność do wykonania funkcji Aplikacji, z której korzystasz).

### 3.2. Zdjęcia

- **Co:** zdjęcia robione przez Ciebie w Aplikacji oraz zdjęcia importowane z galerii. Pliki zdjęciowe mogą zawierać metadane EXIF (w tym datę, model aparatu i - jeżeli włączyłeś tę funkcję w systemie - lokalizację GPS).
- **Gdzie trafia:** wyłącznie do lokalnej pamięci urządzenia oraz, jeżeli wyrazisz zgodę systemową, do galerii systemowej.
- **Podstawa prawna:** art. 6 ust. 1 lit. b) RODO (wykonanie funkcji Aplikacji).

### 3.3. Ustawienia użytkownika

- Preferencje związane z dokładnością GPS, czasem auto-zapisu, językiem, akceptacją niniejszej polityki itp.
- Przechowywane lokalnie w bazie SQLite Aplikacji.

### 3.4. Dane techniczne (diagnostyka)

W bieżącej wersji Aplikacja **nie korzysta** z żadnego zewnętrznego systemu raportowania błędów (np. Sentry). Dzienniki techniczne pozostają na Twoim urządzeniu i nie są nigdzie wysyłane bez Twojej wiedzy.

W przyszłych wersjach Aplikacja może wprowadzić dobrowolne raportowanie awarii. Każda taka zmiana będzie poprzedzona aktualizacją niniejszej polityki oraz prośbą o ponowną zgodę.

---

## 4. Komu udostępniamy dane

Administrator **nie udostępnia** żadnych danych osobowych osobom trzecim w sposób automatyczny.

Następujące podmioty mogą uzyskać dostęp do wybranych danych w sytuacjach opisanych poniżej:

- **Google Play (Google Ireland Ltd.)** - identyfikator instalacji oraz statystyki anonimowe, w zakresie, w jakim Google jako dystrybutor sklepu zbiera takie dane od wszystkich aplikacji.
- **Twój klient e-mail** - treść zgłoszenia błędu, wyłącznie wtedy, gdy świadomie wyślesz zgłoszenie z Aplikacji.

Aplikacja w obecnej wersji nie zawiera bibliotek reklamowych ani analitycznych firm trzecich.

---

## 5. Okres przechowywania

- Dane lokalne (wspomnienia, zdjęcia, ustawienia) są przechowywane do momentu, w którym je usuniesz lub odinstalujesz Aplikację.
- Wiadomości e-mail wysłane do Administratora przechowywane są przez okres niezbędny do udzielenia odpowiedzi i obsługi sprawy, nie dłużej niż 12 miesięcy.

---

## 6. Twoje prawa

Zgodnie z RODO masz prawo do:

1. **dostępu** do swoich danych - wszystkie dane masz fizycznie na swoim urządzeniu;
2. **sprostowania** danych - możesz edytować lub usunąć każde wspomnienie w Aplikacji;
3. **usunięcia** („prawo do bycia zapomnianym") - odinstalowanie Aplikacji lub funkcja „Wyczyść dane" w Ustawieniach trwale usuwa wszystkie dane;
4. **ograniczenia** przetwarzania;
5. **przenoszenia** danych - funkcja „Eksportuj dane" pozwala pobrać Twoje wspomnienia w czytelnym formacie;
6. **sprzeciwu** wobec przetwarzania;
7. **cofnięcia zgody** w dowolnym momencie, bez wpływu na zgodność z prawem przetwarzania dokonanego przed jej cofnięciem;
8. **wniesienia skargi** do organu nadzorczego.

W każdej sprawie dotyczącej danych możesz napisać na: **matt.the.peak.coder@gmail.com**.

---

## 7. Bezpieczeństwo danych

- Aplikacja przechowuje dane wyłącznie w obrębie sandboksa systemu Android, niedostępnego dla innych aplikacji.
- Komunikacja z usługami systemowymi (lokalizacja, kamera, galeria) odbywa się wyłącznie poprzez oficjalne API systemu Android.
- Aplikacja nie wymaga tworzenia konta ani podawania hasła.

Niezależnie od powyższego, ze względu na charakter urządzeń mobilnych, zalecamy zabezpieczenie telefonu hasłem/biometrią oraz korzystanie z aktualnego oprogramowania systemowego.

---

## 8. Dzieci

Aplikacja jest przeznaczona dla osób w wieku **13 lat i starszych**. Administrator nie zbiera świadomie danych dzieci poniżej tego wieku. Jeżeli jesteś rodzicem lub opiekunem i sądzisz, że dziecko korzysta z Aplikacji bez Twojej zgody, prosimy o kontakt - pomożemy usunąć dane.

---

## 9. Zmiany polityki

Każda istotna zmiana niniejszej polityki będzie sygnalizowana w Aplikacji oraz wymagała ponownej akceptacji przy następnym uruchomieniu. Drobne zmiany redakcyjne mogą być wprowadzane bez dodatkowej zgody, ale numer wersji dokumentu zostanie zaktualizowany.

Historia wersji jest dostępna w publicznym repozytorium: https://github.com/Izzy4me/szczytownik-legal

---

## 10. Kontakt

W sprawie niniejszej polityki prywatności:

**Mateusz Smęt**  
e-mail: **matt.the.peak.coder@gmail.com**

---

*Niniejszy dokument przygotowano w języku polskim jako wersji autorytatywnej. Tłumaczenia na inne języki służą wyłącznie celom informacyjnym - w razie wątpliwości wiążąca jest wersja polska.*
