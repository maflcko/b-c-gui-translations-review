# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>fr</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bfr%5D%20request)


<!-- cache_translation_check_fr_d169309d7d31bbaed002baa73511e4f2ae0f9258b969d010d26a6e4fbee0b105 -->
```
        <source>Delete the currently selected address from the list</source>
        <translation>Supprimer de la liste l’adresse choisie actuellement</translation>
    
ERR
The French is understandable but awkwardly ordered. No format specifiers are present and there are no whitespace issues.

Better/widely used phrasing:
Supprimer l'adresse actuellement sélectionnée de la liste
(or shorter)
Supprimer l'adresse sélectionnée de la liste
```

<!-- cache_translation_check_fr_f17dd09c3153279aa0c3683d01b43dc11b98892f4037c3ef000123a5150eb18a -->
```
        <source>Copy the currently selected address to the clipboard</source>
        <translation>Copier dans le presse-papiers l’adresse choisie actuellement</translation>
    
ERR
The French is understandable but slightly awkward in word order. A more natural phrasing places "actuellement" before "sélectionnée" or omits it.

Correct translation:
Copier l’adresse actuellement sélectionnée dans le presse-papiers.
```

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

<!-- cache_translation_check_fr_7a130a75f3e4be2f61a2cd7886ae03e67b4bd67dda3ca7835106c0fcd54f773d -->
```
        <source>&amp;Verify message…</source>
        <translation>&amp;Confirmer un message…</translation>
    
ERR
The translation uses "Confirmer un message…" which means "Confirm a message", but the correct translation of "Verify message" in the Bitcoin context is "Vérifier un message…". Additionally, the ampersand (&) is correctly placed for the shortcut key.

Correct translation:
&amp;Vérifier un message…
```

<!-- cache_translation_check_fr_a22572c3c7e30a1b7b879354466eca4d0c153075568fec37a8c6292e3302c9a1 -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>&amp;Charger la TBSP d’un fichier…</translation>
    
ERR
The acronym 'PSBT' (Partially Signed Bitcoin Transaction) is incorrectly translated as 'TBSP', which appears to be a typographical error or reversal of the letters. In French, the accepted practice is to retain 'PSBT'.

Correct translation:
&Charger la PSBT d’un fichier…
```

<!-- cache_translation_check_fr_56175f0101887bffe86dd68244d7cf599ce137d7f3339da93f7598b25f8ae40c -->
```
        <source>Open &amp;URI…</source>
        <translation>Ouvrir une &amp;URI…</translation>
    
ERR
In French, 'URI' is masculine and does not require an article here. The indefinite article "une" before 'URI' is ungrammatical and not natural in UI context. Additionally, "Ouvrir &amp;URI…" should follow the English pattern directly.

Correct translation:
Ouvrir &amp;URI…
```

<!-- cache_translation_check_fr_e6a32246e840ddbf9b8228c4366cbea4426666ac78030215335849f18a1882a6 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>Charger la TBSP du &amp;presse-papiers…</translation>
    
ERR
The acronym "PSBT" (Partially Signed Bitcoin Transaction) has been incorrectly reversed to "TBSP" in French, which is not standard and could cause confusion. The correct approach is to keep "PSBT" untranslated, as it is a technical term used identically in French Bitcoin contexts.

Correct translation:
Charger la PSBT depuis le &amp;presse-papiers…
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

<!-- cache_translation_check_fr_eb5f959ff0fc7a73580bf0e2aa4da545a5d7ce21b70ebc9621b73ba3a2c95e46 -->
```
        <source>(un)select all</source>
        <translation>Tout (ne rien) choisir</translation>
    
ERR
The French is awkward and not natural. "Tout (ne rien) choisir" is incorrect phrasing.

Correct translations:
- "(dé)sélectionner tout"
or
- "Sélectionner/désélectionner tout"
```

<!-- cache_translation_check_fr_1f81dd3c16a4ce300e80cab13848b074411cf26efea2cdfe3b8e6a5dc9eb06c6 -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>Copier l’ID de la transaction et l’index des sorties</translation>
    
ERR
The translation omits the ampersand, which indicates the shortcut key. The & must appear exactly once in the translation. Additionally, "output index" should be singular to match the source ("output"), unless multiple outputs are always implied in context. But the main error is the missing shortcut indicator.

Correct translation:
Copier l’&ID de la transaction et l’index de sortie
```

<!-- cache_translation_check_fr_641ab2e8ebfa61fbc7a5ec3af00fa518127015a19de1ecacfdae3210a65c5879 -->
```
        <source>L&amp;ock unspent</source>
        <translation>&amp;Verrouillé ce qui n’est pas dépensé</translation>
    
ERR
The translation is not accurate. "Verrouillé ce qui n’est pas dépensé" translates back to "Locked what is not spent," which suggests a past action rather than the command to "Lock unspent." Additionally, "Verrouiller" should be in the infinitive form to match the imperative/context.

Correct translation:
&Verrouiller les fonds non dépensés
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

<!-- cache_translation_check_fr_f1783f4b9489d015dedc0a733d000149ecf63c28fdaae0db4c68395e4e795364 -->
```
        <source>&amp;Main</source>
        <translation>&amp;Principales</translation>
    
ERR
The translation "Principales" is incorrect for "Main" in this context. "Principales" is the plural form of "principal", and it doesn't match the likely intended singular menu/section "Main". The correct translation should be "Principal" or, commonly in Bitcoin wallet UIs, "Accueil" ("Home" or "Main"). 

Also, the ampersand for the shortcut key is preserved, which is correct.

Correct translation:
&amp;Principal
or
&amp;Accueil
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

<!-- cache_translation_check_fr_20efe36b43b7beb78a9a2203de1168fdd15eaaf315a307703773a5e5f3b041b3 -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Activer les contrôles &amp;TBPS</translation>
    
ERR
The initialism "PSBT" stands for "Partially Signed Bitcoin Transaction" and must remain untranslated, as it is a technical term used in Bitcoin. In the translation, "TBPS" appears to be a mistaken reordering or an incorrect translation of the acronym.

Correct translation:
Activer les contrôles &amp;PSBT
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

<!-- cache_translation_check_fr_830da6a0c5ce7c7e1f71ff14df1cba9ada0e9aec1dbe98013508690df8a5df81 -->
```
        <source>&amp;Third-party transaction URLs</source>
        <translation>URL de transaction de $tiers</translation>
    
ERR
The translation is incorrect for several reasons:
- "&" (used for keyboard shortcuts) is missing in the French translation; it must appear once.
- "$tiers" is erroneous; the correct French word is "tiers" without a dollar sign.
- "URL de transaction" is singular, but the English is plural ("URLs").
- There is also a stray space at the start due to indentation, but that may not appear in the real string.

Correct translation:
&amp;URL de transactions de tiers
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

<!-- cache_translation_check_fr_e2617c4b36f3e65cf460d630a850c6ffb73ccf1ae8edaac6271c5b8b3a11f0b9 -->
```
        <source>&amp;Peers</source>
        <translation>&amp;Pairs</translation>
    
ERR
The word "Pairs" is a mistranslation; the correct French term for "Peers" (in the context of network peers) is "Pairs" is a false friend, as in English it means pairs/couples, but "Peers" in Bitcoin context should be "Pairs" in French. However, in French "pairs" does also mean "peers" in a technical context, so the translation is correct from that point of view. Additionally, the &amp; is correctly included exactly once. However, to avoid confusion for users, "Pairs" is acceptable in the Bitcoin network context in French.

Upon reflection, the translation is actually acceptable due to the technical context, and "Pairs" is used in French software for "Peers". Thus, the translation is not problematic.

NO
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

<!-- cache_translation_check_fr_5c7b1397deedfa853652533f63ee611f896f975a09945b6f67d292f63e363a3b -->
```
        <source>we selected the peer for high bandwidth relay</source>
        <translation>nous avons choisi le pair comme relais à large bande passante</translation>
    
ERR
The French is understandable but slightly unnatural: "le pair" is okay but the phrase "relais à large bande passante" is awkward. A more natural phrasing is:

Correct translation:
Nous avons sélectionné le pair pour un relais à haute bande passante.
```

<!-- cache_translation_check_fr_fedf0b3242756124fc6b7eeb6c53809d9b796ebb8fb5943b27ad788269591dfa -->
```
        <source>the peer selected us for high bandwidth relay</source>
        <translation>le pair nous a choisis comme relais à large bande passante</translation>
    
ERR
The French is understandable but slightly awkward: "à large bande passante" is not idiomatic and the adjective should agree with "bande passante" (feminine). A more natural translation in this Bitcoin/network context is:

Correct translation:
Le pair nous a sélectionnés pour un relais à haut débit

Alternate natural variant:
Le pair nous a sélectionnés pour un relais à haute bande passante
```

<!-- cache_translation_check_fr_723e64bc31e6dcf1952218ebdb9cd15ad9b974de4aadbaa0dc6873136bc10edc -->
```
        <source>&amp;Copy IP/Netmask</source>
        <extracomment>Context menu action to copy the IP/Netmask of a banned peer. IP/Netmask is the combination of a peer's IP address and its Netmask. For IP address, see: https://en.wikipedia.org/wiki/IP_address.</extracomment>
        <translation>&amp;Copier l’IP, le masque réseau</translation>
    
ERR
The translation changes the separator from "/" to "," and does not reflect the original format "IP/Netmask". Additionally, in French UI, "IP" is usually not preceded by an article. The shortcut key (&) is correctly placed.

Correct translation:
&Copier l’IP/Masque réseau
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

<!-- cache_translation_check_fr_c0908ef476add7350e93fd43e1582adb7becd6874d8e79def11fe5eed9755f1e -->
```
        <source>&amp;Verify</source>
        <translation>&amp;Confirmer</translation>
    
ERR
The translation of "&Verify" as "&Confirmer" is incorrect. The English word "Verify" translates to "Vérifier" in French, not "Confirmer" (which means "Confirm"). 

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
There are two errors here:
1. The abbreviation "Ko" (for kilooctet) is sometimes used in French to mean "kilobyte," but in Bitcoin's context "kB" is the common (and necessary) technical usage, even in French, to avoid confusion.
2. "Kov" is a mistranslation/misinterpretation of "kvB" ("kilovirtual byte"), which should be left as "kvB" even in French due to its technical nature.
3. The note should clarify the relation with virtual bytes, not just "octets".

Correct translation:
Spécifiez des frais personnalisés par kB (1 000 octets) de taille virtuelle de la transaction.

Remarque : Étant donné que les frais sont calculés par octet, un taux de frais de « 100 satoshis par kvB » pour une transaction d'une taille de 500 octets virtuels (la moitié de 1 kvB) n'entraînerait finalement que 50 satoshis de frais.
```

<!-- cache_translation_check_fr_6bc0dc2393d24268ae7135c9dac7057993287bf5aa2ab9368e534dcf6f36a92c -->
```
        <source>The address you selected for change is not part of this wallet. Any or all funds in your wallet may be sent to this address. Are you sure?</source>
        <translation>L’adresse que vous avez choisie pour la monnaie ne fait pas partie de ce portemonnaie. Les fonds de ce portemonnaie peuvent en partie ou en totalité être envoyés vers cette adresse. Confirmez-vous ?</translation>
    
ERR
The French uses awkward/incorrect phrasing: "pour la monnaie" is unclear for Bitcoin "change" and "portemonnaie" is less common than "portefeuille". Also style can be improved.

Correct translation:
L'adresse que vous avez sélectionnée comme adresse de change ne fait pas partie de ce portefeuille. Tout ou partie des fonds de votre portefeuille peuvent être envoyés à cette adresse. Êtes-vous sûr ?
```

<!-- cache_translation_check_fr_ccb3b3748a300c6f636d21c8ec95104a61b095d79bf768099dc028312bfa3bf9 -->
```
        <source>&amp;Verify Message</source>
        <translation>&amp;Confirmer un message</translation>
    
ERR
The translation is inaccurate: "Verify Message" should be translated as "Vérifier le message" in French. "Confirmer un message" means "Confirm a message," which is not the same meaning.

Correct translation:
&Vérifier le message
</reply>
```

<!-- cache_translation_check_fr_8d4f7d37269dd625d52d79258b88865ceb7d36ad0f93fa08780928937a9616c8 -->
```
        <source>Verify &amp;Message</source>
        <translation>Confirmer le &amp;message</translation>
    
ERR
The English source uses "Verify" which means "Vérifier" in French; "Confirmer" means "Confirm". The translation should accurately reflect the intended Bitcoin context of verifying a message.

Correct translation:
Vérifier le &amp;message
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

<!-- cache_translation_check_fr_2581a314ac205fbe57138292d7e7f4f213d0e54a7e001041a52513032338ca44 -->
```
        <source>Mined</source>
        <translation>Miné </translation>
    
ERR
There is an unwanted trailing space after "Miné" in the translation, which is a whitespace formatting issue.

Correct translation:
Miné
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

<!-- cache_translation_check_fr_0a01ad0157ad9eb078be0d8e53af44d1d5c4cb64908b3b436abe161a674dd557 -->
```
        <source>&amp;Edit address label</source>
        <translation>&amp;Modifier l’adresse de l’étiquette</translation>
    
ERR
The translation misinterprets "Edit address label". The correct translation should mean "Edit the label of the address," not "edit the address of the label". Also, the phrase "étiquette d’adresse" (label of address) or "libellé de l’adresse" is more appropriate.

Correct translation:
&Modifier le libellé de l’adresse
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

<!-- cache_translation_check_fr_cadde5690aab51bd291e9d66396fd174c801d0a9aa570d206c61d4385ee4a1aa -->
```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>Les frais maximaux de transaction que vous payez (en plus des frais habituels) afin de prioriser une dépense non partielle plutôt qu’un choix normale de pièces.</translation>
    
ERR
The French is awkward and contains grammatical errors ("dépense non partielle" is unnatural; "choix normale" should be "choix normal"). Also the phrasing should more clearly render "partial spend avoidance" as "évitement des dépenses partielles".

Correct translation:
Montant maximal des frais de transaction que vous payez (en plus des frais normaux) pour privilégier l'évitement des dépenses partielles plutôt que la sélection normale de pièces.
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

<!-- cache_translation_check_fr_4c3da931e827bebf817c1820800e8217601e7f03e00249193c6f97e594a62a13 -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>Élagage : la dernière synchronisation de portemonnaie va par-delà les données élaguées. Vous devez « -reindex » (réindexer, retélécharger toute la chaîne de blocs au cas ou un nœud a été élagué)</translation>
    
ERR
Problems:
- "portemonnaie" is nonstandard in French for wallet; use "portefeuille".
- Phrase "va par-delà les données élaguées" is awkward; "dépasse" or "outrepasse" is better.
- Missing accent: "au cas ou" should be "au cas où".
- Last clause is unidiomatic: "au cas où un nœud a été élagué" → better "si le nœud est élagué" or "dans le cas d'un nœud élagué".
- Quotation marks around -reindex are unnecessary but acceptable; ensure command appears exactly as in source.

Correct translation:
Élagage : la dernière synchronisation du portefeuille dépasse les données élaguées. Vous devez utiliser -reindex (retélécharger toute la chaîne de blocs si le nœud est élagué)
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
The French has grammatical errors and awkward phrasing:
- "portemonnaie" is uncommon; "portefeuille" is standard.
- "à descripteurs" is awkward; better "de type descriptor" or similar.
- "a peut-être avoir été altéré" is incorrect grammar — should be "a peut-être été altéré" or "peut avoir été altéré".

Corrected translation:
Une entrée héritée inattendue a été trouvée dans le portefeuille de type descriptor. Chargement du portefeuille %s

Le portefeuille a peut-être été altéré ou créé dans un but malveillant.
```

<!-- cache_translation_check_fr_97e25bee54e6f50c059698a0f081ec41224628cf1c8b369e44ea2b217c65e46c -->
```
        <source>Can't spend unconfirmed version %d pre-selected input with a version 3 tx</source>
        <translation>Impossible de dépenser une entrée présélectionnée de version %d avec une transaction de version 3</translation>
    
ERR
The French translation omits "unconfirmed" (non confirmée), which changes the meaning. The format specifier %d is preserved correctly and spacing is fine.

Correct translation:
Impossible de dépenser une entrée présélectionnée non confirmée de version %d avec une transaction de version 3
```

<!-- cache_translation_check_fr_13e25be797d9de8195f0d0202e237fa71d182af44745954f47f08e742864ef80 -->
```
        <source>Can't spend unconfirmed version 3 pre-selected input with a version %d tx</source>
        <translation>Impossible de dépenser une entrée présélectionnée de version  avec une transaction de version %d</translation>
    
ERR
The French translation omits "3" and does not render "unconfirmed" ("non confirmée"). Also there's an extra space after "version" where the "3" should be.

Correct translation:
Impossible de dépenser une entrée présélectionnée non confirmée de version 3 avec une transaction de version %d
```

<!-- cache_translation_check_fr_46e956d80823a663ae0d8c3ae18e18ea2766002ea1d820f12ac2b44afa6dacc8 -->
```
        <source>Cannot add WalletDescriptor to a non-descriptor wallet</source>
        <translation>Impossible d’ajouter WalletDescriptor à un portemonnaie qui n’est pas un portemonnaie à descripteurs</translation>
    
ERR
The French is awkward and repetitive ("portemonnaie qui n’est pas un portemonnaie à descripteurs") and uses "portemonnaie" (physical wallet) instead of the usual Bitcoin term "portefeuille". Also prefer a clearer phrasing for "non-descriptor wallet".

Correct translation suggestions:
- Impossible d'ajouter WalletDescriptor à un portefeuille qui n'est pas de type « descripteur ».
or
- Impossible d'ajouter WalletDescriptor à un portefeuille non-descripteur.
```

<!-- cache_translation_check_fr_b8f6da732ad8c514c9bc738a2020f34d2dcd6fb935c25a0cf37dee25e36ee17a -->
```
        <source>Could not generate scriptPubKeys (cache is empty)</source>
        <translation>Impossible de générer scriptPubKeys (le cache est vide)</translation>
    
ERR
The French is understandable but missing the definite article before "scriptPubKeys". Better to include the article for natural French.

Correct translation:
Impossible de générer les scriptPubKeys (le cache est vide)
```

<!-- cache_translation_check_fr_ed194820827e8dab706a099514893737dc7ffcf3b7c43d93a184f40f13c1f827 -->
```
        <source>Error: This wallet is already a descriptor wallet</source>
        <translation>Erreur : Ce portemonnaie est déjà un portemonnaie à descripteurs</translation>
    
ERR
The French is understandable but uses awkward wording ("portemonnaie" is less common than "portefeuille" for a crypto wallet, and "portemonnaie à descripteurs" is unnatural). 

Correct translation:
Erreur : ce portefeuille est déjà un portefeuille de descripteurs
```

<!-- cache_translation_check_fr_307f3781cbdf6c749bce87720a0a49dcb79b3e092dbe3f3895d7749e40ab3a7e -->
```
        <source>Failed to acquire rescan reserver during wallet initialization</source>
        <translation>Échec de réservation de l’accès à l’opération de réanalyse lors de l’initialisation du porte-monnaie</translation>
    
ERR
The French is awkward and imprecise. "rescan reserver" is mistranslated as "réservation de l’accès à l’opération de réanalyse", which is not natural; also "porte-monnaie" is acceptable but "portefeuille" is more common in Bitcoin context. No format specifiers issues.

Suggested correction:
Échec de l'acquisition du verrou de réanalyse lors de l'initialisation du portefeuille

(Alternative literal option if you prefer "reserver"):
Échec de l'acquisition du réservateur de réanalyse lors de l'initialisation du portefeuille
```

<!-- cache_translation_check_fr_945ff4a892dc14d2858e97104272d71af38dfe06ba63c7b7769e3a532c6b4043 -->
```
        <source>Failed to close block undo file.</source>
        <translation>Échec de fermeture du fichier d’annulation des blocs.</translation>
    
ERR
The French is understandable but missing the definite article and sounds slightly unidiomatic.

Correct translation:
Échec de la fermeture du fichier d'annulation des blocs.
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

<!-- cache_translation_check_fr_b86606f1c0ec752c2d5238f10228f480208826c686cdae0d6df1b7b02248f4d9 -->
```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on an enormous cluster of unconfirmed transactions.</source>
        <translation>Échec de calcul de la majoration des frais, car les UTXO non confirmés dépendent d’un groupe énorme de transactions non confirmées.</translation>
    
ERR
Minor grammatical and stylistic issues. In French it should be "Échec du calcul…" (not "Échec de calcul") and "majoration des frais" is better phrased as "frais de majoration" or simply "augmentation des frais". Also keep "UTXO" as-is.

Correct translation:
Échec du calcul des frais de majoration, car les UTXO non confirmés dépendent d’un énorme groupe de transactions non confirmées.
```

<!-- cache_translation_check_fr_3d32697841c2d9582cec1745f56e69c25b995d812661f1273664545e6aaacfb6 -->
```
        <source>Transaction requires one destination of non-zero value, a non-zero feerate, or a pre-selected input</source>
        <translation>Une destination d’une valeur non nulle, des taux de frais non nuls, ou une entrée présélectionnée sont nécessaires pour cette transaction</translation>
    
ERR
The French is understandable but slightly awkward: it mixes singular and plural subjects then uses the plural verb ("Une destination ..., des taux ..., ou une entrée ... sont nécessaires"), and "taux de frais" is less natural than "taux de frais" in singular here ("un taux de frais non nul"). A clearer, more natural translation keeps the singular verb and consistent nouns.

Correct translation:
Cette transaction nécessite une destination d'une valeur non nulle, un taux de frais non nul ou une entrée présélectionnée.
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
The translation is understandable and preserves the placeholder and formatting, but uses "portemonnaie" (less common) instead of the more standard French term "portefeuille". Minor style suggestion: use "portefeuille" for consistency with typical Bitcoin/French translations.

Correct translation:
Un descripteur non reconnu a été trouvé. Chargement du portefeuille %s

Le portefeuille a peut‑être été créé avec une version plus récente.
Veuillez essayer d’exécuter la version la plus récente du logiciel.
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

Number of issues: 63.
