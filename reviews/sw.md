# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>sw</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bsw%5D%20request)


<!-- cache_translation_check_sw_62419019a8d232cfdaa9851e736d8d5ee418f6fd4cf3098317a3d4351891673e -->
```
        <source>C&amp;lose</source>
        <translation>C&amp;Funga</translation>
    
ERR
The translation includes an extra leading "C" that should not be present. The original uses a single '&' to mark the shortcut; the translation also has one '&' but has an incorrect extra character. No format specifiers or spacing issues otherwise.

Correct translation:
&Funga
```

<!-- cache_translation_check_sw_4f7bcd49ac64b9b550985cad69452acdc3b09edb653c3220282e1ec962cd8760 -->
```
        <source>C&amp;hoose</source>
        <translation>Chagua</translation>
    
ERR
The translation is missing the shortcut marker '&' from the source. The source contains a single '&' to mark the accelerator key and the translation must include exactly one '&' as well.

Correct translation:
<translation>&amp;Chagua</translation>
```

<!-- cache_translation_check_sw_dcbeb84ed4be3ca4d0cc577593ce8248d65d53d9c6d5913158a714fc1d549e1e -->
```
        <source>Copy &amp;Label</source>
        <translation>Nakili &amp; Chapa</translation>
    
ERR
Problems:
- The Swahili word "Chapa" means "stamp/print", not "label". A better word for "label" is "lebo" or "lebuli".
- There's an extra space between the ampersand and the following word ("& Chapa"); the ampersand should be immediately adjacent to the shortcut character (no stray space).
- Ensure exactly one & appears.

Correct translation suggestion:
<translation>Nakili &amp;Lebo</translation>
```

<!-- cache_translation_check_sw_cc79a547cf94b7b5ec534f7ab556e70f03b6fff1ac4775d2757a5119e2505399 -->
```
        <source>&amp;Edit</source>
        <translation>&amp; hariri</translation>
    
ERR
The translation is correct lexically ("hariri" = "Edit"), but there is an extra space between the ampersand and the word ("&amp; hariri"). The ampersand indicating the shortcut should be immediately before the character and appear exactly once.

Correct translation:
&amp;Hariri
```

<!-- cache_translation_check_sw_83a7147b69aed134ae02d3beda544071575bbd044601084dcea259aca4da05b2 -->
```
        <source>Encrypt wallet</source>
        <translation>Simba mkoba</translation>
    
ERR
The translation "Simba mkoba" is problematic. In Swahili, "Simba" means "lion" and is not related to "encrypt." The correct translation for "Encrypt wallet" would be "Sificha mkoba," "Kodisha mkoba," or more accurately "Ficha mkoba" (hide wallet), but the technical term "Encryption" is best translated as "sificha" or "kodisha".

Correct translation:
Sificha mkoba
```

<!-- cache_translation_check_sw_26b5b702dcfd419e3d72ec35965aa112ff590ec2c1ef8d585af74c693d427d5a -->
```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Faili ya mipangilio ya asilimia %1 inaweza kuwa mbovu au batili.</translation>
    
ERR
The translation incorrectly translates "%1" as "asilimia %1" which means "percent %1" in Swahili. "%1" is a format specifier and should be retained as is. The rest of the translation is otherwise accurate, but this error renders it problematic.

Correct translation:
Faili ya mipangilio %1 inaweza kuwa mbovu au batili.
```

<!-- cache_translation_check_sw_d283a9340c94b010d71184cb7ba31bed3147583edfd7648f194ab2ec357d1fc0 -->
```
        <source>Runaway exception</source>
        <translation>Ubaguzi wa kukimbia</translation>
    
ERR
The translation is inaccurate. "Runaway exception" (a technical term referring to an unhandled or uncontrolled exception in programming or system execution) is translated as "Ubaguzi wa kukimbia", which means "discrimination of running" or "running discrimination", and does not convey the intended technical meaning.

Correct translation:
Hitilafu isiyoweza kudhibitiwa

Alternative acceptable translation:
Hitilafu isiyodhibitiwa
```

<!-- cache_translation_check_sw_dcffebfb11913ccc55b7f772ae6693a0799424522bcec0e1fdd6363831554271 -->
```
        <source>&amp;Transactions</source>
        <translation>&amp;Shughuli za malipo</translation>
    
ERR
Translation is understandable but not the most natural for Bitcoin UI. "Shughuli za malipo" means "payment activities" and is somewhat specific; the common, concise UI term for "Transactions" in Swahili is "Miamala" (or "Muamala" depending on dialect).

Correct translation:
&amp;Miamala
```

<!-- cache_translation_check_sw_7027bcbb1b251488c6eac59b8355160e5e7cd3fd3920648bb283bd1d6a8702a5 -->
```
        <source>&amp;About %1</source>
        <translation>Kuhusu %1</translation>
    
ERR
The translation is missing the shortcut ampersand (&) that appears in the source. It should include exactly one &. 

Correct translation:
&Kuhusu %1
```

<!-- cache_translation_check_sw_1c1dd507bdd8f13f02354655ebac24fb5420cd342c5475c95086a1b47a0eed83 -->
```
        <source>&amp;Minimize</source>
        <translation>Kupunguza</translation>
    
ERR
The translation is missing the shortcut indicator "&" from the source. No other issues.

Correct translation:
&amp;Kupunguza
```

<!-- cache_translation_check_sw_6246fd5ba0725f39fbe05dff9f700cb7be5282eeff45399594c0f7a32e427d75 -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation>&amp;Simba Mkoba...</translation>
    
ERR
"Simba" in Swahili means "lion", so the translation is incorrect. Also use the same ellipsis character as in the source.

Correct translation (suggestions):
&Fichamisha Mkoba…
or
&Enkripti Mkoba…
```

<!-- cache_translation_check_sw_dc82d49db11bb67491e11bad51058722586e6c9a8cb4363a20ae5a54db6b831c -->
```
        <source>Open &amp;URI…</source>
        <translation>Fungua &amp;URI ...</translation>
    
ERR
The Swahili translation is correct in meaning and preserves the shortcut (&) exactly once, but it has a spacing/punctuation issue: there's an extra space before the ellipsis and it uses three dots with a preceding space instead of the source's ellipsis character.

Correct translation (no space before ellipsis, using the single ellipsis char):
Fungua &URI…
```

<!-- cache_translation_check_sw_4c1ac8a54ee646332bd8e45ad129edc2698971aabb04bb6add548f749e7bc383 -->
```
        <source>&amp;Settings</source>
        <translation>&amp;Vipimo</translation>
    
ERR
"Vipimo" usually means "measurements" or "parameters" in Swahili; the more appropriate translation for "Settings" (as an application/menu label) is "Mipangilio".

Correct translation:
&Mipangilio
```

<!-- cache_translation_check_sw_aba9be6c2dc99d54508ad20ca219e6572fa46e701d8f197645de3712b49b9019 -->
```
        <source>&amp;Help</source>
        <translation>&amp;Msaidie</translation>
    
ERR
The Swahili translation uses "Msaidie" (imperative/verb) which is not the usual noun for a Help menu. The ampersand is preserved correctly, but the correct noun is "Msaada" (or "Saidia" in some contexts). 

Correct translation:
&amp;Msaada
```

<!-- cache_translation_check_sw_5531ac067eb35611e4def151e43f2435d7fe951dfd873745b5752eb076f0a24e -->
```
        <source>&amp;Command-line options</source>
        <translation>&amp;Chaguo za amri ya amri</translation>
    
ERR
The Swahili translation incorrectly repeats "amri" ("amri ya amri") and is therefore incorrect. Also a more natural rendering is needed.

Correct translation:
&Chaguo za mstari wa amri
```

<!-- cache_translation_check_sw_c0674eb5e7a03b6270e95bf6dc7191a1f71f4bb09dc2ea120c8aa02c3265a5ff -->
```
        <source>Last received block was generated %1 ago.</source>
        <translation>Kizuizi cha mwisho kilichopokelewa kilitolewa awali.</translation>
    
ERR
The translation is missing the required format specifier '%1', which represents the time duration (e.g., "5 minutes ago"). It also ends with "awali" (previously/initially) instead of providing a placeholder for the relative time.

Correct translation:
Kizuizi cha mwisho kilichopokelewa kilitengenezwa %1 iliyopita.
```

<!-- cache_translation_check_sw_255c7be7921031a3f1a701c09a1af76ab32dffb1ad983525ca5c08ff302e3ffd -->
```
        <source>&amp;Receiving addresses</source>
        <translation>&amp;Inapokea anwani</translation>
    
ERR
The Swahili uses a verb form "Inapokea" ("receives") instead of a noun phrase for "Receiving addresses". Also the ampersand is present correctly but the grammar is wrong.

Correct translation:
&Anwani za kupokea
```

<!-- cache_translation_check_sw_0a01c22920741a4dcf59b4839e4787db931f1aa42b09f5cceb71830cfa77891e -->
```
        <source>&amp;Mask values</source>
        <translation>&amp;Funga maadili</translation>
    
ERR
The Swahili translation is inaccurate. "Funga maadili" means "close/lock morals/values" and uses "maadili" (morals/ethics) instead of numeric/field "values". The ampersand is present exactly once (OK).

Correct translation:
&Ficha thamani
```

<!-- cache_translation_check_sw_bc2f66b0a6f5bf9c266740d62b5ae332023170816e7e88b777a3ea4155f14c50 -->
```
        <source>S&amp;how</source>
        <translation>Jinsi &amp; jinsi</translation>
    
ERR
The Swahili translation is incorrect and awkward. "Jinsi jinsi" means "how how" (not "show"), and spacing around the ampersand is inconsistent with the source. The shortcut ampersand should appear exactly once and the correct Swahili verb for "Show" is "Onyesha".

Correct translation:
O&amp;nyesha
```

<!-- cache_translation_check_sw_7804636bff742301db50520a8bfb3cc3921c92fef132d47b11a78deec950665c -->
```
        <source>Copy &amp;label</source>
        <translation>Nakili &amp;chapa</translation>
    
ERR
"&chapa" is understandable but not the best Swahili choice for the UI term "label". A more common translation for a UI "label" is "lebo" (or "alama"). The ampersand is present exactly once, which is correct.

Correct translation suggestion:
Nakili &lebo
```

<!-- cache_translation_check_sw_48f5427ebbe2e910c6966fa8d58049900cc094367cb815c32b14e069512d3f41 -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>Nakili &amp;Kitambulisho cha muamala na faharasa ya matokeo</translation>
    
ERR
"faharasa ya matokeo" is unnatural/incorrect Swahili: "faharis(a)" is misspelled and "matokeo" means "results" (not the transaction output). Use "pato" for output or the borrowed "indeksi" for index. The ampersand is present exactly once (OK).

Suggested correction:
Nakili &kitambulisho cha muamala na nambari ya pato

(Alternative using "index" loanword:
Nakili &kitambulisho cha muamala na indeksi ya pato)
```

<!-- cache_translation_check_sw_f8a3d5d903ecffcebf0a0b97b95532dc96c075b65d31d34c2880d08b30d92bc0 -->
```
        <source>L&amp;ock unspent</source>
        <translation>&amp;Funga ambayo haijatumika</translation>
    
ERR
The Swahili is understandable but slightly awkward/incorrect: "ambayo haijatumika" is a singular relative clause and omits the noun; for UTXOs (plural) a plural form is better.

Correct translation:
&Funga zisizotumika
```

<!-- cache_translation_check_sw_1f516eea8faa90f303f929cfa11ba30e3afb948fa5f18ac6b918f588768b8b6a -->
```
        <source>&amp;Unlock unspent</source>
        <translation>&amp;Fungua ambayo haijatumika</translation>
    
ERR
The Swahili translation is understandable but slightly ungrammatical/awkward. "Fungua ambayo haijatumika" literally reads "Open which has not been used" and lacks proper agreement and natural phrasing.

Corrected translation:
&amp;Fungua zisizotumika
```

<!-- cache_translation_check_sw_4cb3be6ad7bbd405628a73996cd65c2d24eed2b2dfbab4b4e32cf785fb4fa798 -->
```
        <source>Error</source>
        <translation>Onyo</translation>
    
ERR
The translation of "Error" as "Onyo" is incorrect. "Onyo" means "Warning" in Swahili.

Correct translation:
Hitilafu
```

<!-- cache_translation_check_sw_529ce375d4a989a1d749fa7d58c6e28cb377fa4d45f38a0f39064f20e1a94111 -->
```
        <source>Address</source>
        <extracomment>Title of Peers Table column which contains the IP/Onion/I2P address of the connected peer.</extracomment>
        <translation>Anuani</translation>
    
ERR
The Swahili word is misspelled. "Anuani" should be "Anwani". No format specifiers or spacing issues.

Correct translation:
Anwani
```

<!-- cache_translation_check_sw_465130f02afc9db960995eafb87468479bd6186cb45afe540f955263806d5302 -->
```
        <source>&amp;Label:</source>
        <translation>&amp;Chapa:</translation>
    
ERR
"Chapa" in Swahili more directly means "print" or "stamp" and is not the most appropriate UI translation for "Label" in this context. The ampersand is used correctly and spacing is fine.

Suggested translation:
&Lebeli:
```

<!-- cache_translation_check_sw_7804636bff742301db50520a8bfb3cc3921c92fef132d47b11a78deec950665c -->
```
        <source>Copy &amp;label</source>
        <translation>Nakili &amp;chapa</translation>
    
ERR
"&chapa" is understandable but not the best Swahili choice for the UI term "label". A more common translation for a UI "label" is "lebo" (or "alama"). The ampersand is present exactly once, which is correct.

Correct translation suggestion:
Nakili &lebo
```

<!-- cache_translation_check_sw_465130f02afc9db960995eafb87468479bd6186cb45afe540f955263806d5302 -->
```
        <source>&amp;Label:</source>
        <translation>&amp;Chapa:</translation>
    
ERR
"Chapa" in Swahili more directly means "print" or "stamp" and is not the most appropriate UI translation for "Label" in this context. The ampersand is used correctly and spacing is fine.

Suggested translation:
&Lebeli:
```

<!-- cache_translation_check_sw_7804636bff742301db50520a8bfb3cc3921c92fef132d47b11a78deec950665c -->
```
        <source>Copy &amp;label</source>
        <translation>Nakili &amp;chapa</translation>
    
ERR
"&chapa" is understandable but not the best Swahili choice for the UI term "label". A more common translation for a UI "label" is "lebo" (or "alama"). The ampersand is present exactly once, which is correct.

Correct translation suggestion:
Nakili &lebo
```

<!-- cache_translation_check_sw_bd3851e85fb4f82ac393697e2ee9fdc15d7c0833e4d045264dc5f2061cbc51c9 -->
```
        <source>&amp;Edit address label</source>
        <translation>&amp;Hariri chapa ya anuani</translation>
    
ERR
Word choice and spelling are off. "chapa ya anuani" is unnatural (and "anuani" is a misspelling of "anwani"); "label" is better translated as "lebo".

Correct translation:
&amp;Hariri lebo ya anwani
```

<!-- cache_translation_check_sw_be37632ddaea6e82550b3043275af4f67d120e66a2b038015d81954005d630ad -->
```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>Zaidi ya anuani moja ya onion bind imetolewa. Inatumia %skwa ajili ya huduma ya Tor onion inayotengeneza kiotomatiki. </translation>
    
ERR
There is a missing space between '%s' and 'kwa', resulting in '%skwa'. Also, "inayoundwa kiotomatiki" is a more accurate rendering of "automatically created" (than 'inayotengeneza kiotomatiki', which is less idiomatic). Additionally, "inatumiwa kwa ajili ya" ("is used for") pairs better with "using".

Correct translation:
Zaidi ya anuani moja ya onion bind imetolewa. %s inatumiwa kwa ajili ya huduma ya Tor onion inayoundwa kiotomatiki.
```
</details>

Number of issues: 31.
