# Kopie zapasowe (backup)

## Wprowadzenie

Kopie zapasowe chronią dane firmy przed utratą. Przyczyny mogą być różne — awaria sprzętu, atak ransomware, przypadkowe usunięcie plików. Dobrze wykonany backup pozwala szybko przywrócić dane.

## Rodzaje kopii zapasowych

- **Kopia pełna** — kopiuje wszystkie dane. Zajmuje dużo miejsca, ale łatwo z niej przywrócić dane.
- **Kopia przyrostowa** — kopiuje tylko to, co się zmieniło od ostatniego backupu. Jest szybka i mała.
- **Kopia różnicowa** — kopiuje zmiany od ostatniej kopii pełnej. Kompromis między pełną a przyrostową.

## Reguła 3-2-1

Podstawowa zasada tworzenia kopii zapasowych:

- **3** kopie danych (oryginał + 2 kopie zapasowe),
- **2** różne nośniki (np. dysk + chmura),
- **1** kopia poza firmą (np. w chmurze).

Dzięki temu nawet pożar w biurze czy atak ransomware nie zniszczy wszystkich kopii.

## Harmonogram backupów

| Typ kopii | Jak często | Jak długo przechowywać |
|---|---|---|
| Pełna | Co tydzień | 4 tygodnie |
| Przyrostowa | Codziennie | 7 dni |
| Archiwalna | Co miesiąc | 12 miesięcy |

## Zasady przechowywania

- kopie zapasowe muszą być szyfrowane,
- dostęp do backupów mają tylko upoważnieni administratorzy,
- kopie w chmurze powinny być szyfrowane przed wysłaniem,
- nośniki z kopiami przechowywać w bezpiecznym miejscu.
- przynajmniej jedna kopia zapasowa powinna być przechowywana w trybie "tylko do odczytu" (WORM - Write Once, Read My), aby wirus ransomware nie mógł jej zmodyfikować ani usunąć, nawet jeśli przejmie konto administratora.

## Testowanie backupów

Sam backup nie wystarczy — trzeba regularnie sprawdzać, czy da się z niego przywrócić dane:

- co kwartał testować odtworzenie wybranych danych,
- po zmianach w infrastrukturze sprawdzić, czy backup nadal działa.

## Przykłady

### Przykład 1: Ransomware

Wirus zaszyfrował pliki na serwerze. Dzięki kopii zapasowej przechowywanej w chmurze (poza zasięgiem wirusa) administrator przywrócił dane z poprzedniego dnia.

### Przykład 2: Awaria dysku

Dysk serwera się zepsuł. Administrator odtworzył bazę danych z kopii pełnej i przyrostowych — utracono maksymalnie dane z ostatnich 24 godzin.

### Przykład 3: Przypadkowe usunięcie

Pracownik skasował ważny folder. Dzięki codziennej kopii przyrostowej pliki przywrócono w ciągu 30 minut.
