# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ga_IE</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bga_IE%5D%20low%20quality)


```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
YES
The translation "Comhad athróige camógdheighilte" is problematic. "Comhad athróige" translates as "variable file", which is incorrect. The standard and accepted Irish translation for "Comma separated file" (as used for "CSV") is "Comhad camógscartha" or "Comhad camóg deighilte".

Correct translation:
Comhad camógscartha

Alternatively (less common, but accurate):
Comhad camóg-deighilte
```

```
        <source>%1 d</source>
        <translation>%1 l</translation>
    
YES
The English source uses '%1 d', where 'd' likely stands for 'days'. The translation '%1 l' is using 'l', which does not correspond to the Irish abbreviation for 'days'. The correct Irish abbreviation is 'la' or 'lá' for 'day', but abbreviations are less commonly used in Irish than in English. For plural, 'lá' is 'laethanta', but abbreviation is typically 'lá'.

Correct translation:
%1 lá
```

```
        <source>%1 m</source>
        <translation>%1 n</translation>
    
YES
The translation is problematic. The source uses "m" (likely for "minutes"), but the translation uses "n", which does not correspond to "minutes" in Irish. The correct abbreviation for "minute" in Irish is "nóim" or sometimes simply "n".

However, if the style demands an abbreviation, the Irish standard is "nóim" for minutes. Single-letter "n" might not be widely understood. For best clarity and standardization, "nóim" should be used.

Correct translation:
%1 nóim
```

```
        <source>Show the list of used sending addresses and labels</source>
        <translation>Taispeáin an liosta de seoltaí seoladh úsáidte agus na lipéid </translation>
    
YES
The phrase "seoltaí seoladh úsáidte" is incorrect and redundant; "sending addresses" should be "seoltaí seolta" or more accurately "seoltaí seolta amach". There is also an unnecessary space at the end.

Correct translation:
Taispeáin an liosta de sheoltaí seolta amach a úsáideadh agus na lipéid
```

```
        <source>Sending addresses</source>
        <translation>Seoltaí seoladh</translation>
    
YES
The translation "Seoltaí seoladh" is incorrect. "Seoltaí" means "sent (plural noun form)" and "seoladh" means "address". This is confusing and ungrammatical. The correct Irish (ga_IE) translation for "Sending addresses" would be:

Seoltaí seolta

Alternatively, to make it more natural and in context: "Seoltaí seolta" or "Seoltaí seoladh" (but "Seoltaí seolta" matches "sending addresses" (plural)). However, the most accurate option with current convention is:

Seoltaí seolta

Correct translation:
Seoltaí seolta
```

```
        <source>%1 client</source>
        <translation>%1 cliaint</translation>
    
YES
The translation uses "cliaint" for "client", which is an incorrect spelling in Irish. The correct word is "cliant". There are no issues with the format specifier.

Correct translation:
%1 cliant
```

```
        <source>Show</source>
        <translation>Sconas</translation>
    
YES
The translation "Sconas" is incorrect for "Show" in Irish (ga_IE). "Sconas" is not the correct word for "Show." 

Correct translation:
Taispeáin
```

```
        <source>(un)select all</source>
        <translation>(neamh)roghnaigh gach rud </translation>
    
YES
The translation "(neamh)roghnaigh gach rud" is understandable, but there is a spelling issue and an unnecessary trailing space. "Neamhroghnaigh" is not standard usage; the usual negation for "roghnaigh" is "díroghnaigh".

Correct translation:
(Roghnaigh/Díroghnaigh) gach rud
```

```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
YES
There is a spelling error in the Irish translation. "Cóipeáíl" should be "Cóipeáil", and "sóinseáil" is a non-standard rendering for "change" in the Bitcoin context—usually "athrú" is used for "change" (as in transaction change).

Correct translation:
Cóipeáil athrú
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>An seoladh chomhcheangailte leis an iontráil liosta seoltaí seo. Ní féidir é seo a mionathraithe ach do seoltaí seoladh.</translation>
    
YES
The translation is problematic: "do seoltaí seoladh" is incorrect (looping translation: "for sending addresses" seems to be translated as "for sending addresses address"). Also, "mionathraithe" is not commonly used for "modified"; "athrú" is preferred. The rest of the translation is generally accurate, but the problematic segment renders it unnatural.

Correct translation:
An seoladh atá bainteach leis an iontráil seo sa liosta seoltaí. Ní féidir é seo a athrú ach do sheoltaí seolta.
```

```
        <source>New sending address</source>
        <translation>Seoladh nua seoladh</translation>
    
YES
The translation repeats the word "seoladh" (address) unnecessarily, resulting in "address new address". The correct translation should be:

Seoladh nua seolta

Or more idiomatically:

Seoladh nua chun seolta
```

```
        <source>Edit sending address</source>
        <translation>Eagarthóireacht seoladh seoladh</translation>
    
YES
The translation is problematic. "Eagarthóireacht seoladh seoladh" is incorrect; it redundantly repeats the word "seoladh" (address) and does not accurately convey the meaning of "Edit sending address." The proper translation should be "Cuir in eagar seoladh seolta" or "Cuir in eagar an seoladh seolta" (if "the sending address" is meant). 

Correct translation:
Cuir in eagar seoladh seolta
```

```
        <source>Estimated time left until synced</source>
        <translation>Measta am fágtha go dtí sioncrónaithe</translation>
    
YES
The translation is inaccurate and unidiomatic. "Measta am fágtha go dtí sioncrónaithe" does not convey the intended meaning clearly in Irish. The phrase "go dtí sioncrónaithe" is awkward and would more naturally be rendered as "go dtí go mbeidh sioncrónaithe" or "go dtí go mbeidh sé sioncrónaithe". Also, "Measta am fágtha" is not idiomatic; "Am measta fágtha" or "Am fágtha measta" is better.

Correct translation:
Am fágtha measta go dtí go mbeidh sé sioncrónaithe
```

```
        <source>Mapped AS</source>
        <translation>CU Mapáilte</translation>
    
YES
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

```
        <source>detecting: peer could be v1 or v2</source>
        <extracomment>Explanatory text for "detecting" transport type.</extracomment>
        <translation>bhrath: d’fhéadfadh v1 nó v2 a bheith i gcomhghleacaí</translation>
    
YES
The translation is problematic. The Irish word "bhrath" does not adequately correspond to "detecting" as a verbal noun or present participle here; it looks like a noun form ("betrayal" or "notice/observation") with wrong mutation. The rest of the translation generally conveys the message but could be clearer.

Correct translation:
"Ag braiteadh: d’fhéadfadh v1 nó v2 a bheith i gcomhghleacaí"
```

```
        <source>Copy change</source>
        <translation>Cóipeáíl sóinseáil</translation>
    
YES
There is a spelling error in the Irish translation. "Cóipeáíl" should be "Cóipeáil", and "sóinseáil" is a non-standard rendering for "change" in the Bitcoin context—usually "athrú" is used for "change" (as in transaction change).

Correct translation:
Cóipeáil athrú
```

```
        <source>Increase transaction fee</source>
        <translation>Méadaigh idirbheart  táille</translation>
    
YES
There is an erroneous extra space between "idirbheart" and "táille", and the word order is unnatural in Irish. The correct translation should be:

Méadaigh an táille idirbheart

This translates as "Increase the transaction fee", which matches the intent of the source.
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comhad athróige camógdheighilte</translation>
    
YES
The translation "Comhad athróige camógdheighilte" is problematic. "Comhad athróige" translates as "variable file", which is incorrect. The standard and accepted Irish translation for "Comma separated file" (as used for "CSV") is "Comhad camógscartha" or "Comhad camóg deighilte".

Correct translation:
Comhad camógscartha

Alternatively (less common, but accurate):
Comhad camóg-deighilte
```

```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>Cóipeáil PSBT bump táille chuig an ngearrthaisce</translation>
    
YES
The translation is problematic. The sentence incorrectly uses the infinitive ("Cóipeáil") rather than the past tense, and "bump táille" is not a natural or clear expression in Irish for "fee-bump". The translation should more accurately reflect the English source, especially the phrase "Fee-bump PSBT copied to clipboard".

Correct translation:
PSBT ardaithe táille cóipeáilte chuig an ngearrthaisce
```

```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>Theip ar %s an staid snapshot -assumeutxo a bhailíochtú. Léiríonn sé seo fadhb crua-earraí, nó fabht sna bogearraí, nó droch-mhodhnú bogearraí a cheadaigh pictiúr neamhbhailí a luchtú. Mar thoradh air seo, stopfar an nód agus stopfaidh sé de úsáid a bhaint as staid ar bith a tógadh ar an seat, ag athshocrú airde an tslabhra ó%dgo%d. Ar an gcéad atosú eile, athchromfar ar an nód ag sioncronú ó %d gan úsáid a bhaint as sonraí seat. Tuairiscigh an teagmhas seo do %s lena n-áirítear conas a fuair tú an pictiúr. Fágfar an slabhrashlabhra neamhbhailí ar an diosca ar eagla go mbeadh sé ina chuidiú leis an tsaincheist ba chúis leis an earráid seo a dhiagnóisiú.</translation>
    
YES
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

```
        <source>Cannot downgrade wallet from version %i to version %i. Wallet version unchanged.</source>
        <translation>Ní féidir an sparán a íosghrádú ó leagan %igo leagan%i. Leagan sparán gan athrú.</translation>
    
YES
There is a formatting issue with the space around the format specifiers %i. In the source, there are spaces before and after %i ("from version %i to version %i"), but in the translation, the spaces are missing ("ó leagan %igo leagan%i"). This could result in "leagan1go leagan2", which is incorrect.

Correct translation:
Ní féidir an sparán a íosghrádú ó leagan %i go leagan %i. Leagan sparán gan athrú.
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>Ní féidir sparán scoilte neamh-HD a uasghrádú ó leagan%igo leagan%i gan uasghrádú chun tacú le heochrach réamh-scoilte. Úsáid leagan %i nó níl aon leagan sonraithe.</translation>
    
YES
There are several issues:
1. Format specifiers "%i" are not spaced correctly in Irish; there should be a space before and after in the running text, following the source (e.g. 'leagan%igo' should be 'leagan %i go').
2. "heochrach réamh-scoilte" is mistranslation. "Keypool" is typically left untranslated or more specifically rendered; "réamh-scoilte" means "pre-split" but the phrase is awkward here.
3. "no version specified" — "nó níl aon leagan sonraithe" could be more clearly: "nó gan leagan ar bith sonraithe".
4. Minor wording issues and some ambiguity in "tacú le heochrach réamh-scoilte".

Correct translation:
Ní féidir sparán scoilte neamh-HD a uasghrádú ó leagan %i go leagan %i gan uasghrádú chun tacú le pre-split keypool. Úsáid leagan %i nó gan leagan ar bith sonraithe.
```

```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Earráid agus%s á léamh! Seans go bhfuil sonraí idirbhirt in easnamh nó mícheart. Sparán athscanadh.</translation>
    
YES
The translation omits key details, notably "Got "%s", expected "format"." The inclusion of "agus%s á léamh" is unnatural and does not correctly convey the format error message. The phrase about missing or incorrect transaction data and rescanning the wallet does not directly match the source.

Correct translation:
Earráid: Tá an taifead formáide sa chomhad dumpála mícheart. Fuarthas "%s", "format" a bhí súil leis.
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Is é seo an táille idirbhirt a fhéadfaidh tú cuileáil má tá sóinseáil níos lú ná dusta ag an leibhéal seo</translation>
    
YES
The word "cuileáil" is not standard Irish and is likely an erroneous or non-existent term. The standard translation for "discard" in this context would be "a chur i leataobh" or "a dhiúltú". Also, "sóinseáil" is correctly used for "change", and "dusta" for "dust" is fine in the technical context. The rest of the sentence is mostly appropriate but could be smoother.

Correct translation:
Is é seo an táille idirbhirt ar féidir leat a chur i leataobh má tá an tsóinseáil níos lú ná an dusta ag an leibhéal seo
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Leibhéal logála catagóir ar leith nach dtacaítear leis %1$s=%2$s. Bhíothas ag súil le %1$s=1:2. Catagóirí bailí: %3$s. Leibhéil loga bailí: %4$s.</translation>
    
YES
The translation is mostly accurate but has some issues:

1. The expected format in the source string is "%1$s=<category>:<loglevel>", but the translation uses "%1$s=1:2" which is not correct and loses the original meaning.
2. The word "logála" should be "loga" for consistency with the later usage ("Leibhéil loga bailí").
3. Otherwise, format specifiers are transferred and spacing is correct.

Correct translation:
Leibhéal loga catagóire nach dtacaítear leis %1$s=%2$s. Bhíothas ag súil le %1$s=&lt;category&gt;:&lt;loglevel&gt;. Catagóirí bailí: %3$s. Leibhéil loga bailí: %4$s.
```

```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>Theip ar bhaint an tsainstáit seat seat (%s). Bain de láimh é roimh atosú.
</translation>
    
YES
There is an issue with the translation: "theip ar bhaint an tsainstáit seat seat"—the phrase "seat seat" is a duplication and appears nonsensical in Irish. Also, "chainstate" should be translated more clearly, and the terminology for "snapshot" and "chainstate" in Irish Bitcoin contexts should ideally be closer to the English where there is no established equivalent.

Correct translation:
Theip ar bhaint eolaire chainstate seataispeána (%s). Bain de láimh é roimh atosú.

Or if "chainstate" and "snapshot" have no commonly used Irish translations, retain them:
Theip ar bhaint an eolaire snapshot chainstate (%s). Bain de láimh é roimh atosú.
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>Naisc amach teoranta do Tor (-onlynet=onion) ach ní thugtar an seachfhreastalaí chun líonra Tor a bhaint amach: ní thugtar aon seachfhreastalaí, -oinniún nó -listenonion</translation>
    
YES
The translation omits some technical and important details from the source, specifically the list of options "-proxy, -onion or -listenonion". Instead, it paraphrases and introduces the term "seachfhreastalaí" (proxy) more than once, and translates "-onion" as "-oinniún", which, while literally meaning "onion" in Irish, may not be recognized in context as the Tor network flag; the convention is usually to keep such command-line flags untranslated.

Correct translation:
Naisc amach teoranta do Tor (-onlynet=onion) ach níor tugadh an seachfhreastalaí chun fáil ar an líonra Tor: níl aon cheann de -proxy, -onion ná -listenonion curtha ar fáil
```

```
        <source>whitebind may only be used for incoming connections ("out" was passed)</source>
        <translation>ní féidir ceangaltán bán a úsáid ach amháin le haghaidh naisc isteach (ritheadh ​​​​"amach")</translation>
    
YES
The translation is largely accurate semantically, but the term "ceangaltán bán" for "whitebind" is a nonstandard calque and might be confusing in technical context. Also, the translation of ("out" was passed) as (ritheadh ​​​​"amach") is unclear, especially since "out" is in English in the message (should match the source).

A more natural and technically precise translation would be:
Ní féidir "whitebind" a úsáid ach amháin le haghaidh naisc isteach (ritheadh "out").
```

```
        <source>Listening for incoming connections failed (listen returned error %s)</source>
        <translation>Theip ar éisteacht le naisc isteach (éisteacht ar ais earráid %s)</translation>
    
YES
The translation is understandable but not entirely accurate or idiomatic in Irish. "Theip ar éisteacht le naisc isteach" awkwardly combines English structure and literal elements. Also, "éisteacht ar ais earráid %s" is not idiomatic; it should be clearer that "listen" is a function returning an error.

Correct translation:
Theip ar éisteacht le haghaidh naisc isteach (d’fhill listen earráid %s)
```

```
        <source>Prune cannot be configured with a negative value.</source>
        <translation>Ní féidir Bearradh a bheidh cumraithe le luach diúltach.</translation>
    
YES
The Irish (ga_IE) translation is understandable but slightly awkward. The construction "Bearradh a bheidh cumraithe le luach diúltach" is not idiomatic. It would be better rendered as: "Ní féidir bearradh a chumrú le luach diúltach."

Correct translation:
Ní féidir bearradh a chumrú le luach diúltach.
```

```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>Rialacha nua anaithnid curtha i ngníomh (leagan giotán %ii)</translation>
    
YES
There are two issues:
1. The format specifier is incorrectly copied. Source has '%i', but translation has '%ii' (double 'i'), which is an error.
2. Otherwise, the translation is generally accurate.

Correct translation:
Rialacha nua anaithnid curtha i ngníomh (versionbit %i)
or a more natural version:
Rialacha nua anaithnid curtha i ngníomh (giotán leagain %i)
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Earráid: Níorbh fhéidir watch amháin tx %s a chur le sparán faire amháin</translation>
    
YES
The translation mixes English with Irish (e.g., "watch amháin tx" instead of a proper translation for "watchonly tx"), and does not handle "watchonly" as a consistent term. Also, "sparán faire amháin" is awkward; the standard translation for "watch-only wallet" is usually "sparán faire" or "sparán faire amháin" if strictly literal, but the English word "tx" for "transaction" should also be translated.

Correct translation:
Earráid: Níorbh fhéidir an t-idirbheart faire amháin %s a chur le sparán faire amháin
```
</details>

Number of issues: 32.
