# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>is</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bis%5D%20request)


<!-- cache_translation_check_is_448c30508376fb8b97ae9671c6bc397757f02abe5027b852f988b521fc8f7c80 -->
```
        <source>Create a new address</source>
        <translation>Búa til nýtt veski</translation>
    
ERR
The translation inaccurately translates "address" as "veski" (wallet). The correct Icelandic word for "address" in the context of Bitcoin would be "fang" or "lykilorð", but "fang" is standard for "address".

Correct translation:
Búa til nýtt fang
```

<!-- cache_translation_check_is_d08c58e2b154590edb3a26dd32f063af32978eec7fe53a2a4a51d438a4e57d4f -->
```
        <source>Enter address or label to search</source>
        <translation>Veldu veski eða merkingu fyrir leit</translation>
    
ERR
The Icelandic translation is inaccurate. "Veldu veski eða merkingu fyrir leit" translates as "Select wallet or label for search," which does not convey "Enter address or label to search." The verb "enter" should be translated as "Sláðu inn" or "Settu inn" in Icelandic, and "address" as "fang" or, in the Bitcoin context, "wallet address". Furthermore, "veski" means "wallet" rather than "address".

Correct translation:
Sláðu inn vistfang eða merkingu til að leita
```

<!-- cache_translation_check_is_de9141ff17ca281ebb8265e944ffecbe019e58d60e24ec7aabffd41dccb36e2c -->
```
        <source>Export the data in the current tab to a file</source>
        <translation>Flyttu gögnin í núverandi flipa út í skrá                                                                    </translation>
    
ERR
There is unnecessary trailing whitespace at the end of the translation.

Correct translation:
Flyttu gögnin í núverandi flipa út í skrá
```

<!-- cache_translation_check_is_5e1845c5adc89d8266cdf4a35c9c2591123632db0ace0edfc62f4e785fb371cd -->
```
        <source>Choose the address to send coins to</source>
        <translation>Veldu veski sem greiða skal til</translation>
    
ERR
The translation is inaccurate. "Veldu veski sem greiða skal til" translates as "Choose the wallet to pay to," but the source refers specifically to "address" (which can mean a Bitcoin address, not a wallet). The Icelandic word for "address" in the Bitcoin context is "aðili" or more commonly "færslureikningur", but usually "heimilisfang" or simply "addressa" (loan word) is used among Icelandic crypto users.

Correct translation:
Veldu addressu sem þú vilt senda myntunum til
```

<!-- cache_translation_check_is_b25d5081d2b66ae2e3aa4de1a7e8b4954056251049c70be38fcdeb3cee524acb -->
```
        <source>Choose the address to receive coins with</source>
        <translation>Veldu veski til að taka við rafmynt</translation>
    
ERR
The translation changes the meaning: "Veldu veski til að taka við rafmynt" translates to "Choose wallet to receive cryptocurrency," instead of "Choose the address to receive coins with." The original specifies "address," not "wallet," and "coins," not the generic "cryptocurrency."

Correct translation:
Veldu vistfangið til að taka við myntum
```

<!-- cache_translation_check_is_9aaf8ebe7733fa281f27190f6eaf34c431acb200e225d91c36e44eb2ac4fa5ad -->
```
        <source>&amp;Copy Address</source>
        <translation>&amp;Afrita færslugildi</translation>
    
ERR
The translation of "&amp;Copy Address" as "&amp;Afrita færslugildi" is problematic. "Færslugildi" means "transaction value" in Icelandic, which is not equivalent to "address". The correct translation of "address" (in the context of Bitcoin, usually meaning a receiving address or wallet address) is "vistfang" or "heimilisfang" (though "vistfang" is usual in the software sense). The shortcut ampersand is correctly placed.

Correct translation:
&Afrita vistfang
```

<!-- cache_translation_check_is_6204bd04f0786d7d9c1284adbba627e296fe68f294c67d7952851ce71cd5765a -->
```
        <source>Copy &amp;Label</source>
        <translation>Afrita og &amp;Merkja</translation>
    
ERR
The translation rearranges the meaning. "Afrita og &Merkja" means "Copy and label", which is not the same as "Copy Label". The correct Icelandic translation would be "Afrita &Merkimiða" or simply "Afrita &Merk".

Correct translation:
Afrita &Merkimiða
or
Afrita &Merk
```

<!-- cache_translation_check_is_e07ce852e6bec92fc7c5248ee9e4fdee872e062c949ab9b883680657b22a8343 -->
```
        <source>Export Address List</source>
        <translation>Flytja út færslulista</translation>
    
ERR
The translation "Flytja út færslulista" means "Export entry list" or "export transaction list" rather than "Export Address List." The word "address" should be translated as "vistfang" (for general use), or "heimilisfang" (for physical addresses), but in the Bitcoin context, "address" is usually translated as "vistfang". "Færslulisti" refers to transactions/entries.

Correct translation:
Flytja út vistfangalista
```

<!-- cache_translation_check_is_f9a9077e901288bcd96aa3ad1adda9a15b9b78867e6818da4d5a8a0dddd52d4e -->
```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Ekki tókst að vista færslugildalistann á %1. Reyndu aftur.</translation>
    
ERR
The translation misinterprets "address list" as "færslugildalistann" ("transaction amount list"), which is incorrect. It should be "vistfangalista" or "addressulistann" to refer to the list of addresses.

Correct translation:
Ekki tókst að vista vistfangalistann á %1. Reyndu aftur.
```

<!-- cache_translation_check_is_049b8fd936747b9be857d82a012a36239f6e0b14c16bec8363e4b4e7295a2f92 -->
```
        <source>Sending addresses - %1</source>
        <translation>heimilisföng - %1 </translation>
    
ERR
The translation "heimilisföng" means "addresses" (plural), but it does not capture the meaning of "Sending addresses". A more accurate Icelandic translation would specify that these are addresses used for sending, e.g., "Sendingarheimilisföng", "Sendingarföng", or "Heimilisföng til að senda frá".

Correct translation:
Sendingarheimilisföng - %1

Additionally, remove the stray space at the end.

Final correct translation:
Sendingarheimilisföng - %1
```

<!-- cache_translation_check_is_5224b5c20f1956a0eaf89cc802ecf1aa558e9435b56343758da601de80df59a0 -->
```
        <source>Receiving addresses - %1</source>
        <translation>heimilisföng - %1</translation>
    
ERR
The Icelandic translation only says "heimilisföng - %1" ("addresses - %1") and omits the "Receiving" meaning. The format specifier %1 is preserved correctly and there are no whitespace issues, but the translation is incomplete/less specific.

Suggested correct translation:
Móttökuheimilisföng - %1
```

<!-- cache_translation_check_is_5b39350b4fc9ab7819b66712032c85c27ebd658998324fbc84377a559c24ea57 -->
```
        <source>Address</source>
        <translation>Færslugildi</translation>
    
ERR
The translation is inaccurate. "Færslugildi" means "transaction value" or "transaction amount", not "address". The correct Icelandic translation for "Address" in the context of Bitcoin is "Vistfang".

Correct translation:
Vistfang
```

<!-- cache_translation_check_is_769326bccaff16592d12cb69b2d185773d32ac98ec24302a68af8469d72d405c -->
```
        <source>Show passphrase</source>
        <translation>lykilorð</translation>
    
ERR
The translation is incorrect. The source phrase "Show passphrase" is an imperative instruction to display (show) the passphrase, but the Icelandic translation "lykilorð" simply means "password" or "passphrase" and does not convey the action "Show".

Correct translation:
Sýna lykilorð
```

<!-- cache_translation_check_is_8f70cdfef2a677cda40064d70f2e0d1d822447ddc394abeaf3d46fab1a79b330 -->
```
        <source>Your wallet is now encrypted. </source>
        <translation>Veskið þitt er um það bil að vera dulkóðað.</translation>
    
ERR
The translation is inaccurate. The English source states that the wallet is *now* encrypted (completed action), while the Icelandic translation says it is *about to be* encrypted (future/intention). This changes the meaning.

Correct translation:
Veskið þitt er nú dulkóðað.
```

<!-- cache_translation_check_is_96e203c27eeb6f51d26e43f2537ea13a068a573a1ad7c24c5e52e42c31c7e8c1 -->
```
        <source>%1 didn't yet exit safely…</source>
        <translation>%1 fór ekki enn á öruggan hátt…</translation>
    
ERR
The Icelandic phrasing is awkward and unidiomatic. "fór ekki enn á öruggan hátt…" literally reads "went not yet in a safe way" and doesn't convey "didn't yet exit safely" for a program/process. The format specifier %1 and the ellipsis are preserved correctly.

Suggested correction:
%1 hefur ekki ennþá hætt örugglega.
```

<!-- cache_translation_check_is_580d53aa8862a3a285305009b2842a47f2465b935d6020f352da91d2c41afb53 -->
```
        <source>Send coins to a Bitcoin address</source>
        <translation>Senda mynt í Bitcoin færslugildi</translation>
    
ERR
The translation is problematic. The phrase "færslugildi" means "transaction value" or "transaction amount", which is incorrect for "Bitcoin address". The correct Icelandic term for "address" in this context is "Bitcoin vistfang".

Correct translation:
Senda mynt á Bitcoin vistfang
```

<!-- cache_translation_check_is_072e720a5d612c8f1b8ba05806d8f6d2b6dbf67cc8cc09fe339440d73b9d066f -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>&amp;Öryggisveski...</translation>
    
ERR
The translation misinterprets "Backup Wallet" as "Öryggisveski", which means "safety wallet" or "secure wallet" in Icelandic, rather than the verb "Back up". The correct translation should communicate the action to back up the wallet.

Correct translation:
&Afrita veski...
```

<!-- cache_translation_check_is_baae1fdb51c905c8d7139162c17fb9d83eb893d6e53381463b9c966a06e7a5c5 -->
```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>Sýna færslugildi sem notuð hafa verið til að taka við mynt og merkingar þeirra</translation>
    
ERR
The translation is not accurate. "Sýna færslugildi sem notuð hafa verið til að taka við mynt og merkingar þeirra" translates more like "Show the transaction values that have been used to receive coins and their labels," which changes the meaning and introduces "færslugildi" (transaction values) and "mynt" (coins), neither of which are mentioned in the original sentence.

Correct translation:
Sýna lista yfir notuð móttökuföng og merkingar þeirra
```

<!-- cache_translation_check_is_1f4287e1f88b6aacc41af9898af1c3924e079a006266ddf573bf83f39b1a8223 -->
```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Sýna %1 hjálparskilaboðin til að fá lista yfir valkosti Bitcoin aðgerðir í skipanalínu</translation>
    
ERR
The Icelandic translation is awkward and slightly incorrect. The phrase "valkosti Bitcoin aðgerðir í skipanalínu" is ungrammatical and unclear. A better translation would be:

Sýna %1 hjálparskilaboðin til að fá lista yfir mögulega Bitcoin skipanalínuflokka

Or more literally:

Sýna %1 hjálparskilaboðin til að fá lista yfir mögulega skipanalínuvalkosti fyrir Bitcoin
```

<!-- cache_translation_check_is_09bcfc715e55b0237dde7df3439e020035d65b337b95193837f9dd80be5d60a3 -->
```
        <source>%1 client</source>
        <translation>%1 biðlarar</translation>
    
ERR
The translation uses the plural "biðlarar" (clients), while the English source "%1 client" is singular. The correct Icelandic singular form should be "biðlari".

Correct translation:
%1 biðlari
```

<!-- cache_translation_check_is_4f828d89eb2d0069049b20f899fd305856031722a6f55fb2b4d2dcc6ad69f75c -->
```
        <source>Address: %1
</source>
        <translation>Færslugildi: %1
</translation>
    
ERR
The translation is inaccurate. "Address" should be translated as "Vistfang" or "Heimilisfang" (if contextually a Bitcoin address, "Vistfang" is usually used), but the translation uses "Færslugildi" which means "transaction value". This is a significant error in context.

Correct translation:
Vistfang: %1
```

<!-- cache_translation_check_is_674ce1f3a01fa98359d996eb0cae2d99bf24e6b576b9e298273c01cf80eeba86 -->
```
        <source>Sent transaction</source>
        <translation>Send færsla</translation>
    
ERR
The translation is problematic. "Send færsla" is a mix of English ("Send") and Icelandic ("færsla"). The correct Icelandic translation for "Sent transaction" is "Send færsla" incorrectly uses the imperative form of "send" in English.

Correct translation:
Send færslan
```

<!-- cache_translation_check_is_e238b07a12398ab5cf9eb129f50aa31247cb55f1a0265ced7cc512145deadc00 -->
```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Veskið er &lt;b&gt;dulkóðað&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</translation>
    
ERR
The translation is partially untranslated: "and currently <b>locked</b>" remains in English. The proper Icelandic translation for "locked" in this context is "læst" and "and currently" is "og núna" or "og er núna".

Correct translation:
Veskið er <b>dulkóðað</b> og er núna <b>læst</b>
```

<!-- cache_translation_check_is_a5feb2a4b2c0f04f3bdf7c2e95e45aa0e993f67e603c4f77ffae382d0eb01933 -->
```
        <source>Quantity:</source>
        <translation>Magn:</translation>
    
ERR
The translation "Magn:" is incorrect in Icelandic. The correct word for "Quantity" is "Magn" without the colon at the end of the word and with correct Icelandic spelling. However, adding a colon after the label is stylistically acceptable.

Correct translation:
Magn:
```

<!-- cache_translation_check_is_d7e0634749a3a5a14901ab88cba95d6b14d551bb777e2f8920c244849d84006b -->
```
        <source>List mode</source>
        <translation>Listahamur</translation>
    
ERR
The translation "Listahamur" is incorrect. In Icelandic, the correct translation for "List mode" would be "Listahamur" (if referring to "list" as in a "list of items"), but "Listahamur" is already used. However, "Listahamur" means "list mode" as intended. But "Listahamur" is more like "list display" or "list appearance", not literally "mode". Another, possibly more idiomatic translation is "Listayfirlit" ("list overview") or "Listahamur" is acceptable in UI context.

However, the translation is not problematic in format or content, so it could be accepted. To comply with your rules on giving the best translation:

Correct translation (polished for Icelandic UI context):
Listahamur

NO
```

<!-- cache_translation_check_is_d1f75930a791911f20586c5f539f88af9965a38c5e8871a32443040e717ae6b9 -->
```
        <source>Received with address</source>
        <translation>Móttekið með færslugildi</translation>
    
ERR
The translation is inaccurate. "Móttekið með færslugildi" means "Received with transaction value", whereas the English phrase is "Received with address". The correct translation should refer to an address, not transaction value.

Correct translation:
Móttekið með vistfangi
```

<!-- cache_translation_check_is_f657074daa2f561f4a6864946bf9d4740bf0be166a815ff6ad276b55abf9bfc9 -->
```
        <source>Edit Address</source>
        <translation>Breyta færslugildi</translation>
    
ERR
The translation "Breyta færslugildi" means "Edit transaction value," which is incorrect for "Edit Address." The correct Icelandic translation should be "Breyta vistfangi".

Correct translation:
Breyta vistfangi
```

<!-- cache_translation_check_is_29fa17515dc3ad34499fa9994760f711990de95720d250f14c424f7cd46de259 -->
```
        <source>The label associated with this address list entry</source>
        <translation>Merking tengd þessu færslugildi</translation>
    
ERR
The translation "Merking tengd þessu færslugildi" is problematic. The English source refers to "address list entry" (i.e., an entry in the address list), while "færslugildi" translates closer to "transaction value" or "transaction amount," which does not match the intended meaning. 

Correct translation:
Merkimiði sem tengist þessari færslu á listanum

Or more simply:
Merking sem tengist þessari færslu á listanum
```

<!-- cache_translation_check_is_2f1a3a6a1b258f741a64cec0396017171550f50761fdbda239dc18d664d1f303 -->
```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>Færslugildið sem tengt er þessari færslu. Þessu má einungis breyta þegar sent er.</translation>
    
ERR
The translation is inaccurate. "Færslugildið" means "the transaction value", which does not correspond to "the address" as in the source. The original refers specifically to the address associated with an entry, not a value. Also, "Þessu má einungis breyta þegar sent er" translates more closely to "This can only be changed when sending," which is less specific than the original.

Correct translation:
Heimilisfangið sem tengist þessari færslu í listanum. Þessu má aðeins breyta fyrir sendiheimilföng.
```

<!-- cache_translation_check_is_6f8f32a799f988af66f78d23b7993f723948b2bde404f656e4fed161f8115402 -->
```
        <source>&amp;Address</source>
        <translation>Nýtt móttökufærslugildi</translation>
    
ERR
The translation "Nýtt móttökufærslugildi" does not accurately convey the meaning of "Address". The English "&Address" is meant as a menu or button title with an accelerator key, and should be translated concisely as "Address" into Icelandic. Also, the ampersand (&) for the shortcut key is missing.

Correct translation:
&Heimilisfang
```

<!-- cache_translation_check_is_906d6220f0cde5c0d48d5cbe59aae055c72298cd0abba6557b16f0edd1957e63 -->
```
        <source>New sending address</source>
        <translation>Nýtt sendingarfærslugildi</translation>
    
ERR
The translation "Nýtt sendingarfærslugildi" is problematic. The word "sendingarfærslugildi" does not accurately convey "sending address". The correct term for "address" in the context of Bitcoin is "heimilisfang" or "vistfang". "Sending" refers to sending coins, so "sendingarheimilisfang" or "nýtt sendingarvistfang" is more appropriate.

Correct translation:
Nýtt sendingarheimilisfang
```

<!-- cache_translation_check_is_585969050eecf1b114b8dd9684a2b4cb15274370e98b1f5d175ab5a4dc5f9d21 -->
```
        <source>Edit sending address</source>
        <translation>Breyta sendingarfærslugildi</translation>
    
ERR
The translation "Breyta sendingarfærslugildi" is incorrect. The term "sendingarfærslugildi" is not a natural or correct way to express "sending address" in Icelandic. The correct translation for "address" in this context is "heimilisfang" or more commonly for Bitcoin, "vistfang". The correct phrase should be "Breyta sendingarvistfangi" or "Breyta vistfangi sendanda", depending on exact UI context.

Correct translation:
Breyta sendingarvistfangi
```

<!-- cache_translation_check_is_8d944bf8ecf99d9c3570812e1654e63b894436e635b7799ea386a33fc481565b -->
```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Færslugildið sem slegið var inn "%1" er ekki leyfilegt Bitcoin færslugildi.</translation>
    
ERR
The Icelandic translation uses "færslugildið" ("the transaction value/identifier") instead of "address" ("vistfang", "reikningsnúmer", or simply "addressa" in context). This changes the meaning from "address" to "transaction value," which is incorrect in the context of Bitcoin.

Correct translation:
Heimilisfangið "%1" sem þú slóst inn er ekki gilt Bitcoin heimilisfang.
```

<!-- cache_translation_check_is_43bf74927e5eaca6185126a08bb887d396d7f5fb8f8beb0665cef2d607255de4 -->
```
        <source>Directory already exists. Add %1 if you intend to create a new directory here.</source>
        <translation>Skráin er þegar til. Bættu við %1 ef þú ætlar að búa til nýja möppu hér.</translation>
    
ERR
The Icelandic uses "Skráin" (the file) but the source refers to a directory. Use the Icelandic word for directory ("mappa") or "möppan".

Correct translation:
Möppan er þegar til. Bættu við %1 ef þú ætlar að búa til nýja möppu hér.
```

<!-- cache_translation_check_is_7c53057216fc5df48e7b76394a2ca67640b20d56930db142be879eeeaa2b2d71 -->
```
        <source>This initial synchronisation is very demanding, and may expose hardware problems with your computer that had previously gone unnoticed. Each time you run %1, it will continue downloading where it left off.</source>
        <translation>Þessi fyrstu samstilling er mjög krefjandi og getur leitt til vélbúnaðarvandamála með tölvunni þinni sem áður hafði farið framhjá. Í hvert skipti sem þú keyrir %1 mun það halda áfram að hlaða niður þar sem frá var horfið.</translation>
    
ERR
The Icelandic is understandable but has awkward phrasing and some grammatical issues (word choice and tense/agreement). Provide a clearer, more natural translation preserving %1:

Correct translation:
Þessi upphaflega samstilling er mjög krefjandi og gæti afhjúpað vélbúnaðarvandamál í tölvunni þinni sem áður höfðu farið fram hjá þér. Í hvert sinn sem þú keyrir %1 heldur hún áfram að hlaða niður þaðan sem hún hætti.
```

<!-- cache_translation_check_is_b13056a58fa13dad215f8125e8610ee86ba86f4e9c2e4af84686205dd6529e9c -->
```
        <source>Sign Tx</source>
        <translation>Skilti Tx</translation>
    
ERR
The Icelandic word "Skilti" means "sign" as in a physical sign or placard, not the verb "to sign (a transaction)". The correct verb is "Undirrita", which means "to sign" in the sense of authorizing a transaction.

Correct translation:
Undirrita Tx
```

<!-- cache_translation_check_is_f711fcf09d68b8a47f5a2ae0c983860e3c1404576d7a426d8e98ed0d4ded031c -->
```
        <source>Address</source>
        <extracomment>Title of Peers Table column which contains the IP/Onion/I2P address of the connected peer.</extracomment>
        <translation>Færslugildi</translation>
    
ERR
The Icelandic translation "Færslugildi" does not correctly translate "Address." "Færslugildi" more closely means "transaction value" and is not appropriate in this context, where "Address" refers to an IP/Onion/I2P address. The correct Icelandic translation for "Address" in this context is "Tala" or more specifically, "Netfang" if it's an email, but for a network address, "Slóð" or "Tengi" could also be considered, but the usual term is "Vistfang".

Correct translation:
Vistfang
```

<!-- cache_translation_check_is_ab5d211d2a1250e55b94230fd9577240cd41d816125eabde3d4efad7ecebb4bc -->
```
        <source>Executing command using "%1" wallet</source>
        <translation>Framkvæmir skipun með "%1" veski</translation>
    
ERR
The Icelandic is awkward/ungrammatical. "Framkvæmir skipun með "%1" veski" uses the wrong verb form and noun case. Also "veski" should be in the definite/appropriate form ("veskinu") and the phrasing should indicate an ongoing action.

Correct translation:
Er að framkvæma skipun með veskinu „%1“
```

<!-- cache_translation_check_is_a5feb2a4b2c0f04f3bdf7c2e95e45aa0e993f67e603c4f77ffae382d0eb01933 -->
```
        <source>Quantity:</source>
        <translation>Magn:</translation>
    
ERR
The translation "Magn:" is incorrect in Icelandic. The correct word for "Quantity" is "Magn" without the colon at the end of the word and with correct Icelandic spelling. However, adding a colon after the label is stylistically acceptable.

Correct translation:
Magn:
```

<!-- cache_translation_check_is_639042fbf25dfea2aa18ac972ab21a29ec297a94f9f007e324ae150255dc188f -->
```
        <source>External signer failure</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Bilun í ytri undirritara</translation>
    
ERR
The translation is somewhat problematic. "Bilun í ytri undirritara" uses "í", which is uncommon in this context in Icelandic. A better translation would be "Villa í ytri undirritara" or "Bilun í ytri undirritaraferli". The word "bilun" is possible, but "villa" ("error") is more conventional in UI error messages.

Correct translation:
Villa í ytri undirritara
```

<!-- cache_translation_check_is_5b39350b4fc9ab7819b66712032c85c27ebd658998324fbc84377a559c24ea57 -->
```
        <source>Address</source>
        <translation>Færslugildi</translation>
    
ERR
The translation is inaccurate. "Færslugildi" means "transaction value" or "transaction amount", not "address". The correct Icelandic translation for "Address" in the context of Bitcoin is "Vistfang".

Correct translation:
Vistfang
```

<!-- cache_translation_check_is_de9141ff17ca281ebb8265e944ffecbe019e58d60e24ec7aabffd41dccb36e2c -->
```
        <source>Export the data in the current tab to a file</source>
        <translation>Flyttu gögnin í núverandi flipa út í skrá                                                                    </translation>
    
ERR
There is unnecessary trailing whitespace at the end of the translation.

Correct translation:
Flyttu gögnin í núverandi flipa út í skrá
```

<!-- cache_translation_check_is_133c830628d6a651778fc8ff76c85c59c2397d1beeb57ef9f1999411d8ba13d9 -->
```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Óstudd flokkasértæk skráningarstig %1$s=%2$s. Búist var við %1$s=:. Gildir flokkar: %3$s. Gild logstig: %4$s.</translation>
    
ERR
The translation omits critical information from the source sentence, specifically the placeholders "<category>:<loglevel>" in the expected format. The translated sentence, "Búist var við %1$s=:", loses the explanation that the expected value is "%1$s=<category>:<loglevel>". This may be confusing for the user.

Correct translation:
Óstudd flokkasértæk skráningarstig %1$s=%2$s. Búist var við %1$s=&lt;flokkur&gt;:&lt;skráningarstig&gt;. Gildir flokkar: %3$s. Gild skráningarstig: %4$s.
```
</details>

Number of issues: 43.
