# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>nl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bnl%5D%20low%20quality)


```
        <source>After Fee:</source>
        <translation>Naheffing:</translation>
    
YES
The translation is incorrect. In the context of Bitcoin, "After Fee:" refers to the amount remaining after a fee has been deducted, not a surtax or additional levy.

Correct translation: Na de fee:
```

```
        <source>(change)</source>
        <translation>(wijzig)</translation>
    
YES: The word "wijzig" in Dutch means "change" in the sense of altering or modifying something, not the "change" as in leftover money from a transaction. In the context of Bitcoin, "change" refers to the return amount of cryptocurrency after a transaction. The correct Dutch word for this is "wisselgeld".
(wisselgeld)
```

```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Herstellen wallet &lt;b&gt;%1&lt;/b&gt;…HerstellenL


</translation>
    
YES, The translation has extra text and incorrect spacing. The correct translation is: Herstellen wallet &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Prune block storage to</source>
        <translation>Prune  block opslag op</translation>
    
YES, The translation is problematic due to an extra space after "Prune" and the word "opslag" should be "opslag naar" or "opslag tot". The word "op" is incorrect.
Prune block opslag naar
```

```
        <source>Sends %1 to %2</source>
        <translation>Verzenden %1 van %2</translation>
    
YES. The translation incorrectly uses "van" (from) instead of "naar" (to).

Verzenden %1 naar %2
```

```
        <source>Unable to calculate transaction fee or total transaction amount.</source>
        <translation>Onmogelijk om de transactie kost of totale bedrag te berekenen.</translation>
    
YES, erroneous content. The word "kost" should be "kosten" to agree with "transactie". Also, "transactie kost" is not the correct phrasing for transaction fee. The correct phrasing would be "transactiekosten".

Onmogelijk om de transactiekosten of het totale transactiebedrag te berekenen.
```

```
        <source>After Fee:</source>
        <translation>Naheffing:</translation>
    
YES
The translation is incorrect. In the context of Bitcoin, "After Fee:" refers to the amount remaining after a fee has been deducted, not a surtax or additional levy.

Correct translation: Na de fee:
```

```
        <source>When there is less transaction volume than space in the blocks, miners as well as relaying nodes may enforce a minimum fee. Paying only this minimum fee is just fine, but be aware that this can result in a never confirming transaction once there is more demand for bitcoin transactions than the network can process.</source>
        <translation>De minimale toeslag betalen is prima mits het transactievolume kleiner is dan de ruimte in de blokken. Let wel op dat dit tot gevolg kan hebben dat een transactie nooit wordt bevestigd als er meer vraag is naar bitcointransacties dan het netwerk kan verwerken.</translation>
    
YES: The translation is missing a crucial part of the source sentence. The source sentence states that paying the minimum fee is fine *when* there is less transaction volume than block space. The translation implies that paying the minimum fee is fine *if* the transaction volume is less than the block space, which reverses the conditional relationship and creates an illogical statement.

Correct translation: "Wanneer het transactievolume kleiner is dan de ruimte in de blokken, kunnen miners en doorgeefnodes een minimumprijs afdwingen. Het betalen van alleen deze minimumprijs is prima, maar wees ervan bewust dat dit ertoe kan leiden dat een transactie nooit wordt bevestigd als er meer vraag is naar bitcointransacties dan het netwerk kan verwerken."
```

```
        <source>External signer failure</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Externe ondertekenaars fout</translation>
    
YES
The translation "Externe ondertekenaars fout" is grammatically incorrect. The plural form of "ondertekenaar" (signer) is "ondertekenaars," but the error is singular, "fout." The correct translation should be "Fout externe ondertekenaar".

NO
```

```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Dubbel adres gevonden: adressen mogen maar één keer worden gebruikt worden.</translation>
    
YES, the translation is problematic. The Dutch translation has an extra "worden" which makes the sentence grammatically incorrect.

The correct translation is: "Dubbel adres gevonden: adressen mogen maar één keer worden gebruikt."
```

```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Voer het adres van de ontvanger in, bericht (zorg ervoor dat de regeleinden, spaties, tabs etc. precies kloppen) en onderteken onderaan om het bericht te verifiëren. Wees voorzicht om niet meer in de ondertekening te lezen dan in het getekende bericht zelf, om te voorkomen dat je wordt aangevallen met een man-in-the-middle attack. Houd er mee rekening dat dit alleen de ondertekende partij bewijst met het ontvangen adres, er kan niet bewezen worden dat er een transactie heeft plaatsgevonden!</translation>
    
YES, The Dutch translation misinterprets the meaning of "sender" and "receiver" and also mistranslates "sendership". The original text states that the signature proves the signing party *receives* with the address, not that they *send* to it. The current translation implies proof of sending.

Correct translation:
Voer het adres van de afzender in, bericht (zorg ervoor dat de regeleinden, spaties, tabs etc. precies kloppen) en onderteken onderaan om het bericht te verifiëren. Wees voorzichtig om niet meer in de ondertekening te lezen dan in het getekende bericht zelf, om te voorkomen dat je wordt aangevallen met een man-in-the-middle attack. Houd er rekening mee dat dit alleen bewijst dat de ondertekenende partij een bericht ontvangt met het adres, het kan niet bewijzen dat er een transactie is verzonden!
```

```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Niet beschikbaar (%1 bevestigingen, zal beschikbaar zijn na %2)</translation>
    
YES, the translation is problematic because it mistranslates "Immature" to "Niet beschikbaar" (Not available). In the context of Bitcoin, "immature" refers to a state where a transaction has not yet reached a sufficient number of confirmations to be considered spendable. A more accurate translation would be "Onrijp".

NO
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>Het PSBT bestand moet kleiner dan 100 MiB te zijn.</translation>
    
YES, The translation has a grammatical error. The phrase "te zijn" is redundant.
Het PSBT bestand moet kleiner zijn dan 100 MiB.
```

```
        <source>Error starting/committing db txn for wallet transactions removal process</source>
        <translation>Fout bij starten/toekennen db txn voor verwijderproces wallettransacties</translation>
    
YES, The translation is problematic because "committing" is translated to "toekennen" which means "to grant" or "to assign". The correct translation for "committing" in the context of database transactions is "vastleggen".

Fout bij starten/vastleggen db txn voor verwijderproces wallettransacties
```

```
        <source>Wallet loaded successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future. Legacy wallets can be migrated to a descriptor wallet with migratewallet.</source>
        <translation>Wallet succesvol aangemaakt. Het oude wallettype wordt uitgefaseerd en ondersteuning voor het maken en openen van verouderde wallets zal in de toekomst komen te vervallen. Oude wallettypes kan gemigreerd worden naar een descriptor wallet met migratewallet.</translation>
    
YES. The Dutch translation is problematic. The source text states "Wallet loaded successfully", but the translation says "Wallet succesvol aangemaakt" which translates to "Wallet created successfully".

NO
```

```
        <source>Specified -blockmaxweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Opgegeven -blockmaxweight (%d) oveschrijdt consensus maximum block weight (%d)</translation>
    
YES, The Dutch translation contains a spelling error. "oveschrijdt" should be "overschrijdt".
Opgegeven -blockmaxweight (%d) overschrijdt consensus maximum block weight (%d)
```

```
        <source>Unrecognized descriptor found. Loading wallet %s

The wallet might had been created on a newer version.
Please try running the latest software version.
</source>
        <translation>Onbekende descriptor gevonden. Portemonnee%sladen

De portemonnee is mogelijk gemaakt op een nieuwere versie.
Probeer de nieuwste softwareversie te starten.
</translation>
    
YES: The translation contains a formatting error. The format specifier "%s" is not correctly placed.
Unrecognized descriptor found. Loading wallet %s

The wallet might had been created on a newer version.
Please try running the latest software version.
Onbekende descriptor gevonden. Portemonnee %s laden

De portemonnee is mogelijk gemaakt op een nieuwere versie.
Probeer de nieuwste softwareversie te starten.
```

```
        <source>Failed to listen on any port. Use -listen=0 if you want this.</source>
        <translation>Mislukt om op welke poort dan ook te luisteren. Gebruik -listen=0 as u dit wilt.</translation>
    
YES - The Dutch translation uses "as" instead of "als" to mean "if". "Als" is the correct word to use in this context.
NO
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>Ongeldig -onion adress of hostnaam: '%s'</translation>
    
YES - The word "adress" is misspelled. It should be "adres".
Ongeldig -onion adres of hostnaam: '%s'
```

```
        <source>SQLiteDatabase: Failed to execute statement to verify database: %s</source>
        <translation>SQLite Databank: mislukt om het statement uit te voeren dat de de databank verifieert: %s</translation>
    
YES, The word "databank" is repeated, which is an error.
SQLite Databank: mislukt om het statement uit te voeren dat de databank verifieert: %s
```

```
        <source>The transaction amount is too small to pay the fee</source>
        <translation>Het transactiebedrag is te klein om transactiekosten in rekening te brengen</translation>
    
YES, The translation "Het transactiebedrag is te klein om transactiekosten in rekening te brengen" is problematic because "in rekening te brengen" means "to charge" or "to bill", which is the opposite of what the original English sentence intends to convey. The original sentence states that the amount is too small to *pay* the fee, not to charge the fee.

The correct translation should be:
Het transactiebedrag is te klein om de transactiekosten te betalen
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>Transactiebedragen moeten positief zijn</translation>
    
YES, The translation is factually incorrect. The source states "must not be negative", which means the amounts can be zero or positive. The translation states "must be positive", which excludes zero. Also, the original sentence is a negation. The translation should ideally also be a negation.
Correct translation: Transactiebedragen mogen niet negatief zijn
```

```
        <source>Transaction change output index out of range</source>
        <translation>Transactie change output is buiten bereik</translation>
    
YES, The Dutch translation "Transactie change output is buiten bereik" is missing the word "index". The corrected translation should be "Transactie change output index is buiten bereik".
```

```
        <source>Unable to start HTTP server. See debug log for details.</source>
        <translation>Niet mogelijk ok HTTP-server te starten. Zie debuglogboek voor details.</translation>
    
YES: The Dutch translation contains a grammatical error. "ok" should not be in the sentence. The correct translation is "Niet mogelijk om HTTP-server te starten. Zie debuglogboek voor details."
```

```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>User Agentcommentaar (%s) bevat onveilige karakters.</translation>
    
YES, There is a missing space between "User" and "Agentcommentaar". The correct translation should be "User Agent commentaar (%s) bevat onveilige karakters."
```
</details>
