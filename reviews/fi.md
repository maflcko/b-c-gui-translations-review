# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>fi</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bfi%5D%20low%20quality)


```
        <source>Passphrase Dialog</source>
        <translation>Tunnuslauseen tekstinsyöttökenttä</translation>
    
YES
The translation "Tunnuslauseen tekstinsyöttökenttä" means "passphrase text input field", which is more specific than "Passphrase Dialog". The original refers to a dialog window, not specifically the input field.

Correct translation:
Tunnuslauseen valintaikkuna
```

```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>Lohko Rele</translation>
    
YES
The translation "Lohko Rele" is not idiomatic Finnish; the compound words are not joined, and "rele" usually means a physical relay component, not an information relay. The correct and commonly used translation for "Block Relay" in this context would be "Lohkovälitys" or "Lohkojen välitys".

Correct translation:
Lohkovälitys
```

```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>Tunturi</translation>
    
YES
The Finnish word "Tunturi" means "fell" (a type of mountain/hill) and is not appropriate here. The source term "Feeler" refers to a probing connection, someone who "feels out" or tests. 
A better translation would be:
Kokeilija

Correct translation:
Kokeilija
```

```
        <source>Network activity disabled.</source>
        <extracomment>A substring of the tooltip.</extracomment>
        <translation>Verkkoyhteysmittari pois käytöstä</translation>
    
YES
The translation "Verkkoyhteysmittari pois käytöstä" means "Network connection meter disabled", which is not accurate for the source "Network activity disabled." The correct translation should refer to the network activity itself, not a connection meter.

Correct translation:
Verkkoliikenne poistettu käytöstä.
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Varmista, että viestisi on allekirjoitettu määritetyllä Bitcoin -osoitteella</translation>
    
YES
The translation has minor issues:
1. The English original talks about verifying "messages" (plural), but the translation uses the singular "viestisi" (your message). This changes the meaning.
2. There is a space before the hyphen in "Bitcoin -osoitteella", which is nonstandard in Finnish. It should be "Bitcoin-osoitteella" with no space.

Correct translation:
Varmenna viestit varmistaaksesi, että ne on allekirjoitettu määritetyillä Bitcoin-osoitteilla
```

```
        <source>Syncing Headers (%1%)…</source>
        <translation>Synkronoi järjestysnumeroita (%1%)...</translation>
    
YES
The translation is inaccurate. "Headers" in the context of Bitcoin refers to "lohkopäät" or "lohkotunnisteet", not "järjestysnumeroita" ("sequence numbers"). Also, the ellipsis should be the same Unicode character as the source. The format specifier %1% should be just %1 as in the source.

Correct translation:
Synkronoidaan lohkopäitä (%1)…
```

```
        <source>Catching up…</source>
        <translation>Jäljellä...</translation>
    
YES
The translation is inaccurate. "Jäljellä..." means "remaining..." or "left...", which does not convey the meaning of "Catching up…", typically shown when synchronizing with the blockchain. A better translation would be:

Correct translation:
Otetaan kiinni…
or
Synkronoidaan…
```

```
        <source>Last received block was generated %1 ago.</source>
        <translation>Viimeisin vastaanotettu lohko tuotettu %1.</translation>
    
YES  
The translation drops "ago" and the passive verb, making it less clear and incorrect in Finnish. Also, "tuotettu" is less standard than "luotiin" in this context.

Correct translation:  
Viimeisin vastaanotettu lohko luotiin %1 sitten.
```

```
        <source>Lock unspent</source>
        <translation>Lkitse käyttämättömät</translation>
    
YES
There is a typographical error in the Finnish translation: "Lkitse" should be "Lukitse".

Correct translation:
Lukitse käyttämättömät
```

```
        <source>Unlock unspent</source>
        <translation>Avaa käyttämättömien lukitus</translation>
    
YES
The translation "Avaa käyttämättömien lukitus" is not fully accurate. The phrase "Unlock unspent" refers to unlocking unspent transaction outputs (UTXOs), and the correct Finnish translation should more directly match the English imperative and subject.

Correct translation:
Avaa käyttämättömät
```

```
        <source>change from %1 (%2)</source>
        <translation>Vaihda %1 (%2)</translation>
    
YES
The translation is inaccurate. The English phrase "change from %1 (%2)" (in the context of Bitcoin, "change" refers to the returned amount from a transaction) should be translated to retain this meaning, not as an imperative "Vaihda" ("Change [something]"). The correct Finnish term for "change" in this financial/Bitcoin sense is "vaihtoraha".

Correct translation:
Vaihtoraha %1 (%2)
```

```
        <source>Encrypt the wallet. The wallet will be encrypted with a passphrase of your choice.</source>
        <translation>Salaa lompakko. Lompakko salataan valitsemallasa salasanalla.</translation>
    
YES
There is a small spelling error in the translation: "valitsemallasa" should be "valitsemallasi". The "sa" ending is a typo; the correct form is "si" for "your" (possessive).

Correct translation:
Salaa lompakko. Lompakko salataan valitsemallasi salasanalla.
```

```
        <source>Unknown. Syncing Headers (%1, %2%)…</source>
        <translation>Tuntematon. Synkronoidaan järjestysnumeroita (%1,%2%)...</translation>
    
YES
The Finnish translation uses "järjestysnumeroita" (ordinal numbers) instead of "lohkojen otsikoita" (block headers), which is the correct term in the context of Bitcoin. Also, a space is missing after the comma in numbers (%1,%2%).

Correct translation:
Tuntematon. Synkronoidaan lohkojen otsikoita (%1, %2%)...
```

```
        <source>If you disable the spending of unconfirmed change, the change from a transaction cannot be used until that transaction has at least one confirmation. This also affects how your balance is computed.</source>
        <translation>Jos poistat varmistamattomien vaihtorahojen käytön, ei siirtojen vaihtorahaa ei voida käyttää ennen vähintään yhtä varmistusta. Tämä vaikuttaa myös taseesi lasketaan.</translation>
    
YES
The translation has multiple grammar issues and awkward phrasing in Finnish. "Tämä vaikuttaa myös taseesi lasketaan" is ungrammatical, and parts of the translation do not flow naturally. Also, "taseesi" does not match the way "your balance" should be expressed in this context ("saldosi" is preferable). 

Correct translation:
Jos poistat käytöstä vahvistamattoman vaihtorahan käyttämisen, ei siirrosta saatua vaihtorahaa voi käyttää ennen kuin siirrolla on vähintään yksi vahvistus. Tämä vaikuttaa myös siihen, miten saldosi lasketaan.
```

```
        <source>Current settings will be backed up at "%1".</source>
        <extracomment>Text explaining to the user that the client's current settings will be backed up at a specific location. %1 is a stand-in argument for the backup location's path.</extracomment>
        <translation>Nykyiset asetukset varmuuskopioidaan klo"%1"</translation>
    
YES
There is a formatting issue: in Finnish, "klo" means "at" in the context of time (e.g., "at 10 o'clock"), but here we are talking about a file path/location, not a time. Also, there is a missing space before the quotation mark, and the wording is somewhat clumsy.

Correct translation:
Nykyiset asetukset varmuuskopioidaan sijaintiin "%1".
```

```
        <source>Could not read setting "%1", %2.</source>
        <translation>Ei voinut luke asetusta "%1", %2.</translation>
    
YES
There is a typographical error: "luke" should be "lukea" (the infinitive form). Also, "asetusta" should be "asetusta" (the partitive case), which is correct, but more common would be "asetusta" in this context.

Correct translation:
Ei voitu lukea asetusta "%1", %2.
```

```
        <source>PSBT saved to disk.</source>
        <translation>PSBT (osittain tallennettu bitcoin-siirto) tallennettiin levylle.</translation>
    
YES
The translation expands "PSBT" into "osittain tallennettu bitcoin-siirto", which is not accurate—PSBT stands for "Partially Signed Bitcoin Transaction" ("osittain allekirjoitettu bitcoin-siirto" in Finnish). Furthermore, the source does not expand the abbreviation, so the translation should keep "PSBT" and should match the brevity of the source.

Correct translation:
PSBT tallennettu levylle.
```

```
        <source>User Agent</source>
        <extracomment>Title of Peers Table column which contains the peer's User Agent string.</extracomment>
        <translation>Käyttöliittymä</translation>
    
YES
The translation is inaccurate. "Käyttöliittymä" means "user interface", not "user agent". The correct translation for "User Agent" in Finnish is "Käyttäjäagentti".

Correct translation:
Käyttäjäagentti
```

```
        <source>Transaction Relay</source>
        <translation>Siirtokulu</translation>
    
YES
The translation is inaccurate. "Siirtokulu" means "transaction fee" in Finnish, not "Transaction Relay." The correct translation should refer to the process of relaying or forwarding transactions.

Correct translation:
Transaktion välitys

Alternatively:
Siirron välitys
```

```
        <source>Ctrl+=</source>
        <extracomment>Secondary shortcut to increase the RPC console font size.</extracomment>
        <translation>Ctrl+-</translation>
    
YES  
The translation is incorrect. The source denotes the "Ctrl+=" keyboard shortcut, but the translation changes it to "Ctrl+-", which would be interpreted as "minus", not "equals". The shortcut semantics are thus reversed.

Correct translation:
Ctrl+=
```

```
        <source>1 day</source>
        <translation>1 pivä</translation>
    
YES
There is a typographical error in the Finnish word: "pivä" should be "päivä".

Correct translation:
1 päivä
```

```
        <source>Generates a native segwit address (BIP-173). Some old wallets don't support it.</source>
        <translation> 
Luo natiivin segwit-osoitteen (BIP-173). Jotkin vanhat lompakot eivät tue sitä.</translation>
    
YES
There is a leading whitespace character (non-breaking space or newline) before the translation, which is a formatting issue. Otherwise, the translation is accurate.

Correct translation:
Luo natiivin segwit-osoitteen (BIP-173). Jotkin vanhat lompakot eivät tue sitä.
```

```
        <source>Request payment to …</source>
        <translation>Pyydä maksua ooitteeseen ...</translation>
    
YES
There is a spelling error in the Finnish word "ooitteeseen". It should be "osoitteeseen". Also, the ellipsis should be "…" (U+2026) rather than three periods, to match the source formatting. 

Correct translation:
Pyydä maksua osoitteeseen …
```

```
        <source>Hide transaction fee settings</source>
        <translation> Piilota siirtomaksuasetukset</translation>
    
YES
There is an extra space at the beginning of the translation, causing a whitespace formatting issue.

Correct translation:
Piilota siirtomaksuasetukset
```

```
        <source>Creates a Partially Signed Bitcoin Transaction (PSBT) for use with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <translation>Luo osittain allekirjoitetun bitcoin-siirtotapahtuman (PSBT) käytettäväksi mm. offline %1 lompakko tai PSBT-yhteensopiva hardware-lompakko.</translation>
    
YES
There is a grammatical problem in the translation: "käytettäväksi mm. offline %1 lompakko tai PSBT-yhteensopiva hardware-lompakko." should use the instructive or adessive case and proper plural form to cover both options ("lompakossa tai PSBT-yhteensopivassa laitteistolompakossa"). Also "hardware-lompakko" should be "laitteistolompakko". A more natural formulation would be:

Correct translation:
Luo osittain allekirjoitetun bitcoin-siirtotapahtuman (PSBT), jota voi käyttää esimerkiksi offline-%1-lompakossa tai PSBT-yhteensopivassa laitteistolompakossa.
```

```
        <source>A fee higher than %1 is considered an absurdly high fee.</source>
        <translation>%1:tä ja korkeampaa siirtokulua pidetään mielettömän korkeana.</translation>
    
YES
The translation is mostly correct but could be improved for naturalness. The translation uses "%1:tä", which tries to reflect the partitive case, but the English "higher than %1" should directly translate as "suurempaa kuin %1". Also, "siirtokulua" is good, but "maksua" (fee) can also be used.

Correct translation:
Suurempaa kuin %1 maksua pidetään mielettömän korkeana.
```

```
        <source>Copy full transaction details</source>
        <translation>Kopioi koko tapahtuma  tiedot</translation>
    
YES
There is an extra space between "tapahtuma" and "tiedot" that should not be there.

Correct translation:
Kopioi koko tapahtumatiedot
```

```
        <source>Edit address label</source>
        <translation>Muokkaa osoitekenttää</translation>
    
YES
The translation "Muokkaa osoitekenttää" means "Edit the address field", which does not accurately reflect "Edit address label". It should refer to editing the label associated with the address, not the address field itself.

Correct translation:
Muokkaa osoitteen nimeä
```

```
        <source>Partially Signed Transaction (*.psbt)</source>
        <translation>Osittain allekirjoitettu siirto (*.pbst)</translation>
    
YES
There is an error in the filename extension; it should be '.psbt', not '.pbst'. Otherwise the translation is accurate.

Correct translation:
Osittain allekirjoitettu siirto (*.psbt)
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>PBST-tiedoston tulee olla pienempi kuin 100 mebitavua</translation>
    
YES
There is a typo in the abbreviation: "PBST" should be "PSBT", to match the English source and Bitcoin context.

Correct translation:
PSBT-tiedoston tulee olla pienempi kuin 100 mebitavua
```

```
        <source>Warning: This may pay the additional fee by reducing change outputs or adding inputs, when necessary. It may add a new change output if one does not already exist. These changes may potentially leak privacy.</source>
        <translation> 
Varoitus: Tämä voi maksaa ylimääräisen maksun vähentämällä vaihtotuloja tai lisäämällä tuloja tarvittaessa. Se voi lisätä uuden vaihtotulojen, jos sellaista ei jo ole. Nämä muutokset voivat mahdollisesti vuotaa yksityisyyttä.</translation>
    
YES
There are some issues:
1. Whitespace: The translation starts with a stray whitespace line.
2. The term "vaihtotulon" is more appropriate for "change output" than "vaihtotulojen" (which is plural and in the genitive case).
3. "tuloja" translates to "incomes/entries", but in Bitcoin context, "inputs" is best translated as "syötteitä".
4. The plurality/singularity switch in the sentence "Se voi lisätä uuden vaihtotulojen" should be "Se voi lisätä uuden vaihtotulon".
5. The translation of "by reducing change outputs or adding inputs" is better directly as "vähentämällä vaihtotuloja tai lisäämällä syötteitä".
6. The sequence and structure could be improved for clarity.

Correct translation:
Varoitus: Tämä voi maksaa ylimääräisen maksun vähentämällä vaihtotuloja tai lisäämällä syötteitä tarvittaessa. Se voi lisätä uuden vaihtotulon, jos sellaista ei jo ole. Nämä muutokset voivat mahdollisesti vaarantaa yksityisyytesi.

Note: Fixed whitespace and grammar, improved term choices and sentence flow.
```

```
        <source>Signer error</source>
        <translation>Signaalivirhe</translation>
    
YES
The translation "Signaalivirhe" is incorrect in this context. "Signaali" means "signal" in Finnish, but "Signer" here refers to a person or entity that signs (a message, transaction, etc.).

Correct translation:
Allekirjoittajan virhe
```

```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>%s virheellinen -assumeutxo-snapshot-tila. Tämä viittaa laitteistoon liittyvään ongelmaan, ohjelmistovirheeseen tai huonoon ohjelmistomuutokseen, joka on sallinut virheellisen snapshotin lataamisen. Tämän seurauksena solmu sulkeutuu ja lopettaa kaiken sen tilan käytön, joka perustui snapshottiin, ja nollaa lohkokorkeuden%darvoon%d. Seuraavassa uudelleenkäynnistyksessä solmu jatkaa synkronointia kohdasta%d  
ilman, että käytetään mitään snapshot-tietoja. Ilmoita tästä tapauksesta osoitteeseen%s, mukaan lukien se, miten sait snapshotin. Virheellinen snapshot-tilatiedosto jätetään levylle, jos se on hyödyllinen ongelman diagnosoinnissa, joka aiheutti tämän virheen.</translation>
    
YES
There are several issues with the Finnish translation:
- The format specifiers %d and %s are missing spaces or are joined with words (e.g. 'lohkokorkeuden%darvoon%d', 'osoitteeseen%s'), making them error-prone in software use.
- The meaning of "resetting the chain height from %d to %d" is mistranslated as "nollaa lohkokorkeuden%darvoon%d", which is grammatically incorrect and unclear. It should separate the numbers and express "from %d to %d" clearly.
- Extra whitespace after "...kohdasta%d   ilman," should be fixed.
- The translation somewhat omits or changes the structure in a way that is stylistically awkward.

Correct translation:
%s epäonnistui -assumeutxo-snapshotin tilan varmennuksessa. Tämä osoittaa laitteisto-ongelman, ohjelmistovirheen tai huonon ohjelmistomuutoksen, joka on mahdollistanut virheellisen snapshotin lataamisen. Tämän seurauksena solmu sammutetaan ja lopettaa kaikkien snapshotin perusteella rakennetun tilan käytön, palauttaen lohkoketjun korkeuden %d:sta %d:een. Seuraavassa uudelleenkäynnistyksessä solmu jatkaa synkronointia kohdasta %d ilman snapshot-tietoja. Ilmoita tästä tapauksesta osoitteeseen %s ja kerro, miten sait snapshotin. Virheellinen snapshot-tila säilytetään levyllä, jotta sitä voidaan käyttää virheen diagnosoinnissa.

Key fixes:
- %d and %s format specifiers are correctly separated.
- Grammar and style are improved.
- All information is retained and flows naturally in Finnish.
```

```
        <source>Prune configured below the minimum of %d MiB.  Please use a higher number.</source>
        <translation>Karsinta konfiguroitu alle minimin %d MiB. Käytä surempaa numeroa.</translation>
    
YES
There is a typo in the word "suurempaa" ("surempaa" is incorrect), and the phrase "Käytä suurempaa numeroa" is slightly unnatural in Finnish ("numero" should be "arvoa" or "määrää"). Otherwise, format specifier is correct and no spacing or unwanted content issues.

Correct translation:
Karsinta on konfiguroitu alle minimin %d MiB. Käytä suurempaa arvoa.
```

```
        <source>Unable to replay blocks. You will need to rebuild the database using -reindex-chainstate.</source>
        <translation>Lohkoja ei voida uudelleenlukea. Joulut uudelleenrakentamaan tietokannan käyttämällä -reindex-chainstate -valitsinta.</translation>
    
YES
There is a typographical error in the Finnish translation: "Joulut" should be "Joudut" (meaning "you will need to"). Additionally, the translation omits the hyphen before "reindex-chainstate" and has an extra space after it. The correct form is "-reindex-chainstate". Also, "uudelleenlukea" is acceptable, but "toistaa" (replay) would be more natural.

Correct translation:
Lohkoja ei voida toistaa. Joudut uudelleenrakentamaan tietokannan käyttämällä -reindex-chainstate-valitsinta.
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Varoitus: lompakosta {%s} tunnistetut yksityiset avaimet, on poistettu käytöstä</translation>
    
YES
The Finnish translation is inaccurate and changes the meaning. It suggests the private keys were disabled, not that they were detected in a wallet with disabled private keys. Also, the placement of parts is awkward and "on poistettu käytöstä" refers to being disabled, not detected in a wallet with that property.

Correct translation:
Varoitus: Lompakosta {%s} havaittiin yksityisiä avaimia, vaikka yksityiset avaimet on poistettu käytöstä
```

```
        <source>
Unable to restore backup of wallet.</source>
        <translation>
Ei voinut palauttaa lompakon varmuuskopiota..</translation>
    
YES
The translation contains an extra period at the end ("varmuuskopiota..") which is a typographical error. Also, there is unnecessary leading whitespace.

Correct translation:
Ei voitu palauttaa lompakon varmuuskopiota.
```

```
        <source>Error reading configuration file: %s</source>
        <translation>Virhe luettaessa asetustiedostoa 1%s</translation>
    
YES
The format specifier '%s' is incorrectly rendered as '1%s' in the Finnish translation, which is erroneous. The correct translation should retain the '%s' format specifier exactly as in the source.

Correct translation:
Virhe luettaessa asetustiedostoa: %s
```

```
        <source>Not solvable pre-selected input %s</source>
        <translation>Ei ratkaistavissa esivalittu tulo%s</translation>
    
YES
The translation is mostly correct, but there is a minor spacing issue: there should be a space between 'tulo' and the format specifier '%s' to match the source formatting. 'Input' as 'tulo' is acceptable in this context, but sometimes 'syöte' could also be used depending on software context; however, 'tulo' is used in some Finnish Bitcoin translations.

Correct translation:
Ei ratkaistavissa esivalittu tulo %s
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>Lähetyksen siirtosumman tulee olla positiivinen</translation>
    
YES
The translation changes the meaning of the source sentence. The English source says that transaction amounts must not be negative, while the Finnish translation says that the transaction amount "must be positive", which is not strictly the same (zero is allowed in "not negative", but not in "must be positive").

Correct translation:
Tapahtuman määrät eivät saa olla negatiivisia
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>Tapahtuma vaatii osoitteenmuutoksen, mutta emme voi luoda sitä.</translation>
    
YES
The translation "Tapahtuma vaatii osoitteenmuutoksen, mutta emme voi luoda sitä." is inaccurate. "Osoitteenmuutos" literally means "change of address" (like notifying of a new postal address), which is incorrect in the Bitcoin context. The English "change address" refers to a special Bitcoin address that receives the 'change' from a transaction.

Correct translation:
Tapahtuma tarvitsee vaihtorahan osoitteen, mutta emme voi luoda sitä.
```

```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>hyväksyttyjä ilmaisia ​​arvioita ei tueta %s ketju.</translation>
    
YES
The Finnish translation is incorrect in several ways:
- "hyväksyttyjä ilmaisia ​​arvioita" means "accepted free estimates," which completely mistranslates "acceptstalefeeestimates."
- The sentence structure is ungrammatical in Finnish.
- The word "chain" should correspond to "lohkaketju," "ketju," or be adapted in context.

Correct translation:
acceptstalefeeestimates-toimintoa ei tueta %s-ketjussa.
```
</details>

Number of issues: 42.
