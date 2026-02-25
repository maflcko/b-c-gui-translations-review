# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>am</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bam%5D%20request)


<!-- cache_translation_check_am_daef632cd58a6585925e9c0ec563d1d787d3bc5b0d8db9513c054d76e7ff3aff -->
```
        <source>&amp;Edit</source>
        <translation> &amp;አርም</translation>
    
ERR
There is a leading space before the ampersand (" &amp;አርም"), which is a whitespace formatting issue. Also, "አርም" does not accurately translate "Edit" to Amharic; the appropriate translation for "Edit" is "አርትዕ". The ampersand should directly precede the translated word.

Correct translation:
&amp;አርትዕ
```

<!-- cache_translation_check_am_caedc154897b9403e735ab7f661103b703ac79f18cc6eda4d6db945ed4aebfbc -->
```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>በንዑስ ሰረዝ የተለዩ ፋይሎች</translation>
    
ERR
The translation "በንዑስ ሰረዝ የተለዩ ፋይሎች" translates to "files separated by comma", but in a plural and generic sense ("files" rather than "file"), and does not capture the intended format specification as precisely as possible.

A more accurate translation for "Comma separated file" in Amharic would be:
በንዑስ ሰረዝ የተለየ ፋይል

This keeps the singular "file", directly corresponding to the source. If you want to make it clear it's an actual file format, you might use:
በንዑስ ሰረዝ የተለየ ፋይል (CSV)

But for literal translation:
በንዑስ ሰረዝ የተለየ ፋይል
```

<!-- cache_translation_check_am_3c1afb7232845823832e16000be1c1dadff6b6bf0c9abefe89f999681f9e87eb -->
```
        <source>IP/Netmask</source>
        <translation>አይፒ/ኔትማስክ  IP/Netmask</translation>
    
ERR
The translation unnecessarily duplicates the source English text after the Amharic translation, which is redundant and may confuse users. The correct translation should only be in Amharic, unless some technical terms are commonly left in English, but duplication is not standard practice.

Correct translation:
አይፒ/ኔትማስክ
```

<!-- cache_translation_check_am_205f44415cf01308343a7d450b5bfe154da532c9f723acd9696a0c554bbfb7fe -->
```
        <source>Default system font "%1"</source>
        <translation>ነባሪ የስርዓት ቅርጸ-ቁምፊ "%1</translation>
    
ERR
The Amharic translation is missing the closing quotation mark after %1, which is present in the source. This creates a formatting inconsistency.

Correct translation:
ነባሪ የስርዓት ቅርጸ-ቁምፊ "%1"
```

<!-- cache_translation_check_am_73f29ac14b2ecfc00a028468830e415834d867ebfc7be77a9872442d56001b1d -->
```
        <source>Copy fee</source>
        <translation>ክፍያው ቅዳ</translation>
    
ERR
The translation "ክፍያው ቅዳ" literally means "cut the fee" instead of "copy fee". The verb "ቅዳ" means "cut", not "copy". The correct translation should use the verb for "copy", which is "ቅዳተ" or "ግልባጭ አድርግ".

Correct translation:
ክፍያውን ቅዳተ
or
ክፍያውን ግልባጭ አድርግ
```

<!-- cache_translation_check_am_d7a536b1f1a1af8df54b4d6006de718b992564cce2c7305acbd5e5fec015821d -->
```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>እርግጠኛ ኖት ዎሌት 1 ለማዘዋወር ይፈልጋሉ ?</translation>
    
ERR
The translation has several issues:
- It incorrectly translates "%1" as "1", losing the dynamic placeholder (format specifier).
- The phrase "እርግጠኛ ኖት" is an awkward construction; the idiomatic way to ask "Are you sure" is "እርግጠኛ ነዎት".
- Whitespace: There is a space before the question mark, which is not standard in Amharic.

Correct translation:
እርግጠኛ ነዎት የሚፈልጉት የዎሌትን &lt;i&gt;%1&lt;/i&gt; ማዘዋወር ነው?
```

<!-- cache_translation_check_am_4a365989cb386e891a0e4999b5e1f71742cbd6edab7defa39de7b841a6f60a84 -->
```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>ዋሌትን ማዛወር ይህንን ዋሌት አንድ ወይም ከዚያ በላይ ወደሆነ ገላጭ ዋሌቶች ይቀይረዋል።አዲስ ዋሌት ማዘጋጀት ያስፈልጋል ።ይህ ዋሌት ምንም ዓይነት የመመልከት ብቻ ስክሪፕቶችን የያዘ ከሆነ፣እነዚያን የመመልከት ብቻ ስክሪፕቶችን የያዘ አዲስ ዋሌት ይፈጠራል።ይህ ዋሌት ሊፈቱ የሚችሉ ነገር ግን የመመልከት ብቻ ያልሆኑ ስክሪፕቶችን የያዘ ከሆነ ፣ እነዚህን የያዘ አዲስ እና ልዩ የሆነ ዋሌት ይፈጠራል ።የማዛወር ሂደቱ ማዘዋወር ከመፈጸሙ በፊት የነዚህን ዋሌቶች መጠባበቂያ ቅጂ ይይዛል።ይህ መጠባበቂያ ቅጂ 1-2 legacy.bak ተብሎ ተሰይሞ በዋሌቱ ማውጫ ውስጥ ይገኛል።የተሳሳተ ዝውውር በሚከሰትበት ጊዜየመጠባበቂያ ቅጂው በ ዋሌት መመለሻ መተግበሪያ ውስጥ ይከማቻል።</translation>
    
ERR
The translation is generally understandable, but it has several issues:

1. Punctuation issues: Missing spaces after sentence-ending punctuation (።), creating run-on sentences.
2. Literal translations: Key technical terms such as "descriptor wallet", "watchonly scripts", or "solvable but not watched scripts" are not clearly and accurately rendered in Amharic; some are mistranslated or omitted.
3. Filename template "&lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak" is incorrectly rendered as "1-2 legacy.bak", which is inaccurate and omits critical information.
4. Unnecessary whitespace within sentences.
5. Some semantic drift, e.g. "የማዛወር ሂደቱ ማዘዋወር ከመፈጸሙ በፊት የነዚህን ዋሌቶች" is awkward.

Corrected translation:
ዋሌትን ማዛወር ይህንን ዋሌት ወደ አንድ ወይም ከዚያ በላይ የመግለጫ (descriptor) ዋሌቶች ያስቀድማል። አዲስ የዋሌት ቅጂ (backup) ማድረግ ይኖርቦታል። ይህ ዋሌት የመመልከት ብቻ (watchonly) ስክሪፕቶች ካሉበት በፊት፣ እነዚህን የመመልከት ብቻ ስክሪፕቶች የያዘ አዲስ ዋሌት ይፈጠራል። ይህ ዋሌት ማፍቃት የሚችሉ ነገር ግን የመመልከት ብቻ ያልሆኑ ስክሪፕቶች ካሉበት፣ እነዚህን የያዘ የተለየ አዲስ ዋሌት ይፈጠራል።

የማዛወር ሂደቱ ከመጀመሩ በፊት የዋሌት ቅጂ ይመስራል። ይህ የቅጂ ፋይል &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak ተብሎ በዋሌቱ ማውጫ ውስጥ ይገኛል። በስህተት ዝውውር ቢፈጠር፣ የቅጂው ፋይል በ “ዋሌት መመለሻ” ተግባር መድረሻ ሊመለስ ይችላል።
```

<!-- cache_translation_check_am_dd3f0f309e40dd2a1d0760550209afad48aeda21ac0ab04cb02a695f7199fdf8 -->
```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>የመመልከት ብቻ ስክሪፕቶች'%1'.ወደ ተሰኘው ዋሌት ተዛውረዋል </translation>
    
ERR
There are whitespace and punctuation format issues in the translation. The apostrophe in '%1' should be followed by a space before "ወደ", and there should be a space after "ስክሪፕቶች". Also, the Amharic translation could be made smoother. Additionally, there shouldn't be a period after '%1'.

Correct translation:
የመመልከት ብቻ ስክሪፕቶች ወደ '%1' ተብሎ የተሰኘው አዲስ ዋሌት ተዛውረዋል
```

<!-- cache_translation_check_am_afc9427c96c5ec48fb724f4ea9c6ce53b48450ac083ad52a769f029e764635e1 -->
```
        <source>About %1</source>
        <translation>ስለ እኛ %1</translation>
    
ERR
The translation "ስለ እኛ %1" is problematic. "ስለ እኛ" means "about us" rather than "about %1", where %1 is a variable (e.g., "About Bitcoin Core"). The correct translation should be "ስለ %1".

Correct translation:
ስለ %1
```

<!-- cache_translation_check_am_bacc9d36e4077e25ae02a8fa5744824a4d987b0e2e57550c8eaf70f898bd1cb0 -->
```
        <source>Form</source>
        <translation>ከ</translation>
    
ERR
The translation "ከ" means "from" or "of" in Amharic, which is not equivalent to "Form." This is an erroneous translation.

Correct translation:
ቅጽ
```

<!-- cache_translation_check_am_bacc9d36e4077e25ae02a8fa5744824a4d987b0e2e57550c8eaf70f898bd1cb0 -->
```
        <source>Form</source>
        <translation>ከ</translation>
    
ERR
The translation "ከ" means "from" or "of" in Amharic, which is not equivalent to "Form." This is an erroneous translation.

Correct translation:
ቅጽ
```

<!-- cache_translation_check_am_73f29ac14b2ecfc00a028468830e415834d867ebfc7be77a9872442d56001b1d -->
```
        <source>Copy fee</source>
        <translation>ክፍያው ቅዳ</translation>
    
ERR
The translation "ክፍያው ቅዳ" literally means "cut the fee" instead of "copy fee". The verb "ቅዳ" means "cut", not "copy". The correct translation should use the verb for "copy", which is "ቅዳተ" or "ግልባጭ አድርግ".

Correct translation:
ክፍያውን ቅዳተ
or
ክፍያውን ግልባጭ አድርግ
```

<!-- cache_translation_check_am_a95a4d302afe2713fc09de2d182cc042f1605af9d32cde28940aa35aa20eb4c7 -->
```
        <source>%1 from wallet '%2'</source>
        <translation>%1 ከዋሌት %2'</translation>
    
ERR
The translation is missing the opening single quote before %2 and has an extra or misplaced single quote after %2. It also lacks the word "from" ("ከ") formatted properly with both parameters and doesn't encapsulate the wallet name in single quotes as in the source.

Correct translation:
%1 ከ'ዋሌት '%2'
```

<!-- cache_translation_check_am_caedc154897b9403e735ab7f661103b703ac79f18cc6eda4d6db945ed4aebfbc -->
```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>በንዑስ ሰረዝ የተለዩ ፋይሎች</translation>
    
ERR
The translation "በንዑስ ሰረዝ የተለዩ ፋይሎች" translates to "files separated by comma", but in a plural and generic sense ("files" rather than "file"), and does not capture the intended format specification as precisely as possible.

A more accurate translation for "Comma separated file" in Amharic would be:
በንዑስ ሰረዝ የተለየ ፋይል

This keeps the singular "file", directly corresponding to the source. If you want to make it clear it's an actual file format, you might use:
በንዑስ ሰረዝ የተለየ ፋይል (CSV)

But for literal translation:
በንዑስ ሰረዝ የተለየ ፋይል
```

<!-- cache_translation_check_am_57f4ebc82b1ff90822dcd7093d5fe6127c8cc0bfc1906fcdadf72b6e01976ffb -->
```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>ከክፍያ-ነፃ PSBT ወደ ቅንጥብ ሰሌዳ ተቀድቷል።</translation>
    
ERR
The translation incorrectly renders "Fee-bump" as "ክፍያ-ነፃ", which means "free of charge" or "payment-free" in Amharic. However, "Fee-bump" in the context of Bitcoin refers to an increase in the transaction fee (e.g., to speed up confirmation). The translation should reflect the correct technical meaning.

Correct translation:
"የክፍያ መጨመሪያ PSBT ወደ ቅንጥብ ሰሌዳ ተቀድቷል።"
```
</details>

Number of issues: 15.
