# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>so</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bso%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation>Xaq-click si aad cinwaanka edit ama qoraalka</translation>
    
YES
The translation is understandable but contains several issues:
- "Xaq-click" uses an English/Somali hybrid form; the correct Somali word for "right" is "midig."
- The format "edit address or label" is not properly rendered; "edit" should be translated.
- There is some awkward phrasing, and the format is not natural or standard for Somali.
- It is missing correct translation for "label" ("qoraal" can suffice but "sumad" might be more suitable).
- The word order and spacing are acceptable.

Correct translation:
Midig-guji si aad u tafatirto cinwaanka ama sumadda
```

```
        <source>New</source>
        <translation>Hormarin</translation>
    
YES
The translation "Hormarin" is incorrect for "New." The correct translation for "New" in Somali is "Cusub."

Correct translation:
Cusub
```

```
        <source>Close</source>
        <translation>CLose</translation>
    
YES
The translation is incorrect—the word "CLose" is simply a misspelled/transliterated English word and is not Somali. Also, it uses a capital "L" unnecessarily. The correct Somali translation would be:

Xir
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>Sida loo tababbardhigo qaabka loo takhasusay</translation>
    
YES  
The provided translation is inaccurate and does not convey the meaning of the English source, which is about exporting data from the current tab into a file. The Somali text given roughly translates to "How to specialize the way of training", which is unrelated.  

Correct translation:  
Dhoofinta xogta ku jirta tabka hadda furan ee fayl.
```

```
        <source>Export</source>
        <translation> Dhoofinta</translation>
    
YES
There is an extra leading whitespace in the translation, which is a formatting issue. Also, while "Dhoofinta" means "The export" (noun), in software context "Export" as an action/button is better rendered as "Dhoof", which is the imperative/verb form.

Correct translation:
Dhoof

Or, if noun is intended (less common for UI buttons):
Dhoofin

So the best translation here is:
Dhoof
```

```
        <source>Choose the address to send coins to</source>
        <translation>Dooro cinwaanka u dirto lacagta qadaadiicda ah si ay u</translation>
    
YES
The translation is incomplete and ungrammatical. The Somali translation cuts off at "si ay u", which does not complete the sentence. Additionally, "lacagta qadaadiicda ah" is a literal translation of "the money of coins/coins' money", but "qadaadiic" suffices for "coins" in Somali.

Correct translation:
Dooro cinwaanka aad dooneyso inaad u dirto qadaadiicda
```

```
        <source>Choose</source>
        <translation>CAagga</translation>
    
YES
There is a typographical error in the translation: "CAagga" is not correct in Somali, and the capitalization is inconsistent. The correct Somali translation for "Choose" is "Dooro".

Correct translation:
Dooro
```

```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Kuwani waa cinwaanada Seeraar in aad ku direyso lacagaha. Marwalba waxaa ka mid ah masuuliyiinta kubadda cagta ah ee hubinaya in ay ka soo horjeedaan tacaddiyadeeda, taas oo ay ku tallaabsato in ay ka qayb qaataan isbedelka taleemooyinka.</translation>
    
YES
The translation is problematic. The Somali ('so') translation provided is incorrect, off-topic, and appears to contain unrelated content about football authorities and reforms rather than the meaning of the original Bitcoin-related source. There is also no mention of "legacy" addresses, "receive tab", or correct terminology for Bitcoin addresses.

Correct translation:
Kuwani waa cinwaannadaaga Bitcoin ee lagu helo lacagaha. Isticmaal badhanka 'Abuur cinwaan cusub oo la helo' ee tabta la helayo si aad u abuurto cinwaan cusub.
Saxeexidda waxay suurtagal u tahay keliya cinwaanada nooca 'legacy'.
```

```
        <source>Copy Address</source>
        <translation> Nuqul Kabaha Cinwaanka</translation>
    
YES
There is an erroneous word in the translation. "Kabaha" means "shoes" in Somali, which is not correct here. Also, there is an extra space at the beginning of the translation.

Correct translation:
Nuqul cinwaanka

Explanation:
- "Nuqul" = "Copy"
- "cinwaanka" = "the address"
- Removed erroneous "Kabaha" and the stray leading space.
```

```
        <source>Copy Label</source>
        <translation>Nuqul  Label</translation>
    
YES
There is an unnecessary space between "Nuqul" and "Label". Somali ("so") language does not require this spacing, and keeping it introduces a formatting error. Furthermore, "Nuqul" is the correct term for "Copy", and "Label" can be left as is if there is no established Somali term; however, to avoid code mixing, "Label" could optionally be translated as "Sumad" (meaning "label" or "mark").

Correct translation:
Nuqul Label
or, for a more Somali wording:
Nuqul Sumad
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comma kala file</translation>
    
YES
The translation "Comma kala file" is incorrect in Somali, and does not accurately translate "Comma separated file". "Kala" by itself means "separate" but the phrase does not make sense as written. Also, terms like "comma" and "file" may be localized or more appropriately explained to Somali speakers.

Correct translation:
Faylka kooxo lagu kala saaray faasiil (,)
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Waxaa jiray qalad isku dayaya in uu badbaadiyo liiska cinwaanka si. %1Iskuday mar kale.</translation>
    
YES
The translation has issues:
- The format specifier %1 is incorrectly separated from the rest of the sentence, causing readability problems.
- The sentence structure is awkward and does not flow well in Somali.
- Missing appropriate punctuation and proper flow in Somali.

Correct translation:
Waxaa jiray qalad markii la isku dayay in liiska cinwaannada lagu kaydiyo %1. Fadlan isku day mar kale.
```

```
        <source>Sending addresses - %1</source>
        <translation>Cinwaanada diraya%1</translation>
    
YES
There is a missing space between "diraya" and "%1", causing a whitespace format issue. Also, the translation would be clearer as "Cinwaanada diraya - %1" to mirror the source formatting.

Correct translation:
Cinwaanada diraya - %1
```

```
        <source>Repeat new passphrase</source>
        <translation>Ku celi passphrase cusub</translation>
    
YES
The translation "Ku celi passphrase cusub" literally means "Repeat new passphrase," but the construction is awkward in Somali. "Ku celi" means "repeat," but contextually for "Repeat new passphrase" (as in prompting the user to re-enter their new passphrase), a clearer Somali translation would be:

Soo celi ereyga sirta cusub

Correct translation:
Soo celi ereyga sirta cusub
```

```
        <source>Encrypt wallet</source>
        <translation>jeebka Encrypt</translation>
    
YES
The translation is problematic. "jeebka Encrypt" mixes Somali and English, and the word order is incorrect. The correct Somali translation should be fully in Somali.

Correct translation:
Qarso jeebka
```

```
        <source>Unlock wallet</source>
        <translation>jeebka Unlock</translation>
    
YES
The translation simply mixes Somali ("jeebka" which means "pocket" and is sometimes colloquially used for "wallet") with the English word "Unlock". It is neither fully translated nor correct.

Correct translation:
Fur jeebka
or
Fur boorsada
(Depending on preferred terminology for "wallet" in the Bitcoin context. "Boorsada" is also commonly used for wallet/purse in Somali. "Fur" means "unlock/open".)
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Digniin: Haddii aad jeebka jeebkaaga qarisid, Oo aad lumiso ereygii,Adigaa sameyn doontaa&lt;b&gt;Lumin oo dhan BITCOINS AAD&lt;/b&gt;!</translation>
    
YES
There are issues with repetition ("jeebka jeebkaaga" meaning "your wallet your wallet"), awkward phrasing, and the translation does not fully preserve the original meaning and emphasis. The translation also lacks proper spacing and natural word order in Somali, particularly around the bold warning. Format specifiers are not an issue here, but the syntax and capitalisation do not follow the source's intention.

Correct translation:
Digniin: Haddii aad qarisid jeebkaaga oo aad lumiso erayga sirta ah, &lt;b&gt;WAXAAD WAAYI DOONTAA DHAMMAAN BITCOIN-KAAGA&lt;/b&gt;!
```

```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>Ma hubtaa in aad jeceshahay in aad jeebka sirta?</translation>
    
YES
The translation is inaccurate and ungrammatical. The Somali translation provided does not clearly convey the intended meaning of "encrypting the wallet"; it translates literally as "Are you sure that you like to encrypt the pocket?", which is not appropriate for the technical term "wallet" (here meaning Bitcoin wallet) or for "encrypt".

Correct translation:
Ma hubtaa inaad rabto inaad jeebkaaga sirgaysato?
OR (more formally/technically accurate)
Ma hubtaa inaad rabto inaad kaydkaaga qariso?
OR
Ma hubtaa inaad rabto inaad sirgaysato boorsadaada?
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Ku qor passrase cusub jeebka.&lt;br/&gt;Fadlan isticmaal ereygii passphrase ah &lt;b&gt;toban ama in ka badan characters random&lt;/b&gt;ama&lt;b&gt;sideed ama kabadan&lt;/b&gt;.</translation>
    
YES
The translation is inaccurate and incomplete. Several elements are missing, such as the words "words" and there is poor handling of spacing around tags and format. The phrase "characters random" should be "xarfo aan la isku xirin". Also, "jeebka" is a literal translation of "wallet" but "jeebka" means "pocket" in Somali, while "wallet" as a crypto wallet should be "boorsada" or "kaydiska" to avoid confusion. "passphrase" should be localized or quoted if no Somali equivalent. Also, missing is the full sentence structure and proper linkage.

Correct translation:
Geli erayga sirta cusub ee boorsada.&lt;br/&gt;Fadlan isticmaal &lt;b&gt;toban ama in ka badan xarfo aan la isku xirin&lt;/b&gt;, ama &lt;b&gt;sideed ama in ka badan erayo&lt;/b&gt; oo kala duwan.
```

```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>sideed ula kacsan ama kabadan</translation>
    
YES
The translation is completely incorrect and unrelated to the source sentence. The Somali phrase "sideed ula kacsan ama kabadan" does not translate to "Enter the old passphrase and new passphrase for the wallet." It appears to be nonsensical in this context.

Correct translation:
Geli erayga sirta hore iyo erayga sirta cusub ee boorsada.
```

```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Xusuusnow in encrypting jeebka si buuxda ma uu ilaalin karo bitcoins aad ka xado by furin qaadsiinaya aad computer.</translation>
    
YES
The translation is problematic for the following reasons:
- It awkwardly mixes Somali and English (“encrypting”, "by", "bitcoins") rather than using Somali equivalents.
- The phrase "furin qaadsiinaya" is an unclear or incorrect attempt at 'malware infecting'.
- Sentence structure is not natural in Somali.
- There are stray spaces ("ka xado by furin").
- The translation is inaccurate and unclear for Somali speakers.

Correct translation:
Xusuusnow in jeebkaaga la sirayo aysan si buuxda u ilaalin karin bitcoins-kaaga, haddii barnaamij xun uu ku dhaco kombiyuutarkaaga.
```

```
        <source>Wallet to be encrypted</source>
        <translation>Jeebka in la encrypted</translation>
    
YES
The translation is partly Anglicized and ungrammatical. The word "encrypted" is not translated into Somali; it should be localized. Also "Jeebka" means "the pocket" and is not a common translation for "wallet" in the context of Bitcoin—the preferred term is "boorsada" or "boorsada lacagta".

Correct translation:
Boorsada waa in la sirgaxaa
```

```
        <source>Your wallet is about to be encrypted. </source>
        <translation>Jeebka in aan la xarriiqin</translation>
    
YES
The translation is inaccurate. The English sentence states "Your wallet is about to be encrypted", which means the wallet will soon be encrypted. The Somali translation "Jeebka in aan la xarriiqin" is incorrect; "Jeebka" means "wallet" but "in aan la xarriiqin" may mean "that is not to be drawn" or "not to be crossed out" and does not convey the meaning of encryption.

Correct translation:
Boorsadaada waa la ilaalinayaa (ama "Boorsadaada waa la qarfinayaa")
```

```
        <source>The supplied passphrases do not match.</source>
        <translation>Supplied passrases ma u dhigma.</translation>
    
YES
The translation is incorrect. It is mostly in English with only "ma u dhigma" in Somali, and contains a spelling error ("passrases" instead of "passphrases"). 

Correct translation:
Erayada sirta ah ee la bixiyay isma mid aha.
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Passrase soo galay for decryption jeebka ahaa mid khaldan.</translation>
    
YES
The translation contains grammatical errors and an unnatural mix of English and Somali. 'Passrase soo galay for decryption jeebka' is not proper Somali and includes unnecessary English words ("for decryption"). Also, "wallet" is more clearly translated as "boorsada" or "wallet-ka" in Somali.

Correct translation:
Erayga sirta ah ee loo geliyay furitaanka boorsada waa mid khaldan.
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Settings file,%1waxaa laga yaabaa in musuqmaasuq ama aan asal ahayn.</translation>
    
YES
The translation is problematic for several reasons:
- The English term "Settings file" is untranslated; it should be rendered in Somali.
- There is a stray comma after "Settings file", which is not present in the source.
- "%1" is merged directly with Somali words without appropriate spacing.
- The tone and choice of "musuqmaasuq" (corruption) is correct, but "aan asal ahayn" is unclear for "invalid".

Correct translation:
Faylka dejinta %1 waxa laga yaabaa inuu musuqmaasuqmo ama aanu sax ahayn.
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>Qalad gudaha ah ayaa dhacay.%1isku dayi doonaan in ay si ammaan ah u sii socdaan. Kani waa cayil aan la filayn oo la soo sheegi karo sida hoos ku xusan.</translation>
    
YES
There are two issues:

1. Missing space after the period: ".%1isku" should be ". %1 isku"
2. "cayil" is an incorrect term for "bug" in Somali, as "cayil" means "fat." The correct word is "cilad" or "khalad" for "bug."

Correct translation:
Qalad gudaha ah ayaa dhacay. %1 waxay isku dayi doonaan inay si ammaan ah u sii socdaan. Kani waa cilad aan la filayn oo la soo sheegi karo sida hoos ku xusan.
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>Waxaa dhacday qalad dilaa ah. Hubi in file settings waa writable, ama isku day inaad la -nosettings socda.</translation>
    
YES
The translation contains several issues:
- "file settings waa writable" mixes English and Somali; "writable" should be rendered in Somali.
- "la -nosettings socda" is awkward; it would be better as "ku soco" or "isticmaal".
- The word order/grammar can be improved for clarity.

Correct translation:
Waxaa dhacay qalad halis ah. Hubi in faylka dejinta la qori karo, ama isku day inaad ku socoto adigoo isticmaalaya -nosettings.
```

```
        <source>Transactions</source>
        <translation>Transaction-yada</translation>
    
YES
The translation "Transaction-yada" is incorrect for Somali ('so'). It inappropriately blends English ("Transaction") with a Somali plural suffix ("-yada"). The correct Somali word for "Transactions" is "Xawaaladaha" or "Macamilada" depending on the context, but "Xawaaladaha" is commonly used for financial transactions.

Correct translation:
Xawaaladaha
```

```
        <source>Exit</source>
        <translation>ka bax</translation>
    
YES
The translation "ka bax" is understandable in Somali and means "get out" or "leave," but it is more colloquial and less formal than the appropriate imperative or menu context use for "Exit" in software.

Correct translation:
Bax

This is more standard for application menus.
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comma kala file</translation>
    
YES
The translation "Comma kala file" is incorrect in Somali, and does not accurately translate "Comma separated file". "Kala" by itself means "separate" but the phrase does not make sense as written. Also, terms like "comma" and "file" may be localized or more appropriately explained to Somali speakers.

Correct translation:
Faylka kooxo lagu kala saaray faasiil (,)
```

```
        <source>Export</source>
        <translation> Dhoofinta</translation>
    
YES
There is an extra leading whitespace in the translation, which is a formatting issue. Also, while "Dhoofinta" means "The export" (noun), in software context "Export" as an action/button is better rendered as "Dhoof", which is the imperative/verb form.

Correct translation:
Dhoof

Or, if noun is intended (less common for UI buttons):
Dhoofin

So the best translation here is:
Dhoof
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>Sida loo tababbardhigo qaabka loo takhasusay</translation>
    
YES  
The provided translation is inaccurate and does not convey the meaning of the English source, which is about exporting data from the current tab into a file. The Somali text given roughly translates to "How to specialize the way of training", which is unrelated.  

Correct translation:  
Dhoofinta xogta ku jirta tabka hadda furan ee fayl.
```
</details>

Number of issues: 33.
