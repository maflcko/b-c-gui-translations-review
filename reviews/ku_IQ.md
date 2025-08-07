# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ku_IQ</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bku_IQ%5D%20low%20quality)


```
        <source>Encrypt wallet</source>
        <translation>کیف خو یه پاره رمزه دانینه بر</translation>
    
YES
The translation has errors and unnatural phrasing. The phrase "کیف خو یه پاره رمزه دانینه بر" is not correct or natural in Central Kurdish (ku_IQ). "کیف" means "bag," and "خو یه پاره" is not idiomatic for "wallet." Also, the grammar is awkward.

Correct translation:
کیف پاره‌ت رمز بکە

This phrase directly and naturally means "Encrypt your wallet" in Central Kurdish.
```

```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>به راستی اون هشیارن کا دخازن بو کیف خو یه پاره رمزه دانین</translation>
    
YES
The translation has several issues:
1. The use of "به راستی اون هشیارن کا دخازن" is awkward and not standard in Kurdish (Kurmanji as used in Iraq, i.e., 'ku_IQ'). It reads more like bad Sorani/Kurmanji mix and includes spelling mistakes.
2. "کیف خو یه پاره" is nonstandard for "your wallet" and is hard to parse.
3. The translation of "encrypt" to "رمزه دانین" is awkward and could more naturally use "رمز بکەیت" (remz bikêt) or "پارێزگای بکەیت" (to protect).
4. The translation suffers from typographical and grammatical errors.

Correct translation:
ئایا دڵنیایت دەته‌وێت جزدانەکەت بدرێتە رمز؟ 

Or, more literally:
ئایا دڵنیایت دا ئەوە جزدانەکەت بكەیت بە رمز؟

This is a much clearer Kurmanji (ku_IQ) translation.
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>دۆخی تایبەتمەندی چالاک کرا بۆ تابی گشتی. بۆ کردنەوەی بەهاکان، بەهاکان ڕێکخستنەکان&gt;ماسک.</translation>
    
YES
The translation has issues with clarity and accuracy. The phrase "Settings-&gt;Mask values" is not translated clearly and is rendered as a confusing phrase "بەهاکان ڕێکخستنەکان&gt;ماسک". The verb forms in "بۆ کردنەوەی بەهاکان" are awkward, and the mention of "Privacy mode" is not correctly rendered (it only says "دۆخی تایبەتمەندی", which means "special mode", not "privacy mode"). Also, the term "unmask" should be properly translated.

Correct translation:
دۆخی نهێنی بۆ تابێ گشتی چالاک کرا. بۆ نمایانکردنی بەهاکان، تیکەڵی ڕێکخستنەکان -> ماسککردنی بەهاکان بسڕەوە.
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

Number of issues: 6.
