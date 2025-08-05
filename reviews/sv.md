# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sv</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsv%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation>Adresi veya etiketi düzenlemek için sağ tıklayın.</translation>
    
YES  
The translation is in Turkish, not Swedish ('sv'). It should be in Swedish.

Correct translation:  
Högerklicka för att redigera adress eller etikett
```

```
        <source>Choose the address to send coins to</source>
        <translation>Välj en adress att skicka transaktionen till</translation>
    
YES  
The translation introduces the word "transaktionen" (the transaction), which is not present in the source text. The source only mentions "the address to send coins to," without specifying "the transaction." The correct translation should be more literal and avoid adding new elements.  

Correct translation:  
Välj den adress som du vill skicka mynt till
```

```
        <source>Choose the address to receive coins with</source>
        <translation>Välj en adress att ` emot transaktionen med</translation>
    
YES  
The Swedish translation is incorrect and contains nonsensical text: "` emot transaktionen med" is meaningless and does not correspond to the source. The source means "Choose the address to receive coins with," which should indicate selecting an address for receiving coins.

Correct translation:  
Välj en adress att ta emot mynt med
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Konfigurationsfil %1 verkar vara korrupt</translation>
    
YES  
The translation is incomplete and missing the "or invalid" part from the source text. Additionally, the Swedish word "Konfigurationsfil" is fine but it would be more natural to say "inställningsfil" for "settings file". The word "verkar" ("seems") is less direct than "kan vara" ("might be") in this context.  

Correct translation:  
Inställningsfilen %1 kan vara korrupt eller ogiltig.
```

```
        <source>Restore a wallet from a backup file</source>
        <extracomment>Status tip for Restore Wallet menu item</extracomment>
        <translation>Återställt en plånbok från en backup-fil</translation>
    
YES
The translation uses the past tense "Återställt" (restored), while the English source is an imperative/infinitive phrase "Restore." It should be in the imperative or infinitive form to match the source's intended meaning.

Correct translation:
"Återställ en plånbok från en backup-fil"
```

```
        <source>Hide</source>
        <translation>och göm</translation>
    
YES  
The translation "och göm" means "and hide," which is incorrect in this context. The source word "Hide" is a command or label and should be translated simply as "Göm" without the conjunction "och" (which means "and").  

Correct translation:  
Göm
```

```
        <source>Pre-syncing Headers (%1%)…</source>
        <translation>Förhandsinkoppling av rubriker ( %1 %)...</translation>
    
YES  
The translation has incorrect spacing around the format specifier %1 and an incorrect choice of wording. The English "Pre-syncing Headers (%1%)…" implies a process of downloading or synchronizing the headers, commonly translated as "Förhandsynkroniserar rubriker (%1%)…" or "Förinladdning av rubriker (%1%)…". Additionally, there should be no spaces inside the parentheses around %1%.

Correct translation:  
Förhandsynkroniserar rubriker (%1%)…
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
The Swedish translation is incomplete and abruptly cut off ("Om den här plånboken innehåller lösbara" without completing the sentence). This leaves the translation erroneous and unusable as is.

Correct translation:
Migrering av plånboken kommer att konvertera denna plånbok till en eller flera deskriptorplånböcker. En ny säkerhetskopia av plånboken måste skapas.
Om den här plånboken innehåller några watchonly-skript skapas en ny plånbok som innehåller dessa watchonly-skript.
Om den här plånboken innehåller några lösbara men inte övervakade skript skapas en annan och ny plånbok som innehåller dessa skript.

Migreringsprocessen kommer att skapa en säkerhetskopia av plånboken innan migreringen. Denna säkerhetskopieringsfil kommer att heta &lt;plånboksnamn&gt;-&lt;tidsstämpel&gt;.legacy.bak och kan hittas i katalogen för denna plånbok. Vid en felaktig migrering kan säkerhetskopian återställas med funktionen "Återställ plånbok".
```

```
        <source>The wallet '%1' was migrated successfully.</source>
        <translation>Migrering av plånboken ' %1 ' genomförd.</translation>
    
YES  
There are extra spaces inside the single quotes around %1 in the translation, which is inconsistent with the source. Also, the translation word order and clarity can be slightly improved.

Correct translation:  
Migreringen av plånboken '%1' genomfördes framgångsrikt.
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Minst %1 GB data kommer att sparas i den här katalogen, och de växer över tiden.</translation>
    
YES  
The translation uses the plural pronoun "de" ("they") referring to "data," which in Swedish is generally treated as singular (or uncountable) in this context. Also, "över tiden" is less common and less natural than "med tiden" or "över tid" when referring to growth over time. The correct Swedish translation should treat "data" as singular and use a more natural phrase for "over time."

Correct translation:  
Minst %1 GB data kommer att sparas i den här katalogen, och det kommer att växa med tiden.
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Vid avstängning av denna inställning kommer den fullständiga blockkedjan behövas laddas ned igen.</translation>
    
YES
The Swedish translation is somewhat awkward and does not convey the meaning clearly. The phrase "Vid avstängning av denna inställning" is incorrect since "avstängning" means "turning off" or "shutting down," which does not fit well with "reverting this setting." Also, the word order and phrasing could be more natural.

A better translation would be:
"Att återställa denna inställning kräver att hela blockkedjan laddas ner igen."
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>Privat läge aktiverad för fliken Översikt. För att visa data, bocka ur Inställningar &gt; Dölj data.</translation>
    
YES  
There is a spelling error in the translation: "Privat läge" should be "Integritetsläge" or "Integritetsläge aktiverat". "Privat läge" is not a correct Swedish phrase in this context. Also, "lägen" was written as "läge" but the correct phrasing is "Integritetsläge aktiverad" (Privacy mode activated). The rest is mostly correct, but the phrase "För att visa data" is acceptable but "För att avmaskera värden" (to unmask the values) would be more precise.

Correct translation:  
Integritetsläge aktiverat för fliken Översikt. För att avmaskera värden, bocka ur Inställningar &gt; Dölj värden.
```

```
        <source>Transaction has %1 unsigned inputs.</source>
        <translation>Transaktion %1 har osignerad indata.</translation>
    
YES  
The translation misplaces the format specifier and mistranslates "unsigned inputs." The English sentence means the transaction has a certain number (%1) of unsigned inputs (inputs not signed). The correct Swedish translation should keep %1 next to "osignerade indata" and properly pluralize "indata" (plural of input) to match the context.

Correct translation:  
Transaktionen har %1 osignerade indata.
```

```
        <source>(But no wallet is loaded.)</source>
        <translation>&lt;br&gt;(</translation>
    
YES  
The translation is incomplete and incorrect. The source text is "(But no wallet is loaded.)", but the translation only contains an HTML line break tag and an opening parenthesis, which do not convey the meaning.  

Correct translation:  
(But no wallet is loaded.)  
→  
(Men ingen plånbok är inläst.)
```

```
        <source>Ban for</source>
        <translation>Bannlys i</translation>
    
YES  
The Swedish translation "Bannlys i" is incorrect and appears to be Danish or Norwegian ("Bannlys" means "ban" in those languages, not Swedish). The correct Swedish translation for "Ban for" (likely meaning "Ban for [duration]" or "Ban for [reason]") should be:

"Blockera i" or "Avstängd i"  

Depending on context, the typical term for "ban" in Swedish Bitcoin or network contexts is "Blockera".

Correct translation:  
Blockera i
```

```
        <source>Payment information</source>
        <translation>Betalinformaton</translation>
    
YES  
There is a typo in the Swedish translation: "Betalinformaton" should be "Betalinformation".  

Correct translation:  
Betalinformation
```

```
        <source>%1 (%2 blocks)</source>
        <translation>%1 (%2 block)</translation>
    
YES  
The Swedish translation uses "block" as singular, but the source indicates plural ("%2 blocks"). In Swedish, the plural of "block" is also "block" (same form), so it should remain "block" in plural form without changing.

Correct translation:  
%1 (%2 block)
```

```
        <source>The amount to send in the selected unit</source>
        <translation>Beloppett att skicka i vald enhet</translation>
    
YES  
The Swedish translation contains a typo: "Beloppett" should be "Beloppet".  

Correct translation:  
Beloppet att skicka i vald enhet
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Detta är transaktionsavgiften som slängs borta om det är mindre än damm på denna nivå</translation>
    
YES  
The translation is somewhat inaccurate and awkward. The phrase "may discard" implies a possibility or option, which is not properly conveyed in Swedish by "slängs borta" (is thrown away) without indicating it is conditional or optional. Also, "dust" in the Bitcoin context is a technical term and should ideally be kept or explained rather than translated literally as "damm" (which means dust in the physical sense). A better translation would also clarify that the change amount is being referred to.

Correct translation:  
Detta är transaktionsavgiften som du kan bortse från om växeln är mindre än dust på denna nivå
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Varning: Privata nycklar upptäcktes i plånbok (%s) vilken har dessa inaktiverade</translation>
    
YES  
The translation is inaccurate and somewhat unclear. The source mentions "wallet {%s} with disabled private keys," meaning the wallet identified by the placeholder %s has private keys disabled, but private keys were detected anyway. The current translation uses parentheses instead of curly braces and the phrasing "vilken har dessa inaktiverade" ("which has these disabled") is vague and unnatural.

A better translation would maintain the placeholder curly braces and clearly state that the wallet {%s} has private keys disabled:

Correct translation:  
Varning: Privata nycklar upptäcktes i plånbok {%s} med inaktiverade privata nycklar
```

```
        <source>Maximum transaction weight is too low, can not accommodate change output</source>
        <translation>Maximal transaktionsvikt är för låg, kan inte tillgodose ändrad utdata</translation>
    
YES  
The translation contains inaccuracies related to terminology and phrasing:

1. "transaktionsvikt" is a literal and uncommon translation for "transaction weight" in this Bitcoin context; the more accepted term is "transaktionsvikt" or "transaktionsvikt" can be used, but it is better to keep consistent with Bitcoin terminology. "transaktionsvikt" is acceptable but the phrase could be improved.  
2. "ändrad utdata" incorrectly translates "change output." Here "change" means the 'change amount' returned to sender in a Bitcoin transaction. In Swedish Bitcoin terminology, "change output" is best translated as "växelutgång."  
3. Some of the syntax and wording is slightly awkward and could be clarified.

A better translation:  
"Maximal transaktionsvikt är för låg för att rymma växelutgången"

or, to keep the original flavor:  
"Maximal transaktionsvikt är för låg och kan inte rymma växelutgången"

Hence, corrected translation:  
<translation>Maximal transaktionsvikt är för låg och kan inte rymma växelutgången</translation>
```

```
        <source>Insufficient funds</source>
        <translation>Otillräckligt med bitcoins</translation>
    
YES  
The translation adds the word "bitcoins," which is not present in the original and might be misleading, as "Insufficient funds" generally refers to lack of any funds, not specifically bitcoins. A more accurate and faithful translation would be:  
Otillräckliga medel
```

```
        <source>Need to specify a port with -whitebind: '%s'</source>
        <translation>Port måste anges med -whitelist: '%s'</translation>
    
YES  
The source uses "-whitebind" but the translation incorrectly uses "-whitelist". The correct translation should keep the option name as "-whitebind".

Correct translation:  
Port måste anges med -whitebind: '%s'
```
</details>
