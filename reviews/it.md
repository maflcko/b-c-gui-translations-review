# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>it</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bit%5D%20request)


<!-- cache_translation_check_it_5d43a64ea3e3e2e5e23b65c179d0d4b35a69527189f532ac9e02b534ecaeab70 -->
```
        <source>C&amp;lose</source>
        <translation>Chiudere</translation>
    
ERR
The Italian translation does not preserve the shortcut key indicator (&) from the source. It should appear exactly once in the translation.

Correct translation:
&Chiudere
or
C&hiudere

(Either placement is acceptable as long as there is exactly one '&' for the shortcut key.)
```

<!-- cache_translation_check_it_c1511ad78d2827091f7d0cb7b1687862a681c0ba8b748f0280bf4cdf50c24784 -->
```
        <source>C&amp;hoose</source>
        <translation>Scegli</translation>
    
ERR
The translation omits the ampersand (&), which is used for shortcut keys. The '&' should appear exactly once in the translation.

Correct translation:
&Scegli
```

<!-- cache_translation_check_it_ca604b1e0da264b211ce54392857780e2b5e2fec842541aa988523656ba0272c -->
```
        <source>Address Fetch</source>
        <extracomment>Short-lived peer connection type that solicits known addresses from a peer.</extracomment>
        <translation>Trova l’indirizzo </translation>
    
ERR
The translation "Trova l’indirizzo" means "Find the address", which is not accurate for "Address Fetch" in this context. It also introduces an unnecessary space at the end. The correct translation should reflect the process of fetching or retrieving addresses, not just finding a single address.

Correct translation:
Recupero indirizzi
```

<!-- cache_translation_check_it_39f1a5cfadbc20edf10ded7beb433b903e908fce887948c56f98c60a4cdebf41 -->
```
        <source>Backup wallet to another location</source>
        <translation>Effettua il backup del portafoglio</translation>
    
ERR
The translation omits "to another location," which should be included to match the original meaning.

Correct translation:
Effettua il backup del portafoglio in un'altra posizione
```

<!-- cache_translation_check_it_843f869ea4d8f044a0faaefc6aeb96371441fb77308e3bcadec4329bbc8125ae -->
```
        <source>&amp;Options…</source>
        <translation>Opzioni</translation>
    
ERR
The translation omits the '&' which is used in English and should appear exactly once in the Italian translation as it indicates the shortcut key. The ellipsis ("…") is also missing in the translation.

Correct translation:
&Opzioni…
```

<!-- cache_translation_check_it_1a5e4350f0d30cdae0a5fb50e20428afed96535ddf9077694f4923565ce6bc06 -->
```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>Mostra la lista degli indirizzi di ricezione utilizzati</translation>
    
ERR
The translation omits the "and labels" part from the original English source. The correct translation should include "etichette" for "labels".

Correct translation:
Mostra la lista degli indirizzi di ricezione e delle etichette utilizzati
```

<!-- cache_translation_check_it_90ffb2944fcbfa596e3bb0b4709e0b239306e275da6c3c66e351ccb45d646f92 -->
```
        <source>&amp;Sending addresses</source>
        <translation>Indirizzi &amp;mittenti</translation>
    
ERR
The translation reverses the meaning; "&amp;Sending addresses" refers to addresses the user is sending to (i.e., "receiving" addresses from the user's perspective), not addresses that are sending.

Correct translation:
Indirizzi &amp;di invio
```

<!-- cache_translation_check_it_0ac1ff1dd68d64106a6f9b8d80de7421e49b2cf3ff80d12e4817b8e6749b8ccf -->
```
        <source>&amp;Receiving addresses</source>
        <translation>Indirizzi di &amp;destinazione</translation>
    
ERR
The translation is inaccurate. In Bitcoin context, "receiving addresses" means wallet addresses where you receive coins. "Indirizzi di destinazione" is ambiguous and more like "destination addresses". The correct translation is:

Indirizzi di &amp;ricezione
```

<!-- cache_translation_check_it_54e7395343ab757faa2eae676cd7612280051fe24ecf8c7c00bfed572fad004f -->
```
        <source>S&amp;how</source>
        <translation>S&amp;come</translation>
    
ERR
The translation "S&come" is incorrect. "Show" should be translated as "Mostra" in Italian. The ampersand (&) is correctly preserved for the shortcut key.

Correct translation:
&Mostra
```

<!-- cache_translation_check_it_b8f5486c73f6eb53606d37cdc3115b0e5b17589102bb4a3bfab93a2b353957b7 -->
```
        <source>Pre-syncing Headers (%1%)…</source>
        <translation>Pre-sincronizzazione intestazioni  (%1%)…</translation>
    
ERR
There is an unwanted extra space before the opening parenthesis in the Italian translation. It should be: "Pre-sincronizzazione intestazioni (%1%)…"

Correct translation:
Pre-sincronizzazione intestazioni (%1%)…
```

<!-- cache_translation_check_it_44b738f55953720fb1bfb41bd85c7d7495053c04d4f234af2c73d2fafdcef370 -->
```
        <source>Copy &amp;amount</source>
        <translation>Copi&amp;a importo</translation>
    
ERR
In the Italian translation, the ampersand indicating the shortcut key is misplaced inside the word "Copia". It should precede a relevant character, and "importo" should not be separated unnaturally from "Copia". The spacing is also awkward.

Correct translation:
&Copia importo
```

<!-- cache_translation_check_it_c13cc791c657d5409830227d5c998ad5a9f1852b479ba710fcc9e236ff557c21 -->
```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>L'indirizzo "%1" esiste già come indirizzo di setinazione con l'etichetta "%2" e quindi non può essere aggiunto come indirizzo mittente.</translation>
    
ERR
There is a typo in the translation: "setinazione" should be "destinazione". Also, while the meaning is mostly carried over, changing "indirizzo di setinazione" to "indirizzo di ricezione" more accurately reflects "receiving address", and "indirizzo mittente" is fine for "sending address".

Correct translation:
L'indirizzo "%1" esiste già come indirizzo di ricezione con l'etichetta "%2" e quindi non può essere aggiunto come indirizzo mittente.
```

<!-- cache_translation_check_it_88c074635f393ee164518e167602740051a00d1fef1c6d3af2afaee2c305d617 -->
```
        <source>&amp;Start %1 on system login</source>
        <translation>&amp;Start %1 all'accesso al sistema</translation>
    
ERR
The word "Start" is not translated into Italian. It should be "Avvia". The ampersand is present only once, as required.

Correct translation:
&Avvia %1 all'accesso al sistema
```

<!-- cache_translation_check_it_5c8ffda95384b6d6ab51428fb55f8f2e4fce0f7791edd1170131a5f8244f13be -->
```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Mostra se il proxy SOCK5 di default che p stato fornito è usato per raggiungere i contatti attraverso questo tipo di rete.</translation>
    
ERR
There is a typographical error: "che p stato fornito" should be "che è stato fornito". Also, "peers" in this context is better translated as "peer" or "nodi" rather than "contatti". "Di default" is acceptable but "predefinito" is preferable.

Correct translation:
Mostra se il proxy SOCKS5 predefinito fornito è utilizzato per raggiungere i peer attraverso questo tipo di rete.
```

<!-- cache_translation_check_it_05e3b074672fcc474fb076d0482b98aa418de0c97ef90bba41057c8fcad7774e -->
```
        <source>&amp;Network</source>
        <translation>Rete</translation>
    
ERR
The ampersand (&) indicating the shortcut key is missing in the Italian translation. It must appear exactly once.

Correct translation:
&Network

or, if localizing the shortcut to a relevant Italian letter:

& Rete

(Rete)
```

<!-- cache_translation_check_it_3a3ad3bc6b16ab8c057b8afe3d1db56e315a2ef1f8819e7d5d851fb41e3ee7c0 -->
```
        <source>Prune &amp;block storage to</source>
        <translation>Modalità "prune": elimina i blocchi dal disco dopo</translation>
    
ERR
The Italian translation does not accurately reflect the English source. The source talks about "Prune &block storage to", i.e., pruning (reducing) the blockchain storage to a certain size, and includes the shortcut key (&). The translation omits both the storage size and the shortcut, and paraphrases imprecisely.

Correct translation:
Pruna &archiviazione dei blocchi a

Or, to be more natural:
Riduci &archiviazione dei blocchi a

(Be sure to retain the & for the shortcut key.)
```

<!-- cache_translation_check_it_15b7541c81257a1a9462cb536f7c6076b0b3b5aad1f7b8a3649c430c1d9904bc -->
```
        <source>Enable coin &amp;control features</source>
        <translation>Abilita le funzionalità di coin &amp;control</translation>
    
ERR
The shortcut key (&) is not adapted for Italian. In the Italian translation, the shortcut should be positioned on the relevant letter in the corresponding Italian word (usually "controllo" for "control"), and the English word "coin control" is often translated as "controllo delle monete" or "controllo delle coin" depending on the context. Also, a direct Anglicism should be avoided if possible.

Correct translation:
Abilita le funzionalità di &controllo delle monete
```

<!-- cache_translation_check_it_d195d27e6eae52256c7cc01d8479e09c0846a4455d29d2eaa9b5e6d197eca0dc -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Accetta connessioni in entrata</translation>
    
ERR
The translation omits the shortcut key indicator '&' from the source, which should appear exactly once in the translation. Additionally, "Allow" should be accurately translated as "Consenti" instead of "Accetta".

Correct translation:
Consenti connes&ssioni in entrata
```

<!-- cache_translation_check_it_048d946718d10291c256bfd0153ff15a4606e031656c3a3729866620b47c07f1 -->
```
        <source>&amp;Show tray icon</source>
        <translation>&amp;Mostra l'icona</translation>
    
ERR
The Italian translation omits "tray" ("area di notifica" or "barra delle applicazioni"), losing the specific meaning ("tray icon" refers to the system tray or notification area icon). 

Correct translation:
&Mostra l'icona nell'area di notifica
```

<!-- cache_translation_check_it_a2e6cfff61a3c5aa04d6f9804c49ed60f0ff24aa999b7891a6468ab86807d556 -->
```
        <source>Could not read setting "%1", %2.</source>
        <translation>Non posso leggere l'impostazione "%1", %2,</translation>
    
ERR
The Italian translation incorrectly uses "Non posso leggere" ("I cannot read"), which is more personal and less formal than appropriate. The standard for error messages is "Impossibile leggere". Also, the sentence ends with a comma instead of a period, which is inconsistent.

Correct translation:
Impossibile leggere l'impostazione "%1", %2.
```

<!-- cache_translation_check_it_4df2e937e438ce0c145a17b19249eeab2dd6bf712420f9af66196e0ff588d51b -->
```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>Transizione Parzialmente Firmata (Binaria)</translation>
    
ERR
There is a spelling error in the Italian translation. "Transizione" means "transition" rather than "transaction". The correct term is "Transazione". Additionally, "Binaria" is correct for "Binary".

Correct translation:
Transazione Parzialmente Firmata (Binaria)
```

<!-- cache_translation_check_it_4f2f9b36086e82689100257866b47ba0ffbef5013332621beb25af4024f21182 -->
```
        <source>&amp;Peers</source>
        <translation>&amp;Peer</translation>
    
ERR
The translation is incorrect: the English plural "&amp;Peers" is rendered as the Italian singular "&amp;Peer". The correct Italian translation should use the plural form.

Correct translation:
&amp;Peer
OR
&amp;Peer

However, "Peer" is often left untranslated in Italian technical contexts, and the plural of "peer" in Italian can remain "peer" (indeclinabile) or "peer" can sometimes be "pari". Given the context, if "Peer" is adopted as a loanword, the plural does not change (i.e., "Peer" for both singular and plural), so the translation may be acceptable in context. 

But if we want to be more accurate, and use Italian, the plural for "peer" (in this context) could be "pari".

So, possible better translations:
&amp;Peer (acceptable in technical contexts)
OR
&amp;Pari (if fully Italianized)

Given the ambiguity and accepted use in technical Italian, accepting "&amp;Peer" may not be considered an error. Therefore, the original translation can be accepted as "NO".

But considering the strict prompt on plural, the more explanatory answer is:

ERR
"Peers" is plural; the translation keeps the singular. Italian technical usage often leaves "peer" unchanged in plural, so "&amp;Peer" may be acceptable, but if pluralization is required, consider "&amp;Peer" or "&amp;Pari".

Correct translation (if pluralization is needed):
&amp;Peer
```

<!-- cache_translation_check_it_72b797f6442b5552e80ee06a73ab17ca613d20e2c6330b9f6ff42a6739f8c240 -->
```
        <source>Ctrl+I</source>
        <translation>Ctrl+W</translation>
    
ERR  
The translation is incorrect. "Ctrl+I" should be kept as "Ctrl+I" because keyboard shortcuts do not change between languages unless the application assigns different shortcuts for the Italian version (which is rare). "Ctrl+W" refers to a different keyboard shortcut.

Correct translation:  
Ctrl+I
```

<!-- cache_translation_check_it_499b9240c8cced95d0a7ed726fe468d761584ca941549ef0c293d60e799582c5 -->
```
        <source>&amp;Create new receiving address</source>
        <translation>Crea nuovo indirizzo ricevente.</translation>
    
ERR
The translation omits the ampersand (&) used for the shortcut key. It also adds an unnecessary period at the end and does not preserve the format exactly (the English omits a period). The phrase "indirizzo ricevente" is understandable but "indirizzo di ricezione" or simply "nuovo indirizzo di ricezione" would be more idiomatic in Italian.

Correct translation:
&Crea nuovo indirizzo di ricezione
```

<!-- cache_translation_check_it_398cad6677a56d354833f04dce0230e58d477427ded89cb3303b37858e689645 -->
```
        <source>Copy &amp;message</source>
        <translation>Copia &amp;message</translation>
    
ERR
The English 'message' was not translated into Italian; it should be 'messaggio'. Otherwise, the ampersand is correct and preserved once.

Correct translation:
Copia &amp;messaggio
```

<!-- cache_translation_check_it_44b738f55953720fb1bfb41bd85c7d7495053c04d4f234af2c73d2fafdcef370 -->
```
        <source>Copy &amp;amount</source>
        <translation>Copi&amp;a importo</translation>
    
ERR
In the Italian translation, the ampersand indicating the shortcut key is misplaced inside the word "Copia". It should precede a relevant character, and "importo" should not be separated unnaturally from "Copia". The spacing is also awkward.

Correct translation:
&Copia importo
```

<!-- cache_translation_check_it_688abbebdcdd0f219f1185363a5d92bda8fccaee7abcd4aa5b0ae10e68be8fc0 -->
```
        <source>Could not generate new %1 address</source>
        <translation>Non è stato possibile generare il nuovo %1 indirizzo</translation>
    
ERR
The word order in Italian is incorrect; the adjective "nuovo" should precede the noun "indirizzo". It should be "nuovo indirizzo %1" or more naturally "un nuovo indirizzo %1" if indefinite is appropriate.

Correct translation:
Non è stato possibile generare un nuovo indirizzo %1
```

<!-- cache_translation_check_it_8421c5a3480d8c50c84dcc758a0ecea111c97a331e8f95346d3111362ec76703 -->
```
        <source>Copy &amp;Address</source>
        <translation>Copi&amp;a Indirizzo</translation>
    
ERR
The ampersand (&) for the shortcut key is attached to the "a" in "Copia", creating "Copi&a", which is incorrect and breaks the intended shortcut. The ampersand should be attached to the "I" in "Indirizzo" or the "C" in "Copia" to create a meaningful shortcut.

Correct translation:
Copia &Indirizzo

Alternatively, if you want the shortcut on "C":
&Copia indirizzo

(both are accepted conventions, but never split a word with "&")
```

<!-- cache_translation_check_it_71ef9ceb75d11b8e6a53f653ea70b74bc44605f44a580334fc55ba16fa506e4e -->
```
        <source>Inputs…</source>
        <translation>Input...</translation>
    
ERR
The word "Inputs…" should be translated as "Input…" is not correct in Italian ('Input' is singular), and the ellipsis characters differ (use the typographical '…' rather than three dots). The correct plural form in Italian could be "Input…" (borrowing the word as invariable, but better would be "Input…" OR "Ingressi…", depending on context—commonly "input" is used in Italian, but "Ingresso" or "Ingressi" is correct for clarity).

Correct translation:
Input…
or
Ingressi…
```

<!-- cache_translation_check_it_6573f0732314ff7326ae0677549599051a2e57451623c713334cc6fe5391a425 -->
```
        <source>Cr&amp;eate Unsigned</source>
        <translation>Cr&amp;ea Non Firmata</translation>
    
ERR
The translation is awkward and not fully correct. "Creare" is the correct verb in Italian, and "Non Firmata" (feminine) doesn't agree since "transazione" would need to be present. Also, "Unsigned" is likely referring to "Create Unsigned Transaction", so context should be maintained.

Correct translation:
Cr&amp;ea non firmata

Alternatively, if the full context is "Create Unsigned Transaction", it should be:
Cr&amp;ea transazione non firmata
```

<!-- cache_translation_check_it_4df2e937e438ce0c145a17b19249eeab2dd6bf712420f9af66196e0ff588d51b -->
```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>Transizione Parzialmente Firmata (Binaria)</translation>
    
ERR
There is a spelling error in the Italian translation. "Transizione" means "transition" rather than "transaction". The correct term is "Transazione". Additionally, "Binaria" is correct for "Binary".

Correct translation:
Transazione Parzialmente Firmata (Binaria)
```

<!-- cache_translation_check_it_9ae69f3bf17367feed7521b59766fdf63c9a85e0946a4803edb2cafe7d676b80 -->
```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Rilevato un indirizzo duplicato Ciascun indirizzo dovrebbe essere utilizzato una sola volta.</translation>
    
ERR
There is a missing period after "duplicato" in the Italian translation, which makes the sentence structure off. Also, a comma or period should separate the two clauses.

Correct translation:
Rilevato un indirizzo duplicato: ciascun indirizzo dovrebbe essere utilizzato una sola volta.
```

<!-- cache_translation_check_it_3dc526f0d9f11cd6aca29b38e73e306cd7e8f0be07fb27b028087b175f504a09 -->
```
        <source>Confirm custom change address</source>
        <translation>Conferma il cambio di indirizzo</translation>
    
ERR
The translation is inaccurate. "change address" in the context of Bitcoin refers to a specific address where the change from a transaction is sent, not "cambio di indirizzo" ("change of address"). The correct translation is:

Conferma l'indirizzo di resto personalizzato
```

<!-- cache_translation_check_it_4ab31582452ee8e08139b38b207ffafa1af327c30fdf5320a672524bcbd4a3c7 -->
```
        <source>Inputs</source>
        <translation>Input</translation>
    
ERR
The translation is incorrect because "Inputs" is plural, but the Italian translation "Input" is singular. The correct plural form in Italian is also "Input" (the word does not change in plural), but in context, it's better to use "Input" for plural, as is common in technical Italian usage. However, "Input" in the plural would still be "Input" without an 's', so technically, the translation is acceptable, but if you want to clarify plurality for Italian speakers, you could use "Ingressi".

Correct translation:
Input

Or alternatively, for more clarity:
Ingressi
```

<!-- cache_translation_check_it_44b738f55953720fb1bfb41bd85c7d7495053c04d4f234af2c73d2fafdcef370 -->
```
        <source>Copy &amp;amount</source>
        <translation>Copi&amp;a importo</translation>
    
ERR
In the Italian translation, the ampersand indicating the shortcut key is misplaced inside the word "Copia". It should precede a relevant character, and "importo" should not be separated unnaturally from "Copia". The spacing is also awkward.

Correct translation:
&Copia importo
```

<!-- cache_translation_check_it_7a6d2eeb74459837a3f06f9f15a38ea044c7b684aac745beeadadb29efc90197 -->
```
        <source>Copy full transaction &amp;details</source>
        <translation>Copia tutti i dettagli &amp;della transazione </translation>
    
ERR
There is a whitespace issue: there is an extra space at the end of the Italian translation. Additionally, the position of the '&amp;' may not be optimal for shortcut keys in Italian (it should ideally be placed before the first suitable shortcut letter for accessibility), but since '&amp;' is present exactly once, this is not an error per instruction.

Correct translation:
Copia tutti i dettagli &amp;della transazione
```

<!-- cache_translation_check_it_62926500cb494677748649f119ad63c67bf7f932c1fe1f3db3618770f1950dfc -->
```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>Errore: l'identificativo rispetto la registrazione del dumpfile è incorretta.  ricevuto "%s", sarebbe dovuto essere "%s".</translation>
    
ERR
The Italian translation is problematic for several reasons:
- "rispetto la registrazione del dumpfile" is not grammatically correct or natural in Italian.
- There is a double space before "ricevuto".
- "ricevuto" is not capitalized to match the English source.
- The technical term "record" should be kept as "record" (not "registrazione").
- The phrase structure does not reflect the technical tone of the source sentence.

Correct translation:
Errore: il record identificativo del dumpfile non è corretto. Ricevuto "%s", previsto "%s".
```

<!-- cache_translation_check_it_f97fe792e1d5b64e301d031fc6e02ae5b35007d3de372a1ead31e0d1334d1ea1 -->
```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Errore: la versione di questo dumpfile non è supportata. Questa versione del bitcoin-wallet supporta solo la versione 1 dei dumpfile. Ricevuto un dumpfile di versione%s</translation>
    
ERR
There is a minor formatting issue: in the phrase "Ricevuto un dumpfile di versione%s", there should be a space between "versione" and the format specifier "%s". Also, "bitcoin-wallet" should not have the article "del", and "dumpfile" should be in Italian quotation marks for clarity, though this is optional.

Correct translation:
Errore: la versione di questo dumpfile non è supportata. Questa versione di bitcoin-wallet supporta solo la versione 1 dei dumpfile. Ricevuto un dumpfile di versione %s
```

<!-- cache_translation_check_it_d8d366456f33e5338375df30654a15e397f20e5302cd75a53ed05733055d5c1c -->
```
        <source>File %s already exists. If you are sure this is what you want, move it out of the way first.</source>
        <translation>file %s esistono già. Se desideri continuare comunque, prima rimuovilo.</translation>
    
ERR
The translation has some issues:
1. "file %s esistono già" is incorrect. "File" should be capitalized, and "%s" is singular, so the singular form "esiste già" should be used.
2. The translation omits the phrase "If you are sure this is what you want".
3. "move it out of the way" is better translated as "spostalo altrove" rather than "rimuovilo", which means "remove it".

Correct translation:
Il file %s esiste già. Se sei sicuro che sia questo ciò che vuoi, spostalo altrove prima di continuare.
```

<!-- cache_translation_check_it_adf435d787393d62cf457faa5af4b906e2c3524bad59bcdf4d3466f99fb8dd54 -->
```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>Viene fornito più di un indirizzo di associazione onion. L'utilizzo di %s per il servizio Tor onion viene creato automaticamente.</translation>
    
ERR
The translation is not accurate and is awkwardly worded in Italian. The English sentence means: if more than one "onion bind address" is given, only one (%s) is used for the automatically created onion service. The translation somewhat distorts the meaning by suggesting that the Tor onion service is created by the act of using %s, and "indirizzo di associazione onion" is an awkward calque.

Correct translation:
Viene fornito più di un indirizzo bind onion. Verrà utilizzato %s per il servizio onion Tor creato automaticamente.
```

<!-- cache_translation_check_it_e99983bdbaeb842dce67980a990585151971795300020301b80db1d12230a387 -->
```
        <source>No dump file provided. To use createfromdump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>Nessun dump file fornito. Per usare creadumpfile, -dumpfile=&lt;filename&gt; deve essere fornito.</translation>
    
ERR
The translation contains an error: "creadumpfile" is incorrect; it should be "createfromdump" as in the source. Also, "dump file" should be rendered in a consistent way – "file di dump" or "dumpfile". There are minor English/Italian consistency issues.

Correct translation:
Nessun file di dump fornito. Per usare createfromdump, -dumpfile=&lt;filename&gt; deve essere fornito.
```

<!-- cache_translation_check_it_a84e799399ed3ce3a725076482cc0ae545cda33e013f2f97c0d3cf0628343281 -->
```
        <source>Cannot resolve -%s address: '%s'</source>
        <translation>Impossobile risolvere l'indirizzo -%s: '%s'</translation>
    
ERR
There is a typographical error in the Italian word "Impossobile"; it should be "Impossibile". Additionally, the word order in Italian is generally "Impossibile risolvere l'indirizzo -%s: '%s'", which is correct apart from the typo.

Correct translation:
Impossibile risolvere l'indirizzo -%s: '%s'
```

<!-- cache_translation_check_it_0c44083cbe396aa292841be9c88bcdbe04d4b3d2fec842833d8fac437e4b00fb -->
```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>Impossibile rimuovere la directory dello stato della catena dello snapshot (1%s). Rimuovilo manualmente prima di riavviare.
</translation>
    
ERR
There are two issues:

1. The format specifier is incorrect: the source uses (%s), but the translation uses (1%s) — the '1' is extraneous and incorrect.
2. The word 'snapshot' is left untranslated. In Italian, it is often kept as 'snapshot', but can also be translated as 'istantanea'. However, consistent usage is recommended.
3. "lo stato della catena dello snapshot" is an awkward expression in Italian. A better translation would be "catena degli snapshot" or "catena degli stati snapshot".

Correct translation:
Impossibile rimuovere la directory della catena di stato snapshot (%s). Rimuovila manualmente prima di riavviare.
```

<!-- cache_translation_check_it_41858317ed6e2297faebec9e7d2033ef683b33b6ab3e83e03f97db53e6d3509b -->
```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Errore: Ricevuta un valore che non ha hex:%s</translation>
    
ERR
The Italian translation has grammatical issues and a slightly awkward structure. "Ricevuta" should agree with "valore" (masculine), and "un valore che non ha hex" is not idiomatic. Also, there is a missing space before %s.

Correct translation:
Errore: Ricevuto un valore che non è esadecimale: %s
```

<!-- cache_translation_check_it_ac6c4fb65678c74f40fbbfe46c110222bc82f24dbe7b4b8fc2fb497ae201a3af -->
```
        <source>Error: No %s addresses available.</source>
        <translation>Errore:  Nessun %s indirizzo disponibile</translation>
    
ERR
There is an unwanted double space after the colon in "Errore:  Nessun %s indirizzo disponibile". Also, in Italian, the adjective "disponibile" should agree in number with "indirizzi" if more than one is implied; since it's "no addresses", plural is correct.

Correct translation:
Errore: Nessun indirizzo %s disponibile.
```

<!-- cache_translation_check_it_62417059ee2698d18d80d5949d6e300c96b45ea2786ed07e7cc022472fa2a72a -->
```
        <source>Failed to write undo data.</source>
        <translation> 
Errore nella scrittura dei dati di ripristino.</translation>
    
ERR
There is an unwanted leading whitespace in the translation, which should be removed. Otherwise, the translation is accurate.

Correct translation:
Errore nella scrittura dei dati di ripristino.
```

<!-- cache_translation_check_it_2ebc1ce5139e4de15c589a33d9ffb50d1592b2fedef8e97c3fe7436d4dc85213 -->
```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>Il tasso di conversione(%s) è inferiore al minore tasso di conversione delle impostazioni(%s)</translation>
    
ERR
The translation for "fee rate" as "tasso di conversione" is incorrect; "fee rate" in the context of Bitcoin should be translated as "commissione" or more precisely "commissione per byte" or "commissione per unità". Additionally, "minore tasso" is awkward and should be replaced with "tasso minimo". There is also a missing space before the parentheses.

Correct translation:
Il tasso di commissione (%s) è inferiore al tasso minimo di commissione impostato (%s)
```

<!-- cache_translation_check_it_d4931f23993e077229c20ea214b9222a594e1a4de2c45058c4db451a30bc3f16 -->
```
        <source>Signer did not echo address</source>
        <translation>Signer non ha generato un indirizzo di ritorno</translation>
    
ERR
The translation is inaccurate. "Signer non ha generato un indirizzo di ritorno" means "Signer did not generate a return address," which is not the same as "Signer did not echo address." The term "echo" in this context typically means to repeat or send back the same address.

Correct translation:
Il firmatario non ha restituito l'indirizzo
```

<!-- cache_translation_check_it_d12da9a5a9548a9aafa54b0b8707a3db5637cb88e0d78a1407cd6e616a82e433 -->
```
        <source>System error while saving block to disk: %s</source>
        <translation> 
Errore di sistema in fase di salvataggio del blocco nel disco: %s</translation>
    
ERR
There is an unwanted leading whitespace/newline before the translation text. Otherwise, the translation is accurate and the format specifier is correctly transferred.

Correct translation:
Errore di sistema in fase di salvataggio del blocco nel disco: %s
```

<!-- cache_translation_check_it_8fde11a56e2558a5f792ef390e42f083b75862ee090ce8f1fe8bfec3e9a600f7 -->
```
        <source>Transaction change output index out of range</source>
        <translation>La transazione cambia l' indice dell'output fuori dal limite.</translation>
    
ERR
The translation is awkward and incorrect. In Italian, "change" as noun in Bitcoin context should not be translated as the verb "cambia" but as "resto". Also, there should not be a space after the apostrophe, and the phrase structure should follow the original for clarity. 

Correct translation:
Indice dell’output di resto della transazione fuori dall’intervallo
```

<!-- cache_translation_check_it_77977004de783565ef2831424ec696c4d712c82289d6ba82581ac383152677c4 -->
```
        <source>Unsupported global logging level %s=%s. Valid values: %s.</source>
        <translation>Livello di logging globale non supportato %s=%s. Regole valide: %s.</translation>
    
ERR
The translation of "Valid values: %s." as "Regole valide: %s." is inaccurate. The correct translation should be "Valori validi: %s." since "Regole" means "rules" and not "values".

Correct translation:
Livello di logging globale non supportato %s=%s. Valori validi: %s.
```
</details>

Number of issues: 51.
