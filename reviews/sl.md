# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsl%5D%20low%20quality)


```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Vnesite novo geslo za denarnico. &lt;br/&gt;Prosimo, uporabite geslo z vsaj &lt;b&gt;10 ali več naključnimi simboli&lt;/b&gt; ali vsaj osmimi besedami.&lt;b&gt;</translation>
    
YES, The translation incorrectly translates "characters" to "simboli" (symbols) instead of "znaki" (characters). Additionally, there is a stray closing &lt;/b&gt; tag.
Vnesite novo geslo za denarnico.&lt;br/&gt;Prosimo, uporabite geslo z vsaj &lt;b&gt;10 ali več naključnimi znaki&lt;/b&gt; ali vsaj osmimi besedami.
```

```
        <source>Runaway exception</source>
        <translation>Pobegla napaka</translation>
    
YES, The translation is problematic because "Pobegla napaka" is not the correct Slovenian translation for "Runaway exception". A more appropriate translation would be "Izredna napaka" or "Nevidena napaka".
Correct translation: Izredna napaka
```

```
        <source>Do you want to reset settings to default values, or to abort without making changes?</source>
        <extracomment>Explanatory text shown on startup when the settings file cannot be read. Prompts user to make a choice between resetting or aborting.</extracomment>
        <translation>Želite ponastaviti nastavitve na privzete vrednosti ali prekiniti urejanje brez sprememb?</translation>
    
YES - The translation uses "urejanje" which means "editing" but the source text is "making changes", so it should be "sprememb" instead of "urejanje brez sprememb". The correct translation would be: Želite ponastaviti nastavitve na privzete vrednosti ali prekiniti brez sprememb?
```

```
        <source>%1 and %2</source>
        <translation>%1 in %2</translation>
    
YES: The translation uses the incorrect preposition "in" instead of "and".
%1 and %2
```

```
        <source>Verify message…</source>
        <translation>Preveri podpis...</translation>
    
YES, The Slovenian word "podpis" means "signature". The English source text "Verify message…" translates to "Preveri sporočilo…" in Slovenian.
Preveri sporočilo…
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Preverite, če je bilo prejeto sporočilo podpisano z določenim bitcoin-naslovom.</translation>
    
YES - The translation is inaccurate and incomplete. The source text uses the plural "addresses", while the translation uses the singular "bitcoin-naslovom". Additionally, the translation omits the phrase "to ensure they were signed with specified".

Correct translation: Preverite sporočila, da zagotovite, da so bila podpisana z določenimi bitcoin naslovi.
```

```
        <source>Load PSBT from file…</source>
        <translation>Naloži DPBT iz datoteke...</translation>
    
YES
The translation uses "DPBT" instead of "PSBT".
Naloži PSBT iz datoteke…
```

```
        <source>Synchronizing with network…</source>
        <translation>Dohitevam omrežje ...</translation>
    
YES, The translation uses an invented word "Dohitevam" which does not exist in the Slovenian language. The correct translation should be "Sinhroniziram z omrežjem…".
Dohitevam omrežje ...
Sinhroniziram z omrežjem…
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>Naloži DPBT z odložišča...</translation>
    
YES: The translation incorrectly uses "DPBT" instead of "PSBT".
Naloži PSBT z odložišča...
```

```
        <source>Cannot create new wallet, the software was compiled without sqlite support (required for descriptor wallets)</source>
        <translation>Ne morem ustvariti nove datoteke. Programska oprema je bila prevedena brez podpore za sqlite, ki je potrebna za denarnice z deskriptorji.</translation>
    
YES: The word "wallet" is translated to "datoteke" (files) instead of the correct term "denarnice" (wallets).
Ne morem ustvariti nove denarnice, programska oprema je bila prevedena brez podpore za sqlite, ki je potrebna za denarnice z deskriptorji.
```

```
        <source>Quantity:</source>
        <translation>Št. vhodov:</translation>
    
YES, The translation is incorrect and uses the wrong word. "Št. vhodov" translates to "Number of inputs" in English, whereas the source text "Quantity:" means "Količina:" in Slovenian.
Količina:
```

```
        <source>Change:</source>
        <translation>Vračilo:</translation>
    
YES, The translation of "Change:" to "Vračilo:" is incorrect in the context of Bitcoin. "Vračilo" translates to "refund" or "return," which is not the correct term for the change amount in a Bitcoin transaction. The correct term for change in Bitcoin is "Vzdrževanje" or "Drobiž," but "Vzdrževanje" is more commonly used.

Correct translation: Vzdrževanje:
```

```
        <source>Received with label</source>
        <translation>Oznaka priliva</translation>
    
YES - The translation is inaccurate and doesn't convey the original meaning. "Received with label" in the context of Bitcoin would translate to something like "Prejeto z oznako" or "Prejeto z nalepko". The provided translation "Oznaka priliva" translates to "Label of inflow," which is not the correct meaning.

Correct translation: Prejeto z oznako
```

```
        <source>Received with address</source>
        <translation>Naslov priliva</translation>
    
YES, The translation is inaccurate. The source text "Received with address" implies receiving something (likely Bitcoin) associated with a specific address. The translation "Naslov priliva" means "Title of inflow" or "Address of inflow", which doesn't convey the intended meaning of receiving *with* an address. A more accurate translation would reflect receiving something at or using a given address.

The correct translation should be: "Prejeto na naslov".
```

```
        <source>External signer</source>
        <translation>Zunanji podpisni</translation>
    
YES, The translation is grammatically incorrect. The word "podpisni" is an adjective and should be a noun. The correct translation for "signer" is "podpisnik".
Zunanji podpisnik
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Prevedeno brez podpore za zunanje podpisovanje</translation>
    
YES - The translation is missing a crucial part of the original text. It should also include the parenthetical explanation.
Prevedeno brez podpore za zunanje podpisovanje (potrebno za zunanje podpisovanje)
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>Oznaka tega naslova. Urejate jo lahko le pri naslovih za pošiljanje.</translation>
    
YES - The translation incorrectly translates "address associated with this address list entry" to "Oznaka tega naslova" which means "Label of this address". The correct translation for "address" should be "naslov".

NO
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>V  tem direktoriju bo shranjenih vsaj %1 GB podatkov, količina podatkov pa bo s časom naraščala.</translation>
    
YES: The word "V" at the beginning of the translation is an extra space.
V tem direktoriju bo shranjenih vsaj %1 GB podatkov, količina podatkov pa bo s časom naraščala.
```

```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>%1 trenutno dohiteva omrežje. Od soležnikov bodo preneseni in preverjeni zaglavja in bloki do vrha verige.</translation>
    
YES - The translation incorrectly states "%1 trenutno dohiteva omrežje." which translates to "%1 is currently downloading the network." The English source states "%1 is currently syncing." which implies the process of synchronizing data, not downloading the entire network.

Correct translation: %1 se trenutno sinhronizira. Od soležnikov bodo preneseni in preverjeni zaglavja in bloki do vrha verige.
```

```
        <source>Maximum database cache size. Make sure you have enough RAM. A larger cache can contribute to faster sync, after which the benefit is less pronounced for most use cases. Lowering the cache size will reduce memory usage. Unused mempool memory is shared for this cache.</source>
        <extracomment>Tooltip text for Options window setting that sets the size of the database cache. Explains the corresponding effects of increasing/decreasing this value.</extracomment>
        <translation>Največja dovoljena velikost predpomnilnika podatkovne baze. Imeti morate dovolj velik delovni pomnilnik (RAM). Povečanje predpomnilnika lahko prispeva k hitrejši začetni sinhronizaciji, kasneje pa večinoma manj pomaga. Znižanje velikosti predpomnilnika bo zmanjšalo porabo pomnilnika. Za ta predpomnilnik se uporablja tudi neporabljeni predpomnilnik za transakcije.</translation>
    
YES: The last sentence contains a mistranslation. "Unused mempool memory is shared for this cache" should be translated as "Neporabljeni pomnilnik iz mempool-a se deli za ta predpomnilnik." instead of "Za ta predpomnilnik se uporablja tudi neporabljeni predpomnilnik za transakcije."

NO.
```

```
        <source>Prune block storage to</source>
        <translation>Obreži velikost podatkovne baze na</translation>
    
YES - The translation is inaccurate and misleading. "Prune block storage to" refers to reducing the size of the blockchain data, not the database size in general.

Correct translation: "Obreži shranjevanje blokov na"
```

```
        <source>This allows you or a third party tool to communicate with the node through command-line and JSON-RPC commands.</source>
        <extracomment>Tooltip text for Options window setting that enables the RPC server.</extracomment>
        <translation>RPC-strežnik omogoča vam in raznim orodjem komunikacijo z vozliščem prek ukazne vrstice in ukazov JSON-RPC.</translation>
    
YES: The translation is a significant departure from the source text. It rephrases the sentence and changes the subject from the ability to communicate to the RPC server itself enabling communication. Additionally, it uses "raznim orodjem" (various tools) instead of "a third party tool".
Correct translation: To vam omogoča ali orodje tretje osebe, da komunicirate z vozliščem prek ukazne vrstice in ukazov JSON-RPC.
```

```
        <source>Enable PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Omogoči nastavitve DPBT</translation>
    
YES - The translation incorrectly translates "PSBT" to "DPBT". The correct translation for PSBT is also PSBT.
NO - Omogoči nastavitve PSBT
```

```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Ali naj se prikaže upravljanje z DPBT</translation>
    
YES. The translation uses the abbreviation "DPBT" which is not the correct abbreviation for "PSBT" in Slovenian. PSBT stands for Partially Signed Bitcoin Transaction. The correct Slovenian term for this would be "delno podpisana bitcoin transakcija" or a similar variation, and the abbreviation would typically be DPDT.

NO. Ali naj se prikaže upravljanje z DPBT.
```

```
        <source>Third-party transaction URLs</source>
        <translation>Zunanji URL-ji</translation>
    
YES: The translation is inaccurate and lacks context. It fails to convey the meaning of "third-party transaction URLs" in the context of Bitcoin.

Correct translation: Zunanji URL-ji transakcij
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Prevedeno brez podpore za zunanje podpisovanje</translation>
    
YES - The translation is missing a crucial part of the original text. It should also include the parenthetical explanation.
Prevedeno brez podpore za zunanje podpisovanje (potrebno za zunanje podpisovanje)
```

```
        <source>none</source>
        <translation>jih ni</translation>
    
YES - The translation is incorrect and nonsensical in the context of Bitcoin. The correct translation for "none" in Slovene, especially in a technical context like Bitcoin, would be "nič" or "brez".
 jih ni
```

```
        <source>Client will be shut down. Do you want to proceed?</source>
        <extracomment>Text asking the user to confirm if they would like to proceed with a client shutdown.</extracomment>
        <translation>Program bo zaustavljen. Želite nadaljevati z izhodom?</translation>
    
YES. The translation includes an unnecessary and potentially confusing phrase "z izhodom" (with exiting) which is not present in the source text. The format specifiers are also missing.

NO. Program bo zaustavljen. Želite nadaljevati?
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Skupni znesek sredstev, s katerimi še ne razpolagate prosto, ker so del še nepotrjenih transakcij.</translation>
    
YES - The translation is inaccurate and misleading. It states that the funds are not freely available because they are part of unconfirmed transactions, but the source text refers to unconfirmed transactions that *do not yet count toward the spendable balance*. The translation implies the funds are in unconfirmed transactions and therefore not spendable, which is not quite the same.

A more accurate translation would be:
Skupni znesek transakcij, ki še niso potrjene in se še ne vštevajo v razpoložljivo stanje.
```

```
        <source>Broadcast Tx</source>
        <translation>Oddaj transakcijo v omrežje</translation>
    
UNK_LANG
```

```
        <source>PSBT copied to clipboard.</source>
        <translation>DPBT kopirana v odložišče.</translation>
    
YES - The translation uses "DPBT" instead of "PSBT".
The English text is "PSBT copied to clipboard.".
The translation should be "PSBT kopirana v odložišče.".
```

```
        <source>own address</source>
        <translation>lasten naslov</translation>
    
YES, The translation "lasten naslov" is incorrect. The correct translation for "own address" in the context of Bitcoin in Slovene is "lastni naslov". The word "lasten" is not a standard Slovene word, and "lastni" means "own".

NO, lastni naslov
```

```
        <source>Pays transaction fee: </source>
        <translation>Vsebuje transakcijsko provizijo:</translation>
    
YES - The Slovenian translation is inaccurate. "Pays transaction fee" means "Plača transakcijsko provizijo" or "Nese transakcijsko provizijo". The provided translation "Vsebuje transakcijsko provizijo" translates to "Contains transaction fee".
Vsebuje transakcijsko provizijo:
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Ni mogoče zagnati rokovalca plačilnih povezav tipa bitcoin:.</translation>
    
YES - The translation is problematic due to an incorrect interpretation of "click-to-pay handler". In the context of Bitcoin, this likely refers to a feature that allows clicking on a Bitcoin payment link to initiate a transaction. The provided Slovenian translation "rokovalca plačilnih povezav tipa bitcoin:" can be interpreted as a "Bitcoin payment link handler," but the addition of "tipa" (type) and the colon at the end makes it awkward and grammatically incorrect in this context.

A more accurate translation would be: "Ne morem zagnati upravljalnika klikni-za-plačilo za bitcoin."
```

```
        <source>Received</source>
        <extracomment>Title of Peers Table column which indicates the total amount of network information we have received from the peer.</extracomment>
        <translation>Prejeto</translation>
    
YES: The translation of "Received" to "Prejeto" is incorrect. "Prejeto" means "project" or "proposal" in Slovene. The correct translation for "Received" in this context would be "Prejeto" (past participle of "prejeti" - to receive).
NO: Prejeto
```

```
        <source>Received</source>
        <translation>Prejeto</translation>
    
YES, the translation is incorrect. The Slovenian word "Prejeto" means "Received" in English, which is exactly what the source text says. However, the provided translation seems to be a typo of the correct word. The correct translation for "Received" in Slovenian is "Prejeto".

NO
```

```
        <source>Open the %1 debug log file from the current data directory. This can take a few seconds for large log files.</source>
        <translation>Odpre %1 razhroščevalni dnevnik debug.log, ki se nahaja v trenutni podatkovni mapi. Če je datoteka velika, lahko postopek traja nekaj sekund.</translation>
    
YES - The translation "Odpre %1 razhroščevalni dnevnik debug.log, ki se nahaja v trenutni podatkovni mapi. Če je datoteka velika, lahko postopek traja nekaj sekund." is problematic because the phrase "razhroščevalni dnevnik debug.log" is redundant and awkward. The word "razhroščevalni" translates to "debugging" and "debug.log" already indicates a debug log. A more natural translation would be to simply refer to the debug log file.

Correct translation: Odpre %1 datoteko dnevnika odpravljanja napak iz trenutne podatkovne mape. Če je datoteka velika, lahko postopek traja nekaj sekund.
```

```
        <source>Last Send</source>
        <translation>Nazadje oddano</translation>
    
YES, The translation "Nazadje oddano" is incorrect. The Slovenian word for "Last" is "Zadnja" or "Nazadnje", and "Send" translates to "Pošlji". Therefore, "Last Send" should be translated to "Zadnja pošiljka" or "Nazadnje poslano".
The correct translation is:
Nazadnje poslano
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Odhodna dostavljalka naslovov: krakoživa, zaproša za naslove</translation>
    
YES - The translation uses "dostavljalka" which means "delivery person" or "courier", which is not appropriate for "fetch" in this context. The correct translation for "fetch" in the sense of retrieving data is "pridobivanje" or "priklic".

NO
Odhodno pridobivanje naslovov: kratkotrajno, za pridobivanje naslovov
```

```
        <source>no high bandwidth relay selected</source>
        <translation>ni posredovanja na visoki pasovni širini</translation>
    
YES: The translation is missing the word "selected" from the original English sentence.
The correct translation is: "ni izbrana posredovanja na visoki pasovni širini"
```

```
        <source>Show the selected request (does the same as double clicking an entry)</source>
        <translation>Prikaz izbranega zahtevka. (Isto funkcijo opravi dvojni klik na zapis.)</translation>
    
YES - The translation is incorrect and uses Croatian instead of Slovenian. The correct Slovenian translation would be: "Prikaži izbrano zahtevo (isto kot pri dvojnem kliku na vnos)".
```

```
        <source>Base58 (Legacy)</source>
        <translation>Base58 (podedovano)</translation>
    
YES, The translation is incorrect. The Slovenian word "podedovano" means "inherited" or "legacy" but in a way that implies inheritance from family, not in the technical sense of a legacy system. The correct term for a legacy Bitcoin address format is "staro" which means "old".

Base58 (Legacy) -> Base58 (staro)
```

```
        <source>Request payment to …</source>
        <translation>Zahtevaj plačilo prejmeniku ...</translation>
    
YES. The translation is inaccurate and uses an incorrect word for "address" in the context of Bitcoin. The word "prejmenik" does not have a relevant meaning in this context.

Correct translation: Zahtevaj plačilo na naslov ...
```

```
        <source>Quantity:</source>
        <translation>Št. vhodov:</translation>
    
YES, The translation is incorrect and uses the wrong word. "Št. vhodov" translates to "Number of inputs" in English, whereas the source text "Quantity:" means "Količina:" in Slovenian.
Količina:
```

```
        <source>Change:</source>
        <translation>Vračilo:</translation>
    
YES, The translation of "Change:" to "Vračilo:" is incorrect in the context of Bitcoin. "Vračilo" translates to "refund" or "return," which is not the correct term for the change amount in a Bitcoin transaction. The correct term for change in Bitcoin is "Vzdrževanje" or "Drobiž," but "Vzdrževanje" is more commonly used.

Correct translation: Vzdrževanje:
```

```
        <source>Creates a Partially Signed Bitcoin Transaction (PSBT) for use with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <translation>Ustvari delno podpisano bitcoin-transakcijo (DPBT, angl. PSBT), ki jo lahko kopirate in potem podpišete n.pr. z nepovezano (offline) %1 denarnico ali pa s hardversko denarnico, ki podpira DPBT.</translation>
    
YES: The translation introduces an acronym "DPBT" and claims it's the English abbreviation for PSBT, which is incorrect. The correct translation should reflect that PSBT is the English term. Additionally, the phrasing "ki jo lahko kopirate in potem podpišete" is a bit verbose and could be more direct.

Correct translation: Ustvari delno podpisano bitcoin-transakcijo (PSBT) za uporabo n.pr. z nepovezano (offline) %1 denarnico ali s hardversko denarnico, ki podpira PSBT.
```

```
        <source>%1 to %2</source>
        <translation>%1 v %2</translation>
    
YES: The translation is inaccurate. The Slovenian word "v" means "in" or "at", which does not convey the intended meaning of "to" in the context of a range or connection between two points. The correct translation for "to" in this context is "do".

%1 do %2
```

```
        <source>PSBT saved</source>
        <extracomment>Popup message when a PSBT has been saved to a file</extracomment>
        <translation>DPBT shranjena</translation>
    
YES: The translation is incorrect. "PSBT" is a specific technical term in the Bitcoin context and should not be translated as "DPBT".
NO
```

```
        <source>The PSBT has been copied to the clipboard. You can also save it.</source>
        <translation>DPBT je bila skopirana na odložišče. Lahko jo tudi shranite.</translation>
    
YES: The abbreviation "PSBT" is not translated into Slovene. The correct translation should be: "PSBT je bil kopiran na odložišče. Lahko ga tudi shranite."
```

```
        <source>PSBT saved to disk</source>
        <translation>DPBT shranjena na disk</translation>
    
YES, The translation is incorrect. The acronym "PSBT" refers to Partially Signed Bitcoin Transactions. The translation used "DPBT" which is incorrect.
PSBT shranjen na disk
```

```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Naslov je že bil uporabljen. Vsak naslov naj bi se uporabil samo enkrat.</translation>
    
YES - The translation is grammatically incorrect and does not accurately convey the meaning of the source text. The source text uses the word "duplicate" to indicate that an address has been encountered more than once, implying an error or a potential problem. The translation uses "Naslov je že bil uporabljen" which translates to "The address has already been used." While this is somewhat similar, it lacks the implication of duplication and the corrective tone of the original. Furthermore, the phrase "addresses should only be used once each" is translated as "Vsak naslov naj bi se uporabil samo enkrat," which is grammatically awkward.

A more accurate translation would be: "Ponavljajoč se naslov: naslove je treba uporabiti samo enkrat." This translates to "Duplicate address: addresses should be used only once."
```

```
        <source>Subtract fee from amount</source>
        <translation>Odštej provizijo od zneska</translation>
    
YES: The translation is incorrect. The language specified by 'sl' is not Slovenian. It appears to be Czech.
UNK_LANG
```

```
        <source>Sign the message to prove you own this Bitcoin address</source>
        <translation>Podpišite sporočilo, da dokažete lastništvo zgornjega naslova.</translation>
    
YES - The translation is missing a crucial part of the original message. It says "the above address" instead of "this Bitcoin address."

Correct translation: Podpišite sporočilo, da dokažete lastništvo tega Bitcoin naslova.
```

```
        <source>conflicted with a transaction with %1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that conflicts with a confirmed transaction.</extracomment>
        <translation>v sporu s transakcijo z %1 potrditvami</translation>
    
YES - The Slovenian translation uses "v sporu s" which means "in dispute with" or "in conflict with", but the English phrase "conflicted with" in this context means that the transaction is invalid because it conflicts with another valid transaction, not that it is in a dispute. The correct translation should convey this invalidity.

Correct translation: "neveljavna zaradi konflikta s transakcijo s %1 potrditvami"
```

```
        <source>own address</source>
        <translation>lasten naslov</translation>
    
YES, The translation "lasten naslov" is incorrect. The correct translation for "own address" in the context of Bitcoin in Slovene is "lastni naslov". The word "lasten" is not a standard Slovene word, and "lastni" means "own".

NO, lastni naslov
```

```
        <source>Received with</source>
        <translation>Prejeto z</translation>
    
YES: The translation is inaccurate and does not convey the original meaning of "Received with". In the context of Bitcoin, "Received with" implies that an amount was received from a certain source. The Slovenian translation "Prejeto z" literally means "Rejected with", which is the opposite of the intended meaning.

Correct translation: Prejeto z
```

```
        <source>Received from</source>
        <translation>Prejeto od</translation>
    
YES, The translation of "Received from" to "Prejeto od" is incorrect. "Prejeto od" translates to "Rejected from" in English. The correct translation for "Received from" in Slovenian, in the context of Bitcoin transactions, is "Prejeto od".

NO
```

```
        <source>Sent to</source>
        <translation>Poslano na </translation>
    
YES, There is an extra space at the end of the translation.
Poslano na
```

```
        <source>Received with</source>
        <translation>Prejeto z</translation>
    
YES: The translation is inaccurate and does not convey the original meaning of "Received with". In the context of Bitcoin, "Received with" implies that an amount was received from a certain source. The Slovenian translation "Prejeto z" literally means "Rejected with", which is the opposite of the intended meaning.

Correct translation: Prejeto z
```

```
        <source>Sent to</source>
        <translation>Poslano na </translation>
    
YES, There is an extra space at the end of the translation.
Poslano na
```

```
        <source>Unable to decode PSBT from clipboard (invalid base64)</source>
        <translation>Ne morem dekodirati DPBT z odložišča (neveljaven format base64)</translation>
    
YES - The translation contains an error as "PSBT" is incorrectly translated as "DPBT". The correct translation for "PSBT" is "PSBT" or "deljeno nadzorovano denarnico" if context allows for a more descriptive translation, but keeping the acronym is generally preferred in technical contexts.

NO - The translation is unproblematic.
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>Velikost DPBT ne sme presegati 100 MiB.</translation>
    
YES. The translation incorrectly uses "DPBT" instead of "PSBT".
The correct translation should be: "Velikost PSBT ne sme presegati 100 MiB."
```

```
        <source>Warning: This may pay the additional fee by reducing change outputs or adding inputs, when necessary. It may add a new change output if one does not already exist. These changes may potentially leak privacy.</source>
        <translation>Opozorilo: za dodatno provizijo je včasih potrebno odstraniti izhode za vračilo ali dodati vhode. Lahko se tudi doda izhod za vračilo, če ga še ni. Te spremembe lahko okrnijo zasebnost.</translation>
    
YES: The phrase "za dodatno provizijo je včasih potrebno odstraniti izhode za vračilo ali dodati vhode" is a bit awkward and could be phrased more naturally in Slovenian. The word "zmanjšanje" (reduction) for "reducing" is missing, and the translation implies that removing outputs or adding inputs is always necessary, rather than done when necessary.

A more accurate translation would be: "Opozorilo: To lahko plača dodatno provizijo z zmanjšanjem izhodov za vračilo ali dodajanjem vhodov, ko je to potrebno. Lahko doda nov izhod za vračilo, če ga že ni. Te spremembe lahko potencialno ogrozijo zasebnost."
```

```
        <source>Can't draft transaction.</source>
        <translation>Ne morem shraniti osnutka transakcije</translation>
    
YES - The translation uses a literal interpretation of "draft transaction" which is not idiomatic in Slovenian. The word "shraniti" (save) is also not the most accurate translation for "draft" in this context. The more appropriate translation would be to indicate the inability to create or prepare the transaction.
Ne morem ustvariti osnutka transakcije.
```

```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>DPBT z višjo provizijo kopirana v odložišče.</translation>
    
YES, "DPBT" is not a correct or standard abbreviation in the context of Bitcoin. The correct abbreviation for Partially Signed Bitcoin Transaction is PSBT.

DPBT z višjo provizijo kopirana v odložišče.
```

```
        <source>File %s already exists. If you are sure this is what you want, move it out of the way first.</source>
        <translation>Datoteka %s že obstaja. Če stre prepričani, da to želite, obstoječo datoteko najprej odstranite oz. premaknite.</translation>
    
YES: The translation contains a spelling error: "stre" should be "ste".
Datoteka %s že obstaja. Če ste prepričani, da to želite, obstoječo datoteko najprej odstranite oz. premaknite.
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>Nastavljen je več kot en onion-naslov. Za samodejno ustvarjeno storitev na Toru uporabljam %s.</translation>
    
YES: The Slovenian translation incorrectly states "Nastavljen je več kot en onion-naslov" which translates to "More than one onion address is set". The original English states "More than one onion bind address is provided", which is more accurately translated as "Več kot en onion-naslov za vezavo je bil posredovan".

The corrected translation is:
Nastavljen je več kot en onion-naslov za vezavo. Za samodejno ustvarjeno storitev na Toru uporabljam %s.
```

```
        <source>No wallet file format provided. To use createfromdump, -format=&lt;format&gt; must be provided.</source>
        <translation>Potrebno je določiti obliko izvozne (dump) datoteke. Z ukazom createfromdump morate uporabiti možnost -format=&lt;format&gt;.</translation>
    
YES - The translation is missing the format specifier "<format>".
NO - Potrebno je določiti obliko izvozne (dump) datoteke. Z ukazom createfromdump morate uporabiti možnost -format=<%format%>.
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>To je najvišja transakcijska provizija, ki jo plačate (poleg običajne provizije) za prednostno izogibanje delni porabi pred rednim izbiranjem kovancev.</translation>
    
UNK_LANG
```

```
        <source>Unknown wallet file format "%s" provided. Please provide one of "bdb" or "sqlite".</source>
        <translation>Nastavljena je neznana oblika datoteke denarnice "%s". Prosimo, uporabite "bdb" ali "sqlite".</translation>
    
YES
The translation is not accurate and misinterprets the English sentence. The English sentence states that an unknown wallet file format was *provided*, whereas the Slovenian translation implies that the wallet file format was *set* or *configured*.

Correct translation: Nepredvidena oblika datoteke denarnice "%s". Prosimo, predložite "bdb" ali "sqlite".
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Opozorilo: v denarnici {%s} z onemogočenimi zasebnimi ključi so prisotni zasebni ključi.</translation>
    
YES - The Slovenian translation is grammatically incorrect and the word order is unnatural. The correct translation should be: "Opozorilo: V denarnici {%s} so zaznani zasebni ključi z onemogočenimi zasebnimi ključi."
```

```
        <source>Error loading %s: External signer wallet being loaded without external signer support compiled</source>
        <translation>Napaka pri nalaganu %s: Denarnica za zunanje podpisovanje naložena, podpora za zunanje podpisovanje pa ni prevedena</translation>
    
YES: The translation of "compiled" is incorrect. "Prevedena" means "translated", but in this context, it should refer to the software being compiled.

Correct translation: Napaka pri nalaganju %s: Denarnica za zunanje podpisovanje naložena, podpora za zunanje podpisovanje pa ni prevedena
```

```
        <source>Error loading %s: Wallet corrupted</source>
        <translation>Napaka pri nalaganju %s: Denarnica ovkarjena</translation>
    
YES, The translation of "Wallet corrupted" to "Denarnica ovkarjena" is not standard in Slovenian. The more appropriate translation for "corrupted" in this context would be "poškodovana" or "poškodovana datoteka".

NO
```

```
        <source>Error: No %s addresses available.</source>
        <translation>Napaka: na voljo ni nobenega naslova '%s'</translation>
    
YES - The translation is missing the closing punctuation mark.
Error: No %s addresses available. -> Napaka: na voljo ni nobenega naslova '%s'.
```

```
        <source>Failed to rescan the wallet during initialization</source>
        <translation>Med inicializacijo denarnice ni bilo mogoče preveriti zgodovine (rescan failed).</translation>
    
YES, the translation uses a literal translation of "rescan" as "preveriti zgodovine", which is not a standard or clear term in the context of Bitcoin wallets in Slovenian. It also adds an unnecessary English parenthetical. The more appropriate translation would be to keep "rescan" or use a more common term for this operation if one exists in Slovenian Bitcoin jargon.

NO, Failed to rescan the wallet during initialization
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s'</source>
        <translation>Neveljaven znesek za %s=&lt;amount&gt;:'%s'</translation>
    
YES - The translation uses an apostrophe within the quoted string for the second %s, which is incorrect. The apostrophe should not be there, and there is an extra space before the closing apostrophe.
Correct translation: Neveljaven znesek za %s=&lt;amount&gt;: '%s'
```

```
        <source>Loading P2P addresses…</source>
        <translation>Nalagam P2P naslove ...</translation>
    
YES, the translation is problematic because the Slovenian word for "loading" is typically "nalaganje", not "nalagam". "Nalaganje" is the gerund form which is more appropriate here.

NO
```

```
        <source>Pruning blockstore…</source>
        <translation>Obrezujem ...</translation>
    
YES, the translation is problematic. The Slovenian word "Obrezujem" means "I am pruning" or "I am trimming." While technically a correct translation of "pruning," in the context of Bitcoin and blockstores, a more specific and appropriate term would be "Blokovni pomnilnik se obrezuje..." which translates to "The blockstore is pruning..." or "Obrezovanje blokovnega pomnilnika..." which translates to "Pruning of the blockstore...".

The provided translation is also missing the word "blockstore" entirely.

NO
```
</details>
