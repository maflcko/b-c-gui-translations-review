# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sr</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsr%5D%20low%20quality)


<!-- cache_translation_check_sr_48df7cc335dbe779a8dc38d57a7fef7d3e72fe7bd58d739ee04ec6476a7cbf98 -->
```
        <source>Choose the address to receive coins with</source>
        <translation>Одабери адресу за примање</translation>
    
ERR
The translation omits the word "coins" ("новци" or "новчићи") present in the source, which makes the sentence less clear in the Bitcoin context. The phrase "за примање" is incomplete in conveying the full meaning "to receive coins with". Additionally, the aspect "to receive coins with" is somewhat more idiomatically rendered in Serbian as "адресу на коју ћете примити новчиће".

Correct translation:
Одаберите адресу на коју ћете примити новчиће
```

<!-- cache_translation_check_sr_2628147a4d2c1a795db2bdaaf3f6ac246dd3c86d2848558df0ecf637592e31f7 -->
```
        <source>Copy Label</source>
        <translation>Копирај  Обележи</translation>
    
ERR
There is a double space between "Копирај" and "Обележи". Furthermore, "Copy Label" should be translated as "Копирај ознаку" (where "ознака" is the appropriate translation for "label" in this context), not "Обележи" ("Обележи" means "Mark" or "Highlight").

Correct translation:
Копирај ознаку
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

<!-- cache_translation_check_sr_a416968fa0733193f3a53549641c22adba8b4c692b207e22ea5883ca8cc8d88c -->
```
        <source>Load PSBT from clipboard…</source>
        <translation>Учитај ”PSBT” из привремене меморије</translation>
    
ERR
The translation uses quotation marks around "PSBT" instead of leaving it unquoted, which isn't necessary or idiomatic in Serbian. Also, "привремена меморија" is technically correct for "clipboard", but "клипборд" is more recognizable in the context of software UI, or "међу меморију" is sometimes used.
The ellipsis in the source is a single Unicode character (…); this is missing in the translation.

Correct translation:
Учитај PSBT из клипборда…
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

<!-- cache_translation_check_sr_efc9094a83a62dfceb458d9102660c382b4b4d6e390718b46f626e44c43f1e67 -->
```
        <source>Number of script verification threads</source>
        <translation>Број скрипти и CPU за верификацију</translation>
    
ERR
The translation is inaccurate. The English source says "Number of script verification threads," which refers specifically to the number of processing threads used for script verification. The provided Serbian translation, "Број скрипти и CPU за верификацију," translates back as "Number of scripts and CPU for verification," which introduces erroneous and unnecessary elements ("CPU" and "scripts" instead of "threads").

Correct translation:
Број нити за верификацију скрипти
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

<!-- cache_translation_check_sr_039eeee3a4042e52a70d988657fd5fb9e800f56eea9705640ae0b2ac6bb6f549 -->
```
        <source>Prune block storage to</source>
        <translation>Сакрати block складиштење на</translation>
    
ERR
The translation partially translates the text: "block storage" is left in English, while it should be in Serbian. Additionally, the word order is odd, and the infinitive "Prune" is usually rendered as an imperative or descriptive action.

Correct translation:
Скратити складиштење блокова на

Or, to match familiar UI phrasing:

Скратити складиштење блокова на
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

<!-- cache_translation_check_sr_3e1c31380edd8079c4b6f046c1f44bfe3cb4013aa454c18cdbbba954e75326af -->
```
        <source>Connect to the Bitcoin network through a SOCKS5 proxy.</source>
        <translation>Конектуј се на Биткоин мрежу кроз SOCKS5 проксијем.</translation>
    
ERR
The translation uses the informal imperative "Конектуј се", but a more standard and formal Serbian phrasing would use "Повежите се". Also, "кроз SOCKS5 проксијем" is incorrect; it should be "преко SOCKS5 проксија". 

Correct translation:
Повежите се на Биткоин мрежу преко SOCKS5 проксија.
```

<!-- cache_translation_check_sr_a2574513b092ed2f803aba0277c1dca3c3f1ddd4215430de18e7bd3ec463a878 -->
```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>минимизирај у доњу линију, уместо у програмску траку</translation>
    
ERR
The translation is inaccurate. In Serbian, "system tray" is commonly referred to as "системску траку" or "област обавештења", while "taskbar" is "програмска трака" or "дно екрана". The phrase "доња линија" is not standard for "tray".

Correct translation:
Минимизуј у системску траку уместо у програмску траку
```

<!-- cache_translation_check_sr_65b07b7af96b1d4fd009b562c6fd331cb6c923f20debb37ada8e62b19510ce23 -->
```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>Салдорударења у адресама које су у моду само гледање, који још увек није доспео</translation>
    
ERR
There is a minor issue with the translation: "Салдорударења" is a concatenation and should be split. The correct term for "mined balance" would be "ископани салдо" or "салдо од рударења". The rest of the translation is generally accurate, but it can be made smoother.

Correct translation:
Ископани салдо на адресама у режиму само за гледање који још увек није доспео
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

<!-- cache_translation_check_sr_e65b0acef7da49c852a0c76d6617e6d05da55e2c5c1545468a21e89bd8920747 -->
```
        <source>Save Image…</source>
        <translation>Сачували слику…</translation>
    
ERR
The translation is inaccurate. "Сачували слику…" means "Saved the image…" (past tense), rather than the imperative form "Save Image…". The correct translation should be in the imperative mood.

Correct translation:
Сачувај слику…
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

<!-- cache_translation_check_sr_e65b0acef7da49c852a0c76d6617e6d05da55e2c5c1545468a21e89bd8920747 -->
```
        <source>Save Image…</source>
        <translation>Сачували слику…</translation>
    
ERR
The translation is inaccurate. "Сачували слику…" means "Saved the image…" (past tense), rather than the imperative form "Save Image…". The correct translation should be in the imperative mood.

Correct translation:
Сачувај слику…
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

<!-- cache_translation_check_sr_cba81f8591f01d9be5584c1b898a09145c23c6bbdd8f12e6393a4fc1b621656b -->
```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Без обзира да ли је у ову трансакције укључена или није - адреса само за гледање.</translation>
    
ERR
The Serbian translation is not accurate and sounds unnatural. There is also a grammatical error: "трансакције" should be "трансакцију" (accusative case). The construction "или није - адреса само за гледање" is not idiomatic and adds unnecessary complexity.

Correct translation:
Да ли је у ову трансакцију укључена адреса само за посматрање.

Alternative:
Да ли је у ову трансакцију укључена watch-only адреса.
```

<!-- cache_translation_check_sr_f35d3271a27b6c3d0ce5daabb8e8207a9c6d382f94bcaee5d4ba85dd3046288c -->
```
        <source>Copy transaction ID</source>
        <translation>Копирај трансакцију ID</translation>
    
ERR
There is a minor issue in the translation: the word order is incorrect. "ID" in Serbian should usually come before the noun as "ID трансакције" or the phrase should be "Копирај ID трансакције" to accurately mean "Copy transaction ID". Additionally, "ID" can be transliterated or left, but it is usually left as "ID". There is also an unnecessary mixing of Latin and Cyrillic scripts (since "ID" is in Latin, and the rest is in Cyrillic, which is acceptable in Serbian IT context but not ideal stylistically).

Correct translation:
Копирај ID трансакције
```

<!-- cache_translation_check_sr_979313ead12f58021712ec7029fa9fbb79aded9c9d3edcf80e39dd4d90c7ddef -->
```
        <source>Edit address label</source>
        <translation>Promeni adresu etikete</translation>
    
ERR
The translation is incorrect. The phrase "Edit address label" means to edit the label (name or description) assigned to an address, not to change the address of a label. The correct Serbian translation should be "Izmeni oznaku adrese" or "Uredi oznaku adrese".

Correct translation:
Izmeni oznaku adrese
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

Number of issues: 57.
