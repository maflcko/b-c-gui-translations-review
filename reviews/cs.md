# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>cs</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bcs%5D%20low%20quality)


```
        <source>Passphrase Dialog</source>
        <translation>Změna hesla</translation>
    
YES, the translation is incorrect. The source text "Passphrase Dialog" refers to a dialog box for entering a passphrase, likely for a wallet or encryption. The translation "Změna hesla" means "Password Change", which is a different function. A more accurate translation would be "Dialog pro heslo" or "Dialog pro frázi".

NO
```

```
        <source>Repeat new passphrase</source>
        <translation>Totéž heslo ještě jednou</translation>
    
YES, The translation is problematic because it does not accurately convey the meaning of "Repeat new passphrase". "Totéž heslo ještě jednou" translates to "The same password one more time," which is a correct translation of repeating a password, but it doesn't specifically mention that it's a *new* passphrase. A more accurate translation would be "Zopakujte nové heslo."
Zopakujte nové heslo
```

```
        <source>Sent transaction</source>
        <translation>Odeslané transakce</translation>
    
YES, The translation is inaccurate because it uses the plural form "transakce" (transactions) instead of the singular form "transakce" (transaction). The correct translation should be "Odeslaná transakce".
```

```
        <source>Copy after fee</source>
        <translation>Kopíruj čistou částku</translation>
    
YES, The translation is inaccurate. The phrase "Copy after fee" refers to copying the amount of Bitcoin remaining after deducting the transaction fee. The provided translation "Kopíruj čistou částku" means "Copy the net amount," which is close but not entirely precise. A better translation would be "Kopírovat částku po odečtení poplatku" or "Kopírovat částku bez poplatku".

NO
```

```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>Utrácení bitcoinů, které už utratily zatím nezobrazené transakce, nebude bitcoinovou sítí umožněno.</translation>
    
YES, the translation incorrectly states that the bitcoins have already been spent. The original text states that the transactions have not yet been displayed.
The correct translation should be: "Pokus o utracení bitcoinů ovlivněných zatím nezobrazenými transakcemi nebude bitcoinovou sítí akceptován."
```

```
        <source>Font in the Overview tab: </source>
        <translation>Písmo s pevnou šířkou v panelu Přehled:</translation>
    
YES, The translation is problematic because it includes the phrase "s pevnou šířkou" which translates to "fixed-width". The original English text "Font in the Overview tab:" does not specify that the font should be fixed-width. This is an unwarranted addition to the translation.

The correct translation should simply convey that it's about the font in the Overview tab.

Correct translation: Písmo v panelu Přehled:
```

```
        <source>Expert</source>
        <translation>Pokročilá nastavení</translation>
    
YES, The translation is inaccurate. "Expert" in the context of Bitcoin usually refers to a user with advanced knowledge or settings, not "Advanced settings" which is a more general term. The correct translation for "Expert" in this context would be "Expert".

NO
```

```
        <source>Spendable:</source>
        <translation>Běžné:</translation>
    
YES: The translation of "Spendable:" to "Běžné:" is incorrect in the context of Bitcoin. "Spendable" refers to funds that can be spent, while "Běžné" means "common" or "usual." A more accurate translation would be "Utraťitelné:" or "K dispozici k útratě:".
Běžné:
```

```
        <source>Signed %1 inputs, but more signatures are still required.</source>
        <translation>Podepsáno %1 výstupů, ale jsou ještě potřeba další podpisy.</translation>
    
YES: The word "inputs" was incorrectly translated as "výstupů" (outputs). The correct translation should be "vstupů".
Signed %1 vstupů, ale jsou ještě potřeba další podpisy.
```

```
        <source>Save Transaction Data</source>
        <translation>Zachovej procesní data</translation>
    
YES, The translation is problematic because "procesní" is not the correct translation for "Transaction". The correct translation for "Transaction" in this context is "transakční".

Zachovej transakční data
```

```
        <source>(But this wallet does not have the right keys.)</source>
        <translation>Ale tenhle vstup nemá správné klíče</translation>
    
YES, The translation is inaccurate and problematic because it translates "wallet" as "vstup" (input) which is not the correct meaning in the context of Bitcoin. The correct translation for "wallet" in this context is "peněženka".

NO
```

```
        <source>Inbound</source>
        <extracomment>An Inbound Connection from a Peer.</extracomment>
        <translation>Sem</translation>
    
YES - The translation is inaccurate. "Sem" means "here" in Czech, which is not the correct translation for "Inbound" in the context of a Bitcoin connection. The correct translation should reflect the direction of the connection.
NO
```

```
        <source>To specify a non-default location of the blocks directory use the '%1' option.</source>
        <translation>Pro specifikaci neklasické lokace pro data použij možnost '%1'</translation>
    
YES, The translation is inaccurate and uses incorrect terminology for the Bitcoin context. The word "nekalssické" means "unclassic" or "unconventional" which is not what the original English text intended. The original text is trying to say "non-default location". The word "data" is also too general.

Correct translation: Pro specifikaci výchozí lokace pro bloky použijte možnost '%1'.
```

```
        <source>The mapped Autonomous System used for diversifying peer selection.</source>
        <translation>Mapovaný nezávislý - Autonomní Systém používaný pro rozšírení vzájemného výběru protějsků.</translation>
    
YES, the translation contains erroneous content. The word "nezávislý" is not a correct translation of "Autonomous" in this context. It should refer to an "Autonomous System" as a defined entity in networking.

NO, the translation is unproblematic.
```

```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>Adresy s omezením počtu přijatých adres</translation>
    
YES: The translation is inaccurate and does not convey the meaning of the source text. The source text refers to addresses that have been rate-limited (meaning their processing was limited due to exceeding a certain rate), not addresses with a limit on the number of received addresses.

Correct translation: Adresy omezené rychlostí
```

```
        <source>Current block height</source>
        <translation>Velikost aktuálního bloku</translation>
    
YES, The translation is inaccurate and misleading. "Velikost aktuálního bloku" translates to "Current block size", not "Current block height".
Correct translation: "Aktuální výška bloku"
```

```
        <source>Ban for</source>
        <translation>Uval klatbu na</translation>
    
YES, The translation uses a word that is too strong and inappropriate for the context. "Uval klatbu na" translates to "curse" or "excommunicate", which is not fitting for a Bitcoin context. A more appropriate translation would be "Zákaz pro".
        <source>Ban for</source>
        <translation>Zákaz pro</translation>
```

```
        <source>An optional label to associate with the new receiving address (used by you to identify an invoice).  It is also attached to the payment request.</source>
        <translation>Volitelný popis který sa přidá k téjo nové přijímací adrese (pro jednoduchší identifikaci). Tenhle popis bude také přidán do výzvy k platbě.</translation>
    
YES, the translation has several grammatical errors and unnatural phrasing in Czech.

The main issues are:
1.  "Volitelný popis který sa přidá" - "který" should be "která" to agree with "popis" (masculine noun). "sa přidá" is colloquial/regional and should be "se přidá".
2.  "k téjo nové přijímací adrese" - "téjo" is incorrect. It should be "této" (dative case of "tato"). "přijímací adrese" is acceptable but "přijímací" might sound slightly technical; "přijaté" or "příchozí" could be alternatives depending on nuance.
3.  "(pro jednoduchší identifikaci)" - "jednoduchší" should be "jednodušší".
4.  "Tenhle popis bude také přidán do výzvy k platbě." - "Tenhle" is colloquial. "Tento" or "Tato poznámka/popis" would be more formal. "výzvy k platbě" is correct, but "žádosti o platbu" is more common for "payment request."

A more accurate and natural translation would be:

"Volitelný popis, který se přidá k této nové přijímací adrese (pro vaše snadnější rozlišení). Tento popis se také připojí k žádosti o platbu."
```

```
        <source>Remove the selected entries from the list</source>
        <translation>Smaž zvolené požadavky ze seznamu</translation>
    
YES, the translation is inaccurate. The source text "Remove the selected entries from the list" translates to "Smaž zvolené položky ze seznamu" in Czech, not "Smaž zvolené požadavky ze seznamu" which means "Delete the selected requests from the list".

NO
```

```
        <source>Hide transaction fee settings</source>
        <translation>Schovat nastavení poplatků transakce - transaction fee</translation>
    
YES, The translation contains an English phrase "transaction fee" at the end, which is redundant and not a natural part of the Czech sentence.
Schovat nastavení poplatků transakce
```

```
        <source>When there is less transaction volume than space in the blocks, miners as well as relaying nodes may enforce a minimum fee. Paying only this minimum fee is just fine, but be aware that this can result in a never confirming transaction once there is more demand for bitcoin transactions than the network can process.</source>
        <translation>Když je zde měně transakcí než místa na bloky, mineři stejně tak relay-e mohou nasadit minimální poplatky. Zaplacením pouze minimálního poplatku je v pohodě, ale mějte na paměti že toto může mít za následek nikdy neověřenou transakci pokud zde bude více bitcoinových transakcí než může síť zvládnout.</translation>
    
YES: The translation contains grammatical errors and awkward phrasing. The term "relay-e" is not a recognized word in Czech. The phrase "zaplacením pouze minimálního poplatku je v pohodě" is also unnatural.

Corrected translation: Když je transakčního objemu méně než místa v blocích, těžaři i uzly pro předávání mohou vynucovat minimální poplatek. Zaplacení pouze tohoto minimálního poplatku je v pořádku, ale mějte na paměti, že to může vést k transakci, která se nikdy nepotvrdí, jakmile bude poptávka po bitcoinových transakcích vyšší, než síť zvládne zpracovat.
```

```
        <source>Copy after fee</source>
        <translation>Kopíruj čistou částku</translation>
    
YES, The translation is inaccurate. The phrase "Copy after fee" refers to copying the amount of Bitcoin remaining after deducting the transaction fee. The provided translation "Kopíruj čistou částku" means "Copy the net amount," which is close but not entirely precise. A better translation would be "Kopírovat částku po odečtení poplatku" or "Kopírovat částku bez poplatku".

NO
```

```
        <source>Save Transaction Data</source>
        <translation>Zachovej procesní data</translation>
    
YES, The translation is problematic because "procesní" is not the correct translation for "Transaction". The correct translation for "Transaction" in this context is "transakční".

Zachovej transakční data
```

```
        <source>The address you selected for change is not part of this wallet. Any or all funds in your wallet may be sent to this address. Are you sure?</source>
        <translation>Adresa, kterou jsi zvolil pro drobné, není součástí této peněženky. Potenciálně všechny prostředky z tvé peněženky mohou být na tuto adresu odeslány. Souhlasíš, aby se tak stalo?</translation>
    
YES, the translation is problematic because it uses the informal second-person singular pronoun "jsi" and verb conjugations ("zvolil", "souhlasíš") which are inappropriate for a general user interface message. A more formal or neutral tone is expected. Additionally, the phrasing "Potenciálně všechny prostředky z tvé peněženky mohou být na tuto adresu odeslány" is a bit clunky.

NO, the translation is not problematic.
```

```
        <source>Enter a label for this address to add it to the list of used addresses</source>
        <translation>Zadej označení této adresy; obojí se ti pak uloží do adresáře</translation>
    
YES, The translation is not accurate and is problematic. The source text requests to add a label for an address to a list of used addresses. The translation, however, states that both the address and the label will be saved to an address book, which is a different functionality. It also uses informal language ("obojí se ti pak uloží") which might not be appropriate for a Bitcoin context.

The correct translation should be:
Zadejte popisek této adresy, aby se přidala do seznamu použitých adres
```

```
        <source>Reset all sign message fields</source>
        <translation>Vymaž všechna pole formuláře pro podepsání zrávy</translation>
    
YES, the translation is problematic. The word "zrávy" is a misspelling of "zprávy", which means "messages". The translation should be "Vymaž všechna pole formuláře pro podepsání zprávy".
```

```
        <source>Reset all verify message fields</source>
        <translation>Vymaž všechna pole formuláře pro ověření zrávy</translation>
    
YES: The Czech translation uses "zrávy" which is a misspelling of "zprávy" (messages).
Correct translation: Vymaž všechna pole formuláře pro ověření zprávy
```

```
        <source>Please check the address and try again.</source>
        <translation>Zkontroluj ji prosím a zkus to pak znovu.</translation>
    
YES, the translation is problematic because it is too informal and does not specify what "it" refers to. In the context of Bitcoin, the word "address" should be translated as "adresa".

The corrected translation is: Zkontrolujte prosím adresu a zkuste to znovu.
```

```
        <source>Increasing transaction fee failed</source>
        <translation>Nepodařilo se navýšeit poplatek</translation>
    
YES, The translation has a spelling error. The word "navýšeit" should be "navýšit".
Nepodařilo se navýšit poplatek
```

```
        <source>Could not commit transaction</source>
        <translation>Nemohl jsem uložit transakci do peněženky</translation>
    
YES, The Czech translation is not entirely accurate. The phrase "commit transaction" in the context of Bitcoin usually refers to broadcasting the transaction to the network for confirmation, not saving it to a wallet. A more accurate translation would be:

Nemohl jsem odeslat transakci.
```

```
        <source>%s request to listen on port %u. This port is considered "bad" and thus it is unlikely that any peer will connect to it. See doc/p2p-bad-ports.md for details and a full list.</source>
        <translation> %s Žádost o poslech na portu 2 %u . Tento port je považován za "špatný", a proto je nepravděpodobné, že by se k němu připojil nějaký peer. Viz doc/p2p-bad-ports.md pro podrobnosti a úplný seznam.</translation>
    
YES: There is an extra space before the percentage sign for the port number and a typo in the word "port".
%s Žádost o poslech na portu %u. Tento port je považován za "špatný", a proto je nepravděpodobné, že by se k němu připojil nějaký peer. Viz doc/p2p-bad-ports.md pro podrobnosti a úplný seznam.
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Jedná se o maximální poplatek, který zaplatíte (navíc k běžnému poplatku), aby se upřednostnila útrata z dosud nepoužitých adres oproti těm už jednou použitých.</translation>
    
YES, The translation introduces an inaccurate concept related to Bitcoin transactions. The original English text refers to "partial spend avoidance over regular coin selection," meaning prioritizing avoiding transactions that leave small amounts of Bitcoin behind (partial spends) over standard coin selection. The translation, however, implies prioritizing spending from unused addresses over already used ones, which is not the intended meaning.

The correct translation should focus on the avoidance of partial spends.

Correct translation: Jedná se o maximální poplatek, který zaplatíte (navíc k běžnému poplatku), aby se upřednostnilo vyhýbání se částečným útratám před běžným výběrem mincí.
```

```
        <source>Total length of network version string (%i) exceeds maximum length (%i). Reduce the number or size of uacomments.</source>
        <translation>Celková délka síťového identifikačního řetězce (%i) překročila svůj horní limit (%i). Omez počet nebo velikost voleb uacomment.</translation>
    
YES, The word "identifikačního" should be "verzního" to accurately translate "version".
Celková délka síťového verzního řetězce (%i) překročila svůj horní limit (%i). Omez počet nebo velikost voleb uacomment.
```

```
        <source>Unable to replay blocks. You will need to rebuild the database using -reindex-chainstate.</source>
        <translation>Nedaří se mi znovu aplikovat bloky. Budeš muset přestavět databázi použitím -reindex-chainstate.</translation>
    
YES, The translation uses informal language ("Budeš muset") when the source text is formal.

Correct translation: Nedaří se mi znovu aplikovat bloky. Bude nutné přestavět databázi pomocí -reindex-chainstate.
```

```
        <source>You need to rebuild the database using -reindex to go back to unpruned mode.  This will redownload the entire blockchain</source>
        <translation>K návratu k neprořezávacímu režimu je potřeba přestavět databázi použitím -reindex.  Také se znovu stáhne celý blockchain</translation>
    
YES, The translation is problematic because it uses "Také" which means "also" or "too", implying that the redownload of the blockchain is an additional action to rebuilding the database. The original sentence implies that rebuilding the database *will* redownload the blockchain.

The correct translation is:
K návratu k neprořezávacímu režimu je potřeba přestavět databázi použitím -reindex. To znovu stáhne celý blockchain.
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>Neplatná částka pro %s=&lt;amount&gt;: '%s' (musí být alespoň minrelay poplatek z %s, aby se zabránilo zaseknutí transakce)</translation>
    
YES, the translation is problematic. The second "%s" in the English source text refers to the minimum relay fee amount, which is missing in the Czech translation.

NO
```

```
        <source>Outbound connections restricted to CJDNS (-onlynet=cjdns) but -cjdnsreachable is not provided</source>
        <translation>Odchozí připojení omezená na CJDNS (-onlynet=cjdns), ale -cjdnsreachable nejsou k dispozici</translation>
    
YES, The translation is grammatically incorrect and sounds unnatural. The plural form of "nejsou k dispozici" is not appropriate when referring to a single option "-cjdnsreachable".

Here's the corrected translation:
Odchozí připojení jsou omezena na CJDNS (-onlynet=cjdns), ale -cjdnsreachable není poskytnuto.
```

```
        <source>UTXO snapshot failed to validate. Restart to resume normal initial block download, or try loading a different snapshot.</source>
        <translation>UTXO snímek se nepodařilo ověřit. K pokračování normálního iniciálního stáhnutí bloku restartujte, nebo zkuste nahrát jiný snímek.</translation>
    
YES. The Czech translation incorrectly uses the word "iniciálního" (initial) when it should use "inicializaci" (initialization) in the phrase "normálního iniciálního stáhnutí bloku". The correct translation for "initial block download" in this context is "stahování počátečního bloku" or "stahování inicializačního bloku".

NO.
UTXO snímek se nepodařilo ověřit. Restartujte, aby se obnovilo normální stahování počátečního bloku, nebo zkuste nahrát jiný snímek.
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>Chyba: Nepodařilo se zapsat data peněženky %sna disk</translation>
    
YES: The format specifier '%s' is incorrectly translated as '%sna'. The 'a' after '%s' should not be there.
Chyba: Nepodařilo se zapsat data peněženky %s na disk
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>Nemám žádný nebo jen špatný genesis blok. Není špatně nastavený datadir?</translation>
    
YES, The translation is problematic because it incorrectly translates "wrong datadir for network?". The literal translation "Není špatně nastavený datadir?" means "Is the datadir not set incorrectly?". The correct translation should convey that the datadir might be incorrectly set for the network.

NO
```

```
        <source>Invalid P2P permission: '%s'</source>
        <translation>Neplatné oprávnenie P2P: '%s'</translation>
    
YES: The translation uses Slovak (sk) instead of Czech (cs). The correct translation into Czech is "Neplatné oprávnění P2P: '%s'".
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>Neplatná částka %s=&lt;amount&gt;:'%s' (musí být alespoň%s)</translation>
    
YES, there is a missing space after the format specifier %s in the translation.
Neplatná částka %s=&lt;amount&gt;:'%s' (musí být alespoň %s)
```

```
        <source>Missing solving data for estimating transaction size</source>
        <translation>Chybí data pro vyřešení odhadnutí velikosti transakce</translation>
    
YES, the translation is inaccurate. The word "vyřešení" (solving) is out of place in this context. The correct translation should convey the idea of missing data for the estimation process itself.

NO
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Chyba: Nelze přidat pouze-sledovací tx %s do peněženky pro čtení</translation>
    
YES: The translation is grammatically incorrect and unnatural. The phrase "pouze-sledovací tx %s do peněženky pro čtení" is awkward. A more natural translation would be "watch-only tx %s do watch-only peněženky".

NO
```

```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Nedostatek volných file deskriptorů. %dvolných, %dvyžadovaných</translation>
    
YES, The translation is missing spaces around the format specifiers.
Nedostatek volných file deskriptorů. %d volných, %d vyžadovaných.
```
</details>
