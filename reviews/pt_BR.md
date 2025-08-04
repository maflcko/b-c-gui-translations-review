# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>pt_BR</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bpt_BR%5D%20low%20quality)


```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>A palavra passe inserida para a de-criptografia da carteira é incorreta . Ela contém um caractere nulo (ou seja - um byte zero). Se a palavra passe foi configurada em uma versão anterior deste software antes da versão 25.0, por favor tente novamente apenas com os caracteres maiúsculos — mas não incluindo — o primeiro caractere nulo. Se for bem-sucedido, defina uma nova senha para evitar esse problema no futuro.</translation>
    
YES: The translation incorrectly states "caracteres maiúsculos" (uppercase characters) when the source text refers to "characters up to — but not including — the first null character". There is no mention of case sensitivity in the source text.

The word "de-criptografia" should be "decifragem" or "descriptografia".

The phrase "palavra passe" is acceptable but "senha" is more common.

A corret translation would be: "A senha inserida para a descriptografia da carteira está incorreta. Ela contém um caractere nulo (ou seja - um byte zero). Se a senha foi configurada em uma versão deste software anterior à 25.0, por favor tente novamente apenas com os caracteres até — mas não incluindo — o primeiro caractere nulo. Se for bem-sucedido, defina uma nova senha para evitar esse problema no futuro."
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>A senha antiga inserida para a de-criptografia da carteira está incorreta. Ele contém um caractere nulo (ou seja, um byte zero). Se a senha foi definida com uma versão deste software anterior a 25.0, tente novamente apenas com os caracteres maiúsculo — mas não incluindo — o primeiro caractere nulo.</translation>
    
YES: The translation incorrectly translates "uppercase" to "maiúsculo". It should be "até" to match the source "up to". The phrase "only the characters up to — but not including — the first null character" is translated as "apenas com os caracteres maiúsculo — mas não incluindo — o primeiro caractere nulo". The correct translation should be: "A senha antiga inserida para a descriptografia da carteira está incorreta. Ela contém um caractere nulo (ou seja, um byte zero). Se a senha foi definida com uma versão deste software anterior a 25.0, tente novamente apenas com os caracteres até — mas não incluindo — o primeiro caractere nulo."
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Carregar</translation>
    
YES, The translation is incomplete and misleading. It only translates "Load" and omits the rest of the source text "Partially Signed Bitcoin Transaction".

Correct translation: Carregar Transação Bitcoin Parcialmente Assinada
```

```
        <source>Open wallet warning</source>
        <translation>Abrir carteira alerta</translation>
    
YES, The translation is inaccurate. "Open wallet warning" should be translated to "Aviso de abertura de carteira" or "Alerta ao abrir carteira".
Aviso de abertura de carteira
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>Quando clicar em OK, %1 iniciará o download e irá processar a cadeia de blocos completa %4 (%2 GB) iniciando com as mais recentes transações em %3 enquanto %4 é processado. </translation>
    
YES, The translation incorrectly uses "mais recentes transações" (most recent transactions) instead of "earliest transactions". The phrase "enquanto %4 é processado" (while %4 is processed) is also vague and doesn't accurately convey the meaning of the original phrase "when %4 initially launched".

Correct translation: Quando clicar em OK, %1 iniciará o download e irá processar a cadeia de blocos completa %4 (%2 GB) iniciando com as transações mais antigas em %3 quando %4 foi lançado inicialmente.
```

```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>Tentar gastar bitcoins que estão em transações ainda não exibidas, não vão ser aceitos pela rede.</translation>
    
YES. The sentence structure in the Portuguese translation is awkward and unclear. It should be more direct.

Tentar gastar bitcoins afetados por transações ainda não exibidas não será aceito pela rede.
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>Caminho completo para %1 um script compatível com Bitcoin Core (exemplo: C: \ Downloads \ hwi.exe ou /Users/you/Downloads/hwi.py). Cuidado: um malware pode roubar suas moedas!</translation>
    
YES: The translation contains extraneous spacing around the format specifier.
Caminho completo para um script compatível com Bitcoin Core (%1) (exemplo: C:\Downloads\hwi.exe ou /Users/you/Downloads/hwi.py). Cuidado: um malware pode roubar suas moedas!
```

```
        <source>Open the %1 configuration file from the working directory.</source>
        <translation>Abrir o arquivo de configuração %1 apartir do diretório trabalho.</translation>
    
YES
The word "apartir" should be "a partir".
Abrir o arquivo de configuração %1 a partir do diretório de trabalho.
```

```
        <source>Prune block storage to</source>
        <translation>Fazer Prune da memória de blocos para</translation>
    
YES, The translation uses a verb phrase in Portuguese that is not commonly used in this context. The term "Prune" is often kept in English in technical contexts or translated more directly.

Correct translation: "Poda o armazenamento de blocos para"
```

```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>Mostra a quantia com a taxa já subtraída.</translation>
    
YES - The translation is inaccurate and does not convey the meaning of the original English text. The English text refers to a setting that determines whether to *subtract* the fee from the amount by default. The Portuguese translation, "Mostra a quantia com a taxa já subtraída" (Shows the amount with the fee already subtracted), describes the *result* of that setting, not the setting itself. A more accurate translation would be: "Definir se a taxa deve ser subtraída do valor como padrão ou não."
```

```
        <source>An optional label to associate with the new receiving address (used by you to identify an invoice).  It is also attached to the payment request.</source>
        <translation>Um rótulo opcional para associar ao novo endereço de recebimento (usado por você para identificar uma solicitação de pagamento). Que também será adicionado a solicitação de pagamento.</translation>
    
YES: The phrase "Que também será adicionado a solicitação de pagamento." is redundant and grammatically awkward. It reiterates information already provided in the first part of the sentence.

Correct translation: Um rótulo opcional para associar ao novo endereço de recebimento (usado por você para identificar uma fatura). Ele também será anexado à solicitação de pagamento.
```

```
        <source>Bech32m (BIP-350) is an upgrade to Bech32, wallet support is still limited.</source>
        <translation>Bech32m (BIP-350) é uma atualização para o Bech32,</translation>
    
YES - The translation is incomplete. The phrase "wallet support is still limited" is missing.

Correct translation: Bech32m (BIP-350) é uma atualização para o Bech32, o suporte da carteira ainda é limitado.
```

```
        <source>%1 from wallet '%2'</source>
        <translation>%1 da pasta "%2</translation>
    
YES: The translation is missing the closing quotation mark for the wallet name.
%1 da pasta "%2"
```

```
        <source>The recipient address is not valid. Please recheck.</source>
        <translation>Endereço de envio inváido. Favor checar.</translation>
    
YES: The translation is grammatically incorrect and omits a word. The source states "recipient address", but the translation uses "endereço de envio" which means "sending address". Additionally, "inváido" is a misspelling of "inválido".

The correct translation should be: "O endereço do destinatário é inválido. Por favor, verifique novamente."
```

```
        <source>The address you selected for change is not part of this wallet. Any or all funds in your wallet may be sent to this address. Are you sure?</source>
        <translation>O endereço selecionado para o troco não pertence a esta carteira. Alguns ou todos os fundos da sua carteira modem ser mandados para esse endereço. Tem certeza?</translation>
    
YES, erroneous content. The word "modem" is incorrect and should be "podem".
O endereço selecionado para o troco não pertence a esta carteira. Alguns ou todos os fundos da sua carteira podem ser mandados para esse endereço. Tem certeza?
```

```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Coloque o endereço do autor, a mensagem (certifique-se de copiar toda a mensagem, incluindo quebras de linha, espaços, tabulações, etc.) e a assinatura abaixo para verificar a mensagem. Cuidado para não compreender mais da assinatura do que está na mensagem assinada de fato, para evitar ser enganado por um ataque man-in-the-middle. Note que isso somente prova que o signatário recebe com este endereço, não pode provar que é o remetente de nenhuma transação!</translation>
    
YES: The translation incorrectly translates "receiver's" to "autor" (author) instead of "destinatário" (receiver). It also uses "com este endereço" which is a bit awkward and could be improved.
Corrected translation: Coloque o endereço do destinatário, a mensagem (certifique-se de copiar toda a mensagem, incluindo quebras de linha, espaços, tabulações, etc.) e a assinatura abaixo para verificar a mensagem. Cuidado para não interpretar mais da assinatura do que o que está na mensagem assinada em si, para evitar ser enganado por um ataque man-in-the-middle. Note que isso apenas prova que a parte que assina recebe com o endereço, não pode provar a remessa de nenhuma transação!
```

```
        <source>The signature did not match the message digest.</source>
        <translation>A assinatura não corresponde a mensagem.</translation>
    
YES. The translation is missing the word "digest" from the original English sentence.

A assinatura não corresponde ao resumo da mensagem.
```

```
        <source>%s request to listen on port %u. This port is considered "bad" and thus it is unlikely that any peer will connect to it. See doc/p2p-bad-ports.md for details and a full list.</source>
        <translation>1%s solicita para escutar na porta 2%u. Esta porta é considerada "ruim" e, portanto, é improvável que qualquer ponto se conecte-se a ela. Consulte doc/p2p-bad-ports.md para obter detalhes e uma lista completa.</translation>
    
YES - The translation incorrectly inserts "1" and "2" before the format specifiers.
%s solicita para escutar na porta %u. Esta porta é considerada "ruim" e, portanto, é improvável que qualquer ponto se conecte a ela. Consulte doc/p2p-bad-ports.md para obter detalhes e uma lista completa.
```

```
        <source>Disk space for %s may not accommodate the block files. Approximately %u GB of data will be stored in this directory.</source>
        <translation>O espaço em disco para 1%s pode não acomodar os arquivos de bloco. Aproximadamente 2%u GB de dados serão armazenados neste diretório.</translation>
    
YES: The format specifiers %s and %u are incorrectly translated. They should be %s and %u respectively.
O espaço em disco para %s pode não acomodar os arquivos de bloco. Aproximadamente %u GB de dados serão armazenados neste diretório.
```

```
        <source>Error: Unable to produce descriptors for this legacy wallet. Make sure to provide the wallet's passphrase if it is encrypted.</source>
        <translation>Erro: Não foi possível produzir descritores para esta carteira antiga. Certifique-se que a carteira foi desbloqueada antes</translation>
    
YES: The translation is inaccurate and doesn't convey the original meaning correctly. The original text advises to provide the wallet's passphrase if it's encrypted, while the translation states that the wallet should be unlocked beforehand, which is not the same.

Correct translation: Erro: Não foi possível produzir descritores para esta carteira antiga. Certifique-se de fornecer a senha da carteira caso ela esteja criptografada.
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>Mais de um endereço onion associado é fornecido. Usando %s para automaticamento criar serviço onion Tor.</translation>
    
YES, The translation contains a grammatical error. The word "automaticamento" should be "automaticamente".

More than one onion bind address is provided. Using %s for the automatically created Tor onion service.
Mais de um endereço onion associado é fornecido. Usando %s para criar automaticamente o serviço onion Tor.
```

```
        <source>Witness data for blocks after height %d requires validation. Please restart with -reindex.</source>
        <translation>Testemunhar dados de blocos após 1%d requer validação. Por favor reinicie com -reindex.</translation>
    
YES: The "%d" format specifier was incorrectly translated to "1%d".
Correct translation: Testemunhar dados de blocos após %d requer validação. Por favor reinicie com -reindex.
```

```
        <source>Rename of '%s' -&gt; '%s' failed. Cannot clean up the background chainstate leveldb directory.</source>
        <translation>Renomear de '%s' -&gt; '%s'falhou. Não é possível limpar o diretório leveldb do chainstate em segundo plano.</translation>
    
YES: The translation has a spacing error where " '%s'falhou" should be " '%s' falhou".
Renomear de '%s' -> '%s' falhou. Não é possível limpar o diretório leveldb do chainstate em segundo plano.
```

```
        <source>A fatal internal error occurred, see debug.log for details: </source>
        <translation>Ocorreu um fatal internal error, consulte debug.log para obter detalhes:</translation>
    
YES, The word "internal" was not translated.
Ocorreu um erro interno fatal, consulte debug.log para obter detalhes:
```

```
        <source>Cannot write to directory '%s'; check permissions.</source>
        <translation>Não é possível escrever no diretório '%s'; verifique aspermissões.</translation>
    
YES - There is a missing space between "verifique" and "aspermissões". The correct translation is "Não é possível escrever no diretório '%s'; verifique as permissões."
```

```
        <source>Transaction change output index out of range</source>
        <translation>Endereço de troco da transação fora da faixa</translation>
    
YES, The translation is problematic because "Endereço de troco da transação fora da faixa" translates to "Transaction change address out of range". The source text specifies "output index", not "address".

The correct translation should be:
Endereço de troco da transação fora do índice de saída
```

```
        <source>Unable to find UTXO for external input</source>
        <translation>Impossível localizar e entrada externa UTXO</translation>
    
YES - The word order in the translation is unnatural for Portuguese. The correct translation should be "Impossível localizar UTXO para entrada externa".
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>falha na criação do ficheiro da pasta: %s</translation>
    
YES - The translation uses "ficheiro da pasta" which is not the standard Portuguese for "wallet file". The correct term in Brazilian Portuguese would be "arquivo da carteira".
falha na criação do arquivo da carteira: %s
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Erro: Não foi possível adicionar tx %s de vigilância à pasta de vigilância</translation>
    
YES - The translation incorrectly uses "pasta de vigilância" for "watchonly wallet". In the context of Bitcoin, a "watchonly wallet" refers to a wallet that can track addresses without having the private keys to spend from them. A more appropriate translation would be "carteira de somente vigilância" or "carteira de monitoramento".

Correct translation: Erro: Não foi possível adicionar tx %s de somente vigilância à carteira de somente vigilância
```

```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Não estão disponíveis descritores de ficheiros suficientes. %d disponíveis, %d necessários.</translation>
    
YES - The translation uses "ficheiros" which is Portuguese from Portugal, not Brazilian Portuguese. The correct translation should use "arquivos".
Não estão disponíveis descritores de arquivos suficientes. %d disponíveis, %d necessários.
```
</details>
