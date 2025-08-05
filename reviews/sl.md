# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsl%5D%20low%20quality)


```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Vnesite novo geslo za denarnico. &lt;br/&gt;Prosimo, uporabite geslo z vsaj &lt;b&gt;10 ali več naključnimi simboli&lt;/b&gt; ali vsaj osmimi besedami.&lt;b&gt;</translation>
    
YES
The translation is incomplete and has formatting issues. The translated text ends abruptly with an opening <b> tag without closing it. Also, the original English distinguishes between "ten or more random characters" and "eight or more words," whereas the translation says "10 ali več naključnimi simboli" (10 or more random symbols), which is acceptable, but it lacks the closing tag for </b>. Furthermore, the conjunction "or" should be clearly included between the two bold phrases as in the source.

Correct translation:
Vnesite novo geslo za denarnico.&lt;br/&gt;Prosimo, uporabite geslo z vsaj &lt;b&gt;desetimi ali več naključnimi znaki&lt;/b&gt; ali &lt;b&gt;osmimi ali več besedami&lt;/b&gt;.

(Note: I replaced "10" with "desetimi" for stylistic consistency since the source uses "ten," but "10" digit is acceptable too.)
```

```
        <source>Verify message…</source>
        <translation>Preveri podpis...</translation>
    
YES
The source text "Verify message…" indicates an action to verify a message, but the translation "Preveri podpis..." means "Verify signature...," which is incorrect and changes the meaning.

Correct translation:
Preveri sporočilo...
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Preverite, če je bilo prejeto sporočilo podpisano z določenim bitcoin-naslovom.</translation>
    
YES  
The translation changes the meaning slightly and is less direct. The source implies verifying multiple messages to ensure each was signed with specific Bitcoin addresses, while the translation focuses on checking if "the received message" was signed by a specified Bitcoin address. Also, "bitcoin" should be capitalized as "Bitcoin" to match the source. The translation should also reflect the plural where appropriate.

Correct translation:  
Preverite sporočila, da zagotovite, da so bila podpisana z določenimi Bitcoin-naslovi.
```

```
        <source>Synchronizing with network…</source>
        <translation>Dohitevam omrežje ...</translation>
    
YES  
The Slovenian translation is incorrect and contains a misspelling. The correct verb is "Dohitevam," not "Dohitevam." Also, the ellipsis should be the single Unicode character (…) without spaces before or after. The correct translation is:  
Dohitevam omrežje…
```

```
        <source>Quantity:</source>
        <translation>Št. vhodov:</translation>
    
YES  
The English source "Quantity:" is a general term, typically translated as "Količina:" in Slovenian. The provided translation "Št. vhodov:" means "Number of inputs:", which is more specific and context-dependent. Unless the context explicitly requires specifying "Number of inputs," this translation is inaccurate.

Correct translation:  
Količina:
```

```
        <source>Received with label</source>
        <translation>Oznaka priliva</translation>
    
YES  
The translation "Oznaka priliva" is not correct Slovene for "Received with label." It appears to be a literal, but inaccurate translation possibly mixing other languages. The correct Slovene translation should convey the meaning of receiving something associated with a label.

Correct translation:  
Prejeto z oznako
```

```
        <source>Received with address</source>
        <translation>Naslov priliva</translation>
    
YES  
The translation "Naslov priliva" is incorrect for the context of Bitcoin. "Naslov" means "address," which is correct, but "priliva" means "inflow" or "income," which is not an appropriate translation of "Received with" here. The English phrase "Received with address" in Bitcoin context generally means "received using the address" or "received at the address."

A more accurate Slovene translation would be:  
"Prejeto z naslovom"
```

```
        <source>External signer</source>
        <translation>Zunanji podpisni</translation>
    
YES  
The Slovenian translation is grammatically incorrect. "Zunanji podpisni" is incomplete and does not appropriately convey "External signer." It should be "Zunanji podpisnik."

Correct translation:  
Zunanji podpisnik
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Prevedeno brez podpore za zunanje podpisovanje</translation>
    
YES
The translation "Prevedeno brez podpore za zunanje podpisovanje" means "Translated without support for external signing," which is incorrect. The English source says "Compiled without external signing support (required for external signing)," referring to software compilation, not translation.

Correct translation:
"Sestavljeno brez podpore za zunanje podpisovanje (zahtevano za zunanje podpisovanje)"
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>V  tem direktoriju bo shranjenih vsaj %1 GB podatkov, količina podatkov pa bo s časom naraščala.</translation>
    
YES  
The translation uses "V  tem direktoriju" with an extra space after "V", which is a formatting issue. Also, "v tem direktoriju" is incorrect Slovenian; the correct locative form is "v tem imeniku" or "v tem imeniku" (for directory), but commonly "v tem imeniku" is acceptable. The rest of the sentence is accurate.

Correct translation:  
"V tem imeniku bo shranjenih vsaj %1 GB podatkov, količina podatkov pa bo s časom naraščala."
```

```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>%1 trenutno dohiteva omrežje. Od soležnikov bodo preneseni in preverjeni zaglavja in bloki do vrha verige.</translation>
    
YES  
The Slovene translation has an issue with the word "dohiteva omrežje," which translates to "catching up with the network" rather than synchronizing. Also, "od soležnikov" is misspelled; it should be "od sodelavcev" or preferably "od sodelujočih" or simply "od sodelujočih vozlišč" (from peers). The original English phrase is about syncing, downloading headers and blocks from peers, and validating them until the tip of the blockchain is reached. The translation also has a missing subject or extra spacing and slight awkwardness.

Correct translation:  
%1 trenutno sinhronizira. Prenesel bo glave in bloke od sodelujočih ter jih preverjal, dokler ne doseže vrha verige blokov.
```

```
        <source>Enable PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Omogoči nastavitve DPBT</translation>
    
YES  
The abbreviation "PSBT" is not translated correctly; it has been changed to "DPBT," which is incorrect and misleading. The correct translation should keep "PSBT" as is because it is a standard acronym in Bitcoin terminology. Also, "Enable controls" is better translated as "Omogoči kontrole" or "Omogoči upravljanje," but "nastavitve" means "settings," which slightly changes the meaning. "Controls" refers to user interface controls rather than settings.

Correct translation:  
Omogoči kontrole PSBT
```

```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Ali naj se prikaže upravljanje z DPBT</translation>
    
YES
The translation is missing a question mark or a verb form to clearly indicate the conditional or interrogative nature of "Whether to show PSBT controls." A clearer, more accurate translation in Slovene would be:
"Ali naj se prikažejo kontrolniki PSBT."
```

```
        <source>Third-party transaction URLs</source>
        <translation>Zunanji URL-ji</translation>
    
YES  
The translation "Zunanji URL-ji" means "External URLs" rather than "Third-party transaction URLs". It omits the concept of "transaction" which is important in the context of Bitcoin. A more accurate translation would include the word for "transaction" (transakcija).  

Correct translation:  
"Tretji strani URL-ji transakcij"  
or more naturally:  
"URL-ji transakcij tretjih oseb"
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Prevedeno brez podpore za zunanje podpisovanje</translation>
    
YES
The translation "Prevedeno brez podpore za zunanje podpisovanje" means "Translated without support for external signing," which is incorrect. The English source says "Compiled without external signing support (required for external signing)," referring to software compilation, not translation.

Correct translation:
"Sestavljeno brez podpore za zunanje podpisovanje (zahtevano za zunanje podpisovanje)"
```

```
        <source>none</source>
        <translation>jih ni</translation>
    
YES
The translation "jih ni" does not correspond to the English word "none" in Slovenian. The correct Slovenian translation for "none" is "noben" (for masculine singular), or simply "nič" depending on context, but commonly "noben" or "ni" is used. "jih ni" means "they are not" or "there are none of them," which is a phrase, not a direct translation of the word "none."

Correct translation:
noben
```

```
        <source>Client will be shut down. Do you want to proceed?</source>
        <extracomment>Text asking the user to confirm if they would like to proceed with a client shutdown.</extracomment>
        <translation>Program bo zaustavljen. Želite nadaljevati z izhodom?</translation>
    
YES  
The translation "Program bo zaustavljen. Želite nadaljevati z izhodom?" has issues:  
- "zaustavljen" is not standard Slovenian; the correct Slovenian word for "shut down" in this context is "ustavljen" or "izklopljen".  
- "Program" is less common than "Odjemalec" (client) for "Client" in the Bitcoin context.  
- The second sentence literally means "Do you want to continue with exiting?" whereas the source asks "Do you want to proceed?" which is more general; a better translation would not specify "izhodom" (exiting) unless the source explicitly mentions that.  

Correct translation:  
"Odjemalec bo ustavljen. Želite nadaljevati?"
```

```
        <source>own address</source>
        <translation>lasten naslov</translation>
    
YES  
The Slovenian translation "lasten naslov" is incorrect in this Bitcoin context. The English "own address" refers to "your own address" (e.g., wallet or network address). The correct Slovenian phrase is "lasten naslov" would mean "private address" or "own address" literally, but in the Bitcoin context the accepted translation is "lasten naslov" or better "lasten naslov" is actually correct. However, to confirm, "own address" is correctly translated as "lasten naslov" in Slovenian. So is it unproblematic?

Actually, "lasten naslov" is the correct Slovenian translation of "own address" and is commonly used in Bitcoin software in Slovenian localization.

No format specifiers are involved, and no extra whitespace issues.

Therefore, the translation is correct and unproblematic.

Corrected output:

NO
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Ni mogoče zagnati rokovalca plačilnih povezav tipa bitcoin:.</translation>
    
YES  
The translation contains a grammatical error and an unnecessary colon at the end. The phrase "Ni mogoče" is incorrect in Slovene; it should be "Ni mogoče zagnati" or more naturally "Ni mogoče zagnati bitcoin: upravljalnika click-to-pay" or "Ni mogoče zagnati upravljalnika bitcoin click-to-pay". The colon in the source is part of the original phrase and should not be duplicated or followed by an extra colon in Slovene.

Correct translation:  
Ni mogoče zagnati bitcoin upravljalnika click-to-pay
```

```
        <source>Open the %1 debug log file from the current data directory. This can take a few seconds for large log files.</source>
        <translation>Odpre %1 razhroščevalni dnevnik debug.log, ki se nahaja v trenutni podatkovni mapi. Če je datoteka velika, lahko postopek traja nekaj sekund.</translation>
    
YES  
The translation mixes English and Slovenian incorrectly and does not correctly translate "debug log file." The phrase "razhroščevalni dnevnik debug.log" combines Slovenian "razhroščevalni dnevnik" and English "debug.log" unnecessarily and is somewhat redundant or confusing. Also, "debug log file" should be fully translated (e.g., "dnevnik odpravljanja napak") or retain "debug log datoteka" consistently. The source only refers to "%1 debug log file," so "%1" should directly precede "datoteka dnevnika odpravljanja napak" or a similar phrasing.

Correct translation:  
Odprite %1 datoteko dnevnika odpravljanja napak iz trenutne podatkovne mape. Za velike datoteke lahko postopek traja nekaj sekund.
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Odhodna dostavljalka naslovov: krakoživa, zaproša za naslove</translation>
    
YES  
The translation has issues with word choice and spacing. "Odhodna dostavljalka naslovov" is awkward and not standard Slovenian. A better wording for "Outbound Address Fetch" would be "Odhodno pridobivanje naslovov". Also, "krakoživa" should be "kratkotrajna" to correctly translate "short-lived". Moreover, a comma should be used as in the source text to separate the clauses.

Correct translation:  
Odhodno pridobivanje naslovov: kratkotrajno, za zahtevanje naslovov
```

```
        <source>no high bandwidth relay selected</source>
        <translation>ni posredovanja na visoki pasovni širini</translation>
    
YES  
The Slovene translation is incomplete and omits the negation and verb. The source means "no high bandwidth relay selected," which implies that no relay with high bandwidth was selected. The correct translation should clearly convey "no" and "selected."  

Correct translation:  
"ni izbran posrednik z visoko pasovno širino"
```

```
        <source>Base58 (Legacy)</source>
        <translation>Base58 (podedovano)</translation>
    
YES
The English term "Legacy" in the Bitcoin context refers to the older or original format, and should be translated into Slovene accordingly. "podedovano" is a misspelling and incorrect Slovene word. The correct Slovene word is "dedni" or "stari" to convey "legacy." 

Correct translation:
Base58 (dedni)
```

```
        <source>Request payment to …</source>
        <translation>Zahtevaj plačilo prejmeniku ...</translation>
    
YES  
The Slovene translation incorrectly translates "to …" as "prejmeniku," which means "to the rename" and is unrelated to the context. The correct word for "to" in this context (request payment to an address) should be "na" or omitted depending on the phrase structure. Also, ellipsis should use the single Unicode character "…" instead of three dots "..." for consistency.

Correct translation:  
Zahtevaj plačilo na …
```

```
        <source>Quantity:</source>
        <translation>Št. vhodov:</translation>
    
YES  
The English source "Quantity:" is a general term, typically translated as "Količina:" in Slovenian. The provided translation "Št. vhodov:" means "Number of inputs:", which is more specific and context-dependent. Unless the context explicitly requires specifying "Number of inputs," this translation is inaccurate.

Correct translation:  
Količina:
```

```
        <source>PSBT saved</source>
        <extracomment>Popup message when a PSBT has been saved to a file</extracomment>
        <translation>DPBT shranjena</translation>
    
YES  
The acronym "PSBT" is incorrectly translated as "DPBT" in Slovene. The correct translation should keep the acronym as "PSBT" because it stands for "Partially Signed Bitcoin Transaction" and should not be altered.  

Correct translation:  
PSBT shranjena
```

```
        <source>PSBT saved to disk</source>
        <translation>DPBT shranjena na disk</translation>
    
YES
The acronym "PSBT" is mistranslated as "DPBT" in Slovene; it should remain "PSBT" as it is a technical term. Also, the verb should agree with the feminine noun "PSBT" (if treated as feminine), making it "shranjena". The rest of the translation is correct.

Correct translation:
PSBT shranjena na disk
```

```
        <source>Sign the message to prove you own this Bitcoin address</source>
        <translation>Podpišite sporočilo, da dokažete lastništvo zgornjega naslova.</translation>
    
YES  
The translation is not fully accurate. The original English specifies "this Bitcoin address," implying the specific address being referenced, whereas the Slovene translation uses "zgornjega naslova" ("the above address"), which may not be appropriate or accurate depending on the context. Moreover, it omits the mention of "Bitcoin," which is important for clarity in this context.

A better translation would explicitly mention "Bitcoin naslov" and keep the wording closer to the original meaning:

Correct translation:  
Podpišite sporočilo, da dokažete, da ste lastnik tega Bitcoin naslova.
```

```
        <source>own address</source>
        <translation>lasten naslov</translation>
    
YES  
The Slovenian translation "lasten naslov" is incorrect in this Bitcoin context. The English "own address" refers to "your own address" (e.g., wallet or network address). The correct Slovenian phrase is "lasten naslov" would mean "private address" or "own address" literally, but in the Bitcoin context the accepted translation is "lasten naslov" or better "lasten naslov" is actually correct. However, to confirm, "own address" is correctly translated as "lasten naslov" in Slovenian. So is it unproblematic?

Actually, "lasten naslov" is the correct Slovenian translation of "own address" and is commonly used in Bitcoin software in Slovenian localization.

No format specifiers are involved, and no extra whitespace issues.

Therefore, the translation is correct and unproblematic.

Corrected output:

NO
```

```
        <source>Sent to</source>
        <translation>Poslano na </translation>
    
YES
The translation includes a trailing space after "na", which is unnecessary and inconsistent with the source text formatting. The source text "Sent to" does not have a trailing space.

Correct translation:
Poslano na
```

```
        <source>Sent to</source>
        <translation>Poslano na </translation>
    
YES
The translation includes a trailing space after "na", which is unnecessary and inconsistent with the source text formatting. The source text "Sent to" does not have a trailing space.

Correct translation:
Poslano na
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>Velikost DPBT ne sme presegati 100 MiB.</translation>
    
YES  
The abbreviation "PSBT" (Partially Signed Bitcoin Transaction) is mistranslated as "DPBT" in Slovenian, which is incorrect. The correct abbreviation "PSBT" should be retained as is. Additionally, the original English states "must be smaller than 100 MiB," while the translation says "ne sme presegati 100 MiB" meaning "must not exceed 100 MiB," which is acceptable, but the abbreviation is wrong.

Correct translation:  
PSBT datoteka mora biti manjša od 100 MiB.
```

```
        <source>Can't draft transaction.</source>
        <translation>Ne morem shraniti osnutka transakcije</translation>
    
YES
The translation "Ne morem shraniti osnutka transakcije" means "I cannot save the draft of the transaction," which deviates from the source "Can't draft transaction." The source implies inability to create or draft a transaction, not specifically failing to save it.

A more accurate Slovenian translation would be:
"Ne morem sestaviti osnutka transakcije."
```

```
        <source>File %s already exists. If you are sure this is what you want, move it out of the way first.</source>
        <translation>Datoteka %s že obstaja. Če stre prepričani, da to želite, obstoječo datoteko najprej odstranite oz. premaknite.</translation>
    
YES
There is a small typo in the Slovene translation: "stre" should be "ste". Also, the phrase "obstoječo datoteko najprej odstranite oz. premaknite" is acceptable but slightly less direct than "najprej jo odstranite ali premaknite" (using "jo" to directly refer to the file).

Correct translation:
Datoteka %s že obstaja. Če ste prepričani, da to želite, jo najprej odstranite ali premaknite iz poti.
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>Nastavljen je več kot en onion-naslov. Za samodejno ustvarjeno storitev na Toru uporabljam %s.</translation>
    
YES  
The translation is somewhat inaccurate and awkward. The source mentions "More than one onion bind address is provided" and "Using %s for the automatically created Tor onion service." The current translation translates "More than one onion bind address is provided" as "Nastavljen je več kot en onion-naslov," which is not entirely correct because "nastavljen je" means "is set" rather than "is provided." It also incorrectly translates "using %s" as "Uporabljam %s," which is first-person singular ("I am using %s") rather than an impersonal or passive construction appropriate here.

A better translation would be:  
"Podanih je več kot en onion bind naslov. Za samodejno ustvarjeno storitev Tor onion uporabljam %s."  

Or slightly more natural:  
"Podanih je več kot en naslov onion bind. Za samodejno ustvarjeno storitev Tor onion uporabljam %s."

Note also: "storitev na Toru" should be "storitev Tor onion" or "storitev Torovega onion." Since the source says "Tor onion service," the phrase "storitev Tor onion" is acceptable.

Corrected translation:  
<translation>Podanih je več kot en onion bind naslov. Za samodejno ustvarjeno Tor onion storitev uporabljam %s.</translation>
```

```
        <source>Unknown wallet file format "%s" provided. Please provide one of "bdb" or "sqlite".</source>
        <translation>Nastavljena je neznana oblika datoteke denarnice "%s". Prosimo, uporabite "bdb" ali "sqlite".</translation>
    
YES  
The translation contains an incorrect phrase "Nastavljena je neznana oblika datoteke denarnice", which translates to "An unknown wallet file format has been set." The source says "Unknown wallet file format "%s" provided," implying that the format provided is unknown, not that it was set. The verb choice and sentence structure are misleading in this context.

Correct translation:  
Neznan format datoteke denarnice "%s" je bil posredovan. Prosimo, navedite enega od "bdb" ali "sqlite".
```

```
        <source>Error loading %s: Wallet corrupted</source>
        <translation>Napaka pri nalaganju %s: Denarnica ovkarjena</translation>
    
YES  
The word "ovkarjena" is incorrect in Slovenian and does not mean "corrupted." The correct word for "corrupted" in this context is "poškodovana" or better "pokvarjena." A good translation would be:

Napaka pri nalaganju %s: Denarnica je poškodovana
```

```
        <source>Error: No %s addresses available.</source>
        <translation>Napaka: na voljo ni nobenega naslova '%s'</translation>
    
YES
The translation incorrectly places the format specifier '%s' inside single quotes, which is not reflective of the source text. Also, the phrase "Error: No %s addresses available." implies a lack of any addresses of a certain type, so the translation should reflect the plural "addresses" properly and include "%s" without quotes.

Correct translation:
Napaka: na voljo ni nobenih naslovov %s.
```

```
        <source>Failed to rescan the wallet during initialization</source>
        <translation>Med inicializacijo denarnice ni bilo mogoče preveriti zgodovine (rescan failed).</translation>
    
YES  
The translation is partially in Slovenian, but it incorrectly uses the word "Med" (which means "during" in Slovenian) with the incorrect capitalization and mixes English within parentheses "rescan failed" which should be translated or omitted. Also, "denarnice" is Slovenian for "wallet," but "preveriti zgodovine" literally means "check history," which is acceptable but "rescan" is more precise as "ponovno pregledati" or "ponovno skenirati." The phrase "ni bilo mogoče preveriti zgodovine" translates as "it was not possible to check the history," which is close but less direct than "failed to rescan."

A better Slovenian translation that respects the original meaning and style is:

"Med inicializacijo denarnice ni bilo mogoče znova pregledati."

or, to be more explicit about "rescan":

"Med inicializacijo denarnice ni bilo mogoče opraviti ponovnega skeniranja."

Correct translation:  
Med inicializacijo denarnice ni bilo mogoče opraviti ponovnega skeniranja.
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s'</source>
        <translation>Neveljaven znesek za %s=&lt;amount&gt;:'%s'</translation>
    
YES  
There is a missing space after the colon in the translation. In the source, there is a space after the colon before the quoted amount: ": '%s'". The translation omits the space after the colon, which can reduce readability.

Correct translation:  
Neveljaven znesek za %s=&lt;amount&gt;: '%s'
```

```
        <source>Loading P2P addresses…</source>
        <translation>Nalagam P2P naslove ...</translation>
    
YES  
The translation contains spacing issues and an incorrect word choice. "Nalagam" seems incorrect for "Loading," and "naslove" typically means "headings" or "titles," not "addresses." The correct Slovenian translation for "Loading P2P addresses…" would be "Nalaganje P2P naslovov…" without extra spaces before the ellipsis.

Correct translation:  
Nalaganje P2P naslovov…
```

```
        <source>Pruning blockstore…</source>
        <translation>Obrezujem ...</translation>
    
YES
The translation "Obrezujem ..." is incomplete and omits the object "blockstore," which is necessary for clarity. Also, there is an unnecessary space before the ellipsis. A better translation would be:

"Obrezujem blokovno skladišče…"
```
</details>
