# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>hr</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bhr%5D%20request)


<!-- cache_translation_check_hr_26012c814f0c86a6c2b1e17dbc4f2719566da9997c6a8e400ea122e28a39d1e1 -->
```
        <source>Create a new address</source>
        <translation>Stvoriti  novu adresu</translation>
    
ERR
There is an unnecessary space between "Stvoriti" and "novu", and the verb form should be imperative ("Stvori") instead of infinitive ("Stvoriti") to match the context.

Correct translation:
Stvori novu adresu
```

<!-- cache_translation_check_hr_b4b35589f1e76b9476d517c46d6e46d7ae61f1154c319f9cf29dc7f19ed753a7 -->
```
        <source>&amp;Edit</source>
        <translation>&amp;Uredite</translation>
    
ERR
The translation "&amp;Uredite" uses the imperative form ("Uredite"), which means "Edit (you all)" or "Please edit". The correct translation for menu items like "&amp;Edit" is simply the noun "Uredi".

Correct translation:
&amp;Uredi
```

<!-- cache_translation_check_hr_03f7c961f8ac151838d9dbd2507a38d10910bf629575b8891159f6bf10b344b3 -->
```
        <source>Show information about %1</source>
        <translation>Prikažite informacije o programu %1</translation>
    
ERR
The translation adds "programu" ("program"), which is not present in the source text. The original talks about showing information about %1, which could refer to more than just a program (for example, a network or transaction).

Correct translation:
Prikaži informacije o %1
```

<!-- cache_translation_check_hr_46706c0807fcee136254a4484a6f6e4d6a141d2046714caf87e41877132248a9 -->
```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Provjerite poruku da je potpisana s navedenom Bitcoin adresom</translation>
    
ERR
The translation is inaccurate: the source refers to "messages" (plural), but the translation uses the singular "poruku". Also, "to ensure they were signed" is not precisely captured; the translation says "that it is signed", missing the verification aspect. For greater accuracy and correct pluralization:

Correct translation:
Provjerite poruke kako biste bili sigurni da su potpisane s navedenim Bitcoin adresama
```

<!-- cache_translation_check_hr_18d16a9b27daddf65862f7939a28c0319c9e75d9d7b0aa6780d711b794002bac -->
```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Pokaži Peers tab </translation>
    
ERR
The translation leaves "Peers tab" untranslated, which is not idiomatic in Croatian. "Peers" can be translated as "Čvorovi" or "Sudionici", and "tab" as "kartica". It also has a stray space at the end.

Correct translation:
Pokaži karticu Čvorovi
```

<!-- cache_translation_check_hr_d3e7768970690f8493535d52189133e03a85f4b9956ec39132542730ad370bf2 -->
```
        <source>Copy bytes</source>
        <translation>Kopirajte količinu bajtova</translation>
    
ERR
The translation is misleading. The English "Copy bytes" refers to copying the actual bytes (data), but the Croatian translation "Kopirajte količinu bajtova" means "Copy the amount of bytes," which wrongly suggests copying a number or quantity rather than the data itself.

Correct translation:
Kopiraj bajtove
```

<!-- cache_translation_check_hr_e75597fcea6b271ac140ffa5ce32f3843331e19aba186f64de02ef64d27c1fb9 -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Kompajlirano bez mogućnosti vanjskog potpisivanje (potrebno za vanjsko potpisivanje)</translation>
    
ERR
There is a grammatical error: "vanjskog potpisivanje" should be "vanjskog potpisivanja" (genitive case consistency). Also, for clarity, "mogućnosti vanjskog potpisivanja" could be better as "podrške za vanjsko potpisivanje".

Correct translation:
Kompajlirano bez podrške za vanjsko potpisivanje (potrebno za vanjsko potpisivanje)
```

<!-- cache_translation_check_hr_346a8d8d4b30a887b393c2669d2db7d70232bd90d4aa236602a694ab816481e1 -->
```
        <source>%1 is shutting down…</source>
        <translation>%1 do zatvaranja...</translation>
    
ERR
The translation "do zatvaranja..." implies "until closing..." rather than "[is] shutting down." Also, the ellipsis uses three periods instead of the correct Unicode ellipsis (as in the source, "…"). The translation should accurately reflect the continuous action.

Correct translation:
%1 se gasi…
```

<!-- cache_translation_check_hr_0cdd94c24a5ea3e86496fbef3dd3894326f67dab955918afe9cec6eadcbfbedb -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>Broj CPU niti za verifikaciju transakcija</translation>
    
ERR
The translation does not accurately capture the source text:
- The phrase "script verification" is not translated ("verifikacija skripte" or "verifikacija skripata" should be used depending on plurality), and instead it refers to "verification of transactions", which is incorrect.
- The translation omits the ampersand ("&") intended for a shortcut key.

Correct translation:
Broj niti za &verifikaciju skripte
```

<!-- cache_translation_check_hr_66598c584210e780dcff2f8726c8c1c80dac2a7f5cdb9c0480db1d71f866b6f5 -->
```
        <source>Expert</source>
        <translation>Stručne postavke</translation>
    
ERR
The translation "Stručne postavke" means "Brief settings" and does not correspond to the English term "Expert". The correct Croatian translation for "Expert" would be "Stručnjak" or, if it refers to an "Expert" mode or setting, "Napredno" or "Ekspert".

Correct translation:
Ekspert

(or if used as a label for a mode: "Napredno" or "Ekspertni način" depending on context)
```

<!-- cache_translation_check_hr_5f9219de0e1c1c1e03f8d857c1fb0d77aaac2961f74be47181b34f1cf816e061 -->
```
        <source>Enable coin &amp;control features</source>
        <translation>Uključite postavke kontroliranja inputa</translation>
    
ERR
The translation is not fully accurate. "Enable coin &control features" should refer to enabling coin control functionalities in the Bitcoin context, not just "control of inputs". Also, the "&" for the accelerator key is missing from the translation.

Correct translation:
Omogući značajke &kontrole kovanica
```

<!-- cache_translation_check_hr_1dedc051c5488e060f7ee40f141d6daee908f77b152b2759aec96f30f98e8950 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>&amp;Trošenje nepotvrđenih vraćenih iznosa</translation>
    
ERR
The translation "Trošenje nepotvrđenih vraćenih iznosa" is understandable but is not the most accurate or idiomatic for the context. "Change" in Bitcoin refers to the "ostatak" (change amount) from a transaction, not "vraćeni iznos" (returned amount). Also, "Trošenje" is a noun, making the menu option sound odd; the English uses the imperative verb "Spend".

Correct translation:
&amp;Potroši nepotvrđeni ostatak
```

<!-- cache_translation_check_hr_b288a44058e70f9db1fd99e134ac7e4d110a15e8e714aeedb07800dc819f0a07 -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Uključi  &amp;PBST opcije za upravljanje</translation>
    
ERR
There are a couple of issues:
- The acronym PSBT was incorrectly transcribed as PBST in the translation.
- There is an extra space between "Uključi" and "&amp;PBST".

Correct translation:
Uključi &amp;PSBT opcije za upravljanje
```

<!-- cache_translation_check_hr_89d048f40d2a21beb3379f7d55309274cc6a0d56741f0db63886106c6de76ee3 -->
```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Za prikazivanje PSBT opcija za upravaljanje. </translation>
    
ERR
There is a typo in the word "upravljanje" (written as "upravaljanje"). Also, the translation could be more concise and natural. The extra space before the period should be removed.

Correct translation:
Za prikazivanje PSBT kontrola.
```

<!-- cache_translation_check_hr_dced7ef91db0abe507eca26f3cc1e53df656cd8d610972a6ba5b5ac2daafae67 -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Dozvolite dolazeće veze</translation>
    
ERR
The translation omits the shortcut indicator '&' from the original. It should appear exactly once in the translation to match the functionality.

Correct translation:
Dozvolite dolazeće v&eze
```

<!-- cache_translation_check_hr_66f918b464dd117ad0e13fa6ec3908aca0b288b65f91512c086e87096c6c277f -->
```
        <source>Used for reaching peers via:</source>
        <translation>Korišten za dohvaćanje klijenata preko:</translation>
    
ERR
The word "peers" in the Bitcoin context means "čvorovi" or "peerovi" (nodes/peers) rather than "klijenati" (clients), which is a misinterpretation in Bitcoin networking.

Correct translation:
Korišten za dohvaćanje čvorova preko:
```

<!-- cache_translation_check_hr_4430e8dcc4ab45d681eed8f02cff741c7f88f3ccb65e691a96eb0ac6b2440300 -->
```
        <source>&amp;Show tray icon</source>
        <translation>&amp;Pokaži ikonu</translation>
    
ERR
The translation omits "tray" from "tray icon", making it less specific and potentially confusing.

Correct translation:
&amp;Pokaži ikonu u traci sustava
```

<!-- cache_translation_check_hr_e75597fcea6b271ac140ffa5ce32f3843331e19aba186f64de02ef64d27c1fb9 -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Kompajlirano bez mogućnosti vanjskog potpisivanje (potrebno za vanjsko potpisivanje)</translation>
    
ERR
There is a grammatical error: "vanjskog potpisivanje" should be "vanjskog potpisivanja" (genitive case consistency). Also, for clarity, "mogućnosti vanjskog potpisivanja" could be better as "podrške za vanjsko potpisivanje".

Correct translation:
Kompajlirano bez podrške za vanjsko potpisivanje (potrebno za vanjsko potpisivanje)
```

<!-- cache_translation_check_hr_597a95f393d920d628aac154e0e5ae93f06283bc64d9b9e98fce30fb0bc47e63 -->
```
        <source>&amp;Peers</source>
        <translation>&amp;Klijenti</translation>
    
ERR
The English term "Peers" in the context of Bitcoin refers to network participants or nodes, not clients. The correct Croatian translation in this context is "Čvorovi" or "Poveznici", but the most direct equivalent is "Čvorovi".

Correct translation:
&Čvorovi
```

<!-- cache_translation_check_hr_1de257d25b7e98a5189288a21acca868f60b267a7a650aec79fde3bb819fc8e9 -->
```
        <source>Select a peer to view detailed information.</source>
        <translation>Odaberite klijent kako biste vidjeli detaljne informacije.</translation>
    
ERR
The translation uses "klijent" (client) instead of "peer". In the Bitcoin context, "peer" should be translated as "peer" or "čvor" (node), not "klijent". Also, "kako biste" can simply be "za prikaz".

Correct translation:
Odaberite peer za prikaz detaljnih informacija.
or
Odaberite čvor za prikaz detaljnih informacija.
```

<!-- cache_translation_check_hr_b8e0afcb96b0c89d53fbaebe84c8022a3f6eb37b7a435f9242dc06c16a345e8d -->
```
        <source>Outbound Manual: added using RPC %1 or %2/%3 configuration options</source>
        <extracomment>Explanatory text for an outbound peer connection that was established manually through one of several methods. The numbered arguments are stand-ins for the methods available to establish manual connections.</extracomment>
        <translation>Priručnik za izlazeće (?): dodano koristeći RPC %1 ili %2/%3 konfiguracijske opcije</translation>
    
ERR
The translation is inaccurate and awkward. "Priručnik za izlazeće (?)" incorrectly renders "Outbound Manual"—it suggests something like "Manual for outgoing (?),” which does not fit the context. The correct translation should capture the notion that the outbound connection was manually added, not refer to a manual (booklet).

Correct translation:
Izlazna veza (ručno): dodano korištenjem RPC %1 ili %2/%3 konfiguracijskih opcija
```

<!-- cache_translation_check_hr_217e1d31eded8250979c4794ba42ff28bbd2d2d126c2c46baaa1ef5038a1e532 -->
```
        <source>no high bandwidth relay selected</source>
        <translation>brzopodatkovni prijenos nije odabran</translation>
    
ERR
The translation is inaccurate. "brzopodatkovni prijenos nije odabran" means "high data transfer is not selected," which does not reflect the original context regarding selecting a high bandwidth relay. 

Correct translation:
"Nije odabran relej s velikom propusnošću"
```

<!-- cache_translation_check_hr_3135adcf24e90016c88d5eab9288c84cc138729484fe3bf024353c8b5654538d -->
```
        <source>Ban for</source>
        <translation>Zabranite za</translation>
    
ERR
The translation "Zabranite za" is not idiomatic and does not accurately convey "Ban for" in Croatian. It should use a form that matches context, e.g., "Zabrana na" (if referring to duration, e.g., "Ban for 24 hours" → "Zabrana na 24 sata").

Correct translation:
Zabrana na
```

<!-- cache_translation_check_hr_b948c0ee8aabddba4b2f7ba69a9d50b4b4699b99b0d38eca1bf77dc6a8783f19 -->
```
        <source>Custom change address</source>
        <translation>Zadana adresa u koju će ostatak biti poslan</translation>
    
ERR
The translation is understandable, but it is not accurate. The English phrase "Custom change address" refers specifically to a user-specified "change address" in the context of Bitcoin. The provided translation ("Zadana adresa u koju će ostatak biti poslan") expands the meaning and does not explicitly mention that it's a change address, which could confuse users familiar with the term.

Correct translation:
Prilagođena adresa za ostatak
```

<!-- cache_translation_check_hr_ba43dbabcee25e27e7941cee634d2751f8ce128e2960ffe9c578cc76aef4044b -->
```
        <source>Send to multiple recipients at once</source>
        <translation>Pošalji novce većem broju primatelja u jednoj transakciji</translation>
    
ERR
The translation adds extra information ("u jednoj transakciji" meaning "in one transaction") that is not present in the source. Also, "novce" ("money") is implied but not explicit in the source.

Correct translation:
Pošalji više primatelja odjednom
```

<!-- cache_translation_check_hr_d3e7768970690f8493535d52189133e03a85f4b9956ec39132542730ad370bf2 -->
```
        <source>Copy bytes</source>
        <translation>Kopirajte količinu bajtova</translation>
    
ERR
The translation is misleading. The English "Copy bytes" refers to copying the actual bytes (data), but the Croatian translation "Kopirajte količinu bajtova" means "Copy the amount of bytes," which wrongly suggests copying a number or quantity rather than the data itself.

Correct translation:
Kopiraj bajtove
```

<!-- cache_translation_check_hr_ae1ecd8c9051cf1e0be209f680ac7f987a5f068b498e75d6854ae9c5fba0b8fa -->
```
        <source>Cr&amp;eate Unsigned</source>
        <translation>Cr&amp;eate nije potpisan</translation>
    
ERR
The translation is incorrect. It retains the English word "Create" rather than translating it into Croatian, and the structure is wrong. The correct translation should read:

Stvori &amp;nepotpisano

This preserves the shortcut key (&amp;), which can appear anywhere but must exist once, and provides an accurate and idiomatic Croatian translation.
```

<!-- cache_translation_check_hr_20177be8f12e1ae042f752f302911e11e46b9fd8fb211c318fbda427b4f310fb -->
```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>Molimo pregledajte svoj prijedlog transakcije. Ovo će stvoriti djelomično potpisanu Bitcoin transakciju (PBST) koju možete spremiti ili kopirati i zatim potpisati sa npr. novčanikom %1 koji nije povezan s mrežom ili sa PSBT kompatibilnim hardverskim novčanikom.</translation>
    
ERR
There is a typographical error: "PBST" should be "PSBT". Additionally, "sa npr." would be better as "npr. s". The phrase "novčanikom %1 koji nije povezan s mrežom" translates to "a %1 wallet that is not connected to the network", which is a correct interpretation of "an offline %1 wallet", but a more faithful translation would be "offline novčanikom %1". Also, PSBT-compatible should include a hyphen: "PSBT-kompatibilnim".

Correct translation:
Molimo, pregledajte svoj prijedlog transakcije. Ovo će stvoriti djelomično potpisanu Bitcoin transakciju (PSBT) koju možete spremiti ili kopirati, a zatim potpisati npr. offline novčanikom %1 ili PSBT-kompatibilnim hardverskim novčanikom.
```

<!-- cache_translation_check_hr_bcf0abeef6ced396c05782e4804879e1987fbb6a09aa9825b58e55122d05196f -->
```
        <source>Please, review your transaction. You can create and send this transaction or create a Partially Signed Bitcoin Transaction (PSBT), which you can save or copy and then sign with, e.g., an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can send their transaction or create a PSBT. This string is displayed when both private keys and PSBT controls are enabled.</extracomment>
        <translation>Molimo pregledajte svoju transakciju. Možete kreirarti i poslati ovu transakciju ili kreirati djelomično potpisanu Bitcoin transakciju (PBST) koju možete spremiti ili kopirati i zatim potpisati sa npr. novčanikom %1 koji nije povezan s mrežom ili sa PSBT kompatibilnim hardverskim novčanikom.</translation>
    
ERR
There are a few issues:
1. Typo: "kreirarti" should be "kreirati".
2. Abbreviation error: should be "PSBT", not "PBST" — the original uses "PSBT".
3. Style: "sa npr. novčanikom %1 koji nije povezan s mrežom" is fine, but "offline novčanikom %1" is clearer for "offline %1 wallet".
4. "sa PSBT kompatibilnim hardverskim novčanikom" should be "PSBT-kompatibilnim hardverskim novčanikom".

Correct translation:
Molimo pregledajte svoju transakciju. Možete kreirati i poslati ovu transakciju ili kreirati djelomično potpisanu Bitcoin transakciju (PSBT), koju možete spremiti ili kopirati i zatim potpisati, npr. s offline novčanikom %1 ili s PSBT-kompatibilnim hardverskim novčanikom.
```

<!-- cache_translation_check_hr_ec60bd28d2de85d3daccd925fc40092b630eb84a7117ae5f291d2a365dded8c8 -->
```
        <source>Transaction creation failed!</source>
        <translation>Neuspješno stvorenje transakcije!</translation>
    
ERR
The translation is understandable but is not idiomatic Croatian. "Neuspješno stvorenje" is awkward and not correct; the noun "stvorenje" means "creature". A more natural translation would be:

Transakcija nije uspjela!
or
Stvaranje transakcije nije uspjelo!

Correct translation:
Stvaranje transakcije nije uspjelo!
```

<!-- cache_translation_check_hr_c46c067f11580c3fdd90aec51338054081135be5baf77f879e3898bc009d5bfa -->
```
        <source>S&amp;ubtract fee from amount</source>
        <translation>Oduzmite naknadu od iznosa</translation>
    
ERR
The translation does not preserve the '&' shortcut key indicator from the source. The target text should include exactly one '&' to specify the shortcut key.

Correct translation:
&Oduzmite naknadu od iznosa
```

<!-- cache_translation_check_hr_d353131ca8a8369e03786f8e948691e7c7bed8b5ce0c3dc188bc2aff148e0214 -->
```
        <source>conflicted with a transaction with %1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that conflicts with a confirmed transaction.</extracomment>
        <translation>subokljen s transakcijom broja potvrde %1</translation>
    
ERR
The translation is problematic. The word "subokljen" is incorrect in Croatian; likely a typo of "sukobljen" (conflicted). Additionally, "broja potvrde %1" is an incorrect structure; it should reflect "with %1 confirmations." A correct and natural translation would be:

Correct translation:
Sukobljen s transakcijom koja ima %1 potvrda
```

<!-- cache_translation_check_hr_ebd505e662608aea7fe43a781f33102d9635379cfa84929388fb2595e4df857d -->
```
        <source>Transaction status. Hover over this field to show number of confirmations.</source>
        <translation>Status transakcije</translation>
    
ERR
The translation is incomplete; it only translates "Transaction status" and omits "Hover over this field to show number of confirmations." The user would miss important information.

Correct translation:
Status transakcije. Zadržite pokazivač miša iznad ovog polja kako biste prikazali broj potvrda.
```

<!-- cache_translation_check_hr_a6318952ca5f7ba25a59e6a58b580d4237fd32f85841f0a698c3088782871ed2 -->
```
        <source>No wallet has been loaded.
Go to File &gt; Open Wallet to load a wallet.
- OR -</source>
        <translation>Nijedan novčanik nije učitan.
Idi na Datoteka &gt;  Otvori novčanik za učitanje novčanika.
- ILI -</translation>
    
ERR
There is an unnecessary double space after "&gt;" and the phrase "za učitanje novčanika" is awkward; "kako biste učitali novčanik" would be more natural. Also, "ILI" is a valid alternative for "- OR -" in Croatian.

Correct translation:
Nijedan novčanik nije učitan.
Idi na Datoteka &gt; Otvori novčanik kako biste učitali novčanik.
- ILI -
```

<!-- cache_translation_check_hr_5f0328459a63610a43605f04a05389f4b0d2caa8bb70d4b516dd435dee79a8d6 -->
```
        <source>File %s already exists. If you are sure this is what you want, move it out of the way first.</source>
        <translation>Datoteka %s već postoji. Ako ste sigurni da ovo želite, prvo ju maknite, </translation>
    
ERR
The translation is incomplete and ends with a comma, leaving the sentence unfinished. Additionally, the pronoun "ju" is correct for "datoteka" (feminine), but the sentence should not end with a comma.

Correct translation:
Datoteka %s već postoji. Ako ste sigurni da je to ono što želite, najprije je premjestite.
```

<!-- cache_translation_check_hr_052df137fb8488f9d21b2a5d4890e11789d84989120071143b2151a5a2b05c8a -->
```
        <source>No dump file provided. To use createfromdump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>Dump datoteka nije automatski dostupna. Kako biste koristili createfromdump, -dumpfile=&lt;filename&gt; mora biti osiguran. </translation>
    
ERR
The translation is understandable but has issues:
1. The English "No dump file provided." is translated as "Dump datoteka nije automatski dostupna," which changes the meaning; it should directly state that no dump file was provided, not that it's "not automatically available."
2. The English "must be provided" is translated as "mora biti osiguran," which is less idiomatic than "mora biti naveden."
3. There is an unnecessary space before the closing tag.

Correct translation:
Nije navedena dump datoteka. Da biste koristili createfromdump, morate navesti -dumpfile=&lt;filename&gt;.
```

<!-- cache_translation_check_hr_541da5a38662f5ae4e48ac2b0de8280e93c88fead4a57dac806a808ac3d11eb7 -->
```
        <source>Error: Couldn't create cursor into database</source>
        <translation>Greška: Nije moguće kreirati cursor u batu podataka</translation>
    
ERR
There is an error in the translation: "cursor" is left untranslated, and "batu podataka" is incorrect—it should be "baz u podataka". The correct translation of "cursor" would be "kursor" or "pokazivač".

Correct translation:
Greška: Nije moguće kreirati kursor u bazi podataka
```

<!-- cache_translation_check_hr_3fe758b41b31804694131ae788d8c511e5113394070a19c2555d81c353fd6bf3 -->
```
        <source>Pruning blockstore…</source>
        <translation>Pruning blockstore-a...</translation>
    
ERR
The translation uses an English loanword ("Pruning") instead of the correct Croatian term, and the ellipsis should be three dots (as in original), but using the Croatian ellipsis character (…) is also acceptable. However, "blockstore-a" is somewhat awkward; a better translation would Croatianize both terms or at least "pruning".

Correct translation:
Smanjujem spremište blokova...
or more literally,
Obrezujem spremište blokova...
or, if you want to be more technical,
Prerađujem spremište blokova...

Any of the above would be clearer and better localized than retaining English terms.
```

<!-- cache_translation_check_hr_80b8d28602d1bb27c91f6dff56df8120e86df22151d3a459c398cf6110919744 -->
```
        <source>The transaction amount is too small to pay the fee</source>
        <translation>Transakcijiski iznos je premalen da plati naknadu</translation>
    
ERR
The word "Transakcijiski" is incorrect; the correct adjective form in Croatian is "Transakcijski". Furthermore, "da plati naknadu" sounds awkward. A more natural phrasing would be "za plaćanje naknade".

Correct translation:
Transakcijski iznos je premalen za plaćanje naknade
```

<!-- cache_translation_check_hr_c0fe71c5d8603125078770f76dabb704831020449ba5cf9d67880fa8bdb1b58f -->
```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>Transakciji je potrebna change adresa, ali ju ne možemo generirati.</translation>
    
ERR
The term "change adresa" uses the English word "change" instead of its proper Croatian equivalent. The correct translation for "change address" in the Bitcoin context is "adresa za ostatak" or "adresa za povrat ostatka".

Correct translation:
Transakciji je potrebna adresa za ostatak, ali ju ne možemo generirati.
```

<!-- cache_translation_check_hr_3e09a512862062ec7535ac0c633a46c1d1d1004b70bdbf341cc9861265ccf6cf -->
```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation> Nepoznata nova pravila aktivirana (versionbit %i)</translation>
    
ERR
There is an unwanted leading space before the translation and an unnecessary trailing space at the end. Otherwise, the translation is accurate and correct.

Correct translation:
Nepoznata nova pravila aktivirana (versionbit %i)
```

<!-- cache_translation_check_hr_32e5468c5429841d27a4c5651ea21c90af808bb04f6f5caaa1c0a7819c628bc7 -->
```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Novčanik je trebao prepravak: ponovo pokrenite %s</translation>
    
ERR
The translation omits the "to complete" part of the source, which indicates that the restart is needed to finish the rewriting process.

Correct translation:
Novčanik je trebao biti prepravljen: za dovršetak ponovo pokrenite %s
```

<!-- cache_translation_check_hr_0d6d7952bf5632f694b26055c5e99c695463728423ff7bcd131b5c20c349df68 -->
```
        <source>Settings file could not be written</source>
        <translation>Datoteka postavke se ne može mijenjati</translation>
    
ERR
The translation is inaccurate. The source says the "settings file could not be written," meaning the file could not be saved or written to. The translation "Datoteka postavke se ne može mijenjati" means "Settings file cannot be changed," which is not precise and omits the concept of a failed write operation.

Correct translation:
Datoteku s postavkama nije moguće zapisati
```
</details>

Number of issues: 43.
