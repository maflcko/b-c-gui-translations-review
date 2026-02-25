# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Buk%5D%20request)



<details><summary>uk</summary>


<!-- cache_translation_check_uk_34da7fd6bcd6baafb8ccca6b702f6be8472c470252a71d50fed13e9ad1b38a7a -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>Змінити парол&amp;ь…</translation>
    
ERR
The ampersand `&`, used to indicate a keyboard shortcut (mnemonic), is placed before the soft sign 'ь'. The soft sign is a diacritical mark and cannot be used as a shortcut key. The ampersand should be placed before a letter that can be activated with the 'Alt' key.

Correct translation:
&Змінити пароль…
```

<!-- cache_translation_check_uk_8922de2c20dd920c03c255bd587af5592e806faef74d7251aa94f473aa5d5ce0 -->
```
        <source>&amp;Main</source>
        <translation>&amp;Основні</translation>
    
ERR
The translation "Основні" is the plural form, while the source "Main" is singular. A singular form should be used. A better translation would be "Головна" (implying a main page/tab) or "Основне".

Correct translation:
&amp;Головна
```

<!-- cache_translation_check_uk_e2cf48cba3a3c7ae68e22e2a06e9c19123871fe19207c2caed2ab6c5a0036f8b -->
```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>Адрес пропущено</translation>
    
ERR
The translation "Адрес пропущено" is grammatically incorrect and does not accurately convey the meaning of "Addresses Rate-Limited". "Адрес" is singular, while the source is plural. Furthermore, it doesn't clearly indicate that the addresses were dropped specifically due to rate-limiting.

Correct translation:
Обмеження частоти адрес
```

<!-- cache_translation_check_uk_5da597924656e70c495330db8f16dcf2337a85a0acaa157ad99d0e4513c332d0 -->
```
        <source>The entered address is invalid.</source>
        <translation>Введена адреса не співпадає.</translation>
    
ERR
The Ukrainian translation is inaccurate. "Не співпадає" means "does not match" or "is not the same," whereas the source word "invalid" should be translated as "недійсна" or "неправильна" in this context.

Correct translation:
Введена адреса недійсна.
```

<!-- cache_translation_check_uk_5f2e5407ab33f7e7cf4faab20ad3b56dced70e48fb7e89f50cb0fdc2fd80f7b0 -->
```
        <source>The entered address does not refer to a legacy (P2PKH) key. Message signing for SegWit and other non-P2PKH address types is not supported in this version of %1. Please check the address and try again.</source>
        <translation>Введена адреса не відноситься до застарілого (P2PKH) ключа. Підписання повідомлень для SegWit та інших типів адрес, відмінних від P2PKH, не підтримується в цій версії . Будь ласка, перевірте адресу і спробуйте ще раз.</translation>
    
ERR
The format specifier '%1' is missing in the translation. In the source text, it refers to the application name (e.g., Bitcoin Core), and it must be included in the translation to maintain context and technical correctness.

Correct translation:
Введена адреса не відноситься до застарілого (P2PKH) ключа. Підписання повідомлень для SegWit та інших типів адрес, відмінних від P2PKH, не підтримується в цій версії %1. Будь ласка, перевірте адресу і спробуйте ще раз.
```

<!-- cache_translation_check_uk_d3b3a5b3041d22af59fc9d5996028d1776145dfe622ed697fd25751619cb0d6b -->
```
        <source>This pane shows a detailed description of the transaction</source>
        <translation>Даний діалог показує детальну статистику по вибраній транзакції</translation>
    
ERR
The translation is inaccurate. The word 'description' is translated as 'статистику' (statistics) instead of 'опис' (description). Also, 'This pane' is translated as 'Даний діалог' (This dialog), while 'панель' or 'вікно' would be more appropriate for 'pane'.

Correct translation:
Ця панель показує детальний опис транзакції
```

<!-- cache_translation_check_uk_6e1248cff4386c2513c43fc435d83ff61585994b58c9382aa3fe07d1d14ffb40 -->
```
        <source>Copy &amp;raw transaction</source>
        <translation>Копіювати &amp;всю транзакцію</translation>
    
ERR
The translation of "raw transaction" as "всю транзакцію" (the whole transaction) is inaccurate. The term "raw" in this context refers to the unprocessed, serialized data of the transaction, not just its completeness. The current translation loses this important technical nuance. A more accurate translation would be "необроблена транзакція" (unprocessed transaction) or "сира транзакція" (literal translation of "raw transaction").

Correct translation:
Копіювати &необроблену транзакцію
```

<!-- cache_translation_check_uk_79ee7f13a3f2bab239e1d5e2e18b3c9522181efe25c386c57053e30fba671809 -->
```
        <source>%s request to listen on port %u. This port is considered "bad" and thus it is unlikely that any peer will connect to it. See doc/p2p-bad-ports.md for details and a full list.</source>
        <translation>%s прохання прослухати на порту %u . Цей порт вважається «поганим» і тому навряд чи до нього підключиться який-небудь бенкет. Перегляньте doc/p2p-bad-ports.md для отримання детальної інформації та повного списку.</translation>
    
ERR
The translation contains a serious mistranslation ("бенкет" meaning "banquet/feast" instead of "peer") and a whitespace issue (an extra space before the period after %u).

The word "peer" in a networking context should be translated as "вузол" (node) or "пір" (peer), but definitely not "бенкет".

Correct translation:
%s запит на прослуховування порту %u. Цей порт вважається «поганим», тому малоймовірно, що будь-який вузол підключиться до нього. Деталі та повний список див. у doc/p2p-bad-ports.md.
```
</details>

Number of issues: 8.
