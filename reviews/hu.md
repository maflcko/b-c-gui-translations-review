# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>hu</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bhu%5D%20request)


<!-- cache_translation_check_hu_4fd1d9792ceabd089e82786ece5febd3c0e5e26a856f823fda68545908667371 -->
```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Ne feledje, hogy a tárca titkosítása nem nyújt teljes védelmet az adathalász programok fertőzésével szemben.</translation>
    
ERR
The translation does not accurately convey that encrypting the wallet cannot fully protect your bitcoins in the case of malware infection. "Adathalász programok" specifically means "phishing programs" rather than the broader term "malware." Also, "bitcoins" is omitted in the translation. A more accurate translation would be:

Correct translation:
Ne feledje, hogy a tárca titkosítása nem védi meg teljesen a bitcoinjait, ha rosszindulatú program fertőzi meg a számítógépét.
```

<!-- cache_translation_check_hu_ba70028021e631a032f8be208345806c17527a0dbb18491716326cb5e2c915a5 -->
```
        <source>Your wallet is about to be encrypted. </source>
        <translation>Tárcatitkosítás megkezdése.</translation>
    
ERR
The translation is inaccurate and omits the full meaning of the source sentence. The original informs the user that wallet encryption is imminent, while the translation merely states "Start of wallet encryption," losing the nuance and the user address.

Correct translation:
A tárca hamarosan titkosításra kerül.
```

<!-- cache_translation_check_hu_b96225181c5b5386a8b5beac2e528e4d98cbc451373ce5ad7ad625e6e6b29e79 -->
```
        <source>%1 d</source>
        <translation>%1 n</translation>
    
ERR
The translation is incorrect. In Hungarian, "d" for "days" should be "n" only if "nap" (day) is abbreviated as "n", which is uncommon. The more standard or universally recognized abbreviation for "nap" is indeed "n", but it's best practice to ensure clarity or possibly use the full word unless context absolutely requires abbreviation and it's used consistently in the application.

If the context confirms "n" is the abbreviation used elsewhere, it's fine; otherwise, it may cause confusion.

Correct translation:
If abbreviation is used throughout:
%1 n
If not, prefer full word:
%1 nap
```

<!-- cache_translation_check_hu_f3e9c44100cf103bf4a4fa8865004a66dd0224536d399dd2c38f7f237145b7e3 -->
```
        <source>&amp;Command-line options</source>
        <translation>Paran&amp;cssor kapcsolók</translation>
    
ERR
The Hungarian word "Parancssor" (command line) is misspelled as "Parancssor" (should be one "s"), and the ampersand (&) indicating shortcut key is moved but correctly present. Whitespace is fine. The correct translation is:

Correct translation:
&Parancssori kapcsolók
```

<!-- cache_translation_check_hu_79f72470a3ac4d379e95a28d542e49c54c58b83cfe22f9815ec6631a5b9cfa25 -->
```
        <source>Invalid Wallet Name</source>
        <translation>Érvénytelen tárca név</translation>
    
ERR
In Hungarian orthography, the compound noun "tárcanév" (wallet name) should be written as a single word without a space.

Correct translation:
Érvénytelen tárcanév
```

<!-- cache_translation_check_hu_4ce2ef43f977d3691b1d19c8c7eac8369a324e708c5a1c59baa9204d1a49ecb5 -->
```
        <source>Enable coin &amp;control features</source>
        <translation>Pénzküldés b&amp;eállításainak engedélyezése</translation>
    
ERR
The translation is inaccurate. "Pénzküldés beállításainak engedélyezése" translates to "Enable sending settings", which does not correctly render "Enable coin control features". Additionally, the & indicating the shortcut is incorrectly placed at "beállításainak" instead of "control" (or a reasonable equivalent).

Correct translation:
Érme&amp;kezelési funkciók engedélyezése
```

<!-- cache_translation_check_hu_875fed03d82dc158a6f37f5c9f4d24dc9997b5db61373573a6b0c9d5dc70638e -->
```
        <source>&amp;Show tray icon</source>
        <translation>&amp;Tálca icon megjelenítése</translation>
    
ERR
There is a minor issue: "icon" is not properly translated into Hungarian. The correct word is "ikon". 

Correct translation:
&Tálcaikon megjelenítése
```

<!-- cache_translation_check_hu_cab78c7bbf6f2deac39832c2ad800584a2977c5ccdb56117ee0d0baf7132d225 -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>&amp;Kicsinyítés a tálcára az eszköztár helyett</translation>
    
ERR
The Hungarian translation incorrectly uses "tálcára" ("to the taskbar") instead of "rendszertálcára" ("to the system tray"). In Hungarian IT terminology, "tálca" means the Windows taskbar, and "rendszertálca" is the system tray. The English source says "Minimize to the tray instead of the taskbar", so this is reversed in the translation.

Correct translation:
&Kicsinyítés a rendszertálcára az eszköztár helyett

However, "eszköztár" means "toolbar" and not "taskbar". The correct term for "taskbar" is "tálca". Thus, the phrase should be:

&Kicsinyítés a rendszertálcára a tálca helyett
```

<!-- cache_translation_check_hu_679fc2835539951916833532444ac5e0ae5fc4027facf6207a925efcadc81ff4 -->
```
        <source>&amp;Unit to show amounts in:</source>
        <translation>&amp;Mértékegység:</translation>
    
ERR
The translation omits "to show amounts in", which may reduce clarity. The Hungarian translation should more closely match the meaning of the original, indicating that this is the unit in which amounts are displayed.

Correct translation:
& Mértékegység a mennyiségek megjelenítéséhez:
or
&A megjelenített összegek mértékegysége:
```

<!-- cache_translation_check_hu_728a480a4dace81b24bc6a06159f9e0fb451b209f88560c1dda855b6e85b0835 -->
```
        <source>Whether to show coin control features or not.</source>
        <translation>Mutassa-e a pénzküldés beállításait.</translation>
    
ERR
The translation does not accurately reflect the source text. "Coin control" refers to advanced features that let users select which coins to spend in Bitcoin, not general "pénzküldés beállításai" ("send money settings"). Also, the translation omits the conditional aspect ("Whether to show...").

Correct translation:
Megjelenítse-e az érmevezérlési funkciókat vagy sem.
```

<!-- cache_translation_check_hu_19ff7b81fd5f492ffa6e94599fd82026e10dd351ec68a52556da26f7732ab0bd -->
```
        <source>Sends %1 to %2</source>
        <translation>Küldés innen: %1 ide: %2</translation>
    
ERR
The Hungarian translation changes the structure of the sentence and adds "innen" (from here) and "ide" (to here), which is not present in the original. Also, "Küldés" is a noun ("sending"), while the English uses a verb ("Sends"). The translation should more directly mirror the structure and tense of the English sentence.

Correct translation:
%1 elküldése %2 részére
```

<!-- cache_translation_check_hu_f5ff7c1daf1e963ffa75c2eb408221e062a5bf57b3a17a7d08d2e0e2d98923d4 -->
```
        <source>Mapped AS</source>
        <translation>Leképezett AR</translation>
    
ERR
The abbreviation "AS" stands for "Autonomous System" in networking contexts and should remain "AS" in Hungarian technical translations as well. "AR" does not have the same meaning and is incorrect in this context.

Correct translation:
Leképezett AS
```

<!-- cache_translation_check_hu_e509b840a35d1e002794e49c43c1105be6019d90cf0ccb6768f0b2f8af6edf52 -->
```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>Eldobott címek</translation>
    
ERR
The translation "Eldobott címek" means "Dropped addresses," which does not accurately capture the meaning of "Addresses Rate-Limited." The intended meaning is that the addresses are subject to rate-limiting, not just that they were dropped.

Correct translation:
Címek korlátozva (ütemezési korlát miatt)
```

<!-- cache_translation_check_hu_ab302c5233be4747aa10cee73f25c1828c34cf3a8e12054414b3b75c6366b30b -->
```
        <source>Could not generate new %1 address</source>
        <translation>Cím előállítása sikertelen %1 </translation>
    
ERR
The translation has word order issues and an extra space at the end. Also, the Hungarian translation should reflect the structure and intent of the English sentence, ensuring that the variable %1 appears in the correct place.

Correct translation:
Nem sikerült új %1 címet létrehozni
```

<!-- cache_translation_check_hu_fb62f0b1b1e346e26a6f361130c5ac2f56ce8a69d0bbe9e6bc712c9fe17a52b2 -->
```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>Részlegesen Aláírt Tranzakció (PSBT bináris)</translation>
    
ERR
The translation is understandable but uses non-idiomatic capitalization for Hungarian (only proper nouns and sentence starts should be capitalized). Also it's clearer to include "PSBT" and "bináris" in lowercase or separated by a comma.

Correct translation:
Részlegesen aláírt tranzakció (PSBT, bináris)
```

<!-- cache_translation_check_hu_a39033abbfe6f2f9403c354d0af3f3686676e607426ebd02960454daafa8abd0 -->
```
        <source>S&amp;ubtract fee from amount</source>
        <translation>&amp;Vonja le a díjat az összegből</translation>
    
ERR
The translation is largely correct but problematic regarding shortcut key placement and style. In Hungarian, "&amp;" should be placed before the shortcut character in the Hungarian word, and the selection of "V" (for "Vonja") may not be ideal, as in the English original, it's "S" for "Subtract." Hungarian interfaces often use "L" for "Levásás" (subtract) or similar.

A more common translation in Hungarian Bitcoin interfaces:
A díj levonása az összegből (&amp;L)

Correct translation:
A díj levonása az összegből (&amp;L)
```

<!-- cache_translation_check_hu_1a1762edd7f9e1a0c928f5134bca0b872727506559d3f277d2c77f2f60f15798 -->
```
        <source>You can sign messages/agreements with your legacy (P2PKH) addresses to prove you can receive bitcoins sent to them. Be careful not to sign anything vague or random, as phishing attacks may try to trick you into signing your identity over to them. Only sign fully-detailed statements you agree to.</source>
        <translation>Aláírhat üzeneteket/megállapodásokat a régí típusú (P2PKH) címeivel amivel bizonyítja, hogy fogadni és elkölteni is tudja az oda küldött bitcoint. Legyen óvatos és ne írjon alá semmilyen ködös vagy véletlenszerű üzenetet, mivel adathalászok megkísérelhetik rávenni a személyazonosságának átruházására. Csak olyan alaposan részletezett állításokat írjon alá amivel teljesen egyetért.</translation>
    
ERR
There are minor grammatical errors and inaccuracies:

1. "régí típusú" should be "régi típusú" (typo).
2. The phrase "fogadni és elkölteni is tudja az oda küldött bitcoint" is inaccurate, as the original only says "prove you can receive", not "spend".
3. Sentences should be broken up for clarity.
4. Some punctuation and article use are missing for natural-sounding Hungarian.

Correct translation:
Üzeneteket vagy megállapodásokat aláírhat régi típusú (P2PKH) címeivel, hogy bizonyítsa: tud bitcoint fogadni az ezekre a címekre érkező utalásokkal. Legyen óvatos, és ne írjon alá semmilyen homályos vagy véletlenszerű üzenetet, mivel adathalász támadók megpróbálhatják rávenni, hogy ezzel átruházza személyazonosságát. Csak olyan teljesen részletes nyilatkozatokat írjon alá, amellyel valóban egyetért.
```

<!-- cache_translation_check_hu_2b394076e2e74f9fbf2bf75a2a52f9c54308df6deff28b206fd686ef269dd363 -->
```
        <source>Copy the current signature to the clipboard</source>
        <translation>A kiválasztott aláírás másolása a vágólapra</translation>
    
ERR
"current" was translated as "kiválasztott" (selected), which changes the meaning. It should be "aktuális".

Correct translation:
Az aktuális aláírás másolása a vágólapra
```

<!-- cache_translation_check_hu_b0953bbbeee0c6b1ae4d7d577d991d2c29dd52024ff312b4450cb5228fff5375 -->
```
        <source>Copy &amp;raw transaction</source>
        <translation>Nye&amp;rs tranzakció másolása</translation>
    
ERR
There is a typo in the translation: "Nye&amp;rs" should be "Nye&amp;rs" (which is still incorrect Hungarian). The correct translation of "raw transaction" is "nyers tranzakció", and the shortcut indicator (&) must be used exactly once.

Correct translation:
Nyers tranzakció másolása(&amp;)
```

<!-- cache_translation_check_hu_fb3df14788f453368c7124673ecf196f32a130d34b1fb64427d4a7e9f4122f66 -->
```
        <source>Error starting/committing db txn for wallet transactions removal process</source>
        <translation>Hiba a tárca tranzakciókat eltávolító adatbázis tranzakció létrehozása közben</translation>
    
ERR
The translation omits the “committing” part (only says “creation”) and misattributes the modifier, missing the “process” aspect.
Correct translation:
Hiba a tárcatranzakciók eltávolítási folyamatához tartozó adatbázis-tranzakció indítása vagy véglegesítése közben
```

<!-- cache_translation_check_hu_04eded0095b5ffe17b33a13c8bc7bec99edd4e62a7b52c435e052ea07f42a2ee -->
```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>Érvénytelen összeg: %s=&lt;amount&gt;: '%s' (legalább a minrelay összeg azaz %s kell legyen, hogy ne ragadjon be a tranzakció)</translation>
    
ERR
The Hungarian translation is mostly accurate but the word order and clarity could be improved, and the format specifier order does not fully match the English. The source suggests "Invalid amount for %s=<amount>: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)". The translation places ": %s=<amount>" after "Érvénytelen összeg:", which is less natural and risks confusion for the format specifiers' placement.

Correct translation:
Érvénytelen összeg a(z) %s=&lt;amount&gt; esetén: '%s' (legalább a minrelay díjnak, azaz %s-nek kell lennie, hogy a tranzakció ne akadjon el)

Explanation: 
- The position and context of format specifiers now match the source.
- "minrelay fee" is better translated as "minrelay díj", and "akadjon el" for "stuck".
- Word order and specifier mapping is corrected.
```

<!-- cache_translation_check_hu_ac37436a8854698826501d8d525480f9fe861b822ba46597ec44f0a6ed38856c -->
```
        <source>Specified -blockreservedweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>A megadott -blockreservedweight (%d) meghaladja a konszenzus maximum blokk súlyt (%d)</translation>
    
ERR
The Hungarian phrasing is awkward and uses incorrect compounding. "maximum blokk súly" should be "maximális blokksúly", and "konszenzus szerinti" clarifies the relation.

Correct translation:
A megadott -blockreservedweight (%d) meghaladja a konszenzus szerinti maximális blokksúlyt (%d)
```

<!-- cache_translation_check_hu_bb0166355183a1a87c9ccb65c51971cac2cc6b8964481d266d243848d97fa3d7 -->
```
        <source>Cannot write to directory '%s'; check permissions.</source>
        <translation>Nem tudok írni a '%s' könyvtárba, ellenőrizd a jogosultságokat.</translation>
    
ERR
The translation uses first person and informal imperative, which is inappropriate for standard UI strings. It also replaces the semicolon with a comma. 

Correct translation:
Nem lehet írni a(z) '%s' könyvtárba; ellenőrizze a jogosultságokat.
```

<!-- cache_translation_check_hu_37eea520921e6a17a9f0ce06461e382550aae618a784e4c3b833b711221e024d -->
```
        <source>Error loading databases</source>
        <translation>Hiba az adatbázis betöltése közben</translation>
    
ERR
The translation uses the singular "adatbázis" while the source is plural "databases".

Correct translation:
Hiba az adatbázisok betöltése közben
```

<!-- cache_translation_check_hu_a8ad998dcb21d61143934a99a368859d0143e7da43c25aa40479b5e4ac7f0fa7 -->
```
        <source>Failed to close block undo file.</source>
        <translation>Visszavonási adatok bezárása nem sikerült.</translation>
    
ERR
The translation omits "fájl" (file) and doesn't clearly reference "block". Also Hungarian word order is awkward. No format specifiers or whitespace issues, but the meaning should explicitly mention the block undo file.

Correct translation:
A blokkvisszavonási fájl bezárása nem sikerült.
(or)
Nem sikerült bezárni a blokkvisszavonási fájlt.
```

<!-- cache_translation_check_hu_85cb9ae474e22d8a7e348c21fa00ebed6f5595b97c060f201bee2e06c5bdb44f -->
```
        <source>Failed to close file when writing block.</source>
        <translation>Blokk írása közben nem sikerült bezárni a fájlt</translation>
    
ERR
Missing terminal period compared to source sentence.

Correct translation:
Blokk írása közben nem sikerült bezárni a fájlt.
```

<!-- cache_translation_check_hu_29312b5be5cc3031227410c0e403600e30415ae9f19eb8f5185af5ae17730cb8 -->
```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>A tranzakcióhoz szükség van visszajáró címekre, de nem lehet előállítani egyet.</translation>
    
ERR
There is an inaccuracy and a plural/singular mismatch. The source says "a change address" (singular), but the translation uses plural 'visszajáró címekre' (change addresses) and then 'egyet' (one), which is awkward. Also, "visszajáró cím" is the proper term for "change address".

Correct translation:
A tranzakcióhoz szükség van egy visszajáró címre, de azt nem tudjuk előállítani.
```

<!-- cache_translation_check_hu_58c8fa4621acac880849f507a76995a756d53838f2335388843d553c97c97838 -->
```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on an enormous cluster of unconfirmed transactions.</source>
        <translation>Sikertelen az emelt díjak becslése, mert a megerősítetlen UTXO-k hatalmas mennyiségű megerősítetlen tranzakcióktól függnek.</translation>
    
ERR
The translation uses "becslése" (estimation) instead of "kiszámítása" (calculation), has an awkward/incorrect construction with "hatalmas mennyiségű ... tranzakcióktól", and "emelt díjak" can mislead (already increased fees) rather than "fees for the bump".

Correct translation:
Nem sikerült kiszámítani a díjemeléshez szükséges díjakat, mert a megerősítetlen UTXO-k egy óriási, megerősítetlen tranzakciókból álló klasztertől függenek.
```

<!-- cache_translation_check_hu_cf4b7f25c0317f2f2993d7e58dab2856e6eab964f9c97647a667e634808c6ce8 -->
```
        <source>Transaction requires one destination of non-zero value, a non-zero feerate, or a pre-selected input</source>
        <translation>A tranzakcióhoz szükséges egy nem nulla értékű utalás, egy nem-nulla tranzakciós díj vagy egy előre kiválaszott bemenet</translation>
    
ERR
Multiple issues: unnatural phrasing ("szükséges egy"), incorrect term for "destination" ("utalás" instead of "célcím"), "feerate" mistranslated as fee amount, a typo ("kiválaszott"), and inconsistent hyphenation.

Correct translation:
A tranzakcióhoz szükség van egy nem nulla értékű célcímre, egy nem nulla díjrátára vagy egy előre kiválasztott bemenetre.
```

<!-- cache_translation_check_hu_39277b58c6ea5e6d986705a8b1be5022fa10d4848cdd61f6c03d0ed63a98a016 -->
```
        <source>Failed to start indexes, shutting down…</source>
        <translation>Indexek indítása sikertelen, a program leáll...</translation>
    
ERR
Ellipsis character mismatch: source uses the single-character ellipsis (…), while the translation uses three periods (...). Use the same ellipsis character for consistency.

Correct translation:
Indexek indítása sikertelen, a program leáll…
```
</details>

Number of issues: 30.
