# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>fo</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bfo%5D%20request)


<!-- cache_translation_check_fo_ba9d1bcd19d525af595a1ce6c5c5391dcdb346f33c24ed8544ba9bb9d1c4f69b -->
```
        <source>Create a new address</source>
        <translation>Innlegg nýggja útgjaldsadressu</translation>
    
ERR
The translation "Innlegg" is a noun meaning "input", "contribution", or "post" (like on a forum). It is not the verb "Create". Also, "útgjaldsadressu" specifically means "payout address" or "spending address", which is more specific than the source text "address". A more natural translation for "Create a new address" would use a verb like "Stovna".

Correct translation:
Stovna nýggja adressu
```

<!-- cache_translation_check_fo_ea8c7490415e4d6780a2c266eb0e70a21100c1f2fe3eea8189f76a34d4d7470a -->
```
        <source>Confirm wallet encryption</source>
        <translation>Váttað mappu bronglan</translation>
    
ERR
The translation contains grammatical errors. "Váttað" is the past participle (confirmed), but here the imperative or infinitive "Vátta" (Confirm) is needed. Also, "mappu bronglan" (wallet encryption) is translated as two separate nouns without proper connection or compound structure. In Faroese, compound nouns are written together, or a genitive structure is used. "Mappa" often means folder, but is used for wallet in some contexts (though "lumma" is pocket/wallet, "mappa" is commonly used in software contexts for wallet/portfolio). "Bronglan" is a somewhat obscure word for encryption (often "kryptering" is used, or "dulnevning"). However, assuming "mappa" and "bronglan" are the chosen terminology, they should be combined or grammatically linked.

A better, more standard translation would be "Vátta bronglan av lumma" or "Vátta mappukryptering". Given the existing words:

Correct translation:
Vátta mappubronglan
```

<!-- cache_translation_check_fo_ce8d9c572849fa271822ea7a0c30eee94659f3e74f77bbfaddca5e290a84265a -->
```
        <source>Back</source>
        <translation>Ógilda</translation>
    
ERR
The translation "Ógilda" means "Invalidate" or "Cancel" (similar to 'Cancel' or 'Void'). While it might be used for an "Undo" or "Cancel" button, "Back" (navigation) is usually translated as "Aftur" or "Tilbake" (though Faroese uses *Aftur*). If the context is navigation (going back to the previous screen), "Ógilda" is incorrect. If the context were a browser history or wizard steps, "Aftur" is the standard term. Given the ambiguity but high likelihood of navigation in UI contexts, "Aftur" is safer and more accurate for "Back". "Ógilda" is definitely wrong for "Back"; it corresponds to "Cancel".

Correct translation:
Aftur
```

<!-- cache_translation_check_fo_208de8cbd79da0c34440e0c3c33dd1a2960d9f10c49c1bd5b763f780a22a953b -->
```
        <source>Wallet to be encrypted</source>
        <translation>Mappa ið verður brongla</translation>
    
ERR
The translation uses "Mappa" (Folder) for "Wallet", which might be acceptable in some contexts but usually "Pungur" is preferred for a Bitcoin wallet. More importantly, the grammar is incorrect. "Brongla" is a verb (to scramble/encrypt), but here it should be a past participle used as an adjective ("bronglað" or "bronglaður"). Also, the phrasing "Mappa ið verður brongla" translates literally to "Folder which becomes scramble". A better translation for "Wallet to be encrypted" would be "Pungur at brongla" or "Pungur sum skal bronglast".

Correct translation:
Pungur at brongla
```

<!-- cache_translation_check_fo_d1b0669a460533a748f2cfd94ac5ea6b5062758d0ed63b77e0447966c8bae7f6 -->
```
        <source>Your wallet is about to be encrypted. </source>
        <translation>Tín mappa verður brongla.</translation>
    
ERR
The translation is grammatically incorrect and uses a slightly odd word for "encrypted". "Brongla" is a verb meaning "to confuse" or "to tangle". The participle "bronglað" (confused/tangled/scrambled) is sometimes used for encryption, but "krypterað" is standard in technical contexts. Crucially, the sentence ends abruptly. The source says "is about to be encrypted". The translation "verður brongla" is ungrammatical (missing the past participle ending 'ð' and possibly a future marker like "farið at verða").

A better translation would be:
Tín lumma-mappa fer at verða krypterað.

Correct translation:
Tín lumma-mappa fer at verða krypterað.
```

<!-- cache_translation_check_fo_7024581e3221473d89bd75ac77039b7da259e2267108ce10401cba4c32155126 -->
```
        <source>Browse transaction history</source>
        <translation>Vís flytingaryvirlit, tilhoyrandi mappuna</translation>
    
ERR
The translation includes extra information not present in the source text. "Vís flytingaryvirlit" means "Show transaction history", which is close enough to "Browse...", but ", tilhoyrandi mappuna" means ", belonging to the folder" or ", the associated folder". This extra phrase changes the meaning and seems to have been copied from a different context or is a hallucination.

Correct translation:
Kaga ígjøgnum flytingarsøgu
```

<!-- cache_translation_check_fo_906ac37103d5b761ab3e492f8b300e161beeb13f6b7c92b69f788bbad6c6b64b -->
```
        <source>Create a new wallet</source>
        <translation>Ger nýggja mappu</translation>
    
ERR
In the context of Bitcoin software, "wallet" should typically be translated to a term referring to a digital wallet (like 'lummapungur' or 'seðlahefti'), not "mappu". "Mappu" means "folder" or "directory" in Faroese, which is confusing in this context.

Correct translation:
Stovna nýggjan lummapung
```

<!-- cache_translation_check_fo_0fe93e14ddceb8b0f0a351d223da51f57c3fc96a9ee4f940cff335869c18e24a -->
```
        <source>Wallet:</source>
        <translation>Mappa:</translation>
    
ERR
In the context of Bitcoin software, "Wallet" is almost universally translated as "Lummapungur" (literally "pocket purse") or sometimes just "Pungur" in Faroese to refer to the digital wallet holding funds. "Mappa" means "folder" or "portfolio" (in the sense of a briefcase), which is not the standard terminology for a crypto wallet.

Correct translation:
Lummapungur:
```

<!-- cache_translation_check_fo_9216749058908e9a28ee28458812bad6912cdcaad1c5b79c07d06877aecb0a9b -->
```
        <source>Open a wallet</source>
        <translation>Innles eina mappu</translation>
    
ERR
The translation "Innles eina mappu" more accurately translates to "Import a folder" or "Import a wallet" rather than "Open a wallet". In Faroese, "wallet" in the context of Bitcoin is often translated as "lummapungur" (pocket purse) or "pungur" (purse), but "mappa" (folder/file) is sometimes used in software contexts for "wallet" (as in a wallet file). However, "innles" (import/read in) is not the best verb for "Open". A better verb for "Open" is "Lat upp".

Correct translation:
Lat ein pung upp
```

<!-- cache_translation_check_fo_56897f47deca2157d03db69c9fd9f86759b51c170af09867f551f8947d50d542 -->
```
        <source>List mode</source>
        <translation>Óbólkaðar myntir</translation>
    
ERR
The translation provided ("Óbólkaðar myntir") actually means "Unconfirmed coins" or "Ungrouped coins" (specifically referencing coins/currency), which is completely different from the source text "List mode" (a UI view setting). It seems the translator might have pasted a translation for a different string (perhaps related to "unconfirmed" or "unspent" outputs) or misunderstood the context entirely.

Correct translation:
Listaháttur
```

<!-- cache_translation_check_fo_cc6b0b53c32d9a64ab4916baadc469f0ddc70d6fa097dc2b7fed7fcdf5bf453a -->
```
        <source>(%1 locked)</source>
        <translation>(%1 løst)</translation>
    
ERR
The translation means "loose" or "solved" (as in a problem), which is the opposite of "locked". The correct Faroese word for "locked" is "læst".

Correct translation:
(%1 læst)
```

<!-- cache_translation_check_fo_f57d3686962e876b03fa063d65ac4d730e0d797ab211a6cd119d3eb625364109 -->
```
        <source>Create wallet failed</source>
        <translation>Miseydnaðist at gera mappu</translation>
    
ERR
The translation uses the word "mappu" which means "folder" in Faroese. In the context of Bitcoin, "wallet" should be translated as "seðlahefti" (or sometimes "pungur", though seðlahefti is often used in software). "Mappa" refers to a file directory.

Correct translation:
Miseydnaðist at gera seðlahefti
```

<!-- cache_translation_check_fo_d6e876b33fae7c21989ae54e9cb1ba77bd59d3608f53bf6edb3bf446cb470f22 -->
```
        <source>Migrate wallet</source>
        <translation>Uppstiga mappusnið</translation>
    
ERR
The Faroese translation "Uppstiga mappusnið" (Upgrade folder/wallet format) captures the general idea of an upgrade, but "mappusnið" usually refers to a file format or layout, while "wallet" in the context of Bitcoin is typically translated as "lumma" (pocket/wallet) in Faroese software contexts. "Uppstiga" is also a bit unusual; "Flyt" (move/migrate) or "Dagfør" (update/upgrade) might be better depending on the exact technical process, but "Uppstiga" is acceptable for "upgrade". However, equating "wallet" to "mappusnið" (folder format) is technically imprecise and slightly confusing. A more direct translation of "Migrate wallet" would be better.

Correct translation:
Flyt lumma
```

<!-- cache_translation_check_fo_b9510fefa0983063057ec19c7bf29c9ee83f3344b0010894ddfe996a1bb12062 -->
```
        <source>Restore wallet message</source>
        <extracomment>Title of message box which is displayed when the wallet is successfully restored.</extracomment>
        <translation>Uppstigan av mappusniði væleydnað</translation>
    
ERR
The translation provided seems to mean "Upgrade of folder format successful" or "Upgrade of wallet format successful" (specifically using 'mappusniði' which relates to folder/wallet format, and 'uppstigan' which relates to upgrading/rising). This deviates significantly from the source text "Restore wallet message" which is a title for a message box about restoration, not an upgrade confirmation itself. The source is a title/header string.

The term "mappa" often means "folder" or "wallet" in computer contexts in Faroese/Icelandic (though "fíggjarmappa" or just "mappa" is used). However, "Uppstigan" (Upgrade) is definitely wrong for "Restore". "Endurstovna" is usually used for "Restore".

Correct translation:
Boð um endurstovnan av lumma
```

<!-- cache_translation_check_fo_de25c2c7d81e32ee82115d0bb73be924224ce521a382073ce8188e311e4667a5 -->
```
        <source>The wallet will also be stored in this directory.</source>
        <translation>Mappan verður eisini løgd í hesa skjáttuna.</translation>
    
ERR
The translation swaps the meaning of "wallet" and "directory/folder".

*   Source: "The **wallet** will also be stored in this **directory**."
*   Translation provided: "**Mappan** (The folder) verður eisini løgd í hesa **skjáttuna** (the wallet)."

It says "The folder will also be placed into this wallet," which is the reverse of the original meaning. In Bitcoin contexts, "wallet" is usually translated as "lumma" or "skjátta", and "directory" is "mappa" or "skrá".

Correct translation:
Lummin verður eisini goymdur í hesi mappuni.
```

<!-- cache_translation_check_fo_afc457a9861e6e314541de1c97b75f50c9bfc8f4443a7ca2539965090b713a24 -->
```
        <source>Form</source>
        <translation>Formil</translation>
    
UNK_LANG, not familiar with the Faroese language 'fo'.
```

<!-- cache_translation_check_fo_afc457a9861e6e314541de1c97b75f50c9bfc8f4443a7ca2539965090b713a24 -->
```
        <source>Form</source>
        <translation>Formil</translation>
    
UNK_LANG, not familiar with the Faroese language 'fo'.
```

<!-- cache_translation_check_fo_9fa34eecaac09b85734d6a145bee0c5b3bf5e8d7844df089b110cfa31b688ff3 -->
```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>Fær ikki undirrita inntøk tá mappan er løst.</translation>
    
ERR
The translation uses "inntøk" which generally means "income" or "revenue". In the context of Bitcoin transactions, "inputs" should be translated as "innsetingar" (deposits/inputs) or possibly just kept as the technical term if appropriate, but "inntøk" is misleading here. Additionally, "mappan" usually refers to a folder, whereas "wallet" in a crypto context is typically translated as "fíggjarmappa" or "pungur" (though "mappa" might be understood in a very casual sense, it's imprecise). Finally, "løst" usually means "loose" or "solved/resolved", not "locked". "Locked" is "læst".

Correct translation:
Kann ikki undirrita innsetingar meðan fíggjarmappan er læst.
```

<!-- cache_translation_check_fo_3e7f9346cf5b4ae5595987dad3fdd836cf47e3a933df6efebe82a4936d202c72 -->
```
        <source>Wallet: </source>
        <translation>Mappa:</translation>
    
ERR
"Mappa" translates to "Folder" in Faroese, not "Wallet". The correct term for a wallet (especially in a financial/Bitcoin context) is usually "Pungur" or "Money-pocket".

Correct translation:
Pungur:
```

<!-- cache_translation_check_fo_0fe93e14ddceb8b0f0a351d223da51f57c3fc96a9ee4f940cff335869c18e24a -->
```
        <source>Wallet:</source>
        <translation>Mappa:</translation>
    
ERR
In the context of Bitcoin software, "Wallet" is almost universally translated as "Lummapungur" (literally "pocket purse") or sometimes just "Pungur" in Faroese to refer to the digital wallet holding funds. "Mappa" means "folder" or "portfolio" (in the sense of a briefcase), which is not the standard terminology for a crypto wallet.

Correct translation:
Lummapungur:
```

<!-- cache_translation_check_fo_a1923d6ea5dbaecb696e55977aa6e5d65f1161f3301ff61b387170ad749ffc6c -->
```
        <source>automatically selected</source>
        <translation>Um eingi inntøk (myntir) verða vald, so vera tey vald sjálvvirkandi</translation>
    
ERR
The translation provided is much longer and more explanatory than the source text. It translates to something like "If no inputs (coins) are selected, then they will be selected automatically". While this explains the *logic* behind the automatic selection mode, it is not a direct translation of the phrase "automatically selected", which is likely a label or a state indicator. A concise translation is better suited for UI elements.

Correct translation:
sjálvvirkandi valt
```

<!-- cache_translation_check_fo_a8304a5d9b50fb7c2416b4b8a4c4de9429fcf4d76be51e499c616e73ab19b41a -->
```
        <source>%1/kvB</source>
        <translation>%1/ktB</translation>
    
ERR
The translation changes the unit from `kvB` (kilo-virtual-Bytes) to `ktB` (kilo-thousand-Bytes?), which is incorrect. In technical contexts like Bitcoin, specific units like 'kvB' should generally be preserved or translated accurately to the target language's equivalent abbreviation if it exists, but 'ktB' is not a standard Faroese abbreviation for virtual bytes. 'vB' stands for 'virtual bytes'. In Faroese, 'byte' is often just 'být' or kept as 'byte'. 'Virtual' is 'virtual' or similar.

Correct translation:
%1/kvB
```

<!-- cache_translation_check_fo_5cf359818a9627e655a2013b066649a974e4edcf8a40ed0ea9dc2409244c0479 -->
```
        <source>S&amp;ubtract fee from amount</source>
        <translation>Draga avgjald frá upphædd</translation>
    
ERR
The translation is missing the ampersand (`&`) for the keyboard shortcut, which is present in the source text (`S&amp;ubtract`).

Correct translation:
D&amp;raga avgjald frá upphædd
```

<!-- cache_translation_check_fo_4d33c62ec5f5dc5d470724a3aeae4d7e8059923e3df8025f34d30e2dcc5d1d61 -->
```
        <source>Message signed.</source>
        <translation>Boð undirritaði</translation>
    
ERR
The translation "Boð undirritaði" means "Message signed" in the sense that the message *performed* the action of signing (past tense verb), or it is grammatically incomplete. "Message signed" in English is a passive construction meaning "The message *has been* signed".

In Faroese, "Boð" is plural (neuter noun), so the past participle should likely be "undirritað".

Correct translation:
Boð undirritað
```

<!-- cache_translation_check_fo_a6bb486aa8ca885aac5fb6464b2b5298b84254b6c158f36e5cc0980d09c42685 -->
```
        <source>Received from</source>
        <translation>Inngjald</translation>
    
ERR
"Inngjald" translates more closely to "Payment" or "Deposit" (noun). While related, "Received from" is a prepositional phrase indicating the source. A more accurate translation for "Received from" in a transaction list context would be "Frá" (From) or "Móttikið frá" (Received from).

Correct translation:
Móttikið frá
```

<!-- cache_translation_check_fo_8a2a96cb484048ad909e3635404ce4e6e14dfb937d170a6e118059ec555a6ba2 -->
```
        <source>Sent to</source>
        <translation>Útgjald</translation>
    
ERR
The translation "Útgjald" means "payment" or "expense" in Faroese. While related, "Sent to" specifically indicates the recipient or the action of sending to a destination. A more accurate translation for "Sent to" in this context (likely transaction history) would be "Sent til" or simply "Til". "Útgjald" is a noun describing the transaction type, whereas "Sent to" is a label for the destination field.

Correct translation:
Sent til
```

<!-- cache_translation_check_fo_9352ff2a31e67cffc54ea3192cebfc57c7b35993e5dd8ad545abe2c19cf9568b -->
```
        <source>Sent to</source>
        <translation>Útgjøld</translation>
    
ERR
"Útgjøld" translates to "Expenses" or "Payments out" (plural noun) in Faroese. "Sent to" acts more like a prepositional phrase indicating the recipient or destination. A more accurate translation in the context of a transaction history label would be "Sent til" (Sent to) or perhaps "Móttakari" (Recipient), but strictly translating the action, "Sent til" is better. If the context is a filter or category header, "Útgjøld" *might* work as "Outgoing payments", but "Sent to" specifically asks "To whom?".

Correct translation:
Sent til
```

<!-- cache_translation_check_fo_906ac37103d5b761ab3e492f8b300e161beeb13f6b7c92b69f788bbad6c6b64b -->
```
        <source>Create a new wallet</source>
        <translation>Ger nýggja mappu</translation>
    
ERR
In the context of Bitcoin software, "wallet" should typically be translated to a term referring to a digital wallet (like 'lummapungur' or 'seðlahefti'), not "mappu". "Mappu" means "folder" or "directory" in Faroese, which is confusing in this context.

Correct translation:
Stovna nýggjan lummapung
```

<!-- cache_translation_check_fo_9500cc1f755400abc4eb48e5ad97609b6c9f37b6a5416448af9d4bd51ebee031 -->
```
        <source>Error loading wallet. Wallet requires blocks to be downloaded, and software does not currently support loading wallets while blocks are being downloaded out of order when using assumeutxo snapshots. Wallet should be able to load successfully after node sync reaches height %s</source>
        <translation>Villa undir innlesing av mappu. Mappur tørva at blokkar eru tiknir niður. Og ritbúnaðurin kann ikki, sum er, innlesa mappur undir niðurtøku av blokkum, í ósamanhangandi raðfylgju, tá assumeutxo løtumynd verur brúkt. Eftir at knúturin hevur samstilla til hædd %s skuldi eydnast at innlisið mappuna.</translation>
    
UNK_LANG
```

<!-- cache_translation_check_fo_00258c2a38755692de21f5a83af6a90db1813af7427b572a75cb4fde880e85a9 -->
```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Villa: Hendan útgávan av bitcoin-mappuni kann bert innlessa útgávu 1 dumsufílur. Læs útgávu %s dumsufílu</translation>
    
ERR
The translation misinterprets the second part of the message. The English source says "Got dumpfile with version %s" (indicating what was found). The Faroese translation says "Læs útgávu %s dumsufílu" which translates to something like "Read version %s dumpfile" (imperative or past tense "read", but the context suggests it thinks it successfully read it, whereas the English implies a mismatch error: "I received version %s"). "Læs" looks like a typo for "Las" (read, past tense) or a misunderstanding. A better phrasing would reflect that the system received or found an unsupported version.

Correct translation:
Villa: Dumpfílu-útgávan er ikki stuðlað. Hendan útgávan av bitcoin-mappuni stuðlar bert útgávu 1 dumpfílum. Fekk dumpfílu við útgávu %s
```

<!-- cache_translation_check_fo_24a3ead1fb25d206eef76c45995680cc190ac188159976da2c088723460cc657 -->
```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Vekslipeningur, ið er lægri enn støv (upphædd ið ikki loysir seg at hava og brúka), kann verða strikaður og goldin sum avgjald ístaðin</translation>
    
UNK_LANG

I am not familiar enough with the Faroese language ('fo') to fully evaluate the accuracy and grammar of this translation.
```

<!-- cache_translation_check_fo_578543f6f5b9238a414a81055b74697f680731d043c191607c4dcc944ad4f8fb -->
```
        <source>UTXO snapshot failed to validate. Restart to resume normal initial block download, or try loading a different snapshot.</source>
        <translation>Kundi ikki váttað UTXO løtumynd. Endurbyrja fyri at halda fram við vannligu blokk-niðurtøkuni, ella royn at innlesa eina aðra løtumynd.</translation>
    
ERR
The translation contains grammatical and spelling errors.
1. The modal verb 'kundi' (could) should be followed by the infinitive 'vátta', not the supine/participle 'váttað'.
2. The word 'vannligu' (normal) is misspelled; the correct spelling is 'vanligu'.

Correct translation:
Kundi ikki vátta UTXO-løtumynd. Endurbyrja fyri at halda fram við vanligu blokk-niðurtøkuni, ella royn at innlesa eina aðra løtumynd.
```

<!-- cache_translation_check_fo_c85712a0e10e26059f19c3820aceffa84da8d51ceb8cdd1d64689fac68a9826a -->
```
        <source>whitebind may only be used for incoming connections ("out" was passed)</source>
        <translation>whitebind kann bert brúkast til inngangandi sambon ("out" var ásett)</translation>
    
ERR
The translation contains a typo/misspelling. "sambon" is likely intended to be "sambond" (connections).

Correct translation:
whitebind kann bert brúkast til inngangandi sambond ("out" var ásett)
```

<!-- cache_translation_check_fo_47f1736d1816cb7ad4aaf03b3931ab7eae699ac294d5bad3699e0da25ab4d8a4 -->
```
        <source>Error creating %s</source>
        <translation>Villa undir innlesing av %s</translation>
    
ERR
The translation means "Error during reading/loading of %s", which is different from "Error creating %s". "Creating" implies making something new, while "innlesing" implies reading existing data.

Correct translation:
Villa tá %s varð stovnað
```

<!-- cache_translation_check_fo_5199692813c5d67a1bd18f0cd81bcefd5190186f64cecc1a9221b445c6b9cb57 -->
```
        <source>Failure removing transaction: %s</source>
        <translation>Miseydnaðist at strikað flyting: %s</translation>
    
ERR
The grammar in the Faroese translation is slightly incorrect. "at strikað" combines the infinitive marker "at" with a past participle "strikað". It should be the infinitive form "strika". Also, "flyting" (transaction) needs to be in the accusative case or determined by the context, but the main issue is the verb conjugation. A more natural phrasing would be "Miseydnaðist at strika flyting" or "Feilur við at strika flyting".

Correct translation:
Miseydnaðist at strika flyting: %s
```
</details>

Number of issues: 35.
