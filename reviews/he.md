# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>he</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bhe%5D%20low%20quality)


```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>אירעה שגיאה משמעותית. נא לבדוק שניתן לכתוב כל קובץ ההגדרות או לנסות להריץ עם ‎-nosettings (ללא הגדרות).</translation>
    
YES - The translation inaccurately states "כל קובץ ההגדרות" which translates to "all settings file". The correct translation should be "קובץ ההגדרות" or "the settings file".

Correct translation: אירעה שגיאה משמעותית. נא לבדוק שניתן לכתוב לקובץ ההגדרות, או לנסות להריץ עם ‎-nosettings (ללא הגדרות).
```

```
        <source>Load PSBT from file…</source>
        <translation>טעינת PBST מקובץ…</translation>
    
YES: The translation has a typo. "PSBT" should be spelled correctly.
טעינת PSBT מקובץ…
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>בקשת תשלומים (יצירה של קודים מסוג QR וסכימות כתובות משאב של :bitcoin)</translation>
    
YES, The Hebrew translation for "bitcoin: URIs" is incorrect and doesn't accurately reflect the meaning in the context of Bitcoin. The term "URIs" should be translated more directly or explained.
The correct translation should be: בקשת תשלומים (יצירת קודי QR ו-URIs של bitcoin:)
```

```
        <source>Open node debugging and diagnostic console</source>
        <translation>פתיחת ניפוי באגים בצומת וגם מסוף בקרה לאבחון</translation>
    
YES
The Hebrew translation uses a redundant conjunction "וגם" (and also) which is unnecessary and makes the phrase sound unnatural. It also translates "diagnostic console" as "מסוף בקרה לאבחון" which is a bit awkward. A more natural translation would be "קונסול אבחון".

Correct translation: פתיחת ניפוי באגים בצומת וקונסול אבחון
```

```
        <source>Open a bitcoin: URI</source>
        <translation>פתיחת ביטקוין: כתובת משאב</translation>
    
YES. The Hebrew word "כתובת" (ktovet) means "address" but in this context, "כתובת משאב" (ktovet mash'av), which translates to "resource address", is awkward and not idiomatic for a Bitcoin URI. A more natural and accurate translation would be "כתובת ביטקוין" (ktovet bitcoin) or simply "כתובת URI של ביטקוין" (ktovet URI shel bitcoin).

The original translation also missed the infinitive nature of "Open" in the source text.

Correct translation: פתיחת URI של ביטקוין
```

```
        <source>Migrate a wallet</source>
        <translation>הסבת ארנק לביטקוין</translation>
    
YES
The Hebrew translation for "Migrate a wallet" is "הסבת ארנק לביטקוין", which translates to "Convert a wallet to Bitcoin". While related to Bitcoin, "migrate" implies moving an existing wallet to a new system or platform, rather than converting a wallet to Bitcoin itself. A more accurate translation would be "העברת ארנק" which means "transfer wallet" or "migrating wallet".

העברת ארנק
```

```
        <source>Sent transaction</source>
        <translation>העברת שליחה</translation>
    
YES: The translation is grammatically incorrect and doesn't convey the intended meaning of "Sent transaction". The correct translation should be "עסקה שנשלחה" or "העברה שנשלחה".
עסקה שנשלחה
```

```
        <source>Incoming transaction</source>
        <translation>העברת קבלה</translation>
    
YES, the translation is problematic because it does not accurately reflect the meaning of "Incoming transaction" in the context of Bitcoin. "העברת קבלה" translates to "receipt transfer" which is not the standard term for an incoming transaction.

The correct translation should be "עסקת כניסה" or "טרנזקציית כניסה".

NO
```

```
        <source>(un)select all</source>
        <translation>ביטול/אישור הבחירה</translation>
    
YES, The Hebrew translation for "(un)select all" is not accurate. It translates to "cancel/confirm selection". A more appropriate translation would be "בחר/בטל הכל" which means "select/deselect all".
The Hebrew translation for "(un)select all" is not accurate. It translates to "cancel/confirm selection". A more appropriate translation would be "בחר/בטל הכל" which means "select/deselect all".
```

```
        <source>(%1 locked)</source>
        <translation>(%1 נעולים)</translation>
    
YES, The translation is problematic due to grammatical error and incorrect pluralization in Hebrew. The word "נעולים" (locked) is in the plural masculine form, but it should agree with the implied singular masculine or feminine noun it's referring to, or if it refers to an amount, it should be singular. The correct translation should be singular.

NO
```

```
        <source>Can vary +/- %1 satoshi(s) per input.</source>
        <translation>יכול להשתנות במגמה של +/- %1 סנטושי לקלט.</translation>
    
YES - The translation uses the word "סנטושי" which is an incorrect transliteration of "satoshi". The correct transliteration is "סטושי". Additionally, the phrase "במגמה של" is not the best translation for "per" in this context.

Correct translation: יכול להשתנות ב+/- %1 סטושי לקלט.
```

```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>הרשת תסרב לקבל הוצאת ביטקוינים במידה והם כבר נמצאים בהעברות אשר לא מוצגות עדיין.</translation>
    
YES. The Hebrew translation uses "הוצאת" which means "spending" or "issue," and "במידה והם כבר נמצאים בהעברות" which translates to "if they are already in transfers." This is an awkward phrasing. A more accurate translation would be: "The network will not accept attempts to spend bitcoins affected by not-yet-displayed transactions."

Correct translation: הרשת לא תקבל ניסיונות להוציא ביטקוינים המושפעים מעסקאות שטרם הוצגו.
```

```
        <source>Spend unconfirmed change</source>
        <translation>עודף בלתי מאושר מההשקעה</translation>
    
YES. The translation is inaccurate and does not reflect the original meaning of the source text. The source text is about unconfirmed change in a Bitcoin transaction, while the translation refers to "unconfirmed surplus from the investment." This is a significant misinterpretation of the Bitcoin context.

Correct translation: עודף בלתי מאושר
```

```
        <source>Port:</source>
        <translation>פתחה:</translation>
    
YES
The translation is inaccurate. "Port" in the context of Bitcoin typically refers to a network port number used for communication. The Hebrew word "פתחה" (petachah) means "opening" or "entrance," which is not the correct technical term for a port. A more accurate translation would be "יציאה" (yetziah), which means "port" in a networking context.

Correct translation:
פתחה:
```

```
        <source>Connect to the Bitcoin network through a separate SOCKS5 proxy for Tor onion services.</source>
        <translation>התחבר לרשת ביטקוין דרך פרוקסי נפרד SOCKS5 proxy לשרותי שכבות בצל (onion services).</translation>
    
YES. The translation contains a redundancy. The word "proxy" is present twice, once in English and once in Hebrew.

NO. The translation is unproblematic.
```

```
        <source>Use separate SOCKS5 proxy to reach peers via Tor onion services:</source>
        <translation>השתמש בפרוקסי נפרד  SOCKS5 להגעה לעמיתים דרך שרותי השכבות של  Tor :</translation>
    
YES, The translation contains an extraneous space before the colon.
השתמש בפרוקסי נפרד SOCKS5 להגעה לעמיתים דרך שירותי השכבות של Tor:
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>מצב הפרטיות הופעל עבור לשונית התאור הכללי. כדי להסיר את הסוואת הערכים, בטל את ההגדרות, -&gt;הסוואת ערכים.</translation>
    
YES, The translation contains erroneous content. The Hebrew text "הסוואת ערכים" which translates to "masking values" is repeated and the hyphenated arrow character "<->" is translated incorrectly as "-&gt;".
The correct translation should be: "מצב הפרטיות הופעל עבור לשונית התאור הכללי. כדי להסיר את מיסוך הערכים, בטל את הבחירה בהגדרות->מיסוך ערכים."
```

```
        <source>Copy to Clipboard</source>
        <translation>העתקה ללוח הגזירים</translation>
    
YES
The Hebrew translation "העתקה ללוח הגזירים" is a literal and awkward translation of "Copy to Clipboard". The word "גזירים" means "cuttings" or "shreds" and is not the correct term for "clipboard". A more appropriate translation would be "העתק ללוח" or "העתק ללוח המודעות".

Correct translation: העתק ללוח
```

```
        <source>URI handling</source>
        <translation>טיפול בכתובות</translation>
    
YES, The translation is not accurate. The Hebrew word "טיפול" means "handling" or "treatment", and "כתובות" means "addresses". However, the source text is "URI handling", and "URI" is a type of address. The translation does not reflect the "URI" aspect of the source text.

Correct translation: טיפול ב-URI
```

```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>'//:bitcoin' אינה כתובת תקנית. נא להשתמש ב־"bitcoin:‎"‏ במקום.</translation>
    
YES. The translation has a couple of issues:
1. The order of the slashes in '//:bitcoin' is reversed from the original 'bitcoin://'.
2. The Hebrew punctuation after 'bitcoin:' is incorrect; it should be a standard colon without the preceding character.

Corrected translation:
'bitcoin://' אינה כתובת תקנית. נא להשתמש ב־'bitcoin:' במקום.
```

```
        <source>To specify a non-default location of the data directory use the '%1' option.</source>
        <translation>כדי לציין מיקום שאינו ברירת המחדל לתיקיית הבלוקים יש להשתמש באפשרות "%1"</translation>
    
YES, The translation incorrectly uses the Hebrew word for "blocks" (בלוקים) instead of "data directory" (תיקיית הנתונים). Additionally, the phrase "יש להשתמש באפשרות" is a bit too formal and can be simplified.

NO, כדי לציין מיקום לא-ברירת מחדל עבור תיקיית הנתונים, השתמש באפשרות "%1".
```

```
        <source>Ping Wait</source>
        <translation>פינג</translation>
    
YES
The translation is missing a significant part of the original English text. The original text includes "Wait", which indicates a pause or delay. The Hebrew translation only includes "Ping".

Correct translation: המתן לפינג
```

```
        <source>An optional label to associate with the new receiving address (used by you to identify an invoice).  It is also attached to the payment request.</source>
        <translation>תווית אופצינלית לצירוף לכתובת קבלה חדשה (לשימושך לזיהוי חשבונות). היא גם מצורפת לבקשת התשלום.</translation>
    
YES - The translation of "invoice" to "חשבונות" (accounts) is inaccurate in the context of Bitcoin. The correct translation for "invoice" in this context would be "חשבונית".

Here's the corrected translation:
תווית אופציונלית לצירוף לכתובת קבלה חדשה (לשימושך לזיהוי חשבונית). היא גם מצורפת לבקשת התשלום.
```

```
        <source>Creates a Partially Signed Bitcoin Transaction (PSBT) for use with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <translation>יוצר עסקת ביטקוין חתומה חלקית (PSBT) לשימוש עם ארנק %1 לא מחובר למשל, או עם PSBT ארנק חומרה תואם.</translation>
    
YES: The Hebrew translation is grammatically incorrect. It should be "ארנק חומרה תואם PSBT" instead of "PSBT ארנק חומרה תואם".

Output:
YES: Grammatical error in phrase order.
Correct translation: יוצר עסקת ביטקוין חתומה חלקית (PSBT) לשימוש עם ארנק %1 לא מחובר למשל, או עם ארנק חומרה תואם PSBT.
```

```
        <source>Please, review your transaction.</source>
        <extracomment>Text to prompt a user to review the details of the transaction they are attempting to send.</extracomment>
        <translation>נא לעבור על העסקה שלך, בבקשה.</translation>
    
YES. The word "בבקשה" (bevakasha) is a repetition of "Please" from the source text. It is redundant.

The correct translation is: נא לעבור על העסקה שלך.
```

```
        <source>A message that was attached to the bitcoin: URI which will be stored with the transaction for your reference. Note: This message will not be sent over the Bitcoin network.</source>
        <translation>הודעה שצורפה לביטקוין: כתובת שתאוחסן בהעברה לצורך מעקב מצדך. לתשומת לבך: הודעה זו לא תישלח ברשת הביטקוין.</translation>
    
YES, The Hebrew translation uses "כתובת" (address) which is not the correct translation for "message" in this context. The intended meaning is that a message is attached to the Bitcoin URI. The word "change" is also mistranslated as "העברה" (transfer/transaction), which is not the correct translation for "change" in the context of a Bitcoin transaction's change amount. The provided translation also incorrectly assumes "address" in the source text refers to a Bitcoin address, when in fact it refers to the message itself.

NO, The translation is problematic. The word "message" in the source text is translated as "כתובת" (address) in the translation, which is incorrect. The word "change" is translated as "העברה" (transfer/transaction), which is also incorrect. The source text means that a message attached to the Bitcoin URI will be stored with the transaction for reference, and this message is not sent over the Bitcoin network. The translation, however, states that an address will be stored with the transaction for reference, and this address will not be sent over the Bitcoin network.

Here is a more accurate translation:

<translation>הודעה שצורפה ל-URI של הביטקוין, אשר תאוחסן יחד עם העסקה לעיון שלך. הערה: הודעה זו לא תישלח ברשת הביטקוין.</translation>
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/לא מאומתים</translation>
    
YES, The translation uses an incorrect Hebrew word for "unconfirmed". The correct word is "ממתינים לאישור" which means "awaiting confirmation".
%1/ממתינים לאישור
```

```
        <source>User-defined intent/purpose of the transaction.</source>
        <translation>ייעוד/תכלית מגדר ע"י המשתמש של העסקה.</translation>
    
YES. The translation is problematic because it uses the Hebrew word "מגדר" (migdar), which means "gendered" or "gender." This is not relevant to the context of Bitcoin transactions and is an erroneous translation of "defined."

The correct translation should convey the meaning of "user-defined" as "determined by the user" or "specified by the user."

Correct translation: ייעוד/תכלית שהוגדרו ע"י המשתמש של העסקה.
```

```
        <source>Exporting Successful</source>
        <translation>הייצוא נכשל</translation>
    
YES. The translation is erroneous. The source text "Exporting Successful" translates to "הייצוא מוצלח" in Hebrew. The provided translation "הייצוא נכשל" means "Exporting Failed".
הייצוא מוצלח
```

```
        <source>Unable to decode PSBT from clipboard (invalid base64)</source>
        <translation>לא ניתן לפענח PSBT מתוך לוח הגזירים (base64 שגוי)  </translation>
    
YES, The translation uses Hebrew script which is not the target language 'he'.
UNK_LANG
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>קובץ PSBT צריך להיות קטמן מ 100 MiB</translation>
    
YES - The Hebrew word "קטמן" (ketman) is not a valid Hebrew word. The correct word should be "קטן" (katan), meaning "smaller than".
קובץ PSBT צריך להיות קטן מ-100 MiB
```

```
        <source>Can't draft transaction.</source>
        <translation>לא ניתן לשמור את העסקה כטיוטה.</translation>
    
YES, the translation is problematic because it does not accurately convey the meaning of the source text. The source text "Can't draft transaction" implies an inability to create a transaction in a draft state, whereas the translation "לא ניתן לשמור את העסקה כטיוטה" translates to "Cannot save the transaction as a draft". This is a subtle but important difference in meaning.

The correct translation should reflect the inability to *initiate* or *create* a draft transaction, not the inability to *save* it as a draft.

Correct translation: לא ניתן לנסח עסקה.
```

```
        <source>%s corrupt. Try using the wallet tool bitcoin-wallet to salvage or restoring a backup.</source>
        <translation>%s משובש. נסו להשתמש בכלי הארנק bitcoin-wallet כדי להציל או לשחזר מגיבוי..</translation>
    
YES - The Hebrew translation uses a period at the end of the sentence instead of the correct Hebrew punctuation mark, which is a period followed by a space. The correct punctuation is ". ".
%s משובש. נסו להשתמש בכלי הארנק bitcoin-wallet כדי להציל או לשחזר מגיבוי.
```

```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of pruned node)</source>
        <translation>גיזום: הסינכרון האחרון של הארנק עובר את היקף הנתונים שנגזמו. יש לבצע חידוש אידקסציה (נא להוריד את כל שרשרת הבלוקים שוב במקרה של צומת מקוצצת)</translation>
    
YES - The translation uses incorrect terminology for "reindex" and "pruned node". The Hebrew translation for "reindex" should be "reindex" and for "pruned node" should be "pruned node". The provided translation is: "גיזום: הסינכרון האחרון של הארנק עובר את היקף הנתונים שנגזמו. יש לבצע חידוש אינדקס (נא להוריד את כל שרשרת הבלוקים שוב במקרה של צומת מקוצצת)" which translates to "Pruning: The last wallet synchronization goes beyond the scope of the pruned data. Re-indexing must be performed (please download the entire blockchain again in case of a pruned node)".
Correct translation: "גיזום: הסינכרון האחרון של הארנק חורג מהנתונים המגזמים. עליך לבצע -reindex (להוריד מחדש את כל שרשרת הבלוקים במקרה של צומת מגזם)"
```

```
        <source>Unable to replay blocks. You will need to rebuild the database using -reindex-chainstate.</source>
        <translation>שידור-חוזר של הבלוקים לא הצליח. תצטרכו לבצע בנייה מחדש של מאגר הנתונים באמצעות הדגל reindex-chainstate-.</translation>
    
YES - The translation incorrectly uses the term "שידור-חוזר" (broadcast-repeat) instead of a more appropriate term for "replay". Additionally, the placement of the hyphen in "reindex-chainstate-" is incorrect.

Correct translation: "לא ניתן לשדר מחדש בלוקים. תצטרכו לבנות מחדש את מאגר הנתונים באמצעות -reindex-chainstate."
```

```
        <source>Cannot set -peerblockfilters without -blockfilterindex.</source>
        <translation>לא מצליח להגדיר את  -peerblockfilters ללא-blockfilterindex.</translation>
    
YES. The translation is problematic because it omits the hyphen before "blockfilterindex" and adds an unnecessary space between "ללא" and "-blockfilterindex".

NO
```

```
        <source>Config setting for %s only applied on %s network when in [%s] section.</source>
        <translation>הגדרות הקונפיג עבור %s מיושמות רק  %s הרשת כאשר בקבוצה [%s] .</translation>
    
YES - The translation has a prepositional phrase in the wrong order, which makes the sentence awkward. The word "only" is also misplaced.

Corrected translation: הגדרות הקונפיג עבור %s מיושמות רק ברשת %s כאשר בקבוצה [%s].
```

```
        <source>Could not find asmap file %s</source>
        <translation>  קובץ asmap %s לא נמצא</translation>
    
YES, The translation has leading whitespace.
קובץ asmap %s לא נמצא
```

```
        <source>Could not parse asmap file %s</source>
        <translation> קובץ asmap %s לא נפרס</translation>
    
YES - The Hebrew translation is missing the word "could not" or its equivalent.
Correct translation: לא ניתן היה לפענח את קובץ asmap %s
```

```
        <source>Error loading %s: Private keys can only be disabled during creation</source>
        <translation>שגיאת טעינה %s: מפתחות פרטיים ניתנים לניטרול רק בעת תהליך היצירה</translation>
    
YES: The Hebrew translation uses "ניטרול" (nitrul) which means "neutralization" or "disabling". However, the English word "disabled" in this context likely means "cannot be enabled" or "are inactive". "ניטרול" might be misleading as it could imply an active process of disabling, rather than a state of being unable to be enabled. A more accurate translation would convey that private keys can only be set during creation and not altered later.
Correct translation: שגיאת טעינה %s: ניתן להגדיר מפתחות פרטיים רק בעת היצירה
```

```
        <source>Error: Disk space is low for %s</source>
        <translation>שגיאה: שטח הדיסק קטן מדי עובר %s</translation>
    
YES, The Hebrew translation is incorrect. The word "עובר" (over) is not the correct translation for "for". The correct translation is "עבור" (for).

The correct translation is: שגיאה: שטח הדיסק קטן מדי עבור %s
```

```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>שגיאה: Keypool עבר את המכסה, קרא תחילה ל  keypoolrefill </translation>
    
YES: The translation contains a common error of not translating technical terms like "keypool" and "keypoolrefill". Additionally, the Hebrew word "עבר את המכסה" (passed the quota) is not the best translation for "ran out".

Correct translation: שגיאה: Keypool אזל, אנא קרא תחילה ל keypoolrefill
```

```
        <source>Ignoring duplicate -wallet %s.</source>
        <translation>מתעלם ארנק-כפול %s.</translation>
    
YES, The translation is not accurate. The word "duplicate" is translated as "כפול" (double) instead of "כפולה" (duplicate). Additionally, the word "wallet" is translated as "ארנק-כפול" (double wallet) which is not the correct translation.
The correct translation should be: מתעלם מהארנק הכפול %s.
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>מקטע הפתיח הוא שגוי או לא נמצא. תיקיית נתונים שגויה עבור הרשת?</translation>
    
YES - The translation is problematic because it mistranslates "genesis block" as "opening section" instead of "genesis block".

Correct translation: גוש בראשית שגוי או לא נמצא. תיקיית נתונים שגויה עבור הרשת?
```

```
        <source>Initialization sanity check failed. %s is shutting down.</source>
        <translation>איתחול של תהליך בדיקות השפיות נכשל. %s  בתהליך סגירה.</translation>
    
YES. The translation is problematic because of a misplaced word and awkward phrasing.

Here's a breakdown:

*   **Accuracy:** The core meaning is conveyed, but the phrasing is unnatural in Hebrew.
*   **Problematic Content:** The word "תהליך" (process) is repeated unnecessarily and the placement of "%s" is awkward.

**Correct Translation:**

איתחול בדיקות השפיות נכשל. %s נסגר.
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>אי תקינות כתובת  -onion או hostname: '%s'</translation>
    
YES - The Hebrew translation is grammatically incorrect. The phrase "אי תקינות כתובת" is unnatural. A more correct and natural phrasing would be "כתובת לא תקינה".

The correct translation should be:
כתובת לא תקינה -onion או hostname: '%s'
```

```
        <source>Invalid -proxy address or hostname: '%s'</source>
        <translation>אי תקינות כתובת -proxy או hostname: '%s'</translation>
    
YES, The translation is problematic because the Hebrew translation uses "אי תקינות" which translates to "inaccuracy" or "non-compliance". The English text implies that the provided address or hostname is not valid. The correct translation for "Invalid" in this context would be "לא תקין" or "שגוי".

The correct translation is: לא תקין כתובת proxy או hostname: '%s'
```

```
        <source>Invalid amount for -%s=&lt;amount&gt;: '%s'</source>
        <translation>סכום שגוי עבור ‎-%s=&lt;amount&gt;:‏ '%s'</translation>
    
YES. The translation contains a Hebrew character that is not standard in English.
The correct translation is: "Invalid amount for -%s=&lt;amount&gt;: '%s'"
```

```
        <source>Unable to bind to %s on this computer (bind returned error %s)</source>
        <translation>לא ניתן להתאגד עם הפתחה %s במחשב זה (פעולת האיגוד החזירה את השגיאה %s)</translation>
    
YES, The translation is problematic because the Hebrew word "הפתחה" (haftacha) does not accurately translate "address" in the context of Bitcoin. It has connotations of opening or unlocking, which is not relevant here. A more appropriate translation for "address" in this context would be "כתובת" (כתובת). Additionally, the phrasing "פעולת האיגוד החזירה את השגיאה" is a bit literal and could be slightly more natural.

Correct translation: לא ניתן להתאגד עם הכתובת %s במחשב זה (פעולת ה-bind החזירה את השגיאה %s)
```

```
        <source>Unable to bind to %s on this computer. %s is probably already running.</source>
        <translation>לא מצליח להתחבר אל %s על מחשב זה. %s  קרוב לודאי שכבר רץ.</translation>
    
YES - The word "running" is translated to "רץ" which in Hebrew means "running" but in the context of computers and programs it should be translated to "פועל" or "רץ". The correct translation is "לא מצליח להתחבר אל %s על מחשב זה. %s קרוב לודאי שכבר פועל."
```

```
        <source>Unknown network specified in -onlynet: '%s'</source>
        <translation>רשת לא ידועה צוינה דרך ‎-onlynet:‏ '%s'</translation>
    
YES, The translation contains an unnecessary character (‎) before the hyphen in '-onlynet'.
The correct translation should be: רשת לא ידועה צוינה דרך -onlynet: '%s'
```
</details>
