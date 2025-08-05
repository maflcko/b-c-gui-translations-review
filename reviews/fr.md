# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>fr</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bfr%5D%20low%20quality)


```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Une erreur est survenue lors de l’enregistrement de la liste d’adresses vers %1. Rréessayez plus tard.</translation>
    
YES
There is a typo in the French translation ("Rréessayez" should be "Réessayez"), and "vers" is less appropriate than "dans" or "sur" in this context when referring to saving to a file.

Correct translation:
Une erreur est survenue lors de l’enregistrement de la liste d’adresses dans %1. Réessayez plus tard.
```

```
        <source>Onion</source>
        <comment>network name</comment>
        <extracomment>Name of Tor network in peer info</extracomment>
        <translation>Oignon</translation>
    
YES  
The French word for the "Onion" network (Tor) is typically left as "Onion" because it is a proper noun referring to the Tor network's special addressing system. Translating it as "Oignon" (the vegetable) is misleading and incorrect in this technical context.

Correct translation:  
Onion
```

```
        <source>%1 m</source>
        <translation>%1 min</translation>
    
YES  
The source "%1 m" most likely represents "%1 meters" or "%1 minutes", but the original abbreviation "m" is preserved. In French, "min" explicitly means "minute" whereas "m" can mean "mètre". Replacing "m" with "min" therefore changes the unit and could be misleading if the original text meant meters. The translation should preserve the abbreviation "m" as is.

Correct translation:  
%1 m
```

```
        <source>%1 B</source>
        <translation>%1 o</translation>
    
YES  
The translation is incorrect. The source "%1 B" refers to a size in bytes, where "B" stands for "bytes." The French translation should also use the abbreviation "B" for bytes, not "o." The letter "o" might be a confusion with "octets," but the correct abbreviation for bytes in French is still "B."

Correct translation:  
%1 B
```

```
        <source>Cannot create new wallet, the software was compiled without sqlite support (required for descriptor wallets)</source>
        <translation>Impossible de créer un nouveau portemonnaies. Le logiciel a été compilé sans prise en charge de sqlite (nécessaire pour les portemonnaies de descripteurs) </translation>
    
YES
The French translation contains a plural form "portemonnaies" instead of the singular "portefeuille" or "portefeuille" for "wallet," and there is an unnecessary space before the closing parenthesis. Additionally, "portemonnaies" should be singular as in the original ("wallet" singular). Also, "portefeuille" is a more standard term for wallet in French Bitcoin context. The sentence is split into two parts with a period, while the original is a single sentence. The sentence should be continuous.

Correct translation:
Impossible de créer un nouveau portefeuille, le logiciel a été compilé sans prise en charge de sqlite (nécessaire pour les portefeuilles descripteurs)
```

```
        <source>Type: %1
</source>
        <translation>Type  : %1
</translation>
    
YES
There is an extra space before and after the colon in the French translation, which is unnecessary and inconsistent with the source formatting. The source simply ends with a colon immediately after "Type". The correct translation should not have spaces around the colon to mirror the source string.

Correct translation:
Type: %1
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>Quand vous cliquerez sur Valider, %1 commencera à télécharger et à traiter l’intégralité de la chaîne de blocs %4 (%2 Go) en débutant avec les transactions les plus anciennes de %3, lors du lancement de %4 a été lancé initialement.</translation>
    
YES  
The translation is mostly accurate but has redundancy and awkward phrasing in the last part: "lors du lancement de %4 a été lancé initialement." This literally says "when the launch of %4 was launched initially," which is repetitive and ungrammatical.

A better phrasing would be:  
"Quand vous cliquerez sur Valider, %1 commencera à télécharger et à traiter l’intégralité de la chaîne de blocs %4 (%2 Go) en débutant par les transactions les plus anciennes de %3, au moment du lancement initial de %4."

Note also that the narrow no-break space before "Go" is correct in French typographic rules, so that spacing can remain. The format specifiers (%1, %2, %3, %4) are correctly preserved.
```

```
        <source>If you disable the spending of unconfirmed change, the change from a transaction cannot be used until that transaction has at least one confirmation. This also affects how your balance is computed.</source>
        <translation>Si vous désactivé la dépense de la monnaie non confirmée, la monnaie d’une transaction ne peut pas être utilisée tant que cette transaction n’a pas reçu au moins une confirmation. Celai affecte aussi le calcul de votre solde.</translation>
    
YES
The translation contains grammatical errors and a typo:
- "désactivé" should be "désactivez" to match the imperative/conditional form.
- "monnaie" is not appropriate in this Bitcoin context; "change" should be translated as "la monnaie" only if meant literally, but here "change" (the leftover amount) is better left as "la monnaie restante" or "la monnaie non confirmée" is not usual in Bitcoin context. The source says "unconfirmed change," which is usually translated as "la monnaie non confirmée" or simply "la monnaie de retour non confirmée". Better to use "la monnaie" for generic but "le rendu" or "la monnaie de retour" or just "le change" can be used in Bitcoin context. Since "change" is standard in Bitcoin, "le change non confirmé" is acceptable.
- "Celai" is a typo, should be "Cela".
- Sentence flow can be improved.

Corrected translation:
Si vous désactivez la dépense du change non confirmé, le change d’une transaction ne peut pas être utilisé tant que cette transaction n’a pas reçu au moins une confirmation. Cela affecte aussi le calcul de votre solde.
```

```
        <source>Enable PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Activer les contrôles TBPS</translation>
    
YES  
The acronym "PSBT" (Partially Signed Bitcoin Transaction) should be kept as "PSBT" in French, not reversed to "TBPS". The correct translation is:  
Activer les contrôles PSBT
```

```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Affichez ou non les contrôles TBPS.</translation>
    
YES  
The translation changes the tone and meaning slightly. The source is phrased as a neutral description ("Whether to show PSBT controls.") and should reflect that ambiguity, whereas the translation is an imperative ("Affichez ou non...") which commands the user rather than stating the option. Also, "PSBT" is mistranslated as "TBPS" which is incorrect and may confuse users. The abbreviation should remain "PSBT" as it is a technical term.

Correct translation:  
Afficher ou non les contrôles PSBT.
```

```
        <source>Third-party transaction URLs</source>
        <translation>URL de transaction de $tiers</translation>
    
YES  
The translation incorrectly uses "$tiers" which is not appropriate here. The correct word is "tiers" without the dollar sign. Also, "URL" should be pluralized to "URLs" to match the source.

Correct translation:  
URL de transaction tierces
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>Votre balance actuelle en adresses juste-regarder</translation>
    
YES  
The phrase "juste-regarder" is not the correct translation for "watch-only" in this Bitcoin context. The term commonly used in French Bitcoin terminology is "adresses en lecture seule" or "adresses watch-only" (sometimes left in English). Also, "balance" is better translated as "solde" for monetary balance.

Correct translation:  
Votre solde actuel dans les adresses en lecture seule
```

```
        <source>Unconfirmed transactions to watch-only addresses</source>
        <translation>Transactions non confirmées vers des adresses juste-regarder</translation>
    
YES  
The phrase "juste-regarder" is not a correct or natural way to say "watch-only" in French. The correct term commonly used in the Bitcoin context for "watch-only addresses" is "adresses à surveillance seule" or simply "adresses en mode 'watch-only'".  

Correct translation:  
Transactions non confirmées vers des adresses en mode watch-only
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>Le solde miné dans des adresses juste-regarder, qui n’est pas encore mûr</translation>
    
YES  
The phrase "juste-regarder" is an incorrect and unnatural translation for "watch-only" in the Bitcoin context. The standard French terminology for "watch-only addresses" is "adresses en consultation seule" or "adresses en lecture seule". Additionally, "mûr" (meaning ripe) is not the best choice here; "mature" or "échue" is more appropriate in financial or Bitcoin context. The sentence also needs to correctly reflect plural for "mature".

Correct translation:  
Le solde miné dans des adresses en consultation seule qui n’est pas encore mature
```

```
        <source>Current total balance in watch-only addresses</source>
        <translation>Solde total actuel dans des adresses juste-regarder</translation>
    
YES  
The phrase "juste-regarder" is a literal and incorrect translation for "watch-only." The correct term in French for "watch-only addresses" (in the Bitcoin context) is "adresses en lecture seule" or "adresses en surveillance."  
Correct translation:  
Solde total actuel dans des adresses en lecture seule
```

```
        <source>PSBT Operations</source>
        <translation>Opération TBSP</translation>
    
YES  
The abbreviation PSBT (Partially Signed Bitcoin Transaction) should be kept as is or translated properly. The reversed abbreviation "TBSP" is incorrect and not used in French. Also, "Opération" should be plural as in the source ("Operations").  

Correct translation:  
Opérations PSBT
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Impossible de démarrer le gestionnaire de cliquer-pour-payer bitcoin:</translation>
    
YES  
The French translation is inaccurate and awkward. The English phrase "Cannot start bitcoin: click-to-pay handler" indicates that the click-to-pay handler for bitcoin cannot be started. The French translation "Impossible de démarrer le gestionnaire de cliquer-pour-payer bitcoin:" is incorrect because "cliquer-pour-payer" is not an established French phrase, and the colon at the end is unnecessary and does not match the source.

A better translation would be:  
"Impossible de démarrer le gestionnaire bitcoin de clic-pour-payer"  
or  
"Impossible de démarrer le gestionnaire clic-pour-payer bitcoin"  

However, "clic-pour-payer" is the more common French equivalent of "click-to-pay" than "cliquer-pour-payer."

Correct translation:  
Impossible de démarrer le gestionnaire bitcoin clic-pour-payer
```

```
        <source>Whether we relay addresses to this peer.</source>
        <extracomment>Tooltip text for the Address Relay field in the peer details area, which displays whether we relay addresses to this peer (Yes/No).</extracomment>
        <translation>Reliez ou non des adresses à ce pair.</translation>
    
YES  
The translation "Reliez ou non des adresses à ce pair." is not accurate and sounds imperative ("Relay or not addresses to this peer.") rather than describing whether we relay addresses or not. A correct translation should convey the idea of whether the system relays addresses to this peer (affirmative or negative), consistent with the tooltip context.

Correct translation:  
« Si nous relayons des adresses à ce pair. »
```

```
        <source>the peer selected us for high bandwidth relay</source>
        <translation>le pair nous avons sélectionné comme relais à large bande passante</translation>
    
YES  
The French translation is incorrect and ungrammatical. The intended meaning is "the peer selected us for high bandwidth relay," where "the peer" is the subject, and "selected us" is the verb phrase.

Correct translation:  
"le pair nous a sélectionnés comme relais à haute bande passante"
```

```
        <source>Request payment to …</source>
        <translation>Demander de paiement à…</translation>
    
YES  
The translation "Demander de paiement à…" is not idiomatic French. The correct phrase should use "un paiement" (a payment) with the preposition "à". Also, spacing before the ellipsis in French typography is typically a narrow non-breaking space. However, since the English uses three dots without space, we can keep the ellipsis tight.

Correct translation:  
Demander un paiement à…
```

```
        <source>Specify a custom fee per kB (1,000 bytes) of the transaction's virtual size.

Note:  Since the fee is calculated on a per-byte basis, a fee rate of "100 satoshis per kvB" for a transaction size of 500 virtual bytes (half of 1 kvB) would ultimately yield a fee of only 50 satoshis.</source>
        <translation>Indiquer des frais personnalisés par Ko (1 000 octets) de la taille virtuelle de la transaction.

Note : Les frais étant calculés par octet, un taux de frais de « 100 satoshis par Kov » pour une transaction d’une taille de 500 octets (la moitié de 1 Kov) donneront des frais de seulement 50 satoshis.</translation>
    
YES
The abbreviation "Ko" and "Kov" used in the French translation is inconsistent and non-standard for "kB" (kilobytes). The standard abbreviation in French is "kB" (kilooctet) or simply "Ko" (with a lowercase k and uppercase O), but the abbreviation "Kov" is incorrect and not used.

Also, there is inconsistent use of narrow no-break spaces: the source uses normal spaces, but the translation uses non-breaking spaces and some incorrect spacing near punctuation like the colon and quotes.

Correct translation:
Indiquer des frais personnalisés par kB (1 000 octets) de la taille virtuelle de la transaction.

Note : comme les frais sont calculés à l'octet, un taux de 100 satoshis par kB pour une transaction de taille virtuelle de 500 octets (la moitié d’un kB) correspondra finalement à des frais de seulement 50 satoshis.
```

```
        <source>Watch-only balance:</source>
        <translation>Solde juste-regarder :</translation>
    
YES  
The translation "Solde juste-regarder :" is incorrect and unnatural in French. The term "watch-only" in the Bitcoin context is typically translated as "lecture seule". The correct translation should be:  
Solde en lecture seule :
```

```
        <source>Private key for the entered address is not available.</source>
        <translation>La clé privée pour l’adresse saisie n’est pas proposée.</translation>
    
YES  
The word "proposée" (offered) is not appropriate in this context. The proper way to say "not available" in French here is "n’est pas disponible".  

Correct translation:  
La clé privée pour l’adresse saisie n’est pas disponible.
```

```
        <source>watch-only</source>
        <translation>juste-regarder</translation>
    
YES  
The French translation "juste-regarder" is incorrect and unnatural. The proper term used in the Bitcoin context for "watch-only" is "lecture seule."

Correct translation:  
<translation>lecture seule</translation>
```

```
        <source>Mined</source>
        <translation>Miné </translation>
    
YES  
The French translation "Miné" is incorrect in this context. The English term "Mined" (past participle of "mine" related to cryptocurrency mining) should be translated as "Miné" without an extra space, but more importantly, in French related to Bitcoin, the past participle "Miné" is correct but the trailing space after "Miné " is incorrect. Also, "Miné" without context might be ambiguous but is the appropriate translation here.  

Correct translation:  
Miné
```

```
        <source>watch-only</source>
        <translation>juste-regarder</translation>
    
YES  
The French translation "juste-regarder" is incorrect and unnatural. The proper term used in the Bitcoin context for "watch-only" is "lecture seule."

Correct translation:  
<translation>lecture seule</translation>
```

```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Une adresse juste-regarder est-elle ou non impliquée dans cette transaction.</translation>
    
YES  
The phrase "juste-regarder" is a literal and incorrect translation for "watch-only." In the context of Bitcoin, "watch-only address" is a specific technical term and should be translated as "adresse watch-only" or "adresse en lecture seule."  

Correct translation:  
Une adresse watch-only est-elle impliquée ou non dans cette transaction ?
```

```
        <source>User-defined intent/purpose of the transaction.</source>
        <translation>Intention, but de la transaction défini par l’utilisateur.</translation>
    
YES  
The translation is incorrect and awkward. The word "but" is English and should be replaced by the French translation "but" (meaning "purpose" or "goal") or "objet" or "finalité". Also, "défini" should agree in gender and number with "intention," which is feminine singular, so it should be "définie". A better translation is:  
Intention ou but de la transaction définie par l’utilisateur.
```

```
        <source>Mined</source>
        <translation>Miné </translation>
    
YES  
The French translation "Miné" is incorrect in this context. The English term "Mined" (past participle of "mine" related to cryptocurrency mining) should be translated as "Miné" without an extra space, but more importantly, in French related to Bitcoin, the past participle "Miné" is correct but the trailing space after "Miné " is incorrect. Also, "Miné" without context might be ambiguous but is the appropriate translation here.  

Correct translation:  
Miné
```

```
        <source>Other</source>
        <translation>Autres </translation>
    
YES  
There is an unnecessary trailing space in the French translation. Also, "Other" in singular form usually translates to "Autre" unless context requires plural. Without further context, the singular form is preferable.

Correct translation:  
Autre
```

```
        <source>Edit address label</source>
        <translation>Modifier l’adresse de l’étiquette</translation>
    
YES  
The translation "Modifier l’adresse de l’étiquette" is incorrect and does not convey the intended meaning. The English phrase "Edit address label" means to edit the label associated with an address, not to edit the "address of the label." In French, this should be translated as "Modifier le libellé de l’adresse" or "Modifier l’étiquette de l’adresse."  

Correct translation:  
Modifier le libellé de l’adresse
```

```
        <source>ID</source>
        <translation>ID </translation>
    
YES
There is an unnecessary trailing space after "ID" in the translation.

Correct translation:
ID
```

```
        <source>to</source>
        <translation>à </translation>
    
YES  
There is an extra trailing space after "à" which should not be there.  
Correct translation:  
<translation>à</translation>
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>Le fichier de la TBSP doit être inférieur à 100 Mio</translation>
    
YES  
The acronym "PSBT" (Partially Signed Bitcoin Transaction) is mistranslated as "TBSP" which is incorrect and confusing. Additionally, "fichier" is masculine, so the adjective should be "inférieur" (which is correct), but the spacing before "Mio" is a non-breaking space, which is appropriate in French typography. However, to be consistent and clearer, it's better to keep the same acronym and add the missing word "taille" or "poids" if needed. Also, "Mio" can be used, but "MiB" is also acceptable as it is a technical unit.

Correct translation:  
Le fichier PSBT doit être inférieur à 100 Mio
```

```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>%s n’a pas réussi à valider l’état de l’instantané -assumeutxo. Cela indique un problème matériel, un bogue logiciel ou une mauvaise modification logicielle qui a permis le chargement d’un instantané invalide. Par conséquent, le nœud s’arrêtera et cessera d’utiliser tout état fondé sur cet instantané, ce qui réinitialisera à le niveau de la chaîne de %d à %d. Lors du prochain démarrage, la synchronisation reprendra de %d, sans utiliser les données d’un instantané. Signalez cet incident à %s en indiquant comment vous avez obtenu l’instantané. L’état de chaîne de l’instantané invalide sera laissé sur le disque au cas afin d’aider éventuellement à diagnostiquer le problème à l’origine de cette erreur.</translation>
    
YES  
There are minor issues in the French translation that affect readability and accuracy:  

1. "ce qui réinitialisera à le niveau de la chaîne de %d à %d."  
This is incorrect French grammar. It should be "ce qui réinitialisera le niveau de la chaîne de %d à %d." (remove "à" before "le niveau").  

2. "au cas afin d’aider éventuellement"  
This phrasing is awkward and redundant. It should be either "au cas où cela pourrait aider" or "au cas où cela serait utile" to sound natural.  

Corrected translation:  
%s n’a pas réussi à valider l’état de l’instantané -assumeutxo. Cela indique un problème matériel, un bogue logiciel ou une mauvaise modification logicielle qui a permis le chargement d’un instantané invalide. Par conséquent, le nœud s’arrêtera et cessera d’utiliser tout état fondé sur cet instantané, ce qui réinitialisera le niveau de la chaîne de %d à %d. Lors du prochain démarrage, la synchronisation reprendra de %d, sans utiliser les données d’un instantané. Signalez cet incident à %s en indiquant comment vous avez obtenu l’instantané. L’état de chaîne de l’instantané invalide sera laissé sur le disque au cas où cela pourrait aider à diagnostiquer le problème à l’origine de cette erreur.
```

```
        <source>Error starting/committing db txn for wallet transactions removal process</source>
        <translation>Erreur de lancement, de validation de la transaction de base de données pour le processus de suppression des transactions du portemonnaie</translation>
    
YES  
The translation is slightly awkward and can be clarified. The original English suggests an error occurred while starting or committing a database transaction related to the wallet transactions removal process. The French translation does not explicitly convey the "starting/committing" aspect clearly and is a bit unnatural in phrasing.

A better translation would be:  
Erreur lors du démarrage ou de la validation de la transaction de la base de données pour le processus de suppression des transactions du porte-monnaie
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>Erreur : L’enregistrement de l’identificateur du fichier de vidage est incorrect. Est « %s », mais « %s » est attendu. </translation>
    
YES  
The French translation is generally correct in meaning but has minor issues with spacing and phrasing that could be improved for clarity and French typographic conventions:

1. The space before the colon (:) in French should be a non-breaking space, but here it is a normal space (acceptable, but typically typographers use non-breaking space).
2. The quotation marks used are French-style (« ») but with inconsistent spacing: there are non-breaking spaces before and after the quoted strings, which is typical. However, the wording "Est « %s », mais « %s » est attendu." is somewhat awkward.

A more natural and clear phrasing is:

"Erreur : l’enregistrement de l’identificateur du fichier de vidage est incorrect. Valeur reçue : « %s », valeur attendue : « %s »."

This is simpler, clearer, and maintains the same meaning.

Correct translation:  
Erreur : l’enregistrement de l’identificateur du fichier de vidage est incorrect. Valeur reçue : « %s », valeur attendue : « %s ».
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Les frais maximaux de transaction que vous payez (en plus des frais habituels) afin de prioriser une dépense non partielle plutôt qu’une sélection normale de pièces.</translation>
    
YES  
The translation is incorrect in the phrase "une dépense non partielle" which contradicts the original meaning "partial spend avoidance." The original English means prioritizing avoiding partial spending, but the French says prioritizing a non-partial spend, which is misleading.

Correct translation:  
Les frais maximaux de transaction que vous payez (en plus des frais habituels) pour prioriser l'évitement des dépenses partielles plutôt que la sélection normale des pièces.
```

```
        <source>Wallet loaded successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future. Legacy wallets can be migrated to a descriptor wallet with migratewallet.</source>
        <translation>Le portemonnaie a été créé. Le type de portemonnaie ancien devient obsolète et la prise en charge de la création et de l’ouverture des portemonnaie anciens sera supprimée à l’avenir. Les anciens portemonnaies peuvent être migrés vers un portemonnaie de descripteurs avec migratewallet.</translation>
    
YES
The translation has some inaccuracies and awkward phrasing:
- "Wallet loaded successfully." is translated as "Le portemonnaie a été créé." which means "The wallet has been created." This is inaccurate; "loaded" and "created" are different actions. A better translation is "Le portefeuille a été chargé avec succès."
- "wallet" is better translated as "portefeuille" instead of "portemonnaie" in the context of Bitcoin.
- "portemonnaie anciens" should be plural and consistent: "portefeuilles anciens" or better "portefeuilles hérités" or "portefeuilles legacy" (the English term "legacy" is often kept).
- "portemonnaie de descripteurs" should be "portefeuille descripteur" (singular) or "portefeuille basé sur descripteurs".
- "la prise en charge de la création et de l’ouverture des portemonnaie anciens" should have consistent plural "portefeuilles anciens".
- The term "legacy wallet" is common and often kept in English or translated as "portefeuille hérité".

Corrected translation:

Le portefeuille a été chargé avec succès. Le type de portefeuille hérité est déprécié et la prise en charge de la création et de l’ouverture de portefeuilles hérités sera supprimée à l’avenir. Les portefeuilles hérités peuvent être migrés vers un portefeuille descripteur avec migratewallet.
```

```
        <source>%s is set very high!</source>
        <translation>La valeur %s est très élevée</translation>
    
YES  
The translation is missing the exclamation mark at the end, which should be preserved as in the source text.  

Correct translation:  
La valeur %s est très élevée !
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>Les connexions sortantes sont limitées à Tor (-onlynet=onion), mais le mandataire pour accéder au réseau Tor n’est pas indiqué : ni -proxy, ni -onion, ni -onion=0 n’est indiqué</translation>
    
YES  
The source mentions: "none of -proxy, -onion or -listenonion is given".  
The translation incorrectly replaces "-listenonion" by "-onion=0", which changes the meaning and is incorrect.  

Correct translation:  
Les connexions sortantes sont limitées à Tor (-onlynet=onion), mais le mandataire pour accéder au réseau Tor n’est pas indiqué : ni -proxy, ni -onion, ni -listenonion n’est indiqué
```

```
        <source>Unexpected legacy entry in descriptor wallet found. Loading wallet %s

The wallet might have been tampered with or created with malicious intent.
</source>
        <translation>Une entrée héritée inattendue a été trouvée dans le portemonnaie de descripteurs. Chargement du portemonnaie %s

Le portemonnaie a peut-être avoir été altéré ou créé avec des intentions malveillantes.
</translation>
    
YES  
The translation has some awkward phrasing and issues:  
- "portemonnaie" is less commonly used in French for "wallet" in the Bitcoin context; "portefeuille" is more appropriate.  
- "de descripteurs" is grammatically incorrect. It should be "de descripteur" or better "de type descriptor" or "decripteur" depending on the context, but "de descripteurs" is incorrect plural usage here.  
- The phrase "a peut-être avoir été altéré" is ungrammatical. It should be either "a peut-être été altéré" or "a peut-être été modifié".  
- Also, the line break in the source is preserved, but in French we avoid extra spaces before punctuation if present. The space issue is not problematic here, but the phrasing is.  

Correct translation:  
Une entrée héritée inattendue dans un portefeuille de type descripteur a été trouvée. Chargement du portefeuille %s

Le portefeuille a peut-être été altéré ou créé avec des intentions malveillantes.
```

```
        <source>Error initializing wallet database environment %s!</source>
        <translation>Erreur d’initialisation de l’environnement de la base de données du portemonnaie %s </translation>
    
YES  
The translation misses the exclamation mark "!" at the end, which is present in the source. Also, the last character before the closing quote is a thin space (U+2009), which is non-standard spacing after the placeholder and should be removed for consistency and formatting correctness. Furthermore, the word "portemonnaie" is a less common variant; "portefeuille" is more standard in French for "wallet" in this context.

Correct translation:  
Erreur d’initialisation de l’environnement de la base de données du portefeuille %s !
```

```
        <source>Insufficient dbcache for block verification</source>
        <translation>dbcache est insuffisant pour la confirmation des blocs</translation>
    
YES  
The translation is understandable but could be improved for clarity and correctness. The English "Insufficient dbcache for block verification" refers to a shortage of database cache memory for the process of verifying blocks. The word "confirmation" (confirmation) is not the precise equivalent of "verification" (vérification). Also, the original phrase does not start with a noun; it is a statement about the amount of dbcache being insufficient. It's better to keep the same phrasing structure.

Correct translation:  
« Cache db insuffisant pour la vérification des blocs »
```

```
        <source>The transactions removal process can only be executed within a db txn</source>
        <translation>Le processus de suppression des transactions ne peut être exécuté que dans une transaction .de base de données</translation>
    
YES  
The translation contains a spacing error and a mistranslation for "db txn." The phrase ".de base de données" is incorrect and has an unnecessary space before the period. "db txn" should be translated as "transaction de base de données" without splitting or extra punctuation.

Correct translation:  
Le processus de suppression des transactions ne peut être exécuté que dans une transaction de base de données.
```

```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>Il s’agit des frais minimaux que vous payerez si vous envoyez une transaction.</translation>
    
YES  
The translation adds "minimaux" (minimal), which is not present in the source and changes the meaning. The source simply refers to "the transaction fee" without specifying it as minimal. Also, "payerez" should be spelled with two "r" in the future tense ("payerez" is correct, but "payerez" is the proper future form; "payerez" here is correct). The rest is correct. However, the addition of "minimaux" is not warranted.

Correct translation:  
Il s’agit des frais de transaction que vous paierez si vous envoyez une transaction.
```

```
        <source>Transaction change output index out of range</source>
        <translation>L’index des sorties de monnaie des transactions est hors échelle</translation>
    
YES  
The French translation is somewhat awkward and inaccurate. The phrase "Transaction change output index out of range" refers specifically to the index number of the "change output" in a transaction being outside the allowed range. The provided translation "L’index des sorties de monnaie des transactions est hors échelle" translates back roughly as "The index of the transaction money outputs is out of scale," which is not precise and uses "hors échelle" (out of scale) incorrectly in this context.

A better translation would be:  
**"L’index de la sortie de monnaie rendue de la transaction est hors plage"**  
or more succinctly:  
**"L’index de la sortie de monnaie de retour de la transaction est hors plage"**

Alternatively, using "hors plage" ("out of range") is preferable to "hors échelle." Also, "change output" is commonly translated as "sortie de monnaie" or "sortie de la monnaie rendue" in Bitcoin terminology.

Corrected translation:  
**L’index de la sortie de monnaie de la transaction est hors plage**
```

```
        <source>Transaction too large</source>
        <translation>La transaction est trop élevée</translation>
    
YES  
The French translation "La transaction est trop élevée" is incorrect because "élevée" usually refers to height or level, not size or magnitude. The correct translation for "Transaction too large" in the Bitcoin context is:  
"Transaction trop volumineuse" or simply "Transaction trop grande".  

Correct translation:  
Transaction trop volumineuse
```

```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Trop peu de descripteurs de fichiers sont proposés. %d proposés, %d requis</translation>
    
YES  
The translation "Trop peu de descripteurs de fichiers sont proposés." is not appropriate, as "proposés" means "offered" or "suggested", which is incorrect in this technical context. The correct term is "disponibles" (available). Also, there is a minor spacing problem: the French format specifiers should not have non-breaking spaces before them.

Correct translation:  
Trop peu de descripteurs de fichiers disponibles. %d disponibles, %d requis.
```
</details>
