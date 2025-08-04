# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sr</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsr%5D%20low%20quality)


```
        <source>Choose the address to receive coins with</source>
        <translation>Одабери адресу за примање</translation>
    
YES - The translation is missing the word "coins" from the original English phrase, which is important for context.
Correct translation: Одабери адресу за примање новчића
```

```
        <source>Copy Label</source>
        <translation>Копирај  Обележи</translation>
    
YES, The translation is problematic. The word "Обележи" means "mark" or "label" but the space between "Копирај" and "Обележи" is incorrect and looks like two separate commands rather than one.
The correct translation should be "Копирај ознаку".
```

```
        <source>Change passphrase</source>
        <translation>Измени лозинку</translation>
    
YES, The translation is problematic because the Serbian word "лозинку" (lozinku) is a colloquial and somewhat informal term for "password". A more formal and appropriate translation in the context of Bitcoin security would be "промените лозинку" (promenite lozinku) or "промените шифру" (promenite šifru) which means "change password".

"NO"
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Унеси нову приступну фразу за новчаник&lt;br/&gt;Молимо користи приступну фразу од десет или више насумичних карактера&lt;b&gt;,или&lt;b&gt;осам или више речи&lt;/b&gt;.</translation>
    
YES, The translation is problematic. The phrase "Молимо користи приступну фразу од десет или више насумичних карактера" is grammatically incorrect. Also, the bolding is applied incorrectly.
Correct translation: Унесите нову приступну фразу за новчаник.<br/>Молимо користите приступну фразу од <b>десет или више насумичних карактера</b>, или <b>осам или више речи</b>.
```

```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Упамти, шифрирање новчаника не може у потуности заштити твоје биткоине од крађе од стране малвера инфицира твој рачунар.</translation>
    
YES, The translation is problematic because the verb "инфицира" (inficira) is in the present tense, singular, third person, which doesn't agree with the plural noun "малвера" (malvera) or the implied plural noun "твој рачунар" (your computer). The correct verb form should be in the plural or past tense.

The correct translation is:
Упамти, шифрирање новчаника не може у потуности заштити твоје биткоине од крађе од стране малвера који инфицирају твој рачунар.
```

```
        <source>Warning: The Caps Lock key is on!</source>
        <translation>Упозорање Caps Lock дугме укључено!</translation>
    
YES, The translation is missing a period at the end of the sentence. The phrase "Upozorenje" (Warning) should also be followed by a colon. The correct translation is: "Упозорење: Caps Lock дугме је укључено!"
```

```
        <source>Amount</source>
        <translation>Износ</translation>
    
YES, The translation is incorrect. "Amount" in the context of Bitcoin transactions refers to the quantity of Bitcoin being sent, not the depreciation or consumption of an asset. The correct translation for "Amount" in this context would be "Износ".
The correct translation is:

        <source>Amount</source>
        <translation>Износ</translation>
```

```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>Унеси Биткоин адресу, (нпр %1)</translation>
    
YES, The translation uses a comma after "адресу" and before "(нпр %1)". The correct translation should not have this comma.
Унеси Биткоин адресу (нпр %1)
```

```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>Блокирана предаја</translation>
    
YES
The translation "Блокирана предаја" which means "Blocked transmission" or "Blocked relay" is incorrect. The source text "Block Relay" refers to relaying blocks, not blocking them. The correct translation should convey the idea of relaying blocks.

NO
```

```
        <source>Create a new wallet</source>
        <translation>Направи нови ночаник</translation>
    
YES, The translation is incorrect and problematic. The word "ночаник" is not a recognized word in Serbian. The correct translation for "wallet" in this context would be "novčanik".
NO
```

```
        <source>Change Passphrase…</source>
        <translation>Измени приступну фразу</translation>
    
YES
The translation uses a singular imperative verb ("Измени") which is informal and inappropriate for the context of a user interface. The correct translation should use a plural or formal imperative verb.

Correct translation: Измените приступну фразу…
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Потписуј поруку са своје Биткоин адресе као доказ да си њихов власник</translation>
    
YES - The translation uses the informal second-person singular pronoun "си" when the English "you" is likely intended to be general or formal. Additionally, the possessive pronoun "њихов" is not correctly placed. The correct translation should use the formal second-person plural pronoun "своје" and adjust the possessive pronoun accordingly.

NO - Potpisujte poruke svojim Bitcoin adresama kao dokaz da ih posedujete.
```

```
        <source>Show the list of used sending addresses and labels</source>
        <translation>Прегледајте листу коришћених адреса и етикета за слање уплата</translation>
    
YES - The translation uses "уплата" which translates to "payment" or "deposit", but the source text refers to "sending addresses". It should reflect sending rather than receiving or payment in general.
The correct translation should be:
Прегледајте листу коришћених адреса и етикета за слање
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>Учитај ”PSBT” из привремене меморије</translation>
    
YES, The translation is problematic because it is missing the "..." ellipsis from the source text.
Load PSBT from clipboard…
```

```
        <source>Node window</source>
        <translation>Ноде прозор</translation>
    
YES, The translation of "Node window" to "Ноде прозор" is not a natural or accurate Serbian translation. The word "prozor" means "window" in Serbian, but "Node" is a technical term that should likely be translated more directly or kept as is, depending on context. However, "Ноде прозор" sounds like a direct, unidiomatic transliteration.

A more appropriate translation would be to use the English term "Node" as it's commonly understood in technical contexts, or if a Serbian equivalent is preferred and understood, it would be more context-specific. Given the Bitcoin context, keeping "Node" is often preferred.

Correct translation: Node prozor (keeping "Node" as is) or Прозор за чвор (more literal Serbian translation of "node" as "чвор", but less common in technical contexts). However, "Node prozor" is the most likely expected translation in this context.
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Прикажи  поруку помоћи %1 за листу са могућим опцијама Биткоин командне линије</translation>
    
YES, The translation is problematic because of an extra space before the format specifier %1.
The correct translation is: Прикажи поруку помоћи %1 за листу са могућим опцијама Биткоин командне линије
```

```
        <source>Mask the values in the Overview tab</source>
        <translation>Филтрирај вредности у картици за преглед</translation>
    
UNK_LANG
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Прикажи картицу са ”Клијентима”</translation>
    
YES, The translation is incorrect. The word "Peers" in the context of Bitcoin refers to other nodes on the network, not "clients". A better translation would be "членовима" or "учесницима".

NO
```

```
        <source>Amount: %1
</source>
        <translation>Износ: %1
</translation>
    
YES. The Serbian word "Износ" translates to "amount" or "sum" in English, but in the context of Bitcoin transactions, "amount" typically refers to the value being transferred or the change returned. A more appropriate translation for "amount" in this context would be "Износ" or "Сума". However, the word "Износ" can also mean "wear and tear" or "depreciation" in other contexts, which could be misleading if not clearly defined as the transaction amount. Given the Bitcoin context, it's crucial to use a term that unambiguously refers to a monetary value. A better translation would be "Износ: %1" which is the direct translation and commonly used.

Correct translation: Износ: %1
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Новчаник јс &lt;b&gt;шифриран&lt;/b&gt; и тренутно &lt;b&gt;откључан&lt;/b&gt;</translation>
    
YES, The word "јс" is a typo and should be "је".
Новчаник је &lt;b&gt;шифриран&lt;/b&gt; и тренутно &lt;b&gt;откључан&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Новчаник јс &lt;b&gt;шифрован&lt;/b&gt; и тренутно &lt;b&gt;закључан&lt;/b&gt;</translation>
    
YES, The Serbian translation uses "јс" which is not a valid word in Serbian. It seems like a misspelling or an incomplete word. The correct word should be "је" which means "is".

Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;
Новчаник је &lt;b&gt;шифрован&lt;/b&gt; и тренутно &lt;b&gt;закључан&lt;/b&gt;
```

```
        <source>Amount:</source>
        <translation>Износ:</translation>
    
YES, The translation of "Amount:" to "Износ:" is incorrect in the context of Bitcoin transactions. "Износ" refers to wear and tear or depreciation, not the monetary value. The correct translation for "Amount" in this context is "Износ".

NO
```

```
        <source>Amount</source>
        <translation>Износ</translation>
    
YES, The translation is incorrect. "Amount" in the context of Bitcoin transactions refers to the quantity of Bitcoin being sent, not the depreciation or consumption of an asset. The correct translation for "Amount" in this context would be "Износ".
The correct translation is:

        <source>Amount</source>
        <translation>Износ</translation>
```

```
        <source>Unlock unspent</source>
        <translation>Откључај непотрошено</translation>
    
UNK_LANG
```

```
        <source>change from %1 (%2)</source>
        <translation>Измени од %1 (%2)</translation>
    
YES, The translation is not accurate. In the context of Bitcoin, "change" refers to the return amount of Bitcoin after a transaction, not a modification or alteration. The Serbian word "Измени" means "changes" or "modifications". A more appropriate translation would be "Повраћај" which means "return" or "change" in the financial sense.

The correct translation is:
<translation>Повраћај од %1 (%2)</translation>
```

```
        <source>Create wallet warning</source>
        <translation>Направи упозорење за новчаник</translation>
    
YES, The translation is problematic. The word "warning" is translated as "упозорење" which means warning in Serbian. However, the phrase "Create wallet warning" in English is likely a heading or a title for a warning message related to wallet creation. A more accurate translation for a title like this would be "Упозорење при креирању новчаника" or simply "Упозорење за новчаник". The current translation "Направи упозорење за новчаник" literally translates to "Make a warning for a wallet" which is not grammatically correct or natural in Serbian for a title.

Correct translation: Упозорење при креирању новчаника
```

```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>Da li si siuran da želiš da preneseš novčanik &lt;i&gt;%1&lt;/i&gt;? </translation>
    
YES, The word "siuran" is a misspelling of "siguran". Also, there is an extra space before the ".".
Da li ste sigurni da želite da prenesete novčanik <i>%1</i>?
```

```
        <source>Migration Successful</source>
        <translation>Prenošenje novčanika je uspešno</translation>
    
YES - The Serbian translation "Prenošenje novčanika je uspešno" is a literal translation of "Wallet transfer is successful" and does not accurately reflect the source text "Migration Successful". In the context of Bitcoin, "migration" can refer to various processes, not just wallet transfers. The correct translation should be more general.
Correct translation: Migracija uspešna
```

```
        <source>Opening Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the open wallet progress window which indicates to the user which wallet is currently being opened.</extracomment>
        <translation>Отвањаре новчаника &lt;b&gt;%1&lt;/b&gt;</translation>
    
YES, The translation is inaccurate. The Serbian word "Отвањаре" does not exist. It seems to be a typo.
Opening Wallet <b>%1</b>… -> Otvaranje novčanika <b>%1</b>…
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Онемогући приватни кључ за овај новчаник. Новчаници са онемогућеним приватним кључем неће  имати приватни кључ и не могу имати HD семе или увезени приватни кључ. Ова опција идеална је за новчанике који су искључиво за посматрање.</translation>
    
YES, The translation is problematic because it uses singular forms of "private key" and "wallet" when the source text uses plural forms. Additionally, it uses an incorrect Serbian word for "seed".

NO
```

```
        <source>Make a blank wallet. Blank wallets do not initially have private keys or scripts. Private keys and addresses can be imported, or an HD seed can be set, at a later time.</source>
        <translation>Направи празан новчаник. Празни новчанци немају приватане кључеве или скрипте. Приватни кључеви могу се увести, или HD семе може бити постављено касније.</translation>
    
YES, "приватане" should be "приватне".
Направи празан новчаник. Празни новчаници немају приватне кључеве или скрипте. Приватни кључеви могу се увести, или HD семе може бити постављено касније.
```

```
        <source>Edit Address</source>
        <translation>Измени адресу</translation>
    
YES
The translation is grammatically incorrect in Serbian. The noun "address" should be in the accusative case and singular form, which is "адресу" (adresu) if it refers to a specific address, or "адресу" (adresu) if it refers to a general address. The verb "Edit" should be in the imperative form, singular or plural depending on the context. Assuming the context is a button to edit a single address, "Измени адресу" (Izmeni adresu) is correct. However, the provided translation uses "Измени адресу" which is grammatically incorrect for a singular noun in this context.

Correct translation: Измени адресу
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>Адреса повезана са овом ставком из листе адреса. Ово можете променити једини у случају адреса за плаћање.</translation>
    
YES, The translation is not accurate. The Serbian word "плаћање" means "payment" or "paying", but the English word "sending" in this context refers to the action of sending Bitcoin. The correct Serbian word for "sending" in this context is "слање". Also, "једини у случају" is an awkward phrasing, and "само" or "једино" would be better.

The address associated with this address list entry. This can only be modified for sending addresses.
Адреса повезана са овим уносом у листу адреса. Ово се може изменити само за адресе за слање.
```

```
        <source>Edit receiving address</source>
        <translation>Измени адресу за примање</translation>
    
YES, The translation is inaccurate. In Serbian, the genitive case should be used for "address" after the preposition "for". Additionally, the adjective "receiving" should be in the genitive case as well to agree with "address".

Correct translation: Измени адресу за примање
```

```
        <source>Edit sending address</source>
        <translation>Измени адресу за слање</translation>
    
YES, The translation should be "Измени адресу за слање" instead of "Измени адресу за слање". The second word should be "адресу" and not "адресу".
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Најмање %1 GB подататака биће складиштен у овај директорјиум који ће временом порасти.</translation>
    
YES, The word "директорјиум" is misspelled, it should be "директоријум".
NO, At least %1 GB of data will be stored in this directory, and it will grow over time.
```

```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Најмање %1 GB подататака биће складиштен у овај директорјиум.</translation>
    
YES: The Serbian translation incorrectly uses "Најмање" (at least) instead of "Приближно" (approximately). Additionally, "директорјиум" is a misspelling of "директоријуму".

Correct translation: Приближно %1 GB података биће складиштено у овом директоријуму.
```

```
        <source>%1 will download and store a copy of the Bitcoin block chain.</source>
        <translation>%1 биће преузеће и складиштити копију Биткоин ланца блокова.</translation>
    
YES, The translation is grammatically incorrect. The correct translation should be: "%1 ће преузети и сачувати копију биткоин ланца блокова."
```

```
        <source>Error: Specified data directory "%1" cannot be created.</source>
        <translation>Грешка: Одабрана датотека  "%1" не може бити креирана.</translation>
    
YES: The word "data directory" was mistranslated as "file".
Correct translation: Грешка: Одабрани директоријум за податке "%1" не може бити креиран.
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Налепите адресу из базе за копирање</translation>
    
YES - The translation "Налепите адресу из базе за копирање" is incorrect. "Базе за копирање" translates to "copy database" which is not the correct term for clipboard. The correct term for clipboard in Serbian is "клипборд" or "одражавајућа плоча".

NO
```

```
        <source>Number of script verification threads</source>
        <translation>Број скрипти и CPU за верификацију</translation>
    
YES
The translation is inaccurate. The original English phrase refers to the number of threads for script verification, not the number of scripts and CPU for verification.

Correct translation: Број нити за верификацију скрипти
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Приказује се ако је испоручени уобичајени SOCKS5 проxy коришћен ради проналажења клијената преко овог типа мреже. </translation>
    
YES, The translation erroneously uses "клијената" (clients) instead of "peers" (peer).
The correct translation should be: "Приказује се ако је испоручени уобичајени SOCKS5 проxy коришћен ради проналажења peer-ова преко овог типа мреже."
```

```
        <source>Prune block storage to</source>
        <translation>Сакрати block складиштење на</translation>
    
YES, the translation is problematic because it uses Cyrillic script for the word "block" which is not the standard Serbian Latin script and it appears to be a direct transliteration from English which makes it unnatural and incorrect.
The Serbian Latin script is the standard for written Serbian.
The correct translation is: Smanjite skladištenje blokova na
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Враћање ове опције захтева да поновно преузимање целокупонг блокчејна.</translation>
    
YES, The word "целокупонг" is a misspelling of "целокупно".
Враћање ове опције захтева поновно преузимање целокупног блокчејна.
```

```
        <source>Connect to the Bitcoin network through a SOCKS5 proxy.</source>
        <translation>Конектуј се на Биткоин мрежу кроз SOCKS5 проксијем.</translation>
    
YES, The grammatical case of "SOCKS5 proxy" is incorrect in Serbian. It should be in the instrumental case to agree with "кроз" (through).
Конектуј се на Биткоин мрежу кроз SOCKS5 прокси.</translation>
```

```
        <source>Connect through SOCKS5 proxy (default proxy):</source>
        <translation>Конектуј се кроз SOCKS5 прокси (уобичајени прокси):</translation>
    
YES - The translation uses "уобичајени прокси" which means "usual proxy" or "common proxy" instead of "default proxy". The correct translation for "default proxy" is "подразумевани прокси".
NO
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>минимизирај у доњу линију, уместо у програмску траку</translation>
    
YES, The Serbian translation is grammatically incorrect and does not accurately convey the meaning of the English source text. "Donju liniju" is not a standard term for a system tray. The correct Serbian term for "tray" in this context is "системска палета".

The corrected translation is: "Минимизирај у системску палету уместо у програмску траку".
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>Салдорударења у адресама које су у моду само гледање, који још увек није доспео</translation>
    
YES. The translation contains a grammatical error and an incorrect word choice. The word "Салдорударења" is not a valid Serbian word.

The correct translation should be: "Стање на адресама само за гледање које још увек није доспело"
```

```
        <source>Signed %1 inputs, but more signatures are still required.</source>
        <translation>Потписано %1 поље, али је потребно још потписа.</translation>
    
YES, the translation is problematic because the word "поље" (field) is an incorrect translation of "inputs" in the context of Bitcoin. The correct translation for "inputs" in this context is "улаза".
NO
```

```
        <source>own address</source>
        <translation>сопствена адреса</translation>
    
YES, the translation contains an error. The correct translation should be "ваша адреса" or "власничка адреса".
YES, сопствена адреса
```

```
        <source>Transaction has %1 unsigned inputs.</source>
        <translation>Трансакција има %1 непотписана поља.</translation>
    
YES, The word "поља" (fields) is not the correct translation for "inputs" in the context of Bitcoin transactions. The correct translation would be "улаза" (inputs).
The correct translation is: Трансакција има %1 непотписана улаза.
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Не могу покренути биткоин: "кликни-да-платиш" механизам</translation>
    
YES, the translation uses Cyrillic script while the provided language code is 'sr' which indicates Serbian Latin script. Also, "механизам" is not a good translation for "handler" in this context.

Correct translation would be:
NO
```

```
        <source>URI handling</source>
        <translation>URI руковање</translation>
    
YES, The translation is incorrect. The Serbian word "rukovanje" means "handshake", which is not appropriate in this context. The correct translation for "URI handling" in Serbian is " rukovanje URI-jem".
The translation is problematic because "rukovanje" means "handshake". The correct translation for "URI handling" in Serbian is "rukovanje URI-jem" or "obrada URI-ja".

URI rukovanje
```

```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>'bitcoin://' није важећи URI. Уместо тога користити  'bitcoin:'.</translation>
    
YES, The translation erroneously added an extra space before the closing quote in the phrase "Уместо тога користити 'bitcoin:'." The correct translation should have no space before the closing quote.
'bitcoin://' није важећи URI. Уместо тога користити 'bitcoin:'.
```

```
        <source>Save Image…</source>
        <translation>Сачували слику…</translation>
    
YES, The translation is grammatically incorrect and sounds unnatural in Serbian. The verb "Сачували" is in the past plural form, implying multiple subjects saved the image, while the English "Save Image…" is an imperative phrase with an implied singular subject.

Correct translation: Сачувај слику…
```

```
        <source>Resulting URI too long, try to reduce the text for label / message.</source>
        <translation>Дати резултат URI  предуг, покушај да сманиш текст за ознаку / поруку.</translation>
    
YES, The translation contains a spelling error. "предуг" should be "предугачак".

Дати резултат URI пре-дугачак, покушај да смањиш текст за ознаку / поруку.
```

```
        <source>Memory Pool</source>
        <translation>Удружена меморија</translation>
    
YES
The translation "Удружена меморија" is a literal translation of "pooled memory" but it is not the standard or correct term used in the Serbian Bitcoin community. It can be confusing as it literally translates to "associated/joined memory". The more common and accurate term is a direct transliteration "Мемпул" (Mempul) or "Базен меморије" (Memory pool, using "bazen" for "pool").
Correct translation: Мемпул
```

```
        <source>Select a peer to view detailed information.</source>
        <translation>Одабери колегу да би видели детаљне информације</translation>
    
YES, the translation is problematic because the verb "видети" (videti - to see) is in the second person plural, while the imperative "Одабери" (Odaberi - Select) is in the second person singular. This creates an inconsistency in the grammatical person.

Correct translation: Одабери колегу да би видео/видела детаљне информације. (Odaberi kolegu da bi video/videla detaljne informacije.)
```

```
        <source>The mapped Autonomous System used for diversifying peer selection.</source>
        <translation>Мапирани аутономни систем који се користи за диверсификацију селекције колега чворова.</translation>
    
YES, The translation uses a word that means "node peers" which is not present in the source. The correct translation should be: "Мапирани аутономни систем који се користи за диверсификацију избора колега."
```

```
        <source>Node window</source>
        <translation>Ноде прозор</translation>
    
YES, The translation of "Node window" to "Ноде прозор" is not a natural or accurate Serbian translation. The word "prozor" means "window" in Serbian, but "Node" is a technical term that should likely be translated more directly or kept as is, depending on context. However, "Ноде прозор" sounds like a direct, unidiomatic transliteration.

A more appropriate translation would be to use the English term "Node" as it's commonly understood in technical contexts, or if a Serbian equivalent is preferred and understood, it would be more context-specific. Given the Bitcoin context, keeping "Node" is often preferred.

Correct translation: Node prozor (keeping "Node" as is) or Прозор за чвор (more literal Serbian translation of "node" as "чвор", but less common in technical contexts). However, "Node prozor" is the most likely expected translation in this context.
```

```
        <source>The direction and type of peer connection: %1</source>
        <translation>Смер и тип конекције клијената: %1</translation>
    
YES, The translation uses the word "клијената" which translates to "clients" in English. The source text uses the word "peer" which refers to peers in the Bitcoin network. Therefore, the translation is inaccurate. A more accurate translation would be:

Смер и тип конекције peer-ова: %1
```

```
        <source>Ping Wait</source>
        <translation>Чекање на пинг</translation>
    
YES, The translation is not appropriate. The source text "Ping Wait" in the context of Bitcoin typically refers to a delay or waiting period associated with network activity or a connection check. The provided translation "Чекање на пинг" is in Macedonian, not Serbian.

NO
```

```
        <source>Debug log file</source>
        <translation>Дебугуј лог фајл</translation>
    
YES, The translation contains an error. The word "Debug" should be translated as "Дебаг" and not "Дебугуј". Also, the phrase "log file" should be translated as "лог датотеку" or "лог фајл".

Correct translation: Дебаг лог фајл
```

```
        <source>Outbound Block Relay: does not relay transactions or addresses</source>
        <extracomment>Explanatory text for an outbound peer connection that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>Оутбоунд Блоцк Релаи: не преноси трансакције или адресе</translation>
    
YES, The translation is not accurate and uses Latin script instead of Cyrillic script, which is the standard for Serbian. The term "Outbound Block Relay" should be translated to Serbian.
Оутбоунд Блоцк Релаи: не преноси трансакције или адресе
```

```
        <source>the peer selected us for high bandwidth relay</source>
        <translation>клијент нас је одабрао за висок пренос података</translation>
    
YES, The translation is inaccurate. The source text uses "peer" which in the context of Bitcoin refers to a node in the network. The translation uses "клијент" (client), which is not the correct term.

NO
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
    
YES, the translation contains a grammatical error in the sentence "За више информација о коришћењу конзоле, притисни %6". The verb "притисни" (press) is in the singular imperative form, but the context suggests addressing multiple users or a general instruction, where "притисните" (press) would be more appropriate. Also, the word "комплексности" (complexity) is not the best choice to convey "ramifications" in this context. "Последице" (consequences) would be more fitting.
Добродошли у %1 "RPC” конзолу.
Користи тастере за горе и доле да наводиш историју, и %2 да очистиш екран.
Користи %3 и %4 да увећаш и смањиш величину фонта.
Унеси %5 за преглед доступних комади.
За више информација о коришћењу конзоле, притисните %6
%7 УПОЗОРЕЊЕ: Преваранти су се активирали, говорећи корисницима да уносе команде овде, и тако краду садржај новчаника. Не користи ову конзолу без потпуног схватања последица ове команде. %8
```

```
        <source>(peer: %1)</source>
        <translation>(клијент: %1)</translation>
    
YES, The word "peer" in English often refers to another node on the Bitcoin network, which could be translated to "peer" or "connected node". The Serbian translation "клијент" (client) implies a one-way relationship where one party requests services from another, which is not always the case in a peer-to-peer network like Bitcoin.
The correct translation should reflect the peer-to-peer nature of the connection.
(peer: %1)
```

```
        <source>To</source>
        <translation>За</translation>
    
YES: The translation is incorrect. In the context of Bitcoin transactions, "To" should be translated as "Ка" or "До" when referring to the recipient's address. "За" translates to "For" or "About" in English.
Ка
```

```
        <source>Amount:</source>
        <translation>Износ:</translation>
    
YES, The translation of "Amount:" to "Износ:" is incorrect in the context of Bitcoin transactions. "Износ" refers to wear and tear or depreciation, not the monetary value. The correct translation for "Amount" in this context is "Износ".

NO
```

```
        <source>Amount:</source>
        <translation>Износ:</translation>
    
YES, The translation of "Amount:" to "Износ:" is incorrect in the context of Bitcoin transactions. "Износ" refers to wear and tear or depreciation, not the monetary value. The correct translation for "Amount" in this context is "Износ".

NO
```

```
        <source>Save Image…</source>
        <translation>Сачували слику…</translation>
    
YES, The translation is grammatically incorrect and sounds unnatural in Serbian. The verb "Сачували" is in the past plural form, implying multiple subjects saved the image, while the English "Save Image…" is an imperative phrase with an implied singular subject.

Correct translation: Сачувај слику…
```

```
        <source>Amount:</source>
        <translation>Износ:</translation>
    
YES, The translation of "Amount:" to "Износ:" is incorrect in the context of Bitcoin transactions. "Износ" refers to wear and tear or depreciation, not the monetary value. The correct translation for "Amount" in this context is "Износ".

NO
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Коришћење безбедносне накнаде може резултовати у времену потребно за потврду трансакције од неколико сати или дана (или никад). Размислите о ручном одабиру провизије или сачекајте док нисте потврдили комплетан ланац.</translation>
    
YES, The translation of "fallbackfee" to "безбедносне накнаде" (security fee) is incorrect in this context. The correct term for "fallback fee" in Bitcoin transactions is "резервна провизија" or "зализна провизија".

The translation of "validated the complete chain" to "потврдили комплетан ланац" is also slightly awkward. A more natural phrasing would be "синхронизовали цео ланац" (synchronized the entire chain) or "потврдили цео блокчејн" (validated the entire blockchain).

NO
```

```
        <source>Inputs…</source>
        <translation>Поља...</translation>
    
YES, The Serbian translation for "Inputs" should be "Улази" or "Улазни подаци" in the context of Bitcoin transactions, not "Поља" which means "fields".
NO
```

```
        <source>Set external signer script path in Options -&gt; Wallet</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Подси екстерну скрипту за потписивање у : Options -&gt; Wallet</translation>
    
YES, The translation incorrectly attempts to translate "Set" into "Подси" which is not a valid Serbian word in this context and appears to be a mistranslation or typo. The correct Serbian word for "Set" in this context would be "Постави" or "Наместти".

NO
```

```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>Не сигнализира Замени-са-Провизијом, BIP-125.</translation>
    
YES, The translation is problematic because "Замени-са-Провизијом" is an incorrect translation of "Replace-By-Fee". The correct translation for "Replace-By-Fee" in Serbian, in the context of Bitcoin, is "Замена по накнади" or "Замена по плаћању".

NO
```

```
        <source>Amount:</source>
        <translation>Износ:</translation>
    
YES, The translation of "Amount:" to "Износ:" is incorrect in the context of Bitcoin transactions. "Износ" refers to wear and tear or depreciation, not the monetary value. The correct translation for "Amount" in this context is "Износ".

NO
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Биткоин адреса на коју се шаље уплата</translation>
    
YES, The translation is problematic because it uses the wrong case for "адреса". The correct case is "адреса".

The Bitcoin address to send the payment to
Биткоин адреса на коју се шаље уплата
```

```
        <source>Paste address from clipboard</source>
        <translation>Налепите адресу из базе за копирање</translation>
    
YES
The translation is inaccurate. "базе за копирање" translates to "copying database" which is not the correct term for clipboard.

Correct translation: Налепите адресу са отпремљене меморије
```

```
        <source>The amount to send in the selected unit</source>
        <translation>Износ који ће бити послат у одабрану јединицу</translation>
    
YES
The translation is inaccurate. "Износ који ће бити послат у одабрану јединицу" translates to "The amount that will be sent in the selected unit". The English source text is "The amount to send in the selected unit", which is more direct. Also, "износ" means "amount" or "sum", and it is used here appropriately. However, the verb "износ" in Serbian means "to spend", "to expend", or "to wear out". This is not what the English text implies. The correct translation would be "Износ који треба послати у одабрану јединицу".

Correct translation: Износ који треба послати у одабрану јединицу
```

```
        <source>A message that was attached to the bitcoin: URI which will be stored with the transaction for your reference. Note: This message will not be sent over the Bitcoin network.</source>
        <translation>Порука која је приложена биткоину: URI која ће бити сачувана уз трансакцију ради референце. Напомена: Ова порука се шаље преко Биткоин мреже.</translation>
    
YES, The translation incorrectly states that the message "will be sent over the Bitcoin network" when the source text clearly states it will not be sent. The correct translation should reflect this.
NO, Порука која је приложена биткоину: URI која ће бити сачувана уз трансакцију ради референце. Напомена: Ова порука се не шаље преко Биткоин мреже.
```

```
        <source>Paste address from clipboard</source>
        <translation>Налепите адресу из базе за копирање</translation>
    
YES
The translation is inaccurate. "базе за копирање" translates to "copying database" which is not the correct term for clipboard.

Correct translation: Налепите адресу са отпремљене меморије
```

```
        <source>The Bitcoin address the message was signed with</source>
        <translation>Биткоин адреса са којом је потписана порука</translation>
    
YES, The Serbian translation has a grammatical error. The word "адреса" (address) is singular, but the phrase "са којом је потписана порука" (with which the message was signed) implies a singular address. However, the structure of the Serbian sentence suggests it's referring to the address in a general sense, but grammatically, it should be plural if it's implied that there could be multiple addresses or if it's a more formal, generalized statement. A more accurate translation would use the genitive plural for "адреса" if it's meant as "Bitcoin addresses" or keep it singular if it's strictly referring to one specific address. Given the context of a message being signed *with* an address, it's most likely referring to a single address. The grammatical issue is the case agreement with the prepositional phrase.

Correct translation: Биткоин адреса са којом је порука потписана
```

```
        <source>Verify the message to ensure it was signed with the specified Bitcoin address</source>
        <translation>Потврдите поруку да осигурате да је потписана са одговарајућом Биткоин адресом</translation>
    
YES, the translation is not accurate. The English text mentions a "specified" Bitcoin address, implying a particular address was provided or intended. The Serbian translation uses "одговарајућом" which translates to "appropriate" or "corresponding", which is not the same as "specified".

NO
```

```
        <source>conflicted with a transaction with %1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that conflicts with a confirmed transaction.</extracomment>
        <translation>постоји неусаглашеност са трансакцијом са %1 потврда</translation>
    
YES, The translation is problematic. It is not an accurate or natural-sounding translation for the provided English source text. The phrase "постоји неусаглашеност" (there is a disagreement/inconsistency) is not the standard or idiomatic way to express a conflict in a Bitcoin transaction context.

A more accurate and natural translation would be:

YES, u sukobu sa transakcijom sa %1 potvrda
```

```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>%1 порврде</translation>
    
YES. The translation for "%1 confirmations" is incorrect. The word "порврде" is not a valid Serbian word. The correct translation should be "%1 potvrde".

NO
```

```
        <source>To</source>
        <translation>За</translation>
    
YES: The translation is incorrect. In the context of Bitcoin transactions, "To" should be translated as "Ка" or "До" when referring to the recipient's address. "За" translates to "For" or "About" in English.
Ка
```

```
        <source>own address</source>
        <translation>сопствена адреса</translation>
    
YES, the translation contains an error. The correct translation should be "ваша адреса" or "власничка адреса".
YES, сопствена адреса
```

```
        <source>Credit</source>
        <translation>Заслуге</translation>
    
YES, The Serbian translation "Заслуге" means "merits" or "credits" in a general sense. In the context of Bitcoin, "Credit" would more appropriately translate to "Кредит" (Kredit) if it refers to a credit of funds, or possibly "Упис" (Upis) if it refers to an entry or deposit. "Заслуге" does not fit the financial context of Bitcoin.

Correct translation: Кредит
```

```
        <source>Generated coins must mature %1 blocks before they can be spent. When you generated this block, it was broadcast to the network to be added to the block chain. If it fails to get into the chain, its state will change to "not accepted" and it won't be spendable. This may occasionally happen if another node generates a block within a few seconds of yours.</source>
        <translation>Генерисани новчићи морају доспети %1 блокова пре него што могу бити потрошени. Када генеришете овај блок, он се емитује у мрежу, да би био придодат на ланац блокова. Укупно не успе да се придода на ланац, његово стање се мења у "није прихваћен" и неће га бити могуће потрошити. Ово се може повремено десити уколико други чвор генерише блок у периоду од неколико секунди од вашег.</translation>
    
YES, The Serbian translation has a grammatical error. The phrase "Укупно не успе да се придода на ланац" translates to "Totally fails to be added to the chain", which is not the intended meaning. The correct translation should be "If it fails to be added to the chain".

Correct translation: Генерисани новчићи морају доспети %1 блокова пре него што могу бити потрошени. Када генеришете овај блок, он се емитује у мрежу, да би био придодат на ланац блокова. Ако не успе да се придода на ланац, његово стање се мења у "није прихваћен" и неће га бити могуће потрошити. Ово се може повремено десити уколико други чвор генерише блок у периоду од неколико секунди од вашег.
```

```
        <source>Amount</source>
        <translation>Износ</translation>
    
YES, The translation is incorrect. "Amount" in the context of Bitcoin transactions refers to the quantity of Bitcoin being sent, not the depreciation or consumption of an asset. The correct translation for "Amount" in this context would be "Износ".
The correct translation is:

        <source>Amount</source>
        <translation>Износ</translation>
```

```
        <source>Conflicted</source>
        <translation>Неуслагашен</translation>
    
YES, The Serbian translation "Неуслагашен" is incorrect and does not convey the meaning of "Conflicted" in the context of Bitcoin transactions. "Conflicted" in Bitcoin usually refers to a transaction that is in a state of conflict or dispute, such as a double-spend attempt. The provided translation seems to be an attempt to translate "unattended" or "unresolved" which is not accurate for the Bitcoin context. A more appropriate translation would be "У сукобу" or "У конфронтацији".

However, I cannot provide the correct translation as per the instructions.
UNK_LANG
```

```
        <source>Transaction status. Hover over this field to show number of confirmations.</source>
        <translation>Статус трансакције. Пређи мишем преко поља за приказ броја трансакција.</translation>
    
YES, The translation incorrectly translates "number of confirmations" to "broja трансакција" (number of transactions). The correct translation for "number of confirmations" in the context of Bitcoin is "броја потврда".
The correct translation is: Статус трансакције. Пређи мишем преко поља за приказ броја потврда.
```

```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Без обзира да ли је у ову трансакције укључена или није - адреса само за гледање.</translation>
    
YES, The word order in the Serbian translation is unnatural and grammatically incorrect. The phrase "адреса само за гледање" should precede the verb "укључена".

NO
```

```
        <source>Amount removed from or added to balance.</source>
        <translation>Износ одбијен или додат салду.</translation>
    
YES, The translation is problematic. The word "Износ" means "amount" or "sum" in Serbian, but the word "odnos" means "relation" or "ratio". The correct word to use here would be "iznos". Additionally, the word "odnos" does not fit the context of Bitcoin transactions.

Correct translation: Износ уклоњен са или додат на биланс.
```

```
        <source>Copy transaction ID</source>
        <translation>Копирај трансакцију ID</translation>
    
YES, The translation uses the word "трансакцију" which is a transliteration of "transaction" but it is used incorrectly. The correct word for transaction is "трансакцију" when it is in the accusative case, but in this context it should be in the genitive case which is "трансакције". The translation should be "Копирај ID трансакције" or "Копирај идентификатор трансакције".
NO
```

```
        <source>Edit address label</source>
        <translation>Promeni adresu etikete</translation>
    
YES
The translation is inaccurate and misinterprets the meaning of the English source text. The source text "Edit address label" means to change the label associated with a Bitcoin address. The provided translation "Promeni adresu etikete" literally means "Change the address of the label," which is nonsensical in the context of Bitcoin.

Correct translation: Promeni oznaku adrese
```

```
        <source>Create a new wallet</source>
        <translation>Направи нови ночаник</translation>
    
YES, The translation is incorrect and problematic. The word "ночаник" is not a recognized word in Serbian. The correct translation for "wallet" in this context would be "novčanik".
NO
```

```
        <source>Confirm fee bump</source>
        <translation>Потврдите ударну провизију</translation>
    
YES, The translation is problematic because "ударну" which translates to "strike" or "impact" does not convey the intended meaning of "bump" in the context of a Bitcoin fee. A fee bump in Bitcoin refers to increasing a transaction fee to speed up confirmation. The word "bump" is often used informally, and a more appropriate translation would reflect the act of increasing or raising the fee.

NO
```

```
        <source>The transaction amount is too small to send after the fee has been deducted</source>
        <translation>Износ трансакције је толико мали за слање након што се одузме провизија</translation>
    
YES, The Serbian translation uses "Износ трансакције је толико мали за слање након што се одузме провизија" which translates to "The transaction amount is so small for sending after the commission is deducted". The original English sentence states that the amount is too small to send *after* the fee is deducted, meaning the remaining amount is too small. The Serbian translation implies that the transaction amount itself is too small for sending, and the commission is also deducted. A more accurate translation would be: "Износ трансакције је премали да би се послао након одбитка провизије".
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Ову провизију можете обрисати уколико је кусур мањи од нивоа прашине</translation>
    
YES, The translation is problematic because it is not a good translation of the original text. The original text is about Bitcoin, and the translation is not relevant to Bitcoin. The translation is also not grammatically correct. The correct translation is: "Ovu naknadu možete odbaciti ako je kusur manji od prašine na ovom nivou."
```

```
        <source>Unable to replay blocks. You will need to rebuild the database using -reindex-chainstate.</source>
        <translation>Блокове није могуће поново репродуковати. Ви ћете морати да обновите базу података користећи -reindex-chainstate.</translation>
    
YES, The translation is problematic because "reproduced" is not the correct word to use in this context. In the context of Bitcoin, "replay" refers to re-processing transactions. Therefore, the translation should use a word that conveys the meaning of re-processing.
The correct translation is: Блокове није могуће поново обрадити. Мораћете да поново изградите базу података користећи -reindex-chainstate.
```

```
        <source>Warning: We do not appear to fully agree with our peers! You may need to upgrade, or other nodes may need to upgrade.</source>
        <translation>Упозорење: Изгледа да се ми у потпуности не слажемо са нашим чворовима! Можда постоји потреба да урадите надоградњу, или други чворови морају да ураде надоградњу.</translation>
    
YES, The translation has an error. The word "peers" is translated as "чворовима" (nodes) instead of "peer" (drugim čvorovima or kolegama). The correct translation should be:
Упозорење: Изгледа да се ми у потпуности не слажемо са нашим вршњацима! Можда постоји потреба да урадите надоградњу, или други чворови морају да ураде надоградњу.
```

```
        <source>Cannot resolve -%s address: '%s'</source>
        <translation>Не могу решити -%s адреса: '%s'</translation>
    
YES, The translation uses the incorrect word for "address" in Serbian. The correct word should be "адресу" (adresa) instead of "адреса" (adresa). The use of a hyphen before the first placeholder is also unusual and might be a typo.

The correct translation should be:
Не могу да решим адресу '%s': '%s'
```

```
        <source>The transaction amount is too small to pay the fee</source>
        <translation>Износ трансакције је сувише мали да се плати трансакција</translation>
    
YES, The translation is not accurate and conveys an incorrect meaning. The original sentence states that the transaction amount is too small to pay the fee. The translated sentence states that the transaction amount is too small to pay the transaction itself, which is not the intended meaning.
Correct translation: Износ трансакције је сувише мали да би се платила провизија
```

```
        <source>This is experimental software.</source>
        <translation>Ово је експерименталн софтвер.</translation>
    
YES, The word "експерименталн" is missing the letter "и" at the end. The correct translation should be "експериментални".
Ово је експериментални софтвер.
```

```
        <source>Transaction amount too small</source>
        <translation>Износ трансакције премали.</translation>
    
YES, the translation is problematic because it mistranslates "amount" as "износ" (iznos), which means "sum" or "total", when it should be "сума" (suma) or "износ" in the context of Bitcoin transactions.
Correct translation: Трансакциона сума је премала.
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>Износ трансакције не може бити негативан</translation>
    
YES, The word "Износ" translates to "amount" or "sum". However, it is used in the context of "transaction amounts" in English. In Serbian, the correct translation for "transaction amounts" would be "iznosi transakcija" or "svote transakcija". The current translation "Износ трансакције" translates to "The amount of the transaction" which is singular. Additionally, the verb "не може бити" translates to "cannot be" and is grammatically correct. However, the meaning is shifted from plural "amounts" to singular "amount".

The correct translation should be:
<translation>Iznosi transakcija ne smeju biti negativni</translation>
```

```
        <source>Unable to bind to %s on this computer (bind returned error %s)</source>
        <translation>Није могуће повезати %s на овом рачунару (веза враћа грешку %s)</translation>
    
YES, The translation is inaccurate. It translates "bind" as "connect" which is not the correct meaning in this context. The correct translation for "bind" in this technical context is "привезати" or "везати".
Није могуће привезати %s на овом рачунару (привезивање враћа грешку %s)
```

```
        <source>Unable to create the PID file '%s': %s</source>
        <translation>Стварање PID документа '%s': %s није могуће</translation>
    
YES - The translation is grammatically incorrect and sounds unnatural in Serbian. The word "документа" (document) is also not the best choice for "file" in this context, "фајла" (file) would be more appropriate.

Correct translation: Није могуће креирати PID фајл '%s': %s
```

```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Новчаник треба да буде преписан: поновно покрените %s да завршите</translation>
    
UNK_LANG
```
</details>
