# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>fr</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bfr%5D%20request)


<!-- cache_translation_check_fr_eafadccade984155c3ab3302171f6f699085577057470b60a4c820f1eb60a909 -->
```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Une erreur est survenue lors de l’enregistrement de la liste d’adresses vers %1. Rréessayez plus tard.</translation>
    
ERR
- Typo: "Rréessayez" has an extra "R".
- Meaning change: "Please try again" was translated as "Réessayez plus tard" ("try again later"), which adds "later" not present in the source.
- Preposition: "to %1" when saving to a file is better rendered as "dans %1" in French.

Correct translation:
Une erreur est survenue lors de l’enregistrement de la liste d’adresses dans %1. Veuillez réessayer.
```

<!-- cache_translation_check_fr_7a130a75f3e4be2f61a2cd7886ae03e67b4bd67dda3ca7835106c0fcd54f773d -->
```
        <source>&amp;Verify message…</source>
        <translation>&amp;Confirmer un message…</translation>
    
ERR
"Confirmer un message" is inaccurate; the standard UI term is "Vérifier" (to verify a signed message).
Correct translation:
&Vérifier le message…
```

<!-- cache_translation_check_fr_a22572c3c7e30a1b7b879354466eca4d0c153075568fec37a8c6292e3302c9a1 -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>&amp;Charger la TBSP d’un fichier…</translation>
    
ERR
"PSBT" was incorrectly translated as "TBSP". Also, "d’un fichier" after "Charger" is unnatural; use "à partir d’un fichier" or "depuis un fichier". The ampersand is correctly present once.

Correct translation:
&Charger une PSBT à partir d’un fichier…
```

<!-- cache_translation_check_fr_56175f0101887bffe86dd68244d7cf599ce137d7f3339da93f7598b25f8ae40c -->
```
        <source>Open &amp;URI…</source>
        <translation>Ouvrir une &amp;URI…</translation>
    
ERR
The gender is incorrect. In French, "URI" corresponds to "identifiant" (masculine), so it should be "un URI", not "une URI". The shortcut ampersand and ellipsis are fine.

Correct translation:
Ouvrir un &URI…
```

<!-- cache_translation_check_fr_e6a32246e840ddbf9b8228c4366cbea4426666ac78030215335849f18a1882a6 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>Charger la TBSP du &amp;presse-papiers…</translation>
    
ERR
"PSBT" was incorrectly rendered as "TBSP". It should remain "PSBT" in French. Also, "depuis le presse-papiers" is more idiomatic than "du presse-papiers."

Correct translation:
Charger une PSBT depuis le &presse-papiers…
```

<!-- cache_translation_check_fr_229b9f3152a201b44944a7f36e15b1af786b6f3b03532fd0915180583b023036 -->
```
        <source>Type: %1
</source>
        <translation>Type  : %1
</translation>
    
ERR
There is an extra space before the colon. In French, there should be a single (ideally non-breaking) space before “:”.

Correct translation:
Type : %1
```

<!-- cache_translation_check_fr_eb5f959ff0fc7a73580bf0e2aa4da545a5d7ce21b70ebc9621b73ba3a2c95e46 -->
```
        <source>(un)select all</source>
        <translation>Tout (ne rien) choisir</translation>
    
ERR
The French is unidiomatic and uses "choisir" instead of the standard "sélectionner". It should convey toggling select/unselect all.

Correct translation:
(Dé)sélectionner tout
```

<!-- cache_translation_check_fr_1f81dd3c16a4ce300e80cab13848b074411cf26efea2cdfe3b8e6a5dc9eb06c6 -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>Copier l’ID de la transaction et l’index des sorties</translation>
    
ERR
The ampersand indicating a shortcut key is missing, and "output index" should be singular.
Correct translation:
Copier l’&ID de la transaction et l’index de sortie
```

<!-- cache_translation_check_fr_641ab2e8ebfa61fbc7a5ec3af00fa518127015a19de1ecacfdae3210a65c5879 -->
```
        <source>L&amp;ock unspent</source>
        <translation>&amp;Verrouillé ce qui n’est pas dépensé</translation>
    
ERR
The translation uses the past participle "Verrouillé" instead of the imperative/infinitive required for a command and is awkward ("ce qui n’est pas dépensé"). It should be an action label like "Verrouiller les sorties non dépensées". Keep a single ampersand for the shortcut.

Correct translation:
&Verrouiller les sorties non dépensées
```

<!-- cache_translation_check_fr_3fe5ef77cb009362912b8af0289d6708366bcbe3e2d250dfcf1346daf5aba60c -->
```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>Quand vous cliquerez sur Valider, %1 commencera à télécharger et à traiter l’intégralité de la chaîne de blocs %4 (%2 Go) en débutant avec les transactions les plus anciennes de %3, lors du lancement de %4 a été lancé initialement.</translation>
    
ERR
- "Valider" should match "OK".
- The clause "lors du lancement de %4 a été lancé initialement" is ungrammatical and redundant.
- More natural to use "de %4" after "chaîne de blocs".

Correct translation:
Lorsque vous cliquez sur OK, %1 commencera à télécharger et à traiter l’intégralité de la chaîne de blocs de %4 (%2 Go), en commençant par les transactions les plus anciennes de %3, lorsque %4 a été lancé pour la première fois.
```

<!-- cache_translation_check_fr_f1783f4b9489d015dedc0a733d000149ecf63c28fdaae0db4c68395e4e795364 -->
```
        <source>&amp;Main</source>
        <translation>&amp;Principales</translation>
    
ERR
"Principales" is incorrect (plural feminine) for the menu/tab label "Main". It should be singular masculine in this context.

Correct translation:
&Principal
```

<!-- cache_translation_check_fr_ccdae3ff5c2404764a36cc86c5a9fc76670ed6e580639f0c17021e9c4f585694 -->
```
        <source>If you disable the spending of unconfirmed change, the change from a transaction cannot be used until that transaction has at least one confirmation. This also affects how your balance is computed.</source>
        <translation>Si vous désactivé la dépense de la monnaie non confirmée, la monnaie d’une transaction ne peut pas être utilisée tant que cette transaction n’a pas reçu au moins une confirmation. Celai affecte aussi le calcul de votre solde.</translation>
    
ERR
Grammar and typos: "désactivé" should be "désactivez"; "Celai" should be "Cela". Improved fluency.

Correct translation:
Si vous désactivez la dépense de la monnaie non confirmée, la monnaie d’une transaction ne peut pas être utilisée tant que cette transaction n’a pas reçu au moins une confirmation. Cela affecte aussi le calcul de votre solde.
```

<!-- cache_translation_check_fr_20efe36b43b7beb78a9a2203de1168fdd15eaaf315a307703773a5e5f3b041b3 -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Activer les contrôles &amp;TBPS</translation>
    
ERR
The acronym "PSBT" was incorrectly altered to "TBPS". It should remain "PSBT". The single ampersand for the shortcut is fine.
Correct translation:
Activer les contrôles &PSBT
```

<!-- cache_translation_check_fr_ffa3bcece099002a4168e4848493d2dd510d9a10a2ae4323871921a5ae55ac97 -->
```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Affichez ou non les contrôles TBPS.</translation>
    
ERR
The acronym PSBT was incorrectly translated as "TBPS". Also, a more natural phrasing for a setting description is preferable.

Correct translation:
Indique s'il faut afficher les contrôles PSBT.
```

<!-- cache_translation_check_fr_830da6a0c5ce7c7e1f71ff14df1cba9ada0e9aec1dbe98013508690df8a5df81 -->
```
        <source>&amp;Third-party transaction URLs</source>
        <translation>URL de transaction de $tiers</translation>
    
ERR
The translation contains an incorrect placeholder "$tiers" and is missing the required single '&' for the shortcut. It also mismatches plurality ("URLs" vs "URL"). 

Correct translation:
&URL de transactions de tiers
```

<!-- cache_translation_check_fr_e6c68a40f89e9df803f1a9fb999b49275697be9c7775ec7ea92c813e9e6d39e9 -->
```
        <source>PSBT Operations</source>
        <translation>Opération TBSP</translation>
    
ERR
The acronym is incorrect (PSBT was changed to TBSP) and the number is wrong (singular instead of plural).

Correct translation:
Opérations PSBT
```

<!-- cache_translation_check_fr_1010231c057ee49af96234a0ef5f309d3aec35a7543c3416259831e47ff11cb2 -->
```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Impossible de démarrer le gestionnaire de cliquer-pour-payer bitcoin:</translation>
    
ERR
The French phrasing is unnatural, the colon is misplaced (should follow "Bitcoin" as in the source), there's an unnecessary trailing colon, and "Bitcoin" should be capitalized.

Correct translation:
Impossible de démarrer Bitcoin : gestionnaire de paiement par clic
```

<!-- cache_translation_check_fr_f47a9ab2871af05f079adb64673019ee4f0b6227b394a4423d5125aba2bc1269 -->
```
        <source>Whether we relay addresses to this peer.</source>
        <extracomment>Tooltip text for the Address Relay field in the peer details area, which displays whether we relay addresses to this peer (Yes/No).</extracomment>
        <translation>Reliez ou non des adresses à ce pair.</translation>
    
ERR
The French uses the imperative ("Reliez") and is ungrammatical for a descriptive tooltip. It should be an indicative description.

Correct translation:
Indique si nous relayons des adresses à ce pair.
```

<!-- cache_translation_check_fr_723e64bc31e6dcf1952218ebdb9cd15ad9b974de4aadbaa0dc6873136bc10edc -->
```
        <source>&amp;Copy IP/Netmask</source>
        <extracomment>Context menu action to copy the IP/Netmask of a banned peer. IP/Netmask is the combination of a peer's IP address and its Netmask. For IP address, see: https://en.wikipedia.org/wiki/IP_address.</extracomment>
        <translation>&amp;Copier l’IP, le masque réseau</translation>
    
ERR
The translation uses a comma instead of a slash, which changes the meaning. It should mirror the "IP/Netmask" format, and "masque de réseau" is the standard term.

Correct translation:
&Copier l’adresse IP/masque de réseau
```

<!-- cache_translation_check_fr_f9e1bc7069dcb1f533402edc761d68efc05968cfd30b63e029c67b5f1bfade82 -->
```
        <source>Request payment to …</source>
        <translation>Demander de paiement à…</translation>
    
ERR
Grammatical error: should be "Demander un paiement", not "Demander de paiement". Also, the space before the ellipsis should be preserved as in the source.

Correct translation:
Demander un paiement à …
```

<!-- cache_translation_check_fr_c0908ef476add7350e93fd43e1582adb7becd6874d8e79def11fe5eed9755f1e -->
```
        <source>&amp;Verify</source>
        <translation>&amp;Confirmer</translation>
    
ERR
"Verify" should be translated as "Vérifier" in French, not "Confirmer". The shortcut ampersand is correctly present once.

Correct translation:
&Vérifier
```

<!-- cache_translation_check_fr_63d1680c07ae452d4ecb587d5b40550c42640204e551180c8a428c98740c7a2c -->
```
        <source>Specify a custom fee per kB (1,000 bytes) of the transaction's virtual size.

Note:  Since the fee is calculated on a per-byte basis, a fee rate of "100 satoshis per kvB" for a transaction size of 500 virtual bytes (half of 1 kvB) would ultimately yield a fee of only 50 satoshis.</source>
        <translation>Indiquer des frais personnalisés par Ko (1 000 octets) de la taille virtuelle de la transaction.

Note : Les frais étant calculés par octet, un taux de frais de « 100 satoshis par Kov » pour une transaction d’une taille de 500 octets (la moitié de 1 Kov) donneront des frais de seulement 50 satoshis.</translation>
    
ERR
- Incorrect unit: "Kov" is not standard; should match source "kvB". Also mixed "Ko" with "kvB" is inconsistent; better to keep "kB"/"kvB" as in source.
- Missing "virtuels" when referring to "500 virtual bytes".
- Grammar agreement: subject "un taux" is singular; use "donnerait" not "donneront".

Correct translation:
Indiquer des frais personnalisés par kB (1 000 octets) de la taille virtuelle de la transaction.

Note : Les frais étant calculés par octet, un taux de « 100 satoshis par kvB » pour une transaction d’une taille de 500 octets virtuels (la moitié de 1 kvB) donnerait des frais de seulement 50 satoshis.
```

<!-- cache_translation_check_fr_6bc0dc2393d24268ae7135c9dac7057993287bf5aa2ab9368e534dcf6f36a92c -->
```
        <source>The address you selected for change is not part of this wallet. Any or all funds in your wallet may be sent to this address. Are you sure?</source>
        <translation>L’adresse que vous avez choisie pour la monnaie ne fait pas partie de ce portemonnaie. Les fonds de ce portemonnaie peuvent en partie ou en totalité être envoyés vers cette adresse. Confirmez-vous ?</translation>
    
ERR
Terminology and style are non-idiomatic for Bitcoin context: "portefeuille" is preferred over "portemonnaie", "adresse de monnaie" (or "adresse de rendu") is clearer than "pour la monnaie", and "Êtes-vous sûr ?" is more natural than "Confirmez-vous ?".

Correct translation:
L’adresse de monnaie que vous avez sélectionnée ne fait pas partie de ce portefeuille. Tout ou partie des fonds de votre portefeuille pourraient être envoyés à cette adresse. Êtes-vous sûr ?
```

<!-- cache_translation_check_fr_ccb3b3748a300c6f636d21c8ec95104a61b095d79bf768099dc028312bfa3bf9 -->
```
        <source>&amp;Verify Message</source>
        <translation>&amp;Confirmer un message</translation>
    
ERR
"Confirmer un message" means "Confirm a message" and does not match "Verify Message" in this Bitcoin UI context.

Correct translation:
&Vérifier un message
```

<!-- cache_translation_check_fr_8d4f7d37269dd625d52d79258b88865ceb7d36ad0f93fa08780928937a9616c8 -->
```
        <source>Verify &amp;Message</source>
        <translation>Confirmer le &amp;message</translation>
    
ERR
"Confirmer" is inaccurate here; the action is to verify a signed message. Use "Vérifier".
Correct translation:
Vérifier le &message
```

<!-- cache_translation_check_fr_da5a9fe127fe54e3e66387d88a6e57fba63f3672367a95fd1977d4b96d6b5c8f -->
```
        <source>Private key for the entered address is not available.</source>
        <translation>La clé privée pour l’adresse saisie n’est pas proposée.</translation>
    
ERR
The phrase "n’est pas proposée" is unnatural here; "not available" should be "n’est pas disponible". Also "de l’adresse" is more idiomatic than "pour l’adresse" in this context.

Correct translation:
La clé privée de l’adresse saisie n’est pas disponible.
```

<!-- cache_translation_check_fr_2581a314ac205fbe57138292d7e7f4f213d0e54a7e001041a52513032338ca44 -->
```
        <source>Mined</source>
        <translation>Miné </translation>
    
ERR
Trailing whitespace in the translation.

Correct translation:
Miné
```

<!-- cache_translation_check_fr_a0658ac333d432138e177a7716cbc5b8ae5e2c4c9af31ec657d473a0b116c826 -->
```
        <source>User-defined intent/purpose of the transaction.</source>
        <translation>Intention, but de la transaction défini par l’utilisateur.</translation>
    
ERR
Accord incorrect et formulation maladroite (“Intention, but … défini”).

Correct translation:
Finalité de la transaction définie par l’utilisateur.
```

<!-- cache_translation_check_fr_2581a314ac205fbe57138292d7e7f4f213d0e54a7e001041a52513032338ca44 -->
```
        <source>Mined</source>
        <translation>Miné </translation>
    
ERR
Trailing whitespace in the translation.

Correct translation:
Miné
```

<!-- cache_translation_check_fr_d712e4d82cdf8ed43937bf22c0ac338b1f2574483e98fba5e7f119d1c4d70f1c -->
```
        <source>Other</source>
        <translation>Autres </translation>
    
ERR
Trailing whitespace in the translation. Also, "Other" is typically singular in UI contexts; "Autre" is more appropriate.

Correct translation:
Autre
```

<!-- cache_translation_check_fr_0a01ad0157ad9eb078be0d8e53af44d1d5c4cb64908b3b436abe161a674dd557 -->
```
        <source>&amp;Edit address label</source>
        <translation>&amp;Modifier l’adresse de l’étiquette</translation>
    
ERR
The French reverses the relationship, implying "modify the address of the label" instead of "modify the label of the address."

Correct translation:
&Modifier le libellé de l’adresse
```

<!-- cache_translation_check_fr_1ed765406ea228864967795799abdc3fc65c0421b9bea326ae648a4df13d6d7d -->
```
        <source>ID</source>
        <translation>ID </translation>
    
ERR
Trailing whitespace in the translation.

Correct translation:
ID
```

<!-- cache_translation_check_fr_e20adac52b7c6602797cc3528d5d7bb55c3825e6536689ba171722c2ca40d279 -->
```
        <source>to</source>
        <translation>à </translation>
    
ERR
Trailing whitespace in the translation.

Correct translation:
à
```

<!-- cache_translation_check_fr_4a652c0bb148d008c3711cb54b2e6bbe1a9a1da2d965753556c94c1a989ade73 -->
```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>Le fichier de la TBSP doit être inférieur à 100 Mio</translation>
    
ERR
The acronym PSBT was incorrectly rendered as "TBSP", and "Le fichier de la TBSP" is unnatural. It should remain "PSBT". The rest is fine.

Correct translation:
Le fichier PSBT doit être inférieur à 100 Mio
```

<!-- cache_translation_check_fr_59c3aa842804c19c4e3cec14a72f83cd2e1ef868c94ab20e4bc17097c7765799 -->
```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>%s n’a pas réussi à valider l’état de l’instantané -assumeutxo. Cela indique un problème matériel, un bogue logiciel ou une mauvaise modification logicielle qui a permis le chargement d’un instantané invalide. Par conséquent, le nœud s’arrêtera et cessera d’utiliser tout état fondé sur cet instantané, ce qui réinitialisera à le niveau de la chaîne de %d à %d. Lors du prochain démarrage, la synchronisation reprendra de %d, sans utiliser les données d’un instantané. Signalez cet incident à %s en indiquant comment vous avez obtenu l’instantané. L’état de chaîne de l’instantané invalide sera laissé sur le disque au cas afin d’aider éventuellement à diagnostiquer le problème à l’origine de cette erreur.</translation>
    
ERR
The French contains grammatical errors (“réinitialisera à le niveau”), awkward phrasing (“au cas afin”), and slightly unclear rendering of “chain height” and “any snapshot data”.

Correct translation:
%s n’a pas réussi à valider l’état de l’instantané -assumeutxo. Cela indique un problème matériel, un bogue dans le logiciel, ou une mauvaise modification logicielle qui a permis le chargement d’un instantané invalide. Par conséquent, le nœud va s’arrêter et cesser d’utiliser tout état construit à partir de cet instantané, ce qui réinitialisera la hauteur de la chaîne de %d à %d. Au prochain redémarrage, le nœud reprendra la synchronisation à partir de %d sans utiliser aucune donnée d’instantané. Veuillez signaler cet incident à %s, en précisant comment vous avez obtenu l’instantané. L’état de chaîne de l’instantané invalide sera laissé sur le disque, au cas où cela aiderait à diagnostiquer le problème à l’origine de cette erreur.
```

<!-- cache_translation_check_fr_cadde5690aab51bd291e9d66396fd174c801d0a9aa570d206c61d4385ee4a1aa -->
```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Les frais maximaux de transaction que vous payez (en plus des frais habituels) afin de prioriser une dépense non partielle plutôt qu’un choix normale de pièces.</translation>
    
ERR
Issues:
- "dépense non partielle" misrenders "partial spend avoidance"; should express avoiding partial spends.
- Agreement error: "choix normale" should be "choix normal".
- More natural phrasing for "prioritize ... over ..." and "transaction fee".

Correct translation:
Il s’agit des frais de transaction maximum que vous payez (en plus des frais habituels) pour donner la priorité à l’évitement des dépenses partielles par rapport à la sélection de pièces habituelle.
```

<!-- cache_translation_check_fr_d44e291b11ea967678b1275762edb7a80cee0b30f07771e1b68bc50841e8e727 -->
```
        <source>%s is set very high!</source>
        <translation>La valeur %s est très élevée</translation>
    
ERR
The exclamation mark is missing, altering the tone. A more accurate rendering of “is set very high” is also preferable.

Correct translation:
%s est défini à une valeur très élevée !
```

<!-- cache_translation_check_fr_a0ca98fb52f070fbec40df67d497b91429857c43ee345b6ad4343b87216c3426 -->
```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>Les connexions sortantes sont limitées à Tor (-onlynet=onion), mais le mandataire pour accéder au réseau Tor n’est pas indiqué : ni -proxy, ni -onion, ni -onion=0 n’est indiqué</translation>
    
ERR
The option names are incorrect: the source mentions -listenonion, but the translation uses -onion=0. Also improve agreement and clarity.

Correct translation:
Les connexions sortantes sont limitées à Tor (-onlynet=onion), mais le proxy pour accéder au réseau Tor n’est pas fourni : aucune des options -proxy, -onion ou -listenonion n’est fournie.
```

<!-- cache_translation_check_fr_4c3da931e827bebf817c1820800e8217601e7f03e00249193c6f97e594a62a13 -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>Élagage : la dernière synchronisation de portemonnaie va par-delà les données élaguées. Vous devez « -reindex » (réindexer, retélécharger toute la chaîne de blocs au cas ou un nœud a été élagué)</translation>
    
ERR
Minor issues: "au cas ou" should be "au cas où"; tense/wording for "in case of a pruned node" is off; "portemonnaie" is nonstandard for Bitcoin, "portefeuille" is preferred.

Correct translation:
Élagage : la dernière synchronisation du portefeuille dépasse les données élaguées. Vous devez utiliser -reindex (retélécharger toute la chaîne de blocs dans le cas d’un nœud élagué)
```

<!-- cache_translation_check_fr_93d193774ed96a8b6f1ee31334b7fe8cd7fb35b42822b46d812c8e811e377e42 -->
```
        <source>Unexpected legacy entry in descriptor wallet found. Loading wallet %s

The wallet might have been tampered with or created with malicious intent.
</source>
        <translation>Une entrée héritée inattendue a été trouvée dans le portemonnaie à descripteurs. Chargement du portemonnaie %s

Le portemonnaie a peut-être avoir été altéré ou créé avec des intentions malveillantes.
</translation>
    
ERR
Grammatical error: "a peut-être avoir été" should be "a peut-être été".

Correct translation:
Une entrée héritée inattendue a été trouvée dans le portemonnaie à descripteurs. Chargement du portemonnaie %s

Le portemonnaie a peut-être été altéré ou créé avec des intentions malveillantes.
```

<!-- cache_translation_check_fr_97e25bee54e6f50c059698a0f081ec41224628cf1c8b369e44ea2b217c65e46c -->
```
        <source>Can't spend unconfirmed version %d pre-selected input with a version 3 tx</source>
        <translation>Impossible de dépenser une entrée présélectionnée de version %d avec une transaction de version 3</translation>
    
ERR
The translation omits "unconfirmed" (non confirmée).

Correct translation:
Impossible de dépenser une entrée présélectionnée non confirmée de version %d avec une transaction de version 3
```

<!-- cache_translation_check_fr_13e25be797d9de8195f0d0202e237fa71d182af44745954f47f08e742864ef80 -->
```
        <source>Can't spend unconfirmed version 3 pre-selected input with a version %d tx</source>
        <translation>Impossible de dépenser une entrée présélectionnée de version  avec une transaction de version %d</translation>
    
ERR
Missing the version number "3" and the notion "unconfirmed"; also results in awkward spacing. The %d specifier is correctly preserved.

Correct translation:
Impossible de dépenser une entrée présélectionnée non confirmée de version 3 avec une transaction de version %d
```

<!-- cache_translation_check_fr_b8f6da732ad8c514c9bc738a2020f34d2dcd6fb935c25a0cf37dee25e36ee17a -->
```
        <source>Could not generate scriptPubKeys (cache is empty)</source>
        <translation>Impossible de générer scriptPubKeys (le cache est vide)</translation>
    
ERR
Missing article in French; should be "des scriptPubKeys" to be grammatical.

Correct translation:
Impossible de générer des scriptPubKeys (le cache est vide)
```

<!-- cache_translation_check_fr_307f3781cbdf6c749bce87720a0a49dcb79b3e092dbe3f3895d7749e40ab3a7e -->
```
        <source>Failed to acquire rescan reserver during wallet initialization</source>
        <translation>Échec de réservation de l’accès à l’opération de réanalyse lors de l’initialisation du porte-monnaie</translation>
    
ERR
The French phrasing is awkward and missing an article; "porte-monnaie" is nonstandard in this context (use "portefeuille"). "de l’accès" is unnecessary.

Correct translation:
Échec de l’obtention de la réservation de réanalyse lors de l’initialisation du portefeuille
```

<!-- cache_translation_check_fr_945ff4a892dc14d2858e97104272d71af38dfe06ba63c7b7769e3a532c6b4043 -->
```
        <source>Failed to close block undo file.</source>
        <translation>Échec de fermeture du fichier d’annulation des blocs.</translation>
    
ERR
The French is slightly unidiomatic and changes number: "des blocs" implies plural, while the source is singular ("block undo file"). It should also include the article "la" after "Échec".

Correct translation:
Échec de la fermeture du fichier d’annulation de bloc.
```

<!-- cache_translation_check_fr_102eb036f54106531a9693fbfc2907d16729878b99ce51b16ff988aa60e30629 -->
```
        <source>Insufficient dbcache for block verification</source>
        <translation>dbcache est insuffisant pour la confirmation des blocs</translation>
    
ERR
"confirmation des blocs" is inaccurate; it should be "vérification des blocs". Also the phrasing can be improved.

Correct translation:
dbcache insuffisant pour la vérification des blocs
```

<!-- cache_translation_check_fr_fa73ce7097d954feee47af2eabfa7c8030caa62ec683032228fa8cf5d89121af -->
```
        <source>The transactions removal process can only be executed within a db txn</source>
        <translation>Le processus de suppression des transactions ne peut être exécuté que dans une transaction .de base de données</translation>
    
ERR
Typo and incorrect spacing: ".de" should be "de" without the dot.

Correct translation:
Le processus de suppression des transactions ne peut être exécuté que dans une transaction de base de données
```

<!-- cache_translation_check_fr_32e7d269919fb348b05a663bd4464284a058db2af26b6102b65e0f062ebd32e3 -->
```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>Il s’agit des frais minimaux que vous payerez si vous envoyez une transaction.</translation>
    
ERR
The translation adds "minimaux" (minimum), which is not present in the source, and it omits "de transaction" after "frais".

Correct translation:
Il s’agit des frais de transaction que vous paierez si vous envoyez une transaction.
```

<!-- cache_translation_check_fr_19042570ce817d0b4d909509aa4212b48a976077169fddbe0397e7c1257d861c -->
```
        <source>Transaction change output index out of range</source>
        <translation>L’index des sorties de monnaie des transactions est hors échelle</translation>
    
ERR
"Hors échelle" is incorrect in this context, and the number should be singular to match "output index" and "transaction". Use "hors limites" and singular forms.

Correct translation:
L’indice de la sortie de monnaie de la transaction est hors limites
```

<!-- cache_translation_check_fr_0f723cf19e976900dcbb581afc5b09c4736b086c81c05e1c86862a819cc4779c -->
```
        <source>Transaction too large</source>
        <translation>La transaction est trop élevée</translation>
    
ERR
"trop élevée" suggests the amount is too high, not the size. In this context, it should refer to the transaction's size (in bytes).

Correct translation:
La transaction est trop volumineuse
```

<!-- cache_translation_check_fr_b86606f1c0ec752c2d5238f10228f480208826c686cdae0d6df1b7b02248f4d9 -->
```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on an enormous cluster of unconfirmed transactions.</source>
        <translation>Échec de calcul de la majoration des frais, car les UTXO non confirmés dépendent d’un groupe énorme de transactions non confirmées.</translation>
    
ERR
Grammatical issue: “Échec de calcul” is incorrect; it should be “Échec du calcul”. “Cluster” is better rendered as “amas” in this context.

Correct translation:
Échec du calcul de la majoration des frais, car les UTXO non confirmés dépendent d’un énorme amas de transactions non confirmées.
```

<!-- cache_translation_check_fr_3d32697841c2d9582cec1745f56e69c25b995d812661f1273664545e6aaacfb6 -->
```
        <source>Transaction requires one destination of non-zero value, a non-zero feerate, or a pre-selected input</source>
        <translation>Une destination d’une valeur non nulle, des taux de frais non nuls, ou une entrée présélectionnée sont nécessaires pour cette transaction</translation>
    
ERR
The French translation uses the plural for "taux de frais" and implies multiple items are necessary, whereas the source requires only one of the listed singular options. It should keep singular forms and mirror the "requires ... or ..." structure.

Correct translation:
Cette transaction requiert une destination d’une valeur non nulle, un taux de frais non nul ou une entrée présélectionnée.
```

<!-- cache_translation_check_fr_bb87f4828ea32beae319360b10e5810f5caeac72b90e68d03a93ed1f02d0684d -->
```
        <source>Unrecognized descriptor found. Loading wallet %s

The wallet might have been created on a newer version.
Please try running the latest software version.
</source>
        <translation>Un descripteur non reconnu a été trouvé. Chargement du portemonnaie %s

Le portemonnaie a peut-être été créé avec une version plus récente.
Essayez d’utiliser la version la plus récente du logiciel.
</translation>
    
ERR
The term "portemonnaie" is nonstandard in the Bitcoin context; "portefeuille" is the commonly used term in French for "wallet". The rest, including the %s placeholder and spacing, is correct.

Correct translation:
Un descripteur non reconnu a été trouvé. Chargement du portefeuille %s

Le portefeuille a peut-être été créé avec une version plus récente.
Essayez d’utiliser la version la plus récente du logiciel.
```

<!-- cache_translation_check_fr_3f1f3033120113d3aa6008488edb7b6cd63b7e460b7e1b33b5a0b786dbbc6e31 -->
```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Trop peu de descripteurs de fichiers sont proposés. %d proposés, %d requis</translation>
    
ERR
“proposés” is incorrect here; it should be “disponibles” for “available”. There is also a missing period at the end of the second sentence.

Correct translation:
Pas assez de descripteurs de fichiers disponibles. %d disponibles, %d requis.
```
</details>

Number of issues: 54.
