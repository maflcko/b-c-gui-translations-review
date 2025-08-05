# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>is</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bis%5D%20low%20quality)


```
        <source>Create a new address</source>
        <translation>Búa til nýtt veski</translation>
    
YES  
The Icelandic translation "Búa til nýtt veski" means "Create a new wallet," not "Create a new address." The correct translation for "Create a new address" should be:  
"Búa til nýtt netfang" (if referring to an email-like address) or more appropriate in Bitcoin context:  
"Búa til nýtt heimilisfang" (address as in location or Bitcoin address).  
Since the context is Bitcoin, "heimilisfang" is the suitable word.  

Correct translation:  
Búa til nýtt heimilisfang
```

```
        <source>Copy the currently selected address to the system clipboard</source>
        <translation>Afrita valið veski í klemmuspjald</translation>
    
YES  
The translation is not in Icelandic, which is the language code 'is'. Instead, it appears to be in Icelandic but incorrectly uses the word "veski" which means "wallet" rather than "address" (which is "heimilisfang" or in this context better "netfang" or simply "fangi"). The source text refers to copying the selected Bitcoin address, not a wallet. Also, the preposition "í klemmuspjald" is not idiomatic Icelandic for "to the clipboard." A more natural translation would use "afrita" (copy) and "að klemmuspjaldið" (to the clipboard).

Correct translation:  
Afrita valið netfang í klemmuspjaldið
```

```
        <source>Enter address or label to search</source>
        <translation>Veldu veski eða merkingu fyrir leit</translation>
    
YES  
The translation is in Icelandic (language code 'is'), but it is not an accurate rendering of "Enter address or label to search." Instead, it says "Choose wallet or label for search," which changes the meaning and introduces confusion. "Enter" should be translated as "Sláðu inn" or "Skrifaðu inn," and "address" should be translated as "heimilisfang" or "töluheimilisfang" (in the Bitcoin context typically "heimilisfang").

Correct translation:  
Sláðu inn heimilisfang eða merki til að leita
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>Flyttu gögnin í núverandi flipa út í skrá                                                                    </translation>
    
YES  
The translation contains excessive trailing whitespace and an incorrect verb choice. The Icelandic verb "Flytja" means "to move" rather than "to export." A better translation should use "Flytja út" or "Flytja gögnin út" to clearly mean "Export," without excessive spaces.

Correct translation:  
Flytja gögnin í núverandi flipa í skrá
```

```
        <source>Choose the address to send coins to</source>
        <translation>Veldu veski sem greiða skal til</translation>
    
YES  
The Icelandic translation is incorrect and misleading. The source says "Choose the address to send coins to," which implies selecting an address to which coins will be sent. However, the translation "Veldu veski sem greiða skal til" means "Choose the wallet to pay to," which omits the concept of "address" and substitutes it with "wallet," and the wording is somewhat unnatural.

A better translation would be:  
"Veldu netfangið sem myntum skal senda til"  
Here, "netfangið" (the address) fits the Bitcoin context, and the meaning closely follows the original. Alternatively:  
"Veldu heimilisfangið til að senda myntir til"  
("Choose the address to send coins to") is also valid.

Correct translation:  
Veldu heimilisfangið sem myntum skal senda til
```

```
        <source>Choose the address to receive coins with</source>
        <translation>Veldu veski til að taka við rafmynt</translation>
    
YES  
The English source mentions "address" specifically, whereas the Icelandic translation uses "veski" (wallet), which is not equivalent. The term "address" in the Bitcoin context usually refers to an address, not the wallet itself. A more accurate translation would keep the word "fang" (address) to match the source meaning.

Correct translation:  
Veldu heimilisfangið sem á að taka við myntum með
```

```
        <source>Copy Address</source>
        <translation>Afrita færslugildi</translation>
    
YES  
The provided translation "Afrita færslugildi" is Icelandic ('is'). However, "Afrita færslugildi" translates to "Copy transaction value" rather than "Copy Address." The term "address" in the context of Bitcoin usually corresponds to "heimilisfang" or simply "færsluatriði" (less common), but the more accurate and clear translation for "Copy Address" would be:

Correct translation:  
Afrita heimilisfang
```

```
        <source>Export Address List</source>
        <translation>Flytja út færslulista</translation>
    
YES  
The translation "Flytja út færslulista" means "Export transaction list," not "Export address list." The correct Icelandic translation for "Export Address List" is:  
"Flytja út heimilisfangalista"
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Ekki tókst að vista færslugildalistann á %1. Reyndu aftur.</translation>
    
YES  
The Icelandic translation uses "færslugildalistann," which means "entry value list," not "address list." The correct term should refer to an "address list" ("tölu-/netföng" or simply "fylki með netföngum," but the common term for address list in Icelandic related to Bitcoin or networking is "föslisti" or "tölu-/heimilisfangalisti"). The rest of the sentence is okay and format specifier %1 is correctly included.

Correct translation:  
Ekki tókst að vista heimilisfangalistann á %1. Reyndu aftur.
```

```
        <source>Sending addresses - %1</source>
        <translation>heimilisföng - %1 </translation>
    
YES  
The translation misses the word "Sending" before "addresses", so it loses the original meaning. Also, there is an extra trailing space after "%1".  

Correct translation:  
Senda heimilisföng - %1
```

```
        <source>Address</source>
        <translation>Færslugildi</translation>
    
YES  
The English word "Address" in the context of Bitcoin (wallet address or network address) should be translated as "Heimilisfang" in Icelandic. "Færslugildi" means "transaction value" or "entry value," which is incorrect and misleading.  

Correct translation:  
Heimilisfang
```

```
        <source>Show passphrase</source>
        <translation>lykilorð</translation>
    
YES  
The English source is a command or prompt "Show passphrase," which implies displaying the passphrase. The Icelandic word "lykilorð" simply means "password" or "passphrase" but does not convey the action "show." The translation should reflect the action (imperative) to "Show passphrase."  

Correct translation:  
Sýna lykilorðið
```

```
        <source>Your wallet is now encrypted. </source>
        <translation>Veskið þitt er um það bil að vera dulkóðað.</translation>
    
YES  
The translation means "Your wallet is about to be encrypted," which is incorrect because the source states "Your wallet is now encrypted," indicating that the encryption has already been completed, not that it is about to happen.

Correct translation:  
Veskið þitt er nú dulkóðað.
```

```
        <source>Runaway exception</source>
        <translation>Undantekning á flótta</translation>
    
YES  
The Icelandic translation "Undantekning á flótta" is not an accurate rendering of "Runaway exception." The phrase "Undantekning á flótta" literally means "exception on the run" or "exception in flight," which is a literal but awkward and non-idiomatic translation. In Icelandic computer terminology, "runaway exception" is better translated as "ógild undantekning" or "útvanaleg undantekning," reflecting an exception that has escaped normal handling or "runaway."

A better and clearer translation would be:  
"Óstjórnleg undantekning" or "Óstjórnanleg undantekning"  

Therefore, a suitable correction is:  
Óstjórnanleg undantekning
```

```
        <source>Send coins to a Bitcoin address</source>
        <translation>Senda mynt í Bitcoin færslugildi</translation>
    
YES  
The Icelandic word "færslugildi" is incorrect in this context. The correct term for "address" in Bitcoin context is "föng" or "heimilisfang," but "föng" is more commonly used for addresses (including Bitcoin addresses). Also, "Senda mynt í Bitcoin færslugildi" incorrectly uses "í" (in/to) instead of "á" which is the correct preposition for "to an address."  

Correct translation:  
Senda mynt á Bitcoin-föng
```

```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>Sýna færslugildi sem notuð hafa verið til að taka við mynt og merkingar þeirra</translation>
    
YES  
The translation is somewhat inaccurate and adds unnecessary detail not present in the source. The source states: "Show the list of used receiving addresses and labels." The given Icelandic translation means: "Show transaction values that have been used to receive coins and their labels," which is more specific and changes the meaning.

A better translation would be:  
"Sýna lista yfir notaðar viðtakandi heimilisfang og merkingar"
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Sýna %1 hjálparskilaboðin til að fá lista yfir valkosti Bitcoin aðgerðir í skipanalínu</translation>
    
YES  
The translation is mostly understandable but slightly awkward and can be improved for clarity and naturalness in Icelandic. In particular, "valkosti Bitcoin aðgerðir í skipanalínu" is awkwardly ordered and missing a preposition. A better phrasing would be "valkosti fyrir Bitcoin skipanalínu" (options for Bitcoin command-line). Also, the source "command-line options" must be clearly separated as compound noun with correct case.  

Correct translation:  
Sýna %1 hjálparskilaboðin til að fá lista yfir mögulega Bitcoin skipanalínuvalkosti
```

```
        <source>%1 client</source>
        <translation>%1 biðlarar</translation>
    
YES  
The Icelandic word for "client" in this context is "viðskiptavinur" or "kúnni," not "biðlarar." "Biðlarar" is not a correct or meaningful Icelandic word related to this usage and appears erroneous.

Correct translation:  
%1 viðskiptavinur
```

```
        <source>Address: %1
</source>
        <translation>Færslugildi: %1
</translation>
    
YES  
The Icelandic word "Færslugildi" means "transaction value," which is incorrect in the context of "Address." The correct translation for "Address" in Bitcoin context is "Heimilisfang."

Correct translation:  
Heimilisfang: %1
```

```
        <source>Sent transaction</source>
        <translation>Send færsla</translation>
    
YES  
The Icelandic translation incorrectly uses the English word "Send" instead of the Icelandic equivalent. The correct Icelandic translation for "Sent transaction" should use the past tense verb to convey the completed action. A correct translation is:  
"Send færslu" or better: "Send færsla" is incorrect because "Send" is English; instead, use "Sendt færsla" or "Send færsla" is not idiomatic Icelandic.  

The most accurate Icelandic translation for "Sent transaction" in the Bitcoin context is:  
"Send færsla" → incorrect (uses English "Send").  
Better: "Send færslur" = plural, but source is singular.  
Correct should be: "Send færsla" → "Sendt færsla" or "Send færsla" no.  

"Sent transaction" = "Send færsla" → "Sendt færsla" or "Send færslu" depending on grammar.  

Correct phrase: "Sendt færsla" or "Send færslu" (accusative case "færslu")  
But the noun "færsla" is feminine, accusative and nominative singular is "færsla", accusative is "færslu." Since it is the subject, nominative is correct.  

Actually, as a label or status, "Sendt færsla" (Sent transaction) is commonly used in Icelandic interface translations.  

Hence, the correct translation:  
"Sendt færsla"  

Therefore:  

YES  
The translation uses the English verb "Send". The Icelandic translation must use the correct past participle form "Sendt" to indicate a past completed action.  

Correct translation:  
Sendt færsla
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Veskið er &lt;b&gt;dulkóðað&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</translation>
    
YES  
The translation is partially in Icelandic but contains untranslated English words "and currently" and "locked". These should be translated into Icelandic to maintain consistency and correctness.

Correct translation:  
Veskið er &lt;b&gt;dulkóðað&lt;/b&gt; og nú &lt;b&gt;læst&lt;/b&gt;
```

```
        <source>Quantity:</source>
        <translation>Magn:</translation>
    
YES  
The English word "Quantity" should be translated to its correct Icelandic equivalent "Magn:" not "Magn:". The given translation "Magn:" is correct; however, ensure that the colon is included without any trailing spaces. Since the provided translation matches the correct Icelandic word and formatting, there is no need for correction.

Correction: No correction needed; the translation is accurate and properly formatted.
```

```
        <source>Bytes:</source>
        <translation>Bæti:</translation>
    
YES  
The language code 'is' corresponds to Icelandic. The English word "Bytes:" should be translated as "Bætur:" or "Bitar:" in Icelandic when referring to bytes in computing, but "Bæti:" is incorrect because it means "repair" or "patch."  
Correct translation:  
Bitar:
```

```
        <source>(un)select all</source>
        <translation>(af)velja allt</translation>
    
YES  
The Icelandic translation "(af)velja allt" is incorrect. The correct translation for "(un)select all" should reflect the action of selecting and deselecting all items. In Icelandic, a common way to express this is "(aftur)velja allt" or "Velja/afvelja allt". Using "afvelja" (deselect) with "velja" (select) together would be clearer.  

Correct translation:  
"(aftur)velja allt"  
or  
"Velja/afvelja allt"
```

```
        <source>List mode</source>
        <translation>Listahamur</translation>
    
YES  
The translation "Listahamur" is incorrect in Icelandic ('is'). The English phrase "List mode" is best translated as "Listarhamur" in Icelandic, where "listi" means "list" and "hamur" means "mode" or "state."

Correct translation:  
Listarhamur
```

```
        <source>Received with address</source>
        <translation>Móttekið með færslugildi</translation>
    
YES  
The translation "Móttekið með færslugildi" is incorrect and does not accurately convey the meaning of the original English phrase "Received with address." The Icelandic word "færslugildi" means "entry value" or "transaction value," which is unrelated to "address" in the Bitcoin context. The correct Icelandic term for "address" in this Bitcoin context is "heimilisfang."  

Correct translation:  
Móttökutengd heimilisfang
```

```
        <source>Copy transaction ID and output index</source>
        <translation>Afritaðu færslu  auðkenni og úttaksvísitölu</translation>
    
YES  
There is an extra space between "færslu" and "auðkenni" which should not be there. Also, "transaction ID" is better translated as "viðskiptaauðkenni" or "tilvísun viðskipta" in the Bitcoin context to clearly refer to the transaction identifier. The phrase "output index" is correctly translated as "úttaksvísitala," but it should be singular and consistent in spacing and format.

Correct translation:  
Afritaðu færsluauðkenni og úttaksvísitölu
```

```
        <source>Edit Address</source>
        <translation>Breyta færslugildi</translation>
    
YES  
The English source "Edit Address" refers to modifying an address, likely a Bitcoin wallet or network address. The Icelandic translation "Breyta færslugildi" means "Change entry value" or "Change record value," which is not an accurate or appropriate translation for "Edit Address." The correct Icelandic translation should be:

"Breyta heimilisfangi" (if referring to "address" as physical mailing address)  
or  
"Breyta netfangi" (if referring to network address)  
or simply  
"Breyta aðfangareikningi" / "Breyta reikningsfangi" (if referring to wallet address).

Since the context is Bitcoin and "address" likely means a wallet or Bitcoin address, the best correct translation is:

"Breyta netfangi" or "Breyta heimilisfangi" depending on context, but usually "Breyta heimilisfangi" for general purposes.

If the Bitcoin software typically uses "Reikningsfang" or "Wallet address," better:

"Breyta reikningsfangi"

Hence, a good translation is:

Breyta reikningsfangi
```

```
        <source>The label associated with this address list entry</source>
        <translation>Merking tengd þessu færslugildi</translation>
    
YES  
The Icelandic translation misses the word for "list" (lista) to clearly correspond to "address list entry." "færslugildi" is not a correctly used term here and sounds unnatural. A more accurate translation would be:

Merking tengd færslu í þessum heimilislista
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>Færslugildið sem tengt er þessari færslu. Þessu má einungis breyta þegar sent er.</translation>
    
YES  
The translation does not fully convey the original meaning. The original states "The address associated with this address list entry. This can only be modified for sending addresses." The translation says "The transaction value associated with this transaction. This can only be changed when sending," which is incorrect because "færslugildið" means "transaction value," not "address," and the second sentence is vague and does not mention "sending addresses."

Correct translation:  
"Slóðin sem tengist þessari færslu á slóðalista. Þetta má aðeins breyta fyrir sendingarslóðir."
```

```
        <source>Address</source>
        <translation>Nýtt móttökufærslugildi</translation>
    
YES  
The translation "Nýtt móttökufærslugildi" means "New receiving transaction value" or something similar, which is not an accurate translation of the English word "Address" in the context of Bitcoin (which usually refers to a wallet or network address). A more appropriate Icelandic translation for "Address" in this context would be simply "Heimilisfang" (address), or in the Bitcoin context often just "Slóð" (address/location) or "Netfang" (network address), but "Heimilisfang" is commonly used.

Correct translation:  
Heimilisfang
```

```
        <source>New sending address</source>
        <translation>Nýtt sendingarfærslugildi</translation>
    
YES  
The Icelandic translation uses "sendingarfærslugildi," which is an incorrect and unnatural compound. The correct term for "New sending address" in the context of Bitcoin would be "Nýr sendingarfangar" or "Nýr sendirfangur." "Address" in this context is best translated as "fangar" or "fangur."  

Correct translation:  
Nýr sendingarfangar
```

```
        <source>Edit sending address</source>
        <translation>Breyta sendingarfærslugildi</translation>
    
YES  
The Icelandic translation is incorrect and awkward. The phrase "sendingarfærslugildi" is a nonsensical compound and does not correctly translate "sending address." The correct translation for "Edit sending address" in the context of Bitcoin (editing a sending wallet or P2P network address) would be:

Breyta sendingarheimilisfangi
```

```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Færslugildið sem slegið var inn "%1" er ekki leyfilegt Bitcoin færslugildi.</translation>
    
YES  
The translation uses "Færslugildið" which means "transaction value" rather than "address." The correct Icelandic word for "address" in the Bitcoin context is "fangar" or simply "fang" (address), not "færslugildið." Also, "leyfilegt" means "permitted," but "gilt" ("valid") is better here. The corrected translation should reflect that "%1" is not a valid Bitcoin address.

Correct translation:  
Fangurinn „%1“ sem sleginn var inn er ekki gilt Bitcoin-fang.
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>Innistæða færslugilda sem eru einungis til skoðunar</translation>
    
YES  
The translation is somewhat inaccurate and unclear. The original text refers to the "balance" in "watch-only addresses," which in Bitcoin context means the amount of bitcoins in addresses that are monitored but not spendable. The provided translation "Innistæða færslugilda sem eru einungis til skoðunar" translates roughly as "Balance of transaction values which are only for viewing," which is confusing and does not use the standard terminology for "watch-only addresses."

A more accurate translation would be:  
**"Innistæða í einungis til skoðunar-töluðum innfærslum"**  
or more naturally:  
**"Innistæða á einungis til skoðunar-tölum"**  
where "einungis til skoðunar" is a common Icelandic term used for "watch-only" and "tölum" or "föngum" can refer to addresses or funds.

If the terminology from Bitcoin Icelandic community uses a specific term, it should be followed, but the key is to retain "balance" (innistæða) and "watch-only addresses" clearly.

A more precise and natural version:  
**"Innistæða á einungis til skoðunar-töluðum heimilisföngum"**

If the term "heimilisföngum" is used for addresses (wallet addresses).  
So the corrected translation:  
**"Innistæða á einungis til skoðunar heimilisföngum"**
```

```
        <source>Sign Tx</source>
        <translation>Skilti Tx</translation>
    
YES  
The Icelandic verb for "sign" in this context should be the imperative form "Undirrita" instead of "Skilti," which means "sign" as in a physical sign or a placard, not to sign a transaction. Also, "Tx" (short for transaction) is commonly not translated or can be kept as is.  

Correct translation:  
Undirrita Tx
```

```
        <source>Address</source>
        <extracomment>Title of Peers Table column which contains the IP/Onion/I2P address of the connected peer.</extracomment>
        <translation>Færslugildi</translation>
    
YES  
The translation "Færslugildi" means "transaction value" or "transfer value" in Icelandic, which is incorrect for the term "Address." The correct Icelandic translation for "Address" in this context (Bitcoin wallet or network address) is "Heimilisfang."  

Correct translation:  
Heimilisfang
```

```
        <source>Quantity:</source>
        <translation>Magn:</translation>
    
YES  
The English word "Quantity" should be translated to its correct Icelandic equivalent "Magn:" not "Magn:". The given translation "Magn:" is correct; however, ensure that the colon is included without any trailing spaces. Since the provided translation matches the correct Icelandic word and formatting, there is no need for correction.

Correction: No correction needed; the translation is accurate and properly formatted.
```

```
        <source>Bytes:</source>
        <translation>Bæti:</translation>
    
YES  
The language code 'is' corresponds to Icelandic. The English word "Bytes:" should be translated as "Bætur:" or "Bitar:" in Icelandic when referring to bytes in computing, but "Bæti:" is incorrect because it means "repair" or "patch."  
Correct translation:  
Bitar:
```

```
        <source>External signer failure</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Bilun í ytri undirritara</translation>
    
YES  
The translation "Bilun í ytri undirritara" contains errors and is not correct Icelandic. The English phrase "External signer failure" should be translated as "Bilun hjá ytri undirritara" or "Bilun í ytri undirritara" is somewhat understandable, but "Bilun hjá ytri undirritara" is more idiomatic for "failure in/by external signer". The word "bilun" means "fault" or "failure", but "í" (in) is less appropriate than "hjá" (at/by) when referring to a device or entity causing the failure.

Correct translation:  
Bilun hjá ytri undirritara
```

```
        <source>Mined</source>
        <translation>Námuunnið</translation>
    
YES  
The Icelandic translation "Námuunnið" is incorrect and unnatural for the English term "Mined" in the Bitcoin context. The correct Icelandic term would be "Námu" or "Námuvinna" is more noun-like, but since "Mined" here is likely used as a past participle or adjective describing a block or coin as having been mined, the Icelandic past participle of "nám" (to mine) does not involve "Námuunnið." A better translation would simply be:

Námt  
or more accurately  
Námi (meaning "mining" but less common for past participle)

However, in Bitcoin contexts, Icelandic translations often just adopt "Námið" (the mined [one]) or "Námið" (mined) as a past participle adjective.

Hence the suggested correction:

Námið
```

```
        <source>Mined</source>
        <translation>Námuunnið</translation>
    
YES  
The Icelandic translation "Námuunnið" is incorrect and unnatural for the English term "Mined" in the Bitcoin context. The correct Icelandic term would be "Námu" or "Námuvinna" is more noun-like, but since "Mined" here is likely used as a past participle or adjective describing a block or coin as having been mined, the Icelandic past participle of "nám" (to mine) does not involve "Námuunnið." A better translation would simply be:

Námt  
or more accurately  
Námi (meaning "mining" but less common for past participle)

However, in Bitcoin contexts, Icelandic translations often just adopt "Námið" (the mined [one]) or "Námið" (mined) as a past participle adjective.

Hence the suggested correction:

Námið
```

```
        <source>Address</source>
        <translation>Færslugildi</translation>
    
YES  
The English word "Address" in the context of Bitcoin (wallet address or network address) should be translated as "Heimilisfang" in Icelandic. "Færslugildi" means "transaction value" or "entry value," which is incorrect and misleading.  

Correct translation:  
Heimilisfang
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>Flyttu gögnin í núverandi flipa út í skrá                                                                    </translation>
    
YES  
The translation contains excessive trailing whitespace and an incorrect verb choice. The Icelandic verb "Flytja" means "to move" rather than "to export." A better translation should use "Flytja út" or "Flytja gögnin út" to clearly mean "Export," without excessive spaces.

Correct translation:  
Flytja gögnin í núverandi flipa í skrá
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Óstudd flokkasértæk skráningarstig %1$s=%2$s. Búist var við %1$s=:. Gildir flokkar: %3$s. Gild logstig: %4$s.</translation>
    
YES  
The translation has an incomplete phrase for the expected format and some terms could be more precise. The original specifies: "Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;." but the translation says "Búist var við %1$s=:." which omits "<category>:<loglevel>" and the colon. Also, "Gildir flokkar" should be "Gildir flokkar:" (adding the colon for correct enumeration), similarly for "Gild logstig". Additionally, "loglevels" translated as "logstig" is acceptable, but can be improved for clarity.

Correct translation:  
Óstudd flokkasértækt skráningarstig %1$s=%2$s. Búist var við %1$s=&lt;flokkur&gt;:&lt;skráningarstig&gt;. Gildir flokkar: %3$s. Gild skráningarstig: %4$s.
```
</details>
