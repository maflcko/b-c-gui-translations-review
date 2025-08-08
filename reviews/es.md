# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>es</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bes%5D%20low%20quality)


<!-- cache_translation_check_es_9bad0e76c68c46a6bbd1f536fd3d07e775f1066a402f58d5d0c6c6d9bcb0288c -->
```
        <source>Exporting Failed</source>
        <translation>Exportación incorrecta</translation>
    
ERR
The translation "Exportación incorrecta" is not the best equivalent for "Exporting Failed". "Incorrecta" means "incorrect" or "wrong", which does not directly convey that the export operation failed. A more accurate translation is "Error al exportar" or "La exportación falló".

Correct translation:
Error al exportar
```

<!-- cache_translation_check_es_6ef0187887d75c9e6a3149d9ec9179b46b33ac20abd43ee20d3e3d5a7b14b13d -->
```
        <source>Load PSBT from file…</source>
        <translation>Cargar TBPF desde archivo...</translation>
    
ERR
The abbreviation "TBPF" is incorrect in Spanish. The correct translation for "PSBT" (Partially Signed Bitcoin Transaction) is usually kept as "PSBT", since it's an established acronym; it is not typically translated nor rearranged to "TBPF".

Also, the ellipsis at the end should use the Unicode ellipsis character (…) for consistency with the source (instead of three dots ...).

Correct translation:
Cargar PSBT desde archivo…
```

<!-- cache_translation_check_es_c98005d5e22baef97c822fb40d1883bd8a1692f017ce1b9ebdfcd903be63b796 -->
```
        <source>Hide</source>
        <translation>Ocultar </translation>
    
ERR
There is an unwanted trailing space after "Ocultar", which is a whitespace formatting issue.

Correct translation:
Ocultar
```

<!-- cache_translation_check_es_cc0d89daceab71a8db71cbc4c3662e986972df63652273821a585bb845c9560d -->
```
        <source>Enable PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Activar controles de TBPF</translation>
    
ERR
The translation is problematic: "TBPF" does not correspond to "PSBT" in Spanish. The correct abbreviation is "PSBT", as it is a technical term (Partially Signed Bitcoin Transaction) and is not localized. Also, the rest of the translation is accurate.

Correct translation:
Activar controles de PSBT
```

<!-- cache_translation_check_es_0521b08e0040b9eabb08b469210e7118379e1792ff95abe8f1a922459f0d08c5 -->
```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Establecer si se muestran los controles de TBPF.</translation>
    
ERR
The translation is problematic because "PSBT" should be left untranslated, not rendered as "TBPF". Also, "Establecer si se muestran..." ("Set whether to show...") is less natural than "Mostrar los controles PSBT."

Correct translation:
Mostrar los controles de PSBT.
```

<!-- cache_translation_check_es_7072c5be0341c369eaac01cc868dfce4b178f9570bce31c3e13bd1ece22a6928 -->
```
        <source>PSBT Operations</source>
        <translation>Operaciones de TBPF</translation>
    
ERR
The translation erroneously renders "PSBT" (Partially Signed Bitcoin Transaction) as "TBPF," which does not correspond to any known Bitcoin acronym in Spanish. The acronym "PSBT" should be kept in translation, as it is not localized.

Correct translation:
Operaciones de PSBT
```

<!-- cache_translation_check_es_8a5e8e23df36067e95a47a95557d86e335bcaae89ecf7f704c6b7a9be36f3dbc -->
```
        <source>PSBT saved to disk.</source>
        <translation>TBPF guardada en disco.</translation>
    
ERR
The translation is problematic because the acronym "PSBT" (Partially Signed Bitcoin Transaction) should not be localized as "TBPF." In Spanish contexts, "PSBT" is commonly used as is. "guardada" should agree in number ("PSBT guardada" if referring to a feminine noun) but "PSBT" is treated as feminine in practice. However, the main issue is with the acronym translation.

Correct translation:
PSBT guardada en disco.
```

<!-- cache_translation_check_es_f72611a3f782c43221bb396468eaf4f4e33dee8c1dc0073328d9c2bacc61313c -->
```
        <source>Sign failed</source>
        <translation>Firma incorrecta</translation>
    
ERR
The translation "Firma incorrecta" means "Incorrect signature" or "Wrong signing", not "Sign failed". The correct translation should indicate that the signing process failed.

Correct translation:
Error al firmar
```

<!-- cache_translation_check_es_598de604daf819ca8b60989f0c8ee0786b320a19cae83d2bc6e469f5effab63b -->
```
        <source>External signer failure</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Firmante externo incorrecto</translation>
    
ERR
The translation "Firmante externo incorrecto" means "incorrect external signer," but the source refers to a failure (which could be an error, malfunction, or some other problem), not necessarily "incorrect." A better translation would convey a general failure.

Correct translation:
Error del firmante externo
```

<!-- cache_translation_check_es_fb61377aaa00b13be2c30ebd0919cb8d0948952ca924d46008783a125bcf1bef -->
```
        <source>PSBT saved</source>
        <extracomment>Popup message when a PSBT has been saved to a file</extracomment>
        <translation>TBPF guardada</translation>
    
ERR
The translation is problematic because "PSBT" stands for "Partially Signed Bitcoin Transaction" and is typically not translated, especially in technical contexts; however, "TBPF" corresponds to the Spanish initialism, but it is very uncommon and potentially confusing in the Bitcoin community where "PSBT" is standard. Also, "guardada" is feminine, while "PSBT" in Spanish would likely be treated as masculine ("el archivo PSBT") or neutral; to match the context, "guardado" is preferable for masculine/neutral, or "guardada" if "transacción" is implied, which is not explicit here.

Correct translation:
PSBT guardado
```

<!-- cache_translation_check_es_35e4426ffec80464ccd13c5343987b0ae0643c84b6ce00975e73bad44dd6fb3c -->
```
        <source>Please, review your transaction. You can create and send this transaction or create a Partially Signed Bitcoin Transaction (PSBT), which you can save or copy and then sign with, e.g., an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can send their transaction or create a PSBT. This string is displayed when both private keys and PSBT controls are enabled.</extracomment>
        <translation>Revisa la transacción. Puedes crear y enviar esta transacción de Bitcoin parcialmente firmada (TBPF), que además puedes guardar o copiar y, luego, firmar; por ejemplo, con un monedero %1 sin conexión o un monedero de hardware compatible con TBPF.</translation>
    
ERR
The translation is not accurate. The meaning is changed:

1. The translation implies that the transaction itself is "parcialmente firmada" (partially signed), but the source says you can either create and send a transaction, or create a PSBT.
2. The abbreviation "TBPF" is used for PSBT, but the normal Spanish term is "PSBT" or, in some contexts, "Transacción de Bitcoin Parcialmente Firmada", but the abbreviation "TBPF" is very rare or nonstandard; "PSBT" is preferred to match the original and standard Bitcoin terminology.
3. The order and logic are merged; in the original, sending and PSBT are alternative options, not part of the same step.
4. "transacción de Bitcoin parcialmente firmada" is only correct when referring to PSBT, not the immediate transaction.
5. Some details, like "you can save or copy and then sign", are merged to be less clear in Spanish.

Correct translation:
Por favor, revisa tu transacción. Puedes crear y enviar esta transacción, o crear una Transacción de Bitcoin Parcialmente Firmada (PSBT), que puedes guardar o copiar y luego firmar, por ejemplo, con un monedero %1 fuera de línea o un monedero de hardware compatible con PSBT.
```

<!-- cache_translation_check_es_d85eff9e17524a1a7711cb9da20293b6c09d4e44519d5f16b742a6ba1f246e37 -->
```
        <source>Copy the current signature to the system clipboard</source>
        <translation>Copiar la dirección seleccionada actualmente al portapapeles del sistema</translation>
    
ERR  
The translation is incorrect. It says "Copy the currently selected address to the system clipboard" instead of "Copy the current signature to the system clipboard".

Correct translation:  
Copiar la firma actual al portapapeles del sistema
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

<!-- cache_translation_check_es_9bad0e76c68c46a6bbd1f536fd3d07e775f1066a402f58d5d0c6c6d9bcb0288c -->
```
        <source>Exporting Failed</source>
        <translation>Exportación incorrecta</translation>
    
ERR
The translation "Exportación incorrecta" is not the best equivalent for "Exporting Failed". "Incorrecta" means "incorrect" or "wrong", which does not directly convey that the export operation failed. A more accurate translation is "Error al exportar" or "La exportación falló".

Correct translation:
Error al exportar
```

<!-- cache_translation_check_es_de8ef9694cd17c841567a17b04b1278f049bf88fd0df82d7ad7e46fdfa13ad73 -->
```
        <source>PSBT copied</source>
        <translation>TBPF copiada </translation>
    
ERR
The translation is problematic. "PSBT" stands for "Partially Signed Bitcoin Transaction" and should not be translated or altered to "TBPF". The correct translation would keep "PSBT" and translate "copied":

Correct translation:
PSBT copiada
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

<!-- cache_translation_check_es_52b3398a9d0f081c845422cf67d694a907b206a1a9597855aa89f320cffd6289 -->
```
        <source>Error: Disk space is low for %s</source>
        <translation>Error: El espacio en disco es pequeño para %s</translation>
    
ERR
The phrase "el espacio en disco es pequeño" is not the most accurate or natural translation. The typical expression in Spanish for insufficient disk space is "bajo" or "insuficiente" rather than "pequeño". 

Correct translation:
Error: El espacio en disco es bajo para %s
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

<!-- cache_translation_check_es_9295bd68c3610e1e1f7b0ee9d89c9f17313d4d5d770299e4f3740937d6fb13e7 -->
```
        <source>Unsupported logging category %s=%s.</source>
        <translation>La categoría de registro no es compatible %s=%s. </translation>
    
ERR
There is a minor issue with an extra space at the end of the translated sentence. Otherwise, the translation is accurate and correctly maintains the format specifiers.

Correct translation:
La categoría de registro no es compatible %s=%s.
```
</details>

Number of issues: 20.
