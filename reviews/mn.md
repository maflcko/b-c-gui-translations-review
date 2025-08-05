# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>mn</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bmn%5D%20low%20quality)


```
        <source>Copy the currently selected address to the system clipboard</source>
        <translation>Одоогоор сонгогдсон байгаа хаягуудыг сануулах</translation>
    
YES
The translation is incorrect and does not match the source meaning. The source talks about copying the currently selected address to the system clipboard. The provided translation means roughly "Remind the currently selected addresses," which is unrelated.

Correct translation:
Одоогоор сонгогдсон хаягийг системийн самбар руу хуулна уу
```

```
        <source>Choose the address to send coins to</source>
        <translation>Зооснуудыг илгээх хаягийг сонгоно уу</translation>
    
YES  
The translation "Зооснуудыг илгээх хаягийг сонгоно уу" means "Please choose the address to send the coins" which is understandable but slightly unnatural and could be improved for clarity and formality in the Bitcoin context.

A better translation would be:  
"Зоос илгээх хаягийг сонгоно уу"  
This removes the plural suffix on "зоос" (coins) which is typically not needed here, and sounds more natural in Mongolian.  
Alternatively, to be more precise:  
"Зоос илгээх хаягийг сонгоно уу"
```

```
        <source>Sending addresses - %1</source>
        <translation>хаягуудииг Илгээж байна - %1</translation>
    
YES
The translation is problematic because "хаягуудииг" contains an extra "и" and the word should be plural "хаягуудыг" to properly mean "addresses" in Mongolian. Also, the case marking "-ыг" (accusative) is appropriate here, but the word as given is misspelled.

Correct translation:
хаягуудыг Илгээж байна - %1
```

```
        <source>Wallet passphrase was successfully changed.</source>
        <translation>Түрүйвчийн нууц үг амжилттай ѳѳр</translation>
    
YES  
The translation is incomplete and cut off. The phrase "амжилттай ѳѳр" translates as "successfully other" but does not complete the thought "was successfully changed." A correct full translation would be:

Түрүүвчний нууц үг амжилттай өөрчлөгдлөө.
```

```
        <source>Send</source>
        <translation>Илгээх
 </translation>
    
YES
There is an unnecessary trailing whitespace (a non-breaking space) after the word "Илгээх". The translation should have no extra spaces or line breaks.

Correct translation:
Илгээх
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Түрүйвч &lt;b&gt;цоожтой&lt;/b&gt; ба одоогоор цоож &lt;b&gt;хаалттай&lt;/b&gt; байна</translation>
    
YES
The translation inaccurately reverses the meanings of "encrypted" and "locked." The correct terms should reflect that the wallet is first "encrypted" and then "locked." The phrase "цоожтой" means "locked," and "хаалттай" means "closed," which is not appropriate for "encrypted."

Correct translation:
Түрүйвч &lt;b&gt;шивэгдсэн&lt;/b&gt; ба одоогоор &lt;b&gt;цоожтой&lt;/b&gt; байна
```

```
        <source>Copy change</source>
        <translation>Ѳѳрчлѳлтийг санах</translation>
    
YES  
The translation "Ѳѳрчлѳлтийг санах" means "remember the change," which is incorrect for the Bitcoin context. The English phrase "Copy change" refers to copying the change amount (the leftover amount in a transaction), not memorizing or recalling it.

A more accurate translation would be:  
"Ѳѳрчлѳлийг хуулах"  
(where "хуулах" means "to copy" and "Ѳѳрчлѳл" means "change" in the context of amounts).
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Копидсон хаягийг буулгах</translation>
    
YES
The translation "Копидсон хаягийг буулгах" is problematic. The word "Копидсон" is a transliteration and does not correspond to the proper Mongolian word for "clipboard." Additionally, "буулгах" means "to unload" or "to bring down," which is not the correct verb for "paste" in this context.

Correct translation:
Тавиурнаас хаягыг наах
```

```
        <source>Client restart required to activate changes.</source>
        <extracomment>Text explaining that the settings changed will not come into effect until the client is restarted.</extracomment>
        <translation>Ѳѳрчлѳлтүүдийг идэвхижүүлхийн тулд клиентийг ахин эхлүүлэх шаардлагтай</translation>
    
YES
The translation has a typo: "шаардлагтай" should be "шаардлагатай". Also, there is a missing period at the end, which is present in the source text.

Correct translation:
Ѳѳрчлѳлтүүдийг идэвхижүүлхийн тулд клиентийг ахин эхлүүлэх шаардлагатай.
```

```
        <source>This change would require a client restart.</source>
        <translation>Энэ ѳѳрчлѳлтийг оруулахын тулд кли1нт програмыг ахин эхлүүлэх шаардлагтай</translation>
    
YES  
There is a typo in the translation: "кли1нт" should be "клиент". Also, the word "шаардлагтай" should be "шаардлагатай".  

Correct translation:  
Энэ өөрчлөлтийг оруулахын тулд клиент програмыг ахин эхлүүлэх шаардлагатай.
```

```
        <source>Copy change</source>
        <translation>Ѳѳрчлѳлтийг санах</translation>
    
YES  
The translation "Ѳѳрчлѳлтийг санах" means "remember the change," which is incorrect for the Bitcoin context. The English phrase "Copy change" refers to copying the change amount (the leftover amount in a transaction), not memorizing or recalling it.

A more accurate translation would be:  
"Ѳѳрчлѳлийг хуулах"  
(where "хуулах" means "to copy" and "Ѳѳрчлѳл" means "change" in the context of amounts).
```

```
        <source>Paste address from clipboard</source>
        <translation>Копидсон хаягийг буулгах</translation>
    
YES
The translation contains a non-Mongolian script word "Копидсон," which appears to be a transliteration of "copied" but is inappropriate and unidiomatic in Mongolian. The phrase "Paste address from clipboard" should be translated in clear Mongolian without mixing Cyrillic transliteration of English words.

Correct translation:
Хаягийг самбарнаас наах
```

```
        <source>Paste address from clipboard</source>
        <translation>Копидсон хаягийг буулгах</translation>
    
YES
The translation contains a non-Mongolian script word "Копидсон," which appears to be a transliteration of "copied" but is inappropriate and unidiomatic in Mongolian. The phrase "Paste address from clipboard" should be translated in clear Mongolian without mixing Cyrillic transliteration of English words.

Correct translation:
Хаягийг самбарнаас наах
```

```
        <source>Transaction ID</source>
        <translation>Тодорхойлолт</translation>
    
YES
The translation "Тодорхойлолт" means "Description" or "Definition," which is incorrect for "Transaction ID." The correct translation for "Transaction ID" in Mongolian should be "Гүйлгээний ID" or "Гүйлгээний дугаар."

Correct translation:
<translation>Гүйлгээний ID</translation>
```

```
        <source>Received with</source>
        <translation>Хүлээн авсан хаяг</translation>
    
YES  
The translation "Хүлээн авсан хаяг" means "Received address," which introduces "address" explicitly, but the source text "Received with" is incomplete on its own and likely meant to be followed by something (e.g., "Received with address" or "Received with label"). Translating it as "Хүлээн авсан хаяг" may misrepresent or prematurely specify the meaning by adding "address."

A better translation that captures "Received with" as a standalone phrase without adding extra words would be:  
"Хүлээн авсан"  

If more context is needed (e.g., "Received with address"), it should be included in the source or translated accordingly.
```

```
        <source>Received with</source>
        <translation>Хүлээн авсан хаяг</translation>
    
YES  
The translation "Хүлээн авсан хаяг" means "Received address," which introduces "address" explicitly, but the source text "Received with" is incomplete on its own and likely meant to be followed by something (e.g., "Received with address" or "Received with label"). Translating it as "Хүлээн авсан хаяг" may misrepresent or prematurely specify the meaning by adding "address."

A better translation that captures "Received with" as a standalone phrase without adding extra words would be:  
"Хүлээн авсан"  

If more context is needed (e.g., "Received with address"), it should be included in the source or translated accordingly.
```
</details>
