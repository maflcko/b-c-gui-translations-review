# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>pl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bpl%5D%20low%20quality)


```
        <source>Are you sure you wish to close all wallets?</source>
        <translation>Na pewno zamknąć wszystkie portfele?</translation>
    
YES  
The translation is incomplete and grammatically incorrect. The English sentence is a question properly formed as "Are you sure you wish to close all wallets?" The Polish translation omits the equivalent of "Are you sure you wish to," and just says "Na pewno zamknąć wszystkie portfele?" which literally translates to "Sure to close all wallets?" This sounds unnatural and incomplete in Polish.  

A correct and natural Polish translation would be:  
"Czy na pewno chcesz zamknąć wszystkie portfele?"
```

```
        <source>Ban for</source>
        <translation>Ban na</translation>
    
YES  
The Polish translation "Ban na" is more appropriate than "Ban na". The provided translation "Ban na" is a mix of English and Polish, which is not correct. The correct Polish translation for "Ban for" in the Bitcoin context (e.g., "Ban for 24 hours") is "Zakaz na" or "Ban na". However, commonly "Ban na" is used in technical contexts.

Correct translation:  
Ban na
```

```
        <source>Custom change address</source>
        <translation>Niestandardowy adres reszty</translation>
    
YES  
The Polish word "Niestandardowy" is more commonly translated as "non-standard" rather than "custom." In Bitcoin context, "custom change address" means a user-specified address, so the better translation would use "niestandardowy" or "własny," but "własny" ("own") captures the idea of custom better here. Also, "reszta" is a better translation for "change" in Bitcoin transactions than "reszta," which is fine, but "adres reszty" is uncommon phraseology in Polish Bitcoin terminology. The more natural term is "adres na resztę" or just "adres reszty." However, "adres reszty" is acceptable.

A better translation would be:  
"Własny adres na resztę"  
or  
"Niestandardowy adres na resztę"

Given the source phrase, the most standard and idiomatic would be:  
"Niestandardowy adres na resztę"

Correct translation:  
<Niestandardowy adres na resztę>
```

```
        <source>0/unconfirmed, in memory pool</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that is in the memory pool.</extracomment>
        <translation>0/niepotwierdzone, jest w puli pamięci</translation>
    
YES
The translation is understandable but can be improved for naturalness and clarity. The phrase "jest w puli pamięci" is somewhat awkward in Polish technical context. A more common and clearer translation of "in memory pool" related to Bitcoin transactions is "w puli pamięci" without the extra "jest" or reformulated slightly for better flow.

Correct translation:
0/niepotwierdzone, w puli pamięci
```

```
        <source>Error: Unable to produce descriptors for this legacy wallet. Make sure to provide the wallet's passphrase if it is encrypted.</source>
        <translation>Błąd: Nie można wygenerować deskryptorów dla tego starego portfela. Upewnij się najpierw, że portfel jest zaszyfrowany.</translation>
    
YES
The original English text says: "Make sure to provide the wallet's passphrase if it is encrypted." The Polish translation changes the meaning to "Make sure first that the wallet is encrypted," which is not the same and loses the instruction to provide the passphrase.

Correct translation:
Błąd: Nie można wygenerować deskryptorów dla tego starego portfela. Upewnij się, że podałeś hasło do portfela, jeśli jest zaszyfrowany.
```

```
        <source>Error: Got key that was not hex: %s</source>
        <translation>Błąd: Otrzymano klucz, który nie jest szestnastkowy %s</translation>
    
YES  
The translation misses a comma before the format specifier %s, which is present in the source after the colon. Also, the phrase "nie jest szestnastkowy" is unusual; the correct Polish adjective for "hexadecimal" is "szesnastkowy" (note the spelling).  

Correct translation:  
Błąd: Otrzymano klucz, który nie jest szesnastkowy: %s
```

```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Błąd: Otrzymano wartość, która nie jest szestnastkowa %s</translation>
    
YES  
The translation contains a minor error: the term "hex" should be translated as "szesnastkowa" instead of "szestnastkowa" (missing the "e" after "sz"). Also, there should be a colon or comma before the format specifier %s, matching the source which includes a colon after "Error". Additionally, there is a missing comma after "szesnastkowa" before "%s".  

Correct translation:  
Błąd: Otrzymano wartość, która nie jest szesnastkowa: %s
```
</details>
