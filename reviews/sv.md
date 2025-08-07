# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sv</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsv%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation>Adresi veya etiketi düzenlemek için sağ tıklayın.</translation>
    
SPAM
The translation provided is in Turkish, not Swedish ('sv').

Correct translation:
Högerklicka för att redigera adress eller etikett
```

```
        <source>Choose the address to send coins to</source>
        <translation>Välj en adress att skicka transaktionen till</translation>
    
YES
The translation incorrectly specifies "skicka transaktionen" ("send the transaction") rather than "skicka mynt" ("send coins"). It also adds "en" ("an address"), which is not present in the source.

Correct translation:
Välj adressen att skicka mynt till
```

```
        <source>Choose the address to receive coins with</source>
        <translation>Välj en adress att ` emot transaktionen med</translation>
    
YES
There is an erroneous backtick (`) in "att ` emot", and "emot transaktionen" (receive the transaction) is not as accurate as "ta emot mynt" (receive coins). Also, "address" is indefinite in the source, so "en adress" is okay, but "att ta emot" should not be split up. Correct translation:

Välj den adress du vill ta emot mynt med
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Konfigurationsfil %1 verkar vara korrupt</translation>
    
YES
The translation omits "or invalid" from the original meaning. It should also be "konfigurationsfil" with two n's, not "konfigurationsfil".

Correct translation:
Inställningsfilen %1 kan vara korrupt eller ogiltig.
```

```
        <source>Restore a wallet from a backup file</source>
        <extracomment>Status tip for Restore Wallet menu item</extracomment>
        <translation>Återställt en plånbok från en backup-fil</translation>
    
YES
The translation is incorrect. The Swedish phrase "Återställt en plånbok från en backup-fil" means "Restored a wallet from a backup file" (past tense), while the English source is an instruction or option in present/future ("Restore a wallet from a backup file"). The translation should use imperative or infinitive form.

Correct translation:
Återställ en plånbok från en backup-fil
```

```
        <source>Hide</source>
        <translation>och göm</translation>
    
YES
The translation is incorrect. The English word "Hide" should be translated as "Dölj" in Swedish. "och göm" means "and hide" or "and conceal", which adds unwanted content.

Correct translation:
Dölj
```

```
        <source>Pre-syncing Headers (%1%)…</source>
        <translation>Förhandsinkoppling av rubriker ( %1 %)...</translation>
    
YES
The translation is problematic: 
1. The format specifier %1 should not be surrounded by spaces unless present in the source.
2. The English word "Headers" in this Bitcoin context is better translated as "blockhuvuden" or "huvuden" rather than "rubriker" (which usually means "headlines" or "titles" in Swedish).
3. Pre-syncing is more naturally translated as "Försynkroniserar" or "Försynkronisering av".
4. The ellipsis should use the unicode character "…" as in the source, not three dots "...".

Correct translation:
Försynkroniserar blockhuvuden (%1)…
```

```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>Migrering av plånboken kommer att konvertera denna plånbok till en eller flera deskriptorplånböcker. En ny säkerhetskopia av plånboken måste skapas.
Om den här plånboken innehåller watchonly-skript skapas en ny plånbok som innehåller dessa watchonly-skript.
Om den här plånboken innehåller lösbara</translation>
    
YES
The Swedish translation is incomplete; it ends abruptly after "innehåller lösbara", which omits the remainder of the English text. This truncation leads to loss of crucial information about "solvable but not watched scripts", the migration process, backup file naming, and restoration instructions.

Correct translation:
Migrering av plånboken kommer att konvertera denna plånbok till en eller flera deskriptorplånböcker. En ny säkerhetskopia av plånboken måste skapas.  
Om den här plånboken innehåller några "watchonly"-skript skapas en ny plånbok som innehåller dessa "watchonly"-skript.  
Om den här plånboken innehåller några lösbara men ej övervakade ("watched") skript, kommer en annan ny plånbok att skapas som innehåller dessa skript.  

Migrationsprocessen skapar en säkerhetskopia av plånboken innan migreringen. Denna säkerhetskopia namnges &lt;plånboksnamn&gt;-&lt;tidsstämpel&gt;.legacy.bak och kan hittas i katalogen för denna plånbok. Vid felaktig migrering kan säkerhetskopian återställas med funktionen "Återställ plånbok".
```

```
        <source>The wallet '%1' was migrated successfully.</source>
        <translation>Migrering av plånboken ' %1 ' genomförd.</translation>
    
YES
There are unnecessary spaces inside the single quotes around %1. In Swedish, this is uncommon, and the format should be consistent with the source. Also, "genomförd" on its own is a little less direct than "lyckades" or "har slutförts" for "was migrated successfully", but it's acceptable. For clarity and correctness, it should be:

Correct translation:
Migreringen av plånboken '%1' slutfördes framgångsrikt.
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Minst %1 GB data kommer att sparas i den här katalogen, och de växer över tiden.</translation>
    
YES
The pronoun "de" ("they") in "och de växer över tiden" is incorrect; it refers to "data" in plural, but what will grow is the stored amount, not the "data" as a countable object. Furthermore, "över tiden" is a less common way to say "over time"; "med tiden" is more idiomatic. The English "it will grow" refers to the storage requirement, not to the data.

Correct translation:
Minst %1 GB data kommer att sparas i den här katalogen, och det kommer att öka med tiden.
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Vid avstängning av denna inställning kommer den fullständiga blockkedjan behövas laddas ned igen.</translation>
    
YES
The translation is understandable but not entirely accurate. The English says "Reverting this setting requires re-downloading the entire blockchain," which means if you change the setting back, you have to re-download the blockchain. The Swedish translation instead says "When disabling this setting, the entire blockchain will need to be downloaded again," changing the nuance from "reverting" (could be enable or disable) to specifically "turning off" (disable).

Correct translation:
Att återställa denna inställning kräver att hela blockkedjan laddas ned igen.
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>Privat läge aktiverad för fliken Översikt. För att visa data, bocka ur Inställningar &gt; Dölj data.</translation>
    
YES
There is a minor issue: "Privat läge" should be one word, "Privatl&auml;ge". "Visa data" is a good paraphrase for "unmask the values", and "bocka ur Inställningar > Dölj data" is acceptable, though "värden" would be more accurate than "data" for "values".

Correct translation:
Privatläge aktiverat för fliken Översikt. För att visa värden, bocka ur Inställningar &gt; Dölj värden.
```

```
        <source>Transaction has %1 unsigned inputs.</source>
        <translation>Transaktion %1 har osignerad indata.</translation>
    
YES
The translation is incorrect and does not accurately reflect the plural ("inputs") and structure of the source sentence. "%1" should indicate the number of unsigned inputs and appears before "osignerad indata", making the sentence unclear.

Correct translation:
Transaktionen har %1 osignerade indata.
```

```
        <source>(But no wallet is loaded.)</source>
        <translation>&lt;br&gt;(</translation>
    
YES
The translation is incomplete; it only contains "<br>(" which does not accurately convey the English sentence "(But no wallet is loaded.)" in Swedish.

Correct translation:
(Men ingen plånbok är laddad.)
```

```
        <source>Payment information</source>
        <translation>Betalinformaton</translation>
    
YES
There is a spelling error in the Swedish translation. "Betalinformaton" is missing an 'i' and should be "Betalinformation".

Correct translation:
Betalinformation
```

```
        <source>%1 (%2 blocks)</source>
        <translation>%1 (%2 block)</translation>
    
YES
The plural form "blocks" should be translated as "block" in singular ("ett block") or "block" in plural ("block" is both singular and plural in Swedish, but the article changes), but considering the context "(%2 blocks)" should be translated as "(%2 block)" only when %2 > 1. For this generic UI string, the translation is acceptable, but for clarity, it's better Swedish to write "%1 (%2 block)" for plural.

Explanation:
"block" is both singular and plural in Swedish, but to be more natural, using "%2 block" is correct—so the translation is fine in terms of grammar.

So: NO

But since the singular/plural is not affected in Swedish, this translation is in fact unproblematic.

NO
```

```
        <source>The amount to send in the selected unit</source>
        <translation>Beloppett att skicka i vald enhet</translation>
    
YES
There is a typo in the translation: "Beloppett" should be "Beloppet" (with one 't').

Correct translation:
Beloppet att skicka i vald enhet
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Detta är transaktionsavgiften som slängs borta om det är mindre än damm på denna nivå</translation>
    
YES
The translation is inaccurate and awkward. The phrase "slängs borta" is unnatural in Swedish. Also, "change" should be "växel" (referring to Bitcoin transaction change), and "damm" is generally fine but the subject is missing in the "är mindre än damm".

Correct translation:
Detta är transaktionsavgiften du kan bortse från om växeln är mindre än damm på denna nivå.
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Varning: Privata nycklar upptäcktes i plånbok (%s) vilken har dessa inaktiverade</translation>
    
YES
There is a slight mistranslation issue. The Swedish translation "vilken har dessa inaktiverade" makes it sound like 'these' private keys are deactivated, which is not how the source reads. The source means that the wallet has the "private keys disabled" setting, not the keys themselves. Additionally, the translation uses parentheses instead of curly braces, but that's a minor formatting issue if the software supports it.

Correct translation:
Varning: Privata nycklar upptäcktes i plånboken {%s} där privata nycklar är inaktiverade
```

```
        <source>Maximum transaction weight is too low, can not accommodate change output</source>
        <translation>Maximal transaktionsvikt är för låg, kan inte tillgodose ändrad utdata</translation>
    
YES
The Swedish translation incorrectly translates "change output" as "ändrad utdata". In the context of Bitcoin, "change" refers to the remaining amount returned to the sender, not "changed" output. The correct Swedish term for "change output" is "växelutgång".

Correct translation:
Maximal transaktionsvikt är för låg, kan inte tillgodose växelutgång
```

```
        <source>Insufficient funds</source>
        <translation>Otillräckligt med bitcoins</translation>
    
YES
The translation is incorrect. "Otillräckligt med bitcoins" literally means "Insufficient with bitcoins," which is not idiomatic Swedish and could also be misunderstood as "enough" due to "med". The standard and clear translation would be:

Correct translation:
Otillräckliga medel
```

```
        <source>Need to specify a port with -whitebind: '%s'</source>
        <translation>Port måste anges med -whitelist: '%s'</translation>
    
YES
The translation uses "-whitelist" instead of the correct switch "-whitebind" as in the source. This is an erroneous translation that may mislead users.

Correct translation:
Port måste anges med -whitebind: '%s'
```
</details>

Number of issues: 22.
