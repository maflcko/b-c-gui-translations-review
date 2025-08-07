# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>da</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bda%5D%20low%20quality)


```
        <source>Copy the currently selected address to the system clipboard</source>
        <translation>Kopier den valgte adressen til systemets utklippstavle</translation>
    
YES
The translation uses Norwegian ("adressen", "utklippstavle") instead of correct Danish terms. In Danish, "address" is "adresse" (not "adressen"), and "clipboard" is usually "udklipsholder".

Correct translation:
Kopier den valgte adresse til systemets udklipsholder
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Indstillings filen 1%1 kan være korrupt eller invalid.</translation>
    
YES
There are multiple issues:
1. "Indstillings filen" should be "Indstillingsfilen" (no space).
2. "1%1" is a typographical error; the format specifier %1 should be used as in the source, i.e., "%1".
3. "korrupt eller invalid" is better phrased as "korrupt eller ugyldig" in Danish.
   
Correct translation:
Indstillingsfilen %1 kan være korrupt eller ugyldig.
```

```
        <source>Restore a wallet from a backup file</source>
        <extracomment>Status tip for Restore Wallet menu item</extracomment>
        <translation>Gendan en pung, fra en backup fil. </translation>
    
YES
The translation contains minor issues:
- "pung," has an unnecessary comma.
- "backup fil" is not correctly compounded in Danish. It should be "backupfil".
- There is an extra space at the end.

Correct translation:
Gendan en pung fra en backupfil.
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Vis værktøjslinjeknuder</translation>
    
YES
The translation "Vis værktøjslinjeknuder" is incorrect. It translates to "Show toolbar nodes," which does not correspond to "Show Peers tab." The correct translation should refer specifically to displaying the "Peers" tab.

Correct translation:
Vis fanen Peers
```

```
        <source>(change)</source>
        <translation>(byttepange)</translation>
    
YES
The translation "byttepange" is incorrect and not a recognized Danish word. The correct Danish translation for "change" in the context of Bitcoin transactions is "vekselpenge".

Correct translation:
(vekselpenge)
```

```
        <source>Make Blank Wallet</source>
        <translation>Lav flad tegnebog</translation>
    
YES
The Danish translation "Lav flad tegnebog" is incorrect. "Blak" in "Blank Wallet" refers to an empty wallet without any keys or transactions, not "flad" (flat). A more accurate translation would be:

Correct translation:
Opret tom tegnebog
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Kompileret uden ekstern underskriver understøttelse (nødvendig for ekstern underskriver)</translation>
    
YES
The Danish translation is awkward and slightly incorrect. "Ekstern underskriver understøttelse" is not idiomatic, and "nødvendig for ekstern underskriver" is unclear in context. A better translation more naturally conveys the concept of "external signing" (digital signature process with hardware wallets):

Correct translation:
Kompileret uden understøttelse af ekstern signering (krævet for ekstern signering)
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>Adressen, der er associeret med denne indgang i adresselisten. Denne kan kune ændres for afsendelsesadresser.</translation>
    
YES
There are two issues: 
1. Typo in "kune", should be "kun".
2. "Adressen" (definite form) should be "Adressen" or better, "Adressen der er tilknyttet denne post i adresselisten". Also, the singular/plural sounds awkward, and "entry" is better translated as "post" or "indgang" (both are OK, but "post" is more common in UI context).

Correct translation:
Adressen, der er associeret med denne post i adresselisten. Denne kan kun ændres for afsendelsesadresser.
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Kompileret uden ekstern underskriver understøttelse (nødvendig for ekstern underskriver)</translation>
    
YES
The Danish translation is awkward and slightly incorrect. "Ekstern underskriver understøttelse" is not idiomatic, and "nødvendig for ekstern underskriver" is unclear in context. A better translation more naturally conveys the concept of "external signing" (digital signature process with hardware wallets):

Correct translation:
Kompileret uden understøttelse af ekstern signering (krævet for ekstern signering)
```

```
        <source>The mapped Autonomous System used for diversifying peer selection.</source>
        <translation>Afbildning fra Autonome Systemer (et Internet-Protocol-rutefindingsprefiks) til IP-adresser som bruges til at diversificere knudeforbindelser. Den engelske betegnelse er "asmap".</translation>
    
YES  
The translation is verbose, adds extra explanatory content not present in the source (e.g., the explanation of "Autonome Systemer" and the mention of "asmap"), and changes the structure of the sentence. It also introduces new terms and clarifications that may not be needed or correct for a simple translation.

Correct translation:  
Det kortlagte autonome system, der bruges til at diversificere peer-udvælgelse.
```

```
        <source>Ban for</source>
        <translation>Bandlys i</translation>
    
YES
The translation "Bandlys i" is problematic. The English phrase "Ban for" indicates a duration (e.g., "Ban for 1 hour"), whereas "Bandlys i" is unnatural and misleading in Danish. The correct translation should be "Bloker i" or "Udeluk i".

Correct translation:
Bloker i
```

```
        <source>Sign Message</source>
        <translation>Singér besked</translation>
    
YES
The Danish word "Singér" is incorrect; the verb "to sign" in this context should be "Underskriv." "Singér" does not exist in Danish and resembles the English word "sign" with a French diacritic.

Correct translation:
Underskriv besked
```

```
        <source>watch-only</source>
        <translation>kigge</translation>
    
YES  
The translation "kigge" is inaccurate. "Watch-only" in Bitcoin wallet contexts refers specifically to addresses or wallets that can only be monitored (watched), not spent from. The Danish term "kigge" just means "look" or "watch" in an informal sense and does not capture the wallet context.

Correct translation:
kun-visning
```

```
        <source>Inputs</source>
        <translation>Input</translation>
    
YES
The translation is incorrect. "Inputs" in English is plural, but "Input" in Danish is singular. The correct Danish translation is "Indgange".

Correct translation:
Indgange
```

```
        <source>true</source>
        <translation>sand</translation>
    
YES
The translation is incorrect. The English word "true" should be translated as "sand" only if "sand" means "true" in Danish, which it does not. The correct Danish translation for "true" is "sand", but only as an adjective meaning "true" as in "truthful". However, in programming or logical contexts, "true" is typically left untranslated or translated as "sand".

Given the context of Bitcoin software, "true" may refer to a Boolean value, in which case "sand" is technically correct in Danish. However, usage varies: sometimes "true" is left untranslated, while "sand" is the correct literal translation. Since "sand" is used in Danish for Boolean "true", the translation is accurate.

Therefore, the translation can be considered unproblematic.

NO
```

```
        <source>watch-only</source>
        <translation>kigge</translation>
    
YES  
The translation "kigge" is inaccurate. "Watch-only" in Bitcoin wallet contexts refers specifically to addresses or wallets that can only be monitored (watched), not spent from. The Danish term "kigge" just means "look" or "watch" in an informal sense and does not capture the wallet context.

Correct translation:
kun-visning
```

```
        <source>Copy full transaction details</source>
        <translation>Kopiér alle transaktion oplysninger </translation>
    
YES
There is a whitespace formatting issue: there is an unnecessary space at the end of the translation. Also, a better translation for "full transaction details" would be "fulde transaktionsdetaljer". The current translation ("alle transaktion oplysninger") is understandable but less precise.

Correct translation:
Kopiér fulde transaktionsdetaljer
```

```
        <source>Watch-only</source>
        <translation>Kigge</translation>
    
YES
The translation "Kigge" is inaccurate. "Watch-only" in the context of Bitcoin wallets refers to addresses or wallets that can be watched but not spent from. The correct Danish translation should be "Kun visning" or "Kun se".

Correct translation:
Kun visning
```

```
        <source>Exporting Successful</source>
        <translation>Eksport problemfri</translation>
    
YES
The Danish translation "Eksport problemfri" does not accurately convey "Exporting Successful". "Problemfri" means "trouble-free", but it's not idiomatic here, and the verb "Exporting" should be translated more precisely.

Correct translation:
Eksporten var vellykket
```

```
        <source>Backup Successful</source>
        <translation>Sikkerhedskopiering problemfri</translation>
    
YES  
The phrase "Sikkerhedskopiering problemfri" is not idiomatic Danish for "Backup Successful". The word "problemfri" translates as "trouble-free" or "problem free", which does not accurately convey the same meaning as "successful" in this context.

Correct translation:  
Sikkerhedskopiering fuldført  
or  
Sikkerhedskopiering lykkedes
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>Fejl: Dumpfilformat dokument er forkert. Fik "%s", forventet "%s".</translation>
    
YES
The Danish translation is slightly inaccurate. "Dumpfilformat dokument" does not match the source's "Dumpfile identifier record". The word "identifier record" should be translated more directly (e.g., "identifikatorpost" or "identifikationspost"). The rest of the phrase is acceptable, but "dokument" introduces confusion.

Correct translation:
Fejl: Dumpfilidentifikatorpost er forkert. Fik "%s", forventede "%s".
```

```
        <source>Need to specify a port with -whitebind: '%s'</source>
        <translation>Nødt til at angive en port med -whitebinde: “%s”</translation>
    
YES
The translation contains a typographical error with the option "-whitebinde" instead of the correct "-whitebind" from the English source. Also, the quotation marks are different from the standard ones used in the source ("%s" vs. “%s”).

Correct translation:
Nødt til at angive en port med -whitebind: '%s'
```

```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>Dette er transaktionsgebyret, som betaler, når du sender en transaktion.</translation>
    
YES
The translation omits the subject 'du' (you) before 'betaler'. It should explicitly state who pays the fee for clarity.

Correct translation:
Dette er transaktionsgebyret, som du betaler, når du sender en transaktion.
```

```
        <source>Unable to generate keys</source>
        <translation>U-istand til at generere nøgler</translation>
    
YES
The translation contains an error. "U-istand" is not correct Danish. The correct phrase in Danish for "Unable to" is "Kan ikke".

Correct translation:
Kan ikke generere nøgler
```
</details>

Number of issues: 24.
