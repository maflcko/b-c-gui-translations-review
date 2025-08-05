# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>am</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bam%5D%20low%20quality)


```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>በንዑስ ሰረዝ የተለዩ ፋይሎች</translation>
    
YES
The Amharic translation "በንዑስ ሰረዝ የተለዩ ፋይሎች" literally means "Files that are separated by comma," which is understandable. However, the English source refers to the file format (i.e., "Comma separated file" or ideally "Comma-separated values file"), not the files themselves.

A more accurate and idiomatic translation that is used for CSV (Comma-separated values) files in Amharic is:
በንዑስ ሰረዝ የተለየ ፋይል

So, the correct translation should be:
በንዑስ ሰረዝ የተለየ ፋይል
```

```
        <source>IP/Netmask</source>
        <translation>አይፒ/ኔትማስክ  IP/Netmask</translation>
    
YES
The translation redundantly includes both the Amharic translation and the original English text, which is unnecessary. Also, there is an extra space before "IP/Netmask". The correct translation should only be in Amharic, unless technical terms like "IP" and "Netmask" are not localized; in that case, transliteration may be used or the English terms may be retained, but not duplicated.

Correct translation:
አይፒ/ኔትማስክ
```

```
        <source>Default system font "%1"</source>
        <translation>ነባሪ የስርዓት ቅርጸ-ቁምፊ "%1</translation>
    
YES
The quotation marks in the translation are not balanced; the closing quote after %1 is missing. This can cause formatting issues.

Correct translation:
ነባሪ የስርዓት ቅርጸ-ቁምፊ "%1"
```

```
        <source>Error creating wallet</source>
        <translation>ዋሌትዎን ለፍጠር ተሳስተዋል </translation>
    
YES
The translation is not fully accurate. The English "Error creating wallet" is a statement about an error that happened during wallet creation, but the translation "ዋሌትዎን ለፍጠር ተሳስተዋል" is more like "There was a mistake to create your wallet", which is slightly awkward and informal in Amharic.

A more precise and natural translation would be:
ዋሌት ሲፈጠር ስህተት ተፈጥሯል

Also, there is a stray space at the end of the translation.

Correct translation:
ዋሌት ሲፈጠር ስህተት ተፈጥሯል
```

```
        <source>Copy fee</source>
        <translation>ክፍያው ቅዳ</translation>
    
YES
The translation "ክፍያው ቅዳ" is problematic. "Copy fee" should refer to copying (i.e., transferring to clipboard) the fee value, not an instruction to "cut" or "remove" the fee. "ቅዳ" more closely translates to "cut" rather than "copy." The correct translation should be:

Correct translation:
"ክፍያውን ቅዳ" should be replaced with "ክፍያውን ቅዳል" or "ክፍያውን ቅዳ" if "copy" is meant as an instruction. However, the correct word for "copy" in Amharic is "ገልብጥ" or "ቅዳው".

Best translation:
ክፍያውን ገልብጥ
```

```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>ዋሌትን ማዛወር ይህንን ዋሌት አንድ ወይም ከዚያ በላይ ወደሆነ ገላጭ ዋሌቶች ይቀይረዋል።አዲስ ዋሌት ማዘጋጀት ያስፈልጋል ።ይህ ዋሌት ምንም ዓይነት የመመልከት ብቻ ስክሪፕቶችን የያዘ ከሆነ፣እነዚያን የመመልከት ብቻ ስክሪፕቶችን የያዘ አዲስ ዋሌት ይፈጠራል።ይህ ዋሌት ሊፈቱ የሚችሉ ነገር ግን የመመልከት ብቻ ያልሆኑ ስክሪፕቶችን የያዘ ከሆነ ፣ እነዚህን የያዘ አዲስ እና ልዩ የሆነ ዋሌት ይፈጠራል ።የማዛወር ሂደቱ ማዘዋወር ከመፈጸሙ በፊት የነዚህን ዋሌቶች መጠባበቂያ ቅጂ ይይዛል።ይህ መጠባበቂያ ቅጂ 1-2 legacy.bak ተብሎ ተሰይሞ በዋሌቱ ማውጫ ውስጥ ይገኛል።የተሳሳተ ዝውውር በሚከሰትበት ጊዜየመጠባበቂያ ቅጂው በ ዋሌት መመለሻ መተግበሪያ ውስጥ ይከማቻል።</translation>
    
YES
The translation has several issues:
- There are spacing issues, such as missing spaces after periods and commas, and some unnecessary spaces before punctuation marks.
- The backup file name in the translation ("1-2 legacy.bak") does not accurately reflect the format in the source ("<wallet name>-<timestamp>.legacy.bak").
- The sentence structure in places is hard to understand and could confuse users (e.g., "ሊፈቱ የሚችሉ ነገር ግን የመመልከት ብቻ ያልሆኑ ስክሪፕቶችን").
- Terms such as "restore" and "backup" could be better localized.
- General clarity and accuracy could be improved for technical users.

Corrected translation:
<translation>ዋሌትን ማዛወር ይህን ዋሌት ወደ አንድ ወይም ከአንዱ በላይ የገላጭ ዋሌቶች ይለውጣል። አዲስ ዋሌት ቅፅ ማዘጋጀት ያስፈልጋል። ይህ ዋሌት ብቻ እንዲታዩ የተባሉ ስክሪፕቶችን ካሳየ፣ እነዚህን የመመልከት ብቻ የሆኑ ስክሪፕቶች የያዘ አዲስ ዋሌት ይፈጠራል። ይህ ዋሌት በሚፈቱ ነገር ግን የመመልከት ብቻ ያልሆኑ ስክሪፕቶችን ካሳየ፣ እነዚህን የያዘ በተለየ አዲስ ዋሌት ይፈጠራል። የማዛወር ሂደት ከመጀመሩ በፊት የዋሌቱን ቅርጸ መቆጣጠሪያ ይፈጥራል። ይህ የሚገኙት ማያውቅ መቅረጽ &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak የተባለ ስም ያለው በዚህ ዋሌት መያዣ አድራሻ ውስጥ ይገኛል። በሚያሳውቅ ተሳሳት የዘውውር ሂደት ሲከሰት ቅብራ መመዝገቢያውን በ "ዋሌት መመለሻ" ተግባር ማመልከት ይችላሉ።</translation>
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>የመመልከት ብቻ ስክሪፕቶች'%1'.ወደ ተሰኘው ዋሌት ተዛውረዋል </translation>
    
YES
There are spacing and punctuation format issues in the translation. There should be a space before and after '%1'. The Amharic translation also has minor awkward phrasing; it would be clearer and more natural to phrase it as "የመመልከት ብቻ ስክሪፕቶች ወደ '%1' ተብሎ የተሰኘው አዲስ ዋሌት ተዛውረዋል።"

Correct translation:
የመመልከት ብቻ ስክሪፕቶች ወደ '%1' ተብሎ የተሰኘው አዲስ ዋሌት ተዛውረዋል።
```

```
        <source>Welcome to %1.</source>
        <translation>እንኳን  ወድ %1 በደህና መጣህ።</translation>
    
YES
There are formatting issues in the translation: there are double spaces after "እንኳን" and around "%1". The correct Amharic greeting does not require these extra spaces.

Correct translation:
እንኳን ወደ %1 በደህና መጣህ።
```

```
        <source>About %1</source>
        <translation>ስለ እኛ %1</translation>
    
YES
The translation "ስለ እኛ %1" means "About us %1", which changes the meaning of the original English text. The correct translation for "About %1" (where %1 is likely a program or application's name) should be:

Correct translation:
ስለ %1
```

```
        <source>Form</source>
        <translation>ከ</translation>
    
YES
The translation is incorrect. "Form" in English (referring to a form or document, not "from") should be translated as "ቅፅ" or "ቅጽ" in Amharic. The given translation "ከ" means "from" (a preposition), which is completely incorrect in this context.

Correct translation:
<translation>ቅጽ</translation>
```

```
        <source>Form</source>
        <translation>ከ</translation>
    
YES
The translation is incorrect. "Form" in English (referring to a form or document, not "from") should be translated as "ቅፅ" or "ቅጽ" in Amharic. The given translation "ከ" means "from" (a preposition), which is completely incorrect in this context.

Correct translation:
<translation>ቅጽ</translation>
```

```
        <source>Copy fee</source>
        <translation>ክፍያው ቅዳ</translation>
    
YES
The translation "ክፍያው ቅዳ" is problematic. "Copy fee" should refer to copying (i.e., transferring to clipboard) the fee value, not an instruction to "cut" or "remove" the fee. "ቅዳ" more closely translates to "cut" rather than "copy." The correct translation should be:

Correct translation:
"ክፍያውን ቅዳ" should be replaced with "ክፍያውን ቅዳል" or "ክፍያውን ቅዳ" if "copy" is meant as an instruction. However, the correct word for "copy" in Amharic is "ገልብጥ" or "ቅዳው".

Best translation:
ክፍያውን ገልብጥ
```

```
        <source>%1 from wallet '%2'</source>
        <translation>%1 ከዋሌት %2'</translation>
    
YES
The translation is missing the opening single quote before "%2", resulting in a format inconsistency. The English source has single quotes around %2 ('%2'), but the Amharic translation only has the closing quote. It should also more clearly indicate "from wallet" in Amharic.

Correct translation:
%1 ከዋሌት '%2'
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>በንዑስ ሰረዝ የተለዩ ፋይሎች</translation>
    
YES
The Amharic translation "በንዑስ ሰረዝ የተለዩ ፋይሎች" literally means "Files that are separated by comma," which is understandable. However, the English source refers to the file format (i.e., "Comma separated file" or ideally "Comma-separated values file"), not the files themselves.

A more accurate and idiomatic translation that is used for CSV (Comma-separated values) files in Amharic is:
በንዑስ ሰረዝ የተለየ ፋይል

So, the correct translation should be:
በንዑስ ሰረዝ የተለየ ፋይል
```

```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>ከክፍያ-ነፃ PSBT ወደ ቅንጥብ ሰሌዳ ተቀድቷል።</translation>
    
YES
The translation "ከክፍያ-ነፃ PSBT ወደ ቅንጥብ ሰሌዳ ተቀድቷል።" translates back to "Fee-free PSBT copied to clipboard". This is incorrect, as "fee-bump" refers to increasing the transaction fee, not making it "fee-free."

Correct translation:
የክፍያ ጨምሮ የተሰራው PSBT ወደ ቅንጥብ ሰሌዳ ተገልቧል።

This ensures accuracy in the Bitcoin context.
```
</details>
