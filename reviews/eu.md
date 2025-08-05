# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>eu</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Beu%5D%20low%20quality)


```
        <source>Repeat new passphrase</source>
        <translation>Pasahitz berria errepiikatu</translation>
    
YES  
The word "errepiikatu" is incorrect in Basque. The correct verb to use for "repeat" is "errepikatu" (with one 'i' after 'rep'). Also, "Pasahitz berria" is correct for "new passphrase."  

Correct translation:  
Pasahitz berria errepikatu
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Diruzorroaren pasahitz berria sartu. &lt;br/&gt;Mesedez &lt;b&gt; hamar edo gehiago ausazko hizkiko&lt;/b&gt; pasahitza erabili, edo &lt;b&gt; gutxienez zortzi hitz&lt;/b&gt;</translation>
    
YES
The translation is incomplete and misses the end of the sentence. The English source ends with "eight or more words," but the Basque translation ends abruptly after "gutxienez zortzi hitz" ("at least eight words") without repeating or including "pasahitza erabili" or equivalent, making it incomplete and unclear.

Correct translation:
Diruzorroaren pasahitz berria sartu.&lt;br/&gt;Mesedez &lt;b&gt;hamar edo gehiago ausazko karaktere&lt;/b&gt; edo &lt;b&gt;gutxienez zortzi hitz&lt;/b&gt; dituzten pasahitzen bat erabili.
```

```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>GARRANTZITSUA: Diruzorroaren segurtasun-kopia, wallet.dat, erabilezina bihurtuko da enkriptazioa burutu ondoren. Ondorioz, segurtasun-kopia berriekin ordezkatu beharko zenituzke zure jada eginik dituzun diruzorroaren kopiak.</translation>
    
YES
The translation is not fully accurate and omits key details from the source. The source emphasizes replacing previous backups of the wallet file with the newly generated encrypted wallet file and warns that previous unencrypted backups become useless once you start using the new encrypted wallet. The translation only partially conveys these ideas and uses "wallet.dat" specifically, which is not present in the source. Also, the logical flow is somewhat altered.

Correct translation:
GARRANTZITSUA: Zure diruzorroaren fitxategiaren aurreko segurtasun-kopiak leundu berri eta enkriptatutako fitxategiarekin ordezkatu beharko dituzu. Segurtasun-arrazoiak direla eta, enkriptatu gabeko diruzorroaren kopia zaharrak erabilgarriak izango dira bakarrik zure diruzorro enkriptatua erabiltzen hasi arte.
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Kartera deszifratzeko sartu den pasahitza ez da zuzena. Karaktere nulua du (adib - zero byte). Passphrasak software honen bertsio bat bazuen 25.0 bertsioaren aurretik, mesedez, saia zaitez berriro karaktere hutsekin, lehen karaktere nulua barne hartu gabe. Arrakasta izanez gero, jar ezazu passphrase berri bat etorkizunean hori saihesteko.</translation>
    
YES  
The translation contains some errors and unnatural phrasing in Basque (eu). Also, format specifiers such as "ie - a zero byte" should be properly translated or explained, and some English words like "passphrase" and "software" appear untranslated or inconsistent with common Basque usage. The instruction about "characters up to — but not including — the first null character" is unclear and partly incorrect in the translation.

Correct translation:  
"Kartera deszifratzeko sartu den pasahitza ez da zuzena. Karaktere nulua dauka (hau da, zero byte bat). Software honen 25.0 bertsioaren aurretik pasahitza ezarri bazen, mesedez, saiatu berriro lehen karaktere nulura arteko karaktereekin — lehen karaktere nulua barne hartu gabe. Arrakasta izanez gero, ezarri mesedez pasahitz berri bat etorkizunean arazo hau saihesteko."

Notes:  
- "pasahitza" is preferable to "passphrase" (Basque word).  
- "hau da" better than "adib" (adib. = adibidez = for example), as original says "ie - a zero byte", meaning "that is".  
- Clearer instruction regarding characters before the first null character.  
- Removes awkward "karaktere hutsekin" (empty characters) and clarifies meaning.
```

```
        <source>Banned Until</source>
        <translation>Honarte debekatua </translation>
    
YES  
The translation adds an unnecessary trailing space and "Honarte" is incorrect. The correct Basque translation for "Banned Until" in this Bitcoin context (likely referring to a ban expiry) is "Debekatua arte" or "Debekatua izan arte" depending on formality. "Honarte" is not correct here.

Correct translation:  
Debekatua arte
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>%1 Konfigurazio fitxategian akatsa edo baliogabea izan daiteke</translation>
    
YES  
The translation has minor issues with word order and missing punctuation. The phrase "might be corrupt or invalid" is better translated as "korrupzioa edo baliogabea izan daiteke" or similar, maintaining the meaning clearly. Also, the placement of "%1" at the start without any article or connector sounds unnatural in Basque.

A better translation would be:  
"%1 konfigurazio-fitxategia hondatuta edo baliogabea izan daiteke."
```

```
        <source>Runaway exception</source>
        <translation>Ranaway exception</translation>
    
YES  
The translation incorrectly copies the English phrase but misspells "Runaway" as "Ranaway." Moreover, this is not a translation into Basque (language code 'eu'); it is just an English phrase with a typo.

Correct translation:  
"Irteerako salbuespena"
```

```
        <source>%1 d</source>
        <translation>%1 e</translation>
    
YES  
The source text "%1 d" likely stands for "%1 days" or similar, where "d" is an abbreviation for "days." The translated text "%1 e" uses "e," which is not a standard abbreviation for "day" or "days" in Basque ('eu'). In Basque, "day" is "egun," and a common abbreviation might be "eg" or "eg." The letter "e" alone is not appropriate and changes the meaning.

Correct translation:  
%1 eg
```

```
        <source>Change Passphrase…</source>
        <translation>aldatu pasahitza</translation>
    
YES  
The original English text uses an ellipsis ("…") indicating that the action will lead to another step or dialog, which is lost in the translation. Additionally, the translation lacks capitalization at the beginning, and the ellipsis should be included. A suitable corrected translation would be:

Aldatu pasahitza…
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Egiaztatu mesua Bitcoin helbide espezifikoarekin erregistratu direla ziurtatzeko</translation>
    
YES  
The translation has some minor issues: "mesua" should be plural ("mezuak") to correspond to "messages," and "Bitcoin helbide espezifikoarekin erregistratu direla" translates as "registered with the specified Bitcoin address," which is inaccurate because the source says "signed with specified Bitcoin addresses." Also, the source uses plural "addresses," so the translation should reflect that. The phrase "ziurtatzeko" ("to ensure") is correct in meaning but the syntax is not very natural in Basque.

A better translation would be:  
"Egiaztatu mezuak, Bitcoin helbide zehatzekin sinatu direla bermatzeko"  

This means "Verify messages to ensure they were signed with specified Bitcoin addresses," correctly reflecting plurality and terminology.
```

```
        <source>Fee:</source>
        <translation>Ordainketa:</translation>
    
YES  
The translation "Ordainketa" means "order" or "ordering" in Basque, which is incorrect in this context. The correct term for "Fee" (as in a charge or commission) in Basque is "Komisioa" or "Tasa".  

Correct translation:  
<translation>Komisioa:</translation>
```

```
        <source>Copy amount</source>
        <translation>zenbatekoaren kopia</translation>
    
YES
The translation is incorrect. "Copy amount" in the Bitcoin context should imply the action of copying the amount (verb), but "zenbatekoaren kopia" means "copy of the amount" (a noun phrase). The translation should convey the imperative or noun phrase consistent with interface actions.

A better translation is:
"Kopiatu zenbatekoa"  
which means "Copy the amount" (imperative verb form).
```

```
        <source>%1 is shutting down…</source>
        <translation>%1Itzaltzen ari da...</translation>
    
YES  
There is a spacing issue: "%1" and "Itzaltzen" are joined without a space. Also, the ellipsis in the source is a single character "…" (U+2026), but the translation uses three dots "...". It is better to use the proper ellipsis character to match the source format.

Correct translation:  
%1 Itzaltzen ari da…
```

```
        <source>IP address of the proxy (e.g. IPv4: 127.0.0.1 / IPv6: ::1)</source>
        <translation>Proxyaren IP helbidea  (IPv4: 127.0.0.1 / IPv6: ::1 adibidez )</translation>
    
YES
There are extra spaces before the opening parenthesis and before the closing parenthesis in the translation, which is improper formatting. Also, the placement of "adibidez" (meaning "for example") should be immediately after the colon without spaces.

Correct translation:
Proxyaren IP helbidea (IPv4: 127.0.0.1 / IPv6: ::1 adibidez)
```

```
        <source>This change would require a client restart.</source>
        <translation>Aldaketa honek clienta berriro piztea eskatzen du</translation>
    
YES
The word "clienta" is not the correct Basque term; Basque typically adapts foreign words more natively or uses loanwords with appropriate suffixes. Additionally, the sentence misses ending punctuation (a period). A better translation uses "bezeroa" or "klientea" for "client," and also adds the missing period.

Correct translation:
Aldaketa honek bezeroa berriro piztea eskatzen du.
```

```
        <source>Fee:</source>
        <translation>Ordainketa:</translation>
    
YES  
The translation "Ordainketa" means "order" or "ordering" in Basque, which is incorrect in this context. The correct term for "Fee" (as in a charge or commission) in Basque is "Komisioa" or "Tasa".  

Correct translation:  
<translation>Komisioa:</translation>
```

```
        <source>Copy amount</source>
        <translation>zenbatekoaren kopia</translation>
    
YES
The translation is incorrect. "Copy amount" in the Bitcoin context should imply the action of copying the amount (verb), but "zenbatekoaren kopia" means "copy of the amount" (a noun phrase). The translation should convey the imperative or noun phrase consistent with interface actions.

A better translation is:
"Kopiatu zenbatekoa"  
which means "Copy the amount" (imperative verb form).
```

```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>%1 konfirmazio</translation>
    
YES  
The Basque (eu) translation for "%1 confirmations" should use the plural form, since the number (%1) can be more than one. The correct plural form is "konfirmazioak". Also, there shouldn't be a trailing space or missing letter.  

Correct translation:  
%1 konfirmazioak
```

```
        <source>Mined</source>
        <translation>Meatua</translation>
    
YES  
The Basque word "Meatua" is incorrect and does not correspond to "Mined." The correct translation for "Mined" in the Bitcoin context (referring to coins or blocks obtained through mining) is "Meatutako."  

Correct translation:  
Meatutako
```

```
        <source>This week</source>
        <translation>Aste honetankoak</translation>
    
YES  
The translation "Aste honetankoak" is incorrect. The correct Basque translation for "This week" is "Aste hau" or "Aste honetakoa" if emphasizing "the one belonging to this week." The suffix "-ko" or "-tako" indicates belonging, but the plural suffix "-ak" at the end makes "honetankoak" incorrect and awkward.

Correct translation:  
Aste hau
```

```
        <source>Mined</source>
        <translation>Meatua</translation>
    
YES  
The Basque word "Meatua" is incorrect and does not correspond to "Mined." The correct translation for "Mined" in the Bitcoin context (referring to coins or blocks obtained through mining) is "Meatutako."  

Correct translation:  
Meatutako
```

```
        <source>Unable to generate initial keys</source>
        <translation>hasierako giltzak sortzeko ezgai</translation>
    
YES  
The translation is incomplete and ungrammatical in Basque ('eu'). "hasierako giltzak sortzeko ezgai" literally means "unable to generate initial keys," but "ezgai" is an incorrect or non-standard form for "unable." The correct Basque term for "unable" in this context is "ezinean" (meaning "incapable of" or "unable to").  

Correct translation:  
Hasierako giltzak sortzeko ezinean.
```
</details>
