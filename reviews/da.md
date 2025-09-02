# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>da</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bda%5D%20request)


<!-- cache_translation_check_da_2218dd66486dc430cfaeb60111fb3d740d26cfdcd4e615cf1bd029344778a985 -->
```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Indstillings filen 1%1 kan være korrupt eller invalid.</translation>
    
ERR
Issues:
- The format specifier is incorrect: "1%1" instead of "%1".
- Incorrect spacing: "Indstillings filen" should be the compound "Indstillingsfilen".
- "invalid" should be "ugyldig" in Danish.

Correct translation:
Indstillingsfilen %1 kan være beskadiget eller ugyldig.
```

<!-- cache_translation_check_da_b57ef4619d8bdc078f9aa9feb62042be4ad1e601ed1ad65cac34f0b5947276ca -->
```
        <source>Restore a wallet from a backup file</source>
        <extracomment>Status tip for Restore Wallet menu item</extracomment>
        <translation>Gendan en pung, fra en backup fil. </translation>
    
ERR
Issues:
- Unnecessary comma after "pung".
- Unnecessary period and trailing space not present in source.
- "pung" is colloquial; "tegnebog" is more appropriate in this context.
- "backup fil" should be compounded as "backupfil".

Correct translation:
Gendan en tegnebog fra en backupfil
```

<!-- cache_translation_check_da_d51a8a3f47ed398d5bc9d0d9024ca4b6e70cf10500a1918c016183d79d29b653 -->
```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Vis værktøjslinjeknuder</translation>
    
ERR
The Danish translation is inaccurate. "Vis værktøjslinjeknuder" means "Show toolbar nodes" and does not reflect "Show Peers tab". In Danish UI, a tab is "fane", and "Peers" is typically kept as the English term.

Correct translation:
Vis Peers-fanen
```

<!-- cache_translation_check_da_760690408f658c1c41fd2703f708dd857dce665898a6b0d948bb06d63b662897 -->
```
        <source>(change)</source>
        <translation>(byttepange)</translation>
    
ERR
Typo in Danish: "byttepange" should be "byttepenge".

Correct translation:
(byttepenge)
```

<!-- cache_translation_check_da_de687608516804504fdc979b12546c38bb98385311f2c437ca588417fc6b253e -->
```
        <source>Make Blank Wallet</source>
        <translation>Lav flad tegnebog</translation>
    
ERR
"Flad" means "flat," not "blank." UI wording should use "Opret" and "tom" for "blank."
Correct translation:
Opret tom tegnebog
```

<!-- cache_translation_check_da_a1f932e2f3b1700c0c92e296e93b31701656710b0f3190cb64238712e481c107 -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Kompileret uden ekstern underskriver understøttelse (nødvendig for ekstern underskriver)</translation>
    
ERR
The Danish uses "underskriver" (signer) instead of "signering" (signing) and is unidiomatic. It should refer to support for external signing, not an external signer.

Correct translation:
Kompileret uden understøttelse af ekstern signering (kræves til ekstern signering)
```

<!-- cache_translation_check_da_137416b4b806250a0da1015015b5ee104f36e2d57c4a267a579e6fb796dc35e5 -->
```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>Adressen, der er associeret med denne indgang i adresselisten. Denne kan kune ændres for afsendelsesadresser.</translation>
    
ERR
Typo: "kune" should be "kun".

Correct translation:
Adressen, der er associeret med denne indgang i adresselisten. Denne kan kun ændres for afsendelsesadresser.
```

<!-- cache_translation_check_da_4c2be052ff0012655726808b2ac20b2552e48b960514702335f6a951815d0881 -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Brug separate SOCKS&amp;5 proxy, for at nå fælle via Tor-onion-tjenester:</translation>
    
ERR
Issues:
- Grammar: "separate" should be "separat".
- Word choice: "fælle" is incorrect; should be "noder" (peers).
- Punctuation: unnecessary comma after "proxy".
- Hyphenation: "SOCKS5-proxy" is standard.

Correct translation:
Brug separat SOCKS&5-proxy til at nå noder via Tor-onion-tjenester:
```

<!-- cache_translation_check_da_a1f932e2f3b1700c0c92e296e93b31701656710b0f3190cb64238712e481c107 -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Kompileret uden ekstern underskriver understøttelse (nødvendig for ekstern underskriver)</translation>
    
ERR
The Danish uses "underskriver" (signer) instead of "signering" (signing) and is unidiomatic. It should refer to support for external signing, not an external signer.

Correct translation:
Kompileret uden understøttelse af ekstern signering (kræves til ekstern signering)
```

<!-- cache_translation_check_da_aaa38a4b65c22a752136e49fcedd3b4cec91fa96095c17d7958ea59f977b07c9 -->
```
        <source>The mapped Autonomous System used for diversifying peer selection.</source>
        <translation>Afbildning fra Autonome Systemer (et Internet-Protocol-rutefindingsprefiks) til IP-adresser som bruges til at diversificere knudeforbindelser. Den engelske betegnelse er "asmap".</translation>
    
ERR
The translation adds unsolicited explanations, contains inaccuracies (it describes a mapping from AS to IPs, which is the wrong direction), and diverges from the concise source.

Correct translation:
Det kortlagte autonome system, der bruges til at diversificere peer-udvælgelsen.
```

<!-- cache_translation_check_da_e86573af9456c66bfd9ad709023124b5a35d04e8862df9da61650f05adf8ce61 -->
```
        <source>&amp;Create new receiving address</source>
        <translation>&amp;Opret ny modtager adresse</translation>
    
ERR
In Danish, "modtageradresse" should be a single compound word. The current translation has an incorrect space.

Correct translation:
&Opret ny modtageradresse
```

<!-- cache_translation_check_da_5a0e8a1939c952fa324f0aafffeb54abbbccde75bd53272ff7fe054d35aad666 -->
```
        <source>&amp;Sign Message</source>
        <translation>&amp;Singér besked</translation>
    
ERR
Misspelling in Danish: "Singér" should be "Signér".
Correct translation:
&Signér besked
```

<!-- cache_translation_check_da_4ab31582452ee8e08139b38b207ffafa1af327c30fdf5320a672524bcbd4a3c7 -->
```
        <source>Inputs</source>
        <translation>Input</translation>
    
ERR
The source is plural ("Inputs"), while the Danish translation uses "Input," which can be read as singular. In this Bitcoin context, the standard Danish term for transaction inputs is "Indgange."

Correct translation:
Indgange
```

<!-- cache_translation_check_da_7f919572b1efba10617b4271ce3bc4b61c244d2616355f3e7ae923be1eabf68b -->
```
        <source>Copy full transaction &amp;details</source>
        <translation>Kopiér alle transaktion &amp;oplysninger </translation>
    
ERR
Issues:
- Grammatical error: "alle transaktion" should be "alle transaktionsoplysninger" (compound noun).
- Trailing space at the end of the translation.

Correct translation:
Kopiér alle transaktions&oplysninger
```

<!-- cache_translation_check_da_c9509191bf0e63df1f16320af6e0d2de7a11a6dfd41a3af627e09fcd6115f66f -->
```
        <source>A&amp;bandon transaction</source>
        <translation>&amp;Opgiv transaction</translation>
    
ERR
The Danish translation incorrectly uses the English word "transaction" instead of the Danish "transaktion". The accelerator ampersand is correctly included once.

Correct translation:
&Opgiv transaktion
```

<!-- cache_translation_check_da_d8f83f0163c3e29efa20ade8d65d8c679cdf64e87ce45f5c4d9f7719fa07b499 -->
```
        <source>Exporting Successful</source>
        <translation>Eksport problemfri</translation>
    
ERR
The Danish phrasing is unnatural and grammatically incomplete. A natural translation would be:

Correct translation:
Eksporten lykkedes
```

<!-- cache_translation_check_da_f2bb764710650fa719de78d2936ef788864a9a5f0fa9c448e35e1e636d72a538 -->
```
        <source>Backup Successful</source>
        <translation>Sikkerhedskopiering problemfri</translation>
    
ERR
The Danish translation is ungrammatical; "problemfri" is an adjective and needs a verb. A natural translation is:
Sikkerhedskopiering lykkedes
```

<!-- cache_translation_check_da_36518c43dfe6068ed56907583292c312ac524e53abf865502c794cb3eb115d21 -->
```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>Fejl: Dumpfilformat dokument er forkert. Fik "%s", forventet "%s".</translation>
    
ERR
The translation mistranslates "Dumpfile identifier record" as "Dumpfilformat dokument," which changes the meaning. A more accurate Danish rendering is needed.

Correct translation:
Fejl: Dumpfilens identifikatorpost er forkert. Fik "%s", forventede "%s".
```

<!-- cache_translation_check_da_ec74e572d26fbb04cffaa4a03ef32f676966fa884511315518ac3fa512cbf597 -->
```
        <source>Need to specify a port with -whitebind: '%s'</source>
        <translation>Nødt til at angive en port med -whitebinde: “%s”</translation>
    
ERR
The option name '-whitebind' was incorrectly altered to '-whitebinde'. It should remain unchanged. Also, a more appropriate phrasing is "Der skal angives ...".

Correct translation:
Der skal angives en port med -whitebind: '%s'
```

<!-- cache_translation_check_da_f0eff68be21147d8c7d91f14268ea1b5d3c05f556bd7b97567fb196a29a5298f -->
```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>Dette er transaktionsgebyret, som betaler, når du sender en transaktion.</translation>
    
ERR
The Danish sentence is missing the subject "du" after "som", making it ungrammatical.

Correct translation:
Dette er det transaktionsgebyr, du vil betale, hvis du sender en transaktion.
```
</details>

Number of issues: 20.
