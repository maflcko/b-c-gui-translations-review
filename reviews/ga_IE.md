# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>ga_IE</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bga_IE%5D%20request)


<!-- cache_translation_check_ga_IE_a76f02c2625faa3c26bf62a305ec068da9a05b182f189ebbf2a0015e2c7e887e -->
```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
ERR
The translation "Comhad athróige camógdheighilte" is problematic. "Comhad athróige" translates as "variable file", which is incorrect. The standard and accepted Irish translation for "Comma separated file" (as used for "CSV") is "Comhad camógscartha" or "Comhad camóg deighilte".

Correct translation:
Comhad camógscartha

Alternatively (less common, but accurate):
Comhad camóg-deighilte
```

<!-- cache_translation_check_ga_IE_2070d76dae35fbcddd0c442798ac9506e86e9b8a34c623ff5bec7102f214bc0e -->
```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Tharla earráid ag iarraidh an liosta seoltaí a shábháil go %1. Bain triail eile, le d'thoil.</translation>
    
ERR
Problems:
- The preposition "go %1" is unnatural here in Irish; "chuig %1" (or "chun %1") is better for "to %1" in the context of saving to a file.
- "Bain triail eile" is non‑idiomatic; "Bain triail arís" is the usual phrasing for "please try again."
- "le d'thoil" is incorrect orthography — it should be "le do thoil" (no apostrophe).

Correct translation:
Tharla earráid agus rinneamar iarracht an liosta seoltaí a shábháil chuig %1. Bain triail arís, le do thoil.
```

<!-- cache_translation_check_ga_IE_fbbd49736bb3a0aadcc535930d40b12e1e7c96df21eb7e79e034197e16d65fa9 -->
```
        <source>Receiving addresses - %1</source>
        <translation>Seoltaí á bhfáil - %1</translation>
    
ERR
The Irish translation "Seoltaí á bhfáil - %1" is not idiomatic/grammatically correct. The progressive construction should use "ag" + verbal noun. A better translation is:

Seoltaí ag fáil - %1
```

<!-- cache_translation_check_ga_IE_35ce3e95966fdd3e569b5f5ec2779e077dfd87065cf721a3fc05fc214bef7235 -->
```
        <source>%1 d</source>
        <translation>%1 l</translation>
    
ERR
The English source uses '%1 d', where 'd' likely stands for 'days'. The translation '%1 l' is using 'l', which does not correspond to the Irish abbreviation for 'days'. The correct Irish abbreviation is 'la' or 'lá' for 'day', but abbreviations are less commonly used in Irish than in English. For plural, 'lá' is 'laethanta', but abbreviation is typically 'lá'.

Correct translation:
%1 lá
```

<!-- cache_translation_check_ga_IE_960f84a66baa6755f976c33c0a3e1f3a9e45c9117efe19ac368cf962c5bbe9bf -->
```
        <source>%1 m</source>
        <translation>%1 n</translation>
    
ERR
The translation is problematic. The source uses "m" (likely for "minutes"), but the translation uses "n", which does not correspond to "minutes" in Irish. The correct abbreviation for "minute" in Irish is "nóim" or sometimes simply "n".

However, if the style demands an abbreviation, the Irish standard is "nóim" for minutes. Single-letter "n" might not be widely understood. For best clarity and standardization, "nóim" should be used.

Correct translation:
%1 nóim
```

<!-- cache_translation_check_ga_IE_1a9d7941ee4ff8f43e33d55452428a54bf7b4af55623f65cfad4a23c72510b17 -->
```
        <source>Show the list of used sending addresses and labels</source>
        <translation>Taispeáin an liosta de seoltaí seoladh úsáidte agus na lipéid </translation>
    
ERR
The phrase "seoltaí seoladh úsáidte" is incorrect and redundant; "sending addresses" should be "seoltaí seolta" or more accurately "seoltaí seolta amach". There is also an unnecessary space at the end.

Correct translation:
Taispeáin an liosta de sheoltaí seolta amach a úsáideadh agus na lipéid
```

<!-- cache_translation_check_ga_IE_04e25357b9ac5d8ea3b71e252ab44f23bfe1ecb661ddebb328d2250184589aa3 -->
```
        <source>&amp;Sending addresses</source>
        <translation>&amp;Seoltaí seoladh</translation>
    
ERR
The translation "&amp;Seoltaí seoladh" is problematic for these reasons:
1. "Seoltaí" already means "addresses", and "seoladh" means "address" (singular). This is redundant.
2. "Sending addresses" in this context refers to Bitcoin addresses from which coins are sent; the best translation is "Seoltaí seolta" or "Seoltaí seolta amach" (to clarify "sending" as in "sending out").
3. The ampersand (&amp;) is preserved, which is correct.

Correct translation:
&amp;Seoltaí seolta
```

<!-- cache_translation_check_ga_IE_c404e8d632f955f20538c55725a2cb700f45401c9b277a0cb8ce5b188e534a08 -->
```
        <source>%1 client</source>
        <translation>%1 cliaint</translation>
    
ERR
The translation uses "cliaint" for "client", which is an incorrect spelling in Irish. The correct word is "cliant". There are no issues with the format specifier.

Correct translation:
%1 cliant
```

<!-- cache_translation_check_ga_IE_b3a4d3e16cfb22170ee3731d15a295985c684c00f55bfd488ec3fcc35d7ed427 -->
```
        <source>S&amp;how</source>
        <translation>S&amp;conas</translation>
    
ERR
The translation "Sconas" is incorrect for "Show" in Irish. "Sconas" is not an Irish word and does not translate as "Show". The correct Irish translation for "Show" in this context (for menu/label) would be "Taispeáint".

Correct translation:
T&amp;aispeáint
```

<!-- cache_translation_check_ga_IE_be59dc72cfec6bdd6a0cc2415ab0b047308cfbbab75c957346981295e622e5a0 -->
```
        <source>(un)select all</source>
        <translation>(neamh)roghnaigh gach rud </translation>
    
ERR
The translation "(neamh)roghnaigh gach rud" is understandable, but there is a spelling issue and an unnecessary trailing space. "Neamhroghnaigh" is not standard usage; the usual negation for "roghnaigh" is "díroghnaigh".

Correct translation:
(Roghnaigh/Díroghnaigh) gach rud
```

<!-- cache_translation_check_ga_IE_f76515df9b1327b7dff3c27143b961a7b5039149a0885aa08c6c3154559e7da7 -->
```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
ERR
There is a spelling error in the Irish translation. "Cóipeáíl" should be "Cóipeáil", and "sóinseáil" is a non-standard rendering for "change" in the Bitcoin context—usually "athrú" is used for "change" (as in transaction change).

Correct translation:
Cóipeáil athrú
```

<!-- cache_translation_check_ga_IE_16a829ea7557691e9e0377a6fe0f9de4a648186fe1018f8ce46caccf5a019625 -->
```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>An seoladh chomhcheangailte leis an iontráil liosta seoltaí seo. Ní féidir é seo a mionathraithe ach do seoltaí seoladh.</translation>
    
ERR
The translation is problematic: "do seoltaí seoladh" is incorrect (looping translation: "for sending addresses" seems to be translated as "for sending addresses address"). Also, "mionathraithe" is not commonly used for "modified"; "athrú" is preferred. The rest of the translation is generally accurate, but the problematic segment renders it unnatural.

Correct translation:
An seoladh atá bainteach leis an iontráil seo sa liosta seoltaí. Ní féidir é seo a athrú ach do sheoltaí seolta.
```

<!-- cache_translation_check_ga_IE_511f70952f678ca37e9af45a5d8f70831ccfdac0c6951b6ffc94b170c299618e -->
```
        <source>New sending address</source>
        <translation>Seoladh nua seoladh</translation>
    
ERR
The translation repeats the word "seoladh" (address) unnecessarily, resulting in "address new address". The correct translation should be:

Seoladh nua seolta

Or more idiomatically:

Seoladh nua chun seolta
```

<!-- cache_translation_check_ga_IE_7f8254ab58a12f0acb39c67dc845b3c7a558b84e685714f1f03c43c652b8e3a1 -->
```
        <source>Edit sending address</source>
        <translation>Eagarthóireacht seoladh seoladh</translation>
    
ERR
The translation is problematic. "Eagarthóireacht seoladh seoladh" is incorrect; it redundantly repeats the word "seoladh" (address) and does not accurately convey the meaning of "Edit sending address." The proper translation should be "Cuir in eagar seoladh seolta" or "Cuir in eagar an seoladh seolta" (if "the sending address" is meant). 

Correct translation:
Cuir in eagar seoladh seolta
```

<!-- cache_translation_check_ga_IE_7097bf34f143965b7e00e1a416a5e1ff225bbf509662891ebffc847cf96af30a -->
```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Níl seoladh bailí Bitcoin í an seoladh iontráilte "%1".</translation>
    
ERR
The Irish translation is grammatically incorrect and has wrong word order ("Níl seoladh bailí Bitcoin í an seoladh iontráilte "%1"."). The format specifier %1 is preserved, but the sentence should place the entered address phrase before the predicate and use the proper copula/structure.

Correct translation:
Níl an seoladh iontráilte "%1" ina sheoladh Bitcoin bailí.
```

<!-- cache_translation_check_ga_IE_606f2c3392ee23eba7467848d92f299ae7a4f3e3b7497316c3e103538cd93a6a -->
```
        <source>Estimated time left until synced</source>
        <translation>Measta am fágtha go dtí sioncrónaithe</translation>
    
ERR
The translation is inaccurate and unidiomatic. "Measta am fágtha go dtí sioncrónaithe" does not convey the intended meaning clearly in Irish. The phrase "go dtí sioncrónaithe" is awkward and would more naturally be rendered as "go dtí go mbeidh sioncrónaithe" or "go dtí go mbeidh sé sioncrónaithe". Also, "Measta am fágtha" is not idiomatic; "Am measta fágtha" or "Am fágtha measta" is better.

Correct translation:
Am fágtha measta go dtí go mbeidh sé sioncrónaithe
```

<!-- cache_translation_check_ga_IE_a5b40bd1d47bbab099ea2933c0bd02e063ca289fa7a1ab965d8c3e64efc6c6f0 -->
```
        <source>&amp;Third-party transaction URLs</source>
        <translation>URLanna idirbheart tríú páirtí</translation>
    
ERR
The translation is missing the ampersand (&), which is intended for keyboard shortcuts and should appear exactly once, as in the source.

Correct translation:
&URLanna idirbheart tríú páirtí
```

<!-- cache_translation_check_ga_IE_b65fb896e1dd0cb6ad835358483797b07689ba832fa94ca3945e48d4e730dd06 -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Úsáid seachfhreastalaí SOCKS5 ar leith chun sroicheadh piaraí trí sheirbhísí Tor oinniún:</translation>
    
ERR
The translation is missing the '&' (ampersand) which is present in the source, usually indicating a keyboard shortcut. It should appear exactly once in the translation.

Correct translation:
Úsáid seachfhreastalaí SOCKS&5 ar leith chun piaraí a bhaint amach trí sheirbhísí oinniún Tor:
```

<!-- cache_translation_check_ga_IE_86afc8f988d0ad22d9fcd706474dee9cca6337d282f1d67165c226edbd086e0e -->
```
        <source>&amp;OK</source>
        <translation>&amp;Togha</translation>
    
ERR
The translation of "&OK" as "&Togha" is problematic. "Togha" means "choice" or "selection" in Irish, which does not accurately convey "OK" as an action (i.e., to confirm or accept). The standard translation for "OK" in Irish user interfaces is simply "OK".

Correct translation:
&OK
```

<!-- cache_translation_check_ga_IE_f767d2470530d58e9c8dddc9388c8938bece5604754d8f71d60284f0724a2663 -->
```
        <source>Mapped AS</source>
        <translation>CU Mapáilte</translation>
    
ERR
The translation of "Mapped AS" as "CU Mapáilte" is problematic for several reasons:
- "AS" in the context of networking commonly stands for "Autonomous System". Translating "AS" as "CU" is unclear and not a standard abbreviation in Irish. Also, "CU" does not correspond to any recognized Irish term for "Autonomous System".
- "Mapáilte" is a correct past participle for "mapped", but the whole phrase together is not idiomatic or standard in Irish.
- In technical contexts, "Mapped" can often be rendered as "Mapáilte" or "Aimapáilte", but the whole phrase should better reflect the original meaning.

Correct translation:
AS mapáilte

or, spelled out fully in Irish context:
Córas Uathrialach mapáilte

But the standard is often to leave "AS" untranslated, so:

AS mapáilte

is best.
```

<!-- cache_translation_check_ga_IE_8e3580f9b44f60cd0a35aa583559d173f4d399321201a1e5e6eafe3ad17eb574 -->
```
        <source>detecting: peer could be v1 or v2</source>
        <extracomment>Explanatory text for "detecting" transport type.</extracomment>
        <translation>bhrath: d’fhéadfadh v1 nó v2 a bheith i gcomhghleacaí</translation>
    
ERR
The translation is problematic. The Irish word "bhrath" does not adequately correspond to "detecting" as a verbal noun or present participle here; it looks like a noun form ("betrayal" or "notice/observation") with wrong mutation. The rest of the translation generally conveys the message but could be clearer.

Correct translation:
"Ag braiteadh: d’fhéadfadh v1 nó v2 a bheith i gcomhghleacaí"
```

<!-- cache_translation_check_ga_IE_a3091a4315888a5971d8f6145ce8cceab5e205955b5000672d3b24c1d7b9a2a8 -->
```
        <source>S&amp;end</source>
        <translation>S&amp;eol</translation>
    
ERR
The translation "Seol" is correct for "Send" in Irish ('ga_IE'), and the shortcut marker (&) is preserved. However, the source text's shortcut is on the "e" in "Send" (S&end), while in the translation, it is also on the "e" (S&eol). This may be acceptable if it does not conflict with other shortcuts, but typically, the shortcut should be placed on the same logical letter/position as in the source if possible.

Correct translation:
S&eol

So, the translation is technically correct, but you may want to ensure that the shortcut does not conflict within the UI.
```

<!-- cache_translation_check_ga_IE_f76515df9b1327b7dff3c27143b961a7b5039149a0885aa08c6c3154559e7da7 -->
```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
ERR
There is a spelling error in the Irish translation. "Cóipeáíl" should be "Cóipeáil", and "sóinseáil" is a non-standard rendering for "change" in the Bitcoin context—usually "athrú" is used for "change" (as in transaction change).

Correct translation:
Cóipeáil athrú
```

<!-- cache_translation_check_ga_IE_98a292a82ce7aede798e69a79a6fc7f3ce40b84320c0eb86323694aeb611cf87 -->
```
        <source>Cr&amp;eate Unsigned</source>
        <translation>Cruthaigh Gan Sín</translation>
    
ERR
The translation does not include the '&' that indicates the shortcut key in the source. This must be present exactly once in the translation.

Correct translation:
Cr&amp;uthaigh Gan Sín
```

<!-- cache_translation_check_ga_IE_84cfc3dd0aaeb04dd0fb349af875e4aee635a49dce518961d9d13195f109b713 -->
```
        <source>Copy full transaction &amp;details</source>
        <translation>Cóipeáil idirbheart agus sonraí iomlána</translation>
    
ERR
The '&' indicating a shortcut key in the source ("&details") is missing from the translation. It must be included exactly once, typically at the point where the shortcut key should be assigned.

Correct translation:
Cóipeáil &sonraí iomlána an idirbheart
```

<!-- cache_translation_check_ga_IE_6b0f9328d21840b4a26c19eeaf5cbd942393b5bcb07b8c862501e132063be589 -->
```
        <source>A&amp;bandon transaction</source>
        <translation>Idirbheart&amp;tréigean</translation>
    
ERR
The ampersand (&) indicating the shortcut key is not at the start of the word in the translation, unlike in the source where it is before the 'b' in 'Abandon'. In Irish, the word order should also be natural. For menu items, a better translation is "Tréig &idirbheart", putting the ampersand before the shortcut letter.

Correct translation:
&Tréig idirbheart
```

<!-- cache_translation_check_ga_IE_a76f02c2625faa3c26bf62a305ec068da9a05b182f189ebbf2a0015e2c7e887e -->
```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
ERR
The translation "Comhad athróige camógdheighilte" is problematic. "Comhad athróige" translates as "variable file", which is incorrect. The standard and accepted Irish translation for "Comma separated file" (as used for "CSV") is "Comhad camógscartha" or "Comhad camóg deighilte".

Correct translation:
Comhad camógscartha

Alternatively (less common, but accurate):
Comhad camóg-deighilte
```

<!-- cache_translation_check_ga_IE_3be7182e3268aae212ce152f9791da5f1e49fffdac1936b1e4b57b05ba9d5f07 -->
```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>Cóipeáil PSBT bump táille chuig an ngearrthaisce</translation>
    
ERR
The translation is problematic. The sentence incorrectly uses the infinitive ("Cóipeáil") rather than the past tense, and "bump táille" is not a natural or clear expression in Irish for "fee-bump". The translation should more accurately reflect the English source, especially the phrase "Fee-bump PSBT copied to clipboard".

Correct translation:
PSBT ardaithe táille cóipeáilte chuig an ngearrthaisce
```

<!-- cache_translation_check_ga_IE_c33ad8874e90aa7b0ea59b40febb4ae0814337addc2216e5f1c1eeb46cb7f059 -->
```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>Theip ar %s an staid snapshot -assumeutxo a bhailíochtú. Léiríonn sé seo fadhb crua-earraí, nó fabht sna bogearraí, nó droch-mhodhnú bogearraí a cheadaigh pictiúr neamhbhailí a luchtú. Mar thoradh air seo, stopfar an nód agus stopfaidh sé de úsáid a bhaint as staid ar bith a tógadh ar an seat, ag athshocrú airde an tslabhra ó%dgo%d. Ar an gcéad atosú eile, athchromfar ar an nód ag sioncronú ó %d gan úsáid a bhaint as sonraí seat. Tuairiscigh an teagmhas seo do %s lena n-áirítear conas a fuair tú an pictiúr. Fágfar an slabhrashlabhra neamhbhailí ar an diosca ar eagla go mbeadh sé ina chuidiú leis an tsaincheist ba chúis leis an earráid seo a dhiagnóisiú.</translation>
    
ERR
There are several issues with the translation:

1. The word "snapshot" is inconsistently translated as both "snapshot", "pictiúr", and "seat", which is confusing and does not clearly refer to the Bitcoin-specific concept.
2. The format specifiers `%d` are merged as `%dgo%d` instead of having spaces ("ó%d go %d").
3. The language is at times stilted, and there is inconsistent terminology: "pictiúr" means "picture" and is incorrect in the context of "snapshot" in Bitcoin; "seat" is also incorrect. "Staid snapshot" and "slabhrashlabhra" are problematic compounds.
4. The word "chainstate" is translated as "slabhrashlabhra", which is a concatenation and not idiomatic Irish.
5. Whitespace is missing (e.g., "ó%dgo%d").
6. The overall translation is not consistent or clear in Bitcoin context.

Correct translation:

The correct translation should keep "snapshot" in English or use "grianghraf" only if widely understood in Bitcoin Irish context (it's not). Usually, English terms are retained for such technical words.

Correct translation:
Theip ar %s bailíochtú staid shnáithín -assumeutxo. Léiríonn sé seo fadhb le crua-earraí, nó fabht sa bhogearra, nó droch-mhodhnú bogearraí a cheadaigh snapshot neamhbhailí a luchtú. Mar thoradh air seo, dúnfar an nód agus stopfaidh sé d'úsáid ar aon staid a tógadh bunaithe ar an snapshot, agus athshocrófar airde an chroíshlabhra ó %d go %d. Ar an gcéad atosú eile, cuirfear ar aghaidh an sioncrónú ón %d gan aon sonraí ó snapshot a úsáid. Cuir an eachtra seo in iúl do %s, agus mínigh conas a fuair tú an snapshot. Fágfar an chainstate neamhbhailí ar an diosca le go mbeidh sé cabhrach chun an fhadhb a aithint a ba chúis leis an earráid seo.

Notes:
- "snapshot" and "chainstate" are likely best left in English for clarity unless there are established Irish terms within the Bitcoin Irish-speaking community.
- Spaces and format specifiers are fixed.
- The translation now directly refers to the Bitcoin context without confusion.
```

<!-- cache_translation_check_ga_IE_947364c9282f5a2577c87bdaf9f80759633b54d25263b010f3c7ac7f5fcc5dfe -->
```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Earráid agus%s á léamh! Seans go bhfuil sonraí idirbhirt in easnamh nó mícheart. Sparán athscanadh.</translation>
    
ERR
The translation omits key details, notably "Got "%s", expected "format"." The inclusion of "agus%s á léamh" is unnatural and does not correctly convey the format error message. The phrase about missing or incorrect transaction data and rescanning the wallet does not directly match the source.

Correct translation:
Earráid: Tá an taifead formáide sa chomhad dumpála mícheart. Fuarthas "%s", "format" a bhí súil leis.
```

<!-- cache_translation_check_ga_IE_c86d8460c3c2fe7445b3e7a14d9be7c1a79b19372c8470040ee2dfdeec6e4046 -->
```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Is é seo an táille idirbhirt a fhéadfaidh tú cuileáil má tá sóinseáil níos lú ná dusta ag an leibhéal seo</translation>
    
ERR
The word "cuileáil" is not standard Irish and is likely an erroneous or non-existent term. The standard translation for "discard" in this context would be "a chur i leataobh" or "a dhiúltú". Also, "sóinseáil" is correctly used for "change", and "dusta" for "dust" is fine in the technical context. The rest of the sentence is mostly appropriate but could be smoother.

Correct translation:
Is é seo an táille idirbhirt ar féidir leat a chur i leataobh má tá an tsóinseáil níos lú ná an dusta ag an leibhéal seo
```

<!-- cache_translation_check_ga_IE_f504ed46fb4ff727b26d2aeeb8d2cafc4e599f7b7a296e208c0a1f7dc7ce8217 -->
```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Leibhéal logála catagóir ar leith nach dtacaítear leis %1$s=%2$s. Bhíothas ag súil le %1$s=1:2. Catagóirí bailí: %3$s. Leibhéil loga bailí: %4$s.</translation>
    
ERR
The translation is mostly accurate but has some issues:

1. The expected format in the source string is "%1$s=<category>:<loglevel>", but the translation uses "%1$s=1:2" which is not correct and loses the original meaning.
2. The word "logála" should be "loga" for consistency with the later usage ("Leibhéil loga bailí").
3. Otherwise, format specifiers are transferred and spacing is correct.

Correct translation:
Leibhéal loga catagóire nach dtacaítear leis %1$s=%2$s. Bhíothas ag súil le %1$s=&lt;category&gt;:&lt;loglevel&gt;. Catagóirí bailí: %3$s. Leibhéil loga bailí: %4$s.
```

<!-- cache_translation_check_ga_IE_5a7ca5491283f4091b358b2981bc1150c962c5a2e00cd01ddf8ba0a3b58f9eaf -->
```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>Theip ar bhaint an tsainstáit seat seat (%s). Bain de láimh é roimh atosú.
</translation>
    
ERR
There is an issue with the translation: "theip ar bhaint an tsainstáit seat seat"—the phrase "seat seat" is a duplication and appears nonsensical in Irish. Also, "chainstate" should be translated more clearly, and the terminology for "snapshot" and "chainstate" in Irish Bitcoin contexts should ideally be closer to the English where there is no established equivalent.

Correct translation:
Theip ar bhaint eolaire chainstate seataispeána (%s). Bain de láimh é roimh atosú.

Or if "chainstate" and "snapshot" have no commonly used Irish translations, retain them:
Theip ar bhaint an eolaire snapshot chainstate (%s). Bain de láimh é roimh atosú.
```

<!-- cache_translation_check_ga_IE_b81bf190e2c953b057a8009302249823c6d2b560166be8879dcaeab06cc90140 -->
```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>Naisc amach teoranta do Tor (-onlynet=onion) ach ní thugtar an seachfhreastalaí chun líonra Tor a bhaint amach: ní thugtar aon seachfhreastalaí, -oinniún nó -listenonion</translation>
    
ERR
The translation omits some technical and important details from the source, specifically the list of options "-proxy, -onion or -listenonion". Instead, it paraphrases and introduces the term "seachfhreastalaí" (proxy) more than once, and translates "-onion" as "-oinniún", which, while literally meaning "onion" in Irish, may not be recognized in context as the Tor network flag; the convention is usually to keep such command-line flags untranslated.

Correct translation:
Naisc amach teoranta do Tor (-onlynet=onion) ach níor tugadh an seachfhreastalaí chun fáil ar an líonra Tor: níl aon cheann de -proxy, -onion ná -listenonion curtha ar fáil
```

<!-- cache_translation_check_ga_IE_4bec6bad37ef89b268c16f13a39776bba13c5ff1668c4616df327920d3a02ff0 -->
```
        <source>whitebind may only be used for incoming connections ("out" was passed)</source>
        <translation>ní féidir ceangaltán bán a úsáid ach amháin le haghaidh naisc isteach (ritheadh ​​​​"amach")</translation>
    
ERR
The translation is largely accurate semantically, but the term "ceangaltán bán" for "whitebind" is a nonstandard calque and might be confusing in technical context. Also, the translation of ("out" was passed) as (ritheadh ​​​​"amach") is unclear, especially since "out" is in English in the message (should match the source).

A more natural and technically precise translation would be:
Ní féidir "whitebind" a úsáid ach amháin le haghaidh naisc isteach (ritheadh "out").
```

<!-- cache_translation_check_ga_IE_4347b2017571d921c0634e3d36c70a104e6beeb34e22c5bd370fcbf260d017ac -->
```
        <source>Error: Not all transaction records were migrated</source>
        <translation>Earráid: Níor aistríodh gach taifead idirbhirt</translation>
    
ERR
The Irish contains a grammatical/spelling issue: "taifead idirbhirt" is incorrect (singular/plural and misspelling). 

Correct translation:
Earráid: Níor aistríodh na taifid idirbhearta go léir.
```

<!-- cache_translation_check_ga_IE_cd1dd3527f0e92514235321e9324aa0d4fd7756d14f33841bf85ee04a3bbb82c -->
```
        <source>Failed to acquire rescan reserver during wallet initialization</source>
        <translation>Theip ar an gcuntar athscanála a fháil le linn thúsú an sparáin.</translation>
    
ERR
The Irish contains grammatical issues and uses incorrect/mistranslated words (e.g. "gcuntar" is not appropriate here, and "thúsú" is mis-inflected). No format specifiers are present in the source.

Suggested correct translation:
Theip ar fháil ar an áirithint athscanála le linn túsúcháin an sparáin.
```

<!-- cache_translation_check_ga_IE_8cb67c974c57c1e4bedbcb4ce22e5d049a8dfac2d2510af05ca75f3d1c673e22 -->
```
        <source>Failed to close block undo file.</source>
        <translation>Theip ar chomhad cealaithe bloc a dhúnadh.</translation>
    
ERR
The Irish translation has incorrect word order and missing definite article/lenition. The structure should place the noun phrase with the article before "a dhúnadh".

Correct translation:
Theip ar an chomhad cealaithe bhloc a dhúnadh.
```

<!-- cache_translation_check_ga_IE_43ec6c34685263727061ab78e2ede20e6559b25c31d0580924e8fcab5368f998 -->
```
        <source>Listening for incoming connections failed (listen returned error %s)</source>
        <translation>Theip ar éisteacht le naisc isteach (éisteacht ar ais earráid %s)</translation>
    
ERR
The translation is understandable but not entirely accurate or idiomatic in Irish. "Theip ar éisteacht le naisc isteach" awkwardly combines English structure and literal elements. Also, "éisteacht ar ais earráid %s" is not idiomatic; it should be clearer that "listen" is a function returning an error.

Correct translation:
Theip ar éisteacht le haghaidh naisc isteach (d’fhill listen earráid %s)
```

<!-- cache_translation_check_ga_IE_dec7998ca31ae8acb001b5aff9eafa634b1b89c24b7e386fe93af29f78250e6a -->
```
        <source>Prune cannot be configured with a negative value.</source>
        <translation>Ní féidir Bearradh a bheidh cumraithe le luach diúltach.</translation>
    
ERR
The Irish (ga_IE) translation is understandable but slightly awkward. The construction "Bearradh a bheidh cumraithe le luach diúltach" is not idiomatic. It would be better rendered as: "Ní féidir bearradh a chumrú le luach diúltach."

Correct translation:
Ní féidir bearradh a chumrú le luach diúltach.
```

<!-- cache_translation_check_ga_IE_a6a3f9ec960fda9d62350b2b039dd41dff2bbbfdb3943cc5f7189c83b4fcd7bf -->
```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>Rialacha nua anaithnid curtha i ngníomh (leagan giotán %ii)</translation>
    
ERR
There are two issues:
1. The format specifier is incorrectly copied. Source has '%i', but translation has '%ii' (double 'i'), which is an error.
2. Otherwise, the translation is generally accurate.

Correct translation:
Rialacha nua anaithnid curtha i ngníomh (versionbit %i)
or a more natural version:
Rialacha nua anaithnid curtha i ngníomh (giotán leagain %i)
```

<!-- cache_translation_check_ga_IE_df4c6195232e85a952814c6bc3ed73835a2d24ea754dd9967f025eac15d60328 -->
```
        <source>Transaction requires one destination of non-zero value, a non-zero feerate, or a pre-selected input</source>
        <translation>Éilíonn an t-idirbheart ceann scríbe amháin de luach neamh-nialas, ráta táille neamh-nialas, nó ionchur réamhroghnaithe.</translation>
    
ERR
Minor grammatical issues and an extraneous period. The phrase "neamh-nialas" is unnatural in Irish — use "neamh-niallach", and the translation added a trailing full stop although the source has none.

Suggested correction:
Éilíonn an t-idirbheart ceann scríbe amháin le luach neamh-niallach, ráta táille neamh-niallach, nó ionchur réamhroghnaithe
```

<!-- cache_translation_check_ga_IE_4cf143335aa11abf8cbabffea1d89243fd56b8adad2601000e7f604008d59ccd -->
```
        <source>Unrecognized descriptor found. Loading wallet %s

The wallet might have been created on a newer version.
Please try running the latest software version.
</source>
        <translation>Tuairisceoir anaithnid aimsithe. Ag luchtú sparán %s

B’fhéidir gur cruthaíodh an sparán ar leagan níos nuaí.
Déan iarracht an leagan bogearraí is déanaí a rith.
</translation>
    
ERR
The word "tuairisceoir" usually means "reporter" (a person) and is not the best choice for the technical term "descriptor". Use "tuairisc" or "cur síos" for "descriptor". Otherwise the %s and spacing are fine.

Correct translation suggestion:
Tuairisc anaithnid aimsithe. Ag luchtú an sparáin %s

B’fhéidir gur cruthaíodh an sparán ar leagan níos nuaí.
Déan iarracht an leagan bogearraí is déanaí a rith.
```

<!-- cache_translation_check_ga_IE_afcb7dfe4ed7569b2d949652843094743dba5cd903f974894dcc322fac91002b -->
```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Earráid: Níorbh fhéidir watch amháin tx %s a chur le sparán faire amháin</translation>
    
ERR
The translation mixes English with Irish (e.g., "watch amháin tx" instead of a proper translation for "watchonly tx"), and does not handle "watchonly" as a consistent term. Also, "sparán faire amháin" is awkward; the standard translation for "watch-only wallet" is usually "sparán faire" or "sparán faire amháin" if strictly literal, but the English word "tx" for "transaction" should also be translated.

Correct translation:
Earráid: Níorbh fhéidir an t-idirbheart faire amháin %s a chur le sparán faire amháin
```

<!-- cache_translation_check_ga_IE_24b6754689011842413d0f255bd5803beb2efaa3f543d42cbb82728b22089950 -->
```
        <source>Invalid -proxy address or hostname, ends with '=': '%s'</source>
        <translation>Seoladh nó ainm óstach neamhbhailí -proxy, críochnaíonn le '=': '%s'</translation>
    
ERR
The Irish phrasing is slightly awkward/ungrammatical and the placement of "-proxy" would be clearer earlier. Also add a subject for "críochnaíonn" or use a relative form.

Suggested correction:
Seoladh -proxy nó ainm óstach neamhbhailí; críochnaíonn sé le '=': '%s'
```
</details>

Number of issues: 45.
