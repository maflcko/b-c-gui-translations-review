# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>de</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bde%5D%20low%20quality)


```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>Sicher, dass die Wallet migriert werden soll? &lt;i&gt;%1&lt;/i&gt;?</translation>
    
YES
The translation has a grammatical error with a misplaced and redundant question mark.

Correct translation:
Sicher, dass die Wallet &lt;i&gt;%1&lt;/i&gt; migriert werden soll?
```

```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Lösbare aber nicht beobachtete Scripts wurde in eine neue Wallet namens '%1' überführt.</translation>
    
YES
The verb "wurde" is singular, but the subject "Scripts" is plural. The correct verb form is "wurden".
Lösbare aber nicht beobachtete Scripts wurden in eine neue Wallet namens '%1' überführt.
```

```
        <source>Restore wallet message</source>
        <extracomment>Title of message box which is displayed when the wallet is successfully restored.</extracomment>
        <translation>Wallet Wiederherstellungs Nachricht</translation>
    
YES, The words should be combined into a single compound noun. In German, "Wallet Wiederherstellungs Nachricht" is grammatically incorrect due to the spaces.

Correct translation: Wallet-Wiederherstellungsnachricht
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Ohne Unterstützung für die Signierung durch externe Geräte Dritter kompiliert (notwendig für Signierung durch externe Geräte Dritter)</translation>
    
YES, The translation adds the term "Dritter" (of third parties), which is not present in the source text and makes the translation overly specific and potentially inaccurate. "External" refers to devices external to the software, not necessarily from a third party.

Corrected translation:
Ohne Unterstützung für externe Signierung kompiliert (notwendig für externe Signierung)
```

```
        <source>Edit sending address</source>
        <translation>Zahlungsadresse bearbeiten</translation>
    
YES
The translation "Zahlungsadresse bearbeiten" means "Edit payment address". This is ambiguous as "payment address" could refer to either the sending address or the receiving address. A more precise and clearer translation for "sending address" is "Absenderadresse".

Correct translation:
Absenderadresse bearbeiten
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>Vollständiger Pfad zu %1 einem Bitcoin Core kompatibelen Script (z.B.: C:\Downloads\hwi.exe oder /Users/you/Downloads/hwi.py). Achtung: Malware kann Bitcoins stehlen!</translation>
    
YES
The translation is grammatically incorrect and contains a typo.
1. The phrase "zu %1 einem ... Script" is grammatically incorrect. It should be "zu einem mit %1 kompatiblen Skript".
2. There is a typo in "kompatibelen"; the correct spelling is "kompatiblen".
3. The German spelling "Skript" is preferred over the anglicism "Script".
4. The translation adds "Bitcoin Core", which is not present in the source text.
5. "kann Bitcoins stehlen" is a good translation for "can steal your coins", but "kann Ihre Coins stehlen" is more literal.

A correct translation would be:
Vollständiger Pfad zu einem mit %1 kompatiblen Skript (z.B. C:\Downloads\hwi.exe oder /Users/you/Downloads/hwi.py). Achtung: Malware kann Ihre Coins stehlen
```

```
        <source>Spend unconfirmed change</source>
        <translation>Unbestätigtes Wechselgeld darf ausgegeben werden</translation>
    
YES

The translation is a grammatically correct sentence that describes the function, but the English source is an imperative command, which is more typical for a UI option label. A more direct and concise translation would be better.

Correct translation:
Unbestätigtes Wechselgeld ausgeben
```

```
        <source>Enable PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>PBST-Kontrollen aktivieren</translation>
    
YES
The acronym "PSBT" is misspelled as "PBST".
PSBT-Kontrollen aktivieren
```

```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Ob PSBT-Kontrollen angezeigt werden sollen. </translation>
    
YES
The translation contains a trailing whitespace.
Ob PSBT-Kontrollen angezeigt werden sollen.
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Ohne Unterstützung für die Signierung durch externe Geräte Dritter kompiliert (notwendig für Signierung durch externe Geräte Dritter)</translation>
    
YES, The translation adds the term "Dritter" (of third parties), which is not present in the source text and makes the translation overly specific and potentially inaccurate. "External" refers to devices external to the software, not necessarily from a third party.

Corrected translation:
Ohne Unterstützung für externe Signierung kompiliert (notwendig für externe Signierung)
```

```
        <source>Hide Peers Detail</source>
        <translation>Reiter mit Peers verstecken</translation>
    
YES

The translation incorrectly introduces the word "Reiter" (tab) and omits the word "Detail". A more accurate translation would be "Peer-Details ausblenden" or "Details zu Peers ausblenden".

Correct translation:
Peer-Details ausblenden
```

```
        <source>Whether we relay transactions to this peer.</source>
        <translation>Ob wir Adressen an diesen Peer weiterleiten.</translation>
    
YES, the translation is incorrect. It translates "transactions" as "Adressen" (addresses). The correct German word is "Transaktionen".
Corrected translation: Ob wir Transaktionen an diesen Peer weiterleiten.
```

```
        <source>The total number of addresses received from this peer that were processed (excludes addresses that were dropped due to rate-limiting).</source>
        <extracomment>Tooltip text for the Addresses Processed field in the peer details area, which displays the total number of addresses received from this peer that were processed (excludes addresses that were dropped due to rate-limiting).</extracomment>
        <translation>Die Gesamtzahl der von diesem Peer empfangenen Adressen, die aufgrund von Ratenbegrenzung verworfen (nicht verarbeitet) wurden.</translation>
    
YES
The translation states the opposite of the source text. The source describes the number of addresses that were *processed*, while the translation describes the number of addresses that were *dropped* ("verworfen").

Correct translation:
Die Gesamtzahl der von diesem Peer empfangenen Adressen, die verarbeitet wurden (ausgenommen Adressen, die aufgrund von Ratenbegrenzung verworfen wurden).
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Die Zahlungsadresse der Überweisung</translation>
    
YES
The translation omits the crucial word "Bitcoin", making the address type ambiguous. "Die Zahlungsadresse" (the payment address) is too generic.
Correct translation: Die Bitcoin-Adresse, an die die Zahlung gesendet wird
```

```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Geben Sie die Zahlungsadresse des Empfängers, Nachricht (achten Sie darauf Zeilenumbrüche, Leerzeichen, Tabulatoren usw. exakt zu kopieren) und Signatur unten ein, um die Nachricht zu verifizieren. Vorsicht, interpretieren Sie nicht mehr in die Signatur hinein, als in der signierten Nachricht selber enthalten ist, um nicht von einem Man-in-the-middle-Angriff hinters Licht geführt zu werden. Beachten Sie, dass dies nur beweist, dass die signierende Partei über diese Adresse Überweisungen empfangen kann.</translation>
    
YES
The translation is incomplete. It omits the last clause of the source text: ", it cannot prove sendership of any transaction!". This is a critical security warning and must be included.

Correct translation:
Geben Sie die Zahlungsadresse des Empfängers, Nachricht (achten Sie darauf Zeilenumbrüche, Leerzeichen, Tabulatoren usw. exakt zu kopieren) und Signatur unten ein, um die Nachricht zu verifizieren. Vorsicht, interpretieren Sie nicht mehr in die Signatur hinein, als in der signierten Nachricht selber enthalten ist, um nicht von einem Man-in-the-middle-Angriff hinters Licht geführt zu werden. Beachten Sie, dass dies nur beweist, dass die signierende Partei mit dieser Adresse empfangen kann, es aber nicht die Absenderschaft irgendeiner Transaktion beweisen kann
```

```
        <source>Generated coins must mature %1 blocks before they can be spent. When you generated this block, it was broadcast to the network to be added to the block chain. If it fails to get into the chain, its state will change to "not accepted" and it won't be spendable. This may occasionally happen if another node generates a block within a few seconds of yours.</source>
        <translation>Erzeugte Bitcoins müssen %1 Blöcke lang reifen, bevor sie ausgegeben werden können. Als Sie diesen Block erzeugten, wurde er an das Netzwerk übertragen, um ihn der Blockchain hinzuzufügen. Falls dies fehlschlägt wird der Status in "nicht angenommen" geändert und Sie werden keine Bitcoins gutgeschrieben bekommen. Das kann gelegentlich passieren, wenn ein anderer Knoten einen Block fast zeitgleich erzeugt.</translation>
    
YES, the translation inaccurately translates "and it won't be spendable" as "und Sie werden keine Bitcoins gutgeschrieben bekommen" (and you will not get any Bitcoins credited). This changes the meaning from describing the state of the coins to describing the consequence for the user. Additionally, a comma is missing after the introductory subordinate clause.

Erzeugte Bitcoins müssen %1 Blöcke lang reifen, bevor sie ausgegeben werden können. Als Sie diesen Block erzeugten, wurde er an das Netzwerk übertragen, um ihn der Blockchain hinzuzufügen. Falls dies fehlschlägt, wird sein Status in "nicht angenommen" geändert und er ist nicht ausgebbar. Das kann gelegentlich passieren, wenn ein anderer Knoten einen Block fast zeitgleich erzeugt.
```

```
        <source>The transaction history was successfully saved to %1.</source>
        <translation>Speichern des Transaktionsverlaufs nach %1 war erfolgreich.</translation>
    
YES, The translation is grammatically correct but uses an awkward nominalization ("Speichern ... war erfolgreich") which is unnatural in this context. A passive voice construction would be much more common and fluent, mirroring the English source.

Der Transaktionsverlauf wurde erfolgreich in %1 gespeichert.
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>Kann ein aufgespaltenes nicht-HD Wallet nicht von Version %i auf Version %i aktualisieren, ohne auf Unterstützung von Keypools vor der Aufspaltung zu aktualisieren. Bitte benutze Version%i oder keine bestimmte Version.</translation>
    
YES
A space is missing between "Version" and the format specifier "%i".
Correct translation:
Kann ein aufgespaltenes nicht-HD Wallet nicht von Version %i auf Version %i aktualisieren, ohne auf Unterstützung von Keypools vor der Aufspaltung zu aktualisieren. Bitte benutze Version %i oder keine bestimmte Version.
```

```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Fehler: Dumpdatei Format Eintrag ist Ungültig. Habe "%s" bekommen, aber "format" erwartet.</translation>
    
YES, The adjective "ungültig" is incorrectly capitalized, it must be lowercase. Additionally, "Dumpdatei Format Eintrag" is not a proper German compound noun and sounds unnatural. The second sentence is also phrased colloquially.

Corrected translation:
Fehler: Der Formateintrag der Dumpdatei ist ungültig. Erhalten: "%s", erwartet: "format".
```

```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Fehler: Die Version der Speicherauszugsdatei ist %s und wird nicht unterstützt. Diese Version von bitcoin-wallet unterstützt nur Speicherauszugsdateien der Version 1.</translation>
    
YES, The translation is grammatically correct but stylistically awkward and reorders the information in a slightly unnatural way. The phrase "ist %s und wird nicht unterstützt" ("is %s and is not supported") is clunky. A more direct and natural phrasing would improve the message.

Correct translation:
Fehler: Die Version %s der Speicherauszugsdatei wird nicht unterstützt. Diese Version von bitcoin-wallet unterstützt nur Speicherauszugsdateien der Version 1.
```

```
        <source>Error: Transaction %s in wallet cannot be identified to belong to migrated wallets</source>
        <translation>Fehler: Transaktion in Wallet %s kann nicht als zu migrierten Wallet gehörend identifiziert werden</translation>
    
YES
The placeholder `%s` is misplaced. In the source, it identifies the transaction ("Transaction %s..."), but in the translation, it seems to identify the wallet ("...in Wallet %s"). Furthermore, the translation uses the singular "Wallet", while the source uses the plural "wallets". The overall phrasing is also unnatural.

Correct translation:
Fehler: Transaktion %s in der Wallet kann nicht den migrierten Wallets zugeordnet werden.
```

```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>Fehler beim Entfernen des Snapshot-Chainstate-Verzeichnisses (%s). Entferne es manuell, bevor dem Neustart.
</translation>
    
YES
The preposition "bevor" is used incorrectly. The correct preposition to use with a noun ("dem Neustart") is "vor".

Fehler beim Entfernen des Snapshot-Chainstate-Verzeichnisses (%s). Entferne es manuell vor dem Neustart.
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is explicitly forbidden: -onion=0</source>
        <translation>Ausgehende Verbindungen sind eingeschränkt auf Tor (-onlynet=onion), aber der Proxy, um das Tor-Netzwerk zu erreichen ist nicht vorhanden (no -proxy= and no -onion= given) oder ausdrücklich verboten (-onion=0)</translation>
    
YES

The translation adds information that is not present in the source text. The source states that the proxy is "explicitly forbidden: -onion=0". The translation adds a case where the proxy is "nicht vorhanden (no -proxy= and no -onion= given)", which is not mentioned in the original English text.

Correct translation:
Ausgehende Verbindungen sind auf Tor beschränkt (-onlynet=onion), aber der Proxy zum Erreichen des Tor-Netzwerks ist explizit verboten: -onion=0
```

```
        <source>Transaction requires one destination of non-0 value, a non-0 feerate, or a pre-selected input</source>
        <translation>Die Transaktion erfordert ein Ziel mit einem Wert ungleich nicht-0, eine Gebühr ungleich nicht-0 oder eine vorausgewählte Eingabe</translation>
    
YES, The translation contains a double negative which reverses the meaning. "ungleich nicht-0" literally translates to "unequal to not-0", which means "equal to 0". The source "non-0" means "ungleich 0" (unequal to 0).

Die Transaktion erfordert ein Ziel mit einem Wert ungleich 0, eine Gebührenrate ungleich 0 oder eine vorausgewählte Eingabe.
```

```
        <source>Config setting for %s only applied on %s network when in [%s] section.</source>
        <translation>Konfigurationseinstellungen für %s sind nur auf %s network gültig, wenn in Sektion [%s]</translation>
    
YES, the translation uses the English word "network" instead of the German "Netzwerk", and the incorrect German word "Sektion" instead of "Abschnitt" for a configuration file section. It is also grammatically awkward and misses the final period.

Corrected translation:
Konfigurationseinstellung für %s ist nur im %s-Netzwerk gültig, wenn sie im Abschnitt [%s] steht.
```

```
        <source>Dump file %s does not exist.</source>
        <translation>Speicherauszugsdatei %sexistiert nicht.</translation>
    
YES
There is a missing space after the format specifier %s.
Speicherauszugsdatei %s existiert nicht.
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>Fehler: Daten können nicht auf die Festplatte für die Wallet %s geschrieben werden </translation>
    
YES
The translation contains a trailing whitespace.
Fehler: Daten können nicht auf die Festplatte für die Wallet %s geschrieben werden
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>Ungültiger Betrag für %s=&lt;amount&gt;: '%s' (muss mindestens %ssein)</translation>
    
YES
There is a missing space between the last format specifier %s and the word 'sein'.
Ungültiger Betrag für %s=&lt;amount&gt;: '%s' (muss mindestens %s sein)
```

```
        <source>Not solvable pre-selected input %s</source>
        <translation>Nicht auflösbare vorausgewählter Input %s</translation>
    
YES
The adjective "auflösbare" has an incorrect grammatical ending. For the masculine noun "Input", the correct declension is "auflösbarer".

Correct translation:
Nicht auflösbarer vorausgewählter Input %s
```

```
        <source>Reducing -maxconnections from %d to %d, because of system limitations.</source>
        <translation>Reduziere -maxconnections von %d zu %d, aufgrund von Systemlimitierungen.</translation>
    
YES
The preposition 'zu' is incorrect in this context. The correct German phrase for changing a value 'from X to Y' is 'von X auf Y'.

Correct translation:
Reduziere -maxconnections von %d auf %d aufgrund von Systemlimitierungen.
```

```
        <source>SQLiteDatabase: Failed to read database verification error: %s</source>
        <translation>Datenbank konnte nicht gelesen werden
Verifikations-Error: %s</translation>
    
YES, The translation is problematic because it omits the "SQLiteDatabase:" prefix, which provides essential context for the error message. It also introduces a line break that is not present in the original string, changing the format.

Correct translation:
SQLiteDatabase: Fehler beim Lesen der Datenbank, Verifizierungsfehler: %s
```

```
        <source>Section [%s] is not recognized.</source>
        <translation>Sektion [%s] ist nicht delegiert.</translation>
    
YES
The translation is incorrect. The German word "delegiert" means "delegated", while the English source text says "recognized". The correct German word for "recognized" is "erkannt" or "bekannt".
Correct translation: Sektion [%s] wird nicht erkannt.
```

```
        <source>The specified config file %s does not exist</source>
        <translation>Die angegebene Konfigurationsdatei %sexistiert nicht</translation>
    
YES
A space is missing between the format specifier %s and the following word.
Die angegebene Konfigurationsdatei %s existiert nicht
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>Das Wallet verhindert Zahlungen, die die Mindesttransaktionsgebühr nicht berücksichtigen.</translation>
    
YES, The translation incorrectly states that the wallet "prevents payments" ("verhindert Zahlungen"). The source text explains that the wallet "avoids paying" a *fee* that is too low. The wallet does not block the entire payment, but rather ensures that the fee associated with it is sufficient.

A more accurate translation is: "Das Wallet vermeidet es, weniger als die Mindest-Relay-Gebühr zu zahlen."
```

```
        <source>Unable to open %s for writing</source>
        <translation>Konnte %s nicht zum Schreiben zu öffnen</translation>
    
YES
The German grammar is incorrect. The verb 'öffnen' should be in the infinitive without 'zu' when used with the modal verb 'konnte'.

Konnte %s nicht zum Schreiben öffnen
```
</details>
