# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bsk%5D%20request)



<details><summary>sk</summary>


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

<!-- cache_translation_check_sk_b17f1636a4741f9a8a39f3f9b8aabdc9347d79703cdce3008f9adc10759e5589 -->
```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Obnovovanie peňaženky</translation>
    
ERR
The translation is incomplete. It misses the format specifier %1 (which represents the name of the wallet) and the bold HTML tags <b></b>, as well as the ellipsis.

Correct translation:
Obnovovanie peňaženky <b>%1</b>…
```

<!-- cache_translation_check_sk_b17f1636a4741f9a8a39f3f9b8aabdc9347d79703cdce3008f9adc10759e5589 -->
```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Obnovovanie peňaženky</translation>
    
ERR
The translation is incomplete. It misses the format specifier %1 (which represents the name of the wallet) and the bold HTML tags <b></b>, as well as the ellipsis.

Correct translation:
Obnovovanie peňaženky <b>%1</b>…
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

<!-- cache_translation_check_sk_ab7c46e25d383166fb044076206a302ac1602a40a4c882c270cddd298a7c6961 -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>&amp;Zobraziť len ikonu na lište po minimalizovaní okna.</translation>
    
ERR
The translation meaning diverges from the English original. The English text states "Minimize to the tray instead of the taskbar," while the Slovak translation suggests "Show only the icon on the bar after minimizing the window," which does not accurately reflect the original meaning about minimizing to the system tray rather than the taskbar.

Correct translation:
&Minimalizovať do systémovej lišty namiesto panela úloh
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

<!-- cache_translation_check_sk_510c1858e701eca6a301e1f7b9eaa19795b99d6e02383bc5978f84fb5cfce6df -->
```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Použitie núdzového poplatku („fallbackfee“) môže vyústiť v transakciu, ktoré bude trvať hodiny alebo dni (prípadne večnosť), kým bude potvrdená. Zvážte preto ručné nastavenie poplatku, prípadne počkajte, až sa Vám kompletne skontroluje reťazec blokov.</translation>
    
ERR
There is a grammatical error in the translation. The word "transakciu" (transaction) is feminine singular, but the following relative pronoun "ktoré" is neuter plural. It should be "ktorá".

Correct translation:
Použitie núdzového poplatku („fallbackfee“) môže vyústiť v transakciu, ktorá bude trvať hodiny alebo dni (prípadne večnosť), kým bude potvrdená. Zvážte preto ručné nastavenie poplatku, prípadne počkajte, kým sa vám kompletne overí reťazec blokov.
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

<!-- cache_translation_check_sk_4690bb78960bd4c90c1c00ffd3751027dd955b4a34eca1f58e23dd7b37b3135f -->
```
        <source>&amp;Edit address label</source>
        <translation>&amp;Upraviť popis transakcie</translation>
    
ERR
The translation is incorrect. "address label" should be translated as "označenie adresy" or "popis adresy", not "popis transakcie" ("transaction label/description").

Correct translation:
&Upraviť označenie adresy
```

<!-- cache_translation_check_sk_60c34e6a5b6e28ced3363ff2fa609cc405e60c69a4b5f713c651a90d86027b75 -->
```
        <source>Can't sign transaction.</source>
        <translation>Nemôzeme podpíaať transakciu.</translation>
    
ERR
The translation contains typos and grammatical errors. "Nemôzeme" is missing an accent on the 'z' (should be 'nemôžeme'), and "podpíaať" contains an extra 'a' and an incorrect accent (should be 'podpísať').

Correct translation:
Nemôžeme podpísať transakciu.
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

<!-- cache_translation_check_sk_d113eacef622799c6f25276d91f851a447196f908f4bd4118767af2ea2afc36a -->
```
        <source>Can't spend unconfirmed version %d pre-selected input with a version 3 tx</source>
        <translation>Nemožno minúť nepotvrdený vstup verzie %d vopred vybraný s verziou 3 tx</translation>
    
ERR
Slovak translation is grammatically awkward and word order is unclear; "tx" shouldn't be left as "tx" and the modifiers should be ordered/commas fixed. The %d specifier is preserved correctly.

Correct translation:
Nemožno minúť nepotvrdený, vopred vybraný vstup verzie %d v transakcii verzie 3.
```

<!-- cache_translation_check_sk_4149497949ffd4c8b484441576e3a89c5e38adea199cb1339a6d75251786263a -->
```
        <source>Can't spend unconfirmed version 3 pre-selected input with a version %d tx</source>
        <translation>Nemožno minúť nepotvrdený predvolený vstup verzie 3 s verziou %d tx</translation>
    
ERR
The Slovak translation is understandable but slightly off: "predvolený" suggests "default" rather than "pre-selected", and "tx" should be localized to "transakcii" (or "transakcia") for clarity. Grammar/word order can be improved.

Correct translation:
Nemožno minúť nepotvrdený predvybraný vstup verzie 3 v transakcii s verziou %d
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

<!-- cache_translation_check_sk_859ffaf7e7054dd4db70b67ed70b1b7b0c4c7bf4a9343576245a08de74129365 -->
```
        <source>Failed to acquire rescan reserver during wallet initialization</source>
        <translation>Počas inicializácie peňaženky sa nepodarilo získať rezervátor pre opätovné skenovanie.</translation>
    
ERR
The Slovak phrasing is understandable but uses an unnatural/incorrect term "rezervátor" and slightly awkward word order. Better to use "rezerva" or "zámok" depending on intended meaning.

Suggested correction:
Počas inicializácie peňaženky sa nepodarilo získať rezervu pre opätovné skenovanie.

Or, if the meaning is a lock/reservation object:
Počas inicializácie peňaženky sa nepodarilo získať zámok pre opätovné skenovanie.
```

<!-- cache_translation_check_sk_9658d7ad8aebbab64afdc55e7c092d560fbe5a845b8104a9ff3d7b0cb2e204a7 -->
```
        <source>Failed to close block undo file.</source>
        <translation>Nepodarilo sa zatvoriť súbor s vrátením bloku späť.</translation>
    
ERR
The Slovak translation is awkward/redundant and not idiomatic. "súbor s vrátením bloku späť" literally says "file with returning the block back" (double "back") and is unclear.

Correct translation (idiomatic, concise):
Nepodarilo sa zatvoriť undo súbor bloku.
Alternate, more descriptive:
Nepodarilo sa zatvoriť súbor undo pre blok.
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

<!-- cache_translation_check_sk_74694da9120db92b63981d7918dd277bee61187a24a9cedbafec81c655b900b7 -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>Chyba pri načítavaní %s: Peňaženka je staršia peňaženka. Prejdite na deskriptorovú peňaženku pomocou migračného nástroja (migratewallet RPC).</translation>
    
ERR
The Slovak translation is understandable and preserves the format specifier, but it's slightly awkward/redundant: "Peňaženka je staršia peňaženka" repeats "peňaženka". 

Corrected translation:
Chyba pri načítavaní %s: Ide o starú peňaženku. Prejdite na deskriptorovú peňaženku pomocou migračného nástroja (migratewallet RPC).
```

<!-- cache_translation_check_sk_51a9e35006b171be35c5a54ff116eec854b07d8a7227ceebca2d5f829546b7c5 -->
```
        <source>Transaction requires one destination of non-zero value, a non-zero feerate, or a pre-selected input</source>
        <translation>Transakcia vyžaduje jeden cieľ s nenulovou hodnotou, nenulový poplatok alebo vopred vybraný vstup.</translation>
    
ERR
The Slovak is mostly understandable, but "feerate" was translated as "poplatok" (fee), which is different from "fee rate". Also a more natural phrasing is to use the feminine form for "sadzba" to match "feerate".

Correct translation:
Transakcia vyžaduje jeden cieľ s nenulovou hodnotou, nenulovú sadzbu poplatku alebo vopred vybraný vstup.
```

<!-- cache_translation_check_sk_e94f60c68c097fd2d6612911f0cd6ddf0fd42c570c25e44b839337aa7b93fb90 -->
```
        <source>Unrecognized descriptor found. Loading wallet %s

The wallet might have been created on a newer version.
Please try running the latest software version.
</source>
        <translation>Našiel sa nerozpoznaný deskriptor. Načítava sa peňaženka%s. 

Peňaženka mohla byť vytvorená v novej verzii. 

Spustite najnovšiu verziu softvéru.
</translation>
    
ERR
The translation has a missing space before the "%s" placeholder ("peňaženka%s"), and there are extra spaces/newlines. Slight stylistic improvement for the last sentence is suggested to match "Please try running the latest software version."

Correct translation:
Našiel sa nerozpoznaný deskriptor. Načítava sa peňaženka %s

Peňaženka mohla byť vytvorená v novej verzii.

Skúste spustiť najnovšiu verziu softvéru.
```
</details>

Number of issues: 35.
