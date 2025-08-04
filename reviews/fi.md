# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>fi</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bfi%5D%20low%20quality)


```
        <source>Passphrase Dialog</source>
        <translation>Tunnuslauseen tekstinsyöttökenttä</translation>
    
YES, The translation is inaccurate. The English text "Passphrase Dialog" refers to a window or interface for entering a passphrase, not a text field.
Tunnuslauseen dialogi
```

```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>Lohko Rele</translation>
    
YES. The translation is too literal and sounds unnatural in Finnish. The term "Rele" is not commonly used in this context in Finnish. A more appropriate translation for "Relay" in this context would be "välitys" or "tiedonsiirto". Also, "Lohko" is correct for "Block".

Correct translation: Lohkovälitys
```

```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>Tunturi</translation>
    
YES
The translation is incorrect and does not convey the intended meaning. "Tunturi" means a fell or mountain in Finnish, which is unrelated to the concept of a "feeler" in the context of Bitcoin.

NO
```

```
        <source>Show information about Qt</source>
        <translation>Näytä tietoja Qt:ta</translation>
    
YES, the translation is grammatically incorrect. In Finnish, when "Qt" is used as a direct object with a verb like "Näytä" (Show), it should take the partitive case, which is "Qt:ta" but with a space between "Qt" and the case ending, or better yet, without the unnecessary apostrophe and with the correct case ending. The apostrophe is typically used for foreign words or abbreviations that end in a vowel, which Qt doesn't. A better translation would be "Näytä tietoja Qt:sta" (Show information about Qt) or "Näytä Qt:n tiedot" (Show Qt's information). Given the context of "Show information about...", the partitive case is usually preferred when referring to a topic or subject in a general sense.

NO
```

```
        <source>Network activity disabled.</source>
        <extracomment>A substring of the tooltip.</extracomment>
        <translation>Verkkoyhteysmittari pois käytöstä</translation>
    
YES - The translation means "Network connection meter is disabled", which is not the same as "Network activity disabled".
The correct translation should be "Verkkotoiminta pois käytöstä" or "Verkkotoiminnot pois käytöstä".
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Varmista, että viestisi on allekirjoitettu määritetyllä Bitcoin -osoitteella</translation>
    
YES, The Finnish translation uses the singular "osoitteella" (address) when the English source uses the plural "addresses". Additionally, there is an unnecessary space before the hyphen in "Bitcoin -osoitteella".

Correct translation: Varmista, että viestisi on allekirjoitettu määritetyillä Bitcoin-osoitteilla
```

```
        <source>Syncing Headers (%1%)…</source>
        <translation>Synkronoi järjestysnumeroita (%1%)...</translation>
    
YES, The translation is problematic because "järjestysnumeroita" translates to "sequence numbers" which is not relevant in the context of Bitcoin. The correct translation for "Headers" in this context is "otsikkotiedot".
Synkronoidaan otsikkotiedot (%1%)...
```

```
        <source>Catching up…</source>
        <translation>Jäljellä...</translation>
    
YES, the translation is inaccurate and problematic. The Finnish word "Jäljellä" means "remaining" or "left", which does not accurately convey the meaning of "Catching up" in this context.

A more appropriate translation for "Catching up…" in the context of Bitcoin, implying a process of synchronizing or updating, would be:

"Synkronoidaan…" or "Päivitetään…"

Therefore, the corrected translation is:

<translation>Synkronoidaan…</translation>
```

```
        <source>Last received block was generated %1 ago.</source>
        <translation>Viimeisin vastaanotettu lohko tuotettu %1.</translation>
    
YES: The translation is missing the temporal unit for the time difference.
Viimeisin vastaanotettu lohko tuotettiin %1 sitten.
```

```
        <source>Lock unspent</source>
        <translation>Lkitse käyttämättömät</translation>
    
YES, The translation is not accurate. The Finnish word "Lkitse" is not a valid Finnish word. It should be "Lukitse" which means "Lock".
Lukitse käyttämättömät
```

```
        <source>Unlock unspent</source>
        <translation>Avaa käyttämättömien lukitus</translation>
    
YES
The translation is awkward and ungrammatical in Finnish. "Avaa käyttämättömien lukitus" literally translates to "Unlock of the unused's lock" which doesn't make sense. The term "unspent" in the context of Bitcoin refers to unspent transaction outputs (UTXOs). A more natural and accurate translation would be "Avaa käyttämättömät" which translates to "Unlock the unspent ones" or "Unlock unspent".

Correct translation: Avaa käyttämättömät
```

```
        <source>Copy fee</source>
        <translation>Kopioi rahansiirtokulu</translation>
    
YES, the translation is problematic because it is inaccurate. The Finnish translation "Kopioi rahansiirtokulu" translates to "Copy transfer fee" which is not what "Copy fee" means in the context of Bitcoin. "Copy fee" in this context likely refers to copying a transaction fee. A more accurate translation would be "Kopioi palkkio" or "Kopioi siirtomaksu".

Kopioi palkkio
```

```
        <source>Copy after fee</source>
        <translation>Kopioi rahansiirtokulun jälkeen</translation>
    
YES, The translation is problematic because it mistranslates "fee" as "rahansiirtokulu" (transfer fee), whereas "fee" in this context refers to a transaction fee.

The correct translation should be:
Kopioi maksun jälkeen
```

```
        <source>change from %1 (%2)</source>
        <translation>Vaihda %1 (%2)</translation>
    
YES, The translation is problematic because it uses the wrong word for "change". The Finnish word for "change" in this context should be "vaihtoraha" or "vaihto" instead of "vaihda".
The correct translation is: Vaihtoraha %1 (%2)
```

```
        <source>Encrypt the wallet. The wallet will be encrypted with a passphrase of your choice.</source>
        <translation>Salaa lompakko. Lompakko salataan valitsemallasa salasanalla.</translation>
    
YES - The Finnish word "valitsemallasa" is a misspelling. The correct word is "valitsemallasi".
NO
```

```
        <source>Welcome to %1.</source>
        <translation>Tervetuloa %1 pariin.</translation>
    
YES, The translation is inaccurate. The phrase "pariin" means "in pairs" or "with a couple", which does not fit the context of "Welcome to %1.". The correct translation should be "Tervetuloa %1!".
NO
```

```
        <source>Unknown. Syncing Headers (%1, %2%)…</source>
        <translation>Tuntematon. Synkronoidaan järjestysnumeroita (%1,%2%)...</translation>
    
YES, The translation erroneously translates "Headers" to "järjestysnumeroita" (sequence numbers) which is not accurate in the context of Bitcoin. In Bitcoin, "headers" refers to block headers.

The correct translation for "Headers" in this context would be "lohkojen otsikoita" or simply "otsikoita".

Correct translation:
Tuntematon. Synkronoidaan otsikoita (%1, %2 %)…
```

```
        <source>If you disable the spending of unconfirmed change, the change from a transaction cannot be used until that transaction has at least one confirmation. This also affects how your balance is computed.</source>
        <translation>Jos poistat varmistamattomien vaihtorahojen käytön, ei siirtojen vaihtorahaa ei voida käyttää ennen vähintään yhtä varmistusta. Tämä vaikuttaa myös taseesi lasketaan.</translation>
    
YES: The translation contains a grammatical error and awkward phrasing. The phrase "ei siirtojen vaihtorahaa ei voida käyttää" has a double negative and is grammatically incorrect. The phrase "taseesi lasketaan" is also slightly awkward.

Correct translation: Jos poistat varmistamattomien vaihtorahojen käytön, vaihto-osuutta ei voida käyttää ennen kuin kyseisellä siirrolla on vähintään yksi varmistus. Tämä vaikuttaa myös taseesi laskentaan.
```

```
        <source>Used for reaching peers via:</source>
        <translation>Vertaisten saavuttamiseen käytettävät verkkotyypit:</translation>
    
YES: The translation is inaccurate. The Finnish text implies "types of networks used for reaching peers", whereas the English text is asking "Used for reaching peers via:". The Finnish translation is also grammatically awkward and does not make much sense in the given context.

Correct translation: Vertaisten tavoittamiseen käytettävät tavat:
```

```
        <source>Current settings will be backed up at "%1".</source>
        <extracomment>Text explaining to the user that the client's current settings will be backed up at a specific location. %1 is a stand-in argument for the backup location's path.</extracomment>
        <translation>Nykyiset asetukset varmuuskopioidaan klo"%1"</translation>
    
YES - The word "klo" in Finnish means "around" or "at approximately", which is not the correct preposition to use in this context. The correct translation would be "osoitteeseen" which means "to the address".
Nykyiset asetukset varmuuskopioidaan osoitteeseen "%1".
```

```
        <source>Could not read setting "%1", %2.</source>
        <translation>Ei voinut luke asetusta "%1", %2.</translation>
    
YES - The Finnish translation has a grammatical error. The verb "lukea" (to read) should be in the infinitive form "lukea" and not "luke".
Correct translation: Ei voinut lukea asetusta "%1", %2.
```

```
        <source>PSBT saved to disk.</source>
        <translation>PSBT (osittain tallennettu bitcoin-siirto) tallennettiin levylle.</translation>
    
YES - The translation is problematic because "osittain tallennettu bitcoin-siirto" is a literal translation of PSBT which does not make sense in Finnish. The correct translation should be simply "PSBT".

PSBT saved to disk.
```

```
        <source>User Agent</source>
        <extracomment>Title of Peers Table column which contains the peer's User Agent string.</extracomment>
        <translation>Käyttöliittymä</translation>
    
YES, The Finnish translation "Käyttöliittymä" means "User Interface" which is not accurate in this context. The correct translation for "User Agent" would be "Käyttäjäagentti".
Käyttäjäagentti
```

```
        <source>Transaction Relay</source>
        <translation>Siirtokulu</translation>
    
YES, The translation is incorrect. "Siirtokulu" means "transfer fee" or "transaction cost", not "Transaction Relay". The correct translation for "Transaction Relay" in the context of Bitcoin is "Siirtoprosessi".

NO.
```

```
        <source>we selected the peer for high bandwidth relay</source>
        <translation>valitsimme korkean kaistanleveyden releen vertaislaitteen</translation>
    
YES, the translation is problematic. The word "releen" (relay's) modifies "vertaislaitteen" (peer device) in a way that doesn't accurately convey the meaning of the source text. In the context of Bitcoin, "peer" refers to another node in the network, not necessarily a "device" in the typical sense. Also, "high bandwidth relay" should ideally be translated as a concept applied to the peer, rather than a device that *is* a high bandwidth relay.

A more accurate translation would be:

valitsimme korkean kaistanleveyden välitykseen tarkoitetun vertaislaitteen
```

```
        <source>Ctrl+=</source>
        <extracomment>Secondary shortcut to increase the RPC console font size.</extracomment>
        <translation>Ctrl+-</translation>
    
YES - The translation is incorrect. The source states "+=" which should be translated to "+=". The translation provides "-".
Ctrl+=
```

```
        <source>1 day</source>
        <translation>1 pivä</translation>
    
YES, the translation of "day" to "pivä" is incorrect. The correct Finnish word for "day" is "päivä".
1 päivä
```

```
        <source>Executing command without any wallet</source>
        <translation>Suoritetaan komento ilman lomakkoa</translation>
    
YES
The translation uses the Finnish word "lomakkoa" which means "form" or "template". This is incorrect in the context of Bitcoin, where "wallet" refers to a digital wallet used to store and manage cryptocurrencies. The correct translation for "wallet" in this context is "lompakkoa".

Suoritetaan komento ilman lompakkoa
```

```
        <source>Ban for</source>
        <translation>Estä</translation>
    
YES, The translation is incorrect. The Finnish word "Estä" means "block" or "prevent", which is not the intended meaning of "Ban" in this context. The correct translation for "Ban for" in the context of Bitcoin would be "Estä käyttäjä" (Ban user) or "Porttikielto" (Ban) depending on the specific nuance. Assuming the context implies banning a user or entity, a more appropriate translation would be:
Estä
```

```
        <source>Generates a native segwit address (BIP-173). Some old wallets don't support it.</source>
        <translation> 
Luo natiivin segwit-osoitteen (BIP-173). Jotkin vanhat lompakot eivät tue sitä.</translation>
    
YES, There is a leading space in the translation.
Luo natiivin segwit-osoitteen (BIP-173). Jotkin vanhat lompakot eivät tue sitä.
```

```
        <source>Request payment to …</source>
        <translation>Pyydä maksua ooitteeseen ...</translation>
    
YES, The Finnish translation of "Request payment to …" is "Pyydä maksua ooitteeseen ...". The word "ooitteeseen" is a misspelling of "osoitteeseen", which means "address". The correct translation should be "Pyydä maksua osoitteeseen ...".
```

```
        <source>Hide transaction fee settings</source>
        <translation> Piilota siirtomaksuasetukset</translation>
    
YES
The translation has an unnecessary leading space.
Hide transaction fee settings
```

```
        <source>Copy fee</source>
        <translation>Kopioi rahansiirtokulu</translation>
    
YES, the translation is problematic because it is inaccurate. The Finnish translation "Kopioi rahansiirtokulu" translates to "Copy transfer fee" which is not what "Copy fee" means in the context of Bitcoin. "Copy fee" in this context likely refers to copying a transaction fee. A more accurate translation would be "Kopioi palkkio" or "Kopioi siirtomaksu".

Kopioi palkkio
```

```
        <source>Copy after fee</source>
        <translation>Kopioi rahansiirtokulun jälkeen</translation>
    
YES, The translation is problematic because it mistranslates "fee" as "rahansiirtokulu" (transfer fee), whereas "fee" in this context refers to a transaction fee.

The correct translation should be:
Kopioi maksun jälkeen
```

```
        <source>Creates a Partially Signed Bitcoin Transaction (PSBT) for use with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <translation>Luo osittain allekirjoitetun bitcoin-siirtotapahtuman (PSBT) käytettäväksi mm. offline %1 lompakko tai PSBT-yhteensopiva hardware-lompakko.</translation>
    
YES - The translation is missing a comma after "lompakko" and has an extra space before "tai".
Luo osittain allekirjoitetun bitcoin-siirtotapahtuman (PSBT) käytettäväksi mm. offline %1-lompakko tai PSBT-yhteensopiva hardware-lompakko.
```

```
        <source>You can increase the fee later (signals Replace-By-Fee, BIP-125).</source>
        <translation>Voit korottaa palkkiota myöhemmin (osoittaa Replace-By-Fee:tä, BIP-125).</translation>
    
YES: The Finnish word "osoittaa" (shows/points) is not the correct translation for "signals" in this context. The correct word would be "signaaloi" or "käyttää signaalina".

Corrected translation: Voit korottaa palkkiota myöhemmin (käyttää signaalina Replace-By-Fee:tä, BIP-125).
```

```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>Ei signalointia Korvattavissa korkeammalla kululla, BIP-125.</translation>
    
YES: The translation of "Replace-By-Fee" as "Korvattavissa korkeammalla kululla" is inaccurate and doesn't convey the intended meaning of BIP-125 in the context of Bitcoin. BIP-125 allows for a transaction to be replaced by another transaction with a higher fee. A more accurate translation would be "Ei signaalia korvaamisesta maksulla, BIP-125."
NO: Ei signaalia korvaamisesta maksulla, BIP-125.
```

```
        <source>A fee higher than %1 is considered an absurdly high fee.</source>
        <translation>%1:tä ja korkeampaa siirtokulua pidetään mielettömän korkeana.</translation>
    
YES: The translation incorrectly translates "fee" as "siirtokulua" (transfer cost), which is a more general term and less specific to Bitcoin transaction fees. It also adds an unnecessary colon after %1.

Correct translation: %1:tä ja korkeampaa transaktiokulua pidetään mielettömän korkeana.
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/vahvistamaton</translation>
    
YES, The translation is incorrect. "vahvistamaton" means "unconfirmed", but the context indicates the transaction is confirmed in at least one block. A more accurate translation would be "%1/vähän vahvistettu" which translates to "%1/little confirmed".
%1/vähän vahvistettu
```

```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>Varmistetaan (%1 suositellusta %2 varmistuksesta)</translation>
    
YES, The translation is problematic because it incorrectly translates "1 of 2 recommended confirmations" as "1 of 2 recommended confirmations" when it should be "1 of 2 recommended confirmations".
Correct translation: Varmistetaan (%1 / %2 suositeltua varmistusta)
```

```
        <source>Transaction status. Hover over this field to show number of confirmations.</source>
        <translation>Rahansiirron tila. Siirrä osoitin kentän päälle nähdäksesi vahvistusten lukumäärä.</translation>
    
YES, The translation is problematic as it incorrectly translates "Transaction status" as "Rahansiirron tila" which means "Money transfer status", and "address" as "osoitin" which means "pointer". It also uses "Siirrä osoitin kentän päälle nähdäksesi vahvistusten lukumäärä." which means "Move the pointer over the field to see the number of confirmations." instead of "Siirrä osoitin kentän päälle nähdäksesi vahvistusten määrä."
The correct translation should be: "Siirron tila. Vie hiiri kentän päälle nähdäksesi vahvistusten määrä."
```

```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Onko rahansiirrossa mukana ainoastaan seurattava osoite vai ei.</translation>
    
YES, the translation is problematic. The Finnish translation does not accurately convey the meaning of "watch-only address". The phrase "ainoastaan seurattava osoite" translates to "only trackable address" or "only monitored address", which is not the intended meaning of "watch-only address" in the context of Bitcoin. A watch-only address is an address that can be monitored but cannot be used to send funds.

A more accurate translation would be: "Onko tässä siirrossa mukana vain tarkkailuun tarkoitettu osoite."

However, even this translation is a bit literal and could be improved for naturalness in Finnish. A better translation considering the context of Bitcoin would be: "Sisältääkö tämä rahansiirto vain tarkkailuun sallitun osoitteen." or more simply "Onko tämä rahansiirto vain seurattava osoite."

Given the options, I will go with the most direct correction of the original problematic phrase:

YES, Sisältääkö tämä rahansiirto vain tarkkailuun sallitun osoitteen.
```

```
        <source>Copy full transaction details</source>
        <translation>Kopioi koko tapahtuma  tiedot</translation>
    
YES, The translation has a double space between "tapahtuma" and "tiedot".
Kopioi koko tapahtumatiedot
```

```
        <source>Edit address label</source>
        <translation>Muokkaa osoitekenttää</translation>
    
YES - The Finnish translation is inaccurate. "Osoitekenttää" means "address field" rather than "address label". The correct translation should be "Muokkaa osoitetarraa".
Muokkaa osoitetarraa
```

```
        <source>Partially Signed Transaction (*.psbt)</source>
        <translation>Osittain allekirjoitettu siirto (*.pbst)</translation>
    
YES, the translation contains an erroneous character in the file extension.
The correct translation for the file extension should be "*.psbt".

Corrected translation: Osittain allekirjoitettu siirto (*.psbt)
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>PBST-tiedoston tulee olla pienempi kuin 100 mebitavua</translation>
    
YES - The translation incorrectly translates "PSBT" to "PBST". The correct translation should be "PSBT-tiedoston tulee olla pienempi kuin 100 MiB".
```

```
        <source>Increase:</source>
        <translation>Korota:</translation>
    
YES, The translation is incorrect. The Finnish word "Korota" means "Increase" or "raise" but in the context of Bitcoin, "Lisää" or "Kasvata" would be a more appropriate translation for "Increase".
The correct translation is:
        <source>Increase:</source>
        <translation>Lisää:</translation>
```

```
        <source>Warning: This may pay the additional fee by reducing change outputs or adding inputs, when necessary. It may add a new change output if one does not already exist. These changes may potentially leak privacy.</source>
        <translation> 
Varoitus: Tämä voi maksaa ylimääräisen maksun vähentämällä vaihtotuloja tai lisäämällä tuloja tarvittaessa. Se voi lisätä uuden vaihtotulojen, jos sellaista ei jo ole. Nämä muutokset voivat mahdollisesti vuotaa yksityisyyttä.</translation>
    
YES: The translation incorrectly uses "vaihtotuloja" (revenue/income) instead of "vaihtosummia" (change amounts). The word "tuloja" also incorrectly translates "outputs".

Varoitus: Tämä voi maksaa ylimääräisen maksun vähentämällä vaihtosummia tai lisäämällä syötteitä tarvittaessa. Se voi lisätä uuden vaihtosumin, jos sellaista ei jo ole. Nämä muutokset voivat mahdollisesti vuotaa yksityisyyttä.
```

```
        <source>Signer error</source>
        <translation>Signaalivirhe</translation>
    
YES, The translation "Signaalivirhe" means "Signal error". The correct translation for "Signer error" in Finnish, in the context of Bitcoin, would be "Allekirjoittajan virhe".

NO
```

```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>%s virheellinen -assumeutxo-snapshot-tila. Tämä viittaa laitteistoon liittyvään ongelmaan, ohjelmistovirheeseen tai huonoon ohjelmistomuutokseen, joka on sallinut virheellisen snapshotin lataamisen. Tämän seurauksena solmu sulkeutuu ja lopettaa kaiken sen tilan käytön, joka perustui snapshottiin, ja nollaa lohkokorkeuden%darvoon%d. Seuraavassa uudelleenkäynnistyksessä solmu jatkaa synkronointia kohdasta%d  
ilman, että käytetään mitään snapshot-tietoja. Ilmoita tästä tapauksesta osoitteeseen%s, mukaan lukien se, miten sait snapshotin. Virheellinen snapshot-tilatiedosto jätetään levylle, jos se on hyödyllinen ongelman diagnosoinnissa, joka aiheutti tämän virheen.</translation>
    
YES: The format specifiers %d are not correctly carried over. There are missing spaces before the format specifiers.

%s virheellinen -assumeutxo-snapshot-tila. Tämä viittaa laitteistoon liittyvään ongelmaan, ohjelmistovirheeseen tai huonoon ohjelmistomuutokseen, joka on sallinut virheellisen snapshotin lataamisen. Tämän seurauksena solmu sulkeutuu ja lopettaa kaiken sen tilan käytön, joka perustui snapshottiin, ja nollaa lohkoketjun korkeuden %d:stä %d:hen. Seuraavassa uudelleenkäynnistyksessä solmu jatkaa synkronointia kohdasta %d ilman, että käytetään mitään snapshot-tietoja. Ilmoita tästä tapauksesta osoitteeseen %s, mukaan lukien se, miten sait snapshotin. Virheellinen snapshot-ketjutila jätetään levylle, jos se on hyödyllinen ongelman diagnosoinnissa, joka aiheutti tämän virheen.
```

```
        <source>Prune configured below the minimum of %d MiB.  Please use a higher number.</source>
        <translation>Karsinta konfiguroitu alle minimin %d MiB. Käytä surempaa numeroa.</translation>
    
YES, the word "surempaa" should be "suurempaa".
Karsinta konfiguroitu alle minimin %d MiB. Käytä suurempaa numeroa.
```

```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of pruned node)</source>
        <translation>Karsinta: viime lompakon synkronisointi menee karsitun datan taakse. Sinun tarvitsee ajaa -reindex (lataa koko lohkoketju uudelleen tapauksessa jossa karsiva noodi)</translation>
    
YES - The Finnish translation is grammatically incorrect and incomplete. The phrase "menee karsitun datan taakse" is awkward and doesn't accurately convey the meaning of "goes beyond pruned data." Additionally, the sentence ends abruptly with "tapauksessa jossa karsiva noodi."

Correct translation: Karsinta: viimeisin lompakon synkronisointi ulottuu karsitun datan ulkopuolelle. Sinun täytyy ajaa `-reindex` (lataa koko lohkoketju uudelleen karsivassa solmussa).
```

```
        <source>Unable to replay blocks. You will need to rebuild the database using -reindex-chainstate.</source>
        <translation>Lohkoja ei voida uudelleenlukea. Joulut uudelleenrakentamaan tietokannan käyttämällä -reindex-chainstate -valitsinta.</translation>
    
YES, the translation contains erroneous content. The word "Joulut" (Christmases) is incorrect and should be "Lohkot" (blocks) to match the context of rebuilding the database.

NO
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Varoitus: lompakosta {%s} tunnistetut yksityiset avaimet, on poistettu käytöstä</translation>
    
YES: The Finnish translation incorrectly states that the private keys are "poistettu käytöstä" (disabled/removed from use), when the English text implies that the wallet has disabled the *functionality* of displaying or using private keys, but the keys themselves were detected. The original English implies a warning that private keys are present in a wallet that has had its private key functionality disabled.

Correct translation: "Varoitus: Yksityisavaimia havaittu lompakosta {%s}, jossa yksityisavaimet on poistettu käytöstä"
```

```
        <source>
Unable to restore backup of wallet.</source>
        <translation>
Ei voinut palauttaa lompakon varmuuskopiota..</translation>
    
YES, The translation has an extra period at the end of the sentence.
Ei voinut palauttaa lompakon varmuuskopiota.
```

```
        <source>Error reading configuration file: %s</source>
        <translation>Virhe luettaessa asetustiedostoa 1%s</translation>
    
YES: The format specifier "%s" in the source text is incorrectly translated to "1%s" in the translation. The "1" before the percent sign is erroneous.
Virhe luettaessa asetustiedostoa: %s
```

```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>Virhe: Avainallas tyhjentyi, ole hyvä ja kutsu keypoolrefill ensin</translation>
    
YES
The word "Avainallas" is likely a typo and should be "Avainpool".
Virhe: Avainpool tyhjentyi, ole hyvä ja kutsu keypoolrefill ensin
```

```
        <source>Not solvable pre-selected input %s</source>
        <translation>Ei ratkaistavissa esivalittu tulo%s</translation>
    
YES
The word "tulo" means income, which is not the correct meaning of "input" in the context of Bitcoin transactions. The correct translation for "input" in this context is "syöte".

Ei ratkaistavissa esivalittu syöte %s
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>Lähetyksen siirtosumman tulee olla positiivinen</translation>
    
YES, The original Finnish text states that the transaction amount should be positive. However, the English text states that transaction amounts must not be negative. There is a slight difference between not being negative and being positive. A zero value is not negative, but it is also not positive.
A more accurate translation would be:
Lähetyssumma ei saa olla negatiivinen
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>Tapahtuma vaatii osoitteenmuutoksen, mutta emme voi luoda sitä.</translation>
    
YES - The translation is too literal and does not convey the intended meaning. "Osoitteenmuutos" means changing an address, not a change address for a transaction. The correct translation should reflect the concept of a "change address" in the context of Bitcoin transactions.

NO - Transaction needs a change address, but we can't generate it.
YES - Tapahtuma vaatii vaihtoehtoisen osoitteen, mutta emme voi luoda sitä.
```

```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>hyväksyttyjä ilmaisia ​​arvioita ei tueta %s ketju.</translation>
    
YES, The translation has a significant meaning error. "acceptstalefeeestimates" should be translated as "acceptstalefeeestimates" or a close functional equivalent. "hyväksyttyjä ilmaisia ​​arvioita" translates to "accepted free estimates", which is completely different and nonsensical in the context of Bitcoin.

NO
```
</details>
