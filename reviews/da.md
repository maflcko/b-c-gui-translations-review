# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>da</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bda%5D%20low%20quality)


```
        <source>Copy the currently selected address to the system clipboard</source>
        <translation>Kopier den valgte adressen til systemets utklippstavle</translation>
    
YES - The word "adressen" is definite singular in Danish, but the English source text uses "address" in an indefinite context. The correct translation should use the indefinite form "en adresse".

NO
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Indstillings filen 1%1 kan være korrupt eller invalid.</translation>
    
YES, The format specifier %1 is not correctly translated. It should be %1 in the Danish translation.
Indstillingsfilen %1 kan være korrupt eller ugyldig.
```

```
        <source>Close Wallet…</source>
        <translation>Luk Tegnebog...</translation>
    
YES, The translation is problematic because "Tegnebog" is not a standard Danish word for wallet in the context of Bitcoin. The correct translation should be "Luk pung..." or "Luk tegnebog..." if it refers to a coin purse.

Correct translation: Luk pung...
```

```
        <source>%1 behind</source>
        <translation>%1 bagud</translation>
    
YES: The translation of "behind" to "bagud" is incorrect. "Bagud" is not a Danish word. The correct Danish translation for "behind" in this context would be "bag".

%1 bag
```

```
        <source>Restore a wallet from a backup file</source>
        <extracomment>Status tip for Restore Wallet menu item</extracomment>
        <translation>Gendan en pung, fra en backup fil. </translation>
    
YES: The translation has an unnecessary space before the period.
Gendan en pung fra en backupfil.
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Vis værktøjslinjeknuder</translation>
    
YES, The translation is inaccurate and does not convey the meaning of the source text. The source text refers to a "Peers tab" which is a user interface element. The translation "Vis værktøjslinjeknuder" translates to "Show toolbar nodes", which is unrelated.

NO
```

```
        <source>(change)</source>
        <translation>(byttepange)</translation>
    
YES, the translation is erroneous. While "bytte" can mean "exchange" or "change" in Danish, "pange" is not a recognized word in this context. The correct translation for "change" in the context of Bitcoin transactions in Danish would be "restbeløb" or simply "veksel".

The correct translation is:
(restbeløb)
```

```
        <source>Make Blank Wallet</source>
        <translation>Lav flad tegnebog</translation>
    
YES, The translation is not accurate and does not convey the intended meaning. "Lav flad tegnebog" translates to "Make flat wallet" which is nonsensical in the context of Bitcoin. The English phrase "Make Blank Wallet" likely refers to creating an empty or new Bitcoin wallet.

A more appropriate translation would be "Opret tom tegnebog".

NO
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Kompileret uden ekstern underskriver understøttelse (nødvendig for ekstern underskriver)</translation>
    
YES, The Danish translation uses an incorrect word for "signing support". The correct translation should be "signering understøttelse".

Kompileret uden ekstern signering understøttelse (nødvendig for ekstern signering)
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>Adressen, der er associeret med denne indgang i adresselisten. Denne kan kune ændres for afsendelsesadresser.</translation>
    
YES - The Danish translation uses "Adressen" (The address) twice, which is redundant. It should be "Adressen, der er associeret med denne indgang i adresselisten. Den kan kun ændres for afsendelsesadresser."
```

```
        <source>Use separate SOCKS5 proxy to reach peers via Tor onion services:</source>
        <translation>Brug separate SOCKS5 proxy, for at nå fælle via Tor-onion-tjenester:</translation>
    
YES, The word "fælle" means "fellow" or "accomplice" in Danish and does not fit the context of Bitcoin peers. The correct translation for "peers" in this context is "peers" or "deltagere".

NO
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Kompileret uden ekstern underskriver understøttelse (nødvendig for ekstern underskriver)</translation>
    
YES, The Danish translation uses an incorrect word for "signing support". The correct translation should be "signering understøttelse".

Kompileret uden ekstern signering understøttelse (nødvendig for ekstern signering)
```

```
        <source>Copy Image</source>
        <translation>Kopiér foto</translation>
    
YES
The translation is inaccurate. The Danish word for "image" is "billede," not "foto."

Correct translation: Kopiér billede
```

```
        <source>The mapped Autonomous System used for diversifying peer selection.</source>
        <translation>Afbildning fra Autonome Systemer (et Internet-Protocol-rutefindingsprefiks) til IP-adresser som bruges til at diversificere knudeforbindelser. Den engelske betegnelse er "asmap".</translation>
    
YES - The translation is significantly inaccurate and misinterprets the source text. The source text refers to an "Autonomous System" as a concept used for peer selection, while the translation explains what an Autonomous System is in a technical internet protocol context and then describes a mapping to IP addresses for diversifying node connections. This is a much broader and more technical explanation than the original, and it introduces concepts not present in the source. It also wrongly states that "asmap" is the English term for this, when "asmap" itself is the term being explained in the translation.

Correct translation: "Det afbildede Autonome System, der bruges til at diversificere peer-valg."
```

```
        <source>1 hour</source>
        <translation>1 time</translation>
    
YES, The translation is incorrect. "time" is not the correct translation for "hour" in this context. The correct translation is "time".
NO
```

```
        <source>Ban for</source>
        <translation>Bandlys i</translation>
    
YES, The translation is incorrect. "Ban for" translates to "Bandlys for" in Danish.
NO
```

```
        <source>Creates a Partially Signed Bitcoin Transaction (PSBT) for use with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <translation>Laver en delvist signeret bitcointransaktion (forkortet PSBT) som kan bruges med f.eks. en offline %1 tegnebog. De kan også bruges med PSBT-kompatible hardwaretegnebøger.</translation>
    
YES - The translation introduces an unnecessary pluralization and change in meaning. The original text states that the PSBT is for use *with* a wallet, not that the wallet *can be used with* the PSBT.

Correct Translation: Laver en delvist signeret bitcointransaktion (forkortet PSBT) som kan bruges med f.eks. en offline %1 tegnebog eller en PSBT-kompatibel hardwaretegnebog.
```

```
        <source>Please, review your transaction.</source>
        <extracomment>Text to prompt a user to review the details of the transaction they are attempting to send.</extracomment>
        <translation>Venligst, vurder din transaktion.</translation>
    
YES, The word "vurder" means "assess" or "evaluate" which isn't the correct meaning for "review" in this context. The correct translation for "review" in this context would be "gennemse".
Venligst, gennemse din transaktion.
```

```
        <source>Sign Message</source>
        <translation>Singér besked</translation>
    
YES, The translation of "Sign Message" to "Singér besked" is incorrect. "Signér" is not a valid Danish word. The correct Danish translation for "Sign Message" in the context of Bitcoin is "Signér besked".

NO
```

```
        <source>watch-only</source>
        <translation>kigge</translation>
    
YES
The Danish word "kigge" means "to look" or "to peek" and is not the correct translation for "watch-only" in the context of Bitcoin. The correct translation would be "kun til visning" or "nomineret", depending on the specific nuance intended.

Here is the corrected translation:
<translation>kun til visning</translation>
```

```
        <source>Inputs</source>
        <translation>Input</translation>
    
YES
The translation should be plural to match the source text.
Correct translation: Inputs
```

```
        <source>true</source>
        <translation>sand</translation>
    
YES, the translation is incorrect. The Danish word for "true" is "sandt", not "sand".
sandt
```

```
        <source>watch-only</source>
        <translation>kigge</translation>
    
YES
The Danish word "kigge" means "to look" or "to peek" and is not the correct translation for "watch-only" in the context of Bitcoin. The correct translation would be "kun til visning" or "nomineret", depending on the specific nuance intended.

Here is the corrected translation:
<translation>kun til visning</translation>
```

```
        <source>Copy full transaction details</source>
        <translation>Kopiér alle transaktion oplysninger </translation>
    
YES, The translation is problematic because it uses an extra space before "oplysninger".
The correct translation is: Kopiér alle transaktionsoplysninger
```

```
        <source>Watch-only</source>
        <translation>Kigge</translation>
    
YES, The translation is incorrect. In the context of Bitcoin, "Watch-only" refers to an address or wallet that can monitor transactions but cannot send funds. The Danish word "Kigge" simply means "to look" or "to peek" and does not convey the intended meaning of monitoring without the ability to transact.

A more accurate translation would be "Kun til overvågning" or "Kun til at kigge på".

Correct translation: Kun til overvågning
```

```
        <source>Exporting Successful</source>
        <translation>Eksport problemfri</translation>
    
YES, The translation "Eksport problemfri" means "Export trouble-free" or "Export smooth". The word "Successful" usually translates to "Vellykket" or "Succesful" in Danish.
The correct translation should be:
Eksport vellykket
```

```
        <source>Partially Signed Transaction (*.psbt)</source>
        <translation>Partvist Signeret Transaktion (*.psbt)</translation>
    
YES, the translation contains an erroneous word.
The Danish word for "Partially" is "Delvist", not "Partvist".

Correct translation: Delvist Signeret Transaktion (*.psbt)
```

```
        <source>Backup Successful</source>
        <translation>Sikkerhedskopiering problemfri</translation>
    
YES, The translation is not accurate. "Problemfri" means "trouble-free" or "seamless", which is not the correct meaning of "successful". The correct translation of "Backup Successful" is "Sikkerhedskopiering lykkedes".
                Sikkerhedskopiering lykkedes
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>Fejl: Dumpfilformat dokument er forkert. Fik "%s", forventet "%s".</translation>
    
YES - The translation of "identifier record" to "format dokument" is inaccurate. In this context, "identifier record" refers to a specific record that identifies something, not a document format. A more accurate translation would be "identifikationsoptegnelse" or "identifikationspost".

Correct translation: Fejl: Dumpfils identifikationspost er forkert. Fik "%s", forventet "%s".
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Dette er det maksimale transaktionsgebyr, du betaler (ud over det normale gebyr) for, at prioritere partisk forbrugsafvigelse over almindelig møntudvælgelse.</translation>
    
YES, The translation incorrectly translates "partial spend avoidance" to "partisk forbrugsafvigelse". The correct Danish translation for "partial spend avoidance" in this context is "undgåelse af delvise udbetalinger".

NO
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Dette er det transaktionsgebyr, du kan kassere, hvis byttepengene er mindre end støv på dette niveau</translation>
    
YES - The translation uses "byttepengene" which translates to "the change" in the sense of money you get back after a purchase. In the context of Bitcoin, "change" refers to unspent transaction outputs. The correct Danish term for this is "restbeløb".

NO - This is the transaction fee you may discard if change is smaller than dust at this level
YES - Dette er transaktionsgebyret, du kan kassere, hvis restbeløbet er mindre end støv på dette niveau
```

```
        <source>Error reading %s! All keys read correctly, but transaction data or address metadata may be missing or incorrect.</source>
        <translation>Fejl under læsning af %s! Alle nøgler blev læst korrekt, men transaktionsdata eller indgange i adressebogen kan mangle eller være ukorrekte.</translation>
    
YES - The translation of "address metadata" to "indgange i adressebogen" is incorrect in the context of Bitcoin. "Address metadata" refers to information associated with a Bitcoin address, not entries in an address book.
Correct translation: Fejl under læsning af %s! Alle nøgler blev læst korrekt, men transaktionsdata eller adressemetadata kan mangle eller være ukorrekte.
```

```
        <source>Need to specify a port with -whitebind: '%s'</source>
        <translation>Nødt til at angive en port med -whitebinde: “%s”</translation>
    
YES, the translation is problematic. The Danish word "Nødt" should be "Nødvendigt" to convey the meaning of "Need to specify". Additionally, the Danish verb "angive" needs a preposition "en" before it, making it "angive en port". The quotation marks are also incorrect, they should be standard double quotes "".

NO
Nødvendigt at angive en port med -whitebind: "%s"
```

```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>Dette er transaktionsgebyret, som betaler, når du sender en transaktion.</translation>
    
YES - The translation incorrectly uses "betaler" (pays) instead of "betaler du" (you pay) or a similar construction to refer to the user paying the fee.
Correct translation: "Dette er transaktionsgebyret, som du betaler, når du sender en transaktion."
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>Transaktionen behøver en byttepenge adresse, men vi kan ikke generere den.</translation>
    
YES, The word "byttepenge" is not the correct term for "change address" in the context of Bitcoin transactions. The correct term is "returadresse".
Transaktionen behøver en returadresse, men vi kan ikke generere den.
```

```
        <source>Unable to generate keys</source>
        <translation>U-istand til at generere nøgler</translation>
    
YES, The translation is incorrect. The Danish word "U-istand" is not a valid word. The correct translation should be "Kan ikke generere nøgler".
Kan ikke generere nøgler
```

```
        <source>Unknown change type '%s'</source>
        <translation>Ukendt byttepengetype ‘%s’</translation>
    
YES, The translation is problematic because "byttepenge" is not the correct translation for "change" in the context of Bitcoin transactions. In Bitcoin, "change" refers to the unspent output of a transaction, not literal change money. The correct term in Danish for this concept is "retur" or "rest."

Ukendt vekseltype '%s'
```
</details>
