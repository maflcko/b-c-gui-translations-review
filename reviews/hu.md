# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>hu</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bhu%5D%20low%20quality)


```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Ne feledje, hogy a tárca titkosítása nem nyújt teljes védelmet az adathalász programok fertőzésével szemben.</translation>
    
YES  
The translation does not fully convey the meaning of the source. The source says that encrypting your wallet cannot fully protect your bitcoins from malware stealing them, while the translation mentions protection only against "phishing programs" (adathalász programok) infecting the computer, which is narrower and incorrect in this context. Also, the original talks specifically about "bitcoins" being stolen, which is missing in the translation.

Correct translation:  
Ne feledje, hogy a tárcája titkosítása nem nyújt teljes védelmet arra, hogy a számítógépét fertőző rosszindulatú programok ellopják a bitcoinjait.
```

```
        <source>Your wallet is about to be encrypted. </source>
        <translation>Tárcatitkosítás megkezdése.</translation>
    
YES  
The Hungarian translation is incomplete and does not fully convey the meaning of the source sentence. The source "Your wallet is about to be encrypted." implies an imminent action about to happen, whereas the translation "Tárcatitkosítás megkezdése." means "Starting wallet encryption," which sounds like a noun phrase or a title rather than a full sentence expressing the imminent event.

A more accurate and natural Hungarian translation would be:  
"Tárcája hamarosan titkosítva lesz."  
or  
"Tárcája éppen titkosítás alatt áll."  
However, the first option is closer to the intended meaning of "about to be encrypted."

Correct translation:  
Tárcája hamarosan titkosítva lesz.
```

```
        <source>Wallet passphrase was successfully changed.</source>
        <translation>A tárca jelmondatát sikeresen megváltoztatta.</translation>
    
YES  
The Hungarian translation uses a form that implies the wallet itself changed the passphrase, which is unnatural and incorrect. The original English means that the user successfully changed the passphrase. A more accurate Hungarian translation would be:

A tárca jelszavát sikeresen megváltoztatták.
```

```
        <source>%1 d</source>
        <translation>%1 n</translation>
    
YES  
The source uses "d," which likely stands for "days" (d), while the Hungarian translation uses "n," which is an abbreviation for "nap" (day). However, the source text uses the single-letter abbreviation "d," and the translation should reflect the same letter to maintain consistency, especially if it's part of a time duration format. Using "n" instead of "d" could cause confusion or inconsistency in the UI.

Correct translation:  
%1 d
```

```
        <source>%1 h</source>
        <translation>%1 ó</translation>
    
YES
The Hungarian abbreviation for "hour" is "ó" with an accent, but the source uses "h" (likely the English abbreviation). In time abbreviations, Hungarian usually uses "ó" (óra) without a period. However, the shorthand for hours in many technical contexts, especially with Bitcoin software, might better stay consistent with the source "h". Also, there should be no extra space issues.

Therefore, if it's meant to be a unit abbreviation consistent with Hungarian usage, "%1 ó" is correct, but the translation uses "%1 ó" where the source is "%1 h". It's acceptable if the software expects Hungarian unit abbreviations.

If the software uses "h" always, it might be better not to translate the unit.

Given that "%1 ó" is the standard Hungarian abbreviation, the translation is acceptable.

Hence, NO
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>A tárolt blokkok számának ritkításával jelentősen csökken a tranzakció történet tárolásához szükséges tárhely. Minden blokk továbbra is érvényesítve lesz. Ha ezt a beállítást később törölni szeretné újra le kell majd tölteni a teljes blokkláncot.</translation>
    
YES  
The translation contains a small inaccuracy regarding the concept of "pruning" and the wording could be smoother. The source says "Enabling pruning significantly reduces the disk space required to store transactions," but the Hungarian translation says "A tárolt blokkok számának ritkításával" ("by pruning the number of stored blocks"), which is somewhat indirect and less precise. Pruning reduces the disk space required to store transaction history by removing old block data, not just by reducing the number of stored blocks in a vague way. Also, the phrase "Ha ezt a beállítást később törölni szeretné" ("If you want to delete this setting later") can be improved to "Ha ezt a beállítást vissza akarja vonni" ("If you want to revert this setting") to better reflect the meaning "reverting this setting."

Correct translation:  
"A ritkítás engedélyezése jelentősen csökkenti a tranzakciók tárolásához szükséges lemezterületet. Minden blokk továbbra is teljes mértékben érvényesítve lesz. Ennek a beállításnak a visszavonása a teljes blokklánc újbóli letöltését igényli."
```

```
        <source>Whether to show coin control features or not.</source>
        <translation>Mutassa-e a pénzküldés beállításait.</translation>
    
YES  
The Hungarian translation does not accurately reflect the meaning of the English source. The source talks about showing "coin control features," which refers to Bitcoin-specific functionality, not just general "sending money" settings. Also, "coin control" is a known term in Bitcoin wallets and should be reflected accordingly to avoid confusion.

Correct translation:  
"Mutassa-e a coin control funkciókat vagy sem."  
or to keep it more natural Hungarian while maintaining meaning:  
"Mutassa-e a coin control funkciókat."
```

```
        <source>Sends %1 to %2</source>
        <translation>Küldés innen: %1 ide: %2</translation>
    
YES  
The original English text is concise and simply states an action: "Sends %1 to %2". The Hungarian translation "Küldés innen: %1 ide: %2" translates back as "Sending from: %1 to: %2", which adds words ("innen" = "from here", "ide" = "to here") not present in the source and changes the style from a simple verb phrase to a noun phrase with added details. It does not match the original meaning or format.

A correct Hungarian translation should be a simple verb phrase matching the original style and preserving placeholders without added words or colons:

Correct translation:  
"Küld %1-et %2-nek"  

(Note: Depending on context, "küld" is the verb "send(s)" in present tense; the suffixes "-et" and "-nek" indicate object and indirect object/case respectively, which fit typical Hungarian usage for "send %1 to %2". If %1 and %2 represent addresses or amounts, this form is most natural.)
```

```
        <source>Mapped AS</source>
        <translation>Leképezett AR</translation>
    
YES
The abbreviation "AS" in the context of Bitcoin or networking likely refers to "Autonomous System," which is commonly left as "AS" in Hungarian technical texts rather than translated to "AR." The translation "Leképezett AR" is incorrect because "AR" is not a proper or recognized abbreviation for "AS" in Hungarian. 

Correct translation:
Leképezett AS
```

```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>Eldobott címek</translation>
    
YES
The English source "Addresses Rate-Limited" refers specifically to Bitcoin addresses that have been limited (rate-limited), meaning the system intentionally restricts their processing to avoid abuse. The Hungarian translation "Eldobott címek" means "Dropped addresses," which shifts the nuance from "rate-limited" (throttled or limited) to simply "discarded," losing the technical meaning and could be misleading.

A more accurate translation that preserves the specificity of "rate-limited" would be:

"Rate-korlátozott címek"
```

```
        <source>Could not generate new %1 address</source>
        <translation>Cím előállítása sikertelen %1 </translation>
    
YES
The original source text "Could not generate new %1 address" should explicitly mention "new" and keep the placeholder %1 close to the word "address." The Hungarian translation omits the word "new" (új) and places %1 at the end detached from "Cím" (address), which may cause confusion. Also, there is a trailing space after %1 that should be removed.

Correct translation:
„Nem sikerült új %1 cím generálása”
```

```
        <source>You can sign messages/agreements with your legacy (P2PKH) addresses to prove you can receive bitcoins sent to them. Be careful not to sign anything vague or random, as phishing attacks may try to trick you into signing your identity over to them. Only sign fully-detailed statements you agree to.</source>
        <translation>Aláírhat üzeneteket/megállapodásokat a régí típusú (P2PKH) címeivel amivel bizonyítja, hogy fogadni és elkölteni is tudja az oda küldött bitcoint. Legyen óvatos és ne írjon alá semmilyen ködös vagy véletlenszerű üzenetet, mivel adathalászok megkísérelhetik rávenni a személyazonosságának átruházására. Csak olyan alaposan részletezett állításokat írjon alá amivel teljesen egyetért.</translation>
    
YES  
There are some errors and awkward phrasing in the Hungarian translation that need correction:

1. "régí" should be "régi" (correct spelling).
2. The phrase "amivel bizonyítja, hogy fogadni és elkölteni is tudja az oda küldött bitcoint." is problematic:
   - The source only says you can prove you can receive bitcoins sent to the address, not spend them.
   - Also, "elkölteni" (to spend) is not mentioned in the source and might be misleading.
3. Missing commas for better readability.
4. The phrase "rávenni a személyazonosságának átruházására" is awkward and incorrect Hungarian. It should be something like "rávenni, hogy aláírja azonosítóját".
5. "alaposan részletezett állításokat" is a bit unnatural — better is "teljes körű részleteket tartalmazó nyilatkozatokat".
6. Also, the sentence splitting and flow could be improved.

Corrected translation:

Aláírhat üzeneteket/megállapodásokat a régi típusú (P2PKH) címeivel, hogy bizonyítsa: fogadni tudja az oda küldött bitcoinokat. Legyen óvatos, és ne írjon alá semmilyen homályos vagy véletlenszerű üzenetet, mivel adathalászok megkísérelhetik rávenni, hogy aláírja személyazonosságát. Csak olyan, teljes körű részleteket tartalmazó nyilatkozatokat írjon alá, amelyekkel egyetért.

(Note: "%"-prefixed format specifiers are not present, so no check needed.)
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/megerősítetlen</translation>
    
YES  
The Hungarian word for "unconfirmed" is "megerősítetlen", but the slash (/) should have a space before and after or be replaced with a suitable separator for better readability. However, since the source uses "%1/unconfirmed" without spaces, it is acceptable to keep the slash without spaces to match formatting exactly. The main issue is that Hungarian often uses a hyphen (-) instead of a slash to separate values or states.

That said, the translation "%1/megerősítetlen" is understandable but better practice might be to use a hyphen or a space around the slash to improve clarity.

Correct translation:  
%1/megerősítetlen

No format specifier issues and no extra whitespace detected. Given the source uses a slash without spaces, this translation matches formatting well.

Final verdict: NO
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>Érvénytelen összeg: %s=&lt;amount&gt;: '%s' (legalább a minrelay összeg azaz %s kell legyen, hogy ne ragadjon be a tranzakció)</translation>
    
YES  
The order and structure of the placeholders and text do not precisely match the original source, which may cause confusion. In the source, the placeholder %s=&lt;amount&gt; is shown first, followed by the invalid amount value '%s'. The Hungarian translation places these placeholders in a different order, starting with "Érvénytelen összeg: %s=&lt;amount&gt;: '%s'". Also, the phrase "legalább a minrelay összeg azaz %s kell legyen" is awkwardly phrased and can be improved for clarity and fluency.

Correct translation:  
Érvénytelen összeg %s=&lt;amount&gt;: '%s' (legalább a %s minimális továbbítási díjnak kell lennie, hogy elkerülhető legyen a tranzakció elakadása)
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>A tranzakcióhoz szükség van visszajáró címekre, de nem lehet előállítani egyet.</translation>
    
YES
The source text uses the singular "a change address," but the translation uses the plural "visszajáró címekre" ("change addresses"), which alters the meaning. Additionally, "előállítani" ("to produce/generate") is acceptable but a more natural wording would use "létrehozni" ("to create/generate").

Correct translation:
A tranzakcióhoz szükség van egy visszajáró címre, de nem tudunk létrehozni egyet.
```
</details>
