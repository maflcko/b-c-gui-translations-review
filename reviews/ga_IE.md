# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ga_IE</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bga_IE%5D%20low%20quality)


```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
YES, The translation is problematic because "athróige" means "change" in the context of money, not "separated". The correct translation for "Comma separated file" in Irish is "Comhad deighilte le camóga".
Comhad deighilte le camóga
```

```
        <source>Passphrase change failed</source>
        <translation>Theip ar athrú pasfhocail</translation>
    
YES, The translation is not accurate and the word order is incorrect. The correct translation should be "Teip ar athrú pasfhocail".
```

```
        <source>IP/Netmask</source>
        <translation>PI/Mascadhidirlíon</translation>
    
YES
The translation contains an unsupported character 'í'.
PI/Mascadhidirlíon
```

```
        <source>%1 d</source>
        <translation>%1 l</translation>
    
YES. The 'd' in the source text represents days and is a common abbreviation. The translation uses 'l' which is not a standard abbreviation for days in Irish.

NO
```

```
        <source>%1 m</source>
        <translation>%1 n</translation>
    
YES, The translation is incorrect. The letter 'm' in the source text should not be translated to 'n' in the target text as this changes the meaning of the word. The letter 'm' is likely a placeholder for a number.
%1 m
```

```
        <source>Encrypt Wallet…</source>
        <translation>Criptigh Sparán…</translation>
    
YES, the translation is problematic. The word "Criptigh" means "Encrypt" but the rest of the sentence is not correctly translated. The correct translation for "Encrypt Wallet…" in Irish (ga_IE) is "Criptigh an Sparán…" or "Criptigh Do Sparán…".

NO
```

```
        <source>Processing blocks on disk…</source>
        <translation>Bloic ar diosca á bpróiseáil…</translation>
    
YES, the translation is problematic. The verb "bpróiseáil" is not a standard Irish word. The correct term for "processing" in Irish is usually "próiseáil" or "ag próiseáil". The context suggests a present participle.

NO
```

```
        <source>Show the list of used sending addresses and labels</source>
        <translation>Taispeáin an liosta de seoltaí seoladh úsáidte agus na lipéid </translation>
    
YES, The translation is problematic because of a grammatical error. The noun "seoltaí" (addresses) should be in the genitive plural form to agree with "seoladh" (sending). The correct form is "seoltaí seolta". Additionally, "lipéid" should be in the genitive plural form "lipéidí" to agree with "na" (the).

Taispeáin an liosta de sheoltaí seolta úsáidte agus na lipéidí
```

```
        <source>Sending addresses</source>
        <translation>Seoltaí seoladh</translation>
    
YES, The translation is incorrect and does not accurately reflect the source text. "Seoltaí seoladh" translates to "sending addresses," but it appears to be a literal and awkward phrasing in Irish. The term "address" in the context of Bitcoin should be translated as "seoladh" and the plural as "seoltaí".

NO
```

```
        <source>%1 client</source>
        <translation>%1 cliaint</translation>
    
YES: The translation has a misspelling in the word "client". The correct spelling in Irish is "cliant".
%1 cliant
```

```
        <source>Show</source>
        <translation>Sconas</translation>
    
YES, The translation is incorrect and conveys the opposite meaning. The English word "Show" translates to "Taispeáin" in Irish, while "Sconas" means "Hide".
Sconas
```

```
        <source>Error creating wallet</source>
        <translation>Earráid agus sparán á chruthú</translation>
    
YES, the translation is erroneous. The word "and" (agus) is incorrectly inserted in the translation. The correct translation should be "Earráid ag cruthú sparán".

NO
```

```
        <source>Change:</source>
        <translation>Sóinseáil:</translation>
    
YES
The translation is incorrect. "Sóinseáil" means "tickle" or "itch" in Irish. The correct translation for "Change" in the context of Bitcoin transactions would be "Athrú".

Change: Athrú:
```

```
        <source>(un)select all</source>
        <translation>(neamh)roghnaigh gach rud </translation>
    
YES, The translation is problematic because it does not accurately reflect the meaning of the English source text, particularly in the context of Bitcoin. The Irish translation "roghnaigh gach rud" means "select everything", but the English "(un)select all" implies a toggle functionality where selecting all can be undone by unselecting all. The translation omits the "un" part of the phrase.

(un)roghnaigh gach ceann
```

```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
YES, The translation of "change" as "sóinseáil" is incorrect in the context of Bitcoin transactions. "Change" in Bitcoin refers to the leftover amount returned to the sender after a transaction. The correct word in Irish for this context is "tilleadh" or "aisíoc".
Cóipeáil tilleadh
```

```
        <source>(%1 locked)</source>
        <translation>(%1 glasáilte)</translation>
    
YES, The translation is problematic because the Irish word "glasáilte" means "locked" in the sense of being secured or shut. In the context of Bitcoin, when an amount is "locked," it typically refers to it being unavailable for use or being held in a transaction. The word "glasáilte" does not accurately convey this meaning.

A more appropriate translation for "locked" in this context would be "curtha i leataobh" which translates to "set aside" or "held back."

Correct translation: (%1 curtha i leataobh)
```

```
        <source>change from %1 (%2)</source>
        <translation>sóinseáil ó %1 (%2)</translation>
    
YES, The translation uses the word "sóinseáil" which means "worry" or "concern". The correct translation for "change" in the context of Bitcoin transactions (money returned) would be "aisíoc" or "íocaíocht a thabhairt ar ais". The format specifiers are correctly transferred.

YES, sóinseáil ó %1 (%2)
aisíoc ó %1 (%2)
```

```
        <source>(change)</source>
        <translation>(sóinseáil)</translation>
    
YES, The translation for "(change)" to Irish (ga_IE) is incorrect in the context of Bitcoin. The word "sóinseáil" means "editing" or "redaction". In the context of Bitcoin transactions, "change" refers to the leftover amount of cryptocurrency returned to the sender. The correct Irish word for this is "torthaí" (returns) or "athrú" (change, in a more general sense but acceptable here).

(athrú)
```

```
        <source>Create wallet failed</source>
        <translation>Theip ar chruthú sparán</translation>
    
YES, The translation uses an incorrect verb and word order. The correct translation should be "Theip ar sparán a chruthú".
```

```
        <source>Open wallet failed</source>
        <translation>Theip ar oscail sparán</translation>
    
YES - The translation uses a past tense verb "Theip ar oscail" ("opened") which does not accurately reflect the present tense imperative "Open" in the source text. The correct translation should be in the present tense imperative form.

NO
```

```
        <source>Restore wallet failed</source>
        <extracomment>Title of message box which is displayed when the wallet could not be restored.</extracomment>
        <translation>Theip ar athchóiriú an sparán</translation>
    
YES - The translation is grammatically incorrect and uses the wrong verb form. The correct translation should be "Theip ar an sparán a athchóiriú". The word "theip" should be followed by "ar" and then the noun. Also, "athchóiriú an sparán" should be "an sparán a athchóiriú" to indicate that the wallet is the object of the verb.

Theip ar an sparán a athchóiriú
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>An seoladh chomhcheangailte leis an iontráil liosta seoltaí seo. Ní féidir é seo a mionathraithe ach do seoltaí seoladh.</translation>
    
YES - The word "seoladh" is repeated unnecessarily in the translation. The correct translation is: "An seoladh comhcheangailte leis an iontráil liosta seoltaí seo. Ní féidir é seo a mionathraithe ach do sheoltaí seolta."
```

```
        <source>New sending address</source>
        <translation>Seoladh nua seoladh</translation>
    
YES, The translation is erroneous. The word "seoladh" is repeated unnecessarily and the meaning of "sending address" is not accurately conveyed.

NO
```

```
        <source>Edit sending address</source>
        <translation>Eagarthóireacht seoladh seoladh</translation>
    
YES, The translation is erroneous. The word "seoladh" (address) is repeated unnecessarily.
Eagarthóireacht seoladh seolta
```

```
        <source>Limit block chain storage to</source>
        <translation>Teorainn a chur le blocshlabhra stórála go</translation>
    
YES - The translation is grammatically incorrect and awkward. The intended meaning is to set a limit on blockchain storage.

Correct translation: Teorainn a chur le stóráil an bhlocshlabhra go dtí
```

```
        <source>Estimated time left until synced</source>
        <translation>Measta am fágtha go dtí sioncrónaithe</translation>
    
UNK_LANG
```

```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>Tá %1 ag sioncronú faoi láthair. Déanfaidh sé é a íoslódáil agus a fíorú ar ceanntásca agus bloic ó phiaraí go dtí barr an blocshlabhra.</translation>
    
YES - The translation uses "é" ("it") to refer to the syncing process, which is grammatically incorrect and makes the sentence confusing. Additionally, it incorrectly translates "download headers and blocks" as "íoslódáil agus a fíorú ar ceanntásca agus bloic" which translates to "download and verify on headers and blocks". The correct translation should be "íoslódáil ceanntásca agus bloic" ("download headers and blocks").

Correct translation: Tá %1 ag sioncronú faoi láthair. Íoslódálfaidh sé ceanntásca agus bloic ó phiaraí agus fíoróidh sé iad go dtí barr an blocshlabhra.
```

```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>Cibé an táille a dhealú ón méid a shocrú mar réamhshocrú nó nach bhfuil.</translation>
    
YES - The translation uses "táille" which translates to "fee" in English. However, the source text uses "subtract fee from amount", and the translation is "deduct the fee from the amount". This creates a misunderstanding as it implies that the fee is being deducted from the amount sent, rather than the amount itself being reduced to account for the fee. A more accurate translation would be "Cibé an dtabharfar an táille as an méid mar réamhshocrú nó nach bhfuil."
```

```
        <source>Whether to show coin control features or not.</source>
        <translation>Gnéithe rialúchán bonn a thaispeáint nó nach.</translation>
    
YES - The translation is grammatically incorrect. The verb "taispeáint" should be in the infinitive form "a thaispeáint" and the sentence structure is awkward. A more natural translation would be:

"An taispeántar gnéithe rialúchán bonn nó nach ndéantar."
```

```
        <source>This change would require a client restart.</source>
        <translation>Theastódh cliant a atosú leis an athrú seo.</translation>
    
YES, The Irish translation uses archaic vocabulary and word order that is not standard for modern Irish. The word 'Theastódh' is a less common past tense form of 'is gá' (is needed/required) and the word order is also unusual.

A more natural and standard translation would be:

YES, This change would require a client restart.
Theastódh an t-athrú seo go n-atosófaí an cliant.
```

```
        <source>Broadcast Tx</source>
        <translation>Craol Tx</translation>
    
YES, The translation is problematic because "Craol Tx" is not a valid or meaningful translation of "Broadcast Tx" in the context of Bitcoin. The correct term for broadcasting a transaction in Irish is "Craoltóireacht Idirlíne" or more specifically, "Craoladh idirbheart".

NO
```

```
        <source>Failed to load transaction: %1</source>
        <translation>Theip ar lódáil idirbheart: %1</translation>
    
YES - The translation contains a misspelling. "Theip" should be "Theip". The correct translation is: "Theip ar lódáil idirbheart: %1"
```

```
        <source>PSBT copied to clipboard.</source>
        <translation>Cóipeáladh IBSP chuig an gearrthaisce.</translation>
    
YES, The translation uses the incorrect acronym "IBSP" instead of "PSBT".
Cóipeáladh PSBT chuig an gearrthaisce.
```

```
        <source>Mapped AS</source>
        <translation>CU Mapáilte</translation>
    
YES, the translation is problematic because "CU Mapáilte" is not a correct translation of "Mapped AS" in the context of Bitcoin. "AS" likely refers to Autonomous System, which is a concept in internet routing, not directly related to Bitcoin in this common phrasing. Without further context about what "Mapped AS" specifically refers to in this Bitcoin context, a direct translation is difficult and potentially misleading. If "AS" is intended to be "Address", then the translation is still incorrect. Assuming "AS" is a typo for "Address", the translation should be something like "Seoladh Mapáilte".

CU Mapáilte
```

```
        <source>detecting: peer could be v1 or v2</source>
        <extracomment>Explanatory text for "detecting" transport type.</extracomment>
        <translation>bhrath: d’fhéadfadh v1 nó v2 a bheith i gcomhghleacaí</translation>
    
YES - The translation is inaccurate. The word "bhrath" means "betray" or "deceive" in Irish, which is not relevant to the context of detecting a peer type. The correct translation should be something like "á bhrath" meaning "detecting" or "á aimsiú" meaning "finding".

Corrected translation: á bhrath: d’fhéadfadh v1 nó v2 a bheith i gcomhghleacaí
```

```
        <source>Change:</source>
        <translation>Sóinseáil:</translation>
    
YES
The translation is incorrect. "Sóinseáil" means "tickle" or "itch" in Irish. The correct translation for "Change" in the context of Bitcoin transactions would be "Athrú".

Change: Athrú:
```

```
        <source>Custom change address</source>
        <translation>Seoladh sóinseáil saincheaptha</translation>
    
YES, the translation is problematic. The word "sóinseáil" translates to "farming" or "cultivation" in English, which is not related to the Bitcoin context of "change" referring to transaction change.

NO
```

```
        <source>per kilobyte</source>
        <translation>in aghaidh an cilibheart</translation>
    
YES, The word "kilobyte" is mistranslated. The correct translation for "kilobyte" is "cilefocal" or "cilibyte". The translation also uses "in aghaidh an" which is not the correct phrasing for "per". The correct phrasing is "in aghaidh gach".

NO
```

```
        <source>Recommended:</source>
        <translation>Molta:</translation>
    
YES, The translation of "Recommended:" to "Molta:" is incorrect. "Molta" means "much" or "many" in Irish. The correct translation for "Recommended:" in this context would be "Molta:" or "Snaidhme":
NO
```

```
        <source>Clear All</source>
        <translation>Glan Gach</translation>
    
YES, the translation is inaccurate and uses the wrong word for "all." The correct translation should be "Glan Gach Uile" or "Glan Gach Ceann."

NO
Glan Gach Uile
```

```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
YES, The translation of "change" as "sóinseáil" is incorrect in the context of Bitcoin transactions. "Change" in Bitcoin refers to the leftover amount returned to the sender after a transaction. The correct word in Irish for this context is "tilleadh" or "aisíoc".
Cóipeáil tilleadh
```

```
        <source>%1 (%2 blocks)</source>
        <translation>%1 (%2 bloic)</translation>
    
YES, the translation is erroneous. The word "bloic" is not a correct Irish word; it should be "bloic" as in "blocanna" for blocks.
NO
```

```
        <source>Sign failed</source>
        <translation>Theip ar an síniú</translation>
    
YES, the translation is problematic because it is not in the correct language. The language specified is 'ga_IE' which is Irish, but the translation is in Welsh.

NO
```

```
        <source>PSBT saved</source>
        <extracomment>Popup message when a PSBT has been saved to a file</extracomment>
        <translation>IBSP sábháilte</translation>
    
YES - The translation is incorrect and doesn't reflect the original meaning. The correct translation should be "PSBT sábháilte".
```

```
        <source>The total exceeds your balance when the %1 transaction fee is included.</source>
        <translation>Sáraíonn an t-iomlán d’iarmhéid nuair a chuirtear an táille idirbhirt %1 san áireamh.</translation>
    
YES - The word "Sáraíonn" translates to "exceeds" in English, but it should be "iomlán" which means "total". The word "iarmhéid" means "balance" and should be placed after "d'iomlán". The correct translation is: "An t-iomlán, nuair a chuirtear an táille idirbhirt %1 san áireamh, sáraíonn sé d'iarmhéid."
```

```
        <source>Warning: Unknown change address</source>
        <translation>Rabhadh: Seoladh sóinseáil anaithnid</translation>
    
YES, the translation contains an erroneous word. In the context of Bitcoin transactions, "change" refers to the remaining amount of Bitcoin returned to the sender. The word "sóinseáil" means "haggling" or "bargaining" and is not the correct term.

The correct translation should be:
Rabhadh: Seoladh athraithe anaithnid
```

```
        <source>Clear All</source>
        <translation>Glan Gach</translation>
    
YES, the translation is inaccurate and uses the wrong word for "all." The correct translation should be "Glan Gach Uile" or "Glan Gach Ceann."

NO
Glan Gach Uile
```

```
        <source>Message signing failed.</source>
        <translation>Theip ar shíniú teachtaireachtaí.</translation>
    
YES - The word 'theip' is not a recognized Irish word. The correct word should be 'Teip'. The 'ar' is also incorrect, it should be 'ar' to signify the action. The correct translation should be "Teipigh ar shíniú teachtaireachtaí."
```

```
        <source>Copy transaction ID</source>
        <translation>Cóipeáil idirbheart ID</translation>
    
YES, The translation is not entirely accurate and could be improved for clarity in the context of Bitcoin transactions. The word "idirbheart" is a direct translation of "transaction" but "cóip idirbheart" sounds a bit clunky. A more natural phrasing would be "Cóipeáil uimhir idirbhirt" or "Cóipeáil aitheantóir idirbhirt".

"Cóipeáil aitheantóir idirbhirt"
```

```
        <source>Increase transaction fee</source>
        <translation>Méadaigh idirbheart  táille</translation>
    
YES, The translation is problematic as it has an extra space between "idirbheart" and "táille".

NO
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
YES, The translation is problematic because "athróige" means "change" in the context of money, not "separated". The correct translation for "Comma separated file" in Irish is "Comhad deighilte le camóga".
Comhad deighilte le camóga
```

```
        <source>Unable to decode PSBT from clipboard (invalid base64)</source>
        <translation>Ní féidir IBSP a dhíchódú ón ghearrthaisce (Bun64 neamhbhailí)</translation>
    
YES - The translation contains an untranslatable acronym "PSBT" as "IBSP". It also uses "Bun64" for "base64", which is not a standard translation.

Correct translation: Ní féidir PSBT a dhíchódú ón ghearrthaisce (bunús64 neamhbhailí)
```

```
        <source>Unable to decode PSBT</source>
        <translation>Ní féidir díchódú IBSP</translation>
    
YES, The translation is incorrect. "PSBT" is a technical term and should not be translated. The correct translation should be "Ní féidir PSBT a dhíchódú".

Ní féidir PSBT a dhíchódú
```

```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>Cóipeáil PSBT bump táille chuig an ngearrthaisce</translation>
    
YES, The translation uses the Irish word 'bump' which is not a standard Irish word. The correct translation should be: Cóipeáil PSBT méadú táille chuig an ngearrthaisce
```

```
        <source>Backup Failed</source>
        <translation>Theip ar cúltacú</translation>
    
YES, The provided translation is problematic. The word "Theip" does not translate to "Backup" in Irish. A more accurate translation for "Backup Failed" would be "Theip ar chúltacú".

NO
```

```
        <source>%s corrupt. Try using the wallet tool bitcoin-wallet to salvage or restoring a backup.</source>
        <translation>Tá %s truaillithe. Triail an uirlis sparán bitcoin-wallet a úsáid chun tharrtháil nó chun cúltaca a athbhunú.</translation>
    
YES. The translation contains a grammatical error. The verb "triail" should be followed by "a" before the infinitive.

NO.
Tá %s truaillithe. Bain triail as an uirlis sparán bitcoin-wallet a úsáid chun tharrtháil nó chun cúltaca a athbhunú.
```

```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>Theip ar %s an staid snapshot -assumeutxo a bhailíochtú. Léiríonn sé seo fadhb crua-earraí, nó fabht sna bogearraí, nó droch-mhodhnú bogearraí a cheadaigh pictiúr neamhbhailí a luchtú. Mar thoradh air seo, stopfar an nód agus stopfaidh sé de úsáid a bhaint as staid ar bith a tógadh ar an seat, ag athshocrú airde an tslabhra ó%dgo%d. Ar an gcéad atosú eile, athchromfar ar an nód ag sioncronú ó %d gan úsáid a bhaint as sonraí seat. Tuairiscigh an teagmhas seo do %s lena n-áirítear conas a fuair tú an pictiúr. Fágfar an slabhrashlabhra neamhbhailí ar an diosca ar eagla go mbeadh sé ina chuidiú leis an tsaincheist ba chúis leis an earráid seo a dhiagnóisiú.</translation>
    
YES: The translation contains a literal translation of "snapshot" as "pictiúr" which is incorrect in this context. "Snapshot" in Bitcoin refers to a specific state of the blockchain data, not a picture. The correct term in Irish for this context would be "léargas" or "staid". Also, there is an incorrect repetition of "slabhra" in the last sentence.

Theip ar %s an staid snapshot -assumeutxo a bhailíochtú. Léiríonn sé seo fadhb crua-earraí, nó fabht sna bogearraí, nó droch-mhodhnú bogearraí a cheadaigh léargas neamhbhailí a luchtú. Mar thoradh air seo, stopfar an nód agus stopfaidh sé de úsáid a bhaint as staid ar bith a tógadh ar an léargas, ag athshocrú airde an tslabhra ó %d go %d. Ar an gcéad atosú eile, athchromfar ar an nód ag sioncronú ó %d gan úsáid a bhaint as sonraí léargais. Tuairiscigh an teagmhas seo do %s lena n-áirítear conas a fuair tú an léargas. Fágfar an slabhrashlabhra neamhbhailí ar an diosca ar eagla go mbeadh sé ina chuidiú leis an tsaincheist ba chúis leis an earráid seo a dhiagnóisiú.
```

```
        <source>Cannot downgrade wallet from version %i to version %i. Wallet version unchanged.</source>
        <translation>Ní féidir an sparán a íosghrádú ó leagan %igo leagan%i. Leagan sparán gan athrú.</translation>
    
YES, The translation incorrectly includes "%i" twice in the phrase "ó leagan %igo leagan%i". The correct translation should be "Ní féidir an sparán a íosghrádú ó leagan %i go leagan %i. Leagan sparán gan athrú."
```

```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Earráid agus%s á léamh! Seans go bhfuil sonraí idirbhirt in easnamh nó mícheart. Sparán athscanadh.</translation>
    
YES - The translation is nonsensical and does not match the source text. The source text is about a dumpfile format error, while the translation talks about reading data, missing or incorrect transaction data, and re-scanning a wallet. It also incorrectly places the format specifier within a word.

Correct translation: Earráid: Níl taifead formáid Dumpfile ceart. Fuarthas "%s", bhí súil le "format".
```

```
        <source>Invalid value detected for '-wallet' or '-nowallet'. '-wallet' requires a string value, while '-nowallet' accepts only '1' to disable all wallets</source>
        <translation>Braitheadh ​​luach neamhbhailí le haghaidh '-wallet' nó '-nowallet'. Teastaíonn luach teaghrán le '-wallet', agus ní ghlacann '-nowallet' ach le '1' chun gach sparán a dhíchumasú</translation>
    
YES: The Irish word "Braitheadh" is not a standard Irish word. The correct word would be "Braitheadh".

Correct Translation: Braitheadh luach neamhbhailí le haghaidh '-wallet' nó '-nowallet'. Teastaíonn luach teaghrán le '-wallet', agus ní ghlacann '-nowallet' ach le '1' chun gach sparán a dhíchumasú
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Is é seo an táille idirbhirt a fhéadfaidh tú cuileáil má tá sóinseáil níos lú ná dusta ag an leibhéal seo</translation>
    
YES: The word "cuileáil" is not a suitable translation for "discard" in this context. It means "to excrete" or "to void". A better translation would be "fág" (leave) or "caith ar shiúl" (throw away). The word "soinseáil" is also not the correct translation for "change" in the context of Bitcoin. It means "sophistication" or "trickery". The correct translation for "change" in this context would be "an t-athrú" or simply "táille ar ais" (return change).

NO
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Leibhéal logála catagóir ar leith nach dtacaítear leis %1$s=%2$s. Bhíothas ag súil le %1$s=1:2. Catagóirí bailí: %3$s. Leibhéil loga bailí: %4$s.</translation>
    
YES, The translation erroneously uses "1:2" for the expected format. The correct translation should reflect the placeholder for category and loglevel.
Leibhéal logála catagóir ar leith nach dtacaítear leis %1$s=%2$s. Bhíothas ag súil le %1$s=&lt;catagóir&gt;:&lt;leibhéal loga&gt;. Catagóirí bailí: %3$s. Leibhéil loga bailí: %4$s.
```

```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>Theip ar bhaint an tsainstáit seat seat (%s). Bain de láimh é roimh atosú.
</translation>
    
YES, The translation contains an extraneous word "seat" which means "seat" in Irish. The correct translation for "snapshot" in this context is "ga/ghabháil/tuairt".

Theip ar bhaint an t-ainm comhaid sechainstate (%s). Bain de láimh é roimh atosú.
```

```
        <source>Fee estimation failed. Fallbackfee is disabled. Wait a few blocks or enable %s.</source>
        <translation>Theip ar mheastachán na dtáillí. Tá fallbackfee díchumasaithe. Fan cúpla bloc nó cumasaigh %s.</translation>
    
YES - The translation contains erroneous content. The word "Theip" is not a valid Irish word. The correct translation of "Fee estimation failed" is "Teip ar mheastachán na dtáillí".

Theip ar mheastachán na dtáillí. Tá fallbackfee díchumasaithe. Fan cúpla bloc nó cumasaigh %s.
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>Naisc amach teoranta do Tor (-onlynet=onion) ach ní thugtar an seachfhreastalaí chun líonra Tor a bhaint amach: ní thugtar aon seachfhreastalaí, -oinniún nó -listenonion</translation>
    
YES - The translation uses the word "seachfhreastalaí" for "proxy" twice, but then incorrectly uses the same word for "onion". The correct translation for "onion" in this context is "oinnín".

NO
```

```
        <source>Rename of '%s' -&gt; '%s' failed. Cannot clean up the background chainstate leveldb directory.</source>
        <translation>Theip ar athainmniú '%s' -&gt; '%s'. Ní féidir eolaire leveldb an tslabhra cúlra a ghlanadh.</translation>
    
YES - The translation is problematic. The first part of the sentence "Theip ar athainmniú" translates to "Failed on renaming" which is grammatically incorrect. It should be "Theip ar athainmniú" or "The athainmniú". Also, the phrase "an tslabhra cúlra" translates to "the background chain" which is too literal and doesn't convey the meaning of "background chainstate" in the context of Bitcoin. A more appropriate translation for "chainstate" would be "staid an tslabhra" or "stádas an tslabhra".

Here's a corrected translation:

YES - Theip ar athainmniú '%s' -&gt; '%s'. Ní féidir eolaire leveldb staid an tslabhra cúlra a ghlanadh.
```

```
        <source>Specified -blockmaxweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Sáraíonn -blockmaxweight sonraithe (%d) uasmheáchan comhaontaithe (%d)</translation>
    
YES - The word "block" is missing from the translation.
Sáraíonn -blockmaxweight sonraithe (%d) uasmheáchan an bhloic chomhaontaithe (%d)
```

```
        <source>Specified -blockreservedweight (%d) is lower than minimum safety value of (%d)</source>
        <translation>Sáraíonn -blockreservedweight sonraithe (%d) níos ísle ná an íosluach sábháilteachta de (%d)</translation>
    
YES - The translation uses an inappropriate word for "specified".
Sáraíonn -blockreservedweight sonraithe (%d) níos ísle ná an íosluach sábháilteachta de (%d)
```

```
        <source>UTXO snapshot failed to validate. Restart to resume normal initial block download, or try loading a different snapshot.</source>
        <translation>Theip ar bhailíochtú a dhéanamh ar achomair UTXO. Atosaigh chun gnáthíoslódáil na mbloc tosaigh a atosú, nó bain triail as pictiúr eile a lódáil.</translation>
    
YES

The translation for "snapshot" is inconsistent and incorrect. It is first translated as "achomair" (summary) and then incorrectly as "pictiúr" (picture). "Pictiúr" is a literal mistranslation in this technical context. A better and more consistent translation is needed.

Correct translation:
Níorbh fhéidir léargas UTXO a bhailíochtú. Atosaigh chun an gnáth-íoslódáil bloc tosaigh a atosú, nó bain triail as léargas eile a lódáil.
```

```
        <source>whitebind may only be used for incoming connections ("out" was passed)</source>
        <translation>ní féidir ceangaltán bán a úsáid ach amháin le haghaidh naisc isteach (ritheadh ​​​​"amach")</translation>
    
YES, the translation is problematic. The phrase "ceangaltán bán" is a literal translation of "whitebind" which doesn't make sense in the context of Bitcoin. The word "bind" in this context likely refers to binding an address to a port for incoming connections. A more appropriate translation would be to focus on the concept of binding an address or simply an address.

NO
```

```
        <source>Failed to connect best block (%s).</source>
        <translation>Theip ar nascadh an bhloc is fearr (%s).</translation>
    
YES, The translation is incorrect and does not convey the intended meaning. The word "Theip" is not a recognized Irish word. The correct translation should convey that the connection to the best block failed.

NO
```

```
        <source>Failed to rescan the wallet during initialization</source>
        <translation>Theip athscanadh ar an sparán le linn túsúchán</translation>
    
YES, The translation is grammatically incorrect. The verb "Theip" is typically followed by "ar" or "as", but in this context, "ar" does not fit grammatically. The correct translation should use a different phrasing to convey the meaning of "failed". Additionally, "túsúchán" is not a standard word for initialization in Irish. A more appropriate term would be "tosú" or "curtha ar bun".

Theip athscanadh ar an sparán le linn túsúchán.
Correct translation: Níorbh fhéidir an sparán a athscanadh le linn tosú.
```

```
        <source>Failed to start indexes, shutting down..</source>
        <translation>Theip ar thús a chur leis na hinnéacsanna, dúnadh.</translation>
    
YES, The translation is erroneous. The phrase "Theip ar thús a chur leis na hinnéacsanna" translates to "Failed to start with the indexes". The word "dúnadh" means "closing" or "shutdown". The correct translation should be "Theip ar thús a chur leis na hinnéacsanna, ag dúnadh síos..".
Theip ar thús a chur leis na hinnéacsanna, ag dúnadh síos..
```

```
        <source>Failed to verify database</source>
        <translation>Theip ar fhíorú an mbunachar sonraí</translation>
    
YES, The Irish translation is grammatically incorrect and does not accurately convey the meaning of the English source text. The word "Theip" is not a recognized Irish verb.

Correct translation: Theip ar fhíorú an bunachar sonraí -> Theip ar fhíorú an bunachar sonraí
```

```
        <source>Failed to write undo data.</source>
        <translation>Theip ar scríobh sonraí cealaigh.</translation>
    
YES - The translation uses an incorrect word for "undo". The correct word for "undo" in this context would be "aischuir".
Failed to write undo data. -> Theip ar scríobh sonraí aischuir.
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>Bloc geineasas mícheart nó ní aimsithe. datadir mícheart don líonra?</translation>
    
YES - The translation contains an untranslated English word "datadir". The correct translation should be "eolaire sonraí".
Bloc geineasas mícheart nó ní aimsithe. Eolaire sonraí mícheart don líonra?
```

```
        <source>Listening for incoming connections failed (listen returned error %s)</source>
        <translation>Theip ar éisteacht le naisc isteach (éisteacht ar ais earráid %s)</translation>
    
YES - The translation uses "éisteacht ar ais" which translates to "listening back" or "hear back". The correct translation for "listen" in this context should be "éisteacht". The word "ar" before "ais" is also unnecessary.

Theip ar éisteacht le naisc isteach (éisteacht ar ais earráid %s)
Corrected translation: Theip ar éisteacht le naisc isteach (thug éisteacht earráid %s)
```

```
        <source>Prune cannot be configured with a negative value.</source>
        <translation>Ní féidir Bearradh a bheidh cumraithe le luach diúltach.</translation>
    
YES - The translation is grammatically incorrect and does not convey the intended meaning. The phrase "Ní féidir Bearradh a bheidh cumraithe le luach diúltach" translates to "Pruning cannot be configured with a negative value", but the structure is awkward and unnatural in Irish. A more appropriate translation would be "Ní féidir Bearradh a chumrú le luach diúltach.".
Ní féidir Bearradh a chumrú le luach diúltach.
```

```
        <source>SQLiteDatabase: Failed to execute statement to verify database: %s</source>
        <translation>SQLiteDatabase: Theip ar rith ráiteas chun an bunachar sonraí a fhíorú: %s</translation>
    
YES - The Irish translation for "Failed to execute statement to verify database" is incorrect. The word "Theip" is not a valid Irish word in this context. A more accurate translation would be "Teip" or "Theipigh".

Corrected translation:
SQLiteDatabase: Theipigh ar rith ráiteas chun an bunachar sonraí a fhíorú: %s
```

```
        <source>SQLiteDatabase: Unexpected application id. Expected %u, got %u</source>
        <translation>SQLiteDatabase: Aitheantas feidhmchlár nach raibh súil leis. Ag súil le %u, fuair %u</translation>
    
UNK_LANG
```

```
        <source>Signing transaction failed</source>
        <translation>Theip ar síniú idirbheart</translation>
    
YES, the translation uses "Theip" which is a misspelling of "Theip".
NO
```

```
        <source>Specified -walletdir "%s" does not exist</source>
        <translation>Níl -walletdir "%s" sonraithe ann</translation>
    
YES - The translation is grammatically incorrect. The structure "sonraithe ann" implies that the directory *itself* is specified and exists, rather than the act of specifying the directory. The phrase "does not exist" should modify the directory.

Correct translation: Níl an fillteán -walletdir "%s" a shonraigh tú ann
```

```
        <source>Specified -walletdir "%s" is a relative path</source>
        <translation>Is cosán spleách é -walletdir "%s" sonraithe</translation>
    
YES - The translation incorrectly states that the path is "dependent" or "relative" instead of just "relative". The Irish word "spleách" means "dependent" or "reliant", which is not the intended meaning of "relative path" in this context. A more accurate translation would be "Is cosán coibhneasta é -walletdir "%s" sonraithe", where "coibhneasta" accurately translates to "relative".

Is cosán coibhneasta é -walletdir "%s" sonraithe
```

```
        <source>Unknown change type '%s'</source>
        <translation>Anaithnid cineál sóinseáil '%s'</translation>
    
YES, The translation uses "sóinseáil" which means "foal" and not "change" in the context of Bitcoin transactions.

The correct translation should be:
Anaithnid cineál athruithe '%s'
```

```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>Rialacha nua anaithnid curtha i ngníomh (leagan giotán %ii)</translation>
    
YES, The translation contains erroneous content. The format specifier `%i` in the source text has been incorrectly translated as `%ii` in the target text.

NO
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Earráid: Níorbh fhéidir watch amháin tx %s a chur le sparán faire amháin</translation>
    
YES: The translation uses "watch amháin" for "watchonly". While "amháin" means "only", the combination doesn't accurately convey the technical term "watchonly" in the context of Bitcoin. The phrase "watchonly wallet" and "watchonly tx" are specific technical terms that should ideally be kept in English or translated more precisely to reflect their meaning within the Bitcoin ecosystem.

NO
```
</details>
