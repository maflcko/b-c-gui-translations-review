# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>nl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bnl%5D%20low%20quality)


```
        <source>After Fee:</source>
        <translation>Naheffing:</translation>
    
YES  
The translation "Naheffing:" is incorrect in this context. The English term "After Fee:" refers to the amount remaining or displayed after deducting the fee, often used in Bitcoin transaction summaries. The correct Dutch translation should convey "After Fee" as in "Na aftrek van kosten" or simply "Na kosten:". 

Correct translation:  
"Na kosten:"
```

```
        <source>(change)</source>
        <translation>(wijzig)</translation>
    
YES  
The term "change" in the context of Bitcoin transactions refers to the leftover amount returned to the sender, which is commonly translated in Dutch as "(wissel)" or "(teruggave)" rather than "(wijzig)". The word "wijzig" means "change" as a verb ("to change" or "modify"), which is incorrect here.

Correct translation:  
(change) -> (wissel)
```

```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Herstellen wallet &lt;b&gt;%1&lt;/b&gt;…HerstellenL


</translation>
    
YES  
The translation is incomplete, contains capitalization errors, and is not idiomatic Dutch. The English "Restoring Wallet" should be translated as "Portemonnee herstellen" or "Wallet herstellen" with proper spacing and casing. Also, the trailing "HerstellenL" seems like a typographical error.

Correct translation:  
Herstellen van portemonnee &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Prune block storage to</source>
        <translation>Prune  block opslag op</translation>
    
YES  
The English phrase "Prune block storage to" is a fragment typically followed by a size or limit. The Dutch translation erroneously includes an English word "Prune" and has a double space after it. Also, "prune" should be translated into Dutch (e.g., "Bespaar" or "Snoei") and the phrase "block opslag" should be more naturally phrased as "blokopslag" (one word). The preposition "op" is acceptable, meaning "to" in terms of limiting storage.

Correct translation:  
"Snoei blokopslag op"  
or more explicitly:  
"Beperk blokopslag tot"
```

```
        <source>Sends %1 to %2</source>
        <translation>Verzenden %1 van %2</translation>
    
YES  
The translation is inaccurate and misleading. The English phrase "Sends %1 to %2" means something is being sent from the subject to a recipient, while "Verzenden %1 van %2" translates as "Send %1 from %2," which changes the meaning and uses an incorrect verb form.

A correct Dutch translation would be:  
"Stuurt %1 naar %2"
```

```
        <source>Unable to calculate transaction fee or total transaction amount.</source>
        <translation>Onmogelijk om de transactie kost of totale bedrag te berekenen.</translation>
    
YES  
The translation has issues with word choice and grammar. "transactie kost" should be "transactiekosten" (transaction fees) as a compound noun, and "totale bedrag" should be "totaal bedrag" to correctly reflect "total amount." Also, the phrase "Onmogelijk om ..." is less natural than "Kan ... niet berekenen."

Correct translation:  
Kan de transactiekosten of het totale transactiebedrag niet berekenen.
```

```
        <source>After Fee:</source>
        <translation>Naheffing:</translation>
    
YES  
The translation "Naheffing:" is incorrect in this context. The English term "After Fee:" refers to the amount remaining or displayed after deducting the fee, often used in Bitcoin transaction summaries. The correct Dutch translation should convey "After Fee" as in "Na aftrek van kosten" or simply "Na kosten:". 

Correct translation:  
"Na kosten:"
```

```
        <source>When there is less transaction volume than space in the blocks, miners as well as relaying nodes may enforce a minimum fee. Paying only this minimum fee is just fine, but be aware that this can result in a never confirming transaction once there is more demand for bitcoin transactions than the network can process.</source>
        <translation>De minimale toeslag betalen is prima mits het transactievolume kleiner is dan de ruimte in de blokken. Let wel op dat dit tot gevolg kan hebben dat een transactie nooit wordt bevestigd als er meer vraag is naar bitcointransacties dan het netwerk kan verwerken.</translation>
    
YES  
The Dutch translation omits the part that both miners and relaying nodes may enforce a minimum fee. It also changes "minimum fee" to "minimale toeslag" which is less precise in this context. The original describes that when transaction volume is less than block space, miners and relaying nodes may enforce a minimum fee, and paying only that minimum fee is acceptable, but warns that if demand exceeds network capacity, the transaction may never be confirmed.

Correct translation:  
"Wanneer er minder transactievolume is dan ruimte in de blokken, kunnen miners evenals doorgeefnodes een minimumvergoeding afdwingen. Alleen deze minimumvergoeding betalen is prima, maar wees ervan bewust dat dit kan resulteren in een nooit bevestigde transactie zodra er meer vraag is naar bitcointransacties dan het netwerk kan verwerken."
```

```
        <source>External signer failure</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Externe ondertekenaars fout</translation>
    
YES  
The Dutch translation has a grammatical error and awkward phrasing. It translates to "External signers fault," which is incorrect. A better translation would be "Externe ondertekenaar fout" (singular) or more naturally "Fout bij externe ondertekenaar" to clearly indicate a failure. Since the English phrase is "External signer failure," the best concise translation is:

Correct translation:  
Externe ondertekenaarfout
```

```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Dubbel adres gevonden: adressen mogen maar één keer worden gebruikt worden.</translation>
    
YES
The translation contains a redundancy with the phrase "worden gebruikt worden." The second "worden" is unnecessary and grammatically incorrect.

Correct translation:
Dubbel adres gevonden: adressen mogen maar één keer worden gebruikt.
```

```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Voer het adres van de ontvanger in, bericht (zorg ervoor dat de regeleinden, spaties, tabs etc. precies kloppen) en onderteken onderaan om het bericht te verifiëren. Wees voorzicht om niet meer in de ondertekening te lezen dan in het getekende bericht zelf, om te voorkomen dat je wordt aangevallen met een man-in-the-middle attack. Houd er mee rekening dat dit alleen de ondertekende partij bewijst met het ontvangen adres, er kan niet bewezen worden dat er een transactie heeft plaatsgevonden!</translation>
    
YES
The translation has multiple issues:
- "onderteken onderaan" means "sign below," but the source says to enter the signature below to verify the message, not to sign again. A better phrase is "handtekening onderaan" or "handtekening hieronder".
- "Wees voorzicht" should be "Wees voorzichtig".
- "man-in-the-middle attack" should be translated as "man-in-the-middle-aanval" or "man-in-the-middle aanval".
- "Houd er mee rekening" should be "Houd er rekening mee".
- The phrase "dit alleen de ondertekende partij bewijst met het ontvangen adres" is awkward and unclear. The source says "only proves the signing party receives with the address," suggesting the signer controls the address, not that he received with it.
- The second sentence should be clearer and more accurate.

Correct translation:

Voer hieronder het adres van de ontvanger, bericht (zorg ervoor dat je regeleinden, spaties, tabs, enz. exact kopieert) en handtekening in om het bericht te verifiëren. Wees voorzichtig om niet meer in de handtekening te lezen dan in het ondertekende bericht zelf, om te voorkomen dat je wordt misleid door een man-in-the-middle-aanval. Houd er rekening mee dat dit alleen bewijst dat de ondertekenaar beschikt over het adres, maar niets zegt over het verzenden van een transactie!
```

```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Niet beschikbaar (%1 bevestigingen, zal beschikbaar zijn na %2)</translation>
    
YES  
The translation changes the meaning. The source "Immature (%1 confirmations, will be available after %2)" refers to a transaction output that is not yet spendable because it is immature, but will become available after the specified number of confirmations. The Dutch translation "Niet beschikbaar" means "Not available," which is less precise and does not convey the nuance of immaturity related to confirmations.

Correct translation:  
"Onrijp (%1 bevestigingen, zal beschikbaar zijn na %2)"
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>Het PSBT bestand moet kleiner dan 100 MiB te zijn.</translation>
    
YES  
The Dutch translation has incorrect word order and grammatical structure. The infinitive clause "te zijn" is misplaced and unnecessary here. A better translation would be a simpler and more direct sentence matching the English source:  

Correct translation:  
Het PSBT-bestand moet kleiner zijn dan 100 MiB.
```

```
        <source>Error starting/committing db txn for wallet transactions removal process</source>
        <translation>Fout bij starten/toekennen db txn voor verwijderproces wallettransacties</translation>
    
YES  
The Dutch translation is partly inaccurate and unnatural. The English "committing" is incorrectly translated as "toekennen," which means "assign" or "allocate," not "commit" in a database transaction context. Also, the phrase order is awkward, and "wallet transactions removal process" is better translated with proper word order and articles.

Correct translation:  
Fout bij starten/toevoeren van db-transactie voor het verwijderingsproces van wallettransacties
```

```
        <source>Wallet loaded successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future. Legacy wallets can be migrated to a descriptor wallet with migratewallet.</source>
        <translation>Wallet succesvol aangemaakt. Het oude wallettype wordt uitgefaseerd en ondersteuning voor het maken en openen van verouderde wallets zal in de toekomst komen te vervallen. Oude wallettypes kan gemigreerd worden naar een descriptor wallet met migratewallet.</translation>
    
YES
The translation contains slight inaccuracies and awkward phrasing:
- "Wallet succesvol aangemaakt" translates to "Wallet successfully created," which is not the same as "Wallet loaded successfully."
- "Oude wallettypes kan gemigreerd worden" has a grammatical error ("kan" should be "kunnen" to match plural "wallettypes").
- "komt te vervallen" is less idiomatic than "zal vervallen" in this context.

Correct translation:
Wallet succesvol geladen. Het oude wallettype wordt uitgefaseerd en ondersteuning voor het maken en openen van verouderde wallets zal in de toekomst vervallen. Oude wallettypes kunnen gemigreerd worden naar een descriptor wallet met migratewallet.
```

```
        <source>Specified -blockmaxweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Opgegeven -blockmaxweight (%d) oveschrijdt consensus maximum block weight (%d)</translation>
    
YES
The Dutch translation contains a spelling error: "oveschrijdt" should be "overschrijdt". Also, "consensus maximum block weight" is left partially untranslated; it would be more consistent to translate the whole phrase.

Correct translation:
Opgegeven -blockmaxweight (%d) overschrijdt het maximale consensusblokgewicht (%d)
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
    
YES  
The Dutch translation has multiple issues:  
1. Missing space between "Portemonnee" and "%s laden" which merges "Portemonnee%sladen" into one word. It should be separated with a space: "Portemonnee %s laden".  
2. The phrase "De portemonnee is mogelijk gemaakt op een nieuwere versie." is incorrect or unnatural Dutch. It attempts to translate "might had been created on a newer version" but the grammar and word choice are wrong. A better phrase is: "De portemonnee is mogelijk aangemaakt met een nieuwere versie." ("aangemaakt" means "created," and "mogelijk" suitably conveys "might").  
3. The last sentence "Probeer de nieuwste softwareversie te starten." is understandable but a more natural expression would be: "Probeer de nieuwste softwareversie uit te voeren." ("uitvoeren" is commonly used for running software).  

Correct translation:  
Onbekende descriptor gevonden. Portemonnee %s laden

De portemonnee is mogelijk aangemaakt met een nieuwere versie.  
Probeer de nieuwste softwareversie uit te voeren.
```

```
        <source>Failed to listen on any port. Use -listen=0 if you want this.</source>
        <translation>Mislukt om op welke poort dan ook te luisteren. Gebruik -listen=0 as u dit wilt.</translation>
    
YES  
The Dutch translation contains a spelling mistake: "as" should be "als".  

Correct translation:  
Mislukt om op welke poort dan ook te luisteren. Gebruik -listen=0 als u dit wilt.
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>Ongeldig -onion adress of hostnaam: '%s'</translation>
    
YES
There is a spelling mistake in the Dutch translation. "Ongeldig" is misspelled as "Ongeldig" should have a capital 'O' but more importantly, the actual correct spelling is "Ongeldig" (the first letter capitalized or not depends on context, but since it is at the start of the sentence, lowercase is fine if it is a continuation; however, in this context, it looks like a complete sentence, so capital "O" is correct). Furthermore, there is a typo in "adress" which should be "adres" in Dutch. The rest of the translation is correct and the format specifier '%s' is preserved properly.

Correct translation:  
Ongeldig -onion adres of hostnaam: '%s'
```

```
        <source>SQLiteDatabase: Failed to execute statement to verify database: %s</source>
        <translation>SQLite Databank: mislukt om het statement uit te voeren dat de de databank verifieert: %s</translation>
    
YES  
The Dutch translation is somewhat awkward and contains minor issues: "mislukt om het statement uit te voeren dat de de databank verifieert" is not idiomatic Dutch. "Databank" is less common than "database" in Dutch technical contexts. Also, there is a duplicate "de de" which is incorrect. A more natural translation would be:  

Correct translation:  
SQLiteDatabase: mislukt om de instructie uit te voeren om de database te verifiëren: %s
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>Transactiebedragen moeten positief zijn</translation>
    
YES  
The original English text states "Transaction amounts must not be negative," which means the amounts can be zero or positive, just not less than zero. The Dutch translation "Transactiebedragen moeten positief zijn" means "Transaction amounts must be positive," implying strictly greater than zero, excluding zero itself. This is more restrictive and changes the meaning.

Correct translation:  
Transactiebedragen mogen niet negatief zijn
```

```
        <source>Transaction change output index out of range</source>
        <translation>Transactie change output is buiten bereik</translation>
    
YES  
The translation mixes Dutch and English terms improperly. The word "change" should be translated into Dutch to keep consistency and clarity. Also, the phrase "index out of range" should be translated more naturally. A better translation would be:  

Correct translation:  
"Index van transactie-wisseluitgang buiten bereik"
```

```
        <source>Unable to start HTTP server. See debug log for details.</source>
        <translation>Niet mogelijk ok HTTP-server te starten. Zie debuglogboek voor details.</translation>
    
YES  
The translation contains a typo: "ok" should be "om". Also, "debug log" is translated as "debuglogboek," which is understandable, but "debuglog" or "debuglogbestand" might be more commonly used. A better translation would be:

"Niet mogelijk om HTTP-server te starten. Zie het debuglogboek voor details."
```
</details>
