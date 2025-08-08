# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sk</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsk%5D%20low%20quality)


<!-- cache_translation_check_sk_cb41c8aa9a33587fc1af83cdd888b8a780b9bfa3f9eb758c2b0474e587fedf63 -->
```
        <source>Receiving addresses - %1</source>
        <translation>Prijímajúce adresy -%1</translation>
    
ERR
There is a formatting issue: there should be a space before the dash, as in the source (" - %1"), but the translation has " -%1" without the space after the dash.

Correct translation:
Prijímajúce adresy - %1
```

<!-- cache_translation_check_sk_ed5bbafc44849440135b6f1c47910ad6f3cdb53b5e386b8ede5bda70a3a2155a -->
```
        <source>IP/Netmask</source>
        <translation>IP/Maska stiete</translation>
    
ERR
There is a typo in the translation: "Maska stiete" should be "Maska siete" (the word "siete" means "network" in Slovak, and "stiete" is incorrect).

Correct translation:
IP/Maska siete
```

<!-- cache_translation_check_sk_acaa03f5f5954d6e59a2a65291be2e5f3703f538d9e1a87b8c8c57ab89ff9184 -->
```
        <source>%1 and %2</source>
        <translation>%1 a  %2</translation>
    
ERR
There is an extra space between 'a' and '%2' in the Slovak translation. There should be only one space. 

Correct translation:
%1 a %2
```

<!-- cache_translation_check_sk_6f9d3c27f5ab647addf2fb3a0d2223bb7f69a248cecf5b7cc6f69131f8623358 -->
```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Proxy sú &lt;b&gt;zapnuté&lt;/b&gt;: %1</translation>
    
ERR
The word "Proxy" should be treated as singular ("Proxy je"), not plural ("Proxy sú"), in Slovak when referring to the status of a proxy as a service or feature, not multiple proxies.

Correct translation:
Proxy je &lt;b&gt;zapnutý&lt;/b&gt;: %1
```

<!-- cache_translation_check_sk_41c55d9b09bcde99fa65ff24da52b1cf92481986b1411b04704928e836f95052 -->
```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Ukáž %1 zoznam možných nastavení Bitcoinu pomocou príkazového riadku</translation>
    
ERR
The translation changes the structure and omits "help message" ("pomocnú správu" or "správu s pomocou"). Also, "get a list" is not literal—"zoznam" is moved and doesn't refer to the help message. "pomocou príkazového riadku" means "using the command line," which is not quite correct contextually; it should express that the options are command-line options, not that you use a command-line.

Correct translation:
Zobraz správu s pomocou %1 pre zoznam možných príkazov pre Bitcoin z príkazového riadku
```

<!-- cache_translation_check_sk_51c10042ce29149c0150a8f896ede09f5d3c3e87ac9f9a760d4485ce319d1e5e -->
```
        <source>Sent transaction</source>
        <translation>Odoslané transakcie</translation>
    
ERR
The translation is plural ("Odoslané transakcie" = "Sent transactions"), but the source is singular ("Sent transaction"). It should match in number.

Correct translation:
Odoslaná transakcia
```

<!-- cache_translation_check_sk_a66adf836ad94d9e754ef32c5b2f5970e0237fd749b6c14afd31006a2c40612b -->
```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Vložená adresa "%1" nieje platnou adresou Bitcoin.</translation>
    
ERR
There is an orthographic error in the word "nieje", which should be "nie je" (spelled as two words in correct Slovak). Also, the phrase "adresou Bitcoin" is unnatural; it is better to say "platná Bitcoin adresa" or "platná adresa Bitcoin". For naturalness and correctness, it's better to translate as:

Správna preklad:
Zadaná adresa „%1“ nie je platná Bitcoin adresa.

Alternatively, to be even more natural:
Zadaná adresa „%1“ nie je platná Bitcoinová adresa.
```

<!-- cache_translation_check_sk_653205f179cb7480ecedbadc1d5d0416a99525eb5f8eaa994a9663b4c1cd9697 -->
```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Adresa "%1" už existuje ako prijímacia adresa s označením "%2" .Nemôže tak byť pridaná ako odosielacia adresa.</translation>
    
ERR
There is a minor issue with whitespace; there should be a space after '%2"' and before the period. Also, the conjunction "a preto" or "takže" is more natural than "Nemôže tak byť". Here is a smoother, corrected version:

Correct translation:
Adresa "%1" už existuje ako prijímacia adresa s označením "%2", a preto nemôže byť pridaná ako odosielacia adresa.
```

<!-- cache_translation_check_sk_4017ae783435cf710ff709b5c7b65b1e3e4fe8f96f7ea9bb77064bcbb36dd089 -->
```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Zvoľte ako deliť bitcoin pri zobrazovaní pri platbách a užívateľskom rozhraní.</translation>
    
ERR  
The translation is understandable but not adequately accurate, and it omits several concepts from the source, notably "default", "unit", and "when sending coins". A more precise translation would be:

Zvoľte predvolenú jednotku delenia, ktorá sa bude zobrazovať v rozhraní a pri odosielaní mincí.
```

<!-- cache_translation_check_sk_e96aa53823f82f3d296105114ce46b0ab49bf049ada82cbed7490eaee4a631d3 -->
```
        <source>In:</source>
        <translation>Dnu:</translation>
    
ERR
The translation "Dnu:" is incorrect and not idiomatic in Slovak. The correct translation for "In:" (as in incoming transaction) is "Prichádzajúce:" or simply "Vstup:" depending on the UI context. "Dnu" is not used in this context.

Correct translation:
Prichádzajúce:
or
Vstup:
```

<!-- cache_translation_check_sk_b9932ef85389f5463efdb8c8b32a4fbde776c296e46cb44ff27c9e8e0e643d81 -->
```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Použitie núdzového poplatku („fallbackfee“) môže vyústiť v transakciu, ktoré bude trvat hodiny nebo dny (prípadne večnosť), kým bude potvrdená. Zvážte preto ručné nastaveníe poplatku, prípadne počkajte, až sa Vám kompletne zvaliduje reťazec blokov.</translation>
    
ERR
There are several issues:
- Grammar mix: The translation uses Czech words ("nebo", "nastaveníe", "až se Vám", "zvaliduje") instead of Slovak ("alebo", "nastavenie", "kým sa vám", "overí").
- Diacritics: "trvat" should be "trvať".
- In Slovak, the polite form "Vám" is capitalized only in formal letters, less common in technical UI.
- The source specifies "the complete chain", better as "celý reťazec" or "celý blokový reťazec".

Correct translation:
Použitie núdzového poplatku („fallbackfee“) môže viesť k tomu, že transakcia bude potvrdená až o niekoľko hodín alebo dní (prípadne nikdy). Zvážte preto ručné nastavenie poplatku alebo počkajte, kým bude celý reťazec blokov overený.
```

<!-- cache_translation_check_sk_dc3d14865b0ffa75d94a15f64469f8e07521f2b7717a4c610947e37aeab26acb -->
```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Zvoľte adresu kam poslať platbu</translation>
    
ERR
The translation does not accurately convey the original meaning. The source specifies "The Bitcoin address to send the payment to," which indicates a specific Bitcoin address. The translation says "Choose the address where to send the payment," which introduces an action ("choose") not found in the source.

Correct translation:
Bitcoin adresa, na ktorú chcete poslať platbu
```

<!-- cache_translation_check_sk_192300479c20659ce07ab5736e0e99b63678603eb5fc19c8e018bdd3b9799a68 -->
```
        <source>The Bitcoin address to sign the message with</source>
        <translation>Bitcoin adresa pre podpísanie správy s</translation>
    
ERR
The Slovak translation is not fully natural and contains a word order issue. The phrase "pre podpísanie správy s" is awkward; it should mirror the English structure that implies "to use in signing the message".

Correct translation:
Bitcoin adresa na podpísanie správy

Alternatively (more literal, but natural):
Bitcoin adresa, ktorou sa má správa podpísať
```

<!-- cache_translation_check_sk_df094f8116b45c70c54ff78bf2c0d70d4dfb8e0f9d55de462ba94d4c01ee2d50 -->
```
        <source>Verify the message to ensure it was signed with the specified Bitcoin address</source>
        <translation>Overím správy sa uistiť že bola podpísaná označenou Bitcoin adresou</translation>
    
ERR
The translation is not entirely accurate and has issues with grammar and style. The verb "Overím" is first person singular ("I will verify") instead of an imperative form or descriptive form, and "správy" is plural ("messages") while the original is singular ("message"). The structure "sa uistiť že bola" is not stylistically correct in Slovak.

Correct translation:
Overte správu, aby ste sa uistili, že bola podpísaná zadanou Bitcoin adresou
```

<!-- cache_translation_check_sk_fa37861e60584781ecfaf9973eae2bb0cb6bc0dc5b0f7fe91919b7796d9718e5 -->
```
        <source>Private key for the entered address is not available.</source>
        <translation>Súkromný kľúč pre zadanú adresu nieje k dispozícii.</translation>
    
ERR
There is a spelling issue: "nieje" should be written as two words, "nie je" in Slovak.

Correct translation:
Súkromný kľúč pre zadanú adresu nie je k dispozícii.
```

<!-- cache_translation_check_sk_d35302f2de11e9b92c2ff564f74ffb3c621812c02720b3b8a6ab23384c095a35 -->
```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Či je v tejto transakcii adresy iba na sledovanie.</translation>
    
ERR
The translation is grammatically incorrect and somewhat unclear. "Adresy iba na sledovanie" is plural ("addresses"), and it omits the verb that would clarify the meaning. The proper translation should retain the singular "address" and the conditional form.

Correct translation:
Či sa tejto transakcie zúčastňuje adresa iba na sledovanie.
```

<!-- cache_translation_check_sk_4103e3ad4990342d7b82ae33b763194ea27ec0d3e5a963993fd6ca2ac8b55937 -->
```
        <source>Edit address label</source>
        <translation>Upraviť popis transakcie</translation>
    
ERR  
The translation is inaccurate. "Edit address label" should be referring to editing the label (name or description) of an address, not a transaction description.  

Correct translation:  
Upraviť popis adresy
```

<!-- cache_translation_check_sk_68ac3aa1c3ac91072142d38d20bd4e7b96b4c139f81553e8b7a6563df71dd756 -->
```
        <source>Could not commit transaction</source>
        <translation>Nemôzeme uložiť transakciu do peňaženky</translation>
    
ERR
The translation inaccurately adds "do peňaženky" (to the wallet), which is not present in the source. Also, "Nemôzeme" should correctly be "Nemôžeme".

Correct translation:
Nemôžeme potvrdiť transakciu
```

<!-- cache_translation_check_sk_c4b9c36970043cc94a3b5e575dad8002394d1bb8fe6c4e5f22f8f2395acd08d0 -->
```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>Neplatné množstvo pre %s=&lt;amount&gt;: '%s' (musí byť aspoň  vo výške poplatku "minrelay" pre %s, aby sa zabránilo zaseknutým transakciám)</translation>
    
ERR
There is an unnecessary space before "vo výške", and "poplatku 'minrelay' pre %s" changes the meaning—it's more accurate to keep "%s" as the minrelay fee value, not describe it as "pre %s." The position of the parameter is also different from the original. 

Correct translation:
Neplatná suma pre %s=&lt;amount&gt;: '%s' (musí byť aspoň minimálnym poplatkom minrelay vo výške %s, aby sa zabránilo zaseknutým transakciám)
```

<!-- cache_translation_check_sk_82744644ddb005793fc9efba2716e70a87352da943a6b07da1a6ed68094658ec -->
```
        <source>Maximum transaction weight is too low, can not accommodate change output</source>
        <translation>Maximálna veľkosť transakcie je príliš nízka, nebudú sa do nej zmestiť výstupy </translation>
    
ERR
The translation is inaccurate. The original mentions "maximum transaction weight" and inability to accommodate the "change output" specifically. The translation changes "weight" to "size", refers non-specifically to "outputs", and omits "change" entirely. There is also an extra space at the end.

Correct translation:
Maximálna hmotnosť transakcie je príliš nízka, nie je možné zahrnúť výstup na vydanie
```

<!-- cache_translation_check_sk_ff3b95484f636b80b3d326c8f5c911c4fde1c9c6718a4d21b8e7970b12b7d3bd -->
```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Chyba: Obdržaná hodnota nebola v hex tvare: : %s</translation>
    
ERR
There is an extra colon before the format specifier "%s". Also, the phrase "v hex tvare" could be improved for clarity and standard usage. 

Correct translation:
Chyba: Obdržaná hodnota nebola v hexadecimálnom formáte: %s
```

<!-- cache_translation_check_sk_ba0cf980c0f33528b21d5363d673b88df43dbb2e45a01d8ccdd317a3eb32dacf -->
```
        <source>Error: Unable to write solvable wallet best block locator record</source>
        <translation>Chyba: Nepodarilo sa zapísať záznam o umiestnení najlepšieho bloku do peňaženky "solvable"</translation>
    
ERR
The translation introduces a quotation mark around "solvable" and modifies the structure in a way that could lead to confusion. The source refers to a specific type of wallet—likely "solvable wallet"—not a wallet named "solvable". The term "solvable" should be treated as an adjective, not as a name.

Correct translation:
Chyba: Nepodarilo sa zapísať záznam o ukazovateli najlepšieho bloku pre riešiteľnú peňaženku
```

<!-- cache_translation_check_sk_34a9c7593596c254fc6a4ac418f5b8a1f9e5fb33a0ba9aeb27329d6af3f79577 -->
```
        <source>SQLiteDatabase: Unexpected application id. Expected %u, got %u</source>
        <translation>SQLiteDatabase: Neočakávané ID aplikácie: %u. Očakávané:  %u</translation>
    
ERR
The translation reverses the order of the expected and actual values compared to the English source. Additionally, there is an unnecessary extra space before the second %u.

Correct translation:
SQLiteDatabase: Neočakávané ID aplikácie. Očakávané %u, získané %u
```

<!-- cache_translation_check_sk_2b40e164e1e09c522906159519e9b5f7de6f472f51fc8a010c95b399bbfc644f -->
```
        <source>Signing transaction failed</source>
        <translation>Podpísanie správy zlyhalo</translation>
    
ERR
The translation incorrectly translates "transaction" as "správy" (which means "message" in Slovak). The correct word for "transaction" in this Bitcoin context is "transakcie".

Correct translation:
Podpísanie transakcie zlyhalo
```

<!-- cache_translation_check_sk_b7e564017d2ae20ce27e86dd7727f4cb575add440ccb17dda0e90f41222e6ba0 -->
```
        <source>System error while loading external block file: %s</source>
        <translation>Systémov chyba pri čítaní externého súboru blokov: %s</translation>
    
ERR
There is a typo/mistake in the translation: "Systémov chyba" should be "Systémová chyba" (correct adjective agreement). Also, "súboru blokov" is acceptable, but "blokového súboru" (block file) would be a more common phrasing.

Correct translation:
Systémová chyba pri čítaní externého blokového súboru: %s
```
</details>

Number of issues: 25.
