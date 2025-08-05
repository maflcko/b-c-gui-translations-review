# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sr</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsr%5D%20low%20quality)


```
        <source>Choose the address to receive coins with</source>
        <translation>Одабери адресу за примање</translation>
    
YES  
The translation is incomplete and unclear. It should fully convey "Choose the address to receive coins with," implying the address used for receiving coins.  

Correct translation:  
Одабери адресу за примање новчића
```

```
        <source>Copy Label</source>
        <translation>Копирај  Обележи</translation>
    
YES  
The translation includes two words "Копирај  Обележи" which means "Copy Label" and "Mark/Label" separately, with an extra double space between them. The source text "Copy Label" is a single phrase that means "copy the label," so the translation should be a single verb phrase that conveys "Copy Label" without splitting it into two words or adding extra spacing.

Correct translation:  
Копирај обележје
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Унеси нову приступну фразу за новчаник&lt;br/&gt;Молимо користи приступну фразу од десет или више насумичних карактера&lt;b&gt;,или&lt;b&gt;осам или више речи&lt;/b&gt;.</translation>
    
YES  
The translation has formatting errors: the HTML tags are not correctly placed and spaced. The opening <b> tags are attached to the words without spaces and the closing </b> tags are missing after "програмских карактера" and before "или". Also, there is no space after the comma before "или". The corrected translation should properly mirror the source's HTML and spacing:

Correct translation:  
Унеси нову приступну фразу за новчаник.&lt;br/&gt;Молимо користи приступну фразу од &lt;b&gt;десет или више насумичних карактера&lt;/b&gt;, или &lt;b&gt;осам или више речи&lt;/b&gt;.
```

```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Упамти, шифрирање новчаника не може у потуности заштити твоје биткоине од крађе од стране малвера инфицира твој рачунар.</translation>
    
YES  
The translation contains grammatical errors and awkward phrasing. For example, "инфицира" (infects) is a verb in present tense and singular third person, but it's incorrectly used without proper connection; the phrase "малева инфицира твој рачунар" is ungrammatical. Also, "упамти" is not the best choice in Serbian for "remember" in this context; "Запамти" or "Имај на уму" would be better. The phrase "не може у потуности заштити" is somewhat unnatural; "не може у потпуности да заштити" is more idiomatic.

Correct translation:  
Запамти да шифровање твог новчаника не може у потпуности да заштити твоје биткоине од крађе уз помоћ малвера који инфицира твој рачунар.
```

```
        <source>Warning: The Caps Lock key is on!</source>
        <translation>Упозорање Caps Lock дугме укључено!</translation>
    
YES
The translation misses a preposition and sounds incomplete or unnatural in Serbian. It should clearly state that the Caps Lock key is on. A better translation would be:  
"Упозорење: Caps Lock дугме је укључено!"
```

```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>Унеси Биткоин адресу, (нпр %1)</translation>
    
YES
There is an unnecessary comma after "адресу" which is not present in the English source and disrupts the natural flow of the sentence. Also, "нпр" should be capitalized as "нпр." with a period to denote abbreviation properly.

Correct translation:
Унеси Биткоин адресу (нпр. %1)
```

```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>Блокирана предаја</translation>
    
YES  
The translation "Блокирана предаја" literally means "blocked transmission" or "blocked relay," which is incorrect in this context. The source term "Block Relay" refers to a peer connection type that relays block information in the Bitcoin network. A better translation would be "Пренос блокова" or "Релеј блокова," which correctly convey "Block Relay" as relaying or forwarding blocks rather than blocking something.

Correct translation:  
Пренос блокова
```

```
        <source>Create a new wallet</source>
        <translation>Направи нови ночаник</translation>
    
YES  
The translation contains an error: the word "ночаник" is incorrect and does not mean "wallet" in Serbian. The correct word is "новчаник". Also, the adjective "нови" should agree in gender with "новчаник," which is masculine, so "нови" is correct here.  

Correct translation:  
Направи нови новчаник
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Потписуј поруку са своје Биткоин адресе као доказ да си њихов власник</translation>
    
YES  
The translation uses singular forms "поруку" (message) and "адресе" (address), but the source text is plural "messages" and "addresses". Also, "као доказ да си њихов власник" is informal ("ти" form) while the source tone is neutral; it's better to keep neutral or consistent tone, preferably formal or neutral in instructions.  

Correct translation:  
Потписујте поруке са својих Биткоин адреса као доказ да их поседујете
```

```
        <source>Show the list of used sending addresses and labels</source>
        <translation>Прегледајте листу коришћених адреса и етикета за слање уплата</translation>
    
YES  
The translation is somewhat inaccurate and slightly awkward. Specifically, "етикета" is less commonly used in Serbian for "labels" in this context; "налепнице" or simply "ознаке" might work better, but "етикета" is acceptable though less natural. More importantly, "за слање уплата" translates to "for sending payments," which is not exactly the intended meaning. The source says "sending addresses and labels," referring to addresses used to send Bitcoin and their associated labels—not specifically "sending payments." Also, "Прегледајте" ("Review" or "Browse") is more of an imperative and doesn't fit the neutral "Show" as well as "Прикажите" or "Прикажи" ("Show").  

A more accurate and natural translation would be:  
"Прикажите листу коришћених адреса и ознака за слање"

Or if labels must be "етикете":  
"Прикажите листу коришћених адреса и етикета за слање"

No format specifiers or whitespace issues noted.

Correct translation:  
<translation>Прикажите листу коришћених адреса и етикета за слање</translation>
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>Учитај ”PSBT” из привремене меморије</translation>
    
YES  
The translation uses the Latin alphabet term "PSBT" in quotes, which is acceptable, but the ellipsis is missing (the source ends with an ellipsis '…', and the translation does not). Also, "привремене меморије" literally means "temporary memory," which is a literal but less common way to say "clipboard"; the usual Serbian term for clipboard is "међуспeминa" or "међуспоменик".  

A better and more natural translation would be:  
Учитај PSBT из међуспемина…
```

```
        <source>Node window</source>
        <translation>Ноде прозор</translation>
    
YES
The word "Node" is not translated into Serbian; it should be adapted to Serbian Cyrillic or Serbian language rather than left in English transliteration. Also, "прозор" (window) is correct. The proper Serbian translation for "Node window" would be "Везни прозор" or "Прозор нода" depending on context, but "Ноде прозор" mixes English and Serbian incorrectly.

Correct translation:
Ноде прозор -> Прозор нода
```

```
        <source>Mask the values in the Overview tab</source>
        <translation>Филтрирај вредности у картици за преглед</translation>
    
YES  
The English source says "Mask the values in the Overview tab," which means to hide or obscure the values, but the Serbian translation "Филтрирај вредности у картици за преглед" means "Filter the values in the Overview tab," which changes the meaning entirely. The correct translation should convey "mask" (скриј/маскирај) rather than "filter."

Correct translation:  
Маскирај вредности у картици за преглед
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Прикажи картицу са ”Клијентима”</translation>
    
YES  
The word "Клијентима" (Clients) is not accurate in the Bitcoin context here; "Peers" should be translated as "Чворови" or "Пеери" since it refers to nodes or peers in the Bitcoin network, not clients. Also, the quotation marks are inconsistent: the English source does not have them, so they should be omitted or standardized in Serbian.

Correct translation:  
Прикажи картицу са „Пеерима“  
or  
Прикажи картицу са „Чворовима“
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Новчаник јс &lt;b&gt;шифриран&lt;/b&gt; и тренутно &lt;b&gt;откључан&lt;/b&gt;</translation>
    
YES  
The translation contains a typo in the word "јс" which should be "је" (the verb "is" in Serbian).  

Correct translation:  
Новчаник је &lt;b&gt;шифриран&lt;/b&gt; и тренутно &lt;b&gt;откључан&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Новчаник јс &lt;b&gt;шифрован&lt;/b&gt; и тренутно &lt;b&gt;закључан&lt;/b&gt;</translation>
    
YES  
The translation has a typo: "јс" should be "је". Also, the word "шифрован" is a direct borrowing from Russian; the correct Serbian word is "шифрован" with Serbian Cyrillic spelling is questionable, better use "шифрован" or preferably "шифрован" depending on dialect, but more standard and commonly used is "шифрован" or the verb form "шифрован". However, more appropriate Serbian term is "шифрован" (from "шифровати") is acceptable, but the more natural Serbian adjective for encrypted is "шифрован". So the better phrase is:  

Новчаник је &lt;b&gt;шифрован&lt;/b&gt; и тренутно &lt;b&gt;закључан&lt;/b&gt;  

Correct translation:  
Новчаник је &lt;b&gt;шифрован&lt;/b&gt; и тренутно &lt;b&gt;закључан&lt;/b&gt;
```

```
        <source>change from %1 (%2)</source>
        <translation>Измени од %1 (%2)</translation>
    
YES  
The translation "Измени од %1 (%2)" is incorrect. The English phrase "change from %1 (%2)" refers to the Bitcoin transaction "change" (i.e., the leftover amount returned to the sender), and should be translated in Serbian as "Промена са %1 (%2)" or "Каса са %1 (%2)". The current translation uses "Измени," which is the imperative form of the verb "to change," not a noun meaning "change" in the transaction sense.

Correct translation:  
Промена од %1 (%2)
```

```
        <source>Create wallet warning</source>
        <translation>Направи упозорење за новчаник</translation>
    
YES
The translation is incorrect and misleading. "Направи упозорење за новчаник" literally means "Make/Create a warning for the wallet," which does not convey the intended meaning of a warning message titled "Create wallet warning."

A better translation for "Create wallet warning" in this context would be:
"Упозорење о креирању новчаника"
```

```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>Da li si siuran da želiš da preneseš novčanik &lt;i&gt;%1&lt;/i&gt;? </translation>
    
YES  
There is a typo in the translation: "siuran" should be "siguran". Also, there is an unnecessary trailing space at the end of the sentence.  

Correct translation:  
Da li si siguran da želiš da preneseš novčanik &lt;i&gt;%1&lt;/i&gt;?
```

```
        <source>Migration Successful</source>
        <translation>Prenošenje novčanika je uspešno</translation>
    
YES  
The translation adds extra information ("novčanika" meaning "of the wallet") that is not present in the source text "Migration Successful," which is more general and could refer to any migration, not specifically a wallet. A more accurate and neutral translation would be:

Uspešna migracija
```

```
        <source>Opening Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the open wallet progress window which indicates to the user which wallet is currently being opened.</extracomment>
        <translation>Отвањаре новчаника &lt;b&gt;%1&lt;/b&gt;</translation>
    
YES  
The translation contains a typographical error in the Serbian word "Отвањаре". The correct form should be "Отварање" which means "Opening". Also, the ellipsis ("…") at the end of the source text is missing in the translation, which changes the nuance of ongoing action.

Correct translation:  
Отварање новчаника &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Онемогући приватни кључ за овај новчаник. Новчаници са онемогућеним приватним кључем неће  имати приватни кључ и не могу имати HD семе или увезени приватни кључ. Ова опција идеална је за новчанике који су искључиво за посматрање.</translation>
    
YES
There are spacing issues before "имати" and "увезени" (extra space after "неће" and before "имати", and before "увезени приватни кључ"). Also, the singular "приватни кључ" should be plural "приватне кључеве" to match meaning ("no private keys"). The verb phrase "Онемогући приватни кључ" should be "Онемогући приватне кључеве" since keys is plural. Corrected translation:

Онемогући приватне кључеве за овај новчаник. Новчаници са онемогућеним приватним кључевима неће имати приватне кључеве и не могу имати HD семе или увезене приватне кључеве. Ова опција идеална је за новчанике који су искључиво за посматрање.
```

```
        <source>Make a blank wallet. Blank wallets do not initially have private keys or scripts. Private keys and addresses can be imported, or an HD seed can be set, at a later time.</source>
        <translation>Направи празан новчаник. Празни новчанци немају приватане кључеве или скрипте. Приватни кључеви могу се увести, или HD семе може бити постављено касније.</translation>
    
YES  
There is a minor typo and some inconsistent terminology in the translation. The phrase "приватане кључеве" should be "приватне кључеве." The plural form of "wallets" is translated as "новчанци," which is somewhat informal; "новчаници" or "новчанци" can be accepted in Serbian, but "новчаници" is more standard. Also, the phrase "направи празан новчаник" is informal and imperative; it is acceptable if the context is instructive, but otherwise, "Креирај празан новчаник" might be more neutral/formal. The abbreviation "HD" is untranslated, which is acceptable because it's a technical term.

Corrected translation:  
Направи празан новчаник. Празни новчаници немају приватне кључеве или скрипте. Приватни кључеви и адресе могу се увести, или HD семе може бити постављено касније.
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Најмање %1 GB подататака биће складиштен у овај директорјиум који ће временом порасти.</translation>
    
YES  
The word "директорјиум" is an incorrect or non-standard Serbian word for "directory." The correct Serbian word is "директоријум." Also, the sentence can be slightly improved for naturalness and clarity.

Correct translation:  
Најмање %1 GB података биће сачувано у овом директоријуму, и његова величина ће временом расти.
```

```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Најмање %1 GB подататака биће складиштен у овај директорјиум.</translation>
    
YES  
The translation contains an error with "Најмање," which means "at least," while the source says "Approximately." Also, "директорјиум" is a less common and somewhat awkward transliteration of "directory." A better and more natural Serbian term is "директоријум."  

Correct translation:  
Приближно %1 GB података биће складиштено у овај директоријум.
```

```
        <source>%1 will download and store a copy of the Bitcoin block chain.</source>
        <translation>%1 биће преузеће и складиштити копију Биткоин ланца блокова.</translation>
    
YES  
The translation contains a redundancy: both "биће" (will be) and "преузеће" (will download) are used together, which is incorrect. The phrase should have only one future tense verb. Also, "лања блокова" is a more common and clearer phrasing than "ланца блокова."

Correct translation:  
%1 ће преузети и сачувати копију Биткоин ланца блокова.
```

```
        <source>Error: Specified data directory "%1" cannot be created.</source>
        <translation>Грешка: Одабрана датотека  "%1" не може бити креирана.</translation>
    
YES  
The Serbian translation incorrectly uses "датотека" which means "file" instead of "директоријум" or "папка" which mean "directory" or "folder". The source text says "data directory," so the correct term should be "директоријум" or "фасцикла". Also, there is an extra space before the quotation mark in the translation that should be removed.

Correct translation:  
Грешка: Одабрани директоријум „%1“ не може бити креиран.
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Налепите адресу из базе за копирање</translation>
    
YES  
The Serbian translation uses "Налепите адресу из базе за копирање," which is incorrect. "база за копирање" literally means "database for copying," which is not the correct phrase for "clipboard." The correct translation for "clipboard" in Serbian is "међуспремник" or "међуспремник за копирање."

Correct translation:  
Налепите адресу из међуспремника
```

```
        <source>Number of script verification threads</source>
        <translation>Број скрипти и CPU за верификацију</translation>
    
YES  
The translation is inaccurate and adds content not present in the source. The original source refers to the "Number of script verification threads," which means how many threads (concurrent processing units) are used for verifying scripts. The provided translation "Број скрипти и CPU за верификацију" means "Number of scripts and CPU for verification," which is incorrect and changes the meaning.

Correct translation:  
Број нити за верификацију скрипти
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Приказује се ако је испоручени уобичајени SOCKS5 проxy коришћен ради проналажења клијената преко овог типа мреже. </translation>
    
YES  
The translation is mostly correct but could be improved for clarity and style, and there is a trailing whitespace at the end that should be removed. Also, "проxy" mixes Cyrillic and Latin letters; it should be fully in Cyrillic as "проки".

Correct translation:  
Приказује се ако је испоручени подразумевани SOCKS5 прокси коришћен за повезивање са чворовима преко овог типа мреже.
```

```
        <source>Prune block storage to</source>
        <translation>Сакрати block складиштење на</translation>
    
YES  
The word "block" is untranslated and left in English, which is inconsistent and should be translated or adapted. Also, "складиштење" is correct for "storage," but it would be better to write "блок" in Cyrillic instead of "block" in Latin script for consistency. The verb "Сакрати" should be "Скрати" (correct infinitive form meaning "to prune"/"to shorten").  

Correct translation:  
Скрати блок складиштење на
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Враћање ове опције захтева да поновно преузимање целокупонг блокчејна.</translation>
    
YES  
There is an erroneous word "целокупонг" which appears to be a typo or misspelling. The correct word is "целокупног". Also, the phrase would be more natural as "понoвно преузимање целокупног блокчејна."

Correct translation:  
Враћање ове опције захтева да поновно преузимање целокупног блокчејна.
```

```
        <source>Connect to the Bitcoin network through a SOCKS5 proxy.</source>
        <translation>Конектуј се на Биткоин мрежу кроз SOCKS5 проксијем.</translation>
    
YES  
The translation contains a grammatical error in the instrumental case usage. In Serbian, when expressing "through a SOCKS5 proxy," the word "прокси" should be in the instrumental case "проксијем" but without the preposition "кроз," which requires accusative. Proper wording would use "помоћу" + instrumental or "преко" + genitive.

Correct translation:  
Конектуј се на Биткоин мрежу преко SOCKS5 проксија.  
OR  
Конектуј се на Биткоин мрежу помоћу SOCKS5 проксија.
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>минимизирај у доњу линију, уместо у програмску траку</translation>
    
YES  
The translation is understandable but could be improved for clarity and naturalness in Serbian. The phrase "доњу линију" ("bottom line") is not the usual way to refer to the system tray. The term "tray" in the context of minimizing an application typically refers to the system tray, which is best translated as "системску траку" or "икону пријава" depending on the context. Also, the original phrase uses "taskbar" (progamska traka), which is correct, but "доњу линију" is not an appropriate translation for "tray."

A better translation would be:

Минимизирај у системску траку уместо у програмску траку

This clarifies minimizing to the system tray instead of the taskbar and is more idiomatic for Serbian users.
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>Салдорударења у адресама које су у моду само гледање, који још увек није доспео</translation>
    
YES  
The translation contains erroneous and awkward wording: "Салдорударења" is not a correct Serbian word for "balance," and the phrase "у моду само гледање" is an unnatural and incorrect translation for "watch-only." The phrase "који још увек није доспео" correctly translates "has not yet matured," but the rest needs correction for clarity and accuracy.

Correct translation:  
"Миновани износ на адресама само за праћење који још увек није доспео"
```

```
        <source>Signed %1 inputs, but more signatures are still required.</source>
        <translation>Потписано %1 поље, али је потребно још потписа.</translation>
    
YES  
The word "поље" translates to "field," which is incorrect in this Bitcoin context. The correct term for "inputs" in Serbian when referring to Bitcoin transactions should be "улаза" (inputs). Also, the spacing and format specifier %1 are correctly used.  

Correct translation:  
Потписано %1 улаза, али је потребно још потписа.
```

```
        <source>Transaction has %1 unsigned inputs.</source>
        <translation>Трансакција има %1 непотписана поља.</translation>
    
YES  
The translation contains an inaccurate term. The word "поља" means "fields" or "areas," which is incorrect for the context of Bitcoin transactions. The correct translation should use the term for "inputs," which is "улиза" in Serbian.

Correct translation:  
Трансакција има %1 непотписаних улаза.
```

```
        <source>Save Image…</source>
        <translation>Сачували слику…</translation>
    
YES  
The translation "Сачували слику…" is incorrect because it uses the past tense ("Saved the image") instead of the imperative or infinitive form which matches the English command "Save Image…". A correct translation should use the imperative form.

Correct translation:  
Сачувај слику…
```

```
        <source>Resulting URI too long, try to reduce the text for label / message.</source>
        <translation>Дати резултат URI  предуг, покушај да сманиш текст за ознаку / поруку.</translation>
    
YES  
The translated sentence contains a typo and awkward phrasing: "Дати резултат URI предуг" is incorrect and unclear. The phrase should properly convey "Resulting URI too long". The word "предуг" seems to be a truncated or misspelled form of "предугачак" (too long). Also, there is an unnecessary non-breaking space after "URI". The verb "сманиш" is an informal imperative, which is acceptable but could be replaced with a more neutral/standard "скратиш".

Correct translation:  
Резултујући URI је превише дуг, покушај да срежеш текст за ознаку / поруку.
```

```
        <source>Memory Pool</source>
        <translation>Удружена меморија</translation>
    
YES  
The translation "Удружена меморија" means "associated memory" or "combined memory," which is incorrect in the Bitcoin context. The correct term for "Memory Pool" (the pool of unconfirmed Bitcoin transactions) in Serbian is commonly translated as "пул меморије" or more precisely "меморијски пул" or "пул трансакција."

Correct translation:  
Пул меморије
```

```
        <source>Select a peer to view detailed information.</source>
        <translation>Одабери колегу да би видели детаљне информације</translation>
    
YES  
The translation is mostly correct but the word "колегу" more commonly means "colleague" in a professional context rather than a "peer" in a P2P network or Bitcoin context. A better choice would be "члана" (member) or "једног од учесника" (one of the peers/participants). Also, the sentence is missing a period at the end, which is present in the source. The phrase "да би видели" should agree in number with the subject; better is to say "да бисте видели" (formal/polite form).

Correct translation:  
Одаберите једног од учесника да бисте видели детаљне информације.
```

```
        <source>Node window</source>
        <translation>Ноде прозор</translation>
    
YES
The word "Node" is not translated into Serbian; it should be adapted to Serbian Cyrillic or Serbian language rather than left in English transliteration. Also, "прозор" (window) is correct. The proper Serbian translation for "Node window" would be "Везни прозор" or "Прозор нода" depending on context, but "Ноде прозор" mixes English and Serbian incorrectly.

Correct translation:
Ноде прозор -> Прозор нода
```

```
        <source>The direction and type of peer connection: %1</source>
        <translation>Смер и тип конекције клијената: %1</translation>
    
YES  
The Serbian translation contains a typo and a slight inaccuracy. The word "Смер" should be "Смер" (direction) which is correct, but "конекције" is a transliteration from English "connection" which is not natural Serbian. The proper Serbian word is "везе" for "connection". Also, "клијената" means "clients," but in the Bitcoin context, "peers" are often referred to as "чворови" (nodes) or simply "peer-ови".  

Correct translation:  
Смер и тип везе пира: %1
```

```
        <source>Outbound Block Relay: does not relay transactions or addresses</source>
        <extracomment>Explanatory text for an outbound peer connection that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>Оутбоунд Блоцк Релаи: не преноси трансакције или адресе</translation>
    
YES  
The translation uses untranslated English loanwords "Оутбоунд Блоцк Релаи" (Outbound Block Relay) written in Cyrillic, which is not appropriate or clear. These terms should be translated or transliterated properly in Serbian for clarity and naturalness. Also, "преноси" is acceptable but "преноси" generally means "transports"; "преносити" can be used, but "преноси" here is fine. However, translating the key technical terms into Serbian is better.

Correct translation:  
"Излазни пренос блока: не преноси трансакције или адресе"
```

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
    
YES  
The translation contains several issues:

1. The word "команди" in "преглед доступних комади" is incorrect; it should be "команди" (genitive plural of "команда") instead of "комади" (which means "pieces" or "parts").  
2. The phrase "говорећи корисницима да уносе команде овде" is slightly unnatural; better phrasing is "упућујући кориснике да овде уносе команде".  
3. The warning sentence "и тако краду садржај новчаника" is understandable but could be smoother as "крадући садржај њихових новчаника".  
4. The wording "потпуног схватања комплексности ове команде" is awkward and should be "потпуног разумевања последица команди" or "потпуног разумевања последица неке команде" because "complexity of this command" is not a perfect match for "рамфикације" (ramifications).  
5. Some punctuation and spacing issues appear around %7 and %8 tags: in the source, there is no space after %7 and before the warning, but the translation adds a space ("%7 УПОЗОРЕЊЕ"). The warning should immediately follow %7 with no space, to preserve styling.

Corrected translation:

Добродошли у %1 RPC конзолу.  
Користи тастере за горе и доле да наводиш историју, и %2 да очистиш екран.  
Користи %3 и %4 да увећаш и смањиш величину фонта.  
Унеси %5 за преглед доступних команди.  
За више информација о коришћењу конзоле, притисни %6.  
%7УПОЗОРЕЊЕ: Преваранти су били активни, упућујући кориснике да овде уносе команде, крадући садржај њихових новчаника. Не користи ову конзолу без потпуног разумевања последица неког наређења.%8
```

```
        <source>Save Image…</source>
        <translation>Сачували слику…</translation>
    
YES  
The translation "Сачували слику…" is incorrect because it uses the past tense ("Saved the image") instead of the imperative or infinitive form which matches the English command "Save Image…". A correct translation should use the imperative form.

Correct translation:  
Сачувај слику…
```

```
        <source>Inputs…</source>
        <translation>Поља...</translation>
    
YES  
The English source "Inputs…" refers to "inputs" in a Bitcoin transaction context, which should translate to "Улази…" in Serbian, reflecting the correct technical term for transaction inputs. The provided translation "Поља..." means "Fields...", which is incorrect in this context.

Correct translation:  
Улази…
```

```
        <source>Set external signer script path in Options -&gt; Wallet</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Подси екстерну скрипту за потписивање у : Options -&gt; Wallet</translation>
    
YES  
The translation contains errors and formatting issues:  
- "Подси" is incorrect and seems like a typo or incomplete word. It should be "Подеси" (which means "Set").  
- The colon before "Options" is incorrectly spaced and not necessary; it should be omitted or replaced with a proper dash or simply left as plain text.  
- The English words "Options" and "Wallet" should be either translated or written consistently; usually in Serbian UI translations they are either left in English or transliterated, but since the source uses English UI labels, it is acceptable to keep them.  
- The phrase should read smoothly and naturally in Serbian.

Correct translation:  
Подеси путању до екстерног скрипта за потписивање у Options -&gt; Wallet
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Биткоин адреса на коју се шаље уплата</translation>
    
YES  
The translation uses the genitive singular form "адреса" instead of the accusative "адресу" which is required as the direct object of the verb phrase "to send the payment to". Also, "уплата" (payment) is in nominative, but the preposition "на" requires accusative "уплату". The corrected translation preserves the meaning and correct case usage:

Correct translation:  
Биткоин адресу на коју се шаље уплату
```

```
        <source>Paste address from clipboard</source>
        <translation>Налепите адресу из базе за копирање</translation>
    
YES  
The phrase "база за копирање" is not the correct or natural term for "clipboard" in Serbian. The proper term is "међуспремник" or simply "међуспремника" (genitive case) to mean "from clipboard". The correct translation is:

Налепите адресу из међуспремника
```

```
        <source>A message that was attached to the bitcoin: URI which will be stored with the transaction for your reference. Note: This message will not be sent over the Bitcoin network.</source>
        <translation>Порука која је приложена биткоину: URI која ће бити сачувана уз трансакцију ради референце. Напомена: Ова порука се шаље преко Биткоин мреже.</translation>
    
YES  
The translation contains an error in the second sentence. The English source says: "Note: This message will not be sent over the Bitcoin network." The translation instead says: "This message is sent over the Bitcoin network," which reverses the meaning.

Correct translation:  
Порука која је приложена биткоину: URI која ће бити сачувана уз трансакцију ради референце. Напомена: Ова порука неће бити послата преко Биткоин мреже.
```

```
        <source>Paste address from clipboard</source>
        <translation>Налепите адресу из базе за копирање</translation>
    
YES  
The phrase "база за копирање" is not the correct or natural term for "clipboard" in Serbian. The proper term is "међуспремник" or simply "међуспремника" (genitive case) to mean "from clipboard". The correct translation is:

Налепите адресу из међуспремника
```

```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>%1 порврде</translation>
    
YES  
There is a typographical error in the translation. The correct Serbian word for "confirmations" is "потврде", not "порврде".

Correct translation:  
%1 потврде
```

```
        <source>Credit</source>
        <translation>Заслуге</translation>
    
YES  
The Serbian translation "Заслуге" means "merits" or "accolades," which is incorrect in the Bitcoin context where "Credit" refers to an amount of value added or credited (e.g., to a wallet). The correct translation in this context would be "Кредит".  

Correct translation:  
Кредит
```

```
        <source>Generated coins must mature %1 blocks before they can be spent. When you generated this block, it was broadcast to the network to be added to the block chain. If it fails to get into the chain, its state will change to "not accepted" and it won't be spendable. This may occasionally happen if another node generates a block within a few seconds of yours.</source>
        <translation>Генерисани новчићи морају доспети %1 блокова пре него што могу бити потрошени. Када генеришете овај блок, он се емитује у мрежу, да би био придодат на ланац блокова. Укупно не успе да се придода на ланац, његово стање се мења у "није прихваћен" и неће га бити могуће потрошити. Ово се може повремено десити уколико други чвор генерише блок у периоду од неколико секунди од вашег.</translation>
    
YES
There are small issues with idiomatic clarity and a confusing phrase in the translation:

1. "морају доспети %1 блокова" is a bit awkward; more natural Serbian would be "морају да сазреју %1 блокова" or "морају да прођу %1 блокова" (the meaning is that the generated coins must mature/age).
2. "емитује у мрежу, да би био придодат на ланац блокова" sounds unnatural and slightly incorrect. Better: "преноси на мрежу како би био додат у блокчејн" or "преноси на мрежу да би био додат у ланац блокова".
3. "Укупно не успе да се придода" contains a typo/"унатно не" which makes no sense ("Укупно" means "in total", not "if"). It should be "Ако не успе да се придода", i.e. "If it fails to be added...".
4. "његово стање се мења у "није прихваћен"" → properly agreement is "није прихваћен" is masculine singular, but "он" (the block) is masculine, so that's fine. Just typographically quotes should be „“ in Serbian, but this is minor.
5. "неће га бити могуће потрошити." - better: "неће бити могуће потрошити" (remove "га" which is unnecessary).

A polished version:

Генерисани новчићи морају да сазреју %1 блокова пре него што могу бити потрошени. Када генеришете овај блок, он се преноси на мрежу да би био додат у ланац блокова. Ако не успе да се додат у ланац, његово стање се мења у „није прихваћен“ и неће бити могуће потрошити. Ово се повремено може десити ако други чвор генерише блок у року од неколико секунди после вашег.

Correct translation:  
Генерисани новчићи морају да сазреју %1 блокова пре него што могу бити потрошени. Када генеришете овај блок, он се преноси на мрежу да би био додат у ланац блокова. Ако не успе да се додат у ланац, његово стање се мења у „није прихваћен“ и неће бити могуће потрошити. Ово се повремено може десити ако други чвор генерише блок у року од неколико секунди после вашег.
```

```
        <source>Conflicted</source>
        <translation>Неуслагашен</translation>
    
YES  
The Serbian translation uses "Неуслагашен," which is not a standard or commonly understood Serbian word for "Conflicted." A more accurate translation in this Bitcoin context would be "Сукобљен" (meaning conflicted, as in conflicting states) or "У сукобу."  

Correct translation:  
<translation>Сукобљен</translation>
```

```
        <source>Transaction status. Hover over this field to show number of confirmations.</source>
        <translation>Статус трансакције. Пређи мишем преко поља за приказ броја трансакција.</translation>
    
YES  
The translation misinterprets the second sentence. The original English says "Hover over this field to show number of confirmations," but the translation says "Hover over the field to show number of transactions" ("броја трансакција" means "number of transactions," not "number of confirmations"). Also, "Hover over this field" should be translated as "Преместите курсор преко овог поља" or "Пређите мишем преко овог поља" for clarity.

Correct translation:  
Статус трансакције. Пређите мишем преко овог поља да бисте видели број потврда.
```

```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Без обзира да ли је у ову трансакције укључена или није - адреса само за гледање.</translation>
    
YES
The Serbian translation has grammatical and stylistic issues. The phrase "у ову трансакције" is incorrect because "трансакције" is plural/genitive but "овa" is singular feminine accusative, so they do not agree. Also, "адреса само за гледање" is awkward and less common; the established Bitcoin-related term is "адреса само за праћење" or "само за праћење адреса". The translation is also somewhat unnatural and could be more fluid.

Correct translation:
Без обзира да ли је адреса само за праћење укључена у ову трансакцију или није.
```

```
        <source>Copy transaction ID</source>
        <translation>Копирај трансакцију ID</translation>
    
YES  
The abbreviation "ID" should be translated or adapted consistently in Serbian Cyrillic and preferably in lowercase as "ИД" or fully translated as "идентификатор" depending on context. Since "ID" is an English abbreviation, it is better to transliterate it into Cyrillic as "ИД" to keep consistency and avoid mixing Latin and Cyrillic scripts in one phrase.

Correct translation:  
Копирај трансакцију ИД
```

```
        <source>Edit address label</source>
        <translation>Promeni adresu etikete</translation>
    
YES
The translation is not fully accurate and is somewhat unnatural. "Edit address label" in this context means to change the label/name assigned to an address, not "change the address of the label."

A more accurate and natural Serbian translation would be:
"Измени опис адресу" or "Измени ознаку адресе"

In Latin script: "Izmeni oznaku adrese"
```

```
        <source>Create a new wallet</source>
        <translation>Направи нови ночаник</translation>
    
YES  
The translation contains an error: the word "ночаник" is incorrect and does not mean "wallet" in Serbian. The correct word is "новчаник". Also, the adjective "нови" should agree in gender with "новчаник," which is masculine, so "нови" is correct here.  

Correct translation:  
Направи нови новчаник
```

```
        <source>Confirm fee bump</source>
        <translation>Потврдите ударну провизију</translation>
    
YES  
The phrase "Confirm fee bump" in the context of Bitcoin typically means to confirm an increase in the transaction fee. The translation "Потврдите ударну провизију" uses "ударну" which literally means "impact" or "strike," and doesn't convey the intended meaning of a "bump" or increase in fee.

A more accurate and natural Serbian translation would be:  
"Потврдите повећање провизије"  
(which means "Confirm increase of fee") or  
"Потврдите повећање накнаде" (using "накнада" as fee).  

Preferred correction:  
Потврдите повећање провизије
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Ову провизију можете обрисати уколико је кусур мањи од нивоа прашине</translation>
    
YES
The translation partially conveys the meaning but is not fully accurate. The original sentence talks about the transaction fee that may be discarded if the change amount is smaller than dust at this level. The translation omits the part about "This is the transaction fee" and uses "кусур" (change), which is correct for 'change,' but the phrasing is somewhat informal and the sentence structure is incomplete. Also, the phrase "на овом нивоу" (at this level) is more correct than "од нивоа".

Correct translation:
Ово је накнада за трансакцију коју можете одбацити уколико је кусур мањи од прашине на овом нивоу
```

```
        <source>The transaction amount is too small to pay the fee</source>
        <translation>Износ трансакције је сувише мали да се плати трансакција</translation>
    
YES  
The translation is slightly inaccurate and misleading. The source says "The transaction amount is too small to pay the fee," meaning the amount is insufficient to cover the fee. The current translation "да се плати трансакција" means "to pay the transaction," which is incorrect. It should reflect paying the fee ("такса" or "надокнада" in Serbian).

Correct translation:  
Износ трансакције је сувише мали да би се платила такса
```

```
        <source>This is experimental software.</source>
        <translation>Ово је експерименталн софтвер.</translation>
    
YES  
There is a typo in the Serbian translation: "експерименталн" should be "експерименталан".  

Correct translation:  
Ово је експерименталан софтвер.
```
</details>
