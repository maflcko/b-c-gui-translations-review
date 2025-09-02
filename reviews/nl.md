# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>nl</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bnl%5D%20request)


<!-- cache_translation_check_nl_13117fa3236539da3becc8bd6cfad278b705499855fc0537d48eb43d7ab3c163 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>Laad PSBT vanaf klembord...</translation>
    
ERR
The ampersand (&) indicating the shortcut key is missing from the Dutch translation. It should be present exactly once in the translation, as in the source.

Correct translation:
Laad PSBT van &klembord…
```

<!-- cache_translation_check_nl_82dd84a9cdf6394fd003031f3d65a8db9c0350393c44b06e7136336271c4d0a3 -->
```
        <source>&amp;Sending addresses</source>
        <translation>Verzendadressen</translation>
    
ERR
The translation omits the '&' which is used for keyboard shortcuts. The English source includes '&' indicating an access key. It should be present exactly once in the translation, placed appropriately.

Correct translation:
&Verzendadressen
or
Verzend&adressen
```

<!-- cache_translation_check_nl_75db58706b729502b5f861dced598f4793f1247549efb8b3d201580221ca2595 -->
```
        <source>&amp;Receiving addresses</source>
        <translation>Ontvangstadressen</translation>
    
ERR
The translation omits the ampersand (&) used for the shortcut key in the English source. The ampersand should be present exactly once.

Correct translation:
&Ontvangstadressen
```

<!-- cache_translation_check_nl_3abf29fa1c69c8582c4c7d68292ee911dc49218e9f9a0fcb4325a38b6000c379 -->
```
        <source>&amp;Window</source>
        <translation>&amp;Scherm</translation>
    
ERR
The word "Window" should be translated as "Venster" in Dutch, not "Scherm". "Scherm" means "screen", which is a different concept in a software context.

Correct translation:
&Venster
```

<!-- cache_translation_check_nl_20df24e309e758cf01e12e938217da8366bce22f134e1caec1fd5eed84a61066 -->
```
        <source>After Fee:</source>
        <translation>Naheffing:</translation>
    
ERR
The translation "Naheffing" means "additional assessment" or "supplementary tax assessment," which is not an accurate translation of "After Fee:" in the context of Bitcoin transactions. "After Fee:" indicates the amount remaining after subtracting the transaction fee.

Correct translation:
Na aftrek van kosten:
```

<!-- cache_translation_check_nl_cd904d6aa0024a04e2209e19c01b30a1141d72a301fa9c8e44f36f40857764b7 -->
```
        <source>(change)</source>
        <translation>(wijzig)</translation>
    
ERR
The term "change" in the Bitcoin context refers to the change output in a transaction (geld terug van een transactie), not "wijzig" (which means "modify" or "edit"). The translation is contextually incorrect.

Correct translation:
(wisselgeld)
```

<!-- cache_translation_check_nl_942cbbac456e4558c965f5770e51ca31c9e5fd63a3d5b735ba636433a032b57c -->
```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Herstellen wallet &lt;b&gt;%1&lt;/b&gt;…HerstellenL


</translation>
    
ERR
The translation is problematic: it incorrectly uses "Herstellen wallet" instead of correct Dutch ("Bezig met herstellen van portemonnee" or "Portemonnee wordt hersteld"), and it has an erroneous fragment "…HerstellenL" at the end. Also, "wallet" should be translated as "portemonnee" or "wallet" (if kept untranslated), but not as a direct English word. The extra characters and lack of proper sentence structure make it problematic.

Correct translation:
Portemonnee &lt;b&gt;%1&lt;/b&gt; wordt hersteld…
or, alternatively:
Bezig met herstellen van portemonnee &lt;b&gt;%1&lt;/b&gt;…
```

<!-- cache_translation_check_nl_79997e1eaa72a7fd1b7ddb3d19266c73b9092535f50f28fa77176540e3b784d7 -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Sta inkomende verbindingen toe</translation>
    
ERR
The ampersand (&) is present in the source to indicate a keyboard shortcut (for the letter 'g' in "incoming"), but it is missing from the Dutch translation. It should appear exactly once in the translation.

Correct translation:
Sta inkomende &verbindingen toe
```

<!-- cache_translation_check_nl_3abf29fa1c69c8582c4c7d68292ee911dc49218e9f9a0fcb4325a38b6000c379 -->
```
        <source>&amp;Window</source>
        <translation>&amp;Scherm</translation>
    
ERR
The word "Window" should be translated as "Venster" in Dutch, not "Scherm". "Scherm" means "screen", which is a different concept in a software context.

Correct translation:
&Venster
```

<!-- cache_translation_check_nl_70ee6b0ea83520da03de2ee4282a949fcd72ec2bf8448c3dfc784b5018bb726b -->
```
        <source>&amp;Display</source>
        <translation>&amp;Interface</translation>
    
ERR
The translation is inaccurate. The English word "Display" should be translated as "Weergave" in Dutch, not "Interface". Additionally, the ampersand is used correctly as a shortcut key indicator.

Correct translation:
&amp;Weergave
```

<!-- cache_translation_check_nl_fb007f4d4008068a4ba94d3ffedfa6baf82c51252cef236558a31fa2812dfd60 -->
```
        <source>User Interface &amp;language:</source>
        <translation>Taal &amp;gebruikersinterface:</translation>
    
ERR
The Dutch translation changes the word order in a confusing way; it should match the original's intent that "language" is the user interface language. The ampersand is correctly present exactly once.

Correct translation:
Gebruikersinterface&amp;taal:
or
&amp;Taal gebruikersinterface: (if UI guidelines prefer & at the start)

But most commonly:
&amp;Taal van de gebruikersinterface:
```

<!-- cache_translation_check_nl_51c8af39d7d32e1ccb354a0221f2dfd1baae62aec124a518e241253ce2787bc4 -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Gebruik afzonderlijke SOCKS &amp; 5-proxy om peers te bereiken via Tor Onion-services:</translation>
    
ERR
There is an incorrect space in the translation between "SOCKS" and "5". In Dutch, as in English, "SOCKS5" should not include a space. Additionally, the ampersand (&amp;) must occur exactly once in the translation as in the source. In the translation, it is placed incorrectly (as "SOCKS &amp; 5-proxy") splitting "SOCKS5", and should be placed in a similar logical position as the English original (likely before the '5').

Correct translation:
Gebruik afzonderlijke SOCKS5-&amp;proxy om peers te bereiken via Tor Onion-services:

Note: If the ampersand is meant as a shortcut key (as usual in Qt translations), it should precede a character that is appropriate as a shortcut in context, likely at the same place as the source. A close match is "SOCKS&5-proxy", unless a different shortcut makes more sense for Dutch UI conventions. Thus, a safe and literal translation following the English is:

Gebruik afzonderlijke SOCKS&5-proxy om peers te bereiken via Tor Onion-services:
```

<!-- cache_translation_check_nl_715723d70a05aff43d30bcf55458e5f4f7375df9201e745b80730096c8f5789a -->
```
        <source>Sends %1 to %2</source>
        <translation>Verzenden %1 van %2</translation>
    
ERR
The translation is incorrect. The English text means "Sends %1 to %2", implying that %1 is being sent to %2. However, the Dutch translation "Verzenden %1 van %2" means "Send %1 from %2", which reverses the direction of the transaction and changes the meaning. Additionally, "Verzenden" is an infinitive and should be conjugated.

Correct translation:
Verstuurt %1 naar %2
```

<!-- cache_translation_check_nl_870c6c0a1188d977ca63260110f5f09353262d4fc45616e577a8dd46d8c47ad6 -->
```
        <source>Unable to calculate transaction fee or total transaction amount.</source>
        <translation>Onmogelijk om de transactie kost of totale bedrag te berekenen.</translation>
    
ERR
The Dutch translation has a couple of issues:
- "transactie kost" should be "transactiekost" (one word), or preferably "transactiekosten" (plural, as is common in Dutch).
- "totale bedrag" is incorrect; it should be "het totale bedrag".
- "Onmogelijk om ... te berekenen." is an awkward structure. A more natural rendering is "Het is niet mogelijk om ... te berekenen."

Correct translation:
Het is niet mogelijk om de transactiekosten of het totale bedrag te berekenen.
```

<!-- cache_translation_check_nl_1182dbe649fa19b14a5d868e09291fd93a519e10645027dddc2b523ed6fa1468 -->
```
        <source>&amp;Unban</source>
        <translation>&amp;Maak ban voor node ongedaan</translation>
    
ERR
The translation is mostly correct, but may be too specific. "&Unban" is a menu option and usually should be translated succinctly as “&Deblokkeren” or “&Ban opheffen”, as in user interfaces brevity is preferred.

Correct translation:
&Ban opheffen
```

<!-- cache_translation_check_nl_ea2b5b1fff9d8f90f320a7732fa7138372d52207cdce1df16c9e43e99ed625d4 -->
```
        <source>&amp;Amount:</source>
        <translation>&amp;Bedrag</translation>
    
ERR
The translation omits the colon at the end, which should be preserved for consistency and formatting.

Correct translation:
&Amount: 
&Bedrag:
```

<!-- cache_translation_check_nl_20df24e309e758cf01e12e938217da8366bce22f134e1caec1fd5eed84a61066 -->
```
        <source>After Fee:</source>
        <translation>Naheffing:</translation>
    
ERR
The translation "Naheffing" means "additional assessment" or "supplementary tax assessment," which is not an accurate translation of "After Fee:" in the context of Bitcoin transactions. "After Fee:" indicates the amount remaining after subtracting the transaction fee.

Correct translation:
Na aftrek van kosten:
```

<!-- cache_translation_check_nl_87bc6787e4d4b3bbf91274021e25c34db4cc403adc4a1a295d8f16935bc6b81c -->
```
        <source>When there is less transaction volume than space in the blocks, miners as well as relaying nodes may enforce a minimum fee. Paying only this minimum fee is just fine, but be aware that this can result in a never confirming transaction once there is more demand for bitcoin transactions than the network can process.</source>
        <translation>De minimale toeslag betalen is prima mits het transactievolume kleiner is dan de ruimte in de blokken. Let wel op dat dit tot gevolg kan hebben dat een transactie nooit wordt bevestigd als er meer vraag is naar bitcointransacties dan het netwerk kan verwerken.</translation>
    
ERR
The translation deviates from the structure and content of the source and omits important details, such as the role of both miners and relaying nodes in enforcing a minimum fee. It also does not mention that paying only the minimum fee is fine but can result in a transaction never confirming "once there is more demand than the network can process." The causal relationship is not fully captured and the part about both miners and relaying nodes is missing.

Correct translation:
Wanneer er minder transactievolume is dan ruimte in de blokken, kunnen zowel miners als relayende knooppunten een minimumbedrag aan transactiekosten afdwingen. Alleen deze minimale vergoeding betalen is prima, maar wees ervan bewust dat dit kan resulteren in een transactie die nooit wordt bevestigd zodra er meer vraag is naar bitcointransacties dan het netwerk aankan.
```

<!-- cache_translation_check_nl_a3bd727c544eafffc23f90ac35115101d446b125720d11a0ea38bc88f92bfd2a -->
```
        <source>External signer failure</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Externe ondertekenaars fout</translation>
    
ERR
The translation "Externe ondertekenaars fout" is incorrect as "ondertekenaars" is plural, whereas "signer" is singular, and the word order is awkward. The correct translation should be:

Correct translation:
Externe ondertekenaar fout

Alternatively, to make it even more natural in Dutch:
Fout met externe ondertekenaar
```

<!-- cache_translation_check_nl_fd6e13019e50803c2a7fd6befa69823efbbd5526175b53f04a3985bf7d16fea5 -->
```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Dubbel adres gevonden: adressen mogen maar één keer worden gebruikt worden.</translation>
    
ERR
The Dutch translation contains a redundancy: "worden gebruikt worden" repeats the verb "worden". The correct translation should use "worden gebruikt" only once.

Correct translation:
Dubbel adres gevonden: adressen mogen maar één keer worden gebruikt.
```

<!-- cache_translation_check_nl_f72ef038718efa31d0b650ee6978ea327f876614b2985c2790c3451ab5fc2f02 -->
```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Voer het adres van de ontvanger in, bericht (zorg ervoor dat de regeleinden, spaties, tabs etc. precies kloppen) en onderteken onderaan om het bericht te verifiëren. Wees voorzicht om niet meer in de ondertekening te lezen dan in het getekende bericht zelf, om te voorkomen dat je wordt aangevallen met een man-in-the-middle attack. Houd er mee rekening dat dit alleen de ondertekende partij bewijst met het ontvangen adres, er kan niet bewezen worden dat er een transactie heeft plaatsgevonden!</translation>
    
ERR  
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

<!-- cache_translation_check_nl_e88ec3876fb13073170e938a0a163444dbd8919bc2fa5940d1d264e1f162fbbe -->
```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Niet beschikbaar (%1 bevestigingen, zal beschikbaar zijn na %2)</translation>
    
ERR
The translation is not entirely accurate. "Immature" in the context of Bitcoin refers to coins that are not yet spendable, not necessarily "not available". The term "Onvolwassen" is conventionally used for "immature" in Dutch Bitcoin contexts.

Correct translation:
Onvolwassen (%1 bevestigingen, wordt beschikbaar na %2)
```

<!-- cache_translation_check_nl_6ad57e28fff7c65389a771957dfe6e1162c003c6c8a7ef3e2059000d4566c07d -->
```
        <source>Copy full transaction &amp;details</source>
        <translation>Kopieer volledige transactie&amp;details</translation>
    
ERR
The translation is missing a space before the ampersand (it has "transactie&amp;details" instead of "transactie &amp;details"). Also the Dutch phrasing is slightly awkward; better to keep spacing consistent with the source.

Correct translation:
Kopieer volledige transactie &amp;details
```

<!-- cache_translation_check_nl_d703082867288a63338556056158c72efd7b4ef49f66edb7619713e25b4857a3 -->
```
        <source>Increase transaction &amp;fee</source>
        <translation>Verhoog transactiekosten</translation>
    
ERR
The translation is missing the keyboard shortcut ampersand (&) that appears once in the source ("Increase transaction &fee"). Also ensure the ampersand appears exactly once.

Correct translation:
Verhoog &transactiekosten
```

<!-- cache_translation_check_nl_511ea328fec278cef8c3e5c24c64307a3ed154d09896fc344cba54e804146e51 -->
```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>Het PSBT bestand moet kleiner dan 100 MiB te zijn.</translation>
    
ERR
The Dutch translation is grammatically incorrect. The phrase "moet kleiner dan ... te zijn" is not proper Dutch. It should be "moet kleiner zijn dan 100 MiB."

Correct translation:
Het PSBT-bestand moet kleiner zijn dan 100 MiB.
```

<!-- cache_translation_check_nl_eb28b0207d0e5314ecc89537b2613c85b1e3c8ace7e2ad2dc85579666c4ce9eb -->
```
        <source>Error starting/committing db txn for wallet transactions removal process</source>
        <translation>Fout bij starten/toekennen db txn voor verwijderproces wallettransacties</translation>
    
ERR
The translation uses "toekennen" for "committing," which is incorrect. "Toekennen" means "to assign" rather than "to commit" in the transaction context. A more accurate translation would use "committen" or "voltooien". Also, "verwijderproces wallettransacties" omits a preposition. A more natural phrasing is "verwijderproces van wallettransacties".

Correct translation:
Fout bij starten/committen van db-tx voor het verwijderproces van wallettransacties
```

<!-- cache_translation_check_nl_d6e6035d12e71eda46b41d4b059428fd8dc209e3d15a879d20bad4cd5eb02517 -->
```
        <source>Specified -blockmaxweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Opgegeven -blockmaxweight (%d) oveschrijdt consensus maximum block weight (%d)</translation>
    
ERR
There is a typo in the Dutch translation: "oveschrijdt" should be "overschrijdt". Additionally, "block weight" should be translated into Dutch ("blokgewicht") for consistency and clarity. Also, an extra space may be preferred ("consensusmaximum" as one word, or "consensus maximum" as two, but "block weight" should match source formatting).

Correct translation:
Opgegeven -blockmaxweight (%d) overschrijdt het consensus maximum voor blokgewicht (%d)
```

<!-- cache_translation_check_nl_d927ed55de9c3f400854f211aea3750782212b58d5428e7a1eff891619c74e75 -->
```
        <source>Failed to close file when writing block.</source>
        <translation>Kon bestand niet sluiten tijdens het schrijven van een blok.</translation>
    
ERR
The Dutch translation is grammatically incorrect / missing an article. Also "tijdens het schrijven van een blok" is understandable but "bij het schrijven van een blok" or "terwijl er een blok werd geschreven" sounds more natural.

Correct translation:
Kon het bestand niet sluiten tijdens het schrijven van een blok.
```

<!-- cache_translation_check_nl_3bda24822b73f248b10785a9938aa42b8f7e628fa5b8232a42d73e2861bd33d7 -->
```
        <source>Failed to listen on any port. Use -listen=0 if you want this.</source>
        <translation>Mislukt om op welke poort dan ook te luisteren. Gebruik -listen=0 as u dit wilt.</translation>
    
ERR
The translation uses "as u dit wilt" which is incorrect. It should be "als u dit wilt". Also, "Mislukt om op welke poort dan ook te luisteren" is awkward; a better translation would be "Het is niet gelukt om op een poort te luisteren".

Correct translation:
Het is niet gelukt om op een poort te luisteren. Gebruik -listen=0 als u dit wilt.
```

<!-- cache_translation_check_nl_e8d631fd7d147043a881f995c127036ebfdb1a0b2967e04026e622c03920a199 -->
```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>Ongeldig -onion adress of hostnaam: '%s'</translation>
    
ERR
The Dutch word for "address" is "adres," not "adress." There's a spelling mistake.

Correct translation:
Ongeldig -onion adres of hostnaam: '%s'
```

<!-- cache_translation_check_nl_33c432c0c6d00e52c76535788ef530a658c96c5190f4319062c843d594e078fb -->
```
        <source>Transaction amounts must not be negative</source>
        <translation>Transactiebedragen moeten positief zijn</translation>
    
ERR
The translation changes the meaning of the source sentence. The English source states that amounts "must not be negative" (they can be zero or positive), but the Dutch translation says amounts "must be positive" (implying greater than zero).

Correct translation:
Transactiebedragen mogen niet negatief zijn
```

<!-- cache_translation_check_nl_29bb416405192bceaedcc947a5f23c03697eb5596ef254d4f7816b055bf46493 -->
```
        <source>Transaction change output index out of range</source>
        <translation>Transactie change output is buiten bereik</translation>
    
ERR
The translation is somewhat problematic. The English phrase "Transaction change output index out of range" specifically refers to the "index" of the change output in a transaction. The Dutch translation omits "index" making the message less precise.

Correct translation:
Transactie change output-index buiten bereik
```

<!-- cache_translation_check_nl_552155f08b60a09a522b4bb2d140ad80b6a4b850cc90774f6ee2760edd1e928b -->
```
        <source>Unable to start HTTP server. See debug log for details.</source>
        <translation>Niet mogelijk ok HTTP-server te starten. Zie debuglogboek voor details.</translation>
    
ERR
The translation contains a minor grammatical error and a typo: "ok" should be "om" ("om HTTP-server te starten"), and "debuglogboek" is an awkward rendering for "debug log" in Dutch; "debuglog" is more standard.

Correct translation:
Niet mogelijk om HTTP-server te starten. Zie debuglog voor details.
```
</details>

Number of issues: 33.
