# Bezpieczeństwo komputerów i stacji roboczych

## Wprowadzenie

Komputery w firmie muszą być odpowiednio zabezpieczone, żeby nikt niepowołany nie uzyskał dostępu do danych. Poniżej opisano najważniejsze zasady.

## Bezpieczeństwo fizyczne

![Zablokowany komputer](images/locked.png)

- komputery powinny znajdować się w zamykanych pomieszczeniach,
- laptopy nie mogą być zostawiane bez nadzoru w miejscach publicznych,
- przy odchodzeniu od komputera należy blokować ekran (`Win + L` lub `Ctrl + Command + Q`),
- nie wolno podłączać nieznanych pendrive'ów do komputera służbowego,
- zużyte dyski twarde należy trwale zniszczyć lub nadpisać.

## Aktualizacje i oprogramowanie

- system operacyjny i programy muszą być na bieżąco aktualizowane,
- automatyczne aktualizacje powinny być włączone,
- instalować wolno tylko oprogramowanie zatwierdzone przez dział IT,
- nie wolno wyłączać antywirusa ani firewalla.

## Konta użytkowników

- każdy pracownik ma własne konto,
- do codziennej pracy używamy konta bez uprawnień administratora,
- konta nieużywane ponad 30 dni powinny być dezaktywowane.

## Bezpieczeństwo sieci

- firmowe Wi-Fi powinno korzystać z WPA2 lub WPA3,
- nie wolno łączyć się z otwartymi sieciami Wi-Fi na komputerze służbowym,
- przy pracy zdalnej obowiązkowe jest korzystanie z VPN,
- dysk powinien być zaszyfrowany (BitLocker lub FileVault).

## Przykłady zagrożeń

### Przykład 1: Nieznany pendrive

Pracownik znalazł pendrive'a na parkingu i podłączył do komputera. Pendrive zawierał wirusa, który zaczął rejestrować hasła.

**Jak się chronić:** Nigdy nie podłączać nieznanych nośników USB — przekazać je do działu IT.

### Przykład 2: Niezablokowany komputer

Pracownik poszedł na obiad i nie zablokował ekranu. Ktoś inny uzyskał dostęp do jego plików.

**Jak się chronić:** Zawsze blokować ekran. Warto ustawić automatyczną blokadę po 5 minutach bezczynności.

### Przykład 3: Stara przeglądarka

Pracownik nie aktualizował przeglądarki przez pół roku. Haker wykorzystał znaną lukę w tej wersji i przejął kontrolę nad komputerem.

**Jak się chronić:** Włączyć automatyczne aktualizacje przeglądarki i systemu.
