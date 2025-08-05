# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>pt_BR</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bpt_BR%5D%20low%20quality)


```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>A palavra passe inserida para a de-criptografia da carteira é incorreta . Ela contém um caractere nulo (ou seja - um byte zero). Se a palavra passe foi configurada em uma versão anterior deste software antes da versão 25.0, por favor tente novamente apenas com os caracteres maiúsculos — mas não incluindo — o primeiro caractere nulo. Se for bem-sucedido, defina uma nova senha para evitar esse problema no futuro.</translation>
    
YES  
There are some errors and inconsistencies in the translation:

1. "de-criptografia" should be "de criptografia" (no hyphen, as the correct term is "descriptografia" or "de criptografia" depending on context, but here "de criptografia" is better).
2. There is an unnecessary space before the period in "incorreta ."
3. The translation says "apenas com os caracteres maiúsculos" ("only with uppercase characters"), which is not in the original. The original means "only the characters up to — but not including — the first null character." The word "maiúsculos" ("uppercase") is incorrect here.
4. The word "senha" is used instead of "palavra passe" to translate "passphrase." The original consistently uses "palavra passe," so it is better to keep it consistent.
5. The whole sentence about "Se for bem-sucedido, defina uma nova senha" doesn't specify who should do the action; better to follow the original wording: "If this is successful, please set a new passphrase..."
6. The dash "—" usage is correct, but spacing around it should be consistent and normally spaces around those dashes in Portuguese should be thin spaces or normal spaces, but this is minor and not critical.
7. "por favor tente novamente apenas com os caracteres maiúsculos" doesn't capture the meaning. It should be "por favor, tente novamente utilizando somente os caracteres até — mas não incluindo — o primeiro caractere nulo."

Correct translation:

A palavra-passe inserida para a descriptografia da carteira está incorreta. Ela contém um caractere nulo (ou seja, um byte zero). Se a palavra-passe foi configurada com uma versão deste software anterior à 25.0, por favor, tente novamente utilizando somente os caracteres até — mas não incluindo — o primeiro caractere nulo. Se isso for bem-sucedido, defina uma nova palavra-passe para evitar esse problema no futuro.

Note: "palavra-passe" with a hyphen is the most usual form in Brazilian Portuguese for "passphrase" in security context.

Final replacement:

<translation>A palavra-passe inserida para a descriptografia da carteira está incorreta. Ela contém um caractere nulo (ou seja, um byte zero). Se a palavra-passe foi configurada com uma versão deste software anterior à 25.0, por favor, tente novamente utilizando somente os caracteres até — mas não incluindo — o primeiro caractere nulo. Se isso for bem-sucedido, defina uma nova palavra-passe para evitar esse problema no futuro.</translation>
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>A senha antiga inserida para a de-criptografia da carteira está incorreta. Ele contém um caractere nulo (ou seja, um byte zero). Se a senha foi definida com uma versão deste software anterior a 25.0, tente novamente apenas com os caracteres maiúsculo — mas não incluindo — o primeiro caractere nulo.</translation>
    
YES  
There are errors in the translation:  
1. "Ele contém um caractere nulo" uses the masculine pronoun "Ele" (he/it masculine), but it should refer to "senha" (password), which is feminine ("senha" is feminine in Portuguese). So it should be "Ela contém um caractere nulo".  
2. The phrase "apenas com os caracteres maiúsculo — mas não incluindo — o primeiro caractere nulo" is incorrect. The source says "only the characters up to — but not including — the first null character." The word "maiúsculo" means "uppercase," which is unrelated and a mistranslation. The correct phrase should be "apenas com os caracteres até — mas sem incluir — o primeiro caractere nulo."  
3. The translation of "decryption" as "de-criptografia" is understandable but uncommon in Brazilian Portuguese; "descriptografia" or "decodificação" is preferred. "Descriptografia" is most common in tech contexts.  

Correct translation:  
A senha antiga inserida para a descriptografia da carteira está incorreta. Ela contém um caractere nulo (ou seja, um byte zero). Se a senha foi definida com uma versão deste software anterior à 25.0, tente novamente apenas com os caracteres até — mas sem incluir — o primeiro caractere nulo.
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Carregar</translation>
    
YES  
The translation is incomplete and does not convey the full meaning of the English source. "Load Partially Signed Bitcoin Transaction" should indicate loading a partially signed Bitcoin transaction, not just "Carregar" (which means "Load" in a very general sense).  

Correct translation:  
Carregar Transação Bitcoin Parcialmente Assinada
```

```
        <source>Open wallet warning</source>
        <translation>Abrir carteira alerta</translation>
    
YES  
The translation is not natural and sounds awkward in Portuguese. A more appropriate translation would be:  
"Aviso ao abrir carteira"
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>Quando clicar em OK, %1 iniciará o download e irá processar a cadeia de blocos completa %4 (%2 GB) iniciando com as mais recentes transações em %3 enquanto %4 é processado. </translation>
    
YES  
The translation introduces inaccuracies and changes the meaning of the original sentence. For example, "as mais recentes transações" means "the most recent transactions," while the source says "starting with the earliest transactions." Also, the source says "starting with the earliest transactions in %3 when %4 initially launched," but the translation says "enquanto %4 é processado" ("while %4 is processed"), which is incorrect.

A more accurate translation would be:  
"Quando clicar em OK, %1 iniciará o download e processará a cadeia de blocos completa %4 (%2 GB), começando pelas transações mais antigas em %3, quando %4 foi lançado inicialmente."
```

```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>Tentar gastar bitcoins que estão em transações ainda não exibidas, não vão ser aceitos pela rede.</translation>
    
YES  
The translation contains a subject-verb agreement error and an unnecessary comma before the conjunction. The subject "Tentar gastar bitcoins" (Trying to spend bitcoins) is singular, so it should be followed by "não vai ser aceito" (singular), not "vão ser aceitos" (plural). Also, the comma after "exibidas" is not needed.

Correct translation:  
Tentar gastar bitcoins que estão em transações ainda não exibidas não vai ser aceito pela rede.
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>Caminho completo para %1 um script compatível com Bitcoin Core (exemplo: C: \ Downloads \ hwi.exe ou /Users/you/Downloads/hwi.py). Cuidado: um malware pode roubar suas moedas!</translation>
    
YES
There is a word order issue and unnecessary spacing in the translation. The phrase "%1 um script compatível com Bitcoin Core" incorrectly places "%1" before "um script". Also, there is an extra space after "C:" and before the backslashes in the Windows path.

Correct translation:
Caminho completo para um script compatível com %1 (exemplo: C:\Downloads\hwi.exe ou /Users/you/Downloads/hwi.py). Cuidado: malware pode roubar suas moedas!
```

```
        <source>Open the %1 configuration file from the working directory.</source>
        <translation>Abrir o arquivo de configuração %1 apartir do diretório trabalho.</translation>
    
YES  
There is a typographical error in the translation: "apartir" should be "a partir". Also, "diretório trabalho" is missing the preposition "de" before "trabalho". The corrected phrase is "diretório de trabalho."  

Correct translation:  
Abrir o arquivo de configuração %1 a partir do diretório de trabalho.
```

```
        <source>Prune block storage to</source>
        <translation>Fazer Prune da memória de blocos para</translation>
    
YES  
The translation is partially incorrect and inconsistent. The English phrase "Prune block storage to" refers to reducing or trimming the blockchain data stored to a specified size, commonly called "prune" in technical contexts. The word "Prune" should be translated or adapted consistently rather than left in English. Also, "memória de blocos" ("block memory") is not an accurate or common term for "block storage." A better term is "armazenamento de blocos."

Correct translation:  
"Reduzir o armazenamento de blocos para"  
or  
"Poda do armazenamento de blocos para" (if you want to retain the technical term "prune" as "poda").
```

```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>Mostra a quantia com a taxa já subtraída.</translation>
    
YES  
The translation does not accurately convey the meaning of the source text. The source discusses whether to set "subtract fee from amount" as the default behavior (a Boolean choice), but the translation says "Shows the amount with the fee already subtracted," which is more of a description of a display behavior, not a setting toggle.

Correct translation:  
"Definir subtrair taxa do valor como padrão ou não."
```

```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>Bem vindo ao %1 console de RPC.
Utilize as setas para cima e para baixo para navegar no histórico, e %2 para limpar a tela.
Utilize %3 e %4 para aumentar ou diminuir a tamanho da fonte.
Digite %5 para ver os comandos disponíveis.
Para mais informações sobre a utilização desse console. digite %6.

%7 AVISO: Scammers estão ativamente influenciando usuário a digitarem comandos aqui, roubando os conteúdos de suas carteiras. Não use este terminal sem pleno conhecimento dos efeitos de cada comando.%8</translation>
    
YES
There are some grammatical and phrasing issues in the translation:

1. "Bem vindo" should be hyphenated: "Bem-vindo".
2. The phrase "aumentar ou diminuir a tamanho da fonte" is incorrect; it should be "aumentar ou diminuir o tamanho da fonte".
3. The sentence "Para mais informações sobre a utilização desse console. digite %6." is a fragment with a period instead of a comma; it should be "Para mais informações sobre a utilização desse console, digite %6."
4. The word "Scammers" should be translated to Portuguese as "Golpistas" or "Criminosos". Leaving it in English is inappropriate.
5. The phrase "estão ativamente influenciando usuário a digitarem comandos aqui" is awkward. A better phrasing: "Estão ativamente enganando usuários para digitar comandos aqui".
6. Remove the space after %7 to keep consistent with the note about style tags being attached without spaces.

Corrected translation:

Bem-vindo ao %1 console de RPC.  
Utilize as setas para cima e para baixo para navegar no histórico, e %2 para limpar a tela.  
Utilize %3 e %4 para aumentar ou diminuir o tamanho da fonte.  
Digite %5 para ver os comandos disponíveis.  
Para mais informações sobre a utilização desse console, digite %6.

%7AVISO: Golpistas estão ativamente enganando usuários para digitar comandos aqui, roubando os conteúdos de suas carteiras. Não use este terminal sem pleno conhecimento dos efeitos de cada comando.%8
```

```
        <source>An optional label to associate with the new receiving address (used by you to identify an invoice).  It is also attached to the payment request.</source>
        <translation>Um rótulo opcional para associar ao novo endereço de recebimento (usado por você para identificar uma solicitação de pagamento). Que também será adicionado a solicitação de pagamento.</translation>
    
YES  
There's a grammatical issue with the second sentence fragment "Que também será adicionado a solicitação de pagamento." It should be connected properly and use the correct form of the verb to avoid a sentence fragment.

Correct translation:  
Um rótulo opcional para associar ao novo endereço de recebimento (usado por você para identificar uma solicitação de pagamento). Ele também é anexado à solicitação de pagamento.
```

```
        <source>Bech32m (BIP-350) is an upgrade to Bech32, wallet support is still limited.</source>
        <translation>Bech32m (BIP-350) é uma atualização para o Bech32,</translation>
    
YES  
The translation is incomplete and omits the second part of the sentence "wallet support is still limited." This makes the translation inaccurate and potentially misleading.

Correct translation:  
Bech32m (BIP-350) é uma atualização do Bech32, o suporte em carteiras ainda é limitado.
```

```
        <source>%1 from wallet '%2'</source>
        <translation>%1 da pasta "%2</translation>
    
YES  
The translation is incomplete and missing the closing quotation mark after "%2". Also, "pasta" literally means "folder" or "folder on a computer," but in the Bitcoin context, "wallet" should be translated as "carteira".

Correct translation:  
%1 da carteira "%2"
```

```
        <source>The recipient address is not valid. Please recheck.</source>
        <translation>Endereço de envio inváido. Favor checar.</translation>
    
YES  
The translation has a typo ("inváido" should be "inválido") and uses "Endereço de envio" ("sending address") instead of "Endereço do destinatário" or "Endereço do recebedor" which better matches "recipient address." Also, "Favor checar" is informal; "Por favor, verifique" is more standard and polite. The original message is more formal and clear.

Correct translation:  
"O endereço do destinatário não é válido. Por favor, verifique."
```

```
        <source>The address you selected for change is not part of this wallet. Any or all funds in your wallet may be sent to this address. Are you sure?</source>
        <translation>O endereço selecionado para o troco não pertence a esta carteira. Alguns ou todos os fundos da sua carteira modem ser mandados para esse endereço. Tem certeza?</translation>
    
YES  
There is a typo: "modem" should be "podem". Also, "mandados" is less formal and less appropriate in this context compared to "enviados". The phrase "para o troco" is a correct translation of "for change" referring to Bitcoin change.

Correct translation:  
O endereço selecionado para o troco não pertence a esta carteira. Alguns ou todos os fundos da sua carteira podem ser enviados para esse endereço. Tem certeza?
```

```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Coloque o endereço do autor, a mensagem (certifique-se de copiar toda a mensagem, incluindo quebras de linha, espaços, tabulações, etc.) e a assinatura abaixo para verificar a mensagem. Cuidado para não compreender mais da assinatura do que está na mensagem assinada de fato, para evitar ser enganado por um ataque man-in-the-middle. Note que isso somente prova que o signatário recebe com este endereço, não pode provar que é o remetente de nenhuma transação!</translation>
    
YES  
The translation has an error in the important technical detail: "Enter the receiver's address" was translated as "Coloque o endereço do autor", which means "Enter the author's address" or "creator's address," which is incorrect in this context. It should be "endereço do destinatário" to reflect "receiver's address."

Also, the phrase "certifique-se de copiar toda a mensagem, incluindo quebras de linha, espaços, tabulações, etc." translates as "make sure to copy the entire message, including line breaks, spaces, tabs, etc." which is acceptable, but the source emphasizes "ensure you copy line breaks, spaces, tabs, etc. exactly" — adding the word "exatamente" to reflect exactness would be better.

Another minor point: "signatário" is a good technical word for "signing party," and the rest is mostly fine.

Correct translation:  
Coloque o endereço do destinatário, a mensagem (certifique-se de copiar exatamente quebras de linha, espaços, tabulações, etc.) e a assinatura abaixo para verificar a mensagem. Cuidado para não ler mais na assinatura do que está na própria mensagem assinada, para evitar ser enganado por um ataque man-in-the-middle. Note que isso somente prova que a parte que assina recebe com este endereço, não pode provar que é o remetente de nenhuma transação!
```

```
        <source>The signature did not match the message digest.</source>
        <translation>A assinatura não corresponde a mensagem.</translation>
    
YES  
The translation is inaccurate. The English text refers specifically to "message digest," which is a technical term in cryptography meaning a hash of the message. The translation "mensagem" alone is too general and omits the concept of "digest." Also, the phrase "não corresponde a mensagem" is missing a preposition; it should be "não corresponde à mensagem."  

A better translation would be:  
"A assinatura não corresponde ao resumo da mensagem."  
or more formally and in line with technical context:  
"A assinatura não corresponde ao resumo (digest) da mensagem."
```

```
        <source>%s request to listen on port %u. This port is considered "bad" and thus it is unlikely that any peer will connect to it. See doc/p2p-bad-ports.md for details and a full list.</source>
        <translation>1%s solicita para escutar na porta 2%u. Esta porta é considerada "ruim" e, portanto, é improvável que qualquer ponto se conecte-se a ela. Consulte doc/p2p-bad-ports.md para obter detalhes e uma lista completa.</translation>
    
YES
The format specifiers %s and %u should appear in the same order and without additional characters. The translation incorrectly adds "1" before %s and "2" before %u, which is wrong. Also, "ponto" is not the best translation for "peer" in a Bitcoin context; "par" or "nó" would be better. Additionally, "conecte-se" is reflexive and should not be hyphenated as "conecte-se" after "qualquer ponto"—the verb form should be "conecte" without reflexive pronoun.

Correct translation:
%s solicita para escutar na porta %u. Esta porta é considerada "ruim" e, portanto, é improvável que qualquer par se conecte a ela. Consulte doc/p2p-bad-ports.md para obter detalhes e uma lista completa.
```

```
        <source>Disk space for %s may not accommodate the block files. Approximately %u GB of data will be stored in this directory.</source>
        <translation>O espaço em disco para 1%s pode não acomodar os arquivos de bloco. Aproximadamente 2%u GB de dados serão armazenados neste diretório.</translation>
    
YES  
The format specifiers "%s" and "%u" are incorrectly changed to "1%s" and "2%u", which is wrong. They should be preserved exactly as in the source.  

Correct translation:  
O espaço em disco para %s pode não acomodar os arquivos de bloco. Aproximadamente %u GB de dados serão armazenados neste diretório.
```

```
        <source>Error: Unable to produce descriptors for this legacy wallet. Make sure to provide the wallet's passphrase if it is encrypted.</source>
        <translation>Erro: Não foi possível produzir descritores para esta carteira antiga. Certifique-se que a carteira foi desbloqueada antes</translation>
    
YES  
The translation changes the meaning of the source text. The source says to "make sure to provide the wallet's passphrase if it is encrypted," which is a conditional instruction about providing the passphrase. The translation says "Certifique-se que a carteira foi desbloqueada antes" ("Make sure the wallet was unlocked before"), which does not mention providing the passphrase and changes the nuance.

A better, more accurate translation would be:  
"Erro: Não foi possível produzir descritores para esta carteira legacy. Certifique-se de fornecer a senha da carteira se ela estiver criptografada."
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>Mais de um endereço onion associado é fornecido. Usando %s para automaticamento criar serviço onion Tor.</translation>
    
YES  
The translation has a few issues:  
1. "automaticamento" is a typo; the correct word is "automaticamente".  
2. The phrase "para automaticamento criar serviço onion Tor" is awkward and not grammatically smooth. It misses the definite article and verb form for clarity.  
3. The original implies "Using %s for the automatically created Tor onion service." The translation should reflect that the service was already created automatically, not that it will be created.  

Correct translation:  
"Mais de um endereço onion associado foi fornecido. Usando %s para o serviço onion Tor criado automaticamente."
```

```
        <source>Witness data for blocks after height %d requires validation. Please restart with -reindex.</source>
        <translation>Testemunhar dados de blocos após 1%d requer validação. Por favor reinicie com -reindex.</translation>
    
YES  
The translation incorrectly adds "1" before the format specifier "%d" ("1%d") which does not exist in the source and is erroneous. Also, the phrase "Testemunhar dados de blocos" is awkward and misleading. "Witness data" in the context of Bitcoin should be translated as "Dados de testemunha".

Correct translation:  
Dados de testemunha para blocos após a altura %d requerem validação. Por favor, reinicie com -reindex.
```

```
        <source>Rename of '%s' -&gt; '%s' failed. Cannot clean up the background chainstate leveldb directory.</source>
        <translation>Renomear de '%s' -&gt; '%s'falhou. Não é possível limpar o diretório leveldb do chainstate em segundo plano.</translation>
    
YES  
There is a missing space after the second '%s' placeholder before "falhou." and also a slight improvement can be made for naturalness and clarity in Portuguese.

Correct translation:  
Renomear de '%s' -> '%s' falhou. Não é possível limpar o diretório leveldb do chainstate em segundo plano.
```

```
        <source>A fatal internal error occurred, see debug.log for details: </source>
        <translation>Ocorreu um fatal internal error, consulte debug.log para obter detalhes:</translation>
    
YES  
The translation incorrectly mixes English and Portuguese ("fatal internal error" should be fully translated). The phrase "fatal internal error" should be translated as "erro interno fatal". Also, "consulte" is correct, but the original has a space before the colon which is not needed in Portuguese. The corrected translation preserves formatting and is fluent Portuguese:

Correct translation:  
Ocorreu um erro interno fatal, consulte debug.log para obter detalhes:
```

```
        <source>Cannot write to directory '%s'; check permissions.</source>
        <translation>Não é possível escrever no diretório '%s'; verifique aspermissões.</translation>
    
YES  
There is a whitespace issue: the phrase "as permissões" is written as "aspermissões" without space.

Correct translation:  
Não é possível escrever no diretório '%s'; verifique as permissões.
```

```
        <source>Transaction change output index out of range</source>
        <translation>Endereço de troco da transação fora da faixa</translation>
    
YES  
The translation is inaccurate. The source phrase refers to an "output index" related to transaction change, not an "address." The correct translation should preserve "output index" and not replace it with "endereço" (address).  
  
Correct translation:  
Índice de saída de troco da transação fora do intervalo
```

```
        <source>Unable to find UTXO for external input</source>
        <translation>Impossível localizar e entrada externa UTXO</translation>
    
YES
The translation contains a grammatical error: "e entrada externa UTXO" is incorrect. The conjunction "e" (and) is wrong here; it should be "a entrada externa UTXO" (the external input UTXO). Also, the word order can be improved for clarity.

Correct translation:
Impossível localizar UTXO para entrada externa
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>falha na criação do ficheiro da pasta: %s</translation>
    
YES  
The translation uses "ficheiro da pasta" which is incorrect and unnatural in Brazilian Portuguese. "Ficheiro" is more common in European Portuguese, and "pasta" means folder, not wallet. The correct term in the Bitcoin context should be "arquivo da carteira" or simply "arquivo da wallet" (using "carteira" for wallet). Also, the phrase should start with a capital letter.

Correct translation:  
Falha na criação do arquivo da carteira: %s
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Erro: Não foi possível adicionar tx %s de vigilância à pasta de vigilância</translation>
    
YES  
The translation is inaccurate and uses incorrect terminology for the Bitcoin context. "tx" should be retained or translated as "transação" for clarity, and "watchonly wallet" should be translated as "carteira somente observação" or "carteira apenas para visualização." The phrase "pasta de vigilância" is incorrect since "pasta" means folder, not wallet.

Correct translation:  
Erro: Não foi possível adicionar a transação somente observação %s à carteira somente observação
```
</details>
