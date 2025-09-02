# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>eu</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Beu%5D%20request)


<!-- cache_translation_check_eu_b830c3d99b7d1b0fa4e4cca27c2549079f30093701e592b4a394ce515efb97dd -->
```
        <source>Repeat new passphrase</source>
        <translation>Pasahitz berria errepiikatu</translation>
    
ERR
There is a minor spelling error in the Basque word for "repeat". It should be "errepikatu" rather than "errepiikatu" (one too many 'i's).

Correct translation:
Pasahitz berria errepikatu
```

<!-- cache_translation_check_eu_07dd8e5bbff4b11e7d23557e7ae93cb5f26fc87b1c50e8af2211422bb23bf1dd -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Diruzorroaren pasahitz berria sartu. &lt;br/&gt;Mesedez &lt;b&gt; hamar edo gehiago ausazko hizkiko&lt;/b&gt; pasahitza erabili, edo &lt;b&gt; gutxienez zortzi hitz&lt;/b&gt;</translation>
    
ERR
The Basque translation contains grammar and fluency issues:
- "Diruzorroaren" is an uncommon (literal) translation for "wallet" in Basque; "zorro" is more common.
- The sentence structure and word order are not fully natural.
- There is a missing full stop at the end, and "erabili" is not capitalized otherwise.
- The translation omits "Please use a passphrase of ...", which should be "Erabili mesedez ..." or similar.
- The phrase "hogeita hamar edo gehiago ausazko hizkiko" is awkward and should be "... hamar karaktere edo gehiago ausazkoak ..." (characters) and similarly for words.
- The tag and bold markup are transferred correctly.

Correct translation:
Sartu zorroaren pasahitz berria.&lt;br/&gt;Mesedez, erabili &lt;b&gt;hamar karaktere edo gehiago ausazkoak&lt;/b&gt; dituen pasahitza, edo &lt;b&gt;gutxienez zortzi hitz&lt;/b&gt;.
```

<!-- cache_translation_check_eu_da7396bbeffdde7e417c8b8b1ba34052160bdfe989d906b3db8384a1b4565cf4 -->
```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>GARRANTZITSUA: Diruzorroaren segurtasun-kopia, wallet.dat, erabilezina bihurtuko da enkriptazioa burutu ondoren. Ondorioz, segurtasun-kopia berriekin ordezkatu beharko zenituzke zure jada eginik dituzun diruzorroaren kopiak.</translation>
    
ERR
The translation does not accurately render the original English message. It omits several important details: specifically, the instructions to replace old backups with the newly generated encrypted wallet, and it does not mention explicitly that unencrypted backups become useless, nor the reason ("for security reasons"). It also adds "wallet.dat" which is not specified in the source.

Correct translation:
GARRANTZITSUA: Zure diruzorro fitxategiaren aurretik egindako segurtasun-kopiak ordezkatu behar dituzu orain sortutako, zifratutako diruzorro fitxategiarekin. Segurtasun arrazoiengatik, zifratugabea den diruzorro fitxategiaren aurretiko segurtasun-kopiak baliogabe bihurtuko dira zifratutako berria erabiltzen hasten zarenean.
```

<!-- cache_translation_check_eu_15c0657e0f0f9c998bc0adc3c91cbc231455941b7ea4530537f0a3b8b65a7494 -->
```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Kartera deszifratzeko sartu den pasahitza ez da zuzena. Karaktere nulua du (adib - zero byte). Passphrasak software honen bertsio bat bazuen 25.0 bertsioaren aurretik, mesedez, saia zaitez berriro karaktere hutsekin, lehen karaktere nulua barne hartu gabe. Arrakasta izanez gero, jar ezazu passphrase berri bat etorkizunean hori saihesteko.</translation>
    
ERR
There are some inaccuracies and style issues in the translation:
- "adib" is likely an attempt at "adibidez" ("for example"), but the English says "(ie - a zero byte)", meaning "that is", which in Basque should be "hau da".
- "karaktere hutsak" means "blank/empty characters", which does not convey "characters up to (but not including) the first null character".
- The structure and precision of the English has not been fully preserved.

Correct translation:
Kartera deszifratzeko sartu duzun pasahitza ez da zuzena. Karaktere nulu bat dauka (hau da, zero byte bat). Pasahitza software honen 25.0 bertsioa baino lehenagoko bertsio batekin ezarri bazen, saiatu berriro, lehen karaktere nuluaraino, baina hura barne hartu gabe, dagoen karaktereak bakarrik sartzen. Honek funtzionatzen badu, ezarri pasahitz berri bat etorkizunean arazo hau saihesteko.
```

<!-- cache_translation_check_eu_f7858909e0063f37b408eea72f8ef442600cb3c906b76d729b1184d4ed95aa7e -->
```
        <source>Banned Until</source>
        <translation>Honarte debekatua </translation>
    
ERR
The translation is incorrect and has a spelling mistake. "Honarte debekatua" does not convey the meaning of "Banned Until" in Basque, and "Honarte" should be "honaino" if attempting "until", but "honaino debekatua" is still not idiomatic.

Correct translation:
Debekatua honaino
or, more naturally,
Debekatuta (epea: [insert date/time here])
or
Debekatua data hau arte

If the intention is to indicate a date until which the ban lasts, "Debekatua data hau arte" ("Banned until this date") is the clearest.
```

<!-- cache_translation_check_eu_a5c8d167630846f7f109dea259a69a4559a3e36190940c4e46dd069cf4352c6c -->
```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>%1 Konfigurazio fitxategian akatsa edo baliogabea izan daiteke</translation>
    
ERR
The translation is missing an article and does not properly convey the meaning of "might be corrupt or invalid." It also drops the word "file" ("fitxategi"), and the structure is unnatural.

Correct translation:
%1 konfigurazio-fitxategia hondatuta edo baliogabea egon daiteke.
```

<!-- cache_translation_check_eu_2bd91aaf1bc7f23129a665b4a96bdddb0be800163592025b06a296e47634e87a -->
```
        <source>Runaway exception</source>
        <translation>Ranaway exception</translation>
    
ERR
The translation is erroneous; it simply repeats the original English phrase with a typo ("Ranaway" instead of "Runaway") rather than translating it into Basque.

Correct translation:
Salbuespen iheslaria
```

<!-- cache_translation_check_eu_3ace3987a5d12c5e09479bbe96867525e0282802022783e672ae6a66313a23ad -->
```
        <source>%1 d</source>
        <translation>%1 e</translation>
    
ERR
The translation is problematic. The English source "%1 d" likely stands for "%1 days", where "d" is an abbreviation for "days". In Basque ('eu'), the abbreviation for "days" is "eg" (from "egun"), not "e". 

Correct translation:
%1 eg
```

<!-- cache_translation_check_eu_0f5be8484c0350dba7e01bdd64d1145e6fee13960d06b27b8dd122c6066b8c2a -->
```
        <source>E&amp;xit</source>
        <translation>Irten</translation>
    
ERR
The ampersand (&) indicating the shortcut key in the source text is missing in the translation. The translation should include it, in any position, but exactly once.

Correct translation:
&Irteten or Irte&n
```

<!-- cache_translation_check_eu_75eb7d7f8963f88ee97a607336afad5b4e0b7da88a7b16e7770c4b9811c8d08e -->
```
        <source>&amp;About %1</source>
        <translation>%1-ri buruz</translation>
    
ERR
The translation omits the & shortcut key indicator, which should appear exactly once in the translation (anywhere). Also, the translation would be improved for clarity by making it: "&%1-ri buruz".

Correct translation:
&%1-ri buruz
```

<!-- cache_translation_check_eu_9cc32eb64f6a698b8c8c8f79a644b1b6ed74c215f71940ee7ff9a8b49313f3b3 -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>&amp;aldatu pasahitza</translation>
    
ERR
The translation is mostly correct, but the ellipsis ("…") at the end of the source text is missing in the Basque translation. The format specifier &amp; is present exactly once, which is correct.

Correct translation:
&Aldatu pasahitza…
```

<!-- cache_translation_check_eu_73bcabd5375e6a19b7b1bf1a356ed6af7666f22e410780d5d6bc5438afa5f9bb -->
```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Egiaztatu mesua Bitcoin helbide espezifikoarekin erregistratu direla ziurtatzeko</translation>
    
ERR
The translation is not accurate. The English source says "Verify messages to ensure they were signed with specified Bitcoin addresses". The Basque ('eu') translation says "Egiaztatu mesua Bitcoin helbide espezifikoarekin erregistratu direla ziurtatzeko", which means "Verify the message to ensure that it has been registered with a specific Bitcoin address". The translation misses the plural 'messages', changes 'signed' to 'registered', and otherwise loses precision.

Correct translation:
Mezuak egiaztatu, zehaztutako Bitcoin helbideekin sinatu direla ziurtatzeko
```

<!-- cache_translation_check_eu_9e59e66b3dfaf304a9fbeb82624f46650e9f0204e4dc781f74dbafa3a81c592b -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>kargatu PSBT arbeletik...</translation>
    
ERR
The translation does not maintain the shortcut key indicator (&), which should appear exactly once, and "kargatu" should be capitalized as it starts the sentence. The ellipsis character should match the source (the translation uses three dots instead of a single unicode ellipsis).

Correct translation:
&Kargatu PSBT arbeletik…
```

<!-- cache_translation_check_eu_e688664f45cfb130fab871ad521cf3c29704e4f8e25562b67cb1adfb212866da -->
```
        <source>&amp;Sending addresses</source>
        <translation>&amp;Helbideak bidaltzen</translation>
    
ERR
The translation "Helbideak bidaltzen" literally means "sending addresses" as a verb phrase ("addresses sending"), not as a noun phrase ("addresses to send to" or "sending addresses"). In Basque, the correct phrasing for "Sending addresses" (as in a list of addresses used for sending) is "Bidaltzeko helbideak".

Correct translation:
&amp;Bidaltzeko helbideak
```

<!-- cache_translation_check_eu_95902831e0aa11f0ccf37bed611e7bbb00cbde0cd20069298eda72edf2ef561a -->
```
        <source>&amp;Receiving addresses</source>
        <translation>&amp;Helbideak jasotzen</translation>
    
ERR
The translation is grammatically incorrect; "Helbideak jasotzen" literally means "receiving addresses" in a non-standard way ("helbideak" = "addresses", "jasotzen" = "receiving (in the process)"), which does not properly correspond to the noun phrase "Receiving addresses". A correct translation would be "Helbide hartzaileak" or "Jasotzeko helbideak".

Correct translation:
&Jasotzeko helbideak
```

<!-- cache_translation_check_eu_7e40afc1f9a7635b1b0cda646bfa9081f67ae12b5443f8a8c94540fdbd2dc003 -->
```
        <source>Fee:</source>
        <translation>Ordainketa:</translation>
    
ERR
The translation is inaccurate. 'Ordainketa' means 'payment', not 'fee' (which would be 'komisio' or 'tasak' in Basque). 'Fee:' should be translated as 'Komisioa:' or 'Tasa:' in this context.

Correct translation:
Komisioa:
```

<!-- cache_translation_check_eu_c847bd33bbf4fc55136eff3344d13ea104104ad12d95b0414cc75480b0e4e1dd -->
```
        <source>Copy amount</source>
        <translation>zenbatekoaren kopia</translation>
    
ERR
The Basque translation "zenbatekoaren kopia" is not idiomatic and does not clearly convey the imperative "Copy amount". It reads like "copy of the amount" rather than giving a command.

Correct translation:
Zenbatekoa kopiatu
```

<!-- cache_translation_check_eu_06b96d9bbb9be8768f67bc26988824d43a3693f163822829e4d27ba27812e392 -->
```
        <source>%1 is shutting down…</source>
        <translation>%1Itzaltzen ari da...</translation>
    
ERR
There is a missing space between the format specifier and the translation text ("%1Itzaltzen" instead of "%1 Itzaltzen"). Additionally, the ellipsis should match the source ("…" vs "..."). The correct form in Basque would also make the translation more natural.

Correct translation:
%1 itzaltzen ari da…
```

<!-- cache_translation_check_eu_62125b9ef1846f0039ea8e24c7a84c9b9d9c42597a4611ae2ebbf0272dc83289 -->
```
        <source>Size of &amp;database cache</source>
        <translation>Databasearen cache tamaina</translation>
    
ERR
The translation omits the ampersand (&) used for the shortcut key, which is present in the source and must exist exactly once in the translation. Additionally, "Databasearen" should be "Datbasearen" or preferably localized to "datubasearen" as "database" can be translated into Basque.

Correct translation:
&Datubasearen cache-tamaina
```

<!-- cache_translation_check_eu_c2049d9f5e126800a680ed733254c646a0aefd39fd02b47d7d46d84d4eba14ed -->
```
        <source>IP address of the proxy (e.g. IPv4: 127.0.0.1 / IPv6: ::1)</source>
        <translation>Proxyaren IP helbidea  (IPv4: 127.0.0.1 / IPv6: ::1 adibidez )</translation>
    
ERR
There are minor whitespace issues and the position of "adibidez" (e.g.) is inconsistent with the English source. In Basque, "adibidez" should directly follow the examples, not be at the end in parenthesis. Also, there is an unnecessary double space after "helbidea".

Correct translation:
Proxyaren IP helbidea (adibidez, IPv4: 127.0.0.1 / IPv6: ::1)
```

<!-- cache_translation_check_eu_2e1855c5842ad0f4dcff050e39a8dd2710173a6eb8014e13366753b9af4126fd -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Sarbide konexioak baimendu</translation>
    
ERR
The ampersand (&) indicating the shortcut key in the source text ("Allow incomin&g connections") is missing in the translation. There should be exactly one & in the translation at some location.

Correct translation:
Sar&bide konexioak baimendu
or
Sarbide kone&xioak baimendu

Either placement of the & is valid as long as it appears exactly once.
```

<!-- cache_translation_check_eu_753305df1d9115bdf9502131a21ca477ced0837151d9dc31a0a05d598eed8a03 -->
```
        <source>This change would require a client restart.</source>
        <translation>Aldaketa honek clienta berriro piztea eskatzen du</translation>
    
ERR
The translation uses "clienta," which is a mix of Basque and Spanish/English ("client"). In Basque, the correct term would be "bezeroa" for "client." Furthermore, a period is missing at the end of the sentence to match the source punctuation.

Correct translation:
Aldaketa honek bezeroa berrabiaraztea eskatzen du.
```

<!-- cache_translation_check_eu_7e40afc1f9a7635b1b0cda646bfa9081f67ae12b5443f8a8c94540fdbd2dc003 -->
```
        <source>Fee:</source>
        <translation>Ordainketa:</translation>
    
ERR
The translation is inaccurate. 'Ordainketa' means 'payment', not 'fee' (which would be 'komisio' or 'tasak' in Basque). 'Fee:' should be translated as 'Komisioa:' or 'Tasa:' in this context.

Correct translation:
Komisioa:
```

<!-- cache_translation_check_eu_e5eb3542c0d6d48151116dc5ebfbb19867b24325360769a6da06d72b16017303 -->
```
        <source>S&amp;end</source>
        <translation>Bidali</translation>
    
ERR
The translation omits the '&' character, which is used to indicate the shortcut key in the UI. The translation should include the '&' exactly once, placed appropriately for a shortcut in Basque.

Correct translation:
&Bidali
or
Bi&dali

(Usual Basque practice is to put the ampersand before the B or D, but either is acceptable as long as there is exactly one '&'.)
```

<!-- cache_translation_check_eu_c847bd33bbf4fc55136eff3344d13ea104104ad12d95b0414cc75480b0e4e1dd -->
```
        <source>Copy amount</source>
        <translation>zenbatekoaren kopia</translation>
    
ERR
The Basque translation "zenbatekoaren kopia" is not idiomatic and does not clearly convey the imperative "Copy amount". It reads like "copy of the amount" rather than giving a command.

Correct translation:
Zenbatekoa kopiatu
```

<!-- cache_translation_check_eu_f36d2f4e6172ac9fec36d1404dcf9b15572e18f0abd5239a7bb68e8dbb02ae10 -->
```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>%1 konfirmazio</translation>
    
ERR
The translation is incorrect because "konfirmazio" is not correct in Basque for "confirmations". The correct translation should be "konfirmazio" for singular, but for plural it should be "konfirmazio", which is still not quite right; the correct plural form in Basque is "konfirmazio". However, the actual Basque for "confirmation" is "berrespen", and the plural form is "berrespen". Additionally, the word is missing the plural suffix and adaptation for "%1" (e.g. "%1 berrespen").

Correct translation:
%1 berrespen
```

<!-- cache_translation_check_eu_bdcf55dc0f0ce2d61fa1f3c79e8fb886be362c244fcb93358c3d6529d9ed3e8c -->
```
        <source>Mined</source>
        <translation>Meatua</translation>
    
ERR
The translation "Meatua" is incorrect in Basque. The correct term for "Mined" in the context of Bitcoin (referring to coins that have been produced through mining) is "Meatua". However, "Meatua" in Basque more often means "mine" (noun: a mine, as in a coal mine). The correct translation for the verb "Mined" (as in "has been mined") is "Meatutako".

Correct translation:
Meatutako
```

<!-- cache_translation_check_eu_121926b40832dd954279b8909907420e12fa442716959927c2b9b665e0322444 -->
```
        <source>This week</source>
        <translation>Aste honetankoak</translation>
    
ERR
The translation "Aste honetankoak" is incorrect and ungrammatical in Basque. The correct translation for "This week" is "Aste hau".

Correct translation:
Aste hau
```

<!-- cache_translation_check_eu_bdcf55dc0f0ce2d61fa1f3c79e8fb886be362c244fcb93358c3d6529d9ed3e8c -->
```
        <source>Mined</source>
        <translation>Meatua</translation>
    
ERR
The translation "Meatua" is incorrect in Basque. The correct term for "Mined" in the context of Bitcoin (referring to coins that have been produced through mining) is "Meatua". However, "Meatua" in Basque more often means "mine" (noun: a mine, as in a coal mine). The correct translation for the verb "Mined" (as in "has been mined") is "Meatutako".

Correct translation:
Meatutako
```
</details>

Number of issues: 29.
