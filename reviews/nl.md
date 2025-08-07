# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>nl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bnl%5D%20low%20quality)


```
        <source>After Fee:</source>
        <translation>Naheffing:</translation>
    
YES
The translation "Naheffing" means "additional assessment" or "supplementary tax assessment," which is not an accurate translation of "After Fee:" in the context of Bitcoin transactions. "After Fee:" indicates the amount remaining after subtracting the transaction fee.

Correct translation:
Na aftrek van kosten:
```

```
        <source>(change)</source>
        <translation>(wijzig)</translation>
    
YES
The term "change" in the Bitcoin context refers to the change output in a transaction (geld terug van een transactie), not "wijzig" (which means "modify" or "edit"). The translation is contextually incorrect.

Correct translation:
(wisselgeld)
```

```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Herstellen wallet &lt;b&gt;%1&lt;/b&gt;…HerstellenL


</translation>
    
YES
The translation is problematic: it incorrectly uses "Herstellen wallet" instead of correct Dutch ("Bezig met herstellen van portemonnee" or "Portemonnee wordt hersteld"), and it has an erroneous fragment "…HerstellenL" at the end. Also, "wallet" should be translated as "portemonnee" or "wallet" (if kept untranslated), but not as a direct English word. The extra characters and lack of proper sentence structure make it problematic.

Correct translation:
Portemonnee &lt;b&gt;%1&lt;/b&gt; wordt hersteld…
or, alternatively:
Bezig met herstellen van portemonnee &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Prune block storage to</source>
        <translation>Prune  block opslag op</translation>
    
YES
There is an issue with spacing; there is an unnecessary double space between "Prune" and "block". Also, "Prune" is untranslated and should be "Verklein" or "Snoei" in Dutch. The phrase "op" is not the best preposition here; "tot" would be more accurate for "to". 

Correct translation:
Blokopslag verkleinen tot
```

```
        <source>Sends %1 to %2</source>
        <translation>Verzenden %1 van %2</translation>
    
YES
The translation is incorrect. The English text means "Sends %1 to %2", implying that %1 is being sent to %2. However, the Dutch translation "Verzenden %1 van %2" means "Send %1 from %2", which reverses the direction of the transaction and changes the meaning. Additionally, "Verzenden" is an infinitive and should be conjugated.

Correct translation:
Verstuurt %1 naar %2
```

```
        <source>Unable to calculate transaction fee or total transaction amount.</source>
        <translation>Onmogelijk om de transactie kost of totale bedrag te berekenen.</translation>
    
YES
The Dutch translation has a couple of issues:
- "transactie kost" should be "transactiekost" (one word), or preferably "transactiekosten" (plural, as is common in Dutch).
- "totale bedrag" is incorrect; it should be "het totale bedrag".
- "Onmogelijk om ... te berekenen." is an awkward structure. A more natural rendering is "Het is niet mogelijk om ... te berekenen."

Correct translation:
Het is niet mogelijk om de transactiekosten of het totale bedrag te berekenen.
```

```
        <source>After Fee:</source>
        <translation>Naheffing:</translation>
    
YES
The translation "Naheffing" means "additional assessment" or "supplementary tax assessment," which is not an accurate translation of "After Fee:" in the context of Bitcoin transactions. "After Fee:" indicates the amount remaining after subtracting the transaction fee.

Correct translation:
Na aftrek van kosten:
```

```
        <source>When there is less transaction volume than space in the blocks, miners as well as relaying nodes may enforce a minimum fee. Paying only this minimum fee is just fine, but be aware that this can result in a never confirming transaction once there is more demand for bitcoin transactions than the network can process.</source>
        <translation>De minimale toeslag betalen is prima mits het transactievolume kleiner is dan de ruimte in de blokken. Let wel op dat dit tot gevolg kan hebben dat een transactie nooit wordt bevestigd als er meer vraag is naar bitcointransacties dan het netwerk kan verwerken.</translation>
    
YES
The translation deviates from the structure and content of the source and omits important details, such as the role of both miners and relaying nodes in enforcing a minimum fee. It also does not mention that paying only the minimum fee is fine but can result in a transaction never confirming "once there is more demand than the network can process." The causal relationship is not fully captured and the part about both miners and relaying nodes is missing.

Correct translation:
Wanneer er minder transactievolume is dan ruimte in de blokken, kunnen zowel miners als relayende knooppunten een minimumbedrag aan transactiekosten afdwingen. Alleen deze minimale vergoeding betalen is prima, maar wees ervan bewust dat dit kan resulteren in een transactie die nooit wordt bevestigd zodra er meer vraag is naar bitcointransacties dan het netwerk aankan.
```

```
        <source>External signer failure</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Externe ondertekenaars fout</translation>
    
YES
The translation "Externe ondertekenaars fout" is incorrect as "ondertekenaars" is plural, whereas "signer" is singular, and the word order is awkward. The correct translation should be:

Correct translation:
Externe ondertekenaar fout

Alternatively, to make it even more natural in Dutch:
Fout met externe ondertekenaar
```

```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Dubbel adres gevonden: adressen mogen maar één keer worden gebruikt worden.</translation>
    
YES
The Dutch translation contains a redundancy: "worden gebruikt worden" repeats the verb "worden". The correct translation should use "worden gebruikt" only once.

Correct translation:
Dubbel adres gevonden: adressen mogen maar één keer worden gebruikt.
```

```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Voer het adres van de ontvanger in, bericht (zorg ervoor dat de regeleinden, spaties, tabs etc. precies kloppen) en onderteken onderaan om het bericht te verifiëren. Wees voorzicht om niet meer in de ondertekening te lezen dan in het getekende bericht zelf, om te voorkomen dat je wordt aangevallen met een man-in-the-middle attack. Houd er mee rekening dat dit alleen de ondertekende partij bewijst met het ontvangen adres, er kan niet bewezen worden dat er een transactie heeft plaatsgevonden!</translation>
    
YES  
There are several issues:  
- "onderteken onderaan" is a mistranslation of "signature below". It should be "handtekening hieronder".  
- "Wees voorzicht" should be "Wees voorzichtig".  
- The sentence structure "om te voorkomen dat je wordt aangevallen met een man-in-the-middle attack" is awkward and unnecessarily literal; "door een man-in-the-middle aanval" is better.  
- "Houd er mee rekening" should be "Houd er rekening mee".  
- "de ondertekende partij bewijst met het ontvangen adres" is unclear. A closer rendering would be: "alleen bewijst dat de ondertekenende partij over het adres beschikt".  
- The translation omits "it cannot prove sendership of any transaction", which is closer to "het kan niet bewijzen dat er transacties mee zijn verzonden".  

Correct translation:  
Voer hieronder het adres van de ontvanger, het bericht (zorg ervoor dat u regeleinden, spaties, tabs, enzovoort exact overneemt) en de handtekening in om het bericht te verifiëren. Wees voorzichtig om niet meer betekenis aan de handtekening toe te kennen dan aan het ondertekende bericht zelf, om te voorkomen dat je slachtoffer wordt van een man-in-the-middle-aanval. Let op: dit bewijst alleen dat de ondertekenende partij het adres bezit; het kan het verzenden van transacties niet bewijzen!
```

```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Niet beschikbaar (%1 bevestigingen, zal beschikbaar zijn na %2)</translation>
    
YES
The translation is not entirely accurate. "Immature" in the context of Bitcoin refers to coins that are not yet spendable, not necessarily "not available". The term "Onvolwassen" is conventionally used for "immature" in Dutch Bitcoin contexts.

Correct translation:
Onvolwassen (%1 bevestigingen, wordt beschikbaar na %2)
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>Het PSBT bestand moet kleiner dan 100 MiB te zijn.</translation>
    
YES
The Dutch translation is grammatically incorrect. The phrase "moet kleiner dan ... te zijn" is not proper Dutch. It should be "moet kleiner zijn dan 100 MiB."

Correct translation:
Het PSBT-bestand moet kleiner zijn dan 100 MiB.
```

```
        <source>Error starting/committing db txn for wallet transactions removal process</source>
        <translation>Fout bij starten/toekennen db txn voor verwijderproces wallettransacties</translation>
    
YES
The translation uses "toekennen" for "committing," which is incorrect. "Toekennen" means "to assign" rather than "to commit" in the transaction context. A more accurate translation would use "committen" or "voltooien". Also, "verwijderproces wallettransacties" omits a preposition. A more natural phrasing is "verwijderproces van wallettransacties".

Correct translation:
Fout bij starten/committen van db-tx voor het verwijderproces van wallettransacties
```

```
        <source>Wallet loaded successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future. Legacy wallets can be migrated to a descriptor wallet with migratewallet.</source>
        <translation>Wallet succesvol aangemaakt. Het oude wallettype wordt uitgefaseerd en ondersteuning voor het maken en openen van verouderde wallets zal in de toekomst komen te vervallen. Oude wallettypes kan gemigreerd worden naar een descriptor wallet met migratewallet.</translation>
    
YES  
The translation has several issues:
1. "Wallet succesvol aangemaakt" means "Wallet successfully created," which does not match the source "Wallet loaded successfully."
2. The plural use "oude wallettypes kan" is grammatically incorrect; it should either be singular or properly conjugated for plural.
3. "aangemaakt" (created) does not fit as well in this context as "geladen" (loaded).

Correct translation:  
Wallet succesvol geladen. Het verouderde wallettype wordt uitgefaseerd en ondersteuning voor het aanmaken en openen van verouderde wallets zal in de toekomst worden verwijderd. Legacy wallets kunnen worden gemigreerd naar een descriptor-wallet met migratewallet.
```

```
        <source>Specified -blockmaxweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Opgegeven -blockmaxweight (%d) oveschrijdt consensus maximum block weight (%d)</translation>
    
YES
There is a typo in the Dutch translation: "oveschrijdt" should be "overschrijdt". Additionally, "block weight" should be translated into Dutch ("blokgewicht") for consistency and clarity. Also, an extra space may be preferred ("consensusmaximum" as one word, or "consensus maximum" as two, but "block weight" should match source formatting).

Correct translation:
Opgegeven -blockmaxweight (%d) overschrijdt het consensus maximum voor blokgewicht (%d)
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
There are several issues in the Dutch translation:
- Missing space: "Portemonnee%sladen" should be "Portemonnee %s laden".
- "De portemonnee is mogelijk gemaakt op een nieuwere versie" is unnatural; a better translation would be "De portemonnee is mogelijk aangemaakt met een nieuwere versie."
- "Probeer de nieuwste softwareversie te starten" is understandable but a more natural translation is "Probeer de nieuwste softwareversie uit te voeren."

Correct translation:
Onbekende descriptor gevonden. Portemonnee %s laden

De portemonnee is mogelijk aangemaakt met een nieuwere versie.
Probeer de nieuwste softwareversie uit te voeren.
```

```
        <source>Failed to listen on any port. Use -listen=0 if you want this.</source>
        <translation>Mislukt om op welke poort dan ook te luisteren. Gebruik -listen=0 as u dit wilt.</translation>
    
YES
The translation uses "as u dit wilt" which is incorrect. It should be "als u dit wilt". Also, "Mislukt om op welke poort dan ook te luisteren" is awkward; a better translation would be "Het is niet gelukt om op een poort te luisteren".

Correct translation:
Het is niet gelukt om op een poort te luisteren. Gebruik -listen=0 als u dit wilt.
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>Ongeldig -onion adress of hostnaam: '%s'</translation>
    
YES
The Dutch word for "address" is "adres," not "adress." There's a spelling mistake.

Correct translation:
Ongeldig -onion adres of hostnaam: '%s'
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>Transactiebedragen moeten positief zijn</translation>
    
YES
The translation changes the meaning of the source sentence. The English source states that amounts "must not be negative" (they can be zero or positive), but the Dutch translation says amounts "must be positive" (implying greater than zero).

Correct translation:
Transactiebedragen mogen niet negatief zijn
```

```
        <source>Transaction change output index out of range</source>
        <translation>Transactie change output is buiten bereik</translation>
    
YES
The translation is somewhat problematic. The English phrase "Transaction change output index out of range" specifically refers to the "index" of the change output in a transaction. The Dutch translation omits "index" making the message less precise.

Correct translation:
Transactie change output-index buiten bereik
```

```
        <source>Unable to start HTTP server. See debug log for details.</source>
        <translation>Niet mogelijk ok HTTP-server te starten. Zie debuglogboek voor details.</translation>
    
YES
The translation contains a minor grammatical error and a typo: "ok" should be "om" ("om HTTP-server te starten"), and "debuglogboek" is an awkward rendering for "debug log" in Dutch; "debuglog" is more standard.

Correct translation:
Niet mogelijk om HTTP-server te starten. Zie debuglog voor details.
```
</details>

Number of issues: 22.
