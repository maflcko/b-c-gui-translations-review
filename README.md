# Translations Review by LLM (✨ experimental)

<details><summary>pl</summary>

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>hasłoOstrzeżenie: Jeśli zaszyfrujesz swój portfel i zgubisz hasło - &lt;b&gt;STRACISZ WSZYSTKIE SWOJE BITCONY&lt;/b&gt;!</translation>
    
YES: The translation contains an extraneous word "hasło" at the beginning, which is not present in the source text.
Ostrzeżenie: Jeśli zaszyfrujesz swój portfel i zgubisz hasło - <strong>STRACISZ WSZYSTKIE SWOJE BITCOINY</strong>!
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Plik ustawień 1%1 może być uszkodzony lub nieprawidłowy</translation>
    
YES: The format specifier "%1" is incorrectly translated as "1%1". It should be "%1".
Plik ustawień %1 może być uszkodzony lub nieprawidłowy
```

```
        <source>Runaway exception</source>
        <translation>Błąd zapisu do portfela</translation>
    
YES
The Polish translation "Błąd zapisu do portfela" means "Error writing to wallet", which is not an accurate translation of "Runaway exception". A more accurate translation for "Runaway exception" in a programming context, especially related to Bitcoin, would be "Nieprzewidziane wyjątek" or "Nieunikniony wyjątek".
"Nieprzewidziane wyjątek"
```

```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>Szczelinomierz</translation>
    
YES - The Polish word "Szczelinomierz" translates to "feeler gauge" in English, which is a tool used for measuring small gaps or clearances. This is not an accurate translation of "Feeler" in the context of Bitcoin, which refers to a short-lived peer connection. The correct translation should reflect this meaning.

Correct translation: Czujnik
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>Zażądaj płatności (wygeneruj QE code i bitcoin: URI)</translation>
    
YES: The word "QE" in the translation is a misspelling of "QR".
The correct translation is: Zażądaj płatności (wygeneruj kody QR i adresy bitcoin: URI)
```

```
        <source>Open a bitcoin: URI</source>
        <translation>Otwórz URI</translation>
    
YES - The translation is missing the word "bitcoin" from the source text. The correct translation should be "Otwórz URI bitcoin:".
```

```
        <source>Confirmed</source>
        <translation>Potwerdzone</translation>
    
YES: The translation contains a spelling error. The correct spelling is "Potwierdzone".
Potwierdzone
```

```
        <source>Create Wallet</source>
        <extracomment>Title of window indicating the progress of creation of a new wallet.</extracomment>
        <translation>Stwórz potrfel</translation>
    
YES: The Polish translation of "Create Wallet" is misspelled. The correct translation is "Stwórz portfel".
```

```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Sprawne, ale nie oglądane skrypty tylko do odczytu zostały przeniesione do nowego portfela '%1'</translation>
    
YES: The translation incorrectly states that the scripts are "read-only" ("tylko do odczytu"). The original English text implies that the scripts are "solvable" (meaning they can be solved or executed) but not "watched" (meaning they are not actively monitored for incoming transactions). The Polish phrase "tylko do odczytu" changes the meaning significantly.

Correct translation: Sprawne, ale nie monitorowane skrypty zostały przeniesione do nowego portfela o nazwie '%1'.
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>Zamknięcie portfela na zbyt długo może skutkować koniecznością ponownego załadowania całego łańcucha, jeżeli jest włączony pruning.</translation>
    
YES - The Polish translation uses the English word "pruning" which is not a standard Polish term and could be confusing for users. A more appropriate translation would be "przycinanie".

Correct translation: Zamknięcie portfela na zbyt długo może skutkować koniecznością ponownego załadowania całego łańcucha, jeżeli jest włączone przycinanie.
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Skompilowany bez obsługi podpisywania zewnętrznego (wymagany do podpisywania zewnętrzengo)</translation>
    
YES - The word "zewnętrznego" is misspelled in the Polish translation. It should be "zewnętrznego".
Skompilowany bez obsługi podpisywania zewnętrznego (wymagany do podpisywania zewnętrznego)
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Co najmniej %1 GB danych, zostanie zapisane w tym katalogu, dane te będą przyrastały w czasie.</translation>
    
YES - The word order in the translation is slightly unnatural. "Co najmniej %1 GB danych zostanie zapisane w tym katalogu, a dane te będą przyrastały w czasie." is a more fluent phrasing.
```

```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>Próba wydania bitcoinów które nie są jeszcze wyświetlone jako transakcja zostanie odrzucona przez sieć.</translation>
    
YES: The translation is grammatically incorrect and does not accurately convey the meaning of the source text. The phrase "nie są jeszcze wyświetlone jako transakcja" is awkward and doesn't make sense in the context of Bitcoin transactions.

A more accurate and natural translation would be:

"Próba wydania bitcoinów, których transakcje nie zostały jeszcze wyświetlone, zostanie odrzucona przez sieć."
```

```
        <source>Unknown. Syncing Headers (%1, %2%)…</source>
        <translation>nieznany, Synchronizowanie nagłówków (1%1, 2%2%)</translation>
    
YES, The translation contains a mistranslation of the phrase "Unknown". It should be translated as "Nieznany" and not "nieznany" as the capitalization is inconsistent. The percentage formatting is also incorrect.
Correct translation: Nieznany. Synchronizowanie nagłówków (%1, %2%)…
```

```
        <source>Whether to show coin control features or not.</source>
        <translation>Wybierz pokazywanie lub nie funkcji kontroli monet.</translation>
    
YES: The translation is grammatically incorrect and doesn't convey the intended meaning. It should be "Czy pokazywać funkcje kontroli monet, czy nie." or "Określa, czy mają być pokazywane funkcje kontroli monet."

Correct translation: Czy pokazywać funkcje kontroli monet, czy nie.
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Skompilowany bez obsługi podpisywania zewnętrznego (wymagany do podpisywania zewnętrzengo)</translation>
    
YES - The word "zewnętrznego" is misspelled in the Polish translation. It should be "zewnętrznego".
Skompilowany bez obsługi podpisywania zewnętrznego (wymagany do podpisywania zewnętrznego)
```

```
        <source>Signed transaction successfully. Transaction is ready to broadcast.</source>
        <translation>transakcja</translation>
    
YES: The translation is incomplete and does not convey the full meaning of the original English text. The word "transakcja" is just the Polish word for "transaction", and it's missing the rest of the sentence.
Correct translation: Pomyślnie podpisano transakcję. Transakcja jest gotowa do emisji.
```

```
        <source>(But this wallet cannot sign transactions.)</source>
        <translation>(Ale ten portfel nie może podipisać transakcji.)</translation>
    
YES, The Polish word "podipisać" is not a valid word. The correct word should be "podpisać".
(Ale ten portfel nie może podpisać transakcji.)
```

```
        <source>High bandwidth BIP152 compact block relay: %1</source>
        <translation>Kompaktowy przekaźnik blokowy BIP152 o dużej przepustowości: 1 %1</translation>
    
YES, The word "Kompaktowy" is used incorrectly in this context. It should be "Kompaktowe" to agree in gender and number with "przekaźnik blokowy". The order of the placeholders is also incorrect. The correct translation is "Przekaźnik kompaktowych bloków BIP152 o dużej przepustowości: %1".
```

```
        <source>The duration of a currently outstanding ping.</source>
        <translation>Czas trwania nadmiarowego pingu</translation>
    
YES. The translation is problematic. The word "nadmiarowego" (excessive/redundant) does not accurately convey the meaning of "outstanding" in the context of a ping. "Outstanding" in this context refers to a ping that has been sent but not yet received or acknowledged.

A more accurate translation would be:

NO. The translation is correct.
Długość trwania nierozstrzygniętego pinga.
```

```
        <source>Outbound Manual: added using RPC %1 or %2/%3 configuration options</source>
        <extracomment>Explanatory text for an outbound peer connection that was established manually through one of several methods. The numbered arguments are stand-ins for the methods available to establish manual connections.</extracomment>
        <translation>Outbound Manual: dodano przy użyciu opcji konfiguracyjnych RPC 1%1 lub 2%2/3%3</translation>
    
YES: The format specifiers are not correctly translated. They should be "%1", "%2", and "%3".
Outbound Manual: dodano przy użyciu opcji konfiguracyjnych RPC %1 lub %2/%3
```

```
        <source>Ban for</source>
        <translation>Zbanuj na</translation>
    
YES
The translation is unnatural and doesn't accurately convey the meaning of "Ban for" in the context of Bitcoin. "Zbanuj na" translates to "Ban on" which is grammatically incorrect and doesn't make sense in the context.

A more appropriate translation would be:
"Zbanuj za" (Ban for) or "Ban za" (Ban for)
```

```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>Opcjonalna kwota by zażądać. Zostaw puste lub zero by nie zażądać konkretnej kwoty.</translation>
    
YES: The translation uses the infinitive form "by zażądać" which is grammatically incorrect in this context. The correct form would be "do zażądania" or simply "do zażądania kwoty".

Correct translation: Opcjonalna kwota do zażądania. Zostaw puste lub zero, aby nie zażądać konkretnej kwoty.
```

```
        <source>Custom change address</source>
        <translation>Niestandardowe zmiany adresu</translation>
    
YES, The translation is problematic as "zmiany adresu" (changes of address) does not accurately convey the meaning of "change address" in the context of Bitcoin, which refers to an address where unspent output is returned. The correct translation should reflect this meaning.

Niestandardowy adres zwrotny
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>206/5000
Korzystanie z opłaty domyślnej może skutkować wysłaniem transakcji, która potwierdzi się w kilka godzin lub dni (lub nigdy). Rozważ wybranie opłaty ręcznie lub poczekaj, aż sprawdzisz poprawność całego łańcucha.</translation>
    
YES: The translation includes an irrelevant number "206/5000" at the beginning.
Korzystanie z opłaty domyślnej może skutkować wysłaniem transakcji, która potwierdzi się w kilka godzin lub dni (lub nigdy). Rozważ wybranie opłaty ręcznie lub poczekaj, aż sprawdzisz poprawność całego łańcucha.
```

```
        <source>%1 (%2 blocks)</source>
        <translation>%1 (%2 bloków)github.com </translation>
    
YES, The translation contains spam in the form of a URL.
%1 (%2 bloków)
```

```
        <source>%1 to '%2'</source>
        <translation>%1 do '%2'8f0451c0-ec7d-4357-a370-eff72fb0685f</translation>
    
YES. The translation contains extraneous characters. The correct translation should be: %1 do '%2'.

NO
```

```
        <source>Please, review your transaction. You can create and send this transaction or create a Partially Signed Bitcoin Transaction (PSBT), which you can save or copy and then sign with, e.g., an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can send their transaction or create a PSBT. This string is displayed when both private keys and PSBT controls are enabled.</extracomment>
        <translation>Proszę przejrzeć propozycję transakcji. Zostanie utworzona częściowo podpisana transakcja (ang. PSBT), którą można skopiować, a następnie podpisać np. offline z portfelem %1 lub z innym portfelem zgodnym z PSBT.</translation>
    
YES: The translation incorrectly states that the partially signed transaction (PSBT) will be created and sent. The original text says "create and send this transaction OR create a Partially Signed Bitcoin Transaction (PSBT)". The translation omits the option to send the transaction directly and incorrectly claims that a PSBT will be created automatically.

Correct translation: Proszę przejrzeć transakcję. Możesz utworzyć i wysłać tę transakcję lub utworzyć częściowo podpisaną transakcję Bitcoin (PSBT), którą możesz zapisać lub skopiować, a następnie podpisać np. za pomocą portfela offline %1 lub sprzętowego portfela zgodnego z PSBT.
```

```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Duplikat adres-u znaleziony: adresy powinny zostać użyte tylko raz.</translation>
    
YES: The translation has a grammatical error. The accusative case of "adres" is "adres", not "adres-u". Also, the phrase "powinny zostać użyte tylko raz" is slightly unnatural. A more natural phrasing would be "każdy adres powinien być użyty tylko raz".

Correct translation: Duplikat adresu znaleziony: każdy adres powinien być użyty tylko raz.
```

```
        <source>The fee will be deducted from the amount being sent. The recipient will receive less bitcoins than you enter in the amount field. If multiple recipients are selected, the fee is split equally.</source>
        <translation>Opłata zostanie odjęta od kwoty wysyłane.Odbiorca otrzyma mniej niż bitcoins wpisz w polu kwoty. Jeśli wybrano kilku odbiorców, opłata jest podzielona równo.</translation>
    
YES - The translation contains grammatical errors and awkward phrasing. The word "bitcoins" should be translated and placed correctly.
The fee will be deducted from the amount being sent. The recipient will receive fewer bitcoins than you enter in the amount field. If multiple recipients are selected, the fee is split equally.
Opłata zostanie odjęta od wysyłanej kwoty. Odbiorca otrzyma mniej bitcoinów niż wpisano w polu kwoty. Jeśli wybrano wielu odbiorców, opłata jest dzielona równo.
```

```
        <source>Subtract fee from amount</source>
        <translation>Odejmij od wysokości opłaty</translation>
    
YES
The translation is problematic because it incorrectly translates "Subtract fee from amount" to "Odejmij od wysokości opłaty". The correct translation should be "Odejmij opłatę od kwoty". The original translation implies subtracting the fee from the fee amount itself, which is nonsensical in the context of Bitcoin transactions.

Correct translation: Odejmij opłatę od kwoty
```

```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Wpisz adres, wiadomość oraz sygnaturę (podpis) odbiorcy (upewnij się, że dokładnie skopiujesz wszystkie zakończenia linii, spacje, tabulacje itp.).  Uważaj by nie dodać więcej do podpisu niż do samej podpisywanej wiadomości by uniknąć ataku man-in-the-middle. 
Zwróć uwagę, że poprawnie zweryfikowana wiadomość potwierdza to, że nadawca posiada klucz do adresu, natomiast nie potwierdza to, że poprawne wysłanie jakiejkolwiek transakcji!</translation>
    
YES: The translation contains an error in the final sentence. It incorrectly states that a verified message proves the sender has the key to the address, rather than proving that the message was signed by the address. The original English text says "this only proves the signing party receives with the address".
Correct translation: Wpisz adres, wiadomość oraz sygnaturę (podpis) odbiorcy (upewnij się, że dokładnie skopiujesz wszystkie zakończenia linii, spacje, tabulacje itp.). Uważaj by nie dodać więcej do podpisu niż do samej podpisywanej wiadomości by uniknąć ataku man-in-the-middle. Zwróć uwagę, że dowodzi to jedynie tego, że strona podpisująca otrzymuje za pomocą adresu, nie może to udowodnić nadawczości jakiejkolwiek transakcji!
```

```
        <source>0/unconfirmed, in memory pool</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that is in the memory pool.</extracomment>
        <translation>0/niepotwierdzone, w kolejce w pamięci</translation>
    
YES, The word "niepotwierdzone" is a mistranslation of "unconfirmed." The correct translation is "niepotwierdzona."

Correct translation: 0/niepotwierdzona, w kolejce w pamięci
```

```
        <source>0/unconfirmed, not in memory pool</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that is not in the memory pool.</extracomment>
        <translation>0/niepotwierdzone, nie wysłane do kolejki w pamięci</translation>
    
YES, The translation is problematic because it is an inaccurate and awkward phrasing for the given context. The term "nie wysłane do kolejki w pamięci" directly translates to "not sent to the memory queue," which doesn't convey the intended meaning of a transaction not being in the memory pool. A more accurate and natural translation for the Bitcoin context would be "nie w puli pamięci" or "nie w mempoolu."

0/niepotwierdzone, nie w puli pamięci
```

```
        <source>Copy transaction ID</source>
        <translation>transakcjaSkopiuj ID transakcji</translation>
    
YES: The Polish translation is grammatically incorrect and awkward. It also appears to be a concatenation of multiple words rather than a proper phrase. A more natural and accurate translation would be "Skopiuj identyfikator transakcji".

Skopiuj identyfikator transakcji
```

```
        <source>Edit address label</source>
        <translation>Wyedytuj adres etykiety</translation>
    
YES - The translation is grammatically incorrect. The correct translation should be "Edytuj etykietę adresu".
```

```
        <source>Confirmed</source>
        <translation>Potwerdzone</translation>
    
YES: The translation contains a spelling error. The correct spelling is "Potwierdzone".
Potwierdzone
```

```
        <source>No wallet has been loaded.
Go to File &gt; Open Wallet to load a wallet.
- OR -</source>
        <translation>Portfel nie został wybrany.
Przejdź do Plik &gt; Otwórz Portfel aby wgrać portfel.</translation>
    
YES
The translation is incomplete. The "- OR -" part from the source text is missing in the translation.
No wallet has been loaded.
Go to File &gt; Open Wallet to load a wallet.
- OR -
Portfel nie został wybrany.
Przejdź do Plik &gt; Otwórz Portfel aby wgrać portfel.
- LUB -
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>PSBT musi być mniejsze niż 100MB</translation>
    
YES - The word "mniejsze" (smaller) is used incorrectly in Polish. The correct translation should be "mniejszy" (smaller) when referring to a masculine noun like "PSBT".

The correct translation is:
PSBT musi być mniejszy niż 100MB
```

```
        <source>Cannot downgrade wallet from version %i to version %i. Wallet version unchanged.</source>
        <translation>Nie można zmienić wersji portfela z wersji %ina wersje %i. Wersja portfela pozostaje niezmieniona.</translation>
    
YES: The translation incorrectly handles the first format specifier `%i`. It should be `%i` in the translation as well.

Correct translation: Nie można zmienić wersji portfela z wersji %i na wersję %i. Wersja portfela pozostaje niezmieniona.
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>Nie można zaktualizować portfela dzielonego innego niż HD z wersji 1%i do wersji 1%i bez aktualizacji w celu obsługi wstępnie podzielonej puli kluczy. Użyj wersji 1%i lub nie określono wersji.</translation>
    
YES - The translation incorrectly inserts "1" before each format specifier (%i). This is erroneous and likely unintended.

Correct translation: Nie można zaktualizować portfela dzielonego innego niż HD z wersji %i do wersji %i bez aktualizacji w celu obsługi wstępnie podzielonej puli kluczy. Użyj wersji %i lub nie określono wersji.
```

```
        <source>Error loading wallet. Wallet requires blocks to be downloaded, and software does not currently support loading wallets while blocks are being downloaded out of order when using assumeutxo snapshots. Wallet should be able to load successfully after node sync reaches height %s</source>
        <translation>Błąd ładowania portfela. Portfel wymaga ściągnięcia bloków, a oprogramowanie obecnie nie wspiera ładowania portfeli podczas ściągania bloków poza kolejnością gdy używa się zrzutów assumeutxo. Portfel powinien załadować się poprawnie po osiągnięciu przez węzeł synchronizacji%s</translation>
    
YES: The Polish translation omits the word "height" in the last sentence, which is crucial for understanding the context of the synchronization.

Correct translation: Błąd ładowania portfela. Portfel wymaga ściągnięcia bloków, a oprogramowanie obecnie nie wspiera ładowania portfeli podczas ściągania bloków poza kolejnością gdy używa się zrzutów assumeutxo. Portfel powinien załadować się poprawnie po osiągnięciu przez węzeł synchronizacji wysokości %s
```

```
        <source>Error reading %s! Transaction data may be missing or incorrect. Rescanning wallet.</source>
        <translation>Błąd odczytu 1%s! Może brakować danych transakcji lub mogą być one nieprawidłowe. Ponowne skanowanie portfela.</translation>
    
YES. The format specifier `%s` was incorrectly translated to `1%s`.
Błąd odczytu %s! Może brakować danych transakcji lub mogą być one nieprawidłowe. Ponowne skanowanie portfela.
```

```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Błąd: rekord formatu pliku zrzutu jest nieprawidłowy. Otrzymano „1%s”, oczekiwany „format”.</translation>
    
YES: The format specifier "%s" in the source text is incorrectly translated to "1%s" in the target text. This will likely cause an error during runtime.
Błąd: rekord formatu pliku zrzutu jest nieprawidłowy. Otrzymano "%s", oczekiwany "format".
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>Błąd: rekord identyfikatora pliku zrzutu jest nieprawidłowy. Otrzymano „1%s”, oczekiwano „1%s”.</translation>
    
YES: The translation incorrectly includes an extra "1" before the format specifiers "%s".

Błąd: rekord identyfikatora pliku zrzutu jest nieprawidłowy. Otrzymano "%s", oczekiwano "%s".
```

```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Błąd: wersja pliku zrzutu nie jest obsługiwana. Ta wersja bitcoin-wallet obsługuje tylko pliki zrzutów w wersji 1. Mam plik zrzutu w wersji 1%s</translation>
    
YES - The translation is problematic because it incorrectly includes the format specifier "%s" at the end of the sentence instead of in the correct position to represent the version number.
Correct translation: Błąd: wersja pliku zrzutu nie jest obsługiwana. Ta wersja bitcoin-wallet obsługuje tylko pliki zrzutów w wersji 1. Mam plik zrzutu w wersji %s
```

```
        <source>Error: Unable to produce descriptors for this legacy wallet. Make sure to provide the wallet's passphrase if it is encrypted.</source>
        <translation>Błąd: Nie można wygenerować deskryptorów dla tego starego portfela. Upewnij się najpierw, że portfel jest odblokowany.</translation>
    
YES: The translation is missing the format specifier `%s` which is present in the source text. The Polish translation also uses a phrase "Upewnij się najpierw, że portfel jest odblokowany" which is not an accurate translation of "Make sure to provide the wallet's passphrase if it is encrypted". The correct translation should include the passphrase part.

Błąd: Nie można wygenerować deskryptorów dla tego starego portfela. Upewnij się, że podano hasło do portfela, jeśli jest zaszyfrowany.
```

```
        <source>File %s already exists. If you are sure this is what you want, move it out of the way first.</source>
        <translation>Plik 1%s już istnieje. Jeśli jesteś pewien, że tego chcesz, najpierw usuń to z drogi.</translation>
    
YES: The format specifier %s was incorrectly translated as 1%s. The word "move" was also translated to "usuń" (delete) instead of "przesuń" (move).
NO: Plik %s już istnieje. Jeśli jesteś pewien, że tego chcesz, najpierw przesuń go z drogi.
```

```
        <source>Invalid or corrupt peers.dat (%s). If you believe this is a bug, please report it to %s. As a workaround, you can move the file (%s) out of the way (rename, move, or delete) to have a new one created on the next start.</source>
        <translation>Nieprawidłowy lub uszkodzony plik peers.dat (1%s). Jeśli uważasz, że to błąd, zgłoś go do 1%s. Jako obejście, możesz przenieść plik (1%s) z drogi (zmień nazwę, przenieś lub usuń), aby przy następnym uruchomieniu utworzyć nowy.</translation>
    
YES: The format specifiers are incorrect in the translation. They should be '%s', not '1%s'.
NO
```

```
        <source>No dump file provided. To use dump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>Nie dostarczono pliku zrzutu. Aby użyć funkcji createfromdump, należy podać -dumpfile=1.</translation>
    
YES - The translation erroneously replaces the placeholder `<filename>` with a hardcoded value "1".
Correct translation: Nie dostarczono pliku zrzutu. Aby użyć zrzutu, należy podać -dumpfile=&lt;nazwa_pliku&gt;.
```

```
        <source>No wallet file format provided. To use createfromdump, -format=&lt;format&gt; must be provided.</source>
        <translation>Nie dostarczono pliku zrzutu. Aby użyć funkcji createfromdump, należy podać -dumpfile=&lt;format&gt;.</translation>
    
YES: The translation incorrectly substitutes "wallet file format" with "file dump" and misunderstands the parameter name. The format specifier `<format>` should refer to the format itself, not a dumpfile.

Correct translation: Nie podano formatu pliku portfela. Aby użyć createfromdump, należy podać -format=&lt;format&gt;.
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Nieobsługiwany poziom rejestrowania specyficzny dla kategorii %1$s=%2$s. Oczekiwano %1$s=&lt;category&gt;:&lt;loglevel&gt;. Poprawne kategorie %3$s. Poprawne poziomy logowania: %4 $s.</translation>
    
YES. The Polish translation contains a formatting error. The space before "%4$s" is incorrect.

NO.
```

```
        <source>%s is set very high! Fees this large could be paid on a single transaction.</source>
        <translation>%sto bardzo dużo!  Tak duże opłaty można uiścić w ramach jednej transakcji.</translation>
    
YES: The translation is problematic because the format specifier '%s' is not correctly transferred. The source uses '%s' to represent a placeholder for text, but the translation incorrectly uses '%sto' which merges the placeholder with the subsequent word "to" (meaning "is" or "to" in Polish). This will likely cause an error when the formatted string is used.

Correct translation: %s jest bardzo dużo! Tak duże opłaty można uiścić w ramach jednej transakcji.
```

```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on enormous cluster of unconfirmed transactions.</source>
        <translation>Nie udało się obliczyć opłat za uderzenia, ponieważ niepotwierdzone UTXO zależą od ogromnego skupiska niepotwierdzonych transakcji.</translation>
    
YES: The Polish translation of "bump fees" as "opłat za uderzenia" is incorrect and nonsensical in the context of Bitcoin. In Bitcoin terminology, "bump fees" refers to increasing transaction fees to incentivize miners to include a transaction faster. A more accurate translation would be "opłat za podniesienie" or "opłat za zwiększenie".

NO
```

```
        <source>Fee estimation failed. Fallbackfee is disabled. Wait a few blocks or enable %s.</source>
        <translation>Estymacja opłat nieudana. Domyślna opłata jest wyłączona. Poczekaj kilka bloków lub włącz  -%s.</translation>
    
YES: The translation incorrectly translates "%s" as "-%s". The format specifier should be directly translated without any added characters.
Correct translation: Estymacja opłat nieudana. Domyślna opłata jest wyłączona. Poczekaj kilka bloków lub włącz %s.
```

```
        <source>Error: Got key that was not hex: %s</source>
        <translation>Błąd: Otrzymana wartość nie jest szestnastkowa%s</translation>
    
YES - The translation is missing a colon after "szestnastkowa" which is present in the source text after "hex".
Błąd: Otrzymana wartość nie jest szesnastkowa: %s
```

```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Błąd: Otrzymana wartość nie jest szestnastkowa%s</translation>
    
YES: The format specifier '%s' is not correctly transferred from the source to the translation. The space after "szestnastkowa" should be before the '%s'.
Błąd: Otrzymana wartość nie jest szesnastkowa: %s
```

```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>Błąd: Pula kluczy jest pusta, odwołaj się do puli kluczy.</translation>
    
YES: The translation is too literal and doesn't convey the intended meaning. "Odwołaj się do puli kluczy" is not a correct or natural phrasing in Polish. The English "keypoolrefill" is a command or function name, and it's better to keep it as is or translate it descriptively.

Correct translation: Błąd: Pula kluczy się wyczerpała, najpierw uruchom polecenie keypoolrefill.
```

```
        <source>Error: No %s addresses available.</source>
        <translation>Błąd: %s adres nie dostępny</translation>
    
YES
The original English sentence uses a plural form "addresses" but the Polish translation uses a singular form "adres". The translation should also use the plural form.
Błąd: nie dostępnych jest %s adresów.
```

```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>Błąd: Nie można zapisać wersji %u jako uint32_t</translation>
    
YES: The Polish translation incorrectly uses "zapisać" (to save/write) instead of "przetworzyć" or "zinterpretować" (to parse/interpret) which is the correct meaning of "parse" in this context. The format specifier %u is correctly transferred.

Correct translation: Błąd: Nie można przetworzyć wersji %u jako uint32_t
```

```
        <source>Error: database transaction cannot be executed for wallet %s</source>
        <translation>Błąd: transakcja bazy danych nie może zostać wykonana dla portfela%s</translation>
    
YES: The space before '%s' is missing. The correct translation is: "Błąd: transakcja bazy danych nie może zostać wykonana dla portfela %s"
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>Wartość opłaty (%s) jest mniejsza niż wartość minimalna w ustawieniach (%s)</translation>
    
YES - The translation incorrectly uses "wartość opłaty" (fee value) instead of "stawka opłaty" (fee rate). The context of Bitcoin transactions implies a rate rather than a simple value.
Correct translation: Stawka opłaty (%s) jest niższa niż minimalna stawka opłaty w ustawieniach (%s)
```

```
        <source>Invalid port specified in %s: '%s'</source>
        <translation>Nieprawidłowa maska sieci określona w %s: '%s'</translation>
    
YES - The Polish translation incorrectly translates "port" as "maska sieci" (network mask). The correct translation for "port" in this context is "port".
NO - "Invalid port specified in %s: '%s'"
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>Portfel będzie unikał płacenia mniejszej niż przekazana opłaty.</translation>
    
YES: The translation is problematic because it inaccurately translates "minimum relay fee" as "przekazana opłaty" (submitted fee). The correct translation should convey the idea of a minimum fee required for relaying the transaction on the Bitcoin network.
Correct translation: Portfel będzie unikał płacenia opłaty niższej niż minimalna opłata za przekazanie.
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>Kwota transakcji musi być dodatnia</translation>
    
YES: The translation is inaccurate because it states that the transaction amount must be positive, whereas the original English text states that it must not be negative. The correct translation should reflect that the amount can be zero.

NO: Kwota transakcji nie może być ujemna
```
