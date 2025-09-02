# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>ro</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bro%5D%20request)


<!-- cache_translation_check_ro_08e69dd38ccb27aea37ea74d931c13128bf1f56965b82358e66c308a5615df39 -->
```
        <source>Copy &amp;Label</source>
        <translation>Copiază și etichetează</translation>
    
ERR
Problems:
- The ampersand (&) marking the shortcut key is missing in the translation; the source contains one and the translation must contain exactly one.
- The Romanian phrasing is slightly off: "Copiază și etichetează" literally means "Copy and label" (two actions) rather than the intended single action "Copy Label".

Correct translation suggestion:
Copiază &eticheta
```

<!-- cache_translation_check_ro_c58b5e7948968de17a215eda43d0570721b43ed4a96a1c755f1c95258666b286 -->
```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>Introduceţi vechea şi noua parolă pentru portofel.
 </translation>
    
ERR
There is an unwanted whitespace character at the end of the translation (a non-breaking space). Also, "Introduceţi vechea şi noua parolă pentru portofel." omits "Enter the old passphrase and new passphrase" nuance: ideally, the translation should preserve both the request to enter each passphrase and clarity.

Correct translation:
Introduceți vechea parolă și noua parolă pentru portofel.
```

<!-- cache_translation_check_ro_a5d47599c638a9ba65b230ad59fcef441c124fead45675ec49d7318fb9e9a6a2 -->
```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Fraza de acces introdusă pentru deblocarea portofelului este incorectă. Aceasta conține un caracter nul (ex - un octet zero). Dacă fraza de accesa fost setată cu o versiune de software mai veche decât 25.0, încearcă din nou doar cu caracterele de până la - dar fără a include - primul caracter nul. Dacă va funcționa, setează o nouă frază de acces pentru a evita această problemă în viitor.</translation>
    
ERR
The translation has a typo ("Dacă fraza de accesa" should be "Dacă fraza de acces") and a few minor wording issues (e.g., "ex - un octet zero" could be clearer). No format specifiers are involved.

Corrected translation:
Fraza de acces introdusă pentru deblocarea portofelului este incorectă. Aceasta conține un caracter nul (de exemplu — un octet zero). Dacă fraza de acces a fost setată cu o versiune a acestui software anterioară versiunii 25.0, încercați din nou folosind doar caracterele până la — dar fără a include — primul caracter nul. Dacă aceasta are succes, setați o nouă frază de acces pentru a evita această problemă în viitor.
```

<!-- cache_translation_check_ro_800b6a1b3c410fd42becec5aff68d0fc747c710c553164c78789c6fd1538158e -->
```
        <source>Wallet passphrase was successfully changed.</source>
        <translation>Parola portofelului a fost schimbată.</translation>
    
ERR
The translation omits the sense of "successfully" — it says "the wallet's password was changed" but doesn't include "successfully". A more accurate Romanian translation:

Parola portofelului a fost schimbată cu succes.
```

<!-- cache_translation_check_ro_faa315f4a9a4008dd7b3c5fb778da0cdcf11929ad43b45e2b4e08812bb121a53 -->
```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>A apărut o eroare fatală.%1 nu mai poate continua în siguranță și va ieși din program. </translation>
    
ERR
There is a missing space between the sentences: "fatală.%1" should be "fatală. %1". Additionally, there is an extra space at the end of the translation.

Correct translation:
A apărut o eroare fatală. %1 nu mai poate continua în siguranță și va ieși din program.
```

<!-- cache_translation_check_ro_ecff246488b66992df2327b4369b1c4f38b05c58ea59f4015dfd6cc5e3f27416 -->
```
        <source>Do you want to reset settings to default values, or to abort without making changes?</source>
        <extracomment>Explanatory text shown on startup when the settings file cannot be read. Prompts user to make a choice between resetting or aborting.</extracomment>
        <translation>Vrei să resetezi opțiunile la valorile predeterminate sau sa abordezi fără a face schimbări?</translation>
    
ERR
The word "abordezi" is incorrect in this context; it should be "abortezi" or "renunți", as "abordezi" means "to approach", while here it should be "to abort" or "give up".

Correct translation:
Vrei să resetezi opțiunile la valorile implicite sau să renunți fără a face schimbări?
```

<!-- cache_translation_check_ro_79de85dd8c37b4291669d632c884d95724f10cd1acff4d7b67e15dffa099c1dd -->
```
        <source>%1 d</source>
        <translation>%1 z</translation>
    
ERR
The translation uses "z" instead of the correct Romanian abbreviation for "days". The English "d" stands for "days" and should be translated to "zile" or abbreviated as "z" only if that's standard in Romanian. However, in Romanian date abbreviations, "z" is sometimes used for "zi" (day), but for "days" (plural) it's more standard to use "zile" or at least confirm local software conventions. If the application uses "z" consistently, it may be acceptable, but "d" should not be changed to "z" solely on an assumption.

Correct translation (most standard):
%1 z
or alternatively (fully written):
%1 zile

However, if local convention is single-letter, "z" can be accepted, but context should be checked. 

So, briefly:

The translation is potentially problematic because "z" may not be a standard plural abbreviation for "zile" in all contexts. To be fully correct:

Correct translation:
%1 zile
```

<!-- cache_translation_check_ro_cddd4e137a08fc78911573142e1c3bbc3f9aa4346e861f9e8928ff9e07e00c48 -->
```
        <source>&amp;Overview</source>
        <translation>&amp;Imagine de ansamblu</translation>
    
ERR
The Romanian translation is understandable but not natural for a UI label. A more idiomatic translation for "Overview" is "Prezentare generală" (or "Imagine de ansamblu" is literal but less common).

Ensure the shortcut marker & appears exactly once. Correct translation suggestion:

&Prezentare generală
```

<!-- cache_translation_check_ro_83447f655bacc2ef8ec66b9c005a4250560a5e25c18c2c61bb28e1fcdacf19f7 -->
```
        <source>E&amp;xit</source>
        <translation>Ieşire</translation>
    
ERR
The source contains a single '&' indicating a keyboard shortcut (E&amp;xit). The Romanian translation is missing the '&'. Also use the proper Romanian spelling with 'ș'.

Correct translation:
&Ieșire
```

<!-- cache_translation_check_ro_eb70ce29dbd3ad0dbb65fe3f72ad0373c693ab486c0a7089b84a9a4b458029f1 -->
```
        <source>&amp;Minimize</source>
        <translation>&amp;Reduce</translation>
    
SPAM
The translation is in English ("&Reduce"), not Romanian.

Correct translation:
&amp;Minimizează
```

<!-- cache_translation_check_ro_1a521928ed38112cdb7a8664bb392bedd67759c074fd0640c44b1e41dff590c5 -->
```
        <source>&amp;Send</source>
        <translation>Trimite</translation>
    
ERR
The source includes an ampersand (&) indicating a keyboard shortcut; the translation omits it. Add exactly one & in the translation.

Correct translation:
&amp;Trimite
```

<!-- cache_translation_check_ro_0632de0903eeddcb786cc510436d69cc29b630a42135607f3e6955356aac788e -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation>&amp;Criptarea Portofelului…</translation>
    
ERR
The translation is understandable but awkward/unnatural in Romanian: "Criptarea Portofelului…" is a noun phrase with unnecessary capitalization and not the usual imperative used in UI labels. Also UI strings typically use the verb form.

Correct translation:
&Criptează portofelul…
```

<!-- cache_translation_check_ro_7a239e4f197663010fecb220b0868121b4f7eb554083fb674b2c4c502d718177 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>&amp;Backup Portofelului...</translation>
    
ERR
Problems:
- The Romanian is awkward: "Backup Portofelului" mixes English and Romanian word order and uses a capitalized "Portofelului" (shouldn't be capitalized in this context).
- The source uses a single ellipsis character (…) while the translation uses three dots (...). Keep the same style.
- Better to use a natural Romanian phrasing.

Correct suggestions (choose one):
- &Backup portofelului…
- &Copia de rezervă a portofelului…
Both use the ampersand exactly once and the proper ellipsis character.
```

<!-- cache_translation_check_ro_9cddbbec769d90836d5d5bcbdc87a6de6394aa2eba2fbf561610a41826afb18a -->
```
        <source>Sign &amp;message…</source>
        <translation>Semnați și transmiteți un mesaj...</translation>
    
ERR
Problems:
- The translation changes the meaning: "Semnați și transmiteți un mesaj..." means "Sign and send a message...", while the source is just "Sign message…" (i.e., sign a message), not "sign and send".
- The source contains a single & indicating a keyboard shortcut; the translation does not include any &. The & must appear exactly once in the translation.
- Ellipsis: the source uses a single ellipsis character (…) — the translation uses three periods. Prefer using the same ellipsis character for consistency.

Correct translation (keeps meaning, includes one & and ellipsis):
Semnați &mesaj…
```

<!-- cache_translation_check_ro_5c888bfaa97851fb14ab4c9d12ac95bdd2ccce3bd99c2e8c5546bbbf2c3842ba -->
```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>Cereţi plăţi (generează coduri QR şi bitcoin-uri: URls)</translation>
    
ERR
The translation has a few issues:
- "bitcoin: URIs" refers to the URI scheme "bitcoin:", not "bitcoin-uri", and "URls" has a typographical error ("URls" vs "URI-uri" or "URI").
- The plural of "plată" should be "plăți", not "plăţi" (although ț and ţ are both used, the correct character is ț - Unicode U+021B).
- While "Cereți" is acceptable, "Solicită" is a more neutral imperative verb fit for a UI context.

Correct translation:
Solicită plăți (generează coduri QR și URI-uri bitcoin:)
```

<!-- cache_translation_check_ro_f2acd3917c127f42952d1afda410b742b69ef33161a008fd2c54600190df24b5 -->
```
        <source>&amp;Command-line options</source>
        <translation>Opţiuni linie de &amp;comandă</translation>
    
ERR
Grammar and naturalness issue in Romanian. "Opţiuni linie de &comandă" is awkward; better wording is "Opțiuni liniei de comandă" or "Opțiuni pentru linia de comandă". Ensure the shortcut ampersand appears exactly once.

Correct translation (with ampersand as entity):
Op&amp;ţiuni liniei de &amp;comandă

Alternatively (more common):
Op&amp;țiuni pentru linia de &amp;comandă
```

<!-- cache_translation_check_ro_084858eca1ae1d987d93171de56f18d11c1ff3be822a2b01655e882f79c3f2f6 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>Incarca PSBT din &amp;notite</translation>
    
ERR
Problems:
- The Romanian translation is semantically wrong: "notițe" means "notes", not "clipboard".
- Missing Romanian diacritics and the ellipsis character (…).
- Minor capitalization: should match source style.

Correct translation (keeps the shortcut & exactly once, uses diacritics and ellipsis):
Încarcă PSBT din &clipboard…
```

<!-- cache_translation_check_ro_245831d208e3b6c6515e31a8709fef334763b6c65f8361ffa1c4319344f9a9eb -->
```
        <source>&amp;Sending addresses</source>
        <translation>&amp;Adresele de destinatie</translation>
    
ERR
The Romanian translation changes the meaning: "Adresele de destinație" means "destination addresses" (receiving), not "sending addresses". Also the source has no definite article; UI label should be generic. Recommended correction (with ampersand kept once):

&Adrese de trimitere
```

<!-- cache_translation_check_ro_2715643192591928636c1f2e221628aa082df341e05545c422955829ab523288 -->
```
        <source>Open a bitcoin: URI</source>
        <translation>Deschidere bitcoin: o adresa URI sau o cerere de plată</translation>
    
ERR
The translation introduces extra content ("sau o cerere de plată" means "or a payment request") that is not present in the source text. Also, "Deschidere" should be "Deschide" to correctly translate "Open" in this context.

Correct translation:
Deschide un bitcoin: URI
```

<!-- cache_translation_check_ro_b91d204df620056decc7f7868c9dca2e81aa93e8f08ebba5e5963a0dde9bd054 -->
```
        <source>Restore a wallet from a backup file</source>
        <extracomment>Status tip for Restore Wallet menu item</extracomment>
        <translation>Recupereaza Portofelul din fisierele rezerva</translation>
    
ERR
The Romanian translation contains some errors:
- "Recupereaza" should have an accent: "Recuperează"
- "Portofelul" should be lowercase as in the source: "portofel"
- "fisierele rezerva" sounds odd; it should be "fișierul de backup" or "fișier de rezervă"
- The translation shifts from singular (wallet) to plural (files) incorrectly.

Correct translation:
Recuperează un portofel dintr-un fișier de backup
```

<!-- cache_translation_check_ro_f43ecaed8710e350af098d038a17cf3d87087dc8ced058031d45569db02b00e1 -->
```
        <source>&amp;Mask values</source>
        <translation>&amp;Valorile măștii</translation>
    
ERR
The translation "&Valorile măștii" reads as "the mask's values" (a noun phrase) and is unnatural for the GUI action "Mask values" (which is an instruction/label to mask values). Also word order/meaning is incorrect.

Suggested correct translation (verb form / GUI label):
&Maschează valorile

Alternative (if intended as "Hide values"):
&Ascunde valorile
```

<!-- cache_translation_check_ro_a0d2c07f8f4b01b61674e1f2da8d637d7a4fd4eef89cef7f86ea567d4f76e20f -->
```
        <source>(un)select all</source>
        <translation>(de)selectare tot</translation>
    
ERR
The translation is incorrect. The English phrase "(un)select all" should be accurately translated into Romanian, but "(de)selectare tot" is awkward and not idiomatic. A correct translation would be:

Selectează/deselectează tot

Alternatively, in concise UI language:

Selectează/deselectează toate

This uses the imperative forms appropriate for buttons or actions.
```

<!-- cache_translation_check_ro_522c3c292d11100eb892db1ed58ab06ad811a1208d27f0e4ac047975fbf43d6b -->
```
        <source>&amp;Copy address</source>
        <translation>&amp;Copiaza adresa</translation>
    
ERR
The translation is understandable but misses the Romanian diacritic on "Copiază". Use of diacritics is preferred.

Correct translation:
&amp;Copiază adresa
```

<!-- cache_translation_check_ro_8992d8ea7d822178f76e6fa1dff365f346f968640cd98d063b765d063f348168 -->
```
        <source>Copy &amp;label</source>
        <translation>Copiaza si eticheteaza</translation>
    
ERR
The translation is incorrect and problematic:
- It mistranslates the meaning by adding "și" ("and"), turning "Copy label" into "Copy and label".
- It omits the UI shortcut marker (&) that exists exactly once in the source.
- It lacks proper Romanian diacritics (optional but preferred): "Copiaza si eticheteaza" → "Copiază etichetează" would still be wrong meaning-wise.

Correct translation suggestions (include exactly one & for the shortcut), with diacritics:
- Copiază &etichetă

If you prefer without diacritics:
- Copiaza &etichetă
```

<!-- cache_translation_check_ro_66fc71084e485154b1c60e5f97979aeb3fd177034d8825f9d6f8de9e78f8cfca -->
```
        <source>Copy &amp;amount</source>
        <translation>copiaza &amp;valoarea</translation>
    
ERR
The Romanian translation lacks correct diacritics and capitalization. It should use "copiază" (with ă/ș). Also ensure the ampersand appears exactly once — keeping it before "valoarea" is fine.

Correct translation:
Copiază &valoarea
```

<!-- cache_translation_check_ro_73af8a8feb14b3ac87ccf990eea251300731f8657bc6beb951739082b0deb769 -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>copiaza ID-ul de tranzactie si indexul de iesire</translation>
    
ERR
Problems:
- The translation is missing the shortcut ampersand (&) present in the source; the translation must include exactly one &.
- It lacks proper Romanian capitalization and diacritics.
- Slightly awkward wording ("de tranzactie" should use diacritics and genitive form).

Correct translation (with one & for the shortcut):
Copiază &ID-ul tranzacției și indexul ieșirii
```

<!-- cache_translation_check_ro_3453ba4e7ab3f4835b380082662e4962171378c1ff5faacbd026f1b9eab623aa -->
```
        <source>(change)</source>
        <translation>(rest)</translation>
    
ERR
The Romanian translation uses "rest", which, while sometimes used informally in the context of financial transactions to mean "change", it is slightly ambiguous and less formal/clear. In the context of Bitcoin and technical terminology, "schimb" or "monedă de schimb" could be used, but more typically, "rest" is understood by Romanian speakers in this context.

However, if following standard translations in Romanian Bitcoin interfaces, "rest" is widely accepted and not problematic. For clarity and formality, it could be improved to "schimb" or "suma de rest", but strictly speaking, it is not erroneous nor spam.

So, the answer is:

NO
```

<!-- cache_translation_check_ro_8e503fa6e141140a51531ed616806e7c50a3a70c87c4d2a3e22d3e4bdd767175 -->
```
        <source>Creating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the create wallet progress window which indicates to the user which wallet is currently being created.</extracomment>
        <translation>Creeaza Protofel&lt;b&gt;%1&lt;/b&gt;</translation>
    
ERR
There are issues with this translation:
1. "Creeaza" should be "Creează" (diacritic missing).
2. "Protofel" is a typo; the correct word is "Portofel".
3. The ellipsis at the end of the sentence ("…") is missing in the translation.
4. There should be a space between "Portofel" and "<b>".

Correct translation:
Creează portofelul &lt;b&gt;%1&lt;/b&gt;…
```

<!-- cache_translation_check_ro_cd0cb8a0361ed553c6decaa224e1f51de2e07bb2fcbf855fd4dd86daeb6e29b9 -->
```
        <source>Reverting this setting requires re-downloading the entire blockchain. It is faster to download the full chain first and prune it later. Disables some advanced features.</source>
        <translation>Revenirea la această setare necesită re-descărcarea întregului blockchain. Este mai rapid să descărcați mai întâi rețeaua complet și să o fragmentați  mai târziu. Dezactivează unele funcții avansate.</translation>
    
ERR
There are two issues:
1. "să descărcați mai întâi rețeaua complet" should be "să descărcați mai întâi lanțul complet", as "blockchain" is usually translated as "lanțul de blocuri" or just "lanțul".
2. There is an extra space before "mai târziu" ("fragmentați  mai târziu").

Correct translation:
Revenirea la această setare necesită re-descărcarea întregului blockchain. Este mai rapid să descărcați mai întâi lanțul complet și să îl fragmentați mai târziu. Dezactivează unele funcții avansate.
```

<!-- cache_translation_check_ro_b34503f3b7e36feb8b353a4954eedd4505da4863a9192f76ad045a072b54b7f0 -->
```
        <source>Open bitcoin URI</source>
        <translation>DeschidețI Bitcoin URI</translation>
    
ERR
The Romanian translation has an incorrect capitalization of "DeschidețI" (should be "Deschideți") and the phrase "Bitcoin URI" would be more natural as "URI Bitcoin".

Correct translation:
Deschideți un URI Bitcoin
```

<!-- cache_translation_check_ro_ff1351ce9daa5ebb74dfafd42e2f13034f5df2d018893984031467cc8aa0e0bd -->
```
        <source>&amp;Main</source>
        <translation>Principal</translation>
    
ERR
The translation is correct word-wise ("Principal" = "Main") but it is missing the required shortcut marker '&' that appears exactly once in the source. Add the ampersand in the translation.

Correct translation:
&amp;Principal
```

<!-- cache_translation_check_ro_10ec30ae97585499730ea275d47e00e968071aa56782517e95a8ed677dec6bfc -->
```
        <source>&amp;Start %1 on system login</source>
        <translation>&amp;Porneste %1 la logarea in sistem.</translation>
    
ERR
Problems:
- Romanian diacritics missing: "Porneste" should be "Pornește" and "in" should be "în".
- Unnecessary trailing period added (source has no period).

Correct translation (preserving %1 and single &):
&Pornește %1 la autentificarea în sistem
```

<!-- cache_translation_check_ro_2053f41889fd6789dca61268fc8e2c572eb50fcb0e89820aaee5c9c8aac4fde2 -->
```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>A activa "pruning" reduce signifiant spațiul pe disk pentru a stoca tranzacțiile.</translation>
    
ERR
The translation omits much of the original content, does not fully convey the meaning, and leaves out important details about full block validation and the need to re-download the blockchain if reverted. Moreover, "A activa 'pruning'" should be phrased more naturally in Romanian.

Correct translation:
Activarea modului de pruning reduce semnificativ spațiul pe disc necesar pentru stocarea tranzacțiilor. Toate blocurile sunt totuși complet validate. Revenirea la această setare necesită re-descărcarea întregului blockchain.
```

<!-- cache_translation_check_ro_9fa1fc0eef4b7d444425590187d5ffab144101d3f4a6db925d97a291d109edbc -->
```
        <source>Size of &amp;database cache</source>
        <translation>Mărimea bazei de &amp;date cache</translation>
    
ERR
The Romanian is awkward and has incorrect word order: "Mărimea bazei de &date cache" mixes "bazei de date" and "cache" incorrectly. Also the accelerator (&) is placed before "date" which is odd given wording.

Correct translation (accelerator kept once):
Mărimea &cache-ului bazei de date
```

<!-- cache_translation_check_ro_7b49ef298fac68fe41999c64e7dc372df57ccbcb5ec8f8eb5c5476334be6a104 -->
```
        <source>&amp;Network</source>
        <translation>Reţea</translation>
    
ERR
The source contains a single shortcut marker '&' which must also appear exactly once in the translation. The provided translation "Reţea" is missing the '&'. Also prefer the Romanian letter 'ț' (t-comma) rather than 'ţ' (t-cedilla).

Correct translation:
&amp;Rețea
```

<!-- cache_translation_check_ro_dcbd609767804ca4a88f6f4dc507cffd4fd50a2b6f58597dd289e13f05c2cc8a -->
```
        <source>Prune &amp;block storage to</source>
        <translation>Reductie &amp;block storage la</translation>
    
ERR
The translation mixes Romanian and English ("block storage") and uses an incorrect Romanian word form ("Reductie" should be "Reduceți" or similar). Also word order/grammar is off. The ampersand is present once (good), but the phrase should be fully translated.

Suggested correct translations (choose appropriate tone for your UI):
- Reduceți &stocarea blocurilor la
or
- Trunchiați &stocarea blocurilor la

(Place the & exactly once to mark the shortcut; both suggestions have it before "stocarea".)
```

<!-- cache_translation_check_ro_77ea801a9e738212f61ac76bd25910a70e873da6c51c4e3c6b6954e1d61d0191 -->
```
        <source>Enable R&amp;PC server</source>
        <extracomment>An Options window setting to enable the RPC server.</extracomment>
        <translation>Permite server-ul R&amp;PC</translation>
    
ERR
The Romanian is awkward/grammatically incorrect. "Permite server-ul R&amp;PC" uses "Permite" incorrectly with the definite article attached via a hyphen and is not the usual imperative for "Enable". Also "server-ul" should not have a hyphen; use "serverul" and the verb "Activează" or "Activează/Permite" is more natural.

Correct translation:
Activează serverul R&amp;PC
```

<!-- cache_translation_check_ro_814524a7cf40aa56da3a58637cf85cd8251a6bc841fe901f5da62006a1e219de -->
```
        <source>W&amp;allet</source>
        <translation>Portofel</translation>
    
ERR
The source contains a single shortcut marker "W&amp;allet" (an ampersand). The translation "Portofel" is missing the required ampersand. No other issues, but the shortcut marker must be included exactly once.

Correct translation (include one ampersand for the shortcut), for example:
<translation>&Portofel</translation>
```

<!-- cache_translation_check_ro_6ec3d177d22d97dc7834c644030a04c9744249cb897ba5b72b8535190525bc8f -->
```
        <source>Enable coin &amp;control features</source>
        <translation>Activare caracteristici de control ale monedei</translation>
    
ERR
Problems:
- The Romanian text uses the noun "Activare" (activation) rather than the verb/command form expected in the UI ("Enable").
- The ampersand (&) accelerator present in the source is missing in the translation; there must be exactly one & to indicate the shortcut key.
- A more natural Romanian phrasing is preferred.

Correct translation:
Activează funcțiile de &control ale monedei
```

<!-- cache_translation_check_ro_fb11d08d0ba451d1f7ba0c969499f7072916bc11335850048617c5a114e0e801 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>Cheltuire rest neconfirmat</translation>
    
ERR
Problems:
- The accelerator '&' from the source is missing; the translation must include exactly one '&'.
- The Romanian phrase is awkward and missing diacritics. It should use a verb form and include the definite article for natural phrasing.

Correct translation:
&amp;Cheltuiește restul neconfirmat
```

<!-- cache_translation_check_ro_26f6027ae40437308c86f9e643f9e97defdd315a14dbe308650547ff4a7ddfee -->
```
        <source>&amp;Connect through SOCKS5 proxy (default proxy):</source>
        <translation>&amp;Conectare printr-un proxy SOCKS5 (implicit proxy):</translation>
    
ERR
The translation is understandable but slightly awkward in Romanian — the phrase "implicit proxy" uses English word order and should be "proxy implicit". Also "proxy SOCKS5" is more natural than "un proxy SOCKS5" in this label.

Correct translation:
&amp;Conectare prin proxy SOCKS5 (proxy implicit):
```

<!-- cache_translation_check_ro_ff6b464a1f9aeb141a6f95778a4a0ba502680302108942fef643c0519600a4e4 -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>&amp;Minimizare în tray în loc de taskbar</translation>
    
ERR
Problems:
- Uses English words "tray" and "taskbar" instead of Romanian equivalents.
- "Minimizare" is a noun; the source requests an imperative/verb form for a menu/option label.

Suggested correct translation:
&amp;Minimizează în tava de sistem în locul barei de activități
```

<!-- cache_translation_check_ro_b64f9ed4c4c30aa3495fa64255f472de04557cecb62c7b121d9e1e0bd36ce26e -->
```
        <source>M&amp;inimize on close</source>
        <translation>M&amp;inimizare fereastră în locul închiderii programului</translation>
    
ERR
The Romanian text is grammatically incorrect/awkward and doesn't convey the original succinctly. The accelerator (&) is present once (good), but the wording should be a verb form and the phrase reordered.

Correct translations, preserving a single & for the shortcut:
- M&inimizează fereastra la închidere
or shorter:
- M&inimizează la închidere

(Place the & before the letter you want as the shortcut; here it precedes 'i' as in the source.)
```

<!-- cache_translation_check_ro_6e1aef39a84402e6bc8c18040a08a2617709450efb64a6d1b13b8aa3848c9742 -->
```
        <source>User Interface &amp;language:</source>
        <translation>&amp;Limbă interfaţă utilizator</translation>
    
ERR
Issues:
- Word order and grammar are off for Romanian; "Limbă interfaţă utilizator" is unnatural.
- The colon (:) at the end of the source is missing in the translation.
- Keep exactly one ampersand; the translation has one, which is fine, but position can be adjusted.

Correct translation (suggested):
&Limba interfeței utilizatorului:
```

<!-- cache_translation_check_ro_0b532a1fda725c5b0d89b6cdb4908faa5a68c2527b74b37549ad2fd267ca7cfd -->
```
        <source>&amp;Cancel</source>
        <translation>Renunţă</translation>
    
ERR
The translation is missing the accelerator ampersand (&) present in the source. Also the Romanian character should use "ț" (t-comma) if possible.

Correct translation:
&amp;Renunță
```

<!-- cache_translation_check_ro_a7eeb632072838541f4a372008007c17cb98ab73310a28278f717f2655b677e1 -->
```
        <source>Unable to calculate transaction fee or total transaction amount.</source>
        <translation>Nu s-a putut calcula comisionul de tranzactie sau suma totala al tranzactiei.</translation>
    
ERR
There are issues with the grammatical agreement in the Romanian translation. "tranzactie" should have the proper diacritics ("tranzacție"), and "suma totala al tranzactiei" should use the correct agreement: "suma totală a tranzacției."

Correct translation:
Nu s-a putut calcula comisionul de tranzacție sau suma totală a tranzacției.
```

<!-- cache_translation_check_ro_c538c536717a0ff7e1241b192d541d525c4fb0e5d3347b20bb16f33360754f0b -->
```
        <source>&amp;Save Image…</source>
        <translation>&amp;Salveaza Imaginea...</translation>
    
ERR
The Romanian translation uses no diacritics, uses three periods instead of the single ellipsis character, and capitalizes "Imaginea" (minor style). Also ensure the & shortcut is present once (it is), but use proper Romanian spelling.

Correct translation:
&amp;Salvează imaginea…
```

<!-- cache_translation_check_ro_b82de2202ca8621b86aa98cf22d0250ea38ae7b147b7adae87605f18b395559d -->
```
        <source>&amp;Copy Image</source>
        <translation>&amp;Copiaza Imaginea</translation>
    
ERR
The translation is understandable but has issues: missing Romanian diacritics and incorrect capitalization. In Romanian the verb should be "Copiază" (with ă) and the noun is normally lowercase "imaginea".

Correct translation:
&amp;Copiază imaginea
```

<!-- cache_translation_check_ro_1f964bd23862f341f5d1a8368b266f55b7b28c0c2fe4868e447ddd66a68b6199 -->
```
        <source>Datadir</source>
        <translation>Dirdate</translation>
    
ERR
The translation is incorrect. "Datadir" should be translated as "Director de date" or left as "Datadir" if it refers to a technical directory name. "Dirdate" does not have meaning in Romanian.

Correct translation:
Director de date
```

<!-- cache_translation_check_ro_c963ad4875b9974aaf4184dc54a244b91958a38e2b5d380c229882719103c709 -->
```
        <source>&amp;Network Traffic</source>
        <translation>Trafic reţea</translation>
    
ERR
The translation is missing the required shortcut ampersand (&) and uses the deprecated cedilla 'ţ' instead of the correct comma 'ț' in modern Romanian. Also ensure exactly one '&' is present.

Correct translation:
&amp;Trafic rețea
```

<!-- cache_translation_check_ro_96a37554d20e206b5c4be6e25a908bbeb71d1268c3909de47e81faabcaa70d4d -->
```
        <source>Ctrl+I</source>
        <translation>Ctrl+l</translation>
    
ERR
The translation uses a lowercase 'L' (l) instead of the uppercase 'I' (I). In Romanian, shortcut keys should match the source key.

Correct translation:
Ctrl+I
```

<!-- cache_translation_check_ro_17414efb3d237a8ee2bedaf6103458404a32363fd8d93946910fa243542ccfca -->
```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>Bine ai venit la consola RPC %1 .
Folosește săgețile sus și jos pentru a naviga istoricul, iar %2 pentru a curăța ecranul.
Folosește %3 și %4 pentru a crește sau scădea dimensiunea textului.
Tastează %5pentru o listă a comenzilor disponibile .
Pentru mai multe informații privind folosirea consolei, tastează %6.

%7ATENȚIE: Scammerii au fost activi, cerându-le utilizatorilor să tasteze anumite comenzi, furându-le date din portofel. Nu folosi consola fără a înțelege complet ramificațiile unei comenzi. %8</translation>
    
ERR
There are minor formatting and spacing errors, as well as a slight stylistic issue. Specifically:
- In "%1 .", the space should not be before the period.
- In "Tastează %5pentru o listă...", there is no space between '%5' and 'pentru'.
- In "comenzii disponibile .", the space before the period should be removed.
- In the warning text, there is a space before '%8' that should likely not be there, to preserve the intentional formatting.

Correct translation:
Bine ai venit la consola RPC %1.
Folosește săgețile sus și jos pentru a naviga istoricul, iar %2 pentru a curăța ecranul.
Folosește %3 și %4 pentru a crește sau scădea dimensiunea textului.
Tastează %5 pentru o listă a comenzilor disponibile.
Pentru mai multe informații privind folosirea consolei, tastează %6.

%7ATENȚIE: Escrocii au fost activi, cerându-le utilizatorilor să tasteze anumite comenzi, furându-le conținutul portofelului. Nu folosi consola fără a înțelege complet ramificațiile unei comenzi.%8
```

<!-- cache_translation_check_ro_213cf7b9ea72fddbc5eb710b9218a25707a4808d5c4e6f6874e1f2db5cce61bc -->
```
        <source>&amp;Amount:</source>
        <translation>&amp;Suma:</translation>
    
ERR
The translation is nearly correct but misses the Romanian diacritic on "Sumă". Also ensure the ampersand for the shortcut appears exactly once (it does).

Correct translation:
&amp;Sumă:
```

<!-- cache_translation_check_ro_9edf893a4ecea81adf24f23005d55813736be3e23e746cc15cb21ca712a1bcbc -->
```
        <source>Copy &amp;URI</source>
        <translation>Copiază &amp;URl</translation>
    
ERR
The translation has a typo: "URl" uses a lowercase "l" instead of an uppercase "I". The ampersand shortcut is present exactly once (good), and "Copiază" is correct Romanian. 

Correct translation:
Copiază &URI
```

<!-- cache_translation_check_ro_522c3c292d11100eb892db1ed58ab06ad811a1208d27f0e4ac047975fbf43d6b -->
```
        <source>&amp;Copy address</source>
        <translation>&amp;Copiaza adresa</translation>
    
ERR
The translation is understandable but misses the Romanian diacritic on "Copiază". Use of diacritics is preferred.

Correct translation:
&amp;Copiază adresa
```

<!-- cache_translation_check_ro_8992d8ea7d822178f76e6fa1dff365f346f968640cd98d063b765d063f348168 -->
```
        <source>Copy &amp;label</source>
        <translation>Copiaza si eticheteaza</translation>
    
ERR
The translation is incorrect and problematic:
- It mistranslates the meaning by adding "și" ("and"), turning "Copy label" into "Copy and label".
- It omits the UI shortcut marker (&) that exists exactly once in the source.
- It lacks proper Romanian diacritics (optional but preferred): "Copiaza si eticheteaza" → "Copiază etichetează" would still be wrong meaning-wise.

Correct translation suggestions (include exactly one & for the shortcut), with diacritics:
- Copiază &etichetă

If you prefer without diacritics:
- Copiaza &etichetă
```

<!-- cache_translation_check_ro_fc87f6563de38e6a26a93e11584b1bfd7a6e3252fb5acf0196087b79bd77a92e -->
```
        <source>Copy &amp;message</source>
        <translation>Copie și mesaj</translation>
    
ERR
The translation is incorrect. "Copie și mesaj" literally means "Copy and message" and is grammatically wrong; it also omits the required '&' shortcut marker.

Correct translation (with a single & for the shortcut):
Copiază &mesaj
```

<!-- cache_translation_check_ro_66fc71084e485154b1c60e5f97979aeb3fd177034d8825f9d6f8de9e78f8cfca -->
```
        <source>Copy &amp;amount</source>
        <translation>copiaza &amp;valoarea</translation>
    
ERR
The Romanian translation lacks correct diacritics and capitalization. It should use "copiază" (with ă/ș). Also ensure the ampersand appears exactly once — keeping it before "valoarea" is fine.

Correct translation:
Copiază &valoarea
```

<!-- cache_translation_check_ro_9edf893a4ecea81adf24f23005d55813736be3e23e746cc15cb21ca712a1bcbc -->
```
        <source>Copy &amp;URI</source>
        <translation>Copiază &amp;URl</translation>
    
ERR
The translation has a typo: "URl" uses a lowercase "l" instead of an uppercase "I". The ampersand shortcut is present exactly once (good), and "Copiază" is correct Romanian. 

Correct translation:
Copiază &URI
```

<!-- cache_translation_check_ro_c538c536717a0ff7e1241b192d541d525c4fb0e5d3347b20bb16f33360754f0b -->
```
        <source>&amp;Save Image…</source>
        <translation>&amp;Salveaza Imaginea...</translation>
    
ERR
The Romanian translation uses no diacritics, uses three periods instead of the single ellipsis character, and capitalizes "Imaginea" (minor style). Also ensure the & shortcut is present once (it is), but use proper Romanian spelling.

Correct translation:
&amp;Salvează imaginea…
```

<!-- cache_translation_check_ro_7f9c120af5b3e0de9b65399a8c1739cbf60420038fa4b42e93176e79f1c10f24 -->
```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Introduceţi adresa de semnatură, mesajul (asiguraţi-vă că aţi copiat spaţiile, taburile etc. exact) şi semnatura dedesubt pentru a verifica mesajul. Aveţi grijă să nu citiţi mai mult în semnatură decît mesajul în sine, pentru a evita să fiţi păcăliţi de un atac de tip man-in-the-middle. De notat ca aceasta dovedeste doar ca semnatarul primeste odata cu adresa, nu dovedesta insa trimiterea vreunei tranzactii.</translation>
    
ERR
There are several issues in the translation:
1. The phrase "adresa de semnatură" is incorrect and should be "adresa destinatarului" ("receiver's address").
2. It omits "line breaks" from the list of what must be copied exactly.
3. "că aţi copiat spaţiile, taburile etc. exact" omits the specificity of including newlines, and does not mirror the English precisely.
4. Double diacritics are missing for Romanian (e.g., "semnatură" → "semnătură", "dedesubt" could be clearer as "mai jos").
5. "semnatura dedesubt" is awkward Romanian; better: "și semnătura mai jos".
6. "dovedeste" should have diacritics ("dovedește"), and "primestre" does not literally exist; it should mention "primește cu adresa".
7. "trimiterea vreunei tranzactii" should be "trimiterea vreunei tranzacții".

Correct translation:
Introduceți mai jos adresa destinatarului, mesajul (asigurați-vă că ați copiat exact toate liniuțele noi, spațiile, taburile etc.) și semnătura pentru a verifica mesajul. Aveți grijă să nu interpretați mai mult în semnătură decât ceea ce se află în mesajul semnat, pentru a evita să fiți păcăliți de un atac de tip man-in-the-middle. Rețineți că acest lucru dovedește doar că partea semnatară primește cu acea adresă, nu poate dovedi trimiterea vreunei tranzacții!
```

<!-- cache_translation_check_ro_adcee763eebe23e6995cd02e9092e90547533024dae35dd24cf509926d89383d -->
```
        <source>The Bitcoin address the message was signed with</source>
        <translation>Introduceţi o adresă Bitcoin</translation>
    
ERR
The translation is incorrect. The source refers to "The Bitcoin address the message was signed with," while the translation says "Introduceţi o adresă Bitcoin" ("Enter a Bitcoin address"), which does not convey the original meaning.

Correct translation:
Adresa Bitcoin cu care a fost semnat mesajul
```

<!-- cache_translation_check_ro_8064580f88dc37f7dae8b3b84b69caeee5e2debf8c6214dcdb9eac0a715e7c77 -->
```
        <source>Reset all verify message fields</source>
        <translation>Resetează toate cîmpurile mesajelor semnate</translation>
    
ERR
The translation changes the meaning. The source refers to "verify message fields", but the translation refers to "fields of signed messages" ("cîmpurile mesajelor semnate"). Furthermore, the correct character in modern Romanian is "î" (not "î" at the beginning, but "â" inside words, so "câmpurilor", not "cîmpurilor").

Correct translation:
Resetează toate câmpurile pentru verificarea mesajului
```

<!-- cache_translation_check_ro_f5d72e5d919a9268783e90800e06c4b950d062c8464f9ad458a7d443d0cfe518 -->
```
        <source>The signature did not match the message digest.</source>
        <translation>Semnatura nu se potriveşte cu mesajul.</translation>
    
ERR
The translation is inaccurate. The English source refers to the message digest (i.e., hash of the message), not just the message. The Romanian translation omits this important term.

Correct translation:
Semnătura nu corespunde cu rezumatul (digestul) mesajului.
```

<!-- cache_translation_check_ro_6a3669313fa3fc3d4a272bdf23837fabb0b1580ee7088eb49c2a4e7c31c063d9 -->
```
        <source>Generated coins must mature %1 blocks before they can be spent. When you generated this block, it was broadcast to the network to be added to the block chain. If it fails to get into the chain, its state will change to "not accepted" and it won't be spendable. This may occasionally happen if another node generates a block within a few seconds of yours.</source>
        <translation>Monedele generate se pot cheltui doar dupa inca %1 blocuri.  După ce a fost generat, s-a propagat în reţea, urmând să fie adăugat in blockchain.  Dacă nu poate fi inclus in lanţ, starea sa va deveni "neacceptat" si nu va putea fi folosit la tranzacţii.  Acest fenomen se întâmplă atunci cand un alt nod a generat un bloc la o diferenţa de câteva secunde.</translation>
    
ERR
There are several issues with the translation:
- The number of required blocks to mature ("%1 blocks") should be explicitly mentioned, as in the source, not rendered vaguely as "doar dupa inca %1 blocuri" (only after another %1 blocks).
- Some content is omitted: "When you generated this block" is not translated explicitly; the translation only states "După ce a fost generat" (After it was generated), not making clear the subject "you".
- "it won't be spendable" is rendered as "nu va putea fi folosit la tranzacţii" (cannot be used for transactions), which is acceptable, but a closer equivalent for "spendable" would be better.
- The translation turns explanations into more generic phrases, losing the clarity of cause and effect from the original.
- There's stray double spacing in several places.
- Word choices such as "blockchain" vs "lanţ" should be consistent (choose either "blockchain" or "lanţ de blocuri" for the Romanian context).
- The last sentence omits “your block” (ai tău) for clarity.

Correct translation:
Monedele generate trebuie să se maturizeze timp de %1 blocuri înainte de a putea fi cheltuite. Când ai generat acest bloc, el a fost transmis în rețea pentru a fi adăugat la lanțul de blocuri. Dacă nu reușește să fie inclus în lanț, starea lui va deveni „neacceptat” și nu va putea fi cheltuit. Acest lucru se poate întâmpla uneori dacă un alt nod generează un bloc la câteva secunde după al tău.
```

<!-- cache_translation_check_ro_d6f83d3e84a29ee01c6f2a587aa3a850e647e4570c86b8665547e973eddef5ba -->
```
        <source>User-defined intent/purpose of the transaction.</source>
        <translation>Intentie/scop al tranzactie definit de user.</translation>
    
ERR
There are several issues: "tranzactie" should be "tranzacție" (with diacritics), "user" should be translated to "utilizator", and the article should be correct in context ("o tranzacție"). Also, "intenție" and "scop" should be with proper diacritics.

Correct translation:
Intenție/scop al tranzacției definit de utilizator.
```

<!-- cache_translation_check_ro_522c3c292d11100eb892db1ed58ab06ad811a1208d27f0e4ac047975fbf43d6b -->
```
        <source>&amp;Copy address</source>
        <translation>&amp;Copiaza adresa</translation>
    
ERR
The translation is understandable but misses the Romanian diacritic on "Copiază". Use of diacritics is preferred.

Correct translation:
&amp;Copiază adresa
```

<!-- cache_translation_check_ro_8992d8ea7d822178f76e6fa1dff365f346f968640cd98d063b765d063f348168 -->
```
        <source>Copy &amp;label</source>
        <translation>Copiaza si eticheteaza</translation>
    
ERR
The translation is incorrect and problematic:
- It mistranslates the meaning by adding "și" ("and"), turning "Copy label" into "Copy and label".
- It omits the UI shortcut marker (&) that exists exactly once in the source.
- It lacks proper Romanian diacritics (optional but preferred): "Copiaza si eticheteaza" → "Copiază etichetează" would still be wrong meaning-wise.

Correct translation suggestions (include exactly one & for the shortcut), with diacritics:
- Copiază &etichetă

If you prefer without diacritics:
- Copiaza &etichetă
```

<!-- cache_translation_check_ro_66fc71084e485154b1c60e5f97979aeb3fd177034d8825f9d6f8de9e78f8cfca -->
```
        <source>Copy &amp;amount</source>
        <translation>copiaza &amp;valoarea</translation>
    
ERR
The Romanian translation lacks correct diacritics and capitalization. It should use "copiază" (with ă/ș). Also ensure the ampersand appears exactly once — keeping it before "valoarea" is fine.

Correct translation:
Copiază &valoarea
```

<!-- cache_translation_check_ro_109b18f173e964b712e61b44d6e0cf81eea255afbb34168fa51111e71cc15860 -->
```
        <source>Copy transaction &amp;ID</source>
        <translation>Copiaza ID-ul de tranzactie</translation>
    
ERR
The translation is missing the required shortcut ampersand (&), lacks Romanian diacritics, and uses an unnatural phrasing ("de tranzactie"). 

Correct translation (with single & for the shortcut):
Copiază &ID-ul tranzacției
```

<!-- cache_translation_check_ro_83a8103c5a068d7be63a955431385a64dbb0fdb3a3cf73becaa06fabad4e711e -->
```
        <source>Copy full transaction &amp;details</source>
        <translation>Copiaza toate detaliile tranzacţiei</translation>
    
ERR
Problems:
- The translation is missing the mnemonic ampersand (&) that appears exactly once in the source ("&details").
- It also lacks Romanian diacritics.

Correct translation (include & once; placement before 'detaliile' preserves the original shortcut on 'd'):
Copiază toate &detaliile tranzacției
```

<!-- cache_translation_check_ro_ef18bbc46b106b835b0cba5a37a88bec67b8b0e70d1f751bd0bed77248763c55 -->
```
        <source>Error reading %s! Transaction data may be missing or incorrect. Rescanning wallet.</source>
        <translation>Error citind %s! Data tranzacțieii poate fi lipsă sau incorectă. Rescanând portofel.</translation>
    
ERR
There are minor errors: "Error citind" should be in Romanian ("Eroare la citirea"), "tranzacțieii" has a double "i" and should be "tranzacției", "data" should be capitalized only if it starts the sentence, and "Rescanând portofel." is grammatically incomplete; "Rescanez portofelul" or "Se rescanează portofelul" is correct.

Correct translation:
Eroare la citirea %s! Datele tranzacției pot lipsi sau pot fi incorecte. Se rescanează portofelul.
```

<!-- cache_translation_check_ro_793f7bb703cf349b2fe4d8c602e19011e64517097424541fe6a0ec3ece5ac176 -->
```
        <source>The block database contains a block which appears to be from the future. This may be due to your computer's date and time being set incorrectly. Only rebuild the block database if you are sure that your computer's date and time are correct</source>
        <translation>Baza de date a blocurilor contine un bloc ce pare a fi din viitor. Acest lucru poate fi cauzat de setarea incorecta a datei si orei in computerul dvs. Reconstruiti baza de date a blocurilor doar daca sunteti sigur ca data si ora calculatorului dvs sunt corecte.</translation>
    
ERR
Issues:
- Missing Romanian diacritics (ex: "contine", "incorecta", "Reconstruiti", "sunteti").
- Inconsistent word choice for "computer" ("computerul" then "calculatorul") — should be consistent.
- Missing period after the abbreviation "dvs" in the phrase "calculatorului dvs sunt".
- Small stylistic improvements to sound natural.

Correct translation:
Baza de date a blocurilor conține un bloc care pare a fi din viitor. Aceasta se poate datora setării incorecte a datei și orei calculatorului dvs. Reconstruiți baza de date a blocurilor doar dacă sunteți sigur că data și ora calculatorului dvs. sunt corecte.
```

<!-- cache_translation_check_ro_0f64183033c9b7e9ad0a43bac6a75497448a183cc6b03976cb7e8366a7a231a8 -->
```
        <source>Failed to verify database</source>
        <translation>Verificarea datei de baze a eșuat</translation>
    
ERR
There is a minor grammatical error in the Romanian translation. "datei de baze" should be "bazei de date". The correct translation is:

Verificarea bazei de date a eșuat
```

<!-- cache_translation_check_ro_f1ae5ee3e4f69b813e41dfebc624bbc547e60a4d2a2b4e49a7ebc1f4e6abbf95 -->
```
        <source>Starting network threads…</source>
        <translation>Pornire fire de execuție rețea…</translation>
    
ERR
The Romanian is ungrammatical/awkward ("Pornire fire de execuție rețea…"). No format specifiers present, and ellipsis spacing is fine.

Correct translations (choose preferred style):
- Se pornesc firele de execuție ale rețelei…
- Pornirea firelor de execuție ale rețelei…
```
</details>

Number of issues: 75.
