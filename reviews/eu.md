# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>eu</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Beu%5D%20low%20quality)


```
        <source>Delete the currently selected address from the list</source>
        <translation>Ezabatu aukeratutako helbideak listatik</translation>
    
YES: The translation is problematic because it uses the plural "helbideak" (addresses) when the source text specifies the singular "address". The correct translation should use the singular form.
Ezabatu aukeratutako helbidea listatik
```

```
        <source>Repeat new passphrase</source>
        <translation>Pasahitz berria errepiikatu</translation>
    
YES. The translation is inaccurate. "Errepiikatu" is not a standard Basque word.

Pasahitz berria errepikatu
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Diruzorroaren pasahitz berria sartu. &lt;br/&gt;Mesedez &lt;b&gt; hamar edo gehiago ausazko hizkiko&lt;/b&gt; pasahitza erabili, edo &lt;b&gt; gutxienez zortzi hitz&lt;/b&gt;</translation>
    
YES: The translation incorrectly translates "random characters" as "random words". The correct translation should reflect "characters" as "karaktereak".

NO
```

```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>GARRANTZITSUA: Diruzorroaren segurtasun-kopia, wallet.dat, erabilezina bihurtuko da enkriptazioa burutu ondoren. Ondorioz, segurtasun-kopia berriekin ordezkatu beharko zenituzke zure jada eginik dituzun diruzorroaren kopiak.</translation>
    
YES: The translation is inaccurate and does not convey the original meaning correctly. It mentions the wallet.dat file specifically, which is not mentioned in the source. It also incorrectly states that the wallet.dat file will become unusable after encryption, rather than previous backups of the unencrypted file becoming useless after using the new encrypted file.
GARRANTZITSUA: Jada eginiko diruzorro fitxategi guztien segurtasun-kopia berriekin ordezkatu behar dira, berriki sortutako, enkriptatutako diruzorro fitxategiarekin. Segurtasun arrazoiengatik, enkriptatu gabeko diruzorro fitxategiaren aurreko segurtasun-kopiek ez dute balio izango, enkriptatutako diruzorro berria erabiltzen hasten zarenean.
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Zorroa desenkriptatzeko sartutako pasahitza okerra da.</translation>
    
YES, The translation uses "Zorroa" which means "fox" instead of "wallet". The correct translation for "wallet" in this context is "zorroa" or "monederoa".

NO
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Kartera deszifratzeko sartu den pasahitza ez da zuzena. Karaktere nulua du (adib - zero byte). Passphrasak software honen bertsio bat bazuen 25.0 bertsioaren aurretik, mesedez, saia zaitez berriro karaktere hutsekin, lehen karaktere nulua barne hartu gabe. Arrakasta izanez gero, jar ezazu passphrase berri bat etorkizunean hori saihesteko.</translation>
    
YES: The translation incorrectly states "lehen karaktere nulua barne hartu gabe" which translates to "without including the first null character". The source text states "up to — but not including — the first null character" which should be translated as "lehen karaktere nulua baino lehenagoko karaktereak".

Kartera deszifratzeko sartu den pasahitza ez da zuzena. Karaktere nulua du (adib - zero byte). Passphrasak software honen bertsio bat bazuen 25.0 bertsioaren aurretik, mesedez, saia zaitez berriro, lehen karaktere nulua baino lehenagoko karaktereak soilik erabiliz. Arrakasta izanez gero, jar ezazu passphrase berri bat etorkizunean arazo hau saihesteko.
```

```
        <source>Banned Until</source>
        <translation>Honarte debekatua </translation>
    
YES, The translation is problematic because it contains a trailing space and the term "Honarte debekatua" is not a standard or accurate translation for "Banned Until" in the context of Bitcoin.

The correct translation should be:
<translation>Debekatuta egon arte</translation>
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>%1 Konfigurazio fitxategian akatsa edo baliogabea izan daiteke</translation>
    
YES
The translation misses the format specifier '%1'.
%1 Konfigurazio fitxategia hondatuta edo baliogabe egon daiteke.
```

```
        <source>Runaway exception</source>
        <translation>Ranaway exception</translation>
    
YES, The translation contains a spelling error.
Correct translation: Salbuespen iheslari
```

```
        <source>%1 d</source>
        <translation>%1 e</translation>
    
YES. The provided translation incorrectly translates the 'd' to 'e'. In the context of Bitcoin transactions, 'd' typically represents days. Therefore, the translation should also use 'd' to maintain accuracy.

%1 d
```

```
        <source>Change Passphrase…</source>
        <translation>aldatu pasahitza</translation>
    
YES, The translation is problematic because it omits the ellipsis (...) from the source text.

Change Passphrase…
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Egiaztatu mesua Bitcoin helbide espezifikoarekin erregistratu direla ziurtatzeko</translation>
    
YES, The translation uses the singular "helbidearekin" (with the address) instead of the plural "helbideekin" (with the addresses) as implied by the source text.

The correct translation should be:
Egiaztatu mezuak Bitcoin helbide espezifikoekin sinatu direla ziurtatzeko
```

```
        <source>Fee:</source>
        <translation>Ordainketa:</translation>
    
YES - The translation of "Fee" to "Ordainketa" is incorrect in the context of Bitcoin. "Ordainketa" means "payment". The correct translation for "Fee" in this context is "Komisioa" or "Tasa".
The correct translation is:
<source>Fee:</source>
<translation>Komisioa:</translation>
```

```
        <source>Copy amount</source>
        <translation>zenbatekoaren kopia</translation>
    
YES
The translation is inaccurate and misses the intended meaning of "Copy amount". The provided translation "zenbatekoaren kopia" directly translates to "copy of the amount" which is not idiomatic or contextually appropriate for the action of copying an amount in a Bitcoin transaction.

The correct translation should be "Kopiatu zenbatekoa".

NO
YES
The translation is inaccurate and misses the intended meaning of "Copy amount". The provided translation "zenbatekoaren kopia" directly translates to "copy of the amount" which is not idiomatic or contextually appropriate for the action of copying an amount in a Bitcoin transaction.

The correct translation should be "Kopiatu zenbatekoa".
```

```
        <source>Copy after fee</source>
        <translation>Kopia kuotaren ondoren</translation>
    
YES: The translation is inaccurate. "Kopia kuotaren ondoren" translates to "Copy after quote", not "Copy after fee".

NO
```

```
        <source>Are you sure you wish to close all wallets?</source>
        <translation>Ziur diruzorro guztiak itxi nahi dituzula?</translation>
    
YES - The translation uses "diruzorro" which means "piggy bank". The correct translation for "wallet" in this context is "zorro".
Ziur zorro guztiak itxi nahi dituzula?
```

```
        <source>%1 is shutting down…</source>
        <translation>%1Itzaltzen ari da...</translation>
    
YES, The Basque translation is problematic. The word "Itzaltzen" means "shutting down" but it is missing the space after the placeholder %1. Also, the ellipsis (...) is missing from the translation.

Correct translation: %1Itzaltzen ari da...
```

```
        <source>IP address of the proxy (e.g. IPv4: 127.0.0.1 / IPv6: ::1)</source>
        <translation>Proxyaren IP helbidea  (IPv4: 127.0.0.1 / IPv6: ::1 adibidez )</translation>
    
YES: The phrase "adibidez" (for example) is misplaced. It should follow the examples it refers to, not the IPv6 address.
Proxyaren IP helbidea (adibidez IPv4: 127.0.0.1 / IPv6: ::1)
```

```
        <source>This change would require a client restart.</source>
        <translation>Aldaketa honek clienta berriro piztea eskatzen du</translation>
    
YES: The verb "piztea" (to light/ignite) is not the correct translation for "restart" in this context. The correct translation for "restart" would be "berriro hastea". Additionally, the original translation is missing a period at the end of the sentence.

NO: Aldaketa honek clienta berriro hastea eskatzen du.
```

```
        <source>Sent</source>
        <extracomment>Title of Peers Table column which indicates the total amount of network information we have sent to the peer.</extracomment>
        <translation>Bidalia</translation>
    
YES - The translation is incorrect and doesn't convey the meaning of "Sent" in the context of network activity. The correct translation for "Sent" in this context would be "Igoa".
        <source>Sent</source>
        <extracomment>Title of Peers Table column which indicates the total amount of network information we have sent to the peer.</extracomment>
        <translation>Igoa</translation>
```

```
        <source>Fee:</source>
        <translation>Ordainketa:</translation>
    
YES - The translation of "Fee" to "Ordainketa" is incorrect in the context of Bitcoin. "Ordainketa" means "payment". The correct translation for "Fee" in this context is "Komisioa" or "Tasa".
The correct translation is:
<source>Fee:</source>
<translation>Komisioa:</translation>
```

```
        <source>Copy amount</source>
        <translation>zenbatekoaren kopia</translation>
    
YES
The translation is inaccurate and misses the intended meaning of "Copy amount". The provided translation "zenbatekoaren kopia" directly translates to "copy of the amount" which is not idiomatic or contextually appropriate for the action of copying an amount in a Bitcoin transaction.

The correct translation should be "Kopiatu zenbatekoa".

NO
YES
The translation is inaccurate and misses the intended meaning of "Copy amount". The provided translation "zenbatekoaren kopia" directly translates to "copy of the amount" which is not idiomatic or contextually appropriate for the action of copying an amount in a Bitcoin transaction.

The correct translation should be "Kopiatu zenbatekoa".
```

```
        <source>Copy after fee</source>
        <translation>Kopia kuotaren ondoren</translation>
    
YES: The translation is inaccurate. "Kopia kuotaren ondoren" translates to "Copy after quote", not "Copy after fee".

NO
```

```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>%1 konfirmazio</translation>
    
YES, The pluralization of "confirmation" in Basque is incorrect. The correct translation should be "%1 konfirmazio%s".
NO
```

```
        <source>Mined</source>
        <translation>Meatua</translation>
    
YES - The translation is incorrect. "Meatua" is not a valid word in Basque. The correct translation for "Mined" in the context of Bitcoin is "Meatzatua".
Meatzatua
```

```
        <source>This week</source>
        <translation>Aste honetankoak</translation>
    
YES - The translation is grammatically incorrect and does not make sense in context. The word "honetankoak" is a plural noun form, which is not appropriate for "This week". A more accurate translation would be "Aste honetan".
Aste honetan
```

```
        <source>Mined</source>
        <translation>Meatua</translation>
    
YES - The translation is incorrect. "Meatua" is not a valid word in Basque. The correct translation for "Mined" in the context of Bitcoin is "Meatzatua".
Meatzatua
```

```
        <source>Unable to generate initial keys</source>
        <translation>hasierako giltzak sortzeko ezgai</translation>
    
YES, the translation is problematic. The verb conjugation and structure are incorrect. The correct translation should be "Ezgaitu hasierako giltzak sortzen" or "Hasierako giltzak sortzea ezgaitu".

NO
```
</details>
