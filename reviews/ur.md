# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ur</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bur%5D%20low%20quality)


```
        <source>Delete</source>
        <translation>ڈیلیٹ

 </translation>
    
YES
The translation uses an Urdu transliteration of "Delete" (ڈیلیٹ), which is commonly used in informal contexts. However, there is an extra newline and a stray non-breaking space character after the translation, resulting in whitespace formatting issues. Also, a more accurate Urdu translation would be "حذف کریں".

Correct translation:
حذف کریں
```

```
        <source>Choose the address to send coins to</source>
        <translation>کوئین وصول کرنے والے کا پتہ</translation>
    
YES
The translation does not accurately reflect the source text. The source asks the user to select or choose an address to send coins to, but the translation reads "The address of the coin receiver," which is more of a description than an instruction or choice prompt.

Correct translation:
"سکے بھیجنے کے لیے پتہ منتخب کریں"
```

```
        <source>Choose the address to receive coins with</source>
        <translation>کوئین وصول کرنے والے کا پتہ</translation>
    
YES
The translation omits the imperative "Choose" and does not convey the user's action of selecting an address. The correct translation should retain the instruction to choose/select.

Correct translation:
سکے وصول کرنے کے لیے پتہ منتخب کریں
```

```
        <source>Choose</source>
        <translation>چوز کریں

 </translation>
    
YES
The translation "چوز کریں" is incorrect. "چوز" is just a transliteration of the English word "choose," which is not natural Urdu. Also, there is an unnecessary newline and whitespace at the end, which is a format issue.

Correct translation:
منتخب کریں
```

```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>یہ آپ کے ادائیگی بھیجنے کے لئے بٹ کوائن ایڈریس ہیں.سکے بھیجنے سے پہلے ہمیشہ رقم اور وصول کنندہ پتہ چیک کریں۔</translation>
    
YES
There are minor grammatical errors and spacing issues in the Urdu translation:
- "آپ کے ادائیگی بھیجنے کے لئے بٹ کوائن ایڈریس ہیں." is awkward and should be "یہ آپ کے بٹ کوائن ایڈریس ہیں جنہیں ادائیگی بھیجنے کے لیے استعمال کیا جاتا ہے۔"
- There is a missing space after the period/full stop.
- "پتہ" should be "پتہ" but "ایڈریس" may be more commonly understood for "address"; both are acceptable but "پتہ" fits the sentence better.

Correct translation:
یہ آپ کے بٹ کوائن ایڈریس ہیں جنہیں ادائیگی بھیجنے کے لیے استعمال کیا جاتا ہے۔ سکے بھیجنے سے پہلے ہمیشہ رقم اور وصول کنندہ کا پتہ چیک کریں۔
```

```
        <source>Unlock wallet</source>
        <translation>بستہ کھولیں</translation>
    
YES
The Urdu word "بستہ" means "bag" or "briefcase", not "wallet". The correct word for "wallet" in Urdu is "پرس" or "والیٹ". Also, "کھولیں" is a polite/plural imperative, which is fine, but the translation should accurately reflect "Unlock wallet".

Correct translation:
والیٹ ان لاک کریں
or
پرس کو ان لاک کریں
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>پرس کے لئے نیا پاسفریج درج کریں۔ براہ کرم دس یا زیادہ بے ترتیب حرفوں ، یا آٹھ یا زیادہ الفاظ کا پاس فریز استعمال کریں۔</translation>
    
YES
The translation has several issues:
- "پرس کے لئے" should be "والیٹ کے لیے" (wallet for) to accurately match the terminology.
- "پاسفریج" is a transliteration error; it should be "پاس فریز".
- The translation omits the instruction formatting (&lt;br/&gt; and &lt;b&gt;).
- The sentence structure loses the clarity and detailed formatting of the original.

Correct translation:
والیٹ کے لیے نیا پاس فریز درج کریں۔&lt;br/&gt; براہ کرم &lt;b&gt;دس یا اس سے زیادہ بے ترتیب حروف&lt;/b&gt;، یا &lt;b&gt;آٹھ یا اس سے زیادہ الفاظ&lt;/b&gt; کا پاس فریز استعمال کریں۔
```

```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>پرس کے لئے پرانا پاسفریج اور نیا پاسفریز درج کریں۔</translation>
    
YES
The translation contains two issues:
1. The word "پرس" is an uncommon and unclear Urdu word for wallet; the standard term "والیٹ" is preferred.
2. The translation says "پاسفریج" for "passphrase" in the first instance, which is a typo; it should be "پاسفریز" in both cases.

Correct translation:
والیٹ کے لیے پرانا پاسفریز اور نیا پاسفریز درج کریں۔
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>بٹوے کے ڈکرپشن کے لیے درج کیا گیا پرانا پاس فریز غلط ہے۔ اس میں ایک خالی کریکٹر ہے (یعنی - ایک صفر بائٹ)۔ اگر پاس فریز 25.0 سے پہلے اس سافٹ ویئر کے ورژن کے ساتھ سیٹ کیا گیا تھا، تو براہ کرم صرف حروف کے ساتھ دوبارہ کوشش کریں — لیکن شامل نہیں — پہلے خالی کریکٹر۔</translation>
    
YES
There are minor issues with terminology and clarity:

1. "null character" should be translated as "نَل کریکٹر" rather than "خالی کریکٹر". In computing, "خالی" may be interpreted as "empty" or "blank", which is not the same as "null/نَل".
2. The translation for "up to — but not including — the first null character" should be clearer. The Urdu dash is potentially unclear for readers; better to paraphrase for accuracy.
3. The punctuation in " — لیکن شامل نہیں — " is awkward. The phrase is not idiomatic.
4. The format specifiers and the structure are correctly preserved.

Correct translation:
بٹوے کو ڈکرپٹ کرنے کے لیے جو پرانا پاس فریز درج کیا گیا ہے وہ غلط ہے۔ اس میں ایک نَل کریکٹر (یعنی صفر بائٹ) شامل ہے۔ اگر پاس فریز اس سافٹ ویئر کے 25.0 سے پچھلے ورژن کے ساتھ سیٹ کیا گیا تھا تو براہ مہربانی صرف پہلے نَل کریکٹر تک کے حروف کے ساتھ دوبارہ کوشش کریں، مگر اس نَل کریکٹر کو شامل نہ کریں۔
```

```
        <source>Banned Until</source>
        <translation>تک پابندی عائد</translation>
    
YES
The translation "تک پابندی عائد" is inaccurate and awkward. It literally means "ban imposed until," which is not natural or clear in Urdu. A more accurate and idiomatic translation would be:
"پابندی کی مدت" or "پابندی تک" or "پابندی کی آخری تاریخ"

Correct translation:
پابندی تک
```

```
        <source>Runaway exception</source>
        <translation>بھگوڑے رعایت</translation>
    
YES
The translation is inaccurate. "Runaway exception" refers to an unhandled or unexpected software error, not "بھگوڑے رعایت" which incorrectly means "runaway discount" or "runaway concession." The correct translation for a software context would be:

Correct translation:
غیر متوقع استثنا

or more descriptively:

غیر قابو شدہ استثنا
```

```
        <source>Show general overview of wallet</source>
        <translation>پرس کا عمومی جائزہ دکھائیں</translation>
    
YES
The word "پرس" is a possible translation for "wallet", but it is not commonly used in modern Urdu for digital wallets or Bitcoin context—"والیٹ" is used instead. Otherwise, the translation is accurate and non-problematic.

Correct translation:
والیٹ کا عمومی جائزہ دکھائیں
```

```
        <source>About %1</source>
        <translation>معلومات%1</translation>
    
YES
There is a whitespace formatting issue: there should be a space between "معلومات" and "%1".

Correct translation:
%1 کے بارے میں
or, if sticking closer to the original structure:
‏%1 کے بارے میں

Alternatively, if you want to use "معلومات", it should be:
‏%1 کے بارے میں معلومات

But the direct translation of "About %1" is:
‏%1 کے بارے میں
```

```
        <source>Modify configuration options for %1</source>
        <translation>%1 اختیارات کے لئےترتیب ترمیم کریں</translation>
    
YES
There is a spacing issue in the translation: "کے لئےترتیب" lacks a space between "لئے" and "ترتیب". Additionally, the overall phrasing is awkward. A better translation would be:

%1 کی ترتیب کے اختیارات میں ترمیم کریں

So the corrected translation is:

%1 کی ترتیب کے اختیارات میں ترمیم کریں
```

```
        <source>Backup Wallet…</source>
        <translation> بیک اپ والیٹ…</translation>
    
YES
There is an unnecessary leading space in the translation. The translation should not start with a space.

Correct translation:
بیک اپ والیٹ…
```

```
        <source>Change Passphrase…</source>
        <translation> بیک اپ والیٹ…</translation>
    
YES
The translation is incorrect. The source text refers to changing the wallet passphrase, but the translation means "Backup Wallet…". Additionally, there is an unnecessary space at the start.

Correct translation:
پاس فریز تبدیل کریں…
```

```
        <source>Sign message…</source>
        <translation>سائن اور پیغام…</translation>
    
YES
The translation "سائن اور پیغام…" means "sign and message...", which is incorrect. The correct translation for "Sign message…" (which means to sign a message, as in digital signing) should be:

پیغام پر دستخط کریں…

The word "اور" (which means "and") is not appropriate here.
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>اپنے ویکیپیڈیا پتوں کے ساتھ پیغامات پر دستخط کریں تاکہ آپ ان کے مالک ہوں</translation>
    
YES
The translation incorrectly uses "ویکیپیڈیا" which means "Wikipedia" instead of "بٹ کوائن" for "Bitcoin". Additionally, the last part is awkwardly phrased; it should convey "to prove you own them".

Correct translation:
اپنے بٹ کوائن پتوں کے ساتھ پیغامات پر دستخط کریں تاکہ آپ ثابت کر سکیں کہ آپ ان کے مالک ہیں۔
```

```
        <source>Open URI…</source>
        <translation>کھولیں اور یو آر آئی…</translation>
    
YES
The translation "کھولیں اور یو آر آئی…" means "Open and URI…", which incorrectly introduces an "اور" ("and") and is not a direct translation of "Open URI…". 

Correct translation:
یو آر آئی کھولیں…
```

```
        <source>Close Wallet…</source>
        <translation>پرس بند کریں…</translation>
    
YES
The translation uses "پرس" for "Wallet," which is understandable but not the most widely used or accurate term for "Wallet" in the context of Bitcoin in Urdu. The term "والیٹ" (phonetic transliteration of "Wallet") is commonly used in the cryptocurrency context. Also, "بند کریں" is correct for "Close", and the ellipsis "…" is properly carried over.

Correct translation:
والیٹ بند کریں…
```

```
        <source>File</source>
        <translation>اور فائل</translation>
    
YES
The translation "اور فائل" means "and file" in Urdu, which is incorrect and adds an extra word not present in the source. The translation should simply be "فائل".

Correct translation:
فائل
```

```
        <source>Settings</source>
        <translation>اور ترتیبات</translation>
    
YES
The translation "اور ترتیبات" means "and settings" in Urdu, but the correct translation for "Settings" alone is "ترتیبات". The word "اور" ("and") is extraneous.

Correct translation:
ترتیبات
```

```
        <source>Help</source>
        <translation>اور مدد</translation>
    
YES
The translation "اور مدد" means "and help", which is incorrect. The correct translation for "Help" is simply "مدد".

Correct translation:
مدد
```

```
        <source>Syncing Headers (%1%)…</source>
        <translation> '%1%' ہیڈرز کی مطابقت پذیری</translation>
    
YES
There are issues with both punctuation/format and naturalness. The percent signs (%) in "%1%" should not be present in the translation as "%1" is a format specifier, and the ellipsis (…) at the end of the source is missing in the translation. Also, the translation is slightly unnatural in Urdu.

Correct translation:
ہیڈرز کی مطابقت پذیری (%1)…
```

```
        <source>Synchronizing with network…</source>
        <translation>نیٹ ورک کے ساتھ ہم آہنگ ہو کر</translation>
    
YES
The translation is not fully accurate and omits the ellipsis, which indicates the process is ongoing. The correct translation should preserve both the sense of ongoing synchronization and the ellipsis.

Correct translation:
نیٹ ورک کے ساتھ ہم آہنگی کر رہا ہے…
```

```
        <source>Connecting to peers…</source>
        <translation>ساتھیوں سے منسلک کرنے</translation>
    
YES
The translation "ساتھیوں سے منسلک کرنے" is slightly inaccurate and unidiomatic. The infinitive "کرنے" implies "to connect to," rather than the ongoing action "Connecting." Also, an ellipsis "…" is missing.

Correct translation:
ساتھیوں سے منسلک ہو رہا ہے…
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>ادائیگی کی درخواست کریں: ( کوئیک رسپانس ( کیو۔آر ) کوڈ اور بٹ کوائن ( یونیورسل ادائیگیوں کا نظام) کے ذریعے سے</translation>
    
YES
The translation is somewhat problematic:
- The original says "(generates QR codes and bitcoin: URIs)", but the translation changes the meaning by expanding "bitcoin: URIs" to "بٹ کوائن ( یونیورسل ادائیگیوں کا نظام)". That is not a correct representation of the term "bitcoin: URIs", which refers to the URI scheme for Bitcoin and not a general system for universal payments.
- The parentheses and colons are also not used consistently.
- "Request payments" is rendered as "ادائیگی کی درخواست کریں:"; the colon is unnecessary.
- There are some minor readability and flow issues as well.

Correct translation:
ادائیگیوں کی درخواست کریں (کیو آر کوڈز اور بٹ کوائن: یو آر آئیز تیار کرتا ہے)
```

```
        <source>Catching up…</source>
        <translation>پکڑنا</translation>
    
YES  
The translation "پکڑنا" literally means "to catch", not "catching up" in the sense of synchronizing or catching up to the latest data/blockchain. The correct Urdu translation in the context of Bitcoin (catching up to the latest block or syncing) would be closer to "ہم آہنگی ہو رہی ہے" or "تازہ کاری کی جارہی ہے".

Correct translation:  
ہم آہنگی ہو رہی ہے…
```

```
        <source>Last received block was generated %1 ago.</source>
        <translation>آخری موصول شدہ 1 '%1' پہلے تیار کیا گیا تھا۔</translation>
    
YES
There is an error in the translation: The "1" is extraneous before "%1", and '%1' should not be surrounded by single quotes. The order of the words is also a bit awkward in Urdu.

Correct translation:
آخری موصول شدہ بلاک %1 پہلے تیار کیا گیا تھا۔
```

```
        <source>Receiving addresses</source>
        <translation>اور پتے وصول کرنا</translation>
    
YES
The translation is incorrect. The provided translation "اور پتے وصول کرنا" means "and to receive addresses," which is not a correct translation for "Receiving addresses." The correct translation should reflect the plural noun "Receiving addresses" in the context of Bitcoin wallet addresses meant for receiving funds.

Correct translation:
وصولی کے پتے
```

```
        <source>Zoom</source>
        <translation>بغور جائزہ لینا</translation>
    
YES
The translation "بغور جائزہ لینا" means "to examine closely" or "to scrutinize," which doesn't accurately reflect the meaning of "Zoom" in the context of user interfaces or graphics, where "zoom" refers to changing the scale of the view.

Correct translation:
زوم کریں
```

```
        <source>Date: %1
</source>
        <translation>%1' تاریخ۔
</translation>
    
YES
The translation is inaccurate and awkward. The placement of %1 is incorrect, and the use of the apostrophe (') is unnecessary in Urdu. The correct translation should be:

Correct translation:
تاریخ: %1

This preserves the order and format of the source text.
```

```
        <source>Amount: %1
</source>
        <translation>%1' مقدار
</translation>
    
YES
The placement of %1 is incorrect and there is an unnecessary apostrophe. The correct translation preserves the format specifier and matches the order of words in Urdu.

Correct translation:
مقدار: %1
```

```
        <source>Wallet: %1
</source>
        <translation>%1' والیٹ
</translation>
    
YES
The Urdu translation improperly places the format specifier (%1) before "والیٹ" and uses an apostrophe after %1, which is unnecessary and incorrect in Urdu. Also, the translation reverses the order: in Urdu, the term "والیٹ" (Wallet) should precede the variable, and the line break should be preserved at the end.

Correct translation:
والیٹ: %1
```

```
        <source>Type: %1
</source>
        <translation>1 %1'قسم
</translation>
    
YES
The translation is problematic:
- The order is incorrect; "قسم: %1" is more natural.
- There is an erroneous "1" at the beginning and misplaced punctuation/apostrophe.
- The format specifier %1 must appear exactly as in the source.

Correct translation:
قسم: %1
```

```
        <source>Label: %1
</source>
        <translation>%1'لیبل
</translation>
    
YES
There is a formatting issue: the translation puts '%1' at the start without a space and does not include the colon. The order should match the source, with the word 'لیبل' first, then a colon, a space, and then '%1'.

Correct translation:
لیبل: %1
```

```
        <source>Address: %1
</source>
        <translation>%1' پتہ
</translation>
    
YES
The translation is incorrect in word order and format. The correct translation should be: 
پتہ: %1

Explanation: In Urdu, the word "پتہ" (address) should precede the placeholder %1, matching the format and structure of the English source. The current translation places %1 before the word, and uses an incorrect apostrophe, which is a formatting issue.
```

```
        <source>HD key generation is &lt;b&gt;enabled&lt;/b&gt;</source>
        <translation>درجہ بندی کا تعین کرنے والی ایچ۔ڈی کلیدی جنریشن &lt;b&gt;فعال&lt;/b&gt; ہے</translation>
    
YES
The translation is overly verbose and somewhat inaccurate. The phrase "درجہ بندی کا تعین کرنے والی ایچ۔ڈی کلیدی جنریشن" literally means "HD key generation that determines classification," which misinterprets "HD" (Hierarchical Deterministic) as "determining classification." Additionally, the translation is wordy and deviates from the source's concise language.

Correct translation:
ایچ ڈی کلید جنریشن &lt;b&gt;فعال&lt;/b&gt; ہے
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>درجہ بندی کا تعین کرنے والی ایچ۔ ڈی کلیدی جنریشن&lt;b&gt; غیر فعال&lt;/b&gt; ہے</translation>
    
YES
The translation is inaccurate. The English sentence means "HD key generation is disabled," with "HD" referring to "Hierarchical Deterministic" (a cryptocurrency wallet term). The Urdu translation incorrectly adds "درجہ بندی کا تعین کرنے والی" (classification determining), which is unnecessary and potentially confusing. Also, the word order and phrasing are awkward.

Correct translation:
ایچ ڈی کلید کی تخلیق &lt;b&gt;غیر فعال&lt;/b&gt; ہے
```

```
        <source>(un)select all</source>
        <translation>سب کو غیر منتخب کریں</translation>
    
YES
The translation only covers "Unselect all" ("سب کو غیر منتخب کریں") and omits the "(select all)" meaning of the source phrase, making it incomplete.

Correct translation:
سب کو منتخب یا غیر منتخب کریں
```

```
        <source>Copy label</source>
        <translation>کاپی اور لیبل</translation>
    
YES
The translation "کاپی اور لیبل" means "Copy and label," which adds the word "and" (اور) not present in the source. The correct translation for "Copy label" should be concise and accurate.

Correct translation:
لیبل نقل کریں
```

```
        <source>Copy amount</source>
        <translation>کاپی اور رقم</translation>
    
YES
The translation is incorrect. "کاپی اور رقم" translates to "Copy and amount", which is not accurate. The correct translation for "Copy amount" is "رقم نقل کریں".

Correct translation:
رقم نقل کریں
```

```
        <source>(%1 locked)</source>
        <translation>مقفل'%1</translation>
    
YES
There is a formatting issue. The Urdu translation has the percentage specifier %1 and the word "مقفل" (locked) in the wrong order, and single quotation marks are misplaced. It should match the source format: (%1 locked).

Correct translation:
(%1 مقفل)
```

```
        <source>Creating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the create wallet progress window which indicates to the user which wallet is currently being created.</extracomment>
        <translation>والیٹ بنانا &lt;b&gt; %1&lt;/b&gt;</translation>
    
YES
The translation omits the trailing ellipsis (… ) which is present in the source, and there's an unnecessary space after "&lt;b&gt;". 

Correct translation:
والیٹ تیار کیا جا رہا ہے &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Loading wallets…</source>
        <extracomment>Descriptive text of the load wallets progress window which indicates to the user that wallets are currently being loaded.</extracomment>
        <translation>اپکا والٹ لوڈ ہورہا ہے </translation>
    
YES
The translation "اپکا والٹ لوڈ ہورہا ہے" means "Your wallet is being loaded", which is singular and refers to only one wallet and also uses the informal 'you'. The original text refers to multiple wallets ("wallets…"), and the translation should reflect that plurality, while also keeping the ellipsis ("…") for consistency with the source. Additionally, the translation omits the ellipsis.

Correct translation:
والیٹس لوڈ ہو رہے ہیں…
```

```
        <source>Label</source>
        <translation>چٹ</translation>
    
YES
The translation "چٹ" is incorrect. "چٹ" means "note" or "slip" in Urdu, and is not an appropriate translation for "Label" in the context of Bitcoin or general UI terminology.

Correct translation:
لیبل
```

```
        <source>calculating…</source>
        <translation>حساب لگانا</translation>
    
YES
The translation "حساب لگانا" means "calculating" as a verb ("to calculate" or "applying calculation"), but the English source "calculating…" is the present continuous, indicating an ongoing action ("in the process of calculating"). A better translation to reflect the ongoing nature would be:
"حساب کیا جا رہا ہے…"

Correct translation:
حساب کیا جا رہا ہے…
```

```
        <source>Main</source>
        <translation>اور مرکزی</translation>
    
YES
The translation "اور مرکزی" means "and central" or "and main", which is not an accurate translation of "Main". The correct Urdu translation for "Main" in this context (as a menu/tab or section title) is "اہم" or "مرکزی" (without the "اور", which means "and"). "اور" is incorrect here.

Correct translation:
اہم
or
مرکزی
```

```
        <source>Reset Options</source>
        <translation>اور دوبارہ ترتیب دینے کے اختیارات</translation>
    
YES
The translation is incorrect and ungrammatical. "اور دوبارہ ترتیب دینے کے اختیارات" means "and the options to reset," which doesn't make sense as a translation of "Reset Options." It adds the word "and," which is not present in the source, and is awkwardly phrased.

Correct translation:
اختیارات کو ری سیٹ کریں

or simply:
دوبارہ ترتیب دینے کے اختیارات
```

```
        <source>Enable coin control features</source>
        <translation>سکے اور کنٹرول کی خصوصیات کو فعال کریں۔</translation>
    
YES
The translation inaccurately splits "coin control" into "سکے اور کنٹرول" (coins and control), which changes the intended meaning. "Coin control" is a technical term in Bitcoin referring to features for manually selecting transaction inputs. The translation should keep the phrase unified and accurately reflect the technical context.

Correct translation:
کوئن کنٹرول فیچرز کو فعال کریں۔
```

```
        <source>Information</source>
        <translation>اور معلومات</translation>
    
YES  
The translation "اور معلومات" means "and information" in Urdu, which is incorrect for "Information". The correct translation should be "معلومات".  

Correct translation:  
معلومات
```

```
        <source>Peers</source>
        <translation>اور فریق</translation>
    
YES
The translation "اور فریق" means "and party/side", which is incorrect for the English term "Peers" in the context of Bitcoin, where "Peers" refers to other nodes or participants on the network.

Correct translation:
ہم منصب
```

```
        <source>Disconnect</source>
        <translation>اور منقطع کریں۔</translation>
    
YES
The translation "اور منقطع کریں۔" means "And disconnect." The addition of "اور" ("and") is unnecessary and incorrect here. Also, the translation uses a full stop; in software UI context, punctuation is often omitted unless present in the source.

Correct translation:
منقطع کریں
```

```
        <source>Amount:</source>
        <translation>اور رقم</translation>
    
YES
The translation "اور رقم" is incorrect for "Amount:". "اور" means "and", so the translation reads as "and amount", which is not correct. Also, the colon ':' from the source is missing in the translation.

Correct translation:
رقم:
```

```
        <source>Message:</source>
        <translation>اور پیغام</translation>
    
YES
The translation is incorrect. "اور پیغام" means "and message" or "more messages". The correct translation for "Message:" is:

پیغام:

Correct translation:
پیغام:
```

```
        <source>Copy label</source>
        <translation>کاپی اور لیبل</translation>
    
YES
The translation "کاپی اور لیبل" means "Copy and label," which adds the word "and" (اور) not present in the source. The correct translation for "Copy label" should be concise and accurate.

Correct translation:
لیبل نقل کریں
```

```
        <source>Copy amount</source>
        <translation>کاپی اور رقم</translation>
    
YES
The translation is incorrect. "کاپی اور رقم" translates to "Copy and amount", which is not accurate. The correct translation for "Copy amount" is "رقم نقل کریں".

Correct translation:
رقم نقل کریں
```

```
        <source>per kilobyte</source>
        <translation>فی کلو بائٹ(kb)</translation>
    
YES
There are two main issues:
1. The translation uses both Urdu script and English "(kb)" which is not standard and inconsistent.
2. "کلو بائٹ" is correct for 'kilobyte'; however, adding "(kb)" is unnecessary unless it's also in the original.

Correct translation:
فی کلو بائٹ
```

```
        <source>Copy label</source>
        <translation>کاپی اور لیبل</translation>
    
YES
The translation "کاپی اور لیبل" means "Copy and label," which adds the word "and" (اور) not present in the source. The correct translation for "Copy label" should be concise and accurate.

Correct translation:
لیبل نقل کریں
```

```
        <source>Copy amount</source>
        <translation>کاپی اور رقم</translation>
    
YES
The translation is incorrect. "کاپی اور رقم" translates to "Copy and amount", which is not accurate. The correct translation for "Copy amount" is "رقم نقل کریں".

Correct translation:
رقم نقل کریں
```

```
        <source>Copy transaction ID</source>
        <translation>لین دین اور شناخت کی تفصیلات(ID) کاپی کریں۔</translation>
    
YES
The translation adds unnecessary detail ("اور شناخت کی تفصیلات" meaning "and identity details") and does not directly correspond to the actual source phrase "Copy transaction ID". Also, the format "(ID)" is awkward.

Correct translation:
ٹرانزیکشن آئی ڈی کاپی کریں۔
```
</details>

Number of issues: 61.
