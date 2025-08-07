# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sr</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsr%5D%20low%20quality)


```
        <source>Choose the address to receive coins with</source>
        <translation>Одабери адресу за примање</translation>
    
YES
The translation omits the word "coins" ("новци" or "новчићи") present in the source, which makes the sentence less clear in the Bitcoin context. The phrase "за примање" is incomplete in conveying the full meaning "to receive coins with". Additionally, the aspect "to receive coins with" is somewhat more idiomatically rendered in Serbian as "адресу на коју ћете примити новчиће".

Correct translation:
Одаберите адресу на коју ћете примити новчиће
```

```
        <source>Copy Label</source>
        <translation>Копирај  Обележи</translation>
    
YES
There is a double space between "Копирај" and "Обележи". Furthermore, "Copy Label" should be translated as "Копирај ознаку" (where "ознака" is the appropriate translation for "label" in this context), not "Обележи" ("Обележи" means "Mark" or "Highlight").

Correct translation:
Копирај ознаку
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Унеси нову приступну фразу за новчаник&lt;br/&gt;Молимо користи приступну фразу од десет или више насумичних карактера&lt;b&gt;,или&lt;b&gt;осам или више речи&lt;/b&gt;.</translation>
    
YES
There are several issues with the Serbian translation:
- "приступну фразу за новчаник" should be "приступну фразу за новчаник." (missing period at the end of the first sentence)
- HTML tags are misplaced: "&lt;b&gt;" is not properly closed around "десет или више насумичних карактера" (it is closing after "или").
- Extra spacing issues after punctuation (missing space after a comma).
- The sentence "или осам или више речи" is missing proper context and HTML formatting.

Correct translation:
Унесите нову приступну фразу за новчаник.&lt;br/&gt;Молимо вас да користите приступну фразу од &lt;b&gt;десет или више насумичних карактера&lt;/b&gt; или &lt;b&gt;осам или више речи&lt;/b&gt;.
```

```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Упамти, шифрирање новчаника не може у потуности заштити твоје биткоине од крађе од стране малвера инфицира твој рачунар.</translation>
    
YES
There are several issues:
1. "у потуности" should be "у потпуности" (spelling error).
2. "малвера инфицира твој рачунар" is ungrammatical; it should be "малвер који инфицира твој рачунар" or simply "малвера који је инфицирао твој рачунар".
3. The formal tone is inconsistent; the source is somewhat neutral, but the translation uses informal "твоје". If the UI uses "ви", use "ваш".

Correct translation:
Упамтите да шифрирање новчаника не може у потпуности заштитити ваше биткоине од крађе од стране малвера који инфицира ваш рачунар.
```

```
        <source>Warning: The Caps Lock key is on!</source>
        <translation>Упозорање Caps Lock дугме укључено!</translation>
    
YES
The translation is mostly correct, but it is missing the verb "је" ("is") for full clarity, which matches the original phrase structure. Also, the phrase should ideally be: "Упозорење: Caps Lock дугме је укључено!"

Correct translation:
Упозорење: Caps Lock дугме је укључено!
```

```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>Унеси Биткоин адресу, (нпр %1)</translation>
    
YES
There is an unnecessary comma after "адресу" and missing period at the end. In Serbian, it is also more idiomatic to use "на пример" or "например" rather than "нпр", which is less formal. Additionally, the abbreviation should be followed by a period. The correct translation should be:

Унеси Биткоин адресу (нпр. %1)
```

```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>Блокирана предаја</translation>
    
YES
The translation "Блокирана предаја" means "Blocked relay" or "Blocked transmission" in Serbian, which is incorrect. The correct translation of "Block Relay" (as in a peer connection type relaying block data) should be "Релеј блокова" or "Пренос блокова".

Correct translation:
Релеј блокова
```

```
        <source>Create a new wallet</source>
        <translation>Направи нови ночаник</translation>
    
YES
There is a spelling error in the translation: "ночаник" should be "новчаник". Also, "направи" is understandable but "креирај" or "направите" (formal) is more commonly used in software contexts. 

Correct translation:
Креирај нови новчаник
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Потписуј поруку са своје Биткоин адресе као доказ да си њихов власник</translation>
    
YES
The translation has a few issues:
1. The original text is plural: "addresses" and "messages", but the translation is singular ("поруку", "адресе").
2. The pronoun "њихов" (their) refers to addresses, which should agree in number.
3. The instruction voice ("Sign messages") in English is imperative, but the translation uses the informal singular "Потписуј", which can imply habitual action, rather than a direct imperative ("Потпиши").
4. The translation says "са своје Биткоин адресе" ("from your Bitcoin address") instead of "with your Bitcoin addresses".
5. The translation switches between singular and plural inconsistently.

Correct translation:
Потпишите поруке својим Биткоин адресама да докажете да сте њихов власник
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>Учитај ”PSBT” из привремене меморије</translation>
    
YES
The translation uses quotation marks around "PSBT" instead of leaving it unquoted, which isn't necessary or idiomatic in Serbian. Also, "привремена меморија" is technically correct for "clipboard", but "клипборд" is more recognizable in the context of software UI, or "међу меморију" is sometimes used.
The ellipsis in the source is a single Unicode character (…); this is missing in the translation.

Correct translation:
Учитај PSBT из клипборда…
```

```
        <source>Node window</source>
        <translation>Ноде прозор</translation>
    
YES
"Ноде прозор" transliterates the English word "Node" instead of translating it into Serbian. The correct translation for "Node" in Serbian, in the context of Bitcoin, is "Чвор".

Correct translation:
Прозор чвора
```

```
        <source>Mask the values in the Overview tab</source>
        <translation>Филтрирај вредности у картици за преглед</translation>
    
YES  
The translation is inaccurate. "Mask the values" means to hide or obscure them, not to filter. The Serbian translation says "Filter the values in the overview tab," which changes the meaning.

Correct translation:  
Маскирај вредности на картици прегледа
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Прикажи картицу са ”Клијентима”</translation>
    
YES
The translation uses "Клијентима" for "Peers", which is inaccurate in the Bitcoin context. "Peers" should be "чворови" (nodes/peers), not "клијенти" (clients).

Correct translation:
Прикажи картицу са „чворовима“
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Новчаник јс &lt;b&gt;шифриран&lt;/b&gt; и тренутно &lt;b&gt;откључан&lt;/b&gt;</translation>
    
YES
There is a typo in the translation: "јс" should be "је" ("is" in Serbian). The rest of the translation is correct, including the formatting and spacing.

Correct translation:
Новчаник је &lt;b&gt;шифриран&lt;/b&gt; и тренутно &lt;b&gt;откључан&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Новчаник јс &lt;b&gt;шифрован&lt;/b&gt; и тренутно &lt;b&gt;закључан&lt;/b&gt;</translation>
    
YES
There is a typo in the translation: "јс" should be "је".

Correct translation:
Новчаник је &lt;b&gt;шифрован&lt;/b&gt; и тренутно &lt;b&gt;закључан&lt;/b&gt;
```

```
        <source>Create wallet warning</source>
        <translation>Направи упозорење за новчаник</translation>
    
YES
The translation is inaccurate. The original phrase "Create wallet warning" refers to a warning about wallet creation, not the action of making a warning for a wallet. The translation suggests creating (making) a warning, which changes the meaning.

Correct translation:
Упозорење при креирању новчаника
```

```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>Da li si siuran da želiš da preneseš novčanik &lt;i&gt;%1&lt;/i&gt;? </translation>
    
YES
There are minor issues with spelling and formality in the Serbian translation. "Siuran" is a typo; the correct word is "siguran". Also, the style is somewhat informal ("da želiš da"), which can be replaced with a more standard form. Additionally, there is an unnecessary trailing whitespace at the end.

Correct translation:
Da li ste sigurni da želite da migrirate novčanik &lt;i&gt;%1&lt;/i&gt;?
```

```
        <source>Migration Successful</source>
        <translation>Prenošenje novčanika je uspešno</translation>
    
YES
The translation is inaccurate. The source text "Migration Successful" is translated as "Prenošenje novčanika je uspešno", which means "Wallet transfer is successful". The word "novčanika" (wallet) is not present in the source and is an addition. Additionally, the translation is more verbose than necessary.

Correct translation:
Migracija je uspešna
```

```
        <source>Opening Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the open wallet progress window which indicates to the user which wallet is currently being opened.</extracomment>
        <translation>Отвањаре новчаника &lt;b&gt;%1&lt;/b&gt;</translation>
    
YES
There is a spelling error in the Serbian word "Отвањаре". The correct word is "Отварање". Additionally, the ellipsis (…) from the source is missing in the translation. The rest, including the %1 specifier, is correct.

Correct translation:
Отварање новчаника &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Онемогући приватни кључ за овај новчаник. Новчаници са онемогућеним приватним кључем неће  имати приватни кључ и не могу имати HD семе или увезени приватни кључ. Ова опција идеална је за новчанике који су искључиво за посматрање.</translation>
    
YES
There are inconsistencies between the plural and singular forms used for "private keys" and spacing errors (double space after "неће"). "Приватни кључ" (singular) is used instead of "приватни кључеви" (plural) which can mislead the meaning. Also, the original English references "wallets" (plural), and the translation sometimes shifts between singular and plural inconsistently. 

Correct translation:
Онемогући приватне кључеве за овај новчаник. Новчаници са онемогућеним приватним кључевима неће имати приватне кључеве и не могу имати HD семе или увезене приватне кључеве. Ово је идеално за новчанике који служе само за посматрање.
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Најмање %1 GB подататака биће складиштен у овај директорјиум који ће временом порасти.</translation>
    
YES
There are several issues with the Serbian translation:
1. "подататака" is a typo; it should be "података".
2. "директорјиум" is also a typo/misspelling; it should be "директоријум".
3. The structure "биће складиштен у овај директорјиум" is awkward; more appropriate would be "ће бити сачувано у овом директоријуму".
4. The English source uses "will be stored", so "ће бити сачувано" is better than "биће складиштен".
5. The plural form of "ГБ" should be "GB" (Latin letters, as is often kept in Serbian technical usage), but that is minor and acceptable.

Correct translation:
Најмање %1 GB података ће бити сачувано у овом директоријуму и количина ће с временом расти.
```

```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Најмање %1 GB подататака биће складиштен у овај директорјиум.</translation>
    
YES
The translation contains several errors:
1. "Најмање" means "at least", not "approximately". The correct word for "approximately" in Serbian is "Приближно" or "Око".
2. "подататака" is a typo, the correct word is "података".
3. "биће складиштен" should be "биће сачувано" or "ће бити сачувано" for "will be stored".
4. "у овај директорјиум" should be "у овај директоријум".

Correct translation:
Приближно %1 GB података ће бити сачувано у овом директоријуму.
```

```
        <source>%1 will download and store a copy of the Bitcoin block chain.</source>
        <translation>%1 биће преузеће и складиштити копију Биткоин ланца блокова.</translation>
    
YES
The translation has grammatical issues; specifically, "биће преузеће и складиштити" is incorrect. "Преузеће" and "биће" are redundant, and the verb "складиштити" should be coordinated properly.

Correct translation:
%1 ће преузети и сачувати копију Биткоин блокчејна.
```

```
        <source>Error: Specified data directory "%1" cannot be created.</source>
        <translation>Грешка: Одабрана датотека  "%1" не може бити креирана.</translation>
    
YES
The translation uses "датотека" which means "file" instead of "директоријум" which means "directory". Also, the correct phrase for "specified" here should be "наведени", not "одабрана". There is also an extra space after the word "датотека".

Correct translation:
Грешка: Намењени директоријум „%1“ не може бити креиран.
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Налепите адресу из базе за копирање</translation>
    
YES
The translation "Налепите адресу из базе за копирање" is inaccurate. The term "база за копирање" is not a correct term for "clipboard" in Serbian; the correct word is "клипборд" or "привремена меморија." Additionally, "Налепите" could be replaced with "Налепи" to match common UI imperative tone.

Correct translation:
Налепи адресу из клипборда
```

```
        <source>Number of script verification threads</source>
        <translation>Број скрипти и CPU за верификацију</translation>
    
YES
The translation is inaccurate. The English source says "Number of script verification threads," which refers specifically to the number of processing threads used for script verification. The provided Serbian translation, "Број скрипти и CPU за верификацију," translates back as "Number of scripts and CPU for verification," which introduces erroneous and unnecessary elements ("CPU" and "scripts" instead of "threads").

Correct translation:
Број нити за верификацију скрипти
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Приказује се ако је испоручени уобичајени SOCKS5 проxy коришћен ради проналажења клијената преко овог типа мреже. </translation>
    
YES
There are a few problems with the translation:
1. The original English says "Shows if the supplied...", which is impersonal, but the Serbian uses a more personal/active voice ("Приказује се ако је...").
2. Incorrect rendering of "proxy" as "проxy" (the "x" is not in Cyrillic).
3. "клијената" translates to "clients", but the appropriate term for "peers" in the context of Bitcoin is "чворова" (nodes/peers).
4. Minor format issue: stray space at the end of the sentence.

Correct translation:
Показује да ли се испоручени подразумевани SOCKS5 прокси користи за повезивање са чворовима преко ове врсте мреже.
```

```
        <source>Prune block storage to</source>
        <translation>Сакрати block складиштење на</translation>
    
YES
The translation partially translates the text: "block storage" is left in English, while it should be in Serbian. Additionally, the word order is odd, and the infinitive "Prune" is usually rendered as an imperative or descriptive action.

Correct translation:
Скратити складиштење блокова на

Or, to match familiar UI phrasing:

Скратити складиштење блокова на
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Враћање ове опције захтева да поновно преузимање целокупонг блокчејна.</translation>
    
YES
There is a grammatical error in the translation, specifically in "понвно преузимање целокупонг блокчејна" - "целокупонг" is incorrect; the correct form is "целокупног", and sentence structure can be improved for clarity.

Correct translation:
Враћање ове опције захтева поновно преузимање целокупног блокчејна.
```

```
        <source>Connect to the Bitcoin network through a SOCKS5 proxy.</source>
        <translation>Конектуј се на Биткоин мрежу кроз SOCKS5 проксијем.</translation>
    
YES
The translation uses the informal imperative "Конектуј се", but a more standard and formal Serbian phrasing would use "Повежите се". Also, "кроз SOCKS5 проксијем" is incorrect; it should be "преко SOCKS5 проксија". 

Correct translation:
Повежите се на Биткоин мрежу преко SOCKS5 проксија.
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>минимизирај у доњу линију, уместо у програмску траку</translation>
    
YES
The translation is inaccurate. In Serbian, "system tray" is commonly referred to as "системску траку" or "област обавештења", while "taskbar" is "програмска трака" or "дно екрана". The phrase "доња линија" is not standard for "tray".

Correct translation:
Минимизуј у системску траку уместо у програмску траку
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>Салдорударења у адресама које су у моду само гледање, који још увек није доспео</translation>
    
YES
There is a minor issue with the translation: "Салдорударења" is a concatenation and should be split. The correct term for "mined balance" would be "ископани салдо" or "салдо од рударења". The rest of the translation is generally accurate, but it can be made smoother.

Correct translation:
Ископани салдо на адресама у режиму само за гледање који још увек није доспео
```

```
        <source>Signed %1 inputs, but more signatures are still required.</source>
        <translation>Потписано %1 поље, али је потребно још потписа.</translation>
    
YES
The translation is inaccurate. The word "inputs" in the Bitcoin context rarely translates as "поље" ("field") in Serbian; the proper term is "улаза" ("inputs"). Additionally, the plural form should be used. The rest of the sentence is acceptable.

Correct translation:
Потписано је %1 улаза, али је потребно још потписа.
```

```
        <source>Transaction has %1 unsigned inputs.</source>
        <translation>Трансакција има %1 непотписана поља.</translation>
    
YES
The translation is inaccurate. The term "inputs" in Bitcoin context should be "улази" (inputs), not "поља" (fields). "Поља" is misleading in this context. Also, the format specifier %1 is correctly preserved.

Correct translation:
Трансакција има %1 непотписаних улаза.
```

```
        <source>Save Image…</source>
        <translation>Сачували слику…</translation>
    
YES
The translation is inaccurate. "Сачували слику…" means "Saved the image…" (past tense), rather than the imperative form "Save Image…". The correct translation should be in the imperative mood.

Correct translation:
Сачувај слику…
```

```
        <source>Resulting URI too long, try to reduce the text for label / message.</source>
        <translation>Дати резултат URI  предуг, покушај да сманиш текст за ознаку / поруку.</translation>
    
YES
The Serbian translation is problematic for multiple reasons:
- "Дати резултат URI предуг" is not grammatically correct or idiomatic. It should convey that the resulting URI is too long.
- The word "URI" is left in Latin script, although it's common to transliterate/leave as URI, this is acceptable but the structure is still awkward.
- "Дати резултат" is not a natural way to say "resulting".
- There is a double space after "URI", which is a whitespace formatting issue.
- "предуг" is a typo; the correct word is "предугачак" or "предугачак".

Correct translation:
Резултујући URI је предугачак, покушај да скратиш текст за ознаку/поруку.
```

```
        <source>Memory Pool</source>
        <translation>Удружена меморија</translation>
    
YES
The translation "Удружена меморија" is incorrect. "Memory Pool" in the context of Bitcoin refers to "мемпул" or "меморијски пул", not "удружена меморија" ("pooled/joined memory"), which does not convey the intended technical meaning.

Correct translation:
Мемпул
```

```
        <source>Select a peer to view detailed information.</source>
        <translation>Одабери колегу да би видели детаљне информације</translation>
    
YES
The translation is problematic: "колега" is not the correct translation for "peer" in the context of Bitcoin. "Пир" (the transliterated term widely used in this context) or "чвор" ("node") would be more appropriate. Also, "да би видели" is grammatically incorrect; it should match the (you) imperative, so "да видите" is correct.

Correct translation:
Одаберите пира да видите детаљне информације.
```

```
        <source>Node window</source>
        <translation>Ноде прозор</translation>
    
YES
"Ноде прозор" transliterates the English word "Node" instead of translating it into Serbian. The correct translation for "Node" in Serbian, in the context of Bitcoin, is "Чвор".

Correct translation:
Прозор чвора
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

```
        <source>Save Image…</source>
        <translation>Сачували слику…</translation>
    
YES
The translation is inaccurate. "Сачували слику…" means "Saved the image…" (past tense), rather than the imperative form "Save Image…". The correct translation should be in the imperative mood.

Correct translation:
Сачувај слику…
```

```
        <source>Inputs…</source>
        <translation>Поља...</translation>
    
YES
The English word "Inputs" in the context of Bitcoin refers to "улази" (inputs to a transaction), not "поља" (which means "fields"). The translation is incorrect.

Correct translation:
Улази...
```

```
        <source>Set external signer script path in Options -&gt; Wallet</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Подси екстерну скрипту за потписивање у : Options -&gt; Wallet</translation>
    
YES
The Serbian translation is problematic. The phrase "Подси екстерну скрипту за потписивање у : Options -> Wallet" contains several issues:
1. "Подси" is not a correct Serbian word for "Set". It should be "Поставите".
2. The order and structure are confusing, and there is an unnecessary space before the colon.
3. Options and Wallet are untranslated, but could be left as-is if keeping UI terms in English is the convention.

Correct translation:
Поставите путању до скрипте за екстерно потписивање у Options -> Wallet
```

```
        <source>Paste address from clipboard</source>
        <translation>Налепите адресу из базе за копирање</translation>
    
YES
The translation of "clipboard" as "база за копирање" is incorrect and unidiomatic in Serbian. The correct term for "clipboard" is "клипборд" or "привремена меморија". Furthermore, the verb "налепите" is properly used but may be more common as "налепи" in UI commands for consistency with imperative forms. Also, there is no whitespace issue or format specifier.

Correct translation:
Налепи адресу из клипборда
```

```
        <source>A message that was attached to the bitcoin: URI which will be stored with the transaction for your reference. Note: This message will not be sent over the Bitcoin network.</source>
        <translation>Порука која је приложена биткоину: URI која ће бити сачувана уз трансакцију ради референце. Напомена: Ова порука се шаље преко Биткоин мреже.</translation>
    
YES
The translation is problematic. The phrase "Ова порука се шаље преко Биткоин мреже." translates as "This message is sent over the Bitcoin network," which is the opposite of the source text meaning ("This message will not be sent over the Bitcoin network.").

Correct translation:
Порука која је приложена bitcoin: URI-ју и која ће бити сачувана уз трансакцију ради ваше референце. Напомена: Ова порука неће бити послата преко Биткоин мреже.
```

```
        <source>Paste address from clipboard</source>
        <translation>Налепите адресу из базе за копирање</translation>
    
YES
The translation of "clipboard" as "база за копирање" is incorrect and unidiomatic in Serbian. The correct term for "clipboard" is "клипборд" or "привремена меморија". Furthermore, the verb "налепите" is properly used but may be more common as "налепи" in UI commands for consistency with imperative forms. Also, there is no whitespace issue or format specifier.

Correct translation:
Налепи адресу из клипборда
```

```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>%1 порврде</translation>
    
YES
There is a typo in the translation: "порврде" should be "потврде". The word "порврде" is not a valid Serbian word.

Correct translation:
%1 потврде
```

```
        <source>Credit</source>
        <translation>Заслуге</translation>
    
YES
The Serbian translation "Заслуге" means "merits" or "accomplishments" rather than "credit" in the financial sense, which in this context is likely referring to a credited amount or incoming funds.

Correct translation:
Кредит
```

```
        <source>Generated coins must mature %1 blocks before they can be spent. When you generated this block, it was broadcast to the network to be added to the block chain. If it fails to get into the chain, its state will change to "not accepted" and it won't be spendable. This may occasionally happen if another node generates a block within a few seconds of yours.</source>
        <translation>Генерисани новчићи морају доспети %1 блокова пре него што могу бити потрошени. Када генеришете овај блок, он се емитује у мрежу, да би био придодат на ланац блокова. Укупно не успе да се придода на ланац, његово стање се мења у "није прихваћен" и неће га бити могуће потрошити. Ово се може повремено десити уколико други чвор генерише блок у периоду од неколико секунди од вашег.</translation>
    
YES
There are a few errors:
1. "Укупно не успе да се придода на ланац" is incorrect and awkward; "уколико не успе да се придода на ланац" or "ако не успе да се придода на ланац" is correct.
2. The sentence flow is somewhat unnatural, and "он се емитује у мрежу, да би био придодат на ланац блокова" would be better as "он је емитован у мрежу да би био додат у ланац блокова".
3. "доспети %1 блокова" is unnatural; it should be "сазрети %1 блокова" or more commonly "сазрети током %1 блокова".
4. "периоду од неколико секунди од вашег" should be "у року од неколико секунди након вашег".

Correct translation:
Генерисани новчићи морају сазрети током %1 блокова пре него што могу бити потрошени. Када генеришете овај блок, он је емитован у мрежу да би био додат у ланац блокова. Ако не успе да уђе у ланац, његово стање ће бити промењено у „није прихваћен“ и неће га бити могуће потрошити. Ово се може повремено десити ако неки други чвор генерише блок у року од неколико секунди након вашег.
```

```
        <source>Transaction status. Hover over this field to show number of confirmations.</source>
        <translation>Статус трансакције. Пређи мишем преко поља за приказ броја трансакција.</translation>
    
YES  
The translation is inaccurate. The phrase "пређи мишем преко поља за приказ броја трансакција" translates as "hover over the field to display the number of transactions." However, the original English says "number of confirmations," not "number of transactions."  
Correct translation:  
Статус трансакције. Пређите мишем преко овог поља да бисте видели број потврда.
```

```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Без обзира да ли је у ову трансакције укључена или није - адреса само за гледање.</translation>
    
YES
The Serbian translation is not accurate and sounds unnatural. There is also a grammatical error: "трансакције" should be "трансакцију" (accusative case). The construction "или није - адреса само за гледање" is not idiomatic and adds unnecessary complexity.

Correct translation:
Да ли је у ову трансакцију укључена адреса само за посматрање.

Alternative:
Да ли је у ову трансакцију укључена watch-only адреса.
```

```
        <source>Copy transaction ID</source>
        <translation>Копирај трансакцију ID</translation>
    
YES
There is a minor issue in the translation: the word order is incorrect. "ID" in Serbian should usually come before the noun as "ID трансакције" or the phrase should be "Копирај ID трансакције" to accurately mean "Copy transaction ID". Additionally, "ID" can be transliterated or left, but it is usually left as "ID". There is also an unnecessary mixing of Latin and Cyrillic scripts (since "ID" is in Latin, and the rest is in Cyrillic, which is acceptable in Serbian IT context but not ideal stylistically).

Correct translation:
Копирај ID трансакције
```

```
        <source>Edit address label</source>
        <translation>Promeni adresu etikete</translation>
    
YES
The translation is incorrect. The phrase "Edit address label" means to edit the label (name or description) assigned to an address, not to change the address of a label. The correct Serbian translation should be "Izmeni oznaku adrese" or "Uredi oznaku adrese".

Correct translation:
Izmeni oznaku adrese
```

```
        <source>Create a new wallet</source>
        <translation>Направи нови ночаник</translation>
    
YES
There is a spelling error in the translation: "ночаник" should be "новчаник". Also, "направи" is understandable but "креирај" or "направите" (formal) is more commonly used in software contexts. 

Correct translation:
Креирај нови новчаник
```

```
        <source>Confirm fee bump</source>
        <translation>Потврдите ударну провизију</translation>
    
YES
The translation "Потврдите ударну провизију" is problematic. The phrase "ударну провизију" literally means "impact fee" or "hit fee", which is not an accurate or idiomatic rendering of "fee bump" in the Bitcoin context. In Bitcoin, "fee bump" refers to increasing the transaction fee. The correct translation in this context should convey the idea of confirming an increase in the transaction fee, typically accomplished with terms like "повећање накнаде".

Correct translation:
Потврдите повећање накнаде
```

```
        <source>The transaction amount is too small to pay the fee</source>
        <translation>Износ трансакције је сувише мали да се плати трансакција</translation>
    
YES
The translation is problematic: the phrase "да се плати трансакција" means "to pay the transaction," which is incorrect. It should refer to paying the fee, not the transaction itself. Also, "суviše мали" (too small) is fine, but "трансакција" at the end should be "такса" or "надокнада" (fee).

Correct translation:
Износ трансакције је сувише мали да плати таксу.
```

```
        <source>This is experimental software.</source>
        <translation>Ово је експерименталн софтвер.</translation>
    
YES
There is a spelling error in the Serbian translation. The word "експерименталн" is missing the last letter "и" to correctly spell "експериментални".

Correct translation:
Ово је експериментални софтвер.
```
</details>

Number of issues: 57.
