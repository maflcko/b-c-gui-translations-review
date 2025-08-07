# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>hu</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bhu%5D%20low%20quality)


```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Ne feledje, hogy a tárca titkosítása nem nyújt teljes védelmet az adathalász programok fertőzésével szemben.</translation>
    
YES
The translation does not accurately convey that encrypting the wallet cannot fully protect your bitcoins in the case of malware infection. "Adathalász programok" specifically means "phishing programs" rather than the broader term "malware." Also, "bitcoins" is omitted in the translation. A more accurate translation would be:

Correct translation:
Ne feledje, hogy a tárca titkosítása nem védi meg teljesen a bitcoinjait, ha rosszindulatú program fertőzi meg a számítógépét.
```

```
        <source>Your wallet is about to be encrypted. </source>
        <translation>Tárcatitkosítás megkezdése.</translation>
    
YES
The translation is inaccurate and omits the full meaning of the source sentence. The original informs the user that wallet encryption is imminent, while the translation merely states "Start of wallet encryption," losing the nuance and the user address.

Correct translation:
A tárca hamarosan titkosításra kerül.
```

```
        <source>%1 d</source>
        <translation>%1 n</translation>
    
YES
The translation is incorrect. In Hungarian, "d" for "days" should be "n" only if "nap" (day) is abbreviated as "n", which is uncommon. The more standard or universally recognized abbreviation for "nap" is indeed "n", but it's best practice to ensure clarity or possibly use the full word unless context absolutely requires abbreviation and it's used consistently in the application.

If the context confirms "n" is the abbreviation used elsewhere, it's fine; otherwise, it may cause confusion.

Correct translation:
If abbreviation is used throughout:
%1 n
If not, prefer full word:
%1 nap
```

```
        <source>Whether to show coin control features or not.</source>
        <translation>Mutassa-e a pénzküldés beállításait.</translation>
    
YES
The translation does not accurately reflect the source text. "Coin control" refers to advanced features that let users select which coins to spend in Bitcoin, not general "pénzküldés beállításai" ("send money settings"). Also, the translation omits the conditional aspect ("Whether to show...").

Correct translation:
Megjelenítse-e az érmevezérlési funkciókat vagy sem.
```

```
        <source>Sends %1 to %2</source>
        <translation>Küldés innen: %1 ide: %2</translation>
    
YES
The Hungarian translation changes the structure of the sentence and adds "innen" (from here) and "ide" (to here), which is not present in the original. Also, "Küldés" is a noun ("sending"), while the English uses a verb ("Sends"). The translation should more directly mirror the structure and tense of the English sentence.

Correct translation:
%1 elküldése %2 részére
```

```
        <source>Mapped AS</source>
        <translation>Leképezett AR</translation>
    
YES
The abbreviation "AS" stands for "Autonomous System" in networking contexts and should remain "AS" in Hungarian technical translations as well. "AR" does not have the same meaning and is incorrect in this context.

Correct translation:
Leképezett AS
```

```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>Eldobott címek</translation>
    
YES
The translation "Eldobott címek" means "Dropped addresses," which does not accurately capture the meaning of "Addresses Rate-Limited." The intended meaning is that the addresses are subject to rate-limiting, not just that they were dropped.

Correct translation:
Címek korlátozva (ütemezési korlát miatt)
```

```
        <source>Could not generate new %1 address</source>
        <translation>Cím előállítása sikertelen %1 </translation>
    
YES
The translation has word order issues and an extra space at the end. Also, the Hungarian translation should reflect the structure and intent of the English sentence, ensuring that the variable %1 appears in the correct place.

Correct translation:
Nem sikerült új %1 címet létrehozni
```

```
        <source>You can sign messages/agreements with your legacy (P2PKH) addresses to prove you can receive bitcoins sent to them. Be careful not to sign anything vague or random, as phishing attacks may try to trick you into signing your identity over to them. Only sign fully-detailed statements you agree to.</source>
        <translation>Aláírhat üzeneteket/megállapodásokat a régí típusú (P2PKH) címeivel amivel bizonyítja, hogy fogadni és elkölteni is tudja az oda küldött bitcoint. Legyen óvatos és ne írjon alá semmilyen ködös vagy véletlenszerű üzenetet, mivel adathalászok megkísérelhetik rávenni a személyazonosságának átruházására. Csak olyan alaposan részletezett állításokat írjon alá amivel teljesen egyetért.</translation>
    
YES
There are minor grammatical errors and inaccuracies:

1. "régí típusú" should be "régi típusú" (typo).
2. The phrase "fogadni és elkölteni is tudja az oda küldött bitcoint" is inaccurate, as the original only says "prove you can receive", not "spend".
3. Sentences should be broken up for clarity.
4. Some punctuation and article use are missing for natural-sounding Hungarian.

Correct translation:
Üzeneteket vagy megállapodásokat aláírhat régi típusú (P2PKH) címeivel, hogy bizonyítsa: tud bitcoint fogadni az ezekre a címekre érkező utalásokkal. Legyen óvatos, és ne írjon alá semmilyen homályos vagy véletlenszerű üzenetet, mivel adathalász támadók megpróbálhatják rávenni, hogy ezzel átruházza személyazonosságát. Csak olyan teljesen részletes nyilatkozatokat írjon alá, amellyel valóban egyetért.
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>Érvénytelen összeg: %s=&lt;amount&gt;: '%s' (legalább a minrelay összeg azaz %s kell legyen, hogy ne ragadjon be a tranzakció)</translation>
    
YES
The Hungarian translation is mostly accurate but the word order and clarity could be improved, and the format specifier order does not fully match the English. The source suggests "Invalid amount for %s=<amount>: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)". The translation places ": %s=<amount>" after "Érvénytelen összeg:", which is less natural and risks confusion for the format specifiers' placement.

Correct translation:
Érvénytelen összeg a(z) %s=&lt;amount&gt; esetén: '%s' (legalább a minrelay díjnak, azaz %s-nek kell lennie, hogy a tranzakció ne akadjon el)

Explanation: 
- The position and context of format specifiers now match the source.
- "minrelay fee" is better translated as "minrelay díj", and "akadjon el" for "stuck".
- Word order and specifier mapping is corrected.
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>A tranzakcióhoz szükség van visszajáró címekre, de nem lehet előállítani egyet.</translation>
    
YES
There is an inaccuracy and a plural/singular mismatch. The source says "a change address" (singular), but the translation uses plural 'visszajáró címekre' (change addresses) and then 'egyet' (one), which is awkward. Also, "visszajáró cím" is the proper term for "change address".

Correct translation:
A tranzakcióhoz szükség van egy visszajáró címre, de azt nem tudjuk előállítani.
```
</details>

Number of issues: 11.
