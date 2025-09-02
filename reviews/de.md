# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>de</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bde%5D%20request)


<!-- cache_translation_check_de_e3c92398da0384a2df7d073b74ab27a95fa1e29352e64d1d9bfd2f0a5ee13131 -->
```
        <source>Copy the currently selected address to the clipboard</source>
        <translation>Kopieren der aktuell ausgewählte Adresse in die Zwischenablage</translation>
    
ERR
German grammar is incorrect. Either use the infinitive construction or the imperative. Also ensure adjective agreement if using a genitive construction.

Correct translation:
Die aktuell ausgewählte Adresse in die Zwischenablage kopieren
```

<!-- cache_translation_check_de_4a4b331d125decb9c7e827826934faf0860de67f89e0d175ab6cd52552da87f9 -->
```
        <source>%1 h</source>
        <translation>%1 S</translation>
    
ERR
The unit was incorrectly changed from "h" (hours) to "S". In German, "h" is also used for hours and should be preserved to match the source.

Correct translation:
%1 h
```

<!-- cache_translation_check_de_7f16d7c974a18118959dea2c14d2be7b801ba8c842760c52722b75a9e55bb3c6 -->
```
        <source>&amp;Window</source>
        <translation>&amp;Programmfenster</translation>
    
ERR
The translation is semantically different. "Window" should be translated as "Fenster" in UI contexts, not "Programmfenster".

Correct translation:
&Fenster
```

<!-- cache_translation_check_de_7eadbe2102be15382bc9015f3f577e7fec84eef711ac1c95f9224f7fc41c0353 -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Standardmäßig die Gebühr vom Betrag abziehen</translation>
    
ERR
The German translation omits the ampersand (&) that marks the keyboard shortcut, which should appear exactly once in the translation. The meaning is accurately conveyed, but for correct UI behavior, the ampersand is required.

Correct translation:
Standardmäßig &Gebühr vom Betrag abziehen
```

<!-- cache_translation_check_de_8b2e09edda1278389e67402ff321ea1e68d8a536088ad207d8ac33d91295897a -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>&amp;Unbestätigtes Wechselgeld darf ausgegeben werden</translation>
    
ERR
The German translation is not faithful to the English. It renders the sentence as a statement ("Unbestätigtes Wechselgeld darf ausgegeben werden") rather than as a menu item or command, and uses "Wechselgeld", which is ambiguous in this context. "Wechselgeld" usually means cash change in German, while "change" in Bitcoin terminology is typically translated as "Wechselbetrag" or simply "Change". The format specifier (&) is preserved correctly.

Correct translation:
&Unbestätigten Wechselbetrag ausgeben
```

<!-- cache_translation_check_de_8b2eb07d76db68a79b60cc017e57ab0e9e56315867f3ab8749d51138852766e6 -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>&amp;PBST-Kontrollen aktivieren</translation>
    
ERR
The acronym PSBT is misspelled as PBST, and "Kontrollen" is not ideal UI wording in German. Use "Steuerelemente".
Correct translation:
&PSBT-Steuerelemente aktivieren
```

<!-- cache_translation_check_de_7ee3ac25088b3ff208013c5095387d053cbc2c0d19cb60299115ea5b8feb8625 -->
```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Ob PSBT-Kontrollen angezeigt werden sollen. </translation>
    
ERR
Trailing whitespace at the end of the translation. Also, "Kontrollen" is uncommon in this context; "Steuerelemente" or "Bedienelemente" is more appropriate.

Correct translation:
Ob PSBT-Steuerelemente angezeigt werden sollen.
```

<!-- cache_translation_check_de_7f16d7c974a18118959dea2c14d2be7b801ba8c842760c52722b75a9e55bb3c6 -->
```
        <source>&amp;Window</source>
        <translation>&amp;Programmfenster</translation>
    
ERR
The translation is semantically different. "Window" should be translated as "Fenster" in UI contexts, not "Programmfenster".

Correct translation:
&Fenster
```

<!-- cache_translation_check_de_b178f65e8227b2569c0f1ad7fef7e5daedbd51ac7b465366828545ebdee7425f -->
```
        <source>&amp;Unit to show amounts in:</source>
        <translation>&amp;Einheit der Beträge:</translation>
    
ERR
The translation omits the part "to show amounts in" which specifies the purpose ("to show amounts in" a particular unit). The translation "Einheit der Beträge" is too general and doesn't reflect the functional intent.

Correct translation:
&amp;Einheit, in der Beträge angezeigt werden:
```

<!-- cache_translation_check_de_208f7861e4803e6564b11a406baad9388ff4141e2137e08c57b58b13c4242be4 -->
```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>Eingaben können nicht unterzeichnet werden, wenn die Brieftasche gesperrt ist.</translation>
    
ERR
"Inputs" in the Bitcoin context are "Eingänge", not "Eingaben" (user inputs). In cryptographic context, "signieren" is preferred over "unterzeichnen", and "Wallet" is the standard term in German UI text.

Correct translation:
Eingänge können nicht signiert werden, solange die Wallet gesperrt ist.
```

<!-- cache_translation_check_de_3b136319368213551fd549917be3f17e29cbcafba6cd806a4f504693ef3b20d8 -->
```
        <source>Sent</source>
        <extracomment>Title of Peers Table column which indicates the total amount of network information we have sent to the peer.</extracomment>
        <translation>Übertragen</translation>
    
ERR
"Übertragen" is less precise here; the column refers to data we have sent. "Gesendet" is the standard German term for this context.

Correct translation:
Gesendet
```

<!-- cache_translation_check_de_1a64fac9465a853789e5e6889a1e40426da0781c3996b8d7f3b2f88cd70a66fa -->
```
        <source>&amp;Information</source>
        <translation>&amp;Informationen</translation>
    
ERR
The translation changes the singular "Information" to the plural "Informationen". In this GUI context, the singular noun is usually correct and matches the original English intent. Also, the single '&' is correctly preserved.

Correct translation:
&Information
```

<!-- cache_translation_check_de_78ab6a62e57e938e5986a6dab2dcc66a6f4ef12732387a3637d0e7e772ea1b49 -->
```
        <source>Sent</source>
        <translation>Übertragen</translation>
    
ERR
"Übertragen" is uncommon/misleading in this context. The standard UI label for outgoing transactions is "Gesendet".

Correct translation:
Gesendet
```

<!-- cache_translation_check_de_4b8ddaac0a6208e49422b93ca403d62813b033230c6d5d51af527a09f6c8481f -->
```
        <source>Clear &amp;All</source>
        <translation>&amp;Zurücksetzen</translation>
    
ERR
The translation "&amp;Zurücksetzen" means "Reset" in German, which does not fully convey the meaning of "Clear All". The English implies that all fields/entries will be cleared, not just a 'reset' operation. Also, "Alle löschen" or "Alles löschen" would be more accurate.

Correct translation:
&amp;Alles löschen
```

<!-- cache_translation_check_de_e01cdbfc95d76b3f72518333b65a179d238a2467ecc7d7eb125baf2d406baea6 -->
```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Die Zahlungsadresse der Überweisung</translation>
    
ERR
The German translation does not accurately reflect the source. "Die Zahlungsadresse der Überweisung" is ambiguous and does not specify that it pertains to a Bitcoin address, nor does it clarify that it is the address to which payment is to be sent.

Correct translation:
Die Bitcoin-Adresse, an die die Zahlung gesendet werden soll
```

<!-- cache_translation_check_de_e502e92f91b72319f3cd2fa212dd162ae5012fff3ef57ab063aa012473a46145 -->
```
        <source>Copy the current signature to the clipboard</source>
        <translation>Kopieren der aktuelle Signatur in die Zwischenablage</translation>
    
ERR
German grammar is incorrect ("der aktuelle" should be "der aktuellen"), and the phrasing is awkward. Use the imperative form for UI text.

Correct translation:
Aktuelle Signatur in die Zwischenablage kopieren
```

<!-- cache_translation_check_de_4b8ddaac0a6208e49422b93ca403d62813b033230c6d5d51af527a09f6c8481f -->
```
        <source>Clear &amp;All</source>
        <translation>&amp;Zurücksetzen</translation>
    
ERR
The translation "&amp;Zurücksetzen" means "Reset" in German, which does not fully convey the meaning of "Clear All". The English implies that all fields/entries will be cleared, not just a 'reset' operation. Also, "Alle löschen" or "Alles löschen" would be more accurate.

Correct translation:
&amp;Alles löschen
```

<!-- cache_translation_check_de_a801f268ad792da99e857270fad1a69facb0c03230e8bb644fc759bff1dcf823 -->
```
        <source>Generated coins must mature %1 blocks before they can be spent. When you generated this block, it was broadcast to the network to be added to the block chain. If it fails to get into the chain, its state will change to "not accepted" and it won't be spendable. This may occasionally happen if another node generates a block within a few seconds of yours.</source>
        <translation>Erzeugte Bitcoins müssen %1 Blöcke lang reifen, bevor sie ausgegeben werden können. Als Sie diesen Block erzeugten, wurde er an das Netzwerk übertragen, um ihn der Blockchain hinzuzufügen. Falls dies fehlschlägt, wird der Status in "nicht angenommen" geändert und Sie werden keine Bitcoins gutgeschrieben bekommen. Das kann gelegentlich passieren, wenn ein anderer Knoten einen Block fast zeitgleich erzeugt.</translation>
    
ERR
The translation mostly conveys the correct meaning but introduces two inaccuracies:

1. The phrase "und Sie werden keine Bitcoins gutgeschrieben bekommen" ("and you will not have Bitcoins credited to you") deviates from the source, which says "and it won't be spendable." This is not a direct equivalent; the translation should indicate the coins are not available for spending, not about being credited.

2. The rest of the translation is good but could match the phrasing more closely, especially for technical accuracy (e.g., "block chain" vs. "Blockchain", though "Blockchain" is acceptable in German).

Correct translation:
Erzeugte Coins müssen %1 Blöcke lang reifen, bevor sie ausgegeben werden können. Als Sie diesen Block erzeugten, wurde er an das Netzwerk übertragen, um zur Blockchain hinzugefügt zu werden. Falls dies fehlschlägt, wird sein Status auf „nicht angenommen“ gesetzt und er kann nicht ausgegeben werden. Dies kann gelegentlich vorkommen, wenn ein anderer Knoten innerhalb weniger Sekunden nach Ihnen einen Block erzeugt.
```

<!-- cache_translation_check_de_efa52dd85b7239631fca72daef91d35d41e0b79baa5e9c09a3c4d86cec8e80cc -->
```
        <source>Copy transaction &amp;ID</source>
        <translation>Transaktionskennung kopieren</translation>
    
ERR
The translation omits the ampersand (&amp;) which is intended to mark the shortcut key. It must be present exactly once in the translation.

Correct translation:
Transaktions&kennung kopieren

or

&Transaktionskennung kopieren
```

<!-- cache_translation_check_de_4612457685f6d8b9d7284297275358be675b0dc410fd10c8cd723c1b57c77046 -->
```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Fehler: Dumpdatei Format Eintrag ist ungültig. "%s" erhalten, "format" erwartet.</translation>
    
ERR
The translation is understandable, but "Dumpdatei Format Eintrag" is not idiomatic German and lacks correct hyphenation. "Dumpdatei-Format-Eintrag" or "Format-Eintrag in der Dumpdatei" would be more appropriate. There are also minor stylistic issues.

Correct translation:
Fehler: Format-Eintrag in der Dumpdatei ist ungültig. "%s" erhalten, "format" erwartet.
```

<!-- cache_translation_check_de_7f9d8b72e7576aeda46917153887e328fba6f2941820cb152be26873a89c7498 -->
```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Fehler: Die Version %s der Dumpdatei wird nicht unterstützt. Diese Version von bitcoin-wallet unterstützt nur Dumpdateien der Version 1.</translation>
    
ERR
The translation omits the second sentence "Got dumpfile with version %s" and instead merges the version specifier %s into the first sentence. Also, the error about the received version is not explicitly stated.

Correct translation:
Fehler: Die Version der Dumpdatei wird nicht unterstützt. Diese Version von bitcoin-wallet unterstützt nur Dumpdateien der Version 1. Gefundene Dumpdatei mit Version %s.
```

<!-- cache_translation_check_de_c2a6d6f620ef1583c161314bdabc0d5eb064654abada07c0562a03c85b4fbf2c -->
```
        <source>Option '-maxorphantx' is set but no longer has any effect (see release notes). Please remove it from your configuration.</source>
        <translation>Die Option '-maxorphantx' ist gesetzt, hat aber keine Wirkung mehr (siehe Release Notes). Bitte von der Konfiguration entfernen.</translation>
    
ERR
The second sentence is an incomplete phrase and uses the less appropriate preposition "von". Also, "Release Notes" should be "Versionshinweise" in German.

Correct translation:
Die Option '-maxorphantx' ist gesetzt, hat aber keine Wirkung mehr (siehe Versionshinweise). Bitte entfernen Sie sie aus Ihrer Konfiguration.
```

<!-- cache_translation_check_de_3d92ea9d9fdeec04a43a8baa25128384119e6d2c692e763422d79e0fb92e88cb -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>Prune: Die Synchronisierung der letzten Wallet geht über beschnittene Daten (pruned) hinaus. Sie müssen -reindex laufen lassen (Es wird die gesamte Blockchain erneut heruntergeladen, falls es ein beschnittener Node (pruned) ist)</translation>
    
ERR
The phrasing “Synchronisierung der letzten Wallet” implies “synchronization of the last wallet” instead of “the last synchronization of the wallet.” Also, “Node” should be “Knoten” in German, and the parenthetical English “(pruned)” is unnecessary.

Correct translation:
Prune: Die letzte Wallet-Synchronisierung geht über die beschnittenen Daten hinaus. Sie müssen -reindex ausführen (bei einem beschnittenen Knoten wird die gesamte Blockchain erneut heruntergeladen)
```

<!-- cache_translation_check_de_6005003fc2f130110c65aef05cbf0acba00ab071edfa8cb7d74f6858dc229945 -->
```
        <source>Config setting for %s only applied on %s network when in [%s] section.</source>
        <translation>Konfigurationseinstellungen für %s sind nur auf %s network gültig, wenn in Sektion [%s]</translation>
    
ERR
- "Konfigurationseinstellungen" is plural; source is singular.
- "network" remains in English; should be "Netzwerk".
- "in Sektion" is awkward; "im Abschnitt" is more idiomatic.
- Missing period at the end.

Correct translation:
Die Konfigurationseinstellung für %s gilt nur im %s-Netzwerk, wenn sie im Abschnitt [%s] steht.
```

<!-- cache_translation_check_de_b4046fa3c88c3bad5ab24697f7e12008e5cacd1de9b240cc1196e24f19739c8d -->
```
        <source>Could not top up scriptPubKeys</source>
        <translation>scriptPubKeys konnten nicht aufgeladen werden</translation>
    
ERR
"Aufgeladen" implies charging (e.g., a battery) and is incorrect here. "Top up" in this context means "auffüllen/nachfüllen".

Correct translation:
ScriptPubKeys konnten nicht aufgefüllt werden
```

<!-- cache_translation_check_de_30cd8c6940936d245663dad4b7e855a03b9182045ac0bd6920f4ef11cd245b27 -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>Fehler beim Laden %s: Wallet ist eine Legacy-Wallet. Bitte mit dem Migrationstool (migratewallet RPC) migrieren zu einer Deskriptor-Wallet.</translation>
    
ERR
German grammar and style issues:
- Missing "von" after "Laden": should be "beim Laden von %s".
- Missing article: "Die Wallet ist eine Legacy-Wallet."
- Awkward phrasing for migration instruction; use "mithilfe des".
- Term is commonly "Descriptor-Wallet" in this context.

Correct translation:
Fehler beim Laden von %s: Die Wallet ist eine Legacy-Wallet. Bitte migrieren Sie mithilfe des Migrationstools (migratewallet RPC) zu einer Descriptor-Wallet.
```

<!-- cache_translation_check_de_ace0c4b67f0bc1c008438c3e7e1eb2350c8d8f0961b653aa87303b8ab6ba2e80 -->
```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on an enormous cluster of unconfirmed transactions.</source>
        <translation>Fehler bei der Berechnung von Bump-Gebühren, da unbestätigte UTXOs von einer enormen Ansammlung unbestätigter Transaktionen abhängen.</translation>
    
ERR
"Bump-Gebühren" is an anglicism and unclear in German UI. Use "Gebührenanhebung" (or "Gebührenerhöhung") to reflect fee bump. The rest is fine.

Correct translation:
Berechnung der Gebührenanhebung fehlgeschlagen, da unbestätigte UTXOs von einem enormen Cluster unbestätigter Transaktionen abhängen.
```

<!-- cache_translation_check_de_9a0a19ab7f27845d9cb3dc862682c892093c5cfa24b2acdb33fb21d296033317 -->
```
        <source>Transaction requires one destination of non-zero value, a non-zero feerate, or a pre-selected input</source>
        <translation>Die Transaktion erfordert ein Ziel mit einem Wert ungleich Null, einen Gebührensatz ungleich Null oder eine vorausgewähltes Input.</translation>
    
ERR
Grammar error: mismatched article/adjective with "Input". It should be accusative masculine (or use "Eingabe" fem.).

Correct translation:
Die Transaktion erfordert ein Ziel mit einem Wert ungleich Null, einen Gebührensatz ungleich Null oder einen vorausgewählten Input.
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
The last sentence is ungrammatical (missing "Sie" and comma). Also "in einer neueren Version" is better as "mit einer neueren Version."

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
"Heruntergefahren" is incorrectly capitalized; it should be lowercase as a verb in this context. Also, the source uses a single ellipsis character (…), while the translation uses three dots (...).

Correct translation:
Fehler beim Starten von Indizes, es wird heruntergefahren…
```

<!-- cache_translation_check_de_d97f463a4f28d187960e6d383c3b73b494d7093037bdf343bd0b749e69dcedb0 -->
```
        <source>Invalid -proxy address or hostname, ends with '=': '%s'</source>
        <translation>Ungültige -proxy Adresse oder Hostname, endet mit '=': '%s'</translation>
    
ERR
German grammar and compounding are off. The adjective only agrees with "Adresse" and not with "Hostname", and "proxy Adresse" should be compounded as "proxy-Adresse".

Correct translation:
Ungültige -proxy-Adresse oder ungültiger Hostname, endet mit '=': '%s'
```
</details>

Number of issues: 31.
