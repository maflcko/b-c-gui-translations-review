# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>yi</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Byi%5D%20low%20quality)


```
        <source>Create a new address</source>
        <translation>רעכט-קנעפּל דריקט צו רעדאַקטירן אַדרעס אָדער לייבל</translation>
    
YES
The translation is incorrect. The given 'yi' translation means "Right-click to edit address or label," which does not correspond to "Create a new address."

Correct translation:
שאַפֿן אַ נייַע אַדרעס
```

```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>די זענען אייער ביטקאָין־אַדרעסן פֿאַר באקומען צאָלונגען. ניצט דעם קנעפּל „שאַפֿן אַ נײַע באקומען־אַדרעס“ 
אין די „באקומען“־טעב, צו שאַפֿן נײַעאַדרעסן.אונterschרייבן איז בלויז מעגלעך מיט אַדרעסן פון דעם טיפּ „לעגאַסי“.</translation>
    
YES
There are several issues with the Yiddish translation:
- "נײַעאַדרעסן" is missing a space: it should be "נײַע אַדרעסן".
- Linebreak or unnecessary spacing in the middle of a sentence ("ניצט דעם קנעפּל „שאַפֿן אַ נײַע באקומען־אַדרעס“ \nאין די „באקומען“־טעב, צו שאַפֿן נײַעאַדרעסן").
- Code-mixed word: "אונterschרייבן" is German/Yiddish code-mixing; the correct Yiddish is "אונterschרייבן" (with a Yiddish spelling "אונטערשרייבן").
- There is a missing comma: "צו שאַפֿן נײַעאַדרעסן.אונterschרייבן..." needs a space or a new sentence after the period.
- Consistency: Use spaces between words properly and apply a period or new sentence at the right place.

Correct translation:
די זענען אייערע ביטקאָין־אַדרעסן פֿאַר באקומען צאָלונגען. ניצט דעם קנעפּל „שאַפֿן אַ נײַע באקומען־אַדרעס“ אין דער „באקומען“־טעב צו שאַפֿן נײַע אַדרעסן. אונטערשרייבן איז בלויז מעגלעך מיט אַדרעסן פון טיפּ „לעגאַסי“.
```

```
        <source>Exporting Failed</source>
        <translation>אכסניות פֿעלד</translation>
    
YES
The translation "אכסניות פֿעלד" is incorrect. "אכסניות" means "hostels" or "inns," which is not related to "Exporting," and "פֿעלד" means "field." This is an erroneous translation.

Correct translation:
אויספיר איז ניט געלונגען

Explanation: "אויספיר" (export) and "איז ניט געלונגען" (failed/not successful) together accurately convey "Exporting Failed" in Yiddish.
```

```
        <source>Encrypt wallet</source>
        <translation>ארויפשטעלן וואַלטל</translation>
    
YES  
The translation is incorrect. "ארויפשטעלן וואַלטל" translates to "set up wallet" in Yiddish, not "encrypt wallet". The correct translation for "Encrypt wallet" in Yiddish should be:  

קאָדירן דעם וואָלט

Correct translation:
קאָדירן דעם וואָלט
```

```
        <source>Confirm wallet encryption</source>
        <translation>אָפּלייקענען וואָלעט ענקריפּשאַן</translation>
    
YES
The Yiddish translation "אָפּלייקענען וואָלעט ענקריפּשאַן" means "Deny wallet encryption" or "Reject wallet encryption," which is incorrect. The source says "Confirm wallet encryption," so the translation should use a word meaning "confirm" or "approve," not "deny."

Correct translation:
באַשטעטיק וואָלעט ענקריפּשאַן
```

```
        <source>Wallet encrypted</source>
        <translation>בייַטל ינקריפּטיד</translation>
    
YES
The translation is problematic. The word "ינקריפּטיד" is a transliteration of "encrypted" instead of a proper Yiddish translation. Additionally, "בייַטל" is an informal term for wallet; a more accurate term would be "וועלט". The correct translation would be:

וואַלעט איז ענקריפּטירט

Or, if "בייַטל" is desired for informal contexts:

בייַטל איז ענקריפּטירט

But "ינקריפּטיד" is incorrect; use "ענקריפּטירט". 

Correct translation:
בייַטל איז ענקריפּטירט
```

```
        <source>Wallet encryption failed</source>
        <translation>בייטל ענקריפּשאַן ניט אַנדערש</translation>
    
YES
The Yiddish translation is incorrect. The word "ניט אַנדערש" literally means "not different", which is not an accurate translation of "failed". Also, "בייטל" is a Yiddishization of "wallet" but the spelling and rendering should be closer to Yiddish standards. The proper word for "encryption" is "ענקריפּציע" or similar.

Correct translation:
ענקריפּציע פֿון וואָלעט איז דורכגעפֿאַלן
```

```
        <source>Wallet unlock failed</source>
        <translation>אַנלאַקינג די בייַטל איז ניט אַנדערש</translation>
    
YES
The translation is problematic. The phrase "אַנלאַקינג די בייַטל איז ניט אַנדערש" is ungrammatical and inaccurate. "אַנדערש" means "different/otherwise" rather than "successful." 

Correct translation:
די בייַטל קען נישט ווערן אויפגעשלעסן
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>סעטטינגס טעקע %1  קען זיין פאַרדאָרבןאָדער פאַרקריפּלט.</translation>
    
YES
There are minor issues in the translation:
- "סעטטינגס טעקע" is a transliteration of "settings file" and is acceptable, but could be improved for clarity (for example, "איינסטעלונגן טעקע").
- There is no space between "פאַרדאָרבן" and "אָדער".
- "פאַרקריפּלט" is a possible translation for "invalid," but "אומגילטיק" would be more standard.

Correct translation:
סעטטינגס טעקע %1 קען זיין פאַרדאָרבן אָדער אומגילטיק.

Or, with slightly more native phrasing:
די איינסטעלונגן טעקע %1 קען זיין פאַרדאָרבן אָדער אומגילטיק.
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>א אינערלעכער טעות איז פארגעקומען.  %1וועט פּרווון צו פאָרזעצן בעשאָלעם. דאָס איז אַן אומגעריכט זשוק וואָס קענען זיין רעפּאָרטעד ווי דיסקרייבד אונטן.</translation>
    
YES
There are a few issues:
- There is an extra space between the period and "%1" ("... טעות איז פארגעקומען.  %1וועט ...").
- "%1וועט" is missing a space: it should be "%1 וועט".
- "זשוק" is a transliteration of "bug" and isn't the ideal Yiddish term; "גרייהער", "פעלער", or "טעות" would be preferable. However, "זשוק" is sometimes used informally.
- "רעפּאָרטעד ווי דיסקרייבד אונטן" is mostly English in transliteration. Prefer idiomatic Yiddish: "וואָס מע קען מעלדן ווי באַשריבן אונטן."
- The overall translation sticks too closely to English syntax and vocabulary.

Correct translation:
א אינערלעכער טעות איז פארגעקומען. %1 וועט פּרוּוון פאָרזעצן בעשאָלעם. דאָס איז אַן אומגעריכט פעלער וועלכער מע קען מעלדן ווי באַשריבן אונטן.
```

```
        <source>Do you want to reset settings to default values, or to abort without making changes?</source>
        <extracomment>Explanatory text shown on startup when the settings file cannot be read. Prompts user to make a choice between resetting or aborting.</extracomment>
        <translation>צי איר ווילן צו באַשטעטיק סעטטינגס צו פעליקייַט וואַלועס אָדער אַבאָרט אָן ענדערונגען?</translation>
    
YES
There is an error in the Yiddish translation: "באַשטעטיק" means "confirm" rather than "reset" and the overall phrase structure and some transliterations are awkward. Also, "settings" and "default values" are not naturally rendered in Yiddish, and should be adapted.

Correct translation:
צי וויל איר צוריקזעצן די אַפּ-סעטטינגס צו די פעליקטע ווערט, אָדער אפשטעלן אָן קיין ענדערונגען?
```

```
        <source>Exit</source>
        <translation>עxit</translation>
    
YES  
The translation "עxit" is problematic because it mixes Hebrew script with the Latin "x", which is incorrect for Yiddish. The correct Yiddish translation should be entirely in Hebrew script, using the proper Yiddish term for "Exit".

Correct translation:
אַרויס  
or  
פֿאַרלאָזן (depending on context; "אַרויס" is most common for UI "Exit" buttons)
```

```
        <source>Exporting Failed</source>
        <translation>אכסניות פֿעלד</translation>
    
YES
The translation "אכסניות פֿעלד" is incorrect. "אכסניות" means "hostels" or "inns," which is not related to "Exporting," and "פֿעלד" means "field." This is an erroneous translation.

Correct translation:
אויספיר איז ניט געלונגען

Explanation: "אויספיר" (export) and "איז ניט געלונגען" (failed/not successful) together accurately convey "Exporting Failed" in Yiddish.
```

```
        <source>Unrecognized descriptor found. Loading wallet %s

The wallet might had been created on a newer version.
Please try running the latest software version.
</source>
        <translation>אונטערגעריפענע דעזקריפּטאָר געפונען. לאודינג וואָלעט 1%s דער וואָלעט קען געווען געמאכט אויף אַן נײַער ווערסיע. ביטע פּרוּוון אראפקומען דעם לעצטן סאָפטווער ווערסיע.</translation>
    
YES  
There are several issues with this translation:

1. "לאודינג וואָלעט 1%s" should be "לאד איבער די בייַטל %s" or similar, and '%s' should not have '1' before it.  
2. The translation for "Unrecognized descriptor found." ("אונטערגעריפענע דעזקריפּטאָר געפונען") uses a German/Yiddish hybrid; "אונטערגעריפענע" is clumsy and not idiomatic.  
3. "The wallet might had been created on a newer version." is missing in translated content, and the existing translation doesn't convey the same conditional meaning.
4. "Please try running the latest software version." is mistranslated; "אראפקומען" is incorrect for "run," it means "download."  
5. English words like "loading wallet" are used as transliterated words ("לאודינג"), which is not standard or idiomatic for Yiddish UI translations.

Correct translation:
געפֿונען אַ נישט ערקענטער דיסקריפּטאָר. לאָדן בייַטל %s.

דער בייַטל איז מסתּמא באַשאַפן געוואָרן אויף אַ נײַער ווערסיע.
ביטע פּרוּווט אויסצופירן די לעצטע ווייכווארג-ווערסיע.
```

```
        <source>
Unable to cleanup failed migration</source>
        <translation>נישט אפשר צו רייניקן אויוולע געדריט</translation>
    
YES
The translation "נישט אפשר צו רייניקן אויוולע געדריט" is problematic for the following reasons:
- "אויוולע געדריט" appears to be a mistranslation or nonsensical for "failed migration"; "אויוולע" means 'evil' or 'wicked', and "געדריט" is not an apt term for 'migration' in this context.
- The English phrase refers to a technical operation: "Unable to cleanup failed migration". "Migration" here typically refers to data or software migration, not something "evil".

Correct translation:
קענעט נישט רייניקן אן דורכגעפאלענע מאַיגראַציע

Alternatively:
ניטאָ מעגליכקייט צו רייניקן א דורכגעפאלענע מיגראַציע

Either of the above would be much more appropriate.
```

```
        <source>A fatal internal error occurred, see debug.log for details: </source>
        <translation>אויבערלעכער אינערלעכער אסקאָרגעס איז אריינגעקומען, זוך די debug.log פאר דעטאלן:</translation>
    
YES
There are multiple errors in the translation:

1. "אויבערלעכער אינערלעכער אסקאָרגעס איז אריינגעקומען" is an awkward and incorrect rendering of "A fatal internal error occurred."
   - "אויבערלעכער" is not the standard term for "fatal" (the more accepted Yiddish term is "פאַטאַל" or "הארבע").
   - "אסקאָרגעס" does not correspond to "error"; a better word would be "טעות" or "פעלער".
   - "איז אריינגעקומען" ("has entered/arrived") is not idiomatic; use "איז פארגעקומען" or "האט פאסירט".
2. "זוך די debug.log פאר דעטאלן" should be "קוק אין debug.log פאר דעטאלן" ("see the debug.log for details").
3. There is an unnecessary colon at the end, which matches the source, but is awkward in Yiddish sentence flow.

Correct translation:
א internal error occurred, see debug.log for details.

But to render this accurately in Yiddish:
א שווערער אינערלעכער טעות איז פארגעfallen, קוק אין debug.log פאר דעטאלן.

Or, more idiomatic:
א פאַטאַלער אינערלעכער טעות איז פאסירט, קוק אין debug.log פאר דעטאלן.

So:

YES
The translation is awkward and incorrect Yiddish. "אויבערלעכער אינערלעכער אסקאָרגעס איז אריינגעקומען" does not correctly convey "A fatal internal error occurred." Prefer:

א פאַטאַלער אינערלעכער טעות איז פאסירט, קוק אין debug.log פאר דעטאלן.
```

```
        <source>Assumeutxo data not found for the given blockhash '%s'.</source>
        <translation>עס איז נישט געפונען אראפגעגעבן דאטן פאר דעם געגעבן בלאָק-האשט '1%s'.</translation>
    
YES
The translation introduces an error: it has '1%s' instead of '%s', which changes the format specifier and will cause runtime issues. Additionally, "אראפגעגעבן דאטן" is a literal translation, but the standard phrasing in Yiddish for "the given data" is more accurately "די געגעבן דאטן".

Correct translation:
עס איז נישט געפונען די Assumeutxo-דאַטן פֿאַר דעם געגעבן בלאָק-האַש '%s'.
```

```
        <source>Block verification was interrupted</source>
        <translation>די באַשטעטיקונג פון בלאָק איז פֿאַרעפֿנטיקט געוואָרן</translation>
    
YES
The translation is inaccurate. The Yiddish phrase "די באַשטעטיקונג פון בלאָק איז פֿאַרעפֿנטיקט געוואָרן" translates back as "The confirmation of block has been published", which does not convey the intended meaning of "verification was interrupted". Also, "באַשטעטיקונג" means "confirmation", but here we want "verification". "פֿאַרעפֿנטיקט געוואָרן" means "was published", which is incorrect.

Correct translation:
די וואָלידאַציע פונעם בלאָק איז אונטערבראָכן געוואָרן
```

```
        <source>Config setting for %s only applied on %s network when in [%s] section.</source>
        <translation>קאַנפיג אָטאַמאַטיש פֿאַר 1%s איז בלויז פֿאַראַנען אויף 1%s נעץ ווען אין [1%s] אָפּטייל.</translation>
    
YES
The translation is problematic for several reasons:
1. The format specifier %s in the source is incorrectly handled as 1%s and 1%s and [1%s] in the translation. The 1 should not be present.
2. The Yiddish wording is awkward and partially inaccurate: 
   - "קאַנפיג אָטאַמאַטיש" is not a correct translation for "Config setting".
   - "פאראַנען" (available) doesn't correspond to "applied".
   - "נץ" should be "נעץ" for "network", but overall the sentence is confusing.
   - The translation does not clearly convey the conditional relationship ("only applied on X network when in [Y] section") as the English source does.

Correct translation:
קאַנפֿיגוראַציע באַשטימט פֿאַר %s ווערט בלויז אָנגעווענדט אויף %s נעץ ווען עס איז אין [%s] אָפּטייל.
```

```
        <source>Copyright (C) %i-%i</source>
        <translation>קויפירייט (C) 1%i - 1%i</translation>
    
YES
The translation is incorrect. The format specifiers %i in the source should remain unchanged in the translation. The translation wrongly introduces '1%i' instead of merely '%i', duplicating the '1' which does not exist in the source format specifier.

Correct translation:
קאפירייט (C) %i-%i
```

```
        <source>Corrupt block found indicating potential hardware failure.</source>
        <translation>איבערשפיגלטע בלאָק געפֿונען וואָס דועט אויף אַ מעגלעך האַרדווער עמעצער</translation>
    
YES  
The translation is problematic. The Yiddish word "איבערשפיגלטע" means "reflected" and is incorrect for "corrupt". Also, "האַרדווער עמעצער" translates as "hardware somebody", which is nonsensical. The correct translation should use a word like "פאַראבראָכענע" for "corrupt" and "שטעל" or "פייל" for "failure". 

Correct translation:  
פאַראבראָכענע בלאָק געפֿונען וואָס קען ווייזן אויף אַ מעגלעכע האַרדווער טעות.
```

```
        <source>Corrupted block database detected</source>
        <translation>יָאָרע בלאק דאַטאַבאַסע געפונען</translation>
    
YES
The translation is inaccurate. The Yiddish phrase "יָאָרע בלאק דאַטאַבאַסע געפונען" translates roughly as "corrupted block database found," but "יָאָרע" (with the diacritic) may be a typographical error or not the standard way to say "corrupted" in this context. Also, "דאַטאַבאַסע" is a transliteration of "database," which is acceptable, but the translation should be more technically standard.

Correct translation:
קוראָפּטירטע בלאָק-דאַטאַבייס געפונען

Alternatively (more concise Yiddish spelling):
אייטן אַ קאָרופטירטן בלאַק־דאַטאַבייס

But the most accepted form:
קוראָפּטירטע בלאָק־דאַטאַבייס געפֿונען
```

```
        <source>Could not find asmap file %s</source>
        <translation>נישט געמאַכט געפֿינען אַסמאַפּ אַרכיוו 1%s</translation>
    
YES
The translation has several issues:
1. "1%s" is an incorrect format specifier; it should be "%s", as in the source.
2. The Yiddish wording is awkward and partially incorrect. "נישט געמאַכט געפֿינען" is not idiomatic for "Could not find", and "אַרכיוו" means "archive", which is not the intended meaning here; "טעקע" (file) is more precise.

Correct translation:
קענען נישט געפֿינען אַסמאַפּ טעקע %s
```

```
        <source>Could not parse asmap file %s</source>
        <translation>קען ניט פֿאַראַרבעטן די asmap טעקע 1%s</translation>
    
YES
The translation contains an error: it incorrectly includes "1%s" instead of the required format specifier "%s" alone (the digit '1' is extraneous), which could cause display or runtime problems. The translation is otherwise understandable in Yiddish.

Correct translation:
קען ניט פֿאַראַרבעטן די asmap טעקע %s
```

```
        <source>Done loading</source>
        <translation>יאָש, אויסגעלעצט</translation>
    
YES
The translation uses "יאָש", which is slang in Yiddish meaning "great" or "done!", and "אויסגעלעצט" which is an incorrect or misspelled word; likely a confusion with "אויסגעלאָדן" (loaded/finished loading) or "אויסגעלאָדעט". The translation is also too casual, and "יאָש" is colloquial and not appropriate for UI.

Correct translation:
פערטיק געלאָדן
or
אויסגעלאָדן

Therefore:

YES
The phrase is mistranslated. Use "פערטיק געלאָדן" or "אויסגעלאָדן" for correct, professional Yiddish.
```

```
        <source>Dump file %s does not exist.</source>
        <translation>די טשיפּ אַרכיוו 1%s עסט נישט.</translation>
    
YES  
The translation is problematic for several reasons:
1. The source string refers to a 'dump file', but the translation uses "די טשיפּ אַרכיוו", which means something like "the chip archive" and is incorrect. 'אַרכיוו' means 'archive', not 'file'.  
2. The variable %s must remain unchanged and is replaced as '1%s' (with a mistyped '1' and misplaced position).
3. The verb form "עסט נישט" is an incorrect rendering and not idiomatic-- "עקסיסטירט נישט" or "עקזיסטירט נישט" is correct in Yiddish for "does not exist".  

Correct translation:  
די דאַמפּ טעקע %s עקזיסטירט נישט.
```

```
        <source>Elliptic curve cryptography sanity check failure. %s is shutting down.</source>
        <translation>עליפטישער קרויִז קריפּטאָגראַפֿיע סאַנטי טשעק פעלער. 1%s איז שפּאַשנדיק אאָפֿן.</translation>
    
YES
There are several issues in the Yiddish translation:

1. "עליפטישער קרויִז קריפּטאָגראַפֿיע" is a word-for-word transliteration and not a natural way to say "Elliptic curve cryptography" in Yiddish. While Yiddish often incorporates Hebrew or German terms for technical concepts, it’s better to use terminology that's either widely understood or at least adapts to standard loanword practices.

2. The phrase "סאַנטי טשעק פעלער" is awkward — it’s a transliteration of "sanity check failure" but may not be understood by a Yiddish reader. "פעלער" (error/failure) is acceptable, but "סאַנטי טשעק" is unnatural.

3. The format specifier was mistyped as "1%s" instead of "%s".

4. "איז שפּאַשנדיק אאָפֿן" appears to transliterate "is shutting down" incorrectly (and "אאָפֿן" is a typo).

Correct translation:
עליפּטישע קריוו קריפּטאָגראַפֿיע קאָנטראָל פעלער. %s גייט זיך אויסמאַכן.

Or, using fully loaned terms if no better Yiddish equivalent exists:
עליפּטישע קריוו קריפּטאָגראַפֿיע קאָנטראָל פעלער. %s וועט זיך אויסשליסן.

Either is more natural Yiddish, rectifies the format specifier, and avoids unnecessary transliteration.
```

```
        <source>Error creating %s</source>
        <translation>אור מיט שאפן 1%s</translation>
    
YES
The translation is incorrect. The Yiddish translation "אור מיט שאפן 1%s" is not accurate, and "1%s" is a mistake (the format specifier is "%s" in the source, but it appears as "1%s" in the translation, which is erroneous). The correct Yiddish word for "Error" is "טעות" or "גרײַבן" (mistake/error), and the phrase should read along the lines of "טעות בײַם שאפן %s".

Correct translation:
טעות בײַם שאפן %s
```

```
        <source>Error initializing wallet database environment %s!</source>
        <translation>עראר בײַ איניציאליזירן דעם וואַלט דאַטאַבאַסע אויסשטעלונג 1%s!</translation>
    
YES
The translation is mostly accurate but has an error:
- The format specifier '%s' from the source was changed to '1%s', which is incorrect.
- 'אויסשטעלונג' is not a standard translation for 'environment'; a better term is 'סביבה' or 'אַרומע' (context-dependent).
- The rest of the sentence is understandable Yiddish, though 'דעם וואַלט דאַטאַבאַסע סביבה' is more accurate.

Correct translation:
עראַר בײַ איניציאַליזירן דעם וואַלט דאַטאַבאַסע סביבה %s!
```

```
        <source>Error loading %s</source>
        <translation>ערראָר לאָאַדינג 1%s</translation>
    
YES
The translation contains a typo and an erroneous prefix ("1%s" instead of "%s"). Also, "לאָאַדינג" is a transliteration and should ideally be translated properly into Yiddish. The word "ערראָר" is also just transliterated "error"; depending on idiomatic usage, "טעות" or "פֿעלער" (for "error") would be better.

Correct translation:
פֿעלער בײַם לאָדענען %s
```

```
        <source>Error loading %s: Private keys can only be disabled during creation</source>
        <translation>גרייַזונג לאָדן 1%s: פּריוואַטע שליסלען קענען נאָר ווערן דיסאַבלירט בזמן שלאַפֿן</translation>
    
YES
There are multiple issues in this Yiddish translation:
1. "גרייַזונג" is not a correct or common word for "Error"; the standard is "טעות" or "פעלער".
2. "1%s" is a format specifier mistake; the English uses "%s", not "1%s".
3. "בזמן שלאַפֿן" ("during sleep") is erroneous and nonsensical here. The correct phrase should be "נאָר בזמן שאַפֿן" ("only during creation").

Correct translation:
פֿעלער בעת לאָדן %s: פּריוואַטע שליסלען קענען נאָר ווערן אויסגעשאַלט בעת שאַפֿן
```

```
        <source>Error loading %s: Wallet corrupted</source>
        <translation>Ошибка לאָדן 1%s: װאַלעט קראָופּטעד</translation>
    
YES
The translation is problematic for several reasons:
- It mixes Russian ("Ошибка" means "Error") with Yiddish. The translation should be fully in Yiddish.
- The format specifier is incorrectly written as "1%s" instead of "%s".
- "Wallet corrupted" is transliterated (קראָופּטעד) not translated, which is not ideal.

Correct translation:
טעות בײַם לאָדן %s: בייַטל איז פארשליסן

Explanation:
- "טעות בײַם לאָדן" means "Error loading".
- "%s" is preserved as in the source.
- "בייַטל איז פארשליסן" means "wallet is corrupted".
```

```
        <source>Error loading %s: Wallet requires newer version of %s</source>
        <translation>טעות אין לאָאַדינג 1%s: וואָלאַט דאַרף אַ נײַער ווערסיע פון 1%s</translation>
    
YES
There are two issues:
1. The format specifiers have been incorrectly rendered as '1%s' instead of '%s', which could cause runtime errors.
2. The use of 'טעות' is an acceptable translation for 'Error', and 'וואָלאַט' for 'Wallet' is fine, but 'לאָאַדינג' is a Yiddishized English word—while often used for technical software UI, more idiomatic Yiddish would use something like 'אַרײַנלאָדן'. However, usage of such transliterations is common in digital contexts, so it's borderline, but still acceptable.

Correct translation:
טעות בײַם לאָדן %s: די וואָלעט דאַרף אַ נייער ווערסיע פֿון %s

- Fixed the format specifiers from '1%s' to '%s'
- Adjusted word order and spelling for natural Yiddish flow
```

```
        <source>Error loading block database</source>
        <translation>Ошибка בעת טעילונג פון בלאָק דאַטאַבייס</translation>
    
YES
The translation is problematic for two reasons:
1. It incorrectly mixes Russian ("Ошибка" means "Error" in Russian) with Yiddish, which is inappropriate.
2. The rest of the translation is a transliterated Yiddish version for "Error loading block database", but it contains some non-standard phrasing and inconsistent word choice.

Correct translation:
טעות בעת לאָדן די בלאָק דאַטאַבייס

Explanation:
- Remove the Russian word "Ошибка" and use "טעות" or "Fehler" (German Yiddish variant) for "Error".
- "בעת לאָדן" appropriately means "while loading".
- "די בלאָק דאַטאַבייס" refers to "the block database".
```

```
        <source>Error reading configuration file: %s</source>
        <translation>יֶתֶר שְׁגוּת בַּקרִיאָה של קובץ ההגדרות: 1%s</translation>
    
YES
The translation is problematic for several reasons:
1. The translation is a mixture of Yiddish and Hebrew, with words and diacritics that are not typical of proper Yiddish orthography (e.g., "יֶתֶר שְׁגוּת בַּקרִיאָה" uses modern Hebrew spelling and vowels).
2. "1%s" is incorrect usage of the format specifier; it should remain as "%s" as in the original.
3. The word "יתר" (yetér) means "surplus" or "extra" in Hebrew, which is unrelated. The phrase is not an accurate translation of "Error reading configuration file: %s". 
4. The phrase "של קובץ ההגדרות" is also modern Hebrew, not Yiddish.

Correct translation:
שָׁטֶע בעת דעם לייענען פֿון דער קאָנפֿיגוראַציע־טעקע: %s

Or, using standard Yiddish orthography:
טעות ביים לייענען פון דער קאנוּפיגוראַציע טעקע: %s

Either version is more accurate Yiddish.
```

```
        <source>Error: Disk space is low for %s</source>
        <translation>גרייַז: דיסק פּלאַץ איז נידעריק פֿאַר 1%s</translation>
    
YES
There are two issues:
1. The number '1' appears before %s, which should not be present. The correct translation should reproduce the format specifier %s exactly as in the source, with no stray characters.
2. The Yiddish word for "Error" is more commonly "טעות" or "פעלער" rather than "גרייַז" (which is an uncommon or possibly erroneous transliteration).

Correct translation:
פעלער: דיסק פלאץ איז נידעריק פֿאַר %s
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>טעות: דער טשעקזאַם פון דעם דאטעי איז נישט גלייך. רעכנט 1%s, ערווארטעט 1%s</translation>
    
YES
There are two issues in the translation:
1. The format specifiers "%s" were incorrectly replaced with "1%s", which is wrong and may break format substitution.
2. The translation is not fully accurate: "דאטעי" is a literal Yiddishization of "file" but is uncommon; "טעקע" is the proper term for "file" in Yiddish. Additionally, the error message's structure could be closer to the English source. 

Correct translation:
טעות: דער טשעקזאַם פֿון דער טעקע שטימט נישט. באמערקט %s, ערווארטעט %s
```

```
        <source>Error: Got key that was not hex: %s</source>
        <translation> טעות: באקומען אַ שליסל וואָס איז נישט העקס: 1%s</translation>
    
YES
There are a few issues:
1. The format specifier "%s" in the source text must be preserved as "%s" in the translation, but here it appears as "1%s", adding an extra "1", which is incorrect.
2. There is an unwanted leading space at the beginning of the translation.
3. The rest of the translation appears accurate.

Correct translation:
טעות: באקומען אַ שליסל וואָס איז נישט העקס: %s
```

```
        <source>Error: Got value that was not hex: %s</source>
        <translation>טעות: באקומען אַ ווערט וואָס איז נישט העקס: 1%s</translation>
    
YES
There are two issues with this translation:

1. The format specifier '%s' was incorrectly replaced with '1%s', which is erroneous.
2. Otherwise, the translation is mostly accurate, but should use the correct specifier.

Correct translation:
טעות: באקומען אַ ווערט וואָס איז נישט העקס: %s
```

```
        <source>Error: No %s addresses available.</source>
        <translation>טע mistake: קיין 1%s אַדרעסן ניט פארfügbar.</translation>
    
YES
The translation is problematic for the following reasons:
- The Yiddish word "טע mistake" incorrectly mixes Yiddish ("טע") and English ("mistake"). Only one is needed: "טע" alone means "error" or "mistake."
- The format specifier order is wrong: "1%s" instead of "%s".
- The phrase "ניט פארfügbar" mixes Yiddish ("ניט") and German ("פארfügbar" = "verfügbar"). The correct Yiddish would use "נישט בנימצא" or "נישט פארהאן" for "not available".
- Unnecessary space after "טע".
- There should be no double space.

Correct translation:
טע: קיין %s אַדרעסן זענען נישט פארהאן.
```

```
        <source>Error: database transaction cannot be executed for wallet %s</source>
        <translation>טעות: די דאטאבאזע טראַנזאַקשאַן קען נישט דורכגעפֿירט ווערן פֿאַר וואַלעט 1%s</translation>
    
YES
The translation contains an error: there is an unnecessary "1" before the %s format specifier, changing it to "1%s", which does not match the source.

Correct translation:
טעות: די דאטאבאזע טראַנזאַקשאַן קען נישט דורכגעפֿירט ווערן פֿאַר וואַלעט %s
```

```
        <source>Failed to connect best block (%s).</source>
        <translation>ניט הצלחה צו פאַרבינדן דעם בעסטן בלאָק (1%s).</translation>
    
YES
The translation incorrectly includes "1" before %s in the parentheses, which is not present in the original. Also, "ניט הצלחה צו פאַרבינדן" is a literal and somewhat awkward way to say "Failed to connect". A more natural Yiddish translation would be "מע האָט זיך נישט געקאָנט פֿאַרבינדן מיטן בעסטן בלאָק (%s)."

Correct translation:
מע האָט זיך נישט געקאָנט פֿאַרבינדן מיטן בעסטן בלאָק (%s).
```

```
        <source>Failed to disconnect block.</source>
        <translation>פֿאַרפאַלן צונויפֿרובֿן בלאָק</translation>
    
YES
The Yiddish translation is incorrect. The word "צונויפֿרובֿן" means "to assemble" or "to put together," which is the opposite of "disconnect." The correct verb for "disconnect" should be "אָפּטרענען" (optrenen). Also, "פֿאַרפאַלן" is a direct transliteration of "failed," but the correct way to say "Failed to disconnect block" would be to use a phrase like "איז נישט געלונגען אָפּצוטרענען דעם בלאָק" (it was not successful to disconnect the block), which is idiomatic in Yiddish.

Correct translation:
נישט געלונגען אָפּצוטרענען דעם בלאָק
```

```
        <source>Failed to read block.</source>
        <translation>יאָר נישט קריגן בלאָק</translation>
    
YES  
The Yiddish translation is incorrect. "יאָר נישט קריגן בלאָק" literally means "Year not get block," which is not a correct or idiomatic rendering of "Failed to read block." Additionally, the translation does not convey the failure to read or access the block.

Correct translation:
קאַנען נישט לייענען דעם בלאָק

Explanation: "קאַנען נישט לייענען דעם בלאָק" directly translates to "Cannot read the block," which is suitable for the context of a block reading failure in software.
```

```
        <source>Failed to verify database</source>
        <translation>פֿעלן צו פאַראַוואָרטן די דאַטאַבאַזע</translation>
    
YES
The translation is incorrect. The Yiddish phrase "פֿעלן צו פאַראַוואָרטן די דאַטאַבאַזע" literally means "to be missing to maintain the database," which is not a correct or idiomatic translation for "Failed to verify database." It also confuses "verify" with "maintain." The correct translation should accurately reflect "verify" as "פֿאַריפֿן" (to verify or check).

Correct translation:
ניט אַנדערע טאָן די דאַטאַבאַזע
or 
פֿאַרפעַלן אָפּצופּרווון די דאַטאַבאַזע

A more natural translation:
אַפּרווון פון דער דאַטאַבאַזע איז ניט געלונגען

Alternative:
ס׳איז ניט געלונגען אָפּצופּרווון די דאַטאַבאַזע
```

```
        <source>Failure removing transaction: %s</source>
        <translation>פאלשיקייט אויבן ארויף די טראַנסאַקשאַן: 1%s</translation>
    
YES
The translation is problematic for the following reasons:
- "פאלשיקייט אויבן ארויף די טראַנסאַקשאַן" is not a natural or accurate rendering of "Failure removing transaction" in Yiddish. "פאלשיקייט" is not standard Yiddish for "failure", and "אויבן ארויף" ("up above") makes no sense in this context.
- The format specifier is changed from %s to 1%s, which is incorrect.
- The wording does not sound idiomatic or correct for the Bitcoin context.

Correct translation:
פעלער בײַם אַוועקנעמען טראַנסאַקשאַן: %s
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>פֿיע-ראַטע (1%s) איז נידעריקער ווי די מינימום-פֿיע-ראַטע באַשטעטיקן (1%s)</translation>
    
YES
The translation has two main issues:
1. The format specifier '%s' from the source is incorrectly rendered as '1%s' in both instances, which is an error.
2. The Yiddish for "fee rate" should be written as "פֿי־ראַטע" (with a makaf/dash; though some variation exists), and "setting" is better translated as "אײַנשטעלונג" or "אַרײַנשטעלונג", rather than "באַשטעטיקן" which means "to confirm".

Correct translation:
פֿי־ראַטע (%s) איז נידעריקער ווי די מינימום־פֿי־ראַטע אײַנשטעלונג (%s)
```

```
        <source>Ignoring duplicate -wallet %s.</source>
        <translation>ניט באַמערקן דופליקאַט -וואָלעט 1%s.</translation>
    
YES
The translation incorrectly adds "1" before the %s specifier ("-וואָלעט 1%s"), which is not present in the source. Also, the phrase "ניט באַמערקן" is not a natural way to say "Ignoring" in Yiddish; "אויסגעלאָזן" or "איבערגיין" would be more appropriate. 

Correct translation:
אויסגעלאָזן דופליקאַט -וואָלעט %s.
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>נאכאמלק נישט קיין גענעזיס בלאָק געפֿונען, אָדער נישט קיין געלעגנהייט. פֿאַרוואָן דאטע-דירעקטאָריע פֿאַר נעץ?</translation>
    
YES
The translation contains errors and awkward wording. Specifically:
- "נאַכאַמלק" is not a recognizable Yiddish word and seems to be gibberish.
- "נישט קיין גענעזיס בלאָק געפֿונען" is close, but "נאכאמלק" at the beginning makes no sense.
- "אָדער נישט קיין געלעגנהייט" ("or no opportunity") is a mistranslation of "or no genesis block found".
- "פֿאַרוואָן דאטע-דירעקטאָריע פֿאַר נעץ?" ("Wrong data directory for network?") is close but awkwardly constructed.

Correct translation:
נישט געפֿונען קיין גענעזיס-בלאָק אָדער געפֿונען נישט ריכטיק. אפשר די דאטע דירעקטעריע איז נישט גוט פֿאַר דעם נעץ?
```

```
        <source>Initialization sanity check failed. %s is shutting down.</source>
        <translation>יוזע אָנפאַנג סאַנטי טשעק איז פעלל געווען. 1%s איז זיך אונטערגעשטעלט.</translation>
    
YES
There are two issues:
1. The format specifier from the source (%s) was changed to 1%s in the translation, which is incorrect.
2. There is a whitespace formatting issue—there should not be a space at the start of the line.

Correct translation:
יָצאָג־אָנפאַנג סאַניטי־טשעק איז דורכגעפֿאַלן. %s שטערט זיך אָפּ.
```

```
        <source>Invalid -i2psam address or hostname: '%s'</source>
        <translation>אַרויסגעבן -i2psam אַדרעס אָדער האָסטניימע: '1%s' איז אומגערעכט.</translation>
    
YES
The translation has multiple problems:
1. "אַרויסגעבן" means "to issue" or "to publish," not "invalid".
2. The word "אומגערעכט" is a bit awkward for "invalid"; a more common term would be "אומגילטיק".
3. There is an erroneous "1" in '1%s'.
4. The word order is awkward; it should stick close to the original.

Correct translation:
אומגילטיק -i2psam אַדרעס אָדער האָסטניימע: '%s'
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>יולעזער -אוןיאָן אדרעס אדער הוסטנאַם: '1%s'</translation>
    
YES
The translation is problematic for the following reasons:
- "יולעזער" is an incorrect transliteration and does not mean "invalid" in Yiddish.
- The translation uses "1%s" instead of the correct "%s" format specifier.
- The dash before "אוןיאָן" ("-אוןיאָן") is a literal and should match the context of the original string.
- The rest of the translation, "אדרעס אדער הוסטנאַם" for "address or hostname", is a fair translation.

Correct translation:
אומגילטיקער -onion אַדרעס אָדער האָסטנאַם: '%s'
```

```
        <source>Invalid -proxy address or hostname: '%s'</source>
        <translation>אין גültיק -פּראָקסי אַדרעס אָדער האָסטנײם: '1%s'</translation>
    
YES
There are several issues:
1. "גültיק" is a mix of Yiddish and German (should be "גילטיק" or more properly "אויגעטיק" for "invalid").
2. The format specifier '%s' in the source was changed to '1%s' in the translation, which is incorrect.
3. The hyphen before "פּראָקסי" should be maintained together with the word, as in the source.
4. "האָסטנײם" is an attempt at "hostname," but using "האָסטנאַם" is better for Yiddish.

Correct translation:
אויסגילטיקע -פּראָקסי אַדרעס אָדער האָסטנאַם: '%s'
```

```
        <source>Invalid P2P permission: '%s'</source>
        <translation>יוצרים פּ2פּ זכּות: '1%s'</translation>
    
YES  
The translation is incorrect. The word "יוצרים" means "creating" or "creators" and "זכּות" means "right" or "privilege", but here the translation is not faithfully translating "Invalid P2P permission: '%s'". Also, the format specifier '%s' was changed to '1%s', which is not faithful to the original.

Correct translation:
פאַרקריפּלטע פּ2פּ-בירעכטיקונג: '%s'
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>ניט גאָלדיגער בטראַכט פֿאַר 1%s=: '1%s' (מוז זײַן בּאַלד נישט ווייניקער ווי 1%s)</translation>
    
YES
The translation contains multiple errors:
1. The translation uses "ניט גאָלדיגער בטראַכט" which is not idiomatic in Yiddish for "Invalid amount". A better term is "אומגילטיק סומע" or "אומגילטיקער סכום".
2. It incorrectly uses "1%s" several times instead of simply "%s", which would break format specifiers.
3. The phrase "מוז זײַן בּאַלד נישט ווייניקער ווי" is too wordy and awkward for "must be at least %s". The usual Yiddish is "מוז זיין לפּחות %s".
4. The placement and format of specifiers does not match the source.

Correct translation:
אומגילטיקע סומע פֿאַר %s=&lt;amount&gt;: '%s' (מוז זיין לפּחות %s)
```

```
        <source>Invalid netmask specified in -whitelist: '%s'</source>
        <translation>ניט גיטע נעטמאַסק געבאַטן אין -ווייטליסט: '1%s'</translation>
    
YES
There are several problems with the translation:
1. The correct placeholder is '%s' from the source, but in the translation it's written as '1%s', which is incorrect.
2. The translation is not entirely accurate. "ניט גיטע נעטמאַסק געבאַטן" literally means "not good netmask given" which is nonstandard and a bit awkward.
3. The term "נעטמאַסק" is usable but could be more idiomatically "נעטמאַסק" or clarify further, and "געבאַטן" should ideally be "אַנגעגעבן" or "אַנגעצייגט" for "specified".

Correct translation:
אומגילטיקער נעטמאַסק ספּעציפיצירט אין -ווייטליסט: '%s'
```

```
        <source>Invalid port specified in %s: '%s'</source>
        <translation>יערור פּאָרט פארמאַטער אין 1%s: '1%s'</translation>
    
YES
The translation is problematic for several reasons:
1. The format specifiers '%s' were replaced with '1%s', which is incorrect and not standard in Yiddish or general translation practice; they must remain as '%s'.
2. The phrase is incorrectly translated: "יערור פּאָרט פארמאַטער אין 1%s: '1%s'" doesn't make sense in Yiddish, both in grammar and word choice.
3. Yiddish transliteration for "Invalid port specified in %s: '%s'" should be much closer in meaning and structure.

Correct translation:
אונבילדיקע פּאָרט אנגעגעבן אין %s: '%s'
```

```
        <source>Invalid pre-selected input %s</source>
        <translation>ניט געלטיק פּרע-געקליבן אַרײַן 1%s</translation>
    
YES  
There is an error in the translation:  
- "אַרײַן 1%s" mistakenly inserts a "1" before the "%s" placeholder, which is not present in the source and thus erroneous.
- The English term "input" should be better rendered as "איינצוג" (or occasionally other yiddishizations for the technical term).
- The rest of the text is otherwise mostly correct.

Correct translation:  
ניט געלטיק פּרע-געקליבן איינצוג %s
```

```
        <source>Listening for incoming connections failed (listen returned error %s)</source>
        <translation>פֿאַרענטפֿערס פֿאַר אָנקומען קאָנעקציעס איז געשלאגן (הערן האט צוריקגעגעבן טעות 1%s)</translation>
    
YES
There are several issues:
- The translation mistranslates "Listening" as "פֿאַרענטפֿערס", which means "responses"; the correct word should be "הערן" (to listen).
- The translation introduces "1" before %s ("טעות 1%s"), which is not in the original and is erroneous.
- The word order and terminology do not sound natural in Yiddish for technical content.

Correct translation:
הערן אויף אָנקומענדיקע פֿאַרבינדונגען איז דורכגעפֿאַלן (הערן האָט צוריקגעגעבן דער טעות %s)
```

```
        <source>Maximum transaction weight must be between %d and %d</source>
        <translation>דער מקסימום פון טערנזאַקטיאָן וואָג מוז זיין צווישן 1%d און 1%d</translation>
    
YES
The translation is problematic. The numbers (%d) in the translation source are prefixed with '1', which is incorrect and will cause formatting errors. Also, the word "טערנזאַקטיאָן" should be spelled "טראַנסאַקטיאָן" in standard Yiddish, and "וואָג" should remain "וואָג". The structure "דער מקסימום פון ..." is a bit awkward; a smoother translation would be:

Correct translation:
דער מאַקסימום טראַנסאַקטיאָן וואָג דאַרף זײַן צווישן %d און %d

Explanation: The format specifiers are now correctly retained, the wording is improved, and the spelling standard.
```

```
        <source>Need to specify a port with -whitebind: '%s'</source>
        <translation>מוז מען צושטעלן אַ פּאָרט מיט -whitebind: '1%s'</translation>
    
YES
There is an error in the translation: '%s' in the source becomes '1%s' in the translation. The stray '1' is incorrect and should be removed. Also, the translation should keep the variable placeholder formatting exactly as in the source.

Correct translation:
מוז מען ספּעציפיצירן אַ פּאָרט מיט -whitebind: '%s'
```

```
        <source>Not found pre-selected input %s</source>
        <translation>נישט געפֿונען פֿאַר-ערקלערטע אַפּגראַדע 1%s</translation>
    
YES
The Yiddish translation is incorrect and introduces the untranslated word "אַפּגראַדע" (upgrade), which is unrelated to the original text. "פֿאַר-ערקלערטע" attempts to mean "pre-selected", but the word for "input" is missing, and the number formatting (%s) is off (should be kept as %s, not 1%s).

Correct translation:
נישט געפֿונען פֿאַר-אויסגעקליבן אַרײַנפֿיר %s
```

```
        <source>Not solvable pre-selected input %s</source>
        <translation>נישט אָסאָלוועבל פּרע-רעבחרטע אינפּוט 1%s</translation>
    
YES
There are problems with the translation:
- The correct Yiddish for 'Not solvable' is 'ניט פארהאנעמבאר' or 'ניט אָפּצולעזן' (though more technical speakers may prefer a different phrase).
- '%s' must not be altered; '1%s' is incorrect formatting.
- 'פּרע-רעבחרטע' should be 'פרי-אויסגעקליבענע' for 'pre-selected'.
- 'אינפּוט' is acceptable, though 'אַרײַנפֿיר' may also be used, but 'אינפּוט' is generally used for technical translations.

Correct translation:
ניט אויסצולעזן פרי-אויסגעקליבענע אינפּוט %s
```

```
        <source>Only direction was set, no permissions: '%s'</source>
        <translation>נור פֿאַרלויף איז אופן, קיין רעכט נישט: '1%s'</translation>
    
YES
There is a translation error:
- "נור פֿאַרלויף איז אופן" is not correct Yiddish for "Only direction was set".
- "רעכט" generally means "rights" or "law"; in this context, "permissions" is better as "דערלויבענישן".
- The format specifier '%s' should be retained as '%s' and must not be changed to '1%s' (this looks like an error).
- Also, "נור" should be "נאָר" ("only").

Correct translation:
נאָר דער ריכטונג איז געזעצט געווארן, קיין דערלויבענישן נישט: '%s'
```

```
        <source>Reducing -maxconnections from %d to %d, because of system limitations.</source>
        <translation>מינעערן -maxconnections פון 1%d צו 1%d, צוליב סיסטעם גרעניצונגען.</translation>
    
YES
The format specifiers in the translation are incorrect. In the source, %d is used, but in the translation, 1%d is used, which is an error. Also, "מינעערן" is a reasonable rendering of "reducing," and the rest of the translation is largely accurate, though "צוליב סיסטעם גרעניצונגען" could use a slight improvement for clarity ("סיסטעם באַגרענעצונגען"). The spacing and order are correct otherwise.

Correct translation:
מינעערן -maxconnections פון %d צו %d, צוליב סיסטעם באַגרענעצונגען.
```

```
        <source>Replaying blocks…</source>
        <translation>ייִדן בלאָקען נאָך</translation>
    
YES  
The translation is incorrect. "ייִדן בלאָקען נאָך" translates to "Jews blocks after" or nonsensical/Yiddish gibberish. The word for "replaying" should be something like "וויידערשפּילן" or "נאָכמאל דורכגיין".  
A more accurate translation would be:  
וויידערשפּילן בלאָקען…  
or  
דורכגיין בלאָקען נאָך…  
So,  
Correct translation:  
וויידערשפּילן בלאָקען…
```

```
        <source>SQLiteDatabase: Failed to execute statement to verify database: %s</source>
        <translation>SQLiteDatabase: אויב עס איז נישט מיטגעקומען מיטן אויספירן דעקלאראַציע צו אויפריכטען די דאטן-בנק: 1%s</translation>
    
YES
The translation is inaccurate and problematic. The phrase "אויב עס איז נישט מיטגעקומען מיטן אויספירן דעקלאראַציע צו אויפריכטען די דאטן-בנק: 1%s" is awkward, not idiomatic, and contains errors.

Problems:
- The translation is more like "If it didn't succeed with executing the declaration to set up the data bank: 1%s", which changes the meaning.
- The insertion of "1" before "%s" is erroneous, distorting the format specifier.
- "דאטן-בנק" is a correct term for "database", but "אויפריכטען" means "to set up", not "to verify".
- "Failed to execute statement to verify database: %s" should more faithfully describe a failure in running a verification statement.

Correct translation:
SQLiteDatabase: דורכפאַל צו אויספירן דער קלערונג-זאַץ צו באשטעטיגן די דאטן-באַנק: %s
```

```
        <source>SQLiteDatabase: Failed to prepare statement to verify database: %s</source>
        <translation>SQLiteDatabase: עס איז נישט מצליח צו פארהערן דער אויסשטרעלונג צו באשטעטיגן דעם דאטאבייס: 1%s</translation>
    
YES
The translation has several issues:
- "עס איז נישט מצליח צו פארהערן דער אויסשטרעלונג" is not a correct or idiomatic Yiddish rendering of "Failed to prepare statement".
- The word "אויסשטרעלונג" does not fit the context of "statement" (as in SQL statement).
- The format specifier "%s" has an erroneous "1" prefixed in the translation ("1%s"), which is incorrect.

Correct translation:
SQLiteDatabase: נישט געלונגען צוגרייטן דער סטאַטעמענט צו באשטעטיגן דעם דאטאבייס: %s
```

```
        <source>SQLiteDatabase: Failed to read database verification error: %s</source>
        <translation>SQLiteDatabase: עס איז נישט מצליח צו פארהערן דער אויסשטרעלונג צו באשטעטיגן דעם דאטאבייס: 1%s</translation>
    
YES
There are several issues:
1. The translation is inaccurately structured and semantically problematic. The phrase "עס איז נישט מצליח צו פארהערן דער אויסשטרעלונג צו באשטעטיגן דעם דאטאבייס" is an incorrect rendering of "Failed to read database verification error: %s". For instance, "אויששטרעלונג" is not the correct word for "verification error", and "פארהערן" is not appropriate for "read" in this context.
2. There is a spurious "1" in "1%s", which does not exist in the source and is a likely typo.
3. The translation is clumsy and hard to understand for a native Yiddish speaker.

Correct translation:
SQLiteDatabase: נישט געקענט לייענען די דאטאבייס-באשטעטיקונגס-פעלער: %s
```

```
        <source>SQLiteDatabase: Unexpected application id. Expected %u, got %u</source>
        <translation> SQLiteDatabase: אומפאַרווארפן אַפּליקאַציע אייר. ציפער 1%u, באקומען 1%u</translation>
    
YES
There are several issues:
- "אומפאַרווארפן אַפּליקאַציע אייר" is a mistranslation and awkward. "אייר" is probably a typo intended for "ID" (should be "ID" or "איידי" in Yiddish).
- The text does not preserve the order and usage of the format specifiers; "%u" is wrongly positioned and has an unnecessary "ציפער 1" ("number 1") which is inaccurate.
- There is an unnecessary space at the start of the translation string.
- The word "Unexpected" should be something like "נישט דערוואַרטער", and "expected" should use "דערוואַרט".

Correct translation:
SQLiteDatabase: נישט דערוואַרטער אַפּליקאַציע איידי. דערוואַרט %u, באקומען %u
```

```
        <source>Section [%s] is not recognized.</source>
        <translation>סעקטאָר [1%s] איז נישט אנערקענט.</translation>
    
YES
The translation is problematic: "סעקטאָר [1%s] איז נישט אנערקענט." has two issues:
1. The English word "Section" should not be "סעקטאָר" (which means "sector" and not "section" in Yiddish/Hebrew usage). "Section" in this context is better rendered as "סעקציע".
2. The format specifier is incorrect: "[1%s]" instead of "[%s]".

Correct translation:
סעקציע [%s] איז נישט אנערקענט.
```

```
        <source>Signer returned error: %s</source>
        <translation>Yiddish: סײַנער האָט צוריקגעגעבן עראָר: 1%s</translation>
    
YES
The translation is problematic for several reasons:
1. It includes the word 'Yiddish:', which is unnecessary and not part of a proper translation.
2. The format specifier '%s' is incorrectly rendered as '1%s'; the '1' is an error.
3. The translation itself is awkward and not idiomatic Yiddish.

Correct translation:
סײַנער האָט צוריקגעגעבן אַ טעות: %s
```

```
        <source>Signing transaction failed</source>
        <translation>דער אָנשטיין פון דער טרנזקציע איז אויווד</translation>
    
YES  
The translation is problematic. The Yiddish text "דער אָנשטיין פון דער טרנזקציע איז אויווד" is incorrect both in word choice and meaning:

1. "אָנשטיין" is not the correct term for "signing" in this context.
2. "איז אויווד" means "is lost", which does not correspond to "failed".

Correct translation:
דער אונטערשרייבן פֿון דער טראַנזאַקשאַן איז ניט געגלונגען
```

```
        <source>Specified -walletdir "%s" does not exist</source>
        <translation>יאָוולעט דיר '-walletdir "1%s"' עקזיסטירט נישט.</translation>
    
YES
There are several errors in this translation:
1. The translation incorrectly introduces 'יאָוולעט דיר' which is a literal transliteration of 'walletdir', but it is not standard Yiddish. The source path should be kept as a technical term or just quoted.
2. The format specifier is wrong: '1%s' instead of '%s'.
3. There are unnecessary single quotes.
4. The original message says "Specified", which is not translated.
5. The order of elements is off, and the translation is awkward.

Correct translation:
דער אָנגעגעבןער -walletdir "%s" עקזיסטירט נישט.
```

```
        <source>Specified -walletdir "%s" is a relative path</source>
        <translation>די צוגעגעבענע -walletdir "1%s" איז אַ רעלאַטיווע פּאַט.</translation>
    
YES
There is an error in the format specifier: the source uses "%s" but the translation has "1%s". The "1" should not be present; it looks like either a typo or a mistaken attempt at a positional specifier. Also, the translation is otherwise correct.

Correct translation:
די צוגעגעבענע -walletdir "%s" איז אַ רעלאַטיווע פּאַט.
```

```
        <source>Specified -walletdir "%s" is not a directory</source>
        <translation>דער באשטימטער -walletdir '1%s' איז נישט אַ דירעקטאָריע</translation>
    
YES
The translation is mostly correct, but there is a formatting error: the format specifier is '1%s', which is incorrect. It should just be '%s' as in the source. Also, the quotation marks should be consistent with the original (use double quotes as in the source). Additionally, the rest of the translation is accurately rendered.

Correct translation:
דער באשטימטער -walletdir "%s" איז נישט אַ דירעקטאָריע
```

```
        <source>Specified blocks directory "%s" does not exist.</source>
        <translation>געווויערן בלאָק דיירעקטאָריע '1%s' עקזיסטירט נישט.</translation>
    
YES
The translation is problematic for two reasons:
1. The word "געווויערן" is a nonstandard or erroneous transliteration and is not the correct way to say "specified" in Yiddish.
2. The format specifier is written as '1%s' instead of '%s', resulting in an incorrect output.

Correct translation:
ספּעציפיצירטע בלאָק־דירעקטאָריע "%s" עקזיסטירט נישט.
```

```
        <source>Specified data directory "%s" does not exist.</source>
        <translation>Yiddish: דער באַשטימטער דאַטע דירעקטאָריע "1%s" עקזיסטירט נישט.</translation>
    
YES
The translation is problematic. It improperly includes "Yiddish:" in the translation, which is unnecessary and nonstandard. Furthermore, it mistranslates the format specifier: "1%s" should be "%s" as in the source. The remainder of the Yiddish translation is acceptable, but should not include English text or erroneous format specifiers.

Correct translation:
דער באַשטימטער דאַטע־דירעקטאָריע "%s" עקזיסטירט נישט.
```

```
        <source>System error while flushing: %s</source>
        <translation>ייִדיש: סיסטעם עראר בעת פלושטשינג: 1%s</translation>
    
YES
The translation is problematic. The prefix "ייִדיש:" ("Yiddish:") is unnecessary and incorrect. The word "פלושטשינג" is a literal transliteration of "flushing" and may not be clear in Yiddish. Additionally, the format specifier "%s" should be preserved exactly as in the source, but "1%s" is present, which is incorrect.

Correct translation:
סיסטעמען טעות בעת פלישן: %s
```

```
        <source>System error while loading external block file: %s</source>
        <translation>יִשׁוּב סִיסטֶם בעת לאָדן אָפּזעצער בלאָק-פֿײַל: 1%s</translation>
    
YES
The translation is problematic. The Yiddish translation uses a mixture of Hebrew and phonetic Yiddish, and there is a formatting error with "1%s" (should be "%s", and number placement appears incorrect). Also, "אָפּזעצער בלאָק-פֿײַל" is not an accurate technical rendering of "external block file," and "יִשׁוּב סִיסטֶם" is not standard Yiddish for "system error."

Correct translation:
סיסטעם-טעות ביים לאָډן אַן עקסטערנעם בלאָק-טעקע: %s
```

```
        <source>System error while saving block to disk: %s</source>
        <translation>סיסטעם ערראָר בעת שמירה בלאָק אויף דיסק: 1%s</translation>
    
YES
There is an error with the format specifier. The source uses "%s" but the translation uses "1%s" (which is not a valid placeholder and may cause issues). It should be "%s" in both.

Correct translation:
סיסטעם ערראָר בעת שמירה בלאָק אויף דיסק: %s
```

```
        <source>The source code is available from %s.</source>
        <translation>די מקור קאָד איז בנימצא פון 1%s.</translation>
    
YES
The translation incorrectly inserts "1" before %s ("פון 1%s"), which does not appear in the original English and is erroneous. The format specifier %s is also misplaced.

Correct translation:
די מקור קאָד איז בנימצא פון %s.
```

```
        <source>The specified config file %s does not exist</source>
        <translation>דער צוגעגעבענע קאנפיג־טעקסט 1%s עקזיסטירט נישט.</translation>
    
YES
The translation has two issues:
1. The format specifier %s should appear exactly as in the source. The translation has '1%s' which is incorrect.
2. The word "טעקסט" is not appropriate for "file"; the usual term for "file" in Yiddish is "טעקע".

Correct translation:
דער אנגעגעבןער קאנפיג־טעקע %s עקזיסטירט נישט.
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>די וואַלטעוועט וועט אויסמאַכן נישט צאָלן פחות ווי דער מינימום פֿאַרבינדונג קאָסטן.</translation>
    
YES
The translation has multiple issues:
- "די וואַלטעוועט וועט אויסמאַכן נישט צאָלן" is awkward and not idiomatic Yiddish; "wallet" should be "וועלט" or "בייַטל", not "וואַלטעוועט".
- "מינימום פֿאַרבינדונג קאָסטן" means "minimum connection cost", which does not match "minimum relay fee" (a specific term in Bitcoin transactions). The relay fee should be transliterated or explained (e.g. "רעליי-פֿי" or "מינימום רעליי-שטער") for clarity.
- There is no spelling or double space error, but the translation is semantically incorrect.

Correct translation:
דער בייַטל וועט נישט צאָלן ווייניקער ווי דעם מינימום רעליי-שטער.
```

```
        <source>This is experimental software.</source>
        <translation>דערהייַנטיק איז עקספּערימענטאַלע ווייכווארג.</translation>
    
YES
The translation has a grammatical error: "דערהייַנטיק" means "current" or "updated", rather than "this".

Correct translation:
דאס איז אַ עקספּערימענטעלע ווייכווארג.
```

```
        <source>Transaction %s does not belong to this wallet</source>
        <translation>טראַנסאַקטיאָן 1%s איז נישט פֿאַר די וואָלט</translation>
    
YES
The translation is incorrect. The numeral "1" appears erroneously before "%s", and "די וואָלט" should be "דעם וואָלט" to match the original meaning ("this wallet"). Also, the phrase should use the possessive construct.

Correct translation:
טראַנסאַקטיאָן %s געהערט נישט צו דעם וואָלט
```

```
        <source>Unable to bind to %s on this computer (bind returned error %s)</source>
        <translation>ניט מעגלעך צו בינדן צו 1%s אויף דעם קאָמפּיוטער (בינדן האָט צוריקגעגעבן אַ גרייַז 1%s)</translation>
    
YES
The translation is mostly correct but contains two format specifier mistakes. The source uses "%s", but the translation renders them as "1%s", which is incorrect and will break runtime behavior. The "%s" should be carried over exactly as in the source.

Correct translation:
ניט מעגלעך צו בינדן צו %s אויף דעם קאָמפּיוטער (בינדן האָט צוריקגעגעבן אַ גרייַז %s)
```

```
        <source>Unable to bind to %s on this computer. %s is probably already running.</source>
        <translation>ניט מעגלעך צו בינדן צו 1%s אויף דעם קאָמפּיוטער. 1%s לויפט מסתּמא שוין.</translation>
    
YES
The translation contains errors with respect to format specifiers. The original source uses "%s" twice, but the translation uses "1%s" twice instead, which is not correct and could cause formatting issues. Additionally, the remainder of the translation is generally accurate.

Correct translation:
ניט מעגלעך צו בינדן צו %s אויף דעם קאָמפּיוטער. %s לויפט מסתּמא שוין.
```

```
        <source>Unable to create the PID file '%s': %s</source>
        <translation>נישט קאָנען שאַפֿן די PID טעקע '1%s': 1%s</translation>
    
YES  
The translation is problematic for two reasons:

1. The format specifiers in the translation are incorrect. In the source, the placeholders are '%s' but in the translation, they appear as '1%s', which is not standard and could break program functionality.
2. The Yiddish wording could be improved for clarity and correctness. "נישט קאָנען שאַפֿן" is a literal calque from English and may sound unnatural; a better phrasing is "קענען נישטשאַפֿן" or "קענען נישט מאַכן."

Correct translation:
קענען נישט מאַכן די PID טעקע '%s': %s
```

```
        <source>Unable to generate initial keys</source>
        <translation>ניט אפשריק צו générירן אָרײַנקע לאַרגעלע</translation>
    
YES
The translation is problematic for several reasons:
1. The word "גערןירן" (génériren) is a Yiddish transliteration of the French/English "generate," but it is not standard usage in Yiddish. The standard Yiddish term for "to generate" or "to create" would be "שאַפֿן" (shafn) or "הערויסברענגען" (heroysbrengen).
2. "אָרײַנקע לאַרגעלע" does not convey the meaning of "initial keys". "אָנהייביקע שליסלען" would be appropriate for "initial keys".
3. The sentence structure does not accurately translate the source meaning.

Correct translation:
ניט מעגליך צו שאַפֿן אָנהייביקע שליסלען
```

```
        <source>Unable to open %s for writing</source>
        <translation>קענט ניט עפענען 1%s פֿאַר געשריבן</translation>
    
YES
The translation is problematic in two ways:
1. The placeholder '%s' is incorrectly written as '1%s' instead of '%s'. The '1' is extraneous.
2. The phrase "פֿאַר געשריבן" is not idiomatic in Yiddish; the correct phrase should be "פאר שרייבן" which means 'for writing'.

Correct translation:
קענט ניט עפענען %s פֿאַר שרייבן
```

```
        <source>Unable to parse -maxuploadtarget: '%s'</source>
        <translation>קענט נישט פֿאַראַרבעטן -maxuploadtarget: '1%s'</translation>
    
YES
There is a problem with the format specifier. The source text uses '%s', but the translation contains '1%s', which appears to be a typo or error (the '1' is extraneous). Also, the translation for "parse" should more accurately be "פּאַרסירן" in this context, not "פֿאַראַרבעטן" ("process").

Correct translation:
קענט נישט פּאַרסירן -maxuploadtarget: '%s'
```

```
        <source>Unable to unload the wallet before migrating</source>
        <translation>נישט אפשר צו אויסלאָדן דעם וואַלעט ווען קודם פּונקטירן</translation>
    
YES
There is a problematic translation: The Yiddish "נישט אפשר צו אויסלאָדן דעם וואַלעט ווען קודם פּונקטירן" is not accurate. "פונקטירן" usually means "to punctuate" or "to mark," and does not accurately convey "migrating." The translation should reflect "before migrating" more accurately. Also, the sentence structure could be improved.

Correct translation:
ניט מעגליך ארויסצולאָדן דעם וועלעט איבערצופירן
Or, more literally:
ניט מעגליך אויסלאָדן דעם וועלעט איידער איבערפירן

Either is much clearer.
```

```
        <source>Unknown -blockfilterindex value %s.</source>
        <translation>יידנט -בלאָקפֿילטער אינדעקס ווערט 1%s.</translation>
    
YES
The translation is problematic. The word "יידנט" ("ident" or similar) does not mean "unknown" in Yiddish, and there is a problem with the placement of "1" before %s ("1%s" instead of "%s"). The translation also has format and wording errors.

Correct translation:
אומבאַקאַנט -בלאָקפֿילטער אינדעקס ווערט %s.
```

```
        <source>Unknown address type '%s'</source>
        <translation>אומדעוקט אדרעס טיפּ '1%s'</translation>
    
YES  
There are several issues:  
1. The '%s' format specifier in the source is incorrectly translated as '1%s', which is erroneous.  
2. The Yiddish spelling of "Unknown" should be 'אונbekannt' or 'אומבקאנט', but 'אומדעוקט' is not a Yiddish word.  
3. The word "address" in Yiddish is "אַדרעס", not "אדרעס".  
4. The word "type" should be "טיפּ".  
Correct translation:  
אומבקאנט אַדרעס טיפּ '%s'
```

```
        <source>Unknown change type '%s'</source>
        <translation>יידישע: אנבעלשערט טייפל פון ענדערונג '1%s'</translation>
    
YES
The translation has several issues:
1. It starts with "יידישע:" which means "Yiddish:"—this is not part of the original message and should not be present.
2. The content "אַנבעלשערט טייפל פון ענדערונג" does not match standard Yiddish and is a literal mix. "אַנבעלשערט" means "unbound," but "unknown" would be better translated as "אומבאַקאַנט".
3. The variable is changed from '%s' to '1%s'—this is incorrect; the format specifier should be preserved exactly as in the source.
4. "טייפל" (teypl) is likely a transcription error or a nonstandard form for "טיפּ" (tip), meaning "type".

Correct translation:
אומבאַקאַנט ענדערונג־טיפּ '%s'
```

```
        <source>Unknown network specified in -onlynet: '%s'</source>
        <translation>אומפֿרידן נעץ איז צוגעגעבן אין -onlynet: '1%s'</translation>
    
YES
There is a translation error: 'אומפֿרידן נעץ' translates to 'unsatisfied network', which is not correct for 'Unknown network'. Also, the specifier has erroneously become '1%s' instead of '%s'. The rest of the sentence structure is also off.

Correct translation:
אונbekanntע נעץ ספּעציפֿיצירט אין -onlynet: '%s'
```

```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>נישט באקאנטע נייע רשימות אַקטיווי (װערסיעביט 1%i)</translation>
    
YES
There is an error in the translation:
- "רשימות" means "lists", but the correct term in the Bitcoin context is "רעגולות" (rules).
- The format specifier "%i" is incorrectly rendered as "1%i".
- There is an awkward and incorrect translation of "activated" as "אַקטיווי", which should be "אַקטיווירט".
- The rest of the translation has minor spelling issues (e.g. "נישט באקאנטע" should use "אומבאקאנטע").

Correct translation:
אומבאקאנטע נייע רגולות זענען אַקטיווירט (ווערסיעביט %i)
```

```
        <source>Unrecognised option "%s" provided in -test=&lt;option&gt;.</source>
        <translation>ניט דערקענט אָפּציע "1%s" צוגעשטעלט אין - פּרובירן=&lt;option&gt;.</translation>
    
YES  
There are several issues with the translation:  
1. "1%s" is incorrect. It should be "%s", matching the format specifier in the source.
2. The translation for "option" and "test" should be more precise; ײִדיש speakers are more likely to use "אָפּציע" for "option", but "פּרובירן" is more of a verb ("to try/test") rather than a noun for the flag.  
3. The translation awkwardly adds spaces and doesn't preserve the structure.

Correct translation:  
ניט דערקענט אָפּציע "%s" צוגעשטעלט אין -test=&lt;option&gt;.
```

```
        <source>Unsupported global logging level %s=%s. Valid values: %s.</source>
        <translation>נישט געשטיצט גלאבאלע לאָגגינג מדרגה 1%s=1%s. גילטיקע ווערטן: 1%s.</translation>
    
YES
The translation has several issues:
1. The format specifiers (%s) are incorrectly changed to 1%s=1%s. They should remain as %s (no leading number or equal sign).
2. The rest of the sentence is fairly accurate, but the errors in format specifiers may cause runtime issues in the application.

Correct translation:
נישט געשטיצט גלאבאלע לאָגגינג מדרגה %s=%s. גילטיקע ווערטן: %s.
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>דער שאַפֿן וואָלעט טעקע איז פאַרפאַלן: 1%s</translation>
    
YES
There are several issues:
1. "פאַרפאַלן" is not a natural word for "failed" in this context; "ניט געלונגען" or "אײַנשאַפֿן טעקע פאַרוואָלעט איז ניט געלונגען" is better.
2. The format specifier "%s" is incorrectly prefixed with a "1", resulting in "1%s", which is not present in the source and is a formatting error.

Correct translation:
די שאפֿן פֿון דער וואלעט-טעקע איז ניט געלונגען: %s
```

```
        <source>Unsupported logging category %s=%s.</source>
        <translation>נישט געשטיצט לאָגינג קאַטעגאָריע 1%s=1%s.</translation>
    
YES
The translation is problematic because it incorrectly includes "1" before the format specifiers, changing "%s" to "1%s". This is not present in the original and will break format substitution. Also, the correct Yiddish translation should accurately reflect the source.

Correct translation:
נישט געשטיצט לאָגינג קאַטעגאָריע %s=%s.
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>אַ טעות: קען נישט לייגען די וואָטשט-נאָר איבערגעשיקט 1%s אין דער וואָטשט-נאָר וואָלעט</translation>
    
YES
There are a few issues in the Yiddish translation:

1. The format specifier "%s" is replaced incorrectly by "1%s". The "1" should not be present.
2. The translation uses "וואָטשט-נאָר איבערגעשיקט", which is not a direct or common translation for "watchonly tx". "tx" stands for "transaction" and could be better rendered as "טראַנסאַקציע".
3. The overall sentence structure and terminology could be improved for clarity and accuracy.

Correct translation:
אַ טעות: קען נישט צולייגן די watchonly טראַנסאַקציע %s אין דער watchonly וואָלעט

Explanation:
- Kept "watchonly" in transliteration as is common in technical parlance.
- Used "טראַנסאַקציע" for "transaction" (tx).
- Ensured "%s" is carried over correctly with no preceding '1'.
```

```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>אנהייב: באַמערקונג פון באַניצער אַגענט (1%s) כּולל אומזיכערע אותיות.</translation>
    
YES
There are several issues:
1. The translation incorrectly inserts 'אנהייב:' ("Start:") at the beginning, which is not present in the English.
2. The format specifier is translated as '1%s' instead of '%s'—the '1' is erroneous.
3. The translation, while understandable, is slightly off in phrasing and does not closely match the English syntax.

Correct translation:
באַניצער־אַגענט באַמערקונג (%s) כּולל אומזיכערע אותיות.
```

```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>די וואָלעט דאַרף ווערן איבערגעשריבן: פאַרהייב 1%s צו פאַרענדיקן</translation>
    
YES
The translation uses "1%s" instead of "%s", incorrectly introducing the numeral "1" before the format specifier. This is an error, and "%s" should be preserved as in the source.

Correct translation:
די וואָלעט דאַרף ווערן איבערגעשריבן: פאַרהייב %s צו פאַרענדיקן
```

```
        <source>Settings file could not be written</source>
        <translation>  די באַשטעטיקונגען טעקע קען נישט געשריבן ווערן</translation>
    
YES
There is a leading unnecessary space in the translation, which is a whitespace formatting issue. Also, the translation might be slightly improved for flow in Yiddish.

Correct translation:
די באַשטעטיקונגען טעקע קען נישט געשריבן ווערן
```
</details>

Number of issues: 106.
