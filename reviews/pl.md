# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>pl</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bpl%5D%20request)


<!-- cache_translation_check_pl_2805001c8b81f3a9d7661c2a85fc4ef2a1e606ef6f2e908d1dcac7d8e04ad07f -->
```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>Jesteś pewien, że chcesz zaszyfrować swój portfel?</translation>
    
ERR
The Polish translation is grammatically correct but uses a masculine form ("pewien"), which is not gender-neutral and can be problematic in UI text. A neutral and standard phrasing is preferred.

Correct translation:
Czy na pewno chcesz zaszyfrować swój portfel?
```

<!-- cache_translation_check_pl_c563a455862ae7e4254cd531104e2a34c9425b3f0e2b109fe1baa135c8ed9130 -->
```
        <source>Back</source>
        <translation>Cofnij</translation>
    
ERR
"Back" in UI navigation is typically "Wstecz" in Polish; "Cofnij" corresponds to "Undo".

Correct translation:
Wstecz
```

<!-- cache_translation_check_pl_2ebdf202fbee162ab9b5407f00172b0d95d3ffe750ff67f4dc00d1ff2d09acb4 -->
```
        <source>IP/Netmask</source>
        <translation>IP / maska sieci</translation>
    
ERR
Added spaces around the slash; the formatting should match the source.

Correct translation:
IP/maska sieci
```

<!-- cache_translation_check_pl_6fe3b5ee5e019bc82e8813eaa7277b52064b6c422ff5877ffe7b3696ff82cff6 -->
```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>Wystąpił wewnętrzny błąd. %1 będzie próbować bezpiecznie pracować. Jest to niespodziewany błąd, który może zostać zgłoszony w sposób opisany poniżej.</translation>
    
ERR
The phrase "będzie próbować bezpiecznie pracować" is an awkward rendering of "will attempt to continue safely." A more accurate and idiomatic translation is "spróbuje bezpiecznie kontynuować działanie."

Correct translation:
Wystąpił wewnętrzny błąd. %1 spróbuje bezpiecznie kontynuować działanie. To nieoczekiwany błąd, który można zgłosić w sposób opisany poniżej.
```

<!-- cache_translation_check_pl_a03c0f55fc06ac461fcf1fe7a0fe9097121be159e5d4f2de37a3698cd438873a -->
```
        <source>Inbound</source>
        <extracomment>An inbound connection from a peer. An inbound connection is a connection initiated by a peer.</extracomment>
        <translation>Przychodzący</translation>
    
ERR
The form "Przychodzący" is grammatically mismatched for this UI label. The standard label in Polish for "Inbound" (as in connection) is "Przychodzące".

Correct translation:
Przychodzące
```

<!-- cache_translation_check_pl_d836efbd908e5138d209ab28b7a0690b0b436f8cd1e25035b8616e568d36738f -->
```
        <source>Outbound</source>
        <extracomment>An outbound connection to a peer. An outbound connection is a connection initiated by us.</extracomment>
        <translation>Wychodzący</translation>
    
ERR
Grammatical gender mismatch; as a standalone label for a connection, it should be neuter.
Correct translation:
Wychodzące
```

<!-- cache_translation_check_pl_2c397a05411f587aa9d9f03962bb1b9da6ce4645833c16747a5f8a1b6a29d729 -->
```
        <source>Manual</source>
        <extracomment>Peer connection type established manually through one of several methods.</extracomment>
        <translation>Ręczne</translation>
    
ERR
The grammatical form is incorrect for "type" (typ), which is masculine; it should be "Ręczny", not "Ręczne".

Correct translation:
Ręczny
```

<!-- cache_translation_check_pl_dd961a9dba0a83a1a527dae54e86035ed4d0261e55dc5ed0e8cf8bba0c6fda91 -->
```
        <source>&amp;Overview</source>
        <translation>P&amp;odsumowanie</translation>
    
ERR
The Polish translation uses "Podsumowanie" (Summary), which is semantically different from "Overview". A more accurate UI term is "Przegląd". The accelerator is present exactly once as required.

Correct translation:
&Przegląd
```

<!-- cache_translation_check_pl_8a731c85489b6af93828a8c02435921317d9bfb9c1b51b09042644f025815807 -->
```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Podpisz wiadomości swoim adresem, aby udowodnić ich posiadanie</translation>
    
ERR
The translation omits "Bitcoin", uses singular "adresem" instead of plural "addresses", and "ich" is ambiguous. 

Correct translation:
Podpisz wiadomości swoimi adresami Bitcoin, aby potwierdzić, że je posiadasz.
```

<!-- cache_translation_check_pl_953baca2d02bf7987ebc27d25ad01cec1781871bb3661b31f9174f5f50eeafce -->
```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Zweryfikuj wiadomości, aby upewnić się, że została podpisana podanym adresem bitcoinowym.</translation>
    
ERR
Number agreement and plurality are incorrect: plural "wiadomości" requires "zostały podpisane", and "specified Bitcoin addresses" should be plural. 

Correct translation:
Zweryfikuj wiadomości, aby upewnić się, że zostały podpisane określonymi adresami bitcoinowymi.
```

<!-- cache_translation_check_pl_09a34749a42df339cceb6421072395e0c84b812cef119842508f357ac928dcb7 -->
```
        <source>Migrate a wallet</source>
        <translation>Przenieś Portfel</translation>
    
ERR
Incorrect capitalization in Polish; common nouns should not be capitalized mid-sentence.

Correct translation:
Przenieś portfel
```

<!-- cache_translation_check_pl_0b20b3e105282a12775930e88c643024d5fc57623b772ac04e4bd310005da674 -->
```
        <source>Mask the values in the Overview tab</source>
        <translation>Ukryj kwoty w zakładce Podsumowanie</translation>
    
ERR
"Mask" should be translated as "maskuj/zamaskuj" rather than "ukryj" to reflect masking rather than full hiding, and "Overview" is more accurately "Przegląd" in Polish UI terminology.

Correct translation:
Maskuj wartości w zakładce Przegląd
```

<!-- cache_translation_check_pl_bccd4d9b0eaf2b488fb4e5085415b940be6794094eb1a0ce345038102dfd1800 -->
```
        <source>Restore Wallet</source>
        <extracomment>Title of pop-up window shown when the user is attempting to restore a wallet.</extracomment>
        <translation>Przywróć Portfel</translation>
    
ERR
In Polish UI, only the first word should be capitalized unless it's a proper noun. "Portfel" should be lowercase.

Correct translation:
Przywróć portfel
```

<!-- cache_translation_check_pl_d1cd000787f8f3f83f882913472bfd084396adea5ad1bcb630cd6a1904fa31f8 -->
```
        <source>Type: %1
</source>
        <translation>Rodzaj: %1
</translation>
    
ERR
"Rodzaj" is understandable but not the standard UI term. In Polish software interfaces, "Type" is typically translated as "Typ". The format specifier and whitespace are correct.

Correct translation:
Typ: %1
```

<!-- cache_translation_check_pl_5e1b1bd770d99b94510393032eade201b25666f09ded5979009bf629817f85b0 -->
```
        <source>Migrate wallet</source>
        <translation>Przenieś Portfel</translation>
    
ERR
The capitalization is incorrect ("Portfel" should be lowercase), and "Przenieś" suggests moving rather than migrating in a technical context. A clearer command label is:
Migruj portfel
```

<!-- cache_translation_check_pl_7048718f7316b64b1e1d08ba5dc333b117e2acc716873ad9f880a71d38a0e6bd -->
```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Skrypty tylko do odczytu zostały przeniesione do nowego portfela '%1'.</translation>
    
ERR
"Watch-only" in Bitcoin context is better translated as "tylko do obserwacji", and "named" should be rendered as "o nazwie" for accuracy.

Correct translation:
Skrypty tylko do obserwacji zostały przeniesione do nowego portfela o nazwie '%1'.
```

<!-- cache_translation_check_pl_c0c5e7a09d440144da1c8a8d29092f5ffe6b5c42f70cd91161f517f7f0be1b8e -->
```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>Gdy naciśniesz OK, %1 zacznie się pobieranie i przetwarzanie całego %4 łańcucha bloków (%2 GB) zaczynając od najwcześniejszych transakcji w %3 gdy %4 został uruchomiony.</translation>
    
ERR
Grammatical issues and awkward phrasing: “%1 zacznie się pobieranie” is incorrect; word order around “%4 łańcucha bloków” is unnatural; missing comma before “gdy”.

Correct translation:
Kiedy klikniesz OK, %1 rozpocznie pobieranie i przetwarzanie pełnego łańcucha bloków %4 (%2 GB), zaczynając od najwcześniejszych transakcji z %3, gdy %4 został po raz pierwszy uruchomiony.
```

<!-- cache_translation_check_pl_97d82cb92e094bed1ed4e46847a8ae894310a1f351c26b8f9e531b298dc01e31 -->
```
        <source>&amp;Reset Options</source>
        <translation>Z&amp;resetuj ustawienia</translation>
    
ERR
"Options" should be translated as "opcje" rather than "ustawienia" to maintain consistency. Also, placing the accelerator at the start is clearer.

Correct translation:
&Resetuj opcje
```

<!-- cache_translation_check_pl_733d4fcb4c57001c146f455c54b34638278ec9e2f0e30c3e59a7a78f3577aff0 -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Włącz ustawienia &amp;PSBT</translation>
    
ERR
"controls" was mistranslated as "ustawienia" (settings). A more accurate UI term is "kontrolki" or "elementy sterujące". Also keep exactly one ampersand for the shortcut.

Correct translation:
Włącz kontrolki &PSBT
```

<!-- cache_translation_check_pl_da57b633b7b7166174ba941fbaf3757ed55182ff111ae303ee7e3e60b02f34bd -->
```
        <source>User Interface &amp;language:</source>
        <translation>Język &amp;użytkownika:</translation>
    
ERR
The translation is inaccurate: it omits "interfejsu" and changes the meaning to "user's language" instead of "User Interface language." The ampersand is present exactly once, which is fine.

Correct translation:
&Język interfejsu użytkownika:
```

<!-- cache_translation_check_pl_62cb31a0ebb08f0cc8d0ef4f2fa55ed1a6708ab78451a293272f0ccf22dcf3ea -->
```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Wybierz podział jednostki pokazywany w interfejsie oraz podczas wysyłania monet</translation>
    
ERR
The translation is ungrammatical and slightly changes the meaning. It should specify "domyślną jednostkę podziału" and agree in gender/number. It also misses the final period.

Correct translation:
Wybierz domyślną jednostkę podziału wyświetlaną w interfejsie oraz podczas wysyłania monet.
```

<!-- cache_translation_check_pl_cbd68e94c390819e6422a5eeed61a1214170969e52bcf683402349ec28644ccf -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Użyj oddzielnego proxy SOCKS&amp;5 aby osiągnąć węzły w ukrytych usługach Tor:</translation>
    
ERR
The verb choice "osiągnąć węzły" is unnatural; "połączyć się z węzłami" is correct. Also, "ukryte usługi" should reflect "onion services" explicitly. Missing comma before "aby" in Polish style.

Correct translation:
Użyj oddzielnego proxy SOCKS&5, aby połączyć się z węzłami poprzez usługi onion w sieci Tor:
```

<!-- cache_translation_check_pl_43466b08a2a860125274d947ccbdb4ee826d3ccf9343a4f96d4cdb291bf4e161 -->
```
        <source>PSBT saved to disk.</source>
        <translation>PSBT zapisana na dysk.</translation>
    
ERR
Grammatical error in Polish; the sentence lacks the auxiliary or impersonal form.

Correct translation:
PSBT zapisano na dysk.
```

<!-- cache_translation_check_pl_4b7180861a679f9da57f73e7aa557438983fc5a7eb1fe0dd513a0bf123d30cb1 -->
```
        <source>Transaction is fully signed and ready for broadcast.</source>
        <translation>Transakcja została pomyślnie podpisana. Jest gotowa do rozgłoszenia.</translation>
    
ERR
"Fully signed" means "w pełni podpisana," not "pomyślnie podpisana" (successfully). The latter changes the meaning.

Correct translation:
Transakcja jest w pełni podpisana i gotowa do rozgłoszenia.
```

<!-- cache_translation_check_pl_707964f18bcef2a0a3f6a31ac40f311461b0d4ce56472f72f51329be65d66200 -->
```
        <source>Inbound</source>
        <extracomment>An Inbound Connection from a Peer.</extracomment>
        <translation>Przychodzący</translation>
    
ERR
The Polish adjective should agree with the implied noun "połączenie" (neuter). "Przychodzący" (masculine) is grammatically off in this context.

Correct translation:
Przychodzące
```

<!-- cache_translation_check_pl_b5272f4e0924567c9db94d5795ab7422227543831d3c7fca0f0317961159d908 -->
```
        <source>Outbound</source>
        <extracomment>An Outbound Connection to a Peer.</extracomment>
        <translation>Wychodzący</translation>
    
ERR
The Polish term should match the common UI label for connection direction. "Wychodzące" is the natural form used for categories like connections or messages. "Wychodzący" sounds like an adjective modifying a masculine noun and is less appropriate as a standalone label.

Correct translation:
Wychodzące
```

<!-- cache_translation_check_pl_7c443cbfe29a5e3b749356d461803e53a619e8c10b9444483fdf2b8fb08eab95 -->
```
        <source>Whether we relay transactions to this peer.</source>
        <translation>Czy przekazujemy transakcje do tego węzła zdalnego.</translation>
    
ERR
The translation adds "zdalnego" (remote), which is not in the source. Also, using the dative is more natural here.

Correct translation:
Czy przekazujemy transakcje temu węzłowi.
```

<!-- cache_translation_check_pl_9ff216abfd65af9e4652e53f0ec19e800316b660899307a9407f10c6c5a32542 -->
```
        <source>Whether we relay addresses to this peer.</source>
        <extracomment>Tooltip text for the Address Relay field in the peer details area, which displays whether we relay addresses to this peer (Yes/No).</extracomment>
        <translation>Czy przekazujemy transakcje do tego węzła zdalnego.</translation>
    
ERR
The translation incorrectly mentions "transakcje" (transactions) instead of "adresy" (addresses) and slightly awkward phrasing.

Correct translation:
Czy przekazujemy adresy temu węzłowi.
```

<!-- cache_translation_check_pl_fe0929c0872c4efaf9f19ff2af6f1f9cc323a51ebc6403591aa3a9dab5db4d26 -->
```
        <source>Totals</source>
        <translation>Łączna ilość</translation>
    
ERR
"Łączna ilość" is singular and implies "quantity," which is not ideal for a general totals label. A more natural Polish UI label is:
Razem
```

<!-- cache_translation_check_pl_bfa3a06d33b01007b837ad6568182f874ff788c07351d9ccbf7a9ad4e997971e -->
```
        <source>Inbound: initiated by peer</source>
        <extracomment>Explanatory text for an inbound peer connection.</extracomment>
        <translation>Przychodzący: zainicjowane przez węzeł zdalny</translation>
    
ERR
Grammatical agreement is off and the noun is missing; it should specify "połączenie" (connection).
Correct translation:
Połączenie przychodzące: zainicjowane przez węzeł zdalny
```

<!-- cache_translation_check_pl_1ea5f5c488380942bf5e399ba6f5e76808b433814a4f9dba332e0ff5986e4513 -->
```
        <source>&amp;Amount:</source>
        <translation>&amp;Ilość:</translation>
    
ERR
In financial/Bitcoin context, "Amount" should be translated as "Kwota", not "Ilość".

Correct translation:
&Kwota:
```

<!-- cache_translation_check_pl_7af98a4ae2d84bc8e4bf9bfa26579ffc357b38656cf1fa3aa956effd160839d6 -->
```
        <source>Wallet:</source>
        <translation>Portfel: </translation>
    
ERR
Unnecessary trailing space after the colon.

Correct translation:
Portfel:
```

<!-- cache_translation_check_pl_c262f14104c68dcc0674cfbff14f9f146236c60b96b96171618c93282bdd2e6b -->
```
        <source>S&amp;end</source>
        <translation>Wy&amp;syłka</translation>
    
ERR
"Wysyłka" is a noun and sounds unnatural for a button/menu command; the imperative "Wyślij" is preferred. Keep exactly one accelerator.
Correct translation:
&Wyślij
```

<!-- cache_translation_check_pl_646cc3e7e10973cd460d0358e6c18f7bd1a9585d21ea30c3f28788beb65b5279 -->
```
        <source>PSBT saved to disk</source>
        <translation>PSBT zapisana na dysk.</translation>
    
ERR
Grammatical agreement is off; “PSBT zapisana” sounds incorrect. Use impersonal form.
Correct translation:
PSBT zapisano na dysk
```

<!-- cache_translation_check_pl_58c51320cc212d19c8693b07d4535ce33042475cea90b15a23a969695b0dd608 -->
```
        <source>Verify the message to ensure it was signed with the specified Bitcoin address</source>
        <translation>Zweryfikuj wiadomość, aby upewnić się, że została podpisana odpowiednim adresem Bitcoin.</translation>
    
ERR
"specified" was mistranslated as "odpowiednim" (appropriate). It should be "określonym"/"wskazanym" to match the source.

Correct translation:
Zweryfikuj wiadomość, aby upewnić się, że została podpisana wskazanym adresem Bitcoin.
```

<!-- cache_translation_check_pl_24b56163fb69849279f7f3cf3178706c9ff4d60d47593cfd7f96fa6c51335cd1 -->
```
        <source>Total credit</source>
        <translation>Uznania ogółem</translation>
    
ERR
The Polish phrasing "Uznania ogółem" is understandable but unnatural in UI/accounting context. A more standard translation is:
Suma uznań
```

<!-- cache_translation_check_pl_4b402a8c28af4abe167ec97b99f0507edbb1dc10199bb71b6aa677d48697e2ca -->
```
        <source>Generated coins must mature %1 blocks before they can be spent. When you generated this block, it was broadcast to the network to be added to the block chain. If it fails to get into the chain, its state will change to "not accepted" and it won't be spendable. This may occasionally happen if another node generates a block within a few seconds of yours.</source>
        <translation>Wygenerowane monety muszą dojrzeć przez %1 bloków, zanim będzie można je wydać. Kiedy wygenerowano ten blok, został on rozesłany do sieci w celu dodania go do łańcucha bloków. Jeśli nie zostanie dodany do łańcucha, jego status zmieni się na „niezaakceptowany” i nie będzie można go wydać. Może się to czasami zdarzyć, jeśli inny węzeł wygeneruje blok w ciągu kilku sekund od Twojego.</translation>
    
ERR
Inconsistent person: the translation switches from impersonal ("Kiedy wygenerowano ten blok") to second person ("Twojego"). Make the whole passage consistently second person. 

Correct translation:
Wygenerowane monety muszą dojrzeć przez %1 bloków, zanim będzie można je wydać. Gdy wygenerowałeś(-aś) ten blok, został on rozesłany do sieci w celu dodania go do łańcucha bloków. Jeśli nie zostanie dodany do łańcucha, jego status zmieni się na „niezaakceptowany” i nie będzie można go wydać. Może się to czasami zdarzyć, jeśli inny węzeł wygeneruje blok w ciągu kilku sekund od Twojego.
```

<!-- cache_translation_check_pl_5c38b182efdd0e407071dbc7b03a5e2f1d554b93d69f4c74bba21cbea295115c -->
```
        <source>The %s developers</source>
        <translation>Deweloperzy %s </translation>
    
ERR
There is an extra trailing space in the translation.

Correct translation:
Deweloperzy %s
```

<!-- cache_translation_check_pl_942426a03e0665141a23c01a3f805056ccba19adf8ee1c4504fa1a991e3838e7 -->
```
        <source>%s request to listen on port %u. This port is considered "bad" and thus it is unlikely that any peer will connect to it. See doc/p2p-bad-ports.md for details and a full list.</source>
        <translation>%s żąda nasłuchiwania na porcie %u. Ten port jest uznany za "zły" i nie jest zbyt prawdopodobne, aby jakikolwiek węzeł połączył się do niego. Zobacz doc/p2p-bad-ports.md, aby dowiedzieć się więcej i zobaczyć pełną listę.</translation>
    
ERR
The phrase "połączył się do niego" is ungrammatical in Polish; it should be "połączył się z nim". Slight style adjustments improve clarity.

Correct translation:
%s żąda nasłuchiwania na porcie %u. Ten port jest uznany za "zły" i dlatego jest mało prawdopodobne, że jakikolwiek węzeł połączy się z nim. Zobacz doc/p2p-bad-ports.md, aby uzyskać szczegóły i pełną listę.
```

<!-- cache_translation_check_pl_6f80ed8d081bf722568d594b850a5cacda886e0ef97b93d4713f3f577b5afaf9 -->
```
        <source>Total length of network version string (%i) exceeds maximum length (%i). Reduce the number or size of uacomments.</source>
        <translation>Całkowita długość łańcucha wersji (%i) przekracza maksymalną dopuszczalną długość (%i). Zmniejsz ilość lub rozmiar parametru uacomments.</translation>
    
ERR
The translation omits "network" and uses "łańcucha" (chain) instead of the more accurate "ciągu/napisu" for "string." Also, "liczbę" is preferable to "ilość."

Correct translation:
Całkowita długość ciągu wersji sieci (%i) przekracza maksymalną długość (%i). Zmniejsz liczbę lub rozmiar uacomments.
```

<!-- cache_translation_check_pl_397571f91528122dbdb1d36f41004fda644c91a00dcbdbbea5f26d1f58f42604 -->
```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Uwaga: Wykryto klucze prywatne w portfelu {%s} który ma wyłączone klucze prywatne</translation>
    
ERR
Missing comma before "który" and style: "Warning" is better translated as "Ostrzeżenie". A more natural phrasing avoids repeating "klucze prywatne".

Correct translation:
Ostrzeżenie: Wykryto klucze prywatne w portfelu {%s} z wyłączonymi kluczami prywatnymi
```

<!-- cache_translation_check_pl_6ad5890d9c16e8d86804ba587ea12b5b7bab68207d392b704b51069d4b9b9b4a -->
```
        <source>Flushing undo file to disk failed. This is likely the result of an I/O error.</source>
        <translation>Nie udało się zapisać pliku cofającego na dysk. Prawdopodobnie jest to wynik błędu operacji wejścia/wyjścia (I/O).</translation>
    
ERR
"plik cofającego" is ungrammatical; it should be "plik cofania" (or "plik undo"). Also, "flushing" is better rendered as flushing/writing buffers rather than simply "zapisać plik".

Correct translation:
Opróżnienie buforów pliku cofania na dysk nie powiodło się. Prawdopodobnie jest to wynik błędu operacji wejścia/wyjścia (I/O).
```

<!-- cache_translation_check_pl_8684c92433eec828bfd4f67b1a677fcae5e48ebfcada7328eb6d1b90dfaf8e25 -->
```
        <source>Options '-datacarrier' or '-datacarriersize' are set but are marked as deprecated. They will be removed in a future version.</source>
        <translation>Opcje '-datacarrier' lub '-datacarriersize' są oznaczone jako przestarzałe. Zostaną usunięte w przyszłej wersji.</translation>
    
ERR
The translation omits the "are set" part, changing the meaning.

Correct translation:
Opcje '-datacarrier' lub '-datacarriersize' zostały ustawione, ale są oznaczone jako przestarzałe. Zostaną usunięte w przyszłej wersji.
```

<!-- cache_translation_check_pl_b0b043f79190694630d4aec33a0e3a9aa3de6e83b06a6902e24824b17fc89eee -->
```
        <source>Could not top up scriptPubKeys</source>
        <translation>Nie można doładować scriptPubKeys</translation>
    
ERR
"Doładować" implies recharging (e.g., phone balance) and is inappropriate here. "Top up" in this context means "uzupełnić"/"dopełnić".

Correct translation:
Nie można uzupełnić scriptPubKeys
```

<!-- cache_translation_check_pl_2332f2fc322143d80c10f29f3c7799d7bfaaa5d25d426e4f625ac08159bb2a3e -->
```
        <source>Failed to acquire rescan reserver during wallet initialization</source>
        <translation>Nie udało się uzyskać rezerwacji stanu ponownego skanowania podczas inicjalizacji portfela.</translation>
    
ERR
"rescan reserver" was mistranslated as "rezerwacji stanu ponownego skanowania"; the added word "stanu" (state) is incorrect and changes the meaning.

Correct translation:
Nie udało się uzyskać rezerwacji ponownego skanowania podczas inicjalizacji portfela.
```

<!-- cache_translation_check_pl_2a1a8aff65452a651da21bb387dc2d0f2e914f53eeb0b3f36efb0ba5551ea523 -->
```
        <source>Failed to close block undo file.</source>
        <translation>Nie udało się zamknąć pliku danych cofających.</translation>
    
ERR
"plik danych cofających" is ungrammatical and unnatural. A clearer, accurate rendering of "block undo file" is "plik cofania bloków."

Correct translation:
Nie udało się zamknąć pliku cofania bloków.
```

<!-- cache_translation_check_pl_64e731f981394618260408bc0d9eea224a4773151ebb0c7aa03a890aa3666c9f -->
```
        <source>Loading wallet…</source>
        <translation>Ładowanie portfeli…</translation>
    
ERR
Number mismatch: source is singular "wallet", translation uses plural "portfeli".

Correct translation:
Ładowanie portfela…
```

<!-- cache_translation_check_pl_349a059b49832108f1798beec52cbd924b9e003e85a8f76b6f8de86832a23614 -->
```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>acceptstalefeeestimates nie jest wspierany na łańcuchu %s</translation>
    
ERR
Stylistic and grammatical issues: "wspierany" is less appropriate than "obsługiwane" for a feature/option, and a period is missing. Preposition "w" fits better here.
Correct translation:
acceptstalefeeestimates nie jest obsługiwane w łańcuchu %s.
```
</details>

Number of issues: 48.
