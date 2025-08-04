# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>mn</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bmn%5D%20low%20quality)


```
        <source>Copy the currently selected address to the system clipboard</source>
        <translation>Одоогоор сонгогдсон байгаа хаягуудыг сануулах</translation>
    
YES, The translation is inaccurate and does not convey the original meaning. The original text instructs the user to copy an address to the system clipboard, while the translation says "Remember the currently selected addresses", which is a different action.

Correct translation: Одоогоор сонгогдсон хаягийг системийн санах төхөөрөмж рүү хуулах
```

```
        <source>Choose the address to send coins to</source>
        <translation>Зооснуудыг илгээх хаягийг сонгоно уу</translation>
    
YES: The translation is inaccurate. "Зооснуудыг илгээх хаягийг сонгоно уу" translates to "Choose the address to send animals to", which is not the intended meaning. The correct translation should refer to sending coins.
NO
```

```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>Эдгээр Биткойн хаягууд нь илгээх хаягууд. Хүлээн авах хаяг болон тоо хэмжээг илгээхээсээ өмнө сайн нягталж үзэж байна уу</translation>
    
YES: The Mongolian translation omits the meaning of "sending payments". The phrase "Эдгээр Биткойн хаягууд нь илгээх хаягууд" translates to "These Bitcoin addresses are sending addresses", which is grammatically awkward and incomplete.
Correct translation: Эдгээр нь төлбөр илгээх Биткойн хаягууд юм. Зоос илгээхээсээ өмнө гүйлгээний хэмжээ болон хүлээн авах хаягаа үргэлж шалгаж байгаарай.
```

```
        <source>Sending addresses - %1</source>
        <translation>хаягуудииг Илгээж байна - %1</translation>
    
YES, The word "хаягуудииг" is plural and in accusative case, which is not suitable for the context. The correct translation should be "хаяг - %1".
хаяг - %1
```

```
        <source>Wallet passphrase was successfully changed.</source>
        <translation>Түрүйвчийн нууц үг амжилттай ѳѳр</translation>
    
YES, The translation is incomplete. The Mongolian phrase is missing the verb "боллоо" which means "became" or "is".
Түрүйвчийн нууц үг амжилттай ѳѳр боллоо.
```

```
        <source>N/A</source>
        <translation>Алга Байна</translation>
    
YES
The Mongolian translation "Алга Байна" means "Going Away" or "Disappeared". This is not an appropriate translation for "N/A" in the context of Bitcoin. "N/A" typically signifies "Not Available" or "Not Applicable".

A more accurate translation for "N/A" in Mongolian would be:

- **Боломжгүй** (Bolomjgüi) - meaning "Not possible" or "Unavailable"
- **Хэрэглэх боломжгүй** (Kherglekh bolomjgüi) - meaning "Not usable" or "Not applicable"
- **Оюунгүй** (Oyuungüi) - meaning "Not available" (less common, but can be used)

For the specific context of Bitcoin, where "N/A" might indicate data that isn't present or applicable, "Боломжгүй" is likely the most fitting.

Correct translation: Боломжгүй
```

```
        <source>Send</source>
        <translation>Илгээх
 </translation>
    
YES, the translation has an extraneous space character at the end.
Илгээх
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Түрүйвч &lt;b&gt;цоожтой&lt;/b&gt; ба одоогоор цоож &lt;b&gt;онгорхой&lt;/b&gt; байна</translation>
    
YES - The Mongolian translation incorrectly states that the wallet is locked and the lock is open, which is a contradiction. It should reflect that the wallet is encrypted and unlocked.

Correct translation: Түрүйвч &lt;b&gt;нууцлагдсан&lt;/b&gt; ба одоогоор &lt;b&gt;тайлагдсан&lt;/b&gt; байна
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Түрүйвч &lt;b&gt;цоожтой&lt;/b&gt; ба одоогоор цоож &lt;b&gt;хаалттай&lt;/b&gt; байна</translation>
    
YES, The Mongolian translation is problematic because it uses the word "Түрүйвч" which means "wallet" in Mongolian, however, it is redundant with the word "цоож" which also means "lock" in Mongolian. The corrected translation is: "Хэтэвч &lt;b&gt;цоожилсон&lt;/b&gt; бөгөөд одоогоор &lt;b&gt;хүлээн авагч&lt;/b&gt; байна".
```

```
        <source>Copy change</source>
        <translation>Ѳѳрчлѳлтийг санах</translation>
    
YES. The translation is inaccurate and does not convey the meaning of "Copy change" in the context of Bitcoin. The Mongolian translation seems to mean "Remember the change" or "Memorize the change," which is not the intended action of copying a value.

The correct translation for "Copy change" in a Bitcoin context would be:

<translation>Өөрчлөлтийг хуулах</translation>
```

```
        <source>(change)</source>
        <translation>(ѳѳрчлѳх)</translation>
    
YES - The translation of "change" as "ѳѳрчлѳх" is incorrect in the context of Bitcoin transactions. In Bitcoin, "change" refers to the unspent output returned to the sender. A more accurate translation would be "(хаягдал)" or "(буцаалт)".
(хаягдал)
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Копидсон хаягийг буулгах</translation>
    
YES, The translation is inaccurate. The Mongolian word "Копидсон" means "copied" but it should be "Clipboard". Also, the word "хаягийг" means "address" but it should be "address from". The word "буулгах" means "paste" but it should be "paste address". The correct translation should be "Clipboard-оос хаяг буулгах".
Clipboard-оос хаяг буулгах
```

```
        <source>Client restart required to activate changes.</source>
        <extracomment>Text explaining that the settings changed will not come into effect until the client is restarted.</extracomment>
        <translation>Ѳѳрчлѳлтүүдийг идэвхижүүлхийн тулд клиентийг ахин эхлүүлэх шаардлагтай</translation>
    
YES, The translation uses archaic Cyrillic characters ("Ѳ") which are not standard in modern Mongolian. The correct characters should be "Ө".
Өөрчлөлтүүдийг идэвхижүүлэхийн тулд клиентийг ахин эхлүүлэх шаардлагатай.
```

```
        <source>This change would require a client restart.</source>
        <translation>Энэ ѳѳрчлѳлтийг оруулахын тулд кли1нт програмыг ахин эхлүүлэх шаардлагтай</translation>
    
YES, The translation contains an error in the word "кли1нт" which should be "клиент".
Энэ ѳѳрчлѳлтийг оруулахын тулд клиент програмыг ахин эхлүүлэх шаардлагатай.
```

```
        <source>N/A</source>
        <translation>Алга Байна</translation>
    
YES
The Mongolian translation "Алга Байна" means "Going Away" or "Disappeared". This is not an appropriate translation for "N/A" in the context of Bitcoin. "N/A" typically signifies "Not Available" or "Not Applicable".

A more accurate translation for "N/A" in Mongolian would be:

- **Боломжгүй** (Bolomjgüi) - meaning "Not possible" or "Unavailable"
- **Хэрэглэх боломжгүй** (Kherglekh bolomjgüi) - meaning "Not usable" or "Not applicable"
- **Оюунгүй** (Oyuungüi) - meaning "Not available" (less common, but can be used)

For the specific context of Bitcoin, where "N/A" might indicate data that isn't present or applicable, "Боломжгүй" is likely the most fitting.

Correct translation: Боломжгүй
```

```
        <source>Copy change</source>
        <translation>Ѳѳрчлѳлтийг санах</translation>
    
YES. The translation is inaccurate and does not convey the meaning of "Copy change" in the context of Bitcoin. The Mongolian translation seems to mean "Remember the change" or "Memorize the change," which is not the intended action of copying a value.

The correct translation for "Copy change" in a Bitcoin context would be:

<translation>Өөрчлөлтийг хуулах</translation>
```

```
        <source>Paste address from clipboard</source>
        <translation>Копидсон хаягийг буулгах</translation>
    
YES, the translation is problematic because it uses an incorrect word for "paste". The correct word for "paste" in Mongolian in this context is "буулгах" (buulgah), not "копидсон" (kopidson), which means "copied".

NO
```

```
        <source>Paste address from clipboard</source>
        <translation>Копидсон хаягийг буулгах</translation>
    
YES, the translation is problematic because it uses an incorrect word for "paste". The correct word for "paste" in Mongolian in this context is "буулгах" (buulgah), not "копидсон" (kopidson), which means "copied".

NO
```

```
        <source>Transaction ID</source>
        <translation>Тодорхойлолт</translation>
    
YES, The translation of "Transaction ID" to "Тодорхойлолт" is incorrect and misleading in the context of Bitcoin. "Тодорхойлолт" means "Description" or "Definition". The correct translation for "Transaction ID" in Mongolian is "Гүйлгээний дугаар" or "Транзакцын дугаар".
NO, Гүйлгээний дугаар
```

```
        <source>Received with</source>
        <translation>Хүлээн авсан хаяг</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning. The English phrase "Received with" in a Bitcoin context typically refers to how an amount was received (e.g., "Received with thanks"). The provided Mongolian translation "Хүлээн авсан хаяг" translates to "Received address," which is not a meaningful phrase in this context.

The correct translation should reflect the idea of receiving something. Without further context, a direct and neutral translation of "Received with" is difficult, but it likely implies a positive or neutral reception.

Correct Translation: Хүлээн авсан
```

```
        <source>Received with</source>
        <translation>Хүлээн авсан хаяг</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning. The English phrase "Received with" in a Bitcoin context typically refers to how an amount was received (e.g., "Received with thanks"). The provided Mongolian translation "Хүлээн авсан хаяг" translates to "Received address," which is not a meaningful phrase in this context.

The correct translation should reflect the idea of receiving something. Without further context, a direct and neutral translation of "Received with" is difficult, but it likely implies a positive or neutral reception.

Correct Translation: Хүлээн авсан
```
</details>
