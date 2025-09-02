# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>sv</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bsv%5D%20request)


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

<!-- cache_translation_check_sv_f6bb2e9be805e096f33c6ab83f3ee93c7f54b4acc250dc0efa1bb3adeef75317 -->
```
        <source>&amp;Options…</source>
        <translation>&amp;Inställningar</translation>
    
ERR
The translation is missing the ellipsis (…) present in the source. The ampersand is used correctly and spacing is fine.

Correct translation:
&amp;Inställningar…
```

<!-- cache_translation_check_sv_10b0ff6066d2931158cf134945b06bb6220dddcee428046ae9db789ce7d4ffd4 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>&amp;Säkerhetskopiera plånbok...</translation>
    
ERR
Issues:
- The translation uses three ASCII dots "..." instead of the single Unicode ellipsis character "…". The source uses "…" so the translation should match.
- Slightly more natural Swedish would use the definite form "plånboken" ("the wallet") in this UI context.

Correct translation:
&amp;Säkerhetskopiera plånboken…
```

<!-- cache_translation_check_sv_677448fb6e26547661be547036b18bff08d0065f31639a06e74388d593ee641c -->
```
        <source>&amp;Verify message…</source>
        <translation>&amp;Bekräfta meddelandet…</translation>
    
ERR
The Swedish word "Bekräfta" means "confirm" rather than "verify"; a more accurate translation in the Bitcoin context is "Verifiera". The ampersand and ellipsis are present and spacing is fine.

Correct translation:
&Verifiera meddelande…
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

<!-- cache_translation_check_sv_51d70f6ad03f0ef4bbddf7fad8e4408e08a5655ec1c936bdfae30a529b55611c -->
```
        <source>&amp;Hide</source>
        <translation>och göm</translation>
    
ERR
The Swedish translation is incorrect. "och göm" means "and hide" and does not include the required shortcut ampersand. It also uses lowercase and adds an extra word ("och") that is not in the source.

Correct translation (with single & for the shortcut):
&göm

Alternatively using a more common verb form:
&Dölj
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

<!-- cache_translation_check_sv_040262e037d986b626673915fca7f275d3ca09919a6db2c15f1324b01060e859 -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>Kopiera transaktion &amp;ID och utdatindex</translation>
    
ERR
Problems:
- Typo: "utdatindex" should be "utdataindex" or better "utgångsindex".
- The compound "transaktion &ID" is awkward; in Swedish it should be "transaktions-ID".
- The translation uses "&amp;ID" (HTML-escaped ampersand) but the ampersand must appear exactly once; it's okay to keep one ampersand for the shortcut, but placement and wording should be fixed.

Correct translation (with one shortcut ampersand placed at the start):
&Kopiera transaktions-ID och utgångsindex
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

<!-- cache_translation_check_sv_2c577c82c31c070ac7074ca1001400e074ce3b4851b3efcbf4c444f63c75f5f6 -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>Antalet skript&amp;verifikationstrådar</translation>
    
ERR
The Swedish is understandable but slightly awkward and has minor issues:
- "Antalet" is less typical in UI labels than "Antal".
- "verifikation" is less common than "verifiering" in this context.
- The spacing around the & shortcut marker differs from the source (recommend placing it where desired), and the translation should use exactly one & (encoded as &amp; in XML).

Suggested correction (two alternatives you can use depending on preferred style):

1) Compound form:
Antal skript&amp;verifieringstrådar

2) More explicit:
Antal trådar för skript&amp;verifiering
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

<!-- cache_translation_check_sv_f451684b668c24eca17ec552772270e0fec85a76e34a08bfea78ad5361c669da -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Ta bort avgift från summa som standard</translation>
    
ERR
Issues:
- Missing shortcut indicator (&). The source has "&fee" so the translation must include a single & before the word for the shortcut.
- Word choice and phrasing: "Ta bort" means "remove" rather than "subtract"; "summa" is less precise than "beloppet" in this context. More natural Swedish is "Dra av ... från beloppet som standard".

Correct translation suggestions:
- Dra av &avgiften från beloppet som standard
or shorter:
- Dra av &avgift från beloppet som standard
```

<!-- cache_translation_check_sv_5238801fc3eae14db88abe3536a86bb03948b2556b813eef1e9edb17441862d4 -->
```
        <source>Enable coin &amp;control features</source>
        <translation>Aktivera mynt&amp;kontrollfunktioner</translation>
    
ERR
The translation is understandable but has formatting/spacing issues: the ampersand is glued to the words ("mynt&amp;kontrollfunktioner") which is awkward in Swedish. A more natural translation with the & present exactly once is:

Aktivera mynt &amp; kontrollfunktioner
```

<!-- cache_translation_check_sv_1c33ce07b974fb51356500742a707826673469d219a613286293f62ba321e1f2 -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Aktivera &amp;PSBT-kontroll</translation>
    
ERR
The Swedish translation uses singular "kontroll" but the source is plural "controls". Also keep the ampersand exactly once. 

Correct translation:
Aktivera &PSBT-kontroller
```

<!-- cache_translation_check_sv_203f819596a7d49c591df128a375aee88e481e312db1a0b098438289917ec7f1 -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Tillåt inkommande anslutningar</translation>
    
ERR
The translation is missing the shortcut marker (&) that exists in the source. The source contains "incomin&amp;g" which places a single & (shortcut) in the original string; the Swedish translation must include exactly one & as well.

Correct translation:
Tillåt inkommande &anslutningar
```

<!-- cache_translation_check_sv_db3f5b60da3e1ed39fc4ee4d3c66318559d4102d9a6eaecacfe54c2befc5d63f -->
```
        <source>Proxy &amp;IP:</source>
        <translation>Proxy-&amp;IP:</translation>
    
ERR
The translation inserts an unexpected hyphen ("Proxy-&amp;IP:") that changes the label formatting compared with the source. The ampersand (shortcut marker) should be preserved without adding extra punctuation. Also keep the ampersand exactly once.

Correct translation:
Proxy &amp;IP:
```

<!-- cache_translation_check_sv_f0e13d2720e6800223a60df2a2ef6b5a9ee811df24b6bdd4524d37c407e13870 -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Använd en fristående SOCKS&amp;5 proxy för att  nå noder via Tor onion tjänster:</translation>
    
ERR
The translation has a double space between "att" and "nå" and could improve wording/compound formation ("onion tjänster" should be hyphenated or combined). Keep the single &amp; exactly as in source.

Correct translation:
Använd en separat SOCKS&amp;5-proxy för att nå noder via Tor .onion-tjänster:
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

<!-- cache_translation_check_sv_a143c9b5e229fe8b4de5b0c257b14cb1f3b03b9ad8d8b3ae02d00b8b46d73b33 -->
```
        <source>1 d&amp;ay</source>
        <translation>1d&amp;ag</translation>
    
ERR
Whitespace error: the translation is missing the space between the numeral and the word. The ampersand/shortcut placement is fine (before the 'a' in 'dag').

Correct translation:
1 d&amp;ag
```

<!-- cache_translation_check_sv_004caaa63ac6d41be8038532c832dfed3389e98821a6ce659bd500e0e3277fab -->
```
        <source>&amp;Create new receiving address</source>
        <translation>S&amp;kapa ny mottagaradress</translation>
    
ERR
The ampersand (shortcut marker) is in the wrong place. The translation currently "S&amp;kapa ny mottagaradress" would render an actual '&' in the middle of the word instead of marking the accelerator. Correct translation should place the ampersand before the mnemonic letter (encoded as &amp; in XML):

Correct translation:
&amp;Skapa ny mottagaradress
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

<!-- cache_translation_check_sv_8ce7a36d86c32292237ee7e0c4072cc228de7de74bdd3247bb387e4f657e801b -->
```
        <source>Cr&amp;eate Unsigned</source>
        <translation>Sk&amp;apa Osignerad</translation>
    
ERR
The Swedish is mostly correct, but "Osignerad" should be lowercase ("osignerad") to match Swedish casing conventions. The ampersand shortcut is present exactly once which is fine.

Correct translation:
<translation>Sk&amp;apa osignerad</translation>
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

<!-- cache_translation_check_sv_d83e42a626affd0d8f633844a3e2825836b56cf00d76270dcea5e6ef20d8fd95 -->
```
        <source>Copy transaction &amp;ID</source>
        <translation>Kopiera transaktions &amp;ID</translation>
    
ERR
The Swedish is slightly unnatural: "Kopiera transaktions &amp;ID" is understandable but missing the hyphen used in Swedish for "transaktions-ID" (compound noun), and the placement of the & is awkward. Also avoid the space before the ID when using the hyphenated form.

Suggested correct translation (with ampersand kept for the same shortcut on "I"):
Kopiera transaktions-&amp;ID

Or without explicit shortcut mark:
Kopiera transaktions-ID
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

Number of issues: 37.
