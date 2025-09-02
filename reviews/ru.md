# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>ru</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bru%5D%20request)


<!-- cache_translation_check_ru_3d5142c12236a0298d28ab23d3b9ab635c2b1423345ef63266f16217b1080cb7 -->
```
        <source>Create a new address</source>
        <translation>Создать новые адрес</translation>
    
ERR
The translation is grammatically incorrect; "адрес" is singular and masculine, so the correct adjective form is "новый," not "новые" (which is plural feminine/neutral). It should be singular to match the English source.

Correct translation:
Создать новый адрес
```

<!-- cache_translation_check_ru_42d830ba9e1f3e976f0afb7a640a613b8fba2b9b6254a0f5d353b5a3c7992bb7 -->
```
        <source>Delete the currently selected address from the list</source>
        <translation>Удалить выбранные адреса из списка</translation>
    
ERR
The translation changes the number from singular ("the currently selected address") to plural ("выбранные адреса" = "selected addresses"), which is inaccurate. The source refers to a single address, so the translation should maintain the singular form.

Correct translation:
Удалить выбранный адрес из списка
</reply>
```

<!-- cache_translation_check_ru_3c3168105370b1f3cf2d3bb5a46a9575dade292875cf83b64d1631996b6fb72a -->
```
        <source>Choose the address to send coins to</source>
        <translation>Выберите адреса, для отправки на них монет</translation>
    
ERR
The translation is inaccurate in two ways:
1. "адреса" is plural, but the English source is singular ("the address").
2. There is an unnecessary comma after "адреса" and the preposition usage is awkward.

Correct translation:
Выберите адрес для отправки монет
```

<!-- cache_translation_check_ru_25bd04d2ce9462ad58d70a703797938d8e8feade557188fe21d53cd0c2b409b1 -->
```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Это ваши Биткойн адреса для получения платежей. Используйте кнопку «Создать новый адрес для получения» на вкладке Получить, чтобы создать новые адреса.
Подписание возможно только с адресами типа "наследие".</translation>
    
ERR
The word "наследие" is a literal but incorrect translation of Bitcoin term "legacy". Use "legacy" as-is or a phrase like "старого формата" / "формата legacy". Also minor stylistic suggestions for UI labels.

Corrected translation:
Это ваши адреса Bitcoin для получения платежей. Используйте кнопку «Создать новый адрес для получения» на вкладке «Получить», чтобы создать новые адреса.
Подписание возможно только с адресами формата legacy.

(Alternative with fully Russian wording for "legacy"):
Подписание возможно только с адресами старого формата (legacy).
```

<!-- cache_translation_check_ru_2f0956cf6a5e5f62bbe474a27d528ffe6c88bc0b666a02285b7ed89289f21d09 -->
```
        <source>Passphrase Dialog</source>
        <translation>Пароль</translation>
    
ERR
The translation is inaccurate. "Passphrase Dialog" refers to a dialog window for entering or managing a passphrase, not just a "password". The current translation loses this UI context.

Correct translation:
Диалоговая форма для ввода парольной фразы
```

<!-- cache_translation_check_ru_65095e9910e2d861df0524a62b79be81dbde9f76472518fa0c2dcf2ba0fc7d8f -->
```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Пароль, введенный при шифровании кошелька, некорректен.</translation>
    
ERR
The translation is inaccurate. The source refers to decryption ("wallet decryption"), but the translation says "при шифровании" (at encryption), which changes the meaning.

Correct translation:
Пароль, введённый для расшифровки кошелька, неверен.
```

<!-- cache_translation_check_ru_84bf920b15b1adfbc70ebf9808176caaf0033e15807bb0d98ceb494f0a8b9664 -->
```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Текущий пароль, введенный для расшифрования кошелька, не подходит. Он содержит нулевой байт. Если пароль была задан в программе версии ниже 25.0, пожалуйста, попробуйте ввести только символы до первого нулевого байта, не включая его.</translation>
    
ERR
There are a few issues:
1. "Текущий пароль" more literally means "current password", whereas "The old passphrase entered" is better translated as "Введённая старая парольная фраза" or "Старая введённая парольная фраза".
2. "Пароль была задан" — "пароль" is masculine and should be "был задан".
3. "пароль" is used instead of "парольная фраза", which is more accurate for "passphrase".
4. The phrasing "не подходит" ("does not fit") is less precise than "неверна" ("incorrect").

Correct translation:
Введённая старая парольная фраза для расшифровки кошелька неверна. Она содержит нулевой символ (то есть, байт со значением ноль). Если парольная фраза была установлена в версии программы до 25.0, пожалуйста, попробуйте ещё раз, используя только символы до — но не включая — первого нулевого символа.
```

<!-- cache_translation_check_ru_145cecf3dc5c4d48e67018be1d11ba68beaf132feb65ca5c0b9b83266a3093d2 -->
```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>Введите биткоин-адрес (например,%1)</translation>
    
ERR
There is a spacing issue: a space is missing after the comma before %1. 

Correct translation:
Введите биткоин-адрес (например, %1)
```

<!-- cache_translation_check_ru_1eb03c158f1133e6395efafd4f569a837bb2a3fd419294d8f8dc75f94d01da0b -->
```
        <source>Unroutable</source>
        <translation>Немаршрутизируемый</translation>
    
ERR
The literal word "Немаршрутизируемый" is understandable but uncommon/awkward in Russian. No format-specifier or whitespace issues.

Suggested clearer translations (choose depending on UI context):
- For a status/label (adjective): "Не маршрутизируемый"
- For a description/verb phrase: "Невозможно маршрутизировать"
```

<!-- cache_translation_check_ru_a30fa6d69a259594d9c43c0fa6b6c274dac44de3b2e8047d2dad593907cf4b9e -->
```
        <source>N/A</source>
        <translation>Н/д</translation>
    
ERR
The translation "Н/д" mixes uppercase and lowercase letters; for "N/A" the Russian abbreviation is typically written either "Н/Д" (uppercase) or "н/д" (lowercase) for consistency. No format specifiers or whitespace issues.

Correct translation (recommended):
Н/Д
```

<!-- cache_translation_check_ru_a72ab1013414bb2450ed3719336efc360147b19613743fbb31018736d00b1297 -->
```
        <source>About &amp;Qt</source>
        <translation>o &amp; неисчисляемoe</translation>
    
ERR
The translation is incorrect and nonsensical: "неисчисляемoe" means "uncountable" and has nothing to do with "Qt". Also the English program name "Qt" must be preserved. The ampersand should appear exactly once. Correct translation:

О &Qt
```

<!-- cache_translation_check_ru_b11b041b673bfd478dd6e658774539233acbc179d921ececd9d4f6affc3f6ffd -->
```
        <source>&amp;Minimize</source>
        <translation>&amp;Уменьшить</translation>
    
ERR
The translation "&Уменьшить" is understandable but not the standard Russian UI term for "Minimize" (window). "Уменьшить" literally means "make smaller" and can be ambiguous; the common and appropriate translation in GUI contexts is "Свернуть".

Correct translation:
&Свернуть
```

<!-- cache_translation_check_ru_47fffdbf7c769dc7756182e2221195373e2eb013c4b492d2260a87d7332188ae -->
```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Подписать сообщения своими Биткоин кошельками, что-бы доказать, что вы ими владеете</translation>
    
ERR
There are minor issues: the correct verb is "адресами" (addresses), not "кошельками" (wallets), and "чтобы" should not have a hyphen. Also, the comma after "сообщения" is awkward and unnecessary; better sentence structure would be more natural.

Correct translation:
Подписывайте сообщения своими Биткоин-адресами, чтобы доказать, что они принадлежат вам
```

<!-- cache_translation_check_ru_a78ac86d9401214b77d962b83811aad617a83c0f08be326360b218a1afd21dfa -->
```
        <source>&amp;Verify message…</source>
        <translation>&amp;Проверить сообщение</translation>
    
ERR
The translation is mostly correct, but it omits the ellipsis (…) present in the source. Preserve the ellipsis character and the single & for the shortcut.

Correct translation:
&amp;Проверить сообщение…
```

<!-- cache_translation_check_ru_71e8c11c3db97ad914706f490c173a135c5e3b6be3756c9e6a0223e977637db5 -->
```
        <source>(un)select all</source>
        <translation>Выбрать все</translation>
    
ERR
The translation only means "Select all". It misses the "(un)" part, which should indicate both "select all" and "deselect all". 

Correct translation:
(Выбрать/снять выбор) все
```

<!-- cache_translation_check_ru_84450f43bafc6f2e3db852a197c7dce7c555ae0cb74d48f707bc8d9e14a524e7 -->
```
        <source>L&amp;ock unspent</source>
        <translation>З&amp;аблокировать неизрасходованный остаток</translation>
    
ERR
The Russian is understandable but slightly unnatural for Bitcoin terminology: "неизрасходованный остаток" is awkward. In Bitcoin context "unspent" usually refers to outputs (UTXOs) — use "непотраченные выходы" or "неизрасходованные выходы". The ampersand is present once (OK).

Correct translation:
З&amp;аблокировать непотраченные выходы
```

<!-- cache_translation_check_ru_d0c0bcd204d05cbff45f05960e35b5f7a586846b1dd820dc76bea5c618602490 -->
```
        <source>&amp;Unlock unspent</source>
        <translation>&amp;Разблокировать неизрасходованный остаток</translation>
    
ERR
The Russian is understandable but slightly inaccurate for Bitcoin terminology. "Неизрасходованный остаток" reads as "unspent balance" (singular) while the source likely refers to unlocking unspent outputs/UTXOs. Use terminology consistent with Bitcoin UI.

Suggested corrections (choose depending on intended meaning):
- For unspent outputs/UTXOs: &Разблокировать неизрасходованные выходы
- For unspent funds/balance: &Разблокировать неизрасходованные средства

The ampersand is present exactly once and spacing is fine.
```

<!-- cache_translation_check_ru_57a70500f7ef68fe67654f531dc6b883091a4bd50712ee7bfc0410005dc942ca -->
```
        <source>Open Wallet</source>
        <extracomment>Title of window indicating the progress of opening of a wallet.</extracomment>
        <translation>Открыть кошелёк</translation>
    
ERR
The Russian translation "Открыть кошелёк" is an infinitive/imperative ("Open wallet") and suits a button label, but the source is a window title indicating the progress of opening a wallet. The correct translation for that context is the noun phrase "Opening wallet".

Correct translation:
Открытие кошелька
```

<!-- cache_translation_check_ru_ca07309fb016b0abcea0827e872670e13db0787f69eeb10fd38756bcfbb33016 -->
```
        <source>Restore Wallet</source>
        <extracomment>Title of progress window which is displayed when wallets are being restored.</extracomment>
        <translation>Восстановить кошелёк</translation>
    
ERR
The Russian text "Восстановить кошелёк" is an imperative ("Restore wallet") whereas the context is a window title shown while wallets are being restored (a noun/gerund). Use a noun form.

Correct translation (singular):
Восстановление кошелька

Or if referring to multiple wallets (matches the context):
Восстановление кошельков
```

<!-- cache_translation_check_ru_1570b09f72034a92ea1140b93f40cbe7b24b54981bba1580f90cbc258c336f23 -->
```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>Попытка потратить средства, использованные в транзакциях, которые ещё не синхронизированы, будет отклонена сетью.</translation>
    
ERR
The translation is problematic because it alters the meaning of the original sentence. The English source specifically refers to "bitcoins that are affected by not-yet-displayed transactions," meaning bitcoins tied up in transactions that have not yet appeared/been displayed in the user's wallet. The Russian translation refers to "funds used in transactions that are not yet synchronized," which changes the meaning and does not convey the nuance of the original sentence.

Correct translation:
Попытка потратить биткойны, затронутые ещё не отображёнными транзакциями, не будет принята сетью.
```

<!-- cache_translation_check_ru_4872ca5cad45a238098245376c302f76ab0568d6c48add1775ea8c957066f4dd -->
```
        <source>Size of &amp;database cache</source>
        <translation>Размер кеша &amp;базы данных</translation>
    
ERR
Minor issue: the word "кеша" is misspelled. The correct spelling is "кэша". The ampersand is used exactly once (OK).

Correct translation:
Размер кэша &базы данных
```

<!-- cache_translation_check_ru_1874ae6ad7ad6c9d07306d5b36ceb2a496115f64642e3fbf2635e6d01ffe6853 -->
```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>Полный путь до скрипта, совместимого с %1 (к примеру, C:\Downloads\hwi.exe или же /Users/you/Downloads/hwi.py). Будь бдителен: мошенники могут украсть твои деньги!</translation>
    
ERR
The translation is mostly accurate, but the warning part deviates in tone and meaning: "Beware: malware can steal your coins!" translates to a specific threat of malware (вредоносное ПО), not simply fraudsters (мошенники). Also, "твои деньги" should be "ваши монеты" or "ваши средства" (with "coins" being specific to cryptocurrency). The formal register ("ваши") is generally preferred in software translations.

Correct translation:
Полный путь к скрипту, совместимому с %1 (например, C:\Downloads\hwi.exe или /Users/you/Downloads/hwi.py). Осторожно: вредоносное ПО может украсть ваши монеты!
```

<!-- cache_translation_check_ru_1f8854256831b57da5d70c06a068dd107a93c19736d5c9ec3191a8dc212edf19 -->
```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Использовать SOCKS5 прокси для доступа к узлам через этот тип сети.</translation>
    
ERR
The translation does not accurately render the original meaning and changes the sentence from a descriptive statement ('Shows if...is used') to an instruction or affirmation ('Use SOCKS5 proxy to access...'). Additionally, the format is altered.

Correct translation:
Показывает, используется ли заданный по умолчанию SOCKS5-прокси для подключения к узлам через этот тип сети.
```

<!-- cache_translation_check_ru_294e436bba811aa57996d5501112288a9e88e0f7f0902c566f0078d6b9b6b8d5 -->
```
        <source>Options set in this dialog are overridden by the command line:</source>
        <translation>Параметры командной строки, которые переопределили параметры из этого окна:</translation>
    
ERR
The Russian translation changes the meaning: it implies that "parameters of the command line have overridden parameters from this window," rather than stating that "options set in this dialog are overridden by the command line." The direction of overriding should be preserved.

Correct translation:
Параметры, установленные в этом окне, будут переопределены параметрами командной строки:
```

<!-- cache_translation_check_ru_faf091f7959e2a534ef478e45492d82a72a83277259ae82400dcdf37f1c7a063 -->
```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>Вычитать комиссию из суммы по умолчанию или нет.</translation>
    
ERR
The Russian wording is ambiguous/awkward: "Вычитать комиссию из суммы по умолчанию или нет." reads as if "по умолчанию" modifies "суммы" (the default amount), not the action of making subtracting the fee the default behavior.

Suggested corrections:
- "Устанавливать по умолчанию вычитание комиссии из суммы или нет."
or a shorter tooltip-style:
- "Вычитать комиссию из суммы по умолчанию?"
or
- "Устанавливать вычитание комиссии из суммы по умолчанию."
```

<!-- cache_translation_check_ru_0e5b60066befe02b63f37ea669124d017c2dc07d418d9270e53aa46f24c48760 -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Вычесть &amp;комиссию из суммы</translation>
    
ERR
The translation misses the "by default" meaning ("по умолчанию") from the source — "Вычесть комиссию из суммы" is just an action, not an Options setting to make this the default. The ampersand is present once and fine, and there are no spacing/format issues.

Suggested correct translation:
По умолчанию вычитать &комиссию из суммы
```

<!-- cache_translation_check_ru_337b7d35c103b586866a5611349e76ba912b82afa83820042d95d7891397bfc5 -->
```
        <source>Expert</source>
        <translation>Экспертные настройки</translation>
    
ERR
The source is a single word "Expert". The translation "Экспертные настройки" means "Expert settings" (adds "settings") and is not an accurate literal match. No format specifiers or whitespace issues.

Correct translation (depending on context):
- For a single-label or mode: Эксперт
- If it specifically denotes a mode named "Expert mode": Режим эксперта
(Use "Эксперт" for a short label/title.)
```

<!-- cache_translation_check_ru_c55e70beedc377d6619d46d58bb695da5d3fe42c10e5d6ab88630274f68a6205 -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Включить управление частично подписанными транзакциями (PSBT)</translation>
    
ERR
The translation is correct in meaning, but it is missing the shortcut marker (&). The source contains "&amp;PSBT controls" so the translation must include a single '&' to mark the accelerator. No other format specifiers or whitespace issues.

Suggested correction (include & once):
Включить элементы &управления частично подписанными транзакциями (PSBT)
```

<!-- cache_translation_check_ru_d31e3c26691dc96295e7c44cd7a773d72221075821cabad6d99a92b73d286ed2 -->
```
        <source>&amp;External signer script path</source>
        <translation>&amp;Внешний скрипт для подписи</translation>
    
ERR
The translation omits "path" — it reads "External script for signing" instead of "External signer script path". Suggest a corrected translation that includes "path" and keeps the shortcut marker (&):

Correct translation:
&Путь к внешнему скрипту подписи
```

<!-- cache_translation_check_ru_d68da6ace4391ae4a31be7a80ba442db4532c72111dcf17d615ab8c57e1d32cc -->
```
        <source>Proxy &amp;IP:</source>
        <translation>IP &amp;прокси:</translation>
    
ERR
Word order and phrasing are unnatural in Russian. "IP &прокси:" reads awkwardly; better to use a natural Russian label and keep a single &.

Suggested correction:
IP-адрес &прокси:
```

<!-- cache_translation_check_ru_d1c010dad6ebf0d5d6453788401fb45198f0b77a59e418da568092804da9fd11 -->
```
        <source>&amp;Show tray icon</source>
        <translation>&amp;Показывать значок в области ведомлений</translation>
    
ERR
The Russian phrase uses "области ведомлений", which is incorrect. The correct term is "области уведомлений" (or simply "в трее"). The ampersand is used once (OK).

Correct translation:
&Показывать значок в области уведомлений

(Alternative shorter option:
&Показывать значок в трее)
```

<!-- cache_translation_check_ru_b369cb312596c584d1801cd4c665fd65f35f87b07f8fe7f7db22029d17e5b905 -->
```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>Невозможно подписать входы пока кошелёк заблокирован</translation>
    
ERR
The translation is understandable but has minor punctuation/grammar issues: it lacks a comma before "пока" and a terminating period. Also consider using the imperfective infinitive "подписывать" but "подписать" is acceptable. No format specifiers are involved.

Corrected translation:
Невозможно подписать входы, пока кошелёк заблокирован.
```

<!-- cache_translation_check_ru_e91159b2f650679be23f0c14319f5ac37849c986f6ca9546454cc7be8a10f352 -->
```
        <source>PSBT copied to clipboard.</source>
        <translation>PSBT скопирована в буфер обмена</translation>
    
ERR
The translation is mostly correct, but it omits the final period from the source. Also a more common/neutral phrasing in Russian would be "PSBT скопирована в буфер обмена." (keeping the period). 

Correct translation:
PSBT скопирована в буфер обмена.
```

<!-- cache_translation_check_ru_242fadcdbd4cd1a0ef582a138bf0ba5206a09464ebb2e45461985290d2841ab4 -->
```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>Частично подписанная транзакция (двоичный файл)</translation>
    
ERR
The translation adds the word "файл" ("file") which is not present in the source and slightly changes the meaning: the source denotes the binary format, not explicitly "binary file". Better to mirror the original more closely.

Correct translation:
Частично подписанная транзакция (в двоичном формате)
```

<!-- cache_translation_check_ru_8f18a784e69db356ec6e20fca23ee6ef7f6f8fc7d54e12fdbba2655d77598e2c -->
```
        <source>Transaction is missing some information about inputs.</source>
        <translation>Транзакция имеет недостаточно информации о некоторых входах.</translation>
    
ERR
The Russian phrasing is understandable but unidiomatic: "Транзакция имеет недостаточно информации о некоторых входах." is awkward (literal "has not enough information"). Better, more natural translations would be:

Correct translations:
В транзакции отсутствует некоторая информация о входах.
or
В транзакции не хватает информации о некоторых входах.
```

<!-- cache_translation_check_ru_33488b79fd13e1d9b13759a2d06c1de0891b4f8c3b47f429a89d1917b3cace1c -->
```
        <source>Transaction still needs signature(s).</source>
        <translation>Транзакции требуется по крайней мере ещё одна подпись.</translation>
    
ERR
The Russian is understandable but slightly ungrammatical/awkward: "Транзакции требуется..." misses a preposition and the phrasing is redundant. Also "по крайней мере ещё одна" is wordy.

Correct translation:
Для транзакции по-прежнему требуется хотя бы одна подпись.
```

<!-- cache_translation_check_ru_5ca7a77001f3d8c0830f5b75e931e7630ef47846c77be56af7aa1cc663704e60 -->
```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Невозможно запустить обработчик bitcoin: click-to-pay</translation>
    
ERR
The Russian is understandable but awkward and misorders the elements. It mixes English and Russian in a confusing way and uses lowercase "bitcoin". More natural and accurate translations would preserve meaning and read fluently in Russian.

Correct translations (choose one):
- Не удалось запустить обработчик click-to-pay для Bitcoin
- Невозможно запустить обработчик click-to-pay для Bitcoin

(If you prefer fully Russian wording for "click-to-pay", you can also use:
- Не удалось запустить обработчик «Click-to-Pay» для Bitcoin)
```

<!-- cache_translation_check_ru_a0d1056dac6c679db9b1de61d151e2c6dcfe28d9e4a1306f2198bac50908902b -->
```
        <source>Cannot process payment request because BIP70 is not supported.
Due to widespread security flaws in BIP70 it's strongly recommended that any merchant instructions to switch wallets be ignored.
If you are receiving this error you should request the merchant provide a BIP21 compatible URI.</source>
        <translation>Не удалось обработать транзакцию, потому что BIP70 не поддерживается.
Из-за широко распространённых уязвимостей в BIP70, настоятельно рекомендуется игнорировать любые инструкции продавцов сменить кошелёк.
Если вы получили эту ошибку, вам следует попросить у продавца URI, совместимый с BIP21.</translation>
    
ERR
The translation is mostly clear but has two issues:
1. "payment request" was translated as "транзакцию" (transaction), which is less accurate than "запрос платежа".
2. Slightly awkward phrasing in the second sentence: "инструкции продавцов сменить кошелёк" — better as singular/plural agreement or using "по смене кошелька".

Correct translation:
Не удалось обработать запрос на оплату, потому что BIP70 не поддерживается.
Из‑за широко распространённых уязвимостей в BIP70 настоятельно рекомендуется игнорировать любые инструкции продавца/продавцов по смене кошелька.
Если вы получили эту ошибку, вам следует попросить у продавца URI, совместимый с BIP21.
```

<!-- cache_translation_check_ru_0c44a413d9cda32a23f6e9f9de29542bd1e933db82b5beaf32f894f1472eadde -->
```
        <source>Inbound</source>
        <extracomment>An Inbound Connection from a Peer.</extracomment>
        <translation>Входящий</translation>
    
ERR
The Russian adjective should agree with "соединение" (neuter). "Входящий" is masculine; the correct form is "Входящее".

Correct translation:
Входящее

No format specifiers or spacing issues present.
```

<!-- cache_translation_check_ru_6897a59c118ac33debd4392490a26b9def570d1e749dd351858de3134c833747 -->
```
        <source>%1 from wallet '%2'</source>
        <translation>%1из кошелька '%2'</translation>
    
ERR
There is a missing space between "%1" and "из" in the Russian translation, leading to a formatting issue.

Correct translation:
%1 из кошелька '%2'
```

<!-- cache_translation_check_ru_c362fc34bcdf152133df4cce0365deb01f1d11f5fc3e8e10ddfa7be16f10bda1 -->
```
        <source>The entered address does not refer to a legacy (P2PKH) key. Message signing for SegWit and other non-P2PKH address types is not supported in this version of %1. Please check the address and try again.</source>
        <translation>Введенный адрес не относится к устаревшему (P2PKH) ключу. Подписывание сообщений для SegWit и других не--P2PKH типов адресов не поддерживается в этой версии %1. Пожалуйста, проверьте адрес и попробуйте ещё раз.</translation>
    
ERR
There is a typographical error in the translation: There is a double hyphen "не--P2PKH" instead of "не-P2PKH". Additionally, it is preferable to align the hyphen spacing for clarity and style in Russian.

Correct translation:
Введённый адрес не относится к устаревшему (P2PKH) ключу. Подписывание сообщений для SegWit и других не-P2PKH типов адресов не поддерживается в этой версии %1. Пожалуйста, проверьте адрес и попробуйте ещё раз.
```

<!-- cache_translation_check_ru_19d4c80862747d27b9d8915a76a2f7bdd2b25a09deb9f79bdea26b0a2a1cdb80 -->
```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Это максимальная транзакция, которую вы заплатите (в добавок к обычной плате) для избежания затрат по причине отбора монет.</translation>
    
ERR
The translation is inaccurate and does not fully convey the meaning of the source sentence. The phrase "maximum transaction fee" is mistranslated as "максимальная транзакция" (maximum transaction), which is incorrect. It should be "максимальная комиссия за транзакцию". The explanation about prioritizing partial spend avoidance is not precise.

Correct translation:
Это максимальная комиссия за транзакцию, которую вы заплатите (в дополнение к обычной комиссии), чтобы отдать приоритет избежанию частичных расходов перед стандартным выбором монет.
```

<!-- cache_translation_check_ru_49d1d04b7076706d5b8646deb60aa9101e35e908a30cdf37603f264c1e48f6a0 -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>Очистка: последняя синхронизация кошелька выходит за рамки обрезанных данных. Необходимо выполнить переиндексацию (перезагрузить весь блокчейн в случае обрезания узла).</translation>
    
ERR
The translation is understandable but contains awkward and slightly incorrect word choices: "Очистка" is a poor rendering of "Prune" (better "Обрезка" or "Режим обрезки"), "выходит за рамки" is less natural than "выходит за пределы", "перезагрузить" is misleading for "download again", and "в случае обрезания узла" is ungrammatical — should be "в случае обрезанного узла". Also the command flag -reindex should be preserved as-is.

Suggested correction:
Режим обрезки: последняя синхронизация кошелька выходит за пределы обрезанных данных. Необходимо выполнить -reindex (скачать блокчейн заново в случае обрезанного узла).
```

<!-- cache_translation_check_ru_2a5d5f3d239e4309ee63ef4763a983cc2d51d881ca14dbbae2cf4aa103af97de -->
```
        <source>A fatal internal error occurred, see debug.log for details: </source>
        <translation>A fatal internal error occurred, see debug.log for details:</translation>
    
ERR
The translation is not in Russian; it simply repeats the English text. It should be translated to Russian.

Correct translation:
Произошла фатальная внутренняя ошибка, подробности смотрите в debug.log:
```

<!-- cache_translation_check_ru_290f4041693314e289fd2274f5782a6f3343805f1ec49bea8de6390d62f235f2 -->
```
        <source>Failed to acquire rescan reserver during wallet initialization</source>
        <translation>Не удалось получить повторное сканирование резерва во время инициализации кошелька.</translation>
    
ERR
The phrase "rescan reserver" is mistranslated. The Russian "повторное сканирование резерва" is unnatural and changes the meaning. It should convey obtaining a "reserver" / reserve/lock for a rescan.

Correct translation:
Не удалось получить резерв для повторного сканирования во время инициализации кошелька.
```

<!-- cache_translation_check_ru_93090ca67f65e1e6355ba620441bede23d5950b2792429a74ea5f0cdd9760df6 -->
```
        <source>Wallet file creation failed: %s</source>
        <translation>Не удалось создать кошелёк 1%s</translation>
    
ERR
The translation is problematic. The original format specifier "%s" must be preserved intact in the Russian translation, and there is an erroneous "1" before "%s". Also, "файл кошелька" more directly translates "wallet file", while "кошелёк" means "wallet".

Correct translation:
Не удалось создать файл кошелька: %s
```

<!-- cache_translation_check_ru_cfdf3d36935f11cff87477924039f7f54a55684a8b7327ea6a94dd33450b5e6a -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation> Ошибка загрузки %s: кошелек является устаревшим. Пожалуйста, перейдите на дескрипторный кошелек с помощью инструмента миграции (migratewallet RPC).</translation>
    
ERR
There is an extra leading space before "Ошибка" and minor stylistic issues. The format specifier %s is preserved correctly.

Suggested correction (remove leading space, optional use of "кошелёк" and place "RPC" before name for natural phrasing):

Ошибка загрузки %s: кошелёк является устаревшим. Пожалуйста, выполните миграцию на дескрипторный кошелёк с помощью инструмента миграции (RPC migratewallet).
```

<!-- cache_translation_check_ru_43ae5fed7dbcc51942d23b9787f875b74763992bc4039ca3b11f737f06ae8655 -->
```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on an enormous cluster of unconfirmed transactions.</source>
        <translation>Не удалось рассчитать комиссионные за бамп, поскольку неподтвержденные UTXO зависят от огромного скопления неподтвержденных транзакций.</translation>
    
ERR
The translation uses the anglicism "бамп" which is unnatural in Russian. Better to use "повышения комиссии" or "увеличения комиссии". Also "комиссионные за ..." is slightly odd; "сумму повышения комиссии" or simply "повышение комиссии" is more natural.

Correct translation:
Не удалось рассчитать сумму повышения комиссии, поскольку неподтверждённые UTXO зависят от огромного скопления неподтверждённых транзакций.
```

<!-- cache_translation_check_ru_d01d816e56bc71244f140dfe113c7a50b6f4f80cde48e14e148e1cf58ffacd88 -->
```
        <source>Transaction requires one destination of non-zero value, a non-zero feerate, or a pre-selected input</source>
        <translation>Для транзакции требуется один пункт назначения с ненулевым значением, ненулевая ставка или предварительно выбранный вход.</translation>
    
ERR
The translation is mostly understandable but has stylistic and terminology issues for Bitcoin context: "пункт назначения" is awkward (better "адрес назначения"), "ставка" alone is vague for "feerate" (use "ставка комиссии" or "уровень комиссии"), and the list items should be connected consistently (use "либо ... либо ... либо").

Correct translation:
Транзакция требует либо одного адреса назначения с ненулевой суммой, либо ненулевой ставки комиссии, либо заранее выбранного входа.
```

<!-- cache_translation_check_ru_b45936091f7d98f10731f1b621a2837aee9f2ed808fa924193c4fa4eaf00809e -->
```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Ошибка: не удалось добавить транзакцию только для наблюдения(watchonly) %s  в  кошелек только для наблюдения (watchonly)</translation>
    
ERR
There are formatting issues: extra spaces are present around "%s  в  кошелек", specifically before and after "%s". It also unnecessarily repeats the English term "watchonly" in parentheses, which may not be required for a Russian translation if a proper Russian term exists, but since "watchonly" is a specific Bitcoin term, including it in parentheses once is acceptable. However, better spacing and punctuation are required.

Correct translation:
Ошибка: не удалось добавить транзакцию только для наблюдения (watchonly) %s в кошелек только для наблюдения (watchonly)
```
</details>

Number of issues: 50.
