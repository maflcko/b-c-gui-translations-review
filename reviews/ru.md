# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ru</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bru%5D%20low%20quality)


```
        <source>Create a new address</source>
        <translation>Создать новые адрес</translation>
    
YES
The Russian translation uses the plural adjective "новые" with the singular noun "адрес," which is grammatically incorrect. "Адрес" is masculine singular and should be paired with the singular adjective "новый."

Correct translation:
Создать новый адрес
```

```
        <source>Delete the currently selected address from the list</source>
        <translation>Удалить выбранные адреса из списка</translation>
    
YES  
The source text refers to "the currently selected address" in singular, but the translation uses the plural "выбранные адреса" ("selected addresses"), which is inaccurate. The translation should reflect the singular form to match the source.

Correct translation:  
Удалить выбранный адрес из списка
```

```
        <source>Choose the address to send coins to</source>
        <translation>Выберите адреса, для отправки на них монет</translation>
    
YES  
The Russian translation is grammatically incorrect and stylistically awkward. "адреса" is plural while the source suggests choosing one address ("the address"). Also, "для отправки на них монет" is an unnatural construction. A more natural and accurate translation would be:

Выберите адрес для отправки монет
```

```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>Це ваші біткоїн-адреси для надсилання платежів. Завжди перевіряйте суму та адресу отримання перед тим, як надсилати монети.</translation>
    
YES  
The translation is actually in Ukrainian, not Russian. The English source is translated as:  
"Це ваші біткоїн-адреси для надсилання платежів. Завжди перевіряйте суму та адресу отримання перед тим, як надсилати монети."  
"Це" ("this is") and words like "надіслання", "перевіряйте", "перед тим, як" are Ukrainian, not Russian.

Correct Russian translation:  
"Это ваши биткоин-адреса для отправки платежей. Всегда проверяйте сумму и адрес получателя перед отправкой монет."
```

```
        <source>Passphrase Dialog</source>
        <translation>Пароль</translation>
    
YES
The English source "Passphrase Dialog" refers to a dialog window for entering a passphrase, not just the passphrase itself. The translation "Пароль" means only "Password," which is incomplete and potentially misleading. A correct translation would explicitly indicate that it is a dialog, for example:

Correct translation:
Диалог ввода пароля
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Пароль, введенный при шифровании кошелька, некорректен.</translation>
    
YES  
The translation incorrectly refers to "шифровании" (encryption) instead of "дешифровании" (decryption). The original English states that the passphrase for wallet decryption was incorrect.

Correct translation:  
Пароль, введенный для расшифровки кошелька, был неверным.
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Текущий пароль, введенный для расшифрования кошелька, не подходит. Он содержит нулевой байт. Если пароль была задан в программе версии ниже 25.0, пожалуйста, попробуйте ввести только символы до первого нулевого байта, не включая его.</translation>
    
YES
The translation has a grammatical error: "Если пароль была задан" is incorrect because "пароль" is masculine and should be "Если пароль был задан". Also, "нулевой байт" in the source is "null character (ie - a zero byte)" — "нулевой байт" is acceptable but "нулевой символ" or "нулевой байт" is fine; however, to match "null character" better, "нулевой символ" might be preferred but not critical. The em dash in the source was replaced by a comma, which changes the tone slightly. The second sentence could be slightly refined for clarity and naturalness.

Correct translation:
Текущая парольная фраза, введённая для расшифровки кошелька, неверна. Она содержит нулевой символ (то есть нулевой байт). Если парольная фраза была установлена в версии программы ниже 25.0, пожалуйста, попробуйте снова использовать только символы до — но не включая — первого нулевого символа.

Or a closer correction while keeping wording close:

Старый пароль, введённый для расшифровки кошелька, неверен. Он содержит нулевой символ (то есть нулевой байт). Если пароль был установлен в версии программы ниже 25.0, пожалуйста, попробуйте ввести только символы до — но не включая — первого нулевого символа.
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Подписать сообщения своими Биткоин кошельками, что-бы доказать, что вы ими владеете</translation>
    
YES  
The translation has minor issues:  
1. The word "кошельками" (wallets) is incorrect here; the source says "addresses," which should be translated as "адресами."  
2. The phrase "что-бы" is incorrect; the correct form is "чтобы" (without a hyphen).  
3. The wording "своими Биткоин кошельками" is awkward; it is better to say "своими Bitcoin-адресами" to match the source more precisely.  
4. Slight rephrasing improves the flow and clarity.

Correct translation:  
Подписывайте сообщения своими Bitcoin-адресами, чтобы доказать, что вы ими владеете
```

```
        <source>(un)select all</source>
        <translation>Выбрать все</translation>
    
YES  
The source text indicates a toggle action: "(un)select all" means the user can either select all or unselect all. The translation "Выбрать все" only means "Select all" and does not convey the "unselect all" part.

Correct translation:  
"(де)выбрать всё"  
or  
"Выбрать/снять выбор со всех"
```

```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>Попытка потратить средства, использованные в транзакциях, которые ещё не синхронизированы, будет отклонена сетью.</translation>
    
YES  
The translation introduces a meaning shift. The source text says "bitcoins that are affected by not-yet-displayed transactions," implying bitcoins influenced by transactions that have not yet been shown or confirmed, whereas the translation says "средства, использованные в транзакциях, которые ещё не синхронизированы" ("funds already spent in transactions that are not yet synchronized"), which suggests that bitcoins have already been spent, which changes the meaning.

A more accurate translation keeping the original meaning would be:  
"Попытка потратить биткойны, затронутые ещё не отображаемыми транзакциями, не будет принята сетью."
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>Полный путь до скрипта, совместимого с %1 (к примеру, C:\Downloads\hwi.exe или же /Users/you/Downloads/hwi.py). Будь бдителен: мошенники могут украсть твои деньги!</translation>
    
YES
The translation is mostly correct, but the phrase "Будь бдителен" sounds somewhat informal and less common in technical warnings. Also, "мошенники" literally means "scammers," which is less appropriate contextually in technical security warnings than "вредоносное ПО" (malware). The source warns about malware specifically stealing coins, not general scammers stealing money.

A more appropriate translation would be:
Полный путь до скрипта, совместимого с %1 (например, C:\Downloads\hwi.exe или /Users/you/Downloads/hwi.py). Внимание: вредоносное ПО может украсть ваши монеты!

This version preserves the technical tone, uses "например" (more standard than "к примеру"), and refers to "вредоносное ПО" (malware) stealing "монеты," consistent with Bitcoin terminology instead of "твои деньги."
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Использовать SOCKS5 прокси для доступа к узлам через этот тип сети.</translation>
    
YES  
The translation is not accurate. The source sentence describes what the software "shows" (i.e., indicates) whether the supplied SOCKS5 proxy is used, whereas the Russian translation is an imperative or statement meaning "Use SOCKS5 proxy to access nodes via this network type," which changes the meaning. Also, the nuance about "shows if" is lost.

Correct translation:  
Показывает, используется ли указанный SOCKS5 прокси для соединения с узлами через этот тип сети.
```

```
        <source>Options set in this dialog are overridden by the command line:</source>
        <translation>Параметры командной строки, которые переопределили параметры из этого окна:</translation>
    
YES  
The translation is somewhat inaccurate and awkward. The source says "Options set in this dialog are overridden by the command line:" — this means the options set via the command line take precedence over those set in the dialog. The Russian translation literally says "Command line parameters that overrode parameters from this window," which changes the sentence structure and could confuse the meaning.

A better translation would be:  
"Параметры, заданные в этом диалоговом окне, переопределяются параметрами командной строки:"
```

```
        <source>%1 from wallet '%2'</source>
        <translation>%1из кошелька '%2'</translation>
    
YES  
There is a missing space between "%1" and "из". It should be "%1 из кошелька '%2'".  

Correct translation:  
%1 из кошелька '%2'
```

```
        <source>The entered address does not refer to a legacy (P2PKH) key. Message signing for SegWit and other non-P2PKH address types is not supported in this version of %1. Please check the address and try again.</source>
        <translation>Введенный адрес не относится к устаревшему (P2PKH) ключу. Подписывание сообщений для SegWit и других не--P2PKH типов адресов не поддерживается в этой версии %1. Пожалуйста, проверьте адрес и попробуйте ещё раз.</translation>
    
YES  
There is a formatting issue with the double hyphen in "не--P2PKH". It should be a single hyphen or an en dash without spaces, matching the source.

Correct translation:  
Введенный адрес не относится к устаревшему (P2PKH) ключу. Подписывание сообщений для SegWit и других не-P2PKH типов адресов не поддерживается в этой версии %1. Пожалуйста, проверьте адрес и попробуйте ещё раз.
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Это максимальная транзакция, которую вы заплатите (в добавок к обычной плате) для избежания затрат по причине отбора монет.</translation>
    
YES
The translation is inaccurate and partially misleading. The English talks about the "maximum transaction fee you pay (in addition to the normal fee)" related to prioritizing "partial spend avoidance" over regular coin selection. The Russian translation incorrectly refers to "maximum transaction" and "costs due to coin selection," which distorts the original meaning and omits the "prioritize partial spend avoidance" concept.

A better translation would be:
Это максимальная комиссия за транзакцию, которую вы платите (в дополнение к обычной комиссии), чтобы приоритетно избегать частичного расхода средств по сравнению с обычным выбором монет.
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Это комиссия за транзакцию, которую вы можете отбросить, если сдача меньше, чем пыль на этом уровне</translation>
    
YES  
The translation is mostly correct, but the term "dust" in the Bitcoin context is better translated as "пыль" only if it is understood in the precise technical sense. However, the phrase "сдача меньше, чем пыль" sounds a bit unnatural in Russian. A more idiomatic and technically accurate translation would use "пыль" without "чем" or rephrase slightly for clarity.

Also, the comma before "если" is correct, and the format specifiers are not present here, so no issues there. No extra spaces or formatting problems.

A better translation would be:  
"Это комиссия за транзакцию, которую вы можете отбросить, если сдача меньше пыли на этом уровне"
```

```
        <source>Wallet loaded successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future. Legacy wallets can be migrated to a descriptor wallet with migratewallet.</source>
        <translation>Кошелёк успешно создан. Старый формат кошелька признан устаревшим. Поддержка создания кошелька в этом формате и его открытие в будущем будут удалены.</translation>
    
YES  
The Russian translation contains an error in the first sentence: "Кошелёк успешно создан." means "Wallet created successfully," but the source text says "Wallet loaded successfully." which is different. The rest of the translation is mostly accurate but could be improved for completeness and fidelity by including all parts of the original sentence, such as the mention of "Legacy wallets can be migrated to a descriptor wallet with migratewallet."

Correct translation:  
Кошелёк успешно загружен. Тип устаревшего кошелька устаревает, и поддержка создания и открытия таких кошельков будет убрана в будущем. Устаревшие кошельки можно мигрировать в дескрипторный кошелёк с помощью migratewallet.
```

```
        <source>A fatal internal error occurred, see debug.log for details: </source>
        <translation>A fatal internal error occurred, see debug.log for details:</translation>
    
YES
The translation is not translated into Russian; it remains in English. It should be translated to Russian to be appropriate.

Correct translation:
Произошла фатальная внутренняя ошибка, подробности см. в debug.log:
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>Не удалось создать кошелёк 1%s</translation>
    
YES  
The translation introduces an extraneous "1" before the format specifier "%s" and incorrectly translates "wallet file" as just "кошелёк" (wallet), omitting "file" ("файл кошелька"). The original error message refers to the failure to create the wallet file, not the wallet itself.

Correct translation:  
Не удалось создать файл кошелька: %s
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Ошибка: не удалось добавить транзакцию только для наблюдения(watchonly) %s  в  кошелек только для наблюдения (watchonly)</translation>
    
YES  
The Russian translation is understandable but awkward and has spacing issues around parentheses and extra spaces before "кошелек". Also, the English term "watchonly" could be localized or transliterated, but repeating the English word inside parentheses twice is redundant and stylistically poor. It is better to translate "watchonly" as "только для просмотра" or "только для наблюдения," and keep the phrase consistent and without spaces before parentheses.

Correct translation:  
Ошибка: не удалось добавить транзакцию только для просмотра %s в кошелёк только для просмотра
```
</details>
