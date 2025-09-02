# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>pt</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bpt%5D%20request)


<!-- cache_translation_check_pt_d49da9fabba493bdadbf873436655b6fea6997e5d8d6659fa7b263f6f8ab9156 -->
```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>Antena</translation>
    
ERR
"Antena" is incorrect: it means "antenna" in Portuguese and doesn't convey the technical meaning. The source refers to a short-lived peer connection used to test whether known addresses are alive.

Suggested translation:
Feeler — Conexão de teste curta (tipo de ligação temporária para verificar se endereços conhecidos estão ativos)

Or shorter:
Conexão de verificação curta
```

<!-- cache_translation_check_pt_43a52571e52e121012eecb59cdc15efc7b4ba9bb3329387206a50f2bcc80d3f7 -->
```
        <source>Address Fetch</source>
        <extracomment>Short-lived peer connection type that solicits known addresses from a peer.</extracomment>
        <translation>Procura de endreços</translation>
    
ERR
The Portuguese translation contains a spelling error: "endreços" should be "endereços". Also consider a more natural phrasing for this context (short-lived peer connection): "Busca de endereços" or "Recuperação de endereços".

Correct translation (fixed spelling, literal match):
Procura de endereços

Alternative, more natural translations:
Busca de endereços
Recuperação de endereços
```

<!-- cache_translation_check_pt_3349460b4377e2d127961979ce13dbc2e36c3accceaf189826513ce4385afe8c -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation>Carteira &amp;encriptada…</translation>
    
ERR
The translation changes the meaning. The source is a command (“&Encrypt Wallet…”), but the translation is a description (“Wallet encrypted…”). The correct translation should maintain the imperative.

Correct translation:
&amp;Encriptar carteira…
```

<!-- cache_translation_check_pt_5a8d11ad380f34acfa6f69b9007f8cf0ed086b3c073ae506fdc3af10668ef199 -->
```
        <source>&amp;Command-line options</source>
        <translation>&amp;Opções da linha de &amp;comando</translation>
    
ERR
The translation contains the shortcut key indicator (&) twice: once before "Opções" and once before "comando". There should be exactly one shortcut key indicator in the translation, as in the source text.

Correct translation:
&Opções da linha de comando
or
Opções da linha de &comando

Either is acceptable, but only one & should appear.
```

<!-- cache_translation_check_pt_f647d5310008bb25f9520386ba81d3628d16e2af3e2452d5038a9742f70f43f4 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>Carregar PSBT da área de transferência...</translation>
    
ERR
The translation is missing the shortcut key indicator (&) from the source, which is important for UI consistency. The ellipsis character (…) is also replaced with three dots (...), which is acceptable but less ideal. Correct translation:

Carregar PSBT da &área de transferência…
</reply>
```

<!-- cache_translation_check_pt_b1b4889ae5722e85a424ed07885094b1426c5a82805daa67badd18113e37750f -->
```
        <source>&amp;Sending addresses</source>
        <translation>&amp;Endereço de envio</translation>
    
ERR
The translation uses the singular "Endereço de envio" instead of the correct plural form, which should match the source "Sending addresses". Additionally, the ampersand is present only once, as required.

Correct translation:
&amp;Endereços de envio
</reply>
```

<!-- cache_translation_check_pt_84a4736c2a3d7d41e855a29f46740fac50d60c9b5a892c752b71d1dc269cdf44 -->
```
        <source>&amp;Mask values</source>
        <translation>&amp;Valores de Máscara</translation>
    
ERR
The translation "Valores de Máscara" does not accurately convey the meaning of "Mask values" in the Bitcoin context. The correct translation should be "Mascarar valores", which matches the verb form, rather than the noun phrase "Valores de Máscara".

Correct translation:
&amp;Mascarar valores
```

<!-- cache_translation_check_pt_c38a528109aac10ea0f408800d1dad451f018c4a68b2d0012aba913d849f07a6 -->
```
        <source>&amp;Hide</source>
        <translation>Ocultar</translation>
    
ERR
The translation omits the '&' which indicates the shortcut key. It must appear exactly once in the translation.

Correct translation:
&Ocutlar
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

<!-- cache_translation_check_pt_93dc03eaf7c4953bb66fff7604f71021ea60a5a7ecba7edcbda2084528f34611 -->
```
        <source>External Signer (e.g. hardware wallet)</source>
        <translation>Assinante externo (por exemplo, carteira de hardware)</translation>
    
ERR
The Portuguese word "assinante" usually means "subscriber" and can be ambiguous. In this Bitcoin context "signer" (device that signs transactions) is better translated as "assinador".

Correct translation:
Assinador externo (por exemplo, carteira de hardware)
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

<!-- cache_translation_check_pt_0f924c73e066a64247e6a037251164efb7be0b32fe71d34754c7cf1037b0abf1 -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>&amp;Minimizar para a bandeja de sistema e não para a barra de ferramentas</translation>
    
ERR
The translation inaccurately translates "taskbar" as "barra de ferramentas" (toolbar) instead of "barra de tarefas" (taskbar). Also, "bandeja de sistema" can be shortened to simply "bandeja" or "bandeja do sistema" for clarity.

Correct translation:
&amp;Minimizar para a bandeja em vez da barra de tarefas
```

<!-- cache_translation_check_pt_7ce81eb92c5edb4eaae36e9caf8af0563b93766498af85360bef1a19106248fb -->
```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>Modo de privacidade ativado para a aba de visão geral. para desmascarar os valores, desmarque nas Configurações -&gt; Valores de máscara</translation>
    
ERR
Issues:
- Sentence after the period should start with a capital letter ("para" → "Para").
- The phrasing "para a aba de visão geral" is awkward; prefer "na aba Visão Geral".
- The menu item translation is incorrect/awkward: "Valores de máscara" reads like a noun phrase. The source is a menu action "Mask values" (verb), so it should be translated as "Mascarar valores" and presented as a menu path.
- Minor punctuation: keep the arrow spacing consistent.

Correct translation:
Modo de privacidade ativado na aba Visão Geral. Para desmascarar os valores, desmarque Configurações -> Mascarar valores.
```

<!-- cache_translation_check_pt_5b78996bfd056288f155ee580ec07b87cdcc95a563195947ef185daf5812d8cc -->
```
        <source>Failed to load transaction: %1</source>
        <translation>Falha ao carregar transação: %1</translation>
    
ERR
The translation is understandable but missing the definite article that is more natural in Portuguese. Keep the format specifier as-is.

Correct translation:
Falha ao carregar a transação: %1
```

<!-- cache_translation_check_pt_777867c9bd1107745ab6bd281635e3ab95849852603be0cf38c33f7de2ac49b7 -->
```
        <source>Signed %1 inputs, but more signatures are still required.</source>
        <translation>Assinadas entradas %1, mas mais assinaturas ainda são necessárias.</translation>
    
ERR
Word order in Portuguese is incorrect. "Assinadas entradas %1" is unnatural; the number should precede the noun or the adjective should follow. The format specifier %1 is preserved, but the phrase should be reworded.

Correct translation:
%1 entradas assinadas, mas ainda são necessárias mais assinaturas.
```

<!-- cache_translation_check_pt_bfe93608a06cf5d1892c3004bc20a2b727c60b31a6f65a7036516a3bbb06a0b6 -->
```
        <source>Save Transaction Data</source>
        <translation>Salvar informação de transação</translation>
    
ERR
The translation is understandable but slightly unnatural in Portuguese. Use the plural and a more natural preposition/article.

Better translations:
- Salvar dados da transação
or
- Salvar informações da transação
```

<!-- cache_translation_check_pt_b4866c000111a57c85bd09f9598472bd73ec1a8dca1a426e6ca122e0949501a4 -->
```
        <source>Transaction is missing some information about inputs.</source>
        <translation>Transação está com alguma informação faltando sobre as entradas.</translation>
    
ERR
The Portuguese is understandable but slightly ungrammatical/awkward: it lacks the definite article before "Transação" and uses singular "alguma informação" while "entradas" is plural. A more natural translation:

Correct translation:
A transação está com algumas informações faltando sobre as entradas.
```

<!-- cache_translation_check_pt_5f030f239e8afab223435ad0f0177c8c4c8c11b96e1073262779c4bb24fafba1 -->
```
        <source>Transaction status is unknown.</source>
        <translation>Status da transação é desconhecido.</translation>
    
ERR
The Portuguese translation is understandable but stylistically incomplete: it omits the definite article. More natural translations are:

Correct translation:
O status da transação é desconhecido.

Or alternatively:
O estado da transação é desconhecido.
```

<!-- cache_translation_check_pt_be3761d45355d173ff541fe845649a17affba2e7febf41f797482e05fd12809a -->
```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Impossível iniciar o controlador de bitcoin: click-to-pay</translation>
    
ERR
The translation is understandable but slightly unnatural: "controlador" is not the best choice for a software "handler", and the phrase order could be clearer in Portuguese. Also consider quoting or hyphenating the feature name.

Suggested translation:
Impossível iniciar o manipulador "click-to-pay" do Bitcoin
```

<!-- cache_translation_check_pt_4b8f8256f4ab8699cd3dd3a1a381f5aef46bb412914d39c90652cc0dfb0f78b9 -->
```
        <source>Cannot process payment request because BIP70 is not supported.
Due to widespread security flaws in BIP70 it's strongly recommended that any merchant instructions to switch wallets be ignored.
If you are receiving this error you should request the merchant provide a BIP21 compatible URI.</source>
        <translation>Não é possível processar o pagamento pedido porque o BIP70 não é suportado.
Devido a falhas de segurança no BIP70, é recomendado que todas as instruçōes ao comerciante para mudar de carteiras sejam ignorada.
Se está a receber este erro, deverá pedir ao comerciante para fornecer um URI compatível com BIP21.</translation>
    
ERR
The Portuguese has several issues: awkward phrasing ("pagamento pedido" should be "pedido de pagamento"), a mis-typed accent ("instruçōes" wrong), grammatical agreement ("sejam ignorada" should be "sejam ignoradas"), and unnatural wording ("mudar de carteiras").

Correct translation:
Não é possível processar o pedido de pagamento porque o BIP70 não é suportado.
Devido às falhas de segurança generalizadas no BIP70, recomenda-se fortemente que quaisquer instruções do comerciante para mudar de carteira sejam ignoradas.
Se estiver a receber este erro, deve pedir ao comerciante que forneça um URI compatível com BIP21.
```

<!-- cache_translation_check_pt_d95e9111e71a2147f9c9c1cdef74d5d8fb0396f66937d0626d58a8b0a1970556 -->
```
        <source>Payment request file handling</source>
        <translation>Controlo de pedidos de pagamento.</translation>
    
ERR
The translation "Controlo de pedidos de pagamento." reads as "Control of payment requests" and doesn't convey "file handling" (i.e., handling/manipulation of payment request files). Also it adds a terminal period not present in the source.

Suggested corrections (no trailing period):
- European Portuguese: Manipulação de ficheiros de pedido de pagamento
- Brazilian Portuguese: Manipulação de arquivos de solicitação de pagamento
```

<!-- cache_translation_check_pt_8a1d391706529dda0419dd477fcfabd684f11b849f33af1a0ad2b7de38cc7587 -->
```
        <source>Age</source>
        <extracomment>Title of Peers Table column which indicates the duration (length of time) since the peer connection started.</extracomment>
        <translation>idade</translation>
    
ERR
The translation is correct in meaning ("idade") but should follow title capitalization. Also maintain same casing as other UI labels — capitalize the first letter.

Correct translation:
Idade
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

<!-- cache_translation_check_pt_c216f87aaeae13d8d78249aae320ce96b8bb34fe6ca7c2bb5ec90558c5abe982 -->
```
        <source>&amp;Label:</source>
        <translation>&amp;Etiqueta</translation>
    
ERR
The translation is missing the colon at the end, which should be kept for consistency with the source.

Correct translation:
&amp;Etiqueta:
</reply>
```

<!-- cache_translation_check_pt_892249fbf760b35d4f0581de94344670c6178adefc12adceba9cd638e3780e61 -->
```
        <source>Cr&amp;eate Unsigned</source>
        <translation>Criar &amp;não assinado</translation>
    
ERR
The translation is literally correct but unnatural in Portuguese. "Criar &não assinado" is awkward and typical translations for "Unsigned" in the context of Bitcoin are "transação não assinada" (unsigned transaction). Also, ideally, the shortcut key (&) should be applied to an appropriate letter in the Portuguese translation. It would be better as "Criar &Não Assinada".

Correct translation:
Criar &Não Assinada
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

<!-- cache_translation_check_pt_c216f87aaeae13d8d78249aae320ce96b8bb34fe6ca7c2bb5ec90558c5abe982 -->
```
        <source>&amp;Label:</source>
        <translation>&amp;Etiqueta</translation>
    
ERR
The translation is missing the colon at the end, which should be kept for consistency with the source.

Correct translation:
&amp;Etiqueta:
</reply>
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

<!-- cache_translation_check_pt_fd65566c9df3f9c7f931ea36980037ae9c1fb171d68fe97847311cd2ce1341b0 -->
```
        <source>Copy transaction &amp;ID</source>
        <translation>Copiar ID da transação</translation>
    
ERR
The translation omits the '&' which is important for indicating the keyboard shortcut. There should be exactly one '&' in the translation.

Correct translation:
Copiar &ID da transação
</reply>
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

<!-- cache_translation_check_pt_30cde3871fe5c22ffeaa630a7b2e23ce636071794a1d1d7b6e2863a1a3e3b878 -->
```
        <source>Prune configured below the minimum of %d MiB.  Please use a higher number.</source>
        <translation>Poda configurada abaixo do mínimo de %d MiB.  Por favor, utilize um valor mais elevado.</translation>
    
ERR
The Portuguese translation is understandable but slightly awkward and has double spacing after the period. "Poda configurada abaixo do mínimo..." is not idiomatic; also prefer a single space after the period.

Correct translation (keeps %d MiB and fixes phrasing and spacing):
A poda está configurada abaixo do mínimo de %d MiB. Por favor, use um número maior.
```

<!-- cache_translation_check_pt_3afd6c183cae30e45b28ff1f9a2babffef3730d6e323c38d6216747fb4a6d79b -->
```
        <source>Prune mode is incompatible with -reindex-chainstate. Use full -reindex instead.</source>
        <translation>O modo Prune é incompatível com a opção "-reindex-chainstate". Ao invés disso utilize "-reindex".</translation>
    
ERR
Minor style/grammar issue and casing: "Prune" should be lowercase (mode name) and add a comma/flow improvement. No format specifiers are involved and the options are preserved correctly.

Correct translation:
O modo prune é incompatível com a opção "-reindex-chainstate". Utilize o "-reindex" completo em vez disso.
```

<!-- cache_translation_check_pt_db75cea49f5e3c14d1a32f9a9fefb0a4560cd43caa54921c62365a5f67c9570b -->
```
        <source>The block database contains a block which appears to be from the future. This may be due to your computer's date and time being set incorrectly. Only rebuild the block database if you are sure that your computer's date and time are correct</source>
        <translation>A base de dados de blocos contém um bloco que aparenta ser do futuro. Isto pode ser causado por uma data incorreta definida no seu computador. Reconstrua apenas a base de dados de blocos caso tenha a certeza de que a data e hora do seu computador estão corretos.</translation>
    
ERR
The translation mostly reads naturally, but it omits "time" in the middle sentence ("uma data incorreta" only mentions date). The source says "date and time being set incorrectly", so both date and time should appear there for accuracy.

Correct translation:
A base de dados de blocos contém um bloco que aparenta ser do futuro. Isto pode dever‑se à data e hora do seu computador estarem definidas incorretamente. Reconstrua apenas a base de dados de blocos caso tenha a certeza de que a data e a hora do seu computador estão corretas.
```

<!-- cache_translation_check_pt_68c5e98d9f4a0247bd0a2efe24e7fd9993a0ba806ca0587323318d68be5e160f -->
```
        <source>Incompatible options: -dnsseed=1 was explicitly specified, but -onlynet forbids connections to IPv4/IPv6</source>
        <translation>Opções incompatíveis: "-dnsseed=1" foi explicitamente específicada, mas "-onlynet" proíbe conexões para IPv4/IPv6</translation>
    
ERR
There's a typo in "específicada" (should be "especificada") and the preposition is better as "com" or "a" rather than "para".

Correct translation:
Opções incompatíveis: "-dnsseed=1" foi explicitamente especificada, mas "-onlynet" proíbe conexões com IPv4/IPv6
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

<!-- cache_translation_check_pt_0a6fe395f694569a245449e0ee0e3e7c4f10e065cf67b588bddfaae966e28300 -->
```
        <source>Can't spend unconfirmed version %d pre-selected input with a version 3 tx</source>
        <translation>Não é possível gastar a entrada pré-selecionada da versão %d não confirmada com uma versão 3 tx</translation>
    
ERR
The Portuguese is understandable but has awkward word order and a gender/position issue with "versão %d não confirmada" placed after "entrada", making it unclear. Also "tx" is left in English; better to use "transação" or place "tx" after "versão 3" properly.

Correct translation:
Não é possível gastar a entrada pré-selecionada não confirmada de versão %d com uma transação de versão 3
```

<!-- cache_translation_check_pt_4464d7afbaa89f228541fa73d8f87d9c3d69c120cbcb6ad51fc67c8d32655c53 -->
```
        <source>Can't spend unconfirmed version 3 pre-selected input with a version %d tx</source>
        <translation>Não é possível gastar a entrada pré-selecionada da versão 3 não confirmada com uma versão %d tx</translation>
    
ERR
The Portuguese is understandable but awkwardly ordered and mixes English abbreviation "tx" with "versão %d". Better to place "não confirmada" next to "entrada" and use "transação" for clarity while keeping the %d specifier.

Correct translation:
Não é possível gastar a entrada pré-selecionada não confirmada da versão 3 com uma transação de versão %d
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

<!-- cache_translation_check_pt_02d76519c9d3cc6e194dd2fd5b858716692c9da658d8528e87cf08932008417d -->
```
        <source>The %s path uses exFAT, which is known to have intermittent corruption problems on macOS. Move this directory to a different filesystem to avoid data loss.</source>
        <translation>O caminho %s utiliza exFAT, que é conhecido por ter problemas intermitentes de corrupção no macOS. Mova esta diretoria para um sistema de ficheiros diferente para evitar a perda de dados.</translation>
    
ERR
The word "diretoria" is incorrect in this context (it means "board/management" in Portuguese). Also there's a mix of variants ("ficheiros" with "diretoria"). Use "diretório" (or "directório") for a filesystem directory.

Correct translation:
O caminho %s utiliza exFAT, que é conhecido por ter problemas intermitentes de corrupção no macOS. Mova este diretório para um sistema de ficheiros diferente para evitar a perda de dados.
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

Number of issues: 48.
