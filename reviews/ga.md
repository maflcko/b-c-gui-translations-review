# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ga</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bga%5D%20low%20quality)


<!-- cache_translation_check_ga_a76f02c2625faa3c26bf62a305ec068da9a05b182f189ebbf2a0015e2c7e887e -->
```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
ERR
The translation is inaccurate. "Comhad athróige camógdheighilte" means "variable file, comma-separated" or "variable, comma-separated file", which is incorrect and unnatural. The standard translation for "Comma separated file" is "Comhad camógscartha".

Correct translation:
Comhad camógscartha
```

<!-- cache_translation_check_ga_3fbf62e4aafbf3e42b3d85ba07d24d2252389dd42aaed59d53e6f25908378c1b -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Iontráil an pasfhrása nua don sparán. &lt;br/&gt;Le do thoil úsáid pasfhocail de &lt;b&gt;dheich gcarachtar randamacha nó níos mó&lt;/b&gt;, nó &lt;/b&gt;ocht bhfocal nó níos mó&lt;/b&gt;.</translation>
    
ERR
There are a few issues:
1. Incorrect translation of "passphrase" as "pasfhocal" in the second sentence; it should remain consistent as "pasfhrása" or "frása faire".
2. Mismatched HTML tags: the opening <b> for "eight or more words" is missing (it has a closing </b> only).
3. Slight awkwardness: "úsáid pasfhocail" is better as "úsáid pasfhrása" (passphrase), or more literally "frása faire".
4. "randamacha" should be "randamach" to agree with "carachtar" (singular).

Correct translation:
Iontráil an pasfhrása nua don sparán.&lt;br/&gt;Le do thoil, bain úsáid as pasfhrása de &lt;b&gt;dheich gcarachtar randamach ar a laghad&lt;/b&gt;, nó &lt;b&gt;ocht bhfocal ar a laghad&lt;/b&gt;.
```

<!-- cache_translation_check_ga_071cef8df8f79add676e1e50e0713518b8b57e9d90cca34b35297ce5a67c37f9 -->
```
        <source>IP/Netmask</source>
        <translation>PI/Mascadhidirlíon</translation>
    
ERR
"Mascadhidirlíon" is a misspelling and awkward combination; the standard Irish term is "masc líonra" or "masc líonra/IP". Also, "PI" should be "IP" in Irish, as the abbreviation is standard.

Correct translation:
IP/masc líonra
```

<!-- cache_translation_check_ga_35ce3e95966fdd3e569b5f5ec2779e077dfd87065cf721a3fc05fc214bef7235 -->
```
        <source>%1 d</source>
        <translation>%1 l</translation>
    
ERR
The translation is incorrect. The English "%1 d" represents a placeholder for "days" (d = days). In Irish ('ga'), the abbreviation for day is "l" for "lá", but this is not a standard or commonly recognized abbreviation in Irish for "day" as a standalone; however, in context, "l" may sometimes be used, but typically "la" or "lá" would be clearer. Also, "d" as an abbreviation is not appropriate for Irish. If brevity is necessary for UI, use "la" (without an accent, as accents are often omitted in short formats), or "lá" if space allows. So "%1 l" is somewhat understandable, but potentially confusing and not the best choice.

Correct translation:
%1 lá

Or, for very short UIs:
%1 la
```

<!-- cache_translation_check_ga_960f84a66baa6755f976c33c0a3e1f3a9e45c9117efe19ac368cf962c5bbe9bf -->
```
        <source>%1 m</source>
        <translation>%1 n</translation>
    
ERR
The translation is incorrect. In the context of Bitcoin (and generally), "m" stands for "meters" (if used literally), but it can also be a unit prefix, whereas "n" is not a standard replacement in Irish for "m". In Irish, the abbreviation for "meter" is also "m". Therefore, the format specifier should remain unchanged.

Correct translation:
%1 m
```

<!-- cache_translation_check_ga_651f56239b4d952cd82352f53ce66b9ff56d4f9578a3c16e955f69b67d546e42 -->
```
        <source>N/A</source>
        <translation>N/B</translation>
    
ERR
"N/A" in English typically stands for "Not Applicable" or "Not Available". In Irish ('ga'), the standard translation is "N/B" for "Níl Bailí" (not valid) or sometimes "N/A" is kept due to widespread recognition, but "N/B" is acceptable. However, for clarity and more common usage, you might consider "N/A" or "Níl ar Fáil".

Correct translation:
Níl ar Fáil
```

<!-- cache_translation_check_ga_71f105c04bc3a7839d47ee7c3517f00982e44c7a44bb32089d473533a48f1587 -->
```
        <source>Syncing Headers (%1%)…</source>
        <translation>Ceanntásca á Sioncronú (%1 %)…</translation>
    
ERR
There is an issue with spacing in the format specifier. In the source, the format is "%1%" with no space between the number and percent sign. In the translation, there is a space: "%1 %", which is incorrect. Also, the translation could be slightly improved for clarity and conciseness.

Correct translation:
Ceanntásca á shioncronú (%1%)…
```

<!-- cache_translation_check_ga_1a9d7941ee4ff8f43e33d55452428a54bf7b4af55623f65cfad4a23c72510b17 -->
```
        <source>Show the list of used sending addresses and labels</source>
        <translation>Taispeáin an liosta de seoltaí seoladh úsáidte agus na lipéid </translation>
    
ERR
There are a few issues:
1. The word "seoltaí seoladh úsáidte" is confusing and redundant; "seoltaí seoladh" (addresses address) does not make sense.
2. The phrase has an extra space at the end.
3. A better translation for "used sending addresses" would be "na seoltaí seolta úsáide" or "na seoltaí seolta a úsáideadh".

Correct translation:
Taispeáin an liosta de na seoltaí seolta a úsáideadh agus na lipéid
```

<!-- cache_translation_check_ga_110e3bbacaa2fb46955a1a8b1f16300bf5ca8e9857789997534eed7a6e1f642a -->
```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>Taispeáin an liosta de seoltaí glacadh úsáidte agus lipéid </translation>
    
ERR
There is a minor grammatical error: "de seoltaí glacadh úsáidte" should be "de na seoltaí glacadh a úsáideadh" for correct Irish. Also, there is an extra space at the end.

Correct translation:
Taispeáin an liosta de na seoltaí glacadh a úsáideadh agus lipéid
```

<!-- cache_translation_check_ga_dde248ac6ef0c8631ece76c08a962da5af981093ee819c9aeebbb18bda2a8fe5 -->
```
        <source>Sending addresses</source>
        <translation>Seoltaí seoladh</translation>
    
ERR
The translation is erroneous. "Seoltaí seoladh" is incorrect and redundant ("seoltaí" is plural of "seoladh", and "seoladh" means "address"). The correct translation for "Sending addresses" (i.e., addresses from which coins are sent) is:

Seoltaí seolta (or) Seoltaí seolta amach

However, a more idiomatic and widely accepted translation would be:

Seoltaí seolta

Correct translation:
Seoltaí seolta
```

<!-- cache_translation_check_ga_c404e8d632f955f20538c55725a2cb700f45401c9b277a0cb8ce5b188e534a08 -->
```
        <source>%1 client</source>
        <translation>%1 cliaint</translation>
    
ERR
The Irish translation incorrectly uses the English word "cliaint" instead of the correct Irish word "cliant". The word "cliaint" would also mean "clients" (plural), but the source is singular. The correct singular is "cliant".

Correct translation:
%1 cliant
```

<!-- cache_translation_check_ga_a1b107b1ba2b95857e97ec56fcce447d8fac6daa36c6f4d42f41551c3d49ea06 -->
```
        <source>Show</source>
        <translation>Sconas</translation>
    
ERR
The translation "Sconas" is incorrect for "Show" in Irish ('ga'). "Sconas" is not the correct Irish term for "show".

Correct translation:
Taispeáin
```

<!-- cache_translation_check_ga_dd1e7dfd96cdcd3d16e2fd27f51da47248d6e6db97ee9537d326ff4820328d01 -->
```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Sparán &lt;b&gt;criptithe&lt;/b&gt;agus &lt;b&gt;díghlasáilte&lt;/b&gt;faoi láthair</translation>
    
ERR
There is a spacing issue in the translation: there should be a space between "criptithe" and "agus", and between "díghlasáilte" and "faoi láthair". 

Correct translation:
Sparán &lt;b&gt;criptithe&lt;/b&gt; agus &lt;b&gt;díghlasáilte&lt;/b&gt; faoi láthair
```

<!-- cache_translation_check_ga_61a5501bb18f00c6d00c17fd5b7f2692ac6e452d52190565b7884243493f84da -->
```
        <source>Received with address</source>
        <translation>Seoladh faighte le</translation>
    
ERR
The word order is incorrect in Irish. "Seoladh faighte le" literally means "Address received with," which is awkward and potentially confusing in Irish. The more natural and accurate translation would be:

Correct translation:
Faighte le seoladh

This places "Faighte" ("Received") at the front, mirroring the English structure and typical Irish phrasing.
```

<!-- cache_translation_check_ga_2991e6a538c99d30a25eed0362f86c488380d59df3bbc4695bda8d3f8a6892e8 -->
```
        <source>Copy transaction ID and output index</source>
        <translation>Cóipeáil idirbheart  ID agus innéacs aschuir</translation>
    
ERR
There is a spacing error in the translation: "idirbheart  ID" has a double space between "idirbheart" and "ID". Also, in Irish, "ID" can often remain untranslated as an acronym, but it is clearer to format as "ID idirbhirt" (transaction ID). The translation could be more idiomatic and clearer.

Correct translation:
Cóipeáil ID idirbhirt agus innéacs aschuir
```

<!-- cache_translation_check_ga_f76515df9b1327b7dff3c27143b961a7b5039149a0885aa08c6c3154559e7da7 -->
```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
ERR
The translation is problematic. The word "Cóipeáíl" is a misspelling; the correct Irish for "Copy" is "Cóipeáil". The word "sóinseáil" can theoretically mean "change" in some contexts, but it is an uncommon form and may not be immediately recognized as referring to the change amount in a transaction; "sóinseáil" typically means "to change" rather than the noun "change".

A better translation for "change" as the amount returned in a transaction is "aisiú" or "fáisceáil". However, "aisiúchán" is used in banking contexts for "change returned". In the Bitcoin context, "aisiú" or "aisiúchán" would be most understandable.

Correct translation:
Cóipeáil an t-aisiú
```

<!-- cache_translation_check_ga_d041ae8cf491f80d6f21695da32ac3ed0f6ebfe7b2af96807e6120b8a73d5d5a -->
```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>An bhfuil tú cinnte gur mian leat an sparán &lt;i&gt;%1 &lt;/i&gt;?</translation>
    
ERR
There is a minor formatting issue: there is an extra space before the closing &lt;/i&gt; tag in the translation that is not in the source. This could affect display in some UIs.

Correct translation:
An bhfuil tú cinnte gur mian leat an sparán &lt;i&gt;%1&lt;/i&gt; a aistriú?
(Note: Also, the original translation omits the verb "migrate" (a aistriú). To fully reflect the source, add "a aistriú" at the end.)

Final correct translation:
An bhfuil tú cinnte gur mian leat an sparán &lt;i&gt;%1&lt;/i&gt; a aistriú?
```

<!-- cache_translation_check_ga_f68e95f5d08b1ceccbb0c523c9e4b55b5fc511a0456e3b41be3420fd8942ef6d -->
```
        <source>Opening Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the open wallet progress window which indicates to the user which wallet is currently being opened.</extracomment>
        <translation>Sparán Oscailte&lt;b&gt;%1&lt;/b&gt;…</translation>
    
ERR
The translation has a word order issue. "Sparán Oscailte" means "Opened Wallet", not "Opening Wallet". The correct translation for "Opening Wallet" is "Sparán á Oscailt". Also, there should be a space before the opening <b> tag for proper formatting.

Correct translation:
Sparán á oscailt &lt;b&gt;%1&lt;/b&gt;…
```

<!-- cache_translation_check_ga_0e585a5ef038709071eec06768f45d6a3e93c6077b0939052e36bef36e262590 -->
```
        <source>Restore wallet message</source>
        <extracomment>Title of message box which is displayed when the wallet is successfully restored.</extracomment>
        <translation>Athchóirigh teachtaireacht sparán</translation>
    
ERR
The translation "Athchóirigh teachtaireacht sparán" literally means "Restore wallet message" as in "restore the message of the wallet," which is incorrect for the context ("Title of message box which is displayed when the wallet is successfully restored."), where it should likely convey something like "Wallet Restored" or "Wallet Successfully Restored".

Correct translation:
Sparán athchóirithe
```

<!-- cache_translation_check_ga_16a829ea7557691e9e0377a6fe0f9de4a648186fe1018f8ce46caccf5a019625 -->
```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>An seoladh chomhcheangailte leis an iontráil liosta seoltaí seo. Ní féidir é seo a mionathraithe ach do seoltaí seoladh.</translation>
    
ERR
The Irish ('ga') translation is problematic: "Ní féidir é seo a mionathraithe ach do seoltaí seoladh" is awkward and incorrect. The part "do seoltaí seoladh" is ungrammatical and unclear; "mionathraithe" should be "mionathrú" in this construction.

Correct translation:
An seoladh a bhaineann leis an iontráil liosta seoltaí seo. Ní féidir é seo a athrú ach amháin do sheoltaí seolta.
```

<!-- cache_translation_check_ga_511f70952f678ca37e9af45a5d8f70831ccfdac0c6951b6ffc94b170c299618e -->
```
        <source>New sending address</source>
        <translation>Seoladh nua seoladh</translation>
    
ERR
The translation is incorrect and repeats the word "seoladh" (address) instead of conveying the intended meaning of "New sending address". The correct translation should be:

Seoladh nua seolta

Or, to be more explicit:

Seoladh nua seolta amach

Either is preferable to the current version.
```

<!-- cache_translation_check_ga_7f8254ab58a12f0acb39c67dc845b3c7a558b84e685714f1f03c43c652b8e3a1 -->
```
        <source>Edit sending address</source>
        <translation>Eagarthóireacht seoladh seoladh</translation>
    
ERR
The translation is problematic because "Eagarthóireacht seoladh seoladh" repeats "seoladh" (address) unnecessarily and uses "Eagarthóireacht" (editing) instead of the verb/imperative or noun form.

Correct translation:
Cuir eagar ar sheoladh seolta
```

<!-- cache_translation_check_ga_3889859f5376cadf343ffd28833f0421ffd372555c1e9e015831b5abd2f2d06a -->
```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Stórálfar thart ar %1 GB de shonraí sa comhadlann seo.</translation>
    
ERR
The Irish translation contains a minor grammatical mistake: "sa comhadlann" should be "sa chomhadlann" (the lenition of "c" after "sa") and "Stórálfar" is a verb form that is uncommon or inappropriate here. A more idiomatic rendering would use "Stórálfar" in passive or just use the present tense.

Correct translation:
Stórálfar thart ar %1 GB de shonraí sa chomhadlann seo.
Alternative (more common):
Stórálfar thart ar %1 GB de shonraí sa chomhadlann seo.

But since "Stórálfar" is less idiomatic, a better translation is:
Beidh thart ar %1 GB de shonraí á stóráil sa chomhadlann seo.
```

<!-- cache_translation_check_ga_d27d3e63f81d44d170d929e0822366e1528961ba6d293942b6e7503528dc68d7 -->
```
        <source>Last block time</source>
        <translation>Am bloc deireanach</translation>
    
ERR
The translation "Am bloc deireanach" means "Last block" not "Last block time". It omits the reference to "time".

Correct translation:
Am an bhloic dheireanaigh
```

<!-- cache_translation_check_ga_dbc6b8a5a75395ee9894e7ebf727f035d71c8d632077b3918795633bdd3f07cb -->
```
        <source>OK</source>
        <translation>Togha</translation>
    
ERR
The translation of "OK" as "Togha" is problematic. "Togha" means "choice" or "selection" in Irish, not the interjection "OK". The more standard translation for "OK" in Irish is "Ceart go leor".

Correct translation:
Ceart go leor
```

<!-- cache_translation_check_ga_651f56239b4d952cd82352f53ce66b9ff56d4f9578a3c16e955f69b67d546e42 -->
```
        <source>N/A</source>
        <translation>N/B</translation>
    
ERR
"N/A" in English typically stands for "Not Applicable" or "Not Available". In Irish ('ga'), the standard translation is "N/B" for "Níl Bailí" (not valid) or sometimes "N/A" is kept due to widespread recognition, but "N/B" is acceptable. However, for clarity and more common usage, you might consider "N/A" or "Níl ar Fáil".

Correct translation:
Níl ar Fáil
```

<!-- cache_translation_check_ga_3d6b1059ab517dca08c0b1d63fb1ee6951da3e43ad6166b370395910c53923a9 -->
```
        <source>Blocksdir</source>
        <translation>Eolbloic</translation>
    
ERR
The translation "Eolbloic" is not accurate for "Blocksdir". The term "Blocksdir" refers to the directory where blocks are stored, usually used as a technical term in Bitcoin software. The translation should either retain "Blocksdir" as a technical term, or provide an equivalent Irish term such as "comhadlann na mbloc" (directory of blocks) or simply "Comhadlann Bloic".

Correct translation:
Comhadlann Bloic
```

<!-- cache_translation_check_ga_d27d3e63f81d44d170d929e0822366e1528961ba6d293942b6e7503528dc68d7 -->
```
        <source>Last block time</source>
        <translation>Am bloc deireanach</translation>
    
ERR
The translation "Am bloc deireanach" means "Last block" not "Last block time". It omits the reference to "time".

Correct translation:
Am an bhloic dheireanaigh
```

<!-- cache_translation_check_ga_8e3580f9b44f60cd0a35aa583559d173f4d399321201a1e5e6eafe3ad17eb574 -->
```
        <source>detecting: peer could be v1 or v2</source>
        <extracomment>Explanatory text for "detecting" transport type.</extracomment>
        <translation>bhrath: d’fhéadfadh v1 nó v2 a bheith i gcomhghleacaí</translation>
    
ERR
The translation is problematic. The English "detecting: peer could be v1 or v2" means "detecting" as an action happening now, not as a noun. The Irish "bhrath: d’fhéadfadh v1 nó v2 a bheith i gcomhghleacaí" renders "bhrath" as a noun ("detection"), which is not correct. Also, "i gcomhghleacaí" is awkward; it would be better as "an comhghleacaí" for "the peer."

Correct translation:
Ag braiteadh: d’fhéadfadh an comhghleacaí a bheith ina v1 nó v2
```

<!-- cache_translation_check_ga_223b3214290943e3b57d27a0d26c5f92e680afbbfe05be390e6510ce194a724f -->
```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>Fáilte go consól RPC %1.
Úsáid saigheada suas agus síos chun an stair a nascleanúint, agus %2 chun an scáileán a ghlanadh.
Úsáid %3 agus %4 chun an clómhéid a mhéadú nó a laghdú.
Clóscríobh %5 le haghaidh forbhreathnú ar na horduithe atá ar fáil.
Chun tuilleadh eolais a fháil faoin gconsól seo a úsáid, clóscríobh %6.

%7 RABHADH: Bhí scamadóirí gníomhach, ag rá le húsáideoirí orduithe a chlóscríobh anseo, ag goid a n-inneachar sparán. Ná húsáid an consól seo gan iarmhairtí ordaithe a thuiscint go hiomlán.%8</translation>
    
ERR
There are some issues in the Irish ('ga') translation:

1. The translation adds a space after %7 (" %7 RABHADH:"), but the source intentionally does not have a space so that the style tag starts immediately. This mismatch may affect formatting/styling.
2. The translation for "WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents." uses "Bhí scamadóirí gníomhach," which is not the most natural way of saying "Scammers have been active," and mixes perfect/continuous tense.
3. "ag goid a n-inneachar sparán" is awkward; "inneachar sparán" is not idiomatic for "wallet contents". More proper would be "airgead óna sparán" ("money from their wallets").
4. "iarmhairtí ordaithe" is ambiguous compared to "the ramifications of a command." Better: "iarmhairtí aon ordaithe".

Correct translation:
Fáilte go dtí consól RPC %1.
Úsáid na saigheada suas agus síos chun an stair a nascleanúint, agus %2 chun an scáileán a ghlanadh.
Úsáid %3 agus %4 chun an clómhéid a mhéadú nó a laghdú.
Clóscríobh %5 le haghaidh forbhreathnú ar na horduithe atá ar fáil.
Chun tuilleadh eolais a fháil faoin gconsól seo, clóscríobh %6.

%7RABHADH: Tá scamadóirí gníomhach ag insint d’úsáideoirí orduithe a chlóscríobh anseo agus ag goid airgid óna sparán. Ná húsáid an consól seo gan na hiarmhairtí a d’fhéadfadh a bheith le hordú a thuiscint go hiomlán.%8
```

<!-- cache_translation_check_ga_3e4c988794fb24f8434c677a150cd8acea1d294e72925bd94071068659e4369f -->
```
        <source>Copy message</source>
        <translation>Cóipeáil  teachtaireacht</translation>
    
ERR
There is an extra space before "teachtaireacht" in the translation, which creates a whitespace formatting issue.

Correct translation:
Cóipeáil teachtaireacht
```

<!-- cache_translation_check_ga_9765dc041f34a3683c1de71a6e54bc7d34bcdf3c57f41c48a953877b24e7eeee -->
```
        <source>Base58 (P2SH-SegWit)</source>
        <translation>Base58 (P2SH- SegWit)</translation>
    
ERR
There is an unwanted space between "P2SH-" and "SegWit" in the translation, which is not present in the source.

Correct translation:
Base58 (P2SH-SegWit)
```

<!-- cache_translation_check_ga_cbea20dc1116a68ee1b4b83300e976f39c2701b918b4b98daed2238d84ee726b -->
```
        <source>Recommended:</source>
        <translation>Molta:</translation>
    
ERR
The translation "Molta:" is incorrect for Irish ('ga'). "Molta" is Irish for "recommendations," but it's not used as an adjective or standalone in this context. The correct translation for "Recommended:" (as in "suggested" or "advised") is "Moltar:".

Correct translation:
Moltar:
```

<!-- cache_translation_check_ga_f76515df9b1327b7dff3c27143b961a7b5039149a0885aa08c6c3154559e7da7 -->
```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
ERR
The translation is problematic. The word "Cóipeáíl" is a misspelling; the correct Irish for "Copy" is "Cóipeáil". The word "sóinseáil" can theoretically mean "change" in some contexts, but it is an uncommon form and may not be immediately recognized as referring to the change amount in a transaction; "sóinseáil" typically means "to change" rather than the noun "change".

A better translation for "change" as the amount returned in a transaction is "aisiú" or "fáisceáil". However, "aisiúchán" is used in banking contexts for "change returned". In the Bitcoin context, "aisiú" or "aisiúchán" would be most understandable.

Correct translation:
Cóipeáil an t-aisiú
```

<!-- cache_translation_check_ga_9ff585780fbad9a032a41d648778cf6646d00936e407101d590cfdfb76d7dfe2 -->
```
        <source>PSBT saved</source>
        <extracomment>Popup message when a PSBT has been saved to a file</extracomment>
        <translation>IBSP sábháilte</translation>
    
ERR
The translation is problematic because "IBSP" is an incorrect transliteration of "PSBT" (which stands for "Partially Signed Bitcoin Transaction"). The standard in Irish would be to retain "PSBT" as it is, since it is an established acronym in the Bitcoin context. Also, the Irish word for "saved" is "sábhálta", not "sábháilte" (which is a misspelling). Therefore, the translation should read:

Correct translation:
PSBT sábhálta
```

<!-- cache_translation_check_ga_c47725dfbf4dbb2b4fd6b4b2c8edcc2a25d6ed32bfaac8e9c005cf46eca7095f -->
```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>Níl comhartha chuig Athchuir-Le-Táille, BIP-125</translation>
    
ERR
The translation is understandable but not entirely correct or idiomatic in Irish. "comhartha chuig" is awkward for "signalling", and "Athchuir-Le-Táille" is a direct translation, but typically "Replace-By-Fee" is not translated in technical Irish content. Also, a full stop is missing at the end.

Correct translation:
Níl Replace-By-Fee, BIP-125, á chomharthaíocht.
```

<!-- cache_translation_check_ga_ef7e6af5c62970b5fe0e53653efe71cadf5a5edd2e0b616d73d414c9e1cb9686 -->
```
        <source>Generated</source>
        <translation>Ghinte</translation>
    
ERR
The translation "Ghinte" is not a correct or established Irish ('ga') translation for "Generated". The correct Irish translation would be "Ginte" or "Cruthaithe," depending on context. "Ginte" is the standard past participle for "generate" (to have been generated). "Ghinte" is a dialect or spelling variant, but "Ginte" is standard.

Correct translation:
Ginte
```

<!-- cache_translation_check_ga_297c479cfdef568465f7956edda60e8a65207b9199bdc07ee8e755372bfeb0a1 -->
```
        <source>Copy transaction ID</source>
        <translation>Cóipeáil idirbheart ID</translation>
    
ERR
The translation is problematic because the word order is incorrect, and 'ID' should be qualified as 'aitheantas' or 'ID'. The correct translation should be:

Cóipeáil aitheantas an idirbhirt

or

Cóipeáil ID an idirbhirt
```

<!-- cache_translation_check_ga_25a6dcf3bd8b34af382759b764dd358977f9b94640b6f08c3969ddc62567d1d0 -->
```
        <source>Copy full transaction details</source>
        <translation>Cóipeáil idirbheart agus sonraí iomlána</translation>
    
ERR
The translation is understandable but not fully accurate. The phrase "Cóipeáil idirbheart agus sonraí iomlána" translates as "Copy transaction and full details," which parses the phrase incorrectly. The correct translation should keep "transaction details" together, referring to the "full transaction details" as a unit.

Correct translation:
Cóipeáil sonraí iomlána na hidirbhearta
```

<!-- cache_translation_check_ga_5bf127badf502b0f8081903a509d7800d7e99eab060f29b5069c2961d8d13422 -->
```
        <source>Increase transaction fee</source>
        <translation>Méadaigh idirbheart  táille</translation>
    
ERR
There is an erroneous whitespace in the translation between "idirbheart" and "táille". It should read "idirbheart táille" as one phrase ("transaction fee increase"), but the phrase order is awkward for Irish. A better translation would use "Méadaigh an táille idirbhirt" ("Increase the transaction fee").

Correct translation:
Méadaigh an táille idirbhirt
```

<!-- cache_translation_check_ga_a76f02c2625faa3c26bf62a305ec068da9a05b182f189ebbf2a0015e2c7e887e -->
```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
ERR
The translation is inaccurate. "Comhad athróige camógdheighilte" means "variable file, comma-separated" or "variable, comma-separated file", which is incorrect and unnatural. The standard translation for "Comma separated file" is "Comhad camógscartha".

Correct translation:
Comhad camógscartha
```

<!-- cache_translation_check_ga_c0c03732067f428fdf7e15e267cd9a9032ed2dee743d26b61f495e9612acaefa -->
```
        <source>Watch-only</source>
        <translation>Faire-amháin</translation>
    
ERR
The translation "Faire-amháin" is incorrect; it is a calque from English. In Irish, "faire" is not used for "watch" in this context. The established term in the Irish Bitcoin community is "Amharc amháin".

Correct translation:
Amharc amháin
```

<!-- cache_translation_check_ga_3be7182e3268aae212ce152f9791da5f1e49fffdac1936b1e4b57b05ba9d5f07 -->
```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>Cóipeáil PSBT bump táille chuig an ngearrthaisce</translation>
    
ERR
The translation "Cóipeáil PSBT bump táille chuig an ngearrthaisce" is problematic. The verb is in the imperative ("copy"), rather than indicating that the action has been completed ("copied"). Additionally, the term "fee-bump" should ideally be translated or clearly explained in Irish, though "bump táille" is increasingly used in technical contexts. Better Irish syntax would be beneficial.

Correct translation:
PSBT bump táille cóipeáilte chuig an ngearrthaisce
```

<!-- cache_translation_check_ga_c33ad8874e90aa7b0ea59b40febb4ae0814337addc2216e5f1c1eeb46cb7f059 -->
```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>Theip ar %s an staid snapshot -assumeutxo a bhailíochtú. Léiríonn sé seo fadhb crua-earraí, nó fabht sna bogearraí, nó droch-mhodhnú bogearraí a cheadaigh pictiúr neamhbhailí a luchtú. Mar thoradh air seo, stopfar an nód agus stopfaidh sé de úsáid a bhaint as staid ar bith a tógadh ar an seat, ag athshocrú airde an tslabhra ó%dgo%d. Ar an gcéad atosú eile, athchromfar ar an nód ag sioncronú ó %d gan úsáid a bhaint as sonraí seat. Tuairiscigh an teagmhas seo do %s lena n-áirítear conas a fuair tú an pictiúr. Fágfar an slabhrashlabhra neamhbhailí ar an diosca ar eagla go mbeadh sé ina chuidiú leis an tsaincheist ba chúis leis an earráid seo a dhiagnóisiú.</translation>
    
ERR
There are several issues:

1. "staid snapshot -assumeutxo" is awkward; "staid seatamh snapshot -assumeutxo" or "staid seatamh -assumeutxo" is more idiomatic.
2. "pictiúr" is used for "snapshot" in two places, but "seatamh" (snapshot/seat) is the standard technical translation in blockchain contexts; "pictiúr" just means "picture".
3. "an seat" is used for "the snapshot", but "seat" is not a word in Irish—the correct word is "seatamh".
4. There are missing spaces in format specifiers: e.g., "ó%dgo%d" should be "ó %d go %d".
5. "slabhrashlabhra neamhbhailí" contains a duplicated word.
6. General phrasing is off, and some sentences lack clarity.

Correct translation:
Theip ar %s bailíochtú a dhéanamh ar staid seatamh -assumeutxo. Léiríonn sé seo fadhb crua-earraí, nó fabht sa bhogearra, nó droch-mhodhnú bogearraí a cheadaigh seatamh neamhbhailí a luchtú. Mar thoradh air seo, múchfar an nód agus stopfaidh sé de bheith ag úsáid aon staid a tógadh ar an seatamh, agus athshocrófar airde an tslabhra ó %d go %d. Ar an gcéad atosú eile, leanfaidh an nód ag sioncronú ó %d gan sonraí seatamh a úsáid. Tuairiscigh an teagmhas seo do %s agus mínigh conas a fuair tú an seatamh. Fágfar an seatamh neamhbhailí ar an diosca ar eagla go gcabhródh sé le fadhb an earráide a aimsiú.
```

<!-- cache_translation_check_ga_85cc96759b6ba5f76f567c6ce64b61824546dc28916a080e7b1f49e0bdf62936 -->
```
        <source>Cannot downgrade wallet from version %i to version %i. Wallet version unchanged.</source>
        <translation>Ní féidir an sparán a íosghrádú ó leagan %igo leagan%i. Leagan sparán gan athrú.</translation>
    
ERR
There is a formatting error with the placement of the format specifiers: there should be spaces between '%i' and the succeeding text ("leagan %i go leagan %i"). Also, "gan athrú" fits, but "Leagan an sparán gan athrú" is more idiomatic for "Wallet version unchanged." "íosghrádú" is the correct word for "downgrade." No unwanted or spam content.

Correct translation:
Ní féidir an sparán a íosghrádú ó leagan %i go leagan %i. Leagan an sparán gan athrú.
```

<!-- cache_translation_check_ga_2a78f903ac23bb4da7bc3f9d593a4ed6e8f4023e9a9ea60a5cea643be8b2177d -->
```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>Ní féidir sparán scoilte neamh-HD a uasghrádú ó leagan%igo leagan%i gan uasghrádú chun tacú le heochrach réamh-scoilte. Úsáid leagan %i nó níl aon leagan sonraithe.</translation>
    
ERR
There are spacing issues with the format specifiers: "leagan%igo leagan%i" should be "leagan %i go leagan %i", maintaining a space before and after the format specifiers as in the source. Additionally, "heochrach réamh-scoilte" should read "réamh-eochairphóill" to match the technical term "pre-split keypool". The rest of the translation is understandable, though the last sentence could be slightly more natural.

Correct translation:
Ní féidir sparán scoilte neamh-HD a uasghrádú ó leagan %i go leagan %i gan uasghrádú chun tacú le réamh-eochairphóill. Úsáid leagan %i nó mura bhfuil leagan ar bith sonraithe.
```

<!-- cache_translation_check_ga_947364c9282f5a2577c87bdaf9f80759633b54d25263b010f3c7ac7f5fcc5dfe -->
```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Earráid agus%s á léamh! Seans go bhfuil sonraí idirbhirt in easnamh nó mícheart. Sparán athscanadh.</translation>
    
ERR
The Irish translation does not accurately capture the meaning of the source text, which specifies an error with the dumpfile format record and the expected string "format". Instead, the translation speaks about a general error when reading "%s" and suggests that transaction data might be missing or incorrect, and to rescan the wallet, which is not present in the English source.

Correct translation:
Earráid: Tá taifead formáide na comhaid dump mícheart. Fuarthas "%s", bhí "format" ag teastáil.
```

<!-- cache_translation_check_ga_dd629b17bdd9242cfe7d07f3f989770da7e250d16f7424e658d748649a7f6196 -->
```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Leibhéal logála catagóir ar leith nach dtacaítear leis%11$s=%2$s. Bhíothas ag súil le %1$s=1:2. Catagóirí bailí: %3$s. Leibhéil loga bailí: %4$s.</translation>
    
ERR
The translation contains several issues:
- There is a missing space after "leis" and before the format specifier %1$s.
- The format specifier "%1$s" is incorrectly rendered as "%11$s" in "leis%11$s", which is a typo; it should be "%1$s".
- In the expected format, "%1$s=1:2" is incorrect; it should be "%1$s=&lt;category&gt;:&lt;loglevel&gt;", just as in the original source (with placeholders kept, not literal "1:2").
- The format specifiers are not consistently preserved from the source.
- The translation omits "&lt;category&gt;:&lt;loglevel&gt;" and instead uses "1:2", which is not correct.

Correct translation:
Ní thacaítear leis an leibhéal logála catagóire-sonrach %1$s=%2$s. Bhíothas ag súil le %1$s=&lt;category&gt;:&lt;loglevel&gt;. Catagóirí bailí: %3$s. Leibhéil logála bailí: %4$s.
```

<!-- cache_translation_check_ga_360e555d9c8fa6581ae68c31fc6a7b119a1ee7a0f5a993d04ce3e6a17263e31e -->
```
        <source>%s is set very high! Fees this large could be paid on a single transaction.</source>
        <translation>Tá%s socraithe an-ard! D’fhéadfaí táillí chomh mór seo a íoc ar idirbheart amháin.</translation>
    
ERR
There is a whitespace formatting issue: there is no space after "Tá" and before "%s" in the translation. It should be "Tá %s socraithe an-ard! D’fhéadfaí táillí chomh mór seo a íoc ar idirbheart amháin."

Correct translation:
Tá %s socraithe an-ard! D’fhéadfaí táillí chomh mór seo a íoc ar idirbheart amháin.
```

<!-- cache_translation_check_ga_5924edcedd92428825a8e007d8943c6916c543ba74b2dc97ee0f0d6b42c6ae46 -->
```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>Theip ar bhaint an tsainstáit seat seat (%s). Bain de láimh é roimh atosú.</translation>
    
ERR
There are issues in both meaning and word usage. The phrase "tsainstáit seat seat" is incorrect and nonsensical in Irish. "Snapshot chainstate dir" should be translated more clearly as "comhadlann chainstate na seatphictiúir" or similar.

Correct translation:
Níor éirigh le bainte comhadlann chainstate na seatphictiúir (%s). Bain de láimh é sula ndéanfaidh tú atosú.
```

<!-- cache_translation_check_ga_665f8fe080011eedd009b207293ab42b35a0d01207df08330201b791f75eaed2 -->
```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>Méid neamhbhailí le haghaidh %s=1: '%s' (ní mór an táille sealaíochta nóiméad de %s a bheith ann ar a laghad chun idirbhearta bhfostú a chosc)</translation>
    
ERR
There are several issues with the translation:
1. The string "%s=&lt;amount&gt;" in the source should be preserved as-is, but in the translation it is replaced with "%s=1", which is incorrect and loses the meaning.
2. The term "minrelay fee" is translated as "táille sealaíochta nóiméad" which is not accurate; it should be "táille íosta athsheachadta" or similar.
3. "idirbhearta bhfostú" is not a correct rendering of "stuck transactions"; a better translation would be "idirbhearta greamaithe" or "idirbhearta blocáilte".

Correct translation:
Méid neamhbhailí do %s=&lt;amount&gt;: '%s' (caithfidh sé a bheith ar a laghad ar chomhionann leis an táille íosta athsheachadta de %s chun idirbhearta greamaithe a chosc)
```

<!-- cache_translation_check_ga_b81bf190e2c953b057a8009302249823c6d2b560166be8879dcaeab06cc90140 -->
```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>Naisc amach teoranta do Tor (-onlynet=onion) ach ní thugtar an seachfhreastalaí chun líonra Tor a bhaint amach: ní thugtar aon seachfhreastalaí, -oinniún nó -listenonion</translation>
    
ERR
The translation contains some inaccuracies:
- "no proxy, -onion or -listenonion" should carry the correct parameter names. "-onion" is rendered as "-oinniún", which is not standard and could confuse users. Parameters should not be translated.
- The word "none of -proxy, -onion or -listenonion is given" is translated as "ní thugtar aon seachfhreastalaí, -oinniún nó -listenonion", but it implies a list of parameters where "proxy" is interpreted as the word rather than the flag "-proxy".

Correct translation:
Naisc amach teoranta do Tor (-onlynet=onion) ach níl an seachfhreastalaí chun líonra Tor a bhaint amach curtha ar fáil: níl ceann ar bith de -proxy, -onion ná -listenonion tugtha

This keeps the parameter names as-is and accurately mirrors the source structure.
```

<!-- cache_translation_check_ga_6fdf9eab64bfc36fa51df2e14ae0b33bf6503ddb6d9c8c6c5cdf6522d793e8b5 -->
```
        <source>UTXO snapshot failed to validate. Restart to resume normal initial block download, or try loading a different snapshot.</source>
        <translation>Theip ar bhailíochtú a dhéanamh ar achomair UTXO. Atosaigh chun gnáthíoslódáil na mbloc tosaigh a atosú, nó bain triail as pictiúr eile a lódáil.</translation>
    
ERR
The translation is mostly accurate, but the phrase "bain triail as pictiúr eile a lódáil" is problematic. "Pictiúr" usually means "picture" or "image," not "snapshot" in the technical/Bitcoin context. The correct term in Irish for a technical "snapshot" would be "achomair", as used previously in the translation.

Correct translation:
Theip ar bhailíochtú a dhéanamh ar achomair UTXO. Atosaigh chun gnáth-íoslódáil na mbloc tosaigh a atosú, nó bain triail as achomair eile a lódáil.
```

<!-- cache_translation_check_ga_c3a386be63db3545343062348302b0ef103636d3880715ea6821b097382ad48a -->
```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>Méid neamhbhailí le haghaidh %s=1: '%s' (ar a laghad %s)</translation>
    
ERR
The translation has two issues:
1. The format specifier %s=&lt;amount&gt; is replaced by %s=1 in the translation. The "1" should be "&lt;amount&gt;" (or an Irish equivalent like "<méid>") to preserve the original placeholder meaning.
2. The rest of the translation is mostly accurate, but the placeholder must be maintained as a variable.

Correct translation:
Méid neamhbhailí le haghaidh %s=&lt;méid&gt;: '%s' (caithfidh sé a bheith ar a laghad %s)
```

<!-- cache_translation_check_ga_43ec6c34685263727061ab78e2ede20e6559b25c31d0580924e8fcab5368f998 -->
```
        <source>Listening for incoming connections failed (listen returned error %s)</source>
        <translation>Theip ar éisteacht le naisc isteach (éisteacht ar ais earráid %s)</translation>
    
ERR
The translation is inaccurate and contains awkward phrasing. "éisteacht ar ais earráid %s" is an incorrect calque and doesn't convey the technical sense in Irish. The verb "theip" is correctly used, but the rest needs to be clearer.

Correct translation:
Theip ar éisteacht le haghaidh naisc isteach (d’fhill éisteacht an earráid %s)
```

<!-- cache_translation_check_ga_474aa382a1b9f9a4249142916017e7cdc9bf75b76f28d9d960ca85f4732591e4 -->
```
        <source>Unknown change type '%s'</source>
        <translation>Anaithnid cineál sóinseáil '%s'</translation>
    
ERR
The translation contains an error with the placement and choice of words. "cineál sóinseáil" is not idiomatic or standard for "change type" in Bitcoin context. "Soinseáil" (for "change") is rarely used, and the adjective order is awkward. Also, the word order is off; in Irish, "cineál" (type) should be followed directly by the qualifier, without an attempted noun-adjective compound.

Correct translation:
Cineál athraithe anaithnid '%s'

Explanation: "athraithe" is a more accurate translation of "change" in this context, especially for Bitcoin transactions. The phrase should be "Cineál athraithe anaithnid" for "Unknown change type".
```

<!-- cache_translation_check_ga_a6a3f9ec960fda9d62350b2b039dd41dff2bbbfdb3943cc5f7189c83b4fcd7bf -->
```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>Rialacha nua anaithnid curtha i ngníomh (leagan giotán %ii)</translation>
    
ERR
There are two issues:
1. The format specifier is incorrect: "versionbit %i" should retain "%i" as is in the translation, but in the Irish, it is rendered as "%ii", which is erroneous.
2. Minor language nuance: "leagan giotán" could be phrased better as "giotán leagain" or, more idiomatically, "bit leagain".

Correct translation:
Rialacha nua anaithnid curtha i ngníomh (giotán leagain %i)
```

<!-- cache_translation_check_ga_ed049d22066759881de7aa7b781c9f13ff89030f98fe8368e67c751806345e12 -->
```
        <source>Unrecognised option "%s" provided in -test=&lt;option&gt;.</source>
        <translation>Rogha neamhaitheanta "%s" curtha ar fáil i -test=1.</translation>
    
ERR
The translation inaccurately translates "-test=&lt;option&gt;" as "-test=1". The "%s" placeholder is also taken over correctly, but using "=1" is incorrect—it should reflect the placeholder "<option>" (more generally, an option value, not the digit 1).

Correct translation:
Rogha neamhaitheanta "%s" curtha ar fáil i -test=&lt;option&gt;.
Or, even more clearly in natural Irish: 
Rogha neamhaitheanta "%s" curtha ar fáil i -test=&lt;rogha&gt;.
```

<!-- cache_translation_check_ga_afcb7dfe4ed7569b2d949652843094743dba5cd903f974894dcc322fac91002b -->
```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Earráid: Níorbh fhéidir watch amháin tx %s a chur le sparán faire amháin</translation>
    
ERR
The translation is mostly correct, but the term "watchonly" is inconsistently rendered: it appears untranslated ("watch amháin") and also as a hybrid translation ("sparán faire amháin"). Consistency is important, and "sparán faire" is the usual term for "watchonly wallet" in Irish Bitcoin translation contexts. Also, "tx" could be better as "idirbheart" (transaction). 

Correct translation:
Earráid: Níorbh fhéidir idirbheart faire amháin %s a chur le sparán faire amháin
```
</details>

Number of issues: 59.
