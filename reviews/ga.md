# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ga</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bga%5D%20low%20quality)


```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
YES
The translation contains errors in word choice and spelling. The correct term for "comma separated file" in Irish ('ga') should be "Comhad camógdeighilte" or "Comhad Camógdeighilte" (depending on capitalization conventions), meaning "comma-separated file." The provided translation "Comhad athróige camógdheighilte" is incorrect and nonsensical— "athróige" means "of variable" or "variable," which is unnecessary here, and "camógdheighilte" is misspelled (should be "camógdeighilte").

Correct translation:
Comhad camógdeighilte
```

```
        <source>Exporting Failed</source>
        <translation>Theip ar Easpórtáil</translation>
    
YES  
The translation has word order and preposition issues. The word "Theip" (failure) should follow the verb "Theip ar" correctly, but "Easpórtáil" (export) should take the proper verbal noun or verbal construction.

A better translation would be:  
"Theip ar an easpórtáil"  
(or simply "Theip ar easpórtáil" without "an", depending on context, but the definite article is common here)  

So the corrected translation is:  
Theip ar an easpórtáil
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Iontráil an pasfhrása nua don sparán. &lt;br/&gt;Le do thoil úsáid pasfhocail de &lt;b&gt;dheich gcarachtar randamacha nó níos mó&lt;/b&gt;, nó &lt;/b&gt;ocht bhfocal nó níos mó&lt;/b&gt;.</translation>
    
YES  
The translation contains an erroneous closing tag sequence and incorrect wording:  
- The phrase "pasfhocail" (plural of "password") should be "pasfhrása" (passphrase) to match the source.  
- There is an incorrect closing tag sequence: "&lt;/b&gt;ocht bhfocal nó níos mó&lt;/b&gt;" contains a stray closing tag at the beginning and mismatched tags.  
- Also, "deich gcarachtar randamacha nó níos mó" is awkward; "deich gcarachtar randamacha nó níos mó" is literal but "randamacha" is an Anglicism; "randamach" or "randamacha" is sometimes used, but "randamach" is preferable.  
- A more natural and correct correction would be:  

Correct translation:  
Iontráil an pasfhrása nua don sparán.&lt;br/&gt;Le do thoil, bain úsáid as pasfhrása de &lt;b&gt;deich gcarachtar randamacha nó níos mó&lt;/b&gt;, nó &lt;b&gt;ocht bhfocal nó níos mó&lt;/b&gt;.
```

```
        <source>Wallet encryption failed</source>
        <translation>Theip ar chriptiú sparán</translation>
    
YES  
The translation has a typographical error: "ar" should be "ar an," and "chriptiú" should be "criptiú." Also, "Theip" means "failure," but the phrase "Theip ar an criptiú sparán" is more idiomatic for "Wallet encryption failed."  

Correct translation:  
Theip ar an criptiú sparán
```

```
        <source>Wallet unlock failed</source>
        <translation>Theip ar dhíghlasáil sparán</translation>
    
YES  
The translation uses Irish Gaelic, but contains errors: "Theip ar dhíghlasáil sparán" is incorrect Irish grammar. "Wallet" translates as "sparán," but the phrase should properly convey that unlocking the wallet failed. A more accurate translation is:  
**"Theip ar dhíghlasáil an sparán"**  
This adds the definite article "an" before "sparán" for grammatical correctness and natural phrasing in Irish.
```

```
        <source>IP/Netmask</source>
        <translation>PI/Mascadhidirlíon</translation>
    
YES  
The translation is incorrect. "IP" should not be translated as "PI" because "IP" is a widely recognized technical abbreviation and generally remains unchanged. "Netmask" is accurately translated as "Mascadh idirlíon" but there is a spacing issue: "Mascadhidirlíon" is combined into one word incorrectly. The correct form should have a space between "Mascadh" and "idirlíon."

Correct translation:  
IP/Mascadh idirlíon
```

```
        <source>%1 d</source>
        <translation>%1 l</translation>
    
YES  
The source "%1 d" likely means "%1 days" with "d" as an abbreviation for days. The translation uses "%1 l", where "l" is not a recognized abbreviation for days in Irish (ga). The correct abbreviation for "day" in Irish is usually "l." for "lá" in singular or "laethanta" plural, but abbreviations are not commonly used in Irish this way.

If the abbreviation "d" is retained for days in the app, it is typical to keep it, or translate to full word if needed. Since the source uses "d" as abbreviation, it should be carried over or translated appropriately.

Correct translation:  
%1 d

(or, if preferred full Irish word)  
%1 lá(s)  

But maintaining format specifier and original abbreviation as is would be best:

%1 d
```

```
        <source>%1 m</source>
        <translation>%1 n</translation>
    
YES  
The English source "%1 m" presumably represents "%1 meters" (where "m" stands for meters). The translation into Irish Gaelic uses "n," which is not the abbreviation for meters in Irish. The abbreviation for "méadar" (meter) in Irish is commonly "m" as in English, or "méadar" can be spelled out. Changing "m" to "n" is incorrect and misleading.

Correct translation:  
%1 m
```

```
        <source>N/A</source>
        <translation>N/B</translation>
    
YES  
The English abbreviation "N/A" (Not Applicable or Not Available) is commonly translated into Irish (ga) as either "N/A" (used as is) or sometimes "Níl infháil" or "Ní feiliúnach." The provided translation "N/B" is unusual and not a recognized equivalent in Irish for "N/A."  

Correct translation:  
N/A
```

```
        <source>Syncing Headers (%1%)…</source>
        <translation>Ceanntásca á Sioncronú (%1 %)…</translation>
    
YES  
There are a few issues in the translation:  
1. The grammar and word order are incorrect in "Ceanntásca á Sioncronú". The noun "headers" should be in plural "Ceanntásca", but "á" is not the correct preposition here to mean "Syncing Headers".  
2. The phrase should translate as "Ag sioncronú ceanntásca" or "Ceanntásca ag sioncronú" to indicate the action of syncing headers.  
3. The format specifier "%1%" in the source is malformed in the translation as "%1 %", adding an unnecessary space before the second percent sign. The percent signs should be together as in the source "(%1%)".  

Correct translation:  
Ag sioncronú ceanntásca (%1%)…
```

```
        <source>Show the list of used sending addresses and labels</source>
        <translation>Taispeáin an liosta de seoltaí seoladh úsáidte agus na lipéid </translation>
    
YES  
There are issues with redundancy and spacing in the translation. The phrase "seoltaí seoladh" is repetitive because both words relate to 'address'; only one should be used to avoid redundancy. Also, there is an unnecessary trailing space at the end.

A better translation would be:  
"Taispeáin an liosta de na seoltaí seolta a úsáidtear agus lipéid"  
(meaning: "Show the list of used sending addresses and labels")
```

```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>Taispeáin an liosta de seoltaí glacadh úsáidte agus lipéid </translation>
    
YES
There is an extra space at the end of the translation that should be removed for proper formatting. Also, the phrase "seoltaí glacadh úsáidte" is a literal translation but awkward in Irish. A better phrasing would be "seoltaí faighte a úsáidtear" or more naturally "an liosta de sheoltaí faighte agus lipéid a úsáidtear."

Correct translation:
Taispeáin an liosta de sheoltaí faighte a úsáidtear agus lipéid
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Lódáil Idirbheart Bitcoin Sínithe go Páirteach ón gearrthaisce</translation>
    
YES  
The translation uses the Irish (ga) word "Lódáil," which is borrowed from English "load" but is not standard or widely accepted in formal Irish. Also, "Idirbheart Bitcoin Sínithe go Páirteach" is a direct but somewhat awkward and overly literal rendering of "Partially Signed Bitcoin Transaction." A more natural and understandable translation would be: 

"Uaslódáil Idirbheart Bitcoin a Sínithe Go Páirteach ón ngearrthaisce" 

or simply:

"Uaslódáil Idirbheart Bitcoin Sínithe Go Páirteach ón ngearrthaisce"  

Note also the use of "gearrthaisce" (clipboard) is correct, and the preposition "ón" causing lenition of "gearrthaisce" is appropriate, as is the capitalisation style consistent with the source.  

Correct translation:  
Uaslódáil Idirbheart Bitcoin Sínithe Go Páirteach ón ngearrthaisce
```

```
        <source>Sending addresses</source>
        <translation>Seoltaí seoladh</translation>
    
YES  
The translation "Seoltaí seoladh" is semantically redundant and incorrect. "Seoltaí" means "sent" or "addresses" (plural of "seoladh" in some contexts), and "seoladh" means "address." Together, "Seoltaí seoladh" is nonsensical, effectively meaning "Sent addresses address" or just an awkward repetition.

The English phrase "Sending addresses" likely means "Addresses being sent" or "Sending of addresses," so the correct Irish translation should be a gerund or verbal noun phrase indicating the action of sending addresses.

A correct translation would be:  
"Ag seoladh seoltaí"  
("Ag seoladh" = "sending," "seoltaí" = "addresses")

Hence:  
<translation>Ag seoladh seoltaí</translation>
```

```
        <source>%1 client</source>
        <translation>%1 cliaint</translation>
    
YES
The translation contains a typo in the word "cliaint"; the correct Irish (ga) word for "client" is "cliant."

Correct translation:
%1 cliant
```

```
        <source>Show</source>
        <translation>Sconas</translation>
    
YES  
The translation "Sconas" is incorrect in Irish. The English word "Show" in the context of a button or command is typically translated as "Taispeáin".  

Correct translation:  
Taispeáin
```

```
        <source>Error creating wallet</source>
        <translation>Earráid agus sparán á chruthú</translation>
    
YES  
The translation "Earráid agus sparán á chruthú" literally means "Error and wallet being created," which does not accurately reflect the intended meaning of "Error creating wallet." The source implies that an error occurred during the creation of the wallet, not a conjunction of an error plus wallet creation.

Correct translation:  
"Earráid ag cruthú sparán"  
(This means "Error creating wallet," properly expressing that the error occurred while creating the wallet.)
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Sparán &lt;b&gt;criptithe&lt;/b&gt;agus &lt;b&gt;díghlasáilte&lt;/b&gt;faoi láthair</translation>
    
YES  
There are spacing issues in the Irish translation: no spaces around "agus" and before "faoi láthair." Also, the Irish word for "encrypted" should be "criptithe," not "criptithe" without spaces.

Correct translation:  
Sparán &lt;b&gt;criptithe&lt;/b&gt; agus &lt;b&gt;díghlasáilte&lt;/b&gt; faoi láthair
```

```
        <source>Change:</source>
        <translation>Sóinseáil:</translation>
    
YES  
The translation "Sóinseáil:" is incorrect for the term "Change:" in the context of Bitcoin transactions. The Irish word "Sóinseáil" does not correspond to "Change" and may cause confusion.

A more appropriate translation for "Change:" (referring to the change amount in a Bitcoin transaction) in Irish would be:

"Athrú:"
```

```
        <source>Received with address</source>
        <translation>Seoladh faighte le</translation>
    
YES  
The provided translation "Seoladh faighte le" is actually in Irish Gaelic (language code 'ga'), but it contains errors and awkward phrasing. "Seoladh" means "address," "faighte" means "received," and "le" means "with." However, the phrase "Seoladh faighte le" translates literally as "address received with," which is not the correct construction.

In Bitcoin context, "Received with address" means funds have been received using a particular Bitcoin address, so the phrase should reflect "Received at address" or "Received via address," correctly showing the association.

A more idiomatic and correct Irish translation would be:  
"Faighte ag an seoladh"  
which means "Received at the address," or alternatively:  
"Faighte le seoladh" (Received with address), which is acceptable, but the article "an" (the) is important here for clarity.

Thus, the correct translation should be:  
"Faighte le seoladh"

Additionally, the original translation reverses the usual word order and omits the article and preposition placement is awkward.

Correct translation:  
<translation>Faighte le seoladh</translation>
```

```
        <source>Copy transaction ID and output index</source>
        <translation>Cóipeáil idirbheart  ID agus innéacs aschuir</translation>
    
YES  
The translation contains a spacing issue before "ID" ("idirbheart  ID" has two spaces instead of one) and the word "Cóipeáil" uses an accented 'ó', which is not standard in Irish for this word ("Cóip" means "copy" and the verb form should be "Cóipeáil" without accent on 'o' ? Actually, "Cóip" has an accent on the 'o', but the infinitive verb "Cóipeáil" is correct). So accented 'ó' is correct.

However, the phrase "output index" is translated as "innéacs aschuir", which is accurate ("innéacs" = index, "aschur" = output, genitive "aschuir"). The phrase "Copy transaction ID and output index" is correctly conveyed in meaning.

Correct spacing is needed. Also, the spacing after "idirbheart" and before "ID" should be a single space.

Corrected translation:  
Cóipeáil ID idirbheart agus innéacs aschuir
```

```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
YES  
The translation "Cóipeáíl sóinseáil" contains spelling errors and incorrect word forms. "Copy" should be translated as "Cóip" or "Cóipeáil" (meaning "to copy"), but the correct gerund or verbal noun form is "Cóipeáil." The word "change" in the Bitcoin context refers to the leftover amount and should be translated as "sóinseáil" or "sóinseáil" if it were correct, but the correct Irish word for "change" (money returned) is "sóinseáil" is not recognized—more standard would be "sóinseáil" is a misspelling.

However, the proper Irish word for "change" (in monetary sense) is "athrú" or "céatadán" (percentage), but in Bitcoin context "change" is usually translated as "soinseáil" or "athrú." The commonly used Bitcoin context term in Irish could be "athrú" (meaning "change").

Given the intended meaning is "Copy change," the correct translation would be:

Correct translation:  
Cóipeáil an t-athrú

Alternatively, if "change" is used as a noun, it may be acceptable as "an t-athrú," or simply "athrú" depending on the context.

Therefore:

Correct translation:  
Cóipeáil an t-athrú
```

```
        <source>change from %1 (%2)</source>
        <translation>sóinseáil ó %1 (%2)</translation>
    
YES  
The Irish translation "sóinseáil ó %1 (%2)" is incorrect and does not convey the meaning of "change" in the context of a Bitcoin transaction (i.e., the change amount returned). "Sóinseáil" is not the correct term here.

A more accurate translation for "change" in this context is "airgead athshlánaithe" or simply "athrú" depending on usage, but in Bitcoin contexts "athrú" (meaning "change") is commonly used.

Correct translation:  
athrú ó %1 (%2)
```

```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>An bhfuil tú cinnte gur mian leat an sparán &lt;i&gt;%1 &lt;/i&gt;?</translation>
    
YES  
There is unnecessary whitespace inside the italic tags in the translation ("%1 &lt;/i&gt;"). The space after %1 before the closing tag should be removed to match the source format.  

Correct translation:  
An bhfuil tú cinnte gur mian leat an sparán &lt;i&gt;%1&lt;/i&gt;?
```

```
        <source>Opening Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the open wallet progress window which indicates to the user which wallet is currently being opened.</extracomment>
        <translation>Sparán Oscailte&lt;b&gt;%1&lt;/b&gt;…</translation>
    
YES
The translation "Sparán Oscailte&lt;b&gt;%1&lt;/b&gt;…" literally means "Open Wallet&lt;b&gt;%1&lt;/b&gt;…", which reads more like a title or label rather than a descriptive sentence indicating that the wallet is currently being opened. The English source "Opening Wallet <b>%1</b>…" uses the present continuous tense, implying an ongoing action.

A more accurate and natural Irish (ga) translation that conveys the ongoing action would be:
"Sparán á oscailt&lt;b&gt;%1&lt;/b&gt;…"

This translates to "Wallet opening <b>%1</b>…" or "Opening wallet <b>%1</b>…", which better matches the intent of the source text.
```

```
        <source>Restore wallet message</source>
        <extracomment>Title of message box which is displayed when the wallet is successfully restored.</extracomment>
        <translation>Athchóirigh teachtaireacht sparán</translation>
    
YES  
The phrase "Athchóirigh teachtaireacht sparán" translates back as "Restore message wallet," which is grammatically incorrect in Irish (ga). The verb "Athchóirigh" ("Restore") should not directly modify "teachtaireacht" ("message") in this way. The original English phrase "Restore wallet message" means a message regarding wallet restoration, so a better translation would be a phrase meaning "Message about wallet restoration" or "Wallet restoration message."

Correct translation:  
"Teachtaireacht athchóirithe sparán"  
(meaning "Message of wallet restoration")
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>An seoladh chomhcheangailte leis an iontráil liosta seoltaí seo. Ní féidir é seo a mionathraithe ach do seoltaí seoladh.</translation>
    
YES  
The word "mionathraithe" is not correct in Irish; the proper form would be "athrú" (change/modify) with the correct construction. Also, "seoltaí seoladh" is redundant and awkward; "seoltaí" alone suffices for "sending addresses." The translation should properly convey that the address can only be modified for sending addresses.

Correct translation:  
An seoladh a bhaineann leis an iontráil liosta seoltaí seo. Ní féidir é seo a athrú ach do sheoltaí a sheoladh.
```

```
        <source>New sending address</source>
        <translation>Seoladh nua seoladh</translation>
    
YES  
The translation "Seoladh nua seoladh" is redundant and incorrect. The phrase "New sending address" should be translated in Irish as "Seoladh nua seolta" or "Seoladh nua le haghaidh seolta". The word "seoladh" means "address" and "seolta" is the verbal adjective form relating to sending.

Correct translation:  
Seoladh nua seolta
```

```
        <source>Edit sending address</source>
        <translation>Eagarthóireacht seoladh seoladh</translation>
    
YES  
The translation literally means "Editing sending address," but it is awkward and redundant because "seoladh seoladh" repeats "address" twice. The correct phrase for "Edit sending address" in Irish should be concise and clear.

Correct translation:  
Eagair an seoladh seoltaí
```

```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Stórálfar thart ar %1 GB de shonraí sa comhadlann seo.</translation>
    
YES  
The translation is problematic because it is in Irish Gaelic (ga) but contains inaccurate wording and a spelling mistake ("Stórálfar" is misspelled as "Stórálfar" but with an extra character "Stórálfar" should be spelled "Stórálfar"). The phrase "sa comhadlann seo" ("in this directory") is correct. However, the verb form should be "Stórálfar" (future passive of "store") rather than "Stórálfar thart ar".

Moreover, the phrase "thart ar" means "about/approximately" and is correctly positioned after "Stórálfar." So the correct translation should be:

Stórálfar thart ar %1 GB de shonraí sa comhadlann seo. 

Since spelling error was due to a typo in the prompt, assuming it was a scanning error. If the prompt is exactly as is, correct as follows:

Correct translation:  
Stórálfar thart ar %1 GB de shonraí sa comhadlann seo.
```

```
        <source>Last block time</source>
        <translation>Am bloc deireanach</translation>
    
YES  
The translation "Am bloc deireanach" is incorrect in Irish (language code 'ga'). The word "Am" (meaning "time") is in Irish, but "bloc" is borrowed from English and not properly inflected or adapted. The correct Irish term for "block" (in the Bitcoin context) would generally remain "bloc" as a technical term, but the adjective "deireanach" should come before the noun.

Furthermore, in Irish, the usual word order is noun + adjective, so "Last block time" would be correctly translated as "Am an bhloc deireanach". Here, "bhloc" is the lenited form of "bloc" because of the definite article "an".

Correct translation:  
Am an bhloc deireanach
```

```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>Tá %1 ag sioncronú faoi láthair. Déanfaidh sé é a íoslódáil agus a fíorú ar ceanntásca agus bloic ó phiaraí go dtí barr an blocshlabhra.</translation>
    
YES  
The translation has an issue with format specifiers and slight grammatical/contextual inaccuracies:

1. The original English text has a double space after the period: "syncing.  It will download"
   - This should be preserved as a single space in the translation, no double space.
2. The phrase "It will download headers and blocks from peers and validate them until reaching the tip of the block chain." translates important technical terms and the logic incorrectly:
   - "Déanfaidh sé é a íoslódáil agus a fíorú ar ceanntásca agus bloic ó phiaraí" misplaces "é" (it) and "a" (to) before "íoslódáil" and "fíorú".  
   - There should be clear reference that "headers and blocks" are downloaded and validated.
   - The phrase "go dtí barr an blocshlabhra" is good for "until reaching the tip of the block chain".

A better translation preserving format and clarity would be:

%1 tá ag sioncronú faoi láthair. Íosóidh sé ceanntásca agus bloic ó phiaraí agus déanfaidh sé iad a fhíorú go dtí an barr is déanaí den blocshlabhra.

Correct translation:

<translation>%1 tá ag sioncronú faoi láthair. Íosóidh sé ceanntásca agus bloic ó phiaraí agus déanfaidh sé iad a fhíorú go dtí an barr is déanaí den blocshlabhra.</translation>
```

```
        <source>Unknown. Syncing Headers (%1, %2%)…</source>
        <translation>Anaithnid. Ceanntásca á Sioncronú (%1, %2 %)…</translation>
    
YES  
The translation has an extra space before the percent sign (%) in "%2 %". In the source, the percent sign is immediately after the number (%2%), so it should be the same in the translation without any space.  

Correct translation:  
Anaithnid. Ceanntásca á Sioncronú (%1, %2%)…
```

```
        <source>Spend unconfirmed change</source>
        <translation>Caith sóinseáil neamhdheimhnithe</translation>
    
YES  
The translation has two issues:  
1. The word "sóinseáil" does not correctly convey "change" in the Bitcoin transaction context. The appropriate term for "change" (as in leftover money returned in a transaction) in Irish related to finance would be "athrú" or "sóinseáil" is uncommon and may be considered incorrect here.  
2. The phrase "unconfirmed change" should reflect "athrú néamhdheimhnithe" where "néamhdheimhnithe" means "unconfirmed".  

Correct translation:  
Caith athrú néamhdheimhnithe
```

```
        <source>OK</source>
        <translation>Togha</translation>
    
YES  
The Irish (ga) word "Togha" means "choice" or "option," which is not an appropriate translation of the English "OK," a confirmation or acceptance term. The correct Irish translation for "OK" (as an acknowledgment or acceptance) is "Ceart go leor" or simply "OK" as used commonly.  

Correct translation:  
<translation>Ceart go leor</translation>
```

```
        <source>none</source>
        <translation>ceann ar bith</translation>
    
YES  
The provided translation "ceann ar bith" means "any head" or "any one" in Irish, which is incorrect for the English word "none." The correct Irish translation for "none" in this context is "níl" or "duda," depending on the precise usage, but most commonly simply "níl" or "ní hea." However, for simply "none," the best single-word translation is "níl."

Correct translation:  
<translation>níl</translation>
```

```
        <source>This change would require a client restart.</source>
        <translation>Theastódh cliant a atosú leis an athrú seo.</translation>
    
YES  
The translation contains a spacing issue: there is no space between "Theastódh" and "cliant". It should be "Theastódh cliant a atosú leis an athrú seo." with a space after "Theastódh".  

Correct translation:  
Theastódh cliant a atosú leis an athrú seo.
```

```
        <source>Failed to load transaction: %1</source>
        <translation>Theip ar lódáil idirbheart: %1</translation>
    
YES  
The translation contains English words ("ar lódáil") instead of the correct Irish (ga) equivalents. Also, "Theip ar" is not idiomatic; a better phrase for "Failed to load transaction" in Irish would be "Theip ar an idirbheart a luchtú: %1" or "Theip orm an idirbheart a luchtú: %1".

Correct translation:  
Theip orm an idirbheart a luchtú: %1
```

```
        <source>Transaction broadcast failed: %1</source>
        <translation>Theip ar chraoladh idirbhirt: %1</translation>
    
YES
The translation contains a typographical error: "ar" should be "ar an" to correctly express "Transaction broadcast failed" in Irish. The phrase "Theip ar an chraoladh idirbhirt: %1" is the proper translation, where "Theip ar an" means "failed to" and "chraoladh idirbhirt" means "transaction broadcast."

Correct translation:
Theip ar an chraoladh idirbhirt: %1
```

```
        <source>PSBT copied to clipboard.</source>
        <translation>Cóipeáladh IBSP chuig an gearrthaisce.</translation>
    
YES  
The abbreviation "PSBT" (Partially Signed Bitcoin Transaction) should be retained as-is in the translation to avoid confusion. Translating it as "IBSP" is incorrect and misleading.  

Correct translation:  
Cóipeáladh PSBT chuig an gearrthaisce.
```

```
        <source>N/A</source>
        <translation>N/B</translation>
    
YES  
The English abbreviation "N/A" (Not Applicable or Not Available) is commonly translated into Irish (ga) as either "N/A" (used as is) or sometimes "Níl infháil" or "Ní feiliúnach." The provided translation "N/B" is unusual and not a recognized equivalent in Irish for "N/A."  

Correct translation:  
N/A
```

```
        <source>Blocksdir</source>
        <translation>Eolbloic</translation>
    
YES  
The translation "Eolbloic" is incorrect and does not reflect the meaning of "Blocksdir." The term "Blocksdir" likely refers to a directory (folder) for blocks, especially in a technical/Bitcoin context. A more accurate translation in Irish (ga) would be a direct transliteration or a compound word reflecting "directory" (e.g., "MótaBloc" or "EolaireBloc"). Since "dir" is short for directory, the better approach is to use "Eolaire Bloc" or "Eolaire Blocanna" (directory of blocks).  
Correct translation:  
Eolaire Blocanna
```

```
        <source>Elapsed time since a novel block passing initial validity checks was received from this peer.</source>
        <translation>Tá achar ama caite ó fuarthas bloc úrscéil a rinne na seiceálacha bailíochta tosaigh ón gcomhghleacaí seo.</translation>
    
YES  
The Irish (ga) translation contains errors and awkward phrasing:

- "Tá achar ama caite" is incorrect and unnatural; "achar" typically means "distance," not elapsed time.
- The phrase structure is awkward and does not accurately convey "Elapsed time since..."
- The source describes time elapsed since receiving a novel block that passed initial validity checks, but the translation is unclear and grammatically incorrect.
- Also, the phrase "a rinne na seiceálacha bailíochta tosaigh" ("that performed the initial validity checks") incorrectly implies the block performed the checks, whereas actually the block passed those checks.

A better translation would be:

"Am atá caite ó fuarthas bloc úrscéil a d’fhág na seiceálacha bailíochta tosaigh slána ón gcomhghleacaí seo."

This translates to:

"Elapsed time since a novel block that passed the initial validity checks was received from this peer."

Note the correct use of "Am atá caite" for "Elapsed time" and "a d’fhág na seiceálacha bailíochta tosaigh slána" ("that left the initial validity checks intact") to express passing checks properly.
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>Chuaigh an t-am caite ó fuarthas idirbheart úrnua a glacadh isteach inár mempool ón bpiaraí seo.</translation>
    
YES  
The translation contains a mix of English ("mempool", "peer") and Irish (ga) words, which may be acceptable for technical terms but the phrasing and grammar are awkward and not idiomatic Irish. The word "idirbheart úrnua" is incorrect; the correct phrase for "novel transaction" should be "idirbheart nua" (novel/new transaction). Also, the verb tense and word order in the sentence are not natural in Irish.

A clearer translation would be:

"Am a caitheadh ó fuarthas idirbheart nua a cuireadh isteach inár mempool ón bpiaraí seo."

This translates roughly as: "Elapsed time since a new transaction was received from this peer and added into our mempool."

If you want to keep "mempool" and "bpiaraí" as technical terms, they can remain, but ensure the sentence is idiomatic Irish.

Correct translation:  
"Am a caitheadh ó fuarthas idirbheart nua a cuireadh isteach inár mempool ón bpiaraí seo."
```

```
        <source>Last block time</source>
        <translation>Am bloc deireanach</translation>
    
YES  
The translation "Am bloc deireanach" is incorrect in Irish (language code 'ga'). The word "Am" (meaning "time") is in Irish, but "bloc" is borrowed from English and not properly inflected or adapted. The correct Irish term for "block" (in the Bitcoin context) would generally remain "bloc" as a technical term, but the adjective "deireanach" should come before the noun.

Furthermore, in Irish, the usual word order is noun + adjective, so "Last block time" would be correctly translated as "Am an bhloc deireanach". Here, "bhloc" is the lenited form of "bloc" because of the definite article "an".

Correct translation:  
Am an bhloc deireanach
```

```
        <source>detecting: peer could be v1 or v2</source>
        <extracomment>Explanatory text for "detecting" transport type.</extracomment>
        <translation>bhrath: d’fhéadfadh v1 nó v2 a bheith i gcomhghleacaí</translation>
    
YES  
The Irish translation has a typo at the start. The English "detecting:" should be translated as "ag braith:" rather than "bhrath:". The vowel initial word should start with a vowel for proper grammatical form with the preceding preposition "ag". Also, the rest of the phrase is mostly acceptable, but "peer" is correctly translated as "comhghleacaí" (which means peer or opponent), appropriate here. The format specifiers are not present, so no issue there.

Correct translation:  
ag braith: d’fhéadfadh v1 nó v2 a bheith i gcomhghleacaí
```

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
    
YES
The translated text has an unnecessary space after the placeholder %7 before "RABHADH:". According to the source, %7 and %8 are style tags and should not be space-separated from the surrounding text. Also, in the English source, "WARNING" is uppercase and the Irish translation uses "RABHADH" which is fine, but there should be no leading space after %7.

Correct translation:
Fáilte go consól RPC %1.
Úsáid saigheada suas agus síos chun an stair a nascleanúint, agus %2 chun an scáileán a ghlanadh.
Úsáid %3 agus %4 chun an clómhéid a mhéadú nó a laghdú.
Clóscríobh %5 le haghaidh forbhreathnú ar na horduithe atá ar fáil.
Chun tuilleadh eolais a fháil faoin gconsól seo a úsáid, clóscríobh %6.

%7RABHADH: Bhí scamadóirí gníomhach, ag rá le húsáideoirí orduithe a chlóscríobh anseo, ag goid a n-inneachar sparán. Ná húsáid an consól seo gan iarmhairtí ordaithe a thuiscint go hiomlán.%8
```

```
        <source>Copy message</source>
        <translation>Cóipeáil  teachtaireacht</translation>
    
YES  
There is an extra space between "Cóipeáil" and "teachtaireacht". The correct translation should be one word with no space.

Correct translation:  
Cóipeáilteachtaireacht
```

```
        <source>Base58 (P2SH-SegWit)</source>
        <translation>Base58 (P2SH- SegWit)</translation>
    
YES
There is an unnecessary space after the hyphen in "P2SH- SegWit". The source has "P2SH-SegWit" without any spaces.

Correct translation:
Base58 (P2SH-SegWit)
```

```
        <source>Change:</source>
        <translation>Sóinseáil:</translation>
    
YES  
The translation "Sóinseáil:" is incorrect for the term "Change:" in the context of Bitcoin transactions. The Irish word "Sóinseáil" does not correspond to "Change" and may cause confusion.

A more appropriate translation for "Change:" (referring to the change amount in a Bitcoin transaction) in Irish would be:

"Athrú:"
```

```
        <source>Custom change address</source>
        <translation>Seoladh sóinseáil saincheaptha</translation>
    
YES  
The translation "Seoladh sóinseáil saincheaptha" is problematic. The word "sóinseáil" seems to be a mistranslation or a nonsensical term in Irish (ga) for "change" in the Bitcoin context. The correct term for "change" in the context of money or transactions is generally "athrú". "Seoladh" correctly means "address," and "saincheaptha" means "custom."

Correct translation:  
Seoladh athraithe saincheaptha
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Má úsáidtear an táilletacachumas is féidir idirbheart a sheoladh a thógfaidh roinnt uaireanta nó laethanta (nó riamh) dearbhú. Smaoinigh ar do tháille a roghnú de láimh nó fan go mbeidh an slabhra iomlán bailíochtaithe agat.</translation>
    
YES
The translation contains several errors and awkward phrases in Irish that affect clarity and accuracy. For example:
- "Má úsáidtear an táilletacachumas" is not correct Irish for "Using the fallbackfee." "Táilletacachumas" is a nonsensical compound and does not translate "fallbackfee."
- "idirbheart" is correct for "transaction," but "a thógfaidh roinnt uaireanta nó laethanta (nó riamh) dearbhú" is a literal and awkward phrasing for "that will take several hours or days (or never) to confirm."
- The phrase "nó riamh" ("or ever") should be "nó ná riamh" or better expressed as "nó ní riamh," for "or never."
- "Smaoinigh ar do tháille a roghnú de láimh" ("Consider choosing your fee manually") is acceptable but could be more idiomatic.
- The translation omits the concept of "sending a transaction" clearly and the clause structure is awkward.

A better, clearer translation would be:

<Má úsáidtear an táille athshlánaithe (fallbackfee) d'fhéadfadh sé go seolfadh tú idirbheart a thógfaidh roinnt uaireanta nó laethanta (nó nach bhfíorófar riamh) chun a dhearbhú. Smaoinigh ar do tháille a roghnú de láimh nó fan go mbeidh an slabhra iomlán bailíochtaithe agat.>

Or more polished:

<Nuair a úsáidtear an táille athshlánaithe (fallbackfee) d’fhéadfadh idirbheart a sheoladh a thógfaidh roinnt uaireanta, laethanta, nó nach bhfíorófar riamh. Smaoinigh ar do tháille a roghnú de láimh nó fan go mbeidh an slabhra iomlán bailíochtaithe agat.>
```

```
        <source>per kilobyte</source>
        <translation>in aghaidh an cilibheart</translation>
    
YES  
The word "cilibheart" is incorrect in Irish (ga). The correct term for "kilobyte" is "cilibeit" or sometimes "cilibeáit." Also, "in aghaidh an" is correct for "per," so the phrase should be:

Correct translation:  
in aghaidh an chilibheit
```

```
        <source>Recommended:</source>
        <translation>Molta:</translation>
    
YES  
The Irish word for "Recommended:" is "Moltar:" not "Molta:". The given translation misses the final "r".  

Correct translation:  
Moltar:
```

```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
YES  
The translation "Cóipeáíl sóinseáil" contains spelling errors and incorrect word forms. "Copy" should be translated as "Cóip" or "Cóipeáil" (meaning "to copy"), but the correct gerund or verbal noun form is "Cóipeáil." The word "change" in the Bitcoin context refers to the leftover amount and should be translated as "sóinseáil" or "sóinseáil" if it were correct, but the correct Irish word for "change" (money returned) is "sóinseáil" is not recognized—more standard would be "sóinseáil" is a misspelling.

However, the proper Irish word for "change" (in monetary sense) is "athrú" or "céatadán" (percentage), but in Bitcoin context "change" is usually translated as "soinseáil" or "athrú." The commonly used Bitcoin context term in Irish could be "athrú" (meaning "change").

Given the intended meaning is "Copy change," the correct translation would be:

Correct translation:  
Cóipeáil an t-athrú

Alternatively, if "change" is used as a noun, it may be acceptable as "an t-athrú," or simply "athrú" depending on the context.

Therefore:

Correct translation:  
Cóipeáil an t-athrú
```

```
        <source>%1 to '%2'</source>
        <translation>%1 go '%2'</translation>
    
YES
The English preposition "to" is incorrectly translated as "go" in Irish ("ga"). The correct Irish preposition for "to" in this context should be "go" with an acute accent on the "o" (i.e., "go"), but it should not be confused with the English word "go." In Irish, the preposition "go" is correct, but it must be spelled accurately.

Additionally, the translation uses single quotes around '%2', which is acceptable if consistent with style, but typically the source's use of straight single quotes should be preserved exactly, including spacing.

Correct translation:
%1 go '%2'
```

```
        <source>%1 to %2</source>
        <translation>%1 go %2</translation>
    
YES  
The Irish (ga) translation uses "go" instead of "to." While "go" is commonly used in Irish to mean "to" when indicating direction, in the context of a phrase like "%1 to %2," especially for Bitcoin addresses or amounts, the preposition "chuig" or simply "–" (a dash) might be more appropriate depending on context. However, the direct translation of "to" as "go" is generally acceptable in Irish.  

The main issue is spacing: there should be no extra spaces introduced, but here there is a correct single space on either side of "go." This matches the source, which has spaces before and after "to." So spacing is fine.

Given the source is "%1 to %2" (with spaces), the translation "%1 go %2" is acceptable.

However, for clarity and idiomatic usage in financial or transactional contexts, Irish often uses "go" when indicating movement or direction. Since no other errors or format specifier misuse is present, the translation is acceptable.

Therefore, no correction is necessary.

<reply>NO</reply>
```

```
        <source>PSBT saved</source>
        <extracomment>Popup message when a PSBT has been saved to a file</extracomment>
        <translation>IBSP sábháilte</translation>
    
YES  
The abbreviation "PSBT" is incorrectly translated as "IBSP" which is not a standard or recognized translation in Irish (ga). The abbreviation should remain as "PSBT" since it is a technical term (Partially Signed Bitcoin Transaction) and acronyms like this are usually retained as-is in translations. The word "sábháilte" (correct spelling with fada) means "saved" and is appropriate.

Correct translation:  
PSBT sábháilte
```

```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>Níl comhartha chuig Athchuir-Le-Táille, BIP-125</translation>
    
YES  
The Irish translation has an issue with the phrase "Not signalling Replace-By-Fee, BIP-125." The English sentence indicates that something is *not* signalling a feature, i.e., it is not sending a signal for Replace-By-Fee (RBF). The Irish translation "Níl comhartha chuig Athchuir-Le-Táille, BIP-125" literally translates to "There is no signal to Replace-By-Fee, BIP-125," which is somewhat understandable but not idiomatic and uses "chuig," meaning "to" or "towards," which is not appropriate here.

A better translation for "Not signalling Replace-By-Fee, BIP-125." would express "No signal for Replace-By-Fee, BIP-125" or "Not signalling Replace-By-Fee, BIP-125" with correct idiomatic usage.

Correct translation:  
Níl comhartha ann le haghaidh Athchuir-Le-Táille, BIP-125.
```

```
        <source>Warning: Unknown change address</source>
        <translation>Rabhadh: Seoladh sóinseáil anaithnid</translation>
    
YES  
The translation uses the Irish word "sóinseáil" which means "capitalization" or "accentuation," and does not correspond to the term "change" in the Bitcoin context (i.e., the "change address" for transaction outputs). The correct term for "change" in this context should be "athraithe" or "sóinse" (specifically referring to Bitcoin change), but more commonly "seoladh athraithe" would be understood as "change address."

Correct translation:  
Rabhadh: Seoladh athraithe anaithnid
```

```
        <source>Message signing failed.</source>
        <translation>Theip ar shíniú teachtaireachtaí.</translation>
    
YES  
The translation has spelling and grammatical errors. The correct Irish (ga) translation for "Message signing failed." is:  
"Theip ar shíniú na teachtaireachta."
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/neamhdheimhnithe</translation>
    
YES  
The Irish translation is incorrect and contains a typo. The correct Irish word for "unconfirmed" in this context is "neamhdeimhnithe" (meaning "unconfirmed"). The provided translation "neamhdheimhnithe" has an extra "d" misplaced.

Correct translation:  
%1/neamhdeimhnithe
```

```
        <source>Generated</source>
        <translation>Ghinte</translation>
    
YES
The Irish (ga) translation "Ghinte" is correct for "Generated" (past participle of "generate" - "ghin" + suffix). However, the initial consonant should be lenited properly. The verb "gineann" in the past participle form is "ghinte" with a slender 'i' and lenition applied. The correct spelling is "Ghinte" as provided, but depending on context, "Ghinte" is acceptable. However, the given form "Ghinte" looks correct.

On further check, "Ghinte" is the correct past participle form of "generate" in Irish.

Therefore, the translation is accurate, there are no format specifiers involved, and no spelling or spacing issues.

<reply>NO</reply>
```

```
        <source>Copy transaction ID</source>
        <translation>Cóipeáil idirbheart ID</translation>
    
YES  
The Irish translation contains an acute accent on the 'o' in "Cóipeáil" which is incorrect. The correct spelling is "Cóipáil" without the extra 'e'. Also, "idirbheart ID" is redundant because "ID" is an English abbreviation; it would be better to translate "ID" fully or ensure consistent use, but "ID" is commonly used in technical contexts.  

Correct translation:  
Cóipáil ID idirbheart
```

```
        <source>Copy raw transaction</source>
        <translation>Cóipeáil amh-idirbheart</translation>
    
YES  
The translation contains a spelling error: "Cóipeáil" should be "Cóipáil" in Irish (ga). The correct translation is:  
Cóipáil amh-idirbheart
```

```
        <source>Copy full transaction details</source>
        <translation>Cóipeáil idirbheart agus sonraí iomlána</translation>
    
YES
The translation is in Irish (ga), but has a grammatical issue and a slight meaning distortion. "Cóipeáil idirbheart agus sonraí iomlána" translates roughly as "Copy transaction and full details," which is a bit off from "Copy full transaction details." The phrase "full transaction details" should be understood as a whole—copy all the details related to the transaction.

A more correct translation would be:
"Cóipeáil sonraí iomlána an idirbhirt"

This means "Copy the full details of the transaction," preserving the structure and meaning from the source.
```

```
        <source>Increase transaction fee</source>
        <translation>Méadaigh idirbheart  táille</translation>
    
YES  
There is an incorrect extra space between "idirbheart" and "táille" in the translation. Also, "transaction fee" in Irish is correctly translated as "táille idirbheart," with "táille" (fee) preceding "idirbheart" (transaction) as a genitive construction.

Correct translation:  
Méadigh táille idirbheart
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
YES
The translation contains errors in word choice and spelling. The correct term for "comma separated file" in Irish ('ga') should be "Comhad camógdeighilte" or "Comhad Camógdeighilte" (depending on capitalization conventions), meaning "comma-separated file." The provided translation "Comhad athróige camógdheighilte" is incorrect and nonsensical— "athróige" means "of variable" or "variable," which is unnecessary here, and "camógdheighilte" is misspelled (should be "camógdeighilte").

Correct translation:
Comhad camógdeighilte
```

```
        <source>Watch-only</source>
        <translation>Faire-amháin</translation>
    
YES  
The translation "Faire-amháin" is incorrect. In Irish (language code 'ga'), "watch-only" in a Bitcoin context usually means an address or wallet that can be viewed but not spent from. The correct phrase is "Faire amháin" (meaning "view only" or "watch only") without a hyphen and with a space between words. Also, the word "faire" here should be lowercase.

Correct translation:  
Faire amháin
```

```
        <source>Exporting Failed</source>
        <translation>Theip ar Easpórtáil</translation>
    
YES  
The translation has word order and preposition issues. The word "Theip" (failure) should follow the verb "Theip ar" correctly, but "Easpórtáil" (export) should take the proper verbal noun or verbal construction.

A better translation would be:  
"Theip ar an easpórtáil"  
(or simply "Theip ar easpórtáil" without "an", depending on context, but the definite article is common here)  

So the corrected translation is:  
Theip ar an easpórtáil
```

```
        <source>Unable to decode PSBT from clipboard (invalid base64)</source>
        <translation>Ní féidir IBSP a dhíchódú ón ghearrthaisce (Bun64 neamhbhailí)</translation>
    
YES  
The translation contains an incorrect abbreviation "IBSP" instead of "PSBT" and incorrect capitalization/spelling of "base64" as "Bun64". Also, "ní féidir" ("cannot") should be lowercase at the start, and the phrase would be better rendered as a fluent Irish sentence.

Correct translation:  
"Ní féidir PSBT a dhíchódú ón ngearrthaisce (base64 neamhbhailí)"
```

```
        <source>Unable to decode PSBT</source>
        <translation>Ní féidir díchódú IBSP</translation>
    
YES  
The Irish translation contains a non-Irish accent mark on the initial 'N' (Ní should have a fada only on the i, not an accent on the N). Also, the wording is slightly off for technical accuracy: "díchódú IBSP" is understandable but awkward. A better phrase would use the verb form to express "Unable to decode," e.g., "Ní féidir PSBT a díchódú," which literally means "PSBT cannot be decoded."

Correct translation:  
Ní féidir PSBT a díchódú
```

```
        <source>Increasing transaction fee failed</source>
        <translation>Theip ar méadú táille idirbhirt</translation>
    
YES  
The Irish translation contains an error: "méadú" (increase) should be in the verbal noun form with "ag" to indicate the ongoing action "increasing." Also, "ar" (on) is incorrect here; the phrase should start with "Theip ar an..." for "failed on the..." but better idiomatic phrasing is "Theip ar mhéadú táille idirbhirt."

Correct translation:  
Theip ar mhéadú táille idirbheart
```

```
        <source>PSBT copied</source>
        <translation>IBSP cóipeáilte</translation>
    
YES  
The translation incorrectly uses "IBSP" which appears to be a literal or incorrect acronym for PSBT. The correct equivalent in Irish should keep "PSBT" as is or transliterate appropriately, as acronyms typically remain unchanged or are explained. The rest of the phrase "copied" is correctly translated as "cóipeáilte".  

Correct translation:  
PSBT cóipeáilte
```

```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>Cóipeáil PSBT bump táille chuig an ngearrthaisce</translation>
    
YES  
The provided translation includes an unnecessary English loanword "bump" which is not translated or adapted into Irish (ga). The phrase "Fee-bump PSBT" should be fully translated or at least adapted idiomatically. Also, "gearrthaisce" is acceptable for clipboard, but the phrase order and grammar could be improved for natural Irish.

A better translation would be:  
"Cóipeáladh PSBT bump táille chuig an ngearrthaisce" (making clear the past passive action), but better to translate "fee-bump" as "méadú táille" or "ardú táille":

Correct translation:  
"Cóipeáladh PSBT le méadú táille chuig an ngearrthaisce"  

Or:  
"Cóipeáladh PSBT méadaithe táille chuig an ngearrthaisce"  

Explanation:  
- "Cóipeáil" is the verbal noun; the past tense passive "Cóipeáladh" is preferred in such contexts.  
- "Fee-bump" should be translated as "méadú táille" or "méadaithe táille."  
- Retain "PSBT" as is (it is a Bitcoin technical term).  
- "gearrthaisce" is the standard word for clipboard.  

Hence, the existing translation is inaccurate due to untranslated term and suboptimal grammar.
```

```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>Theip ar %s an staid snapshot -assumeutxo a bhailíochtú. Léiríonn sé seo fadhb crua-earraí, nó fabht sna bogearraí, nó droch-mhodhnú bogearraí a cheadaigh pictiúr neamhbhailí a luchtú. Mar thoradh air seo, stopfar an nód agus stopfaidh sé de úsáid a bhaint as staid ar bith a tógadh ar an seat, ag athshocrú airde an tslabhra ó%dgo%d. Ar an gcéad atosú eile, athchromfar ar an nód ag sioncronú ó %d gan úsáid a bhaint as sonraí seat. Tuairiscigh an teagmhas seo do %s lena n-áirítear conas a fuair tú an pictiúr. Fágfar an slabhrashlabhra neamhbhailí ar an diosca ar eagla go mbeadh sé ina chuidiú leis an tsaincheist ba chúis leis an earráid seo a dhiagnóisiú.</translation>
    
YES  
The translation contains several errors and awkward phrasing in Irish ('ga'), including incorrect word forms and missing spaces after punctuation. The phrase "Theip ar %s an staid snapshot -assumeutxo a bhailíochtú." should be "Theip ar %s an staid snapshot -assumeutxo a fhíorú." for better usage of "validate." Words like "seat" are incorrect translations for "snapshot" and confuse meaning; "pictiúr" (literally "picture") is inappropriate here. Also, there is a missing space: "ó%dgo%d" should be "ó %d go %d". The phrase "athchromfar ar an nód ag sioncronú" is awkward and should be "seolfaidh an nód arís ag sioncronú". The phrase "slabhrashlabhra" is redundant and incorrect, "slabhra" suffices. The phrase "gan úsáid a bhaint as sonraí seat" should be "gan úsáid a bhaint as sonraí den snapshot" or better "den slatama snapshot." Finally, overall style should be more formal and clear.

Corrected translation suggestion:

Theip ar %s an staid snapshot -assumeutxo a fhíorú. Tá sé seo ag léiriú fadhb crua-earraí, fabht sa bhogearraí, nó droch-mhodhnú bogearraí a cheadaigh snapshot neamhbhailí a luchtú. Mar thoradh air seo, stopfaidh an nód agus stadfaidh sé de úsáid a bhaint as aon staid a tógadh ón snapshot, ag athshocrú airde an tslabhra ó %d go %d. Beimid ag tosú arís den chéad uair ag sioncronú ón bpointe %d gan úsáid a bhaint as sonraí den snapshot. Cuir in iúl an eachtra seo do %s, lena n-áirítear conas a fuair tú an snapshot. Fágfar an staid slabhra neamhbhailí ar an diosca chun cabhrú leis an bhfadhb a d'fhéadfadh a bheith mar chúis leis an earráid seo a dhiagnóisiú.

Note: Since "snapshot" and "-assumeutxo" are technical terms without direct Irish equivalents, it's acceptable to keep them untranslated or use them as is, but with consistent usage and proper grammar around them.
```

```
        <source>Cannot downgrade wallet from version %i to version %i. Wallet version unchanged.</source>
        <translation>Ní féidir an sparán a íosghrádú ó leagan %igo leagan%i. Leagan sparán gan athrú.</translation>
    
YES  
The translation contains errors: "Ní féidir an sparán a íosghrádú ó leagan %igo leagan%i" is incorrect. The format specifiers are malformed ("%igo" should be "%i go" with space and "go" meaning "to"). Also, "Leagan sparán gan athrú." is acceptable but could be smoother.

Correct translation:  
Ní féidir an sparán a íosghrádú ó leagan %i go leagan %i. Níor athraíodh leagan an sparán.
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>Ní féidir sparán scoilte neamh-HD a uasghrádú ó leagan%igo leagan%i gan uasghrádú chun tacú le heochrach réamh-scoilte. Úsáid leagan %i nó níl aon leagan sonraithe.</translation>
    
YES  
The translation is in Irish (language code 'ga'), which I am familiar with. The main issues are related to spacing around the format specifiers and some awkward phrasing that could lead to confusion:

1. Missing spaces between words and format specifiers `%i` in "leagan%igo leagan%i". This should be spaced correctly as "leagan %i go leagan %i".
2. The phrase "Ní féidir sparán scoilte neamh-HD" would be clearer as "Ní féidir sparán scoilte neamh-HD" but the original "non HD split wallet" might be better translated as "sparán scoilte neamh-HD" (which is correct).
3. The phrase "gan uasghrádú chun tacú le heochrach réamh-scoilte" literally means "without upgrading to support pre-split key". It is quite literal but acceptable.
4. "Úsáid leagan %i nó níl aon leagan sonraithe." is slightly awkward in Irish — better would be "Úsáid leagan %i nó ná sonraigh aon leagan." (Use version %i or do not specify any version.)

Corrected translation:  
Ní féidir sparán scoilte neamh-HD a uasghrádú ó leagan %i go leagan %i gan uasghrádú chun tacú le heochrach réamh-scoilte. Úsáid leagan %i nó ná sonraigh aon leagan.

Also, note the consistent spacing before and after %i placeholders.

Final output:  
YES  
The translation has spacing errors around the format specifiers and slightly awkward phrasing. Correct spacing and more natural phrasing:  
Ní féidir sparán scoilte neamh-HD a uasghrádú ó leagan %i go leagan %i gan uasghrádú chun tacú le heochrach réamh-scoilte. Úsáid leagan %i nó ná sonraigh aon leagan.
```

```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Earráid agus%s á léamh! Seans go bhfuil sonraí idirbhirt in easnamh nó mícheart. Sparán athscanadh.</translation>
    
YES  
The translation does not correspond to the source text. The source states an error about the dumpfile format record being incorrect and specifies the unexpected and expected values ("%s" and "format"). The translation instead says: "Error reading %s! Possibly transaction data missing or incorrect. Wallet rescanning." which introduces concepts not present in the source and omits the original message about the dumpfile format record.

Correct translation:  
Earráid: Tá taifead fhormáidiúil an dumpfile mícheart. Fuair %s, ba mhian "format".
```

```
        <source>The transaction amount is too small to send after the fee has been deducted</source>
        <translation>Tá méid an idirbhirt ró-bheag le seoladh agus an táille asbhainte</translation>
    
YES  
The translation is in Irish ('ga') but contains grammar and phrasing issues, notably the conjunction "agus" ("and") used incorrectly where the English implies a temporal condition ("after the fee has been deducted"). The phrase "an táille asbhainte" is awkward and does not clearly convey "after the fee has been deducted."

Correct translation:  
Tá méid an idirbhirt ró-bheag le seoladh tar éis don táille a bheith bainte amach.
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Is é seo an táille idirbhirt a fhéadfaidh tú cuileáil má tá sóinseáil níos lú ná dusta ag an leibhéal seo</translation>
    
YES  
The translation has incorrect word choices and grammar for Irish (ga). The words "cuileáil" and "sóinseáil" are not correct translations in this context ("discard" and "change" respectively). Also, "dust" should be transliterated or explained as it is a technical term in Bitcoin, often left as "dust" or translated as "deannaigh" (dust/particles). The phrase "idirbhirt" is acceptable for "transaction."

Correct translation:  
Is é seo an táille idirbhirt ar féidir leat a chur ar ceal má tá an t-athrú níos lú ná dusta ag an leibhéal seo
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Leibhéal logála catagóir ar leith nach dtacaítear leis%11$s=%2$s. Bhíothas ag súil le %1$s=1:2. Catagóirí bailí: %3$s. Leibhéil loga bailí: %4$s.</translation>
    
YES  
The translation incorrectly formats and changes the placeholders and example text. Specifically:  
- The placeholder `%1$s` is altered to `%11$s` (an invalid placeholder).  
- The expected format `%1$s=<category>:<loglevel>` is incorrectly translated as `%1$s=1:2.` which hardcodes example digits instead of placeholders.  
- There is a missing space before `%11$s=%2$s` ("leis%11$s=%2$s" should be "leis %1$s=%2$s").  
- The phrase "Bhíothas ag súil le" is the past passive ("was expected"), the original requires present tense ("Expected"), so it should be "Spreagadh" or similar present or neutral form.  
- Overall, placeholders must be preserved exactly, and spacing corrected.

Correct translation:  
Leibhéal logála catagóir ar leith nach dtacaítear leis %1$s=%2$s. Bhíothas ag súil le %1$s=&lt;catagóir&gt;:&lt;leibhéal logála&gt;. Catagóirí bailí: %3$s. Leibhéil logála bailí: %4$s.
```

```
        <source>Cannot resolve -%s address: '%s'</source>
        <translation>Ní féidir réiteach seoladh -%s: '%s'</translation>
    
YES  
The translation uses "Ní féidir réiteach seoladh -%s: '%s'", which is incorrect and unnatural in Irish (ga). The phrase "Cannot resolve" should be translated as "Ní féidir an seoladh -%s a réiteach: '%s'" to maintain the correct word order and grammar. The verb "réiteach" (to resolve) needs the definite article and the correct verbal noun construction here.  

Correct translation:  
Ní féidir an seoladh -%s a réiteach: '%s'
```

```
        <source>%s is set very high! Fees this large could be paid on a single transaction.</source>
        <translation>Tá%s socraithe an-ard! D’fhéadfaí táillí chomh mór seo a íoc ar idirbheart amháin.</translation>
    
YES  
The Irish translation has a formatting issue: there is no space between "Tá" and "%s". In Irish, as in English, the placeholder should be separated by a space. Also, the rest of the sentence is correct and conveys the meaning accurately.  

Correct translation:  
Tá %s socraithe an-ard! D’fhéadfaí táillí chomh mór seo a íoc ar idirbheart amháin.
```

```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>Theip ar bhaint an tsainstáit seat seat (%s). Bain de láimh é roimh atosú.</translation>
    
YES  
The translation contains a repeated word "seat seat" which is erroneous. The correct Irish word for "snapshot" in this context should be "sainstáit" (chainstate), and "seat seat" appears to be a typo or mistranslation.

Correct translation:  
Theip ar bhaint an tsainstáit snaíomhchadán (%s). Bain de láimh é roimh atosú.
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>Méid neamhbhailí le haghaidh %s=1: '%s' (ní mór an táille sealaíochta nóiméad de %s a bheith ann ar a laghad chun idirbhearta bhfostú a chosc)</translation>
    
YES  
The translation incorrectly replaces the placeholder `<amount>` with `1` in `%s=1`, which changes the meaning and breaks the placeholder usage. Additionally, "sealaíochta nóiméad" is an awkward and incorrect phrase for "minrelay fee." A better translation for "minrelay fee" is "táille athsheolta íosta."

Correct translation:  
Méid neamhbhailí le haghaidh %s=&lt;amount&gt;: '%s' (ní mór an táille athsheolta íosta de %s a bheith ann ar a laghad chun idirbhearta a fhorbhlocáil a chosc)
```

```
        <source>Maximum transaction weight is less than transaction weight without inputs</source>
        <translation>Tá an t-uasmheáchan idirbhirt níos lú ná meáchan idirbhirt gan ionchuir</translation>
    
YES  
The provided translation is in Irish (ga) but does not reflect the technical meaning accurately. It translates "weight" as "meáchan," which means physical "weight" and not the technical term used in Bitcoin transactions. The term "transaction weight" in Bitcoin context refers to a unit of measurement for transaction size/complexity, not physical weight, and ideally it should be left untranslated or explained more appropriately.

Additionally, the English phrase uses a more technical term "Maximum transaction weight," which would be better reflected with a closer technical equivalent or untranslated phrase to avoid confusion.

Improved translation suggestion:  
"Tá uasmheáchan idirbhirt níos lú ná meáchan idirbhirt gan ionchuir"

This removes the definite article "an" before "uasmheáchan," as "Maximum transaction weight" is more naturally rendered as "uas-mheáchan idirbhirt" without the definite article.

Alternatively, one could keep "transaction weight" untranslated or put in italics if a known term exists in Irish Bitcoin terminology:

"Tá an Maximum Transaction Weight níos lú ná meáchan idirbhirt gan ionchuir"

But since no established terminology is given, the first improved suggestion is safest.

Also confirming no issues with format specifiers or whitespace. There are no format specifiers in the source, and no whitespace issues.

Hence, the original translation is somewhat inaccurate but not spam or erroneous in format.

Correct translation:  
"Tá uasmheáchan idirbhirt níos lú ná meáchan idirbhirt gan ionchuir"
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>Naisc amach teoranta do Tor (-onlynet=onion) ach ní thugtar an seachfhreastalaí chun líonra Tor a bhaint amach: ní thugtar aon seachfhreastalaí, -oinniún nó -listenonion</translation>
    
YES  
The translation contains a few issues:  
1. "Ní thugtar an seachfhreastalaí" translates correctly as "the proxy is not provided," but the phrase "ní thugtar aon seachfhreastalaí, -oinniún nó -listenonion" is unclear and seems incomplete or awkward. In the source, it lists three options that are not given: "-proxy, -onion or -listenonion". The translation used "seachfhreastalaí, -oinniún nó -listenonion," where "-oinniún" is a mistranslation or typo for "-onion." It should be "-proxy, -onion nó -listenonion" to match the source. Also, "seachfhreastalaí" needs to be repeated only once or better structured to parallel the source.

2. The phrase "ach ní thugtar" is fine, but "líonra Tor a bhaint amach" is good. Still, each item should be clearly listed and correctly labeled.

Correct translation:  
Naisc amach teoranta do Tor (-onlynet=onion), ach níl an seachfhreastalaí chun líonra Tor a bhaint amach ar fáil: ní thugtar aon cheann de -proxy, -onion nó -listenonion.

This keeps the meaning, corrects the item names to English command-line flags as in the source, and smooths the grammar.
```

```
        <source>UTXO snapshot failed to validate. Restart to resume normal initial block download, or try loading a different snapshot.</source>
        <translation>Theip ar bhailíochtú a dhéanamh ar achomair UTXO. Atosaigh chun gnáthíoslódáil na mbloc tosaigh a atosú, nó bain triail as pictiúr eile a lódáil.</translation>
    
YES  
The phrase "Theip ar bhailíochtú a dhéanamh ar achomair UTXO" is awkward and unidiomatic in Irish. A more natural phrasing would be "Theip ar an achomharc UTXO a bhailíochtú" or "Theip ar dhearbhú achomair UTXO". Also, "pictiúr" is a literal "picture" and not the right term for "snapshot" in a technical sense. A better term would be "driogán" or "sneachta" for "snapshot," or simply transliterating "snapshot" if no common term exists. The phrase "gnáthíoslódáil na mbloc tosaigh" is understandable but could be smoother as "íoslódáil ghnáthbhloc tosaigh". Also, spacing and format is fine.

Corrected translation:  
Theip ar an achomharc UTXO a bhailíochtú. Atosaigh chun íoslódáil ghnáthbhloc tosaigh a atosú, nó bain triail as driogán eile a lódáil.
```

```
        <source>Unconfirmed UTXOs are available, but spending them creates a chain of transactions that will be rejected by the mempool</source>
        <translation>Tá UTXOanna neamhdheimhnithe ar fáil, ach cruthaítear slabhra idirbheart a ndiúltóidh an mempool dóibh má dhéantar iad a chaitheamh</translation>
    
YES  
The provided translation is in Irish (Gaeilge), which corresponds to the 'ga' language code, but it is not accurate because it uses Irish vocabulary and grammar unrelated to Bitcoin-specific terminology in English. Specifically, the translation is in Irish but is not idiomatic for technical Bitcoin terms like "UTXOs," "mempool," and "transactions." However, more importantly, there are spacing issues: no extra spaces but the flow could be improved for clarity. Also, there is a direct literal translation of "chain of transactions" as "slabhra idirbheart," which is roughly correct but might be clearer as "slabhra idirbhearta." The phrase "má dhéantar iad a chaitheamh" ("if they are spent") is okay but "spending" is best translated as "a chaitheamh" or "a chaitheamh amach," both acceptable.

Still, the main issue is that the translation lacks the English format specifiers, but the original sentence has none, so that is fine.

Since the existing translation is a reasonable literal translation but might confuse people not familiar with the Irish terms for Bitcoin concepts, a better translation might clarify "UTXOs" and "mempool" in Irish as technical terms, but given that those are probably loanwords, leaving as is is acceptable.

Thus, it is not problematic other than slight wording preference.

Therefore, I will say: NO
```

```
        <source>whitebind may only be used for incoming connections ("out" was passed)</source>
        <translation>ní féidir ceangaltán bán a úsáid ach amháin le haghaidh naisc isteach (ritheadh ​​​​"amach")</translation>
    
YES  
The translation has some spacing issues (extra spaces in "ritheadh ​​​​"amach"") and the phrasing can be improved for clarity and naturalness in Irish. The word "ní féidir" literally means "cannot" rather than "may only be". A better alternative would be "Ní féidir whitebind a úsáid ach le haghaidh naisc isteach ('amach' a cuireadh isteach)".

Correct translation:  
Ní féidir whitebind a úsáid ach le haghaidh naisc isteach ("amach" a cuireadh isteach)
```

```
        <source>Error opening coins database</source>
        <translation>Earráid agus bunachar sonraí boinn á oscailt</translation>
    
YES  
The translation "Earráid agus bunachar sonraí boinn á oscailt" literally means "Error and coins database opening," which is not idiomatic or fully accurate. The source phrase implies an error occurred while trying to open the coins database, so "when opening" or "during opening" should be conveyed. The conjunction "agus" ("and") is incorrect here.

Correct translation:  
"Earráid ag oscailt an bhunachar sonraí boinn"
```

```
        <source>Error: Got key that was not hex: %s</source>
        <translation>Earráid: Fuair ​​​​tú eochair nach heicsidheachúlach í: %s</translation>
    
YES
The translation contains unnecessary zero-width spaces (represented by multiple adjacent spaces) between "Fuair" and "tú," which is incorrect formatting. Additionally, the phrase "nach heicsidheachúlach í" is awkward and not the standard way to say "that was not hex." A more natural and accurate translation would be:

Correct translation:
Earráid: Fuair tú eochair nach heicsideachúlach í: %s
```

```
        <source>Failed to disconnect block.</source>
        <translation>Theip ar dhínascadh an bhloc.</translation>
    
YES  
The translation contains errors and does not accurately convey the meaning of the source. The phrase "Failed to disconnect block." refers to an unsuccessful attempt to disconnect a block (in Bitcoin context), which should be translated clearly with the verb indicating "failure" and the concept "disconnect".

Issues:  
- "Theip ar dhínascadh" is incorrect; "Theip ar" is not the correct idiomatic construction for "Failed to" in Irish Gaelic.  
- "dhínascadh" appears incorrect or a misspelling related to "disconnect". The verb for "disconnect" can be "dícheangal" or a form based on it.  
- The literal word order and grammar are off.

A correct Irish translation would be:  
"Theip ar dhícheangal an bhloc."

Explanation:  
- "Theip ar" means "Failed to" (in a sense of failure upon trying)  
- "dhícheangal" is the verbal noun form of "dícheangal" (to disconnect) with the appropriate lenition after "ar"  
- "an bhloc" = "the block", correctly lenited after the preposition "ar".

Correct translation:  
Theip ar dhícheangal an bhloc.
```

```
        <source>Failed to rescan the wallet during initialization</source>
        <translation>Theip athscanadh ar an sparán le linn túsúchán</translation>
    
YES  
The translation contains a typo and a slight grammatical error. "athscanadh" should be "athscánadh" (with an accent on 'á') to mean "rescanning." Also, "túsúchán" should be "túsúchán" (correct as is), but the phrase "ar an sparán" is acceptable for "the wallet," though "sparán" can be masculine or feminine depending on dialect; however, this is not problematic.

Correct translation:  
Theip athscánadh ar an sparán le linn túsúchán
```

```
        <source>Failed to start indexes, shutting down..</source>
        <translation>Theip ar thús a chur leis na hinnéacsanna, dúnadh.</translation>
    
YES  
The translation contains several issues:  
- "Theip ar thús a chur leis na hinnéacsanna" is awkward and not idiomatic in Irish.  
- There is a spelling error in "thús" (should be "tús").  
- The phrase for "shutting down.." should reflect the progressive or immediate nature, and the double period ".." is not standard punctuation.  
- A more natural and accurate translation would be:  
  "Theip ar thús na n-innéacsanna, ag dúnadh."  

Correct translation:  
Theip ar thús na n-innéacsanna, ag dúnadh.
```

```
        <source>Failed to write undo data.</source>
        <translation>Theip ar scríobh sonraí cealaigh.</translation>
    
YES  
The translation is mostly accurate, but the verb form could be improved for better naturalness in Irish (Gaeilge). "Theip ar scríobh" is understandable but slightly awkward. A better construction is "Theip orm scríobh" or more simply "Theip ar scríobh," though "Theip orm" (The failure was on me) is more idiomatic when referring to the subject failing to do an action. Also, the noun "sonraí cealaigh" ("cancel data") could be better expressed as "sonraí aisghabhála" ("undo data" or "recovery data"), since "undo" in the context of Bitcoin likely refers to reversing a prior action rather than canceling.

Correct translation:  
Theip orm sonraí aisghabhála a scríobh.
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>Bloc geineasas mícheart nó ní aimsithe. datadir mícheart don líonra?</translation>
    
YES  
The translation is mostly accurate but contains some minor issues:  
- "datadir" should not be left untranslated as it is a technical term and should be consistent with the source or properly adapted. In English, "datadir" refers to "data directory," and it is better either to leave it as is or transliterate it consistently, preferably in italics or quotes, but not mixed in the sentence without capitalization.  
- The sentence in Irish starts with a lowercase "Bloc geineasas" which should be capitalized as it begins the sentence.  
- Also, the phrase "bloc geineasas mícheart" should use the singular "bloc géineas" (with fada accents) for "genesis block," maintaining proper Irish spelling.  
- The word "líonra" (network) is correct.  
- The question mark placement is correct.

A better translation would be:  
"Bloc géineas mícheart nó gan ann aimsithe. An bhfuil an datadir mícheart don líonra?"

Or alternatively, if "datadir" is left as is and marked as a term:  
"Bloc géineas mícheart nó gan ann aimsithe. Datadir mícheart don líonra?"

Full corrected translation with minor punctuation adjustment:  
"Bloc géineas mícheart nó gan ann aimsithe. An bhfuil an datadir mícheart don líonra?"
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>Méid neamhbhailí le haghaidh %s=1: '%s' (ar a laghad %s)</translation>
    
YES  
The translation incorrectly substitutes the placeholder `<amount>` in the source with the literal `1` in the target, which is incorrect—placeholders must be preserved as in the source. Additionally, the phrase "méid neamhbhailí le haghaidh" is somewhat literal and can be improved for clarity. The English source emphasizes that the amount provided is invalid for the argument `%s=<amount>`, so the translation should keep the placeholder and express "invalid amount".

Correct translation:  
Méid neamhbhailí do %s=&lt;amount&gt;: '%s' (caithfidh sé a bheith ar a laghad %s)
```

```
        <source>Listening for incoming connections failed (listen returned error %s)</source>
        <translation>Theip ar éisteacht le naisc isteach (éisteacht ar ais earráid %s)</translation>
    
YES  
The translation contains inaccurate and awkward phrasing. "Theip ar éisteacht le naisc isteach" is a direct but somewhat unnatural translation for "Listening for incoming connections failed." Also, "éisteacht ar ais earráid %s" is a literal and unclear rendering of "listen returned error %s."

A more natural and accurate Irish translation would be:  
"Theip ar éisteacht le nascanna isteach (d'fhill éisteacht ar earráid %s)"

Explanation:  
- "Theip ar éisteacht" correctly reflects "Listening failed."  
- "nascanna isteach" is the plural of "nasc isteach" (incoming connections), which fits better since multiple connections are generally involved.  
- "d'fhill éisteacht ar earráid %s" translates as "listen returned error %s," using the past tense verb "d'fhill" (returned).  

Correct translation:  
Theip ar éisteacht le nascanna isteach (d'fhill éisteacht ar earráid %s)
```

```
        <source>Prune cannot be configured with a negative value.</source>
        <translation>Ní féidir Bearradh a bheidh cumraithe le luach diúltach.</translation>
    
YES  
The translation is partly incorrect and mixes Irish (Gaelic) and some other language (likely Irish influenced by English structure), and uses some incorrect grammar. The word "Bearradh" is a rough word for "Prune" but it is not used correctly here, and the sentence structure is awkward. Also, "Ní féidir" means "cannot," but the sentence construction is off, and the phrase "a bheidh cumraithe" is not correct for "be configured."

A better, correct Irish translation would be:  
**Ní féidir bearradh a chumrú le luach diúltach.**  

This means: "Prune cannot be configured with a negative value."  
- "bearradh" is "prune" (noun),  
- "a chumrú" = "to configure" (verbal noun with possessive particle),  
- "Ní féidir" = "cannot",  
- "le luach diúltach" = "with a negative value."  

Also note that "bearradh" is lowercase here, consistent with Irish capitalization rules.
```

```
        <source>Pruning blockstore…</source>
        <translation>Blocsiopa á bhearradh…</translation>
    
YES  
The Irish translation uses "Blocsiopa á bhearradh," which is not a proper or commonly used term in Irish for "blockstore" or the act of pruning in this technical context. The word "blocsiopa" is a direct phonetic transliteration of "blockstore" and sounds unnatural in Irish. Also, "á bhearradh" is awkward and not a standard gerund form in Irish.

A better translation would retain the technical term more clearly and use a more accurate verb form for "pruning." Since "pruning" in computing/Bitcoin context means removing unnecessary data, a suitable Irish verb is "ag gearradh siar" (cutting back) or "ag laghdú" (reducing).

A recommended translation:  
"Ag gearradh siar ar an mbunachar bloc…"  
or more literally consistent with the source:  
"Ag gearradh siar an blocsiopa…"  

However, since "blockstore" is technical and might have no direct equivalent, it may be acceptable to keep "blockstore" untranslated:

**Correct translation:**  
"Ag gearradh siar an blockstore…"  

If a fully Irish spelling is desired and the term "blockstore" is acceptable as a loanword, it can be simply written as "ag gearradh siar blockstore…"

Therefore, the corrected full translation could be:  
"Ag gearradh siar blockstore…"  

Or, if preferring a noun form:  
"Blocsiopa á laghdú…" (less natural)  

Given this, the best practical translation is:  
**Ag gearradh siar blockstore…**
```

```
        <source>SQLiteDatabase: Failed to execute statement to verify database: %s</source>
        <translation>SQLiteDatabase: Theip ar rith ráiteas chun an bunachar sonraí a fhíorú: %s</translation>
    
YES
The phrase "Theip ar rith ráiteas" is not idiomatic and sounds awkward in Irish (ga). A more natural translation of "Failed to execute statement to verify database" would use "Theip ar rith ráitis" (plural of ráiteas/statement) or better yet, rephrase as "Theip ar rith an ráitis chun an bunachar sonraí a fhíorú". Also, "ráiteas" should be in singular/plural consistency, preferably singular for "statement" unless multiple statements are meant.

Correct translation:
SQLiteDatabase: Theip ar rith an ráitis chun an bunachar sonraí a fhíorú: %s
```

```
        <source>SQLiteDatabase: Failed to prepare statement to verify database: %s</source>
        <translation>SQLiteDatabase: Theip ar ullmhú ráiteas chun bunachar sonraí: %s a fhíorú</translation>
    
YES
The translation incorrectly places the verb or phrase order, causing confusion. The phrase should reflect failure to prepare a statement for verifying the database, i.e. "Failed to prepare statement to verify database."

A better translation would be:
SQLiteDatabase: Theip ar ullmhú ráiteas chun an bunachar sonraí a fhíorú: %s
```

```
        <source>Unknown address type '%s'</source>
        <translation>Anaithnid cineál seoladh '%s'</translation>
    
YES
The Irish ('ga') word "Anaithnid" means "unknown," but it should be capitalized if it starts the sentence. More importantly, the phrase structure is slightly off for idiomatic Irish. "cineál seoladh" is correct for "address type," but a more natural phrasing is:

"cineál seolta neamhaithnide '%s'"

However, the simplest correction to keep the source meaning intact and idiomatic would be:

"Ainmniú cineál seolta anaithnid '%s'"

But that is less common. Generally, Irish tends to place the adjective after the noun, so "cineál seoladh anaithnid '%s'" is correct.

Also, note that "seoladh" (address) is typically used correctly here, and the word order should remain.

Corrected translation (capitalizing the first letter and ordering):

"Ainmniú cineál seoladh anaithnid '%s'"

or better (simpler and natural):

"Cineál seoladh anaithnid '%s'"

Therefore, the best correction is:

"Cineál seoladh anaithnid '%s'"

# So final:

YES
The translation "Anaithnid cineál seoladh '%s'" has incorrect word order for Irish. The adjective should follow the noun: "cineál seoladh anaithnid '%s'".
Also, the first letter should be capitalized as it begins the sentence.

Correct translation:
"Cineál seoladh anaithnid '%s'"
```

```
        <source>Unknown change type '%s'</source>
        <translation>Anaithnid cineál sóinseáil '%s'</translation>
    
YES  
The Irish word "sóinseáil" is incorrect and does not correspond to the bitcoin-related term "change" (i.e., change amount in a transaction). The correct Irish word for "change" in this financial/transaction context is "athrú."  

Correct translation:  
Anaithnid cineál athraithe '%s'
```

```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>Rialacha nua anaithnid curtha i ngníomh (leagan giotán %ii)</translation>
    
YES  
The translation has an error with the format specifier "%ii" which should be "%i" to match the source. Also, the phrase "leagan giotán" for "versionbit" is unnatural and incorrect; a better term could be "bithleagan" or "bit leagain" (bit version). 

Correct translation:  
Rialacha nua anaithnid curtha i ngníomh (bithleagan %i)
```

```
        <source>Unrecognised option "%s" provided in -test=&lt;option&gt;.</source>
        <translation>Rogha neamhaitheanta "%s" curtha ar fáil i -test=1.</translation>
    
YES  
The translation is inaccurate and inconsistent with the source. The source includes a format specifier "%s" that should be preserved in the translation. Instead, the translation replaces "%s" with "1", which is incorrect. Also, the original ending is "-test=&lt;option&gt;", but the translation ends with "-test=1", which is a specific value rather than a placeholder.

A more accurate translation preserving the placeholder would be:  
Rogha neamhaitheanta "%s" curtha ar fáil i -test=&lt;rogha&gt;.
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>Theip ar chruthú comhaid sparán: %s</translation>
    
YES  
The Irish translation contains a minor grammatical error: "ar" is incorrectly used instead of "ag" after "Theip". The correct phrase is "Theip ag" when indicating failure to do something.  

Correct translation:  
Theip ag chruthú comhaid sparán: %s
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Earráid: Níorbh fhéidir watch amháin tx %s a chur le sparán faire amháin</translation>
    
YES  
The translation contains some literal and awkward phrases that do not sound natural in Irish Gaelic ("ga"). The phrase "watchonly tx" and "watchonly wallet" have been left partly untranslated ("watch amháin tx" and "sparán faire amháin"), which may confuse native speakers. The term "watchonly" in the Bitcoin context would be better conveyed by adapting it as "faire amháin" or "nagfaire" consistently, and "tx" (transaction) should be translated or at least contextualized properly. Also, there is an inconsistent use of "watch amháin" when "watchonly" should be treated as a compound adjective, not split.

Better translation would be:

Earráid: Níorbh fhéidir an idirbheart faire amháin %s a chur leis an sparán faire amháin

Notes:  
- "idirbheart" is the common term for "transaction" in financial/Bitcoin contexts.  
- "faire amháin" can convey "watch-only".  
- "a chur leis an sparán faire amháin" = "to add to the watch-only wallet".  
- The format specifier %s is preserved correctly with no extra space.  

Hence the corrected translation is:

Earráid: Níorbh fhéidir an idirbheart faire amháin %s a chur leis an sparán faire amháin
```

```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>Tá carachtair neamhshábháilte i nóta tráchta (%s) Gníomhaire Úsáideora.</translation>
    
YES  
The translation is not accurate and is awkward in Irish ('ga'). The phrase "User Agent comment (%s) contains unsafe characters." should clearly convey that the comment within the user agent contains unsafe characters. The provided translation instead literally says "There are unsafe characters in a traffic note (%s) User Agent," which is confusing and misplaced.

A better translation would be:  
"Tá carachtair neamhshábháilte i dtuairisc Gníomhaire Úsáideora (%s)."  

This means: "There are unsafe characters in the User Agent comment (%s)."
```
</details>
