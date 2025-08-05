# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>yi</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Byi%5D%20low%20quality)


```
        <source>Create a new address</source>
        <translation>רעכט-קנעפּל דריקט צו רעדאַקטירן אַדרעס אָדער לייבל</translation>
    
YES  
The translation does not accurately represent the source text "Create a new address." Instead, it reads as "Right-click button clicks to edit address or label," which is unrelated and potentially confusing.  

Correct translation:  
א נײַע אַדרעס שאַפֿן
```

```
        <source>Delete</source>
        <translation> אַרויסמאַכן</translation>
    
YES  
The translation contains a leading whitespace before the word, which is a formatting issue. Also, the Yiddish word for "Delete" is more appropriately "אויסמעקן" without the leading space.

Correct translation:  
<translation>אויסמעקן</translation>
```

```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>די זענען אייער ביטקאָין־אַדרעסן פֿאַר באקומען צאָלונגען. ניצט דעם קנעפּל „שאַפֿן אַ נײַע באקומען־אַדרעס“ 
אין די „באקומען“־טעב, צו שאַפֿן נײַעאַדרעסן.אונterschרייבן איז בלויז מעגלעך מיט אַדרעסן פון דעם טיפּ „לעגאַסי“.</translation>
    
YES
The translation contains punctuation and spacing issues: 
- There should be a space after the period in "נײַעאַדרעסן.אונterschרייבן".
- The word "אונterschרייבן" is a German Yiddish loanword, but in standard Yiddish the correct term for "Signing" would be closer to "אונטערשרײַבן".
- Also, the phrase " unusig" (use) should be consistent with the second sentence, and the quotes should be consistent (either use „ “ or ‘ ’).

Correct translation:
די זענען אייער ביטקאָין־אַדרעסן פֿאַר באַקומען צאָלונגען. ניצט דעם קנעפּל „שאַפֿן אַ נײַע באַקומען־אַדרעס“ אין די „באַקומען“־טעב, צו שאַפֿן נײַע אַדרעסן. אונטערשרײַבן איז בלויז מעגלעך מיט אַדרעסן פֿון דעם טיפּ „לעגאַסי“.
```

```
        <source>Exporting Failed</source>
        <translation>אכסניות פֿעלד</translation>
    
YES
The translation "אכסניות פֿעלד" means "hostels field" or "inns field," which is incorrect and inappropriate as a translation for "Exporting Failed." A correct Yiddish translation would be "עקספּאָרטירן געפֿעלט" or "אויספירן איז איינגעקומען" depending on context. The most straightforward and accurate translation is:

עקספּאָרטירן איז פארפאלן
```

```
        <source>Encrypt wallet</source>
        <translation>ארויפשטעלן וואַלטל</translation>
    
YES  
The translation "ארויפשטעלן וואַלטל" means "install wallet" or "set up wallet," which is incorrect for "Encrypt wallet." The term for "encrypt" in Yiddish should be closer to "פֿאַרקריפטן" (farkript'n) or "פֿאַרפּעסטיקן" (farpestikn), though "פֿאַרקריפטן" is more appropriate. Also, "wallet" should be translated as "וואַלט" or "קאָשעלע."

Correct translation:  
פֿאַרקריפטן וואַלט
```

```
        <source>Confirm wallet encryption</source>
        <translation>אָפּלייקענען וואָלעט ענקריפּשאַן</translation>
    
YES  
The translation "אָפּלייקענען וואָלעט ענקריפּשאַן" is incorrect and misleading. It literally reads "Apply wallet encryption" rather than "Confirm wallet encryption." The English source asks for confirmation, so the translation should reflect the meaning of "confirm" (as in "verify" or "affirm"), not "apply."

A more accurate translation would be:  
"קאָנפירמירן וואָלעט ענקריפּשאַן"  
(using a transliteration of the English "confirm" as there might not be a direct Yiddish equivalent in the context of technical Bitcoin terms, or alternatively:  
"באַשטעטיקן וואָלעט ענקריפּשאַן").
```

```
        <source>Wallet encrypted</source>
        <translation>בייַטל ינקריפּטיד</translation>
    
YES
The translation is written in Latin characters using English phonetics ("בייַטל ינקריפּטיד") instead of proper Yiddish script and vocabulary. In Yiddish, "Wallet encrypted" should be properly translated as:

    וואָלט אַל דערהאַלטן (wallet) געשעערט

Or more literally reflecting "Wallet encrypted":

    פּאַרזל געשעערט

However, the word "wallet" is often transliterated but should be in Yiddish script and the verb for "encrypted" should be accurate.

A better, clearer translation in Yiddish script is:

    פּאַרזל פאַרקריפּטירט

So the correct translation is:

    פּאַרזל פאַרקריפּטירט
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>אַרייַן דעם נייעם פּאַספראַזע פֿאַר דער געלט-פּאָמעלע.&lt;br/&gt;ביטע ניצן אַ פּאַספראַזע פון &lt;b&gt;צען אָדער מער אומגעפֿערלעכע אותיות &lt;/b&gt;, אָדער &lt;b&gt; אַכט אָדער מער ווערטער&lt;/b&gt;.</translation>
    
YES
There is an extra space before the closing </b> tag in the first formatted phrase ("... אותיות &lt;/b&gt;" should be "... אותיות&lt;/b&gt;") and before the second opening <b> tag ("&lt;b&gt; אַכט..." should be "&lt;b&gt;אַכט..."). Also, the phrase "אומגעפֿערלעכע אותיות" ("approximate letters") is inaccurate; the original English means "random characters." A better translation for "random characters" would be "צופֿעליקער אותיות" or "צופֿעליק אותיות." 

Correct translation:
אַרייַן דעם נייעם פּאַספֿראַזע פֿאַר דער געלט-פּאָמעלע.&lt;br/&gt;ביטע ניצן אַ פּאַספֿראַזע פֿון &lt;b&gt;צען אָדער מער צופֿעליקע אותיות&lt;/b&gt;, אָדער &lt;b&gt;אַכט אָדער מער וואָרטער&lt;/b&gt;.
```

```
        <source>Wallet encryption failed</source>
        <translation>בייטל ענקריפּשאַן ניט אַנדערש</translation>
    
YES  
The translation is incorrect. The phrase "Wallet encryption failed" should convey that the action of encrypting the wallet was unsuccessful. The provided translation "בייטל ענקריפּשאַן ניט אַנדערש" translates roughly to "Wallet encryption not different," which is nonsensical in this context.  
A correct Yiddish translation would be:  
"ואָלט ענקריפּשאַן אויף אַן ערראָר" or more simply:  
"ואָלט ענקריפּשאַן נישט צוגעקומען"  
but a more standard and clear phrase is:  
"ואָלט ענקריפּשאַן געפיילערט" (Wallet encryption failed).  

Correct translation:  
"ואָלט ענקריפּשאַן געפיילערט"
```

```
        <source>Wallet unlock failed</source>
        <translation>אַנלאַקינג די בייַטל איז ניט אַנדערש</translation>
    
YES
The translation "אַנלאַקינג די בייַטל איז ניט אַנדערש" is incorrect and does not convey "Wallet unlock failed." It roughly translates to "Unlocking the wallet is not different," which is not appropriate.

A correct translation would be:
"ווײַלעט גלאָז מאַכן איז בנאָטיז געווען"  
or more literally,  
"ווײַלעט אויפמעקן נאכגעקוקט" (meaning "Wallet unlocking failed").  

Since Yiddish often borrows words for technical terms, a straightforward, clear phrase like "וואַלעט אויפמעקן איז פּאָגדאָרפֿן" or "וואַלעט אויפמעקן האָט פֿעלער געמאכט" might be better.  

Suggested corrected translation:  
"וואָקלעט אויפמעקן האָט ניט געקענט"
```

```
        <source>IP/Netmask</source>
        <translation>IP / נעטמאַסק</translation>
    
YES
There is an incorrect whitespace around the slash. The source has "IP/Netmask" without spaces. The translation has an extra space before and after the slash "IP / נעטמאַסק", which is inconsistent formatting.

Correct translation:
IP/נעטמאַסק
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>סעטטינגס טעקע %1  קען זיין פאַרדאָרבןאָדער פאַרקריפּלט.</translation>
    
YES
The translation has spacing issues and combines two alternative words without spacing or proper conjunction: "פאַרדאָרבןאָדער" should be split or connected with a space or a word equivalent to "or". Also, "Settings" is transliterated to "סעטטינגס" which is acceptable as a loanword, but the phrase could be more natural.

A corrected version could be:
סעטטינגס טעקע %1 קען זיין פאַרדאָרבן אָדער פאַרקריפּלט.
```

```
        <source>Runaway exception</source>
        <translation>ראַנאַוויי ויסנעם</translation>
    
YES
The transliteration "ראַנאַוויי ויסנעם" is a phonetic rendering of the English phrase and does not convey the meaning in Yiddish. A proper Yiddish translation for "Runaway exception" in a programming or technical context would be:

            "ויסנעם אָנליין" 

or more literally,

            "ויסנעם וואָס לויפט אָן" 

depending on context. The provided translation looks like a direct phonetic borrowing, which is not appropriate.
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>א אינערלעכער טעות איז פארגעקומען.  %1וועט פּרווון צו פאָרזעצן בעשאָלעם. דאָס איז אַן אומגעריכט זשוק וואָס קענען זיין רעפּאָרטעד ווי דיסקרייבד אונטן.</translation>
    
YES  
The translation has issues with spacing (missing space after the period before "%1") and uses anglicized words ("רעפּאָרטעד", "דיסקרייבד") instead of proper Yiddish equivalents. The phrase "This is an unexpected bug which can be reported as described below." is translated partially with English loanwords that are not standard in Yiddish.

Corrected translation:  
"א אינערלעכער טעות איז פארגעקומען. %1 וועט פּרוּוון צו פאָרזעצן בעשאָלעם. דאָס איז אַן אומגעריכטן פילער וואָס קען געשיקט זיין ווי ווייטער אונטן באַשריבן."
```

```
        <source>Do you want to reset settings to default values, or to abort without making changes?</source>
        <extracomment>Explanatory text shown on startup when the settings file cannot be read. Prompts user to make a choice between resetting or aborting.</extracomment>
        <translation>צי איר ווילן צו באַשטעטיק סעטטינגס צו פעליקייַט וואַלועס אָדער אַבאָרט אָן ענדערונגען?</translation>
    
YES
The translation is problematic because it mixes English words ("סעטטינגס", "פעליקייַט", "וואַלועס", "אָבאָרט") transliterated into Yiddish characters rather than using proper Yiddish equivalents. This is unnatural and incorrect in a proper Yiddish translation.

Correct translation:
צי ווילט איר באַזעצן די אַיציערדיקע שעטינגען צו די פאָרגעשטעקטע ווערטן, אָדער אָפּחאָלן אָן צו טאָן ענדערונגען?
```

```
        <source>Exit</source>
        <translation>עxit</translation>
    
YES  
The translation incorrectly mixes Yiddish script ("ע") with Latin letters ("xit"). The whole word should be fully transliterated or fully in Yiddish script. In Yiddish, "Exit" is typically translated as "אויסגאַנג" (oys-gang) or a transliteration fully in Yiddish letters. Mixing scripts is erroneous.

Correct translation:  
אויסגאַנג
```

```
        <source>Exporting Failed</source>
        <translation>אכסניות פֿעלד</translation>
    
YES
The translation "אכסניות פֿעלד" means "hostels field" or "inns field," which is incorrect and inappropriate as a translation for "Exporting Failed." A correct Yiddish translation would be "עקספּאָרטירן געפֿעלט" or "אויספירן איז איינגעקומען" depending on context. The most straightforward and accurate translation is:

עקספּאָרטירן איז פארפאלן
```

```
        <source>Unrecognized descriptor found. Loading wallet %s

The wallet might had been created on a newer version.
Please try running the latest software version.
</source>
        <translation>אונטערגעריפענע דעזקריפּטאָר געפונען. לאודינג וואָלעט 1%s דער וואָלעט קען געווען געמאכט אויף אַן נײַער ווערסיע. ביטע פּרוּוון אראפקומען דעם לעצטן סאָפטווער ווערסיע.</translation>
    
YES  
The translation contains several issues:  
1. The format specifier `%s` is incorrectly placed as `1%s`. It should directly replace `%s` without any extra characters.  
2. The phrase "לאודינג וואָלעט" is a transliteration of "Loading wallet" instead of a proper translation. A better Yiddish phrase for "Loading wallet" would be "לאַדן וואָלעט".  
3. The original source text is split into multiple lines. The translation should preserve similar line breaks or at least punctuation to separate sentences.  
4. Minor grammar issue: "דאַרפֿט האָבן געשאַפֿן" (might have been created) would be better than "קען געווען געמאכט".

Correct translation:  
אונטערגעריפענער דעזקריפּטאָר געפֿונען.  
לאַדן וואָלעט %s  
דער וואָלעט קען האָבן געשאַפֿן אויף אַן נײַער ווערסיע.  
ביטע פּרוּוון לויפן די לעצטע סאָפטווער ווערסיע.
```

```
        <source>
Unable to cleanup failed migration</source>
        <translation>נישט אפשר צו רייניקן אויוולע געדריט</translation>
    
YES  
The translation contains a misspelling and does not accurately reflect the source meaning. The phrase "Unable to cleanup failed migration" should be translated to convey the inability to clean up after a failed migration. The given translation "נישט אפשר צו רייניקן אויוולע געדריט" contains a misspelling: "אויוולע" is incorrect and should be "פֿאַרא" or a term meaning "failed."

A better translation would be:  
נישט מעגלעך צו רייניקן אױף דער פֿעלן­der מיגראציע
```

```
        <source>A fatal internal error occurred, see debug.log for details: </source>
        <translation>אויבערלעכער אינערלעכער אסקאָרגעס איז אריינגעקומען, זוך די debug.log פאר דעטאלן:</translation>
    
YES  
The translation contains an unclear and somewhat incorrect rendering of "fatal internal error occurred." The phrase "אויבערלעכער אינערלעכער אסקאָרגעס איז אריינגעקומען" is awkward and not idiomatic Yiddish. Specifically, "אסקאָרגעס" is a transliteration of "errors" but doesn't conform well to Yiddish usage, and the overall expression is unnatural.  

A better translation would be:  
"א טויטלעך אינערלעך שיטה (אויפֿטרעטנדיקער) שװערער באַדראָונג, זעט אין debug.log פֿאַר דעטאַילן:"  

Or more simply:  
"א טויטלעכע אינערלעכע טעות איז פּאַסירט, זע בײַם debug.log פֿאַר דעטאַילן:"  

This conveys "A fatal internal error occurred, see debug.log for details:" clearly and naturally in Yiddish.
```

```
        <source>Assumeutxo data not found for the given blockhash '%s'.</source>
        <translation>עס איז נישט געפונען אראפגעגעבן דאטן פאר דעם געגעבן בלאָק-האשט '1%s'.</translation>
    
YES  
The translation adds an extraneous character '1' before the format specifier %s, which is incorrect. Also, the phrase "Assumeutxo data" should be translated accurately or at least transliterated if no proper Yiddish equivalent exists, but the given translation uses "אראפגעגעבן דאטן" meaning "downloaded data," which is not an exact match for "Assumeutxo data." A better approach is to transliterate or keep "Assumeutxo" and translate the rest properly without adding extra characters or changing the order of the format specifier.

Correct translation:  
עס איז נישט געפונען Assumeutxo דאטן פאר דעם געגעבן בלאָק-האַש '%s'.
```

```
        <source>Block verification was interrupted</source>
        <translation>די באַשטעטיקונג פון בלאָק איז פֿאַרעפֿנטיקט געוואָרן</translation>
    
YES  
The translation is incorrect. The English phrase means "Block verification was interrupted," indicating the process was stopped or disrupted. However, the given Yiddish translation says "די באַשטעטיקונג פון בלאָק איז פֿאַרעפֿנטיקט געוואָרן," which means "The verification of the block was published," which is wrong and misleading.

Correct translation:  
די באַשטעטיקונג פון בלאָק איז אונטערבראָכן געווארן
```

```
        <source>Config setting for %s only applied on %s network when in [%s] section.</source>
        <translation>קאַנפיג אָטאַמאַטיש פֿאַר 1%s איז בלויז פֿאַראַנען אויף 1%s נעץ ווען אין [1%s] אָפּטייל.</translation>
    
YES  
The format specifiers (%s) in the original text are incorrectly modified to "1%s" in the translation, which is erroneous. They should remain exactly as "%s" without any added characters. Also, the translated phrase "אָטאַמאַטיש" means "automatically," which is not in the source text. The source talks about a "config setting," so the Hebrew/Yiddish equivalent of "config" or "configuration setting" is preferable. The rest of the sentence structure can be preserved as is.

Correct translation:  
קאָנפיגוראַציע סעטטינג פֿאַר %s ווערט בלויז געפֿינט אויף %s נעץ ווען אין [%s] אָפּטייל.
```

```
        <source>Copyright (C) %i-%i</source>
        <translation>קויפירייט (C) 1%i - 1%i</translation>
    
YES  
The translation incorrectly adds the digit "1" before the format specifiers %i, which is not present in the source and is erroneous. The format specifiers must be copied exactly as in the source without additional characters or spaces.

Correct translation:  
קויפירייט (C) %i-%i
```

```
        <source>Corrupt block found indicating potential hardware failure.</source>
        <translation>איבערשפיגלטע בלאָק געפֿונען וואָס דועט אויף אַ מעגלעך האַרדווער עמעצער</translation>
    
YES
The translation is incomplete and incorrect. The English sentence states: "Corrupt block found indicating potential hardware failure." The Yiddish translation ends abruptly with "אַ מעגלעך האַרדווער עמעצער" ("a possible hardware something"), which is incomplete and does not convey "failure." Also, "corrupt block" should be rendered clearly, and "indicating potential hardware failure" should be fully and properly translated.

Correct translation:
"געפֿונען קורופּירט בלאק וואָס ווייזט אויף מעגלעכע האַרדוואַר קראַש"
```

```
        <source>Corrupted block database detected</source>
        <translation>יָאָרע בלאק דאַטאַבאַסע געפונען</translation>
    
YES  
The translation is incorrect and incomplete. "Corrupted block database detected" means that a corrupted block database has been found or detected. The provided Yiddish translation "יָאָרע בלאק דאַטאַבאַסע געפונען" translates roughly to "found a block database," but it misses the meaning of "corrupted" and "detected" in the proper grammatical form. Also, "יָאָרע" is incorrect here.

A better Yiddish translation would be:  
"געפונען געקרימפט בלאק דאַטאַבייס" (Found corrupted block database)  
or more fully:  
"א פּלוצליכער טויטן אין בלאק דאַטאַבייס געפונען" (A corrupted block database has been detected)

A concise and clear corrected translation:  
"געקרימפּטע בלאק דאַטאַבייס געפֿונען"  
or even better:  
"געקרימפּטע בלאק דאַטאַבייס דעטעקטירט" (Corrupted block database detected)

Since "דעטעקטירט" is not a native Yiddish word but used in technical contexts, it can be acceptable.

Corrected suggestion:  
"געקרימפּטע בלאק דאַטאַבייס דעטעקטירט"
```

```
        <source>Could not find asmap file %s</source>
        <translation>נישט געמאַכט געפֿינען אַסמאַפּ אַרכיוו 1%s</translation>
    
YES
The translation is inaccurate and contains formatting errors. The source string "Could not find asmap file %s" means that the program could not locate the asmap file indicated by %s. The translation "נישט געמאַכט געפֿינען אַסמאַפּ אַרכיוו 1%s" is incorrect because:
- "נישט געמאַכט געפֿינען" literally means "not made find," which is an awkward and incorrect phrasing.
- "1%s" incorrectly adds a "1" before the format specifier "%s".
- The word "file" should be translated as "טעקע" or "פֿאָרמאַט" (common Yiddish words for 'file'), whereas "אַרכיוו" means "archive," which is not exactly correct here.

A better translation preserving the meaning and correct format specifier is:

"קען נישט געפֿינען די אַסמאַפּ־טעקע %s" 

This means "Cannot find the asmap file %s" and correctly includes the %s without extra characters.

Correct translation:
<translation>קען נישט געפֿינען די אַסמאַפּ־טעקע %s</translation>
```

```
        <source>Could not parse asmap file %s</source>
        <translation>קען ניט פֿאַראַרבעטן די asmap טעקע 1%s</translation>
    
YES  
The translation has the format specifier misplaced as "1%s" instead of "%s". Also, there is an unnecessary space before "asmap" which should be attached to the rest. The correct translation should keep "%s" as is, without adding any extra characters, and the phrase should read naturally in Yiddish.

Correct translation:  
קען ניט פֿאַראַרבעטן די asmap טעקע %s
```

```
        <source>Done loading</source>
        <translation>יאָש, אויסגעלעצט</translation>
    
YES  
The translation "יאָש, אויסגעלעצט" is incorrect and does not properly convey "Done loading" in Yiddish. "יאָש" is not a proper word here and "אויסגעלעצט" is misspelled and not fitting.

A correct translation for "Done loading" in Yiddish would be:  
"אויפֿלאַדן סוף" or more natural: "אויפֿגעלאָדן" (loaded), or "לאָדן באענטפערט" (loading finished). 

A good clear and concise Yiddish translation:  
"אויפֿלאָדן באַענדיקט"  

Correct translation:  
<translation>אויפֿלאָדן באַענדיקט</translation>
```

```
        <source>Dump file %s does not exist.</source>
        <translation>די טשיפּ אַרכיוו 1%s עסט נישט.</translation>
    
YES  
The format specifier "%s" is incorrectly written as "1%s" in the translation. The correct position of the specifier should directly mirror the source without an extra character. Also, "טשיפּ אַרכיוו" translates as "chip archive," which is not accurate for "dump file." A better translation for "dump file" in Yiddish would be "דאמפּ טעקע" (dump file) or simply transliterate "dump" and use "טעקע" (file).

Correct translation:  
די דאמפּ טעקע %s עקזיסטירט נישט.
```

```
        <source>Elliptic curve cryptography sanity check failure. %s is shutting down.</source>
        <translation>עליפטישער קרויִז קריפּטאָגראַפֿיע סאַנטי טשעק פעלער. 1%s איז שפּאַשנדיק אאָפֿן.</translation>
    
YES  
The translation misplaces the format specifier ("%s" should remain as in the source, not "1%s"), and the phrase "is shutting down" is incorrectly translated as "איז שפּאַשנדיק אאָפֿן" which means "is having fun open" or similar nonsense. The correct translation should properly convey the meaning of "sanity check failure" and "is shutting down."

Correct translation:  
עליפטישער קרויִז קריפּטאָגראַפֿיע סאַנטי טשעק פעלער. %s וועט צעספּאָרט ווערן.
```

```
        <source>Error creating %s</source>
        <translation>אור מיט שאפן 1%s</translation>
    
YES  
The translation is incorrect and contains errors and misplaced format specifier. The proper Yiddish translation for "Error creating %s" should use a correct structure and position the %s format specifier properly without an extraneous numeral "1".

Correct translation:  
שװעהַל(ש) בײַם שאפֿן %s
```

```
        <source>Error initializing wallet database environment %s!</source>
        <translation>עראר בײַ איניציאליזירן דעם וואַלט דאַטאַבאַסע אויסשטעלונג 1%s!</translation>
    
YES  
The translation contains a formatting error: the source uses "%s" as the format specifier, but the translation has "1%s" which is incorrect and will cause runtime errors. Also, the phrase is a bit awkward and mixes English words with Yiddish letters. A clearer and correctly formatted translation would be:  
עראַר בײַם איניציאליזירן פון באַנקערארגאַניזירונג־דאַטאַבאַזע %s!
```

```
        <source>Error loading %s</source>
        <translation>ערראָר לאָאַדינג 1%s</translation>
    
YES  
The translation contains errors: the English word "Error" is partially transliterated incorrectly as "ערראָר" (should be "עראָר"), "loading" is left untranslated as "לאָאַדינג", and the format specifier "%s" is incorrectly changed to "1%s" which breaks the format placeholder.  

Correct translation:  
עראָר לאָודינג %s
```

```
        <source>Error loading %s: Private keys can only be disabled during creation</source>
        <translation>גרייַזונג לאָדן 1%s: פּריוואַטע שליסלען קענען נאָר ווערן דיסאַבלירט בזמן שלאַפֿן</translation>
    
YES  
The translation contains errors and awkward wording. The English source is:  
"Error loading %s: Private keys can only be disabled during creation"

The provided translation:  
"גרייַזונג לאָדן 1%s: פּריוואַטע שליסלען קענען נאָר ווערן דיסאַבלירט בזמן שלאַפֿן"

Issues:  
1. "גרייַזונג" means "error", but the phrase "גרייַזונג לאָדן" is incorrect; the typical Yiddish expression would be "טעות בעת לאָודן" or "טעות בעת לאָדן" for "Error loading".  
2. The format specifier %s is placed as "1%s" instead of simply "%s". The extraneous "1" before "%s" is incorrect.  
3. The phrase "בזמן שלאַפֿן" literally means "during sleep", which is incorrect in this context; the source says "during creation", meaning "during creation" or "while creating". The Yiddish word for "creation" is "שאַפונג" or "ئەשפּונג" — the correct phrase should be "ביז אָן שאַפֿן" or "בײַ דער שאַפונג".  
4. "կענען נאָר ווערן דיסאַבלירט" uses "disable" as a loan word from English transliterated into Hebrew letters ("דיסאַבלירט"), which is not typical in Yiddish. A better Yiddish term might be "אויסמאַכן" (to disable, turn off) or "אָפּשאַצן" depending on context. However, loanwords are sometimes used but it's better to at least keep usage consistent and natural.

Corrected translation:  
"טעות בעת לאָודן %s: פּריוואַטע שליסלען קענען נאָר ווערן פֿונקט אין שאַפונג"

More natural full version:  
"טעות בעת לאָודן %s: פּריוואַטע שליסלען קענען נאָר בעת דער שאַפונג געוואַלט ווערן אָפּגעשטעלט"

Or more succinctly:  
"טעות בעת לאָודן %s: פּריוואַטע שליסלען קענען נאָר בעת דער שאַפונג דיסאַבלירט ווערן"

Given the domain and for clarity, a good translation would be:  
"טעות בעת לאָודן %s: פּריוואַטע שליסלען קענען נאָר בעת דער שאַפונג דיסאַבלירט ווערן"

Summary: fix "גרייַזונג" to "טעות בעת", remove "1" before "%s", replace "בזמן שלאַפֿן" with "בײַ דער שאַפונג" and keep "דיסאַבלירט" if loanword is acceptable.  

Final correct translation:  
טעות בעת לאָודן %s: פּריוואַטע שליסלען קענען נאָר בעת דער שאַפונג דיסאַבלירט ווערן
```

```
        <source>Error loading %s: Wallet corrupted</source>
        <translation>Ошибка לאָדן 1%s: װאַלעט קראָופּטעד</translation>
    
YES  
The translation contains mixed languages: the first word "Ошибка" is Russian, not Yiddish (yi). Also, the format specifier "%s" is incorrectly written as "1%s". The Yiddish text "לאָדן" (loading) and "וואַלעט קראָופּטעד" (wallet corrupted, using an anglicism) is mixed with Russian, which is inconsistent and likely problematic. The correct Yiddish translation should be fully in Yiddish script and preserve the format specifier "%s" properly.

Correct translation:  
שטרעקל בייַ לאָדן %s: וואַלעט צעבראכן
```

```
        <source>Error loading %s: Wallet requires newer version of %s</source>
        <translation>טעות אין לאָאַדינג 1%s: וואָלאַט דאַרף אַ נײַער ווערסיע פון 1%s</translation>
    
YES  
The placeholders "%s" are incorrectly written as "1%s" in the translation, which breaks the format specifier integrity. Also, the phrase "Error loading" is partially translated as "טעות אין לאָאַדינג" which mixes English and Yiddish ("loading" is left untranslated). A better Yiddish translation would use "טעות בייטע לאָדן" ("Error while loading") or a more natural phrasing.  

Correct translation:  
טעות בייטע לאָדן %s: וואָלטשע וועט אַ נײַערע ווערסיע פון %s פאַרלאנגט
```

```
        <source>Error loading block database</source>
        <translation>Ошибка בעת טעילונג פון בלאָק דאַטאַבייס</translation>
    
YES
The translation mixes Russian ("Ошибка") and Yiddish ("בעת טעילונג פון בלאָק דאַטאַבייס"). This is inconsistent and unacceptable for a pure Yiddish translation.

Correct translation:
פאַרשפּרייטונג בלעטער דאַטאַבייס לאָדן פֿעלער
```

```
        <source>Error opening block database</source>
        <translation>אַ ערראָר בעת עפענען בלאָק דאַטאַבייס</translation>
    
YES  
The translation mixes English ("ערראָר", "בלאָק", "דאַטאַבייס") with Yiddish transliteration, which is not appropriate. The phrase should be fully translated into Yiddish using proper Yiddish terminology and script.

A correct translation would be:  
"שײַכטןע טעות בײַם עפֿענען פֿון בלאָק־דאַטאַבייס"
```

```
        <source>Error reading configuration file: %s</source>
        <translation>יֶתֶר שְׁגוּת בַּקרִיאָה של קובץ ההגדרות: 1%s</translation>
    
YES  
The translation is problematic. It contains Hebrew characters instead of Yiddish (which uses the Hebrew alphabet but different orthography and has different vocabulary), and the format specifier `%s` is incorrectly prefixed by the number `1`, making it `1%s` instead of `%s`. Also, "Error reading configuration file:" should be correctly reflected in Yiddish.  

Correct translation:  
שטראָף לייענען קאַנפיגוראַציע טעקע: %s
```

```
        <source>Error reading from database, shutting down.</source>
        <translation>טעעות לייענען פֿון דער דאטן-בנק, פֿאַראָפנט זיך.</translation>
    
YES  
The translation contains errors and is problematic. The phrase "shutting down" is incorrectly translated as "פֿאַראָפנט זיך" which means "opens" instead of "shuts down" or "closing". Also, "דאטן-בנק" is a calque from English "data-bank", but the more appropriate Yiddish term for "database" could be "דאטענבנק" or a more understandable phrasing.  

Correct translation:  
"טעות בײַם לייענען פֿון דער דאַטאַבאַנק, פּאָטשלאָסן."  
or alternatively:  
"טעות בײַם לייענען פֿון דער דאַטאבייס, פּאָטשלאָסן."
```

```
        <source>Error: Cannot extract destination from the generated scriptpubkey</source>
        <translation>טרוט: קענען נישט ארויסנעמען דעם דעסטינאציע פון ​​דער דזשענערירט סקрипטפּובקיי</translation>
    
YES  
The translation contains a whitespace formatting issue: there is an unwanted space after the Hebrew "פֿון" (פון) and before "דער" which is joined incorrectly. Also, the phrase "דעסטינאציע" is a transliteration of "destination," which is acceptable given Yiddish usage, but "סקрипטפּובקיי" is a transliteration of "scriptpubkey" that might be better hyphenated or spaced for clarity. Additionally, the word "Error" is translated as "טרוט" which is incorrect; the correct Yiddish word for "Error" is "טעות" (to'es).

Correct translation:  
טעות: קענען נישט ארויסנעמען דעם דעסטינאציע פֿון דער דזשענערירט סקрипטפּובקיי
```

```
        <source>Error: Disk space is low for %s</source>
        <translation>גרייַז: דיסק פּלאַץ איז נידעריק פֿאַר 1%s</translation>
    
YES  
The translation has an incorrect placement of the format specifier. The source has `%s`, but the translation has `1%s`, which is wrong. Also, the rest of the sentence is accurate, but the stray '1' before `%s` is an error.

Correct translation:  
גרייַז: דיסק פּלאַץ איז נידעריק פֿאַר %s
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>טעות: דער טשעקזאַם פון דעם דאטעי איז נישט גלייך. רעכנט 1%s, ערווארטעט 1%s</translation>
    
YES  
The translation incorrectly adds '1' before the format specifiers %s, which is not present in the source and is erroneous. The rest of the translation accurately conveys the message. The format specifiers should match exactly.  

Correct translation:  
טעות: דער טשעקזאַם פֿון דער דאטעי פּאַרטע שטימט נישט צו. רעכנט %s, ערוואַרט %s
```

```
        <source>Error: Got key that was not hex: %s</source>
        <translation> טעות: באקומען אַ שליסל וואָס איז נישט העקס: 1%s</translation>
    
YES  
The translation contains an erroneous addition of "1" before the format specifier "%s", which is incorrect and breaks the placeholder usage. Also, the format specifier should be copied exactly from the source without any added characters.  

Correct translation:  
טעות: באקומען אַ שליסל וואָס איז נישט העקס: %s
```

```
        <source>Error: Got value that was not hex: %s</source>
        <translation>טעות: באקומען אַ ווערט וואָס איז נישט העקס: 1%s</translation>
    
YES  
The translation incorrectly includes a stray "1" before the format specifier "%s" and the phrase "Got value" is translated as "באקומען אַ ווערט" ("received a value") instead of a more neutral "Got value" or "Received a value". Also, there should be no extra space before the colon (although in Yiddish colon usage often follows the same pattern as English). The format specifier "%s" should be exactly as in the source and without a leading "1".

Correct translation:  
טעות: געהאט אַ ווערט וואָס איז נישט העקס: %s
```

```
        <source>Error: Missing checksum</source>
        <translation>אַ עירור: מענגלען טשעקסום</translation>
    
YES  
The translation contains a typo: "אַ עירור" should be "אַ פּראָבלעם" or "טעקע" instead of "אַ עירור" ("אַ עירור" literally means "a city" or "a disturbance," which is incorrect here). Also, "מענגלען" is slightly off; the correct Yiddish word for "missing" is "פעלן" or "פעלן דעם". "טשעקסום" for "checksum" is acceptable as a transliteration, but "טעקע" or "טעקע" might be better depending on context.

Correct translation:  
"טעקע: פֿעלן טשעקזאַם"  
or more formally:  
"פֿאַרקערט: קינדערדיקער באַזע פֿעלן"  
But keeping close to original:  
"טעקע: פֿעלן טשעקזאַם"
```

```
        <source>Error: No %s addresses available.</source>
        <translation>טע mistake: קיין 1%s אַדרעסן ניט פארfügbar.</translation>
    
YES  
The translation contains English ("mistake") and mixes format specifier incorrectly ("1%s" instead of "%s"). The correct placement of the format specifier "%s" must match the source, and foreign words should be consistent. The word "טע" (te) is Yiddish for "the", but "mistake" is English and should be replaced by the Yiddish equivalent, e.g., "פאַרקער" (error/mistake).

Correct translation:  
שיטעך: קיין %s אַדרעסן פאַראַנונטער.  
(Alternatively, using "אויפֿפֿאַל" or "פאַרקער" for error depending on dialect:  
"אפֿער: קיין %s אַדדרעסן ניט פאַראַנונטער." )
```

```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>אורור: נישט קענען פארשטיין ווערסיע %u אלס א uint32_t</translation>
    
YES
The Yiddish word for "Error" is spelled "טעות" or "פֿעלער" rather than "אורור," which appears to be a typo or nonsense. Also, "נישט קענען פארשטיין" is a literal and awkward translation of "Unable to parse." A better phrasing would be "נישט מעגלעך צו אַרייַננעמען" or "נישט מעגלעך צו פּאַרסירן." The format specifier %u is correctly preserved.

Correct translation:
טעקע: נישט מעגלעך צו פּאַרסירן ווערסיע %u אלס אַ uint32_t
```

```
        <source>Error: database transaction cannot be executed for wallet %s</source>
        <translation>טעות: די דאטאבאזע טראַנזאַקשאַן קען נישט דורכגעפֿירט ווערן פֿאַר וואַלעט 1%s</translation>
    
YES  
The format specifier "%s" is incorrectly changed to "1%s" in the translation, which is an error. Also, the translation mixes English ("דאטאבאזע טראַנזאַקשאַן") with the rest of the text in Yiddish (which is the 'yi' language). While some technical terms may be borrowed, it is better to keep the format specifier intact and correctly positioned.

Correct translation:  
טעות: די דאטאבאזע טראַנזאַקשאַן קען נישט דורכגעפֿירט ווערן פֿאַר וואַלעט %s
```

```
        <source>Failed to connect best block (%s).</source>
        <translation>ניט הצלחה צו פאַרבינדן דעם בעסטן בלאָק (1%s).</translation>
    
YES
The format specifier "%s" is incorrectly written as "1%s" in the translation. Also, the phrase "ניט הצלחה צו פאַרבינדן" is a bit unnatural; a more standard Yiddish phrasing would use "ניט מצליח צו פאַרבינדן" or "פֿאַרמאָגט נישט צו פֿאַרבינדן".

Correct translation:  
ניט מצליח צו פֿאַרבינדן דעם בעסטן בלאָק (%s).
```

```
        <source>Failed to disconnect block.</source>
        <translation>פֿאַרפאַלן צונויפֿרובֿן בלאָק</translation>
    
YES  
The translation "פֿאַרפאַלן צונויפֿרובֿן בלאָק" is not an accurate or natural rendering of "Failed to disconnect block." in Yiddish. The phrase "פֿאַרפאַלן" means "lost" or "failed" in some contexts but is not used as a verb here, and "צונויפֿרובֿן" is a very literal and awkward construction meaning something like "to connect together" (not "disconnect"). The English concept "disconnect" should be translated more clearly. A better translation would emphasize failure to disconnect or separate a block.

Correct translation:  
פֿאַרהאַלטן אָפּצונײַדן בלאָק.  
(or)  
ניט גענוג צו עפֿענען דעם בלאָק.  

Given the Bitcoin context, a clearer and more direct expression:  
ניט געלונגען דעם בלאָק צו טרענען.  

Among these, the last is likely the clearest:  
ניט געלונגען דעם בלאָק צו טרענען.
```

```
        <source>Failed to read block.</source>
        <translation>יאָר נישט קריגן בלאָק</translation>
    
YES  
The provided Yiddish translation "יאָר נישט קריגן בלאָק" is incorrect and does not convey the intended meaning. "יאָר" means "year," which is not appropriate here, and the verb form is also incorrect for "Failed to read block." The correct translation should convey the failure to read a block, typically using a negative past form of "to read" or "to get."

Correct translation:  
ניט צוגעקענט ליינען דעם בלאָק.  
(or)  
ניט געקענט ליינען בלאָק.
```

```
        <source>Failed to verify database</source>
        <translation>פֿעלן צו פאַראַוואָרטן די דאַטאַבאַזע</translation>
    
YES  
The translation "פֿעלן צו פאַראַוואָרטן די דאַטאַבאַזע" is problematic. The phrase "פֿעלן צו" is not the correct way to say "Failed to" in Yiddish. Also, "פֿאַראַוואָרטן" is not a standard Yiddish verb for "verify." A better translation would be:  
"ניט מצליח צו פאַרשטיין די דאַטאַבאַזע" or more precisely "פֿאַרפאַלן צו פֿאַרשטיין די דאַטאַבאַזע" although "verify" is better translated as "פאַרשאַפֿן" or "בודק" is not idiomatic in Yiddish. A more suitable phrase for "Failed to verify database" could be:  

"ניט מצליח צו קאָנטראָלירן די דאַטאַבאַזע"  

So the correct translation is:  
"ניט מצליח צו קאָנטראָלירן די דאַטאַבאַזע"
```

```
        <source>Failure removing transaction: %s</source>
        <translation>פאלשיקייט אויבן ארויף די טראַנסאַקשאַן: 1%s</translation>
    
YES  
The translation incorrectly places "1" before the format specifier "%s" and uses a mistranslation for "Failure" ("פאלשיקייט" means "failure" but the phrase structure is unnatural). The phrase should clearly convey "Failure removing transaction: %s" without extra characters. Also, the verb or action "removing" is missing or unclear in the translation.

Correct translation:  
פֿאַלשיקייַט ביים פֿאַרבייַטן דעם טראַנסאַקשאַן: %s
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>פֿיע-ראַטע (1%s) איז נידעריקער ווי די מינימום-פֿיע-ראַטע באַשטעטיקן (1%s)</translation>
    
YES  
The translation incorrectly inserts a "1" before the format specifiers "%s". The placeholders should be copied exactly as in the source without additional characters.  

Correct translation:  
פֿיע-ראַטע (%s) איז נידעריקער ווי די מינימום-פֿיע-ראַטע באַשטעטיקן (%s)
```

```
        <source>Ignoring duplicate -wallet %s.</source>
        <translation>ניט באַמערקן דופליקאַט -וואָלעט 1%s.</translation>
    
YES
The translation incorrectly adds "1" before the %s format specifier and mistranslates "Ignoring" as "ניט באַמערקן" (which means "not notice" or "not remark"). The phrase "Ignoring duplicate -wallet %s." should convey that a duplicate wallet argument is being ignored, not just unnoticed.

Correct translation:
"עכענען אויס דופליקאַט -וואָלעט %s."
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>נאכאמלק נישט קיין גענעזיס בלאָק געפֿונען, אָדער נישט קיין געלעגנהייט. פֿאַרוואָן דאטע-דירעקטאָריע פֿאַר נעץ?</translation>
    
YES
The translation contains inaccuracies and awkward phrasing. "נאכאמלק נישט קיין גענעזיס בלאָק געפֿונען, אָדער נישט קיין געלעגנהייט." is unclear and does not correctly convey "Incorrect or no genesis block found." The original message refers to an incorrect or missing genesis block related to blockchain data, not "no opportunity" (געלעגנהייט).

A better translation would be:
"אונקארעקט אָדער קיינער גענעזיס בלאָק געפונען. פאַלשער דאטאַדיר פאַר נעץ?"

This correctly reflects the original meaning and retains the technical terms appropriately.
```

```
        <source>Initialization sanity check failed. %s is shutting down.</source>
        <translation>יוזע אָנפאַנג סאַנטי טשעק איז פעלל געווען. 1%s איז זיך אונטערגעשטעלט.</translation>
    
YES  
The translation contains errors:  
1. The phrase "יוזע אָנפאַנג סאַנטי טשעק" is a direct transliteration of "Initialization sanity check," which is not idiomatic or clear in Yiddish.  
2. "פעלל געווען" should be "געפעלט" for "failed."  
3. The format specifier "%s" is incorrectly written as "1%s." The "1" is extraneous and should be removed.  
4. "איז זיך אונטערגעשטעלט" is an awkward way to say "is shutting down"; a better phrasing would be "איז אָנטשאָלטן" or "גייט אַוועק."  

Correct translation:  
"פֿאַרשטעלן-געפֿאַלן סאַנטקייט־פּרובירן. %s גייט אַוועק."
```

```
        <source>Invalid -i2psam address or hostname: '%s'</source>
        <translation>אַרויסגעבן -i2psam אַדרעס אָדער האָסטניימע: '1%s' איז אומגערעכט.</translation>
    
YES  
The translation introduces an incorrect prefix "אַרויסגעבן" which means "output" or "export" rather than "Invalid". Additionally, the '%s' format specifier is incorrectly changed to '1%s'. Also, the sentence structure should reflect that the address or hostname is invalid, similar to the source.  

Correct translation:  
אומגעלאנג -i2psam אַדרעס אָדער האָסטנימע: '%s'
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>יולעזער -אוןיאָן אדרעס אדער הוסטנאַם: '1%s'</translation>
    
YES
The translation incorrectly adds a "1" before the %s format specifier, which is not present in the source and breaks the format. Also, "יולעזער" is a transliteration of "user," not the translation of "Invalid," which should be something like "איין אומגעלונגען" or "אינוואַלידעץ" if transliterated. The word "hostname" is transliterated correctly as "הוסטנאַם," and "address" as "אדרעס" is acceptable.

Correct translation:
אינוואַליד -אוןיאָן אדרעס אדער הוסטנאַם: '%s'
```

```
        <source>Invalid -proxy address or hostname: '%s'</source>
        <translation>אין גültיק -פּראָקסי אַדרעס אָדער האָסטנײם: '1%s'</translation>
    
YES
The translation contains a mix of Hebrew/Yiddish script and German ("גültיק" means "valid" in German) and incorrectly adds an extra "1" before the %s format specifier. The format specifier should be exactly as in the source ("%s") without extra characters. Also, the German word is inappropriate here; the correct Yiddish equivalent would be used instead of "גולטיק" or "גוט".

Correct translation:
אונגילטיק -פּראָקסי אַדרעס אָדער האָסטןיים: '%s'
```

```
        <source>Invalid P2P permission: '%s'</source>
        <translation>יוצרים פּ2פּ זכּות: '1%s'</translation>
    
YES
The translation is incorrect and contains errors. The English phrase "Invalid P2P permission: '%s'" should convey that the permission is invalid, but the translated phrase "יוצרים פּ2פּ זכּות: '1%s'" means "Creators P2P rights: '1%s'", which is both semantically wrong and contains an extraneous "1" before the format specifier.

Correct translation:
אינוואַלאַד פּ2פּ באַוויליקונג: '%s'
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>ניט גאָלדיגער בטראַכט פֿאַר 1%s=: '1%s' (מוז זײַן בּאַלד נישט ווייניקער ווי 1%s)</translation>
    
YES  
The translation has multiple issues:  
1. Erroneous insertion of numeral '1' before each %s placeholder (e.g., "1%s"), which is incorrect and distorts the placeholders. The placeholders must be identical to the source: %s.

2. The phrase structure is unnatural and does not clearly convey "Invalid amount for %s=<amount>".

3. The last part "(must be at least %s)" is rendered as "(מוז זײַן בּאַלד נישט ווייניקער ווי 1%s)" – "בּאַלד" means "soon" and is incorrect here.

A correct translation would keep the placeholders intact and express the meaning properly:  

ניט תקין סומע פֿאַר %s=&lt;amount&gt;: '%s' (מוזן זיין מינימום %s)
```

```
        <source>Invalid amount for -%s=&lt;amount&gt;: '%s'</source>
        <translation>אין ואלידער בטראָג פֿאַר -%s=&lt;amount&gt;: '%s'</translation>
    
YES  
The translation contains the English word "וואalidער" which is a transliteration of "valid" and is not standard Yiddish. The phrase "אין ואלידער" is incorrect; a proper Yiddish translation for "Invalid amount" should use the Yiddish word for "invalid" (e.g., "אונגלײַכטער", "אינוואלידער" or "אונגילטיקער") and "בטראָג" (amount) is correct. Also, the use of single quotes around '%s' is correct and format specifiers are preserved.

Correct translation:  
אונגילטיקער בטראָג פֿאַר -%s=&lt;amount&gt;: '%s'
```

```
        <source>Invalid netmask specified in -whitelist: '%s'</source>
        <translation>ניט גיטע נעטמאַסק געבאַטן אין -ווייטליסט: '1%s'</translation>
    
YES
The format specifier in the source is '%s', but in the translation it appears as '1%s', which is incorrect and would cause formatting errors. The '1' should be removed.

Correct translation:
ניט גיטע נעטמאַסק געבאַטן אין -ווייטליסט: '%s'
```

```
        <source>Invalid port specified in %s: '%s'</source>
        <translation>יערור פּאָרט פארמאַטער אין 1%s: '1%s'</translation>
    
YES  
The translation is incorrect and contains erroneous format specifiers "1%s" instead of "%s", which breaks the placeholders used in the source. The word "יערור" means "error" but does not directly translate "Invalid" accurately in this context. The phrase "פּאָרט פארמאַטער" (port parameter) is understandable, but the format specifiers must be exact. Also, the quotes around '%s' are correct as in the source.

Correct translation:  
אינפֿאַליד פּאָרט אינדיקירט אין %s: '%s'
```

```
        <source>Invalid pre-selected input %s</source>
        <translation>ניט געלטיק פּרע-געקליבן אַרײַן 1%s</translation>
    
YES  
The translation incorrectly places the format specifier as "1%s" instead of "%s". The correct translation should keep the format specifier exactly as in the source without additional characters. Also, the use of "1" before "%s" is a mistake.

Correct translation:  
ניט געלטיק פּרע-געקליבן אַרײַן %s
```

```
        <source>Listening for incoming connections failed (listen returned error %s)</source>
        <translation>פֿאַרענטפֿערס פֿאַר אָנקומען קאָנעקציעס איז געשלאגן (הערן האט צוריקגעגעבן טעות 1%s)</translation>
    
YES
The translation erroneously adds a '1' before the format specifier '%s', which is not present in the original source text. Also, the phrase "הערן האט צוריקגעגעבן טעות" literally means "listening returned error," but more natural phrasing would be preferable. The correct translation should preserve the format specifier exactly as in source and read smoothly in Yiddish.

Correct translation:
פֿאַרענטפֿערס פֿאַר אָנקומען קאָנעקציעס איז געשלאגן (הערן האט צוריקגעגעבן פֿעלער %s)
```

```
        <source>Loading block index…</source>
        <translation>יִדעוועקט דעם בלאָק אינדעקס…</translation>
    
YES  
The translation uses "יִדעוועקט" which appears to be a borrowing or incorrect form and not a proper Yiddish verb equivalent to "loading." A more accurate translation for "Loading block index…" in Yiddish could be:  
"לאַדינג בלאָק אינדעקס…" is too anglicized; better to use "לאָדירנדיק בלאָק אינדעקס…" or "לאָדן בלאָק אינדעקס…"  

Correct translation:  
"לאָדן בלאָק אינדעקס…"
```

```
        <source>Maximum transaction weight must be between %d and %d</source>
        <translation>דער מקסימום פון טערנזאַקטיאָן וואָג מוז זיין צווישן 1%d און 1%d</translation>
    
YES
The translation incorrectly adds a "1" before the format specifiers (%d), which does not exist in the source text. Additionally, the phrase "דער מקסימום פון טערנזאַקטיאָן וואָג" is understandable but slightly unnatural. A more natural Yiddish translation would be:

מאַקסימום טראַנסאַקציע וואָג מוז זיין צווישן %d און %d
```

```
        <source>Missing solving data for estimating transaction size</source>
        <translation>פֿעלן די פתרון דאטן פֿאַר דערשיידן טראַנסאַקשאַן גרייס</translation>
    
YES
The translation has some issues: the word "דערשיידן" literally means "to distinguish" rather than "estimating" or "estimating/calculating." A more appropriate verb to convey "estimating" would be "שאַצן" (to estimate). Also, the phrase "Missing solving data" should be clearer in Yiddish; "Missing" is better translated as "פעלן" (missing) but the word order and phrasing can be improved for clarity.

Correct translation:
פֿעלן לייזונג דאטן פֿאַר שאַצן טראַנסאַקשאַן גרייס
```

```
        <source>Need to specify a port with -whitebind: '%s'</source>
        <translation>מוז מען צושטעלן אַ פּאָרט מיט -whitebind: '1%s'</translation>
    
YES  
The format specifier %s from the source is incorrectly changed to '1%s' in the translation, which is a formatting error that can lead to runtime issues. The translation should preserve the exact format specifier.

Correct translation:  
מוז מען צושטעלן אַ פּאָרט מיט -whitebind: '%s'
```

```
        <source>Not found pre-selected input %s</source>
        <translation>נישט געפֿונען פֿאַר-ערקלערטע אַפּגראַדע 1%s</translation>
    
YES  
The translation is inaccurate and does not correspond to the source text. The source sentence "Not found pre-selected input %s" refers to an input (likely in Bitcoin context) that was pre-selected but not found, whereas the translation "נישט געפֿונען פֿאַר-ערקלערטע אַפּגראַדע 1%s" reads as "Not found pre-declared upgrade 1%s," which uses incorrect terminology ("אַפּגראַדע" meaning "upgrade") and incorrectly places the format specifier after the number 1, which was not in the source text. 

Correct translation:  
נישט געפֿונען פּרע-סעלעקטעד אינפּוט %s
```

```
        <source>Not solvable pre-selected input %s</source>
        <translation>נישט אָסאָלוועבל פּרע-רעבחרטע אינפּוט 1%s</translation>
    
YES  
The translation incorrectly places the format specifier as "1%s" instead of "%s". Also, the phrase "נישט אָסאָלוועבל" is a transliteration of "not solvable" but may be better expressed in proper Yiddish as "ניט לייזלעך". The "pre-selected input" can be translated as "פֿאַראויסגערופענע אינפּוט" or "פֿאַראויסגעקליבן אינפּוט".  

Correct translation:  
ניט לייזלעך פֿאַראויסגעקליבן אינפּוט %s
```

```
        <source>Only direction was set, no permissions: '%s'</source>
        <translation>נור פֿאַרלויף איז אופן, קיין רעכט נישט: '1%s'</translation>
    
YES
The placeholder in the source is '%s', but in the translation it appears as '1%s', which is incorrect and could cause errors when formatting the string. Also, the phrase "Only direction was set, no permissions" should be accurately rendered without added or misplaced characters.

Correct translation:
נור דעם ריכטונג איז איינגעשטעלט געווארן, קיין דערלויבעניש: '%s'
```

```
        <source>Prune mode is incompatible with -txindex.</source>
        <translation>פּרון מצב איז אומגעפּאַראַט מיט -txindex.</translation>
    
YES  
The translation contains a mix of Hebrew/Yiddish script and English, and the phrase "פּרון מצב" (which seems to be trying to render "Prune mode") is not idiomatic nor correct Yiddish. The word "אָומגעפּאַראַט" is a transliteration of "incompatible" but is not standard or correct Yiddish usage. The English command line argument "-txindex" is correctly copied.  

A more accurate Yiddish translation would be:  
"פּרון מאָדע איז נישט קאַמפּאַטיביל מיט -txindex."  

This uses "מאָדע" for "mode" and "נישט קאַמפּאַטיביל" (not compatible) which is understandable in technical contexts or alternatively:  
"פּרון מאָדע פֿונקטיאָנירן נישט מיט -txindex." (Prune mode does not work with -txindex.)  

Corrected:  
<translation>פּרון מאָדע איז נישט קאַמפּאַטיביל מיט -txindex.</translation>
```

```
        <source>Pruning blockstore…</source>
        <translation>פאַרקייַטונג בלאקסטאָר</translation>
    
YES  
The translation "פאַרקייַטונג בלאקסטאָר" literally means "pruning blockstore" but is missing the ellipsis (…) which is present in the source and usually indicates an ongoing process. Also, the English "blockstore" is transliterated rather than fully translated or adapted. In Yiddish, it would be better to either transliterate consistently or use an appropriate term. A more natural translation would be:

פאַרקייַטונג בלאקסטאָר…
```

```
        <source>Reducing -maxconnections from %d to %d, because of system limitations.</source>
        <translation>מינעערן -maxconnections פון 1%d צו 1%d, צוליב סיסטעם גרעניצונגען.</translation>
    
YES
The translation incorrectly prefixes the format specifiers %d with an extra '1' (i.e., "1%d" instead of "%d"), which is not correct and will cause formatting errors. The rest of the translation is appropriate.

Correct translation:
מינעערן -maxconnections פון %d צו %d, צוליב סיסטעם גרעניצונגען.
```

```
        <source>Replaying blocks…</source>
        <translation>ייִדן בלאָקען נאָך</translation>
    
YES  
The translation "ייִדן בלאָקן נאָך" is incorrect and problematic. It roughly means "Yidden block after" or "Jews blocks after," which is unrelated and potentially misleading. The English phrase "Replaying blocks…" in the context of Bitcoin means reprocessing or replaying blockchain blocks. A better Yiddish translation would be:  
"געשפּילן לעבן בלאָקעס…"  
or  
"רעפערירן בלאָקעס…"  
to convey the sense of replaying or reprocessing blocks.
```

```
        <source>SQLiteDatabase: Failed to execute statement to verify database: %s</source>
        <translation>SQLiteDatabase: אויב עס איז נישט מיטגעקומען מיטן אויספירן דעקלאראַציע צו אויפריכטען די דאטן-בנק: 1%s</translation>
    
YES  
The translation is inaccurate and problematic. The phrase "אָויב עס איז נישט מיטגעקומען מיטן אויספירן דעקלאראַציע צו אויפריכטען די דאטן-בנק: 1%s" incorrectly translates "Failed to execute statement to verify database" and adds an extraneous "אָויב" ("if") and a misplaced "1%s" instead of "%s." The format specifier "%s" is incorrectly changed to "1%s," which is wrong.

Correct translation:  
SQLiteDatabase: פאַרטויגן צו דורכפירן דער באַפֿעלן צו קאָנטראָלירן דעם דאַטאַבאַזע: %s
```

```
        <source>SQLiteDatabase: Failed to prepare statement to verify database: %s</source>
        <translation>SQLiteDatabase: עס איז נישט מצליח צו פארהערן דער אויסשטרעלונג צו באשטעטיגן דעם דאטאבייס: 1%s</translation>
    
YES  
The translation includes an incorrect placement of the format specifier "%s" as "1%s" which is erroneous. The original "%s" must be preserved exactly and not changed or prefixed with "1". Also, the phrase "עס איז נישט מצליח צו פארהערן" is literal but awkward Yiddish ("it is not successful to prepare"). A better phrasing would be more natural and closer to the original meaning.

Correct translation:  
SQLiteDatabase: עס איז נישט מצליאן צו צוגרייטן אַן אויסשטרעלונג צו באשטעטיקן דעם דאטאבייס: %s
```

```
        <source>SQLiteDatabase: Failed to read database verification error: %s</source>
        <translation>SQLiteDatabase: עס איז נישט מצליח צו פארהערן דער אויסשטרעלונג צו באשטעטיגן דעם דאטאבייס: 1%s</translation>
    
YES  
The translation contains erroneous content: the source placeholder "%s" is incorrectly altered to "1%s" and the sentence structure is unnatural and confusing in Yiddish. Also, "פארהערן" is incorrect here; a more appropriate word for "read" in this context would be "לייענען" (to read). The phrase "verification error" should be translated more clearly as "באַשטעטיקונג פאַלקער" or "באַשטעטיקונג ערראָר".

Correct translation:  
SQLiteDatabase: עס איז נישט מצליח צו לייענען באַשטעטיקונג ערראָר פֿון דער דאטאַבייס: %s
```

```
        <source>SQLiteDatabase: Unexpected application id. Expected %u, got %u</source>
        <translation> SQLiteDatabase: אומפאַרווארפן אַפּליקאַציע אייר. ציפער 1%u, באקומען 1%u</translation>
    
YES
The translation has spacing issues (leading space before "SQLiteDatabase:"), and the format specifiers %u are incorrectly placed with extraneous characters ("1%u" instead of "%u"). The phrase "Unexpected application id. Expected %u, got %u" is mistranslated as "אָמפאַרווארפן אַפּליקאַציע אייר. ציפער 1%u, באקומען 1%u", which is not accurate Yiddish.

Correct translation:
SQLiteDatabase: אומגעראכט איינטרעטן אַפּלאַקאַציע אידענטיפיקאַטאָר. ציפער %u, באקומען %u
```

```
        <source>Section [%s] is not recognized.</source>
        <translation>סעקטאָר [1%s] איז נישט אנערקענט.</translation>
    
YES  
The translation incorrectly includes "1" before the "%s" format specifier, which does not exist in the source text. The format specifier should be copied exactly as "%s" without added characters.  

Correct translation:  
סעקטאָר [%s] איז נישט אנערקענט.
```

```
        <source>Signer returned error: %s</source>
        <translation>Yiddish: סײַנער האָט צוריקגעגעבן עראָר: 1%s</translation>
    
YES
The translation incorrectly adds "Yiddish:" at the beginning and inserts a stray '1' before the format specifier '%s'. The format specifier should be preserved exactly as in the source without additional characters. Also, the English word "error" should be properly translated into Yiddish, for example, as "פארטאָן" or "טעות" instead of "עראָר".

Correct translation:
סײַנער האָט צוריקגעגעבן טעות: %s
```

```
        <source>Signing transaction failed</source>
        <translation>דער אָנשטיין פון דער טרנזקציע איז אויווד</translation>
    
YES  
The translation is incorrect and awkward. It uses a phrase that literally means "The ignition of the transaction is failed," which does not correctly convey "Signing transaction failed." The proper translation should directly state that the signing process failed.

Correct translation:  
אונמעגליך צו אונטערשרײַבן די טרנזקציע
```

```
        <source>Specified -walletdir "%s" does not exist</source>
        <translation>יאָוולעט דיר '-walletdir "1%s"' עקזיסטירט נישט.</translation>
    
YES  
The translation is incorrect in several ways:  
- The placeholder `%s` is altered to `1%s`, which is wrong; format specifiers must be identical to the source.  
- There is an improper addition of a Hebrew/Yiddish-like term "יאָוולעט דיר" instead of a transliteration or proper Yiddish equivalent for "-walletdir".  
- The dash before "walletdir" is missing or misplaced in the translation.  
- The sentence structure is awkward.

A better translation would be a direct and clear statement preserving the format specifier and the option name as in the source, for example:  

יילאזט -walletdir "%s" עקזיסטירט נישט.  

(Note: Yiddish often borrows technical terms in Latin characters; keeping "-walletdir" as is is acceptable.)
```

```
        <source>Specified -walletdir "%s" is a relative path</source>
        <translation>די צוגעגעבענע -walletdir "1%s" איז אַ רעלאַטיווע פּאַט.</translation>
    
YES
The format specifier "%s" is incorrectly translated as "1%s" with an added "1" before the percent sign. This alters the intended placeholder and is erroneous.

Correct translation:
די צוגעגעבענע -walletdir "%s" איז אַ רעלאַטיווע פּאַט.
```

```
        <source>Specified -walletdir "%s" is not a directory</source>
        <translation>דער באשטימטער -walletdir '1%s' איז נישט אַ דירעקטאָריע</translation>
    
YES  
The format specifier "%s" is incorrectly changed to "1%s" in the translation, which is a critical error. The specifier must remain exactly as in the source to function correctly. Also, the quotation marks around "%s" in the source should be mirrored properly in the translation.  

Correct translation:  
דער באשטימטער -walletdir "%s" איז נישט אַ דירעקטאָריע
```

```
        <source>Specified blocks directory "%s" does not exist.</source>
        <translation>געווויערן בלאָק דיירעקטאָריע '1%s' עקזיסטירט נישט.</translation>
    
YES  
The translation incorrectly includes '1%s' instead of '%s'. The format specifier from the source ("%s") must be preserved exactly in the translation without adding any extra characters. Additionally, the Yi language typically uses the Latin alphabet for transliteration, and the quotation marks should match as in the source.

Correct translation:  
געוו speci פאַרבאָרגן בלאָק דיירעקטאָריע "%s" עקזיסטירט נישט.
```

```
        <source>Specified data directory "%s" does not exist.</source>
        <translation>Yiddish: דער באַשטימטער דאַטע דירעקטאָריע "1%s" עקזיסטירט נישט.</translation>
    
YES  
The translation incorrectly includes the English word "Yiddish:" at the beginning and incorrectly prepends a "1" before the format specifier %s. The format specifier should be preserved exactly as "%s" without changes. Also, the unnecessary "1" should be removed, and the prefix "Yiddish:" is not part of the translation.  

Correct translation:  
דער באַשטימטער דאַטע דירעקטאָריע "%s" עקזיסטירט נישט.
```

```
        <source>System error while flushing: %s</source>
        <translation>ייִדיש: סיסטעם עראר בעת פלושטשינג: 1%s</translation>
    
YES
The translation contains erroneous content: the word "ייִדיש:" (meaning "Yiddish:") is incorrectly included at the start, which is unnecessary. Also, "פלושטשינג" is a transliteration of the English "flushing," but a better Yiddish equivalent or clearer phrasing should be used. The format specifier "%s" is misplaced as "1%s". 

Correct translation:  
סיסטעם שטײַרט בעת אָפּשאַפן: %s
```

```
        <source>System error while loading external block file: %s</source>
        <translation>יִשׁוּב סִיסטֶם בעת לאָדן אָפּזעצער בלאָק-פֿײַל: 1%s</translation>
    
YES  
The format specifier `%s` is incorrectly changed to `1%s` in the translation. It should remain exactly `%s` to match the source. Also, the transliteration "לאָדן" for "loading" and "אָפּזעצער" for "external" appear acceptable, but the prefix "1" before `%s` is an error.  

Correct translation:  
יִשׁוּב סִיסטֶם בעת לאָדן אָפּזעצער בלאָק-פֿײַל: %s
```

```
        <source>System error while saving block to disk: %s</source>
        <translation>סיסטעם ערראָר בעת שמירה בלאָק אויף דיסק: 1%s</translation>
    
YES  
The translation incorrectly places the format specifier as "1%s" instead of "%s". The "1" is extraneous and should be removed. Also, the rest of the translation accurately conveys the meaning "System error while saving block to disk".  

Correct translation:  
סיסטעם ערראָר בעת שמירה בלאָק אויף דיסק: %s
```

```
        <source>The source code is available from %s.</source>
        <translation>די מקור קאָד איז בנימצא פון 1%s.</translation>
    
YES  
The translation incorrectly places the format specifier as "1%s" instead of "%s". The correct format specifier should be kept exactly as in the source. The word order and phrasing are otherwise fine, but the "%s" must not be altered.

Correct translation:  
די מקור קאָד איז בנימצא פֿון %s.
```

```
        <source>The specified config file %s does not exist</source>
        <translation>דער צוגעגעבענע קאנפיג־טעקסט 1%s עקזיסטירט נישט.</translation>
    
YES  
The format specifier %s is incorrectly placed as "1%s" and should be "%s" in the translation. Also, the period at the end was not present in the source and should be removed for consistency.  

Correct translation:  
דער צוגעגעבענער קאַנפיג־טעקסט %s עקזיסטירט נישט
```

```
        <source>The transaction amount is too small to pay the fee</source>
        <translation>דער טראַנזאַקשאַן בetrאָג איז צו קליין כדי צו באַצאָלן די פֿיס.</translation>
    
YES  
The transliteration "בetrאָג" mixes Latin and Hebrew scripts, which is inappropriate. It should be fully in Hebrew script. The correct Yiddish word for "amount" is "באַטראָג" or "סומע". Additionally, "פֿיס" (feet) is incorrect for "fee"; the correct term in financial context is "פֿע" (fee) or "אפֿשר "פֿי".

Correct translation:  
דער טראַנזאַקשאַן באַטրאָג איז צו קליין כדי צו באַצאָלן די פֿעי.
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>די וואַלטעוועט וועט אויסמאַכן נישט צאָלן פחות ווי דער מינימום פֿאַרבינדונג קאָסטן.</translation>
    
YES  
The translation contains some inaccuracies:  
- "וואַלטעוועט" mixes English and Yiddish-like elements and is not correct for "wallet" in Yiddish ('וואַלט' or 'פּאָרטל' would be better).  
- "אויסמאַכן" means "to settle" or "decide", not "will avoid". A better verb for "avoid" is "אויסהאַלטן" or "פארמיידן".  
- "פחות" is a Hebrew word meaning "less", but in Yiddish "קיניגער" or "ווייניקער" would be more appropriate.  
- "פֿאַרבינדונג קאָסטן" means "connection costs" rather than "relay fee". The correct term for relay fee should be closer to "רעלייַ פֿיס".  
- The sentence also has grammatical and word order issues.

Correct translation:  
די פּאָרטל וועט פאַרמיידן צו באַצאָלן ווייניקער ווי די מינימום רעלייַ פאָר.
```

```
        <source>This is experimental software.</source>
        <translation>דערהייַנטיק איז עקספּערימענטאַלע ווייכווארג.</translation>
    
YES  
The translation "דערהייַנטיק איז עקספּערימענטאַלע ווייכווארג." means "The current is experimental software," where "דערהייַנטיק" translates to "current" or "up-to-date," which does not accurately reflect "This." A better translation is:  
"דאָס איז עקספּערימענטאַל ווייכווארג."
```

```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>אַזוי איז דער טראַנסאַקשאַן פייַעך וואָס איר וועט צאָלן אויב איר שיקט אַ טראַנסאַקשאַן.</translation>
    
YES  
The word "פייַעך" is a transliteration of the English word "fee" but is not a standard or accurate Yiddish term. In Yiddish, "fee" is better translated as "פֿיי” or more appropriately "פֿיז" or "פֿי". Also, the sentence structure can be smoothed for better readability and correctness in Yiddish.

Correct translation:  
"דאָס איז דער טראַנסאַקשאַן־פֿיז וואָס איר וועט צאָלן אויב איר שיקט אַ טראַנסאַקשאַן."
```

```
        <source>Transaction %s does not belong to this wallet</source>
        <translation>טראַנסאַקטיאָן 1%s איז נישט פֿאַר די וואָלט</translation>
    
YES  
The translation has a formatting error: the source uses "%s" as a format specifier, but the translation uses "1%s", which is incorrect and will break formatting. Also, the phrase "איז נישט פֿאַר די וואָלט" ("is not for the wallet") is less precise than the source "does not belong to this wallet". A better phrasing would explicitly say it "does not belong to this wallet" (example: "טראנזאקציע %s גייט נישט צו דעם וואָלקעט").

Correct translation:  
טראַנסאַקציע %s גייט נישט צו דעם וואָלקעט
```

```
        <source>Transaction must have at least one recipient</source>
        <translation>א פּראָצעס מוז האָבן לפּחות איין רעציפּיענט.</translation>
    
YES  
The translation uses "א פּראָצעס" which means "a process" rather than "a transaction," which is contextually incorrect for Bitcoin terminology. Also, "רעציפּיענט" is a transliteration of "recipient" but not the common Yiddish word; a better term might be "א עמחל" (a recipient) or a more contextually accurate phrase. The original sentence means a Bitcoin transaction must have at least one recipient.

Correct translation:  
טראַנזאַקשאַן מוז האָבן לפּחות איין עמחל.
```

```
        <source>Unable to bind to %s on this computer (bind returned error %s)</source>
        <translation>ניט מעגלעך צו בינדן צו 1%s אויף דעם קאָמפּיוטער (בינדן האָט צוריקגעגעבן אַ גרייַז 1%s)</translation>
    
YES  
The translation incorrectly adds a leading "1" before the %s format specifiers, which alters the intended placeholder and breaks the format. Also, the word "גרייַז" means "error" but is a strange or uncommon spelling here; the correct Yiddish word for "error" is "אַרויספֿאַל" (failure) or "פֿעלער" (error). The translation should also avoid unnecessary insertions or typos.

Correct translation:  
ניט מעגלעך צו בינדן צו %s אויף דעם קאָמפּיוטער (בינדן האָט צוריקגעגעבן אַ פֿעלער %s)
```

```
        <source>Unable to bind to %s on this computer. %s is probably already running.</source>
        <translation>ניט מעגלעך צו בינדן צו 1%s אויף דעם קאָמפּיוטער. 1%s לויפט מסתּמא שוין.</translation>
    
YES  
The format specifiers are incorrect in the translation. Instead of "1%s", it should be "%s" to match the source placeholders exactly.

Correct translation:  
ניט מעגלעך צו בינדן צו %s אויף דעם קאָמפּיוטער. %s לויפט מסתּמא שוין.
```

```
        <source>Unable to create the PID file '%s': %s</source>
        <translation>נישט קאָנען שאַפֿן די PID טעקע '1%s': 1%s</translation>
    
YES  
The translation incorrectly adds the digit '1' before the format specifiers '%s', which does not exist in the source text and breaks the format specifiers. The correct translation should preserve the original format specifiers exactly without any added characters.

Correct translation:  
נישט קענען שאַפֿן די PID טעקע '%s': %s
```

```
        <source>Unable to generate initial keys</source>
        <translation>ניט אפשריק צו générירן אָרײַנקע לאַרגעלע</translation>
    
YES  
The translation contains non-Yiddish words and a mix of Latin and Hebrew scripts that is inappropriate. The word "générer" is French, and "אָרײַנקע לאַרגעלע" is incorrect Yiddish for "initial keys." Also, "ניט אפשריק" is incorrect; the correct form is "ניט מעגלעך" or "ניט מעגלעך צו."  

Correct translation:  
ניט מעגלעך צו לייגן אָרענטע שליסלען
```

```
        <source>Unable to open %s for writing</source>
        <translation>קענט ניט עפענען 1%s פֿאַר געשריבן</translation>
    
YES  
The format specifier `%s` is incorrectly written as `1%s` in the translation. It should be `%s` without the leading `1`. Also, the translation for the phrase "for writing" is more naturally represented as "צו שרייבן" rather than "פֿאַר געשריבן," which sounds unnatural or incorrect in Yiddish.

Correct translation:  
קענט ניט עפענען %s צו שרייבן
```

```
        <source>Unable to parse -maxuploadtarget: '%s'</source>
        <translation>קענט נישט פֿאַראַרבעטן -maxuploadtarget: '1%s'</translation>
    
YES
The translation incorrectly adds a '1' before the '%s' format specifier, changing the intended placeholder and causing a formatting error.

Correct translation:
קענט נישט פֿאַראַרבעטן -maxuploadtarget: '%s'
```

```
        <source>Unable to unload the wallet before migrating</source>
        <translation>נישט אפשר צו אויסלאָדן דעם וואַלעט ווען קודם פּונקטירן</translation>
    
YES  
The translation contains errors and awkward phrasing. The phrase "before migrating" is incorrectly translated as "ווען קודם פּונקטירן" ("when first puncturing/clicking"), which is not related to migration. Also, "נישט אפשר" is awkward; the more natural negation is "ניט אוממעגלעך" or "ניט מעגלעך". The word "וואלעט" (wallet) is correct.

Correct translation:  
**ניט מעגלעך אויסלאָדן דעם וואָלעט לפני מיגרירן**  
(or, more smoothly)  
**ניט מעגלעך אויסלאָדן דעם וואָלעט איידער מיגרירן**
```

```
        <source>Unknown -blockfilterindex value %s.</source>
        <translation>יידנט -בלאָקפֿילטער אינדעקס ווערט 1%s.</translation>
    
YES
The translation incorrectly adds the numeral "1" before the format specifier "%s" and mistranslates the word "Unknown." The English word "Unknown" should be translated appropriately to Yiddish (e.g., "אָונוועסט"), and the format specifier "%s" should appear exactly as in the source without any added characters.

Correct translation:
"אונבאַקאַנט -blockfilterindex ווערט %s."
```

```
        <source>Unknown address type '%s'</source>
        <translation>אומדעוקט אדרעס טיפּ '1%s'</translation>
    
YES  
The translation has a few issues:  
1. The English source has one format specifier '%s', but the translation has '1%s', which incorrectly adds a '1' prefix before the placeholder. The '1' should be removed to match the source.  
2. The translation "אומדעוקט" is not the correct word for "Unknown". The correct Yiddish word for "unknown" is "Unbekannt" (in Yiddish script: "אומבאַקאַנט" or transliterated "אונבאַקאַנט").  
3. The phrase "address type" should be translated correctly as "אדרעס טיפּ" is acceptable for "address type".  
4. The single quotes around '%s' in the source are correctly preserved.  

Correct translation:  
אונבאַקאַנט אדרעס טיפּ '%s'
```

```
        <source>Unknown change type '%s'</source>
        <translation>יידישע: אנבעלשערט טייפל פון ענדערונג '1%s'</translation>
    
YES  
The translation is problematic. The source phrase is "Unknown change type '%s'", where '%s' is a format specifier that must be preserved exactly in the translation. The provided translation incorrectly includes '1%s' instead of '%s'. Also, the phrase starts with "יידישע:" which means "Yiddish:" in the translation itself, which is unnecessary and incorrect in this context.

A better translation would be:  
"אונבעטראכט טיפּ פון ענדערונג '%s'"

(assuming "אונבעטראכט" = "unknown", "טיפּ פון ענדערונג" = "change type")

Final corrected translation:  
יידישע: אונבעטראכט טיפּ פון ענדערונג '%s'  
But without the "יידישע:" prefix, the proper translation is:  
אונבעטראכט טיפּ פון ענדערונג '%s'
```

```
        <source>Unknown network specified in -onlynet: '%s'</source>
        <translation>אומפֿרידן נעץ איז צוגעגעבן אין -onlynet: '1%s'</translation>
    
YES
The translation incorrectly adds a "1" before the %s format specifier ('1%s' instead of '%s'), which breaks the placeholder usage. Also, the Yiddish word for "Unknown" should be "אומבאַקאַנט" or a similar term, as "אומפֿרידן" means "unsatisfied," which is incorrect here.

Correct translation:
אומבאַקאַנט נעץ איז צוגעגעבן אין -onlynet: '%s'
```

```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>נישט באקאנטע נייע רשימות אַקטיווי (װערסיעביט 1%i)</translation>
    
YES
The format specifier %i is incorrect in the translation as "1%i" instead of "%i". Also, the phrase "רשימות" (lists) is incorrect for "rules" in this context; the correct term should be "רעגולעס" or "רולעס" (rules). The correct translation should maintain the wording for "Unknown new rules activated" and fix the format specifier:

Correct translation:
נישט באַקאַנטע נייַע רולעס אַקטיוואַטירט (װערסיעביט %i)
```

```
        <source>Unrecognised option "%s" provided in -test=&lt;option&gt;.</source>
        <translation>ניט דערקענט אָפּציע "1%s" צוגעשטעלט אין - פּרובירן=&lt;option&gt;.</translation>
    
YES  
The translation incorrectly adds a '1' before the format specifier %s ("1%s"), which is not present in the source and should be exactly "%s". Also, there is an extra space after the dash in "- פּרובירן", whereas the source has "-test=" with no space or word break. Moreover, the word "פּרובירן" literally means "test", which is correct, but it must be attached properly as "-test=" without space.  

Correct translation:  
ניט דערקענט אָפּציע "%s" צוגעשטעלט אין -test=&lt;option&gt;.
```

```
        <source>Unsupported global logging level %s=%s. Valid values: %s.</source>
        <translation>נישט געשטיצט גלאבאלע לאָגגינג מדרגה 1%s=1%s. גילטיקע ווערטן: 1%s.</translation>
    
YES
The translation incorrectly inserts the digit "1" before all format specifiers (%s), which is not present in the source and is erroneous. The format specifiers must be copied exactly as in the source.

Correct translation:
נישט געשטיצט גלאבאלע לאָגגינג מדרגה %s=%s. גילטיקע ווערטן: %s.
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>דער שאַפֿן וואָלעט טעקע איז פאַרפאַלן: 1%s</translation>
    
YES  
The translation mistakenly includes "1" before the format specifier "%s" and has order issues. The correct translation should properly place "%s" without an extraneous character and follow natural Yiddish syntax.  

Correct translation:  
דער שאַפֿן פון וואָלעט טעקע איז פאַרפאַלן: %s
```

```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>אַננעמען-שטערקייט-פֿאַרמעסטונגן איז נישט געשטיצט אויף %s קייט.</translation>
    
YES  
The translation inaccurately segments and translates "acceptstalefeeestimates." The source word is a single configuration option and should be transliterated or adapted as one term rather than broken into parts. Also, "%s chain" should be translated so that "chain" is clearly understood in the context of a blockchain network. The translated phrase "קייט" is an acceptable transliteration of "chain," but the first word should be kept as one unit to preserve meaning.

Correct translation:  
acceptstalefeeestimates איז נישט געשטיצט אויף %s קייט.
```

```
        <source>Unsupported logging category %s=%s.</source>
        <translation>נישט געשטיצט לאָגינג קאַטעגאָריע 1%s=1%s.</translation>
    
YES  
The translation incorrectly uses "1%s=1%s" instead of the format specifiers "%s=%s" as in the source. Also, the numbers "1" before "%s" are wrong. The correct translation should preserve the format specifiers exactly as in the source.

Correct translation:  
נישט געשטיצט לאָגינג קאַטעגאָריע %s=%s.
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>אַ טעות: קען נישט לייגען די וואָטשט-נאָר איבערגעשיקט 1%s אין דער וואָטשט-נאָר וואָלעט</translation>
    
YES
The translation incorrectly places the format specifier "%s" after the numeral "1", which is not in the original source and changes the meaning. The correct position and form of "%s" must be retained exactly as in the source.

Correct translation:
א פיילער: קען נישט לייגן watchonly טראַנסאקציע %s אין watchonly וואָלעט
```

```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>אנהייב: באַמערקונג פון באַניצער אַגענט (1%s) כּולל אומזיכערע אותיות.</translation>
    
YES
The source string contains the format specifier "%s", but in the translation it is rendered as "1%s", which is incorrect; the "1" should not be added. Also, the word "אנהייב:" means "beginning:" or "start:", which is not present in the source and is an erroneous addition.

Correct translation:
באַמערקונג פֿון באַניצער אַגענט (%s) כּולל אומזיכערע אותיות.
```

```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>די וואָלעט דאַרף ווערן איבערגעשריבן: פאַרהייב 1%s צו פאַרענדיקן</translation>
    
YES  
The format specifier "%s" is incorrectly changed to "1%s" in the translation. Also, "restart" is better translated as "ריסטאַרט" (a transliteration) or an appropriate Yiddish equivalent, whereas "פאַרהייב" means "raise" or "lift," which is incorrect here.  

Correct translation:  
די וואָלעט דאַרף ווערן איבערגעשריבן: ריסטאַרט %s צו פאַרענדיקן
```

```
        <source>Settings file could not be written</source>
        <translation>  די באַשטעטיקונגען טעקע קען נישט געשריבן ווערן</translation>
    
YES
There is an unnecessary leading whitespace in the translation before the text "די". Also, the phrase can be made more natural in Yiddish by adjusting word order.

Correct translation:
די באַשטעטיקונגען טעקע קען נישט געשריבן ווערן
```
</details>
