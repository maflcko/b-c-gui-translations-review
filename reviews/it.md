# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>it</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bit%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation>Click destro del mouse per modificare l'indirizzo oppure l'etichetta</translation>
    
YES  
The Italian translation is understandable but it is not idiomatic and mixes English and Italian ("Click destro del mouse"). A better and more natural translation would be:  
"Fai clic con il tasto destro per modificare l'indirizzo o l'etichetta"
```

```
        <source>Address Fetch</source>
        <extracomment>Short-lived peer connection type that solicits known addresses from a peer.</extracomment>
        <translation>Trova l’indirizzo </translation>
    
YES  
The translation has an extra trailing space and is not precise. "Address Fetch" refers to the action or process of retrieving addresses, not just "Find the address" (singular). A better translation would be more literal and noun-focused, such as "Recupero indirizzo" or "Recupero degli indirizzi" (if plural is intended). Since the source is singular ("Address Fetch"), the singular form is preferable.

Correct translation:  
Trova l’indirizzo
```

```
        <source>Backup wallet to another location</source>
        <translation>Effettua il backup del portafoglio</translation>
    
YES  
The translation "Effettua il backup del portafoglio" means "Perform the wallet backup" rather than specifying "to another location," which is part of the original English text. The phrase "to another location" is omitted and should be included to preserve the meaning.

Correct translation:  
"Effettua il backup del portafoglio in un'altra posizione"
```

```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>Mostra la lista degli indirizzi di ricezione utilizzati</translation>
    
YES
The translation is incomplete and misses "e delle etichette" (and labels), which is part of the source sentence.

Correct translation:
Mostra la lista degli indirizzi di ricezione utilizzati e delle etichette
```

```
        <source>Show</source>
        <translation>Scome</translation>
    
YES  
The Italian translation is incorrect. The English word "Show" should be translated as "Mostra" or "Visualizza" in Italian, not "Scome," which is not an Italian word.

Correct translation:  
Mostra
```

```
        <source>Pre-syncing Headers (%1%)…</source>
        <translation>Pre-sincronizzazione intestazioni  (%1%)…</translation>
    
YES
There is an extra space before the opening parenthesis that does not exist in the source text, which causes a formatting discrepancy. The Italian translation should avoid the space before the parentheses.

Correct translation:
Pre-sincronizzazione intestazioni (%1%)…
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>L'indirizzo "%1" esiste già come indirizzo di setinazione con l'etichetta "%2" e quindi non può essere aggiunto come indirizzo mittente.</translation>
    
YES  
There is a typo in the word "setinazione" which should be "destinazione". Also, the phrase "indirizzo mittente" is less common; it is more natural to say "indirizzo di invio" or "indirizzo mittente" is acceptable but "indirizzo di invio" fits better stylistically in this context.

Correct translation:  
L'indirizzo "%1" esiste già come indirizzo di destinazione con l'etichetta "%2" e quindi non può essere aggiunto come indirizzo di invio.
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Mostra se il proxy SOCK5 di default che p stato fornito è usato per raggiungere i contatti attraverso questo tipo di rete.</translation>
    
YES  
The translation contains errors:  
- "SOCK5" should be "SOCKS5" to match the source.  
- The phrase "che p stato fornito" contains "p" instead of "è" (missing accent), which is a typo.  
- "contatti" (contacts) is less appropriate in the Bitcoin network context; "peer" or "nodi" (nodes) would be better.  
- Overall, the sentence can be improved for clarity and correctness.

Correct translation:  
Mostra se il proxy SOCKS5 predefinito fornito è utilizzato per raggiungere i peer tramite questo tipo di rete.
```

```
        <source>Prune block storage to</source>
        <translation>Modalità "prune": elimina i blocchi dal disco dopo</translation>
    
YES  
The translation adds extra information ("Modalità 'prune': elimina i blocchi dal disco dopo") that is not present in the source text, which is shorter and more neutral ("Prune block storage to"). This makes the translation less accurate and potentially misleading. The original phrase is likely a label or prompt indicating setting a pruning target size and should remain concise.

Correct translation:  
Pruning dello spazio di archiviazione blocchi a
```

```
        <source>Could not read setting "%1", %2.</source>
        <translation>Non posso leggere l'impostazione "%1", %2,</translation>
    
YES
The translation incorrectly ends with a comma instead of a period, which differs from the source punctuation. Also, the source phrase "Could not read setting ..." conveys a past inability; "Non posso leggere ..." is present tense ("I cannot read ..."), which is not accurate. The correct tense is past ("Non ho potuto leggere ...").

Correct translation:
Non ho potuto leggere l'impostazione "%1", %2.
```

```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>Transizione Parzialmente Firmata (Binaria)</translation>
    
YES
The Italian word for "Transaction" is "Transazione," not "Transizione," which means "transition." 

Correct translation:
Transazione Parzialmente Firmata (Binaria)
```

```
        <source>(But no wallet is loaded.)</source>
        <translation>(Ma nessun portafogli è stato caricato.)</translation>
    
YES  
The Italian word for "wallet" is singular and masculine, so it should be "portafoglio" (singular) instead of "portafogli" (plural). Also, "Ma" is correct at the beginning, but the sentence would be more natural without capitalization after the opening parenthesis, or simply lowercase "ma" if inside parentheses. The original English places emphasis with parentheses, so keeping that is fine.  

Correct translation:  
(Ma nessun portafoglio è stato caricato.)
```

```
        <source>Transaction Relay</source>
        <translation>Relay di transazione</translation>
    
YES
The term "Relay" should be translated into Italian to maintain consistency and avoid mixing languages. The correct translation is:

"Rete di trasmissione delle transazioni" 

or more simply:

"Trasmissione delle transazioni" 

If brevity is needed and the concept corresponds specifically to "Transaction Relay," then:

"Relay di transazioni" (using "transazioni" plural) is acceptable, but ideally the English word "Relay" should be replaced by the Italian equivalent "Trasmissione" or "Inoltro".

Corrected translation:

"Relay di transazioni" 

or better:

"Inoltro delle transazioni"
```

```
        <source>Disconnect</source>
        <translation>Disconnetti</translation>
    
YES
The Italian translation contains a typo. The correct spelling is "Disconnetti" with two 'n's.

Correct translation:
Disconnetti
```

```
        <source>Unban</source>
        <translation>Elimina Ban</translation>
    
YES  
The translation is inaccurate and unnatural. "Unban" in Italian is better translated as "Rimuovi il ban" or simply "Sblocca". "Elimina Ban" incorrectly mixes English "Ban" with Italian, and "Elimina" usually means "Delete" rather than "Unban".

Correct translation:  
Rimuovi il ban
```

```
        <source>Ctrl+I</source>
        <translation>Ctrl+W</translation>
    
YES
The translation incorrectly changes the shortcut from "Ctrl+I" to "Ctrl+W". Shortcut keys should be preserved exactly as in the source.

Correct translation:
Ctrl+I
```

```
        <source>Copy message</source>
        <translation>Copia message</translation>
    
YES  
The English phrase "message" should be translated to the Italian equivalent "messaggio." The correct translation is:  
Copia messaggio
```

```
        <source>Could not generate new %1 address</source>
        <translation>Non è stato possibile generare il nuovo %1 indirizzo</translation>
    
YES  
The word order in Italian is incorrect. "indirizzo" (address) should immediately follow "%1" without intervening words. Also, "nuovo" should come after "%1" and before "indirizzo" as an adjective, but the phrase "il nuovo %1 indirizzo" is unnatural and incorrect because "%1" represents a placeholder (likely something like "Bitcoin"), so it should be "%1 nuovo indirizzo" or ideally "%1 indirizzo nuovo" is not idiomatic. The best way to say this in Italian is:  
"Non è stato possibile generare un nuovo indirizzo %1"  
or if "%1" is an adjective describing the type of address, then place it before "indirizzo":  
"Non è stato possibile generare un nuovo indirizzo %1"  

Correct translation:  
Non è stato possibile generare un nuovo indirizzo %1
```

```
        <source>Inputs…</source>
        <translation>Input...</translation>
    
YES
The translation uses "Input" in English rather than the correct Italian term. Also, the ellipsis character differs: the source uses the proper single character "…" (Unicode U+2026), while the translation uses three dots "...". The Italian word for "Inputs" (plural) in this Bitcoin context is "Input" (often used as is in Italian technical jargon), but if plural is intended, it should remain "Input" as it can be invariant in plural, or clarify with context. However, the main issue is the use of English rather than Italian. A better translation keeping the original ellipsis character would be:

Input…
```

```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>Transizione Parzialmente Firmata (Binaria)</translation>
    
YES
The Italian word for "Transaction" is "Transazione," not "Transizione," which means "transition." 

Correct translation:
Transazione Parzialmente Firmata (Binaria)
```

```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Rilevato un indirizzo duplicato Ciascun indirizzo dovrebbe essere utilizzato una sola volta.</translation>
    
YES  
The translation is missing proper punctuation and a connecting conjunction or pause between the two sentences, making it feel rushed and unclear. It should have a period or semicolon after "duplicato" and be rewritten for natural flow.

Correct translation:  
Rilevato un indirizzo duplicato. Ciascun indirizzo dovrebbe essere utilizzato una sola volta.
```

```
        <source>Confirm custom change address</source>
        <translation>Conferma il cambio di indirizzo</translation>
    
YES  
The translation "Conferma il cambio di indirizzo" is inaccurate in this Bitcoin context. "Change" refers to the leftover amount returned to the sender in a transaction, not a "change" of address. A correct translation should reflect "custom change address" as a specific type of Bitcoin address.

Correct translation:  
Conferma l'indirizzo di resto personalizzato
```

```
        <source>Sign Message</source>
        <translation>Firma Messaggio</translation>
    
YES  
The Italian translation "Firma Messaggio" is understandable but not idiomatic. The correct translation for "Sign Message" in this Bitcoin context (to digitally sign a message) is "Firma messaggio" (with lowercase 'm' in "messaggio") or better "Firma il messaggio" to be more natural.

Correct translation:  
Firma messaggio
```

```
        <source>Sign Message</source>
        <translation>Firma Messaggio</translation>
    
YES  
The Italian translation "Firma Messaggio" is understandable but not idiomatic. The correct translation for "Sign Message" in this Bitcoin context (to digitally sign a message) is "Firma messaggio" (with lowercase 'm' in "messaggio") or better "Firma il messaggio" to be more natural.

Correct translation:  
Firma messaggio
```

```
        <source>Inputs</source>
        <translation>Input</translation>
    
YES  
The English source is plural "Inputs," but the Italian translation "Input" is singular. The correct plural form in Italian should be "Input" as well, since "input" is an invariable noun in Italian and remains the same in singular and plural. However, in this context, the plural is implied by the English source. To clarify plurality in Italian, you can use "Input" (as is) or add a clarifying phrase if needed. But usually "Input" is accepted for both singular and plural.

So, the translation "Input" is acceptable and widely used. However, if explicitly needed, "Ingressi" could be used to specify plural "Inputs," though this is less common in Bitcoin terminology.

Because "Input" is uncountable and used in singular and plural in Italian technical language, no error occurs.

Given that, the initial translation is correct and not problematic.

Therefore, the answer is NO.
```

```
        <source>Copy transaction ID</source>
        <translation>Copia la transazione ID</translation>
    
YES  
The translation is slightly inaccurate and unnatural in Italian. "ID" should be translated as "ID" or "identificativo" and placed properly. The phrase "Copy transaction ID" is best translated as "Copia l'ID della transazione" or "Copia l'identificativo della transazione" for clarity and correctness.

Correct translation:  
Copia l'ID della transazione
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>impossibile aggiornare un portafoglio non diviso e non HD dalla versione %i alla versione %i senza fare l'aggiornamento per supportare il pre-split keypool. Prego usare la versione %i senza specificare la versione</translation>
    
YES  
The translation is mostly clear but contains some inaccuracies and awkward phrasing:  
- It should start with a capital letter ("Impossibile").  
- "portafoglio non diviso e non HD" is incorrect; the original says "non HD split wallet," meaning a wallet that is both non-HD and non-split (or at least "non-HD split wallet"). A better phrasing is "un portafoglio non HD e non diviso" or "un portafoglio non HD e non split".  
- The phrase "senza fare l'aggiornamento per supportare il pre-split keypool" sounds unnatural; better is "senza aggiornarlo per supportare il pre-split keypool."  
- The ending "Prego usare la versione %i senza specificare la versione" is contradictory ("usare la versione %i senza specificare la versione"). The original "Please use version %i or no version specified" means "utilizzare la versione %i o non specificare alcuna versione."  
- Also, punctuation and capitalization could be improved.  

Corrected translation:  
Impossibile aggiornare un portafoglio non HD e non diviso dalla versione %i alla versione %i senza aggiornarlo per supportare il pre-split keypool. Si prega di usare la versione %i oppure di non specificare alcuna versione.
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>Errore: l'identificativo rispetto la registrazione del dumpfile è incorretta.  ricevuto "%s", sarebbe dovuto essere "%s".</translation>
    
YES  
The Italian translation contains awkward phrasing and some minor grammatical issues. The phrase "l'identificativo rispetto la registrazione del dumpfile" is unnatural and should be corrected. Also, there is an extra space before "ricevuto", and the verb agreement should be adjusted to match the feminine noun "identificativo" (masculine) or rephrase for clarity.

Correct translation:  
Errore: il record identificativo del dumpfile non è corretto. Ricevuto "%s", era previsto "%s".
```

```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Errore: la versione di questo dumpfile non è supportata. Questa versione del bitcoin-wallet supporta solo la versione 1 dei dumpfile. Ricevuto un dumpfile di versione%s</translation>
    
YES
There is a missing space before the format specifier "%s" in the translation, causing a formatting issue.

Correct translation:
Errore: la versione di questo dumpfile non è supportata. Questa versione del bitcoin-wallet supporta solo la versione 1 dei dumpfile. Ricevuto un dumpfile di versione %s
```

```
        <source>File %s already exists. If you are sure this is what you want, move it out of the way first.</source>
        <translation>file %s esistono già. Se desideri continuare comunque, prima rimuovilo.</translation>
    
YES  
The translation contains errors: "file" should be capitalized as it starts the sentence, and "esistono" (plural) is incorrect because "%s" refers to a single file. Also, "Se desideri continuare comunque" is less precise than "Se sei sicuro che è quello che vuoi fare." The original meaning about "moving it out of the way first" is better rendered as "spostalo da un'altra parte prima."  

Correct translation:  
"File %s esiste già. Se sei sicuro che è quello che vuoi fare, spostalo da un'altra parte prima."
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>Viene fornito più di un indirizzo di associazione onion. L'utilizzo di %s per il servizio Tor onion viene creato automaticamente.</translation>
    
YES  
The Italian translation is awkward and partially inaccurate. The phrase "indirizzo di associazione onion" is unnatural; a better term would be "indirizzo onion di binding" or "indirizzo onion vincolato." The second sentence lacks clarity and is phrased awkwardly; it should reflect that "%s" is being used for the automatically created Tor onion service.

Correct translation:  
"È stato fornito più di un indirizzo onion di binding. Verrà utilizzato %s per il servizio Tor onion creato automaticamente."
```

```
        <source>No dump file provided. To use createfromdump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>Nessun dump file fornito. Per usare creadumpfile, -dumpfile=&lt;filename&gt; deve essere fornito.</translation>
    
YES  
The Italian translation has some issues:  
- "dump file" should be translated consistently ("file di dump" is common in Italian).  
- The command "createfromdump" is mistranslated as "creadumpfile" which is incorrect; it should remain "createfromdump" as it is a command/option.  
- The sentence structure can be improved for clarity and naturalness.

Correct translation:  
Nessun file di dump fornito. Per usare createfromdump, deve essere specificato -dumpfile=&lt;filename&gt;.
```

```
        <source>Unknown wallet file format "%s" provided. Please provide one of "bdb" or "sqlite".</source>
        <translation>Il formato “%s” del file portafoglio fornito non è riconosciuto. si prega di fornire uno che sia “bdb” o “sqlite”. </translation>
    
YES  
The translation has a lowercase "si" at the beginning of the second sentence, which should be capitalized as it starts a new sentence. There's also a trailing space before the period at the end, which should be removed.  

Correct translation:  
Il formato “%s” del file portafoglio fornito non è riconosciuto. Si prega di fornire uno che sia “bdb” o “sqlite”.
```

```
        <source>Cannot resolve -%s address: '%s'</source>
        <translation>Impossobile risolvere l'indirizzo -%s: '%s'</translation>
    
YES
There is a spelling error in the Italian translation: "Impossobile" should be "Impossibile".

Correct translation:
Impossibile risolvere l'indirizzo -%s: '%s'
```

```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>Impossibile rimuovere la directory dello stato della catena dello snapshot (1%s). Rimuovilo manualmente prima di riavviare.
</translation>
    
YES  
The placeholder "%s" in the source is incorrectly translated as "1%s" in the Italian text, which is erroneous. Also, "Rimuovilo" refers to a masculine singular object, but "directory" is feminine in Italian, so it should be "Rimuovila".

Correct translation:  
Impossibile rimuovere la directory dello stato della catena dello snapshot (%s). Rimuovila manualmente prima di riavviare.
```

```
        <source>Transaction requires one destination of non-0 value, a non-0 feerate, or a pre-selected input</source>
        <translation>La transazione richiede una destinazione di valore diverso da -0, una tariffa diversa da -0 o un input preselezionato</translation>
    
YES  
The translation incorrectly uses "-0" to represent "non-0," which is not correct in Italian. The source means "non-zero" value, so it should be translated as "diverso da 0" without the minus sign. Also, "feerate" is a technical term and should be translated clearly, preferably as "tasso di commissione" or "fee rate" kept in English if commonly used. "Tariffa" can be misleading, as it usually means "price" or "rate" in a general sense, while "feerate" in Bitcoin context is specifically the transaction fee rate.

Correct translation:  
La transazione richiede una destinazione con valore diverso da 0, un tasso di commissione diverso da 0 o un input preselezionato
```

```
        <source>Elliptic curve cryptography sanity check failure. %s is shutting down.</source>
        <translation>Errore nel controllo di integrità della crittografia a curva ellittica. %s in spegnimento. </translation>
    
YES  
The phrase "in spegnimento" is not idiomatic Italian for "is shutting down." A more natural and correct translation is "si sta spegnendo" or simply "si sta chiudendo." Also, there is an extra trailing space at the end of the sentence, which should be removed.

Correct translation:  
Errore nel controllo di integrità della crittografia a curva ellittica. %s si sta spegnendo.
```

```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Errore: Ricevuta un valore che non ha hex:%s</translation>
    
YES  
There is a missing space before the format specifier %s in the translation. Also, the phrase "non ha hex" is awkward in Italian; a better translation would use "non era esadecimale" or "non è esadecimale" to clearly convey "was not hex."  

Correct translation:  
Errore: Ricevuto un valore che non era esadecimale: %s
```

```
        <source>Error: No %s addresses available.</source>
        <translation>Errore:  Nessun %s indirizzo disponibile</translation>
    
YES  
There is an extra space after the colon and before "Nessun," and the word order is incorrect. In Italian, the noun usually precedes the adjective, so "indirizzi" (plural of "indirizzo") should be used as well since "No" corresponds to "Nessun" meaning "no" or "none," but in Italian, it implies singular; however, "addresses" is plural and should be plural too. The correct plural form is "indirizzi," and the correct negative form is "Nessun" only for singular masculine nouns; for plural, "Nessun" is not correct—actually, Italian typically uses "Nessun" for singular, but "Nessun indirizzo" (singular) vs. "Nessun indirizzo" (singular). Since the English is plural "addresses," the correct negative plural expression is "Nessun" doesn't have a plural form, so better to use "Nessun" with singular or "Nessun indirizzo" meaning no address, or "Nessun indirizzo %s disponibile." But to mirror the plural English, it's more natural to say "Non ci sono indirizzi %s disponibili." Alternatively, you can rearrange to "Errore: Non ci sono indirizzi %s disponibili."

Also ensure no double spaces.

Correct translation:  
Errore: nessun indirizzo %s disponibile.  

Alternatively, to reflect plural "addresses":  
Errore: nessun indirizzo %s disponibile. (singular, common usage)  
Or:  
Errore: nessun indirizzo %s disponibile.  

Since the source says "addresses," plural, the singular in Italian is typical.

Hence, the corrected translation with proper spacing and order is:  
Errore: nessun indirizzo %s disponibile.

Note the lowercase "nessun" because it follows colon and standard Italian style.

Final correction:  
Errore: nessun indirizzo %s disponibile.
```

```
        <source>Failed to write undo data.</source>
        <translation> 
Errore nella scrittura dei dati di ripristino.</translation>
    
YES  
The translation contains an unnecessary leading whitespace before "Errore". Also, the English "undo data" is correctly rendered as "dati di ripristino" which is appropriate in the Bitcoin context, but the extra whitespace should be removed.

Correct translation:  
Errore nella scrittura dei dati di ripristino.
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>Il tasso di conversione(%s) è inferiore al minore tasso di conversione delle impostazioni(%s)</translation>
    
YES  
The translation is incorrect in terminology and spacing. The English source refers to "Fee rate" which in Bitcoin context means the transaction fee rate, not "tasso di conversione" (conversion rate). Also, there should be a space before each parenthesis. Additionally, "minore" is not the right adjective here; "minimo" (minimum) should be used to match "minimum fee rate setting".

Correct translation:  
Il tasso di commissione (%s) è inferiore all'impostazione del tasso di commissione minimo (%s)
```

```
        <source>Invalid -i2psam address or hostname: '%s'</source>
        <translation>Indirizzo --i2psam o hostname non valido: '%s'</translation>
    
YES  
The source uses a single hyphen for the option "-i2psam", but the translation has a double hyphen "--i2psam". The translation should reflect the single hyphen as in the source to maintain accuracy.

Correct translation:  
Indirizzo -i2psam o hostname non valido: '%s'
```

```
        <source>Signer did not echo address</source>
        <translation>Signer non ha generato un indirizzo di ritorno</translation>
    
YES  
The translation introduces a meaning not present in the source. The English source means the "Signer" did not repeat (echo) the address, not that they generated a return address. Also, "echo address" should be kept as "ripetuto l'indirizzo" or similar, avoiding additional interpretation.

Correct translation:  
Signer non ha ripetuto l'indirizzo
```

```
        <source>System error while saving block to disk: %s</source>
        <translation> 
Errore di sistema in fase di salvataggio del blocco nel disco: %s</translation>
    
YES  
There is unwanted leading whitespace before the translation text. Also, "nel disco" should be "su disco" or "sul disco" for natural Italian.

Correct translation:  
Errore di sistema in fase di salvataggio del blocco su disco: %s
```

```
        <source>Transaction change output index out of range</source>
        <translation>La transazione cambia l' indice dell'output fuori dal limite.</translation>
    
YES  
The translation adds unnecessary words and changes the meaning. The source means that the index of the change output is out of range, but the translation reads as "The transaction changes the output index out of range," which is incorrect. Also, spacing around apostrophes is incorrect in Italian.

Correct translation:  
Indice dell'output del resto della transazione fuori intervallo
```

```
        <source>Unsupported global logging level %s=%s. Valid values: %s.</source>
        <translation>Livello di logging globale non supportato %s=%s. Regole valide: %s.</translation>
    
YES  
The translation incorrectly uses "Regole valide" which means "Valid rules," whereas the source text says "Valid values." The correct Italian word for "values" in this context is "valori."  

Correct translation:  
Livello di logging globale non supportato %s=%s. Valori validi: %s.
```
</details>
