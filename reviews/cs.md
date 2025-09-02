# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>cs</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bcs%5D%20request)


<!-- cache_translation_check_cs_4cd0f4d5661cb58aaa388d1755639ab300f65c3b07bf87d786de36e8ddb736b6 -->
```
        <source>Passphrase Dialog</source>
        <translation>Změna hesla</translation>
    
ERR
The translation changes the meaning from "Passphrase Dialog" to "Change password".
Correct translation:
Dialog heslové fráze
```

<!-- cache_translation_check_cs_6575de34fb127eca9a13bb7a4cbee73a1ac6873cf238e4a438515550ff89858e -->
```
        <source>Repeat new passphrase</source>
        <translation>Totéž heslo ještě jednou</translation>
    
ERR
The translation omits "new" and uses "heslo" instead of the more accurate "přístupová fráze" for "passphrase."

Correct translation:
Zopakujte novou přístupovou frázi
```

<!-- cache_translation_check_cs_18a4553c0d0960d9cdad0cad918b88510e307306d09f6c5f78f5bdb7001e41e9 -->
```
        <source>&amp;Sending addresses</source>
        <translation>Odesílací adresy</translation>
    
ERR
The shortcut marker '&' is missing in the translation; it should appear exactly once.

Correct translation:
&Odesílací adresy
```

<!-- cache_translation_check_cs_f44ee0401769d5729f91b2c701a51ab129d5ffa6256c10e067dc78eecfff5c25 -->
```
        <source>&amp;Receiving addresses</source>
        <translation>Přijímací adresy</translation>
    
ERR
The accelerator ampersand is missing in the translation; it must appear exactly once.

Correct translation:
&Přijímací adresy
```

<!-- cache_translation_check_cs_62e79b2b259bb42d3dd25dd40b39894a5eae951b3860f139ccc7c8ad395f1b8c -->
```
        <source>&amp;Hide</source>
        <translation>Skryj</translation>
    
ERR
The mnemonic ampersand is missing and the verb form is nonstandard for a menu item. Use the infinitive form with a single ampersand.

Correct translation:
&Skrýt
```

<!-- cache_translation_check_cs_1faac1c3c63e3f6149842937eb924b4370a7918513965251ff2a911c69d9ab44 -->
```
        <source>S&amp;how</source>
        <translation>Zobraz</translation>
    
ERR
Missing accelerator marker '&' in the translation. It must appear exactly once.

Correct translation:
&Zobraz
```

<!-- cache_translation_check_cs_cba23791ab05ccae924343d36546a00776762e9f7aa319cc729303d15e7f5d6f -->
```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>Migrace peněženky povede k její přeměně na jednu nebo více deskriptorových peněženek. Bude třeba vytvořit novou zálohu peněženky.
Pokud peněženka obsahuje jakékoliv skripty, které lze pouze sledovat, bude vytvořena nová peněženka pouze pro tyto skripty.
Pokud tato peněženka obsahuje jakékoliv řešitelné skripty, které nejdou sledovat, bude vytvořena nová jiná peněženka, která bude obsahovat tyto skripty.

Proces migrace vytvoří zálohu peněženky přes samotnou migrací. Soubor se zálohou se bude nazývat &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak a bude umístěn v adresáři s touto peněženkou. V případě nepovedené migrace je možné provést obnovu prostřednitvím funkce "Obnovit peněženku".</translation>
    
ERR
- The phrase "nová peněženka pouze pro tyto skripty" implies exclusivity not present in the source; it should state the new wallet will contain those scripts.
- "které nejdou sledovat" means "cannot be watched," but the source says "not watched" (i.e., not being watched), not "impossible to watch."
- Typos: "přes samotnou migrací" should be "před samotnou migrací"; "prostřednitvím" should be "prostřednictvím."

Correct translation:
Migrace peněženky povede k její přeměně na jednu nebo více deskriptorových peněženek. Bude třeba vytvořit novou zálohu peněženky.
Pokud tato peněženka obsahuje jakékoli skripty typu watch-only, bude vytvořena nová peněženka, která bude tyto watch-only skripty obsahovat.
Pokud tato peněženka obsahuje jakékoli řešitelné skripty, které však nejsou sledované, bude vytvořena jiná nová peněženka, která bude tyto skripty obsahovat.

Proces migrace vytvoří zálohu peněženky před samotnou migrací. Tento záložní soubor ponese název &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak a bude umístěn v adresáři této peněženky. V případě nesprávně provedené migrace lze zálohu obnovit pomocí funkce "Obnovit peněženku".
```

<!-- cache_translation_check_cs_6aa4a5720f0176e17f52eab9e1f66e059dada8b326f00679a1a47cce4e310941 -->
```
        <source>Font in the Overview tab: </source>
        <translation>Písmo s pevnou šířkou v panelu Přehled:</translation>
    
ERR
The translation adds "s pevnou šířkou" (monospaced), which is not present in the source, and "tab" should be "kartě" or "záložce" rather than "panelu".

Correct translation:
Písmo na kartě Přehled:
```

<!-- cache_translation_check_cs_3d43f37d77c7a54ec32c819f60c30a5e85ea10bee7952a1c156e65d1afe804c4 -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>&amp;Minimalizovávat do ikony v panelu</translation>
    
ERR
The translation omits "instead of the taskbar" and uses an awkward form ("Minimalizovávat"). It should clearly mention the taskbar and use the standard term for system tray.

Correct translation:
&Minimalizovat do oznamovací oblasti místo na hlavní panel
```

<!-- cache_translation_check_cs_121dd3bcd2c1a87a8299233b8870a02b64de0c974b220768763369469c57fe74 -->
```
        <source>&amp;OK</source>
        <translation>&amp;Budiž</translation>
    
ERR
"Budiž" is archaic and not standard for UI buttons. The conventional Czech UI keeps "OK" as-is.

Correct translation:
&OK
```

<!-- cache_translation_check_cs_8e25fbfcfb8d6dc5c9a3af3102fe80e015193058de333f845f2a2224ac858f4b -->
```
        <source>Save Transaction Data</source>
        <translation>Zachovaj procesní data</translation>
    
ERR
"Zachovaj" is Slovak (Czech would be "Zachovej"/"Uložit") and "procesní data" misrenders "Transaction Data". 

Correct translation:
Uložit data transakce
```

<!-- cache_translation_check_cs_f544c7771e6a2b529a6b4919b0452634638c5fe03a321f8bf342e15091d2f4f7 -->
```
        <source>(But this wallet does not have the right keys.)</source>
        <translation>Ale tenhle vstup nemá správné klíče</translation>
    
ERR
The translation misinterprets "wallet" as "vstup" (input), uses colloquial phrasing, and omits the parentheses and final period present in the source.

Correct translation:
(Ale tato peněženka nemá správné klíče.)
```

<!-- cache_translation_check_cs_b3d38fa0548b71297a36d3ca90423dc7740c6a9dc8e2ebd9e1bdf10bde6e8140 -->
```
        <source>Inbound</source>
        <extracomment>An Inbound Connection from a Peer.</extracomment>
        <translation>Sem</translation>
    
ERR
"Sem" means "here" and is incorrect in this context. Use the standard networking term.
Correct translation:
Příchozí
```

<!-- cache_translation_check_cs_e68de09c9a141b73f289c5b643a1b29850c23cc540a695c8405c9efebbb25e1b -->
```
        <source>To specify a non-default location of the blocks directory use the '%1' option.</source>
        <translation>Pro specifikaci neklasické lokace pro data použij možnost '%1'</translation>
    
ERR
The Czech phrasing is awkward and inaccurate: "neklasické lokace pro data" is incorrect for "non-default location of the blocks directory", and "použij" is informal. Also missing the final period.

Correct translation:
Chcete-li zadat nevýchozí umístění adresáře bloků, použijte volbu '%1'.
```

<!-- cache_translation_check_cs_6546cee50c003944c22f807b84cba749e4a7c8020f440c25e83b3fe9e29f0d31 -->
```
        <source>The mapped Autonomous System used for diversifying peer selection.</source>
        <translation>Mapovaný nezávislý - Autonomní Systém používaný pro rozšírení vzájemného výběru protějsků.</translation>
    
ERR
The translation contains unnecessary words ("nezávislý"), incorrect capitalization, a spelling error ("rozšírení"), and an awkward phrasing of "peer selection." 

Correct translation:
Mapovaný autonomní systém používaný k diverzifikaci výběru protějšků.
```

<!-- cache_translation_check_cs_0419c0d4361a7b46aa3ed887bf32a7f2582e5d8d74684d240b951ed9501ea049 -->
```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>Adresy s omezením počtu přijatých adres</translation>
    
ERR
The Czech translation is awkward and redundant; it reads "Addresses with limitation of number of received addresses," which misrepresents "rate-limited." It should convey that addresses were limited by rate limiting.

Correct translation:
Adresy omezené rychlostí
```

<!-- cache_translation_check_cs_d1f05f8c744fe91baf902ededfd7414871c26cc5ecade836be3d6bba9d3e97b7 -->
```
        <source>Current block height</source>
        <translation>Velikost aktuálního bloku</translation>
    
ERR
"Velikost aktuálního bloku" means "size of the current block," not "block height." The correct term in Czech for "block height" is "výška bloku."

Correct translation:
Aktuální výška bloku
```

<!-- cache_translation_check_cs_9cb9ccc14c8af1662600802ed91723c25201eb2d1d121eadf16876cbd9d1c475 -->
```
        <source>Ban for</source>
        <translation>Uval klatbu na</translation>
    
ERR
The translation "Uval klatbu na" means "cast a curse on" and is incorrect in this context. It should refer to banning/blocking for a duration.

Correct translation:
Zablokovat na
```

<!-- cache_translation_check_cs_20fbaab2f44d517f3202034a9cd21e9d3b2fc9f47f26bfe2e75436a3389f98b7 -->
```
        <source>An optional label to associate with the new receiving address (used by you to identify an invoice).  It is also attached to the payment request.</source>
        <translation>Volitelný popis který sa přidá k téjo nové přijímací adrese (pro jednoduchší identifikaci). Tenhle popis bude také přidán do výzvy k platbě.</translation>
    
ERR
The Czech translation contains grammatical and stylistic issues (“sa”, “téjo”, colloquial “Tenhle”), mistranslates/omits “label” and “invoice”, and uses a less standard term for “payment request”.

Correct translation:
Volitelný štítek, který se přiřadí k nové adrese pro příjem (slouží vám k identifikaci faktury). Je také přiložen k žádosti o platbu.
```

<!-- cache_translation_check_cs_772af33f87523f54cba0e1aa4cf0cb02a101c8357b7fccacbd61469960cca4b1 -->
```
        <source>Remove the selected entries from the list</source>
        <translation>Smaž zvolené požadavky ze seznamu</translation>
    
ERR
"entries" was mistranslated as "požadavky" (requests), and the tone "Smaž" is an informal singular imperative. Standard UI wording uses "Odstranit/Smazat" and "položky".

Correct translation:
Odstranit vybrané položky ze seznamu
```

<!-- cache_translation_check_cs_576620dcbfacf296932119fb8f32bb5831bb93a433c947767f043f2de83d0543 -->
```
        <source>Hide transaction fee settings</source>
        <translation>Schovat nastavení poplatků transakce - transaction fee</translation>
    
ERR
The translation contains unnecessary English text ("- transaction fee") and uses an awkward phrasing. A clearer and standard UI phrasing in Czech is:

Correct translation:
Skrýt nastavení transakčního poplatku
```

<!-- cache_translation_check_cs_2c3e356353ddad5cb6d70e108348024b2d3dc5691a5502423f1eaf0d6764e947 -->
```
        <source>When there is less transaction volume than space in the blocks, miners as well as relaying nodes may enforce a minimum fee. Paying only this minimum fee is just fine, but be aware that this can result in a never confirming transaction once there is more demand for bitcoin transactions than the network can process.</source>
        <translation>Když je zde měně transakcí než místa na bloky, mineři stejně tak relay-e mohou nasadit minimální poplatky. Zaplacením pouze minimálního poplatku je v pohodě, ale mějte na paměti že toto může mít za následek nikdy neověřenou transakci pokud zde bude více bitcoinových transakcí než může síť zvládnout.</translation>
    
ERR
The Czech translation contains typos (“měně”), awkward/colloquial terms (“mineři”, “relay-e”), a plurality mismatch (“minimální poplatky” vs singular), and stylistic/punctuation issues. It also uses less accurate phrasing for blockchain terms.

Correct translation:
Když je objem transakcí menší než kapacita bloků, mohou těžaři i přeposílající uzly vyžadovat minimální poplatek. Zaplatit pouze tento minimální poplatek je v pořádku, ale mějte na paměti, že to může vést k tomu, že se transakce nikdy nepotvrdí, jakmile bude poptávka po bitcoinových transakcích vyšší, než kolik síť dokáže zpracovat.
```

<!-- cache_translation_check_cs_e506fab03f87f886d38316e6266f2caa7b289759c6d4e625ec7f50271c8c5229 -->
```
        <source>Clear &amp;All</source>
        <translation>Všechno &amp;smaž</translation>
    
ERR
The Czech phrasing "Všechno smaž" is colloquial and not a standard UI label. A more appropriate translation is "Smazat vše" (or "Vymazat vše"). Also, placing the accelerator on the first word is more typical.

Correct translation:
&Smazat vše
```

<!-- cache_translation_check_cs_66ecdcf785eac60fb29f467cbdf323253c93db8a0185d54af6e807d2a239c352 -->
```
        <source>Cr&amp;eate Unsigned</source>
        <translation>Vytvořit bez podpisu</translation>
    
ERR
The accelerator ampersand from the source is missing; there must be exactly one '&' in the translation.

Correct translation:
&Vytvořit bez podpisu
```

<!-- cache_translation_check_cs_f5a062154ebe68e07d6877864c43d824a27779809ec9426035ed6f5d756608ca -->
```
        <source>Save Transaction Data</source>
        <translation>Zachovej procesní data</translation>
    
ERR
"Zachovej procesní data" is inaccurate and stylistically inappropriate. "Zachovej" (preserve) is wrong for UI save action, and "procesní data" means process/procedural data, not transaction data.

Correct translation:
Uložit data transakce
```

<!-- cache_translation_check_cs_a014cc9be6200a8e8275ec6b5a64869d2f475638ea9beaeeb90414d7caf74579 -->
```
        <source>Enter a label for this address to add it to the list of used addresses</source>
        <translation>Zadej označení této adresy; obojí se ti pak uloží do adresáře</translation>
    
ERR
The translation is inaccurate and informal. It mentions saving both items to an address book ("adresář"), which is not in the source, and uses informal tone. The source means adding the address (with its label) to the list of used addresses.

Correct translation:
Zadejte štítek pro tuto adresu, aby byla přidána do seznamu použitých adres.
```

<!-- cache_translation_check_cs_02a28bd8f028e7427ba6d916c1c5cefaaf3e50830fee0e6eb60abe3ba5e52ef1 -->
```
        <source>Copy the current signature to the clipboard</source>
        <translation>Zkopírovat právě vybraný podpis do schránky</translation>
    
ERR
"právě vybraný" means "currently selected," which differs from "current." A closer translation is "aktuální podpis."

Correct translation:
Zkopírovat aktuální podpis do schránky
```

<!-- cache_translation_check_cs_b9c59a69a4566fe8087b9c6569d7639dfec5c4523360bc958f148353d6614f5d -->
```
        <source>Reset all sign message fields</source>
        <translation>Vymaž všechna pole formuláře pro podepsání zrávy</translation>
    
ERR
Contains a typo ("zrávy" → "zprávy") and adds "formuláře" unnecessarily.

Correct translation:
Resetovat všechna pole pro podepsání zprávy
```

<!-- cache_translation_check_cs_e506fab03f87f886d38316e6266f2caa7b289759c6d4e625ec7f50271c8c5229 -->
```
        <source>Clear &amp;All</source>
        <translation>Všechno &amp;smaž</translation>
    
ERR
The Czech phrasing "Všechno smaž" is colloquial and not a standard UI label. A more appropriate translation is "Smazat vše" (or "Vymazat vše"). Also, placing the accelerator on the first word is more typical.

Correct translation:
&Smazat vše
```

<!-- cache_translation_check_cs_708369179b35c435b16d7d61f08a9e6f7fe891ed7f9f33c24f73b56f28d79390 -->
```
        <source>Reset all verify message fields</source>
        <translation>Vymaž všechna pole formuláře pro ověření zrávy</translation>
    
ERR
Typo: "zrávy" should be "zprávy". Also "Reset" here is better rendered as clearing fields.
Correct translation:
Vymazat všechna pole pro ověření zprávy
```

<!-- cache_translation_check_cs_62d99320592ec813bced04974851598343791c94f5f6307dbf6f44250257a51d -->
```
        <source>Please check the address and try again.</source>
        <translation>Zkontroluj ji prosím a zkus to pak znovu.</translation>
    
ERR
The translation is too informal for UI text and omits “adresu,” relying on a pronoun. A clearer, formal translation is preferred.

Correct translation:
Zkontrolujte adresu a zkuste to znovu.
```

<!-- cache_translation_check_cs_5972f9af235394f8c8f213554dea0733f551037b958c6a9ec2568517d4f7d1c6 -->
```
        <source>Increasing transaction fee failed</source>
        <translation>Nepodařilo se navýšeit poplatek</translation>
    
ERR
The Czech word "navýšeit" is a typo; it should be "navýšit". It’s also clearer to specify "transakční poplatek".

Correct translation:
Nepodařilo se navýšit transakční poplatek
```

<!-- cache_translation_check_cs_001b7e363c98f66d33c0dd956aa5b9e4315796f44a48099976c9c410d6beddbc -->
```
        <source>Could not commit transaction</source>
        <translation>Nemohl jsem uložit transakci do peněženky</translation>
    
ERR
The translation adds content not in the source (“do peněženky”) and uses first person (“Nemohl jsem”), which is inappropriate for UI strings. It also misrenders “commit,” which is better as “zapsat” here.

Correct translation:
Nepodařilo se zapsat transakci
```

<!-- cache_translation_check_cs_990b34d53f2ae8233b59d9868a4f04efb9324dd3b69cf16a0cf62d0806398490 -->
```
        <source>%s request to listen on port %u. This port is considered "bad" and thus it is unlikely that any peer will connect to it. See doc/p2p-bad-ports.md for details and a full list.</source>
        <translation> %s Žádost o poslech na portu 2 %u . Tento port je považován za "špatný", a proto je nepravděpodobné, že by se k němu připojil nějaký peer. Viz doc/p2p-bad-ports.md pro podrobnosti a úplný seznam.</translation>
    
ERR
The translation contains errors: an extra "2" inserted before %u, leading/trailing stray spaces, an extra space before the period, and awkward phrasing. It also must preserve the %s and %u format specifiers exactly.

Correct translation:
%s požaduje naslouchání na portu %u. Tento port je považován za „špatný“, a proto je nepravděpodobné, že se k němu připojí nějaký peer. Viz doc/p2p-bad-ports.md pro podrobnosti a úplný seznam.
```

<!-- cache_translation_check_cs_e61df5912efea44304ab9a408c64128d9127ff6f426b178a693ea9c0713b6587 -->
```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Jedná se o maximální poplatek, který zaplatíte (navíc k běžnému poplatku), aby se upřednostnila útrata z dosud nepoužitých adres oproti těm už jednou použitých.</translation>
    
ERR
The translation changes the meaning: it talks about preferring spending from unused addresses, which is unrelated. It should refer to avoiding partial spends versus regular coin selection.

Correct translation:
Toto je maximální transakční poplatek, který zaplatíte (navíc k běžnému poplatku), abyste upřednostnili vyhýbání se částečným útratám před běžným výběrem mincí.
```

<!-- cache_translation_check_cs_f0bf813d6cc85974dd5ae101fa7c667c68911de86a1f9066911a854415669f6c -->
```
        <source>Options '-datacarrier' or '-datacarriersize' are set but are marked as deprecated. They will be removed in a future version.</source>
        <translation>Možnosti '-datacarrier' a '-datacarriersize' jsou nastaveny, ale jsou označené za zastaralé. V budoucí verzi budou odstraněny.</translation>
    
ERR
The translation changes "or" to "and", implying both options are set, which is inaccurate. Also, "označené za" is less idiomatic than "označena jako" here.

Correct translation:
Jedna z možností '-datacarrier' nebo '-datacarriersize' je nastavena, ale je označena jako zastaralá. V některé budoucí verzi budou odstraněny.
```

<!-- cache_translation_check_cs_69110ef6a3e1dbe3806c05475b5d246147219d484fd56091e8755fedacf6546e -->
```
        <source>Outbound connections restricted to CJDNS (-onlynet=cjdns) but -cjdnsreachable is not provided</source>
        <translation>Odchozí připojení omezená na CJDNS (-onlynet=cjdns), ale -cjdnsreachable nejsou k dispozici</translation>
    
ERR
The clause about -cjdnsreachable uses an incorrect plural and phrasing; it should be singular and indicate the option wasn't provided.

Correct translation:
Odchozí připojení jsou omezena na CJDNS (-onlynet=cjdns), ale -cjdnsreachable není zadán.
```

<!-- cache_translation_check_cs_c48b4230850b83d8bad33d61f189ed6a7f3ac23c932466284c2eddd4357d132a -->
```
        <source>-paytxfee is deprecated and will be fully removed in v31.0.</source>
        <translation>Možnost -paytxfee je zastaralá a bude v příští verzi v31.0 plně odstraněna</translation>
    
ERR
The translation adds "příští" (next), which changes the meaning, and it is missing the final period. Also, "ve verzi" is preferable before the version tag.

Correct translation:
Možnost -paytxfee je zastaralá a bude ve verzi v31.0 plně odstraněna.
```

<!-- cache_translation_check_cs_21a62c07301c626678a6cc7b7c2939794b3053480363c30207cf4758e1a042ef -->
```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>Chyba: Nepodařilo se zapsat data peněženky %sna disk</translation>
    
ERR
Chybí mezera mezi %s a „na“ a slovosled je neobratný.

Correct translation:
Chyba: Nepodařilo se zapsat data na disk pro peněženku %s
```

<!-- cache_translation_check_cs_b36a8df3b23f58746d5fee9e4d64164353bcb2e87fd410fc0a9ab77355e611aa -->
```
        <source>Invalid P2P permission: '%s'</source>
        <translation>Neplatné oprávnenie P2P: '%s'</translation>
    
ERR
The word "opr\u00e1vnenie" is Slovak; in Czech it should be "oprávnění". The format specifier and quotes are correct.

Correct translation:
Neplatné oprávnění P2P: '%s'
```

<!-- cache_translation_check_cs_5a00de39dbc4b6fecdf9cf98bda7e27b26c36ba48c91c402fa49a59fed992cf0 -->
```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>Neplatná částka %s=&lt;amount&gt;:'%s' (musí být alespoň%s)</translation>
    
ERR
Missing preposition "pro" for "for", missing spaces around colon and before the last %s.

Correct translation:
Neplatná částka pro %s=&lt;amount&gt;: '%s' (musí být alespoň %s)
```

<!-- cache_translation_check_cs_5e7ff3563bdf6c3889fec1c8aca0611fdc64755d7a2f1631e0b209fb51a52923 -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>Chyba při načítání %s: Zastaralý typ peněženky. Převeďte ji prosím na deskriptorovou pomocí převodného nástroje (migratewallet RPC)</translation>
    
ERR
The sentence is incomplete ("na deskriptorovou" lacks the noun), stylistically awkward ("převodného nástroje"), and missing the final period. Also better to make the second sentence a full clause.

Correct translation:
Chyba při načítání %s: Peněženka je zastaralého typu. Převeďte ji prosím na deskriptorovou peněženku pomocí migračního nástroje (migratewallet RPC).
```

<!-- cache_translation_check_cs_f38ba91afdc56338ce369458efb74cab5b082824796c660518805e8e55cb478f -->
```
        <source>Transaction requires one destination of non-zero value, a non-zero feerate, or a pre-selected input</source>
        <translation>Transakce vyžaduje jeden cíl nenulové hodnoty, nenulový poplatek nebo předvybraný vstup</translation>
    
ERR
"Feerate" was mistranslated as "poplatek" (fee) instead of "sazba poplatku" (fee rate). Also, "jeden cíl s nenulovou hodnotou" reads more naturally.

Correct translation:
Transakce vyžaduje jeden cíl s nenulovou hodnotou, nenulovou sazbu poplatku nebo předem vybraný vstup
```

<!-- cache_translation_check_cs_7dbe4d3bd8b3611230af4faaa6ce145b6c5a4c819c0e60df70d06beaa18b3371 -->
```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Chyba: Nelze přidat pouze-sledovací tx %s do peněženky pro čtení</translation>
    
ERR
The translation uses "peněženky pro čtení" (read-only) instead of the standard "jen ke sledování" (watch-only) and the phrase "pouze-sledovací tx" is unnatural. It should use "transakci" for "tx" and consistently render "watch-only" as "jen ke sledování".

Correct translation:
Chyba: Nelze přidat transakci %s jen ke sledování do peněženky jen ke sledování
```

<!-- cache_translation_check_cs_2a3b61b390d83a02f36b1ec46adfd835fa6d4b83d49e92c70f23b7ff71b0e760 -->
```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Nedostatek volných file deskriptorů. %dvolných, %dvyžadovaných</translation>
    
ERR
Missing spaces around format specifiers, missing comma and final period, and awkward mix of English/Czech terminology ("file deskriptorů"). Also "vyžadovaných" is inflected as an adjective without a noun.

Correct translation:
Nedostatek souborových deskriptorů. %d k dispozici, %d požadováno.
```

<!-- cache_translation_check_cs_3588514a0ca418b049d0a08b18f086d4cb13e33cf7cde3f3342f949e132f55bf -->
```
        <source>Unrecognized network in -proxy='%s': '%s'</source>
        <translation>Nerozeznaná síť v -proxy='%s': '%s'</translation>
    
ERR
The adjective choice is nonstandard; "Nerozpoznaná" is the correct and common form in Czech.

Correct translation:
Nerozpoznaná síť v -proxy='%s': '%s'
```
</details>

Number of issues: 46.
