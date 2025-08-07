# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>gl_ES</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bgl_ES%5D%20low%20quality)


```
        <source>Choose the address to receive coins with</source>
        <translation>Selecciona o enderezo do que recibir moedas</translation>
    
YES
The translation is understandable but inaccurate. The phrase "Selecciona o enderezo do que recibir moedas" literally means "Select the address from which to receive coins," which implies the address is the sender, not the receiver. The correct translation should convey "the address with which to receive coins" or "the address where coins are to be received." 

Correct translation:
Selecciona o enderezo co que recibir moedas
or
Selecciona o enderezo no que recibir moedas
```

```
        <source>Wallet to be encrypted</source>
        <translation>Carteira para ser encriptada</translation>
    
YES
The word "carteira" is incorrect in Galician; it is a Portuguese word. The correct Galician term for "wallet" in this context is "moedeiro". Additionally, "encriptada" is acceptable, but "cifrada" is more standard in Galician when referring to cryptographic encryption.

Correct translation:
Moedeiro para ser cifrado
```

```
        <source>Wallet encryption failed</source>
        <translation>Error na Encriptación da carteira </translation>
    
YES
There are several issues:
1. "na" should be "na" (Galician for "in the"), but it's not idiomatic in this context. The preposition is unnecessary.
2. "Encriptación" is an accepted form, but "Cifrado" (encryption) is more common and preferred in technical Galician contexts.
3. There is an extra space at the end of the translation.

Correct translation:
Erro na cifrado da carteira
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Produciuse un erro non cambio de frase de contrasinal</translation>
    
YES  
The Galician ('gl_ES') translation is incomplete and erroneous. The provided translation, "Produciuse un erro non cambio de frase de contrasinal", is too short and does not convey the information present in the source, especially regarding the null character and instructions about software version and what the user should do.

Correct translation:
A antiga frase de contrasinal introducida para descifrar a carteira é incorrecta. Contén un carácter nulo (é dicir, un byte cero). Se a frase de contrasinal foi establecida cunha versión deste software anterior á 25.0, inténteo de novo só cos caracteres ata — pero sen incluír — o primeiro carácter nulo.
```

```
        <source>About %1</source>
        <translation>A cerca de %1</translation>
    
YES
The translation incorrectly separates "acerca" into "a cerca", which is not correct in Galician (nor in Spanish). The correct expression is "Acerca de %1". Also, Galician for "About" is usually translated as "Sobre" or "Acerca de".

Correct translation:
Acerca de %1
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>A carteira está &lt;b&gt;encrypted&lt;/b&gt; e actualmente &lt;b&gt;desbloqueada&lt;/b&gt;</translation>
    
YES
The word "encrypted" is not translated into Galician; this is an untranslated term. For Galician ('gl_ES'), "wallet" is correctly translated as "carteira", "currently" as "actualmente" (not "actualmente" with a c in Galician), and "encrypted" should be translated as "cifrada" or "encriptada".

Correct translation:
A carteira está &lt;b&gt;cifrada&lt;/b&gt; e actualmente &lt;b&gt;desbloqueada&lt;/b&gt;
```
</details>

Number of issues: 6.
