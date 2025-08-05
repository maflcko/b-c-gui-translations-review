# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ga_IE</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bga_IE%5D%20low%20quality)


```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
YES
The translation "Comhad athróige camógdheighilte" contains errors and awkward phrasing. The correct term for "Comma separated file" in Irish should be "Comhad leakeanta le camóga" or more commonly "Comhad scartha le camóga". The original word "athróige" does not fit here and "camógdheighilte" is an incorrect compound.

Correct translation:
Comhad scartha le camóga
```

```
        <source>IP/Netmask</source>
        <translation>PI/Mascadhidirlíon</translation>
    
YES  
The translation "PI/Mascadhidirlíon" is incorrect and problematic. "IP" should remain as "IP" since it's a technical term (Internet Protocol) and not usually translated. "Netmask" in Irish could be correctly translated as "Mionscálalíonra" or "Masc líonra". "Mascadhidirlíon" is not a proper compound word and is not standard Irish. Also, there should be no space or concatenation errors.

Correct translation:  
IP/Mionscála Líonra  
(or if preferred without space: IP/MionscálaLíonra)  
However, the most accurate and technical term commonly used is:  
IP/Masc líonra
```

```
        <source>%1 d</source>
        <translation>%1 l</translation>
    
YES  
The source uses "d" which likely stands for "days" (as a time unit), but the translation uses "l" which stands for "laithe" (days in Irish). However, in Bitcoin and technical contexts, it is typical to keep single-letter abbreviations consistent with English standards or use clearly understood abbreviations. The lowercase "l" can be confused with the digit "1" and is not standard for days.

If the intent is to translate "d" (days) into Irish, it would be better to either keep "%1 d" unchanged (as it is a technical standard) or use the full word "lae" (singular) or "lá" (plural) appropriately, but since it is an abbreviation, it is common to retain the English "d" for days.

Correct translation:  
%1 d
```

```
        <source>%1 m</source>
        <translation>%1 n</translation>
    
YES  
The translation incorrectly uses "n" instead of "m" for meters. In Irish (ga_IE), the abbreviation for meters remains "m".  

Correct translation:  
%1 m
```

```
        <source>Show the list of used sending addresses and labels</source>
        <translation>Taispeáin an liosta de seoltaí seoladh úsáidte agus na lipéid </translation>
    
YES  
The translation has a redundancy and a spacing issue. The phrase "seoltaí seoladh" is repetitive; "seoltaí" already means "addresses," so adding "seoladh" (which also means "address") is unnecessary and incorrect here. Also, there is an extra space at the end of the translation.  

Correct translation:  
Taispeáin an liosta de sheoltaí agus na lipéid úsáidte
```

```
        <source>Sending addresses</source>
        <translation>Seoltaí seoladh</translation>
    
YES  
The translation "Seoltaí seoladh" literally means "Sent addresses" or "Sending of addresses," but it is awkward and redundant in Irish because "seoladh" means "address" and "seoltaí" is the plural past participle of "send," which doesn't function well here. A better idiomatic and clear translation for "Sending addresses" (as in addresses being sent, or addresses that are sending) in the context of Bitcoin would be:

"Seoltaí seolta"  

Here, "Seoltaí" is "addresses" (plural), and "seolta" is the verbal adjective meaning "sent" or "sending," but this is still somewhat ambiguous. However, more likely, the phrase implies "Addresses for sending" or "Sending addresses" in the sense of addresses involved in sending Bitcoin.

Alternatively, if it refers to addresses used for sending, a better phrase might be:

"Seoltaí chun seoladh" (Addresses for sending)

Without more context, the simplest and clearest correction is:

"Seoltaí ag seoladh"

which means "Addresses sending" or "Sending addresses."

If the source phrase is a label in a UI panel or list referring to addresses which are in the process of sending, the best idiomatic translation would be:

"Seoltaí atá á seoladh"

But given the need for concise UI text, "Seoltaí ag seoladh" is appropriate.

Therefore, the corrected translation is:

"Seoltaí ag seoladh"
```

```
        <source>%1 client</source>
        <translation>%1 cliaint</translation>
    
YES  
The translation contains a typo: "cliaint" should be "cliant". However, the correct Irish word for "client" is "cliant". So it appears to be a misspelling.  

Correct translation:  
%1 cliant
```

```
        <source>Show</source>
        <translation>Sconas</translation>
    
YES  
The translation "Sconas" is incorrect for the English word "Show" in Irish (ga_IE). "Sconas" means "slipper" (a type of footwear), which is unrelated and incorrect in this context.

Correct translation:  
"Taispeáin"
```

```
        <source>Error creating wallet</source>
        <translation>Earráid agus sparán á chruthú</translation>
    
YES  
The translation "Earráid agus sparán á chruthú" literally means "Error and wallet being created," which is inaccurate and misleading. The correct translation should convey that there was an error in the process of creating the wallet. A better translation is:  

"Earráid ag cruthú sparán"
```

```
        <source>Change:</source>
        <translation>Sóinseáil:</translation>
    
YES
The translation "Sóinseáil:" is incorrect and does not convey the meaning of "Change:" in the Bitcoin context (referring to the amount of leftover funds returned in a transaction). The correct Irish translation for "Change:" in this financial/transactional context is "Athrú:". 

Correct translation:
Athrú:
```

```
        <source>(un)select all</source>
        <translation>(neamh)roghnaigh gach rud </translation>
    
YES
There is an extra space at the end of the translation string which should be removed.

Correct translation:
(neamh)roghnaigh gach rud
```

```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
YES  
The translation "Cóipeáíl sóinseáil" is incorrect and does not convey the intended meaning of "Copy change" in the Bitcoin context. The English phrase refers to copying the "change" amount (leftover funds) in a transaction, not "sóisneáil" which means "lighting" or "ignition." Also, "Cóipeáíl" is misspelled; the correct Irish verb for "copy" is "Cóipeáil."

A correct translation would be:  
"Cóipeáil an sruth"  
Here, "sruth" can mean "change" or "balance" in some financial contexts, but ideally, a more context-specific phrase is needed. However, since in Bitcoin, "change" refers to "the returned amount," and there is no widely-used standard Irish term for Bitcoin "change," it may be acceptable to use "Cóipeáil an athrú" where "athrú" means "change" or "difference."

Thus, the corrected translation:  
"Cóipeáil an athrú"
```

```
        <source>change from %1 (%2)</source>
        <translation>sóinseáil ó %1 (%2)</translation>
    
YES  
The word "sóinseáil" is incorrect or does not exist in Irish (ga_IE) and does not correspond to "change" in the Bitcoin transaction context. The correct translation for "change" in the sense of a Bitcoin transaction (i.e., the leftover amount returned to the sender) is typically "athrú".  

Correct translation:  
athrú ó %1 (%2)
```

```
        <source>Restore wallet failed</source>
        <extracomment>Title of message box which is displayed when the wallet could not be restored.</extracomment>
        <translation>Theip ar athchóiriú an sparán</translation>
    
YES
The translation is missing a verb to convey the failure properly. "Theip ar athchóiriú an sparán" translates more literally to "Failure on restoring the wallet," but it lacks the past tense or perfect construction needed for "Restore wallet failed." A more accurate and natural translation would be:

"Theip ar athchóiriú an sparán" can be improved to:
"Theip ar athchóiriú an tsparán"

Note the correction in the definite article lenition: "sparán" (wallet) should be "an sparán" or "an tsparán"? In Irish, after certain prepositions, the article can cause eclipsis or lenition. "Ar" (on) plus the article "an" + "sparán" results in "an tsparán" because "sparán" starts with "s," which lenites to "ts" after "ar an."

Similarly, the phrase "Theip ar athchóiriú an tsparán" is the standard usage to say "Failure on the restoration of the wallet."

Alternatively, a better way to say "Restore wallet failed" succinctly would be:

"Theip ar athchóiriú an tsparán"

Hence, the corrected translation:

Theip ar athchóiriú an tsparán
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>An seoladh chomhcheangailte leis an iontráil liosta seoltaí seo. Ní féidir é seo a mionathraithe ach do seoltaí seoladh.</translation>
    
YES  
The translation contains some awkward phrasing and a redundant word that affects clarity. Specifically, "seoltaí seoladh" is repetitive and unnatural in Irish (both mean "addresses"). A more natural phrasing would be:  
"An seoladh comhcheangailte leis an iontráil liosta seoltaí seo. Ní féidir é seo a mionathrú ach do sheoltaí chun seolta."  

Explanation:  
- "mionathraithe" should be "mionathrú" for the verbal noun form.  
- "seoltaí seoladh" is redundant; "sheoltaí chun seolta" or "seoltaí a sheoladh" (sending addresses) is clearer and grammatically correct.  
- The rest of the translation preserves the meaning and format correctly.  

Correct translation:  
An seoladh comhcheangailte leis an iontráil liosta seoltaí seo. Ní féidir é seo a mionathrú ach do sheoltaí chun seolta.
```

```
        <source>New sending address</source>
        <translation>Seoladh nua seoladh</translation>
    
YES  
The translation repeats the word "seoladh" (address) unnecessarily, making it incorrect and awkward. The correct translation should be:  
"Seoladh nua"
```

```
        <source>Edit sending address</source>
        <translation>Eagarthóireacht seoladh seoladh</translation>
    
YES  
The translation incorrectly repeats the word "seoladh" ("address") twice, resulting in "seoladh seoladh" which is not correct. The source phrase "Edit sending address" should be translated as "Eagarthóireacht seolaí seolta" or more naturally "Eagarthóireacht an seolaí seolta" depending on context. Here, "sending address" refers to the address used to send (seolaí seolta).  

Correct translation:  
Eagarthóireacht seolaí seolta
```

```
        <source>Estimated time left until synced</source>
        <translation>Measta am fágtha go dtí sioncrónaithe</translation>
    
YES  
The translation contains errors: "Measta" should be "Meastachán" for "Estimated," and "am" is gendered masculine "time," but the article "an" is missing ("an t-am" or just "am" is acceptable with context). Additionally, "sioncrónaithe" is a correct form of "synced," but standard Irish spelling for "synchronized" would be "shioncrónaithe". The phrase lacks proper grammar and spacing.

Correct translation:  
"Am meastacháin fágtha go dtí an tsioncrónú"  
or more naturally:  
"An t-am meastacháin atá fágtha go dtí sioncrónú"  

A smoother idiomatic translation might be:  
"Am meastacháin fágtha go dtí go bhfuil sé sioncrónaithe"  

But for conciseness and technical usage, the following is acceptable and accurate:  
"Am meastacháin fágtha go dtí sioncrónú"
```

```
        <source>PSBT copied to clipboard.</source>
        <translation>Cóipeáladh IBSP chuig an gearrthaisce.</translation>
    
YES  
The abbreviation "PSBT" (Partially Signed Bitcoin Transaction) should not be translated into "IBSP," as abbreviations for technical terms like PSBT are generally kept in their original form in Irish as well for clarity and consistency. The rest of the sentence is correctly translated.  

Correct translation:  
Cóipeáladh PSBT chuig an gearrthaisce.
```

```
        <source>Mapped AS</source>
        <translation>CU Mapáilte</translation>
    
YES  
The translation "CU Mapáilte" is incorrect. The English source "Mapped AS" likely refers to "Mapped Autonomous System" in a Bitcoin or networking context. "CU" is not a Gaelic abbreviation for "AS" and does not convey the intended meaning. The proper translation should keep "AS" as is or translate as "Córas Uathrialach Mapáilte" if fully translated.

Correct translation:  
"AS Mapáilte"  
or  
"Córas Uathrialach Mapáilte"
```

```
        <source>detecting: peer could be v1 or v2</source>
        <extracomment>Explanatory text for "detecting" transport type.</extracomment>
        <translation>bhrath: d’fhéadfadh v1 nó v2 a bheith i gcomhghleacaí</translation>
    
YES  
The translation contains a spacing issue: there should be a space after the colon following "bhrath". Also, the English word "peer" is translated as "comhghleacaí," which literally means "opponent" or "rival" in Irish, not the correct technical term for a P2P Bitcoin peer or node. The better Irish term would be "piara" (peer) which is used in technical contexts.

Corrected translation:  
bhrath: d’fhéadfadh v1 nó v2 a bheith i bpíara
```

```
        <source>Change:</source>
        <translation>Sóinseáil:</translation>
    
YES
The translation "Sóinseáil:" is incorrect and does not convey the meaning of "Change:" in the Bitcoin context (referring to the amount of leftover funds returned in a transaction). The correct Irish translation for "Change:" in this financial/transactional context is "Athrú:". 

Correct translation:
Athrú:
```

```
        <source>Custom change address</source>
        <translation>Seoladh sóinseáil saincheaptha</translation>
    
YES  
The translation uses "sóinseáil" for "change," which is a literal financial term for coinage or small change in Irish, but in the Bitcoin context "change" refers to the leftover amount returned in a transaction. The usual translation for "change" in Bitcoin terminology is "athrú" (meaning change, as in returned money). "Seoladh athraithe saincheaptha" would better convey "Custom change address."

Correct translation:  
Seoladh athraithe saincheapta
```

```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
YES  
The translation "Cóipeáíl sóinseáil" is incorrect and does not convey the intended meaning of "Copy change" in the Bitcoin context. The English phrase refers to copying the "change" amount (leftover funds) in a transaction, not "sóisneáil" which means "lighting" or "ignition." Also, "Cóipeáíl" is misspelled; the correct Irish verb for "copy" is "Cóipeáil."

A correct translation would be:  
"Cóipeáil an sruth"  
Here, "sruth" can mean "change" or "balance" in some financial contexts, but ideally, a more context-specific phrase is needed. However, since in Bitcoin, "change" refers to "the returned amount," and there is no widely-used standard Irish term for Bitcoin "change," it may be acceptable to use "Cóipeáil an athrú" where "athrú" means "change" or "difference."

Thus, the corrected translation:  
"Cóipeáil an athrú"
```

```
        <source>Warning: Unknown change address</source>
        <translation>Rabhadh: Seoladh sóinseáil anaithnid</translation>
    
YES  
The phrase "Seoladh sóinseáil anaithnid" is not idiomatic Irish and includes a misuse of the word "sóinseáil," which does not fit contextually here. The English "change address" refers to a Bitcoin transaction term (the address where change is sent), and should be translated in a way that reflects this technical meaning, ideally using "seoladh athraithe" or "seoladh athrú" where "athrú" means "change" in this transactional sense.  

Correct translation:  
Rabhadh: Seoladh athraithe anaithnid
```

```
        <source>Increase transaction fee</source>
        <translation>Méadaigh idirbheart  táille</translation>
    
YES  
There is an extra space between "idirbheart" and "táille" in the translation, which is a formatting issue. Also, the phrase in Irish should be without the extra space and more commonly "méadaigh táille idirbheart" or "méadaigh táille idirbhearta" (if plural) depending on context. The most accurate and natural translation would be:

Correct translation:  
Méadaigh táille idirbheart
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
YES
The translation "Comhad athróige camógdheighilte" contains errors and awkward phrasing. The correct term for "Comma separated file" in Irish should be "Comhad leakeanta le camóga" or more commonly "Comhad scartha le camóga". The original word "athróige" does not fit here and "camógdheighilte" is an incorrect compound.

Correct translation:
Comhad scartha le camóga
```

```
        <source>Unable to decode PSBT from clipboard (invalid base64)</source>
        <translation>Ní féidir IBSP a dhíchódú ón ghearrthaisce (Bun64 neamhbhailí)</translation>
    
YES  
The abbreviation "PSBT" should be preserved as in the source, not translated as "IBSP," which is incorrect. Also, "base64" should remain lowercase and untranslated as it is a technical term. "gearrthaisce" (clipboard) and the rest are acceptable.  

Correct translation:  
Níl sé indéanta PSBT a dhíchódú ón ngearrthaisce (base64 neamhbhailí)
```

```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>Cóipeáil PSBT bump táille chuig an ngearrthaisce</translation>
    
YES  
The phrase "Fee-bump PSBT copied to clipboard" is translated as "Cóipeáil PSBT bump táille chuig an ngearrthaisce," which is not idiomatic and contains direct word order and word choices that seem unnatural in Irish. In particular:  
- "Cóipeáil" is a noun meaning "copy" rather than a verb (the verb form would be "Cóipeáil" as an imperative or "Rinneadh cóip de..."). Here the sentence is in passive past tense ("copied"), so it should be a past passive construction rather than just "copy."  
- "bump táille" is a literal and awkward word order for "fee bump." The adjective usually comes after the noun in Irish, so "bump táille" is reversed and "bump" is English. "Bump" should be translated if possible or kept consistent.  
- The term "PSBT" (Partially Signed Bitcoin Transaction) might remain untranslated as an acronym, which is acceptable.  
- "Chuig an ngearrthaisce" correctly means "to the clipboard," so that part is fine.  

A better translation would be something like:  
"PSBT le bump táille cóipeáilte chuig an ngearrthaisce"  
OR  
"PSBT bump táille cóipeáilte chuig an ngearrthaisce"  

This uses "cóipeáilte," the proper past participle for "copied," and places adjectives properly.  

Final correction:  
<translation>PSBT bump táille cóipeáilte chuig an ngearrthaisce</translation>
```

```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>Theip ar %s an staid snapshot -assumeutxo a bhailíochtú. Léiríonn sé seo fadhb crua-earraí, nó fabht sna bogearraí, nó droch-mhodhnú bogearraí a cheadaigh pictiúr neamhbhailí a luchtú. Mar thoradh air seo, stopfar an nód agus stopfaidh sé de úsáid a bhaint as staid ar bith a tógadh ar an seat, ag athshocrú airde an tslabhra ó%dgo%d. Ar an gcéad atosú eile, athchromfar ar an nód ag sioncronú ó %d gan úsáid a bhaint as sonraí seat. Tuairiscigh an teagmhas seo do %s lena n-áirítear conas a fuair tú an pictiúr. Fágfar an slabhrashlabhra neamhbhailí ar an diosca ar eagla go mbeadh sé ina chuidiú leis an tsaincheist ba chúis leis an earráid seo a dhiagnóisiú.</translation>
    
YES
The translation contains several errors and awkward phrasing that can cause confusion:

1. "Theip ar %s an staid snapshot -assumeutxo a bhailíochtú."  
   - This is an awkward and incorrect structure. A better phrasing would be:  
     "Theip ar %s staid an snapshot -assumeutxo a bhailíochtú." or  
     "Theip ar %s an staid snapshot -assumeutxo a dhearbhú."

2. "fadhb crua-earraí" is understandable but "fhabht" should be "fabht" (typo corrected), though "fabht" is fine.

3. "droch-mhodhnú bogearraí" is understandable but "droch-mhodhnú bogearraí a cheadaigh pictiúr neamhbhailí a luchtú." - "pictiúr" is not suitable for "snapshot" in this context. Prefer "íomhá" or "snapshot" retained or "cóip".

4. "sean" or "snapshot" should be translated consistently; "pictiúr" is wrong here.

5. "ar an seat" - "seat" is untranslated and wrong; it should be "snapshot" or "íomhá".

6. "ag athshocrú airde an tslabhra ó%dgo%d." -- missing spaces after "ó" and before "go", and the expression of range should be: "ó %d go %d."

7. "Ar an gcéad atosú eile, athchromfar ar an nód ag sioncronú ó %d gan úsáid a bhaint as sonraí seat."  
   - "athchromfar" is not a proper Irish word, probably a typo of "athchosnófar" or "athstopfar".  
   - "gan úsáid a bhaint as sonraí seat" - again "seat" should be "snapshot" or "íomhá."

8. "Tuairiscigh an teagmhas seo do %s lena n-áirítear conas a fuair tú an pictiúr." - again "pictiúr" should be "íomhá" or "snapshot."

9. "Fágfar an slabhrashlabhra neamhbhailí ar an diosca" - repeated "slabhrashlabhra" (slabhra slabhra). Should be "slabhra neamhbhailí."

10. Stylistically, some phrases can be improved for clarity and idiomatic Irish.

Corrected translation:

Theip ar %s staid an snapshot -assumeutxo a bhailíochtú. Léiríonn sé seo fadhb crua-earraí, fabht sa bhogearra, nó droch-mhodhnú bogearra a cheadaigh snapshot neamhbhailí a luchtú. Mar thoradh air seo, dúnfar an nód agus stopfar de úsáid a bhaint as aon staid a tógadh ón snapshot, ag athshocrú airde an tslabhra ó %d go %d. Sa chéad atosú eile, leanfaidh an nód ar aghaidh ag sioncronú ó %d gan aon sonraí snapshot a úsáid. Tá fáilte roimh thuairisc ar an teagmhas seo chuig %s, lena n-áirítear conas a fuair tú an snapshot. Fágfar slabhra stáit neamhbhailí an snapshot ar an diosca fiúntach chun cabhrú leis an earráid a dhiagnóisiú.

Therefore:

YES  
The translation contains multiple errors: incorrect or inconsistent word choice for "snapshot" (pictiúr instead of snapshot/íomhá), untranslated or incorrect terms ("seat"), missing spaces around format specifiers, repeated words, and awkward phrasing. Here is the corrected translation:

Theip ar %s staid an snapshot -assumeutxo a bhailíochtú. Léiríonn sé seo fadhb crua-earraí, fabht sa bhogearra, nó droch-mhodhnú bogearra a cheadaigh snapshot neamhbhailí a luchtú. Mar thoradh air seo, dúnfar an nód agus stopfar de úsáid a bhaint as aon staid a tógadh ón snapshot, ag athshocrú airde an tslabhra ó %d go %d. Sa chéad atosú eile, leanfaidh an nód ar aghaidh ag sioncronú ó %d gan aon sonraí snapshot a úsáid. Tá fáilte roimh thuairisc ar an teagmhas seo chuig %s, lena n-áirítear conas a fuair tú an snapshot. Fágfar slabhra stáit neamhbhailí an snapshot ar an diosca fiúntach chun cabhrú leis an earráid a dhiagnóisiú.
```

```
        <source>Cannot downgrade wallet from version %i to version %i. Wallet version unchanged.</source>
        <translation>Ní féidir an sparán a íosghrádú ó leagan %igo leagan%i. Leagan sparán gan athrú.</translation>
    
YES
The translation contains errors in spacing and format specifiers. The format specifiers %i are incorrectly merged with surrounding words ("%igo" and "leagan%i"). Also, there is a missing space between "sparán" and "gan". 

Correct translation:
Ní féidir an sparán a íosghrádú ó leagan %i go leagan %i. Leagan sparán gan athrú.
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>Ní féidir sparán scoilte neamh-HD a uasghrádú ó leagan%igo leagan%i gan uasghrádú chun tacú le heochrach réamh-scoilte. Úsáid leagan %i nó níl aon leagan sonraithe.</translation>
    
YES
There is a spacing issue with the format specifiers "%i" in the translation: it appears as "leagan%igo" and "leagan%i" without spaces after "leagan". In Irish, like in English, a space is required before the format specifier.

Correct translation:
Níl sé indéanta sparán scoilte neamh-HD a uasghrádú ó leagan %i go leagan %i gan uasghrádú chun tacú le heochrach réamh-scoilte. Úsáid leagan %i nó níl aon leagan sonraithe.
```

```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Earráid agus%s á léamh! Seans go bhfuil sonraí idirbhirt in easnamh nó mícheart. Sparán athscanadh.</translation>
    
YES  
The translation does not accurately reflect the source text. The source message is a specific error about the dumpfile format record being incorrect, mentioning the received and expected values with a "%s" format specifier. However, the translation is a generic error about reading and missing or incorrect transaction data, with no mention of the dumpfile format or the "%s" placeholder, and it adds unrelated text about rescanning the wallet.  

Correct translation:  
Earráid: Tá taifead formáid comhaid dump mícheart. Fuair muid "%s", ba mhaith leat "format".
```

```
        <source>Invalid value detected for '-wallet' or '-nowallet'. '-wallet' requires a string value, while '-nowallet' accepts only '1' to disable all wallets</source>
        <translation>Braitheadh ​​luach neamhbhailí le haghaidh '-wallet' nó '-nowallet'. Teastaíonn luach teaghrán le '-wallet', agus ní ghlacann '-nowallet' ach le '1' chun gach sparán a dhíchumasú</translation>
    
YES
There is a stray zero-width space (or similar invisible character) after "Braitheadh" ("Braitheadh ​​luach"), which is incorrect formatting. Also, the translation could be improved for clarity and naturalness in Irish.

Correct translation:
Braitheadh luach neamhbhailí le haghaidh '-wallet' nó '-nowallet'. Teastaíonn luach teaghráin ó '-wallet', agus ní ghlacann '-nowallet' ach '1' chun gach sparán a dhíchumasú
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Is é seo an táille idirbhirt a fhéadfaidh tú cuileáil má tá sóinseáil níos lú ná dusta ag an leibhéal seo</translation>
    
YES  
The translation uses incorrect Irish words that do not convey the intended meaning, and mixes English ("dust") untranslated and "cuileáil" which means "to crawl" instead of "discard." Also, "sóinseáil" is an incorrect term for "change" in a Bitcoin transaction context.

Correct translation:  
Is é seo an táille idirbhirt ar féidir leat a chaitheamh más lú an sóinseáil ná dust ar an leibhéal seo
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Leibhéal logála catagóir ar leith nach dtacaítear leis %1$s=%2$s. Bhíothas ag súil le %1$s=1:2. Catagóirí bailí: %3$s. Leibhéil loga bailí: %4$s.</translation>
    
YES
The translation contains an error in replicating the expected format specifier example. The English source shows the expected format as `%1$s=<category>:<loglevel>`, but the translation incorrectly shows `%1$s=1:2`, which is not accurate and confusing.

Correct translation:
Leibhéal logála catagóir ar leith nach dtacaítear leis %1$s=%2$s. Bhíothas ag súil le %1$s=&lt;catagóir&gt;:&lt;leibhéalloga&gt;. Catagóirí bailí: %3$s. Leibhéil loga bailí: %4$s.
```

```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>Theip ar bhaint an tsainstáit seat seat (%s). Bain de láimh é roimh atosú.
</translation>
    
YES  
The translation contains repeated words "seat seat" which is an error. The phrase "snapshot chainstate dir" should be translated more accurately and clearly in Irish. A better translation would be:  

Theip ar bhaint an eolaire staidse slabhra seat (%s). Bain de láimh é sula atosófar é.
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>Naisc amach teoranta do Tor (-onlynet=onion) ach ní thugtar an seachfhreastalaí chun líonra Tor a bhaint amach: ní thugtar aon seachfhreastalaí, -oinniún nó -listenonion</translation>
    
YES  
The translation contains an error with the word "oinniún," which should be "onion" as it is a literal network parameter and should not be translated or altered. Also, the part "ní thugtar aon seachfhreastalaí, -oinniún nó -listenonion" is incomplete or confusing, as it does not fully replicate the source list "-proxy, -onion or -listenonion is given." The source specifies three parameters: -proxy, -onion, and -listenonion, which must all be mentioned correctly.

Correct translation:  
Naisc amach teoranta do Tor (-onlynet=onion) ach ní thugtar an seachfhreastalaí chun líonra Tor a bhaint amach: ní thugtar aon cheann de -proxy, -onion nó -listenonion
```

```
        <source>whitebind may only be used for incoming connections ("out" was passed)</source>
        <translation>ní féidir ceangaltán bán a úsáid ach amháin le haghaidh naisc isteach (ritheadh ​​​​"amach")</translation>
    
YES  
There are extra spaces around the word "ritheadh" before the quoted "amach" which are not present in the source and create formatting inconsistencies. Also, the phrase "ní féidir ceangaltán bán a úsáid ach amháin le haghaidh naisc isteach" is understandable but could be phrased more naturally. Additionally, "whitebind" is a technical term and should remain as is (without translation).  

Corrected translation:  
whitebind ní féidir ach do naisc isteach a úsáid ("amach" a rith)
```

```
        <source>Failed to rescan the wallet during initialization</source>
        <translation>Theip athscanadh ar an sparán le linn túsúchán</translation>
    
YES  
The translation contains a spelling error: "athscanadh" should be "athscanáil" to correctly reflect "rescan" as a noun or verbal noun. Additionally, "túsúchán" is misspelled and should be "túsú" (initialization/start).  

Correct translation:  
Theip ar athscanáil an sparán le linn túsú
```

```
        <source>Failed to start indexes, shutting down..</source>
        <translation>Theip ar thús a chur leis na hinnéacsanna, dúnadh.</translation>
    
YES  
The translation contains grammatical errors and awkward phrasing. "Theip ar thús a chur leis na hinnéacsanna" is not idiomatic Irish and sounds incorrect. Also, the English has double dots ".." indicating an ellipsis or a trailing thought, which the Irish translation does not reflect, and "dúnadh" is just "closed" without clear connection to the rest of the phrase.

A better translation would be:  
"Theip ar thús a chur na hinnéacsanna, ag dúnadh..."  
or more idiomatically:  
"Theip ar thús a chur leis na hinnéacsanna, tá an córas ag dúnadh..."  

A recommended corrected translation:  
"Theip ar thús a chur leis na hinnéacsanna, tá an córas ag dúnadh..."
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>Bloc geineasas mícheart nó ní aimsithe. datadir mícheart don líonra?</translation>
    
YES  
The translation uses "Bloc geineasas" which is a less common and somewhat awkward rendering of "genesis block". A better term is "bloc bunúsach" or "bloc tosaigh" which are more natural and better understood as "genesis block" in a Bitcoin context. Also, "datadir" is left untranslated and lowercase, whereas it should be capitalized or translated for clarity. The rest of the sentence is mostly acceptable, but the question "Wrong datadir for network?" should be better rendered as a full question in Irish, e.g. "An bhfuil an datadir mícheart don líonra?"

Correct translation:  
Bloc bunúsach mícheart nó gan bhriseán tosaigh aimsithe. An bhfuil an datadir mícheart don líonra?
```

```
        <source>Listening for incoming connections failed (listen returned error %s)</source>
        <translation>Theip ar éisteacht le naisc isteach (éisteacht ar ais earráid %s)</translation>
    
YES
The translation contains a minor grammatical and word choice issue. "Theip ar éisteacht le naisc isteach" is understandable but awkward and not idiomatic for this context. A better phrase for "Listening for incoming connections failed" would be "Theip ar an éisteacht le nasc isteach" or "Theip ar éisteacht leis naisc isteach," using the singular "nasc" or plural "naisc" correctly with the prepositions. Also, "éisteacht ar ais earráid %s" is a literal and somewhat awkward rendering of "listen returned error %s"; "ar ais" ('back') is unnecessary and can be omitted for clarity.

Corrected translation:
Theip ar an éisteacht le nasc isteach (d\'fhuair éisteacht earráid %s)
```

```
        <source>Prune cannot be configured with a negative value.</source>
        <translation>Ní féidir Bearradh a bheidh cumraithe le luach diúltach.</translation>
    
YES  
The translation contains grammatical errors and unnatural phrasing in Irish. "Ní féidir Bearradh a bheith cumraithe le luach diúltach." would be a more accurate rendering. Note the correction from "a bheidh" (future tense) to "a bheith" (infinitive), and "Bearradh" should not be capitalized unless it is a proper noun, but it is more natural to leave it as is or lowercase for the common noun.

Correct translation:  
Ní féidir bearradh a bheith cumraithe le luach diúltach.
```

```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>Rialacha nua anaithnid curtha i ngníomh (leagan giotán %ii)</translation>
    
YES
There is an incorrect format specifier in the translation: "%ii" should be "%i" to match the source. Also, "leagan giotán" is the correct translation for "versionbit".

Correct translation:
Rialacha nua anaithnid curtha i ngníomh (leagan giotán %i)
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Earráid: Níorbh fhéidir watch amháin tx %s a chur le sparán faire amháin</translation>
    
YES  
The translation partially reflects the source meaning, but it sounds unnatural and inconsistent in Irish. The phrase "watchonly tx" is left untranslated and awkwardly combined. "watch amháin" does not correctly convey "watchonly" as a single technical term (referring to "watch-only" functionality in wallets). Also, "sparán faire amháin" is a literal and awkward rendering of "watchonly wallet," which should be translated to reflect the specific wallet type (e.g., "sparán faire-ní amháin" or "sparán faire amháin" is not idiomatic). The English technical terms should be either kept as-is or accurately localized.

A more accurate and idiomatic version would be:

Earráid: Níorbh fhéidir an idirbheart watch-only %s a chur leis an sparán watch-only

This keeps "watch-only" as a compound adjective describing the transaction and the wallet, which is a recognized recent loanword in technical Irish contexts, or alternatively, it could be fully translated with explanation if a better term exists.

If the technical terms must be fully translated:

Earráid: Níorbh fhéidir an idirbheart faire amháin %s a chur leis an sparán faire amháin

But this risks losing exact technical meaning.

Overall, the original is awkward and mixes partial Irish and English.

Correct translation:

Earráid: Níorbh fhéidir an idirbheart watch-only %s a chur leis an sparán watch-only
```
</details>
