# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ur</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bur%5D%20low%20quality)


```
        <source>Delete</source>
        <translation>ڈیلیٹ

 </translation>
    
YES  
The translation contains unnecessary trailing whitespace and a non-breaking space, making it formatted incorrectly. The translation word "ڈیلیٹ" is a valid transliteration of "Delete" in Urdu, but the extra spaces/newlines after it should be removed.

Correct translation:  
ڈیلیٹ
```

```
        <source>Choose the address to send coins to</source>
        <translation>کوئین وصول کرنے والے کا پتہ</translation>
    
YES  
The translation "کوئین وصول کرنے والے کا پتہ" means "Address of the coin receiver," which does not accurately convey the imperative "Choose the address to send coins to." The original text instructs the user to select an address to send coins to, while the translation states the receiver's address without the instruction to choose.

Correct translation:  
"سکّے بھیجنے کے لیے پتہ منتخب کریں"
```

```
        <source>Choose the address to receive coins with</source>
        <translation>کوئین وصول کرنے والے کا پتہ</translation>
    
YES  
The translation "کوئین وصول کرنے والے کا پتہ" is incorrect and incomplete. It translates roughly as "the address of the coin receiver" but misses the imperative or instruction "Choose" and sounds unnatural for an instruction. A better translation would be:

"سکّے وصول کرنے کے لیے پتہ منتخب کریں"
```

```
        <source>Choose</source>
        <translation>چوز کریں

 </translation>
    
YES  
The Urdu translation "چوز کریں" is a direct transliteration of the English word "Choose" rather than a proper Urdu translation. Additionally, there is a trailing whitespace and a non-breaking space character after the text which should be removed.

Correct translation:  
چُنیں
```

```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>یہ آپ کے ادائیگی بھیجنے کے لئے بٹ کوائن ایڈریس ہیں.سکے بھیجنے سے پہلے ہمیشہ رقم اور وصول کنندہ پتہ چیک کریں۔</translation>
    
YES  
There is a spacing issue after the first sentence where the period is immediately followed by the next sentence without a space. Also, the phrase "Bitcoin addresses" is translated as "بٹ کوائن ایڈریس" which is understandable but could be better expressed as "بٹ کوائن کے پتے" for clarity. Additionally, "سکے بھیجنے" should be "سکے بھیجنے سے" for grammatical correctness.

Correct translation:  
"یہ آپ کے ادائیگی بھیجنے کے لیے بٹ کوائن کے پتے ہیں۔ سکے بھیجنے سے پہلے ہمیشہ رقم اور وصول کنندہ کا پتہ چیک کریں۔"
```

```
        <source>Show passphrase</source>
        <translation>پاسفریز دکھائیں</translation>
    
YES
The term "پاسفریز" is a transliteration and not a standard Urdu word for "passphrase." A more accurate and natural Urdu translation for "Show passphrase" would be:
"پاس فریز دکھائیں" or better yet "پاسفریز دکھائیں" is widely used, but separating it as "پاس فریز" aligns better with Urdu script conventions.
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>پرس کو غیر مقفل کرنے کے لئے اس آپریشن کو آپ کے بٹوے کا پاسفریز درکار ہے۔</translation>
    
YES
The translation contains a problematic word choice and phrase order. The word "پرس" is not correct in this context; it should be "آپ کے بٹوے" (your wallet). Also, the sentence structure is awkward and unclear.

Correct translation:
اس آپریشن کو آپ کے بٹوے کو غیر مقفل کرنے کے لیے پاسفریز کی ضرورت ہے۔
```

```
        <source>Unlock wallet</source>
        <translation>بستہ کھولیں</translation>
    
YES  
The translation "بستہ کھولیں" means "open the package" or "open the bundle," which is incorrect in the Bitcoin wallet context. The correct translation for "Unlock wallet" should convey unlocking the wallet (i.e., removing the lock or password protection).

Correct translation:  
"والٹ ان لاک کریں"  
or more formally:  
"والٹ کا لاک کھولیں"
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>انتباہ: اگر آپ اپنا بٹوہ انکرپٹ کرتے ہیں اور اپنا پاس فریز کھو دیتے ہیں تو ، آپ اپنے تمام بٹکوئنز کھو دیں گے.</translation>
    
YES  
The translation misses the strong emphasis from "LOSE ALL OF YOUR BITCOINS" which is marked with <b> tags in the source. Also, the Urdu translation uses a comma before "آپ" which is not standard in Urdu punctuation. Additionally, the word "بٹوہ" (wallet) can be better transliterated or replaced with a more common Urdu term "والیٹ". Finally, the sentence ends with a period instead of an exclamation mark, and the emphasis in the source should be preserved.

Correct translation:  
انتباہ: اگر آپ اپنا والیٹ انکرپٹ کرتے ہیں اور اپنا پاسفریز کھو دیتے ہیں تو آپ اپنے تمام بٹ کوائنز &lt;b&gt;کھو دیں گے&lt;/b&gt;!
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>پرس کے لئے نیا پاسفریج درج کریں۔ براہ کرم دس یا زیادہ بے ترتیب حرفوں ، یا آٹھ یا زیادہ الفاظ کا پاس فریز استعمال کریں۔</translation>
    
YES  
The translation has minor issues:  
1. "پرس کے لئے" is not the correct term for "wallet" in the Bitcoin context. The correct term should be "والٹ" or "بٹ کوائن والیٹ" depending on formality, but "والٹ" is common in Urdu translations for "wallet".  
2. "پاسفریج" is commonly transliterated from "passphrase" and acceptable, but "پاس فریز" appears inconsistently in the next phrase. Choose one consistent transliteration.  
3. The source uses HTML tags (`&lt;br/&gt;`, `<b>`) which are lost in the translation. The line break and bold formatting should be preserved or equivalently expressed.

A better translation:  
"والٹ کے لیے نئی پاس فریز داخل کریں۔&lt;br/&gt;براہِ کرم ایسی پاس فریز استعمال کریں جس میں &lt;b&gt;دس یا اس سے زیادہ بے ترتیب حروف&lt;/b&gt; یا &lt;b&gt;آٹھ یا اس سے زیادہ الفاظ&lt;/b&gt; ہوں۔"

This preserves formatting and meaning, and uses the correct term for wallet. Also, spacing around punctuation is corrected (no spaces before commas).  

Correct translation:  
والٹ کے لیے نئی پاس فریز داخل کریں۔&lt;br/&gt;براہِ کرم ایسی پاس فریز استعمال کریں جس میں &lt;b&gt;دس یا اس سے زیادہ بے ترتیب حروف&lt;/b&gt; یا &lt;b&gt;آٹھ یا اس سے زیادہ الفاظ&lt;/b&gt; ہوں۔
```

```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>پرس کے لئے پرانا پاسفریج اور نیا پاسفریز درج کریں۔</translation>
    
YES  
The translation incorrectly uses "پرس" (purse) instead of "والٹ" (wallet), and the singular/plural form of "passphrase" is inconsistent. Also, "passphrase" is usually transliterated or translated as "پاس فریز". The correct translation should be:  
"والٹ کے لیے پرانا پاسفریز اور نیا پاسفریز درج کریں۔"
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>بٹوے کے ڈکرپشن کے لیے درج کیا گیا پرانا پاس فریز غلط ہے۔ اس میں ایک خالی کریکٹر ہے (یعنی - ایک صفر بائٹ)۔ اگر پاس فریز 25.0 سے پہلے اس سافٹ ویئر کے ورژن کے ساتھ سیٹ کیا گیا تھا، تو براہ کرم صرف حروف کے ساتھ دوبارہ کوشش کریں — لیکن شامل نہیں — پہلے خالی کریکٹر۔</translation>
    
YES
The translation has some issues:
1. The phrase "null character" is translated as "خالی کریکٹر" which literally means "empty character", but "null character" in computing is better translated as "صفر کردار" or "نیل کردار" to accurately convey "null (zero byte) character".
2. The last part "but not including — the first null character" is incomplete and unclear in translation: "— لیکن شامل نہیں — پہلے خالی کریکٹر" lacks the object and proper phrasing, making it confusing.
3. The phrase "wallet decryption" translated as "بٹوے کے ڈکرپشن" mixes English and Urdu; it would be better to use "بٹوے کو ڈکرپٹ کرنے کے لیے" or "بٹوے کی ڈی کرپشن کے لیے" for fluency.

Corrected translation:

"بٹوے کو ڈی کرپٹ کرنے کے لیے درج کیا گیا پرانا پاس فریز غلط ہے۔ اس میں ایک نیل کردار (یعنی صفر بائٹ) موجود ہے۔ اگر پاس فریز اس سافٹ ویئر کے 25.0 سے پہلے کے ورژن کے ساتھ سیٹ کیا گیا تھا، تو براہ کرم پہلے نیل کردار تک کے (لیکن اسے شامل کیے بغیر) صرف حروف کے ساتھ دوبارہ کوشش کریں۔"
```

```
        <source>Banned Until</source>
        <translation>تک پابندی عائد</translation>
    
YES  
The translation "تک پابندی عائد" is incorrect and awkward. A more accurate and natural translation for "Banned Until" in Urdu would be:

"تک پابندی"  
or  
"پابندی ختم ہونے تک" (meaning "Banned until [time]").  

Given the shortness of the source phrase, the best concise translation is:

"تک پابندی"
```

```
        <source>Runaway exception</source>
        <translation>بھگوڑے رعایت</translation>
    
YES  
The Urdu translation "بھگوڑے رعایت" is incorrect and misleading. The English phrase "Runaway exception" in a programming or technical context means an exception that occurs uncontrollably or unexpectedly, not a "runaway" in the literal sense of a fugitive or absconder (بھگوڑا) or a "discount" (رعایت). 

Correct translation:  
"بے قابو استثناء"  
or  
"بے قابو استثناء کی خرابی"
```

```
        <source>Address Fetch</source>
        <extracomment>Short-lived peer connection type that solicits known addresses from a peer.</extracomment>
        <translation>پتہ بازیافت کریں۔</translation>
    
YES  
The Urdu translation "پتہ بازیافت کریں۔" is somewhat literal and sounds like an imperative sentence meaning "Fetch Address." However, the original source text "Address Fetch" is a noun phrase (title or label), not a command. The period/full stop at the end is unnecessary and uncommon in UI labels.

Correct translation:  
"پتہ بازیافت"
```

```
        <source>Show general overview of wallet</source>
        <translation>پرس کا عمومی جائزہ دکھائیں</translation>
    
YES  
The Urdu translation "پرس کا عمومی جائزہ دکھائیں" literally means "Show the general overview of the purse," which is incorrect in the context of Bitcoin wallets. The correct term for "wallet" in the Bitcoin context is "والیٹ".  

Correct translation:  
"والیٹ کا عمومی جائزہ دکھائیں"
```

```
        <source>Quit application</source>
        <translation>درخواست چھوڑ دیں</translation>
    
YES
The translation "درخواست چھوڑ دیں" literally means "leave the request," which is not accurate for "Quit application." A better translation would be:

"ایپلیکیشن بند کریں"
```

```
        <source>About %1</source>
        <translation>معلومات%1</translation>
    
YES  
There is a spacing issue in the translation. In Urdu, there should be a space between "معلومات" and "%1" to match the formatting of the source text. Also, "About" in this context (likely as a label "About %1" meaning "About [something]") is better translated as "کے بارے میں %1" or "%1 کے بارے میں" depending on the flow, but since the source is "About %1", the literal simple translation is "%1 کے بارے میں".

Correct translation:  
%1 کے بارے میں
```

```
        <source>Modify configuration options for %1</source>
        <translation>%1 اختیارات کے لئےترتیب ترمیم کریں</translation>
    
YES
The translation has spacing issues and slightly awkward phrasing. There should be a space between "کے لئے" and "ترتیب" and the overall phrasing can be smoother. A better translation would be:

%1 کے لیے ترتیب کے اختیارات میں ترمیم کریں
```

```
        <source>Wallet:</source>
        <translation>پرس:</translation>
    
YES
The translation "پرس:" does not correctly translate "Wallet:". The correct translation for "Wallet:" in Urdu should be "والٹ:". 

Correct translation:
والٹ:
```

```
        <source>Backup Wallet…</source>
        <translation> بیک اپ والیٹ…</translation>
    
YES  
The translation contains an unnecessary leading space before "بیک اپ والیٹ…". This is a whitespace formatting issue. Also, the ellipsis character appears correct, but ensure there is no extra space before it.  

Correct translation:  
بیک اپ والیٹ…
```

```
        <source>Change Passphrase…</source>
        <translation> بیک اپ والیٹ…</translation>
    
YES  
The translation "بیک اپ والیٹ…" means "Backup Wallet…" which is not an accurate translation of "Change Passphrase…". The correct translation should convey changing the passphrase, not backing up the wallet.

Correct translation:  
"پاس فریز تبدیل کریں…"
```

```
        <source>Sign message…</source>
        <translation>سائن اور پیغام…</translation>
    
YES  
The translation "سائن اور پیغام…" means "Sign and message…" which is incorrect. The source phrase "Sign message…" means "Sign message…" as a single action (signing a message). The correct translation should be:

"پیغام پر دستخط کریں…"
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>اپنے ویکیپیڈیا پتوں کے ساتھ پیغامات پر دستخط کریں تاکہ آپ ان کے مالک ہوں</translation>
    
YES  
The translation incorrectly uses "ویکیپیڈیا" (Wikipedia) instead of "بٹ کوائن" (Bitcoin). It also ends abruptly and is not fluent. A more accurate translation would be:  
اپنے بٹ کوائن پتوں کے ساتھ پیغامات پر دستخط کریں تاکہ آپ ان کے مالک ہوں۔
```

```
        <source>Open URI…</source>
        <translation>کھولیں اور یو آر آئی…</translation>
    
YES  
The translation "کھولیں اور یو آر آئی…" means "Open and URI…" which does not accurately reflect the English source "Open URI…". The English text is an imperative phrase instructing to open a URI. The correct Urdu translation should be "یو آر آئی کھولیں…" which maintains the correct word order and meaning.  

Correct translation:  
یو آر آئی کھولیں…
```

```
        <source>Close Wallet…</source>
        <translation>پرس بند کریں…</translation>
    
YES  
The translation "پرس بند کریں…" is inaccurate and problematic. The English source "Close Wallet…" refers to closing a Bitcoin wallet, but "پرس" typically means "purse" or "small wallet" in a physical sense and is less commonly used in technical contexts. A more appropriate term for the Bitcoin wallet would be "والیٹ" which is commonly adopted in Urdu for digital wallets. Also, the verb "بند کریں" (close) is correctly used, but better phrasing would be "والیٹ بند کریں…" to accurately reflect the context.

Correct translation:  
والیٹ بند کریں…
```

```
        <source>File</source>
        <translation>اور فائل</translation>
    
YES  
The translation "اور فائل" means "and file" in Urdu, which is incorrect for the English word "File". The correct translation should be simply "فائل".
```

```
        <source>Settings</source>
        <translation>اور ترتیبات</translation>
    
YES  
The translation contains an unnecessary and incorrect word "اور" which means "and" in Urdu. The correct translation for "Settings" alone is "ترتیبات".

Correct translation:  
ترتیبات
```

```
        <source>Help</source>
        <translation>اور مدد</translation>
    
YES
The translation "اور مدد" means "and help" in Urdu, which is incorrect and adds an extraneous word "اور" (and). The correct translation for "Help" in Urdu is simply:

مدد
```

```
        <source>Syncing Headers (%1%)…</source>
        <translation> '%1%' ہیڈرز کی مطابقت پذیری</translation>
    
YES
The translation contains extraneous quotation marks and the phrase is incomplete or unnatural in Urdu. Additionally, the format specifier %1% should be inside the sentence correctly without extra quotes or spacing issues. The phrase "ہیڈرز کی مطابقت پذیری" is somewhat awkward; a better term for "Syncing Headers" would be "ہیڈرز ہم آہنگ کر رہے ہیں" or "ہیڈرز ہم آہنگی" to imply synchronization.

Correct translation:
ہیڈرز (%1%) ہم آہنگ ہو رہے ہیں…
```

```
        <source>Synchronizing with network…</source>
        <translation>نیٹ ورک کے ساتھ ہم آہنگ ہو کر</translation>
    
YES  
The translation "نیٹ ورک کے ساتھ ہم آہنگ ہو کر" roughly means "becoming synchronized with the network," but it is incomplete and misses the progressive aspect conveyed by "Synchronizing with network…". Also, it lacks the ellipsis (…) indicating ongoing action. A more accurate and natural Urdu translation would be:  
"نیٹ ورک کے ساتھ ہم آہنگ ہو رہا ہے…"
```

```
        <source>Connecting to peers…</source>
        <translation>ساتھیوں سے منسلک کرنے</translation>
    
YES  
The translation "ساتھیوں سے منسلک کرنے" literally means "connecting to peers," but it is incomplete and grammatically incorrect. It is a verbal phrase without proper tense or completion, making it sound like "to connect to peers" rather than the ongoing action "Connecting to peers…" as in the source.

A better translation would use a continuous/progressive form or a phrase that expresses the ongoing connection process, for example:

"ساتھیوں سے جڑ رہا ہوں…"  
or  
"ساتھیوں سے رابطہ قائم کیا جا رہا ہے…"  

These convey the meaning "Connecting to peers…" in Urdu more naturally.

Correct translation:  
ساتھیوں سے جڑ رہا ہوں…
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>ادائیگی کی درخواست کریں: ( کوئیک رسپانس ( کیو۔آر ) کوڈ اور بٹ کوائن ( یونیورسل ادائیگیوں کا نظام) کے ذریعے سے</translation>
    
YES  
The translation is incomplete and improperly formatted; there is an opening parenthesis after "کریں" but no closing one. Also, mixed English and Urdu terms disrupt clarity. The phrase "bitcoin: URIs" is incorrectly translated as "بٹ کوائن ( یونیورسل ادائیگیوں کا نظام)" which means "Universal Payment System," which is not equivalent to "bitcoin: URIs". The term "bitcoin: URIs" should be transliterated or left as is, as it is a technical term. Also, "QR codes" was translated as "کوئیک رسپانس ( کیو۔آر ) کوڈ" which is a repetition; better to use just "کیو۔آر کوڈز".

Correct translation:  
ادائیگیوں کی درخواست کریں (کیو آر کوڈز اور bitcoin: URIs تیار کرتا ہے)
```

```
        <source>Catching up…</source>
        <translation>پکڑنا</translation>
    
YES  
The translation "پکڑنا" means "to catch" or "to seize" in an infinitive form, which is not appropriate in this context. The English phrase "Catching up…" here implies that the system is synchronizing or updating to the latest state, a continuous or progressive action. A more accurate Urdu translation would be:  
"اپ ٹو ڈیٹ ہو رہا ہے…" or simply "اپ ڈیٹ ہو رہا ہے…" or "ہم آہنگ ہو رہا ہے…" depending on style and context.

Correct translation:  
اپ ڈیٹ ہو رہا ہے…
```

```
        <source>Last received block was generated %1 ago.</source>
        <translation>آخری موصول شدہ 1 '%1' پہلے تیار کیا گیا تھا۔</translation>
    
YES  
The translation has word order issues and misplaces the '%1' format specifier inside quotes, which is incorrect. Also, the position of "1" before '%1' is unnecessary and confusing. The phrase should be fluent and correctly incorporate '%1' without extra spaces or punctuation.

Correct translation:  
آخری موصول شدہ بلاک %1 پہلے تیار کیا گیا تھا۔
```

```
        <source>Receiving addresses</source>
        <translation>اور پتے وصول کرنا</translation>
    
YES  
The translation "اور پتے وصول کرنا" means "and receive addresses," which is incorrect and changes the meaning. The source phrase "Receiving addresses" refers to addresses that receive Bitcoin, not an action combining "and" with addresses. A better translation would be:  
"وصول کرنے والے پتے"
```

```
        <source>Zoom</source>
        <translation>بغور جائزہ لینا</translation>
    
YES  
The provided translation "بغور جائزہ لینا" means "to examine carefully" or "to review thoroughly," which is not an appropriate translation for the English word "Zoom," especially in the context of Bitcoin UI where "Zoom" typically refers to magnifying or resizing the view.

Correct translation:  
"زوم"
```

```
        <source>Date: %1
</source>
        <translation>%1' تاریخ۔
</translation>
    
YES  
The translation has an unnecessary apostrophe after %1 and an incorrect full stop (۔) at the end. Also, the word order is awkward. A correct Urdu translation for "Date: %1" would be:

تاریخ: %1
```

```
        <source>Amount: %1
</source>
        <translation>%1' مقدار
</translation>
    
YES  
The translation has a misplaced apostrophe (') after %1 and incorrect word order. In Urdu, the word "مقدار" (Amount) should appear before the value. Also, there is an unnecessary space before the word "مقدار". The correct translation should be:

%1 مقدار
```

```
        <source>Wallet: %1
</source>
        <translation>%1' والیٹ
</translation>
    
YES  
The placement of the apostrophe (') after %1 is incorrect and unnatural in Urdu. The translation also unnecessarily adds an apostrophe that is not present in the source text. The word "والیٹ" (wallet) follows the placeholder %1, which is correct, but the quote mark should be removed. Additionally, in Urdu, the label "Wallet: %1" should retain the colon ":" to match the source format.  

Correct translation:  
%1 والیٹ:  
or  
والیٹ: %1  

Since the source is "Wallet: %1\n", the natural and clear translation would place the colon after "والیٹ" and then the placeholder:  

والیٹ: %1
```

```
        <source>Type: %1
</source>
        <translation>1 %1'قسم
</translation>
    
YES
The translation is incorrect and garbled. The correct translation for "Type: %1" in Urdu should be:

قسم: %1
```

```
        <source>Label: %1
</source>
        <translation>%1'لیبل
</translation>
    
YES  
The translation inaccurately places the placeholder %1 before the word "لیبل" and includes an unnecessary apostrophe. The source text "Label: %1\n" means the word "Label" followed by a colon and a space, then the placeholder %1. The correct Urdu translation should have the label text first, then the placeholder %1, and reflect the colon properly.

Correct translation:  
لیبل: %1\n
```

```
        <source>Address: %1
</source>
        <translation>%1' پتہ
</translation>
    
YES
The translation incorrectly places the placeholder %1 before the word پتہ (address) and includes an unnecessary apostrophe. The source has "Address: %1" where "Address:" is the label and %1 is the variable part; in Urdu, the word "پتہ" should come before the placeholder and the colon should be correctly placed.

Correct translation:
پتہ: %1
```

```
        <source>HD key generation is &lt;b&gt;enabled&lt;/b&gt;</source>
        <translation>درجہ بندی کا تعین کرنے والی ایچ۔ڈی کلیدی جنریشن &lt;b&gt;فعال&lt;/b&gt; ہے</translation>
    
YES
The phrase "درجہ بندی کا تعین کرنے والی ایچ۔ڈی کلیدی جنریشن" is awkward and incorrect in Urdu, as it translates to something like "classification determining HD key generation," which is not meaningful in this context. The correct translation should clearly convey "HD key generation is enabled" without extra unrelated words.

Correct translation:
ایچ ڈی کی چابی کی تخلیق &lt;b&gt;فعال&lt;/b&gt; ہے
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>درجہ بندی کا تعین کرنے والی ایچ۔ ڈی کلیدی جنریشن&lt;b&gt; غیر فعال&lt;/b&gt; ہے</translation>
    
YES  
The translation is incorrect and awkward in Urdu. The phrase "درجہ بندی کا تعین کرنے والی" means "the one that determines classification," which is incorrect in this context. The correct translation should clearly communicate that "HD key generation is disabled" without adding unrelated phrases.

Correct translation:  
ایچ۔ڈی کلید کی تخلیق &lt;b&gt;غیر فعال&lt;/b&gt; ہے
```

```
        <source>(un)select all</source>
        <translation>سب کو غیر منتخب کریں</translation>
    
YES  
The source "(un)select all" means toggle selection: either select all or unselect all, implying both actions are covered. The Urdu translation "سب کو غیر منتخب کریں" only means "deselect all," missing the "(un)select" dual meaning.  

Correct translation:  
"(غیر) منتخب کریں"  
or more explicitly:  
"سب کو منتخب/غیر منتخب کریں"
```

```
        <source>Copy label</source>
        <translation>کاپی اور لیبل</translation>
    
YES
The translation mixes English and Urdu transliterations instead of translating fully into Urdu. "Copy" is written as "کاپی" (transliteration of "copy") and "label" as "لیبل" (transliteration of "label"). A better Urdu translation would fully translate the terms to be clear and natural.

Correct translation:
"لیبل کی کاپی کریں"
```

```
        <source>Copy amount</source>
        <translation>کاپی اور رقم</translation>
    
YES
The current translation "کاپی اور رقم" literally means "Copy and amount," which is incorrect. The English phrase "Copy amount" here is an imperative or label meaning to copy the amount, so the correct translation should be concise and convey the action "Copy amount."

Correct translation:
رقم کو کاپی کریں
```

```
        <source>(%1 locked)</source>
        <translation>مقفل'%1</translation>
    
YES
The translation places the placeholder %1 after the word without appropriate spacing and the use of an incorrect apostrophe character. Also, the English parentheses are not replicated, which can affect clarity.

Correct translation:
(%1 مقفل)
```

```
        <source>Creating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the create wallet progress window which indicates to the user which wallet is currently being created.</extracomment>
        <translation>والیٹ بنانا &lt;b&gt; %1&lt;/b&gt;</translation>
    
YES  
There is an extra space before %1 in the translation, which is inconsistent with the source. Also, the ellipsis (…) at the end is missing.  

Correct translation:  
والیٹ بنانا &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Can't list signers</source>
        <translation>دستخط کنندگان کی فہرست نہیں بن سکتی</translation>
    
YES  
The Urdu translation is somewhat awkward and not idiomatic. The phrase "دستخط کنندگان کی فہرست نہیں بن سکتی" literally translates as "The list of signers cannot be made," which can be better expressed more naturally as "دستخط کنندگان کی فہرست نہیں دکھائی جا سکتی" or "دستخط کنندگان کی فہرست ظاہر نہیں کی جا سکتی" meaning "Can't display the list of signers." Also, the original English uses "Can't list signers," which implies inability to list them, so the translation should reflect that clearly.

Correct translation:  
دستخط کنندگان کی فہرست نہیں دکھائی جا سکتی
```

```
        <source>Loading wallets…</source>
        <extracomment>Descriptive text of the load wallets progress window which indicates to the user that wallets are currently being loaded.</extracomment>
        <translation>اپکا والٹ لوڈ ہورہا ہے </translation>
    
YES
The translation uses "اپکا والٹ لوڈ ہورہا ہے" which means "Your wallet is loading." This changes the plural "wallets" to singular and also adds a possessive "your," which is not present in the English source. Additionally, there is a trailing space before the closing tag which is a minor formatting issue. A more accurate translation, preserving plural and neutrality, would be:

والٹس لوڈ ہو رہے ہیں۔
```

```
        <source>Label</source>
        <translation>چٹ</translation>
    
YES  
The translation "چٹ" is incorrect and inappropriate for the term "Label" in the Bitcoin context. The correct Urdu translation for "Label" (as in a tag or name for identification) is "لیبل".

Correct translation:  
لیبل
```

```
        <source>Limit block chain storage to</source>
        <translation>بلاک چین اسٹوریج کو محدود کریں۔</translation>
    
YES  
The translation adds a full stop (۔) which is not present in the source text and is unnecessary here. Additionally, the original English phrase is incomplete and functions as a phrase fragment, likely expecting a value or unit after it ("Limit block chain storage to [amount]"). A better Urdu translation should also omit the full stop and retain the fragment form:

Correct translation:  
بلاک چین اسٹوریج کو محدود کریں
```

```
        <source>calculating…</source>
        <translation>حساب لگانا</translation>
    
YES
The translation "حساب لگانا" means "to calculate" or "calculating" in an infinitive or verbal noun form. The English source "calculating…" implies an ongoing process (present participle) and often includes an ellipsis to indicate progress. A more accurate Urdu translation capturing the ongoing action and the ellipsis would be:

"حساب لگایا جا رہا ہے…"

This translates to "Calculating…" in the present continuous tense, reflecting the source meaning more precisely.
```

```
        <source>Estimated time left until synced</source>
        <translation>مطابقت پذیر ہونے میں تخمینی وقت باقی ہے۔</translation>
    
YES  
The translation "مطابقت پذیر ہونے میں تخمینی وقت باقی ہے۔" is somewhat unnatural and a bit verbose for the concise English phrase "Estimated time left until synced." The phrase "مطابقت پذیر ہونے" (meaning "becoming compatible") is not commonly used in the context of syncing in Urdu. A more appropriate and natural translation in the Bitcoin or technical context would be:

"ہم آہنگ ہونے تک تخمینی باقی وقت"  

or  

"ہم وقت سازی مکمل ہونے تک تخمینی وقت باقی ہے"  

This conveys clearly that the remaining estimated time is until synchronization completes.
```

```
        <source>Main</source>
        <translation>اور مرکزی</translation>
    
YES  
The translation "اور مرکزی" literally means "and central" or "also central" in Urdu, which is incorrect and does not convey the meaning of "Main." The correct Urdu translation for "Main" in this context (likely as a label or title meaning primary or principal) should be:

Correct translation:  
"مرکزی"
```

```
        <source>Reset Options</source>
        <translation>اور دوبارہ ترتیب دینے کے اختیارات</translation>
    
YES  
The translation "اور دوبارہ ترتیب دینے کے اختیارات" is incorrect and unnatural. The word "اور" means "and" and is unnecessary here, leading to a confusing phrase that reads roughly as "and reset options." The correct translation for "Reset Options" in Urdu should be:

"اختیارات کو دوبارہ ترتیب دیں"  
or more succinctly:  
"اختیارات ری سیٹ کریں"
```

```
        <source>Enable coin control features</source>
        <translation>سکے اور کنٹرول کی خصوصیات کو فعال کریں۔</translation>
    
YES
The translation incorrectly translates "coin control" as "سکے اور کنٹرول" which means "coin and control," altering the intended meaning of "coin control" as a compound noun (a Bitcoin feature). The correct translation should treat "coin control" as a single concept related to Bitcoin.

Correct translation:
سکوں کے کنٹرول کی خصوصیات کو فعال کریں۔
```

```
        <source>Failed to load transaction: %1</source>
        <translation>لین دین لوڈ کرنے میں ناکام:%1</translation>
    
YES
There is a spacing issue in the translation. In Urdu, there should be a space after the colon (:) before the format specifier %1. Also, "لین دین" is the correct term for "transaction," and "لوڈ کرنے میں ناکام" correctly means "failed to load."

Correct translation:
لین دین لوڈ کرنے میں ناکام: %1
```

```
        <source>Failed to sign transaction: %1</source>
        <translation>لین دین پر دستخط کرنے میں ناکام:%1</translation>
    
YES  
There is a spacing issue before the format specifier %1; there should be a space after the colon for proper formatting in Urdu. Also, the phrase can be made more natural:

Correct translation:  
لین دین پر دستخط کرنے میں ناکام: %1
```

```
        <source>Information</source>
        <translation>اور معلومات</translation>
    
YES
The translation contains an unnecessary and incorrect word "اور" which means "and". The correct translation of "Information" in Urdu is simply "معلومات".

Correct translation:
معلومات
```

```
        <source>Peers</source>
        <translation>اور فریق</translation>
    
YES
The translation "اور فریق" means "and party" in Urdu, which is incorrect for "Peers" in the Bitcoin/network context. "Peers" refers to network nodes or connected participants.

Correct translation:
ساتھی
```

```
        <source>Disconnect</source>
        <translation>اور منقطع کریں۔</translation>
    
YES  
The Urdu translation has an unnecessary period (۔) at the end, which is not needed in this context. Also, "Disconnect" is better translated as "منقطع کریں" without "اور" ("and" / "or"). The correct and concise translation should be:

منقطع کریں
```

```
        <source>Amount:</source>
        <translation>اور رقم</translation>
    
YES  
The translation "اور رقم" literally means "and amount," which is incorrect as the source simply indicates "Amount:". The word "اور" means "and" and is unnecessary here. The correct translation should be:

رقم:
```

```
        <source>Message:</source>
        <translation>اور پیغام</translation>
    
YES
The original English "Message:" is a label indicating a message field, typically followed by a colon. The translation "اور پیغام" means "and message," which is incorrect and changes the meaning. The correct translation should simply be:

پیغام:
```

```
        <source>Copy label</source>
        <translation>کاپی اور لیبل</translation>
    
YES
The translation mixes English and Urdu transliterations instead of translating fully into Urdu. "Copy" is written as "کاپی" (transliteration of "copy") and "label" as "لیبل" (transliteration of "label"). A better Urdu translation would fully translate the terms to be clear and natural.

Correct translation:
"لیبل کی کاپی کریں"
```

```
        <source>Copy amount</source>
        <translation>کاپی اور رقم</translation>
    
YES
The current translation "کاپی اور رقم" literally means "Copy and amount," which is incorrect. The English phrase "Copy amount" here is an imperative or label meaning to copy the amount, so the correct translation should be concise and convey the action "Copy amount."

Correct translation:
رقم کو کاپی کریں
```

```
        <source>Wallet:</source>
        <translation>پرس:</translation>
    
YES
The translation "پرس:" does not correctly translate "Wallet:". The correct translation for "Wallet:" in Urdu should be "والٹ:". 

Correct translation:
والٹ:
```

```
        <source>per kilobyte</source>
        <translation>فی کلو بائٹ(kb)</translation>
    
YES
The translation uses mixed scripts and an unclear abbreviation. The English "per kilobyte" should be translated clearly and consistently in Urdu script without mixing Latin abbreviations inside parentheses unnecessarily. Also, the abbreviation "kb" should be in uppercase "KB" and separated from Urdu text properly.

Correct translation:
فی کلو بائٹ
```

```
        <source>Copy label</source>
        <translation>کاپی اور لیبل</translation>
    
YES
The translation mixes English and Urdu transliterations instead of translating fully into Urdu. "Copy" is written as "کاپی" (transliteration of "copy") and "label" as "لیبل" (transliteration of "label"). A better Urdu translation would fully translate the terms to be clear and natural.

Correct translation:
"لیبل کی کاپی کریں"
```

```
        <source>Copy amount</source>
        <translation>کاپی اور رقم</translation>
    
YES
The current translation "کاپی اور رقم" literally means "Copy and amount," which is incorrect. The English phrase "Copy amount" here is an imperative or label meaning to copy the amount, so the correct translation should be concise and convey the action "Copy amount."

Correct translation:
رقم کو کاپی کریں
```

```
        <source>Copy transaction ID</source>
        <translation>لین دین اور شناخت کی تفصیلات(ID) کاپی کریں۔</translation>
    
YES  
The translation is inaccurate and awkward. "لین دین اور شناخت کی تفصیلات(ID) کاپی کریں۔" literally means "Copy transaction and identity details (ID)". The source only says "Copy transaction ID," which should be translated as "ٹرانزیکشن آئی ڈی کو کاپی کریں" or "ٹرانزیکشن ID کو کاپی کریں". Also, the parentheses around "ID" should not have a space before them, and the phrase should be concise.

Correct translation:  
ٹرانزیکشن آئی ڈی کو کاپی کریں۔
```
</details>
