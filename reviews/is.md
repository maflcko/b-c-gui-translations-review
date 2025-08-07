# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>is</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bis%5D%20low%20quality)


```
        <source>Create a new address</source>
        <translation>Búa til nýtt veski</translation>
    
YES
The translation inaccurately translates "address" as "veski" (wallet). The correct Icelandic word for "address" in the context of Bitcoin would be "fang" or "lykilorð", but "fang" is standard for "address".

Correct translation:
Búa til nýtt fang
```

```
        <source>Copy the currently selected address to the system clipboard</source>
        <translation>Afrita valið veski í klemmuspjald</translation>
    
YES
The translation is inaccurate. The English phrase is "Copy the currently selected address to the system clipboard," while the Icelandic translation says "Afrita valið veski í klemmuspjald" which means "Copy the selected wallet to the clipboard." The word "address" is mistranslated as "veski" (wallet) instead of "address" ("fang" or "vistfang").

Correct translation:
Afrita valið vistfang í klemmuspjald
```

```
        <source>Enter address or label to search</source>
        <translation>Veldu veski eða merkingu fyrir leit</translation>
    
YES
The Icelandic translation is inaccurate. "Veldu veski eða merkingu fyrir leit" translates as "Select wallet or label for search," which does not convey "Enter address or label to search." The verb "enter" should be translated as "Sláðu inn" or "Settu inn" in Icelandic, and "address" as "fang" or, in the Bitcoin context, "wallet address". Furthermore, "veski" means "wallet" rather than "address".

Correct translation:
Sláðu inn vistfang eða merkingu til að leita
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>Flyttu gögnin í núverandi flipa út í skrá                                                                    </translation>
    
YES
There is unnecessary trailing whitespace at the end of the translation.

Correct translation:
Flyttu gögnin í núverandi flipa út í skrá
```

```
        <source>Choose the address to send coins to</source>
        <translation>Veldu veski sem greiða skal til</translation>
    
YES
The translation is inaccurate. "Veldu veski sem greiða skal til" translates as "Choose the wallet to pay to," but the source refers specifically to "address" (which can mean a Bitcoin address, not a wallet). The Icelandic word for "address" in the Bitcoin context is "aðili" or more commonly "færslureikningur", but usually "heimilisfang" or simply "addressa" (loan word) is used among Icelandic crypto users.

Correct translation:
Veldu addressu sem þú vilt senda myntunum til
```

```
        <source>Choose the address to receive coins with</source>
        <translation>Veldu veski til að taka við rafmynt</translation>
    
YES
The translation changes the meaning: "Veldu veski til að taka við rafmynt" translates to "Choose wallet to receive cryptocurrency," instead of "Choose the address to receive coins with." The original specifies "address," not "wallet," and "coins," not the generic "cryptocurrency."

Correct translation:
Veldu vistfangið til að taka við myntum
```

```
        <source>Copy Address</source>
        <translation>Afrita færslugildi</translation>
    
YES
The translation is inaccurate. "Afrita færslugildi" means "Copy transaction value" or "Copy transaction attribute", which is unrelated to copying an address.

Correct translation:
Afrita vistfang
```

```
        <source>Export Address List</source>
        <translation>Flytja út færslulista</translation>
    
YES
The translation "Flytja út færslulista" means "Export entry list" or "export transaction list" rather than "Export Address List." The word "address" should be translated as "vistfang" (for general use), or "heimilisfang" (for physical addresses), but in the Bitcoin context, "address" is usually translated as "vistfang". "Færslulisti" refers to transactions/entries.

Correct translation:
Flytja út vistfangalista
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Ekki tókst að vista færslugildalistann á %1. Reyndu aftur.</translation>
    
YES
The translation misinterprets "address list" as "færslugildalistann" ("transaction amount list"), which is incorrect. It should be "vistfangalista" or "addressulistann" to refer to the list of addresses.

Correct translation:
Ekki tókst að vista vistfangalistann á %1. Reyndu aftur.
```

```
        <source>Sending addresses - %1</source>
        <translation>heimilisföng - %1 </translation>
    
YES
The translation "heimilisföng" means "addresses" (plural), but it does not capture the meaning of "Sending addresses". A more accurate Icelandic translation would specify that these are addresses used for sending, e.g., "Sendingarheimilisföng", "Sendingarföng", or "Heimilisföng til að senda frá".

Correct translation:
Sendingarheimilisföng - %1

Additionally, remove the stray space at the end.

Final correct translation:
Sendingarheimilisföng - %1
```

```
        <source>Address</source>
        <translation>Færslugildi</translation>
    
YES
The translation is inaccurate. "Færslugildi" means "transaction value" or "transaction amount", not "address". The correct Icelandic translation for "Address" in the context of Bitcoin is "Vistfang".

Correct translation:
Vistfang
```

```
        <source>Show passphrase</source>
        <translation>lykilorð</translation>
    
YES
The translation is incorrect. The source phrase "Show passphrase" is an imperative instruction to display (show) the passphrase, but the Icelandic translation "lykilorð" simply means "password" or "passphrase" and does not convey the action "Show".

Correct translation:
Sýna lykilorð
```

```
        <source>Your wallet is now encrypted. </source>
        <translation>Veskið þitt er um það bil að vera dulkóðað.</translation>
    
YES
The translation is inaccurate. The English source states that the wallet is *now* encrypted (completed action), while the Icelandic translation says it is *about to be* encrypted (future/intention). This changes the meaning.

Correct translation:
Veskið þitt er nú dulkóðað.
```

```
        <source>Send coins to a Bitcoin address</source>
        <translation>Senda mynt í Bitcoin færslugildi</translation>
    
YES
The translation is problematic. The phrase "færslugildi" means "transaction value" or "transaction amount", which is incorrect for "Bitcoin address". The correct Icelandic term for "address" in this context is "Bitcoin vistfang".

Correct translation:
Senda mynt á Bitcoin vistfang
```

```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>Sýna færslugildi sem notuð hafa verið til að taka við mynt og merkingar þeirra</translation>
    
YES
The translation is not accurate. "Sýna færslugildi sem notuð hafa verið til að taka við mynt og merkingar þeirra" translates more like "Show the transaction values that have been used to receive coins and their labels," which changes the meaning and introduces "færslugildi" (transaction values) and "mynt" (coins), neither of which are mentioned in the original sentence.

Correct translation:
Sýna lista yfir notuð móttökuföng og merkingar þeirra
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Sýna %1 hjálparskilaboðin til að fá lista yfir valkosti Bitcoin aðgerðir í skipanalínu</translation>
    
YES
The Icelandic translation is awkward and slightly incorrect. The phrase "valkosti Bitcoin aðgerðir í skipanalínu" is ungrammatical and unclear. A better translation would be:

Sýna %1 hjálparskilaboðin til að fá lista yfir mögulega Bitcoin skipanalínuflokka

Or more literally:

Sýna %1 hjálparskilaboðin til að fá lista yfir mögulega skipanalínuvalkosti fyrir Bitcoin
```

```
        <source>%1 client</source>
        <translation>%1 biðlarar</translation>
    
YES
The translation uses the plural "biðlarar" (clients), while the English source "%1 client" is singular. The correct Icelandic singular form should be "biðlari".

Correct translation:
%1 biðlari
```

```
        <source>Address: %1
</source>
        <translation>Færslugildi: %1
</translation>
    
YES
The translation is inaccurate. "Address" should be translated as "Vistfang" or "Heimilisfang" (if contextually a Bitcoin address, "Vistfang" is usually used), but the translation uses "Færslugildi" which means "transaction value". This is a significant error in context.

Correct translation:
Vistfang: %1
```

```
        <source>Sent transaction</source>
        <translation>Send færsla</translation>
    
YES
The translation is problematic. "Send færsla" is a mix of English ("Send") and Icelandic ("færsla"). The correct Icelandic translation for "Sent transaction" is "Send færsla" incorrectly uses the imperative form of "send" in English.

Correct translation:
Send færslan
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Veskið er &lt;b&gt;dulkóðað&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</translation>
    
YES
The translation is partially untranslated: "and currently <b>locked</b>" remains in English. The proper Icelandic translation for "locked" in this context is "læst" and "and currently" is "og núna" or "og er núna".

Correct translation:
Veskið er <b>dulkóðað</b> og er núna <b>læst</b>
```

```
        <source>Quantity:</source>
        <translation>Magn:</translation>
    
YES
The translation "Magn:" is incorrect in Icelandic. The correct word for "Quantity" is "Magn" without the colon at the end of the word and with correct Icelandic spelling. However, adding a colon after the label is stylistically acceptable.

Correct translation:
Magn:
```

```
        <source>List mode</source>
        <translation>Listahamur</translation>
    
YES
The translation "Listahamur" is incorrect. In Icelandic, the correct translation for "List mode" would be "Listahamur" (if referring to "list" as in a "list of items"), but "Listahamur" is already used. However, "Listahamur" means "list mode" as intended. But "Listahamur" is more like "list display" or "list appearance", not literally "mode". Another, possibly more idiomatic translation is "Listayfirlit" ("list overview") or "Listahamur" is acceptable in UI context.

However, the translation is not problematic in format or content, so it could be accepted. To comply with your rules on giving the best translation:

Correct translation (polished for Icelandic UI context):
Listahamur

NO
```

```
        <source>Received with address</source>
        <translation>Móttekið með færslugildi</translation>
    
YES
The translation is inaccurate. "Móttekið með færslugildi" means "Received with transaction value", whereas the English phrase is "Received with address". The correct translation should refer to an address, not transaction value.

Correct translation:
Móttekið með vistfangi
```

```
        <source>Copy transaction ID and output index</source>
        <translation>Afritaðu færslu  auðkenni og úttaksvísitölu</translation>
    
YES
There is a formatting error: there is an unnecessary space between "færslu" and "auðkenni". The phrase should be "færsluauðkenni" (transaction ID), not split into two words.

Correct translation:
Afritaðu færsluauðkenni og úttaksvísitölu
```

```
        <source>Edit Address</source>
        <translation>Breyta færslugildi</translation>
    
YES
The translation "Breyta færslugildi" means "Edit transaction value," which is incorrect for "Edit Address." The correct Icelandic translation should be "Breyta vistfangi".

Correct translation:
Breyta vistfangi
```

```
        <source>The label associated with this address list entry</source>
        <translation>Merking tengd þessu færslugildi</translation>
    
YES
The translation "Merking tengd þessu færslugildi" is problematic. The English source refers to "address list entry" (i.e., an entry in the address list), while "færslugildi" translates closer to "transaction value" or "transaction amount," which does not match the intended meaning. 

Correct translation:
Merkimiði sem tengist þessari færslu á listanum

Or more simply:
Merking sem tengist þessari færslu á listanum
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>Færslugildið sem tengt er þessari færslu. Þessu má einungis breyta þegar sent er.</translation>
    
YES
The translation is inaccurate. "Færslugildið" means "the transaction value", which does not correspond to "the address" as in the source. The original refers specifically to the address associated with an entry, not a value. Also, "Þessu má einungis breyta þegar sent er" translates more closely to "This can only be changed when sending," which is less specific than the original.

Correct translation:
Heimilisfangið sem tengist þessari færslu í listanum. Þessu má aðeins breyta fyrir sendiheimilföng.
```

```
        <source>Address</source>
        <translation>Nýtt móttökufærslugildi</translation>
    
YES
The translation "Nýtt móttökufærslugildi" means "New receiving transaction value", which is incorrect for the simple word "Address". The translation should simply be "Heimilisfang" or, in the context of Bitcoin, "Vistfang".

Correct translation:
Vistfang
```

```
        <source>New sending address</source>
        <translation>Nýtt sendingarfærslugildi</translation>
    
YES
The translation "Nýtt sendingarfærslugildi" is problematic. The word "sendingarfærslugildi" does not accurately convey "sending address". The correct term for "address" in the context of Bitcoin is "heimilisfang" or "vistfang". "Sending" refers to sending coins, so "sendingarheimilisfang" or "nýtt sendingarvistfang" is more appropriate.

Correct translation:
Nýtt sendingarheimilisfang
```

```
        <source>Edit sending address</source>
        <translation>Breyta sendingarfærslugildi</translation>
    
YES
The translation "Breyta sendingarfærslugildi" is incorrect. The term "sendingarfærslugildi" is not a natural or correct way to express "sending address" in Icelandic. The correct translation for "address" in this context is "heimilisfang" or more commonly for Bitcoin, "vistfang". The correct phrase should be "Breyta sendingarvistfangi" or "Breyta vistfangi sendanda", depending on exact UI context.

Correct translation:
Breyta sendingarvistfangi
```

```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Færslugildið sem slegið var inn "%1" er ekki leyfilegt Bitcoin færslugildi.</translation>
    
YES
The Icelandic translation uses "færslugildið" ("the transaction value/identifier") instead of "address" ("vistfang", "reikningsnúmer", or simply "addressa" in context). This changes the meaning from "address" to "transaction value," which is incorrect in the context of Bitcoin.

Correct translation:
Heimilisfangið "%1" sem þú slóst inn er ekki gilt Bitcoin heimilisfang.
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>Innistæða færslugilda sem eru einungis til skoðunar</translation>
    
YES
The translation is inaccurate. "Innistæða færslugilda sem eru einungis til skoðunar" translates more like "Balance of transaction values that are for viewing only," which is not a direct or clear translation of "Your current balance in watch-only addresses". The possessive ("your") and the reference to "addresses" are missing.

Correct translation:
Núverandi innistæða þín í aðeins lesanlegum vistföngum
```

```
        <source>Sign Tx</source>
        <translation>Skilti Tx</translation>
    
YES
The Icelandic word "Skilti" means "sign" as in a physical sign or placard, not the verb "to sign (a transaction)". The correct verb is "Undirrita", which means "to sign" in the sense of authorizing a transaction.

Correct translation:
Undirrita Tx
```

```
        <source>Address</source>
        <extracomment>Title of Peers Table column which contains the IP/Onion/I2P address of the connected peer.</extracomment>
        <translation>Færslugildi</translation>
    
YES
The Icelandic translation "Færslugildi" does not correctly translate "Address." "Færslugildi" more closely means "transaction value" and is not appropriate in this context, where "Address" refers to an IP/Onion/I2P address. The correct Icelandic translation for "Address" in this context is "Tala" or more specifically, "Netfang" if it's an email, but for a network address, "Slóð" or "Tengi" could also be considered, but the usual term is "Vistfang".

Correct translation:
Vistfang
```

```
        <source>Quantity:</source>
        <translation>Magn:</translation>
    
YES
The translation "Magn:" is incorrect in Icelandic. The correct word for "Quantity" is "Magn" without the colon at the end of the word and with correct Icelandic spelling. However, adding a colon after the label is stylistically acceptable.

Correct translation:
Magn:
```

```
        <source>External signer failure</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Bilun í ytri undirritara</translation>
    
YES
The translation is somewhat problematic. "Bilun í ytri undirritara" uses "í", which is uncommon in this context in Icelandic. A better translation would be "Villa í ytri undirritara" or "Bilun í ytri undirritaraferli". The word "bilun" is possible, but "villa" ("error") is more conventional in UI error messages.

Correct translation:
Villa í ytri undirritara
```

```
        <source>Address</source>
        <translation>Færslugildi</translation>
    
YES
The translation is inaccurate. "Færslugildi" means "transaction value" or "transaction amount", not "address". The correct Icelandic translation for "Address" in the context of Bitcoin is "Vistfang".

Correct translation:
Vistfang
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>Flyttu gögnin í núverandi flipa út í skrá                                                                    </translation>
    
YES
There is unnecessary trailing whitespace at the end of the translation.

Correct translation:
Flyttu gögnin í núverandi flipa út í skrá
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Óstudd flokkasértæk skráningarstig %1$s=%2$s. Búist var við %1$s=:. Gildir flokkar: %3$s. Gild logstig: %4$s.</translation>
    
YES
The translation omits critical information from the source sentence, specifically the placeholders "<category>:<loglevel>" in the expected format. The translated sentence, "Búist var við %1$s=:", loses the explanation that the expected value is "%1$s=<category>:<loglevel>". This may be confusing for the user.

Correct translation:
Óstudd flokkasértæk skráningarstig %1$s=%2$s. Búist var við %1$s=&lt;flokkur&gt;:&lt;skráningarstig&gt;. Gildir flokkar: %3$s. Gild skráningarstig: %4$s.
```
</details>

Number of issues: 39.
