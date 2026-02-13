# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>pam</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bpam%5D%20request)


<!-- cache_translation_check_pam_9799f26330f097a59beef6210e832325362bbddd18fa25e15df0fab0c6476f87 -->
```
        <source>Copy &amp;Label</source>
        <translation>Kopyan ing &amp;Label</translation>
    
SPAM
The translation provided is in Kapampangan ('pam' language tag), but "Kopyan ing &Label" actually means "Copy the Label" and uses the particle "ing" which is unique to Kapampangan—so it is likely not spam. However, a deeper check is necessary:

- "Kopyan ing" means "Copy the" in Kapampangan, which seems appropriate.
- The placement of & is preserved exactly once, which is correct.
- Whitespace and format seem correct.

Upon closer inspection, the translation is reasonably appropriate and not in an unrelated language.

Therefore:

NO
```

<!-- cache_translation_check_pam_9b8fdc24229bb0759ad3f4eda51427028b6c6df448654ffe6c438a872790e876 -->
```
        <source>Wallet unlock failed</source>
        <translation>Memali ya ing pamag-unlock king wallet </translation>
    
ERR
There is an issue with the translation:
1. The word "Memali ya ing" translates more as "It failed the ..." but the phrasing is awkward in Kapampangan ('pam') and adds unnecessary words.
2. There is an extra space before the closing tag.
3. The most natural translation for "Wallet unlock failed" would be "E megumpisa ing pamag-unlock king wallet" or simply "E me-unlock ing wallet", meaning "Wallet failed to unlock" or "Wallet was not unlocked."

Correct translation:
E me-unlock ing wallet
```

<!-- cache_translation_check_pam_a0ebfbeb1ce7ca82b5d35919ca394b11a8ff8a5b4a559159d4d3e2d3cec72290 -->
```
        <source>Wallet passphrase was successfully changed.</source>
        <translation>Mi-alilan ne ing passphrase na ning wallet.</translation>
    
ERR
The translation has accuracy issues.

Explanation:
The phrase "Mi-alilan ne ing passphrase na ning wallet." awkwardly renders "was successfully changed" as "Mi-alilan ne", which is not idiomatic in Kapampangan. "Mi-alilan" means "to change", but it does not include the sense of success. The standard and more precise wording should use "me-salikut" or "me-bayu" for "was changed", but to express "successfully changed", "me-salikut yang makatuking pamagobra" or simply "me-salikut ya" could be more natural.

Correct translation:
Me-salikut ya ing passphrase ning wallet.
```

<!-- cache_translation_check_pam_68c80f98c5c4600c2e0fa1d04def3e2cff336b5cb858a1b8615c2ee509428b97 -->
```
        <source>Last received block was generated %1 ago.</source>
        <translation>Ing tatauling block a metanggap,  me-generate ya %1 ing milabas</translation>
    
ERR
The translation has both grammatical issues and the format specifier "%1" is not well integrated. "Ing tatauling block a metanggap" is awkward, and the phrase "me-generate ya %1 ing milabas" is not idiomatic in Kapampangan ('pam'). There is also a spacing issue in "block a metanggap,  me-generate" (double space after the comma).

Correct translation:
Ing pekarulang block a receive, me-generate ya %1 a milabas.
```

<!-- cache_translation_check_pam_467126be6daabeba4026ecc05465dd58fff9bcbd182633ae0c4db5b279bea74b -->
```
        <source>Up to date</source>
        <translation>Makatuki ya king aldo</translation>
    
ERR
The translation "Makatuki ya king aldo" is problematic. "Makatuki" isn't a recognized word in Kapampangan, and "ya king aldo" translates to "today" or "for the day". The phrase "Up to date" in the context of Bitcoin software should convey "latest" or "current", referring to being synchronized with the latest blockchain state.

Correct translation:
Agpang king bayung datos

This means "[It is] according to the latest data", which properly captures "Up to date."
```

<!-- cache_translation_check_pam_d9e5cea769e9be94049ccb599f60a0259c5bddfb109ff044e88a64d397dd82ce -->
```
        <source>Edit receiving address</source>
        <translation>Alilan ya ing address king pamagpadala</translation>
    
ERR
The translation is problematic. "Edit receiving address" refers to editing the address where funds are received, not sent. The translation says "address for sending" ("king pamagpadala"), which is the opposite of what is intended. Also, "alilan" for "edit" is acceptable in some contexts, but "alisan" or "ayusan" may be better for "edit" in Kapampangan (pam).

Correct translation:
Ayusan ya ing address para king pamagpasali

Alternative:
Alilan ya ing address para king pamagpasali

("pamagpasali" means "receiving.")
```

<!-- cache_translation_check_pam_09ae4dcbd3c533909de535326eade592998c1051d2b8233a413b7498e2495844 -->
```
        <source>New key generation failed.</source>
        <translation>Memali ya ing pamangaua king key</translation>
    
ERR
The translation "Memali ya ing pamangaua king key" is inaccurate and awkward. It translates literally to "Failed is the making of key," but in Kapampangan ('pam'), it is more natural and clear to say "Mealbung mag-generate key" or "E meging matagumpe ing pamag-generate ning key." Furthermore, the structure could be improved for clarity.

Correct translation:
"E meging matagumpe ing pamag-generate ning key."
or 
"Mealbung mag-generate key."
```

<!-- cache_translation_check_pam_5c302006cc165b08b092cb2c88bb936bffda011bc8a08c5806fc3fa4a023aff1 -->
```
        <source>version</source>
        <translation>bersion</translation>
    
ERR
The translation is incorrect. "Bersion" is a misspelling and not the correct Kapampangan ('pam') translation of "version". In Kapampangan, "version" is typically borrowed directly as "bersyun". 

Correct translation:
bersyun
```

<!-- cache_translation_check_pam_97b298e9aee4b5548d14bfa8b73172dffee604fd9aae91da921eae90da4f179d -->
```
        <source>M&amp;inimize on close</source>
        <translation>P&amp;alatian istung isara</translation>
    
ERR
The translation "Palatian istung isara" does not correctly convey the meaning of "Minimize on close", which refers to the application minimizing to the tray or background when the close button is pressed. The translation seems to be inaccurate in both lexical choice (palatian = 'Choose', istung = 'session', isara = 'close') and formatting.

Correct translation:
I-minimize king pamagsara
```

<!-- cache_translation_check_pam_71d0f116f71724136796c4104d26ea3295bbc73a447512a7ea2d4c80892ba873 -->
```
        <source>User Interface &amp;language:</source>
        <translation>Amanu na ning user interface:</translation>
    
ERR
The translation omits the word "language" and the shortcut key indicator (&). It should refer to the "language" setting for the user interface, and "&" must appear exactly once to indicate the shortcut key.

Correct translation:
&Language ning User Interface:
```

<!-- cache_translation_check_pam_f94956b361e96ad1f187e8e977fc672aae4cc2552ab4513263074fa45860de50 -->
```
        <source>&amp;Cancel</source>
        <translation>I-&amp;Cancel</translation>
    
ERR
The translation simply copies the English word "Cancel" and adds an "I-" prefix, which is not a translation into 'pam' (Pampangan/Kapampangan). The translation should use the Kapampangan equivalent.

Correct translation:
&amp;Ikanxela
(Note: If the typical Pampangan translation for "Cancel" is not "Ikanxela", adjust as appropriate after consulting native resources. "Ikanxela" is derived by analogy from Tagalog "Kanselahin", as "pam" does not have a standardized technical vocabulary for such interface terms.)
```

<!-- cache_translation_check_pam_90a2048d782ca2840c6908902d10f437606ddca7f27c35e0380c401f5c6e3d42 -->
```
        <source>The supplied proxy address is invalid.</source>
        <translation>Ing milageng proxy address eya katanggap-tanggap.</translation>
    
ERR
The translation is inaccurate. "Eya katanggap-tanggap" means "is acceptable," which is the opposite of "is invalid." Additionally, "milageng" is not appropriate; "pilan" or "ibinigay" could be used for "supplied".

Correct translation:
Ing ibinigay a proxy address alayan tamu makasaup. (But this may be a poor translation as well.)

A better and direct translation would be:
Ing ibinigay a proxy address alang bisa.
```

<!-- cache_translation_check_pam_7a9d4696cce1e4559fa35e61aeda6de228671f6fe47d3b03ce00f7640e07e654 -->
```
        <source>Clear &amp;All</source>
        <translation>I-Clear &amp;Eganagana</translation>
    
ERR
The translation "I-Clear &amp;Eganagana" is problematic for the following reasons:
- 'pam' refers to the Kapampangan language. The translation uses a structure ("I-Clear") that is not Kapampangan but influenced by Filipino/Tagalog or English.
- "Eganagana" phonetically resembles "lahat" (Tagalog for 'all') but is not a Kapampangan word. In Kapampangan, 'all' is usually "eganaganang" or "anggang".
- "Clear" should be translated or left as is only if it is commonly loaned, but the "I-" prefix is not standard for Kapampangan commands.
- Also, there is no whitespace issue or spam/unwanted content, but the translation does not sound natural or accurate in Kapampangan.

Correct translation:
"I-Clear &Ampong Eganaganang" or, more accurately, "I-Clear &Ampong Eganaganang" (to retain shortcut &). However, the most natural would be: "Limpiu &Ampong Eganaganang" (Limpiu = Clean/Clear, Ampong = and, Eganaganang = All), or simply "Limpiu &Eganaganang".

So, "Limpiu &Eganaganang" would be more correct.

Correct translation:
Limpiu &Eganaganang
```

<!-- cache_translation_check_pam_7a9d4696cce1e4559fa35e61aeda6de228671f6fe47d3b03ce00f7640e07e654 -->
```
        <source>Clear &amp;All</source>
        <translation>I-Clear &amp;Eganagana</translation>
    
ERR
The translation "I-Clear &amp;Eganagana" is problematic for the following reasons:
- 'pam' refers to the Kapampangan language. The translation uses a structure ("I-Clear") that is not Kapampangan but influenced by Filipino/Tagalog or English.
- "Eganagana" phonetically resembles "lahat" (Tagalog for 'all') but is not a Kapampangan word. In Kapampangan, 'all' is usually "eganaganang" or "anggang".
- "Clear" should be translated or left as is only if it is commonly loaned, but the "I-" prefix is not standard for Kapampangan commands.
- Also, there is no whitespace issue or spam/unwanted content, but the translation does not sound natural or accurate in Kapampangan.

Correct translation:
"I-Clear &Ampong Eganaganang" or, more accurately, "I-Clear &Ampong Eganaganang" (to retain shortcut &). However, the most natural would be: "Limpiu &Ampong Eganaganang" (Limpiu = Clean/Clear, Ampong = and, Eganaganang = All), or simply "Limpiu &Eganaganang".

So, "Limpiu &Eganaganang" would be more correct.

Correct translation:
Limpiu &Eganaganang
```

<!-- cache_translation_check_pam_b4e316528b799a0a6d8938d9779925723bc1489bfd8251ef080898e0f7daa48f -->
```
        <source>not accepted</source>
        <translation>ali metanggap</translation>
    
ERR
The translation "ali metanggap" is problematic and incorrect. In Kapampangan (pam), "not accepted" should be "e tanggap" or "ali tanggap". The use of "metanggap" is conjugated incorrectly.

Correct translation:
e tanggap
```

<!-- cache_translation_check_pam_6736ed11c8e393e1f0d67e5b0ca2360504ffc7ee46276255c5f3faf47810655e -->
```
        <source>Transaction ID</source>
        <translation>ID</translation>
    
ERR
The translation is incomplete. "ID" only reflects the "ID" part but omits "Transaction". It should provide the full phrase in 'pam' (Pampangan/Kapampangan).

Correct translation:
Transaction ID
```

<!-- cache_translation_check_pam_8f0ff13ae1689bd4021c02e9247975840f23d7514f27580ff5cbca0dbd4e851c -->
```
        <source>false</source>
        <translation>e tutu</translation>
    
ERR
The translation of "false" as "e tutu" is incorrect. "False" in Pampangan can be translated as "alilan" or "e totoo" (lit. "not true"), but "e tutu" is closer to "not true" in colloquial speech. While it is technically a possible rendering, for an interface context like a Bitcoin application, "alilan" or "e totoo" would be more appropriate to avoid ambiguity.

Correct translation:
alilan
or
e totoo
```
</details>

Number of issues: 17.
