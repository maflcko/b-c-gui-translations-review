# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>he</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bhe%5D%20low%20quality)


```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>אירעה שגיאה משמעותית. נא לבדוק שניתן לכתוב כל קובץ ההגדרות או לנסות להריץ עם ‎-nosettings (ללא הגדרות).</translation>
    
YES  
The phrase "שגיאה משמעותית" is not the most accurate or natural way to say "fatal error" in Hebrew in this technical context. A better translation is "שגיאה קריטית" or "שגיאה קשה". Additionally, "כל קובץ ההגדרות" incorrectly contains the word "כל" ("any"/"every") which is not in the source and changes the meaning. The correct phrase should be "קובץ ההגדרות".

Correct translation:  
אירעה שגיאה קריטית. נא לבדוק שניתן לכתוב בקובץ ההגדרות, או לנסות להריץ עם ‌-nosettings (ללא הגדרות).
```

```
        <source>Load PSBT from file…</source>
        <translation>טעינת PBST מקובץ…</translation>
    
YES  
There is a typo in the translation: "PBST" should be "PSBT" to match the source text's abbreviation.  

Correct translation:  
טעינת PSBT מקובץ…
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>בקשת תשלומים (יצירה של קודים מסוג QR וסכימות כתובות משאב של :bitcoin)</translation>
    
YES  
The translation has awkward phrasing and includes an incorrect literal translation of "bitcoin: URIs" as "סכימות כתובות משאב של :bitcoin", which is unnatural in Hebrew. The term "bitcoin: URIs" refers to a URI scheme and should be transliterated or described more naturally. Also, "יצירה של קודים מסוג QR" is acceptable but could be smoother.

Correct translation:  
בקשת תשלומים (יוצרת קודי QR וקישורי bitcoin:)
```

```
        <source>Open a bitcoin: URI</source>
        <translation>פתיחת ביטקוין: כתובת משאב</translation>
    
YES  
The translation "פתיחת ביטקוין: כתובת משאב" literally means "Opening bitcoin: resource address," which is inaccurate and somewhat awkward in the given context. The original English phrase "Open a bitcoin: URI" likely refers to the action of opening a bitcoin URI (a specific type of link). A more accurate translation would preserve the technical term "URI" and convey the action of opening it.

Correct translation:  
פתח URI מסוג bitcoin:
```

```
        <source>Sent transaction</source>
        <translation>העברת שליחה</translation>
    
YES  
The translation "העברת שליחה" is not idiomatic Hebrew for "Sent transaction." It literally means "transfer of sending," which is redundant and unnatural. The usual and correct Hebrew phrase for "Sent transaction" in the context of Bitcoin or general financial transactions is "עסקה שנשלחה" or simply "עסקה שנשלחה" (transaction that was sent).

Correct translation:  
עסקה שנשלחה
```

```
        <source>Incoming transaction</source>
        <translation>העברת קבלה</translation>
    
YES  
The phrase "העברת קבלה" literally means "receipt transfer," which is not the common or accurate way to say "Incoming transaction" in Hebrew, especially in the Bitcoin context. The correct translation should be "עסקה נכנסת" or "העתק נכנס" but the most common and clear term is "עסקה נכנסת".

Correct translation:  
עסקה נכנסת
```

```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>הרשת תסרב לקבל הוצאת ביטקוינים במידה והם כבר נמצאים בהעברות אשר לא מוצגות עדיין.</translation>
    
YES  
The Hebrew translation is somewhat inaccurate and stylistically awkward. The original English discusses that attempts to spend bitcoins affected by transactions not yet displayed will be rejected by the network. The Hebrew translation incorrectly implies bitcoins that "are already in transfers not yet displayed," which is confusing and less precise.

A more accurate and clear translation would be:  
"הרשת תסרב לקבל הוצאה של ביטקוינים שהושפעו על ידי העברות שטרם הוצגו."
```

```
        <source>Spend unconfirmed change</source>
        <translation>עודף בלתי מאושר מההשקעה</translation>
    
YES  
The translation "עודף בלתי מאושר מההשקעה" literally means "unconfirmed surplus from the investment," which is incorrect and misleading in the Bitcoin context. The source phrase "Spend unconfirmed change" refers to spending the unconfirmed change amount in a Bitcoin transaction (change = leftover funds from a transaction), not any investment. The correct translation should accurately convey spending unconfirmed change funds.

Correct translation:  
"להוציא עודף בלתי מאושר"
```

```
        <source>Port:</source>
        <translation>פתחה:</translation>
    
YES  
The Hebrew translation "פתחה:" is incorrect for the English source "Port:". The word "Port" in the context of networking or Bitcoin typically refers to the network port, which in Hebrew is "פורט:".  
"פתחה" means "she opened" or "opening (feminine form)", which is unrelated and incorrect in this context.  

Correct translation:  
פורט:
```

```
        <source>Connect to the Bitcoin network through a separate SOCKS5 proxy for Tor onion services.</source>
        <translation>התחבר לרשת ביטקוין דרך פרוקסי נפרד SOCKS5 proxy לשרותי שכבות בצל (onion services).</translation>
    
YES  
The translation redundantly repeats the word "proxy" in English ("פרוקסי נפרד SOCKS5 proxy") which is inconsistent and awkward. Also, the phrase "לשרותי שכבות בצל" is inaccurate; the correct term for "onion services" in Hebrew related to Tor is "שירותי אוניון" or more commonly "שירותי טור אוניון". The parentheses with the English "onion services" should be removed or replaced for clarity.  

Correct translation:  
"התחבר לרשת ביטקוין דרך פרוקסי SOCKS5 נפרד לשירותי אוניון של טור."
```

```
        <source>URI handling</source>
        <translation>טיפול בכתובות</translation>
    
YES
The translation "טיפול בכתובות" means "handling addresses," which is broader and slightly different from "URI handling." The source specifically mentions "URI," which stands for Uniform Resource Identifier and is a standard term. The correct translation should explicitly include "URI" to preserve the technical meaning and avoid ambiguity.

Correct translation: טיפול ב-URI
```

```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>'//:bitcoin' אינה כתובת תקנית. נא להשתמש ב־"bitcoin:‎"‏ במקום.</translation>
    
YES  
The translation incorrectly reverses the URI scheme from 'bitcoin://' to '//:bitcoin', which could confuse users. Also, in the original English, 'bitcoin://' is indicated as invalid, but the translation implies the invalid string is '//:bitcoin'. The correction should keep 'bitcoin://' as is.

Correct translation:  
'bitcoin://' אינה URI תקני. נא להשתמש ב־"bitcoin:" במקום.
```

```
        <source>Ping Wait</source>
        <translation>פינג</translation>
    
YES  
The translation "פינג" only translates "Ping" but omits "Wait." The full phrase "Ping Wait" should be translated to convey both words. A correct translation would be:  
"המתנת פינג"
```

```
        <source>Please, review your transaction.</source>
        <extracomment>Text to prompt a user to review the details of the transaction they are attempting to send.</extracomment>
        <translation>נא לעבור על העסקה שלך, בבקשה.</translation>
    
YES  
The translation contains a minor stylistic and punctuation issue. In Hebrew, placing "בבקשה" (please) at the end with a comma before it is less natural. A more appropriate translation would put "בבקשה" at the beginning or omit the comma. Also, the common and more natural phrasing would be: "אנא עיין בעסקה שלך." or "אנא עיין בעסקה שלך בבקשה."  

Correct translation:  
אנא עיין בעסקה שלך.
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/לא מאומתים</translation>
    
YES  
The translation "%1/לא מאומתים" uses the plural form "לא מאומתים" (unconfirmed, plural masculine), which is incorrect here. The status refers to a single transaction, so the singular form "לא מאומת" should be used instead.  
  
Correct translation:  
%1/לא מאומת
```

```
        <source>User-defined intent/purpose of the transaction.</source>
        <translation>ייעוד/תכלית מגדר ע"י המשתמש של העסקה.</translation>
    
YES  
The phrase "מגדר ע"י המשתמש" is incorrect because "מגדר" means "gender" and does not correspond to "user-defined." The correct phrase is "הוגדר על ידי המשתמש" or "הוגדר ע"י המשתמש," meaning "defined by the user."  

Correct translation:  
ייעוד/תכלית שהוגדרה על ידי המשתמש של העסקה.
```

```
        <source>Exporting Successful</source>
        <translation>הייצוא נכשל</translation>
    
YES  
The Hebrew translation means "The export failed," which contradicts the English source "Exporting Successful."  

Correct translation:  
הייצוא הצליח
```

```
        <source>Unable to decode PSBT from clipboard (invalid base64)</source>
        <translation>לא ניתן לפענח PSBT מתוך לוח הגזירים (base64 שגוי)  </translation>
    
YES  
There is extra trailing whitespace at the end of the translation. Also, the term "base64" should be properly capitalized or transliterated consistently if desired. However, the main problem is the whitespace and a more natural phrasing would be:

Correct translation:  
לא ניתן לפענח PSBT מלוח הגזירים (base64 שגוי)
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>קובץ PSBT צריך להיות קטמן מ 100 MiB</translation>
    
YES  
The Hebrew word "קטמן" is incorrect; the correct word for "smaller" is "קטן". Also, there should be no spaces around the preposition "מ" in this context.  

Correct translation:  
קובץ PSBT צריך להיות קטן מ-100 MiB
```

```
        <source>%s corrupt. Try using the wallet tool bitcoin-wallet to salvage or restoring a backup.</source>
        <translation>%s משובש. נסו להשתמש בכלי הארנק bitcoin-wallet כדי להציל או לשחזר מגיבוי..</translation>
    
YES  
There is an extra period at the end of the Hebrew translation (".."). Also, "restoring a backup" is translated as "לשחזר מגיבוי" which is acceptable, but more precise would be "לשחזר מגיבוי" or simply "לשחזר מגיבוי" is fine. The structure is understandable.

Correct translation:  
%s משובש. נסו להשתמש בכלי הארנק bitcoin-wallet כדי להציל או לשחזר מגיבוי.
```

```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of pruned node)</source>
        <translation>גיזום: הסינכרון האחרון של הארנק עובר את היקף הנתונים שנגזמו. יש לבצע חידוש אידקסציה (נא להוריד את כל שרשרת הבלוקים שוב במקרה של צומת מקוצצת)</translation>
    
YES  
There is a spelling mistake in the Hebrew translation. The word "אידקסציה" is incorrect and should be "אינדקסציה". Also, the term "-reindex" should ideally remain in English or be enclosed in quotes or italicized as it is a command option, but leaving it as is can be acceptable.  

Correct translation:  
גיזום: הסינכרון האחרון של הארנק עובר את היקף הנתונים שנגזמו. יש לבצע חידוש אינדקסציה (נא להוריד את כל שרשרת הבלוקים שוב במקרה של צומת מקוצצת)
```

```
        <source>Unable to replay blocks. You will need to rebuild the database using -reindex-chainstate.</source>
        <translation>שידור-חוזר של הבלוקים לא הצליח. תצטרכו לבצע בנייה מחדש של מאגר הנתונים באמצעות הדגל reindex-chainstate-.</translation>
    
YES
The translation has a minor issue with the placement of the flag "-reindex-chainstate". The hyphen should precede "reindex-chainstate" without a trailing hyphen, mirroring the source. Additionally, it's better to place the flag exactly as in the source, which is "-reindex-chainstate", not "reindex-chainstate-".

Correct translation:
שידור חוזר של הבלוקים לא הצליח. תצטרכו לבצע בנייה מחדש של מאגר הנתונים באמצעות הדגל -reindex-chainstate.
```

```
        <source>Cannot set -peerblockfilters without -blockfilterindex.</source>
        <translation>לא מצליח להגדיר את  -peerblockfilters ללא-blockfilterindex.</translation>
    
YES  
There is a spacing issue and slight awkwardness in the Hebrew translation. The dash for the second parameter is attached without space, while the first one has a space before it. The correct translation should have consistent spacing and improved clarity:

Correct translation:  
לא ניתן להגדיר את -peerblockfilters ללא -blockfilterindex.
```

```
        <source>Config setting for %s only applied on %s network when in [%s] section.</source>
        <translation>הגדרות הקונפיג עבור %s מיושמות רק  %s הרשת כאשר בקבוצה [%s] .</translation>
    
YES
The translation has issues with word order and spacing. The phrase "רק  %s הרשת" is awkward and the spacing before "%s" is incorrect (double space), and "בקבוצה" is less appropriate than "בחלק" or "בסעיף" for "section" in this context.

Correct translation:
"הגדרה של %s חלה רק על הרשת %s כאשר נמצא בסעיף [%s]."
```

```
        <source>Could not find asmap file %s</source>
        <translation>  קובץ asmap %s לא נמצא</translation>
    
YES  
There is leading whitespace before the text in the translation, which is incorrect. Also, the phrase could be slightly improved for clarity and fluency in Hebrew by placing the file name at the end after the descriptor.

Correct translation:  
קובץ asmap %s לא נמצא
```

```
        <source>Could not parse asmap file %s</source>
        <translation> קובץ asmap %s לא נפרס</translation>
    
YES  
There is an extra leading space before the translation text. The format specifier %s is correctly preserved and the meaning is accurate. Removing the leading space will fix the formatting issue.

Correct translation:  
קובץ asmap %s לא נפרס
```

```
        <source>Error: Disk space is low for %s</source>
        <translation>שגיאה: שטח הדיסק קטן מדי עובר %s</translation>
    
YES  
The Hebrew translation has an incorrect phrasing with "עובר %s" which does not correspond to the source meaning "for %s". The correct preposition should be "עבור %s".  

Correct translation:  
שגיאה: שטח הדיסק נמוך מדי עבור %s
```

```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>שגיאה: Keypool עבר את המכסה, קרא תחילה ל  keypoolrefill </translation>
    
YES  
The translation contains spacing issues (unwanted spaces before and after Hebrew and English words, especially around "keypoolrefill"). The phrase "Keypool עבר את המכסה" is not very idiomatic in Hebrew; a better phrasing would be "מאגר המפתחות נגמר". Also, the English term "keypoolrefill" should have no spaces around it, as it is a function or command name.

Correct translation:  
שגיאה: מאגר המפתחות נגמר, אנא קרא תחילה ל-keypoolrefill
```

```
        <source>Ignoring duplicate -wallet %s.</source>
        <translation>מתעלם ארנק-כפול %s.</translation>
    
YES  
The translation is missing a preposition or connector to correctly convey "Ignoring duplicate -wallet %s." in Hebrew. Also, "ארנק-כפול" is a literal but unnatural phrasing for "duplicate wallet." A better phrase is "ארנק כפול" (without the hyphen) and the verb should be in the present tense with an object.

Correct translation:  
מתעלם מארנק כפול -%s.
```

```
        <source>Initialization sanity check failed. %s is shutting down.</source>
        <translation>איתחול של תהליך בדיקות השפיות נכשל. %s  בתהליך סגירה.</translation>
    
YES  
The Hebrew translation has a spacing issue: there are two spaces before "בתהליך סגירה." Also, the phrasing "בתהליך סגירה" is awkward and incomplete as a sentence. A more natural and complete translation would be:  
"בדיקת תקינות האתחול נכשלה. %s מתכוון לסגור את עצמו."  
or alternatively:  
"בדיקת תקינות האתחול נכשלה. %s מכבה את עצמו."  

Corrected translation:  
איתחול של תהליך בדיקות השפיות נכשל. %s סוגר את עצמו.
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>אי תקינות כתובת  -onion או hostname: '%s'</translation>
    
YES  
There is an unnecessary space before "-onion" in the translation, which is not present in the source. Also, "אי תקינות" is not the standard way to say "Invalid" when referring to an address or hostname; a better choice is "כתובת -onion או שם מארח לא תקינים: '%s'".

Correct translation:  
כתובת -onion או שם מארח לא תקינים: '%s'
```

```
        <source>Invalid -proxy address or hostname: '%s'</source>
        <translation>אי תקינות כתובת -proxy או hostname: '%s'</translation>
    
YES  
The Hebrew phrase "אי תקינות" is awkward and not standard for "Invalid" in this context. A more accurate translation would be "כתובת -proxy או שם מארח ('hostname') שגויה: '%s'". Also, the English term "hostname" is left untranslated but placed inside Hebrew text; it is better to use the Hebrew equivalent or clearly mark it if needed. There is no whitespace or format specifier issue.

Correct translation:  
כתובת -proxy או שם מארח שגויה: '%s'
```

```
        <source>Unable to bind to %s on this computer (bind returned error %s)</source>
        <translation>לא ניתן להתאגד עם הפתחה %s במחשב זה (פעולת האיגוד החזירה את השגיאה %s)</translation>
    
YES  
The Hebrew translation uses incorrect terms and phrasing. "לא ניתן להתאגד עם הפתחה" is not correct for "Unable to bind to" in a technical sense. The term "bind" in the context of networking or Bitcoin software should be translated as "לצרף" or "לקשור". Also, "הפתחה" is not appropriate; "כתובת" (address) should be used. The original uses "bind to %s", so %s likely refers to an address or endpoint.

Correct translation:  
לא ניתן לקשור ל-%s במחשב זה (פעולת הקשירה החזירה את השגיאה %s)
```
</details>
