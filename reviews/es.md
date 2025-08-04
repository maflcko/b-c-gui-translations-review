# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>es</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bes%5D%20low%20quality)


```
        <source>Exporting Failed</source>
        <translation>Exportación incorrecta</translation>
    
YES, The translation "Exportación incorrecta" means "Incorrect export". The source text "Exporting Failed" means "Exportación fallida". The translation is inaccurate.
The correct translation is: Exportación fallida
```

```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>Sensor</translation>
    
YES - The translation is too generic. In the context of Bitcoin, "feeler" refers to a specific type of connection used to test the network. A more accurate translation would be "ping" or "prueba de conexión".
Translation: Ping
```

```
        <source>Load PSBT from file…</source>
        <translation>Cargar TBPF desde archivo...</translation>
    
YES - The translation is inaccurate. The acronym PSBT stands for Partially Signed Bitcoin Transaction, and it is not standard practice to translate it to TBPF in Spanish. The correct translation should maintain the acronym as it is or provide a more accurate, widely understood Spanish equivalent if one exists, but TBPF is not it.
Cargar PSBT desde archivo…
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>Cargar TBPF desde portapapeles...</translation>
    
YES - The abbreviation "PSBT" should not be translated. The correct translation is "Cargar PSBT desde portapapeles...".
```

```
        <source>Hide</source>
        <translation>Ocultar </translation>
    
YES: The translation has a trailing space.
Ocultar
```

```
        <source>Enable PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Activar controles de TBPF</translation>
    
YES: The translation of "PSBT" to "TBPF" is incorrect. PSBT is a widely recognized acronym in the Bitcoin community and should not be translated.
NO
```

```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Establecer si se muestran los controles de TBPF.</translation>
    
YES - The translation contains an incorrect acronym (TBPF instead of PSBT). The format specifier is also incorrectly translated.
NO - Si se muestran los controles de PSBT.
```

```
        <source>PSBT Operations</source>
        <translation>Operaciones de TBPF</translation>
    
YES: The translation contains an unsupported abbreviation and does not accurately reflect the source text. The correct translation for "PSBT Operations" should be "Operaciones de PSBT".
Operaciones de PSBT
```

```
        <source>PSBT copied to clipboard.</source>
        <translation>TBPF copiada al portapapeles.</translation>
    
YES. The translation is problematic because "TBPF" is an incorrect translation of "PSBT". "PSBT" stands for Partially Signed Bitcoin Transaction.

NO
```

```
        <source>PSBT saved to disk.</source>
        <translation>TBPF guardada en disco.</translation>
    
YES, The Spanish translation is incorrect. The source text uses "PSBT" which is a specific acronym for Partially Signed Bitcoin Transaction. The translation uses "TBPF" which does not correspond to this acronym. It seems like a mistranslation or an arbitrary abbreviation.

NO
```

```
        <source>Whether we relay addresses to this peer.</source>
        <extracomment>Tooltip text for the Address Relay field in the peer details area, which displays whether we relay addresses to this peer (Yes/No).</extracomment>
        <translation>Establecer si retransmitimos las direcciones a este par.</translation>
    
YES - The Spanish translation is inaccurate. It translates "Whether we relay addresses to this peer" as "Establish whether we relay addresses to this peer." The word "Establecer" (Establish) is incorrect in this context. The correct translation should be "Si retransmitimos las direcciones a este par."
NO
```

```
        <source>The total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</source>
        <extracomment>Tooltip text for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>El número total de direcciones recibidas desde este par que se desestimaron (no se procesaron) debido a la limitación de volumen.</translation>
    
YES, The translation is problematic because "rate-limiting" has been translated to "limitación de volumen", which is not the correct translation in this context. The correct translation should be "limitación de velocidad".

The correct translation is: El número total de direcciones recibidas desde este par que se desestimaron (no se procesaron) debido a la limitación de velocidad.
```

```
        <source>Sign failed</source>
        <translation>Firma incorrecta</translation>
    
YES: The translation "Firma incorrecta" means "Incorrect signature" or "Wrong signature". The source text "Sign failed" means "The signing process failed". The correct translation should reflect that the signing process encountered an error.
Firma fallida
```

```
        <source>External signer failure</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Firmante externo incorrecto</translation>
    
YES: The translation "Firmante externo incorrecto" means "Incorrect external signer", which is not an accurate translation of "External signer failure". The correct translation should convey that the external signer has failed.

NO
```

```
        <source>PSBT saved</source>
        <extracomment>Popup message when a PSBT has been saved to a file</extracomment>
        <translation>TBPF guardada</translation>
    
YES: The translation "TBPF guardada" is incorrect. "PSBT" is a specific technical term in the context of Bitcoin, and it should not be translated or abbreviated in this way. The correct translation should be a direct transliteration or the full term if commonly understood.

Correct translation: PSBT guardada
```

```
        <source>Please, review your transaction. You can create and send this transaction or create a Partially Signed Bitcoin Transaction (PSBT), which you can save or copy and then sign with, e.g., an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can send their transaction or create a PSBT. This string is displayed when both private keys and PSBT controls are enabled.</extracomment>
        <translation>Revisa la transacción. Puedes crear y enviar esta transacción de Bitcoin parcialmente firmada (TBPF), que además puedes guardar o copiar y, luego, firmar; por ejemplo, con un monedero %1 sin conexión o un monedero de hardware compatible con TBPF.</translation>
    
YES: The translation incorrectly defines PSBT as "TBPF" which is not the correct or commonly used acronym in Spanish for Partially Signed Bitcoin Transaction. It also incorrectly states that the user can create a "Bitcoin partially signed transaction" directly, when the source states they can create *and send* it or create a PSBT.

The correct translation should be:
Revisa la transacción. Puedes crear y enviar esta transacción o crear una transacción de Bitcoin parcialmente firmada (PSBT), que además puedes guardar o copiar y, luego, firmar; por ejemplo, con un monedero %1 sin conexión o un monedero de hardware compatible con PSBT.
```

```
        <source>PSBT saved to disk</source>
        <translation>TBPF guardada en disco</translation>
    
YES - The translation is incorrect. "PSBT" is a technical term that should not be translated, or if it must be translated, it should be translated as "PSBT" (Partial Bitcoin Transaction Format). The provided translation "TBPF" is not a recognized acronym in the context of Bitcoin and is likely erroneous.

Correct translation: PSBT guardada en disco
```

```
        <source>Copy the current signature to the system clipboard</source>
        <translation>Copiar la dirección seleccionada actualmente al portapapeles del sistema</translation>
    
YES - The translation incorrectly translates "signature" to "dirección" (address).
Copiar la firma actual al portapapeles del sistema
```

```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Inmadura (%1 confirmaciones; estará disponibles después de %2)</translation>
    
YES - The translation uses "Inmadura" which is feminine, but the English sentence is neutral. It should be "Inmaduro". Also, the English text uses a comma after %1, but the translation uses a semicolon. The correct translation should use a comma.
Inmaduro (%1 confirmaciones, estará disponible después de %2)
```

```
        <source>Exporting Failed</source>
        <translation>Exportación incorrecta</translation>
    
YES, The translation "Exportación incorrecta" means "Incorrect export". The source text "Exporting Failed" means "Exportación fallida". The translation is inaccurate.
The correct translation is: Exportación fallida
```

```
        <source>PSBT copied</source>
        <translation>TBPF copiada </translation>
    
YES. The translation is problematic because it uses the incorrect abbreviation for PSBT and includes an unnecessary trailing space.

Correct translation: PSBT copiado
```

```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>TBPF con incremento de comisión copiada en el portapapeles</translation>
    
YES: The translation uses an unfamiliar acronym "TBPF" instead of translating "Fee-bump PSBT" which is the key element of the message. The acronym "PSBT" (Partially Signed Bitcoin Transaction) is a technical term that should ideally be kept or explained if translated. "Fee-bump" refers to increasing the transaction fee.

A more accurate and understandable translation would be: "PSBT con aumento de comisión copiado al portapapeles".
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Esta es la comisión de transacción que puedes descartar si el cambio es más pequeño que el remanente en este nivel.</translation>
    
YES - The translation uses "remanente" for "dust". In Bitcoin terminology, "dust" refers to very small amounts of Bitcoin that are uneconomical to spend. "Remanente" means remainder or residue, which is not the correct term. The correct translation for "dust" in this context is "polvo" or simply leaving it as "dust" if the audience is familiar with the English term.

NO
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>El nivel de registro específico de la categoría no es compatible: %1$s=%2$s. Se esperaba %1$s=&lt;category&gt;:&lt;loglevel&gt;. Categorías válidas: %3$s. Niveles de registro válidos: %4 $s.</translation>
    
YES: The translation has a spacing error. The '%' symbol in '%4 $s' should not have a space before the '$'.

Correct translation: El nivel de registro específico de la categoría no es compatible: %1$s=%2$s. Se esperaba %1$s=&lt;category&gt;:&lt;loglevel&gt;. Categorías válidas: %3$s. Niveles de registro válidos: %4$s.
```

```
        <source>Rename of '%s' -&gt; '%s' failed. Cannot clean up the background chainstate leveldb directory.</source>
        <translation>Error al cambiar el nombre de ''%s" a ''%s". No se puede limpiar el directorio leveldb del estado de la cadena de fondo.</translation>
    
YES, The translation contains a formatting error with the apostrophes around the %s placeholders. The apostrophes should not be there, and the "%s" format specifier should be directly next to the quotes.

NO
```

```
        <source>Error: Disk space is low for %s</source>
        <translation>Error: El espacio en disco es pequeño para %s</translation>
    
YES: The Spanish word "pequeño" (small) is not the correct translation for "low" in this context. The correct word to indicate a lack of space is "bajo".
Error: El espacio en disco es bajo para %s
```

```
        <source>Failed to listen on any port. Use -listen=0 if you want this.</source>
        <translation>Fallo al escuchar en todos los puertos. Usa -listen=0 si quieres hacerlo.</translation>
    
YES, the translation uses an incorrect verb conjugation. "Fallo" should be "Fallo al escuchar".
Fallo al escuchar en todos los puertos. Usa -listen=0 si quieres hacerlo.
```

```
        <source>Ignoring duplicate -wallet %s.</source>
        <translation>Ignorar duplicación de -wallet %s.</translation>
    
YES. The Spanish translation uses "duplicación de" which sounds a bit unnatural and could be more concise. A more direct and common way to express "duplicate" in this context would be "duplicado". Also, the hyphen in "-wallet" should be preserved.

Correct translation: Ignorar -wallet duplicado %s.
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>El bloque génesis es incorrecto o no se encontró. ¿Equivocación en el directorio de datos para la red?</translation>
    
YES: The translation uses "Equivocación" which is too informal and not appropriate for the technical context of Bitcoin. It should be "Error" or "Incorrecto".
El bloque génesis es incorrecto o no se encontró. ¿Directorio de datos incorrecto para la red?
```

```
        <source>Invalid -i2psam address or hostname: '%s'</source>
        <translation>La dirección -i2psam o el nombre de host no es válido: "%s" </translation>
    
YES - The translation has an extra space before the closing quotation mark.
The address -i2psam or hostname is invalid: "%s"
```

```
        <source>Unsupported logging category %s=%s.</source>
        <translation>La categoría de registro no es compatible %s=%s. </translation>
    
YES, The translation has an extra space before the period.
The category of registration is not supported %s=%s.
```
</details>
