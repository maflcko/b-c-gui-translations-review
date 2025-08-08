# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>pt_BR</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bpt_BR%5D%20low%20quality)


<!-- cache_translation_check_pt_BR_96ab2f62047a9b2dbccbaf589a52e486a1162c6dd904e96c7058080faa4be5b8 -->
```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>A palavra passe inserida para a de-criptografia da carteira é incorreta . Ela contém um caractere nulo (ou seja - um byte zero). Se a palavra passe foi configurada em uma versão anterior deste software antes da versão 25.0, por favor tente novamente apenas com os caracteres maiúsculos — mas não incluindo — o primeiro caractere nulo. Se for bem-sucedido, defina uma nova senha para evitar esse problema no futuro.</translation>
    
ERR  
There are several issues:

1. The translation for "passphrase" is rendered as "palavra passe", which is incorrect and uncommon in Brazilian Portuguese. The established term is "senha" or "frase secreta" (better for 'passphrase').
2. The phrase "apenas com os caracteres maiúsculos" is a mistranslation of "only the characters up to" (should be "apenas com os caracteres até", not "maiúsculos" which means "uppercase").
3. There is redundant spacing before the period after "incorreta".
4. For clarity, "de-criptografia" should be "descriptografia".  
5. "Se a palavra passe foi configurada em uma versão anterior deste software antes da versão 25.0" is unnecessarily redundant, and does not reflect the English "with a version of this software prior to 25.0".
6. For "define uma nova senha", "senha" (password) is more common, but since "passphrase" was used, "frase secreta" is the best translation.

Correct translation:
A frase secreta inserida para a descriptografia da carteira está incorreta. Ela contém um caractere nulo (ou seja, um byte zero). Se a frase secreta foi definida em uma versão deste software anterior à 25.0, tente novamente usando apenas os caracteres até — mas não incluindo — o primeiro caractere nulo. Se for bem-sucedido, defina uma nova frase secreta para evitar esse problema no futuro.
```

<!-- cache_translation_check_pt_BR_2093b786514e0fdc7be7386cce2794d370fedb27afed5aa47fe021e7905d4d79 -->
```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>A senha antiga inserida para a de-criptografia da carteira está incorreta. Ele contém um caractere nulo (ou seja, um byte zero). Se a senha foi definida com uma versão deste software anterior a 25.0, tente novamente apenas com os caracteres maiúsculo — mas não incluindo — o primeiro caractere nulo.</translation>
    
ERR
There are accuracy problems in the translation:

1. "de-criptografia" is not the standard; the usual form in Brazilian Portuguese is "descriptografia".
2. "Ele contém um caractere nulo" uses the masculine "Ele", while the correct pronoun for "senha" (password/passphrase) is feminine in Portuguese: "Ela contém...".
3. "com os caracteres maiúsculo — mas não incluindo — o primeiro caractere nulo" is an incorrect translation of "with only the characters up to — but not including — the first null character." The mention of "maiúsculo" (uppercase) doesn't appear in the source and is erroneous.
4. Whitespace and punctuation are appropriate, but the overall message changes the meaning.

Correct translation:
A senha antiga inserida para a descriptografia da carteira está incorreta. Ela contém um caractere nulo (ou seja, um byte zero). Se a senha foi definida com uma versão deste software anterior à 25.0, tente novamente utilizando apenas os caracteres até — mas sem incluir — o primeiro caractere nulo.
```

<!-- cache_translation_check_pt_BR_4449abc1e8eb7d6f53fdd23c9894b3e5d553eec4fbb452f57f1c77935e48dafd -->
```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Carregar</translation>
    
ERR
The translation is incomplete—the source text "Load Partially Signed Bitcoin Transaction" is translated only as "Carregar" ("Load"), omitting the rest of the phrase. This can confuse users since "Carregar" does not specify what is being loaded.

Correct translation:
Carregar Transação Bitcoin Parcialmente Assinada
```

<!-- cache_translation_check_pt_BR_ac6e8ea1cc8789ec5dae7b1a5bc255bfa784eceaae9705c2def94a2c77da5d26 -->
```
        <source>Open wallet warning</source>
        <translation>Abrir carteira alerta</translation>
    
ERR
The translation is unnatural in Portuguese and does not correctly convey the meaning. "Abrir carteira alerta" is a literal and awkward translation. The correct translation should be:

Aviso ao abrir carteira

or

Aviso de abertura da carteira
```

<!-- cache_translation_check_pt_BR_a76a8b4a54053137822745f682752d21d835e9540875427682bcd4dbdcc7ac85 -->
```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>Quando clicar em OK, %1 iniciará o download e irá processar a cadeia de blocos completa %4 (%2 GB) iniciando com as mais recentes transações em %3 enquanto %4 é processado. </translation>
    
ERR
The translation inaccurately states "iniciando com as mais recentes transações" ("starting with the most recent transactions"), whereas the source says "starting with the earliest transactions". Additionally, the last part diverges from the meaning: "enquanto %4 é processado" ("while %4 is processed") does not match "when %4 initially launched".

Correct translation:
Quando você clicar em OK, %1 começará a baixar e processar a cadeia de blocos completa do %4 (%2 GB), começando com as transações mais antigas em %3, quando o %4 foi lançado inicialmente.
```

<!-- cache_translation_check_pt_BR_1673a1d49d7620cb63f82bbf6a7a0aa91e91244d2cbfc57df770420dd8fe7be4 -->
```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>Caminho completo para %1 um script compatível com Bitcoin Core (exemplo: C: \ Downloads \ hwi.exe ou /Users/you/Downloads/hwi.py). Cuidado: um malware pode roubar suas moedas!</translation>
    
ERR
The translation alters the meaning by specifying "um script compatível com Bitcoin Core" instead of strictly following the source "a %1 compatible script". "Bitcoin Core" was not present in the source and should not be added. There are also stray spaces around slashes due to how the paths are rendered ("C: \ Downloads \ hwi.exe"), which do not match standard path formatting.

Correct translation:
Caminho completo para um script compatível com %1 (exemplo: C:\Downloads\hwi.exe ou /Users/you/Downloads/hwi.py). Cuidado: malware pode roubar suas moedas!
```

<!-- cache_translation_check_pt_BR_3f32bb9e03216986bfab8ecbfca0f4d3f6bc3d9e7c9c47d6eb98bf1d84bd3578 -->
```
        <source>Open the %1 configuration file from the working directory.</source>
        <translation>Abrir o arquivo de configuração %1 apartir do diretório trabalho.</translation>
    
ERR  
There are two problems in the translation:  
1. "apartir" should be "a partir" (it's two words in Portuguese).  
2. "diretório trabalho" lacks the preposition and definite article, it should be "diretório de trabalho" to correctly mean "working directory".  

Correct translation:  
Abrir o arquivo de configuração %1 a partir do diretório de trabalho.
```

<!-- cache_translation_check_pt_BR_0dfd204ddd3204c9753ef0d3d4556d6ae244a6b1e25d48c01270eaefb58e2299 -->
```
        <source>Prune block storage to</source>
        <translation>Fazer Prune da memória de blocos para</translation>
    
ERR  
The translation is not natural and does not use the proper term in Portuguese. "Prune" is left untranslated, and "memória de blocos" should be "armazenamento de blocos". Also, the phrase in English is incomplete, but the translation unnecessarily capitalizes "Prune" and adds "Fazer".  

Correct translation:  
Reduzir o armazenamento de blocos para
```

<!-- cache_translation_check_pt_BR_f991c863c1acfda1eebfa23466e661fd83b45fcb165a56452189cad11012136b -->
```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>Mostra a quantia com a taxa já subtraída.</translation>
    
ERR
The translation changes the original meaning. The original sentence is about whether to set "subtract fee from amount" as the default option, not merely displaying the amount with the fee subtracted.

Correct translation:
Definir ou não “subtrair a taxa do valor” como padrão.
```

<!-- cache_translation_check_pt_BR_7edb37286165b84c496fff296323fd990b925ec5f22de9dbb1513047b81ce23e -->
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
    
ERR
There are some issues with this translation:
- "Bem vindo ao %1 console de RPC." should be "Bem-vindo ao console RPC %1." for natural word order and correct spelling ("Bem-vindo" instead of "Bem vindo").
- "a tamanho da fonte" is incorrect. It should be "o tamanho da fonte".
- In "Para mais informações sobre a utilização desse console. digite %6.", there is a period instead of a comma or semicolon before "digite". It should be "Para mais informações sobre a utilização desse console, digite %6."
- In "%7 AVISO: Scammers estão ativamente influenciando usuário a digitarem comandos aqui, roubando os conteúdos de suas carteiras.", "Scammers" should be translated to "golpistas".
- "usuário" should be plural ("usuários").
- "AVISO:" is now separated from %7, unlike the source, which appears to intend for both the opening and closing style tags (%7 and %8) to be flush with the text that follows/preceded them (i.e. no extra space).
- "conteúdos de suas carteiras" can be more naturally rendered as "o conteúdo de suas carteiras".
- "este terminal" should be "este console" to match the context.

Correct translation:
Bem-vindo ao console RPC %1.
Utilize as setas para cima e para baixo para navegar no histórico e %2 para limpar a tela.
Utilize %3 e %4 para aumentar ou diminuir o tamanho da fonte.
Digite %5 para ver uma visão geral dos comandos disponíveis.
Para mais informações sobre o uso deste console, digite %6.

%7AVISO: Golpistas têm estado ativos, instruindo usuários a digitarem comandos aqui e roubando o conteúdo de suas carteiras. Não utilize este console sem compreender plenamente as consequências de um comando.%8
```

<!-- cache_translation_check_pt_BR_eb7fb4ab3e3cf215743d3f7cdf6db90d5344e4de30a0484df05fd740cab4bccd -->
```
        <source>An optional label to associate with the new receiving address (used by you to identify an invoice).  It is also attached to the payment request.</source>
        <translation>Um rótulo opcional para associar ao novo endereço de recebimento (usado por você para identificar uma solicitação de pagamento). Que também será adicionado a solicitação de pagamento.</translation>
    
ERR
The translation contains some issues:
- "identificar uma solicitação de pagamento" does not accurately translate "identify an invoice" (should be "identificar uma fatura").
- The second sentence has a minor issue: "Que também será adicionado a solicitação de pagamento." is not idiomatic; "Que" should not begin the sentence, and "a solicitação de pagamento" is missing an accent: "à solicitação de pagamento".

Correct translation:
Um rótulo opcional para associar ao novo endereço de recebimento (usado por você para identificar uma fatura). Ele também será anexado à solicitação de pagamento.
```

<!-- cache_translation_check_pt_BR_237e70b743fcb1723d03b598807b6ae0e7546472efec38ebd3572c79b029a456 -->
```
        <source>Bech32m (BIP-350) is an upgrade to Bech32, wallet support is still limited.</source>
        <translation>Bech32m (BIP-350) é uma atualização para o Bech32,</translation>
    
ERR
The translation is incomplete. The second clause "wallet support is still limited" is missing.

Correct translation:
Bech32m (BIP-350) é uma atualização do Bech32, o suporte por carteiras ainda é limitado.
```

<!-- cache_translation_check_pt_BR_ac72309daae00474d89ae7b63fe98dbedeea03ccc80ddd37e42e2a00a2cbc805 -->
```
        <source>%1 from wallet '%2'</source>
        <translation>%1 da pasta "%2</translation>
    
ERR
The translation is problematic for two reasons:
1. "wallet" should be translated as "carteira" in the Bitcoin context, not "pasta" (which means "folder"). 
2. The closing quotation mark after %2 is missing.

Correct translation:
%1 da carteira "%2"
```

<!-- cache_translation_check_pt_BR_7c488705dbfb6809d899d8fffef73bc142ee140f57c07c287757235f335f3149 -->
```
        <source>The recipient address is not valid. Please recheck.</source>
        <translation>Endereço de envio inváido. Favor checar.</translation>
    
ERR
There is a typo in the translation ("inváido" instead of "inválido"). Additionally, "Endereço de envio" is not the best equivalent of "recipient address"; "O endereço do destinatário" is clearer. The translation omits the nuance of "Please recheck" as "Favor checar" is less formal and a bit awkward.

Correct translation:
O endereço do destinatário não é válido. Por favor, verifique novamente.
```

<!-- cache_translation_check_pt_BR_3a6704b1bc92f2003d5c981f6d6a2dfc3d66ca3d3c4c018a4c95f563760ecda6 -->
```
        <source>The address you selected for change is not part of this wallet. Any or all funds in your wallet may be sent to this address. Are you sure?</source>
        <translation>O endereço selecionado para o troco não pertence a esta carteira. Alguns ou todos os fundos da sua carteira modem ser mandados para esse endereço. Tem certeza?</translation>
    
ERR
There is a typo in the translation: "modem ser mandados" should be "podem ser enviados".

Correct translation:
O endereço selecionado para o troco não pertence a esta carteira. Alguns ou todos os fundos da sua carteira podem ser enviados para esse endereço. Tem certeza?
```

<!-- cache_translation_check_pt_BR_b19e3aeca63b082de2e16e94e7bca6477eceddb9bb662231a23e90e52928e012 -->
```
        <source>The signature did not match the message digest.</source>
        <translation>A assinatura não corresponde a mensagem.</translation>
    
ERR
The translation omits the meaning of "message digest" ("resumo da mensagem" or "digest da mensagem"). The correct translation should reflect that the signature does not match the digest, not just "the message".

Correct translation:
A assinatura não corresponde ao resumo da mensagem.
```

<!-- cache_translation_check_pt_BR_c72524e5555d5ae8e75e3011e4cd68d92b5e69ddf2d998b1f265ef3c60ff2895 -->
```
        <source>%s request to listen on port %u. This port is considered "bad" and thus it is unlikely that any peer will connect to it. See doc/p2p-bad-ports.md for details and a full list.</source>
        <translation>1%s solicita para escutar na porta 2%u. Esta porta é considerada "ruim" e, portanto, é improvável que qualquer ponto se conecte-se a ela. Consulte doc/p2p-bad-ports.md para obter detalhes e uma lista completa.</translation>
    
ERR
There are several issues in the translation:
- The placeholders "%s" and "%u" have been incorrectly rendered as "1%s" and "2%u", which is incorrect.
- "peer" is translated as "ponto", which is not standard for Bitcoin context ("par" is better).
- "conecte-se a ela" is awkward. "que qualquer par se conecte a ela" is better.
- The rest is mostly accurate, but the format specifiers must not change.

Correct translation:
%s solicita para escutar na porta %u. Esta porta é considerada "ruim" e, portanto, é improvável que qualquer par se conecte a ela. Consulte doc/p2p-bad-ports.md para obter detalhes e uma lista completa.
```

<!-- cache_translation_check_pt_BR_803cb7fb1babfe21ae7e2c1bd3a7df16a4cbc1c5e6c54dc22e310e3fe2094296 -->
```
        <source>Disk space for %s may not accommodate the block files. Approximately %u GB of data will be stored in this directory.</source>
        <translation>O espaço em disco para 1%s pode não acomodar os arquivos de bloco. Aproximadamente 2%u GB de dados serão armazenados neste diretório.</translation>
    
ERR
The translation has multiple formatting errors:
- The format specifiers %s and %u were incorrectly changed to 1%s and 2%u, which will cause errors in string substitution.
- There are unintended numerals "1" and "2" before the format specifiers.
- Otherwise, the translation is good.

Correct translation:
O espaço em disco para %s pode não acomodar os arquivos de bloco. Aproximadamente %u GB de dados serão armazenados neste diretório.
```

<!-- cache_translation_check_pt_BR_0f7085f564f7e361d335424f8a0c835df6b7696e616c42d3de0571f8dde2d6b8 -->
```
        <source>Error: Unable to produce descriptors for this legacy wallet. Make sure to provide the wallet's passphrase if it is encrypted.</source>
        <translation>Erro: Não foi possível produzir descritores para esta carteira antiga. Certifique-se que a carteira foi desbloqueada antes</translation>
    
ERR
The translation omits the instruction "Make sure to provide the wallet's passphrase if it is encrypted" and instead says "Certifique-se que a carteira foi desbloqueada antes" ('Make sure the wallet was unlocked before'), which is not an accurate representation of the source. It also omits the condition concerning encryption and the use of the passphrase.

Correct translation:
Erro: Não foi possível produzir descritores para esta carteira antiga. Certifique-se de fornecer a senha da carteira caso ela esteja criptografada.
```

<!-- cache_translation_check_pt_BR_b26a1e55623ff2a6741b0374442d180c4413d1fd78be6e329255485f76054b24 -->
```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>Mais de um endereço onion associado é fornecido. Usando %s para automaticamento criar serviço onion Tor.</translation>
    
ERR
There is a grammar and word choice error: "automaticamento criar" is not correct Portuguese—it should be "criado automaticamente" to reflect "automatically created". Also, the phrase could be more naturally rendered. 

Correct translation:
Mais de um endereço onion foi fornecido. Usando %s para o serviço onion do Tor criado automaticamente.
```

<!-- cache_translation_check_pt_BR_b512286469bad97c9c2fd391adab6912fae95841d8c38b468d6d69b5187f57a1 -->
```
        <source>Witness data for blocks after height %d requires validation. Please restart with -reindex.</source>
        <translation>Testemunhar dados de blocos após 1%d requer validação. Por favor reinicie com -reindex.</translation>
    
ERR
The translation incorrectly uses "1%d" instead of the correct format specifier "%d". Also, "Testemunhar dados de blocos" is awkward; "Os dados de testemunha para blocos após a altura %d requerem validação." is more natural in Portuguese.

Correct translation:
Os dados de testemunha para blocos após a altura %d requerem validação. Por favor, reinicie com -reindex.
```

<!-- cache_translation_check_pt_BR_1f02c0dba2663f6297306617169259f44c21625c667974c76a2ada3dec5e9b2f -->
```
        <source>Rename of '%s' -&gt; '%s' failed. Cannot clean up the background chainstate leveldb directory.</source>
        <translation>Renomear de '%s' -&gt; '%s'falhou. Não é possível limpar o diretório leveldb do chainstate em segundo plano.</translation>
    
ERR
There is a missing space after the arrow ('%s' -> '%s'falhou), which should be '%s' -> '%s' falhou. Also, for clarity, "em segundo plano" can be retained, but "leveldb do chainstate em segundo plano" is a somewhat awkward phrase compared to "diretório chainstate leveldb em segundo plano", which closer mirrors the English context.

Correct translation:
Renomear de '%s' -> '%s' falhou. Não é possível limpar o diretório chainstate leveldb em segundo plano.
```

<!-- cache_translation_check_pt_BR_280444c4ef418dd2c14f4e051ff039321931b8370a634fe1e19957ae69555734 -->
```
        <source>A fatal internal error occurred, see debug.log for details: </source>
        <translation>Ocorreu um fatal internal error, consulte debug.log para obter detalhes:</translation>
    
ERR
The translation inappropriately mixes English and Portuguese ("fatal internal error" remains untranslated). Additionally, "fatal" should precede "erro interno" in natural Portuguese, and there should be no unnecessary whitespace before the colon.

Correct translation:
Ocorreu um erro interno fatal, consulte o debug.log para obter detalhes:
```

<!-- cache_translation_check_pt_BR_d27d9299ae36f50757303fda5e3399f6ba68c9be2f191433d8c66ed32df64054 -->
```
        <source>Cannot write to directory '%s'; check permissions.</source>
        <translation>Não é possível escrever no diretório '%s'; verifique aspermissões.</translation>
    
ERR
There is a typo in the translation: "aspermissões" should be "as permissões" (with a space between "as" and "permissões").

Correct translation:
Não é possível escrever no diretório '%s'; verifique as permissões.
```

<!-- cache_translation_check_pt_BR_c93f70935e64ce375f4b63043fa0886c53a70f59e906b50d69e32d65a94f5d21 -->
```
        <source>Transaction change output index out of range</source>
        <translation>Endereço de troco da transação fora da faixa</translation>
    
ERR
The translation is inaccurate. "Transaction change output index out of range" refers to the index of the change output in a transaction being out of range, not specifically to the address. The translation also omits "index" and the concept of "output". A correct translation would be:

Índice da saída de troco da transação fora do intervalo
```

<!-- cache_translation_check_pt_BR_551d53eed3972ece7fab682c107e226256eab32d27c3c4ea91d0a9eb9e78cc29 -->
```
        <source>Unable to find UTXO for external input</source>
        <translation>Impossível localizar e entrada externa UTXO</translation>
    
ERR
The translation is inaccurate and contains an error. The phrase "e entrada externa UTXO" is incorrect and does not correctly reflect the meaning of the source text. "Impossível localizar UTXO para entrada externa" would be the correct translation.

Correct translation:
Impossível localizar UTXO para entrada externa
```

<!-- cache_translation_check_pt_BR_ed2dcf583a185798747a10ff6c71a93ee66b631ce797911114bb5c3a94806daa -->
```
        <source>Wallet file creation failed: %s</source>
        <translation>falha na criação do ficheiro da pasta: %s</translation>
    
ERR
The translation has issues:
1. "ficheiro" is European Portuguese; 'pt_BR' should use "arquivo".
2. "da pasta" translates to "of the folder", which is incorrect, as "wallet file" means specifically the file, not a folder.

Correct translation:
Falha na criação do arquivo de carteira: %s
```

<!-- cache_translation_check_pt_BR_49f904c4059906cfd1499ed83bab244be3008485917f7b006aeff59990db17c6 -->
```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Erro: Não foi possível adicionar tx %s de vigilância à pasta de vigilância</translation>
    
ERR
The translation uses "pasta de vigilância" for "watchonly wallet", which is incorrect. In Bitcoin context, "wallet" is usually translated as "carteira", not "pasta". "Tx de vigilância" is understandable, but "transação watchonly" or "somente observação" would be better.

Correct translation:
Erro: Não foi possível adicionar a transação %s somente observação à carteira somente observação
```
</details>

Number of issues: 28.
