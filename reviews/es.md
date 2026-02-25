# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bes%5D%20request)



<details><summary>es</summary>


<!-- cache_translation_check_es_0b2b40482548f71ec5efeba28ba7fb886338b2f4e0bb6e6cb3879f00d639de16 -->
```
        <source>Connecting to peers…</source>
        <translation>Conectando con sus pares ...</translation>
    
ERR
The translation contains unnecessary spaces before the ellipsis, and the ellipsis itself uses three separate periods instead of the single character used in the source (though the source uses three dots, the spacing issue is the main concern). Additionally, "sus pares" is a bit formal/literal; in Bitcoin contexts, "pares" or "compañeros" is usually used without the possessive "sus".

Correct translation:
Conectando con pares…
```

<!-- cache_translation_check_es_649f1d331807940c7bd3a04ee08f84d329745823f20fd863e4efa9f751688e2f -->
```
        <source>Last received block was generated %1 ago.</source>
        <translation>El último bloque recibido fue generado hace %1 horas.</translation>
    
ERR
The translation incorrectly adds the word "horas" (hours). The placeholder %1 in this context typically represents a formatted time duration (e.g., "5 minutes" or "2 days"). Adding "horas" would result in incorrect phrases like "hace 5 minutos horas".

Correct translation:
El último bloque recibido fue generado hace %1.
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

<!-- cache_translation_check_es_7072c5be0341c369eaac01cc868dfce4b178f9570bce31c3e13bd1ece22a6928 -->
```
        <source>PSBT Operations</source>
        <translation>Operaciones de TBPF</translation>
    
ERR
The acronym "PSBT" (Partially Signed Bitcoin Transaction) is a technical standard and is almost universally kept as "PSBT" in Spanish-speaking Bitcoin contexts. Translating it to "TBPF" (Transacción de Bitcoin Parcialmente Firmada) is non-standard and would likely confuse users who are looking for the technical term.

Correct translation:
Operaciones PSBT
```

<!-- cache_translation_check_es_8a5e8e23df36067e95a47a95557d86e335bcaae89ecf7f704c6b7a9be36f3dbc -->
```
        <source>PSBT saved to disk.</source>
        <translation>TBPF guardada en disco.</translation>
    
ERR
The translation uses the acronym "TBPF", which is not a standard or recognized translation for "PSBT" (Partially Signed Bitcoin Transaction) in Spanish. In Spanish technical contexts, the acronym "PSBT" is typically kept as is, or the full phrase "transacción de Bitcoin firmada parcialmente" is used.

Correct translation:
PSBT guardada en disco.
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

<!-- cache_translation_check_es_f349d93ada954e01ff7439058c9c58f6d6dc2912563098a5515a6ed536b3daaa -->
```
        <source>Wallet unlock was cancelled.</source>
        <translation>Se ha cancelado el desbloqueo del monedero. </translation>
    
ERR
The translation contains a trailing space after the period, which violates the requirement to ensure no whitespace format issues exist.

Correct translation:
Se ha cancelado el desbloqueo del monedero.
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

<!-- cache_translation_check_es_63e0134a046cac1d2f8737790dce4da76fae106ec25a0bd7f275328e21770e0c -->
```
        <source>Last month</source>
        <translation>El mes pasado </translation>
    
ERR
There is a trailing whitespace at the end of the translation which is not present in the source.

Correct translation:
El mes pasado
```

<!-- cache_translation_check_es_de8ef9694cd17c841567a17b04b1278f049bf88fd0df82d7ad7e46fdfa13ad73 -->
```
        <source>PSBT copied</source>
        <translation>TBPF copiada </translation>
    
ERR
The translation contains a trailing space and uses a non-standard acronym. In the context of Bitcoin, "PSBT" (Partially Signed Bitcoin Transaction) is a technical standard and is typically kept as "PSBT" in Spanish, rather than being translated to "TBPF".

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

<!-- cache_translation_check_es_a1e4c3beb5432c1dc7eb676b56eba296d6fa5794c75306e200fb89a9c80cd0ef -->
```
        <source>Error loading %s: External signer wallet being loaded without external signer support compiled</source>
        <translation>Error de carga %s : Se está cargando el monedero del firmante externo sin que se haya compilado el soporte del firmante externo</translation>
    
ERR
There is an unnecessary space before the colon. In Spanish, like in English, there should be no space before a colon.

Correct translation:
Error de carga %s: Se está cargando el monedero del firmante externo sin que se haya compilado el soporte del firmante externo
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

<!-- cache_translation_check_es_7ba901c8087555807438816dc9d3c93eabace5e96a9f47351d7d8a8da86d8bac -->
```
        <source>A %zu MiB dbcache may be too large for a system memory of only %zu MiB.</source>
        <translation>%zuMiB dbcache es demasiado grande para una memoria del sistema de solamente %zu MiB.</translation>
    
ERR
There is a missing space between the format specifier '%zu' and the unit 'MiB' in the first instance. Additionally, the translation omits the indefinite article "A" at the beginning and translates "may be" (puede ser) as "is" (es).

Correct translation:
Un dbcache de %zu MiB puede ser demasiado grande para una memoria del sistema de solamente %zu MiB.
```

<!-- cache_translation_check_es_8ed647a9abc33638e38815ace000db61f2585cfb60886e8f9464a86c87a0841b -->
```
        <source>The transactions removal process can only be executed within a db txn</source>
        <translation>El proceso de eliminación de transacciones sólo puede ejecutarse dentro de una base de datos de transacción</translation>
    
ERR
The translation of "db txn" (database transaction) is incorrect. "base de datos de transacción" translates back to "transaction database", whereas "db txn" refers to a transaction within a database.

Correct translation:
El proceso de eliminación de transacciones solo puede ejecutarse dentro de una transacción de base de datos.
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

Number of issues: 28.
