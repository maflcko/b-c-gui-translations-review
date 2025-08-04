# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>is</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bis%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation>Smelltu á hægri músatakka til að velja veski eða merkingu</translation>
    
YES. The Icelandic translation is incorrect and does not convey the intended meaning. The phrase "Smelltu á hægri músatakka til að velja veski eða merkingu" translates to "Click the right mouse button to select a wallet or meaning". The source text "Right-click to edit address or label" means to right-click to modify the address or label.

The correct translation should be:
"Hægri-smelltu til að breyta heimilisfangi eða merkingu"
```

```
        <source>Create a new address</source>
        <translation>Búa til nýtt veski</translation>
    
YES: The translation is problematic because "veski" means "wallet", but the source text "Create a new address" is more general and could refer to a new Bitcoin network address, not necessarily a new wallet. A more accurate translation would be closer to "Búa til nýtt heimilisfang".
Búa til nýtt heimilisfang
```

```
        <source>Copy the currently selected address to the system clipboard</source>
        <translation>Afrita valið veski í klemmuspjald</translation>
    
YES. The translation contains erroneous content. The source text mentions "address" in the context of Bitcoin, which could refer to a P2P network address or a wallet address. However, the translation uses "veski" (wallet) which narrows the meaning to only a wallet address. The more general and accurate translation for "address" in this context would be "vistfang".

NO. The translation contains erroneous content. The source text refers to copying the selected "address" to the clipboard. The translation uses "veski" (wallet), which is too specific and incorrect as it implies only a wallet address is being copied, whereas "address" could also refer to a network address.

Correct translation: Afrita valið vistfang í klemmuspjald
```

```
        <source>Enter address or label to search</source>
        <translation>Veldu veski eða merkingu fyrir leit</translation>
    
YES
The translation is inaccurate and uses the wrong Icelandic terms for "address" and "search". The word "Veldu" which translates to "Choose" is incorrect in this context, and "leit" which means "search" is not used in the translation.

Correct translation: Sláðu inn heimilisfang eða merki til að leita
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>Flyttu gögnin í núverandi flipa út í skrá                                                                    </translation>
    
YES: The translation contains extraneous whitespace at the end.
Flyttu gögnin í núverandi flipa út í skrá
```

```
        <source>Choose the address to send coins to</source>
        <translation>Veldu veski sem greiða skal til</translation>
    
YES, The translation is problematic because it does not accurately reflect the meaning of the source text. The source text "Choose the address to send coins to" refers to a Bitcoin wallet address or a P2P Bitcoin network address. The translation "Veldu veski sem greiða skal til" translates to "Choose the wallet to pay to", which is a correct translation in isolation but might not be precise enough for the context of Bitcoin. The word "address" can refer to more than just a wallet, and in Bitcoin, sending to an address doesn't necessarily mean paying *to* a wallet in the sense of completing a transaction.

A more accurate translation would be:

Veldu heimilisfang til að senda mynt til
```

```
        <source>Choose the address to receive coins with</source>
        <translation>Veldu veski til að taka við rafmynt</translation>
    
YES - The translation is inaccurate and lacks context. In Bitcoin, "address" refers to a specific Bitcoin wallet address, not the entire wallet itself. The translation also uses "rafmynt" which is a general term for cryptocurrency and not specific to Bitcoin.

Correct translation: Veldu heimilisfang til að taka við myntu
```

```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>Þetta eru Bitcoin veskin sem senda greiðslur. Skoðið ævinlega vel upphæðina og veskin sem þiggja greiðslur áður en rafmynt er send.</translation>
    
YES: The translation incorrectly states that the addresses are for *sending* payments, when they are in fact for *receiving* payments. Also, the phrasing "always check the amount and the receiving address before sending coins" is slightly awkward in the Icelandic translation.

A more accurate translation would be:

Þetta eru Bitcoin veskin þín til að taka á móti greiðslum. Athugaðu alltaf upphæðina og móttökufangið áður en þú sendir mynt.
```

```
        <source>Copy Address</source>
        <translation>Afrita færslugildi</translation>
    
YES, The translation is problematic because "Afrita færslugildi" translates to "Copy transaction value", not "Copy Address". The correct translation for "Copy Address" in Icelandic is "Afrita heimilisfang".
Afrita heimilisfang
```

```
        <source>Export Address List</source>
        <translation>Flytja út færslulista</translation>
    
YES - The translation is incorrect. "Flytja út færslulista" translates to "Export transaction list", not "Export Address List".

Correct translation: Flytja út heimilisfangalista
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Ekki tókst að vista færslugildalistann á %1. Reyndu aftur.</translation>
    
YES: The word "færslugildalistann" is an incorrect translation of "address list". The correct translation for "address list" in this context would be "vistfangalista".
NO: There was an error trying to save the address list to %1. Please try again.
```

```
        <source>Sending addresses - %1</source>
        <translation>heimilisföng - %1 </translation>
    
YES: The translation has an extra space after the format specifier.
Sending addresses - %1
```

```
        <source>Address</source>
        <translation>Færslugildi</translation>
    
YES. The Icelandic translation "Færslugildi" means "transaction value" or "transfer value" and does not accurately translate "Address". In the context of Bitcoin, "Address" refers to a Bitcoin wallet address.

The correct translation for "Address" in this context is "Heimilisfang".

NO
```

```
        <source>(no label)</source>
        <translation>(engin merking)</translation>
    
YES
The translation "engin merking" is inaccurate and does not convey the intended meaning of "(no label)". The correct translation would be "(ekki merkt)".

(ekki merkt)
```

```
        <source>Show passphrase</source>
        <translation>lykilorð</translation>
    
YES. The translation is inaccurate and does not convey the meaning of the source text. The Icelandic word for "passphrase" is "lykilorð", but the source text is "Show passphrase". The correct translation should be "Sýna lykilorð".

Sýna lykilorð
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>Þessi aðgerð þarf að fá lykilsetninguna þína til að opna veskið.</translation>
    
YES - The Icelandic translation uses "lykilsetninguna" which translates to "key phrase" or "key sentence". However, the English source text refers to "wallet passphrase", which is more akin to a password or a security phrase. A more appropriate translation would be "lykilorðið" (passphrase/password) or "aðgangsorðið" (access word/password). The current translation is misleading.

Correct translation: Þessi aðgerð þarf að fá lykilorðið þitt til að opna veskið.
```

```
        <source>Your wallet is now encrypted. </source>
        <translation>Veskið þitt er um það bil að vera dulkóðað.</translation>
    
YES: The Icelandic translation "Veskið þitt er um það bil að vera dulkóðað" translates to "Your wallet is about to be encrypted," which is not an accurate translation of "Your wallet is now encrypted." The use of "um það bil að" (about to) implies an incomplete or future action, whereas "now" indicates a completed or present action.

The correct translation should convey that the encryption is complete.

Correct translation: Veskið þitt er nú dulkóðað.
```

```
        <source>IP/Netmask</source>
        <translation>IP/Netgríma</translation>
    
YES - The translation contains a typographical error in "Netgríma". The correct word is "Netgríma".
IP/Netgríma
```

```
        <source>Runaway exception</source>
        <translation>Undantekning á flótta</translation>
    
YES - The translation is a literal translation of "Runaway exception" which does not make sense in the context of Bitcoin. It is likely that the original English text was mistyped or a non-standard term. If "runaway exception" is intended to mean an unexpected or uncontrolled exception, a better translation would be "Óvænt undantekning" or "Óstýranlegt undantekning". However, without further context, it is impossible to provide a definitive correction.

Óvænt undantekning
```

```
        <source>Error: %1</source>
        <translation>Villa: %1</translation>
    
YES
The word "Villa" in Icelandic means "house" or "mansion," which is not a suitable translation for "Error" in the context of Bitcoin. The correct translation for "Error" is "Villa" or "Galli".

The correct translation should be:
        <source>Error: %1</source>
        <translation>Villa: %1</translation>
```

```
        <source>Send coins to a Bitcoin address</source>
        <translation>Senda mynt í Bitcoin færslugildi</translation>
    
YES: The word "færslugildi" translates to "transaction value" or "transaction unit" in English. The correct translation for "address" in the context of Bitcoin is "heimilisfang".

NO
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Kvitta undir skilaboð með Bitcoin færslugildunum þínum til að sanna að þú eigir þau</translation>
    
YES. The translation uses an incorrect word for "addresses". "Færslugildum" means transaction values, not addresses.

NO. Kvitta undir skilaboð með Bitcoin vistföngunum þínum til að sanna að þú eigir þau
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Yfirfara skilaboð til að tryggja að kvittað hafi verið fyrir þau með tilteknum Bitcoin færslugildum</translation>
    
YES - The translation is problematic because "færslugildum" is not the correct Icelandic word for "addresses" in this context. In Icelandic, "færslugildi" refers to transaction values, not addresses. The correct translation for Bitcoin addresses is "slóðir".

NO
- "Yfirfara skilaboð til að tryggja að kvittað hafi verið fyrir þau með tilteknum Bitcoin slóðum"
```

```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>Sýna færslugildi sem notuð hafa verið til að taka við mynt og merkingar þeirra</translation>
    
YES: The translation is problematic as it incorrectly translates "receiving addresses" to "færslugildi" (transaction values). It should refer to Bitcoin addresses.

Correct translation: Sýna lista yfir notuð móttöku heimilisföng og merkingar þeirra
```

```
        <source>%1 behind</source>
        <translation>%1 á eftir</translation>
    
YES. The translation is problematic because the phrase "%1 behind" in the context of Bitcoin usually refers to a transaction that has been processed or included in a block, meaning it's not an error. However, "%1 á eftir" in Icelandic literally translates to "%1 after" or "%1 behind" in a temporal sense, which could be misleading in a Bitcoin context and might imply an error or delay that isn't intended.

The correct translation would depend on the exact intended meaning of "behind" in the source text. If it means "confirmed" or "processed," then a more appropriate translation would be needed. If it's a literal countdown or progress indicator, then "%1 á eftir" might be acceptable, but it's still ambiguous in a financial/transactional context.

Given the ambiguity and potential for misinterpretation, a better translation might be:

Correct translation: "%1 staðfestur" (if referring to confirmation) or "%1 í bið" (if referring to being in a pending state). Without more context on what "%1 behind" specifically refers to in the Bitcoin transaction flow, it's hard to give a definitive correction. However, "%1 á eftir" is not ideal.

NO
```

```
        <source>Error</source>
        <translation>Villa</translation>
    
YES: The Icelandic word for "error" is "villa", which is a correct translation. However, "Villa" with a capital V is not the correct Icelandic word for error. The correct translation would be "villa".
YES: Villa
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Sýna %1 hjálparskilaboðin til að fá lista yfir valkosti Bitcoin aðgerðir í skipanalínu</translation>
    
YES - The translation is grammatically incorrect and unnatural. The phrase "valkosti Bitcoin aðgerðir í skipanalínu" translates to "options Bitcoin actions in command line", which is not idiomatic. A more natural translation would be "valkosti fyrir Bitcoin-skipanalínu" meaning "options for Bitcoin command line".
Sýna %1 hjálparskilaboðin til að fá lista yfir valkosti fyrir Bitcoin-skipanalínu
```

```
        <source>%1 client</source>
        <translation>%1 biðlarar</translation>
    
YES. The translation for "%1 client" is incorrect. The Icelandic word for "client" is typically "viðskiptavinur" or "skjólstæðingur" depending on context, not "biðlarar" which means "seekers" or "petitioners".

Correct translation: %1 viðskiptavinur
```

```
        <source>Error: %1</source>
        <translation>Villa: %1</translation>
    
YES
The word "Villa" in Icelandic means "house" or "mansion," which is not a suitable translation for "Error" in the context of Bitcoin. The correct translation for "Error" is "Villa" or "Galli".

The correct translation should be:
        <source>Error: %1</source>
        <translation>Villa: %1</translation>
```

```
        <source>Address: %1
</source>
        <translation>Færslugildi: %1
</translation>
    
YES
The translation is incorrect. The Icelandic word "Færslugildi" translates to "transaction value" or "transfer value" in English, not "Address".

Correct translation:
Address: %1
```

```
        <source>Sent transaction</source>
        <translation>Send færsla</translation>
    
YES
The translation uses an incorrect Icelandic word for "transaction." The correct translation for "transaction" in Icelandic is "viðskipti" or "færslur."

NO
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Veskið er &lt;b&gt;dulkóðað&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</translation>
    
YES - The word "and" is not translated. The correct translation is: Veskið er &lt;b&gt;dulkóðað&lt;/b&gt; og &lt;b&gt;læst&lt;/b&gt;
```

```
        <source>Quantity:</source>
        <translation>Magn:</translation>
    
YES. The translation of "Quantity" to "Magn" is not appropriate in the context of Bitcoin. "Magn" can be interpreted as "magnitude," which is not the standard term for quantity in this domain. The correct translation for "Quantity" in a Bitcoin context would be "Množství".

NO.
```

```
        <source>Bytes:</source>
        <translation>Bæti:</translation>
    
YES: The translation uses an incorrect Icelandic word for "Bytes". The correct translation should be "Tengi".
Bytes: Tengi:
```

```
        <source>After Fee:</source>
        <translation>Eftirgjald:</translation>
    
YES: The translation is inaccurate. "Eftirgjald" means "after payment" or "refund" in Icelandic. The correct translation for "After Fee:" in the context of Bitcoin transactions should be "Eftir þóknun:".
Eftir þóknun:
```

```
        <source>(un)select all</source>
        <translation>(af)velja allt</translation>
    
YES, The translation is problematic. The source text "(un)select all" contains a parenthetical element that is not handled correctly in the translation. The translated text "(af)velja allt" seems to be an attempt to translate "unselect all" but it doesn't maintain the structure of the original English.

The correct translation should maintain the parenthetical structure to convey the dual meaning of selecting and unselecting.

Correct translation: (velja allt / afvelja allt)
```

```
        <source>List mode</source>
        <translation>Listahamur</translation>
    
YES. The translation uses an invented word "Listahamur" which is not a valid Icelandic word for "List mode". The correct translation for "List mode" in Icelandic is "Listahamur".
Listahamur
```

```
        <source>Received with address</source>
        <translation>Móttekið með færslugildi</translation>
    
YES. The Icelandic translation is incorrect and does not convey the meaning of the English source text in the context of Bitcoin. "Móttekið með færslugildi" translates to "Received with transaction value," which is not related to a Bitcoin address.

Correct translation: "Móttekið með heimilisfangi" (Received with address).
```

```
        <source>Copy transaction ID and output index</source>
        <translation>Afritaðu færslu  auðkenni og úttaksvísitölu</translation>
    
YES - The translation is problematic. "Afritaðu" means "copy" but it is grammatically incorrect in Icelandic. "Færslu" means "transaction" but it should be in the genitive case. "Auðkenni" means "identifier" but it should be in the genitive case. "Úttaksvísitölu" means "output index" but it should be in the genitive case. The correct translation is "Afritaðu færslunnar auðkenni og úttaksvísitölu".
```

```
        <source>(no label)</source>
        <translation>(engin merking)</translation>
    
YES
The translation "engin merking" is inaccurate and does not convey the intended meaning of "(no label)". The correct translation would be "(ekki merkt)".

(ekki merkt)
```

```
        <source>Too many external signers found</source>
        <translation>Of margir ytri undirritarar fundust</translation>
    
YES: The translation is inaccurate and contains a grammatical error. The correct translation should be "Of margir ytri undirskrifarar fundust".
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Samið án utanaðkomandi undirskriftarstuðnings (krafist fyrir utanaðkomandi undirskrift)</translation>
    
YES. The Icelandic translation is a literal word-for-word translation that does not sound natural and might be confusing to a native speaker. The phrase "utanaðkomandi undirskriftarstuðnings" is grammatically incorrect in this context.

A more natural and accurate translation would be:

YES. Samið án stuðnings fyrir utanaðkomandi undirskrift (þörf fyrir utanaðkomandi undirskrift)
```

```
        <source>Edit Address</source>
        <translation>Breyta færslugildi</translation>
    
YES: The translation of "Edit Address" to "Breyta færslugildi" is incorrect and misleading in the context of Bitcoin. "Færslugildi" translates to "transaction value" or "entry value," which does not relate to editing a Bitcoin address. A correct translation would be "Breyta heimilisfangi."
Breyta heimilisfangi
```

```
        <source>The label associated with this address list entry</source>
        <translation>Merking tengd þessu færslugildi</translation>
    
YES - The translation uses "færslugildi" which means "entry value". In this context, it should be "heimilisfang" which means "address".

The label associated with this address list entry - Merking tengd þessu heimilisfangi
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>Færslugildið sem tengt er þessari færslu. Þessu má einungis breyta þegar sent er.</translation>
    
YES: The Icelandic translation is inaccurate and doesn't convey the meaning of the English source text. The word "færslugildið" which translates to "transaction value" or "stake" is incorrectly used instead of "address". Additionally, "færslu" in the second sentence, meaning "entry" or "posting", does not fit the context of modifying an address. The phrase "þegar sent er" (when sending) also doesn't fully capture the nuance of "for sending addresses."

A more accurate translation would be: "Heimilisfangið sem tengist þessari heimilsfangaskrá. Þetta er aðeins hægt að breyta fyrir sendanleg heimilisföng."
```

```
        <source>Address</source>
        <translation>Nýtt móttökufærslugildi</translation>
    
YES - The translation "Nýtt móttökufærslugildi" is incorrect and does not mean "Address" in the context of Bitcoin. It translates to "New receiving value", which is nonsensical for a Bitcoin address. The correct translation for "Address" in Icelandic in this context is "Heimilisfang".

NO
```

```
        <source>New sending address</source>
        <translation>Nýtt sendingarfærslugildi</translation>
    
YES
The translation uses a word for "value" instead of "address".
New sending address
```

```
        <source>Edit receiving address</source>
        <translation>Breyta móttökufærslugildi</translation>
    
YES
The translation uses the Icelandic word "færslugildi" which translates to "transaction value" or "entry value." The correct term for "address" in Icelandic, especially in the context of Bitcoin, is "heimilisfang."

Breyta móttökuheimilisfangi
```

```
        <source>Edit sending address</source>
        <translation>Breyta sendingarfærslugildi</translation>
    
YES, The translation is problematic because it doesn't accurately convey the meaning of "sending address" in the context of Bitcoin. "Færslugildi" means "transaction value", which is incorrect.

The correct translation should be:

Breyta heimilisfangi sendanda
```

```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Færslugildið sem slegið var inn "%1" er ekki leyfilegt Bitcoin færslugildi.</translation>
    
YES - The translation is problematic because "færslugildi" means "transaction value" or "transaction amount" in Icelandic, not "address". The word "address" in the context of Bitcoin refers to a specific string of characters used to send or receive Bitcoin, not its value. The correct translation for "address" in this context would be "heimilisfang" or "slóð".

Correct translation: Færslugildið sem slegið var inn "%1" er ekki gilt Bitcoin heimilisfang.
```

```
        <source>Error</source>
        <translation>Villa</translation>
    
YES: The Icelandic word for "error" is "villa", which is a correct translation. However, "Villa" with a capital V is not the correct Icelandic word for error. The correct translation would be "villa".
YES: Villa
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Samið án utanaðkomandi undirskriftarstuðnings (krafist fyrir utanaðkomandi undirskrift)</translation>
    
YES. The Icelandic translation is a literal word-for-word translation that does not sound natural and might be confusing to a native speaker. The phrase "utanaðkomandi undirskriftarstuðnings" is grammatically incorrect in this context.

A more natural and accurate translation would be:

YES. Samið án stuðnings fyrir utanaðkomandi undirskrift (þörf fyrir utanaðkomandi undirskrift)
```

```
        <source>Error</source>
        <translation>Villa</translation>
    
YES: The Icelandic word for "error" is "villa", which is a correct translation. However, "Villa" with a capital V is not the correct Icelandic word for error. The correct translation would be "villa".
YES: Villa
```

```
        <source>Mined balance that has not yet matured</source>
        <translation>Námuunnin innistæða sem hefur enn ekki komið fram</translation>
    
YES: The translation is problematic because it uses a non-existent word "námuunnin". The correct word for "mined" in this context would be "námuð" or "unnið".

NO
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>Innistæða færslugilda sem eru einungis til skoðunar</translation>
    
YES - The translation is problematic as it misinterprets "watch-only addresses". The Icelandic translation suggests "addresses of payable values that are only for viewing", which is not the correct meaning. "Watch-only addresses" in Bitcoin refers to addresses for which you can view the balance and transaction history but cannot spend from.

Correct translation: „Innistæða þín á aðeins-á-skoða heimilisföng“
```

```
        <source>Unconfirmed transactions to watch-only addresses</source>
        <translation>Óstaðfestar færslur til færslugilda sem eru einungis til skoðunar</translation>
    
YES - The translation uses an awkward and unnatural phrasing. "færslugilda sem eru einungis til skoðunar" is a very literal and clunky translation of "watch-only addresses". A more natural and idiomatic translation would be "einskilt-skoðaðar heimilisföng" or "aðgangslaus heimilisföng".

Correct translation: Óstaðfestar færslur til einskilt-skoðaðra heimilisfanga
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>Námuunnin innistæða á færslugildum sem eru einungis til skoðunar og hafa ekki komið fram</translation>
    
YES: The translation uses an incorrect Icelandic term for "watch-only addresses". The term "færslugildum" translates to "transaction values" or "transaction IDs" and is not appropriate in this context. The term "komið fram" is also a mistranslation of "matured".

Correct translation: Námuunnin innistæða á aðgangum sem eru einungis til skoðunar og hafa ekki þroskast.
```

```
        <source>Current total balance in watch-only addresses</source>
        <translation>Innistæða á færslugildum sem eru einungis til skoðunar</translation>
    
YES. The translation is problematic because it incorrectly translates "balance" to "færslugildum" which means "transaction amounts" or "transaction values" rather than "balance" or "innistæða".

The correct translation should be:
NO. Current total balance in watch-only addresses
```

```
        <source>Sign Tx</source>
        <translation>Skilti Tx</translation>
    
YES
The translation is inaccurate. "Skilti Tx" does not convey the intended meaning of "Sign Tx".
Correct translation: Undirrita Tx
```

```
        <source>Address</source>
        <extracomment>Title of Peers Table column which contains the IP/Onion/I2P address of the connected peer.</extracomment>
        <translation>Færslugildi</translation>
    
YES: The Icelandic translation "Færslugildi" translates to "Transaction value" or "Transfer value", which is not accurate for an address. The correct translation for "Address" in this context would be "Heimilisfang".
NO
The Icelandic translation for "Address" in the context of Bitcoin (IP/Onion/I2P address of a connected peer) should be "Heimilisfang". The provided translation "Færslugildi" means "Transaction value" or "Transfer value", which is incorrect.

YES: Færslugildi means "transfer value", not "address".
Heimilisfang
```

```
        <source>The total number of addresses received from this peer that were processed (excludes addresses that were dropped due to rate-limiting).</source>
        <extracomment>Tooltip text for the Addresses Processed field in the peer details area, which displays the total number of addresses received from this peer that were processed (excludes addresses that were dropped due to rate-limiting).</extracomment>
        <translation>Heildarfjöldi heimilisfönga sem berast frá þessum jafningja sem voru unnin (án utan heimilisföng sem voru sleppt vegna gjaldtakmarkana).</translation>
    
YES - The translation is grammatically incorrect and doesn't accurately convey the meaning of the source text. It also has a formatting error with the word "utan" which seems out of place and incorrect. A more accurate translation would be:

"Heildarfjöldi heimilisfanga sem móttekin voru frá þessum jafningja sem var unnin (útilokar heimilisföng sem féllu vegna takmarkana á hraða)."
```

```
        <source>v1: unencrypted, plaintext transport protocol</source>
        <extracomment>Explanatory text for v1 transport type.</extracomment>
        <translation>v1: ódulkóðuð, látlaus flutningsaðferð</translation>
    
YES
The translation contains an unknown word "ódulkóðuð". The correct Icelandic word for "unencrypted" is "ódulkóðuð" which is correct. The correct translation for "plaintext transport protocol" is "efnisflutnings samskiptareglur".

v1: ódulkóðuð, látlaus efnisflutnings samskiptareglur
```

```
        <source>(no label)</source>
        <translation>(engin merking)</translation>
    
YES
The translation "engin merking" is inaccurate and does not convey the intended meaning of "(no label)". The correct translation would be "(ekki merkt)".

(ekki merkt)
```

```
        <source>Quantity:</source>
        <translation>Magn:</translation>
    
YES. The translation of "Quantity" to "Magn" is not appropriate in the context of Bitcoin. "Magn" can be interpreted as "magnitude," which is not the standard term for quantity in this domain. The correct translation for "Quantity" in a Bitcoin context would be "Množství".

NO.
```

```
        <source>Bytes:</source>
        <translation>Bæti:</translation>
    
YES: The translation uses an incorrect Icelandic word for "Bytes". The correct translation should be "Tengi".
Bytes: Tengi:
```

```
        <source>After Fee:</source>
        <translation>Eftirgjald:</translation>
    
YES: The translation is inaccurate. "Eftirgjald" means "after payment" or "refund" in Icelandic. The correct translation for "After Fee:" in the context of Bitcoin transactions should be "Eftir þóknun:".
Eftir þóknun:
```

```
        <source>External signer failure</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Bilun í ytri undirritara</translation>
    
YES - The translation "Bilun í ytri undirritara" means "Malfunction in external signer", which is not a correct translation for "External signer failure". The correct translation should convey the meaning of a failure or error occurring with an external signer.
External signer failure
```

```
        <source>(no label)</source>
        <translation>(engin merking)</translation>
    
YES
The translation "engin merking" is inaccurate and does not convey the intended meaning of "(no label)". The correct translation would be "(ekki merkt)".

(ekki merkt)
```

```
        <source>Mined</source>
        <translation>Námuunnið</translation>
    
YES: The translation uses an unusual form of the past participle of 'to mine' in Icelandic. A more common and appropriate translation in the context of Bitcoin mining would be "Meynt".
Meynt
```

```
        <source>(no label)</source>
        <translation>(engin merking)</translation>
    
YES
The translation "engin merking" is inaccurate and does not convey the intended meaning of "(no label)". The correct translation would be "(ekki merkt)".

(ekki merkt)
```

```
        <source>Mined</source>
        <translation>Námuunnið</translation>
    
YES: The translation uses an unusual form of the past participle of 'to mine' in Icelandic. A more common and appropriate translation in the context of Bitcoin mining would be "Meynt".
Meynt
```

```
        <source>Address</source>
        <translation>Færslugildi</translation>
    
YES. The Icelandic translation "Færslugildi" means "transaction value" or "transfer value" and does not accurately translate "Address". In the context of Bitcoin, "Address" refers to a Bitcoin wallet address.

The correct translation for "Address" in this context is "Heimilisfang".

NO
```

```
        <source>Error</source>
        <translation>Villa</translation>
    
YES: The Icelandic word for "error" is "villa", which is a correct translation. However, "Villa" with a capital V is not the correct Icelandic word for error. The correct translation would be "villa".
YES: Villa
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>Flyttu gögnin í núverandi flipa út í skrá                                                                    </translation>
    
YES: The translation contains extraneous whitespace at the end.
Flyttu gögnin í núverandi flipa út í skrá
```

```
        <source>Error loading wallet. Wallet requires blocks to be downloaded, and software does not currently support loading wallets while blocks are being downloaded out of order when using assumeutxo snapshots. Wallet should be able to load successfully after node sync reaches height %s</source>
        <translation>Villa við að hlaða veski. Veski krefst þess að kubbum sé hlaðið niður og hugbúnaður styður ekki hleðslu veski eins og er á meðan verið er að hlaða niður kubbum úr röð þegar assumeutxo skyndimyndir eru notaðar. Veski ætti að geta hlaðið upp eftir að hnútsamstilling nær hæð %s</translation>
    
YES: The Icelandic translation is not accurate and uses an incorrect word for "wallet". The word "villa" means "house" or "mansion", not "error".
NO: Villa við að hlaða veski. Veski krefst þess að kubbum sé hlaðið niður og hugbúnaður styður ekki hleðslu veski eins og er á meðan verið er að hlaða niður kubbum úr röð þegar assumeutxo skyndimyndir eru notaðar. Veski ætti að geta hlaðið upp eftir að hnútsamstilling nær hæð %s
```

```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Villa: Skráning á sorpskráarsniði er röng. Fékk "%s", búist við "sniði".</translation>
    
YES. The translation is problematic because the word "Villa" in Icelandic means "villa" or "mansion", which is completely unrelated to the context of Bitcoin and the word "Error". The correct translation for "Error" in this context would be "Villa" or "Mistak".

NO
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>Villa: Auðkennisskrá dumpfile er röng. Fékk "%s", bjóst við "%s".</translation>
    
YES. The translation uses "Villa" which translates to "house" or "villa" in English and is completely unrelated to the Bitcoin context. The correct translation should use "Villa" replaced with "Villa" for the error message.

Correct translation: Villa: Auðkennisskrá dumpfile er röng. Fékk "%s", bjóst við "%s".
```

```
        <source>Prune mode is incompatible with -reindex-chainstate. Use full -reindex instead.</source>
        <translation>Prune háttur er ósamrýmanlegur -reindex-chainstate. Notaðu fulla -reindex í staðinn.</translation>
    
YES - The Icelandic translation uses "háttur" which means "manner" or "mode" which is not the correct term for "mode" in the context of software settings. The correct term is "stilling" or "skilyrði". Also, "ósamrýmanlegur" should be "ósamrýmanlegt" to agree with "Prune háttur".

Correct translation: Prune stilling er ósamrýmanleg -reindex-chainstate. Notaðu fulla -reindex í staðinn.
```

```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of pruned node)</source>
        <translation>Prune: síðasta samstilling veskis fer út fyrir klippt gögn. Þú þarft að endurtryggja (hala niður öllu blockchain aftur ef um er að ræða klipptan hnút)</translation>
    
YES: The Icelandic translation uses "endurtryggja" which means "re-insure" or "re-secure", rather than the intended meaning of "reindex". The correct Icelandic word for "reindex" in this context would be "endurvísa".

NO: Prune: síðasta samstilling veskis fer út fyrir klippt gögn. Þú þarft að endurvísa (hala niður öllu blockchain aftur ef um er að ræða klipptan hnút)
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Þetta er hámarks viðskiptagjaldið sem þú greiðir (til viðbótar við venjulega gjaldið) til að forgangsraða að hluta til að forðast eyðslu fram yfir venjulegt myntval.</translation>
    
YES: The translation uses "að hluta til að forðast eyðslu" which is a literal translation of "partial spend avoidance" and doesn't quite capture the intended meaning in the context of Bitcoin transactions. The phrase "regular coin selection" is also translated as "venjulegt myntval", which is a bit too literal. A more natural and accurate translation in this context would focus on the concept of "avoiding partially spending UTXOs" or "prioritizing avoiding partially spending outputs".

Correct translation: Þetta er hámarks viðskiptagjaldið sem þú greiðir (til viðbótar við venjulega gjaldið) til að forgangsraða því að forðast að eyða hluta af útgöngum fram yfir venjulegt myntval.
```

```
        <source>Total length of network version string (%i) exceeds maximum length (%i). Reduce the number or size of uacomments.</source>
        <translation>Heildarlengd netútgáfustrengs (%i) fer yfir hámarkslengd (%i). Fækkaðu fjölda eða stærð ua athugasemda.</translation>
    
YES: The translation uses a misspelling of "uacomments". The correct translation should be "uacomments".
Heildarlengd netútgáfustrengs (%i) fer yfir hámarkslengd (%i). Fækkaðu fjölda eða stærð uacomments.
```

```
        <source>Unable to replay blocks. You will need to rebuild the database using -reindex-chainstate.</source>
        <translation>Ekki hægt að spila kubba aftur. Þú þarft að endurbyggja gagnagrunninn með því að nota -reindex-chainstate.</translation>
    
YES - The translation contains an error in word choice. "Spila" means "to play" in Icelandic, but in this context, it should be "endurtaka" (repeat) or "endursending" (resend).

Correct translation: Ekki hægt að endurtaka kubba. Þú þarft að endurbyggja gagnagrunninn með því að nota -reindex-chainstate.
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Óstudd flokkasértæk skráningarstig %1$s=%2$s. Búist var við %1$s=:. Gildir flokkar: %3$s. Gild logstig: %4$s.</translation>
    
YES: The translation is missing part of the expected format in the "Expected" clause.
Óstudd flokkasértæk skráningarstig %1$s=%2$s. Búist var við %1$s=&lt;category&gt;:&lt;loglevel&gt;. Gildir flokkar: %3$s. Gild logstig: %4$s.
```

```
        <source>You need to rebuild the database using -reindex to go back to unpruned mode.  This will redownload the entire blockchain</source>
        <translation>Þú þarft að endurbyggja gagnagrunninn með því að nota -reindex til að fara aftur í óklippta stillingu. Þetta mun hlaða niður öllu blockchain aftur</translation>
    
UNK_LANG
```

```
        <source>Error loading %s: External signer wallet being loaded without external signer support compiled</source>
        <translation>Villa við að hlaða %s: Ytra undirritaraveski verið hlaðið án þess að utanaðkomandi undirritarastuðningur hafi verið settur saman</translation>
    
YES - The translation of "External signer wallet" to "Ytra undirritaraveski" is not entirely accurate. "External signer" should be translated as "utanaðkomandi undirritari". Also, "being loaded without external signer support compiled" is translated as "verið hlaðið án þess að utanaðkomandi undirritarastuðningur hafi verið settur saman", which is a bit awkward. A more natural phrasing would be "án þess að utanaðkomandi undirritaraaðstoð sé til staðar."

Error loading %s: External signer wallet being loaded without external signer support compiled
Villa við að hlaða %s: Ytra undirritaraveski er hlaðið án stuðnings fyrir utanaðkomandi undirritara
```

```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on enormous cluster of unconfirmed transactions.</source>
        <translation>Mistókst að reikna út högggjöld vegna þess að óstaðfest UTXO er háð gríðarlegum hópi óstaðfestra viðskipta.</translation>
    
YES. The translation incorrectly uses the singular form "UTXO" in Icelandic when the source text uses the plural form "UTXOs".

Correct translation: Mistókst að reikna út högggjöld vegna þess að óstaðfest UTXO eru háð gríðarlegum hópi óstaðfestra viðskipta.
```
</details>
