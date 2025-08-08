# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>no</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bno%5D%20low%20quality)


<!-- cache_translation_check_no_91a670e733feab6da6edd881c05c7127f544716707d7872c2a5f479265ea7ba6 -->
```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Dette er Bitcoin-adressene dine for å motta betalinger. Bruk knappen ‘Opprett ny mottaksadresse’ i mottaksfanen for å opprette nye adresser.Signering er kun mulig med adresser av typen ‘legacy’.</translation>
    
ERR
There is a whitespace formatting issue: there is no space between the two sentences "opprette nye adresser." and "Signering er kun mulig...".

Correct translation:
Dette er Bitcoin-adressene dine for å motta betalinger. Bruk knappen ‘Opprett ny mottaksadresse’ i mottaksfanen for å opprette nye adresser. Signering er kun mulig med adresser av typen ‘legacy’.
```

<!-- cache_translation_check_no_0388fd06d80d57ecaa9a81820f8b91aef8dd2f6f321d7b32097b458cbcca8b70 -->
```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Advarsel: Hvis du krypterer lommeboken din og mister passordet, vil du 1 MISTE ALLE BITCOINENE DINE 1 !</translation>
    
ERR
The translation is problematic. The HTML bold tags (&lt;b&gt;...&lt;/b&gt;) from the source are not retained, and "1" is incorrectly included in place of the bold tags. Additionally, "passordet" is technically "password"; "passphrase" is better translated as "passordfrase" or "passfrase". There is also an extra space before the exclamation mark.

Correct translation:
Advarsel: Hvis du krypterer lommeboken din og mister passordfrasen, vil du &lt;b&gt;MISTE ALLE BITCOINENE DINE&lt;/b&gt;!
```

<!-- cache_translation_check_no_51b22ea5c919428e5f92ec636b05c3d2da681980833b3d03617552182febea4a -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Skriv inn det nye passordet for lommeboken. 1 Vennligst bruk et passord med 2 ti eller flere tilfeldige tegn 2, eller 3 åtte eller flere ord 3.</translation>
    
ERR  
The Norwegian translation contains several issues:
- It introduces numbers ("1", "2", "3") that are not present in the source; these resemble placeholder errors.
- The translation uses "passord" ("password") instead of "passphrase" ("passordfrase" or "frasepassord"), which is particularly important in Bitcoin context.
- The HTML tags (&lt;br/&gt;, &lt;b&gt;) are lost.
- There's some awkward wording; e.g., "med 2 ti" is not correct Norwegian.

Correct translation:
Skriv inn den nye passordfrasen for lommeboken.&lt;br/&gt;Vennligst bruk en passordfrase med &lt;b&gt;ti eller flere tilfeldige tegn&lt;/b&gt;, eller &lt;b&gt;åtte eller flere ord&lt;/b&gt;.
```

<!-- cache_translation_check_no_28ee791138ff1285b1dcfcb50ee6b21f4333d0c77d1cd5ddf4567bc9ccacf7b4 -->
```
        <source>Sending addresses</source>
        <translation>Åpne node-feilsøkings- og diagnostikkonsoll</translation>
    
ERR  
The translation is incorrect. The source text "Sending addresses" should be translated as "Sendingsadresser" or "Adresser for sending" in Norwegian ('no'). Instead, the provided translation means "Open node debugging and diagnostics console," which is unrelated.

Correct translation:
Sendingsadresser
```

<!-- cache_translation_check_no_bcab3506701ead81d7c95852af7ec9aab2476fe81c8f35090a08f736e97af3b2 -->
```
        <source>Window</source>
        <translation>Vindu 
</translation>
    
ERR
The translation adds an unnecessary trailing space/newline after "Vindu", which is a formatting issue. The translation is otherwise correct, but it should not contain trailing whitespace.

Correct translation:
Vindu
```

<!-- cache_translation_check_no_f5eef8aea8cef3b364912ad5a4cef2e3c1bcb7a45375b0c5da077ba6836deaae -->
```
        <source>Change:</source>
        <translation>Veksel</translation>
    
ERR
The translation "Veksel" is not accurate in the context of Bitcoin. In Norwegian, "veksel" typically means currency exchange or a bill of exchange, which does not reflect the concept of "change" as the returned amount in a transaction. The correct term is "Vekselbeløp" or "Vekslepenger", but the most commonly used and contextually correct term in Norwegian Bitcoin wallets is "Vekslepenger".

Correct translation:
Vekslepenger:
```

<!-- cache_translation_check_no_bcab3506701ead81d7c95852af7ec9aab2476fe81c8f35090a08f736e97af3b2 -->
```
        <source>Window</source>
        <translation>Vindu 
</translation>
    
ERR
The translation adds an unnecessary trailing space/newline after "Vindu", which is a formatting issue. The translation is otherwise correct, but it should not contain trailing whitespace.

Correct translation:
Vindu
```

<!-- cache_translation_check_no_f5eef8aea8cef3b364912ad5a4cef2e3c1bcb7a45375b0c5da077ba6836deaae -->
```
        <source>Change:</source>
        <translation>Veksel</translation>
    
ERR
The translation "Veksel" is not accurate in the context of Bitcoin. In Norwegian, "veksel" typically means currency exchange or a bill of exchange, which does not reflect the concept of "change" as the returned amount in a transaction. The correct term is "Vekselbeløp" or "Vekslepenger", but the most commonly used and contextually correct term in Norwegian Bitcoin wallets is "Vekslepenger".

Correct translation:
Vekslepenger:
```
</details>

Number of issues: 8.
