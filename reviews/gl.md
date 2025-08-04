# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>gl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bgl%5D%20low%20quality)


```
        <source>Choose the address to receive coins with</source>
        <translation>Escolle a dirección da que recibir moedas</translation>
    
YES, the translation is problematic. The English source "Choose the address to receive coins with" means to select a Bitcoin address to send coins to. The provided Galician translation "Escolle a dirección da que recibir moedas" translates to "Choose the address from which to receive coins", which is the opposite meaning.

NO
```

```
        <source>Copy Address</source>
        <translation>Copiar Enderezo</translation>
    
YES - The translation uses "Enderezo" which is a Portuguese word, not Galician. The correct Galician word for "address" is "Enderezo".
NO
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Precaución: Se encriptas o teu moedeiro e perdes o teu contrasinal, ti &lt;b&gt;PERDERÁS TÓDOLOS TEUS BITCOINS&lt;/b&gt;!</translation>
    
YES - The translation uses "o teu moedeiro" which translates to "your wallet" in English, but it should be "a túa carteira" in Galician. Additionally, "Se encriptas" is grammatically incorrect and should be "Se encriptas a túa carteira".

Correct translation: Precaución: Se encriptas a túa carteira e perdes o teu contrasinal, perderás &lt;b&gt;TÓDOLOS TEUS BITCOINS&lt;/b&gt;!
```

```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>Introduce a frase contrasinal anterior mais a nova frase contrasinal para a carteira.</translation>
    
YES, the translation is problematic due to incorrect word choice and grammar. The word "frase contrasinal" is not standard Galician for "passphrase". Additionally, the use of "mais a" is not the correct way to connect the two phrases.

The correct translation should be:

Introduce o contrasinal antigo e o novo contrasinal para a carteira.
```

```
        <source>Wallet to be encrypted</source>
        <translation>Carteira para ser encriptada</translation>
    
UNK_LANG
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>A frase de acceso introducida para o descifrado da carteira é incorrecta. Contén un carácter nulo (é dicir, un byte cero). Se a frase de paso se estableceu cunha versión deste software anterior á 25.0, téntao de novo con só os caracteres ata, pero sen incluír, o primeiro carácter nulo. Se se realiza correctamente, establece unha nova frase de acceso para evitar este problema no futuro.</translation>
    
YES: The translation uses "frase de acceso" which is Portuguese for "passphrase", but the target language is Galician ('gl'). In Galician, the correct term is "contrasinal" or "clave". Additionally, "frase de paso" is also a valid term in Galician, but "frase de acceso" is incorrect.

The translation is also problematic because it contains "frase de acceso" which is Portuguese for "passphrase". The correct Galician translation for "passphrase" is "contrasinal" or "clave".

Correct translation: A contrasinal introducida para o descifrado da carteira é incorrecta. Contén un carácter nulo (é dicir, un byte cero). Se a contrasinal se estableceu cunha versión deste software anterior á 25.0, téntao de novo con só os caracteres ata, pero sen incluír, o primeiro carácter nulo. Se se realiza correctamente, establece unha nova contrasinal para evitar este problema no futuro.
```

```
        <source>Passphrase change failed</source>
        <translation>Produciuse un erro no cambio de frase de contrasinal</translation>
    
YES - The translation uses an incorrect verb for "failed." The correct translation should be "Falou o cambio da frase de contrasinal."
```

```
        <source>Change Passphrase…</source>
        <translation>Cambiar a frase de contrasinal...</translation>
    
YES, The translation is incorrect. The word "contrasinal" is not a valid Galician word. The correct translation for "passphrase" is "contrasinal" or "contrasinal".

Correct translation: Cambiar a frase de contrasinal...
```

```
        <source>Open a bitcoin: URI</source>
        <translation>Abre una URI de Bitcoin</translation>
    
YES: The translation is in Spanish ("es") and not Galician ("gl"). The correct translation into Galician would be "Abre unha URI de Bitcoin".
```

```
        <source>Received with address</source>
        <translation>Recibida con enderezo</translation>
    
YES, The translation is incorrect. The word "enderezo" is not a valid Galician word. The correct translation should use "enderezo" as it appears in the source text.
Recibida co enderezo
```

```
        <source>change from %1 (%2)</source>
        <translation>Cambia de %1 a (%2)</translation>
    
YES
The translation incorrectly uses "Cambia de" which implies a change *from* something. The English "change from" in this context refers to the Bitcoin transaction change, meaning the remaining amount of Bitcoin returned to the sender. The correct translation should reflect this meaning.

NO
```

```
        <source>Edit Address</source>
        <translation>Modificar Enderezo</translation>
    
YES
The translation uses "Enderezo" which is Portuguese for "Address". The correct Galician word for "Address" is "Enderezo". However, since the source language is English and the target language is specified as 'gl' (Galician), "Enderezo" is the correct translation in this context.

The provided translation "Modificar Enderezo" is actually correct for Galician. It seems there was a misunderstanding in the prompt regarding the language identifier. Galician (gl) and Portuguese (pt) share many similarities, and "endereço" is a valid word in both.

However, if we are strictly evaluating for *unwanted content, erroneous content, or spam* and the context is Bitcoin addresses, the translation is accurate and appropriate.

NO
```

```
        <source>Reset Options</source>
        <translation>Opcións de Restaurar</translation>
    
YES
The translation uses "Restaurar" which is the infinitive form of the verb "to restore". The correct translation should be the noun form "Restauración". Also, "Opcións" should be "Opcións".

Correct translation: Opcións de restauración
```

```
        <source>This change would require a client restart.</source>
        <translation>Este cambio requeriría un reinicio do cliente.</translation>
    
YES, The translation uses Spanish instead of Galician. The correct translation in Galician is: Este cambio requiriría un reinicio do cliente.
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Total de transaccións que aínda teñen que ser confirmadas, e non contan todavía dentro do balance gastable</translation>
    
YES - The word "transaccións" is misspelled. The correct spelling is "transaccións".
Total de transaccións que aínda teñen que ser confirmadas, e non contan todavía dentro do balance gastable
```

```
        <source>Resulting URI too long, try to reduce the text for label / message.</source>
        <translation>A URI resultante é demasiado larga, tenta reducir o texto para a etiqueta / mensaxe.</translation>
    
YES: The translation uses "A URI resultante é demasiado larga" which is Portuguese. The target language is Galician ('gl'). In Galician, "URI" should be "URI" and "resultante" should be "resultante" or "resultada". "demasiado" should be "demasiado" or "demasiado". "larga" should be "lonxitud" or "longa".

Correct translation: A URI resultante é demasiado longa, tenta reducir o texto para a etiqueta / mensaxe.
```

```
        <source>Copy Address</source>
        <translation>Copiar Enderezo</translation>
    
YES - The translation uses "Enderezo" which is a Portuguese word, not Galician. The correct Galician word for "address" is "Enderezo".
NO
```

```
        <source>Send Coins</source>
        <translation>Moedas Enviadas</translation>
    
YES, The translation is incorrect. "Send Coins" is a command or an action, while "Moedas Enviadas" means "Coins Sent", which is a past action or a statement of fact. The correct translation should be "Enviar Moedas".
YES, The translation is incorrect. "Send Coins" is a command or an action, while "Moedas Enviadas" means "Coins Sent", which is a past action or a statement of fact. The correct translation should be "Enviar Moedas".
```

```
        <source>Send to multiple recipients at once</source>
        <translation>Enviar a múltiples receptores á vez</translation>
    
YES - The translation is in Spanish, not Galician. The correct translation to Galician is "Enviar a múltiples destinatarios á vez".
```

```
        <source>Reset all verify message fields</source>
        <translation>Restaurar todos os campos de verificación de mensaxe</translation>
    
YES, The translation is inaccurate. The word "verify" is translated to "verificación", which is the noun form. The correct translation should use the adjective form "verificar" to modify "mensaxe".
Restaurar todos os campos de mensaxe a verificar
```

```
        <source>Click "Sign Message" to generate signature</source>
        <translation>Click en "Asinar Mensaxe" para xerar sinatura</translation>
    
YES: The translation incorrectly uses "Asinar Mensaxe" instead of the correct Galician phrase for "Sign Message", which is "Asinar Mensaxe". Additionally, the source text uses a placeholder for a button label which should be preserved.
Correct translation: Click "Asinar Mensaxe" para xerar sinatura
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/sen confirmar</translation>
    
YES: The translation is inaccurate. The correct translation for "%1/unconfirmed" in Galician, in the context of Bitcoin, is "%1/sen confirmar". The provided translation is "%1/sen confirmar", which is the correct translation. There seems to be a mistake in the provided answer. The correct answer should be "NO".

NO
```

```
        <source>Send Coins</source>
        <translation>Moedas Enviadas</translation>
    
YES, The translation is incorrect. "Send Coins" is a command or an action, while "Moedas Enviadas" means "Coins Sent", which is a past action or a statement of fact. The correct translation should be "Enviar Moedas".
YES, The translation is incorrect. "Send Coins" is a command or an action, while "Moedas Enviadas" means "Coins Sent", which is a past action or a statement of fact. The correct translation should be "Enviar Moedas".
```

```
        <source>Unknown network specified in -onlynet: '%s'</source>
        <translation>Rede descoñecida especificada en -onlynet: '%s'</translation>
    
UNK_LANG
```
</details>
