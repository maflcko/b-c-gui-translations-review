# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>ca</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bca%5D%20request)


<!-- cache_translation_check_ca_6e7e27a0c71fa0d7a505aa9f7741b5b3076adce9ff70d7a7c6106050ec6ed8c0 -->
```
        <source>Copy the currently selected address to the clipboard</source>
        <translation>Copia les adreçes seleccionades al porta-retalls</translation>
    
ERR
The translation uses the plural and contains a spelling error (“adreçes” should be “adreces”). It should be singular to match the source, and “currently” can be reflected explicitly.

Correct translation:
Copia l'adreça seleccionada actualment al porta-retalls
```

<!-- cache_translation_check_ca_1ef7dd59fbcc90e12fc6ab0aef28b3294f9490ce19799998803852e2537db485 -->
```
        <source>Choose the address to receive coins with</source>
        <translation>Trieu l'adreça on rebre les monedes amb</translation>
    
ERR
The Catalan sentence is ungrammatical/awkward, ending with the preposition "amb". It should be rephrased idiomatically.

Correct translation:
Trieu l'adreça per rebre les monedes
```

<!-- cache_translation_check_ca_2a03b9585912c1550989c8e9fb9fe8944a0e4753da5e94d4cc0f44e4f9daabac -->
```
        <source>Error: %1</source>
        <translation>Avís: %1</translation>
    
ERR
Severity changed: "Error" was translated as "Avís" (Warning).

Correct translation:
Error: %1
```

<!-- cache_translation_check_ca_ceea8edca337277da702f6a3afdfa81fbaa9d7b836e0ef13d1f40fdf93aed2ee -->
```
        <source>Default system font "%1"</source>
        <translation>%1Sistema de tipus de lletra per defecte "% 1"</translation>
    
ERR
The placeholder is duplicated and malformed ("$% 1"), and the word order/spacing is incorrect. It should include the single %1 placeholder exactly as in the source and proper Catalan phrasing.

Correct translation:
Tipus de lletra del sistema per defecte "%1"
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

<!-- cache_translation_check_ca_01bcdbb4c2507786e5f8f91a1edf787b6465f9add08ae841ffb818be6b1a5f67 -->
```
        <source>&amp;Receive</source>
        <translation>&amp;Rep</translation>
    
ERR
Catalan UI convention prefers the infinitive form. "Rep" (imperative) sounds odd for a menu item. Keep the single ampersand for the shortcut.

Correct translation:
&Rebre
```

<!-- cache_translation_check_ca_ca626bf9b2d0ce74d2e623f27deb30547b710f0d66268167e907a8c111a56c32 -->
```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>Encripta les claus privades pertanyents de la cartera</translation>
    
ERR
"pertanyents de" is ungrammatical in Catalan; it should be "que pertanyen a". Also, "wallet" is better rendered as "moneder" in this context, and including "teu" reflects "your".

Correct translation:
Encripta les claus privades que pertanyen al teu moneder
```

<!-- cache_translation_check_ca_90e43b68563733b6449f96244242f0f4ea71096ba67276c5fd7ec712524b24c7 -->
```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Signa els missatges amb la seva adreça de Bitcoin per a provar que les posseeixes</translation>
    
ERR
Inconsistencies in number and register: uses singular "adreça" but source is plural "addresses"; mixes "Signa" (informal) with "la seva" (formal/third person). Also pronoun agreement mismatch.

Correct translation:
Signa els missatges amb les teves adreces de Bitcoin per provar que en ets el propietari
```

<!-- cache_translation_check_ca_7315aa6db96914c150e1ba81d2d911968a9fc5dcdaf4b9dd4e884f79b5724b1b -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>&amp;Carrega el PSBT des del fitxer ...</translation>
    
ERR
Issues:
- Ellipsis should use the single character (…) as in the source, without a preceding space.
- Using "des d'un fitxer" better matches the indefinite "from file" in the source.
- Remove the extra space before the ellipsis.

Correct translation:
&Carrega el PSBT des d'un fitxer…
```

<!-- cache_translation_check_ca_b5f01fb3ee4b74c0a6d055c16cb33faea84eaa6b7dd22462459893965fc962fc -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>Carrega la PSBT des del porta-retalls.</translation>
    
ERR
Missing shortcut marker '&' and the ellipsis should be preserved; a period was used instead.

Correct translation:
&Carrega la PSBT des del porta-retalls…
```

<!-- cache_translation_check_ca_2a03b9585912c1550989c8e9fb9fe8944a0e4753da5e94d4cc0f44e4f9daabac -->
```
        <source>Error: %1</source>
        <translation>Avís: %1</translation>
    
ERR
Severity changed: "Error" was translated as "Avís" (Warning).

Correct translation:
Error: %1
```

<!-- cache_translation_check_ca_162418b37ca08aed77d02e0af774e3ebfb30f5c2f6929263be73d3a6f8197e3f -->
```
        <source>Copy after fee</source>
        <translation>Copia la tarifa posterior</translation>
    
ERR
"tarifa posterior" is unnatural and changes the meaning. Use "comissió" and clarify it's the amount after the fee.

Correct translation:
Copia l'import després de la comissió
```

<!-- cache_translation_check_ca_95b6a47f2aca2b59154a5707ccd66327e7cdeb9d6d2929b878e7e3d27bc716d8 -->
```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>Migrant cartera &lt;b&gt;%1&lt;/b&gt;...</translation>
    
ERR
The Catalan phrasing is incorrect and missing the article. It should be "Migrant la cartera". Also, match the source’s ellipsis character.

Correct translation:
Migrant la cartera &lt;b&gt;%1&lt;/b&gt;…
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

<!-- cache_translation_check_ca_cf4a29d519ab43a038c1e7aea542f60015d34ecf72034b773b46fd2ceb0984bf -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>Nombre de fils de &amp;verificació d'scripts</translation>
    
ERR
Incorrect elision: "d'scripts" is wrong in Catalan; it should be "de scripts". Everything else is acceptable, and the single & is correctly included.

Correct translation:
Nombre de fils de &verificació de scripts
```

<!-- cache_translation_check_ca_d22b35eb5713286d40e7fa46d0a88d7f725b0338351b1f12170eb0156fc2731c -->
```
        <source>Prune &amp;block storage to</source>
        <translation>Prunar emmagatzemament de &amp;block a</translation>
    
ERR
Several issues:
- "Prunar" is incorrect; correct verb is "Poda".
- "emmagatzemament" is incorrect; correct noun is "emmagatzematge".
- "block" should be translated to "blocs".
- Keep exactly one '&' for the shortcut.

Correct translation:
Poda l'emmagatzematge de &blocs a
```

<!-- cache_translation_check_ca_dc7bb563aa1e7981ff1fce3591a64bff3c5fbd3979fc9cf4a2e30ab8fb5c9cf0 -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Permet connexions entrants</translation>
    
ERR
- The accelerator ampersand (&) from the source is missing in the translation; it must appear exactly once.
- Wording is slightly unnatural; “connexions d'entrada” is the more idiomatic Catalan.

Correct translation:
&Permetre connexions d'entrada
```

<!-- cache_translation_check_ca_4254e3a8de95f75e47090999c7b25c878423c6ee26bd935b3aef4805f7af34a4 -->
```
        <source>&amp;Third-party transaction URLs</source>
        <translation>URL de transaccions de tercers</translation>
    
ERR
The translation is missing the required single '&' accelerator marker.

Correct translation:
&URL de transaccions de tercers
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

<!-- cache_translation_check_ca_6078b1947ebd38c09c2a181d10802b183f93032ddb92a8e4c732f1deefd110d8 -->
```
        <source>no high bandwidth relay selected</source>
        <translation>cap trànsit de gran amplada de banda ha estat seleccionat</translation>
    
ERR
"relay" was mistranslated as "trànsit", and the sentence structure is unidiomatic. It should use the impersonal "no s'ha seleccionat cap ...".

Correct translation:
No s'ha seleccionat cap relé d'alta amplada de banda
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

<!-- cache_translation_check_ca_a457f84febae2f7b054719132dea3d37f1c87fbb4bd562abd349f3d8f5f6b32c -->
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
    
ERR
Placeholders %7 and %8 are misplaced and have added spaces around them. According to the note, %7 must directly precede the warning text and %8 must directly follow the final period, with no spaces. Also, the translation reordered "%7" after "ADVERTIMENT" and added a colon in the wrong place. Preserve the blank line before the warning as in the source.

Correct translation:
Benvingut a la consola RPC %1.
Utilitzeu les fletxes amunt i avall per a navegar per l'historial i %2 per a esborrar la pantalla.
Utilitzeu %3 i %4 per augmentar o reduir la mida de la lletra.
Escriviu %5 per a obtenir una visió general de les ordres disponibles.
Per a obtenir més informació sobre com utilitzar aquesta consola, escriviu %6.

%7ADVERTIMENT: Els estafadors han estat actius, dient als usuaris que escriguin ordres aquí, robant el contingut de la seva cartera. No utilitzeu aquesta consola sense entendre completament les ramificacions d'una ordre.%8
```

<!-- cache_translation_check_ca_5dc4a9c21e6ac4d90fa11729689ca7b292d79e5d992ada82c707f2edb98492e2 -->
```
        <source>Ban for</source>
        <translation>Bandeja per a</translation>
    
ERR
"Bandeja per a" means "tray for" and is unrelated. It should express banning duration.

Correct translation:
Bloquejar durant
```

<!-- cache_translation_check_ca_207e1f3689e0ef4a4b3dcf6961c243ba70c7d8d97edd10209191736c72a0ec70 -->
```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>L'ús de la tarifa de pagament pot provocar l'enviament d'una transacció que trigarà diverses hores o dies (o mai) a confirmar. Penseu a triar la possibilitat d'escollir la tarifa manualment o espereu fins que hagueu validat la cadena completa.</translation>
    
ERR
The term "fallbackfee" is mistranslated as "tarifa de pagament" and important Bitcoin terminology is off. The sentence is also awkward and redundant. Use "comissió" and "cadena de blocs".

Correct translation:
L'ús de la comissió de reserva (fallbackfee) pot fer que s'enviï una transacció que trigui diverses hores o dies (o que no es confirmi mai). Considereu establir la comissió manualment o espereu fins que hàgiu validat la cadena de blocs completa.
```

<!-- cache_translation_check_ca_162418b37ca08aed77d02e0af774e3ebfb30f5c2f6929263be73d3a6f8197e3f -->
```
        <source>Copy after fee</source>
        <translation>Copia la tarifa posterior</translation>
    
ERR
"tarifa posterior" is unnatural and changes the meaning. Use "comissió" and clarify it's the amount after the fee.

Correct translation:
Copia l'import després de la comissió
```

<!-- cache_translation_check_ca_4f04fa75288f7ce8ac8902ceed1954d53a14327e8d28deed0a69ea5c1d9529fd -->
```
        <source>Cr&amp;eate Unsigned</source>
        <translation>Creació sense firmar</translation>
    
ERR
Missing shortcut ampersand and wording is off (uses noun and Spanish-derived "firmar"). Use an imperative verb and include exactly one '&'.

Correct translation:
C&rea sense signar
```

<!-- cache_translation_check_ca_3dd971aa8a67336336bee816a1992d588398fa0d5336b417a3beb2074142c6e3 -->
```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>Substitució per tarifa sense senyalització, BIP-125</translation>
    
ERR
Missing final period and slightly unnatural phrasing; better to keep the established term. 

Correct translation:
Sense senyalitzar Replace-By-Fee, BIP-125.
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

<!-- cache_translation_check_ca_aa0b82fb430f16f526748043b19e67cff78f710bc9d7746f0843a8c4ad7a9f44 -->
```
        <source>The wallet data was successfully saved to %1.</source>
        <translation>S'han desat correctament %1 les dades de la cartera a .</translation>
    
ERR
The placement of %1 is incorrect, and the phrase "a ." is malformed. The correct order is to place "a %1" at the end.

Correct translation:
Les dades de la cartera s'han desat correctament a %1.
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

<!-- cache_translation_check_ca_a5f722b03b51d42bcf52954df5b92b0b6a6b58f1d32fccee6b096ea7d7a635c3 -->
```
        <source>Error reading %s! All keys read correctly, but transaction data or address metadata may be missing or incorrect.</source>
        <translation>S'ha produït un error en llegir %s. Totes les claus es llegeixen correctament, però les dades de la transacció o les entra des de la llibreta d'adreces podrien faltar o ser incorrectes.</translation>
    
ERR
The Catalan has grammatical errors ("es llegeixen" should be past tense) and a mistranslation ("les entra des de la llibreta d'adreces" is incorrect; should refer to address metadata). Punctuation should mirror the exclamation.

Correct translation:
S'ha produït un error en llegir %s! Totes les claus s'han llegit correctament, però les dades de la transacció o les metadades d'adreça poden faltar o ser incorrectes.
```

<!-- cache_translation_check_ca_b5b6b61b8323207521c42af7e9c245c6a99b2842ef381b912f37db025f94a203 -->
```
        <source>A fatal internal error occurred, see debug.log for details: </source>
        <translation>Error fatal intern, detalls a debug.log:</translation>
    
ERR
Issues:
- Awkward/incorrect phrasing ("detalls a debug.log"); should use "vegeu ... per als detalls".
- Missing the occurrence aspect ("S'ha produït...") is more natural.
- Missing the trailing space after the colon, which may affect concatenation.

Correct translation:
S'ha produït un error intern fatal, vegeu debug.log per als detalls:
```

<!-- cache_translation_check_ca_291f09a6c9804dd9140b9d2e408492d8ef452a56d5f44634fab8f3e9873e4d33 -->
```
        <source>Config setting for %s only applied on %s network when in [%s] section.</source>
        <translation>Configuració per a %s únicament aplicada a  %s de la xarxa quan es troba a la secció [%s].</translation>
    
ERR
The phrase "a  %s de la xarxa" is ungrammatical, there's an extra space, and the sentence is awkward. It should clearly state that the setting only applies to the %s network.

Correct translation:
El paràmetre de configuració per a %s només s'aplica a la xarxa %s quan és a la secció [%s].
```

<!-- cache_translation_check_ca_79319ca07c17fbd6d4bc4c486562531d4e066626015e2dfe261c6993099b7d1e -->
```
        <source>Error loading databases</source>
        <translation>Error llegint les bases de dades</translation>
    
ERR
The verb "llegint" means "reading," not "loading." The correct Catalan for "loading" is "carregant."

Correct translation:
Error carregant les bases de dades
```

<!-- cache_translation_check_ca_29b51966c7f3a6e683c70b73ac813f98c856129295a5924555a675ae79ba1581 -->
```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>Error: la suma de comprovació del fitxer bolcat no coincideix. S'ha calculat %s, s'esperava 
%s</translation>
    
ERR
There is an unintended newline before the second %s, causing a whitespace/format issue.

Correct translation:
Error: la suma de comprovació del fitxer bolcat no coincideix. S'ha calculat %s, s'esperava %s
```

<!-- cache_translation_check_ca_6802ea22fc700bf0aa9363f1db126b3107ad8c57555b8bd76c56cbd0770f1d3c -->
```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>Error: Keypool s’ha esgotat. Visiteu primer keypoolrefill</translation>
    
ERR
"Visiteu" (visit) is incorrect for "call" in a technical context; it should be "crideu" or "executeu". Also adding the article improves flow.

Correct translation:
Error: s’ha esgotat el keypool; crideu primer keypoolrefill
```

<!-- cache_translation_check_ca_19cf1ef1aa761000f85d025cb7d3cc3bfaf2db1f2264d75a10a10e11db6be3dd -->
```
        <source>Ignoring duplicate -wallet %s.</source>
        <translation>Ignorant -cartera duplicada %s.</translation>
    
ERR
The option flag "-wallet" should not be translated, and "Ignorant" is ungrammatical here. Use an impersonal form.

Correct translation:
S'ignora -wallet duplicat %s.
```

<!-- cache_translation_check_ca_443c43755c6a5bbede5d864d225e18208f41a4c5e9649ff107f1895ca6d5a326 -->
```
        <source>No addresses available</source>
        <translation>No hi ha adreçes disponibles</translation>
    
ERR
Misspelling: In Catalan, the plural of "adreça" is "adreces" (without cedilla before 'e').

Correct translation:
No hi ha adreces disponibles
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

Number of issues: 45.
