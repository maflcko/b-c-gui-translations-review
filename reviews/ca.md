# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>ca</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bca%5D%20request)


<!-- cache_translation_check_ca_6ef9b171efdc28ef93a36f0d902dc589ccd6b73175f0daa916e54cd827daf286 -->
```
        <source>Default system font "%1"</source>
        <translation>Tipus de lletra per defecte del sistema"%1"</translation>
    
ERR
Missing space before the quoted placeholder. It should be: Tipus de lletra per defecte del sistema "%1"
```

<!-- cache_translation_check_ca_46e24b6bc52f0135214e0bda6a6f81915efdb2de7182951598281cfefd2b0023 -->
```
        <source>Full Relay</source>
        <extracomment>Peer connection type that relays all network information.</extracomment>
        <translation>Transmissió completa</translation>
    
ERR
"Transmissió completa" misses the nuance of "relay" (retransmit). A more accurate Catalan translation is "Retransmissió completa".

Correct translation:
Retransmissió completa
```

<!-- cache_translation_check_ca_ef2f3a9cb56c69d6cf71ab7557a82cd4b7fd85d9deff8457170fd8ac83f555e1 -->
```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Signa els missatges amb les teves adreces de Bitcoin per provar que en són teves</translation>
    
ERR
The Catalan phrasing is slightly unidiomatic: "provar" here is better as "demostrar", and "en" is unnecessary. 

Correct translation:
Signa els missatges amb les teves adreces de Bitcoin per demostrar que són teves
```

<!-- cache_translation_check_ca_b456336f9a8bce8672cd5481cd3204a91418e529f81084b5ba150dc0d0b00333 -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>&amp;Carrega la PSBT des del fitxer…</translation>
    
ERR
Preposition/article use is off. It should be indefinite “from a file” in Catalan: “des d’un fitxer” instead of “des del fitxer”.

Correct translation:
&Carrega la PSBT des d'un fitxer…
```

<!-- cache_translation_check_ca_70d1bbdb0906d97a3ef5677b01a5d10a56194cd170c478486ea3b3546db5ccea -->
```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>Migrant la cartera &lt;b&gt;%1&lt;/b&gt;...</translation>
    
ERR
The verb form is incorrect; "Migrant la cartera" is ungrammatical in Catalan for this progress message. Also, the ellipsis should match the source’s ellipsis character.

Correct translation:
S'està migrant la cartera <b>%1</b>…
```

<!-- cache_translation_check_ca_dbde7bf47738bc763d5cbadb948623bb30e187c0a973c6a418ced2709b2785f5 -->
```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Restaurant la cartera &lt;b&gt;%1&lt;/b&gt;...</translation>
    
ERR
The translation uses three periods "..." instead of the single ellipsis character "…", which should match the source punctuation.

Correct translation:
Restaurant la cartera <b>%1</b>…
```

<!-- cache_translation_check_ca_cf4a29d519ab43a038c1e7aea542f60015d34ecf72034b773b46fd2ceb0984bf -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>Nombre de fils de &amp;verificació d'scripts</translation>
    
ERR
Incorrect elision: "d'scripts" is wrong in Catalan; it should be "de scripts". Everything else is acceptable, and the single & is correctly included.

Correct translation:
Nombre de fils de &verificació de scripts
```

<!-- cache_translation_check_ca_ae83ab0f685ce38cf2bdd2c841116bcbaa0b5d82246d655fac7d9e86e734f506 -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Permet les connexions entrants</translation>
    
ERR
The translation is missing the required '&' accelerator from the source.

Correct translation:
Permet les connexions e&ntrants
```

<!-- cache_translation_check_ca_4dc3346d02f04aa929e3972c24bebba3e5b7b7c40e7a052f0e2ecb4ba7626037 -->
```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>Temps transcorregut des que es va rebre d'aquest igual una transacció nova acceptada al nostre mempool.</translation>
    
ERR
"peer" is mistranslated as "igual" (a calque from Spanish). In Catalan for P2P contexts, "peer" should be "parell".

Correct translation:
Temps transcorregut des que es va rebre d'aquest parell una transacció nova acceptada al nostre mempool.
```

<!-- cache_translation_check_ca_9c80c5c75fcf2fe24035d721aab3fbf65defd5b35477eb838012913a53057557 -->
```
        <source>no high bandwidth relay selected</source>
        <translation>no s'ha seleccionat cap igual per transmissió d'alta amplada de banda</translation>
    
ERR
"relay" has been mistranslated as "igual" (peer). It should be "relé" or "repetidor" in this context. The rest is acceptable.

Correct translation:
no s'ha seleccionat cap relé d'alta amplada de banda
```

<!-- cache_translation_check_ca_41c5ea3288ad4942c84832891070a1ea9c124db08d279f16e73bfa05e746916c -->
```
        <source>&amp;Unban</source>
        <translation>&amp;Desbandeja</translation>
    
ERR
"Desbandeja" is not correct Catalan and reads like Spanish "bandeja" (tray). The intended action is to remove a ban; a clear Catalan UI term is "Desbloqueja".

Correct translation:
&Desbloqueja
```

<!-- cache_translation_check_ca_e8a871664916064cae73b81c6dd25afd821376d24426db1e3b7a79dbdcb29e78 -->
```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>Benvingut a la consola RPC %1.
Utilitzeu les fletxes amunt i avall per a navegar per l'historial i %2 per a esborrar la pantalla.
Utilitzeu %3 i %4 per augmentar o reduir la mida de la lletra.
Escriviu %5 per a obtenir una visió general de les ordres disponibles.
Per a obtenir més informació sobre com utilitzar aquesta consola, escriviu %6.
%7AVÍS : Els estafadors han estat actius, dient als usuaris que escriguin ordres aquí, robant el contingut de la seva cartera. No utilitzeu aquesta consola sense entendre completament les ramificacions d'una ordre.%8</translation>
    
ERR
There is an incorrect space before the colon in “AVÍS :”. In Catalan it should be “AVÍS:”. Also, mirroring the source, include the blank line before the warning.

Correct translation:
Benvingut a la consola RPC %1.
Utilitzeu les fletxes amunt i avall per navegar per l'historial i %2 per esborrar la pantalla.
Utilitzeu %3 i %4 per augmentar o reduir la mida de la lletra.
Escriviu %5 per obtenir una visió general de les ordres disponibles.
Per obtenir més informació sobre com utilitzar aquesta consola, escriviu %6.

%7AVÍS: Els estafadors han estat actius, dient als usuaris que escriguin ordres aquí, robant el contingut de la seva cartera. No utilitzeu aquesta consola sense entendre completament les conseqüències d'una ordre.%8
```

<!-- cache_translation_check_ca_48da809e09361d2975f7c04861b5cbb613fa3a747cef41664d8220aebb0fb5fb -->
```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>L'ús de la tarifa d'últim recurs (fallbackfee) pot provocar que envieu una transacció que trigui diverses hores o dies a confirmar-se (o que non es confirmi mai). Considereu triar la tarifa manualment o espereu fins que hagueu validat la cadena completa.</translation>
    
ERR
Contains a typo "non" instead of "no", and "hagueu" should be "hàgiu" in standard Catalan.

Correct translation:
L'ús de la tarifa d'últim recurs (fallbackfee) pot provocar que envieu una transacció que trigui diverses hores o dies a confirmar-se (o que no es confirmi mai). Considereu triar la tarifa manualment o espereu fins que hàgiu validat la cadena completa.
```

<!-- cache_translation_check_ca_c3ea4bfef119ca4e14057a92f742886fa07c5b581c126129f360d6e43fd95275 -->
```
        <source>S&amp;ubtract fee from amount</source>
        <translation>S&amp;ubstreu la tarifa de l'import</translation>
    
ERR
The verb "Substreu" is incorrect in Catalan, and "tarifa" is not the best term for Bitcoin fees; "comissió" is preferred. The accelerator is present once, which is fine.

Correct translation:
&Descompta la comissió de l'import
```

<!-- cache_translation_check_ca_05d60d2a1da0c1652016d0d01e5a93a257d834cdce7aef0771b5e6b487718b85 -->
```
        <source>Reset all sign message fields</source>
        <translation>Neteja tots els camps de signatura de missatges</translation>
    
ERR
"Reset" should be translated as "Restableix" (or "Reinicia"), not "Neteja" (which means "clear/clean"). The current translation changes the intended action.

Correct translation:
Restableix tots els camps de signatura de missatges
```

<!-- cache_translation_check_ca_b49a95996e952b99608c0837492020d0efe2a4af21e3991bf9d4a34af7dfd508 -->
```
        <source>A&amp;bandon transaction</source>
        <translation>A&amp;amp;bandona la transacció</translation>
    
ERR
The shortcut marker ampersand is double-escaped as "&amp;amp;", which will display incorrectly. There must be exactly one shortcut marker.

Correct translation:
A&amp;bandona la transacció
```

<!-- cache_translation_check_ca_199ecc7e0e82c25be59a4c466952516396a31a17a5eb2b500e5b991b3088a403 -->
```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>Es proporcionen més d'una adreça de vinculació onion. Utilitzant %s pel servei Tor onion creat automàticament.</translation>
    
ERR
- Verb agreement: "més d'una adreça" should take singular ("Es proporciona"), not plural ("Es proporcionen").
- Second sentence is a fragment; should be a finite verb ("S'utilitza") rather than a gerund.
- Slightly improved phrasing for "Tor onion service".

Correct translation:
Es proporciona més d'una adreça de vinculació onion. S'utilitza %s per al servei onion de Tor creat automàticament.
```

<!-- cache_translation_check_ca_b7b651ccb3548725a25c6ca3d1232002a0be6775736ba47d7828417231dbecc2 -->
```
        <source>No dump file provided. To use dump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>No s'ha proporcionat cap fitxer de bolcat. Per utilitzar la funció de bolcat, cal proporcionar -dumpfile=&lt;filename&gt;</translation>
    
ERR
The translation is accurate but is missing the final period in the second sentence.

Correct translation:
No s'ha proporcionat cap fitxer de bolcat. Per utilitzar la funció de bolcat, cal proporcionar -dumpfile=&lt;filename&gt;.
```

<!-- cache_translation_check_ca_0db4bd802579a027f4cbe7f2b27224d0eccaf6a6056e4683ec21a00e3644626d -->
```
        <source>A fatal internal error occurred, see debug.log for details: </source>
        <translation>S'ha produït un error intern fatal, consulteu debug.log per a més detalls:</translation>
    
ERR
The translation removes the trailing space after the colon present in the source. This may cause formatting issues if additional text is appended.

Correct translation:
S'ha produït un error intern fatal, consulteu debug.log per a més detalls:
```

<!-- cache_translation_check_ca_3df905a6885c0379c701cc0d781144ebc7c619573d8c3359db4aae967b715ace -->
```
        <source>Config setting for %s only applied on %s network when in [%s] section.</source>
        <translation>La configuració de %s només s'aplica a la xarxa %s quan és troba a la secció [%s].</translation>
    
ERR
Grammatical error: "és troba" should be "es troba". Also "paràmetre de configuració" is more precise.
Correct translation:
El paràmetre de configuració per a %s només s'aplica a la xarxa %s quan es troba a la secció [%s].
```

<!-- cache_translation_check_ca_87c31778c098a189f1c77f4cebd0c9a9f7ac0f9f280ead19f4014641352cc148 -->
```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>Error: la suma de comprovació del fitxer bolcat (checksum) no coincideix amb l'esperat. S'ha calculat %s, s'esperava  %s</translation>
    
ERR
There is an extra space before the second %s, and agreement is better with the feminine “l'esperada” to match “suma”.

Correct translation:
Error: la suma de comprovació del fitxer bolcat (checksum) no coincideix amb l'esperada. S'ha calculat %s, s'esperava %s
```

<!-- cache_translation_check_ca_734f22e63b85ac8077ebbc7e54c6554c34cc6bbb04f1532fce5551d69713b344 -->
```
        <source>Ignoring duplicate -wallet %s.</source>
        <translation>Ignorant -wallet %s duplicat.</translation>
    
ERR
The Catalan phrasing "Ignorant -wallet %s duplicat." is unidiomatic and ambiguous. A more natural and clear system message is impersonal: "S'ignora el -wallet %s duplicat."

Correct translation:
S'ignora el -wallet %s duplicat.
```

<!-- cache_translation_check_ca_d819ad6d68d99a34eed694ca17a344747c9763f7e7fd032ea904c88779f37dbb -->
```
        <source>Pruning blockstore…</source>
        <translation>Podant l'emmagatzematge de blocs...</translation>
    
ERR
The ellipsis character differs from the source (uses "..." instead of "…"). Use the same ellipsis as in the source.

Correct translation:
Podant l'emmagatzematge de blocs…
```

<!-- cache_translation_check_ca_562bd9415e849ded41ebe3d833484131baf981c1c484611346b706fca6a464d3 -->
```
        <source>Specified -walletdir "%s" does not exist</source>
        <translation>El -Walletdir "%s" especificat no existeix</translation>
    
ERR
The option name is case-sensitive and should remain lowercase as in the source. "Walletdir" was capitalized.

Correct translation:
El -walletdir "%s" especificat no existeix
```
</details>

Number of issues: 24.
