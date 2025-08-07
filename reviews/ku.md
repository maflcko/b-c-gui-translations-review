# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ku</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bku%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>ئەمانە ناونیشانی بیتکۆبیتەکانی تۆنە بۆ وەرگرتنی پارەدانەکان. دوگمەی 'دروستکردنیناونیشانی وەرگرتنی نوێ' لە تابی وەرگرتندا بۆ دروستکردنی ناونیشانی نوێ بەکاربێنە.
واژووکردن تەنها دەکرێت لەگەڵ ناونیشانەکانی جۆری 'میرات'.</translation>
    
YES
The translation uses "بیتکۆبیتەکانی" which appears to be a typo; it should be "بیتکۆینی" (Bitcoin). Also, "واژووکردن" is used for "signing," but a more appropriate term in the context of digital signatures is "واژۆکردن". Furthermore, "میرات" seems to be a literal translation of "legacy" and doesn't clearly indicate the specialized Bitcoin address type. The industry-standard way is often to leave "legacy" in Latin script or clarify with context.

Correct translation:
ئەمانە ناونیشانی بیتکۆینی ھە بۆ وەرگرتنی پارەدانەکانت. دوگمەی 'دروستکردنی ناونیشانی وەرگرتنی نوێ' لە تابی وەرگرتندا بەکاربەرە بۆ زیادکردنی ناونیشانێکی نوێ.
واژۆکردن تەنها دەکرێت لەگەڵ ناونیشانەکان بە جۆری 'legacy'.
```

```
        <source>Encrypt wallet</source>
        <translation>Şîfrekirina cizdên</translation>
    
YES
The translation "Şîfrekirina cizdên" is not accurate. The word "cizdên" is not the correct Kurdish word for "wallet" in this context—it seems erroneous or possibly a typographical error. The correct word for "wallet" in Kurdish is "portefey" or "cüzdan".

Correct translation:
Şîfrekirina cüzdanê

Or, depending on dialect:
Şîfrekirina portefêyê
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>او شوله بو ور کرنا کیف پاره گرکه رمزا کیفه وؤ یه پاره بزانی</translation>
    
YES
The translation has several issues:
1. The translation is mostly written in Kurmanji Kurdish (ku), but it contains some non-standard wording and awkward phrasing.
2. The sentence structure is confusing and some parts are redundant or mistranslated (e.g., "گرکه رمزا کیفه وؤ یه پاره بزانی" is awkward and mixes dialects).
3. "شوله بو ور کرنا" is also awkward and not idiomatic for "This operation needs".

Correct translation:
Ev kar pêdivî ye ku tu şîfreya pursê xwe bikar bînî da ku pursê xwe veke.

Or more directly:
Ev xebat pêdivîya şîfreya qalîlkê te heye da ku qalîlkê veke.

Either of these provides a correct and fluent translation.
```

```
        <source>Change passphrase</source>
        <translation>Pêborînê biguherîne</translation>
    
YES
The translation "Pêborînê biguherîne" is not entirely accurate. "Pêborîn" means "password", but "passphrase" in the context of Bitcoin wallets is better translated as "peyva-êrxas" or sometimes "şîfreyê dirêj", which conveys the idea of a phrase, not a single word password. Also, the command form "biguherîne" (change) is appropriate.

Correct translation:
Peyva-êrxasê biguherîne

or

Şîfreyê dirêj biguherîne

Either is acceptable, but "Peyva-êrxasê biguherîne" is most faithful to "Change passphrase".
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>دۆخی تایبەتمەندی چالاک کرا بۆ تابی گشتی. بۆ کردنەوەی بەهاکان، بەهاکان ڕێکخستنەکان&gt;ماسک.</translation>
    
YES
The translation is inaccurate and problematic for several reasons:
- The phrase "دۆخی تایبەتمەندی" translates as "special/private mode," but "privacy" is more accurately "نهێنی".
- The term "Overview tab" is translated as "تابی گشتی" ("General tab"), but "گشتی" does not specifically refer to "Overview".
- The phrase "بەهاکان ڕێکخستنەکان&gt;ماسک" is nonsensical and does not maintain structure or meaning. The setting path should be translated logically and clearly.
- "&gt;" is not properly converted or spaced.

Correct translation:
دۆخی نهێنی بۆ تابەکەی پێشبینینی چالاک کرا. بۆ نیشاندانەوەی بەهاکان، تیکە لە ڕێکخستنەکان->پوشاندنی بەهاکان بەرەدە.

Explanation:
- "دۆخی نهێنی" = privacy mode
- "تابی پێشبینین" = Overview tab
- "بەهاکان" = values
- "تیکە لە ... بەرەدە" = uncheck ...
- "ڕێکخستنەکان->پوشاندنی بەهاکان" = Settings->Mask values (settings path), which preserves the meaning and intent.
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>ناتوانێت دەست بکات بە bitcoin: کرتە بکە بۆ-پارەدانی کار</translation>
    
YES
The translation uses Arabic script Kurdish ('ku-Arab') which is acceptable, but the translation is awkward and inaccurate. Specifically, "کرتە بکە بۆ-پارەدانی کار" is not a clear or idiomatic rendering of "click-to-pay handler"; it directly and erroneously translates "click-to-pay" word-for-word, and "handler" is rendered as "کار" (work/job) which is incorrect.

Correct translation:
ناتوانێت bitcoin-ڕێکخەرە کلیک-بۆ-پارەدان دەستپێ بکات

Or more idiomatically:
ناتوانێت بەستەری bitcoin بۆ پەرەدان بە کرتەکردن دەست پێ بکات

This preserves the technical intent and clarity.
```

```
        <source>Type</source>
        <extracomment>Title of Peers Table column which describes the type of peer connection. The "type" describes why the connection exists.</extracomment>
        <translation>Cure</translation>
    
YES
The translation is not accurate. The English word "Type" in this context should be translated to the Kurdish word "Tîp" which directly means "type" as in "kind" or "category." "Cure" is incorrect, as in Kurdish "cure" means more like "kind/sort", but the more direct translation—and the most commonly used in the context of tables or technical language—is "Tîp".

Correct translation:
Tîp
```

```
        <source>When there is less transaction volume than space in the blocks, miners as well as relaying nodes may enforce a minimum fee. Paying only this minimum fee is just fine, but be aware that this can result in a never confirming transaction once there is more demand for bitcoin transactions than the network can process.</source>
        <translation>کاتێک قەبارەی مامەڵە کەمتر بێت لە بۆشایی بلۆکەکان، لەوانەیە کانەکان و گرێکانی گواستنەوە کەمترین کرێ جێبەجێ بکەن. پێدانی تەنیا ئەم کەمترین کرێیە تەنیا باشە، بەڵام ئاگاداربە کە ئەمە دەتوانێت ببێتە هۆی ئەوەی کە هەرگیز مامەڵەیەکی پشتڕاستکردنەوە ئەنجام بدرێت جارێک داواکاری زیاتر هەیە بۆ مامەڵەکانی بیت کۆبیتکۆ لەوەی کە تۆڕەکە دەتوانێت ئەنجامی بدات.</translation>
    
YES
The translation has multiple issues:
- The phrase "مامەڵەیەکی پشتڕاستکردنەوە ئەنجام بدرێت" is an incorrect and confusing rendering of "a never confirming transaction".
- The translation uses "بیت کۆبیتکۆ" which seems to be a repetition or typo for "بیتکۆین".
- Some structure and flow problems make parts unclear or awkward, especially the last part.

Correct translation:
کاتێک قەبارەی مامەڵەکان کەمتر بێت لە بۆشایی بلۆکەکان، لەوانەیە کانەکان و خانووی گواستنەوەکان کەمترین کرێی پێویست جێبەجێ بکەن. پێدانی تەنیا ئەم کەمترین کرێیە باشە، بەڵام پێت بزانە ئەمە دەتوانێت بێت هۆی ئەوەی مامەڵەکەت هەرگیز پشتڕاست نەکرێت ئەگەر داواکاری مامەڵەی بیتکۆین زیاتر بێت لە ئەوەی تۆڕەکە دەتوانێت پڕۆسە بکات.
```

```
        <source>Type</source>
        <translation>Cure</translation>
    
YES
The translation is problematic. "Cure" is not the correct translation for "Type" in Kurdish ('ku'). It looks like a mistaken, unrelated English word.

Correct translation:
Tîp
```

```
        <source>Type</source>
        <translation>Cure</translation>
    
YES
The translation is problematic. "Cure" is not the correct translation for "Type" in Kurdish ('ku'). It looks like a mistaken, unrelated English word.

Correct translation:
Tîp
```

```
        <source>You need to rebuild the database using -reindex to go back to unpruned mode.  This will redownload the entire blockchain</source>
        <translation>پێویستە بنکەی زانیارییەکان دروست بکەیتەوە بە بەکارهێنانی -دووبارە ئیندێکس بۆ گەڕانەوە بۆ دۆخی نەپڕاو.  ئەمە هەموو بەربەستەکە دائەبەزێنێت</translation>
    
YES
There are some issues in the translation:
- The option "-reindex" is incorrectly translated as "-دووبارە ئیندێکس" which is not the actual command and could confuse users. It should remain as "-reindex".
- The translation for "blockchain" is rendered as "بەربەستەکە" which more literally means "obstacle" or "barrier", not "blockchain". The correct term should be "زنجیرە-بلۆکەکان" or "بلۆکچێین" (common in technical Kurdish).
- The translation for "unpruned mode" as "دۆخی نەپڕاو" is correct.
- The final translation for "redownload the entire blockchain" as "ئەمە هەموو بەربەستەکە دائەبەزێنێت" is incorrect, as above.

Correct translation:
پێویستە بنکەی زانیارییەکان دووبارە دروست بکەیت بە بەکارهێنانی -reindex بۆ گەڕانەوە بۆ دۆخی نەپڕاو. ئەمە هەموو بلۆکچێینەکە دووبارە دابەزێنێت
```

```
        <source>Could not find asmap file %s</source>
        <translation>ئاسماپ بدۆزرێتەوە %s نەتوانرا فایلی</translation>
    
YES
The translation is unnatural and the word order is incorrect. The phrase "ئاسماپ بدۆزرێتەوە %s نەتوانرا فایلی" does not clearly convey "Could not find asmap file %s" in Kurdish ('ku'). The word "ئاسماپ" (asmap) comes first, which is confusing, and the verb "find" and "could not" are not structured properly.

Correct translation:
نەتوانرا فایلی asmap %s بدۆزرێتەوە

Or more naturally:
ناتوانرێت فایلی asmap %s بدۆزرێتەوە

Either will be clearer and correct in Kurdish.
```
</details>

Number of issues: 12.
