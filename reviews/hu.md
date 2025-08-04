# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>hu</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bhu%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Ezek az Ön Bitcoin címei amelyeken fogadni tud Bitcoin utalásokat. Az "Új cím létrehozása" gombbal tud új címet létrehozni.
Aláírni csak régi típusú, egyessel kezdődő címekkel lehet.</translation>
    
YES - The translation incorrectly states that legacy addresses must start with a '1'. While many legacy addresses do start with a '1', this is not a strict requirement and some legacy addresses start with a '3'. The phrase "eggyel kezdődő" (starting with one) is the problematic part. A more accurate translation would be to simply state "legacy" addresses.

Correct translation: Ezek az Ön Bitcoin címei amelyeken fogadni tud Bitcoin utalásokat. Az "Új cím létrehozása" gombbal tud új címet létrehozni.
Aláírni csak régi típusú címekkel lehet.
```

```
        <source>Repeat new passphrase</source>
        <translation>Ismét az új jelmondat</translation>
    
YES - The Hungarian translation is grammatically incorrect and unnatural. "Ismét az új jelmondat" translates to "Again the new passphrase," which doesn't convey the intended meaning of repeating a passphrase.

Correct translation: Ismételje meg az új jelszót
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>Ehhez a művelethez szükség van a tárcanyitó jelmondatra.</translation>
    
YES, The translation is missing a word. It should be "tárca-nyitó" instead of "tárcanyitó".

Correct translation: Ehhez a művelethez szükség van a tárca-nyitó jelmondatra.
```

```
        <source>Change passphrase</source>
        <translation>Jelmondat megváltoztatása</translation>
    
YES: The translation is incorrect. "Change passphrase" translates to "Jelszó megváltoztatása" in Hungarian. "Jelmondat megváltoztatása" translates to "Change motto" or "Change slogan".
Jelszó megváltoztatása
```

```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Ne feledje, hogy a tárca titkosítása nem nyújt teljes védelmet az adathalász programok fertőzésével szemben.</translation>
    
YES, The translation is inaccurate and problematic. The Hungarian translation uses "adathalász programok" which translates to "phishing programs," but the source text mentions "malware infecting your computer." The correct translation should reflect this.
Correct translation: Ne feledje, hogy a tárca titkosítása nem nyújt teljes védelmet a számítógépét megfertőző kártevőkkel szemben.
```

```
        <source>Your wallet is about to be encrypted. </source>
        <translation>Tárcatitkosítás megkezdése.</translation>
    
YES, the translation is inaccurate and misses the nuance of the source text. The source text indicates that the wallet *is about to be* encrypted, implying an impending action. The translation "Tárcatitkosítás megkezdése." translates to "Starting wallet encryption," which suggests the encryption has already begun or is currently in progress, not that it is about to happen.

The correct translation should reflect the future tense.

NO
```

```
        <source>Wallet passphrase was successfully changed.</source>
        <translation>A tárca jelmondatát sikeresen megváltoztatta.</translation>
    
YES, The translation uses "megváltoztatta" which implies the user themselves changed it. The correct translation would be "megváltozott" which means it was changed (passively).
A tárca jelszavát sikeresen megváltoztatta.
```

```
        <source>%1 d</source>
        <translation>%1 n</translation>
    
YES, The translation is problematic because it changes the unit of time from days to nights. The correct translation should be "%1 d" to indicate days, as is common in many contexts, including financial or technical ones.

%1 d
```

```
        <source>%1 h</source>
        <translation>%1 ó</translation>
    
YES, The translation of 'h' to 'ó' is incorrect in this context. In Hungarian, 'h' is typically used to denote hours, and 'ó' is not a standard abbreviation for hours. The correct translation should be '%1 óra' for hours or '%1 h' if it's meant to be a direct abbreviation similar to English. Based on the context of Bitcoin, where time is often measured in hours, '%1 óra' is the more appropriate translation.
%1 óra
```

```
        <source>%1 s</source>
        <translation>%1 mp</translation>
    
YES, The translation uses an incorrect abbreviation for seconds. "mp" is not a standard abbreviation for seconds in Hungarian. The correct abbreviation is "s".

%1 mp
```

```
        <source>As this is the first time the program is launched, you can choose where %1 will store its data.</source>
        <translation>Mivel ez a program első indulása, megváltoztathatja, hogy a %1 hova mentse az adatokat.</translation>
    
YES, the translation incorrectly translates "choose" to "megváltoztathatja" (can change) instead of "választhatja" (can choose).
Mivel ez a program első indulása, választhatja, hogy a %1 hova mentse az adatokat.
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>A tárolt blokkok számának ritkításával jelentősen csökken a tranzakció történet tárolásához szükséges tárhely. Minden blokk továbbra is érvényesítve lesz. Ha ezt a beállítást később törölni szeretné újra le kell majd tölteni a teljes blokkláncot.</translation>
    
YES, The Hungarian translation is problematic because it contains an error in conveying the meaning of the source text. Specifically, the phrase "tárolt blokkok számának ritkításával" implies reducing the number of stored blocks, while the original English text "Enabling pruning significantly reduces the disk space required to store transactions" means reducing the disk space needed for transactions by pruning, not reducing the number of blocks. Additionally, the Hungarian translation incorrectly states that reverting the setting requires re-downloading the entire blockchain, whereas the English text states that re-downloading the entire blockchain is required if you want to disable pruning.

A tárolt blokkok számának ritkításával -> A metszés engedélyezése jelentősen csökkenti a tranzakciók tárolásához szükséges lemezterületet.
Ha ezt a beállítást később törölni szeretné -> Ha ezt a beállítást később vissza kell állítani

Correct translation: A metszés engedélyezése jelentősen csökkenti a tranzakciók tárolásához szükséges lemezterületet. Minden blokk továbbra is teljes mértékben érvényesítve lesz. Ennek a beállításnak a visszafordítása az egész blokklánc újbóli letöltését igényli.
```

```
        <source>Prune block storage to</source>
        <translation>Ritkítja a blokkok tárolását erre:</translation>
    
YES, The translation is inaccurate. The Hungarian translation of "Prune block storage to" should be something like "A blokkok tárolásának csonkítása ekkorára:". The provided translation is awkward and doesn't convey the intended meaning clearly.

"A blokkok tárolásának csonkítása ekkorára:"
```

```
        <source>Third-party URLs (e.g. a block explorer) that appear in the transactions tab as context menu items. %s in the URL is replaced by transaction hash. Multiple URLs are separated by vertical bar |.</source>
        <translation>Külső URL-ek (pl. blokkböngésző) amik megjelennek a tranzakciók fülön a helyi menüben. %s helyére az URL-ben behelyettesítődik a tranzakció ellenőrzőösszege. Több URL függőleges vonallal | van elválasztva egymástól.</translation>
    
YES, The translation of "transaction hash" is incorrect. It should be "tranzakció hash" or "tranzakció azonosítója" instead of "tranzakció ellenőrzőösszege".

NO, Külső URL-ek (pl. blokkböngésző) amik megjelennek a tranzakciók fülön a helyi menüben. %s helyére az URL-ben behelyettesítődik a tranzakció hash-e. Több URL függőleges vonallal | van elválasztva egymástól.
```

```
        <source>Whether to show coin control features or not.</source>
        <translation>Mutassa-e a pénzküldés beállításait.</translation>
    
YES, The translation is inaccurate and does not convey the meaning of the source text. The source text is about controlling coin features, not sending money.
The correct translation is: "A pénzkezelés funkcióinak megjelenítése vagy sem."
```

```
        <source>Sends %1 to %2</source>
        <translation>Küldés innen: %1 ide: %2</translation>
    
YES, The translation is inaccurate. The English phrase "Sends %1 to %2" implies sending something from a source (represented by %1) to a destination (represented by %2). However, the Hungarian translation "Küldés innen: %1 ide: %2" translates to "Sending from here: %1 to here: %2". This is problematic because it misinterprets the role of %1 and %2. In the context of Bitcoin, %1 would typically be the amount being sent and %2 would be the recipient's address.

The correct translation should reflect sending an amount to an address. A more accurate translation would be:

Küldés: %1 címre: %2
```

```
        <source>Mapped AS</source>
        <translation>Leképezett AR</translation>
    
YES
The term "AS" is not a standard abbreviation in Bitcoin context and "AR" is also not a recognized abbreviation in Hungarian for anything related to Bitcoin. Assuming "AS" is meant to be "Autonomous System", a term used in networking, the translation should reflect that.
Leképezett autonóm rendszer
```

```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>Eldobott címek</translation>
    
YES - The Hungarian translation "Eldobott címek" translates to "Dropped addresses" which is not an accurate translation of "Addresses Rate-Limited". The concept of rate-limiting is not conveyed in the translation. A more accurate translation would be "Címek sebességkorlátozása" or "Korlátozott számú címek".

The correct translation should convey the meaning of rate limiting.

Correct translation: Címek sebességkorlátozása
```

```
        <source>Could not generate new %1 address</source>
        <translation>Cím előállítása sikertelen %1 </translation>
    
YES, The translation is inaccurate and has formatting issues. The word order is incorrect, and the format specifier '%1' is misplaced.
Cím előállítása sikertelen: %1
```

```
        <source>You can sign messages/agreements with your legacy (P2PKH) addresses to prove you can receive bitcoins sent to them. Be careful not to sign anything vague or random, as phishing attacks may try to trick you into signing your identity over to them. Only sign fully-detailed statements you agree to.</source>
        <translation>Aláírhat üzeneteket/megállapodásokat a régí típusú (P2PKH) címeivel amivel bizonyítja, hogy fogadni és elkölteni is tudja az oda küldött bitcoint. Legyen óvatos és ne írjon alá semmilyen ködös vagy véletlenszerű üzenetet, mivel adathalászok megkísérelhetik rávenni a személyazonosságának átruházására. Csak olyan alaposan részletezett állításokat írjon alá amivel teljesen egyetért.</translation>
    
YES, The translation incorrectly implies that signing a message with a P2PKH address allows you to "spend" bitcoins, which is not the primary purpose of message signing in Bitcoin. The purpose is to prove ownership of the address, not to enable spending.

Correct translation:
Aláírhat üzeneteket/megállapodásokat a régí típusú (P2PKH) címeivel, amivel bizonyítja, hogy tud fogadni arra a címre küldött bitcoint. Legyen óvatos és ne írjon alá semmilyen ködös vagy véletlenszerű üzenetet, mivel adathalászok megkísérelhetik rávenni a személyazonosságának átruházására. Csak olyan alaposan részletezett állításokat írjon alá, amivel teljesen egyetért.
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/megerősítetlen</translation>
    
YES: The Hungarian word "megerősítetlen" means "unconfirmed". The source text specifies a transaction that is confirmed in at least one block, but less than six blocks. This means the transaction is *partially* confirmed, not unconfirmed. A more accurate translation would be "részben megerősített".

%1/részben megerősített
```

```
        <source>Warning: This may pay the additional fee by reducing change outputs or adding inputs, when necessary. It may add a new change output if one does not already exist. These changes may potentially leak privacy.</source>
        <translation>Figyelmeztetés: Többletdíjakhoz vezethet ha a bemenetek és visszajáró kimenetek szükség szerint kerülnek hozzáadásra illetve összevonásra. Ezzel létrejöhet új kimenet a visszajárónak, ha még nem létezik ilyen. Ezekkel beállításokkal jelentősen sérülhet az adatvédelem hatékonysága.</translation>
    
YES: The translation significantly alters the meaning of the source text by misinterpreting "reducing change outputs or adding inputs" as "bemenetek és visszajáró kimenetek szükség szerint kerülnek hozzáadásra illetve összevonásra" (inputs and change outputs are added or merged as needed), and "leak privacy" as "jelentősen sérülhet az adatvédelem hatékonysága" (the effectiveness of data protection can be significantly damaged). The original text indicates potential privacy leakage, not a significant damage to data protection effectiveness.

Correct translation: Figyelmeztetés: Ez szükség esetén a visszajáró kimenetek csökkentésével vagy bemenetek hozzáadásával fizetheti a többletdíjat. Új visszajáró kimenetet adhat hozzá, ha még nem létezik ilyen. Ezek a változtatások potenciálisan kiszivárogtathatnak magánjellegű információt.
```

```
        <source>Error reading %s! All keys read correctly, but transaction data or address metadata may be missing or incorrect.</source>
        <translation>Hiba %s beolvasása közben. Az összes kulcs sikeresen beolvasva, de a tranzakciós adatok vagy a címtár rekordok hiányoznak vagy sérültek.</translation>
    
YES - The translation for "address metadata" is "címtár rekordok", which is not accurate in the context of Bitcoin. A more appropriate translation would be "cím metaadatok".

Correct translation: Hiba %s beolvasása közben. Az összes kulcs sikeresen beolvasva, de a tranzakciós adatok vagy a cím metaadatok hiányoznak vagy sérültek.
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>Érvénytelen összeg: %s=&lt;amount&gt;: '%s' (legalább a minrelay összeg azaz %s kell legyen, hogy ne ragadjon be a tranzakció)</translation>
    
YES - The Hungarian translation is grammatically incorrect and awkward. The phrase "minrelay összeg azaz" is redundant and doesn't flow well. A more natural translation would be "a %s minimális közvetítési díjnak megfelelő összeg".

Érvénytelen összeg: %s=&lt;amount&gt;: '%s' (legalább a %s minimális közvetítési díjnak megfelelő összeg kell, hogy ne ragadjon be a tranzakció)
```

```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>A címraktár kiürült, előbb adja ki a keypoolrefill parancsot.</translation>
    
YES, The Hungarian translation uses "címraktár" which translates to "address repository" or "address pool". While this is a plausible translation in some contexts, in the context of Bitcoin, "keypool" refers to a pool of private keys, not addresses. The term "address pool" or "key pool" would be more accurate. Additionally, the original sentence implies that the user needs to *call* or *execute* the `keypoolrefill` command, not necessarily *issue* it.

Correct Translation: Hiba: A kulcspool elfogyott, kérjük, hívja előbb a keypoolrefill parancsot.
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>A tranzakcióhoz szükség van visszajáró címekre, de nem lehet előállítani egyet.</translation>
    
YES: The translation uses the plural "visszajáró címekre" (to change addresses) when the source text uses the singular "a change address". The Hungarian text should reflect the singular form.

Correct translation: A tranzakcióhoz szükség van egy visszajáró címre, de nem lehet előállítani egyet.
```
</details>
