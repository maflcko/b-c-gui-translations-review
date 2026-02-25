# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>mk</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bmk%5D%20request)


<!-- cache_translation_check_mk_91cd0797e940472692099e9ae67520ab785abb97f8bdb57baf131c14a543bac5 -->
```
        <source>&amp;New</source>
        <translation>Нова</translation>
    
ERR
The translation omits the ampersand (&), which is necessary to indicate the keyboard shortcut and should be present exactly once in the translation.

Correct translation:
&Нова
```

<!-- cache_translation_check_mk_11d5cb638d3bcda14a00013e4da7e211b6913da57c3b034a8b5fc4b64ba26ef9 -->
```
        <source>&amp;Copy</source>
        <translation>Копирај</translation>
    
ERR
The translation omits the '&' which denotes the keyboard shortcut. In menus, '&' should be kept in the translation (placed before the mnemonic letter).

Correct translation:
&Копирај
```

<!-- cache_translation_check_mk_8e0eafe66cd7ba9d6be708998b81364167b60aee56785115f5d556443e391c9a -->
```
        <source>C&amp;lose</source>
        <translation>Затвори</translation>
    
ERR
The translation omits the ampersand (&), which designates the shortcut key. It should be present in the translation as it is in the source.

Correct translation:
&Затвори
or
Затвори (&Z)
(placing & before a shortcut letter in Macedonian, e.g., З, matching standard practice)
```

<!-- cache_translation_check_mk_6b8e8a1a0624b9162cbbfae581de3e2d6104ba029a1ec44a9f28965cdd5ee896 -->
```
        <source>&amp;Export</source>
        <translation>Извези</translation>
    
ERR
The translation omits the ampersand (&) which indicates a shortcut key in the menu. It should appear somewhere in the translated string.

Correct translation:
&Извези

or

Извези &

(but usually at the start: &Извези)
```

<!-- cache_translation_check_mk_8fecb02b60d402e6015df0e4f49cba5cc7fffe23c4157395e03239cef60a832f -->
```
        <source>&amp;Delete</source>
        <translation>Избриши</translation>
    
ERR
The translation omits the ampersand (&), which denotes the shortcut key in the UI. It must be present exactly once, as in the source.

Correct translation:
&Избриши
or
Из&бриши
(but & must be present exactly once, anywhere in the word)
```

<!-- cache_translation_check_mk_2bc77e0a53c1422639fca6cf542f035394bef3d39b362d7bbe817805907e9c64 -->
```
        <source>C&amp;hoose</source>
        <translation>Избери</translation>
    
ERR
The translation omits the ampersand (&) which is used to denote a keyboard shortcut. In the Macedonian translation, the ampersand should be included to indicate the shortcut, ideally placed before a suitable letter.

Correct translation:
&Избери

Or, if a different letter should be used as a shortcut:
И&збери
```

<!-- cache_translation_check_mk_060a4bdd95b6a659b2fcea70c8782f9a601dd733ba020e59a6bfb678f2920d33 -->
```
        <source>Copy &amp;Label</source>
        <translation>Копирај етикета</translation>
    
ERR
The ampersand (&) indicating the shortcut key is missing in the Macedonian translation. It should appear exactly once, attached to the shortcut letter. A correct translation would be:

Копирај &Етикета
or
&Копирај етикета

Either placement is acceptable as long as the "&" is present.
```

<!-- cache_translation_check_mk_fabfc490c77558fe1cf0f04c517453561f1057539704b5fed957e070a188df2c -->
```
        <source>Repeat new passphrase</source>
        <translation>Повтори ја лозинката</translation>
    
ERR
The translation "Повтори ја лозинката" means "Repeat the passphrase." However, the source specifies "Repeat new passphrase," indicating that it is specifically the new passphrase (not just any passphrase) that should be repeated, often used in scenarios for entering a new password twice for confirmation.

Correct translation:
Повтори ја новата лозинка
```

<!-- cache_translation_check_mk_729d90d7959f6e8afaaede71b2f86aeddd2241116f45d555d960348ea0351d6a -->
```
        <source>%1 didn't yet exit safely…</source>
        <translation>%1не излезе безбедно...</translation>
    
ERR
There is a missing space between '%1' and 'не' in the translation. The ellipsis character '…' in the source is used as three periods '...' in the translation, which is inconsistent but acceptable in usage. It would be more precise to use the ellipsis character.

Correct translation:
%1 не излезе безбедно…
```

<!-- cache_translation_check_mk_59e16d775c67d0254fd7696debdd1b22dd85e095ccb875811c335fbea6c753af -->
```
        <source>&amp;Overview</source>
        <translation>Преглед</translation>
    
ERR
The shortcut marker '&' is missing in the Macedonian translation. It should appear exactly once, as in the source, to indicate the menu shortcut.

Correct translation:
&Преглед
or
Пр&еглед
(both are acceptable as long as only one '&' is present and marks a shortcut letter)
```

<!-- cache_translation_check_mk_4633fe224ba5b561096e30691941b59c44ca4ec8a3acd499e2905c996c2f3608 -->
```
        <source>&amp;Transactions</source>
        <translation>Трансакции</translation>
    
ERR
The shortcut indicator '&' is missing in the Macedonian translation, though it is present in the source. The translation should preserve the '&' for keyboard shortcuts.

Correct translation:
&Трансакции
or
Т&рансакции (if another shortcut key is preferred, but must match interface convention)
```

<!-- cache_translation_check_mk_6678ffc596465040be9c33b34a817a7ea8473752c48895bfb0fc444998b59739 -->
```
        <source>E&amp;xit</source>
        <translation>Излез</translation>
    
ERR
The translation does not preserve the '&' from the source, which is used to indicate a shortcut key in menu items. The translated 'Излез' should contain '&' (e.g., '&Излез') to provide the expected menu shortcut.

Correct translation:
&Излез
```

<!-- cache_translation_check_mk_5f54671df6080aed79e76464307cbd6abdd59554acfa447570f209137370b2ae -->
```
        <source>About &amp;Qt</source>
        <translation>За Qt</translation>
    
ERR
The translation omits the ampersand (&), which designates a shortcut key in menus. It should be preserved as in the source. 

Correct translation:
За &Qt
```

<!-- cache_translation_check_mk_e14b8b0afc89d626c544529051e86f843c8f7044cd44f09fc407586f9e845c04 -->
```
        <source>&amp;Send</source>
        <translation>Испрати</translation>
    
ERR
The translation omits the '&' which is used for setting a keyboard shortcut in menus. The translated text should also contain a single '&' at an appropriate position (usually corresponding as closely as possible to the English, and preferably before a shortcut-relevant letter; in Macedonian, '&' is "Испрати" as the word, so a common placement would be '&Испрати').

Correct translation:
&Испрати
```

<!-- cache_translation_check_mk_338d734493399d0d40907e788ac419eafcc5862eaa5c5771af57cfeb0cb02dfb -->
```
        <source>&amp;Receive</source>
        <translation>Прими</translation>
    
ERR
The ampersand (&) which is used to indicate the shortcut key in menu items is missing in the Macedonian translation. It should exist exactly once in the translation.

Correct translation:
&Прими
or
Пр&ими
```

<!-- cache_translation_check_mk_0cc350a185fe145f90f6fe8b029fb9aab075ee1f1648bf3ec5069843ca562dfd -->
```
        <source>&amp;Options…</source>
        <translation>Поставки...</translation>
    
ERR
The translation "Поставки..." means "supplies" in Macedonian, which is incorrect for "Options." Also, the ampersand (&) indicating a shortcut key is missing.

Correct translation:
&Опции...
```

<!-- cache_translation_check_mk_efdc411a2345b6325b79e4691307bf6abec931cfed386998111be2267ee7503d -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>Сигурносен паричник...</translation>
    
ERR
The translation omits the '&' character, which is used for indicating a keyboard shortcut in the UI. Also, "Сигурносен паричник..." translates as "Secure wallet..." which is inaccurate; the source means "Backup Wallet", i.e., to make a backup (verb), not to describe it as secure.

Correct translation:
&Резервна копија на паричник...
or
&Бекап на паричник...
```

<!-- cache_translation_check_mk_d1202e9e5b4e66da11422cb2496cb7b41b2429d9bcedf28a0ff8eb529f355828 -->
```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Потврдување на пораките за да се знае дека се напишани со дадените биткоин-адреси.</translation>
    
ERR
The translation is inaccurate. The original English says "Verify messages to ensure they were signed with specified Bitcoin addresses", but the translation says "Потврдување на пораките за да се знае дека се напишани со дадените биткоин-адреси", which translates back as "Confirmation of the messages to know that they were written with the given Bitcoin addresses". The phrase "were signed" is important in the context of Bitcoin, and "напишани" (written) is incorrect.

Correct translation:
Потврдете ги пораките за да се осигурате дека се потпишани со одредени биткоин-адреси.
```

<!-- cache_translation_check_mk_68689943d7a36ca4a343453b7207cc01f32258cf44e24a3c56f674a872c48c69 -->
```
        <source>Restore Wallet…</source>
        <extracomment>Name of the menu item that restores wallet from a backup file.</extracomment>
        <translation>Обнови паричник...</translation>
    
ERR
The translation "Обнови паричник..." means "Update wallet..." or "Refresh wallet...", not "Restore Wallet…". The correct translation for "Restore Wallet…" should convey the idea of restoring from a backup rather than updating.

Correct translation:
Врати паричник од резервна копија...
or
Врати паричник...
```

<!-- cache_translation_check_mk_b2085978f151e881f0f833c4b4d4e45fbd995afd801d5ed4153bb7959adc61b6 -->
```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Исклучи ја мрежната активност</translation>
    
ERR
The translation is incorrect. The source says "Show Peers tab", but the translation says "Исклучи ја мрежната активност", which means "Disable the network activity". This does not convey the original meaning.

Correct translation:
Прикажи ја јазичето за врски
```

<!-- cache_translation_check_mk_770cf3386e8496214d3e56f38f27dd03cae2744a161647eca85f820beaf53b21 -->
```
        <source>After Fee:</source>
        <translation>После Провизија:</translation>
    
ERR
The Macedonian translation incorrectly capitalizes 'Провизија' (Fee), which should not be capitalized in this context. Also, stylistically, the phrase "После такса:" or "По одбивање на такса:" is more natural in Macedonian for financial contexts.

Correct translation:
По одбивање на такса:
```

<!-- cache_translation_check_mk_4cec818613cb2a94bd586a6a51102f9d0ff5ccc8a8060ce5b7c82e9d47db96a4 -->
```
        <source>List mode</source>
        <translation>список Режим</translation>
    
ERR
The translation is grammatically incorrect. In Macedonian, the correct phrase would be "Режим на список" or "Режим на прикажување во список".

Correct translation:
Режим на список
```

<!-- cache_translation_check_mk_56ce800a173e6af1fa394a5449a65da1ad977fa78895feda406231215c1bcb23 -->
```
        <source>Edit Address</source>
        <translation>Измени Адреса</translation>
    
ERR
The translation uses "Адреса" which is plural ("addresses") in Macedonian, but the source "Edit Address" is singular. Also, the correct form should be "Адреса" (with the definite article if context demands, e.g., "Адресата" for "the address"), but for command-like UI options, addressing the noun in indefinite singular is preferred.

Correct translation:
Измени адреса
```

<!-- cache_translation_check_mk_770cf3386e8496214d3e56f38f27dd03cae2744a161647eca85f820beaf53b21 -->
```
        <source>After Fee:</source>
        <translation>После Провизија:</translation>
    
ERR
The Macedonian translation incorrectly capitalizes 'Провизија' (Fee), which should not be capitalized in this context. Also, stylistically, the phrase "После такса:" or "По одбивање на такса:" is more natural in Macedonian for financial contexts.

Correct translation:
По одбивање на такса:
```

<!-- cache_translation_check_mk_6b8e8a1a0624b9162cbbfae581de3e2d6104ba029a1ec44a9f28965cdd5ee896 -->
```
        <source>&amp;Export</source>
        <translation>Извези</translation>
    
ERR
The translation omits the ampersand (&) which indicates a shortcut key in the menu. It should appear somewhere in the translated string.

Correct translation:
&Извези

or

Извези &

(but usually at the start: &Извези)
```
</details>

Number of issues: 25.
