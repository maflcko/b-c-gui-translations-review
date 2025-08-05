# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>pt</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bpt%5D%20low%20quality)


```
        <source>Runaway exception</source>
        <translation>Exceção de fuga (runaway)</translation>
    
YES
The translation "Exceção de fuga (runaway)" is awkward and not idiomatic in Portuguese. The term "runaway exception" refers to an exception that propagates uncontrollably. A better translation would be simply "Exceção descontrolada" or "Exceção fora de controle," which conveys the intended meaning more naturally.

Correct translation:
Exceção descontrolada
```

```
        <source>Sending addresses</source>
        <translation>Endereço de envio</translation>
    
YES  
The English source "Sending addresses" is plural and likely means multiple addresses used for sending (e.g., Bitcoin sending addresses). The translation "Endereço de envio" is singular and translates as "Sending address," which is inaccurate. The correct plural form should be:  

"Endereços de envio"
```

```
        <source>Unit to show amounts in. Click to select another unit.</source>
        <translation>Unidade de quantias recebidas. Clique para selecionar outra unidade.</translation>
    
YES  
The translation misinterprets "amounts" (which refers to quantities or values) as "quantias recebidas" (received amounts), which is not accurate. The correct translation should reflect that the unit is for showing amounts in general, not specifically received ones.

Correct translation:  
Unidade para mostrar os valores. Clique para selecionar outra unidade.
```

```
        <source>Restore wallet message</source>
        <extracomment>Title of message box which is displayed when the wallet is successfully restored.</extracomment>
        <translation>Mensagem de restaurar a carteira</translation>
    
YES
The translation is overly literal and sounds unnatural in Portuguese. A better, more natural phrasing for a message box title indicating successful wallet restoration would be:

Mensagem de carteira restaurada
```

```
        <source>Connect to the Bitcoin network through a SOCKS5 proxy.</source>
        <translation>Conectar à rede da Bitcoin através dum proxy SOCLS5.</translation>
    
YES  
There is a spelling error in the word "SOCKS5," which is incorrectly written as "SOCLS5." Also, "a Bitcoin" should be "a rede Bitcoin" (without "da") because "Bitcoin" as a network is commonly untranslated and does not require the article "da." The phrase "através dum" is somewhat informal; more formal and common is "através de um."  

Correct translation:  
Conectar à rede Bitcoin através de um proxy SOCKS5.
```

```
        <source>Show the icon in the system tray.</source>
        <translation>Mostrar o ícone na barra de ferramentas.</translation>
    
YES  
The English source refers specifically to the "system tray," which is typically the area near the clock in the taskbar where icons for running applications appear. The translation "barra de ferramentas" means "toolbar," which is not equivalent to "system tray." The correct Portuguese translation should refer to the system tray explicitly.

Correct translation:  
Mostrar o ícone na bandeja do sistema.
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>Modo de privacidade ativado para a aba Resumo. para desmascarar os valores, desmarque nas Configurações -&gt; Valores de máscara</translation>
    
YES  
The translation has a few issues:  
1. The sentence after the period should start with a capital letter ("para" → "Para").  
2. "Configurações" should be plural but with no extra space before the arrow and it should be consistent with the source format "Settings-&gt;Mask values." ("-&gt;Valores de máscara").  
3. The phrase "Valores de máscara" is a bit awkward; a more natural translation would be "Mascarar valores" or "Mascarar os valores" to match "Mask values."  
4. The punctuation is missing at the end (original ends with a period).  

Correct translation:  
Modo de privacidade ativado para a aba Resumo. Para desmascarar os valores, desmarque em Configurações-&gt;Mascarar valores.
```

```
        <source>Ban for</source>
        <translation>Banir para</translation>
    
YES  
The verb "Banir" is incorrectly conjugated here. In the context of a software message, "Ban for" (indicating a duration or reason) should be translated as "Banir por" or more naturally as "Banir durante" or simply "Banir" depending on context. However, the infinitive "Banir" followed by "para" is incorrect.  

A better translation would be:  
"Banir por"  
or if the English message is incomplete and expects a duration, "Banir por" is the closest equivalent.
```

```
        <source>The amount to pay must be larger than 0.</source>
        <translation>A quantia a pagar dever maior que 0.</translation>
    
YES  
The translation is missing the verb "ser" ("must be" = "deve ser") and is therefore incomplete and incorrect. Also, it lacks the preposition "que" after "dever".  

Correct translation:  
A quantia a pagar deve ser maior que 0.
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/não confirmado</translation>
    
YES  
The source "%1/unconfirmed" is a concise status indicator showing the number of unconfirmed transactions (e.g., "3/unconfirmed"). Translating it as "%1/não confirmado" is inconsistent because "não confirmado" is longer and changes the format; it should keep the slash and use the word "unconfirmed" as a single word equivalent.

A better translation is "%1/não confirmados" or "%1/ não confirmado" but since it's a status label, the literal and more commonly used Bitcoin Portuguese equivalent is to keep the slash and use "não confirmado" as an adjective, but without spacing issues.

However, to maintain the original format and brevity, and since it's showing a count plus a label, the translation should be:

"%1/não confirmados"

instead of "%1/não confirmado" because "confirmados" (plural) matches the count implied by %1.

Correct translation:  
%1/não confirmados
```

```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>Imaturo (%1 confirmações, estarão disponível após %2)</translation>
    
YES  
There is a subject-verb agreement error in the translation. "confirmações" is plural, so "estarão" is correct, but "disponível" should be plural "disponíveis" to agree with it. Additionally, the article before "disponível" is missing in the original translation, but it's acceptable to omit it here.  

Correct translation:  
Imaturo (%1 confirmações, estarão disponíveis após %2)
```

```
        <source>Generated but not accepted</source>
        <translation>Gerada mas não aceite</translation>
    
YES  
The translation uses "mas" which is a conjunction meaning "but," but the correct word in Portuguese for "but" in this context is "mas" (correct), so this part is correct. However, the main issue is with the gender agreement and verb form: "Generated" translated as "Gerada" is feminine singular, but "Generated" as a standalone participle should be "Gerado" (masculine singular) or gender-neutral depending on context. Since it's likely referring to a masculine noun like "bloco" or "hash," "Gerado" is preferred. Also, "aceite" is the past participle for "accepted," which is correct, but if "aceite" is used in European Portuguese, it is standard; in Brazilian Portuguese, "aceito" is used. Assuming European Portuguese (given "aceite"), this is acceptable.

Therefore, the corrected translation is:

Gerado mas não aceite
```

```
        <source>Unable to decode PSBT from clipboard (invalid base64)</source>
        <translation>Não foi possível descodificar a transação de Bitcoin parcialmente assinada (PSTB) da área de transferência (base64 inválida)</translation>
    
YES  
There is a typo in the acronym "PSBT": the source has "PSBT", but the translation writes "PSTB". Also, the translation explicitly expands "PSBT" as "transação de Bitcoin parcialmente assinada", which is acceptable but should keep the original acronym "PSBT" (not "PSTB").  

Correct translation:  
Não foi possível decodificar PSBT da área de transferência (base64 inválida)
```

```
        <source>Warning: This may pay the additional fee by reducing change outputs or adding inputs, when necessary. It may add a new change output if one does not already exist. These changes may potentially leak privacy.</source>
        <translation>Aviso: pode pagar a taxa adicional reduzindo as saídas ou aumentando as entradas, quando necessário. Poderá ser acrescentada uma nova moeda, caso ainda não exista nenhuma. Estas alterações podem potencialmente causar fugas de privacidade.</translation>
    
YES
The translation incorrectly translates "change output" as "nova moeda" (new currency/coin), which changes the meaning significantly. In the Bitcoin context, "change output" refers to a specific transaction output returning leftover funds, not "new currency." The correct translation should use "saída de troco" or "saída de mudança" to reflect the Bitcoin term.

Correct translation:
Aviso: pode pagar a taxa adicional reduzindo as saídas de troco ou aumentando as entradas, quando necessário. Pode ser acrescentada uma nova saída de troco, caso ainda não exista nenhuma. Estas alterações podem potencialmente causar fugas de privacidade.
```

```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Erro: esta versão do bitcoin-wallet apenas suporta ficheiros dump na versão 1. (Versão atual: %s)</translation>
    
YES
The Portuguese translation omits some information and changes the structure, which affects the accuracy and completeness. The original mentions that the "Dumpfile version is not supported" and specifies that the current version of bitcoin-wallet "only supports version 1 dumpfiles," and finally reports the dumpfile’s actual version with a full sentence.

The translation:
- Starts with "Erro:" but omits the phrase "Dumpfile version is not supported."
- Does not explicitly say the dumpfile version is unsupported.
- Changes "Got dumpfile with version %s" to just "(Versão atual: %s)" which is less precise and is ambiguous because "Versão atual" means "current version," implying version of the software or something else, not the dumpfile version.

A better translation preserving the original meaning and structure would be:

Erro: a versão do ficheiro dump não é suportada. Esta versão do bitcoin-wallet apenas suporta ficheiros dump na versão 1. Ficheiro dump recebido com versão %s

This matches the original sentence closely and includes all necessary information.
```

```
        <source>Error: Legacy wallets only support the "legacy", "p2sh-segwit", and "bech32" address types</source>
        <translation>Erro: as carteiras legadas apenas suportam os tipos de endereço "legado", "p2sh-segwit" e "bech32</translation>
    
YES
The translation is missing the closing quotation mark after "bech32" and a closing period to match the source's end of sentence. Also, "legacy" is translated as "legado" whereas the English source uses "legacy" to refer both to wallets and address types consistently; therefore, "legacy" should be kept as is for the address type (or translated consistently).

Correct translation:
Erro: as carteiras legadas apenas suportam os tipos de endereço "legacy", "p2sh-segwit" e "bech32"
```

```
        <source>File %s already exists. If you are sure this is what you want, move it out of the way first.</source>
        <translation>O ficheiro%s já existe. Se tem a certeza que é isso que quer, mova-o primeiro para fora do caminho.</translation>
    
YES  
There is a missing space between "ficheiro" and "%s". Also, the phrase "mova-o primeiro para fora do caminho" is somewhat unnatural in Portuguese. A better phrasing would be "mova-o para outro local antes" or "remova-o primeiro".  

Correct translation:  
O ficheiro %s já existe. Se tem a certeza de que é isso que quer, mova-o para outro local primeiro.
```

```
        <source>Invalid or corrupt peers.dat (%s). If you believe this is a bug, please report it to %s. As a workaround, you can move the file (%s) out of the way (rename, move, or delete) to have a new one created on the next start.</source>
        <translation>O ficheiro peers.dat (%s) está corrompido ou é inválido. Se acredita qua se trata de um "bug", por favor reporte para %s. Como solução, pode mover, alterar o nome ou eliminar (%s) para ser criado um novo na próxima inicialização</translation>
    
YES
There is a minor typo and punctuation issue in the translation:
- "qua" should be "que".
- A comma is needed after "eliminar" for better clarity.
- The phrase "por favor reporte para %s" should be "por favor reporte-o para %s" for more natural Portuguese.
- The part "para ser criado um novo na próxima inicialização" would be better as "para que um novo seja criado na próxima inicialização" for correctness and clarity.
- Also, there is no period at the end of the last sentence.

Correct translation:
O ficheiro peers.dat (%s) está corrompido ou é inválido. Se acredita que se trata de um "bug", por favor reporte-o para %s. Como solução, pode mover, alterar o nome ou eliminar (%s), para que um novo seja criado na próxima inicialização.
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Esta é a taxa de transação que poderá descartar, se o troco for menor que o remanescente a este nível</translation>
    
YES  
The translation incorrectly renders "dust" as "remanescente," which does not convey the Bitcoin-specific meaning of "dust" (very small, negligible amount). In Bitcoin context, "dust" usually remains untranslated or is translated as "pó" or "quantia mínima" to indicate the tiny amount. Also, the comma after "descartar" is unnecessary and slightly changes the sentence flow.

Correct translation:  
Esta é a taxa de transação que poderá descartar se o troco for menor que o pó neste nível
```

```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on enormous cluster of unconfirmed transactions.</source>
        <translation>Não foi possível calcular as taxas de compensação, porque os UTXOs não confirmados dependem de um enorme conjunto de transações não confirmadas..</translation>
    
YES  
The translation is mostly correct, but there is a punctuation error: there are two periods at the end of the sentence. Also, "bump fees" might be better translated as "taxas de aumento" or "taxas ajustadas" for clarity, but "taxas de compensação" is acceptable in context if consistent with terminology used elsewhere. The most important issue is the double period.

Correct translation:  
Não foi possível calcular as taxas de compensação, porque os UTXOs não confirmados dependem de um enorme conjunto de transações não confirmadas.
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is explicitly forbidden: -onion=0</source>
        <translation>As conexões de saída foram restringidas à rede Tor (-onlynet-onion) mas o proxy para alcançar a rede Tor foi explicitamente proibido: "-onion=0"</translation>
    
YES
There is a formatting error in the translation regarding the option name. The source has "-onlynet=onion" and "-onion=0" with equal signs, but the translation shows "-onlynet-onion" (a dash instead of an equal sign) and includes unnecessary quotes around "-onion=0". Also, the quotes are inconsistent with the source (which has none).

Correct translation:
As conexões de saída foram restringidas à rede Tor (-onlynet=onion), mas o proxy para alcançar a rede Tor foi explicitamente proibido: -onion=0
```

```
        <source>Rename of '%s' -&gt; '%s' failed. Cannot clean up the background chainstate leveldb directory.</source>
        <translation>Renomear de '%s' -&gt; '%s'falhou. Não é possível limpar o diretório leveldb do chainstate em segundo plano.</translation>
    
YES
There is a missing space after the second '%s' placeholder before "falhou." Also, "Renomear de" is not the best phrasing; a better option is "Renomeação de". The translation can be improved for clarity and readability.

Correct translation:
Renomeação de '%s' -> '%s' falhou. Não é possível limpar o diretório leveldb do chainstate em segundo plano.
```

```
        <source>A fatal internal error occurred, see debug.log for details: </source>
        <translation>Ocorreu um fatal internal error, consulte debug.log para obter detalhes:</translation>
    
YES
The translation contains an untranslated English phrase "fatal internal error" which should be translated into Portuguese. Also, the comma should be replaced by a period or semicolon for better flow in Portuguese.

Correct translation:
"Ocorreu um erro interno fatal, consulte o debug.log para obter detalhes:"
```

```
        <source>Pruning blockstore…</source>
        <translation>Prunando os blocos existentes…</translation>
    
YES  
The translation "Prunando os blocos existentes…" is not fully accurate or idiomatic in Portuguese. The English "Pruning blockstore…" refers to the process of pruning the blockstore (a Bitcoin data structure), not necessarily just "existing blocks." Also, "prunando" is a direct, informal adaptation of the English verb "prune," which is uncommon in Portuguese. A better translation would use "Podando" or "Limpeza do blockstore…" to convey the technical meaning more naturally.

Correct translation:  
"Podando o armazenamento de blocos…"  
or more literally:  
"Poda do armazenamento de blocos…"  
Alternatively, using "Pruning" adapted more formally:  
"Cortando o armazenamento de blocos…" (less common)

Among these, "Podando o armazenamento de blocos…" sounds natural and clear.
```

```
        <source>Rescanning…</source>
        <translation>A tornar a examinar…</translation>
    
YES
The translation is understandable but not the most natural or commonly used in Portuguese (Portugal or Brazil) in the Bitcoin context. The English "Rescanning…" usually refers to "re-examining" or "scanning again," and a more idiomatic Portuguese translation would be:

Correct translation:  
"Reanalisando…" (more common)  
or  
"Reexaminando…"  

"A tornar a examinar…" is a literal and somewhat awkward construction that does not flow naturally.
```

```
        <source>Transaction must have at least one recipient</source>
        <translation>A transação dever pelo menos um destinatário</translation>
    
YES  
The translation is incomplete and missing the verb "ter" (to have) which is required in this context. Also, "dever" should be conjugated as "deve" to agree with "A transação".  

Correct translation:  
A transação deve ter pelo menos um destinatário
```

```
        <source>Unrecognised option "%s" provided in -test=&lt;option&gt;.</source>
        <translation>Opção não reconhecida "%s" fornecido em -test=&lt;option&gt;.</translation>
    
YES
The Portuguese translation has a gender agreement error. The word "Opção" is feminine, so the past participle should be feminine as well: "fornecida" instead of "fornecido".

Correct translation:
Opção não reconhecida "%s" fornecida em -test=&lt;option&gt;.
```
</details>
