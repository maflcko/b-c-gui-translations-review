# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>uk</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Buk%5D%20low%20quality)


```
        <source>Create a new address</source>
        <translation>Додати нову адрессу</translation>
    
YES: The translation uses a word "адресссу" which is a misspelling of "адресу". The correct translation should be "Створити нову адресу".
Створити нову адресу
```

```
        <source>calculating…</source>
        <translation>підраховується…</translation>
    
UNK_LANG
```

```
        <source>Whether to show coin control features or not.</source>
        <translation>Показати або сховати керування входами.</translation>
    
YES
The translation is inaccurate and does not reflect the original meaning. The English phrase "coin control features" refers to the ability to select specific inputs (UTXOs) for a Bitcoin transaction, not the general management of inputs.

Correct translation: Чи показувати функції керування монетами.
```

```
        <source>Network addresses that your Bitcoin node is currently using to communicate with other nodes.</source>
        <translation>Мережеві адреси, які ваша біткоїн-вузол використовує для зв'язку з іншими вузлами</translation>
    
YES, The translation contains a grammatical error. The phrase "ваша біткоїн-вузол" should be "ваш біткоїн-вузол" to agree in gender with "вузол" (node), which is masculine.
Мережеві адреси, які ваш біткоїн-вузол використовує для зв'язку з іншими вузлами.
```

```
        <source>Addresses Processed</source>
        <extracomment>Text title for the Addresses Processed field in the peer details area, which displays the total number of addresses received from this peer that were processed (excludes addresses that were dropped due to rate-limiting).</extracomment>
        <translation>Адрес оброблено</translation>
    
YES, The translation is grammatically incorrect and the word "оброблено" should be in plural form to match "Addresses".
Correct translation: Адреси оброблено
```

```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>Адрес пропущено</translation>
    
YES: The Ukrainian translation "Адрес пропущено" means "Address skipped" or "Address missed", which is not an accurate translation of "Addresses Rate-Limited". The "Rate-Limited" part is missing and the plural "Addresses" is translated as singular "Address". The correct translation should convey the idea of addresses being limited by rate.
Correct translation: Обмеження частоти адрес
```

```
        <source>An optional message that is attached to the payment request and may be displayed to the sender.</source>
        <translation>Необов’язкове повідомлення, яке додається до запиту на оплату і може відображати відправника.</translation>
    
YES - The translation incorrectly states that the message may be displayed *to* the sender, instead of *by* the sender.

Correct translation: Необов’язкове повідомлення, яке додається до запиту на оплату і може відображатися відправником.
```

```
        <source>Custom:</source>
        <translation>Змінено:</translation>
    
YES
The Ukrainian translation uses "Змінено:" which means "Changed:". This is a mistranslation of "Custom:".

Correct translation:
<translation>Власне:</translation>
```

```
        <source>The entered address is invalid.</source>
        <translation>Введена адреса не співпадає.</translation>
    
YES, the translation is inaccurate. The Ukrainian word "співпадає" means "matches" or "coincides", which is not the correct meaning for "invalid". The correct translation for "invalid" in this context would be "недійсна" (nevidna).

NO
```

```
        <source>This pane shows a detailed description of the transaction</source>
        <translation>Даний діалог показує детальну статистику по вибраній транзакції</translation>
    
YES - The translation incorrectly uses "діалог" (dialogue) and "статистику" (statistics) when the original text refers to a "pane" and "description". A more accurate translation would be "Ця панель показує детальний опис транзакції".
        <source>This pane shows a detailed description of the transaction</source>
        <translation>Ця панель показує детальний опис транзакції</translation>
```

```
        <source>Rename of '%s' -&gt; '%s' failed. You should resolve this by manually moving or deleting the invalid snapshot directory %s, otherwise you will encounter the same error again on the next startup.</source>
        <translation>Не вдалося перейменувати '%s' -&gt; '%s'. Слід вирішити це, перемістивши або видаливши неправильний каталог знімків %sвручну, інакше ця помилка станеться при наступному запуску.</translation>
    
YES. The Ukrainian translation contains a grammatical error. The word "вручну" (manually) is misplaced and should precede the verbs it modifies.

NO
```

```
        <source>You need to rebuild the database using -reindex to go back to unpruned mode.  This will redownload the entire blockchain</source>
        <translation>Вам необхідно перебудувати базу даних з використанням -reindex для завантаження повного блокчейну.</translation>
    
YES, The translation is inaccurate. It omits the crucial detail that rebuilding the database with -reindex is necessary to "go back to unpruned mode." Instead, it simply states it's for "downloading the full blockchain," which is a consequence, not the primary reason in this context.

Correct translation: Вам необхідно перебудувати базу даних з використанням -reindex, щоб повернутися до нестислого режиму. Це завантажить весь блокчейн.
```

```
        <source>Copyright (C) %i-%i</source>
        <translation>Всі права збережено. %i-%i</translation>
    
YES. The translation is inaccurate and misleading. It translates "Copyright (C) %i-%i" to "All rights reserved. %i-%i", which completely changes the meaning. The correct translation should reflect the copyright information.

NO.
```

```
        <source>Invalid port specified in %s: '%s'</source>
        <translation>Неприпустимий порт, указаний в %s : '%s'</translation>
    
YES: The translation uses the Russian word "указаний" instead of the Ukrainian word "вказаний".
The correct translation is: Неприпустимий порт, вказаний в %s: '%s'
```
</details>
