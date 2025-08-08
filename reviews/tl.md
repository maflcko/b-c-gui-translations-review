# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>tl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Btl%5D%20low%20quality)


<!-- cache_translation_check_tl_a517053c17cd28bc770f39bfa765fcb2d2dc840f12afbf1a49b527198ed638b9 -->
```
        <source>Right-click to edit address or label</source>
        <translation>pindutin lamang ang kanang pindutan upang i-edit ang address o label.</translation>
    
ERR  
The translation uses a conversational phrasing and does not maintain the capital letter at the start. "Pindutin lamang ang kanang pindutan upang i-edit ang address o label." translates more as "Just press the right button to edit the address or label," which adds "lamang/just" and misses the nuance of "right-click" (which refers specifically to clicking the right mouse button, not just pressing it). The translation should adhere more closely to computer terminology.

Correct translation:  
I-right click upang i-edit ang address o label.
```

<!-- cache_translation_check_tl_367f53f4d47cfbccf88bf484bab55099f3afe9087f0f56ad00434ca9f6358d17 -->
```
        <source>Create a new address</source>
        <translation>Lumikha ng bagong ♦address♦</translation>
    
ERR
The translation incorrectly includes the symbols "♦" around "address", and "address" is not translated into Filipino/Tagalog. It should be translated into proper Filipino, and unnecessary characters should be removed.

Correct translation:
Lumikha ng bagong address
```

<!-- cache_translation_check_tl_98aa54cb462863c7ceff2cac18a4c7e3a45b8d47766d3bb733131e7245d403e9 -->
```
        <source>Copy the currently selected address to the system clipboard</source>
        <translation>Gayahin ang pinipiling ♦address♦ sa kasalakuyan sa ♦clipboard♦ ng sistem</translation>
    
ERR
The translation is inaccurate. The word "address" is unnecessarily enclosed in symbols (♦address♦) instead of being properly translated. "Kasalakuyan" is a misspelling of "kasalukuyan", and "clipboard" is also unnecessarily enclosed in symbols. The sentence contains awkward phrasing and direct transliterations instead of natural Filipino.

Correct translation:
Kopyahin ang kasalukuyang napiling address sa clipboard ng sistema
```

<!-- cache_translation_check_tl_a4eb143cfa96614545e82b4685293de0addccc043fbc69a1f468bf4b2f7add1d -->
```
        <source>Close</source>
        <translation>(Do you mean: Close?) :isara, sarado </translation>
    
ERR
The translation includes unnecessary English text ("(Do you mean: Close?)") and two synonyms ("isara, sarado"), which is awkward and unprofessional. The translation should simply be the Filipino word for "Close".

Correct translation:
Isara
```

<!-- cache_translation_check_tl_45d8b4a185cb8bbafab2277701ac00895b1f1eeba1f6d8c646e17500ec9bfdb7 -->
```
        <source>Choose the address to send coins to</source>
        <translation>Piliin ang ♦address♦ kung saan ipapadala ang mga barya</translation>
    
ERR
The translation uses the placeholder "♦address♦" which is unnecessary and incorrect in Filipino; the word "address" should simply be "address" (as borrowed), or "tirahan" if clarified. Also, "barya" for "coins" is technically correct, but in the Bitcoin context, "mga coin" or even just "Bitcoin" is better for clarity. There are no whitespace issues, but the translation introduces a confusing symbol not present in the original.

Correct translation:
Piliin ang address kung saan ipapadala ang mga coin
```

<!-- cache_translation_check_tl_f7f61c5a66f4a917e0277d2ce55104c191540f27277345457f8aede5adaab460 -->
```
        <source>Choose</source>
        <translation>(do you mean: CHOOSE?) ;Pumili,Piliin.</translation>
    
ERR
The translation is problematic for several reasons:
- It contains English meta-commentary ("(do you mean: CHOOSE?) ;") which is not appropriate in production software.
- Multiple translations are listed without context ("Pumili,Piliin."). Only the correct one should be used based on the context.
- There is an unnecessary semicolon and stray punctuation.

Correct translation:
Pumili
```

<!-- cache_translation_check_tl_2fa3e31f76eb75253bbaddda418d469686ad6fe7a1a82dcffa03d472fc924760 -->
```
        <source>Copy Address</source>
        <translation>Kopyahin ang ♦Address♦</translation>
    
ERR
The translation incorrectly includes the special characters "♦" around the word "Address", which are not present in the source and may confuse users. Also, "Address" should be translated to Filipino as "address" or "adres", unless referring to a specifically untranslated technical term—but in UI translations, "address" is often rendered as "address" for clarity in the Bitcoin context. There is no whitespace or format specifier issue.

Correct translation:
Kopyahin ang Address

Alternatively, if "address" is to be localized:
Kopyahin ang Adres
```

<!-- cache_translation_check_tl_92ee6a77281da23df6c9704d3b53f54937123a9033392941def5cf299e4d2f78 -->
```
        <source>Address</source>
        <translation>♦Address♦</translation>
    
ERR
The translation is problematic: the inclusion of "♦" symbols is unnecessary and was not present in the original source. The word "Address" should be translated into Filipino (Tagalog) if an appropriate term exists, or left as is if it's commonly used untranslated in the technical context, but without extraneous symbols.

Correct translation:
Address

Or, if a Filipino translation is appropriate:
Adres
```

<!-- cache_translation_check_tl_b4448b51b797a2b5f5fba868b038709fe456d1772864ee382996558556253806 -->
```
        <source>Passphrase Dialog</source>
        <translation>♦Passphrase♦ na ♦Dialog♦</translation>
    
ERR
The translation is incorrect and contains extraneous symbols (♦), which are not appropriate. The words "Passphrase" and "Dialog" are left untranslated and simply wrapped with these symbols, which is not standard in Filipino (tl) translations.

Correct translation:
Dialog ng Passphrase
```

<!-- cache_translation_check_tl_bcb5f9aa1535d599cc35c54fb82e36df776bfc8a6ab1cc07ac5f0faf32c542da -->
```
        <source>Enter passphrase</source>
        <translation>Ilagay ang ♦passphrase♦</translation>
    
ERR  
The translation uses decorative symbols "♦" around "passphrase," which are not present in the source. This is unnecessary and nonstandard for UI localization. Also, "Ilagay ang passphrase" is otherwise appropriate.

Correct translation:  
Ilagay ang passphrase
```

<!-- cache_translation_check_tl_f21b4bc6a7adc6d9501a8b3e2db7f38362c6e130ac3b836736ffaf6a07201784 -->
```
        <source>New passphrase</source>
        <translation>Bagong ♦passphrase♦</translation>
    
ERR
The translation adds unnecessary special characters (♦) around "passphrase", which are not present in the source and may confuse users. Also, "passphrase" is often kept untranslated in localizations for technical contexts, but the extra decoration is problematic.

Correct translation:
Bagong passphrase
```

<!-- cache_translation_check_tl_8aafa7db7e4813b29597c3cfd3ac83326339aba025e6a8fa04cc1653dad214b8 -->
```
        <source>Repeat new passphrase</source>
        <translation>Ulitin ang bagong ♦passphrase♦</translation>
    
ERR
The translation introduces unnecessary symbols (♦) around "passphrase", which are not present in the source and could confuse users. Also, "passphrase" is often untranslated in IT contexts, but the extra symbols are problematic.

Correct translation:
Ulitin ang bagong passphrase
```

<!-- cache_translation_check_tl_bcae1ad3df75737a2700005421a690939f048716ca596a1ed53a734de8dbf6f3 -->
```
        <source>Change passphrase</source>
        <translation>Palitan ang ♦passphrase♦</translation>
    
ERR
The translation uses unnecessary decorative characters (♦) surrounding "passphrase", which is not standard and may confuse users. The correct translation should be:

Correct translation:
Palitan ang passphrase
```

<!-- cache_translation_check_tl_8b76bdaf404b6ebaa6123e5343141a925b9e7c20b8a1cbd09fdc3cdb9cab2e0c -->
```
        <source>Confirm wallet encryption</source>
        <translation>Kumpirmahin ang ♦encryption♦ ng pitaka</translation>
    
ERR
The translation has unnecessary symbols ("♦") around the word "encryption", which are not present in the source text and should not be there. Also, "encryption" should ideally be translated to "pag-e-encrypt" or "pag-encrypt" for clarity in Filipino.

Correct translation:
Kumpirmahin ang pag-encrypt ng pitaka
```

<!-- cache_translation_check_tl_554e7c62c8cc54c3b9ced90e9e7f7626f1172c2b4ec6c436702207e0fbda8746 -->
```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Babala: IKung i-encrypt mo ang iyong pitaka at mawawala ang ♦passphrase♦,  &lt;b&gt;MAWAWALA MO ANG LAHAT NG IYONG MGA BITCOIN&lt;/b&gt;!</translation>
    
ERR
There are several issues:
- "IKung" should be "Kung" (extraneous "I" at the start).
- The "♦" characters around 'passphrase' are erroneous and unnecessary.
- "pitaka" is correct for "wallet", but contextually "mawawala" should be "mawala" (future tense is better: "mawawala sa iyo"), but "mawawala" as "will lose" is okay.
- "MO ANG LAHAT NG IYONG MGA BITCOIN" is a bit wordy; "ang lahat ng iyong Bitcoin" or "lahat ng iyong Bitcoin" is better.
- Format specifiers are preserved (none), and HTML tags are correctly copied.
- Whitespace before the HTML tag is slightly incorrect (unnecessary space before "&lt;b&gt;").

Correct translation:
Babala: Kung i-encrypt mo ang iyong pitaka at mawalan ka ng passphrase, &lt;b&gt;MAWAWALA LAHAT NG IYONG BITCOIN&lt;/b&gt;!
```

<!-- cache_translation_check_tl_797b428e4e1b157c652db2ed9e1db143d31f147844386265d1bf919c4a5c85a7 -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Ilagay ang bagong ♦passphrase♦ para sa pitaka.&lt;br/&gt;Pakigamit ang ♦passphrase♦ of &lt;b&gt;sampu o higit pa na mga ♦random♦ na mga karakter&lt;/b&gt;, o &lt;b&gt;walo o higit pang mga salita&lt;/b&gt;.</translation>
    
ERR
There are several issues with the translation:
- The word "♦passphrase♦" and "♦random♦" are not proper in Filipino and seem to be placeholders or erroneous insertions.
- The phrase "passphrase of sampu o higit pa na mga random na mga karakter" is not fluent. "Random characters" should be translated to proper Filipino, e.g., "hindi magkakaugnay na mga titik o character".
- "walo o higit pang mga salita" is a correct translation for "eight or more words".

Correct translation:
Ilagay ang bagong passphrase para sa pitaka.&lt;br/&gt;Mangyaring gumamit ng passphrase na &lt;b&gt;sampu o higit pang mga hindi magkakaugnay na karakter&lt;/b&gt;, o &lt;b&gt;walo o higit pang mga salita&lt;/b&gt;.
```

<!-- cache_translation_check_tl_4ed2c3bccf6947ed8ac82b385513c7d0a620a1831e978df18c5a6ce6f993baab -->
```
        <source>The supplied passphrases do not match.</source>
        <translation>Ang mga ibinigay na mga ♦passphrase♦ ay hindi nagtugma.</translation>
    
ERR
The translation uses unnecessary markers "♦" around "passphrase", which are not present in the source. Additionally, "mga" is redundantly used twice with "ibinigay na mga", which can make the phrase sound awkward, and "passphrases" could be better rendered in a more natural way for Filipino users.

Correct translation:
Ang mga ibinigay na passphrase ay hindi magkatugma.
```

<!-- cache_translation_check_tl_ec4e05381c7bd801f73c281f5a881dbf8639db3e19889ddd5a38ec45e1269dbe -->
```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Ang ♦passphrase♦ na ipinasok sa ♦decryption♦ sa pitaka ay hindi tama.</translation>
    
ERR
The translation contains unnecessary English words "passphrase" and "decryption" that have not been localized, and the use of "♦" is inappropriate and not standard in Filipino ('tl') translations. This could lead to misunderstandings or look unprofessional.

Correct translation:
Ang passphrase na inilagay para sa pag-decrypt ng pitaka ay mali.

Or, for a more natural flow:
Mali ang ipinasok na passphrase para sa pag-decrypt ng pitaka.
```

<!-- cache_translation_check_tl_3e31dccd6b572f59a08104221029355ccb520bc14fcee01f0bb083b1f270fe6b -->
```
        <source>Warning: The Caps Lock key is on!</source>
        <translation>Babala: Ang ♦Caps Lock Key♦ ay naka-on!</translation>
    
ERR
The translation unnecessarily adds "♦" symbols around "Caps Lock Key", which are not present in the original English text. The inclusion of 'Key' is acceptable, but the styling with symbols is not standard and could be considered unwanted formatting.

Correct translation:
Babala: Naka-on ang Caps Lock!
```

<!-- cache_translation_check_tl_977ab0f87f7149e47b1495fa241c8727a6d15d64fbe36f40dfa370de0ea57e68 -->
```
        <source>Do you want to reset settings to default values, or to abort without making changes?</source>
        <extracomment>Explanatory text shown on startup when the settings file cannot be read. Prompts user to make a choice between resetting or aborting.</extracomment>
        <translation>Gusto mo bang i-reset ang mga ♦setting♦ sa ♦default♦ na mga ♦value♦, o itigil na hindi gumagawa ng mga pagbabago?</translation>
    
ERR
The translation uses the English words "setting," "default," and "value," surrounded by unconventional symbols (♦) instead of Filipino equivalents. This is awkward and not in standard Tagalog. The format specifier or wording is not carried over precisely. The translation should use Tagalog terms and avoid unnecessary symbols.

Correct translation:
Gusto mo bang i-reset ang mga setting sa mga default na halaga, o itigil nang hindi gumagawa ng anumang pagbabago?

Alternatively, to localize further (optional):
Nais mo bang i-reset ang mga setting sa mga paunang halaga, o itigil nang hindi nagbabago ng anuman?
```

<!-- cache_translation_check_tl_f0b16b8c75c39a41ab8252b955853743e86a41b4648053633c731a19a3293677 -->
```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>Isang malubhang pagkakamali ang naganap. Suriin ang mga ♦setting♦ ng ♦file♦ na ♦writable♦, o subukan na patakbuhin sa ♦-nosettings♦.</translation>
    
ERR  
The translation uses the English words "setting", "file", "writable", and "-nosettings" wrapped with ♦, which is incorrect for a proper Filipino (Tagalog) translation. These terms should be translated or at least adapted more naturally into Tagalog. It also inaccurately refers to "mga setting ng file" instead of "settings file" ("file ng mga setting"), and doesn't capture the prompt to check if it's writable—"na maaaring sulatan."

Correct translation:  
Isang malubhang pagkakamali ang naganap. Suriin kung ang file ng mga setting ay maaaring sulatan, o subukang patakbuhin gamit ang -nosettings.
```

<!-- cache_translation_check_tl_5ccf4ffb280b241960dcfab468483390cea44bf82a0c124f21d2d5c58504b4e7 -->
```
        <source>default wallet</source>
        <translation>pitaka na ♦default♦</translation>
    
ERR  
The translation is problematic. "pitaka na ♦default♦" uses mixed language ("pitaka" is Tagalog for "wallet", but "default" is just kept in English, surrounded by decorative symbols "♦"). This is neither standard nor idiomatic in Filipino. Also, the "na" particle is unnecessary. The correct translation should be:

Correct translation:  
default na pitaka

(Note: In Filipino UI, "default na pitaka" is standard, but sometimes "nakatalagang pitaka" or "pangunahing pitaka" can be used for "default wallet".)
```

<!-- cache_translation_check_tl_998b9a966b99ba2693535dca1022d691895eeb6ead5cbed369688c9d9688a8ec -->
```
        <source>Modify configuration options for %1</source>
        <translation>Baguhin ang mga pagpipilian sa ♦configuration♦ para sa %1</translation>
    
ERR  
The word "configuration" should be translated to Filipino as "konpigurasyon" or "pagkonpigurasyon". Additionally, the use of the special characters "♦" is unnecessary and problematic.

Correct translation:  
Baguhin ang mga pagpipilian sa konpigurasyon para sa %1
```

<!-- cache_translation_check_tl_04b1c3ddd0aa0cac8552cfd3a9a8ef39150ff416d895b6e9c19231c1a8907cba -->
```
        <source>Network activity disabled.</source>
        <extracomment>A substring of the tooltip.</extracomment>
        <translation>Na-disable ang aktibidad ng ♦network♦</translation>
    
ERR
The translation has two issues:
1. The English term "disabled" should be translated as "Hindi aktibo" or "Hindi pinagana", which more accurately reflects "disabled" rather than using the borrowed "na-disable".
2. The use of "♦network♦" is unusual and not idiomatic; "network" should be translated as "network" if the English term is retained intentionally, or "network" can be "network" or "nag-network" in Tagalog, but best is "network" if the interface uses English terms. However, the ♦ symbols are not natural.

Correct translation:
Hindi aktibo ang aktibidad ng network.
```

<!-- cache_translation_check_tl_42b7479210fdd365e16c61ed93cc12ab727c05222faa21cedfed3335c6959d0b -->
```
        <source>Send coins to a Bitcoin address</source>
        <translation>Magpadala ng mga ♦coin♦ sa ♦address♦ ng Bitcoin</translation>
    
ERR
The translation incorrectly retains English words with surrounding symbols (♦coin♦, ♦address♦), which is not idiomatic in Filipino ('tl'). The correct approach is to use natural Filipino phrasing, possibly keeping "Bitcoin address" untranslated as it is often the convention, but translating "Send coins" into proper Filipino.

Correct translation:
Magpadala ng mga coin sa Bitcoin address

Or, if "coin" is to be translated:
Magpadala ng mga barya sa Bitcoin address

Note: If "coins" refers specifically to cryptocurrency, it's standard to leave "coin" as is. Remove the special symbols (♦) and avoid unnecessary English unless standard in the context.
```

<!-- cache_translation_check_tl_f0c2ade417ebc2119fc7691cc23f1388beb240b207d46b32e09a8462b9b7cc1e -->
```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Palitan ang ♦passphrase♦ na ginamit para sa pag-encrypt sa pitaka</translation>
    
ERR
The translation is mostly correct, but the use of special characters "♦passphrase♦" is unnecessary and not standard in 'tl'. Also, the preposition should be "ng" instead of "sa" for "pag-encrypt ng pitaka".

Correct translation:
Palitan ang passphrase na ginamit para sa pag-encrypt ng pitaka
```

<!-- cache_translation_check_tl_f724766031a37fd0c5f12604abcc675d6770bd1ce471165cb605333836de6b23 -->
```
        <source>Change Passphrase…</source>
        <translation>Palitan ang ♦Passphrase♦...</translation>
    
ERR
The translation introduces unnecessary symbols ("♦") around "Passphrase" and translates "…" (ellipsis) as "..." (three dots), which may not match interface conventions. Furthermore, "Passphrase" does not need to be surrounded by symbols. The word "Passphrase" is commonly left untranslated, but the translation should be clear and natural.

Correct translation:
Palitan ang Passphrase…
```

<!-- cache_translation_check_tl_099f7bf1dace526e67f1335cf75d1b56631b17735c43ffa958a3e840dd718735 -->
```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Tanda na mga mensahe sa mga ♦address♦ ng iyong ♦Bitcoin♦ para patunayan na pagmamay-ari mo sila</translation>
    
ERR
The translation contains unnecessary symbols (♦) around "address" and "Bitcoin", which are not present in the source and make the translation problematic and unnatural. Furthermore, "Tanda na mga mensahe" is not a natural way to say "Sign messages" in Tagalog. The correct term for "sign" in this context is "Lagdaan".

Correct translation:
Lagdaan ang mga mensahe gamit ang iyong mga Bitcoin address upang patunayan na ikaw ang may-ari ng mga ito
```

<!-- cache_translation_check_tl_4eefc2850b888a06d5266c014d05e397778970f5a300787261ca9d7d5c1ab7e1 -->
```
        <source>Load PSBT from file…</source>
        <translation>I-load ang PSBT mula sa ♦file♦...</translation>
    
ERR
The translation introduces '♦file♦', which is not present in the source. The ellipsis uses three dots '...' instead of the ellipsis character '…' from the source, and the format specifier should be preserved literally as in the source.

Correct translation:
I-load ang PSBT mula sa file…
```

<!-- cache_translation_check_tl_6c9a25fae523c92179cb4acb16ebd69290e8e7a9faa71013e7486aef5437d1a7 -->
```
        <source>Open URI…</source>
        <translation>Buksan ang ♦URL♦...</translation>
    
ERR
The translation introduces the symbols "♦" around "URL" which do not appear in the source and is non-standard. Also, the ellipsis should be the single Unicode character "…" not three dots ("..."). Furthermore, consistency with standard Filipino UI translations should use "Open" as "Buksan" but "URI" is often not localized. If translated, it would be "Buksan ang URI…"

Correct translation:
Buksan ang URI…
```

<!-- cache_translation_check_tl_0fb081f3120c8c8f8abe5d285c583ba2f3d67bbd4d5bc62264c2a809397c4ffc -->
```
        <source>File</source>
        <translation>♦File♦</translation>
    
ERR
The translation is problematic because it simply copies the English word "File" and adds unwanted characters (♦) around it, which is inappropriate and not a valid Filipino (tl) translation. Also, "File" as a menu item would typically be translated to "File" (retained in many UI contexts), or, if localization is needed, "File" in Filipino is "Talaksan".

Correct translation:
Talaksan
```

<!-- cache_translation_check_tl_77615ade3f200548bbe9ca0f802a2459b907c9c987c1ebceadee06d5a4122d08 -->
```
        <source>Settings</source>
        <translation>Mga ♦Setting♦</translation>
    
ERR
The translation includes non-standard characters "♦", which are not appropriate and may be considered spammy or erroneous in a UI context. Also, while "Setting" is sometimes left as-is in Filipino, the plural form "Mga Setting" is more appropriate, and the decorative symbols should be removed.

Correct translation:
Mga Setting
```

<!-- cache_translation_check_tl_71bd7dc66fb75ad1409a38fe1ed156d497ea2389afd2b604947ba61b3426eb30 -->
```
        <source>Syncing Headers (%1%)…</source>
        <translation>♦Syncing Headers♦ (%1%)…</translation>
    
ERR
The translation unnecessarily adds "♦" symbols around "Syncing Headers", which are not present in the source and may be considered unwanted content. Additionally, "Syncing Headers" is untranslated and should be in Filipino.

Correct translation:
Sinusynchronize ang mga header (%1%)…
```

<!-- cache_translation_check_tl_b12b387de1249c7f6ba424ddc3a0e5c16fa7e4708722bee7da700be1a1942409 -->
```
        <source>Synchronizing with network…</source>
        <translation>Sini-siynchronize sa ♦network♦...</translation>
    
ERR
There are several issues:
- The use of "Sini-siynchronize" is not idiomatic Tagalog/Filipino. The correct form is "Sinisynchronize" or better yet, a more natural Filipino translation should be used, like "Sinasabay sa network", "Sumasabay sa network", or "Ipinagsi-synchronize sa network".
- The phrase "♦network♦" is not appropriate; it should just be "network" or "sa network" if retained.
- Ellipsis formatting ("...") in Filipino is usually three dots without extra trailing spaces.
- Unwanted non-standard characters (♦) are present.

Correct translation:
Sinusynchronize sa network...
or
Sinasabay sa network...
or, more formally,
Sinusunod ang takbo ng network...
```

<!-- cache_translation_check_tl_975aa88a85ffb1861f6409e02314e5616b2869d199496805e3b0e7ea25990554 -->
```
        <source>Indexing blocks on disk…</source>
        <translation>Ini-index ang mga bloke sa ♦disk♦...</translation>
    
ERR
The translation uses ♦disk♦ which is unusual and nonstandard in Tagalog. It should simply use "disk" or its Filipino equivalent if there is one, but not with special characters. Otherwise, the meaning is clear, but the ellipsis should match the source (use the same number of dots, preferably three).

Correct translation:
Ini-index ang mga bloke sa disk...
```

<!-- cache_translation_check_tl_ef4f9b88e5171853d75c562f0630f38f6d41d654411a14794de0eb6cde8a89ed -->
```
        <source>Processing blocks on disk…</source>
        <translation>Pinoproseso ang mga bloke sa ♦disk♦...</translation>
    
ERR
The translation uses "♦disk♦", which is unidiomatic and contains unnecessary symbols. In Filipino ('tl'), "disk" is commonly translated as "disk" or "disco", depending on context. The ellipsis character "..." should be consistent with the source, which uses "…".

Correct translation:
Pinoproseso ang mga bloke sa disk…
```

<!-- cache_translation_check_tl_aa13ecf2eef291efbdd29076f223273b01b7c709d59639e2432b8c6db2ce3c31 -->
```
        <source>Connecting to peers…</source>
        <translation>Kumokonekta sa mga ♦peers♦...</translation>
    
ERR
The translation contains unnecessary symbols ("♦") around "peers" and did not localize "peers" into Filipino (usually "katambal", "kasamahan", or simply keeping the English "peers" if commonly used in the technical context). The ellipsis formatting ("...") should be aligned with the original, using the single Unicode ellipsis "…" if possible.

Correct translation:
Kumokonekta sa mga peer…
```

<!-- cache_translation_check_tl_1dc35ed17492f4a6d33d881624e5db18facdc562877947f06aa01a7dd1ca2ef6 -->
```
        <source>Command-line options</source>
        <translation>♦Command-line♦ na mga pagpipilian</translation>
    
ERR  
The translation includes extraneous characters ("♦") at the start and around "Command-line", which are not present in the source and are unwanted. The phrase "Command-line" should be translated appropriately to Filipino/Tagalog if possible.

Correct translation:  
Mga pagpipilian sa command-line
```

<!-- cache_translation_check_tl_83998df7dc9623c396fb00945729e528a386fd8b1f548b352d7d3e4705da69ae -->
```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Ang ♦Load♦ ay Bahagyang Napirmahan na Transaksyon sa ♦Bitcoin♦</translation>
    
ERR  
The translation is problematic.  
1. The source phrase is "Load Partially Signed Bitcoin Transaction," which should be a simple imperative or descriptive phrase.
2. The translation includes unnecessary symbols "♦" and an unnatural structure.
3. The "Load" is unnecessarily emphasized and translated as if it were a noun ("Ang Load"), while it should be an imperative or a succinct noun phrase.
4. "na Transaksyon sa Bitcoin" is acceptable, but overall, the phrase is awkward and not natural Filipino.

Correct translation:
I-load ang Bahagyang Napirmahang Transaksyon sa Bitcoin
```

<!-- cache_translation_check_tl_a4c2b701fbaa77e34e9fdb67eee3424232613b0f0d67557f35772e90dd08df5c -->
```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Ang ♦Load♦ ay Bahagyang Napirmahan na Transaksyon sa ♦Bitcoin♦ mula sa ♦clipboard♦</translation>
    
ERR
The translation introduces unnecessary symbols (♦) and an awkward sentence structure. "Ang Load ay Bahagyang Napirmahan na Transaksyon sa Bitcoin mula sa clipboard" is unnatural in Filipino/Tagalog, and "Load" should be rendered as "I-load" or similar to make it actionable/imperative.

Correct translation:
I-load ang Bahagyang Napirmahang Transaksyong Bitcoin mula sa clipboard
```

<!-- cache_translation_check_tl_98e05599392772861ff5e902b2f73d10d9152621323bf6a86dd262d9866f9840 -->
```
        <source>Sending addresses</source>
        <translation>Pagpapadalhan na mga ♦address♦</translation>
    
ERR
The translation is problematic due to the unnecessary addition of "na" and the use of special symbols ♦ which are not present in the source. The translation should be simple, straightforward, and free of extraneous formatting or words. Also, "address" should usually just be "address," as it is commonly used untranslated in Filipino IT/crypto contexts, or "mga address" if pluralization is preferred.

Correct translation:
Mga address na padadalhan
```

<!-- cache_translation_check_tl_9124a7b647cc646a0d84a0b5820c1df5eb248ead5a5d7c75919894d892e21987 -->
```
        <source>Receiving addresses</source>
        <translation>Pagtatanggapan na mga ♦address♦</translation>
    
ERR
The translation uses "Pagtatanggapan na mga ♦address♦", which is awkward and includes untranslated English word "address" with special characters. The proper Filipino word for "addresses" should be used, and "receiving addresses" can be translated more naturally.

Correct translation:
Mga address ng pagtanggap
```

<!-- cache_translation_check_tl_ad4ee142c4a1c914a8341da8fbd15416768d0fd9b629cbfc0dcdcbbe81a9c8b8 -->
```
        <source>Open a bitcoin: URI</source>
        <translation>Buksan ang ♦bitcoin: URI♦</translation>
    
ERR  
The translation incorrectly includes extra symbols "♦" around "bitcoin: URI". This is not present in the source text and may confuse users. The rest of the translation is otherwise correct.

Correct translation:  
Buksan ang bitcoin: URI
```

<!-- cache_translation_check_tl_b560346c7322969e270b27f7e50fe0271736cea745beeba2af270d7a28045282 -->
```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Ipakita ang %1 tumulong sa mensahe na kumuha ng listahan ng posibleng ♦Bitcoin command-line♦ na mga pagpipilian</translation>
    
ERR
The translation mixes English and Filipino unnecessarily ("tumulong sa mensahe", "command-line"), contains awkward phrasing, and introduces an extraneous symbol (♦). "tumulong sa mensahe" is not a correct translation for "help message". The format is also confusing.

Correct translation:
Ipakita ang mensahe ng tulong ng %1 upang makakuha ng listahan ng mga posibleng pagpipilian sa command-line ng Bitcoin
```

<!-- cache_translation_check_tl_32fb836ae44b9007189be9a6af331fad3208eed45ebbf099c106a551de9e805a -->
```
        <source>Main Window</source>
        <translation>Pangunahing ♦Window♦</translation>
    
ERR
The translation unnecessarily retains the English word "Window" and adds inappropriate symbols (♦), which is not standard in Filipino translations. "Main Window" should be translated as "Pangunahing Window" (if 'Window' is used as a proper term in Filipino interfaces), or better yet, fully in Filipino as "Pangunahing Bintana".

Correct translation:
Pangunahing Bintana
```

<!-- cache_translation_check_tl_b0ca125dfca02e8e1f6c4971ee2389c4d6786ec9d56861aa2ddb60598b79012b -->
```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>I-enable ang aktibidad ng ♦network♦</translation>
    
ERR
The translated phrase "I-enable ang aktibidad ng ♦network♦" is problematic:
1. The word "network" is not translated into Tagalog ("tl"). It should be "network" (as a loanword) only if no better word is applicable, but the diamond symbols (♦) are inappropriate and not present in the original source.
2. The extra symbols (♦) do not belong and are unwanted content.

Correct translation:
I-enable ang aktibidad ng network

Alternatively, you may use "I-enable ang aktibidad ng network" if "network" as a loanword is acceptable in local Bitcoin context, but DO NOT add decorative symbols.
```

<!-- cache_translation_check_tl_5e458709d3799066cd5602224f75c56be0889fea658318ab1aa6fd8e63874407 -->
```
        <source>Address: %1
</source>
        <translation>♦Address♦: %1
</translation>
    
ERR
The translation inappropriately adds "♦" symbols around "Address", which are not present in the source and are likely unintended. Additionally, the English word "Address" is retained, which may be acceptable if the term is left untranslated in the software, but typically it should be translated to "Address: %1" → "Address: %1" (if left untranslated), or in Filipino, it should be "Address: %1" → "Address: %1" (since "Address" is commonly used in Filipino Bitcoin contexts and may remain untranslated). However, the main issue is the addition of unwanted symbols.

Correct translation:
Address: %1
or, if you prefer a Filipino word,
Tirahan: %1
```

<!-- cache_translation_check_tl_46a6de912cbda065947f61a7a60b144a10ebb7edc143ffd96f0247869780cd36 -->
```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>♦HD key generation♦ ay &lt;b&gt;na-disable&lt;/b&gt;</translation>
    
ERR
The translation is problematic because:
- The "♦" symbols at the start and around "HD key generation" are unwanted and introduce stray characters.
- "na-disable" is an anglicized and informal term. A more appropriate Filipino translation is "hindi pinagana" or "hindi aktibo".
- "HD key generation" is a technical term that can be left untranslated for the Filipino audience, but without the stray symbols.

Correct translation:
Ang HD key generation ay <b>hindi pinagana</b>
```

<!-- cache_translation_check_tl_841108c8853ec5707989c73d392834c209c90f7424a7eb5ff92ca2e983b3e1e7 -->
```
        <source>Coin Selection</source>
        <translation>Pagpipilian ng ♦coin♦</translation>
    
ERR
The translation is problematic because it literally translates "Coin Selection" as "Pagpipilian ng ♦coin♦", where "coin" is not translated to Filipino/Tagalog and unnecessary decorative symbols (♦) are present. The word "coin" should be translated appropriately for the Bitcoin context (e.g., "barya" or simply kept as "coin" if that is standard in local usage, but without symbols). Also, "Pagpipilian ng" is awkward; a better translation would be "Pagpili ng Barya" or "Pagpili ng Coin" depending on standard usage in the Bitcoin community in the Philippines.

Correct translation:
Pagpili ng Barya
```

<!-- cache_translation_check_tl_a3153cba7880480e30075989ac2c97d8c1142e629883e5432104a56a2c322a7e -->
```
        <source>List mode</source>
        <translation>Listajhan na ♦mode♦</translation>
    
ERR
The translation is incorrect and uses "Listajhan" (which is not a valid Tagalog word) and adds symbols ("♦mode♦") that are not present in the source. The correct translation should use proper Tagalog or a near match if a direct translation isn't standard.

Correct translation:
Paraan ng listahan
```

<!-- cache_translation_check_tl_613e93104618b067ba56cc85fc7c4d06d1b8e80d94b21608e9aff9796b5c5124 -->
```
        <source>Received with label</source>
        <translation>Natanggap na may kasamang ♦tatak♦</translation>
    
ERR
The use of "♦tatak♦" is incorrect and non-standard. The diamonds (♦) are not appropriate and may indicate a placeholder or erroneous characters. The word "tatak" is an acceptable translation for "label," but "kasamang" is awkward in this context. The standard phrase should be directly and neutrally translated.

Correct translation:
Natanggap na may label
```

<!-- cache_translation_check_tl_6c3a259493a5e061bb10e1b2feca65f4935d0dba297c26b9edb7e32d060b8228 -->
```
        <source>Received with address</source>
        <translation>Natanggap na may ♦address♦</translation>
    
ERR
The translation is problematic because it uses "♦address♦" instead of translating the term or correctly using a format specifier if required. Additionally, "na may" is acceptable but not the standard way to phrase this in Filipino UI.

Correct translation:
Natanggap sa address
```

<!-- cache_translation_check_tl_8b998371fdb18b91ab7231c559531349ce14e29252288935b88597596296ec4b -->
```
        <source>Copy address</source>
        <translation>Kopyahin ang ♦address♦</translation>
    
ERR The translation "Kopyahin ang ♦address♦" is problematic. The word "address" is untranslated, and the use of "♦" is unnecessary and incorrect in this context. 

Correct translation:
Kopyahin ang address

If you want a more natural translation, you can use:
Kopyahin ang address

Or, if you want to translate "address" as "address ng pitaka" ("wallet address"):
Kopyahin ang address

But strictly for "Copy address", the accurate "tl" is:
Kopyahin ang address
```

<!-- cache_translation_check_tl_673cc0fb2a849c6945dad72ba1089f4f4c15b03f8d6643f7c88f86b9abed0552 -->
```
        <source>Copy bytes</source>
        <translation>Kopyahin ang ♦bytes♦</translation>
    
ERR
The translation is problematic. The phrase "Kopyahin ang ♦bytes♦" includes unnecessary symbols (♦) around "bytes" that are not present in the source. Furthermore, the English word "bytes" is typically used directly in Filipino technical contexts, but the symbols make the translation erroneous.

Correct translation:
Kopyahin ang bytes
```

<!-- cache_translation_check_tl_436bfe96a15bd3557511910af3f0024bc11778dac136927f009a18fb323dbea6 -->
```
        <source>Can vary +/- %1 satoshi(s) per input.</source>
        <translation>Maaaring magbago ng +/- %1♦4satoshi(s)♦ kada ♦input♦.</translation>
    
ERR
There are issues with stray and incorrect characters (e.g., "♦4", "♦"), and the English word "input" is unnecessarily wrapped with special symbols. The format specifier "%1" is taken over correctly, but the extra "4" and "♦" are errors and "satoshi(s)" could be localized.

Correct translation:
Maaaring magbago ng +/- %1 satoshi kada input.
```

<!-- cache_translation_check_tl_ec15bef870ce1f12ea54d7e9de066f3b2cc7de13619f15356afbbd3961121c63 -->
```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>Ang pagsasarod sa pitaka sa matagal ay maaaring humantong sa pag-resync ng kabuuang ♦chain♦ kung ang pagputol ay na-enable.</translation>
    
ERR  
The translation contains the following issues:  
1. The word "pagsasarod" is a typo; it should be "pagsasara".  
2. The phrase "♦chain♦" should be translated or kept in English only if there's no Filipino equivalent, but the use of "♦♦" is unusual and likely unintended.  
3. "Pagputol" is not the preferred translation for "pruning" in the context of Bitcoin; "pruning" is best kept in English in technical context, or else clarified.  
4. The sentence structure and translation for "enabled" is not optimal.  
5. Minor awkward phrasing throughout.

Correct translation:
Ang pagsasara ng pitaka nang matagal ay maaaring magresulta sa kinakailangang i-resync ang buong chain kung naka-enable ang pruning.
```

<!-- cache_translation_check_tl_3744dde566f285549490a25e9eb13ee4e5753f25f09a887922c3e081fc6f8b17 -->
```
        <source>Encrypt the wallet. The wallet will be encrypted with a passphrase of your choice.</source>
        <translation>I-encrypt ang pitaka. Ang pitaka ay mae-encrypt na may ♦passphrase♦ ng iyong mapipili.</translation>
    
ERR
The translation uses "♦passphrase♦", which is an unnecessary decoration and is not standard. It should simply use the word "passphrase" or its equivalent. Otherwise, the translation is generally accurate and does not have spacing or format issues.

Correct translation:
I-encrypt ang pitaka. Ang pitaka ay mae-encrypt gamit ang passphrase na iyong pinili.
```

<!-- cache_translation_check_tl_eae5dedb6064163bbaeb3072db20c61c7e6bcdfb2bc8902c45969211b78c4a55 -->
```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>I-disable ang mga pribadong mga susi para sa pitaka na ito. Ang mga pitaka na may mga pribadong mga susi na na-disable ay mawawalng ng pribadong mga susi at hindi magkakaroon ng ♦HD seed♦ o mga na-import na pribadong mga susi. Ito ay perpekto lamang para sa mga ♦watch-only♦ na mga pitaka.</translation>
    
ERR  
There are several issues in the translation:
1. The use of "♦HD seed♦" and "♦watch-only♦" with symbols is unnecessary and not standard in Filipino translations. English terms like "HD seed" and "watch-only" are often retained, but without symbols.
2. "mawawalng" is misspelled; it should be "mawawalan".
3. Excessive repetition of "mga" (plural marker) before "pribadong mga susi". It is more natural to say "mga pribadong susi".

Correct translation:
I-disable ang mga pribadong susi para sa pitakang ito. Ang mga pitakang may disabled na pribadong susi ay mawawalan ng pribadong susi at hindi magkakaroon ng HD seed o na-import na pribadong susi. Ito ay perpekto para sa mga watch-only na pitaka.
```

<!-- cache_translation_check_tl_913c301d63896291aba157ac0e50b096b411885dbb04af33d05d73abc601b7ed -->
```
        <source>Use an external signing device such as a hardware wallet. Configure the external signer script in wallet preferences first.</source>
        <translation>Gumamit ng panlabas na pagpirmang ♦device♦ katulad ng ♦hardware♦ na pitaka. I-configure ang panlabas na ♦signer script♦ sa loob ng ♦preferences♦ ng pitaka n listahan. </translation>
    
ERR
There are several issues with the translation:
1. The use of "♦device♦", "♦hardware♦", and "♦signer script♦" is inconsistent and uses unnecessary symbols; these terms can be translated directly or appropriately localized.
2. "Preferences" can be translated as "mga kagustuhan," and "wallet preferences" as "mga kagustuhan ng pitaka" rather than "preferences ng pitaka n listahan".
3. The phrase "n listahan" at the end appears to be an erroneous fragment.
4. The use of English fragments is unnecessarily high; certain terms can be better localized.

Correct translation:
Gumamit ng panlabas na kagamitan sa pagpirma tulad ng hardware wallet. I-configure muna ang panlabas na signer script sa mga kagustuhan ng pitaka.
```

<!-- cache_translation_check_tl_14a7ea247d63eb45d55f8870a31d780894f38ce30c9125dd5a30874b06da536f -->
```
        <source>External signer</source>
        <translation>Panlabas na ♦signer♦</translation>
    
ERR
The word "signer" is not translated and is marked with unusual symbols (♦), which is not standard practice and can be confusing or appear as spam. Additionally, "signer" can be translated for clarity.

Correct translation:
Panlabas na tagapirma
```

<!-- cache_translation_check_tl_3a9506a5a2a00325c007490fcf76a36f2bd3ada4df864a940ece4283ac64885c -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Pinagsama-sama na walang suporta ng ♦pag-pirma♦ (kailangan para sa panlabasna pagpirma)</translation>
    
ERR
The translation is problematic due to:
- Unnecessary use of the symbols "♦" around "pag-pirma", which is incorrect and not present in the source.
- "Panlabasna" should be "panlabas na" (missing space).
- The use of "Pinagsama-sama" is not idiomatic in this context; a better term is "Inipon" or directly using "Na-compile" which is more appropriate in a technical context.

Correct translation:
Na-compile nang walang suporta para sa panlabas na pagpirma (kinakailangan para sa panlabas na pagpirma)
```

<!-- cache_translation_check_tl_5b1a10c0394b729e4ac2be8a6b99b461dd7622e4d458d77cfb4392eadb9411c5 -->
```
        <source>Edit Address</source>
        <translation>I-edit ang ♦address♦</translation>
    
ERR
The translation "I-edit ang ♦address♦" unnecessarily leaves the word "address" untranslated and adds unwanted symbols (♦), which are not in the source or appropriate. In Tagalog, "address" (especially in the context of Bitcoin) can be translated as "address" (commonly used loan word) or more fully as "adres" if needed, but symbols should not be present.

Correct translation:
I-edit ang address
```

<!-- cache_translation_check_tl_026d67241b4536ead66c0054b88c379c62cf03f8bf5219655fb32924bfadd4a7 -->
```
        <source>The label associated with this address list entry</source>
        <translation>Ang tatak na nauugnay sa ♦entry♦ ng listahan ng ♦address♦</translation>
    
ERR
The translation is problematic for multiple reasons:
- The translation awkwardly maintains the English placeholders "entry" and "address" with ♦, which is not standard practice in Filipino and makes the text sound unnatural.
- "Entry" and "address" are not translated, and should be.
- "Address list entry" should be translated as "entry ng listahan ng address", but "address" could also be natively translated as "address" (Filipino usage does sometimes borrow the English term in technical contexts).

Correct translation:
Ang label na nauugnay sa entry ng listahan ng address na ito
```

<!-- cache_translation_check_tl_b78f5159c5589fe9ff8d98a3611767d86600a0375660015d8ce5cafd00ec785a -->
```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>Ang ♦address♦ na may kaugnayan sa ipinasok sa listahan ng ♦address♦. Ito ay maaari lamang ng mabago para sa pagpapadalhan na mga ♦address♦.</translation>
    
ERR
The translation uses the placeholder "♦address♦" instead of the word "address" translated into Filipino/Tagalog (typically "address" is retained or "adres" is used as a loanword in context). Additionally, the phrase structure is awkward and not entirely natural in Filipino. There are also some grammatical issues such as "ng mabago" (should be "lamang mabago").

Correct translation:
Ang address na kaugnay ng entry na ito sa listahan ng address. Maaari lamang itong baguhin para sa mga address na gagamitin sa pagpapadala.
```

<!-- cache_translation_check_tl_92ee6a77281da23df6c9704d3b53f54937123a9033392941def5cf299e4d2f78 -->
```
        <source>Address</source>
        <translation>♦Address♦</translation>
    
ERR
The translation is problematic: the inclusion of "♦" symbols is unnecessary and was not present in the original source. The word "Address" should be translated into Filipino (Tagalog) if an appropriate term exists, or left as is if it's commonly used untranslated in the technical context, but without extraneous symbols.

Correct translation:
Address

Or, if a Filipino translation is appropriate:
Adres
```

<!-- cache_translation_check_tl_1af09f24e32f9e00da1ee44ee8dd74aeb613e190d1e7b08c21fe638a9b1fa5dd -->
```
        <source>New sending address</source>
        <translation>Bagong pagpapadalhan na ♦address♦</translation>
    
ERR
The translation is problematic. The use of "♦address♦" is not proper Filipino and seems to include untranslated placeholder text with decorative symbols, which is unnecessary and confusing. The phrase "Bagong pagpapadalhan" is generally understandable, but "address" should be translated as "address" in Filipino contexts ("address" is often used directly, or "adres" can be used). Remove the decorative symbols.

Correct translation:
Bagong address ng padadalhan

Or optionally, using "adres":
Bagong adres ng padadalhan
```

<!-- cache_translation_check_tl_06af6a1b208d04d36ab32d5db2eaad168adee910537485ac3d4a431f750b8de0 -->
```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Ang naipasok na ♦address♦ "%1" ay hindi wasto na ♦Bitcoin address♦.</translation>
    
ERR
The translation contains unnecessary symbols "♦address♦" and "♦Bitcoin address♦", which are not standard or appropriate in Tagalog and do not appear in the original English. Also, the structure could be more idiomatic. 

Correct translation:
Ang ipinasok na address na "%1" ay hindi wastong Bitcoin address.
```

<!-- cache_translation_check_tl_2c91f62c6d85439a20b3cf2d60c52f0c93922615dcd55fea63663b0c0c03b34b -->
```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>Ang naipasok na ♦address♦ "%1" ay nasa aklat na ng ♦address♦ na may tatak "%2".</translation>
    
ERR  
The translation incorrectly uses "♦address♦" as placeholders, which is not idiomatic and unnecessary in Filipino ('tl'), and may confuse users. The word "address" should be translated as "address" (since the context of Bitcoin usually keeps the term untranslated), or at least consistently and not surrounded by special characters. The phrase "aklat na ng ♦address♦" is ungrammatical and awkward—"address book" should be translated as "aklat ng mga address" or "address book" (as calque).

Correct translation:  
Ang ipinasok na address na "%1" ay nasa address book na may tatak na "%2".
```

<!-- cache_translation_check_tl_a1bb2a70982941997461f24fbfaeac7213984cf9cc2421d618f53b77ccaffee9 -->
```
        <source>New key generation failed.</source>
        <translation>Ang Bagong susi sa ♦generation♦ ay nabigo.</translation>
    
ERR
The translation has several issues:
- The word "generation" is not translated; it appears as "♦generation♦".
- "Bagong" should not be capitalized unless at the start.
- The correct translation of "key generation" is "pagbuo ng susi" or "paggawa ng bagong susi".
- Format specifiers and spacing are not problematic here, but the translation does not accurately convey the source.

Correct translation:
Nabigo ang pagbuo ng bagong susi.
```

<!-- cache_translation_check_tl_3ed2c92242ca0c4bdfd6efdac704d7375b65ad709f53fbeed1938bf89e1654e0 -->
```
        <source>A new data directory will be created.</source>
        <translation>May bagong datos na ♦directory♦ ay magagawa.</translation>
    
ERR  
The translation is awkward and contains an untranslated word ("directory") boxed by special characters (♦directory♦), which is not standard in Tagalog ('tl'). It should read more naturally and either translate "directory" (e.g., as "direktoryo") or consistently borrow it if it is common in local usage, but without special characters.  
  
Correct translation:  
Lilikha ng isang bagong direktoryo ng datos.  
or  
Isang bagong data directory ang lilikhain.
```

<!-- cache_translation_check_tl_6ecf2f122605aa99c26d0feb5afa3dc86f1f8539c0ec39eb0fe7c06363f3901c -->
```
        <source>Directory already exists. Add %1 if you intend to create a new directory here.</source>
        <translation>Ang ♦directory♦ ay mayroon na. Magdagdag ng%1kung balak mong gumawa ng bagong ♦directory♦ dito.</translation>
    
ERR
There are several issues: 
- "%1" is not spaced properly ("Magdagdag ng%1kung" should be "Magdagdag ng %1 kung").
- The word "directory" is not translated or left as is but wrapped in unusual symbols (♦), which is not standard.
- The tone is slightly awkward in Filipino.

Correct translation:
Umiiral na ang directory. Magdagdag ng %1 kung nais mong gumawa ng bagong directory dito.
```

<!-- cache_translation_check_tl_4dc1782055eb5911f92de0d954f9675e5926b612b6ae9bd1c8c4590b7bd2a823 -->
```
        <source>Cannot create data directory here.</source>
        <translation>Hindi makakagawa ng datos na ♦directory♦ dito.</translation>
    
ERR  
The translation is partly problematic. The word "directory" is not translated and is awkwardly surrounded by the characters ♦, which are unnecessary and not standard. In addition, "data directory" should ideally be translated as "directory ng datos" or "folder ng datos," not "datos na directory." A better and more natural translation:

Correct translation:  
Hindi maaaring lumikha ng directory ng datos dito.
```

<!-- cache_translation_check_tl_8772ceffa95c1a2632dbd7da7d8143e28476fa6e965634fb2a1f69e98b24ea0d -->
```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Hindi bababa sa %1 ng ♦GB♦ na dato ay mailalagay sa ♦directory♦, at lalaki sa paglipas ng panahon.</translation>
    
ERR
There are several issues with the translation:
- "♦GB♦" and "♦directory♦" should not be wrapped with such symbols; these are not typical in Tagalog translation and are not present in the source.
- "ng GB" is incorrect; should be "%1 GB".
- "dato" should be "data".
- "directory" should be translated as "direktoryo".
- The sentence structure could be improved for naturalness.
- The translation does not preserve the original format specifier "%1" correctly, since it's followed by "ng" without "GB".

Correct translation:
Hindi bababa sa %1 GB ng data ang itatago sa direktoryong ito, at madaragdagan pa ito habang tumatagal.
```

<!-- cache_translation_check_tl_24ae433f5d824b80229dca9a349a4b99545dc87d8d2f52d955faf2550e9d7866 -->
```
        <source>Size of database cache</source>
        <translation>Laki ng ♦database cache♦</translation>
    
ERR
The translation "Laki ng ♦database cache♦" is problematic because it inappropriately uses the English phrase "database cache" without translation or explanation. Additionally, the diamond symbols (♦) are not present in the source and are unnecessary.

Correct translation:
Laki ng cache ng database
```

<!-- cache_translation_check_tl_d411348dec9fb4d8c16806a016aec296efa39acd8dcdd5f0841694af2fb48a10 -->
```
        <source>Number of script verification threads</source>
        <translation>Bilang ng ♦script♦ pagpapatunay na mga ♦threads♦</translation>
    
ERR
The translation improperly uses English words "script" and "threads" enclosed in symbols (♦), which is not standard and may confuse users. In Filipino ("tl"), technical terms like "script" and "threads" are sometimes borrowed, but not marked with special symbols, and the word order could be improved.

Correct translation:
Bilang ng mga thread para sa pagpapatunay ng script
```

<!-- cache_translation_check_tl_94212e31e34a6ba6c5d1902ec5e27d710e00822f10c6dfbdb806fed78af49797 -->
```
        <source>Network</source>
        <translation>♦Network♦</translation>
    
ERR
The translation is problematic. The Tagalog ('tl') translation is simply the English word "Network" with decorative characters (♦) added, which are not present in the original source. This addition is unwarranted and constitutes a format issue.

Correct translation:
Network

Alternatively, if you prefer a direct Tagalog translation (though English terms are often used in computing contexts in the Philippines):

Correct translation:
Ugnayan (but "Network" is commonly retained)

So the best choice for software UI is just:
Network
```

<!-- cache_translation_check_tl_e99df2a14b804dc61030a0a291e1f3b0c30b444cfa77b5e863b8447288132009 -->
```
        <source>Prune block storage to</source>
        <translation>Putulan i-block ang imbakan sa</translation>
    
ERR
The translation "Putulan i-block ang imbakan sa" is awkward and not entirely accurate. The verb "putulan" is not the commonly used term for "prune" in this technical context, and the structure is unnatural in Filipino. 

A better, more natural and clear translation would be:
"Putulin ang storage ng block sa"

Correct translation:
Putulin ang storage ng block sa
```

<!-- cache_translation_check_tl_0ad745d1f84d94299c76ffc18d37ddca32f812f84aff50a6cd3f15fc6ad93afc -->
```
        <source>External signer script path</source>
        <translation>Panlabas na ♦signer script♦ na daanan</translation>
    
ERR
The translation is somewhat awkward and contains the phrase "♦signer script♦" which appears to be a placeholder or markup rather than a translation. The use of "daanan" for "path" is acceptable but could be improved for clarity.

Correct translation:
Panlabas na landas ng signer script

Or, more fluently:
Landas ng panlabas na signer script
```

<!-- cache_translation_check_tl_3a9506a5a2a00325c007490fcf76a36f2bd3ada4df864a940ece4283ac64885c -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Pinagsama-sama na walang suporta ng ♦pag-pirma♦ (kailangan para sa panlabasna pagpirma)</translation>
    
ERR
The translation is problematic due to:
- Unnecessary use of the symbols "♦" around "pag-pirma", which is incorrect and not present in the source.
- "Panlabasna" should be "panlabas na" (missing space).
- The use of "Pinagsama-sama" is not idiomatic in this context; a better term is "Inipon" or directly using "Na-compile" which is more appropriate in a technical context.

Correct translation:
Na-compile nang walang suporta para sa panlabas na pagpirma (kinakailangan para sa panlabas na pagpirma)
```

<!-- cache_translation_check_tl_09251f95f3c3a8e78ac73fe9f7b4e8193df10e409fed3254c270988f08ccfc15 -->
```
        <source>Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>Kopyahin ang ♦address♦</translation>
    
ERR
The translation "Kopyahin ang ♦address♦" is problematic. The placeholder "♦address♦" is not a proper translation; it should translate "address" as "address" or "adres" in Filipino/Tagalog, but without the special characters. The correct translation is:

Correct translation:
Kopyahin ang address

Alternatively, if "address" should be perfectly localized:  
Kopyahin ang adres

However, "address" is often left untranslated in Filipino tech contexts. The use of special characters is unnecessary and incorrect.
```

<!-- cache_translation_check_tl_8b998371fdb18b91ab7231c559531349ce14e29252288935b88597596296ec4b -->
```
        <source>Copy address</source>
        <translation>Kopyahin ang ♦address♦</translation>
    
ERR The translation "Kopyahin ang ♦address♦" is problematic. The word "address" is untranslated, and the use of "♦" is unnecessary and incorrect in this context. 

Correct translation:
Kopyahin ang address

If you want a more natural translation, you can use:
Kopyahin ang address

Or, if you want to translate "address" as "address ng pitaka" ("wallet address"):
Kopyahin ang address

But strictly for "Copy address", the accurate "tl" is:
Kopyahin ang address
```

<!-- cache_translation_check_tl_673cc0fb2a849c6945dad72ba1089f4f4c15b03f8d6643f7c88f86b9abed0552 -->
```
        <source>Copy bytes</source>
        <translation>Kopyahin ang ♦bytes♦</translation>
    
ERR
The translation is problematic. The phrase "Kopyahin ang ♦bytes♦" includes unnecessary symbols (♦) around "bytes" that are not present in the source. Furthermore, the English word "bytes" is typically used directly in Filipino technical contexts, but the symbols make the translation erroneous.

Correct translation:
Kopyahin ang bytes
```

<!-- cache_translation_check_tl_8b998371fdb18b91ab7231c559531349ce14e29252288935b88597596296ec4b -->
```
        <source>Copy address</source>
        <translation>Kopyahin ang ♦address♦</translation>
    
ERR The translation "Kopyahin ang ♦address♦" is problematic. The word "address" is untranslated, and the use of "♦" is unnecessary and incorrect in this context. 

Correct translation:
Kopyahin ang address

If you want a more natural translation, you can use:
Kopyahin ang address

Or, if you want to translate "address" as "address ng pitaka" ("wallet address"):
Kopyahin ang address

But strictly for "Copy address", the accurate "tl" is:
Kopyahin ang address
```

<!-- cache_translation_check_tl_e59785ae44d2b039c9835eed9786b0d5ed31a447d8572c58a0585e2902aee269 -->
```
        <source>Copy transaction ID</source>
        <translation>Kopyahin ang transaksyon  ng ♦ID♦</translation>
    
ERR
The translation is problematic because:
1. The original "transaction ID" should be "ID ng transaksyon" or "transaksyon ID" in Filipino. 
2. There is an unnecessary space before "ng".
3. The use of "♦ID♦" is odd and could be confusing or introduce unwanted content.

Correct translation:
Kopyahin ang ID ng transaksyon
```

<!-- cache_translation_check_tl_92ee6a77281da23df6c9704d3b53f54937123a9033392941def5cf299e4d2f78 -->
```
        <source>Address</source>
        <translation>♦Address♦</translation>
    
ERR
The translation is problematic: the inclusion of "♦" symbols is unnecessary and was not present in the original source. The word "Address" should be translated into Filipino (Tagalog) if an appropriate term exists, or left as is if it's commonly used untranslated in the technical context, but without extraneous symbols.

Correct translation:
Address

Or, if a Filipino translation is appropriate:
Adres
```
</details>

Number of issues: 85.
