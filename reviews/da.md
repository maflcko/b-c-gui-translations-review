# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>da</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bda%5D%20low%20quality)


```
        <source>Copy the currently selected address to the system clipboard</source>
        <translation>Kopier den valgte adressen til systemets utklippstavle</translation>
    
YES  
The Danish translation has a grammar error. "valgte" should be in the indefinite form "valgte" must agree with "adressen," which is definite singular, so it should be "den valgte adresse" (not "den valgte adressen") or "den valgte adresse." Also, "Kopier" is a correct imperative form but it misses the article 'den' before "valgte adresse," also "adressen" should be "adresse." The correct phrase is:  

Correct translation:  
Kopier den valgte adresse til systemets udklipsholder
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Indstillings filen 1%1 kan være korrupt eller invalid.</translation>
    
YES  
There is a spacing error and incorrect word order in the Danish translation. "Indstillings filen" should be "Indstillingsfilen" (one word), and "%1" should directly follow without "1%" or extra spacing.

Correct translation:  
Indstillingsfilen %1 kan være korrupt eller ugyldig.
```

```
        <source>%1 behind</source>
        <translation>%1 bagud</translation>
    
YES  
The Danish word "bagud" is not commonly used in this technical context. A more accurate and idiomatic translation for "%1 behind" (e.g., blocks behind in a blockchain) would be "%1 efter" or "%1 bagud" could be understood but is less precise and less commonly used in Danish technical texts related to Bitcoin. However, the best and most common phrasing in Danish Bitcoin clients is "%1 bagud" or "%1 efter".  

Given the context, I recommend:  
%1 efter  

Correct translation:  
<translation>%1 efter</translation>
```

```
        <source>Restore a wallet from a backup file</source>
        <extracomment>Status tip for Restore Wallet menu item</extracomment>
        <translation>Gendan en pung, fra en backup fil. </translation>
    
YES  
The Danish translation has incorrect spacing and a less natural phrasing. Specifically, there should be no space before the comma, and "backup fil" should be combined into the single Danish compound noun "backupfil". Additionally, "en pung" (a purse) is not the usual term for a Bitcoin wallet in Danish; "en wallet" or "en tegnebog" is more appropriate, but "wallet" is commonly used in the Bitcoin context. Also, the English original does not have a period at the end, so the translation should omit it as well.  

Correct translation:  
Gendan en wallet fra en backupfil
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Vis værktøjslinjeknuder</translation>
    
YES
The Danish translation "Vis værktøjslinjeknuder" is incorrect. It translates to "Show toolbar nodes," which does not correspond to "Show Peers tab." The correct translation should reflect showing the "Peers" tab, likely as "Vis fanen Peers" or "Vis fanen for Peers."

Correct translation:
Vis Peers-fanen
```

```
        <source>(change)</source>
        <translation>(byttepange)</translation>
    
YES  
The Danish word for "change" in the context of Bitcoin transactions is typically "bytte" or simply "change" (often untranslated), but "byttepange" is incorrect and does not exist in Danish. The correct translation should simply be:  
(change) -> (bytte)  
or just keep it as "(change)" if it is used as a technical term. However, the most common and straightforward Danish equivalent would be:  

Correct translation:  
<translation>(bytte)</translation>
```

```
        <source>Make Blank Wallet</source>
        <translation>Lav flad tegnebog</translation>
    
YES  
The Danish translation "Lav flad tegnebog" is incorrect and awkward in this context. "Make Blank Wallet" in the context of Bitcoin means to create an empty wallet, not a "flat" wallet. The correct translation should convey creating or making a new empty wallet.

Correct translation:  
"Lav tom tegnebog"
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Kompileret uden ekstern underskriver understøttelse (nødvendig for ekstern underskriver)</translation>
    
YES  
The Danish translation is slightly awkward and incorrect in phrasing. The term "underskriver" means "signer" (a person who signs) rather than "signing" (the process/action of signing). The correct translation should use "signeringsunderstøttelse" or "understøttelse af ekstern signering" to convey "external signing support." Also, "ekstern" should be consistent with "ekstern signering" and "til ekstern signering." 

Correct translation:  
"Kompileret uden ekstern signeringsunderstøttelse (påkrævet for ekstern signering)"
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>Adressen, der er associeret med denne indgang i adresselisten. Denne kan kune ændres for afsendelsesadresser.</translation>
    
YES  
There are typographical errors in the Danish translation: "associeret" is misspelled as "associeret" (which is correct) but the sentence structure and word choice could be improved for clarity and correctness. Also, "kune" should be "kun".

Correct translation:  
"Adressen, der er associeret med denne post i adresselisten. Den kan kun ændres for afsendelsesadresser."
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Kompileret uden ekstern underskriver understøttelse (nødvendig for ekstern underskriver)</translation>
    
YES  
The Danish translation is slightly awkward and incorrect in phrasing. The term "underskriver" means "signer" (a person who signs) rather than "signing" (the process/action of signing). The correct translation should use "signeringsunderstøttelse" or "understøttelse af ekstern signering" to convey "external signing support." Also, "ekstern" should be consistent with "ekstern signering" and "til ekstern signering." 

Correct translation:  
"Kompileret uden ekstern signeringsunderstøttelse (påkrævet for ekstern signering)"
```

```
        <source>The mapped Autonomous System used for diversifying peer selection.</source>
        <translation>Afbildning fra Autonome Systemer (et Internet-Protocol-rutefindingsprefiks) til IP-adresser som bruges til at diversificere knudeforbindelser. Den engelske betegnelse er "asmap".</translation>
    
YES
The translation adds extra explanatory content not present in the source, including the phrase "Den engelske betegnelse er 'asmap'." and an explanation of Autonomous Systems that is not in the original. It also changes the meaning from describing a single "mapped Autonomous System" to a more general explanation involving prefixes and IP addresses.

A more accurate and concise translation would be:

"Afbilledet autonomt system, der bruges til at diversificere peer-udvælgelse."

This preserves the original meaning without adding unsolicited clarifications or definitions.
```

```
        <source>Ban for</source>
        <translation>Bandlys i</translation>
    
YES  
The Danish word for "ban" in this context is typically "Bloker" or "Forbyd". "Bandlys" is incorrect and not a valid Danish word. The preposition "i" does not fit here without further context.

Correct translation:  
Forbyd i
```

```
        <source>Sign Message</source>
        <translation>Singér besked</translation>
    
YES  
The Danish translation uses "Singér", which is incorrect and unnatural in this context. The proper verb is "Signér" (without the accent on 'e'), which means "Sign" as a command. Also, "besked" is correct for "message."

Correct translation:  
Signér besked
```

```
        <source>watch-only</source>
        <translation>kigge</translation>
    
YES
The Danish translation "kigge" means "to look" or "to peek," which does not accurately convey the technical term "watch-only" in the context of Bitcoin (referring to addresses or wallets that can be watched but not spent from). A more appropriate Danish translation would be "kun overvågning" or "kun til overvågning," which better captures the meaning of "watch-only."

Correct translation:
kun overvågning
```

```
        <source>Inputs</source>
        <translation>Input</translation>
    
YES  
The English source "Inputs" is plural, while the Danish translation "Input" is singular or an uninflected loanword form. The correct Danish plural form should be "Indgange" or "Indtastninger" depending on context. Given the Bitcoin context, "Inputs" refers to transaction inputs, so "Indgange" is appropriate.

Correct translation:  
Indgange
```

```
        <source>true</source>
        <translation>sand</translation>
    
YES  
The Danish translation "sand" is incorrect for the English word "true." The correct translation should be "sand" spelled as "sand" in Danish means "sand" in English, the correct word for "true" in Danish is "sand" with all lowercase but it is a false friend here. The word "true" in English translates to "sand" in Danish is false. Actually, in Danish "true" is translated as "sand", so the translation is correct. However, "sand" is lowercase in the translation but the source is lowercase as well, so that's consistent. There is no whitespace or format specifiers issues.

Wait, but the example shows this is for 'da' (Danish), and "true" translates as "sand" in Danish. That is correct.

Therefore, the translation is accurate and correct.

NO
```

```
        <source>watch-only</source>
        <translation>kigge</translation>
    
YES
The Danish translation "kigge" means "to look" or "to peek," which does not accurately convey the technical term "watch-only" in the context of Bitcoin (referring to addresses or wallets that can be watched but not spent from). A more appropriate Danish translation would be "kun overvågning" or "kun til overvågning," which better captures the meaning of "watch-only."

Correct translation:
kun overvågning
```

```
        <source>Copy full transaction details</source>
        <translation>Kopiér alle transaktion oplysninger </translation>
    
YES  
There is an unnecessary trailing space at the end of the translation. The correct translation without extra whitespace is:  
Kopiér alle transaktionsoplysninger
```

```
        <source>Watch-only</source>
        <translation>Kigge</translation>
    
YES  
The Danish translation "Kigge" is not accurate for the context of Bitcoin "Watch-only." In Bitcoin terminology, "Watch-only" refers to addresses that can be monitored but not spent from. The correct Danish term commonly used is "Kun overvågning" or "Overvågningsadresse."   
Correct translation:  
Kun overvågning
```

```
        <source>Exporting Successful</source>
        <translation>Eksport problemfri</translation>
    
YES  
The Danish translation is incorrect and unnatural. "Eksport problemfri" directly translates back to "Export problem-free," which is not idiomatic Danish nor a proper way to say "Exporting Successful."  

A correct Danish translation would be:  
"Eksport gennemført"  
or  
"Export gennemført" (though 'Eksport' is more commonly used).  

Therefore, the corrected translation should be:  
Eksport gennemført
```

```
        <source>Backup Successful</source>
        <translation>Sikkerhedskopiering problemfri</translation>
    
YES
The Danish translation "Sikkerhedskopiering problemfri" is not natural and is awkward. A better translation would be "Sikkerhedskopiering lykkedes" or "Sikkerhedskopi succesfuld" to convey "Backup Successful" clearly and correctly.

Correct translation:
Sikkerhedskopi succesfuld
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>Fejl: Dumpfilformat dokument er forkert. Fik "%s", forventet "%s".</translation>
    
YES  
The translation is slightly inaccurate. The source refers to an "identifier record" which means a specific record or entry identifying the dumpfile, whereas the translation "Dumpfilformat dokument" translates roughly to "dump file format document," which changes the meaning. A more accurate translation would maintain the focus on the "identifier record" being incorrect.

Correct translation:  
Fejl: Dumpfilens identifikationspost er forkert. Fik "%s", forventet "%s".
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Dette er det maksimale transaktionsgebyr, du betaler (ud over det normale gebyr) for, at prioritere partisk forbrugsafvigelse over almindelig møntudvælgelse.</translation>
    
YES  
The Danish translation contains a mistranslation of "partial spend avoidance." The phrase "partisk forbrugsafvigelse" translates to "biased consumption deviation," which is incorrect and confusing in this context. The correct term should reflect the concept of avoiding partial spends (i.e., "delvis forbrug" or "undgåelse af delvis forbrug"). Also, no extra spaces or format specifier errors are present.

Correct translation:  
Dette er det maksimale transaktionsgebyr, du betaler (ud over det normale gebyr) for at prioritere undgåelse af delvist forbrug frem for almindelig møntudvælgelse.
```

```
        <source>Need to specify a port with -whitebind: '%s'</source>
        <translation>Nødt til at angive en port med -whitebinde: “%s”</translation>
    
YES  
The translation contains an error in the word "-whitebinde," which incorrectly adds an "e" at the end. The correct term is "-whitebind," matching the source exactly. Additionally, quotation marks should be consistent and standard double quotes. The spacing and format specifiers are correct.

Correct translation:  
Nødt til at angive en port med -whitebind: "%s"
```

```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>Dette er transaktionsgebyret, som betaler, når du sender en transaktion.</translation>
    
YES  
The Danish translation implies "which pays" (som betaler), incorrectly attributing the action of paying to the fee rather than to the user. It should indicate that the user will pay the fee. Correct translation:  
Dette er transaktionsgebyret, som du betaler, når du sender en transaktion.
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>Transaktionen behøver en byttepenge adresse, men vi kan ikke generere den.</translation>
    
YES  
The Danish translation uses "byttepenge adresse" which is incorrect and unnatural in this context. The correct term for "change address" in the context of Bitcoin transactions is "ændringsadresse" or simply "change-adresse." Also, "Transaktionen" should be singular "Transaktionen" is German; the correct Danish word is "Transaktionen" (note: in Danish "transaktion" is singular, "transaktioner" plural, so "Transaktion" singular would be correct). Here it should be singular as in the source ("Transaction").

Correct translation:  
Transaktionen har brug for en ændringsadresse, men vi kan ikke generere den.
```

```
        <source>Unable to generate keys</source>
        <translation>U-istand til at generere nøgler</translation>
    
YES  
The Danish translation is incorrect. "U-istand" is not a proper Danish word, and the correct translation for "Unable to generate keys" should be:  
"Kan ikke generere nøgler"
```

```
        <source>Unknown change type '%s'</source>
        <translation>Ukendt byttepengetype ‘%s’</translation>
    
YES  
The translation uses the wrong word "byttepengetype" for "change type". In the Bitcoin context, "change" refers to the leftover amount in a transaction and should be translated as "ændring" or "change" related terms, not "byttepenge" (which means actual physical change like coins). Furthermore, the quotes around %s should be standard ASCII single quotes ('%s'), not the curved quotes (‘%s’), to maintain format consistency.

Correct translation:  
Ukendt ændringstype '%s'
```
</details>
