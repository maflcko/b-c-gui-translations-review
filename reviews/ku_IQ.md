# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ku_IQ</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bku_IQ%5D%20low%20quality)


```
        <source>Choose the address to receive coins with</source>
        <translation>ناونیشانەکە هەڵبژێرە بۆ وەرگرتنی دراوەکان لەگەڵ</translation>
    
YES - The translation "ناونیشانەکە هەڵبژێرە بۆ وەرگرتنی دراوەکان لەگەڵ" incorrectly includes "لەگەڵ" (with) at the end, making it grammatically awkward and potentially confusing in the context of Bitcoin addresses.

Correct translation: ناونیشانەکە هەڵبژێرە بۆ وەرگرتنی دراوەکان
(Choose the address to receive coins)
```

```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>ئەمانە ناونیشانی بیتکۆبیتەکانی تۆنە بۆ ناردنی پارەدانەکان. هەمیشە بڕی و ناونیشانی وەرگرەکان بپشکنە پێش ناردنی دراوەکان.</translation>
    
YES, the translation contains erroneous content. The word "بیتکۆبیتەکانی" is a misspelling of "بیتکۆینەکان" (Bitcoin).

NO, the translation is unproblematic. The translation correctly conveys the meaning of the source text without any unwanted content, erroneous content, or spam. All format specifiers and whitespace are maintained correctly.
```

```
        <source>Show passphrase</source>
        <translation>نیشان دانا ناوه چونه</translation>
    
YES, The translation is problematic. The word "ناوه چونه" translates to "name of the season" which is not relevant to the context of "passphrase".

The correct translation should be: "نیشاندانی وشەی نھێنی"
```

```
        <source>Encrypt wallet</source>
        <translation>کیف خو یه پاره رمزه دانینه بر</translation>
    
YES, the translation is erroneous. The Kurdish word "کیف" (kif) means bag or purse, and "خو" (xw) is a possessive suffix meaning "your". "یه" (ya) is an indefinite article and "پاره" (para) means money. "رمزه" (ramz) means code or cipher and "دانه" (dana) means seed or to plant. "بر" (br) means brother or on. The translation therefore seems to mean "Your money bag encrypt plant brother" which is nonsensical in the context of Bitcoin.

The correct translation for "Encrypt wallet" would be:

<translation>پارێزراوکردنی هه‌موو ئه‌دره‌سه‌کان</translation>
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>او شوله بو ور کرنا کیف پاره گرکه رمزا کیفه وؤ یه پاره بزانی</translation>
    
YES, The translation is inaccurate and does not convey the original meaning. It seems to be a nonsensical arrangement of words in Kurdish. The original sentence is about needing a wallet passphrase to unlock the wallet for an operation.

Correct translation: پێویستت بە وشەی نهێنیی خولامەکەت هەیە بۆ کردنەوەی خولامەکە.
```

```
        <source>Change passphrase</source>
        <translation>Pêborînê biguherîne</translation>
    
YES, The translation is problematic. The word "Pêborînê" translates to "forgiveness" in English, which is not related to the context of Bitcoin and changing a passphrase. The correct translation for "passphrase" in this context would be "şîfreya derbasbûnê" or simply "şîfreya we".

Correct translation: Şîfreya derbasbûnê biguherîne
```

```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>به راستی اون هشیارن کا دخازن بو کیف خو یه پاره رمزه دانین</translation>
    
UNK_LANG
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>ناونیشان "%1" پێشتر هەبوو وەک ناونیشانی وەرگرتن لەگەڵ ناونیشانی "%2" و بۆیە ناتوانرێت زیاد بکرێت وەک ناونیشانی ناردن.</translation>
    
YES, The translation is problematic because the word "ناونیشانی" (address) is repeated twice incorrectly. Additionally, the phrase "لەگەڵ ناونیشانی" (with address) is not the correct translation for "with label".

NO
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>دۆخی تایبەتمەندی چالاک کرا بۆ تابی گشتی. بۆ کردنەوەی بەهاکان، بەهاکان ڕێکخستنەکان&gt;ماسک.</translation>
    
YES, The translation is problematic. The phrase "ڕێکخستنەکان>ماسک" is not a correct translation of "Settings->Mask values". The correct translation should be "ڕێکخستنەکان > شاردنەوەی بەهاکان".
NO
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>ناتوانێت دەست بکات بە bitcoin: کرتە بکە بۆ-پارەدانی کار</translation>
    
YES, The translation is problematic because "کرتە بکە بۆ-پارەدانی کار" is a literal and awkward translation of "click-to-pay handler" that doesn't convey the intended meaning in the context of Bitcoin. It implies a physical payment card rather than a software function.

NO
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>تکایە، پێداچوونەوە بکە بە پێشنیارەکانی مامەڵەکەت. ئەمە مامەڵەیەکی بیتکۆپەکی کەبەشیونکراو (PSBT) بەرهەمدەهێنێت کە دەتوانیت پاشەکەوتی بکەیت یان کۆپی بکەیت و پاشان واژووی بکەیت لەگەڵ بۆ ئەوەی بە دەرهێڵی %1 جزدانێک، یان جزدانێکی رەقەواڵەی گونجاو بە PSBT.</translation>
    
YES, The translation is not entirely accurate and has some grammatical errors. The phrase "بۆ ئەوەی بە دەرهێڵی %1 جزدانێک" translates to "in order to with a %1 wallet", which is awkward. A more natural phrasing would be "بە بەکارهێنانی جزدانێکی %1" (using a %1 wallet) or "لەگەڵ جزدانێکی %1" (with a %1 wallet). Additionally, "جزدانێکی رەقەواڵەی گونجاو بە PSBT" is a bit clunky. It would be better to say "جزدانێکی ڕەقەواڵەی گونجاو لەگەڵ PSBT" (a hardware wallet compatible with PSBT).

Here's a corrected translation:

تکایە، پێداچوونەوە بکە بە پێشنیارەکانی مامەڵەکەت. ئەمە مامەڵەیەکی بیتکۆین بەشێوەی واژۆکراوی نیمچە (PSBT) بەرهەمدەهێنێت کە دەتوانیت پاشەکەوتی بکەیت یان کۆپی بکەیت و پاشان واژووی بکەیت بە بەکارهێنانی جزدانێکی %1 کە ئۆفلاینە، یان جزدانێکی ڕەقەواڵەی گونجاو لەگەڵ PSBT.
```

```
        <source>Prune configured below the minimum of %d MiB.  Please use a higher number.</source>
        <translation>پڕە لە خوارەوەی کەمترین %d MiB شێوەبەند کراوە.  تکایە ژمارەیەکی بەرزتر بەکاربێنە.</translation>
    
YES
The word "Prune" is incorrectly translated as "پڕە", which means "it is full". This completely changes the meaning of the sentence and makes it nonsensical. The correct term should be "بژارکردن" or "کەمکردنەوە" (pruning/reduction).

Correct translation:
بژارکردن بۆ کەمتر لە کەمترین بڕی (%d MiB) ڕێکخراوە. تکایە ژمارەیەکی بەرزتر بەکاربێنە.
```

```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of pruned node)</source>
        <translation>پرە: دوایین هاودەمکردنی جزدان لە داتای بەپێز دەچێت. پێویستە دووبارە -ئیندێکس بکەیتەوە (هەموو بەربەستەکە دابەزێنە دووبارە لە حاڵەتی گرێی هەڵکراو)</translation>
    
YES, The translation contains erroneous content. The word "wallet" is translated to "جزدان" which means "bag" in Kurdish. In the context of Bitcoin, "wallet" refers to a digital wallet, not a physical bag. The word "pruned" is translated to "بەپێز" which means "delicious" or "tasty" in Kurdish. In the context of Bitcoin, "pruned" refers to a node that has removed older blocks from the blockchain to save disk space.

The correct translation should be:
پرە: دوایین هاودەمکردنی خەزێنەکە لە داتاکانی کەمکراوە تێپەڕیوە. پێویستە دووبارە -ئیندێکس بکەیتەوە (هەموو زنجیرەبڵۆکەکە دابەزێنە دووبارە لە حاڵەتی گرێی کەمکراوە)
```

```
        <source>You need to rebuild the database using -reindex to go back to unpruned mode.  This will redownload the entire blockchain</source>
        <translation>پێویستە بنکەی زانیارییەکان دروست بکەیتەوە بە بەکارهێنانی -دووبارە ئیندێکس بۆ گەڕانەوە بۆ دۆخی نەپڕاو.  ئەمە هەموو بەربەستەکە دائەبەزێنێت</translation>
    
YES: The translation of "blockchain" to "بەربەستەکە" (barrier) is incorrect. The correct translation should be "زنجیرە بلۆکەکە" (blockchain).

NO: پێویستە بنکەی زانیارییەکان دروست بکەیتەوە بە بەکارهێنانی -دووبارە ئیندێکس بۆ گەڕانەوە بۆ دۆخی نەپڕاو. ئەمە هەموو زنجیرە بلۆکەکە دائەبەزێنێت
```

```
        <source>Could not find asmap file %s</source>
        <translation>ئاسماپ بدۆزرێتەوە %s نەتوانرا فایلی</translation>
    
YES, The translation is problematic because the word order is incorrect, and the sentence structure is unnatural in Kurdish. The "%s" format specifier is also misplaced.

Correct translation: نەتوانرا فایلی asmap %s بدۆزرێتەوە
```

```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>هەڵە: کلیلی پوول ڕایکرد، تکایە سەرەتا پەیوەندی بکە بە پڕکردنەوەی کلیل</translation>
    
YES, The translation contains a mistranslation of "keypoolrefill". It translates to "filling the key" which is not the correct meaning. The correct translation should convey the idea of refilling the pool of keys.

NO
```
</details>
