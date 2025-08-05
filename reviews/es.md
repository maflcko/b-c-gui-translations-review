# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>es</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bes%5D%20low%20quality)


```
        <source>Exporting Failed</source>
        <translation>Exportación incorrecta</translation>
    
YES  
The Spanish translation "Exportación incorrecta" means "Incorrect export" or "Wrong export," which does not perfectly convey the English message "Exporting Failed." A better translation reflecting failure in the process would be:

Correct translation:  
Exportación fallida
```

```
        <source>Load PSBT from file…</source>
        <translation>Cargar TBPF desde archivo...</translation>
    
YES
The translation incorrectly translates "PSBT" as "TBPF". "PSBT" (Partially Signed Bitcoin Transaction) is a standard acronym and should remain untranslated. The ellipsis character is also different between source and translation—the source uses a single Unicode ellipsis (…) while the translation uses three periods (...). It is better to keep the same ellipsis character for consistency.

Correct translation:
Cargar PSBT desde archivo…
```

```
        <source>Hide</source>
        <translation>Ocultar </translation>
    
YES
The translation contains a trailing whitespace after "Ocultar". The word itself is a correct translation of "Hide" in this context.

Correct translation:
Ocultar
```

```
        <source>Enable PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Activar controles de TBPF</translation>
    
YES  
The acronym PSBT (Partially Signed Bitcoin Transaction) should be preserved as is, not translated into Spanish as TBPF. The correct translation keeps the acronym unchanged.

Correct translation:  
Activar controles de PSBT
```

```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Establecer si se muestran los controles de TBPF.</translation>
    
YES  
The translation inaccurately translates "PSBT" as "TBPF," which is incorrect. The acronym PSBT (Partially Signed Bitcoin Transaction) should remain as "PSBT" in the translation. Additionally, the translation introduces unnecessary words ("Establecer si"), which slightly changes the original meaning. A more accurate and concise translation would be:

"Mostrar controles de PSBT."
```

```
        <source>PSBT Operations</source>
        <translation>Operaciones de TBPF</translation>
    
YES  
The acronym "PSBT" (Partially Signed Bitcoin Transaction) should not be translated into "TBPF" as it is a standard term in Bitcoin context. It is better to keep "PSBT" as is.

Correct translation:  
Operaciones PSBT
```

```
        <source>PSBT saved to disk.</source>
        <translation>TBPF guardada en disco.</translation>
    
YES  
The abbreviation "PSBT" (Partially Signed Bitcoin Transaction) should be preserved as is in Spanish, since it is a technical acronym commonly used in Bitcoin contexts. The translation "TBPF" is incorrect and unclear.  

Correct translation:  
PSBT guardada en disco.
```

```
        <source>Sign failed</source>
        <translation>Firma incorrecta</translation>
    
YES  
The translation "Firma incorrecta" means "Incorrect signature" rather than "Sign failed." The correct translation should accurately convey that the signing operation failed, not that the signature itself is incorrect.

Correct translation:  
"Error al firmar"
```

```
        <source>External signer failure</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Firmante externo incorrecto</translation>
    
YES  
The translation "Firmante externo incorrecto" means "Incorrect external signer," which implies an error in the signer being incorrect rather than a failure of the external signer. A more accurate translation that preserves the meaning of a failure (i.e., malfunction or error) would be:

**Correct translation:**  
Fallo del firmante externo
```

```
        <source>PSBT saved</source>
        <extracomment>Popup message when a PSBT has been saved to a file</extracomment>
        <translation>TBPF guardada</translation>
    
YES  
The abbreviation "PSBT" (Partially Signed Bitcoin Transaction) should be kept as is in Spanish, as it is a standard technical term, not translated as "TBPF." The rest of the translation is correct in gender agreement ("guardada" for feminine), since "transacción" is feminine, but here the message is short and "PSBT" is an English acronym that should remain unchanged.

Correct translation:  
PSBT guardada
```

```
        <source>Please, review your transaction. You can create and send this transaction or create a Partially Signed Bitcoin Transaction (PSBT), which you can save or copy and then sign with, e.g., an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can send their transaction or create a PSBT. This string is displayed when both private keys and PSBT controls are enabled.</extracomment>
        <translation>Revisa la transacción. Puedes crear y enviar esta transacción de Bitcoin parcialmente firmada (TBPF), que además puedes guardar o copiar y, luego, firmar; por ejemplo, con un monedero %1 sin conexión o un monedero de hardware compatible con TBPF.</translation>
    
YES
The translation incorrectly replaces "Partially Signed Bitcoin Transaction (PSBT)" with "Bitcoin parcialmente firmada (TBPF)," which is not the accepted or used Spanish acronym and changes the meaning slightly. It also omits the option to either "create and send this transaction" or "create a PSBT," instead only mentioning creating and sending a "partially signed Bitcoin transaction," which differs from the source.

Correct translation:
Por favor, revisa tu transacción. Puedes crear y enviar esta transacción o crear una Transacción Bitcoin Parcialmente Firmada (PSBT), que puedes guardar o copiar y luego firmar, por ejemplo, con un monedero %1 fuera de línea o un monedero hardware compatible con PSBT.
```

```
        <source>Copy the current signature to the system clipboard</source>
        <translation>Copiar la dirección seleccionada actualmente al portapapeles del sistema</translation>
    
YES  
The translation is incorrect as it changes the meaning of the original text. The source talks about copying the "current signature," but the translation refers to copying the "currently selected address," which is wrong. The correct translation should accurately reflect the "current signature."

Correct translation:  
Copiar la firma actual al portapapeles del sistema
```

```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Inmadura (%1 confirmaciones; estará disponibles después de %2)</translation>
    
YES
The translation has a subject-verb agreement error: "Estará" should be "Estarán" to agree with "confirmaciones" (plural). Also, the semicolon is not necessary and a comma is more natural in Spanish. Correct translation:
Inmadura (%1 confirmaciones, estarán disponibles después de %2)
```

```
        <source>Exporting Failed</source>
        <translation>Exportación incorrecta</translation>
    
YES  
The Spanish translation "Exportación incorrecta" means "Incorrect export" or "Wrong export," which does not perfectly convey the English message "Exporting Failed." A better translation reflecting failure in the process would be:

Correct translation:  
Exportación fallida
```

```
        <source>PSBT copied</source>
        <translation>TBPF copiada </translation>
    
YES  
There is an extra space at the end of the translation. Also, "PSBT" should be translated following its Spanish acronym or kept as is if it's a known term, but "PSBT" (Partially Signed Bitcoin Transaction) is commonly kept as "PSBT" in Spanish technical contexts. The given translation "TBPF" is an incorrect acronym and does not correspond to "PSBT". 

Correct translation:  
PSBT copiada
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>El nivel de registro específico de la categoría no es compatible: %1$s=%2$s. Se esperaba %1$s=&lt;category&gt;:&lt;loglevel&gt;. Categorías válidas: %3$s. Niveles de registro válidos: %4 $s.</translation>
    
YES
There is an incorrect format specifier in the Spanish translation: "%4 $s" has an extra space and should be "%4$s" to match the source format specifier exactly. Also, the colon after "nivel" in the source ("category-specific logging level %1$s=%2$s") was translated as "no es compatible:" which is acceptable but slightly altering the structure; however, this is not a critical issue. The main problem is the whitespace in the format specifier.

Correct translation:
El nivel de registro específico de la categoría no es compatible: %1$s=%2$s. Se esperaba %1$s=&lt;category&gt;:&lt;loglevel&gt;. Categorías válidas: %3$s. Niveles de registro válidos: %4$s.
```

```
        <source>Rename of '%s' -&gt; '%s' failed. Cannot clean up the background chainstate leveldb directory.</source>
        <translation>Error al cambiar el nombre de ''%s" a ''%s". No se puede limpiar el directorio leveldb del estado de la cadena de fondo.</translation>
    
YES  
The translation has inconsistent and incorrect use of quotation marks around the placeholders '%s'. In the source, single quotes (') are used, but in the translation, it uses doubled single quotes ('') and mismatched double quotes ("). This should be corrected to use consistent and matching single quotes, as in the source.

Correct translation:  
Error al cambiar el nombre de '%s' -> '%s' falló. No se puede limpiar el directorio leveldb del estado de la cadena de fondo.
```

```
        <source>Error: Disk space is low for %s</source>
        <translation>Error: El espacio en disco es pequeño para %s</translation>
    
YES  
The Spanish translation "El espacio en disco es pequeño para %s" is not a natural or accurate way to express "Disk space is low." The word "pequeño" means "small," which is incorrect in this context. The proper adjective to describe low disk space is "bajo" or the phrase "poco espacio en disco."  

Correct translation:  
Error: El espacio en disco es bajo para %s  
or better:  
Error: El espacio en disco es insuficiente para %s
```

```
        <source>Ignoring duplicate -wallet %s.</source>
        <translation>Ignorar duplicación de -wallet %s.</translation>
    
YES  
The translation is inaccurate and sounds unnatural in Spanish. The English gerund "Ignoring" indicates a present continuous action, which would be better translated using a gerund or present participle form in Spanish (e.g., "Ignorando"). Also, it is better to include an article and connect the elements more naturally.

Correct translation:  
"Ignorando duplicado -wallet %s."
```

```
        <source>Invalid -i2psam address or hostname: '%s'</source>
        <translation>La dirección -i2psam o el nombre de host no es válido: "%s" </translation>
    
YES
The translation has a whitespace issue: there is an extra space before the closing quotation mark and at the end of the sentence. Also, the source text uses single quotes around %s, while the translation uses double quotes; it is better to keep the same style for consistency. Additionally, the source says "address or hostname" as separate items, but the translation says "dirección -i2psam o el nombre de host," which is fine, but it can be slightly improved for clarity.

Correct translation:
La dirección o el nombre de host -i2psam no son válidos: '%s'
```

```
        <source>Unsupported logging category %s=%s.</source>
        <translation>La categoría de registro no es compatible %s=%s. </translation>
    
YES
There is a trailing whitespace at the end of the translation and the phrasing is slightly unnatural. A more natural and direct translation would be:

Categoría de registro no soportada %s=%s.
```
</details>
