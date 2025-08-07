# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ru</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bru%5D%20low%20quality)


```
        <source>Create a new address</source>
        <translation>Создать новые адрес</translation>
    
YES
The translation is grammatically incorrect; "адрес" is singular and masculine, so the correct adjective form is "новый," not "новые" (which is plural feminine/neutral). It should be singular to match the English source.

Correct translation:
Создать новый адрес
```

```
        <source>Delete the currently selected address from the list</source>
        <translation>Удалить выбранные адреса из списка</translation>
    
YES
The translation changes the number from singular ("the currently selected address") to plural ("выбранные адреса" = "selected addresses"), which is inaccurate. The source refers to a single address, so the translation should maintain the singular form.

Correct translation:
Удалить выбранный адрес из списка
</reply>
```

```
        <source>Choose the address to send coins to</source>
        <translation>Выберите адреса, для отправки на них монет</translation>
    
YES
The translation is inaccurate in two ways:
1. "адреса" is plural, but the English source is singular ("the address").
2. There is an unnecessary comma after "адреса" and the preposition usage is awkward.

Correct translation:
Выберите адрес для отправки монет
```

```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>Це ваші біткоїн-адреси для надсилання платежів. Завжди перевіряйте суму та адресу отримання перед тим, як надсилати монети.</translation>
    
YES
The translation is in Ukrainian, not Russian. Additionally, the correct Russian translation should use Russian vocabulary and grammar.

Correct translation:
Это ваши биткойн-адреса для отправки платежей. Всегда проверяйте сумму и адрес получателя перед отправкой монет.
```

```
        <source>Passphrase Dialog</source>
        <translation>Пароль</translation>
    
YES
The translation is inaccurate. "Passphrase Dialog" refers to a dialog window for entering or managing a passphrase, not just a "password". The current translation loses this UI context.

Correct translation:
Диалоговая форма для ввода парольной фразы
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Пароль, введенный при шифровании кошелька, некорректен.</translation>
    
YES
The translation is inaccurate. The source refers to decryption ("wallet decryption"), but the translation says "при шифровании" (at encryption), which changes the meaning.

Correct translation:
Пароль, введённый для расшифровки кошелька, неверен.
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Текущий пароль, введенный для расшифрования кошелька, не подходит. Он содержит нулевой байт. Если пароль была задан в программе версии ниже 25.0, пожалуйста, попробуйте ввести только символы до первого нулевого байта, не включая его.</translation>
    
YES
There are a few issues:
1. "Текущий пароль" more literally means "current password", whereas "The old passphrase entered" is better translated as "Введённая старая парольная фраза" or "Старая введённая парольная фраза".
2. "Пароль была задан" — "пароль" is masculine and should be "был задан".
3. "пароль" is used instead of "парольная фраза", which is more accurate for "passphrase".
4. The phrasing "не подходит" ("does not fit") is less precise than "неверна" ("incorrect").

Correct translation:
Введённая старая парольная фраза для расшифровки кошелька неверна. Она содержит нулевой символ (то есть, байт со значением ноль). Если парольная фраза была установлена в версии программы до 25.0, пожалуйста, попробуйте ещё раз, используя только символы до — но не включая — первого нулевого символа.
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Подписать сообщения своими Биткоин кошельками, что-бы доказать, что вы ими владеете</translation>
    
YES
There are minor issues: the correct verb is "адресами" (addresses), not "кошельками" (wallets), and "чтобы" should not have a hyphen. Also, the comma after "сообщения" is awkward and unnecessary; better sentence structure would be more natural.

Correct translation:
Подписывайте сообщения своими Биткоин-адресами, чтобы доказать, что они принадлежат вам
```

```
        <source>(un)select all</source>
        <translation>Выбрать все</translation>
    
YES
The translation only means "Select all". It misses the "(un)" part, which should indicate both "select all" and "deselect all". 

Correct translation:
(Выбрать/снять выбор) все
```

```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>Попытка потратить средства, использованные в транзакциях, которые ещё не синхронизированы, будет отклонена сетью.</translation>
    
YES
The translation is problematic because it alters the meaning of the original sentence. The English source specifically refers to "bitcoins that are affected by not-yet-displayed transactions," meaning bitcoins tied up in transactions that have not yet appeared/been displayed in the user's wallet. The Russian translation refers to "funds used in transactions that are not yet synchronized," which changes the meaning and does not convey the nuance of the original sentence.

Correct translation:
Попытка потратить биткойны, затронутые ещё не отображёнными транзакциями, не будет принята сетью.
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>Полный путь до скрипта, совместимого с %1 (к примеру, C:\Downloads\hwi.exe или же /Users/you/Downloads/hwi.py). Будь бдителен: мошенники могут украсть твои деньги!</translation>
    
YES
The translation is mostly accurate, but the warning part deviates in tone and meaning: "Beware: malware can steal your coins!" translates to a specific threat of malware (вредоносное ПО), not simply fraudsters (мошенники). Also, "твои деньги" should be "ваши монеты" or "ваши средства" (with "coins" being specific to cryptocurrency). The formal register ("ваши") is generally preferred in software translations.

Correct translation:
Полный путь к скрипту, совместимому с %1 (например, C:\Downloads\hwi.exe или /Users/you/Downloads/hwi.py). Осторожно: вредоносное ПО может украсть ваши монеты!
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Использовать SOCKS5 прокси для доступа к узлам через этот тип сети.</translation>
    
YES
The translation does not accurately render the original meaning and changes the sentence from a descriptive statement ('Shows if...is used') to an instruction or affirmation ('Use SOCKS5 proxy to access...'). Additionally, the format is altered.

Correct translation:
Показывает, используется ли заданный по умолчанию SOCKS5-прокси для подключения к узлам через этот тип сети.
```

```
        <source>Options set in this dialog are overridden by the command line:</source>
        <translation>Параметры командной строки, которые переопределили параметры из этого окна:</translation>
    
YES
The Russian translation changes the meaning: it implies that "parameters of the command line have overridden parameters from this window," rather than stating that "options set in this dialog are overridden by the command line." The direction of overriding should be preserved.

Correct translation:
Параметры, установленные в этом окне, будут переопределены параметрами командной строки:
```

```
        <source>%1 from wallet '%2'</source>
        <translation>%1из кошелька '%2'</translation>
    
YES
There is a missing space between "%1" and "из" in the Russian translation, leading to a formatting issue.

Correct translation:
%1 из кошелька '%2'
```

```
        <source>The entered address does not refer to a legacy (P2PKH) key. Message signing for SegWit and other non-P2PKH address types is not supported in this version of %1. Please check the address and try again.</source>
        <translation>Введенный адрес не относится к устаревшему (P2PKH) ключу. Подписывание сообщений для SegWit и других не--P2PKH типов адресов не поддерживается в этой версии %1. Пожалуйста, проверьте адрес и попробуйте ещё раз.</translation>
    
YES
There is a typographical error in the translation: There is a double hyphen "не--P2PKH" instead of "не-P2PKH". Additionally, it is preferable to align the hyphen spacing for clarity and style in Russian.

Correct translation:
Введённый адрес не относится к устаревшему (P2PKH) ключу. Подписывание сообщений для SegWit и других не-P2PKH типов адресов не поддерживается в этой версии %1. Пожалуйста, проверьте адрес и попробуйте ещё раз.
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Это максимальная транзакция, которую вы заплатите (в добавок к обычной плате) для избежания затрат по причине отбора монет.</translation>
    
YES
The translation is inaccurate and does not fully convey the meaning of the source sentence. The phrase "maximum transaction fee" is mistranslated as "максимальная транзакция" (maximum transaction), which is incorrect. It should be "максимальная комиссия за транзакцию". The explanation about prioritizing partial spend avoidance is not precise.

Correct translation:
Это максимальная комиссия за транзакцию, которую вы заплатите (в дополнение к обычной комиссии), чтобы отдать приоритет избежанию частичных расходов перед стандартным выбором монет.
```

```
        <source>Wallet loaded successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future. Legacy wallets can be migrated to a descriptor wallet with migratewallet.</source>
        <translation>Кошелёк успешно создан. Старый формат кошелька признан устаревшим. Поддержка создания кошелька в этом формате и его открытие в будущем будут удалены.</translation>
    
YES
The translation omits important information from the original source text, namely the mention of migrating legacy wallets to a descriptor wallet with 'migratewallet'. Additionally, it translates "loaded" as "создан" (created), which is inaccurate; "загружен" (loaded) would be correct. 

Correct translation:
Кошелёк успешно загружен. Старый тип кошелька устарел, и поддержка создания и открытия старых кошельков будет удалена в будущем. Старые кошельки можно перенести в дескрипторный кошелёк с помощью команды migratewallet.
```

```
        <source>A fatal internal error occurred, see debug.log for details: </source>
        <translation>A fatal internal error occurred, see debug.log for details:</translation>
    
YES
The translation is not in Russian; it simply repeats the English text. It should be translated to Russian.

Correct translation:
Произошла фатальная внутренняя ошибка, подробности смотрите в debug.log:
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>Не удалось создать кошелёк 1%s</translation>
    
YES
The translation is problematic. The original format specifier "%s" must be preserved intact in the Russian translation, and there is an erroneous "1" before "%s". Also, "файл кошелька" more directly translates "wallet file", while "кошелёк" means "wallet".

Correct translation:
Не удалось создать файл кошелька: %s
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Ошибка: не удалось добавить транзакцию только для наблюдения(watchonly) %s  в  кошелек только для наблюдения (watchonly)</translation>
    
YES
There are formatting issues: extra spaces are present around "%s  в  кошелек", specifically before and after "%s". It also unnecessarily repeats the English term "watchonly" in parentheses, which may not be required for a Russian translation if a proper Russian term exists, but since "watchonly" is a specific Bitcoin term, including it in parentheses once is acceptable. However, better spacing and punctuation are required.

Correct translation:
Ошибка: не удалось добавить транзакцию только для наблюдения (watchonly) %s в кошелек только для наблюдения (watchonly)
```
</details>

Number of issues: 20.
