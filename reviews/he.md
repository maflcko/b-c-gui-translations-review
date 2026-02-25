# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bhe%5D%20request)



<details><summary>he</summary>


<!-- cache_translation_check_he_b195f838c9ea5808ff03cec6edf0a93fcd15f982252a73633446b6a43efe8a28 -->
```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>אירעה שגיאה משמעותית. נא לבדוק שניתן לכתוב כל קובץ ההגדרות או לנסות להריץ עם ‎-nosettings (ללא הגדרות).</translation>
    
ERR
The translation inaccurately renders "A fatal error occurred" as "אירעה שגיאה משמעותית", which means "A significant error occurred". The word "משמעותית" means "significant" rather than "fatal" (קיומית or חמורה would be more appropriate for "fatal"). Additionally, "שניתן לכתוב כל קובץ ההגדרות" mistranslates "that settings file is writable" ("כל" means "any"/"all" rather than denoting the specific settings file).

Correct translation:
אירעה שגיאת מערכת חמורה. בדוק האם ניתן לכתוב לקובץ ההגדרות, או נסה להריץ עם ‎-nosettings (ללא הגדרות).
```

<!-- cache_translation_check_he_bb6bca6b71329ada82211be94dc6d9bce5a63e8e4ae1bc6ce9bb47909b2435be -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>גיבוי הארנק</translation>
    
ERR
The translation omits the ampersand (&), which is used for the shortcut key and should appear exactly once, typically before the first letter of the word to indicate the mnemonic. Also, the ellipsis (…) at the end of the source should be preserved in Hebrew as well.

Correct translation:
‏&גיבוי הארנק…
```

<!-- cache_translation_check_he_cc35446c3e8a39c20b508c6120a0981fa046705b4242bcfb563f44088da817e9 -->
```
        <source>&amp;Verify message…</source>
        <translation>&amp;אשר הודעה</translation>
    
ERR
The source "&amp;Verify message…" includes an ellipsis (…). The translation "&amp;אשר הודעה" omits the ellipsis, which is expected in the context to indicate further action. The translation would be improved by including the ellipsis at the end.

Correct translation:
&אשר הודעה…
```

<!-- cache_translation_check_he_db3add57a91bd69b06b7b94545f89567e3b0fd440208b9f1ea804244cd03991a -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>&amp;טעינת PBST מקובץ…</translation>
    
ERR
There is a typo in the translation: "PBST" should be "PSBT" to match the English source and the established term (Partially Signed Bitcoin Transaction). Also, the ellipsis character (…) is correctly maintained, and the ampersand is present.

Correct translation:
&טעינת PSBT מקובץ…
```

<!-- cache_translation_check_he_93f0c583596a27dcbac719c0dd94420f2a5e224b8979fa061efbe887d87a8ea9 -->
```
        <source>Open &amp;URI…</source>
        <translation>פתיחת הקישור</translation>
    
ERR
The translation omits the ampersand (&), which is used for shortcut keys, and the ellipsis (…). The source's meaning is "Open &URI…", but the translation just says "Open the link", which is not a close translation and loses the intent (specifically the term "URI" as a technical term).

Correct translation:
פתח &URI…
```

<!-- cache_translation_check_he_3bec04c3efa2a1a189c9c8539c11dcc33159c06dd707e2d07cc172cf6fbe07e1 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>העלאת PSBT מהקליפבורד...</translation>
    
ERR
The shortcut indicator '&' from the English source (&clipboard) is missing in the Hebrew translation. It must appear exactly once to indicate the access key.

Correct translation:
העלאת PSBT מה&amp;קליפבורד...
```

<!-- cache_translation_check_he_1500dd3492ed1321f70e6c1392a222b0f5a01e65cfa19ed78cfefc1670251ad8 -->
```
        <source>Open a bitcoin: URI</source>
        <translation>פתיחת ביטקוין: כתובת משאב</translation>
    
ERR
The translation is inaccurate and awkward. "פתיחת ביטקוין: כתובת משאב" literally says "Open Bitcoin: resource address", which is not how "bitcoin: URI" would be rendered in Hebrew user interfaces. The more standard and comprehensible translation is to use "URI Bitcoin" or even just "כתובת bitcoin:". The translation should match how URIs are referenced in Hebrew technical contexts.

Correct translation:
פתח כתובת bitcoin:
```

<!-- cache_translation_check_he_92b5049b8f09d8b8d02eba11d266d4ed27e64ef9dae56b73dae61a68907ee112 -->
```
        <source>Sent transaction</source>
        <translation>העברת שליחה</translation>
    
ERR  
The translation "העברת שליחה" is awkward and unnatural in Hebrew. The term "שליחה" means "sending," so the phrase translates as "sending of sending" or an awkward redundancy. A better and more accurate translation for "Sent transaction" is "עסקה שנשלחה" ("a transaction that was sent" or "sent transaction").  

Correct translation:  
עסקה שנשלחה
```

<!-- cache_translation_check_he_6e4b1d9ea5f3cfc0973303a19b0f2c96a9479139c7d7c98112b1aa8835afabae -->
```
        <source>Incoming transaction</source>
        <translation>העברת קבלה</translation>
    
ERR  
The translation "העברת קבלה" is incorrect. "העברת" means "transfer" and "קבלה" means "receipt" (as in a physical receipt), which together do not accurately convey "Incoming transaction" in the context of Bitcoin. The correct translation should be:

עסקה נכנסת

Correct translation:
עסקה נכנסת
```

<!-- cache_translation_check_he_12963b7b34bc3b21f27a8b38db4645bf15eb474150f594ee1e674d0e91e8757d -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>עודף &amp;בלתי מאושר מההשקעה</translation>
    
ERR
The translation misrepresents the original meaning. The source means "Spend unconfirmed change," referring to spending the 'change' from Bitcoin transactions that hasn't yet been confirmed. The translation implies "Unconfirmed change from the investment," which isn't accurate, and the placement of the ampersand is acceptable but the structure is misleading. Additionally, "מההשקעה" ("from the investment") should not appear here.

Correct translation:
להוציא עודף &amp;בלתי מאושר
```

<!-- cache_translation_check_he_efaae479017e87b40b82238ceeb2f742fdf6de66d11e435c5ea8a9d283654c24 -->
```
        <source>Connect to the Bitcoin network through a separate SOCKS5 proxy for Tor onion services.</source>
        <translation>התחבר לרשת ביטקוין דרך פרוקסי נפרד SOCKS5 proxy לשרותי שכבות בצל (onion services).</translation>
    
ERR
The translation has redundancy ("פרוקסי נפרד SOCKS5 proxy")—"proxy" is repeated in English and Hebrew, which is unnecessary. Also, "שרותי שכבות בצל" is a literal translation but "שירותי Onion" or "שירותי טור (Tor)" is more commonly used for Tor onion services in Hebrew tech context.

Correct translation:
התחבר לרשת הביטקוין דרך פרוקסי SOCKS5 נפרד עבור שירותי onion של Tor.
```

<!-- cache_translation_check_he_dfbe1852b6886238d185be8d0793907b39519f3a4a6ce95b005324593c0fd0d7 -->
```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>'//:bitcoin' אינה כתובת תקנית. נא להשתמש ב־"bitcoin:‎"‏ במקום.</translation>
    
ERR
The translation has two issues:
1. The order and format of '//:bitcoin' is incorrect. It should be 'bitcoin://', matching the source.
2. There is an unnecessary use of right-to-left and left-to-right punctuation. The translation also uses both single and double quotes inconsistently.

Correct translation:
'הכתובת ‎bitcoin://‎ אינה תקנית. נא להשתמש ב־bitcoin:‎ במקום.'
```

<!-- cache_translation_check_he_101f12234d530652e12eaad8977e153dbb8900e669733ee43df92a59195ff482 -->
```
        <source>Ping Wait</source>
        <translation>פינג</translation>
    
ERR
The translation omits the word "Wait", translating only "Ping". The correct translation should include both concepts to reflect "Ping Wait" (i.e., time waiting for a ping or pending ping response).

Correct translation:
המתנה לפינג
```

<!-- cache_translation_check_he_21226919d2ef385896101211e01a079a5cdc722041f31ac6180ff656680f3739 -->
```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/לא מאומתים</translation>
    
ERR
The translation "%1/לא מאומתים" means "%1/unverified" or "%1/not authenticated," but the correct context is "unconfirmed" (as in "not yet confirmed" in the blockchain). A more accurate translation would be "%1/לא מאושר" or "%1/לא אישור".

Correct translation:
%1/לא מאושר
```

<!-- cache_translation_check_he_32c6074739fcdedf9fc2c38e658b6f05d2c00630f173e2f7ff6adad61bff7655 -->
```
        <source>User-defined intent/purpose of the transaction.</source>
        <translation>ייעוד/תכלית מגדר ע"י המשתמש של העסקה.</translation>
    
ERR
The translation contains an error: the word "מגדר" is not appropriate; it seems to be a mistranslation (it means "gender" in Hebrew). Also, the phrase should be smoother, with a clear attribution to the user's intention.

Correct translation:
הכוונה/מטרה שהוגדרה על־ידי המשתמש עבור העסקה.
```

<!-- cache_translation_check_he_70dd21cf73202f0dbe3ce9cf870a1ee79bfa46b55937468119abdc2175e86565 -->
```
        <source>Exporting Successful</source>
        <translation>הייצוא נכשל</translation>
    
ERR  
The translation is incorrect. The Hebrew text means "The export failed," which is the opposite of "Exporting Successful."  

Correct translation:  
הייצוא הצליח
```

<!-- cache_translation_check_he_035854d8aff807e6f27f31ed2b5601ee0678248a4e35dc4cf24b0a9e63b7286c -->
```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>קובץ PSBT צריך להיות קטמן מ 100 MiB</translation>
    
ERR  
There is a spelling mistake in the Hebrew word "קטמן", which should be "קטן". Additionally, there should not be a space between "מ" and "100". The correct translation is:  
קובץ PSBT צריך להיות קטן מ-100 MiB
```

<!-- cache_translation_check_he_aafdf2dacb75b821ab644b6c48e20358e1adbc16789f2112d07290776734a98e -->
```
        <source>Please contribute if you find %s useful. Visit %s for further information about the software.</source>
        <translation>נא לשקול לתרום אם %s שימושי בשבילך. יש לבקר ב־ %s למידע נוסף על התוכנה.</translation>
    
ERR
The Hebrew is generally correct but has a spacing issue: the prefixed Hebrew hyphen (־) should not be followed by a space. Also the first sentence word order can be made more natural.

Corrected translation:
אם %s מועיל עבורך, נא לשקול לתרום. בקר ב-%s למידע נוסף על התוכנה.
```

<!-- cache_translation_check_he_0fb62d8115519697a3b469116d07e9663da9747516425d9b796e90c4f863e5a7 -->
```
        <source>Config setting for %s only applied on %s network when in [%s] section.</source>
        <translation>הגדרות הקונפיג עבור %s מיושמות רק  %s הרשת כאשר בקבוצה [%s] .</translation>
    
ERR
The translation contains a few issues:
1. The phrase "הגדרות הקונפיג עבור %s" translates to "the config settings for %s", but "קונפיג" is an unnecessary transliteration and should be "הגדרה" or "הגדרת תצורה".
2. There is an extra space after "רק", and the sentence structure is awkward.
3. The phrase "בשעה ש" should be used for "when", and "הרשת" (the network) is unnecessarily definite.

Correct translation:
הגדרת תצורה עבור %s תחול רק ברשת %s כאשר היא נמצאת במקטע [%s].
```

<!-- cache_translation_check_he_1d2ef11d46a85c77d1f8bee7c5ef3b99f428ff9b02f688f8d5767a3b9e22d83f -->
```
        <source>Could not find asmap file %s</source>
        <translation>  קובץ asmap %s לא נמצא</translation>
    
ERR
There is an unwanted leading whitespace at the start of the translation. The translation itself is accurate, but the extra leading space is a formatting issue.

Correct translation:
קובץ asmap %s לא נמצא
```

<!-- cache_translation_check_he_46f98d9615297a8b7ae452ea6844d96f1de32d7990918285b4a5c0deccf79f89 -->
```
        <source>Could not parse asmap file %s</source>
        <translation> קובץ asmap %s לא נפרס</translation>
    
ERR
There is a leading whitespace at the start of the translation and the structure is a bit awkward. Also, "לא נפרס" is not commonly used for "could not parse", a better Hebrew translation would use "לא ניתן היה לנתח את קובץ asmap ‎%s".

Correct translation:
לא ניתן היה לנתח את קובץ asmap ‎%s
```

<!-- cache_translation_check_he_c4db8c14b45afdf4025be94c1bfa32cb6ff7798f0a8f0ca54acd8df886ceba92 -->
```
        <source>Error: Disk space is low for %s</source>
        <translation>שגיאה: שטח הדיסק קטן מדי עובר %s</translation>
    
ERR
There is a typo in the Hebrew translation: "עובר" should be "עבור". Also, "קטן מדי" (too small) is common, but "שטח הדיסק אוזל" (disk space is running out) is a more natural expression in this context. However, to stick closely to the original:

Correct translation:
שגיאה: שטח הדיסק קטן מדי עבור %s
```

<!-- cache_translation_check_he_fd0a4ab3db07578a51db0c759d95e9545c08aa19212d13b444123da473509020 -->
```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>שגיאה: Keypool עבר את המכסה, קרא תחילה ל  keypoolrefill </translation>
    
ERR
There is an unnecessary space between "ל" and "keypoolrefill", and the phrase "Keypool עבר את המכסה" ("keypool exceeded its quota") is less accurate than directly indicating exhaustion or depletion ("אזל"). Additionally, the English idiom "ran out" is better rendered as "אזל".

Correct translation:
שגיאה: מאגר המפתחות אזל, יש להריץ תחילה את keypoolrefill
```

<!-- cache_translation_check_he_c731e369a3a030d1703ec461614291c0299e43ecc6d692f39da08caa3acea1e0 -->
```
        <source>Ignoring duplicate -wallet %s.</source>
        <translation>מתעלם ארנק-כפול %s.</translation>
    
ERR
The translation is inaccurate. The construction "מתעלם ארנק-כפול %s." is incorrect and unidiomatic in Hebrew. The phrase "duplicate -wallet" should be translated in a way that reflects the meaning: that duplicate specification of the wallet is being ignored.

Correct translation:
מתעלם מהגדרת ‎-wallet כפולה %s.
```

<!-- cache_translation_check_he_eb20c40ae82f6c6a3592b8e72d7f63d92cbdb0d9334da902467ff4bbe8cf3cab -->
```
        <source>Unable to bind to %s on this computer (bind returned error %s)</source>
        <translation>לא ניתן להתאגד עם הפתחה %s במחשב זה (פעולת האיגוד החזירה את השגיאה %s)</translation>
    
ERR
There are issues with word choice and some awkwardness. Specifically:
- "להתאגד" ("to unite/affiliate") is not the correct technical term for "bind" in the context of network programming. The accepted Hebrew term is "לקשר" or more neutrally "להיקשר".
- "הפתחה" is not a correct translation for %s. The %s can be a general network address or port. The word "הפתחה" is unclear.
- The translation of "bind" should refer to "לקשר ל־" (to bind to), and the translation of "returned error" is reasonable.

Correct translation:
לא ניתן להיקשר אל %s במחשב זה (פעולת ההיקשרות החזירה את השגיאה %s)
```
</details>

Number of issues: 25.
