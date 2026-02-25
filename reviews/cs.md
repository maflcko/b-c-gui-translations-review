# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bcs%5D%20request)



<details><summary>cs</summary>


<!-- cache_translation_check_cs_3ca95584af0d74951b48f5847796870c9f4091c6aa1a9ef49c4e4db7409b019a -->
```
        <source>Passphrase Dialog</source>
        <translation>Dialog pro zadání hesla</translation>
    
ERR
"Passphrase" is more accurately translated as "přístupová/heslová fráze" rather than "heslo" (password).

Correct translation:
Dialog pro zadání přístupové fráze
```

<!-- cache_translation_check_cs_b875fa49c93f3add21f1153292633dbdaf1a09a5fe895fdac536adf9170a98b6 -->
```
        <source>Repeat new passphrase</source>
        <translation>Zopakujte nové heslo</translation>
    
ERR
"Passphrase" should be translated as "heslová/přístupová fráze," not "heslo."

Correct translation:
Zopakujte novou heslovou frázi
```

<!-- cache_translation_check_cs_75886a51d394fed6d83479207a698b6ff3f9a3102f756563ee18ebc80971c8b2 -->
```
        <source>Custom…</source>
        <translation>Volitelný...</translation>
    
ERR
The translation is inaccurate. For a menu/button label, "Custom…" should be translated as "Vlastní…", not "Volitelný...". Also, the ellipsis should use the single-character ellipsis (…) rather than three dots.

Correct translation:
Vlastní…
```

<!-- cache_translation_check_cs_51102850dc026afddf5d77414bad7bc78453237ebf97788ae48cc35561278082 -->
```
        <source>&amp;Hide</source>
        <translation>&amp;Skryj</translation>
    
ERR
The Czech menu item should use the infinitive form. "Skryj" is an imperative; the standard UI label is "Skrýt".

Correct translation:
&Skrýt
```

<!-- cache_translation_check_cs_05ba27d4cbd6c3936c405531fafd6759687b949bba51a0bb8cb464745549e36b -->
```
        <source>S&amp;how</source>
        <translation>&amp;Zobraz</translation>
    
ERR
The Czech translation uses a truncated imperative ("Zobraz"), which is nonstandard for UI labels. The conventional form is the infinitive.

Correct translation:
&Zobrazit
```

<!-- cache_translation_check_cs_99677164388ff8a20f128384a60f0a62ea67bd0d8c9b0dc5cc22465eeddbd056 -->
```
        <source>Automatically open the Bitcoin client port on the router. This only works when your router supports PCP or NAT-PMP and it is enabled. The external port could be random.</source>
        <translation>Automaticky otevřít port klienta Bitcoinu na routeru. To funguje pouze tehdy, pokud váš router podporuje PCP nebo NAT-PMP a jsou povoleny. Externí port může být náhodný. </translation>
    
ERR
- Agreement issue: "a jsou povoleny" uses plural, but the source says "it is enabled" (singular). Better to refer to the feature in singular.
- Trailing whitespace at the end of the translation.

Correct translation:
Automaticky otevřít port klienta Bitcoinu na routeru. To funguje pouze tehdy, pokud váš router podporuje PCP nebo NAT-PMP a je to povoleno. Externí port může být náhodný.
```

<!-- cache_translation_check_cs_0a8c6c198174c153ad3bacf76a36ef4e4acee734c4c08ef8351e5230be2b118c -->
```
        <source>Font in the Overview tab: </source>
        <translation>Písmo na kartě Přehled:</translation>
    
ERR
Missing trailing space after the colon, which is present in the source and may be needed for UI concatenation.

Correct translation:
Písmo na kartě Přehled:
```

<!-- cache_translation_check_cs_14b3fff8fc7e161cb67d9d6bf2a127640c1fd317fd679852b79a3a334579beb0 -->
```
        <source>(0 = auto, &lt;0 = leave that many cores free)</source>
        <translation>(0 = automaticky, &lt;0 = nechat daný počet jader volný)</translation>
    
ERR
Grammatical agreement issue: "volný" should be plural genitive "volných" to agree with "počet jader".
Correct translation:
(0 = automaticky, <0 = nechat daný počet jader volných)
```

<!-- cache_translation_check_cs_6d3e7e4905239073b780b73c007e2e9652d1c0a2f10cb8d3df4e6820dc9ba301 -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Odečíst &amp;poplatek od výchozí částky</translation>
    
ERR
The translation suggests subtracting the fee from a "default amount" ("od výchozí částky"), which changes the meaning. It should indicate that this is the default behavior to subtract the fee from the amount. Also, "z částky" is the correct preposition.

Correct translation:
Ve výchozím nastavení odečíst &poplatek z částky
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

<!-- cache_translation_check_cs_cc540d33d798b1aaf2e7068a0e2eb626c6362144071cc85e1ecfea348981ebb3 -->
```
        <source>Ban for</source>
        <translation>Zákaz na</translation>
    
ERR
"Zákaz na" is unnatural in Czech; "zákaz" is a noun and typically not used with "na" like this. A more appropriate phrasing for a UI label indicating duration is the verb form.

Correct translation:
Zakázat na
```

<!-- cache_translation_check_cs_265c24c059022e5b0edcfa293bedccfbe3563dc665e97a4dea09a4bc16e17873 -->
```
        <source>An optional label to associate with the new receiving address.</source>
        <translation>Volitelný štítek, který se má přiřadit k nové přijímající adrese.</translation>
    
ERR
The phrase "přijímající adrese" is unnatural in Czech UI; the standard term is "přijímací adrese." Also, "Nepovinný" can be slightly more idiomatic than "Volitelný" here.

Correct translation:
Nepovinný štítek, který se má přiřadit k nové přijímací adrese.
```

<!-- cache_translation_check_cs_aa083e1f9112517c817e0529fa0469fb4e1113b8d6378dfea032e463414e21ad -->
```
        <source>An optional label to associate with the new receiving address (used by you to identify an invoice).  It is also attached to the payment request.</source>
        <translation>Volitelný štítek k přiřazení nové přijímací adrese (použijete jej k identifikaci faktury). Je také připojen k platební žádosti.</translation>
    
ERR
Neobratná a částečně chybná vazba „k přiřazení nové přijímací adrese“. Správně má být „pro přiřazení k nové adrese pro příjem“ nebo obdobně.

Correct translation:
Volitelný štítek pro přiřazení k nové adrese pro příjem (použijete jej k identifikaci faktury). Je také připojen k platební žádosti.
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

<!-- cache_translation_check_cs_afcf0c27409892cbbf34f9e8c91069da004f8676ff4ef78584ae9d68765e4068 -->
```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Jedná se o maximální poplatek, který zaplatíte (navíc k běžnému poplatku), abyste upřednostnili vyhýbání se částečnému utrácení před běžným výběrem mincí.</translation>
    
ERR
The translation omits "transaction" before "fee," which can reduce clarity in this context.

Correct translation:
Jedná se o maximální transakční poplatek, který zaplatíte (navíc k běžnému poplatku), abyste upřednostnili vyhýbání se částečnému utrácení před běžným výběrem mincí.
```

<!-- cache_translation_check_cs_311da9f1d4c8fdc60b484a8d0eb004fc4f1c60163072888e5c02cf1327e513bb -->
```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>Nepodařilo se odstranit adresář snímku stavu řetězce (%s). Před restartem jej ručně jej odstraňte.
</translation>
    
ERR
The Czech translation contains a duplicated word "jej" and slightly awkward word order.

Correct translation:
Nepodařilo se odstranit adresář snímku stavu řetězce (%s). Před restartem jej odstraňte ručně.
```

<!-- cache_translation_check_cs_1fe3c297b5937c367950e3fbfe5e71f673f9d052079a42de9f6a7cfb600ea733 -->
```
        <source>Flushing block file to disk failed. This is likely the result of an I/O error.</source>
        <translation>Nepodařilo se vyprázdnit blokový soubor na disk. Toto je patrně výsledek I/O chyby.</translation>
    
ERR
The phrase "vyprázdnit blokový soubor na disk" is unnatural and misleading in Czech; "flush" refers to flushing buffered data to disk, not emptying the file itself.

Correct translation:
Vyprázdnění (flush) souboru s bloky na disk selhalo. Pravděpodobně došlo k chybě vstupu/výstupu.
```

<!-- cache_translation_check_cs_db3bdd89e3dbb95bffcae6277e2366a7ff2ca2af8fac8efb8d4053a5c85bcaec -->
```
        <source>Flushing undo file to disk failed. This is likely the result of an I/O error.</source>
        <translation>Nepodařilo se vyprázdnit soubor s daty pro návrat na disk. Toto je patrně výsledek I/O chyby.</translation>
    
ERR
"Flushing" was mistranslated as "vyprázdnit" (to empty). In this context it means flushing buffers/writing to disk. Also "undo file" is better rendered directly as "undo soubor" or similar.

Correct translation:
Zápis undo souboru na disk selhal. Pravděpodobně jde o důsledek I/O chyby.
```

<!-- cache_translation_check_cs_0091810b0450aee9e6dcfe0d67d152f153d842764dfa371ec44024bc23780d52 -->
```
        <source>Maximum transaction weight is too low, can not accommodate change output</source>
        <translation>Maximální váha transakce je příliš nízká, nemůže pojmout změnu výstupu</translation>
    
ERR
"change output" was mistranslated as "změnu výstupu" (change of output) instead of the Bitcoin term for a change output. A clearer phrasing also uses "nelze" or "nelze zahrnout".

Correct translation:
Maximální váha transakce je příliš nízká, nelze zahrnout výstup na vrácení
```

<!-- cache_translation_check_cs_53793174b6cc480df647568cb47563edc58a7dc11bd69d221faa60aae234dc23 -->
```
        <source>Rename of '%s' -&gt; '%s' failed. Cannot clean up the background chainstate leveldb directory.</source>
        <translation>Přejmenování '%s' -&gt; '%s' selhalo. Nemohu vyčistit adresář leveldb se stavem řetězce.</translation>
    
ERR
The translation omits "background" and translates the component name "chainstate" descriptively instead of keeping the proper name. Also, impersonal "Nelze" is more appropriate for system messages.

Correct translation:
Přejmenování '%s' -&gt; '%s' selhalo. Nelze vyčistit adresář chainstate LevelDB na pozadí.
```

<!-- cache_translation_check_cs_521ad8f6a419998f0ce5047ebbdd1bee01b5d5f916f2048326180efa81d8ffba -->
```
        <source>The combination of the pre-selected inputs and the wallet automatic inputs selection exceeds the transaction maximum weight. Please try sending a smaller amount or manually consolidating your wallet's UTXOs</source>
        <translation>Kombinace předzvolených vstupů a volba automatických vstupů peněženky přesahuje maximální váhu transakce. Prosím zkuste poslat nižší částku nebo ručně konsolidujte UTXO své peněženky</translation>
    
ERR
Grammar issue: "volba automatických vstupů peněženky" is in nominative, but should be in genitive to match "kombinace X a Y". Also "výběr" is more idiomatic than "volba" here. Word order improved slightly.

Correct translation:
Kombinace předvybraných vstupů a automatického výběru vstupů peněženky přesahuje maximální váhu transakce. Zkuste prosím poslat nižší částku nebo ručně konsolidovat UTXO své peněženky
```

<!-- cache_translation_check_cs_24710a83d085a9c2bf743a6f03ba2a888a6992a819d28a026f143cb34c7c7705 -->
```
        <source>whitebind may only be used for incoming connections ("out" was passed)</source>
        <translation>whitebind může být použit pouze pro příchozí spojení (odchozí byla schválena)</translation>
    
ERR
The parenthetical incorrectly states that outgoing was approved; it should indicate that the literal parameter "out" was passed.

Correct translation:
whitebind smí být použit pouze pro příchozí spojení („out“ byl předán)
```

<!-- cache_translation_check_cs_f5d41f3ba2b39f4a5cd6cbee52cc141c57e9349ef405c5bf87d81825497dd237 -->
```
        <source>A fatal internal error occurred, see debug.log for details: </source>
        <translation>Nastala závažná vnitřní chyba, podrobnosti viz debug.log:</translation>
    
ERR
Missing trailing space after the colon, which may break concatenation formatting.

Correct translation:
Nastala závažná vnitřní chyba, podrobnosti viz debug.log:
```

<!-- cache_translation_check_cs_9b270f488250663f39ba1cc86729d7aac2e6bb0c615ef3729aa165796cafeae7 -->
```
        <source>Assumeutxo data not found for the given blockhash '%s'.</source>
        <translation>Data assumeutxo nenalezena pro zvolený blockhash '%s'.</translation>
    
ERR
Czech grammar and terminology issues: "Data" is plural, so use "nebyla nalezena"; "blockhash" should be "hash bloku"; "zvolený" is less accurate than "daný".

Correct translation:
Data assumeutxo nebyla nalezena pro daný hash bloku '%s'.
```

<!-- cache_translation_check_cs_75766d28cbf0ce6a43add65fee0433371b4e1e36680c98db29ab6f57a153e60c -->
```
        <source>Can't spend unconfirmed version %d pre-selected input with a version 3 tx</source>
        <translation>Nemohu použít nepotvrzenou verzi %d předvybraného vstupu s verzí 3 tx</translation>
    
ERR
The phrasing is unnatural, uses "tx" instead of "transakce", and "použít" is less accurate than "utratit" in this Bitcoin context. Word order around "verze %d" is also better placed after "vstup".

Correct translation:
Nelze utratit nepotvrzený předvybraný vstup verze %d s transakcí verze 3.
```

<!-- cache_translation_check_cs_8a679e4ea9c1be60a54362056b641bd7faabcd39106532de999c585152a9d14a -->
```
        <source>Can't spend unconfirmed version 3 pre-selected input with a version %d tx</source>
        <translation>Nemohu použít nepotvrzenou verzi 3 předvybraného vstupu s verzí %d tx</translation>
    
ERR
The Czech translation is awkward and misleading: it suggests "using an unconfirmed version of an input" rather than "spending an unconfirmed, version 3, pre-selected input". Also "tx" should be translated as "transakce", and impersonal "Nelze" is more appropriate than "Nemohu".

Correct translation:
Nelze utratit nepotvrzený předvybraný vstup verze 3 pomocí transakce verze %d
```

<!-- cache_translation_check_cs_4149af0af8e7c37191fced59cd08325d724b65fa3f182cd06b8cad6b7d580637 -->
```
        <source>Config setting for %s only applied on %s network when in [%s] section.</source>
        <translation>Nastavení pro %s je použito pouze na síťi %s , pokud jste v sekci [%s].</translation>
    
ERR
Typos and style issues: "síťi" should be "síti"; incorrect space before the comma; and the sentence suggests the user is "in the section" instead of the setting. Placeholders are preserved.

Correct translation:
Konfigurační nastavení pro %s se použije pouze v síti %s, pokud je v sekci [%s].
```

<!-- cache_translation_check_cs_75a05508a17bdb80ebe84ce5d7eb2e8674f34d134661a4dfd99ba784483e0526 -->
```
        <source>Corrupt block found indicating potential hardware failure.</source>
        <translation>Nalezen poškožený blok, může to znamenat hw problém.</translation>
    
ERR
Uses an informal abbreviation ("hw") and slightly awkward phrasing. Prefer standard terminology and clearer structure.

Correct translation:
Byl nalezen poškozený blok, což může znamenat selhání hardwaru.
```

<!-- cache_translation_check_cs_4507e5c38afcf0075911691d6f5c4ddda2096440f0b761d55ed6757a74120678 -->
```
        <source>Elliptic curve cryptography sanity check failure. %s is shutting down.</source>
        <translation>Selhala zevrubná prověrka elyptické kryptografie. %s se ukončuje.</translation>
    
ERR
"elyptické" is a misspelling; the correct Czech term is "eliptické" and the natural phrasing is "kryptografie eliptických křivek". Also "sanity check" is better rendered as "kontrola správnosti".

Correct translation:
Selhala kontrola správnosti kryptografie eliptických křivek. %s se ukončuje.
```

<!-- cache_translation_check_cs_edc1846fc03378e37ac25fca6086f215657b1193029fea5ff591b9129f6a3d6c -->
```
        <source>Error: Unable to read wallet's best block locator record</source>
        <translation>Chyba: Není možné číst záznam lokace nejlepšího bloku peněženky</translation>
    
ERR
"lokace" means "location", but "block locator" should be "lokátor bloku". "Není možné číst" is less idiomatic than "Nelze přečíst".

Correct translation:
Chyba: Nelze přečíst záznam lokátoru nejlepšího bloku peněženky
```

<!-- cache_translation_check_cs_1403f56278b1c288c90f964b9edc0029d47d849d756c8823b452076807a4cc41 -->
```
        <source>Error: Unable to write solvable wallet best block locator record</source>
        <translation>Chyba: Nelze zapsat záznam lokace nejlepšího bloku řešitelné peněženky</translation>
    
ERR
"locator" was mistranslated as "lokace" (location). It should be "lokátor" (locator).

Correct translation:
Chyba: Nelze zapsat záznam lokátoru nejlepšího bloku řešitelné peněženky
```

<!-- cache_translation_check_cs_d9bff8949732ba62240f8221907bcecf4a5180ad02dcaed166e61287c1dbb142 -->
```
        <source>Error: Unable to write watchonly wallet best block locator record</source>
        <translation>Chyba: Nelze zapsat záznam lokace nejlepšího bloku peněženky pro sledování</translation>
    
ERR
"watchonly" should be translated as "pouze pro sledování" (watch-only), and "locator" should be "lokátor" rather than "lokace".

Correct translation:
Chyba: Nelze zapsat záznam lokátoru nejlepšího bloku peněženky pouze pro sledování
```

<!-- cache_translation_check_cs_369f1ab523c3f44f3119a8f60db8970b4a6d8ec0c5207acbabbc5a6b8796f9f7 -->
```
        <source>Failed to acquire rescan reserver during wallet initialization</source>
        <translation>Během inicializace peněženky se nepodařilo zajistit práva pro její opětovné proskenování</translation>
    
ERR
"rescan reserver" is mistranslated as "práva" (rights). It refers to a reservation/lock for a rescan, not permissions. Also "proskenování" is colloquial and the possessive "její" is unnecessary.

Correct translation:
Během inicializace peněženky se nepodařilo získat rezervaci pro opětovné prohledání.
```

<!-- cache_translation_check_cs_5b995f859ca5154a74491219725e01dd75f50392ff8070e01a8df2c4e5a95c4a -->
```
        <source>Failed to write undo data.</source>
        <translation>Nepodařilo se zapsat data pro vracení změn</translation>
    
ERR
Missing trailing period compared to the source sentence.

Correct translation:
Nepodařilo se zapsat data pro vracení změn.
```

<!-- cache_translation_check_cs_d6819abf34c35785d6b0b75b2b87c238be4ed32bc4d28787ba53878e1918194b -->
```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s'</source>
        <translation>Neplatná částka %s=&lt;amount&gt;:'%s'</translation>
    
ERR
Missing preposition "pro" and missing space after the colon.

Correct translation:
Neplatná částka pro %s=&lt;amount&gt;: '%s'
```

<!-- cache_translation_check_cs_7bd47b680f93fe6ffdad8b5effa44974b6ad4282f160b11685e85a2c1b2c9d2e -->
```
        <source>A %zu MiB dbcache may be too large for a system memory of only %zu MiB.</source>
        <translation>%zu MiB dbcache může být příliš velká pro systémovou paměť o velikosti %zu MiB.</translation>
    
ERR
The Czech translation has a gender agreement error. The word "dbcache" (database cache) is typically treated as masculine or neuter in technical Czech, but the adjective "velká" is feminine. It should match the neuter "velké" or masculine "velký" to be grammatically correct in this context.

Correct translation:
%zu MiB dbcache může být příliš velké pro systémovou paměť o velikosti %zu MiB.
```

<!-- cache_translation_check_cs_8c3c4ffab7de121db5fcdc9d5f1d2c67b342212c61311c975d4ba4f53c80f0e5 -->
```
        <source>Duplicate binding configuration for address %s. Please check your -bind, -bind=...=onion and -whitebind settings.</source>
        <translation>Vytvořit duplicitní nastavení pro adresu %s. Prosím ověřte nastavení -bind, -bind=...=onion a -whitebind.</translation>
    
ERR
The translation changes the meaning of the first sentence. "Vytvořit duplicitní nastavení" translates to "Create a duplicate configuration," whereas the source text states that a "Duplicate binding configuration" exists (indicates an error or status). In Czech technical contexts, this is usually translated using "Duplicitní nastavení vazby" or simply "Duplicitní konfigurace". Also, "ověřte" is better as "zkontrolujte".

Correct translation:
Duplicitní nastavení vazby pro adresu %s. Zkontrolujte prosím nastavení -bind, -bind=...=onion a -whitebind.
```

<!-- cache_translation_check_cs_6c16a9dcda055994537f3d0b81ab98e22066ec93aff966e092bd48c7a4d59514 -->
```
        <source>Invalid amount for -%s=&lt;amount&gt;: '%s'</source>
        <translation>Neplatná částka -%s=&lt;amount&gt;: '%s'</translation>
    
ERR
The preposition "for" is missing in Czech. It should be "pro -%s".

Correct translation:
Neplatná částka pro -%s=&lt;amount&gt;: '%s'
```

<!-- cache_translation_check_cs_c98201510b8c2a2b42ffddd66e4f7ebb51b6173ceb33fbd25ffb7bc74fab868e -->
```
        <source>Signer did not echo address</source>
        <translation>Podepisovatel nevrátil adresu</translation>
    
ERR
"nevrátil adresu" suggests "did not return," which is misleading. "Echo" here means "repeat/confirm." A clearer translation is:
Podepisovatel nezopakoval adresu
```

<!-- cache_translation_check_cs_7fd39c4e428d983ab2a4bda706c29d5ef1a73c8853ec886298909a2c46ed0a54 -->
```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>acceptstalefeeestimates není podporována na %s řetězu.</translation>
    
ERR
Grammatical gender agreement is incorrect (“není podporována” should be neuter “není podporováno”), and “řetězu” should be “řetězci” in this context.

Correct translation:
acceptstalefeeestimates není podporováno na %s řetězci.
```

<!-- cache_translation_check_cs_f598fd6a32de2f446399e3b01488360667f4aad2f7d765e54f6768316e7ebae2 -->
```
        <source>Error: Dumpfile specifies an unsupported database format (%s). Only sqlite database dumps are supported</source>
        <translation>Chyba: Zvolený formát databáze (%s) není možné uložit do souboru. Pro tento účel lze použít pouze sqlite databázi.</translation>
    
ERR
The translation changes the meaning: it implies the format cannot be saved to a file, while the source says the dump file specifies an unsupported database format. It should indicate only SQLite database dumps are supported.

Correct translation:
Chyba: Soubor s dumpem uvádí nepodporovaný formát databáze (%s). Podporovány jsou pouze dumpy databáze SQLite.
```

<!-- cache_translation_check_cs_45c95e530d5f54581a5e8bd3790237b684b0b98ef34cc1f7e23d2a236f39207d -->
```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on an enormous cluster of unconfirmed transactions.</source>
        <translation>Nepodařilo se vypočítat poplatky za přidání, protože nepotvrzená UTXO závisejí na příliš velkém klastru nepotvrzených transakcí.</translation>
    
ERR
"poplatky za přidání" mistranslates "bump fees" (fee bumping). Better is "poplatky pro navýšení" or "navýšení poplatků". Also "enormous" is better rendered as "obrovském" rather than "příliš velkém", and "nepotvrzené UTXO" is the more natural agreement.

Correct translation:
Nepodařilo se vypočítat poplatky pro navýšení, protože nepotvrzené UTXO závisí na obrovském klastru nepotvrzených transakcí.
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

<!-- cache_translation_check_cs_c424c2e65be2e293546645b3036a4540b42b8030a5017087876f3285a8bf8bb0 -->
```
        <source>Failed to start indexes, shutting down…</source>
        <translation>Start indexace se nezdařil, ukončuji se...</translation>
    
ERR
- "indexes" should be "indexy", not "indexace" (indexing).
- The phrase "Start indexace se nezdařil" is unnatural; better "Nepodařilo se spustit …".
- The ellipsis should match the source character (… instead of ...).

Correct translation:
Nepodařilo se spustit indexy, ukončuji se…
```

<!-- cache_translation_check_cs_37f7fb21adc339858f1cc581dd4e902e3a43742555d65b5d3ffb1b840a1c7036 -->
```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Nedostatek volných souborových deskriptorů. %dvolných, %dvyžadovaných.</translation>
    
ERR
Missing spaces around the format specifiers and slightly awkward phrasing.

Correct translation:
Nedostatek volných souborových deskriptorů. %d k dispozici, %d vyžadováno.
```
</details>

Number of issues: 46.
