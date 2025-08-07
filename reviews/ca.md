# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ca</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bca%5D%20low%20quality)


```
        <source>Choose the address to receive coins with</source>
        <translation>Trieu l'adreça on rebre les monedes amb</translation>
    
YES
The translation is awkward and contains an unnecessary "amb" ("with") at the end, which doesn't match natural Catalan syntax. A more accurate translation would be:

Correct translation:
Trieu l'adreça on rebre les monedes

Alternatively, more standard and natural:
Trieu l'adreça per rebre les monedes
```

```
        <source>Error: %1</source>
        <translation>Avís: %1</translation>
    
YES
The translation is incorrect. The English "Error: %1" should be translated as "Error: %1" in Catalan, not "Avís: %1" ("Avís" means "Warning").

Correct translation:
Error: %1
```

```
        <source>Full Relay</source>
        <extracomment>Peer connection type that relays all network information.</extracomment>
        <translation>Trànsit completat</translation>
    
YES
The translation "Trànsit completat" does not accurately convey the meaning of "Full Relay" in the context of Bitcoin, where it refers to a peer type that relays all network information. The translation should be "Relé complet" or "Transmissió completa".

Correct translation:
Relé complet
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>Encripta les claus privades pertanyents de la cartera</translation>
    
YES
The translation contains an error: "pertanyents de la cartera" is incorrect in Catalan. The correct phrase is "que pertanyen a la cartera".

Correct translation:
Encripta les claus privades que pertanyen a la cartera
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Signa els missatges amb la seva adreça de Bitcoin per a provar que les posseeixes</translation>
    
YES
The translation contains an inconsistency in the use of formal and informal address ("seva" is formal, while "les posseeixes" is informal and also uses plural for "them" but "adressa" is singular). Also, "la seva adreça de Bitcoin" is singular, but "them" refers to multiple addresses. The translation should reflect the plural "addresses" as in the source.

Correct translation:
Signa els missatges amb les teves adreces de Bitcoin per provar que en són teves
```

```
        <source>Error: %1</source>
        <translation>Avís: %1</translation>
    
YES
The translation is incorrect. The English "Error: %1" should be translated as "Error: %1" in Catalan, not "Avís: %1" ("Avís" means "Warning").

Correct translation:
Error: %1
```

```
        <source>Copy after fee</source>
        <translation>Copia la tarifa posterior</translation>
    
YES
The translation is incorrect. "Copia la tarifa posterior" does not convey the intended meaning of "Copy after fee" in the context of Bitcoin (i.e., copying the amount after the fee has been subtracted). The current translation also has an awkward phrasing in Catalan.

Correct translation:
Copia l'import després de la comissió
```

```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>Migrant cartera &lt;b&gt;%1&lt;/b&gt;...</translation>
    
YES
The translation "Migrant cartera" is incorrect. The verb “migrant” is not the proper Catalan form and should be “Migrant la cartera”. Also, the ellipsis should use the correct typographical character if possible (“…” instead of three periods), mimicking the source. Additionally, while the original uses the Unicode ellipsis character (…), the translation used '...'.

Correct translation:
Migrant la cartera &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Restaurant cartera &lt;b&gt;%1&lt;/b&gt;...</translation>
    
YES
There are two minor issues:
1. The ellipsis: In the source, a Unicode ellipsis (‘…’, U+2026) is used. In the translation, three periods ("...") are used. It's preferable to keep the style consistent and use the Unicode ellipsis.
2. "Restaurant" should be "Restaurant" if the Catalan translation for "Restoring" is correct. Actually, "Restoring" should be "Restaurant" as a participle, so "Restaurant cartera" is accurate.

Correct translation:
Restaurant cartera &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Copy to Clipboard</source>
        <translation>Copia al Clipboard</translation>
    
YES
"Copia al Clipboard" is not proper Catalan. The word "Clipboard" should be translated as "Portapapers" in Catalan.

Correct translation:
Copia al portapapers
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>El temps transcorregut des que es va rebre d'aquesta transacció una nova transacció acceptada al nostre igual.</translation>
    
YES
The translation is inaccurate and has grammar issues. 'Des que es va rebre d'aquesta transacció una nova transacció acceptada al nostre igual' does not make sense in Catalan, and the sentence structure is incorrect. "Igual" is not commonly used for "peer" in this context; "parella" or "company" might be more appropriate, but often "peer" is directly translated as "peer" in technical contexts or "node" in cryptocurrencies. "Elapsed time" is better as "Temps transcorregut".

Correct translation:
El temps transcorregut des que es va rebre d'aquest igual (peer) una transacció nova acceptada al nostre mempool.
```

```
        <source>Outbound Block Relay: does not relay transactions or addresses</source>
        <extracomment>Explanatory text for an outbound peer connection that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>Trànsit de blocs de sortida: no transmet trànsit ni adreces</translation>
    
YES
The translation is problematic. "no transmet trànsit ni adreces" mistranslates "transactions" as "trànsit", which means "traffic", not "transactions". The translation should refer specifically to "transaccions" (transactions) rather than "trànsit".

Correct translation:
Trànsit de blocs de sortida: no transmet transaccions ni adreces
```

```
        <source>no high bandwidth relay selected</source>
        <translation>cap trànsit de gran amplada de banda ha estat seleccionat</translation>
    
YES
The Catalan translation is awkward and incorrect. "Cap trànsit de gran amplada de banda ha estat seleccionat" literally translates as "no high bandwidth traffic has been selected", which is not equivalent to "no high bandwidth relay selected". The word "relay" (that is, a network relay) should be translated as "relé" or "repetidor", and the correct sentence structure should be used.

Correct translation:
no s'ha seleccionat cap relé d'alta amplada de banda
```

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
ADVERTIMENT %7: Els estafadors han estat actius, dient als usuaris que escriguin ordres aquí, robant el contingut de la seva cartera.
No utilitzeu aquesta consola sense entendre completament les ramificacions d'una ordre. %8</translation>
    
YES
Issues:
1. The warning section reverses the usage of %7 and %8. According to the English source, %7 and %8 are not meant to be part of the visible text but are tags that wrap the warning content; in the translation, "ADVERTIMENT %7: ..." inverts this logic and may not render the warning with the intended style.
2. The placement and usage of %7 and %8 should wrap the actual warning message exactly as in the source, without additional text outside the placeholders.
3. The period and spacing at the end could potentially result in double spacing or punctuation issues depending on how %8 is used at runtime.
4. There is one minor fidelity issue: "una ordre" should agree in gender with "comandament" if meant to refer to "command" (Catalan can use "ordre" for "command", which is feminine, so it's okay, but better to keep "ordre" plural-well). However, this is a minor style issue.

Correct translation:
Benvingut a la consola RPC %1.
Utilitzeu les fletxes amunt i avall per navegar per l'historial i %2 per netejar la pantalla.
Utilitzeu %3 i %4 per augmentar o reduir la mida de la lletra.
Escriviu %5 per obtenir una visió general de les ordres disponibles.
Per a més informació sobre com utilitzar aquesta consola, escriviu %6.

%7ADVERTIMENT: Els estafadors han estat actius, indicant als usuaris que escriguin ordres aquí i robant el contingut de la seva cartera. No utilitzeu aquesta consola sense entendre completament les ramificacions d'una ordre.%8
```

```
        <source>Ban for</source>
        <translation>Bandeja per a</translation>
    
YES
The translation is incorrect. "Bandeja per a" literally means "tray for" in Catalan, rather than "Ban for" (likely meaning "Ban for [time]" or "Ban for [reason]"). The correct Catalan translation for "Ban for" (in the context of banning someone for a duration) would be:

Correct translation:
Prohibició durant
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>L'ús de la tarifa de pagament pot provocar l'enviament d'una transacció que trigarà diverses hores o dies (o mai) a confirmar. Penseu a triar la possibilitat d'escollir la tarifa manualment o espereu fins que hagueu validat la cadena completa.</translation>
    
YES
The translation is problematic in the following ways:

1. "tarifa de pagament" does not properly convey "fallbackfee", which is a technical term referring to a default or fallback transaction fee, not a "payment fee."
2. "Penseu a triar la possibilitat d'escollir la tarifa manualment" is redundant and stylistically awkward—it should be direct, e.g., "Considereu triar la tarifa manualment."
3. The original structure "consider choosing your fee manually or wait..." is not adequately reflected.

Correct translation:
L'ús de la tarifa de reserva pot provocar que envieu una transacció que trigui diverses hores o dies (o mai) a confirmar-se. Considereu triar la tarifa manualment o espereu fins que hàgiu validat la cadena completa.
```

```
        <source>Copy after fee</source>
        <translation>Copia la tarifa posterior</translation>
    
YES
The translation is incorrect. "Copia la tarifa posterior" does not convey the intended meaning of "Copy after fee" in the context of Bitcoin (i.e., copying the amount after the fee has been subtracted). The current translation also has an awkward phrasing in Catalan.

Correct translation:
Copia l'import després de la comissió
```

```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>Substitució per tarifa sense senyalització, BIP-125</translation>
    
YES
The translation is not fully accurate and does not reflect the structure of the source sentence. The source explicitly begins with "Not signalling Replace-By-Fee", implying the action is not being performed. The translation could be misread as "Replace by fee without signalling". Additionally, the term "Replace-By-Fee" is best left untranslated in this technical context. There is also a missing period at the end, and a minor stylistic improvement is needed.

Correct translation:
No s'està senyalitzant Replace-By-Fee, BIP-125.
```

```
        <source>Reset all sign message fields</source>
        <translation>Neteja tots els camps de clau</translation>
    
YES
The translation is inaccurate. "Neteja tots els camps de clau" means "Clear all key fields," which is not a correct rendering of "Reset all sign message fields." The term "sign message" should not be translated as "clau" (key), but instead should refer to the message-signing feature.

Correct translation:
Restableix tots els camps de signatura de missatges
```

```
        <source>Abandon transaction</source>
        <translation>Transacció d'abandonar</translation>
    
YES
The translation is incorrect. The English phrase "Abandon transaction" should be translated as an imperative ("Abandona la transacció") rather than as a noun phrase ("Transacció d'abandonar"), which sounds awkward and unnatural in Catalan.

Correct translation:
Abandona la transacció
```

```
        <source>The wallet data was successfully saved to %1.</source>
        <translation>S'han desat correctament %1 les dades de la cartera a .</translation>
    
YES
The Catalan translation has an incorrect word order and misplaced elements, resulting in an awkward and unclear sentence. The placeholder "%1" is also misplaced.

Correct translation:
Les dades de la cartera s'han desat correctament a %1.
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation> Es proporciona més d'una adreça de vinculació. Utilitzant %s pel servei Tor onion automàticament creat.</translation>
    
YES
There is a minor whitespace issue: an unnecessary space at the beginning of the translation. Additionally, "adreça de vinculació" is an awkward rendering for "onion bind address." For clarity, it is better to specify "adreça de vinculació onion". The phrase "automàticament creat" is fine but could also be more naturally as "creat automàticament" in Catalan.

Correct translation:
Es proporcionen més d'una adreça de vinculació onion. S'utilitza %s pel servei Tor onion creat automàticament.
```

```
        <source>No dump file provided. To use createfromdump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>No s'ha proporcionat cap fitxer de bolcat. Per a utilitzar createfromdump, s'ha de proporcionar&lt;filename&gt;.</translation>
    
YES
The translation omits the crucial '-dumpfile=' format specifier from the source, which is important for clarity and correct usage. Additionally, there is a missing space before '&lt;filename&gt;' in the translation.

Correct translation:
No s'ha proporcionat cap fitxer de bolcat. Per utilitzar createfromdump, cal proporcionar -dumpfile=&lt;filename&gt;.
```

```
        <source>No dump file provided. To use dump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>No s'ha proporcionat cap fitxer de bolcat. Per a bolcar, cal proporcionar&lt;filename&gt;.</translation>
    
YES
The translation omits the necessary format specifier "-dumpfile=&lt;filename&gt;" and the sense of the phrase "To use dump". Also, there is no space between "proporcionar" and "&lt;filename&gt;". The instruction to provide the argument is missing. 

Correct translation:
No s'ha proporcionat cap fitxer de bolcat. Per utilitzar la funció de bolcat, s'ha de proporcionar -dumpfile=&lt;filename&gt;.
```

```
        <source>No wallet file format provided. To use createfromdump, -format=&lt;format&gt; must be provided.</source>
        <translation>No s'ha proporcionat cap format de fitxer de cartera. Per a utilitzar createfromdump, s'ha de proporcionar&lt;format&gt;.</translation>
    
YES
The translation omits the "-format=" prefix before "&lt;format&gt;" in the last part, which is needed for accurate instructions. There is also missing spacing ("proporcionar&lt;format&gt;." should be "proporcionar -format=&lt;format&gt;.").

Correct translation:
No s'ha proporcionat cap format de fitxer de cartera. Per utilitzar createfromdump, s'ha de proporcionar -format=&lt;format&gt;.
```

```
        <source>Error reading %s! All keys read correctly, but transaction data or address metadata may be missing or incorrect.</source>
        <translation>S'ha produït un error en llegir %s. Totes les claus es llegeixen correctament, però les dades de la transacció o les entra des de la llibreta d'adreces podrien faltar o ser incorrectes.</translation>
    
YES
The translation contains a typo: "les entra des de la llibreta d'adreces" is incorrect ("entra des" is a typo/mistranslation for "metadades"). Also, "llibreta d'adreces" (address book) is more specific than the original "address metadata". In Bitcoin context, "address metadata" is broader.

Correct translation:
S'ha produït un error en llegir %s! Totes les claus s'han llegit correctament, però les dades de la transacció o les metadades de l'adreça podrien faltar o ser incorrectes.
```

```
        <source>Config setting for %s only applied on %s network when in [%s] section.</source>
        <translation>Configuració per a %s únicament aplicada a  %s de la xarxa quan es troba a la secció [%s].</translation>
    
YES
There is excess spacing between "a" and "%s" ("a  %s de la xarxa") and the phrase "de la xarxa" is inaccurate as it inverts the syntax and removes clarity compared to the English ("on %s network"). Also, "Configuració per a %s" should specify "la configuració de %s" for clarity. The translation loses the explicit connection to the "network" element. 

Correct translation:
La configuració de %s només s'aplica a la xarxa %s quan és a la secció [%s].
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>Error: la suma de comprovació del fitxer bolcat no coincideix. S'ha calculat %s, s'esperava 
%s</translation>
    
YES
There is an unwanted line break before the second %s, resulting in a whitespace/format issue. Otherwise, the translation is accurate and clear.

Correct translation:
Error: la suma de comprovació del fitxer bolcat no coincideix. S'ha calculat %s, s'esperava %s
```

```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>Error: Keypool s’ha esgotat. Visiteu primer keypoolrefill</translation>
    
YES
The translation uses "Visiteu primer keypoolrefill", where "visiteu" (visit) is not appropriate for an action like "call" (cridar/executar). The term "Keypool" should probably remain untranslated given the technical context. A more accurate translation would be:

Correct translation:
Error: El keypool s'ha esgotat, si us plau crideu primer keypoolrefill
```

```
        <source>Ignoring duplicate -wallet %s.</source>
        <translation>Ignorant -cartera duplicada %s.</translation>
    
YES
The translation is understandable but not fully correct and is slightly unidiomatic. "-wallet" should be kept unaltered (as it is likely a command-line parameter) and the message should better reflect standard Catalan usage.

Correct translation:
S'ignora -wallet duplicat %s.
```

```
        <source>Pruning blockstore…</source>
        <translation>Taller de poda...</translation>
    
YES
The translation is incorrect. "Taller de poda..." literally means "pruning workshop" in Catalan, which is not the intended meaning in the context of Bitcoin. The correct translation should convey that the blockstore is being pruned.

Correct translation:
S'està podant l'emmagatzematge de blocs...
or
S'està podant el bloc d'emmagatzematge...
```
</details>

Number of issues: 31.
