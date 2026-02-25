# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>de</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bde%5D%20request)


<!-- cache_translation_check_de_39a82cea9f52135e6922b6da54dda5d083aca16cd9b7295f9fe6b22350982d81 -->
```
        <source>Node window</source>
        <translation>Node Fenster</translation>
    
ERR
In German, compound nouns like "Node window" should be written as a single word or with a hyphen. "Node Fenster" with a space is orthographically incorrect.

Correct translation:
Node-Fenster
```

<!-- cache_translation_check_de_50716bbc9eaafac3b198425074d78d73d11371358abb2a9ace3e9341a59d5a1a -->
```
        <source>Are you sure you wish to restore the wallet file &lt;i&gt;%1&lt;/i&gt; to &lt;i&gt;%2&lt;/i&gt; and migrate it?</source>
        <translation>Bist du sicher, dass du die Wallet-Dateie &lt;i&gt;%1&lt;/i&gt; nach &lt;i&gt;%2&lt;/i&gt; wiederherstellen und migrieren möchtest?</translation>
    
ERR
The German word "Wallet-Dateie" is incorrect. The singular is "Wallet-Datei".

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

<!-- cache_translation_check_de_7f16d7c974a18118959dea2c14d2be7b801ba8c842760c52722b75a9e55bb3c6 -->
```
        <source>&amp;Window</source>
        <translation>&amp;Programmfenster</translation>
    
ERR
The standard German UI label for the "Window" menu is "Fenster". "Programmfenster" is unnatural and too specific.

Correct translation:
&Fenster
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

<!-- cache_translation_check_de_0562f7af8cb194b3840f837f141ae9b11aeec8aebdcd778d35d46b320df3a635 -->
```
        <source>%s request to listen on port %u. This port is considered "bad" and thus it is unlikely that any peer will connect to it. See doc/p2p-bad-ports.md for details and a full list.</source>
        <translation>%s Aufforderung, auf Port %u zu lauschen. Dieser Port wird als "schlecht" eingeschätzt und es ist daher unwahrscheinlich, dass sich Bitcoin Core Gegenstellen mit ihm verbinden. Siehe doc/p2p-bad-ports.md für Details und eine vollständige Liste.</translation>
    
ERR
The German translation "Aufforderung" for "request" is incorrect in this technical context. In software logs or status messages, "request" typically refers to an attempt or request made by the system, often translated as "Anfrage" or "versucht". Furthermore, "Bitcoin Core Gegenstellen" is an unnecessarily specific and slightly clunky translation for "peers".

Correct translation:
%s versucht, auf Port %u zu lauschen. Dieser Port wird als „schlecht“ eingestuft und es ist daher unwahrscheinlich, dass sich Gegenstellen mit ihm verbinden. Siehe doc/p2p-bad-ports.md für Details und eine vollständige Liste.
```

<!-- cache_translation_check_de_65769c23df810df0d65c72586e0f3a3a33acf57f526ecca0d6fbbb95a4596469 -->
```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Fehler: Dumpdatei Format Eintrag ist Ungültig. Habe "%s" bekommen, aber "format" erwartet.</translation>
    
ERR
The German translation has several grammatical and capitalization issues. "Dumpdatei Format Eintrag" should be a compound noun or hyphenated ("Dumpdatei-Formateintrag"), and "ungültig" should not be capitalized. Additionally, the phrase "Habe ... bekommen" is too colloquial for a technical error message.

Correct translation:
Fehler: Format-Eintrag der Dumpdatei ist ungültig. "%s" erhalten, "format" erwartet.
```

<!-- cache_translation_check_de_9490ab52d564d6544553bd3f1873d3f8e8d4888ba095a5947963967d35b60a3b -->
```
        <source>Error: Transaction %s in wallet cannot be identified to belong to migrated wallets</source>
        <translation>Fehler: Transaktion in Wallet %s kann nicht als zu migrierten Wallet gehörend identifiziert werden</translation>
    
ERR
The translation changes the meaning of the sentence and misplaces the format specifier. In the source, %s refers to the transaction ID, but in the translation, it is positioned as if it refers to the wallet. Additionally, "migrierten Wallet" should be plural "migrierten Wallets".

Correct translation:
Fehler: Transaktion %s im Wallet kann nicht als zu migrierten Wallets gehörend identifiziert werden
```

<!-- cache_translation_check_de_7ef5fe2f7a4c4adcabb3f7d7b4332ecf6ad706c39341a95a679eb4682b153168 -->
```
        <source>Can't spend unconfirmed version %d pre-selected input with a version 3 tx</source>
        <translation>Unbestätigter, vorab ausgewählte Input der Version %d kann nicht mit einer Version-3-Transaktion ausgegeben werden</translation>
    
ERR
The German translation has a grammar error regarding noun-adjective agreement. "Unbestätigter, vorab ausgewählte Input" mixes cases/inflections. Since "Input" is masculine, it should be "Unbestätigter, vorab ausgewählter Input". Additionally, the word "Transaktion" is often abbreviated as "Tx" in technical contexts, but the current phrasing is acceptable; however, the grammar fix is necessary.

Correct translation:
Unbestätigter, vorab ausgewählter Input der Version %d kann nicht mit einer Version-3-Transaktion ausgegeben werden
```

<!-- cache_translation_check_de_9676a22d9187169c376157407a9d27b5ff53f26f196af064ba08224556e9673b -->
```
        <source>Can't spend unconfirmed version 3 pre-selected input with a version %d tx</source>
        <translation>Unbestätigter, vorab ausgewählte Input der Version 3 kann nicht mit einer Version %d Transaktion ausgegeben werden</translation>
    
ERR
The German grammar is incorrect. The noun 'Input' is masculine, so 'vorab ausgewählte' should be in the nominative 'vorab ausgewählter' to match the subject of the sentence.

Correct translation:
Unbestätigter, vorab ausgewählter Input der Version 3 kann nicht mit einer Version %d Transaktion ausgegeben werden
```

<!-- cache_translation_check_de_b8e9d9ecca1d400d8cd810953b60efaeabf5f5e03be8e9204e4e1f16a57b0d37 -->
```
        <source>SQLiteDatabase: Failed to read database verification error: %s</source>
        <translation>Datenbank konnte nicht gelesen werden Verifikations-Error: %s</translation>
    
ERR
The German translation is grammatically awkward and uses the English term "Error" where "Fehler" would be more appropriate. A more natural phrasing should be used to connect the parts of the sentence.

Correct translation:
SQLiteDatabase: Datenbank-Verifizierungsfehler konnte nicht gelesen werden: %s
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

<!-- cache_translation_check_de_9fa1aa01524b1822f0e806fc6b438caf5e72a2538106ffd942928a6cfb502b2c -->
```
        <source>The total exceeds your balance when the %s transaction fee is included.</source>
        <translation>Der Gesamtbetrag %s übersteigt Ihr Guthaben, wenn die Transaktionsgebühr hinzugerechnet wird.</translation>
    
ERR
The translation changes the meaning and misplaces the format specifier. In the source text, %s refers to the fee amount ("the %s transaction fee"), but in the translation, %s is placed after "Gesamtbetrag" (total amount), implying the total is the variable.

Correct translation:
Der Gesamtbetrag übersteigt Ihr Guthaben, wenn die Transaktionsgebühr von %s hinzugerechnet wird.
```

<!-- cache_translation_check_de_d6968ce91b06b15a6436f97954a0b243f0155d7a3a35a277b328ef4358e4c8ff -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>Fehler beim Laden von %s: Die Wallet ist eine Legacy-Wallet. Bitte mit dem Migrationstool (migratewallet RPC) migrieren zu einer Deskriptor-Wallet.</translation>
    
ERR
The German word order is incorrect. In German infinitive constructions used as an imperative, the verb ("migrieren") should be placed at the end of the phrase.

Correct translation:
Fehler beim Laden von %s: Die Wallet ist eine Legacy-Wallet. Bitte mit dem Migrationstool (migratewallet RPC) zu einer Deskriptor-Wallet migrieren.
```

<!-- cache_translation_check_de_1643127c580fd5f15ab1ccff97eaa170e8018cc8df1059b28ad227f0a66bc712 -->
```
        <source>Transaction requires one destination of non-zero value, a non-zero feerate, or a pre-selected input</source>
        <translation>Die Transaktion erfordert ein Ziel mit einem Wert ungleich Null, einen Gebührensatz ungleich Null oder ein vorausgewähltes Input.</translation>
    
ERR
The translation uses the wrong grammatical gender for "Input". In German technical terminology, "Input" is masculine ("einen vorausgewählten Input"), not neuter ("ein vorausgewähltes Input").

Correct translation:
Die Transaktion erfordert ein Ziel mit einem Wert ungleich Null, einen Gebührensatz ungleich Null oder einen vorausgewählten Input.
```
</details>

Number of issues: 17.
