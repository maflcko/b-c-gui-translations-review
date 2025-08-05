# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>gl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bgl%5D%20low%20quality)


```
        <source>Choose the address to receive coins with</source>
        <translation>Escolle a dirección da que recibir moedas</translation>
    
YES  
The translation "Escolle a dirección da que recibir moedas" literally means "Choose the address from which to receive coins," which contradicts the source meaning that is about choosing the address **to receive** coins (i.e., "to" indicates the destination, not the source). A more accurate translation to convey the intended meaning is:

"Escolle a dirección para recibir moedas"
```

```
        <source>change from %1 (%2)</source>
        <translation>Cambia de %1 a (%2)</translation>
    
YES
The translation incorrectly uses "a" which means "to," altering the meaning. The source phrase "change from %1 (%2)" should reflect "change from" intuitively as "cambio de" or "cambios de" without adding "a."

Correct translation:
Cambia de %1 (%2)
```

```
        <source>Reset Options</source>
        <translation>Opcións de Restaurar</translation>
    
YES  
The translation "Opcións de Restaurar" is incorrect. The source phrase "Reset Options" refers to a command or label related to resetting configuration options, so it should be translated as "Restablecer opcións" or "Restablecer opcións" in Galician. The word "Opcións" is correct, but "Restaurar" means "Restore," not "Reset." Also, there should be no plural article "de" in this context.  

Correct translation:  
Restablecer opcións
```

```
        <source>This change would require a client restart.</source>
        <translation>Este cambio requeriría un reinicio do cliente.</translation>
    
YES  
The translation is in Spanish, not in Galician (gl).  
Correct translation in Galician:  
Este cambio requeriría un reinicio do cliente.  

(Note: The provided translation text is identical, but as it stands it is Spanish, not Galician. However, in this case, the correct Galician translation would be almost the same but changing the article "un" to "un" is correct; the phrase "un reinicio do cliente" is correct in Galician. The only difference is that the phrase starts with "Este" which is identical in both Spanish and Galician. The provided translation is actually correct Galician, as "Este cambio requeriría un reinicio do cliente." is correct in Galician.)  

Re-evaluating, the translation is actually correct Galician and matches the source in meaning, and there are no format specifiers to check. No extra spacing issues.

Therefore, the initial judgment was incorrect.

Final decision:  
NO
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Total de transaccións que aínda teñen que ser confirmadas, e non contan todavía dentro do balance gastable</translation>
    
YES  
The translation uses "todavía," which is Spanish, not Galician ("aínda" should be used consistently). Also, "balance" in Galician is usually translated as "saldo." The phrase "inside the spendable balance" is better translated as "no saldo dispoñible para gastar" rather than "dentro do balance gastable." Correct terminology and consistent use of Galician improves clarity.

Correct translation:  
"Total de transaccións que aínda teñen que ser confirmadas, e non contan aínda no saldo dispoñible para gastar"
```

```
        <source>Send Coins</source>
        <translation>Moedas Enviadas</translation>
    
YES  
The translation is incorrect. "Send Coins" is an imperative or a button label meaning to send coins, so it should be translated as a command or action ("Enviar moedas"). The provided translation "Moedas Enviadas" means "Coins Sent," which is past tense and does not match the original intent.

Correct translation:  
Enviar moedas
```

```
        <source>Reset all verify message fields</source>
        <translation>Restaurar todos os campos de verificación de mensaxe</translation>
    
YES  
The translation uses "Restaurar" which is not the best choice in Galician for "Reset." A more accurate and commonly used term is "Restablecer" or "Reiniciar." Also, "mensaxe" should be in the singular or plural depending on the source context; since the source says "message" (singular), "mensaxe" is correct. The rest of the translation is accurate and no format specifiers or spacing issues are present.

Correct translation:  
Restablecer todos os campos de verificación da mensaxe
```

```
        <source>Click "Sign Message" to generate signature</source>
        <translation>Click en "Asinar Mensaxe" para xerar sinatura</translation>
    
YES  
The translation is mostly correct but it mixes English and Galician. The word "Click" should be translated to "Fai click" or "Preme" in Galician to keep the entire sentence consistent in the 'gl' language.  

Correct translation:  
Fai click en "Asinar Mensaxe" para xerar sinatura
```

```
        <source>Send Coins</source>
        <translation>Moedas Enviadas</translation>
    
YES  
The translation is incorrect. "Send Coins" is an imperative or a button label meaning to send coins, so it should be translated as a command or action ("Enviar moedas"). The provided translation "Moedas Enviadas" means "Coins Sent," which is past tense and does not match the original intent.

Correct translation:  
Enviar moedas
```

```
        <source>Unknown network specified in -onlynet: '%s'</source>
        <translation>Rede descoñecida especificada en -onlynet: '%s'</translation>
    
YES  
The translation contains a typo: "Rede" should be "Rede" (correct, meaning "network" in Galician), but the word "descoñecida" is correctly spelled. However, the phrase "Redes descoñecida" should be "Rede descoñecida" since "rede" is feminine singular, so the adjective must agree in gender and number: "descoñecida". This part is correct. The grammatical issue is in the article: "Rede" is singular feminine, so "descoñecida" is correct, but "Rede descoñecida" is correct as is.

Checking the original: "Unknown network specified in -onlynet: '%s'"

Translation: "Rede descoñecida especificada en -onlynet: '%s'"

This is accurate and clear.

Therefore, no error from the first point.

But the output says "Rede descoñecida", which is correct.

No whitespace errors, format specifier '%s' is correctly placed.

Therefore, the translation is accurate and unproblematic.

Output should be NO.

Reconsider. The initial "YES" was a mistake.

Correct output:

NO
```
</details>
