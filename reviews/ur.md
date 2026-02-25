# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>ur</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bur%5D%20request)


<!-- cache_translation_check_ur_69c3948dbabd12a0d6958b99ff97483048e7bffbb1f5e6881c94ab3a8104c48f -->
```
        <source>&amp;Copy</source>
        <translation>نقل</translation>
    
ERR
The Urdu word "نقل" correctly means "Copy", but the source contains a single shortcut marker "&" which must be preserved in the translation. The translation is missing the "&".

Correct translation (include the ampersand exactly once), for example:
&نقل
```

<!-- cache_translation_check_ur_d08e72d2ca811e3007c1d2013927e9644cb1c4ddc0a492f4da283de26a59fec4 -->
```
        <source>C&amp;lose</source>
        <translation>بند</translation>
    
ERR
The Urdu translation is correct semantically ("بند" = "Close") but it's missing the required shortcut ampersand. The source contains a single & (C&amp;lose) to mark the accelerator key; the translation must also include exactly one &.

Correct translation:
&بند
```

<!-- cache_translation_check_ur_f125f1aa972cab44ac49995ab859c666d786dad9cb27ceb90164afab72b84cf9 -->
```
        <source>&amp;Export</source>
        <translation>برآمد</translation>
    
ERR
The translation is missing the mnemonic ampersand (&) present in the source. The ampersand should appear exactly once in the translation to indicate the shortcut key.

Correct translation:
&amp;برآمد
```

<!-- cache_translation_check_ur_a9ee13129da56840646dc393c327e52f5bcc75667d861aeb07987ae25bfc0496 -->
```
        <source>&amp;Delete</source>
        <translation>ڈیلیٹ

 </translation>
    
ERR
The translation is missing the required shortcut marker (&) and contains extra newline/whitespace characters. The source has a single '&' which must appear exactly once in the translation. Also keep the translation on one line without stray spaces.

Correct translation (one-line, with shortcut marker):
&حذف

(Alternatively you can use "&ڈیلیٹ" if you prefer the loanword "ڈیلیٹ".)
```

<!-- cache_translation_check_ur_db64a726a05c702ea8468126c217ac96d374ce39f8a46715ddb41dadd5999bdf -->
```
        <source>Choose the address to send coins to</source>
        <translation>کوئین وصول کرنے والے کا پتہ</translation>
    
ERR
The translation does not accurately reflect the source text. The source asks the user to select or choose an address to send coins to, but the translation reads "The address of the coin receiver," which is more of a description than an instruction or choice prompt.

Correct translation:
"سکے بھیجنے کے لیے پتہ منتخب کریں"
```

<!-- cache_translation_check_ur_9b8f5248de3ac59650b2740592cc71d12a7a1b41638bb78a6b1974eec3588627 -->
```
        <source>Choose the address to receive coins with</source>
        <translation>کوئین وصول کرنے والے کا پتہ</translation>
    
ERR
The translation omits the imperative "Choose" and does not convey the user's action of selecting an address. The correct translation should retain the instruction to choose/select.

Correct translation:
سکے وصول کرنے کے لیے پتہ منتخب کریں
```

<!-- cache_translation_check_ur_65fa5059596cbcbb12b7b80b8dcee1d500fdbff3c821153965f1bfbb6f8b145b -->
```
        <source>C&amp;hoose</source>
        <translation>چوز کریں

 </translation>
    
ERR
Problems:
- The translation is missing the required single '&' shortcut marker from the source.
- It contains extra whitespace/newline at the end.
- It uses an English loanword "چوز کریں" rather than a more natural Urdu phrase.

Corrected translation (include exactly one & and no extra spaces/newlines):
&منتخب کریں
```

<!-- cache_translation_check_ur_f77d856ae69ce505e0a318782737ad70e7a18f007aa541931b9f6911e42da4b8 -->
```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>یہ آپ کے ادائیگی بھیجنے کے لئے بٹ کوائن ایڈریس ہیں.سکے بھیجنے سے پہلے ہمیشہ رقم اور وصول کنندہ پتہ چیک کریں۔</translation>
    
ERR
There are minor grammatical errors and spacing issues in the Urdu translation:
- "آپ کے ادائیگی بھیجنے کے لئے بٹ کوائن ایڈریس ہیں." is awkward and should be "یہ آپ کے بٹ کوائن ایڈریس ہیں جنہیں ادائیگی بھیجنے کے لیے استعمال کیا جاتا ہے۔"
- There is a missing space after the period/full stop.
- "پتہ" should be "پتہ" but "ایڈریس" may be more commonly understood for "address"; both are acceptable but "پتہ" fits the sentence better.

Correct translation:
یہ آپ کے بٹ کوائن ایڈریس ہیں جنہیں ادائیگی بھیجنے کے لیے استعمال کیا جاتا ہے۔ سکے بھیجنے سے پہلے ہمیشہ رقم اور وصول کنندہ کا پتہ چیک کریں۔
```

<!-- cache_translation_check_ur_ea6e7df2778affed127d4424fd944b12e76b7270abb782253974c0bb981c1aca -->
```
        <source>Unlock wallet</source>
        <translation>بستہ کھولیں</translation>
    
ERR
The Urdu word "بستہ" means "bag" or "briefcase", not "wallet". The correct word for "wallet" in Urdu is "پرس" or "والیٹ". Also, "کھولیں" is a polite/plural imperative, which is fine, but the translation should accurately reflect "Unlock wallet".

Correct translation:
والیٹ ان لاک کریں
or
پرس کو ان لاک کریں
```

<!-- cache_translation_check_ur_732a1495b62183499f3f2bf43168d54f44da54c86a35bfdfc698b8b32862f224 -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>پرس کے لئے نیا پاسفریج درج کریں۔ براہ کرم دس یا زیادہ بے ترتیب حرفوں ، یا آٹھ یا زیادہ الفاظ کا پاس فریز استعمال کریں۔</translation>
    
ERR
The translation has several issues:
- "پرس کے لئے" should be "والیٹ کے لیے" (wallet for) to accurately match the terminology.
- "پاسفریج" is a transliteration error; it should be "پاس فریز".
- The translation omits the instruction formatting (&lt;br/&gt; and &lt;b&gt;).
- The sentence structure loses the clarity and detailed formatting of the original.

Correct translation:
والیٹ کے لیے نیا پاس فریز درج کریں۔&lt;br/&gt; براہ کرم &lt;b&gt;دس یا اس سے زیادہ بے ترتیب حروف&lt;/b&gt;، یا &lt;b&gt;آٹھ یا اس سے زیادہ الفاظ&lt;/b&gt; کا پاس فریز استعمال کریں۔
```

<!-- cache_translation_check_ur_4bc7869d0c06b98e92993adae8825f2b57ace30b30b35d79978f378e4da5aa31 -->
```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>پرس کے لئے پرانا پاسفریج اور نیا پاسفریز درج کریں۔</translation>
    
ERR
The translation contains two issues:
1. The word "پرس" is an uncommon and unclear Urdu word for wallet; the standard term "والیٹ" is preferred.
2. The translation says "پاسفریج" for "passphrase" in the first instance, which is a typo; it should be "پاسفریز" in both cases.

Correct translation:
والیٹ کے لیے پرانا پاسفریز اور نیا پاسفریز درج کریں۔
```

<!-- cache_translation_check_ur_4d6ec7d8233ee6d751beaaae741f7d8041d8ec0d695a17332fd6cd594fb04001 -->
```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>بٹوے کے ڈکرپشن کے لیے درج کیا گیا پرانا پاس فریز غلط ہے۔ اس میں ایک خالی کریکٹر ہے (یعنی - ایک صفر بائٹ)۔ اگر پاس فریز 25.0 سے پہلے اس سافٹ ویئر کے ورژن کے ساتھ سیٹ کیا گیا تھا، تو براہ کرم صرف حروف کے ساتھ دوبارہ کوشش کریں — لیکن شامل نہیں — پہلے خالی کریکٹر۔</translation>
    
ERR
There are minor issues with terminology and clarity:

1. "null character" should be translated as "نَل کریکٹر" rather than "خالی کریکٹر". In computing, "خالی" may be interpreted as "empty" or "blank", which is not the same as "null/نَل".
2. The translation for "up to — but not including — the first null character" should be clearer. The Urdu dash is potentially unclear for readers; better to paraphrase for accuracy.
3. The punctuation in " — لیکن شامل نہیں — " is awkward. The phrase is not idiomatic.
4. The format specifiers and the structure are correctly preserved.

Correct translation:
بٹوے کو ڈکرپٹ کرنے کے لیے جو پرانا پاس فریز درج کیا گیا ہے وہ غلط ہے۔ اس میں ایک نَل کریکٹر (یعنی صفر بائٹ) شامل ہے۔ اگر پاس فریز اس سافٹ ویئر کے 25.0 سے پچھلے ورژن کے ساتھ سیٹ کیا گیا تھا تو براہ مہربانی صرف پہلے نَل کریکٹر تک کے حروف کے ساتھ دوبارہ کوشش کریں، مگر اس نَل کریکٹر کو شامل نہ کریں۔
```

<!-- cache_translation_check_ur_f988ee561cc50117f60286d6c3fbef8043842f06f6c04b679b3007818dcd0428 -->
```
        <source>Banned Until</source>
        <translation>تک پابندی عائد</translation>
    
ERR
The translation "تک پابندی عائد" is inaccurate and awkward. It literally means "ban imposed until," which is not natural or clear in Urdu. A more accurate and idiomatic translation would be:
"پابندی کی مدت" or "پابندی تک" or "پابندی کی آخری تاریخ"

Correct translation:
پابندی تک
```

<!-- cache_translation_check_ur_b9d0c1c219fbf13c2503ab31b96c967ad46d22e9d460de4db83e3548a78b25c5 -->
```
        <source>Runaway exception</source>
        <translation>بھگوڑے رعایت</translation>
    
ERR
The translation is inaccurate. "Runaway exception" refers to an unhandled or unexpected software error, not "بھگوڑے رعایت" which incorrectly means "runaway discount" or "runaway concession." The correct translation for a software context would be:

Correct translation:
غیر متوقع استثنا

or more descriptively:

غیر قابو شدہ استثنا
```

<!-- cache_translation_check_ur_fb9ba24e9b278c2b20360559663500eaae5076a23236780031a4bfb830ed6c02 -->
```
        <source>Ctrl+W</source>
        <translation>موجودہ ٹیب بند کریں</translation>
    
ERR
The translation provides a descriptive Urdu phrase ("Close the current tab") instead of translating or preserving the keyboard shortcut "Ctrl+W". Keyboard shortcut strings should generally maintain their format unless the convention in the target language is to translate the key names themselves.

Correct translation:
Ctrl+W
```

<!-- cache_translation_check_ur_72a2b3057321c9d0aaeb04ad2cebb3dce51083fccbd22fcfecfa298ba80cb3b9 -->
```
        <source>IPv6</source>
        <comment>network name</comment>
        <extracomment>Name of IPv6 network in peer info</extracomment>
        <translation>"آئی پی وی 6"</translation>
    
ERR
The translation includes unnecessary quotation marks around the term "IPv6". In Urdu, technical terms like "IPv6" should either be left as is or transliterated without surrounding quotes in this context.

Correct translation:
آئی پی وی 6
```

<!-- cache_translation_check_ur_f812bf06a2a0c0cbeed81fa3a857386aad6bd626f3f934b809b48f147c4a8967 -->
```
        <source>Onion</source>
        <comment>network name</comment>
        <extracomment>Name of Tor network in peer info</extracomment>
        <translation>پیاز </translation>
    
ERR
The translation includes a stray trailing space that is not present in the source text. Additionally, while "پیاز" is the literal translation for the vegetable "onion", in a technical context referring to the Tor network, it is often preferred to transliterate the name or keep it as "Onion".

Correct translation:
پیاز
```

<!-- cache_translation_check_ur_a2ca37027e0bae365dce7421c70f2caf494c376aa15d559bbcb9e40cc3f12d48 -->
```
        <source>CJDNS</source>
        <comment>network name</comment>
        <extracomment>Name of CJDNS network in peer info</extracomment>
        <translation>مکمل ریلے</translation>
    
ERR
The translation provided ("مکمل ریلے", which means "Full Relay") is incorrect. "CJDNS" is a specific proper name of a networking protocol/network and should be transliterated or left as is, rather than translated as "Full Relay".

Correct translation:
CJDNS
```

<!-- cache_translation_check_ur_d6ff4ed9e6bf8cb6a34c689b23ef3984d21ed1060391fb8ea1f6b279406454b5 -->
```
        <source>&amp;Overview</source>
        <translation>اور جائزہ</translation>
    
ERR
The translation is incorrect. The source "&Overview" uses "&" to mark a shortcut key; the Urdu translation has no "&" and also incorrectly translates "&" as the word "اور" ("and"), resulting in "اور جائزہ" ("and overview"), which is wrong.

Correct translation (include the shortcut marker exactly once), for example:
&جائزہ
```

<!-- cache_translation_check_ur_3731353e7a76ce85cafb535807727ffc055f1591a9385b28945ce38b5ed2dc10 -->
```
        <source>Show general overview of wallet</source>
        <translation>پرس کا عمومی جائزہ دکھائیں</translation>
    
ERR
The word "پرس" is a possible translation for "wallet", but it is not commonly used in modern Urdu for digital wallets or Bitcoin context—"والیٹ" is used instead. Otherwise, the translation is accurate and non-problematic.

Correct translation:
والیٹ کا عمومی جائزہ دکھائیں
```

<!-- cache_translation_check_ur_4d836b66dd503771094a5d68c0457770544cab1e97a82a5bbd3af0dea1a2bdc2 -->
```
        <source>&amp;Transactions</source>
        <translation>اور لین دین</translation>
    
ERR
The translation incorrectly adds the word "اور" ("and") and does not include the shortcut ampersand. The source "&" is a shortcut marker and should be preserved exactly once in the translation. Also remove the stray word "اور".

Correct translation:
&amp;لین دین
```

<!-- cache_translation_check_ur_fa0ac7d43a191e8b130cbd939580870a6169037b0dd0f07174dd891ed5f04601 -->
```
        <source>E&amp;xit</source>
        <translation>باہر نکلیں</translation>
    
ERR
The translation is missing the ampersand (&) used to mark the shortcut key. The source has "E&amp;xit" (one &), so the translation must include exactly one & as well.

Correct translation example (with & placed before the first letter):
<translation>&باہر نکلیں</translation>
```

<!-- cache_translation_check_ur_3764bcc77910ece3d00fe023152cda6dc50f7f1cee29561f19e91fa7129f0495 -->
```
        <source>&amp;About %1</source>
        <translation>&amp;معلومات%1</translation>
    
ERR
The translation is understandable but has formatting and naturalness issues:
- Missing space before %1 ("&معلومات%1" should have a space: "&معلومات %1").
- More natural Urdu for "About %1" is "%1 کے بارے میں". Also ensure the single & is present exactly once.

Correct translations (choose one, keeping a single &):
- &معلومات %1
or more natural:
- &%1 کے بارے میں
```

<!-- cache_translation_check_ur_c7cfec77910c4771230e7a742eba97e9317e419c34da2403f1c0f1dd88e7c103 -->
```
        <source>Modify configuration options for %1</source>
        <translation>%1 اختیارات کے لئےترتیب ترمیم کریں</translation>
    
ERR
There is a spacing issue in the translation: "کے لئےترتیب" lacks a space between "لئے" and "ترتیب". Additionally, the overall phrasing is awkward. A better translation would be:

%1 کی ترتیب کے اختیارات میں ترمیم کریں

So the corrected translation is:

%1 کی ترتیب کے اختیارات میں ترمیم کریں
```

<!-- cache_translation_check_ur_83f2871d825eeae43c262254ca6cf0fd08e951db6aedbf105d8c4bea7549004e -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>&amp; بیک اپ والیٹ…</translation>
    
ERR
The translation is understandable but slightly awkward and has an extra space after the ampersand. A more natural Urdu UI string would put the ampersand directly before the word and use a clearer phrasing.

Correct translation:
&والیٹ کا بیک اپ…
```

<!-- cache_translation_check_ur_015f74f05a5e5e50a74bf008e88901cabb6d2fc867f9a5b1c8bc27bb78b477d8 -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>&amp; بیک اپ والیٹ…</translation>
    
ERR
The translation is incorrect: "بیک اپ والیٹ" means "backup wallet", not "Change Passphrase". The ampersand exists once (good), but the semantic content is wrong.

Correct translation:
<translation>&amp;پاس فریز تبدیل کریں…</translation>
```

<!-- cache_translation_check_ur_710f71d6ef6461015e4833ceb736eef13d582c1764aed1e4b7679b74dc91aea7 -->
```
        <source>Sign &amp;message…</source>
        <translation>سائن اور پیغام…</translation>
    
ERR
The translator replaced the shortcut ampersand with the Urdu word "اور" (and) and changed the phrase structure. The ampersand must appear exactly once as the accelerator marker, and the meaning should be "Sign message…".

Correct translation (with one &):
پیغام پر &دستخط کریں…
```

<!-- cache_translation_check_ur_b30e706feef6cda8c9810b1b4190a3167af57a1a5adb16179ac152757aa1ac11 -->
```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>اپنے ویکیپیڈیا پتوں کے ساتھ پیغامات پر دستخط کریں تاکہ آپ ان کے مالک ہوں</translation>
    
ERR
The translation incorrectly uses "ویکیپیڈیا" which means "Wikipedia" instead of "بٹ کوائن" for "Bitcoin". Additionally, the last part is awkwardly phrased; it should convey "to prove you own them".

Correct translation:
اپنے بٹ کوائن پتوں کے ساتھ پیغامات پر دستخط کریں تاکہ آپ ثابت کر سکیں کہ آپ ان کے مالک ہیں۔
```

<!-- cache_translation_check_ur_e3b6f250bbff8cb7b87ad1326c6b7677a61d14741003edb3af53f106db020f28 -->
```
        <source>&amp;Verify message…</source>
        <translation>پیغام کی توثیق کریں…</translation>
    
ERR
The translation is correct Urdu but is missing the required shortcut indicator '&' from the source. Also ensure the ellipsis is preserved.

Correct translation:
&amp;پیغام کی توثیق کریں…
```

<!-- cache_translation_check_ur_c93679b8a623c0e779d27e9c8d69777c9c563ba1129c4688d2782fce0af8524f -->
```
        <source>Open &amp;URI…</source>
        <translation>کھولیں اور یو آر آئی…</translation>
    
ERR
The translation wrongly uses the Urdu word "اور" (meaning "and") instead of preserving the mnemonic ampersand. The source uses "&URI" to mark a shortcut; the translation must include a single & (not the word "اور"). Also keep the ellipsis.

Correct translation:
&URI کھولیں…
```

<!-- cache_translation_check_ur_70336a7747381c9ded8cf2eddeec749e7d672fb7bb61b41d6df8de15030120eb -->
```
        <source>Close Wallet…</source>
        <translation>پرس بند کریں…</translation>
    
ERR
The translation uses "پرس" for "Wallet," which is understandable but not the most widely used or accurate term for "Wallet" in the context of Bitcoin in Urdu. The term "والیٹ" (phonetic transliteration of "Wallet") is commonly used in the cryptocurrency context. Also, "بند کریں" is correct for "Close", and the ellipsis "…" is properly carried over.

Correct translation:
والیٹ بند کریں…
```

<!-- cache_translation_check_ur_a8d62c7f57e511a8ed9de9475cff915fd067e8a21923d0a855a5c01a9c6cd91d -->
```
        <source>&amp;File</source>
        <translation>اور فائل</translation>
    
ERR
The translation is incorrect: it reads "اور فائل" ("and file") instead of "File" and it does not include the required shortcut marker (&). Also there is an extra word. 

Correct translation:
&فائل
```

<!-- cache_translation_check_ur_527bdb422c131876144e2ba726aaf586c2f8ebc36d55102063fea1031f2c5f89 -->
```
        <source>&amp;Settings</source>
        <translation>اور ترتیبات</translation>
    
ERR
The translation is incorrect. "اور ترتیبات" reads as "and settings" (with an extra "اور" meaning "and") and it does not include the required single '&' shortcut marker from the source.

Correct translation (with the '&' shortcut included exactly once):
&ترتیبات

Or, if you prefer the ampersand before the second character to choose a different shortcut:
ت&رتیبات
```

<!-- cache_translation_check_ur_164bd6809a0c4e9f93d4df30b51cc42b078af1804605520d2ba48d513c2e165f -->
```
        <source>&amp;Help</source>
        <translation>اور مدد</translation>
    
ERR
The Urdu translation "اور مدد" means "and help" and adds an extra word "اور" (and). It also omits the required shortcut marker "&". 

Correct translation (include the & exactly once), for example:
&مدد
```

<!-- cache_translation_check_ur_9b17a8be8dc3b008c2afcfd7cdf0a36b3f217a1a6e53b6c1b58ac92696e0aff2 -->
```
        <source>Syncing Headers (%1%)…</source>
        <translation> '%1%' ہیڈرز کی مطابقت پذیری</translation>
    
ERR
There are issues with both punctuation/format and naturalness. The percent signs (%) in "%1%" should not be present in the translation as "%1" is a format specifier, and the ellipsis (…) at the end of the source is missing in the translation. Also, the translation is slightly unnatural in Urdu.

Correct translation:
ہیڈرز کی مطابقت پذیری (%1)…
```

<!-- cache_translation_check_ur_a91d9c20693f46e445f8e9637c422543c80372301cbc1c73a16f563a5be4db49 -->
```
        <source>Synchronizing with network…</source>
        <translation>نیٹ ورک کے ساتھ ہم آہنگ ہو کر</translation>
    
ERR
The translation is not fully accurate and omits the ellipsis, which indicates the process is ongoing. The correct translation should preserve both the sense of ongoing synchronization and the ellipsis.

Correct translation:
نیٹ ورک کے ساتھ ہم آہنگی کر رہا ہے…
```

<!-- cache_translation_check_ur_ccaba6e97adab0095d9a1b03b99faef9768bb6410ed18c03da0fb055efd9d43a -->
```
        <source>Connecting to peers…</source>
        <translation>ساتھیوں سے منسلک کرنے</translation>
    
ERR
The translation "ساتھیوں سے منسلک کرنے" is slightly inaccurate and unidiomatic. The infinitive "کرنے" implies "to connect to," rather than the ongoing action "Connecting." Also, an ellipsis "…" is missing.

Correct translation:
ساتھیوں سے منسلک ہو رہا ہے…
```

<!-- cache_translation_check_ur_30ec31766258e07f23a6d454f79c1d9b3dddc0c734c447c9ec328783669c508c -->
```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>ادائیگی کی درخواست کریں: ( کوئیک رسپانس ( کیو۔آر ) کوڈ اور بٹ کوائن ( یونیورسل ادائیگیوں کا نظام) کے ذریعے سے</translation>
    
ERR
The translation is somewhat problematic:
- The original says "(generates QR codes and bitcoin: URIs)", but the translation changes the meaning by expanding "bitcoin: URIs" to "بٹ کوائن ( یونیورسل ادائیگیوں کا نظام)". That is not a correct representation of the term "bitcoin: URIs", which refers to the URI scheme for Bitcoin and not a general system for universal payments.
- The parentheses and colons are also not used consistently.
- "Request payments" is rendered as "ادائیگی کی درخواست کریں:"; the colon is unnecessary.
- There are some minor readability and flow issues as well.

Correct translation:
ادائیگیوں کی درخواست کریں (کیو آر کوڈز اور بٹ کوائن: یو آر آئیز تیار کرتا ہے)
```

<!-- cache_translation_check_ur_4dc9b803379fa5e93348fc6f2b5b727f696b30e029d26fdf256b17d02a8d14b1 -->
```
        <source>&amp;Command-line options</source>
        <translation>اور کمانڈ لائن اختیارات</translation>
    
ERR
The translation incorrectly replaces the shortcut marker "&" with the Urdu word "اور" ("and") and thus removes the required single ampersand. Also a more natural Urdu phrasing would include the possessive particle "کے". 

Correct translation (keep one & for the shortcut):
&کمانڈ لائن کے اختیارات
```

<!-- cache_translation_check_ur_563eb8cb7c0ec4390192ea47620a786740d6e7e265834f6ba785b9730fd1d06e -->
```
        <source>Catching up…</source>
        <translation>پکڑنا</translation>
    
ERR  
The translation "پکڑنا" literally means "to catch", not "catching up" in the sense of synchronizing or catching up to the latest data/blockchain. The correct Urdu translation in the context of Bitcoin (catching up to the latest block or syncing) would be closer to "ہم آہنگی ہو رہی ہے" or "تازہ کاری کی جارہی ہے".

Correct translation:  
ہم آہنگی ہو رہی ہے…
```

<!-- cache_translation_check_ur_fb3e9d7f223f86f59aefda45646f4739c68bbc30cf5a7a27be51607bd24d1025 -->
```
        <source>Last received block was generated %1 ago.</source>
        <translation>آخری موصول شدہ 1 '%1' پہلے تیار کیا گیا تھا۔</translation>
    
ERR
There is an error in the translation: The "1" is extraneous before "%1", and '%1' should not be surrounded by single quotes. The order of the words is also a bit awkward in Urdu.

Correct translation:
آخری موصول شدہ بلاک %1 پہلے تیار کیا گیا تھا۔
```

<!-- cache_translation_check_ur_8c2a323d024bb39eec6aa05cfa4443c61bfbb8b7a1185f99658c7aaf1e99e993 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>PSBT کو &amp;clipboard سے لوڈ کریں...</translation>
    
ERR
Problems:
- Missing space before "سے": the translation has "&clipboardسے" without a space.
- The source uses a single ellipsis character (…) but the translation uses three dots (...). Use the same ellipsis character.
- It's better to transliterate "clipboard" into Urdu script (optional).

Corrected translation:
PSBT کو &کلپ بورڈ سے لوڈ کریں…

(If you prefer to keep "clipboard" in Latin script: "PSBT کو &clipboard سے لوڈ کریں…" with a space and the single ellipsis character.)
```

<!-- cache_translation_check_ur_7f44de51051a863edebc31475cc73e8d219a556ddb6dd4171ed611b2ba48f502 -->
```
        <source>&amp;Sending addresses</source>
        <translation>اور بھیجنے والے پتے</translation>
    
ERR
The translator rendered the ampersand (&) as the Urdu word "اور" (meaning "and"), which changes the meaning. The ampersand is a GUI mnemonic marker and must be kept exactly once. Also the rest of the phrase is fine.

Correct translation:
&amp;بھیجنے والے پتے
```

<!-- cache_translation_check_ur_58121311d14d6eb3430a8c346f878ae6c298e7f77547e591b89a81f58a69c1c2 -->
```
        <source>&amp;Receiving addresses</source>
        <translation>اور پتے وصول کرنا</translation>
    
ERR
The Urdu translation is incorrect. It begins with "اور" (meaning "and") and reads awkwardly ("and receive addresses") and it does not include the required single '&' shortcut marker from the source.

Correct translation (with single & for shortcut):
&amp;وصولی پتے
```

<!-- cache_translation_check_ur_cf6668e5375d837f930448223d68f402a4439310c4a0fbb58f0d97fd46e1fde7 -->
```
        <source>&amp;Mask values</source>
        <translation>قدروں کو چھپائیں</translation>
    
ERR
The Urdu text correctly conveys "hide values" but is missing the required single ampersand (&) for the shortcut key. No other format specifiers or spacing issues.

Correct translation (with ampersand):
&amp;قدروں کو چھپائیں
```

<!-- cache_translation_check_ur_6713eef3b7491f5764d87dc1833865f473b05c468708d35dff18e2edc716799a -->
```
        <source>&amp;Window</source>
        <translation>اور ونڈو</translation>
    
ERR
The translation is incorrect. It adds the Urdu word "اور" (meaning "and") and omits the required shortcut marker '&'. The source is a single menu label "&Window" — the translation should be the Urdu word for "Window" with the '&' included exactly once.

Correct translation:
&amp;ونڈو
```

<!-- cache_translation_check_ur_0890fef4fbca0c57cdc0d842d73354aa882bdb7d3c7be3a154c9295e43f8a60c -->
```
        <source>Zoom</source>
        <translation>بغور جائزہ لینا</translation>
    
ERR
The translation "بغور جائزہ لینا" means "to examine closely" or "to scrutinize," which doesn't accurately reflect the meaning of "Zoom" in the context of user interfaces or graphics, where "zoom" refers to changing the scale of the view.

Correct translation:
زوم کریں
```

<!-- cache_translation_check_ur_ddab3b2573936e5db8b7c6201259f5eb4e37f342c6fe2dc1f4e8ab4969bfaf4c -->
```
        <source>Date: %1
</source>
        <translation>1%1' تاریخ۔
</translation>
    
ERR
The translation contains an extra '1' and an unnecessary apostrophe. Additionally, the format specifier '%1' is malformed as '1%1'.

Correct translation:
تاریخ: %1
```

<!-- cache_translation_check_ur_f77a80a6293fe7110cd804bf629d251fe140633d186e0d6a57ae7532207bddd8 -->
```
        <source>Amount: %1
</source>
        <translation>1%1' مقدار
</translation>
    
ERR
The format specifier is incorrect. The translation includes an extra "1" and a single quote character around the "%1" specifier, and the colon is missing.

Correct translation:
مقدار: %1
```

<!-- cache_translation_check_ur_932d8012b35e617206bc57515c81133c371149a8a25dea2f2c3376d3365da15e -->
```
        <source>Wallet: %1
</source>
        <translation>1%1' والیٹ
</translation>
    
ERR
The translation contains an extra '1' before the format specifier, and the format specifier itself is malformed or improperly handled in the RTL context. In Urdu, the colon should also follow the word 'Wallet'.

Correct translation:
والٹ: %1
```

<!-- cache_translation_check_ur_b564144b415ed5d559681930462359bf7c5fa473020a2a798b1f97d0505a513f -->
```
        <source>Type: %1
</source>
        <translation>1 %1'قسم
</translation>
    
ERR
The translation is problematic:
- The order is incorrect; "قسم: %1" is more natural.
- There is an erroneous "1" at the beginning and misplaced punctuation/apostrophe.
- The format specifier %1 must appear exactly as in the source.

Correct translation:
قسم: %1
```

<!-- cache_translation_check_ur_b056398067569b0a549c34c8ed4b91618b7eb483de1aa5346c32c6bb18cd0b7d -->
```
        <source>Label: %1
</source>
        <translation>1%1'لیبل
</translation>
    
ERR
The translation contains an error in handling the format specifier and the text layout. The specifier `%1` has been corrupted into `1%1`, and the Urdu word for 'Label' is missing or replaced by a transliteration with incorrect punctuation.

Correct translation:
لیبل: %1
```

<!-- cache_translation_check_ur_ba6e2c37415988b7280bdc9be7f0097289a54ee02d6173731fe067deb377fe9e -->
```
        <source>Address: %1
</source>
        <translation>1%1' پتہ
</translation>
    
ERR
The translation contains an incorrect format specifier and an unnecessary apostrophe. The format specifier `%1` has been mangled into `1%1'`. Additionally, there is a stray newline or spacing issue compared to the source.

Correct translation:
پتہ: %1
```

<!-- cache_translation_check_ur_433adf43f81d4d73cbf80cd8e08dc8222a4771e538ccf1edc1939312474d3b87 -->
```
        <source>HD key generation is &lt;b&gt;enabled&lt;/b&gt;</source>
        <translation>درجہ بندی کا تعین کرنے والی ایچ۔ڈی کلیدی جنریشن &lt;b&gt;فعال&lt;/b&gt; ہے</translation>
    
ERR
The translation is overly verbose and somewhat inaccurate. The phrase "درجہ بندی کا تعین کرنے والی ایچ۔ڈی کلیدی جنریشن" literally means "HD key generation that determines classification," which misinterprets "HD" (Hierarchical Deterministic) as "determining classification." Additionally, the translation is wordy and deviates from the source's concise language.

Correct translation:
ایچ ڈی کلید جنریشن &lt;b&gt;فعال&lt;/b&gt; ہے
```

<!-- cache_translation_check_ur_9f60ef30ac05a91ef568cf06e1c6e0b88a4c4fba60e5ef8ed3483d202dea50f8 -->
```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>درجہ بندی کا تعین کرنے والی ایچ۔ ڈی کلیدی جنریشن&lt;b&gt; غیر فعال&lt;/b&gt; ہے</translation>
    
ERR
The translation is inaccurate. The English sentence means "HD key generation is disabled," with "HD" referring to "Hierarchical Deterministic" (a cryptocurrency wallet term). The Urdu translation incorrectly adds "درجہ بندی کا تعین کرنے والی" (classification determining), which is unnecessary and potentially confusing. Also, the word order and phrasing are awkward.

Correct translation:
ایچ ڈی کلید کی تخلیق &lt;b&gt;غیر فعال&lt;/b&gt; ہے
```

<!-- cache_translation_check_ur_7a2145540e698d442724d52d04a38258f343d9a6a300eed48a42ca41b5448d95 -->
```
        <source>(un)select all</source>
        <translation>سب کو غیر منتخب کریں</translation>
    
ERR
The translation only covers "Unselect all" ("سب کو غیر منتخب کریں") and omits the "(select all)" meaning of the source phrase, making it incomplete.

Correct translation:
سب کو منتخب یا غیر منتخب کریں
```

<!-- cache_translation_check_ur_23dc6480cdf08387666510a341a5cab042775344dba86c91513d643de2c33adc -->
```
        <source>&amp;Copy address</source>
        <translation>ایڈریس کاپی کریں۔</translation>
    
ERR
The translation is mostly correct wording-wise, but it is missing the required shortcut ampersand (&) and includes an unnecessary terminal Urdu full stop (۔). The source contains a single '&' which must be present exactly once in the translation. Also avoid adding a period.

Correct translation (ampersand added, no period):
&ایڈریس کاپی کریں
```

<!-- cache_translation_check_ur_bc11306ec248499f17350da76f827f2b3b9e35088f478dff2283a984a72b5cdb -->
```
        <source>Copy &amp;label</source>
        <translation>کاپی اور لیبل</translation>
    
ERR
The translation is incorrect. "کاپی اور لیبل" reads as "copy and label" (using Urdu word "اور" = "and") instead of "Copy label" and it omits the required accelerator ampersand (&). The source uses "&" to mark a shortcut and that must appear exactly once in the translation.

Correct suggestions (include a single & for the shortcut):
- "کاپی &لیبل"
or more natural:
- "&لیبل کی کاپی کریں"
```

<!-- cache_translation_check_ur_19ad5a4ca83c2c2cb0a89b9ea156f41fce43e5822bd7e486012a70ef1bd4ef9f -->
```
        <source>Copy &amp;amount</source>
        <translation>کاپی اور رقم</translation>
    
ERR
The translation "کاپی اور رقم" literally reads "copy and amount" (the word "اور" means "and") which is incorrect. It should mean "Copy amount". Also the source uses a single '&' for the shortcut; the translation must include exactly one '&'.

Correct translations (with a single shortcut marker) — choose one appropriate for your UI convention:
- &کاپی رقم
- &رقم کی کاپی

Both convey "Copy amount" and include exactly one '&'.
```

<!-- cache_translation_check_ur_ed352ec5ebbebf1cafe9939ef0934fbacc58fd5c24af1444f2d26e887115d30e -->
```
        <source>L&amp;ock unspent</source>
        <translation>غیر خرچ شدہ آؤٹ پٹ بند کریں</translation>
    
ERR
Problems:
- The translation is missing the single '&' accelerator marker present in the source.
- Minor grammatical issue: it should include the Urdu object marker "کو" after "آؤٹ پٹ" to be natural.

Suggested correct translation (with one &):
غیر خرچ شدہ آؤٹ پٹ کو &لاک کریں
```

<!-- cache_translation_check_ur_0cad0e18e868f9075032361881952422344aa078a1598744d58b121764fe4c75 -->
```
        <source>&amp;Unlock unspent</source>
        <translation>غیر خرچ شدہ کھولیں</translation>
    
ERR
The translation is missing the required shortcut marker "&" and the Urdu phrasing could be more natural. The source has no format specifiers or extra whitespace issues.

Suggested translation (with single &):
&غیر خرچ شدہ کو انلاک کریں
```

<!-- cache_translation_check_ur_b8269bad5cc4add6251c7c49be905dbcfa4f59ddd240098801d2949435f826dd -->
```
        <source>(%1 locked)</source>
        <translation>مقفل'%1</translation>
    
ERR
There is a formatting issue. The Urdu translation has the percentage specifier %1 and the word "مقفل" (locked) in the wrong order, and single quotation marks are misplaced. It should match the source format: (%1 locked).

Correct translation:
(%1 مقفل)
```

<!-- cache_translation_check_ur_f35039407536052db8ed435c11b4a9e1d44b08e87c9cda948b71d7d559601c62 -->
```
        <source>Creating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the create wallet progress window which indicates to the user which wallet is currently being created.</extracomment>
        <translation>والیٹ بنانا &lt;b&gt; %1&lt;/b&gt;</translation>
    
ERR
The translation omits the trailing ellipsis (… ) which is present in the source, and there's an unnecessary space after "&lt;b&gt;". 

Correct translation:
والیٹ تیار کیا جا رہا ہے &lt;b&gt;%1&lt;/b&gt;…
```

<!-- cache_translation_check_ur_5973fabf0c5931fed0650f18ad3e10ade341c250351cd9c88cf7269d56398f38 -->
```
        <source>Loading wallets…</source>
        <extracomment>Descriptive text of the load wallets progress window which indicates to the user that wallets are currently being loaded.</extracomment>
        <translation>اپکا والٹ لوڈ ہورہا ہے </translation>
    
ERR
The translation "اپکا والٹ لوڈ ہورہا ہے" means "Your wallet is being loaded", which is singular and refers to only one wallet and also uses the informal 'you'. The original text refers to multiple wallets ("wallets…"), and the translation should reflect that plurality, while also keeping the ellipsis ("…") for consistency with the source. Additionally, the translation omits the ellipsis.

Correct translation:
والیٹس لوڈ ہو رہے ہیں…
```

<!-- cache_translation_check_ur_3da8535c4c201b36edd866bc8098465d9ba26dd30caa4ddcaf4206cbcc14dfe2 -->
```
        <source>Migration failed</source>
        <translation>بٹ کوائن کے لیے منتقلی ناکام ہوئی</translation>
    
ERR
The translation adds "بٹ کوائن کے لیے" (for Bitcoin) which is not present in the source text. A more direct and accurate translation is preferred.

Correct translation:
منتقلی ناکام رہی
```

<!-- cache_translation_check_ur_5d51bc5c2b314acc0da4d325ab3ee47762f23d412b8d2b4ad8aa153bcb8b2ce4 -->
```
        <source>Restore wallet message</source>
        <extracomment>Title of message box which is displayed when the wallet is successfully restored.</extracomment>
        <translation>بٹ کوائن کے لیے بٹوے کو بحال کریں</translation>
    
ERR
The Urdu translation includes extra words not present in the source. The source "Restore wallet message" is the title of a message box, whereas the translation says "بٹ کوائن کے لیے بٹوے کو بحال کریں" (Restore wallet for Bitcoin).

Correct translation:
بٹوا بحال کرنے کا پیغام
```

<!-- cache_translation_check_ur_a6fd45dfcc186d66665dd8a67f623e039e7c9ac0e4d3f01ccd8ccbc977008cae -->
```
        <source>&amp;Label</source>
        <translation>چٹ</translation>
    
ERR
Problems:
- The translation "چٹ" is incorrect/unnatural for "Label" in this context; it means "note" or "scratch" and is not the common term for a UI label.
- The source contains a single '&' indicating a mnemonic; the translation must include exactly one '&' as well (it's missing).

Correct translation suggestion (include mnemonic):
&لیبل
```

<!-- cache_translation_check_ur_78bd0e458ed5dd2c4d68a6b134ae7236c7fd0530edd891c2abfda2ec7c959388 -->
```
        <source>&amp;Address</source>
        <translation>پتہ</translation>
    
ERR
The Urdu word "پتہ" correctly translates "Address", but the source contains an ampersand (&) as a shortcut marker which must appear exactly once in the translation. The provided translation is missing it.

Correct translation (include & once):
&پتہ
```

<!-- cache_translation_check_ur_a2c17795ff46fafa08e5c9eb811c1d86db2447f8587a75592231925f90842fa6 -->
```
        <source>Choose data directory</source>
        <translation>ٹ کوائن کے لیے ڈیٹا ڈائریکٹری منتخب کریں</translation>
    
ERR
The Urdu translation includes extra words not present in the source. It translates to "Choose data directory for Bitcoin", whereas the source is simply "Choose data directory".

Correct translation:
ڈیٹا ڈائریکٹری منتخب کریں
```

<!-- cache_translation_check_ur_3c142954b5c5ceb61902024c937ae58102d676ec3600729581b7c1cf5966c8a6 -->
```
        <source>calculating…</source>
        <translation>حساب لگانا</translation>
    
ERR
The translation "حساب لگانا" means "calculating" as a verb ("to calculate" or "applying calculation"), but the English source "calculating…" is the present continuous, indicating an ongoing action ("in the process of calculating"). A better translation to reflect the ongoing nature would be:
"حساب کیا جا رہا ہے…"

Correct translation:
حساب کیا جا رہا ہے…
```

<!-- cache_translation_check_ur_2aefabe7e6e1dc0eba2b3cf1f1df2a6ad9da0ed8d39fc6f68e823aaf634bd1fa -->
```
        <source>&amp;Main</source>
        <translation>اور مرکزی</translation>
    
ERR
The translation is incorrect. It uses the Urdu word "اور" (meaning "and") rather than preserving the ampersand shortcut marker, and the ampersand (&) must appear exactly once to indicate the menu shortcut. Also there is an extra word that shouldn't be there.

Correct translation:
&amp;مرکزی
```

<!-- cache_translation_check_ur_36f4750adabe6959239e68ecde7ba7f241fd3be4441c671e61e76db4f9572df8 -->
```
        <source>Maximum database cache size. Make sure you have enough RAM. A larger cache can contribute to faster sync, after which the benefit is less pronounced for most use cases. Lowering the cache size will reduce memory usage. Unused mempool memory is shared for this cache.</source>
        <extracomment>Tooltip text for Options window setting that sets the size of the database cache. Explains the corresponding effects of increasing/decreasing this value.</extracomment>
        <translation>"بٹ کوائن کے لیے زیادہ سے زیادہ ڈیٹابیس کیش کا سائز۔ یقینی بنائیں کہ آپ کے پاس کافی ریم ہے۔ بڑا کیش تیز سنک کرنے میں مدد کر سکتا ہے، لیکن اس کے بعد زیادہ تر استعمال کے لیے فائدہ کم ہوتا ہے۔ کیش کا سائز کم کرنے سے میموری کا استعمال کم ہوگا۔ غیر استعمال شدہ میمپول میموری اس کیش کے لیے شیئر کی جاتی ہے</translation>
    
ERR
The translation starts with an unnecessary opening quotation mark (") and is missing a closing one. Additionally, the phrase "بٹ کوائن کے لیے" (for Bitcoin) was added at the beginning, which is not present in the source text.

Correct translation:
ڈیٹابیس کیش کا زیادہ سے زیادہ سائز۔ یقینی بنائیں کہ آپ کے پاس کافی ریم (RAM) ہے۔ بڑا کیش تیز سنک (sync) کرنے میں مدد کر سکتا ہے، جس کے بعد زیادہ تر استعمال کے کیسز کے لیے فائدہ کم واضح ہوتا ہے۔ کیش کا سائز کم کرنے سے میموری کا استعمال کم ہوگا۔ غیر استعمال شدہ میمپول میموری اس کیش کے لیے شیئر کی جاتی ہے۔
```

<!-- cache_translation_check_ur_0d4961bc60fee38d1313b43865e782ebb224ba023339dec3efbd5ed5879eef73 -->
```
        <source>Size of &amp;database cache</source>
        <translation>ڈیٹا بیس کیشے کا سائز</translation>
    
ERR
The translation is correct in meaning but it omits the shortcut marker (&) that appears in the source. There are no format specifiers to check. Ensure exactly one & is included in the translation.

Correct translation:
&ڈیٹا بیس کیشے کا سائز
```

<!-- cache_translation_check_ur_7d442416104214d9633ffbe2156ad469102943315c77c397c5fda412171ff938 -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>اسکرپٹ اور تصدیقی دھاگوں کی تعداد</translation>
    
ERR
The translation is understandable Urdu but it omits the required shortcut ampersand (&) present in the source. Also the source uses an ampersand to mark the mnemonic before "verification", so the translation must include a single &. 

Correct translation (with ampersand before تصدیقی):
اسکرپٹ اور &تصدیقی دھاگوں کی تعداد
```

<!-- cache_translation_check_ur_64e6c4c8d84da2bfa5c0f9421c10607bb6a34f9eebb4d9a93aba2103475d9b68 -->
```
        <source>Automatically open the Bitcoin client port on the router. This only works when your router supports PCP or NAT-PMP and it is enabled. The external port could be random.</source>
        <translation>"بٹ کوائن کلائنٹ پورٹ کو روٹر پر خودکار طور پر کھولیں۔ یہ صرف اس وقت کام کرتا ہے جب آپ کا روٹر PCP یا NAT-PMP کو سپورٹ کرتا ہو اور یہ فعال ہو۔ بیرونی پورٹ بے ترتیب ہو سکتا ہے۔</translation>
    
ERR
The translation includes an opening double quotation mark (") at the beginning that is not present in the source text.

Correct translation:
بٹ کوائن کلائنٹ پورٹ کو روٹر پر خودکار طور پر کھولیں۔ یہ صرف اس وقت کام کرتا ہے جب آپ کا روٹر PCP یا NAT-PMP کو سپورٹ کرتا ہو اور یہ فعال ہو۔ بیرونی پورٹ بے ترتیب ہو سکتا ہے۔
```

<!-- cache_translation_check_ur_cf274838cb556b0c61a523818f45c39f2dd5d80eb00ae2d051b8c4ec05e66ad3 -->
```
        <source>Map port using PCP or NA&amp;T-PMP</source>
        <translation>بٹ کوائن کے لیے PCP یا NAT-PMP کا استعمال کرتے ہوئے پورٹ میپ کریں</translation>
    
ERR
The translation includes "بٹ کوائن کے لیے" (for Bitcoin), which is not present in the source text. Additionally, the shortcut key indicator (&amp;) is missing in the translation.

Correct translation:
PCP یا NA&amp;T-PMP کا استعمال کرتے ہوئے پورٹ میپ کریں
```

<!-- cache_translation_check_ur_0d4072a25825358b37522710fb92cd1411802d8c9e92dd3a88af8c64fed8a735 -->
```
        <source>Font in the Overview tab: </source>
        <translation>بٹ کوائن کے لیے اوور ویو ٹیب میں فونٹ"</translation>
    
ERR
The translation includes an extra "بٹ کوائن کے لیے" (for Bitcoin) which is not in the source text, and it ends with a stray quotation mark.

Correct translation:
اوور ویو ٹیب میں فونٹ:
```

<!-- cache_translation_check_ur_5b7b95242d4af55521f118d8f64f570430170e409e3779df525dcecd3678b4cf -->
```
        <source>&amp;Reset Options</source>
        <translation>اور دوبارہ ترتیب دینے کے اختیارات</translation>
    
ERR
Problems:
- The Urdu text "اور دوبارہ ترتیب دینے کے اختیارات" literally reads "and options to reset" — the leading "اور" ("and") is incorrect and changes meaning.
- The translation is missing the single '&' used to mark the shortcut key; the source has one '&' and the translation must include exactly one.
- Wording is awkward; better phrasing is needed.

Correct translation (include single &):
&اختیارات کو ری سیٹ کریں
```

<!-- cache_translation_check_ur_84d6949fffd17e4e904038689cde51c6084bd3c0089153a6eea0e8c896160c2a -->
```
        <source>&amp;Network</source>
        <translation>اور نیٹ ورک</translation>
    
ERR
The source "&Network" uses "&" to mark a keyboard shortcut; the translation incorrectly rendered this as the Urdu word "اور" ("and") and omitted the required "&" shortcut marker. Also avoid adding extra spaces.

Correct translation:
&نیٹ ورک
```

<!-- cache_translation_check_ur_9b6a9a5121d76bcb2d9b56c640c2e8b723bf31a001d1dafd1405abbd0171ce7c -->
```
        <source>MiB</source>
        <translation>بٹ کوائن کے لیے بلاک اسٹوریج کو میبی بائٹ تک پرون کریں</translation>
    
ERR
The translation includes an entire sentence ("Prune block storage for Bitcoin to Mebibyte") instead of just translating the unit "MiB". This will likely break the user interface where only the unit suffix is expected.

Correct translation:
میبی بائٹ
```

<!-- cache_translation_check_ur_c9ceaee6c16b71f3d49650dd789f66de30a39e32b72b95c9966c3ded8b1155df -->
```
        <source>(0 = auto, &lt;0 = leave that many cores free)</source>
        <translation>(بٹ کوائن کے لیے) 0 = خودکار، &lt;0 = اتنی کورز کو سسٹم کے لیے آزاد
 چھوڑیں</translation>
    
ERR
The translation includes "(بٹ کوائن کے لیے)" (for Bitcoin) which is not in the source text and adds unnecessary context. Additionally, there is an unnecessary line break within the translation.

Correct translation:
(0 = خودکار، <0 = اتنی کورز کو آزاد چھوڑیں)
```

<!-- cache_translation_check_ur_7a8a2bcbd861a4a534db742e10e314d1eb0a1bccc2e2d26c05b14f3f824aabb9 -->
```
        <source>This allows you or a third party tool to communicate with the node through command-line and JSON-RPC commands.</source>
        <extracomment>Tooltip text for Options window setting that enables the RPC server.</extracomment>
        <translation>بٹ کوائن کے لیے اس سے آپ یا کوئی تیسری پارٹی کا ٹول نوڈ کے ساتھ کمانڈ لائن اور JSON-RPC کمانڈز کے ذریعے رابطہ کر سکتا ہے۔"</translation>
    
ERR
The translation includes an unnecessary addition "بٹ کوائن کے لیے" (for Bitcoin) at the beginning, which is not in the source text, and it ends with a stray quotation mark.

Correct translation:
اس سے آپ یا کوئی تیسری پارٹی کا ٹول نوڈ کے ساتھ کمانڈ لائن اور JSON-RPC کمانڈز کے ذریعے رابطہ کر سکتا ہے۔
```

<!-- cache_translation_check_ur_d1d273f8ef83eb4296e98360afd45ff7fcc75713716ebcdecae7fb0e095671e4 -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>فیس کو رقم سے خودکار طور پر منہا کریں</translation>
    
ERR
The translation is missing the '&' character, which is used to indicate the shortcut key as per the instructions.

Correct translation:
فیس کو رقم سے &خودکار طور پر منہا کریں
```

<!-- cache_translation_check_ur_cbbd258258fd71ccd7ebc10eabbb5b6536405f088ecd7db4f23079b85a33ff6e -->
```
        <source>Enable coin &amp;control features</source>
        <translation>سکے اور کنٹرول کی خصوصیات کو فعال کریں۔</translation>
    
ERR
Problems:
- The original uses an accelerator marker '&' (before "control"); the Urdu translation omits the '&'. The translation must include exactly one '&'.
- The meaning was changed: "coin &control features" is "coin-control features" (a compound), but the Urdu reads as "سکے اور کنٹرول" ("coin and control"), which is incorrect.

Suggested correct translation (with one '&'):
کوائن &کنٹرول کی خصوصیات کو فعال کریں
```

<!-- cache_translation_check_ur_afc7dd12fd317e072b5ebea43dc5444ad3a44bf30d5d854cf7ca0f49bfc5fc71 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>اور غیر مصدقہ تبدیلی خرچ کریں۔</translation>
    
ERR
Problems:
- The translation begins with "اور" ("and"), which incorrectly adds "and" not present in the source.
- The ampersand (&) used to mark the shortcut key is missing; there should be exactly one &.
- Unnecessary terminal punctuation "۔" (period) is not needed for menu texts.

Suggested correct translation (with shortcut marker):
&غیر مصدقہ تبدیلی خرچ کریں
```

<!-- cache_translation_check_ur_2eca6804dc72543efee7e53832432aed351c33f27a571e6c53caaa28bed65d04 -->
```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>کیا PSBT کنٹرولز دکھانے ہیں۔"</translation>
    
ERR
The translation includes an unnecessary closing double quotation mark at the end.

Correct translation:
کیا PSBT کنٹرولز دکھانے ہیں۔
```

<!-- cache_translation_check_ur_516620b9a687779d4d829ff63f0bf3824e3d2c714ce025eebfd6115e60404eb7 -->
```
        <source>External Signer (e.g. hardware wallet)</source>
        <translation>یرونی دستخط کنندہ (مثلاً ہارڈویئر بٹوا)</translation>
    
ERR
The translation for "External" is misspelled. It should be "بیرونی" (starting with 'ب'), but it is written as "یرونی".

Correct translation:
بیرونی دستخط کنندہ (مثلاً ہارڈویئر بٹوا)
```

<!-- cache_translation_check_ur_c7a2ff4c690ff16ce87936784377d4b6bd9700ccea76ef360cbef00b3d75aa47 -->
```
        <source>Accept connections from outside.</source>
        <translation>باہر سے رابطے قبول کری</translation>
    
ERR
The Urdu translation is grammatically incorrect and incomplete. The word "کری" (kari) is used incorrectly here; it should be "کریں" (karein) to indicate a command or a plural/formal action.

Correct translation:
باہر سے کنکشنز قبول کریں۔
```

<!-- cache_translation_check_ur_bba6333366b8d55ab05f66bac06520337853304c4f20649847615d111140c685 -->
```
        <source>Connect to the Bitcoin network through a SOCKS5 proxy.</source>
        <translation>بٹ کوائن نیٹ ورک سے SOCKS5 پراکسی کے ذریع
ے رابطہ کریں"</translation>
    
ERR
The translation contains an unnecessary line break within a word and an trailing double quote at the end.

Correct translation:
بٹ کوائن نیٹ ورک سے SOCKS5 پراکسی کے ذریعے رابطہ کریں۔
```

<!-- cache_translation_check_ur_8a717d48d241729b9f7a683527aca97ceeb14ffb184fa6e732ad2b7dc52d2ea1 -->
```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>پراکسی کا پورٹ (مثلاً 9050)"</translation>
    
ERR
The translation includes a stray double quote character at the end of the string which is not present in the source.

Correct translation:
پراکسی کا پورٹ (مثلاً 9050)
```

<!-- cache_translation_check_ur_97621b9afae6570295af73929b60c3b123821bac6d4ffd920d4292c35a21d8aa -->
```
        <source>Used for reaching peers via:</source>
        <translation>"ساتھیوں تک رسائی کے لیے استعمال کیا جاتا ہے:</translation>
    
ERR
The translation includes an unnecessary opening quotation mark (`"`) that is not present in the source text.

Correct translation:
ساتھیوں تک رسائی کے لیے استعمال کیا جاتا ہے:
```

<!-- cache_translation_check_ur_e264c3b6a363212efa9abcaba908e199c9b89bcb1ac8d25b5df335078525a88d -->
```
        <source>IPv6</source>
        <translation>"آئی پی وی 6"</translation>
    
ERR
The translation includes unnecessary quotation marks around the term. In technical contexts like this, the name of the protocol should not be quoted.

Correct translation:
آئی پی وی 6
```

<!-- cache_translation_check_ur_4e7a7cbc0d790a51c2bc878fab880083794662e3c0f699f5d6d44203da4bde68 -->
```
        <source>Tor</source>
        <translation>ور"</translation>
    
ERR
The translation is incorrect and includes a stray double quote. "Tor" is a proper noun referring to the anonymity network and should be transliterated as "ٹور" in Urdu. The provided text "ور\"" is missing the initial letter and contains an extra character.

Correct translation:
ٹور
```

<!-- cache_translation_check_ur_6713eef3b7491f5764d87dc1833865f473b05c468708d35dff18e2edc716799a -->
```
        <source>&amp;Window</source>
        <translation>اور ونڈو</translation>
    
ERR
The translation is incorrect. It adds the Urdu word "اور" (meaning "and") and omits the required shortcut marker '&'. The source is a single menu label "&Window" — the translation should be the Urdu word for "Window" with the '&' included exactly once.

Correct translation:
&amp;ونڈو
```

<!-- cache_translation_check_ur_857e4dbfc445030249764015f311ad800676f321d69d78038c331090725d93e8 -->
```
        <source>Show only a tray icon after minimizing the window.</source>
        <translation>"ونڈو کو کم کرنے کے بعد صرف ٹرے آئیکن دکھائیں"</translation>
    
ERR
The translation includes unnecessary quotation marks around the text, which were not present in the source.

Correct translation:
ونڈو کو کم کرنے کے بعد صرف ٹرے آئیکن دکھائیں
```

<!-- cache_translation_check_ur_047a0d252c22607afa277adf82080d875bc89b1583ae7e95a7ab1962f1662857 -->
```
        <source>Whether to show coin control features or not.</source>
        <translation>"کیا سکے کنٹرول فیچرز دکھانے ہیں یا نہیں۔</translation>
    
ERR
The translation includes an unnecessary opening double quote (") at the start of the sentence.

Correct translation:
کیا کوائن کنٹرول فیچرز دکھانے ہیں یا نہیں۔
```

<!-- cache_translation_check_ur_17a0a4aa090b67f6de5e9c9e677ee19fcadea2a8aa9acfe133ff7535a79bb8b4 -->
```
        <source>The configuration file is used to specify advanced user options which override GUI settings. Additionally, any command-line options will override this configuration file.</source>
        <extracomment>Explanatory text about the priority order of instructions considered by client. The order from high to low being: command-line, configuration file, GUI settings.</extracomment>
        <translation>کنفیگریشن فائل کا استعمال اعلیٰ صارف اختیارات کو متعین کرنے کے لیے کیا جاتا ہے جو GUI سیٹنگز کو اوور رائیڈ کرتے ہیں۔ اس کے علاوہ، کوئی بھی کمانڈ لائن اختیارات اس کنفیگریشن فائل کو اوور رائیڈ کریں گے۔"</translation>
    
ERR
The translation includes a stray double quote character at the very end of the sentence which is not present in the source text.

Correct translation:
کنفیگریشن فائل کا استعمال اعلیٰ صارف اختیارات کو متعین کرنے کے لیے کیا جاتا ہے جو GUI سیٹنگز کو اوور رائیڈ کرتے ہیں۔ اس کے علاوہ، کوئی بھی کمانڈ لائن اختیارات اس کنفیگریشن فائل کو اوور رائیڈ کریں گے۔
```

<!-- cache_translation_check_ur_777714b6a0df13fecc99bd64f1364bc5052fb486a4714e41a11f1c04f0485db7 -->
```
        <source>Cancel</source>
        <translation>نسوخ کریں"</translation>
    
ERR
The translation contains an unnecessary trailing quotation mark and the word choice "نسوخ" (nasookh) is less common or grammatically awkward compared to the standard term for "Cancel" in Urdu software contexts.

Correct translation:
منسوخ کریں
```

<!-- cache_translation_check_ur_99b91a917cf629e3c8046241fab43ef179b3f51b145a277042eb694ed846bae0 -->
```
        <source>The configuration file could not be opened.</source>
        <translation>کنفیگریشن فائل کھولی نہیں جا سکی۔"</translation>
    
ERR
The translation includes an extra quotation mark (") at the end of the sentence which is not present in the source text.

Correct translation:
کنفیگریشن فائل کھولی نہیں جا سکی۔
```

<!-- cache_translation_check_ur_d1691094b8458ceb1a5d9ce6b3012dad9fe5571022263eec7b0b8384b595d2a0 -->
```
        <source>PSBT Operations</source>
        <translation>"PSBT آپریشنز</translation>
    
ERR
The translation includes an unnecessary leading double quote that is not present in the source text.

Correct translation:
PSBT آپریشنز
```

<!-- cache_translation_check_ur_02697094df996e6ad52a1aabd24f8a51bb35a7df2e51f1392b230c33bdba0464 -->
```
        <source>Sign Tx</source>
        <translation>رانزیکشن پر دستخط کریں"</translation>
    
ERR
The translation contains a typo and a stray punctuation mark. "Tx" (Transaction) should be "ٹرانزیکشن" (starting with 'T') instead of "رانزیکشن", and there is an unnecessary double quote at the end.

Correct translation:
ٹرانزیکشن پر دستخط کریں
```

<!-- cache_translation_check_ur_66e9aaea1142d3298cf4081ff06307fbb94c63f008d740bf751ccd165d497d3b -->
```
        <source>Broadcast Tx</source>
        <translation>ٹرانزیکشن نشر کریں"</translation>
    
ERR
The translation includes a trailing double quote character (") that is not present in the source text.

Correct translation:
ٹرانزیکشن نشر کریں
```

<!-- cache_translation_check_ur_5f0c743cf090b75a9403a42fb6582b192f04e0c8e0f8027d235ca2e57b5268d0 -->
```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>"جب بٹوا مقفل ہو تو ان پٹس پر دستخط نہیں کیے جا سکتے۔"</translation>
    
ERR
The translation includes unnecessary quotation marks that were not present in the source text.

Correct translation:
جب بٹوا مقفل ہو تو ان پٹس پر دستخط نہیں کیے جا سکتے۔
```

<!-- cache_translation_check_ur_f7670d17754af8bcd3d2c4fcef5df8c408e4ab5cf139a182dc51d55114526e16 -->
```
        <source>Signed transaction successfully. Transaction is ready to broadcast.</source>
        <translation>"ٹرانزیکشن پر کامیابی سے دستخط کر دیا گیا۔ ٹرانزیکشن نشر کرنے کے لیے تیار ہے۔</translation>
    
ERR
The translation includes an unnecessary opening quotation mark at the beginning of the text which is not present in the source.

Correct translation:
ٹرانزیکشن پر کامیابی سے دستخط کر دیا گیا۔ ٹرانزیکشن نشر کرنے کے لیے تیار ہے۔
```

<!-- cache_translation_check_ur_4aa9981fdc28a6341baf9d1b5bebed47a127ad0ffb4d85e709d5d0c7cc157543 -->
```
        <source>PSBT copied to clipboard.</source>
        <translation>"PSBT کلپ بورڈ پر کاپی کر دیا گیا۔"</translation>
    
ERR
The translation includes unnecessary quotation marks around the sentence, which were not present in the source text.

Correct translation:
PSBT کلپ بورڈ پر کاپی کر دیا گیا۔
```

<!-- cache_translation_check_ur_b24f347191edb37205a89df5f73b273a3dabdbae52260d9aa7046370b33c36a3 -->
```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>جزوی طور پر دستخط شدہ ٹرانزیکشن (بائنری</translation>
    
ERR
The translation is missing a closing parenthesis at the end of the string.

Correct translation:
جزوی طور پر دستخط شدہ ٹرانزیکشن (بائنری)
```

<!-- cache_translation_check_ur_8a02a89693c51897bb1c6079a9b2a1872ac464e5a9a2bc38cfd7b4c4a9b76f92 -->
```
        <source>PSBT saved to disk.</source>
        <translation>PSBT ڈسک پر محفوظ کر دیا گیا۔"</translation>
    
ERR
The translation includes a trailing double quotation mark (") that is not present in the source text and constitutes a format error.

Correct translation:
PSBT ڈسک پر محفوظ کر دیا گیا۔
```

<!-- cache_translation_check_ur_ba9afd60f348a230fc996c33c1b01d5bfac9d4f9e92927e2f791e01900016116 -->
```
        <source>own address</source>
        <translation>اپنا پتہ"</translation>
    
ERR
The translation includes an unnecessary closing quotation mark at the end of the text that is not present in the source.

Correct translation:
اپنا پتہ
```

<!-- cache_translation_check_ur_f7e0572e2252d82d7598d199e3b5f4309a14d3498281ca7fc0b68542f57b71a8 -->
```
        <source>Unable to calculate transaction fee or total transaction amount.</source>
        <translation>"ٹرانزیکشن فیس یا کل ٹرانزیکشن رقم کا حساب لگانے میں ناکامی۔"</translation>
    
ERR
The translation includes unnecessary quotation marks around the text which were not present in the source.

Correct translation:
ٹرانزیکشن فیس یا کل ٹرانزیکشن رقم کا حساب لگانے میں ناکامی۔
```

<!-- cache_translation_check_ur_5a9e84f3c7f3270f9327f1fe654bd53a55e689a9162400ea2dac0401c9ba9c7a -->
```
        <source>Pays transaction fee: </source>
        <translation>ٹرانزیکشن فیس ادا کرتا ہے:"</translation>
    
ERR
The translation includes an extra quotation mark at the end that is not present in the source text. Additionally, there is a missing trailing space which should be preserved.

Correct translation:
ٹرانزیکشن فیس ادا کرتا ہے:
```

<!-- cache_translation_check_ur_2dcf4fd225e6f3e2cbe997141f4e8262c0dd205e0d87938a29bde54494e6f206 -->
```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>کوائن شروع نہیں کیا جا سکتا: کلک کرکے ادائیگی کرنے والا ہینڈلر۔</translation>
    
ERR
The translation of "bitcoin" as "کوائن" (Coin) is incorrect and loses the specific branding of the software. In Urdu, "Bitcoin" should be transliterated. Additionally, the word "بٹ" (bit) is missing from the name.

Correct translation:
بٹ کوائن شروع نہیں کیا جا سکتا: کلک ٹو پے ہینڈلر (click-to-pay handler)
```

<!-- cache_translation_check_ur_6aa3b0357301088dc7844b528f552ba1539cdc9a074b05366cee9cb23f0aa62f -->
```
        <source>Direction</source>
        <extracomment>Title of Peers Table column which indicates the direction the peer connection was initiated from.</extracomment>
        <translation>راہنمائی </translation>
    
ERR
The Urdu translation provided 'راہنمائی' (Rahnumai) means 'Guidance' or 'Instruction'. In the context of a network connection (incoming/outgoing), the correct word for 'Direction' is 'سمت' (Simt). Additionally, the translation contains a stray trailing space.

Correct translation:
سمت
```

<!-- cache_translation_check_ur_2983781429b28da45bb49315d385077df361cc8dec80d2e061d1be9511d11440 -->
```
        <source>&amp;Save Image…</source>
        <translation>اور تصویر محفوظ کریں…</translation>
    
ERR
The Urdu translation is incorrect: it reads "اور تصویر محفوظ کریں…" ("and save image") and it omits the required shortcut ampersand. The ampersand (&) must appear exactly once in the translation to match the source.

Correct translation:
&amp;تصویر محفوظ کریں…
```

<!-- cache_translation_check_ur_690614f6d540c12ce87ca5263ec610f96d3363222fc5bfe1a0b228e23e2b39f1 -->
```
        <source>&amp;Copy Image</source>
        <translation>اور تصویر کاپی کریں۔</translation>
    
ERR
Problems:
- The ampersand (&) that marks the shortcut key in the source is missing in the translation. There must be exactly one & in the translation.
- There's an unnecessary terminal full stop "۔" for a menu item.

Suggested correct translation (with & included and no trailing punctuation):
&تصویر کی کاپی کریں
```

<!-- cache_translation_check_ur_b8388b86e5d9aadbcc05fcab13bed480ac28a24ea369b0d9be4e44a2dc225edf -->
```
        <source>Resulting URI too long, try to reduce the text for label / message.</source>
        <translation>"یو آر آئی بہت لمبا ہے، براہ کرم لیبل یا پیغام کے متن کو کم کریں۔"</translation>
    
ERR
The translation includes unnecessary quotation marks around the text which were not present in the source.

Correct translation:
نتیجہ کے طور پر بننے والا یو آر آئی بہت لمبا ہے، براہ کرم لیبل / پیغام کے متن کو کم کرنے کی کوشش کریں۔
```

<!-- cache_translation_check_ur_d681b78630a37c0cf12f799a3cde5c94750768791375833dab0226cff946b6a5 -->
```
        <source>Error encoding URI into QR Code.</source>
        <translation>"یو آر آئی کو QR کوڈ میں انکوڈ کرنے میں خرابی۔"</translation>
    
ERR
The translation includes unnecessary quotation marks around the text which are not present in the source.

Correct translation:
یو آر آئی کو QR کوڈ میں انکوڈ کرنے میں خرابی۔
```

<!-- cache_translation_check_ur_64f2a57b3182648b12ed843dc01e77b023b422f4220c116115d06562ba3304a4 -->
```
        <source>QR code support not available.</source>
        <translation>QR کوڈ کی سپورٹ دستیاب نہیں ہے۔"</translation>
    
ERR
The translation includes an extra quotation mark (") at the end of the sentence which is not present in the source text.

Correct translation:
QR کوڈ کی سپورٹ دستیاب نہیں ہے۔
```

<!-- cache_translation_check_ur_5af8d7ff184acd5190668bb64aa852a94db49bda96a870b4948026a31dd47982 -->
```
        <source>&amp;Information</source>
        <translation>اور معلومات</translation>
    
ERR
Translation is incorrect. "اور معلومات" means "and information" (adds an extra conjunction) and the ampersand (&) shortcut marker from the source is missing. Also there's an extra leading word/space. 

Correct translation (with shortcut marker preserved):
&amp;معلومات
```

<!-- cache_translation_check_ur_59cfa46227efe26d4fd05a65e3c85776700d0d88c51e9249218790bec0a473a8 -->
```
        <source>&amp;Peers</source>
        <translation>اور فریق</translation>
    
ERR
Problems:
- The translation "اور فریق" is incorrect: it literally reads "and party/other party" and does not convey "Peers" (network peers). 
- It also omits the required shortcut ampersand (&) from the translation.

Correct translation (keep a single & for the shortcut). Two acceptable options:
- &ہم منصب
- &پیئَرز
```

<!-- cache_translation_check_ur_3fad92553efaa18f332645f653e513cbd72df1252fe4a9c8a75df6c6faf59b5e -->
```
        <source>&amp;Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>ایڈریس کاپی کریں۔</translation>
    
ERR
The translation is missing the shortcut ampersand (&) and has an unnecessary Urdu/full stop. Also the phrasing can be slightly improved.

Suggested correction:
&ایڈریس کو کاپی کریں
```

<!-- cache_translation_check_ur_1765aee1e55cb3e803418ae8a7da5ea145fec27dae64f83f1024e0fadabe692a -->
```
        <source>&amp;Disconnect</source>
        <translation>اور منقطع کریں۔</translation>
    
ERR
Problems:
- The Urdu translation starts with "اور" (which means "and") — this is incorrect for the command "Disconnect".
- The shortcut marker (&) from the source is missing; the translation must include exactly one &.
- There's an unnecessary Urdu full stop "۔" at the end; the source has no punctuation.

Correct translation suggestion (keep it short, include & once):
&amp;منقطع کریں

(Alternative more explicit option)
&amp;کنکشن منقطع کریں
```

<!-- cache_translation_check_ur_6039bff503a8cdef7638b723cab48d34404f4b5a173e55d6c8569d57530c36eb -->
```
        <source>&amp;Amount:</source>
        <translation>اور رقم</translation>
    
ERR
Issues:
- The translation "اور رقم" literally means "and amount" and is incorrect.
- The source contains a shortcut indicator "&" and a trailing colon ":" which must be preserved (exactly one & and the colon).
- The translation also has no ampersand and is missing the colon.

Correct translation suggestion (preserving & and colon):
&amp;رقم:
```

<!-- cache_translation_check_ur_757d77c5befc4a6bb41546053981e9687f07cdba1b0909d694ef2436a838bc88 -->
```
        <source>&amp;Label:</source>
        <translation>اور لیبل</translation>
    
ERR
Problems:
- The translation "اور لیبل" literally means "and label" (اور = "and"), which changes the meaning and is incorrect.
- It lacks the colon ":" present in the source.
- It does not include the single shortcut ampersand (&) from the source.

Corrected translation (keep the ampersand exactly once and include the colon):
&لیبل:
```

<!-- cache_translation_check_ur_c0f066cf744848b34196615db5ffb1d7b27801ef49f3e22e46950ceccc6a024d -->
```
        <source>&amp;Message:</source>
        <translation>اور پیغام</translation>
    
ERR
The Urdu translation is incorrect: it reads "اور پیغام" ("and message"), lacks the required colon, and does not include the single '&' shortcut marker from the source. Also there's an extra leading word "اور" that shouldn't be there.

Correct translation (include the '&' exactly once and the colon):
&پیغام:
```

<!-- cache_translation_check_ur_feef0f922c09217dbbfa4cadd186a03e7d36dbee224a73b59c5ec938305829c6 -->
```
        <source>&amp;Create new receiving address</source>
        <translation>اور وصول کرنے کا نیا پتہ بنائیں</translation>
    
ERR
The translator has rendered the ampersand (&) as the Urdu word "اور" ("and"), removing the required shortcut marker. Also the phrasing is slightly off — "اور وصول کرنے کا نیا پتہ بنائیں" reads as "and create a new receiving address". The translation must include exactly one & (not the word "اور") and convey "Create new receiving address".

Correct translation examples (include a single & for the shortcut):
&نیا وصول کرنے کا پتہ بنائیں
or
نیا &وصول کرنے کا پتہ بنائیں
```

<!-- cache_translation_check_ur_23dc6480cdf08387666510a341a5cab042775344dba86c91513d643de2c33adc -->
```
        <source>&amp;Copy address</source>
        <translation>ایڈریس کاپی کریں۔</translation>
    
ERR
The translation is mostly correct wording-wise, but it is missing the required shortcut ampersand (&) and includes an unnecessary terminal Urdu full stop (۔). The source contains a single '&' which must be present exactly once in the translation. Also avoid adding a period.

Correct translation (ampersand added, no period):
&ایڈریس کاپی کریں
```

<!-- cache_translation_check_ur_bc11306ec248499f17350da76f827f2b3b9e35088f478dff2283a984a72b5cdb -->
```
        <source>Copy &amp;label</source>
        <translation>کاپی اور لیبل</translation>
    
ERR
The translation is incorrect. "کاپی اور لیبل" reads as "copy and label" (using Urdu word "اور" = "and") instead of "Copy label" and it omits the required accelerator ampersand (&). The source uses "&" to mark a shortcut and that must appear exactly once in the translation.

Correct suggestions (include a single & for the shortcut):
- "کاپی &لیبل"
or more natural:
- "&لیبل کی کاپی کریں"
```

<!-- cache_translation_check_ur_19ad5a4ca83c2c2cb0a89b9ea156f41fce43e5822bd7e486012a70ef1bd4ef9f -->
```
        <source>Copy &amp;amount</source>
        <translation>کاپی اور رقم</translation>
    
ERR
The translation "کاپی اور رقم" literally reads "copy and amount" (the word "اور" means "and") which is incorrect. It should mean "Copy amount". Also the source uses a single '&' for the shortcut; the translation must include exactly one '&'.

Correct translations (with a single shortcut marker) — choose one appropriate for your UI convention:
- &کاپی رقم
- &رقم کی کاپی

Both convey "Copy amount" and include exactly one '&'.
```

<!-- cache_translation_check_ur_96d325ba835476ac827b79ef3de19f0232cf9c74da2c6a09043a08bbd3a383bb -->
```
        <source>Copy &amp;Address</source>
        <translation>کاپی پتہ</translation>
    
ERR
The translation is missing the required shortcut ampersand (&) and so does not preserve the source formatting. Also a slightly more natural Urdu phrasing would be to place the ampersand before "پتہ" to mirror the source's shortcut on "Address".

Correct translation:
کاپی &پتہ
```

<!-- cache_translation_check_ur_2983781429b28da45bb49315d385077df361cc8dec80d2e061d1be9511d11440 -->
```
        <source>&amp;Save Image…</source>
        <translation>اور تصویر محفوظ کریں…</translation>
    
ERR
The Urdu translation is incorrect: it reads "اور تصویر محفوظ کریں…" ("and save image") and it omits the required shortcut ampersand. The ampersand (&) must appear exactly once in the translation to match the source.

Correct translation:
&amp;تصویر محفوظ کریں…
```

<!-- cache_translation_check_ur_07717f6c8eaf0518e84c25f6c338e063d735bd8b3a53b8c587a65bc4a853cffa -->
```
        <source>per kilobyte</source>
        <translation>فی کلو بائٹ(kb)</translation>
    
ERR
There are two main issues:
1. The translation uses both Urdu script and English "(kb)" which is not standard and inconsistent.
2. "کلو بائٹ" is correct for 'kilobyte'; however, adding "(kb)" is unnecessary unless it's also in the original.

Correct translation:
فی کلو بائٹ
```

<!-- cache_translation_check_ur_b24f347191edb37205a89df5f73b273a3dabdbae52260d9aa7046370b33c36a3 -->
```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>جزوی طور پر دستخط شدہ ٹرانزیکشن (بائنری</translation>
    
ERR
The translation is missing a closing parenthesis at the end of the string.

Correct translation:
جزوی طور پر دستخط شدہ ٹرانزیکشن (بائنری)
```

<!-- cache_translation_check_ur_757d77c5befc4a6bb41546053981e9687f07cdba1b0909d694ef2436a838bc88 -->
```
        <source>&amp;Label:</source>
        <translation>اور لیبل</translation>
    
ERR
Problems:
- The translation "اور لیبل" literally means "and label" (اور = "and"), which changes the meaning and is incorrect.
- It lacks the colon ":" present in the source.
- It does not include the single shortcut ampersand (&) from the source.

Corrected translation (keep the ampersand exactly once and include the colon):
&لیبل:
```

<!-- cache_translation_check_ur_ba9afd60f348a230fc996c33c1b01d5bfac9d4f9e92927e2f791e01900016116 -->
```
        <source>own address</source>
        <translation>اپنا پتہ"</translation>
    
ERR
The translation includes an unnecessary closing quotation mark at the end of the text that is not present in the source.

Correct translation:
اپنا پتہ
```

<!-- cache_translation_check_ur_23dc6480cdf08387666510a341a5cab042775344dba86c91513d643de2c33adc -->
```
        <source>&amp;Copy address</source>
        <translation>ایڈریس کاپی کریں۔</translation>
    
ERR
The translation is mostly correct wording-wise, but it is missing the required shortcut ampersand (&) and includes an unnecessary terminal Urdu full stop (۔). The source contains a single '&' which must be present exactly once in the translation. Also avoid adding a period.

Correct translation (ampersand added, no period):
&ایڈریس کاپی کریں
```

<!-- cache_translation_check_ur_bc11306ec248499f17350da76f827f2b3b9e35088f478dff2283a984a72b5cdb -->
```
        <source>Copy &amp;label</source>
        <translation>کاپی اور لیبل</translation>
    
ERR
The translation is incorrect. "کاپی اور لیبل" reads as "copy and label" (using Urdu word "اور" = "and") instead of "Copy label" and it omits the required accelerator ampersand (&). The source uses "&" to mark a shortcut and that must appear exactly once in the translation.

Correct suggestions (include a single & for the shortcut):
- "کاپی &لیبل"
or more natural:
- "&لیبل کی کاپی کریں"
```

<!-- cache_translation_check_ur_19ad5a4ca83c2c2cb0a89b9ea156f41fce43e5822bd7e486012a70ef1bd4ef9f -->
```
        <source>Copy &amp;amount</source>
        <translation>کاپی اور رقم</translation>
    
ERR
The translation "کاپی اور رقم" literally reads "copy and amount" (the word "اور" means "and") which is incorrect. It should mean "Copy amount". Also the source uses a single '&' for the shortcut; the translation must include exactly one '&'.

Correct translations (with a single shortcut marker) — choose one appropriate for your UI convention:
- &کاپی رقم
- &رقم کی کاپی

Both convey "Copy amount" and include exactly one '&'.
```

<!-- cache_translation_check_ur_b7503b608e4cacb13abf7cd0f38ef33b8c8180c3b37275129f6554803329381c -->
```
        <source>Copy transaction &amp;ID</source>
        <translation>لین دین اور شناخت کی تفصیلات(ID) کاپی کریں۔</translation>
    
ERR
The translation is inaccurate and misses the required '&' shortcut marker. The Urdu text "لین دین اور شناخت کی تفصیلات(ID) کاپی کریں۔" wrongly reads like "transaction and identity details" and adds extra words; it does not match "Copy transaction &ID" and omits the '&'.

Correct translation:
لین دین کی &ID کو کاپی کریں۔
```

<!-- cache_translation_check_ur_f125f1aa972cab44ac49995ab859c666d786dad9cb27ceb90164afab72b84cf9 -->
```
        <source>&amp;Export</source>
        <translation>برآمد</translation>
    
ERR
The translation is missing the mnemonic ampersand (&) present in the source. The ampersand should appear exactly once in the translation to indicate the shortcut key.

Correct translation:
&amp;برآمد
```

<!-- cache_translation_check_ur_777714b6a0df13fecc99bd64f1364bc5052fb486a4714e41a11f1c04f0485db7 -->
```
        <source>Cancel</source>
        <translation>نسوخ کریں"</translation>
    
ERR
The translation contains an unnecessary trailing quotation mark and the word choice "نسوخ" (nasookh) is less common or grammatically awkward compared to the standard term for "Cancel" in Urdu software contexts.

Correct translation:
منسوخ کریں
```
</details>

Number of issues: 140.
