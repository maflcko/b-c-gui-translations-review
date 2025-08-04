# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>am</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bam%5D%20low%20quality)


```
        <source>Delete the currently selected address from the list</source>
        <translation>አሁን የተመረጠውን አድራሻ ከዝርዝሩ ውስጥ ያጥፉ</translation>
    
YES - The word "ያጥፉ" which means "destroy" or "demolish" is too strong and inappropriate for deleting an address. A more suitable word would be "ያስወግዱ" which means "remove".

Correct translation: አሁን የተመረጠውን አድራሻ ከዝርዝሩ ውስጥ ያስወግዱ
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>በዚህ ማውጫ ውስጥ ያለውን ውሂብ ወደ ፋይል አዛውረው ያስቀምጡ</translation>
    
UNK_LANG
```

```
        <source>Choose the address to send coins to</source>
        <translation>ገንዘብ/ኮይኖችን የሚልኩበትን አድራሻ ይምረጡ</translation>
    
YES - The translation is problematic because it uses two different scripts, Amharic and Ge'ez, which are not compatible and would not render correctly together. The word "coins" is translated using an English word within the Amharic script.

Correct translation: ገንዘብ የሚልኩበትን አድራሻ ይምረጡ
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>በንዑስ ሰረዝ የተለዩ ፋይሎች</translation>
    
YES
The translation of "Comma separated file" to "በንዑስ ሰረዝ የተለዩ ፋይሎች" is inaccurate. The Amharic word for comma is "ኮማ" (koma), not "ንዑስ ሰረዝ" (n'us serz), which translates to "sub-dash" or "hyphen".

Correct translation: በኮማ የተለዩ ፋይሎች
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>የአድራሻ ዝርዝሩን ወደ %1 ለማስቀመጥ ሲሞከር ስህተት አጋጥሟል:: እባክዎ መልሰው ይሞክሩ::</translation>
    
YES: The translation uses two colons (::) at the end of sentences instead of one.
The correct translation is: የአድራሻ ዝርዝሩን ወደ %1 ለማስቀመጥ ሲሞከር ስህተት አጋጥሟል:: እባክዎ መልሰው ይሞክሩ.
```

```
        <source>Receiving addresses - %1</source>
        <translation>አድራሻዎችን በማቀበል ላይ - %1</translation>
    
YES, the translation is problematic as it incorrectly translates "Receiving addresses" to "አድራሻዎችን በማቀበል ላይ" which means "Receiving addresses" or "Receiving the addresses". The correct translation for "Receiving addresses" in Amharic, in the context of Bitcoin, would be "የሚቀበሉ አድራሻዎች".

The translation also has a whitespace issue as there is an extra space before the hyphen.

Correct translation: የሚቀበሉ አድራሻዎች - %1
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>ይህ ክንዋኔ የቢትኮይን ቦርሳዎን ለመክፈት የቦርሳዎ ይለፍ-ሐረግ ያስፈልገዋል::</translation>
    
YES - The translation incorrectly uses the term "ቢትኮይን ቦርሳዎ" (Bitcoin wallet of yours) twice. It should simply refer to "your wallet" or "your Bitcoin wallet". Additionally, there is an unnecessary double colon at the end.

Correct translation: ይህ ክንዋኔ የኪስ ቦርሳዎን ለመክፈት የይለፍ-ቃል ያስፈልገዎታል።
```

```
        <source>Confirm wallet encryption</source>
        <translation>የቢትኮይን ቦርሳዎን ማመስጠር ያረጋግጡ</translation>
    
YES, the translation is problematic because it uses a literal translation of "confirm wallet encryption" without considering the Bitcoin context. In Bitcoin, "wallet encryption" refers to the passphrase protecting the private keys within a wallet, not the process of encrypting the wallet itself. The Amharic translation can be misunderstood as confirming the encryption of the wallet's contents rather than the passphrase.

The correct translation should focus on confirming the wallet's passphrase for security.

NO, the translation is problematic. The Amharic translation literally translates "confirm wallet encryption," which might not accurately convey the intended meaning in the context of Bitcoin. In Bitcoin, "wallet encryption" usually refers to setting or confirming a passphrase that protects the wallet's private keys, rather than encrypting the wallet's data itself. A more appropriate translation would focus on confirming the passphrase.

Correct translation: የኪስዎን የይለፍ ቃል ያረጋግጡ (Yekiswoyn yilef k'al yareggach'u) - This translates to "Confirm your wallet's password/passphrase."
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>ማስጠንቀቂያ: የቢትኮይን ቦርሳዎን አመስጥረው የይለፍ-ሐረግዎን ካጡት&lt;b&gt;ቢትኮይኖቾን በሙሉ ያጣሉ&lt;/b&gt;!</translation>
    
YES: The translation incorrectly uses "ቢትኮይኖቾን" which seems to be a made-up word. It should be "ቢትኮይኖችዎን" (your Bitcoins). Additionally, the spacing between "ያጣሉ" and the exclamation mark is incorrect.

Correct translation: ማስጠንቀቂያ: የቢትኮይን ቦርሳዎን አመስጥረው የይለፍ-ሐረግዎን ካጡት&lt;b&gt;ቢትኮይኖችዎን በሙሉ ያጣሉ&lt;/b&gt;!
```

```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>አስፈላጊ: ከ ቦርሳ ፋይልዎ ያከናወኗቸው ቀደም ያሉ ምትኬዎች በአዲስ በተፈጠረ የማመስጠሪያ ፋይል ውስጥ መተካት አለባቸው. ለደህንነት ሲባል, አዲሱን የተመሰጠ የቦርሳ ፋይል መጠቀም ሲጀመሩ ወዲያውኑ ቀደም ሲል ያልተመሰጠሩ የቦርሳ ፋይል ቅጂዎች ዋጋ ቢስ ይሆናሉ::</translation>
    
YES: The translation uses "ቀደም ያሉ ምትኬዎች" which means "previous backups" and "የማመስጠሪያ ፋይል" which means "encryption file". The source text says "encrypted wallet file". The word "wallet" is not translated in the translation. The correct translation for "wallet" is "ቦርሳ". Therefore, the translation should be "አስፈላጊ: ከ ቦርሳዎ ያከናወኗቸው ቀደም ያሉ ምትኬዎች በአዲስ በተፈጠረ የቦርሳ ምትኬ መተካት አለባቸው. ለደህንነት ሲባል, አዲሱን የተመሰጠ የቦርሳ ፋይል መጠቀም ሲጀመሩ ወዲያውኑ ቀደም ሲል ያልተመሰጠሩ የቦርሳ ፋይል ቅጂዎች ዋጋ ቢስ ይሆናሉ::"
```

```
        <source>Wallet encryption failed</source>
        <translation>የቦርሳ ማመስጠር አልተሳካም</translation>
    
YES
The translation uses the word "ማመስጠር" which means "encryption". While the translation is not technically incorrect, the word "ማመስጠር" is not commonly used in modern Amharic. A more commonly used and natural-sounding word for encryption in Amharic is "መመስጠር".

Correct translation: የኪስ ማመስጠር አልተሳካም
```

```
        <source>Wallet encryption failed due to an internal error. Your wallet was not encrypted.</source>
        <translation>የቦርሳ ማመስጠር በውስጣዊ ስህተት ምክንያት አልተሳካም:: ቦርሳዎ አልተመሰጠረም::</translation>
    
YES - The translation uses double colons (::) which is not standard punctuation in Amharic. The correct translation should use a single colon.

Correct translation: የቦርሳ ማመስጠር በውስጣዊ ስህተት ምክንያት አልተሳካም:: ቦርሳዎ አልተመሰጠረም::
```

```
        <source>The supplied passphrases do not match.</source>
        <translation>የተሰጡት የይለፍ-ሐረግዎች አይዛመዱም::</translation>
    
YES
The translation uses an unnecessary colon at the end and also has extra spacing around the hyphens.
The supplied passphrases do not match.
የተሰጡት የይለፍ-ሐረግዎች አይዛመዱም።
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>ቦርሳ ለመፍታት ያስገቡት የይለፍ-ሐረግ ትክክል አልነበረም::</translation>
    
YES: The translation uses the Amharic letter "::" at the end, which is not standard for Amharic punctuation. The correct punctuation is usually a single period or no punctuation at all in this context.

Corrected translation: ቦርሳ ለመፍታት ያስገቡት የይለፍ-ሐረግ ትክክል አልነበረም።
```

```
        <source>IP/Netmask</source>
        <translation>አይፒ/ኔትማስክ  IP/Netmask</translation>
    
YES
The translation includes the original English text "IP/Netmask" appended to the Amharic translation. This is unnecessary and suggests the translation might have been generated by a system that doesn't fully understand the context or purpose.

Correct translation:
አይፒ/ኔትማስክ
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>ውስጣዊ ችግር ተፈጥሯል።  %1 ደህንነቱን ጠብቆ ለመቀጠል ይሞክራል። ይህ ችግር ያልተጠበቀ ሲሆን ከታች በተገለፀው መሰረት ችግሩን ማመልከት ይቻላል። </translation>
    
YES: The translation is in Amharic, not 'am'. The translation is mostly accurate but uses informal language for "error occurred".

Correct translation in Amharic:
ውስጣዊ ስህተት ተከስቷል። %1 በደህንነቱ ለመቀጠል ይሞክራል። ይህ ያልተጠበቀ ሳንካ ሲሆን ከታች እንደተገለጸው ሪፖርት ሊደረግ ይችላል።
```

```
        <source>Do you want to reset settings to default values, or to abort without making changes?</source>
        <extracomment>Explanatory text shown on startup when the settings file cannot be read. Prompts user to make a choice between resetting or aborting.</extracomment>
        <translation>ቅንብሩን መጀመሪያ ወደነበረው ነባሪ ዋጋ መመለስ ይፈልጋሉ? ወይስ ምንም አይነት ለውጥ ሳያደርጉ እንዲከሽፍ ይፈልጋሉ?</translation>
    
YES, The translation uses informal language which is not appropriate for technical context, and the phrasing is awkward.
<source>Do you want to reset settings to default values, or to abort without making changes?</source>
<translation>ቅንብሩን ነባሪ ዋጋዎች ላይ ዳግም ማስጀመር ይፈልጋሉ፣ ወይስ ምንም ለውጥ ሳያደርጉ መሰረዝ ይፈልጋሉ?</translation>
```

```
        <source>Default system font "%1"</source>
        <translation>ነባሪ የስርዓት ቅርጸ-ቁምፊ "%1</translation>
    
YES, The closing quotation mark for the string is missing.
The correct translation is: ነባሪ የስርዓት ቅርጸ-ቁምፊ "%1"
```

```
        <source>Error creating wallet</source>
        <translation>ዋሌትዎን ለፍጠር ተሳስተዋል </translation>
    
YES, The translation is problematic because it implies the user made a mistake in creating the wallet, whereas the original text is a system error message.
Correct translation: ዋሌት ለመፍጠር አልተቻለም (It was not possible to create the wallet)
```

```
        <source>Copy fee</source>
        <translation>ክፍያው ቅዳ</translation>
    
YES - The translation is incorrect and does not convey the meaning of "Copy fee". The correct translation should be "ክፍያውን ቅዳ" or "ክፍያን ቅዳ" depending on the context.
YES - The translation is incorrect and does not convey the meaning of "Copy fee". The correct translation should be "ክፍያውን ቅዳ" or "ክፍያን ቅዳ" depending on the context.
```

```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>ዋሌትን ማዛወር ይህንን ዋሌት አንድ ወይም ከዚያ በላይ ወደሆነ ገላጭ ዋሌቶች ይቀይረዋል።አዲስ ዋሌት ማዘጋጀት ያስፈልጋል ።ይህ ዋሌት ምንም ዓይነት የመመልከት ብቻ ስክሪፕቶችን የያዘ ከሆነ፣እነዚያን የመመልከት ብቻ ስክሪፕቶችን የያዘ አዲስ ዋሌት ይፈጠራል።ይህ ዋሌት ሊፈቱ የሚችሉ ነገር ግን የመመልከት ብቻ ያልሆኑ ስክሪፕቶችን የያዘ ከሆነ ፣ እነዚህን የያዘ አዲስ እና ልዩ የሆነ ዋሌት ይፈጠራል ።የማዛወር ሂደቱ ማዘዋወር ከመፈጸሙ በፊት የነዚህን ዋሌቶች መጠባበቂያ ቅጂ ይይዛል።ይህ መጠባበቂያ ቅጂ 1-2 legacy.bak ተብሎ ተሰይሞ በዋሌቱ ማውጫ ውስጥ ይገኛል።የተሳሳተ ዝውውር በሚከሰትበት ጊዜየመጠባበቂያ ቅጂው በ ዋሌት መመለሻ መተግበሪያ ውስጥ ይከማቻል።</translation>
    
YES - The phrase "1-2 legacy.bak" seems to be a mistranslation of "<wallet name>-<timestamp>.legacy.bak". The intended meaning is that the backup file name includes the wallet's name and a timestamp, not the literal string "1-2".

Correct translation:
"ዋሌትን ማዛወር ይህንን ዋሌት አንድ ወይም ከዚያ በላይ ወደሆነ ገላጭ ዋሌቶች ይቀይረዋል።አዲስ ዋሌት ማዘጋጀት ያስፈልጋል ።ይህ ዋሌት ምንም ዓይነት የመመልከት ብቻ ስክሪፕቶችን የያዘ ከሆነ፣እነዚያን የመመልከት ብቻ ስክሪፕቶችን የያዘ አዲስ ዋሌት ይፈጠራል።ይህ ዋሌት ሊፈቱ የሚችሉ ነገር ግን የመመልከት ብቻ ያልሆኑ ስክሪፕቶችን የያዘ ከሆነ ፣ እነዚህን የያዘ አዲስ እና ልዩ የሆነ ዋሌት ይፈጠራል ።የማዛወር ሂደቱ ማዘዋወር ከመፈጸሙ በፊት የነዚህን ዋሌቶች መጠባበቂያ ቅጂ ይይዛል።ይህ መጠባበቂያ ቅጂ <wallet name>-<timestamp>.legacy.bak ተብሎ ተሰይሞ በዋሌቱ ማውጫ ውስጥ ይገኛል።የተሳሳተ ዝውውር በሚከሰትበት ጊዜየመጠባበቂያ ቅጂው በ ዋሌት መመለሻ መተግበሪያ ውስጥ ይከማቻል።"
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>የመመልከት ብቻ ስክሪፕቶች'%1'.ወደ ተሰኘው ዋሌት ተዛውረዋል </translation>
    
YES - The translation is problematic due to grammatical errors and word order. The word order is unnatural, and the placement of '%1' is incorrect.

Correct translation: "የመመልከት ብቻ ስክሪፕቶች ወደ '%1' በተሰየመ አዲስ ዋሌት ተዛውረዋል።"
```

```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>ሊፈቱ የሚችሉ ነገር ግን የማይታዩ ስክሪፕቶች ወደ አዲስ ዋሌት ተዛውረዋል '%1'።</translation>
    
YES: The translation has a grammatical error. The possessive particle should follow the noun it modifies.
Correct translation: ሊፈቱ የሚችሉ ነገር ግን የማይታዩ ስክሪፕቶች በ '%1' ስም ወደ አዲስ ዋሌት ተዛውረዋል።
```

```
        <source>Migration failed</source>
        <translation>ዝውውሩ አልተሳካም </translation>
    
YES, The translation contains an unnecessary space at the end of the sentence.
ዝውውሩ አልተሳካም
```

```
        <source>Welcome to %1.</source>
        <translation>እንኳን  ወድ %1 በደህና መጣህ።</translation>
    
YES. The translation is problematic as it contains an extraneous space between "እንኳን" and "ወድ". Additionally, the word "ወድ" is not a standard Amharic word for "Welcome to". The correct translation should be "እንኳን ወደ %1 በደህና መጣህ።".

NO
```

```
        <source>About %1</source>
        <translation>ስለ እኛ %1</translation>
    
YES, the translation is problematic. The Ethiopian Amharic word "እኛ" (eñña) means "us" or "we", not "about". The correct translation for "about" would be "ስለ" (sile). Therefore, "About %1" should be translated as "ስለ %1".

YES, ስለ %1
```

```
        <source>Form</source>
        <translation>ከ</translation>
    
YES
The translation is incorrect and nonsensical in the context of Bitcoin. The Amharic word "ከ" (ke) means "from" or "than" and does not translate to "Form". A more appropriate translation for "Form" in this context would be "ቅጽ" (q'is) or "መልክ" (malk).

Here's the corrected translation:

YES
The translation is incorrect and nonsensical.
Correct translation: ቅጽ
```

```
        <source>Form</source>
        <translation>ከ</translation>
    
YES
The translation is incorrect and nonsensical in the context of Bitcoin. The Amharic word "ከ" (ke) means "from" or "than" and does not translate to "Form". A more appropriate translation for "Form" in this context would be "ቅጽ" (q'is) or "መልክ" (malk).

Here's the corrected translation:

YES
The translation is incorrect and nonsensical.
Correct translation: ቅጽ
```

```
        <source>Copy fee</source>
        <translation>ክፍያው ቅዳ</translation>
    
YES - The translation is incorrect and does not convey the meaning of "Copy fee". The correct translation should be "ክፍያውን ቅዳ" or "ክፍያን ቅዳ" depending on the context.
YES - The translation is incorrect and does not convey the meaning of "Copy fee". The correct translation should be "ክፍያውን ቅዳ" or "ክፍያን ቅዳ" depending on the context.
```

```
        <source>%1 from wallet '%2'</source>
        <translation>%1 ከዋሌት %2'</translation>
    
YES, The translation is problematic because the word "wallet" was not translated. The correct translation should be: %1 ከ'%2' መክሰፊያ
```

```
        <source>The entered address does not refer to a legacy (P2PKH) key. Message signing for SegWit and other non-P2PKH address types is not supported in this version of %1. Please check the address and try again.</source>
        <translation>የገባው አድራሻ የቅርስ (P2PKH) ቁልፍን አያመለክትም። ለሴግዊት እና ሌሎች P2PKH ላልሆኑ የአድራሻ አይነቶች የመልዕክት መፈረም በዚህ የ%1 ስሪት ውስጥ አይደገፍም። እባክዎ አድራሻውን ያረጋግጡ እና እንደገና ይሞክሩ።</translation>
    
YES: The translation contains an English word "P2PKH" which should have been translated into Amharic.

The entered address does not refer to a legacy (P2PKH) key. Message signing for SegWit and other non-P2PKH address types is not supported in this version of %1. Please check the address and try again.
የገባው አድራሻ የቅርስ (P2PKH) ቁልፍን አያመለክትም። ለሴግዊት እና ሌሎች P2PKH ላልሆኑ የአድራሻ አይነቶች የመልዕክት መፈረም በዚህ የ%1 ስሪት ውስጥ አይደገፍም። እባክዎ አድራሻውን ያረጋግጡ እና እንደገና ይሞክሩ።
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>በንዑስ ሰረዝ የተለዩ ፋይሎች</translation>
    
YES
The translation of "Comma separated file" to "በንዑስ ሰረዝ የተለዩ ፋይሎች" is inaccurate. The Amharic word for comma is "ኮማ" (koma), not "ንዑስ ሰረዝ" (n'us serz), which translates to "sub-dash" or "hyphen".

Correct translation: በኮማ የተለዩ ፋይሎች
```

```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>ከክፍያ-ነፃ PSBT ወደ ቅንጥብ ሰሌዳ ተቀድቷል።</translation>
    
YES - The translation uses "ከክፍያ-ነፃ" which means "fee-free" or "free of charge". The English source text "Fee-bump" implies an increase in the fee, not a reduction or absence of a fee. The literal translation of "fee-bump" is closer to "የክፍያ መጨመር" or "የክፍያ ጭማሪ".

Correct translation: የክፍያ ጭማሪ PSBT ወደ ቅንጥብ ሰሌዳ ተቀድቷል።
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>በዚህ ማውጫ ውስጥ ያለውን ውሂብ ወደ ፋይል አዛውረው ያስቀምጡ</translation>
    
UNK_LANG
```
</details>
