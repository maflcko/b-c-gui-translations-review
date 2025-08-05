# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>cs</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bcs%5D%20low%20quality)


```
        <source>Passphrase Dialog</source>
        <translation>Změna hesla</translation>
    
YES  
The English source "Passphrase Dialog" refers to a dialog window related to entering or managing a passphrase, not "Change password." The Czech translation "Změna hesla" means "Change password," which is inaccurate.

Correct translation:  
"Dialog pro zadání hesla" or "Dialog pro passphrase"
```

```
        <source>Repeat new passphrase</source>
        <translation>Totéž heslo ještě jednou</translation>
    
YES  
The translation "Totéž heslo ještě jednou" means "The same password once again," which is not an accurate or natural translation for "Repeat new passphrase." The source instructs the user to repeat the *new* passphrase (i.e., enter it again for confirmation), whereas the translation implies repeating the *same password*, which is less clear and less formal.

A more appropriate translation would be:  
"Zopakujte novou passphrasu"  
or  
"Zopakujte nové heslo"  

If "passphrase" should remain untranslated as a technical term, "passphrasu" is acceptable; otherwise "heslo" (password) can be used if appropriate. Given context, "Zopakujte novou passphrasu" is best.
```

```
        <source>Copy after fee</source>
        <translation>Kopíruj čistou částku</translation>
    
YES  
The translation "Kopíruj čistou částku" means "Copy the net amount," which is not an accurate or appropriate translation of "Copy after fee." The phrase "Copy after fee" typically refers to copying the amount or value after subtracting the transaction fee, not specifically the "net amount" as a phrase to be copied or an imperative "copy."

A more accurate translation, maintaining the imperative tone and context (likely a button or command), would be:

"Kopírovat částku po poplatku"  
or  
"Kopírovat po poplatku"  

depending on the exact UI context, but the first is more precise.

Correct translation:  
<Kopírovat částku po poplatku>
```

```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>Utrácení bitcoinů, které už utratily zatím nezobrazené transakce, nebude bitcoinovou sítí umožněno.</translation>
    
YES  
The translation is misleading and incorrect. It says "Spending bitcoins that have already been spent by not-yet-displayed transactions," which is incorrect and confusing. The original English means "Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network," i.e., the bitcoins are affected by transactions that have not yet been displayed (or processed/shown).

A better translation would be:  
"Pokus o utrácení bitcoinů, které jsou ovlivněny zatím nezobrazenými transakcemi, nebude sítí akceptován."
```

```
        <source>Font in the Overview tab: </source>
        <translation>Písmo s pevnou šířkou v panelu Přehled:</translation>
    
YES  
The English source "Font in the Overview tab: " simply refers to the font used in the Overview tab. The translation "Písmo s pevnou šířkou v panelu Přehled:" means "Monospaced font in the Overview panel:", which adds the meaning of "monospaced font" that is not present in the original. Additionally, "tab" is better translated as "záložka" (tab) rather than "panel," which usually means "panel" or "pane."  

Correct translation:  
Písmo v záložce Přehled:
```

```
        <source>Expert</source>
        <translation>Pokročilá nastavení</translation>
    
YES  
The source word "Expert" is a noun meaning an expert, typically masculine or neutral in Czech. The translation "Pokročilá nastavení" means "Advanced settings," which is a phrase and not an equivalent of "Expert." The translation is therefore inaccurate and misleading.  

Correct translation:  
Expert
```

```
        <source>Spendable:</source>
        <translation>Běžné:</translation>
    
YES  
The translation "Běžné:" means "Common:" or "Ordinary:", which is not an accurate translation of "Spendable:". In the Bitcoin context, "Spendable" refers to the amount of coins that are available to be spent. A better Czech translation would be:

"Utratitelné:"
```

```
        <source>Save Transaction Data</source>
        <translation>Zachovej procesní data</translation>
    
YES  
The Czech translation uses "procesní data," which is an uncommon and somewhat awkward expression in this context. A more natural and accurate translation for "Save Transaction Data" would be "Uložit data transakce" or "Uložit data transakce."  

Correct translation:  
Uložit data transakce
```

```
        <source>(But this wallet does not have the right keys.)</source>
        <translation>Ale tenhle vstup nemá správné klíče</translation>
    
YES  
The Czech translation uses "vstup" which means "input" rather than "wallet" ("peněženka"). The English source clearly refers to a wallet, so the correct translation should use "peněženka". Also, the source ends with a period inside the parentheses, which is missing in the translation.  

Correct translation:  
(Ale tahle peněženka nemá správné klíče.)
```

```
        <source>Inbound</source>
        <extracomment>An Inbound Connection from a Peer.</extracomment>
        <translation>Sem</translation>
    
YES  
The translation "Sem" is incorrect for the English term "Inbound" in the context of a network or peer connection. The correct Czech translation for "Inbound" (as in "incoming connection") is "Příchozí".

Correct translation:  
Příchozí
```

```
        <source>To specify a non-default location of the blocks directory use the '%1' option.</source>
        <translation>Pro specifikaci neklasické lokace pro data použij možnost '%1'</translation>
    
YES  
The translation has a slight issue with tone and phrasing for clarity and naturalness in Czech. The phrase "neklasické lokace pro data" is not the best choice here, and "použij" is informal and missing a period at the end. A better translation would explicitly mention "adresáře bloků" (blocks directory) as in the source text and use formal phrasing appropriate for documentation.

Correct translation:  
Pro určení nestandardního umístění adresáře bloků použijte možnost „%1“.
```

```
        <source>The mapped Autonomous System used for diversifying peer selection.</source>
        <translation>Mapovaný nezávislý - Autonomní Systém používaný pro rozšírení vzájemného výběru protějsků.</translation>
    
YES  
The translation is problematic due to incorrect capitalization, mistranslation of terms, and grammatical issues. "Autonomous System" should be "autonomní systém" (not capitalized as a proper noun here), "diversifying" is better translated as "diverzifikaci" or "rozmanitost," and "peer selection" should be "výběru protějšků" but without "vzájemného," which adds an unnecessary notion of mutuality. Also, the punctuation and spacing have an unnecessary space before the dash and inconsistent use of dashes.

Correct translation:  
Mapovaný autonomní systém používaný k diverzifikaci výběru protějšků.
```

```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>Adresy s omezením počtu přijatých adres</translation>
    
YES
The translation is inaccurate and redundant. The source text "Addresses Rate-Limited" refers to addresses that have been rate-limited (i.e., limited in processing due to rate limits). The provided translation "Adresy s omezením počtu přijatých adres" literally means "Addresses with a limitation on the number of received addresses," which is confusing and repeats "addresses" redundantly.

A better translation would be concise and clear, for example:
"Adresy omezené kvůli rychlostnímu limitu" 
or
"Adresy omezené rychlostí"

These capture the idea that the addresses are rate-limited (limited by rate).

Correct translation:
Adresy omezené rychlostí
```

```
        <source>Current block height</source>
        <translation>Velikost aktuálního bloku</translation>
    
YES  
The translation "Velikost aktuálního bloku" means "Size of the current block," which is inaccurate. The source "Current block height" refers to the block number or the height of the blockchain, not its size. A more accurate translation would be:  
"Výška aktuálního bloku"
```

```
        <source>Ban for</source>
        <translation>Uval klatbu na</translation>
    
YES  
The translation "Uval klatbu na" is incorrect and does not correspond to Czech. It appears to be gibberish or a mix of unrelated words. The correct Czech translation for "Ban for" (as in a ban for a specific reason) would be:  

"Zákaz na" or "Blokace na"  

So the corrected translation could be:  

<translation>Zákaz na</translation>
```

```
        <source>An optional label to associate with the new receiving address (used by you to identify an invoice).  It is also attached to the payment request.</source>
        <translation>Volitelný popis který sa přidá k téjo nové přijímací adrese (pro jednoduchší identifikaci). Tenhle popis bude také přidán do výzvy k platbě.</translation>
    
YES  
The translation contains errors and informal style that are not appropriate for this context:

1. "který sa přidá" – In Czech, the reflexive pronoun is "se," not "sa."  
2. "téjo" – should be "té" (correct demonstrative form).  
3. "Tenhle" – very informal; better to use "Tento" or rephrase to a more neutral style.  
4. The original mentions "label," literally "popisek" or "štítek," and "used by you to identify an invoice," which is not fully conveyed by "pro jednoduchší identifikaci."  
5. Slight punctuation fixes by adding commas for clarity.

Correct translation:  
Volitelný popis, který se přidá k nové přijímací adrese (používaný vámi k identifikaci faktury). Tento popis je také připojen k žádosti o platbu.
```

```
        <source>Remove the selected entries from the list</source>
        <translation>Smaž zvolené požadavky ze seznamu</translation>
    
YES  
The Czech word "Smaž" is correct for "Remove," but "požadavky" means "requests" rather than "entries." The correct term for "entries" is "záznamy" or "položky."  

Correct translation:  
Smaž zvolené položky ze seznamu
```

```
        <source>Hide transaction fee settings</source>
        <translation>Schovat nastavení poplatků transakce - transaction fee</translation>
    
YES  
The translation is partly in Czech ("Schovat nastavení poplatků transakce") but then unnecessarily repeats the English phrase " - transaction fee," which is redundant and breaks the normalization of the text. The phrase "Schovat" is a colloquial form; a more standard Czech verb would be "Skrýt."

Correct translation:  
Skrýt nastavení poplatků za transakci
```

```
        <source>When there is less transaction volume than space in the blocks, miners as well as relaying nodes may enforce a minimum fee. Paying only this minimum fee is just fine, but be aware that this can result in a never confirming transaction once there is more demand for bitcoin transactions than the network can process.</source>
        <translation>Když je zde měně transakcí než místa na bloky, mineři stejně tak relay-e mohou nasadit minimální poplatky. Zaplacením pouze minimálního poplatku je v pohodě, ale mějte na paměti že toto může mít za následek nikdy neověřenou transakci pokud zde bude více bitcoinových transakcí než může síť zvládnout.</translation>
    
YES
The translation contains several issues:
1. The word "měně" should be "méně" (correct spelling).
2. "relay-e" is an anglicism awkwardly adapted; the correct Czech term is "přeposílací uzly" or simply "uzly" or "relé uzly".
3. "poplatky" is plural ("fees"), but the source says "a minimum fee" (singular). It should be "minimální poplatek".
4. Minor punctuation is missing: a comma is needed before "že".
5. The phrase "nikdy neověřenou transakci" is understandable but "nikdy nepotvrzenou transakci" better fits Bitcoin context ("unconfirmed transaction").
6. The sentence can be made more fluent and natural in Czech.

Correct translation:
Když je v blocích méně transakcí než místa, mohou těžaři i přeposílací uzly vynucovat minimální poplatek. Zaplacení pouze tohoto minimálního poplatku je v pořádku, ale mějte na paměti, že to může vést k nikdy nepotvrzené transakci, pokud bude poptávka po bitcoinových transakcích větší, než síť dokáže zpracovat.
```

```
        <source>Copy after fee</source>
        <translation>Kopíruj čistou částku</translation>
    
YES  
The translation "Kopíruj čistou částku" means "Copy the net amount," which is not an accurate or appropriate translation of "Copy after fee." The phrase "Copy after fee" typically refers to copying the amount or value after subtracting the transaction fee, not specifically the "net amount" as a phrase to be copied or an imperative "copy."

A more accurate translation, maintaining the imperative tone and context (likely a button or command), would be:

"Kopírovat částku po poplatku"  
or  
"Kopírovat po poplatku"  

depending on the exact UI context, but the first is more precise.

Correct translation:  
<Kopírovat částku po poplatku>
```

```
        <source>Save Transaction Data</source>
        <translation>Zachovej procesní data</translation>
    
YES  
The Czech translation uses "procesní data," which is an uncommon and somewhat awkward expression in this context. A more natural and accurate translation for "Save Transaction Data" would be "Uložit data transakce" or "Uložit data transakce."  

Correct translation:  
Uložit data transakce
```

```
        <source>Enter a label for this address to add it to the list of used addresses</source>
        <translation>Zadej označení této adresy; obojí se ti pak uloží do adresáře</translation>
    
YES  
The translation introduces content not present in the source and changes the meaning. The source instructs to enter a label to add the address to the list of used addresses, whereas the translation says "Enter a label for this address; both will then be saved in the address book," which adds "both" and "address book," deviating from the original meaning. Also, the source does not mention "address book" but "list of used addresses."

Correct translation:  
Zadej označení této adresy, aby se přidala do seznamu použitých adres
```

```
        <source>Reset all sign message fields</source>
        <translation>Vymaž všechna pole formuláře pro podepsání zrávy</translation>
    
YES  
There is a typo in the translation: "zrávy" should be "zprávy". The corrected translation is:  
Vymaž všechna pole formuláře pro podepsání zprávy
```

```
        <source>Reset all verify message fields</source>
        <translation>Vymaž všechna pole formuláře pro ověření zrávy</translation>
    
YES  
The Czech word "zrávy" is a typo and should be "zprávy" (meaning "message").  

Correct translation:  
Vymaž všechna pole formuláře pro ověření zprávy
```

```
        <source>Please check the address and try again.</source>
        <translation>Zkontroluj ji prosím a zkus to pak znovu.</translation>
    
YES  
The translation "Zkontroluj ji prosím a zkus to pak znovu." is informal and uses "ji" (her/it) without explicitly stating what should be checked, which can be unclear in the context. The source specifically says "Please check the address and try again," so the word "address" should be explicitly mentioned for clarity and accuracy. A more appropriate translation would be:

"Zkontrolujte prosím adresu a zkuste to znovu."
```

```
        <source>Increasing transaction fee failed</source>
        <translation>Nepodařilo se navýšeit poplatek</translation>
    
YES  
The Czech translation contains a typo: "navýšeit" should be "navýšit". Also, the sentence is incomplete because it misses the object "transaction fee" ("poplatek za transakci"). A more accurate translation would be:  

Nepodařilo se navýšit poplatek za transakci
```

```
        <source>Could not commit transaction</source>
        <translation>Nemohl jsem uložit transakci do peněženky</translation>
    
YES  
The translation is inaccurate and introduces first-person ("Nemohl jsem" = "I could not"), which is not present in the source. The source is a general statement without specifying the subject. Also, "commit" in this context means to finalize or submit the transaction, not specifically "save to wallet."  

Correct translation:  
"Nebylo možné potvrdit transakci"  
(or)  
"Nepodařilo se potvrdit transakci"
```

```
        <source>%s request to listen on port %u. This port is considered "bad" and thus it is unlikely that any peer will connect to it. See doc/p2p-bad-ports.md for details and a full list.</source>
        <translation> %s Žádost o poslech na portu 2 %u . Tento port je považován za "špatný", a proto je nepravděpodobné, že by se k němu připojil nějaký peer. Viz doc/p2p-bad-ports.md pro podrobnosti a úplný seznam.</translation>
    
YES  
There are spacing errors and an erroneous character in the translation. Specifically:

- There is an extra space before `%s` at the start.
- The word "Žádost" is capitalized incorrectly mid-sentence.
- The number "2" before `%u` is incorrect and should be removed.
- There are spaces before `%u` and the period that shouldn't be there.

Correct translation:  
`%s žádost o poslech na portu %u. Tento port je považován za "špatný", a proto je nepravděpodobné, že by se k němu připojil nějaký peer. Viz doc/p2p-bad-ports.md pro podrobnosti a úplný seznam.`
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Jedná se o maximální poplatek, který zaplatíte (navíc k běžnému poplatku), aby se upřednostnila útrata z dosud nepoužitých adres oproti těm už jednou použitých.</translation>
    
YES  
The translation deviates from the original meaning. The source talks about a "maximum transaction fee" paid "to prioritize partial spend avoidance over regular coin selection." The original focuses on the fee for avoiding partial spends rather than selecting coins normally. The translation wrongly explains it as prioritizing spending from "unused addresses" versus "those already used," which is not equivalent and may mislead users.

Correct translation:  
Jedná se o maximální transakční poplatek, který zaplatíte (navíc k běžnému poplatku) za upřednostnění vyhnutí se částečné útratě před běžným výběrem mincí.
```

```
        <source>Outbound connections restricted to CJDNS (-onlynet=cjdns) but -cjdnsreachable is not provided</source>
        <translation>Odchozí připojení omezená na CJDNS (-onlynet=cjdns), ale -cjdnsreachable nejsou k dispozici</translation>
    
YES  
There is a grammatical and number agreement error in the Czech translation. The English source uses "is not provided" (singular), but the Czech translation says "jsou k dispozici" (are available, plural) which contradicts the negation. Also, "jsou k dispozici" means "are available," which doesn't align well with "is not provided." A better translation would use singular negation and a phrase closer to "není poskytnut" or "není k dispozici."

Correct translation:  
Odchozí připojení omezená na CJDNS (-onlynet=cjdns), ale -cjdnsreachable není poskytnut
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>Chyba: Nepodařilo se zapsat data peněženky %sna disk</translation>
    
YES  
The translation has spacing and word order issues. The phrase "%sna disk" should have a space ("%s na disk") and the phrase "data peněženky %s na disk" is somewhat ambiguous and unnatural in Czech. The English phrase means "data to disk for wallet %s," so the wallet identifier should be clearly associated with writing data to disk.

Correct translation:  
Chyba: Nepodařilo se zapsat data peněženky %s na disk
```

```
        <source>Invalid P2P permission: '%s'</source>
        <translation>Neplatné oprávnenie P2P: '%s'</translation>
    
YES  
The translation uses Slovak ("Neplatné oprávnenie P2P...") instead of Czech. In Czech, "Invalid P2P permission" should be translated as:  
"Neplatné P2P oprávnění: '%s'"
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>Neplatná částka %s=&lt;amount&gt;:'%s' (musí být alespoň%s)</translation>
    
YES  
There is a missing space between "alespoň" and "%s" in the translation. Also, it is better to add a space after the colon for readability.

Correct translation:  
Neplatná částka pro %s=&lt;amount&gt;: '%s' (musí být alespoň %s)
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Chyba: Nelze přidat pouze-sledovací tx %s do peněženky pro čtení</translation>
    
YES  
The term "pouze-sledovací" is an awkward literal translation for "watchonly" in this Bitcoin context. The correct technical term in Czech Bitcoin wallets is typically "pouze ke sledování" or "sledovací". Also, "peněženky pro čtení" is not a proper term for "watchonly wallet"; it literally means "wallet for reading". A better translation would be:  

Chyba: Nelze přidat watchonly tx %s do watchonly peněženky  

Alternatively, you can translate watchonly more fully:  

Chyba: Nelze přidat watchonly transakci %s do peněženky pouze ke sledování  

This preserves the technical meaning and is clearer to Czech Bitcoin users.
```

```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Nedostatek volných file deskriptorů. %dvolných, %dvyžadovaných</translation>
    
YES  
The translation has spacing issues around the format specifiers (%d) and mixes English and Czech terms ("file deskriptorů" should be "popisovačů souborů" or fully translated). Also, the formatting should match the source more closely for clarity.

Correct translation:  
"Nedostatek volných popisovačů souborů. %d dostupných, %d vyžadovaných."
```
</details>
