# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>lt</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Blt%5D%20request)


<!-- cache_translation_check_lt_f900d8f202b82a411de97e10ae8d3a027030f92db3db7981a798d90f69d825fd -->
```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Bandant išsaugoti adresų sąrašą - įvyko klaida keliant į %1. Prašome bandyti dar kartą.</translation>
    
ERR
The translation is mostly correct in meaning, but the structure is awkward and adds unnecessary wording ("keliant į", which means "uploading to", instead of "saving to"). The dash after "adresų sąrašą" is also unnecessary. The format specifier %1 is correctly transferred.

Correct translation:
Įvyko klaida bandant išsaugoti adresų sąrašą į %1. Prašome bandyti dar kartą.
```

<!-- cache_translation_check_lt_f6b103e237d9f52a912094001086a41dc8faf7c0c1bf16a05ba9c426f5b84834 -->
```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>Įveskite seną ir naują slaptažodį.</translation>
    
ERR
The translation omits "for the wallet" ("piniginės" in Lithuanian), which could clarify which passphrases are meant. Also, the structure loses the explicit separation between old and new passphrase.

Correct translation:
Įveskite seną ir naują piniginės slaptažodį.
```

<!-- cache_translation_check_lt_52ee76e401227a1668290e54050738293c3f5e423cfad9f29d76ba9dbd5882cf -->
```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Atminkite kad piniginės užšifravimas neužtrikrina kad jūsų bitkoinai negali būti pavogti dėl kenkėjiškų programų užkrėtusių jūsų kompiuterį.</translation>
    
ERR
The Lithuanian translation contains several issues:
- "neu��trikrina" is a typo and should be "neužtikrina".
- There are missing commas for proper sentence structure.
- The sentence structure could be improved for clarity and flow.
- The negative construction "kad jūsų bitkoinai negali būti pavogti" translates as "that your bitcoins cannot be stolen", but the original merely says encryption cannot fully protect them from being stolen.
- The translation of "malware infecting your computer" as "kenkėjiškų programų užkrėtusių jūsų kompiuterį" is awkward and the participle is not well-placed.

Correct translation:
Atminkite, kad piniginės užšifravimas negali visiškai apsaugoti jūsų bitkoinų nuo vagystės, jei jūsų kompiuterį užkrečia kenkėjiška programa.
```

<!-- cache_translation_check_lt_d2325cb1defa5d2c551229a30b4515999bd49718f4f61bc4fc3829ac8ad3088a -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation>&amp; Užšifruoti piniginę</translation>
    
ERR
There is an extra space after the '&' in the translation. The shortcut indicator '&' should appear immediately before the letter without a space. Also, the ellipsis '…' from the source is missing and should be preserved.

Correct translation:
&Užšifruoti piniginę…
```

<!-- cache_translation_check_lt_d3ed22d71654f5360300ccee9857f5edc8bf98faff568ab6bc2f30bd5eb3e06f -->
```
        <source>&amp;Command-line options</source>
        <translation>Komandinės eilutės parametrai</translation>
    
ERR
The translation omits the ampersand (&), which is used for shortcut keys. It must appear exactly once, anywhere in the translation.

Correct translation:
&Komandinės eilutės parametrai
```

<!-- cache_translation_check_lt_ca810c270ffdc6797cce6ead371730ec6de422970dc8405c58c880c14bff01bc -->
```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Užkraukite dalinai pasirašytas Bitcoin transakcijas iš iškarpinės...</translation>
    
ERR
There are several issues:
1. "Užkraukite" is an unusual word in this context; "Įkelkite" is more appropriate for 'Load' when referring to data.
2. The English text is singular ("Transaction"), the translation uses plural ("transakcijas").
3. The ellipsis ("...") is not present in the source and should be omitted for consistency.

Correct translation:
Įkelkite dalinai pasirašytą Bitcoin transakciją iš iškarpinės
```

<!-- cache_translation_check_lt_eadda51401fadbd691b3baefdf8a3d6ef636f1bafd725486c08591243da2078c -->
```
        <source>Type: %1
</source>
        <translation>Spausti: %1
</translation>
    
ERR
The Lithuanian word "Spausti" means "Press" or "Click", which is incorrect for "Type". The correct translation for "Type" in this context is "Tipas".

Correct translation:
Tipas: %1
```

<!-- cache_translation_check_lt_c0a7fc3516b8a3dc4c108534a6edfa7991f783b2ba216c2a00082a7857e244ab -->
```
        <source>Label: %1
</source>
        <translation>Antraštė: %1
</translation>
    
ERR
The translation of "Label" as "Antraštė" is incorrect in this context. "Antraštė" means "headline" or "title," not "label." The correct Lithuanian word for "label" (particularly in the Bitcoin UI context) is "Etiketė."

Correct translation:
Etiketė: %1
```

<!-- cache_translation_check_lt_aa64d954ebe5a574ebf6712b6fc14ed90de50dbad2e5c484ad8359ee40dba7e2 -->
```
        <source>Copy change</source>
        <translation>Kopijuoti keisti</translation>
    
ERR
The translation "Kopijuoti keisti" is inaccurate in Lithuanian. The English term "change" in the Bitcoin context means "likutis" or "grąža" (the returned amount in a transaction), not "keisti" (which means "to change" as a verb).

Correct translation:
Kopijuoti grąžą
```

<!-- cache_translation_check_lt_3bebd657861277925df099921d566b99b39ad8b906e16f3c7225a165ef2a527f -->
```
        <source>change from %1 (%2)</source>
        <translation>pakeisti nuo %1 (%2)</translation>
    
ERR
The Lithuanian translation "pakeisti nuo %1 (%2)" means "to change from %1 (%2)", which misinterprets "change" in the context of Bitcoin transactions. Here, "change" refers to the remainder (change amount) returned in a transaction, not the verb "to change." 

Correct translation:
grąža iš %1 (%2)
```

<!-- cache_translation_check_lt_668129a5ce02a3b6ac18e4f389c45da5a4c12678b0694f3aadd779200c66ce30 -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>Patvirtinimų skaičius</translation>
    
ERR
The translation "Patvirtinimų skaičius" means "Number of confirmations" and does not reflect the meaning of "Number of script &verification threads". The translation is also missing the shortcut key (&). 

Correct translation:
Skriptų &patikrinimo gijų skaičius
```

<!-- cache_translation_check_lt_3e6716430b71e28e189b7f480536caec39d6c5ed954d08814b3231d0b987f426 -->
```
        <source>Prune &amp;block storage to</source>
        <translation>&amp;blokuokite saugyklą į</translation>
    
ERR
The translation "&amp;blokuokite saugyklą į" is problematic. The command "Prune &amp;block storage to" refers to reducing (pruning) the amount of disk space used for block storage, not "blocking" or "locking" storage. Additionally, "į" at the end is inappropriate here.

Correct translation:
Apkarpykite &amp;blokų saugyklą iki

This clearly communicates the pruning (apkarpykite) of block storage, and "iki" means "to" (a certain size or amount).
```

<!-- cache_translation_check_lt_29abc9e3a391603d2595d27f49a390e4e3101a61ec04ce5d5e5b412bc689389e -->
```
        <source>W&amp;allet</source>
        <translation>Piniginė</translation>
    
ERR
The translation for "W&allet" is missing the '&', which is necessary to indicate the shortcut key. The '&' must appear exactly once in both source and translation.

Correct translation:
&Pinigine
```

<!-- cache_translation_check_lt_2037a608404eb21e4dfa26873d21f8c37dbe0366633995f88eaee2612f9bf524 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>&amp;Išleiskite nepatvirtintus pakeitimus</translation>
    
ERR
The Lithuanian translation "Išleiskite nepatvirtintus pakeitimus" is problematic. The word "pakeitimai" generally means "changes" (as in modifications), not "change" in the financial sense. The correct term for "change" (as in transaction change output) in Lithuanian is "grąža". Also, the verb form should match the imperative style used in menu commands; "Išleisti" (infinitive) is more appropriate.

Correct translation:
&amp;Išleisti nepatvirtintą grąžą
```

<!-- cache_translation_check_lt_6c0818d210597239fe296b6a40dd67323d466bd5baf70768abfe2db33275972a -->
```
        <source>&amp;Connect through SOCKS5 proxy (default proxy):</source>
        <translation>&amp; Prisijunkite per SOCKS5 proxy (numatytasis proxy):</translation>
    
ERR
There is an unnecessary space after '&amp;' at the start of the translation, which would hinder proper shortcut key functionality. The ampersand should be placed immediately before the shortcut letter with no space.

Correct translation:
&amp;Prisijunkite per SOCKS5 proxy (numatytasis proxy):
```

<!-- cache_translation_check_lt_ee24370a4253cec5e3727aa89688ef4b91c9847ef4dacc472d1add58cda0b450 -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>&amp;M sumažinti langą bet ne užduočių juostą</translation>
    
ERR
The Lithuanian translation is inaccurate. The phrase "M sumažinti langą bet ne užduočių juostą" does not accurately convey minimizing to the tray instead of the taskbar. Also, "&amp;M" is not correctly placed or justified.
Correct translation:
&amp;Sumažinti į sisteminę sritį, o ne į užduočių juostą
```

<!-- cache_translation_check_lt_292816eb4f84dc65ab1bb1e293388d2e717afdc6ea29cc5b5e20c2f835d71374 -->
```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Rodomų ir siunčiamų monetų kiekio matavimo vienetai</translation>
    
ERR  
The Lithuanian translation does not accurately capture the meaning of the source text, which is about "choosing" the default subdivision unit; the translation simply describes "units for displaying and sending coins". Also, the imperative or instruction "Choose" is missing.

Correct translation:  
Pasirinkite numatytąjį monetų padalijimo vienetą, kuris bus rodomas sąsajoje ir siunčiant monetas.
```

<!-- cache_translation_check_lt_db5b0c86ebb1da2641a34460cb0a7be8db5617cd1268d3fad31cbf197d00826b -->
```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Negalima paleisti bitcoin: paspauskite sumokėti tvarkytojui</translation>
    
ERR
The phrase "paspauskite sumokėti tvarkytojui" is a literal translation and does not convey the intended technical meaning of "click-to-pay handler" (i.e., a software handler for click-to-pay functionality). Also, "bitcoin" should be capitalized ("Bitcoin") in Lithuanian, following naming conventions. The translation should convey that the "click-to-pay handler" component of Bitcoin could not be started.

Correct translation:
Negalima paleisti Bitcoin: nepavyksta paleisti „click-to-pay“ tvarkyklės
```

<!-- cache_translation_check_lt_8a707bee3ecdc400464ac5befa9102ee8cd19bf0fd631d92e4ad7c96dc7d0c7d -->
```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>„bitcoin: //“ nėra galiojantis URI. Vietoj to naudokite „bitcoin:“.</translation>
    
ERR
There is an erroneous space in "bitcoin: //" – it should be "bitcoin://", without the space. Also, Lithuanian quotation marks („...“) are correctly used, but the space inside the quotes is problematic.

Correct translation:
„bitcoin://“ nėra galiojantis URI. Vietoj to naudokite „bitcoin:“.
```

<!-- cache_translation_check_lt_5fd62a9a56ae165df8a431aa55e5f81c083487574d07b3880bcf27c941b9f25e -->
```
        <source>&amp;Copy Image</source>
        <translation>Kopijuoti nuotrauką</translation>
    
ERR
The translation does not preserve the shortcut key indicator (&amp;) from the source. It should be present exactly once in the translation.

Correct translation:
&Kopijuoti nuotrauką
```

<!-- cache_translation_check_lt_99742bb7e145d0a1c05251e22d9eeb419ded69e012030b62d1b38799de19a441 -->
```
        <source>&amp;Amount:</source>
        <translation>Suma:</translation>
    
ERR
The translation omits the '&' character, which is used for the shortcut key and must appear exactly once (can be placed anywhere in the word).

Correct translation:
&Suma:
or
S&uma:
```

<!-- cache_translation_check_lt_c3ba5931660aea4df483b1c9c5d150268c4dc81b184cab1f96672f4b7454a871 -->
```
        <source>&amp;Message:</source>
        <translation>Žinutė:</translation>
    
ERR
The shortcut key indicator (&) from the source is missing in the translation. It should appear exactly once in the translation.

Correct translation:
&Žinutė:
</reply>
```

<!-- cache_translation_check_lt_4e3602eecaf894daa951352f67e4a0f5e7d6575153283d173ee538e1524c42b5 -->
```
        <source>Custom change address</source>
        <translation>Pakeisti adresą</translation>
    
ERR
The translation "Pakeisti adresą" means "Change address" (as in "to change the address"), not "Custom change address". It misses both the "custom" aspect and the nuance that this is a special type of address in Bitcoin ("change address" is a technical term).

Correct translation:
Individualus grąžos adresas
```

<!-- cache_translation_check_lt_ab417315ec7ef73142ce42fdad62211d784d0da244706cb5d8bbe32a847cc870 -->
```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Naudojant backbackfee gali būti siunčiamas sandoris, kuris užtruks kelias valandas ar dienas (arba niekada), kad patvirtintų. Apsvarstykite galimybę pasirinkti mokestį rankiniu būdu arba palaukite, kol patvirtinsite visą grandinę.</translation>
    
ERR
There are multiple issues in the translation:
1. Typo: "backbackfee" should be "fallbackfee" or a correct Lithuanian equivalent. The original term should be kept ("fallbackfee", as there is no standard Lithuanian equivalent).
2. The phrase "kad patvirtintų" is grammatically awkward in this sentence and does not accurately render "to confirm". Better: "kad būtų patvirtintas" (so that the transaction is confirmed), or "kad būtų patvirtinta" referring to the action.
3. The sentence about waiting until validating the complete chain should be improved for clarity in Lithuanian.

Correct translation:
Naudojant fallbackfee gali būti išsiųsta transakcija, kurios patvirtinimas gali užtrukti kelias valandas, dienas ar net niekada neįvykti. Apsvarstykite galimybę pasirinkti mokestį rankiniu būdu arba palaukite, kol patvirtinsite visą blokų grandinę.
```

<!-- cache_translation_check_lt_73b5bdd82185727f57b8c3e3ebc542156ba9bdbbc2f60ad9bbf9714370cd4d1e -->
```
        <source>Add &amp;Recipient</source>
        <translation>&amp;A Pridėti gavėją</translation>
    
ERR
There should be only one '&' indicating the shortcut key, but here there are two: one before 'A' and one before 'Pridėti'. Also, the placement is nonstandard and likely to create two shortcut keys. In Lithuanian, the word order should also be consistent with Lithuanian UI terminology.

Correct translation:
Pridėti &gavėją
```

<!-- cache_translation_check_lt_f1763d07ff95b30c13653d890a3a3026880dc85fd5d324de1fd4174f534c3b21 -->
```
        <source>Enable Replace-By-Fee</source>
        <translation>Įgalinti keitimąsi mokesčiu</translation>
    
ERR
The translation "Įgalinti keitimąsi mokesčiu" is not accurate. In the context of Bitcoin, "Replace-By-Fee" refers to a feature that allows transactions to be replaced with another transaction that pays a higher fee. The term "keitimąsi mokesčiu" suggests "exchange with fee" rather than enabling the Replace-By-Fee option.

Correct translation:
Įgalinti pakaitą pagal mokestį
```

<!-- cache_translation_check_lt_418a66fc1b88785dc126a7832f79053edacf4fde5e1823b51795cb5b04ece411 -->
```
        <source>With Replace-By-Fee (BIP-125) you can increase a transaction's fee after it is sent. Without this, a higher fee may be recommended to compensate for increased transaction delay risk.</source>
        <translation>Naudojant Replace-by-Fend (BIP-125) galite išsiųsti sandorio mokestį vėliau. Be jo, gali būti rekomenduojamas didesnis mokestis, kad būtų kompensuota padidėjusi sandorio vėlavimo rizika.</translation>
    
ERR
There is an error in the translation:

1. "Replace-by-Fend" is incorrect. It should be "Replace-by-Fee".
2. The phrase "galite išsiųsti sandorio mokestį vėliau" mistranslates the meaning. It should convey the idea of increasing the fee after sending the transaction, not sending the fee later.
3. The rest of the translation is acceptable, but to increase accuracy and maintain the original meaning, the sentence structure should be revised.

Correct translation:
Naudodami Replace-by-Fee (BIP-125) galite padidinti sandorio mokestį po jo išsiuntimo. Be šios galimybės gali būti rekomenduojamas didesnis mokestis, kad būtų kompensuota padidėjusi sandorio vėlavimo rizika.
```

<!-- cache_translation_check_lt_aa64d954ebe5a574ebf6712b6fc14ed90de50dbad2e5c484ad8359ee40dba7e2 -->
```
        <source>Copy change</source>
        <translation>Kopijuoti keisti</translation>
    
ERR
The translation "Kopijuoti keisti" is inaccurate in Lithuanian. The English term "change" in the Bitcoin context means "likutis" or "grąža" (the returned amount in a transaction), not "keisti" (which means "to change" as a verb).

Correct translation:
Kopijuoti grąžą
```

<!-- cache_translation_check_lt_ec028baa38439cab852e3942deb898cc33c2dcf09ee1b7df40b04361820a03ff -->
```
        <source>Paste address from clipboard</source>
        <translation>Įvesti adresą iš mainų atminties</translation>
    
ERR
The Lithuanian translation "Įvesti adresą iš mainų atminties" means "Enter address from clipboard". The verb "Įvesti" is "enter" or "input," whereas "Paste" should be translated as "Įklijuoti." The remainder of the translation is correct.

Correct translation:
Įklijuoti adresą iš mainų atminties
```

<!-- cache_translation_check_lt_e35dc4b680a5220da16e938fa875434161c4d84c02d8275b320027fdc097c4ac -->
```
        <source>The Bitcoin address to sign the message with</source>
        <translation>Bitcoin adresas, kuriuo bus pasirašytas pranešimas su</translation>
    
ERR
The Lithuanian translation "Bitcoin adresas, kuriuo bus pasirašytas pranešimas su" is grammatically incorrect; the word "su" ("with") is redundant at the end and makes the sentence ungrammatical. Correct translation should be:

Bitcoin adresas, kuriuo bus pasirašytas pranešimas
```

<!-- cache_translation_check_lt_ec028baa38439cab852e3942deb898cc33c2dcf09ee1b7df40b04361820a03ff -->
```
        <source>Paste address from clipboard</source>
        <translation>Įvesti adresą iš mainų atminties</translation>
    
ERR
The Lithuanian translation "Įvesti adresą iš mainų atminties" means "Enter address from clipboard". The verb "Įvesti" is "enter" or "input," whereas "Paste" should be translated as "Įklijuoti." The remainder of the translation is correct.

Correct translation:
Įklijuoti adresą iš mainų atminties
```

<!-- cache_translation_check_lt_49c51ff5df81e01ecdf190cc7e3a8d872d2cd5a1657476f070fc903706b04a63 -->
```
        <source>Sign the message to prove you own this Bitcoin address</source>
        <translation>Registruotis žinute įrodymuii, kad turite šį adresą</translation>
    
ERR
The translation is inaccurate. "Registruotis žinute" does not correctly convey "Sign the message" (should be "Pasirašykite žinutę"). "įrodymuii" is a typo and not correct. Also, it omits "Bitcoin" and "adresas/adresą", making it inaccurate for the Bitcoin context.

Correct translation:
Pasirašykite žinutę, kad įrodytumėte, jog valdote šį Bitcoin adresą
```

<!-- cache_translation_check_lt_ede15d87202b85a6153a96e6a81349a2f7ed3fb7f3ebf6a8d8702e98b1cf3f2e -->
```
        <source>Sign &amp;Message</source>
        <translation>Registruoti praneši&amp;mą</translation>
    
ERR
The Lithuanian verb "registruoti" means "to register," which is not the correct translation for "Sign" in this Bitcoin context. The correct Lithuanian translation for "Sign &Message" (as in 'digitally sign a message') is "Pasirašyti praneši&amp;mą". The ampersand (&amp;) is placed correctly.

Correct translation:
Pasirašyti praneši&amp;mą
```

<!-- cache_translation_check_lt_17bed199aaf715f37a920f547c5620cfa8439c55a647770456a52a8eb968d187 -->
```
        <source>The signature did not match the message digest.</source>
        <translation>Parašas neatitinka žinutės.</translation>
    
ERR
The translation is inaccurate. The source refers specifically to the message digest (a cryptographic hash of the message), but the translation omits "digest" and only refers to the "message" ("žinutės"), which reduces clarity regarding cryptographic context.

Correct translation:
Parašas neatitinka žinutės santraukos.
```

<!-- cache_translation_check_lt_001841626dd5e3b3229bafc934ff5bb25f9d6aca018d81141507dfe2e2e73951 -->
```
        <source>This pane shows a detailed description of the transaction</source>
        <translation>Šis langas sandorio detalų aprašymą</translation>
    
ERR  
The Lithuanian translation is missing a verb and is grammatically incorrect. It should read as a full sentence.

Correct translation:  
Šiame lange rodomas išsamus sandorio aprašymas
```

<!-- cache_translation_check_lt_194058a6af4f7326cc91058da8dba324a37680ce50dc519d13a7b3db49ad4ecb -->
```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>Patvirtinima (%1 iš rekomenduojamų patvirtinimų %2)</translation>
    
ERR
The word "Patvirtinima" is incorrectly rendered and should be "Patvirtinama". The structure of the translation is unnatural, and the order of elements does not match the source. The correct translation should preserve the format specifiers and accurately reflect the original structure.

Correct translation:
Patvirtinama (%1 iš %2 rekomenduojamų patvirtinimų)
```

<!-- cache_translation_check_lt_b227dfeaacb95449caf13796d25ee3fee1616bf9554f25f541f3adc1b03c6963 -->
```
        <source>Confirmed (%1 confirmations)</source>
        <translation>Patvirtinta (%1 patvirtinimas)</translation>
    
ERR
The translation does not correctly reflect the plural form "confirmations." The Lithuanian translation uses the singular "patvirtinimas," but it should be plural to match the English source.

Correct translation:
Patvirtinta (%1 patvirtinimai)
```

<!-- cache_translation_check_lt_6b1b1da74dd95ba26e5e5d12c05ba8fec54af1522ba7a1a95fe6dba6b9518d2a -->
```
        <source>Enter address, transaction id, or label to search</source>
        <translation>Įveskite adresą ar žymę į paiešką</translation>
    
ERR
The translation omits "transaction id" (sandorio ID) from the source, making it incomplete. The English "or" ("ar") should also consistently separate all options.

Correct translation:
Įveskite adresą, sandorio ID arba žymę paieškai
```

<!-- cache_translation_check_lt_9471fad2cfdbaea58a915be6423ad5d75994af45457cda9c63557ea20822c4ec -->
```
        <source>Error loading %s: Wallet requires newer version of %s</source>
        <translation>Klaida įkeliant %s: Piniginei reikia naujesnės%s versijos</translation>
    
ERR
There is a spacing error in the translation: "naujesnės%s versijos" should be "naujesnės %s versijos" (a space is missing before %s). Additionally, the word order is a bit awkward; a clearer translation would be:

Correct translation:
Klaida įkeliant %s: piniginei reikia naujesnės %s versijos
```
</details>

Number of issues: 39.
