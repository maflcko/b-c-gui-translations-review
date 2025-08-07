# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>eu</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Beu%5D%20low%20quality)


```
        <source>Repeat new passphrase</source>
        <translation>Pasahitz berria errepiikatu</translation>
    
YES
There is a minor spelling error in the Basque word for "repeat". It should be "errepikatu" rather than "errepiikatu" (one too many 'i's).

Correct translation:
Pasahitz berria errepikatu
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Diruzorroaren pasahitz berria sartu. &lt;br/&gt;Mesedez &lt;b&gt; hamar edo gehiago ausazko hizkiko&lt;/b&gt; pasahitza erabili, edo &lt;b&gt; gutxienez zortzi hitz&lt;/b&gt;</translation>
    
YES
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

```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>GARRANTZITSUA: Diruzorroaren segurtasun-kopia, wallet.dat, erabilezina bihurtuko da enkriptazioa burutu ondoren. Ondorioz, segurtasun-kopia berriekin ordezkatu beharko zenituzke zure jada eginik dituzun diruzorroaren kopiak.</translation>
    
YES
The translation does not accurately render the original English message. It omits several important details: specifically, the instructions to replace old backups with the newly generated encrypted wallet, and it does not mention explicitly that unencrypted backups become useless, nor the reason ("for security reasons"). It also adds "wallet.dat" which is not specified in the source.

Correct translation:
GARRANTZITSUA: Zure diruzorro fitxategiaren aurretik egindako segurtasun-kopiak ordezkatu behar dituzu orain sortutako, zifratutako diruzorro fitxategiarekin. Segurtasun arrazoiengatik, zifratugabea den diruzorro fitxategiaren aurretiko segurtasun-kopiak baliogabe bihurtuko dira zifratutako berria erabiltzen hasten zarenean.
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Kartera deszifratzeko sartu den pasahitza ez da zuzena. Karaktere nulua du (adib - zero byte). Passphrasak software honen bertsio bat bazuen 25.0 bertsioaren aurretik, mesedez, saia zaitez berriro karaktere hutsekin, lehen karaktere nulua barne hartu gabe. Arrakasta izanez gero, jar ezazu passphrase berri bat etorkizunean hori saihesteko.</translation>
    
YES
There are some inaccuracies and style issues in the translation:
- "adib" is likely an attempt at "adibidez" ("for example"), but the English says "(ie - a zero byte)", meaning "that is", which in Basque should be "hau da".
- "karaktere hutsak" means "blank/empty characters", which does not convey "characters up to (but not including) the first null character".
- The structure and precision of the English has not been fully preserved.

Correct translation:
Kartera deszifratzeko sartu duzun pasahitza ez da zuzena. Karaktere nulu bat dauka (hau da, zero byte bat). Pasahitza software honen 25.0 bertsioa baino lehenagoko bertsio batekin ezarri bazen, saiatu berriro, lehen karaktere nuluaraino, baina hura barne hartu gabe, dagoen karaktereak bakarrik sartzen. Honek funtzionatzen badu, ezarri pasahitz berri bat etorkizunean arazo hau saihesteko.
```

```
        <source>Banned Until</source>
        <translation>Honarte debekatua </translation>
    
YES
The translation is incorrect and has a spelling mistake. "Honarte debekatua" does not convey the meaning of "Banned Until" in Basque, and "Honarte" should be "honaino" if attempting "until", but "honaino debekatua" is still not idiomatic.

Correct translation:
Debekatua honaino
or, more naturally,
Debekatuta (epea: [insert date/time here])
or
Debekatua data hau arte

If the intention is to indicate a date until which the ban lasts, "Debekatua data hau arte" ("Banned until this date") is the clearest.
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>%1 Konfigurazio fitxategian akatsa edo baliogabea izan daiteke</translation>
    
YES
The translation is missing an article and does not properly convey the meaning of "might be corrupt or invalid." It also drops the word "file" ("fitxategi"), and the structure is unnatural.

Correct translation:
%1 konfigurazio-fitxategia hondatuta edo baliogabea egon daiteke.
```

```
        <source>Runaway exception</source>
        <translation>Ranaway exception</translation>
    
YES
The translation is erroneous; it simply repeats the original English phrase with a typo ("Ranaway" instead of "Runaway") rather than translating it into Basque.

Correct translation:
Salbuespen iheslaria
```

```
        <source>%1 d</source>
        <translation>%1 e</translation>
    
YES
The translation is problematic. The English source "%1 d" likely stands for "%1 days", where "d" is an abbreviation for "days". In Basque ('eu'), the abbreviation for "days" is "eg" (from "egun"), not "e". 

Correct translation:
%1 eg
```

```
        <source>Change Passphrase…</source>
        <translation>aldatu pasahitza</translation>
    
YES
The translation "aldatu pasahitza" means "change the password" but does not include the ellipsis and lacks capitalization. Also, "Passphrase" is better translated as "sarrerako esapidea" or "pasahitz esapide". The correct translation with ellipsis and proper capitalization would be:

Correct translation:
Pasahesa aldatu…
or
Pasahitz esapidea aldatu…
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Egiaztatu mesua Bitcoin helbide espezifikoarekin erregistratu direla ziurtatzeko</translation>
    
YES
The translation is not accurate. The English source says "Verify messages to ensure they were signed with specified Bitcoin addresses". The Basque ('eu') translation says "Egiaztatu mesua Bitcoin helbide espezifikoarekin erregistratu direla ziurtatzeko", which means "Verify the message to ensure that it has been registered with a specific Bitcoin address". The translation misses the plural 'messages', changes 'signed' to 'registered', and otherwise loses precision.

Correct translation:
Mezuak egiaztatu, zehaztutako Bitcoin helbideekin sinatu direla ziurtatzeko
```

```
        <source>Fee:</source>
        <translation>Ordainketa:</translation>
    
YES
The translation is inaccurate. 'Ordainketa' means 'payment', not 'fee' (which would be 'komisio' or 'tasak' in Basque). 'Fee:' should be translated as 'Komisioa:' or 'Tasa:' in this context.

Correct translation:
Komisioa:
```

```
        <source>Copy amount</source>
        <translation>zenbatekoaren kopia</translation>
    
YES
The Basque translation "zenbatekoaren kopia" is not idiomatic and does not clearly convey the imperative "Copy amount". It reads like "copy of the amount" rather than giving a command.

Correct translation:
Zenbatekoa kopiatu
```

```
        <source>%1 is shutting down…</source>
        <translation>%1Itzaltzen ari da...</translation>
    
YES
There is a missing space between the format specifier and the translation text ("%1Itzaltzen" instead of "%1 Itzaltzen"). Additionally, the ellipsis should match the source ("…" vs "..."). The correct form in Basque would also make the translation more natural.

Correct translation:
%1 itzaltzen ari da…
```

```
        <source>IP address of the proxy (e.g. IPv4: 127.0.0.1 / IPv6: ::1)</source>
        <translation>Proxyaren IP helbidea  (IPv4: 127.0.0.1 / IPv6: ::1 adibidez )</translation>
    
YES
There are minor whitespace issues and the position of "adibidez" (e.g.) is inconsistent with the English source. In Basque, "adibidez" should directly follow the examples, not be at the end in parenthesis. Also, there is an unnecessary double space after "helbidea".

Correct translation:
Proxyaren IP helbidea (adibidez, IPv4: 127.0.0.1 / IPv6: ::1)
```

```
        <source>This change would require a client restart.</source>
        <translation>Aldaketa honek clienta berriro piztea eskatzen du</translation>
    
YES
The translation uses "clienta," which is a mix of Basque and Spanish/English ("client"). In Basque, the correct term would be "bezeroa" for "client." Furthermore, a period is missing at the end of the sentence to match the source punctuation.

Correct translation:
Aldaketa honek bezeroa berrabiaraztea eskatzen du.
```

```
        <source>Fee:</source>
        <translation>Ordainketa:</translation>
    
YES
The translation is inaccurate. 'Ordainketa' means 'payment', not 'fee' (which would be 'komisio' or 'tasak' in Basque). 'Fee:' should be translated as 'Komisioa:' or 'Tasa:' in this context.

Correct translation:
Komisioa:
```

```
        <source>Copy amount</source>
        <translation>zenbatekoaren kopia</translation>
    
YES
The Basque translation "zenbatekoaren kopia" is not idiomatic and does not clearly convey the imperative "Copy amount". It reads like "copy of the amount" rather than giving a command.

Correct translation:
Zenbatekoa kopiatu
```

```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>%1 konfirmazio</translation>
    
YES
The translation is incorrect because "konfirmazio" is not correct in Basque for "confirmations". The correct translation should be "konfirmazio" for singular, but for plural it should be "konfirmazio", which is still not quite right; the correct plural form in Basque is "konfirmazio". However, the actual Basque for "confirmation" is "berrespen", and the plural form is "berrespen". Additionally, the word is missing the plural suffix and adaptation for "%1" (e.g. "%1 berrespen").

Correct translation:
%1 berrespen
```

```
        <source>Mined</source>
        <translation>Meatua</translation>
    
YES
The translation "Meatua" is incorrect in Basque. The correct term for "Mined" in the context of Bitcoin (referring to coins that have been produced through mining) is "Meatua". However, "Meatua" in Basque more often means "mine" (noun: a mine, as in a coal mine). The correct translation for the verb "Mined" (as in "has been mined") is "Meatutako".

Correct translation:
Meatutako
```

```
        <source>This week</source>
        <translation>Aste honetankoak</translation>
    
YES
The translation "Aste honetankoak" is incorrect and ungrammatical in Basque. The correct translation for "This week" is "Aste hau".

Correct translation:
Aste hau
```

```
        <source>Mined</source>
        <translation>Meatua</translation>
    
YES
The translation "Meatua" is incorrect in Basque. The correct term for "Mined" in the context of Bitcoin (referring to coins that have been produced through mining) is "Meatua". However, "Meatua" in Basque more often means "mine" (noun: a mine, as in a coal mine). The correct translation for the verb "Mined" (as in "has been mined") is "Meatutako".

Correct translation:
Meatutako
```
</details>

Number of issues: 21.
