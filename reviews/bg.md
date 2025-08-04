# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>bg</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bbg%5D%20low%20quality)


```
        <source>Repeat new passphrase</source>
        <translation>Повтори парола</translation>
    
YES, The translation is problematic because it is incomplete and omits the word "new".
Correct translation: Повтори новата парола
```

```
        <source>Runaway exception</source>
        <translation>Изключи бягащите</translation>
    
YES, The translation is inaccurate. The correct translation of "Runaway exception" in the context of Bitcoin would be "Извънреден случай" or "Неконтролиран изключителен случай", but given the very literal translation of "runaway" as "бягащи" (running), it is highly unlikely that this is the intended meaning. The original translation "Изключи бягащите" translates to "Turn off the running ones", which is nonsensical in the given context.

NO
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>Възникна фатална грешка. Проверете че файла с настройки е редактируем или опирайте да стартирате без настройки.</translation>
    
YES: The translation uses an incorrect word for "writable". The correct word in Bulgarian is "записваем".

Възникна фатална грешка. Проверете дали файлът с настройки е записваем, или опитайте да стартирате без настройки.
```

```
        <source>Encrypt Wallet…</source>
        <translation>Крипритай уолет..</translation>
    
YES, The translation contains spelling errors. The word "Крипритай" should be "Криптирай" and "уолет" should be "портфейл".
Криптирай портфейл…
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>Шифроване на личните ключове,които принадлежат на портфейла Ви.</translation>
    
YES: The translation contains a superfluous comma after "ключове". The correct translation should be: "Шифроване на личните ключове, които принадлежат на портфейла Ви."
```

```
        <source>Processing blocks on disk…</source>
        <translation>Обработване на сектори от диска...</translation>
    
YES, The translation is inaccurate. The word "blocks" in the context of Bitcoin refers to a block of transactions, not disk sectors.

Correct translation: Обработване на блокове от диска...
```

```
        <source>List mode</source>
        <translation>списък Режим</translation>
    
YES, The word order is unnatural. The correct translation is "Режим на списък".
YES, The word order is unnatural. The correct translation is "Режим на списък".
```

```
        <source>Copy change</source>
        <translation>Промяна на копирането</translation>
    
YES, The translation is inaccurate and conveys a meaning completely different from the source text. "Промяна на копирането" literally translates to "copying change" or "change of copying", which does not make sense in the context of Bitcoin transactions. The correct translation should refer to copying the "change" amount of a transaction.

The correct translation is:
Copy change
```

```
        <source>Can vary +/- %1 satoshi(s) per input.</source>
        <translation>Може да варира с +/- %1 байт(а).</translation>
    
YES, the translation incorrectly uses "байт(а)" (bytes) instead of "сатоши(та)" (satoshis) in the context of Bitcoin.

Correct translation: Може да варира с +/- %1 сатоши(та).
```

```
        <source>Create wallet warning</source>
        <translation>Създайте предупредителен портфейл </translation>
    
YES, The translation is problematic. The Bulgarian translation "Създайте предупредителен портфейл" literally translates to "Create a warning wallet", which is not the intended meaning of "Create wallet warning". The intended meaning is a warning that appears when creating a wallet.

A more accurate translation would be:
"Предупреждение при създаване на портфейл"
```

```
        <source>Open wallet failed</source>
        <translation>Отварянето на уолет неупсешно</translation>
    
YES, erroneous content. The Bulgarian translation is grammatically incorrect.
Correct translation: Отварянето на портфейла е неуспешно.
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain. It is faster to download the full chain first and prune it later. Disables some advanced features.</source>
        <translation>Връщането на тази настройка изисква повторно изтегляне на цялата секторна верига. По-бързо е първо да изтеглите пълната верига и да я подрязвате по-късно. Деактивира някои разширени функции.</translation>
    
YES, The Bulgarian translation incorrectly translates "blockchain" as "секторна верига" (sector chain) instead of "блокчейн" (blockchain) or "верига от блокове" (chain of blocks).
Correct translation: Връщането на тази настройка изисква повторно изтегляне на целия блокчейн. По-бързо е първо да изтеглите пълната верига и да я подрязвате по-късно. Деактивира някои разширени функции.
```

```
        <source>Use a custom data directory:</source>
        <translation>Използване на директория ръчно</translation>
    
YES, The translation is not accurate. The phrase "Use a custom data directory" translates to "Използвайте директория за данни по избор" in Bulgarian. The provided translation "Използване на директория ръчно" means "Using a directory manually" which is not the same meaning.
Използвайте директория за данни по избор
```

```
        <source>Esc</source>
        <translation>избягай</translation>
    
YES, The translation is incorrect. "Esc" in the context of Bitcoin usually refers to the Escape key on a keyboard, which is used to cancel an operation or go back. The provided translation "избягай" means "escape" as in to flee or run away, which is not the intended meaning.

NO
```

```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>%1 в момента синхронизира. Той ще изтегля заглавия и блокове от рояка и ще ги утвърди, докато достигне върха на секторната верига.</translation>
    
YES, The translation uses inappropriate terminology, specifically "рояк" for "peers" and "секторна верига" for "block chain", which are not standard or understandable in the context of Bitcoin.

%1 в момента синхронизира. Той ще изтегля заглавия и блокове от партньори и ще ги валидира, докато достигне върха на блокчейна.
```

```
        <source>Number of script verification threads</source>
        <translation>Брой на скриптове и нишки за потвърждение</translation>
    
YES, The translation is inaccurate and implies that the threads are for both scripts and confirmation, whereas the original text clearly states that the threads are specifically for script verification. The word "нишки" (threads) is also misplaced.
The correct translation should be: "Брой нишки за проверка на скриптове"
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Показва дали предоставеният proxy по подразбиране Socks5 се използва за достигане до рояк чрез този тип мрежа.</translation>
    
YES, The word "ройк" in Bulgarian means "swarm" or "horde". In the context of Bitcoin, the correct translation for "peers" is "пиъри" or "възли".

The correct translation is:

Показва дали предоставеният proxy по подразбиране Socks5 се използва за достигане до пиъри чрез този тип мрежа.
```

```
        <source>Enable coin control features</source>
        <translation>Позволяване на монетите и техните възможности</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning. The original English text "Enable coin control features" refers to enabling functionalities that allow users to manage and select specific UTXOs (Unspent Transaction Outputs) for Bitcoin transactions. The provided Bulgarian translation "Позволяване на монетите и техните възможности" literally translates to "Allowing the coins and their capabilities," which is too general and doesn't capture the specific technical meaning of "coin control features" in the context of Bitcoin.

A more accurate translation would be:

"Активиране на функциите за контрол на монети"
```

```
        <source>Mined balance that has not yet matured</source>
        <translation>Миниран баланс,който все още не се е развил</translation>
    
YES, erroneous content. The translation is too literal and doesn't convey the intended meaning in the context of Bitcoin. "Развил" (developed) is not the correct term for a balance maturing.

Correct translation: Миниран баланс, който все още не е узрял
```

```
        <source>Request payment to %1</source>
        <translation>Изискване на плащане от %1</translation>
    
YES, The translation uses "от" (from) instead of "на" (to). This changes the meaning of the sentence to "Request payment from %1", while the original sentence means "Request payment to %1".

Correct translation: Изискване на плащане на %1
```

```
        <source>Send Coins</source>
        <translation>Изпращане</translation>
    
YES, The translation is too brief and does not convey the full meaning of the source text. The word "Изпращане" means "Sending" but lacks context. A more appropriate translation would be "Изпращане на монети".

        <source>Send Coins</source>
        <translation>Изпращане на монети</translation>
```

```
        <source>automatically selected</source>
        <translation>астоматично избран</translation>
    
YES, The translation is missing the letter "а" at the beginning.
Correct translation: автоматично избран
```

```
        <source>Copy change</source>
        <translation>Промяна на копирането</translation>
    
YES, The translation is inaccurate and conveys a meaning completely different from the source text. "Промяна на копирането" literally translates to "copying change" or "change of copying", which does not make sense in the context of Bitcoin transactions. The correct translation should refer to copying the "change" amount of a transaction.

The correct translation is:
Copy change
```

```
        <source>Confirm send coins</source>
        <translation>Потвърждаване</translation>
    
YES, The translation is too short and does not accurately convey the meaning of the source text. The source text "Confirm send coins" implies a confirmation of a transaction involving sending coins, not just a general confirmation.

The correct translation should be: "Потвърдете изпращането на монети"
```

```
        <source>The total exceeds your balance when the %1 transaction fee is included.</source>
        <translation>Сумата при добавяне на данък добавена стойност по %1 транзакцията надвишава сумата по вашата сметка.</translation>
    
YES, The translation incorrectly interprets "transaction fee" as "value-added tax" (данък добавена стойност). The correct translation for "transaction fee" is "такси за трансакцията".

Correct translation: Сумата при добавяне на такси за трансакцията по %1 транзакцията надвишава сумата по вашата сметка.
```

```
        <source>Paste address from clipboard</source>
        <translation>Вмъкни от клипборда</translation>
    
YES, The translation is missing a key word "address" which is crucial in the context of Bitcoin. The Bulgarian translation should also include the Bulgarian word for "address".
Correct translation: Вмъкни адрес от клипборда
```

```
        <source>Paste address from clipboard</source>
        <translation>Вмъкни от клипборда</translation>
    
YES, The translation is missing a key word "address" which is crucial in the context of Bitcoin. The Bulgarian translation should also include the Bulgarian word for "address".
Correct translation: Вмъкни адрес от клипборда
```

```
        <source>Sign the message to prove you own this Bitcoin address</source>
        <translation>Подпишете съобщение като доказателство, че притежавате определен адрес</translation>
    
YES, The translation is inaccurate. The Bulgarian translation uses "определен адрес" which means "a certain address". The original English text specifies "this Bitcoin address", implying ownership of a specific address. The translation fails to convey this specificity and also omits the crucial term "Bitcoin".

Correct translation: Подпишете съобщението, за да докажете, че притежавате този Bitcoin адрес
```

```
        <source>The signature did not match the message digest.</source>
        <translation>Подписът не отговаря на комбинацията от съобщение и адрес.</translation>
    
YES, The translation is inaccurate. The original English text refers to a "message digest", which is a cryptographic hash of a message. The Bulgarian translation incorrectly translates this as "combination of message and address".

The correct translation should be:
Подписът не отговаря на хеша на съобщението.
```

```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>включена в %1 блока</translation>
    
YES, The translation is incorrect. The source text means "%1 confirmations", while the translation means "%1 blocks". The correct translation should be "%1 потвърждения".
NO, YES, %1 потвърждения
```

```
        <source>Total credit</source>
        <translation>Общ дълг</translation>
    
YES, The translation is incorrect. "Total credit" in the context of Bitcoin usually refers to a positive balance or amount available, while "Общ дълг" translates to "Total debt". The correct translation for "Total credit" is "Общ кредит".
Общ кредит
```

```
        <source>Transaction ID</source>
        <translation>ID</translation>
    
YES, The translation is too brief and lacks context. The original text "Transaction ID" specifically refers to a transaction identifier in the context of Bitcoin. The translated text "ID" is too generic and could refer to any type of identifier.

Correct translation: ID на трансакцията
```

```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Неплатим (%1 потвърждения, ще бъде платим след %2)</translation>
    
YES, the translation is problematic. The Bulgarian word "Неплатим" translates to "unpayable" or "not payable," which is incorrect in this context. In Bitcoin, an immature transaction means it has not yet reached a sufficient number of confirmations to be considered spendable or final. The correct term should convey this idea of not being ready or available yet.

NO
```

```
        <source>Exporting Successful</source>
        <translation>Изнасянето е успешна</translation>
    
YES, the translation is grammatically incorrect. The noun "изнасянето" is neuter, but the adjective "успешна" is feminine. The correct translation would be "Изнасянето е успешно".
Изнасянето е успешно
```

```
        <source>Send Coins</source>
        <translation>Изпращане</translation>
    
YES, The translation is too brief and does not convey the full meaning of the source text. The word "Изпращане" means "Sending" but lacks context. A more appropriate translation would be "Изпращане на монети".

        <source>Send Coins</source>
        <translation>Изпращане на монети</translation>
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>Портфейлът няма да плаша по-малко от миналата такса за препредаване.</translation>
    
YES, erroneous content. The word "плаша" (plashta) should be "плаща" (plashta), which means "pay". Also, "мисли" (misli) should be "минималната" (minimalnata), meaning "minimum".

Correct translation: Портфейлът няма да плаща по-малко от минималната такса за препредаване.
```

```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>Коментар потребителски агент (%s) съдържа не безопасни знаци. </translation>
    
YES, The translation contains an extra space at the end of the sentence.
Коментар потребителски агент (%s) съдържа не безопасни знаци.
```
</details>
