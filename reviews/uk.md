# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>uk</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Buk%5D%20low%20quality)


```
        <source>Create a new address</source>
        <translation>Додати нову адрессу</translation>
    
YES  
The word "адрессу" is misspelled. The correct Ukrainian word for "address" is "адресу" (with one "с"). Also, "Create a new address" is better translated as "Створити нову адресу" because "Додати" means "Add," which is not exactly the same as "Create" in this context.

Correct translation:  
Створити нову адресу
```

```
        <source>Network addresses that your Bitcoin node is currently using to communicate with other nodes.</source>
        <translation>Мережеві адреси, які ваша біткоїн-вузол використовує для зв'язку з іншими вузлами</translation>
    
YES  
The noun "вузол" (node) is masculine, so the possessive pronoun should be "ваш" instead of feminine "ваша". Additionally, the translation misses the word "currently" ("наразі" or "в даний момент") to correspond to "currently using". Also, a period at the end is missing.  

Correct translation:  
Мережеві адреси, які ваш біткоїн-вузол наразі використовує для зв’язку з іншими вузлами.
```

```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>Адрес пропущено</translation>
    
YES
The translation "Адрес пропущено" means "Address skipped," which does not convey the meaning of "Addresses Rate-Limited." The source text indicates that addresses have been rate-limited (i.e., limited in processing due to rate control), which is not the same as being simply skipped. Also, the source mentions multiple addresses ("Addresses"), so the noun should be plural.

Correct translation:
Обмеження швидкості для адрес
```

```
        <source>An optional message that is attached to the payment request and may be displayed to the sender.</source>
        <translation>Необов’язкове повідомлення, яке додається до запиту на оплату і може відображати відправника.</translation>
    
YES  
The translation incorrectly uses "може відображати відправника" which means "may display the sender" (as an action that affects the sender), but the source means the message "may be displayed to the sender." The correct phrasing should reflect that the message is shown to the sender.

Correct translation:  
Необов’язкове повідомлення, яке додається до запиту на оплату і може відображатися відправнику.
```

```
        <source>Custom:</source>
        <translation>Змінено:</translation>
    
YES  
The English word "Custom:" is usually translated as "Користувацький:" in Ukrainian, meaning something made or set by the user or customized. The provided translation "Змінено:" means "Changed:" or "Modified:", which does not correctly convey the meaning of "Custom:".  

Correct translation:  
Користувацький:
```

```
        <source>The entered address is invalid.</source>
        <translation>Введена адреса не співпадає.</translation>
    
YES  
The translation is not accurate. The source sentence means "The entered address is invalid." but the Ukrainian translation "Введена адреса не співпадає." literally means "The entered address does not match," which changes the meaning and is incorrect in this context.

Correct translation:  
Введена адреса недійсна.
```

```
        <source>This pane shows a detailed description of the transaction</source>
        <translation>Даний діалог показує детальну статистику по вибраній транзакції</translation>
    
YES  
The translation adds information not present in the source: "this pane" is translated as "Даний діалог" ("this dialog"), which is a slightly different UI element and may mislead users. Also, "детальну статистику" ("detailed statistics") is not the same as "detailed description". A more accurate translation would preserve the meaning of a detailed description rather than statistics, and keep the reference to "pane" rather than "dialog".

Correct translation:  
Ця панель показує детальний опис транзакції
```

```
        <source>Rename of '%s' -&gt; '%s' failed. You should resolve this by manually moving or deleting the invalid snapshot directory %s, otherwise you will encounter the same error again on the next startup.</source>
        <translation>Не вдалося перейменувати '%s' -&gt; '%s'. Слід вирішити це, перемістивши або видаливши неправильний каталог знімків %sвручну, інакше ця помилка станеться при наступному запуску.</translation>
    
YES  
There is a spacing issue before "вручну" in the translation. It should be separated by a space from the previous word "%s".  

Correct translation:  
Не вдалося перейменувати '%s' -&gt; '%s'. Слід вирішити це, перемістивши або видаливши неправильний каталог знімків %s вручну, інакше ця помилка станеться при наступному запуску.
```

```
        <source>You need to rebuild the database using -reindex to go back to unpruned mode.  This will redownload the entire blockchain</source>
        <translation>Вам необхідно перебудувати базу даних з використанням -reindex для завантаження повного блокчейну.</translation>
    
YES  
The translation is incomplete and changes the meaning. The original message states that rebuilding the database with -reindex is required to return to unpruned mode and that this will redownload the entire blockchain. The translation only mentions rebuilding the database using -reindex to download the full blockchain, omitting that it is necessary to go back to unpruned mode and that the entire blockchain will be redownloaded.

A better translation would be:  
Вам потрібно перебудувати базу даних, використовуючи -reindex, щоб повернутися до неприбраного режиму. Це призведе до повторного завантаження всього блокчейну.
```

```
        <source>Copyright (C) %i-%i</source>
        <translation>Всі права збережено. %i-%i</translation>
    
YES  
The translation changes the meaning incorrectly. The source text is "Copyright (C) %i-%i", which is a copyright notice including format specifiers for years, and should be translated to keep this meaning clearly. The provided translation "Всі права збережено. %i-%i" means "All rights reserved. %i-%i", which is a different phrase.

Correct translation:  
Copyright (C) %i-%i  
translates as:  
«Авторські права (C) %i-%i»  
or simply keeping the original phrase but localized:  
«Авторські права (C) %i-%i»  

If you want to include "All rights reserved" (which the source does not have), it should be separate, but here we must keep the original meaning.

Hence the correct translation is:  
<translation>Авторські права (C) %i-%i</translation>
```

```
        <source>Invalid port specified in %s: '%s'</source>
        <translation>Неприпустимий порт, указаний в %s : '%s'</translation>
    
YES  
There is an extra space before the colon in the translation, which is incorrect in Ukrainian punctuation. The colon should follow immediately after %s without a space.

Correct translation:  
Неприпустимий порт, указаний в %s: '%s'
```
</details>
