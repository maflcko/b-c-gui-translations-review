# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ru</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bru%5D%20low%20quality)


```
        <source>Create a new address</source>
        <translation>Создать новые адрес</translation>
    
YES, The translation uses the plural form "адрес" (addresses) instead of the singular "адрес" (address). This is grammatically incorrect in this context.
The correct translation should be "Создать новый адрес".
```

```
        <source>Delete the currently selected address from the list</source>
        <translation>Удалить выбранные адреса из списка</translation>
    
YES - The English source text uses the singular form "address," while the Russian translation uses the plural form "адреса." This discrepancy could lead to confusion if only one address is selected.

Correct translation: Удалить выбранный адрес из списка
```

```
        <source>Choose the address to send coins to</source>
        <translation>Выберите адреса, для отправки на них монет</translation>
    
YES, The Russian translation uses the plural form "адреса" (addresses) while the English source text uses the singular form "address". This is likely an error.

Correct translation: Выберите адрес для отправки монет.
```

```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>Це ваші біткоїн-адреси для надсилання платежів. Завжди перевіряйте суму та адресу отримання перед тим, як надсилати монети.</translation>
    
UNK_LANG
```

```
        <source>Passphrase Dialog</source>
        <translation>Пароль</translation>
    
YES. The translation is inaccurate and too brief. The original English text "Passphrase Dialog" implies a window or interface for entering a passphrase, not just the word "password".

Correct translation: Диалог ввода парольной фразы
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Пароль, введенный при шифровании кошелька, некорректен.</translation>
    
YES, The Russian translation incorrectly states that the password was entered during wallet encryption, when the English source text indicates it was for wallet decryption.
<source>The passphrase entered for the wallet decryption was incorrect.</source>
<translation>Пароль, введенный для расшифровки кошелька, некорректен.</translation>
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Текущий пароль, введенный для расшифрования кошелька, не подходит. Он содержит нулевой байт. Если пароль была задан в программе версии ниже 25.0, пожалуйста, попробуйте ввести только символы до первого нулевого байта, не включая его.</translation>
    
YES - The translation incorrectly states "Текущий пароль" (current password) instead of "old passphrase" which is "старый пароль" or "прежний пароль". The translation also missed the "incorrect" part in the first sentence.
Correct translation: Старый пароль, введенный для расшифровки кошелька, неверный. Он содержит нулевой байт. Если пароль был установлен в версии программы до 25.0, пожалуйста, попробуйте снова, используя только символы до первого нулевого байта, не включая его.
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Подписать сообщения своими Биткоин кошельками, что-бы доказать, что вы ими владеете</translation>
    
YES: The translation uses "кошельками" (wallets) which is a more general term than "addresses". While Bitcoin addresses are part of wallets, the source specifically mentions "addresses". A more accurate translation would use "адресами". Also, "что-бы" is a colloquial spelling and should be "чтобы".

NO
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Показать вкладку Узлы</translation>
    
YES: The word "Peers" in English, in the context of Bitcoin, refers to other nodes in the network that your node is connected to. "Узлы" in Russian translates to "nodes". Therefore, "Показать вкладку Узлы" is a more accurate translation of "Show Peers tab".
Correct translation: Показать вкладку Пиры
```

```
        <source>(un)select all</source>
        <translation>Выбрать все</translation>
    
YES, The translation is inaccurate because it only translates "select all" and misses the "(un)" part, which implies the option to deselect all as well.
Correct translation: Выбрать/отменить выбор всех
```

```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>Попытка потратить средства, использованные в транзакциях, которые ещё не синхронизированы, будет отклонена сетью.</translation>
    
YES: The translation inaccurately conveys the meaning of "not-yet-displayed transactions." The original English implies transactions that are not yet visible or confirmed on the network, whereas the Russian translation suggests transactions that are "not yet synchronized," which is a different concept. The correct translation should reflect the unconfirmed or unbroadcasted nature of the transactions.

Correct translation: Попытка потратить биткойны, затронутые транзакциями, которые еще не отображаются, не будет принята сетью.
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>Полный путь до скрипта, совместимого с %1 (к примеру, C:\Downloads\hwi.exe или же /Users/you/Downloads/hwi.py). Будь бдителен: мошенники могут украсть твои деньги!</translation>
    
YES - The translation incorrectly uses "мошенники" (scammers/fraudsters) instead of "вредоносное ПО" (malware) in the warning. The original text warns about "malware", which is a direct threat to security, whereas "scammers" implies a different kind of threat. Also, "твои деньги" (your money) is a bit too informal for a technical warning, a more neutral "ваши средства" (your funds) or "ваши монеты" (your coins) would be better.

Полный путь до скрипта, совместимого с %1 (к примеру, C:\Downloads\hwi.exe или же /Users/you/Downloads/hwi.py). Осторожно: вредоносное ПО может украсть ваши монеты!
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Использовать SOCKS5 прокси для доступа к узлам через этот тип сети.</translation>
    
YES: The translation incorrectly states that the SOCKS5 proxy is *used* rather than *showing if it is used*. Also, the original English uses "default SOCKS5 proxy", which is not fully captured.
Correct translation: Отображает, используется ли предоставленный прокси SOCKS5 по умолчанию для связи с узлами через этот тип сети.
```

```
        <source>Options set in this dialog are overridden by the command line:</source>
        <translation>Параметры командной строки, которые переопределили параметры из этого окна:</translation>
    
YES: The translation is inaccurate and potentially misleading. The original English states that the *options set in the dialog are overridden by the command line*, implying the command line has priority. The Russian translation states that the *command line parameters that overrode the parameters from this window*, which reverses the meaning and suggests the window's parameters overrode the command line.

Correct translation: Параметры, установленные в этом диалоговом окне, переопределяются параметрами командной строки:
```

```
        <source>%1 from wallet '%2'</source>
        <translation>%1из кошелька '%2'</translation>
    
YES, The translation is problematic due to a missing space between the first argument and the word "из".
%1 из кошелька '%2'
```

```
        <source>The entered address does not refer to a legacy (P2PKH) key. Message signing for SegWit and other non-P2PKH address types is not supported in this version of %1. Please check the address and try again.</source>
        <translation>Введенный адрес не относится к устаревшему (P2PKH) ключу. Подписывание сообщений для SegWit и других не--P2PKH типов адресов не поддерживается в этой версии %1. Пожалуйста, проверьте адрес и попробуйте ещё раз.</translation>
    
YES, the translation contains an erroneous hyphen in "не--P2PKH". The correct translation should be "не-P2PKH".
NO
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Это максимальная транзакция, которую вы заплатите (в добавок к обычной плате) для избежания затрат по причине отбора монет.</translation>
    
YES: The translation incorrectly interprets "prioritize partial spend avoidance over regular coin selection" as "avoiding expenses due to coin selection." The original English text refers to a fee that prioritizes avoiding partial spending (leaving small amounts of Bitcoin in an address) over the standard process of choosing coins (UTXOs) for a transaction.

Correct translation: Это максимальная комиссия транзакции, которую вы заплатите (в дополнение к обычной комиссии) для приоритезации избежания частичных трат над обычным выбором монет.
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Это комиссия за транзакцию, которую вы можете отбросить, если сдача меньше, чем пыль на этом уровне</translation>
    
YES: The word "пыль" (dust) is a direct translation but in the context of Bitcoin, "dust" refers to very small amounts of Bitcoin that are uneconomical to spend. A more appropriate translation would convey this meaning.
Correct translation: Это комиссия за транзакцию, которую вы можете отбросить, если сдача меньше пылевого значения на этом уровне.
```

```
        <source>Wallet loaded successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future. Legacy wallets can be migrated to a descriptor wallet with migratewallet.</source>
        <translation>Кошелёк успешно создан. Старый формат кошелька признан устаревшим. Поддержка создания кошелька в этом формате и его открытие в будущем будут удалены.</translation>
    
YES, The translation is inaccurate and omits important information. The source text states "Wallet loaded successfully", not "Wallet created successfully". It also omits the mention of the `migratewallet` command.

Correct translation: Кошелек успешно загружен. Старый формат кошелька устаревает, и поддержка создания и открытия старых кошельков будет удалена в будущем. Старые кошельки можно перенести в кошелек с дескриптором с помощью команды migratewallet.
```

```
        <source>Error: Address book data in wallet cannot be identified to belong to migrated wallets</source>
        <translation>Ошибка: адресная книга в кошельке не принадлежит к мигрируемым кошелькам</translation>
    
YES, The translation is problematic. The source text states that the address book data *cannot be identified to belong to* migrated wallets, implying an inability to confirm ownership or origin. The translation, however, asserts that the address book *does not belong to* migrated wallets, which is a stronger and potentially incorrect statement.

Correct translation: Ошибка: данные адресной книги в кошельке не могут быть отнесены к мигрированным кошелькам
```

```
        <source>Unexpected legacy entry in descriptor wallet found. Loading wallet %s

The wallet might have been tampered with or created with malicious intent.
</source>
        <translation>В дескрипторном кошельке %s обнаружено поле устаревшего формата.

Этот кошелёк мог быть подменён или создан со злым умыслом.
</translation>
    
YES. The translation is problematic because it mistranslates the word "entry" as "поле" (field), whereas a more accurate translation in this context would be "запись" (record) or "элемент" (element). Additionally, the phrase "loading wallet %s" is missing from the translation.

The wallet might have been tampered with or created with malicious intent.

Correct translation:
В дескрипторном кошельке %s обнаружена запись устаревшего формата. Загрузка кошелька %s.

Этот кошелёк мог быть подменён или создан со злым умыслом.
```

```
        <source>A fatal internal error occurred, see debug.log for details: </source>
        <translation>A fatal internal error occurred, see debug.log for details:</translation>
    
UNK_LANG
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>Не удалось создать кошелёк 1%s</translation>
    
YES, The format specifier '%s' is incorrectly translated to '1%s'. It should be '%s'. The word "wallet" is also translated to "кошелёк 1", which implies a number "1" before the wallet, this is incorrect.
The correct translation should be: Не удалось создать файл кошелька: %s
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Ошибка: не удалось добавить транзакцию только для наблюдения(watchonly) %s  в  кошелек только для наблюдения (watchonly)</translation>
    
YES
The translation is problematic because it uses "только для наблюдения(watchonly)" which is a literal translation of "watchonly" and sounds unnatural in Russian. Also, the preposition "в" is not needed before "кошелек".

A more natural and accurate translation would be:
Ошибка: не удалось добавить транзакцию watchonly %s в кошелек watchonly
```
</details>
