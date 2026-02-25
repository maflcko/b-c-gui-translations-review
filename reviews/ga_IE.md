# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bga_IE%5D%20request)



<details><summary>ga_IE</summary>


<!-- cache_translation_check_ga_IE_a8e31db341db4bf6c04b2a78085789cddb5a9706af1e4602c2e262635a88ac9d -->
```
        <source>Right-click to edit address or label</source>
        <translation>Deaschliceáil chun eagarthóireacht seoladh nó lipéad</translation>
    
ERR
The Irish translation is grammatically incorrect. The verb "eagarthóireacht" is a noun (editing) and requires the preposition "ar" (on) or should be used in a different verbal construction to function correctly in this context. Additionally, the definite article "an" should be used before "seoladh" (address).

Correct translation:
Deaschliceáil chun an seoladh nó an lipéad a chur in eagar
```

<!-- cache_translation_check_ga_IE_a76f02c2625faa3c26bf62a305ec068da9a05b182f189ebbf2a0015e2c7e887e -->
```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
ERR
The translation includes the word 'athróige' (variable), which is not in the source text and is technically inaccurate for the CSV (Comma-Separated Values) format, where 'values' (luachanna) is the standard term. A direct translation of the source is more appropriate.

Correct translation:
Comhad camógdheighilte
```

<!-- cache_translation_check_ga_IE_2070d76dae35fbcddd0c442798ac9506e86e9b8a34c623ff5bec7102f214bc0e -->
```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Tharla earráid ag iarraidh an liosta seoltaí a shábháil go %1. Bain triail eile, le d'thoil.</translation>
    
ERR
The translation contains a grammatical/spelling error in the final phrase. "le d'thoil" is incorrect; the standard Irish for "please" is "le do thoil".

Correct translation:
Tharla earráid ag iarraidh an liosta seoltaí a shábháil go %1. Bain triail eile as, le do thoil.
```

<!-- cache_translation_check_ga_IE_e055956e0669a30c9024f71ac27ca71e2a608f0ad4298a803f9ba5f82ec873db -->
```
        <source>Sending addresses - %1</source>
        <translation>Seoltaí á seoladh - %1</translation>
    
ERR
The translation "Seoltaí á seoladh" translates literally to "Addresses being sent," which implies the addresses themselves are currently in transit. In the context of a Bitcoin wallet, "Sending addresses" refers to the address book containing addresses to which the user sends funds.

Correct translation:
Seoltaí seolta - %1
```

<!-- cache_translation_check_ga_IE_3fbf62e4aafbf3e42b3d85ba07d24d2252389dd42aaed59d53e6f25908378c1b -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Iontráil an pasfhrása nua don sparán. &lt;br/&gt;Le do thoil úsáid pasfhocail de &lt;b&gt;dheich gcarachtar randamacha nó níos mó&lt;/b&gt;, nó &lt;/b&gt;ocht bhfocal nó níos mó&lt;/b&gt;.</translation>
    
ERR
The translation contains a syntax error in the HTML tags. Specifically, it uses a closing tag `</b>` where an opening tag `<b>` is required. Additionally, there is a minor inconsistency in terminology ("pasfhrása" vs "pasfhocail").

Correct translation:
Iontráil an pasfhrása nua don sparán.<br/>Le do thoil úsáid pasfhrása de <b>dheich gcarachtar randamacha nó níos mó</b>, nó <b>ocht bhfocal nó níos mó</b>.
```

<!-- cache_translation_check_ga_IE_b7129c9595affa8ad339b2f28f167565b20abe4e176d66214085746d12ebc87d -->
```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Cuimhnigh nach dtugann chriptiú do sparán cosaint go hiomlán do do bitcoins ó bheith goidte ag bogearraí mailíseacha atá ag ionfhabhtú do ríomhaire.</translation>
    
ERR
The translation contains grammatical errors in Irish. 
1. "chriptiú" is incorrectly lenited; it should be "criptiú".
2. After the verbal noun "criptiú", the following noun "sparán" should be in the genitive case ("sparáin").
3. "do do bitcoins" is awkward; "ar do chuid bitcoin" is more idiomatic for "protecting your bitcoins".

Correct translation:
Cuimhnigh nach dtugann criptiú do sparáin cosaint iomlán ar do chuid bitcoin ó bheith goidte ag bogearraí mailíseacha atá ag ionfhabhtú do ríomhaire.
```

<!-- cache_translation_check_ga_IE_140bf467fd94aa37cd5c2788c81753deeebdf6accd68a9a3d19613d296f29251 -->
```
        <source>Your wallet is now encrypted. </source>
        <translation>Tá do sparán criptithe anois.</translation>
    
ERR
The translation is missing the trailing space present in the source text.

Correct translation:
Tá do sparán criptithe anois.
```

<!-- cache_translation_check_ga_IE_d9e711f557c9e279554bdb8f9d15d089e6e642b2e1dbf3307e73b10ccddb2b1b -->
```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Tá an seanphasfhrása a cuireadh isteach le haghaidh díchriptithe an sparán mícheart. Tá carachtar nialasach ann (ie - beart nialasach). Má socraíodh an pasfhrása le leagan den bhogearra seo roimh 25.0, bain triail eile as gan ach na carachtair suas go dtí — ach gan a bheith san áireamh — an chéad charachtar null.</translation>
    
ERR
The Irish translation contains a grammatical error and an inconsistency in terminology. The word "sparán" (wallet) should be in the genitive case ("sparáin") after the verbal noun "díchriptithe". Additionally, the term "null character" is translated as "carachtar nialasach" in the first instance and "carachtar null" in the second; consistency is preferred.

Correct translation:
Tá an seanphasfhrása a cuireadh isteach le haghaidh díchriptithe an sparáin mícheart. Tá carachtar nialasach ann (i.e. - beart nialasach). Má socraíodh an pasfhrása le leagan den bhogearra seo roimh 25.0, bain triail eile as gan ach na carachtair suas go dtí — ach gan a bheith san áireamh — an chéad charachtar nialasach.
```

<!-- cache_translation_check_ga_IE_071cef8df8f79add676e1e50e0713518b8b57e9d90cca34b35297ce5a67c37f9 -->
```
        <source>IP/Netmask</source>
        <translation>PI/Mascadhidirlíon</translation>
    
ERR
The translation of "IP" should not be reversed to "PI". In Irish, "IP" is used as the standard acronym for "Internet Protocol". Additionally, "Mascadhidirlíon" is an incorrect compounding. The correct term for Netmask is "Masc líonra".

Correct translation:
IP/Masc líonra
```

<!-- cache_translation_check_ga_IE_e85f9ffddc57ae0292e8b777a798af95846de0cc905a0b0b5d53820467a63021 -->
```
        <source>Runaway exception</source>
        <translation>Eisceacht runaway</translation>
    
ERR
The translation is a partial translation where "runaway" remains in English. In a technical context in Irish, "runaway" should be translated to "neamhshrianta" or "as smacht".

Correct translation:
Eisceacht neamhshrianta
```

<!-- cache_translation_check_ga_IE_6fc024f815f9d7f3f6010841e7ecdbc051401b621ea672957c106dded4fadd9f -->
```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>Fearacht</translation>
    
ERR
The translation "Fearacht" is incorrect. In Irish, "fearacht" means "likeness," "manner," or "similarity" (often used in phrases like "d'fhearacht sin" meaning "like that"). It does not convey the technical meaning of a "feeler" connection, which is a probe or test connection used to determine if a node is active.

Correct translation:
Taiscéalaí
```

<!-- cache_translation_check_ga_IE_e6e817163c1ca1d06bef96d42333f1f0fa7cac79dde80df243a268fb9b8b7dcc -->
```
        <source>Address Fetch</source>
        <extracomment>Short-lived peer connection type that solicits known addresses from a peer.</extracomment>
        <translation>Seoladh Fetch</translation>
    
ERR
The translation is problematic because it leaves the English word "Fetch" untranslated and uses the singular "Seoladh" (Address) which doesn't fully capture the meaning of the peer connection type described in the context. In Irish, "Fetch" should be translated as "Aisghabháil" (Retrieval) or "Fáil" (Getting).

Correct translation:
Aisghabháil Seoltaí
```

<!-- cache_translation_check_ga_IE_74e24fe087000a9b3b2c9d78373d41b12f97ff66ab2b34d55167f07aba31dd70 -->
```
        <source>&amp;Overview</source>
        <translation>&amp;Forléargas </translation>
    
ERR
The translation contains an unnecessary trailing space.

Correct translation:
&Forléargas
```

<!-- cache_translation_check_ga_IE_85fd062f7e513ce6ef45f1e5fa6723eff4e323f79c7533f6b724cb65b68438d8 -->
```
        <source>&amp;Transactions</source>
        <translation>&amp;Idirbheart</translation>
    
ERR
The translation uses the singular "Idirbheart" (Transaction) instead of the plural "Idirbhearta" (Transactions).

Correct translation:
&Idirbhearta
```

<!-- cache_translation_check_ga_IE_0aeb36ca30a8c45ae13041e866901ee4d17eff0a1f92db75d815bbc1f65199d4 -->
```
        <source>Quit application</source>
        <translation>Scoir feidhm</translation>
    
ERR
The translation "Scoir feidhm" is slightly inaccurate. In Irish, "feidhm" means "function" or "use," whereas "feidhmchlár" is the standard term for a software "application." Additionally, the phrasing lacks a preposition or article typically required in this context.

Correct translation:
Scoir den fheidhmchlár
```

<!-- cache_translation_check_ga_IE_d4eb21a1a8275506f209dac7e12134abfa528e081acf6cf7d52bce994620542e -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>&amp;Sparán Cúltaca…</translation>
    
ERR
The translation uses the incorrect word order and grammatical structure for a menu command. "Sparán Cúltaca" translates to "Backup Wallet" as a noun phrase (i.e., a wallet that is a backup), whereas the source is an action/command to perform a backup of the wallet. In Irish, the action or the thing being created should come first.

Correct translation:
&Cúltaca an Sparáin…
```

<!-- cache_translation_check_ga_IE_71f105c04bc3a7839d47ee7c3517f00982e44c7a44bb32089d473533a48f1587 -->
```
        <source>Syncing Headers (%1%)…</source>
        <translation>Ceanntásca á Sioncronú (%1 %)…</translation>
    
ERR
The translation includes a stray space between the placeholder and the percentage symbol that is not present in the source text. In the context of software localization, format specifiers and their immediate suffixes should usually match the source to ensure consistent UI display.

Correct translation:
Ceanntásca á Sioncronú (%1%)…
```

<!-- cache_translation_check_ga_IE_1a9d7941ee4ff8f43e33d55452428a54bf7b4af55623f65cfad4a23c72510b17 -->
```
        <source>Show the list of used sending addresses and labels</source>
        <translation>Taispeáin an liosta de seoltaí seoladh úsáidte agus na lipéid </translation>
    
ERR
There is a stray trailing space at the end of the translation. Additionally, the Irish grammar is slightly incorrect; "de" should cause lenition on the following word ("sheoltaí"), and the phrase "seoltaí seoladh" is redundant.

Correct translation:
Taispeáin liosta na seoltaí seolta úsáidte agus na lipéid
```

<!-- cache_translation_check_ga_IE_110e3bbacaa2fb46955a1a8b1f16300bf5ca8e9857789997534eed7a6e1f642a -->
```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>Taispeáin an liosta de seoltaí glacadh úsáidte agus lipéid </translation>
    
ERR
The translation contains an unnecessary trailing space and has minor grammatical issues in Irish. The phrase "seoltaí glacadh" should be "seoltaí glactha" (genitive case) for better fluency.

Correct translation:
Taispeáin an liosta de sheoltaí glactha agus lipéid a úsáideadh
```

<!-- cache_translation_check_ga_IE_5eba5026e7c08615b056af4d6ad5f8fa16ec4c7ff66d502ffde8c91ee0f8d49e -->
```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Lódáil Idirbheart Bitcoin Sínithe go Páirteach ón gearrthaisce</translation>
    
ERR
The translation is mostly accurate but contains a minor grammatical error in Irish. The prepositional contraction "ón" (from the) should cause lenition (séimhiú) on the following noun "gearrthaisce" (clipboard), which is feminine. Additionally, "Luchtaigh" is often preferred over "Lódáil" for the action of loading data or a file in a software context.

Correct translation:
Luchtaigh Idirbheart Bitcoin Sínithe go Páirteach ón ghearrthaisce
```

<!-- cache_translation_check_ga_IE_04e25357b9ac5d8ea3b71e252ab44f23bfe1ecb661ddebb328d2250184589aa3 -->
```
        <source>&amp;Sending addresses</source>
        <translation>&amp;Seoltaí seoladh</translation>
    
ERR
The Irish translation is grammatically incorrect. "Seoladh" is the singular noun for "address" or the verbal noun for "sending". When modifying the plural noun "Seoltaí" (addresses), it should be in the genitive case "seolta". "Seoltaí seoladh" is redundant and grammatically awkward (literally "Addresses address").

Correct translation:
&Seoltaí seolta
```

<!-- cache_translation_check_ga_IE_263a2778887a4aa3cb2096a87baef72b976e86a2f67c26bacf4282518fce58fe -->
```
        <source>Migrate a wallet</source>
        <translation>Imirce sparán</translation>
    
ERR
The translation "Imirce sparán" is grammatically incorrect. "Imirce" is a noun (migration) or the verbal noun (migrating). If used as a verbal noun, the following noun "sparán" (wallet) must be in the genitive case, which is "sparáin". However, since "Migrate a wallet" is likely a command/action in a menu, the imperative form of the verb is more appropriate.

Correct translation:
Imirigh sparán
```

<!-- cache_translation_check_ga_IE_3f39686b57742bc697792de8feeb01fee0d369a455df236054401d2835074a0f -->
```
        <source>Restore and Migrate Wallet Backup</source>
        <translation>Athchóirigh agus Imircigh Cúltaca Sparán</translation>
    
ERR
The translation contains a grammatical inconsistency. "Athchóirigh" is the singular imperative (command) form, whereas "Imircigh" is the plural imperative form (or the plural noun for "migrants"). In software interfaces, the singular imperative is the standard for actions. To be consistent, both verbs should be in the singular imperative form.

Correct translation:
Athchóirigh agus Imirigh Cúltaca Sparáin
```

<!-- cache_translation_check_ga_IE_03cbb155ca83e1456ca979df7bbe8c9d47a30c516b5f4fe215156601b12d3f04 -->
```
        <source>Restore and Migrate Wallet</source>
        <extracomment>Title of pop-up window shown when the user is attempting to restore a wallet.</extracomment>
        <translation>Athchóirigh agus Imirce Sparán</translation>
    
ERR
The translation mixes a verb form ("Athchóirigh" - Restore) with a noun form ("Imirce" - Migration), which makes the phrase grammatically inconsistent and awkward in Irish. For a window title, it is better to use either two imperative verbs or two verbal nouns. Additionally, "Sparán" should be in the genitive case ("Sparáin") if following the noun "Imirce".

Correct translation:
Athchóirigh agus Imirigh Sparán
```

<!-- cache_translation_check_ga_IE_b3a4d3e16cfb22170ee3731d15a295985c684c00f55bfd488ec3fcc35d7ed427 -->
```
        <source>S&amp;how</source>
        <translation>S&amp;conas</translation>
    
ERR
The translation "S&conas" is incorrect. "Conas" means "How" in Irish, whereas "Show" (to display) should be translated as "Taispeáin".

Correct translation:
&Taispeáin
```

<!-- cache_translation_check_ga_IE_48c4ed924961c1a9373f42a09cf1863fd5d965d992b23668e00a04a7910700cb -->
```
        <source>Pre-syncing Headers (%1%)…</source>
        <translation>Ceanntásca a réamhshioncronú (%1 %)…</translation>
    
ERR
The translation includes a stray space within the format specifier. The source uses "%1%" (no space between the placeholder and the percent sign), whereas the translation uses "%1 %".

Correct translation:
Ceanntásca a réamhshioncronú (%1%)…
```

<!-- cache_translation_check_ga_IE_dd1e7dfd96cdcd3d16e2fd27f51da47248d6e6db97ee9537d326ff4820328d01 -->
```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Sparán &lt;b&gt;criptithe&lt;/b&gt;agus &lt;b&gt;díghlasáilte&lt;/b&gt;faoi láthair</translation>
    
ERR
There are missing spaces before and after the HTML tags, causing the words to run together ("criptitheagus" and "díghlasáiltefaoi").

Correct translation:
Sparán &lt;b&gt;criptithe&lt;/b&gt; agus &lt;b&gt;díghlasáilte&lt;/b&gt; faoi láthair
```

<!-- cache_translation_check_ga_IE_be59dc72cfec6bdd6a0cc2415ab0b047308cfbbab75c957346981295e622e5a0 -->
```
        <source>(un)select all</source>
        <translation>(neamh)roghnaigh gach rud </translation>
    
ERR
The translation contains a trailing space that is not present in the source text.

Correct translation:
(neamh)roghnaigh gach rud
```

<!-- cache_translation_check_ga_IE_2987c34b3c40cbcc2a523c1b8a97c26d03fe5501faf091ab547ba5b2a4257e0a -->
```
        <source>Received with label</source>
        <translation>Lipéad faighte le</translation>
    
ERR
The translation "Lipéad faighte le" literally means "Label received with", which reverses the meaning of the source text. The source "Received with label" indicates that an item (like a transaction) was received and is associated with a specific label.

Correct translation:
Faighte le lipéad
```

<!-- cache_translation_check_ga_IE_61a5501bb18f00c6d00c17fd5b7f2692ac6e452d52190565b7884243493f84da -->
```
        <source>Received with address</source>
        <translation>Seoladh faighte le</translation>
    
ERR
The word order in the translation is incorrect. "Seoladh faighte le" translates to "Address received with", whereas the source "Received with address" should be translated as "Faighte le seoladh".

Correct translation:
Faighte le seoladh
```

<!-- cache_translation_check_ga_IE_96b9c8575155dfa87acb5e70e5b5d39b14c6301dd11504d6c4798bf5f33bb425 -->
```
        <source>Copy &amp;amount</source>
        <translation>Cóipeáil &amp; méid</translation>
    
ERR
There is an unnecessary space between the shortcut key indicator '&' and the word 'méid'. In the source, the indicator is directly attached to the word it modifies.

Correct translation:
Cóipeáil &méid
```

<!-- cache_translation_check_ga_IE_be2e9a849d17372c754346d482becc89251ab2753a2db5468a752a077f6adf6a -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>Cóipeáil idirbheart &amp; ID agus innéacs aschuir</translation>
    
ERR
The translation contains a whitespace format issue. In the context of shortcut keys (indicated by the '&' symbol), there should not be a space between the ampersand and the character it precedes. Additionally, the phrasing "idirbheart ID" is a literal word-for-word translation; in Irish, the genitive case "ID idirbhirt" is more grammatically correct.

Correct translation:
Cóipeáil &ID an idirbhirt agus innéacs an aschuir
```

<!-- cache_translation_check_ga_IE_fc873d44d2912b1da0def4f8c6e6bcd003e202bdd23c709c81b92a9028bf94b2 -->
```
        <source>Copy fee</source>
        <translation>Cóipeáíl táille</translation>
    
ERR
The translation contains a typo in the word "Cóipeáil". The provided text "Cóipeáíl" has an extra "í" before the "l".

Correct translation:
Cóipeáil an táille
```

<!-- cache_translation_check_ga_IE_6c562af98fecd806205fe66267494b3f577edf6f87c32eb3d86b63f65c2c6c8f -->
```
        <source>Copy after fee</source>
        <translation>Cóipeáíl iar-tháille</translation>
    
ERR
There is a typo in the word "Cóipeáíl". The letter 'i' should not have an accent (fada).

Correct translation:
Cóipeáil iar-tháille
```

<!-- cache_translation_check_ga_IE_05febe321304719e316f8459f29106ce1d11c28786cffea8de7a2b4e59ae85e2 -->
```
        <source>Copy bytes</source>
        <translation>Cóipeáíl bearta</translation>
    
ERR
There is a spelling error in the word "Cóipeáíl". The correct spelling is "Cóipeáil" (only the 'a' should have an accent).

Correct translation:
Cóipeáil bearta
```

<!-- cache_translation_check_ga_IE_f76515df9b1327b7dff3c27143b961a7b5039149a0885aa08c6c3154559e7da7 -->
```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
ERR
The translation contains a misspelling. "Cóipeáíl" has an incorrect accent on the 'i'. The correct Irish word for "Copy" is "Cóipeáil".

Correct translation:
Cóipeáil sóinseáil
```

<!-- cache_translation_check_ga_IE_a76c78ad100d1eb8958f584abcdf19afe196765686730938af333148297f778a -->
```
        <source>Create wallet warning</source>
        <translation>Rabhadh cruthú  sparán</translation>
    
ERR
There is a double space between "cruthú" and "sparán".

Correct translation:
Rabhadh cruthú sparán
```

<!-- cache_translation_check_ga_IE_3569e1e271d3f6d27ce1258ba39c8cab6f3a5a010e5067ed3caf2ec713478772 -->
```
        <source>Load Wallets</source>
        <extracomment>Title of progress window which is displayed when wallets are being loaded.</extracomment>
        <translation>Luchtaigh Sparán</translation>
    
ERR
The translation uses the singular form of "wallet" instead of the plural. "Sparán" is singular, while "Sparáin" is plural. Since the source text is "Load Wallets" (plural), the translation should reflect that.

Correct translation:
Luchtaigh Sparáin
```

<!-- cache_translation_check_ga_IE_707d6e91cbd2210d610124af703b9ad5f588a86515a1da892e4f32d3eb7c7184 -->
```
        <source>Loading wallets…</source>
        <extracomment>Descriptive text of the load wallets progress window which indicates to the user that wallets are currently being loaded.</extracomment>
        <translation>Sparán á lódáil…</translation>
    
ERR
The English source "Loading wallets…" uses the plural form "wallets," whereas the Irish translation "Sparán á lódáil…" uses the singular "sparán" (wallet). The plural of "sparán" is "sparáin."

Correct translation:
Sparáin á lódáil…
```

<!-- cache_translation_check_ga_IE_d041ae8cf491f80d6f21695da32ac3ed0f6ebfe7b2af96807e6120b8a73d5d5a -->
```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>An bhfuil tú cinnte gur mian leat an sparán &lt;i&gt;%1 &lt;/i&gt;?</translation>
    
ERR
The translation is incomplete and contains a formatting error. It omits the verb "migrate" (imirce), effectively saying "Are you sure you wish the wallet %1?". It also adds an unnecessary space inside the HTML tags (`%1 ` instead of `%1`).

Correct translation:
An bhfuil tú cinnte gur mian leat an sparán <i>%1</i> a imirce?
```

<!-- cache_translation_check_ga_IE_0cb5517d064789eeba522b0c267cf8ebe08a8ed90ef66eecfe69d47f50b5867e -->
```
        <source>Restore and Migrate wallet</source>
        <translation>Athchóirigh agus Imirce an sparán</translation>
    
ERR
The translation "Athchóirigh agus Imirce an sparán" is grammatically incorrect. "Athchóirigh" is an imperative verb (Restore), but "Imirce" is a noun (Migration). To match the English source "Restore and Migrate", both should be in the imperative verb form. Additionally, if "Imirce" were used as a verbal noun, the following noun "sparán" would need to be in the genitive case ("an sparáin").

Correct translation:
Athchóirigh agus Imiric an sparán
```

<!-- cache_translation_check_ga_IE_245568772c1b96681974e1b909ccb02b122b337a94e3ad9b08d63e9528c2b06a -->
```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Sparán á Athchóiriú&lt;b&gt;%1&lt;/b&gt;…</translation>
    
ERR
There is a missing space before the tag <b> and the word order is unnatural for the context. In the source text, there is a space between "Wallet" and "<b>%1</b>". In the translation, the space between the Irish verb "Athchóiriú" and "<b>%1</b>" is missing. Additionally, the phrase would be more naturally structured in Irish by placing the wallet name before the verbal noun phrase.

Correct translation:
Sparán <b>%1</b> á athchóiriú…
```

<!-- cache_translation_check_ga_IE_55fff6813b168cbfea8a5bc3eeabe18891a2cc5e469d736d4a122d1069472b3d -->
```
        <source>Open wallet failed</source>
        <translation>Theip ar oscail sparán</translation>
    
ERR
The Irish translation is grammatically incorrect. "Theip ar" (failed) should be followed by a verbal noun, or the structure should be rearranged. "Oscail" is the imperative/base form of the verb, whereas "oscailt" is the verbal noun.

Correct translation:
Theip ar oscailt an sparáin
```

<!-- cache_translation_check_ga_IE_f869aed177e38e4e0a4232f5c62c1d1124cf487e98b0e75d526c8bf0137a530e -->
```
        <source>Open wallet warning</source>
        <translation>Rabhadh oscail sparán</translation>
    
ERR
The Irish translation is grammatically incorrect. It uses the imperative verb "oscail" (open) instead of the verbal noun "oscailt" (opening), and "sparán" should be in the genitive case "sparáin".

Correct translation:
Rabhadh faoi oscailt sparáin
```

<!-- cache_translation_check_ga_IE_f68e95f5d08b1ceccbb0c523c9e4b55b5fc511a0456e3b41be3420fd8942ef6d -->
```
        <source>Opening Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the open wallet progress window which indicates to the user which wallet is currently being opened.</extracomment>
        <translation>Sparán Oscailte&lt;b&gt;%1&lt;/b&gt;…</translation>
    
ERR
The Irish translation is grammatically incorrect for the context of an ongoing action. "Sparán Oscailte" translates to "Open Wallet" (as in a wallet that is already open or a command to open one), whereas the English source "Opening..." indicates a continuous process. In Irish, the progressive aspect is formed using "Ag oscailt".

Correct translation:
Ag oscailt Sparáin &lt;b&gt;%1&lt;/b&gt;…
```

<!-- cache_translation_check_ga_IE_245568772c1b96681974e1b909ccb02b122b337a94e3ad9b08d63e9528c2b06a -->
```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Sparán á Athchóiriú&lt;b&gt;%1&lt;/b&gt;…</translation>
    
ERR
There is a missing space before the tag <b> and the word order is unnatural for the context. In the source text, there is a space between "Wallet" and "<b>%1</b>". In the translation, the space between the Irish verb "Athchóiriú" and "<b>%1</b>" is missing. Additionally, the phrase would be more naturally structured in Irish by placing the wallet name before the verbal noun phrase.

Correct translation:
Sparán <b>%1</b> á athchóiriú…
```

<!-- cache_translation_check_ga_IE_110333f06ac1cd350f19c4c5b701325bb4a4c30b6776ff5be55cfd53b64bc353 -->
```
        <source>Restore wallet warning</source>
        <extracomment>Title of message box which is displayed when the wallet is restored with some warning.</extracomment>
        <translation>Athchóirigh rabhadh sparán</translation>
    
ERR
The current translation "Athchóirigh rabhadh sparán" is a literal word-for-word translation that results in a command meaning "Restore [the] wallet warning." Since this is the title of a message box, it should be a noun phrase. In Irish, the noun "Rabhadh" (Warning) should come first, followed by the verbal noun "athchóirithe" (restoring/restoration).

Correct translation:
Rabhadh athchóirithe sparáin
```

<!-- cache_translation_check_ga_IE_0e585a5ef038709071eec06768f45d6a3e93c6077b0939052e36bef36e262590 -->
```
        <source>Restore wallet message</source>
        <extracomment>Title of message box which is displayed when the wallet is successfully restored.</extracomment>
        <translation>Athchóirigh teachtaireacht sparán</translation>
    
ERR
The translation uses the imperative verb "Athchóirigh" (Restore!), making it sound like a command to restore a message. Since the context specifies this is a title for a message box displayed after a wallet has been successfully restored, it should be a noun phrase.

Correct translation:
Teachtaireacht athchóirithe sparáin
```

<!-- cache_translation_check_ga_IE_af2c58649a3db286d314f56c81e53887f079bf7b361d3277989dcfa635a824ca -->
```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>Mar thoradh ar dúnadh an sparán ar feadh ró-fhada, d’fhéadfadh  gá sioncronú leis an slabhra iomlán arís má tá bearradh cumasaithe.</translation>
    
ERR
The translation contains a double space after the word "d’fhéadfadh" and the phrasing "d’fhéadfadh gá" is grammatically incomplete in Irish; it requires a verb like "a bheith" (to be) to function correctly (i.e., "d’fhéadfadh sé a bheith riachtanach").

Correct translation:
D’fhéadfadh sé go mbeadh gá leis an slabhra iomlán a athshioncronú má dhúntar an sparán ar feadh rófhada agus má tá bearradh cumasaithe.
```

<!-- cache_translation_check_ga_IE_fe66029292be3cb7238d4ff6170831b9a1e332258273e0be95c4eb2a9f8e6409 -->
```
        <source>Wallet Name</source>
        <translation>Ainm Sparán</translation>
    
ERR
In Irish grammar, when one noun follows another to indicate a relationship (like "Wallet Name" or "Name of a Wallet"), the second noun must be in the genitive case. The genitive form of "sparán" is "sparáin".

Correct translation:
Ainm Sparáin
```

<!-- cache_translation_check_ga_IE_f15780cb9b7522bf9ade49b168c3220aa4b0e938910c75d66512849c1b758f7d -->
```
        <source>Edit Address</source>
        <translation>Eagarthóireacht Seoladh</translation>
    
ERR
The Irish translation is grammatically incorrect. When one noun qualifies another in Irish, the second noun must be in the genitive case. "Seoladh" (Address) should be in the genitive form "Seolta". Additionally, for a UI label or window title, "Eagar" or "Cuir in eagar" is more common than the verbal noun "Eagarthóireacht".

Correct translation:
Eagar an tSeolta
```

<!-- cache_translation_check_ga_IE_a216d83ab8481bfa90cc9aa355b018abdea519c131427858d4c36d1d96985cf0 -->
```
        <source>The label associated with this address list entry</source>
        <translation>An lipéad chomhcheangailte leis an iontráil liosta seoltaí seo</translation>
    
ERR
The word 'chomhcheangailte' is incorrectly lenited. In Irish, a masculine singular noun like 'lipéad' in the nominative case does not cause lenition on the following adjective.

Correct translation:
An lipéad comhcheangailte leis an iontráil liosta seoltaí seo
```

<!-- cache_translation_check_ga_IE_16a829ea7557691e9e0377a6fe0f9de4a648186fe1018f8ce46caccf5a019625 -->
```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>An seoladh chomhcheangailte leis an iontráil liosta seoltaí seo. Ní féidir é seo a mionathraithe ach do seoltaí seoladh.</translation>
    
ERR
The Irish translation contains a grammatical error and a repetitive phrasing. "Ní féidir é seo a mionathraithe" is incorrect; the verbal noun "mionathrú" should be used instead of the past participle "mionathraithe" after "a". Additionally, "seoltaí seoladh" is a clunky way to translate "sending addresses".

Correct translation:
An seoladh a bhaineann leis an iontráil liosta seoltaí seo. Ní féidir é seo a mhionathrú ach le haghaidh seoltaí seolta.
```

<!-- cache_translation_check_ga_IE_511f70952f678ca37e9af45a5d8f70831ccfdac0c6951b6ffc94b170c299618e -->
```
        <source>New sending address</source>
        <translation>Seoladh nua seoladh</translation>
    
ERR
The translation is repetitive and grammatically incorrect. "Seoladh" means both "address" and "sending" (verbal noun). The phrase "Seoladh nua seoladh" translates literally to "Address new address" or "Sending new address".

Correct translation:
Seoladh seolta nua
```

<!-- cache_translation_check_ga_IE_09d99ec7f5701653c1901384e8c9e002ea803bf664570f1ce69e0660b8e0a4c2 -->
```
        <source>Edit receiving address</source>
        <translation>Eagarthóireacht seoladh glactha</translation>
    
ERR
The translation is grammatically incorrect in Irish. "Eagarthóireacht" is a noun meaning "editing," and when followed by another noun, it should typically trigger the genitive case or be preceded by a preposition. Furthermore, for a UI action like "Edit," it is more natural to use a verbal construction.

Correct translation:
Cuir seoladh glactha in eagar
```

<!-- cache_translation_check_ga_IE_7f8254ab58a12f0acb39c67dc845b3c7a558b84e685714f1f03c43c652b8e3a1 -->
```
        <source>Edit sending address</source>
        <translation>Eagarthóireacht seoladh seoladh</translation>
    
ERR
The translation "seoladh seoladh" is a literal word-for-word translation that is repetitive and grammatically awkward in Irish. In this context, "seoladh" is the word for both "sending" and "address". To distinguish them and sound natural, "sending address" should be translated as "seoladh seolta".

Correct translation:
Eagarthóireacht ar an seoladh seolta
```

<!-- cache_translation_check_ga_IE_7097bf34f143965b7e00e1a416a5e1ff225bbf509662891ebffc847cf96af30a -->
```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Níl seoladh bailí Bitcoin í an seoladh iontráilte "%1".</translation>
    
ERR
The translation contains grammatical errors in Irish. Specifically, it uses the substantive verb "Níl" where the copula "Ní" is required for classification/identification. Furthermore, "seoladh" (address) is a masculine noun, so the masculine pronoun "é" should be used instead of the feminine "í".

Correct translation:
Ní seoladh bailí Bitcoin é an seoladh iontráilte "%1".
```

<!-- cache_translation_check_ga_IE_f440b78427df64e7abb6762e89dcbf62e3d419afff84866da9f8421c53c3f173 -->
```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>Tá an seoladh a iontráladh "%1" sa leabhar seoltaí cheana féin le lipéad "%2"</translation>
    
ERR
The translation is missing the trailing period that is present in the source text.

Correct translation:
Tá an seoladh a iontráladh "%1" sa leabhar seoltaí cheana féin le lipéad "%2".
```

<!-- cache_translation_check_ga_IE_d75f1ca219d2bc928bc3825a2696818b30635dd4bf6cdd3f488c1e971e2a5d92 -->
```
        <source>A new data directory will be created.</source>
        <translation>Cruthófar eolaire sonraíocht nua.</translation>
    
ERR
The word 'sonraíocht' means 'specification'. The correct word for 'data' in Irish is 'sonraí'.

Correct translation:
Cruthófar eolaire sonraí nua.
```

<!-- cache_translation_check_ga_IE_4911b43d6c2d61a01b08433625d4cd92ef16492f57ebbd88100d34685839c4ec -->
```
        <source>Cannot create data directory here.</source>
        <translation>Ní féidir eolaire sonraíocht a chruthú anseo.</translation>
    
ERR
The translation uses the word "sonraíocht" (specification) instead of "sonraí" (data).

Correct translation:
Ní féidir eolaire sonraí a chruthú anseo.
```

<!-- cache_translation_check_ga_IE_b1a48a52abb04535f81224c7846dca9e44ecb2ec24a030acac853a2b238afce7 -->
```
        <source>Use the default data directory</source>
        <translation>Úsáid an comhadlann sonraí réamhshocrú</translation>
    
ERR
The translation contains a grammatical error. The Irish word 'comhadlann' (directory) is a feminine noun. When preceded by the definite article 'an', it should be lenited (add an 'h'). Additionally, 'réamhshocraithe' is the standard adjective for 'default'.

Correct translation:
Úsáid an chomhadlann sonraí réamhshocraithe
```

<!-- cache_translation_check_ga_IE_72cf248f61b11b4b980de99d8ea02848dd866ed00df453bc9dde6eac6872cc72 -->
```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Ar a laghad stórálfar %1 GB de shonraí  sa comhadlann seo, agus fásfaidh sé le himeacht ama.</translation>
    
ERR
The translation contains a double space and a grammatical error. "sa" causes lenition on feminine nouns like "comhadlann", so it should be "sa chomhadlann".

Correct translation:
Ar a laghad stórálfar %1 GB de shonraí sa chomhadlann seo, agus fásfaidh sé le himeacht ama.
```

<!-- cache_translation_check_ga_IE_3889859f5376cadf343ffd28833f0421ffd372555c1e9e015831b5abd2f2d06a -->
```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Stórálfar thart ar %1 GB de shonraí sa comhadlann seo.</translation>
    
ERR
The Irish grammar is incorrect. After the prepositional contraction 'sa' (in the), a feminine noun like 'comhadlann' should be lenited.

Correct translation:
Stórálfar thart ar %1 GB de shonraí sa chomhadlann seo.
```

<!-- cache_translation_check_ga_IE_ed27087547d23e8f6eb715aa5147c23772f18fbe02a00bcde77c8fa090789f12 -->
```
        <source>%1 will download and store a copy of the Bitcoin block chain.</source>
        <translation>Íoslódáileafar %1 and stórálfaidh cóip de bhlocshlabhra Bitcoin.</translation>
    
ERR
The translation contains an English word ("and") instead of the Irish word "agus". Additionally, the verb "Íoslódáileafar" is in the autonomous form (meaning "%1 will be downloaded"), whereas the source indicates that %1 is the subject performing the action.

Correct translation:
Íoslódálfaidh agus stórálfaidh %1 cóip de bhlocshlabhra Bitcoin.
```

<!-- cache_translation_check_ga_IE_1ed7f6378cc3562032f1f8e033ae59c1d4f0ae08a8faa7e4f3df80da604775cb -->
```
        <source>Recent transactions may not yet be visible, and therefore your wallet's balance might be incorrect. This information will be correct once your wallet has finished synchronizing with the bitcoin network, as detailed below.</source>
        <translation>B’fhéidir nach mbeidh idirbhearta dheireanacha le feiceáil fós, agus dá bhrí sin d’fhéadfadh go mbeadh iarmhéid do sparán mícheart. Beidh an faisnéis seo ceart nuair a bheidh do sparán críochnaithe ag sioncrónú leis an líonra bitcoin, mar atá luaite thíos.</translation>
    
ERR
The translation contains minor grammatical errors in Irish.
1. "idirbhearta dheireanacha": The noun "idirbhearta" is a strong plural, so the following adjective should not be lenited. It should be "idirbhearta deireanacha".
2. "an faisnéis": The noun "faisnéis" is feminine, so it should be lenited after the definite article "an". It should be "an fhaisnéis".

Correct translation:
B’fhéidir nach mbeidh idirbhearta deireanacha le feiceáil fós, agus dá bhrí sin d’fhéadfadh go mbeadh iarmhéid do sparán mícheart. Beidh an fhaisnéis seo ceart nuair a bheidh do sparán críochnaithe ag sioncrónú leis an líonra bitcoin, mar atá luaite thíos.
```

<!-- cache_translation_check_ga_IE_de4a28ad4851dd1c83bef6556d8c6378fedf4e4468733a6fc91f2fc1469f1306 -->
```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>Tá %1 ag sioncronú faoi láthair. Déanfaidh sé é a íoslódáil agus a fíorú ar ceanntásca agus bloic ó phiaraí go dtí barr an blocshlabhra.</translation>
    
ERR
The Irish translation contains several grammatical errors and awkward phrasing.
1. The structure "Déanfaidh sé é a íoslódáil agus a fíorú ar ceanntásca agus bloic" is grammatically incorrect. In Irish, the object should precede the verbal nouns, and the preposition "ar" is incorrectly used here.
2. "a fíorú" should be "iad a fhíorú" to reflect "validate them" (plural).
3. "barr an blocshlabhra" should use the genitive case: "barr an bhlocshlabhra".
4. The double space after the first sentence in the source is missing in the translation.

Correct translation:
Tá %1 ag sioncronú faoi láthair.  Íoslódálfaidh sé ceanntásca agus bloic ó phiaraí agus fíoróidh sé iad go dtí go sroichfear barr an bhlocshlabhra.
```

<!-- cache_translation_check_ga_IE_d615a9a52da311109e585a1fa441a5e4f25dfd3a90eb4391ab343380abcafa73 -->
```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Anaithnid. Ceanntásca a Réamhshioncronú (%1, %2 %)…</translation>
    
ERR
There is an unnecessary space between the format specifier '%2' and the percent sign '%'. In the source text, they are adjacent.

Correct translation:
Anaithnid. Ceanntásca a Réamhshioncronú (%1, %2%)…
```

<!-- cache_translation_check_ga_IE_a9b23d660b29498a1b4d99b8e009dbb1c15186c29260d511a2d8ed839e77546a -->
```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Greamaigh seoladh ón gearrthaisce</translation>
    
ERR
The Irish translation contains a minor grammatical error. In Irish, the prepositional contraction 'ón' (from the) causes lenition on the following noun if it starts with a lenitable consonant (like 'g'), unless that consonant is 'd', 't', or 's'. Since 'gearrthaisce' is a feminine noun starting with 'g', it should be lenited to 'ghearrthaisce'.

Correct translation:
Greamaigh seoladh ón ghearrthaisce
```

<!-- cache_translation_check_ga_IE_ee7575d3fbd8812cb2c999d617d25cf4505b9f852e62105a4fe54fe81a8bf3f2 -->
```
        <source>Map port using PCP or NA&amp;T-PMP</source>
        <translation>Port léarscáil ag baint úsáide as PCP nó NA&amp;T-PMP</translation>
    
ERR
The translation uses "léarscáil," which is the noun for a geographical map, instead of a verb. Furthermore, the word order is incorrect for an imperative sentence in Irish.

Correct translation:
Mapáil port ag baint úsáide as PCP nó NA&amp;T-PMP
```

<!-- cache_translation_check_ga_IE_1fce6b1c5959bb7d7cbd584571af62122340bde71da59ec530342b40acc72b86 -->
```
        <source>Reset all client options to default.</source>
        <translation>Athshocraigh gach rogha cliant chuig réamhshocraithe.</translation>
    
ERR
The translation contains grammatical errors in Irish. "Gach rogha cliant" uses the nominative singular, but "cliant" should be in the genitive case ("cliaint"). Additionally, "réamhshocraithe" is an adjective; the noun "réamhshocruithe" (defaults) is more appropriate here.

Correct translation:
Athshocraigh gach rogha cliaint chun na réamhshocruithe.
```

<!-- cache_translation_check_ga_IE_1405b28131ab7b4e2c3978a255821cbeaf7fdd6e35b1e53cf2ea58af3fcfdda4 -->
```
        <source>&amp;Reset Options</source>
        <translation>&amp;Roghanna Athshocraigh</translation>
    
ERR
In Irish, the verb usually precedes the noun in a command or action label. "Roghanna Athshocraigh" literally translates to "Options Reset", whereas "Reset Options" should be "Athshocraigh Roghanna".

Correct translation:
&Athshocraigh Roghanna
```

<!-- cache_translation_check_ga_IE_6c8d00fd13eb74eb1d59e0d5a33478552c6310d8d625a24c2d73578d67b36bdf -->
```
        <source>(0 = auto, &lt;0 = leave that many cores free)</source>
        <translation>(0 = uath, &lt;0 = fág an méid sin cóir saor)</translation>
    
ERR
The translation uses the word "cóir", which means "justice", "right", or "arrangement", instead of the correct term for CPU "cores". The Irish word for "core" (in a computing context) is "croí", and its plural is "croíthe".

Correct translation:
(0 = uath, <0 = fág an méid sin croíthe saor)
```

<!-- cache_translation_check_ga_IE_b2482af195fc53ebeaa5912c8b3c6a54c26e7d88498bfa558dbdd046c0b35614 -->
```
        <source>If you disable the spending of unconfirmed change, the change from a transaction cannot be used until that transaction has at least one confirmation. This also affects how your balance is computed.</source>
        <translation>Má dhíchumasaíonn tú caiteachas sóinseáil neamhdheimhnithe, ní féidir an t-athrú ó idirbheart a úsáid go dtí go mbeidh deimhniú amháin ar a laghad ag an idirbheart sin. Bíonn tionchar aige seo freisin ar an gcaoi a ríomhtar d’iarmhéid.</translation>
    
ERR
The translation contains an inconsistency in how the word "change" (as in Bitcoin change) is translated. In the first clause, it is translated as "sóinseáil", but in the second clause, it is translated as "athrú". In the context of currency/money, "sóinseáil" is the correct term for change, whereas "athrú" means a general change or modification.

Correct translation:
Má dhíchumasaíonn tú caiteachas sóinseáil neamhdheimhnithe, ní féidir an t-sóinseáil ó idirbheart a úsáid go dtí go mbeidh deimhniú amháin ar a laghad ag an idirbheart sin. Bíonn tionchar aige seo freisin ar an gcaoi a ríomhtar d’iarmhéid.
```

<!-- cache_translation_check_ga_IE_911b34edd31e05531e1d64bc2c6f8600c79791ea0acad690c6cdf03dae99178d -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Cumasaigh &amp; rialuithe PSBT</translation>
    
ERR
There is an unnecessary space after the ampersand (&amp;), which is used to define the shortcut key. In UI translations, the ampersand should be placed immediately before the character intended to be the shortcut key without a space.

Correct translation:
Cumasaigh rialuithe &amp;PSBT
```

<!-- cache_translation_check_ga_IE_ee0e376012693e58acbc7d7fb84c1d78c2615d26647dc78a127101df833ce94b -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>&amp;Íoslaghdaigh an tráidire in ionad an tascbharra</translation>
    
ERR
The translation "Íoslaghdaigh an tráidire" means "Minimize the tray" (as if the tray itself is the object being minimized), whereas the English source means to minimize the application window *to* the tray. In Irish, "to the" should be translated using "go dtí an".

Correct translation:
&amp;Íoslaghdaigh go dtí an tráidire in ionad an tascbharra
```

<!-- cache_translation_check_ga_IE_0501745d1376d25cf775d09568d2b1b83a7f70e653322b6c30c4dd1c90484218 -->
```
        <source>Third-party URLs (e.g. a block explorer) that appear in the transactions tab as context menu items. %s in the URL is replaced by transaction hash. Multiple URLs are separated by vertical bar |.</source>
        <translation>URLanna tríú páirtí (m.sh. taiscéalaí bloc) atá le feiceáil sa chluaisín idirbheart mar mhíreanna roghchláir comhthéacs. Cuirtear hais idirbhirt in ionad%s sa URL. Déantar URLanna iolracha a dheighilt le barra ingearach |.</translation>
    
ERR
The translation contains a whitespace formatting issue. There is a missing space before the format specifier '%s' in the phrase "in ionad%s".

Correct translation:
URLanna tríú páirtí (m.sh. taiscéalaí bloc) atá le feiceáil sa chluaisín idirbheart mar mhíreanna roghchláir comhthéacs. Cuirtear hais idirbhirt in ionad %s sa URL. Déantar URLanna iolracha a dheighilt le barra ingearach |.
```

<!-- cache_translation_check_ga_IE_a5b40bd1d47bbab099ea2933c0bd02e063ca289fa7a1ab965d8c3e64efc6c6f0 -->
```
        <source>&amp;Third-party transaction URLs</source>
        <translation>URLanna idirbheart tríú páirtí</translation>
    
ERR
The translation is missing the shortcut key indicator '&' which was present in the source text.

Correct translation:
URLanna idirbheart &tríú páirtí
```

<!-- cache_translation_check_ga_IE_264448894720351aa7e91271974f2503753e7409721b0cf767af6881019dcda7 -->
```
        <source>Whether to show coin control features or not.</source>
        <translation>Gnéithe rialúchán bonn a thaispeáint nó nach.</translation>
    
ERR
The Irish translation is grammatically incomplete. The phrase "nó nach" (or not) cannot stand alone at the end of the sentence in this context; it requires a verb or a pro-verb like "ea". Additionally, "rialúchán" (regulation) is less appropriate than "rialaithe" (control/controlling) in a technical "coin control" context.

Correct translation:
Gnéithe rialaithe bonn a thaispeáint nó nach ea.
```

<!-- cache_translation_check_ga_IE_b65fb896e1dd0cb6ad835358483797b07689ba832fa94ca3945e48d4e730dd06 -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Úsáid seachfhreastalaí SOCKS5 ar leith chun sroicheadh piaraí trí sheirbhísí Tor oinniún:</translation>
    
ERR
The translation is missing the shortcut key indicator '&', which must appear exactly once as per the instructions.

Correct translation:
Úsáid seachfhreastalaí SOCKS&5 ar leith chun sroicheadh piaraí trí sheirbhísí Tor oinniún:
```

<!-- cache_translation_check_ga_IE_86afc8f988d0ad22d9fcd706474dee9cca6337d282f1d67165c226edbd086e0e -->
```
        <source>&amp;OK</source>
        <translation>&amp;Togha</translation>
    
ERR
The translation "Togha" is not an accurate translation for the button "OK". In Irish, "Togha" means "Choice", "Select", or "Excellent/Great". For a standard UI confirmation button like "OK", the most appropriate translation is either to keep it as "OK" or use "Ceart go leor".

Correct translation:
&OK
```

<!-- cache_translation_check_ga_IE_7e23765736c03891f607e3359769deb88480165b8f63f0e983ef9877b9e691c2 -->
```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Iomlán na n-idirbheart nár deimhniú fós, agus nach bhfuil fós ag comhaireamh i dtreo an iarmhéid inchaite.</translation>
    
ERR
The Irish translation contains a grammatical error. The phrase "nár deimhniú fós" is incorrect; "deimhniú" is a noun (confirmation) or verbal noun, but in this context, it needs to be a past participle or a passive verb to mean "confirmed". Additionally, the phrasing is slightly clunky.

Correct translation:
Iomlán na n-idirbheart nach bhfuil deimhnithe fós, agus nach bhfuil fós á gcur san áireamh don iarmhéid inchaite.
```

<!-- cache_translation_check_ga_IE_c673c11a563ce5b1661eaf8b9d3deca543201e37665b76eb82975ed8c29089f2 -->
```
        <source>Mined balance that has not yet matured</source>
        <translation>Iarmhéid mianadóireacht nach bhfuil fós aibithe</translation>
    
ERR
The Irish translation contains a grammatical error and uses a noun where an adjective is more appropriate. "Mianadóireacht" (mining) is a noun in the nominative case; it should either be in the genitive case ("mianadóireachta") to mean "balance of mining," or replaced with the adjective "mianaithe" to mean "mined." Additionally, the word order "nach bhfuil aibithe fós" is more natural than "nach bhfuil fós aibithe."

Correct translation:
Iarmhéid mianaithe nach bhfuil aibithe fós
```

<!-- cache_translation_check_ga_IE_72debf8df500391bcce47a126d97b05def14f8ef6a25fda65a57099d7f4f710f -->
```
        <source>Unknown error processing transaction.</source>
        <translation>Earráide anaithnid ag próiseáil idirbheart.</translation>
    
ERR
The word 'Earráide' is in the genitive case; the nominative 'Earráid' should be used here. Additionally, the noun following the verbal noun 'ag próiseáil' should ideally be in the genitive case.

Correct translation:
Earráid anaithnid ag próiseáil idirbhirt.
```

<!-- cache_translation_check_ga_IE_3f9cc2cdccf1c50fdc5c9426fdd089263f33804d3af8df2f21f2fa02829ab963 -->
```
        <source>PSBT copied to clipboard.</source>
        <translation>Cóipeáladh IBSP chuig an gearrthaisce.</translation>
    
ERR
The translation contains a grammatical error and translates a technical acronym (PSBT) which is usually left in its English form for consistency across Bitcoin software. In Irish, "gearrthaisce" (clipboard) is a feminine noun; after the article 'an' and a preposition like 'chuig', it should be lenited (ghearrthaisce) or eclipsed (ngearrthaisce) depending on the dialectal convention used, but 'an gearrthaisce' is generally incorrect.

Correct translation:
Cóipeáladh PSBT chuig an ngearrthaisce.
```

<!-- cache_translation_check_ga_IE_d9d270ab0ed685f6e06a02c8ade72991ff949b04ed5a623156e957fc456767b0 -->
```
        <source>Pays transaction fee: </source>
        <translation>Íocann táille idirbhirt:</translation>
    
ERR
The translation is missing the trailing space present in the source text. In localization, it is important to maintain consistent spacing for UI layout.

Correct translation:
Íocann táille idirbhirt:
```

<!-- cache_translation_check_ga_IE_7df965382340db4396d0f30d20816cacde059808b0fa0c29dfc60a783a7d0355 -->
```
        <source>Payment request error</source>
        <translation>Earráid iarratais íocaíocht</translation>
    
ERR
The noun "íocaíocht" (payment) should be in its genitive form "íocaíochta" because it is modifying the preceding noun "iarratais".

Correct translation:
Earráid iarratais íocaíochta
```

<!-- cache_translation_check_ga_IE_9d03428408085d09aac2091f776e3cc4cbba9afeb729003a9dc9bad1b76329f0 -->
```
        <source>URI handling</source>
        <translation>Láimhseála URI</translation>
    
ERR
The translation uses the genitive form 'Láimhseála' instead of the nominative 'Láimhseáil'. For a heading or title like "URI handling", the nominative case is appropriate.

Correct translation:
Láimhseáil URI
```

<!-- cache_translation_check_ga_IE_0389509a0e4281f8a746d6c82c244864c869ff2a02e4613c5eb2f6b0e08a8349 -->
```
        <source>Payment request file handling</source>
        <translation>Iarratas ar íocaíocht láimhseáil comhad</translation>
    
ERR
The Irish grammar and word order are incorrect. In Irish, the noun being described usually comes before the descriptor. "Láimhseáil comhad" (file handling) should precede "iarratas ar íocaíocht" (payment request), or be structured as "Láimhseáil comhad iarratais ar íocaíocht".

Correct translation:
Láimhseáil comhad iarratais ar íocaíocht
```

<!-- cache_translation_check_ga_IE_23bd76ab5927190f3cf98a5bb7df335b20bbfa3005c4ef9229d4ced36e991ce2 -->
```
        <source>Peer</source>
        <extracomment>Title of Peers Table column which contains a unique number used to identify a connection.</extracomment>
        <translation>Piaraí</translation>
    
ERR
The English source "Peer" is singular, but the Irish translation "Piaraí" is plural. In the context of a table column identifying a specific connection, the singular form should be used.

Correct translation:
Piara
```

<!-- cache_translation_check_ga_IE_dd9386ef92522a800a56ba8a0f2acb46bf0032ac6e1e30a4b5faa4160222636c -->
```
        <source>Error encoding URI into QR Code.</source>
        <translation>Earráid ag ionchódú URI chuig chód QR.</translation>
    
ERR
The translation contains a grammatical error. The preposition 'chuig' does not trigger lenition (séimhiú) on the following noun 'cód'. Furthermore, 'into' is more accurately translated as 'i' (followed by eclipsis) in this context.

Correct translation:
Earráid ag ionchódú URI i gcód QR.
```

<!-- cache_translation_check_ga_IE_6a5bc03ff19b9ba9d3fa84a1f36a0deb1a7543c26bc29995b8191b38b18ba8a6 -->
```
        <source>Save QR Code</source>
        <translation>Sabháil cód QR.</translation>
    
ERR
The translation includes a period at the end which is not present in the source text.

Correct translation:
Sabháil cód QR
```

<!-- cache_translation_check_ga_IE_c5a50c8f0da1f3de50599b9278c98cae83766b6d8d77cd0e5620cbc125df9309 -->
```
        <source>To specify a non-default location of the data directory use the '%1' option.</source>
        <translation>Chun suíomh neamh-réamhshocraithe den eolaire sonraí a sainigh úsáid an rogha '%1'.</translation>
    
ERR
The Irish translation contains a grammatical error. The particle 'a' before the verb 'sainigh' (imperative) requires the verbal noun 'shainiú' to form an infinitive phrase. Additionally, the word order can be improved for better flow.

Correct translation:
Chun suíomh neamh-réamhshocraithe don eolaire sonraí a shainiú, úsáid an rogha '%1'.
```

<!-- cache_translation_check_ga_IE_b4d4381941f7b6fc373f64a0ff5452ec125870a56977c8b11400bb318305442e -->
```
        <source>To specify a non-default location of the blocks directory use the '%1' option.</source>
        <translation>Chun suíomh neamh-réamhshocraithe den eolaire bloic a sainigh úsáid an rogha '%1'.</translation>
    
ERR
The Irish grammar is incorrect. In the structure "Chun [rud] a [verb]", the verbal noun should be used and lenited where applicable. The verbal noun of "sainigh" is "sainiú", which becomes "a shainiú". Additionally, a comma should ideally separate the two clauses for better readability.

Correct translation:
Chun suíomh neamh-réamhshocraithe den eolaire bloic a shainiú, úsáid an rogha '%1'.
```

<!-- cache_translation_check_ga_IE_3f2035ada2a0bdf8f78e0bb62ad9a198488a3398cf12c690ed57e9a9cbc6c2ac -->
```
        <source>Network addresses that your Bitcoin node is currently using to communicate with other nodes.</source>
        <translation>Seoltaí líonra go bhfuil do nód Bitcoin úsáid faoi láthair chun cumarsáid a dhéanamh le nóid eile.</translation>
    
ERR
The Irish grammar is incorrect. The phrase "go bhfuil do nód Bitcoin úsáid" is missing the necessary particles to indicate the progressive action "is using". It should use the direct relative "atá" and the progressive construction "a úsáid".

Correct translation:
Seoltaí líonra atá do nód Bitcoin a úsáid faoi láthair chun cumarsáid a dhéanamh le nóid eile.
```

<!-- cache_translation_check_ga_IE_4613b5ef7da23065722da3da31dff4321065e892b0de523433d71c4568b50dc6 -->
```
        <source>Current number of transactions</source>
        <translation>Líon reatha h-idirbheart</translation>
    
ERR
The Irish translation contains a grammatical error. The prefix 'h-' is not used before 'idirbheart' in this context. In Irish, 'h' is prefixed to words starting with a vowel only after specific particles (like 'le', 'go', or the feminine possessive 'a') or the plural article 'na'. Here, it is preceded by the adjective 'reatha', which does not trigger an 'h-' prefix.

Correct translation:
Líon reatha idirbheart
```

<!-- cache_translation_check_ga_IE_ab9cfabb5d6071a949ec233f6168193e869c6fb361b4e0af0401a525ff927e6c -->
```
        <source>Wallet: </source>
        <translation>Sparán:</translation>
    
ERR
The translation is missing the trailing space present in the source text. In user interfaces, this space is often necessary for proper spacing between the label and the value.

Correct translation:
Sparán:
```

<!-- cache_translation_check_ga_IE_eca8f21ca2fef77c72bd1e12df8ec83c50301b85691ae743b6ac6671ebd6f91f -->
```
        <source>The total number of addresses received from this peer that were processed (excludes addresses that were dropped due to rate-limiting).</source>
        <extracomment>Tooltip text for the Addresses Processed field in the peer details area, which displays the total number of addresses received from this peer that were processed (excludes addresses that were dropped due to rate-limiting).</extracomment>
        <translation>Líon iomlán na seoltaí a fuarthas ón bpiaraí seo a próiseáladh (ní áirítear seoltaí a laghdaíodh mar gheall ar theorannú rátaí).</translation>
    
ERR
The translation contains a grammatical error and a suboptimal word choice. "bpiaraí" is the plural form of "peer," but the source specifies singular "this peer" (should be "bpiara"). Additionally, "laghdaíodh" means "reduced/lessened" rather than "dropped" (discarded).

Correct translation:
Líon iomlán na seoltaí a fuarthas ón bpiara seo a próiseáladh (ní áirítear seoltaí a caitheadh amach mar gheall ar theorannú rátaí).
```

<!-- cache_translation_check_ga_IE_d2f420ebb5db17535a3771db5784b2dcd43ee9639b10c1907f9243566077bd9a -->
```
        <source>High bandwidth BIP152 compact block relay: %1</source>
        <translation>Bandaleithead ard BIP152 sealaíochta bloc dhlúth: %1</translation>
    
ERR
The Irish translation contains incorrect word order and grammatical issues. "Bandaleithead ard" (High bandwidth) is fine, but the phrase "sealaíochta bloc dhlúth" is grammatically incorrect. "Sealaíocht" (relay) should be at the start of the noun phrase, and "bloc dhlúth" has an incorrect gender agreement ("bloc" is masculine, so "dlúth" should not be lenited).

Correct translation:
Sealaíocht bloc dlúth BIP152 ard-bandaleithid: %1
```

<!-- cache_translation_check_ga_IE_f45801d3bff6c48e59222755e866a4bdf4ba6c27eb8422d70848371ecafa6c12 -->
```
        <source>Elapsed time since a novel block passing initial validity checks was received from this peer.</source>
        <translation>Tá achar ama caite ó fuarthas bloc úrscéil a rinne na seiceálacha bailíochta tosaigh ón gcomhghleacaí seo.</translation>
    
ERR
The word "novel" was mistranslated. In this technical context, "novel" means "new" or "original," but the translation used "úrscéil," which refers to a "novel" in the sense of a literary book (fiction). Also, the phrasing "Tá achar ama caite ó..." turns it into a full sentence ("Time has elapsed since...") rather than a noun phrase describing the field.

Correct translation:
An t-am atá caite ó fuarthas bloc nua a d'éirigh leis na seiceálacha bailíochta tosaigh ón gcomhghleacaí seo.
```

<!-- cache_translation_check_ga_IE_d0d49e0bbef525944b013207d46fdecba9b7c05b02c7c5e88df44f5e897916e1 -->
```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>Chuaigh an t-am caite ó fuarthas idirbheart úrnua a glacadh isteach inár mempool ón bpiaraí seo.</translation>
    
ERR
The translation contains grammatical errors and a number mismatch. "Chuaigh an t-am caite" is an awkward, literal translation of "Elapsed time"; the standard phrase is "An t-am a chuaigh thart". Additionally, "piaraí" is the plural form ("peers"), whereas the source specifies "this peer" (singular), which should be "piara".

Correct translation:
An t-am a chuaigh thart ó fuarthas idirbheart nua, a glacadh isteach inár mempool, ón bpiara seo.
```

<!-- cache_translation_check_ga_IE_f720d31fa450dd0c8181bf50831e0b9ad1bdf6484fe86a5d566f23af34e8154f -->
```
        <source>Outbound Manual: added using RPC %1 or %2/%3 configuration options</source>
        <extracomment>Explanatory text for an outbound peer connection that was established manually through one of several methods. The numbered arguments are stand-ins for the methods available to establish manual connections.</extracomment>
        <translation>Lámhleabhar Amach: curtha leis ag úsáid roghanna cumraíochta RPC %1 nó %2/ %3</translation>
    
ERR
The translation contains a whitespace error in the format specifiers: there is a space between "%2/" and "%3" which is not present in the source ("%2/%3"). Additionally, "Lámhleabhar" is a noun meaning "Handbook"; for "Manual" in the sense of a manual process/connection, "Lámhleabhrach" (adjective) or "De láimh" (by hand) is more appropriate.

Correct translation:
Amach (Lámhleabhrach): curtha leis ag úsáid roghanna cumraíochta RPC %1 nó %2/%3
```

<!-- cache_translation_check_ga_IE_8e3580f9b44f60cd0a35aa583559d173f4d399321201a1e5e6eafe3ad17eb574 -->
```
        <source>detecting: peer could be v1 or v2</source>
        <extracomment>Explanatory text for "detecting" transport type.</extracomment>
        <translation>bhrath: d’fhéadfadh v1 nó v2 a bheith i gcomhghleacaí</translation>
    
ERR
The translation contains grammatical errors and a mistranslation of the relationship between the "peer" and the "versions". The current translation "d’fhéadfadh v1 nó v2 a bheith i gcomhghleacaí" suggests that "v1 or v2 could be in a peer" rather than "the peer could be v1 or v2". Additionally, "bhrath" (with lenition) is the past tense or used after particles, whereas a status like "detecting" should use the verbal noun "brath" or "á bhrath".

Correct translation:
brath: d’fhéadfadh an comhghleacaí a bheith v1 nó v2
```

<!-- cache_translation_check_ga_IE_8d7d207189ff5fc708b53bbf5142c75de4b86ee2ee0b04e6d0d7c0f908aa8066 -->
```
        <source>we selected the peer for high bandwidth relay</source>
        <translation>roghnaigh muid an piaraí le haghaidh sealaíochta bandaleithead ard</translation>
    
ERR
The translation contains a grammatical error: "an piaraí" combines a singular article ("an") with a plural noun ("piaraí"). Since the source text says "the peer" (singular), it should be "an piara". Additionally, the phrasing for "high bandwidth relay" can be improved for better flow.

Correct translation:
roghnaigh muid an piara le haghaidh sealaíochta ard-bandaleithid
```

<!-- cache_translation_check_ga_IE_bd33ae12288a14992131a2d09e898264384dce1d17a89ec4256166bd6f525811 -->
```
        <source>the peer selected us for high bandwidth relay</source>
        <translation>roghnaigh an piaraí sinn le haghaidh sealaíochta bandaleithead ard</translation>
    
ERR
The Irish translation contains a grammatical error in number agreement. "An" is the singular article, but "piaraí" is the plural form of the word "piara" (peer). Since the source text uses the singular "the peer", the translation should use the singular "an piara".

Correct translation:
roghnaigh an piara sinn le haghaidh sealaíochta bandaleithead ard
```

<!-- cache_translation_check_ga_IE_dbe96b490dd2f9dd487186a45dc434148e08b8dd44f234bcb814b1db9a158d97 -->
```
        <source>no high bandwidth relay selected</source>
        <translation>níor roghnaíodh aon sealaíochta bandaleithead ard</translation>
    
ERR
The translation contains grammatical errors in Irish. The word 'sealaíochta' is in the genitive case (or plural), but after 'aon' in this context, the nominative singular 'sealaíocht' should be used. Furthermore, 'high bandwidth' as an attribute to 'relay' requires the genitive case for 'bandwidth' (bandaleithid) and agreement for 'high' (aird), or the use of a compound.

Correct translation:
níor roghnaíodh aon sealaíocht ard-bandaleithid
```

<!-- cache_translation_check_ga_IE_d217764583bfd4faf1f08ab37e3faffb07f6f047dec695ddbbf67d3997bdd747 -->
```
        <source>&amp;Disconnect</source>
        <translation>&amp;Scaoil</translation>
    
ERR
The translation "Scaoil" translates more accurately to "Release" or "Let go". For "Disconnect" in a technical or networking context, the standard Irish term is "Dícheangail".

Correct translation:
&Dícheangail
```

<!-- cache_translation_check_ga_IE_223b3214290943e3b57d27a0d26c5f92e680afbbfe05be390e6510ce194a724f -->
```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>Fáilte go consól RPC %1.
Úsáid saigheada suas agus síos chun an stair a nascleanúint, agus %2 chun an scáileán a ghlanadh.
Úsáid %3 agus %4 chun an clómhéid a mhéadú nó a laghdú.
Clóscríobh %5 le haghaidh forbhreathnú ar na horduithe atá ar fáil.
Chun tuilleadh eolais a fháil faoin gconsól seo a úsáid, clóscríobh %6.

%7 RABHADH: Bhí scamadóirí gníomhach, ag rá le húsáideoirí orduithe a chlóscríobh anseo, ag goid a n-inneachar sparán. Ná húsáid an consól seo gan iarmhairtí ordaithe a thuiscint go hiomlán.%8</translation>
    
ERR
There is an intentional formatting requirement mentioned in the context (extracomment) stating that placeholders %7 and %8 should not be space-separated from the text. The translation incorrectly adds a space after %7 ("%7 RABHADH"). Additionally, the adjective "gníomhach" should be in its plural form "gníomhacha" to agree with "scamadóirí".

Correct translation:
Fáilte go consól RPC %1.
Úsáid saigheada suas agus síos chun an stair a nascleanúint, agus %2 chun an scáileán a ghlanadh.
Úsáid %3 agus %4 chun an clómhéid a mhéadú nó a laghdú.
Clóscríobh %5 le haghaidh forbhreathnú ar na horduithe atá ar fáil.
Chun tuilleadh eolais a fháil faoin gconsól seo a úsáid, clóscríobh %6.

%7RABHADH: Bhí scamadóirí gníomhacha, ag rá le húsáideoirí orduithe a chlóscríobh anseo, ag goid inneachar a sparán. Ná húsáid an consól seo gan iarmhairtí ordaithe a thuiscint go hiomlán.%8
```

<!-- cache_translation_check_ga_IE_611437e8063548778491da639d3ffd08ab8c8f3441af79f4e63dae5d8e482b70 -->
```
        <source>Ban for</source>
        <translation>Cosc do</translation>
    
ERR
The Irish translation "Cosc do" is grammatically incorrect for the context of duration (e.g., "Ban for 1 day"). In Irish, the preposition "do" generally means "to" or "for" (intended for). When referring to a period of time, "ar feadh" or "go ceann" is used.

Correct translation:
Cosc ar feadh
```

<!-- cache_translation_check_ga_IE_93f442c91d07a7d1f0268f48496eb1d3e1230ed1f32f9bb26da6b7692cc61aa0 -->
```
        <source>&amp;Amount:</source>
        <translation>&amp;Suim</translation>
    
ERR
The translation is missing the trailing colon (":") that is present in the source text.

Correct translation:
&Suim:
```

<!-- cache_translation_check_ga_IE_fdfca05b071eba8ac1065626b6e8ac5bd324ac59ef9309c54ce4066430aad18e -->
```
        <source>&amp;Label:</source>
        <translation>&amp;Lipéad</translation>
    
ERR
The translation is missing the colon (:) character at the end of the string, which is present in the source.

Correct translation:
&Lipéad:
```

<!-- cache_translation_check_ga_IE_e88ea85434268889bf1ac776d7a1d2000b120272f7dff991e51b7cce21088db2 -->
```
        <source>&amp;Message:</source>
        <translation>&amp;Teachtaireacht</translation>
    
ERR
The translation is missing the colon at the end of the string, which is present in the source text.

Correct translation:
&Teachtaireacht:
```

<!-- cache_translation_check_ga_IE_df55526d49fe32b124c69a8ea135188c3450ede3ccabbd995e7559eecc2a130e -->
```
        <source>An optional message to attach to the payment request, which will be displayed when the request is opened. Note: The message will not be sent with the payment over the Bitcoin network.</source>
        <translation>Teachtaireacht roghnach le ceangal leis an iarratas íocaíocht, a thaispeánfar nuair a osclaítear an iarraidh. Nóta: Ní sheolfar an teachtaireacht leis an íocaíocht thar líonra Bitcoin.</translation>
    
ERR
The translation contains grammatical errors in Irish. 
1. "an iarratas" should be "an t-iarratas" (masculine nouns starting with a vowel take a 't-' prefix after the definite article 'an'). 
2. "íocaíocht" should be in the genitive case "íocaíochta" when following "iarratas".
3. Consistency: "iarratas" is used for "request" in the first sentence, but "iarraidh" is used in the second part of that sentence. It is better to remain consistent.

Correct translation:
Teachtaireacht roghnach le ceangal leis an t-iarratas íocaíochta, a thaispeánfar nuair a osclaítear an t-iarratas. Nóta: Ní sheolfar an teachtaireacht leis an íocaíocht thar líonra Bitcoin.
```

<!-- cache_translation_check_ga_IE_af0f693a3a9ad4745cd3147f74341c50167020cda38e7f548377df636022bf28 -->
```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>Suim roghnach le hiarraidh. Fág é seo folamh nó nialas chun ná iarr méid ar leith.</translation>
    
ERR
The Irish translation is grammatically incorrect in the second sentence. The phrase "chun ná iarr" is an incorrect way to express negative purpose ("to not request"). In Irish, "chun" (to/in order to) should be followed by a verbal noun construction, and "gan" is used for negation in this context.

Correct translation:
Suim roghnach le hiarraidh. Fág é seo folamh nó nialas chun gan méid ar leith a iarraidh.
```

<!-- cache_translation_check_ga_IE_17e21b6c8ef153ec511e9e2437df42e53517ff88715ffeb536cce298468a12c2 -->
```
        <source>An optional label to associate with the new receiving address (used by you to identify an invoice).  It is also attached to the payment request.</source>
        <translation>Lipéad roghnach chun é a comhcheangail leis an seoladh glactha nua (a úsáideann tú chun sonrasc a aithint). Tá sé ceangailte leis an iarraidh ar íocaíocht freisin.</translation>
    
ERR
The Irish translation contains a few grammatical errors in the first sentence. 
1. The verbal noun of "comhcheangail" (to associate/combine) is "comhcheangal". 
2. When using the structure "chun [object] a [verbal noun]", the verbal noun should be lenited if possible (e.g., "a chomhcheangal").

Correct translation:
Lipéad roghnach chun é a chomhcheangal leis an seoladh glactha nua (a úsáideann tú chun sonrasc a aithint). Tá sé ceangailte leis an iarraidh ar íocaíocht freisin.
```

<!-- cache_translation_check_ga_IE_b163210628b5aa1a722c712e79e8b1a05240f34b1eed21f9a618d8933fd9d923 -->
```
        <source>Copy &amp;message</source>
        <translation>Cóipeáil &amp; teachtaireacht</translation>
    
ERR
The translation contains an extra space before the ampersand (&), which breaks the shortcut key functionality. In 'ga_IE' (Irish), the ampersand should be placed directly before the character intended as the shortcut.

Correct translation:
Cóipeáil &teachtaireacht
```

<!-- cache_translation_check_ga_IE_96b9c8575155dfa87acb5e70e5b5d39b14c6301dd11504d6c4798bf5f33bb425 -->
```
        <source>Copy &amp;amount</source>
        <translation>Cóipeáil &amp; méid</translation>
    
ERR
There is an unnecessary space between the shortcut key indicator '&' and the word 'méid'. In the source, the indicator is directly attached to the word it modifies.

Correct translation:
Cóipeáil &méid
```

<!-- cache_translation_check_ga_IE_9765dc041f34a3683c1de71a6e54bc7d34bcdf3c57f41c48a953877b24e7eeee -->
```
        <source>Base58 (P2SH-SegWit)</source>
        <translation>Base58 (P2SH- SegWit)</translation>
    
ERR
There is a stray space after the hyphen in the translation. In technical identifiers like "P2SH-SegWit", no extra spacing should be added.

Correct translation:
Base58 (P2SH-SegWit)
```

<!-- cache_translation_check_ga_IE_5e817a4b614fac56545955b3531903b336114004fb63da00daf2895900ba43bf -->
```
        <source>Insufficient funds!</source>
        <translation>Neamhleor airgead!</translation>
    
ERR
The word order in the Irish translation is incorrect. In Irish, adjectives typically follow the noun. Additionally, "cistí" is the more standard term for "funds" in a financial context.

Correct translation:
Cistí neamhleor!
```

<!-- cache_translation_check_ga_IE_f4e1853f4129ec2289f66f7a17cfc70f841ad23089b3e51dc973e5ca1b5f326b -->
```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Má úsáidtear an táilletacachumas is féidir idirbheart a sheoladh a thógfaidh roinnt uaireanta nó laethanta (nó riamh) dearbhú. Smaoinigh ar do tháille a roghnú de láimh nó fan go mbeidh an slabhra iomlán bailíochtaithe agat.</translation>
    
ERR
The translation contains a non-standard compound word and grammatical issues. "táilletacachumas" is not a recognized word for "fallback fee"; "táille chúltaca" is the correct term. Additionally, the phrase "a thógfaidh ... dearbhú" is grammatically incomplete in Irish, as it lacks the necessary prepositional structure (e.g., "chun é a dhearbhú" or "le deimhniú").

Correct translation:
Má úsáidtear an táille chúltaca, d'fhéadfadh sé go seolfaí idirbheart a thógfaidh roinnt uaireanta an chloig nó laethanta (nó nach ndeimhneofar go deo é) chun é a dhearbhú. Smaoinigh ar do tháille a roghnú de láimh nó fan go mbeidh an slabhra iomlán bailíochtaithe agat.
```

<!-- cache_translation_check_ga_IE_01a8438c7c2e56485a585e7a622390a53b3bbd18ec8141f7d1b2fee03d3c5b63 -->
```
        <source>Add &amp;Recipient</source>
        <translation>Cuir &amp;Faighteoir</translation>
    
ERR
The Irish translation is grammatically incomplete. In Irish, "Add" (in the sense of appending something to a list or transaction) is translated as "Cuir ... leis" (literally "Put ... with it"). Without the word "leis", "Cuir Faighteoir" simply means "Put Recipient" or "Send Recipient".

Correct translation:
Cuir &amp;Faighteoir Leis
```

<!-- cache_translation_check_ga_IE_2932908e87a42c80c8fbe45f5f86dcf1bde3495f69605a437cca98d34447bc50 -->
```
        <source>When there is less transaction volume than space in the blocks, miners as well as relaying nodes may enforce a minimum fee. Paying only this minimum fee is just fine, but be aware that this can result in a never confirming transaction once there is more demand for bitcoin transactions than the network can process.</source>
        <translation>Nuair a bhíonn méid idirbhirt níos lú ná spás sna bloic, féadfaidh mianadóirí chomh maith le nóid athsheachadadh táille íosta a fhorfheidhmiú. Tá sé sách maith an táille íosta seo a íoc, ach bíodh a fhios agat go bhféadfadh idirbheart nach ndeimhnítear riamh a bheith mar thoradh air seo a nuair a bhíonn níos mó éilimh ar idirbhearta bitcoin ná mar is féidir leis an líonra a phróiseáil.</translation>
    
ERR
The translation contains a grammatical error and a stray character. Specifically, "a nuair" contains an unnecessary "a" before the conjunction "nuair". Additionally, "nóid athsheachadadh" should use the genitive form "nóid athsheachadta".

Correct translation:
Nuair a bhíonn méid na n-idirbheart níos lú ná an spás sna bloic, féadfaidh mianadóirí chomh maith le nóid athsheachadta táille íosta a fhorfheidhmiú. Tá sé ceart go leor an táille íosta seo a íoc, ach bíodh a fhios agat go bhféadfadh idirbheart nach ndeimhnítear riamh a bheith mar thoradh air seo nuair a bhíonn níos mó éilimh ar idirbhearta bitcoin ná mar is féidir leis an líonra a phróiseáil.
```

<!-- cache_translation_check_ga_IE_c4d5c634e6dc87fc15a49dc3a084690fe4c06eb26247f2d4ec1040d69a666d3f -->
```
        <source>With Replace-By-Fee (BIP-125) you can increase a transaction's fee after it is sent. Without this, a higher fee may be recommended to compensate for increased transaction delay risk.</source>
        <translation>Le Athchuir-Le-Táille (BIP-125) is féidir leat táille idirbhirt a mhéadú tar éis é a sheoladh. Gan é seo, féadfar táille níos airde a mholadh chun riosca méadaithe moille idirbheart a cúitigh.</translation>
    
ERR
The Irish translation contains a grammatical error at the end of the second sentence. The verb 'cúitigh' (compensate) is in the imperative/root form, but it should be in the verbal noun form 'chúiteamh' to follow the preposition 'a'.

Correct translation:
Le Athchuir-Le-Táille (BIP-125) is féidir leat táille idirbhirt a mhéadú tar éis é a sheoladh. Gan é seo, féadfar táille níos airde a mholadh chun riosca méadaithe moille idirbhirt a chúiteamh.
```

<!-- cache_translation_check_ga_IE_54558cd7bfe47eae241c1e5de2feb1c43895c5fe8945f4952907c0e0dac0741f -->
```
        <source>Balance:</source>
        <translation>Iarmhéid</translation>
    
ERR
The translation is missing the colon (:) at the end of the word, which is present in the source text.

Correct translation:
Iarmhéid:
```

<!-- cache_translation_check_ga_IE_fc873d44d2912b1da0def4f8c6e6bcd003e202bdd23c709c81b92a9028bf94b2 -->
```
        <source>Copy fee</source>
        <translation>Cóipeáíl táille</translation>
    
ERR
The translation contains a typo in the word "Cóipeáil". The provided text "Cóipeáíl" has an extra "í" before the "l".

Correct translation:
Cóipeáil an táille
```

<!-- cache_translation_check_ga_IE_6c562af98fecd806205fe66267494b3f577edf6f87c32eb3d86b63f65c2c6c8f -->
```
        <source>Copy after fee</source>
        <translation>Cóipeáíl iar-tháille</translation>
    
ERR
There is a typo in the word "Cóipeáíl". The letter 'i' should not have an accent (fada).

Correct translation:
Cóipeáil iar-tháille
```

<!-- cache_translation_check_ga_IE_05febe321304719e316f8459f29106ce1d11c28786cffea8de7a2b4e59ae85e2 -->
```
        <source>Copy bytes</source>
        <translation>Cóipeáíl bearta</translation>
    
ERR
There is a spelling error in the word "Cóipeáíl". The correct spelling is "Cóipeáil" (only the 'a' should have an accent).

Correct translation:
Cóipeáil bearta
```

<!-- cache_translation_check_ga_IE_f76515df9b1327b7dff3c27143b961a7b5039149a0885aa08c6c3154559e7da7 -->
```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
ERR
The translation contains a misspelling. "Cóipeáíl" has an incorrect accent on the 'i'. The correct Irish word for "Copy" is "Cóipeáil".

Correct translation:
Cóipeáil sóinseáil
```

<!-- cache_translation_check_ga_IE_98a292a82ce7aede798e69a79a6fc7f3ce40b84320c0eb86323694aeb611cf87 -->
```
        <source>Cr&amp;eate Unsigned</source>
        <translation>Cruthaigh Gan Sín</translation>
    
ERR
The shortcut key indicator '&amp;' is missing in the translation. Additionally, "Sín" is not the correct term for "unsigned" in this context; "Síniú" (signing/signature) is the appropriate noun/verbal noun to follow "Gan" (without).

Correct translation:
Cr&amp;uthaigh Gan Síniú
```

<!-- cache_translation_check_ga_IE_c47725dfbf4dbb2b4fd6b4b2c8edcc2a25d6ed32bfaac8e9c005cf46eca7095f -->
```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>Níl comhartha chuig Athchuir-Le-Táille, BIP-125</translation>
    
ERR
The translation is grammatically awkward and uses a suboptimal word for "Replace". "Athchuir" typically means "resubmit" or "refer," whereas "Athsholáthar" is the standard term for "Replace." Additionally, "Níl comhartha chuig" translates to "There is no signal to," which does not correctly capture the meaning of the active participle "Not signalling."

Correct translation:
Ní ag comharthú Athsholáthar-trí-Tháille (RBF), BIP-125.
```

<!-- cache_translation_check_ga_IE_c607696ab148b2fd9b44952b3a46e8b3a60ef70e4772ed6fe0d9742f8454cd3d -->
```
        <source>Confirm send coins</source>
        <translation>Deimhnigh seol boinn</translation>
    
ERR
The Irish translation is a word-for-word translation that is grammatically incorrect. In Irish, "Deimhnigh" (Confirm) should be followed by a verbal noun rather than another imperative verb ("seol"). "Seoladh" is the verbal noun for "sending".

Correct translation:
Deimhnigh seoladh na mbonn
```

<!-- cache_translation_check_ga_IE_fdfca05b071eba8ac1065626b6e8ac5bd324ac59ef9309c54ce4066430aad18e -->
```
        <source>&amp;Label:</source>
        <translation>&amp;Lipéad</translation>
    
ERR
The translation is missing the colon (:) character at the end of the string, which is present in the source.

Correct translation:
&Lipéad:
```

<!-- cache_translation_check_ga_IE_305b9fe6c33bf512300af46565c208d798d8cc8f3dd4d53d9c6d9c6e690d38fc -->
```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Seoladh Bitcoin chun an íocaíocht a sheoladh chuig</translation>
    
ERR
The preposition 'chuig' at the end of the sentence is grammatically incomplete in Irish. It should be the prepositional pronoun 'chuige' to refer back to the masculine noun 'seoladh' (address).

Correct translation:
Seoladh Bitcoin chun an íocaíocht a sheoladh chuige
```

<!-- cache_translation_check_ga_IE_e58a18247789372b2a2ef84fdeb4ef04f3ab98086ec577e1c437002f5d5f941e -->
```
        <source>Paste address from clipboard</source>
        <translation>Greamaigh seoladh ón gearrthaisce</translation>
    
ERR
The Irish translation contains a grammatical error. In Irish, nouns following the prepositional contraction 'ón' (from the) undergo lenition (séimhiú) if they are feminine. Since 'gearrthaisce' is a feminine noun, the 'g' should be lenited to 'gh'.

Correct translation:
Greamaigh seoladh ón ghearrthaisce
```

<!-- cache_translation_check_ga_IE_dc86c79a088d7761b7cda02db85a34f9a5caffcdbc728a706dbd0a41226f0010 -->
```
        <source>Create Unsigned</source>
        <translation>Cruthaigh Gan Sín</translation>
    
ERR
The translation "Cruthaigh Gan Sín" is grammatically incorrect. "Sín" is the imperative form of the verb "to sign" or means "stretch". To express "unsigned" in this context, the noun "síniú" (signing/signature) should be used with the preposition "gan" (without), or the adjective "neamhsínithe" should be used.

Correct translation:
Cruthaigh Gan Síniú
```

<!-- cache_translation_check_ga_IE_3ff3ccdbb712bd09bc88f9aef3dcb708bb78b409ac45b8be88e0ce7e333cd152 -->
```
        <source>The Bitcoin address to sign the message with</source>
        <translation>An seoladh Bitcoin chun an teachtaireacht a shíniú le</translation>
    
ERR
In Irish grammar, the preposition "le" cannot stand alone at the end of a clause in this manner. It must be converted to the prepositional pronoun "leis" (with it) to complete the phrase correctly.

Correct translation:
An seoladh Bitcoin chun an teachtaireacht a shíniú leis
```

<!-- cache_translation_check_ga_IE_e58a18247789372b2a2ef84fdeb4ef04f3ab98086ec577e1c437002f5d5f941e -->
```
        <source>Paste address from clipboard</source>
        <translation>Greamaigh seoladh ón gearrthaisce</translation>
    
ERR
The Irish translation contains a grammatical error. In Irish, nouns following the prepositional contraction 'ón' (from the) undergo lenition (séimhiú) if they are feminine. Since 'gearrthaisce' is a feminine noun, the 'g' should be lenited to 'gh'.

Correct translation:
Greamaigh seoladh ón ghearrthaisce
```

<!-- cache_translation_check_ga_IE_a458b1d188089145a3576f2fcf1b227e20347f89e1c9a84b5bd2d333b10908e7 -->
```
        <source>Reset all sign message fields</source>
        <translation>Athshocraigh gach réimse sínigh teachtaireacht</translation>
    
ERR
The translation uses the imperative verb "sínigh" (sign) instead of the verbal noun "síniú" (signing) to describe the fields. Furthermore, it lacks the proper genitive construction for a natural-sounding Irish sentence.

Correct translation:
Athshocraigh gach réimse sínithe teachtaireachta
```

<!-- cache_translation_check_ga_IE_1fa91f75f0b92f8875a714b28ade145986a45e1b1e69383a11804d2c5f496b1b -->
```
        <source>Verify the message to ensure it was signed with the specified Bitcoin address</source>
        <translation>Fíoraigh an teachtaireacht lena chinntiú go raibh sí sínithe leis an seoladh Bitcoin sainithe </translation>
    
ERR
There is a trailing space at the end of the translation which is a whitespace format issue.

Correct translation:
Fíoraigh an teachtaireacht lena chinntiú go raibh sí sínithe leis an seoladh Bitcoin sainithe
```

<!-- cache_translation_check_ga_IE_96a30d13183a2383d88c17ea86104fb1d290d351620337bcf4f37c0eec2acd95 -->
```
        <source>Reset all verify message fields</source>
        <translation>Athshocraigh gach réimse fíorú teachtaireacht</translation>
    
ERR
The Irish translation contains a grammatical error. The word 'teachtaireacht' should be in the genitive case ('teachtaireachta') because it follows the verbal noun 'fíorú'. Additionally, while 'gach' is followed by a singular noun, the phrasing 'fíorú teachtaireacht' is technically 'verification message' rather than 'message verification'.

Correct translation:
Athshocraigh gach réimse d’fhíorú teachtaireachtaí
```

<!-- cache_translation_check_ga_IE_a042a2ef3682e5587aa012db2ed99815dad41c7b246a04639db40a6eedb39444 -->
```
        <source>No error</source>
        <translation>Níl earráid</translation>
    
ERR
The Irish translation "Níl earráid" is grammatically incomplete or awkward in this context. It literally means "There is not error" but lacks the necessary indefinite particle or structure to be natural. In technical contexts, "No error" is typically translated as "Gan earráid" (Without error) or "Níl aon earráid" (There is no error).

Correct translation:
Níl aon earráid
```

<!-- cache_translation_check_ga_IE_b428df6e4fdf0c8ec65bafa3b36294209344e406344848fdf79f5d82e400a5b7 -->
```
        <source>Generated coins must mature %1 blocks before they can be spent. When you generated this block, it was broadcast to the network to be added to the block chain. If it fails to get into the chain, its state will change to "not accepted" and it won't be spendable. This may occasionally happen if another node generates a block within a few seconds of yours.</source>
        <translation>Caithfidh Boinn ghinte aibíocht %1 bloic sular féidir iad a chaitheamh. Nuair a ghin tú an bloc seo, craoladh é chuig an líonra le cur leis an mblocshlabhra. Má theipeann sé fáíl isteach sa slabhra, athróidh a staid go "ní ghlactar" agus ní bheidh sé inchaite. D’fhéadfadh sé seo tarlú ó am go chéile má ghineann nód eile bloc laistigh de chúpla soicind ó do cheann féin.</translation>
    
ERR
The translation contains a spelling error. The word "fáíl" should be "fáil" (to get/attain). Additionally, the first sentence is missing a verbal noun to make it grammatically complete.

Correct translation:
Caithfidh boinn ghinte %1 bloc aibíochta a shroicheadh sular féidir iad a chaitheamh. Nuair a ghin tú an bloc seo, craoladh é chuig an líonra le cur leis an mblocshlabhra. Má theipeann air fáil isteach sa slabhra, athróidh a staid go "ní ghlactar" agus ní bheidh sé inchaite. D’fhéadfadh sé seo tarlú ó am go chéile má ghineann nód eile bloc laistigh de chúpla soicind ó do cheann féin.
```

<!-- cache_translation_check_ga_IE_f3e4f9047e3e805cdb3c25f5230a340a3ebf56490fb110d50b217dfc35ac813f -->
```
        <source>Enter address, transaction id, or label to search</source>
        <translation>Iontráil seoladh, aitheantas idirbhirt, nó lipéad chun cuardach</translation>
    
ERR
The Irish translation is grammatically incomplete. The phrase "chun cuardach" is missing the genitive case ("chun cuardaigh") or a verbal noun construction ("chun cuardach a dhéanamh"). A more natural phrasing for "to search" in this context would use "le cuardach".

Correct translation:
Iontráil seoladh, aitheantas idirbhirt, nó lipéad le cuardach
```

<!-- cache_translation_check_ga_IE_96b9c8575155dfa87acb5e70e5b5d39b14c6301dd11504d6c4798bf5f33bb425 -->
```
        <source>Copy &amp;amount</source>
        <translation>Cóipeáil &amp; méid</translation>
    
ERR
There is an unnecessary space between the shortcut key indicator '&' and the word 'méid'. In the source, the indicator is directly attached to the word it modifies.

Correct translation:
Cóipeáil &méid
```

<!-- cache_translation_check_ga_IE_84cfc3dd0aaeb04dd0fb349af875e4aee635a49dce518961d9d13195f109b713 -->
```
        <source>Copy full transaction &amp;details</source>
        <translation>Cóipeáil idirbheart agus sonraí iomlána</translation>
    
ERR
The shortcut key indicator '&amp;' is missing from the translation. The instructions require it to exist exactly once. Additionally, the translation "Cóipeáil idirbheart agus sonraí iomlána" (Copy transaction and full details) slightly alters the meaning of "Copy full transaction details".

Correct translation:
Cóipeáil &sonraí iomlána an idirbhirt
```

<!-- cache_translation_check_ga_IE_dc368a9c4c2d8841b10ca53d8235ae5fda59047597fe2a690309f2ab628ff4e6 -->
```
        <source>Increase transaction &amp;fee</source>
        <translation>Méadaigh idirbheart &amp; táille</translation>
    
ERR
The translation contains a grammatical error and a formatting issue with the shortcut key. In Irish, "transaction fee" should be "táille idirbhirt" (using the genitive case). Furthermore, the shortcut key "&" is followed by a space, which is incorrect for a UI accelerator, and it appears to be treated as a conjunction rather than a marker for the following letter.

Correct translation:
Méadaigh &amp;táille idirbhirt
```

<!-- cache_translation_check_ga_IE_6b0f9328d21840b4a26c19eeaf5cbd942393b5bcb07b8c862501e132063be589 -->
```
        <source>A&amp;bandon transaction</source>
        <translation>Idirbheart&amp;tréigean</translation>
    
ERR
The translation has a whitespace issue where the shortcut key indicator `&` is placed between two words without a space, making it look like one word. Additionally, the word order in the translation is slightly unnatural for a menu item.

Correct translation:
Tréig an t-&idirbheart
```

<!-- cache_translation_check_ga_IE_a76f02c2625faa3c26bf62a305ec068da9a05b182f189ebbf2a0015e2c7e887e -->
```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
ERR
The translation includes the word 'athróige' (variable), which is not in the source text and is technically inaccurate for the CSV (Comma-Separated Values) format, where 'values' (luachanna) is the standard term. A direct translation of the source is more appropriate.

Correct translation:
Comhad camógdheighilte
```

<!-- cache_translation_check_ga_IE_6766c1963e310461bbcab2d27ced59db4ef5aea28586436202fe90398b2ae183 -->
```
        <source>Can't draft transaction.</source>
        <translation>Ní féidir dréachtú idirbheart.</translation>
    
ERR
The Irish translation is grammatically incomplete. "Dréachtú" is a verbal noun, and in this context, it requires a preposition or a different structure to function correctly as "draft a transaction". "Dréachtú idirbhirt" would mean "the drafting of a transaction", but for the action "to draft transaction", it needs to be clearer.

Correct translation:
Ní féidir idirbheart a dhréachtú.
```

<!-- cache_translation_check_ga_IE_3be7182e3268aae212ce152f9791da5f1e49fffdac1936b1e4b57b05ba9d5f07 -->
```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>Cóipeáil PSBT bump táille chuig an ngearrthaisce</translation>
    
ERR
The Irish translation uses the imperative mood ("Cóipeáil" meaning "Copy!"), whereas the English source is a status notification in the past tense/passive voice ("Copied" meaning "has been copied").

Correct translation:
Cóipeáladh PSBT bump táille chuig an ngearrthaisce
```

<!-- cache_translation_check_ga_IE_15a720da22621b5617dc5c3d6c57bd42e8b54f31bec75b79cf14e739a8146e68 -->
```
        <source>Can't sign transaction.</source>
        <translation>Ní féidir síniú idirbheart.</translation>
    
ERR
The Irish grammar is incorrect. In Irish, when "ní féidir" (cannot) is used with a verbal noun and an object, the construction follows the pattern "ní féidir" + [object] + "a" + [verbal noun].

Correct translation:
Ní féidir idirbheart a shíniú.
```

<!-- cache_translation_check_ga_IE_32d21323607298fdfc330088b5a26a0cfe8c268724aa7b00724c305a75c16e75 -->
```
        <source>Could not commit transaction</source>
        <translation>Níorbh fhéidir feidhmiú idirbheart</translation>
    
ERR
The Irish translation contains a grammatical error and a poor choice of vocabulary for the technical term "commit". In Irish, when a noun follows a verbal noun (feidhmiú), it should be in the genitive case (idirbhirt). Furthermore, "feidhmiú" means "executing" or "functioning"; for "committing" a transaction in a technical or financial context, "cur i gcrích" (completing/carrying out) is more appropriate.

Correct translation:
Níorbh fhéidir an t-idirbheart a chur i gcrích
```

<!-- cache_translation_check_ga_IE_c33ad8874e90aa7b0ea59b40febb4ae0814337addc2216e5f1c1eeb46cb7f059 -->
```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>Theip ar %s an staid snapshot -assumeutxo a bhailíochtú. Léiríonn sé seo fadhb crua-earraí, nó fabht sna bogearraí, nó droch-mhodhnú bogearraí a cheadaigh pictiúr neamhbhailí a luchtú. Mar thoradh air seo, stopfar an nód agus stopfaidh sé de úsáid a bhaint as staid ar bith a tógadh ar an seat, ag athshocrú airde an tslabhra ó%dgo%d. Ar an gcéad atosú eile, athchromfar ar an nód ag sioncronú ó %d gan úsáid a bhaint as sonraí seat. Tuairiscigh an teagmhas seo do %s lena n-áirítear conas a fuair tú an pictiúr. Fágfar an slabhrashlabhra neamhbhailí ar an diosca ar eagla go mbeadh sé ina chuidiú leis an tsaincheist ba chúis leis an earráid seo a dhiagnóisiú.</translation>
    
ERR
There are formatting and terminology issues in the Irish translation. 

1. **Format Specifiers & Spacing**: The text `ó%dgo%d` is missing spaces around the format specifiers. It should be `ó %d go %d` to ensure the numbers do not run into the words.
2. **Erroneous Content**: The word `slabhrashlabhra` is a mistake (literally "chain-chain") for "chainstate".
3. **Inconsistency**: The word "snapshot" is translated inconsistently as "snapshot", "pictiúr" (which usually means a photograph), and "seat" (the standard technical term for a snapshot in Irish).

Correct translation:
Theip ar %s staid an tseat -assumeutxo a bhailíochtú. Léiríonn sé seo fadhb crua-earraí, nó fabht sna bogearraí, nó droch-mhodhnú bogearraí a cheadaigh seat neamhbhailí a luchtú. Mar thoradh air seo, stopfar an nód agus stopfaidh sé d'úsáid a bhaint as staid ar bith a tógadh ar an seat, ag athshocrú airde an tslabhra ó %d go %d. Ar an gcéad atosú eile, tosóidh an nód ag sioncronú arís ó %d gan aon sonraí tseat a úsáid. Tuairiscigh an teagmhas seo do %s, lena n-áirítear conas a fuair tú an seat. Fágfar staid tslabhra an tseat neamhbhailí ar an diosca ar eagla go mbeadh sé cabhrach chun an tsaincheist ba chúis leis an earráid seo a dhiagnóisiú.
```

<!-- cache_translation_check_ga_IE_c382e10fb683c19fb5d2e0414b769ff2dc30c0298fc9e5031cba9be89a6f1525 -->
```
        <source>Disk space for %s may not accommodate the block files. Approximately %u GB of data will be stored in this directory.</source>
        <translation>Ní féidir spás diosca le haghaidh %sa chur san áireamh sna blocchomhaid. Stórálfar thart ar %u GB de shonraí san eolaire seo.</translation>
    
ERR
There is a missing space between the format specifier '%s' and the following word 'a'.

Correct translation:
Ní féidir spás diosca le haghaidh %s a chur san áireamh sna blocchomhaid. Stórálfar thart ar %u GB de shonraí san eolaire seo.
```

<!-- cache_translation_check_ga_IE_1c256ef854f3cddaa3e6dd099deb9dcb63cc39e194c8de7dfd3614ff714de490 -->
```
        <source>Distributed under the MIT software license, see the accompanying file %s or %s</source>
        <translation>Dáilte faoin gceadúnas bogearraí MIT, féach na comhad atá in éindí %s nó %s</translation>
    
ERR
The Irish grammar is incorrect. The article "na" is plural, but the noun "comhad" is singular. Since the source text uses "file" (singular), the singular article "an" should be used.

Correct translation:
Dáilte faoin gceadúnas bogearraí MIT, féach an comhad atá in éindí %s nó %s
```

<!-- cache_translation_check_ga_IE_8b126b44db8c5612456b9b3d2250e09c0890d7f6a64819415f6886b4a3fc28ef -->
```
        <source>Error reading %s! Transaction data may be missing or incorrect. Rescanning wallet.</source>
        <translation>Earráid agus %s á léamh! Seans go bhfuil sonraí idirbhirt in easnamh nó mícheart. Sparán athscanadh.</translation>
    
ERR
The Irish translation is mostly correct, but the final phrase "Sparán athscanadh" is grammatically incorrect and uses a literal noun-verb pairing that doesn't flow naturally. In this context, it should indicate that the wallet is being rescanned.

Correct translation:
Earráid agus %s á léamh! Seans go bhfuil sonraí idirbhirt in easnamh nó mícheart. Sparán á athscanadh.
```

<!-- cache_translation_check_ga_IE_947364c9282f5a2577c87bdaf9f80759633b54d25263b010f3c7ac7f5fcc5dfe -->
```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Earráid agus%s á léamh! Seans go bhfuil sonraí idirbhirt in easnamh nó mícheart. Sparán athscanadh.</translation>
    
ERR
The translation is incorrect and does not match the source text. The translated text discusses a general reading error, missing transaction data, and rescanning the wallet, whereas the source text is a specific technical error message regarding an incorrect format record in a dumpfile. Additionally, there is a missing space between "agus" and "%s".

Correct translation:
Earráid: Tá taifead formáide an dumpchomhaid mícheart. Fuarthas "%s", bhíothas ag súil le "format".
```

<!-- cache_translation_check_ga_IE_68d17e808cde4844ae4040334eb3f93050f06fdde87f356ff06defd7a2f49b3e -->
```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Earráid: Ní thacaítear leis an leagan Dumpfile. Ní thacaíonn an leagan seo de bitcoin-sparán ach le leagan 1 dumpfiles. Fuair ​​​​tú dumpfile le leagan %s</translation>
    
ERR
There are hidden zero-width space characters (U+200B) between "Fuair" and "tú". Additionally, "Fuair tú" (You got) is an active voice translation of the impersonal "Got", and the use of "dumpfiles" with English pluralization inside an Irish sentence is poor style.

Correct translation:
Earráid: Ní thacaítear le leagan an dumpchomhaid. Ní thacaíonn an leagan seo de bitcoin-wallet ach le dumpchomhaid leagan 1. Fuarthas dumpchomhad de leagan %s
```

<!-- cache_translation_check_ga_IE_5911204301b1c8bc3bd668f03e9cedd6c07dd240cf3bdb73b54ab7212ddfa204 -->
```
        <source>Invalid or corrupt peers.dat (%s). If you believe this is a bug, please report it to %s. As a workaround, you can move the file (%s) out of the way (rename, move, or delete) to have a new one created on the next start.</source>
        <translation>Peers.dat neamhbhailí nó truaillithe (%s). Má chreideann tú gur fabht é seo, cuir in iúl do %s é le do thoil. Mar shruth oibre, is féidir leat an comhad (%s) a bhogadh as an mbealach (athainmnigh, bog nó scrios) chun ceann nua a chruthú ar an gcéad thús eile.</translation>
    
ERR
The translation for "As a workaround" is incorrect. "Mar shruth oibre" means "As a workflow." A more accurate translation for "workaround" in this context is "réiteach sealadach" (temporary solution).

Correct translation:
Peers.dat neamhbhailí nó truaillithe (%s). Má chreideann tú gur fabht é seo, cuir in iúl do %s é le do thoil. Mar réiteach sealadach, is féidir leat an comhad (%s) a bhogadh as an mbealach (athainmnigh, bog nó scrios) chun ceann nua a chruthú ar an gcéad thús eile.
```

<!-- cache_translation_check_ga_IE_7ad6aba8c824cec48e07f5bd568a33ba29d592bb8d7c81591be45b24eaee7511 -->
```
        <source>Invalid value detected for '-wallet' or '-nowallet'. '-wallet' requires a string value, while '-nowallet' accepts only '1' to disable all wallets</source>
        <translation>Braitheadh ​​luach neamhbhailí le haghaidh '-wallet' nó '-nowallet'. Teastaíonn luach teaghrán le '-wallet', agus ní ghlacann '-nowallet' ach le '1' chun gach sparán a dhíchumasú</translation>
    
ERR
There is a double space between the words "Braitheadh" and "luach".

Correct translation:
Braitheadh luach neamhbhailí le haghaidh '-wallet' nó '-nowallet'. Teastaíonn luach teaghrán le '-wallet', agus ní ghlacann '-nowallet' ach le '1' chun gach sparán a dhíchumasú
```

<!-- cache_translation_check_ga_IE_0e0ee60d2932351aa2a0c5099a8c437aa7768ebc8ab1e1686819b48cf23fce24 -->
```
        <source>Please contribute if you find %s useful. Visit %s for further information about the software.</source>
        <translation>Tabhair le do thoil má fhaigheann tú %s úsáideach. Tabhair cuairt ar %s chun tuilleadh faisnéise a fháil faoin bogearraí.</translation>
    
ERR
The translation contains grammatical errors and awkward phrasing. 
1. "Tabhair le do thoil" literally means "Give, please" but is missing the object of what to give (contribution/donation). In Irish, "Please contribute" is better translated as "Tabhair síntiús le do thoil".
2. "faoin bogearraí" is grammatically incorrect. "Faoin" is a contraction of "faoi" (about) and "an" (the, singular). "Bogearraí" (software) is a plural noun in Irish. It should be "faoi na bogearraí" (about the [plural] software).

Correct translation:
Tabhair síntiús le do thoil má fhaigheann tú %s úsáideach. Tabhair cuairt ar %s chun tuilleadh faisnéise a fháil faoi na bogearraí.
```

<!-- cache_translation_check_ga_IE_9950c18f37c7414041c0c98dfb7239e2b2beb7e808e1e153796b637237707338 -->
```
        <source>The block database contains a block which appears to be from the future. This may be due to your computer's date and time being set incorrectly. Only rebuild the block database if you are sure that your computer's date and time are correct</source>
        <translation>Tá bloc sa bhunachar sonraí ar cosúil gur as na todhchaí é. B'fhéidir go bhfuil dháta agus am do ríomhaire socraithe go mícheart. Ná déan an bunachar sonraí bloic a atógáil ach má tá tú cinnte go bhfuil dáta agus am do ríomhaire ceart</translation>
    
ERR
The translation contains grammatical errors in Irish. Specifically, "na todhchaí" uses the plural article instead of the singular "an", and "dháta" has an incorrect lenition (the 'h') in this context.

Correct translation:
Tá bloc sa bhunachar sonraí ar cosúil gur as an todhchaí é. B'fhéidir go bhfuil dáta agus am do ríomhaire socraithe go mícheart. Ná déan an bunachar sonraí bloic a atógáil ach má tá tú cinnte go bhfuil dáta agus am do ríomhaire ceart.
```

<!-- cache_translation_check_ga_IE_c38f1245ea4655178fe5ebdcbb4a5adbbb2ad92b8faf1ed83bad22763b1b41e2 -->
```
        <source>This is a pre-release test build - use at your own risk - do not use for mining or merchant applications</source>
        <translation>Tógáil tástála réamheisiúint é seo - úsáid ar do riosca fhéin - ná húsáid le haghaidh iarratas mianadóireachta nó ceannaí</translation>
    
ERR
The translation contains several grammatical errors and a number mismatch:
1. "iarratas" (singular) is used instead of the plural "iarratais" for "applications".
2. "réamheisiúint" should be in the genitive case "réamheisiúna".
3. "ceannaí" (merchant - noun) is used where an adjective or genitive form like "ceannaíochta" (commercial/merchant) would be more appropriate.
4. "feidhmchláir" is the standard modern term for software "applications".

Correct translation:
Is tógáil tástála réamheisiúna é seo - bain úsáid as ar do phriacal féin - ná húsáid le haghaidh feidhmchláir mhianadóireachta nó cheannaíochta
```

<!-- cache_translation_check_ga_IE_7aa4a65249788cae939c9fef77731a15e31cd129eac1669d9cfc099716f64cad -->
```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Is é seo an uasmhéid táille idirbhirt a íocann tú (i dteannta leis an ngnáth-tháille) chun tosaíocht a thabhairt do sheachaint páirteach caiteachais thar gnáth roghnú bonn.</translation>
    
ERR
The translation contains several grammatical errors in Irish. Adjectives like 'páirteach' should follow the noun they modify ('caiteachas páirteach'). Additionally, 'gnáth' is usually used as a prefix ('gnáthroghnú') or requires specific phrasing, and 'uasmhéid' should be preceded by 'an t-' as it is a masculine noun starting with a vowel.

Correct translation:
Is é seo an t-uasmhéid táille idirbhirt a íocann tú (i dteannta na gnáth-tháille) chun tosaíocht a thabhairt do sheachaint caiteachais pháirtigh thar gnáthroghnú bonn.
```

<!-- cache_translation_check_ga_IE_c86d8460c3c2fe7445b3e7a14d9be7c1a79b19372c8470040ee2dfdeec6e4046 -->
```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Is é seo an táille idirbhirt a fhéadfaidh tú cuileáil má tá sóinseáil níos lú ná dusta ag an leibhéal seo</translation>
    
ERR
The Irish translation contains a grammatical error and a literal transliteration that is less common than the standard term. In the phrase "a fhéadfaidh tú cuileáil", the verbal noun "cuileáil" requires the particle "a" and lenition (a chuileáil) to function correctly in this relative clause. Additionally, "dusta" is a transliteration of "dust"; while used in some contexts, "deannach" is the standard Irish word for "dust".

Correct translation:
Is é seo an táille idirbhirt a fhéadfaidh tú a chuileáil má tá an sóinseáil níos lú ná an deannach ag an leibhéal seo
```

<!-- cache_translation_check_ga_IE_f504ed46fb4ff727b26d2aeeb8d2cafc4e599f7b7a296e208c0a1f7dc7ce8217 -->
```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Leibhéal logála catagóir ar leith nach dtacaítear leis %1$s=%2$s. Bhíothas ag súil le %1$s=1:2. Catagóirí bailí: %3$s. Leibhéil loga bailí: %4$s.</translation>
    
ERR
The translation incorrectly replaces the descriptive placeholders `<category>` and `<loglevel>` with literal numbers `1:2`. These placeholders should be preserved (translated or kept as-is) to inform the user about the required format.

Correct translation:
Leibhéal logála catagóir-shonrach nach dtacaítear leis %1$s=%2$s. Bhíothas ag súil le %1$s=<catagóir>:<leibhéallogála>. Catagóirí bailí: %3$s. Leibhéil logála bhailí: %4$s.
```

<!-- cache_translation_check_ga_IE_de6230ec999c5cd51389c349bc289aee303da9f9da768ef994ee01c575771a63 -->
```
        <source>Cannot resolve -%s address: '%s'</source>
        <translation>Ní féidir réiteach seoladh -%s: '%s'</translation>
    
ERR
The Irish grammar is incorrect. In Irish, when a noun (seoladh) is followed by a definite attribute or a specifier, the genitive relationship or word order needs to be handled properly. "Réiteach" is a noun (solution/resolving), but in this context, the verb "réitigh" or the verbal noun with the correct preposition is needed. Also, the word order "réiteach seoladh -%s" is unnatural.

Correct translation:
Ní féidir seoladh -%s a réiteach: '%s'
```

<!-- cache_translation_check_ga_IE_360e555d9c8fa6581ae68c31fc6a7b119a1ee7a0f5a993d04ce3e6a17263e31e -->
```
        <source>%s is set very high! Fees this large could be paid on a single transaction.</source>
        <translation>Tá%s socraithe an-ard! D’fhéadfaí táillí chomh mór seo a íoc ar idirbheart amháin.</translation>
    
ERR
The translation contains a whitespace formatting issue. There is a missing space between the word "Tá" and the format specifier "%s".

Correct translation:
Tá %s socraithe an-ard! D’fhéadfaí táillí chomh mór seo a íoc ar idirbheart amháin.
```

<!-- cache_translation_check_ga_IE_e1f70d62862eefdd2e6f7489aa4935a1d11ec33727b9cd32f8357f7a660808de -->
```
        <source>Cannot provide specific connections and have addrman find outgoing connections at the same time.</source>
        <translation>Ní féidir naisc ar leith a sholáthar agus tá addrman chun naisc amach a aimsiú ag an am céanna.</translation>
    
ERR
The Irish translation is grammatically incorrect. The phrase "tá addrman chun" is a finite clause, which means the "Ní féidir" (Cannot) at the start of the sentence does not logically apply to the second action. In Irish, when "Ní féidir" governs two actions, both should be in the verbal noun construction.

Correct translation:
Ní féidir naisc ar leith a sholáthar agus ligean do addrman naisc amach a aimsiú ag an am céanna.
```

<!-- cache_translation_check_ga_IE_5a7ca5491283f4091b358b2981bc1150c962c5a2e00cd01ddf8ba0a3b58f9eaf -->
```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>Theip ar bhaint an tsainstáit seat seat (%s). Bain de láimh é roimh atosú.
</translation>
    
ERR
The translation contains a repetitive and slightly incorrect term for "snapshot chainstate". "Sainstáit seat seat" is redundant and "sainstáit" is not the standard way to translate "chainstate" in this context. A better translation for "snapshot chainstate dir" would be "eolaire staid slabhra an tseatfhreastail" or similar, though keeping "stát an tslabhra" is more accurate for "chainstate".

Correct translation:
Theip ar eolaire staid slabhra an tseatghrianghraif (%s) a bhaint. Bain de láimh é sula n-atosaíonn tú.
```

<!-- cache_translation_check_ga_IE_f33f9293c2cddd34e4c22f318864fc725d9593856829e78223c2cd5f27ec4228 -->
```
        <source>Incompatible options: -dnsseed=1 was explicitly specified, but -onlynet forbids connections to IPv4/IPv6</source>
        <translation>Roghanna neamh-chomhoiriúnacha: -dnsseed=1 sonraíodh go sainráite, ach cuireann -onlynet cosc ​​ar naisc le IPv4/IPv6</translation>
    
ERR
The translation contains a double space between "cosc" and "ar". Additionally, the word order in the middle clause is slightly unnatural for Irish; the subject (-dnsseed=1) should typically follow the verb (sonraíodh).

Correct translation:
Roghanna neamh-chomhoiriúnacha: sonraíodh -dnsseed=1 go sainráite, ach cuireann -onlynet cosc ar naisc le IPv4/IPv6
```

<!-- cache_translation_check_ga_IE_7fdfa8e3f5eff6fb90d7c9e0e5ed895223f57c47f8d899bc522a1db26891bfb5 -->
```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>Méid neamhbhailí le haghaidh %s=&lt;amount&gt;: '%s' (ní mór an táille sealaíochta nóiméad de %s a bheith ann ar a laghad chun idirbhearta bhfostú a chosc)</translation>
    
ERR
The Irish translation contains a grammatical error and a mistranslation of "stuck transactions". Specifically, "táille sealaíochta nóiméad" translates "minrelay fee" incorrectly (using "nóiméad" for "minute" instead of "minimum"). Additionally, "idirbhearta bhfostú" is grammatically incorrect; it should be "idirbhearta atá i bhfostú" or "idirbhearta greamaithe".

Correct translation:
Méid neamhbhailí le haghaidh %s=&lt;amount&gt;: '%s' (ní mór é a bheith ar a laghad an t-íostáille sealaíochta de %s chun idirbhearta atá i bhfostú a chosc)
```

<!-- cache_translation_check_ga_IE_080bab34771e85719508a2f454d2bc362a2768f23b41f331423f9ecbfb008e14 -->
```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is explicitly forbidden: -onion=0</source>
        <translation>Tá naisc amach teoranta do Tor (-onlynet=onion) ach tá cosc ​​sainráite ar an seachfhreastalaí chun líonra Tor a bhaint amach: -onion=0</translation>
    
ERR
There is a double space between the words "cosc" and "sainráite".

Correct translation:
Tá naisc amach teoranta do Tor (-onlynet=onion) ach tá cosc sainráite ar an seachfhreastalaí chun líonra Tor a bhaint amach: -onion=0
```

<!-- cache_translation_check_ga_IE_b81bf190e2c953b057a8009302249823c6d2b560166be8879dcaeab06cc90140 -->
```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>Naisc amach teoranta do Tor (-onlynet=onion) ach ní thugtar an seachfhreastalaí chun líonra Tor a bhaint amach: ní thugtar aon seachfhreastalaí, -oinniún nó -listenonion</translation>
    
ERR
The translation incorrectly translates technical command-line arguments. Flags like `-proxy` and `-onion` should remain untranslated as they refer to specific software parameters.

Correct translation:
Naisc amach teoranta do Tor (-onlynet=onion) ach ní thugtar an seachfhreastalaí chun líonra Tor a bhaint amach: ní thugtar aon cheann de -proxy, -onion ná -listenonion
```

<!-- cache_translation_check_ga_IE_ff8b3cbc2b2f98f916f68f81cdccc231a1f5cf36e34c2fb675111d66953cabfc -->
```
        <source>Specified -blockreservedweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Sáraíonn -blockreservedweight (%d) níos mó ná meá uasta bloc comhdhearcadh (%d)</translation>
    
ERR
The Irish translation is grammatically incorrect and contains redundant phrasing. "Sáraíonn" means "exceeds" and "níos mó ná" means "more than," so using both is tautological. Additionally, "meá" refers to the act of weighing or a scale, whereas "meáchan" is the correct noun for "weight." The word "Specified" was also omitted.

Correct translation:
Sáraíonn an -blockreservedweight (%d) sonraithe uasmheáchan bloc an chomhdhearcaithe (%d)
```

<!-- cache_translation_check_ga_IE_46b7cc407e991d6b27a6feecff88be4988682ca42c72728e082d3251d2a41e0a -->
```
        <source>Specified -blockreservedweight (%d) is lower than minimum safety value of (%d)</source>
        <translation>Sáraíonn -blockreservedweight sonraithe (%d) níos ísle ná an íosluach sábháilteachta de (%d)</translation>
    
ERR
The Irish translation contains redundant and ungrammatical phrasing. The word 'Sáraíonn' (exceeds/violates) is misplaced and contradicts the meaning of 'níos ísle' (lower). The sentence structure is unnatural.

Correct translation:
Tá an -blockreservedweight sonraithe (%d) níos ísle ná an t-íosluach sábháilteachta (%d)
```

<!-- cache_translation_check_ga_IE_8f4a8c4e5d3f583141074790435088875b59b167105ae411d20c4e061ba074fb -->
```
        <source>
Unable to cleanup failed migration</source>
        <translation>
Ní féidir an t-imirce theip a ghlanadh</translation>
    
ERR
The translation contains grammatical errors. "Imirce" is a feminine noun, so it should be "an imirce" rather than "an t-imirce" (the t-prefix is for masculine nouns starting with a vowel). Also, "failed" as an adjective is "teipthe" rather than the verb form "theip".

Correct translation:
Ní féidir an imirce theipthe a ghlanadh
```

<!-- cache_translation_check_ga_IE_b96f55798c570e954360eca3b070ff629aeb533e01975ed01ee462faf9871337 -->
```
        <source>
Unable to restore backup of wallet.</source>
        <translation>
Ní féidir cúltaca an sparán a chur ar ais.</translation>
    
ERR
The translation contains a grammatical error in Irish. The word "sparán" (wallet) should be in the genitive case ("sparáin") when following the noun "cúltaca" (backup).

Correct translation:
Ní féidir cúltaca an sparáin a chur ar ais.
```

<!-- cache_translation_check_ga_IE_5cbc12665d6bae7a0380afd2f02ae98e16ff4fa6765d01da9a8340ca65b0e098 -->
```
        <source>Assumeutxo data not found for the given blockhash '%s'.</source>
        <translation>Ní bhfuarthas sonraí Assumeutxo don bhlocshlabhra '%s' a tugadh.</translation>
    
ERR
The translation incorrectly translates "blockhash" as "bhlocshlabhra" (blockchain). In Bitcoin terminology, "blockhash" refers to the unique identifier (hash) of a block, not the chain itself.

Correct translation:
Ní bhfuarthas sonraí Assumeutxo don hais bhloic '%s' a tugadh.
```

<!-- cache_translation_check_ga_IE_d42f2279dedf1956cc8b061f73687fc95b0aa9f86f83fa06799b5ac4dfcbfdda -->
```
        <source>Error loading %s</source>
        <translation>Earráid lódáil %s</translation>
    
ERR
The Irish translation is grammatically incorrect. When one noun qualifies another (forming a compound or indicating a relationship like "Error of loading"), the second noun should be in the genitive case. The genitive form of "lódáil" is "lódála".

Correct translation:
Earráid lódála %s
```

<!-- cache_translation_check_ga_IE_a936ed0115b82d4674ec6bcf69a6041e5ae358ce3d66e837da2ad16ce1f4f41c -->
```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Earráid: Fuair ​​tú luach nach heicsidheachúlach é: %s</translation>
    
ERR
There is a double space between "Fuair" and "tú". Additionally, in a technical context, the impersonal "Fuarthas" (Was received/found) is more appropriate than "Fuair tú" (You got).

Correct translation:
Earráid: Fuarthas luach nach heicsidheachúlach é: %s
```

<!-- cache_translation_check_ga_IE_ca59e1775b538166d00d6a645ecb2f90025b82c30be25827fe54d3ef8757af85 -->
```
        <source>Error: No %s addresses available.</source>
        <translation>Earráid: Níl seoladh %s ar fáil.</translation>
    
ERR
The English source uses the plural "addresses", but the Irish translation uses the singular "seoladh". Additionally, to properly convey "No... available" in Irish, it is more natural to include "aon" (any).

Correct translation:
Earráid: Níl aon seoltaí %s ar fáil.
```

<!-- cache_translation_check_ga_IE_65c61d0874c19b6a31fc588be524e653701c0c68e1fbbcd555c5a101b230c125 -->
```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>Earráid: Ní féidir leagan%u a pharsáil mar uint32_t</translation>
    
ERR
There is a missing space before the format specifier '%u'. In Irish, there should be a space between the word 'leagan' (version) and the variable.

Correct translation:
Earráid: Ní féidir leagan %u a pharsáil mar uint32_t
```

<!-- cache_translation_check_ga_IE_cd1dd3527f0e92514235321e9324aa0d4fd7756d14f33841bf85ee04a3bbb82c -->
```
        <source>Failed to acquire rescan reserver during wallet initialization</source>
        <translation>Theip ar an gcuntar athscanála a fháil le linn thúsú an sparáin.</translation>
    
ERR
The word "gcuntar" means "counter" (as in a numerical counter or a shop counter), which is an incorrect translation for "reserver". In the context of Bitcoin software, a "reserver" is a mechanism that secures or reserves a process.

Correct translation:
Theip ar áirithint athscanála a fháil le linn thúsú an sparáin.
```

<!-- cache_translation_check_ga_IE_bb802772df0b82b973e07244d71650a17a3a6a6996d8f4c01c997810f6891f9b -->
```
        <source>Failed to rescan the wallet during initialization</source>
        <translation>Theip athscanadh ar an sparán le linn túsúchán</translation>
    
ERR
The Irish grammar is incorrect. After "Theip", the preposition "ar" is required to indicate what failed. Additionally, "le linn" triggers the genitive case for the following noun, so "túsúchán" should be "túsúcháin". Furthermore, "athscanadh" should be followed by the genitive "an sparáin" (of the wallet).

Correct translation:
Theip ar athscanadh an sparáin le linn túsúcháin
```

<!-- cache_translation_check_ga_IE_8fa80ca0202a218f282856c38f284036396a983fcc482c526006ea5ce6880bb7 -->
```
        <source>Failed to verify database</source>
        <translation>Theip ar fhíorú an mbunachar sonraí</translation>
    
ERR
The Irish translation contains a grammatical error regarding case and word order. In Irish, "Failed to verify the database" is most naturally expressed using the "fail on [noun] its verifying" construction or by using the genitive case correctly. The provided translation uses eclipsis ("mbunachar") incorrectly in this context.

Correct translation:
Theip ar an mbunachar sonraí a fhíorú
```

<!-- cache_translation_check_ga_IE_97a0ee87e5e197ddf91f6749348abf90ea4c0d8e63ac24f1ce0271cba698479b -->
```
        <source>Ignoring duplicate -wallet %s.</source>
        <translation>Neamhaird ar sparán dhúbailt %s.</translation>
    
ERR
The translation translates the command-line argument '-wallet' into the Irish word 'sparán'. Command-line arguments and flags should remain untranslated to help the user identify the specific configuration option. Additionally, 'dhúbailt' is not the correct adjective for 'duplicate' in this context; 'dúblach' is preferred.

Correct translation:
Neamhaird ar -wallet dúblach %s.
```

<!-- cache_translation_check_ga_IE_b03549ada3f0632b92b4d49bdfd1853b85168d6e2cc01abf4e6b22f43b5be833 -->
```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>Bloc geineasas mícheart nó ní aimsithe. datadir mícheart don líonra?</translation>
    
ERR
The Irish translation is grammatically incorrect. "ní aimsithe" is a literal but incorrect way to say "not found". In Irish, to express that something was not found, one would typically use the autonomous past tense "níor aimsíodh" or a phrase like "nach bhfuil aimsithe".

Correct translation:
Bloc geineasas mícheart nó níor aimsíodh aon cheann. Datadir mícheart don líonra?
```

<!-- cache_translation_check_ga_IE_40102d6aaefa0cb49f78b95528a6b6e3e58e7fa89f83ce38baacb28b762c80f0 -->
```
        <source>Insufficient funds</source>
        <translation>Neamhleor ciste</translation>
    
ERR
In Irish, the adjective typically follows the noun. Additionally, "funds" is usually plural in this context. "Neamhleor ciste" uses an incorrect word order and singular form.

Correct translation:
Cistí neamhleora
```

<!-- cache_translation_check_ga_IE_43ec6c34685263727061ab78e2ede20e6559b25c31d0580924e8fcab5368f998 -->
```
        <source>Listening for incoming connections failed (listen returned error %s)</source>
        <translation>Theip ar éisteacht le naisc isteach (éisteacht ar ais earráid %s)</translation>
    
ERR
The phrase "éisteacht ar ais earráid" is a literal and grammatically incorrect translation of "listen returned error". In Irish, "ar ais" means "back" (as in returning to a place), but it is not used as a verb meaning "to return a value". Furthermore, "listen" in the parentheses refers to a specific system function call and is typically left as is or treated as a noun.

Correct translation:
Theip ar éisteacht le naisc isteach (thug listen earráid %s ar ais)
```

<!-- cache_translation_check_ga_IE_dec7998ca31ae8acb001b5aff9eafa634b1b89c24b7e386fe93af29f78250e6a -->
```
        <source>Prune cannot be configured with a negative value.</source>
        <translation>Ní féidir Bearradh a bheidh cumraithe le luach diúltach.</translation>
    
ERR
The Irish grammar is incorrect. The phrase "a bheidh" (which will be) is the future relative form of the verb "to be," whereas the sentence requires the verbal noun "a bheith" (to be) or "a chumrú" (to configure) to complete the "Ní féidir..." (It is not possible...) construction. Additionally, "Bearradh" does not need to be capitalized unless it's the start of the sentence or a specific proper noun in the UI.

Correct translation:
Ní féidir bearradh a chumrú le luach diúltach.
```

<!-- cache_translation_check_ga_IE_52bfe8ca04051b4349c0f4b2ce1dc84c3278e8c7d8c054fae051800d844db305 -->
```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>Seachnóidh an sparán níos lú ná an táille athsheachadán íosta a íoc.</translation>
    
ERR
The Irish translation contains a grammatical error regarding the genitive case and word order. "athsheachadán" (relay) should be in the genitive case ("athsheachadáin") when modifying "táille" (fee). Additionally, the placement of the adjective "íosta" (minimum) is more natural before the genitive noun.

Correct translation:
Seachnóidh an sparán níos lú ná an táille íosta athsheachadáin a íoc.
```

<!-- cache_translation_check_ga_IE_8ca2b8b7dab6ba2d86d3b24c16502b437c368dd6760aec3bb37144fb7ddb84ad -->
```
        <source>Unable to create the PID file '%s': %s</source>
        <translation>Níorbh fhéidir cruthú comhad PID '%s': %s</translation>
    
ERR
The Irish grammar is incorrect. In Irish, when a verbal noun (cruthú) has a definite object (the PID file), the structure should typically be [Object] + [a] + [Verbal Noun]. Additionally, the definite article "an" (the) is missing.

Correct translation:
Níorbh fhéidir an comhad PID '%s' a chruthú: %s
```

<!-- cache_translation_check_ga_IE_355202480a0d1270abb1281dfdc9bffee502aa0be0fdf714c534eb78022b8faf -->
```
        <source>Unknown address type '%s'</source>
        <translation>Anaithnid cineál seoladh '%s'</translation>
    
ERR
The Irish translation is grammatically incorrect. In Irish, adjectives typically follow the noun, and when one noun qualifies another, the second noun usually follows the first and is often in the genitive case. "Anaithnid cineál seoladh" translates literally as "Unknown type address" in a word-for-word manner that does not follow Irish syntax.

Correct translation:
Cineál seolta anaithnid '%s'
```

<!-- cache_translation_check_ga_IE_474aa382a1b9f9a4249142916017e7cdc9bf75b76f28d9d960ca85f4732591e4 -->
```
        <source>Unknown change type '%s'</source>
        <translation>Anaithnid cineál sóinseáil '%s'</translation>
    
ERR
The Irish translation has incorrect word order and grammar. In Irish, the adjective 'anaithnid' (unknown) should follow the noun phrase it modifies, and 'sóinseáil' (change) should be in the genitive case ('sóinseála') when following 'cineál' (type).

Correct translation:
Cineál sóinseála anaithnid '%s'
```

<!-- cache_translation_check_ga_IE_a6a3f9ec960fda9d62350b2b039dd41dff2bbbfdb3943cc5f7189c83b4fcd7bf -->
```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>Rialacha nua anaithnid curtha i ngníomh (leagan giotán %ii)</translation>
    
ERR
The format specifier was not taken over correctly from the source. The source contains '%i', but the translation contains '%ii', which would result in an extra 'i' appearing after the number.

Correct translation:
Rialacha nua anaithnid curtha i ngníomh (leagan giotán %i)
```

<!-- cache_translation_check_ga_IE_5c122b0a6326782c2f6bb8eed52395ea7de9631c563b61635b6c28f941bd6981 -->
```
        <source>Unsupported logging category %s=%s.</source>
        <translation>Catagóir logáil gan tacaíocht %s=%s.</translation>
    
ERR
The translation has a minor grammatical error. In Irish, when one noun qualifies another (e.g., "logging category"), the second noun should be in the genitive case. "Logáil" (logging) should be "logála" (of logging).

Correct translation:
Catagóir logála gan tacaíocht %s=%s.
```

<!-- cache_translation_check_ga_IE_afcb7dfe4ed7569b2d949652843094743dba5cd903f974894dcc322fac91002b -->
```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Earráid: Níorbh fhéidir watch amháin tx %s a chur le sparán faire amháin</translation>
    
ERR
The translation is inconsistent and contains an untranslated English word ('watch') in the first instance of 'watchonly', while using the Irish word 'faire' in the second instance. Technical terms should be consistent.

Correct translation:
Earráid: Níorbh fhéidir tx faire amháin %s a chur le sparán faire amháin
```

<!-- cache_translation_check_ga_IE_6d3b4f90e6ca50a05b9c7a32c70c1b78827c5adf83044573c7f6e2ec897b54c9 -->
```
        <source>Error: Could not delete watchonly transactions. </source>
        <translation>Earráid: Níorbh fhéidir idirbhearta faire amháin a scriosadh.</translation>
    
ERR
The translation is missing a trailing space that exists in the source text.

Correct translation:
Earráid: Níorbh fhéidir idirbhearta faire amháin a scriosadh.
```

<!-- cache_translation_check_ga_IE_5e94771fc8b62087c9b74f90e0183fd746c2408524bc63dc3a46c4d6042d74b4 -->
```
        <source>Verifying wallet(s)…</source>
        <translation>Sparán(aí) á fhíorú…</translation>
    
ERR
The plural of the Irish word 'sparán' (wallet) is 'sparáin', not 'sparánaí'. Therefore, the suffix used to indicate the optional plural should be '(áin)' rather than '(aí)'.

Correct translation:
Sparán(áin) á fhíorú…
```
</details>

Number of issues: 199.
