# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>eu</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Beu%5D%20request)


<!-- cache_translation_check_eu_fb70a25373dbd8aebeaa6890a9976a52a7ccd96d3d78c453497d84550004a47c -->
```
        <source>Copy the currently selected address to the clipboard</source>
        <translation>Kopiatu hautatutako helbidea arbelean</translation>
    
ERR
The translation uses the inessive case ("arbelean" - in the clipboard) instead of the allative case ("arbelera" - to the clipboard). In Basque, when expressing the destination of an action like "copy to", the allative suffix "-ra" should be used. Additionally, "currently" is omitted, though "hautatutako" (selected) is often acceptable in UI contexts.

Correct translation:
Kopiatu unean hautatutako helbidea arbelera
```

<!-- cache_translation_check_eu_95f0e277c40cc9e8627e38e4d7caffa7f1912d0e0c426c8653af66b086bfd248 -->
```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>zorroaren pasahitza behar du eragiketa honek, zure zorroa desblokeatzeko.</translation>
    
ERR
The translation starts with a lowercase letter, whereas the source starts with an uppercase letter. Additionally, the word order is slightly unnatural for a technical user interface, and it misses the possessive "zure" (your) for the first mention of the wallet.

Correct translation:
Eragiketa honek zure zorroaren pasahitza behar du zorroa desblokeatzeko.
```

<!-- cache_translation_check_eu_07dd8e5bbff4b11e7d23557e7ae93cb5f26fc87b1c50e8af2211422bb23bf1dd -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Diruzorroaren pasahitz berria sartu. &lt;br/&gt;Mesedez &lt;b&gt; hamar edo gehiago ausazko hizkiko&lt;/b&gt; pasahitza erabili, edo &lt;b&gt; gutxienez zortzi hitz&lt;/b&gt;</translation>
    
ERR
The Basque translation contains grammar and fluency issues:
- "Diruzorroaren" is an uncommon (literal) translation for "wallet" in Basque; "zorro" is more common.
- The sentence structure and word order are not fully natural.
- There is a missing full stop at the end, and "erabili" is not capitalized otherwise.
- The translation omits "Please use a passphrase of ...", which should be "Erabili mesedez ..." or similar.
- The phrase "hogeita hamar edo gehiago ausazko hizkiko" is awkward and should be "... hamar karaktere edo gehiago ausazkoak ..." (characters) and similarly for words.
- The tag and bold markup are transferred correctly.

Correct translation:
Sartu zorroaren pasahitz berria.&lt;br/&gt;Mesedez, erabili &lt;b&gt;hamar karaktere edo gehiago ausazkoak&lt;/b&gt; dituen pasahitza, edo &lt;b&gt;gutxienez zortzi hitz&lt;/b&gt;.
```

<!-- cache_translation_check_eu_14eba1aaa1b6c2fd5630e56826faf0de2b0a6224121efafed33ac4b8458b1904 -->
```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Gogoan izan zorroaren enkripzioak ezin dituela zure bitcoinak zure ordenagailuan izan dezakezun malware batengandik lapurtuak izatetik guztiz babestu .</translation>
    
ERR
There is a stray space before the final period.

Correct translation:
Gogoan izan zorroaren enkripzioak ezin dituela zure bitcoinak zure ordenagailuan izan dezakezun malware batengandik lapurtuak izatetik guztiz babestu.
```

<!-- cache_translation_check_eu_f7cc5ec329fc9607814621f8325b29daa5da36acedc041b9a1b9a1088f7decc8 -->
```
        <source>Your wallet is about to be encrypted. </source>
        <translation>Zure zorroa enkriptatzekotan dago</translation>
    
ERR
The translation is missing the trailing period and space present in the source text.

Correct translation:
Zure zorroa enkriptatzekotan dago.
```

<!-- cache_translation_check_eu_f7858909e0063f37b408eea72f8ef442600cb3c906b76d729b1184d4ed95aa7e -->
```
        <source>Banned Until</source>
        <translation>Honarte debekatua </translation>
    
ERR
The translation is incorrect and has a spelling mistake. "Honarte debekatua" does not convey the meaning of "Banned Until" in Basque, and "Honarte" should be "honaino" if attempting "until", but "honaino debekatua" is still not idiomatic.

Correct translation:
Debekatua honaino
or, more naturally,
Debekatuta (epea: [insert date/time here])
or
Debekatua data hau arte

If the intention is to indicate a date until which the ban lasts, "Debekatua data hau arte" ("Banned until this date") is the clearest.
```

<!-- cache_translation_check_eu_2915e038e5ae9e8e7e8829402cd2d10291f51836dce1604baf24f70c24421c0d -->
```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>Sartu Bitcoin helbide bat (adibidez:%1 )</translation>
    
ERR
There are whitespace formatting issues. There is a missing space after the colon (common in Basque/English punctuation) and a stray space before the closing parenthesis.

Correct translation:
Sartu Bitcoin helbide bat (adibidez: %1)
```

<!-- cache_translation_check_eu_912b50acd00411f90b0f066e630723e3a5cf74436c52ed491955ce373b25a095 -->
```
        <source>Onion</source>
        <comment>network name</comment>
        <extracomment>Name of Tor network in peer info</extracomment>
        <translation>Tipula</translation>
    
ERR
In the context of networking and Bitcoin (specifically Tor), "Onion" refers to the Tor network name and should generally remain "Onion" as it is a proper name/technical term. The translation "Tipula" is the literal Basque word for the vegetable "onion" and is not typically used to refer to the Tor network in a technical context.

Correct translation:
Onion
```

<!-- cache_translation_check_eu_56e958fb4e6620e686fe2760c760296628c624f4b0555a3acf77eb40581c31bf -->
```
        <source>Full Relay</source>
        <extracomment>Peer connection type that relays all network information.</extracomment>
        <translation> Erabateko erreleboa</translation>
    
ERR
The translation contains a stray leading whitespace character (a non-breaking space) which is not present in the source text.

Correct translation:
Erabateko erreleboa
```

<!-- cache_translation_check_eu_3ace3987a5d12c5e09479bbe96867525e0282802022783e672ae6a66313a23ad -->
```
        <source>%1 d</source>
        <translation>%1 e</translation>
    
ERR
The translation is problematic. The English source "%1 d" likely stands for "%1 days", where "d" is an abbreviation for "days". In Basque ('eu'), the abbreviation for "days" is "eg" (from "egun"), not "e". 

Correct translation:
%1 eg
```

<!-- cache_translation_check_eu_558e50f6d7b7caa41caae499a72afc62684fae0a436b2146bbe61355f2947580 -->
```
        <source>%1 and %2</source>
        <translation>%1eta%2</translation>
    
ERR
The translation lacks spaces around the word "eta" (and), which makes the output strings run together with the variables. In Basque, "eta" is a separate word and should be surrounded by spaces to properly separate the elements.

Correct translation:
%1 eta %2
```

<!-- cache_translation_check_eu_8940817eba281907eea373f3e26f0c0937c0661de9afb977ab6401709054f2f3 -->
```
        <source>default wallet</source>
        <translation>Zorro lehenetsia</translation>
    
ERR
In Basque, "wallet" is typically translated as "diru-zorro" (literally "money-bag/purse"). While "zorro" can mean a bag or case, "diru-zorro" is the standard term used in financial and software contexts for a wallet. Additionally, "Zorro" capitalized can be confused with the fictional character.

Correct translation:
diru-zorro lehenetsia
```

<!-- cache_translation_check_eu_75eb7d7f8963f88ee97a607336afad5b4e0b7da88a7b16e7770c4b9811c8d08e -->
```
        <source>&amp;About %1</source>
        <translation>%1-ri buruz</translation>
    
ERR
The translation omits the & shortcut key indicator, which should appear exactly once in the translation (anywhere). Also, the translation would be improved for clarity by making it: "&%1-ri buruz".

Correct translation:
&%1-ri buruz
```

<!-- cache_translation_check_eu_5027c291362c4596be1bd845b10b5c2ae9c8a82d5d92ed27f19deeff1597d2c5 -->
```
        <source>Backup wallet to another location</source>
        <translation>Zorroaren segurtasun kopia beste leku batean.</translation>
    
ERR
The translation includes an unnecessary period at the end that is not present in the source text. Additionally, "beste leku batean" means "in another place", whereas "to another location" is better expressed using the allative case ("batera") or by phrasing the action more naturally for a menu item or tooltip.

Correct translation:
Zorroaren segurtasun-kopia beste leku batean
```

<!-- cache_translation_check_eu_f3a4ef67bd077aa1ba69ba79020bdb94b79ff57d9988f419e48caf99abbc51de -->
```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>Zure zorroari dagozkion gako pribatuak zifratu.</translation>
    
ERR
The translation includes a trailing period that is not present in the source text. In technical strings and UI elements, punctuation should typically match the source to ensure consistency.

Correct translation:
Zure zorroari dagozkion gako pribatuak zifratu
```

<!-- cache_translation_check_eu_3c832c3329216d2f53a25551a51e66e596a4626fe0ad4dfcd353aa17aa6c77bc -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>&amp;Aldatu Pasahitza</translation>
    
ERR
The translation is missing the ellipsis (…) present in the source text, which is a standard UI convention indicating that further input is required.

Correct translation:
&amp;Aldatu Pasahitza…
```

<!-- cache_translation_check_eu_3dbadf8fe17ce85f650030425406ed4aae6c6414d50c67c907c8e8a75fa2ba59 -->
```
        <source>Open &amp;URI…</source>
        <translation>Irek i&amp;URI...</translation>
    
ERR
The translation contains a typo and a stray space. "Ireki" (meaning "Open") has been split into "Irek i". Additionally, the translation uses three periods instead of the ellipsis character used in the source.

Correct translation:
Ireki &amp;URI…
```

<!-- cache_translation_check_eu_7e734733a54607afe23c223c658199cff63b06f809b20bf89ebc872c12a450ae -->
```
        <source>Close All Wallets…</source>
        <translation>Zorro guztiak itxi...</translation>
    
ERR
The translation uses "Zorro," which means "sack" or "bag." In the context of Bitcoin and software, the correct term for "Wallet" is "Diru-zorro." Additionally, the source uses a single-character ellipsis (…), whereas the translation uses three periods (...).

Correct translation:
Diru-zorro guztiak itxi…
```

<!-- cache_translation_check_eu_510ed29661a2ae37e173a72ba038a0e1df381a3f58fa69431e168e7fc4f31b7a -->
```
        <source>Syncing Headers (%1%)…</source>
        <translation>Goiburuak sinkronizatzen (%%1)…</translation>
    
ERR
The format specifier is incorrect. In the source text `%1%`, `%1` is the placeholder for the value and the trailing `%` is a literal percentage sign. The translation `%%1` incorrectly places two percentage signs before the placeholder.

Correct translation:
Goiburuak sinkronizatzen (%1%)…
```

<!-- cache_translation_check_eu_9e59e66b3dfaf304a9fbeb82624f46650e9f0204e4dc781f74dbafa3a81c592b -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>kargatu PSBT arbeletik...</translation>
    
ERR
The translation does not maintain the shortcut key indicator (&), which should appear exactly once, and "kargatu" should be capitalized as it starts the sentence. The ellipsis character should match the source (the translation uses three dots instead of a single unicode ellipsis).

Correct translation:
&Kargatu PSBT arbeletik…
```

<!-- cache_translation_check_eu_e688664f45cfb130fab871ad521cf3c29704e4f8e25562b67cb1adfb212866da -->
```
        <source>&amp;Sending addresses</source>
        <translation>&amp;Helbideak bidaltzen</translation>
    
ERR
The translation "Helbideak bidaltzen" literally means "sending addresses" as a verb phrase ("addresses sending"), not as a noun phrase ("addresses to send to" or "sending addresses"). In Basque, the correct phrasing for "Sending addresses" (as in a list of addresses used for sending) is "Bidaltzeko helbideak".

Correct translation:
&amp;Bidaltzeko helbideak
```

<!-- cache_translation_check_eu_95902831e0aa11f0ccf37bed611e7bbb00cbde0cd20069298eda72edf2ef561a -->
```
        <source>&amp;Receiving addresses</source>
        <translation>&amp;Helbideak jasotzen</translation>
    
ERR
The translation is grammatically incorrect; "Helbideak jasotzen" literally means "receiving addresses" in a non-standard way ("helbideak" = "addresses", "jasotzen" = "receiving (in the process)"), which does not properly correspond to the noun phrase "Receiving addresses". A correct translation would be "Helbide hartzaileak" or "Jasotzeko helbideak".

Correct translation:
&Jasotzeko helbideak
```

<!-- cache_translation_check_eu_fe686d979e823690497f5a5e8807126765b1f4842427746d4cffcc026a1851f2 -->
```
        <source>Migrate a wallet</source>
        <translation>Zorroren bat migratu</translation>
    
ERR
In the context of Bitcoin, "wallet" is translated as "diru-zorro". Using "zorro" alone is ambiguous as it primarily means "sack", "envelope", or "sheath". Additionally, "zorroren bat" translates to "some wallet" or "any wallet", whereas "diru-zorro bat" is the standard way to say "a wallet".

Correct translation:
Diru-zorro bat migratu
```

<!-- cache_translation_check_eu_9d64abf669ded6ad9ccbf5d92b705e8136cf8e6d9114cf117f401b1528a3b122 -->
```
        <source>Copy &amp;amount</source>
        <translation>Kopiatu kopurua</translation>
    
ERR
The shortcut key indicator '&amp;' is missing from the translation. According to the instructions, it must exist exactly once.

Correct translation:
Kopiatu &amp;kopurua
```

<!-- cache_translation_check_eu_fa4dfe4a78e646834074ed53a8e7b94ac23b2b804f6d85f5f38ec27b9ce3c6c4 -->
```
        <source>L&amp;ock unspent</source>
        <translation>Gastatu gabeak blokeatu</translation>
    
ERR
The translation is missing the shortcut key indicator '&' which was present in the source text. In accordance with the instructions, the '&' should exist exactly once in the translation.

Correct translation:
Gastatu gabeak &blokeatu
```

<!-- cache_translation_check_eu_57ff48573ab041f8c41e122095a98319a1a227911846e5b8c27bcf15ce087886 -->
```
        <source>&amp;Unlock unspent</source>
        <translation>Gastatu gabe dagoena desblokeatu</translation>
    
ERR
The translation is missing the shortcut key indicator '&' which was present in the source text.

Correct translation:
&Gastatu gabe dagoena desblokeatu
```

<!-- cache_translation_check_eu_fb664bfafd9a7fb1a0c777584e3efac35761263e553a5cfb2ee05f7cbd9c260f -->
```
        <source>change from %1 (%2)</source>
        <translation>aldaketa hemendik%1 (%2)</translation>
    
ERR
There is a missing space between the word "hemendik" and the format specifier "%1".

Correct translation:
aldaketa hemendik %1 (%2)
```

<!-- cache_translation_check_eu_2dcb7fb18f843456b969b9540460e7d519c9e96757f906c9caa58396a76c2d4e -->
```
        <source>Creating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the create wallet progress window which indicates to the user which wallet is currently being created.</extracomment>
        <translation>Zorroa sortzen&lt;b&gt;%1&lt;/b&gt;...</translation>
    
ERR
There is a missing space before the opening HTML tag `<b>`. In the source text, there is a space between "Wallet" and "<b>", but in the translation, "sortzen" and "<b>" are joined together.

Correct translation:
Zorroa sortzen <b>%1</b>...
```

<!-- cache_translation_check_eu_8e0923d8b9df6b828eebc6f9d60f69edc314440466b35767a2ff280366e38d5d -->
```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>Zihur zaude zorroa  &lt;i&gt;%1&lt;/i&gt;migratu nahi duzula?</translation>
    
ERR
The translation contains spelling and formatting issues. In standard Basque (Batua), "Ziur" is used instead of "Zihur". Additionally, there is a double space before the opening tag and a missing space after the closing tag.

Correct translation:
Ziur zaude <i>%1</i> zorroa migratu nahi duzula?
```

<!-- cache_translation_check_eu_d6af622249d2db607fd73e2ff189e6b7b051e652624703ee7fa0ce551cf342ca -->
```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>Zorroa migratzean, zorro hau deskribatzaile-zorro batean edo gehiagotan bihurtuko da. Zorroaren babeskopia berri bat egin beharko da.
Zorro honek watch-only script-ak baditu, script horiek dituen zorro berri bat sortuko da.
Zorro honek ebazgarriak baina ez zaindutakoak diren script-ak baditu, script horiek dituen beste zorro berri bat sortuko da.

Migrazio-prozesuak zorroaren segurtasun-kopia bat sortuko du migratu aurretik. Segurtasun-kopia hori &lt;wallet name&gt;-&lt;timestamp&gt; .legacy.bak izendatuko da eta zorro honen direktorioan aurkituko da. Migrazioa okerra bada, segurtasun-kopia hori berreskuratu daiteke "Zorroa Berreskuratu" funtzionalitatearen bidez.</translation>
    
ERR
There is a stray space in the filename format in the translation. Specifically, there is a space before `.legacy.bak` which is not present in the source text.

Correct translation:
Zorroa migratzean, zorro hau deskribatzaile-zorro batean edo gehiagotan bihurtuko da. Zorroaren babeskopia berri bat egin beharko da.
Zorro honek watch-only script-ak baditu, script horiek dituen zorro berri bat sortuko da.
Zorro honek ebazgarriak baina ez zaindutakoak diren script-ak baditu, script horiek dituen beste zorro berri bat sortuko da.

Migrazio-prozesuak zorroaren segurtasun-kopia bat sortuko du migratu aurretik. Segurtasun-kopia hori <wallet name>-<timestamp>.legacy.bak izendatuko da eta zorro honen direktorioan aurkituko da. Migrazioa okerra bada, segurtasun-kopia hori berreskuratu daiteke "Zorroa Berreskuratu" funtzionalitatearen bidez.
```

<!-- cache_translation_check_eu_049d528b19625469717818430827ce24c405d12621c5ed7a24f19efa2631893a -->
```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>Zorroa migratzen &lt;b&gt;%1&lt;/b&gt; …</translation>
    
ERR
The translation contains a formatting error regarding whitespace. There is an unnecessary space before the ellipsis (…), which is not present in the source text. Additionally, in Basque, "Diru-zorro" is the more common term for a digital/Bitcoin wallet than "Zorro".

Correct translation:
<b>%1</b> diru-zorroa migratzen…
```

<!-- cache_translation_check_eu_12302e22c7da0e2b904debfdebad124b24dee26c217210aa71b49b385cccce70 -->
```
        <source>Restoring the wallet will copy the backup file to the wallets directory and place it in the standard wallet directory layout. The original file will not be modified.

Migrating the wallet will convert the restored wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>Zorroa berreskuratzeak segurtasun-kopiako fitxategia zorroen direktoriora kopiatuko du eta ohiko zorro-diren egituran kokatuko du. Jatorrizko fitxategia ez da aldatuko.

Zorroa migratzeak berreskuratuta dagoen zorroa deskriptore-zorro batean edo gehiagotan bihurtuko du. Zorroaren segurtasun-kopia berria sortu beharko da.
Zorro honek behaketa-soilik diren skripteren bat badu, skriptu horiek jasoko dituen zorro berri bat sortuko da.
Zorro honek konpon daitezkeen baina behatzen ez diren skripteren bat badu, skriptu horiek jasoko dituen beste zorro berri eta desberdin bat sortuko da.

Migrazio-prozesuak zorroaren segurtasun-kopia bat sortuko du migratu aurretik. Segurtasun-kopia hori &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak izendatuko da, eta zorro horren direktorioan aurkituko da. Migrazio okerren bat gertatuz gero, segurtasun kopia “Zorroa Berreskuratu” funtzionalitatearekin lehenera daiteke.</translation>
    
ERR
In the first paragraph, "zorro-diren" is a typo or a linguistic error. It should likely be "zorro-direktorioaren" (wallet directory's) or "zorro-direktorioen" (wallet directories') to match the English "wallet directory layout". "Diren" is a verb form in Basque meaning "which are", which does not fit in this context.

Correct translation:
Zorroa berreskuratzeak segurtasun-kopiako fitxategia zorroen direktoriora kopiatuko du eta ohiko zorro-direktorioen egituran kokatuko du. Jatorrizko fitxategia ez da aldatuko.

Zorroa migratzeak berreskuratuta dagoen zorroa deskriptore-zorro batean edo gehiagotan bihurtuko du. Zorroaren segurtasun-kopia berria sortu beharko da.
Zorro honek behaketa-soilik diren skripteren bat badu, skriptu horiek jasoko dituen zorro berri bat sortuko da.
Zorro honek konpon daitezkeen baina behatzen ez diren skripteren bat badu, skriptu horiek jasoko dituen beste zorro berri eta desberdin bat sortuko da.

Migrazio-prozesuak zorroaren segurtasun-kopia bat sortuko du migratu aurretik. Segurtasun-kopia hori <wallet name>-<timestamp>.legacy.bak izendatuko da, eta zorro horren direktorioan aurkituko da. Migrazio okerren bat gertatuz gero, segurtasun kopia “Zorroa Berreskuratu” funtzionalitatearekin lehenera daiteke.
```

<!-- cache_translation_check_eu_41ceba1b69a3a8f5a42caf92f559f3f15ec740eb9e737bac39775e3303b537ba -->
```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Diruzorroa berritzen  &lt;b&gt;%1&lt;/b&gt;…</translation>
    
ERR
The translation contains a double space before the opening HTML tag and uses a term that translates more closely to "renewing" than "restoring" in a technical context.

Correct translation:
Diruzorroa berreskuratzen <b>%1</b>…
```

<!-- cache_translation_check_eu_f589aaba3a021f5a2a7e482e4edac1129b3dac9913656ceaa346d025d6f77241 -->
```
        <source>Migration failed</source>
        <translation>Migrazioa huts egin da</translation>
    
ERR
The Basque grammar is incorrect. The verb phrase 'huts egin' (to fail) is typically used with the auxiliary verb 'du' (nor-nork) and the subject should be in the ergative case ('Migrazioak').

Correct translation:
Migrazioak huts egin du
```

<!-- cache_translation_check_eu_4cfe249a9fa8346f91fb1780d9d25c6ad824dc4eebc67b5e5c885d13473b0e79 -->
```
        <source>Open wallet warning</source>
        <translation>Zorroa irekitzen abisua</translation>
    
ERR
The Basque translation "Zorroa irekitzen abisua" is grammatically incorrect. "Irekitzen" is a gerund/aspectual form (opening), but in this context, an action-related noun or a relational form is required to describe the warning. Additionally, "diru-zorro" is the more standard term for a financial wallet in Basque.

Correct translation:
Diru-zorroa irekitzean abisua
```

<!-- cache_translation_check_eu_6c7a98e98db200dcd5eb730fbe27bae7f542de3027c4c024b8271e9640cd6a00 -->
```
        <source>Open Wallet</source>
        <extracomment>Title of window indicating the progress of opening of a wallet.</extracomment>
        <translation>Zorroa zabaldu</translation>
    
ERR
The translation uses "Zorroa" for "Wallet". In the context of Bitcoin and software in Basque, the standard term for a wallet is "Diru-zorroa" or simply "Zorroa" in some contexts, but "Zorroa" alone usually means "sack" or "envelope". However, more importantly, "Open" in the context of a window title or action is typically "Ireki". "Zabaldu" means to spread or to open (like a book/folder), but "Ireki" is the standard computing term for "Open".

Correct translation:
Diru-zorroa ireki
```

<!-- cache_translation_check_eu_37ab0cb34167e519361f097595a3185aede115a00639bf2d07b31ca850cfc1a7 -->
```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Zorroa berritzen  &lt;b&gt;%1&lt;/b&gt;…</translation>
    
ERR
The translation has a double space between 'berritzen' and '<b>%1</b>'. Furthermore, 'berritzen' means 'renewing' or 'updating' rather than 'restoring'. In the context of Bitcoin wallets, 'berreskuratzen' is the standard term for 'restoring'.

Correct translation:
<b>%1</b> diru-zorroa berreskuratzen…
```

<!-- cache_translation_check_eu_03b9b764bd83473530aa4a33abc07eea4b2037ca18c55c91fbb8eadd37ffcc15 -->
```
        <source>Restore wallet failed</source>
        <extracomment>Title of message box which is displayed when the wallet could not be restored.</extracomment>
        <translation>Zorroa berreskuratzea huts egin da</translation>
    
ERR
The Basque translation uses the word 'zorroa' for 'wallet', but in the context of Bitcoin and software, 'zorro' (meaning sack/envelope/sheath) is rarely used. The standard term used in Basque software localization for a Bitcoin wallet is 'diru-zorroa'. Additionally, the auxiliary verb usage 'huts egin da' is grammatically incorrect in this context; it should be 'huts egin du'.

Correct translation:
Diru-zorroa berreskuratzeak huts egin du
```

<!-- cache_translation_check_eu_a41256a56b098dd81bd0ce5058dafd3816ea55c11786889a0435de799ba4f2fb -->
```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>Zorroa denbora luzez itxi gabe uzteak bloke-katea guztia berriro sinkronizatu beharra ekar dezake, moztea gaituta badago.</translation>
    
ERR
The Basque translation says "Zorroa denbora luzez itxi gabe uzteak" which means "Leaving the wallet open (without closing it) for too long". The source English text says "Closing the wallet for too long". The translation expresses the opposite action.

Correct translation:
Zorroa denbora luzez itxita edukitzeak bloke-kate osoa berriro sinkronizatu beharra ekar dezake, mozketa (pruning) gaituta badago.
```

<!-- cache_translation_check_eu_50d96bf73b907d7f4886ae6922d8fc2a0bbf4b8c7329994bfdca5f2644f1adae -->
```
        <source>You are one step away from creating your new wallet!</source>
        <translation>Zure zorro berri sortzeko pauso bakarra gelditzen da!</translation>
    
ERR
The Basque translation is missing the definite article '-a' at the end of the noun phrase 'zure zorro berri'. In Basque, when using a possessive like 'zure' (your), the noun phrase typically requires the article.

Correct translation:
Zure zorro berria sortzeko pauso bakarra gelditzen da!
```

<!-- cache_translation_check_eu_4d642339ccc4406b29d990b291ff90a4153a55b52034736fd4bb43c4508f8657 -->
```
        <source>Please provide a name and, if desired, enable any advanced options</source>
        <translation>Mesedez, eman izen bat eta nahi izanez gero, gaitz ezazu aukerarik aurreratua.</translation>
    
ERR
The translation contains a grammatical error and a mismatch in number (singular vs plural). "aukerarik aurreratua" incorrectly combines a partitive noun ("aukerarik") with a definite singular adjective ("aurreratua"). Since the source specifies "advanced options" (plural), the translation should reflect this.

Correct translation:
Mesedez, eman izen bat eta, nahi izanez gero, gaitu aukera aurreratuak.
```

<!-- cache_translation_check_eu_9f1f14650e1f306eccb8c2cfc84c462aa25287132ff3078738f85af37f11c0c5 -->
```
        <source>Make a blank wallet. Blank wallets do not initially have private keys or scripts. Private keys and addresses can be imported using descriptors at a later time.</source>
        <translation>Zorro huts bat sortu. Zorro hutsek ez dute hasieran giltza pribaturik edo skriprik izaten. Giltza pribatuak eta helbideak geroago inporta daitezke deskriptoreen bidez.</translation>
    
ERR
The translation contains a typo in the word "skriprik". The word "script" in a technical context should be adapted as "skript" in Basque, making the partitive form "skriptik".

Correct translation:
Zorro huts bat sortu. Zorro hutsek ez dute hasieran giltza pribaturik edo skriptik izaten. Giltza pribatuak eta helbideak geroago inporta daitezke deskriptoreen bidez.
```

<!-- cache_translation_check_eu_fd8d28ad9bb2e64f4428050318ac31dc996e4fd13b526742070e341987378013 -->
```
        <source>Make Blank Wallet</source>
        <translation>Egin zorro hutsa...</translation>
    
ERR
The translation includes an ellipsis (...) at the end, which is not present in the source text. In software localization, punctuation should generally match the source unless the target language grammar requires otherwise.

Correct translation:
Egin zorro hutsa
```

<!-- cache_translation_check_eu_0cf247384afe3521361eee260b202b2e2e7539a302714e8664b82629e5074bb8 -->
```
        <source>The label associated with this address list entry</source>
        <translation>Helbide zerrenda honi dagozkion etiketak</translation>
    
ERR
The translation has a plurality mismatch and misses a word. The source text refers to a singular "label", while the translation uses the plural "etiketak" (labels). Additionally, the word "entry" (sarrera) is missing from the translation.

Correct translation:
Helbide-zerrendako sarrera honi dagokion etiketa
```

<!-- cache_translation_check_eu_a5a930b7fc4aca10d9082483a83db7a5a8688541d2408e974570906d728d0899 -->
```
        <source>Directory already exists. Add %1 if you intend to create a new directory here.</source>
        <translation>Direktorioa dagoeneko existitzen da. Sortu %1hemen direktorio berri bat nahi baduzu.</translation>
    
ERR
There is a missing space between the format specifier '%1' and the next word 'hemen'. Additionally, the verb "Add" is translated as "Sortu" (Create), whereas "Gehitu" or "Erantsi" would be more accurate.

Correct translation:
Direktorioa dagoeneko existitzen da. Gehitu %1 hemen direktorio berri bat sortu nahi baduzu.
```

<!-- cache_translation_check_eu_06b96d9bbb9be8768f67bc26988824d43a3693f163822829e4d27ba27812e392 -->
```
        <source>%1 is shutting down…</source>
        <translation>%1Itzaltzen ari da...</translation>
    
ERR
There is a missing space between the format specifier and the translation text ("%1Itzaltzen" instead of "%1 Itzaltzen"). Additionally, the ellipsis should match the source ("…" vs "..."). The correct form in Basque would also make the translation more natural.

Correct translation:
%1 itzaltzen ari da…
```

<!-- cache_translation_check_eu_1392036a0456e630992a30cb0fd63538e32a92d4613275e4e527b69b34e8d6e7 -->
```
        <source>This initial synchronisation is very demanding, and may expose hardware problems with your computer that had previously gone unnoticed. Each time you run %1, it will continue downloading where it left off.</source>
        <translation>Hasiera sinkronizazio hori oso eskatzailea da, eta ordenagailuan aurretik nabaritu gabeko arazo hardwareak agerian ditzake. Aldi bakoitzean exekutatzen duzunean %1, bertan utzi zuen lekutik deskargatzen jarraituko du.</translation>
    
ERR
The translation contains some grammatical and terminology issues in Basque:
1. "Hasiera sinkronizazio" should be "Hasierako sinkronizazioa" to properly mean "Initial synchronisation".
2. "arazo hardwareak" is an incorrect construction; it should be "hardware-arazoak".
3. "agerian ditzake" is missing a main verb. It should be "agerian utz ditzake" (may leave exposed) or "azaleratu ditzake" (may bring to light/expose).
4. The phrasing "Aldi bakoitzean exekutatzen duzunean %1" is slightly unnatural. "%1 exekutatzen duzun bakoitzean" is more standard.

Correct translation:
Hasierako sinkronizazio hau oso zorrotza da, eta zure ordenagailuan lehenago nabaritu gabeko hardware-arazoak azaleratu ditzake. %1 exekutatzen duzun bakoitzean, utzitako puntuan jarraituko du deskargatzen.
```

<!-- cache_translation_check_eu_4c41b4c0547329a3187fd5550d2f275ee5d6451d2044ac3d5b23a8fc3168e2ed -->
```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>Ados sakatzen duzunean, %1-ek %4blockchain osoa ( %2GB) deskargatzen eta prozesatzen hasiko da, lehen aldiz abiarazi zenean %3-ko lehen %4 transakzioetatik hasita.</translation>
    
ERR
The translation contains grammar and formatting errors:
1. Grammar: The subject "%1-ek" uses the ergative case suffix "-ek", but the verb "hasiko da" is intransitive. The subject should be in the absolutive case: "%1".
2. Spacing: There is a stray space inside the parentheses "( %2 GB)" and a missing space between the variable and the word "%4blockchain".
3. Accuracy: The phrase "lehen %4 transakzioetatik" (from the first %4 transactions) does not correctly reflect the source "when %4 initially launched".

Correct translation:
Ados sakatzen duzunean, %1 %4 blockchain osoa (%2 GB) deskargatzen eta prozesatzen hasiko da, %4 lehen aldiz abiarazi zenean, %3(e)ko lehen transakzioetatik hasita.
```

<!-- cache_translation_check_eu_13fb69e4f70a951e76c9ea6e05af5308df60d1a7cbbd46de228d1cd5cce5ec18 -->
```
        <source>%1 will download and store a copy of the Bitcoin block chain.</source>
        <translation>%1Bitcoin bloke-katearen kopia bat deskargatu eta gordeko du.</translation>
    
ERR
There is a missing space between the format specifier '%1' and the word 'Bitcoin'. Additionally, in Basque, the subject of a transitive verb (like 'download' and 'store') usually takes the ergative case suffix '-k'.

Correct translation:
%1(e)k Bitcoin bloke-katearen kopia bat deskargatu eta gordeko du.
```

<!-- cache_translation_check_eu_9a02b1ac50023271d7cddbabf21c3dc2f2a97ae79e2fff124c350797f482bfad -->
```
        <source>Recent transactions may not yet be visible, and therefore your wallet's balance might be incorrect. This information will be correct once your wallet has finished synchronizing with the bitcoin network, as detailed below.</source>
        <translation>Azken transakzioak baliteke oraindik ikusgai ez egotea, eta, hortaz, zure zorroaren saldoa ez da zuzena izan daiteke. Informazio hau eguneratua egongo da zure zorroa Bitcoin sarearekin sinkronizatzea amaitzen duenean, behean zehazten den bezala.</translation>
    
ERR
The Basque translation contains a grammatical error in the first sentence. The phrase "ez da zuzena izan daiteke" is redundant and grammatically incorrect (literally "is not might be correct"). It should use either "baliteke zuzena ez izatea" or "okerra izan daiteke".

Correct translation:
Azken transakzioak baliteke oraindik ikusgai ez egotea, eta, hortaz, zure zorroaren saldoa okerra izan daiteke. Informazio hau zuzena izango da zure zorroa Bitcoin sarearekin sinkronizatzen amaitu ondoren, behean zehazten den bezala.
```

<!-- cache_translation_check_eu_067c84ed9cd57bfd593ffea3e9c42365e660de6d7bcbbc0420789c6a6b8c4a3b -->
```
        <source>Estimated time left until synced</source>
        <translation>Sinkronizazioa amaitzeko estimatutako denbora geratzen dena.</translation>
    
ERR
The translation includes a trailing period which is not present in the source text. Additionally, the phrase "geratzen dena" at the end is slightly redundant in this context.

Correct translation:
Sinkronizazioa amaitzeko falta den denbora estimatua
```

<!-- cache_translation_check_eu_92da4bb03dd54e3fb5a214774c64741b29b27b2cc65ccb27d3ba97f647f8dd86 -->
```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>%1orain sinkronizatzen ari da. Kideen buruak eta blokeak deskargatuko ditu, eta balioztatuko ditu bloke-katearen punturik gorenera iritsi arte.</translation>
    
ERR
There is a missing space after the format specifier %1. Without a space, the application name and the word "orain" will be joined together (e.g., "Bitcoin Coreorain").

Correct translation:
%1 orain sinkronizatzen ari da. Kideen buruak eta blokeak deskargatuko ditu, eta balioztatuko ditu bloke-katearen punturik gorenera iritsi arte.
```

<!-- cache_translation_check_eu_dfac5e1ddb69929a369e419337b730978ffbfbe051fe585503f271c266f0f7e9 -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>Scripten egiaztapen harien kopurua</translation>
    
ERR
The translation is missing the shortcut key indicator '&' which was present in the source text. In this context, it should be placed before a character to enable a keyboard shortcut.

Correct translation:
Scripten &egiaztapen harien kopurua
```

<!-- cache_translation_check_eu_5db626948e2e3baff4d027ec1fc0f140f173e488e4aa902e9e0ef008745e210a -->
```
        <source>Map port using PCP or NA&amp;T-PMP</source>
        <translation>Portua mapatu PCP edo NAT-PMP erabiliz</translation>
    
ERR
The shortcut key indicator '&amp;' is missing from the translation. It must appear exactly once, as it does in the source text.

Correct translation:
Portua mapatu PCP edo NA&amp;T-PMP erabiliz
```

<!-- cache_translation_check_eu_c2049d9f5e126800a680ed733254c646a0aefd39fd02b47d7d46d84d4eba14ed -->
```
        <source>IP address of the proxy (e.g. IPv4: 127.0.0.1 / IPv6: ::1)</source>
        <translation>Proxyaren IP helbidea  (IPv4: 127.0.0.1 / IPv6: ::1 adibidez )</translation>
    
ERR
There are minor whitespace issues and the position of "adibidez" (e.g.) is inconsistent with the English source. In Basque, "adibidez" should directly follow the examples, not be at the end in parenthesis. Also, there is an unnecessary double space after "helbidea".

Correct translation:
Proxyaren IP helbidea (adibidez, IPv4: 127.0.0.1 / IPv6: ::1)
```

<!-- cache_translation_check_eu_401a9fe207ae054ba0aa13a5512dbdd570135b7195d524ec6225dd4cad725883 -->
```
        <source>W&amp;allet</source>
        <translation>Zorroa</translation>
    
ERR
The translation is missing the shortcut key indicator (&amp;), which is required to be present exactly once according to the instructions.

Correct translation:
&amp;Zorroa
```

<!-- cache_translation_check_eu_03b193ebde716aab2c9fa2de58f816b164ae27242aa10e2e6a38eef30ebe9436 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>&amp;Gastu berretsi gabeko itzulketa</translation>
    
ERR
The word 'Gastu' is a noun meaning 'expense' or 'expenditure'. In this context, 'Spend' is a verb, which in Basque should be 'Gastatu'. Additionally, in Basque, the verb typically follows the object.

Correct translation:
&Gastatu berretsi gabeko itzulketa
```

<!-- cache_translation_check_eu_c27348223c4be18d1918dfe1f606872a1f060492372934a033d4c68ddcb77d17 -->
```
        <source>&amp;External signer script path</source>
        <translation>Kanpo sinatzailearen script bidea</translation>
    
ERR
The shortcut key indicator '&amp;' is missing in the translation. According to the instructions, it must exist exactly once.

Correct translation:
&amp;Kanpo sinatzailearen script bidea
```

<!-- cache_translation_check_eu_2e1855c5842ad0f4dcff050e39a8dd2710173a6eb8014e13366753b9af4126fd -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Sarbide konexioak baimendu</translation>
    
ERR
The ampersand (&) indicating the shortcut key in the source text ("Allow incomin&g connections") is missing in the translation. There should be exactly one & in the translation at some location.

Correct translation:
Sar&bide konexioak baimendu
or
Sarbide kone&xioak baimendu

Either placement of the & is valid as long as it appears exactly once.
```

<!-- cache_translation_check_eu_ac035add39ad1b58ac954b090f05f0145447b6dc592570c91cd55df325e9b8cc -->
```
        <source>&amp;Connect through SOCKS5 proxy (default proxy):</source>
        <translation>Konektatu SOCKS5 proxy bidez (proxy lehenetsia):</translation>
    
ERR
The translation is missing the shortcut key indicator '&', which is present in the source text.

Correct translation:
&Konektatu SOCKS5 proxy bidez (proxy lehenetsia):
```

<!-- cache_translation_check_eu_ef0ae2a43b1c74ee473d3c07c34aab3c7ee1f8b4a34d8133954280c84905e854 -->
```
        <source>The user interface language can be set here. This setting will take effect after restarting %1.</source>
        <translation>Erabiltzaile interfazearen hizkuntza hemen ezar daiteke. Ezarpen hau  %1 berrabiarazi ondoren izango da eraginkorra.</translation>
    
ERR
There is a double space between "hau" and "%1" which violates the formatting instructions.

Correct translation:
Erabiltzaile interfazearen hizkuntza hemen ezar daiteke. Ezarpen hau %1 berrabiarazi ondoren izango da eraginkorra.
```

<!-- cache_translation_check_eu_869a3cd72cab7161776b84acae19fde7f0710080c7dcc5001af4a36954bfee4e -->
```
        <source>Could not read setting "%1", %2.</source>
        <translation>Ezin izan da "%1" ezarpena irakurri%2.</translation>
    
ERR
The translation contains a spacing error. There should be a space between the first part of the sentence and the second format specifier "%2" to match the source text's structure and ensure readability.

Correct translation:
Ezin izan da "%1" ezarpena irakurri, %2.
```

<!-- cache_translation_check_eu_e6c2cc4e8d517e63c891372f9bc4ff0ee9a6b227a31a48c4bacd06a1d5954be1 -->
```
        <source>Failed to sign transaction: %1</source>
        <translation>Transakzioa sinatzeak huts egin du:%1</translation>
    
ERR
There is a missing space after the colon in the translation. In both English and Basque, a colon should be followed by a space when followed by another element.

Correct translation:
Transakzioa sinatzeak huts egin du: %1
```

<!-- cache_translation_check_eu_e46c3d07c6329604015802500f8293771beb9da5c931f9417fcab5e0967ba654 -->
```
        <source>Sends %1 to %2</source>
        <translation>%1Bidaltzen dio%2</translation>
    
ERR
The translation lacks necessary spaces between the format specifiers (%1 and %2) and the text. This would result in the values being concatenated directly to the words (e.g., "1BTCBidaltzen dioAddress"). Additionally, the word order in Basque usually places the verb after the objects.

Correct translation:
%1 %2(r)i bidaltzen dio
```

<!-- cache_translation_check_eu_fdd5eccbaffee93627bd95fd1413011bd3fcf3615a985659144c16aa5b78bdb4 -->
```
        <source>Pays transaction fee: </source>
        <translation>Transakzioaren kuota ordaintzen du:</translation>
    
ERR
The translation is missing the trailing space present in the source text.

Correct translation:
Transakzioaren kuota ordaintzen du:
```

<!-- cache_translation_check_eu_9675760da4964b9b0db61b3f3d332ac113f3a7eea9c64f05d203b382891dbce3 -->
```
        <source>Block chain</source>
        <translation>Bloke-katea.</translation>
    
ERR
The translation includes a trailing period that is not present in the source text.

Correct translation:
Bloke-katea
```

<!-- cache_translation_check_eu_abf4705e3f5d4843eb55be741183b3b7a4bb173a30c721ea6852260ca7bbaf46 -->
```
        <source>Wallet: </source>
        <translation>Zorroa:</translation>
    
ERR
The translation is missing the trailing space present in the source text. Additionally, "Diru-zorroa" is the more accurate and standard term for a financial/Bitcoin wallet in Basque, whereas "Zorroa" can mean a general pouch, case, or bag.

Correct translation:
Diru-zorroa:  (with a trailing space)
```

<!-- cache_translation_check_eu_4b4d7ad0bf2966e6dc5cf57de325d95c7c76e1eef44f8b537c9eb2c494c05aae -->
```
        <source>The transport layer version: %1</source>
        <translation>Garraio geruzako bertsioa:%1</translation>
    
ERR
The translation contains a spacing issue. There should be a space before the format specifier '%1' to match the source text's structure and ensure readability.

Correct translation:
Garraio geruzako bertsioa: %1
```

<!-- cache_translation_check_eu_c70304ce3f45fc4bf94324becde5ea2659984f808db15ba3448c347bc34c46ed -->
```
        <source>The duration of a currently outstanding ping.</source>
        <translation>Uneko ping batzuen iraupena.</translation>
    
ERR
The translation uses the plural form "ping batzuen" (of some pings), whereas the source text uses the singular "a ... ping". Additionally, "outstanding" is better translated as "zain dagoen" (pending/waiting) rather than just "uneko" (current).

Correct translation:
Uneko ping baten iraupena.
```

<!-- cache_translation_check_eu_969e7110f87bee7683b65c4512ab76e9c770f47f3c4190b1988c83f7bd6163f9 -->
```
        <source>Outbound Manual: added using RPC %1 or %2/%3 configuration options</source>
        <extracomment>Explanatory text for an outbound peer connection that was established manually through one of several methods. The numbered arguments are stand-ins for the methods available to establish manual connections.</extracomment>
        <translation>Irteerako Eskuzkoa: RPC %1bidez gehitua edo%2 / %3konfigurazio aukerak</translation>
    
ERR
The translation contains whitespace formatting issues: there is a missing space before "bidez" (following %1), a missing space before "%2", and a missing space before "konfigurazio". Additionally, "edo" (or) requires a space after it.

Correct translation:
Irteerako Eskuzkoa: RPC %1 bidez gehitua edo %2 / %3 konfigurazio aukerak
```

<!-- cache_translation_check_eu_52c14f1b6929bca81642f4d9f5ea0b6065cdfc29761f0a1053dd20f72a944d54 -->
```
        <source>&amp;Copy IP/Netmask</source>
        <extracomment>Context menu action to copy the IP/Netmask of a banned peer. IP/Netmask is the combination of a peer's IP address and its Netmask. For IP address, see: https://en.wikipedia.org/wiki/IP_address.</extracomment>
        <translation>Kopiatu IP/Sare-maskara</translation>
    
ERR
The shortcut key marker '&amp;' is missing from the translation. It must appear exactly once.

Correct translation:
&amp;Kopiatu IP/Sare-maskara
```

<!-- cache_translation_check_eu_c8d119cbefbe2404293cc8949894be3539f7d58e3bae14036a8ec2037c71f027 -->
```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>Ongi etorri %1RPC kontsolara.
Erabili gezi-gora eta gezi-behera historia nabigatzeko, eta %2pantaila garbitzeko.
Erabili %3eta%4 letra-tamaina handitzeko edo txikitzeko.
Idatzi %5eskuragarri dauden %6komandoen ikuspegi orokorra ikusteko.
Kontsola hau erabiltzeko informazio gehiago nahi izanez gero, idatzi .

%7ABISUA: Iruzurgileak jardunean ibili dira, erabiltzaileei hemen komandoak idazteko esanez eta haien diru-zorroko edukia lapurtuz. Ez erabili kontsola hau %8komando baten ondorioak guztiz ulertu gabe.</translation>
    
ERR
The translation has several issues regarding placeholders and formatting:
1. Missing placeholder: %6 is completely missing from the translation.
2. Placeholder spacing: There are missing spaces between placeholders and the surrounding text (e.g., "%1RPC" should be "%1 RPC", "%2pantaila" should be "%2 pantaila", "%3eta%4" should be "%3 eta %4", "%5eskuragarri" should be "%5 eskuragarri").
3. Misplaced style tag: %8 is a closing style tag for the warning. In the source, it is at the very end. In the translation, it is placed in the middle of the sentence.

Correct translation:
Ongi etorri %1 RPC kontsolara.
Erabili gora eta behera geziak historian zehar nabigatzeko, eta %2 pantaila garbitzeko.
Erabili %3 eta %4 letra-tamaina handitzeko edo txikitzeko.
Idatzi %5 eskuragarri dauden komandoen ikuspegi orokorra ikusteko.
Kontsola hau erabiltzeko informazio gehiago nahi izanez gero, idatzi %6.

%7ABISUA: Iruzurgileak jardunean ibili dira, erabiltzaileei hemen komandoak idazteko esanez eta haien diru-zorroko edukia lapurtuz. Ez erabili kontsola hau komando baten ondorioak guztiz ulertu gabe.%8
```

<!-- cache_translation_check_eu_69672cd9fbda6dc49c0e6ddd2fda10c2570d359c7063769c1f106be052ee2902 -->
```
        <source>via %1</source>
        <translation>%1bidez</translation>
    
ERR
The translation lacks a space between the format specifier '%1' and the word 'bidez'. Without a space, the variable and the word will be concatenated (e.g., "Torbidez" instead of "Tor bidez").

Correct translation:
%1 bidez
```

<!-- cache_translation_check_eu_9d64abf669ded6ad9ccbf5d92b705e8136cf8e6d9114cf117f401b1528a3b122 -->
```
        <source>Copy &amp;amount</source>
        <translation>Kopiatu kopurua</translation>
    
ERR
The shortcut key indicator '&amp;' is missing from the translation. According to the instructions, it must exist exactly once.

Correct translation:
Kopiatu &amp;kopurua
```

<!-- cache_translation_check_eu_fe19e8858fcce079f33be7378041eb92b3c4043325182c6bc3ba4e41e747d3bb -->
```
        <source>Payment information</source>
        <translation>Ordainketa informazioa.</translation>
    
ERR
The translation includes a trailing period that is not present in the source text. In UI strings, punctuation should match the source to ensure consistency.

Correct translation:
Ordainketa informazioa
```

<!-- cache_translation_check_eu_7378a6fc581103b07830bfda56c65b085777c1b2278e19e0a9e047ed33ac9f1f -->
```
        <source>If this is activated, but the change address is empty or invalid, change will be sent to a newly generated address.</source>
        <translation>Hau aktibatuta badago, baina aldaketa-helbidea hutsik edo baliogabea bada, aldaketa helbide berri sortu batera bidaliko da.</translation>
    
ERR
The Basque translation contains a grammatical error in the phrase "berri sortu". In Basque, to express "newly created" or "newly generated," the correct word order is "sortu berri".

Correct translation:
Hau aktibatuta badago, baina aldaketa-helbidea hutsik edo baliogabea bada, aldaketa sortu berri den helbide batera bidaliko da.
```

<!-- cache_translation_check_eu_e5eb3542c0d6d48151116dc5ebfbb19867b24325360769a6da06d72b16017303 -->
```
        <source>S&amp;end</source>
        <translation>Bidali</translation>
    
ERR
The translation omits the '&' character, which is used to indicate the shortcut key in the UI. The translation should include the '&' exactly once, placed appropriately for a shortcut in Basque.

Correct translation:
&Bidali
or
Bi&dali

(Usual Basque practice is to put the ampersand before the B or D, but either is acceptable as long as there is exactly one '&'.)
```

<!-- cache_translation_check_eu_d5b8f2de30d47ad069e413c4d5187cdfa26c49f748c3caf89026aa93ffd213af -->
```
        <source>%1 (%2 blocks)</source>
        <translation>%1(%2 bloke)</translation>
    
ERR
The translation is missing a space before the opening parenthesis, which deviates from the source formatting.

Correct translation:
%1 (%2 bloke)
```

<!-- cache_translation_check_eu_a15494bc1b1e08b0e228ece95009d235b03958f3accc2fac7ca4922ca9d374f6 -->
```
        <source>Cr&amp;eate Unsigned</source>
        <translation>Sortu sinatu gabea</translation>
    
ERR
The translation is missing the shortcut key indicator (&amp;), which is present in the source text. According to the instructions, it must exist exactly once in the translation.

Correct translation:
&amp;Sortu sinatu gabea
```

<!-- cache_translation_check_eu_7eceb8c34535a0d068b179ddfba53f330e6d1c3fa10ad631efb94ed8c56c0305 -->
```
        <source>%1 to '%2'</source>
        <translation>%1'%2'-ra</translation>
    
ERR
The translation is missing a space between the first placeholder (%1) and the second one ('%2'). In Basque, while the suffix "-ra" (meaning "to") is correctly appended to the destination, the space from the source text should be preserved to separate the amount/label from the destination.

Correct translation:
%1 '%2'-ra
```

<!-- cache_translation_check_eu_59df445942d7011735ef0bd0210aa670ec35b9a91747955398a79d204389bc49 -->
```
        <source>%1 from wallet '%2'</source>
        <translation>%1'%2' zorrotik</translation>
    
ERR
The translation contains a spacing issue. There should be a space between the first format specifier '%1' and the rest of the text to avoid them running together, as in the source text.

Correct translation:
%1 '%2' zorrotik
```

<!-- cache_translation_check_eu_d32db558ba84be8d0cb0e420ca48caafc8db4ca2bb154aec344874bf0e7f897b -->
```
        <source>Please, review your transaction. You can create and send this transaction or create a Partially Signed Bitcoin Transaction (PSBT), which you can save or copy and then sign with, e.g., an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can send their transaction or create a PSBT. This string is displayed when both private keys and PSBT controls are enabled.</extracomment>
        <translation>Euskara Jasoa dijo:
Mesedez, berrikusi zure transakzioa. Transakzio hau sor eta bidali dezakezu, edo bestela, Partzialki Sinatutako Bitcoin Transakzio (PSBT) bat sor dezakezu; hori gorde edo kopiatu, eta ondoren, adibidez, lineaz kanpoko %1 zorro batekin edo PSBT bateragarria den hardware-zorro batekin sinatu.</translation>
    
ERR
The translation includes an unnecessary prefix "Euskara Jasoa dijo:" which is not part of the source text and appears to be a note or a language label (mixing Basque and Spanish).

Correct translation:
Mesedez, berrikusi zure transakzioa. Transakzio hau sor eta bidali dezakezu, edo bestela, Partzialki Sinatutako Bitcoin Transakzio (PSBT) bat sor dezakezu; hori gorde edo kopiatu, eta ondoren, adibidez, lineaz kanpoko %1 zorro batekin edo PSBT bateragarria den hardware-zorro batekin sinatu.
```

<!-- cache_translation_check_eu_489f35170287ea3144bed833a2b182c9661ec5cb3e50758bfaff952718937134 -->
```
        <source>%1 kvB</source>
        <comment>PSBT transaction creation</comment>
        <extracomment>When reviewing a newly created PSBT (via Send flow), the transaction fee is shown, with "virtual size" of the transaction displayed for context</extracomment>
        <translation>%1kvB</translation>
    
ERR
There is a whitespace formatting issue. The space between the format specifier '%1' and the unit 'kvB' from the source text is missing in the translation.

Correct translation:
%1 kvB
```

<!-- cache_translation_check_eu_c9236f5c9eee632bf478600e44bada750f4d187ba4a646d6ef7557883f118a44 -->
```
        <source>The amount exceeds your balance.</source>
        <translation>Zenbatekoa zure saldoa gainditzen du.</translation>
    
ERR
The Basque grammar is incorrect. In this sentence, "Zenbatekoa" (the amount) is the subject of the transitive verb "gainditu" (to exceed), so it must be in the ergative case ("Zenbatekoak").

Correct translation:
Zenbatekoak zure saldoa gainditzen du.
```

<!-- cache_translation_check_eu_a5008dc50eae9d24e0270ce15d8f4c58db3134752e61a5f555ae8c38b9c6c8cd -->
```
        <source>S&amp;ubtract fee from amount</source>
        <translation>Kendu komisioa zenbatekotik</translation>
    
ERR
The translation is missing the shortcut key indicator '&' which was present in the source text. In the context of the 'eu' (Basque) translation, it should be included to allow for keyboard navigation.

Correct translation:
Kendu &komisioa zenbatekotik
```

<!-- cache_translation_check_eu_e867d69f0e43650d613b701ced2a13c4f1c4191cccdef4df5de06e138e081dd6 -->
```
        <source>The signature could not be decoded.</source>
        <translation>Sinadura dekodetu ezin da.</translation>
    
ERR
The Basque translation "Sinadura dekodetu ezin da." is grammatically incorrect. In this context, the auxiliary verb should be "ezin izan da" or the word order should be adjusted to correctly convey "could not be".

Correct translation:
Sinadura ezin izan da deskodetu.
```

<!-- cache_translation_check_eu_f36d2f4e6172ac9fec36d1404dcf9b15572e18f0abd5239a7bb68e8dbb02ae10 -->
```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>%1 konfirmazio</translation>
    
ERR
The translation is incorrect because "konfirmazio" is not correct in Basque for "confirmations". The correct translation should be "konfirmazio" for singular, but for plural it should be "konfirmazio", which is still not quite right; the correct plural form in Basque is "konfirmazio". However, the actual Basque for "confirmation" is "berrespen", and the plural form is "berrespen". Additionally, the word is missing the plural suffix and adaptation for "%1" (e.g. "%1 berrespen").

Correct translation:
%1 berrespen
```

<!-- cache_translation_check_eu_21153ea5599085c23889bb2c9c20276f267115b9c8fceb1aea8b805b71f79b66 -->
```
        <source>Net amount</source>
        <translation>Sareko zenbatekoa</translation>
    
ERR
The translation "Sareko zenbatekoa" incorrectly interprets "Net" as "Network" (Sare). In a financial or Bitcoin context, "Net amount" refers to the total amount after deductions (like fees), which should be translated as "garbi".

Correct translation:
Zenbateko garbia
```

<!-- cache_translation_check_eu_7af200fc81216e6b7c827dec6c2251a77cfce4de457adc05d3f9a531f4574b23 -->
```
        <source>Abandoned</source>
        <translation>Utzi</translation>
    
ERR
The translation "Utzi" is the verb (to leave/abandon). In the context of a transaction status (like "Abandoned"), the past participle/adjective "Utzia" should be used.

Correct translation:
Utzia
```

<!-- cache_translation_check_eu_50b0d64ae7e406c241e3c0deb799a94f5f6e6cbcc6dfc72ba77a5e26e35d0205 -->
```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>Baieztatzen (%1 gomendatutako%2 baieztapenetatik)</translation>
    
ERR
The translation has a whitespace issue: there is no space between the format specifier '%1' and the text 'gomendatutako', and the format specifiers are used in a way that creates a grammatical or formatting error in Basque. Specifically, 'gomendatutako%2' lacks a space, and the phrasing is slightly unnatural for the context.

Correct translation:
Baieztatzen (%1 / %2 gomendatutako baieztapen)
```

<!-- cache_translation_check_eu_502b42fe8fbbbf01c3ff18099755f7ee8ad6e6dbb9f3c219f0c1587677570d72 -->
```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Heldugabe ( %1baieztapen, erabilgarri izango da %2ondoren)</translation>
    
ERR
The translation contains whitespace issues. There are missing spaces after the opening parenthesis and before/after the format specifiers, which makes the text run together.

Correct translation:
Heldugabe (%1 baieztapen, %2 ondoren egongo da erabilgarri)
```

<!-- cache_translation_check_eu_bdcf55dc0f0ce2d61fa1f3c79e8fb886be362c244fcb93358c3d6529d9ed3e8c -->
```
        <source>Mined</source>
        <translation>Meatua</translation>
    
ERR
The translation "Meatua" is incorrect in Basque. The correct term for "Mined" in the context of Bitcoin (referring to coins that have been produced through mining) is "Meatua". However, "Meatua" in Basque more often means "mine" (noun: a mine, as in a coal mine). The correct translation for the verb "Mined" (as in "has been mined") is "Meatutako".

Correct translation:
Meatutako
```

<!-- cache_translation_check_eu_121926b40832dd954279b8909907420e12fa442716959927c2b9b665e0322444 -->
```
        <source>This week</source>
        <translation>Aste honetankoak</translation>
    
ERR
The translation "Aste honetankoak" is incorrect and ungrammatical in Basque. The correct translation for "This week" is "Aste hau".

Correct translation:
Aste hau
```

<!-- cache_translation_check_eu_bdcf55dc0f0ce2d61fa1f3c79e8fb886be362c244fcb93358c3d6529d9ed3e8c -->
```
        <source>Mined</source>
        <translation>Meatua</translation>
    
ERR
The translation "Meatua" is incorrect in Basque. The correct term for "Mined" in the context of Bitcoin (referring to coins that have been produced through mining) is "Meatua". However, "Meatua" in Basque more often means "mine" (noun: a mine, as in a coal mine). The correct translation for the verb "Mined" (as in "has been mined") is "Meatutako".

Correct translation:
Meatutako
```

<!-- cache_translation_check_eu_9d64abf669ded6ad9ccbf5d92b705e8136cf8e6d9114cf117f401b1528a3b122 -->
```
        <source>Copy &amp;amount</source>
        <translation>Kopiatu kopurua</translation>
    
ERR
The shortcut key indicator '&amp;' is missing from the translation. According to the instructions, it must exist exactly once.

Correct translation:
Kopiatu &amp;kopurua
```

<!-- cache_translation_check_eu_447ad2bd49a2a2db4e8f2133d7707f2ced6d4d0a139638d908cff71bca80df29 -->
```
        <source>Copy transaction &amp;ID</source>
        <translation>Kopiatu transakzioaren IDa</translation>
    
ERR
The translation is missing the shortcut key marker (&amp;), which must be present exactly once according to the instructions.

Correct translation:
Kopiatu transakzioaren &amp;IDa
```

<!-- cache_translation_check_eu_30f9c6cda1d0f905173b4851a737609d9abc55f78447bfa9593c3396aa2daa8a -->
```
        <source>Increase transaction &amp;fee</source>
        <translation>Handitu transakzioaren komisioa</translation>
    
ERR
The translation is missing the shortcut key indicator '&'. The instructions require it to exist exactly once if it is present in the source.

Correct translation:
&Handitu transakzioaren komisioa
```

<!-- cache_translation_check_eu_4858e2f9be5bc29b6597eb5faae1197691d48465ab394580c70f6d536bb90fd5 -->
```
        <source>&amp;Edit address label</source>
        <translation>Editatu helbidearen etiketa</translation>
    
ERR
The shortcut key indicator '&' is missing from the translation. It must be included exactly once as per the instructions.

Correct translation:
&Editatu helbidearen etiketa
```

<!-- cache_translation_check_eu_4d214d79e778535687b41a0c9c5a49cb40cf48d9de74baf04b1d6891b8968922 -->
```
        <source>Range:</source>
        <translation>tartea:</translation>
    
ERR
The translation should start with a capital letter to match the source text ("Range:").

Correct translation:
Tartea:
```

<!-- cache_translation_check_eu_2b50973df809c597a5f028e027bb467eb695accea5fb8cbaa16601fca1b93d24 -->
```
        <source>to</source>
        <translation>-ra</translation>
    
ERR
In Basque, "-ra" is a suffix used to indicate direction (the allative case). However, as a standalone UI label (such as "To: [Address]"), a suffix with a hyphen is grammatically incorrect and visually out of place. The standard translation for "To" as a recipient label in Basque is "Nori" (To whom) or "Hona" (To here).

Correct translation:
Nori
```

<!-- cache_translation_check_eu_c96813b58dcbc0329b99f37709935198d06b11368b896c324a5aac4247a2413b -->
```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>%shuts egin du -assumeutxo snapshot egoera baliozkotzean. Honek hardware-arazo bat, softwareko akats bat, edo softwarearen aldaketa txar bat adierazten du, snapshot baliogabe bat kargatzea baimendu duena. Horren ondorioz, nodoa itzali egingo da eta snapshot horretan oinarrituta eraikitako edozein egoera erabiltzen uzti, katearen altuera%d -tik -%dra berrezarriz. Hurrengo berrabiaraztean, nodoak %d-tik berriro sinkronizatzen hasiko da, snapshot daturik erabili gabe. Mesedez, jakinarazi gertaera hau %s-ri, snapshot-a nola lortu zenuen azalduz. Snapshot baliogabearen chainstate diskoan utziko da, errore hau eragin duen arazoa diagnostikatzeko lagungarria izan badaiteke.</translation>
    
ERR
The translation contains several spacing issues with format specifiers and a spelling error.

1. In the first sentence, there is no space between the format specifier `%s` and the word "huts".
2. In the third sentence, the verb "uzti" is a spelling error (should be "utziz" or "utziko du" depending on the structure, but "erabiltzeari utziz" fits the context of "stop using").
3. There is a missing space between "altuera" and "%d".
4. The phrase "%d -tik -%dra" contains an unnecessary hyphen before the second specifier and inconsistent spacing.
5. In the fourth sentence, "nodoak %d-tik berriro sinkronizatzen hasiko da" uses the wrong ergative case for the subject (should be "nodoa").

Correct translation:
%s-k huts egin du -assumeutxo snapshot egoera baliozkotzean. Honek hardware-arazo bat, softwareko akats bat, edo softwarearen aldaketa txar bat adierazten du, snapshot baliogabe bat kargatzea baimendu duena. Horren ondorioz, nodoa itzali egingo da eta snapshot horretan oinarrituta eraikitako edozein egoera erabiltzeari utziko dio, katearen altuera %d-tik %d-ra berrezarriz. Hurrengo berrabiaraztean, nodoa %d-tik berriro sinkronizatzen hasiko da, snapshot daturik erabili gabe. Mesedez, jakinarazi gertaera hau %s-ri, snapshot-a nola lortu zenuen azalduz. Snapshot baliogabearen chainstate-a diskoan utziko da, errore hau eragin duen arazoa diagnostikatzeko lagungarria izan badaiteke.
```

<!-- cache_translation_check_eu_997393eda3c3657d4686b6b039686be42564a888511b6448a474ae0b54ce678f -->
```
        <source>Disk space for %s may not accommodate the block files. Approximately %u GB of data will be stored in this directory.</source>
        <translation>%sbalioerako disko-lekuak baliteke blokearen fitxategiak hartzeko nahikoa ez izatea. Gutxi gorabehera %uGB datu gordeko dira direktorio honetan.</translation>
    
ERR
There are a few issues with the translation:
1. Whitespace: There is a missing space between the placeholder `%u` and the unit `GB`.
2. Grammar/Formatting: The string `%sbalioerako` attaches the word "balioerako" (meaning "for the value") directly to the placeholder `%s`. In Basque, placeholders for names/entities should generally be separated or handled with appropriate declension suffixes, but "balioerako" is likely an unnecessary addition here. A simpler approach like `%s(e)rako` or `%s-rako` is preferred, or simply adding a space if the variable name is unknown.
3. Terminology: "blokearen fitxategiak" (the files of the block) is better expressed as "bloke-fitxategiak" (block files).

Correct translation:
%s-(e)rako disko-lekuak baliteke bloke-fitxategiak hartzeko nahikoa ez izatea. Gutxi gorabehera %u GB datu gordeko dira direktorio honetan.
```

<!-- cache_translation_check_eu_965d132789e3102d5810a15aa09345561a02bc8e2f063ce6a30ad11e191404d9 -->
```
        <source>File %s already exists. If you are sure this is what you want, move it out of the way first.</source>
        <translation>%sFitxategia dagoeneko existitzen da. Ziur zaude hori nahi duzula, lekuz aldatu ezazu lehenik.</translation>
    
ERR
There is a whitespace formatting issue. The format specifier '%s' is joined with the following word 'Fitxategia' without a space.

Correct translation:
%s fitxategia dagoeneko existitzen da. Ziur bazaude hori dela nahi duzuna, lekuz aldatu ezazu lehenik.
```

<!-- cache_translation_check_eu_34d833cb64385020bba827ec751267ed25a7f3dc9c2c5e40071a14fb54372390 -->
```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>Tipula lotura helbide bat baino gehiago eman da. Automatikoki %ssortutako Tor tipula zerbitzurako erabiliko da.</translation>
    
ERR
There is a whitespace formatting issue. The format specifier `%s` is directly touching the word "sortutako" (`%ssortutako`), which will result in the substituted value being concatenated with the following word. There should be a space between them.

Correct translation:
Tipula lotura helbide bat baino gehiago eman da. Automatikoki %s sortutako Tor tipula zerbitzurako erabiliko da.
```

<!-- cache_translation_check_eu_7361ffda025f4e801d0e960fcf826fac49a33c8037206a8f45c1a238da8874fd -->
```
        <source>Rename of '%s' -&gt; '%s' failed. You should resolve this by manually moving or deleting the invalid snapshot directory %s, otherwise you will encounter the same error again on the next startup.</source>
        <translation>'%s'-&gt; '%s' berrizendatzea huts egin du. Hau konpondu behar duzu snapshot baliogabeko %sdirektorioa eskuz lekuz aldatuz edo ezabatuz; bestela, hurrengo abioan errore bera berriro gertatuko da.</translation>
    
ERR
There is a whitespace issue with the format specifier `%s`. It is attached to the word "direktorioa" (`%sdirektorioa`), which would cause the directory path and the word to be merged (e.g., "/path/todirektorioa"). There should also be a space before the arrow to match the source. Additionally, the grammar in the first sentence is slightly off.

Correct translation:
'%s' -> '%s' berrizendatzeak huts egin du. Hau konpondu behar duzu baliogabeko %s snapshot direktorioa eskuz lekuz aldatuz edo ezabatuz; bestela, hurrengo abioan errore bera berriro gertatuko da.
```

<!-- cache_translation_check_eu_0886127e76d7914273332e47cbbd8405e68280176224b5ba2f848f1462a1bd3b -->
```
        <source>SQLiteDatabase: Unknown sqlite wallet schema version %d. Only version %d is supported</source>
        <translation>SQLiteDatabase: Sqlite zorro eskemaren %dbertsio ezezaguna. Bertsio%d baino ez da onartzen</translation>
    
ERR
The translation has spacing issues involving the format specifiers. There should be a space before the first "%d" and after the second "%d" to ensure readability and correct formatting.

Correct translation:
SQLiteDatabase: Sqlite zorro eskemaren %d bertsio ezezaguna. %d bertsioa baino ez da onartzen
```

<!-- cache_translation_check_eu_3d6e521a3a619fdd9eafa9ee9f3c3bf4047d5096a8da3273dde67db3b80d8c1e -->
```
        <source>Witness data for blocks after height %d requires validation. Please restart with -reindex.</source>
        <translation>%daltueratik gorako blokeetako lekuko datuak baliozkotu behar dira. Mesedez, berrabiarazi -reindex aukerarekin.</translation>
    
ERR
The translation contains a whitespace formatting issue. There should be a space between the format specifier '%d' and the following word 'altueratik' to ensure the number and the word are not concatenated (e.g., "100altueratik" instead of "100 altueratik").

Correct translation:
%d altueratik gorako blokeetako lekuko datuak baliozkotu behar dira. Mesedez, berrabiarazi -reindex aukerarekin.
```

<!-- cache_translation_check_eu_1566917c8d204189196856f2f4dad427c51febeba4239536fe82458dbd90ce9a -->
```
        <source>%s is set very high!</source>
        <translation>%soso altua ezarrita dago!</translation>
    
ERR
The format specifier `%s` from the source has been corrupted in the translation. It was merged with the word "oso" (very) to become `%soso`.

Correct translation:
%s oso altua ezarrita dago!
```

<!-- cache_translation_check_eu_b602dcdd6db95d4a4333e9adeaa772d6be17aa2cbfab7d34e68b02755aa4fa1b -->
```
        <source>Cannot obtain a lock on directory %s. %s is probably already running.</source>
        <translation>Ezin da blokeoa lortu direktorioan%s. %s ziurrenik dagoeneko exekutatzen ari da.</translation>
    
ERR
There is a missing space between "direktorioan" and the format specifier "%s".

Correct translation:
Ezin da blokeoa lortu direktorioan %s. %s ziurrenik dagoeneko exekutatzen ari da.
```

<!-- cache_translation_check_eu_d49a4baf32ed262ec8da4340fa8b9225a9d4bc870430926d0de89e267cf62d61 -->
```
        <source>Cannot resolve -%s address: '%s'</source>
        <translation>Ezin da –%s helbidea ebatzi: '%s'</translation>
    
ERR
The translation uses an en-dash (–) instead of a hyphen-minus (-) for the first format specifier prefix. In technical contexts, especially when referring to command-line flags or specific parameters like -%s, the character must remain a standard hyphen.

Correct translation:
Ezin da -%s helbidea ebatzi: '%s'
```

<!-- cache_translation_check_eu_270747e1b8d6ac09807f76444409aa6ebc5f12800f535c33cf0996ada81421bb -->
```
        <source>%s is set very high! Fees this large could be paid on a single transaction.</source>
        <translation>%soso altua ezarrita dago! Horrelako kuota handiak transakzio bakar batean ordaindu litezke.</translation>
    
ERR
The format specifier %s has been merged with the Basque word 'oso' (meaning 'very'), resulting in '%soso'. This will prevent the variable from being correctly replaced or will result in incorrect text display (e.g., "0.1oso" instead of "0.1 oso").

Correct translation:
%s oso altua ezarrita dago! Horrelako kuota handiak transakzio bakar batean ordaindu litezke.
```

<!-- cache_translation_check_eu_8f98adb68228fed7990b8518711af257ed19db86235c654db1053f433d6f8ea1 -->
```
        <source>Error loading %s: External signer wallet being loaded without external signer support compiled</source>
        <translation>Errorea kargatzean%s: Kanpoko sinatzailearen zorroa kargatzen ari da, baina kanpoko sinatzailearen euskarririk gabe konpilatuta dago.</translation>
    
ERR
There is a missing space before the format specifier '%s'.

Correct translation:
Errorea %s kargatzean: Kanpoko sinatzailearen zorroa kargatzen ari da, kanpoko sinatzailearen euskarririk gabe konpilatu baita.
```

<!-- cache_translation_check_eu_5dd063c6b1a3dbad5f4992672cada3d13d2e7c68d18f21887a54595759452036 -->
```
        <source>Error: Transaction %s in wallet cannot be identified to belong to migrated wallets</source>
        <translation>Errorea: %stransakzioa ezin da identifikatu migratutako zorroei dagokiola</translation>
    
ERR
There is a missing space between the format specifier '%s' and the following word 'transakzioa', which will cause the value and the word to be concatenated.

Correct translation:
Errorea: %s transakzioa ezin da identifikatu migratutako zorroei dagokiola
```

<!-- cache_translation_check_eu_f35ea2e27561d0e0bba6c1150f6b096423afbcd61c171ceb5c0f4579484f3d39 -->
```
        <source>Fee estimation failed. Fallbackfee is disabled. Wait a few blocks or enable %s.</source>
        <translation>Kuota estimazioa huts egin du. Fallbackfee desgaituta dago. Bloke batzuk itxaron edo gaitu %s.</translation>
    
ERR
The Basque translation contains a grammatical error in the first sentence. The noun "estimazioa" (the estimation) is the subject of the intransitive verb "huts egin" (to fail), so it should be in the absolutive case ("estimazioak" if ergative, but "estimazioak huts egin du" is the standard form for this compound verb in many dialects, or simply "Estimazioak"). More importantly, "Kuota" (Fee) should be in the genitive or as a compound. Furthermore, "Fallbackfee" is left untranslated and could be better integrated.

Correct translation:
Tasaren estimazioak huts egin du. Fallbackfee desgaituta dago. Itxaron bloke batzuk edo gaitu %s.
```

<!-- cache_translation_check_eu_fa82aceb6b15e799789641d0a038ae71d3c29c1b6e280c23f62b4e2c2fb4052c -->
```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>Balio baliogabea %s=-&lt;amount&gt;rentzat: '%s' (gutxienez %sminrelay kuota izan behar du transakzio trabatuak saihesteko).</translation>
    
ERR
The translation contains a typo in the format specifier. The source text has `%s=<amount>`, but the translation has `%s=-<amount>` (an extra hyphen). Additionally, there is a missing space between the placeholder `%s` and the word "minrelay".

Correct translation:
Balio baliogabea %s=&lt;amount&gt;rentzat: '%s' (gutxienez %s minrelay kuota izan behar du transakzio trabatuak saihesteko).
```

<!-- cache_translation_check_eu_e4b73486fd5e044a45bed1c44b6fd8384438f5a49289b86c242097747af446fa -->
```
        <source>UTXO snapshot failed to validate. Restart to resume normal initial block download, or try loading a different snapshot.</source>
        <translation>UTXO irudiak balidatzeko huts egin du. Normalean Bloke hasierako deskarga berriro hasteko berrabiarazi, edo saiatu beste irudi bat kargatzen.</translation>
    
ERR
The translation has grammatical and terminology issues. "Normalean" means "Normally" (adverb), whereas the source uses "normal" as an adjective modifying the block download. Also, "Bloke" is unnecessarily capitalized, and the phrasing of the first sentence is slightly awkward.

Correct translation:
UTXO snapshot-aren balidazioak huts egin du. Berrabiarazi hasierako bloke-deskarga normalarekin jarraitzeko, edo saiatu beste snapshot bat kargatzen.
```

<!-- cache_translation_check_eu_8940817eba281907eea373f3e26f0c0937c0661de9afb977ab6401709054f2f3 -->
```
        <source>default wallet</source>
        <translation>Zorro lehenetsia</translation>
    
ERR
In Basque, "wallet" is typically translated as "diru-zorro" (literally "money-bag/purse"). While "zorro" can mean a bag or case, "diru-zorro" is the standard term used in financial and software contexts for a wallet. Additionally, "Zorro" capitalized can be confused with the fictional character.

Correct translation:
diru-zorro lehenetsia
```

<!-- cache_translation_check_eu_2dfbe446b98a039174d224c1eac150b5e13d2624dcff68290252ac0f5e9fc221 -->
```
        <source>Assumeutxo data not found for the given blockhash '%s'.</source>
        <translation>Assumeutxo daturik ez da aurkitu eman den '%s' bloke-hasharentzat</translation>
    
ERR
The translation is missing the trailing period that is present in the source text.

Correct translation:
Assumeutxo daturik ez da aurkitu eman den '%s' bloke-hasharentzat.
```

<!-- cache_translation_check_eu_7877cc91f52412dce7ebc7d8a66d2810d8f5f46d3288c71944d108f1840b8797 -->
```
        <source>Can't spend unconfirmed version %d pre-selected input with a version 3 tx</source>
        <translation>Ezin da baieztatu %dgabeko bertsioaren aurrez hautatutako sarrera bat gastatu 3. bertsioaren transakzio batekin</translation>
    
ERR
The translation contains a spacing error and poor phrasing. The term "%dgabeko" merges the format specifier "%d" with the word "gabeko" (without), which will prevent the number from being displayed correctly. Additionally, "baieztatu gabeko" (unconfirmed) is split awkwardly.

Correct translation:
Ezin da gastatu baieztatu gabeko %d bertsioaren aurrez hautatutako sarrera bat 3. bertsioko tx batekin
```

<!-- cache_translation_check_eu_d7db3cbb24a574036078edbdb81965423a9d7231e2304c5d2828c6a68482b9aa -->
```
        <source>Can't spend unconfirmed version 3 pre-selected input with a version %d tx</source>
        <translation>%dEzin da baieztatu gabeko 3. bertsioaren aurrez hautatutako sarrera bat gastatu bertsioaren transakzio batekin</translation>
    
ERR
The format specifier '%d' is placed at the beginning of the sentence without a space and in the wrong context. In the source text, it refers to the transaction version ("version %d tx"), but in the translation, it is positioned at the start of the string.

Correct translation:
Ezin da baieztatu gabeko 3. bertsioaren aurrez hautatutako sarrera gastatu %d bertsio-transakzio batekin
```

<!-- cache_translation_check_eu_9928e851e1f1148b8988cf555ab6246ca48088c06375c450688bea9e396897da -->
```
        <source>Config setting for %s only applied on %s network when in [%s] section.</source>
        <translation>%skonfigurazio-ezarpena %s soilik aplikatzen da sarean, [%s] atalean dagoenean.</translation>
    
ERR
The translation contains grammatical and structural errors. Specifically, the second %s (representing the network name) is positioned such that it reads "only %s applies to the network" instead of "applies only on the %s network". Additionally, the first %s is missing a space before the following word.

Correct translation:
%s konfigurazio-ezarpena %s sarean soilik aplikatzen da [%s] atalean dagoenean.
```

<!-- cache_translation_check_eu_75bae7c86a68c2c80ac87de8e86a3a0f2be6f57159e356707d1e0009adfec020 -->
```
        <source>Copyright (C) %i-%i</source>
        <translation>Copyright (C) %i- %i</translation>
    
ERR
The translation contains a stray space after the hyphen in the date range specifier ("%i- %i" instead of "%i-%i").

Correct translation:
Copyright (C) %i-%i
```

<!-- cache_translation_check_eu_981772620ed4b2f01a4dc2167e4ae365df97f817c8397a0f8def6969167e1a8e -->
```
        <source>Could not find asmap file %s</source>
        <translation>Ezin izan da %sasmap fitxategia aurkitu</translation>
    
ERR
There is a whitespace format issue. The format specifier '%s' is directly touching the word 'asmap', which will cause the filename/path to be concatenated with the word (e.g., "/path/to/fileasmap" instead of "/path/to/file asmap").

Correct translation:
Ezin izan da %s asmap fitxategia aurkitu
```

<!-- cache_translation_check_eu_c5b7342ba90efe8bdda92814aa69563f084e56877838b6035ec29088b800e513 -->
```
        <source>Error loading %s</source>
        <translation>Kargatzean %serrorea</translation>
    
ERR
The translation lacks a space between the format specifier '%s' and the word 'errorea', which would cause the variable content to run directly into the next word (e.g., "filenameerrorea"). Additionally, the word order is slightly unnatural for this context.

Correct translation:
Errorea %s kargatzean
```

<!-- cache_translation_check_eu_61000348a5cafabac1beba27fa747ac6078a6bf4321123af9b30c62dd86aab6f -->
```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>Errorea: Dumpfitxategiaren bat-datorrenik ez. Kalkulatutakoa , %sespero zena%s </translation>
    
ERR
The translation has several issues:
1. Format specifiers: The `%s` specifiers are placed incorrectly. In the source, they represent the values for "Computed" and "Expected". In the translation, the first `%s` is attached to a word (`%sespero`), and the second `%s` is at the end, which would result in "Kalkulatutakoa , [value]espero zena[value]".
2. Whitespace: There is an unnecessary space before the comma and a missing space after the comma.
3. Grammar: "Dumpfitxategiaren bat-datorrenik ez" is a poor way to translate "Dumpfile checksum does not match".

Correct translation:
Errorea: Dump-fitxategiaren egiaztapen-batura ez dator bat. Kalkulatutakoa: %s, espero zena: %s
```

<!-- cache_translation_check_eu_06137d4e30b86166b83c7267685738b55619775837dcdb9960c35925da9b0e24 -->
```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>Errorea: Ezin izan da %ubertsioa uint32_t gisa analizatu</translation>
    
ERR
There is a whitespace issue in the translation. The format specifier `%u` is concatenated with the word "bertsioa" (%ubertsioa), which will likely cause display issues and prevents proper spacing.

Correct translation:
Errorea: Ezin izan da %u bertsioa uint32_t gisa analizatu
```

<!-- cache_translation_check_eu_6c45d2622208e1e3ba52b623362a3f4a06835f30a2a1071f48de5f6216a86f56 -->
```
        <source>Error: database transaction cannot be executed for wallet %s</source>
        <translation>Errorea: datu-baseko transakzioa ezin da exekutatu %szorrorako</translation>
    
ERR
There is a whitespace issue in the translation. The format specifier `%s` is joined with the word "zorrorako" (for the wallet), resulting in `%szorrorako`. There should be a space between the specifier and the following word to ensure the variable is rendered correctly and the text remains readable.

Correct translation:
Errorea: datu-baseko transakzioa ezin da exekutatu %s zorrorako
```

<!-- cache_translation_check_eu_22bcb1a22c62d9afe6c52ec1e28d1f98f76809a89c3faa149ea713a2d7b1d8f7 -->
```
        <source>Ignoring duplicate -wallet %s.</source>
        <translation>-wallet errepikatuari %sez ikusiarena egiten.</translation>
    
ERR
The translation contains a typo where the word "ez" (part of the verb phrase "ez ikusiarena egin" meaning "to ignore") is attached to the format specifier "%s", resulting in "%sez". This will cause the output to display the wallet name immediately followed by the letters "ez" without a space, and it fundamentally changes the intended grammatical structure of the sentence.

Correct translation:
-wallet %s errepikatua ez ikusiarena egiten.
```

<!-- cache_translation_check_eu_aacfdcd2f6ac30bccb1a97fb5158989c3de31379e2127d00db07f789df7d52b9 -->
```
        <source>Initialization sanity check failed. %s is shutting down.</source>
        <translation>Hasierako zuzentasun-egiaztatak huts egin du. %sitxieren da</translation>
    
ERR
The translation contains spacing and grammatical errors. Specifically, there is a missing space before the format specifier "%s", and "itxieren da" is grammatically incorrect for "is shutting down".

Correct translation:
Hasierako zuzentasun-egiaztapenak huts egin du. %s itzaltzen ari da.
```

<!-- cache_translation_check_eu_7ef82543e2faa8a7a7916354cbd37aa1c3f77b83cb9210e0b683ef21a5fc4e51 -->
```
        <source>Prune cannot be configured with a negative value.</source>
        <translation>Moztu ez da konfiguratu daiteke balio negatibo batekin.</translation>
    
ERR
The Basque grammar is incorrect. The phrase "ez da konfiguratu daiteke" is ungrammatical; the potential mood ("cannot") should be expressed using "ezin da" or "ez daiteke". Additionally, while "Moztu" means "to cut", "Inausketa" is the more standard term for "Pruning" in a technical/Bitcoin context.

Correct translation:
Inausketa ezin da balio negatibo batekin konfiguratu.
```

<!-- cache_translation_check_eu_f860e5fec957327f1be3f2c3945c0d219bec809e195d7489bde89790c0cafe3a -->
```
        <source>Reducing -maxconnections from %d to %d, because of system limitations.</source>
        <translation>-maxconnections %degingarren %dra murrizten, sistema-mugak direla eta.</translation>
    
ERR
The Basque translation is incorrect. The translator added the suffix "egingarren" to the first format specifier "%d", which is inappropriate here as it turns the number into an ordinal (e.g., "100th") and creates a nonsensical word. The verb form "murrizten" is also missing an auxiliary verb to be grammatically complete in this context.

Correct translation:
-maxconnections %d(e)tik %d(e)ra murrizten, sistema-mugak direla eta.
```

<!-- cache_translation_check_eu_86b849098ba04264fc92ac12cb532ba3ed0f2ad5fe530d3e1cfba973b695d2c1 -->
```
        <source>SQLiteDatabase: Failed to execute statement to verify database: %s</source>
        <translation>SQLiteDatabase: Huts egin du datu-basea egiaztatzeko adierazpena exekutatzean:%s</translation>
    
ERR
There is a whitespace issue. The translation is missing a space between the colon and the format specifier '%s'.

Correct translation:
SQLiteDatabase: Huts egin du datu-basea egiaztatzeko adierazpena exekutatzean: %s
```

<!-- cache_translation_check_eu_0ff409ddee529b31f0d1ca3b2b0777f1304fb2910522cc23a3ecf00daebb92bf -->
```
        <source>SQLiteDatabase: Unexpected application id. Expected %u, got %u</source>
        <translation>SQLiteDatabase: Aplikazio ID ustekabea. Espero zena:%u , lortutakoa:%u</translation>
    
ERR
There are whitespace formatting issues in the translation. There is a stray space before the comma, and spaces are missing after the colons.

Correct translation:
SQLiteDatabase: Aplikazio ID ustekabea. Espero zena: %u, lortutakoa: %u
```

<!-- cache_translation_check_eu_cea169cbb259c6ccac36a767d2c216efc9a8fc5814481ee679e9f4167cbf8b9d -->
```
        <source>Signer echoed unexpected address %s</source>
        <translation>Sinatzaileak ustekabeko helbidea errepikatu du%s</translation>
    
ERR
The translation has a whitespace issue: there is no space before the format specifier '%s'. In Basque, there should be a space between the word and the variable to ensure readability.

Correct translation:
Sinatzaileak ustekabeko %s helbidea errepikatu du
```

<!-- cache_translation_check_eu_b97bb67d3eba158f1c427a1ec866332ae1c0b7818333e6d00d5a3e39ff679597 -->
```
        <source>Signer returned error: %s</source>
        <translation>Sinatzaileak errorea itzuli du:%s</translation>
    
ERR
The translation is missing a space before the format specifier '%s', which exists in the source text.

Correct translation:
Sinatzaileak errorea itzuli du: %s
```

<!-- cache_translation_check_eu_acbbefd0682f1070522dfdb280dd811b978e0b60e3b397f64bcf6d6ce19d97c3 -->
```
        <source>System error while flushing: %s</source>
        <translation>Sistemaren errorea garbitzean:%s</translation>
    
ERR
The translation is missing a space after the colon, which is present in the source text and should be maintained for proper formatting.

Correct translation:
Sistemaren errorea garbitzean: %s
```

<!-- cache_translation_check_eu_cb1be3e207f4b072afb7a2b9fc7d70ddf3a801fa4168ed847ffbe29d8ae1553e -->
```
        <source>System error while loading external block file: %s</source>
        <translation>Sistemaren errorea kanpoko bloke fitxategia kargatzean:%s</translation>
    
ERR
There is a whitespace formatting issue. There should be a space before the format specifier '%s' to match the source text and maintain readability.

Correct translation:
Sistemaren errorea kanpoko bloke fitxategia kargatzean: %s
```

<!-- cache_translation_check_eu_5b497e5c8133a237bd3c96313d44b422fa791f8ea150ecd51b6e489c36c46580 -->
```
        <source>System error while saving block to disk: %s</source>
        <translation>Sistemaren errorea blokea diskoan gordetzean:%s</translation>
    
ERR
There is a missing space before the format specifier '%s'.

Correct translation:
Sistemaren errorea blokea diskoan gordetzean: %s
```

<!-- cache_translation_check_eu_8a8d8d1a661b9dcb70cfa47ba894ebfe765b334dcef85bf5b688dd21d10c45f0 -->
```
        <source>The specified config file %s does not exist</source>
        <translation>Zehaztutako konfigurazio %sfitxategia ez da existitzen</translation>
    
ERR
The format specifier %s is attached directly to the word "fitxategia", which will cause the substituted text to be concatenated with the word (e.g., "C:\bitcoin.conffitxategia"). There should be a space to separate the filename from the noun. Additionally, the word order is slightly awkward.

Correct translation:
Zehaztutako %s konfigurazio-fitxategia ez da existitzen
```

<!-- cache_translation_check_eu_d7fef2f316f15ad46c27ba88dca374eb60f79e5491b2851ae325624ec8858612 -->
```
        <source>This is the minimum transaction fee you pay on every transaction.</source>
        <translation>Hau da transakzio bakoitzean ordaintzen duzun gutxieneko transakzio-tasa</translation>
    
ERR
The translation is missing the trailing period that exists in the source text.

Correct translation:
Hau da transakzio bakoitzean ordaintzen duzun gutxieneko transakzio-tasa.
```

<!-- cache_translation_check_eu_1723180c1e8fd0c4e2277f26d99dac31dd5d63b4a5ecbad196effbadb651fb48 -->
```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>Transakzioak helbide aldaketa behar du, baina ezin dugu sortu.</translation>
    
ERR
The Basque translation is slightly inaccurate regarding the term "change address". In the context of Bitcoin, "change" refers to the leftover amount from a transaction (itzulera), not a change or modification (aldaketa). "Helbide aldaketa" translates to "address change" (as in changing one's residence or modifying an address), whereas "itzulera-helbide" is the correct term for a Bitcoin change address.

Correct translation:
Transakzioak itzulera-helbide bat behar du, baina ezin dugu sortu.
```

<!-- cache_translation_check_eu_ae260c744ccb6efbe93cda0228270138b1abef6fb7da1f7657c51a3688fda062 -->
```
        <source>Unable to bind to %s on this computer. %s is probably already running.</source>
        <translation>Ezin da lotu %sordenagailu honetan. %sziurrenik martxan dago.</translation>
    
ERR
There are missing spaces between the format specifiers (%s) and the adjacent words, which will cause the substituted text to be concatenated with the Basque words.

Correct translation:
Ezin da %s lotu ordenagailu honetan. %s ziurrenik martxan dago.
```

<!-- cache_translation_check_eu_e0f46870e614fcde8d7fab0a9f03fe3af06ca34ee9804b637b1ca01b2c5d8818 -->
```
        <source>Unable to open %s for writing</source>
        <translation>Ezin da ireki %sidazteko</translation>
    
ERR
There is a whitespace issue in the translation. The format specifier "%s" is directly attached to the word "idazteko" (%sidazteko), which would result in the filename and the word being joined together (e.g., "file.txtidazteko"). Additionally, the word order is slightly unnatural for Basque.

Correct translation:
Ezin da %s ireki idazteko
```

<!-- cache_translation_check_eu_28cb9a45807d2f2661598afa821fad71f7361c0e4500de2b5ddaa9204ff424f3 -->
```
        <source>Unknown -blockfilterindex value %s.</source>
        <translation>-blockfilterindex balio %s ezezaguna .</translation>
    
ERR
The translation contains an unnecessary space before the final period.

Correct translation:
-blockfilterindex balio %s ezezaguna.
```

<!-- cache_translation_check_eu_ab635a123b18e59084b6cf00546ef3f2f930324064bde9d689402d1ff1addeee -->
```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>Arau berri ezezagunak aktibatu dira (versionbit%i )</translation>
    
ERR
There is a whitespace formatting issue. There should be a space before the format specifier `%i` and no space between `%i` and the closing parenthesis.

Correct translation:
Arau berri ezezagunak aktibatu dira (versionbit %i)
```

<!-- cache_translation_check_eu_6012d78e1b3629bdfa010c6d737b306e62fbc02cb700e1458b9c1a47ec68ccb5 -->
```
        <source>Unrecognised option "%s" provided in -test=&lt;option&gt;.</source>
        <translation>Aukerak hautazko balioa "%s"  -test=&lt;option&gt; eremuan zehaztu behar da.</translation>
    
ERR
The translation completely changes the meaning of the source text. The original English sentence indicates that an unrecognized option was provided, whereas the Basque translation suggests that a value must be specified in a specific field. Additionally, there is a double space after the format specifier.

Correct translation:
"%s" aukera ezezaguna eman da -test=<option> parametroan.
```

<!-- cache_translation_check_eu_9548b7e9675707b5297ddb935b602ff059daf3c7f2585ea5e70190ff781d77c3 -->
```
        <source>Wallet file creation failed: %s</source>
        <translation>Zorro fitxategia sortzeak huts egin du:%s</translation>
    
ERR
There is a spacing issue: the space after the colon is missing. Additionally, while "Zorro" can mean wallet/bag, "Diru-zorro" is the standard term used in Basque for a Bitcoin or financial wallet.

Correct translation:
Diru-zorro fitxategia sortzeak huts egin du: %s
```

<!-- cache_translation_check_eu_710b6f3d3439cbaa5082ab0b5c74d3ac3c7555d94dacf8028ad3a9bced3e3342 -->
```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>acceptstalefeeestimates ez da onartzen%s katean.</translation>
    
ERR
There is a missing space before the format specifier '%s'. In the source, there is a space between "on" and "%s", but in the Basque translation, "onartzen" and "%s" are joined together.

Correct translation:
acceptstalefeeestimates ez da onartzen %s katean.
```

<!-- cache_translation_check_eu_43c8f43720300a4b07291ab1ee8f9d137a2071cbbd31ea3330e48b222681cb8f -->
```
        <source>Unsupported logging category %s=%s.</source>
        <translation>Onartzen ez den erregistro kategoria%s =%s.</translation>
    
ERR
There are whitespace formatting issues. There is a missing space between "kategoria" and the first "%s", and there is an unnecessary space added before the "=" sign.

Correct translation:
Onartzen ez den erregistro kategoria %s=%s.
```

<!-- cache_translation_check_eu_27784566b1f6917811a0e59ca0aa1ad58fac6256998ec79615e993e3e8e82d1c -->
```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Ez dago nahikoa fitxategi-deskribatzailerik. %deskuragarri, %dbeharrezkoak.</translation>
    
ERR
The format specifiers (%d) are incorrect in the translation. The "d" character has been merged into the following Basque words, which breaks the placeholder functionality. Additionally, there should be spaces for better readability.

Correct translation:
Ez dago nahikoa fitxategi-deskribatzailerik. %d eskuragarri, %d beharrezkoak.
```

<!-- cache_translation_check_eu_8f6a0c8e1635f9fbe67d9508ee9d9129896c8fb36ccaadf0a6135d6d7adfcb13 -->
```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Zorroa berridatzi behar izan da: %sberrabiarazi osatzeko</translation>
    
ERR
There is a whitespace formatting issue. The format specifier `%s` is missing a space after it, which will cause it to be concatenated with the following word "berrabiarazi".

Correct translation:
Zorroa berridatzi behar izan da: %s berrabiarazi osatzeko
```
</details>

Number of issues: 151.
