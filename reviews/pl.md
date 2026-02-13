# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



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

<!-- cache_translation_check_pl_9a7b6b6510aeff2bfaa110854cdfeb85ba8f9befc0425afb6842a873786c7738 -->
```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>Wychodzące połączenie testowe: krótkotrwałe, do testowania adresów</translation>
    
ERR
The translation is overly verbose and introduces "wychodzące" (outbound), which is not stated in the source. This label should be concise.
Correct translation:
Sonda
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

<!-- cache_translation_check_pl_c9b0d7be83a1973305a1a0a8301d39b7d169fa439c4df5c2acee90e78a568cbf -->
```
        <source>&amp;Copy address</source>
        <translation>Kopiuj adres</translation>
    
ERR
Missing shortcut marker '&' in the translation.

Correct translation:
&Kopiuj adres
```

<!-- cache_translation_check_pl_5d465186f4c1b9416f4809df08adbbed22e5bfe18d24720fddbe4cad4b1c2f14 -->
```
        <source>Copy &amp;label</source>
        <translation>Kopiuj etykietę</translation>
    
ERR
Missing ampersand for the shortcut key. There must be exactly one '&' in the translation.

Correct translation:
Kopiuj &etykietę
```

<!-- cache_translation_check_pl_2aab17c96a5a3f1e2898aee8ff5002a1e01db1b07aa09c61a24933b72c149d4a -->
```
        <source>Copy &amp;amount</source>
        <translation>Kopiuj kwotę</translation>
    
ERR
The accelerator indicator '&' from the source is missing. It must appear exactly once in the translation.

Correct translation:
Kopiuj &kwotę
```

<!-- cache_translation_check_pl_b43831ab599a514471ca055eccb9bbd15f68fc3cfc077866eeb9d8290f7abdea -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Skompilowany bez obsługi podpisywania zewnętrznego (wymagany do podpisywania zewnętrzengo)</translation>
    
ERR
The Polish translation contains a typo: "zewnętrzengo" should be "zewnętrznego". Additionally, the adjective "Skompilowany" (masculine) should ideally be "Skompilowano" (impersonal) or "Program skompilowany" to match common software terminology, and the masculine "wymagany" does not agree with the feminine noun "obsługa" (support) it refers to.

Correct translation:
Skompilowano bez obsługi zewnętrznego podpisania (wymaganej do zewnętrznego podpisania)
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

<!-- cache_translation_check_pl_b43831ab599a514471ca055eccb9bbd15f68fc3cfc077866eeb9d8290f7abdea -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Skompilowany bez obsługi podpisywania zewnętrznego (wymagany do podpisywania zewnętrzengo)</translation>
    
ERR
The Polish translation contains a typo: "zewnętrzengo" should be "zewnętrznego". Additionally, the adjective "Skompilowany" (masculine) should ideally be "Skompilowano" (impersonal) or "Program skompilowany" to match common software terminology, and the masculine "wymagany" does not agree with the feminine noun "obsługa" (support) it refers to.

Correct translation:
Skompilowano bez obsługi zewnętrznego podpisania (wymaganej do zewnętrznego podpisania)
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

<!-- cache_translation_check_pl_fef09b8b05715a58f52b909683afc239b43d5c34ecf7529668f34526df2d10cf -->
```
        <source>Clear console</source>
        <translation>Wyczyść konosolę</translation>
    
ERR
The Polish word for "console" (in the accusative case) is "konsolę". The provided translation contains a typo: "konosolę".

Correct translation:
Wyczyść konsolę
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

<!-- cache_translation_check_pl_f431407ec4e4cd6eb0e90547b4936b462f80c82023fc95829dd3a1812278ef84 -->
```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Wpisz adres, wiadomość oraz sygnaturę (podpis) odbiorcy (upewnij się, że dokładnie skopiujesz wszystkie zakończenia linii, spacje, tabulacje itp.). Uważaj by nie dodać więcej do podpisu niż do samej podpisywanej wiadomości by uniknąć ataku man-in-the-middle. 
Zwróć uwagę, że poprawnie zweryfikowana wiadomość potwierdza to, że nadawca posiada klucz do adresu, natomiast nie potwierdza to, że poprawne wysłanie jakiejkolwiek transakcji!</translation>
    
ERR
- The parenthetical about copying whitespace is attached to "signature" and "odbiorcy", making it ambiguous; it should modify "message" only.
- The phrase "Uważaj by nie dodać więcej do podpisu..." misrenders the meaning; it should be about not inferring more from the signature than the signed message states.
- Grammar/punctuation issues: missing commas after "Uważaj", awkward "by", and "natomiast nie potwierdza to, że poprawne wysłanie..." is ungrammatical.
- The translation introduces a line break not present in the source.

Correct translation:
Wpisz poniżej adres odbiorcy, wiadomość (upewnij się, że dokładnie skopiujesz podziały wierszy, spacje, tabulatory itp.) oraz podpis, aby zweryfikować wiadomość. Uważaj, aby nie doszukiwać się w podpisie więcej, niż wynika z samej podpisanej wiadomości, aby nie dać się oszukać atakiem typu man-in-the-middle. Zwróć uwagę, że dowodzi to jedynie, iż podpisujący kontroluje ten adres; nie dowodzi wysłania żadnej transakcji!
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

<!-- cache_translation_check_pl_f4838eb324c8c46eea35f8072e6bf0d91e28461f7f3d7d05a428205986740b67 -->
```
        <source>No wallet has been loaded.
Go to File &gt; Open Wallet to load a wallet.
- OR -</source>
        <translation>Portfel nie został wybrany.
Przejdź do Plik &gt; Otwórz Portfel aby wgrać portfel.</translation>
    
ERR
The translation is incomplete because it omits the final line "- OR -". Additionally, "loaded" is more accurately translated as "wczytany" or "załadowany" rather than "wybrany" (selected).

Correct translation:
Nie załadowano żadnego portfela.
Przejdź do Plik > Otwórz Portfel, aby wczytać portfel.
- LUB -
```

<!-- cache_translation_check_pl_f464a64504b94e35336d58cc7e09f94711fa36118b8e12cbfc679674098286f2 -->
```
        <source>Unable to decode PSBT from clipboard (invalid base64)</source>
        <translation>Nie udało się załadować częściowo podpisanej transakcji (nieważny base64)</translation>
    
ERR
The translation changes the meaning of "decode" to "załadować" (load) and replaces "PSBT" with its descriptive name "częściowo podpisanej transakcji" (partially signed transaction). While descriptive, it misses the specific technical term PSBT and the literal action of decoding. It also omits "ze schowka" (from clipboard).

Correct translation:
Nie udało się zdekodować PSBT ze schowka (nieprawidłowy base64)
```

<!-- cache_translation_check_pl_d0551a2e681d34e215b034ed3a1fa2d4bd4869b7d32fb747a55d7258b59e6d48 -->
```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>PSBT musi być mniejsze niż 100MB</translation>
    
ERR
The translation contains two issues:
1. The source specifically mentions "PSBT file", while the translation omits the word for "file" ("plik").
2. The unit "MiB" (mebibyte) was changed to "MB" (megabyte), which are technically different units.
3. Grammatically, if "plik" (masculine) is used, the adjective should be "mniejszy". In the current translation, "PSBT" is treated as neuter ("mniejsze"), but "PSBT" (Partially Signed Bitcoin Transaction) is usually referred to as "transakcja" (feminine - "mniejsza") or "plik PSBT" (masculine - "mniejszy").

Correct translation:
Plik PSBT musi być mniejszy niż 100 MiB
```

<!-- cache_translation_check_pl_43cd3904f1c89821899451216d1f0bf9f2b53efbe29df5921c2e242e42499516 -->
```
        <source>Warning: This may pay the additional fee by reducing change outputs or adding inputs, when necessary. It may add a new change output if one does not already exist. These changes may potentially leak privacy.</source>
        <translation>Ostrzeżenie: Może to spowodować uiszczenie dodatkowej opłaty poprzez zmniejszenie zmian wyjść lub dodanie danych wejściowych, jeśli jest to konieczne. Może dodać nowe wyjście zmiany, jeśli jeszcze nie istnieje. Te zmiany mogą potencjalnie spowodować utratę prywatności.</translation>
    
ERR
The translation of "change outputs" is problematic. In the context of Bitcoin, "change" refers to the amount returned to the sender, which is translated as "reszta". The current translation uses "zmian wyjść" and "wyjście zmiany", which are literal translations of the word "change" (as in "alteration" or "modification") and do not make sense in this technical context. Furthermore, "inputs" in transaction contexts are usually called "wejścia" rather than "dane wejściowe".

Correct translation:
Ostrzeżenie: Może to spowodować uiszczenie dodatkowej opłaty poprzez zmniejszenie wyjść reszty lub dodanie wejść, jeśli jest to konieczne. Może dodać nowe wyjście reszty, jeśli jeszcze nie istnieje. Zmiany te mogą potencjalnie naruszyć prywatność.
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

<!-- cache_translation_check_pl_0a68b984f4b907620b0ca2dab2ee064886fd9e38cd7ed34b9ea947d72d3f8d9e -->
```
        <source>Error: Unable to produce descriptors for this legacy wallet. Make sure to provide the wallet's passphrase if it is encrypted.</source>
        <translation>Błąd: Nie można wygenerować deskryptorów dla tego starego portfela. Upewnij się najpierw, że portfel jest odblokowany.</translation>
    
ERR
The translation is imprecise. The second sentence "Upewnij się najpierw, że portfel jest odblokowany" (Make sure first that the wallet is unlocked) deviates from the source instruction "Make sure to provide the wallet's passphrase if it is encrypted". While the meaning is similar in practice, the translation should more accurately reflect the instruction to provide a passphrase.

Correct translation:
Błąd: Nie można wygenerować deskryptorów dla tego portfela typu legacy. Upewnij się, że podano hasło portfela, jeśli jest on zaszyfrowany.
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

<!-- cache_translation_check_pl_7667ff88d5d0d18d8da72da1b251a9198303480b8e6e9a0f223503016030e083 -->
```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>opcja acceptstalefeeestimates nie są wspierane na łańcuchu %s</translation>
    
ERR
There is a grammatical mismatch in the translation. The word "opcja" (option) is singular, but the verb "są wspierane" (are supported) is plural. It should be singular: "nie jest wspierana". Additionally, the translation is missing the trailing period present in the source.

Correct translation:
opcja acceptstalefeeestimates nie jest wspierana na łańcuchu %s.
```
</details>

Number of issues: 44.
