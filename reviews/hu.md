# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>hu</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bhu%5D%20low%20quality)


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

<!-- cache_translation_check_hu_29312b5be5cc3031227410c0e403600e30415ae9f19eb8f5185af5ae17730cb8 -->
```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>A tranzakcióhoz szükség van visszajáró címekre, de nem lehet előállítani egyet.</translation>
    
ERR
There is an inaccuracy and a plural/singular mismatch. The source says "a change address" (singular), but the translation uses plural 'visszajáró címekre' (change addresses) and then 'egyet' (one), which is awkward. Also, "visszajáró cím" is the proper term for "change address".

Correct translation:
A tranzakcióhoz szükség van egy visszajáró címre, de azt nem tudjuk előállítani.
```
</details>

Number of issues: 11.
