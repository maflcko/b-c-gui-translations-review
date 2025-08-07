# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>uk</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Buk%5D%20low%20quality)


```
        <source>Create a new address</source>
        <translation>Додати нову адрессу</translation>
    
YES
There is a spelling error in the Ukrainian word for "address" ("адрессу" should be "адресу"). Also, "Додати" means "Add", but "Create" is better translated as "Створити".

Correct translation:
Створити нову адресу
```

```
        <source>Network addresses that your Bitcoin node is currently using to communicate with other nodes.</source>
        <translation>Мережеві адреси, які ваша біткоїн-вузол використовує для зв'язку з іншими вузлами</translation>
    
YES
There is a grammatical error in the translation: "ваша біткоїн-вузол" is incorrect, as "вузол" is masculine and should match the possessive pronoun "ваш", not "ваша". There is also a missing period at the end of the sentence, as in the original.

Correct translation:
Мережеві адреси, які ваш біткоїн-вузол наразі використовує для зв'язку з іншими вузлами.
```

```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>Адрес пропущено</translation>
    
YES
The translation is inaccurate. The English source refers to "Addresses Rate-Limited," which implies multiple addresses and a state where address processing is being limited by rate. The translation "Адрес пропущено" means "Address skipped" or "Address omitted," is singular, and does not correctly convey the meaning of "rate-limited" or plurality.

Correct translation:
Адреси з обмеженням частоти
```

```
        <source>An optional message that is attached to the payment request and may be displayed to the sender.</source>
        <translation>Необов’язкове повідомлення, яке додається до запиту на оплату і може відображати відправника.</translation>
    
YES
The translation incorrectly says that the message "може відображати відправника" ("may display the sender"), but the English source says "may be displayed to the sender". The recipient attaches a message that may be shown to the sender, not that displays the sender.

Correct translation:
Необов’язкове повідомлення, яке додається до запиту на оплату і може бути показане відправнику.
```

```
        <source>Custom:</source>
        <translation>Змінено:</translation>
    
YES
The translation is inaccurate. The English term "Custom:" refers to something user-defined or customizable, while "Змінено:" means "Changed:" in Ukrainian, which is not equivalent. The correct translation should be:

Custom: → Власне:
or
Custom: → Користувацьке:
or, depending on context,
Custom: → Власний:
```

```
        <source>The entered address is invalid.</source>
        <translation>Введена адреса не співпадає.</translation>
    
YES
The translation is inaccurate. "Введена адреса не співпадає." means "The entered address does not match," which is not the same as "is invalid." The correct translation should convey that the address is NOT valid.

Correct translation:
Введена адреса є недійсною.
```

```
        <source>This pane shows a detailed description of the transaction</source>
        <translation>Даний діалог показує детальну статистику по вибраній транзакції</translation>
    
YES  
The translation does not accurately reflect the source. The source says "This pane shows a detailed description of the transaction," but the translation says "This dialog shows detailed statistics for the selected transaction." This is a significant change of meaning: "statistics" vs. "description", "pane" vs. "dialog", and "the transaction" vs "the selected transaction".

Correct translation:
Ця панель відображає детальний опис транзакції
```

```
        <source>Rename of '%s' -&gt; '%s' failed. You should resolve this by manually moving or deleting the invalid snapshot directory %s, otherwise you will encounter the same error again on the next startup.</source>
        <translation>Не вдалося перейменувати '%s' -&gt; '%s'. Слід вирішити це, перемістивши або видаливши неправильний каталог знімків %sвручну, інакше ця помилка станеться при наступному запуску.</translation>
    
YES
There is a small whitespace formatting issue: "%sвручну" should have a space after "%s" ("каталог знімків %s вручну"). Additionally, while the translation retains the meaning and structure, using "слід вирішити це" is a bit awkward stylistically; "Вам слід вирішити це" or "Ви повинні вирішити це" would sound more natural, but this isn't a major problem.

Correct translation:
Не вдалося перейменувати '%s' -&gt; '%s'. Слід вирішити це, перемістивши або видаливши неправильний каталог знімків %s вручну, інакше ця помилка станеться при наступному запуску.
```

```
        <source>You need to rebuild the database using -reindex to go back to unpruned mode.  This will redownload the entire blockchain</source>
        <translation>Вам необхідно перебудувати базу даних з використанням -reindex для завантаження повного блокчейну.</translation>
    
YES  
The translation omits the explanation that this action is needed to return to "unpruned mode" and that the entire blockchain will be redownloaded. These are important nuances from the source. Also, the period at the end of the translation is not present in the source, which uses one long sentence.

Correct translation:
Вам необхідно перебудувати базу даних за допомогою -reindex, щоб повернутися до непросіченого режиму. Це призведе до повторного завантаження всього блокчейну.
```

```
        <source>Copyright (C) %i-%i</source>
        <translation>Всі права збережено. %i-%i</translation>
    
YES
The translation "Всі права збережено." means "All rights reserved." and omits the direct translation of "Copyright". Moreover, "Всі права збережено." is a less standard Ukrainian copyright notice. The correct approach should preserve the concept of "Copyright" and directly mirror the format specifiers.

Correct translation:
Авторське право (C) %i-%i
```

```
        <source>Invalid port specified in %s: '%s'</source>
        <translation>Неприпустимий порт, указаний в %s : '%s'</translation>
    
YES
There is a formatting issue: there should be no space before the colon. In Ukrainian, the translation is otherwise accurate.

Correct translation:
Неприпустимий порт, указаний в %s: '%s'
```
</details>

Number of issues: 11.
