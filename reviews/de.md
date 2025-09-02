# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>de</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bde%5D%20request)


<!-- cache_translation_check_de_e3c92398da0384a2df7d073b74ab27a95fa1e29352e64d1d9bfd2f0a5ee13131 -->
```
        <source>Copy the currently selected address to the clipboard</source>
        <translation>Kopieren der aktuell ausgewählte Adresse in die Zwischenablage</translation>
    
ERR
The German grammar is incorrect (“ausgewählte” should be “ausgewählten” in the genitive), and the style is awkward. A clear UI-style translation is:

Aktuell ausgewählte Adresse in die Zwischenablage kopieren
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
The translation adds unnecessary specificity. The standard menu label should be "Fenster".

Correct translation:
&Fenster
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

<!-- cache_translation_check_de_8b2e09edda1278389e67402ff321ea1e68d8a536088ad207d8ac33d91295897a -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>&amp;Unbestätigtes Wechselgeld darf ausgegeben werden</translation>
    
ERR
The translation changes the concise label into a permissive sentence ("darf ausgegeben werden") and is stylistically inappropriate for a checkbox/option label. A more accurate and standard GUI phrasing is imperative.

Correct translation:
&Unbestätigtes Wechselgeld ausgeben
```

<!-- cache_translation_check_de_8b2eb07d76db68a79b60cc017e57ab0e9e56315867f3ab8749d51138852766e6 -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>&amp;PBST-Kontrollen aktivieren</translation>
    
ERR
"Acronym typo: 'PBST' should be 'PSBT'. Also, 'Kontrollen' is not the usual UI term; 'Steuerelemente' or 'Bedienelemente' is more appropriate. The shortcut ampersand is present exactly once, which is correct.

Correct translation:
&PSBT-Steuerelemente aktivieren
```

<!-- cache_translation_check_de_7ee3ac25088b3ff208013c5095387d053cbc2c0d19cb60299115ea5b8feb8625 -->
```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Ob PSBT-Kontrollen angezeigt werden sollen. </translation>
    
ERR
Trailing whitespace at the end of the translation. Also, "Kontrollen" is uncommon in German UI; "Bedienelemente" is more appropriate.

Correct translation:
Ob PSBT-Bedienelemente angezeigt werden sollen.
```

<!-- cache_translation_check_de_7f16d7c974a18118959dea2c14d2be7b801ba8c842760c52722b75a9e55bb3c6 -->
```
        <source>&amp;Window</source>
        <translation>&amp;Programmfenster</translation>
    
ERR
The translation adds unnecessary specificity. The standard menu label should be "Fenster".

Correct translation:
&Fenster
```

<!-- cache_translation_check_de_208f7861e4803e6564b11a406baad9388ff4141e2137e08c57b58b13c4242be4 -->
```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>Eingaben können nicht unterzeichnet werden, wenn die Brieftasche gesperrt ist.</translation>
    
ERR
"Unterzeichnet" is uncommon in this technical context; "signiert" is standard. "Eingaben" is ambiguous and should be "Transaktionseingaben" to match Bitcoin terminology. "Wallet" is also more common than "Brieftasche".

Correct translation:
Transaktionseingaben können nicht signiert werden, während die Wallet gesperrt ist.
```

<!-- cache_translation_check_de_3b136319368213551fd549917be3f17e29cbcafba6cd806a4f504693ef3b20d8 -->
```
        <source>Sent</source>
        <extracomment>Title of Peers Table column which indicates the total amount of network information we have sent to the peer.</extracomment>
        <translation>Übertragen</translation>
    
ERR
"Übertragen" is less precise for a column meaning data we have sent; the standard and clearer term is "Gesendet", which pairs with "Empfangen" for Received.

Correct translation:
Gesendet
```

<!-- cache_translation_check_de_78ab6a62e57e938e5986a6dab2dcc66a6f4ef12732387a3637d0e7e772ea1b49 -->
```
        <source>Sent</source>
        <translation>Übertragen</translation>
    
ERR
"Übertragen" is not the usual or most accurate translation for "Sent" in the Bitcoin wallet context. The standard German term is "Gesendet".

Correct translation:
Gesendet
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

<!-- cache_translation_check_de_e01cdbfc95d76b3f72518333b65a179d238a2467ecc7d7eb125baf2d406baea6 -->
```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Die Zahlungsadresse der Überweisung</translation>
    
ERR
The translation omits "Bitcoin" and is semantically awkward. It should clearly indicate the destination address for the payment.

Correct translation:
Die Bitcoin-Adresse, an die die Zahlung gesendet werden soll
```

<!-- cache_translation_check_de_e502e92f91b72319f3cd2fa212dd162ae5012fff3ef57ab063aa012473a46145 -->
```
        <source>Copy the current signature to the clipboard</source>
        <translation>Kopieren der aktuelle Signatur in die Zwischenablage</translation>
    
ERR
German grammar and style are incorrect for a UI command. Use the infinitive menu style and correct article/adjective agreement.

Correct translation:
Die aktuelle Signatur in die Zwischenablage kopieren
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

<!-- cache_translation_check_de_4612457685f6d8b9d7284297275358be675b0dc410fd10c8cd723c1b57c77046 -->
```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Fehler: Dumpdatei Format Eintrag ist ungültig. "%s" erhalten, "format" erwartet.</translation>
    
ERR
German compound nouns should not be split into separate words. "Dumpdatei Format Eintrag" is unidiomatic; use a compound or hyphenation. Also adding an article improves readability.

Correct translation:
Fehler: Der Formateintrag der Dumpdatei ist ungültig. "%s" erhalten, "format" erwartet.
```

<!-- cache_translation_check_de_c2a6d6f620ef1583c161314bdabc0d5eb064654abada07c0562a03c85b4fbf2c -->
```
        <source>Option '-maxorphantx' is set but no longer has any effect (see release notes). Please remove it from your configuration.</source>
        <translation>Die Option '-maxorphantx' ist gesetzt, hat aber keine Wirkung mehr (siehe Release Notes). Bitte von der Konfiguration entfernen.</translation>
    
ERR
The second sentence is grammatically incomplete; it lacks a pronoun and polite form. Also, "Release Notes" can be localized.

Correct translation:
Die Option '-maxorphantx' ist gesetzt, hat aber keine Wirkung mehr (siehe Versionshinweise). Bitte entfernen Sie sie aus Ihrer Konfiguration.
```

<!-- cache_translation_check_de_3d92ea9d9fdeec04a43a8baa25128384119e6d2c692e763422d79e0fb92e88cb -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>Prune: Die Synchronisierung der letzten Wallet geht über beschnittene Daten (pruned) hinaus. Sie müssen -reindex laufen lassen (Es wird die gesamte Blockchain erneut heruntergeladen, falls es ein beschnittener Node (pruned) ist)</translation>
    
ERR
"Synchronisierung der letzten Wallet" implies the synchronization of the last wallet rather than the last wallet synchronization. Also, "Node" should be "Knoten", and wording can be more idiomatic.

Correct translation:
Prune: Die letzte Wallet-Synchronisierung geht über die beschnittenen Daten hinaus. Sie müssen -reindex ausführen (bei einem beschnittenen Knoten wird dabei die gesamte Blockchain erneut heruntergeladen)
```

<!-- cache_translation_check_de_6005003fc2f130110c65aef05cbf0acba00ab071edfa8cb7d74f6858dc229945 -->
```
        <source>Config setting for %s only applied on %s network when in [%s] section.</source>
        <translation>Konfigurationseinstellungen für %s sind nur auf %s network gültig, wenn in Sektion [%s]</translation>
    
ERR
Multiple issues: singular/plural mismatch ("Config setting" is singular), "network" left in English, awkward phrasing, missing article, and missing final period.

Correct translation:
Die Konfigurationseinstellung für %s wird nur im %s‑Netzwerk angewendet, wenn sie im Abschnitt [%s] steht.
```

<!-- cache_translation_check_de_b4046fa3c88c3bad5ab24697f7e12008e5cacd1de9b240cc1196e24f19739c8d -->
```
        <source>Could not top up scriptPubKeys</source>
        <translation>scriptPubKeys konnten nicht aufgeladen werden</translation>
    
ERR
The verb choice is incorrect. "Aufladen" means "to recharge" (e.g., phone credit), while "top up" here means "to replenish/fill up" (e.g., a pool). Use "auffüllen".

Correct translation:
scriptPubKeys konnten nicht aufgefüllt werden
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

<!-- cache_translation_check_de_db909a547c2a4d3332f504080e817eafc2a9ce33f654288e6d9268fa95000470 -->
```
        <source>Unrecognized descriptor found. Loading wallet %s

The wallet might have been created on a newer version.
Please try running the latest software version.
</source>
        <translation>Nicht erkannter Deskriptor gefunden. Wallet %s wird geladen.

Die Wallet wurde möglicherweise in einer neueren Version erstellt.
Bitte versuchen die neueste Softwareversion auszuführen.
</translation>
    
ERR
The imperative sentence is missing the polite form "Sie" and a comma. Also, "in einer neueren Version" is better rendered as "mit einer neueren Version" in this context.

Correct translation:
Nicht erkannter Deskriptor gefunden. Wallet %s wird geladen.

Die Wallet wurde möglicherweise mit einer neueren Version erstellt.
Bitte versuchen Sie, die neueste Softwareversion auszuführen.
```

<!-- cache_translation_check_de_aadb1fe7079854e6d79b4f30bee191b11ec9f182b9851e7487eea9c45ffde974 -->
```
        <source>Failed to start indexes, shutting down…</source>
        <translation>Fehler beim Starten von Indizes, es wird Heruntergefahren...</translation>
    
ERR
Capitalization error: "Heruntergefahren" should be lowercase after a comma. Also match the ellipsis character.

Correct translation:
Fehler beim Starten der Indizes, es wird heruntergefahren…
```

<!-- cache_translation_check_de_d97f463a4f28d187960e6d383c3b73b494d7093037bdf343bd0b749e69dcedb0 -->
```
        <source>Invalid -proxy address or hostname, ends with '=': '%s'</source>
        <translation>Ungültige -proxy Adresse oder Hostname, endet mit '=': '%s'</translation>
    
ERR
Agreement and hyphenation issues in German. It should be the compound “-proxy-Adresse,” and the adjective must agree with both options.

Correct translation:
Ungültige -proxy-Adresse oder ungültiger Hostname, endet mit '=': '%s'
```
</details>

Number of issues: 27.
