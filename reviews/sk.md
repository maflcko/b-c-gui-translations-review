# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sk</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsk%5D%20low%20quality)


```
        <source>Receiving addresses - %1</source>
        <translation>Prijímajúce adresy -%1</translation>
    
YES
There is a formatting issue: there should be a space before the dash, as in the source (" - %1"), but the translation has " -%1" without the space after the dash.

Correct translation:
Prijímajúce adresy - %1
```

```
        <source>IP/Netmask</source>
        <translation>IP/Maska stiete</translation>
    
YES
There is a typo in the translation: "Maska stiete" should be "Maska siete" (the word "siete" means "network" in Slovak, and "stiete" is incorrect).

Correct translation:
IP/Maska siete
```

```
        <source>%1 and %2</source>
        <translation>%1 a  %2</translation>
    
YES
There is an extra space between 'a' and '%2' in the Slovak translation. There should be only one space. 

Correct translation:
%1 a %2
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Proxy sú &lt;b&gt;zapnuté&lt;/b&gt;: %1</translation>
    
YES
The word "Proxy" should be treated as singular ("Proxy je"), not plural ("Proxy sú"), in Slovak when referring to the status of a proxy as a service or feature, not multiple proxies.

Correct translation:
Proxy je &lt;b&gt;zapnutý&lt;/b&gt;: %1
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Ukáž %1 zoznam možných nastavení Bitcoinu pomocou príkazového riadku</translation>
    
YES
The translation changes the structure and omits "help message" ("pomocnú správu" or "správu s pomocou"). Also, "get a list" is not literal—"zoznam" is moved and doesn't refer to the help message. "pomocou príkazového riadku" means "using the command line," which is not quite correct contextually; it should express that the options are command-line options, not that you use a command-line.

Correct translation:
Zobraz správu s pomocou %1 pre zoznam možných príkazov pre Bitcoin z príkazového riadku
```

```
        <source>Sent transaction</source>
        <translation>Odoslané transakcie</translation>
    
YES
The translation is plural ("Odoslané transakcie" = "Sent transactions"), but the source is singular ("Sent transaction"). It should match in number.

Correct translation:
Odoslaná transakcia
```

```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Vložená adresa "%1" nieje platnou adresou Bitcoin.</translation>
    
YES
There is an orthographic error in the word "nieje", which should be "nie je" (spelled as two words in correct Slovak). Also, the phrase "adresou Bitcoin" is unnatural; it is better to say "platná Bitcoin adresa" or "platná adresa Bitcoin". For naturalness and correctness, it's better to translate as:

Správna preklad:
Zadaná adresa „%1“ nie je platná Bitcoin adresa.

Alternatively, to be even more natural:
Zadaná adresa „%1“ nie je platná Bitcoinová adresa.
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Adresa "%1" už existuje ako prijímacia adresa s označením "%2" .Nemôže tak byť pridaná ako odosielacia adresa.</translation>
    
YES
There is a minor issue with whitespace; there should be a space after '%2"' and before the period. Also, the conjunction "a preto" or "takže" is more natural than "Nemôže tak byť". Here is a smoother, corrected version:

Correct translation:
Adresa "%1" už existuje ako prijímacia adresa s označením "%2", a preto nemôže byť pridaná ako odosielacia adresa.
```

```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Zvoľte ako deliť bitcoin pri zobrazovaní pri platbách a užívateľskom rozhraní.</translation>
    
YES  
The translation is understandable but not adequately accurate, and it omits several concepts from the source, notably "default", "unit", and "when sending coins". A more precise translation would be:

Zvoľte predvolenú jednotku delenia, ktorá sa bude zobrazovať v rozhraní a pri odosielaní mincí.
```

```
        <source>In:</source>
        <translation>Dnu:</translation>
    
YES
The translation "Dnu:" is incorrect and not idiomatic in Slovak. The correct translation for "In:" (as in incoming transaction) is "Prichádzajúce:" or simply "Vstup:" depending on the UI context. "Dnu" is not used in this context.

Correct translation:
Prichádzajúce:
or
Vstup:
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Použitie núdzového poplatku („fallbackfee“) môže vyústiť v transakciu, ktoré bude trvat hodiny nebo dny (prípadne večnosť), kým bude potvrdená. Zvážte preto ručné nastaveníe poplatku, prípadne počkajte, až sa Vám kompletne zvaliduje reťazec blokov.</translation>
    
YES
There are several issues:
- Grammar mix: The translation uses Czech words ("nebo", "nastaveníe", "až se Vám", "zvaliduje") instead of Slovak ("alebo", "nastavenie", "kým sa vám", "overí").
- Diacritics: "trvat" should be "trvať".
- In Slovak, the polite form "Vám" is capitalized only in formal letters, less common in technical UI.
- The source specifies "the complete chain", better as "celý reťazec" or "celý blokový reťazec".

Correct translation:
Použitie núdzového poplatku („fallbackfee“) môže viesť k tomu, že transakcia bude potvrdená až o niekoľko hodín alebo dní (prípadne nikdy). Zvážte preto ručné nastavenie poplatku alebo počkajte, kým bude celý reťazec blokov overený.
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Zvoľte adresu kam poslať platbu</translation>
    
YES
The translation does not accurately convey the original meaning. The source specifies "The Bitcoin address to send the payment to," which indicates a specific Bitcoin address. The translation says "Choose the address where to send the payment," which introduces an action ("choose") not found in the source.

Correct translation:
Bitcoin adresa, na ktorú chcete poslať platbu
```

```
        <source>The Bitcoin address to sign the message with</source>
        <translation>Bitcoin adresa pre podpísanie správy s</translation>
    
YES
The Slovak translation is not fully natural and contains a word order issue. The phrase "pre podpísanie správy s" is awkward; it should mirror the English structure that implies "to use in signing the message".

Correct translation:
Bitcoin adresa na podpísanie správy

Alternatively (more literal, but natural):
Bitcoin adresa, ktorou sa má správa podpísať
```

```
        <source>Verify the message to ensure it was signed with the specified Bitcoin address</source>
        <translation>Overím správy sa uistiť že bola podpísaná označenou Bitcoin adresou</translation>
    
YES
The translation is not entirely accurate and has issues with grammar and style. The verb "Overím" is first person singular ("I will verify") instead of an imperative form or descriptive form, and "správy" is plural ("messages") while the original is singular ("message"). The structure "sa uistiť že bola" is not stylistically correct in Slovak.

Correct translation:
Overte správu, aby ste sa uistili, že bola podpísaná zadanou Bitcoin adresou
```

```
        <source>Private key for the entered address is not available.</source>
        <translation>Súkromný kľúč pre zadanú adresu nieje k dispozícii.</translation>
    
YES
There is a spelling issue: "nieje" should be written as two words, "nie je" in Slovak.

Correct translation:
Súkromný kľúč pre zadanú adresu nie je k dispozícii.
```

```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Či je v tejto transakcii adresy iba na sledovanie.</translation>
    
YES
The translation is grammatically incorrect and somewhat unclear. "Adresy iba na sledovanie" is plural ("addresses"), and it omits the verb that would clarify the meaning. The proper translation should retain the singular "address" and the conditional form.

Correct translation:
Či sa tejto transakcie zúčastňuje adresa iba na sledovanie.
```

```
        <source>Edit address label</source>
        <translation>Upraviť popis transakcie</translation>
    
YES  
The translation is inaccurate. "Edit address label" should be referring to editing the label (name or description) of an address, not a transaction description.  

Correct translation:  
Upraviť popis adresy
```

```
        <source>Could not commit transaction</source>
        <translation>Nemôzeme uložiť transakciu do peňaženky</translation>
    
YES
The translation inaccurately adds "do peňaženky" (to the wallet), which is not present in the source. Also, "Nemôzeme" should correctly be "Nemôžeme".

Correct translation:
Nemôžeme potvrdiť transakciu
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>Neplatné množstvo pre %s=&lt;amount&gt;: '%s' (musí byť aspoň  vo výške poplatku "minrelay" pre %s, aby sa zabránilo zaseknutým transakciám)</translation>
    
YES
There is an unnecessary space before "vo výške", and "poplatku 'minrelay' pre %s" changes the meaning—it's more accurate to keep "%s" as the minrelay fee value, not describe it as "pre %s." The position of the parameter is also different from the original. 

Correct translation:
Neplatná suma pre %s=&lt;amount&gt;: '%s' (musí byť aspoň minimálnym poplatkom minrelay vo výške %s, aby sa zabránilo zaseknutým transakciám)
```

```
        <source>Maximum transaction weight is too low, can not accommodate change output</source>
        <translation>Maximálna veľkosť transakcie je príliš nízka, nebudú sa do nej zmestiť výstupy </translation>
    
YES
The translation is inaccurate. The original mentions "maximum transaction weight" and inability to accommodate the "change output" specifically. The translation changes "weight" to "size", refers non-specifically to "outputs", and omits "change" entirely. There is also an extra space at the end.

Correct translation:
Maximálna hmotnosť transakcie je príliš nízka, nie je možné zahrnúť výstup na vydanie
```

```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Chyba: Obdržaná hodnota nebola v hex tvare: : %s</translation>
    
YES
There is an extra colon before the format specifier "%s". Also, the phrase "v hex tvare" could be improved for clarity and standard usage. 

Correct translation:
Chyba: Obdržaná hodnota nebola v hexadecimálnom formáte: %s
```

```
        <source>Error: Unable to write solvable wallet best block locator record</source>
        <translation>Chyba: Nepodarilo sa zapísať záznam o umiestnení najlepšieho bloku do peňaženky "solvable"</translation>
    
YES
The translation introduces a quotation mark around "solvable" and modifies the structure in a way that could lead to confusion. The source refers to a specific type of wallet—likely "solvable wallet"—not a wallet named "solvable". The term "solvable" should be treated as an adjective, not as a name.

Correct translation:
Chyba: Nepodarilo sa zapísať záznam o ukazovateli najlepšieho bloku pre riešiteľnú peňaženku
```

```
        <source>SQLiteDatabase: Unexpected application id. Expected %u, got %u</source>
        <translation>SQLiteDatabase: Neočakávané ID aplikácie: %u. Očakávané:  %u</translation>
    
YES
The translation reverses the order of the expected and actual values compared to the English source. Additionally, there is an unnecessary extra space before the second %u.

Correct translation:
SQLiteDatabase: Neočakávané ID aplikácie. Očakávané %u, získané %u
```

```
        <source>Signing transaction failed</source>
        <translation>Podpísanie správy zlyhalo</translation>
    
YES
The translation incorrectly translates "transaction" as "správy" (which means "message" in Slovak). The correct word for "transaction" in this Bitcoin context is "transakcie".

Correct translation:
Podpísanie transakcie zlyhalo
```

```
        <source>System error while loading external block file: %s</source>
        <translation>Systémov chyba pri čítaní externého súboru blokov: %s</translation>
    
YES
There is a typo/mistake in the translation: "Systémov chyba" should be "Systémová chyba" (correct adjective agreement). Also, "súboru blokov" is acceptable, but "blokového súboru" (block file) would be a more common phrasing.

Correct translation:
Systémová chyba pri čítaní externého blokového súboru: %s
```
</details>

Number of issues: 25.
