# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>bg</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bbg%5D%20low%20quality)


```
        <source>Repeat new passphrase</source>
        <translation>Повтори парола</translation>
    
YES  
The translation "Повтори парола" means "Repeat the password," which is less precise than the source phrase "Repeat new passphrase." In the context of Bitcoin and security, "passphrase" is better translated as "парола" but with the qualifier "нова" to reflect "new." Also, the imperative form is acceptable, but to be more formal and aligned with the original, it can be "Повтори новата парола" (Repeat the new passphrase) or simply "Повтори новата парола" to be explicit.

Correct translation:  
Повтори новата парола
```

```
        <source>Runaway exception</source>
        <translation>Изключи бягащите</translation>
    
YES  
The translation "Изключи бягащите" is incorrect and misleading. It means "Turn off the runaways" or "Exclude the runaways," which does not correspond to the English meaning of "Runaway exception." The phrase "Runaway exception" refers to an exception (error) that is unhandled or occurring uncontrollably, often translated as "необработено изключение" or "извънконтролно изключение" in Bulgarian.  

Correct translation:  
"Извънконтролно изключение"  
or  
"Необработено изключение"
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>Възникна фатална грешка. Проверете че файла с настройки е редактируем или опирайте да стартирате без настройки.</translation>
    
YES
The Bulgarian translation has some issues:
1. "файла с настройки" should be "файлът с настройки" for correct article usage.
2. "редактируем" is a calque from Russian; the correct Bulgarian term is "записваем" or "с възможност за запис".
3. "опирайте" is incorrect; the verb should be "опитайте".
4. Missing a comma after "Проверете".
5. The phrase "без настройки" is slightly ambiguous; better to say "с опцията -nosettings" or "с параметър -nosettings" to reflect the command line argument in the source.

Correct translation:
"Възникна фатална грешка. Проверете, че файлът с настройки е записваем, или опитайте да стартирате с -nosettings."
```

```
        <source>Encrypt Wallet…</source>
        <translation>Крипритай уолет..</translation>
    
YES  
The translation contains multiple issues:  
1. The word "Encrypt" is incorrectly translated as "Крипритай" which is not a correct Bulgarian word. The correct verb for "Encrypt" would be "Криптирай".  
2. "Wallet" is transliterated as "уолет" which is incorrect. The correct translation for "wallet" in the Bitcoin context is "портфейл".  
3. The ellipsis "…" is distorted as two dots ".." instead of one Unicode ellipsis character.  

Correct translation:  
Криптирай портфейл…
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>Шифроване на личните ключове,които принадлежат на портфейла Ви.</translation>
    
YES  
The translation has minor spacing and spelling issues. There should be a space after the comma, and the correct verb form is "принадлежат" (should be "принадлежат" but in Bulgarian the correct form is "принадлежат" or better is "принадлежат" → actually the verb should be "принадлежат" is not appropriate here; the correct verb in Bulgarian is "принадлежат," but it's not the standard word. More natural would be "които принадлежат на портфейла ви" (with lowercase "ви" as per Bulgarian etiquette unless formal context, which is acceptable here). 

Also, Bulgarian typically uses the noun "шифроване" for "encryption," but the English phrase is imperative, and the Bulgarian phrase appears to be a noun phrase, so it's better to use the verb form "Шифроване" doesn't fully match the imperative command tone. A more natural imperative translation would be: "Шифровайте частните ключове, които принадлежат на вашия портфейл."

Corrected translation:  
Шифровайте частните ключове, които принадлежат на вашия портфейл.
```

```
        <source>Processing blocks on disk…</source>
        <translation>Обработване на сектори от диска...</translation>
    
YES  
The translation "Обработване на сектори от диска..." is inaccurate. The English word "blocks" in the Bitcoin context refers to blockchain blocks, not sectors on a disk. The correct Bulgarian term should reflect "blocks" as blockchain data units, not disk sectors. Also, the ellipsis is represented differently ("…") in the source and translated text ("..."). It's better to keep the ellipsis consistent.

Correct translation:  
Обработка на блокове на диска…
```

```
        <source>List mode</source>
        <translation>списък Режим</translation>
    
YES  
The word order and capitalization are problematic. In Bulgarian, the adjective should precede the noun, and "Режим" should not be capitalized here. The correct translation is:  
списъчен режим
```

```
        <source>Copy change</source>
        <translation>Промяна на копирането</translation>
    
YES  
The translation "Промяна на копирането" literally means "Change of copying," which is incorrect in this Bitcoin context. The source phrase "Copy change" refers to copying the "change" amount (e.g., Bitcoin transaction change), not changing the copy itself. A correct and clearer Bulgarian translation would be:  
"Копирай ресто"  
where "ресто" is the correct term for "change" in a financial/Bitcoin context.
```

```
        <source>Can vary +/- %1 satoshi(s) per input.</source>
        <translation>Може да варира с +/- %1 байт(а).</translation>
    
YES  
The translation incorrectly uses "байт(а)" (byte(s)) instead of "сатоши" which is the correct term for the smallest Bitcoin unit. Also, the structure is slightly off; it should closely match the English meaning and preserve the "+/- %1" pattern.

Correct translation:  
Може да варира с +/- %1 сатоши на вход.
```

```
        <source>Create wallet warning</source>
        <translation>Създайте предупредителен портфейл </translation>
    
YES  
The translation "Създайте предупредителен портфейл" incorrectly suggests an imperative "Create a warning wallet," which distorts the meaning. The original English phrase "Create wallet warning" is a noun phrase likely meaning "Warning about creating a wallet" or "Create wallet: warning."

A better translation would be:  
"Предупреждение при създаване на портфейл"
```

```
        <source>Open wallet failed</source>
        <translation>Отварянето на уолет неупсешно</translation>
    
YES  
The translation contains a typo: "уолет" should be "портфейл" (wallet) and "неупсешно" should be "неуспешно" (unsuccessful).

Correct translation:  
Отварянето на портфейл неуспешно
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain. It is faster to download the full chain first and prune it later. Disables some advanced features.</source>
        <translation>Връщането на тази настройка изисква повторно изтегляне на цялата секторна верига. По-бързо е първо да изтеглите пълната верига и да я подрязвате по-късно. Деактивира някои разширени функции.</translation>
    
YES
The term "секторна верига" is incorrect; the correct translation for "blockchain" in the Bitcoin context is "блокчейн" or "блокчейн верига." Additionally, "подрязвате" (plural/formal you) should be consistent with the rest of the sentence, better replaced with the infinitive form to match the style.

Correct translation:
Връщането на тази настройка изисква повторно изтегляне на целия блокчейн. По-бързо е първо да изтеглите пълния блокчейн и да го подрежете по-късно. Деактивира някои разширени функции.
```

```
        <source>Use a custom data directory:</source>
        <translation>Използване на директория ръчно</translation>
    
YES  
The translation "Използване на директория ръчно" is awkward and inaccurate. It literally means "Using a directory manually," which does not convey the meaning of "Use a custom data directory:" properly. A better translation would indicate explicitly the use of a user-defined or custom data directory.

Correct translation:  
"Използвайте потребителска директория за данни:"
```

```
        <source>Esc</source>
        <translation>избягай</translation>
    
YES  
The translation "избягай" means "escape" in the sense of "to avoid" or "to run away," which is incorrect in this context. The source "Esc" refers to the Escape key on the keyboard, which in Bulgarian is typically translated as "Esc" or "Еск" (transliteration of "Esc"). It is preferable to keep "Esc" untranslated or use the established abbreviation.

Correct translation:  
<translation>Esc</translation>
```

```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>%1 в момента синхронизира. Той ще изтегля заглавия и блокове от рояка и ще ги утвърди, докато достигне върха на секторната верига.</translation>
    
YES  
The translation has a few issues:  
- "в момента синхронизира" is understandable but could be more naturally phrased as "в момента се синхронизира".  
- "Той" (He) is less appropriate for %1 (which could be a program or a service); the neutral form "то" or restructuring the sentence to avoid pronouns is better.  
- "рояк" literally means a "swarm" (usually of insects), which is incorrect here; the proper translation for "peers" in this Bitcoin/network context is "връстници" or "възли".  
- "утвърди" means "confirm" or "establish" in a general sense but is not the best verb for "validate" in the blockchain context. A better term is "потвърди" (confirmed), or "провери/валидира" (validate).  
- "върха на секторната верига" is a mistranslation of "tip of the block chain". "Секторната верига" is incorrect; the correct term is "веригата с блокове" or just "блокчейна". "Върха" is acceptable for "tip". Better: "докато достигне върха на блокчейна".  

Corrected translation:  
%1 в момента се синхронизира. Ще изтегля заглавия и блокове от връстници и ще ги валидира, докато достигне върха на блокчейна.
```

```
        <source>Number of script verification threads</source>
        <translation>Брой на скриптове и нишки за потвърждение</translation>
    
YES  
The translation adds the word "и" ("and") which is not present in the source and changes the meaning. The original phrase refers to the "number of script verification threads," implying the count of threads used for script verification, not a count of both scripts and threads.

Correct translation:  
Брой нишки за проверка на скриптове
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Показва дали предоставеният proxy по подразбиране Socks5 се използва за достигане до рояк чрез този тип мрежа.</translation>
    
YES  
The translation has some issues:  
1. "proxy" should be transliterated consistently or translated as "прокси".  
2. "SOCKS5" should be all uppercase as in the source.  
3. "рояк" is an incorrect translation for "peers" in this context; a better word in Bulgarian for network peers is "връзки" or "участието в мрежата" or simply "връстници".  
4. The phrase "предоставеният proxy по подразбиране Socks5" is awkward and inconsistent with casing.  
5. The original source word order and meaning should be preserved more accurately.

Correct translation:  
Показва дали подаденият по подразбиране SOCKS5 прокси се използва за връзка с връстници през този тип мрежа.
```

```
        <source>Enable coin control features</source>
        <translation>Позволяване на монетите и техните възможности</translation>
    
YES  
The translation is inaccurate and misleading. The source means "Enable coin control features," i.e., activate the features for controlling coins. The provided translation says "Allowing coins and their features," which changes the meaning.

Correct translation:  
"Активиране на функциите за контрол на монети"
```

```
        <source>Mined balance that has not yet matured</source>
        <translation>Миниран баланс,който все още не се е развил</translation>
    
YES  
There is a punctuation spacing issue ("баланс,който" should be "баланс, който") and the phrase "не се е развил" ("has not yet matured") is not the correct terminology in Bulgarian Bitcoin context. The correct translation for "has not yet matured" in this context is "не е узрял" or "не е завършен". The best phrase would be:

Миниран баланс, който все още не е узрял
```

```
        <source>Request payment to %1</source>
        <translation>Изискване на плащане от %1</translation>
    
YES  
The preposition "от" in Bulgarian means "from," which changes the meaning of the phrase. The English source implies requesting a payment to the address %1, so the correct preposition should be "към" (to).  

Correct translation:  
Изискване на плащане към %1
```

```
        <source>automatically selected</source>
        <translation>астоматично избран</translation>
    
YES  
The Bulgarian translation contains a typographical error: "астоматично" should be "автоматично".  

Correct translation:  
автоматично избран
```

```
        <source>Copy change</source>
        <translation>Промяна на копирането</translation>
    
YES  
The translation "Промяна на копирането" literally means "Change of copying," which is incorrect in this Bitcoin context. The source phrase "Copy change" refers to copying the "change" amount (e.g., Bitcoin transaction change), not changing the copy itself. A correct and clearer Bulgarian translation would be:  
"Копирай ресто"  
where "ресто" is the correct term for "change" in a financial/Bitcoin context.
```

```
        <source>Confirm send coins</source>
        <translation>Потвърждаване</translation>
    
YES  
The translation "Потвърждаване" means "Confirmation" or "Confirming" in general and does not fully convey the imperative "Confirm send coins," which is a request to confirm the action of sending coins. A more accurate translation would be:  
"Потвърдете изпращането на монети"
```

```
        <source>The total exceeds your balance when the %1 transaction fee is included.</source>
        <translation>Сумата при добавяне на данък добавена стойност по %1 транзакцията надвишава сумата по вашата сметка.</translation>
    
YES  
The translation introduces the term "данък добавена стойност" (value added tax), which is incorrect in this Bitcoin context. The original sentence refers to the "%1 transaction fee," meaning a fee for processing the transaction, not a tax like VAT. Also, the phrasing is somewhat awkward and does not clearly convey the intended meaning.

A more accurate translation would be:  
"Общата сума надвишава вашия баланс, когато се включи таксата за транзакция %1."
```

```
        <source>Paste address from clipboard</source>
        <translation>Вмъкни от клипборда</translation>
    
YES  
The translation "Вмъкни от клипборда" means "Insert from the clipboard" but does not include the word "address," which is present in the source text. The correct and more accurate translation should convey "Paste address from clipboard."

Correct translation:  
Вмъкни адрес от клипборда
```

```
        <source>Paste address from clipboard</source>
        <translation>Вмъкни от клипборда</translation>
    
YES  
The translation "Вмъкни от клипборда" means "Insert from the clipboard" but does not include the word "address," which is present in the source text. The correct and more accurate translation should convey "Paste address from clipboard."

Correct translation:  
Вмъкни адрес от клипборда
```

```
        <source>Sign the message to prove you own this Bitcoin address</source>
        <translation>Подпишете съобщение като доказателство, че притежавате определен адрес</translation>
    
YES  
The translation is incomplete and somewhat vague. It omits the reference to "this Bitcoin address" ("този Bitcoin адрес"), which is important to keep the context clear and precise. The phrase "определен адрес" ("a certain address") is less specific than "this Bitcoin address." Also, "Подпишете съобщение като доказателство" is a bit awkward; a better, more natural phrasing involves "Подпишете съобщението, за да докажете, че притежавате този Bitcoin адрес."

Correct translation:  
Подпишете съобщението, за да докажете, че притежавате този Bitcoin адрес.
```

```
        <source>The signature did not match the message digest.</source>
        <translation>Подписът не отговаря на комбинацията от съобщение и адрес.</translation>
    
YES
The translation introduces erroneous content by adding "и адрес" ("and address"), which is not present in the source and changes the meaning. The source only refers to "the message digest," without mentioning an "address."

Correct translation:
Подписът не съответства на дайджеста на съобщението.
```

```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>включена в %1 блока</translation>
    
YES  
The translation "включена в %1 блока" means "included in %1 blocks," which is not an exact equivalent of "%1 confirmations." Moreover, the source phrase uses "%1" before "confirmations," implying the number of confirmations, which is a count of how many blocks have confirmed a transaction. A better translation is the plural form for "confirmations" adjusted for the number %1.

Correct translation:  
"%1 потвърждения"
```

```
        <source>Total credit</source>
        <translation>Общ дълг</translation>
    
YES  
The translation "Общ дълг" is incorrect because it means "Total debt" rather than "Total credit." The correct translation for "Total credit" in Bulgarian, especially in the context of Bitcoin or financial transactions, would be "Общ кредит."  

Correct translation:  
Общ кредит
```

```
        <source>Transaction ID</source>
        <translation>ID</translation>
    
YES  
The translation "ID" is incomplete and not fully accurate. The source "Transaction ID" refers specifically to the identifier of a transaction, which should be clearly conveyed in Bulgarian. The correct translation is:  
"Идентификатор на транзакцията"  
or a shorter but still clear form:  
"ID на транзакцията"
```

```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Неплатим (%1 потвърждения, ще бъде платим след %2)</translation>
    
YES  
The translation is incorrect in meaning. The English phrase "Immature" in the context of Bitcoin means that the coins or transaction outputs are not yet spendable (not yet mature). The translation "Неплатим" means "not payable," which is close in idea but not the standard term used in Bulgarian Bitcoin terminology. The original "will be available after %2" indicates it will become spendable (mature) after a certain number of confirmations. The phrase "ще бъде платим след %2" means "will be payable after %2", which is misleading because "платим" relates more to payments, not maturity of outputs.

A better, context-appropriate translation would use "Незрял" for "Immature", which is the typical term for immature/unconfirmed outputs in Bitcoin in Bulgarian, and replace "ще бъде платим" with "ще бъде достъпен" (will become available) or "ще бъде зрел" (will be mature) to better capture the meaning.

Correct translation:  
Незрял (%1 потвърждения, ще бъде достъпен след %2)
```

```
        <source>Exporting Successful</source>
        <translation>Изнасянето е успешна</translation>
    
YES  
The Bulgarian translation has a gender agreement error. The noun "Изнасянето" (The exporting) is neuter, so the adjective/participle should also be neuter: "успешно" instead of the feminine "успешна".

Correct translation:  
Изнасянето е успешно
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>Портфейлът няма да плаша по-малко от миналата такса за препредаване.</translation>
    
YES  
The Bulgarian translation contains a typo and an incorrect word choice. The word "плаша" means "to scare," which is incorrect here; it should be "плаща" (to pay). Also, "миналата" means "the last" or "past," which is wrong; it should be "минималната" (minimum).  

Correct translation:  
Портфейлът няма да плаща по-малко от минималната такса за препредаване.
```

```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>Коментар потребителски агент (%s) съдържа не безопасни знаци. </translation>
    
YES  
The Bulgarian translation is mostly understandable but contains a spacing issue and slightly unnatural phrasing. The phrase "не безопасни" should be combined into one word "небезопасни", and there is an extra trailing space before the closing tag. Also, "потребителски агент" would be better rendered as "потребителски агент" or the phrase could be rearranged for naturalness. A better translation is:

Коментарът на User Agent (%s) съдържа небезопасни знаци.
```
</details>
