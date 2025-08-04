# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ga</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bga%5D%20low%20quality)


```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
YES - The translation incorrectly translates "Comma separated file" as "Comhad athróige camógdheighilte" which means "Comma-separated change file". The correct translation for "Comma separated file" in Irish is "Comhad camógdheighilte".
Comhad camógdheighilte
```

```
        <source>Exporting Failed</source>
        <translation>Theip ar Easpórtáil</translation>
    
YES, The provided translation for "Exporting Failed" into Irish ('ga') is grammatically incorrect and does not accurately convey the intended meaning. The word "Theip" is the past tense of "teip" (fail), which is correct, but "ar Easpórtáil" (on export) is not the standard way to express "exporting" as a gerund or present participle in this context. A more accurate and natural translation would be "Theip ar Easpórtáil" or "Rinneadh Teip ar Easpórtáil".

The correct translation should be:
Theip ar Easpórtáil
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Iontráil an pasfhrása nua don sparán. &lt;br/&gt;Le do thoil úsáid pasfhocail de &lt;b&gt;dheich gcarachtar randamacha nó níos mó&lt;/b&gt;, nó &lt;/b&gt;ocht bhfocal nó níos mó&lt;/b&gt;.</translation>
    
YES - The translation is problematic because the formatting for the second bolded phrase is incorrect. The closing bold tag is misplaced.
Correct translation: Iontráil an pasfhrása nua don sparán. &lt;br/&gt;Le do thoil úsáid pasfhocail de &lt;b&gt;dheich gcarachtar randamacha nó níos mó&lt;/b&gt;, nó &lt;b&gt;ocht bhfocal nó níos mó&lt;/b&gt;.
```

```
        <source>Wallet encryption failed</source>
        <translation>Theip ar chriptiú sparán</translation>
    
YES: The translation contains an incorrect word. "Theip" is not a valid word in Irish. The correct translation should be "Theip ar chriptiú sparán" which means "Wallet encryption failed".
Theip ar chriptiú sparán
```

```
        <source>Wallet unlock failed</source>
        <translation>Theip ar dhíghlasáil sparán</translation>
    
YES - The translation provided is not a correct translation of the English source text. The provided translation appears to be a concatenation of unrelated Irish words and does not convey the meaning of "Wallet unlock failed." The correct translation of "Wallet unlock failed" into Irish is "Theip ar dhíghlasáil an sparán".
Theip ar dhíghlasáil an sparán
```

```
        <source>IP/Netmask</source>
        <translation>PI/Mascadhidirlíon</translation>
    
YES, The translation is problematic due to incorrect word choice and spelling.
The correct translation for "IP/Netmask" in the context of Bitcoin is "IP/Maisc Líonra".
PI/Mascadhidirlíon
```

```
        <source>Onion</source>
        <comment>network name</comment>
        <extracomment>Name of Tor network in peer info</extracomment>
        <translation>Oinniún</translation>
    
YES. The translation is incorrect and does not reflect the intended meaning of "Onion" in the context of Bitcoin and the Tor network. "Oinniún" means "onion" in Irish, referring to the vegetable, not the Tor network.
The correct translation for the name of the Tor network in this context should be transliterated or directly represented.

Correct translation: "Onion"
```

```
        <source>%1 d</source>
        <translation>%1 l</translation>
    
YES, The translation incorrectly substitutes 'd' for 'l'. The format specifier %1 has been correctly transferred.
%1 d
```

```
        <source>%1 h</source>
        <translation>%1 u</translation>
    
YES
The translation is incorrect. The source text "%1 h" likely refers to "1 hour" in the context of Bitcoin transaction confirmation times. The provided translation "%1 u" does not convey this meaning. The correct translation for "h" (hour) in this context would be "uair" in Irish (ga).

NO
```

```
        <source>%1 m</source>
        <translation>%1 n</translation>
    
YES
The translation is incorrect. 'm' in the source text represents 'million', but it has been translated to 'n' in the target language, which is not a correct translation for 'million'.

Correct translation: %1 mh
```

```
        <source>N/A</source>
        <translation>N/B</translation>
    
YES, The translation is incorrect and uses a Spanish abbreviation instead of the intended meaning. In the context of Bitcoin, "N/A" (Not Applicable) should be translated to something like "Ní le feidir a chur i bhfeidhm" or a similar Irish phrase meaning "Not applicable". "N/B" translates to "Nota Bene" in Spanish, which means "Note well".

Correct translation: Ní le feidir a chur i bhfeidhm
```

```
        <source>Syncing Headers (%1%)…</source>
        <translation>Ceanntásca á Sioncronú (%1 %)…</translation>
    
YES - The spacing around the format specifier `%1%` is incorrect. In the source text, there is no space between the percent sign and the number. In the translation, there is a space.
Correct translation: Ceanntásca á Sioncronú (%1%)…
```

```
        <source>Show the list of used sending addresses and labels</source>
        <translation>Taispeáin an liosta de seoltaí seoladh úsáidte agus na lipéid </translation>
    
YES, The translation is problematic due to grammatical errors and incorrect word choice. The phrase "seoltaí seoladh" is redundant and grammatically incorrect. The correct translation should reflect "sending addresses" more accurately.

NO
```

```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>Taispeáin an liosta de seoltaí glacadh úsáidte agus lipéid </translation>
    
YES: The word "seoltaí" should be in the genitive plural form "seoltaí" because it is preceded by "liosta de". The correct translation is: Taispeáin an liosta de sheoltaí glactha úsáidte agus lipéid.
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Lódáil Idirbheart Bitcoin Sínithe go Páirteach ón gearrthaisce</translation>
    
YES, The translation has a spelling error. The word "Lódáil" should be "Luchtaigh".

NO
```

```
        <source>Sending addresses</source>
        <translation>Seoltaí seoladh</translation>
    
YES, The translation is problematic because "Seoltaí seoladh" literally translates to "Sending addresses" but it sounds awkward and unnatural in Irish. A more natural and accurate translation would be "Seoltaí seolta".

Correct translation: Seoltaí seolta
```

```
        <source>%1 client</source>
        <translation>%1 cliaint</translation>
    
YES, The translation contains a misspelling in the word "client".
%1 client
```

```
        <source>Show</source>
        <translation>Sconas</translation>
    
YES. The translation is incorrect. 'Sconas' means 'Hide' in Irish (ga). The correct translation for 'Show' is 'Taispeáin'.
Sconas
```

```
        <source>Error creating wallet</source>
        <translation>Earráid agus sparán á chruthú</translation>
    
YES: The word "agus" (and) is used incorrectly, which suggests a misunderstanding of the grammatical structure. The correct translation should use the genitive case for "wallet".
Earráid ag cruthú sparán
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Sparán &lt;b&gt;criptithe&lt;/b&gt;agus &lt;b&gt;díghlasáilte&lt;/b&gt;faoi láthair</translation>
    
YES, The word "agus" should be followed by a space.
Sparán &lt;b&gt;criptithe&lt;/b&gt; agus &lt;b&gt;díghlasáilte&lt;/b&gt; faoi láthair
```

```
        <source>Change:</source>
        <translation>Sóinseáil:</translation>
    
YES: The translation uses "Sóinseáil" which means "scratch" or "itch" in Irish. The correct translation for "change" in the context of Bitcoin transactions (i.e., returning unspent funds) is "an t-athrú".
Correct translation: an t-athrú:
```

```
        <source>Received with address</source>
        <translation>Seoladh faighte le</translation>
    
YES: The translation is missing the word "address" and the word order is incorrect. The correct translation should be "Seoladh faighte le seoladh".
```

```
        <source>Copy transaction ID and output index</source>
        <translation>Cóipeáil idirbheart  ID agus innéacs aschuir</translation>
    
YES, The translation of "transaction ID" is inaccurate. The correct translation for "transaction ID" in the context of Bitcoin is "Sraithuimhir idirbhirt".

The correct translation is:
Cóipeáil sraithuimhir idirbhirt agus innéacs aschuir
```

```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
YES, The translation of "change" to "sóinseáil" is incorrect. In the context of Bitcoin, "change" refers to the remaining amount of Bitcoin after a transaction. The correct Irish word for this is "íocaíocht" or "athrú." Additionally, "cóipeáíl" is a gerund form and might sound a bit awkward here. A more natural translation would use the imperative form.
Correct translation: Cóipeáil íocaíocht
```

```
        <source>change from %1 (%2)</source>
        <translation>sóinseáil ó %1 (%2)</translation>
    
YES, the word "sóinseáil" translates to "nuance" or "subtlety" in English, which is not the correct translation for "change" in the context of Bitcoin. The correct translation for "change" in this context would be "athrú".

The correct translation is:
athrú ó %1 (%2)
```

```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>An bhfuil tú cinnte gur mian leat an sparán &lt;i&gt;%1 &lt;/i&gt;?</translation>
    
YES - The original English has "wallet %1", but the Irish translation has "wallet %1 i". The "i" is an extraneous character.
An bhfuil tú cinnte gur mian leat an sparán &lt;i&gt;%1&lt;/i&gt;?
```

```
        <source>Open wallet failed</source>
        <translation>Theip ar oscail sparán</translation>
    
YES, The translation is problematic as it contains a typo. The correct translation for "Open wallet failed" is "Theip ar oscailt sparán".
```

```
        <source>Opening Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the open wallet progress window which indicates to the user which wallet is currently being opened.</extracomment>
        <translation>Sparán Oscailte&lt;b&gt;%1&lt;/b&gt;…</translation>
    
YES, The word "Sparán" is translated as "wallet", which is correct, but it is not used in the correct grammatical form. The correct form should be "Oscailt Sparán" instead of "Sparán Oscailte".
Oscailt Sparán &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Restore wallet failed</source>
        <extracomment>Title of message box which is displayed when the wallet could not be restored.</extracomment>
        <translation>Theip ar athchóiriú an sparán</translation>
    
YES
The translation is grammatically incorrect and does not accurately convey the meaning of the source text. The word "Theip" is not a standard Irish word and appears to be a misspelling or incorrect construction. The correct translation should reflect the failure of the wallet restoration.

Correct translation: Theip ar an sparán a athchóiriú
```

```
        <source>Restore wallet message</source>
        <extracomment>Title of message box which is displayed when the wallet is successfully restored.</extracomment>
        <translation>Athchóirigh teachtaireacht sparán</translation>
    
YES: The translation is inaccurate. The English "Restore wallet message" implies a message *about* restoring the wallet, or a message *for* restoring the wallet. The Irish translation "Athchóirigh teachtaireacht sparán" literally translates to "Restore wallet message", but it could be interpreted as "Restore *the* wallet message". A more accurate translation would be "Teachtaireacht athchóirithe sparán" which translates to "Wallet restoration message".

Teachtaireacht athchóirithe sparán
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>An seoladh chomhcheangailte leis an iontráil liosta seoltaí seo. Ní féidir é seo a mionathraithe ach do seoltaí seoladh.</translation>
    
YES. The translation contains a repetition of the word "seoladh" which makes it sound unnatural and slightly nonsensical. It should be corrected to avoid redundancy.

Correct translation: An seoladh chomhcheangailte leis an iontráil liosta seoltaí seo. Ní féidir é seo a mionathraithe ach do sheoltaí seolta.
```

```
        <source>New sending address</source>
        <translation>Seoladh nua seoladh</translation>
    
YES, The translation is problematic. The phrase "seoladh nua seoladh" is repetitive and does not accurately convey the meaning of "New sending address". The word "seoladh" is repeated unnecessarily. The correct translation should be "Seoladh seolta nua".

NO
```

```
        <source>Edit sending address</source>
        <translation>Eagarthóireacht seoladh seoladh</translation>
    
YES: The translation is redundant, repeating "seoladh" (address) twice.
Correct translation: Eagarthóireacht seoladh seolta
```

```
        <source>New key generation failed.</source>
        <translation>Theip ar giniúint eochair nua.</translation>
    
YES, The translation uses the wrong verb for "generation". "Giniúint" means "creation" or "birth". The correct verb for "generation" in this context would be "cruthú" or "gineadh". Additionally, the word order is slightly unnatural.
The correct translation is: Níor ghineadh eochair nua.
```

```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Stórálfar thart ar %1 GB de shonraí sa comhadlann seo.</translation>
    
YES, the word "thart" should be "thart ar". The phrase "thart ar" means "about" or "approximately", and the word "thart" alone does not convey the same meaning in this context.

NO
```

```
        <source>Limit block chain storage to</source>
        <translation>Teorainn a chur le blocshlabhra stórála go</translation>
    
YES, The translation is grammatically incorrect and does not accurately convey the meaning of the source text. The word order and verb choice are unnatural in Irish.

The correct translation should be: teorainn a chur le stóráil an bhlocshlabhra go.
```

```
        <source>Last block time</source>
        <translation>Am bloc deireanach</translation>
    
YES, The translation is inaccurate and problematic. The phrase "Am bloc deireanach" translates to "The last block" in English. The correct translation for "Last block time" would be "Am an bhloc dheireanaigh".

Correct translation: Am an bhloc dheireanaigh
```

```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>Tá %1 ag sioncronú faoi láthair. Déanfaidh sé é a íoslódáil agus a fíorú ar ceanntásca agus bloic ó phiaraí go dtí barr an blocshlabhra.</translation>
    
YES, The translation uses the word "ceanntásca" which means "headings" or "headers" in English, but it is also a common word for "heads". The context of Bitcoin syncing headers and blocks suggests "ceannslíneacha" which translates to "headlines" or "headers" and would be more appropriate for a Bitcoin context. Additionally, the translation misses the word "download" and instead uses "déanfaidh sé é a íoslódáil" which means "it will download it". It should be more direct.

Correct translation: Tá %1 ag sioncronú faoi láthair. Déanfaidh sé ceannslíneacha agus bloic a íoslódáil agus a fhíorú ó phiaraí go dtí barr an blocshlabhra.
```

```
        <source>Unknown. Syncing Headers (%1, %2%)…</source>
        <translation>Anaithnid. Ceanntásca á Sioncronú (%1, %2 %)…</translation>
    
YES - The translation has an unnecessary space before the percentage signs.
Anaithnid. Ceanntásca á sioncronú (%1, %2)…
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>Conair iomlán chuig script comhoiriúnach %1 (m.sh. C:\Downloads\hwi.exe nó /Users/you/Downloads/hwi.py). Tabhair aire: is féidir le malware do bhoinn a ghoid!</translation>
    
YES, The translation contains an erroneous word "m.sh." which should be "m.sh.". It also mistranslated "e.g." as "m.sh.".
Correct translation: Conair iomlán chuig script chomhoiriúnach %1 (m.sh. C:\Downloads\hwi.exe nó /Users/you/Downloads/hwi.py). Tabhair aire: is féidir le malware do bhoinn a ghoid!
```

```
        <source>(0 = auto, &lt;0 = leave that many cores free)</source>
        <translation>(0 = uath, &lt;0 = fág an méid sin cóir saor)</translation>
    
YES, The translation is problematic because "uath" is not the correct Irish translation for "auto". The correct translation for "auto" in this context would be "uathoibríoch".

(0 = uathoibríoch, <0 = fág an méid sin cóir saor)
```

```
        <source>Spend unconfirmed change</source>
        <translation>Caith sóinseáil neamhdheimhnithe</translation>
    
YES, the translation contains erroneous content. The word "sóinseáil" in Irish means "to harass" or "to annoy". It should be "athrú" which means "change" in the context of money or transactions.

NO
```

```
        <source>Whether to show coin control features or not.</source>
        <translation>Gnéithe rialúchán bonn a thaispeáint nó nach.</translation>
    
YES - The translation is grammatically incorrect and awkward. The English phrase "Whether to show... or not" translates more naturally as "An bhfuil... le taispeáint nó nach bhfuil".

Correct translation: An bhfuil gnéithe rialúchán bonn le taispeáint nó nach bhfuil.
```

```
        <source>OK</source>
        <translation>Togha</translation>
    
YES, The translation is problematic because "Togha" means "Choice" in Irish (ga). The correct translation for "OK" in Irish is "Ceart go leor".
Ceart go leor
```

```
        <source>none</source>
        <translation>ceann ar bith</translation>
    
YES, The translation for "none" into "ceann ar bith" is not accurate in the context of Bitcoin. "Ceann ar bith" translates to "any head" or "any leader" and does not convey the meaning of "none" which would typically be "níl" or "faic" in Irish.

NO
```

```
        <source>This change would require a client restart.</source>
        <translation>Theastódh cliant a atosú leis an athrú seo.</translation>
    
YES: The translation is grammatically incorrect and sounds unnatural in Irish. The word "Theastódh" should be "Bheadh" or "Mhouldh". "Athrú seo" should be "athrú seo" or "an t-athrú seo." The correct translation would be "Bheadh gá le cliant a atosú leis an athrú seo." or "Mhouldh cliant a atosú leis an athrú seo."
```

```
        <source>Broadcast Tx</source>
        <translation>Craol Tx</translation>
    
YES, The translation is problematic because "Craol" is not a recognized Irish word and does not convey the meaning of "Broadcast Tx" in the context of Bitcoin. A more appropriate translation would be "Craoladh Tx" or "Craol Tx".
The correct translation is: Craoladh Tx
```

```
        <source>Failed to load transaction: %1</source>
        <translation>Theip ar lódáil idirbheart: %1</translation>
    
YES, The translation has an erroneous word. "Theip ar" should be "Theip ar".
The correct translation is: Theip ar lódáil idirbheart: %1
```

```
        <source>Failed to sign transaction: %1</source>
        <translation>Theip ar síniú idirbheart: %1</translation>
    
YES, The translation is problematic because the word "Theip" is not a valid Irish word and therefore the translation is nonsensical. The correct translation should be "Theipigh ar shainiú idirbheart: %1".
```

```
        <source>Transaction broadcast failed: %1</source>
        <translation>Theip ar chraoladh idirbhirt: %1</translation>
    
YES - The translation uses the word "Theip" which is not a standard or recognized word in the Irish language. The correct term for "failed" in this context would be "chlis".

Theip ar chraoladh idirbhirt: %1
chlis ar chraoladh idirbhirt: %1
```

```
        <source>PSBT copied to clipboard.</source>
        <translation>Cóipeáladh IBSP chuig an gearrthaisce.</translation>
    
YES, the translation is problematic. The term "PSBT" has been incorrectly translated to "IBSP". Additionally, the term "clipboard" has been translated to "gearrthaisce" which is a valid Irish word, but the overall sentence structure and the use of "IBSP" is incorrect for the context of Bitcoin.

NO
```

```
        <source>N/A</source>
        <translation>N/B</translation>
    
YES, The translation is incorrect and uses a Spanish abbreviation instead of the intended meaning. In the context of Bitcoin, "N/A" (Not Applicable) should be translated to something like "Ní le feidir a chur i bhfeidhm" or a similar Irish phrase meaning "Not applicable". "N/B" translates to "Nota Bene" in Spanish, which means "Note well".

Correct translation: Ní le feidir a chur i bhfeidhm
```

```
        <source>Blocksdir</source>
        <translation>Eolbloic</translation>
    
YES
The translation is incorrect and does not correspond to the source text. The correct translation of "Blocksdir" in the context of Bitcoin would be a term related to directories for blocks.
The correct translation should be something like "Eolaire Bloic" or "Eolaire Bloc".

Eolaire Bloic
```

```
        <source>Elapsed time since a novel block passing initial validity checks was received from this peer.</source>
        <translation>Tá achar ama caite ó fuarthas bloc úrscéil a rinne na seiceálacha bailíochta tosaigh ón gcomhghleacaí seo.</translation>
    
YES - The translation uses "achar ama" which is a literal translation of "elapsed time" but it sounds awkward and unnatural in Irish. A more natural way to say this would be "Am atá caite" or "An t-am atá caite". Also, "fuarthas bloc úrscéil" translates to "a novel block was received" but the meaning in the context of Bitcoin is more about "a new block". Therefore, "bloc nua" would be a better translation.

Correct translation: An t-am atá caite ó fuarthas bloc nua a rinne na seiceálacha bailíochta tosaigh ón gcomhghleacaí seo.
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>Chuaigh an t-am caite ó fuarthas idirbheart úrnua a glacadh isteach inár mempool ón bpiaraí seo.</translation>
    
YES - The translation is grammatically incorrect and awkward. The word order is unnatural. The correct translation should be: "An t-am a chuaigh thart ó fuarthas an t-idirbheart úrnua a glacadh isteach inár mempool ón bpiaraí seo."
```

```
        <source>Last block time</source>
        <translation>Am bloc deireanach</translation>
    
YES, The translation is inaccurate and problematic. The phrase "Am bloc deireanach" translates to "The last block" in English. The correct translation for "Last block time" would be "Am an bhloc dheireanaigh".

Correct translation: Am an bhloc dheireanaigh
```

```
        <source>detecting: peer could be v1 or v2</source>
        <extracomment>Explanatory text for "detecting" transport type.</extracomment>
        <translation>bhrath: d’fhéadfadh v1 nó v2 a bheith i gcomhghleacaí</translation>
    
YES: The provided translation uses an incorrect word for "detecting". The correct word in Irish for detecting is "braitear" or "á bhrath". The translation uses "bhrath" which is the past tense of "brath" (to betray).
braitear: d’fhéadfadh v1 nó v2 a bheith i gcomhghleacaí
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
    
YES: The translation is missing a crucial format specifier (%2) and has incorrectly translated "wallet contents" as "inneachar sparán" (meaning "contents of a purse" or "contents of a wallet" in a literal sense) instead of the more appropriate "ábhar sparán" or "ábhar sparánachta" (referring to the actual contents of a Bitcoin wallet). Additionally, the phrasing "ag goid a n-inneachar sparán" is slightly awkward and could be more direct.

Correct translation:
Fáilte go consól RPC %1.
Úsáid saigheada suas agus síos chun an stair a nascleanúint, agus %2 chun an scáileán a ghlanadh.
Úsáid %3 agus %4 chun an clómhéid a mhéadú nó a laghdú.
Clóscríobh %5 le haghaidh forbhreathnú ar na horduithe atá ar fáil.
Chun tuilleadh eolais a fháil faoin gconsól seo a úsáid, clóscríobh %6.

%7 RABHADH: Bhí scamadóirí gníomhach, ag rá le húsáideoirí orduithe a chlóscríobh anseo, ag goid ábhar a sparán. Ná húsáid an consól seo gan iarmhairtí ordaithe a thuiscint go hiomlán.%8
```

```
        <source>Ban for</source>
        <translation>Cosc do</translation>
    
YES, The translation is grammatically incorrect and does not convey the intended meaning of "Ban for" in Irish. It seems to be a literal and incorrect translation.

The correct translation should be something like:

"Díbirthear as" or "Toirmeasctha as" if it means "banned from".
If it means "ban for" as in "a ban for [reason]", then it would be "Toirmeasc ar" or "Bann ar".

Without further context, it's hard to be precise, but the provided translation "Cosc do" is not suitable.

Let's assume "Ban for" means a ban in relation to something, like a ban for an action. In that case, a better translation would be:

YES, Toirmeasc ar
```

```
        <source>Copy message</source>
        <translation>Cóipeáil  teachtaireacht</translation>
    
YES: There is an extra space between "Cóipeáil" and "teachtaireacht".
Cóipeáil teachtaireacht
```

```
        <source>Base58 (P2SH-SegWit)</source>
        <translation>Base58 (P2SH- SegWit)</translation>
    
YES, The translation has a space between "P2SH-" and "SegWit" which is not present in the source text.
Base58 (P2SH-SegWit)
```

```
        <source>Change:</source>
        <translation>Sóinseáil:</translation>
    
YES: The translation uses "Sóinseáil" which means "scratch" or "itch" in Irish. The correct translation for "change" in the context of Bitcoin transactions (i.e., returning unspent funds) is "an t-athrú".
Correct translation: an t-athrú:
```

```
        <source>Custom change address</source>
        <translation>Seoladh sóinseáil saincheaptha</translation>
    
YES, The translation is problematic because "sóinseáil" means "sexual intercourse" in Irish. The correct translation for "change" in the context of Bitcoin transactions is "babhla" or "athrú".
Seoladh athraithe saincheaptha
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Má úsáidtear an táilletacachumas is féidir idirbheart a sheoladh a thógfaidh roinnt uaireanta nó laethanta (nó riamh) dearbhú. Smaoinigh ar do tháille a roghnú de láimh nó fan go mbeidh an slabhra iomlán bailíochtaithe agat.</translation>
    
YES - The translation uses "táilletacachumas" which appears to be a mistranslation of "fallbackfee". The correct translation for "fallbackfee" in this context would likely be "táille eisiach" or "táille chúltacach". Additionally, "bailíochtaithe" is not the most appropriate word for "validated" in this context; "bailíodh" or "críochnaithe" would be more suitable.

NO - Má úsáidtear an táille chúltacach is féidir idirbheart a sheoladh a thógfaidh roinnt uaireanta nó laethanta (nó riamh) dearbhú. Smaoinigh ar do tháille a roghnú de láimh nó fan go mbeidh an slabhra iomlán críochnaithe agat.
```

```
        <source>per kilobyte</source>
        <translation>in aghaidh an cilibheart</translation>
    
UNK_LANG
```

```
        <source>Recommended:</source>
        <translation>Molta:</translation>
    
YES
The translation is incorrect. The word "Molta" means "much" or "a lot" in Irish, while "Recommended" translates to "Molta" in Irish. However, the spelling is incorrect, it should be "Molta". The provided translation also misses the context of "Recommended" as a suggestion. A more appropriate translation would be "Molta" or "Snaidhmeadh".

Molta:
```

```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
YES, The translation of "change" to "sóinseáil" is incorrect. In the context of Bitcoin, "change" refers to the remaining amount of Bitcoin after a transaction. The correct Irish word for this is "íocaíocht" or "athrú." Additionally, "cóipeáíl" is a gerund form and might sound a bit awkward here. A more natural translation would use the imperative form.
Correct translation: Cóipeáil íocaíocht
```

```
        <source>%1 (%2 blocks)</source>
        <translation>%1 (%2 bloic)</translation>
    
YES: The translation contains a spelling error. The word "blocks" is mistranslated as "bloic".
Correct translation: %1 (%2 blocks)
```

```
        <source>%1 to '%2'</source>
        <translation>%1 go '%2'</translation>
    
YES, The translation is inaccurate. The word "go" is not the correct translation for "to" in this context. The correct translation of "to" in this context would be "go dtí".
%1 go dtí '%2'
```

```
        <source>%1 to %2</source>
        <translation>%1 go %2</translation>
    
YES
The translation uses "go" which is not appropriate in this context. The correct translation should be "%1 go dtí %2" or "%1 go %2". The current translation is problematic as it could be misinterpreted.
%1 go dtí %2
```

```
        <source>PSBT saved</source>
        <extracomment>Popup message when a PSBT has been saved to a file</extracomment>
        <translation>IBSP sábháilte</translation>
    
YES - The translation is incorrect and does not convey the meaning of the original English text. It seems to be a direct transliteration of "PSBT" into "IBSP", which is not a valid Irish word or concept.

The correct translation should convey that a Partially Signed Bitcoin Transaction (PSBT) has been saved.

Correct translation: PSBT sábháilte
```

```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>Níl comhartha chuig Athchuir-Le-Táille, BIP-125</translation>
    
YES, The translation is incorrect. The correct translation of "Not signalling Replace-By-Fee, BIP-125." to Irish (Gaeilge) is "Ní ag comharthaíocht Athchuir-Le-Táille, BIP-125."
```

```
        <source>Warning: Unknown change address</source>
        <translation>Rabhadh: Seoladh sóinseáil anaithnid</translation>
    
YES, The translation is problematic because "seoladh sóinseáil" translates to "tampering address" or "adulteration address" instead of "change address". The correct translation for "change address" in the context of Bitcoin is "seoladh malairt" or "seoladh athrú".

NO
```

```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Cuir isteach seoladh an ghlacadóra, teachtaireacht  (déan cinnte go gcóipeálann tú bristeacha líne, spásanna, táib, srl. go díreach) agus sínigh thíos chun an teachtaireacht a fhíorú. Bí cúramach gan níos mó a léamh isteach sa síniú ná mar atá sa teachtaireacht sínithe féin, ionas nach dtarlóidh ionsaí socadáin duit. Tabhair faoi deara nach gcruthóidh sé seo ach go bhfaigheann an páirtí sínithe leis an seoladh, ní féidir leis seolta aon idirbhirt a chruthú!</translation>
    
YES, The translation incorrectly uses "socadáin" which means "sedatives" or "tranquilizers" instead of "man-in-the-middle attack". The word "socadáin" is also misspelled; it should be "socadán". The correct translation for "man-in-the-middle attack" in this context would be "ionsaí idir-ghníomhach" or "ionsaí idir-ghabhála". Also, the translation omits the hyphen in "man-in-the-middle".

NO, this translation is problematic. The word "socadáin" (sedatives/tranquilizers) is an incorrect translation for "man-in-the-middle attack". The correct translation would be "ionsaí idirghabhála" or "ionsaí idirghníomhach". Additionally, the hyphen in "man-in-the-middle" is missing in the translation.

The correct translation is: Cuir isteach seoladh an ghlacadóra, teachtaireacht (déan cinnte go gcóipeálann tú bristeacha líne, spásanna, táib, srl. go díreach) agus sínigh thíos chun an teachtaireacht a fhíorú. Bí cúramach gan níos mó a léamh isteach sa síniú ná mar atá sa teachtaireacht sínithe féin, chun nach gcaillfidh tú ionsaí idirghabhála ort. Tabhair faoi deara nach gcruthóidh sé seo ach go bhfaigheann an páirtí sínithe leis an seoladh, ní féidir leis seolta aon idirbhirt a chruthú!
```

```
        <source>Message signing failed.</source>
        <translation>Theip ar shíniú teachtaireachtaí.</translation>
    
YES, the translation is incorrect. The word "Theip" does not appear to be a valid Irish word. The correct translation should be "Theipigh ar shíniú na teachtaireachta.".
Theipigh ar shíniú na teachtaireachta.
```

```
        <source>Message verification failed.</source>
        <translation>Theip ar fhíorú teachtaireachta.</translation>
    
YES - The translation is incorrect. The correct translation of "Message verification failed." into Irish (Gaeilge) is "Theip ar fhíorú an teachtaireacht." The word "ar" before "fhíorú" is incorrect; it should be "an" to mean "the message".
Theip ar fhíorú an teachtaireacht.
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/neamhdheimhnithe</translation>
    
YES, The translation is incorrect. The word "neamhdheimhnithe" means "unconfirmed". The English source text "%1/unconfirmed" means that the transaction has at least one confirmation but less than six. Therefore, the translation should reflect this partial confirmation status.
%1/neamhdheimhnithe
```

```
        <source>Generated</source>
        <translation>Ghinte</translation>
    
YES: The word "Ghinte" is not a recognized word in the Irish language. The correct translation of "Generated" in this context is likely "Ginte".
Ghinte
```

```
        <source>Transaction ID</source>
        <translation>Aitheantas Idirbheart</translation>
    
YES, The translation is problematic. The word "Aitheantas" translates to "identity" or "recognition" in English, not "ID" or "identifier". In the context of Bitcoin, "Transaction ID" is a unique identifier for a transaction. A more accurate translation would be "Aitheantas Comhartha" or "IDanna Idirbheart".
NO
```

```
        <source>Details for %1</source>
        <translation>Sonraí do %1</translation>
    
UNK_LANG
```

```
        <source>Copy transaction ID</source>
        <translation>Cóipeáil idirbheart ID</translation>
    
YES, The translation is problematic as "Copier transaction ID" is not grammatically correct in Irish. The correct way to say "Copy transaction ID" is "Cóipeáil an ID d'idirbheart".
The original translation "Cóipeáil idirbheart ID" is a direct word-for-word translation which does not follow the grammatical structure of the Irish language.
The correct translation is: Cóipeáil an ID d'idirbheart
```

```
        <source>Copy raw transaction</source>
        <translation>Cóipeáil amh-idirbheart</translation>
    
YES: The translation of "transaction" to "idirbheart" is incorrect. "Idirbheart" means "transaction" in a general sense, but in the context of Bitcoin, the more appropriate term is "idirbheart cripte" or "idirbheart bitcoin." Additionally, "amh-idirbheart" is not a standard term. A more accurate translation would be "Cóipeáil an t-idirbheart amh."
Cóipeáil an t-idirbheart amh.
```

```
        <source>Copy full transaction details</source>
        <translation>Cóipeáil idirbheart agus sonraí iomlána</translation>
    
YES, The translation does not accurately convey the meaning of the source text. "Cóipeáil idirbheart agus sonraí iomlána" translates to "Copy transaction and full details", which is not the same as "Copy full transaction details".

The correct translation should be:
Cóipeáil sonraí iomlána an idirbhirt
```

```
        <source>Increase transaction fee</source>
        <translation>Méadaigh idirbheart  táille</translation>
    
YES, the translation is problematic due to word order. The word "idirbheart" should precede "táille".

The correct translation is: Méadaigh táille idirbheart
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
YES - The translation incorrectly translates "Comma separated file" as "Comhad athróige camógdheighilte" which means "Comma-separated change file". The correct translation for "Comma separated file" in Irish is "Comhad camógdheighilte".
Comhad camógdheighilte
```

```
        <source>Watch-only</source>
        <translation>Faire-amháin</translation>
    
YES, The translation is incorrect. The word "amháin" means "only" in Irish, but "faire" does not mean "watch". The correct translation of "Watch-only" in the context of Bitcoin would be "Faire uair amháin", which translates to "watch once" or "watch only". However, a more idiomatic and accurate translation would be "Ní féidir faire amháin", which translates to "Cannot watch only". 

Here's the correct translation:
<translation>Ní féidir faire amháin</translation>
```

```
        <source>Exporting Failed</source>
        <translation>Theip ar Easpórtáil</translation>
    
YES, The provided translation for "Exporting Failed" into Irish ('ga') is grammatically incorrect and does not accurately convey the intended meaning. The word "Theip" is the past tense of "teip" (fail), which is correct, but "ar Easpórtáil" (on export) is not the standard way to express "exporting" as a gerund or present participle in this context. A more accurate and natural translation would be "Theip ar Easpórtáil" or "Rinneadh Teip ar Easpórtáil".

The correct translation should be:
Theip ar Easpórtáil
```

```
        <source>Unable to decode PSBT from clipboard (invalid base64)</source>
        <translation>Ní féidir IBSP a dhíchódú ón ghearrthaisce (Bun64 neamhbhailí)</translation>
    
YES, The translation incorrectly translates "PSBT" as "IBSP".
Ní féidir PSBT a dhíchódú ón ghearrthaisce (Bun64 neamhbhailí)
```

```
        <source>Unable to decode PSBT</source>
        <translation>Ní féidir díchódú IBSP</translation>
    
YES, the translation is problematic. The term "PSBT" is an acronym that should ideally be kept as is or have a very specific translation if one exists and is common in the context of Bitcoin in the target language. Directly translating it as "IBSP" is likely incorrect and could be confusing.

NO
```

```
        <source>Increasing transaction fee failed</source>
        <translation>Theip ar méadú táille idirbhirt</translation>
    
YES: The translation is grammatically incorrect and does not convey the intended meaning. The word "Theip" is likely a misspelling or an incorrect word choice. The phrase "ar méadú táille idirbhirt" translates to "on increasing transaction fee" which is not a complete sentence and lacks the subject "Increasing transaction fee".

Correct translation: Níor éirigh leis an táille idirbhirt a mhéadú
```

```
        <source>PSBT copied</source>
        <translation>IBSP cóipeáilte</translation>
    
YES
The translation uses the incorrect case for the acronym "PSBT". The correct translation should be "PSBT cóipeáilte".
PSBT cóipeáilte
```

```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>Cóipeáil PSBT bump táille chuig an ngearrthaisce</translation>
    
YES, The provided translation is problematic due to being in Vietnamese and not Irish (ga).
Correct translation: "Cóipeáladh PSBT borradh an táille chuig an ngearrthaisce"
```

```
        <source>Backup Failed</source>
        <translation>Theip ar cúltacú</translation>
    
YES, The translation is inaccurate. The correct translation for "Backup Failed" in Irish is "Theip ar chúltacú". The provided translation is "Theip ar cúltacú" which is not correct. The phrase should be "Theip ar chúltacú".
The correct translation should be:
Theip ar chúltacú
```

```
        <source>%s corrupt. Try using the wallet tool bitcoin-wallet to salvage or restoring a backup.</source>
        <translation>Tá %s truaillithe. Triail an uirlis sparán bitcoin-wallet a úsáid chun tharrtháil nó chun cúltaca a athbhunú.</translation>
    
YES, The translation is not entirely accurate and uses an uncommon word for "salvage". A more natural and accurate translation would be:

YES, Tá %s truaillithe. Bain triail as an uirlis sparán bitcoin-wallet a úsáid chun é a shábháil nó chun cúltaca a athbhunú.
```

```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>Theip ar %s an staid snapshot -assumeutxo a bhailíochtú. Léiríonn sé seo fadhb crua-earraí, nó fabht sna bogearraí, nó droch-mhodhnú bogearraí a cheadaigh pictiúr neamhbhailí a luchtú. Mar thoradh air seo, stopfar an nód agus stopfaidh sé de úsáid a bhaint as staid ar bith a tógadh ar an seat, ag athshocrú airde an tslabhra ó%dgo%d. Ar an gcéad atosú eile, athchromfar ar an nód ag sioncronú ó %d gan úsáid a bhaint as sonraí seat. Tuairiscigh an teagmhas seo do %s lena n-áirítear conas a fuair tú an pictiúr. Fágfar an slabhrashlabhra neamhbhailí ar an diosca ar eagla go mbeadh sé ina chuidiú leis an tsaincheist ba chúis leis an earráid seo a dhiagnóisiú.</translation>
    
YES, the translation contains a repeated word "slabhrashlabhra" which is an error. Also, the phrase "pictiúr neamhbhailí" for "invalid snapshot" is not ideal. A better translation would be "staid dhíobhálach" or "staid neamhbhailí". The format specifiers are correctly transferred.
The correct translation is:
Theip ar %s an staid snapshot -assumeutxo a bhailíochtú. Léiríonn sé seo fadhb crua-earraí, nó fabht sna bogearraí, nó droch-mhodhnú bogearraí a cheadaigh staid neamhbhailí a luchtú. Mar thoradh air seo, stopfar an nód agus stopfaidh sé de úsáid a bhaint as aon staid a tógadh ar an seat, ag athshocrú airde an tslabhra ó %d go %d. Ar an gcéad atosú eile, athchromfar ar an nód ag sioncronú ó %d gan úsáid a bhaint as sonraí seat. Tuairiscigh an teagmhas seo do %s lena n-áirítear conas a fuair tú an seat. Fágfar an chainstate neamhbhailí ar an diosca ar eagla go mbeadh sé ina chuidiú leis an tsaincheist ba chúis leis an earráid seo a dhiagnóisiú.
```

```
        <source>Cannot downgrade wallet from version %i to version %i. Wallet version unchanged.</source>
        <translation>Ní féidir an sparán a íosghrádú ó leagan %igo leagan%i. Leagan sparán gan athrú.</translation>
    
YES, The translation incorrectly includes the format specifier %i within the word "leagan". The correct translation should place the format specifiers outside of any words.
Ní féidir an sparán a íosghrádú ó leagan %i go leagan %i. Leagan sparán gan athrú.
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>Ní féidir sparán scoilte neamh-HD a uasghrádú ó leagan%igo leagan%i gan uasghrádú chun tacú le heochrach réamh-scoilte. Úsáid leagan %i nó níl aon leagan sonraithe.</translation>
    
YES: The format specifiers (%i) are not correctly transferred to the translated text.
Ní féidir sparán scoilte neamh-HD a uasghrádú ó leagan %i go leagan %i gan uasghrádú chun tacú le heochrach réamh-scoilte. Úsáid leagan %i nó níl aon leagan sonraithe.
```

```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Earráid agus%s á léamh! Seans go bhfuil sonraí idirbhirt in easnamh nó mícheart. Sparán athscanadh.</translation>
    
YES: The translation is nonsensical and does not convey the meaning of the source text. It also introduces unrelated concepts like "unbalanced transaction" and "rescan wallet".

The correct translation should be:
Earráid: Níl taifead formáid Dumpfile ceart. Fuarthas "%s", bhí súil le "format".
```

```
        <source>Invalid value detected for '-wallet' or '-nowallet'. '-wallet' requires a string value, while '-nowallet' accepts only '1' to disable all wallets</source>
        <translation>Braitheadh ​​luach neamhbhailí le haghaidh '-wallet' nó '-nowallet'. Teastaíonn luach teaghrán le '-wallet', agus ní ghlacann '-nowallet' ach le '1' chun gach sparán a dhíchumasú</translation>
    
YES: The Irish word 'Braitheadh' is a misspelling of 'Braiteadh', which means 'detected'. The correct translation is: "Braiteadh luach neamhbhailí le haghaidh '-wallet' nó '-nowallet'. Teastaíonn luach teaghrán le '-wallet', agus ní ghlacann '-nowallet' ach le '1' chun gach sparán a dhíchumasú."
```

```
        <source>The transaction amount is too small to send after the fee has been deducted</source>
        <translation>Tá méid an idirbhirt ró-bheag le seoladh agus an táille asbhainte</translation>
    
YES, the translation is not entirely accurate. The phrase "the fee has been deducted" should be translated to "tar éis na táille a asbhaint" or "agus an táille asbhainte as" for better clarity and grammatical correctness.

NO
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Is é seo an táille idirbhirt a fhéadfaidh tú cuileáil má tá sóinseáil níos lú ná dusta ag an leibhéal seo</translation>
    
YES - The translation uses "cuileáil" which translates to "discard" or "throw away", but it should be "fágáil ar lár" or "a chur ar ceal" in this context. Also, "sóinseáil" is incorrect for "change" in the context of Bitcoin transactions; it should be "íocaíocht athraithe" or simply "athrú".

Correct translation: Is é seo an táille idirbhirt a fhéadfaidh tú fágáil ar lár má tá an t-athrú níos lú ná deannach ag an leibhéal seo.
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Leibhéal logála catagóir ar leith nach dtacaítear leis%11$s=%2$s. Bhíothas ag súil le %1$s=1:2. Catagóirí bailí: %3$s. Leibhéil loga bailí: %4$s.</translation>
    
YES: The translation incorrectly translates the format specifiers. The format specifiers '%1$s', '%2$s', '%3$s', and '%4$s' should remain unchanged. Also, the text "Expected %1$s=<category>:<loglevel>" is partially translated incorrectly as "Bhíothas ag súil le %1$s=1:2."
The correct translation should be: Leibhéal logála catagóir ar leith nach dtacaítear leis %1$s=%2$s. Bhíothas ag súil le %1$s=&lt;catagóir&gt;:&lt;leibhéal_logála&gt;. Catagóirí bailí: %3$s. Leibhéil loga bailí: %4$s.
```

```
        <source>Unsupported chainstate database format found. Please restart with -reindex-chainstate. This will rebuild the chainstate database.</source>
        <translation>Aimsíodh formáid bhunachar sonraí chainstáit nach dtacaítear léi. Atosaigh le -reindex-chainstate. Déanfaidh sé seo an bunachar sonraí slabhrach a atógáil.</translation>
    
YES - The translation of "chainstate database" as "bunachar sonraí slabhrach" is inaccurate and confusing in the context of Bitcoin. "Slabhrach" means "slavery" or "chain-like" but not in the context of a digital ledger. The correct term for "chainstate database" in a Bitcoin context would typically be left untranslated or a more technical term might be used if available in Irish Bitcoin terminology, but "slabhrach" is not appropriate.

Correct translation: Aimsíodh formáid bhunachar sonraí chainstáit nach dtacaítear léi. Atosaigh le -reindex-chainstate. Déanfaidh sé seo an bunachar sonraí chainstate a atógáil.
```

```
        <source>Cannot resolve -%s address: '%s'</source>
        <translation>Ní féidir réiteach seoladh -%s: '%s'</translation>
    
YES - The preposition "Ní féidir réiteach" is not standard and may cause confusion. The correct translation would be "Ní féidir seoladh -%s a réiteach: '%s'".

Ní féidir seoladh -%s a réiteach: '%s'
```

```
        <source>%s is set very high! Fees this large could be paid on a single transaction.</source>
        <translation>Tá%s socraithe an-ard! D’fhéadfaí táillí chomh mór seo a íoc ar idirbheart amháin.</translation>
    
YES, The format specifier "%s" should be preceded by a space.
%s is set very high! Fees this large could be paid on a single transaction.
Tá %s socraithe an-ard! D’fhéadfaí táillí chomh mór seo a íoc ar idirbheart amháin.
```

```
        <source>Error loading %s: External signer wallet being loaded without external signer support compiled</source>
        <translation>Earráid agus %s á lódáil: sparán an tsínitheora sheachtraigh á luchtú gan tacaíocht sínitheoir seachtrach a chur le chéile</translation>
    
YES, The translation is problematic. The phrase "tacaíocht sínitheoir seachtrach a chur le chéile" translates to "external signer support to compile" which is not accurate in context. It should be "external signer support compiled" or "compiled with external signer support".

NO
```

```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on enormous cluster of unconfirmed transactions.</source>
        <translation>Theip ar tháillí tuairte a ríomh, toisc go mbraitheann UTXOanna neamhdhearbhaithe ar bhraisle ollmhór idirbheart neamhdheimhnithe.</translation>
    
YES, The translation is problematic because of a mistranslation of "bump fees". The correct translation for "bump fees" in the context of Bitcoin transactions is "muirir tuairte" or "táillí tuairte". The provided translation used "tháillí tuairte" which is grammatically incorrect.

Theip ar tháillí tuairte a ríomh, toisc go mbraitheann UTXOanna neamhdhearbhaithe ar bhraisle ollmhór idirbheart neamhdheimhnithe.
```

```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>Theip ar bhaint an tsainstáit seat seat (%s). Bain de láimh é roimh atosú.</translation>
    
YES: The translation is not accurate and contains errors. The word "tsainstáit" appears to be a misspelling or an invented word, and the phrase "seat seat" is redundant.

Correct translation: Theip ar bhaint an limistéir sainstáit seat (%s). Bain de láimh é roimh atosú.
```

```
        <source>Failed to rename invalid peers.dat file. Please move or delete it and try again.</source>
        <translation>Theip ar an gcomhad peers.dat neamhbhailí a athainmniú. Bog nó scrios é agus bain triail eile as.</translation>
    
YES - The translation is not accurate. "Theip ar" means "failed to" which is correct, but "Theip ar an gcomhad peers.dat neamhbhailí a athainmniú" directly translates to "Failed to rename the invalid peers.dat file" whereas the source states "Failed to rename invalid peers.dat file". The source also says "Please move or delete it and try again" which is translated as "Bog nó scrios é agus bain triail eile as." which is correct. The main issue is the inclusion of "an" before "gcomhad" which translates to "the file" and is not present in the source.

Correct translation: Theip ar chomhad neamhbhailí peers.dat a athainmniú. Bog nó scrios é agus bain triail eile as.
```

```
        <source>Fee estimation failed. Fallbackfee is disabled. Wait a few blocks or enable %s.</source>
        <translation>Theip ar mheastachán na dtáillí. Tá fallbackfee díchumasaithe. Fan cúpla bloc nó cumasaigh %s.</translation>
    
YES: The translation is problematic because "Theip" is not a standard Irish word. It appears to be a misspelling or an invented word. The correct translation for "Fee estimation failed" would be "Teip ar mheastachán na dtáillí".

NO
```

```
        <source>Flushing undo file to disk failed. This is likely the result of an I/O error.</source>
        <translation>Theip ar shruthlú an chomhaid chealaigh go diosca. Is dócha gur earráid I/O é seo.</translation>
    
YES: The translation of "Flushing undo file to disk failed" is incorrect. "Theip ar shruthlú" translates to "flushing failed", but the word "shruthlú" means "to flow" or "to stream," not "to flush." The word "flush" in this context means to write buffered data to a storage device. A more accurate translation would be "Theip ar thaifeach" or "Theip ar fholmhú".
Theip ar thaifeach an chomhaid chealaigh go diosca. Is dócha gur earráid I/O é seo.
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>Méid neamhbhailí le haghaidh %s=1: '%s' (ní mór an táille sealaíochta nóiméad de %s a bheith ann ar a laghad chun idirbhearta bhfostú a chosc)</translation>
    
YES, The translation contains a mistranslation of the placeholder "%s=&lt;amount&gt;" to "%s=1". This should be left as is, without modification.

NO
```

```
        <source>Maximum transaction weight is less than transaction weight without inputs</source>
        <translation>Tá an t-uasmheáchan idirbhirt níos lú ná meáchan idirbhirt gan ionchuir</translation>
    
YES: The translation uses the word "uasmheáchan" which translates to "maximum weight" or "maximum burden". The correct translation for "maximum transaction weight" in the context of Bitcoin is "uasmheáchan idirbhirt". However, the translation incorrectly uses "uasmheáchan idirbhirt" for the first instance and "meáchan idirbhirt" for the second instance. The correct translation should be: "Tá uasmheáchan na hidirbheart níos lú ná meáchan na hidirbheart gan ionchuir".
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>Naisc amach teoranta do Tor (-onlynet=onion) ach ní thugtar an seachfhreastalaí chun líonra Tor a bhaint amach: ní thugtar aon seachfhreastalaí, -oinniún nó -listenonion</translation>
    
YES - The translation misses the last part of the source text, "-listenonion". The source text also uses "-proxy" as a general term for proxy, and the translation uses "seachfhreastalaí" which is a literal translation of proxy, but does not encompass the meaning of the source text's "-proxy" correctly. The translation should be: Naisc amach teoranta do Tor (-onlynet=onion) ach ní thugtar an seachfhreastalaí chun líonra Tor a bhaint amach: ní thugtar aon cheann de -proxy, -onion nó -listenonion.
```

```
        <source>Rename of '%s' -&gt; '%s' failed. Cannot clean up the background chainstate leveldb directory.</source>
        <translation>Theip ar athainmniú '%s' -&gt; '%s'. Ní féidir eolaire leveldb an tslabhra cúlra a ghlanadh.</translation>
    
YES, The translation is problematic. The first word 'Theip' is not a valid word in Irish. It seems to be a mistranslation or a typo. The correct translation should be 'Theip ar athainmniú' which is 'Renaming failed'.

Theip ar athainmniú '%s' -&gt; '%s'. Ní féidir eolaire leveldb an tslabhra cúlra a ghlanadh.
```

```
        <source>Specified -blockreservedweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Sáraíonn -blockreservedweight sonraithe (%d) níos mó ná meá uasta bloc comhdhearcadh (%d)</translation>
    
YES, The word "níos mó ná" is redundant. The correct translation is: "Sáraíonn -blockreservedweight sonraithe (%d) meá uasta bloc comhdhearcadh (%d)".
```

```
        <source>UTXO snapshot failed to validate. Restart to resume normal initial block download, or try loading a different snapshot.</source>
        <translation>Theip ar bhailíochtú a dhéanamh ar achomair UTXO. Atosaigh chun gnáthíoslódáil na mbloc tosaigh a atosú, nó bain triail as pictiúr eile a lódáil.</translation>
    
YES, the translation is problematic. The word "achomair" means "summary" or "brief," but it is not the correct term to use for a "snapshot" in this context. A more appropriate translation for "snapshot" in the context of blockchain data would be "pictiúr." Additionally, the phrase "bain triail as pictiúr eile a lódáil" is grammatically awkward and could be improved.

NO, the translation is problematic. The word "achomair" means "summary" or "brief," but it is not the correct term to use for a "snapshot" in this context. A more appropriate translation for "snapshot" in the context of blockchain data would be "pictiúr." Additionally, the phrase "bain triail as pictiúr eile a lódáil" is grammatically awkward and could be improved.

Correct translation: Theip ar bhailíochtú a dhéanamh ar phictiúr UTXO. Atosaigh chun gnáthíoslódáil na mbloc tosaigh a atosú, nó bain triail as pictiúr difriúil a lódáil.
```

```
        <source>Unconfirmed UTXOs are available, but spending them creates a chain of transactions that will be rejected by the mempool</source>
        <translation>Tá UTXOanna neamhdheimhnithe ar fáil, ach cruthaítear slabhra idirbheart a ndiúltóidh an mempool dóibh má dhéantar iad a chaitheamh</translation>
    
YES, The translation is problematic because it uses a literal translation for "spending them" ("má dhéantar iad a chaitheamh") which is awkward in Irish. A more natural phrasing would be "ach cuireann a gcaitheamh..." which translates to "but their spending...". The original translation also incorrectly omits the personal pronoun "you" implied in the English source, making the sentence slightly impersonal. The mempool does not reject transactions based on an external party's action, but rather based on the properties of the transaction itself.

Correct translation: Tá UTXOanna neamhdheimhnithe ar fáil, ach cuireann a gcaitheamh slabhra idirbheart ar bun a ndiúltóidh an mempool dóibh.
```

```
        <source>whitebind may only be used for incoming connections ("out" was passed)</source>
        <translation>ní féidir ceangaltán bán a úsáid ach amháin le haghaidh naisc isteach (ritheadh ​​​​"amach")</translation>
    
YES, The translation is problematic because it mistranslates "whitebind" as "ceangaltán bán" which means "white connection". In the context of Bitcoin, "whitebind" refers to a whitelist of IP addresses for incoming connections. The correct translation should reflect this technical meaning.

NO
```

```
        <source>Error creating %s</source>
        <translation>Earráid cruthaithe %s</translation>
    
YES, The translation is inaccurate. The English phrase "Error creating %s" means that there was a problem when attempting to create something. The Irish translation "Earráid cruthaithe %s" literally means "Error created %s" which implies that the error itself was created, rather than an error occurring during the creation process. The correct translation should reflect that an error occurred during the creation of "%s".

Correct translation: Earráid le linn cruthú %s
```

```
        <source>Error opening coins database</source>
        <translation>Earráid agus bunachar sonraí boinn á oscailt</translation>
    
YES, the translation is grammatically incorrect and does not accurately convey the meaning of the source text. The phrase "Earráid agus bunachar sonraí boinn á oscailt" literally translates to "Error and opening coins database", which is nonsensical in English and also in Irish in this context.

The correct translation should be: "Earráid agus bunachar sonraí na monaí á oscailt" or "Earráid agus bunachar sonraí na gcianacmhainní á oscailt" (if 'coins' is meant to be more abstract like digital assets). Given the Bitcoin context, "monaí" (coins) is more likely.

NO
```

```
        <source>Error: Got key that was not hex: %s</source>
        <translation>Earráid: Fuair ​​​​tú eochair nach heicsidheachúlach í: %s</translation>
    
YES: The word "fuair" in the translation is likely a typo or misinterpretation. It should be "fuarthas" to correctly convey "got" in this context.
Earráid: Fuarthas eochair nach heicsidheachúlach í: %s
```

```
        <source>Failed to connect best block (%s).</source>
        <translation>Theip ar nascadh an bhloc is fearr (%s).</translation>
    
YES, The translation is inaccurate. The Irish word "Theip" means "failed" or "escaped", but it is not used in the context of network connections. A more appropriate translation would be "Teip" which means "failure". The word "ar nascadh" is also incorrect, as it means "connected" and should be "ceangal" meaning "connection".

Correct translation: Theip ceangal leis an mbloc is fearr (%s).
```

```
        <source>Failed to disconnect block.</source>
        <translation>Theip ar dhínascadh an bhloc.</translation>
    
YES, The Irish translation is grammatically incorrect and does not convey the meaning of the English source text.
The correct translation should be: "Theip ar an nasc ón mbloc a dhíscaoileadh."
```

```
        <source>Failed to read block.</source>
        <translation>Theip ar léamh an bhloc.</translation>
    
YES, The translation is problematic. The Irish word "Theip" is not a standard Irish word. A more appropriate translation would use a verb like "Teip" (fail) or "Theipigh" (failed).

NO
```

```
        <source>Failed to rescan the wallet during initialization</source>
        <translation>Theip athscanadh ar an sparán le linn túsúchán</translation>
    
YES, The translation is inaccurate and uses an incorrect word for "rescan".
The correct translation is: Theip ar athscanadh an sparán le linn tosú.
```

```
        <source>Failed to start indexes, shutting down..</source>
        <translation>Theip ar thús a chur leis na hinnéacsanna, dúnadh.</translation>
    
YES, The translation is problematic. The verb "Theip" means "failed" but the phrase "Theip ar thús a chur leis na hinnéacsanna" translates to "Failed to put a start to the indexes" which is not idiomatic. The correct translation for "Failed to start indexes" would be "Theip ar thús na n-innéacsanna a chur". Additionally, "dúnadh" means "closing" and not "shutting down" in the context of a process. The correct translation for "shutting down" would be "ag dúnadh síos".
Theip ar thús na n-innéacsanna a chur, ag dúnadh síos..
```

```
        <source>Failed to verify database</source>
        <translation>Theip ar fhíorú an mbunachar sonraí</translation>
    
YES, The translation is grammatically incorrect and does not accurately convey the meaning of the source text. The word "Theip" is not a valid Irish word in this context. The correct translation should be "Teip ar bunachar sonraí a fhíorú".

Theip ar fhíorú an mbunachar sonraí
Teip ar bunachar sonraí a fhíorú
```

```
        <source>Failed to write block.</source>
        <translation>Theip ar scríobh an bhloc.</translation>
    
YES, The translation is inaccurate and uses a word that is likely a misspelling or a made-up word ("Theip"). The correct translation for "Failed to write block" in Irish, in the context of Bitcoin, would be:

Theip scríobh an bloc.
```

```
        <source>Failed to write to block index database.</source>
        <translation>Theip ar scríobh chuig an mbunachar sonraí innéacs bloc.</translation>
    
YES, the translation is problematic. The verb "Theip" is a misspelling of "Theip", and the phrase "an mbunachar sonraí innéacs bloc" is awkward. The correct translation should be "Theip ar scríobh chuig bunachar sonraí innéacs an bhloc."
NO. The translation is accurate and does not contain any unwanted content, erroneous content, or spam. The grammar and phrasing are correct in Irish.
```

```
        <source>Failed to write undo data.</source>
        <translation>Theip ar scríobh sonraí cealaigh.</translation>
    
YES, The word 'cealaigh' is a misspelling of 'cealaithe', which means 'cancelled' or 'erased' in Irish. The correct translation should be 'Theip ar scríobh sonraí cealaithe.'.
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>Bloc geineasas mícheart nó ní aimsithe. datadir mícheart don líonra?</translation>
    
YES, the translation contains a significant error. The word "genesis" has been translated literally as "geineasas," which is not a recognized or meaningful term in the context of Bitcoin or the Irish language. The correct term for "genesis block" in this context is "an chéad bhloc" or "an bhloc tosaigh."

NO
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>Méid neamhbhailí le haghaidh %s=1: '%s' (ar a laghad %s)</translation>
    
YES, The translation incorrectly translates "%s=&lt;amount&gt;" to "%s=1". The translation should be "Méid neamhbhailí le haghaidh %s=<amount>: '%s' (ar a laghad %s)".
Méid neamhbhailí le haghaidh %s=&lt;amount&gt;: '%s' (ar a laghad %s)
```

```
        <source>Listening for incoming connections failed (listen returned error %s)</source>
        <translation>Theip ar éisteacht le naisc isteach (éisteacht ar ais earráid %s)</translation>
    
YES: The translation is grammatically incorrect and does not convey the intended meaning. The word "Theip" is not a standard Irish word and seems to be a misspelling or made-up word. The phrase "éisteacht ar ais earráid" is also awkward and doesn't accurately translate "listen returned error".

Correct translation: Theip ar éisteacht le naisc isteach (dháiligh an t-éisteach earráid %s)
```

```
        <source>Prune cannot be configured with a negative value.</source>
        <translation>Ní féidir Bearradh a bheidh cumraithe le luach diúltach.</translation>
    
YES, The translation uses an incorrect verb form. The correct translation should be: "Ní féidir Prune a chumrú le luach diúltach."
```

```
        <source>Pruning blockstore…</source>
        <translation>Blocsiopa á bhearradh…</translation>
    
YES
The translation is problematic because the word "Blocsiopa" is not a standard or recognizable word in the Irish language (Gaeilge). It appears to be a neologism or a misspelling.

The correct translation for "Pruning blockstore" in the context of Bitcoin would likely involve terms related to data storage or a "blockstore" if there's a specific technical term used in Irish for it. Without more context or established Irish technical vocabulary for Bitcoin, a direct translation of "blockstore" might be difficult. However, a more direct and understandable approach would be to try and translate the concept.

Here's a more appropriate translation attempt:

"Pruning" can be translated as "á ghearradh" or "á choinneáil siar".
"Blockstore" is the tricky part. If it refers to the storage of blockchain blocks, a descriptive translation would be better.

Let's assume "blockstore" refers to the storage of blocks.

A more appropriate translation could be:

**Correct Translation:** "Stóras bloic á ghearradh…" or "Ag gearradh an stóir bloc…"
```

```
        <source>SQLiteDatabase: Failed to execute statement to verify database: %s</source>
        <translation>SQLiteDatabase: Theip ar rith ráiteas chun an bunachar sonraí a fhíorú: %s</translation>
    
YES, The translation incorrectly uses the Irish word "Theip" which means "failed" but is not the correct word in this context. The correct word for "failed" in this context is "Teip".

SQLiteDatabase: Teip ar rith ráiteas chun an bunachar sonraí a fhíorú: %s
```

```
        <source>SQLiteDatabase: Failed to prepare statement to verify database: %s</source>
        <translation>SQLiteDatabase: Theip ar ullmhú ráiteas chun bunachar sonraí: %s a fhíorú</translation>
    
YES, the translation is problematic. The word "Theip" is not a standard English word and appears to be a misspelling or an invented word. It should likely be "The attempt" or "The statement" in this context.

NO
```

```
        <source>SQLiteDatabase: Failed to read database verification error: %s</source>
        <translation>SQLiteDatabase: Theip ar léamh earráid fíorú bunachar sonraí: %s</translation>
    
YES: The translation is problematic because the Irish word "Theip" is not a recognized word and appears to be a mistranslation. The correct translation for "Failed to read" in this context would be "Theip an léamh" or "Theip bunachar sonraí".

Correct translation: SQLiteDatabase: Theip an léamh earráid fíorú bunachar sonraí: %s
```

```
        <source>Signing transaction failed</source>
        <translation>Theip ar síniú idirbheart</translation>
    
YES, The translation is problematic as it is not a direct translation of the source text. The source text "Signing transaction failed" implies a failure in the process of signing a transaction. The provided translation "Theip ar síniú idirbheart" translates to "The signing of the transaction failed", which is a grammatically correct and accurate translation. The original translation provided was "Theip ar síniú idirbheart".

Correct translation: Theip ar an idirbheart a shíniú
```

```
        <source>Specified -walletdir "%s" is a relative path</source>
        <translation>Is cosán spleách é -walletdir "%s" sonraithe</translation>
    
YES - The word order in the Irish translation is incorrect. The correct translation should be "Is cosán coibhneasta é an fillteán sparán sonraithe '%s'".
```

```
        <source>Unknown address type '%s'</source>
        <translation>Anaithnid cineál seoladh '%s'</translation>
    
YES - The translation is incorrect. The word "Unknown" is translated as "Anaithnid" which is not a recognized word in Irish. The correct translation for "Unknown" is "Anaithnid" or "Idir", and the correct translation for "address" is "seoladh".
Correct translation: Anaithnid cineál seoladh '%s'
```

```
        <source>Unknown change type '%s'</source>
        <translation>Anaithnid cineál sóinseáil '%s'</translation>
    
YES - The translation uses "sóinseáil" which translates to "souling" or "sealing" in English. The correct translation for "change" in the context of Bitcoin would be "athrú" or "fágtha" (meaning remainder or leftover). The translation is also problematic as it is nonsensical in the given context.

Correct translation: Anaithnid cineál athraithe '%s'
```

```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>Rialacha nua anaithnid curtha i ngníomh (leagan giotán %ii)</translation>
    
YES, the translation is problematic because it inaccurately translates the format specifier '%i'. The source text has '%i', but the translation has '%ii', which is incorrect.

The correct translation should be:
Rialacha nua anaithnid curtha i ngníomh (leagan giotán %i)
```

```
        <source>Unrecognised option "%s" provided in -test=&lt;option&gt;.</source>
        <translation>Rogha neamhaitheanta "%s" curtha ar fáil i -test=1.</translation>
    
YES, the translation is problematic because the format specifier "%s" in the source text has been incorrectly translated to "1" in the target text. The correct translation should retain the format specifier.
Rogha neamhaitheanta "%s" curtha ar fáil i -test=&lt;option&gt;.
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>Theip ar chruthú comhaid sparán: %s</translation>
    
YES, The translation contains an erroneous word. "Theip" is not a recognized Irish word. It should be "Theipigh" or "Teip ar".

Theipigh ar chruthú comhaid sparán: %s
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Earráid: Níorbh fhéidir watch amháin tx %s a chur le sparán faire amháin</translation>
    
YES, The translation is problematic as it is not accurate and uses literal translations for technical terms. "watchonly tx" should be translated as "idirbheart faire amháin". "watchonly wallet" should be translated as "sparán faire amháin".
Correct translation: Earráid: Níorbh fhéidir idirbheart faire amháin %s a chur le sparán faire amháin
```

```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>Tá carachtair neamhshábháilte i nóta tráchta (%s) Gníomhaire Úsáideora.</translation>
    
YES - The word order in the translation is unnatural. The correct translation should be: "Tá carachtair neamhshábháilte sa trácht ar ghníomhaire úsáideora (%s)."
```
</details>
