# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>ku</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bku%5D%20request)


<!-- cache_translation_check_ku_0fd8a98879683df051123260d6d91acf7fc818ffcf280cf509f6fd3ea8b956dd -->
```
        <source>C&amp;lose</source>
        <translation>Bigire</translation>
    
ERR
The translation "Bigire" does not contain an "&" to indicate the shortcut, which is present in the source as "&lose". Additionally, the Kurdish translation for "Close" is usually "Bigire" or "Daxwazî", but the shortcut marker must be preserved.

Correct translation:
&Bigere
```

<!-- cache_translation_check_ku_f65441808f2cbe7fe59d4b257fba3678aa56d4cadb070d9a269e9e841207af6d -->
```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>ئەمانە ناونیشانی بیتکۆبیتەکانی تۆنە بۆ وەرگرتنی پارەدانەکان. دوگمەی 'دروستکردنیناونیشانی وەرگرتنی نوێ' لە تابی وەرگرتندا بۆ دروستکردنی ناونیشانی نوێ بەکاربێنە.
واژووکردن تەنها دەکرێت لەگەڵ ناونیشانەکانی جۆری 'میرات'.</translation>
    
ERR
The translation uses "بیتکۆبیتەکانی" which appears to be a typo; it should be "بیتکۆینی" (Bitcoin). Also, "واژووکردن" is used for "signing," but a more appropriate term in the context of digital signatures is "واژۆکردن". Furthermore, "میرات" seems to be a literal translation of "legacy" and doesn't clearly indicate the specialized Bitcoin address type. The industry-standard way is often to leave "legacy" in Latin script or clarify with context.

Correct translation:
ئەمانە ناونیشانی بیتکۆینی ھە بۆ وەرگرتنی پارەدانەکانت. دوگمەی 'دروستکردنی ناونیشانی وەرگرتنی نوێ' لە تابی وەرگرتندا بەکاربەرە بۆ زیادکردنی ناونیشانێکی نوێ.
واژۆکردن تەنها دەکرێت لەگەڵ ناونیشانەکان بە جۆری 'legacy'.
```

<!-- cache_translation_check_ku_404770844e641388040d1aa22837f2e7c03936c06e46700a382ac058d5b7bcb6 -->
```
        <source>Encrypt wallet</source>
        <translation>Şîfrekirina cizdên</translation>
    
ERR
The translation "Şîfrekirina cizdên" is not accurate. The word "cizdên" is not the correct Kurdish word for "wallet" in this context—it seems erroneous or possibly a typographical error. The correct word for "wallet" in Kurdish is "portefey" or "cüzdan".

Correct translation:
Şîfrekirina cüzdanê

Or, depending on dialect:
Şîfrekirina portefêyê
```

<!-- cache_translation_check_ku_6b53800c3f78ee21cf69f60737056b92332ba0f00e6a37bf894be9d4e2dbcdb4 -->
```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>او شوله بو ور کرنا کیف پاره گرکه رمزا کیفه وؤ یه پاره بزانی</translation>
    
ERR
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

<!-- cache_translation_check_ku_822560679b1417494d433e7e0f575e1d129d100261f12c0bbda58cd2dbb72947 -->
```
        <source>Change passphrase</source>
        <translation>Pêborînê biguherîne</translation>
    
ERR
The translation "Pêborînê biguherîne" is not entirely accurate. "Pêborîn" means "password", but "passphrase" in the context of Bitcoin wallets is better translated as "peyva-êrxas" or sometimes "şîfreyê dirêj", which conveys the idea of a phrase, not a single word password. Also, the command form "biguherîne" (change) is appropriate.

Correct translation:
Peyva-êrxasê biguherîne

or

Şîfreyê dirêj biguherîne

Either is acceptable, but "Peyva-êrxasê biguherîne" is most faithful to "Change passphrase".
```

<!-- cache_translation_check_ku_68a85bf5db9687165f9189774606515d19e71023723d1a7692d1f7bb7cacd997 -->
```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>دۆخی تایبەتمەندی چالاک کرا بۆ تابی گشتی. بۆ کردنەوەی بەهاکان، بەهاکان ڕێکخستنەکان&gt;ماسک.</translation>
    
ERR
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

<!-- cache_translation_check_ku_493c1674a64ec7d520c607d054bfa3583306a4428a543087e256784c1e17794c -->
```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>ناتوانێت دەست بکات بە bitcoin: کرتە بکە بۆ-پارەدانی کار</translation>
    
ERR
The translation uses Arabic script Kurdish ('ku-Arab') which is acceptable, but the translation is awkward and inaccurate. Specifically, "کرتە بکە بۆ-پارەدانی کار" is not a clear or idiomatic rendering of "click-to-pay handler"; it directly and erroneously translates "click-to-pay" word-for-word, and "handler" is rendered as "کار" (work/job) which is incorrect.

Correct translation:
ناتوانێت bitcoin-ڕێکخەرە کلیک-بۆ-پارەدان دەستپێ بکات

Or more idiomatically:
ناتوانێت بەستەری bitcoin بۆ پەرەدان بە کرتەکردن دەست پێ بکات

This preserves the technical intent and clarity.
```

<!-- cache_translation_check_ku_d7a5c0f832604ed4fb97d3de4e2c2e775a5a0baa566f4101530012f0ec655def -->
```
        <source>Type</source>
        <extracomment>Title of Peers Table column which describes the type of peer connection. The "type" describes why the connection exists.</extracomment>
        <translation>Cure</translation>
    
ERR
The translation is not accurate. The English word "Type" in this context should be translated to the Kurdish word "Tîp" which directly means "type" as in "kind" or "category." "Cure" is incorrect, as in Kurdish "cure" means more like "kind/sort", but the more direct translation—and the most commonly used in the context of tables or technical language—is "Tîp".

Correct translation:
Tîp
```

<!-- cache_translation_check_ku_20d312c705e5799af722d13ce2d215e0d844ef2237d5790c0a60a3b07943a20f -->
```
        <source>&amp;Amount:</source>
        <translation>&amp;سەرجەم:</translation>
    
ERR
The translation "&amp;سەرجەم:" means "&amp;Total:" in Kurdish (most likely the Sorani script), not "&amp;Amount:". "Amount" should be translated as "بڕ" or "ڕێژە" (commonly used words for "amount" in Kurdish).

Correct translation:
&بڕ:
```

<!-- cache_translation_check_ku_f2f43bf167c70aeced66240e49d4bedb96bbbcefd0a6394d77a0703fc40425b6 -->
```
        <source>When there is less transaction volume than space in the blocks, miners as well as relaying nodes may enforce a minimum fee. Paying only this minimum fee is just fine, but be aware that this can result in a never confirming transaction once there is more demand for bitcoin transactions than the network can process.</source>
        <translation>کاتێک قەبارەی مامەڵە کەمتر بێت لە بۆشایی بلۆکەکان، لەوانەیە کانەکان و گرێکانی گواستنەوە کەمترین کرێ جێبەجێ بکەن. پێدانی تەنیا ئەم کەمترین کرێیە تەنیا باشە، بەڵام ئاگاداربە کە ئەمە دەتوانێت ببێتە هۆی ئەوەی کە هەرگیز مامەڵەیەکی پشتڕاستکردنەوە ئەنجام بدرێت جارێک داواکاری زیاتر هەیە بۆ مامەڵەکانی بیت کۆبیتکۆ لەوەی کە تۆڕەکە دەتوانێت ئەنجامی بدات.</translation>
    
ERR
The translation has multiple issues:
- The phrase "مامەڵەیەکی پشتڕاستکردنەوە ئەنجام بدرێت" is an incorrect and confusing rendering of "a never confirming transaction".
- The translation uses "بیت کۆبیتکۆ" which seems to be a repetition or typo for "بیتکۆین".
- Some structure and flow problems make parts unclear or awkward, especially the last part.

Correct translation:
کاتێک قەبارەی مامەڵەکان کەمتر بێت لە بۆشایی بلۆکەکان، لەوانەیە کانەکان و خانووی گواستنەوەکان کەمترین کرێی پێویست جێبەجێ بکەن. پێدانی تەنیا ئەم کەمترین کرێیە باشە، بەڵام پێت بزانە ئەمە دەتوانێت بێت هۆی ئەوەی مامەڵەکەت هەرگیز پشتڕاست نەکرێت ئەگەر داواکاری مامەڵەی بیتکۆین زیاتر بێت لە ئەوەی تۆڕەکە دەتوانێت پڕۆسە بکات.
```

<!-- cache_translation_check_ku_2d904b8132e368eff388ffb942ed64c49506b8ce7458b83de2b5b22cef7e020d -->
```
        <source>Type</source>
        <translation>Cure</translation>
    
ERR
The translation is problematic. "Cure" is not the correct translation for "Type" in Kurdish ('ku'). It looks like a mistaken, unrelated English word.

Correct translation:
Tîp
```

<!-- cache_translation_check_ku_2d904b8132e368eff388ffb942ed64c49506b8ce7458b83de2b5b22cef7e020d -->
```
        <source>Type</source>
        <translation>Cure</translation>
    
ERR
The translation is problematic. "Cure" is not the correct translation for "Type" in Kurdish ('ku'). It looks like a mistaken, unrelated English word.

Correct translation:
Tîp
```

<!-- cache_translation_check_ku_e6f408fe9cfb49e7a620dc207c044369803bb69a086c86e35e424687a0914e57 -->
```
        <source>You need to rebuild the database using -reindex to go back to unpruned mode.  This will redownload the entire blockchain</source>
        <translation>پێویستە بنکەی زانیارییەکان دروست بکەیتەوە بە بەکارهێنانی -دووبارە ئیندێکس بۆ گەڕانەوە بۆ دۆخی نەپڕاو.  ئەمە هەموو بەربەستەکە دائەبەزێنێت</translation>
    
ERR
There are some issues in the translation:
- The option "-reindex" is incorrectly translated as "-دووبارە ئیندێکس" which is not the actual command and could confuse users. It should remain as "-reindex".
- The translation for "blockchain" is rendered as "بەربەستەکە" which more literally means "obstacle" or "barrier", not "blockchain". The correct term should be "زنجیرە-بلۆکەکان" or "بلۆکچێین" (common in technical Kurdish).
- The translation for "unpruned mode" as "دۆخی نەپڕاو" is correct.
- The final translation for "redownload the entire blockchain" as "ئەمە هەموو بەربەستەکە دائەبەزێنێت" is incorrect, as above.

Correct translation:
پێویستە بنکەی زانیارییەکان دووبارە دروست بکەیت بە بەکارهێنانی -reindex بۆ گەڕانەوە بۆ دۆخی نەپڕاو. ئەمە هەموو بلۆکچێینەکە دووبارە دابەزێنێت
```

<!-- cache_translation_check_ku_f1da53ef46c013c4823cfddcd9b8c270a3e84d311eecd50bc18ecce448b46036 -->
```
        <source>Could not find asmap file %s</source>
        <translation>ئاسماپ بدۆزرێتەوە %s نەتوانرا فایلی</translation>
    
ERR
The translation is unnatural and the word order is incorrect. The phrase "ئاسماپ بدۆزرێتەوە %s نەتوانرا فایلی" does not clearly convey "Could not find asmap file %s" in Kurdish ('ku'). The word "ئاسماپ" (asmap) comes first, which is confusing, and the verb "find" and "could not" are not structured properly.

Correct translation:
نەتوانرا فایلی asmap %s بدۆزرێتەوە

Or more naturally:
ناتوانرێت فایلی asmap %s بدۆزرێتەوە

Either will be clearer and correct in Kurdish.
```
</details>

Number of issues: 14.
