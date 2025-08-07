# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>cs</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bcs%5D%20low%20quality)


```
        <source>Passphrase Dialog</source>
        <translation>Změna hesla</translation>
    
YES
The translation is inaccurate. "Passphrase Dialog" means the dialog window related to the passphrase, not necessarily "Change Password". The translation "Změna hesla" specifically means "Change Password".

Correct translation:
Dialog pro zadání hesla
```

```
        <source>Repeat new passphrase</source>
        <translation>Totéž heslo ještě jednou</translation>
    
YES
The translation is understandable but not entirely accurate or direct. "Totéž heslo ještě jednou" translates more like "The same password once again," which is less precise than the more standard "Zopakujte nové heslo" or "Opakujte nové heslo," meaning "Repeat new passphrase."

Correct translation:
Zopakujte nové heslo
```

```
        <source>Copy after fee</source>
        <translation>Kopíruj čistou částku</translation>
    
YES
The translation is not a literal or accurate rendering of the source. "Copy after fee" refers to copying the amount remaining after the fee is deducted, not just "Copy net amount" (which may be implied but not stated).

Correct translation:
Zkopírovat částku po odečtení poplatku
```

```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>Utrácení bitcoinů, které už utratily zatím nezobrazené transakce, nebude bitcoinovou sítí umožněno.</translation>
    
YES
The translation alters the meaning of the original sentence. The source states that bitcoins affected by not-yet-displayed transactions will not be accepted for spending. The Czech translation implies that bitcoins "which have already been spent by not-yet-displayed transactions" are being spent, which doesn't exactly match the original and may be confusing.

Correct translation:
Pokus o utracení bitcoinů, které jsou ovlivněny dosud nezobrazenými transakcemi, nebude sítí akceptován.
```

```
        <source>Font in the Overview tab: </source>
        <translation>Písmo s pevnou šířkou v panelu Přehled:</translation>
    
YES
The translation incorrectly adds "s pevnou šířkou" (monospace/fixed-width) which is not implied by the source. The source simply refers to a "font" in general, not specifically a fixed-width one.

Correct translation:
Písmo na kartě Přehled:
```

```
        <source>Expert</source>
        <translation>Pokročilá nastavení</translation>
    
YES
The translation "Pokročilá nastavení" means "Advanced settings," not "Expert." The translation is incorrect.

Correct translation:
Expert

Alternatively, you could use "Odborník" if you want to translate it as a noun, or leave it as "Expert" if it is intended as a label.
```

```
        <source>Spendable:</source>
        <translation>Běžné:</translation>
    
YES
The translation "Běžné:" means "Ordinary:" or "Regular:", which does not accurately reflect "Spendable" in the context of Bitcoin, where it usually refers to the balance that can be spent.

Correct translation:
K dispozici:
```

```
        <source>Save Transaction Data</source>
        <translation>Zachovej procesní data</translation>
    
YES
The Czech translation "Zachovej procesní data" is inaccurate. "Procesní data" does not mean "Transaction Data" (it could mislead as "process data"). The correct translation should be:

Uložit údaje o transakci

So, the correct translation is:  
Uložit údaje o transakci
```

```
        <source>(But this wallet does not have the right keys.)</source>
        <translation>Ale tenhle vstup nemá správné klíče</translation>
    
YES
The translation is inaccurate; it translates "this input" instead of "this wallet." Also, the parentheses are missing, and it lacks the period at the end.

Correct translation:
(Ale tato peněženka nemá správné klíče.)
```

```
        <source>Inbound</source>
        <extracomment>An Inbound Connection from a Peer.</extracomment>
        <translation>Sem</translation>
    
YES
The translation "Sem" is incorrect and unrelated to the meaning of "Inbound" as described ("An Inbound Connection from a Peer"). "Sem" means "here" in Czech, which does not fit the context.

Correct translation:
Příchozí
```

```
        <source>To specify a non-default location of the blocks directory use the '%1' option.</source>
        <translation>Pro specifikaci neklasické lokace pro data použij možnost '%1'</translation>
    
YES
The translation is inaccurate: "neklasické lokace pro data" does not convey "non-default location of the blocks directory" correctly. "neklasické" is not idiomatic, and "pro data" is too vague. Also, the sentence is missing the full stop at the end, differing from the source, and the formulation is not ideal in Czech.

Correct translation:
Pro zadání jiného umístění adresáře s bloky použijte volbu '%1'.
```

```
        <source>The mapped Autonomous System used for diversifying peer selection.</source>
        <translation>Mapovaný nezávislý - Autonomní Systém používaný pro rozšírení vzájemného výběru protějsků.</translation>
    
YES
There are inaccuracies and awkward phrasing in the Czech translation:

- "nezávislý" is not needed here, and the dash between "nezávislý - Autonomní Systém" is incorrect.
- "rozšírení vzájemného výběru protějsků" translates more as "expansion of mutual selection of counterparts" and does not accurately reflect "diversifying peer selection."
- "protějsků" is unusual; "uzlů" or "peerů" is more standard in technical/Bitcoin context.
- "Autonomní Systém" should not be capitalized except for the first word ("autonomní systém").

Correct translation:
Mapovaný autonomní systém používaný ke zpestření výběru peerů.
```

```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>Adresy s omezením počtu přijatých adres</translation>
    
YES
The translation is problematic because it changes the meaning of the original. "Addresses Rate-Limited" means that the addresses have been subject to rate limiting (their rate is limited), not that it is an "address with a limit on the number of received addresses". The current translation also introduces ambiguity and awkwardness.

Correct translation:
Adresy omezené rychlostí
or
Adresy omezené kvůli omezení rychlosti

A more context-accurate option:
Adresy omezené rate-limitem

Choose the most context-appropriate, with the first one generally preferred in technical UI:
Adresy omezené rychlostí
```

```
        <source>Current block height</source>
        <translation>Velikost aktuálního bloku</translation>
    
YES
The translation is inaccurate. "Current block height" should be translated as "Aktuální výška bloku" in Czech. The provided translation "Velikost aktuálního bloku" means "Current block size," which is incorrect.

Correct translation:
Aktuální výška bloku
```

```
        <source>Ban for</source>
        <translation>Uval klatbu na</translation>
    
YES
The translation "Uval klatbu na" is incorrect and unnatural in Czech. "Ban for" here refers to a period or duration (e.g., "Ban for 1 hour"), not an action. The correct translation for the duration context would be "Zákaz na" or "Ban na", for example, "Zákaz na 1 hodinu" ("Ban for 1 hour").

Correct translation:
Zákaz na
```

```
        <source>An optional label to associate with the new receiving address (used by you to identify an invoice).  It is also attached to the payment request.</source>
        <translation>Volitelný popis který sa přidá k téjo nové přijímací adrese (pro jednoduchší identifikaci). Tenhle popis bude také přidán do výzvy k platbě.</translation>
    
YES
There are several issues:
1. The word "sa" is incorrect in Czech; it should be "se".
2. "téjo" is a misspelling; the correct form is "této".
3. "jednoduchší" is not standard; "snadnější" or a more precise wording should be used.
4. "Tenhle" is informal and should be replaced with "Tento".
5. "popis" ("description/label") could be improved as "štítek" ("label") for accuracy.
6. The translation is less formal than the source and deviates in details.

Correct translation:
Volitelný štítek k přiřazení nové přijímací adrese (použijete jej k identifikaci faktury). Je také připojen k platební žádosti.
```

```
        <source>Remove the selected entries from the list</source>
        <translation>Smaž zvolené požadavky ze seznamu</translation>
    
YES
The translation uses "požadavky" (which means "requests") instead of a more neutral "položky" (which means "entries" or "items"). Also, "odstranit" is a better verb for "remove" in UI contexts than "smazat" (which is "delete"). "Zvolené" is acceptable for "selected", but "vybrané" is also commonly used.

Correct translation:
Odstraňte vybrané položky ze seznamu
```

```
        <source>Hide transaction fee settings</source>
        <translation>Schovat nastavení poplatků transakce - transaction fee</translation>
    
YES
The translation is problematic. It includes an unnecessary English phrase ("- transaction fee"), which is redundant since "poplatků transakce" already means "transaction fee". The correct translation is:

Schovat nastavení poplatků transakce

Alternatively, a more natural Czech phrasing would be:

Skrýt nastavení poplatků za transakci
```

```
        <source>When there is less transaction volume than space in the blocks, miners as well as relaying nodes may enforce a minimum fee. Paying only this minimum fee is just fine, but be aware that this can result in a never confirming transaction once there is more demand for bitcoin transactions than the network can process.</source>
        <translation>Když je zde měně transakcí než místa na bloky, mineři stejně tak relay-e mohou nasadit minimální poplatky. Zaplacením pouze minimálního poplatku je v pohodě, ale mějte na paměti že toto může mít za následek nikdy neověřenou transakci pokud zde bude více bitcoinových transakcí než může síť zvládnout.</translation>
    
YES
There are several linguistic issues in the Czech translation:
- "měně transakcí" should be "méně transakcí" (typo).
- "místa na bloky" is inaccurate; the correct phrase is "místa v blocích".
- "mineři stejně tak relay-e" is awkward and mixes English/Czech (should be "těžaři stejně jako uzly předávající transakce" or similar).
- "nasadit minimální poplatky" is not fully appropriate; better is "mohou vyžadovat minimální poplatek".
- "je v pohodě" is too colloquial; "je v pořádku" is better.
- Several awkward or ungrammatical phrases ("nikdy neověřenou transakci" vs "transakci, která nikdy nebude potvrzena").

Correct translation:
Když je menší objem transakcí než je místa v blocích, mohou těžaři i uzly, které transakce předávají, vyžadovat minimální poplatek. Zaplatit pouze tento minimální poplatek je v pořádku, ale mějte na paměti, že to může vést k tomu, že vaše transakce nikdy nebude potvrzena, pokud bude větší poptávka po bitcoinových transakcích, než kolik síť zvládne zpracovat.
```

```
        <source>Copy after fee</source>
        <translation>Kopíruj čistou částku</translation>
    
YES
The translation is not a literal or accurate rendering of the source. "Copy after fee" refers to copying the amount remaining after the fee is deducted, not just "Copy net amount" (which may be implied but not stated).

Correct translation:
Zkopírovat částku po odečtení poplatku
```

```
        <source>Save Transaction Data</source>
        <translation>Zachovej procesní data</translation>
    
YES
The Czech translation "Zachovej procesní data" is inaccurate. "Procesní data" does not mean "Transaction Data" (it could mislead as "process data"). The correct translation should be:

Uložit údaje o transakci

So, the correct translation is:  
Uložit údaje o transakci
```

```
        <source>Enter a label for this address to add it to the list of used addresses</source>
        <translation>Zadej označení této adresy; obojí se ti pak uloží do adresáře</translation>
    
YES
The translation does not accurately reflect the English source. The original says to "Enter a label for this address to add it to the list of used addresses"—it does not mention "oboji" ("both") nor does it mention an "adresář" ("directory"), which is misleading. The English intent is to assign a label to an address to be able to add it to the list of used addresses.

Correct translation:
Zadej popisek pro tuto adresu, aby byla přidána do seznamu použitých adres
```

```
        <source>Reset all sign message fields</source>
        <translation>Vymaž všechna pole formuláře pro podepsání zrávy</translation>
    
YES
There is a typographical error in the translation: "zrávy" should be "zprávy" ("message"). The rest of the translation is correct. Also, "Vymaž" (Erase) can be replaced with "Obnovit" (Reset) for accuracy, but "Vymaž" might still be acceptable depending on the UI context.

Correct translation:
Resetuj všechna pole formuláře pro podepsání zprávy
```

```
        <source>Reset all verify message fields</source>
        <translation>Vymaž všechna pole formuláře pro ověření zrávy</translation>
    
YES
There is a typographical error in the Czech word "zrávy"; it should be "zprávy" (message). Also, "vymaž" is more informal/direct, while "obnovit" or "resetovat" is closer to "reset". The rest of the translation is otherwise acceptable, but correcting the typo is essential.

Correct translation:
Resetovat všechna pole formuláře pro ověření zprávy
```

```
        <source>Please check the address and try again.</source>
        <translation>Zkontroluj ji prosím a zkus to pak znovu.</translation>
    
YES
The translation omits the direct translation of "address" ("adresa" in Czech), making the sentence less clear in context. The source says "Please check the address and try again," but the translation simply says "Check it please and try again," without specifying what to check.

Correct translation:
Zkontrolujte prosím adresu a zkuste to znovu.
```

```
        <source>Increasing transaction fee failed</source>
        <translation>Nepodařilo se navýšeit poplatek</translation>
    
YES
There is a typographical error in the Czech translation: "navýšeit" should be "navýšit".

Correct translation:
Nepodařilo se navýšit poplatek
```

```
        <source>Could not commit transaction</source>
        <translation>Nemohl jsem uložit transakci do peněženky</translation>
    
YES
The translation "Nemohl jsem uložit transakci do peněženky" literally means "I could not save the transaction into the wallet," which is more specific and differs from the source "Could not commit transaction". The translation also uses the first person "jsem", which is not used in typical UI/system messages (should be impersonal or passive).

Correct translation:
Nelze potvrdit transakci
```

```
        <source>%s request to listen on port %u. This port is considered "bad" and thus it is unlikely that any peer will connect to it. See doc/p2p-bad-ports.md for details and a full list.</source>
        <translation> %s Žádost o poslech na portu 2 %u . Tento port je považován za "špatný", a proto je nepravděpodobné, že by se k němu připojil nějaký peer. Viz doc/p2p-bad-ports.md pro podrobnosti a úplný seznam.</translation>
    
YES
There is an erroneous "2" inserted before "%u" in the translation ("na portu 2 %u"). Also, there are unnecessary spaces at the start of the translation and around the format specifiers. Otherwise, the translation is mostly accurate.

Correct translation:
%s žádost o poslech na portu %u. Tento port je považován za "špatný", a proto je nepravděpodobné, že by se k němu připojil nějaký peer. Viz doc/p2p-bad-ports.md pro podrobnosti a úplný seznam.
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Jedná se o maximální poplatek, který zaplatíte (navíc k běžnému poplatku), aby se upřednostnila útrata z dosud nepoužitých adres oproti těm už jednou použitých.</translation>
    
YES
The translation introduces an unintended meaning. The English source says "to prioritize partial spend avoidance over regular coin selection", which refers to techniques to avoid making partial spends (to avoid creating small leftover coins, UTXOs). The translation refers to "útrata z dosud nepoužitých adres oproti těm už jednou použitých" (spending from never-before-used addresses rather than those already used), which is inaccurate.

Correct translation:
Jedná se o maximální poplatek, který zaplatíte (navíc k běžnému poplatku), abyste upřednostnili vyhýbání se částečnému utrácení před běžným výběrem mincí.
```

```
        <source>Outbound connections restricted to CJDNS (-onlynet=cjdns) but -cjdnsreachable is not provided</source>
        <translation>Odchozí připojení omezená na CJDNS (-onlynet=cjdns), ale -cjdnsreachable nejsou k dispozici</translation>
    
YES
There is a grammatical error and slight inaccuracy in the translation. "-cjdnsreachable" is singular in the source, but in the translation it's treated as plural ("nejsou k dispozici"). Also, the phrase "nejsou k dispozici" translates as "are not available", which does not fully capture "is not provided".

Correct translation:
Odchozí připojení jsou omezena na CJDNS (-onlynet=cjdns), ale -cjdnsreachable není zadán
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>Chyba: Nepodařilo se zapsat data peněženky %sna disk</translation>
    
YES
There is a minor formatting error in the translation: there should be a space between '%s' and 'na disk'. Also, the word order more naturally reflects the original meaning if we keep "pro peněženku %s".

Correct translation:
Chyba: Nepodařilo se zapsat data na disk pro peněženku %s
```

```
        <source>Invalid P2P permission: '%s'</source>
        <translation>Neplatné oprávnenie P2P: '%s'</translation>
    
YES
The translation uses the Slovak word "oprávnenie" instead of the Czech equivalent "oprávnění". "oprávnenie" is not correct in Czech.

Correct translation:
Neplatné oprávnění P2P: '%s'
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>Neplatná částka %s=&lt;amount&gt;:'%s' (musí být alespoň%s)</translation>
    
YES
There is a missing space before the last %s in the translation ("alespoň%s" should be "alespoň %s").

Correct translation:
Neplatná částka pro %s=&lt;amount&gt;: '%s' (musí být alespoň %s)
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Chyba: Nelze přidat pouze-sledovací tx %s do peněženky pro čtení</translation>
    
YES
The translation "pouze-sledovací tx" is understandable, but "peněženka pro čtení" is incorrect. The term "watchonly wallet" should be translated as "peněženka pouze pro sledování" or "sledovací peněženka". Additionally, it is better to translate "watchonly tx" as "transakci pouze pro sledování".

Correct translation:
Chyba: Nelze přidat transakci pouze pro sledování %s do peněženky pouze pro sledování
```

```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Nedostatek volných file deskriptorů. %dvolných, %dvyžadovaných</translation>
    
YES
There are issues with missing spaces before "volných" and "vyžadovaných", and "file deskriptorů" should be localized as "souborových deskriptorů".

Correct translation:
Nedostatek volných souborových deskriptorů. %d volných, %d vyžadovaných.
```
</details>

Number of issues: 35.
