# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>sr@ijekavianlatin</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bsr@ijekavianlatin%5D%20request)


<!-- cache_translation_check_sr@ijekavianlatin_0d0a31d243186251083dead73b6472ecbead71c7849dbe296d4ec54ff74f92a5 -->
```
        <source>&amp;New</source>
        <translation>&amp;Ново</translation>
    
ERR
The translation uses Cyrillic script ("Ново") but the target locale requests Serbian in ijekavian Latin script. The ampersand is present correctly but must precede the Latin text.

Correct translation:
&amp;Novo
```

<!-- cache_translation_check_sr@ijekavianlatin_208cbebd67e1f4bd409d1575968bff23ee206b62b439c361d251353f6c2650ad -->
```
        <source>C&amp;lose</source>
        <translation>Zatvori</translation>
    
ERR
The translation is missing the shortcut marker (&). The source contains "C&amp;lose" (one & for the shortcut) so the translation must include a single & as well.

Correct translation:
&Zatvori
```

<!-- cache_translation_check_sr@ijekavianlatin_ef6dd13fac4b59842106af9cce819894dc59a875d16a8386e74105ea038bffb7 -->
```
        <source>&amp;Delete</source>
        <translation>&amp;Обриши</translation>
    
ERR
The translation uses Cyrillic script ("Обриши") but the target locale is Serbian in Ijekavian Latin — it should use Latin script. The ampersand is correct (one instance).

Correct translation:
&lt;translation&gt;&amp;Obriši&lt;/translation&gt;
```

<!-- cache_translation_check_sr@ijekavianlatin_48df7cc335dbe779a8dc38d57a7fef7d3e72fe7bd58d739ee04ec6476a7cbf98 -->
```
        <source>Choose the address to receive coins with</source>
        <translation>Одабери адресу за примање</translation>
    
ERR
The translation uses Cyrillic script, but 'sr@ijekavianlatin' requires Latin script with ijekavian dialect. Also, the translation omits "coins" ("novčići" or "kovanice"). 

Correct translation:
Odaberi adresu za primanje novčića
```

<!-- cache_translation_check_sr@ijekavianlatin_fe139c62a0de1618c49d9e08cd49394c7f7148c140e4a7a27b4bf942bc3958d5 -->
```
        <source>&amp;Copy Address</source>
        <translation>&amp;Копирај Адресу</translation>
    
ERR
The translation is in Cyrillic script ("Копирај Адресу") but the requested locale specifies Serbian ijekavian Latin (Latin script). Also keep the ampersand exactly once as the shortcut marker and avoid extra spaces/capitalization issues.

Correct translation:
&amp;Kopiraj adresu
```

<!-- cache_translation_check_sr@ijekavianlatin_d6333b9640a27d33cbd86aeff7bfe7e2ab35fedaae8550dd352508c087fc69d7 -->
```
        <source>Copy &amp;Label</source>
        <translation>Kopiranje &amp;Oznaka</translation>
    
ERR
The translation is grammatically incorrect and uses wrong word forms/capitalization. "Kopiranje &Oznaka" reads as two nouns ("Copying Label") and "Oznaka" is capitalized and in the wrong form. The UI string should be an imperative verb + object.

Correct translation:
Kopiraj &oznaku
```

<!-- cache_translation_check_sr@ijekavianlatin_cabaee2cc453fa8645be3b56816b91c39d2d0c1e24bcff21fb6d011e040dbec2 -->
```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>Ова операција захтева да унесеш лозинку новчаника како би се новчаник откључао.</translation>
    
ERR
The translation is in Serbian Cyrillic script ('Ова операција захтева да унесеш лозинку новчаника како би се новчаник откључао.'), but the requested locale 'sr@ijekavianlatin' requires the Latin script with Ijekavian dialect. Additionally, 'lozinka' is fine for 'passphrase', though 'fraza za pristup' or 'lozinka za novčanik' would also be correct.

Correct translation:
Ova operacija zahtijeva da uneseš lozinku novčanika kako bi se novčanik otključao.
```

<!-- cache_translation_check_sr@ijekavianlatin_15ebeb459b08e31b755855b78a04134bb33cd2275e96967ab6d6d8995e81c811 -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Унеси нову приступну фразу за новчаник&lt;br/&gt;Молимо користи приступну фразу од десет или више насумичних карактера&lt;b&gt;,или&lt;b&gt;осам или више речи&lt;/b&gt;.</translation>
    
ERR
There are multiple issues:
- The translation is in Cyrillic, but 'sr@ijekavianlatin' specifies the Latin script.
- There is a format issue: missing spaces after some punctuation.
- The HTML tags are not properly handled: <b> is not opened/closed correctly in the translation.
- The word order and clarity can be improved.

Correct translation:
Unesi novu pristupnu frazu za novčanik.&lt;br/&gt;Molimo koristi pristupnu frazu od &lt;b&gt;deset ili više nasumičnih karaktera&lt;/b&gt;, ili &lt;b&gt;osam ili više riječi&lt;/b&gt;.
```

<!-- cache_translation_check_sr@ijekavianlatin_0e9dc4f3c014fc32c0f9e1df24c77c80952026632e24c9e281ed86c4ff667f6e -->
```
        <source>Back</source>
        <translation>Назад</translation>
    
ERR
The translation is in Cyrillic ("Назад") but the requested locale is Serbian ijekavian in Latin script. The meaning is correct, but the script is wrong.

Correct translation (Latin script):
Nazad
```

<!-- cache_translation_check_sr@ijekavianlatin_47dff3504bc1da23c387354bedb207492f159e9004c6e6c4dcd3a9083ce9483a -->
```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Упамти, шифрирање новчаника не може у потуности заштити твоје биткоине од крађе од стране малвера инфицира твој рачунар.</translation>
    
ERR
The translation is using Cyrillic script, but 'sr@ijekavianlatin' requires the Ijekavian Latin script. Additionally, the grammar in the second part is off: "малвера инфицира твој рачунар" should be "малвер који инфицира твој рачунар" ("malware infecting your computer"). There is also an incorrect form "у потуности", the correct form is "у потпуности".

Correct translation:
Upamti, šifriranje novčanika ne može u potpunosti zaštititi tvoje bitkoine od krađe od strane malvera koji inficira tvoj računar.
```

<!-- cache_translation_check_sr@ijekavianlatin_a347cb658994035b08e35032b2e46e14965cbbee45df35532eac437a461669e0 -->
```
        <source>Wallet to be encrypted</source>
        <translation>Новчаник за шифрирање</translation>
    
ERR
The translation is in Cyrillic script ('Новчаник за шифрирање'), but 'sr@ijekavianlatin' requires Latin script. Additionally, "шифрирање" is more common in Macedonian/Serbian Cyrillic (but acceptable in Serbian); however, "za šifriranje" or "za enkripciju" can be used. "Wallet" as "novčanik" is correct.

Correct translation:
Novčanik za šifriranje
```

<!-- cache_translation_check_sr@ijekavianlatin_9e24a12e8d7ae5046fb86783dc33dc6119d676c96bb4140e1cfc6cac4f7eb533 -->
```
        <source>The supplied passphrases do not match.</source>
        <translation>Лозинке које сте унели нису исте.</translation>
    
ERR
The translation is in Serbian Cyrillic script, but the requested language is 'sr@ijekavianlatin', which should be in Latin script with Ijekavian dialect.

Correct translation:
Lozinke koje ste unijeli nisu iste.
```

<!-- cache_translation_check_sr@ijekavianlatin_79dbefc44d8faa2d1c4797e638e3468251e386ecd8e30219c872f2829c4caa0b -->
```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Лозинка коју сте унели за дешифровање новчаника је погрешна.</translation>
    
ERR
The translation is in Serbian Cyrillic, not in 'sr@ijekavianlatin', which uses the Latin script. Additionally, "лозинка" is an acceptable translation for "passphrase", but "passphrase" in a Bitcoin context is often better as "frazа" or "tajna fraza" to distinguish from a simple password.

Correct translation:
Lozinka koju ste unijeli za dešifrovanje novčanika je pogrešna.

Or, if preferring greater accuracy for "passphrase":
Frazа koju ste unijeli za dešifrovanje novčanika je pogrešna.
```

<!-- cache_translation_check_sr@ijekavianlatin_011251185a0b842b674885889dbc4549a20df6ec05873fe2047548f7e260d628 -->
```
        <source>Runaway exception</source>
        <translation>Изузетак покретања</translation>
    
ERR
The translation is problematic. The given translation "Изузетак покретања" is not accurate in 'sr@ijekavianlatin' and is also written in Cyrillic, while 'sr@ijekavianlatin' should use Latin script. Additionally, "Runaway exception" in the technical context is better translated as "Neočekivan izuzetak" or "Izuzetak koji se otima kontroli".

Correct translation:
Neočekivan izuzetak
```

<!-- cache_translation_check_sr@ijekavianlatin_d568b4725118b0579b3d9efde1a249dc9930ccefe6f9a2e771f9b8627fa31bfa -->
```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>Унеси Биткоин адресу, (нпр %1)</translation>
    
ERR
The translation uses Serbian Cyrillic script, not the expected Ijekavian Latin script for 'sr@ijekavianlatin'. Also, there is a superfluous comma after "адресу," which does not exist in the source.

Correct translation:
Unesi Bitcoin adresu (npr. %1)
```

<!-- cache_translation_check_sr@ijekavianlatin_329eb67f82a55affc5ba490599fbb6a897a4458bc7ce2fe778458f92b880d84e -->
```
        <source>Unroutable</source>
        <translation>Немогуће преусмерити</translation>
    
ERR
The translation uses Cyrillic script ("Немогуће преусмерити"), but 'sr@ijekavianlatin' requires Latin script. Also, "Unroutable" in network/Bitcoin context would better be translated as "Nije moguće rutirati" or "Nerutabilno" rather than "Nemoguće preusmeriti" (which means "Impossible to redirect").

Correct translation:
Nerutabilno
```

<!-- cache_translation_check_sr@ijekavianlatin_1f2e72c7a6542a45a6e77169c66ee548082d31f4dd9935c97cdb3ab18a6f0d10 -->
```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>Блокирана предаја</translation>
    
ERR
The translation "Блокирана предаја" is inaccurate for two reasons:
1. The script used is Cyrillic, but 'sr@ijekavianlatin' requires Latin script with Ijekavian dialect.
2. "Блокирана предаја" means "Blocked relay" or "Blocked delivery" rather than "Block Relay", which in this context refers to the relaying of information about blocks (as a peer connection type in Bitcoin).

Correct translation:
Prenos blokova
```

<!-- cache_translation_check_sr@ijekavianlatin_99958536d844b9130ac05083e13d5c5db63f936ee6f245fc990599c12e5d262f -->
```
        <source>&amp;Transactions</source>
        <translation>&amp;Трансакције</translation>
    
ERR
The translation uses Cyrillic script ("&Трансакције") but the locale requests Serbian in ijekavian Latin script. The ampersand is present exactly once (OK). No format specifiers or extra whitespace issues.

Correct translation (Latin script):
&Transakcije
```

<!-- cache_translation_check_sr@ijekavianlatin_99e6638b08ccc04b02c39e8bfff202f3e93faf46512530d616ac572d59680b71 -->
```
        <source>E&amp;xit</source>
        <translation>И&amp;злаз</translation>
    
ERR
The translation is in Cyrillic script ("И&amp;злаз") but the requested variant is Serbian ijekavian Latin. Also ensure the ampersand appears exactly once. 

Correct translation (sr@ijekavianlatin, Latin script):
I&zlaz
```

<!-- cache_translation_check_sr@ijekavianlatin_4391d6c2c7bec48abdb4d541620ff4fe766fde73e8590bd2adceb45640a78c84 -->
```
        <source>&amp;About %1</source>
        <translation>&amp;О %1</translation>
    
ERR
The translation uses Cyrillic "О" (О) but the locale requires Latin script (ijekavian Latin). Also ensure the ampersand shortcut remains exactly once (it does). 

Correct translation:
&amp;O %1
```

<!-- cache_translation_check_sr@ijekavianlatin_727f66a948f1a66d5d6c88df79baff84746ca65f43cc774fce69f4208cea541b -->
```
        <source>Show information about %1</source>
        <translation>Prikaži informacije za otprilike %1</translation>
    
ERR
The translation inaccurately renders "about" as "za otprilike", which means "approximately" rather than indicating information relating to something. The correct translation should render "about" as "o" (meaning "about/regarding").

Correct translation:
Prikaži informacije o %1
```

<!-- cache_translation_check_sr@ijekavianlatin_1fef38dcda8218a74406bb679205042c1589e18d59aa20961e278e6ddf937978 -->
```
        <source>&amp;Send</source>
        <translation>&amp;Пошаљи</translation>
    
ERR
The translation is in Cyrillic (Пошаљи) but the language tag 'sr@ijekavianlatin' requires Latin script. The ampersand is present correctly once and there are no extra spaces.

Correct translation in Serbian (ijekavian, Latin script):
&amp;Pošalji
```

<!-- cache_translation_check_sr@ijekavianlatin_fff5273037a07b7da18ea71a61376e65170d4c4776d8d2610f8acfd3999f0d4c -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation>&amp;Енкриптуј новчаник</translation>
    
ERR
The translation is in Cyrillic script ("Енкриптуј новчаник") but the requested locale is sr@ijekavianlatin (Latin script). Also the source includes an ellipsis (…) which is missing in the translation. The ampersand (&) is present once, which is correct.

Correct translation (Latin, ijekavian):
&Enkriptuj novčanik…

(Alternative more natural wording:
&Šifruj novčanik…)
```

<!-- cache_translation_check_sr@ijekavianlatin_b48dc22dab270ea45cfda861abc3355c61616de9ca2e8ff9bff1a958f802a89f -->
```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>Шифрирај приватни клуљ који припада новчанику.</translation>
    
ERR
The translation uses Cyrillic script. The 'sr@ijekavianlatin' locale requires Latin script (ijekavian variant). Also, "клуљ" appears to be a typographical error; the correct word is "ključeve". Additionally, the verbal form should match the source better.

Correct translation:
Šifriraj privatne ključeve koji pripadaju tvom novčaniku.
```

<!-- cache_translation_check_sr@ijekavianlatin_f11237f7fa112919b8fb5c26758d3d2f3eebab0d7eab6db03f0a9bd51b053129 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>&amp;Резервна копија новчаника</translation>
    
ERR
Translation uses Cyrillic script but the requested locale is Latin (sr@ijekavianlatin). It also omits the trailing ellipsis (…) from the source. The ampersand is present exactly once, which is fine.

Correct translation (Latin, ijekavian) preserving & and ellipsis:
&Rezervna kopija novčanika…
```

<!-- cache_translation_check_sr@ijekavianlatin_db0498fd505b7b99d8f5435bf20656e0d2423847202599f303cdcb18e620b8c8 -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>&amp;Измени приступну фразу</translation>
    
ERR
The translation is in Cyrillic script (Измени приступну фразу) but the requested locale is Serbian ijekavian in Latin script. Also the source contains an ellipsis (…) which is missing in the translation. 

Correct translation (sr@ijekavianlatin):
&Promijeni pristupnu frazu…
```

<!-- cache_translation_check_sr@ijekavianlatin_4b72daf23e278c306a08d5af3792168541fbb18e6efa5b2d53bd2fa477d44c46 -->
```
        <source>Sign &amp;message…</source>
        <translation>Потпиши &amp;поруку</translation>
    
ERR
The translation is in Cyrillic (Потпиши &amp;поруку) but the requested variant is Serbian ijekavian in Latin script. It also misses the trailing ellipsis (…) present in the source.

Correct translation:
Potpiši &poruku…
```

<!-- cache_translation_check_sr@ijekavianlatin_689f9902aaf291b9c3c0d1c5168b7a037fb0168e036a7873aec3145d84f8eb2a -->
```
        <source>&amp;Verify message…</source>
        <translation>&amp;Верификуј поруку</translation>
    
ERR
The translation is in Cyrillic script (Верификуј поруку) but the requested locale is 'sr@ijekavianlatin' (Latin script). Also the source uses an ellipsis (…), which the translation omitted.

Correct translation (Latin, ijekavian), preserving the ampersand and ellipsis:
&Verifikuj poruku…
```

<!-- cache_translation_check_sr@ijekavianlatin_f7ce4465cb80021c706e81004941157e761bb5daf415dc76d95ade967bc048fe -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>&amp;Учитава ”PSBT” из датотеке…</translation>
    
ERR
The translation is in Cyrillic script ("Учитава ”PSBT” из датотеке…") but the locale 'sr@ijekavianlatin' requires Latin script. Also the phrasing is awkward — infinitive/imperative form is more appropriate for a menu action. The ampersand exists exactly once (good), but the smart quotes around PSBT are unnecessary.

Correct translation (Latin, ijekavian) suggestion:
&Učitaj PSBT iz datoteke…
```

<!-- cache_translation_check_sr@ijekavianlatin_f5c174e0275310d002193f453e96288c449bf659654de2dc7cc0292fd16c5347 -->
```
        <source>Open &amp;URI…</source>
        <translation>Отвори &amp;URI</translation>
    
ERR
The translation uses Cyrillic script ("Отвори &amp;URI") but the requested locale 'sr@ijekavianlatin' requires Latin script. It also omits the trailing ellipsis character (…) present in the source. The ampersand is present exactly once, which is fine.

Correct translation (Serbian ijekavian, Latin script) should be:
Otvori &URI…
```

<!-- cache_translation_check_sr@ijekavianlatin_dc1287ae9a059bb8080e6444ca9dd869061ae29883e9589e070635f73386c478 -->
```
        <source>&amp;Settings</source>
        <translation>&amp;Подешавања</translation>
    
ERR
The translation uses Cyrillic script ("&Подешавања") but the language tag requests ijekavian Latin script. Use the Latin form instead.

Correct translation:
&amp;Podešavanja
```

<!-- cache_translation_check_sr@ijekavianlatin_7330469a734f823d0ef20ee2490cfc2a735609fcec322d47345fce871f53969d -->
```
        <source>&amp;Help</source>
        <translation>&amp;Помоћ</translation>
    
ERR
The translation is in Cyrillic script ("&Помоћ") but the target variant 'sr@ijekavianlatin' requires Serbian in Latin script. Also ensure the single ampersand is preserved.

Correct translation:
& Pomoć should not have a space after & — use:
&Pomoć
```

<!-- cache_translation_check_sr@ijekavianlatin_d8c899531278707a06a7dd7985fabbefa82aacce8902cb483702e524001c3195 -->
```
        <source>Connecting to peers…</source>
        <translation>Повезивање са клијентима...</translation>
    
ERR
The translation uses Cyrillic script (Повезивање са клијентима...), whereas 'sr@ijekavianlatin' specifies Latin script. Additionally, "peers" should be translated as "čvorovima" or "peerima" in the Bitcoin context, not 'klijentima'.

Correct translation:
Povezivanje sa čvorovima…
```

<!-- cache_translation_check_sr@ijekavianlatin_986c1bb9e9f803edbe176beff96d002d37299fdb4b4c4febb5404a18a8cb4bc8 -->
```
        <source>&amp;Command-line options</source>
        <translation>&amp;Опције командне линије</translation>
    
ERR
The translation is in Serbian Cyrillic ("Опције командне линије") but the target locale 'sr@ijekavianlatin' requires Serbian in Latin script. The ampersand (&) is present and there are no format specifiers or whitespace issues.

Correct translation (Latin script):
&Opcije komandne linije
```

<!-- cache_translation_check_sr@ijekavianlatin_d8fcd325544250661ba66f9dcff88d01533d58e3bbff8e4e6b9e68d16c72d496 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>Учитај ”PSBT” из привремене меморије</translation>
    
ERR
The translation is in Cyrillic rather than the requested Serbian ijekavian Latin script, it omits the required '&' accelerator marker, and it uses curly quotes around PSBT. Also "privremene memorije" is acceptable but "međuspremnika" is more natural for "clipboard". 

Correct translation (sr@ijekavianlatin):
Učitaj PSBT iz &međuspremnika…
```

<!-- cache_translation_check_sr@ijekavianlatin_cea5ee2b8886d5a15badf5ba178a5b8271852de2ef25ac953230cec24b38bbe2 -->
```
        <source>Open node debugging and diagnostic console</source>
        <translation>Отвори конзолу за ноде дебуг и дијагностику</translation>
    
ERR
The translation uses Cyrillic script (Отвори...), while 'sr@ijekavianlatin' requires Latin script. Additionally, "node debugging" and "diagnostic" are better translated as "debugovanje čvora" and "dijagnostiku" to match common terminology.

Correct translation:
Otvori konzolu za debugovanje čvora i dijagnostiku
```

<!-- cache_translation_check_sr@ijekavianlatin_3905110758e709940c6bf294d8b0adf75bd39b2557abcacd7751f2bfdff8b150 -->
```
        <source>&amp;Sending addresses</source>
        <translation>&amp;Адресе за слање</translation>
    
ERR
Translation is in Cyrillic script, but the target variant 'sr@ijekavianlatin' requires Serbian in Latin script. The meaning is correct and the ampersand is present once, but script is wrong.

Correct translation (Latin script, ijekavian):
&Adrese za slanje
```

<!-- cache_translation_check_sr@ijekavianlatin_2358560d71e79cd9c9d3c9cccccefd3086af8c200b55d7d59c55ec33dd320118 -->
```
        <source>&amp;Receiving addresses</source>
        <translation>&amp;Адресе за примање</translation>
    
ERR
Translation uses Cyrillic script ("Адресе за примање") but the requested locale 'sr@ijekavianlatin' requires Latin script. The ampersand (shortcut) is present, but the script mismatch makes it incorrect.

Correct translation (Latin script, ijekavian):
&Adrese za primanje
```

<!-- cache_translation_check_sr@ijekavianlatin_c67bf84687657800de4d524aeae5824485e6547ac73232330c0f201980fdd07b -->
```
        <source>Open a bitcoin: URI</source>
        <translation>Отвори биткоин: URI</translation>
    
ERR
The translation is in Cyrillic script, while 'sr@ijekavianlatin' requires Latin script with Ijekavian pronunciation.

Correct translation:
Otvori bitcoin: URI
```

<!-- cache_translation_check_sr@ijekavianlatin_ca252f4a695e0e82bfa34c7837e51535e7f7701dca74658ebdbbfff1f76a4a93 -->
```
        <source>Restore Wallet…</source>
        <extracomment>Name of the menu item that restores wallet from a backup file.</extracomment>
        <translation>Поврати новчаник...</translation>
    
ERR
The translation is provided in Serbian Cyrillic script, whereas 'sr@ijekavianlatin' requires Serbian in Ijekavian dialect using the Latin script. Also, the ellipsis should be three dots or correct ellipsis character, but the main issue is the script.

Correct translation:
Povrati novčanik…
```

<!-- cache_translation_check_sr@ijekavianlatin_d9586b7cde22f3976d48a8a3bd8c0eb837ef3bade1bcbf28c8f1be1711db360a -->
```
        <source>&amp;Mask values</source>
        <translation>&amp;Маскирај вредности</translation>
    
ERR
The translation is in Serbian Cyrillic ("Маскирај вредности") but the requested locale is 'sr@ijekavianlatin' (Serbian ijekavian in Latin script). Also, the ijekavian form of "vrednosti" should be "vrijednosti".

Correct translation (Latin, ijekavian):
&Maskiraj vrijednosti
```

<!-- cache_translation_check_sr@ijekavianlatin_a3dba58f5094f427ac2079a40552e322da8888a4a696a21d03601386ba277c9b -->
```
        <source>&amp;Window</source>
        <translation>&amp;Прозор</translation>
    
ERR
The translation is in Cyrillic (Прозор) but the requested locale is 'sr@ijekavianlatin' which requires the Latin script. The meaning is correct, but the script is wrong.

Correct translation:
&Prozor
```

<!-- cache_translation_check_sr@ijekavianlatin_e325bae3e6fa76ee26217d109c2191d6a348d9aee95535abe58e8680bbbf849a -->
```
        <source>S&amp;how</source>
        <translation>&amp;Прикажи</translation>
    
ERR
The translation is in Serbian Cyrillic ("Прикажи"), but the locale requests ijekavian Latin script. Also ensure the shortcut marker (&) is preserved exactly once.

Correct translation (Latin ijekavian):
&lt;translation&gt;&amp;Prikaži&lt;/translation&gt;
```

<!-- cache_translation_check_sr@ijekavianlatin_ed93ef579617dc434f9d57fbac92c52d5abb24f652a0ead56dcc244fd5a5e7c8 -->
```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Новчаник јс &lt;b&gt;шифриран&lt;/b&gt; и тренутно &lt;b&gt;откључан&lt;/b&gt;</translation>
    
ERR
The translation uses Cyrillic script instead of Latin, which is required by 'sr@ijekavianlatin'. Also, there is a typo: "јс" should be "je".

Correct translation:
Novčanik je &lt;b&gt;šifriran&lt;/b&gt; i trenutno &lt;b&gt;otključan&lt;/b&gt;
```

<!-- cache_translation_check_sr@ijekavianlatin_ec625a931b16cd72c005bdcac9183eecbdaa41351aaeaf4ee819ee92d88078d6 -->
```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Новчаник јс &lt;b&gt;шифрован&lt;/b&gt; и тренутно &lt;b&gt;закључан&lt;/b&gt;</translation>
    
ERR
The translation contains a typo: "јс" instead of "je" (is). Also, the translation is in Cyrillic script, but 'sr@ijekavianlatin' requires Latin script (ijekavian variant). The correct translation in Latin script is:

Novčanik je <b>šifrovan</b> i trenutno <b>zaključan</b>
```

<!-- cache_translation_check_sr@ijekavianlatin_fbe14f9d171f57a0d3d892c2e1728b973f15b6e83f6dedb85f9433ec4150dc81 -->
```
        <source>Coin Selection</source>
        <translation>Избор новчића</translation>
    
ERR
The translation uses Cyrillic script ("Избор новчића") instead of Latin script as required for 'sr@ijekavianlatin'. The content itself is correct, but the script is not.

Correct translation:
Izbor novčića
```

<!-- cache_translation_check_sr@ijekavianlatin_8222a858873ec13c5df7e9a946592a36bf3eb8671dad9a25599b24410f0c2ebb -->
```
        <source>&amp;Copy address</source>
        <translation>&amp;Копирај адресу</translation>
    
ERR
The translation uses Cyrillic script ("Копирај адресу") but the requested locale 'sr@ijekavianlatin' requires Latin script. The ampersand for the shortcut is present exactly once, which is correct.

Correct translation (Latin, ijekavian):
&amp;Kopiraj adresu
```

<!-- cache_translation_check_sr@ijekavianlatin_d3c67ee6f7daa4d5ec3f613ccf586301db99122f3390c8488657d75dbb5c4432 -->
```
        <source>Copy &amp;label</source>
        <translation>Копирај &amp;означи</translation>
    
ERR
Problems:
- The translation is in Cyrillic (Копирај &amp;означи) but the target requested is sr@ijekavianlatin (Latin script).
- The verb/noun choice is wrong: "означи" means "mark" (imperative), not "label" (noun). The case is also incorrect for "copy the label".

Correct translation (sr@ijekavianlatin, with single &):
Kopiraj &oznaku
```

<!-- cache_translation_check_sr@ijekavianlatin_638ac814c9d49f25c1043de13c925c3b5f2c583035e53e743a5bbbdb53b0f1bf -->
```
        <source>Copy &amp;amount</source>
        <translation>Копирај &amp;износ</translation>
    
ERR
The translation uses Cyrillic script ("Копирај &износ") but the requested locale is Serbian ijekavian Latin; it should be in Latin script. The ampersand/HTML entity is present and placed correctly, but the script is wrong.

Correct translation:
<translation>Kopiraj &amp;iznos</translation>
```

<!-- cache_translation_check_sr@ijekavianlatin_4976c57c852456d2428e3c8dd6019732c4fa415d80d052627d4b252a3adb4504 -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>Kopiraj transakciju &amp;ID i izlazni index</translation>
    
ERR
Problems:
- Uses English "index" instead of Serbian "indeks".
- Word order is unnatural: "transakciju ID" should be "ID transakcije" (genitive).
- The & shortcut exists, which is fine, but ensure it's placed consistently; it's okay before "ID".

Correct translation:
Kopiraj &ID transakcije i izlazni indeks
```

<!-- cache_translation_check_sr@ijekavianlatin_0e3a2093f7a81f0eb8be8107ee3cd0e220d482f571a1f346de0aab09f9507d17 -->
```
        <source>L&amp;ock unspent</source>
        <translation>Закључај непотрошено</translation>
    
ERR
The translation is problematic:
- It's in Cyrillic script ("Закључај непотрошено") but the target locale requests Serbian ijekavian in Latin script.
- The ampersand (&) marking the shortcut key from the source is missing; the source has one (&) and the translation must include exactly one.
- Minor wording: prefer Latin-script ijekavian form.

Correct translation (Latin, with one & for shortcut):
Zaklju&čaj nepotrošeno
```

<!-- cache_translation_check_sr@ijekavianlatin_f28249d0c3e5b5f1afdeb988a8cca49aa674f8948e82f1a3507e5b067cb3a74a -->
```
        <source>&amp;Unlock unspent</source>
        <translation>Откључај непотрошено</translation>
    
ERR
Problems:
- The translation is in Cyrillic (Откључај непотрошено) but target language variant requests Latin script (sr@ijekavianlatin).
- The ampersand (&) indicating the shortcut is missing — the source has one and the translation must include it exactly once.
- Minor grammatical nuance: "nepotrošeno" (singular) is less natural than plural "nepotrošene" for "unspent (outputs)".

Suggested correct translation (Latin script, ijekavian-style, with single &):
&Otključaj nepotrošene
```

<!-- cache_translation_check_sr@ijekavianlatin_09ce78b389e3b5f61856d9688d39746baedede47729e42ff8311a998473e30cc -->
```
        <source>change from %1 (%2)</source>
        <translation>Измени од %1 (%2)</translation>
    
ERR
The translation uses Cyrillic script, which is not appropriate for 'sr@ijekavianlatin' (Serbian, Ijekavian, Latin script). It should be in Latin script.

Correct translation:
Izmijeni od %1 (%2)
```

<!-- cache_translation_check_sr@ijekavianlatin_1a8401c404fa25fde86f25f360bc7ac471ac4dbb8a2fd57bd5ea5ff6fb9cbab1 -->
```
        <source>Creating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the create wallet progress window which indicates to the user which wallet is currently being created.</extracomment>
        <translation>Креирање новчаника &lt;b&gt;%1&lt;/b&gt;…</translation>
    
ERR
The translation is correct Serbian wording but uses Cyrillic script. The requested locale 'sr@ijekavianlatin' requires Latin script. Also ensure %1 and HTML tags are preserved (they are).

Correct translation:
Kreiranje novčanika &lt;b&gt;%1&lt;/b&gt;…
```

<!-- cache_translation_check_sr@ijekavianlatin_99505440570a1684db35109575c7f69460952f2c22e032d1c62b881db24be233 -->
```
        <source>Create wallet warning</source>
        <translation>Направи упозорење за новчаник</translation>
    
ERR
The translation is incorrect for several reasons:
1. It is written in Cyrillic script, whereas 'sr@ijekavianlatin' requires the Latin script.
2. The phrase is mistranslated: "Create wallet warning" means a warning message about wallet creation, not an instruction to "create a warning for the wallet".
3. Correct translation into 'sr@ijekavianlatin' (Latin script, ijekavian dialect) would be:
Kreiraj upozorenje za novčanik

However, the best context-appropriate translation is:
Upozorenje pri kreiranju novčanika

So, correct translation:
Upozorenje pri kreiranju novčanika
```

<!-- cache_translation_check_sr@ijekavianlatin_e24d072e432327a2e5cb7899dad8b695bef3114e66e80c8ac08a7757cbd029fa -->
```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>Da li si siuran da želiš da preneseš novčanik &lt;i&gt;%1&lt;/i&gt;? </translation>
    
ERR
There is a typo in the word "siuran" which should be "siguran" in Ijekavian Latin. There is also a stray space character at the end of the translation.

Correct translation:
Da li si siguran da želiš da preneseš novčanik &lt;i&gt;%1&lt;/i&gt;?
```

<!-- cache_translation_check_sr@ijekavianlatin_e30ba362aab39a95655ce8c4a9abb481c5214d1b5638fa6a286941d3b67fa1d1 -->
```
        <source>Opening Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the open wallet progress window which indicates to the user which wallet is currently being opened.</extracomment>
        <translation>Отвањаре новчаника &lt;b&gt;%1&lt;/b&gt;</translation>
    
ERR
The translation uses Cyrillic script, but 'sr@ijekavianlatin' requires Ijekavian in Latin script. Additionally, the ellipsis ("…") at the end is omitted. There are also minor spelling issues: "Otvaranje" is the correct form in Latin script.

Correct translation:
Otvaranje novčanika <b>%1</b>…
```

<!-- cache_translation_check_sr@ijekavianlatin_4ade59cd6c85c3068d362f387d32e1956204783d7409eaa37e7a6656f76ababd -->
```
        <source>&amp;Label</source>
        <translation>&amp;Ознака</translation>
    
ERR
The translation uses Cyrillic script ("Ознака") but the language variant 'sr@ijekavianlatin' requires Latin script. Also ampersand is present, which is correct, but the script mismatch makes this incorrect.

Correct translation:
&amp;Oznaka
```

<!-- cache_translation_check_sr@ijekavianlatin_b672f5ba2b64ff78db7540fb7f5560bc304997f67f8e1129d638d8250e93c582 -->
```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>Адреса повезана са овом ставком из листе адреса. Ово можете променити једини у случају адреса за плаћање.</translation>
    
ERR
There are several problems:
1. The translation uses Cyrillic letters, but 'sr@ijekavianlatin' should be in Latin script.
2. There is a lexical error: "једини" should be "једино" (or, in Latin, "jedino").
3. The intended translation should use "adresa" and "lista", not their Cyrillic counterparts.

Correct translation:
Adresa povezana sa ovom stavkom iz liste adresa. Ovo možete promijeniti jedino u slučaju adresa za slanje.
```

<!-- cache_translation_check_sr@ijekavianlatin_74c3ea811d3fc3e0a76d3dbeff932c9be711d99e81831c6319683b1479c1fa2f -->
```
        <source>Edit sending address</source>
        <translation>Измени адресу за слање</translation>
    
SPAM
The translation is in Serbian Cyrillic script, but 'sr@ijekavianlatin' requires Serbian in Latin script (Ijekavian). 

Correct translation:
Izmijeni adresu za slanje
```

<!-- cache_translation_check_sr@ijekavianlatin_4e606be4ad192cfcfb287e18927dd2373210756bef7ab4aa5ba2d6dd766f83e5 -->
```
        <source>Path already exists, and is not a directory.</source>
        <translation>Путања већ постоји и није директоријум.</translation>
    
ERR
The translation is in Serbian Cyrillic script, but 'sr@ijekavianlatin' specifies the Ijekavian Latin script. The script should be Latin, not Cyrillic.

Correct translation:
Putanja već postoji i nije direktorijum.
```

<!-- cache_translation_check_sr@ijekavianlatin_323efa2061f0ced599293d07ad46ba27961e5c6c4f8e3f658c71b81bcb433743 -->
```
        <source>Limit block chain storage to</source>
        <translation>Ограничите складиштење блок ланца на</translation>
    
SPAM
The translation is in Serbian Cyrillic script, not 'sr@ijekavianlatin' (Serbian Ijekavian Latin). The correct translation should be in Latin script.

Correct translation:
Ograničite skladištenje blok lanca na
```

<!-- cache_translation_check_sr@ijekavianlatin_e0d3b5109cb2d7193590368f17f07152dded2395f9b686fff60399a9c5a0d3a7 -->
```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Најмање %1 GB подататака биће складиштен у овај директорјиум који ће временом порасти.</translation>
    
ERR
The translation uses Cyrillic script, but 'sr@ijekavianlatin' requires Latin script. There are also minor spelling issues ("подататака" should be "podataka"; "директорјиум" should be "direktorijum"). Additionally, some word choices can be improved for naturalness.

Correct translation:
Najmanje %1 GB podataka biće sačuvano u ovom direktorijumu, i on će vremenom rasti.
```

<!-- cache_translation_check_sr@ijekavianlatin_6e8ec9aa0b8539fe8f2768e3135f1b544e97b494891f9e190dc6898c49593f4c -->
```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Најмање %1 GB подататака биће складиштен у овај директорјиум.</translation>
    
ERR
The translation is in Serbian Cyrillic, not in Ijekavian Latin script as required by 'sr@ijekavianlatin'. There are also some spelling issues:
- "подататака" should be "podataka"
- "директорјиум" should be "direktorijum"
- "Најмање" means "at least", but "Approximately" should be "Otprilike" or "Približno"

Correct translation:
Otprilike %1 GB podataka će biti uskladišteno u ovom direktorijumu.
```

<!-- cache_translation_check_sr@ijekavianlatin_4c58c494cbe87108e861c5e59fee14a96a60ea89ccc6bd6f92530d8218c27532 -->
```
        <source>%1 will download and store a copy of the Bitcoin block chain.</source>
        <translation>%1 биће преузеће и складиштити копију Биткоин ланца блокова.</translation>
    
ERR
The translation is grammatically incorrect in Serbian. The construction "биће преузеће и складиштити" is a faulty use of tenses and aspect; "биће" (will be) and "преузеће" (will download) redundantly mix future tense auxiliaries, resulting in a nonsensical phrase.

Correct translation:
%1 će preuzeti i sačuvati kopiju Bitcoin lanca blokova.
```

<!-- cache_translation_check_sr@ijekavianlatin_f2a89d713f9f8eecce461706901717f83b19045b58ee4d030c64a8faa01b9fd2 -->
```
        <source>Error: Specified data directory "%1" cannot be created.</source>
        <translation>Грешка: Одабрана датотека  "%1" не може бити креирана.</translation>
    
ERR
There are two issues:
1. The translation uses Cyrillic script (Грешка...), but 'sr@ijekavianlatin' requires Latin script.
2. 'data directory' is translated as 'датотека' (file), which is incorrect; it should be 'direktorij' or 'direktorijum' (directory).
3. There are double spaces before "%1".

Correct translation:
Greška: Navedeni direktorijum "%1" ne može biti kreiran.
```

<!-- cache_translation_check_sr@ijekavianlatin_e7e51108739259f607536c5948e992bddffb9c0daffcd0212dd411a2ab5dbae2 -->
```
        <source>Last block time</source>
        <translation>Време последњег блока</translation>
    
ERR
The translation is written in Serbian Cyrillic script, but 'sr@ijekavianlatin' specifies Serbian in the Latin script with the Ijekavian accent. The correct translation should use Latin characters and the Ijekavian variant.

Correct translation:
Vrijeme posljednjeg bloka
```

<!-- cache_translation_check_sr@ijekavianlatin_900c39e2a27e53fd09cf2851c4333f16aea74193323c46dd13b9515a759cc5db -->
```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Налепите адресу из базе за копирање</translation>
    
ERR
The provided translation is in Cyrillic script, but 'sr@ijekavianlatin' should use Latin script. Also, "база за копирање" is not the standard way to say "clipboard"; the correct term is "privremena memorija" or simply "clipboard" used in technical contexts.

Correct translation:
Nalijepite adresu iz privremene memorije
```

<!-- cache_translation_check_sr@ijekavianlatin_2e5552db7c9227a626eed1a9be537345e49294d1a0aa129317b27378a6284845 -->
```
        <source>&amp;Main</source>
        <translation>&amp;Главни</translation>
    
ERR
The translation is in Cyrillic ("&Главни") but the requested locale specifies Serbian in Latin script (sr@ijekavianlatin). Use Latin script. Also ensure the ampersand is present exactly once (it is).

Correct translation:
&amp;Glavni
```

<!-- cache_translation_check_sr@ijekavianlatin_f6e624df16dcbd583e2a5cbbd638a8d58c12502f214525e8de5b2ed07e846457 -->
```
        <source>Automatically start %1 after logging in to the system.</source>
        <translation>Аутоматски почети %1 након пријање на систем.</translation>
    
ERR
There are several issues:
1. The translation uses Cyrillic script, but 'sr@ijekavianlatin' should use Latin script.
2. There is a typo: "пријање" should be "prijavljivanja" (from "login").
3. The word order and phrasing are awkward.

Correct translation:
Automatski pokreni %1 nakon prijavljivanja na sistem.
```

<!-- cache_translation_check_sr@ijekavianlatin_8a1c014ffbd9439216859338e77205dd1231c418d1ebeae73ad2fcb70710d6ae -->
```
        <source>&amp;Start %1 on system login</source>
        <translation>&amp;Покрени %1 приликом пријаве на систем</translation>
    
ERR
The translation is in Serbian Cyrillic, but the requested locale is Serbian ijekavian Latin. Also ensure the ampersand is present exactly once and the %1 placeholder is preserved.

Correct translation (sr@ijekavianlatin):
&Pokreni %1 prilikom prijave na sistem
```

<!-- cache_translation_check_sr@ijekavianlatin_6c2e6271f15953db62c464454a57235efecc5c15f1f70df0f453cae06add0d8b -->
```
        <source>Size of &amp;database cache</source>
        <translation>Величина кеша базе података</translation>
    
ERR
The translation is in Serbian Cyrillic ("Величина кеша базе података") but the target locale requests Serbian ijekavian in Latin script. Also the source contains an accelerator marker (&) for "database" which must appear exactly once in the translation; the provided translation has no &.

Correct translation (sr@ijekavianlatin), with the & placed on "baze" to mirror the source accelerator:
Veličina keša &baze podataka
```

<!-- cache_translation_check_sr@ijekavianlatin_4a607db8c92fdfba8d7090eca4db9848cd71ec535445ae2f8ddad7a83c07c5ad -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>Број скрипти и CPU за верификацију</translation>
    
ERR
- Translation is problematic: it's in Cyrillic rather than Latin script, changes meaning (adds "CPU" and uses "и" instead of the shortcut ampersand), and doesn't preserve the single & shortcut indicator.
- No format specifiers present in source, but the & must appear exactly once in the translation.

Correct translation (sr@ijekavianlatin, Latin script) example:
Broj &niti za verifikaciju skripti
```

<!-- cache_translation_check_sr@ijekavianlatin_bed8f81c88c55e0761966617cba9308895643eeee3ca644a5ddb9d6b4b710345 -->
```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Приказује се ако је испоручени уобичајени SOCKS5 проxy коришћен ради проналажења клијената преко овог типа мреже. </translation>
    
ERR
There are several issues:
1. The translation uses Cyrillic script, but 'sr@ijekavianlatin' should be in Latin script.
2. The word "проxy" is a mix of Cyrillic and Latin; it should be "proxy" in Latin.
3. "prikazuje se" should be "Prikazuje" for proper sentence structure.
4. "клијената" means "clients"; "peer" in the Bitcoin context is better translated as "čvorova" or "peerova".
5. There is an unnecessary space at the end of the translation.

Correct translation:
Prikazuje da li se isporučeni podrazumijevani SOCKS5 proxy koristi za pristup peerovima putem ove vrste mreže.
```

<!-- cache_translation_check_sr@ijekavianlatin_f683a00255e2e608027d72bf7ce6cfbc769d1da25381b71f31824e981b8a3afd -->
```
        <source>Open the %1 configuration file from the working directory.</source>
        <translation>Отвори  %1 конфигурациони фајл из директоријума у употреби.</translation>
    
ERR
The translation uses Cyrillic script ("Отвори конфигурациони фајл из директоријума у употреби.") instead of ijekavian Latin, which is required for 'sr@ijekavianlatin'. Additionally, there is an extra space after "Отвори".

Correct translation:
Otvori %1 konfiguracioni fajl iz direktorijuma u upotrebi.
```

<!-- cache_translation_check_sr@ijekavianlatin_d693e0ad3eaa0c151f558614340d015b1c6c481884988075b09e66fc886a489d -->
```
        <source>&amp;Reset Options</source>
        <translation>&amp;Ресет Опције</translation>
    
ERR
Translation uses Cyrillic script ("Ресет Опције") but the target locale requires Latin script (ijekavian Latin). Also the phrase is better translated into natural Serbian.

Correct translation:
&amp;Resetuj opcije

(Alternative ijekavian wording: &amp;Poništi opcije)
```

<!-- cache_translation_check_sr@ijekavianlatin_8989ea55ca4dff4a10b0f3383fb02ce15697ab38d2a94f7c6ff58e6a51fc4fa2 -->
```
        <source>&amp;Network</source>
        <translation>&amp;Мрежа</translation>
    
ERR
The translation uses Cyrillic script ("Мрежа") but the locale requests Serbian Ijekavian in Latin script. Also ensure the ampersand (shortcut) remains exactly once — it is present, which is fine.

Correct translation:
&amp;Mreža
```

<!-- cache_translation_check_sr@ijekavianlatin_7f41849d827d608340c098c4f9b8a465587eee6dac06996db83d4fddcdc5a8a4 -->
```
        <source>Prune &amp;block storage to</source>
        <translation>Сакрати &amp;block складиштење на</translation>
    
ERR
The translation is problematic: it's in Cyrillic script (should be Latin for 'sr@ijekavianlatin'), and it leaves the English word "block" instead of translating it. Also word order and choice should match natural Serbian ijekavian Latin.

Correct translation:
Skratiti &skladištenje blokova na
```

<!-- cache_translation_check_sr@ijekavianlatin_74677d4ac1ee4dc7fcf0c115c25106213a635c6c27c9bb213bae4cb0082fa90f -->
```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Враћање ове опције захтева да поновно преузимање целокупонг блокчејна.</translation>
    
ERR
The translation uses Cyrillic script, while 'sr@ijekavianlatin' requires Latin script. Also, there is a grammatical issue: "поновно преузимање" should be "поновно преузимање" or "da ponovo preuzmete". "целокупонг" is a misspelling; it should be "cijelog".

Correct translation:
Vraćanje ove opcije zahtijeva ponovno preuzimanje cijelog blokčejna.
```

<!-- cache_translation_check_sr@ijekavianlatin_28e8a887e7f6397591b7528074c24c70edaad3858c4106b797e70b581323c5ef -->
```
        <source>W&amp;allet</source>
        <translation>Н&amp;овчаник</translation>
    
ERR
The translation is in Serbian Cyrillic (Н&amp;овчаник) but the requested locale is Serbian Ijekavian Latin (sr@ijekavianlatin). Also ensure the ampersand exists exactly once and use Latin script.

Correct translation (Latin script), preserving one ampersand:
N&ovčanik
```

<!-- cache_translation_check_sr@ijekavianlatin_1ab27e36c8536348eb7c3420a8479d51fc27cce7f84584967da69cb1aaa6008f -->
```
        <source>Enable coin &amp;control features</source>
        <translation>Омогући опцију контроле новчића</translation>
    
ERR
The translation is in Cyrillic script and does not include the & accelerator. The target locale requests ijekavian Latin script and the & must be present exactly once.

Correct translation (sr@ijekavianlatin):
Omogući funkcije &kontrole novčića
```

<!-- cache_translation_check_sr@ijekavianlatin_bf34ccfc39bd144359a77cfe12e64a886fbe72dd7ab4003c76462a81e4285492 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>&amp;Троши непотврђени кусур</translation>
    
ERR
The translation is in Cyrillic script (Српска/ћирилица), but the requested variant is Serbian ijekavian Latin. Also ensure the ampersand is preserved exactly once — it is present, but the script must be Latin.

Correct translation (sr@ijekavianlatin):
&Troši nepotvrđeni kusur
```

<!-- cache_translation_check_sr@ijekavianlatin_196c911250d4690910aff542514bded95b961fb11f31b283845d8afbf7152a3a -->
```
        <source>&amp;External signer script path</source>
        <translation>&amp;Путања скрипте спољног потписника</translation>
    
ERR
The translation is in Cyrillic script (Путања скрипте спољног потписника) but the requested locale 'sr@ijekavianlatin' requires Serbian in ijekavian Latin script. The ampersand is present once and the meaning is correct, but the script is wrong.

Correct translation in ijekavian Latin:
&Putanja skripte spoljnog potpisnika
```

<!-- cache_translation_check_sr@ijekavianlatin_6ef8e317e053328bbe6291c14c4e93aef0637ae91b01c35fe835884d7ab0ddb8 -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Дозволи долазеће конекције.</translation>
    
ERR
The translation is in Serbian Cyrillic, but the requested locale uses Latin script (sr@ijekavianlatin). It also lacks the required single ampersand (&) for the shortcut and has an unnecessary trailing period. No format specifiers are present in the source.

Correct translation (Latin, ijekavian, with one & for the accelerator):
D&ozvoli dolazeće konekcije
```

<!-- cache_translation_check_sr@ijekavianlatin_3e1c31380edd8079c4b6f046c1f44bfe3cb4013aa454c18cdbbba954e75326af -->
```
        <source>Connect to the Bitcoin network through a SOCKS5 proxy.</source>
        <translation>Конектуј се на Биткоин мрежу кроз SOCKS5 проксијем.</translation>
    
ERR
The translation uses Cyrillic script instead of the Latin script required for 'sr@ijekavianlatin'. It also uses "Конектуј се", which is more of a direct transliteration from English than a standard term in Serbian, and "проксијем" is in instrumental case when it should match the preposition. It would be better to use "Poveži se na Bitcoin mrežu putem SOCKS5 proksija."

Correct translation:
Poveži se na Bitcoin mrežu putem SOCKS5 proksija.
```

<!-- cache_translation_check_sr@ijekavianlatin_9b7e5978450412193556bc34436fe8a0eed34d388df75bd97caba09b39c01fa7 -->
```
        <source>&amp;Connect through SOCKS5 proxy (default proxy):</source>
        <translation>&amp;Конектуј се кроз SOCKS5 прокси (уобичајени прокси):</translation>
    
ERR
The translation is in Serbian Cyrillic, while the requested locale 'sr@ijekavianlatin' expects Latin script (ijekavian). Also adjust wording to natural Serbian ijekavian Latin.

Correct translation:
&Poveži se kroz SOCKS5 proxy (podrazumijevani proxy):
```

<!-- cache_translation_check_sr@ijekavianlatin_d53c2ee93761fe6e40503cfc663855de4b05a29f59773ba38b65acbe6084a214 -->
```
        <source>Proxy &amp;IP:</source>
        <translation>Прокси &amp;IP:</translation>
    
ERR
The translation is in Cyrillic script ("Прокси &IP:") but the target variant requests Serbian ijekavian in Latin script. No format specifiers present; the ampersand is correct. Provide a Latin-script translation.

Correct translation:
Proksi &IP:
```

<!-- cache_translation_check_sr@ijekavianlatin_42c29c9d25e766b1f2f83649bbd1c55870893df8d6f66506b5e7fb354a146a2f -->
```
        <source>&amp;Port:</source>
        <translation>&amp;Порт:</translation>
    
ERR
The translation uses Cyrillic script ("&Порт:") but the requested locale is Serbian ijekavian in Latin script. No format specifiers or whitespace issues, and the ampersand is present exactly once, but the script is wrong.

Correct translation (Latin script):
&amp;Port:
```

<!-- cache_translation_check_sr@ijekavianlatin_a3dba58f5094f427ac2079a40552e322da8888a4a696a21d03601386ba277c9b -->
```
        <source>&amp;Window</source>
        <translation>&amp;Прозор</translation>
    
ERR
The translation is in Cyrillic (Прозор) but the requested locale is 'sr@ijekavianlatin' which requires the Latin script. The meaning is correct, but the script is wrong.

Correct translation:
&Prozor
```

<!-- cache_translation_check_sr@ijekavianlatin_5d4e98bed523794526aeb80e812728b98ef6162ec2742137832b0c66d55ea751 -->
```
        <source>&amp;Show tray icon</source>
        <translation>&amp;Прикажи икону у траци</translation>
    
ERR
The translation is in Serbian Cyrillic ("Прикажи икону у траци") but the requested locale is Serbian ijekavian Latin. The ampersand is present and format/spacing is fine otherwise, but the script is wrong.

Correct translation (Latin script, ijekavian):
&Prikaži ikonu na traci
```

<!-- cache_translation_check_sr@ijekavianlatin_b748b2b1a00e41e8836275f6b45880a1c456e64c02adbb59dedd7b230c7fbb0e -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>&amp;минимизирај у доњу линију, уместо у програмску траку</translation>
    
ERR
Translation uses Cyrillic script but target language tag requests Latin (sr@ijekavianlatin). The wording is also a bit awkward: "доњу линију" ("bottom line") is incorrect for "tray" (system tray). The & shortcut exists but must be kept in Latin text.

Correct translation (Latin, ijekavian):
&Minimiziraj u područje za obavještenja umjesto na traku zadataka
```

<!-- cache_translation_check_sr@ijekavianlatin_71f2b0363d4d3ec75f8848720b5326054f7c475404f87da0f73693af7e67b949 -->
```
        <source>M&amp;inimize on close</source>
        <translation>Минимизирај при затварању</translation>
    
ERR
Translation problems:
- The target variant 'sr@ijekavianlatin' requires Latin script, but the translation is in Cyrillic.
- The mnemonic ampersand (&) from the source is missing; it must appear exactly once in the translation.
- Minor style: use ijekavian Latin form.

Correct translation (Latin, with single &):
M&inimiziraj pri zatvaranju
```

<!-- cache_translation_check_sr@ijekavianlatin_11ddd93ea01269724a5c5cdf5e1cf181698ea34c5128c5d5dc696baeadc1a141 -->
```
        <source>&amp;Display</source>
        <translation>&amp;Прикажи</translation>
    
ERR
The translation is in Cyrillic script ("Прикажи") but the language variant requests Serbian ijekavian in Latin script. Also the ampersand is present (good) but the word should be in Latin: use "Prikaži" with š.

Correct translation:
&amp;Prikaži
```

<!-- cache_translation_check_sr@ijekavianlatin_104f40c6ab5d55c7767c19c21b3ebb50071984cb4cb5a931f596eea2165097bd -->
```
        <source>User Interface &amp;language:</source>
        <translation>&amp;Језик корисничког интерфејса:</translation>
    
ERR
The translation is in Cyrillic (Језик корисничког интерфејса) but the requested locale is Serbian ijekavian Latin. Also ensure the shortcut ampersand appears once. 

Correct translation (sr@ijekavianlatin):
<translation>&amp;Jezik korisničkog interfejsa:</translation>
```

<!-- cache_translation_check_sr@ijekavianlatin_a14a87c1f402e572b8bbdb509713a00e4a40d278b796f65ad9b74d2ff40ba38d -->
```
        <source>&amp;Unit to show amounts in:</source>
        <translation>&amp;Јединица за приказивање износа:</translation>
    
ERR
The translation is in Serbian Cyrillic rather than the requested sr@ijekavianlatin (Latin script). No format specifiers to worry about and the & is present exactly once, but the script is wrong.

Correct translation (Latin, ijekavian):
&amp;Jedinica za prikazivanje iznosa:
```

<!-- cache_translation_check_sr@ijekavianlatin_54d86df503dd736bd5cda8ec5c6cd93126f1bddd3395cfcfce32c9c6c7a0520b -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Користите посебан СОЦКС&amp;5 прокси да бисте дошли до вршњака преко услуга Тор онион:</translation>
    
ERR
Translation uses Cyrillic script (the target locale requests Serbian in ijekavian Latin), and should be in Latin. Otherwise wording is acceptable but script and possibly "proxy" transliteration should match locale. The & accelerator must appear exactly once as in the source.

Correct translation (sr@ijekavianlatin):
Koristite poseban SOCKS&amp;5 proxy da biste došli do vršnjaka preko Tor onion usluga:
```

<!-- cache_translation_check_sr@ijekavianlatin_c110505a3dc04284a04a851dcf6ad6f36ed44404a36cde8cbd2154b5c3165818 -->
```
        <source>&amp;OK</source>
        <translation>&amp;Уреду</translation>
    
ERR
Translation is incorrect for the requested locale. The target locale is Serbian (ijekavian) in Latin script, but the translation uses Cyrillic letters ("Уреду") and combines the two-word phrase into one. Also ensure the ampersand is present exactly once.

Correct translation (Latin script), with single ampersand:
&U redu
```

<!-- cache_translation_check_sr@ijekavianlatin_9728df50da22722036667bb442427fdd519fdddb3f6384cf0d1180a6a1ded65d -->
```
        <source>&amp;Cancel</source>
        <translation>&amp;Откажи</translation>
    
ERR
The translation is in Cyrillic script ("&Откажи") but the requested locale is Serbian ijekavian in Latin script. Also ensure the ampersand is present exactly once and no extra spaces.

Correct translation (Latin script):
&Otkaži
```

<!-- cache_translation_check_sr@ijekavianlatin_64f7f8689991571993d9003addcdab9e415f9e1dbeacb3baa8b4e4c17ce95513 -->
```
        <source>The configuration file is used to specify advanced user options which override GUI settings. Additionally, any command-line options will override this configuration file.</source>
        <extracomment>Explanatory text about the priority order of instructions considered by client. The order from high to low being: command-line, configuration file, GUI settings.</extracomment>
        <translation>Конфигурациона датотека се користи да одреди напредне корисничке опције које поништају подешавања у графичком корисничком интерфејсу.</translation>
    
ERR
The translation is incomplete. It only includes the first sentence and omits the second sentence, which is important for conveying the full meaning. Additionally, the translation uses Cyrillic script, while 'sr@ijekavianlatin' requires Latin script.

Correct translation:
Konfiguraciona datoteka se koristi za određivanje naprednih korisničkih opcija koje poništavaju podešavanja u grafičkom korisničkom interfejsu. Takođe, sve opcije komandne linije će poništiti ovu konfiguracionu datoteku.
```

<!-- cache_translation_check_sr@ijekavianlatin_dce33cedc9a9616a694fc83d9f474183bf61c85a6fff19f27a1e6b6ad7de22f4 -->
```
        <source>This change would require a client restart.</source>
        <translation>Ова промена захтева да се рачунар поново покрене.</translation>
    
ERR
The translation uses Cyrillic script, while 'sr@ijekavianlatin' requires Latin script (such as "Ova promjena zahtijeva da se klijent ponovo pokrene."). Additionally, "рачунар" means "computer", but the source refers to "client" (the software), not the computer. Also, the ijekavian orthography poorly applied ("promena" should be "promjena"), and the translation omits the modal nuance "would require".

Correct translation:
Ova promjena bi zahtijevala da se klijent ponovo pokrene.
```

<!-- cache_translation_check_sr@ijekavianlatin_324aa35d9b26680ef377fedd071baa8a2486707eecf4e732cce4d20c8a6eadef -->
```
        <source>Available:</source>
        <translation>Доступно:</translation>
    
ERR
The translation uses Cyrillic script ("Доступно:") instead of Latin script, which is required for 'sr@ijekavianlatin'.

Correct translation:
Dostupno:
```

<!-- cache_translation_check_sr@ijekavianlatin_f9d35a3e964f046d92a8a01dfe5732b684ef3627f95f0de2a225051853c24741 -->
```
        <source>Mined balance that has not yet matured</source>
        <translation>Салдо рударења који још увек није доспео</translation>
    
ERR
The provided translation is in Serbian Cyrillic script, while 'sr@ijekavianlatin' specifies Serbian with Ijekavian pronunciation in Latin script. Additionally, "saldo rudarenja" is not the most natural translation; "oplenjeno" is rarely used for "mined." But the critical error is the script.

Correct translation:
Saldo rudarenja koji još uvijek nije dospio
```

<!-- cache_translation_check_sr@ijekavianlatin_7051b5973fedbe08836bd1f6d68f68f52d45129a96e38f3f17318149d0c0ba2f -->
```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>Режим приватности је активиран за картицу Преглед. Да бисте демаскирали вредности, поништите избор Подешавања-&gt;Маск вредности.</translation>
    
ERR
The translation is written in Cyrillic script, but the 'sr@ijekavianlatin' locale specifically requires the use of the Latin alphabet with Ijekavian pronunciation. Additionally, "Маск вредности" is untranslated.

Correct translation:
Režim privatnosti je aktiviran za karticu Pregled. Da biste demaskirali vrijednosti, poništite izbor Podešavanja-&gt;Maskiraj vrijednosti.
```

<!-- cache_translation_check_sr@ijekavianlatin_721ae588a825107d60bf9ac0cf792232d1b2d113324c3250ab525036cc0c252b -->
```
        <source>Signed transaction successfully. Transaction is ready to broadcast.</source>
        <translation>Потписана трансакција је успешно. Трансакција је спремна за емитовање.</translation>
    
ERR
The translation is in Serbian Cyrillic script, whereas 'sr@ijekavianlatin' requires Latin script. Also, "успешно" is wrongly used as an adjective ("успешно"="successful") rather than the adverb "успешно"="successfully", and the sentence structure doesn't align perfectly with the source. 

Correct translation:
Potpisivanje transakcije je uspješno. Transakcija je spremna za emitovanje.
```

<!-- cache_translation_check_sr@ijekavianlatin_eb42220c66bea3d15fe6085acfb511e050a9bf1b08c755fe57440d22dfbce1d7 -->
```
        <source>URI handling</source>
        <translation>URI руковање</translation>
    
ERR
The translation uses Cyrillic 'руковање' instead of Latin script, which is required for 'sr@ijekavianlatin'. The correct translation in Latin script should be:

URI rukovanje
```

<!-- cache_translation_check_sr@ijekavianlatin_cdbd97358498204e8761f36e069511667c12b9bd067eaafb6451298892c98218 -->
```
        <source>&amp;Save Image…</source>
        <translation>&amp;Сачували слику…</translation>
    
ERR
Problems:
- The translation is in Cyrillic (Сачували слику…) but the requested locale is Serbian ijekavian Latin; it should use Latin script.
- The verb form is incorrect: "Сачували слику" is past tense/plural and means "saved the image". The source is a menu/action label ("Save Image…") and requires the imperative/present form.

Correct translation:
&Sačuvaj sliku…
```

<!-- cache_translation_check_sr@ijekavianlatin_3323b4fc8cd752c9bb256a8cfacadd70aa7d93f9f1fc254bbc7ec556a6df13e5 -->
```
        <source>&amp;Copy Image</source>
        <translation>&amp;Копирај Слику</translation>
    
ERR
The translation uses Cyrillic script ("Копирај Слику") but the requested locale 'sr@ijekavianlatin' requires Latin script. Also capitalization is nonstandard (only the first word should typically be capitalized for menu items). The ampersand is present exactly once, which is correct.

Correct translation:
&amp;Kopiraj sliku
```

<!-- cache_translation_check_sr@ijekavianlatin_0710e5469d32ad341aff427c5331444b9ce354fba4454df4c22a1f3905fbf3d6 -->
```
        <source>&amp;Information</source>
        <translation>&amp;Информације</translation>
    
ERR
The translation uses Cyrillic script ("Информације") but the locale requests Serbian in ijekavian Latin script. The ampersand is present once (OK) but the script is wrong.

Correct translation:
&amp;Informacije
```

<!-- cache_translation_check_sr@ijekavianlatin_5ce1842706da70fc55ac8c9f424eec8c9eb25f91b178a898c2342a4158a44bc3 -->
```
        <source>&amp;Reset</source>
        <translation>&amp;Ресетуј</translation>
    
ERR
The translation uses Cyrillic script ("Ресетуј") but the locale requested is Serbian Ijekavian in Latin script. Also the ampersand is present, but the text should be in Latin.

Correct translation (Ijekavian Latin):
&amp;Resetuj
```

<!-- cache_translation_check_sr@ijekavianlatin_7bbfd2562b6bd639530b3f7dce2567cac7cc451c97bec736cd31fa3d08e3a286 -->
```
        <source>&amp;Peers</source>
        <translation>&amp;Колеге</translation>
    
ERR
The translation uses Cyrillic script ("&Колеге") but the requested locale 'sr@ijekavianlatin' requires Latin script. The ampersand is present once (OK), but the script mismatch makes it incorrect.

Suggested correction (Latin script):
&amp;Kolege

(Alternatively, depending on context, you could use "&Saradnici" or "&Čvorovi" if you prefer those terms for "peers".)
```

<!-- cache_translation_check_sr@ijekavianlatin_b002aa70561e9f2f2610fee4f487092e9d39df4639dcc2fa2df17fe1897203d8 -->
```
        <source>Select a peer to view detailed information.</source>
        <translation>Одабери колегу да би видели детаљне информације</translation>
    
ERR
The translation is in Serbian Cyrillic, but 'sr@ijekavianlatin' requires the Latin script with Ijekavian dialect. Also, there is a slight grammatical issue: "да би видели" is incorrect, it should be "да би видио/vidjela" (depending on gender), or more neutrally/commonly "da vidiš" ("to view", addressing 'you' singular/informal). "Peer" is usually translated as "čvor" or "peer" in Bitcoin context, but "kolega" is not accurate here.

Correct translation:
Odaberi peer da bi vidio detaljne informacije.

Or, more informally:
Odaberi peer da vidiš detaljne informacije.
```

<!-- cache_translation_check_sr@ijekavianlatin_451580f477c587065fa477656b585b35282cd8dbcf74b1618b1d5243e3c88448 -->
```
        <source>Last Receive</source>
        <translation>Последње примљено</translation>
    
ERR
The translation is not in 'sr@ijekavianlatin', but rather in Serbian Cyrillic. The correct 'sr@ijekavianlatin' translation should be in Latin script and with appropriate ijekavian forms.

Correct translation:
Posljednje primljeno
```

<!-- cache_translation_check_sr@ijekavianlatin_e7e51108739259f607536c5948e992bddffb9c0daffcd0212dd411a2ab5dbae2 -->
```
        <source>Last block time</source>
        <translation>Време последњег блока</translation>
    
ERR
The translation is written in Serbian Cyrillic script, but 'sr@ijekavianlatin' specifies Serbian in the Latin script with the Ijekavian accent. The correct translation should use Latin characters and the Ijekavian variant.

Correct translation:
Vrijeme posljednjeg bloka
```

<!-- cache_translation_check_sr@ijekavianlatin_82c0fa75206606348425bdc6be85a253be4763424067f43faf71f846587d9d79 -->
```
        <source>&amp;Open</source>
        <translation>&amp;Отвори</translation>
    
ERR
The translation is in Cyrillic script ("&Отвори") but the requested locale is Serbian ijekavian in Latin script. The ampersand is present correctly, but the script is wrong.

Correct translation:
&amp;Otvori
```

<!-- cache_translation_check_sr@ijekavianlatin_ebe2056075a1059d1abd75a455b49857cc87dca67bf0b572ba85c9c098d9eef1 -->
```
        <source>&amp;Console</source>
        <translation>&amp;Конзола</translation>
    
ERR
Translation uses Cyrillic script ("Конзола") but the requested variant is Serbian in Latin script (ijekavian Latin). The ampersand is present correctly, but the script is wrong.

Correct translation:
&amp;Konzola
```

<!-- cache_translation_check_sr@ijekavianlatin_8ebaa9f01c86b7af944c95253bb172225e2895aff7b3a0b9be823ebd39d95bba -->
```
        <source>&amp;Network Traffic</source>
        <translation>&amp;Мрежни саобраћај</translation>
    
ERR
The translation is in Serbian Cyrillic; the requested locale is Serbian ijekavian Latin. Also ensure the ampersand shortcut remains. 

Correct translation (Latin script):
& Mrežni saobraćaj

Better without extra space after &:
&Mrežni saobraćaj
```

<!-- cache_translation_check_sr@ijekavianlatin_b072d38fe1df5f46cf13d9c6ac4dd7b25fff5f8e71b3cdbab4f860f6de06d14b -->
```
        <source>Outbound Block Relay: does not relay transactions or addresses</source>
        <extracomment>Explanatory text for an outbound peer connection that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>Оутбоунд Блоцк Релаи: не преноси трансакције или адресе</translation>
    
ERR
The translation is written in Cyrillic script (Оутбоунд Блоцк Релаи), but 'sr@ijekavianlatin' requires Latin script. Additionally, "ili" is correctly used for "or", but the usage of "или" in Cyrillic further confirms the script issue.

Correct translation:
Outbound Block Relay: ne prenosi transakcije ili adrese
```

<!-- cache_translation_check_sr@ijekavianlatin_62832f4f72903ef0726ec73ae387367386c1c56f38d3e86ac3bb5154b9a376b3 -->
```
        <source>&amp;Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>&amp;Копирај адресу</translation>
    
ERR
The translation uses Cyrillic script (Копирај адресу) but the requested locale is "sr@ijekavianlatin", which requires Serbian in Latin script. The ampersand shortcut is present exactly once, which is fine. No format specifiers or extra whitespace issues.

Correct translation (Latin script):
&amp;Kopiraj adresu
```

<!-- cache_translation_check_sr@ijekavianlatin_f2803cc99125bba960a70c1861e60f45dd2cad7b595fc36da6ad11e1849c48a2 -->
```
        <source>&amp;Disconnect</source>
        <translation>&amp;Прекини везу</translation>
    
ERR
The translation is in Serbian Cyrillic ("Прекини везу") but the requested locale is sr@ijekavianlatin (Serbian ijekavian in Latin script). The ampersand is present correctly, no other format issues.

Correct translation (Latin script, ijekavian):
&amp;Prekini vezu
```

<!-- cache_translation_check_sr@ijekavianlatin_033a0cf19bf591b7a3dc0d74afd684e9399172917e8bd8913075d9edc7e02e06 -->
```
        <source>1 &amp;hour</source>
        <translation>1 &amp;Сат</translation>
    
ERR
The translation uses Cyrillic script ("Сат") but the target variant is Serbian ijekavian Latin; the text should be in Latin script. Also "Сат" is capitalized while the English source uses lowercase "hour". The format specifier/& placement is fine (one &), but script and casing are wrong.

Correct translation:
1 &amp;sat
```

<!-- cache_translation_check_sr@ijekavianlatin_397cc41211cda1a731126fd6876da2d54237e6e032f541fba76dea87b2826662 -->
```
        <source>1 d&amp;ay</source>
        <translation>1 дан</translation>
    
ERR
Problems:
- The translation uses Cyrillic script ("дан") but the target language tag requests Serbian in Latin script (sr@ijekavianlatin).
- The shortcut ampersand (&) from the source is missing in the translation; the source has a single & and the translation must include exactly one.

Correct translation (Serbian ijekavian, Latin script, with the ampersand placed before the same letter 'a' as in source):
1 d&an
```

<!-- cache_translation_check_sr@ijekavianlatin_330213f330eeb273685dcb0b2bcc5f593dd26e15f83c38478926ba795f3429a5 -->
```
        <source>1 &amp;week</source>
        <translation>1 &amp;недеља</translation>
    
ERR
The translation uses Cyrillic ("недеља") but the requested locale is Serbian in Latin script (ijekavian Latin). Also the ijekavian form should be "nedjelja" (not "nedelja"). Keep the single ampersand exactly once as in the source.

Correct translation:
1 &amp;nedjelja
```

<!-- cache_translation_check_sr@ijekavianlatin_27d7f57e8e893d02768d95402c5987e5bd9d9fbbba52a71ebff80bd026b19a4e -->
```
        <source>1 &amp;year</source>
        <translation>1 &amp;година</translation>
    
ERR
The translation uses Cyrillic script ("година") but the requested locale is ijekavian Latin. Also ensure the ampersand for the shortcut is preserved exactly once and spacing matches the source.

Correct translation:
1 &godina
```

<!-- cache_translation_check_sr@ijekavianlatin_7c3afd815b63c1b151e1c01e9f2e9e2341e5231bd4052f732de1f5819f1e9f96 -->
```
        <source>&amp;Unban</source>
        <translation>&amp;Уклони забрану</translation>
    
ERR
The translation is in Cyrillic script (Уклони забрану) but the requested locale is Serbian ijekavian in Latin script. Also ensure the ampersand is present exactly once.

Correct translation (Latin script):
&Ukloni zabranu
```

<!-- cache_translation_check_sr@ijekavianlatin_9fe5dbe2da0d165c15a360a0a3c03bafd16c61a761da731e903399dfdd72d665 -->
```
        <source>Executing command using "%1" wallet</source>
        <translation>Извршење команде коришћењем  "%1" новчаника</translation>
    
ERR
There is an issue with the script. The translation uses Cyrillic ("Извршење команде коришћењем  "%1" новчаника"), but 'sr@ijekavianlatin' expects Latin script with ijekavian dialect. There is also a double space before the quoted variable.

Correct translation:
Izvršavanje komande korišćenjem "%1" novčanika
```

<!-- cache_translation_check_sr@ijekavianlatin_f30c147e3d760751dd526e3b83090ea6a2218cb779f8b517195617f15bc23c79 -->
```
        <source>(peer: %1)</source>
        <translation>(клијент: %1)</translation>
    
ERR
The translation uses Cyrillic script (клијент) instead of Latin script as required by 'sr@ijekavianlatin'. Also, "peer" is more accurately translated as "čvor" or "peer", not "klijent".

Correct translation:
(peer: %1)
or
(čvor: %1)
```

<!-- cache_translation_check_sr@ijekavianlatin_84cc7cf180a943021652b511ad74df1bea1c3988fe954f1d0b34a7270e14354b -->
```
        <source>&amp;Amount:</source>
        <translation>&amp;Износ:</translation>
    
ERR
The translation uses Cyrillic script ("&Износ:") but the requested locale 'sr@ijekavianlatin' requires Serbian in Latin script. The ampersand is present exactly once and there are no format specifiers or spacing issues otherwise.

Correct translation:
&Iznos:
```

<!-- cache_translation_check_sr@ijekavianlatin_4420bd642e223e7058851279ba44a863faca7b787d6e7957edf9362ce6214c23 -->
```
        <source>&amp;Label:</source>
        <translation>&amp;Ознака</translation>
    
ERR
The translation uses Cyrillic script ("Ознака") but the target locale requests Serbian in Ijekavian Latin script. It also omits the trailing colon present in the source. The ampersand is fine (exactly once) but must be followed by the Latin text and the colon.

Correct translation:
&amp;Oznaka:
```

<!-- cache_translation_check_sr@ijekavianlatin_2bfbe2f2c6bd82789295232b724563092ed0660eebf8428c9b76d99d1f18f639 -->
```
        <source>&amp;Message:</source>
        <translation>Poruka:</translation>
    
ERR
The translation is missing the shortcut indicator (&) present in the source. It should include exactly one & to mark the mnemonic.

Correct translation:
&amp;Poruka:
```

<!-- cache_translation_check_sr@ijekavianlatin_81dc66f08796c020e4534ac3084fed50de5c56da4c36c1cf0dbb1e9e635fb931 -->
```
        <source>&amp;Create new receiving address</source>
        <translation>&amp;Направи нову адресу за примање</translation>
    
ERR
The translation is in Serbian Cyrillic script, but the target locale 'sr@ijekavianlatin' requires Serbian in Latin script. Also ensure the ampersand (&) for the shortcut is present exactly once.

Correct translation (Ijekavian, Latin script):
&amp;Napravi novu adresu za primanje
```

<!-- cache_translation_check_sr@ijekavianlatin_057154c24bfd958d19f054026fc612c775739ad0b7d9a2ceec6d9f6727685322 -->
```
        <source>Remove</source>
        <translation>Уклони</translation>
    
ERR
The translation is in Cyrillic script ("Уклони"), but 'sr@ijekavianlatin' requires the Latin alphabet. The correct translation should use Latin script.

Correct translation:
Ukloni
```

<!-- cache_translation_check_sr@ijekavianlatin_fef56942fa30ebe6bc1d459cdbb44419f0979c26ebe017220765bbe6ee394ecf -->
```
        <source>Copy &amp;URI</source>
        <translation>Копирај &amp;URI</translation>
    
ERR
The target locale requests Serbian ijekavian in Latin script, but the translation uses Cyrillic ("Копирај"). Also ensure the ampersand shortcut is preserved exactly once (it is present). Correct translation in Latin script:

Kopiraj &URI
```

<!-- cache_translation_check_sr@ijekavianlatin_8222a858873ec13c5df7e9a946592a36bf3eb8671dad9a25599b24410f0c2ebb -->
```
        <source>&amp;Copy address</source>
        <translation>&amp;Копирај адресу</translation>
    
ERR
The translation uses Cyrillic script ("Копирај адресу") but the requested locale 'sr@ijekavianlatin' requires Latin script. The ampersand for the shortcut is present exactly once, which is correct.

Correct translation (Latin, ijekavian):
&amp;Kopiraj adresu
```

<!-- cache_translation_check_sr@ijekavianlatin_d3c67ee6f7daa4d5ec3f613ccf586301db99122f3390c8488657d75dbb5c4432 -->
```
        <source>Copy &amp;label</source>
        <translation>Копирај &amp;означи</translation>
    
ERR
Problems:
- The translation is in Cyrillic (Копирај &amp;означи) but the target requested is sr@ijekavianlatin (Latin script).
- The verb/noun choice is wrong: "означи" means "mark" (imperative), not "label" (noun). The case is also incorrect for "copy the label".

Correct translation (sr@ijekavianlatin, with single &):
Kopiraj &oznaku
```

<!-- cache_translation_check_sr@ijekavianlatin_9b0ff01c16ff1b3c79ee14d594a01b3ca5e47d180cac422c08943a60ec8ba767 -->
```
        <source>Copy &amp;message</source>
        <translation>Копирај &amp;поруку</translation>
    
ERR
The translation is in Cyrillic script ("Копирај &amp;поруку") but the requested locale is Serbian ijekavian in Latin script. Otherwise the text and shortcut are fine.

Correct translation (Latin script):
Kopiraj &amp;poruku
```

<!-- cache_translation_check_sr@ijekavianlatin_638ac814c9d49f25c1043de13c925c3b5f2c583035e53e743a5bbbdb53b0f1bf -->
```
        <source>Copy &amp;amount</source>
        <translation>Копирај &amp;износ</translation>
    
ERR
The translation uses Cyrillic script ("Копирај &износ") but the requested locale is Serbian ijekavian Latin; it should be in Latin script. The ampersand/HTML entity is present and placed correctly, but the script is wrong.

Correct translation:
<translation>Kopiraj &amp;iznos</translation>
```

<!-- cache_translation_check_sr@ijekavianlatin_fef56942fa30ebe6bc1d459cdbb44419f0979c26ebe017220765bbe6ee394ecf -->
```
        <source>Copy &amp;URI</source>
        <translation>Копирај &amp;URI</translation>
    
ERR
The target locale requests Serbian ijekavian in Latin script, but the translation uses Cyrillic ("Копирај"). Also ensure the ampersand shortcut is preserved exactly once (it is present). Correct translation in Latin script:

Kopiraj &URI
```

<!-- cache_translation_check_sr@ijekavianlatin_8e2cde33a460a8fd2b593bf3a944337e78b8459b3ebbd54145e29ae4e5aa3411 -->
```
        <source>Copy &amp;Address</source>
        <translation>Копирај &amp;Адресу</translation>
    
ERR
The translation is in Cyrillic ("Копирај &Адресу") but the target locale requests Serbian Ijekavian in Latin script. The ampersand is present exactly once (OK), and there are no format specifiers, but the script is wrong.

Correct translation (sr@ijekavianlatin):
Kopiraj &adresu
```

<!-- cache_translation_check_sr@ijekavianlatin_e5dc85af7f6693aaba378d079ea22945a55e228e7def3eac253538e6e7785af7 -->
```
        <source>&amp;Verify</source>
        <translation>&amp;Верификуј</translation>
    
ERR
The translation uses Cyrillic script ("Верификуј") but the requested locale is Serbian in ijekavian Latin script. The ampersand is present and correct, but the script is wrong.

Correct translation (sr@ijekavianlatin):
&Verifikuj
```

<!-- cache_translation_check_sr@ijekavianlatin_cdbd97358498204e8761f36e069511667c12b9bd067eaafb6451298892c98218 -->
```
        <source>&amp;Save Image…</source>
        <translation>&amp;Сачували слику…</translation>
    
ERR
Problems:
- The translation is in Cyrillic (Сачували слику…) but the requested locale is Serbian ijekavian Latin; it should use Latin script.
- The verb form is incorrect: "Сачували слику" is past tense/plural and means "saved the image". The source is a menu/action label ("Save Image…") and requires the imperative/present form.

Correct translation:
&Sačuvaj sliku…
```

<!-- cache_translation_check_sr@ijekavianlatin_b5245733811e29573b04cfab363713d384f23bdcdbaa7fa59f6b98c935f14ee5 -->
```
        <source>Coin Control Features</source>
        <translation>Опција контроле новчића</translation>
    
ERR
The translation uses Cyrillic script ("Опција контроле новчића"), but the required 'sr@ijekavianlatin' should use Latin script (ijekavian standard).

Correct translation:
Opcija kontrole novčića
```

<!-- cache_translation_check_sr@ijekavianlatin_3073454e2f40f5b40cc47f1402cd451aa36a195539415cfc02f7238f822308b0 -->
```
        <source>If this is activated, but the change address is empty or invalid, change will be sent to a newly generated address.</source>
        <translation>Уколико је ово активирано, али је промењена адреса празна или неважећа, промена ће бити послата на ново-генерисану адресу.</translation>
    
ERR
The translation uses the Cyrillic script ("Уколико је ово активирано, али је промењена адреса празна или неважећа, промена ће бити послата на ново-генерисану адресу.") instead of the required Latin script per 'sr@ijekavianlatin'. Also, the phrase "промењена адреса" translates as "changed address" rather than "change address" (where "change" refers to transaction change in Bitcoin). The appropriate term should be "adresa za kusur".

Correct translation:
Ukoliko je ovo aktivirano, ali je adresa za kusur prazna ili nevažeća, kusur će biti poslat na novo generisanu adresu.
```

<!-- cache_translation_check_sr@ijekavianlatin_15a4f54629d8da579c435c03284567c837c6f9afd6abcac1490bc24911ee5817 -->
```
        <source>Custom change address</source>
        <translation>Прилагођена промењена адреса</translation>
    
ERR
The translation is problematic for two reasons: 
1. The script used is Cyrillic, but 'sr@ijekavianlatin' requires Latin script.
2. The translation is inaccurate. "Промењена адреса" means "changed address", not "change address" (in the context of a Bitcoin transaction, "change address" refers to the address for returning change).

Correct translation:
Prilagođena adresa za kusur
```

<!-- cache_translation_check_sr@ijekavianlatin_4a2f4ce01b29bff07437eff585bbac6d521acaa198e007767bc50a15dac3a6ab -->
```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Коришћење безбедносне накнаде може резултовати у времену потребно за потврду трансакције од неколико сати или дана (или никад). Размислите о ручном одабиру провизије или сачекајте док нисте потврдили комплетан ланац.</translation>
    
ERR  
The translation uses Cyrillic script, not Latin ('sr@ijekavianlatin' requires Latin script). Also, some terms can be improved, and there are some stylistic choices that do not fit the standard ijekavian Latin.

Correct translation:  
Korišćenje fallbackfee može rezultirati time da će transakciji trebati nekoliko sati ili dana (ili nikada) da bude potvrđena. Razmislite o ručnom odabiru naknade ili sačekajte dok ne verifikujete cijeli lanac.
```

<!-- cache_translation_check_sr@ijekavianlatin_fffb11a5e0c5e1074857cca7ce0d8a4b17210a05d38ff67892f82c8e71b8516f -->
```
        <source>Add &amp;Recipient</source>
        <translation>Додај &amp;Примаоца</translation>
    
ERR
The translation is in Cyrillic ("Додај &amp;Примаоца") but the requested locale is serbian ijekavian in Latin script (sr@ijekavianlatin). Also use of the word form should be in Latin script and appropriate case.

Correct translation (Latin script, ijekavian/Serbian):
Dodaj &Primalca
```

<!-- cache_translation_check_sr@ijekavianlatin_b1b479ee5e5adffdb4d30d0ad51f3177aef6355e42fd2446418aa0fea2c154a4 -->
```
        <source>Specify a custom fee per kB (1,000 bytes) of the transaction's virtual size.

Note:  Since the fee is calculated on a per-byte basis, a fee rate of "100 satoshis per kvB" for a transaction size of 500 virtual bytes (half of 1 kvB) would ultimately yield a fee of only 50 satoshis.</source>
        <translation>Одредити прилагођену провизију по kB (1,000 битова) виртуелне величине трансакције. 

Напомена: С обзиром да се провизија рачуна на основу броја бајтова, провизија за "100 сатошија по kB" за величину трансакције од 500 бајтова (пола од 1 kB) ће аутоматски износити само 50 сатошија.</translation>
    
ERR
There are several issues with the translation:

1. The translation is in Serbian Cyrillic, but 'sr@ijekavianlatin' specifically requires Latin script.
2. "битова" should be "bajtova" not "bitova", since "byte" is "bajt" and "bit" (bit) are different.
3. It maintains the abbreviation "kB", which is correct, but the source also uses "kvB" ("kilovirtual bajt"), which is not reflected. However, in the Serbian Bitcoin context, "kB" is often kept as-is.
4. Some slight style improvement for more natural Ijekavian Latin Serbian.

Correct translation:

Odredite prilagođenu naknadu po kB (1.000 bajtova) virtuelne veličine transakcije.

Napomena: Pošto se naknada računa na osnovu broja bajtova, stopa od "100 satoshija po kB" za veličinu transakcije od 500 bajtova (pola od 1 kB) će na kraju iznositi svega 50 satoshija.
```

<!-- cache_translation_check_sr@ijekavianlatin_621cca7efcb42f2c87d5571b7e71e2941585ee7856312bccfc559e8507e44a81 -->
```
        <source>Clear &amp;All</source>
        <translation>Очисти &amp;Све</translation>
    
ERR
The translation is in Cyrillic ("Очисти &amp;Све") but the requested language variant is Serbian ijekavian Latin (Latin script). Also the capitalization/word choice can be adjusted to sound natural.

Correct translation (Latin script, with the & entity preserved):
Očisti &amp;sve
```

<!-- cache_translation_check_sr@ijekavianlatin_ca905e9126c9bf2f3ee8987aa4e3e1737a6059d30900084d263e18078fdac874 -->
```
        <source>S&amp;end</source>
        <translation>&amp;Пошаљи</translation>
    
ERR
The translation is in Cyrillic script ("&Пошаљи") but the requested locale is Serbian ijekavian in Latin script. Also the ampersand is present (good), but the text must be Latin.

Correct translation:
&Pošalji
```

<!-- cache_translation_check_sr@ijekavianlatin_f39fbbc000a30fd081506cf611a5a8bbb95f0e60141c3a0c52ec058a70a68bc0 -->
```
        <source>Set external signer script path in Options -&gt; Wallet</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Подси екстерну скрипту за потписивање у : Options -&gt; Wallet</translation>
    
ERR
The translation contains several issues:
1. "Подси" is a Cyrillic word. 'sr@ijekavianlatin' should be in Latin script, not Cyrillic.
2. "екстерну" should be "eksternu" in Latin, and it's not the most idiomatic. "Eksterni potpisivač" is the usual technical term for external signer.
3. "скрипту за потписивање" is also Cyrillic and should be "skriptu za potpisivanje" in Latin.
4. The full message does not accurately reflect the instructional tone of the original.
5. The translation of "Options -> Wallet" should be "Opcije → Novčanik" in ijekavian Latin localization, and does not need a preceding ":".
6. The sentence order is off and unclear.

Correct translation:
Postavite putanju do skripte eksternog potpisivača u Opcije → Novčanik
```

<!-- cache_translation_check_sr@ijekavianlatin_566f4091d922028011e4cfd151eb5d9e7f69a40c358641d54655bc256330ba59 -->
```
        <source>Cr&amp;eate Unsigned</source>
        <translation>Креирај непотписано</translation>
    
ERR
The translation is in Cyrillic script (Креирај непотписано) but the requested locale 'sr@ijekavianlatin' requires Latin script. Also the source contains a single & (shortcut) which must be preserved exactly once in the translation; the provided translation has no &.

Correct translation (Latin script) example with one shortcut marker:
Kreiraj ne&potpisano
```

<!-- cache_translation_check_sr@ijekavianlatin_ba1b8b843b769b3cfc95c3749c72a31bc6e7271cb34dccf5c7781c1056f9a05c -->
```
        <source>The recipient address is not valid. Please recheck.</source>
        <translation>Адреса примаоца није валидна. Молим проверите поново.</translation>
    
ERR
The translation is in Serbian Cyrillic, but 'sr@ijekavianlatin' requires the use of the Latin alphabet (ijekavian variant). The word order and phrasing are otherwise correct, but the script is wrong.

Correct translation:
Adresa primaoca nije validna. Molim provjerite ponovo.
```

<!-- cache_translation_check_sr@ijekavianlatin_fbd119a17e9b07e1ce3bf263754405126a4cc2e0e5465ce57654c8b8990a2748 -->
```
        <source>The amount to pay must be larger than 0.</source>
        <translation>Овај износ за плаћање мора бити већи од 0.</translation>
    
ERR
The translation uses Serbian Cyrillic script instead of Latin script, whereas 'sr@ijekavianlatin' specifies Ijekavian dialect in Latin script. Also, the definite article "Овај" ("Ovaj") is unnecessary here.

Correct translation:
Iznos za plaćanje mora biti veći od 0.
```

<!-- cache_translation_check_sr@ijekavianlatin_e3533c8f35d55b8a6d38c81cc4c93ae7dd18b570bc205397231a8cd73beaa665 -->
```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Пронађена је дуплирана адреса: адресе се требају користити само једном.</translation>
    
ERR
The translation uses Cyrillic script, but 'sr@ijekavianlatin' requires Latin script. Also, "требају" is typically Ekavian; in Ijekavian, "trebaju" is acceptable, but "treba da se" or "trebaju se" could be both used.

Correct translation:
Pronađena je duplirana adresa: adrese se trebaju koristiti samo jednom.
```

<!-- cache_translation_check_sr@ijekavianlatin_563a4b7989532aef51f7f16f15b169b55069603055da2e532a54487a52568ac6 -->
```
        <source>A&amp;mount:</source>
        <translation>&amp;Износ:</translation>
    
ERR
The translation uses Cyrillic script ("Износ") but the target locale requests Latin script (sr@ijekavianlatin). Also ensure the ampersand appears exactly once.

Correct translation:
&amp;Iznos:
```

<!-- cache_translation_check_sr@ijekavianlatin_b8c6c5da9849bdb49ee565a14846c9b24c49a703f73e32abbdf9ae63c58d1f71 -->
```
        <source>Pay &amp;To:</source>
        <translation>Плати &amp;За:</translation>
    
ERR
The translation is in Serbian Cyrillic ("Плати &За:") but the target locale requests ijekavian Latin script. Also the phrasing could be clearer for a "Pay To:" label.

Correct translation (sr@ijekavianlatin):
Plati &na:
```

<!-- cache_translation_check_sr@ijekavianlatin_4420bd642e223e7058851279ba44a863faca7b787d6e7957edf9362ce6214c23 -->
```
        <source>&amp;Label:</source>
        <translation>&amp;Ознака</translation>
    
ERR
The translation uses Cyrillic script ("Ознака") but the target locale requests Serbian in Ijekavian Latin script. It also omits the trailing colon present in the source. The ampersand is fine (exactly once) but must be followed by the Latin text and the colon.

Correct translation:
&amp;Oznaka:
```

<!-- cache_translation_check_sr@ijekavianlatin_47423f3df56b031a90391e17328d0db68e4ca323a5d99959017aa6803d2177e4 -->
```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Биткоин адреса на коју се шаље уплата</translation>
    
ERR
The translation uses Serbian Cyrillic script "Биткоин адреса на коју се шаље уплата", but 'sr@ijekavianlatin' specifies Ijekavian Latin script. Script must be Latin, not Cyrillic.

Correct translation:
Bitcoin adresa na koju se šalje uplata
```

<!-- cache_translation_check_sr@ijekavianlatin_c8cedd32ca199fd5704e81a8ad8d430232accc79908cdd568bce5436ade7cdcd -->
```
        <source>Paste address from clipboard</source>
        <translation>Налепите адресу из базе за копирање</translation>
    
ERR
The translation uses Cyrillic script ("Налепите адресу из базе за копирање") instead of the required Ijekavian Latin script. Also, "база за копирање" is an awkward translation for "clipboard". The accepted term is "privremena memorija" or simply "clipboard". 

Correct translation:
Nalijepite adresu iz privremene memorije
```

<!-- cache_translation_check_sr@ijekavianlatin_19b0523245d83951697c4f4a6de4fe558f3a084b55eba17da77da5162d42ca6f -->
```
        <source>S&amp;ubtract fee from amount</source>
        <translation>&amp;Одузми провизију од износа</translation>
    
ERR
Translation is in Cyrillic script and not in the requested Serbian ijekavian Latin script. Also ensure the ampersand exists exactly once (it does), and there are no format specifiers to check.

Correct translation (sr@ijekavianlatin, Latin script):
&Oduzmi proviziju od iznosa
```

<!-- cache_translation_check_sr@ijekavianlatin_6f8140282cc6d60ca80d7d6152977712452059b2b4745f21ccf42aa464a658e8 -->
```
        <source>A message that was attached to the bitcoin: URI which will be stored with the transaction for your reference. Note: This message will not be sent over the Bitcoin network.</source>
        <translation>Порука која је приложена биткоину: URI која ће бити сачувана уз трансакцију ради референце. Напомена: Ова порука се шаље преко Биткоин мреже.</translation>
    
ERR
The translation is problematic:
1. It uses Cyrillic script, but 'sr@ijekavianlatin' specifies Latin script.
2. The last sentence incorrectly says the message will be sent over the Bitcoin network, contradicting the source.

Correct translation:
Poruka koja je priložena bitcoin: URI-ju i koja će biti sačuvana uz transakciju radi vaše reference. Napomena: Ova poruka neće biti poslata preko Bitcoin mreže.
```

<!-- cache_translation_check_sr@ijekavianlatin_49d991140f4342194447e388e10e48b7c49b0a53be1803c4434e73b58f0c5ead -->
```
        <source>&amp;Sign Message</source>
        <translation>&amp;Потпиши поруку</translation>
    
ERR
The translation is in Serbian Cyrillic ("&Потпиши поруку"), but the target variant specifies ijekavian Latin script. Also ensure the ampersand shortcut is preserved (exists once).

Correct translation (Latin script):
&Potpiši poruku
```

<!-- cache_translation_check_sr@ijekavianlatin_2d5d223a3a090b71c9868d916e65d8325b4b416c737abf0c09fda8642692d13b -->
```
        <source>The Bitcoin address to sign the message with</source>
        <translation>Биткоин адреса са којом ћете потписати поруку</translation>
    
ERR
The translation is in Cyrillic script, but 'sr@ijekavianlatin' requires Latin script with Ijekavian dialect.

Correct translation:
Bitcoin adresa sa kojom ćete potpisati poruku
```

<!-- cache_translation_check_sr@ijekavianlatin_c8cedd32ca199fd5704e81a8ad8d430232accc79908cdd568bce5436ade7cdcd -->
```
        <source>Paste address from clipboard</source>
        <translation>Налепите адресу из базе за копирање</translation>
    
ERR
The translation uses Cyrillic script ("Налепите адресу из базе за копирање") instead of the required Ijekavian Latin script. Also, "база за копирање" is an awkward translation for "clipboard". The accepted term is "privremena memorija" or simply "clipboard". 

Correct translation:
Nalijepite adresu iz privremene memorije
```

<!-- cache_translation_check_sr@ijekavianlatin_216b367c36f2e08b4c4ba928978a18dae8e6f91f56ea21cc168d01e65a517dc1 -->
```
        <source>Sign &amp;Message</source>
        <translation>Потпис &amp;Порука</translation>
    
ERR
Translation uses Cyrillic script ("Потпис &amp;Порука") but the requested locale is sr@ijekavianlatin (Latin script). Also there's an extra space before the ampersand and the word forms could be more natural for a UI.

Correct translation in Serbian (ijekavian, Latin script), keeping the ampersand once (XML-escaped):
Potpiši &amp;poruku
```

<!-- cache_translation_check_sr@ijekavianlatin_621cca7efcb42f2c87d5571b7e71e2941585ee7856312bccfc559e8507e44a81 -->
```
        <source>Clear &amp;All</source>
        <translation>Очисти &amp;Све</translation>
    
ERR
The translation is in Cyrillic ("Очисти &amp;Све") but the requested language variant is Serbian ijekavian Latin (Latin script). Also the capitalization/word choice can be adjusted to sound natural.

Correct translation (Latin script, with the & entity preserved):
Očisti &amp;sve
```

<!-- cache_translation_check_sr@ijekavianlatin_afd5091261b92d9ed17ccdd937f602a56d1e30057021153c3cd0ea0e01066dcc -->
```
        <source>&amp;Verify Message</source>
        <translation>&amp;Потврди поруку</translation>
    
ERR
The translation is in Cyrillic script ("Потврди поруку") but the target variant 'sr@ijekavianlatin' requires the Latin alphabet. The ampersand is present properly.

Correct translation (Latin, ijekavian):
&amp;Potvrdi poruku
```

<!-- cache_translation_check_sr@ijekavianlatin_8322e6a34c1e4162db9c4633673ab98145fb38274266e126dc85db104a64ff3e -->
```
        <source>The Bitcoin address the message was signed with</source>
        <translation>Биткоин адреса са којом је потписана порука</translation>
    
SPAM
The translation is provided in Cyrillic script, but 'sr@ijekavianlatin' requires the Latin script. Additionally, "са којом је потписана порука" is a good translation.
 
Correct translation:
Bitcoin adresa sa kojom je potpisana poruka
```

<!-- cache_translation_check_sr@ijekavianlatin_43fff02640f8de981bf3758f39d77ea6e20df327c204c9edff9bf84eeee5eaad -->
```
        <source>Verify &amp;Message</source>
        <translation>Потврди &amp;Поруку</translation>
    
ERR
The translation is in Cyrillic script ("Потврди &Поруку") but the requested locale is sr@ijekavianlatin (Serbian Ijekavian in Latin script). Also ensure the ampersand appears exactly once (it does), but script must be Latin.

Correct translation (Ijekavian Latin):
Potvrdi &poruku
```

<!-- cache_translation_check_sr@ijekavianlatin_ba001c9ec59bc7dfe603dddb63bfc2626222765f1e9d19c09e504ec75ca6fb8b -->
```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>%1 порврде</translation>
    
ERR
There is a typo in the translation: "порврде" should be "potvrde" in ijekavian latin script, and it should use Latin characters (since 'sr@ijekavianlatin' specifies Latin, not Cyrillic). Also, the correct Ijekavian form is "potvrde".

Correct translation:
%1 potvrde
```

<!-- cache_translation_check_sr@ijekavianlatin_424f3b02ed675f591d34bdbaa41f658e7ad9f12e5faf10b4e4360e8d777da742 -->
```
        <source>Credit</source>
        <translation>Заслуге</translation>
    
ERR
The translation "Заслуге" is written in Cyrillic script and means "merits" or "achievements," which is an incorrect translation of "Credit" in the context of Bitcoin and also not in the requested 'sr@ijekavianlatin' (which uses Latin script).

Correct translation:
Kredit
```

<!-- cache_translation_check_sr@ijekavianlatin_3546228dee3a5a05b4759f94e845671c7834ddbabe761f58c579e9432e971ee9 -->
```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Није доспео (%1 потврде, биће доступан након %2)</translation>
    
ERR
The translation uses Cyrillic script ("Није доспео") instead of the required Latin script for 'sr@ijekavianlatin'. Additionally, "потврде" should be "potvrda" (or optionally "potvrde", depending on the exact count), but the main issue is the script.

Correct translation:
Nije dospio (%1 potvrda, biće dostupan nakon %2)
```

<!-- cache_translation_check_sr@ijekavianlatin_167e8b43a6aacf2d88ed7304a733a4fe218609f561b42ddbe01e00a776b667ec -->
```
        <source>Transaction status. Hover over this field to show number of confirmations.</source>
        <translation>Статус трансакције. Пређи мишем преко поља за приказ броја трансакција.</translation>
    
ERR
There are two main issues:
1. The translation uses Cyrillic script, whereas 'sr@ijekavianlatin' specifies the Latin script.
2. The translation for "number of confirmations" is rendered as "броја трансакција" ("number of transactions"), which is incorrect. It should be "број потврда" ("number of confirmations").

Correct translation:
Status transakcije. Pređi mišem preko ovog polja za prikaz broja potvrda.
```

<!-- cache_translation_check_sr@ijekavianlatin_ed89ae247a56115b483a2c1956e4b988a4547afaaa7d1b32cfaea99cc1704937 -->
```
        <source>Amount removed from or added to balance.</source>
        <translation>Износ одбијен или додат салду.</translation>
    
ERR
The translation uses Serbian Cyrillic script, but 'sr@ijekavianlatin' requires Latin script. Additionally, "saldu" is less common; "stanje" is more usual. Correct use should also fully localize "removed from or added to".

Correct translation:
Iznos oduzet od ili dodat stanju.
```

<!-- cache_translation_check_sr@ijekavianlatin_3df7f584c7b84347772461b8f22c01a1020c1b0f810fd15d806b104791fc9e71 -->
```
        <source>Enter address, transaction id, or label to search</source>
        <translation>Унесите адресу, ознаку трансакције, или назив за претрагу</translation>
    
ERR
The translation is in Cyrillic script, whereas 'sr@ijekavianlatin' specifies the Serbian language in Ijekavian dialect using the Latin script. Moreover, "трансакције" is "transaction" not "transaction id", and the translation for "label" would better be "ознака" or "етикета".

Correct translation:
Unesite adresu, ID transakcije ili oznaku za pretragu
```

<!-- cache_translation_check_sr@ijekavianlatin_8222a858873ec13c5df7e9a946592a36bf3eb8671dad9a25599b24410f0c2ebb -->
```
        <source>&amp;Copy address</source>
        <translation>&amp;Копирај адресу</translation>
    
ERR
The translation uses Cyrillic script ("Копирај адресу") but the requested locale 'sr@ijekavianlatin' requires Latin script. The ampersand for the shortcut is present exactly once, which is correct.

Correct translation (Latin, ijekavian):
&amp;Kopiraj adresu
```

<!-- cache_translation_check_sr@ijekavianlatin_d3c67ee6f7daa4d5ec3f613ccf586301db99122f3390c8488657d75dbb5c4432 -->
```
        <source>Copy &amp;label</source>
        <translation>Копирај &amp;означи</translation>
    
ERR
Problems:
- The translation is in Cyrillic (Копирај &amp;означи) but the target requested is sr@ijekavianlatin (Latin script).
- The verb/noun choice is wrong: "означи" means "mark" (imperative), not "label" (noun). The case is also incorrect for "copy the label".

Correct translation (sr@ijekavianlatin, with single &):
Kopiraj &oznaku
```

<!-- cache_translation_check_sr@ijekavianlatin_638ac814c9d49f25c1043de13c925c3b5f2c583035e53e743a5bbbdb53b0f1bf -->
```
        <source>Copy &amp;amount</source>
        <translation>Копирај &amp;износ</translation>
    
ERR
The translation uses Cyrillic script ("Копирај &износ") but the requested locale is Serbian ijekavian Latin; it should be in Latin script. The ampersand/HTML entity is present and placed correctly, but the script is wrong.

Correct translation:
<translation>Kopiraj &amp;iznos</translation>
```

<!-- cache_translation_check_sr@ijekavianlatin_e84fb6cd88755bb3b2df9aee78add1c43e86c882481bb46969d0f435bc4299f0 -->
```
        <source>Copy transaction &amp;ID</source>
        <translation>Копирај трансакцију &amp;ID</translation>
    
ERR
The translation is in Cyrillic script and word order is awkward for the intended meaning. The requested locale is Serbian (ijekavian) in Latin script. Also the English has "&ID" (ampersand for shortcut) which should appear exactly once in the translation.

Correct translation (sr@ijekavianlatin, Latin script):
Kopiraj &ID transakcije
```

<!-- cache_translation_check_sr@ijekavianlatin_deff63cc76c7800910ee2ef9573abe1189bc1da7d772fddfcad8d9502e5134cb -->
```
        <source>Copy &amp;raw transaction</source>
        <translation>Копирајте &amp;необрађену трансакцију</translation>
    
ERR
Translation is in Cyrillic script and not in the requested Serbian ijekavian Latin script. The content otherwise is correct and the & shortcut appears exactly once, but the string must use Latin characters.

Correct translation (sr@ijekavianlatin):
Kopiraj &neobrađenu transakciju
```

<!-- cache_translation_check_sr@ijekavianlatin_144f5bd13d12f080bb3ae7661504ebf46f09b7b6ed2dd5885e2ce867a5c2c4e0 -->
```
        <source>Copy full transaction &amp;details</source>
        <translation>Копирајте све детаље трансакције</translation>
    
ERR
Problems:
- The translation is in Serbian Cyrillic, but the requested locale 'sr@ijekavianlatin' requires Latin script.
- The source contains one ampersand (&) marking the shortcut key; the translation has no &. The & must appear exactly once.

Correct translation (Latin, ijekavian, with one & for the shortcut):
Kopirajte sve &detalje transakcije
```

<!-- cache_translation_check_sr@ijekavianlatin_b97560d26fa0c22a215895b3014c68515fa9c737089e8a58eff3a87f6a9168c4 -->
```
        <source>&amp;Show transaction details</source>
        <translation>&amp;Прикажи детаље транакције</translation>
    
ERR
Translation is problematic: it's in Cyrillic (should be Latin for 'sr@ijekavianlatin') and contains a typo ("транакције" instead of "трансакције"). The ampersand is present once which is correct. No format specifiers to check.

Correct translation (Latin, ijekavian):
&Prikaži detalje transakcije
```

<!-- cache_translation_check_sr@ijekavianlatin_909a6b3f2ed6a28e2298ca06b26ea9008e87e356d23bf01a6311319d0fc40c47 -->
```
        <source>Increase transaction &amp;fee</source>
        <translation>Повећај провизију трансакције</translation>
    
ERR
The translation is in Cyrillic (Повећај провизију трансакције) but the requested locale is Serbian Ijekavian in Latin script. Also the shortcut marker (&) from the source is missing. 

Correct translation (sr@ijekavianlatin), with a single & for the shortcut:
Povećaj &proviziju transakcije
```

<!-- cache_translation_check_sr@ijekavianlatin_94468c526042009052f40f5c425f6a92b5a0dc8b08f57f436152dbfea6158e54 -->
```
        <source>&amp;Edit address label</source>
        <translation>&amp;Promeni adresu etikete</translation>
    
ERR
The translation is grammatically incorrect and awkward in Serbian ijekavian Latin. "&Promeni adresu etikete" is not natural — word order and choice are wrong ("promeni" is ekavian and "adresu etikete" is an incorrect collocation).

Correct translation (keep single & for the shortcut):
&Izmijeni oznaku adrese
```

<!-- cache_translation_check_sr@ijekavianlatin_ae477304ee6b46a87948bbaa8e68e0e67eb42bd8b510cc67dc4b966d6011cf52 -->
```
        <source>Confirm fee bump</source>
        <translation>Потврдите ударну провизију</translation>
    
ERR
The translation is problematic for several reasons:
- It is in Cyrillic script instead of Latin, which is required for 'sr@ijekavianlatin'.
- "ударну провизију" is not an accurate translation for "fee bump" in this Bitcoin context. "Fee bump" refers to increasing the transaction fee, not a "sudden" or "strike" fee.
- The phrase "Potvrdite povećanje provizije" is the correct translation in Latin script.

Correct translation:
Potvrdite povećanje provizije
```

<!-- cache_translation_check_sr@ijekavianlatin_c76f87a82970604f7545f43f62a66b717e746d7972cf995a367dec5799534846 -->
```
        <source>Could not commit transaction</source>
        <translation>Трансакција није могућа</translation>
    
ERR
The translation is in Serbian Cyrillic script, but 'sr@ijekavianlatin' requires Latin script. Also, "nije moguća" means "is not possible," which is less precise than "Could not commit transaction" ("Commmit" means to finalize/complete the transaction).

Correct translation:
Transakcija nije mogla biti izvršena
```

<!-- cache_translation_check_sr@ijekavianlatin_7ca002797329f5a743448c82881071daaa967bc24a2a4e0cc3edf6a89de469b0 -->
```
        <source>Backup Successful</source>
        <translation>Резервна копија је успела</translation>
    
SPAM
The translation is in Serbian Cyrillic, not 'sr@ijekavianlatin' (Serbian in Ijekavian Latin script), which is required.

Correct translation:
Rezervna kopija je uspjela
```

<!-- cache_translation_check_sr@ijekavianlatin_e7478a5acc54becf9135f2c3b15a7876d74540ca519c7588cbd666a4c6625531 -->
```
        <source>This is the transaction fee you may pay when fee estimates are not available.</source>
        <translation>Ово је провизија за трансакцију коју можете платити када процена провизије није доступна.</translation>
    
ERR
The translation uses Cyrillic script, but 'sr@ijekavianlatin' requires Latin script (with Ijekavian dialect). The word "провизија" is also a less common choice for "fee" in this context; "naknada" is more appropriate.

Correct translation:
Ovo je naknada za transakciju koju možete platiti kada procjene naknade nisu dostupne.
```

<!-- cache_translation_check_sr@ijekavianlatin_0af1de07ab03f41f76af05c61d470f4dad398e4ab94d1a4c5a18d1b7b9d8e923 -->
```
        <source>Unable to replay blocks. You will need to rebuild the database using -reindex-chainstate.</source>
        <translation>Блокове није могуће поново репродуковати. Ви ћете морати да обновите базу података користећи -reindex-chainstate.</translation>
    
ERR
The translation is in Serbian Cyrillic instead of the required Ijekavian Latin script ('sr@ijekavianlatin'). The text should be in Latin script, not Cyrillic.

Correct translation:
Blokove nije moguće ponovo reprodukovati. Moraćete da obnovite bazu podataka koristeći -reindex-chainstate.
```

<!-- cache_translation_check_sr@ijekavianlatin_1b8fb734655cbadcdef962f46c3a3fc84ed492bc7f5421f136f31c9376abcce6 -->
```
        <source>Error loading %s: Wallet requires newer version of %s</source>
        <translation>Грешка током учитавања %s: Новчаник захтева новију верзију %s</translation>
    
ERR
The translation is in Cyrillic script, but 'sr@ijekavianlatin' specifies Ijekavian Serbian in Latin script. The content is otherwise accurate but uses the wrong script.

Correct translation:
Greška tokom učitavanja %s: Novčanik zahtijeva noviju verziju %s
```

<!-- cache_translation_check_sr@ijekavianlatin_52fc451e54cad0e961b0609a2c8ee72c49e9b0856483e13210ab4aaef1811962 -->
```
        <source>Error: Disk space is low for %s</source>
        <translation>Грешка: Простор на диску је мали за %s</translation>
    
ERR
The translation uses Cyrillic script ("Грешка: Простор на диску је мали за %s"), but 'sr@ijekavianlatin' requires Latin script with Ijekavian spelling.

Correct translation:
Greška: Prostor na disku je mali za %s
```

<!-- cache_translation_check_sr@ijekavianlatin_485f524f45c68b32fe4d4720a481ba5b70b7a436ad8a52e8fd04380960ac4441 -->
```
        <source>Prune cannot be configured with a negative value.</source>
        <translation>Скраћење се не може конфигурисати са негативном вредношћу.</translation>
    
ERR
The translation is in Serbian Cyrillic script, but 'sr@ijekavianlatin' requires the Ijekavian Latin script. Additionally, "скраћење" should be written as "skraćenje", and "вредношћу" as "vrijednošću", respecting the Ijekavian dialect.

Correct translation:
Skraćenje se ne može konfigurisati sa negativnom vrijednošću.
```

<!-- cache_translation_check_sr@ijekavianlatin_2a492305166bc20b176871c70024f3d46f937f9ba957c6dc327da50662c3f104 -->
```
        <source>The transaction amount is too small to pay the fee</source>
        <translation>Износ трансакције је сувише мали да се плати трансакција</translation>
    
ERR
The translation contains an error: "да се плати трансакција" incorrectly translates to "to pay the transaction" instead of "to pay the fee." Also, "трансакција" (transaction) should be "накнада" (fee). Additionally, "суviše" is better rendered as "превише" or "премали" for ijekavian standard.

Correct translation:
Iznos transakcije je previše mali da bi pokrio naknadu.
```

<!-- cache_translation_check_sr@ijekavianlatin_3e8842711946b7215b95587d00923f2ffb1a44be4eb46212194fe825e83b9e13 -->
```
        <source>This is experimental software.</source>
        <translation>Ово је експерименталн софтвер.</translation>
    
ERR
The translation is in Cyrillic script instead of Latin script, and there is a spelling error ("експерименталн" should be "eksperimentalni"). For 'sr@ijekavianlatin', the text must be in ijekavian Latin script.

Correct translation:
Ovo je eksperimentalni softver.
```

<!-- cache_translation_check_sr@ijekavianlatin_5e3ff1e678f4df621d1ca0dc103641c44e1841a25c3cb00e2f76682a6d3dbfe0 -->
```
        <source>Unable to create the PID file '%s': %s</source>
        <translation>Стварање PID документа '%s': %s није могуће</translation>
    
ERR
The translation has multiple issues:
1. The 'sr@ijekavianlatin' language code specifies the Ijekavian Latin variant of Serbian, but the translation is written in Cyrillic script, which is not appropriate.
2. The translation is slightly inaccurate. The phrase "document" ('документа') is not commonly used for 'file' in this context; 'fajl' is preferred. Also, the word order does not match the source's implication that the error is due to some issue (given by %s).

Correct translation:
Nije moguće kreirati PID fajl '%s': %s
```

<!-- cache_translation_check_sr@ijekavianlatin_6aceb26978c4adf1eb952513bced3f4ef969f023716742fea9e64207e5bbda2c -->
```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Новчаник треба да буде преписан: поновно покрените %s да завршите</translation>
    
ERR
The translation is in Cyrillic script, but 'sr@ijekavianlatin' requires Latin script. Additionally, the translation is accurate otherwise.

Correct translation:
Novčanik treba da bude prepisan: ponovo pokrenite %s da završite
```
</details>

Number of issues: 195.
