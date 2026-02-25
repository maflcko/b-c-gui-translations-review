# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>sl</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bsl%5D%20request)


<!-- cache_translation_check_sl_49607f0c441ec21f616c17fc7b5e7cf1e850a02d66d13c76c448425e0c56c1d8 -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Vnesite novo geslo za denarnico. &lt;br/&gt;Prosimo, uporabite geslo z vsaj &lt;b&gt;10 ali več naključnimi simboli&lt;/b&gt; ali vsaj osmimi besedami.&lt;b&gt;</translation>
    
ERR
The translation is mostly accurate but contains two issues:
1. The closing <b> tag for "osmemi besedami" is missing, leading to potential formatting issues.
2. There's a small inconsistency in format for "10 ali več" ("ten or more"); for consistency with the rest, it should use "desetimi znaki ali več".

Correct translation:
Vnesite novo geslo za denarnico.&lt;br/&gt;Prosimo, uporabite geslo z &lt;b&gt;desetimi ali več naključnimi znaki&lt;/b&gt; ali z &lt;b&gt;osmimi ali več besedami&lt;/b&gt;.

Explanation:
- Both bold tags should be properly closed.
- Used the spelling out for "ten" as in the original English.
- Used "znaki" for "characters" (more idiomatic), and "besedami" for "words".
```

<!-- cache_translation_check_sl_aebed3bd7fbbc309572515ff20bbcc40f9676fe1d0ec12c2a9f5c93839ca8319 -->
```
        <source>&amp;About %1</source>
        <translation>&amp;O nas%1</translation>
    
ERR
Problems:
- The Slovene text "O nas" means "About us", which changes the meaning of "About %1" (should refer to the program/name in %1).
- There's no space between "nas" and "%1".
- Better Slovene phrasing is "O %1" or "O programu %1".

Correct translation (examples):
& O %1  -> "&O %1"
& O programu %1  -> "&O programu %1"

Both keep the %1 specifier and a single &. The recommended translation is:
& O programu %1  -> "&O programu %1"
```

<!-- cache_translation_check_sl_6f3f35f7aec94c0d51aca0eba05d73b9014e3e8a828dd2ec03f0ac7bfad6f411 -->
```
        <source>&amp;Options…</source>
        <translation>&amp;Možnosti ...</translation>
    
ERR
Whitespace and punctuation mismatch: the translation inserts a space before the ellipsis and uses three ASCII dots instead of the single ellipsis character as in the source. Also ensure the ampersand appears exactly once (it does).

Correct translation:
&amp;Možnosti…
```

<!-- cache_translation_check_sl_e5f88f844634dda35347add44c98a074082d5ffb2faea193894c3e83bf63f269 -->
```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Preverite, če je bilo prejeto sporočilo podpisano z določenim bitcoin-naslovom.</translation>
    
ERR
The translation is problematic. The source refers to verifying multiple messages and addresses in general ("messages", "Bitcoin addresses"), but the translation only refers to verifying if a received message was signed with a specific address ("prejeto sporočilo", "določenim bitcoin-naslovom"), which is not fully accurate and is overly specific.

Correct translation:
Preverite sporočila, da se prepričate, ali so bila podpisana z določenimi Bitcoin naslovi.
```

<!-- cache_translation_check_sl_801d0046b1eb0926b680204b023ea26087622c6f6e10d81ed3227ecd23f17e18 -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>&amp;Naloži DPBT iz datoteke...</translation>
    
ERR
The translation changes the acronym PSBT to "DPBT", which is incorrect — the acronym should be preserved as "PSBT". Also the source uses a single-character ellipsis (…) while the translation uses three dots; it's better to match the original ellipsis character. The ampersand is present exactly once, which is fine.

Correct translation:
&amp;Naloži PSBT iz datoteke…
```

<!-- cache_translation_check_sl_784c5e1384f7d210dd562b1ed2c95b237f335c7baba5b6aa9e87b935a00942ea -->
```
        <source>Synchronizing with network…</source>
        <translation>Dohitevam omrežje ...</translation>
    
ERR
The Slovenian translation uses three dots and a space (" ...") instead of the ellipsis character ("…") as in the source, and there is an unnecessary space before the dots. It should mirror the source's use of the ellipsis and formatting.

Correct translation:
Sinhronizacija z omrežjem…
```

<!-- cache_translation_check_sl_361ad34a371e43acf32955d2d4b84e418bf9a4e0a9a8761f2d9f804b60e26a07 -->
```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>Preglejte in uredite seznam naslovov, na katere ste kdaj prejeli plačila</translation>
    
ERR
The translation changes the meaning of the source text. The English source says "Show the list...", while the translation says "Preglejte in uredite seznam..." (Review and edit the list...). Additionally, the translation adds "na katere ste kdaj prejeli plačila" (to which you have ever received payments), which is overly descriptive compared to the source "receiving addresses and labels".

Correct translation:
Prikaži seznam uporabljenih naslovov za prejemanje in oznak
```

<!-- cache_translation_check_sl_5373ceaca57fe90d4f4ef222e812ebced777eb2fab71d0c447cd6d5db30544e4 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>Naloži DPBT z &amp;odložišča...</translation>
    
ERR
The acronym PSBT was incorrectly changed to "DPBT". Also the Slovene preposition should be "iz" before "odložišča" (which starts with a vowel). The ampersand shortcut exists exactly once, which is fine. Use the same ellipsis character as in the source.

Correct translation:
Naloži PSBT iz &odložišča…
```

<!-- cache_translation_check_sl_0e880fddb1648bb3ad806eabb8de4b31581d7f2b59c55c66c6743c64813d0d11 -->
```
        <source>&amp;Sending addresses</source>
        <translation>&amp;Naslovi za pošiljanje ...</translation>
    
ERR
Problems:
- Unnecessary ellipsis " ..." and a stray space before it. UI label shouldn't have ellipsis.
- The ampersand & is present exactly once (good), but the extra dots/spaces make it inconsistent with source.

Correct translation:
&amp;Naslovi za pošiljanje
```

<!-- cache_translation_check_sl_9b9ef05956d690f33d9b26c221aa16346e2022907b1d05fb6c70890b350b7548 -->
```
        <source>Quantity:</source>
        <translation>Št. vhodov:</translation>
    
ERR
The translation "Št. vhodov:" means "Number of inputs:" and is not an accurate translation of "Quantity:". "Quantity" should be translated as "Količina" or "Število".

Correct translation:
Količina:
or
Število:
```

<!-- cache_translation_check_sl_a27366d2b3d61bfaddfaf17bfde7895d670c1daca74b6be8c18a0cca81166e59 -->
```
        <source>Received with label</source>
        <translation>Oznaka priliva</translation>
    
ERR
The translation "Oznaka priliva" is not accurate. The English phrase "Received with label" refers to the label associated with a received Bitcoin transaction or address. A more accurate Slovenian translation would be "Prejeto z oznako".

Correct translation:
Prejeto z oznako
```

<!-- cache_translation_check_sl_57fe9bd15c5d2e32f1eef891cdf3a23c579ff47f14e3e31462e22a96d139ad03 -->
```
        <source>Received with address</source>
        <translation>Naslov priliva</translation>
    
ERR
The translation "Naslov priliva" is not an accurate translation of "Received with address" in the context of Bitcoin. "Naslov priliva" literally means "address of inflow" and does not clearly convey that a payment was received using a specific address. The commonly used and accurate translation would be "Prejeto na naslov" or "Prejeto z naslovom," which directly means "Received at address" or "Received with address."

Correct translation:
Prejeto na naslov
```

<!-- cache_translation_check_sl_81794c5ac1b4db15bc8dd9f7adbe79fbce90525a212865a3d6cd745219a1474a -->
```
        <source>L&amp;ock unspent</source>
        <translation>&amp;Zakleni nepotrošene</translation>
    
ERR
The Slovenian wording "Zakleni nepotrošene" is understandable but slightly non-idiomatic. A more natural translation uses "neporabljene" for "unspent".

Correct translation:
&Zakleni neporabljene

(ampersand kept once for the shortcut)
```

<!-- cache_translation_check_sl_39d0e79100eddb31815418577877fb98dbacc61a7645b551c66900867e327475 -->
```
        <source>&amp;Unlock unspent</source>
        <translation>&amp;Odkleni nepotrošene</translation>
    
ERR
The Slovenian translation "&Odkleni nepotrošene" is awkward/incomplete: the adjective "nepotrošene" (unspent) is left without a noun. A more natural and complete translation is "&Odkleni neporabljene izhode" (Unlock unspent outputs). The ampersand is present exactly once — keep it before the first word as shown.
```

<!-- cache_translation_check_sl_2c777168f7b44f49abe65266e613904093c0031665776a6cfb9688ae37a3c572 -->
```
        <source>External signer</source>
        <translation>Zunanji podpisni</translation>
    
ERR
The translation is slightly incorrect. The word "podpisni" is not suitable; the correct term should be "podpisnik", which means "signer" in Slovenian.

Correct translation:
Zunanji podpisnik
```

<!-- cache_translation_check_sl_1df098f7206ca1520398f6105831260f46a9a4e11eeb417682482378f1fbb3cc -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Prevedeno brez podpore za zunanje podpisovanje</translation>
    
ERR
The translation omits the phrase "(required for external signing)", making it incomplete. The format specifier is not present, but in this source, none exist, so that's not an issue. However, the completeness of content is an issue.

Correct translation:
Prevedeno brez podpore za zunanje podpisovanje (potrebno za zunanje podpisovanje)
```

<!-- cache_translation_check_sl_29998a5117c8dcc9e0867f95ff3a6f65353d90b382e082b2213f2cc9f3e44333 -->
```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>%1 trenutno dohiteva omrežje. Od soležnikov bodo preneseni in preverjeni zaglavja in bloki do vrha verige.</translation>
    
ERR
The translation omits some meaning and is slightly inaccurate. "trenutno dohiteva omrežje" literally means "is currently catching up the network," which is a bit awkward and could be misinterpreted. "It will download headers and blocks from peers and validate them..." is rendered awkwardly as well. Also, "do vrha verige" means "to the top of the chain" instead of "until reaching the tip of the block chain," which is understandable but could be more precise.

Correct translation:
%1 se trenutno sinhronizira. Prenesel bo zaglavja in bloke od soležnikov ter jih preveril, dokler ne doseže vrha verige blokov.
```

<!-- cache_translation_check_sl_58af8611824236834c817703da97c25c0f970ff0f10cef956c25f82e902c8474 -->
```
        <source>Size of &amp;database cache</source>
        <translation>Velikost &amp;predpomnilnika podatkovne baze:</translation>
    
ERR
The translation is mostly correct Slovenian, but it adds an extra trailing colon that is not present in the source. Also the ampersand is allowed anywhere but should appear exactly once (it does). Remove the colon to match the source.

Correct translation:
Velikost &predpomnilnika podatkovne baze
```

<!-- cache_translation_check_sl_3cd769f5ba89a250ee79c8ae034dfa079465b6b18c1c9a992fba9591861b8fd3 -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>Število programskih &amp;niti za preverjanje:</translation>
    
ERR
The translation adds a trailing colon that isn't present in the source, and the colon should be removed. Otherwise the wording is acceptable and the single & is used exactly once.

Correct translation:
Število programskih &niti za preverjanje
```

<!-- cache_translation_check_sl_cfb90bec671a6d858fd54e063384f7c1768d4c4a78d308259753642bb22cdfe7 -->
```
        <source>Enable R&amp;PC server</source>
        <extracomment>An Options window setting to enable the RPC server.</extracomment>
        <translation>Omogoči RPC-strežnik</translation>
    
ERR
The translation is missing the shortcut ampersand found in the source ("R&amp;PC"). The source contains one '&' (escaped as &amp;); the translation must include exactly one ampersand as well. Also keep "RPC" intact; using a hyphen for "RPC-strežnik" is fine.

Correct translation:
Omogoči R&amp;PC-strežnik
```

<!-- cache_translation_check_sl_15222e20dcdd8daba64a7e901d261ecf0560ef0f1e069b031d6e00c5a1881856 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>Omogoči &amp;trošenje vračila iz še nepotrjenih plačil</translation>
    
ERR
The translation mixes dialect/word forms and is awkward/unnatural in Slovenian ("trošenje", "vračila" forms) and the phrase structure is not clear. The ampersand is present once (good), but the wording should be natural Slovenian.

Suggested correct translation:
&amp;Dovoli porabo še nepotrjenega vračila
```

<!-- cache_translation_check_sl_c596fc7438f2638aac45ef732e1b874f8a91e98320b536fe6b26c141ed698c10 -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Omogoči nastavitve &amp;DPBT</translation>
    
ERR
The translation incorrectly changes the acronym "PSBT" to "DPBT" and uses "nastavitve" (settings) instead of a closer rendering of "controls". The acronym should remain "PSBT" as in the source, and the ampersand should appear exactly once.

Correct translation:
Omogoči &PSBT kontrole
```

<!-- cache_translation_check_sl_5c2c8961830eab29bd721e136fb67a92ac10f879eca243781dbd7a6980b36c1f -->
```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Ali naj se prikaže upravljanje z DPBT</translation>
    
ERR
There is a typographical error in the translation: "DPBT" instead of "PSBT". Also, the translation could be a bit more explicit to match the original meaning.

Correct translation:
Ali naj se prikaže upravljanje s PSBT.

This keeps the term "PSBT" as in the original, which is a specific technical acronym.
```

<!-- cache_translation_check_sl_ebd0df2cf707e905bf345af6ef9426234d243db8344ff93a33f34cc4e0fac837 -->
```
        <source>&amp;External signer script path</source>
        <translation>&amp;Pot do zunanjega podpisnika</translation>
    
ERR
The translation is understandable but omits the word "script" — "Pot do zunanjega podpisnika" reads more like "Path to external signer" (signer person/program) rather than specifically "External signer script path". The shortcut marker (&) is present exactly once, which is correct.

Correct translation:
&Pot do skripta zunanjega podpisnika
```

<!-- cache_translation_check_sl_8b724049fd9ef77d753ec592c83f5495037ab891c54bbe61b18b79b338903585 -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>&amp;Minimiraj na pladenj namesto na opravilno vrstico</translation>
    
ERR
The translation is understandable but has minor issues with verb form and preposition choice in Slovenian. "Minimiraj" is nonstandard (prefer "Minimiziraj") and "na pladenj" should be "v pladenj" (or better "v sistemski pladenj"). The ampersand is present exactly once, and there are no format-specifier or spacing problems.

Suggested correct translation:
&Minimiziraj v sistemski pladenj namesto v opravilno vrstico
```

<!-- cache_translation_check_sl_ca5321bd06d7fe616999d8751c8d63373709843705a6958a60de9b8c72a37e9a -->
```
        <source>M&amp;inimize on close</source>
        <translation>Ob zapiranju okno zgolj m&amp;inimiraj</translation>
    
ERR
The translation is grammatically incorrect and contains a misspelling. Problems:
- "Ob zapiranju okno zgolj s&inimiraj" uses nominative "okno" where genitive "okna" is required.
- "zgolj" ("only") is awkwardly placed and unnecessary compared to the source.
- "s&inimiraj" is misspelled (and the ampersand placement within that misspelling is odd).

Suggested correct translation (with a single & for the shortcut):
Ob zapiranju okna &minimiziraj
```

<!-- cache_translation_check_sl_084a054e6c6422cd896b382748e294e5e10a3753f72216ec7d51adb6d939b7ff -->
```
        <source>&amp;Third-party transaction URLs</source>
        <translation>&amp;Zunanji URL-ji</translation>
    
ERR
The translation "&Zunanji URL-ji" reads as "External URLs" and omits the "third-party" and "transaction" meaning from the source. It is therefore not an accurate rendering.

Suggested correct translations:
- &URL-ji tretjih oseb za transakcije
or
- &URL-ji tretjih strani za transakcije
```

<!-- cache_translation_check_sl_88e98efca4194629381b4950ecdf87b9150574872ad5f56bbb971fe7465f7247 -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Uporabi ločen posredniški strežik SOCKS5 za povezavo s soležniki prek storitev onion (Tor):</translation>
    
ERR
The translation contains typographical errors and omits the required shortcut ampersand from "SOCKS&amp;5". Specifically:
- "strežik" should be "strežnik".
- "soležniki" is incorrect for "peers" (use "vrstniki").
- The original contains one ampersand (SOCKS&amp;5) for the accelerator; the translation removed it. The ampersand must appear exactly once.

Corrected translation:
Uporabi ločen posredniški strežnik SOCKS&5 za doseganje vrstnikov prek Tor onion storitev:
```

<!-- cache_translation_check_sl_1df098f7206ca1520398f6105831260f46a9a4e11eeb417682482378f1fbb3cc -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Prevedeno brez podpore za zunanje podpisovanje</translation>
    
ERR
The translation omits the phrase "(required for external signing)", making it incomplete. The format specifier is not present, but in this source, none exist, so that's not an issue. However, the completeness of content is an issue.

Correct translation:
Prevedeno brez podpore za zunanje podpisovanje (potrebno za zunanje podpisovanje)
```

<!-- cache_translation_check_sl_c992f8711d7b5e3f0bbb118d4364a92038ca3a9faa469228917ddea52793cd53 -->
```
        <source>none</source>
        <translation>jih ni</translation>
    
ERR
The translation "jih ni" is informal and incomplete for "none," literally meaning "there are none." A more accurate, context-appropriate Slovenian translation for "none" is "brez," "nič," or "noben." The choice depends on the context, but "brez" (without) or "nič" (nothing/none) are standard.

Correct translation:
nič
```

<!-- cache_translation_check_sl_93a506bf2419851bb73b16b81a7e33dddce651a38fa6cd3369cd9036760ac18c -->
```
        <source>Client will be shut down. Do you want to proceed?</source>
        <extracomment>Text asking the user to confirm if they would like to proceed with a client shutdown.</extracomment>
        <translation>Program bo zaustavljen. Želite nadaljevati z izhodom?</translation>
    
ERR
The translation has a minor issue: "Program bo zaustavljen" means "The program will be stopped/shut down", which is fairly close. However, "Želite nadaljevati z izhodom?" means "Do you want to continue with the exit?", which, while understandable, does not directly mean "Do you want to proceed?". It's acceptable, but it would be clearer to more literally translate "Do you want to proceed?".

Correct translation:
Program bo zaustavljen. Ali želite nadaljevati?
```

<!-- cache_translation_check_sl_31a8d8462c0c61b5ab77a27e825375ef620cfe0060dffc745a112d210d038a19 -->
```
        <source>own address</source>
        <translation>lasten naslov</translation>
    
ERR
The translation "lasten naslov" is incorrect. The correct Slovenian translation for "own address" is "lastni naslov".

Correct translation:
lastni naslov
```

<!-- cache_translation_check_sl_5df5e36a49d92d0b308fe6e91f9f04e6829b69b98d99816460fefb815464fd5e -->
```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Ni mogoče zagnati rokovalca plačilnih povezav tipa bitcoin:.</translation>
    
ERR
The translation is mostly accurate in meaning, but the word order and punctuation are slightly awkward. The colon at the end does not correspond to the source. Also, "rokovalca plačilnih povezav tipa bitcoin" might be better phrased for clarity.

Correct translation:
Ni mogoče zagnati rokovalca za click-to-pay (bitcoin).
Or, staying closer to the source:
Ni mogoče zagnati rokovalca za bitcoin: click-to-pay.

Either is valid, but the main issue is the unnecessary colon and slightly awkward phrasing.
```

<!-- cache_translation_check_sl_596a7aa6a0f6a7ddf3332381fd4fba04ad9d9f166a5b66cef27eb92f3d0e28e1 -->
```
        <source>&amp;Save Image…</source>
        <translation>&amp;Shrani sliko ...</translation>
    
ERR
Issues:
- Extra space before the ellipsis and using three periods instead of the single Unicode ellipsis character. In Slovenian there should be no space before the ellipsis.
- Otherwise translation is correct and the & shortcut is present exactly once.

Correct translation:
&amp;Shrani sliko…
```

<!-- cache_translation_check_sl_d5b5838739bdd1be6e97f3ec4b6634467d05ef64695f835c825719c7b57b397b -->
```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Odhodna dostavljalka naslovov: krakoživa, zaproša za naslove</translation>
    
ERR
There is a typo in the word "krakoživa", which should be "kratkoživa". The phrase "Odhodna dostavljalka naslovov" is also slightly unnatural; "Odhodna pridobitev naslovov" or "Odhodna povezava za pridobivanje naslovov" would be clearer. Also, "zaproša za naslove" should be "za pridobivanje naslovov" (for obtaining addresses), since it refers to the purpose, not just the act of "soliciting".

Correct translation:
Odhodna povezava za pridobivanje naslovov: kratkoživa, za pridobivanje naslovov
```

<!-- cache_translation_check_sl_af33cfabfb698d685009d8f1451b53c5ca154c5815154262c7681e0038d4d621 -->
```
        <source>no high bandwidth relay selected</source>
        <translation>ni posredovanja na visoki pasovni širini</translation>
    
ERR
The translation is inaccurate. The English sentence "no high bandwidth relay selected" should be translated to indicate that no relay with high bandwidth has been chosen/selected. The current translation "ni posredovanja na visoki pasovni širini" means "no relaying on high bandwidth," which does not convey the intended meaning.

Correct translation:
ni izbranega releja z visoko pasovno širino
```

<!-- cache_translation_check_sl_25dfdaec4aa2d9462cb6440647aacb56e684f83a38b5274ad2da71bcc5b877e5 -->
```
        <source>Copy &amp;URI</source>
        <translation>Kopiraj &amp;URl</translation>
    
ERR
The translation has a capitalization typo: "URl" uses a lowercase L instead of uppercase I. The ampersand shortcut is present exactly once which is correct.

Correct translation:
Kopiraj &URI
```

<!-- cache_translation_check_sl_94b38fed999e17718398161168b37a526d73b7a35d2794b04e7d8ee2c75cfca2 -->
```
        <source>Request payment to …</source>
        <translation>Zahtevaj plačilo prejmeniku ...</translation>
    
ERR
The translation is inaccurate. "Prejmeniku" means "to the recipient," which is not present in the source. Also, the ellipsis character in the source is "…" (Unicode), but the translation uses three periods "...", which does not match formatting. The correct translation would simply mirror the original intent and punctuation.

Correct translation:
Zahtevaj plačilo …
```

<!-- cache_translation_check_sl_25dfdaec4aa2d9462cb6440647aacb56e684f83a38b5274ad2da71bcc5b877e5 -->
```
        <source>Copy &amp;URI</source>
        <translation>Kopiraj &amp;URl</translation>
    
ERR
The translation has a capitalization typo: "URl" uses a lowercase L instead of uppercase I. The ampersand shortcut is present exactly once which is correct.

Correct translation:
Kopiraj &URI
```

<!-- cache_translation_check_sl_596a7aa6a0f6a7ddf3332381fd4fba04ad9d9f166a5b66cef27eb92f3d0e28e1 -->
```
        <source>&amp;Save Image…</source>
        <translation>&amp;Shrani sliko ...</translation>
    
ERR
Issues:
- Extra space before the ellipsis and using three periods instead of the single Unicode ellipsis character. In Slovenian there should be no space before the ellipsis.
- Otherwise translation is correct and the & shortcut is present exactly once.

Correct translation:
&amp;Shrani sliko…
```

<!-- cache_translation_check_sl_9b9ef05956d690f33d9b26c221aa16346e2022907b1d05fb6c70890b350b7548 -->
```
        <source>Quantity:</source>
        <translation>Št. vhodov:</translation>
    
ERR
The translation "Št. vhodov:" means "Number of inputs:" and is not an accurate translation of "Quantity:". "Quantity" should be translated as "Količina" or "Število".

Correct translation:
Količina:
or
Število:
```

<!-- cache_translation_check_sl_b227dbcfdced27f47525dc292b6c6e31dd908da616cbbef9e47e8e0686d828bc -->
```
        <source>PSBT saved</source>
        <extracomment>Popup message when a PSBT has been saved to a file</extracomment>
        <translation>DPBT shranjena</translation>
    
ERR
The translation is problematic because "DPBT" is not the correct Slovenian abbreviation for "PSBT". "PSBT" (Partially Signed Bitcoin Transaction) is typically not translated or adapted and should remain "PSBT" in the translation. Everything else is correct.

Correct translation:
PSBT shranjena
```

<!-- cache_translation_check_sl_b6011870a5f01b5b1faafc6bffe5be7911f1eb713b14a1b6682b7dfeb48e0504 -->
```
        <source>PSBT saved to disk</source>
        <translation>DPBT shranjena na disk</translation>
    
ERR
There is an error in the abbreviation: "PSBT" (Partially Signed Bitcoin Transaction) should not be translated or changed in the abbreviation. The translation uses "DPBT", which is incorrect. The rest of the phrase is otherwise accurately translated.

Correct translation:
PSBT shranjena na disk
```

<!-- cache_translation_check_sl_b977086807dfb2231a79db745e022efece13fee5581ae2de352824523ba05946 -->
```
        <source>Sign the message to prove you own this Bitcoin address</source>
        <translation>Podpišite sporočilo, da dokažete lastništvo zgornjega naslova.</translation>
    
ERR
The translation is inaccurate. The original specifies "this Bitcoin address," but the translation says "lastništvo zgornjega naslova" ("ownership of the above address"), which is ambiguous, and omits "Bitcoin" ("Bitcoin naslov").

Correct translation:
Podpišite sporočilo, da dokažete, da ste lastnik tega Bitcoin naslova.
```

<!-- cache_translation_check_sl_31a8d8462c0c61b5ab77a27e825375ef620cfe0060dffc745a112d210d038a19 -->
```
        <source>own address</source>
        <translation>lasten naslov</translation>
    
ERR
The translation "lasten naslov" is incorrect. The correct Slovenian translation for "own address" is "lastni naslov".

Correct translation:
lastni naslov
```

<!-- cache_translation_check_sl_ce8a1b038361f2ffa9f1785994a00c9256d7eb70241528e61356447a5d2950e4 -->
```
        <source>Copy &amp;raw transaction</source>
        <translation>Kopiraj su&amp;rovo transkacijo</translation>
    
ERR
The Slovene word "transkacijo" is misspelled. It should be "transakcijo". The shortcut ampersand is fine (placed once).

Correct translation:
<translation>Kopiraj su&amp;rovo transakcijo</translation>
```

<!-- cache_translation_check_sl_86f02a60fb7efc22d811a2a0362540193fe2b60eafafa7c85beaee2a38dc89cf -->
```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>Velikost DPBT ne sme presegati 100 MiB.</translation>
    
ERR
The translation has an error: "DPBT" is not the correct Slovene equivalent for "PSBT". The abbreviation "PSBT" (Partially Signed Bitcoin Transaction) is standard and should be kept as "PSBT" in Slovenian as well. Otherwise, the rest of the translation is accurate.

Correct translation:
Velikost PSBT ne sme presegati 100 MiB.
```

<!-- cache_translation_check_sl_9e4610af319df8bb33489f365698872efaa953d091877074714f23f36f8780fc -->
```
        <source>Can't draft transaction.</source>
        <translation>Ne morem shraniti osnutka transakcije</translation>
    
ERR
The translation changes the meaning of the original message. The English source means "Ni mogoče sestaviti/ustvariti osnutka transakcije," but the provided translation means "I can't save the draft transaction," which is not the same.

Correct translation:
Ni mogoče sestaviti (ali: ustvariti) osnutka transakcije.
```

<!-- cache_translation_check_sl_858cb0220d8975a22b5f5b5c2e0e03b3e7dc7be188d34af314a5d5aadbd3a584 -->
```
        <source>File %s already exists. If you are sure this is what you want, move it out of the way first.</source>
        <translation>Datoteka %s že obstaja. Če stre prepričani, da to želite, obstoječo datoteko najprej odstranite oz. premaknite.</translation>
    
ERR
There is a typo in the translation: "stre prepričani" should be "ste prepričani" ("stre" is incorrect in Slovenian). The phrase could also be made slightly clearer and more idiomatic.

Correct translation:
Datoteka %s že obstaja. Če ste prepričani, da to želite, obstoječo datoteko najprej odstranite ali premaknite.
```

<!-- cache_translation_check_sl_85570487095092ceaf660d3c820dc36e58c636edb24eb3afe066bf0919fbaf75 -->
```
        <source>Error loading %s: Wallet corrupted</source>
        <translation>Napaka pri nalaganju %s: Denarnica ovkarjena</translation>
    
ERR
There is a typo in the Slovenian word for "corrupted": "ovkarjena" is incorrect. The correct word is "poškodovana".

Correct translation:
Napaka pri nalaganju %s: Denarnica poškodovana
```

<!-- cache_translation_check_sl_aa2a36673734a05de1534f2447e0c953f94c1733391e5e27b239830cbf258ed9 -->
```
        <source>Error reading configuration file: %s</source>
        <translation>Napaka pri branju nastavitvene datoteke: 1%s</translation>
    
ERR
The translation incorrectly inserts "1" before the format specifier ("1%s"). The "%s" placeholder must be preserved exactly and not altered.

Correct translation:
Napaka pri branju konfiguracijske datoteke: %s
```

<!-- cache_translation_check_sl_567d6a54984ca6c8de5e03485f0b1724035a84960599a9bf4009f7c38dae2b94 -->
```
        <source>Failed to rescan the wallet during initialization</source>
        <translation>Med inicializacijo denarnice ni bilo mogoče preveriti zgodovine (rescan failed).</translation>
    
ERR
The translation is not fully accurate. The English sentence says "Failed to rescan the wallet during initialization". The Slovenian translation says "During wallet initialization, it was not possible to check history (rescan failed)." This is not fully faithful, and the addition "(rescan failed)" is unnecessary in Slovenian, and "preveriti zgodovino" does not precisely convey "rescan the wallet".

Correct translation:
Med inicializacijo denarnice ni bilo mogoče ponovno pregledati denarnice.
```

<!-- cache_translation_check_sl_31ae29cfec475b611eddca52b7b63b65c46725337eb286234b555b3ffcc271ce -->
```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s'</source>
        <translation>Neveljaven znesek za %s=&lt;amount&gt;:'%s'</translation>
    
ERR
There is a minor spacing issue: there should be a space after the colon, matching the English source.

Correct translation:
Neveljaven znesek za %s=&lt;amount&gt;: '%s'
```

<!-- cache_translation_check_sl_324348fd804f07e9f85554d77f2944cfed656fb3bfcd4589a7decfd66972b1ae -->
```
        <source>Loading P2P addresses…</source>
        <translation>Nalagam P2P naslove ...</translation>
    
ERR
The Slovenian translation uses three periods "..." instead of the correct ellipsis character "…", as in the source. Also, there should be no extra spaces before the ellipsis.

Correct translation:
Nalagam P2P naslove…
```

<!-- cache_translation_check_sl_043df0bd24b2d04be13a42aa61ba63bed6819c88679a4c651d6f21224c8f2cb9 -->
```
        <source>Pruning blockstore…</source>
        <translation>Obrezujem ...</translation>
    
ERR
The translation "Obrezujem ..." is not fully accurate. The term "blockstore" is missing from the translation, and the ellipsis "..." does not follow the source, which uses a single Unicode ellipsis character (…).

Correct translation:
Obrezujem shrambi blokov…
```
</details>

Number of issues: 55.
