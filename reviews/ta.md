# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>ta</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bta%5D%20request)


<!-- cache_translation_check_ta_3cfb0a703f52bc4919671e95ef89c3ea43c709752c774a35c8be7bde6ff9cdae -->
```
        <source>Right-click to edit address or label</source>
        <translation>முகவரியை மாற்ற ரைட் கிளிக் செய்யவும்</translation>
    
ERR
The translation inaccurately renders "edit" as "மாற்ற" (change), which means "change" or "modify" rather than "edit". It also omits "label" from the translation, which should be included.

Correct translation:
முகவரி அல்லது பெயர்ச்சீட்டில் திருத்த ரைட்-கிளிக் செய்யவும்
```

<!-- cache_translation_check_ta_809a5dc4897a03b5714ca9bdaa17bbb83c6426694b2a00a5990781c820353fb0 -->
```
        <source>&amp;Copy</source>
        <translation>&amp;காபி</translation>
    
ERR
The Tamil translation "&காபி" is problematic: "காபி" reads like "kaapi" (coffee) and is not the correct Tamil term for the UI action "Copy". Also the common Tamil UI translations use "நகல்" or "நகல் எடு" for "Copy".

Correct translation examples (keep the single & for the shortcut):
- &நகல்
or
- &நகல் எடு
```

<!-- cache_translation_check_ta_a5616347b8a4c087ff2be596da3293754b993ee6789e1eb53507177657da6c81 -->
```
        <source>C&amp;hoose</source>
        <translation>தே&amp;ர்வுசெய் </translation>
    
ERR
Issues:
- There's an extra trailing space after the translation text.
- In XML the ampersand is escaped as &amp; which is fine, but ensure exactly one shortcut marker exists (it does). The Tamil wording is acceptable.

Correct translation (no trailing space):
<translation>தே&amp;ர்வுசெய்</translation>
```

<!-- cache_translation_check_ta_9f19535b6f933ece432f9056849bf444de3e56c877ba6a9946418c66e0062d66 -->
```
        <source>Sending addresses - %1</source>
        <translation>முகவரிகள் அனுப்பப்படுகின்றன - %1</translation>
    
ERR
The Tamil translation reads more like "addresses are being sent - %1" (passive/progressive) rather than the intended label "Sending addresses - %1" (i.e. "addresses used for sending" or "sending addresses"). The format specifier %1 is preserved correctly.

Suggested correction:
அனுப்பும் முகவரிகள் - %1
```

<!-- cache_translation_check_ta_369157b9992e375c4e78e2b2ec32a1431ef8c7bdb4ac86a200e964ff457072ab -->
```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>பணப்பையை திறக்க, உங்கள் செயல்பாடு உங்கள் பணப்பை கடவுச்சொல்லை தேவை.</translation>
    
ERR
The translation is somewhat confusing and does not accurately reflect the source. It reverses the subject ("your operation needs..." instead of "this operation needs...") and is less clear.

Correct translation:
இந்த செயல்பாட்டை செய்ய, உங்கள் பணப்பை கடவுச்சொல்லை வழங்கி பணப்பையை திறக்க வேண்டும்.
```

<!-- cache_translation_check_ta_292d333a456c9aae2790e89d2ec13c89f28f08efa30b205b4a52bc1aab944613 -->
```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>எச்சரிக்கை: உங்கள் பணப்பையை குறியாக்கி உங்கள் கடவுச்சொற்றொடரை இழந்தால், நீங்கள் உங்கள் பைட்கோனை இழக்கலாம்!</translation>
    
ERR
The translation is understandable but inaccurate and downplays the importance. The original says you will "LOSE ALL OF YOUR BITCOINS", but the translation weakens it to "நீங்கள் உங்கள் பைட்கோனை இழக்கலாம்!" ("you may lose your Bitcoin"), using singular for Bitcoin and saying "may" instead of "will". Also, the bold tags (&lt;b&gt;...&lt;/b&gt;) are omitted.

Correct translation:
எச்சரிக்கை: உங்கள் பணப்பையை குறியாக்கி, உங்கள் கடவுச்சொற்றொடரை இழந்தால், நீங்கள் &lt;b&gt;உங்கள் அனைத்து பிட்காயின்களையும் இழந்து விடுவீர்கள்&lt;/b&gt;!
```

<!-- cache_translation_check_ta_7040392f8d7d23c53340f2332db889c479170fe57e8950642f9d79175bbb9935 -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>வாலட்டை பாதுகாக்க புதிய கடவுச்சொல்லை உல்லிடவும். பத்து அல்லது அதற்கு மேற்பட்ட எழுத்துகள் அல்லது எட்டு அல்லது அதற்கு மேற்பட்ட எழுத்துக்களை கடவுச்சொல்லாக பயன்படுத்தவும்.</translation>
    
ERR
The translation is mostly accurate but slightly incorrect regarding "eight or more words"—it says "எட்டு ... எழுத்துக்களை" (eight or more characters) instead of "words." Additionally, the separation into two sentences loses the structure/clarity of the original.

Correct translation:
வாலட்டிற்காக புதிய கடவுச்சொல்லை உள்ளிடவும்.&lt;br/&gt;தயவுசெய்து &lt;b&gt;பத்து அல்லது அதற்கு அதிகமான சீரற்ற எழுத்துகள்&lt;/b&gt; அல்லது &lt;b&gt;எட்டு அல்லது அதற்கு அதிகமான சொற்கள்&lt;/b&gt; கொண்ட கடவுச்சொல்லை பயன்படுத்தவும்.
```

<!-- cache_translation_check_ta_ca58efd786bb159bc9c1ad2ca94c532f6e6c9363f706e888a382006f4c0ae09f -->
```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>பழைய கடவுச்சொல் மற்றும் புதிய கடுவுசொல்லை உள்ளிடுக.</translation>
    
ERR
There is a typo in the translation: "கடுவுசொல்லை" should be "கடவுச்சொல்லை". Also, the translation omits the explicit mention that both old and new passphrases are for the wallet.

Correct translation:
பணப்பை için பழைய கடவுச்சொல் மற்றும் புதிய கடவுச்சொல்லை உள்ளிடவும்.
```

<!-- cache_translation_check_ta_730816b08b5ad9146636805e9f1c49f5c9340fd5fa2e456ae945de5958efc690 -->
```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>வாலட்டை குறியாக்கம் செய்தால் மட்டும் உங்கள் பிட்காயினை வைரஸிடம் இருந்து பாதுகாக்க இயலாது.</translation>
    
ERR
The translation uses "வாலட்டை" for "wallet" and "பிட்காயினை" for "bitcoins," which is acceptable as a transcription. However, "வைரஸ்" only refers to "virus," not broadly to "malware" (which covers all types of malicious software). Also, the original says "cannot fully protect," but the translation says "cannot protect at all" ("பாதுகாக்க இயலாது") rather than "cannot fully protect" ("முழுமையாக பாதுகாக்க முடியாது").

Correct translation:
உங்கள் வாலட்டை குறியாக்கம் செய்தாலும், உங்கள் பிட்காயின்கள் கணினியில் மால்வேர் தொற்று ஏற்பட்டால் திருடப்படுவதை முழுமையாகக் கவனிப்பது சாத்தியமல்ல.
```

<!-- cache_translation_check_ta_55e7bb08bc11858850e47330a03b05c90eefd020025b57546e01babe96cfc82c -->
```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>முக்கியமானது: உங்கள் பணப்பரிமாற்றத்தை நீங்கள் உருவாக்கிய முந்தைய காப்புப்பிரதி புதிதாக உருவாக்கப்பட்ட, மறைகுறியாக்கப்பட்ட பணப்பரிமாற்றத்துடன் மாற்றப்பட வேண்டும். பாதுகாப்பு காரணங்களுக்காக, நீங்கள் புதிய, மறைகுறியாக்கப்பட்ட பணப்பையைப் பயன்படுத்த ஆரம்பித்தவுடன், மறைகுறியாக்கப்பட்ட பணப்பல் கோப்பின் முந்தைய காப்புப்பிரதிகள் பயனற்றதாகிவிடும்.</translation>
    
ERR
There are errors in meaning and terminology in the translation:
1. "wallet file" is inconsistently and incorrectly translated as "பணப்பரிமாற்றம்" (which means "transaction"), rather than "பணப்பை கோப்பு" or "பணப்பைச் ச(mcumbnail)ைப்பு".
2. "backups" as "காப்புப்பிரதி" is singular; the plural "காப்புப்பிரதிகள்" should be used consistently.
3. Last sentence erroneously says "மறைகுறியாக்கப்பட்ட பணப்பல் கோப்பின் முந்தைய காப்புப்பிரதிகள்" which mixes ideas. It is about the *unencrypted* wallet backups, not the encrypted ones.
4. Need improvement on fluency and terminology.

Correct translation:
முக்கியமானது: நீங்கள் உங்கள் பணப்பை கோப்பை ஏற்கனவே மேற்கொண்ட அனைத்து காப்புப்பிரதிகளும், தற்போது உருவாக்கப்பட்ட மறைகுறியாக்கப்பட்ட (encrypted) பணப்பை கோப்புடன் மாற்றப்பட வேண்டும். பாதுகாப்பு காரணங்களுக்காக, மறைகுறியாக்கப்படாத (unencrypted) பணப்பை கோப்பின் முந்தைய காப்புப்பிரதிகள், நீங்கள் புதிய மறைகுறியாக்கப்பட்ட பணப்பையைப் பயன்படுத்த ஆரம்பித்தவுடன் பயனற்றவையாகிவிடும்.
```

<!-- cache_translation_check_ta_c522571e8b1cbc13d61df0483bced1acb3a3d1f2cdc7c4602d8672696f381f8b -->
```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>பணப்பைக் குறியாக்கத்திற்கு அனுப்பப்பட்ட கடவுச்சொல் தவறானது.</translation>
    
ERR
The translation is understandable, but the phrase "பணப்பைக் குறியாக்கத்திற்கு அனுப்பப்பட்ட" is awkward and incorrect. A more natural and accurate translation would be:

Correct translation:
திரையில் உள்ள பணப்பை உள்நுழைவு கடவுச்சொல் தவறானது. 

Or, even better and direct:

பணப்பையை டிக்ரிப்ட் செய்ய உள்ளிடப்பட்ட கடவுச்சொல் தவறானது.
```

<!-- cache_translation_check_ta_31ab9e811d896af554a26b4eaef1dc83a8d299c67097d6853566d3770eb67a06 -->
```
        <source>Wallet passphrase was successfully changed.</source>
        <translation>Wallet குறியாக்கம் தோல்வியடைந்தது</translation>
    
ERR
The translation is incorrect. The English text says "Wallet passphrase was successfully changed.", but the Tamil translation says "Wallet encryption failed" ("Wallet குறியாக்கம் தோல்வியடைந்தது"), which is the opposite meaning.

Correct translation:
வாலெட் கடவுச்சொல் வெற்றிகரமாக மாற்றப்பட்டது.
```

<!-- cache_translation_check_ta_d8181d4f2458bb7e6e49fe76ecd63fbdae5602260414ec7a6849b02c147f04ca -->
```
        <source>Banned Until</source>
        <translation>வரை தடை செய்யப்பட்டது</translation>
    
ERR
The translation "வரை தடை செய்யப்பட்டது" directly means "Banned has been until," which is awkward and not a natural way to convey "Banned Until" in Tamil. The meaning should be clear that it refers to the time or date up to which the ban is in effect.

Correct translation:
"தடை செய்யப்பட்டது முடிவடையும் வரை" or simply "தடை செய்யப்படும் வரை" or, for brevity and proper UI context, "தடை முடிவின் தேதி" (Ban End Date). 

Best fit:
தடை செய்யப்படும் வரை
```

<!-- cache_translation_check_ta_007bb7a36ee6b4ea585e4a14457d8a25037f237bb0a37775535784e57b8b8cf7 -->
```
        <source>Internal error</source>
        <translation>உள் எறர்</translation>
    
ERR
The translation uses the informal and incorrect transliteration "உள் எறர்", which is not proper Tamil. "எறர்" is just a phonetic rendering of "error" and not a typically accepted term. A more suitable Tamil translation for "Internal error" would be:

Correct translation:
உள் குறைவு

Alternatively, "உள்ளகப் பிழை" is also commonly used for "Internal error".
```

<!-- cache_translation_check_ta_6bcb3d6b93fa34b367e052498b6790a1c41ad0ad96230746d6f4df036c0f3785 -->
```
        <source>%1 didn't yet exit safely…</source>
        <translation>%1இன்னும் பாதுகாப்பாக வெளியேரவில்லை ...</translation>
    
ERR
There is a missing space between "%1" and the Tamil text. Additionally, the ellipsis at the end should be '…' (single character) instead of '...'. Also, the Tamil translation could be more natural.

Correct translation:
%1 இன்னும் பாதுகாப்பாக வெளியேறவில்லை…
```

<!-- cache_translation_check_ta_ef95ad511dc5bd38bc0110191de6d9a263cfa1c797f98464f6c00e3ccd52ccc2 -->
```
        <source>Amount</source>
        <translation>விலை</translation>
    
ERR
The translation "விலை" means "price" in Tamil, which is not the correct term for "amount" in the context of Bitcoin transactions. The term "தொகை" is more appropriate for "amount".

Correct translation:
தொகை
```

<!-- cache_translation_check_ta_dacadd15dd70aae75fad5bfcf35349448b29f6d304ab91be027236009964611e -->
```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>ஒரு விக்கிபீடியா முகவரியை உள்ளிடவும் (எ.கா. %1)</translation>
    
ERR
The translation incorrectly uses "விக்கிபீடியா" (Wikipedia) instead of "பிட்கொயின்" (Bitcoin). This is an erroneous substitution and changes the meaning.

Correct translation:
ஒரு பிட்கொயின் முகவரியை உள்ளிடவும் (உதாரணம்: %1)
```

<!-- cache_translation_check_ta_bcbe1595fe717493d923d117bfd5f7d6ccb84b54f4bbc853c56afbfbb173ee84 -->
```
        <source>None</source>
        <translation>யாரும்</translation>
    
ERR
The translation "யாரும்" means "no one" (as in "no person") in Tamil, but the context is "None" (probably as a selectable option meaning "nothing" or "no selection"). The correct term should be "எதுவும் இல்லை" or simply "இல்லை".

Correct translation:
எதுவும் இல்லை
or
இல்லை
```

<!-- cache_translation_check_ta_98599e39a1a86699614da4e8b3a2de1d62aa322905a9e00a742368a6a0ee1d15 -->
```
        <source>&amp;Overview</source>
        <translation>&amp;கண்ணோட்டம்</translation>
    
ERR
The Tamil word is misspelled. It should be "கண்ணோட்டம்" (overview). Keep the ampersand exactly once.

Correct translation:
&கண்ணோட்டம்
```

<!-- cache_translation_check_ta_ded693f1d3de039cc6ba3a018070fef05cc50fa39683ed2a4306d051e3198c22 -->
```
        <source>Browse transaction history</source>
        <translation>பணப்பை பொது கண்ணோட்டத்தை காட்டு</translation>
    
ERR
The translation is inaccurate. The source says "Browse transaction history," but the translation says "Show wallet overview" ("பணப்பை பொது கண்ணோட்டத்தை காட்டு"), which is incorrect.

Correct translation:
பரிவர்த்தனை வரலாற்றை ஆராய்க
```

<!-- cache_translation_check_ta_2cda72d36385dddfec0170ac1e01bb249b4ea0a6dca1ccaab9420cd24267568f -->
```
        <source>&amp;About %1</source>
        <translation>&amp; %1 பற்றி</translation>
    
ERR
The translation has the ampersand followed by a space ("& %1 பற்றி"). The ampersand marks the shortcut key and must not be separated by a space (placing it before a space could make the shortcut target the space character). The %1 placeholder is preserved, but the spacing is incorrect.

Correct translation:
&%1 பற்றி
```

<!-- cache_translation_check_ta_39bfd6e6e98f8143026d18edcc152cb9afd3e9e91960ed134cc53c712f71d65e -->
```
        <source>Send coins to a Bitcoin address</source>
        <translation>ஒரு விக்கிபீடியா முகவரிக்கு நாணயங்களை அனுப்பவும்</translation>
    
ERR
The translation incorrectly uses "விக்கிபீடியா" (Wikipedia) instead of "பிட்காயின்" (Bitcoin). Also, "coins" can be translated as "நாணயங்கள்", and "address" as "முகவரி". The translation should directly refer to Bitcoin, not Wikipedia.

Correct translation:
ஒரு பிட்காயின் முகவரிக்கு நாணயங்களை அனுப்பவும்
```

<!-- cache_translation_check_ta_03266b8aaf3403adc9867b839c5550ab037ab07522cd26924b19221e1ecc1478 -->
```
        <source>Backup wallet to another location</source>
        <translation>வேறொரு இடத்திற்கு காப்புப் பெட்டகம்</translation>
    
ERR
The translation is incomplete; it only says "wallet to another location" without conveying the action "backup." The term "காப்புப் பெட்டகம்" alone literally means "safe/vault" or "wallet," and does not mean "backup wallet." The verb “backup” (as in to create a backup) is missing.

Correct translation:
வேறொரு இடத்துக்குப் பற் பதி உருவாக்கவும் (or) பங்கிடவும்

Alternatively, for more clarity:
வாலட்டின் பின்பற்றுப் பிரதியை வேறு இடத்திற்கு எடுக்கவும்

Either would be contextually correct.
```

<!-- cache_translation_check_ta_28500237da88289bb94dba596ed510a33548e1d30e5d2388f091111284b33cc3 -->
```
        <source>&amp;Options…</source>
        <translation>&amp;விருப்பங்கள்</translation>
    
ERR
The translation correctly uses Tamil for "Options" and includes a single & accelerator, but it omits the trailing ellipsis (…) present in the source.

Correct translation:
&amp;விருப்பங்கள்…
```

<!-- cache_translation_check_ta_097227917ff562191645a0ab538563a7eff9cd30d7c98b439cf9af8d08b42db7 -->
```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>உங்கள் பிட்டினின் முகவரியுடன் செய்திகளை உங்களிடம் வைத்திருப்பதை நிரூபிக்க</translation>
    
ERR
The Tamil translation is incomplete and inaccurate. It omits the verb and the instruction to "sign messages" using the Bitcoin address, and also "addresses" should be plural.

Correct translation:
உங்களது பிட்ட்காயின் முகவரிகளைப் பயன்படுத்தி செய்திகளுக்கு கையொப்பமிடுங்கள், இது அவற்றை உங்களுக்கு சொந்தமானவை என்று நிரூபிக்க உதவும்.
```

<!-- cache_translation_check_ta_4406b44ef343c6156e9ae6365334f0e89bf4937c865f96c44d8ddb54c11c2c4d -->
```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>குறிப்பிடப்பட்ட விக்கிபீடியா முகவர்களுடன் கையொப்பமிடப்பட்டதை உறுதிப்படுத்த, செய்திகளை சரிபார்க்கவும்</translation>
    
ERR
The translation is problematic for two reasons:
1. The translation wrongly refers to "விக்கிபீடியா" (Wikipedia) instead of "பிட்காயின்" (Bitcoin).
2. The wording can be improved for clarity and naturalness.

Correct translation:
குறிப்பிடப்பட்ட பிட்காயின் முகவர்களுடன் கையொப்பமிடப்பட்டுள்ளதை உறுதிப்படுத்த, செய்திகளை சரிபார்க்கவும்
```

<!-- cache_translation_check_ta_e538ec831137d0a739eebe4eda2ee0569bbe05438a6c863e31897d73fc93bed8 -->
```
        <source>Open &amp;URI…</source>
        <translation>திறந்த &amp;URI...</translation>
    
ERR
The Tamil translation uses "திறந்த" (opened/past tense) which is incorrect for a menu command that should be an instruction ("Open…"). Also the source uses a single ellipsis character (…) while the translation uses three dots; better to match the original. The ampersand & (shortcut marker) is present but should appear exactly once and placed appropriately.

Suggested correction (keeping a single & and an ellipsis):
URI-ஐ &திற…

Or as a slightly more formal option:
&URI-ஐ திற…
```

<!-- cache_translation_check_ta_05a90bb7bdd0ff4ce144f672200c7614c0303761e81fe42a2dd495b24f252ca2 -->
```
        <source>&amp;File</source>
        <translation>&amp;கோப்புறை</translation>
    
ERR
The Tamil word "கோப்புறை" is uncommon for the standard "File" menu label — the usual UI translation is "கோப்பு" (or "கோப்புகள்" for plural). The ampersand is used correctly.

Correct translation:
&amp;கோப்பு
```

<!-- cache_translation_check_ta_b776094b8cc53b7e47a6a191b2c1fa175be957ed0611e33151c102ec79305a5e -->
```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>கொடுப்பனவுகளை கோருதல் (QR குறியீடுகள் மற்றும் bitcoin உருவாக்குகிறது: URI கள்)</translation>
    
ERR
The translation has issues:
1. "bitcoin உருவாக்குகிறது: URI கள்" incorrectly makes it seem like "bitcoin" is producing something. The original refers to generating "bitcoin: URIs".
2. There is excess spacing and a pluralization error: "URI கள்" should be "URIகளை".
3. The phrase is more naturally translated as "பணம் கேட்கும் கோரிக்கை (QR குறியீடுகள் மற்றும் bitcoin: URI களை உருவாக்குகிறது)" but better to keep the sentence accurate and simple.

Correct translation:
பணம் கோருதல் (QR குறியீடுகள் மற்றும் bitcoin: URIகளை உருவாக்குகிறது)
```

<!-- cache_translation_check_ta_3d3bd82a627cf82eea2f52f8a94f81c3795878cfc8e745b5b1793178f785a1d2 -->
```
        <source>&amp;Command-line options</source>
        <translation>&amp; கட்டளை வரி விருப்பங்கள்</translation>
    
ERR
The translation is correct in meaning ("command-line options") but has a formatting issue: the ampersand (&) used for the shortcut marker is followed by a space. The & should be directly before the character it marks (no space).

Correct translation:
&கட்டளை வரி விருப்பங்கள்
```

<!-- cache_translation_check_ta_3d30e9f9d5c66656ed442e37fbfda502186c9791caa9a5aec04a5e0bb680efdd -->
```
        <source>Up to date</source>
        <translation>தேதி வரை</translation>
    
ERR
The translation "தேதி வரை" literally means "till date" or "until date," but "Up to date" in software/UI context usually means "நவீனமடைந்தது" or "இப்போதைய நிலை." The current translation is not idiomatic for this context.

Correct translation:
நவீனமடைந்தது
```

<!-- cache_translation_check_ta_b0561675f450e52069abd51ce4b2ac1ab1edeb3ed41701bc8ee6e2c18ac549cd -->
```
        <source>&amp;Sending addresses</source>
        <translation>முகவரிகள் அனுப்புகிறது</translation>
    
ERR
The Tamil translation is grammatically incorrect and does not include the required shortcut ampersand (&). "முகவரிகள் அனுப்புகிறது" reads as "addresses sends" (wrong word order/verb form). A correct noun phrase for "Sending addresses" is "அனுப்பும் முகவரிகள்". Include the ampersand exactly once for the shortcut, e.g.:

Correct translation:
&அனுப்பும் முகவரிகள்
```

<!-- cache_translation_check_ta_23fff333a39b5f2061f380a0ab479854efc12e541c6cc9e13208d3b8f2d687d3 -->
```
        <source>&amp;Receiving addresses</source>
        <translation>முகவரிகள் பெறுதல்</translation>
    
ERR
The translation is missing the required shortcut ampersand (&) from the source. Also the Tamil phrase can be improved for clarity.

Suggested correction (with single & preserved):
&பெறுநர் முகவரிகள்
```

<!-- cache_translation_check_ta_722a9dca5c24c229102cdd6bde3316046f4a56b68e60dae1097c8b7d707361c7 -->
```
        <source>Open a bitcoin: URI</source>
        <translation>திற பிட்காயின்: URI</translation>
    
ERR
The Tamil translation "திற பிட்காயின்: URI" is inaccurate and unnatural. The word "Open" should be translated as "திற" (which is correct), but the phrase "பிட்காயின்: URI" is awkward and does not match the natural usage in Tamil. The English format "bitcoin: URI" refers to a type of resource identifier, and the ":" should remain joined to "bitcoin" without an intervening space, and "URI" can either be transliterated or kept as-is if not commonly translated.

Correct translation:
பிட்காயின்: URI-ஐ திற

Explanation: 
- Retains the "bitcoin:" part as "பிட்காயின்:"
- The URI is left as-is, which is acceptable in technical contexts.
- The verb is more naturally placed last, as is common in Tamil sentence structure.
- Added "-ஐ" to mark the accusative case (object marker), making the sentence grammatically correct.
```

<!-- cache_translation_check_ta_9dedbdea6938d478142681113b22bc941deac50f035ea9af6a2a800b0ae9603c -->
```
        <source>S&amp;how</source>
        <translation>காண்பி</translation>
    
ERR
The translation is missing the required shortcut ampersand (&). The source contains "S&amp;how" (one & indicating a shortcut); the Tamil translation must include exactly one & as well.

Suggested correction:
&காண்பி
```

<!-- cache_translation_check_ta_cb63f4c90b06299f488814207058923706ec530d59b190c7693d059c4b956b5b -->
```
        <source>Amount:</source>
        <translation>விலை</translation>
    
ERR
The translation "விலை" means "price" in Tamil, which is not the same as "amount". In the context of Bitcoin and finance, "Amount" should be translated as "தொகை".

Correct translation:
தொகை
```

<!-- cache_translation_check_ta_379e5a19cd7a1cbf3c88b7bc0598f187905c1fc8303adfb3085f5e61a0830f4c -->
```
        <source>(un)select all</source>
        <translation>(அனைத்தையும் தேர்வுநீக்கு)</translation>
    
ERR
The translation "(அனைத்தையும் தேர்வுநீக்கு)" only covers "deselect all" (unselect all) and does not cover the meaning of both "select all" and "unselect all". The term "(un)select all" is typically used to indicate a toggle action between selecting and unselecting everything.

Correct translation:
(அனைத்தையும் தேர்வு/தேர்வுநீக்கு)

This properly represents both actions—Select all (அனைத்தையும் தேர்வு) and Deselect all (அனைத்தையும் தேர்வுநீக்கு).
```

<!-- cache_translation_check_ta_ef95ad511dc5bd38bc0110191de6d9a263cfa1c797f98464f6c00e3ccd52ccc2 -->
```
        <source>Amount</source>
        <translation>விலை</translation>
    
ERR
The translation "விலை" means "price" in Tamil, which is not the correct term for "amount" in the context of Bitcoin transactions. The term "தொகை" is more appropriate for "amount".

Correct translation:
தொகை
```

<!-- cache_translation_check_ta_2d324f50fed381b007ac8bed1bf1c44ca00ec8df1b3c3f441fa4aaf144c7d519 -->
```
        <source>Received with address</source>
        <translation>முகவரி பெற்றார்</translation>
    
ERR
The translation "முகவரி பெற்றார்" is incorrect. In Tamil, this means "address received (by)" or "address was received", which distorts the intended meaning. The correct translation in the context of Bitcoin ("Received with address" means the coins were received via a specific address) should be:

Correct translation:
முகவரியில் பெற்றதும்

Alternatively:
முகவரியில் பெறப்பட்டது

Either would properly convey "Received with address" in this context.
```

<!-- cache_translation_check_ta_fa5d21eb0a181783483ba8267d976efa1a7755faa332ba3b087b9eb2cc0936be -->
```
        <source>Copy amount</source>
        <translation>நகல் நகல்</translation>
    
ERR
The translation "நகல் நகல்" is incorrect. It literally means "copy copy" and does not convey the intended meaning of "Copy amount". The correct translation should be:

மொத்தத்தை நகலெடுக்கவும்

Correct translation:
மொத்தத்தை நகலெடுக்கவும்
```

<!-- cache_translation_check_ta_1eee82f8173c320b9db4aac507fc402844d73172ca0485797f2b57f5b2b41ac9 -->
```
        <source>Copy quantity</source>
        <translation>அளவு அளவு</translation>
    
ERR
The translation duplicates the word "அளவு" (quantity), resulting in "அளவு அளவு", which means "quantity quantity." This is incorrect.

Correct translation:
அளவை நகலெடு
```

<!-- cache_translation_check_ta_016509eb0f2108b1b3008b97d72a188c250073acfca68fce51e558d081c94137 -->
```
        <source>Copy after fee</source>
        <translation>நகல் கட்டணம்</translation>
    
ERR
The translation "நகல் கட்டணம்" means "copy fee" which inaccurately translates "Copy after fee". The correct meaning is to copy the amount remaining after the fee has been deducted. The translation does not reflect the "after fee" concept.

Correct translation:
கட்டணத்தைக் கழித்த பிறகு நகலெடு
```

<!-- cache_translation_check_ta_2fb0328a88792e7f1a7c655b0e9843036f2ce04de99419a9567fa9a1fb7753a8 -->
```
        <source>Copy bytes</source>
        <translation>நகல் கட்டணம்</translation>
    
ERR
The translation is incorrect. "நகல் கட்டணம்" means "copy fee," not "Copy bytes." The correct translation for "Copy bytes" in Tamil should be "பைட்டுகளை நகலெடு".

Correct translation:
பைட்டுகளை நகலெடு
```

<!-- cache_translation_check_ta_41cf25bfa97209725f5e5910eb1511bec53f99b1d69ce0b25b0d363253ce29e1 -->
```
        <source>&amp;Label</source>
        <translation>&amp; சிட்டை</translation>
    
ERR
The Tamil translation is incorrect and has an extra space after the ampersand. "சிட்டை" is not the proper word for "Label" in this UI context, and the & should be attached to the label text (no stray space) to mark the shortcut. 

Correct translation:
&லேபிள்
```

<!-- cache_translation_check_ta_a2e003157af5674de748085daf217f76bfe5d77db0e1eac26fa01933c71dfc33 -->
```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>முகவரி முகவரியுடன் தொடர்புடைய முகவரி முகவரி. முகவரிகள் அனுப்புவதற்கு இது மாற்றியமைக்கப்படலாம்.</translation>
    
ERR
The translation is problematic. The word "முகவரி" (address) is unnecessarily repeated, making it redundant and confusing. The sentence is not clear and does not convey the original message accurately.

Correct translation:
இந்த முகவரி பட்டியல் உள்ளீட்டுடன் தொடர்புடைய முகவரி. இது அனுப்பும் முகவரிகளுக்காக மட்டுமே மாற்றியமைக்க முடியும்.
```

<!-- cache_translation_check_ta_38ea1cc1883d359e43454fff3ee73f564df32b225786d2076c144187083cef46 -->
```
        <source>New sending address</source>
        <translation>முகவரி அனுப்பும் புதியது</translation>
    
ERR
The translation is not natural and the word order is incorrect. "New sending address" should be translated as "புதிய அனுப்பும் முகவரி" in Tamil.

Correct translation:
புதிய அனுப்பும் முகவரி
```

<!-- cache_translation_check_ta_f990f50f9a3c16c29205075d8546290d81887a44aaeceb16fdde569fba3ec351 -->
```
        <source>Edit receiving address</source>
        <translation>முகவரியைப் பெறுதல் திருத்து</translation>
    
ERR
The Tamil translation is incorrect and unnatural. The correct translation should convey "Edit the receiving address" (i.e., edit an address used for receiving funds). The given translation awkwardly phrases "to receive, edit address".

Correct translation:
பெறும் முகவரியை திருத்து
```

<!-- cache_translation_check_ta_50d9d2c462b278542f36760b935a5a8d5e538f0ae668fc5f739b155747cbddf3 -->
```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>உள்ளிட்ட முகவரி "%1" என்பது செல்லுபடியாகும் விக்கிபீடியா முகவரி அல்ல.</translation>
    
ERR
The translation is problematic because it translates "Bitcoin address" as "விக்கிபீடியா முகவரி" (Wikipedia address), which is incorrect. It should be "பிட்ட்காயின் முகவரி" (Bitcoin address).

Correct translation:
உள்ளிடப்பட்ட முகவரி "%1" என்பது செல்லுபடியாகும் பிட்ட்காயின் முகவரி இல்லை.
```

<!-- cache_translation_check_ta_0238c92c66eb847658068ca555af6bea35ae1cbf0d4abd620a25b67eeb783267 -->
```
        <source>Estimated time left until synced</source>
        <translation>ஒத்திசைக்கப்படும் வரை மதிப்பிடப்பட்ட நேரங்கள் உள்ளன</translation>
    
ERR
The translation is somewhat erroneous and awkward. The source says "Estimated time left until synced," but the Tamil translation reads "ஒத்திசைக்கப்படும் வரை மதிப்பிடப்பட்ட நேரங்கள் உள்ளன" which literally means "There are estimated times until it will be synced." It's better to say "ஒத்திசைக்கப்படும் வரை மதிப்பிடப்பட்ட நேரம்" which means "Estimated time until synced." The plural "நேரங்கள்" and "உள்ளன" are inappropriate here.

Correct translation:
ஒத்திசைக்கப்படும் வரை மதிப்பிடப்பட்ட நேரம்
```

<!-- cache_translation_check_ta_fb44959f9201ac88a31596a8b34e6651b9d41d8539d461c4ff1a7ea7a9e4a547 -->
```
        <source>&amp;Start %1 on system login</source>
        <translation>கணினி உள்நுழைவில் %1 ஐத் தொடங்குங்கள்</translation>
    
ERR
The translation is correct Tamil and preserves %1, but it is missing the single '&' mnemonic from the source. Add the '&' exactly once (placed before a letter in the translation).

Correct translation:
கணினி உள்நுழைவில் %1 ஐத் &தொடங்குங்கள்
```

<!-- cache_translation_check_ta_a24599415c2d1365599d7979986fe63fb2772ab074cd72261f9613a7759a546e -->
```
        <source>Size of &amp;database cache</source>
        <translation>&amp; தரவுத்தள தேக்ககத்தின் அளவு</translation>
    
ERR
The Tamil contains a misspelling/incorrect rendering for "cache" ("தேக்ககத்தின்" is wrong). Also there's an extra space after the ampersand. The shortcut marker (&) should appear exactly once and directly precede the word (no stray space is preferred).

Correct translation:
&தரவுத்தள கேஷ் அளவு
```

<!-- cache_translation_check_ta_9903751df448c8ba65f165d8b8ee21ff80a715e9d978857082de7972bc555381 -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>ஸ்கிரிப்ட் &amp; சரிபார்ப்பு நூல்கள் எண்ணிக்கை</translation>
    
ERR
"நூல்கள்" is incorrect for "threads" (நூல்கள் means "books"). Use a Tamil term for computing threads such as "தொடர்கள்". The ampersand (shortcut) is present once, which is fine.

Correct translation:
ஸ்கிரிப்ட் &சரிபார்ப்பு தொடர்கள் எண்ணிக்கை
```

<!-- cache_translation_check_ta_1f5d54524aa17366eb82a613770f664f0772c8d934c7d85bbf2945d4331e2ef4 -->
```
        <source>Prune &amp;block storage to</source>
        <translation>பிரவுன் &amp; தடுப்பு சேமிப்பு</translation>
    
ERR
The translation is inaccurate and incomplete. It transliterates "Prune" as "பிரவுன்", omits the trailing "to" (வரை) from the source, and is unnatural Tamil.

Correct translation (preserving a single & for the shortcut):
&பிளாக் சேமிப்பை குறைக்க வரை
```

<!-- cache_translation_check_ta_ed6aa2e09751cdff60b25994756df1439d605cdea5cbf16aa7a4064a96cb11ab -->
```
        <source>Enable coin &amp;control features</source>
        <translation>நாணயம் மற்றும் கட்டுப்பாட்டு அம்சங்களை இயக்கவும்</translation>
    
ERR
The translation is understandable Tamil ("Enable coin and control features") but it omits the required single '&' shortcut marker present in the source. Also consider using the more natural spacing/wording with the ampersand placed before the "control" word.

Correct translation:
நாணய &கட்டுப்பாட்டு அம்சங்களை இயக்கவும்
```

<!-- cache_translation_check_ta_7e0d60f9f4263c59b3eb3fab7ab797587e2dbf6598a2aafc495d1f4b2fd78001 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>&amp; உறுதிப்படுத்தப்படாத மாற்றத்தை செலவழிக்கவும்</translation>
    
ERR
The translation is correct in meaning but has a formatting issue: there's an extra space between the '&' and the Tamil text. The ampersand (shortcut marker) should appear exactly once and directly adjacent to the labeled character (no stray space).

Corrected translation:
&உறுதிப்படுத்தப்படாத மாற்றத்தை செலவழிக்கவும்
```

<!-- cache_translation_check_ta_514c93efb212b533ccce29315ff3def9906af1f7ab9747dfef8a36fcb237ca40 -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Incomin &amp; g இணைப்புகளை அனுமதிக்கவும்</translation>
    
ERR
The translation mixes English and Tamil ("Incomin & g இணைப்புகளை அனுமதிக்கவும்"), leaves the source word untranslated, has an extra space around the ampersand, and doesn't place the shortcut (&) correctly. The ampersand must appear exactly once and there should be no stray spaces.

Correct translation (with a single & for the accelerator):
வரும் &இணைப்புகளை அனுமதிக்கவும்
```

<!-- cache_translation_check_ta_bdeb58a66ce7e4a5b79c42b80a0564c0920c0ed3070b39eb67b8a19928e6c190 -->
```
        <source>&amp;Connect through SOCKS5 proxy (default proxy):</source>
        <translation>&amp; SOCKS5 ப்ராக்ஸி மூலம் இணைக்கவும் (இயல்புநிலை ப்ராக்ஸி):</translation>
    
ERR
The translation is correct in meaning, but there's an extra space after the ampersand. The & should appear exactly once and typically directly adjacent to the label (no stray space).

Corrected translation:
&amp;SOCKS5 ப்ராக்ஸி மூலம்இணைக்கவும் (இயல்புநிலை ப்ராக்ஸி):
```

<!-- cache_translation_check_ta_4444cf9feaeb25d76b996b8b20e122e463fef72e8acf20af872cca7131ee7f4e -->
```
        <source>Proxy &amp;IP:</source>
        <translation>ப்ராக்சி ஐ பி:</translation>
    
ERR
The translation is missing the shortcut marker (&) and introduces an unintended space between the letters for "IP" (ஐ பி). The source contains "&" (used for shortcut) and it must appear exactly once in the translation. 

Correct translation (keep ampersand and no extra spaces):
ப்ராக்சி &IP:
```

<!-- cache_translation_check_ta_c882435e19aa0c3dc1d7f82f189ffc2691324018425cf57a55982d059096e257 -->
```
        <source>&amp;Port:</source>
        <translation>&amp; போர்ட்:</translation>
    
ERR
Issues:
- There's an extra space between '&' and the word. The '&' (shortcut marker) should appear exactly once and can be adjacent to the following character (commonly placed directly before the letter used as the shortcut).
- Minor orthography: the Tamil word is better written as "போர்ட்" rather than "போர்ட்".

Correct translation:
&amp;போர்ட்:
```

<!-- cache_translation_check_ta_afa8c0eda1e91de040c562f52b3ff317d2d056d5820fcbfbcb07686ebc2b5d60 -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>&amp; Taskbar க்கு பதிலாக தட்டில் குறைக்கவும்</translation>
    
ERR
Problems:
- The Tamil word "தட்டில்" literally means "on a plate" and is not an appropriate translation for "tray" in the UI sense (system tray). 
- There's an extra space after the ampersand ("& Taskbar..."); the & should be present exactly once but should not have stray spacing immediately after it.
- Prefer more natural Tamil word order/phrasing for "minimize to the tray instead of the taskbar".

Suggested correct translation (keeps single & and uses appropriate wording):
&Taskbar-ஐ விட சிஸ்டம் ட்ரேவில் குறைக்கவும்
```

<!-- cache_translation_check_ta_fc431a8ea4977f0c6f447af60676ba7109ba56e1f514f744ccb216df4cf2d0e2 -->
```
        <source>M&amp;inimize on close</source>
        <translation>எம் &amp; நெருக்கமாக உள்ளமை</translation>
    
ERR
The Tamil translation is incorrect/unnatural. "எம் &amp; நெருக்கமாக உள்ளமை" is not a correct rendering of "Minimize on close" and the wording is odd.

Keep exactly one & for the shortcut. A natural Tamil UI translation would be:

Correct translation:
&amp;மூடும்போது சுருக்கவும்
```

<!-- cache_translation_check_ta_a0996c464c3e85582ea0eac41499f959cdd304136c3a23fc2ff1cbf1365e93c9 -->
```
        <source>&amp;Unit to show amounts in:</source>
        <translation>&amp; அளவு:</translation>
    
ERR
The translation "& அளவு:" is too short and loses the meaning "Unit to show amounts in:" (it also has an extra space after '&'). Keep the '&' present exactly once and convey that this is the unit used to display amounts.

Correct translation:
&அளவுகளை காண்பிக்க அலகு:
```

<!-- cache_translation_check_ta_fb7f5204c6172a430795adb6a0d3f8d7ac7db45b18122de07728688ff22e4645 -->
```
        <source>The configuration file is used to specify advanced user options which override GUI settings. Additionally, any command-line options will override this configuration file.</source>
        <extracomment>Explanatory text about the priority order of instructions considered by client. The order from high to low being: command-line, configuration file, GUI settings.</extracomment>
        <translation>GUI அமைப்புகளை மேலெழுதக்கூடிய மேம்பட்ட பயனர் விருப்பங்களைக் குறிப்பிட கட்டமைப்பு கோப்பு பயன்படுத்தப்படுகிறது. கூடுதலாக, எந்த கட்டளை வரி விருப்பங்கள் இந்த கட்டமைப்பு கோப்பு புறக்கணிக்க வேண்டும்.</translation>
    
ERR
There are issues in translation accuracy and clarity. The last sentence is grammatically incorrect and changes the meaning; it should state that command-line options override the configuration file, not that they "must ignore" it. Also, "override" is better translated as "மீறுகிறது" or similar terms for clarity.

Correct translation:
GUI அமைப்புகளை மீறக்கூடிய மேம்பட்ட பயனர் விருப்பங்களை குறிப்பிடும் வகையில் கட்டமைப்பு கோப்பு பயன்படுத்தப்படுகிறது. அதனைத் தவிர, எந்த கட்டளை வரி விருப்பங்களும் இந்த கட்டமைப்பு கோப்பை மீறும்.
```

<!-- cache_translation_check_ta_e7f3b1789dd0ed3ed2670994b4c7490dbb9b64dabc8a249471f6ff6ba0982330 -->
```
        <source>Mined balance that has not yet matured</source>
        <translation>இன்னும் முதிர்ச்சியடைந்த மின்கல சமநிலை</translation>
    
ERR
The translation in Tamil means "the matured mined balance", which is the opposite of the intended meaning "mined balance that has not yet matured".

Correct translation:
இன்னும் முதிர்ச்சி அடையாத மையப்பட்ட சமநிலை
```

<!-- cache_translation_check_ta_95d8ced87f37b6572c6667fba22942468907482f215c61a113b62ab15adac0a5 -->
```
        <source>Close</source>
        <translation>நெருக்கமான</translation>
    
ERR
The Tamil translation "நெருக்கமான" means "close" as in "near" or "intimate", not "to close" as an action (e.g., closing a window). The correct translation for the verb "Close" in UI contexts is "மூடு".

Correct translation:
மூடு
```

<!-- cache_translation_check_ta_eafe742856fb6bd04c4ce214a23635119280a7f9da9cd2d1670017c00781dedc -->
```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Bitcoin தொடங்க முடியாது: கிளிக் க்கு ஊதியம் கையாளுதல்</translation>
    
ERR
The Tamil translation is awkward and not fully accurate. The phrase "கிளிக் க்கு ஊதியம் கையாளுதல்" is a word-for-word rendition and does not clearly convey the idea of a "click-to-pay handler" in technical context. Also, spacing around "க்கு" is incorrect; it should be one word.

Correct translation:
Bitcoin ஐத் தொடங்க முடியவில்லை: கிளிக்-பே செய்யும் நிரலை இயக்க முடியவில்லை
```

<!-- cache_translation_check_ta_36db8e2db05810b27b886da11bf55401a4f18ccabda25f32243d72e97a59f9c6 -->
```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>'bitcoin: //' சரியான URI அல்ல. அதற்கு பதிலாக 'பிட்கின்:' பயன்படுத்தவும்.</translation>
    
ERR
There are a couple of issues:
- There is an extra space in "'bitcoin: //'". It should be "'bitcoin://'" (no space).
- The translation says 'பிட்கின்:' for 'bitcoin:', but the commonly used transliteration for Bitcoin in Tamil is 'பிட்காயின்'. However, using 'bitcoin:' itself is often retained in technical usage.
- The rest of the translation is acceptable, but it's clearer and more standard if kept closer to the source.

Correct translation:
'bitcoin://' ஒரு சரியான URI அல்ல. அதற்கு பதிலாக 'bitcoin:' ஐ பயன்படுத்தவும்.
```

<!-- cache_translation_check_ta_fcfd9ccebff90eae739fb772b5f6027925af571e97c1545042c7c4cea13ae0e6 -->
```
        <source>Resulting URI too long, try to reduce the text for label / message.</source>
        <translation>யு.ஐ.ஐ. முடிவுக்கு நீண்ட காலம், லேபிள் / செய்திக்கு உரைகளை குறைக்க முயற்சிக்கவும்.</translation>
    
ERR
The translation is problematic. The English text is about the URI (Uniform Resource Identifier) being too long, not about a "long time" ("நீண்ட காலம்" means "long period/time" in Tamil). Also, "யு.ஐ.ஐ." is a literal transliteration of "URI", which is nonstandard in Tamil technical contexts, where "URI" is typically used as is or translated as "முகவரி".

Correct translation:
URI மிக நீளமாக உள்ளது, லேபிள் அல்லது செய்திக்கான உரையை குறைக்கும் முயற்சி செய்யவும்.
```

<!-- cache_translation_check_ta_01bafc05495a211d32cb8bbecfe4c7a6468c72f51c4d2eaf9f5230d01650e1cd -->
```
        <source>&amp;Reset</source>
        <translation>&amp; மீட்டமை</translation>
    
ERR
The Tamil translation is correct in meaning ("மீட்டமை" = "Reset"), but there is an extra space after the ampersand. The & should appear exactly once and not be separated by a space from the text.

Correct translation:
&amp;மீட்டமை
```

<!-- cache_translation_check_ta_a056115fe3f01e6946ff21526399d3c76e74cd3852fe977274ff35e7eb9ee6ad -->
```
        <source>&amp;Peers</source>
        <translation>&amp;சக</translation>
    
ERR
The translation "&சக" is not a natural Tamil rendering of "Peers" (it may be unclear or incorrect). The ampersand is used correctly, but the word choice is problematic.

Suggested correct translation:
&பியர்கள்
```

<!-- cache_translation_check_ta_cd7746e837b41453f32b6896c7ac09d1ae373256303e865655b7dc19d7598949 -->
```
        <source>Last Receive</source>
        <translation>கடைசியாக பெறவும்</translation>
    
ERR
The translation "கடைசியாக பெறவும்" literally means "Lastly, receive (imperative)", which is not appropriate for the context where "Last Receive" actually refers to the most recent time something was received (e.g., payment, data). The correct rendering should be noun-based, not imperative.

Correct translation:
கடைசியாக பெற்றது
```

<!-- cache_translation_check_ta_de18ac6a8f97d496d88fbec4a8a40009c151ebd59958e943d0867a152d3887f2 -->
```
        <source>&amp;Console</source>
        <translation>&amp;பணியகம்</translation>
    
ERR
The Tamil translation "&பணியகம்" means "office" (or workplace), which is not an appropriate rendering of the UI term "Console". The ampersand is present correctly, but the semantic translation is incorrect.

Suggested correction:
&கான்சோல்
```

<!-- cache_translation_check_ta_75328b8620451f267185888d337bb24c6e538ba57d4958030ea20cee0e94a94c -->
```
        <source>&amp;Network Traffic</source>
        <translation>&amp; நெட்வொர்க் ட்ராஃபிக்</translation>
    
ERR
There is an extra space between the ampersand (&) and the Tamil text. The source has the ampersand directly before the word; keep the accelerator marker exactly once and avoid the stray space.

Correct translation:
&amp;நெட்வொர்க் ட்ராஃபிக்
```

<!-- cache_translation_check_ta_c82d5e9a501f90ad6dc06194ab462dd8e462b00ab66e9422fba9a416e15ee84a -->
```
        <source>&amp;Disconnect</source>
        <translation>&amp; துண்டி</translation>
    
ERR
Problems:
- The translation uses a space after the ampersand ("& துண்டி"). The ampersand should appear exactly once and normally directly precede the shortcut character without an extra space (e.g. "&த...").
- The Tamil word "துண்டி" is not an appropriate UI label for "Disconnect" by itself; it reads like "fragment/cut" and is not a natural command. A clearer UI wording is "தொடர்பை துண்டிக்க" (disconnect the connection) or "இணைப்பை துண்டிக்க".

Corrected suggestions (place ampersand before the desired shortcut key character; no extra space):
- &தொடர்பை துண்டிக்க
or shorter:
- &இணைப்பை துண்டிக்க
```

<!-- cache_translation_check_ta_4a8789f9e4cec6b41be4d375a69ddba5121fffdf1a57e9efe83b85d26d1ace30 -->
```
        <source>&amp;Unban</source>
        <translation>&amp; நீக்கு</translation>
    
ERR
Problems:
- The Tamil word "நீக்கு" alone is ambiguous; a clearer translation for "Unban" is "தடை நீக்கு" or "தடை அகற்று" (meaning "remove ban").
- The ampersand is separated from the text by a space ("& நீக்கு"); the ampersand should be adjacent to the label character (no stray space).

Correct translation suggestion (ampersand placed before first letter, no extra space):
<translation>&தடை நீக்கு</translation>
```

<!-- cache_translation_check_ta_bcbe1595fe717493d923d117bfd5f7d6ccb84b54f4bbc853c56afbfbb173ee84 -->
```
        <source>None</source>
        <translation>யாரும்</translation>
    
ERR
The translation "யாரும்" means "no one" (as in "no person") in Tamil, but the context is "None" (probably as a selectable option meaning "nothing" or "no selection"). The correct term should be "எதுவும் இல்லை" or simply "இல்லை".

Correct translation:
எதுவும் இல்லை
or
இல்லை
```

<!-- cache_translation_check_ta_66b9929856711c44f6e860bdb202b1a83c53dd37181a1fe06cbb3817bfa25067 -->
```
        <source>Executing command using "%1" wallet</source>
        <translation>கட்டளையை "%1" பணியகத்தை பயன்படுத்துகிறது</translation>
    
ERR
The Tamil translation is inaccurate. The source sentence is "Executing command using "%1" wallet", which means an action is being performed now. The provided translation translates to "Using the \"%1\" wallet", missing the action of executing a command and is in the present continuous instead of present participle or passive.

Correct translation:
"%1" பணியகத்தை பயன்படுத்தி கட்டளை இயங்குகிறது

Or a more accurate passive construction:
"%1" பணியகத்தை பயன்படுத்தி கட்டளை இயக்கப்படுகிறது
```

<!-- cache_translation_check_ta_a1b800e11f9d4d0c7a6d587d6ff2b63543d9d64ea2d155a2c8f2f65599530405 -->
```
        <source>Never</source>
        <translation>ஒருகாலம் இல்லை</translation>
    
ERR
The Tamil translation "ஒருகாலம் இல்லை" is unnatural/incorrect for the single-word English "Never". No format specifiers are involved and spacing is fine, but the phrasing should be changed.

Correct translation:
ஒருபோதும்
```

<!-- cache_translation_check_ta_bece5d5a1233db5b5b21c3a426955b13cfe65e250577fd14a5b8d100b4e7e822 -->
```
        <source>&amp;Label:</source>
        <translation>&amp;சிட்டை:</translation>
    
ERR
The Tamil word "சிட்டை" is not a correct or natural rendering of "Label" in this UI context. The ampersand is fine, but the label text should be a commonly used term such as "லேபல்" or "குறிச்சொல்".

Suggested correction:
&லேபல்:
```

<!-- cache_translation_check_ta_61c4fd9e3b81d5a7ee0e8e6b760b9149058814500630f104d0ad2fd8ef71f837 -->
```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>கோரிக்கைக்கு விருப்பமான தொகை. ஒரு குறிப்பிட்ட தொகையை கோர வேண்டாம் இந்த வெற்று அல்லது பூஜ்ஜியத்தை விடு.</translation>
    
ERR
The translation is awkward and not entirely accurate. The second sentence lacks clarity and proper structure in Tamil. Specifically, "இந்த வெற்று அல்லது பூஜ்ஜியத்தை விடு" is not colloquial Tamil, and it doesn't clearly convey "Leave this empty or zero".

Correct translation:
கோரிக்கைக்கான விருப்பத்தேர்ந்த தொகை. ஒரு குறிப்பிட்ட தொகையை கோர விரும்பாவிட்டால், இதை வெறும்/பூஜ்ஜியமாக வையுங்கள்.
```

<!-- cache_translation_check_ta_41729afb2a7c580625c44690425230f3b73188fd53086b5aeb710c95d12a51cc -->
```
        <source>Show the selected request (does the same as double clicking an entry)</source>
        <translation>தேர்ந்தெடுக்கப்பட்ட கோரிக்கையை காட்டு (இரட்டை இடுகையை இரட்டை கிளிக் செய்தால்)</translation>
    
ERR
The translation is problematic. The phrase "இரட்டை இடுகையை இரட்டை கிளிக் செய்தால்" translates to "if you double-click the double entry," which is incorrect and redundant. The correct meaning is "does the same as double clicking an entry."

Correct translation:
தேர்ந்தெடுக்கப்பட்ட கோரிக்கையை காட்டு (ஒரு பதிவை இரட்டை கிளிக் செய்வதற்கு சமமானது)
```

<!-- cache_translation_check_ta_bf186af7ac52bf35b335a4cf40f00cd9e22f1ae6037765b2c53a083116ba503d -->
```
        <source>Copy &amp;URI</source>
        <translation>நகலை &amp;URI</translation>
    
ERR
The Tamil wording "நகலை &amp;URI" is awkward/unnatural: word order and form are not idiomatic Tamil for the UI action "Copy URI". Also the ampersand is present once (good) but should be placed in a more natural location.

Suggested correction (keep a single & as XML entity &amp;):
URI ஐ &amp;நகல்

This reads as "Copy URI" in Tamil (more natural word order and verb form) while preserving a single shortcut marker.
```

<!-- cache_translation_check_ta_cb63f4c90b06299f488814207058923706ec530d59b190c7693d059c4b956b5b -->
```
        <source>Amount:</source>
        <translation>விலை</translation>
    
ERR
The translation "விலை" means "price" in Tamil, which is not the same as "amount". In the context of Bitcoin and finance, "Amount" should be translated as "தொகை".

Correct translation:
தொகை
```

<!-- cache_translation_check_ta_bf186af7ac52bf35b335a4cf40f00cd9e22f1ae6037765b2c53a083116ba503d -->
```
        <source>Copy &amp;URI</source>
        <translation>நகலை &amp;URI</translation>
    
ERR
The Tamil wording "நகலை &amp;URI" is awkward/unnatural: word order and form are not idiomatic Tamil for the UI action "Copy URI". Also the ampersand is present once (good) but should be placed in a more natural location.

Suggested correction (keep a single & as XML entity &amp;):
URI ஐ &amp;நகல்

This reads as "Copy URI" in Tamil (more natural word order and verb form) while preserving a single shortcut marker.
```

<!-- cache_translation_check_ta_76cbd363bd494fbc0289179aa789f0bd3c49764490048652be30a1a8aa25cba9 -->
```
        <source>Copy &amp;Address</source>
        <translation>நகலை விலாசம்</translation>
    
ERR
The Tamil translation is missing the shortcut ampersand (&) and the wording is unnatural. "நகலை விலாசம்" is awkward (literal word order reversed) and does not include the required single &.

Suggested correct translation (with one & for the shortcut):
விலாசத்தை &நகலெடு
```

<!-- cache_translation_check_ta_cb63f4c90b06299f488814207058923706ec530d59b190c7693d059c4b956b5b -->
```
        <source>Amount:</source>
        <translation>விலை</translation>
    
ERR
The translation "விலை" means "price" in Tamil, which is not the same as "amount". In the context of Bitcoin and finance, "Amount" should be translated as "தொகை".

Correct translation:
தொகை
```

<!-- cache_translation_check_ta_7a711487341a6bdeb663a43e34e40d5e7841303bb8c0008b9c30dd77713b72bb -->
```
        <source>Add &amp;Recipient</source>
        <translation>சேர் &amp; பெறுக</translation>
    
ERR
The Tamil translation is awkward/incorrect. "சேர் &amp; பெறுக" mixes words and uses the verb "பெறுக" (receive) incorrectly; word order and wording don't convey "Add Recipient". Also the accelerator (&) is placed between words with a space, which is unusual (it should be adjacent to the character it marks).

Correct translations (with a single &):
- &amp;பெறுநர் சேர்க்க
or
- பெறுநரை &amp;சேர்க்க

Either is acceptable; both mean "Add recipient" in Tamil and include exactly one &.
```

<!-- cache_translation_check_ta_34e19dc6a24ef9dedd22aadff005cc21e48813c2916d077f37113abf9612fc39 -->
```
        <source>A too low fee might result in a never confirming transaction (read the tooltip)</source>
        <translation>ஒரு மிக குறைந்த கட்டணம் ஒரு உறுதி பரிவர்த்தனை விளைவாக (உதவிக்குறிப்பு வாசிக்க)</translation>
    
ERR
The translation has grammar and meaning issues. The Tamil text doesn't accurately convey "might result in a never confirming transaction", and the phrase order is off. A more accurate translation is:

மிக குறைந்த கட்டணம் செலுத்துவது, பரிவர்த்தனை உறுதிப்படுத்தப்படாமல் இருக்க வழிவகுப்பதாக இருக்கலாம் (உதவிக்குறிப்பைப் படிக்கவும்)
```

<!-- cache_translation_check_ta_1e4c4a7b6dfdc2ce9f26b0bcfcfc1d5bc609cff50bfe48fc4de233d7aa857399 -->
```
        <source>Clear &amp;All</source>
        <translation>அழி &amp;அனைத்து</translation>
    
ERR
The Tamil is awkward and misses the object marker. Natural imperative order is "அனைத்தையும் அழி" (erase/clear all). Also ensure the & shortcut appears exactly once.

Suggested correction:
&அனைத்தையும் அழி
```

<!-- cache_translation_check_ta_1eee82f8173c320b9db4aac507fc402844d73172ca0485797f2b57f5b2b41ac9 -->
```
        <source>Copy quantity</source>
        <translation>அளவு அளவு</translation>
    
ERR
The translation duplicates the word "அளவு" (quantity), resulting in "அளவு அளவு", which means "quantity quantity." This is incorrect.

Correct translation:
அளவை நகலெடு
```

<!-- cache_translation_check_ta_fa5d21eb0a181783483ba8267d976efa1a7755faa332ba3b087b9eb2cc0936be -->
```
        <source>Copy amount</source>
        <translation>நகல் நகல்</translation>
    
ERR
The translation "நகல் நகல்" is incorrect. It literally means "copy copy" and does not convey the intended meaning of "Copy amount". The correct translation should be:

மொத்தத்தை நகலெடுக்கவும்

Correct translation:
மொத்தத்தை நகலெடுக்கவும்
```

<!-- cache_translation_check_ta_016509eb0f2108b1b3008b97d72a188c250073acfca68fce51e558d081c94137 -->
```
        <source>Copy after fee</source>
        <translation>நகல் கட்டணம்</translation>
    
ERR
The translation "நகல் கட்டணம்" means "copy fee" which inaccurately translates "Copy after fee". The correct meaning is to copy the amount remaining after the fee has been deducted. The translation does not reflect the "after fee" concept.

Correct translation:
கட்டணத்தைக் கழித்த பிறகு நகலெடு
```

<!-- cache_translation_check_ta_2fb0328a88792e7f1a7c655b0e9843036f2ce04de99419a9567fa9a1fb7753a8 -->
```
        <source>Copy bytes</source>
        <translation>நகல் கட்டணம்</translation>
    
ERR
The translation is incorrect. "நகல் கட்டணம்" means "copy fee," not "Copy bytes." The correct translation for "Copy bytes" in Tamil should be "பைட்டுகளை நகலெடு".

Correct translation:
பைட்டுகளை நகலெடு
```

<!-- cache_translation_check_ta_49345c9ecf2a20af2f8a1da45b93b3beadbef44f9d21c29cdf50a2088d6dd52e -->
```
        <source>You can increase the fee later (signals Replace-By-Fee, BIP-125).</source>
        <translation>நீங்கள் கட்டணத்தை பின்னர் அதிகரிக்கலாம் (என்கிறது மாற்று கட்டணம், பிப்-125).</translation>
    
ERR
The translation "என்கிறது மாற்று கட்டணம், பிப்-125" is an inaccurate rendering of "signals Replace-By-Fee, BIP-125." The phrase "என்கிறது" ("it says") is unnecessary, and "மாற்று கட்டணம்" is not a standard translation for "Replace-By-Fee." "BIP-125" should remain as-is, but "Replace-By-Fee" should be transliterated or explained as a concept relevant to Bitcoin.

Correct translation:
நீங்கள் கட்டணத்தை பின்னர் உயர்த்த முடியும் (Replace-By-Fee, BIP-125-ஐச் சுட்டுகிறது).
```

<!-- cache_translation_check_ta_f6e2615620b55bfdb84a666ea92cd6755abbf515acb310ca8f22649288aa28e0 -->
```
        <source>Pay &amp;To:</source>
        <translation>செலுத்து &amp;கொடு:</translation>
    
ERR
Problems:
- The phrase "செலுத்து கொடு:" is awkward/unidiomatic Tamil for the UI label "Pay To:"; it reads like two verbs.
- The ampersand is encoded as "&amp;" in the translation; the UI expects a single '&' used once to mark the shortcut key.

Suggested correct translation (with a single & for the shortcut):
&பெறுநர்:
```

<!-- cache_translation_check_ta_bece5d5a1233db5b5b21c3a426955b13cfe65e250577fd14a5b8d100b4e7e822 -->
```
        <source>&amp;Label:</source>
        <translation>&amp;சிட்டை:</translation>
    
ERR
The Tamil word "சிட்டை" is not a correct or natural rendering of "Label" in this UI context. The ampersand is fine, but the label text should be a commonly used term such as "லேபல்" or "குறிச்சொல்".

Suggested correction:
&லேபல்:
```

<!-- cache_translation_check_ta_7794d893072ee0f677a39c39690abb7ef1c6f344378c28fc437157b183ded2da -->
```
        <source>S&amp;ubtract fee from amount</source>
        <translation>கட்டணத்தை தொகையிலிருந்து வி&amp;லக்கு</translation>
    
ERR
The Tamil wording uses "விலக்கு" (exemption), which doesn't mean "subtract" here. Also word order is awkward. The & shortcut exists exactly once (good), but it should be placed in a natural position.

Correct translation (with single & for a shortcut):
தொகையிலிருந்து கட்டணத்தை &கழி
```

<!-- cache_translation_check_ta_60de70954063bcef36a0fb40735691d44e523957db66a2e93dc9458a0161d024 -->
```
        <source>Send</source>
        <translation>அனுப்புவும்</translation>
    
ERR
The translation "அனுப்புவும்" is incorrect for the English word "Send". The correct translation should be "அனுப்பு".

Explanation:
- "அனுப்புவும்" is a verb form indicating "will send" or is close to "and send", which is inappropriate in this menu/button context. 
- The menu action "Send" should be translated as the imperative "அனுப்பு" (meaning "Send" as a command).

Correct translation:
அனுப்பு
```

<!-- cache_translation_check_ta_4d8db992019d8bd2c9211181a730ee2d550937c626fbd315d2a790fc2d86f6f7 -->
```
        <source>Sign &amp;Message</source>
        <translation>கையொப்பம் &amp;செய்தி</translation>
    
ERR
Word order is awkward in Tamil. "கையொப்பம் &செய்தி" reads as "signature message" rather than the action "Sign Message". Also ensure the ampersand appears once (it does), but it's better placed before the noun that corresponds to "Message".

Suggested correction:
செய்தி &கையொப்பம்
```

<!-- cache_translation_check_ta_1e4c4a7b6dfdc2ce9f26b0bcfcfc1d5bc609cff50bfe48fc4de233d7aa857399 -->
```
        <source>Clear &amp;All</source>
        <translation>அழி &amp;அனைத்து</translation>
    
ERR
The Tamil is awkward and misses the object marker. Natural imperative order is "அனைத்தையும் அழி" (erase/clear all). Also ensure the & shortcut appears exactly once.

Suggested correction:
&அனைத்தையும் அழி
```

<!-- cache_translation_check_ta_af31f86d0f81f11c529fe89203ad8e0de4dc7658f92d43f0da21ec0833ac7a2a -->
```
        <source>Verify &amp;Message</source>
        <translation>சரிபார்க்கவும் &amp;செய்தி</translation>
    
ERR
The Tamil word order is unnatural (verb before noun) and the ampersand is HTML-escaped as "&amp;" instead of a single '&'. Also the mnemonic ampersand should appear exactly once. A better translation:

Correct translation:
&செய்தியை சரிபார்க்கவும்
```

<!-- cache_translation_check_ta_ef95ad511dc5bd38bc0110191de6d9a263cfa1c797f98464f6c00e3ccd52ccc2 -->
```
        <source>Amount</source>
        <translation>விலை</translation>
    
ERR
The translation "விலை" means "price" in Tamil, which is not the correct term for "amount" in the context of Bitcoin transactions. The term "தொகை" is more appropriate for "amount".

Correct translation:
தொகை
```

<!-- cache_translation_check_ta_21c4bce2442c4b9cae4758747663c2d5efca156ba62d82d977ff46f5411a969e -->
```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>உறுதிப்படுத்துகிறது (%1 ன் %2 பரிந்துரைக்கப்பட்ட உறுதிப்படுத்தல்கல்)</translation>
    
ERR
There is a spelling error and misuse of pluralization in the Tamil translation. The word "உறுதிப்படுத்தல்கல்" is incorrect; the correct plural form is "உறுதிப்படுத்தல்கள்". Also, it is better to use "உறுதிப்படுத்தல்கள்" to match the English "confirmations", and the phrase should indicate that %1 out of %2 recommended confirmations are happening.

Correct translation:
உறுதிப்படுத்துகிறது (%2 பரிந்துரைக்கப்பட்ட உறுதிப்படுத்தல்கள் இல் %1)
Alternatively, to keep closer to the English sentence order:
உறுதிப்படுத்துகிறது (%2 பரிந்துரைக்கப்பட்ட உறுதிப்படுத்தல்களில் %1)
```

<!-- cache_translation_check_ta_2c4d19e79b72b49fe15387027e961530a7fffede60472f759762ff35d261086b -->
```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>இது பரிவர்த்தனைக் கட்டணம் ஆகும் அதன் வேறுபாடு தூசியை விட சிறியதாக இருந்தால் நீங்கள் அதை நிராகரிக்கலாம்.</translation>
    
ERR
The translation is not accurate. The original sentence means "This is the transaction fee you may discard if change is smaller than dust at this level", specifically mentioning "change" in the Bitcoin transaction context—not "its difference" as the Tamil translation says. The structure is a bit off and introduces confusion.

Correct translation:
இது, இந்த நிலையில் மாறுதல் (change) தூசியை விடக் குறைவாக இருந்தால் நீங்கள் நிராகரிக்கக்கூடிய பரிவர்த்தனை கட்டணமாகும்.
```

<!-- cache_translation_check_ta_fd593a1a1553b470c5f12c5916c6138d555195737b1b3a5a3cbb833777f1b1bf -->
```
        <source>Cannot set -peerblockfilters without -blockfilterindex.</source>
        <translation>-blockfiltersindex இல்லாத -peerblockfilters அமைப்பு முடியாது </translation>
    
ERR
There is an error in the Tamil translation: "-blockfiltersindex" is a typographical mistake; the correct option is "-blockfilterindex". The Tamil sentence omits the definite nature ("இல்லாமல்" or "இல்லாத நிலையில்") of the prerequisite, and the pause at the end is missing. There is also a missing period at the end of the Tamil sentence, and there is an extra space at the end.

Correct translation:
-blockfilterindex இல்லாமல் -peerblockfilters ஐ அமைக்க முடியாது.
```
</details>

Number of issues: 105.
