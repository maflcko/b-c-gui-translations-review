# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>fi</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bfi%5D%20low%20quality)


<!-- cache_translation_check_fi_849826846a4e498b80089947afb083769ea98ba81d38ab65a280feed1b4e27b9 -->
```
        <source>Passphrase Dialog</source>
        <translation>Tunnuslauseen tekstinsyöttökenttä</translation>
    
ERR
The translation "Tunnuslauseen tekstinsyöttökenttä" means "passphrase text input field", which is more specific than "Passphrase Dialog". The original refers to a dialog window, not specifically the input field.

Correct translation:
Tunnuslauseen valintaikkuna
```

<!-- cache_translation_check_fi_a71705b4bfadbe432c42cb12baef780cd3dbde3315dc76051a0ae7dbb784b400 -->
```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>Lohko Rele</translation>
    
ERR
The translation "Lohko Rele" is not idiomatic Finnish; the compound words are not joined, and "rele" usually means a physical relay component, not an information relay. The correct and commonly used translation for "Block Relay" in this context would be "Lohkovälitys" or "Lohkojen välitys".

Correct translation:
Lohkovälitys
```

<!-- cache_translation_check_fi_ed3549d0a584149a23579a57a9e737676d551041aebfd384ae6218f537540536 -->
```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>Tunturi</translation>
    
ERR
The Finnish word "Tunturi" means "fell" (a type of mountain/hill) and is not appropriate here. The source term "Feeler" refers to a probing connection, someone who "feels out" or tests. 
A better translation would be:
Kokeilija

Correct translation:
Kokeilija
```

<!-- cache_translation_check_fi_cedce37e83cf1b722bbfee1d98ec7f3c384d9d0c0f3e7bbb745fb9d9fc5e2283 -->
```
        <source>Network activity disabled.</source>
        <extracomment>A substring of the tooltip.</extracomment>
        <translation>Verkkoyhteysmittari pois käytöstä</translation>
    
ERR
The translation "Verkkoyhteysmittari pois käytöstä" means "Network connection meter disabled", which is not accurate for the source "Network activity disabled." The correct translation should refer to the network activity itself, not a connection meter.

Correct translation:
Verkkoliikenne poistettu käytöstä.
```

<!-- cache_translation_check_fi_da6d96525a4d23ead0caa59d733c76b054afbba870b7cd88dd07c2f205a73cc6 -->
```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Varmista, että viestisi on allekirjoitettu määritetyllä Bitcoin -osoitteella</translation>
    
ERR
The translation has minor issues:
1. The English original talks about verifying "messages" (plural), but the translation uses the singular "viestisi" (your message). This changes the meaning.
2. There is a space before the hyphen in "Bitcoin -osoitteella", which is nonstandard in Finnish. It should be "Bitcoin-osoitteella" with no space.

Correct translation:
Varmenna viestit varmistaaksesi, että ne on allekirjoitettu määritetyillä Bitcoin-osoitteilla
```

<!-- cache_translation_check_fi_cb10df7b964f4b54a0340170366e01c21424c3898c4fc1082b4a0c788e38d9a6 -->
```
        <source>Syncing Headers (%1%)…</source>
        <translation>Synkronoi järjestysnumeroita (%1%)...</translation>
    
ERR
The translation is inaccurate. "Headers" in the context of Bitcoin refers to "lohkopäät" or "lohkotunnisteet", not "järjestysnumeroita" ("sequence numbers"). Also, the ellipsis should be the same Unicode character as the source. The format specifier %1% should be just %1 as in the source.

Correct translation:
Synkronoidaan lohkopäitä (%1)…
```

<!-- cache_translation_check_fi_c8e7519d0b8028169b681456e9c18fb6a9fbeb10665481fb5f50d74d13db7602 -->
```
        <source>Catching up…</source>
        <translation>Jäljellä...</translation>
    
ERR
The translation is inaccurate. "Jäljellä..." means "remaining..." or "left...", which does not convey the meaning of "Catching up…", typically shown when synchronizing with the blockchain. A better translation would be:

Correct translation:
Otetaan kiinni…
or
Synkronoidaan…
```

<!-- cache_translation_check_fi_b50e5ece8d698b6a2821d7306183beef085559231b58687d954da5db080241d2 -->
```
        <source>Last received block was generated %1 ago.</source>
        <translation>Viimeisin vastaanotettu lohko tuotettu %1.</translation>
    
ERR  
The translation drops "ago" and the passive verb, making it less clear and incorrect in Finnish. Also, "tuotettu" is less standard than "luotiin" in this context.

Correct translation:  
Viimeisin vastaanotettu lohko luotiin %1 sitten.
```

<!-- cache_translation_check_fi_00e17c16f484be620544253d1cd66b05bba892f0f720950227ff94530831adfd -->
```
        <source>Lock unspent</source>
        <translation>Lkitse käyttämättömät</translation>
    
ERR
There is a typographical error in the Finnish translation: "Lkitse" should be "Lukitse".

Correct translation:
Lukitse käyttämättömät
```

<!-- cache_translation_check_fi_aa238153c1353ed74fcbd3dfba3ec60800913898bcd09b081d2055a79ae2481a -->
```
        <source>Unlock unspent</source>
        <translation>Avaa käyttämättömien lukitus</translation>
    
ERR
The translation "Avaa käyttämättömien lukitus" is not fully accurate. The phrase "Unlock unspent" refers to unlocking unspent transaction outputs (UTXOs), and the correct Finnish translation should more directly match the English imperative and subject.

Correct translation:
Avaa käyttämättömät
```

<!-- cache_translation_check_fi_67f02a4a393dfba3c40d4f2fa458317eb12aafc51187907081eb85695db16864 -->
```
        <source>change from %1 (%2)</source>
        <translation>Vaihda %1 (%2)</translation>
    
ERR
The translation is inaccurate. The English phrase "change from %1 (%2)" (in the context of Bitcoin, "change" refers to the returned amount from a transaction) should be translated to retain this meaning, not as an imperative "Vaihda" ("Change [something]"). The correct Finnish term for "change" in this financial/Bitcoin sense is "vaihtoraha".

Correct translation:
Vaihtoraha %1 (%2)
```

<!-- cache_translation_check_fi_b8e1cb78c85c3e1be1de23db3a1ee3a59f9c7b867a101ae1c6da81e0885b385c -->
```
        <source>Encrypt the wallet. The wallet will be encrypted with a passphrase of your choice.</source>
        <translation>Salaa lompakko. Lompakko salataan valitsemallasa salasanalla.</translation>
    
ERR
There is a small spelling error in the translation: "valitsemallasa" should be "valitsemallasi". The "sa" ending is a typo; the correct form is "si" for "your" (possessive).

Correct translation:
Salaa lompakko. Lompakko salataan valitsemallasi salasanalla.
```

<!-- cache_translation_check_fi_21a51bc21c14abf20def0c91e3e0fd7784899e136cd653df47adf8cb0d91c8db -->
```
        <source>Unknown. Syncing Headers (%1, %2%)…</source>
        <translation>Tuntematon. Synkronoidaan järjestysnumeroita (%1,%2%)...</translation>
    
ERR
The Finnish translation uses "järjestysnumeroita" (ordinal numbers) instead of "lohkojen otsikoita" (block headers), which is the correct term in the context of Bitcoin. Also, a space is missing after the comma in numbers (%1,%2%).

Correct translation:
Tuntematon. Synkronoidaan lohkojen otsikoita (%1, %2%)...
```

<!-- cache_translation_check_fi_c2fa13570715ae441b9192455a8677941fe8a40d7778a97766178449577e4df2 -->
```
        <source>If you disable the spending of unconfirmed change, the change from a transaction cannot be used until that transaction has at least one confirmation. This also affects how your balance is computed.</source>
        <translation>Jos poistat varmistamattomien vaihtorahojen käytön, ei siirtojen vaihtorahaa ei voida käyttää ennen vähintään yhtä varmistusta. Tämä vaikuttaa myös taseesi lasketaan.</translation>
    
ERR
The translation has multiple grammar issues and awkward phrasing in Finnish. "Tämä vaikuttaa myös taseesi lasketaan" is ungrammatical, and parts of the translation do not flow naturally. Also, "taseesi" does not match the way "your balance" should be expressed in this context ("saldosi" is preferable). 

Correct translation:
Jos poistat käytöstä vahvistamattoman vaihtorahan käyttämisen, ei siirrosta saatua vaihtorahaa voi käyttää ennen kuin siirrolla on vähintään yksi vahvistus. Tämä vaikuttaa myös siihen, miten saldosi lasketaan.
```

<!-- cache_translation_check_fi_619eb6a9cfdeb5c1677fc0734218defb8fef76b488dc4728b270b8a8231c23c4 -->
```
        <source>Current settings will be backed up at "%1".</source>
        <extracomment>Text explaining to the user that the client's current settings will be backed up at a specific location. %1 is a stand-in argument for the backup location's path.</extracomment>
        <translation>Nykyiset asetukset varmuuskopioidaan klo"%1"</translation>
    
ERR
There is a formatting issue: in Finnish, "klo" means "at" in the context of time (e.g., "at 10 o'clock"), but here we are talking about a file path/location, not a time. Also, there is a missing space before the quotation mark, and the wording is somewhat clumsy.

Correct translation:
Nykyiset asetukset varmuuskopioidaan sijaintiin "%1".
```

<!-- cache_translation_check_fi_10a8b4879801ff2c064b24ee1d4f55e34f48532bbbae33e73d61ba555e4b0afb -->
```
        <source>Could not read setting "%1", %2.</source>
        <translation>Ei voinut luke asetusta "%1", %2.</translation>
    
ERR
There is a typographical error: "luke" should be "lukea" (the infinitive form). Also, "asetusta" should be "asetusta" (the partitive case), which is correct, but more common would be "asetusta" in this context.

Correct translation:
Ei voitu lukea asetusta "%1", %2.
```

<!-- cache_translation_check_fi_f8f1bdc3b68d8eea3bcbf8ec4708d3d7a93f26cd7ee178dc2f71d5eb3d2db63d -->
```
        <source>PSBT saved to disk.</source>
        <translation>PSBT (osittain tallennettu bitcoin-siirto) tallennettiin levylle.</translation>
    
ERR
The translation expands "PSBT" into "osittain tallennettu bitcoin-siirto", which is not accurate—PSBT stands for "Partially Signed Bitcoin Transaction" ("osittain allekirjoitettu bitcoin-siirto" in Finnish). Furthermore, the source does not expand the abbreviation, so the translation should keep "PSBT" and should match the brevity of the source.

Correct translation:
PSBT tallennettu levylle.
```

<!-- cache_translation_check_fi_1f9e548aca6d7edad3c095cf5d8c19b050be909d1935ca0c70667aa974cf4c87 -->
```
        <source>User Agent</source>
        <extracomment>Title of Peers Table column which contains the peer's User Agent string.</extracomment>
        <translation>Käyttöliittymä</translation>
    
ERR
The translation is inaccurate. "Käyttöliittymä" means "user interface", not "user agent". The correct translation for "User Agent" in Finnish is "Käyttäjäagentti".

Correct translation:
Käyttäjäagentti
```

<!-- cache_translation_check_fi_256b8041049fc7980409dfed02b6e865ba666247828de9d8a993f4ae7eab1089 -->
```
        <source>Transaction Relay</source>
        <translation>Siirtokulu</translation>
    
ERR
The translation is inaccurate. "Siirtokulu" means "transaction fee" in Finnish, not "Transaction Relay." The correct translation should refer to the process of relaying or forwarding transactions.

Correct translation:
Transaktion välitys

Alternatively:
Siirron välitys
```

<!-- cache_translation_check_fi_3379eb872174264ff5f19ebe1c8ba8da1fe5be38cb25d4820a054391fb7a1c28 -->
```
        <source>Ctrl+=</source>
        <extracomment>Secondary shortcut to increase the RPC console font size.</extracomment>
        <translation>Ctrl+-</translation>
    
ERR  
The translation is incorrect. The source denotes the "Ctrl+=" keyboard shortcut, but the translation changes it to "Ctrl+-", which would be interpreted as "minus", not "equals". The shortcut semantics are thus reversed.

Correct translation:
Ctrl+=
```

<!-- cache_translation_check_fi_34bb955939f8354b7a96d5efeba1314a258dfeda7cd30d84605ed2d2f4cf0c91 -->
```
        <source>1 day</source>
        <translation>1 pivä</translation>
    
ERR
There is a typographical error in the Finnish word: "pivä" should be "päivä".

Correct translation:
1 päivä
```

<!-- cache_translation_check_fi_7526e3e732d6e69a433ef99889ff1227f942964397cabafdcf6e805f3df0900d -->
```
        <source>Generates a native segwit address (BIP-173). Some old wallets don't support it.</source>
        <translation> 
Luo natiivin segwit-osoitteen (BIP-173). Jotkin vanhat lompakot eivät tue sitä.</translation>
    
ERR
There is a leading whitespace character (non-breaking space or newline) before the translation, which is a formatting issue. Otherwise, the translation is accurate.

Correct translation:
Luo natiivin segwit-osoitteen (BIP-173). Jotkin vanhat lompakot eivät tue sitä.
```

<!-- cache_translation_check_fi_7ff72da667825a14d0b4ddc92a441085ad6b12f01e8452550c108f1f44d8fb08 -->
```
        <source>Request payment to …</source>
        <translation>Pyydä maksua ooitteeseen ...</translation>
    
ERR
There is a spelling error in the Finnish word "ooitteeseen". It should be "osoitteeseen". Also, the ellipsis should be "…" (U+2026) rather than three periods, to match the source formatting. 

Correct translation:
Pyydä maksua osoitteeseen …
```

<!-- cache_translation_check_fi_491b96f06d64796107556cb02659af3f4b055b4d90518667461b18d3d2a8d048 -->
```
        <source>Hide transaction fee settings</source>
        <translation> Piilota siirtomaksuasetukset</translation>
    
ERR
There is an extra space at the beginning of the translation, causing a whitespace formatting issue.

Correct translation:
Piilota siirtomaksuasetukset
```

<!-- cache_translation_check_fi_671bd61f48b53aca31b2689725d0b603b1965e0b13ab6caa315fcccb29b487b8 -->
```
        <source>Creates a Partially Signed Bitcoin Transaction (PSBT) for use with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <translation>Luo osittain allekirjoitetun bitcoin-siirtotapahtuman (PSBT) käytettäväksi mm. offline %1 lompakko tai PSBT-yhteensopiva hardware-lompakko.</translation>
    
ERR
There is a grammatical problem in the translation: "käytettäväksi mm. offline %1 lompakko tai PSBT-yhteensopiva hardware-lompakko." should use the instructive or adessive case and proper plural form to cover both options ("lompakossa tai PSBT-yhteensopivassa laitteistolompakossa"). Also "hardware-lompakko" should be "laitteistolompakko". A more natural formulation would be:

Correct translation:
Luo osittain allekirjoitetun bitcoin-siirtotapahtuman (PSBT), jota voi käyttää esimerkiksi offline-%1-lompakossa tai PSBT-yhteensopivassa laitteistolompakossa.
```

<!-- cache_translation_check_fi_0603b29e9a3431e23bcf6336899f35301f9c83dc0bfbe83718224b8b95cf1d49 -->
```
        <source>A fee higher than %1 is considered an absurdly high fee.</source>
        <translation>%1:tä ja korkeampaa siirtokulua pidetään mielettömän korkeana.</translation>
    
ERR
The translation is mostly correct but could be improved for naturalness. The translation uses "%1:tä", which tries to reflect the partitive case, but the English "higher than %1" should directly translate as "suurempaa kuin %1". Also, "siirtokulua" is good, but "maksua" (fee) can also be used.

Correct translation:
Suurempaa kuin %1 maksua pidetään mielettömän korkeana.
```

<!-- cache_translation_check_fi_57e6a5030ea50bb0b6d3d423910a435b9c8462a203a5398dbda9e4de483623ec -->
```
        <source>Copy full transaction details</source>
        <translation>Kopioi koko tapahtuma  tiedot</translation>
    
ERR
There is an extra space between "tapahtuma" and "tiedot" that should not be there.

Correct translation:
Kopioi koko tapahtumatiedot
```

<!-- cache_translation_check_fi_a9f0db7d75dad85061afc88d0fe313a47e3f756cf80d57288e3b5138cfb49f3d -->
```
        <source>Edit address label</source>
        <translation>Muokkaa osoitekenttää</translation>
    
ERR
The translation "Muokkaa osoitekenttää" means "Edit the address field", which does not accurately reflect "Edit address label". It should refer to editing the label associated with the address, not the address field itself.

Correct translation:
Muokkaa osoitteen nimeä
```

<!-- cache_translation_check_fi_89317c19cf8fcb19599cd5dba1fbab17ef3d59080e8e9d01682d8496dd3a2941 -->
```
        <source>Partially Signed Transaction (*.psbt)</source>
        <translation>Osittain allekirjoitettu siirto (*.pbst)</translation>
    
ERR
There is an error in the filename extension; it should be '.psbt', not '.pbst'. Otherwise the translation is accurate.

Correct translation:
Osittain allekirjoitettu siirto (*.psbt)
```

<!-- cache_translation_check_fi_f7a2c2060d5ca3e3ac2cc452d3dcaab772cebddb29404f303c90355918c79ec0 -->
```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>PBST-tiedoston tulee olla pienempi kuin 100 mebitavua</translation>
    
ERR
There is a typo in the abbreviation: "PBST" should be "PSBT", to match the English source and Bitcoin context.

Correct translation:
PSBT-tiedoston tulee olla pienempi kuin 100 mebitavua
```

<!-- cache_translation_check_fi_24e967f0c43bbb10b8f57071719c2ef78acbf68d0d4c3134f751581940cefe6b -->
```
        <source>Warning: This may pay the additional fee by reducing change outputs or adding inputs, when necessary. It may add a new change output if one does not already exist. These changes may potentially leak privacy.</source>
        <translation> 
Varoitus: Tämä voi maksaa ylimääräisen maksun vähentämällä vaihtotuloja tai lisäämällä tuloja tarvittaessa. Se voi lisätä uuden vaihtotulojen, jos sellaista ei jo ole. Nämä muutokset voivat mahdollisesti vuotaa yksityisyyttä.</translation>
    
ERR
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

<!-- cache_translation_check_fi_b86fd0fb4d3a284ba472f840d39a32be2d75d69c21f2a61b88731db734310f51 -->
```
        <source>Signer error</source>
        <translation>Signaalivirhe</translation>
    
ERR
The translation "Signaalivirhe" is incorrect in this context. "Signaali" means "signal" in Finnish, but "Signer" here refers to a person or entity that signs (a message, transaction, etc.).

Correct translation:
Allekirjoittajan virhe
```

<!-- cache_translation_check_fi_cfe3ef9935bc9e81b8c025d2d2bd01ce7ba945dd0cc0a6418dd38a0703640010 -->
```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>%s virheellinen -assumeutxo-snapshot-tila. Tämä viittaa laitteistoon liittyvään ongelmaan, ohjelmistovirheeseen tai huonoon ohjelmistomuutokseen, joka on sallinut virheellisen snapshotin lataamisen. Tämän seurauksena solmu sulkeutuu ja lopettaa kaiken sen tilan käytön, joka perustui snapshottiin, ja nollaa lohkokorkeuden%darvoon%d. Seuraavassa uudelleenkäynnistyksessä solmu jatkaa synkronointia kohdasta%d  
ilman, että käytetään mitään snapshot-tietoja. Ilmoita tästä tapauksesta osoitteeseen%s, mukaan lukien se, miten sait snapshotin. Virheellinen snapshot-tilatiedosto jätetään levylle, jos se on hyödyllinen ongelman diagnosoinnissa, joka aiheutti tämän virheen.</translation>
    
ERR
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

<!-- cache_translation_check_fi_07062751fbedf02db840ee351cde1355d8c204c16380481d999b21b64862a6f4 -->
```
        <source>Prune configured below the minimum of %d MiB.  Please use a higher number.</source>
        <translation>Karsinta konfiguroitu alle minimin %d MiB. Käytä surempaa numeroa.</translation>
    
ERR
There is a typo in the word "suurempaa" ("surempaa" is incorrect), and the phrase "Käytä suurempaa numeroa" is slightly unnatural in Finnish ("numero" should be "arvoa" or "määrää"). Otherwise, format specifier is correct and no spacing or unwanted content issues.

Correct translation:
Karsinta on konfiguroitu alle minimin %d MiB. Käytä suurempaa arvoa.
```

<!-- cache_translation_check_fi_1fe8dae43277970c9ceec2bd1143b876a8dd5c5a9ccb408619411877bbc6d09d -->
```
        <source>Unable to replay blocks. You will need to rebuild the database using -reindex-chainstate.</source>
        <translation>Lohkoja ei voida uudelleenlukea. Joulut uudelleenrakentamaan tietokannan käyttämällä -reindex-chainstate -valitsinta.</translation>
    
ERR
There is a typographical error in the Finnish translation: "Joulut" should be "Joudut" (meaning "you will need to"). Additionally, the translation omits the hyphen before "reindex-chainstate" and has an extra space after it. The correct form is "-reindex-chainstate". Also, "uudelleenlukea" is acceptable, but "toistaa" (replay) would be more natural.

Correct translation:
Lohkoja ei voida toistaa. Joudut uudelleenrakentamaan tietokannan käyttämällä -reindex-chainstate-valitsinta.
```

<!-- cache_translation_check_fi_c7f9b9eb196a1b207b082a9e7de16089f324ee8b63bd92465ea1ac8063f2e5c3 -->
```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Varoitus: lompakosta {%s} tunnistetut yksityiset avaimet, on poistettu käytöstä</translation>
    
ERR
The Finnish translation is inaccurate and changes the meaning. It suggests the private keys were disabled, not that they were detected in a wallet with disabled private keys. Also, the placement of parts is awkward and "on poistettu käytöstä" refers to being disabled, not detected in a wallet with that property.

Correct translation:
Varoitus: Lompakosta {%s} havaittiin yksityisiä avaimia, vaikka yksityiset avaimet on poistettu käytöstä
```

<!-- cache_translation_check_fi_8db8f75063f4a7cd2982530ee7e8b080ac66fa0646adfb537d0c96b31dcf317b -->
```
        <source>
Unable to restore backup of wallet.</source>
        <translation>
Ei voinut palauttaa lompakon varmuuskopiota..</translation>
    
ERR
The translation contains an extra period at the end ("varmuuskopiota..") which is a typographical error. Also, there is unnecessary leading whitespace.

Correct translation:
Ei voitu palauttaa lompakon varmuuskopiota.
```

<!-- cache_translation_check_fi_e2c4e5fe64185d0faab67dc62e43a5827a320ef9193cada349726a51cbc49c5a -->
```
        <source>Error reading configuration file: %s</source>
        <translation>Virhe luettaessa asetustiedostoa 1%s</translation>
    
ERR
The format specifier '%s' is incorrectly rendered as '1%s' in the Finnish translation, which is erroneous. The correct translation should retain the '%s' format specifier exactly as in the source.

Correct translation:
Virhe luettaessa asetustiedostoa: %s
```

<!-- cache_translation_check_fi_76b92f02705329c9cf0951ba3ee5569dc36de94e2f88c2ee46f7eaf2f8f6dfae -->
```
        <source>Not solvable pre-selected input %s</source>
        <translation>Ei ratkaistavissa esivalittu tulo%s</translation>
    
ERR
The translation is mostly correct, but there is a minor spacing issue: there should be a space between 'tulo' and the format specifier '%s' to match the source formatting. 'Input' as 'tulo' is acceptable in this context, but sometimes 'syöte' could also be used depending on software context; however, 'tulo' is used in some Finnish Bitcoin translations.

Correct translation:
Ei ratkaistavissa esivalittu tulo %s
```

<!-- cache_translation_check_fi_eff042e006a5d1eae51a49550a4598a5a2f306c2a0f6f13d33e327ce3aeac2dc -->
```
        <source>Transaction amounts must not be negative</source>
        <translation>Lähetyksen siirtosumman tulee olla positiivinen</translation>
    
ERR
The translation changes the meaning of the source sentence. The English source says that transaction amounts must not be negative, while the Finnish translation says that the transaction amount "must be positive", which is not strictly the same (zero is allowed in "not negative", but not in "must be positive").

Correct translation:
Tapahtuman määrät eivät saa olla negatiivisia
```

<!-- cache_translation_check_fi_f2e6eaf39e599d9e00bc9bd1effb818519210d5a9c816703227d1b53da250a67 -->
```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>Tapahtuma vaatii osoitteenmuutoksen, mutta emme voi luoda sitä.</translation>
    
ERR
The translation "Tapahtuma vaatii osoitteenmuutoksen, mutta emme voi luoda sitä." is inaccurate. "Osoitteenmuutos" literally means "change of address" (like notifying of a new postal address), which is incorrect in the Bitcoin context. The English "change address" refers to a special Bitcoin address that receives the 'change' from a transaction.

Correct translation:
Tapahtuma tarvitsee vaihtorahan osoitteen, mutta emme voi luoda sitä.
```

<!-- cache_translation_check_fi_83a411f6224467227a724673dc4981ee9a03d24e5602911bd300fc4fd8eb3d74 -->
```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>hyväksyttyjä ilmaisia ​​arvioita ei tueta %s ketju.</translation>
    
ERR
The Finnish translation is incorrect in several ways:
- "hyväksyttyjä ilmaisia ​​arvioita" means "accepted free estimates," which completely mistranslates "acceptstalefeeestimates."
- The sentence structure is ungrammatical in Finnish.
- The word "chain" should correspond to "lohkaketju," "ketju," or be adapted in context.

Correct translation:
acceptstalefeeestimates-toimintoa ei tueta %s-ketjussa.
```
</details>

Number of issues: 42.
