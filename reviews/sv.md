# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sv</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsv%5D%20low%20quality)


<!-- cache_translation_check_sv_7b1dfbb573001ce6cac2f074c1546588524aa8b799b115d380def8d2cda23b5b -->
```
        <source>Right-click to edit address or label</source>
        <translation>Adresi veya etiketi düzenlemek için sağ tıklayın.</translation>
    
SPAM
The translation provided is in Turkish, not Swedish ('sv').

Correct translation:
Högerklicka för att redigera adress eller etikett
```

<!-- cache_translation_check_sv_1de2b1efbb7a2a6b94a1adac830e5d85109fbf2a0976ba56c224cd05a3cd4bd6 -->
```
        <source>Choose the address to send coins to</source>
        <translation>Välj en adress att skicka transaktionen till</translation>
    
ERR
The translation incorrectly specifies "skicka transaktionen" ("send the transaction") rather than "skicka mynt" ("send coins"). It also adds "en" ("an address"), which is not present in the source.

Correct translation:
Välj adressen att skicka mynt till
```

<!-- cache_translation_check_sv_14478ccc02cf3135745b8ef23b0ea352f8f5e71d387139a30ee2667d92667799 -->
```
        <source>Choose the address to receive coins with</source>
        <translation>Välj en adress att ` emot transaktionen med</translation>
    
ERR
There is an erroneous backtick (`) in "att ` emot", and "emot transaktionen" (receive the transaction) is not as accurate as "ta emot mynt" (receive coins). Also, "address" is indefinite in the source, so "en adress" is okay, but "att ta emot" should not be split up. Correct translation:

Välj den adress du vill ta emot mynt med
```

<!-- cache_translation_check_sv_c83ebb65f87b9ea003dcfc44b1b1ff52c17f82ae59beb54b4d72309e498641a3 -->
```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Konfigurationsfil %1 verkar vara korrupt</translation>
    
ERR
The translation omits "or invalid" from the original meaning. It should also be "konfigurationsfil" with two n's, not "konfigurationsfil".

Correct translation:
Inställningsfilen %1 kan vara korrupt eller ogiltig.
```

<!-- cache_translation_check_sv_c37d3bf5b754554af9a869ab5e994b54ecd2f92404d593dd335dcbf77387e3cb -->
```
        <source>Restore a wallet from a backup file</source>
        <extracomment>Status tip for Restore Wallet menu item</extracomment>
        <translation>Återställt en plånbok från en backup-fil</translation>
    
ERR
The translation is incorrect. The Swedish phrase "Återställt en plånbok från en backup-fil" means "Restored a wallet from a backup file" (past tense), while the English source is an instruction or option in present/future ("Restore a wallet from a backup file"). The translation should use imperative or infinitive form.

Correct translation:
Återställ en plånbok från en backup-fil
```

<!-- cache_translation_check_sv_b9108ffe390ce5b4cd7c9ce85f6ef3eed8b6d9acf125840115e77d0e1fc09a15 -->
```
        <source>Hide</source>
        <translation>och göm</translation>
    
ERR
The translation is incorrect. The English word "Hide" should be translated as "Dölj" in Swedish. "och göm" means "and hide" or "and conceal", which adds unwanted content.

Correct translation:
Dölj
```

<!-- cache_translation_check_sv_382d4bd65681678c2d0de7dea5f123d9b60dc6f0e0c39a12febee685bfa09fef -->
```
        <source>Pre-syncing Headers (%1%)…</source>
        <translation>Förhandsinkoppling av rubriker ( %1 %)...</translation>
    
ERR
The translation is problematic: 
1. The format specifier %1 should not be surrounded by spaces unless present in the source.
2. The English word "Headers" in this Bitcoin context is better translated as "blockhuvuden" or "huvuden" rather than "rubriker" (which usually means "headlines" or "titles" in Swedish).
3. Pre-syncing is more naturally translated as "Försynkroniserar" or "Försynkronisering av".
4. The ellipsis should use the unicode character "…" as in the source, not three dots "...".

Correct translation:
Försynkroniserar blockhuvuden (%1)…
```

<!-- cache_translation_check_sv_26ef454e69889d84282eb5f6f40495ac36d145468a414b51d2a9a269921728b4 -->
```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>Migrering av plånboken kommer att konvertera denna plånbok till en eller flera deskriptorplånböcker. En ny säkerhetskopia av plånboken måste skapas.
Om den här plånboken innehåller watchonly-skript skapas en ny plånbok som innehåller dessa watchonly-skript.
Om den här plånboken innehåller lösbara</translation>
    
ERR
The Swedish translation is incomplete; it ends abruptly after "innehåller lösbara", which omits the remainder of the English text. This truncation leads to loss of crucial information about "solvable but not watched scripts", the migration process, backup file naming, and restoration instructions.

Correct translation:
Migrering av plånboken kommer att konvertera denna plånbok till en eller flera deskriptorplånböcker. En ny säkerhetskopia av plånboken måste skapas.  
Om den här plånboken innehåller några "watchonly"-skript skapas en ny plånbok som innehåller dessa "watchonly"-skript.  
Om den här plånboken innehåller några lösbara men ej övervakade ("watched") skript, kommer en annan ny plånbok att skapas som innehåller dessa skript.  

Migrationsprocessen skapar en säkerhetskopia av plånboken innan migreringen. Denna säkerhetskopia namnges &lt;plånboksnamn&gt;-&lt;tidsstämpel&gt;.legacy.bak och kan hittas i katalogen för denna plånbok. Vid felaktig migrering kan säkerhetskopian återställas med funktionen "Återställ plånbok".
```

<!-- cache_translation_check_sv_52d74c10f72b6b7d7d08133bda37d88bec5b395515dd572bbca72b71e8a706cc -->
```
        <source>The wallet '%1' was migrated successfully.</source>
        <translation>Migrering av plånboken ' %1 ' genomförd.</translation>
    
ERR
There are unnecessary spaces inside the single quotes around %1. In Swedish, this is uncommon, and the format should be consistent with the source. Also, "genomförd" on its own is a little less direct than "lyckades" or "har slutförts" for "was migrated successfully", but it's acceptable. For clarity and correctness, it should be:

Correct translation:
Migreringen av plånboken '%1' slutfördes framgångsrikt.
```

<!-- cache_translation_check_sv_ec9c152f7f16ecf8e4db954bd12133dfc74b4daea21965da1e31c1345d2dce5b -->
```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Minst %1 GB data kommer att sparas i den här katalogen, och de växer över tiden.</translation>
    
ERR
The pronoun "de" ("they") in "och de växer över tiden" is incorrect; it refers to "data" in plural, but what will grow is the stored amount, not the "data" as a countable object. Furthermore, "över tiden" is a less common way to say "over time"; "med tiden" is more idiomatic. The English "it will grow" refers to the storage requirement, not to the data.

Correct translation:
Minst %1 GB data kommer att sparas i den här katalogen, och det kommer att öka med tiden.
```

<!-- cache_translation_check_sv_4c170594bc0f45e41bb3db1451c54c7d02fc4a9aa86efb564cfbeb4d94097a1a -->
```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Vid avstängning av denna inställning kommer den fullständiga blockkedjan behövas laddas ned igen.</translation>
    
ERR
The translation is understandable but not entirely accurate. The English says "Reverting this setting requires re-downloading the entire blockchain," which means if you change the setting back, you have to re-download the blockchain. The Swedish translation instead says "When disabling this setting, the entire blockchain will need to be downloaded again," changing the nuance from "reverting" (could be enable or disable) to specifically "turning off" (disable).

Correct translation:
Att återställa denna inställning kräver att hela blockkedjan laddas ned igen.
```

<!-- cache_translation_check_sv_c2485671d7ccb597a37bbcf6b5039d45fb35b70d56c4928364ec7bf7de41d03d -->
```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>Privat läge aktiverad för fliken Översikt. För att visa data, bocka ur Inställningar &gt; Dölj data.</translation>
    
ERR
There is a minor issue: "Privat läge" should be one word, "Privatl&auml;ge". "Visa data" is a good paraphrase for "unmask the values", and "bocka ur Inställningar > Dölj data" is acceptable, though "värden" would be more accurate than "data" for "values".

Correct translation:
Privatläge aktiverat för fliken Översikt. För att visa värden, bocka ur Inställningar &gt; Dölj värden.
```

<!-- cache_translation_check_sv_77eec5cead6962357d36a92f3992204b6a2d145c2bca7111bb2e08a2d636319e -->
```
        <source>Transaction has %1 unsigned inputs.</source>
        <translation>Transaktion %1 har osignerad indata.</translation>
    
ERR
The translation is incorrect and does not accurately reflect the plural ("inputs") and structure of the source sentence. "%1" should indicate the number of unsigned inputs and appears before "osignerad indata", making the sentence unclear.

Correct translation:
Transaktionen har %1 osignerade indata.
```

<!-- cache_translation_check_sv_239204eda8d83110bcd428a85b5744e3b73b52a1407018421f2bed02eef3cb2a -->
```
        <source>(But no wallet is loaded.)</source>
        <translation>&lt;br&gt;(</translation>
    
SPAM
The translation does not correspond at all to the source text. It only contains an HTML break tag and an opening parenthesis, rather than a Swedish translation.

Correct translation:
(Men ingen plånbok är laddad.)
```

<!-- cache_translation_check_sv_53f4a1b69b4ce626e1084ffcafca68796a7bbd9fbe285d3178bb08ca0b995b4f -->
```
        <source>Payment information</source>
        <translation>Betalinformaton</translation>
    
ERR
There is a spelling error in the Swedish translation. "Betalinformaton" is missing an 'i' and should be "Betalinformation".

Correct translation:
Betalinformation
```

<!-- cache_translation_check_sv_4447364a6c1df9143779440d73656bc4bb03b005fb08c35d44b0042622ac4563 -->
```
        <source>%1 (%2 blocks)</source>
        <translation>%1 (%2 block)</translation>
    
ERR
The plural form "blocks" should be translated as "block" in singular ("ett block") or "block" in plural ("block" is both singular and plural in Swedish, but the article changes), but considering the context "(%2 blocks)" should be translated as "(%2 block)" only when %2 > 1. For this generic UI string, the translation is acceptable, but for clarity, it's better Swedish to write "%1 (%2 block)" for plural.

Explanation:
"block" is both singular and plural in Swedish, but to be more natural, using "%2 block" is correct—so the translation is fine in terms of grammar.

So: NO

But since the singular/plural is not affected in Swedish, this translation is in fact unproblematic.

NO
```

<!-- cache_translation_check_sv_ea8d5f81415e19fd936c334cdf2f8e969252866a7b755b1e56ebb14342af6f75 -->
```
        <source>The amount to send in the selected unit</source>
        <translation>Beloppett att skicka i vald enhet</translation>
    
ERR
There is a typo in the translation: "Beloppett" should be "Beloppet" (with one 't').

Correct translation:
Beloppet att skicka i vald enhet
```

<!-- cache_translation_check_sv_cdf55f5513b3685c5a16a4aa4048cb893d48a0b3e94022b425b37995aaac24e7 -->
```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Detta är transaktionsavgiften som slängs borta om det är mindre än damm på denna nivå</translation>
    
ERR
The translation is inaccurate and awkward. The phrase "slängs borta" is unnatural in Swedish. Also, "change" should be "växel" (referring to Bitcoin transaction change), and "damm" is generally fine but the subject is missing in the "är mindre än damm".

Correct translation:
Detta är transaktionsavgiften du kan bortse från om växeln är mindre än damm på denna nivå.
```

<!-- cache_translation_check_sv_bedb31fbdc95cc72acf54e12a02de85f956f877c2d12e741eb3114ddcf408a0b -->
```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Varning: Privata nycklar upptäcktes i plånbok (%s) vilken har dessa inaktiverade</translation>
    
ERR
There is a slight mistranslation issue. The Swedish translation "vilken har dessa inaktiverade" makes it sound like 'these' private keys are deactivated, which is not how the source reads. The source means that the wallet has the "private keys disabled" setting, not the keys themselves. Additionally, the translation uses parentheses instead of curly braces, but that's a minor formatting issue if the software supports it.

Correct translation:
Varning: Privata nycklar upptäcktes i plånboken {%s} där privata nycklar är inaktiverade
```

<!-- cache_translation_check_sv_daa1224be471b4c4ab814806809f224df7e6ac618e4de79b9d0113d09258ae62 -->
```
        <source>Maximum transaction weight is too low, can not accommodate change output</source>
        <translation>Maximal transaktionsvikt är för låg, kan inte tillgodose ändrad utdata</translation>
    
ERR
The Swedish translation incorrectly translates "change output" as "ändrad utdata". In the context of Bitcoin, "change" refers to the remaining amount returned to the sender, not "changed" output. The correct Swedish term for "change output" is "växelutgång".

Correct translation:
Maximal transaktionsvikt är för låg, kan inte tillgodose växelutgång
```

<!-- cache_translation_check_sv_7c58e5217c8b511a0faa7d3e4f7c87151030e90b7371a34e19e0fd4f745fed62 -->
```
        <source>Insufficient funds</source>
        <translation>Otillräckligt med bitcoins</translation>
    
ERR
The translation is incorrect. "Otillräckligt med bitcoins" literally means "Insufficient with bitcoins," which is not idiomatic Swedish and could also be misunderstood as "enough" due to "med". The standard and clear translation would be:

Correct translation:
Otillräckliga medel
```

<!-- cache_translation_check_sv_a8ecb7dd3413d5225573dde49f2abd3ffc744d29c0db4a592a9c77c21f1a8434 -->
```
        <source>Need to specify a port with -whitebind: '%s'</source>
        <translation>Port måste anges med -whitelist: '%s'</translation>
    
ERR
The translation uses "-whitelist" instead of the correct switch "-whitebind" as in the source. This is an erroneous translation that may mislead users.

Correct translation:
Port måste anges med -whitebind: '%s'
```
</details>

Number of issues: 22.
