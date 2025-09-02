# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>da</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bda%5D%20request)


<!-- cache_translation_check_da_2218dd66486dc430cfaeb60111fb3d740d26cfdcd4e615cf1bd029344778a985 -->
```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Indstillings filen 1%1 kan være korrupt eller invalid.</translation>
    
ERR
There are multiple issues:
1. "Indstillings filen" should be "Indstillingsfilen" (no space).
2. "1%1" is a typographical error; the format specifier %1 should be used as in the source, i.e., "%1".
3. "korrupt eller invalid" is better phrased as "korrupt eller ugyldig" in Danish.
   
Correct translation:
Indstillingsfilen %1 kan være korrupt eller ugyldig.
```

<!-- cache_translation_check_da_b57ef4619d8bdc078f9aa9feb62042be4ad1e601ed1ad65cac34f0b5947276ca -->
```
        <source>Restore a wallet from a backup file</source>
        <extracomment>Status tip for Restore Wallet menu item</extracomment>
        <translation>Gendan en pung, fra en backup fil. </translation>
    
ERR
The translation contains minor issues:
- "pung," has an unnecessary comma.
- "backup fil" is not correctly compounded in Danish. It should be "backupfil".
- There is an extra space at the end.

Correct translation:
Gendan en pung fra en backupfil.
```

<!-- cache_translation_check_da_d51a8a3f47ed398d5bc9d0d9024ca4b6e70cf10500a1918c016183d79d29b653 -->
```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Vis værktøjslinjeknuder</translation>
    
ERR
The translation "Vis værktøjslinjeknuder" is incorrect. It translates to "Show toolbar nodes," which does not correspond to "Show Peers tab." The correct translation should refer specifically to displaying the "Peers" tab.

Correct translation:
Vis fanen Peers
```

<!-- cache_translation_check_da_760690408f658c1c41fd2703f708dd857dce665898a6b0d948bb06d63b662897 -->
```
        <source>(change)</source>
        <translation>(byttepange)</translation>
    
ERR
The translation "byttepange" is incorrect and not a recognized Danish word. The correct Danish translation for "change" in the context of Bitcoin transactions is "vekselpenge".

Correct translation:
(vekselpenge)
```

<!-- cache_translation_check_da_de687608516804504fdc979b12546c38bb98385311f2c437ca588417fc6b253e -->
```
        <source>Make Blank Wallet</source>
        <translation>Lav flad tegnebog</translation>
    
ERR
The Danish translation "Lav flad tegnebog" is incorrect. "Blak" in "Blank Wallet" refers to an empty wallet without any keys or transactions, not "flad" (flat). A more accurate translation would be:

Correct translation:
Opret tom tegnebog
```

<!-- cache_translation_check_da_a1f932e2f3b1700c0c92e296e93b31701656710b0f3190cb64238712e481c107 -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Kompileret uden ekstern underskriver understøttelse (nødvendig for ekstern underskriver)</translation>
    
ERR
The Danish translation is awkward and slightly incorrect. "Ekstern underskriver understøttelse" is not idiomatic, and "nødvendig for ekstern underskriver" is unclear in context. A better translation more naturally conveys the concept of "external signing" (digital signature process with hardware wallets):

Correct translation:
Kompileret uden understøttelse af ekstern signering (krævet for ekstern signering)
```

<!-- cache_translation_check_da_137416b4b806250a0da1015015b5ee104f36e2d57c4a267a579e6fb796dc35e5 -->
```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>Adressen, der er associeret med denne indgang i adresselisten. Denne kan kune ændres for afsendelsesadresser.</translation>
    
ERR
There are two issues: 
1. Typo in "kune", should be "kun".
2. "Adressen" (definite form) should be "Adressen" or better, "Adressen der er tilknyttet denne post i adresselisten". Also, the singular/plural sounds awkward, and "entry" is better translated as "post" or "indgang" (both are OK, but "post" is more common in UI context).

Correct translation:
Adressen, der er associeret med denne post i adresselisten. Denne kan kun ændres for afsendelsesadresser.
```

<!-- cache_translation_check_da_4c2be052ff0012655726808b2ac20b2552e48b960514702335f6a951815d0881 -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Brug separate SOCKS&amp;5 proxy, for at nå fælle via Tor-onion-tjenester:</translation>
    
ERR
There is a typo in the Danish translation: "fælle" should be "fæller" (the plural for "peers"). Furthermore, in Danish, the comma after "proxy" is unnecessary, and "SOCKS5-proxy" should be hyphenated. Hyphenation for "Tor-onion-tjenester" is acceptable, though "Tor onion-tjenester" is also common.

Correct translation:
Brug separat SOCKS5-proxy for at nå fæller via Tor-onion-tjenester:
```

<!-- cache_translation_check_da_a1f932e2f3b1700c0c92e296e93b31701656710b0f3190cb64238712e481c107 -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Kompileret uden ekstern underskriver understøttelse (nødvendig for ekstern underskriver)</translation>
    
ERR
The Danish translation is awkward and slightly incorrect. "Ekstern underskriver understøttelse" is not idiomatic, and "nødvendig for ekstern underskriver" is unclear in context. A better translation more naturally conveys the concept of "external signing" (digital signature process with hardware wallets):

Correct translation:
Kompileret uden understøttelse af ekstern signering (krævet for ekstern signering)
```

<!-- cache_translation_check_da_aaa38a4b65c22a752136e49fcedd3b4cec91fa96095c17d7958ea59f977b07c9 -->
```
        <source>The mapped Autonomous System used for diversifying peer selection.</source>
        <translation>Afbildning fra Autonome Systemer (et Internet-Protocol-rutefindingsprefiks) til IP-adresser som bruges til at diversificere knudeforbindelser. Den engelske betegnelse er "asmap".</translation>
    
ERR  
The translation is verbose, adds extra explanatory content not present in the source (e.g., the explanation of "Autonome Systemer" and the mention of "asmap"), and changes the structure of the sentence. It also introduces new terms and clarifications that may not be needed or correct for a simple translation.

Correct translation:  
Det kortlagte autonome system, der bruges til at diversificere peer-udvælgelse.
```

<!-- cache_translation_check_da_4ea0948feaae9aa73ba8472611841885b4ea2250eca3fc791aab017080cff557 -->
```
        <source>1 &amp;hour</source>
        <translation>1 &amp;time</translation>
    
ERR
The translation "1 &amp;time" is not correct Danish; "time" is Danish for "hour," but the ampersand should correctly mark the shortcut in the translated word. However, placing & before "t" makes "&time," which corresponds to the shortcut "t" (matching the original shortcut key for "h"). If the shortcut key is to remain on the first letter in the translation (which is the first letter of the word), then the translation is technically correct. However, it defeats the intent of matching the shortcut key to the corresponding letter as in the English source ("h" in "hour").

The main issue is that "time" is correct Danish for "hour," but it is not capitalized. Also, the ampersand should be placed as required by the UI.

Correct translation:
1 &amp;time

If the shortcut key must correspond to "h" (even in Danish, though uncommon), it should be 1 t&ime, but this would be awkward for Danish users since "time" starts with "t."

Therefore, since "1 &amp;time" is actually the expected translation for Danish (with the ampersand marking the shortcut key "t"), the translation is acceptable.

NO
```

<!-- cache_translation_check_da_30ce934f109661aaba340757793c2b82907b3b4fe055e92d079d432e7a0e14d3 -->
```
        <source>Ban for</source>
        <translation>Bandlys i</translation>
    
ERR
The translation "Bandlys i" is problematic. The English phrase "Ban for" indicates a duration (e.g., "Ban for 1 hour"), whereas "Bandlys i" is unnatural and misleading in Danish. The correct translation should be "Bloker i" or "Udeluk i".

Correct translation:
Bloker i
```

<!-- cache_translation_check_da_e86573af9456c66bfd9ad709023124b5a35d04e8862df9da61650f05adf8ce61 -->
```
        <source>&amp;Create new receiving address</source>
        <translation>&amp;Opret ny modtager adresse</translation>
    
ERR
In Danish, "modtager adresse" should be written as a single compound word: "modtageradresse". There should not be a space between "modtager" and "adresse". Otherwise, the translation is correct and the '&' shortcut is preserved.

Correct translation:
&Opret ny modtageradresse
```

<!-- cache_translation_check_da_5a0e8a1939c952fa324f0aafffeb54abbbccde75bd53272ff7fe054d35aad666 -->
```
        <source>&amp;Sign Message</source>
        <translation>&amp;Singér besked</translation>
    
ERR
The translation is incorrect. "Singér besked" is not correct Danish—there is an unnecessary accent over the 'e', and "singér" is not the verb "sign" in Danish. The correct term for "Sign Message" in Danish is "Underskriv besked".

Correct translation:
&amp;Underskriv besked
```

<!-- cache_translation_check_da_4ab31582452ee8e08139b38b207ffafa1af327c30fdf5320a672524bcbd4a3c7 -->
```
        <source>Inputs</source>
        <translation>Input</translation>
    
ERR
The translation is incorrect. "Inputs" in English is plural, but "Input" in Danish is singular. The correct Danish translation is "Indgange".

Correct translation:
Indgange
```

<!-- cache_translation_check_da_063a968bcc9796adc377cd2f93dc08beb75470482458360b4be424b8f42ba688 -->
```
        <source>true</source>
        <translation>sand</translation>
    
ERR
The translation is incorrect. The English word "true" should be translated as "sand" only if "sand" means "true" in Danish, which it does not. The correct Danish translation for "true" is "sand", but only as an adjective meaning "true" as in "truthful". However, in programming or logical contexts, "true" is typically left untranslated or translated as "sand".

Given the context of Bitcoin software, "true" may refer to a Boolean value, in which case "sand" is technically correct in Danish. However, usage varies: sometimes "true" is left untranslated, while "sand" is the correct literal translation. Since "sand" is used in Danish for Boolean "true", the translation is accurate.

Therefore, the translation can be considered unproblematic.

NO
```

<!-- cache_translation_check_da_7f919572b1efba10617b4271ce3bc4b61c244d2616355f3e7ae923be1eabf68b -->
```
        <source>Copy full transaction &amp;details</source>
        <translation>Kopiér alle transaktion &amp;oplysninger </translation>
    
ERR
There is a formatting issue: there is an unnecessary space at the end of the Danish translation. The shortcut key (&amp;) has been placed, which is acceptable, but "alle transaktion" is not as idiomatic as "fulde transaktionsoplysninger" for "full transaction details." A better translation would be:

Correct translation:
Kopiér fulde transaktions&amp;oplysninger
```

<!-- cache_translation_check_da_c9509191bf0e63df1f16320af6e0d2de7a11a6dfd41a3af627e09fcd6115f66f -->
```
        <source>A&amp;bandon transaction</source>
        <translation>&amp;Opgiv transaction</translation>
    
ERR
The translation is understandable but not fully accurate. "Abandon" should be translated as "Opgiv", but "transaction" should be translated as "transaktion" (the Danish word). Additionally, the shortcut (&) is preserved.

Correct translation:
&Opgiv transaktion
```

<!-- cache_translation_check_da_d8f83f0163c3e29efa20ade8d65d8c679cdf64e87ce45f5c4d9f7719fa07b499 -->
```
        <source>Exporting Successful</source>
        <translation>Eksport problemfri</translation>
    
ERR
The Danish translation "Eksport problemfri" does not accurately convey "Exporting Successful". "Problemfri" means "trouble-free", but it's not idiomatic here, and the verb "Exporting" should be translated more precisely.

Correct translation:
Eksporten var vellykket
```

<!-- cache_translation_check_da_f2bb764710650fa719de78d2936ef788864a9a5f0fa9c448e35e1e636d72a538 -->
```
        <source>Backup Successful</source>
        <translation>Sikkerhedskopiering problemfri</translation>
    
ERR  
The phrase "Sikkerhedskopiering problemfri" is not idiomatic Danish for "Backup Successful". The word "problemfri" translates as "trouble-free" or "problem free", which does not accurately convey the same meaning as "successful" in this context.

Correct translation:  
Sikkerhedskopiering fuldført  
or  
Sikkerhedskopiering lykkedes
```

<!-- cache_translation_check_da_36518c43dfe6068ed56907583292c312ac524e53abf865502c794cb3eb115d21 -->
```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>Fejl: Dumpfilformat dokument er forkert. Fik "%s", forventet "%s".</translation>
    
ERR
The Danish translation is slightly inaccurate. "Dumpfilformat dokument" does not match the source's "Dumpfile identifier record". The word "identifier record" should be translated more directly (e.g., "identifikatorpost" or "identifikationspost"). The rest of the phrase is acceptable, but "dokument" introduces confusion.

Correct translation:
Fejl: Dumpfilidentifikatorpost er forkert. Fik "%s", forventede "%s".
```

<!-- cache_translation_check_da_ec74e572d26fbb04cffaa4a03ef32f676966fa884511315518ac3fa512cbf597 -->
```
        <source>Need to specify a port with -whitebind: '%s'</source>
        <translation>Nødt til at angive en port med -whitebinde: “%s”</translation>
    
ERR
The translation contains a typographical error with the option "-whitebinde" instead of the correct "-whitebind" from the English source. Also, the quotation marks are different from the standard ones used in the source ("%s" vs. “%s”).

Correct translation:
Nødt til at angive en port med -whitebind: '%s'
```

<!-- cache_translation_check_da_f0eff68be21147d8c7d91f14268ea1b5d3c05f556bd7b97567fb196a29a5298f -->
```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>Dette er transaktionsgebyret, som betaler, når du sender en transaktion.</translation>
    
ERR
The translation omits the subject 'du' (you) before 'betaler'. It should explicitly state who pays the fee for clarity.

Correct translation:
Dette er transaktionsgebyret, som du betaler, når du sender en transaktion.
```
</details>

Number of issues: 23.
