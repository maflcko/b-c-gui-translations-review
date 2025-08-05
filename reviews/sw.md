# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sw</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsw%5D%20low%20quality)


```
        <source>Copy Label</source>
        <translation>Nakili  Chapa</translation>
    
YES  
The translation has an extra space between the two words "Nakili  Chapa". Also, "Nakili Chapa" literally translates to "copy label," but "chapa" is more commonly used for "stamp" rather than "label" in the Bitcoin/wallet context. A better term for "label" in Swahili is "alama". The correct phrase should be:  

Nakili Alama
```

```
        <source>Edit</source>
        <translation> hariri</translation>
    
YES  
The translation contains a leading whitespace before "hariri" which is a formatting issue. The correct translation should not have any leading or trailing spaces.

Correct translation:  
hariri
```

```
        <source>Encrypt wallet</source>
        <translation>Simba mkoba</translation>
    
YES  
The Swahili word "Simba" means "lion" and is incorrect in this context. The verb "Encrypt" should be translated as "Fichua" or "Simbua" (better approximations depend on usage), but the most commonly used term for "Encrypt" in Swahili tech contexts is "Fichua" meaning "to encrypt/protect with a cipher". "Mkoba" correctly translates to "wallet".  

Correct translation:  
Fichua mkoba
```

```
        <source>Change passphrase</source>
        <translation>Badilisha nenosiri </translation>
    
YES
The translation "Badilisha nenosiri " correctly conveys "Change passphrase" in Swahili, but there is an unnecessary trailing space after "nenosiri". 

Correct translation:
Badilisha nenosiri
```

```
        <source>Wallet to be encrypted</source>
        <translation>Wallet itasimbwa kwa njia fiche</translation>
    
YES  
The word "Wallet" should be translated or at least adapted into Swahili to maintain naturalness, such as using "Mfewuko" (wallet) or "Mkoba". The phrase "itasimbwa kwa njia fiche" is inaccurate; the verb should relate to encryption, which in Swahili is commonly "kusimbwa" (to be encrypted), not "itasimbwa" which is more of a future tense and less idiomatic here. Also, "kwa njia fiche" is awkward; "kwa siri" or simply "kusimbwa" is better.

Correct translation:  
"Mkoba kusimbwa"  
or  
"Mkoba utasimbwa" (wallet to be encrypted, future tense)  
or more natural:  
"Mkoba utakaosimbwa" (wallet to be encrypted)
```

```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>MUHIMU: Chelezo zozote ulizofanya hapo awali za faili lako la pochi zinapaswa kubadilishwa na faili mpya ya pochi iliyosimbwa. Kwa sababu za usalama, chelezo za awali za faili la pochi lisilosimbwa zitakuwa hazifai mara tu utakapoanza kutumia pochi mpya iliyosimbwa.
 </translation>
    
YES
There is an unnecessary trailing whitespace character (a non-breaking space or similar) at the end of the translation, which should be removed for formatting consistency.

Also, the source mentions "Any previous backups you have made", which is translated as "Chelezo zozote ulizofanya hapo awali" (backups you have made before) – this is correct. The rest is accurate and conveys the meaning well.

Corrected translation without trailing space:

MUHIMU: Chelezo zozote ulizofanya hapo awali za faili lako la pochi zinapaswa kubadilishwa na faili mpya ya pochi iliyosimbwa. Kwa sababu za usalama, chelezo za awali za faili la pochi lisilosimbwa zitakuwa hazifai mara tu utakapoanza kutumia pochi mpya iliyosimbwa.
```

```
        <source>The supplied passphrases do not match.</source>
        <translation>Nenosiri liliyotolewa haifanani.</translation>
    
YES
The translation is not in Swahili (language code 'sw') but rather appears to be in Swahili's neighboring languages like Kikuyu or a miswritten form. The correct Swahili translation for "The supplied passphrases do not match." is:

"Maneno ya siri yaliyotolewa hayalingani."
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Nenosiri liliyoingizwa kwa ajili ya kufungua pochi sio sahihi.</translation>
    
YES  
The translation contains a miswritten word "liliyoingizwa" which should be "liliyoingizwa." Additionally, "pochi" (wallet) can be better specified as "pochi la Bitcoin" if context clarity is desired, but it is not mandatory. The rest of the sentence is understandable and accurate.  

Correct translation:  
Nenosiri liliyoingizwa kwa ajili ya kufungua pochi sio sahihi.
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Faili ya mipangilio ya asilimia %1 inaweza kuwa mbovu au batili.</translation>
    
YES  
The translation incorrectly translates "%1" as "asilimia %1" (which means "percentage %1" or "percent %1") instead of keeping it as a placeholder for a filename. Also, "Faili" is a direct loanword for "file," which is acceptable in Swahili, and "faili ya mipangilio" appropriately refers to "settings file."

Correct translation:  
Faili ya mipangilio %1 inaweza kuwa mbovu au batili.
```

```
        <source>Runaway exception</source>
        <translation>Ubaguzi wa kukimbia</translation>
    
YES
The translation "Ubaguzi wa kukimbia" is incorrect and misleading. It translates to "Discrimination of running" or "Running discrimination," which does not convey the meaning of "Runaway exception." The phrase "Runaway exception" in a programming or Bitcoin context refers to an exception/error that is not properly handled and causes the program to crash or behave unexpectedly.

A more accurate Swahili translation would be:  
"Hitilafu isiyozuilika"  
or  
"Kosa lisilozuilika"  
which means "Uncontrolled exception" or "Exception that is not stopped."
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Proxy &lt;b&gt;imeamilishwa&lt;/b&gt;: %1</translation>
    
YES
The Swahili translation uses "imeamilishwa" which is incorrect for "enabled." The correct word should be "imewezeshwa," which means "enabled."

Correct translation:
Proxy &lt;b&gt;imewezeshwa&lt;/b&gt;: %1
```

```
        <source>Encrypt Wallet…</source>
        <translation>Simba Mkoba...</translation>
    
YES
The Swahili verb "Simba" means "lion," which is incorrect in this context. The correct verb for "encrypt" is "Fichua" or "Simbua" (derived from "ku-simba," meaning to encrypt or encode). Also, ensure the ellipsis uses the proper Unicode character (…), not three periods.

Correct translation:  
Fichua Mkoba…
```

```
        <source>Command-line options</source>
        <translation>Chaguo za amri ya amri</translation>
    
YES  
The translation "Chaguo za amri ya amri" contains a redundancy by repeating "amri" (command) twice, which makes it unnatural and incorrect. The correct translation should be concise and avoid repeating the word "amri."

Correct translation:  
Chaguo za amri
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Pakia Muamala wa Bitcoin Uliosainiwa Kiasi</translation>
    
YES  
The translation has word order issues and incorrect vocabulary that make it unclear and unnatural. The English phrase "Load Partially Signed Bitcoin Transaction" translates more accurately to Swahili as:  
"Pakia Muamala wa Bitcoin Uliosainiwa Sehemu"  
Explanation:  
- "Pakia" is correct for "Load".  
- "Muamala" means "transaction".  
- "wa Bitcoin" correctly indicates "of Bitcoin".  
- "Uliosainiwa" means "signed".  
- "Sehemu" means "partially", which is more appropriate than "Kiasi" (which means "amount" or "quantity").  
- The original translation uses "Muamala wa Bitcoin Uliosainiwa Kiasi", which is awkward and incorrect.
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Pakia Muamala wa Bitcoin Uliosainiwa Kiasi kutoka kwenye ubao wa kunakili</translation>
    
YES  
The translation contains errors in word choice and phrasing. "Muamala" should be "Muamala" → "Muamala" is not correct here; the correct term is "Muamala" or "Muamala" is wrong; the correct term for "Transaction" in Swahili is "Muamala." Also, "Uliosainiwa Kiasi" incorrectly translates "Partially Signed" as "Signed Amount." Instead, "Partially Signed" is "Iliyosainiwa Sehemu" or "Iliyosainiwa kwa sehemu." Additionally, "from clipboard" is properly translated as "kutoka kwa ubao wa kunakili" (including "kwa"). The phrase "Pakia Muamala..." is unnatural; better to say "Pakia Muamala wa Bitcoin Iliyosainiwa Sehemu kutoka kwenye ubao wa kunakili."

Correct translation:  
Pakia Muamala wa Bitcoin Iliyosainiwa Sehemu kutoka kwenye ubao wa kunakili
```

```
        <source>Load Wallet Backup</source>
        <extracomment>The title for Restore Wallet File Windows</extracomment>
        <translation>Pakia Hifadhi Nakala ya Wallet</translation>
    
YES  
The translation "Pakia Hifadhi Nakala ya Wallet" is a bit awkward and not fully accurate in Swahili. "Pakia" means "load" or "install," which is acceptable, but "Hifadhi Nakala ya Wallet" is a literal translation of "Wallet Backup" that feels unnatural. The word "Wallet" is better translated or transliterated consistently. The phrase should better reflect the functionality, such as loading or restoring a backup of the wallet.

Correct translation:  
"Pakia Nakala Hifadhi ya Mkoba"

Explanation:  
- "Nakala Hifadhi" means "backup copy"  
- "Mkoba" is the Swahili term for "wallet"  
- The order is adjusted to sound natural in Swahili: "Nakala Hifadhi ya Mkoba" = "Backup copy of wallet"  
- The verb "Pakia" correctly means "Load" or "Import"  

Alternatively, if "Restore" is meant, "Rejesha Nakala Hifadhi ya Mkoba" could be used, but since the source is "Load Wallet Backup," "Pakia" is appropriate.
```

```
        <source>Hide</source>
        <translation>Ficha</translation>
    
YES  
The translation "Ficha" is incorrect for the Swahili language. The correct translation for "Hide" in Swahili is "Ficha" (but with a capital F is acceptable as a single word). However, "Ficha" is a correct Swahili verb meaning "to hide". Since the capitalization alone is not problematic and spelling is correct, this translation is actually accurate. There is no erroneous or unwanted content, no format specifiers involved, and no whitespace issues.

Therefore, the initial assessment is that the translation is correct.

Correction: NO
```

```
        <source>Show</source>
        <translation>Jinsi  jinsi</translation>
    
YES  
The translation "Jinsi jinsi" means "gender gender" or can mean "kind, kind" in Swahili, which does not correspond to the source English word "Show." The correct translation for "Show" in Swahili should be "Onyesha."

Correct translation:  
Onyesha
```

```
        <source>HD key generation is &lt;b&gt;enabled&lt;/b&gt;</source>
        <translation>Uzalishaji wa ufunguo wa HD ni &lt;b&gt;kuwezeshwa &lt;/b&gt;</translation>
    
YES  
There is an extra space before the closing &lt;/b&gt; tag in the translation ("kuwezeshwa &lt;/b&gt;"). In addition, the translation "Uzalishaji wa ufunguo wa HD ni kuwezeshwa" is somewhat awkward. A more natural translation would be "Uzalishaji wa ufunguo wa HD umewezeshwa" ("has been enabled") to better reflect the English present perfect tense and the meaning of "is enabled".

Correct translation:  
Uzalishaji wa ufunguo wa HD ni &lt;b&gt;umewezeshwa&lt;/b&gt;
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>Uzalishaji wa ufunguo wa HD ni &lt;b&gt;kutowezeshwa&lt;/b&gt;</translation>
    
YES
The translation is somewhat unnatural and inaccurate. "Kutowezeshwa" is not common in Swahili and sounds awkward here. A more appropriate verb for "disabled" in this technical context would be "zimwa" or "imezimwa," conveying the meaning "turned off" or "disabled."

Correct translation:
Uzalishaji wa ufunguo wa HD ume&lt;b&gt;zimwa&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Wallet &lt;b&gt;imesimbwa kwa njia fiche&lt;/b&gt; na &lt;b&gt;imefunguliwa&lt;/b&gt; kwa sasa</translation>
    
YES
The translation is generally understandable but uses "imesimbwa kwa njia fiche" for "encrypted," which is an uncommon and slightly unclear phrase in Swahili. A more accurate and commonly understood translation for "encrypted" is "imefichwa kwa siri" or "imehifadhiwa kwa siri." Also, the term "Wallet" should ideally be translated as "mkoba" to suit the context. The phrase "imefunguliwa kwa sasa" for "currently unlocked" is acceptable but can be more naturally phrased as "imefunguliwa sasa."

Correct translation:
<Mkoba> ni &lt;b&gt;imehifadhiwa kwa siri&lt;/b&gt; na kwa sasa &lt;b&gt;imefunguliwa&lt;/b&gt;</translation>
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Pochi &lt;b&gt;imesimbwa kwa njia fiche&lt;/b&gt; na &lt;b&gt;imefungwa&lt;/b&gt;kwa sasa</translation>
    
YES
There is a missing space before "kwa sasa" causing formatting issues. Also, "Pochi" is a less common term for wallet; the more standard term is "Msanidi" or "Mfuko" but "pochi" is acceptable in an informal context. The phrase "imesimbwa kwa njia fiche" is a literal translation of "encrypted" but could be better phrased as "imesimbwa" alone or "imesimbwa kwa usimbaji fiche". To improve clarity and spacing:

Correct translation:
Pochi &lt;b&gt;imesimbwa&lt;/b&gt; na &lt;b&gt;imefungwa&lt;/b&gt; kwa sasa
```

```
        <source>Fee:</source>
        <translation>Ada:</translation>
    
YES  
The word "Ada" in Swahili means "custom" or "tradition," which is incorrect in this Bitcoin context. The correct translation for "Fee:" (meaning a charge or cost) in Swahili is "Ada:" with a capital 'A' and colon, but since the translation already is "Ada:" with proper capitalization and punctuation, it is actually correct.  

On closer inspection, the translation is accurate and appropriate, and the formatting is correct. Therefore:  

NO
```

```
        <source>Load Wallets</source>
        <extracomment>Title of progress window which is displayed when wallets are being loaded.</extracomment>
        <translation>Pakia Pochi</translation>
    
YES  
The translation "Pakia Pochi" is incorrect for "Load Wallets." In Swahili, "load" as a verb in this context would be better translated as "Pakia," but "Pochi" means "pocket," which is not appropriate for "wallets" in the Bitcoin context (wallets referring to digital wallets). The correct term for "wallets" in Swahili, especially in a financial or Bitcoin context, is "Mifuko ya akiba" or simply "Mifuko" or "Mifuko ya Bitcoin." A more accurate, natural translation would be:

Pakia Mifuko ya Kidijitali

or more simply:

Pakia Mifuko
```

```
        <source>Encrypt the wallet. The wallet will be encrypted with a passphrase of your choice.</source>
        <translation>Simba pochi. Pochi itasimbwa kwa kutumia nenosiri utakalo chagua.</translation>
    
YES
The translation has some grammatical and word choice issues in Swahili. The phrase "Simba pochi" is incorrect; it should be "Fichua pochi" or "Funga pochi" for "Encrypt the wallet." The second sentence structure is awkward and missing proper linking words.

Correct translation:
Fichua pochi. Pochi itasimizwa kwa nenosiri lako uhlatue.
```

```
        <source>Error</source>
        <translation>Onyo</translation>
    
YES  
The correct Swahili word for "Error" is "Hitilafu" or "Kosa", not "Onyo" which means "Warning".  

Correct translation:  
<translation>Hitilafu</translation>
```

```
        <source>Error</source>
        <translation>Onyo</translation>
    
YES  
The correct Swahili word for "Error" is "Hitilafu" or "Kosa", not "Onyo" which means "Warning".  

Correct translation:  
<translation>Hitilafu</translation>
```

```
        <source>Fee:</source>
        <translation>Ada:</translation>
    
YES  
The word "Ada" in Swahili means "custom" or "tradition," which is incorrect in this Bitcoin context. The correct translation for "Fee:" (meaning a charge or cost) in Swahili is "Ada:" with a capital 'A' and colon, but since the translation already is "Ada:" with proper capitalization and punctuation, it is actually correct.  

On closer inspection, the translation is accurate and appropriate, and the formatting is correct. Therefore:  

NO
```

```
        <source>Error</source>
        <translation>Onyo</translation>
    
YES  
The correct Swahili word for "Error" is "Hitilafu" or "Kosa", not "Onyo" which means "Warning".  

Correct translation:  
<translation>Hitilafu</translation>
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>Zaidi ya anuani moja ya onion bind imetolewa. Inatumia %skwa ajili ya huduma ya Tor onion inayotengeneza kiotomatiki. </translation>
    
YES
There is a missing space between "%s" and "kwa" in the translation, causing formatting issues. Also, the phrase "inatengeneza kiotomatiki" is less natural; "inayotengenezwa kiotomatiki" (passive) better conveys "automatically created." The word "bind" is untranslated and should be adapted or quoted since it is a technical term.

Correct translation:
Zaidi ya anuani moja ya bind ya onion imetolewa. Inatumia %s kwa ajili ya huduma ya Tor onion inayotengenezwa kiotomatiki.
```

```
        <source>Invalid -i2psam address or hostname: '%s'</source>
        <translation>Anuani ya -i2psam au jina la mwenyeji ni batili: '%s'</translation>
    
YES  
The translation contains a few issues:  
- The phrase "Anuani ya -i2psam au jina la mwenyeji ni batili" should use "au" (or) rather than "au" being misspelled as "au". In the translation it's correctly written, but "Anuani ya -i2psam au jina la mwenyeji ni batili" means "Invalid -i2psam address or hostname", which is mostly correct.  
- However, there is a small typo: "Anuani ya -i2psam au jina la mwenyeji ni batili" uses "au" (meaning "or") but in the given translation it is "au" but in the prompt it's "au". This is consistent.  
- The word "Anuani" means "address"; "jina la mwenyeji" means "hostname"; "ni batili" means "is invalid". The format specifier '%s' is correctly placed and intact, with proper quotes.  
- The only issue is a slight awkwardness in the phrasing. A more natural Swahili phrasing might be:  
  "Anuani au jina la mwenyeji la -i2psam si halali: '%s'"  
which literally means "The -i2psam address or hostname is not valid: '%s'".  
- Also, the original uses "Invalid -i2psam address or hostname", so the "-i2psam" should come before "address". Putting "-i2psam" before "anuani" is correct.  

Therefore, the main problem is the awkward phrasing "Anuani ya -i2psam au jina la mwenyeji ni batili" which can be improved for better clarity.  

Correct translation:  
"Anuani au jina la mwenyeji la -i2psam si halali: '%s'"  

This translation is more natural and correctly structured in Swahili.

Hence:  

YES  
The translation is awkward in phrasing and can be improved for clarity. The phrase "Anuani ya -i2psam au jina la mwenyeji ni batili" is literal but not natural. The format specifier '%s' is correctly preserved.  

Correct translation:  
Anuani au jina la mwenyeji la -i2psam si halali: '%s'
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>Anuani ya onion au jina la mwenyeji ni batili: '%s'</translation>
    
YES
The translation uses "Anuani ya onion au jina la mwenyeji ni batili," which is Swahili, not 'sw' (Swahili). However, since 'sw' is the ISO code for Swahili, this matches.

But the phrase "Anuani ya onion au jina la mwenyeji ni batili" is a correct literal translation for "Invalid -onion address or hostname:".

However, "onion" should likely remain as is (since it's a technical term), which it does.

The translation is accurate and format specifiers (%s) are correctly placed without any whitespace issues.

Therefore, NO
```
</details>
