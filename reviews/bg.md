# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>bg</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bbg%5D%20low%20quality)


<!-- cache_translation_check_bg_9878565c8cdb7792d5071d45fcf2e06005cec1001d16366c0a55f2756b6fb298 -->
```
        <source>Repeat new passphrase</source>
        <translation>Повтори парола</translation>
    
ERR
The translation omits "new" ("нова") from "new passphrase", translating only as "Repeat passphrase".

Correct translation:
Повтори нова парола
```

<!-- cache_translation_check_bg_5f262270f93ff22aa90069ab5cd2070e8770ab5aa77e192aca9ce6f85680a96e -->
```
        <source>Runaway exception</source>
        <translation>Изключи бягащите</translation>
    
ERR
The translation is inaccurate. "Изключи бягащите" translates back as "Exclude the running ones" or "Turn off the runaway ones," which is not correct for "Runaway exception." The term refers to an unhandled or cascading exception in software.

Correct translation:
Неуловимо изключение
```

<!-- cache_translation_check_bg_0bbb7fc8f38684cb33cae9b41b134ede8a9688c50dcd7f5b76c79cd80b5779a5 -->
```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>Възникна фатална грешка. Проверете че файла с настройки е редактируем или опирайте да стартирате без настройки.</translation>
    
ERR
There is a mistake in the word "опирайте", which is not correct Bulgarian. The correct imperative form is "опитайте". Also, the translation for "running with -nosettings" should be more accurate, for example, "опитайте да стартирате с -nosettings" to preserve the mention of the command-line option. The article before "файл" should take correct grammatical form: "че файлът с настройки". Also, a comma before the conjunction "или" is appropriate.

Correct translation:
Възникна фатална грешка. Проверете дали файлът с настройки е достъпен за запис, или опитайте да стартирате с -nosettings.
```

<!-- cache_translation_check_bg_8f21514d119e547034a5b62f18481144b822fa1c31b74e9804daaf6330b60d6e -->
```
        <source>Encrypt Wallet…</source>
        <translation>Крипритай уолет..</translation>
    
ERR
The translation contains several errors:
- "Крипритай уолет" is a transliteration, not a proper Bulgarian translation.
- There is a typo: "Крипритай" instead of possibly "Криптирай".
- "уолет" is simply a transliteration of "wallet" instead of using the Bulgarian equivalent.
- The ellipsis is rendered with two dots ("..") instead of the appropriate single ellipsis character or three dots.

Correct translation:
Криптиране на портфейла…
```

<!-- cache_translation_check_bg_98c12d9c717d0d9cb9fb7dd41b5af1a9e761abd550c1bed2a2d2e18086254273 -->
```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>Шифроване на личните ключове,които принадлежат на портфейла Ви.</translation>
    
ERR
There is a formatting issue: there is a missing space after the comma (",които" should be ", които") and "Шифроване" (noun "Encryption") does not match the imperative "Encrypt" in the source sentence. The correct imperative form in Bulgarian should be "Шифровайте". Also, "Вашия портфейл" is a more natural phrase than "портфейла Ви" in this context.

Correct translation:
Шифровайте личните ключове, които принадлежат на вашия портфейл.
```

<!-- cache_translation_check_bg_5c1435a245d3f18292a03bab0ea70d1fc405461c5490f9c624394582203f499f -->
```
        <source>Processing blocks on disk…</source>
        <translation>Обработване на сектори от диска...</translation>
    
ERR
The translation is inaccurate. "Blocks" in the context of Bitcoin refers to "блокове", not "сектори". "Сектори" means "sectors", which is incorrect in this context.

Correct translation:
Обработване на блокове на диска...
```

<!-- cache_translation_check_bg_82e6370f5deba5145600f0d865eef5c5e5ae53c95f51759cd4b12583d9898b19 -->
```
        <source>List mode</source>
        <translation>списък Режим</translation>
    
ERR
The translation is grammatically incorrect. In Bulgarian, adjectives or nouns used as attributes typically precede the noun and agree in capitalization. "List mode" should be translated as "Режим на списък" or more naturally, "Режим на списъка".

Correct translation:
Режим на списък
```

<!-- cache_translation_check_bg_a83b1aa7cb2d9c96e45223e15669472e87fa46113ebf777f52378ce8477f314a -->
```
        <source>Copy change</source>
        <translation>Промяна на копирането</translation>
    
ERR
The translation is incorrect. "Промяна на копирането" means "Change of copying" and does not convey the intended Bitcoin-specific meaning, which is to "copy the change address/amount". 

Correct translation:
Копирай ресто

Explanation: "Ресто" is the standard term for "change" in the context of money, and "Копирай" means "Copy".
```

<!-- cache_translation_check_bg_591cc15809982fefbab8234152a72b78adfa77c4212fbbbec9534980801e5cdd -->
```
        <source>Can vary +/- %1 satoshi(s) per input.</source>
        <translation>Може да варира с +/- %1 байт(а).</translation>
    
ERR
The translation is incorrect. The source refers to "satoshi(s)" (the smallest unit of Bitcoin), but the translation uses "байт(а)" ("byte(s)"), which changes the unit and meaning. Also, the format specifier %1 is correctly preserved.

Correct translation:
Може да варира с +/- %1 сатоши на вход.
```

<!-- cache_translation_check_bg_611ede349b13d882c5cde1ffdae8d1aabcbbb39bb0b3007c75fa09b606e6a277 -->
```
        <source>Create wallet warning</source>
        <translation>Създайте предупредителен портфейл </translation>
    
ERR
The translation is inaccurate. The English means "Warning about wallet creation" (i.e., a warning shown when creating a wallet), but the Bulgarian translation means "Create a warning wallet," which is not the intended meaning.

Correct translation:
Предупреждение при създаване на портфейл
```

<!-- cache_translation_check_bg_86b65678c44ca8136e69c33a5a5561d97a16a239a94d1704680b6839473d0c56 -->
```
        <source>Open wallet failed</source>
        <translation>Отварянето на уолет неупсешно</translation>
    
ERR
The word "уолет" is a transliteration of "wallet" and is not standard in Bulgarian. The correct term is "портфейл". Additionally, "неупсешно" is a misspelling; the correct word is "неуспешно".

Correct translation:
Отварянето на портфейл е неуспешно
```

<!-- cache_translation_check_bg_3c6cd809d8cc0017c56ac5cb89990b0e708d61aa904721038fddefcd2426293d -->
```
        <source>Reverting this setting requires re-downloading the entire blockchain. It is faster to download the full chain first and prune it later. Disables some advanced features.</source>
        <translation>Връщането на тази настройка изисква повторно изтегляне на цялата секторна верига. По-бързо е първо да изтеглите пълната верига и да я подрязвате по-късно. Деактивира някои разширени функции.</translation>
    
ERR
The term "секторна верига" is not a correct translation for "blockchain" in Bulgarian. The standard and widely understood term is "блокчейн" or "веригата от блокове / блокова верига".

Correct translation:
Връщането на тази настройка изисква повторно изтегляне на цялата блокчейн. По-бързо е първо да изтеглите цялата блокчейн и да я подкастрите по-късно. Деактивира някои разширени функции.
```

<!-- cache_translation_check_bg_2821f2b6885a86ec03a1404ee1871b77b2e312befd2f130064710914badf90ee -->
```
        <source>Use a custom data directory:</source>
        <translation>Използване на директория ръчно</translation>
    
ERR  
The translation is inaccurate. The English phrase "Use a custom data directory:" should be rendered as "Използвайте потребителска директория за данни:" in Bulgarian. The given translation omits the concept of "data" and uses an awkward structure.  

Correct translation:  
Използвайте потребителска директория за данни:
```

<!-- cache_translation_check_bg_6223ba027c58068c899cf4b8c0b795a38120daf643419fca1150435b98e0ad2b -->
```
        <source>Esc</source>
        <translation>избягай</translation>
    
ERR  
The translation is problematic. "Esc" refers to the "Escape" key on the keyboard, but "избягай" is the imperative form of the verb "to escape" or "run away" in Bulgarian, not a label for the key itself. The correct translation would be "Esc" (same as in English, as key names are typically not translated in Bulgarian user interfaces).

Correct translation:
Esc
```

<!-- cache_translation_check_bg_ccc3e7f461893d994f8961a9305d1bbf51b19bbad500d98ab7dd1cb53de694e7 -->
```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>%1 в момента синхронизира. Той ще изтегля заглавия и блокове от рояка и ще ги утвърди, докато достигне върха на секторната верига.</translation>
    
ERR
There are several issues with the translation:
1. "рояка" is incorrect in this context; "рояк" means "swarm," but the correct translation for "peers" here is "връстници" or "партньори".
2. "заглавия" is literally "titles," but in blockchain context "headers" should be "хедъри" or "заглавни части".
3. "секторната верига" is a mistranslation of "block chain"; it should be "блокчейн" or "верига от блокове".
4. "Той" (he) is unnecessary and mismatches the subject.

Correct translation:
%1 в момента се синхронизира. Ще изтегля хедъри и блокове от връстници и ще ги валидира, докато достигне върха на блокчейна.
```

<!-- cache_translation_check_bg_1aed6b61187b51c2cf163acebb4bc0ca6640602a8cc4c0cfdaa7bf718b53198d -->
```
        <source>Number of script verification threads</source>
        <translation>Брой на скриптове и нишки за потвърждение</translation>
    
ERR
The translation is inaccurate. The source refers to the "Number of script verification threads" (i.e., the number of threads dedicated to script verification), but the translation splits this into "number of scripts and threads for confirmation," which is not faithful to the original meaning.

Correct translation:
Брой нишки за проверка на скриптове
```

<!-- cache_translation_check_bg_bf2cb71a23038fe1f3855ae67ffeb1e819da8f7fa80f5aa88ef956d014723646 -->
```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Показва дали предоставеният proxy по подразбиране Socks5 се използва за достигане до рояк чрез този тип мрежа.</translation>
    
ERR
The English word "peers" in the context of Bitcoin refers to other network participants or nodes, not "рояк" ("swarm"), which is incorrect and could cause confusion. Also, "proxy" should be translated to "прокси" (the established transliteration), and "SOCKS5" should retain its casing.

Correct translation:
Показва дали предоставеният по подразбиране SOCKS5 прокси се използва за достигане до участници в мрежата чрез този тип мрежа.
```

<!-- cache_translation_check_bg_073a37392fbb40f7b13a3a6ad51f25114ce2f2e17364ada4cfc3604044a9d0db -->
```
        <source>Enable coin control features</source>
        <translation>Позволяване на монетите и техните възможности</translation>
    
ERR  
The translation is inaccurate. The English phrase "Enable coin control features" refers specifically to activating (enabling) the features for controlling ("coin control") which coins/UTXOs are chosen in transactions, not just generally "allowing coins and their possibilities."

Correct translation:
Активиране на функциите за контрол на монетите
```

<!-- cache_translation_check_bg_af8d268b1083102adc333c4c1aa6436778b220f61161adeae1c702d15bb9a9b1 -->
```
        <source>Mined balance that has not yet matured</source>
        <translation>Миниран баланс,който все още не се е развил</translation>
    
ERR
The Bulgarian translation contains an error. The phrase "не се е развил" translates as "has not yet developed," which is incorrect in this Bitcoin context. The correct expression for "has not yet matured" (meaning funds are not yet available for use) should be "не е узрял" or "не е потвърден".

Correct translation:
Миниран баланс, който все още не е узрял
```

<!-- cache_translation_check_bg_c3c98e52785f3a9b74a1cd7d3f75f8e7390676f2b907b8505bd1973ace50fe61 -->
```
        <source>Request payment to %1</source>
        <translation>Изискване на плащане от %1</translation>
    
ERR
The Bulgarian translation incorrectly uses "от" ("from"), suggesting requesting a payment from %1, instead of "to" ("to") as in the original, which is about requesting a payment to the address/account %1.

Correct translation:
Изискване на плащане към %1
```

<!-- cache_translation_check_bg_c2d939c30e86131353e61b4ac599c03b3d34db73ba112da933fe538a4a415d69 -->
```
        <source>automatically selected</source>
        <translation>астоматично избран</translation>
    
ERR
There is a typo in the Bulgarian word "астоматично" — it should be "автоматично".

Correct translation:
автоматично избран
```

<!-- cache_translation_check_bg_a83b1aa7cb2d9c96e45223e15669472e87fa46113ebf777f52378ce8477f314a -->
```
        <source>Copy change</source>
        <translation>Промяна на копирането</translation>
    
ERR
The translation is incorrect. "Промяна на копирането" means "Change of copying" and does not convey the intended Bitcoin-specific meaning, which is to "copy the change address/amount". 

Correct translation:
Копирай ресто

Explanation: "Ресто" is the standard term for "change" in the context of money, and "Копирай" means "Copy".
```

<!-- cache_translation_check_bg_86e13b8e754090ac49b7fcac530bd230aa9ec184a2e74368e4d3770d54541b4c -->
```
        <source>Confirm send coins</source>
        <translation>Потвърждаване</translation>
    
ERR
The translation is incomplete. The source means "Confirm send coins", implying an action related to sending coins, while the translation simply says "Потвърждаване" ("Confirmation"), which omits the context (sending coins).

Correct translation:
Потвърдете изпращането на монетите
```

<!-- cache_translation_check_bg_69840447143d9caf25b4f881cad6634a6b07de71eb1e1dd248945b1b29863e6d -->
```
        <source>The total exceeds your balance when the %1 transaction fee is included.</source>
        <translation>Сумата при добавяне на данък добавена стойност по %1 транзакцията надвишава сумата по вашата сметка.</translation>
    
ERR
The translation incorrectly interprets "transaction fee" as "данък добавена стойност" (value-added tax), which is not correct in the context of Bitcoin; it should be "такса за транзакция". Additionally, "the total exceeds your balance" is not translated precisely, and there is a redundancy with the repeated "сума".

Correct translation:
Сумата надвишава наличността ви, когато е включена таксата за транзакция от %1.
```

<!-- cache_translation_check_bg_abe88dacbaaa0e2546cf9e7e459e4d027795533b3844909f59577430d5f22067 -->
```
        <source>Paste address from clipboard</source>
        <translation>Вмъкни от клипборда</translation>
    
ERR
The translation omits the word "address" ("адрес") from the source, which can be confusing in the context where multiple items could be pasted. It should specify that an address is being pasted.

Correct translation:
Постави адрес от клипборда
```

<!-- cache_translation_check_bg_abe88dacbaaa0e2546cf9e7e459e4d027795533b3844909f59577430d5f22067 -->
```
        <source>Paste address from clipboard</source>
        <translation>Вмъкни от клипборда</translation>
    
ERR
The translation omits the word "address" ("адрес") from the source, which can be confusing in the context where multiple items could be pasted. It should specify that an address is being pasted.

Correct translation:
Постави адрес от клипборда
```

<!-- cache_translation_check_bg_7ee2d3b01a7476743b75765f4e65f21e52d4d92c331caef231c540f476f29535 -->
```
        <source>Sign the message to prove you own this Bitcoin address</source>
        <translation>Подпишете съобщение като доказателство, че притежавате определен адрес</translation>
    
ERR
The translation omits that this is a Bitcoin address and changes "the message" to "a message", which reduces specificity and clarity. The original specifies "this Bitcoin address", which is important in context.

Correct translation:
Подпишете съобщението, за да докажете, че притежавате този Bitcoin адрес
```

<!-- cache_translation_check_bg_45667c8ecf2ee1fb429c5dfe140cd5e9c1474e67696e56178b981ad390ee29f3 -->
```
        <source>The signature did not match the message digest.</source>
        <translation>Подписът не отговаря на комбинацията от съобщение и адрес.</translation>
    
ERR
The translation is inaccurate. The source says "The signature did not match the message digest," meaning the signature does not correspond to the digest (hash) of the message. The translation says, "Подписът не отговаря на комбинацията от съобщение и адрес," which means "The signature does not match the combination of message and address." "Комбинация от съобщение и адрес" is incorrect here. It should refer to the "message digest" (хеш на съобщението / дайджест на съобщението).

Correct translation:
Подписът не съвпада с дайджеста (хеша) на съобщението.
```

<!-- cache_translation_check_bg_f447890d42a0747ed9afcfbf78b3a7c70ba65e8e740ac2296c5d2fccb9c4d3ce -->
```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>включена в %1 блока</translation>
    
ERR
The translation does not accurately convey the source meaning. The source text specifies the number of confirmations, while the translation says "included in %1 blocks," which is not precise. Also, the word "блока" is singular, while it should be plural if the number is more than one.

Correct translation:
%1 потвърждения
```

<!-- cache_translation_check_bg_f970b959487e6eb4bb4015511df2ce07161b7b92b6c60fceed81576dfb422871 -->
```
        <source>Total credit</source>
        <translation>Общ дълг</translation>
    
ERR
The translation is incorrect. "Общ дълг" means "Total debt", not "Total credit". The correct translation for "Total credit" is "Общ кредит".

Correct translation:
Общ кредит
```

<!-- cache_translation_check_bg_6736ed11c8e393e1f0d67e5b0ca2360504ffc7ee46276255c5f3faf47810655e -->
```
        <source>Transaction ID</source>
        <translation>ID</translation>
    
ERR
The translation is incomplete. "ID" alone omits the meaning of "Transaction". The correct Bulgarian translation should be:
Идентификатор на транзакцията
```

<!-- cache_translation_check_bg_2296174707c891a58cca1a2ec1987844ce4d4f45c77af2d27ee08524bb507462 -->
```
        <source>Exporting Successful</source>
        <translation>Изнасянето е успешна</translation>
    
ERR
There is a grammatical gender mismatch. The noun "изнасяне" (exporting) is neuter, so the adjective must agree in gender (успешно). The current translation uses the feminine form "успешна".

Correct translation:
Изнасянето е успешно
```

<!-- cache_translation_check_bg_1c3d3569725d54893226ee8948ff99b85e5d373d175bddbe98b67efea2fd81c4 -->
```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>Портфейлът няма да плаша по-малко от миналата такса за препредаване.</translation>
    
ERR
There is a mistranslation: "миналата такса за препредаване" means "the last relay fee", but the correct meaning is "the minimum relay fee". Also, "плаша" should be "плаща" ("will not pay"). 

Correct translation:
Портфейлът ще избягва да плаща по-малко от минималната такса за препредаване.
```

<!-- cache_translation_check_bg_4199d6ffad544ab5c3d6a753872a60f856f668b54287a94a5f6153feb7bfc3c7 -->
```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>Коментар потребителски агент (%s) съдържа не безопасни знаци. </translation>
    
ERR
There is a minor grammatical error in the Bulgarian translation: "не безопасни" should be "небезопасни" (written as one word). Additionally, there is a stray space at the end.

Correct translation:
Коментарът на потребителския агент (%s) съдържа небезопасни знаци.
```
</details>

Number of issues: 34.
