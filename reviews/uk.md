# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>uk</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Buk%5D%20request)


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

<!-- cache_translation_check_uk_6e1248cff4386c2513c43fc435d83ff61585994b58c9382aa3fe07d1d14ffb40 -->
```
        <source>Copy &amp;raw transaction</source>
        <translation>Копіювати &amp;всю транзакцію</translation>
    
ERR
The translation of "raw transaction" as "всю транзакцію" (the whole transaction) is inaccurate. The term "raw" in this context refers to the unprocessed, serialized data of the transaction, not just its completeness. The current translation loses this important technical nuance. A more accurate translation would be "необроблена транзакція" (unprocessed transaction) or "сира транзакція" (literal translation of "raw transaction").

Correct translation:
Копіювати &необроблену транзакцію
```
</details>

Number of issues: 3.
