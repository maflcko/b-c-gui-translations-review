# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bca%5D%20request)



<details><summary>ca</summary>


<!-- cache_translation_check_ca_6ef9b171efdc28ef93a36f0d902dc589ccd6b73175f0daa916e54cd827daf286 -->
```
        <source>Default system font "%1"</source>
        <translation>Tipus de lletra per defecte del sistema"%1"</translation>
    
ERR
Missing space before the quoted placeholder. It should be: Tipus de lletra per defecte del sistema "%1"
```

<!-- cache_translation_check_ca_7f6a9af3c8931728b5d386e09e1b3db476be95069e4ee87478cd7b913731015f -->
```
        <source>Full Relay</source>
        <extracomment>Peer connection type that relays all network information.</extracomment>
        <translation>Trànsit completat</translation>
    
ERR
"Trànsit completat" means "completed traffic" and misinterprets "Relay". The correct Catalan for the network concept is "Retransmissió completa".

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

<!-- cache_translation_check_ca_c9e20245dbc8ce3e1029b9ad9a917bb6834dfe2cae252756b69a0718297ed08c -->
```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Restaurant cartera &lt;b&gt;%1&lt;/b&gt;...</translation>
    
ERR
- "Restaurant" is incorrect; it means "restaurant" (noun) rather than "restoring" (verb). It should be "Restaurant" as a gerund only when used correctly, but the natural form here is "S'està restaurant".
- Missing definite article "la" before "cartera".
- The ellipsis should use the single character "…" as in the source, not three periods "...".

Correct translation:
S'està restaurant la cartera &lt;b&gt;%1&lt;/b&gt;…
```

<!-- cache_translation_check_ca_c9e20245dbc8ce3e1029b9ad9a917bb6834dfe2cae252756b69a0718297ed08c -->
```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Restaurant cartera &lt;b&gt;%1&lt;/b&gt;...</translation>
    
ERR
- "Restaurant" is incorrect; it means "restaurant" (noun) rather than "restoring" (verb). It should be "Restaurant" as a gerund only when used correctly, but the natural form here is "S'està restaurant".
- Missing definite article "la" before "cartera".
- The ellipsis should use the single character "…" as in the source, not three periods "...".

Correct translation:
S'està restaurant la cartera &lt;b&gt;%1&lt;/b&gt;…
```

<!-- cache_translation_check_ca_f9f0ef5a7ed9026ef702a6be989e57a25b0e7c6d231e0738df9878b3619bcae2 -->
```
        <source>Maximum database cache size. Make sure you have enough RAM. A larger cache can contribute to faster sync, after which the benefit is less pronounced for most use cases. Lowering the cache size will reduce memory usage. Unused mempool memory is shared for this cache.</source>
        <extracomment>Tooltip text for Options window setting that sets the size of the database cache. Explains the corresponding effects of increasing/decreasing this value.</extracomment>
        <translation>Mida màxima de la memòria cau de la base de dades.  Assegureu-vos de tenir prou RAM. Una memòria cau més gran pot contribuir a una sincronització més ràpida, després de la qual el benefici és menys pronunciat per a la majoria dels casos d'ús.  Reduir la mida de la memòria cau reduirà l'ús de memòria.  La memòria mempool no utilitzada es comparteix per a aquesta memòria cau.</translation>
    
ERR
The translation contains unnecessary double spaces between sentences.

Correct translation:
Mida màxima de la memòria cau de la base de dades. Assegureu-vos de tenir prou RAM. Una memòria cau més gran pot contribuir a una sincronització més ràpida, després de la qual el benefici és menys pronunciat per a la majoria dels casos d'ús. Reduir la mida de la memòria cau reduirà l'ús de memòria. La memòria mempool no utilitzada es comparteix per a aquesta memòria cau.
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

<!-- cache_translation_check_ca_045d8394e2db3c3ebc8634c9cc3e253ea9f5b4bc204cafba69a9dc247de446cf -->
```
        <source>Copy to Clipboard</source>
        <translation>Copia al Clipboard</translation>
    
ERR
"Clipboard" is not translated into Catalan. It should be "porta-retalls".

Correct translation:
Copia al porta-retalls
```

<!-- cache_translation_check_ca_7329770a647e37936553412fbba15e72b96ddbf11fbfd0bf46a1b9e0690ac457 -->
```
        <source>Transaction broadcast successfully! Transaction ID: %1</source>
        <translation>La transacció s'ha emès correctament! ID de la transacció: 1%</translation>
    
ERR
The format specifier is incorrect. In the translation, "%1" has been changed to "1%", which will prevent the transaction ID from being displayed correctly.

Correct translation:
La transacció s'ha emès correctament! ID de la transacció: %1
```

<!-- cache_translation_check_ca_5cdaf36a6e5718765e670f188b076a29bf092b45611ee4b785f7142caca8ba54 -->
```
        <source>Transaction Relay</source>
        <translation>Transmissió de la transacció.</translation>
    
ERR
The translation includes a trailing period that is not present in the source text. Additionally, "Relay" in a networking context is more accurately translated as "retransmissió" and usually refers to transactions in general (plural).

Correct translation:
Transmissió de transaccions
```

<!-- cache_translation_check_ca_505c2ee1ef16fc7d215c9d7b8656ac6a8240d95d02b770e3a17cb080364694be -->
```
        <source>Address Relay</source>
        <extracomment>Text title for the Address Relay field in the peer details area, which displays whether we relay addresses to this peer (Yes/No).</extracomment>
        <translation>Adreça de transmissió.</translation>
    
ERR
The translation includes a trailing period that is not present in the source text. Furthermore, in the context of a technical field title or label, "Transmissió d'adreces" is a more accurate translation for "Address Relay" than "Adreça de transmissió" (which would imply "Transmission address").

Correct translation:
Retransmissió d'adreces
```

<!-- cache_translation_check_ca_b300b36a5f63ef8cb27758913276bb7a31efe222564eb8234117476334af711d -->
```
        <source>Addresses Processed</source>
        <extracomment>Text title for the Addresses Processed field in the peer details area, which displays the total number of addresses received from this peer that were processed (excludes addresses that were dropped due to rate-limiting).</extracomment>
        <translation>Adreces processades.</translation>
    
ERR
The translation includes a trailing period that is not present in the source text. In UI labels and titles, punctuation should match the source.

Correct translation:
Adreces processades
```

<!-- cache_translation_check_ca_e091bb3498f48866dab7b214a725a8f6d972a22196caecb758dafa0e3823b591 -->
```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>El temps transcorregut des que es va rebre d'aquesta transacció una nova transacció acceptada al nostre igual.</translation>
    
ERR
The Catalan translation is ungrammatical and mistranslates "peer" as "igual" and includes a redundant/incorrect reference to "aquesta transacció". It should clearly state the elapsed time since a new transaction from this peer, accepted into our mempool, was received.

Correct translation:
Temps transcorregut des que es va rebre d'aquest parell una nova transacció acceptada al nostre mempool.
```

<!-- cache_translation_check_ca_3a1d40980e262a7490fc7adaac9271e313f74e5dcb47b39d69efe8b549882101 -->
```
        <source>Outbound Block Relay: does not relay transactions or addresses</source>
        <extracomment>Explanatory text for an outbound peer connection that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>Trànsit de blocs de sortida: no transmet trànsit ni adreces</translation>
    
ERR
"trànsit" is incorrect for "transactions" (should be "transaccions"), and "Block Relay" is better rendered as "Retransmissió de blocs" rather than "Trànsit de blocs".

Correct translation:
Retransmissió de blocs de sortida: no retransmet transaccions ni adreces
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

<!-- cache_translation_check_ca_66824e60fbba81658981816825e5c71ea5607ad3e093ee964bfefb75e958da5a -->
```
        <source>Reset all sign message fields</source>
        <translation>Neteja tots els camps de clau</translation>
    
ERR
The translation misinterprets "sign message" as "key" ("clau") and changes the meaning. It should refer to the "Sign message" fields.

Correct translation:
Restableix tots els camps de signatura del missatge
```

<!-- cache_translation_check_ca_565ecc6998e06a725fbfbc24d77131e09f3461a43fb6e61cf9ee76b25167efe2 -->
```
        <source>A&amp;bandon transaction</source>
        <translation>Transacció d'a&amp;bandonar</translation>
    
ERR
The Catalan phrasing is awkward ("Transacció d'abandonar") and not a natural UI command. Use an imperative verb form. Keep exactly one ampersand.

Correct translation:
A&bandona la transacció
```

<!-- cache_translation_check_ca_ce133c2a268ef694c7de10c5dce275c4a58660209fdfe2ac42522c7b0c4fd0c3 -->
```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation> Es proporciona més d'una adreça de vinculació. Utilitzant %s pel servei Tor onion automàticament creat.</translation>
    
ERR
- Leading unwanted space at the start of the translation.
- Missing "onion" in the first sentence ("onion bind address" not fully translated).
- The second sentence uses a gerund fragment; better as a finite verb.
- Minor style improvement: "per al" instead of "pel".

Correct translation:
S'han proporcionat més d'una adreça de vinculació onion. S'utilitza %s per al servei onion de Tor creat automàticament.
```

<!-- cache_translation_check_ca_60ee04085d718f3b7e19859e42a558da434847292d74ae90417fb84f3fb0af67 -->
```
        <source>No dump file provided. To use createfromdump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>No s'ha proporcionat cap fitxer de bolcat. Per a utilitzar createfromdump, s'ha de proporcionar&lt;filename&gt;.</translation>
    
ERR
The translation omits the required option "-dumpfile=" and the encoded placeholder, and it lacks a space before the filename placeholder.

Correct translation:
No s'ha proporcionat cap fitxer de bolcat. Per utilitzar createfromdump, s'ha de proporcionar -dumpfile=&lt;filename&gt;.
```

<!-- cache_translation_check_ca_57e67dc9a8ea6bfcf19dbaac5232976723665c7f264f14028e2972f5d08183bd -->
```
        <source>No dump file provided. To use dump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>No s'ha proporcionat cap fitxer de bolcat. Per a bolcar, cal proporcionar&lt;filename&gt;.</translation>
    
ERR
The option flag "-dumpfile=<filename>" is missing in the translation, and there is a spacing issue before <filename>. The flag must be preserved exactly.

Correct translation:
No s'ha proporcionat cap fitxer de bolcat. Per utilitzar el bolcat, s'ha de proporcionar -dumpfile=&lt;filename&gt;.
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

<!-- cache_translation_check_ca_d3b576c178cad3f527c4117aa62fb5eebd381401ad0dcee9f1cd125c2e25ecd0 -->
```
        <source>Pruning blockstore…</source>
        <translation>Taller de poda...</translation>
    
ERR
"Taller de poda..." means "pruning workshop" and changes the meaning. Also the ellipsis should match the source (…) rather than three dots.

Correct translation:
S'està podant el magatzem de blocs…
```
</details>

Number of issues: 32.
