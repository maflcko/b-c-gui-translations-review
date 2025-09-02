# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>uk</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Buk%5D%20request)


<!-- cache_translation_check_uk_9516be5454e48e06befa4cf6520a0b565bc672f9382175a2fb2c7f1e80d9566e -->
```
        <source>&amp;Export</source>
        <translation>Експортувати</translation>
    
ERR
The translation misses the ampersand, which indicates the shortcut key in the UI. It must appear exactly once in the translation, at the appropriate place.

Correct translation:
&Експортувати
```

<!-- cache_translation_check_uk_34da7fd6bcd6baafb8ccca6b702f6be8472c470252a71d50fed13e9ad1b38a7a -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>Змінити парол&amp;ь…</translation>
    
ERR
The ampersand (&) for the shortcut key is positioned incorrectly in the Ukrainian translation, splitting the word "пароль" into "парол&amp;ь". It should precede the correct letter in the word, typically the first letter, such as "&Змінити пароль…" or "З&мінити пароль…", but should not break up a word. Also, Ukrainian convention often uses "Змінити &пароль…".

Correct translation:
Змінити &пароль…
```

<!-- cache_translation_check_uk_1b653cb0f1df10c68c3a62f4425943058622c414e4dfcbef366dadcc9ce398c4 -->
```
        <source>&amp;Unlock unspent</source>
        <translation>&amp;Розблокувати монети</translation>
    
ERR
The translation changes the meaning. The English text "&Unlock unspent" refers specifically to "unspent" outputs, not "coins" in general. The term "монети" ("coins") is a non-technical, somewhat imprecise rendering in this Bitcoin context, where "невитрачені" ("unspent") should be retained for clarity.

Correct translation:
&Розблокувати невитрачені
```

<!-- cache_translation_check_uk_7e25c72e484e0985406fe389ca30260e74251338e3934680c6b7fa6fa921eda8 -->
```
        <source>&amp;Main</source>
        <translation>&amp;Загальні</translation>
    
ERR
The translation of "&Main" should be more contextually accurate. "Main" in application menus typically refers to "Main" as "Головні" or "Основні", not "Загальні" (which means "General"). Also, the ampersand for the shortcut key is retained, which is correct.

Correct translation:
&Головні
or
&Основні

If "Main" is intended as a section for primary options or dashboard: "&Головні"
If it's the main settings: "&Основні"
```

<!-- cache_translation_check_uk_f0c7ae178102efe611dae5c451ecf26ae870d5e83ad9a76563c335417e109692 -->
```
        <source>Enable coin &amp;control features</source>
        <translation>Ввімкнути керування в&amp;ходами</translation>
    
ERR
The translation renders "coin control" as "керування входами", which literally means "input control". While "coin control" in Bitcoin terminology actually refers to the user's ability to control the selection of specific unspent transaction outputs ("UTXOs")—they are often translated as "монети" (coins/outputs), not "входи" (inputs). Also, the position of the '&' should be equivalent to a hotkey in the source.

Correct translation:
Увімкнути функції к&онтролю монет
```

<!-- cache_translation_check_uk_f1dc6dc113383da78714d321f0b6e597fec6a06e4ae8c81865152fbf0c73cd0a -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Дозволити вхідні з'єднання</translation>
    
ERR
The ampersand (&) indicating the shortcut key in "incomin&g" from the source is missing in the translation, so the shortcut will not work in the Ukrainian version. The ampersand should be present exactly once and placed before an appropriate character.

Correct translation:
Дозволити в&хідні з'єднання
```

<!-- cache_translation_check_uk_bba18ded84447d01e90e59b31c7e96f747a6375654aac22a979598c727b15495 -->
```
        <source>&amp;Unit to show amounts in:</source>
        <translation>В&amp;имірювати монети в:</translation>
    
ERR
The translation is inaccurate. The original means "Unit to show amounts in," which should refer to the units (e.g., BTC, mBTC) in which Bitcoin amounts are displayed. The translation "Вимірювати монети в" literally means "To measure coins in," which is awkward and not standard in Ukrainian user interfaces.

Correct translation:
Одиниця для відображення сум:&amp;
```

<!-- cache_translation_check_uk_cf4c2190c3b52e5660dbe1fb3d188e26c195071e0bb0b62a69b7a45ad0b0faee -->
```
        <source>Cannot process payment request because BIP70 is not supported.
Due to widespread security flaws in BIP70 it's strongly recommended that any merchant instructions to switch wallets be ignored.
If you are receiving this error you should request the merchant provide a BIP21 compatible URI.</source>
        <translation>Не вдалося обробити запит на оплату, оскільки BIP70 не підтримується.
Через поширені недоліки безпеки в BIP70 рекомендується ігнорувати будь -які вказівки продавців щодо перемикання гаманців.
Якщо ви отримуєте цю помилку, вам слід вимагати у продавця надати URI, який сумісний з BIP21.</translation>
    
ERR
Issues:
- Incorrect spacing around the hyphen in "будь -які" (should be "будь-які").
- Slightly awkward phrasing: "вказівки продавців" (plural) vs. the source's generic singular "merchant instructions" — better to use singular "продавця" or neutral "торговця". Also "недоліки безпеки" is understandable but "вразливості" is more idiomatic for security context.

Corrected translation:
Не вдалося обробити запит на оплату, оскільки BIP70 не підтримується.
Через поширені вразливості в BIP70 рекомендується ігнорувати будь-які вказівки продавця щодо перемикання гаманців.
Якщо ви отримуєте цю помилку, вам слід вимагати від продавця надати URI, сумісний з BIP21.
```

<!-- cache_translation_check_uk_f854f02e6c3136b59f68a3b5c2e218c1e8b48ed01fab54a45181d85fb312ddfc -->
```
        <source>Could not generate new %1 address</source>
        <translation>Не вдалося згенерувати нову %1 адресу</translation>
    
ERR
The translation is understandable but the word order is unnatural in Ukrainian. The modifier %1 should follow "адресу" or be hyphenated. Also keep the %1 placeholder intact.

Correct translation:
Не вдалося згенерувати нову адресу %1
```

<!-- cache_translation_check_uk_e410cdcfd13c2ce3f5ebf60aafb28820d51fd064cda997d02fef7fb00c774442 -->
```
        <source>Recommended:</source>
        <translation>Рекомендована:</translation>
    
ERR
The Ukrainian translation uses the feminine adjective form "Рекомендована:" which is unnatural as a standalone label. Use the neutral/adverbial form.

Correct translation:
Рекомендовано: (or alternatively: Рекомендується:)
```

<!-- cache_translation_check_uk_1990a3dae3a6930380d420668aceb17e0450619d6a857abd574188ef760ab27e -->
```
        <source>Custom:</source>
        <translation>Власна:</translation>
    
ERR
"Власна:" is ambiguous and may use the wrong gender form. A more standard Ukrainian UI translation for "Custom:" is "Користувацький:".

Correct translation:
Користувацький:
```

<!-- cache_translation_check_uk_185d907919e1004e1f1e38eaa5a0e88c7ecbca4ab811d57461a3c7c80c0ca0b4 -->
```
        <source>Pay &amp;To:</source>
        <translation>&amp;Отримувач:</translation>
    
ERR
The Ukrainian translation uses "Отримувач" which means "Recipient," but the original English is "Pay To," not "Recipient." The translation should more closely follow the meaning and form of the original, which is a prompt for an address to which payment is sent.

Correct translation:
&Сплатити:

or

&Кому сплатити:
```

<!-- cache_translation_check_uk_6e1248cff4386c2513c43fc435d83ff61585994b58c9382aa3fe07d1d14ffb40 -->
```
        <source>Copy &amp;raw transaction</source>
        <translation>Копіювати &amp;всю транзакцію</translation>
    
ERR
The term "raw transaction" in the Bitcoin context refers specifically to the transaction in its raw (serialized) hexadecimal form rather than the entire transaction or all its details. The Ukrainian "всю транзакцію" means "entire transaction," which is not precise.

Correct translation:
Копіювати &amp;сиру транзакцію
```

<!-- cache_translation_check_uk_9516be5454e48e06befa4cf6520a0b565bc672f9382175a2fb2c7f1e80d9566e -->
```
        <source>&amp;Export</source>
        <translation>Експортувати</translation>
    
ERR
The translation misses the ampersand, which indicates the shortcut key in the UI. It must appear exactly once in the translation, at the appropriate place.

Correct translation:
&Експортувати
```

<!-- cache_translation_check_uk_e2cec1b777725cb0a20d9aca637b8a871f63706ec5adffde77d5174b499f1b54 -->
```
        <source>You need to rebuild the database using -reindex to go back to unpruned mode.  This will redownload the entire blockchain</source>
        <translation>Вам необхідно перебудувати базу даних з використанням -reindex для завантаження повного блокчейну.</translation>
    
ERR  
The translation omits the explanation that this action is needed to return to "unpruned mode" and that the entire blockchain will be redownloaded. These are important nuances from the source. Also, the period at the end of the translation is not present in the source, which uses one long sentence.

Correct translation:
Вам необхідно перебудувати базу даних за допомогою -reindex, щоб повернутися до непросіченого режиму. Це призведе до повторного завантаження всього блокчейну.
```

<!-- cache_translation_check_uk_db9376e13e7eb488cff19437e41ad791885f9cfd3b0de296320656d764b1d6e4 -->
```
        <source>Unexpected legacy entry in descriptor wallet found. Loading wallet %s

The wallet might have been tampered with or created with malicious intent.
</source>
        <translation>В дескрипторному гаманці виявлено неочікуваний запис, що не підтримується. Завантаження гаманця %s 

Гаманець міг бути підроблений або створений зі злим умислом.
</translation>
    
ERR
The translation adds "що не підтримується" ("that is not supported"), which is not present in the source and thus changes the meaning. Otherwise it's fine: %s is preserved and language is Ukrainian. Also avoid introducing extra unintended qualifiers.

Correct translation:
У дескрипторному гаманці виявлено несподіваний запис у форматі legacy. Завантаження гаманця %s

Гаманець міг бути підроблений або створений зі злим умислом.
```

<!-- cache_translation_check_uk_8c4b27d4c327ad6ebf427437b99cb7500d07b1b234757f0d8f018860d7402150 -->
```
        <source>-paytxfee is deprecated and will be fully removed in v31.0.</source>
        <translation>Опцію -paytxfee визнано застарілою, і її буде остаточно вилучено у версії v31.0</translation>
    
ERR
The Ukrainian translation is accurate in meaning but missing the final period from the source. Also a small stylistic tweak: "у версії v31.0." (with period) or "версії v31.0." is preferable.

Correct translation:
Опцію -paytxfee визнано застарілою, і її буде остаточно вилучено у версії v31.0.
```

<!-- cache_translation_check_uk_10b5887f9d3d15005c199ada1b09bd4bfa7a49d5e64b00cae48aa8bd5c5a910b -->
```
        <source>Copyright (C) %i-%i</source>
        <translation>Всі права збережено. %i-%i</translation>
    
ERR
The translation "Всі права збережено." means "All rights reserved." and omits the direct translation of "Copyright". Moreover, "Всі права збережено." is a less standard Ukrainian copyright notice. The correct approach should preserve the concept of "Copyright" and directly mirror the format specifiers.

Correct translation:
Авторське право (C) %i-%i
```

<!-- cache_translation_check_uk_b3c64131b6a10fe1e004090bd6c7a883c1e2010576d0cc6342f3fa4173cdf6c4 -->
```
        <source>Could not parse asmap file %s</source>
        <translation>Не вдалося проаналізувати asmap файл %s</translation>
    
ERR
Word order is awkward in Ukrainian. It should place "файл" before "asmap" (or hyphenate). Also "проаналізувати" is acceptable, but "розібрати" or "розпарсити" are alternatives.

Correct translation:
Не вдалося проаналізувати файл asmap %s
```

<!-- cache_translation_check_uk_b98e6e98180c7e3e7af9ec9aea7fedda9d628975affa33f0a6115dac2b166da3 -->
```
        <source>Could not top up scriptPubKeys</source>
        <translation>Не вдалося поповнити scriptPubKey</translation>
    
ERR
The translation changes the identifier from plural "scriptPubKeys" to singular "scriptPubKey". Also no format specifiers are present. Correct translation should preserve the original identifier and plurality:

Correct translation:
Не вдалося поповнити scriptPubKeys
```

<!-- cache_translation_check_uk_a14f58bf453e95204a72c7dc7c39d90a224135cfc752c08203c836a63b47039a -->
```
        <source>Error: This wallet is already a descriptor wallet</source>
        <translation>Помилка: Цей гаманець вже є дескрипторним</translation>
    
ERR
The translation ends with the adjective "дескрипторним" without a noun, making it grammatically incomplete/unnatural in Ukrainian.

Correct translation:
Помилка: цей гаманець уже є дескрипторним гаманцем.
```

<!-- cache_translation_check_uk_2fbac2e0b72dfa00a815a426a77a26421ef976b3635090fba467a521ae14c428 -->
```
        <source>Invalid port specified in %s: '%s'</source>
        <translation>Неприпустимий порт, указаний в %s: '%s'</translation>
    
ERR
The Ukrainian uses the Russian form "указаний". Also better to use Ukrainian preposition "у" before %s. Format specifiers and quoting are correct.

Correct translation:
Неприпустимий порт, вказаний у %s: '%s'
```

<!-- cache_translation_check_uk_6148681d07bffd4092bfba1dd624aea6cca53f2f18f151e60ac07f45b3739e8a -->
```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>Транзакція потребує адресу для решти, але неможливо створити таку адресу.</translation>
    
ERR
The Ukrainian is grammatically incorrect and awkward ("Транзакція потребує адресу..." is ungrammatical; word order and subject for "can't generate it" are unclear).

Correct translation:
Транзакції потрібна адреса для решти, але ми не можемо її згенерувати.
```

<!-- cache_translation_check_uk_27dc5288c42c15a439893174e7e91e15781f8b22a53aca727bab5e3165b2a3b6 -->
```
        <source>Transaction requires one destination of non-zero value, a non-zero feerate, or a pre-selected input</source>
        <translation>Транзакція вимагає хоча б одного призначення з ненульовою сумою, ненульової комісії або заздалегідь обраного входу.</translation>
    
ERR
The translation is mostly understandable Ukrainian but uses "комісії" (fee) which conveys fee amount rather than "feerate" (fee rate), and "призначення" is a bit vague in Bitcoin context (better to mention "призначення/адреса"). Also prefer "принаймні" over "хоча б" for style.

Corrected translation:
Транзакція потребує принаймні одного призначення з ненульовою сумою, ненульової ставки комісії або заздалегідь обраного входу.
```
</details>

Number of issues: 24.
