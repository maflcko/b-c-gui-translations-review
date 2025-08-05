# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ku</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bku%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>ئەمانە ناونیشانی بیتکۆبیتەکانی تۆنە بۆ ناردنی پارەدانەکان. هەمیشە بڕی و ناونیشانی وەرگرەکان بپشکنە پێش ناردنی دراوەکان.</translation>
    
YES
There are several issues with this translation:

1. Usage of "بیتکۆبیتەکانی" ("Bitcoineta" with Kurdish plural suffix) is incorrect and should be "بیتکۆینی" ("Bitcoin") or "بیتکۆین").
2. "پارەدانەکان" is not the right word for "payments" here; "پارەدان" is not idiomatic, it should be "پارە" for "money" or "پارەدان" for the verb "to pay". However, "ناردن" (to send) and "پارەدان" are redundant together here.
3. “بڕی و ناونیشانی وەرگرەکان” ("the amount and the receiving addresses") should be "بڕ و ناونیشانی وەرگر" for singular, or if plural, keep it clear ("بڕەکان و ناونیشانەکانی وەرگر").
4. Excessive use of plural forms makes it confusing.
5. First sentence is awkwardly constructed.

Correct translation:
ئەمانە ناونیشانی بیتکۆینی تۆن بۆ ناردنی پارەیە. هەمیشە بڕ و ناونیشانی وەرگر پێش ناردنی دڕاوەکانت سەلم بکە.

Or more formally:
ئەمە ناونیشانی بیتکۆینی تۆن بۆ ناردنی پارەیە. هەمیشە بڕ و ناونیشانی وەرگر پێش ناردنی کۆینەکانت بە وردی بپشکنە.
```

```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>ئەمانە ناونیشانی بیتکۆبیتەکانی تۆنە بۆ وەرگرتنی پارەدانەکان. دوگمەی 'دروستکردنیناونیشانی وەرگرتنی نوێ' لە تابی وەرگرتندا بۆ دروستکردنی ناونیشانی نوێ بەکاربێنە.
واژووکردن تەنها دەکرێت لەگەڵ ناونیشانەکانی جۆری 'میرات'.</translation>
    
YES
There are several issues:

1. The translation uses "بیتکۆبیتەکانی" which appears to be a typo for "بیتکۆینی".
2. The phrase "دروستکردنیناونیشانی وەرگرتنی نوێ" is missing a space: it should be "دروستکردنی ناونیشانی وەرگرتنی نوێ".
3. The word "میرات" is a literal translation of "legacy" but in the context of Bitcoin, it is better to keep "legacy" in Latin script or an established cryptographic Kurdish equivalent (often the English term "legacy" is used).
4. The register is slightly off; some improvements can be made for clarity and accuracy.

Correct translation:
ئەمانە ناونیشانی بیتکۆینیی تۆن بۆ وەرگرتنی پارەدانن. دوگمەی 'دروستکردنی ناونیشانی وەرگرتنی نوێ' لە تابی وەرگرتندا بەکاربە بۆ دروستکردنی ناونیشانی نوێ.
واژووکردن تەنها دەتوانرێت لەگەڵ ناونیشانەکانی جۆری 'legacy'.
```

```
        <source>Encrypt wallet</source>
        <translation>Şîfrekirina cizdên</translation>
    
YES
The translation "Şîfrekirina cizdên" is problematic. The word "cizdên" is incorrect; the correct word for "wallet" in Kurmanji is "cuzdan" or "cûzdana". Additionally, "Şîfrekirina" means "Encryption of", which is appropriate, but the translation uses the plural of "cuzdan" mistakenly. The correct translation is:

Correct translation:
Şîfrekirina cûzdana
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>او شوله بو ور کرنا کیف پاره گرکه رمزا کیفه وؤ یه پاره بزانی</translation>
    
YES
The translation contains several issues:
1. The script is in Arabic-based Kurdish (Sorani or Kurmanji script), but word choice and structure are awkward and not standard for Kurdish.
2. "شوله بو" does not correspond to "This operation" in Kurdish.
3. There are some format and spacing issues ("وؤ" and "یه" are not Kurdish).
4. The translation is largely unintelligible and includes erroneous or non-Kurdish elements.

Correct translation (Kurmanji Kurdish, using Latin alphabet and standard terminology):
Ev kar pêdivî ye şîfreya portefeyê te bike da ku portefeyê vekê.

(If Sorani script is required, it should be in the appropriate Sorani Kurdish translation.)

Correct translation (Sorani Kurdish):
ئەم کردارە پێویستە تۆ وشەی نهێنی بەرەوپێشەکەت بنووسی تا بەرەوپێشەکەت کرابکرێتەوە.

Summary: Current translation is incorrect, not standard Kurdish, and contains erroneous elements.
```

```
        <source>Change passphrase</source>
        <translation>Pêborînê biguherîne</translation>
    
YES
The translation "Pêborînê biguherîne" is incorrect. "Pêborîn" means "password" in Kurdish (Kurmanji), but "biguherîne" means "to change it" in an imperative form. For a direct and clear translation of "Change passphrase" (assuming passphrase is "şîfreya derbas" or "şîfreya giran"), the translation should use a more accurate word for "passphrase," not just "password," and the imperative should fit menu styling.

Correct translation:
Şîfreya derbas biguherîne

Or, if the interface commonly uses "şîfre" for "passphrase":
Şîfre biguherîne

But to be precise:

Change passphrase = Şîfreya derbas biguherîne
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain. It is faster to download the full chain first and prune it later. Disables some advanced features.</source>
        <translation>دووبارە کردنەوەی ئەم ڕێکخستنە پێویستی بە دووبارە داگرتنی تەواوی بەربەستەکە هەیە. خێراترە بۆ داگرتنی زنجیرەی تەواو سەرەتا و داگرتنی دواتر. هەندێک تایبەتمەندی پێشکەوتوو لە کار دەهێنێت.</translation>
    
YES
There are issues with the translation:

1. The translation for "blockchain" is rendered as "بەربەستەکە", which literally means "the obstacle" or "the locked thing", which is incorrect. The correct term for "blockchain" in Kurdish is "زنجیرە بلوکەکان" or simply "زنجیرەی بلۆک".
2. "Prune" is not translated correctly. The phrase "داگرتنی دواتر" means "delete afterwards", which is confusing. "Prune" in this context means to reduce or trim the blockchain.
3. "Disables some advanced features." is rendered as "هەندێک تایبەتمەندی پێشکەوتوو لە کار دەهێنێت", which means "activates some advanced features", the opposite meaning; it should say "disables" (makes them inactive).
4. The translation has some awkward and ambiguous phrasings.

Correct translation:
دووبارە گۆڕینی ئەم ڕێکخستنە پێویستی بە دووبارە داگرتنی تەواوی زنجیرەی بلۆکەکانە. باشترە سەرەتا زنجیرەی تەواوی بلۆکەکان داگرت و دوای پڕوونەکردنەوەی بکەیت. هەندێک تایبەتمەندی پێشکەوتوو ناچالاک دەکات.
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>دۆخی تایبەتمەندی چالاک کرا بۆ تابی گشتی. بۆ کردنەوەی بەهاکان، بەهاکان ڕێکخستنەکان&gt;ماسک.</translation>
    
YES
The translation contains an error in accurately rendering the instructions and the structure. The phrase "Settings-&gt;Mask values" is not correctly represented, and some meaning is lost or altered. Also, the Kurdish translation uses Arabic script which is correct for 'ku' (Sorani), but the rest of the sentence is not fluent or well-structured.

Correct translation:
دۆخی نهێنی بۆ پەنجەرەی گشتی چالاک کرا. بۆ ئەوەی نرخەکان بڵاوبکەیتەوە، هەڵسوکەوتی 'ڕێکخستنەکان -> نرخەکان پەوش بکه‌' بسڕەوە.

Explanation:
- Kept the meaning of "Privacy mode" as "دۆخی نهێنی".
- Clearly explained the "Settings->Mask values" path.
- Corrected the flow and removed duplicated or misplaced terms.
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>ناتوانێت دەست بکات بە bitcoin: کرتە بکە بۆ-پارەدانی کار</translation>
    
YES
The translation is problematic. The phrase "click-to-pay handler" is not translated correctly; it seems to be a literal and awkward rendering, and partially untranslated English text ("bitcoin:" is left in). Also, "دەست بکات بە bitcoin" means "cannot start with bitcoin", which is not accurate for "Cannot start bitcoin".

Correct translation:
ناتوانێت پڕۆسەی بەڕێوەبردنی کلیک-بۆ-پارەدان بگەزێنێت بۆ بیتکوین

This correctly conveys the meaning, keeps the relevant terms correctly adapted to Kurdish, and does not leave untranslated English phrases.
```

```
        <source>Type</source>
        <extracomment>Title of Peers Table column which describes the type of peer connection. The "type" describes why the connection exists.</extracomment>
        <translation>Cure</translation>
    
YES
The translation "Cure" is incorrect in Kurdish ('ku'). The English word "Type" should be translated as "Cure" only if it means "type" or "kind" in Kurdish, but "Cure" is actually an English word and does not have meaning in Kurdish. The correct translation for "Type" (meaning kind or sort) in Kurdish is "Cûre" (also written as "نوعی" in Kurdish Sorani script).

Correct translation:
Cûre

Note: "Cure" seems like a typographical error or a false friend. Ensure use of correct Kurdish spelling and diacritics.
```

```
        <source>Show the selected request (does the same as double clicking an entry)</source>
        <translation>پیشاندانی داواکارییە دیاریکراوەکان (هەمان کرتەی دووانی کرتەکردن دەکات لە تۆمارێک)</translation>
    
YES
There is a problem with the translation:
- The source refers to showing "the selected request" (singular), while the translation says "داواکارییە دیاریکراوەکان" (plural: "the selected requests").
- The translation also adds "هەمان کرتەی دووانی کرتەکردن دەکات لە تۆمارێک" which is somewhat awkward compared to the English "does the same as double clicking an entry".

Correct translation:
پیشاندانی داواکاری دیاریکراو (هەمان کار دەکات وەک دووجار کرتەکردن لە تۆمارێک)
```

```
        <source>When there is less transaction volume than space in the blocks, miners as well as relaying nodes may enforce a minimum fee. Paying only this minimum fee is just fine, but be aware that this can result in a never confirming transaction once there is more demand for bitcoin transactions than the network can process.</source>
        <translation>کاتێک قەبارەی مامەڵە کەمتر بێت لە بۆشایی بلۆکەکان، لەوانەیە کانەکان و گرێکانی گواستنەوە کەمترین کرێ جێبەجێ بکەن. پێدانی تەنیا ئەم کەمترین کرێیە تەنیا باشە، بەڵام ئاگاداربە کە ئەمە دەتوانێت ببێتە هۆی ئەوەی کە هەرگیز مامەڵەیەکی پشتڕاستکردنەوە ئەنجام بدرێت جارێک داواکاری زیاتر هەیە بۆ مامەڵەکانی بیت کۆبیتکۆ لەوەی کە تۆڕەکە دەتوانێت ئەنجامی بدات.</translation>
    
YES
There are issues with this translation:

1. The translation is in the Sorani Kurdish script, but there are some clarity and term usage issues.
2. The phrase "مامەڵەیەکی پشتڕاستکردنەوە" is a bit awkward for "a never confirming transaction"—it should be something like "مامەڵەیەک کە هەرگیز پشتڕاست ناکرێت" ("a transaction that never confirms").
3. Near the end, "داواکاری زیاتر هەیە بۆ مامەڵەکانی بیت کۆبیتکۆ" is redundant ("بیتکۆ" is repeated).
4. "جێبەجێ بکەن" is fine, but could be more precise as "دەرفەتی کەمترین کرێی دیاری بکەن".
5. The sentence order and connection could be improved; currently, it is somewhat murky.
6. Also, "%1" and other format specifiers do not appear, so nothing to check there.

Correct translation:
کاتێک قەبارەی مامەڵەکان کەمتر بێت لە بۆشایی بلۆکەکان، لەوانەیە کانەکان و گرێکانی گواستنەوە کەمترین کرێ جێبەجێ بکەن. پێدانی تەنیا ئەم کەمترین کرێیە باشە، بەڵام ئاگاداربە کە ئەمە دەتوانێت هۆی ئەوە بێت کە مامەڵەکە هەرگیز پشتڕاست نەکرێت ئەگەر داواکاری بۆ مامەڵەکانی بیتکۆ زیاتر ببێت لە ئەوەی تۆڕەکە دەتوانێت بەڕێوەببەت.
```

```
        <source>Type</source>
        <translation>Cure</translation>
    
YES
The translation is incorrect. "Type" in English means "type" or "kind". In Kurdish ('ku'), the word for "type" is "Tîp". "Cure" is not a Kurdish word; it appears to be a typo or an incorrect guess.

Correct translation:
Tîp
```

```
        <source>Type</source>
        <translation>Cure</translation>
    
YES
The translation is incorrect. "Type" in English means "type" or "kind". In Kurdish ('ku'), the word for "type" is "Tîp". "Cure" is not a Kurdish word; it appears to be a typo or an incorrect guess.

Correct translation:
Tîp
```

```
        <source>You need to rebuild the database using -reindex to go back to unpruned mode.  This will redownload the entire blockchain</source>
        <translation>پێویستە بنکەی زانیارییەکان دروست بکەیتەوە بە بەکارهێنانی -دووبارە ئیندێکس بۆ گەڕانەوە بۆ دۆخی نەپڕاو.  ئەمە هەموو بەربەستەکە دائەبەزێنێت</translation>
    
YES
The translation has several issues:
1. The flag '-reindex' is translated incorrectly as '-دووبارە ئیندێکس'. It should remain as '-reindex', as it is a command-line flag.
2. "pruned mode" is translated as "دۆخی نەپڕاو", which is a possible interpretation, but the word "pruned" in Bitcoin context refers to "trimmed" or "cleaned up" mode. "نەپڕاو" may be understood, but a clearer phrase might be "دۆخی پڕاوکراو" (trimmed/cleaned mode) for technical accuracy.
3. The phrase "redownload the entire blockchain" is mistranslated as "ئەمە هەموو بەربەستەکە دائەبەزێنێت", which actually means "this will re-download the entire obstacle" or "the whole subject". The word "blockchain" should be explicitly mentioned as "بلاکچەین" or "زنجیرەی بلۆکەکان".
4. There is an extra space between sentences, matching the English, but it's better to ensure this spacing is consistent for Kurdish (Kurmanji or Sorani does not normally have two spaces).
5. There is a translation/format specifier mismatch: the translation omits 'blockchain' and replaces it with 'بەربەستەکە', which is incorrect.

Correct translation:
پێویستە بنکەی داتاکان دووبارە دروست بکەیت بە بەکارهێنانی -reindex بۆ گەڕانەوە بۆ دۆخی پڕاوکراونەوە. ئەمە هەموو زنجیرەی بلۆکەکان (blockchain) دووبارە دابەزێنێت
```

```
        <source>Could not find asmap file %s</source>
        <translation>ئاسماپ بدۆزرێتەوە %s نەتوانرا فایلی</translation>
    
YES
The translation is problematic. The word order is incorrect and unnatural in Kurdish (Kurmanji/Sorani), making the sentence confusing. The verb "نەتوانرا" (could not) should come before "بدۆزرێتەوە" (find), and the placement of "%s" and "فایلی" (file) is also off.

Correct translation:
نەتوانرا فایلی ئاسماپ %s بدۆزرێتەوە

Alternatively, more naturally:
نەتوانرا فایلی ئاسماپ بەناوی %s بدۆزرێتەوە
```

```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>هەڵە: کلیلی پوول ڕایکرد، تکایە سەرەتا پەیوەندی بکە بە پڕکردنەوەی کلیل</translation>
    
YES  
The translation is somewhat understandable but contains issues:
1. The term "کلیلی پوول" is not idiomatic in Kurdish for "keypool" and is a literal/unusual rendering.
2. "ڕایکرد" means "finished" or "ended", which is a reasonable translation for "ran out", but the expression could be clearer.
3. "پەیوەندی بکە بە پڕکردنەوەی کلیل" translates to "please contact the refill of the key", which is not accurate for "please call keypoolrefill".
4. There is no indication of the format specifiers, though the original does not contain any.
5. The word "کلیل" (key) is being used, but "keypool" may be better left in English or explained for technical clarity.

Correct translation:
هەڵە: ئەستووی کیپولو بە تەواوەتی بەسەرچوو، تکایە سەرەتا "keypoolrefill" بکە

Explanation: "کیپولو" (keypool) is transliterated for clarity, "بە تەواوەتی بەسەرچوو" means "completely ran out", and the user is told to call "keypoolrefill" as in the original English. The imperative form is direct and clear for technical instructions.
```
</details>
