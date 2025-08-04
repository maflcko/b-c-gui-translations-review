# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>be</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bbe%5D%20low%20quality)


```
        <source>Exporting Failed</source>
        <translation>Экспартаванне няўдалае</translation>
    
YES, The Belarusian translation "Экспартаванне няўдалае" is a literal and awkward translation of "Exporting Failed". While understandable, it's not natural-sounding Belarusian. A more idiomatic translation would be "Не атрымалася экспартаваць" (It was not possible to export) or "Памылка экспартавання" (Exporting error).

Correct translation: Памылка экспартавання
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>Гэтая аперацыя патрабуе кодавую фразу, каб рзблакаваць гаманец.</translation>
    
YES: The Belarusian translation contains a typo ("рзблакаваць" should be "разблакаваць").
NO
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Падпісаць паведамленне з дапамогай Біткойн-адраса каб даказаць, што яно належыць вам</translation>
    
YES, The translation is inaccurate and potentially misleading. The original English sentence implies signing *multiple* messages with *multiple* Bitcoin addresses to prove ownership of *all* of them. The Belarusian translation, however, suggests signing *one* message with *one* Bitcoin address to prove ownership of *that message* (which doesn't make sense in the context of proving address ownership).

Correct translation: Падпісвайце паведамленні вашымі Біткойн-адрасамі, каб даказаць, што яны належаць вам.
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Спраўдзіць паведамленне з дапамогай Біткойн-адраса каб даказаць, што яно належыць вам</translation>
    
YES - The translation is inaccurate and does not convey the meaning of the source text. The source text is about verifying messages using Bitcoin addresses, while the translation suggests using a Bitcoin address to prove ownership of a message. The translation also misses the plural "addresses" from the source.
The correct translation should be: "Verify messages to ensure they were signed with specified Bitcoin addresses"
Correct translation: "Праверце паведамленні, каб пераканацца, што яны былі падпісаны з указаных біткойн-адрасоў"
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>Запатрабаваць плацёж (генеруецца QR-код для біткойн URI)</translation>
    
YES - The translation is grammatically incorrect and missing the plural form of "QR codes" and the singular form of "Bitcoin URIs". Additionally, the phrase "bitcoin: URIs" is not translated correctly. The correct translation should be "Запытваць плацяжы (стварае QR-коды і біткойн: URI)".
```

```
        <source>%1 behind</source>
        <translation>%1 таму</translation>
    
YES, The translation is problematic. The Belarusian translation "%1 таму" does not accurately convey the meaning of "%1 behind" in the context of Bitcoin. In Bitcoin, "behind" typically refers to the number of confirmations a transaction has received, meaning it's still waiting to be fully processed. "%1 таму" translates to "%1 ago" which is related to time, not confirmation status. A more appropriate translation would be related to confirmations or blocks.

Correct translation: %1 пацверджанняў
```

```
        <source>Transactions after this will not yet be visible.</source>
        <translation>Транзакцыи пасля гэтай не будуць бачныя.</translation>
    
YES: The Belarusian translation uses an archaic spelling of "Transactions" ("Транзакцыи" instead of the modern "Транзакцыі"). Also, the word order feels slightly unnatural. A more natural translation would be "Транзакцыі пасля гэтай яшчэ не будуць бачныя."
NO: Транзакцыі пасля гэтай яшчэ не будуць бачныя.
```

```
        <source>Sent transaction</source>
        <translation>Дасланыя транзакцыі</translation>
    
YES: The translation is plural ("transactions") while the source is singular ("transaction").
The correct translation should be "Дасланая транзакцыя".
```

```
        <source>Incoming transaction</source>
        <translation>Прынятыя транзакцыі</translation>
    
YES - The translation is incorrect and does not convey the meaning of "Incoming transaction". The Belarusian phrase "Прынятыя транзакцыі" translates to "Accepted transactions".
The correct translation for "Incoming transaction" would be "Уваходная транзакцыя".
```

```
        <source>Received with label</source>
        <translation>Прыняць праз метку</translation>
    
YES, The translation is not accurate for the context of Bitcoin. "Received with label" in Bitcoin usually means that an amount was received and associated with a specific label or tag in a wallet. The provided translation "Прыняць праз метку" means "Accept via label," which is not the correct meaning. A more accurate translation would be "Атрымана з пазнакай".
Атрымана з пазнакай
```

```
        <source>Copy after fee</source>
        <translation>Капіяваць з выняткам камісіі</translation>
    
YES, The translation is problematic. The word "Copy" is translated as "Капіяваць", which means "to copy", but the phrase "Copy after fee" implies copying the amount *excluding* the fee. The translation "Капіяваць з выняткам камісіі" literally means "Copy with the exclusion of the fee". A more accurate translation would be "Капіяваць без камісіі" which means "Copy without the fee".

NO
```

```
        <source>Directory already exists. Add %1 if you intend to create a new directory here.</source>
        <translation>Каталог ужо існуе. Дадайце %1 калі вы збіраецеся стварыць тут новы каталог.</translation>
    
YES, The translation is problematic as it translates "Add %1" to "Дадайце %1" which is not a suitable translation in this context. The meaning of "add" here is to append something to the directory name or path, not to add an item. The correct translation should reflect this.

NO, Каталог ужо існуе. Дадайце %1, калі вы збіраецеся стварыць тут новы каталог.
```

```
        <source>Copy after fee</source>
        <translation>Капіяваць з выняткам камісіі</translation>
    
YES, The translation is problematic. The word "Copy" is translated as "Капіяваць", which means "to copy", but the phrase "Copy after fee" implies copying the amount *excluding* the fee. The translation "Капіяваць з выняткам камісіі" literally means "Copy with the exclusion of the fee". A more accurate translation would be "Капіяваць без камісіі" which means "Copy without the fee".

NO
```

```
        <source>Transaction ID</source>
        <translation>ID</translation>
    
YES: The translation is too brief and does not accurately convey the meaning of "Transaction ID". The correct translation should include the word "transaction".

Correct translation: Transaction ID
```

```
        <source>Confirmed (%1 confirmations)</source>
        <translation>Пацверджана (%1 пацверджанняў)</translation>
    
YES. The translation uses an incorrect grammatical form for "confirmations". It should be the genitive plural.

Correct translation: Пацверджана (%1 пацверджання)
```

```
        <source>Exporting Failed</source>
        <translation>Экспартаванне няўдалае</translation>
    
YES, The Belarusian translation "Экспартаванне няўдалае" is a literal and awkward translation of "Exporting Failed". While understandable, it's not natural-sounding Belarusian. A more idiomatic translation would be "Не атрымалася экспартаваць" (It was not possible to export) or "Памылка экспартавання" (Exporting error).

Correct translation: Памылка экспартавання
```

```
        <source>Error initializing wallet database environment %s!</source>
        <translation>Памалка ініцыялізацыі асяроддзя базы звестак гаманца %s!</translation>
    
YES, The Belarusian word for "Error" is spelled incorrectly. The correct spelling is "Памылка".
 Памылка ініцыялізацыі асяроддзя базы звестак гаманца %s!
```
</details>
