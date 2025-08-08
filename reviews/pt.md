# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>pt</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bpt%5D%20low%20quality)


<!-- cache_translation_check_pt_834327e41641a4a1a078516919153ca637da84d0237fcf925bd89661206d3f88 -->
```
        <source>Sending addresses</source>
        <translation>Endereço de envio</translation>
    
ERR
The translation is inaccurate. The English phrase "Sending addresses" is plural, referring to multiple addresses, while the Portuguese translation "Endereço de envio" is singular.

Correct translation:
Endereços de envio
```

<!-- cache_translation_check_pt_411049a1fe4d879633292087b59997b239bd6e1bccc5054788b33c47cec24acb -->
```
        <source>Unit to show amounts in. Click to select another unit.</source>
        <translation>Unidade de quantias recebidas. Clique para selecionar outra unidade.</translation>
    
ERR  
The translation is inaccurate. The source says "Unit to show amounts in," which refers to the unit for displaying any amount (not just received amounts). The translation incorrectly restricts this to "quantias recebidas" ("received amounts"). Also, "Unidade de quantias recebidas" omits the idea of "showing/visualizing" amounts.

Correct translation:  
Unidade para exibir valores. Clique para selecionar outra unidade.
```

<!-- cache_translation_check_pt_72fee4ce3bb5a418b9bddd9b7f5206e9401ef4873ec03648095069b6b3ce68d7 -->
```
        <source>Connect to the Bitcoin network through a SOCKS5 proxy.</source>
        <translation>Conectar à rede da Bitcoin através dum proxy SOCLS5.</translation>
    
ERR
There is a typo in the translation: "SOCLS5" should be "SOCKS5". Also, "da Bitcoin" is less idiomatic; "do Bitcoin" or simply "à rede Bitcoin" is more usual.

Correct translation:
Conectar à rede Bitcoin através de um proxy SOCKS5.
```

<!-- cache_translation_check_pt_b07ebeb8789e837d761ef7cef3267c8557749d65b8097fa26ea16c42431f31a8 -->
```
        <source>Show the icon in the system tray.</source>
        <translation>Mostrar o ícone na barra de ferramentas.</translation>
    
ERR
The translation is inaccurate. "System tray" should be translated as "área de notificação" or "bandeja do sistema", not "barra de ferramentas" (which means "toolbar").

Correct translation:
Mostrar o ícone na área de notificação.
or
Mostrar o ícone na bandeja do sistema.
```

<!-- cache_translation_check_pt_3066ae43fd36a7facff35d1ddb7dc9331e88078a53b07e42c60b8dced3cf657c -->
```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>Modo de privacidade ativado para a aba Resumo. para desmascarar os valores, desmarque nas Configurações -&gt; Valores de máscara</translation>
    
ERR  
There are minor issues with the translation:

1. The first letter after the period should be uppercase ("para" → "Para").
2. The phrase "Valores de máscara" does not accurately reflect the original "Mask values" setting; "Mascarar valores" or "Ocultar valores" would be clearer and more idiomatic.
3. The hyphen should have spacing consistent with UI references ("Configurações -> Mascarar valores").

Correct translation:
Modo de privacidade ativado para a aba Resumo. Para desmascarar os valores, desmarque em Configurações -> Mascarar valores.
```

<!-- cache_translation_check_pt_c6b92bf0d1619af628215c9ebd569b8fa0f24d903fa1c5f08bfaca45103f49d4 -->
```
        <source>Ban for</source>
        <translation>Banir para</translation>
    
ERR
The translation "Banir para" is not idiomatic in Portuguese. The English phrase "Ban for" (for example, "Ban for X minutes") would be better translated as "Banir por" to indicate duration.

Correct translation:
Banir por
```

<!-- cache_translation_check_pt_e3e733cfd468f5995177ae0cd1cefdb1d18c3e973820e54506b3e8d40f51e00c -->
```
        <source>The amount to pay must be larger than 0.</source>
        <translation>A quantia a pagar dever maior que 0.</translation>
    
ERR
The translation has a grammatical error: "dever" should be "deve ser" to correctly express "must be". Also, "quantia" is fine, but "valor" is also commonly used. 

Correct translation:
A quantia a pagar deve ser maior que 0.
```

<!-- cache_translation_check_pt_91d6dda1861d5595a187a070bc13de6b919cb3589820758b179312acf23911ab -->
```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Imaturo (%1 confirmações, estarão disponível após %2)</translation>
    
ERR  
The translation uses "estará disponível" (singular) instead of "estarão disponíveis" (plural) to refer to confirmations, which is incorrect. Also, "disponível" should agree in number with "confirmações" (plural).  

Correct translation:  
Imaturo (%1 confirmações, estarão disponíveis após %2)
```

<!-- cache_translation_check_pt_1aed7b099f2640a221d714fdbf00d6f1675fb04cb0b7d6efb669ac73bfdbe475 -->
```
        <source>Generated but not accepted</source>
        <translation>Gerada mas não aceite</translation>
    
ERR
The translation has two issues: 
1. "Gerada" is feminine, but "accept" here refers to a transaction or block, which in Portuguese is "gerado" (masculine) if it refers to "bloco" or "valor". 
2. The expression "não aceite" is rarely used; "não aceite" is imperative or participle for "to accept", but the more common participle in PT-BR/European PT should be "aceito".

Correct translation:
Gerado mas não aceito
```

<!-- cache_translation_check_pt_6b7f7b94be926c7c2ceaf70b8bc20efb4053ac55e246549aedeb422223f48906 -->
```
        <source>Unable to decode PSBT from clipboard (invalid base64)</source>
        <translation>Não foi possível descodificar a transação de Bitcoin parcialmente assinada (PSTB) da área de transferência (base64 inválida)</translation>
    
ERR
The abbreviation "PSBT" is incorrectly rendered as "PSTB" in the translation—it should remain "PSBT". Also, for consistency and technical context, retaining the English acronym is preferred. Otherwise, the translation is accurate.

Correct translation:
Não foi possível descodificar a PSBT (Partially Signed Bitcoin Transaction) da área de transferência (base64 inválida)
```

<!-- cache_translation_check_pt_827f5cd3c074aff5de36fb3153f8773fcc3eddcd67025c4a1f4d0a9977a6b84b -->
```
        <source>Warning: This may pay the additional fee by reducing change outputs or adding inputs, when necessary. It may add a new change output if one does not already exist. These changes may potentially leak privacy.</source>
        <translation>Aviso: pode pagar a taxa adicional reduzindo as saídas ou aumentando as entradas, quando necessário. Poderá ser acrescentada uma nova moeda, caso ainda não exista nenhuma. Estas alterações podem potencialmente causar fugas de privacidade.</translation>
    
ERR  
There are issues with the translation's accuracy and terminology:

1. The source talks about "reducing change outputs" and "adding inputs", but the translation omits "change" (“troco”) and renders "change outputs" simply as "saídas", which could confuse the context (as "saídas" can refer to all outputs, not specifically change outputs).
2. "It may add a new change output if one does not already exist." is translated as "Poderá ser acrescentada uma nova moeda, caso ainda não exista nenhuma." ("moeda" is "coin", which is not accurate; should be "saída de troco").
3. "leak privacy" is better as "comprometer a privacidade" rather than "causar fugas de privacidade".

Correct translation:
Aviso: Isto pode pagar a taxa adicional reduzindo as saídas de troco ou adicionando entradas, quando necessário. Pode ser acrescentada uma nova saída de troco caso ainda não exista. Estas alterações podem potencialmente comprometer a privacidade.
```

<!-- cache_translation_check_pt_ab45f2d4deb9645331332d430516d97112e14eb9236579453b8f4fcfd8feb010 -->
```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Erro: esta versão do bitcoin-wallet apenas suporta ficheiros dump na versão 1. (Versão atual: %s)</translation>
    
ERR
The translation omits the phrase "Dumpfile version is not supported" and "Got dumpfile with version %s", which makes it less complete and less accurate compared to the source. The source error message also gives both the unsupported status and specifies the version encountered.

Correct translation:
Erro: A versão do ficheiro dump não é suportada. Esta versão do bitcoin-wallet apenas suporta ficheiros dump na versão 1. Foi encontrado um ficheiro dump com a versão %s.
```

<!-- cache_translation_check_pt_2a38d3c4a7fbcfd6042deee3037e17b0e3523b2d637edd00195517cd1216e087 -->
```
        <source>Error: Legacy wallets only support the "legacy", "p2sh-segwit", and "bech32" address types</source>
        <translation>Erro: as carteiras legadas apenas suportam os tipos de endereço "legado", "p2sh-segwit" e "bech32</translation>
    
ERR
There is a missing closing quotation mark after "bech32" in the translation. Otherwise, the translation is accurate and unproblematic.

Correct translation:
Erro: as carteiras legadas apenas suportam os tipos de endereço "legado", "p2sh-segwit" e "bech32"
```

<!-- cache_translation_check_pt_4eba6ea0f2ba21c5fda3f70f668f3a01cba4b8d1803b92a15da07f3a0664b046 -->
```
        <source>File %s already exists. If you are sure this is what you want, move it out of the way first.</source>
        <translation>O ficheiro%s já existe. Se tem a certeza que é isso que quer, mova-o primeiro para fora do caminho.</translation>
    
ERR
There is a missing space between "ficheiro" and "%s". In Portuguese, "ficheiro" and the file name should be separated by a space. Additionally, the phrase "mova-o primeiro para fora do caminho" is slightly awkward, but not incorrect; however, commonly "mova-o para outro local primeiro" would be clearer.

Correct translation:
O ficheiro %s já existe. Se tem a certeza de que é isso que quer, mova-o para outro local primeiro.
```

<!-- cache_translation_check_pt_47041c6a51886d74d2e60456a8a0acc93fa427c26d701430a464b961ebf86ad7 -->
```
        <source>Invalid or corrupt peers.dat (%s). If you believe this is a bug, please report it to %s. As a workaround, you can move the file (%s) out of the way (rename, move, or delete) to have a new one created on the next start.</source>
        <translation>O ficheiro peers.dat (%s) está corrompido ou é inválido. Se acredita qua se trata de um "bug", por favor reporte para %s. Como solução, pode mover, alterar o nome ou eliminar (%s) para ser criado um novo na próxima inicialização</translation>
    
ERR
There are a few issues:
1. Minor typo: "qua se trata" should be "que se trata".
2. The placement of the format specifier (%s) is not entirely consistent with the source. It should be clearer that "mover, alterar o nome ou eliminar" refers to "o ficheiro (%s)", matching the source.
3. There's a missing period at the end of the translation.
4. A comma or 'ou' should clarify the list of actions (rename, move or delete) in Portuguese.

Correct translation:
O ficheiro peers.dat (%s) está corrompido ou é inválido. Se acredita que se trata de um bug, por favor reporte para %s. Como solução, pode mover o ficheiro (%s), alterar o nome ou eliminar para que um novo seja criado na próxima inicialização.
```

<!-- cache_translation_check_pt_2bfe177e4280359fe16d315632962366f235dac588b5c3fea5064e986af8b8f8 -->
```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on enormous cluster of unconfirmed transactions.</source>
        <translation>Não foi possível calcular as taxas de compensação, porque os UTXOs não confirmados dependem de um enorme conjunto de transações não confirmadas..</translation>
    
ERR
There are two issues: 1) There is a double period at the end of the sentence ("não confirmadas.."). 2) "bump fees" is not properly translated; "taxas de compensação" is not the standard term in Bitcoin context. The correct expression would be "taxas de aumento" or "taxas para incrementar".

Correct translation:
Não foi possível calcular as taxas de aumento, porque os UTXOs não confirmados dependem de um enorme conjunto de transações não confirmadas.
```

<!-- cache_translation_check_pt_1f02c0dba2663f6297306617169259f44c21625c667974c76a2ada3dec5e9b2f -->
```
        <source>Rename of '%s' -&gt; '%s' failed. Cannot clean up the background chainstate leveldb directory.</source>
        <translation>Renomear de '%s' -&gt; '%s'falhou. Não é possível limpar o diretório leveldb do chainstate em segundo plano.</translation>
    
ERR
There is a missing space after the arrow ("'%s' -&gt; '%s'falhou"), so it reads as "'%s' -&gt; '%s'falhou" instead of "'%s' -&gt; '%s' falhou". Additionally, "Renomear de ... falhou" is awkward in Portuguese; a more natural rendering would be "Falha ao renomear de ... para ...".

Correct translation:
Falha ao renomear de '%s' -&gt; '%s'. Não é possível limpar o diretório leveldb do chainstate em segundo plano.
```

<!-- cache_translation_check_pt_280444c4ef418dd2c14f4e051ff039321931b8370a634fe1e19957ae69555734 -->
```
        <source>A fatal internal error occurred, see debug.log for details: </source>
        <translation>Ocorreu um fatal internal error, consulte debug.log para obter detalhes:</translation>
    
ERR
The translation incorrectly leaves "fatal internal error" untranslated. It should be fully translated into Portuguese, and the overall phrasing should be more natural.

Correct translation:
Ocorreu um erro interno fatal, consulte o debug.log para obter detalhes:
```

<!-- cache_translation_check_pt_16ec4266e1e696ba6f3209ee8b9668bf49741cbdaf7c098641bc6fdeb1b8c52c -->
```
        <source>Pruning blockstore…</source>
        <translation>Prunando os blocos existentes…</translation>
    
ERR  
The term "Prunando os blocos existentes…" is not an accurate or idiomatic translation of "Pruning blockstore…". "Prunando" is a neologism and not commonly used in Portuguese; the standard would be "Podando". Additionally, "blockstore" is better translated as "armazenamento de blocos" or simply "blocos" depending on context, but "os blocos existentes" changes the meaning.  

Correct translation:  
Podando o armazenamento de blocos…
```

<!-- cache_translation_check_pt_255ae7369a0881f01db99125dfd7ea861e4347ca6f3574c6724a2d66679d0f09 -->
```
        <source>Rescanning…</source>
        <translation>A tornar a examinar…</translation>
    
ERR
The translation "A tornar a examinar…" is incorrect and is a literal or awkward structure likely based on European Portuguese norms, but the verb phrase is not standard in Portuguese.

A more accurate translation would be:
A reexaminar…
or
A reescanear…
or
Reanalisando…

Depending on context, "Reexaminando…" or "Reescaneando…" (Brazilian Portuguese) are also acceptable. The key is to use the correct verbal form and inflection.

Correct translation:
Reexaminando…
or
A reexaminar…
or
Reescaneando…
```

<!-- cache_translation_check_pt_3d343833a6ab34506a762b0216d36de51e8e82bf5c1340217917f56a20f6a8f3 -->
```
        <source>Transaction must have at least one recipient</source>
        <translation>A transação dever pelo menos um destinatário</translation>
    
ERR
There is an error in the translation: "dever" should be "deve ter" to correctly say "must have" in Portuguese. "Dever" alone means "must", while "deve ter" corresponds to "must have". There is also a missing word "ter" in the translation.

Correct translation:
A transação deve ter pelo menos um destinatário
```
</details>

Number of issues: 21.
