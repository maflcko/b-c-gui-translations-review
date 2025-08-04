# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>pl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bpl%5D%20low%20quality)


```
        <source>Encrypt wallet</source>
        <translation>Zaszyfruj portfel </translation>
    
YES
The translation has a trailing whitespace.
Correct translation: Zaszyfruj portfel
```

```
        <source>Change passphrase</source>
        <translation>Zmień hasło </translation>
    
YES
The translation contains a trailing space.
Correct translation: Zmień hasło
```

```
        <source>Wallet encrypted</source>
        <translation>Portfel zaszyfrowany </translation>
    
YES. The translation has a trailing space.
Correct translation: Portfel zaszyfrowany
```

```
        <source>Open a bitcoin: URI</source>
        <translation>Otwórz URI</translation>
    
YES The translation is incomplete. It omits the "bitcoin:" part, which specifies the type of URI.

Correct translation: Otwórz URI bitcoin:
```

```
        <source>Are you sure you wish to close all wallets?</source>
        <translation>Na pewno zamknąć wszystkie portfe?</translation>
    
YES
The word "portfe" is a grammatical error. The correct plural form of "portfel" (wallet) is "portfele".

Correct translation:
Na pewno zamknąć wszystkie portfele?
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Co najmniej %1 GB danych, zostanie zapisane w tym katalogu, dane te będą przyrastały w czasie.</translation>
    
YES, The translation contains a grammatical error: an unnecessary comma after "danych", which incorrectly separates the subject from the verb. The overall sentence structure is also slightly unnatural.

Correct translation:
Co najmniej %1 GB danych zostanie zapisanych w tym katalogu, a ich ilość będzie z czasem rosła.
```

```
        <source>Maximum database cache size. Make sure you have enough RAM. A larger cache can contribute to faster sync, after which the benefit is less pronounced for most use cases. Lowering the cache size will reduce memory usage. Unused mempool memory is shared for this cache.</source>
        <extracomment>Tooltip text for Options window setting that sets the size of the database cache. Explains the corresponding effects of increasing/decreasing this value.</extracomment>
        <translation>Maksymalna wielkość pamięci podręcznej dla bazy danych osiągnięta. Upewnij się, że masz odpowiednią ilość pamięci RAM. Większa ilość pamięci podręcznej może przyśpieszyć synchronizację, z mniejszym wpływem w większości przypadków. Zmniejszenie wielkości tej pamięci zredukuje użycie pamięci. Nieużywana pamięć mempool jest współdzielona z cache.</translation>
    
YES, The first sentence incorrectly translates the setting's title "Maximum database cache size" as a status message "Maksymalna wielkość ... osiągnięta" (Maximum size ... reached). Additionally, the translation of "after which the benefit is less pronounced" is imprecise, losing the sequential meaning.

Maksymalny rozmiar pamięci podręcznej bazy danych. Upewnij się, że masz wystarczająco dużo pamięci RAM. Większa pamięć podręczna może przyczynić się do szybszej synchronizacji, po której korzyść jest mniej odczuwalna w większości przypadków. Zmniejszenie rozmiaru pamięci podręcznej zredukuje zużycie pamięci. Nieużywana pamięć puli pamięci (mempool) jest współdzielona na potrzeby tej pamięci podręcznej.
```

```
        <source>(But this wallet does not have the right keys.)</source>
        <translation>(Ale ten portfel nie posiada wlaściwych kluczy.)</translation>
    
YES, The word "wlaściwych" is misspelled. It should be "właściwych".
(Ale ten portfel nie posiada właściwych kluczy.)
```

```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>Opcjonalna kwota by zażądać. Zostaw puste lub zero by nie zażądać konkretnej kwoty.</translation>
    
YES, The first part of the translation, "Opcjonalna kwota by zażądać", is grammatically awkward and unnatural. The construction "by + infinitive" is incorrect in this context. A proper way to express this would be using a noun phrase or a "do + gerund" structure.

Correct translation:
Opcjonalna kwota do zażądania. Pozostaw to pole puste lub wpisz zero, aby nie żądać określonej kwoty.
```

```
        <source>Custom change address</source>
        <translation>Niestandardowe zmiany adresu</translation>
    
YES, The translation is incorrect. The word "change" in the context of a transaction means the remainder ("reszta" in Polish), not an alteration ("zmiana"). The current translation "Niestandardowe zmiany adresu" means "Non-standard changes of an address", which is wrong. The correct translation should refer to a custom address for the transaction change.

Correct translation:
Niestandardowy adres reszty
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Korzystanie z opłaty domyślnej (fallbackfree) może skutkować wysłaniem transakcji, która potwierdzi się w kilka godzin lub dni (lub nigdy). Rozważ wybranie opłaty ręcznie lub poczekaj, aż sprawdzisz poprawność całego łańcucha.</translation>
    
YES
The translation contains a typo. The English term "fallbackfee" has been misspelled as "fallbackfree" in the Polish translation.

Correct translation:
Korzystanie z opłaty domyślnej (fallbackfee) może skutkować wysłaniem transakcji, która potwierdzi się w kilka godzin lub dni (lub nigdy). Rozważ wybranie opłaty ręcznie lub poczekaj, aż sprawdzisz poprawność całego łańcucha.
```

```
        <source>Copy bytes</source>
        <translation>Kopiuj ilość bajtów</translation>
    
YES. The translation adds the word "ilość" (amount/quantity), which changes the meaning. "Copy bytes" implies copying the actual byte data, while "Kopiuj ilość bajtów" means "Copy the amount/number of bytes".

Kopiuj bajty
```

```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Duplikat adres-u znaleziony: adresy powinny zostać użyte tylko raz.</translation>
    
YES
The word "adres-u" is grammatically incorrect due to the hyphen. The correct genitive form is "adresu". Additionally, the word order in the first part is unnatural.
Correct translation: Znaleziono duplikat adresu: adresy powinny zostać użyte tylko raz.
```

```
        <source>0/unconfirmed, not in memory pool</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that is not in the memory pool.</extracomment>
        <translation>0/niepotwierdzone, nie wysłane do kolejki w pamięci</translation>
    
YES, The translation interprets the state rather than translating it directly, which can be misleading.

"nie wysłane do kolejki w pamięci" translates to "not sent to the queue in memory". The original English "not in memory pool" is a statement of the transaction's current state. It might not be in the memory pool for reasons other than not being sent (e.g., it was rejected by nodes). A more accurate and standard translation for "not in memory pool" in Polish Bitcoin terminology is "nie w puli pamięci".

Correct translation:
<translation>0/niepotwierdzone, nie w puli pamięci</translation>
```

```
        <source>No wallet has been loaded.
Go to File &gt; Open Wallet to load a wallet.
- OR -</source>
        <translation>Portfel nie został wybrany.
Przejdź do Plik &gt; Otwórz Portfel aby wgrać portfel.</translation>
    
YES, The translation is problematic. It is incomplete and uses suboptimal wording.

The phrase "- OR -" is completely missing from the translation. Additionally, the verb "to load" is translated first as "wybrany" (selected) and then "wgrać" (to upload), while a more accurate and consistent term would be "wczytać" (to load).

A corrected translation would be:
Nie wczytano portfela.
Przejdź do Plik &gt; Otwórz Portfel, aby wczytać portfel.
- LUB -
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>PSBT musi być mniejsze niż 100MiB</translation>
    
YES
The translation omits the word "file" ("plik") from the source text. It also has a whitespace issue, as there should be a space between the number and the unit (100 MiB). A more accurate translation would also adjust the adjective's gender to match "plik" (masculine).

Correct translation:
Plik PSBT musi być mniejszy niż 100 MiB
```

```
        <source>Warning: This may pay the additional fee by reducing change outputs or adding inputs, when necessary. It may add a new change output if one does not already exist. These changes may potentially leak privacy.</source>
        <translation>Ostrzeżenie: Może to spowodować uiszczenie dodatkowej opłaty poprzez zmniejszenie zmian wyjść lub dodanie danych wejściowych, jeśli jest to konieczne. Może dodać nowe wyjście zmiany, jeśli jeszcze nie istnieje. Te zmiany mogą potencjalnie spowodować utratę prywatności.</translation>
    
YES, The translation incorrectly translates the Bitcoin-specific term "change" (as in leftover funds from a transaction). It uses the word "zmiana" (which means 'a modification' or 'a shift'), while the correct Polish term in this context is "reszta". This makes the translation confusing and technically incorrect.

Corrected translation:
Ostrzeżenie: Może to spowodować uiszczenie dodatkowej opłaty poprzez zmniejszenie wyjść reszty lub dodanie wejść, gdy jest to konieczne. Może zostać dodane nowe wyjście reszty, jeśli jeszcze nie istnieje. Te zmiany mogą potencjalnie naruszyć prywatność.
```

```
        <source>Cannot downgrade wallet from version %i to version %i. Wallet version unchanged.</source>
        <translation>Nie można zmienić wersji portfela z wersji %ina wersje %i. Wersja portfela pozostaje niezmieniona.</translation>
    
YES, W słowie „%ina” brakuje spacji między specyfikatorem formatu a słowem „na”. Dodatkowo, słowo „zmienić” jest mniej precyzyjne niż „obniżyć” w kontekście „downgrade”, a forma „wersje” jest niepoprawna gramatycznie – powinna być „wersję”.

Correct translation:
Nie można obniżyć wersji portfela z %i do %i. Wersja portfela pozostaje niezmieniona.
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>Nie można zaktualizować portfela dzielonego innego niż HD z wersji 1%i do wersji 1%i bez aktualizacji w celu obsługi wstępnie podzielonej puli kluczy. Użyj wersji 1%i lub nie określono wersji.</translation>
    
YES
The format specifiers `%i` are incorrectly written as `1%i` in the translation. This will cause the application to display incorrect version numbers. Additionally, the phrasing "innego niż HD" is slightly awkward, and the final clause "lub nie określono wersji" is grammatically inconsistent with the preceding imperative "Użyj".

Correct translation:
Nie można zaktualizować portfela dzielonego nie-HD z wersji %i do wersji %i bez aktualizacji w celu obsługi wstępnie podzielonej puli kluczy. Użyj wersji %i lub nie określaj wersji.
```

```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Błąd: wersja pliku zrzutu nie jest obsługiwana. Ta wersja bitcoin-wallet obsługuje tylko pliki zrzutów w wersji 1. Mam plik zrzutu w wersji 1%s</translation>
    
YES
The last part of the sentence is translated incorrectly. The phrase "Got dumpfile with version %s" was translated to "Mam plik zrzutu w wersji 1%s", which is wrong. It should be "Otrzymano plik zrzutu w wersji %s" or "Znaleziono plik zrzutu w wersji %s". The translator mistakenly added the number "1" before the format specifier `%s`.

Correct translation:
Błąd: wersja pliku zrzutu nie jest obsługiwana. Ta wersja bitcoin-wallet obsługuje tylko pliki zrzutów w wersji 1. Otrzymano plik zrzutu w wersji %s
```

```
        <source>Error: Unable to produce descriptors for this legacy wallet. Make sure to provide the wallet's passphrase if it is encrypted.</source>
        <translation>Błąd: Nie można wygenerować deskryptorów dla tego starego portfela. Upewnij się najpierw, że portfel jest odblokowany.</translation>
    
YES
The translation of the second sentence is inaccurate. It changes the specific instruction "Make sure to provide the wallet's passphrase if it is encrypted" to a more general and less helpful "Make sure first that the wallet is unlocked". This omits the key information about the passphrase and the condition of the wallet being encrypted.

Correct translation:
Błąd: Nie można wygenerować deskryptorów dla tego starego portfela. Upewnij się, że podajesz hasło do portfela, jeśli jest on zaszyfrowany.
```

```
        <source>Prune mode is incompatible with -reindex-chainstate. Use full -reindex instead.</source>
        <translation>Tryb przycięty jest niekompatybilny z -reindex-chainstate. Użyj pełnego  -reindex.</translation>
    
YES
There is a double space before "-reindex".
Correct translation: Tryb przycięty jest niekompatybilny z -reindex-chainstate. Użyj pełnego -reindex.
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Nieobsługiwany poziom logowania specyficzny dla kategorii %1$s=%2$s. Oczekiwano %1$s=&lt;category&gt;:&lt;loglevel&gt;. Poprawne kategorie %3$s. Poprawne poziomy logowania: %4 $s.</translation>
    
YES, The format specifier `%4 $s` contains an extra space before `$s`. Additionally, a colon is missing after "kategorie" for better consistency.

Correct translation:
Nieobsługiwany poziom logowania specyficzny dla kategorii %1$s=%2$s. Oczekiwano %1$s=&lt;category&gt;:&lt;loglevel&gt;. Poprawne kategorie: %3$s. Poprawne poziomy logowania: %4$s.
```

```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on enormous cluster of unconfirmed transactions.</source>
        <translation>Nie udało się obliczyć opłat za uderzenia, ponieważ niepotwierdzone UTXO zależą od ogromnego skupiska niepotwierdzonych transakcji.</translation>
    
YES, "opłat za uderzenia" is an incorrect, literal translation of "bump fees". In Polish, "uderzenia" means "strikes" or "hits", which is nonsensical in this context. The correct term for fee bumping is "podbicie opłaty" or "zwiększenie opłaty".

Correct translation:
Nie udało się obliczyć opłat za podbicie, ponieważ niepotwierdzone UTXO zależą od ogromnego skupiska niepotwierdzonych transakcji.
```

```
        <source>Specified -blockmaxweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Podany -blockmaxweight (%d) przekracza przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)</translation>
    
YES, the word "przekracza" is duplicated.

Podany -blockmaxweight (%d) przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)
```

```
        <source>Specified -blockreservedweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Podany -blockreservedweight (%d) przekracza przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)</translation>
    
YES
The word "przekracza" is duplicated.
Correct translation: Podany -blockreservedweight (%d) przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)
```

```
        <source>Error: Got key that was not hex: %s</source>
        <translation>Błąd: Otrzymana wartość nie jest szestnastkowa%s</translation>
    
YES, The translation is missing a colon and a space before the format specifier. The word "wartość" (value) is used instead of the more direct "klucz" (key).

Correct translation:
Błąd: Otrzymany klucz nie jest szesnastkowy: %s
```

```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Błąd: Otrzymana wartość nie jest szestnastkowa%s</translation>
    
YES
The translation is missing a colon and a space before the %s format specifier. Additionally, there is a typo in the word "szesnastkowa".
Correct translation: Błąd: Otrzymana wartość nie jest szesnastkowa: %s
```

```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>Błąd: Pula kluczy jest pusta, odwołaj się do puli kluczy.</translation>
    
YES, The translation incorrectly translates the instruction "please call keypoolrefill first". "Odwołaj się do puli kluczy" means "refer to the keypool", which is a vague and incorrect instruction. It omits the specific function name `keypoolrefill` and uses the wrong verb for invoking a function.

Correct translation:
Błąd: Pula kluczy została wyczerpana, najpierw wywołaj keypoolrefill.
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>Portfel będzie unikał płacenia mniejszej niż przekazana opłaty.</translation>
    
YES
The translation is inaccurate. It omits the word "minimum" and translates "relay fee" incorrectly as "przekazana opłata" (the relayed/transferred fee), which changes the meaning of the sentence. The correct translation should specify the "minimum relay fee".

Correct translation:
Portfel będzie unikał płacenia opłaty niższej niż minimalna opłata za przekazanie.
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>Kwota transakcji musi być dodatnia</translation>
    
YES
The translation is not precise. The source "must not be negative" means the value can be zero or positive. The translation "musi być dodatnia" means "must be positive", which excludes zero.

Correct translation: Kwoty transakcji nie mogą być ujemne.
```

```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Zbyt mało dostępnych deskryptorów plików. %d dostępnych, %d wymaganych. </translation>
    
YES The translation has a trailing space at the end.
Zbyt mało dostępnych deskryptorów plików. %d dostępnych, %d wymaganych.
```
</details>
