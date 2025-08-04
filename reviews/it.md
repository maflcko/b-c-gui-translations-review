# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>it</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bit%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation>Click destro del mouse per modificare l'indirizzo oppure l'etichetta</translation>
    
YES, the translation is problematic because "Click destro del mouse" is not standard Italian. The correct phrase would be "Fare clic con il tasto destro del mouse".

NO.
Click destro del mouse per modificare l'indirizzo oppure l'etichetta
```

```
        <source>Address Fetch</source>
        <extracomment>Short-lived peer connection type that solicits known addresses from a peer.</extracomment>
        <translation>Trova l’indirizzo </translation>
    
YES
The translation is a literal translation that does not capture the nuance of the original English. "Address Fetch" in the context of Bitcoin refers to the process of retrieving a list of known addresses from a peer, not just finding a single address. A more appropriate translation would be "Recupero indirizzi".

YES
The translation "Trova l’indirizzo" is too literal and doesn't accurately convey the meaning of "Address Fetch" in the context of Bitcoin, which implies retrieving a list of addresses rather than finding a single one.

Correct translation: Recupero indirizzi
```

```
        <source>Backup wallet to another location</source>
        <translation>Effettua il backup del portafoglio</translation>
    
YES - The translation is missing the phrase "to another location".
Correct translation: Effettua il backup del portafoglio in un'altra posizione
```

```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>Mostra la lista degli indirizzi di ricezione utilizzati</translation>
    
YES - The translation is missing "and labels".
Mostra la lista degli indirizzi e delle etichette di ricezione utilizzati
```

```
        <source>Show</source>
        <translation>Scome</translation>
    
YES. The word "Scome" is not a valid Italian word. The correct translation for "Show" in this context would be "Mostra".
Scome
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Mostra scheda Nodi</translation>
    
YES: The translation is inaccurate. The source text translates to "Show Peers tab", but the translation translates to "Show Nodes tab". The correct translation for "Show Peers tab" is "Mostra scheda Peer".
NO
```

```
        <source>Pre-syncing Headers (%1%)…</source>
        <translation>Pre-sincronizzazione intestazioni  (%1%)…</translation>
    
YES, The translation has a spacing issue. There is an extra space between "intestazioni" and "(%1%)". The correct translation should be "Pre-sincronizzazione intestazioni (%1%)…".
```

```
        <source>Copy fee</source>
        <translation>Copia commissione</translation>
    
YES, The Italian translation "Copia commissione" is grammatically incorrect. The noun "commissione" is feminine, so the adjective "copia" should be "copiata".

Copia commissione
Copiata commissione
```

```
        <source>Create wallet warning</source>
        <translation>Crea un avviso di portafoglio</translation>
    
YES, The translation is inaccurate. The English "Create wallet warning" implies a warning that is being created for a wallet, not a warning that is creating a wallet.
Crea un avviso per il portafoglio
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>L'indirizzo "%1" esiste già come indirizzo di setinazione con l'etichetta "%2" e quindi non può essere aggiunto come indirizzo mittente.</translation>
    
YES, The word "setinazione" is not a valid Italian word. It seems to be a typo for "destinazione" (destination).
L'indirizzo "%1" esiste già come indirizzo di destinazione con l'etichetta "%2" e quindi non può essere aggiunto come indirizzo mittente.
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Mostra se il proxy SOCK5 di default che p stato fornito è usato per raggiungere i contatti attraverso questo tipo di rete.</translation>
    
YES
The translation uses "contatti" which means "contacts" instead of "peers".

Correct translation: Mostra se il proxy SOCKS5 predefinito fornito viene utilizzato per raggiungere i peer tramite questo tipo di rete.
```

```
        <source>Prune block storage to</source>
        <translation>Modalità "prune": elimina i blocchi dal disco dopo</translation>
    
YES
The translation is too literal and doesn't capture the nuance of the English phrase "Prune block storage to". In the context of Bitcoin, "prune" refers to deleting old blocks from storage to save space. The Italian translation uses "Modalità 'prune'" which is an awkward literal translation and doesn't convey the action.

A more accurate translation would be:
"Riduci la dimensione della memoria dei blocchi:"
```

```
        <source>The configuration file is used to specify advanced user options which override GUI settings. Additionally, any command-line options will override this configuration file.</source>
        <extracomment>Explanatory text about the priority order of instructions considered by client. The order from high to low being: command-line, configuration file, GUI settings.</extracomment>
        <translation>Il file di configurazione è utilizzato per specificare opzioni utente avanzate che aggirano le impostazioni della GUI. Inoltre qualunque opzione da linea di comando aggirerà il file di configurazione.</translation>
    
YES - The word "aggirano" is used twice and has a different meaning in each instance. In the first instance, "aggirano" should be "sovrascrivono" (override). In the second instance, "aggirano" should also be "sovrascrive" (overrides).

NO - Il file di configurazione è utilizzato per specificare opzioni utente avanzate che sovrascrivono le impostazioni della GUI. Inoltre qualunque opzione da linea di comando sovrascriverà il file di configurazione.
```

```
        <source>Could not read setting "%1", %2.</source>
        <translation>Non posso leggere l'impostazione "%1", %2,</translation>
    
YES - The translation incorrectly uses "Non posso" (I cannot) instead of "Impossibile" (Cannot) to indicate an inability to read the setting. The trailing comma is also incorrect.
Correct translation: Impossibile leggere l'impostazione "%1", %2.
```

```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>Transizione Parzialmente Firmata (Binaria)</translation>
    
YES - The translation uses the incorrect word for "Transaction". The correct word in Italian for transaction is "Transazione".
Transazione Parzialmente Firmata (Binaria)
```

```
        <source>(But no wallet is loaded.)</source>
        <translation>(Ma nessun portafogli è stato caricato.)</translation>
    
YES, The translation contains a grammatical error. The verb "caricato" should agree in gender and number with the noun "portafogli" (which is masculine plural), but it is used in the masculine singular form. The correct translation is "(Ma nessun portafoglio è stato caricato.)".
```

```
        <source>Whether we relay transactions to this peer.</source>
        <translation>Se si trasmettono transazioni a questo peer.</translation>
    
YES, The Italian translation is grammatically incorrect and does not accurately convey the meaning of the English source text.

Correct translation: "Se trasmettiamo transazioni a questo peer."
```

```
        <source>Transaction Relay</source>
        <translation>Relay di transazione</translation>
    
YES
The provided translation is in Indonesian, not Italian.
Relay di transazione
```

```
        <source>Whether we relay addresses to this peer.</source>
        <extracomment>Tooltip text for the Address Relay field in the peer details area, which displays whether we relay addresses to this peer (Yes/No).</extracomment>
        <translation>Se gli indirizzi vengono ritrasmessi o meno a questo peer.</translation>
    
YES. The translation is grammatically incorrect and the meaning is slightly off.
The correct translation should be: "Se inoltriamo gli indirizzi a questo peer."
```

```
        <source>Disconnect</source>
        <translation>Disconnetti</translation>
    
YES
The translation has a typo. The correct translation should be "Disconnetti".
Disconnetti
```

```
        <source>Unban</source>
        <translation>Elimina Ban</translation>
    
YES, The translation is inaccurate and not idiomatic. "Elimina Ban" directly translates to "Eliminate Ban" which is not a natural way to express unbanning someone in Italian.
Correct translation: Sblocca
```

```
        <source>Ctrl+I</source>
        <translation>Ctrl+W</translation>
    
YES, The translation is incorrect. The keyboard shortcut Ctrl+I is not translated correctly. The correct translation for Ctrl+I in Italian is Ctrl+I.
Ctrl+I
```

```
        <source>Copy message</source>
        <translation>Copia message</translation>
    
YES: The Italian word for "message" is "messaggio". The translation "Copia message" uses the English word "message" instead of the Italian equivalent.

Correct translation: Copia messaggio
```

```
        <source>Could not generate new %1 address</source>
        <translation>Non è stato possibile generare il nuovo %1 indirizzo</translation>
    
YES, The word order in the translation is incorrect. The correct translation should be "Non è stato possibile generare un nuovo indirizzo %1".
```

```
        <source>Custom change address</source>
        <translation>Personalizza indirizzo di resto</translation>
    
YES, the translation is problematic because it misses the nuance of "custom" and uses a verb instead of an adjective. "Indirizzo di resto personalizzato" would be a more accurate translation.
YES, the translation is problematic. The source text "Custom change address" uses "Custom" as an adjective modifying "change address". The translation "Personalizza indirizzo di resto" uses "Personalizza" which is the verb "to customize". This changes the meaning from a noun phrase describing a type of address to an imperative command.

The correct translation should be:
YES, indirizzo di resto personalizzato
```

```
        <source>Inputs…</source>
        <translation>Input...</translation>
    
YES: The source text "Inputs…" is in the plural, while the translation "Input..." is in the singular. The correct translation should maintain the plural form.
Input...
```

```
        <source>Copy fee</source>
        <translation>Copia commissione</translation>
    
YES, The Italian translation "Copia commissione" is grammatically incorrect. The noun "commissione" is feminine, so the adjective "copia" should be "copiata".

Copia commissione
Copiata commissione
```

```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>Transizione Parzialmente Firmata (Binaria)</translation>
    
YES - The translation uses the incorrect word for "Transaction". The correct word in Italian for transaction is "Transazione".
Transazione Parzialmente Firmata (Binaria)
```

```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Rilevato un indirizzo duplicato Ciascun indirizzo dovrebbe essere utilizzato una sola volta.</translation>
    
YES: The translation is missing the colon after "duplicato" which is present in the source text. The phrase "Ciascun indirizzo dovrebbe essere utilizzato una sola volta" should be preceded by a colon for proper punctuation and clarity.

Correct translation: Rilevato un indirizzo duplicato: ciascun indirizzo dovrebbe essere utilizzato una sola volta.
```

```
        <source>Confirm custom change address</source>
        <translation>Conferma il cambio di indirizzo</translation>
    
YES, The translation is missing the word "custom". The correct translation should be "Conferma l'indirizzo di cambio personalizzato".
```

```
        <source>Sign Message</source>
        <translation>Firma Messaggio</translation>
    
YES, the translation is grammatically incorrect. The imperative form of "firmare" (to sign) is "firma" for the second-person singular informal, but in Italian, when addressing a user or a command, it is more common to use the infinitive. Also, "Messaggio" should be lowercase in this context.

The correct translation is: Firma il messaggio
```

```
        <source>Sign Message</source>
        <translation>Firma Messaggio</translation>
    
YES, the translation is grammatically incorrect. The imperative form of "firmare" (to sign) is "firma" for the second-person singular informal, but in Italian, when addressing a user or a command, it is more common to use the infinitive. Also, "Messaggio" should be lowercase in this context.

The correct translation is: Firma il messaggio
```

```
        <source>Inputs</source>
        <translation>Input</translation>
    
YES. The English source text "Inputs" is plural, while the Italian translation "Input" is singular. The correct translation should reflect the plural form.

NO
```

```
        <source>Copy transaction ID</source>
        <translation>Copia la transazione ID</translation>
    
YES, The word "transazione" should be "transazione" and the word "ID" should be "ID".
The correct translation is: Copia l'ID della transazione
```

```
        <source>Can't draft transaction.</source>
        <translation>Non è possibile compilare la transazione. </translation>
    
YES, there is a trailing space in the translation.
Non è possibile compilare la transazione.
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>impossibile aggiornare un portafoglio non diviso e non HD dalla versione %i alla versione %i senza fare l'aggiornamento per supportare il pre-split keypool. Prego usare la versione %i senza specificare la versione</translation>
    
YES, The translation is problematic. The last part "Prego usare la versione %i senza specificare la versione" is grammatically incorrect and awkward in Italian. It should be "si prega di usare la versione %i o nessuna versione specificata."

NO
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>Errore: l'identificativo rispetto la registrazione del dumpfile è incorretta.  ricevuto "%s", sarebbe dovuto essere "%s".</translation>
    
YES - The translation uses "rispetto" which is not idiomatic in this context. The translation should also include a space after the comma.
Correct Translation: Errore: l'identificativo della registrazione del dumpfile non è corretto. Ricevuto "%s", previsto "%s".
```

```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Errore: la versione di questo dumpfile non è supportata. Questa versione del bitcoin-wallet supporta solo la versione 1 dei dumpfile. Ricevuto un dumpfile di versione%s</translation>
    
YES, The translation has a whitespace issue. The "%s" format specifier is missing a space before it.
Errore: la versione di questo dumpfile non è supportata. Questa versione del bitcoin-wallet supporta solo la versione 1 dei dumpfile. Ricevuto un dumpfile di versione %s
```

```
        <source>File %s already exists. If you are sure this is what you want, move it out of the way first.</source>
        <translation>file %s esistono già. Se desideri continuare comunque, prima rimuovilo.</translation>
    
YES, erroneous content. The verb "esistono" (exist) is plural, but it should be singular to agree with "file %s".
Correct translation: file %s esiste già. Se desideri continuare comunque, prima rimuovilo.
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>Viene fornito più di un indirizzo di associazione onion. L'utilizzo di %s per il servizio Tor onion viene creato automaticamente.</translation>
    
YES. The translation uses "Viene fornito più di un indirizzo di associazione onion" which translates to "More than one onion bind address is provided". However, the English text says "More than one onion bind address is provided", not that it is "provided". A more accurate translation would be "Viene fornito più di un indirizzo di associazione onion" which translates to "More than one onion bind address is provided".

However, the translation of the second part of the sentence "Using %s for the automatically created Tor onion service." is "L'utilizzo di %s per il servizio Tor onion viene creato automaticamente." This translates to "The use of %s for the Tor onion service is automatically created." This is not what the English sentence intends to convey. The English sentence is stating that the system is using the provided address for the Tor onion service, not that the use itself is being created.

A more accurate translation would be:

<translation>Viene fornito più di un indirizzo di associazione onion. Utilizzo di %s per il servizio Tor onion creato automaticamente.</translation>
```

```
        <source>No dump file provided. To use createfromdump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>Nessun dump file fornito. Per usare creadumpfile, -dumpfile=&lt;filename&gt; deve essere fornito.</translation>
    
YES, the translation has a spelling error in the command name.
Correct translation: Nessun file di dump fornito. Per utilizzare createfromdump, è necessario fornire -dumpfile=<nomefile>.
```

```
        <source>Unknown wallet file format "%s" provided. Please provide one of "bdb" or "sqlite".</source>
        <translation>Il formato “%s” del file portafoglio fornito non è riconosciuto. si prega di fornire uno che sia “bdb” o “sqlite”. </translation>
    
YES, The translation has a spacing error. It has an unnecessary space before the period at the end of the sentence.
Il formato “%s” del file portafoglio fornito non è riconosciuto. Si prega di fornire uno che sia “bdb” o “sqlite”.
```

```
        <source>Cannot resolve -%s address: '%s'</source>
        <translation>Impossobile risolvere l'indirizzo -%s: '%s'</translation>
    
YES - There is a typo in the translation: "Impossobile" should be "Impossibile".
Impossibile risolvere l'indirizzo -%s: '%s'
```

```
        <source>Cannot set -forcednsseed to true when setting -dnsseed to false.</source>
        <translation>Impossibile impostare -forcednsseed a 'vero' se l'impostazione -dnsseed è impostata a 'falso'</translation>
    
YES - The translation uses "vero" and "falso" which are not the standard boolean values in Italian programming contexts. The correct translation should use "true" and "false".

NO
```

```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>Impossibile rimuovere la directory dello stato della catena dello snapshot (1%s). Rimuovilo manualmente prima di riavviare.
</translation>
    
YES, The translation contains an erroneous format specifier. The "%s" in the source text should be translated as "%s" in Italian.
Impossibile rimuovere la directory dello stato della catena dello snapshot (%s). Rimuovilo manualmente prima di riavviare.
```

```
        <source>Fee estimation failed. Fallbackfee is disabled. Wait a few blocks or enable %s.</source>
        <translation>La stima della tariffa non è riuscita. La Commissione di riserva è disabilitata. Attendere qualche blocco o abilitare %s.</translation>
    
YES - The translation is problematic because "Fallbackfee" is a technical term related to Bitcoin fee estimation, and its direct translation to "Commissione di riserva" is not accurate or commonly used in this context. A more appropriate translation would reflect the idea of a fallback or default fee.

Correct translation: La stima della tariffa non è riuscita. La tariffa di fallback è disabilitata. Attendere qualche blocco o abilitare %s.
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>Importo non valido per %s=&lt;amount&gt;: '%s' (deve essere almeno la commissione minrelay di %s per evitare transazioni bloccate)</translation>
    
YES - The translation uses "Importo" for "amount" but the context states that "amount" could refer to a Bitcoin transaction amount or the minrelay fee amount. "Commissione" is used for "fee" but "amount" is also used in relation to the minrelay fee. It is not clear what %s refers to in the translation. The translation uses "minrelay fee" which translates to "commissione minrelay", but it is unclear how the %s refers to this value. The translation should be: "Importo non valido per %s=&lt;amount&gt;: '%s' (deve essere almeno la commissione minrelay di %s per evitare transazioni bloccate)"
```

```
        <source>Transaction requires one destination of non-0 value, a non-0 feerate, or a pre-selected input</source>
        <translation>La transazione richiede una destinazione di valore diverso da -0, una tariffa diversa da -0 o un input preselezionato</translation>
    
YES, the translation has an erroneous translation of "non-0 value". The source text states "non-0 value", which is intended to mean "a value that is not zero". However, the translation uses "valore diverso da -0", which translates to "value different from -0". This is not the intended meaning, and it also introduces a negative sign that was not present in the source text. The correct translation should convey that the value is simply not zero.

NO, "non-0 feerate" is translated as "tariffa diversa da -0". This is also incorrect. "Non-0" should simply mean "not zero" and not include the negative sign.

Here's the corrected translation:
NO, "non-0 value" is translated as "valore diverso da -0", which is incorrect. The correct translation should mean "a value that is not zero". Also, "non-0 feerate" is translated as "tariffa diversa da -0", which is also incorrect. The correct translation should convey that the fee rate is simply not zero.

The corrected translation is:
La transazione richiede una destinazione di valore non zero, una tariffa non zero o un input preselezionato
```

```
        <source>Unexpected legacy entry in descriptor wallet found. Loading wallet %s

The wallet might have been tampered with or created with malicious intent.
</source>
        <translation>Trovato un portafoglio inatteso nel descrittore. Caricamento del portafoglio %s

Il portafoglio potrebbe essere stato manomesso o creato con intento malevolo.
</translation>
    
YES: The Italian translation uses "portafoglio" (wallet) in the first sentence, but the English source text specifies "descriptor wallet." While "portafoglio" can be used to refer to a wallet in a general sense, "descriptor wallet" implies a specific type of wallet based on descriptors. A more accurate translation would preserve this specificity.

Correct translation: Trovato un portafoglio descrittore inatteso. Caricamento del portafoglio %s

Il portafoglio potrebbe essere stato manomesso o creato con intento malevolo.
```

```
        <source>Elliptic curve cryptography sanity check failure. %s is shutting down.</source>
        <translation>Errore nel controllo di integrità della crittografia a curva ellittica. %s in spegnimento. </translation>
    
YES, The translation has an unnecessary trailing space.
<source>Elliptic curve cryptography sanity check failure. %s is shutting down.</source>
<translation>Errore nel controllo di integrità della crittografia a curva ellittica. %s in spegnimento.</translation>
```

```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Errore: Ricevuta un valore che non ha hex:%s</translation>
    
YES - The translation is missing a space before the format specifier.
Error: Ricevuta un valore che non è esadecimale: %s
```

```
        <source>Error: No %s addresses available.</source>
        <translation>Errore:  Nessun %s indirizzo disponibile</translation>
    
YES, The Italian translation has an extra space before "indirizzo". Also, it is missing the plural form of "indirizzo" to match the English source text. The correct translation should be "Errore: Nessun indirizzo %s disponibile.".

NO
```

```
        <source>Error: Unable to write solvable wallet best block locator record</source>
        <translation>Errore: Impossibile scrivere un localizzatore risolvibile del miglior blocco del wallet</translation>
    
YES - The translation is not accurate and is problematic. The Italian translation incorrectly translates "solvable wallet best block locator record" as "localizzatore risolvibile del miglior blocco del wallet". The correct translation should be "record localizzatore del miglior blocco del wallet risolvibile".

The correct translation is:
Errore: Impossibile scrivere un record localizzatore del miglior blocco del wallet risolvibile
```

```
        <source>Error: Unable to write watchonly wallet best block locator record</source>
        <translation>Errore: Impossibile scrivere il localizzatore di sola lettura del miglior blocco del wallet</translation>
    
YES - The translation is problematic as it incorrectly translates "watchonly wallet" as "localizzatore di sola lettura del wallet". The correct translation should be "wallet di sola visualizzazione" or "wallet di sola visione".

Errore: Impossibile scrivere il record del localizzatore del miglior blocco per il wallet di sola visualizzazione
```

```
        <source>Failed to write undo data.</source>
        <translation> 
Errore nella scrittura dei dati di ripristino.</translation>
    
YES. The translation has an extraneous leading space and a trailing newline. The translation of "undo data" to "dati di ripristino" is acceptable in the context of Bitcoin.

NO.
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>Il tasso di conversione(%s) è inferiore al minore tasso di conversione delle impostazioni(%s)</translation>
    
YES, The translation is problematic because "tasso di conversione" which means "exchange rate" is an incorrect translation of "fee rate" which means "tasso di commissione" or "tariffa". The correct translation is:
Il tasso di commissione (%s) è inferiore al tasso di commissione minimo impostato (%s)
```

```
        <source>Invalid -i2psam address or hostname: '%s'</source>
        <translation>Indirizzo --i2psam o hostname non valido: '%s'</translation>
    
YES, The translation includes an extraneous `--` before the `i2psam` argument. The correct translation should be: Indirizzo i2psam o hostname non valido: '%s'
```

```
        <source>Signer did not echo address</source>
        <translation>Signer non ha generato un indirizzo di ritorno</translation>
    
YES, The translation is inaccurate. The original English "Signer did not echo address" implies that the signer failed to repeat or confirm the provided address, which is a security measure. The Italian translation "Signer non ha generato un indirizzo di ritorno" means "Signer did not generate a return address," which is a different concept.

Correct translation: Signer non ha restituito l'indirizzo
```

```
        <source>Signing transaction failed</source>
        <translation>Firma transazione fallita</translation>
    
YES
The Italian translation is grammatically incorrect. The correct translation should be "Firma transazione fallita" or "Errore durante la firma della transazione".

The user provided "Firma transazione fallita". This is grammatically incorrect.
The correct translation should be "Firma della transazione fallita".

NO
```

```
        <source>System error while saving block to disk: %s</source>
        <translation> 
Errore di sistema in fase di salvataggio del blocco nel disco: %s</translation>
    
YES. The translation has a leading space character before the text.
Errore di sistema in fase di salvataggio del blocco nel disco: %s
```

```
        <source>Transaction change output index out of range</source>
        <translation>La transazione cambia l' indice dell'output fuori dal limite.</translation>
    
YES: The translation is grammatically incorrect. "cambia l'indice dell'output" implies the transaction itself is changing the index, when it should be referring to the index of the change output.

The correct translation is: "Indice dell'output di resto della transazione fuori intervallo."
```

```
        <source>Unsupported global logging level %s=%s. Valid values: %s.</source>
        <translation>Livello di logging globale non supportato %s=%s. Regole valide: %s.</translation>
    
YES: The translation incorrectly uses "Regole valide" (Valid rules) instead of "Valori validi" (Valid values).
Correct translation: Livello di logging globale non supportato %s=%s. Valori validi: %s.
```
</details>
