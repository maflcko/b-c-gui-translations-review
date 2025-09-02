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
"Transmisión completa" is misleading; "relay" implies forwarding/retransmission. Correct translation:
Retransmisión completa
```

<!-- cache_translation_check_es_57f354034cf4969b75bd003cf0a88a42d1efac07406d58f43e6fe4c7832c6c12 -->
```
        <source>Address Fetch</source>
        <extracomment>Short-lived peer connection type that solicits known addresses from a peer.</extracomment>
        <translation>Búsqueda de dirección</translation>
    
ERR
"Fetch" se traduce mejor como "obtención" o "recuperación", no "búsqueda" (search). Además, debería ser plural para ajustarse al contexto de múltiples direcciones.

Correct translation:
Obtención de direcciones
```

<!-- cache_translation_check_es_8cf49beec188e30c4374a5941e5160afa4872226daf5f9870b380d5c48521ad3 -->
```
        <source>&amp;Hide</source>
        <translation>&amp;Ocultar </translation>
    
ERR
The translation has a trailing space, which is a whitespace formatting issue.

Correct translation:
&Ocultar
```

<!-- cache_translation_check_es_f1cfa244210da6deff9fb1ec85f708b11e67abda6ed2e39002662ed752a53e0b -->
```
        <source>(un)select all</source>
        <translation>(des)selecionar todo</translation>
    
ERR
Hay un error ortográfico: "selecionar" debe ser "seleccionar".

Correct translation:
(dés)seleccionar todo
```

<!-- cache_translation_check_es_88fffc940b0c0f7157365b0ed9c7b087e84758cd38b8a526518641c325fc116b -->
```
        <source>Received with label</source>
        <translation>Recibido con dirección</translation>
    
ERR
The translation incorrectly uses "dirección" (address) instead of "etiqueta" (label).

Correct translation:
Recibido con etiqueta
```

<!-- cache_translation_check_es_7c1ff35a25773b5ed18926af41af668176a06cf4c47f8fe970fb0f5b4fbf9981 -->
```
        <source>Received with address</source>
        <translation>Recibido con etiqueta</translation>
    
ERR
The translation incorrectly uses "etiqueta" (label) instead of "dirección" (address).

Correct translation:
Recibido con dirección
```

<!-- cache_translation_check_es_ddbe5c772d9d256205e96515a5ff2874a950599631c28d99e3325b6744e0bafa -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>Copiar &amp;ID de transacción e índice de salidas</translation>
    
ERR
"índice de salidas" is plural, but the source has singular "output index". The shortcut marker & appears exactly once, which is correct.

Correct translation:
Copiar &ID de transacción e índice de salida
```

<!-- cache_translation_check_es_ea082291d36bbc76e7ad26daec9af96516739f34f9c2f01a131e08e91f8a880f -->
```
        <source>L&amp;ock unspent</source>
        <translation>B&amp;loquear no gastado</translation>
    
ERR
Number agreement issue: "no gastado" is singular and mismatches the implied plural UTXOs. Use plural feminine to match "salidas" (UTXOs).

Correct translation:
B&loquear no gastadas
```

<!-- cache_translation_check_es_8fa790086b6f8516a240f7b886fb5b22ba97b8c5f1583aeca1280567ebbf101c -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Activar controles de &amp;PSBT </translation>
    
ERR
There is an unwanted trailing space at the end of the translation.

Correct translation:
Activar controles de &PSBT
```

<!-- cache_translation_check_es_db6f1904a3025b65e3412569b63bebe156b0636a27c99130d917395409977a76 -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Usar proxy SOCKS&amp;5 para conectar a pares a través de los servicios anónimos de Tor:</translation>
    
ERR
Missing the notion of "separate" and slightly awkward preposition ("a pares"). Also better to reflect "onion services" as "servicios onion".

Correct translation:
Usar un proxy SOCKS&5 independiente para conectar con pares a través de los servicios onion de Tor:
```

<!-- cache_translation_check_es_a6e7cf9e9ad40319d32ef46133bca630e794c92fc146d5638095b1f84bdd2aab -->
```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>Modo de privacidad activado para la pestaña de visión general. Para desenmascarar los valores, desmarcar los valores de Configuración-&gt;Enmascarar valores.</translation>
    
ERR
La frase en español es redundante y poco natural: “desmarcar los valores de Configuración->Enmascarar valores” es incorrecto. Debe referirse a desmarcar la opción del menú, no “los valores”.

Correct translation:
Modo de privacidad activado para la pestaña Resumen. Para desenmascarar los valores, desmarque Configuración->Enmascarar valores.
```

<!-- cache_translation_check_es_310a5e0c2c0d69a9f4a34a689de7286e1863ebfcf9c367de1c385382d6e25ef8 -->
```
        <source>Transaction broadcast successfully! Transaction ID: %1</source>
        <translation>¡La transacción se ha difundido correctamente! Código ID de la transacción: %1</translation>
    
ERR
"​​​​Código ID de la transacción" is redundant/unnatural in Spanish. Use "ID de la transacción" or "Identificador de la transacción". The placeholder %1 is correctly preserved.

Correct translation:
¡La transacción se ha difundido correctamente! ID de la transacción: %1
```

<!-- cache_translation_check_es_99548199606555f1cd47756387413f1f35354270e5d4c6a047414ab6a1611e7c -->
```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>Transacción parcialmente firmada (binario) </translation>
    
ERR
Trailing whitespace after the closing parenthesis. Also, agreement should be feminine to match "transacción".

Correct translation:
Transacción parcialmente firmada (binaria)
```

<!-- cache_translation_check_es_a3e6b2ba4d665e42b16768a3e1e2e1a521bfe16cd09391153d5a4d93fef6c8bd -->
```
        <source>Pays transaction fee: </source>
        <translation>Pagar comisión por transacción:</translation>
    
ERR
The verb form should be conjugated ("Paga") rather than infinitive ("Pagar"), and the trailing space after the colon is missing compared to the source.

Correct translation:
Paga la comisión de la transacción:
```

<!-- cache_translation_check_es_5db0de04de0381922b65c188b8bcf71452e69bc18124581684d602d6b793bcf4 -->
```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>No se puede iniciar bitcoin: controlador pulsar-para-pagar</translation>
    
ERR
Falta la preposición "de" y "pulsar-para-pagar" suena antinatural. "clic para pagar" es más natural en español.

Correct translation:
No se puede iniciar bitcoin: controlador de clic para pagar
```

<!-- cache_translation_check_es_1de2c3ffc36919967dacc16e221885d94940c5ddcb22f989d5a6216e6adab131 -->
```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>«bitcoin: //» no es un URI válido. Use «bitcoin:» en su lugar.</translation>
    
ERR
The scheme text has an incorrect space: «bitcoin: //» should be «bitcoin://». Quotation style should preserve the exact literal string.

Correct translation:
'bitcoin://' no es un URI válido. Use 'bitcoin:' en su lugar.
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
The phrase "no se mantiene BIP70" mistranslates "is not supported" (it means "not maintained"). It should be "no se admite" or "no es compatible".

Correct translation:
No se puede procesar la solicitud de pago porque no se admite BIP70.
Debido a los fallos de seguridad generalizados en BIP70, se recomienda encarecidamente ignorar las instrucciones del comerciante para cambiar de monedero.
Si recibe este error, debe solicitar al comerciante que le proporcione un URI compatible con BIP21.
```

<!-- cache_translation_check_es_9bdb6308426f568abc9cd839ac22d6ab48d3ba9be551b757991044736f86008d -->
```
        <source>Peer</source>
        <extracomment>Title of Peers Table column which contains a unique number used to identify a connection.</extracomment>
        <translation>Pareja</translation>
    
ERR
"Pareja" significa "couple/pareja" y no corresponde al contexto de redes P2P. En este contexto, "Peer" debe traducirse como "Par".

Correct translation:
Par
```

<!-- cache_translation_check_es_135481bf4c802ccbb841971c2a927af2279499b715ce4026cb48005948f65ab2 -->
```
        <source>Please, review your transaction. You can create and send this transaction or create a Partially Signed Bitcoin Transaction (PSBT), which you can save or copy and then sign with, e.g., an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can send their transaction or create a PSBT. This string is displayed when both private keys and PSBT controls are enabled.</extracomment>
        <translation>Revisa la transacción. Puedes crear y enviar esta transacción de Bitcoin parcialmente firmada (PSBT), que además puedes guardar o copiar y, luego, firmar; por ejemplo, con un monedero %1 sin conexión o un monedero de hardware compatible con PSBT.</translation>
    
ERR
The translation changes the meaning by implying that the transaction to be sent is a PSBT, whereas the source says you can either send the transaction or create a PSBT. Also, the punctuation around "y, luego," is awkward.

Correct translation:
Por favor, revisa tu transacción. Puedes crear y enviar esta transacción o crear una Transacción de Bitcoin Parcialmente Firmada (PSBT), que puedes guardar o copiar y luego firmar, por ejemplo, con un monedero %1 sin conexión o un monedero de hardware compatible con PSBT.
```

<!-- cache_translation_check_es_6a4a483fbbfdaa27a769412be502750c5615d14e5dc39f7abb6660cbde14d783 -->
```
        <source>The PSBT has been copied to the clipboard. You can also save it.</source>
        <translation>Se copió la  PSBT al portapapeles. También puedes guardarla.</translation>
    
ERR
Hay un espacio doble antes de "PSBT". Además, se recomienda el uso de perfecto compuesto y un registro consistente.

Corrección:
Se ha copiado la PSBT al portapapeles. También puede guardarla.
```

<!-- cache_translation_check_es_592f95278f23aaa28ea8f3f4f6b964e5dae84876c08ce33f8e4151671d460217 -->
```
        <source>PSBT saved to disk</source>
        <translation> PSBT guardada en disco</translation>
    
ERR
Leading whitespace before 'PSBT'. Remove it.

Correct translation:
PSBT guardada en disco
```

<!-- cache_translation_check_es_9105fef6298b2c5d564f5fd9bd7990fa62e5b69a0cbea7f57c1010044a19ce21 -->
```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Inmadura (%1 confirmaciones; estará disponibles después de %2)</translation>
    
ERR
Concordancia gramatical incorrecta: “estará disponibles” debe ser singular “estará disponible”. También es preferible “Inmaduro” en este contexto. Se recomienda mantener la coma del original.

Correct translation:
Inmaduro (%1 confirmaciones, estará disponible después de %2)
```

<!-- cache_translation_check_es_38c960faaaa5725e724613728b6f265ecba28cfd0eea5acf7ec11750e54bd26b -->
```
        <source>Unable to decode PSBT from clipboard (invalid base64)</source>
        <translation>No se puede decodificar la  PSBT desde el portapapeles (Base64 inválida)</translation>
    
ERR
There is an extra space before "PSBT". Also, "base64" should be lowercase for consistency.

Correct translation:
No se puede decodificar la PSBT del portapapeles (base64 inválida)
```

<!-- cache_translation_check_es_6e1f787c2bcac75e3ac2a4c3d14086500b6673e7484c49ac3fcadde8b631fbe0 -->
```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>El archivo de la  PSBT debe ser inferior a 100 MiB</translation>
    
ERR
Hay un doble espacio ("la  PSBT") y la construcción "archivo de la PSBT" es inadecuada; debería ser "archivo PSBT".

Correct translation:
El archivo PSBT debe ser menor que 100 MiB
```

<!-- cache_translation_check_es_31ba839a8cb4530c2edae42c5eb06114bd2832b0948b7b63ca18a545f4c6f078 -->
```
        <source>Unable to decode PSBT</source>
        <translation>No es posible descodificar la  PSBT</translation>
    
ERR
There is an extra space before "PSBT".

Correct translation:
No es posible descodificar la PSBT
```

<!-- cache_translation_check_es_b5ee97719a396022216533001f7e1f53a4e9ffd79a2b9d93acd33f20e3e8abee -->
```
        <source>PSBT copied</source>
        <translation> PSBT copiada </translation>
    
ERR
The translation has unwanted leading and trailing spaces.

Correct translation:
PSBT copiada
```

<!-- cache_translation_check_es_a3e15db6cab6f5b9018029100f7e4cccf698348345a0d56a7e6648edf08ae83a -->
```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation> PSBT con incremento de comisión copiada en el portapapeles</translation>
    
ERR
Leading extra space before "PSBT". Also "al portapapeles" is more idiomatic than "en el portapapeles".

Correct translation:
PSBT con aumento de comisión copiada al portapapeles
```

<!-- cache_translation_check_es_be9bba07dad94efa58a6fa0889dc368689073ce7ed32a4a91feb914a7463e74c -->
```
        <source>Prune configured below the minimum of %d MiB.  Please use a higher number.</source>
        <translation>La poda se ha configurado por debajo del mínimo de %d MiB. Por favor utiliza un valor mas alto.</translation>
    
ERR
Orthography: "mas" should be "más" with an accent. Wording: "número" fits better than "valor" for "number". Optional comma after "Por favor".

Correct translation:
La poda está configurada por debajo del mínimo de %d MiB. Por favor, utiliza un número mayor.
```

<!-- cache_translation_check_es_1d5353c9f6344bc357bbcd5ae63c8dcd35bbcf8ff0e0ba0c6c32d51e9e8ff2db -->
```
        <source>Prune mode is incompatible with -reindex-chainstate. Use full -reindex instead.</source>
        <translation>El modo poda no es compatible con -reindex-chainstate. Haz uso de un -reindex completo en su lugar.</translation>
    
ERR
Falta la preposición "de" en "modo de poda" y el estilo imperativo es mejor como "Usa". Además, no es necesario "un" antes de -reindex.

Correct translation:
El modo de poda no es compatible con -reindex-chainstate. Usa -reindex completo en su lugar.
```

<!-- cache_translation_check_es_39b35a3d989d675d83b3d674a6c1304bafaab2ae68fd666391613ef95ed7aa33 -->
```
        <source>SQLiteDatabase: Unknown sqlite wallet schema version %d. Only version %d is supported</source>
        <translation>SQLiteDatabase: versión del esquema de la monedero sqlite desconocido %d. Sólo version %d se admite</translation>
    
ERR
Grammatical errors and capitalization issues: incorrect gender agreement ("la monedero"), adjective agreement ("desconocido" should be feminine), missing accent in "versión", and "SQLite" should be capitalized. Style improved for clarity.

Correct translation:
SQLiteDatabase: Versión del esquema del monedero SQLite desconocida %d. Solo se admite la versión %d
```

<!-- cache_translation_check_es_4667b30d1bb84139ef87bb8a086ed6b17e6d4489bcbbeafaeec0ff477b2657ab -->
```
        <source>The block database contains a block which appears to be from the future. This may be due to your computer's date and time being set incorrectly. Only rebuild the block database if you are sure that your computer's date and time are correct</source>
        <translation>La base de datos de bloques contiene un bloque que parece ser del futuro. Esto puede ser porque la fecha y hora de su equipo están mal ajustados. Reconstruya la base de datos de bloques solo si está seguro de que la fecha y hora de su equipo están ajustadas correctamente.</translation>
    
ERR
Concordancia de género/número incorrecta: debe ser "mal ajustadas" (femenino plural) para "fecha y hora". También se puede mejorar "Esto puede deberse a que".

Correct translation:
La base de datos de bloques contiene un bloque que parece ser del futuro. Esto puede deberse a que la fecha y la hora de su equipo están mal ajustadas. Reconstruya la base de datos de bloques solo si está seguro de que la fecha y la hora de su equipo están ajustadas correctamente.
```

<!-- cache_translation_check_es_4d3a08cc9651dca497ae9cf351691868f406218db587c48f19619d429e0a9f2b -->
```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>El nivel de registro específico de la categoría no es compatible: %1$s=%2$s. Se esperaba %1$s=&lt;category&gt;:&lt;loglevel&gt;. Categorías válidas: %3$s. Niveles de registro válidos: %4 $s.</translation>
    
ERR
The format specifier %4$s is broken in the translation (%4 $s has an extra space), which will cause formatting errors.

Correct translation:
El nivel de registro específico de la categoría no es compatible: %1$s=%2$s. Se esperaba %1$s=&lt;category&gt;:&lt;loglevel&gt;. Categorías válidas: %3$s. Niveles de registro válidos: %4$s.
```

<!-- cache_translation_check_es_e89d36bfab0c28576b177261f8b3efa91d5fb7bdc5c8029f77c942bfa577c241 -->
```
        <source>Incompatible options: -dnsseed=1 was explicitly specified, but -onlynet forbids connections to IPv4/IPv6</source>
        <translation>Opciones incompatibles: -dnsseed=1 se especificó explicitamente, pero  -onlynet impide conexiones a IPv4/IPv6</translation>
    
ERR
Missing accent in "explícitamente" and an extra space before -onlynet.

Correct translation:
Opciones incompatibles: -dnsseed=1 se especificó explícitamente, pero -onlynet prohíbe conexiones a IPv4/IPv6
```

<!-- cache_translation_check_es_ea65af1e81b181d019f46e49258f7ae156b9c675ce9c9bfbb646cbd4f2dc1ad7 -->
```
        <source>Option '-checkpoints' is set but checkpoints were removed. This option has no effect.</source>
        <translation>La opción '-checkpoints' está activa pero los puntos de guardado han sido eliminados. Esta opción no tiene efecto.</translation>
    
ERR
Terminology issue: "checkpoints" in Bitcoin should be "puntos de control", not "puntos de guardado". "is set" is better as "está configurada/establecida".

Correct translation:
La opción '-checkpoints' está configurada, pero se eliminaron los puntos de control. Esta opción no tiene efecto.
```

<!-- cache_translation_check_es_3a0a4632c58bb380cd1e26e18b3ee392362d733919077f03a152248c26714bd5 -->
```
        <source>Option '-maxorphantx' is set but no longer has any effect (see release notes). Please remove it from your configuration.</source>
        <translation>La opción '-maxorphantx' está activada pero ya no tiene ningún efecto (mirar notas de lanzamiento) . Por favor, elimínala de su configuración.</translation>
    
ERR
- Inconsistent formality: "elimínala" (tú) with "su configuración" (usted).
- Unnatural phrasing for the parenthetical and missing article.
- Extraneous space before the period.

Correct translation:
La opción '-maxorphantx' está activada pero ya no tiene ningún efecto (consulte las notas de la versión). Por favor, elimínela de su configuración.
```

<!-- cache_translation_check_es_a51036254a10414f8db637480c5cb998167fd84fd24c6c73af85ed8b38d327bb -->
```
        <source>Options '-datacarrier' or '-datacarriersize' are set but are marked as deprecated. They will be removed in a future version.</source>
        <translation>Las opciones '-datacarrier' o '-datacarriersize' están activadas, pero están marcadas como obsoletas. Serán eliminadas en una futura versión. </translation>
    
ERR
There is a trailing space at the end of the translation. Also, "set" is better rendered as "configuradas" in this context.

Correct translation:
Las opciones '-datacarrier' o '-datacarriersize' están configuradas, pero están marcadas como obsoletas. Serán eliminadas en una futura versión.
```

<!-- cache_translation_check_es_9f8f2553608eac70b8765c3ff195853a39de1b806bdc171a764207dc111dfa2b -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>Poda: la última sincronización sobrepasa los datos podados. Tiene que -reindex (descarga toda la cadena de bloques de nuevo en caso de tener un nodo podado).</translation>
    
ERR
Missing "wallet" in the first sentence and unnatural phrasing around "-reindex" and the parenthetical. Also, "descarga" should be "descargar" or a clearer construction.

Correct translation:
Poda: la última sincronización del monedero sobrepasa los datos podados. Debe ejecutar -reindex (volverá a descargar toda la cadena de bloques si el nodo está podado).
```

<!-- cache_translation_check_es_e5c409c8e92218231301acd2bbceaac71597b563d8fea57b9d9e879b897c942d -->
```
        <source>Rename of '%s' -&gt; '%s' failed. Cannot clean up the background chainstate leveldb directory.</source>
        <translation>Error al cambiar el nombre de ''%s" a ''%s". No se puede limpiar el directorio leveldb del estado de la cadena de fondo.</translation>
    
ERR
Comillas mal formateadas y terminología técnica inadecuada ("estado de la cadena de fondo"). También se debe respetar "LevelDB" y "chainstate".

Correct translation:
Error al cambiar el nombre de '%s' a '%s'. No se puede limpiar el directorio LevelDB de chainstate en segundo plano.
```

<!-- cache_translation_check_es_3bfb06a630c3e92a8a845ab97ef42a1bb850f3fc716f3a0fe06f06f018b06f19 -->
```
        <source>-paytxfee is deprecated and will be fully removed in v31.0.</source>
        <translation>-paytxfee está obsoleto y será completamente eliminado en v31.0</translation>
    
ERR
Missing ending period.

Correct translation:
-paytxfee está obsoleto y será completamente eliminado en v31.0.
```

<!-- cache_translation_check_es_f0a1494c98e42bc6d554ebbf9aeba5623566430782cc64e3fe2ab88e1f41dc1e -->
```
        <source>Can't spend unconfirmed version %d pre-selected input with a version 3 tx</source>
        <translation>No se puede gastar la versión sin confirmar %d entrada preseleccionada con una version 3 tx</translation>
    
ERR
La estructura es confusa y hay errores de acentuación. Además, el orden de los elementos debe aclararse y "tx" debe ir como "tx de versión 3".

Correct translation:
No se puede gastar una entrada preseleccionada sin confirmar de versión %d con una tx de versión 3
```

<!-- cache_translation_check_es_ec692afd5b0374786f32b998e12f53d9e965ebd266c9536a86fc50ec6db3c0e5 -->
```
        <source>Can't spend unconfirmed version 3 pre-selected input with a version %d tx</source>
        <translation>No se puede gastar una entrada preseleccionada de la versión 3 sin confirmar con una version %d tx</translation>
    
ERR
Missing accent in "versión" and awkward phrasing of "version %d tx". Prefer "transacción de versión %d" for clarity.

Correct translation:
No se puede gastar una entrada preseleccionada sin confirmar de versión 3 con una transacción de versión %d
```

<!-- cache_translation_check_es_4e7ac219874be0b8d0cdddbacb4bd8582afd0b256037230590121036c91b4918 -->
```
        <source>Cannot add WalletDescriptor to a non-descriptor wallet</source>
        <translation>No se puede añadir un monedero basado en descriptores a un monedero no basado en descriptores</translation>
    
ERR
"WalletDescriptor" se tradujo como si fuera un monedero, cambiando el significado. Debe dejarse como identificador o traducirse como "descriptor de monedero".

Correct translation:
No se puede añadir un WalletDescriptor a un monedero no basado en descriptores
```

<!-- cache_translation_check_es_13056e418672e11d288d1aa9e4032c566cc97423c914378af78ac03cc3274c8a -->
```
        <source>Could not generate scriptPubKeys (cache is empty)</source>
        <translation>No se ha podido generar scriptPubKeys ( la cache esta vacía)</translation>
    
ERR
Accents and spacing are incorrect: "cache" should be "caché", "esta" should be "está", and there shouldn't be a space after the opening parenthesis.

Correct translation:
No se ha podido generar scriptPubKeys (la caché está vacía)
```

<!-- cache_translation_check_es_52b3398a9d0f081c845422cf67d694a907b206a1a9597855aa89f320cffd6289 -->
```
        <source>Error: Disk space is low for %s</source>
        <translation>Error: El espacio en disco es pequeño para %s</translation>
    
ERR
The phrase "es pequeño" is unnatural for disk space. Use "insuficiente" or "poco" instead.

Correct translation:
Error: espacio en disco insuficiente para %s
```

<!-- cache_translation_check_es_2a0a5fd1f8b11d75ac06f91157e3bdedd7af54854708e343c70a656d2c33da5d -->
```
        <source>Failed to acquire rescan reserver during wallet initialization</source>
        <translation>No se pudo adquirir la reserva de reescaneo durante la inicialización del monedero </translation>
    
ERR
Trailing whitespace at the end of the translation.

Correct translation:
No se pudo adquirir la reserva de reescaneo durante la inicialización del monedero
```

<!-- cache_translation_check_es_2dbda533769179882c588baf0829a158b5d244f5e8eb8ede3859373885dde904 -->
```
        <source>Failed to close block undo file.</source>
        <translation>No se ha podido cerrar el archivo undo</translation>
    
ERR
La traducción omite "block" y suena incompleta; además, falta el punto final.

Correct translation:
No se pudo cerrar el archivo de reversión de bloque.
```

<!-- cache_translation_check_es_86d207e3d60fdf6ef2c0398ce24697c71b8af97c90236a73e7558362adb2d679 -->
```
        <source>Failed to close file when writing block.</source>
        <translation>No se ha podido cerrar el archivo mientras se escribía un bloque</translation>
    
ERR
Missing final period compared to the source sentence.

Correct translation:
No se ha podido cerrar el archivo mientras se escribía un bloque.
```

<!-- cache_translation_check_es_85a3cc169f47552c330ad3730b70bef84eb5831797c93aa03e25b378336b9f7c -->
```
        <source>Ignoring duplicate -wallet %s.</source>
        <translation>Ignorar duplicación de -wallet %s.</translation>
    
ERR
The Spanish uses an imperative form and an unnatural noun phrase. The original indicates an ongoing action. A more natural translation is:
Ignorando la opción -wallet %s duplicada.
```

<!-- cache_translation_check_es_302442317cd6bc8ad107baa71adf575abdba5bf3f607de199e75669781dc0d95 -->
```
        <source>The %s path uses exFAT, which is known to have intermittent corruption problems on macOS. Move this directory to a different filesystem to avoid data loss.</source>
        <translation>El %s ruta de acceso usa exFAT, el cual es conocido por tener problemas de corrupción intermitente en macOS. Mueve este directorio a un sistema de ficheros distinto para prevenir perdida de datos.</translation>
    
ERR
Errores gramaticales y ortográficos: "El %s ruta de acceso" es incorrecto; falta la concordancia y el artículo. Falta tilde en "pérdida". Se recomienda un estilo imperativo formal consistente.

Correct translation:
La ruta de acceso %s utiliza exFAT, que es conocido por presentar problemas de corrupción intermitente en macOS. Mueva este directorio a un sistema de archivos diferente para evitar la pérdida de datos.
```

<!-- cache_translation_check_es_9295bd68c3610e1e1f7b0ee9d89c9f17313d4d5d770299e4f3740937d6fb13e7 -->
```
        <source>Unsupported logging category %s=%s.</source>
        <translation>La categoría de registro no es compatible %s=%s. </translation>
    
ERR
Trailing whitespace after the period. The phrasing "no es compatible" is awkward here; "no admitida" or "no compatible" should be used without "es" or with proper construction.

Correct translation:
Categoría de registro no admitida %s=%s.
```

<!-- cache_translation_check_es_d4667da96ed8c41a065a4fc2f7775b250e975441f03100e39bf61ba943d129c6 -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>Error cargando %s: El monedero es un monedero tipo legacy. Por favor migra a un monedero basado en descriptores usando la herramienta de migrado  (migratewallet RPC).</translation>
    
ERR
There is an extra double space before the parenthesis, and "herramienta de migrado" is unnatural; "herramienta de migración" is correct. Also "Error cargando" is better as "Error al cargar".

Correct translation:
Error al cargar %s: El monedero es de tipo legacy. Por favor, migra a un monedero basado en descriptores usando la herramienta de migración (migratewallet RPC).
```

<!-- cache_translation_check_es_0ae6d42d4a0c017b1040f3c6fc625600c3a2e33d538fccd4fcdeb2a9f8c78eeb -->
```
        <source>Invalid -proxy address or hostname, ends with '=': '%s'</source>
        <translation>La dirección -proxy o el nombre de host no es válido, acaba con  '=':'%s'</translation>
    
ERR
- Awkward phrasing: "La dirección -proxy" is unnatural; it should indicate the address/hostname for the -proxy option.
- Agreement/grammar could be improved.
- Whitespace issues: double space before '=' and missing space after the colon.

Correct translation:
La dirección o el nombre de host de -proxy no es válido, termina con '=': '%s'
```

<!-- cache_translation_check_es_0f074611ebeb9b1caca1f989b9c0e3daf5e1ee4aefa7637a38d037ae543ff530 -->
```
        <source>Unrecognized network in -proxy='%s': '%s'</source>
        <translation>Red no reconocida en -proxy:'%s':'%s'</translation>
    
ERR
The equals sign after -proxy was omitted, and spaces around the colons were removed. These should match the source format.

Correct translation:
Red no reconocida en -proxy='%s': '%s'
```
</details>

Number of issues: 53.
