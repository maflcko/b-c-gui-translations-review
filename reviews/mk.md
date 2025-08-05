# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>mk</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bmk%5D%20low%20quality)


```
        <source>Repeat new passphrase</source>
        <translation>Повтори ја лозинката</translation>
    
YES
The translation "Повтори ја лозинката" translates back as "Repeat the passphrase", but the source is "Repeat new passphrase", which specifically asks to repeat the *new* passphrase (i.e., not just any passphrase, but the one just entered as new). The translation is missing the "new" ("нова").

Correct translation:
Повтори ја новата лозинка
```

```
        <source>%1 didn't yet exit safely…</source>
        <translation>%1не излезе безбедно...</translation>
    
YES
There is a missing space between "%1" and "не", which creates an issue with readability and format. The ellipsis character in the translation is three dots ("...") instead of the ellipsis character ("…") used in the source.

Correct translation:
%1 не излезе безбедно…
```

```
        <source>Options…</source>
        <translation>Поставки...</translation>
    
YES
The translation of "Options…" as "Поставки..." is incorrect. The correct Macedonian word for "Options" in this context (application/software options or settings) is "Опции". Additionally, the ellipsis character should match the original style (the source uses the Unicode ellipsis “…” not three dots “...”); it is preferable to use the Unicode ellipsis for consistency.

Correct translation:
<translation>Опции…</translation>
```

```
        <source>Backup Wallet…</source>
        <translation>Сигурносен паричник...</translation>
    
YES
The translation "Сигурносен паричник..." is incorrect for several reasons:
1. "Сигурносен паричник" translates to "Secure wallet", which does not convey the meaning of "Backup Wallet".
2. The ellipsis in the source uses a single Unicode character (…), but the translation uses three dots (...). Consistency is preferable.
3. The correct translation for "Backup Wallet" in Macedonian should convey the meaning of "Make a backup of the wallet".

Correct translation:
Резервна копија на паричникот…
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Потврдување на пораките за да се знае дека се напишани со дадените биткоин-адреси.</translation>
    
YES
The translation is inaccurate. The source says "ensure they were signed with specified Bitcoin addresses," but the translation uses "се напишани" ("were written"), which changes the meaning. Also, it uses the noun "Потврдување" instead of an imperative or infinitive.

Correct translation:
Потврдете пораки за да се осигурате дека се потпишани со одредените Биткоин-адреси.
```

```
        <source>Restore Wallet…</source>
        <extracomment>Name of the menu item that restores wallet from a backup file.</extracomment>
        <translation>Обнови паричник...</translation>
    
YES
The Macedonian word "Обнови" means "Update" or "Renew," not "Restore." The correct word for "Restore" is "Врати" or "Врати од резервна копија". Also, the ellipsis should use the proper Unicode character (…).

Correct translation:
Врати паричник…
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Исклучи ја мрежната активност</translation>
    
YES
The translation is incorrect. The source text is "Show Peers tab", which means to display the "Peers" tab in a user interface. The provided translation "Исклучи ја мрежната активност" means "Disable network activity", which is unrelated.

Correct translation:
Прикажи ја јазичето „Рамноправни“
```

```
        <source>After Fee:</source>
        <translation>После Провизија:</translation>
    
YES
The translation is problematic. In Macedonian, the word "Провизија" is generally used for "commission," but in the Bitcoin context (transaction fees), "такса" is the more accurate and commonly used term. Also, "Провизија" is capitalized incorrectly; it should be in lowercase after the preposition.

Correct translation:
После такса:
```

```
        <source>List mode</source>
        <translation>список Режим</translation>
    
YES
The translation improperly orders the words. In Macedonian, the correct term is "Режим на список" or "Списочен режим".

Correct translation:
Режим на список
```

```
        <source>Edit Address</source>
        <translation>Измени Адреса</translation>
    
YES
The translation "Измени Адреса" is problematic. In Macedonian, "Адреса" is singular, but the definite article is used ("Адресата" would be "the address"). The English "Edit Address" does not use the definite article. Also, in menu/UI context, Macedonian typically does not use definite articles, and capitalization of both words is not standard in UI.

Correct translation:
Измени адреса
```

```
        <source>After Fee:</source>
        <translation>После Провизија:</translation>
    
YES
The translation is problematic. In Macedonian, the word "Провизија" is generally used for "commission," but in the Bitcoin context (transaction fees), "такса" is the more accurate and commonly used term. Also, "Провизија" is capitalized incorrectly; it should be in lowercase after the preposition.

Correct translation:
После такса:
```
</details>
