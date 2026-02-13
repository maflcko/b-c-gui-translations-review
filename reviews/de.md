# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>de</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bde%5D%20request)


<!-- cache_translation_check_de_b2c022582a763d4a9f779d9574f6e00c6812b9d2331780a29d679152bdb44082 -->
```
        <source>Right-click to edit address or label</source>
        <translation>Adresse bearbeitenRechtsklick zum Bearbeiten der Adresse oder der Beschreibung</translation>
    
ERR
The translation contains redundant text at the beginning ("Adresse bearbeiten") merged directly with the rest of the sentence without spacing. It appears to be two different translation attempts joined together.

Correct translation:
Rechtsklick zum Bearbeiten der Adresse oder der Bezeichnung
```

<!-- cache_translation_check_de_4b9ae8b4d932f009c9244d7f4294ffcbf67201fc3425f0ff04eda01ee056f505 -->
```
        <source>Private Broadcast</source>
        <extracomment>Short-lived peer connection type that is used for broadcasting privacy-sensitive data.</extracomment>
        <translation>Private Rundsendug</translation>
    
ERR
The German word for "broadcast" is "Rundsendung". The provided translation contains a typo ("Rundsendug" instead of "Rundsendung").

Correct translation:
Private Rundsendung
```

<!-- cache_translation_check_de_4a4b331d125decb9c7e827826934faf0860de67f89e0d175ab6cd52552da87f9 -->
```
        <source>%1 h</source>
        <translation>%1 S</translation>
    
ERR
The unit for hours should be "h" (or "Std."), not "S" (which suggests seconds and is incorrect/capitalized). Keep the same unit as source.

Correct translation:
%1 h
```

<!-- cache_translation_check_de_7f16d7c974a18118959dea2c14d2be7b801ba8c842760c52722b75a9e55bb3c6 -->
```
        <source>&amp;Window</source>
        <translation>&amp;Programmfenster</translation>
    
ERR
The standard German UI label for the "Window" menu is "Fenster". "Programmfenster" is unnatural and too specific.

Correct translation:
&Fenster
```

<!-- cache_translation_check_de_2a7c9ad5872292cb37cdb9cd36f6e9e694e874d81f24e8b8df39f4abfcaaf972 -->
```
        <source>Are you sure you wish to restore the wallet file &lt;i&gt;%1&lt;/i&gt; to &lt;i&gt;%2&lt;/i&gt; and migrate it?</source>
        <translation>Bist du sicher, dass du die Wallet-Dateien &lt;i&gt;%1&lt;/i&gt; bis &lt;i&gt;%2&lt;/i&gt; wiederherstellen und migrieren möchtest?</translation>
    
ERR
The translation contains two errors:
1. It translates "wallet file" (singular) as "Wallet-Dateien" (plural).
2. It uses the preposition "bis" (which means "until" or "up to" in a range), whereas the English "to" in this context indicates a destination path. In German, "nach" or "in" is appropriate for file paths.

Correct translation:
Bist du sicher, dass du die Wallet-Datei <i>%1</i> nach <i>%2</i> wiederherstellen und migrieren möchtest?
```

<!-- cache_translation_check_de_19ae7349582eab63573fc2e94e04364c6b97a8ea5a531729ee4869980bfbd0b0 -->
```
        <source>Restoring the wallet will copy the backup file to the wallets directory and place it in the standard wallet directory layout. The original file will not be modified.

Migrating the wallet will convert the restored wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>Die Wiederherstellung der Wallet kopiert die Backup-Datei in das Wallet-Verzeichnis und legt sie im Standard-Wallet-Verzeichnis. Die Originaldatei wird nicht verändert.

Die Migration der Wallet wandelt die wiederhergestellte Wallet in eine oder mehrere Descriptor-Wallets um. Ein neues Wallet-Backup muss erstellt werden.
Wenn diese Wallet Watchonly-Skripte enthält, wird eine neue Wallet erstellt, die diese Watchonly-Skripte enthält.
Wenn diese Wallet lösbare, aber nicht überwachte Skripte enthält, wird eine andere und neue Wallet erstellt, die diese Skripte enthält.

Der Migrationsprozess erstellt vor der Migration ein Backup der Wallet. Diese Sicherungsdatei wird &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak genannt und ist im Verzeichnis dieser Wallet zu finden. Im Falle einer falschen Migration kann das Backup mit der Funktion "Wallet wiederherstellen" wiederhergestellt werden.</translation>
    
ERR
The translation has a minor grammatical issue and an omission in the first paragraph. The phrase "und legt sie im Standard-Wallet-Verzeichnis" is grammatically incomplete (missing a prefix like "ab" for the verb "legen") and omits the word "layout" from the source text ("standard wallet directory layout").

Correct translation:
Die Wiederherstellung der Wallet kopiert die Backup-Datei in das Wallet-Verzeichnis und ordnet sie in das Standard-Wallet-Verzeichnis-Layout ein. Die Originaldatei wird nicht verändert.

Die Migration der Wallet wandelt die wiederhergestellte Wallet in eine oder mehrere Descriptor-Wallets um. Ein neues Wallet-Backup muss erstellt werden.
Wenn diese Wallet Watchonly-Skripte enthält, wird eine neue Wallet erstellt, die diese Watchonly-Skripte enthält.
Wenn diese Wallet lösbare, aber nicht überwachte Skripte enthält, wird eine andere und neue Wallet erstellt, die diese Skripte enthält.

Der Migrationsprozess erstellt vor der Migration ein Backup der Wallet. Diese Sicherungsdatei wird <wallet name>-<timestamp>.legacy.bak genannt und ist im Verzeichnis dieser Wallet zu finden. Im Falle einer fehlerhaften Migration kann das Backup mit der Funktion "Wallet wiederherstellen" wiederhergestellt werden.
```

<!-- cache_translation_check_de_7eadbe2102be15382bc9015f3f577e7fec84eef711ac1c95f9224f7fc41c0353 -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Standardmäßig die Gebühr vom Betrag abziehen</translation>
    
ERR
Missing ampersand for the shortcut key; the English string has exactly one '&' which must be preserved in the translation.

Correct translation:
Standardmäßig &Gebühr vom Betrag abziehen
```

<!-- cache_translation_check_de_7f16d7c974a18118959dea2c14d2be7b801ba8c842760c52722b75a9e55bb3c6 -->
```
        <source>&amp;Window</source>
        <translation>&amp;Programmfenster</translation>
    
ERR
The standard German UI label for the "Window" menu is "Fenster". "Programmfenster" is unnatural and too specific.

Correct translation:
&Fenster
```

<!-- cache_translation_check_de_78ab6a62e57e938e5986a6dab2dcc66a6f4ef12732387a3637d0e7e772ea1b49 -->
```
        <source>Sent</source>
        <translation>Übertragen</translation>
    
ERR
"Übertragen" is uncommon/awkward in this Bitcoin transaction context. The typical and accurate UI label for "Sent" is "Gesendet".

Correct translation:
Gesendet
```

<!-- cache_translation_check_de_aa29383089c2b284adf9a6ac3efec057d414bc85a1556b1d8ae03d785564a135 -->
```
        <source>The total number of addresses received from this peer that were processed (excludes addresses that were dropped due to rate-limiting).</source>
        <extracomment>Tooltip text for the Addresses Processed field in the peer details area, which displays the total number of addresses received from this peer that were processed (excludes addresses that were dropped due to rate-limiting).</extracomment>
        <translation>Die Gesamtzahl der von diesem Peer empfangenen Adressen, die aufgrund von Ratenbegrenzung verworfen (nicht verarbeitet) wurden.</translation>
    
ERR
The translation is incorrect as it conveys the opposite of the source text. The source text refers to the number of addresses that were **processed** (excluding those dropped), while the translation describes the number of addresses that were **dropped/not processed**.

Correct translation:
Die Gesamtzahl der von diesem Peer empfangenen Adressen, die verarbeitet wurden (Adressen, die aufgrund von Ratenbegrenzung verworfen wurden, sind ausgeschlossen).
```

<!-- cache_translation_check_de_e01cdbfc95d76b3f72518333b65a179d238a2467ecc7d7eb125baf2d406baea6 -->
```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Die Zahlungsadresse der Überweisung</translation>
    
ERR
The translation omits "Bitcoin" and is semantically awkward. It should clearly indicate the destination address for the payment.

Correct translation:
Die Bitcoin-Adresse, an die die Zahlung gesendet werden soll
```

<!-- cache_translation_check_de_4b8ddaac0a6208e49422b93ca403d62813b033230c6d5d51af527a09f6c8481f -->
```
        <source>Clear &amp;All</source>
        <translation>&amp;Zurücksetzen</translation>
    
ERR
The translation changes the meaning: "Zurücksetzen" means "reset," not "Clear All."
Correct translation:
&Alles löschen
```

<!-- cache_translation_check_de_a801f268ad792da99e857270fad1a69facb0c03230e8bb644fc759bff1dcf823 -->
```
        <source>Generated coins must mature %1 blocks before they can be spent. When you generated this block, it was broadcast to the network to be added to the block chain. If it fails to get into the chain, its state will change to "not accepted" and it won't be spendable. This may occasionally happen if another node generates a block within a few seconds of yours.</source>
        <translation>Erzeugte Bitcoins müssen %1 Blöcke lang reifen, bevor sie ausgegeben werden können. Als Sie diesen Block erzeugten, wurde er an das Netzwerk übertragen, um ihn der Blockchain hinzuzufügen. Falls dies fehlschlägt, wird der Status in "nicht angenommen" geändert und Sie werden keine Bitcoins gutgeschrieben bekommen. Das kann gelegentlich passieren, wenn ein anderer Knoten einen Block fast zeitgleich erzeugt.</translation>
    
ERR
The sentence "und Sie werden keine Bitcoins gutgeschrieben bekommen" changes the meaning. The source says the block/coins won't be spendable, not that you won't be credited. Also, “not accepted” is better rendered as “nicht akzeptiert”.

Correct translation:
Erzeugte Bitcoins müssen %1 Blöcke lang reifen, bevor sie ausgegeben werden können. Als Sie diesen Block erzeugten, wurde er an das Netzwerk übertragen, um zur Blockchain hinzugefügt zu werden. Falls er es nicht in die Kette schafft, ändert sich sein Status in "nicht akzeptiert" und er kann nicht ausgegeben werden. Dies kann gelegentlich passieren, wenn ein anderer Knoten innerhalb weniger Sekunden nach Ihrem einen Block erzeugt.
```

<!-- cache_translation_check_de_efa52dd85b7239631fca72daef91d35d41e0b79baa5e9c09a3c4d86cec8e80cc -->
```
        <source>Copy transaction &amp;ID</source>
        <translation>Transaktionskennung kopieren</translation>
    
ERR
The German translation is missing the required single ampersand for the shortcut key.

Correct translation:
&Transaktions-ID kopieren
```

<!-- cache_translation_check_de_addaaed698fa985db2ae9fb99612ec3035ea3da62566419ca84cd7a15658cbce -->
```
        <source>Can't spend unconfirmed version %d pre-selected input with a version 3 tx</source>
        <translation>Unbestätigte, vorab ausgewählte Inputs der Version %d können nicht mit einer Version 3-Tx ausgegeben werden</translation>
    
ERR
The translation uses the plural “Inputs” even though the source is singular (“input”), leading to agreement errors. It also uses the abbreviation “Tx” awkwardly; “Transaktion” is clearer in German.

Correct translation:
Unbestätigter, vorab ausgewählter Input der Version %d kann nicht mit einer Version-3-Transaktion ausgegeben werden
```

<!-- cache_translation_check_de_664919e15c904d39a79c6e71858b42cdc4120a7f78c479c5c3ae814b10c1ae8a -->
```
        <source>Can't spend unconfirmed version 3 pre-selected input with a version %d tx</source>
        <translation>Unbestätigte, vorab ausgewählte Inputs der Version 3 können nicht mit einer Version %d Tx ausgegeben werden</translation>
    
ERR
The source uses singular "input", but the translation uses the plural "Inputs". Also, "tx" should be rendered as "Transaktion" in German, and capitalization of "Tx" is inconsistent with the source.

Correct translation:
Unbestätigter, vorab ausgewählter Input der Version 3 kann nicht mit einer Transaktion der Version %d ausgegeben werden
```

<!-- cache_translation_check_de_4433c7e1e1c84fe6ea661065b102908ab8a16386d8a6b9709a5509179c9164de -->
```
        <source>Config setting for %s only applied on %s network when in [%s] section.</source>
        <translation>Konfigurationseinstellungen für %s sind nur im %s-Netzwerk gültig, wenn in Sektion [%s].</translation>
    
ERR
The German is awkward and slightly ungrammatical: the English uses singular "Config setting" but the translation uses the plural "Konfigurationseinstellungen", and the clause "wenn in Sektion [%s]" is incomplete/unnatural.

Correct translation (singular, natural German):
Konfigurationseinstellung für %s gilt nur im %s-Netzwerk, wenn sie im Abschnitt [%s] steht.

Alternative phrasing:
Die Konfigurationseinstellung für %s wird nur im %s-Netzwerk angewendet, wenn sie im Abschnitt [%s] steht.
```

<!-- cache_translation_check_de_97d9339d764b16cfcd0106b36bd8c38cac7e3018e5135bb51f2ec399aa6810fe -->
```
        <source>Error creating %s: Could not write version metadata.</source>
        <translation>Fehler beim erstellen von %s: Versionsmetadaten konnten nicht geschrieben werden.</translation>
    
ERR
In the German translation, "erstellen" should be capitalized because it is used as a nominalized verb (substantive infinitive) following the preposition "beim" (contraction of "bei dem").

Correct translation:
Fehler beim Erstellen von %s: Versionsmetadaten konnten nicht geschrieben werden.
```

<!-- cache_translation_check_de_98c4a3a6747dc57f084013aba0c293dcce8f14dcb58f54a21d3c205af9f980c3 -->
```
        <source>Option '-limitdescendantsize' is given but descendant size limits have been replaced with cluster size limits (see -limitclustersize). This option has no effect.</source>
        <translation>Die Option '-limitdescendantsize' wird angegeben, aber die Größenbeschränkung der Descendant wurden durch Clustergrößenbeschränkungen ersetzt (siehe -limitclustersize). Diese Option hat keine Wirkung.</translation>
    
ERR
The German translation contains a grammatical error regarding the plural/declension of the term 'Descendant'. In German, it should either be translated (e.g., 'Nachfahren') or, if kept as a technical term, use the plural form 'Descendants' to match the plural 'Größenbeschränkungen'. Additionally, the word "angegeben" is slightly passive; "festgelegt" or "verwendet" is more common in this context.

Correct translation:
Die Option '-limitdescendantsize' wird verwendet, aber die Größenbeschränkungen für Descendants wurden durch Clustergrößenbeschränkungen ersetzt (siehe -limitclustersize). Diese Option hat keine Wirkung.
```

<!-- cache_translation_check_de_488e496f5d5e16762dd5b2c36eaed2f2d5be6ed7370a50443ee3c22183506bdc -->
```
        <source>Private broadcast of own transactions requested (-privatebroadcast) and -proxyrandomize is disabled. Tor circuits for private broadcast connections may be correlated to other connections over Tor. For maximum privacy set -proxyrandomize=1.</source>
        <translation>Private Rundsendungen eigener Transaktionen (-privatebroadcast) und -proxyrandomize sind deaktiviert. Tor-Circuits für private Rundsendungsverbindungen können mit anderen Verbindungen über Tor korreliert sein. Für maximale Privatsphäre setze -proxyrandomize=1.</translation>
    
ERR
The translation incorrectly states that the private broadcast is disabled, whereas the source text states it was requested (enabled). The source says "requested... and -proxyrandomize is disabled", but the translation groups both together as "sind deaktiviert" (are disabled).

Correct translation:
Private Rundsendung eigener Transaktionen angefordert (-privatebroadcast) und -proxyrandomize ist deaktiviert. Tor-Circuits für private Rundsendungsverbindungen können mit anderen Verbindungen über Tor korreliert werden. Für maximale Privatsphäre setzen Sie -proxyrandomize=1.
```

<!-- cache_translation_check_de_887ada539f6a3aa1e7944b20ef61d640b4656a82eefa1f4368c7b97680386f54 -->
```
        <source>Private broadcast of own transactions requested (-privatebroadcast), but -connect is also configured. They are incompatible because the private broadcast needs to open new connections to randomly chosen Tor or I2P peers. Consider using -maxconnections=0 -addnode=... instead</source>
        <translation>Private Rundsendungen eigener Transaktionen wird angefordert (-privatebroadcast), aber -connect ist ebenfalls konfiguriert. Diese sind inkompatibel, weil die private Rundsendung neue Verbindungen zu zufällig ausgewählten Tor- oder I2P-Peers öffnen muss. Erwäge die Verwendung von -maxconnections=0 -addnode=... stattdessen</translation>
    
ERR
The German grammar is incorrect. The subject "Private Rundsendungen" is plural, but the verb "wird" is singular. It should be "Private Rundsendung" (singular) or "werden" (plural). Additionally, the word order in the final sentence is slightly clunky.

Correct translation:
Private Rundsendung eigener Transaktionen angefordert (-privatebroadcast), aber -connect ist ebenfalls konfiguriert. Diese sind inkompatibel, weil die private Rundsendung neue Verbindungen zu zufällig ausgewählten Tor- oder I2P-Peers öffnen muss. Erwägen Sie stattdessen die Verwendung von -maxconnections=0 -addnode=...
```

<!-- cache_translation_check_de_a823c11abeb2a9ac05a83c5343669727a2fe3f2af8ed08ec6705863899cf0818 -->
```
        <source>SQLiteDatabase: Failed to read database verification error: %s</source>
        <translation>Datenbank konnte nicht gelesen werden
Verifikations-Error: %s</translation>
    
ERR
The translation introduces an unnecessary newline character that is not present in the source text. It also omits the "SQLiteDatabase" prefix and slightly alters the meaning (the source indicates a failure to read the verification error message itself).

Correct translation:
SQLiteDatabase: Datenbank-Verifizierungsfehler konnte nicht gelesen werden: %s
```

<!-- cache_translation_check_de_eb39c9cf17e4f159234c1bf816efb7ece4de369c4c36b7e9be39b5f349ce0171 -->
```
        <source>Section [%s] is not recognized.</source>
        <translation>Sektion [%s] ist nicht delegiert.</translation>
    
ERR
The German translation is incorrect. "recognized" means "erkannt", whereas "delegiert" means "delegated". In the context of a software section, "nicht erkannt" or "unbekannt" is the correct terminology.

Correct translation:
Sektion [%s] wird nicht erkannt.
```

<!-- cache_translation_check_de_dba144209bf2d3425da312c35cbebcd53c52026f6f00ffe30da06a77c720346a -->
```
        <source>The %s path uses exFAT, which is known to have intermittent corruption problems on macOS. Move this directory to a different filesystem to avoid data loss.</source>
        <translation>Der %s Pfad verwendet exFAT, das unter macOS bekanntermaßen zeitweise beschädigt wird. Verschiebe dieses Verzeichnis in ein anderes Dateisystem, um Datenverlust zu vermeiden.</translation>
    
ERR
- Style: Informal imperative ("Verschiebe") should be formal ("Verschieben Sie") in typical UI text.
- Grammar/wording: "Der %s Pfad" should be hyphenated as "Der %s-Pfad". "zeitweise beschädigt wird" is unnatural and misleading; the issue is corruption problems with exFAT on macOS.
- Clarity: Better to state exFAT has sporadic corruption issues rather than that it "gets damaged."

Correct translation:
Der %s-Pfad verwendet exFAT, das unter macOS bekanntermaßen sporadische Korruptionsprobleme aufweist. Verschieben Sie dieses Verzeichnis auf ein anderes Dateisystem, um Datenverlust zu vermeiden.
```

<!-- cache_translation_check_de_c76c953889bb6e10c840e4f7692e5742b305954bdfac65e48b4abe66adc43fa9 -->
```
        <source>The specified config file %s does not exist</source>
        <translation>Die angegebene Konfigurationsdatei %sexistiert nicht</translation>
    
ERR
The translation contains a spacing error. There should be a space between the format specifier '%s' and the verb 'existiert' to avoid them being joined together.

Correct translation:
Die angegebene Konfigurationsdatei %s existiert nicht
```

<!-- cache_translation_check_de_d76d54b9a6fd9a49cd46051cded24b4c08269b0177ba8f362df04b2e6676e25c -->
```
        <source>Unable to open %s for writing</source>
        <translation>Konnte %s nicht zum Schreiben zu öffnen</translation>
    
ERR
The German grammar is incorrect. The verb 'öffnen' should be in the infinitive without 'zu' when used with the modal verb 'konnte'.

Correct translation:
Konnte %s nicht zum Schreiben öffnen
```

<!-- cache_translation_check_de_30cd8c6940936d245663dad4b7e855a03b9182045ac0bd6920f4ef11cd245b27 -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>Fehler beim Laden %s: Wallet ist eine Legacy-Wallet. Bitte mit dem Migrationstool (migratewallet RPC) migrieren zu einer Deskriptor-Wallet.</translation>
    
ERR
- Missing preposition: "Fehler beim Laden %s" should be "Fehler beim Laden von %s".
- Missing article and awkward phrasing: Improve sentence flow and politeness.

Correct translation:
Fehler beim Laden von %s: Die Wallet ist eine Legacy-Wallet. Bitte migrieren Sie mithilfe des Migrationstools (migratewallet RPC) zu einer Deskriptor-Wallet.
```

<!-- cache_translation_check_de_9a0a19ab7f27845d9cb3dc862682c892093c5cfa24b2acdb33fb21d296033317 -->
```
        <source>Transaction requires one destination of non-zero value, a non-zero feerate, or a pre-selected input</source>
        <translation>Die Transaktion erfordert ein Ziel mit einem Wert ungleich Null, einen Gebührensatz ungleich Null oder eine vorausgewähltes Input.</translation>
    
ERR
Grammatical error: "eine vorausgewähltes Input" has mismatched gender and uses an Anglicism. Use the feminine noun "Eingabe" or correct the article/adjective if keeping "Input".

Correct translation:
Die Transaktion erfordert ein Ziel mit einem Wert ungleich Null, einen Gebührensatz ungleich Null oder eine vorausgewählte Eingabe.
```
</details>

Number of issues: 28.
