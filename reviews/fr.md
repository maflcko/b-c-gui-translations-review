# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>fr</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bfr%5D%20request)


<!-- cache_translation_check_fr_7e4d3d9c523db168eb02fb280122b89d1970121deafc9d553b05aa336de0dbdc -->
```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Une erreur est survenue lors de l’enregistrement de la liste d’adresses dans %1. Réessayez plus tard.</translation>
    
ERR
"Please try again." was translated as "Réessayez plus tard," which adds "later" not present in the source. Also, since %1 is a file name, specifying "fichier" improves clarity.

Correct translation:
Une erreur est survenue lors de l’enregistrement de la liste d’adresses dans le fichier %1. Veuillez réessayer.
```

<!-- cache_translation_check_fr_4ae860fd8690731996e303d0fe5f102118e46d525c86cc6c755cd91d7b6eaa64 -->
```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>Voulez-vous chiffrer votre portefeuille ?</translation>
    
ERR
The translation omits the "Are you sure" nuance. It should reflect confirmation.

Correct translation:
Êtes-vous sûr de vouloir chiffrer votre portefeuille ?
```

<!-- cache_translation_check_fr_34c6a78f0980b0dd32612a5f074b6ec2c9c57dcd0758afefb9dab2ec37a74af2 -->
```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>N’oubliez pas que le chiffrement de votre portefeuille ne peut pas protéger entièrement vos bitcoins contre le vol par des programmes malveillants qui infecteraient votre ordinateur.</translation>
    
ERR
The phrase "qui infecteraient votre ordinateur" uses the conditional and is awkward here. "Malware" is better rendered as "logiciels malveillants". Use present participle or present indicative.

Correct translation:
N’oubliez pas que le chiffrement de votre portefeuille ne peut pas protéger entièrement vos bitcoins contre le vol par des logiciels malveillants infectant votre ordinateur.
```

<!-- cache_translation_check_fr_3ea62a36871025dea229b214e55806d34d2e50db4edaefc506a3778f91394c07 -->
```
        <source>Wallet encryption failed</source>
        <translation>Échec de chiffrement du portefeuille</translation>
    
ERR
Missing article "du" makes the French phrasing ungrammatical.

Correct translation:
Échec du chiffrement du portefeuille
```

<!-- cache_translation_check_fr_32fc74a8996cbb7144dea07c1213fa9a0d32d78ee098a64836c69a9b26e508ea -->
```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>L’ancienne phrase de passe saisie pour le déchiffrement du portefeuille est erronée. Elle comporte un caractère nul (c.-à.-d. un octet de zéro). Si la phrase de passe a été définie avec une version de ce logiciel antérieure à 25.0, réessayez en ne saisissant que les caractères jusqu’au premier caractère nul, sans saisir ce dernier..</translation>
    
ERR
Minor punctuation and typographic issues:
- Double period at the end ("dernier..").
- The abbreviation for "c.-à-d." is malformed as "c.-à.-d.".
- "un octet de zéro" is awkward; "un octet de valeur zéro" is clearer.

Correct translation:
L’ancienne phrase de passe saisie pour le déchiffrement du portefeuille est erronée. Elle contient un caractère nul (c.-à-d. un octet de valeur zéro). Si la phrase de passe a été définie avec une version de ce logiciel antérieure à 25.0, réessayez en ne saisissant que les caractères jusqu’au premier caractère nul, sans saisir ce dernier.
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

<!-- cache_translation_check_fr_1727bed6888d4b034c115c92e6233d4e6ae8f9272e8eaad4a0ac23dd7f1f2391 -->
```
        <source>Restore a wallet from a backup file</source>
        <extracomment>Status tip for Restore Wallet menu item</extracomment>
        <translation>Restaurer le portefeuille d’un fichier de sauvegarde</translation>
    
ERR
The article and preposition are incorrect. It should be "un portefeuille" (not "le portefeuille") and include "à partir de" or "depuis" to render "from".

Correct translation:
Restaurer un portefeuille à partir d’un fichier de sauvegarde
```

<!-- cache_translation_check_fr_8082b51415358ef7a066ed57321ead4811ed4e7f57777444b9cedb313c1bce7d -->
```
        <source>No wallets available</source>
        <translation>Aucun portefeuille n’est proposé</translation>
    
ERR
The translation is understandable but not idiomatic; "n’est proposé" means "is offered," which differs from the standard UI phrasing for availability.

Correct translation:
Aucun portefeuille disponible
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

<!-- cache_translation_check_fr_6ef757c8c36f88223cb38f48db8849fd3569ab27b5537da54ae80daaa29575dd -->
```
        <source>Create wallet failed</source>
        <translation>Échec de création du portefeuille</translation>
    
ERR
Minor grammatical issue: missing article. More natural French is "Échec de la création du portefeuille".

Correct translation:
Échec de la création du portefeuille
```

<!-- cache_translation_check_fr_6a11480c2f34058efe1705e02760039b9fab776e8217cd04f0106703654f431e -->
```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>Voulez-vous migrer le portefeuille &lt;i&gt;%1&lt;/i&gt; ?</translation>
    
ERR
The translation weakens the meaning by omitting “Are you sure,” rendering it as a simple confirmation rather than a certainty check.

Correct translation:
Êtes-vous sûr de vouloir migrer le portefeuille &lt;i&gt;%1&lt;/i&gt; ?
```

<!-- cache_translation_check_fr_6339f3ee24d311a209a53a05017cbfb2b6809d5947c546c948b26de1cab911ff -->
```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>La migration du portefeuille le convertira en un ou plusieurs portefeuilles de descripteurs. Une nouvelle sauvegarde du portefeuille devra être effectuée.
Si ce portefeuille contient des scripts juste-regarder, un nouveau portefeuille sera créé qui comprendra ces scripts juste-regarder. 
Si ce portefeuille comprend des scripts solubles, mais non surveillés, un nouveau portefeuille différent sera créé comportant ces scripts.

Le processus de migration créera une sauvegarde du portefeuille avant migration. Ce fichier de sauvegarde sera nommé &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak et se trouvera dans le dossier de ce portefeuille. En cas de migration erronée, la sauvegarde peut être restaurée avec la fonction « Restaurer le portefeuille ».</translation>
    
ERR
- "watchonly" incorrectly translated as "juste-regarder"; use "en surveillance uniquement" or keep "(watch-only)" for clarity.
- "solvable" mistranslated as "solubles" (dissolvable); should be "résolubles".
- Minor stylistic/consistency fixes.

Correct translation:
La migration du portefeuille convertira celui-ci en un ou plusieurs portefeuilles à descripteurs. Une nouvelle sauvegarde du portefeuille devra être effectuée.
Si ce portefeuille contient des scripts en surveillance uniquement (watch-only), un nouveau portefeuille sera créé contenant ces scripts.
Si ce portefeuille contient des scripts résolubles mais non surveillés, un autre nouveau portefeuille sera créé contenant ces scripts.

Le processus de migration créera une sauvegarde du portefeuille avant la migration. Ce fichier de sauvegarde sera nommé &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak et se trouvera dans le dossier de ce portefeuille. En cas de migration incorrecte, la sauvegarde peut être restaurée avec la fonction « Restaurer le portefeuille ».
```

<!-- cache_translation_check_fr_8027dfa3203703a8df20847c8161ebdbb0b260827b239933ce6dc1c48e908bc7 -->
```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>Migration du portefeuille&lt;b&gt;%1&lt;/b&gt;…</translation>
    
ERR
Missing space before the bolded placeholder, causing "portefeuille" and the variable to run together.

Correct translation:
Migration du portefeuille <b>%1</b>…
```

<!-- cache_translation_check_fr_3b80bb3df799f17e7253442434de9408719caaed1cc16530c98cf6e05cd57b6f -->
```
        <source>The wallet '%1' was migrated successfully.</source>
        <translation>Le portefeuille « %1 » a été migré.</translation>
    
ERR
The translation omits "successfully," changing the meaning.

Correct translation:
Le portefeuille « %1 » a été migré avec succès.
```

<!-- cache_translation_check_fr_abdd970155c496b16c9408900adc4624a10881b295b0ff8a971aabfdc5dad14f -->
```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Les scripts juste-regarder ont été migrés vers un nouveau portefeuille nommé « %1 ».</translation>
    
ERR
"juste-regarder" is an incorrect calque of "watchonly" and not idiomatic in French Bitcoin terminology.

Correct translation:
Les scripts en lecture seule ont été migrés vers un nouveau portefeuille nommé « %1 ».
```

<!-- cache_translation_check_fr_7fa3632a3f85040bdf5a20c764503efd3c2a4bb91bc82feb8b3961d5b06292fa -->
```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Les scripts solubles, mais non surveillés ont été migrés vers un nouveau portefeuille nommé « %1 ».</translation>
    
ERR
"Solubles" is incorrect in French (means "dissolvable"). The correct term for "solvable" here is "résolubles". Also, the comma after "solubles" is unnecessary.

Correct translation:
Les scripts résolubles mais non surveillés ont été migrés vers un nouveau portefeuille nommé « %1 ».
```

<!-- cache_translation_check_fr_278cf2a015a4ae4e0c77f6a7573d4e87464ed9333f36496b12b78fd4a8864b2b -->
```
        <source>Open Wallet</source>
        <extracomment>Title of window indicating the progress of opening of a wallet.</extracomment>
        <translation>Ouvrir un portefeuille</translation>
    
ERR
As a window title indicating progress, a noun phrase is more natural in French. "Ouvrir un portefeuille" sounds like an action/menu command rather than a progress title.

Correct translation:
Ouverture du portefeuille
```

<!-- cache_translation_check_fr_9e0b6fa184c34d25b0a8dfe44c1dec1be60736b0dbdca010910ccfc8445a7f02 -->
```
        <source>Restore wallet failed</source>
        <extracomment>Title of message box which is displayed when the wallet could not be restored.</extracomment>
        <translation>Échec de restauration du portefeuille</translation>
    
ERR
The French phrasing is slightly unnatural without the article. A more idiomatic title is:
Échec de la restauration du portefeuille
```

<!-- cache_translation_check_fr_00afdbef8e0f6b063375137fe1be8b96d9f698d56c9d7148ef9daf7d7beae7d6 -->
```
        <source>Are you sure you wish to close the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>Voulez-vous fermer le portefeuille &lt;i&gt;%1&lt;/i&gt; ?</translation>
    
ERR
The translation loses the nuance of "Are you sure" and only asks "Do you want". It should reflect confirmation.

Correct translation:
Êtes-vous sûr de vouloir fermer le portefeuille <i>%1</i> ?
```

<!-- cache_translation_check_fr_1f67d1085af289381cbd3e231064fbc336058f57601c445ec61f62678cefe1af -->
```
        <source>Are you sure you wish to close all wallets?</source>
        <translation>Voulez-vous fermer tous les portefeuilles ?</translation>
    
ERR
The translation omits the "Are you sure" nuance and weakens the prompt.

Correct translation:
Êtes-vous sûr de vouloir fermer tous les portefeuilles ?
```

<!-- cache_translation_check_fr_abb56442c35d5d41cd2738d08384be4b2c0f0fdbef72215b1a650765cd47ff37 -->
```
        <source>You are one step away from creating your new wallet!</source>
        <translation>Vous n’êtes qu’à un pas de créer votre nouveau portefeuille</translation>
    
ERR
Missing exclamation mark and slightly unidiomatic phrasing; more natural with "plus que". 

Correct translation:
Vous n’êtes plus qu’à un pas de créer votre nouveau portefeuille !
```

<!-- cache_translation_check_fr_a731654143daa6bda577e518335c5559a489865a00004601622051ff5b9cce35 -->
```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Désactiver les clés privées pour ce portefeuille. Les portefeuille pour lesquels les clés privées sont désactivées n’auront aucune clé privée et ne pourront ni avoir de graine HD ni de clés privées importées. Cela est idéal pour les portefeuilles juste-regarder.</translation>
    
ERR
- "Les portefeuille" should be plural: "Les portefeuilles".
- "portefeuilles juste-regarder" is incorrect; use "portefeuilles d’observation" (watch-only).

Correct translation:
Désactiver les clés privées pour ce portefeuille. Les portefeuilles pour lesquels les clés privées sont désactivées n’auront aucune clé privée et ne pourront ni avoir de graine HD ni de clés privées importées. Cela est idéal pour les portefeuilles d’observation.
```

<!-- cache_translation_check_fr_7c3d397cc8e6397c5bd0d0d5dc8e43de5631d00345f8d2dc97ff83ac93422b71 -->
```
        <source>Make a blank wallet. Blank wallets do not initially have private keys or scripts. Private keys and addresses can be imported, or an HD seed can be set, at a later time.</source>
        <translation>Créer un portefeuilles vide. Les portefeuilles vides n’ont initialement ni clé privée ni script. Ultérieurement, des clés privées et des adresses peuvent être importées ou une graine HD peut être définie.</translation>
    
ERR
"un portefeuilles" has a number agreement error; it should be singular. Also use plurals for "clés privées" and "scripts" to match the source.

Correct translation:
Créer un portefeuille vide. Les portefeuilles vides n’ont initialement ni clés privées ni scripts. Des clés privées et des adresses peuvent être importées ultérieurement, ou une graine HD peut être définie.
```

<!-- cache_translation_check_fr_9ef62feb7e685791a9f1dae315ab94629a9c0f958199d6bb735d1da9c2be10c2 -->
```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>Quand vous cliquerez sur Valider, %1 commencera à télécharger et à traiter l’intégralité de la chaîne de blocs %4 (%2 Go) en commençant par les transactions les plus anciennes de %3, lors du lancement initial de %4.</translation>
    
ERR
The UI button label "OK" should be preserved; "Valider" changes the meaning and may confuse users.

Correct translation:
Quand vous cliquerez sur OK, %1 commencera à télécharger et à traiter l’intégralité de la chaîne de blocs %4 (%2 Go) en commençant par les transactions les plus anciennes de %3, lors du lancement initial de %4.
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

<!-- cache_translation_check_fr_87a6c82ede3591b7721a4a454e426a72e8ddaa8208c23c67700bdb0e1e3c735a -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>Nombre de fils de &amp;vérification des scripts</translation>
    
ERR
"fils" is incorrect for computing threads in French; it should be "threads" or "fils d'exécution". The current phrasing is misleading.

Correct translation:
Nombre de threads de &vérification des scripts
```

<!-- cache_translation_check_fr_717d4db11e0cfbe8c1f1301e64f9f14b07556dc9da2c147cebd29156589807c1 -->
```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>Définissez le nombre de fils de vérification des scripts. Les valeurs négatives correspondent au nombre de cœurs que vous voulez laisser à la disposition du système.</translation>
    
ERR
"fils" seul est ambigu en français informatique. Il vaut mieux employer "threads" ou "fils d'exécution", et préciser "laisser libres".

Correct translation:
Définissez le nombre de threads (fils d'exécution) de vérification des scripts. Les valeurs négatives correspondent au nombre de cœurs que vous souhaitez laisser libres pour le système.
```

<!-- cache_translation_check_fr_aabb8dfdbd07c20965ee0d8eb4d84b8a14246d47ae6657e982232f2f605e3070 -->
```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>Soustraire ou non les frais du montant par défaut.</translation>
    
ERR
La formulation "les frais du montant par défaut" est ambiguë et peut être comprise comme "les frais du montant par défaut". Il faut exprimer qu'il s'agit de l'option par défaut consistant à soustraire les frais du montant envoyé.

Correct translation:
Définir si, par défaut, les frais doivent être soustraits du montant.
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

<!-- cache_translation_check_fr_630fad75ef575b8e782989332d156469300fc4ff5642dcc37466d3328f6917be -->
```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Afficher ou non les contrôles TBPS.</translation>
    
ERR
The acronym PSBT was incorrectly changed to TBPS. In Bitcoin contexts, the acronym should remain PSBT.

Correct translation:
Afficher ou non les contrôles PSBT.
```

<!-- cache_translation_check_fr_25332b0a201563d4a53c7f38147e1035fd6e058fb4028febefeccfc125393372 -->
```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>Le mode privé est activé dans l’onglet Vue d’ensemble. Pour afficher les montants, décocher Paramètres &gt; Masquer les montants.</translation>
    
ERR
Issues:
- Imperative should be “décochez” instead of the infinitive “décocher”.
- Keep the arrow formatting consistent with the source using “-&gt;” and avoid inserting extra spaces.

Correct translation:
Le mode privé est activé dans l’onglet Vue d’ensemble. Pour afficher les montants, décochez Paramètres-&gt;Masquer les montants.
```

<!-- cache_translation_check_fr_b9bb290de6d62289030ab0b1efe85ced3691c22375e34bdbae82a01a8f189466 -->
```
        <source>PSBT Operations</source>
        <translation>Opérations TBSP</translation>
    
ERR
The acronym is incorrect: "TBSP" is a transposition; it should be "PSBT" and is typically left untranslated in French.

Correct translation:
Opérations PSBT
```

<!-- cache_translation_check_fr_c77f633a950aa90a145a24ba9eab1b7b386099393d92292d1c7e1eb8edbe7763 -->
```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Impossible de démarrer un gestionnaire bitcoin: cliquer-pour-payer</translation>
    
ERR
The colon after "bitcoin" denotes the URI scheme and should be preserved as such; the current French reads awkwardly and uses incorrect hyphenation ("cliquer-pour-payer"). A clearer French rendering is needed.

Correct translation:
Impossible de démarrer le gestionnaire « bitcoin: » (cliquer pour payer)
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

<!-- cache_translation_check_fr_437395b452da6082904aa3013c9d6ba87f73a2b138bc7660ccab1f69018ae6a3 -->
```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>Bienvenue dans la console RPC de %1.
Utilisez les touches de déplacement vers le haut et vers le bas pour parcourir l’historique et %2 pour effacer l’écran.
Utilisez %3 et %4 pour augmenter ou diminuer la taille de la police.
Tapez %5 pour un aperçu des commandes proposées.
Pour plus de précisions sur cette console, tapez %6.
%7AVERTISSEMENT : des escrocs sont à l’œuvre et demandent aux utilisateurs de taper des commandes ici, volant ainsi le contenu de leur portefeuille. N’utilisez pas cette console sans entièrement comprendre les ramifications d’une commande. %8</translation>
    
ERR
There is an unwanted space before the placeholder %8. Per the note, %7 and %8 must not be space-separated from the warning text. Also, the blank line before the warning should be preserved.

Correct translation:
Bienvenue dans la console RPC de %1.
Utilisez les flèches haut et bas pour parcourir l’historique, et %2 pour effacer l’écran.
Utilisez %3 et %4 pour augmenter ou diminuer la taille de la police.
Tapez %5 pour un aperçu des commandes disponibles.
Pour plus d’informations sur l’utilisation de cette console, tapez %6.

%7AVERTISSEMENT : des escrocs sont actifs et demandent aux utilisateurs de taper des commandes ici, volant ainsi le contenu de leur portefeuille. N’utilisez pas cette console sans comprendre pleinement les conséquences d’une commande.%8
```

<!-- cache_translation_check_fr_48822add15909412a70b8d004e509668fe746967aacd9db4ae3abaddbea1bc6c -->
```
        <source>Bech32m (BIP-350) is an upgrade to Bech32, wallet support is still limited.</source>
        <translation>Bech32m (BIP-350) est une évolution de Bech32. La prise en charge par les portefeuille est encore limitée.</translation>
    
ERR
"portefeuille" doit être au pluriel. La traduction comporte une faute de grammaire.

Correct translation:
Bech32m (BIP-350) est une évolution de Bech32. La prise en charge par les portefeuilles est encore limitée.
```

<!-- cache_translation_check_fr_7238d733965325e54a07afdf2566d77f7c0c0673944ec3468470ad92d623137d -->
```
        <source>Request payment to …</source>
        <translation>Demander un paiement à…</translation>
    
ERR
"à" suggests requesting payment from someone, while "to" refers to the destination address. Use a preposition that indicates destination.

Correct translation:
Demander un paiement vers …
```

<!-- cache_translation_check_fr_7f8269c0924cd33543564c46b8d17dc4de1aa2db8c381b83be408278b3892876 -->
```
        <source>Specify a custom fee per kB (1,000 bytes) of the transaction's virtual size.

Note:  Since the fee is calculated on a per-byte basis, a fee rate of "100 satoshis per kvB" for a transaction size of 500 virtual bytes (half of 1 kvB) would ultimately yield a fee of only 50 satoshis.</source>
        <translation>Indiquer des frais personnalisés par Ko (1 000 octets) de taille virtuelle de la transaction.

Note : Les frais étant calculés par octet, un taux de frais de « 100 satoshis par Kov » pour une transaction d’une taille de 500 octets (la moitié de 1 Kov) donneront des frais de seulement 50 satoshis.</translation>
    
ERR
Issues:
- "Kov" is incorrect; it should be "kvB" (kilo virtual byte) and should remain unchanged.
- Missing "virtuels" for "500 virtual bytes".
- Subject-verb agreement and mood: "un taux ... donneront" should be singular and conditional to match "would": "donnerait".
- Minor phrasing/consistency improvements.

Correct translation:
Indiquer des frais personnalisés par Ko (1 000 octets) de la taille virtuelle de la transaction.

Note : Les frais étant calculés à l’octet, un taux de « 100 satoshis par kvB » pour une transaction d’une taille de 500 octets virtuels (la moitié de 1 kvB) donnerait des frais de seulement 50 satoshis.
```

<!-- cache_translation_check_fr_d0cd18aba4db1287083116fc0d9deb0a0487a189adc51da24f4b9b688f24c106 -->
```
        <source>Connect your hardware wallet first.</source>
        <translation>Connecter d’abord le portefeuille matériel.</translation>
    
ERR
Uses the infinitive and definite article instead of the imperative and possessive. Should address the user directly.

Correct translation:
Connectez d’abord votre portefeuille matériel.
```

<!-- cache_translation_check_fr_432c2b270c73fb2322fc6b4d18abfdda8763e597763accc0db26352cc94ffa18 -->
```
        <source>Set external signer script path in Options -&gt; Wallet</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>Définir le chemin du script de signataire externe dans Options &gt; Portefeuille</translation>
    
ERR
The arrow separator is incorrect. The source uses "->" (escaped as -&gt;). The translation removed the hyphen, changing the UI cue.

Correct translation:
Définir le chemin du script de signataire externe dans Options -&gt; Portefeuille
```

<!-- cache_translation_check_fr_801bcd713503ce39c3e0bd1f48d3fb3d77525be0de45632baa8dc63398ce493e -->
```
        <source>Creates a Partially Signed Bitcoin Transaction (PSBT) for use with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <translation>Crée une transaction Bitcoin signée partiellement (TBSP) à utiliser, par exemple, avec un portefeuille %1 hors ligne ou avec un portefeuille matériel compatible TBSP.</translation>
    
ERR
The acronym is incorrect: PSBT should be kept as PSBT, not TBSP, as it is a standardized term in Bitcoin. Also, "partiellement signée" is the more natural order in French.

Correct translation:
Crée une transaction Bitcoin partiellement signée (PSBT) à utiliser, par exemple, avec un portefeuille %1 hors ligne ou avec un portefeuille matériel compatible PSBT.
```

<!-- cache_translation_check_fr_6c6a3bde166b009302dcd225bda28ca282f17116c7866dc75fd751d8408db2b7 -->
```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>Vérifiez votre proposition de transaction. Une transaction Bitcoin partiellement signée (TBSP) sera produite, que vous pourrez enregistrer ou copier puis signer avec, par exemple, un portefeuille %1 hors ligne ou avec un portefeuille matériel compatible TBSP.</translation>
    
ERR
The acronym PSBT should not be translated; it must remain PSBT in French as used in the Bitcoin ecosystem. The translation uses "TBSP" incorrectly.

Correct translation:
Vérifiez votre proposition de transaction. Une transaction Bitcoin partiellement signée (PSBT) sera produite, que vous pourrez enregistrer ou copier puis signer avec, par exemple, un portefeuille %1 hors ligne ou avec un portefeuille matériel compatible PSBT.
```

<!-- cache_translation_check_fr_a89f3d1465107a94adc329addd6f7f22b1c6e15cb0c60fc277bd7667094240db -->
```
        <source>%1 from wallet '%2'</source>
        <translation>%1 du portefeuille « %2 ».</translation>
    
ERR
The translation adds a period that is not present in the source.

Correct translation:
%1 du portefeuille « %2 »
```

<!-- cache_translation_check_fr_8592a58a60a4b28fa16960dfde4f8c6d9515e8f38afbdf59f200d67a91f20f79 -->
```
        <source>Please, review your transaction. You can create and send this transaction or create a Partially Signed Bitcoin Transaction (PSBT), which you can save or copy and then sign with, e.g., an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can send their transaction or create a PSBT. This string is displayed when both private keys and PSBT controls are enabled.</extracomment>
        <translation>Révisez votre transaction. Vous pouvez créer et envoyer cette transaction ou créer une transaction Bitcoin partiellement signée (TBSP), que vous pouvez enregistrer ou copier, et ensuite avec laquelle signer, par ex., un portefeuille %1 hors ligne ou avec un portefeuille matériel compatible TBSP.</translation>
    
ERR
L’abréviation PSBT a été incorrectement traduite en TBSP, et la syntaxe "et ensuite avec laquelle signer" est maladroite.
Correct translation:
Veuillez vérifier votre transaction. Vous pouvez créer et envoyer cette transaction ou créer une transaction Bitcoin partiellement signée (PSBT), que vous pouvez enregistrer ou copier, puis signer, par ex., à l’aide d’un portefeuille %1 hors ligne ou d’un portefeuille matériel compatible PSBT.
```

<!-- cache_translation_check_fr_38fd241fec7a7fd664063f2e6a85f2fd3b1f431fb3d73dc9100d4f5364cb17ba -->
```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Saisissez ci-dessous l’adresse du destinataire, le message (assurez-vous de copier fidèlement les retours à la ligne, les espaces, les tabulations, etc.) et la signature pour vérifier le message. Faites attention à ne pas déduire davantage de la signature que ce qui est contenu dans le message signé même, pour éviter d’être trompé par une attaque de l’intercepteur. Notez que cela ne fait que prouver que le signataire reçoit avec l’adresse et ne peut pas prouver la provenance d’une transaction.</translation>
    
ERR
The phrase "attaque de l’intercepteur" is not the standard translation for "man-in-the-middle attack" and "le signataire reçoit avec l’adresse" is awkward. Also improved clarity for "sendership."

Correct translation:
Saisissez ci-dessous l’adresse du destinataire, le message (assurez-vous de copier exactement les retours à la ligne, les espaces, les tabulations, etc.) ainsi que la signature, afin de vérifier le message. Veillez à ne rien déduire de la signature qui ne figure pas déjà dans le message signé lui-même, afin d’éviter d’être trompé par une attaque de l’homme du milieu (MITM). Notez que cela prouve uniquement que le signataire peut recevoir avec cette adresse ; cela ne prouve pas qu’il est l’expéditeur d’une transaction.
```

<!-- cache_translation_check_fr_66280ec5f795d9de8c3977d18190c89f62d22c58e32fcde1b10b5727f257006e -->
```
        <source>Private key for the entered address is not available.</source>
        <translation>La clé privée correspondant à l’adresse saisie est introuvable</translation>
    
ERR
Missing ending period and wording deviates from "not available" (translated as "introuvable"). Closer to source meaning:
La clé privée correspondant à l’adresse saisie n’est pas disponible.
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

<!-- cache_translation_check_fr_b7ce5dffdea406ec345545539b0ecd45209bcd2f17b1982e2044247f86f08bf7 -->
```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>Le fichier TBSP doit être inférieur à 100 Mio</translation>
    
ERR
The acronym is incorrect: "PSBT" was mistakenly translated as "TBSP". It should remain "PSBT". Otherwise the translation is fine.

Correct translation:
Le fichier PSBT doit être inférieur à 100 Mio
```

<!-- cache_translation_check_fr_7ee508c6515223b4a8f9f11c44547010c6127af059a37696d6e2c0b5c4bd4d99 -->
```
        <source>There was an error trying to save the wallet data to %1.</source>
        <translation>Une erreur est survenue lors de l’enregistrement des données du portefeuille vers %1.</translation>
    
ERR
The translation omits the "trying" nuance and uses the awkward preposition "vers" for saving to a location. "Dans %1" is more appropriate.

Correct translation:
Une erreur est survenue en essayant d’enregistrer les données du portefeuille dans %1.
```

<!-- cache_translation_check_fr_1324df018e242decd9e8bf67ecc7f730aa103c12c4bf390c0e42a349d6159409 -->
```
        <source>The wallet data was successfully saved to %1.</source>
        <translation>Les données du portefeuille ont été enregistrées vers %1.</translation>
    
ERR
The preposition "vers" is inappropriate here; "dans" is correct for saving to a location. The adverb "successfully" is also omitted. The format specifier %1 is correctly preserved.

Correct translation:
Les données du portefeuille ont été enregistrées avec succès dans %1.
```

<!-- cache_translation_check_fr_f3841de1a5e8eb3bc9b5b5fd101957a11b3829421045a37cc44a7219ab7e88fb -->
```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>%s n’a pas réussi à valider l’état de l’instantané -assumeutxo. Cela indique un problème matériel, un bogue logiciel ou une mauvaise modification logicielle qui a permis le chargement d’un instantané invalide. C’est pourquoi le nœud s’arrêtera et cessera d’utiliser tout état fondé sur cet instantané, ce qui réinitialisera le niveau de la chaîne de %d à %d. Lors du prochain démarrage, le nœud reprendra synchronisation à partir de %d, sans utiliser de données d’instantané. Signalez cet incident à %s en indiquant comment vous avez obtenu l’instantané. L’état de la chaîne provenant de l’instantané invalide sera laissé sur le disque  au cas où cela pourrait aider à diagnostiquer le problème à l’origine de cette erreur.</translation>
    
ERR
Issues found:
- Terminology: "niveau de la chaîne" should be "hauteur de la chaîne" for "chain height".
- Grammar: "reprendra synchronisation" should be "reprendra la synchronisation".
- Whitespace: double space before "au cas".

Correct translation:
%s n’a pas réussi à valider l’état de l’instantané -assumeutxo. Cela indique un problème matériel, un bogue logiciel ou une mauvaise modification logicielle qui a permis le chargement d’un instantané invalide. En conséquence, le nœud s’arrêtera et cessera d’utiliser tout état fondé sur cet instantané, ce qui réinitialisera la hauteur de la chaîne de %d à %d. Lors du prochain redémarrage, le nœud reprendra la synchronisation à partir de %d, sans utiliser de données d’instantané. Veuillez signaler cet incident à %s, en indiquant comment vous avez obtenu l’instantané. L’état de la chaîne provenant de l’instantané invalide sera laissé sur le disque au cas où cela pourrait aider à diagnostiquer le problème à l’origine de cette erreur.
```

<!-- cache_translation_check_fr_4bb1f2bde5bda8eac26c16423e9ae109e07691312ed24d356ea55cb3a62978e8 -->
```
        <source>Error loading wallet. Wallet requires blocks to be downloaded, and software does not currently support loading wallets while blocks are being downloaded out of order when using assumeutxo snapshots. Wallet should be able to load successfully after node sync reaches height %s</source>
        <translation>Erreur de chargement du portefeuille. Le portefeuille exige le téléchargement de blocs, toutefois le logiciel ne prend pas actuellement en charge le chargement de portefeuilles pendant que des blocs sont téléchargés dans le désordre lors de l’utilisation d’instantanés assumeutxo. Le portefeuille devrait pouvoir se charger une fois que la synchronisation des nœuds aura atteint la hauteur %s</translation>
    
ERR
The translation incorrectly uses the plural "nœuds" instead of the singular "nœud" for "node sync". Everything else, including the %s placeholder and spacing, is fine.

Correct translation:
Erreur de chargement du portefeuille. Le portefeuille nécessite le téléchargement de blocs, et le logiciel ne prend actuellement pas en charge le chargement de portefeuilles pendant que des blocs sont téléchargés dans le désordre lors de l’utilisation d’instantanés assumeutxo. Le portefeuille devrait pouvoir se charger une fois que la synchronisation du nœud aura atteint la hauteur %s
```

<!-- cache_translation_check_fr_b5cebd9d047a38995c7c4cf684084306114835a813382a12f4da1c738f50cb3c -->
```
        <source>Invalid value detected for '-wallet' or '-nowallet'. '-wallet' requires a string value, while '-nowallet' accepts only '1' to disable all wallets</source>
        <translation>Une valeur invalide a été détectée pour « -wallet » ou pour « -nowallet ». « -wallet » demande une valeur de chaine alors que « -nowallet » n’accepte que « 1 » pour désactiver tous les portefeuilles</translation>
    
ERR
"chaine" should be "chaîne" (missing accent). Also "string value" is better rendered as "valeur de chaîne de caractères," and "requiert/tandis que" reads more naturally.

Correct translation:
Une valeur invalide a été détectée pour « -wallet » ou « -nowallet ». « -wallet » requiert une valeur de chaîne de caractères, tandis que « -nowallet » n’accepte que « 1 » pour désactiver tous les portefeuilles
```

<!-- cache_translation_check_fr_e19b91fd3a9810a9cfd673914ec4d360bc6009509875ac0998aa328585a8d12c -->
```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Avertissement : Des clés privées ont été détectées dans le portefeuille {%s} avec des clés privées désactivées</translation>
    
ERR
The phrase implies the wallet has private keys disabled; the current French reads as if specific keys are disabled. Also, in French, the word after the colon should not be capitalized.

Correct translation:
Avertissement : des clés privées ont été détectées dans le portefeuille {%s} alors que les clés privées y sont désactivées
```

<!-- cache_translation_check_fr_4e7924a117e8b2295004b3044e790d16ff6337592fbf5b41f751dc28b5701b3d -->
```
        <source>%s is set very high!</source>
        <translation>La valeur %s est très élevée !</translation>
    
ERR
In French, it should be "La valeur de %s" (value of %s). Without "de", it implies %s is the value itself. Also keeps the %s placeholder correctly.

Correct translation:
La valeur de %s est très élevée !
```

<!-- cache_translation_check_fr_83e029532c5cd9a4856a59297de394888a0dce8fab7cb213cdc2744055868338 -->
```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>Les connexions sortantes sont limitées à Tor (-onlynet=onion), mais le mandataire pour accéder au réseau Tor n’est pas indiqué : ni -proxy, ni -onion, ni -listenonion n’est indiqué </translation>
    
ERR
The French sentence has a grammatical error: with “ni … ni … ni …” as the subject, the verb should be plural (“ne sont …”), not singular (“n’est …”). There is also a trailing space at the end. Using “proxy” is more standard in technical French.

Correct translation:
Les connexions sortantes sont limitées à Tor (-onlynet=onion), mais le proxy pour accéder au réseau Tor n’est pas renseigné : aucune des options -proxy, -onion ou -listenonion n’est fournie.
```

<!-- cache_translation_check_fr_c3bf5fffa7dde0e77bb2a92804732b453b5a435bd6e92c3147b550b9cd502494 -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>Élagage : la dernière synchronisation de portefeuille dépasse les données élaguées. Vous devez utiliser « -reindex » (retélécharger toute la chaîne de blocs au cas ou un nœud a été élagué)</translation>
    
ERR
Minor issues:
- Missing accent in "au cas où".
- Tense/wording: "a été élagué" suggests past perfect; better as a general condition.
- Slightly clearer to mention it's an option: "l’option -reindex".

Correct translation:
Élagage : la dernière synchronisation du portefeuille dépasse les données élaguées. Vous devez utiliser l’option -reindex (retélécharger toute la chaîne de blocs dans le cas d’un nœud élagué)
```

<!-- cache_translation_check_fr_4fdc5eb5c05897d5b0bc6ed3d1cff517401668dd2f47744fdb9fb079bdad2948 -->
```
        <source>The inputs size exceeds the maximum weight. Please try sending a smaller amount or manually consolidating your wallet's UTXOs</source>
        <translation>La taille des entrées dépasse le poids maximum. Essayez d’envoyer un montant plus petit ou de consolider manuellement les UTXO de votre portefeuille</translation>
    
ERR
Missing final period. "Poids maximal" is slightly more idiomatic than "poids maximum" in this context.

Correct translation:
La taille des entrées dépasse le poids maximal. Essayez d’envoyer un montant plus petit ou de consolider manuellement les UTXO de votre portefeuille.
```

<!-- cache_translation_check_fr_f21d3fd3379e9816584587026efe665ee6147a61c1e5d65e39df2eb93f076fb6 -->
```
        <source>Unexpected legacy entry in descriptor wallet found. Loading wallet %s

The wallet might have been tampered with or created with malicious intent.
</source>
        <translation>Une entrée héritée inattendue a été trouvée dans le portefeuille à descripteurs. Chargement du portefeuille %s

Le portefeuille a peut-être avoir été altéré ou créé avec des intentions malveillantes.
</translation>
    
ERR
Grammatical error: "a peut-être avoir été" is incorrect. It should be "a peut-être été".

Correct translation:
Une entrée héritée inattendue a été trouvée dans le portefeuille à descripteurs. Chargement du portefeuille %s

Le portefeuille a peut-être été altéré ou créé avec des intentions malveillantes.
```

<!-- cache_translation_check_fr_4738253759542b323f295d5d04a7d938e39879bce975ef05e58ecda159ee71aa -->
```
        <source>
Unable to restore backup of wallet.</source>
        <translation>
Impossible de restaurer la sauvegarde du portefeuille</translation>
    
ERR
Missing final period in the French translation.

Correct translation:
Impossible de restaurer la sauvegarde du portefeuille.
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

<!-- cache_translation_check_fr_f0bc28df0c1611396c9b7cfcd88a4e3d47f014214eec5d752d82ee80998b07c2 -->
```
        <source>Error: Failed to create new watchonly wallet</source>
        <translation>Erreur : Échec de création d’un nouveau portefeuille juste-regarder</translation>
    
ERR
"watchonly" is mistranslated as "juste-regarder" and the phrasing "Échec de création" is awkward; it should be "Échec de la création".

Correct translation:
Erreur : Échec de la création d’un nouveau portefeuille en lecture seule
```

<!-- cache_translation_check_fr_a64fa75d29f490c316a8e5a872a0b686ad39827c5d9a4ffa195e6dede23c9a8e -->
```
        <source>Error: Unable to read wallet's best block locator record</source>
        <translation>Erreur : Impossible de lire l’enregistrement du meilleur bloc du portefeuille.</translation>
    
ERR
The translation omits the term "locator" (block locator is a specific Bitcoin term), changing the meaning.

Correct translation:
Erreur : Impossible de lire l’enregistrement du localisateur du meilleur bloc du portefeuille.
```

<!-- cache_translation_check_fr_623deb5df6bbf4cedfe2559ffd126a2eea26b43a367a5791ad539fce432a94e9 -->
```
        <source>Error: Unable to write solvable wallet best block locator record</source>
        <translation>Erreur : Impossible d’écrire l’enregistrement du localisateur du meilleur bloc pour le portefeuille soluble</translation>
    
ERR
“soluble” is incorrect; it should be “résoluble” in this Bitcoin context. Also “pour le portefeuille” is better as a genitive “du portefeuille”.

Correct translation:
Erreur : impossible d’écrire l’enregistrement du localisateur du meilleur bloc du portefeuille résoluble
```

<!-- cache_translation_check_fr_ef33e4997227feda4265ce5246ba6b64c7164741fc7196c7287675b018554e74 -->
```
        <source>Error: Unable to write watchonly wallet best block locator record</source>
        <translation>Erreur : Impossible d’écrire l’enregistrement du localisateur du meilleur bloc du portefeuille juste-regarder</translation>
    
ERR
"watchonly wallet" is mistranslated as "portefeuille juste-regarder". Use standard French terminology like "portefeuille en lecture seule" or "portefeuille en observation".

Correct translation:
Erreur : impossible d’écrire l’enregistrement du localisateur du meilleur bloc du portefeuille en lecture seule
```

<!-- cache_translation_check_fr_297cc1b54c25bfca960aed9aa4916fe9a21dd4176ddf220b0f7b180270ab631f -->
```
        <source>Error: database transaction cannot be executed for wallet %s</source>
        <translation>Erreur ; La transaction de la base de données ne peut pas être exécutée pour le portefeuille %s</translation>
    
ERR
Uses a semicolon instead of a colon and incorrectly capitalizes the following word. Correct French punctuation is a colon with a non-breaking space and a lowercase continuation.

Correct translation:
Erreur : la transaction de base de données ne peut pas être exécutée pour le portefeuille %s
```

<!-- cache_translation_check_fr_ae0d56b2bb00fe6ef387a210ea96c9ca1a1be45f876ca39d0bf6f07735a292c5 -->
```
        <source>Failed to acquire rescan reserver during wallet initialization</source>
        <translation>Échec de réservation pour nouvelle analyse lors de l’initialisation du portefeuille</translation>
    
ERR
"nouvelle analyse" should be "réanalyse" to match "rescan", and "Échec de réservation" is awkward; better to express failure to obtain the reservation.

Correct translation:
Échec de l’obtention d’une réservation de réanalyse lors de l’initialisation du portefeuille
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

<!-- cache_translation_check_fr_01e234279a13725418a652221342d9b755a97586d132f4259ec705231ff5d2e3 -->
```
        <source>Failed to rescan the wallet during initialization</source>
        <translation>Échec de réanalyse du portefeuille lors de l’initialisation</translation>
    
ERR
Minor grammar issue: missing definite article before "réanalyse".

Correct translation:
Échec de la réanalyse du portefeuille lors de l’initialisation
```

<!-- cache_translation_check_fr_47cb708673562601e4001af8b6ed8541e96cbf4534e0cf45dda9d4f87cbbd13b -->
```
        <source>Insufficient dbcache for block verification</source>
        <translation>dbcache est insuffisant pour la vérification des blocs</translation>
    
ERR
French grammar/style is awkward with the verb "est" but no article. Prefer a concise error-style phrasing.

Correct translation:
dbcache insuffisant pour la vérification des blocs
```

<!-- cache_translation_check_fr_420e80abe8521da757d847cbd91e4258e7c20e618c869b9d5413e8355da0c5d0 -->
```
        <source>SQLiteDatabase: Failed to prepare statement to verify database: %s</source>
        <translation>SQLiteDatabase : échec de préparation de l’instruction pour vérifier la base de données : %s</translation>
    
ERR
Slight grammatical issue: it should be "échec de la préparation".
Correct translation:
SQLiteDatabase : échec de la préparation de l’instruction pour vérifier la base de données : %s
```

<!-- cache_translation_check_fr_5f6cb6f91d5c6bdd5ddd5a5ef3803060dc9439590101331c64803abf4253dd66 -->
```
        <source>SQLiteDatabase: Failed to read database verification error: %s</source>
        <translation>SQLiteDatabase : échec de lecture de l’erreur de vérification de la base de données : %s</translation>
    
ERR
The French suggests a failure to read the error itself, rather than a failure to read the database due to a verification error.

Correct translation:
SQLiteDatabase : échec de lecture de la base de données, erreur de vérification : %s
```

<!-- cache_translation_check_fr_92006d83b183ee429ac35ccbf54d6e5393a8d54fe0e99022dd568928e28cad80 -->
```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>Les frais que vous payerez si vous envoyez une transaction.</translation>
    
ERR
The translation omits "de transaction" after "frais," which is needed for accuracy. Also, "paierez" is the more standard spelling.

Correct translation:
Il s’agit des frais de transaction que vous paierez si vous envoyez une transaction.
```

<!-- cache_translation_check_fr_52a6a4151d7a6c28bfec98d3e7097dff322f3a62b6fad834cf60c0af38cdd092 -->
```
        <source>Transaction change output index out of range</source>
        <translation>L’index des sorties de monnaie de la transaction est hors échelle</translation>
    
ERR
"Hors échelle" is incorrect here; use "hors limites/hors plage". Also, "sorties" should be singular.

Correct translation:
L’indice de la sortie de monnaie de la transaction est hors limites
```

<!-- cache_translation_check_fr_2c37f9fa8248b9a0bd75b0b65a2871fc03e707adc2fe87c7ffbc26b7f79bf3ac -->
```
        <source>Transaction too large</source>
        <translation>La transaction est trop importante</translation>
    
ERR
"trop importante" suggests importance, not size. For data size, use "volumineuse".

Correct translation:
Transaction trop volumineuse
```

<!-- cache_translation_check_fr_4d61fc86ae3d8e5724af2305655c82d80b3be4f4d3b67ba789d87694ba06a9f3 -->
```
        <source>Wallet file creation failed: %s</source>
        <translation>Échec de création du fichier du portefeuille : %s</translation>
    
ERR
French phrasing is slightly incorrect; it should include the article "la" and use "de portefeuille" rather than "du portefeuille" for "wallet file."

Correct translation:
Échec de la création du fichier de portefeuille : %s
```

<!-- cache_translation_check_fr_4a1beef2635865808149916d14b92d26b4eca1b7bd9857a3f56f416d1f96c629 -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>Erreur de chargement de %s : la version du portefeuille est ancienne. Migrez vers un portefeuille à descripteurs à l’aide de l’outil de migration (migratewallet RPC).</translation>
    
ERR
"Wallet is a legacy wallet" refers to the wallet type/format, not an old version. The translation "la version du portefeuille est ancienne" is misleading.

Correct translation:
Erreur de chargement de %s : le portefeuille est un portefeuille hérité. Veuillez migrer vers un portefeuille à descripteurs à l’aide de l’outil de migration (migratewallet RPC).
```

<!-- cache_translation_check_fr_c08e70b9a40f79ff88cf6fb6868711dc42f0a7620cc0f7bff3951d94379d3cfb -->
```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on an enormous cluster of unconfirmed transactions.</source>
        <translation>Échec de calcul des frais de majoration, car les UTXO non confirmés dépendent d’une énorme grappe de transactions non confirmées.
 </translation>
    
ERR
There is an extra trailing line break and stray space in the translation, and “Échec du calcul” is the correct phrasing.

Correct translation:
Échec du calcul des frais de majoration, car les UTXO non confirmés dépendent d’une énorme grappe de transactions non confirmées.
```

<!-- cache_translation_check_fr_bea73fd1fb3dc8181d120dc944e5155c8bd805a3400ad573b1480e7cb0ccfd69 -->
```
        <source>Error: cannot remove legacy wallet records</source>
        <translation>Erreur : Impossible de supprimer les enregistrements d’anciens portefeuilles</translation>
    
ERR
"Legacy wallet" in Bitcoin Core is typically translated as "portefeuille hérité," not "anciens portefeuilles." Also, in French, the word after the colon should generally be lowercase.

Correct translation:
Erreur : impossible de supprimer les enregistrements du portefeuille hérité
```

<!-- cache_translation_check_fr_a4ff5ae4151731a5858b430eb753c6c65db714ac239364c958825f45504cd03c -->
```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Le nombre de descripteurs de fichiers est insuffisant. %d libres, %d nécessaires</translation>
    
ERR
Missing final period. Also, "disponibles" is a closer match to "available."

Correct translation:
Le nombre de descripteurs de fichiers est insuffisant. %d disponibles, %d nécessaires.
```

<!-- cache_translation_check_fr_2110d5d7aaeb8d7d6801052ee011ff00044203da451c18735029591c8ae235a5 -->
```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Le portefeuille devait être réécrit : redémarrer %s pour terminer l’opération.</translation>
    
ERR
The verb after the colon should be in the imperative in French. Also “a dû être réécrit” is more natural than “devait être réécrit”.

Correct translation:
Le portefeuille a dû être réécrit : redémarrez %s pour terminer.
```
</details>

Number of issues: 83.
