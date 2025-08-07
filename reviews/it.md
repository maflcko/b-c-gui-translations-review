# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>it</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bit%5D%20low%20quality)


```
        <source>Address Fetch</source>
        <extracomment>Short-lived peer connection type that solicits known addresses from a peer.</extracomment>
        <translation>Trova l’indirizzo </translation>
    
YES
The translation "Trova l’indirizzo" means "Find the address", which is not accurate for "Address Fetch" in this context. It also introduces an unnecessary space at the end. The correct translation should reflect the process of fetching or retrieving addresses, not just finding a single address.

Correct translation:
Recupero indirizzi
```

```
        <source>Backup wallet to another location</source>
        <translation>Effettua il backup del portafoglio</translation>
    
YES
The translation omits "to another location," which should be included to match the original meaning.

Correct translation:
Effettua il backup del portafoglio in un'altra posizione
```

```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>Mostra la lista degli indirizzi di ricezione utilizzati</translation>
    
YES
The translation omits the "and labels" part from the original English source. The correct translation should include "etichette" for "labels".

Correct translation:
Mostra la lista degli indirizzi di ricezione e delle etichette utilizzati
```

```
        <source>Show</source>
        <translation>Scome</translation>
    
YES
The translation is incorrect. "Scome" is not an Italian word, and does not mean "Show". The correct translation is "Mostra".

Correct translation:
Mostra
```

```
        <source>Pre-syncing Headers (%1%)…</source>
        <translation>Pre-sincronizzazione intestazioni  (%1%)…</translation>
    
YES
There is an unwanted extra space before the opening parenthesis in the Italian translation. It should be: "Pre-sincronizzazione intestazioni (%1%)…"

Correct translation:
Pre-sincronizzazione intestazioni (%1%)…
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>L'indirizzo "%1" esiste già come indirizzo di setinazione con l'etichetta "%2" e quindi non può essere aggiunto come indirizzo mittente.</translation>
    
YES
There is a typo in the translation: "setinazione" should be "destinazione". Also, while the meaning is mostly carried over, changing "indirizzo di setinazione" to "indirizzo di ricezione" more accurately reflects "receiving address", and "indirizzo mittente" is fine for "sending address".

Correct translation:
L'indirizzo "%1" esiste già come indirizzo di ricezione con l'etichetta "%2" e quindi non può essere aggiunto come indirizzo mittente.
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Mostra se il proxy SOCK5 di default che p stato fornito è usato per raggiungere i contatti attraverso questo tipo di rete.</translation>
    
YES
There is a typographical error: "che p stato fornito" should be "che è stato fornito". Also, "peers" in this context is better translated as "peer" or "nodi" rather than "contatti". "Di default" is acceptable but "predefinito" is preferable.

Correct translation:
Mostra se il proxy SOCKS5 predefinito fornito è utilizzato per raggiungere i peer attraverso questo tipo di rete.
```

```
        <source>Prune block storage to</source>
        <translation>Modalità "prune": elimina i blocchi dal disco dopo</translation>
    
YES
The translation omits the numeric or size-specifying value that should follow "to" in the source. The source refers to reducing block storage to a certain size, whereas the translation explains pruning generally and not the actionable limit.

Correct translation:
Elimina lo storage dei blocchi fino a
or
Riduci l'archivio dei blocchi a
```

```
        <source>Could not read setting "%1", %2.</source>
        <translation>Non posso leggere l'impostazione "%1", %2,</translation>
    
YES
The Italian translation incorrectly uses "Non posso leggere" ("I cannot read"), which is more personal and less formal than appropriate. The standard for error messages is "Impossibile leggere". Also, the sentence ends with a comma instead of a period, which is inconsistent.

Correct translation:
Impossibile leggere l'impostazione "%1", %2.
```

```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>Transizione Parzialmente Firmata (Binaria)</translation>
    
YES
There is a spelling error in the Italian translation. "Transizione" means "transition" rather than "transaction". The correct term is "Transazione". Additionally, "Binaria" is correct for "Binary".

Correct translation:
Transazione Parzialmente Firmata (Binaria)
```

```
        <source>Unban</source>
        <translation>Elimina Ban</translation>
    
YES
The translation "Elimina Ban" is understandable but not the standard or most accurate in Italian for the context of "Unban". A better translation would be simply "Sblocca" or "Rimuovi ban".

Correct translation:
Sblocca
or
Rimuovi ban
```

```
        <source>Ctrl+I</source>
        <translation>Ctrl+W</translation>
    
YES  
The translation is incorrect. "Ctrl+I" should be kept as "Ctrl+I" because keyboard shortcuts do not change between languages unless the application assigns different shortcuts for the Italian version (which is rare). "Ctrl+W" refers to a different keyboard shortcut.

Correct translation:  
Ctrl+I
```

```
        <source>Copy message</source>
        <translation>Copia message</translation>
    
YES
The word "message" is not translated into Italian; it should be "messaggio".

Correct translation:
Copia messaggio
```

```
        <source>Could not generate new %1 address</source>
        <translation>Non è stato possibile generare il nuovo %1 indirizzo</translation>
    
YES
The word order in Italian is incorrect; the adjective "nuovo" should precede the noun "indirizzo". It should be "nuovo indirizzo %1" or more naturally "un nuovo indirizzo %1" if indefinite is appropriate.

Correct translation:
Non è stato possibile generare un nuovo indirizzo %1
```

```
        <source>Inputs…</source>
        <translation>Input...</translation>
    
YES
The word "Inputs…" should be translated as "Input…" is not correct in Italian ('Input' is singular), and the ellipsis characters differ (use the typographical '…' rather than three dots). The correct plural form in Italian could be "Input…" (borrowing the word as invariable, but better would be "Input…" OR "Ingressi…", depending on context—commonly "input" is used in Italian, but "Ingresso" or "Ingressi" is correct for clarity).

Correct translation:
Input…
or
Ingressi…
```

```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>Transizione Parzialmente Firmata (Binaria)</translation>
    
YES
There is a spelling error in the Italian translation. "Transizione" means "transition" rather than "transaction". The correct term is "Transazione". Additionally, "Binaria" is correct for "Binary".

Correct translation:
Transazione Parzialmente Firmata (Binaria)
```

```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Rilevato un indirizzo duplicato Ciascun indirizzo dovrebbe essere utilizzato una sola volta.</translation>
    
YES
There is a missing period after "duplicato" in the Italian translation, which makes the sentence structure off. Also, a comma or period should separate the two clauses.

Correct translation:
Rilevato un indirizzo duplicato: ciascun indirizzo dovrebbe essere utilizzato una sola volta.
```

```
        <source>Confirm custom change address</source>
        <translation>Conferma il cambio di indirizzo</translation>
    
YES
The translation is inaccurate. "change address" in the context of Bitcoin refers to a specific address where the change from a transaction is sent, not "cambio di indirizzo" ("change of address"). The correct translation is:

Conferma l'indirizzo di resto personalizzato
```

```
        <source>Sign Message</source>
        <translation>Firma Messaggio</translation>
    
YES
The translation is not entirely accurate. In Italian, "Firma Messaggio" is awkward and literal; it should be "Firma messaggio" (with a lowercase "m"), or more naturally, "Firma il messaggio".

Correct translation:
Firma il messaggio
```

```
        <source>Sign Message</source>
        <translation>Firma Messaggio</translation>
    
YES
The translation is not entirely accurate. In Italian, "Firma Messaggio" is awkward and literal; it should be "Firma messaggio" (with a lowercase "m"), or more naturally, "Firma il messaggio".

Correct translation:
Firma il messaggio
```

```
        <source>Inputs</source>
        <translation>Input</translation>
    
YES
The translation is incorrect because "Inputs" is plural, but the Italian translation "Input" is singular. The correct plural form in Italian is also "Input" (the word does not change in plural), but in context, it's better to use "Input" for plural, as is common in technical Italian usage. However, "Input" in the plural would still be "Input" without an 's', so technically, the translation is acceptable, but if you want to clarify plurality for Italian speakers, you could use "Ingressi".

Correct translation:
Input

Or alternatively, for more clarity:
Ingressi
```

```
        <source>Copy transaction ID</source>
        <translation>Copia la transazione ID</translation>
    
YES
The translation is not fully accurate. In Italian, "transaction ID" should be translated as "ID della transazione," and the article "la" is unnecessary. The correct translation should be:

Copia l'ID della transazione
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>impossibile aggiornare un portafoglio non diviso e non HD dalla versione %i alla versione %i senza fare l'aggiornamento per supportare il pre-split keypool. Prego usare la versione %i senza specificare la versione</translation>
    
YES
There are two issues:
1. The translation omits "or no version specified" at the end, changing the meaning.
2. Minor stylistic improvement for clarity and formal register.

Correct translation:
Impossibile aggiornare un portafoglio non HD diviso dalla versione %i alla versione %i senza aggiornare per supportare il pre-split keypool. Utilizzare la versione %i oppure nessuna versione specificata.
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>Errore: l'identificativo rispetto la registrazione del dumpfile è incorretta.  ricevuto "%s", sarebbe dovuto essere "%s".</translation>
    
YES
The Italian translation is problematic for several reasons:
- "rispetto la registrazione del dumpfile" is not grammatically correct or natural in Italian.
- There is a double space before "ricevuto".
- "ricevuto" is not capitalized to match the English source.
- The technical term "record" should be kept as "record" (not "registrazione").
- The phrase structure does not reflect the technical tone of the source sentence.

Correct translation:
Errore: il record identificativo del dumpfile non è corretto. Ricevuto "%s", previsto "%s".
```

```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Errore: la versione di questo dumpfile non è supportata. Questa versione del bitcoin-wallet supporta solo la versione 1 dei dumpfile. Ricevuto un dumpfile di versione%s</translation>
    
YES
There is a minor formatting issue: in the phrase "Ricevuto un dumpfile di versione%s", there should be a space between "versione" and the format specifier "%s". Also, "bitcoin-wallet" should not have the article "del", and "dumpfile" should be in Italian quotation marks for clarity, though this is optional.

Correct translation:
Errore: la versione di questo dumpfile non è supportata. Questa versione di bitcoin-wallet supporta solo la versione 1 dei dumpfile. Ricevuto un dumpfile di versione %s
```

```
        <source>File %s already exists. If you are sure this is what you want, move it out of the way first.</source>
        <translation>file %s esistono già. Se desideri continuare comunque, prima rimuovilo.</translation>
    
YES
The translation has some issues:
1. "file %s esistono già" is incorrect. "File" should be capitalized, and "%s" is singular, so the singular form "esiste già" should be used.
2. The translation omits the phrase "If you are sure this is what you want".
3. "move it out of the way" is better translated as "spostalo altrove" rather than "rimuovilo", which means "remove it".

Correct translation:
Il file %s esiste già. Se sei sicuro che sia questo ciò che vuoi, spostalo altrove prima di continuare.
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>Viene fornito più di un indirizzo di associazione onion. L'utilizzo di %s per il servizio Tor onion viene creato automaticamente.</translation>
    
YES
The translation is not accurate and is awkwardly worded in Italian. The English sentence means: if more than one "onion bind address" is given, only one (%s) is used for the automatically created onion service. The translation somewhat distorts the meaning by suggesting that the Tor onion service is created by the act of using %s, and "indirizzo di associazione onion" is an awkward calque.

Correct translation:
Viene fornito più di un indirizzo bind onion. Verrà utilizzato %s per il servizio onion Tor creato automaticamente.
```

```
        <source>No dump file provided. To use createfromdump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>Nessun dump file fornito. Per usare creadumpfile, -dumpfile=&lt;filename&gt; deve essere fornito.</translation>
    
YES
The translation contains an error: "creadumpfile" is incorrect; it should be "createfromdump" as in the source. Also, "dump file" should be rendered in a consistent way – "file di dump" or "dumpfile". There are minor English/Italian consistency issues.

Correct translation:
Nessun file di dump fornito. Per usare createfromdump, -dumpfile=&lt;filename&gt; deve essere fornito.
```

```
        <source>Unknown wallet file format "%s" provided. Please provide one of "bdb" or "sqlite".</source>
        <translation>Il formato “%s” del file portafoglio fornito non è riconosciuto. si prega di fornire uno che sia “bdb” o “sqlite”. </translation>
    
YES
The translation is mostly accurate but has minor issues with capitalization and punctuation. "si prega" should be capitalized as it's the start of a new sentence. Also, it's slightly more natural to write: "Si prega di fornire 'bdb' o 'sqlite'." Furthermore, there is a stray space at the end.

Correct translation:
Il formato "%s" del file portafoglio fornito non è riconosciuto. Si prega di fornire “bdb” o “sqlite”.
```

```
        <source>Cannot resolve -%s address: '%s'</source>
        <translation>Impossobile risolvere l'indirizzo -%s: '%s'</translation>
    
YES
There is a typographical error in the Italian word "Impossobile"; it should be "Impossibile". Additionally, the word order in Italian is generally "Impossibile risolvere l'indirizzo -%s: '%s'", which is correct apart from the typo.

Correct translation:
Impossibile risolvere l'indirizzo -%s: '%s'
```

```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>Impossibile rimuovere la directory dello stato della catena dello snapshot (1%s). Rimuovilo manualmente prima di riavviare.
</translation>
    
YES
There are two issues:

1. The format specifier is incorrect: the source uses (%s), but the translation uses (1%s) — the '1' is extraneous and incorrect.
2. The word 'snapshot' is left untranslated. In Italian, it is often kept as 'snapshot', but can also be translated as 'istantanea'. However, consistent usage is recommended.
3. "lo stato della catena dello snapshot" is an awkward expression in Italian. A better translation would be "catena degli snapshot" or "catena degli stati snapshot".

Correct translation:
Impossibile rimuovere la directory della catena di stato snapshot (%s). Rimuovila manualmente prima di riavviare.
```

```
        <source>Transaction requires one destination of non-0 value, a non-0 feerate, or a pre-selected input</source>
        <translation>La transazione richiede una destinazione di valore diverso da -0, una tariffa diversa da -0 o un input preselezionato</translation>
    
YES
The translation incorrectly says "valore diverso da -0" and "tariffa diversa da -0", which means "value different from -0" and "fee different from -0". The source intends "non-0" as "nonzero" (i.e., not zero), not "not negative zero".

Correct translation:
La transazione richiede una destinazione con valore diverso da zero, una commissione diversa da zero o un input preselezionato.
```

```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Errore: Ricevuta un valore che non ha hex:%s</translation>
    
YES
The Italian translation has grammatical issues and a slightly awkward structure. "Ricevuta" should agree with "valore" (masculine), and "un valore che non ha hex" is not idiomatic. Also, there is a missing space before %s.

Correct translation:
Errore: Ricevuto un valore che non è esadecimale: %s
```

```
        <source>Error: No %s addresses available.</source>
        <translation>Errore:  Nessun %s indirizzo disponibile</translation>
    
YES
There is an unwanted double space after the colon in "Errore:  Nessun %s indirizzo disponibile". Also, in Italian, the adjective "disponibile" should agree in number with "indirizzi" if more than one is implied; since it's "no addresses", plural is correct.

Correct translation:
Errore: Nessun indirizzo %s disponibile.
```

```
        <source>Failed to write undo data.</source>
        <translation> 
Errore nella scrittura dei dati di ripristino.</translation>
    
YES
There is an unwanted leading whitespace in the translation, which should be removed. Otherwise, the translation is accurate.

Correct translation:
Errore nella scrittura dei dati di ripristino.
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>Il tasso di conversione(%s) è inferiore al minore tasso di conversione delle impostazioni(%s)</translation>
    
YES
The translation for "fee rate" as "tasso di conversione" is incorrect; "fee rate" in the context of Bitcoin should be translated as "commissione" or more precisely "commissione per byte" or "commissione per unità". Additionally, "minore tasso" is awkward and should be replaced with "tasso minimo". There is also a missing space before the parentheses.

Correct translation:
Il tasso di commissione (%s) è inferiore al tasso minimo di commissione impostato (%s)
```

```
        <source>Signer did not echo address</source>
        <translation>Signer non ha generato un indirizzo di ritorno</translation>
    
YES
The translation is inaccurate. "Signer non ha generato un indirizzo di ritorno" means "Signer did not generate a return address," which is not the same as "Signer did not echo address." The term "echo" in this context typically means to repeat or send back the same address.

Correct translation:
Il firmatario non ha restituito l'indirizzo
```

```
        <source>System error while saving block to disk: %s</source>
        <translation> 
Errore di sistema in fase di salvataggio del blocco nel disco: %s</translation>
    
YES
There is an unwanted leading whitespace/newline before the translation text. Otherwise, the translation is accurate and the format specifier is correctly transferred.

Correct translation:
Errore di sistema in fase di salvataggio del blocco nel disco: %s
```

```
        <source>Transaction change output index out of range</source>
        <translation>La transazione cambia l' indice dell'output fuori dal limite.</translation>
    
YES
The translation is awkward and incorrect. In Italian, "change" as noun in Bitcoin context should not be translated as the verb "cambia" but as "resto". Also, there should not be a space after the apostrophe, and the phrase structure should follow the original for clarity. 

Correct translation:
Indice dell’output di resto della transazione fuori dall’intervallo
```

```
        <source>Unsupported global logging level %s=%s. Valid values: %s.</source>
        <translation>Livello di logging globale non supportato %s=%s. Regole valide: %s.</translation>
    
YES
The translation of "Valid values: %s." as "Regole valide: %s." is inaccurate. The correct translation should be "Valori validi: %s." since "Regole" means "rules" and not "values".

Correct translation:
Livello di logging globale non supportato %s=%s. Valori validi: %s.
```
</details>

Number of issues: 40.
