# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ku_IQ</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bku_IQ%5D%20low%20quality)


```
        <source>Show passphrase</source>
        <translation>نیشان دانا ناوه چونه</translation>
    
YES
The translation "نیشان دانا ناوه چونه" is inaccurate and problematic. The correct translation for "Show passphrase" in Kurdish (Sorani, Iraq) should be closer to "پیشاندانی وشەی نهێنی" or "نیشاندانی وشەی نهێنی".

Correct translation:
پیشاندانی وشەی نهێنی
```

```
        <source>Encrypt wallet</source>
        <translation>کیف خو یه پاره رمزه دانینه بر</translation>
    
YES
The translation has several issues:
1. The term "wallet" is most commonly translated as "کیف پاره" or just "کیف", but in this translation there is an extraneous space and use of "خو" which means "self", making "کیف خو یه پاره" incorrect or at least awkward.
2. The verb phrase "رمزه دانینه بر" is awkward and unconventional—the standard form is "رمزدانه‌" or "بەرمز بکە".
3. There is stray whitespace at the beginning of the translation and within the words.

Correct translation:
"کیفی پارە رمزدانه‌"

Or a more commonly accepted form:
"کیفی پارە بەرمز بکە"
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>او شوله بو ور کرنا کیف پاره گرکه رمزا کیفه وؤ یه پاره بزانی</translation>
    
YES
The translation is problematic. The text is not accurate, contains Kurdish (Kurmanji or Sorani) mixed with possibly grammatically incorrect or jumbled structure. The sentence should clearly state that to perform this operation, the wallet passphrase is needed to unlock the wallet.

Correct translation:
ئەم كارە پێویستی بە وشەی نهێنی وەلیتە بۆ كردنەوەی وەلیتەكە.

Or in Kurmanji, if that’s the intended variety:
Ev kiryar hewce ye ku şîfreya veşartî ya fêrgehê were bikar anîn da ku fêrgeh were vekirin.

Make sure to match the script and dialect your UI uses, usually Sorani script for 'ku_IQ'.
```

```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>به راستی اون هشیارن کا دخازن بو کیف خو یه پاره رمزه دانین</translation>
    
YES
The translation contains spelling and grammar mistakes, and the sentence structure is awkward. The phrase "به راستی اون هشیارن کا دخازن بو کیف خو یه پاره رمزه دانین" is incorrect.

Correct translation:
ئایا دڵنیایت دەتەوێت جزدانەکەت وشەی نهێنی بکەیت؟ 

or alternatively:
ئایا دڵنیایت دەتەوێت جزدانەکەت قەلەو بکەیت؟

Explanation: The original translation has random words, incorrect inflection, and nonstandard wording. The corrected forms above accurately reflect "Are you sure you wish to encrypt your wallet?" in ku_IQ (Kurdish, Sorani, Iraq).
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>دۆخی تایبەتمەندی چالاک کرا بۆ تابی گشتی. بۆ کردنەوەی بەهاکان، بەهاکان ڕێکخستنەکان&gt;ماسک.</translation>
    
YES
The translation is inaccurate and partially unclear. The phrase "بۆ کردنەوەی بەهاکان، بەهاکان ڕێکخستنەکان>ماسک." is not a faithful rendering of "To unmask the values, uncheck Settings->Mask values." It also introduces repetition and loses instructional clarity.

Correct translation:
دۆخی تایبەتمەندی بۆ تابی پێشوەختە چالاک کرا. بۆ دەرکردنی بەهاکان، ئاراستەکە Settings->Mask values ڕەشنە بکە.

Note: Make sure that "Overview" is translated as "تابی پێشوەختە" or an equivalent in Kurdish (ku_IQ) technical context, and format consistency (like arrows) is preserved.
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>ناتوانێت دەست بکات بە bitcoin: کرتە بکە بۆ-پارەدانی کار</translation>
    
YES
The translation is problematic due to unnatural phrasing and awkward splitting. For example, "کرتە بکە بۆ-پارەدانی کار" is an unclear translation of "click-to-pay handler," and "ناتوانێت دەست بکات بە bitcoin" does not properly capture "Cannot start bitcoin". A better translation would be:

ناتوانیم bitcoin: بەرهێنەرێ "کرتە-بۆ-پارەدان" دەست پێ بکەم

Correct translation:
ناتوانیم bitcoin: بەرهێنەرێ "کرتە-بۆ-پارەدان" دەست پێ بکەم
```

```
        <source>You need to rebuild the database using -reindex to go back to unpruned mode.  This will redownload the entire blockchain</source>
        <translation>پێویستە بنکەی زانیارییەکان دروست بکەیتەوە بە بەکارهێنانی -دووبارە ئیندێکس بۆ گەڕانەوە بۆ دۆخی نەپڕاو.  ئەمە هەموو بەربەستەکە دائەبەزێنێت</translation>
    
YES
There are several issues in the translation:
- The parameter "-reindex" is incorrectly translated as "-دووبارە ئیندێکس", which mixes script and is not the term used in technical contexts and should be kept as "-reindex".
- "redownload the entire blockchain" is mistranslated as "هەموو بەربەستەکە دائەبەزێنێت" ("download the whole obstacle"), but "بەربەست" does not mean blockchain. The standard term for blockchain in Sorani Kurdish is "زنجیرەی بەلوکەکان" or "بلۆکچەین".
- The rest contains some sloppiness, e.g., "دروست بکەیتەوە" for "rebuild", but the sense with "بنکەی زانیارییەکان" is correct.

Correct translation:
پێویستە بنکەی زانیارییەکان بە دووبارە بەکاربردنی -reindex دروست بکەیتەوە بۆ گەڕانەوە بۆ دۆخی نەپڕاو.  ئەمە هەموو زنجیرەی بەلوکەکان دووبارە دابەزێنێت.
```

```
        <source>Could not find asmap file %s</source>
        <translation>ئاسماپ بدۆزرێتەوە %s نەتوانرا فایلی</translation>
    
YES
The translation has word order and clarity issues. The verb placement and the possessive structure are incorrect, making the sentence unnatural in Kurdish (Sorani, ku_IQ). It should be clear that "could not find" refers to the asmap file.

Correct translation:
نەتوانرا فایلەی asmap %s بدۆزرێتەوە

Or a more natural alternative:
فایلەی asmap %s نەدۆزرایەوە

Both properly preserve the format specifier (%s) and word order.
```

```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>هەڵە: کلیلی پوول ڕایکرد، تکایە سەرەتا پەیوەندی بکە بە پڕکردنەوەی کلیل</translation>
    
YES
The translation is understandable but not fully accurate in the context of Bitcoin. "کلیلی پوول ڕایکرد" is a literal and unclear rendering for "Keypool ran out". Also, "پەیوەندی بکە بە پڕکردنەوەی کلیل" translates as "please contact key refill", which is not accurate; it should be an instruction to perform (call) the "keypoolrefill" action (probably a command).

Correct translation:
هەڵە: کتێبەی کلیلیت تەواو بوو، تکایە یەکەم "keypoolrefill" بەکاربهێنە.
```
</details>
