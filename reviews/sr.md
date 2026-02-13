# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>sr</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bsr%5D%20request)


<!-- cache_translation_check_sr_48df7cc335dbe779a8dc38d57a7fef7d3e72fe7bd58d739ee04ec6476a7cbf98 -->
```
        <source>Choose the address to receive coins with</source>
        <translation>Одабери адресу за примање</translation>
    
ERR
The translation omits the word "coins" ("новци" or "новчићи") present in the source, which makes the sentence less clear in the Bitcoin context. The phrase "за примање" is incomplete in conveying the full meaning "to receive coins with". Additionally, the aspect "to receive coins with" is somewhat more idiomatically rendered in Serbian as "адресу на коју ћете примити новчиће".

Correct translation:
Одаберите адресу на коју ћете примити новчиће
```

<!-- cache_translation_check_sr_fe139c62a0de1618c49d9e08cd49394c7f7148c140e4a7a27b4bf942bc3958d5 -->
```
        <source>&amp;Copy Address</source>
        <translation>&amp;Копирај Адресу</translation>
    
ERR
Translation is mostly correct but has inconsistent capitalization. In Serbian Cyrillic UI labels the second word should be lowercase ("адресу"). The ampersand is present exactly once, which is correct.

Correct translation:
&Копирај адресу
```

<!-- cache_translation_check_sr_c1a7d5de7df59bc21d3304b8b7bd44ada476251a40c6607a771152bbb30a041f -->
```
        <source>Copy &amp;Label</source>
        <translation>Копирај &amp; Обележи</translation>
    
ERR
The Serbian translation is awkward and has spacing issues. Problems:
- The wording "Копирај Обележи" is semantically odd (literally "Copy Mark/Label" but phrased unnaturally).
- The & is written as &amp; (which is correct in XML) but surrounded by spaces ("Копирај &amp; Обележи"), introducing an extra space after the ampersand and before the next word. The original had no space between & and the following word; the shortcut marker should appear immediately before the shortcut letter.
- Prefer a more natural Serbian phrase for "Copy Label" such as "Копирај ознаку" and place the & directly before the shortcut letter.

Corrected translation (XML-safe):
<translation>Копирај &amp;Ознаку</translation>
```

<!-- cache_translation_check_sr_15ebeb459b08e31b755855b78a04134bb33cd2275e96967ab6d6d8995e81c811 -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Унеси нову приступну фразу за новчаник&lt;br/&gt;Молимо користи приступну фразу од десет или више насумичних карактера&lt;b&gt;,или&lt;b&gt;осам или више речи&lt;/b&gt;.</translation>
    
ERR
There are several issues with the Serbian translation:
- "приступну фразу за новчаник" should be "приступну фразу за новчаник." (missing period at the end of the first sentence)
- HTML tags are misplaced: "&lt;b&gt;" is not properly closed around "десет или више насумичних карактера" (it is closing after "или").
- Extra spacing issues after punctuation (missing space after a comma).
- The sentence "или осам или више речи" is missing proper context and HTML formatting.

Correct translation:
Унесите нову приступну фразу за новчаник.&lt;br/&gt;Молимо вас да користите приступну фразу од &lt;b&gt;десет или више насумичних карактера&lt;/b&gt; или &lt;b&gt;осам или више речи&lt;/b&gt;.
```

<!-- cache_translation_check_sr_47dff3504bc1da23c387354bedb207492f159e9004c6e6c4dcd3a9083ce9483a -->
```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Упамти, шифрирање новчаника не може у потуности заштити твоје биткоине од крађе од стране малвера инфицира твој рачунар.</translation>
    
ERR
There are several issues:
1. "у потуности" should be "у потпуности" (spelling error).
2. "малвера инфицира твој рачунар" is ungrammatical; it should be "малвер који инфицира твој рачунар" or simply "малвера који је инфицирао твој рачунар".
3. The formal tone is inconsistent; the source is somewhat neutral, but the translation uses informal "твоје". If the UI uses "ви", use "ваш".

Correct translation:
Упамтите да шифрирање новчаника не може у потпуности заштитити ваше биткоине од крађе од стране малвера који инфицира ваш рачунар.
```

<!-- cache_translation_check_sr_d94067653d4671b5acc2e88f9919069687c42b4e5e2dc3e23d0a3341cc018c4e -->
```
        <source>Warning: The Caps Lock key is on!</source>
        <translation>Упозорање Caps Lock дугме укључено!</translation>
    
ERR
The translation is mostly correct, but it is missing the verb "је" ("is") for full clarity, which matches the original phrase structure. Also, the phrase should ideally be: "Упозорење: Caps Lock дугме је укључено!"

Correct translation:
Упозорење: Caps Lock дугме је укључено!
```

<!-- cache_translation_check_sr_d568b4725118b0579b3d9efde1a249dc9930ccefe6f9a2e771f9b8627fa31bfa -->
```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>Унеси Биткоин адресу, (нпр %1)</translation>
    
ERR
There is an unnecessary comma after "адресу" and missing period at the end. In Serbian, it is also more idiomatic to use "на пример" or "например" rather than "нпр", which is less formal. Additionally, the abbreviation should be followed by a period. The correct translation should be:

Унеси Биткоин адресу (нпр. %1)
```

<!-- cache_translation_check_sr_1f2e72c7a6542a45a6e77169c66ee548082d31f4dd9935c97cdb3ab18a6f0d10 -->
```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>Блокирана предаја</translation>
    
ERR
The translation "Блокирана предаја" means "Blocked relay" or "Blocked transmission" in Serbian, which is incorrect. The correct translation of "Block Relay" (as in a peer connection type relaying block data) should be "Релеј блокова" or "Пренос блокова".

Correct translation:
Релеј блокова
```

<!-- cache_translation_check_sr_eda46644e93f482f50a2eee4c1c1c351b8c672f379aaaa4704fa66b4df93f27b -->
```
        <source>Create a new wallet</source>
        <translation>Направи нови ночаник</translation>
    
ERR
There is a spelling error in the translation: "ночаник" should be "новчаник". Also, "направи" is understandable but "креирај" or "направите" (formal) is more commonly used in software contexts. 

Correct translation:
Креирај нови новчаник
```

<!-- cache_translation_check_sr_fff5273037a07b7da18ea71a61376e65170d4c4776d8d2610f8acfd3999f0d4c -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation>&amp;Енкриптуј новчаник</translation>
    
ERR
The translation is correct Serbian (Cyrillic) and the ampersand shortcut is preserved, but it omits the ellipsis (…) present in the source. Add the ellipsis to match the source.

Correct translation:
&amp;Енкриптуј новчаник…
```

<!-- cache_translation_check_sr_f11237f7fa112919b8fb5c26758d3d2f3eebab0d7eab6db03f0a9bd51b053129 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>&amp;Резервна копија новчаника</translation>
    
ERR
The translation is mostly correct Serbian, and the ampersand for the shortcut is present exactly once. However it omits the trailing ellipsis (…) from the source.

Correct translation:
&amp;Резервна копија новчаника…
```

<!-- cache_translation_check_sr_db0498fd505b7b99d8f5435bf20656e0d2423847202599f303cdcb18e620b8c8 -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>&amp;Измени приступну фразу</translation>
    
ERR
The translation is missing the trailing ellipsis (…) present in the source. Also stylistically "Измени приступну фразу" is acceptable, but keep the ellipsis for consistency with the source UI.

Correct translation:
&amp;Измени приступну фразу…
```

<!-- cache_translation_check_sr_4b72daf23e278c306a08d5af3792168541fbb18e6efa5b2d53bd2fa477d44c46 -->
```
        <source>Sign &amp;message…</source>
        <translation>Потпиши &amp;поруку</translation>
    
ERR
The translation is mostly correct Serbian (Cyrillic) and the ampersand/shortcut is present, but it is missing the ellipsis (…) from the source. The source has an ellipsis after "message" which should be preserved.

Correct translation:
Потпиши &amp;поруку…
```

<!-- cache_translation_check_sr_32d62ec62d1a28598065c49b6e80fb56d60282ab997e9dab3b81b1adf929e8c4 -->
```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Потписуј поруку са своје Биткоин адресе као доказ да си њихов власник</translation>
    
ERR
The translation has a few issues:
1. The original text is plural: "addresses" and "messages", but the translation is singular ("поруку", "адресе").
2. The pronoun "њихов" (their) refers to addresses, which should agree in number.
3. The instruction voice ("Sign messages") in English is imperative, but the translation uses the informal singular "Потписуј", which can imply habitual action, rather than a direct imperative ("Потпиши").
4. The translation says "са своје Биткоин адресе" ("from your Bitcoin address") instead of "with your Bitcoin addresses".
5. The translation switches between singular and plural inconsistently.

Correct translation:
Потпишите поруке својим Биткоин адресама да докажете да сте њихов власник
```

<!-- cache_translation_check_sr_689f9902aaf291b9c3c0d1c5168b7a037fb0168e036a7873aec3145d84f8eb2a -->
```
        <source>&amp;Verify message…</source>
        <translation>&amp;Верификуј поруку</translation>
    
ERR
The translation is mostly correct (Serbian Cyrillic, ampersand present), but it is missing the trailing ellipsis (…) present in the source.

Correct translation:
&amp;Верификуј поруку…
```

<!-- cache_translation_check_sr_f7ce4465cb80021c706e81004941157e761bb5daf415dc76d95ade967bc048fe -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>&amp;Учитава ”PSBT” из датотеке…</translation>
    
ERR
The Serbian translation uses the wrong verb form ("Учитава" = "loads" in present tense) and encloses PSBT in nonstandard quotation marks. It should use an imperative/infinitive form suitable for a menu item and not add quotes around PSBT. The ampersand is present once which is correct.

Correct translation:
&Учитај PSBT из датотеке…
```

<!-- cache_translation_check_sr_f5c174e0275310d002193f453e96288c449bf659654de2dc7cc0292fd16c5347 -->
```
        <source>Open &amp;URI…</source>
        <translation>Отвори &amp;URI</translation>
    
ERR
The translation is mostly correct (Cyrillic Serbian), but it omits the trailing ellipsis (…) present in the source. Also ensure the ampersand for the shortcut remains exactly once.

Correct translation:
Отвори &amp;URI…
```

<!-- cache_translation_check_sr_d8fcd325544250661ba66f9dcff88d01533d58e3bbff8e4e6b9e68d16c72d496 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>Учитај ”PSBT” из привремене меморије</translation>
    
ERR
Problems:
- The translation is missing the required '&' shortcut marker (the source contains "&clipboard" so the translation must include a single '&').
- The source ends with an ellipsis (…) which is missing in the translation.
- Unnecessary quotation marks around PSBT; not required.

Suggested correct translation (include one '&' and the ellipsis):
Учитај PSBT из &привремене меморије…

(You can place the '&' elsewhere if a different shortcut placement is desired, e.g. &Учитај PSBT из привремене меморије…)
```

<!-- cache_translation_check_sr_ecf81414049c5ffc6667451457e92e7ce32b74894cdfff7ee7cd45d31230a6ec -->
```
        <source>Node window</source>
        <translation>Ноде прозор</translation>
    
ERR
"Ноде прозор" transliterates the English word "Node" instead of translating it into Serbian. The correct translation for "Node" in Serbian, in the context of Bitcoin, is "Чвор".

Correct translation:
Прозор чвора
```

<!-- cache_translation_check_sr_df62365ad4ac671da0c1a61a2ed295efe643ffddc0f52d245094285c6fa233d8 -->
```
        <source>Mask the values in the Overview tab</source>
        <translation>Филтрирај вредности у картици за преглед</translation>
    
ERR  
The translation is inaccurate. "Mask the values" means to hide or obscure them, not to filter. The Serbian translation says "Filter the values in the overview tab," which changes the meaning.

Correct translation:  
Маскирај вредности на картици прегледа
```

<!-- cache_translation_check_sr_9e55b85bae0f586fe8146321e402a1acf5162e201db71a24861f31ef924a373e -->
```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Прикажи картицу са ”Клијентима”</translation>
    
ERR
The translation uses "Клијентима" for "Peers", which is inaccurate in the Bitcoin context. "Peers" should be "чворови" (nodes/peers), not "клијенти" (clients).

Correct translation:
Прикажи картицу са „чворовима“
```

<!-- cache_translation_check_sr_ed93ef579617dc434f9d57fbac92c52d5abb24f652a0ead56dcc244fd5a5e7c8 -->
```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Новчаник јс &lt;b&gt;шифриран&lt;/b&gt; и тренутно &lt;b&gt;откључан&lt;/b&gt;</translation>
    
ERR
There is a typo in the translation: "јс" should be "је" ("is" in Serbian). The rest of the translation is correct, including the formatting and spacing.

Correct translation:
Новчаник је &lt;b&gt;шифриран&lt;/b&gt; и тренутно &lt;b&gt;откључан&lt;/b&gt;
```

<!-- cache_translation_check_sr_ec625a931b16cd72c005bdcac9183eecbdaa41351aaeaf4ee819ee92d88078d6 -->
```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Новчаник јс &lt;b&gt;шифрован&lt;/b&gt; и тренутно &lt;b&gt;закључан&lt;/b&gt;</translation>
    
ERR
There is a typo in the translation: "јс" should be "је".

Correct translation:
Новчаник је &lt;b&gt;шифрован&lt;/b&gt; и тренутно &lt;b&gt;закључан&lt;/b&gt;
```

<!-- cache_translation_check_sr_d3c67ee6f7daa4d5ec3f613ccf586301db99122f3390c8488657d75dbb5c4432 -->
```
        <source>Copy &amp;label</source>
        <translation>Копирај &amp;означи</translation>
    
ERR
The translation uses the verb "означи" (imperative "mark!") instead of the noun in accusative required by "Copy label". It is therefore incorrect/odd in Serbian.

Correct translation:
Копирај &ознаку
```

<!-- cache_translation_check_sr_4976c57c852456d2428e3c8dd6019732c4fa415d80d052627d4b252a3adb4504 -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>Kopiraj transakciju &amp;ID i izlazni index</translation>
    
ERR
The translation has grammatical/word-choice issues. "transakciju &ID" is awkward — the genitive "ID transakcije" is correct in Serbian, and "index" should be "indeks". The ampersand exists once (good) but should be placed with the corrected wording.

Correct translation:
Kopiraj &ID transakcije i izlazni indeks
```

<!-- cache_translation_check_sr_0e3a2093f7a81f0eb8be8107ee3cd0e220d482f571a1f346de0aab09f9507d17 -->
```
        <source>L&amp;ock unspent</source>
        <translation>Закључај непотрошено</translation>
    
ERR
The translation is fine in meaning ("Закључај непотрошено" = "Lock unspent"), but it is missing the required shortcut ampersand (&). The source contains a single & and the translation must also contain exactly one.

Correct translation (with ampersand):
&Закључај непотрошено

(Alternatively, for slightly more natural wording: "&Закључај непотрошена средства".)
```

<!-- cache_translation_check_sr_f28249d0c3e5b5f1afdeb988a8cca49aa674f8948e82f1a3507e5b067cb3a74a -->
```
        <source>&amp;Unlock unspent</source>
        <translation>Откључај непотрошено</translation>
    
ERR
The translation is missing the shortcut ampersand (&) and has a grammatical issue: "непотрошено" is awkward/unnatural in Serbian in this context. It should also include the & exactly once.

Corrected translation (with ampersand and more natural phrasing):
&Откључај непотрошене
```

<!-- cache_translation_check_sr_99505440570a1684db35109575c7f69460952f2c22e032d1c62b881db24be233 -->
```
        <source>Create wallet warning</source>
        <translation>Направи упозорење за новчаник</translation>
    
ERR
The translation is inaccurate. The original phrase "Create wallet warning" refers to a warning about wallet creation, not the action of making a warning for a wallet. The translation suggests creating (making) a warning, which changes the meaning.

Correct translation:
Упозорење при креирању новчаника
```

<!-- cache_translation_check_sr_e24d072e432327a2e5cb7899dad8b695bef3114e66e80c8ac08a7757cbd029fa -->
```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>Da li si siuran da želiš da preneseš novčanik &lt;i&gt;%1&lt;/i&gt;? </translation>
    
ERR
There are minor issues with spelling and formality in the Serbian translation. "Siuran" is a typo; the correct word is "siguran". Also, the style is somewhat informal ("da želiš da"), which can be replaced with a more standard form. Additionally, there is an unnecessary trailing whitespace at the end.

Correct translation:
Da li ste sigurni da želite da migrirate novčanik &lt;i&gt;%1&lt;/i&gt;?
```

<!-- cache_translation_check_sr_0e5ebeaa2b4c8310a758c3f89ee07e61fe2259baf7fb67d9349b76bc1225f8a6 -->
```
        <source>Migration Successful</source>
        <translation>Prenošenje novčanika je uspešno</translation>
    
ERR
The translation is inaccurate. The source text "Migration Successful" is translated as "Prenošenje novčanika je uspešno", which means "Wallet transfer is successful". The word "novčanika" (wallet) is not present in the source and is an addition. Additionally, the translation is more verbose than necessary.

Correct translation:
Migracija je uspešna
```

<!-- cache_translation_check_sr_e30ba362aab39a95655ce8c4a9abb481c5214d1b5638fa6a286941d3b67fa1d1 -->
```
        <source>Opening Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the open wallet progress window which indicates to the user which wallet is currently being opened.</extracomment>
        <translation>Отвањаре новчаника &lt;b&gt;%1&lt;/b&gt;</translation>
    
ERR
There is a spelling error in the Serbian word "Отвањаре". The correct word is "Отварање". Additionally, the ellipsis (…) from the source is missing in the translation. The rest, including the %1 specifier, is correct.

Correct translation:
Отварање новчаника &lt;b&gt;%1&lt;/b&gt;…
```

<!-- cache_translation_check_sr_b98d86f5e98866db772ecad2c1cf89dd6b1e0bc517a84426e083028f9a310057 -->
```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Онемогући приватни кључ за овај новчаник. Новчаници са онемогућеним приватним кључем неће  имати приватни кључ и не могу имати HD семе или увезени приватни кључ. Ова опција идеална је за новчанике који су искључиво за посматрање.</translation>
    
ERR
There are inconsistencies between the plural and singular forms used for "private keys" and spacing errors (double space after "неће"). "Приватни кључ" (singular) is used instead of "приватни кључеви" (plural) which can mislead the meaning. Also, the original English references "wallets" (plural), and the translation sometimes shifts between singular and plural inconsistently. 

Correct translation:
Онемогући приватне кључеве за овај новчаник. Новчаници са онемогућеним приватним кључевима неће имати приватне кључеве и не могу имати HD семе или увезене приватне кључеве. Ово је идеално за новчанике који служе само за посматрање.
```

<!-- cache_translation_check_sr_e0d3b5109cb2d7193590368f17f07152dded2395f9b686fff60399a9c5a0d3a7 -->
```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Најмање %1 GB подататака биће складиштен у овај директорјиум који ће временом порасти.</translation>
    
ERR
There are several issues with the Serbian translation:
1. "подататака" is a typo; it should be "података".
2. "директорјиум" is also a typo/misspelling; it should be "директоријум".
3. The structure "биће складиштен у овај директорјиум" is awkward; more appropriate would be "ће бити сачувано у овом директоријуму".
4. The English source uses "will be stored", so "ће бити сачувано" is better than "биће складиштен".
5. The plural form of "ГБ" should be "GB" (Latin letters, as is often kept in Serbian technical usage), but that is minor and acceptable.

Correct translation:
Најмање %1 GB података ће бити сачувано у овом директоријуму и количина ће с временом расти.
```

<!-- cache_translation_check_sr_6e8ec9aa0b8539fe8f2768e3135f1b544e97b494891f9e190dc6898c49593f4c -->
```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Најмање %1 GB подататака биће складиштен у овај директорјиум.</translation>
    
ERR
The translation contains several errors:
1. "Најмање" means "at least", not "approximately". The correct word for "approximately" in Serbian is "Приближно" or "Око".
2. "подататака" is a typo, the correct word is "података".
3. "биће складиштен" should be "биће сачувано" or "ће бити сачувано" for "will be stored".
4. "у овај директорјиум" should be "у овај директоријум".

Correct translation:
Приближно %1 GB података ће бити сачувано у овом директоријуму.
```

<!-- cache_translation_check_sr_4c58c494cbe87108e861c5e59fee14a96a60ea89ccc6bd6f92530d8218c27532 -->
```
        <source>%1 will download and store a copy of the Bitcoin block chain.</source>
        <translation>%1 биће преузеће и складиштити копију Биткоин ланца блокова.</translation>
    
ERR
The translation has grammatical issues; specifically, "биће преузеће и складиштити" is incorrect. "Преузеће" and "биће" are redundant, and the verb "складиштити" should be coordinated properly.

Correct translation:
%1 ће преузети и сачувати копију Биткоин блокчејна.
```

<!-- cache_translation_check_sr_f2a89d713f9f8eecce461706901717f83b19045b58ee4d030c64a8faa01b9fd2 -->
```
        <source>Error: Specified data directory "%1" cannot be created.</source>
        <translation>Грешка: Одабрана датотека  "%1" не може бити креирана.</translation>
    
ERR
The translation uses "датотека" which means "file" instead of "директоријум" which means "directory". Also, the correct phrase for "specified" here should be "наведени", not "одабрана". There is also an extra space after the word "датотека".

Correct translation:
Грешка: Намењени директоријум „%1“ не може бити креиран.
```

<!-- cache_translation_check_sr_900c39e2a27e53fd09cf2851c4333f16aea74193323c46dd13b9515a759cc5db -->
```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Налепите адресу из базе за копирање</translation>
    
ERR
The translation "Налепите адресу из базе за копирање" is inaccurate. The term "база за копирање" is not a correct term for "clipboard" in Serbian; the correct word is "клипборд" or "привремена меморија." Additionally, "Налепите" could be replaced with "Налепи" to match common UI imperative tone.

Correct translation:
Налепи адресу из клипборда
```

<!-- cache_translation_check_sr_2e5552db7c9227a626eed1a9be537345e49294d1a0aa129317b27378a6284845 -->
```
        <source>&amp;Main</source>
        <translation>&amp;Главни</translation>
    
ERR
"Главни" is not the correct form in Serbian for a standalone label "Main". Use the neuter or feminine form depending on context; a safe UI translation is "&Главно" (or "&Главна" if the target noun is feminine, e.g. "страна/страница").

Correct translation suggestion:
&Главно
```

<!-- cache_translation_check_sr_6c2e6271f15953db62c464454a57235efecc5c15f1f70df0f453cae06add0d8b -->
```
        <source>Size of &amp;database cache</source>
        <translation>Величина кеша базе података</translation>
    
ERR
The translation is missing the shortcut ampersand (&) present in the source. Otherwise the Serbian text is acceptable.

Correct translation (with & placed before the word corresponding to "database"):
Величина кеша &базе података
```

<!-- cache_translation_check_sr_4a607db8c92fdfba8d7090eca4db9848cd71ec535445ae2f8ddad7a83c07c5ad -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>Број скрипти и CPU за верификацију</translation>
    
ERR
The translation changes the meaning (it says "scripts and CPU for verification" instead of "script verification threads") and it does not preserve the shortcut (&). 

Correct translation:
Број нити за &верификацију скрипти
```

<!-- cache_translation_check_sr_bed8f81c88c55e0761966617cba9308895643eeee3ca644a5ddb9d6b4b710345 -->
```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Приказује се ако је испоручени уобичајени SOCKS5 проxy коришћен ради проналажења клијената преко овог типа мреже. </translation>
    
ERR
There are a few problems with the translation:
1. The original English says "Shows if the supplied...", which is impersonal, but the Serbian uses a more personal/active voice ("Приказује се ако је...").
2. Incorrect rendering of "proxy" as "проxy" (the "x" is not in Cyrillic).
3. "клијената" translates to "clients", but the appropriate term for "peers" in the context of Bitcoin is "чворова" (nodes/peers).
4. Minor format issue: stray space at the end of the sentence.

Correct translation:
Показује да ли се испоручени подразумевани SOCKS5 прокси користи за повезивање са чворовима преко ове врсте мреже.
```

<!-- cache_translation_check_sr_d693e0ad3eaa0c151f558614340d015b1c6c481884988075b09e66fc886a489d -->
```
        <source>&amp;Reset Options</source>
        <translation>&amp;Ресет Опције</translation>
    
ERR
The translation "&Ресет Опције" is understandable but not natural Serbian. It mixes a transliterated English noun "Ресет" with "Опције" and uses a noun phrase rather than an imperative command as in the source. Also more natural Serbian would use a verb form like "Ресетуј опције" or a native word such as "Поништи опције".

Correct suggestions (keeping the & for the shortcut exactly once):
- &Ресетуј опције
- &Поништи опције
- &Врати подразумеване поставке (if you prefer "Restore defaults" nuance)
```

<!-- cache_translation_check_sr_7f41849d827d608340c098c4f9b8a465587eee6dac06996db83d4fddcdc5a8a4 -->
```
        <source>Prune &amp;block storage to</source>
        <translation>Сакрати &amp;block складиштење на</translation>
    
ERR
The translation is problematic: it mixes Cyrillic and Latin scripts (keeps "block" in English), and the phrasing is awkward. Also the ampersand is kept as &amp; which is fine in XML, but the translated words should be fully in Serbian and grammatically correct.

Correct translation:
<translation>Скрати &amp;складиштење блокова на</translation>
```

<!-- cache_translation_check_sr_74677d4ac1ee4dc7fcf0c115c25106213a635c6c27c9bb213bae4cb0082fa90f -->
```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Враћање ове опције захтева да поновно преузимање целокупонг блокчејна.</translation>
    
ERR
There is a grammatical error in the translation, specifically in "понвно преузимање целокупонг блокчејна" - "целокупонг" is incorrect; the correct form is "целокупног", and sentence structure can be improved for clarity.

Correct translation:
Враћање ове опције захтева поновно преузимање целокупног блокчејна.
```

<!-- cache_translation_check_sr_ac986864f76861a6ef9c01f5d3838dc7fec0d3d479779830b149e23efd8ce7ea -->
```
        <source>Enable R&amp;PC server</source>
        <extracomment>An Options window setting to enable the RPC server.</extracomment>
        <translation>Omogući R&amp;PC server</translation>
    
ERR
The Serbian verb is misspelled: "Omoguči" uses č instead of the correct ć in "Omogući".

Correct translation:
Omogući R&amp;PC server
```

<!-- cache_translation_check_sr_1ab27e36c8536348eb7c3420a8479d51fc27cce7f84584967da69cb1aaa6008f -->
```
        <source>Enable coin &amp;control features</source>
        <translation>Омогући опцију контроле новчића</translation>
    
ERR
The translation is missing the shortcut ampersand (&) and is slightly off in wording ("опцију контроле новчића" = "option of coin control" vs. "coin control features"). Also ensure exactly one & is present.

Correct translation:
<translation>Омогући функције &контроле новчића</translation>
```

<!-- cache_translation_check_sr_bf34ccfc39bd144359a77cfe12e64a886fbe72dd7ab4003c76462a81e4285492 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>&amp;Троши непотврђени кусур</translation>
    
ERR
The Serbian translation uses "Троши" (3rd person singular present) which is grammatically incorrect for a UI label. It should be an imperative or infinitive form. Also the ampersand shortcut exists (good).

Correct translation:
&Трошите непотврђени кусур
```

<!-- cache_translation_check_sr_6ef8e317e053328bbe6291c14c4e93aef0637ae91b01c35fe835884d7ab0ddb8 -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Дозволи долазеће конекције.</translation>
    
ERR
Problems:
- The translation adds a trailing period (.) while the source has none.
- The translation is missing the shortcut marker '&' (the source includes a single '&' in "incomin&g"); the translation must include exactly one '&'.
- Minor style: "конекције" is fine, but ensure no extra punctuation.

Correct translation (with one '&' and no trailing period):
Дозволи долазеће &конекције
```

<!-- cache_translation_check_sr_3e1c31380edd8079c4b6f046c1f44bfe3cb4013aa454c18cdbbba954e75326af -->
```
        <source>Connect to the Bitcoin network through a SOCKS5 proxy.</source>
        <translation>Конектуј се на Биткоин мрежу кроз SOCKS5 проксијем.</translation>
    
ERR
The translation uses the informal imperative "Конектуј се", but a more standard and formal Serbian phrasing would use "Повежите се". Also, "кроз SOCKS5 проксијем" is incorrect; it should be "преко SOCKS5 проксија". 

Correct translation:
Повежите се на Биткоин мрежу преко SOCKS5 проксија.
```

<!-- cache_translation_check_sr_9b7e5978450412193556bc34436fe8a0eed34d388df75bd97caba09b39c01fa7 -->
```
        <source>&amp;Connect through SOCKS5 proxy (default proxy):</source>
        <translation>&amp;Конектуј се кроз SOCKS5 прокси (уобичајени прокси):</translation>
    
ERR
The translation uses a non-standard anglicized verb "Конектуј се" and awkward noun form "прокси". It should use more natural Serbian phrasing and correct noun case.

Correct translation:
&Повежи се преко SOCKS5 проксија (подразумевани прокси):
```

<!-- cache_translation_check_sr_b748b2b1a00e41e8836275f6b45880a1c456e64c02adbb59dedd7b230c7fbb0e -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>&amp;минимизирај у доњу линију, уместо у програмску траку</translation>
    
ERR
The Serbian text is understandable but uses an incorrect/awkward phrase "доњу линију" for "tray" and slightly odd word order. Better UI phrasing uses "ладицу" or "sistemska ladica / traka obaveštenja".

Correct translation suggestions:
&Minimiziraj u ladicu umesto na traku zadataka
or (Cyrillic):
&Минимизирај у ладицу уместо на траку задатака
```

<!-- cache_translation_check_sr_71f2b0363d4d3ec75f8848720b5326054f7c475404f87da0f73693af7e67b949 -->
```
        <source>M&amp;inimize on close</source>
        <translation>Минимизирај при затварању</translation>
    
ERR
The translation is correct in meaning but is missing the shortcut indicator (&). The source contains a single '&' which must be present exactly once in the translation. No other format specifiers or spacing issues.

Correct translation (include one &):
&Минимизирај при затварању
```

<!-- cache_translation_check_sr_54d86df503dd736bd5cda8ec5c6cd93126f1bddd3395cfcfce32c9c6c7a0520b -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Користите посебан СОЦКС&amp;5 прокси да бисте дошли до вршњака преко услуга Тор онион:</translation>
    
ERR
The translation is understandable but has issues:
- Uses Cyrillic transliteration "СОЦКС" instead of the common ASCII "SOCKS" (protocol names are usually left in Latin).
- The phrase "да бисте дошли до вршњака" is awkward in networking context; better phrasing is "за повезивање са вршњацима" or "да бисте се повезали са вршњацима".
- "Тор онион" is awkward; it's better to use "Tor .onion услуга(ма)" or "Tor .onion услuga" (plural: услуга/услугама).

Corrected translation suggestion:
Користите посебан SOCKS&amp;5 прокси за повезивање са вршњацима преко Tor .onion услуга:
```

<!-- cache_translation_check_sr_c110505a3dc04284a04a851dcf6ad6f36ed44404a36cde8cbd2154b5c3165818 -->
```
        <source>&amp;OK</source>
        <translation>&amp;Уреду</translation>
    
ERR
The translation uses the Cyrillic word "Уреду" as one word, but the correct Serbian expression is two words "У реду". Also ensure the ampersand remains exactly once (it is present). 

Correct translation:
&amp;У реду
```

<!-- cache_translation_check_sr_61756bdc9b87e53082f66ff2e5389a58dfa0ed82a343eb456b6534641460d2f1 -->
```
        <source>Signed %1 inputs, but more signatures are still required.</source>
        <translation>Потписано %1 поље, али је потребно још потписа.</translation>
    
ERR
The translation is inaccurate. The word "inputs" in the Bitcoin context rarely translates as "поље" ("field") in Serbian; the proper term is "улаза" ("inputs"). Additionally, the plural form should be used. The rest of the sentence is acceptable.

Correct translation:
Потписано је %1 улаза, али је потребно још потписа.
```

<!-- cache_translation_check_sr_918bfac7e1cace4f1796c4686382e92b5e609ea99e9b65abb165ce3f5caf3314 -->
```
        <source>Transaction has %1 unsigned inputs.</source>
        <translation>Трансакција има %1 непотписана поља.</translation>
    
ERR
The translation is inaccurate. The term "inputs" in Bitcoin context should be "улази" (inputs), not "поља" (fields). "Поља" is misleading in this context. Also, the format specifier %1 is correctly preserved.

Correct translation:
Трансакција има %1 непотписаних улаза.
```

<!-- cache_translation_check_sr_cdbd97358498204e8761f36e069511667c12b9bd067eaafb6451298892c98218 -->
```
        <source>&amp;Save Image…</source>
        <translation>&amp;Сачували слику…</translation>
    
ERR
The Serbian translation uses the past participle "Сачували" which is incorrect for a menu command. It should be an imperative ("Save Image") form. The ampersand is present once and there are no whitespace or format-specifier issues.

Correct translation:
&amp;Сачувај слику…
```

<!-- cache_translation_check_sr_ff78b1c332c5faf478cba98f8897e7083824d4b6e7e8609c45dfdaa09132069a -->
```
        <source>Resulting URI too long, try to reduce the text for label / message.</source>
        <translation>Дати резултат URI  предуг, покушај да сманиш текст за ознаку / поруку.</translation>
    
ERR
The Serbian translation is problematic for multiple reasons:
- "Дати резултат URI предуг" is not grammatically correct or idiomatic. It should convey that the resulting URI is too long.
- The word "URI" is left in Latin script, although it's common to transliterate/leave as URI, this is acceptable but the structure is still awkward.
- "Дати резултат" is not a natural way to say "resulting".
- There is a double space after "URI", which is a whitespace formatting issue.
- "предуг" is a typo; the correct word is "предугачак" or "предугачак".

Correct translation:
Резултујући URI је предугачак, покушај да скратиш текст за ознаку/поруку.
```

<!-- cache_translation_check_sr_09ce93caad835b8f9fe5c49a0fe46223f58cdc853c270227e02b86b3298a6b16 -->
```
        <source>Memory Pool</source>
        <translation>Удружена меморија</translation>
    
ERR
The translation "Удружена меморија" is incorrect. "Memory Pool" in the context of Bitcoin refers to "мемпул" or "меморијски пул", not "удружена меморија" ("pooled/joined memory"), which does not convey the intended technical meaning.

Correct translation:
Мемпул
```

<!-- cache_translation_check_sr_b002aa70561e9f2f2610fee4f487092e9d39df4639dcc2fa2df17fe1897203d8 -->
```
        <source>Select a peer to view detailed information.</source>
        <translation>Одабери колегу да би видели детаљне информације</translation>
    
ERR
The translation is problematic: "колега" is not the correct translation for "peer" in the context of Bitcoin. "Пир" (the transliterated term widely used in this context) or "чвор" ("node") would be more appropriate. Also, "да би видели" is grammatically incorrect; it should match the (you) imperative, so "да видите" is correct.

Correct translation:
Одаберите пира да видите детаљне информације.
```

<!-- cache_translation_check_sr_ecf81414049c5ffc6667451457e92e7ce32b74894cdfff7ee7cd45d31230a6ec -->
```
        <source>Node window</source>
        <translation>Ноде прозор</translation>
    
ERR
"Ноде прозор" transliterates the English word "Node" instead of translating it into Serbian. The correct translation for "Node" in Serbian, in the context of Bitcoin, is "Чвор".

Correct translation:
Прозор чвора
```

<!-- cache_translation_check_sr_397cc41211cda1a731126fd6876da2d54237e6e032f541fba76dea87b2826662 -->
```
        <source>1 d&amp;ay</source>
        <translation>1 дан</translation>
    
ERR
The translation is missing the shortcut marker (&) present in the source. The source has a single & indicating an accelerator; the translation must include exactly one & placed before the chosen shortcut character. Also, the Serbian word "дан" is correct for "day" but needs the &.

Correct translation:
1 д&ан
```

<!-- cache_translation_check_sr_c5422ea6da411cef596981f796e9b2f65f7072a4692f69c21dffb15ba8b4ba41 -->
```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>Добродошли у %1 "RPC” конзолу.
Користи тастере за горе и доле да наводиш историју, и %2 да очистиш екран.
Користи %3 и %4 да увећаш и смањиш величину фонта.
Унеси %5 за преглед доступних комади.
За више информација о коришћењу конзоле, притисни %6
%7 УПОЗОРЕЊЕ: Преваранти су се активирали, говорећи корисницима да уносе команде овде, и тако краду садржај новчаника. Не користи ову конзолу без потпуног схватања комплексности ове команде. %8</translation>
    
ERR
There are several issues with this translation:

1. Typo/Mistranslation: "комади" should be "команди" (commands), not "комади" (pieces).
2. Missing period and misplaced line break after "притисни %6" (should have a period).
3. The translation adds extra spaces at the beginning and end of the warning tags (%7 %8), which may break the intended formatting. The tags should not be separated by space from the warning text.
4. "complexности ове команде" should be "последица команде" or "последица наредбе", as "complexности" (complexity) does not convey the meaning of "ramifications".

Correct translation:
Добродошли у %1 RPC конзолу.
Користите тастере горе и доле за навигацију кроз историју, и %2 за чишћење екрана.
Користите %3 и %4 да повећате или смањите величину фонта.
Укуцајте %5 за преглед доступних команди.
За више информација о коришћењу ове конзоле, укуцајте %6.
%7УПОЗОРЕЊЕ: Преваранти су били активни, говорећи корисницима да овде унесу команде, чиме краду садржај њихових новчаника. Не користите ову конзолу без потпуног разумевања последица команде.%8
```

<!-- cache_translation_check_sr_4420bd642e223e7058851279ba44a863faca7b787d6e7957edf9362ce6214c23 -->
```
        <source>&amp;Label:</source>
        <translation>&amp;Ознака</translation>
    
ERR
The translation is missing the trailing colon present in the source. Also ensure the ampersand for the shortcut remains exactly once (it already does).

Correct translation:
&amp;Ознака:
```

<!-- cache_translation_check_sr_2bfbe2f2c6bd82789295232b724563092ed0660eebf8428c9b76d99d1f18f639 -->
```
        <source>&amp;Message:</source>
        <translation>Poruka:</translation>
    
ERR
The translation is missing the shortcut ampersand (&) from the source. The source contains "&Message:" which indicates a single shortcut marker; the translation should include exactly one &.

Correct translation:
&Poruka:
```

<!-- cache_translation_check_sr_d3c67ee6f7daa4d5ec3f613ccf586301db99122f3390c8488657d75dbb5c4432 -->
```
        <source>Copy &amp;label</source>
        <translation>Копирај &amp;означи</translation>
    
ERR
The translation uses the verb "означи" (imperative "mark!") instead of the noun in accusative required by "Copy label". It is therefore incorrect/odd in Serbian.

Correct translation:
Копирај &ознаку
```

<!-- cache_translation_check_sr_cdbd97358498204e8761f36e069511667c12b9bd067eaafb6451298892c98218 -->
```
        <source>&amp;Save Image…</source>
        <translation>&amp;Сачували слику…</translation>
    
ERR
The Serbian translation uses the past participle "Сачували" which is incorrect for a menu command. It should be an imperative ("Save Image") form. The ampersand is present once and there are no whitespace or format-specifier issues.

Correct translation:
&amp;Сачувај слику…
```

<!-- cache_translation_check_sr_c013accef2bcbab965dade1eb0ea779729747ec3baa378f6711e82c41de615d0 -->
```
        <source>Inputs…</source>
        <translation>Поља...</translation>
    
ERR
The English word "Inputs" in the context of Bitcoin refers to "улази" (inputs to a transaction), not "поља" (which means "fields"). The translation is incorrect.

Correct translation:
Улази...
```

<!-- cache_translation_check_sr_f39fbbc000a30fd081506cf611a5a8bbb95f0e60141c3a0c52ec058a70a68bc0 -->
```
        <source>Set external signer script path in Options -&gt; Wallet</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Подси екстерну скрипту за потписивање у : Options -&gt; Wallet</translation>
    
ERR
The Serbian translation is problematic. The phrase "Подси екстерну скрипту за потписивање у : Options -> Wallet" contains several issues:
1. "Подси" is not a correct Serbian word for "Set". It should be "Поставите".
2. The order and structure are confusing, and there is an unnecessary space before the colon.
3. Options and Wallet are untranslated, but could be left as-is if keeping UI terms in English is the convention.

Correct translation:
Поставите путању до скрипте за екстерно потписивање у Options -> Wallet
```

<!-- cache_translation_check_sr_566f4091d922028011e4cfd151eb5d9e7f69a40c358641d54655bc256330ba59 -->
```
        <source>Cr&amp;eate Unsigned</source>
        <translation>Креирај непотписано</translation>
    
ERR
The translation is Serbian Cyrillic and mostly correct, but it is missing the shortcut ampersand (&) which must appear exactly once. Also the phrase is a bit terse; include the implied noun for clarity.

Suggested correction (with a single & for the shortcut):
Креирај &непотписану трансакцију
```

<!-- cache_translation_check_sr_b8c6c5da9849bdb49ee565a14846c9b24c49a703f73e32abbdf9ae63c58d1f71 -->
```
        <source>Pay &amp;To:</source>
        <translation>Плати &amp;За:</translation>
    
ERR
The translation "Плати &amp;За:" is slightly inaccurate: "Плати за" in Serbian means "pay for" (pay on behalf of), while the source "Pay To:" indicates the recipient (pay to...). Also the ampersand is present (good) but the word choice/case is wrong.

Suggested correct translation:
<translation>Плати &на:</translation>
```

<!-- cache_translation_check_sr_4420bd642e223e7058851279ba44a863faca7b787d6e7957edf9362ce6214c23 -->
```
        <source>&amp;Label:</source>
        <translation>&amp;Ознака</translation>
    
ERR
The translation is missing the trailing colon present in the source. Also ensure the ampersand for the shortcut remains exactly once (it already does).

Correct translation:
&amp;Ознака:
```

<!-- cache_translation_check_sr_c8cedd32ca199fd5704e81a8ad8d430232accc79908cdd568bce5436ade7cdcd -->
```
        <source>Paste address from clipboard</source>
        <translation>Налепите адресу из базе за копирање</translation>
    
ERR
The translation of "clipboard" as "база за копирање" is incorrect and unidiomatic in Serbian. The correct term for "clipboard" is "клипборд" or "привремена меморија". Furthermore, the verb "налепите" is properly used but may be more common as "налепи" in UI commands for consistency with imperative forms. Also, there is no whitespace issue or format specifier.

Correct translation:
Налепи адресу из клипборда
```

<!-- cache_translation_check_sr_6f8140282cc6d60ca80d7d6152977712452059b2b4745f21ccf42aa464a658e8 -->
```
        <source>A message that was attached to the bitcoin: URI which will be stored with the transaction for your reference. Note: This message will not be sent over the Bitcoin network.</source>
        <translation>Порука која је приложена биткоину: URI која ће бити сачувана уз трансакцију ради референце. Напомена: Ова порука се шаље преко Биткоин мреже.</translation>
    
ERR
The translation is problematic. The phrase "Ова порука се шаље преко Биткоин мреже." translates as "This message is sent over the Bitcoin network," which is the opposite of the source text meaning ("This message will not be sent over the Bitcoin network.").

Correct translation:
Порука која је приложена bitcoin: URI-ју и која ће бити сачувана уз трансакцију ради ваше референце. Напомена: Ова порука неће бити послата преко Биткоин мреже.
```

<!-- cache_translation_check_sr_c8cedd32ca199fd5704e81a8ad8d430232accc79908cdd568bce5436ade7cdcd -->
```
        <source>Paste address from clipboard</source>
        <translation>Налепите адресу из базе за копирање</translation>
    
ERR
The translation of "clipboard" as "база за копирање" is incorrect and unidiomatic in Serbian. The correct term for "clipboard" is "клипборд" or "привремена меморија". Furthermore, the verb "налепите" is properly used but may be more common as "налепи" in UI commands for consistency with imperative forms. Also, there is no whitespace issue or format specifier.

Correct translation:
Налепи адресу из клипборда
```

<!-- cache_translation_check_sr_216b367c36f2e08b4c4ba928978a18dae8e6f91f56ea21cc168d01e65a517dc1 -->
```
        <source>Sign &amp;Message</source>
        <translation>Потпис &amp;Порука</translation>
    
ERR
The translation "Потпис &amp;Порука" is not a natural/grammatical Serbian rendering of "Sign &Message". It reads like "Signature &Message" rather than the imperative "Sign message". Use an imperative form or a noun phrase that conveys "Sign Message". Also ensure the accelerator (&) is present exactly once.

Correct translation (Cyrillic, with XML-escaped ampersand):
Потпиши &amp;поруку
```

<!-- cache_translation_check_sr_ba001c9ec59bc7dfe603dddb63bfc2626222765f1e9d19c09e504ec75ca6fb8b -->
```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>%1 порврде</translation>
    
ERR
There is a typo in the translation: "порврде" should be "потврде". The word "порврде" is not a valid Serbian word.

Correct translation:
%1 потврде
```

<!-- cache_translation_check_sr_424f3b02ed675f591d34bdbaa41f658e7ad9f12e5faf10b4e4360e8d777da742 -->
```
        <source>Credit</source>
        <translation>Заслуге</translation>
    
ERR
The Serbian translation "Заслуге" means "merits" or "accomplishments" rather than "credit" in the financial sense, which in this context is likely referring to a credited amount or incoming funds.

Correct translation:
Кредит
```

<!-- cache_translation_check_sr_1365cb3d1680620b6ef8b218bb8c26b85bb127204bfe90f22cfac1102aa5c851 -->
```
        <source>Generated coins must mature %1 blocks before they can be spent. When you generated this block, it was broadcast to the network to be added to the block chain. If it fails to get into the chain, its state will change to "not accepted" and it won't be spendable. This may occasionally happen if another node generates a block within a few seconds of yours.</source>
        <translation>Генерисани новчићи морају доспети %1 блокова пре него што могу бити потрошени. Када генеришете овај блок, он се емитује у мрежу, да би био придодат на ланац блокова. Укупно не успе да се придода на ланац, његово стање се мења у "није прихваћен" и неће га бити могуће потрошити. Ово се може повремено десити уколико други чвор генерише блок у периоду од неколико секунди од вашег.</translation>
    
ERR
There are a few errors:
1. "Укупно не успе да се придода на ланац" is incorrect and awkward; "уколико не успе да се придода на ланац" or "ако не успе да се придода на ланац" is correct.
2. The sentence flow is somewhat unnatural, and "он се емитује у мрежу, да би био придодат на ланац блокова" would be better as "он је емитован у мрежу да би био додат у ланац блокова".
3. "доспети %1 блокова" is unnatural; it should be "сазрети %1 блокова" or more commonly "сазрети током %1 блокова".
4. "периоду од неколико секунди од вашег" should be "у року од неколико секунди након вашег".

Correct translation:
Генерисани новчићи морају сазрети током %1 блокова пре него што могу бити потрошени. Када генеришете овај блок, он је емитован у мрежу да би био додат у ланац блокова. Ако не успе да уђе у ланац, његово стање ће бити промењено у „није прихваћен“ и неће га бити могуће потрошити. Ово се може повремено десити ако неки други чвор генерише блок у року од неколико секунди након вашег.
```

<!-- cache_translation_check_sr_167e8b43a6aacf2d88ed7304a733a4fe218609f561b42ddbe01e00a776b667ec -->
```
        <source>Transaction status. Hover over this field to show number of confirmations.</source>
        <translation>Статус трансакције. Пређи мишем преко поља за приказ броја трансакција.</translation>
    
ERR  
The translation is inaccurate. The phrase "пређи мишем преко поља за приказ броја трансакција" translates as "hover over the field to display the number of transactions." However, the original English says "number of confirmations," not "number of transactions."  
Correct translation:  
Статус трансакције. Пређите мишем преко овог поља да бисте видели број потврда.
```

<!-- cache_translation_check_sr_d3c67ee6f7daa4d5ec3f613ccf586301db99122f3390c8488657d75dbb5c4432 -->
```
        <source>Copy &amp;label</source>
        <translation>Копирај &amp;означи</translation>
    
ERR
The translation uses the verb "означи" (imperative "mark!") instead of the noun in accusative required by "Copy label". It is therefore incorrect/odd in Serbian.

Correct translation:
Копирај &ознаку
```

<!-- cache_translation_check_sr_e84fb6cd88755bb3b2df9aee78add1c43e86c882481bb46969d0f435bc4299f0 -->
```
        <source>Copy transaction &amp;ID</source>
        <translation>Копирај трансакцију &amp;ID</translation>
    
ERR
Word order is incorrect in Serbian. "Копирај трансакцију &ID" reads awkwardly / ungrammatically — it should say "transaction ID" as a unit (e.g. "ID трансакције").

Correct translation:
Копирај &ID трансакције
```

<!-- cache_translation_check_sr_144f5bd13d12f080bb3ae7661504ebf46f09b7b6ed2dd5885e2ce867a5c2c4e0 -->
```
        <source>Copy full transaction &amp;details</source>
        <translation>Копирајте све детаље трансакције</translation>
    
ERR
The translation is missing the accelerator ampersand (&) present in the source. The source contains a single & (for the shortcut) and the translation must include exactly one & as well. No other problems.

Correct translation (include a single & before the desired shortcut letter):
Копирајте све &детаље трансакције
```

<!-- cache_translation_check_sr_b97560d26fa0c22a215895b3014c68515fa9c737089e8a58eff3a87f6a9168c4 -->
```
        <source>&amp;Show transaction details</source>
        <translation>&amp;Прикажи детаље транакције</translation>
    
ERR
The Serbian translation contains a typo: "транакције" is missing the letter "с". Ampersand placement is fine.

Correct translation:
&Прикажи детаље трансакције
```

<!-- cache_translation_check_sr_909a6b3f2ed6a28e2298ca06b26ea9008e87e356d23bf01a6311319d0fc40c47 -->
```
        <source>Increase transaction &amp;fee</source>
        <translation>Повећај провизију трансакције</translation>
    
ERR
The translation is good Serbian (Cyrillic) and wording is acceptable, but it is missing the shortcut ampersand (&) that appears in the source. The target must contain exactly one & to mark the shortcut key.

Correct translation (with & placed before 'провизију'):
Повећај &провизију трансакције
```

<!-- cache_translation_check_sr_94468c526042009052f40f5c425f6a92b5a0dc8b08f57f436152dbfea6158e54 -->
```
        <source>&amp;Edit address label</source>
        <translation>&amp;Promeni adresu etikete</translation>
    
ERR
The Serbian translation is grammatically incorrect and the word order is wrong — "Promeni adresu etikete" reads like "change the address of the label" instead of "edit the address label". The ampersand is present once (OK).

Correct translations (Serbian Latin) could be:
&Izmeni oznaku adrese
or
&Promeni oznaku adrese
```

<!-- cache_translation_check_sr_eda46644e93f482f50a2eee4c1c1c351b8c672f379aaaa4704fa66b4df93f27b -->
```
        <source>Create a new wallet</source>
        <translation>Направи нови ночаник</translation>
    
ERR
There is a spelling error in the translation: "ночаник" should be "новчаник". Also, "направи" is understandable but "креирај" or "направите" (formal) is more commonly used in software contexts. 

Correct translation:
Креирај нови новчаник
```

<!-- cache_translation_check_sr_ae477304ee6b46a87948bbaa8e68e0e67eb42bd8b510cc67dc4b966d6011cf52 -->
```
        <source>Confirm fee bump</source>
        <translation>Потврдите ударну провизију</translation>
    
ERR
The translation "Потврдите ударну провизију" is problematic. The phrase "ударну провизију" literally means "impact fee" or "hit fee", which is not an accurate or idiomatic rendering of "fee bump" in the Bitcoin context. In Bitcoin, "fee bump" refers to increasing the transaction fee. The correct translation in this context should convey the idea of confirming an increase in the transaction fee, typically accomplished with terms like "повећање накнаде".

Correct translation:
Потврдите повећање накнаде
```

<!-- cache_translation_check_sr_2a492305166bc20b176871c70024f3d46f937f9ba957c6dc327da50662c3f104 -->
```
        <source>The transaction amount is too small to pay the fee</source>
        <translation>Износ трансакције је сувише мали да се плати трансакција</translation>
    
ERR
The translation is problematic: the phrase "да се плати трансакција" means "to pay the transaction," which is incorrect. It should refer to paying the fee, not the transaction itself. Also, "суviše мали" (too small) is fine, but "трансакција" at the end should be "такса" or "надокнада" (fee).

Correct translation:
Износ трансакције је сувише мали да плати таксу.
```

<!-- cache_translation_check_sr_3e8842711946b7215b95587d00923f2ffb1a44be4eb46212194fe825e83b9e13 -->
```
        <source>This is experimental software.</source>
        <translation>Ово је експерименталн софтвер.</translation>
    
ERR
There is a spelling error in the Serbian translation. The word "експерименталн" is missing the last letter "и" to correctly spell "експериментални".

Correct translation:
Ово је експериментални софтвер.
```
</details>

Number of issues: 90.
