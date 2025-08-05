# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>fi</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bfi%5D%20low%20quality)


```
        <source>Passphrase Dialog</source>
        <translation>Tunnuslauseen tekstinsyöttökenttä</translation>
    
YES  
The translation "Tunnuslauseen tekstinsyöttökenttä" means "Passphrase's text input field," which is a literal description of a UI element rather than a dialog. The source phrase "Passphrase Dialog" refers to a dialog window, typically a pop-up or modal window for entering a passphrase.

A better translation would be:  
"Tunnuslauseen valintaikkuna"  
or simply  
"Tunnuslauseluettelo" (if it's a dialog for passphrase selection), but the most straightforward is "Tunnuslauseen valintaikkuna" ("Passphrase dialog window").  
If the context is a dialog requesting the passphrase, "Tunnuslauseen valintaikkuna" is appropriate.
```

```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>Lohko Rele</translation>
    
YES  
The term "Rele" is a direct borrowing from English "Relay" and is not commonly used in Finnish in this technical context. The correct Finnish term for "relay" in this networking/blockchain context is "lähetin" or "välitys". Additionally, "Lohko" and "Rele" should be combined into a single word or hyphenated as per Finnish compound word norms, but in this context "Lohkovälitys" or "Lohkonsiirto" would be better. The most accurate and commonly accepted translation is "Lohkovälitys".

Correct translation:  
Lohkovälitys
```

```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>Tunturi</translation>
    
YES  
The translation "Tunturi" means "mountain" or "hill" in Finnish, which is incorrect for "Feeler" in this technical Bitcoin context. "Feeler" here refers to a short-lived peer connection that tests if known addresses are alive, so it should be translated into Finnish in a way that conveys "test connection" or "test peer."

A more appropriate translation would be "Testiyhteys" (test connection) or "Testisolmu" (test peer). Given the context, "Testiyhteys" is a clear and concise translation.

Correct translation:  
<translation>Testiyhteys</translation>
```

```
        <source>Network activity disabled.</source>
        <extracomment>A substring of the tooltip.</extracomment>
        <translation>Verkkoyhteysmittari pois käytöstä</translation>
    
YES  
The translation "Verkkoyhteysmittari pois käytöstä" means "Network connection meter disabled," which is more specific than the source text "Network activity disabled." The source refers generally to network activity, not specifically to a connection meter. A more accurate and natural Finnish translation is:

"Verkkotoiminta pois käytöstä"
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Varmista, että viestisi on allekirjoitettu määritetyllä Bitcoin -osoitteella</translation>
    
YES  
The Finnish translation is mostly correct but contains a spacing issue and slightly differs in formality or phrasing. There is an unnecessary space before the hyphen in "Bitcoin -osoitteella"; it should be "Bitcoin-osoitteella" without spaces. Also, the source is plural ("messages" and "addresses"), but the translation is singular ("viestisi" = "your message" and "osoitteella" = "with [a single] address"). The translation should reflect the plural form.

Correct translation:  
Varmista, että viestit on allekirjoitettu määritetyillä Bitcoin-osoitteilla
```

```
        <source>Syncing Headers (%1%)…</source>
        <translation>Synkronoi järjestysnumeroita (%1%)...</translation>
    
YES  
The Finnish translation is inaccurate. "Headers" in the context of Bitcoin means block headers, and it should be translated accordingly (e.g., "lohkojen otsikot" or simply "otsikot"). Additionally, the original English uses an ellipsis character (…), but the translation uses three dots (...). Using the proper ellipsis character is preferable for consistency.

Correct translation:  
Synkronoidaan otsikoita (%1%)…
```

```
        <source>Catching up…</source>
        <translation>Jäljellä...</translation>
    
YES  
The English source "Catching up…" in the Bitcoin context refers to the software syncing or updating to the latest blockchain state. The provided Finnish translation "Jäljellä..." means "Remaining..." or "Left...", which does not correctly convey this meaning. A better translation capturing the syncing concept is "Päivitetään..." or "Synkronoidaan...".

Correct translation:  
Päivitetään...
```

```
        <source>Last received block was generated %1 ago.</source>
        <translation>Viimeisin vastaanotettu lohko tuotettu %1.</translation>
    
YES  
The translation misses the expression indicating "ago" (suom. "sitten") which is important for the meaning of elapsed time. The English sentence "Last received block was generated %1 ago." implies that %1 represents a time duration before now, so the Finnish should reflect that.

Correct translation:  
Viimeisin vastaanotettu lohko tuotettiin %1 sitten.
```

```
        <source>Lock unspent</source>
        <translation>Lkitse käyttämättömät</translation>
    
YES  
The Finnish translation contains a typo and is not correct. The English phrase "Lock unspent" refers to locking unspent outputs in Bitcoin context. The Finnish word "Lkitse" is not a valid word. The correct verb here is "Lukitse" (Lock), and "käyttämättömät" (unspent) is appropriate.  

Correct translation:  
Lukitse käyttämättömät
```

```
        <source>Unlock unspent</source>
        <translation>Avaa käyttämättömien lukitus</translation>
    
YES  
The Finnish translation is grammatically incorrect and awkward. "Avaa käyttämättömien lukitus" literally means "Open the lock of unused" but is not idiomatic or clear Finnish. The phrase "Unlock unspent" in the Bitcoin context likely means unlocking coins or outputs that are unspent.

A better Finnish translation would be:  
"Vapauta käyttämättömät"  
or  
"Poista käyttämättömien lukitus"  

Here "vapauta" means "release/unlock" and "käyttämättömät" (unspent ones) works as a noun, or "Poista ... lukitus" means "remove the lock of...". Either works depending on context. The first is simpler and more natural.
```

```
        <source>Copy after fee</source>
        <translation>Kopioi rahansiirtokulun jälkeen</translation>
    
YES
The translation "Kopioi rahansiirtokulun jälkeen" literally means "Copy after the transfer fee," which is a misinterpretation of the original phrase "Copy after fee." In the context of Bitcoin, "after fee" means the amount or value after deducting the fee, not an instruction to copy something. The term "copy" here is a verb and should correspond directly to the action in English.

A more accurate translation that preserves the meaning would be:
"Kopioi kulujen jälkeen" or "Kopioi maksun jälkeen"

If the phrase is a label or button meaning "Copy the amount after fee deduction," then:
"Kopioi määrä kulujen jälkeen" (Copy amount after fees)

Since the source only says "Copy after fee," the simplest accurate translation is:
"Kopioi kulun jälkeen"
```

```
        <source>change from %1 (%2)</source>
        <translation>Vaihda %1 (%2)</translation>
    
YES
The English source "change from %1 (%2)" refers to the change amount in a Bitcoin transaction, meaning the leftover funds returned from a transaction. The Finnish word "Vaihda" means "change" as a verb ("to change" or "exchange"), which is incorrect in this context. The correct translation should use "Vaihtoraha" (meaning "change" as money returned) or a phrase indicating change amount.

A more accurate translation would be:
"Vaihtoraha %1 (%2)"
```

```
        <source>Encrypt the wallet. The wallet will be encrypted with a passphrase of your choice.</source>
        <translation>Salaa lompakko. Lompakko salataan valitsemallasa salasanalla.</translation>
    
YES  
The Finnish translation has some spelling and grammatical errors. "Salaa lompakko" is incorrect; the correct verb form for the command is "Salaa lompakko" (capitalize only if at the start of the sentence, and the verb spelling is correct as "salaa"). More importantly, "valitsemallasa" is a typo and should be "valitsemallasi" to mean "of your choice" in the correct possessive form. Also, "salasanalla" means "with a password," but "passphrase" is better translated as "salalause" or "salalauseella," which is more accurate for cryptographic contexts. However, "salasanalla" is often used as well. For a precise and natural Finnish translation in this context, the following is better:

Correct translation:  
Salkaa lompakko. Lompakko salataan valitsemallasi salasanalla.
```

```
        <source>Welcome to %1.</source>
        <translation>Tervetuloa %1 pariin.</translation>
    
YES  
The translated phrase "Tervetuloa %1 pariin." is incorrect in this context. The English "Welcome to %1." is a standard greeting typically meaning "Welcome to [a place or service]." The addition of "pariin" (meaning "a pair" or "a couple") changes the meaning and is not appropriate here.

Correct translation:  
Tervetuloa %1.
```

```
        <source>Unknown. Syncing Headers (%1, %2%)…</source>
        <translation>Tuntematon. Synkronoidaan järjestysnumeroita (%1,%2%)...</translation>
    
YES  
The translation is mostly accurate, but there are minor spacing issues and a slight nuance problem. The ellipsis is translated as three dots "..." instead of the single Unicode ellipsis character "…", which is used in the source. Also, there should be a space after the comma between %1 and %2% in the parentheses according to Finnish typography and as in the source " (%1, %2%) " with a space after the comma. Finally, the term "järjestysnumeroita" ("sequence numbers") is not the best equivalent for "Headers" in the Bitcoin context. A better term would be "lohko-otsikoita" (block headers), which corresponds to "headers" in the blockchain context.

Correct translation:  
Tuntematon. Lohko-otsikoita synkronoidaan (%1, %2%)…
```

```
        <source>If you disable the spending of unconfirmed change, the change from a transaction cannot be used until that transaction has at least one confirmation. This also affects how your balance is computed.</source>
        <translation>Jos poistat varmistamattomien vaihtorahojen käytön, ei siirtojen vaihtorahaa ei voida käyttää ennen vähintään yhtä varmistusta. Tämä vaikuttaa myös taseesi lasketaan.</translation>
    
YES  
The translation contains grammatical errors and unnatural phrasing. Specifically:  
- "ei siirtojen vaihtorahaa ei voida käyttää" has a double negation and awkward word order. It should be "siirron vaihtorahaa ei voida käyttää" to correctly mean "the change of a transaction cannot be used".  
- "Tämä vaikuttaa myös taseesi lasketaan." is incorrect grammar. It should be "Tämä vaikuttaa myös siihen, miten saldosi lasketaan." or "Tämä vaikuttaa myös siihen, kuinka saldosi lasketaan." ("saldo" is more natural than "tase" in this context).  

Correct translation:  
Jos poistat varmistamattomien vaihtorahojen käytön, siirron vaihtorahaa ei voida käyttää ennen yhtä varmistusta. Tämä vaikuttaa myös siihen, kuinka saldosi lasketaan.
```

```
        <source>Current settings will be backed up at "%1".</source>
        <extracomment>Text explaining to the user that the client's current settings will be backed up at a specific location. %1 is a stand-in argument for the backup location's path.</extracomment>
        <translation>Nykyiset asetukset varmuuskopioidaan klo"%1"</translation>
    
YES  
The translation has an issue with the inappropriate use of "klo" (which means "o'clock" and relates to time), and missing spacing before the quotation mark. The original text refers to a backup location, not a time.

Correct translation:
Nykyiset asetukset varmuuskopioidaan sijaintiin "%1".
```

```
        <source>Could not read setting "%1", %2.</source>
        <translation>Ei voinut luke asetusta "%1", %2.</translation>
    
YES  
The Finnish translation "Ei voinut luke asetusta" is incorrect because the verb form is incomplete and the sentence is missing a subject. A correct translation would use the passive form "asetusta" is fine, but the verb should be "lukea" as the infinitive (cannot read) or "lukea asetusta". The phrase "Ei voinut lukea asetusta" translates as "Could not read setting".

Correct translation:  
Ei voinut lukea asetusta "%1", %2.
```

```
        <source>PSBT saved to disk.</source>
        <translation>PSBT (osittain tallennettu bitcoin-siirto) tallennettiin levylle.</translation>
    
YES  
The translation introduces an explanatory phrase "(osittain tallennettu bitcoin-siirto)" which is not in the original source and changes the meaning. The original text simply states "PSBT saved to disk." PSBT is an acronym well known in Bitcoin context, so it should be kept as is without adding an explanation. Also, the format is slightly off; adding parentheses and extra explanation is unnecessary and misleading.

Correct translation:  
PSBT tallennettiin levylle.
```

```
        <source>User Agent</source>
        <extracomment>Title of Peers Table column which contains the peer's User Agent string.</extracomment>
        <translation>Käyttöliittymä</translation>
    
YES  
The translation "Käyttöliittymä" means "User Interface," which is incorrect in this context. The correct translation for "User Agent" (referring to the software agent string identifying a peer) should be "Käyttäjäagentti."

Correct translation:  
Käyttäjäagentti
```

```
        <source>Transaction Relay</source>
        <translation>Siirtokulu</translation>
    
YES
The Finnish translation "Siirtokulu" means "transfer fee" or "transaction fee," which is incorrect in this context. The English phrase "Transaction Relay" refers to the forwarding or relaying of transactions, not the fee associated with them.

Correct translation:
"Transaktioiden välitys" or simply "Transaktioiden välitys"
```

```
        <source>Ctrl+=</source>
        <extracomment>Secondary shortcut to increase the RPC console font size.</extracomment>
        <translation>Ctrl+-</translation>
    
YES
The translation incorrectly changes the shortcut key from "Ctrl+=" to "Ctrl+-", which alters the intended meaning. The original shortcut "Ctrl+=" is meant to increase the font size, so it should be kept the same in Finnish.

Correct translation:
Ctrl+=
```

```
        <source>1 day</source>
        <translation>1 pivä</translation>
    
YES  
The Finnish word for "day" is "päivä", not "pivä". The correct translation is:  
1 päivä
```

```
        <source>Executing command without any wallet</source>
        <translation>Suoritetaan komento ilman lomakkoa</translation>
    
YES  
The Finnish word "lomakkoa" means "form" (as in a document form), which is incorrect in this context. The English "wallet" refers to a Bitcoin wallet ("lompakko" in Finnish). The correct translation should use "lompakkoa" instead of "lomakkoa."

Correct translation:  
Suoritetaan komento ilman lompakkoa
```

```
        <source>Generates a native segwit address (BIP-173). Some old wallets don't support it.</source>
        <translation> 
Luo natiivin segwit-osoitteen (BIP-173). Jotkin vanhat lompakot eivät tue sitä.</translation>
    
YES  
There is a leading whitespace character (non-breaking space or space) before the translation that should be removed. The rest of the translation is accurate and correctly carries over the meaning and format.  

Correct translation:  
Luo natiivin segwit-osoitteen (BIP-173). Jotkin vanhat lompakot eivät tue sitä.
```

```
        <source>Request payment to …</source>
        <translation>Pyydä maksua ooitteeseen ...</translation>
    
YES  
The Finnish translation contains a typo: "ooitteeseen" should be "osoitteeseen." Also, the ellipsis is better written as a single character "…" instead of three dots for consistency with the source.

Correct translation:  
Pyydä maksua osoitteeseen …
```

```
        <source>Hide transaction fee settings</source>
        <translation> Piilota siirtomaksuasetukset</translation>
    
YES  
The translation has a leading whitespace before "Piilota" which is incorrect formatting. Otherwise, the translation accurately conveys "Hide transaction fee settings" in Finnish. The correct translation without the leading space is:  
Piilota siirtomaksuasetukset
```

```
        <source>Copy after fee</source>
        <translation>Kopioi rahansiirtokulun jälkeen</translation>
    
YES
The translation "Kopioi rahansiirtokulun jälkeen" literally means "Copy after the transfer fee," which is a misinterpretation of the original phrase "Copy after fee." In the context of Bitcoin, "after fee" means the amount or value after deducting the fee, not an instruction to copy something. The term "copy" here is a verb and should correspond directly to the action in English.

A more accurate translation that preserves the meaning would be:
"Kopioi kulujen jälkeen" or "Kopioi maksun jälkeen"

If the phrase is a label or button meaning "Copy the amount after fee deduction," then:
"Kopioi määrä kulujen jälkeen" (Copy amount after fees)

Since the source only says "Copy after fee," the simplest accurate translation is:
"Kopioi kulun jälkeen"
```

```
        <source>Creates a Partially Signed Bitcoin Transaction (PSBT) for use with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <translation>Luo osittain allekirjoitetun bitcoin-siirtotapahtuman (PSBT) käytettäväksi mm. offline %1 lompakko tai PSBT-yhteensopiva hardware-lompakko.</translation>
    
YES
The Finnish translation is mostly understandable but has issues with missing prepositions and awkward phrasing. Specifically:
- "käytettäväksi mm. offline %1 lompakko tai PSBT-yhteensopiva hardware-lompakko." is missing the partitive suffix or a possessive form to indicate "with an offline wallet" or "with e.g. an offline wallet."
- The phrase "offline %1 lompakko tai PSBT-yhteensopiva hardware-lompakko" should be connected better, for example using "kuten" (such as) or "esimerkiksi" (for example).
- The word "hardware-lompakko" could be better translated as "laitteistolompakko" or simply "laitteistolompakko" to avoid mixing English.

A more natural and correct Finnish translation would be:
"Luo osittain allekirjoitetun bitcoin-siirtotapahtuman (PSBT) käytettäväksi esimerkiksi offline-%1-lompakon tai PSBT-yhteensopivan laitteistolompakon kanssa."

Note that:
- "esimerkiksi" corresponds to "e.g."
- Offline-%1-lompakon has hyphens to clarify the compound
- "kanssa" corresponds to "with"
- "laitteistolompakon" is the Finnish term for hardware wallet (literally hardware wallet)

Correct translation:
Luo osittain allekirjoitetun bitcoin-siirtotapahtuman (PSBT) käytettäväksi esimerkiksi offline-%1-lompakon tai PSBT-yhteensopivan laitteistolompakon kanssa.
```

```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>Ei signalointia Korvattavissa korkeammalla kululla, BIP-125.</translation>
    
YES
The translation has a grammatical error and awkward phrasing. "Ei signalointia" is not correct Finnish. A better and more natural translation would be:

"Ei signaalia Replace-By-Fee -toiminnolle, BIP-125."
```

```
        <source>A fee higher than %1 is considered an absurdly high fee.</source>
        <translation>%1:tä ja korkeampaa siirtokulua pidetään mielettömän korkeana.</translation>
    
YES  
The translation inaccurately uses the partitive case "%1:tä" which is grammatically incorrect here because "%1" is a placeholder for a precise numeric value and should be clearly tied to the noun. Also, "siirtokulua" (transfer fee) is somewhat correct but "maksua" (fee) is more standard and simple to use here. The original phrase indicates that a fee higher than %1 is considered absurdly high, so the comparative should be clear and straightforward.

Correct translation:  
"%1:ä suurempaa maksua pidetään mielettömän korkeana."
```

```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>Varmistetaan (%1 suositellusta %2 varmistuksesta)</translation>
    
YES  
The Finnish translation is awkward and does not accurately convey the meaning of the original. The source means "Confirming (X of Y recommended confirmations)" — i.e., the process of confirming with the number of confirmations so far out of the recommended total. The Finnish translation "Varmistetaan (%1 suositellusta %2 varmistuksesta)" literally reads "Confirming (X of recommended Y confirmations)" but with incorrect grammar and phrasing.

A better translation would use the partitive and genitive cases properly and sound more natural:

Correct translation:  
Vahvistetaan (%1 / suositellusta %2 vahvistuksesta)
```

```
        <source>Transaction status. Hover over this field to show number of confirmations.</source>
        <translation>Rahansiirron tila. Siirrä osoitin kentän päälle nähdäksesi vahvistusten lukumäärä.</translation>
    
YES  
The translation is in Finnish ("fi"), but the given translation is actually in Finnish, and it means "Transaction status. Move the cursor over the field to see the number of confirmations." which is appropriate and accurate. However, the first word "Rahansiirron" means "of the money transfer," which is less common in the context of Bitcoin transactions; the usual term in Bitcoin context is "Tapahtuman" or "Siirron" for "Transaction."

A better translation using common Bitcoin terminology would be:

"Tapahtuman tila. Vie osoitin tämän kentän päälle nähdäksesi vahvistusten lukumäärän."

Or, slightly simpler:

"Siirron tila. Vie osoitin kentän päälle nähdäksesi vahvistusten lukumäärän."

So, the current translation is correct in meaning but can be improved for terminology and style. Also, there is a minor spacing issue: after 'näetäksesi' the word is correctly concatenated, but the phrase "näytäksesi vahvistusten lukumäärä" might be better as "näetksesi vahvistusten lukumäärän" with correct case.

Therefore:

YES  
The translation uses less typical terminology for 'Transaction' ("Rahansiirron" = "money transfer"), which is less suitable in a Bitcoin context. Also, better phrasing would be more idiomatic and accurate.

Correct translation:  
"Tapahtuman tila. Vie osoitin kentän päälle nähdäksesi vahvistusten lukumäärän."
```

```
        <source>Copy full transaction details</source>
        <translation>Kopioi koko tapahtuma  tiedot</translation>
    
YES  
There is an extra space between "tapahtuma" and "tiedot". The correct translation should be:  
Kopioi koko tapahtumatiedot
```

```
        <source>Edit address label</source>
        <translation>Muokkaa osoitekenttää</translation>
    
YES  
The translation "Muokkaa osoitekenttää" means "Edit the address field" rather than "Edit address label." The correct Finnish term for "label" in this context (i.e., a descriptive tag/name for the address) is "tunniste" or "etiketti." A better translation would be:

Muokkaa osoitteen tunnistetta
```

```
        <source>Partially Signed Transaction (*.psbt)</source>
        <translation>Osittain allekirjoitettu siirto (*.pbst)</translation>
    
YES
There is a typo in the file extension. The source has "*.psbt" but the translation has "*.pbst".

Correct translation:
Osittain allekirjoitettu siirto (*.psbt)
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>PBST-tiedoston tulee olla pienempi kuin 100 mebitavua</translation>
    
YES  
There is a typographical error in the translation: "PBST" should be "PSBT" to match the source. Also, "Mebi" is typically abbreviated as "Mi" (not "mebi") in Finnish technical terminology.

Correct translation:  
PSBT-tiedoston tulee olla pienempi kuin 100 MiB
```

```
        <source>Increase:</source>
        <translation>Korota:</translation>
    
YES  
The translation "Korota:" is not Finnish; it appears to be in another language (possibly Swahili). The correct Finnish translation for "Increase:" in this context is "Kasvata:" or "Lisää:".  

Correct translation:  
Kasvata:  
(or)  
Lisää:
```

```
        <source>Warning: This may pay the additional fee by reducing change outputs or adding inputs, when necessary. It may add a new change output if one does not already exist. These changes may potentially leak privacy.</source>
        <translation> 
Varoitus: Tämä voi maksaa ylimääräisen maksun vähentämällä vaihtotuloja tai lisäämällä tuloja tarvittaessa. Se voi lisätä uuden vaihtotulojen, jos sellaista ei jo ole. Nämä muutokset voivat mahdollisesti vuotaa yksityisyyttä.</translation>
    
YES  
The Finnish translation has an extra leading whitespace character at the start, which is a formatting issue. Also, the phrase "uuden vaihtotulojen" is incorrect because "uuden" (singular) does not agree with "vaihtotulojen" (plural, genitive). The correct phrase should be "uuden vaihtotulon" (singular, genitive), referring to "a new change output." Additionally, "inputs" is translated as "tuloja" (which means "income" or "revenue") instead of something like "sisääntuloja" or "inputeja," which would be more appropriate in this technical context. The term "change outputs" is translated as "vaihtotuloja," but the common Bitcoin translation uses "vaihtorahat" or "vaihtolähdöt." 

A better translation:

"Varoitus: Tämä saattaa maksaa ylimääräisen maksun vähentämällä vaihtorahalähteitä tai lisäämällä sisääntuloja tarvittaessa. Se saattaa lisätä uuden vaihtolähdön, jos sellaista ei vielä ole. Nämä muutokset voivat mahdollisesti vuotaa yksityisyyttä."

Corrected translation without leading space and fixed terminology:

<translation>Varoitus: Tämä saattaa maksaa ylimääräisen maksun vähentämällä vaihtorahalähteitä tai lisäämällä sisääntuloja tarvittaessa. Se saattaa lisätä uuden vaihtolähdön, jos sellaista ei vielä ole. Nämä muutokset voivat mahdollisesti vuotaa yksityisyyttä.</translation>
```

```
        <source>Signer error</source>
        <translation>Signaalivirhe</translation>
    
YES  
The Finnish translation "Signaalivirhe" means "Signal error," which is incorrect in the context of "Signer error." The correct translation should reflect an error related to a "signer" (a person or component that signs something, e.g., a cryptographic signature). A suitable translation would be:  

Correct translation:  
Allekirjoittajan virhe
```

```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>%s virheellinen -assumeutxo-snapshot-tila. Tämä viittaa laitteistoon liittyvään ongelmaan, ohjelmistovirheeseen tai huonoon ohjelmistomuutokseen, joka on sallinut virheellisen snapshotin lataamisen. Tämän seurauksena solmu sulkeutuu ja lopettaa kaiken sen tilan käytön, joka perustui snapshottiin, ja nollaa lohkokorkeuden%darvoon%d. Seuraavassa uudelleenkäynnistyksessä solmu jatkaa synkronointia kohdasta%d  
ilman, että käytetään mitään snapshot-tietoja. Ilmoita tästä tapauksesta osoitteeseen%s, mukaan lukien se, miten sait snapshotin. Virheellinen snapshot-tilatiedosto jätetään levylle, jos se on hyödyllinen ongelman diagnosoinnissa, joka aiheutti tämän virheen.</translation>
    
YES  
The translation has spacing issues around format specifiers ("%d") where no spaces or incorrect spacing appear. Also, the sentence structure is somewhat awkward, and there are unnecessary spaces or misplaced commas in some places. For example, "lohkokorkeuden%darvoon%d" lacks spaces around %d, "kohdasta%d   ilman, että käytetään" contains a line break and comma awkwardly placed, and "osoitteeseen%s" has no space before %s.

A more natural and clean Finnish translation preserving format specifiers and spacing could be:

%s epäonnistui -assumeutxo-snapshot-tilan vahvistamisessa. Tämä viittaa laitteisto-ongelmaan, ohjelmistovirheeseen tai huonoon ohjelmistomuutokseen, jonka seurauksena virheellinen snapshot on ladattu. Tämän vuoksi solmu sulkeutuu ja lopettaa kaiken snapshottiin perustuvan tilan käytön, nollaten lohkokorkeuden arvosta %d arvoon %d. Seuraavassa uudelleenkäynnistyksessä solmu jatkaa synkronointia kohdasta %d ilman snapshot-tietojen käyttämistä. Ilmoita tästä tapauksesta osoitteeseen %s, mukaan lukien miten sait snapshotin. Virheellinen snapshot-tilatiedosto jätetään levylle, mikäli se on hyödyksi virheen syyn diagnosoinnissa.
```

```
        <source>Prune configured below the minimum of %d MiB.  Please use a higher number.</source>
        <translation>Karsinta konfiguroitu alle minimin %d MiB. Käytä surempaa numeroa.</translation>
    
YES  
The translation is incorrect and contains non-Finnish words. The original means "Prune configured below the minimum of %d MiB. Please use a higher number." The correct Finnish translation should be:  
"Leikkaus on määritetty alle minimimäärän %d MiB. Käytä suurempaa lukua."
```

```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of pruned node)</source>
        <translation>Karsinta: viime lompakon synkronisointi menee karsitun datan taakse. Sinun tarvitsee ajaa -reindex (lataa koko lohkoketju uudelleen tapauksessa jossa karsiva noodi)</translation>
    
YES  
The translation uses "Karsinta," which means "inspection" or "examination," instead of "Prune," which in the Bitcoin context means "to trim or remove old blockchain data." The correct Finnish term in this context would be "Karsinta" only if it means pruning, but it is better to keep "Prune:" as "Karsinta:" to keep the technical meaning consistent. However, the rest of the sentence has some grammatical issues:

- "viime lompakon synkronisointi" -> The source says "last wallet synchronisation," which should be "viimeisin lompakon synkronointi" to denote "last."
- "karsiva noodi" translates to "pruning node," but "node" is commonly translated as "solmu," and "pruned node" is often "karsittu solmu."
- Missing commas and slight phrasing issues: "tapauksessa jossa" should have a comma: "tapauksessa, jossa".
- "Sinun tarvitsee ajaa -reindex" is understandable but could be improved as "Sinun täytyy ajaa -reindex" or "Sinun täytyy käyttää -reindex-komentoa."

Corrected translation:  
"Karsinta: viimeisin lompakon synkronisointi menee karsitun datan taakse. Sinun täytyy ajaa -reindex (lataa koko lohkoketju uudelleen tapauksessa, jossa käytössä on karsittu solmu)."
```

```
        <source>Unable to replay blocks. You will need to rebuild the database using -reindex-chainstate.</source>
        <translation>Lohkoja ei voida uudelleenlukea. Joulut uudelleenrakentamaan tietokannan käyttämällä -reindex-chainstate -valitsinta.</translation>
    
YES  
The Finnish translation contains an error: "Joulut" is incorrect and likely a typo for "Joudut." The sentence should indicate that the user needs to rebuild the database ("Joudut uudelleenrakentamaan...").

Correct translation:  
Lohkoja ei voida uudelleenlukea. Joudut uudelleenrakentamaan tietokannan käyttämällä -reindex-chainstate -valitsinta.
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Varoitus: lompakosta {%s} tunnistetut yksityiset avaimet, on poistettu käytöstä</translation>
    
YES  
The translation is unclear and grammatically incorrect. The English sentence warns that private keys were detected in a wallet where private keys are disabled. The Finnish translation incorrectly implies that private keys have been disabled or removed, which is misleading.

Correct translation:  
Varoitus: Lompakossa {%s} havaittu yksityisiä avaimia, vaikka yksityisavaimet ovat poistettu käytöstä
```

```
        <source>
Unable to restore backup of wallet.</source>
        <translation>
Ei voinut palauttaa lompakon varmuuskopiota..</translation>
    
YES  
There are two issues:  
1. The translation has a leading newline character, which should be removed to match the source formatting.  
2. There are two periods ".." at the end instead of one.  

Correct translation:  
Ei voinut palauttaa lompakon varmuuskopiota.
```

```
        <source>Error reading configuration file: %s</source>
        <translation>Virhe luettaessa asetustiedostoa 1%s</translation>
    
YES  
The format specifier `%s` is incorrectly written as `1%s`, which is erroneous. Also, there is an extra space before the format specifier that should be removed for correct formatting.  

Correct translation:  
Virhe luettaessa asetustiedostoa %s
```

```
        <source>Not solvable pre-selected input %s</source>
        <translation>Ei ratkaistavissa esivalittu tulo%s</translation>
    
YES  
The translation incorrectly merges the format specifier %s with the preceding word without a space, which causes formatting issues. Also, "Ei ratkaistavissa" should be "Ei ratkaistavissa oleva" or similar to convey "Not solvable". The word "input" is translated as "tulo", which can mean "income" or "arrival" in Finnish and is misleading in the Bitcoin context. A better term here is "sisääntulo" or "syöte".  

Correct translation:  
"Ei ratkaistavissa oleva esivalittu syöte %s"
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>Lähetyksen siirtosumman tulee olla positiivinen</translation>
    
YES  
The translation implies that the transaction amount must be positive, but the source states that the amounts must not be negative, which technically allows zero as well. Also, "lähetyksen siirtosumman" is an awkward and somewhat incorrect compound. A clearer and more accurate translation would be:  

"Siirtosummien ei saa olla negatiivisia"
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>Tapahtuma vaatii osoitteenmuutoksen, mutta emme voi luoda sitä.</translation>
    
YES  
The translation inaccurately translates "change address." In the Bitcoin context, "change address" refers to an address to which the remaining amount (change) of a transaction is sent, not "osoitteenmuutos," which means "address change" in the sense of changing an address. The correct Finnish term would be "vaihto-osoite" or "muutososoite," referring specifically to a change address in Bitcoin transactions.

Correct translation:  
Transaction needs a change address, but we can't generate it.  
→  
Tapahtuma tarvitsee muutososoitteen, mutta emme voi luoda sitä.
```

```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>hyväksyttyjä ilmaisia ​​arvioita ei tueta %s ketju.</translation>
    
YES
The Finnish translation is incorrect and partially nonsensical. The English phrase "acceptstalefeeestimates is not supported on %s chain." is a technical setting name and message. It should not be translated literally as "hyväksyttyjä ilmaisia arvioita", which means "accepted free estimates," which does not correspond to the original meaning.

Also, the phrase "ei tueta %s ketju" is grammatically wrong; it should be "ei ole tuettu %s-ketjulla" or similar, including proper cases and hyphenation.

A correct Finnish translation would be:

"acceptstalefeeestimates ei ole tuettu %s-ketjussa."
```
</details>
