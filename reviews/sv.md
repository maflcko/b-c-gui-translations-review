# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sv</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsv%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation>Adresi veya etiketi düzenlemek için sağ tıklayın.</translation>
    
YES, The provided translation is in Turkish, not Swedish ('sv').
UNK_LANG
```

```
        <source>Choose the address to send coins to</source>
        <translation>Välj en adress att skicka transaktionen till</translation>
    
YES, The translation is inaccurate and potentially misleading. While "transaktionen" can be used in a Bitcoin context, "coins" is directly translated to "mynt" which is not typically used in this context in Swedish. The source text refers to sending coins to an address, not sending the transaction itself.

A more accurate translation would be:

Välj adressen att skicka mynt till
```

```
        <source>Choose the address to receive coins with</source>
        <translation>Välj en adress att ` emot transaktionen med</translation>
    
YES: The translation contains a grammatical error and a typo. The word "emot" should be "mottaga" (receive) or "ta emot" (receive). Also, the backtick around "emot" is unnecessary.
Välj en adress att ta emot transaktionen med
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Konfigurationsfil %1 verkar vara korrupt</translation>
    
YES, The translation is missing the word "invalid" from the source text.
Konfigurationsfil %1 verkar vara korrupt eller ogiltig.
```

```
        <source>Restore a wallet from a backup file</source>
        <extracomment>Status tip for Restore Wallet menu item</extracomment>
        <translation>Återställt en plånbok från en backup-fil</translation>
    
YES: The translation uses the past tense ("Återställt") which is incorrect for a status tip describing an action that can be performed. The correct tense is the infinitive.
Återställ en plånbok från en backup-fil
```

```
        <source>Hide</source>
        <translation>och göm</translation>
    
YES, The translation is problematic because "och göm" means "and hide" which is not a direct translation for "Hide".
The correct translation should be "Göm".
```

```
        <source>Pre-syncing Headers (%1%)…</source>
        <translation>Förhandsinkoppling av rubriker ( %1 %)...</translation>
    
YES, The translation uses "inkoppling" which means connection in Swedish. However, in the context of Bitcoin, "Pre-syncing Headers" refers to the process of downloading and validating the block headers before syncing the entire blockchain. The more appropriate translation would be "Försynkronisering av rubriker".
Additionally, there are unnecessary spaces around the format specifier %1%.

NO.
The translation has an extra space before and after the format specifier %1%. The word "inkoppling" is not the best fit for "syncing" in this context; "synkronisering" is a better choice.

Correct translation: Försynkronisering av rubriker (%1 %)...
```

```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>Migrering av plånboken kommer att konvertera denna plånbok till en eller flera deskriptorplånböcker. En ny säkerhetskopia av plånboken måste skapas.
Om den här plånboken innehåller watchonly-skript skapas en ny plånbok som innehåller dessa watchonly-skript.
Om den här plånboken innehåller lösbara</translation>
    
YES, The translation is incomplete.
Migrering av plånboken kommer att konvertera denna plånbok till en eller flera deskriptorplånböcker. En ny säkerhetskopia av plånboken måste skapas.
Om den här plånboken innehåller watchonly-skript skapas en ny plånbok som innehåller dessa watchonly-skript.
Om den här plånboken innehåller lösbara men ej bevakade skript skapas en annan och ny plånbok som innehåller dessa skript.

Migreringsprocessen skapar en säkerhetskopia av plånboken före migreringen. Denna säkerhetskopia fil namnges &lt;plånboksnamn&gt;-&lt;tidsstämpel&gt;.legacy.bak och kan hittas i katalogen för denna plånbok. I händelse av en felaktig migrering kan säkerhetskopian återställas med funktionen "Återställ plånbok".
```

```
        <source>The wallet '%1' was migrated successfully.</source>
        <translation>Migrering av plånboken ' %1 ' genomförd.</translation>
    
YES: The translation has an extraneous space before the format specifier '%1'.
Migrering av plånboken '%1' genomförd.
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Minst %1 GB data kommer att sparas i den här katalogen, och de växer över tiden.</translation>
    
YES: The verb "växer" (grow) is in the present tense and is used in singular form. The subject "de" (they) is plural and refers to "data". The correct verb form should be "växer" (grow) in the singular form, or alternatively, the subject should be pluralised. However, the most natural way to express this in Swedish would be to use the singular verb form "växer" with the singular noun "katalogen" as the implicit subject. Alternatively, "de" could refer to "data", which is a plural noun in English, but it's often treated as singular in Swedish when referring to a collection of data. Given the context of a directory, "katalogen" is a more likely referent. The corrected sentence uses "den" to refer to "katalogen" and makes the verb agree in number: "och den växer över tiden."
Minst %1 GB data kommer att sparas i den här katalogen, och den växer över tiden.
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Vid avstängning av denna inställning kommer den fullständiga blockkedjan behövas laddas ned igen.</translation>
    
YES: The translation incorrectly states that the blockchain needs to be downloaded again when the setting is *turned off* ("avstängning"). The English source text clearly indicates this is required when *reverting* the setting, implying a change back to a previous state or disabling the setting if it was previously enabled. A more accurate translation would convey this intended meaning.

Reverting this setting requires re-downloading the entire blockchain.
Vid återställning av denna inställning kommer den fullständiga blockkedjan behöva laddas ned igen.
```

```
        <source>Immature:</source>
        <translation>Omogen:</translation>
    
YES, the translation is problematic. The Swedish word "Omogen" translates to "immature" in English in the context of something not being fully developed or ready, which is an accurate translation. However, in the context of Bitcoin, "immature" refers to a transaction that has not yet been confirmed by the network. The correct Swedish translation for this context would be "Oavgjord" or "Oavslutad".

"Omogen" would be more appropriate for describing a person or a fruit that is not ripe.

NO
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>Privat läge aktiverad för fliken Översikt. För att visa data, bocka ur Inställningar &gt; Dölj data.</translation>
    
YES - The translation uses "visa data" which is a bit vague and could be improved. The original text specifically mentions "unmask the values". Also, "bocka ur" means "uncheck" which is correct, but it's often better to use a more direct translation like "avmarkera" or "ta bort markeringen".

Correct translation: Privat läge aktiverat för fliken Översikt. För att visa värdena, avmarkera Inställningar &gt; Dölj värden.
```

```
        <source>Transaction has %1 unsigned inputs.</source>
        <translation>Transaktion %1 har osignerad indata.</translation>
    
YES, the translation is problematic. The word order is incorrect in Swedish. "Transaktion %1 har osignerad indata" should be "Transaktionen %1 har osignerade indata" or "Transaktionen har %1 osignerade indata". The word "indata" is plural in the source text so it should be plural in the translation as well.

NO.
The translation is problematic. The word order and pluralization are incorrect. The word "indata" is in singular form in Swedish, but the source text is in plural form.

Correct translation: "Transaktionen %1 har osignerade indata."
```

```
        <source>(But no wallet is loaded.)</source>
        <translation>&lt;br&gt;(</translation>
    
YES. The translation is incomplete and contains extraneous HTML.
&lt;br&gt;(Men ingen plånbok är laddad.)
```

```
        <source>Ban for</source>
        <translation>Bannlys i</translation>
    
YES
The translation is inaccurate and doesn't convey the intended meaning. "Ban for" in the context of Bitcoin likely refers to a ban *related to* or *because of* something, not a ban *in* a specific location.

Correct translation: "Bannlysning för"
```

```
        <source>Payment information</source>
        <translation>Betalinformaton</translation>
    
YES, The translation has a spelling error. The word "Betalinformaton" should be "Betalningsinformation".
Betalningsinformation
```

```
        <source>%1 (%2 blocks)</source>
        <translation>%1 (%2 block)</translation>
    
YES: The translation has a grammatical error. The source text uses the plural "blocks" while the translation uses the singular "block".
Correct translation: %1 (%2 block)
```

```
        <source>The amount to send in the selected unit</source>
        <translation>Beloppett att skicka i vald enhet</translation>
    
YES: The Swedish translation contains a spelling error. The correct spelling for "amount" is "beloppet".
Beloppet att skicka i vald enhet
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Detta är transaktionsavgiften som slängs borta om det är mindre än damm på denna nivå</translation>
    
YES: The translation uses "slängs borta" which translates to "is thrown away" or "is discarded". The original English text uses "discard" to mean that the fee can be ignored or treated as negligible, not necessarily physically thrown away. A more accurate translation would be "kan ignoreras" or "kan avfärdas".

Correct translation: Detta är transaktionsavgiften som kan ignoreras om växeln är mindre än damm på denna nivå
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Varning: Privata nycklar upptäcktes i plånbok (%s) vilken har dessa inaktiverade</translation>
    
YES: The Swedish translation uses the word "vilken" which can be translated to "which" or "who". In this context, it refers to the wallet, which is an inanimate object. Therefore, "som" (which/that) would be a more appropriate word. The phrase "har dessa inaktiverade" can be translated to "has these disabled", which is a bit awkward. A more natural phrasing would be "med inaktiverade privata nycklar" (with disabled private keys).

Varning: Privata nycklar upptäcktes i plånbok (%s) med inaktiverade privata nycklar
```

```
        <source>Maximum transaction weight is too low, can not accommodate change output</source>
        <translation>Maximal transaktionsvikt är för låg, kan inte tillgodose ändrad utdata</translation>
    
YES: The word "ändrad" in the translation means "changed" or "modified", but in the context of Bitcoin transactions, "change" refers to the "change output" or "växlingsutdata" which is the money returned to the sender.
Maximal transaktionsvikt är för låg, kan inte tillgodose växlingsutdata
```

```
        <source>Insufficient funds</source>
        <translation>Otillräckligt med bitcoins</translation>
    
YES, The translation is too specific to "bitcoins". While the context is Bitcoin, "insufficient funds" is a general term that can be translated more broadly to "Otillräckligt med medel" or "Otillräckliga medel".
Otillräckliga medel
```

```
        <source>Need to specify a port with -whitebind: '%s'</source>
        <translation>Port måste anges med -whitelist: '%s'</translation>
    
YES - The translation contains an error. The English source specifies "-whitebind", but the Swedish translation uses "-whitelist". The correct translation should reflect "-whitebind".

NO
```

```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Plånboken behöver sparas om: Starta om %s för att fullfölja</translation>
    
YES
The translation is problematic because "sparas om" means "saved again" or "re-saved" which is not the same as "rewritten". The phrase "sparas om" implies that the wallet was saved in some way and now needs to be saved again. The English phrase "rewritten" suggests that the wallet data itself needs to be completely rewritten, which is a different meaning.

A more accurate translation would be:
Plånboken behöver skrivas om: starta om %s för att slutföra
```
</details>
