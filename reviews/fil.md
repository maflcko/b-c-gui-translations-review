# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>fil</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bfil%5D%20low%20quality)


```
        <source>Copy</source>
        <translation>gayahin</translation>
    
YES
The translation "gayahin" means "to imitate" or "imitate", which is incorrect in this context. The correct translation for "Copy" (as in the command to copy text or data) in Filipino is "Kopyahin".

Correct translation:
Kopyahin
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>I-exporte yung datos sa kasalukuyang tab doon sa pila</translation>
    
YES
The translation contains several issues:
1. "I-exporte" is an incorrect borrowing. In Filipino, "I-export" is commonly used.
2. "yung" is informal; "ang" is the standard.
3. "doon sa pila" is inaccurate. "pila" means "queue" or "line", which does not correspond to "file". The correct term for "file" is "file" (as a borrowing) or "talaksan".

Correct translation:
I-export ang datos sa kasalukuyang tab papunta sa file
```

```
        <source>%1 and %2</source>
        <translation>%1 at %2</translation>
    
YES
The translation incorrectly uses "at" instead of the correct Filipino conjunction "at" for "and". "%1 at %2" is actually correct, so the translation is already accurate and not problematic. However, if the format specifier handling was the concern (expecting translation), no correction is needed.

NO
```

```
        <source>default wallet</source>
        <translation>walet na default</translation>
    
YES
The translation "walet na default" is awkward and not idiomatic in Filipino. The word "walet" is just a phonetic borrowing with non-standard spelling; the common translation is "pitaka". Also, "default" is better rendered as "pangunahing" or "default" if commonly used in context. The correct translation would be:

Correct translation:
pangunahing pitaka

or, if technical jargon is accepted:

default na pitaka
```

```
        <source>About %1</source>
        <translation>Mga %1</translation>
    
YES
The translation "Mga %1" is inaccurate. The English phrase "About %1" (where %1 is a variable) is typically used to indicate approximation (e.g., "About 5"), and should be translated as "Tungkol sa %1" or "Mga %1" if referring to an approximate number. However, "Mga %1" alone is ambiguous and could be misunderstood. The most natural and context-appropriate translation in Filipino is "Tinatayang %1" or "Mga %1" if used before a number, but "Tungkol sa %1" is more literal for "About %1" in contexts such as "About Bitcoin".

Correct translation:
Tungkol sa %1
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Ang proxy ay &lt;b&gt;in-inable&lt;/b&gt;: %1</translation>
    
YES
The translation uses "in-inable," which is a transliteration of "enabled" rather than a proper Filipino equivalent. A more accurate translation would use "pinagana" for "enabled." Also, there are no whitespace or format specifier issues.

Correct translation:
Ang proxy ay &lt;b&gt;pinagana&lt;/b&gt;: %1
```

```
        <source>Settings</source>
        <translation>Setting</translation>
    
YES
The translation "Setting" is incorrect because "Setting" is in English and should be in Filipino. The correct Filipino translation for "Settings" is "Mga Setting" (commonly used), or more formally "Mga Pagkakaayos" or "Mga Talaan ng Ayos", but "Mga Setting" is widely accepted in contemporary usage in the Philippines.

Correct translation:
Mga Setting
```

```
        <source>Date: %1
</source>
        <translation>Datiles: %1
</translation>
    
YES
The word "Datiles" is incorrect in Filipino/Tagalog; it is a misspelling and in fact means "dates" as in the fruit ("datiles"). The correct translation for "Date" (as in a calendar date) in Filipino is "Petsa".

Correct translation:
Petsa: %1
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Ang pitaka ay &lt;b&gt;na-enkriptuhan&lt;/b&gt; at kasalukuyang &lt;b&gt;naka-lock&lt;/b&gt;</translation>
    
YES
The translation is problematic. The source says the wallet is "currently unlocked" but the translation says "kasalukuyang naka-lock", which means "currently locked". This is the opposite of the intended meaning.

Correct translation:
Ang pitaka ay &lt;b&gt;na-enkriptuhan&lt;/b&gt; at kasalukuyang &lt;b&gt;naka-unlock&lt;/b&gt;
```

```
        <source>After Fee:</source>
        <translation>Bayad sa pagtapusan:</translation>
    
YES
The translation "Bayad sa pagtapusan:" is not a correct or idiomatic translation for "After Fee:" in the context of Bitcoin. "Pagtapusan" is not a standard Tagalog word for "after" in this context; it is more likely a regional or misspelled term, and its usage is ungrammatical in formal Filipino. The phrasing is awkward, and the translation might confuse native speakers.

Correct translation:
"Pagkatapos ng Bayad:" or "Pagkatapos ng Fee:" (if retaining the English term "fee" as is sometimes common in Filipino financial contexts).

So:

Pagkatapos ng Bayad:
```

```
        <source>Date</source>
        <translation>Datiles</translation>
    
YES
The translation is erroneous. "Datiles" in Filipino means "dates" as in the fruit, not the calendar date. The correct Filipino translation for "Date" (as in calendar date) is "Petsa".

Correct translation:
Petsa
```

```
        <source>Copy address</source>
        <translation>Kopyahin and address</translation>
    
YES
The translation is incorrect. The conjunction "and" is not correct in Filipino, and "address" should be translated.

Correct translation:
Kopyahin ang address
```

```
        <source>Copy after fee</source>
        <translation>Kopyahin ang after fee</translation>
    
YES
The translation retains the English phrase "after fee" verbatim, which is unnatural and unclear in Filipino. It should be translated properly.

Correct translation:
Kopyahin pagkatapos ng bayad
```

```
        <source>Disable Private Keys</source>
        <translation>Huwag paganahin ang Privbadong susi</translation>
    
YES
There is a typo in the translation: "Privbadong susi" should be "Pribadong susi". Otherwise, the translation is fine.

Correct translation:
Huwag paganahin ang pribadong susi
```

```
        <source>IP address of the proxy (e.g. IPv4: 127.0.0.1 / IPv6: ::1)</source>
        <translation>IP address ng proxy (e.g. IPv4: 127.0.0.1 / IPv6:::1)</translation>
    
YES
The translation retained much of the English text instead of translating it into Filipino. Additionally, there is a formatting issue in the IPv6 example: it should be "::1" not ":::1". For clarity and natural Filipino, some English technical terms may be retained, but the rest should be translated.

Correct translation:
IP address ng proxy (hal. IPv4: 127.0.0.1 / IPv6: ::1)
```

```
        <source>Prune block storage to</source>
        <translation>I-prune and block storage sa</translation>
    
YES
The translation is partially inaccurate. The English phrase "Prune block storage to" is incomplete as a standalone phrase but is likely followed by a number or size specification in the software context (e.g., "Prune block storage to 2 GB"). The Filipino translation doesn't preserve the structure correctly: "I-prune and block storage sa" mixes English and Filipino incorrectly ("and" should be "ang"), and the phrase structure is awkward.

Correct translation:
"I-prune ang imbakan ng block sa"

Or, keeping more English for technical clarity as in the original, a commonly accepted local translation would be:
"I-prune ang block storage sa"

Either is acceptable, but "and" should be corrected to "ang", and the phrase should be smoothed for grammar.
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>Mga naminang balanse na nasa mga watch-only address na hindi pa ligtas gastusin</translation>
    
YES
The translation is mostly accurate but could be slightly improved for clarity. The original specifies "has not yet matured," which means the funds cannot be spent yet (not matured), but the translation uses "hindi pa ligtas gastusin," which literally translates as "not yet safe to spend." Although this conveys a similar meaning, a more precise translation would capture the idea of "not yet matured" or "hindi pa matured/hinog" in the context of Bitcoin.

Correct translation:
Mga naminang balanse sa mga watch-only address na hindi pa matured/hinog

or

Mga naminang balanse sa mga watch-only address na hindi pa maaaring gastusin

Either would closely preserve the meaning. The format specifiers and spacing are correct.
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>Na-activate ang mode ng privacy para sa tab na Pangkalahatang-ideya.  Upang ma-unkkan ang mga halaga, alisan ng check ang Mga Setting-&gt; Mga halaga ng mask.</translation>
    
YES
There are several issues:
1. "Na-activate ang mode ng privacy" is understandable but not very natural. "Na-activate" is borrowed English; "Aktibo na ang privacy mode" or "Naka-activate ang privacy mode" is more idiomatic in Filipino.
2. "Pangkalahatang-ideya" is a correct translation for "Overview", but shouldn’t be hyphenated in common Filipino ("Pangkalahatang ideya").
3. "ma-unkkan" is not a Filipino word. "ma-unkkan" seems to be a mistranslation of "unmask" (should be "ipakita" or "alisin ang pagkakatakip").
4. "Mga Setting-> Mga halaga ng mask." is a garbled translation for "Settings->Mask values". It should be "Mga Setting->Takpan ang mga halaga" or "Mga Setting->Itago ang mga halaga".
5. There is a double space before "Upang".

Correct translation:
Aktibo ang privacy mode para sa tab na Pangkalahatang ideya. Upang ipakita ang mga halaga, alisin ang check sa Mga Setting->Takpan ang mga halaga.
```

```
        <source>Transaction broadcast successfully! Transaction ID: %1</source>
        <translation>%1</translation>
    
YES
The translation is incorrect. It only contains the format specifier "%1" and omits the rest of the message. This results in missing important information and makes the translation unusable.

Correct translation:
Matagumpay na naipadala ang transaksyon! Transaction ID: %1
```

```
        <source>To specify a non-default location of the blocks directory use the '%1' option.</source>
        <translation>Upang tukuyin and non-default na lokasyon ng direktoryo ng mga block, gamitin ang '%1' na opsyon.</translation>
    
YES
There is a small error: "and" should be "ang" in Filipino. Additionally, "blocks directory" would be better translated as "direktoryo ng mga block" or "direktoryo ng mga bloke." The original uses "blocks directory" (with "blocks" in English), but Filipino often adapts this to "mga bloke" or keeps "block" as is for technical accuracy. Also, "non-default na lokasyon" is acceptable, but "hindi default na lokasyon" is more idiomatic.

Correct translation:
Upang tukuyin ang hindi default na lokasyon ng direktoryo ng mga block, gamitin ang '%1' na opsyon.
```

```
        <source>Out:</source>
        <translation>Labas:</translation>
    
YES
The translation is incorrect. "Labas" means "outside" or "exit" in Filipino, but in the context of Bitcoin (transaction directions), "Out" should be translated as "Labas" only if it refers to "Output," but typically for transaction direction it should be "Palabas" (meaning outgoing) or "Lumabas" ("Sent out"). The colon is correctly preserved.

Correct translation:
Palabas:
```

```
        <source>Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>Kopyahin and address</translation>
    
YES
There is an error in the translation: "and" should be "ang" in Tagalog ("and" is English, "ang" is a Tagalog article). Also, "address" should be translated as "address" or "adres" depending on style, but "address" as an English loanword is commonly used in Filipino for technical contexts. The rest of the translation is acceptable.

Correct translation:
Kopyahin ang address
```

```
        <source>Copy address</source>
        <translation>Kopyahin and address</translation>
    
YES
The translation is incorrect. The conjunction "and" is not correct in Filipino, and "address" should be translated.

Correct translation:
Kopyahin ang address
```

```
        <source>Date</source>
        <translation>Datiles</translation>
    
YES
The translation is erroneous. "Datiles" in Filipino means "dates" as in the fruit, not the calendar date. The correct Filipino translation for "Date" (as in calendar date) is "Petsa".

Correct translation:
Petsa
```

```
        <source>After Fee:</source>
        <translation>Bayad sa pagtapusan:</translation>
    
YES
The translation "Bayad sa pagtapusan:" is not a correct or idiomatic translation for "After Fee:" in the context of Bitcoin. "Pagtapusan" is not a standard Tagalog word for "after" in this context; it is more likely a regional or misspelled term, and its usage is ungrammatical in formal Filipino. The phrasing is awkward, and the translation might confuse native speakers.

Correct translation:
"Pagkatapos ng Bayad:" or "Pagkatapos ng Fee:" (if retaining the English term "fee" as is sometimes common in Filipino financial contexts).

So:

Pagkatapos ng Bayad:
```

```
        <source>Copy after fee</source>
        <translation>Kopyahin ang after fee</translation>
    
YES
The translation retains the English phrase "after fee" verbatim, which is unnatural and unclear in Filipino. It should be translated properly.

Correct translation:
Kopyahin pagkatapos ng bayad
```

```
        <source>Warning: Unknown change address</source>
        <translation>Babala: Hindi alamang address ng sukli</translation>
    
YES
The translation "Babala: Hindi alamang address ng sukli" contains an error. The word "alamang" is incorrect in this context; it should be "kilalang" (meaning "known" in Filipino). The proper translation for "Unknown change address" is "Hindi kilalang address ng sukli."

Correct translation:
Babala: Hindi kilalang address ng sukli
```

```
        <source>Subtract fee from amount</source>
        <translation>Ibawas ang bayad mula sa halagaq</translation>
    
YES
There's a typographical error in the word "halagaq" (should be "halaga"). The formatting of the sentence is otherwise fine.

Correct translation:
Ibawas ang bayad mula sa halaga
```

```
        <source>Signatures - Sign / Verify a Message</source>
        <translation>Pirma - Pumirma / Patunayan ang Mensahe</translation>
    
YES
The translation is understandable but not fully accurate. "Signatures" should be "Pirmado" or "Lagda" (more formal/technical). "Sign / Verify a Message" would be better as "Pumirma / Suriin ang Mensahe" or "Pumirma / Patunayan ang isang Mensahe". "Pirma" refers to the noun "signature" rather than the full process/interface described.

Correct translation:
"Pirmado - Pumirma / Suriin ang Mensahe"
```

```
        <source>Copy the current signature to the system clipboard</source>
        <translation>Kopyahin ang kasalukuyang address sa system clipboard</translation>
    
YES
The translation is inaccurate. The English text refers to copying the "current signature," but the translation refers to copying the "current address" ("kasalukuyang address") instead. Also, "address" should be "lagda" or "pirma" for "signature".

Correct translation:
Kopyahin ang kasalukuyang lagda sa system clipboard
```

```
        <source>Date</source>
        <translation>Datiles</translation>
    
YES
The translation is erroneous. "Datiles" in Filipino means "dates" as in the fruit, not the calendar date. The correct Filipino translation for "Date" (as in calendar date) is "Petsa".

Correct translation:
Petsa
```

```
        <source>Date</source>
        <translation>Datiles</translation>
    
YES
The translation is erroneous. "Datiles" in Filipino means "dates" as in the fruit, not the calendar date. The correct Filipino translation for "Date" (as in calendar date) is "Petsa".

Correct translation:
Petsa
```

```
        <source>Copy address</source>
        <translation>Kopyahin and address</translation>
    
YES
The translation is incorrect. The conjunction "and" is not correct in Filipino, and "address" should be translated.

Correct translation:
Kopyahin ang address
```

```
        <source>Date</source>
        <translation>Datiles</translation>
    
YES
The translation is erroneous. "Datiles" in Filipino means "dates" as in the fruit, not the calendar date. The correct Filipino translation for "Date" (as in calendar date) is "Petsa".

Correct translation:
Petsa
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>I-exporte yung datos sa kasalukuyang tab doon sa pila</translation>
    
YES
The translation contains several issues:
1. "I-exporte" is an incorrect borrowing. In Filipino, "I-export" is commonly used.
2. "yung" is informal; "ang" is the standard.
3. "doon sa pila" is inaccurate. "pila" means "queue" or "line", which does not correspond to "file". The correct term for "file" is "file" (as a borrowing) or "talaksan".

Correct translation:
I-export ang datos sa kasalukuyang tab papunta sa file
```

```
        <source>Backup Wallet</source>
        <translation>Backup na walet</translation>
    
YES
The translation is not fully localized; it mixes English and Filipino. "Backup" may be used as a loanword in Filipino, but the correct Filipino translation would use "I-backup" or "Mag-backup", and "wallet" should be "pitaka". 

Correct translation:
I-backup ang pitaka
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Babala: Napansin ang mga private key sa walet { %s} na may mga hindi pinaganang private key</translation>
    
YES
There is a spacing issue in the placeholder "{ %s}". The space between '{' and '%s' should be removed to match the source.

Correct translation:
Babala: Napansin ang mga private key sa walet {%s} na may mga hindi pinaganang private key
```

```
        <source>Cannot resolve -%s address: '%s'</source>
        <translation>Hindi malutas - %s address: ' %s'</translation>
    
YES
There are whitespace format issues: there is an extra space after the hyphen and before %s, and also an extra space inside the quotes before %s. Also, 'address' is untranslated (should be 'address' or 'adres' in Filipino), but either can be acceptable in Filipino technical contexts.

Correct translation:
Hindi malutas -%s address: '%s'
```
</details>

Number of issues: 38.
