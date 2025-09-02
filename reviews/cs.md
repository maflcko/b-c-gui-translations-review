# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>cs</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bcs%5D%20request)


<!-- cache_translation_check_cs_4cd0f4d5661cb58aaa388d1755639ab300f65c3b07bf87d786de36e8ddb736b6 -->
```
        <source>Passphrase Dialog</source>
        <translation>Změna hesla</translation>
    
ERR
The translation is inaccurate. "Passphrase Dialog" means the dialog window related to the passphrase, not necessarily "Change Password". The translation "Změna hesla" specifically means "Change Password".

Correct translation:
Dialog pro zadání hesla
```

<!-- cache_translation_check_cs_6575de34fb127eca9a13bb7a4cbee73a1ac6873cf238e4a438515550ff89858e -->
```
        <source>Repeat new passphrase</source>
        <translation>Totéž heslo ještě jednou</translation>
    
ERR
The translation is understandable but not entirely accurate or direct. "Totéž heslo ještě jednou" translates more like "The same password once again," which is less precise than the more standard "Zopakujte nové heslo" or "Opakujte nové heslo," meaning "Repeat new passphrase."

Correct translation:
Zopakujte nové heslo
```

<!-- cache_translation_check_cs_c9e4cddca5d3c7a6887785854785a2711fb6a8c3726dbb8298361a46feaaae83 -->
```
        <source>&amp;Help</source>
        <translation>Nápověd&amp;a</translation>
    
ERR
The shortcut key '&' has been incorrectly placed inside the word, resulting in "Nápověd&amp;a", which is not standard and does not properly assign a mnemonic in Czech. Additionally, the correct translation for "&Help" in Czech is "&Nápověda" (shortcut key typically at the beginning).

Correct translation:
&Nápověda
</reply>
```

<!-- cache_translation_check_cs_18a4553c0d0960d9cdad0cad918b88510e307306d09f6c5f78f5bdb7001e41e9 -->
```
        <source>&amp;Sending addresses</source>
        <translation>Odesílací adresy</translation>
    
ERR
The translation omits the '&' character, which is used in the source to indicate the shortcut key. It must appear exactly once in the translation.

Correct translation:
&Odesílací adresy
```

<!-- cache_translation_check_cs_f44ee0401769d5729f91b2c701a51ab129d5ffa6256c10e067dc78eecfff5c25 -->
```
        <source>&amp;Receiving addresses</source>
        <translation>Přijímací adresy</translation>
    
ERR
The translation misses the & character which indicates the shortcut key in the original. It must appear exactly once and can be placed anywhere in the translation.

Correct translation:
&Přijímací adresy
```

<!-- cache_translation_check_cs_62e79b2b259bb42d3dd25dd40b39894a5eae951b3860f139ccc7c8ad395f1b8c -->
```
        <source>&amp;Hide</source>
        <translation>Skryj</translation>
    
ERR
The ampersand (&) indicating the shortcut key is missing in the Czech translation. It must appear exactly once, as in the source.

Correct translation:
&Skryj
</reply>
```

<!-- cache_translation_check_cs_1faac1c3c63e3f6149842937eb924b4370a7918513965251ff2a911c69d9ab44 -->
```
        <source>S&amp;how</source>
        <translation>Zobraz</translation>
    
ERR
The translation is missing the ampersand (&), which is used to indicate the shortcut key. There should be exactly one '&' in the translation.

Correct translation:
&Zobraz
```

<!-- cache_translation_check_cs_a0cc8279c9aafbd920dc8b30d3178a232219e624e432da9211f1423a4a45b872 -->
```
        <source>Copy after fee</source>
        <translation>Kopíruj čistou částku</translation>
    
ERR
The translation is not a literal or accurate rendering of the source. "Copy after fee" refers to copying the amount remaining after the fee is deducted, not just "Copy net amount" (which may be implied but not stated).

Correct translation:
Zkopírovat částku po odečtení poplatku
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
Issues:
- Typo: "přes samotnou migrací" should be "před samotnou migrací" (before migrating).
- Typo: "prostřednitvím" should be "prostřednictvím".
- Awkward phrasing: "bude vytvořena nová jiná peněženka" should be "bude vytvořena další nová peněženka" or similar.
- Minor consistency: add "tato" in the second sentence for clarity.

Correct translation:
Migrace peněženky ji převede na jednu nebo více deskriptorových peněženek. Bude třeba vytvořit novou zálohu peněženky.
Pokud tato peněženka obsahuje jakékoli skripty určené pouze ke sledování, bude vytvořena nová peněženka, která bude tyto skripty obsahovat.
Pokud tato peněženka obsahuje jakékoli řešitelné, ale nesledované skripty, bude vytvořena další nová peněženka, která bude tyto skripty obsahovat.

Proces migrace vytvoří zálohu peněženky před samotnou migrací. Tento záložní soubor se bude jmenovat <wallet name>-<timestamp>.legacy.bak a bude umístěn v adresáři této peněženky. V případě chybné migrace lze zálohu obnovit pomocí funkce "Obnovit peněženku".
```

<!-- cache_translation_check_cs_4e0ad8bb7a809ecf41eeb5636919acf7ebbc5f56c32391c91afd322fad2877e5 -->
```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>Utrácení bitcoinů, které už utratily zatím nezobrazené transakce, nebude bitcoinovou sítí umožněno.</translation>
    
ERR
The translation alters the meaning of the original sentence. The source states that bitcoins affected by not-yet-displayed transactions will not be accepted for spending. The Czech translation implies that bitcoins "which have already been spent by not-yet-displayed transactions" are being spent, which doesn't exactly match the original and may be confusing.

Correct translation:
Pokus o utracení bitcoinů, které jsou ovlivněny dosud nezobrazenými transakcemi, nebude sítí akceptován.
```

<!-- cache_translation_check_cs_6aa4a5720f0176e17f52eab9e1f66e059dada8b326f00679a1a47cce4e310941 -->
```
        <source>Font in the Overview tab: </source>
        <translation>Písmo s pevnou šířkou v panelu Přehled:</translation>
    
ERR
The translation incorrectly adds "s pevnou šířkou" (monospace/fixed-width) which is not implied by the source. The source simply refers to a "font" in general, not specifically a fixed-width one.

Correct translation:
Písmo na kartě Přehled:
```

<!-- cache_translation_check_cs_3d43f37d77c7a54ec32c819f60c30a5e85ea10bee7952a1c156e65d1afe804c4 -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>&amp;Minimalizovávat do ikony v panelu</translation>
    
ERR
The translation is understandable but not fully accurate and omits details. "Minimalizovávat do ikony v panelu" does not specify "instead of the taskbar" and is not colloquial Czech. The accepted translation should explicitly mention minimizing to the system tray and the difference with the taskbar.

Correct translation:
&Minimalizovat do oznamovací oblasti místo na hlavní panel
```

<!-- cache_translation_check_cs_121dd3bcd2c1a87a8299233b8870a02b64de0c974b220768763369469c57fe74 -->
```
        <source>&amp;OK</source>
        <translation>&amp;Budiž</translation>
    
ERR
The translation "&amp;Budiž" is not appropriate for "&amp;OK." "Budiž" is a somewhat archaic or poetic word in Czech, meaning "so be it" or "let it be," and is not commonly used as a button label. The proper translation for the standard OK button is "&amp;OK", which is universally understood in Czech applications.

Correct translation:
&amp;OK
```

<!-- cache_translation_check_cs_8e25fbfcfb8d6dc5c9a3af3102fe80e015193058de333f845f2a2224ac858f4b -->
```
        <source>Save Transaction Data</source>
        <translation>Zachovaj procesní data</translation>
    
ERR
"Zachovaj" is Slovak (Czech would be "Zachovej") and "procesní data" means process/procedural data, not transaction data. In this Bitcoin context it should be "Uložit transakční data" or "Uložit data transakce".

Correct translation:
Uložit transakční data
```

<!-- cache_translation_check_cs_f544c7771e6a2b529a6b4919b0452634638c5fe03a321f8bf342e15091d2f4f7 -->
```
        <source>(But this wallet does not have the right keys.)</source>
        <translation>Ale tenhle vstup nemá správné klíče</translation>
    
ERR
The translation is inaccurate; it translates "this input" instead of "this wallet." Also, the parentheses are missing, and it lacks the period at the end.

Correct translation:
(Ale tato peněženka nemá správné klíče.)
```

<!-- cache_translation_check_cs_b3d38fa0548b71297a36d3ca90423dc7740c6a9dc8e2ebd9e1bdf10bde6e8140 -->
```
        <source>Inbound</source>
        <extracomment>An Inbound Connection from a Peer.</extracomment>
        <translation>Sem</translation>
    
ERR
The translation "Sem" is incorrect and unrelated to the meaning of "Inbound" as described ("An Inbound Connection from a Peer"). "Sem" means "here" in Czech, which does not fit the context.

Correct translation:
Příchozí
```

<!-- cache_translation_check_cs_e68de09c9a141b73f289c5b643a1b29850c23cc540a695c8405c9efebbb25e1b -->
```
        <source>To specify a non-default location of the blocks directory use the '%1' option.</source>
        <translation>Pro specifikaci neklasické lokace pro data použij možnost '%1'</translation>
    
ERR
The translation is inaccurate: "neklasické lokace pro data" does not convey "non-default location of the blocks directory" correctly. "neklasické" is not idiomatic, and "pro data" is too vague. Also, the sentence is missing the full stop at the end, differing from the source, and the formulation is not ideal in Czech.

Correct translation:
Pro zadání jiného umístění adresáře s bloky použijte volbu '%1'.
```

<!-- cache_translation_check_cs_6546cee50c003944c22f807b84cba749e4a7c8020f440c25e83b3fe9e29f0d31 -->
```
        <source>The mapped Autonomous System used for diversifying peer selection.</source>
        <translation>Mapovaný nezávislý - Autonomní Systém používaný pro rozšírení vzájemného výběru protějsků.</translation>
    
ERR
There are inaccuracies and awkward phrasing in the Czech translation:

- "nezávislý" is not needed here, and the dash between "nezávislý - Autonomní Systém" is incorrect.
- "rozšírení vzájemného výběru protějsků" translates more as "expansion of mutual selection of counterparts" and does not accurately reflect "diversifying peer selection."
- "protějsků" is unusual; "uzlů" or "peerů" is more standard in technical/Bitcoin context.
- "Autonomní Systém" should not be capitalized except for the first word ("autonomní systém").

Correct translation:
Mapovaný autonomní systém používaný ke zpestření výběru peerů.
```

<!-- cache_translation_check_cs_0419c0d4361a7b46aa3ed887bf32a7f2582e5d8d74684d240b951ed9501ea049 -->
```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>Adresy s omezením počtu přijatých adres</translation>
    
ERR
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

<!-- cache_translation_check_cs_d1f05f8c744fe91baf902ededfd7414871c26cc5ecade836be3d6bba9d3e97b7 -->
```
        <source>Current block height</source>
        <translation>Velikost aktuálního bloku</translation>
    
ERR
The translation is inaccurate. "Current block height" should be translated as "Aktuální výška bloku" in Czech. The provided translation "Velikost aktuálního bloku" means "Current block size," which is incorrect.

Correct translation:
Aktuální výška bloku
```

<!-- cache_translation_check_cs_9cb9ccc14c8af1662600802ed91723c25201eb2d1d121eadf16876cbd9d1c475 -->
```
        <source>Ban for</source>
        <translation>Uval klatbu na</translation>
    
ERR
The translation "Uval klatbu na" is incorrect and unnatural in Czech. "Ban for" here refers to a period or duration (e.g., "Ban for 1 hour"), not an action. The correct translation for the duration context would be "Zákaz na" or "Ban na", for example, "Zákaz na 1 hodinu" ("Ban for 1 hour").

Correct translation:
Zákaz na
```

<!-- cache_translation_check_cs_20fbaab2f44d517f3202034a9cd21e9d3b2fc9f47f26bfe2e75436a3389f98b7 -->
```
        <source>An optional label to associate with the new receiving address (used by you to identify an invoice).  It is also attached to the payment request.</source>
        <translation>Volitelný popis který sa přidá k téjo nové přijímací adrese (pro jednoduchší identifikaci). Tenhle popis bude také přidán do výzvy k platbě.</translation>
    
ERR
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

<!-- cache_translation_check_cs_772af33f87523f54cba0e1aa4cf0cb02a101c8357b7fccacbd61469960cca4b1 -->
```
        <source>Remove the selected entries from the list</source>
        <translation>Smaž zvolené požadavky ze seznamu</translation>
    
ERR
The translation uses "požadavky" (which means "requests") instead of a more neutral "položky" (which means "entries" or "items"). Also, "odstranit" is a better verb for "remove" in UI contexts than "smazat" (which is "delete"). "Zvolené" is acceptable for "selected", but "vybrané" is also commonly used.

Correct translation:
Odstraňte vybrané položky ze seznamu
```

<!-- cache_translation_check_cs_576620dcbfacf296932119fb8f32bb5831bb93a433c947767f043f2de83d0543 -->
```
        <source>Hide transaction fee settings</source>
        <translation>Schovat nastavení poplatků transakce - transaction fee</translation>
    
ERR
The translation is problematic. It includes an unnecessary English phrase ("- transaction fee"), which is redundant since "poplatků transakce" already means "transaction fee". The correct translation is:

Schovat nastavení poplatků transakce

Alternatively, a more natural Czech phrasing would be:

Skrýt nastavení poplatků za transakci
```

<!-- cache_translation_check_cs_2c3e356353ddad5cb6d70e108348024b2d3dc5691a5502423f1eaf0d6764e947 -->
```
        <source>When there is less transaction volume than space in the blocks, miners as well as relaying nodes may enforce a minimum fee. Paying only this minimum fee is just fine, but be aware that this can result in a never confirming transaction once there is more demand for bitcoin transactions than the network can process.</source>
        <translation>Když je zde měně transakcí než místa na bloky, mineři stejně tak relay-e mohou nasadit minimální poplatky. Zaplacením pouze minimálního poplatku je v pohodě, ale mějte na paměti že toto může mít za následek nikdy neověřenou transakci pokud zde bude více bitcoinových transakcí než může síť zvládnout.</translation>
    
ERR
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

<!-- cache_translation_check_cs_e506fab03f87f886d38316e6266f2caa7b289759c6d4e625ec7f50271c8c5229 -->
```
        <source>Clear &amp;All</source>
        <translation>Všechno &amp;smaž</translation>
    
ERR
The translation switches the order of words compared to the English and uses "Všechno smaž", which is awkward; also, the placement of "&amp;" is incorrect. In Czech UI, it is standard to use "Smazat &amp;vše" or "&amp;Smazat vše" for clarity and menu consistency.

Correct translation:
Smazat &amp;vše
or
&amp;Smazat vše
```

<!-- cache_translation_check_cs_a0cc8279c9aafbd920dc8b30d3178a232219e624e432da9211f1423a4a45b872 -->
```
        <source>Copy after fee</source>
        <translation>Kopíruj čistou částku</translation>
    
ERR
The translation is not a literal or accurate rendering of the source. "Copy after fee" refers to copying the amount remaining after the fee is deducted, not just "Copy net amount" (which may be implied but not stated).

Correct translation:
Zkopírovat částku po odečtení poplatku
```

<!-- cache_translation_check_cs_66ecdcf785eac60fb29f467cbdf323253c93db8a0185d54af6e807d2a239c352 -->
```
        <source>Cr&amp;eate Unsigned</source>
        <translation>Vytvořit bez podpisu</translation>
    
ERR
The shortcut key indicator (&amp;) is missing in the Czech translation, which could lead to the loss of keyboard shortcut functionality. The translation should include exactly one '&' character as in the source.

Correct translation:
Vytvořit &bez podpisu
```

<!-- cache_translation_check_cs_f5a062154ebe68e07d6877864c43d824a27779809ec9426035ed6f5d756608ca -->
```
        <source>Save Transaction Data</source>
        <translation>Zachovej procesní data</translation>
    
ERR
The Czech translation "Zachovej procesní data" is inaccurate. "Procesní data" does not mean "Transaction Data" (it could mislead as "process data"). The correct translation should be:

Uložit údaje o transakci

So, the correct translation is:  
Uložit údaje o transakci
```

<!-- cache_translation_check_cs_a014cc9be6200a8e8275ec6b5a64869d2f475638ea9beaeeb90414d7caf74579 -->
```
        <source>Enter a label for this address to add it to the list of used addresses</source>
        <translation>Zadej označení této adresy; obojí se ti pak uloží do adresáře</translation>
    
ERR
The translation does not accurately reflect the English source. The original says to "Enter a label for this address to add it to the list of used addresses"—it does not mention "oboji" ("both") nor does it mention an "adresář" ("directory"), which is misleading. The English intent is to assign a label to an address to be able to add it to the list of used addresses.

Correct translation:
Zadej popisek pro tuto adresu, aby byla přidána do seznamu použitých adres
```

<!-- cache_translation_check_cs_02a28bd8f028e7427ba6d916c1c5cefaaf3e50830fee0e6eb60abe3ba5e52ef1 -->
```
        <source>Copy the current signature to the clipboard</source>
        <translation>Zkopírovat právě vybraný podpis do schránky</translation>
    
ERR
"Current" was mistranslated as "právě vybraný" ("selected"). It should be "aktuální".

Correct translation:
Zkopírovat aktuální podpis do schránky
```

<!-- cache_translation_check_cs_b9c59a69a4566fe8087b9c6569d7639dfec5c4523360bc958f148353d6614f5d -->
```
        <source>Reset all sign message fields</source>
        <translation>Vymaž všechna pole formuláře pro podepsání zrávy</translation>
    
ERR
There is a typographical error in the translation: "zrávy" should be "zprávy" ("message"). The rest of the translation is correct. Also, "Vymaž" (Erase) can be replaced with "Obnovit" (Reset) for accuracy, but "Vymaž" might still be acceptable depending on the UI context.

Correct translation:
Resetuj všechna pole formuláře pro podepsání zprávy
```

<!-- cache_translation_check_cs_e506fab03f87f886d38316e6266f2caa7b289759c6d4e625ec7f50271c8c5229 -->
```
        <source>Clear &amp;All</source>
        <translation>Všechno &amp;smaž</translation>
    
ERR
The translation switches the order of words compared to the English and uses "Všechno smaž", which is awkward; also, the placement of "&amp;" is incorrect. In Czech UI, it is standard to use "Smazat &amp;vše" or "&amp;Smazat vše" for clarity and menu consistency.

Correct translation:
Smazat &amp;vše
or
&amp;Smazat vše
```

<!-- cache_translation_check_cs_708369179b35c435b16d7d61f08a9e6f7fe891ed7f9f33c24f73b56f28d79390 -->
```
        <source>Reset all verify message fields</source>
        <translation>Vymaž všechna pole formuláře pro ověření zrávy</translation>
    
ERR
There is a typographical error in the Czech word "zrávy"; it should be "zprávy" (message). Also, "vymaž" is more informal/direct, while "obnovit" or "resetovat" is closer to "reset". The rest of the translation is otherwise acceptable, but correcting the typo is essential.

Correct translation:
Resetovat všechna pole formuláře pro ověření zprávy
```

<!-- cache_translation_check_cs_62d99320592ec813bced04974851598343791c94f5f6307dbf6f44250257a51d -->
```
        <source>Please check the address and try again.</source>
        <translation>Zkontroluj ji prosím a zkus to pak znovu.</translation>
    
ERR
The translation omits the direct translation of "address" ("adresa" in Czech), making the sentence less clear in context. The source says "Please check the address and try again," but the translation simply says "Check it please and try again," without specifying what to check.

Correct translation:
Zkontrolujte prosím adresu a zkuste to znovu.
```

<!-- cache_translation_check_cs_5972f9af235394f8c8f213554dea0733f551037b958c6a9ec2568517d4f7d1c6 -->
```
        <source>Increasing transaction fee failed</source>
        <translation>Nepodařilo se navýšeit poplatek</translation>
    
ERR
There is a typographical error in the Czech translation: "navýšeit" should be "navýšit".

Correct translation:
Nepodařilo se navýšit poplatek
```

<!-- cache_translation_check_cs_001b7e363c98f66d33c0dd956aa5b9e4315796f44a48099976c9c410d6beddbc -->
```
        <source>Could not commit transaction</source>
        <translation>Nemohl jsem uložit transakci do peněženky</translation>
    
ERR
The translation "Nemohl jsem uložit transakci do peněženky" literally means "I could not save the transaction into the wallet," which is more specific and differs from the source "Could not commit transaction". The translation also uses the first person "jsem", which is not used in typical UI/system messages (should be impersonal or passive).

Correct translation:
Nelze potvrdit transakci
```

<!-- cache_translation_check_cs_990b34d53f2ae8233b59d9868a4f04efb9324dd3b69cf16a0cf62d0806398490 -->
```
        <source>%s request to listen on port %u. This port is considered "bad" and thus it is unlikely that any peer will connect to it. See doc/p2p-bad-ports.md for details and a full list.</source>
        <translation> %s Žádost o poslech na portu 2 %u . Tento port je považován za "špatný", a proto je nepravděpodobné, že by se k němu připojil nějaký peer. Viz doc/p2p-bad-ports.md pro podrobnosti a úplný seznam.</translation>
    
ERR
There is an erroneous "2" inserted before "%u" in the translation ("na portu 2 %u"). Also, there are unnecessary spaces at the start of the translation and around the format specifiers. Otherwise, the translation is mostly accurate.

Correct translation:
%s žádost o poslech na portu %u. Tento port je považován za "špatný", a proto je nepravděpodobné, že by se k němu připojil nějaký peer. Viz doc/p2p-bad-ports.md pro podrobnosti a úplný seznam.
```

<!-- cache_translation_check_cs_e61df5912efea44304ab9a408c64128d9127ff6f426b178a693ea9c0713b6587 -->
```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Jedná se o maximální poplatek, který zaplatíte (navíc k běžnému poplatku), aby se upřednostnila útrata z dosud nepoužitých adres oproti těm už jednou použitých.</translation>
    
ERR
The translation introduces an unintended meaning. The English source says "to prioritize partial spend avoidance over regular coin selection", which refers to techniques to avoid making partial spends (to avoid creating small leftover coins, UTXOs). The translation refers to "útrata z dosud nepoužitých adres oproti těm už jednou použitých" (spending from never-before-used addresses rather than those already used), which is inaccurate.

Correct translation:
Jedná se o maximální poplatek, který zaplatíte (navíc k běžnému poplatku), abyste upřednostnili vyhýbání se částečnému utrácení před běžným výběrem mincí.
```

<!-- cache_translation_check_cs_f0bf813d6cc85974dd5ae101fa7c667c68911de86a1f9066911a854415669f6c -->
```
        <source>Options '-datacarrier' or '-datacarriersize' are set but are marked as deprecated. They will be removed in a future version.</source>
        <translation>Možnosti '-datacarrier' a '-datacarriersize' jsou nastaveny, ale jsou označené za zastaralé. V budoucí verzi budou odstraněny.</translation>
    
ERR
The conjunction "a" (and) implies both options are set, whereas the source says "or". Also, "označené za zastaralé" is less idiomatic than "označené/označeny jako zastaralé."

Correct translation:
Možnosti '-datacarrier' nebo '-datacarriersize' jsou nastaveny, ale jsou označeny jako zastaralé. V některé z budoucích verzí budou odstraněny.
```

<!-- cache_translation_check_cs_69110ef6a3e1dbe3806c05475b5d246147219d484fd56091e8755fedacf6546e -->
```
        <source>Outbound connections restricted to CJDNS (-onlynet=cjdns) but -cjdnsreachable is not provided</source>
        <translation>Odchozí připojení omezená na CJDNS (-onlynet=cjdns), ale -cjdnsreachable nejsou k dispozici</translation>
    
ERR
There is a grammatical error and slight inaccuracy in the translation. "-cjdnsreachable" is singular in the source, but in the translation it's treated as plural ("nejsou k dispozici"). Also, the phrase "nejsou k dispozici" translates as "are not available", which does not fully capture "is not provided".

Correct translation:
Odchozí připojení jsou omezena na CJDNS (-onlynet=cjdns), ale -cjdnsreachable není zadán
```

<!-- cache_translation_check_cs_c661067b5c3ebddc81555d4cd87924396a7cf41894ceaf50b90e28d49f130deb -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>Prořezávání: poslední synchronizace peněženky proběhla před už prořezanými daty. Je třeba provést -reindex (tedy v případě režimu prořezávání stáhnout celý blockchain znovu)</translation>
    
ERR
The phrase "proběhla před už prořezanými daty" is misleading; it suggests the sync happened before the pruned data, rather than requiring data that have already been pruned. It should indicate that the last sync falls into/extends into already pruned data.

Correct translation:
Prořezávání: poslední synchronizace peněženky spadá do již prořezaných dat. Je třeba provést -reindex (v případě prořezávaného uzlu se znovu stáhne celý blockchain).
```

<!-- cache_translation_check_cs_c48b4230850b83d8bad33d61f189ed6a7f3ac23c932466284c2eddd4357d132a -->
```
        <source>-paytxfee is deprecated and will be fully removed in v31.0.</source>
        <translation>Možnost -paytxfee je zastaralá a bude v příští verzi v31.0 plně odstraněna</translation>
    
ERR
The translation adds "příští" (next), which is not in the source, and "v příští verzi v31.0" is awkward with a double 'v'. It also misses the final period.

Correct translation:
Volba -paytxfee je zastaralá a bude ve verzi v31.0 plně odstraněna.
```

<!-- cache_translation_check_cs_21a62c07301c626678a6cc7b7c2939794b3053480363c30207cf4758e1a042ef -->
```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>Chyba: Nepodařilo se zapsat data peněženky %sna disk</translation>
    
ERR
There is a minor formatting error in the translation: there should be a space between '%s' and 'na disk'. Also, the word order more naturally reflects the original meaning if we keep "pro peněženku %s".

Correct translation:
Chyba: Nepodařilo se zapsat data na disk pro peněženku %s
```

<!-- cache_translation_check_cs_b36a8df3b23f58746d5fee9e4d64164353bcb2e87fd410fc0a9ab77355e611aa -->
```
        <source>Invalid P2P permission: '%s'</source>
        <translation>Neplatné oprávnenie P2P: '%s'</translation>
    
ERR
The translation uses the Slovak word "oprávnenie" instead of the Czech equivalent "oprávnění". "oprávnenie" is not correct in Czech.

Correct translation:
Neplatné oprávnění P2P: '%s'
```

<!-- cache_translation_check_cs_5a00de39dbc4b6fecdf9cf98bda7e27b26c36ba48c91c402fa49a59fed992cf0 -->
```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>Neplatná částka %s=&lt;amount&gt;:'%s' (musí být alespoň%s)</translation>
    
ERR
There is a missing space before the last %s in the translation ("alespoň%s" should be "alespoň %s").

Correct translation:
Neplatná částka pro %s=&lt;amount&gt;: '%s' (musí být alespoň %s)
```

<!-- cache_translation_check_cs_5e7ff3563bdf6c3889fec1c8aca0611fdc64755d7a2f1631e0b209fb51a52923 -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>Chyba při načítání %s: Zastaralý typ peněženky. Převeďte ji prosím na deskriptorovou pomocí převodného nástroje (migratewallet RPC)</translation>
    
ERR
Missing noun in "na deskriptorovou" (should be "na deskriptorovou peněženku") and missing final period. "Převodného" is unnatural; "migračního" fits better.

Correct translation:
Chyba při načítání %s: Peněženka je typu legacy. Převeďte ji prosím na deskriptorovou peněženku pomocí migračního nástroje (migratewallet RPC).
```

<!-- cache_translation_check_cs_f38ba91afdc56338ce369458efb74cab5b082824796c660518805e8e55cb478f -->
```
        <source>Transaction requires one destination of non-zero value, a non-zero feerate, or a pre-selected input</source>
        <translation>Transakce vyžaduje jeden cíl nenulové hodnoty, nenulový poplatek nebo předvybraný vstup</translation>
    
ERR
"Feerate" was mistranslated as "poplatek" (fee) instead of "sazba poplatku" (fee rate). Also "of non-zero value" is more natural as "s nenulovou hodnotou".

Correct translation:
Transakce vyžaduje jeden cíl s nenulovou hodnotou, nenulovou sazbu poplatku nebo předem vybraný vstup
```

<!-- cache_translation_check_cs_7dbe4d3bd8b3611230af4faaa6ce145b6c5a4c819c0e60df70d06beaa18b3371 -->
```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Chyba: Nelze přidat pouze-sledovací tx %s do peněženky pro čtení</translation>
    
ERR
The translation "pouze-sledovací tx" is understandable, but "peněženka pro čtení" is incorrect. The term "watchonly wallet" should be translated as "peněženka pouze pro sledování" or "sledovací peněženka". Additionally, it is better to translate "watchonly tx" as "transakci pouze pro sledování".

Correct translation:
Chyba: Nelze přidat transakci pouze pro sledování %s do peněženky pouze pro sledování
```

<!-- cache_translation_check_cs_2a3b61b390d83a02f36b1ec46adfd835fa6d4b83d49e92c70f23b7ff71b0e760 -->
```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Nedostatek volných file deskriptorů. %dvolných, %dvyžadovaných</translation>
    
ERR
There are issues with missing spaces before "volných" and "vyžadovaných", and "file deskriptorů" should be localized as "souborových deskriptorů".

Correct translation:
Nedostatek volných souborových deskriptorů. %d volných, %d vyžadovaných.
```

<!-- cache_translation_check_cs_3588514a0ca418b049d0a08b18f086d4cb13e33cf7cde3f3342f949e132f55bf -->
```
        <source>Unrecognized network in -proxy='%s': '%s'</source>
        <translation>Nerozeznaná síť v -proxy='%s': '%s'</translation>
    
ERR
Word choice is unnatural; "Nerozpoznaná síť" is the standard way to say "Unrecognized network" in Czech.

Correct translation:
Nerozpoznaná síť v -proxy='%s': '%s'
```
</details>

Number of issues: 51.
