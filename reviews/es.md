# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>es</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bes%5D%20request)


<!-- cache_translation_check_es_ddbe5c772d9d256205e96515a5ff2874a950599631c28d99e3325b6744e0bafa -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>Copiar &amp;ID de transacción e índice de salidas</translation>
    
ERR
"índice de salidas" is plural, but the source has singular "output index". The shortcut marker & appears exactly once, which is correct.

Correct translation:
Copiar &ID de transacción e índice de salida
```

<!-- cache_translation_check_es_a9ee2365ae9cbabf03b81cdfd89e1ea7d5c32d9ef176d9ab5382940f99d851e5 -->
```
        <source>Copy after fee</source>
        <translation>Copiar importe después de comisión</translation>
    
ERR
Falta el artículo definido y suena antinatural en español.

Correct translation:
Copiar importe después de la comisión
```

<!-- cache_translation_check_es_711dac816a8dfedb897a39c27e0e3cc202b44813835f90b95325d153509c6f8f -->
```
        <source>(0 = auto, &lt;0 = leave that many cores free)</source>
        <translation>(0 = auto, &lt;0 = dejar esta cantidad de núcleos libres)</translation>
    
ERR
"esta cantidad" is awkward; it should refer to the user-specified negative number. Use "ese número" or "esa cantidad" for clarity.

Correct translation:
(0 = auto, <0 = dejar ese número de núcleos libres)
```

<!-- cache_translation_check_es_3309c9af03f58c8ac46a926970f22dfaeab51f58a1342f6d306ccdc7b42c20d9 -->
```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>Modo de privacidad activado en la pestaña de vista general. Para mostrar los valores, desmarca "Configuración -&gt; Ocultar valores".</translation>
    
ERR
- "Overview" in Bitcoin Core is typically translated as "Resumen", not "vista general".
- Extra quotation marks and spaces around "->" are unnecessary.
- Prefer formal imperative for consistency.

Correct translation:
Modo de privacidad activado en la pestaña Resumen. Para mostrar los valores, desmarque Configuración-&gt;Ocultar valores.
```

<!-- cache_translation_check_es_49c0db7e6155afafb53450080480d0620a4cd16317aeb01d61e6cbea8c9f840c -->
```
        <source>Pays transaction fee: </source>
        <translation>Paga la comisión de transacción:</translation>
    
ERR
Missing trailing space after the colon; the source ends with a space.

Correct translation:
Paga la comisión de transacción:
```

<!-- cache_translation_check_es_6afe39a300db41c4819cbadfd4c4d362ffc55d1add564102ca080a5875399fc3 -->
```
        <source>(But no wallet is loaded.)</source>
        <translation>(Sin embargo, no se cargó ningún monedero).</translation>
    
ERR
The tense is incorrect ("no se cargó" is past) and the period placement does not match the source (it should be inside the parentheses). Also, "Pero" is a more direct equivalent here than "Sin embargo".

Correct translation:
(Pero no se ha cargado ningún monedero.)
```

<!-- cache_translation_check_es_5ebef66a184d5a30757e643bf73ae81783a7052d5b04d669c8e6744079cf4774 -->
```
        <source>Cannot process payment request because BIP70 is not supported.
Due to widespread security flaws in BIP70 it's strongly recommended that any merchant instructions to switch wallets be ignored.
If you are receiving this error you should request the merchant provide a BIP21 compatible URI.</source>
        <translation>No se puede procesar la solicitud de pago porque no no es compatible con BIP70.
Debido a los fallos de seguridad generalizados en BIP70, se recomienda encarecidamente ignorar las instrucciones del comerciante para cambiar de monedero.
Si recibe este error, debe solicitar al comerciante que le proporcione un URI compatible con BIP21.</translation>
    
ERR
Hay una repetición errónea de "no" en la primera frase ("porque no no es compatible con BIP70") y la redacción puede ser más precisa.

Traducción corregida:
No se puede procesar la solicitud de pago porque BIP70 no es compatible.
Debido a los fallos de seguridad generalizados en BIP70, se recomienda encarecidamente ignorar cualquier instrucción del comerciante para cambiar de monedero.
Si recibe este error, debe solicitar al comerciante que le proporcione un URI compatible con BIP21.
```

<!-- cache_translation_check_es_a9ee2365ae9cbabf03b81cdfd89e1ea7d5c32d9ef176d9ab5382940f99d851e5 -->
```
        <source>Copy after fee</source>
        <translation>Copiar importe después de comisión</translation>
    
ERR
Falta el artículo definido y suena antinatural en español.

Correct translation:
Copiar importe después de la comisión
```

<!-- cache_translation_check_es_0e641e595f56096f38d8d76633c7a0299fb7cefabb0dcc2b4a82fc5188810c1f -->
```
        <source>Can't draft transaction.</source>
        <translation>No puede crear un borrador de la transacción.</translation>
    
ERR
Using "No puede" addresses the user (usted) and is less natural for an impersonal error message. Prefer impersonal construction.

Correct translation:
No se puede crear un borrador de la transacción.
```

<!-- cache_translation_check_es_0287191c3610834f58682201edf907dd58f9b2a2f5fad5bdcf9f4db28a18e098 -->
```
        <source>PSBT copied</source>
        <translation>PSBT copiada </translation>
    
ERR
Trailing whitespace at the end of the translation.

Correct translation:
PSBT copiada
```

<!-- cache_translation_check_es_74ffcc300d24b8bafc6dcbf249c5dda297e601465a140ffddce7eb3dc5362802 -->
```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>PSBT con incremento de comisión copiada en el portapapeles</translation>
    
ERR
Preposition is unnatural; "copiado/a al portapapeles" is standard. Use "al" instead of "en el".

Correct translation:
PSBT con incremento de comisión copiada al portapapeles
```

<!-- cache_translation_check_es_1e0db760e6aa7fdc454345b39f5f958a8e7122ba3bbbf36b6a2673788d1156fc -->
```
        <source>Can't sign transaction.</source>
        <translation>No puede firmar la transacción.</translation>
    
ERR
The Spanish phrasing addresses the user ("No puede..."), while the original is an impersonal system message. Use the impersonal passive for accuracy.

Correct translation:
No se puede firmar la transacción.
```

<!-- cache_translation_check_es_68ef20fb589a8f143457badf67968abe51abe2b89bacb46133975c9b9dee3a9c -->
```
        <source>Can't display address</source>
        <translation>No puede mostrar la dirección</translation>
    
ERR
The Spanish phrasing sounds like “You (formal) cannot show the address.” For a system error, the impersonal form is more appropriate.

Correct translation:
No se puede mostrar la dirección
```

<!-- cache_translation_check_es_9301d218ef71112e4e0ace9adf02c48b95a497d58c429370d5dcede20a88d1b2 -->
```
        <source>SQLiteDatabase: Unknown sqlite wallet schema version %d. Only version %d is supported</source>
        <translation>SQLiteDatabase: versión del esquema de monedero sqlite desconocido (%d). Solo se admite la versión %d.</translation>
    
ERR
Concordancia de género incorrecta ("desconocido" debería ser "desconocida") y se añadieron paréntesis alrededor de %d que no existen en el original.

Correct translation:
SQLiteDatabase: versión del esquema de monedero sqlite desconocida %d. Solo se admite la versión %d.
```

<!-- cache_translation_check_es_33b43a4c0cd96a38b966d91e5002dba96d631193caaedff6c2183974cfba29aa -->
```
        <source>The block database contains a block which appears to be from the future. This may be due to your computer's date and time being set incorrectly. Only rebuild the block database if you are sure that your computer's date and time are correct</source>
        <translation>La base de datos de bloques contiene un bloque que parece ser del futuro. Esto puede deberse a que la fecha y hora del equipo están mal configuradas. Reconstruye la base de datos de bloques solo tienes la certeza de que la fecha y hora del equipo están configuradas correctamente.</translation>
    
ERR
The last sentence is missing "si" after "solo," making it ungrammatical.

Correct translation:
La base de datos de bloques contiene un bloque que parece ser del futuro. Esto puede deberse a que la fecha y hora del equipo están mal configuradas. Reconstruye la base de datos de bloques solo si tienes la certeza de que la fecha y hora del equipo están configuradas correctamente.
```

<!-- cache_translation_check_es_337a93e79c6933a16e30e08b867a8f8c609597d4aa4ecbe77d6ef3c364943fe5 -->
```
        <source>Cannot resolve -%s address: '%s'</source>
        <translation>No se puede resolver - dirección%s: "%s"</translation>
    
ERR
Incorrect placement of the hyphen and spacing around the first %s, missing article, and quotes do not match the source. Ensure both %s are preserved and the formatting mirrors the source.

Correct translation:
No se puede resolver la dirección -%s: '%s'
```

<!-- cache_translation_check_es_8ab377bdb591e052824e00badbd28cf444a7741c8c6d4a33123376cc78a28b6d -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>Poda: la última sincronización sobrepasa los datos podados. Debes ejecutar "-reindex" (descargar toda la cadena de bloques de nuevo en caso de tener un nodo podado).</translation>
    
ERR
The translation omits "wallet" (monedero/cartera), which changes the meaning. Also, the source does not quote -reindex.

Correct translation:
Poda: la última sincronización del monedero sobrepasa los datos podados. Debes ejecutar -reindex (volver a descargar toda la cadena de bloques en caso de un nodo podado).
```

<!-- cache_translation_check_es_33755286e8af434160bb351a07eae26c353084a81eff790652a23fd6c7ce8182 -->
```
        <source>Rename of '%s' -&gt; '%s' failed. Cannot clean up the background chainstate leveldb directory.</source>
        <translation>Error al cambiar el nombre de ''%s" a ''%s". No se puede eliminar el directorio leveldb de chainstate en segundo plano.</translation>
    
ERR
The quotes around the %s placeholders are incorrect (mismatched single/double quotes). Also, "clean up" is better rendered as "limpiar" rather than "eliminar".

Correct translation:
Error al cambiar el nombre de '%s' a '%s'. No se puede limpiar el directorio chainstate de LevelDB en segundo plano.
```

<!-- cache_translation_check_es_72238504c62169d2c007abc62fc7f118f7e8c2aa4df525d6480d2812b0227083 -->
```
        <source>-paytxfee is deprecated and will be fully removed in v31.0.</source>
        <translation>-paytxfee está obsoleto y se eliminará por completo en la versión 31.0.</translation>
    
ERR
The translation changes the literal "v31.0" to "versión 31.0", which may be inconsistent with the original string and product notation.

Correct translation:
-paytxfee está obsoleto y se eliminará por completo en v31.0.
```

<!-- cache_translation_check_es_8656430074c47809074dc42d3477944cca8858d52dce5909774a0f0f66671bda -->
```
        <source>Can't spend unconfirmed version 3 pre-selected input with a version %d tx</source>
        <translation>No se puede gastar una entrada preseleccionada de versión 3 sin confirmar con una transacción de version %d</translation>
    
ERR
Missing accent in the second occurrence of "versión".

Correct translation:
No se puede gastar una entrada preseleccionada de versión 3 sin confirmar con una transacción de versión %d
```

<!-- cache_translation_check_es_56f2c61cb89bb13d12d89ef8f7479e82c7df42b9d3e9812821a2e43b7e44074d -->
```
        <source>Error: Couldn't create cursor into database</source>
        <translation>Error: No pudo crear el cursor en la base de datos</translation>
    
ERR
Spanish needs the impersonal "se" and an indefinite article. The current version implies a specific person and a specific cursor.
Correct translation:
Error: No se pudo crear un cursor en la base de datos
```

<!-- cache_translation_check_es_f52c49c236b3991afe78291a552efcf86a0d90f7b92773844667cbdbd2415faf -->
```
        <source>Failed to close block undo file.</source>
        <translation>No se pudo cerrar el archivo undo de bloques.</translation>
    
ERR
The term "undo" should be translated; using the English word is non-idiomatic. Also "de bloques" is acceptable, but "de bloque" could also work.

Correct translation:
No se pudo cerrar el archivo de reversión de bloques.
```

<!-- cache_translation_check_es_a44906ef8702542a58c2473716fcc22c463ef038ce0c2c2ef7bedd7831f6784b -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>Error al cargar %s: El monedero es de tipo legacy. Realiza la migración a un monedero basado en descriptores mediante la herramienta de migración (RPC migratewallet).</translation>
    
ERR
Minor terminology and consistency issues:
- "legacy" should be translated as "heredado" in Spanish UI terminology.
- Keep the parenthetical term order as in the source: "(migratewallet RPC)".

Correct translation:
Error al cargar %s: el monedero es heredado. Migra a un monedero basado en descriptores usando la herramienta de migración (migratewallet RPC).
```

<!-- cache_translation_check_es_690c6f396b0436be55e8f3827f46f93b63a68f9d1a5db784cb5ede589d42ad36 -->
```
        <source>Invalid -proxy address or hostname, ends with '=': '%s'</source>
        <translation>La dirección -proxy o el nombre de host no son válidos; acaba con "=":"%s"</translation>
    
ERR
Issues:
- Agreement error: mixed plural “no son válidos” with singular “acaba”.
- Quotation mismatch: should keep single quotes around both '=' and %s as in the source.
- Missing space after the colon before the placeholder.

Correct translation:
Dirección o nombre de host de -proxy no válido, termina con '=': '%s'
```

<!-- cache_translation_check_es_2fa571cf15108b171444dd79fd2d5da71933c90f2bde4cf1ebe57f7e9bbe15ac -->
```
        <source>Unrecognized network in -proxy='%s': '%s'</source>
        <translation>Red no reconocida en -proxy="%s": "%s"</translation>
    
ERR
Las comillas alrededor de los especificadores no coinciden con la fuente (dobles en lugar de simples), lo que puede ser problemático en mensajes de registro.

Correct translation:
Red no reconocida en -proxy='%s': '%s'
```
</details>

Number of issues: 25.
