# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>fr</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bfr%5D%20low%20quality)


<!-- cache_translation_check_fr_eafadccade984155c3ab3302171f6f699085577057470b60a4c820f1eb60a909 -->
```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Une erreur est survenue lors de l’enregistrement de la liste d’adresses vers %1. Rréessayez plus tard.</translation>
    
ERR
There is a typographical error in the translation: "Rréessayez" should be "Réessayez". Also, "plus tard" changes the meaning; the original says to try again, not necessarily later. "Veuillez réessayer." matches the original more closely. Additionally, "vers %1" is correct, but more commonly "dans %1" (in %1) fits file saving.

Correct translation:
Une erreur est survenue lors de l’enregistrement de la liste d’adresses dans %1. Veuillez réessayer.
```

<!-- cache_translation_check_fr_c09b35b2349c89ce1c678665da7385623fa8e4a9d99394f93292f517a629d932 -->
```
        <source>%1 m</source>
        <translation>%1 min</translation>
    
ERR
While "min" is a commonly understood abbreviation for "minutes" in French, the source uses "m", likely as a generic abbreviation (perhaps for "minutes" or "meters"). In French interfaces, "min" is usual for "minutes". If context requires strict adherence to the source format specifier, the translation should maintain "m". If the display is explicitly for "minutes", "min" is correct.

However, if "m" could be ambiguous or refer to "meters", keeping "m" would be better. 

Assuming the context is minutes:

NO

If context dictates strict copying of the abbreviation "m":

ERR
The abbreviation differs from the source. If "m" is intentionally generic, to remain faithful, use:

Correct translation:
%1 m

Otherwise, if context is minutes, "min" is accepted and common, so the translation is unproblematic.

Summary: If the context is minutes, "NO". If strict preservation is needed, "YES", translation should be "%1 m".
```

<!-- cache_translation_check_fr_081e730592c1ffd25fba0ffe7d9c2f301bc9b1aaccd8355221fae64fe4f2b3bf -->
```
        <source>%1 B</source>
        <translation>%1 o</translation>
    
ERR
The French translation uses "o" for "octet", but in contexts like Bitcoin and technical fields, "B" (for "byte") is standard, even in French, to avoid confusion with "bit" ("b"). The translation changes the unit symbol inappropriately.

Correct translation:
%1 B
```

<!-- cache_translation_check_fr_12a858477bd71fc6b82ea6da0602eff7ac0eb3a8492fa2c5a6684e6a643af7af -->
```
        <source>Cannot create new wallet, the software was compiled without sqlite support (required for descriptor wallets)</source>
        <translation>Impossible de créer un nouveau portemonnaies. Le logiciel a été compilé sans prise en charge de sqlite (nécessaire pour les portemonnaies de descripteurs) </translation>
    
ERR
There are some issues with the translation:

1. "portemonnaies" should be "portefeuille" in singular, as "wallet" is singular in the English sentence.
2. The plural "portemonnaies" is rarely used in French in the Bitcoin context; "portefeuille" is the standard term.
3. "de descripteurs" is awkward; "à descripteurs" is more natural in this context.
4. The definite article "Le logiciel" should not be capitalized after a period, as in French, after a period that ends a sentence, you start with a capital. However, if you split the sentence which wasn't done in the original, it's okay. Here, the translation matches the two sentences style, but the English is one long sentence, so the translation should also be one sentence.
5. Extra whitespace at the end.

Correct translation:
Impossible de créer un nouveau portefeuille : le logiciel a été compilé sans prise en charge de sqlite (nécessaire pour les portefeuilles à descripteurs)
```

<!-- cache_translation_check_fr_229b9f3152a201b44944a7f36e15b1af786b6f3b03532fd0915180583b023036 -->
```
        <source>Type: %1
</source>
        <translation>Type  : %1
</translation>
    
ERR
There is an unwanted space before the colon in the French translation. In French typographic rules, a non-breaking space is typically used before a colon, but in software UI translations it is common and acceptable to use a regular space, but never an extra space as in "Type  : %1".

Correct translation:
Type : %1
```

<!-- cache_translation_check_fr_3fe5ef77cb009362912b8af0289d6708366bcbe3e2d250dfcf1346daf5aba60c -->
```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>Quand vous cliquerez sur Valider, %1 commencera à télécharger et à traiter l’intégralité de la chaîne de blocs %4 (%2 Go) en débutant avec les transactions les plus anciennes de %3, lors du lancement de %4 a été lancé initialement.</translation>
    
ERR
There is a grammatical issue in the last part: "lors du lancement de %4 a été lancé initialement." ("lors du lancement de %4" or "quand %4 a été lancé initialement", but not both merged). The sentence is redundant and awkward in French.

Correct translation:
Quand vous cliquerez sur OK, %1 commencera à télécharger et à traiter l’intégralité de la chaîne de blocs %4 (%2 Go), en commençant par les transactions les plus anciennes de %3, lorsque %4 a été lancé initialement.
```

<!-- cache_translation_check_fr_ccdae3ff5c2404764a36cc86c5a9fc76670ed6e580639f0c17021e9c4f585694 -->
```
        <source>If you disable the spending of unconfirmed change, the change from a transaction cannot be used until that transaction has at least one confirmation. This also affects how your balance is computed.</source>
        <translation>Si vous désactivé la dépense de la monnaie non confirmée, la monnaie d’une transaction ne peut pas être utilisée tant que cette transaction n’a pas reçu au moins une confirmation. Celai affecte aussi le calcul de votre solde.</translation>
    
ERR
There are grammatical errors in the French translation: 
- "désactivé" should be "désactivez" (subjunctive present or infinitive depending on formal phrasing, but here "désactivez" for imperative or "vous désactivez" for indicative is correct).
- "Celai" is a typographical mistake; it should be "Cela".

Correct translation:
Si vous désactivez la dépense de la monnaie non confirmée, la monnaie d’une transaction ne peut pas être utilisée tant que cette transaction n’a pas reçu au moins une confirmation. Cela affecte aussi le calcul de votre solde.
```

<!-- cache_translation_check_fr_e0c5e5997126307020b9f18decd3da18cc844207c4516c618f7aed1ba3cd8bde -->
```
        <source>Enable PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Activer les contrôles TBPS</translation>
    
ERR
The abbreviation "TBPS" is incorrect in French; it should remain "PSBT" because "PSBT" (Partially Signed Bitcoin Transaction) is a standard technical term in Bitcoin and is not typically translated or rearranged for French.

Correct translation:
Activer les contrôles PSBT
```

<!-- cache_translation_check_fr_ffa3bcece099002a4168e4848493d2dd510d9a10a2ae4323871921a5ae55ac97 -->
```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Affichez ou non les contrôles TBPS.</translation>
    
ERR
The translation introduces two issues:
1. The abbreviation "TBPS" is incorrect; it should be "PSBT" ("Partially Signed Bitcoin Transaction").
2. The French translation "Affichez ou non les contrôles TBPS." is an imperative or instruction ("Display or not...") rather than a descriptive phrase about an option like the English source ("Whether to show...").

Correct translation:
Afficher ou non les contrôles PSBT.
```

<!-- cache_translation_check_fr_fc7b9eb17463fc9d072a2fe8724d2910df925f24746501950b09486211107c4f -->
```
        <source>Third-party transaction URLs</source>
        <translation>URL de transaction de $tiers</translation>
    
ERR
There are two issues:
1. The format specifier "$tiers" is incorrect; "%tiers" should not be used unless it's in the source. "Tiers" here should simply be translated as "tiers".
2. "URL de transaction" should be plural to match "URLs" in the source.
3. "Tiers" is an adjective here; the correct phrase is "tiers" (third-party), and it should pluralize "URL" appropriately.

Correct translation:
URLs de transaction de tiers
```

<!-- cache_translation_check_fr_510f30d5b2f4905ce45bc378f811343af5df944d52defa30bff651e289104959 -->
```
        <source>Your current balance in watch-only addresses</source>
        <translation>Votre balance actuelle en adresses juste-regarder</translation>
    
ERR
The translation is problematic. "juste-regarder" is not a correct or idiomatic translation for "watch-only" in the context of Bitcoin. In French, the term "adresses en lecture seule" or "adresses en mode observation" is standard for "watch-only addresses". Additionally, "balance" should be "solde" in financial context.

Correct translation:
Votre solde actuel dans les adresses en lecture seule
```

<!-- cache_translation_check_fr_91d748224fad1ac87818b27b8524dd55c84cff5c45ab1ff5c26e7791e21a0c6d -->
```
        <source>Unconfirmed transactions to watch-only addresses</source>
        <translation>Transactions non confirmées vers des adresses juste-regarder</translation>
    
ERR
The translation "adresses juste-regarder" is incorrect and unnatural in French. The correct term for "watch-only" in the Bitcoin context is "adresses en lecture seule" or "adresses en surveillance" or simply "adresses de surveillance".

Correct translation:
Transactions non confirmées vers des adresses en lecture seule

Or, alternatively:
Transactions non confirmées vers des adresses de surveillance
```

<!-- cache_translation_check_fr_f1cf9da32bbdb3365ef973efdb62456f46eef953c46bafa1194cf62f0fcc4be7 -->
```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>Le solde miné dans des adresses juste-regarder, qui n’est pas encore mûr</translation>
    
ERR
The translation has a few issues:
1. "juste-regarder" is not the standard term for "watch-only" in French; "en lecture seule" or "d’observation" is more appropriate.
2. "qui n’est pas encore mûr" is awkward; "qui n’a pas encore maturé" or "qui n’est pas encore mature" is better.

Correct translation:
Le solde miné dans des adresses en lecture seule qui n’a pas encore maturé
```

<!-- cache_translation_check_fr_ed11f42bc96fc2e8855836976413808732558c30af2b7249dab4648ce5e2cf51 -->
```
        <source>Current total balance in watch-only addresses</source>
        <translation>Solde total actuel dans des adresses juste-regarder</translation>
    
ERR
The translation is understandable but problematic: "juste-regarder" is a literal and awkward translation of "watch-only". The commonly accepted term in French for "watch-only" is "visualisation seule" or "adresses en lecture seule", depending on software context.

Correct translation:
Solde total actuel dans des adresses en lecture seule
```

<!-- cache_translation_check_fr_e6c68a40f89e9df803f1a9fb999b49275697be9c7775ec7ea92c813e9e6d39e9 -->
```
        <source>PSBT Operations</source>
        <translation>Opération TBSP</translation>
    
ERR
The translation "Opération TBSP" is problematic for two reasons:
1. "PSBT" should not be translated as "TBSP". PSBT stands for "Partially Signed Bitcoin Transaction" and should remain "PSBT" in French technical contexts.
2. "Opérations" should be plural to match the source ("Operations"), and the singular form "Opération" does not correspond.

Correct translation:
Opérations PSBT
```

<!-- cache_translation_check_fr_1010231c057ee49af96234a0ef5f309d3aec35a7543c3416259831e47ff11cb2 -->
```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Impossible de démarrer le gestionnaire de cliquer-pour-payer bitcoin:</translation>
    
ERR
There are several issues:
- The translation structure is awkward and does not accurately reflect the English text.
- "cliquer-pour-payer" is a literal translation and not idiomatic. The commonly used phrase is "cliquez pour payer".
- The colon at the end should not be present unless in the source.
- The order should be improved for clarity and naturalness in French.

Correct translation:
Impossible de démarrer le gestionnaire bitcoin « cliquez pour payer »
```

<!-- cache_translation_check_fr_f47a9ab2871af05f079adb64673019ee4f0b6227b394a4423d5125aba2bc1269 -->
```
        <source>Whether we relay addresses to this peer.</source>
        <extracomment>Tooltip text for the Address Relay field in the peer details area, which displays whether we relay addresses to this peer (Yes/No).</extracomment>
        <translation>Reliez ou non des adresses à ce pair.</translation>
    
ERR
The translation is slightly inaccurate. "Reliez ou non des adresses à ce pair." suggests actively connecting addresses to the peer, not relaying/broadcasting them. The correct translation should capture the meaning of "relay (transmit) addresses to this peer".

Correct translation:
Indique si nous relayons des adresses à ce pair.
```

<!-- cache_translation_check_fr_fc4db70a2ccfc6050293671569b3452a33653e9cb78d3d530eb0a4dd7d93bede -->
```
        <source>the peer selected us for high bandwidth relay</source>
        <translation>le pair nous avons sélectionné comme relais à large bande passante</translation>
    
ERR
The French translation is not grammatically correct. "Le pair nous avons sélectionné..." is incorrect; it should be "Le pair nous a sélectionnés..." or more contextually: "Le pair nous a sélectionnés pour un relais à haute bande passante".

Correct translation:
Le pair nous a sélectionnés pour un relais à large bande passante
```

<!-- cache_translation_check_fr_f9e1bc7069dcb1f533402edc761d68efc05968cfd30b63e029c67b5f1bfade82 -->
```
        <source>Request payment to …</source>
        <translation>Demander de paiement à…</translation>
    
ERR
The French translation is ungrammatical; "de paiement" is incorrect. The correct form is "Demander un paiement à…". There is also a missing space before the ellipsis in French typographic conventions; it should be "à …".

Correct translation:
Demander un paiement à …
```

<!-- cache_translation_check_fr_63d1680c07ae452d4ecb587d5b40550c42640204e551180c8a428c98740c7a2c -->
```
        <source>Specify a custom fee per kB (1,000 bytes) of the transaction's virtual size.

Note:  Since the fee is calculated on a per-byte basis, a fee rate of "100 satoshis per kvB" for a transaction size of 500 virtual bytes (half of 1 kvB) would ultimately yield a fee of only 50 satoshis.</source>
        <translation>Indiquer des frais personnalisés par Ko (1 000 octets) de la taille virtuelle de la transaction.

Note : Les frais étant calculés par octet, un taux de frais de « 100 satoshis par Kov » pour une transaction d’une taille de 500 octets (la moitié de 1 Kov) donneront des frais de seulement 50 satoshis.</translation>
    
ERR
There are two errors here:
1. The abbreviation "Ko" (for kilooctet) is sometimes used in French to mean "kilobyte," but in Bitcoin's context "kB" is the common (and necessary) technical usage, even in French, to avoid confusion.
2. "Kov" is a mistranslation/misinterpretation of "kvB" ("kilovirtual byte"), which should be left as "kvB" even in French due to its technical nature.
3. The note should clarify the relation with virtual bytes, not just "octets".

Correct translation:
Spécifiez des frais personnalisés par kB (1 000 octets) de taille virtuelle de la transaction.

Remarque : Étant donné que les frais sont calculés par octet, un taux de frais de « 100 satoshis par kvB » pour une transaction d'une taille de 500 octets virtuels (la moitié de 1 kvB) n'entraînerait finalement que 50 satoshis de frais.
```

<!-- cache_translation_check_fr_a8413edcce1008cf6fa49a3c0a2e5c42fc2a5f8df4f14cffdc501fac17217af7 -->
```
        <source>Watch-only balance:</source>
        <translation>Solde juste-regarder :</translation>
    
ERR
The translation "juste-regarder" is a literal and incorrect rendering of "watch-only", which in Bitcoin terminology is commonly translated as "solde en lecture seule" or "solde d'observation" in French. "Juste-regarder" is not idiomatic and could confuse users.

Correct translation:
Solde en lecture seule :
```

<!-- cache_translation_check_fr_da5a9fe127fe54e3e66387d88a6e57fba63f3672367a95fd1977d4b96d6b5c8f -->
```
        <source>Private key for the entered address is not available.</source>
        <translation>La clé privée pour l’adresse saisie n’est pas proposée.</translation>
    
ERR
The translation is not fully accurate. "n’est pas proposée" means "is not proposed," which is not the same as "is not available." The correct translation should reflect the unavailability, not whether it was proposed.

Correct translation:
La clé privée pour l’adresse saisie n’est pas disponible.
```

<!-- cache_translation_check_fr_4f39386c8f05ebe50ffed8a2026a8faba40822561a14240047498bc31fe7ea80 -->
```
        <source>watch-only</source>
        <translation>juste-regarder</translation>
    
ERR
The translation "juste-regarder" is a literal translation and not idiomatic in French. The correct term in French Bitcoin contexts is usually "lecture seule" or "observateur", but "lecture seule" (meaning "read-only") is more commonly used in wallet software.

Correct translation:
lecture seule
```

<!-- cache_translation_check_fr_2581a314ac205fbe57138292d7e7f4f213d0e54a7e001041a52513032338ca44 -->
```
        <source>Mined</source>
        <translation>Miné </translation>
    
ERR
There is an unwanted trailing space after "Miné" in the translation, which is a whitespace formatting issue.

Correct translation:
Miné
```

<!-- cache_translation_check_fr_4f39386c8f05ebe50ffed8a2026a8faba40822561a14240047498bc31fe7ea80 -->
```
        <source>watch-only</source>
        <translation>juste-regarder</translation>
    
ERR
The translation "juste-regarder" is a literal translation and not idiomatic in French. The correct term in French Bitcoin contexts is usually "lecture seule" or "observateur", but "lecture seule" (meaning "read-only") is more commonly used in wallet software.

Correct translation:
lecture seule
```

<!-- cache_translation_check_fr_469ace3db7a15f47ad67bd0a4733e52d32ef799aa5f50e0763e3fb10778ec4c2 -->
```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Une adresse juste-regarder est-elle ou non impliquée dans cette transaction.</translation>
    
ERR
The translation uses "juste-regarder" as a literal translation of "watch-only," which is not standard in French Bitcoin terminology. The proper term is "en lecture seule" or "de surveillance." Additionally, the sentence structure is slightly awkward.

Correct translation:
Indique si une adresse en lecture seule est impliquée dans cette transaction ou non.
```

<!-- cache_translation_check_fr_a0658ac333d432138e177a7716cbc5b8ae5e2c4c9af31ec657d473a0b116c826 -->
```
        <source>User-defined intent/purpose of the transaction.</source>
        <translation>Intention, but de la transaction défini par l’utilisateur.</translation>
    
ERR
The translation is mostly accurate but the word order is awkward and redundant: "Intention, but de la transaction" literally repeats both "intention" and "purpose" unnecessarily, making the translation cumbersome. Also, "défini par l’utilisateur" is correct for "user-defined".

Correct translation:
Intention ou but de la transaction défini par l’utilisateur.
```

<!-- cache_translation_check_fr_2581a314ac205fbe57138292d7e7f4f213d0e54a7e001041a52513032338ca44 -->
```
        <source>Mined</source>
        <translation>Miné </translation>
    
ERR
There is an unwanted trailing space after "Miné" in the translation, which is a whitespace formatting issue.

Correct translation:
Miné
```

<!-- cache_translation_check_fr_d712e4d82cdf8ed43937bf22c0ac338b1f2574483e98fba5e7f119d1c4d70f1c -->
```
        <source>Other</source>
        <translation>Autres </translation>
    
ERR
There is an unnecessary trailing space in the French translation ("Autres " instead of "Autres").

Correct translation:
Autres
```

<!-- cache_translation_check_fr_55157cc937b1b3e89b93d577638118debd4a37321f48014b01d6188a4b2a72c1 -->
```
        <source>Edit address label</source>
        <translation>Modifier l’adresse de l’étiquette</translation>
    
ERR  
The French translation is inaccurate. "Modifier l’adresse de l’étiquette" translates to "Edit the address of the label", which is incorrect. The correct translation is:  
Modifier l’étiquette de l’adresse
```

<!-- cache_translation_check_fr_1ed765406ea228864967795799abdc3fc65c0421b9bea326ae648a4df13d6d7d -->
```
        <source>ID</source>
        <translation>ID </translation>
    
ERR
There is an extra trailing space in the French translation. The translation should not contain unnecessary whitespace.

Correct translation:
ID
```

<!-- cache_translation_check_fr_e20adac52b7c6602797cc3528d5d7bb55c3825e6536689ba171722c2ca40d279 -->
```
        <source>to</source>
        <translation>à </translation>
    
ERR
There is a trailing whitespace at the end of the French translation ("à "). This is a whitespace formatting issue.

Correct translation:
à
```

<!-- cache_translation_check_fr_4a652c0bb148d008c3711cb54b2e6bbe1a9a1da2d965753556c94c1a989ade73 -->
```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>Le fichier de la TBSP doit être inférieur à 100 Mio</translation>
    
ERR
There are two issues:
1. The French translation swaps "PSBT" (Partially Signed Bitcoin Transaction) with "TBSP", which is incorrect.
2. "Mio" is technically correct for "Mebibyte", but inconsistent with the English "MiB". While "Mio" can be used in French technical contexts, "MiB" is often retained for clarity in Bitcoin/crypto contexts.

Correct translation:
Le fichier PSBT doit être inférieur à 100 MiB
```

<!-- cache_translation_check_fr_59c3aa842804c19c4e3cec14a72f83cd2e1ef868c94ab20e4bc17097c7765799 -->
```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>%s n’a pas réussi à valider l’état de l’instantané -assumeutxo. Cela indique un problème matériel, un bogue logiciel ou une mauvaise modification logicielle qui a permis le chargement d’un instantané invalide. Par conséquent, le nœud s’arrêtera et cessera d’utiliser tout état fondé sur cet instantané, ce qui réinitialisera à le niveau de la chaîne de %d à %d. Lors du prochain démarrage, la synchronisation reprendra de %d, sans utiliser les données d’un instantané. Signalez cet incident à %s en indiquant comment vous avez obtenu l’instantané. L’état de chaîne de l’instantané invalide sera laissé sur le disque au cas afin d’aider éventuellement à diagnostiquer le problème à l’origine de cette erreur.</translation>
    
ERR
There are a few grammatical errors and awkward phrasing in the French translation. Some parts are not natural, there is a stray "à" in "ce qui réinitialisera à le niveau de la chaîne de %d à %d" (should be "le niveau de la chaîne sera réinitialisé de %d à %d"), and "au cas afin d’aider" is incorrect (the phrase should be "au cas où cela pourrait aider à diagnostiquer...").

Correct translation:
%s n’a pas réussi à valider l’état de l’instantané -assumeutxo. Cela indique un problème matériel, un bogue logiciel ou une modification logicielle défectueuse ayant permis le chargement d’un instantané invalide. En conséquence, le nœud va s’arrêter et cesser d’utiliser tout état construit à partir de cet instantané, réinitialisant la hauteur de la chaîne de %d à %d. Au prochain redémarrage, le nœud recommencera la synchronisation à partir de %d sans utiliser de données d’instantané. Veuillez signaler cet incident à %s en indiquant comment vous avez obtenu l’instantané. L’état de la chaîne provenant de l’instantané invalide sera laissé sur le disque au cas où cela pourrait aider à diagnostiquer le problème ayant provoqué cette erreur.
```

<!-- cache_translation_check_fr_7dab51e078322a463e9b485bf27b76ddd4a0dcf364606d3fc415747a02d1232e -->
```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Les frais maximaux de transaction que vous payez (en plus des frais habituels) afin de prioriser une dépense non partielle plutôt qu’une sélection normale de pièces.</translation>
    
ERR
The translation shifts the meaning: "prioritize partial spend avoidance" was translated as "prioriser une dépense non partielle", which means "prioritize a non-partial spend," rather than "prioritize avoidance of partial spending." The negative sense ("avoidance") is missing.

Correct translation:
Il s'agit des frais de transaction maximum que vous payez (en plus des frais habituels) pour privilégier l'évitement des dépenses partielles par rapport à la sélection normale des pièces.
```

<!-- cache_translation_check_fr_c65fc611607f36fca0a5ed04308e6c2f226a49ee2ba3a733a787a304bf0c827d -->
```
        <source>Wallet loaded successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future. Legacy wallets can be migrated to a descriptor wallet with migratewallet.</source>
        <translation>Le portemonnaie a été créé. Le type de portemonnaie ancien devient obsolète et la prise en charge de la création et de l’ouverture des portemonnaie anciens sera supprimée à l’avenir. Les anciens portemonnaies peuvent être migrés vers un portemonnaie de descripteurs avec migratewallet.</translation>
    
ERR
The translation incorrectly translates "loaded successfully" as "a été créé" ("has been created"), which changes the meaning. It also inconsistently uses singular and plural forms for "portemonnaie(s)" ("wallet(s)"). The translation should use the plural form "portefeuilles" (the more common term in French for Bitcoin wallet). Furthermore, "de descripteurs" is awkward; "à descripteurs" is clearer. 

Correct translation:
Le portefeuille a été chargé avec succès. Le type de portefeuille hérité est en cours de dépréciation et la prise en charge de la création et de l’ouverture des portefeuilles hérités sera supprimée à l’avenir. Les portefeuilles hérités peuvent être migrés vers un portefeuille à descripteurs avec migratewallet.
```

<!-- cache_translation_check_fr_d44e291b11ea967678b1275762edb7a80cee0b30f07771e1b68bc50841e8e727 -->
```
        <source>%s is set very high!</source>
        <translation>La valeur %s est très élevée</translation>
    
ERR
The exclamation mark in the source ("very high!") is missing in the translation. Also, the translation omits the article "La valeur" which is not necessarily implied by the English. However, the most direct translation would keep the exclamation mark to match the emphasis.

Correct translation:
%s est très élevé !
```

<!-- cache_translation_check_fr_a0ca98fb52f070fbec40df67d497b91429857c43ee345b6ad4343b87216c3426 -->
```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>Les connexions sortantes sont limitées à Tor (-onlynet=onion), mais le mandataire pour accéder au réseau Tor n’est pas indiqué : ni -proxy, ni -onion, ni -onion=0 n’est indiqué</translation>
    
ERR
There is a minor accuracy issue: The French translation ends the list differently from the source. The source states: "none of -proxy, -onion or -listenonion is given", but the translation has "ni -proxy, ni -onion, ni -onion=0 n’est indiqué". "-onion=0" is not in the original source and "-listenonion" is omitted.

Correct translation:
Les connexions sortantes sont limitées à Tor (-onlynet=onion), mais le mandataire pour accéder au réseau Tor n’est pas indiqué : ni -proxy, ni -onion, ni -listenonion n’est indiqué.
```

<!-- cache_translation_check_fr_e630182278d3decb58937e9978bf6fb95372572d3afcf462181f120a51951c82 -->
```
        <source>Unexpected legacy entry in descriptor wallet found. Loading wallet %s

The wallet might have been tampered with or created with malicious intent.
</source>
        <translation>Une entrée héritée inattendue a été trouvée dans le portemonnaie de descripteurs. Chargement du portemonnaie %s

Le portemonnaie a peut-être avoir été altéré ou créé avec des intentions malveillantes.
</translation>
    
ERR
There is a grammatical issue in the sentence: "Le portemonnaie a peut-être avoir été altéré ou créé avec des intentions malveillantes."  
It should read "Le portemonnaie a peut-être été altéré ou créé avec des intentions malveillantes."  
Also, "portemonnaie" is less common than "portefeuille" in the context of Bitcoin wallets in French.

Correct translation:
Une entrée héritée inattendue a été trouvée dans le portefeuille de descripteurs. Chargement du portefeuille %s

Le portefeuille a peut-être été altéré ou créé avec des intentions malveillantes.
```

<!-- cache_translation_check_fr_102eb036f54106531a9693fbfc2907d16729878b99ce51b16ff988aa60e30629 -->
```
        <source>Insufficient dbcache for block verification</source>
        <translation>dbcache est insuffisant pour la confirmation des blocs</translation>
    
ERR
The French translation is understandable but not entirely accurate. "dbcache est insuffisant" is acceptable, but "confirmation des blocs" should be "vérification des blocs" to directly match "block verification". Also, adding the definite article "Le" at the start would make it more natural: "Le dbcache est insuffisant...".

Correct translation:
Le dbcache est insuffisant pour la vérification des blocs
```

<!-- cache_translation_check_fr_fa73ce7097d954feee47af2eabfa7c8030caa62ec683032228fa8cf5d89121af -->
```
        <source>The transactions removal process can only be executed within a db txn</source>
        <translation>Le processus de suppression des transactions ne peut être exécuté que dans une transaction .de base de données</translation>
    
ERR
There is a typographical error in the French translation: "transaction .de base de données" has a misplaced period and unnecessary space, resulting in "transaction .de base de données" instead of "transaction de base de données". Furthermore, the meaning is mostly correct, but the phrase could be more natural.

Correct translation:
Le processus de suppression des transactions ne peut être exécuté que dans une transaction de base de données.
```

<!-- cache_translation_check_fr_32e7d269919fb348b05a663bd4464284a058db2af26b6102b65e0f062ebd32e3 -->
```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>Il s’agit des frais minimaux que vous payerez si vous envoyez une transaction.</translation>
    
ERR
The translation adds "minimaux" (minimal), which is not in the source, and uses "payerez" instead of the more correct "paierez" (though both are seen, "paierez" is preferred for "payer" in modern French). The translation is also not literal—a more faithful translation would avoid the addition.

Correct translation:
Il s’agit des frais de transaction que vous paierez si vous envoyez une transaction.
```

<!-- cache_translation_check_fr_19042570ce817d0b4d909509aa4212b48a976077169fddbe0397e7c1257d861c -->
```
        <source>Transaction change output index out of range</source>
        <translation>L’index des sorties de monnaie des transactions est hors échelle</translation>
    
ERR
The translation is understandable but has issues:
1. "sorties de monnaie" is an awkward rendering for "change output"; "sortie de monnaie" isn't idiomatic in French Bitcoin terminology. The standard term for "change output" is often "sortie de monnaie de retour" or "sortie de monnaie rendue", but more simply (and most commonly) "sortie de change" or just "sortie de change".
2. "hors échelle" is not the proper idiom. The standard translation for "out of range" in this context is "hors limites" or "en dehors de la plage".
3. "L’index" should match the singular form from the source, and "transaction" should be singular, as in the English source.

Correct translation:
L’index de la sortie de change de la transaction est hors limites
```

<!-- cache_translation_check_fr_0f723cf19e976900dcbb581afc5b09c4736b086c81c05e1c86862a819cc4779c -->
```
        <source>Transaction too large</source>
        <translation>La transaction est trop élevée</translation>
    
ERR
The translation "La transaction est trop élevée" translates back as "The transaction is too high/expensive," which refers to value, not size. The correct translation should refer to the transaction's size, not its amount.

Correct translation:
La transaction est trop volumineuse
```

<!-- cache_translation_check_fr_3f1f3033120113d3aa6008488edb7b6cd63b7e460b7e1b33b5a0b786dbbc6e31 -->
```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Trop peu de descripteurs de fichiers sont proposés. %d proposés, %d requis</translation>
    
ERR
The translation uses "proposés" ("offered") instead of "disponibles" ("available"), which is a mistranslation. In this context, it should be "disponibles". Additionally, the translation is missing the period at the end to match the source.

Correct translation:
Pas assez de descripteurs de fichiers disponibles. %d disponibles, %d requis.
```
</details>

Number of issues: 45.
