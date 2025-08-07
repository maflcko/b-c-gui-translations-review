# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>am</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bam%5D%20low%20quality)


```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>በንዑስ ሰረዝ የተለዩ ፋይሎች</translation>
    
YES
The translation "በንዑስ ሰረዝ የተለዩ ፋይሎች" translates to "files separated by comma", but in a plural and generic sense ("files" rather than "file"), and does not capture the intended format specification as precisely as possible.

A more accurate translation for "Comma separated file" in Amharic would be:
በንዑስ ሰረዝ የተለየ ፋይል

This keeps the singular "file", directly corresponding to the source. If you want to make it clear it's an actual file format, you might use:
በንዑስ ሰረዝ የተለየ ፋይል (CSV)

But for literal translation:
በንዑስ ሰረዝ የተለየ ፋይል
```

```
        <source>IP/Netmask</source>
        <translation>አይፒ/ኔትማስክ  IP/Netmask</translation>
    
YES
The translation unnecessarily duplicates the source English text after the Amharic translation, which is redundant and may confuse users. The correct translation should only be in Amharic, unless some technical terms are commonly left in English, but duplication is not standard practice.

Correct translation:
አይፒ/ኔትማስክ
```

```
        <source>Default system font "%1"</source>
        <translation>ነባሪ የስርዓት ቅርጸ-ቁምፊ "%1</translation>
    
YES
The Amharic translation is missing the closing quotation mark after %1, which is present in the source. This creates a formatting inconsistency.

Correct translation:
ነባሪ የስርዓት ቅርጸ-ቁምፊ "%1"
```

```
        <source>Error creating wallet</source>
        <translation>ዋሌትዎን ለፍጠር ተሳስተዋል </translation>
    
YES
The translation has an error in the verb tense and format. The original English says "Error creating wallet," which is a short error message, essentially "Failed to create wallet." The Amharic translation says "ዋሌትዎን ለፍጠር ተሳስተዋል", which awkwardly translates as "There was a mistake to create your wallet." Also, there is an unnecessary space at the end.

A better, concise translation would be:
ዋሌት ማፍረር ተሳናቸው

Or, more directly:
ዋሌት ማፍጠር ስህተት ተከስቷል

So:

Correct translation:
ዋሌት ማፍጠር ስህተት ተከስቷል
```

```
        <source>Copy fee</source>
        <translation>ክፍያው ቅዳ</translation>
    
YES
The translation "ክፍያው ቅዳ" literally means "cut the fee" instead of "copy fee". The verb "ቅዳ" means "cut", not "copy". The correct translation should use the verb for "copy", which is "ቅዳተ" or "ግልባጭ አድርግ".

Correct translation:
ክፍያውን ቅዳተ
or
ክፍያውን ግልባጭ አድርግ
```

```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>ዋሌትን ማዛወር ይህንን ዋሌት አንድ ወይም ከዚያ በላይ ወደሆነ ገላጭ ዋሌቶች ይቀይረዋል።አዲስ ዋሌት ማዘጋጀት ያስፈልጋል ።ይህ ዋሌት ምንም ዓይነት የመመልከት ብቻ ስክሪፕቶችን የያዘ ከሆነ፣እነዚያን የመመልከት ብቻ ስክሪፕቶችን የያዘ አዲስ ዋሌት ይፈጠራል።ይህ ዋሌት ሊፈቱ የሚችሉ ነገር ግን የመመልከት ብቻ ያልሆኑ ስክሪፕቶችን የያዘ ከሆነ ፣ እነዚህን የያዘ አዲስ እና ልዩ የሆነ ዋሌት ይፈጠራል ።የማዛወር ሂደቱ ማዘዋወር ከመፈጸሙ በፊት የነዚህን ዋሌቶች መጠባበቂያ ቅጂ ይይዛል።ይህ መጠባበቂያ ቅጂ 1-2 legacy.bak ተብሎ ተሰይሞ በዋሌቱ ማውጫ ውስጥ ይገኛል።የተሳሳተ ዝውውር በሚከሰትበት ጊዜየመጠባበቂያ ቅጂው በ ዋሌት መመለሻ መተግበሪያ ውስጥ ይከማቻል።</translation>
    
YES
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

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>የመመልከት ብቻ ስክሪፕቶች'%1'.ወደ ተሰኘው ዋሌት ተዛውረዋል </translation>
    
YES
There are whitespace and punctuation format issues in the translation. The apostrophe in '%1' should be followed by a space before "ወደ", and there should be a space after "ስክሪፕቶች". Also, the Amharic translation could be made smoother. Additionally, there shouldn't be a period after '%1'.

Correct translation:
የመመልከት ብቻ ስክሪፕቶች ወደ '%1' ተብሎ የተሰኘው አዲስ ዋሌት ተዛውረዋል
```

```
        <source>About %1</source>
        <translation>ስለ እኛ %1</translation>
    
YES
The translation "ስለ እኛ %1" is problematic. "ስለ እኛ" means "about us" rather than "about %1", where %1 is a variable (e.g., "About Bitcoin Core"). The correct translation should be "ስለ %1".

Correct translation:
ስለ %1
```

```
        <source>Form</source>
        <translation>ከ</translation>
    
YES
The translation "ከ" means "from" or "of" in Amharic, which is not equivalent to "Form." This is an erroneous translation.

Correct translation:
ቅጽ
```

```
        <source>Form</source>
        <translation>ከ</translation>
    
YES
The translation "ከ" means "from" or "of" in Amharic, which is not equivalent to "Form." This is an erroneous translation.

Correct translation:
ቅጽ
```

```
        <source>Copy fee</source>
        <translation>ክፍያው ቅዳ</translation>
    
YES
The translation "ክፍያው ቅዳ" literally means "cut the fee" instead of "copy fee". The verb "ቅዳ" means "cut", not "copy". The correct translation should use the verb for "copy", which is "ቅዳተ" or "ግልባጭ አድርግ".

Correct translation:
ክፍያውን ቅዳተ
or
ክፍያውን ግልባጭ አድርግ
```

```
        <source>%1 from wallet '%2'</source>
        <translation>%1 ከዋሌት %2'</translation>
    
YES
The translation is missing the opening single quote before %2 and has an extra or misplaced single quote after %2. It also lacks the word "from" ("ከ") formatted properly with both parameters and doesn't encapsulate the wallet name in single quotes as in the source.

Correct translation:
%1 ከ'ዋሌት '%2'
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>በንዑስ ሰረዝ የተለዩ ፋይሎች</translation>
    
YES
The translation "በንዑስ ሰረዝ የተለዩ ፋይሎች" translates to "files separated by comma", but in a plural and generic sense ("files" rather than "file"), and does not capture the intended format specification as precisely as possible.

A more accurate translation for "Comma separated file" in Amharic would be:
በንዑስ ሰረዝ የተለየ ፋይል

This keeps the singular "file", directly corresponding to the source. If you want to make it clear it's an actual file format, you might use:
በንዑስ ሰረዝ የተለየ ፋይል (CSV)

But for literal translation:
በንዑስ ሰረዝ የተለየ ፋይል
```

```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>ከክፍያ-ነፃ PSBT ወደ ቅንጥብ ሰሌዳ ተቀድቷል።</translation>
    
YES
The translation incorrectly renders "Fee-bump" as "ክፍያ-ነፃ", which means "free of charge" or "payment-free" in Amharic. However, "Fee-bump" in the context of Bitcoin refers to an increase in the transaction fee (e.g., to speed up confirmation). The translation should reflect the correct technical meaning.

Correct translation:
"የክፍያ መጨመሪያ PSBT ወደ ቅንጥብ ሰሌዳ ተቀድቷል።"
```
</details>

Number of issues: 14.
