# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.

<details><summary>pl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bpl%5D%20low%20quality)


```
        <source>Encrypt wallet</source>
        <translation>Zaszyfruj portfel </translation>
    
YES: The translation has an extra space at the end of the translated string.
Correct translation: Zaszyfruj portfel
```

```
        <source>Change passphrase</source>
        <translation>Zmień hasło </translation>
    
YES, The translation has an extra space at the end of the translated text.
Zmień hasło
```

```
        <source>Wallet encrypted</source>
        <translation>Portfel zaszyfrowany </translation>
    
YES: The translation has an extra space at the end.
Correct translation: Portfel zaszyfrowany
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>Wystąpił krytyczny błąd. Upewnij się, że plik ustawień można nadpisać lub uruchom klienta z parametrem -nosettings.</translation>
    
YES - The Polish translation uses "nadpisać" (overwrite) which is not the correct term for "writable" (do zapisu, z możliwością zapisu). The correct translation for "writable" in this context is "do zapisu" or "z możliwością zapisu".

Wystąpił krytyczny błąd. Upewnij się, że plik ustawień jest do zapisu, lub uruchom klienta z parametrem -nosettings.
```

```
        <source>Open a bitcoin: URI</source>
        <translation>Otwórz URI</translation>
    
YES, The translation is missing the word "bitcoin". The correct translation should be "Otwórz URI bitcoin:".
```

```
        <source>Are you sure you wish to close all wallets?</source>
        <translation>Na pewno zamknąć wszystkie portfe?</translation>
    
YES - The Polish translation is missing a proper word for "wallets" in this context. The word "portfele" should be used instead of "portfe".
Na pewno zamknąć wszystkie portfele?
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Co najmniej %1 GB danych, zostanie zapisane w tym katalogu, dane te będą przyrastały w czasie.</translation>
    
YES, The Polish translation is grammatically incorrect. The comma after %1 GB danych is misplaced and creates an awkward sentence structure. The phrase "dane te będą przyrastały w czasie" is also a bit clunky. A more natural phrasing would be "dane będą przyrastać w czasie" or "ich rozmiar będzie rósł w czasie".

Here's a corrected translation:

Co najmniej %1 GB danych zostanie zapisane w tym katalogu, a ich rozmiar będzie rósł w czasie.
```

```
        <source>Maximum database cache size. Make sure you have enough RAM. A larger cache can contribute to faster sync, after which the benefit is less pronounced for most use cases. Lowering the cache size will reduce memory usage. Unused mempool memory is shared for this cache.</source>
        <extracomment>Tooltip text for Options window setting that sets the size of the database cache. Explains the corresponding effects of increasing/decreasing this value.</extracomment>
        <translation>Maksymalna wielkość pamięci podręcznej dla bazy danych osiągnięta. Upewnij się, że masz odpowiednią ilość pamięci RAM. Większa ilość pamięci podręcznej może przyśpieszyć synchronizację, z mniejszym wpływem w większości przypadków. Zmniejszenie wielkości tej pamięci zredukuje użycie pamięci. Nieużywana pamięć mempool jest współdzielona z cache.</translation>
    
YES: The phrase "osiągnięta" (achieved) is inappropriate in this context. It should be removed to convey the intended meaning of "maximum size".
Maksymalna wielkość pamięci podręcznej dla bazy danych. Upewnij się, że masz odpowiednią ilość pamięci RAM. Większa ilość pamięci podręcznej może przyśpieszyć synchronizację, z mniejszym wpływem w większości przypadków. Zmniejszenie wielkości tej pamięci zredukuje użycie pamięci. Nieużywana pamięć mempool jest współdzielona z cache.
```

```
        <source>(But this wallet does not have the right keys.)</source>
        <translation>(Ale ten portfel nie posiada wlaściwych kluczy.)</translation>
    
YES - The translation contains a spelling error. The Polish word for "proper" or "right" should be "właściwych", not "wlaściwych".
(Ale ten portfel nie posiada właściwych kluczy.)
```

```
        <source>Ban for</source>
        <translation>Zbanuj na</translation>
    
YES, The translation is problematic. The Polish translation "Zbanuj na" literally means "Banned on" or "Ban on". In the context of Bitcoin, the English "Ban for" likely refers to the reason for a ban. A more accurate translation would be "Ban za" which translates to "Ban for" or "Ban because of".

Zbanuj na
```

```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>Opcjonalna kwota by zażądać. Zostaw puste lub zero by nie zażądać konkretnej kwoty.</translation>
    
YES - The grammar in the translation is incorrect. "by zażądać" should be "do zażądania" or "o zażądanie".
Opcjonalna kwota do zażądania. Zostaw puste lub zero, aby nie zażądać konkretnej kwoty.
```

```
        <source>Custom change address</source>
        <translation>Niestandardowe zmiany adresu</translation>
    
YES, The translation is problematic because it is inaccurate and nonsensical. In the context of Bitcoin, "change address" refers to an address used to return unspent amounts from a transaction. The provided Polish translation "Niestandardowe zmiany adresu" literally translates to "Custom changes of address," which does not convey the intended meaning.

NO
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Korzystanie z opłaty domyślnej (fallbackfree) może skutkować wysłaniem transakcji, która potwierdzi się w kilka godzin lub dni (lub nigdy). Rozważ wybranie opłaty ręcznie lub poczekaj, aż sprawdzisz poprawność całego łańcucha.</translation>
    
YES: The translation contains a typo ("fallbackfree" instead of "fallbackfee").
Correct translation: Korzystanie z opłaty domyślnej (fallbackfee) może skutkować wysłaniem transakcji, która potwierdzi się w kilka godzin lub dni (lub nigdy). Rozważ wybranie opłaty ręcznie lub poczekaj, aż sprawdzisz poprawność całego łańcucha.
```

```
        <source>Copy bytes</source>
        <translation>Kopiuj ilość bajtów</translation>
    
YES, The translation is inaccurate. "Bytes" in this context refers to raw data, not a quantity. The correct translation should reflect copying the byte data itself.
Kopiuj bajty
```

```
        <source>You can increase the fee later (signals Replace-By-Fee, BIP-125).</source>
        <translation>Możesz później zwiększyć opłatę (sygnalizuje podmień-przez-opłatę (RBF), BIP-125).</translation>
    
YES, the translation incorrectly renders the hyphen within "Replace-By-Fee" as a Polish word. The correct translation should use an English phrase or a more natural Polish equivalent if one exists and is commonly understood in the Bitcoin context.

NO
```

```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Duplikat adres-u znaleziony: adresy powinny zostać użyte tylko raz.</translation>
    
YES, The Polish translation incorrectly uses "adres-u" instead of "adresu". The correct translation is "Duplikat adresu znaleziony: adresy powinny zostać użyte tylko raz."
```

```
        <source>0/unconfirmed, not in memory pool</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that is not in the memory pool.</extracomment>
        <translation>0/niepotwierdzone, nie wysłane do kolejki w pamięci</translation>
    
YES: The translation contains a factual error. "nie wysłane do kolejki w pamięci" translates to "not sent to the memory pool queue", while the original English "not in memory pool" means that the transaction is not present in the memory pool. The correct translation should reflect that the transaction is not in the memory pool itself.

0/niepotwierdzone, nie w puli pamięci
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/niepotwierdzone</translation>
    
YES: The Polish translation for "unconfirmed" is incorrect. The correct translation is "niepotwierdzone".
%1/niepotwierdzone
```

```
        <source>No wallet has been loaded.
Go to File &gt; Open Wallet to load a wallet.
- OR -</source>
        <translation>Portfel nie został wybrany.
Przejdź do Plik &gt; Otwórz Portfel aby wgrać portfel.</translation>
    
YES - The translation is missing the " - OR -" part of the source text.
Correct translation: Portfel nie został wybrany. Przejdź do Plik &gt; Otwórz Portfel aby wgrać portfel. - LUB -
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>PSBT musi być mniejsze niż 100MiB</translation>
    
YES: The Polish translation uses the masculine gender for "PSBT" ("musi być mniejsze"), implying it's a masculine noun. However, "PSBT" is an acronym, and acronyms often default to neuter gender in Polish, or the gender of the underlying noun if it's known. Without specific context on how "PSBT" is treated in Polish Bitcoin communities, it's safer to use a gender-neutral or neuter form if possible, or a more standard masculine form if that's the established convention. However, the provided translation's grammar isn't strictly incorrect if "PSBT" is considered masculine. A more natural phrasing might be desired.

Corrected translation based on common Polish grammar for acronyms (often treated as neuter or masculine based on the implied noun, but "mniejsze" is often acceptable for acronyms):

PSBT musi być mniejsze niż 100 MiB
```

```
        <source>Warning: This may pay the additional fee by reducing change outputs or adding inputs, when necessary. It may add a new change output if one does not already exist. These changes may potentially leak privacy.</source>
        <translation>Ostrzeżenie: Może to spowodować uiszczenie dodatkowej opłaty poprzez zmniejszenie zmian wyjść lub dodanie danych wejściowych, jeśli jest to konieczne. Może dodać nowe wyjście zmiany, jeśli jeszcze nie istnieje. Te zmiany mogą potencjalnie spowodować utratę prywatności.</translation>
    
YES: The phrase "reducing change outputs or adding inputs" was translated as "zmniejszenie zmian wyjść lub dodanie danych wejściowych". While "danych wejściowych" is a correct translation for "inputs", in the context of Bitcoin transactions, the more appropriate term is "przesunięć" or "dodanie przesunięć". The original English text implies adding inputs to cover the fee by using unspent transaction outputs (UTXOs) from the wallet, which are referred to as "przesunięcia" in Polish Bitcoin jargon.

Corrected translation: Ostrzeżenie: Może to spowodować uiszczenie dodatkowej opłaty poprzez zmniejszenie ilości zwracanej reszty lub dodanie przesunięć, jeśli jest to konieczne. Może dodać nowe wyjście reszty, jeśli jeszcze nie istnieje. Te zmiany mogą potencjalnie spowodować utratę prywatności.
```

```
        <source>Cannot downgrade wallet from version %i to version %i. Wallet version unchanged.</source>
        <translation>Nie można zmienić wersji portfela z wersji %ina wersje %i. Wersja portfela pozostaje niezmieniona.</translation>
    
YES, The format specifier '%i' in the source text is incorrectly translated as '%ina' in the target text. The correct translation should be "Nie można zmienić wersji portfela z wersji %i na wersję %i. Wersja portfela pozostaje niezmieniona.".
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>Nie można zaktualizować portfela dzielonego innego niż HD z wersji 1%i do wersji 1%i bez aktualizacji w celu obsługi wstępnie podzielonej puli kluczy. Użyj wersji 1%i lub nie określono wersji.</translation>
    
YES: The translation erroneously adds "1" before the format specifiers (%i). This is incorrect and likely due to a misunderstanding of the format specifiers or a copy-paste error.

Correct translation: Nie można zaktualizować portfela dzielonego innego niż HD z wersji %i do wersji %i bez aktualizacji w celu obsługi wstępnie podzielonej puli kluczy. Użyj wersji %i lub nie określono wersji.
```

```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Błąd: wersja pliku zrzutu nie jest obsługiwana. Ta wersja bitcoin-wallet obsługuje tylko pliki zrzutów w wersji 1. Mam plik zrzutu w wersji 1%s</translation>
    
YES - The translation incorrectly places the format specifier '%s' at the end of the sentence. It should be placed where the version number is mentioned in the original English text.
Błąd: wersja pliku zrzutu nie jest obsługiwana. Ta wersja bitcoin-wallet obsługuje tylko pliki zrzutów w wersji 1. Mam plik zrzutu w wersji %s
```

```
        <source>Error: Unable to produce descriptors for this legacy wallet. Make sure to provide the wallet's passphrase if it is encrypted.</source>
        <translation>Błąd: Nie można wygenerować deskryptorów dla tego starego portfela. Upewnij się najpierw, że portfel jest odblokowany.</translation>
    
YES - The Polish translation is incorrect and does not accurately convey the original English meaning. The original English mentions providing a passphrase if the wallet is encrypted, while the Polish translation states to ensure the wallet is unlocked.

Correct translation: Błąd: Nie można wygenerować deskryptorów dla tego starego portfela. Upewnij się najpierw, że podajesz hasło do portfela, jeśli jest zaszyfrowany.
```

```
        <source>Prune mode is incompatible with -reindex-chainstate. Use full -reindex instead.</source>
        <translation>Tryb przycięty jest niekompatybilny z -reindex-chainstate. Użyj pełnego  -reindex.</translation>
    
YES, The translation is problematic because of an extra space between "pełnego" and "-reindex".
Tryb przycięty jest niekompatybilny z -reindex-chainstate. Użyj pełnego -reindex.
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Nieobsługiwany poziom logowania specyficzny dla kategorii %1$s=%2$s. Oczekiwano %1$s=&lt;category&gt;:&lt;loglevel&gt;. Poprawne kategorie %3$s. Poprawne poziomy logowania: %4 $s.</translation>
    
YES - There is a space before the format specifier %4$s, which should not be there.
The correct translation is: Nieobsługiwany poziom logowania specyficzny dla kategorii %1$s=%2$s. Oczekiwano %1$s=&lt;category&gt;:&lt;loglevel&gt;. Poprawne kategorie %3$s. Poprawne poziomy logowania: %4$s.
```

```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on enormous cluster of unconfirmed transactions.</source>
        <translation>Nie udało się obliczyć opłat za uderzenia, ponieważ niepotwierdzone UTXO zależą od ogromnego skupiska niepotwierdzonych transakcji.</translation>
    
YES - The word "uderzenia" translates to "strikes" or "hits", which is not the correct term for "bump fees" in the context of Bitcoin. The correct term would be "opłat za zwiększenie" or "opłat za podniesienie".

Correct translation: Nie udało się obliczyć opłat za zwiększenie, ponieważ niepotwierdzone UTXO zależą od ogromnego skupiska niepotwierdzonych transakcji.
```

```
        <source>Specified -blockmaxweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Podany -blockmaxweight (%d) przekracza przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)</translation>
    
YES: The translation contains a repeated word "przekracza".
Podany -blockmaxweight (%d) przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)
```

```
        <source>Specified -blockreservedweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Podany -blockreservedweight (%d) przekracza przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)</translation>
    
YES - The Polish translation contains a double word "przekracza przekracza".
The correct translation is: Podany -blockreservedweight (%d) przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)
```

```
        <source>Error: Got key that was not hex: %s</source>
        <translation>Błąd: Otrzymana wartość nie jest szestnastkowa%s</translation>
    
YES: The translation is missing a space before the format specifier %s.
Błąd: Otrzymana wartość nie jest szesnastkowa %s
```

```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Błąd: Otrzymana wartość nie jest szestnastkowa%s</translation>
    
YES, The translation is missing a space before the format specifier %s.
Błąd: Otrzymana wartość nie jest szesnastkowa %s
```

```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>Błąd: Pula kluczy jest pusta, odwołaj się do puli kluczy.</translation>
    
YES, The translation is inaccurate and does not convey the meaning of the source text. The phrase "odwołaj się do puli kluczy" is a literal and incorrect translation of "call keypoolrefill". It should mean "call keypoolrefill function first" or "call keypoolrefill before doing anything else".

Here's a more accurate translation:
Błąd: Pula kluczy jest pusta, najpierw wywołaj funkcję keypoolrefill.
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>Portfel będzie unikał płacenia mniejszej niż przekazana opłaty.</translation>
    
YES: The translation is inaccurate and does not convey the intended meaning of the original English text. It incorrectly translates "minimum relay fee" as "przekazana opłaty" which is nonsensical in this context.

Correct translation: Portfel będzie unikał płacenia niższej niż minimalna opłata za przekazanie.
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>Kwota transakcji musi być dodatnia</translation>
    
YES - The translation is inaccurate. The original English text states that transaction amounts "must not be negative," meaning they can be zero or positive. The Polish translation states that the transaction amount "must be positive," excluding zero.

Correct translation: Kwota transakcji nie może być ujemna
```

```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Zbyt mało dostępnych deskryptorów plików. %d dostępnych, %d wymaganych. </translation>
    
YES - There is an extra space at the end of the translation.
Zbyt mało dostępnych deskryptorów plików. %d dostępnych, %d wymaganych.
```
