# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>es</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bes%5D%20request)


<!-- cache_translation_check_es_64ff3a0da05f73093699038b8b5a5b80a4a2fa0ebf5c7aaebb28d2f5dd9d05b8 -->
```
        <source>Full Relay</source>
        <extracomment>Peer connection type that relays all network information.</extracomment>
        <translation>Transmisión completa</translation>
    
ERR
The Spanish "Transmisión completa" is understandable but not the best choice for the Bitcoin UI context: "relay" here means relaying/rebroadcasting network data, so "retransmisión" or "reenvío" is more accurate than "transmisión".

Correct translation:
Retransmisión completa
```

<!-- cache_translation_check_es_57f354034cf4969b75bd003cf0a88a42d1efac07406d58f43e6fe4c7832c6c12 -->
```
        <source>Address Fetch</source>
        <extracomment>Short-lived peer connection type that solicits known addresses from a peer.</extracomment>
        <translation>Búsqueda de dirección</translation>
    
ERR
The Spanish translation is not ideal: "Búsqueda de dirección" uses singular "dirección" and translates "fetch" as "búsqueda" (search), whereas in this context it refers to retrieving/obtaining peer addresses (usually plural).

Correct translation:
Obtención de direcciones

(Alternative: "Recuperación de direcciones")
```

<!-- cache_translation_check_es_8cf49beec188e30c4374a5941e5160afa4872226daf5f9870b380d5c48521ad3 -->
```
        <source>&amp;Hide</source>
        <translation>&amp;Ocultar </translation>
    
ERR
There is a stray space at the end of the translation ("&amp;Ocultar "), which can cause formatting issues.

Correct translation:
&amp;Ocultar
</reply>
```

<!-- cache_translation_check_es_f1cfa244210da6deff9fb1ec85f708b11e67abda6ed2e39002662ed752a53e0b -->
```
        <source>(un)select all</source>
        <translation>(des)selecionar todo</translation>
    
ERR
The Spanish translation has a misspelling: "selecionar" should be "seleccionar" (double "c").

Correct translation:
(des)seleccionar todo

(Alternative phrasing often used: "Seleccionar/deseleccionar todo")
```

<!-- cache_translation_check_es_88fffc940b0c0f7157365b0ed9c7b087e84758cd38b8a526518641c325fc116b -->
```
        <source>Received with label</source>
        <translation>Recibido con dirección</translation>
    
ERR
The Spanish translation changes the meaning: "label" was translated as "dirección" (address), which is incorrect in this context.

Correct translation:
Recibido con etiqueta
```

<!-- cache_translation_check_es_7c1ff35a25773b5ed18926af41af668176a06cf4c47f8fe970fb0f5b4fbf9981 -->
```
        <source>Received with address</source>
        <translation>Recibido con etiqueta</translation>
    
ERR
The Spanish translation uses "etiqueta" (label) instead of "dirección" (address), which changes the meaning.

Correct translation:
Recibido con dirección
```

<!-- cache_translation_check_es_ddbe5c772d9d256205e96515a5ff2874a950599631c28d99e3325b6744e0bafa -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>Copiar &amp;ID de transacción e índice de salidas</translation>
    
ERR
The Spanish has a grammatical mistake: "índice de salidas" should be singular ("índice de salida"). The ampersand is present exactly once (OK). 

Correct translation:
Copiar &ID de transacción e índice de salida
```

<!-- cache_translation_check_es_ea082291d36bbc76e7ad26daec9af96516739f34f9c2f01a131e08e91f8a880f -->
```
        <source>L&amp;ock unspent</source>
        <translation>B&amp;loquear no gastado</translation>
    
ERR
The Spanish is understandable but grammatically awkward/inaccurate. It should reflect plural/field context (unspent outputs) and keep a single & for the shortcut.

Suggested correction:
B&loquear salidas no gastadas

(keeps one & and uses a more natural, grammatically correct phrasing)
```

<!-- cache_translation_check_es_d0d2d8bc783190333c201aced7b9f4a1dea6e606567eee14d0eebb450afac7b0 -->
```
        <source>(0 = auto, &lt;0 = leave that many cores free)</source>
        <translation>(0 = auto, &lt;0 = deja esa cantidad de núcleos libres)</translation>
    
ERR
The Spanish uses "deja" (indicative/imperative) which is slightly incorrect in this descriptive context. The source uses infinitive-style phrasing; the translation should mirror that.

Correct translation:
(0 = auto, &lt;0 = dejar esa cantidad de núcleos libres)
```

<!-- cache_translation_check_es_8fa790086b6f8516a240f7b886fb5b22ba97b8c5f1583aeca1280567ebbf101c -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Activar controles de &amp;PSBT </translation>
    
ERR
There is a stray trailing space at the end of the translation. Also a more natural Spanish phrasing would include the article "los" (optional). The ampersand shortcut is present and correctly placed, but remove the extra whitespace.

Correct translations (choose one):

Activar controles de &PSBT
or
Activar los controles de &PSBT
```

<!-- cache_translation_check_es_a17a16fda08a88bf03c08e89d53c9aded432f71abffbedb3039e2dd4e766a567 -->
```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Establecer si se muestran los controles de PSBT</translation>
    
ERR
The Spanish is understandable but slightly awkward and misses the final period. "Establecer si se muestran los controles de PSBT" is literal but more natural would be "Si se deben mostrar los controles PSBT." Also keep the trailing period to match source.

Correct translation suggestions:
- Si se deben mostrar los controles PSBT.
- Mostrar los controles PSBT.
```

<!-- cache_translation_check_es_db6f1904a3025b65e3412569b63bebe156b0636a27c99130d917395409977a76 -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Usar proxy SOCKS&amp;5 para conectar a pares a través de los servicios anónimos de Tor:</translation>
    
ERR
The translation omits the word "separate" ("separado" or "independiente"), which changes the meaning. The translation also uses "servicios anónimos de Tor", whereas "onion services de Tor" or "servicios Onion de Tor" is the commonly accepted technical term in Spanish Bitcoin contexts. The & is properly present once. The format and spacing are correct.

Correct translation:
Usar un proxy SOCKS&5 separado para conectar a pares a través de los servicios Onion de Tor:
```

<!-- cache_translation_check_es_a6e7cf9e9ad40319d32ef46133bca630e794c92fc146d5638095b1f84bdd2aab -->
```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>Modo de privacidad activado para la pestaña de visión general. Para desenmascarar los valores, desmarcar los valores de Configuración-&gt;Enmascarar valores.</translation>
    
ERR
The Spanish is understandable but has awkward phrasing and a redundancy ("desmarcar los valores de ... Enmascarar valores") and could be more natural. Also "pestaña de visión general" is clunky — "Resumen" is the usual UI label.

Correct translation:
Modo de privacidad activado en la pestaña Resumen. Para desenmascarar los valores, desmarque Configuración -> Enmascarar valores.
```

<!-- cache_translation_check_es_3afee8600749fa4dcf961f303f2a1d6c6a1d1e5eec574a6741b1ddc96239a7fa -->
```
        <source>Failed to load transaction: %1</source>
        <translation>Error en la carga de la transacción: %1</translation>
    
ERR
Translation is understandable but slightly unnatural Spanish. Prefer the gerund/infinitive construction for this error message.

Correct translation:
Error al cargar la transacción: %1
```

<!-- cache_translation_check_es_310a5e0c2c0d69a9f4a34a689de7286e1863ebfcf9c367de1c385382d6e25ef8 -->
```
        <source>Transaction broadcast successfully! Transaction ID: %1</source>
        <translation>¡La transacción se ha difundido correctamente! Código ID de la transacción: %1</translation>
    
ERR
The translation is understandable and preserves the format specifier, but wording is slightly awkward for Spanish/Bitcoin context: "difundido" is less common than "transmitida" or "enviada", and "Código ID de la transacción" is redundant/unnatural.

Correct translation:
¡La transacción se ha transmitido correctamente! ID de la transacción: %1
```

<!-- cache_translation_check_es_99548199606555f1cd47756387413f1f35354270e5d4c6a047414ab6a1611e7c -->
```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>Transacción parcialmente firmada (binario) </translation>
    
ERR
Issues:
- Trailing whitespace at end of the translation.
- Gender agreement: "transacción" is feminine, so the parenthetical adjective should be "binaria" rather than "binario" (more natural in Spanish).

Correct translation:
Transacción parcialmente firmada (binaria)
```

<!-- cache_translation_check_es_8016175fab22cacfbc1b89643dc14e659bb3c1555682046ed947f7f8b0779c1b -->
```
        <source>PSBT saved to disk.</source>
        <translation>PSBT guardada en disco.</translation>
    
ERR
Minor grammatical issue: Spanish should include the article and typically uses masculine agreement for saved files ("guardado") if implied noun is "archivo". Also "en disco" is less natural than "en el disco".

Correct translation:
PSBT guardado en el disco.
```

<!-- cache_translation_check_es_a3e6b2ba4d665e42b16768a3e1e2e1a521bfe16cd09391153d5a4d93fef6c8bd -->
```
        <source>Pays transaction fee: </source>
        <translation>Pagar comisión por transacción:</translation>
    
ERR
The Spanish text uses the infinitive "Pagar ..." which doesn't match the English label "Pays transaction fee:" (third-person present / label). Also include the article for natural phrasing. Preserve any trailing space if the UI expects it.

Correct translation:
Paga la comisión de la transacción:
```

<!-- cache_translation_check_es_5db0de04de0381922b65c188b8bcf71452e69bc18124581684d602d6b793bcf4 -->
```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>No se puede iniciar bitcoin: controlador pulsar-para-pagar</translation>
    
ERR
Minor stylistic issues: "bitcoin" should be capitalized as "Bitcoin" (proper name) and the phrase "click-to-pay" is better left as-is or rendered more naturally in Spanish. Also include "de" after "controlador" for clarity.

Correct translation:
No se puede iniciar Bitcoin: controlador de click-to-pay
```

<!-- cache_translation_check_es_1de2c3ffc36919967dacc16e221885d94940c5ddcb22f989d5a6216e6adab131 -->
```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>«bitcoin: //» no es un URI válido. Use «bitcoin:» en su lugar.</translation>
    
ERR
The translation has an extra space inside the quoted URI ("bitcoin: //" instead of "bitcoin://") and uses English-style quotes; also the second sentence uses the English verb "Use" which is better translated into Spanish.

Correct translation:
«bitcoin://» no es un URI válido. Utilice «bitcoin:» en su lugar.
```

<!-- cache_translation_check_es_410f347fb8eabaf93ec0f6d2971cdba5a6fee7c366a45eeb6169a9a53a8ee035 -->
```
        <source>Cannot process payment request because BIP70 is not supported.
Due to widespread security flaws in BIP70 it's strongly recommended that any merchant instructions to switch wallets be ignored.
If you are receiving this error you should request the merchant provide a BIP21 compatible URI.</source>
        <translation>No se puede procesar la solicitud de pago debido a que no se mantiene BIP70.
Debido a los fallos de seguridad generalizados en el BIP70, se recomienda encarecidamente ignorar las instrucciones del comerciante para cambiar de monedero.
Si recibe este error, debe solicitar al comerciante que le proporcione un URI compatible con BIP21.</translation>
    
ERR
"no se mantiene BIP70" is awkward/incorrect Spanish. Use "no es compatible con BIP70" or "no se admite BIP70". Otherwise the translation is accurate and preserves meaning.

Correct translation:
No se puede procesar la solicitud de pago porque BIP70 no es compatible.
Debido a los fallos de seguridad generalizados en BIP70, se recomienda encarecidamente ignorar las instrucciones del comerciante para cambiar de monedero.
Si recibe este error, debe solicitar al comerciante que le proporcione un URI compatible con BIP21.
```

<!-- cache_translation_check_es_9bdb6308426f568abc9cd839ac22d6ab48d3ba9be551b757991044736f86008d -->
```
        <source>Peer</source>
        <extracomment>Title of Peers Table column which contains a unique number used to identify a connection.</extracomment>
        <translation>Pareja</translation>
    
ERR
"Pareja" in Spanish means a romantic or paired couple and is incorrect in this technical/networking context. The correct term for a network/Bitcoin peer is "Par" (or "Nodo" if you prefer emphasizing a node).

Correct translation:
Par
```

<!-- cache_translation_check_es_135481bf4c802ccbb841971c2a927af2279499b715ce4026cb48005948f65ab2 -->
```
        <source>Please, review your transaction. You can create and send this transaction or create a Partially Signed Bitcoin Transaction (PSBT), which you can save or copy and then sign with, e.g., an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can send their transaction or create a PSBT. This string is displayed when both private keys and PSBT controls are enabled.</extracomment>
        <translation>Revisa la transacción. Puedes crear y enviar esta transacción de Bitcoin parcialmente firmada (PSBT), que además puedes guardar o copiar y, luego, firmar; por ejemplo, con un monedero %1 sin conexión o un monedero de hardware compatible con PSBT.</translation>
    
ERR
The translation changes the meaning: it implies "this transaction" is a PSBT ("esta transacción de Bitcoin parcialmente firmada"), whereas the source says you can either create-and-send the transaction OR create a PSBT. Also the source requests "Please, review your transaction" — better as "Por favor, revisa..." or "Por favor, revise..." depending on formality.

Correct translation:
Por favor, revisa tu transacción. Puedes crear y enviar esta transacción, o crear una Transacción Bitcoin Parcialmente Firmada (PSBT), la cual puedes guardar o copiar y luego firmar, por ejemplo, con una cartera %1 sin conexión o con un monedero de hardware compatible con PSBT.
```

<!-- cache_translation_check_es_6a4a483fbbfdaa27a769412be502750c5615d14e5dc39f7abb6660cbde14d783 -->
```
        <source>The PSBT has been copied to the clipboard. You can also save it.</source>
        <translation>Se copió la  PSBT al portapapeles. También puedes guardarla.</translation>
    
ERR
There's an extra space between "la" and "PSBT" ("la  PSBT"). Also slightly more natural Spanish would use the present perfect.

Correct translation:
La PSBT se ha copiado al portapapeles. También puedes guardarla.
```

<!-- cache_translation_check_es_592f95278f23aaa28ea8f3f4f6b964e5dae84876c08ce33f8e4151671d460217 -->
```
        <source>PSBT saved to disk</source>
        <translation> PSBT guardada en disco</translation>
    
ERR
The translation has a leading space before "PSBT" which is a formatting issue. Also, a more natural Spanish phrasing would omit the extra space (the rest is acceptable). 

Correct translation:
<translation>PSBT guardada en disco</translation>
```

<!-- cache_translation_check_es_9105fef6298b2c5d564f5fd9bd7990fa62e5b69a0cbea7f57c1010044a19ce21 -->
```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Inmadura (%1 confirmaciones; estará disponibles después de %2)</translation>
    
ERR
There is a grammatical error: "disponibles" should match "Inmadura" (feminine singular), so it should be "disponible". Also, the semicolon should match the style of the original source, which uses a comma. The format specifiers are correctly preserved.

Correct translation:
Inmadura (%1 confirmaciones, estará disponible después de %2)
```

<!-- cache_translation_check_es_38c960faaaa5725e724613728b6f265ecba28cfd0eea5acf7ec11750e54bd26b -->
```
        <source>Unable to decode PSBT from clipboard (invalid base64)</source>
        <translation>No se puede decodificar la  PSBT desde el portapapeles (Base64 inválida)</translation>
    
ERR
There is an extra space before "PSBT" and "base64" should keep same case/style as source (or be all lowercase). Also slightly more natural Spanish: "del portapapeles" or keep "desde el portapapeles". 

Correct translation:
No se puede decodificar la PSBT desde el portapapeles (base64 inválida)
```

<!-- cache_translation_check_es_6e1f787c2bcac75e3ac2a4c3d14086500b6673e7484c49ac3fcadde8b631fbe0 -->
```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>El archivo de la  PSBT debe ser inferior a 100 MiB</translation>
    
ERR
Minor issues: extra double space before "PSBT" and awkward phrasing ("archivo de la PSBT"). Also more natural Spanish would be "archivo PSBT" or "archivo .psbt" and "menos de" rather than "inferior a".

Correct translation:
El archivo PSBT debe ser menor de 100 MiB.
```

<!-- cache_translation_check_es_31ba839a8cb4530c2edae42c5eb06114bd2832b0948b7b63ca18a545f4c6f078 -->
```
        <source>Unable to decode PSBT</source>
        <translation>No es posible descodificar la  PSBT</translation>
    
ERR
Problems:
- There is a double space before "PSBT" ("la  PSBT").
- "descodificar" is less common than "decodificar"; prefer "decodificar" or "No se puede decodificar..." for more natural Spanish.

Correct translation:
No es posible decodificar la PSBT

(Alternative more natural phrasing:
No se puede decodificar la PSBT)
```

<!-- cache_translation_check_es_b5ee97719a396022216533001f7e1f53a4e9ffd79a2b9d93acd33f20e3e8abee -->
```
        <source>PSBT copied</source>
        <translation> PSBT copiada </translation>
    
ERR
The translation has stray leading and trailing spaces. Also consider that "PSBT" refers to a (feminine) transaction in Spanish, so "PSBT copiada" is acceptable — keep it without extra spaces.

Correct translation:
<translation>PSBT copiada</translation>
```

<!-- cache_translation_check_es_a3e15db6cab6f5b9018029100f7e4cccf698348345a0d56a7e6648edf08ae83a -->
```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation> PSBT con incremento de comisión copiada en el portapapeles</translation>
    
ERR
There is a leading stray space at the start of the translation. Also the wording is acceptable but can be slightly improved. No format specifiers are involved.

Corrected translation (remove leading space):
PSBT con incremento de comisión copiada en el portapapeles

Alternative more idiomatic option:
PSBT con aumento de tarifa copiada al portapapeles
```

<!-- cache_translation_check_es_be9bba07dad94efa58a6fa0889dc368689073ce7ed32a4a91feb914a7463e74c -->
```
        <source>Prune configured below the minimum of %d MiB.  Please use a higher number.</source>
        <translation>La poda se ha configurado por debajo del mínimo de %d MiB. Por favor utiliza un valor mas alto.</translation>
    
ERR
Minor issues: the Spanish translation is understandable but missing the accent on "más" and could use a comma after "Por favor". Also consider using the formal imperative "utilice" (optional).

Correct translation:
La poda se ha configurado por debajo del mínimo de %d MiB. Por favor, utilice un valor más alto.
```

<!-- cache_translation_check_es_1d5353c9f6344bc357bbcd5ae63c8dcd35bbcf8ff0e0ba0c6c32d51e9e8ff2db -->
```
        <source>Prune mode is incompatible with -reindex-chainstate. Use full -reindex instead.</source>
        <translation>El modo poda no es compatible con -reindex-chainstate. Haz uso de un -reindex completo en su lugar.</translation>
    
ERR
Minor grammatical/idiomatic issues: missing "de" in "modo de poda" and "Haz uso de un -reindex completo" is awkward in Spanish.

Correct translation:
El modo de poda no es compatible con -reindex-chainstate. Usa -reindex completo en su lugar.
```

<!-- cache_translation_check_es_39b35a3d989d675d83b3d674a6c1304bafaab2ae68fd666391613ef95ed7aa33 -->
```
        <source>SQLiteDatabase: Unknown sqlite wallet schema version %d. Only version %d is supported</source>
        <translation>SQLiteDatabase: versión del esquema de la monedero sqlite desconocido %d. Sólo version %d se admite</translation>
    
ERR
Several Spanish mistakes: wrong gender ("la monedero" → "el monedero"), bad word order, missing accent on "versión" in the second occurrence, and awkward phrasing. Format specifiers (%d) are preserved but the sentence should read naturally.

Correct translation:
SQLiteDatabase: versión desconocida del esquema de monedero sqlite %d. Solo se admite la versión %d.
```

<!-- cache_translation_check_es_4667b30d1bb84139ef87bb8a086ed6b17e6d4489bcbbeafaeec0ff477b2657ab -->
```
        <source>The block database contains a block which appears to be from the future. This may be due to your computer's date and time being set incorrectly. Only rebuild the block database if you are sure that your computer's date and time are correct</source>
        <translation>La base de datos de bloques contiene un bloque que parece ser del futuro. Esto puede ser porque la fecha y hora de su equipo están mal ajustados. Reconstruya la base de datos de bloques solo si está seguro de que la fecha y hora de su equipo están ajustadas correctamente.</translation>
    
ERR
The Spanish translation has an agreement error: "la fecha y hora de su equipo están mal ajustados" uses the masculine plural "ajustados" but should be feminine plural "ajustadas" to agree with "fecha y hora". Also a slightly more natural phrasing is to use "puede deberse a que". 

Correct translation:
La base de datos de bloques contiene un bloque que parece ser del futuro. Esto puede deberse a que la fecha y la hora de su equipo están mal ajustadas. Reconstruya la base de datos de bloques solo si está seguro de que la fecha y la hora de su equipo están ajustadas correctamente.
```

<!-- cache_translation_check_es_4d3a08cc9651dca497ae9cf351691868f406218db587c48f19619d429e0a9f2b -->
```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>El nivel de registro específico de la categoría no es compatible: %1$s=%2$s. Se esperaba %1$s=&lt;category&gt;:&lt;loglevel&gt;. Categorías válidas: %3$s. Niveles de registro válidos: %4 $s.</translation>
    
ERR
There is a formatting error in the last format specifier: "%4 $s" should be "%4$s" (no space between 4 and $s), matching the source string.

Correct translation:
El nivel de registro específico de la categoría no es compatible: %1$s=%2$s. Se esperaba %1$s=&lt;category&gt;:&lt;loglevel&gt;. Categorías válidas: %3$s. Niveles de registro válidos: %4$s.
```

<!-- cache_translation_check_es_e89d36bfab0c28576b177261f8b3efa91d5fb7bdc5c8029f77c942bfa577c241 -->
```
        <source>Incompatible options: -dnsseed=1 was explicitly specified, but -onlynet forbids connections to IPv4/IPv6</source>
        <translation>Opciones incompatibles: -dnsseed=1 se especificó explicitamente, pero  -onlynet impide conexiones a IPv4/IPv6</translation>
    
ERR
Issues:
- Typo: "explicitamente" should be "explícitamente" (accent).
- Extra whitespace: two spaces before "-onlynet".

Correct translation:
Opciones incompatibles: -dnsseed=1 se especificó explícitamente, pero -onlynet impide conexiones a IPv4/IPv6
```

<!-- cache_translation_check_es_ea65af1e81b181d019f46e49258f7ae156b9c675ce9c9bfbb646cbd4f2dc1ad7 -->
```
        <source>Option '-checkpoints' is set but checkpoints were removed. This option has no effect.</source>
        <translation>La opción '-checkpoints' está activa pero los puntos de guardado han sido eliminados. Esta opción no tiene efecto.</translation>
    
ERR
The Spanish uses "puntos de guardado", which is unnatural in this Bitcoin context — "checkpoints" is better translated as "puntos de control" (or simply "checkpoints"). Otherwise the sentence is fine. No format-specifier or spacing issues.

Correct translation:
La opción '-checkpoints' está activada, pero los puntos de control fueron eliminados. Esta opción no tiene efecto.
```

<!-- cache_translation_check_es_3a0a4632c58bb380cd1e26e18b3ee392362d733919077f03a152248c26714bd5 -->
```
        <source>Option '-maxorphantx' is set but no longer has any effect (see release notes). Please remove it from your configuration.</source>
        <translation>La opción '-maxorphantx' está activada pero ya no tiene ningún efecto (mirar notas de lanzamiento) . Por favor, elimínala de su configuración.</translation>
    
ERR
Issues:
- Slight punctuation/spacing error: there's an extra space before the final period after the parenthesis.
- Tone/pronoun inconsistency: "elimínala" (tú form) is mixed with "su configuración" (usted/formal). 
- The parenthetical phrase is more natural as "consulte las notas de la versión" or "ver las notas de la versión".

Correct translation:
La opción '-maxorphantx' está activada pero ya no tiene ningún efecto (consulte las notas de la versión). Por favor, elimínela de su configuración.
```

<!-- cache_translation_check_es_a51036254a10414f8db637480c5cb998167fd84fd24c6c73af85ed8b38d327bb -->
```
        <source>Options '-datacarrier' or '-datacarriersize' are set but are marked as deprecated. They will be removed in a future version.</source>
        <translation>Las opciones '-datacarrier' o '-datacarriersize' están activadas, pero están marcadas como obsoletas. Serán eliminadas en una futura versión. </translation>
    
ERR
The translation is correct in meaning but has a trailing space at the end (whitespace issue). Also "activadas" is acceptable but "establecidas" might be more literal for "set".

Correct translation (no trailing space):
Las opciones '-datacarrier' o '-datacarriersize' están activadas, pero están marcadas como obsoletas. Serán eliminadas en una futura versión.

Or with "establecidas":
Las opciones '-datacarrier' o '-datacarriersize' están establecidas, pero están marcadas como obsoletas. Serán eliminadas en una futura versión.
```

<!-- cache_translation_check_es_9f8f2553608eac70b8765c3ff195853a39de1b806bdc171a764207dc111dfa2b -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>Poda: la última sincronización sobrepasa los datos podados. Tiene que -reindex (descarga toda la cadena de bloques de nuevo en caso de tener un nodo podado).</translation>
    
ERR
The Spanish has minor grammatical issues: "Tiene que -reindex" is incomplete/awkward (should indicate running/using the option) and the parenthetical verb should be infinitive ("descargar"), not "descarga".

Correct translation:
Poda: la última sincronización supera los datos podados. Debe ejecutar -reindex (descargar toda la cadena de bloques de nuevo en caso de tener un nodo podado).
```

<!-- cache_translation_check_es_e5c409c8e92218231301acd2bbceaac71597b563d8fea57b9d9e879b897c942d -->
```
        <source>Rename of '%s' -&gt; '%s' failed. Cannot clean up the background chainstate leveldb directory.</source>
        <translation>Error al cambiar el nombre de ''%s" a ''%s". No se puede limpiar el directorio leveldb del estado de la cadena de fondo.</translation>
    
ERR
There are a few problems with this translation:

1. Quotation marks are inconsistent. The source uses single quotes ('%s'), while the translation uses mixed single and double quotes (''%s").
2. The phrase "background chainstate" is awkwardly translated as "estado de la cadena de fondo." In Bitcoin, "chainstate" is almost always left untranslated or perhaps explained, but not literally translated, as "estado de la cadena" or "estado de la cadena de fondo" loses the technical meaning.
3. The translation for "clean up" should be "limpiar", but "limpiar el directorio" is not idiomatic in technical usage. "Eliminar el directorio" or "no se pudo eliminar/limpiar/directorio 'leveldb' de 'chainstate' en segundo plano" would be better, and specifying it's a directory of "chainstate" (not "estado de la cadena").

Correct translation:
Error al cambiar el nombre de '%s' a '%s'. No se puede limpiar el directorio chainstate leveldb en segundo plano.

If you want to leave leveldb untranslated as a proper noun and not make it awkward:
Error al cambiar el nombre de '%s' a '%s'. No se puede limpiar el directorio leveldb de chainstate en segundo plano.
```

<!-- cache_translation_check_es_3bfb06a630c3e92a8a845ab97ef42a1bb850f3fc716f3a0fe06f06f018b06f19 -->
```
        <source>-paytxfee is deprecated and will be fully removed in v31.0.</source>
        <translation>-paytxfee está obsoleto y será completamente eliminado en v31.0</translation>
    
ERR
The Spanish translation is correct in meaning but is missing the terminal period from the source. Also you may consider "estará obsoleto" vs "está obsoleto", but both are acceptable.

Correct translation:
-paytxfee está obsoleto y será completamente eliminado en v31.0.
```

<!-- cache_translation_check_es_f0a1494c98e42bc6d554ebbf9aeba5623566430782cc64e3fe2ab88e1f41dc1e -->
```
        <source>Can't spend unconfirmed version %d pre-selected input with a version 3 tx</source>
        <translation>No se puede gastar la versión sin confirmar %d entrada preseleccionada con una version 3 tx</translation>
    
ERR
The Spanish is understandable but grammatically incorrect and has minor issues (word order, agreement, missing accent, and awkward "tx"). The format specifier %d is preserved, which is good.

Correct translation:
No se puede gastar la entrada preseleccionada sin confirmar de versión %d con una transacción de versión 3

(Alternatively, keeping "tx": "No se puede gastar la entrada preseleccionada sin confirmar de versión %d con una tx de versión 3")
```

<!-- cache_translation_check_es_ec692afd5b0374786f32b998e12f53d9e965ebd266c9536a86fc50ec6db3c0e5 -->
```
        <source>Can't spend unconfirmed version 3 pre-selected input with a version %d tx</source>
        <translation>No se puede gastar una entrada preseleccionada de la versión 3 sin confirmar con una version %d tx</translation>
    
ERR
Problems:
- Awkward word order and grammar in Spanish; "sin confirmar" placed after "versión 3" is confusing. Use "no confirmada" or place the phrase adjacent to "entrada".
- Inconsistent spelling: second "version" is missing the accent (should be "versión").
- "tx" left untranslated; better to use "transacción" or at least "tx" consistently. The format specifier %d is preserved, which is correct.

Correct translation (two acceptable variants):
- No se puede gastar una entrada preseleccionada de la versión 3 no confirmada con una transacción de versión %d.
- No se puede gastar una entrada preseleccionada de versión 3 no confirmada con una tx de versión %d.
```

<!-- cache_translation_check_es_4e7ac219874be0b8d0cdddbacb4bd8582afd0b256037230590121036c91b4918 -->
```
        <source>Cannot add WalletDescriptor to a non-descriptor wallet</source>
        <translation>No se puede añadir un monedero basado en descriptores a un monedero no basado en descriptores</translation>
    
ERR
The translation alters the term "WalletDescriptor" into a descriptive phrase ("monedero basado en descriptores") rather than preserving the specific identifier/class name; this can be confusing in technical context. No format specifiers or spacing issues.

Suggested correction (preserve the term WalletDescriptor):
No se puede añadir WalletDescriptor a un monedero que no esté basado en descriptores.
```

<!-- cache_translation_check_es_13056e418672e11d288d1aa9e4032c566cc97423c914378af78ac03cc3274c8a -->
```
        <source>Could not generate scriptPubKeys (cache is empty)</source>
        <translation>No se ha podido generar scriptPubKeys ( la cache esta vacía)</translation>
    
ERR
Issues:
- Extra space after '(' and lack of space before ')' — parentheses spacing should be "(la caché está vacía)".
- Missing accents: "cache" → "caché", "esta" → "está".
- Verb number: "scriptPubKeys" is plural, so Spanish should use plural agreement ("No se han podido generar...").

Correct translation:
No se han podido generar scriptPubKeys (la caché está vacía)
```

<!-- cache_translation_check_es_52b3398a9d0f081c845422cf67d694a907b206a1a9597855aa89f320cffd6289 -->
```
        <source>Error: Disk space is low for %s</source>
        <translation>Error: El espacio en disco es pequeño para %s</translation>
    
ERR
The phrase "el espacio en disco es pequeño" is not the most accurate or natural translation. The typical expression in Spanish for insufficient disk space is "bajo" or "insuficiente" rather than "pequeño". 

Correct translation:
Error: El espacio en disco es bajo para %s
```

<!-- cache_translation_check_es_2a0a5fd1f8b11d75ac06f91157e3bdedd7af54854708e343c70a656d2c33da5d -->
```
        <source>Failed to acquire rescan reserver during wallet initialization</source>
        <translation>No se pudo adquirir la reserva de reescaneo durante la inicialización del monedero </translation>
    
ERR
The Spanish is correct in meaning but has a trailing space at the end and could use a more common term for "wallet" if desired. Remove the extra whitespace.

Correct translation:
No se pudo adquirir la reserva de reescaneo durante la inicialización del monedero

(Alternative using "billetera": "No se pudo adquirir la reserva de reescaneo durante la inicialización de la billetera")
```

<!-- cache_translation_check_es_2dbda533769179882c588baf0829a158b5d244f5e8eb8ede3859373885dde904 -->
```
        <source>Failed to close block undo file.</source>
        <translation>No se ha podido cerrar el archivo undo</translation>
    
ERR
Minor issues: missing terminal period and literal English word "undo" left untranslated. A clearer Spanish translation that keeps meaning in Bitcoin context:

Correct translation:
No se ha podido cerrar el archivo de deshacer de bloques.
```

<!-- cache_translation_check_es_86d207e3d60fdf6ef2c0398ce24697c71b8af97c90236a73e7558362adb2d679 -->
```
        <source>Failed to close file when writing block.</source>
        <translation>No se ha podido cerrar el archivo mientras se escribía un bloque</translation>
    
ERR
The Spanish translation is accurate in meaning and has no format-specifier issues, but it is missing the final period present in the source sentence. Also a slightly more natural phrasing would use "al escribir" or keep as-is.

Correct translation (retain original wording, add punctuation):
No se ha podido cerrar el archivo mientras se escribía un bloque.

Alternative more natural phrasing:
No se pudo cerrar el archivo al escribir un bloque.
```

<!-- cache_translation_check_es_85a3cc169f47552c330ad3730b70bef84eb5831797c93aa03e25b378336b9f7c -->
```
        <source>Ignoring duplicate -wallet %s.</source>
        <translation>Ignorar duplicación de -wallet %s.</translation>
    
ERR
The translation is understandable but not natural or fully accurate in Spanish. The English source uses "Ignoring" as a present participle, fitting the log/notification context, while "Ignorar" is imperative or infinitive. Also, "duplicación de" is awkward in this context; "copia duplicada de" or simply "duplicado" fits better.

Correct translation:
Ignorando -wallet %s duplicado.
```

<!-- cache_translation_check_es_302442317cd6bc8ad107baa71adf575abdba5bf3f607de199e75669781dc0d95 -->
```
        <source>The %s path uses exFAT, which is known to have intermittent corruption problems on macOS. Move this directory to a different filesystem to avoid data loss.</source>
        <translation>El %s ruta de acceso usa exFAT, el cual es conocido por tener problemas de corrupción intermitente en macOS. Mueve este directorio a un sistema de ficheros distinto para prevenir perdida de datos.</translation>
    
ERR
The Spanish has grammatical and punctuation issues: "El %s ruta de acceso" is incorrect word order and gender ("ruta" is feminine), and "perdida" needs an accent. Also prefer "sistema de archivos" or "sistema de ficheros". The %s specifier should appear in the same logical position as in the source.

Correct translation:
La ruta %s usa exFAT, que se sabe que presenta problemas de corrupción intermitente en macOS. Mueva este directorio a un sistema de archivos distinto para evitar la pérdida de datos.
```

<!-- cache_translation_check_es_9295bd68c3610e1e1f7b0ee9d89c9f17313d4d5d770299e4f3740937d6fb13e7 -->
```
        <source>Unsupported logging category %s=%s.</source>
        <translation>La categoría de registro no es compatible %s=%s. </translation>
    
ERR
There is a minor issue with an extra space at the end of the translated sentence. Otherwise, the translation is accurate and correctly maintains the format specifiers.

Correct translation:
La categoría de registro no es compatible %s=%s.
```

<!-- cache_translation_check_es_d4667da96ed8c41a065a4fc2f7775b250e975441f03100e39bf61ba943d129c6 -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>Error cargando %s: El monedero es un monedero tipo legacy. Por favor migra a un monedero basado en descriptores usando la herramienta de migrado  (migratewallet RPC).</translation>
    
ERR
Problems:
- Awkward wording: "monedero tipo legacy" is unnatural; prefer "monedero heredado" (or "legacy" in quotes) and "migra" should be "migre" (formal imperative) or "migren" depending on register. 
- "herramienta de migrado" is incorrect; should be "herramienta de migración" or "herramienta de migrar".
- Extra double space before "(migratewallet RPC)".
- Consider moving "RPC" before/after for natural Spanish ordering: "RPC migratewallet" or "migratewallet RPC" both acceptable, but keep original meaning.

Correct translation:
Error al cargar %s: el monedero es un monedero heredado. Por favor, migre a un monedero basado en descriptores usando la herramienta de migración (RPC migratewallet).
```

<!-- cache_translation_check_es_0ae6d42d4a0c017b1040f3c6fc625600c3a2e33d538fccd4fcdeb2a9f8c78eeb -->
```
        <source>Invalid -proxy address or hostname, ends with '=': '%s'</source>
        <translation>La dirección -proxy o el nombre de host no es válido, acaba con  '=':'%s'</translation>
    
ERR
Agreement and spacing issues in the Spanish translation. The subject is compound ("La dirección -proxy o el nombre de host") so the predicate should be plural ("no son válidos"), and there are extra/misplaced spaces around '=' and ':'.

Correct translation:
La dirección -proxy o el nombre de host no son válidos, termina con '=': '%s'
```

<!-- cache_translation_check_es_0f074611ebeb9b1caca1f989b9c0e3daf5e1ee4aefa7637a38d037ae543ff530 -->
```
        <source>Unrecognized network in -proxy='%s': '%s'</source>
        <translation>Red no reconocida en -proxy:'%s':'%s'</translation>
    
ERR
The translation alters the original punctuation/format and misses the '=' after -proxy, and also removes the space after the colon. Format specifiers are present but the surrounding punctuation differs from the source, which can confuse logs/parsing.

Correct translation:
Red no reconocida en -proxy='%s': '%s'
```
</details>

Number of issues: 57.
