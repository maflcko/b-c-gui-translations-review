# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ta</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bta%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation>முகவரியை மாற்ற ரைட் கிளிக் செய்யவும்</translation>
    
YES
The translation inaccurately renders "edit" as "மாற்ற" (change), which means "change" or "modify" rather than "edit". It also omits "label" from the translation, which should be included.

Correct translation:
முகவரி அல்லது பெயர்ச்சீட்டில் திருத்த ரைட்-கிளிக் செய்யவும்
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>பணப்பையை திறக்க, உங்கள் செயல்பாடு உங்கள் பணப்பை கடவுச்சொல்லை தேவை.</translation>
    
YES
The translation is somewhat confusing and does not accurately reflect the source. It reverses the subject ("your operation needs..." instead of "this operation needs...") and is less clear.

Correct translation:
இந்த செயல்பாட்டை செய்ய, உங்கள் பணப்பை கடவுச்சொல்லை வழங்கி பணப்பையை திறக்க வேண்டும்.
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>எச்சரிக்கை: உங்கள் பணப்பையை குறியாக்கி உங்கள் கடவுச்சொற்றொடரை இழந்தால், நீங்கள் உங்கள் பைட்கோனை இழக்கலாம்!</translation>
    
YES
The translation is understandable but inaccurate and downplays the importance. The original says you will "LOSE ALL OF YOUR BITCOINS", but the translation weakens it to "நீங்கள் உங்கள் பைட்கோனை இழக்கலாம்!" ("you may lose your Bitcoin"), using singular for Bitcoin and saying "may" instead of "will". Also, the bold tags (&lt;b&gt;...&lt;/b&gt;) are omitted.

Correct translation:
எச்சரிக்கை: உங்கள் பணப்பையை குறியாக்கி, உங்கள் கடவுச்சொற்றொடரை இழந்தால், நீங்கள் &lt;b&gt;உங்கள் அனைத்து பிட்காயின்களையும் இழந்து விடுவீர்கள்&lt;/b&gt;!
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>வாலட்டை பாதுகாக்க புதிய கடவுச்சொல்லை உல்லிடவும். பத்து அல்லது அதற்கு மேற்பட்ட எழுத்துகள் அல்லது எட்டு அல்லது அதற்கு மேற்பட்ட எழுத்துக்களை கடவுச்சொல்லாக பயன்படுத்தவும்.</translation>
    
YES
The translation is mostly accurate but slightly incorrect regarding "eight or more words"—it says "எட்டு ... எழுத்துக்களை" (eight or more characters) instead of "words." Additionally, the separation into two sentences loses the structure/clarity of the original.

Correct translation:
வாலட்டிற்காக புதிய கடவுச்சொல்லை உள்ளிடவும்.&lt;br/&gt;தயவுசெய்து &lt;b&gt;பத்து அல்லது அதற்கு அதிகமான சீரற்ற எழுத்துகள்&lt;/b&gt; அல்லது &lt;b&gt;எட்டு அல்லது அதற்கு அதிகமான சொற்கள்&lt;/b&gt; கொண்ட கடவுச்சொல்லை பயன்படுத்தவும்.
```

```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>பழைய கடவுச்சொல் மற்றும் புதிய கடுவுசொல்லை உள்ளிடுக.</translation>
    
YES
There is a typo in the translation: "கடுவுசொல்லை" should be "கடவுச்சொல்லை". Also, the translation omits the explicit mention that both old and new passphrases are for the wallet.

Correct translation:
பணப்பை için பழைய கடவுச்சொல் மற்றும் புதிய கடவுச்சொல்லை உள்ளிடவும்.
```

```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>வாலட்டை குறியாக்கம் செய்தால் மட்டும் உங்கள் பிட்காயினை வைரஸிடம் இருந்து பாதுகாக்க இயலாது.</translation>
    
YES
The translation uses "வாலட்டை" for "wallet" and "பிட்காயினை" for "bitcoins," which is acceptable as a transcription. However, "வைரஸ்" only refers to "virus," not broadly to "malware" (which covers all types of malicious software). Also, the original says "cannot fully protect," but the translation says "cannot protect at all" ("பாதுகாக்க இயலாது") rather than "cannot fully protect" ("முழுமையாக பாதுகாக்க முடியாது").

Correct translation:
உங்கள் வாலட்டை குறியாக்கம் செய்தாலும், உங்கள் பிட்காயின்கள் கணினியில் மால்வேர் தொற்று ஏற்பட்டால் திருடப்படுவதை முழுமையாகக் கவனிப்பது சாத்தியமல்ல.
```

```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>முக்கியமானது: உங்கள் பணப்பரிமாற்றத்தை நீங்கள் உருவாக்கிய முந்தைய காப்புப்பிரதி புதிதாக உருவாக்கப்பட்ட, மறைகுறியாக்கப்பட்ட பணப்பரிமாற்றத்துடன் மாற்றப்பட வேண்டும். பாதுகாப்பு காரணங்களுக்காக, நீங்கள் புதிய, மறைகுறியாக்கப்பட்ட பணப்பையைப் பயன்படுத்த ஆரம்பித்தவுடன், மறைகுறியாக்கப்பட்ட பணப்பல் கோப்பின் முந்தைய காப்புப்பிரதிகள் பயனற்றதாகிவிடும்.</translation>
    
YES
There are errors in meaning and terminology in the translation:
1. "wallet file" is inconsistently and incorrectly translated as "பணப்பரிமாற்றம்" (which means "transaction"), rather than "பணப்பை கோப்பு" or "பணப்பைச் ச(mcumbnail)ைப்பு".
2. "backups" as "காப்புப்பிரதி" is singular; the plural "காப்புப்பிரதிகள்" should be used consistently.
3. Last sentence erroneously says "மறைகுறியாக்கப்பட்ட பணப்பல் கோப்பின் முந்தைய காப்புப்பிரதிகள்" which mixes ideas. It is about the *unencrypted* wallet backups, not the encrypted ones.
4. Need improvement on fluency and terminology.

Correct translation:
முக்கியமானது: நீங்கள் உங்கள் பணப்பை கோப்பை ஏற்கனவே மேற்கொண்ட அனைத்து காப்புப்பிரதிகளும், தற்போது உருவாக்கப்பட்ட மறைகுறியாக்கப்பட்ட (encrypted) பணப்பை கோப்புடன் மாற்றப்பட வேண்டும். பாதுகாப்பு காரணங்களுக்காக, மறைகுறியாக்கப்படாத (unencrypted) பணப்பை கோப்பின் முந்தைய காப்புப்பிரதிகள், நீங்கள் புதிய மறைகுறியாக்கப்பட்ட பணப்பையைப் பயன்படுத்த ஆரம்பித்தவுடன் பயனற்றவையாகிவிடும்.
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>பணப்பைக் குறியாக்கத்திற்கு அனுப்பப்பட்ட கடவுச்சொல் தவறானது.</translation>
    
YES
The translation is understandable, but the phrase "பணப்பைக் குறியாக்கத்திற்கு அனுப்பப்பட்ட" is awkward and incorrect. A more natural and accurate translation would be:

Correct translation:
திரையில் உள்ள பணப்பை உள்நுழைவு கடவுச்சொல் தவறானது. 

Or, even better and direct:

பணப்பையை டிக்ரிப்ட் செய்ய உள்ளிடப்பட்ட கடவுச்சொல் தவறானது.
```

```
        <source>Wallet passphrase was successfully changed.</source>
        <translation>Wallet குறியாக்கம் தோல்வியடைந்தது</translation>
    
YES
The translation is incorrect. The English text says "Wallet passphrase was successfully changed.", but the Tamil translation says "Wallet encryption failed" ("Wallet குறியாக்கம் தோல்வியடைந்தது"), which is the opposite meaning.

Correct translation:
வாலெட் கடவுச்சொல் வெற்றிகரமாக மாற்றப்பட்டது.
```

```
        <source>Banned Until</source>
        <translation>வரை தடை செய்யப்பட்டது</translation>
    
YES
The translation "வரை தடை செய்யப்பட்டது" directly means "Banned has been until," which is awkward and not a natural way to convey "Banned Until" in Tamil. The meaning should be clear that it refers to the time or date up to which the ban is in effect.

Correct translation:
"தடை செய்யப்பட்டது முடிவடையும் வரை" or simply "தடை செய்யப்படும் வரை" or, for brevity and proper UI context, "தடை முடிவின் தேதி" (Ban End Date). 

Best fit:
தடை செய்யப்படும் வரை
```

```
        <source>Internal error</source>
        <translation>உள் எறர்</translation>
    
YES
The translation uses the informal and incorrect transliteration "உள் எறர்", which is not proper Tamil. "எறர்" is just a phonetic rendering of "error" and not a typically accepted term. A more suitable Tamil translation for "Internal error" would be:

Correct translation:
உள் குறைவு

Alternatively, "உள்ளகப் பிழை" is also commonly used for "Internal error".
```

```
        <source>%1 didn't yet exit safely…</source>
        <translation>%1இன்னும் பாதுகாப்பாக வெளியேரவில்லை ...</translation>
    
YES
There is a missing space between "%1" and the Tamil text. Additionally, the ellipsis at the end should be '…' (single character) instead of '...'. Also, the Tamil translation could be more natural.

Correct translation:
%1 இன்னும் பாதுகாப்பாக வெளியேறவில்லை…
```

```
        <source>Amount</source>
        <translation>விலை</translation>
    
YES
The translation "விலை" means "price" in Tamil, which is not the correct term for "amount" in the context of Bitcoin transactions. The term "தொகை" is more appropriate for "amount".

Correct translation:
தொகை
```

```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>ஒரு விக்கிபீடியா முகவரியை உள்ளிடவும் (எ.கா. %1)</translation>
    
YES
The translation incorrectly uses "விக்கிபீடியா" (Wikipedia) instead of "பிட்கொயின்" (Bitcoin). This is an erroneous substitution and changes the meaning.

Correct translation:
ஒரு பிட்கொயின் முகவரியை உள்ளிடவும் (உதாரணம்: %1)
```

```
        <source>None</source>
        <translation>யாரும்</translation>
    
YES
The translation "யாரும்" means "no one" (as in "no person") in Tamil, but the context is "None" (probably as a selectable option meaning "nothing" or "no selection"). The correct term should be "எதுவும் இல்லை" or simply "இல்லை".

Correct translation:
எதுவும் இல்லை
or
இல்லை
```

```
        <source>Browse transaction history</source>
        <translation>பணப்பை பொது கண்ணோட்டத்தை காட்டு</translation>
    
YES
The translation is inaccurate. The source says "Browse transaction history," but the translation says "Show wallet overview" ("பணப்பை பொது கண்ணோட்டத்தை காட்டு"), which is incorrect.

Correct translation:
பரிவர்த்தனை வரலாற்றை ஆராய்க
```

```
        <source>Send coins to a Bitcoin address</source>
        <translation>ஒரு விக்கிபீடியா முகவரிக்கு நாணயங்களை அனுப்பவும்</translation>
    
YES
The translation incorrectly uses "விக்கிபீடியா" (Wikipedia) instead of "பிட்காயின்" (Bitcoin). Also, "coins" can be translated as "நாணயங்கள்", and "address" as "முகவரி". The translation should directly refer to Bitcoin, not Wikipedia.

Correct translation:
ஒரு பிட்காயின் முகவரிக்கு நாணயங்களை அனுப்பவும்
```

```
        <source>Backup wallet to another location</source>
        <translation>வேறொரு இடத்திற்கு காப்புப் பெட்டகம்</translation>
    
YES
The translation is incomplete; it only says "wallet to another location" without conveying the action "backup." The term "காப்புப் பெட்டகம்" alone literally means "safe/vault" or "wallet," and does not mean "backup wallet." The verb “backup” (as in to create a backup) is missing.

Correct translation:
வேறொரு இடத்துக்குப் பற் பதி உருவாக்கவும் (or) பங்கிடவும்

Alternatively, for more clarity:
வாலட்டின் பின்பற்றுப் பிரதியை வேறு இடத்திற்கு எடுக்கவும்

Either would be contextually correct.
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>உங்கள் பிட்டினின் முகவரியுடன் செய்திகளை உங்களிடம் வைத்திருப்பதை நிரூபிக்க</translation>
    
YES
The Tamil translation is incomplete and inaccurate. It omits the verb and the instruction to "sign messages" using the Bitcoin address, and also "addresses" should be plural.

Correct translation:
உங்களது பிட்ட்காயின் முகவரிகளைப் பயன்படுத்தி செய்திகளுக்கு கையொப்பமிடுங்கள், இது அவற்றை உங்களுக்கு சொந்தமானவை என்று நிரூபிக்க உதவும்.
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>குறிப்பிடப்பட்ட விக்கிபீடியா முகவர்களுடன் கையொப்பமிடப்பட்டதை உறுதிப்படுத்த, செய்திகளை சரிபார்க்கவும்</translation>
    
YES
The translation is problematic for two reasons:
1. The translation wrongly refers to "விக்கிபீடியா" (Wikipedia) instead of "பிட்காயின்" (Bitcoin).
2. The wording can be improved for clarity and naturalness.

Correct translation:
குறிப்பிடப்பட்ட பிட்காயின் முகவர்களுடன் கையொப்பமிடப்பட்டுள்ளதை உறுதிப்படுத்த, செய்திகளை சரிபார்க்கவும்
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>கொடுப்பனவுகளை கோருதல் (QR குறியீடுகள் மற்றும் bitcoin உருவாக்குகிறது: URI கள்)</translation>
    
YES
The translation has issues:
1. "bitcoin உருவாக்குகிறது: URI கள்" incorrectly makes it seem like "bitcoin" is producing something. The original refers to generating "bitcoin: URIs".
2. There is excess spacing and a pluralization error: "URI கள்" should be "URIகளை".
3. The phrase is more naturally translated as "பணம் கேட்கும் கோரிக்கை (QR குறியீடுகள் மற்றும் bitcoin: URI களை உருவாக்குகிறது)" but better to keep the sentence accurate and simple.

Correct translation:
பணம் கோருதல் (QR குறியீடுகள் மற்றும் bitcoin: URIகளை உருவாக்குகிறது)
```

```
        <source>Up to date</source>
        <translation>தேதி வரை</translation>
    
YES
The translation "தேதி வரை" literally means "till date" or "until date," but "Up to date" in software/UI context usually means "நவீனமடைந்தது" or "இப்போதைய நிலை." The current translation is not idiomatic for this context.

Correct translation:
நவீனமடைந்தது
```

```
        <source>Sending addresses</source>
        <translation>முகவரிகள் அனுப்புகிறது</translation>
    
YES
The translation is incorrect. The given translation "முகவரிகள் அனுப்புகிறது" translates back as "addresses is sending", which is grammatically wrong and unclear in Tamil. It should refer to "addresses used for sending" (i.e., "sending addresses").

Correct translation:
அனுப்பும் முகவரிகள்
```

```
        <source>Open a bitcoin: URI</source>
        <translation>திற பிட்காயின்: URI</translation>
    
YES
The Tamil translation "திற பிட்காயின்: URI" is inaccurate and unnatural. The word "Open" should be translated as "திற" (which is correct), but the phrase "பிட்காயின்: URI" is awkward and does not match the natural usage in Tamil. The English format "bitcoin: URI" refers to a type of resource identifier, and the ":" should remain joined to "bitcoin" without an intervening space, and "URI" can either be transliterated or kept as-is if not commonly translated.

Correct translation:
பிட்காயின்: URI-ஐ திற

Explanation: 
- Retains the "bitcoin:" part as "பிட்காயின்:"
- The URI is left as-is, which is acceptable in technical contexts.
- The verb is more naturally placed last, as is common in Tamil sentence structure.
- Added "-ஐ" to mark the accusative case (object marker), making the sentence grammatically correct.
```

```
        <source>Amount:</source>
        <translation>விலை</translation>
    
YES
The translation "விலை" means "price" in Tamil, which is not the same as "amount". In the context of Bitcoin and finance, "Amount" should be translated as "தொகை".

Correct translation:
தொகை
```

```
        <source>(un)select all</source>
        <translation>(அனைத்தையும் தேர்வுநீக்கு)</translation>
    
YES
The translation "(அனைத்தையும் தேர்வுநீக்கு)" only covers "deselect all" (unselect all) and does not cover the meaning of both "select all" and "unselect all". The term "(un)select all" is typically used to indicate a toggle action between selecting and unselecting everything.

Correct translation:
(அனைத்தையும் தேர்வு/தேர்வுநீக்கு)

This properly represents both actions—Select all (அனைத்தையும் தேர்வு) and Deselect all (அனைத்தையும் தேர்வுநீக்கு).
```

```
        <source>Amount</source>
        <translation>விலை</translation>
    
YES
The translation "விலை" means "price" in Tamil, which is not the correct term for "amount" in the context of Bitcoin transactions. The term "தொகை" is more appropriate for "amount".

Correct translation:
தொகை
```

```
        <source>Received with address</source>
        <translation>முகவரி பெற்றார்</translation>
    
YES
The translation "முகவரி பெற்றார்" is incorrect. In Tamil, this means "address received (by)" or "address was received", which distorts the intended meaning. The correct translation in the context of Bitcoin ("Received with address" means the coins were received via a specific address) should be:

Correct translation:
முகவரியில் பெற்றதும்

Alternatively:
முகவரியில் பெறப்பட்டது

Either would properly convey "Received with address" in this context.
```

```
        <source>Copy amount</source>
        <translation>நகல் நகல்</translation>
    
YES
The translation "நகல் நகல்" is incorrect. It literally means "copy copy" and does not convey the intended meaning of "Copy amount". The correct translation should be:

மொத்தத்தை நகலெடுக்கவும்

Correct translation:
மொத்தத்தை நகலெடுக்கவும்
```

```
        <source>Copy quantity</source>
        <translation>அளவு அளவு</translation>
    
YES
The translation duplicates the word "அளவு" (quantity), resulting in "அளவு அளவு", which means "quantity quantity." This is incorrect.

Correct translation:
அளவை நகலெடு
```

```
        <source>Copy after fee</source>
        <translation>நகல் கட்டணம்</translation>
    
YES
The translation "நகல் கட்டணம்" means "copy fee" which inaccurately translates "Copy after fee". The correct meaning is to copy the amount remaining after the fee has been deducted. The translation does not reflect the "after fee" concept.

Correct translation:
கட்டணத்தைக் கழித்த பிறகு நகலெடு
```

```
        <source>Copy bytes</source>
        <translation>நகல் கட்டணம்</translation>
    
YES
The translation is incorrect. "நகல் கட்டணம்" means "copy fee," not "Copy bytes." The correct translation for "Copy bytes" in Tamil should be "பைட்டுகளை நகலெடு".

Correct translation:
பைட்டுகளை நகலெடு
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>முகவரி முகவரியுடன் தொடர்புடைய முகவரி முகவரி. முகவரிகள் அனுப்புவதற்கு இது மாற்றியமைக்கப்படலாம்.</translation>
    
YES
The translation is problematic. The word "முகவரி" (address) is unnecessarily repeated, making it redundant and confusing. The sentence is not clear and does not convey the original message accurately.

Correct translation:
இந்த முகவரி பட்டியல் உள்ளீட்டுடன் தொடர்புடைய முகவரி. இது அனுப்பும் முகவரிகளுக்காக மட்டுமே மாற்றியமைக்க முடியும்.
```

```
        <source>New sending address</source>
        <translation>முகவரி அனுப்பும் புதியது</translation>
    
YES
The translation is not natural and the word order is incorrect. "New sending address" should be translated as "புதிய அனுப்பும் முகவரி" in Tamil.

Correct translation:
புதிய அனுப்பும் முகவரி
```

```
        <source>Edit receiving address</source>
        <translation>முகவரியைப் பெறுதல் திருத்து</translation>
    
YES
The Tamil translation is incorrect and unnatural. The correct translation should convey "Edit the receiving address" (i.e., edit an address used for receiving funds). The given translation awkwardly phrases "to receive, edit address".

Correct translation:
பெறும் முகவரியை திருத்து
```

```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>உள்ளிட்ட முகவரி "%1" என்பது செல்லுபடியாகும் விக்கிபீடியா முகவரி அல்ல.</translation>
    
YES
The translation is problematic because it translates "Bitcoin address" as "விக்கிபீடியா முகவரி" (Wikipedia address), which is incorrect. It should be "பிட்ட்காயின் முகவரி" (Bitcoin address).

Correct translation:
உள்ளிடப்பட்ட முகவரி "%1" என்பது செல்லுபடியாகும் பிட்ட்காயின் முகவரி இல்லை.
```

```
        <source>Estimated time left until synced</source>
        <translation>ஒத்திசைக்கப்படும் வரை மதிப்பிடப்பட்ட நேரங்கள் உள்ளன</translation>
    
YES
The translation is somewhat erroneous and awkward. The source says "Estimated time left until synced," but the Tamil translation reads "ஒத்திசைக்கப்படும் வரை மதிப்பிடப்பட்ட நேரங்கள் உள்ளன" which literally means "There are estimated times until it will be synced." It's better to say "ஒத்திசைக்கப்படும் வரை மதிப்பிடப்பட்ட நேரம்" which means "Estimated time until synced." The plural "நேரங்கள்" and "உள்ளன" are inappropriate here.

Correct translation:
ஒத்திசைக்கப்படும் வரை மதிப்பிடப்பட்ட நேரம்
```

```
        <source>Prune block storage to</source>
        <translation>பிரவுன்  தடுப்பு சேமிப்பு</translation>
    
YES
The translation is incomplete and does not convey the meaning of "to" (which indicates a size or limit). "Prune" is also transliterated instead of translated. 

Correct translation:
தடுப்பு சேமிப்பை குறைத்து கொண்டிருக்க (to a size)
```

```
        <source>Allow incoming connections</source>
        <translation>Incomin  g இணைப்புகளை அனுமதிக்கவும்</translation>
    
YES
There is a typographical error: "Incomin  g" has an unnecessary space and is in English instead of Tamil. The translation should be entirely in Tamil.

Correct translation:
செயல்படுத்தும் இணைப்புகளை அனுமதிக்கவும்
```

```
        <source>Port:</source>
        <translation> போர்ட்:</translation>
    
YES
There is an unnecessary leading space before "போார்ட்:". There should be no space at the start of the translation.

Correct translation:
போர்்ட்:
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation> Taskbar க்கு பதிலாக தட்டில் குறைக்கவும்</translation>
    
YES
There is an unnecessary space at the beginning of the translation. Also, "tray" can be better translated as "System Tray" for clarity, "தட்டி" (thatti) is not a commonly used term for 'system tray' in Tamil; "சிஸ்டம் டிரே" is preferred. 

Correct translation:
பணிப் பட்டிக்குப் பதிலாக சிஸ்டம் டிரேவில் குறைக்கவும்
```

```
        <source>Minimize on close</source>
        <translation>எம்  நெருக்கமாக உள்ளமை</translation>
    
YES
The translation is incorrect. The provided Tamil translation ("எம்  நெருக்கமாக உள்ளமை") does not convey the meaning of "Minimize on close". There is also an unnecessary extra space after "எம்".

Correct translation:
மூடும்போது குறைத்து வைக்கவும்
```

```
        <source>Unit to show amounts in:</source>
        <translation> அளவு:</translation>
    
YES
The translation is incomplete and does not convey the full meaning of the source text. The phrase "Unit to show amounts in:" provides context that is missing in the translation, which only says "amount:".

Correct translation:
அளவை காண்பிக்க வேண்டிய அலகு:
```

```
        <source>The configuration file is used to specify advanced user options which override GUI settings. Additionally, any command-line options will override this configuration file.</source>
        <extracomment>Explanatory text about the priority order of instructions considered by client. The order from high to low being: command-line, configuration file, GUI settings.</extracomment>
        <translation>GUI அமைப்புகளை மேலெழுதக்கூடிய மேம்பட்ட பயனர் விருப்பங்களைக் குறிப்பிட கட்டமைப்பு கோப்பு பயன்படுத்தப்படுகிறது. கூடுதலாக, எந்த கட்டளை வரி விருப்பங்கள் இந்த கட்டமைப்பு கோப்பு புறக்கணிக்க வேண்டும்.</translation>
    
YES
There are issues in translation accuracy and clarity. The last sentence is grammatically incorrect and changes the meaning; it should state that command-line options override the configuration file, not that they "must ignore" it. Also, "override" is better translated as "மீறுகிறது" or similar terms for clarity.

Correct translation:
GUI அமைப்புகளை மீறக்கூடிய மேம்பட்ட பயனர் விருப்பங்களை குறிப்பிடும் வகையில் கட்டமைப்பு கோப்பு பயன்படுத்தப்படுகிறது. அதனைத் தவிர, எந்த கட்டளை வரி விருப்பங்களும் இந்த கட்டமைப்பு கோப்பை மீறும்.
```

```
        <source>Mined balance that has not yet matured</source>
        <translation>இன்னும் முதிர்ச்சியடைந்த மின்கல சமநிலை</translation>
    
YES
The translation in Tamil means "the matured mined balance", which is the opposite of the intended meaning "mined balance that has not yet matured".

Correct translation:
இன்னும் முதிர்ச்சி அடையாத மையப்பட்ட சமநிலை
```

```
        <source>Close</source>
        <translation>நெருக்கமான</translation>
    
YES
The Tamil translation "நெருக்கமான" means "close" as in "near" or "intimate", not "to close" as an action (e.g., closing a window). The correct translation for the verb "Close" in UI contexts is "மூடு".

Correct translation:
மூடு
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Bitcoin தொடங்க முடியாது: கிளிக் க்கு ஊதியம் கையாளுதல்</translation>
    
YES
The Tamil translation is awkward and not fully accurate. The phrase "கிளிக் க்கு ஊதியம் கையாளுதல்" is a word-for-word rendition and does not clearly convey the idea of a "click-to-pay handler" in technical context. Also, spacing around "க்கு" is incorrect; it should be one word.

Correct translation:
Bitcoin ஐத் தொடங்க முடியவில்லை: கிளிக்-பே செய்யும் நிரலை இயக்க முடியவில்லை
```

```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>'bitcoin: //' சரியான URI அல்ல. அதற்கு பதிலாக 'பிட்கின்:' பயன்படுத்தவும்.</translation>
    
YES
There are a couple of issues:
- There is an extra space in "'bitcoin: //'". It should be "'bitcoin://'" (no space).
- The translation says 'பிட்கின்:' for 'bitcoin:', but the commonly used transliteration for Bitcoin in Tamil is 'பிட்காயின்'. However, using 'bitcoin:' itself is often retained in technical usage.
- The rest of the translation is acceptable, but it's clearer and more standard if kept closer to the source.

Correct translation:
'bitcoin://' ஒரு சரியான URI அல்ல. அதற்கு பதிலாக 'bitcoin:' ஐ பயன்படுத்தவும்.
```

```
        <source>Resulting URI too long, try to reduce the text for label / message.</source>
        <translation>யு.ஐ.ஐ. முடிவுக்கு நீண்ட காலம், லேபிள் / செய்திக்கு உரைகளை குறைக்க முயற்சிக்கவும்.</translation>
    
YES
The translation is problematic. The English text is about the URI (Uniform Resource Identifier) being too long, not about a "long time" ("நீண்ட காலம்" means "long period/time" in Tamil). Also, "யு.ஐ.ஐ." is a literal transliteration of "URI", which is nonstandard in Tamil technical contexts, where "URI" is typically used as is or translated as "முகவரி".

Correct translation:
URI மிக நீளமாக உள்ளது, லேபிள் அல்லது செய்திக்கான உரையை குறைக்கும் முயற்சி செய்யவும்.
```

```
        <source>Last Receive</source>
        <translation>கடைசியாக பெறவும்</translation>
    
YES
The translation "கடைசியாக பெறவும்" literally means "Lastly, receive (imperative)", which is not appropriate for the context where "Last Receive" actually refers to the most recent time something was received (e.g., payment, data). The correct rendering should be noun-based, not imperative.

Correct translation:
கடைசியாக பெற்றது
```

```
        <source>None</source>
        <translation>யாரும்</translation>
    
YES
The translation "யாரும்" means "no one" (as in "no person") in Tamil, but the context is "None" (probably as a selectable option meaning "nothing" or "no selection"). The correct term should be "எதுவும் இல்லை" or simply "இல்லை".

Correct translation:
எதுவும் இல்லை
or
இல்லை
```

```
        <source>Executing command using "%1" wallet</source>
        <translation>கட்டளையை "%1" பணியகத்தை பயன்படுத்துகிறது</translation>
    
YES
The Tamil translation is inaccurate. The source sentence is "Executing command using "%1" wallet", which means an action is being performed now. The provided translation translates to "Using the \"%1\" wallet", missing the action of executing a command and is in the present continuous instead of present participle or passive.

Correct translation:
"%1" பணியகத்தை பயன்படுத்தி கட்டளை இயங்குகிறது

Or a more accurate passive construction:
"%1" பணியகத்தை பயன்படுத்தி கட்டளை இயக்கப்படுகிறது
```

```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>கோரிக்கைக்கு விருப்பமான தொகை. ஒரு குறிப்பிட்ட தொகையை கோர வேண்டாம் இந்த வெற்று அல்லது பூஜ்ஜியத்தை விடு.</translation>
    
YES
The translation is awkward and not entirely accurate. The second sentence lacks clarity and proper structure in Tamil. Specifically, "இந்த வெற்று அல்லது பூஜ்ஜியத்தை விடு" is not colloquial Tamil, and it doesn't clearly convey "Leave this empty or zero".

Correct translation:
கோரிக்கைக்கான விருப்பத்தேர்ந்த தொகை. ஒரு குறிப்பிட்ட தொகையை கோர விரும்பாவிட்டால், இதை வெறும்/பூஜ்ஜியமாக வையுங்கள்.
```

```
        <source>Show the selected request (does the same as double clicking an entry)</source>
        <translation>தேர்ந்தெடுக்கப்பட்ட கோரிக்கையை காட்டு (இரட்டை இடுகையை இரட்டை கிளிக் செய்தால்)</translation>
    
YES
The translation is problematic. The phrase "இரட்டை இடுகையை இரட்டை கிளிக் செய்தால்" translates to "if you double-click the double entry," which is incorrect and redundant. The correct meaning is "does the same as double clicking an entry."

Correct translation:
தேர்ந்தெடுக்கப்பட்ட கோரிக்கையை காட்டு (ஒரு பதிவை இரட்டை கிளிக் செய்வதற்கு சமமானது)
```

```
        <source>Copy URI</source>
        <translation>நகலை URI</translation>
    
YES
The translation "நகலை URI" is incorrect. "நகலை" means "copy" as a noun, not as a verb, and the phrasing is unnatural. The correct translation should use the verb form, and ideally translate "URI" as is (since it's a technical term).

Correct translation:
URI ஐ நகலெடு
```

```
        <source>Amount:</source>
        <translation>விலை</translation>
    
YES
The translation "விலை" means "price" in Tamil, which is not the same as "amount". In the context of Bitcoin and finance, "Amount" should be translated as "தொகை".

Correct translation:
தொகை
```

```
        <source>Copy URI</source>
        <translation>நகலை URI</translation>
    
YES
The translation "நகலை URI" is incorrect. "நகலை" means "copy" as a noun, not as a verb, and the phrasing is unnatural. The correct translation should use the verb form, and ideally translate "URI" as is (since it's a technical term).

Correct translation:
URI ஐ நகலெடு
```

```
        <source>Copy Address</source>
        <translation>நகலை விலாசம்</translation>
    
YES
The Tamil translation "நகலை விலாசம்" is incorrect. It means "copy replica/address" or "duplicate address," which does not convey the imperative "Copy Address" as a button label or command.

Correct translation:
முகவரியை நகலெடுக்க

This precisely means "Copy the address."
```

```
        <source>Amount:</source>
        <translation>விலை</translation>
    
YES
The translation "விலை" means "price" in Tamil, which is not the same as "amount". In the context of Bitcoin and finance, "Amount" should be translated as "தொகை".

Correct translation:
தொகை
```

```
        <source>Add Recipient</source>
        <translation>சேர்  பெறுக</translation>
    
YES
There is an unnecessary space between "சேர்" and "பெறுக". Also, "பெறுக" means "receive", which isn't correct in this context; "Add Recipient" should be translated as "பெறுநரை சேர்க்கவும்" or "பெறுநர் சேர்".

Correct translation:
பெறுநர் சேர்க்கவும்
or 
பெறுநர் சேர்
```

```
        <source>A too low fee might result in a never confirming transaction (read the tooltip)</source>
        <translation>ஒரு மிக குறைந்த கட்டணம் ஒரு உறுதி பரிவர்த்தனை விளைவாக (உதவிக்குறிப்பு வாசிக்க)</translation>
    
YES
The translation has grammar and meaning issues. The Tamil text doesn't accurately convey "might result in a never confirming transaction", and the phrase order is off. A more accurate translation is:

மிக குறைந்த கட்டணம் செலுத்துவது, பரிவர்த்தனை உறுதிப்படுத்தப்படாமல் இருக்க வழிவகுப்பதாக இருக்கலாம் (உதவிக்குறிப்பைப் படிக்கவும்)
```

```
        <source>Clear All</source>
        <translation>அழி அனைத்து</translation>
    
YES
The translation is understandable but not natural in Tamil. The phrase "அழி அனைத்து" is a literal word-for-word translation ("Delete all") instead of the more idiomatic or commonly used phrase for "Clear All". Also, the word order is unnatural in Tamil.

Correct translation:
அனைத்தையும் நீக்கு
```

```
        <source>Copy quantity</source>
        <translation>அளவு அளவு</translation>
    
YES
The translation duplicates the word "அளவு" (quantity), resulting in "அளவு அளவு", which means "quantity quantity." This is incorrect.

Correct translation:
அளவை நகலெடு
```

```
        <source>Copy amount</source>
        <translation>நகல் நகல்</translation>
    
YES
The translation "நகல் நகல்" is incorrect. It literally means "copy copy" and does not convey the intended meaning of "Copy amount". The correct translation should be:

மொத்தத்தை நகலெடுக்கவும்

Correct translation:
மொத்தத்தை நகலெடுக்கவும்
```

```
        <source>Copy after fee</source>
        <translation>நகல் கட்டணம்</translation>
    
YES
The translation "நகல் கட்டணம்" means "copy fee" which inaccurately translates "Copy after fee". The correct meaning is to copy the amount remaining after the fee has been deducted. The translation does not reflect the "after fee" concept.

Correct translation:
கட்டணத்தைக் கழித்த பிறகு நகலெடு
```

```
        <source>Copy bytes</source>
        <translation>நகல் கட்டணம்</translation>
    
YES
The translation is incorrect. "நகல் கட்டணம்" means "copy fee," not "Copy bytes." The correct translation for "Copy bytes" in Tamil should be "பைட்டுகளை நகலெடு".

Correct translation:
பைட்டுகளை நகலெடு
```

```
        <source>You can increase the fee later (signals Replace-By-Fee, BIP-125).</source>
        <translation>நீங்கள் கட்டணத்தை பின்னர் அதிகரிக்கலாம் (என்கிறது மாற்று கட்டணம், பிப்-125).</translation>
    
YES
The translation "என்கிறது மாற்று கட்டணம், பிப்-125" is an inaccurate rendering of "signals Replace-By-Fee, BIP-125." The phrase "என்கிறது" ("it says") is unnecessary, and "மாற்று கட்டணம்" is not a standard translation for "Replace-By-Fee." "BIP-125" should remain as-is, but "Replace-By-Fee" should be transliterated or explained as a concept relevant to Bitcoin.

Correct translation:
நீங்கள் கட்டணத்தை பின்னர் உயர்த்த முடியும் (Replace-By-Fee, BIP-125-ஐச் சுட்டுகிறது).
```

```
        <source>Send</source>
        <translation>அனுப்புவும்</translation>
    
YES
The translation "அனுப்புவும்" is incorrect for the English word "Send". The correct translation should be "அனுப்பு".

Explanation:
- "அனுப்புவும்" is a verb form indicating "will send" or is close to "and send", which is inappropriate in this menu/button context. 
- The menu action "Send" should be translated as the imperative "அனுப்பு" (meaning "Send" as a command).

Correct translation:
அனுப்பு
```

```
        <source>Clear All</source>
        <translation>அழி அனைத்து</translation>
    
YES
The translation is understandable but not natural in Tamil. The phrase "அழி அனைத்து" is a literal word-for-word translation ("Delete all") instead of the more idiomatic or commonly used phrase for "Clear All". Also, the word order is unnatural in Tamil.

Correct translation:
அனைத்தையும் நீக்கு
```

```
        <source>Amount</source>
        <translation>விலை</translation>
    
YES
The translation "விலை" means "price" in Tamil, which is not the correct term for "amount" in the context of Bitcoin transactions. The term "தொகை" is more appropriate for "amount".

Correct translation:
தொகை
```

```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>உறுதிப்படுத்துகிறது (%1 ன் %2 பரிந்துரைக்கப்பட்ட உறுதிப்படுத்தல்கல்)</translation>
    
YES
There is a spelling error and misuse of pluralization in the Tamil translation. The word "உறுதிப்படுத்தல்கல்" is incorrect; the correct plural form is "உறுதிப்படுத்தல்கள்". Also, it is better to use "உறுதிப்படுத்தல்கள்" to match the English "confirmations", and the phrase should indicate that %1 out of %2 recommended confirmations are happening.

Correct translation:
உறுதிப்படுத்துகிறது (%2 பரிந்துரைக்கப்பட்ட உறுதிப்படுத்தல்கள் இல் %1)
Alternatively, to keep closer to the English sentence order:
உறுதிப்படுத்துகிறது (%2 பரிந்துரைக்கப்பட்ட உறுதிப்படுத்தல்களில் %1)
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>இது பரிவர்த்தனைக் கட்டணம் ஆகும் அதன் வேறுபாடு தூசியை விட சிறியதாக இருந்தால் நீங்கள் அதை நிராகரிக்கலாம்.</translation>
    
YES
The translation is not accurate. The original sentence means "This is the transaction fee you may discard if change is smaller than dust at this level", specifically mentioning "change" in the Bitcoin transaction context—not "its difference" as the Tamil translation says. The structure is a bit off and introduces confusion.

Correct translation:
இது, இந்த நிலையில் மாறுதல் (change) தூசியை விடக் குறைவாக இருந்தால் நீங்கள் நிராகரிக்கக்கூடிய பரிவர்த்தனை கட்டணமாகும்.
```

```
        <source>Cannot set -peerblockfilters without -blockfilterindex.</source>
        <translation>-blockfiltersindex இல்லாத -peerblockfilters அமைப்பு முடியாது </translation>
    
YES
There is an error in the Tamil translation: "-blockfiltersindex" is a typographical mistake; the correct option is "-blockfilterindex". The Tamil sentence omits the definite nature ("இல்லாமல்" or "இல்லாத நிலையில்") of the prerequisite, and the pause at the end is missing. There is also a missing period at the end of the Tamil sentence, and there is an extra space at the end.

Correct translation:
-blockfilterindex இல்லாமல் -peerblockfilters ஐ அமைக்க முடியாது.
```
</details>

Number of issues: 73.
