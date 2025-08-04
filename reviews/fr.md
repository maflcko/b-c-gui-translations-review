# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>fr</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bfr%5D%20low%20quality)


```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Une erreur est survenue lors de l’enregistrement de la liste d’adresses vers %1. Rréessayez plus tard.</translation>
    
YES: The translation contains a typo in the word "Rréessayez" (should be "Réessayez") and "plus tard" (later) is not present in the original English text.
Une erreur est survenue lors de l’enregistrement de la liste d’adresses vers %1. Réessayez.
```

```
        <source>Onion</source>
        <comment>network name</comment>
        <extracomment>Name of Tor network in peer info</extracomment>
        <translation>Oignon</translation>
    
YES
The translation of "Onion" to "Oignon" is too literal and doesn't convey the correct meaning in the context of Bitcoin and the Tor network. "Onion" in this context refers to the ".onion" domain used for Tor hidden services.

The correct translation should reflect the technical term used in French for Tor hidden services.

Correct translation: Services Onion
```

```
        <source>%1 m</source>
        <translation>%1 min</translation>
    
YES: The translation is incorrect. The source text "%1 m" likely represents "%1 minutes" or "%1 meters" in a Bitcoin context. The translation "%1 min" is a valid abbreviation for "minute" in French. However, without further context, it is impossible to definitively say whether "m" in the source refers to minutes or meters. Assuming "m" refers to "minutes," the translation is acceptable. If "m" refers to "meters," the translation is incorrect.

Correct translation depends on the intended meaning of "m" in the source text.

If "%1 m" means "%1 minutes":
<translation>%1 min</translation>

If "%1 m" means "%1 meters":
<translation>%1 m</translation>
```

```
        <source>%1 B</source>
        <translation>%1 o</translation>
    
YES - The translation changes the unit "B" (likely referring to Bytes) to "o" (likely referring to octets). In the context of Bitcoin, "B" typically represents Bitcoin or BTC, not Bytes. The correct translation should preserve the unit if it's a currency.

%1 B
```

```
        <source>Load PSBT from file…</source>
        <translation>Charger la TBSP d’un fichier…</translation>
    
YES, The translation is problematic because "PSBT" is an acronym and should be translated as is, not as "TBSP". The correct translation is "Charger le PSBT d’un fichier…".
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>Charger la TBSP du presse-papiers…</translation>
    
YES, The abbreviation PSBT is not translated into French. The correct translation is: Charger le PSBT du presse-papiers…
```

```
        <source>Cannot create new wallet, the software was compiled without sqlite support (required for descriptor wallets)</source>
        <translation>Impossible de créer un nouveau portemonnaies. Le logiciel a été compilé sans prise en charge de sqlite (nécessaire pour les portemonnaies de descripteurs) </translation>
    
YES - The translation contains a double space between "portemonnaies" and "Le".
Correct translation: Impossible de créer un nouveau portemonnaie. Le logiciel a été compilé sans prise en charge de sqlite (nécessaire pour les portemonnaies de descripteurs).
```

```
        <source>Type: %1
</source>
        <translation>Type  : %1
</translation>
    
YES. The translation introduces an extra space before the colon, which is not present in the source text.
Type : %1
```

```
        <source>change from %1 (%2)</source>
        <translation>monnaie de %1 (%2)</translation>
    
YES, The word "monnaie" translates to "money" or "currency" and not "change" in the context of Bitcoin. In Bitcoin, "change" refers to the unspent amount returned to the sender after a transaction. The correct French term for this is "rendu" or "restant".

NO
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>Quand vous cliquerez sur Valider, %1 commencera à télécharger et à traiter l’intégralité de la chaîne de blocs %4 (%2 Go) en débutant avec les transactions les plus anciennes de %3, lors du lancement de %4 a été lancé initialement.</translation>
    
YES, The translation is problematic. The phrase "lors du lancement de %4 a été lancé initialement" is redundant and grammatically incorrect. It translates to "at the launch of %4 was launched initially".

NO
```

```
        <source>If you disable the spending of unconfirmed change, the change from a transaction cannot be used until that transaction has at least one confirmation. This also affects how your balance is computed.</source>
        <translation>Si vous désactivé la dépense de la monnaie non confirmée, la monnaie d’une transaction ne peut pas être utilisée tant que cette transaction n’a pas reçu au moins une confirmation. Celai affecte aussi le calcul de votre solde.</translation>
    
YES - The translation contains a grammatical error ("désactivé" should be "désactivez") and a spelling error ("Celai" should be "Cela").
Si vous désactivez la dépense de la monnaie non confirmée, la monnaie d’une transaction ne peut pas être utilisée tant que cette transaction n’a pas reçu au moins une confirmation. Cela affecte aussi le calcul de votre solde.
```

```
        <source>Enable PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Activer les contrôles TBPS</translation>
    
YES: The translation contains an abbreviation that is not a direct translation of the source. TBPS is not a known abbreviation for PSBT.
Correct translation: Activer les contrôles PSBT
```

```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Affichez ou non les contrôles TBPS.</translation>
    
YES: The translation "TBPS" is incorrect. The correct abbreviation for Partially Signed Bitcoin Transaction in French is PSBT.
Affichez ou non les contrôles PSBT.
```

```
        <source>Third-party transaction URLs</source>
        <translation>URL de transaction de $tiers</translation>
    
YES, The translation uses a placeholder "$tiers" that is not present in the source text. The source text "Third-party transaction URLs" refers to URLs of transactions made by third parties, not a variable. The correct translation should be "URL de transaction de tiers".

URL de transaction de tiers
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>Votre balance actuelle en adresses juste-regarder</translation>
    
YES - The translation is inaccurate. "juste-regarder" is not a recognized term in the context of Bitcoin or in French. The correct term for "watch-only" in this context would be "lecture seule" or "en lecture seule".
Votre balance actuelle en adresses en lecture seule
```

```
        <source>Unconfirmed transactions to watch-only addresses</source>
        <translation>Transactions non confirmées vers des adresses juste-regarder</translation>
    
YES, the translation of "watch-only addresses" is not accurate. In the context of Bitcoin, "watch-only" refers to addresses that can be monitored for incoming transactions but cannot be used to send funds. A more appropriate translation would be "adresses de surveillance" or "adresses en lecture seule".

NO, Transactions non confirmées vers des adresses de surveillance
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>Le solde miné dans des adresses juste-regarder, qui n’est pas encore mûr</translation>
    
YES, The translation uses a literal translation of "watch-only" which is not idiomatic in French. The correct term for "watch-only" in this context is "adresses de visualisation seule" or "adresses uniquement en lecture".

Mined balance in watch-only addresses that has not yet matured -> Le solde miné dans des adresses de visualisation seule qui n’est pas encore mûr
```

```
        <source>Current total balance in watch-only addresses</source>
        <translation>Solde total actuel dans des adresses juste-regarder</translation>
    
YES: The translation "juste-regarder" for "watch-only" is awkward and unnatural in French. A more idiomatic and accurate translation would be "en lecture seule" or "de consultation uniquement".
Current total balance in watch-only addresses -> Solde total actuel dans les adresses en lecture seule
```

```
        <source>PSBT Operations</source>
        <translation>Opération TBSP</translation>
    
YES: The translation of "PSBT Operations" to "Opération TBSP" is incorrect. "PSBT" is an acronym that should not be translated as "TBSP".
Opérations PSBT
```

```
        <source>PSBT saved to disk.</source>
        <translation>La TBSP a été enregistrée sur le disque.</translation>
    
YES - The acronym "PSBT" should not be translated in this context. The translation should be "PSBT enregistré sur le disque."
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Impossible de démarrer le gestionnaire de cliquer-pour-payer bitcoin:</translation>
    
YES - The colon at the end of the translation is misplaced. It should be after "bitcoin" not at the end of the sentence.
Impossible de démarrer le gestionnaire de cliquer-pour-payer bitcoin :
```

```
        <source>Whether we relay addresses to this peer.</source>
        <extracomment>Tooltip text for the Address Relay field in the peer details area, which displays whether we relay addresses to this peer (Yes/No).</extracomment>
        <translation>Reliez ou non des adresses à ce pair.</translation>
    
YES: The French translation is not accurate and uses the wrong verb. "Reliez" means "connect" or "link" and does not convey the meaning of "relay" in this context. The correct verb should be "relayer".
NO
```

```
        <source>Addresses Rate-Limited</source>
        <extracomment>Text title for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>Adresses ciblées par la limite de débit</translation>
    
YES - The translation is grammatically incorrect and does not accurately convey the meaning of the source text. The phrase "ciblées par la limite de débit" suggests that the addresses are the targets of rate limiting, when in fact they are the ones being limited. A more accurate translation would be "Adresses limitées par débit".
Adresses limitées par débit
```

```
        <source>the peer selected us for high bandwidth relay</source>
        <translation>le pair nous avons sélectionné comme relais à large bande passante</translation>
    
YES: The verb "avons sélectionné" is conjugated incorrectly. It should be "a sélectionné" to agree with "le pair" (singular).
le pair nous a sélectionné comme relais à large bande passante
```

```
        <source>Ban for</source>
        <translation>Bannir pendant</translation>
    
YES: The translation is inaccurate and doesn't convey the intended meaning in the context of Bitcoin. "Ban for" likely refers to a prohibition or restriction related to something. "Bannir pendant" means "to ban during" or "to ban for a period of time," which is a different meaning.

Correct translation: Bannir pour
```

```
        <source>Request payment to …</source>
        <translation>Demander de paiement à…</translation>
    
YES - The translation should be "Demander un paiement à…" or "Faire une demande de paiement à…". The current translation is missing the article "un".
Demander un paiement à…
```

```
        <source>Specify a custom fee per kB (1,000 bytes) of the transaction's virtual size.

Note:  Since the fee is calculated on a per-byte basis, a fee rate of "100 satoshis per kvB" for a transaction size of 500 virtual bytes (half of 1 kvB) would ultimately yield a fee of only 50 satoshis.</source>
        <translation>Indiquer des frais personnalisés par Ko (1 000 octets) de la taille virtuelle de la transaction.

Note : Les frais étant calculés par octet, un taux de frais de « 100 satoshis par Kov » pour une transaction d’une taille de 500 octets (la moitié de 1 Kov) donneront des frais de seulement 50 satoshis.</translation>
    
YES. The translation has an error in the abbreviation "kvB" which is not translated correctly to "Kov". The correct translation should be "ko".

Indiquer des frais personnalisés par Ko (1 000 octets) de la taille virtuelle de la transaction.

Note : Les frais étant calculés par octet, un taux de frais de « 100 satoshis par ko » pour une transaction d’une taille de 500 octets (la moitié de 1 ko) donneront des frais de seulement 50 satoshis.
```

```
        <source>Watch-only balance:</source>
        <translation>Solde juste-regarder :</translation>
    
YES - The translation uses an incorrect term for "watch-only" in French. The correct translation is "lecture seule" or "seulement consultation".
Solde en lecture seule :
```

```
        <source>Private key for the entered address is not available.</source>
        <translation>La clé privée pour l’adresse saisie n’est pas proposée.</translation>
    
YES. The translation uses "proposée" which means "offered" or "proposed". In this context, "available" should be translated to "disponible" to accurately convey that the private key cannot be found or accessed.

La clé privée pour l’adresse saisie n’est pas disponible.
```

```
        <source>watch-only</source>
        <translation>juste-regarder</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning of "watch-only" in the context of Bitcoin. "Juste-regarder" directly translates to "just look" or "only look," which is not the correct term for a watch-only wallet.

The correct translation should be "lecture seule" or "sans signature".

Here's the corrected translation:
<translation>lecture seule</translation>
```

```
        <source>Mined</source>
        <translation>Miné </translation>
    
YES
The translation contains a trailing space.
Miné
```

```
        <source>watch-only</source>
        <translation>juste-regarder</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning of "watch-only" in the context of Bitcoin. "Juste-regarder" directly translates to "just look" or "only look," which is not the correct term for a watch-only wallet.

The correct translation should be "lecture seule" or "sans signature".

Here's the corrected translation:
<translation>lecture seule</translation>
```

```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Une adresse juste-regarder est-elle ou non impliquée dans cette transaction.</translation>
    
YES: The translation uses "juste-regarder" which is a literal translation of "watch-only" but it's not a commonly used term in French for Bitcoin. A more idiomatic translation would be "adresses en lecture seule" or "adresses surveillées".
Une adresse en lecture seule est-elle ou non impliquée dans cette transaction.
```

```
        <source>User-defined intent/purpose of the transaction.</source>
        <translation>Intention, but de la transaction défini par l’utilisateur.</translation>
    
YES, The translation contains erroneous content. The word "but" is not a valid French word in this context, and the sentence structure is awkward.

Intention, but de la transaction défini par l’utilisateur.
Intention/but de la transaction défini par l'utilisateur.
```

```
        <source>Mined</source>
        <translation>Miné </translation>
    
YES
The translation contains a trailing space.
Miné
```

```
        <source>Other</source>
        <translation>Autres </translation>
    
YES - The translation has an extra space at the end. The correct translation is "Autres".
```

```
        <source>Edit address label</source>
        <translation>Modifier l’adresse de l’étiquette</translation>
    
YES, The translation is problematic. The original English text "Edit address label" implies editing the label associated with a specific address. The French translation "Modifier l’adresse de l’étiquette" translates to "Modify the label of the address," which reverses the intended meaning.

Correct translation: Modifier l'étiquette de l'adresse
```

```
        <source>ID</source>
        <translation>ID </translation>
    
YES. The translation has an unwanted trailing space.
ID
```

```
        <source>to</source>
        <translation>à </translation>
    
YES
The translation has an extra space at the end.
Correct translation: à
```

```
        <source>Unable to decode PSBT from clipboard (invalid base64)</source>
        <translation>Impossible de décoder la TBSP du presse-papiers (le Base64 est invalide)</translation>
    
YES: The translation incorrectly translates "PSBT" to "TBSP". "PSBT" is an acronym commonly used in the Bitcoin community and should ideally be kept as is or explained.
Correct translation: Impossible de décoder la PSBT du presse-papiers (le Base64 est invalide)
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>Le fichier de la TBSP doit être inférieur à 100 Mio</translation>
    
YES: The translation incorrectly translates "PSBT" to "TBSP". The correct translation for PSBT is "PSBT".
Le fichier PSBT doit être inférieur à 100 Mio
```

```
        <source>Unable to decode PSBT</source>
        <translation>Impossible de décoder la TBSP</translation>
    
YES: The abbreviation "PSBT" should be translated to "BSVT" in French.
Impossible de décoder la BSVT
```

```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>%s n’a pas réussi à valider l’état de l’instantané -assumeutxo. Cela indique un problème matériel, un bogue logiciel ou une mauvaise modification logicielle qui a permis le chargement d’un instantané invalide. Par conséquent, le nœud s’arrêtera et cessera d’utiliser tout état fondé sur cet instantané, ce qui réinitialisera à le niveau de la chaîne de %d à %d. Lors du prochain démarrage, la synchronisation reprendra de %d, sans utiliser les données d’un instantané. Signalez cet incident à %s en indiquant comment vous avez obtenu l’instantané. L’état de chaîne de l’instantané invalide sera laissé sur le disque au cas afin d’aider éventuellement à diagnostiquer le problème à l’origine de cette erreur.</translation>
    
YES: The phrase "réinitialisera à le niveau de la chaîne de %d à %d" is grammatically incorrect. It should be "réinitialisera le niveau de la chaîne de %d à %d".
%s n’a pas réussi à valider l’état de l’instantané -assumeutxo. Cela indique un problème matériel, un bogue logiciel ou une mauvaise modification logicielle qui a permis le chargement d’un instantané invalide. Par conséquent, le nœud s’arrêtera et cessera d’utiliser tout état fondé sur cet instantané, ce qui réinitialisera le niveau de la chaîne de %d à %d. Lors du prochain démarrage, la synchronisation reprendra de %d, sans utiliser les données d’un instantané. Signalez cet incident à %s en indiquant comment vous avez obtenu l’instantané. L’état de chaîne de l’instantané invalide sera laissé sur le disque au cas afin d’aider éventuellement à diagnostiquer le problème à l’origine de cette erreur.
```

```
        <source>Error starting/committing db txn for wallet transactions removal process</source>
        <translation>Erreur de lancement, de validation de la transaction de base de données pour le processus de suppression des transactions du portemonnaie</translation>
    
YES: The French translation is grammatically incorrect and awkward. The phrase "lancement, de validation" is not idiomatic. A more natural phrasing would be "démarrage et validation".

NO
```

```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Erreur : L’enregistrement du format du fichier de vidage est incorrect. Est « %s », mais « format » est attendu. </translation>
    
YES - The translation of "Got \"%s\", expected \"format\"." is slightly awkward and could be more natural. The use of "Est" is not ideal here.

Correct translation: Erreur : L’enregistrement du format du fichier de vidage est incorrect. Reçu "%s", attendu "format".
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>Erreur : L’enregistrement de l’identificateur du fichier de vidage est incorrect. Est « %s », mais « %s » est attendu. </translation>
    
YES: The word order in the translation is unnatural. The placement of "mais" is also incorrect.
Erreur : L'enregistrement de l'identificateur du fichier de vidage est incorrect. Reçu "%s", attendu "%s".
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Les frais maximaux de transaction que vous payez (en plus des frais habituels) afin de prioriser une dépense non partielle plutôt qu’une sélection normale de pièces.</translation>
    
YES: The translation is problematic as it mistranslates "partial spend avoidance" as "dépense non partielle". It should be "évitement des dépenses partielles".

NO
```

```
        <source>Wallet loaded successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future. Legacy wallets can be migrated to a descriptor wallet with migratewallet.</source>
        <translation>Le portemonnaie a été créé. Le type de portemonnaie ancien devient obsolète et la prise en charge de la création et de l’ouverture des portemonnaie anciens sera supprimée à l’avenir. Les anciens portemonnaies peuvent être migrés vers un portemonnaie de descripteurs avec migratewallet.</translation>
    
YES: The French translation uses "créé" which translates to "created". The English source text states "Wallet loaded successfully", not "Wallet created successfully". The correct translation should reflect that the wallet was loaded.

NO: Le portemonnaie a été chargé avec succès. Le type de portemonnaie ancien devient obsolète et la prise en charge de la création et de l’ouverture des portemonnaie anciens sera supprimée à l’avenir. Les anciens portemonnaies peuvent être migrés vers un portemonnaie de descripteurs avec migratewallet.
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>Les connexions sortantes sont limitées à Tor (-onlynet=onion), mais le mandataire pour accéder au réseau Tor n’est pas indiqué : ni -proxy, ni -onion, ni -onion=0 n’est indiqué</translation>
    
YES, the translation is problematic because it incorrectly translates "-onion or -listenonion" as "-onion ou -onion=0". The correct translation for "-listenonion" should be "-listenonion".

NO
```

```
        <source>Unexpected legacy entry in descriptor wallet found. Loading wallet %s

The wallet might have been tampered with or created with malicious intent.
</source>
        <translation>Une entrée héritée inattendue a été trouvée dans le portemonnaie de descripteurs. Chargement du portemonnaie %s

Le portemonnaie a peut-être avoir été altéré ou créé avec des intentions malveillantes.
</translation>
    
YES: The French translation contains a grammatical error ("a peut-être avoir été" should be "a peut-être été").
Correct translation: Une entrée héritée inattendue a été trouvée dans le portemonnaie de descripteurs. Chargement du portemonnaie %s

Le portemonnaie a peut-être été altéré ou créé avec des intentions malveillantes.
```

```
        <source>Error initializing wallet database environment %s!</source>
        <translation>Erreur d’initialisation de l’environnement de la base de données du portemonnaie %s </translation>
    
YES - The translation contains an incorrect character for the percentage symbol. The correct translation should use the standard "%s" format specifier.
Erreur d’initialisation de l’environnement de la base de données du portemonnaie %s !
```

```
        <source>Insufficient dbcache for block verification</source>
        <translation>dbcache est insuffisant pour la confirmation des blocs</translation>
    
YES - The translation incorrectly uses "confirmation" instead of "verification". While related, "verification" is the more accurate term in this context.
dbcache est insuffisant pour la vérification des blocs
```

```
        <source>The transactions removal process can only be executed within a db txn</source>
        <translation>Le processus de suppression des transactions ne peut être exécuté que dans une transaction .de base de données</translation>
    
YES: The translation has a misplaced period and an unnecessary space before the period. The period should be after "transaction" and there should be no space before it.
Le processus de suppression des transactions ne peut être exécuté que dans une transaction de base de données.
```

```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>Il s’agit des frais minimaux que vous payerez si vous envoyez une transaction.</translation>
    
YES - The translation is inaccurate. It states "minimum fees" instead of "transaction fee". The source does not mention "minimum fees".

Il s'agit des frais de transaction que vous paierez si vous envoyez une transaction.
```

```
        <source>Transaction change output index out of range</source>
        <translation>L’index des sorties de monnaie des transactions est hors échelle</translation>
    
YES - The translation is grammatically incorrect and unnatural in French. The phrase "hors échelle" is not appropriate in this context and the phrasing of "L’index des sorties de monnaie des transactions" is awkward. A more accurate and natural translation would be: "L'index de sortie de la monnaie de la transaction est hors limites."
```

```
        <source>Transaction too large</source>
        <translation>La transaction est trop élevée</translation>
    
YES - The translation of "too large" as "trop élevée" which means "too high" or "too expensive" is not the most accurate for "too large" in the context of a transaction size. The correct translation should reflect the size or volume.
La transaction est trop volumineuse
```

```
        <source>Unsupported logging category %s=%s.</source>
        <translation>La catégorie de journalisation %s=%s n’est pas prise en charge</translation>
    
YES - The translation is missing the period at the end.
Unsupported logging category %s=%s.
```

```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Trop peu de descripteurs de fichiers sont proposés. %d proposés, %d requis</translation>
    
YES: The French translation uses "proposés" (offered) instead of "disponibles" (available). This is a minor accuracy issue. Additionally, there is an unnecessary non-breaking space before the required number, which should be removed.

Correct translation: Trop peu de descripteurs de fichiers sont disponibles. %d disponibles, %d requis.
```
</details>
