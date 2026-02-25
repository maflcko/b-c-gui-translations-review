# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Btk%5D%20request)



<details><summary>tk</summary>


<!-- cache_translation_check_tk_01c84469dbfc4692cf3ca3d959eb2ed8dab665a94726d244cde7266ca440c8b9 -->
```
        <source>&amp;Export</source>
        <translation>&amp;Geçir</translation>
    
ERR
"Geçir" is ambiguous and reads like Turkish; it doesn't clearly convey "Export" in Turkmen UI context.

Correct translation:
&Daşary çykarmak
```

<!-- cache_translation_check_tk_636d84adb14b81e4a74af892a74b5f2ebf1497217329fb9b7f5eef7a5fc0e972 -->
```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Otur bilen aýrylan faýl</translation>
    
ERR
The word for "comma" in Turkmen is "wergül", not "otur" (which matches Kazakh "үтір"). The current translation likely mixes languages.

Correct translation:
Wergül bilen aýrylan faýl
```

<!-- cache_translation_check_tk_1c7ee215d219ab5578a9bef32ae8210ee306f8f10a02e4dbf86f61e06240dd6c -->
```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>(Bitkoin salgysyny giriziň (meselem, %1)</translation>
    
ERR
There is an extra opening parenthesis at the start and the parentheses do not match.

Correct translation:
Bitkoin salgysyny giriziň (meselem, %1)
```

<!-- cache_translation_check_tk_609616960ac716f761f2225363aa849b51ea88d8b8aa867e573735545b36942c -->
```
        <source>Network activity disabled.</source>
        <extracomment>A substring of the tooltip.</extracomment>
        <translation>Tor işleýşi ýapyk.</translation>
    
ERR
"Tor işleýşi ýapyk." is awkward and potentially misleading. "Tor" is capitalized (could be confused with the Tor network), "işleýşi" is not the most natural choice for "activity," and "ýapyk" means "closed" rather than "disabled." A clearer Turkmen translation is:

Correct translation:
Tor işjeňligi öçürildi.
```

<!-- cache_translation_check_tk_c6cd2e7e4ab956480a0f88fbe9c940a52d44c1ccdba9063c918b9d7a7c49816f -->
```
        <source>Synchronizing with network…</source>
        <translation>Tor bilen sinhronlaşdyrmak...</translation>
    
ERR
The translation uses the infinitive form ("to synchronize") instead of the progressive/passive ongoing action implied by "Synchronizing…". It also replaces the ellipsis character (…) with three dots (...).

Correct translation:
Tor bilen sinhronlaşdyrylýar…
```

<!-- cache_translation_check_tk_42be43edf99e051a4a75a06d6bc33052173a22b4064bb189b32b2c0ea787aec9 -->
```
        <source>%1 behind</source>
        <translation>%1 galdy</translation>
    
ERR
"galdy" means "left/remaining," which misinterprets "behind" in this context (sync lag). A clearer Turkmen rendering is "yza galdy."

Correct translation:
%1 yza galdy
```

<!-- cache_translation_check_tk_fb53a1990a82577559ed553e22e45043bdac251aa0aa37d76c20eea42f925442 -->
```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>HD açar döretmeklik &lt;b&gt;öçük&lt;/b&gt;</translation>
    
ERR
The phrasing is awkward and "öçük" (off) is not the best choice for "disabled". A clearer translation uses "öçürildi" (disabled/turned off).

Correct translation:
HD açar döredilişi &lt;b&gt;öçürildi&lt;/b&gt;
```

<!-- cache_translation_check_tk_20c490c6760758c8d90e0d95f0c7f0191afc3d81a8633c933fb9464b43b077a4 -->
```
        <source>Fee:</source>
        <translation>Gatanç:</translation>
    
ERR
"Gatanç" means "participation" in Turkmen, not "fee". For Bitcoin transaction context, use "Komissiýa tölegi:" (or shorter "Komissiýa:").

Correct translation:
Komissiýa tölegi:
```

<!-- cache_translation_check_tk_6136e3899753746cbb902e8bd9b4300f825682df9ebff48779cef392638988cf -->
```
        <source>Change:</source>
        <translation>Çalyş:</translation>
    
ERR
"Çalyş" means "attempt/effort" (or "to try") in Turkmen and does not match the Bitcoin context. For monetary "change" (returned remainder), the correct Turkmen term is "Gaýtarym".

Correct translation:
Gaýtarym:
```

<!-- cache_translation_check_tk_33df3dd98b5d87ac124115dfb25d479bd4ea180fee69121412c401677d81f3da -->
```
        <source>(%1 locked)</source>
        <translation>(%1 gulply)</translation>
    
ERR
The word "gulply" is not the correct Turkmen form for "locked." A proper adjective/participle form should be used.

Correct translation:
(%1 gulplanan)
```

<!-- cache_translation_check_tk_61a823057577cd532bbeaf62ffd6f9736e579088600f0b3c506f2ae01cf3cf63 -->
```
        <source>Restore Wallet</source>
        <extracomment>Title of progress window which is displayed when wallets are being restored.</extracomment>
        <translation>Gapjygy düzeltmek</translation>
    
ERR
The translation uses "düzeltmek", which means "to fix" or "to correct". For restoring a backup or a wallet in a software context, "dikeltmek" is more appropriate in Turkmen.

Correct translation:
Gapjygy dikeltmek
```

<!-- cache_translation_check_tk_47b0c02c9a68aff30b52ce714c0700e1ce6a1a7dbe0e87dfe99a89dafedc665b -->
```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>&lt;b&gt;%1&lt;/b&gt; Gapjyk dikeldilýär…</translation>
    
ERR
Word order is awkward; it currently reads as "%1 wallet" rather than "Wallet %1". Also, "Gapjyk" should follow the identifier.

Correct translation:
Gapjyk &lt;b&gt;%1&lt;/b&gt; dikeldilýär…
```

<!-- cache_translation_check_tk_feb8a782d3178ad97dffedade6261053e5c70bcc9e9161fac07269f5b501c693 -->
```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>OK basanyňyzda, %1%4 başda işledilende %3-däki iň irki amallardan başlap doly %4blok zynjyryny (%2 GB) ýükläp we işläp başlar.</translation>
    
ERR
The translation concatenates placeholders ("%1%4") and is missing a space ("%4blok"). Word order is also awkward. 

Correct translation:
OK düwmesine basanyňyzda, %1 %3 ýylda %4 ilkinji gezek işe girizilende edilen iň irki amallardan başlap, doly %4 blok zynjyryny (%2 GB) ýükläp we işlemäge başlar.
```

<!-- cache_translation_check_tk_1c0779300bcdcc3a8dd45e6f8bf1c4805a111ae28d862d123392c59ebd9f8699 -->
```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>%1häzir sinhronlaşdyrylýar. Ol düwünlerden baş atlary we bloklary ýükläp alar we blok zynjyrynyň ujuna ýetýänçä olary  barlar.</translation>
    
ERR
Issues:
- Missing space after %1 ("%1häzir" -> "%1 häzir").
- Double space before "barlar" ("olary  barlar").
- "baş atlary" is not a proper term for "headers"; "sözbaşylary" is appropriate in computing context.
- "düwünlerden" mixes forms and is less clear; "deň-duşlardan" better matches "peers".

Correct translation:
%1 häzir sinhronlaşdyrylýar. Ol deň-duşlardan sözbaşylary we bloklary ýükläp alar we blok zynjyrynyň ujuna ýetýänçä olary barlar.
```

<!-- cache_translation_check_tk_6e220dcae5f1130a582ca30926391ce5673be758cbb0994d7abd3089943ed4a4 -->
```
        <source>Unknown. Syncing Headers (%1, %2%)…</source>
        <translation>Näbelli. (%1, %2 %) Baş atlar sinhronlaşdyrylýar...</translation>
    
ERR
- "Baş atlar" is incorrect; it means "stallions." Use "Başlyklar" (or "Sözbaşylary") for "Headers."
- The space before the percent sign is wrong: "%2 %)" should be "%2%)".
- The word order should preserve "Syncing Headers" before the parenthetical.
- Use the ellipsis character (…) to match the source.

Correct translation:
Näbelli. Başlyklar sinhronlaşdyrylýar (%1, %2%)…
```

<!-- cache_translation_check_tk_868c18b9620d26fba7bcb55a9f4de54a70b2cd9d722515fc47287c1ccda4eaae -->
```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Näbelli. (%1, %2 %) Baş atlar deslapdan sinhronlaşdyrylýar...</translation>
    
ERR
- The term "Baş atlar" is incorrect for "Headers"; a better Turkmen term is "Sözbaşlar".
- The format specifier has an extra space before the percent sign: "%2 %)" should be "%2%)".
- The order should match the source (text before the parentheses).
- Use a proper ellipsis character to match the source.

Correct translation:
Näbelli. Sözbaşlar deslapdan sinhronlaşdyrylýar (%1, %2%)…
```

<!-- cache_translation_check_tk_322a1e5bc8272da3fe325c7bed5e38610fa96ce832384a70e97c8af34ad86c0a -->
```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Salgyny alyş-çalyş tagtasyna giriz</translation>
    
ERR
The translation uses "alyş-çalyş tagtasy" (exchange board) and "giriz" (enter), which are inaccurate for "clipboard" and "paste."

Correct translation:
Buferdäki salgyny goý
```

<!-- cache_translation_check_tk_eaadc38f673e733091ba118ad19c691474e10126bda3ba6ee9416009068146dd -->
```
        <source>Automatically start %1 after logging in to the system.</source>
        <translation>Ulgama hasaba girilenden soň %1awtomatiki usulda başlat.</translation>
    
ERR
There is a missing space between "%1" and "awtomatiki". Also, "işe giriz" is more natural than "başlat" in Turkmen UI context.

Correct translation:
Ulgama girilenden soň %1 awtomatiki usulda işe giriz.
```

<!-- cache_translation_check_tk_fe33d954da4ae7d7c98121038ea34ec07237456ac44a61f42353c9c9a77f8e04 -->
```
        <source>&amp;Reset Options</source>
        <translation>&amp;Opsiýalary başdaka belle</translation>
    
ERR
The Turkmen text implies "mark options as default" and uses an incorrect form ("başdaka"). The source means "reset options (to default)".

Correct translation:
&Opsiýalary deslapky ýagdaýa gaýtar
```

<!-- cache_translation_check_tk_0c978a292f961fb1d7a7905090da210416cdc035fda533a65053d2ac6717ff75 -->
```
        <source>GB</source>
        <translation>GB çenli</translation>
    
ERR
The translation adds "çenli" (meaning "up to/until"), which changes the meaning. Unit abbreviations like "GB" should remain unchanged.

Correct translation:
GB
```

<!-- cache_translation_check_tk_3585992a0dc2d4572047193f16a69202f0e5d1d11136c6945142f9da0c2afd81 -->
```
        <source>Enable R&amp;PC server</source>
        <extracomment>An Options window setting to enable the RPC server.</extracomment>
        <translation>R&amp;PC serwerini işlet</translation>
    
ERR
The verb "işlet" is Turkish and unnatural in Turkmen. "Enable" should be rendered as "işjeňleşdir" (or "işjeň et") in Turkmen. The ampersand placement is fine and should remain.

Correct translation:
R&PC serwerini işjeňleşdir
```

<!-- cache_translation_check_tk_4142d4cb8fb6db02bf55396c648271cc2b4715c0d5f4f6e95eb10760269ab824 -->
```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Indi tassyklanmaly we entek sowup boljak balansa geçirilmedik amallaryň hemmesi</translation>
    
ERR
The Turkmen wording is unnatural and partially incorrect: "Indi tassyklanmaly" misrepresents "have yet to be confirmed," and "sowup boljak balans" is not an appropriate rendering of "spendable balance."

Correct translation:
Entäk tassyklanman we entäk harçlap bolýan balansa goşulman duran amallaryň jemi
```

<!-- cache_translation_check_tk_ce17501bf46b11cb2a501d239ee005211d52c8799398d33a5a4b7bde6ea39586 -->
```
        <source>Signed transaction successfully. Transaction is ready to broadcast.</source>
        <translation>Amala şowly gol çekildi. Amal ýaýlyma taýyn.</translation>
    
ERR
Wording is awkward and “ýaýlym” refers to radio/TV broadcasting, not network propagation. More natural Turkmen for the Bitcoin context is to use “ýaýratmak” (to propagate/broadcast on the network). Also “üstünlikli” is a more standard choice for “successfully.”

Correct translation:
Amala üstünlikli gol çekildi. Amal ýaýratmaga taýyn.
```

<!-- cache_translation_check_tk_5b37140d02270de22d4671d03b97b8c14f3db9e7bca33b2d886c9124d10dc03f -->
```
        <source>Blocksdir</source>
        <translation>Blok binýadynyň deslapdan bellenmedik ýerini görkezmek üçin  opsiýasyny ulanyň.</translation>
    
ERR
The translation is an unrelated explanatory sentence, not a label, and contains extra whitespace. The source is a short option name and should remain as such.

Correct translation:
Blocksdir
```

<!-- cache_translation_check_tk_8389e5450957eb5e70d9658290df4b6be7cf854fdd8bc6aebf8fd3bd9795b50b -->
```
        <source>Wallet: </source>
        <translation>Gapjyk:</translation>
    
ERR
Missing trailing space after the colon. The source has "Wallet: " with a trailing space; the translation should mirror this spacing.

Correct translation:
Gapjyk:
```

<!-- cache_translation_check_tk_571993284155d3b4d292f117deee9f0fa6ac625c37d98d6e1fd80cbe35d19882 -->
```
        <source>Whether we relay transactions to this peer.</source>
        <translation>Amallary bu düwüne ýaýlyma geçirýärismi.</translation>
    
ERR
The Turkmen sentence is ungrammatical and uses an awkward phrase (“ýaýlyma geçirmek”). It also turns the descriptive statement into a question and lacks proper spacing/punctuation. A clearer, neutral translation is needed.

Correct translation:
Amallary bu düwüne ýetirmek-ýetirmezligimiz.
```

<!-- cache_translation_check_tk_20c490c6760758c8d90e0d95f0c7f0191afc3d81a8633c933fb9464b43b077a4 -->
```
        <source>Fee:</source>
        <translation>Gatanç:</translation>
    
ERR
"Gatanç" means "participation" in Turkmen, not "fee". For Bitcoin transaction context, use "Komissiýa tölegi:" (or shorter "Komissiýa:").

Correct translation:
Komissiýa tölegi:
```

<!-- cache_translation_check_tk_6136e3899753746cbb902e8bd9b4300f825682df9ebff48779cef392638988cf -->
```
        <source>Change:</source>
        <translation>Çalyş:</translation>
    
ERR
"Çalyş" means "attempt/effort" (or "to try") in Turkmen and does not match the Bitcoin context. For monetary "change" (returned remainder), the correct Turkmen term is "Gaýtarym".

Correct translation:
Gaýtarym:
```

<!-- cache_translation_check_tk_1f015dff70af72b1709f6e70f42e234f636ed0c6a7e0d8b72aa49a428c6240c0 -->
```
        <source>Paste address from clipboard</source>
        <translation>Salgyny alyş-çalyş tagtasyna giriz</translation>
    
ERR
The direction is reversed: it says to enter the address into the clipboard, not paste it from the clipboard.

Correct translation:
Salgyny alyş-çalyş tagtasyndan goý
```

<!-- cache_translation_check_tk_1f015dff70af72b1709f6e70f42e234f636ed0c6a7e0d8b72aa49a428c6240c0 -->
```
        <source>Paste address from clipboard</source>
        <translation>Salgyny alyş-çalyş tagtasyna giriz</translation>
    
ERR
The direction is reversed: it says to enter the address into the clipboard, not paste it from the clipboard.

Correct translation:
Salgyny alyş-çalyş tagtasyndan goý
```

<!-- cache_translation_check_tk_636d84adb14b81e4a74af892a74b5f2ebf1497217329fb9b7f5eef7a5fc0e972 -->
```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Otur bilen aýrylan faýl</translation>
    
ERR
The word for "comma" in Turkmen is "wergül", not "otur" (which matches Kazakh "үтір"). The current translation likely mixes languages.

Correct translation:
Wergül bilen aýrylan faýl
```

<!-- cache_translation_check_tk_01c84469dbfc4692cf3ca3d959eb2ed8dab665a94726d244cde7266ca440c8b9 -->
```
        <source>&amp;Export</source>
        <translation>&amp;Geçir</translation>
    
ERR
"Geçir" is ambiguous and reads like Turkish; it doesn't clearly convey "Export" in Turkmen UI context.

Correct translation:
&Daşary çykarmak
```
</details>

Number of issues: 32.
