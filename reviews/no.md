# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>no</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bno%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Dette er Bitcoin-adressene dine for å motta betalinger. Bruk knappen ‘Opprett ny mottaksadresse’ i mottaksfanen for å opprette nye adresser.Signering er kun mulig med adresser av typen ‘legacy’.</translation>
    
YES  
There is a missing space after the period in the Norwegian translation before the sentence "Signering er kun mulig...". It should have a space to separate the two sentences properly, matching the format and readability of the source.

Correct translation:  
Dette er Bitcoin-adressene dine for å motta betalinger. Bruk knappen ‘Opprett ny mottaksadresse’ i mottaksfanen for å opprette nye adresser. Signering er kun mulig med adresser av typen ‘legacy’.
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Advarsel: Hvis du krypterer lommeboken din og mister passordet, vil du 1 MISTE ALLE BITCOINENE DINE 1 !</translation>
    
YES
The translation incorrectly replaces the HTML bold tags (&lt;b&gt; and &lt;/b&gt;) with "1" characters, which is incorrect and breaks the formatting. The passphrase is translated somewhat correctly as "passordet," but it is more accurate to use "passfrasen" as in the source context. The rest is mostly correct but the formatting tags must be preserved.

Correct translation:
Advarsel: Hvis du krypterer lommeboken din og mister passfrasen din, vil du &lt;b&gt;MISTE ALLE BITCOINENE DINE&lt;/b&gt;!
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Skriv inn det nye passordet for lommeboken. 1 Vennligst bruk et passord med 2 ti eller flere tilfeldige tegn 2, eller 3 åtte eller flere ord 3.</translation>
    
YES
The translation has added extraneous numbers ("1", "2", "3") which are not present in the source and breaks the sentence inappropriately. It omits the HTML formatting tags that add emphasis and a line break, which are important for preserving the original structure and emphasis.

Correct translation:
Skriv inn det nye passordet for lommeboken.&lt;br/&gt;Vennligst bruk et passord med &lt;b&gt;ti eller flere tilfeldige tegn&lt;/b&gt;, eller &lt;b&gt;åtte eller flere ord&lt;/b&gt;.
```

```
        <source>Sending addresses</source>
        <translation>Åpne node-feilsøkings- og diagnostikkonsoll</translation>
    
YES  
The translation "Åpne node-feilsøkings- og diagnostikkonsoll" means "Open node debugging and diagnostic console," which is unrelated to the source text "Sending addresses." The translation does not match the source phrase in meaning.

Correct translation:  
"Sender adresser"
```

```
        <source>Window</source>
        <translation>Vindu 
</translation>
    
YES  
The translation contains a trailing whitespace (newline) after "Vindu". The format should not have extra spaces or line breaks.

Correct translation:  
Vindu
```

```
        <source>Change:</source>
        <translation>Veksel</translation>
    
YES  
The translation "Veksel" is incorrect in this context. In Bitcoin terminology, "Change" refers to the leftover amount returned to the sender in a transaction, not the concept of "exchange" or "bill" which "Veksel" implies in Norwegian. The correct translation should reflect the Bitcoin context, typically "Vekslepenger" or simply using "Change:" as "Vekslepenger:" or "Tilbakebetaling:". A more appropriate and commonly used translation in Norwegian Bitcoin contexts is:

Correct translation:  
Vekslepenger:
```

```
        <source>Tree mode</source>
        <translation>Trevisning</translation>
    
YES
The Norwegian translation "Trevisning" is incorrect for "Tree mode." The correct translation in this Bitcoin-related context should be "Tremodus" or "Treetilstand," where "tre" means "tree" and "modus" or "tilstand" means "mode." "Trevisning" translates more to "tree view," which might not fully capture the intended meaning of "mode" here.

Correct translation:
Tremodus
```

```
        <source>Copy fee</source>
        <translation>Kopier gebyr</translation>
    
YES  
The Norwegian translation uses a mix of Norwegian and German/Danish-like structure. The correct Norwegian translation for "Copy fee" should be "Kopier gebyr" is understandable but not idiomatic. A more natural Norwegian translation would be "Kopier gebyr" or better "Kopier avgift" where "avgift" is more appropriate for fee. If "Copy fee" means the fee related to copying (in Bitcoin context), "Kopier avgift" fits better.

Correct translation:  
Kopier avgift
```

```
        <source>Window</source>
        <translation>Vindu 
</translation>
    
YES  
The translation contains a trailing whitespace (newline) after "Vindu". The format should not have extra spaces or line breaks.

Correct translation:  
Vindu
```

```
        <source>Change:</source>
        <translation>Veksel</translation>
    
YES  
The translation "Veksel" is incorrect in this context. In Bitcoin terminology, "Change" refers to the leftover amount returned to the sender in a transaction, not the concept of "exchange" or "bill" which "Veksel" implies in Norwegian. The correct translation should reflect the Bitcoin context, typically "Vekslepenger" or simply using "Change:" as "Vekslepenger:" or "Tilbakebetaling:". A more appropriate and commonly used translation in Norwegian Bitcoin contexts is:

Correct translation:  
Vekslepenger:
```

```
        <source>Copy fee</source>
        <translation>Kopier gebyr</translation>
    
YES  
The Norwegian translation uses a mix of Norwegian and German/Danish-like structure. The correct Norwegian translation for "Copy fee" should be "Kopier gebyr" is understandable but not idiomatic. A more natural Norwegian translation would be "Kopier gebyr" or better "Kopier avgift" where "avgift" is more appropriate for fee. If "Copy fee" means the fee related to copying (in Bitcoin context), "Kopier avgift" fits better.

Correct translation:  
Kopier avgift
```
</details>
