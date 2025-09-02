# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>gl_ES</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bgl_ES%5D%20request)


<!-- cache_translation_check_gl_ES_d205be2cffd855f87f00b1d90afb7b23b4cd7d9408be6af8f5925839b0e087b1 -->
```
        <source>C&amp;lose</source>
        <translation>Pechar</translation>
    
ERR
The translation omits the '&' used for the shortcut key. In Galician, the '&' should appear exactly once, typically as "&Pechar" or "Pechar (&P)" depending on conventions, but "&Pechar" is most common.

Correct translation:
&Pechar
```

<!-- cache_translation_check_gl_ES_bb2135b569bbfeed32d22bfc2fe56c43af179e1b4816f7c8bcc04c29a5510af3 -->
```
        <source>&amp;Export</source>
        <translation>Exportar</translation>
    
ERR
The translation is missing the shortcut key (&) that should appear exactly once. The correct translation must include "&" somewhere in the string.

Correct translation:
&Exportar
```

<!-- cache_translation_check_gl_ES_ab5010033e9affb66796369798d266503aa61a314529db9067acadd13cddeb78 -->
```
        <source>&amp;Delete</source>
        <translation>Borrar</translation>
    
ERR
The translation omits the '&' character, which is used for the shortcut key and should appear exactly once in the translation.

Correct translation:
&Borrar
```

<!-- cache_translation_check_gl_ES_c90a1df685cc3917613ba1d3bcb8c6c50c16843d0b67f0d642183eb5fc5a0b78 -->
```
        <source>Choose the address to receive coins with</source>
        <translation>Selecciona o enderezo do que recibir moedas</translation>
    
ERR
The translation is understandable but inaccurate. The phrase "Selecciona o enderezo do que recibir moedas" literally means "Select the address from which to receive coins," which implies the address is the sender, not the receiver. The correct translation should convey "the address with which to receive coins" or "the address where coins are to be received." 

Correct translation:
Selecciona o enderezo co que recibir moedas
or
Selecciona o enderezo no que recibir moedas
```

<!-- cache_translation_check_gl_ES_af05e23b6043925fbfa0fb74946beab7c59c1b0a997c7c02c14555af9f23f4b8 -->
```
        <source>C&amp;hoose</source>
        <translation>Selecciona</translation>
    
ERR
The English source contains the shortcut key marker '&' (as in C&hoose, which is likely meant to be "Choose" with an accelerator on 'h'), but the Galician translation does not include it. The translation should have a single '&' indicating the shortcut key, preferably in an appropriate place for Galician.

Correct translation:
Selec&ciona
or
&Selleciona

(Choose the letter for '&' based on Galician UI conventions, usually a prominent or unique character.)
```

<!-- cache_translation_check_gl_ES_797d583ec8ac037e43129d5ff07e9b1dd85eab4a3881500456dc8c5fb22c8956 -->
```
        <source>&amp;Copy Address</source>
        <translation>Copiar Enderezo</translation>
    
ERR
The translation is missing the shortcut key indicator '&' that is present in the source and should appear exactly once in the translation.

Correct translation:
&Copiar Enderezo
```

<!-- cache_translation_check_gl_ES_027ac3cf4a2e9a978e7e98e625f557a9cb3578e7e6a911467b70491d98c22ce1 -->
```
        <source>Copy &amp;Label</source>
        <translation>Copia Etiqueta</translation>
    
ERR
The translation is missing the shortcut indicator (&). The ampersand (&) from the source serves to define the keyboard shortcut and should be present exactly once in the translation. 

Correct translation:
Copia &Etiqueta
or
&Copiar Etiqueta

Either placement is acceptable as long as there is only one ampersand (&).
```

<!-- cache_translation_check_gl_ES_5fb63edfad36eb6ed56603df7bc5cf98197e38d676cfa518fed45eb61f55a2b4 -->
```
        <source>&amp;Edit</source>
        <translation>Edita</translation>
    
ERR
The translation omits the ampersand (&) used to indicate the shortcut key. The ampersand should appear exactly once in the translation.

Correct translation:
&amp;Edita
```

<!-- cache_translation_check_gl_ES_68803283e3abafeaa359a598fbac877d28eeda939edb879b5adeb6c9aa180ec4 -->
```
        <source>Wallet to be encrypted</source>
        <translation>Carteira para ser encriptada</translation>
    
ERR
The word "carteira" is incorrect in Galician; it is a Portuguese word. The correct Galician term for "wallet" in this context is "moedeiro". Additionally, "encriptada" is acceptable, but "cifrada" is more standard in Galician when referring to cryptographic encryption.

Correct translation:
Moedeiro para ser cifrado
```

<!-- cache_translation_check_gl_ES_ab851bc2e477735e1e73cf95df1b80f05082060004a712a2b2f6945d6da2a3ff -->
```
        <source>Wallet encryption failed</source>
        <translation>Error na Encriptación da carteira </translation>
    
ERR
There are several issues:
1. "na" should be "na" (Galician for "in the"), but it's not idiomatic in this context. The preposition is unnecessary.
2. "Encriptación" is an accepted form, but "Cifrado" (encryption) is more common and preferred in technical Galician contexts.
3. There is an extra space at the end of the translation.

Correct translation:
Erro na cifrado da carteira
```

<!-- cache_translation_check_gl_ES_d6cb655177e2ae1297cf49db275be5f98959b34df6112365837eeb981ab2722a -->
```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Produciuse un erro non cambio de frase de contrasinal</translation>
    
ERR  
The Galician ('gl_ES') translation is incomplete and erroneous. The provided translation, "Produciuse un erro non cambio de frase de contrasinal", is too short and does not convey the information present in the source, especially regarding the null character and instructions about software version and what the user should do.

Correct translation:
A antiga frase de contrasinal introducida para descifrar a carteira é incorrecta. Contén un carácter nulo (é dicir, un byte cero). Se a frase de contrasinal foi establecida cunha versión deste software anterior á 25.0, inténteo de novo só cos caracteres ata — pero sen incluír — o primeiro carácter nulo.
```

<!-- cache_translation_check_gl_ES_23528ca68459b37e2f2d0334618eb265f17c0d7661af80fd37e030581f7625ce -->
```
        <source>&amp;Transactions</source>
        <translation>&amp;Transaccións</translation>
    
ERR
The translation uses "Transaccións", which is a mix of Spanish ("Transacción") and Galician orthography. The correct Galician term is "Transaccións" or more commonly "Transaccións" (if following the Spanish form), but typically in Galician the correct word is "Transaccións". However, the plural form in authentic Galician would be "Transaccións". The error is subtle, but the spelling is not standard Galician and seems like a hybrid.

Correct translation:
&Transaccións
```

<!-- cache_translation_check_gl_ES_505e38fc6ccfafd1f2941642f68a5729554c949c5e554433400f27f98dec3923 -->
```
        <source>&amp;About %1</source>
        <translation>&amp;A cerca de %1</translation>
    
ERR
In Galician, "Acerca de" is written as one word, not "A cerca de", which is a Spanish misspelling. Also, the use of '&' to indicate the keyboard shortcut is correctly placed and appears only once.

Correct translation:
&Acerca de %1
```

<!-- cache_translation_check_gl_ES_089f7247424ca8d0cd745800789ad62b9debc1056058ebb2aaffa50637c3c6c1 -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation>&amp;Cifrar carteira...</translation>
    
ERR
The translation uses "carteira," which is Portuguese, instead of the correct Galician term "carteira" or "moedeiro." The ellipsis ("...") should be the single character Unicode ellipsis "…", as in the source. 

Correct translation:
&amp;Cifrar moedeiro…
```

<!-- cache_translation_check_gl_ES_7e099f890f3a4a2e88c06544e9dca424006d274a85fe0e55f30f884db4252371 -->
```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>A carteira está &lt;b&gt;encrypted&lt;/b&gt; e actualmente &lt;b&gt;desbloqueada&lt;/b&gt;</translation>
    
ERR
The word "encrypted" is not translated into Galician; this is an untranslated term. For Galician ('gl_ES'), "wallet" is correctly translated as "carteira", "currently" as "actualmente" (not "actualmente" with a c in Galician), and "encrypted" should be translated as "cifrada" or "encriptada".

Correct translation:
A carteira está &lt;b&gt;cifrada&lt;/b&gt; e actualmente &lt;b&gt;desbloqueada&lt;/b&gt;
```

<!-- cache_translation_check_gl_ES_bb2135b569bbfeed32d22bfc2fe56c43af179e1b4816f7c8bcc04c29a5510af3 -->
```
        <source>&amp;Export</source>
        <translation>Exportar</translation>
    
ERR
The translation is missing the shortcut key (&) that should appear exactly once. The correct translation must include "&" somewhere in the string.

Correct translation:
&Exportar
```
</details>

Number of issues: 16.
