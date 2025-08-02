# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>de</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bde%5D%20low%20quality)


```
        <source>Your wallet is about to be encrypted. </source>
        <translation>Wallet wird verschlüsselt.</translation>
    
YES
The translation is grammatically incorrect and lacks the correct possessive pronoun "Your".
Your wallet is about to be encrypted.
Ihr Wallet wird verschlüsselt.
```

```
        <source>%1 d</source>
        <translation>%1 T</translation>
    
YES. The translation incorrectly translates 'd' to 'T'. In the context of Bitcoin, 'd' typically refers to days. The correct translation for 'd' in this context is 'T'.

%1 T
```

```
        <source>%1 m</source>
        <translation>%1 min</translation>
    
YES, The translation from English to German is incorrect. The English text "%1 m" translates to "%1 m" in German, not "%1 min". The word "min" is an abbreviation for "minute" and is not a direct translation of "m".
%1 m
```

```
        <source>Copy after fee</source>
        <translation>Abzüglich Gebühr kopieren</translation>
    
YES, The translation is incorrect. "Copy after fee" means to copy the amount that remains after the fee has been deducted, not to copy the amount that is deducted from the fee. The correct translation should be "Nach Gebühr kopieren".

Abzüglich Gebühr kopieren
Nach Gebühr kopieren
```

```
        <source>change from %1 (%2)</source>
        <translation>Wechselgeld von %1 (%2)</translation>
    
YES, the translation is problematic. The German word "Wechselgeld" refers to coins or bills returned as change after a purchase, which is not the intended meaning in the context of Bitcoin. In Bitcoin, "change" refers to the unspent output of a transaction. A more appropriate translation would be "Rückgeld" or "Restbetrag".

Correct translation: Rückgeld von %1 (%2)
```

```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>Sicher, dass die Wallet migriert werden soll? &lt;i&gt;%1&lt;/i&gt;?</translation>
    
YES, the translation is missing the word "Sie" (you) in German. The correct translation should be "Sind Sie sicher, dass Sie die Wallet &lt;i&gt;%1&lt;/i&gt; migrieren möchten?".
Sind Sie sicher, dass Sie die Wallet &lt;i&gt;%1&lt;/i&gt; migrieren möchten?
```

```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Lösbare aber nicht beobachtete Scripts wurde in eine neue Wallet namens '%1' überführt.</translation>
    
YES - The translation uses the wrong verb form. The subject "Scripts" is plural, but the verb "wurde" is singular.
Lösbare, aber nicht beobachtete Scripts wurden in eine neue Wallet namens '%1' überführt.
```

```
        <source>Restore wallet message</source>
        <extracomment>Title of message box which is displayed when the wallet is successfully restored.</extracomment>
        <translation>Wallet Wiederherstellungs Nachricht</translation>
    
YES - The translation is grammatically incorrect in German. It should be "Wallet-Wiederherstellungsnachricht".
Wallet Wiederherstellungs Nachricht
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Ohne Unterstützung für die Signierung durch externe Geräte Dritter kompiliert (notwendig für Signierung durch externe Geräte Dritter)</translation>
    
YES: The translation introduces "Dritter" (third party), which is not present in the original text and changes the meaning. The extra comment itself specifies "hardware wallets" as an example of external signing, not "third-party devices".
Ohne Unterstützung für die Signierung durch externe Geräte kompiliert (erforderlich für die Signierung durch externe Geräte)
```

```
        <source>Edit sending address</source>
        <translation>Zahlungsadresse bearbeiten</translation>
    
YES
The translation is inaccurate and misleading. "Zahlungsadresse" (payment address) is not the correct term in the context of Bitcoin transactions. The correct term for a Bitcoin address where funds are sent to is "Bitcoin-Adresse" or simply "Adresse".

Zahlungsadresse bearbeiten
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>Vollständiger Pfad zu %1 einem Bitcoin Core kompatibelen Script (z.B.: C:\Downloads\hwi.exe oder /Users/you/Downloads/hwi.py). Achtung: Malware kann Bitcoins stehlen!</translation>
    
YES: The translation incorrectly adds "Bitcoin Core" to the description of the script, which was not present in the original English text. Additionally, it replaces "your coins" with "Bitcoins", which is a minor change but still alters the original meaning.

Correct translation: Vollständiger Pfad zu einem %1-kompatiblen Skript (z.B. C:\Downloads\hwi.exe oder /Users/you/Downloads/hwi.py). Achtung: Malware kann Ihre Coins stehlen!
```

```
        <source>Expert</source>
        <translation>Experten-Optionen</translation>
    
YES, The translation is problematic. The source text "Expert" is a noun, while the translation "Experten-Optionen" means "expert options". This is a mistranslation as it adds additional words that were not present in the source.
Correct translation: Experten
```

```
        <source>Spend unconfirmed change</source>
        <translation>Unbestätigtes Wechselgeld darf ausgegeben werden</translation>
    
YES, the translation is problematic. The German translation uses "Wechselgeld" which translates to "change" in the sense of coins received after a purchase, and implies that one can spend it. However, in the context of Bitcoin, "change" refers to unspent transaction outputs (UTXOs) that are returned to the sender after a transaction. The provided translation implies that unconfirmed change can be spent, which is not technically correct and could be misleading.

A more accurate translation would be:

Unbestätigte Rückerstattung ausgeben
```

```
        <source>Enable PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>PBST-Kontrollen aktivieren</translation>
    
YES, The translation has a typo in the abbreviation, it should be PSBT and not PBST.
PSBT-Kontrollen aktivieren
```

```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Ob PSBT-Kontrollen angezeigt werden sollen. </translation>
    
YES. The translation has a trailing space.
Ob PSBT-Kontrollen angezeigt werden sollen.
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Ohne Unterstützung für die Signierung durch externe Geräte Dritter kompiliert (notwendig für Signierung durch externe Geräte Dritter)</translation>
    
YES: The translation introduces "Dritter" (third party), which is not present in the original text and changes the meaning. The extra comment itself specifies "hardware wallets" as an example of external signing, not "third-party devices".
Ohne Unterstützung für die Signierung durch externe Geräte kompiliert (erforderlich für die Signierung durch externe Geräte)
```

```
        <source>Hide Peers Detail</source>
        <translation>Reiter mit Peers verstecken</translation>
    
YES
The German translation "Reiter mit Peers verstecken" uses the word "Reiter" which means "tab" in the context of a user interface. The English source text "Hide Peers Detail" does not contain the word "tab" and therefore this translation is erroneous.

The correct translation should be "Details zu Peers ausblenden".

NO
```

```
        <source>Whether we relay transactions to this peer.</source>
        <translation>Ob wir Adressen an diesen Peer weiterleiten.</translation>
    
YES, the translation is problematic because "transactions" was translated to "Adressen" which means "addresses". The correct translation should be "Transaktionen".
Ob wir Transaktionen an diesen Peer weiterleiten.
```

```
        <source>The total number of addresses received from this peer that were processed (excludes addresses that were dropped due to rate-limiting).</source>
        <extracomment>Tooltip text for the Addresses Processed field in the peer details area, which displays the total number of addresses received from this peer that were processed (excludes addresses that were dropped due to rate-limiting).</extracomment>
        <translation>Die Gesamtzahl der von diesem Peer empfangenen Adressen, die aufgrund von Ratenbegrenzung verworfen (nicht verarbeitet) wurden.</translation>
    
YES, the translation is problematic as it incorrectly states that the addresses were dropped due to rate-limiting, when the original text states the opposite. The correct translation should reflect that the addresses *were not* dropped due to rate-limiting.

NO, the translation is problematic. The German translation incorrectly states that the addresses processed were dropped due to rate limiting. The original English text says that addresses *excluded* due to rate limiting were not processed.

Correct translation: Die Gesamtzahl der von diesem Peer empfangenen und verarbeiteten Adressen (schließt Adressen aus, die aufgrund von Ratenbegrenzung verworfen wurden).
```

```
        <source>Outbound Block Relay: does not relay transactions or addresses</source>
        <extracomment>Explanatory text for an outbound peer connection that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>Ausgehende Blockweiterleitung: leitet Transaktionen und Adressen nicht weiter</translation>
    
YES - The translation incorrectly states that transactions and addresses are *not* relayed, when the source text clearly says they are *not* relayed. The correct translation should reflect this.
Ausgehende Blockweiterleitung: leitet keine Transaktionen oder Adressen weiter
```

```
        <source>Copy after fee</source>
        <translation>Abzüglich Gebühr kopieren</translation>
    
YES, The translation is incorrect. "Copy after fee" means to copy the amount that remains after the fee has been deducted, not to copy the amount that is deducted from the fee. The correct translation should be "Nach Gebühr kopieren".

Abzüglich Gebühr kopieren
Nach Gebühr kopieren
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Die Zahlungsadresse der Überweisung</translation>
    
YES: The translation uses "Überweisung" (bank transfer), which is not specific to Bitcoin. A more accurate translation would be "Bitcoin-Adresse" or simply "Adresse" in this context.
Die Bitcoin-Adresse, an die die Zahlung gesendet werden soll
```

```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Geben Sie die Zahlungsadresse des Empfängers, Nachricht (achten Sie darauf Zeilenumbrüche, Leerzeichen, Tabulatoren usw. exakt zu kopieren) und Signatur unten ein, um die Nachricht zu verifizieren. Vorsicht, interpretieren Sie nicht mehr in die Signatur hinein, als in der signierten Nachricht selber enthalten ist, um nicht von einem Man-in-the-middle-Angriff hinters Licht geführt zu werden. Beachten Sie, dass dies nur beweist, dass die signierende Partei über diese Adresse Überweisungen empfangen kann.</translation>
    
YES: The translation is missing a portion of the original English text. The sentence "Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!" is not fully translated. The correct translation should include the part about not proving sendership.

Correct translation: Geben Sie die Zahlungsadresse des Empfängers, Nachricht (achten Sie darauf Zeilenumbrüche, Leerzeichen, Tabulatoren usw. exakt zu kopieren) und Signatur unten ein, um die Nachricht zu verifizieren. Vorsicht, interpretieren Sie nicht mehr in die Signatur hinein, als in der signierten Nachricht selber enthalten ist, um nicht von einem Man-in-the-middle-Angriff hinters Licht geführt zu werden. Beachten Sie, dass dies nur beweist, dass die signierende Partei Überweisungen mit der Adresse erhält, aber nicht die Absenderschaft einer Transaktion beweisen kann!
```

```
        <source>watch-only</source>
        <translation>beobachtet</translation>
    
YES, The translation "beobachtet" is too general and doesn't accurately convey the meaning of "watch-only" in the context of Bitcoin, which implies a wallet or address that can be monitored but cannot be used to send funds. A more appropriate translation would be "nur zur Ansicht" or "nur zur Überwachung".

beobachtet -> nur zur Ansicht
```

```
        <source>Generated coins must mature %1 blocks before they can be spent. When you generated this block, it was broadcast to the network to be added to the block chain. If it fails to get into the chain, its state will change to "not accepted" and it won't be spendable. This may occasionally happen if another node generates a block within a few seconds of yours.</source>
        <translation>Erzeugte Bitcoins müssen %1 Blöcke lang reifen, bevor sie ausgegeben werden können. Als Sie diesen Block erzeugten, wurde er an das Netzwerk übertragen, um ihn der Blockchain hinzuzufügen. Falls dies fehlschlägt wird der Status in "nicht angenommen" geändert und Sie werden keine Bitcoins gutgeschrieben bekommen. Das kann gelegentlich passieren, wenn ein anderer Knoten einen Block fast zeitgleich erzeugt.</translation>
    
YES, The translation is problematic because it introduces new, incorrect information not present in the source text. The source states "it won't be spendable", but the translation states "Sie werden keine Bitcoins gutgeschrieben bekommen" which translates to "you will not be credited with any bitcoins." This is not the same as being unable to spend them. Also, the source text states "its state will change to 'not accepted'" which is correctly translated as "wird der Status in 'nicht angenommen' geändert". The translation on the other hand says "Falls dies fehlschlägt wird der Status in "nicht angenommen" geändert und Sie werden keine Bitcoins gutgeschrieben bekommen." This suggests that not being accepted and not being credited are the same thing, which is not what the source text says.
The correct translation should be:
Erzeugte Coins müssen %1 Blöcke reifen, bevor sie ausgegeben werden können. Als Sie diesen Block erzeugten, wurde er an das Netzwerk übertragen, um ihn der Blockchain hinzuzufügen. Falls dies fehlschlägt, wird sein Status auf "nicht angenommen" geändert und er wird nicht ausgebbar sein. Dies kann gelegentlich passieren, wenn ein anderer Knoten einen Block fast zeitgleich mit Ihrem erzeugt.
```

```
        <source>watch-only</source>
        <translation>beobachtet</translation>
    
YES, The translation "beobachtet" is too general and doesn't accurately convey the meaning of "watch-only" in the context of Bitcoin, which implies a wallet or address that can be monitored but cannot be used to send funds. A more appropriate translation would be "nur zur Ansicht" or "nur zur Überwachung".

beobachtet -> nur zur Ansicht
```

```
        <source>The transaction history was successfully saved to %1.</source>
        <translation>Speichern des Transaktionsverlaufs nach %1 war erfolgreich.</translation>
    
YES. The translation is grammatically incorrect. The correct translation should use the verb "wurde" and place the adverb "erfolgreich" correctly.
Speichern des Transaktionsverlaufs wurde erfolgreich nach %1 vorgenommen.
```

```
        <source>Can't sign transaction.</source>
        <translation>Signierung der Transaktion fehlgeschlagen.</translation>
    
YES, The translation is a mistranslation. The source text "Can't sign transaction." means that the transaction cannot be signed, whereas the translation "Signierung der Transaktion fehlgeschlagen." means that the signing of the transaction failed, implying that it was attempted and unsuccessful. The original meaning implies the inability to sign.
Signierung der Transaktion nicht möglich.
```

```
        <source>The wallet data was successfully saved to %1.</source>
        <translation>Speichern der Wallet-Daten nach %1 war erfolgreich.</translation>
    
YES, The translation is problematic because it uses an incorrect word order and awkward phrasing in German. The correct translation should reflect the active voice of the original sentence.
Speichern der Wallet-Daten nach %1 war erfolgreich.
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>Kann ein aufgespaltenes nicht-HD Wallet nicht von Version %i auf Version %i aktualisieren, ohne auf Unterstützung von Keypools vor der Aufspaltung zu aktualisieren. Bitte benutze Version%i oder keine bestimmte Version.</translation>
    
YES: The translation has a spacing error around the format specifier '%i'.
Kann ein aufgespaltenes nicht-HD Wallet nicht von Version %i auf Version %i aktualisieren, ohne auf Unterstützung von Keypools vor der Aufspaltung zu aktualisieren. Bitte benutze Version %i oder keine bestimmte Version.
```

```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Fehler: Dumpdatei Format Eintrag ist Ungültig. Habe "%s" bekommen, aber "format" erwartet.</translation>
    
YES, The translation is problematic because the word "Ungültig" should be "ungültig" and the word "Habe" should be "habe".
Fehler: Dumpdatei Format Eintrag ist ungültig. Habe "%s" bekommen, aber "format" erwartet.
```

```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Fehler: Die Version der Speicherauszugsdatei ist %s und wird nicht unterstützt. Diese Version von bitcoin-wallet unterstützt nur Speicherauszugsdateien der Version 1.</translation>
    
YES. The format specifier %s has been misplaced in the translation. It should appear at the end of the sentence.

Fehler: Die Version der Speicherauszugsdatei wird nicht unterstützt. Diese Version von bitcoin-wallet unterstützt nur Speicherauszugsdateien der Version 1. Sie erhielten eine Speicherauszugsdatei mit der Version %s.
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>Dies ist die Transaktionsgebühr, die ggf. abgeschrieben wird, wenn das Wechselgeld "Staub" ist in dieser Stufe.</translation>
    
YES. The translation is problematic because it uses the English word "Staub" in quotes, which is not standard German usage and likely indicates an incomplete or incorrect translation. The phrase "abgeschrieben wird" is also not the most accurate translation for "discard" in this context.

A more appropriate translation would be:
Dies ist die Transaktionsgebühr, die Sie verwerfen können, wenn das Wechselgeld auf dieser Stufe kleiner als Staub ist.
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Warnung: Es wurden private Schlüssel in der Wallet {%s} entdeckt, welche private Schlüssel jedoch deaktiviert hat.</translation>
    
YES: The translation incorrectly uses "welche private Schlüssel jedoch deaktiviert hat" which implies the wallet itself has disabled private keys, rather than the private keys being disabled in the wallet. The correct phrasing should indicate that the wallet has private keys that are currently disabled.

Correct translation: Warnung: Es wurden private Schlüssel in der Wallet {%s} entdeckt, bei denen private Schlüssel deaktiviert sind.
```

```
        <source>Error: Transaction %s in wallet cannot be identified to belong to migrated wallets</source>
        <translation>Fehler: Transaktion in Wallet %s kann nicht als zu migrierten Wallet gehörend identifiziert werden</translation>
    
YES. The format specifier %s is misplaced in the translation. The English text has the format specifier after the word "Transaction". The German translation has it after "Wallet".
Error: Transaktion %s in Wallet kann nicht als zu migrierten Wallet gehörend identifiziert werden
```

```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>Fehler beim Entfernen des Snapshot-Chainstate-Verzeichnisses (%s). Entferne es manuell, bevor dem Neustart.
</translation>
    
YES. The sentence structure in the German translation is slightly awkward. The phrase "bevor dem Neustart" is grammatically incorrect. It should be "bevor du neu startest" or "vor dem Neustart".

Correct translation: Fehler beim Entfernen des Snapshot-Chainstate-Verzeichnisses (%s). Entferne es manuell, bevor du neu startest.
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is explicitly forbidden: -onion=0</source>
        <translation>Ausgehende Verbindungen sind eingeschränkt auf Tor (-onlynet=onion), aber der Proxy, um das Tor-Netzwerk zu erreichen ist nicht vorhanden (no -proxy= and no -onion= given) oder ausdrücklich verboten (-onion=0)</translation>
    
YES, The translation is problematic because it incorrectly interprets and translates the phrase "explicitly forbidden: -onion=0". The original English states that the proxy is forbidden, and then clarifies this by providing the specific configuration parameter `-onion=0`. The German translation, however, states that the proxy is "not present (no -proxy= and no -onion= given) OR explicitly forbidden (-onion=0)". This implies two separate conditions for the proxy not being available, when the original English presents a single condition (forbidden) with a specific example.

Correct translation:
Ausgehende Verbindungen sind eingeschränkt auf Tor (-onlynet=onion), aber der Proxy zum Erreichen des Tor-Netzwerks ist ausdrücklich verboten: -onion=0
```

```
        <source>Transaction requires one destination of non-0 value, a non-0 feerate, or a pre-selected input</source>
        <translation>Die Transaktion erfordert ein Ziel mit einem Wert ungleich nicht-0, eine Gebühr ungleich nicht-0 oder eine vorausgewählte Eingabe</translation>
    
YES - The translation is grammatically incorrect and uses awkward phrasing. The phrase "einen Wert ungleich nicht-0" is not standard German.

Correct translation: Die Transaktion erfordert ein Ziel mit einem Wert ungleich 0, eine Gebühr ungleich 0 oder eine vorausgewählte Eingabe.
```

```
        <source>Config setting for %s only applied on %s network when in [%s] section.</source>
        <translation>Konfigurationseinstellungen für %s sind nur auf %s network gültig, wenn in Sektion [%s]</translation>
    
YES. The translation of "network" to "network" is incorrect. It should be "Netzwerk". Additionally, there is a missing period at the end of the sentence.

Konfigurationseinstellungen für %s sind nur auf %s Netzwerk gültig, wenn in Sektion [%s].
```

```
        <source>Dump file %s does not exist.</source>
        <translation>Speicherauszugsdatei %sexistiert nicht.</translation>
    
YES, The translation incorrectly joins the format specifier %s with the word "existiert".
The correct translation should be: Speicherauszugsdatei %s existiert nicht.
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>Fehler: Daten können nicht auf die Festplatte für die Wallet %s geschrieben werden </translation>
    
YES, The translation has an extra space before the closing tag.
Fehler: Daten können nicht auf die Festplatte für die Wallet %s geschrieben werden.
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>Ungültiger Betrag für %s=&lt;amount&gt;: '%s' (muss mindestens %ssein)</translation>
    
YES, The translation has a whitespace issue. The word "mindestens" and "%s" are merged together.
Ungültiger Betrag für %s=&lt;amount&gt;: '%s' (muss mindestens %s sein)
```

```
        <source>Not solvable pre-selected input %s</source>
        <translation>Nicht auflösbare vorausgewählter Input %s</translation>
    
YES
The German translation "Nicht auflösbare vorausgewählter Input %s" contains a grammatical error. The adjective "vorausgewählter" (pre-selected) should agree in gender and case with the noun "Input". Since "Input" is masculine singular in the dative case (implied by the context of being unsolvable), the correct form is "vorausgewähltem".

Correct translation: Nicht auflösbare vorausgewähltem Input %s
```

```
        <source>Reducing -maxconnections from %d to %d, because of system limitations.</source>
        <translation>Reduziere -maxconnections von %d zu %d, aufgrund von Systemlimitierungen.</translation>
    
YES, the preposition "zu" is incorrect here. It should be "auf" to indicate "from X to Y".
Reduziere -maxconnections von %d auf %d, aufgrund von Systemlimitierungen.
```

```
        <source>SQLiteDatabase: Failed to read database verification error: %s</source>
        <translation>Datenbank konnte nicht gelesen werden
Verifikations-Error: %s</translation>
    
YES, The translation is problematic because it uses a newline character inappropriately, splitting the sentence into two parts and making the translation grammatically incorrect. The format specifier %s is correctly translated.
The correct translation is: "SQLiteDatenbank: Fehler beim Lesen der Datenbank Überprüfungsfehler: %s"
```

```
        <source>Section [%s] is not recognized.</source>
        <translation>Sektion [%s] ist nicht delegiert.</translation>
    
YES. The translation of "recognized" as "delegiert" is incorrect in this context. "Delegiert" means "delegated." The correct German word for "recognized" in this context would be "erkannt."

NO
```

```
        <source>The specified config file %s does not exist</source>
        <translation>Die angegebene Konfigurationsdatei %sexistiert nicht</translation>
    
YES, The translation is missing a space before the format specifier %s.
The specified config file %s does not exist
Die angegebene Konfigurationsdatei %s existiert nicht
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>Das Wallet verhindert Zahlungen, die die Mindesttransaktionsgebühr nicht berücksichtigen.</translation>
    
YES, The translation is problematic because it misinterprets "minimum relay fee" in the context of Bitcoin. The German translation implies that the wallet avoids payments that don't *consider* the minimum relay fee, whereas the English original means the wallet will avoid paying *less than* the minimum relay fee.

The correct translation should reflect that the wallet *pays* at least the minimum relay fee, not that it *considers* it.

Correct translation: Das Wallet vermeidet Zahlungen, die weniger als die Mindest-Relay-Gebühr betragen.
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>Transaktion erfordert eine Wechselgeldadresse, die jedoch nicht erzeugt werden kann.</translation>
    
YES, the translation is problematic due to word choice. While "Wechselgeldadresse" is a direct translation of "change address," in the context of Bitcoin transactions, "change address" refers to an address for receiving the leftover Bitcoin after a transaction. The German term "Wechselgeld" typically refers to coins or small denominations of currency given back after a purchase. A more accurate and commonly understood term in German Bitcoin contexts for "change address" is "Rückgeldadresse" or "Restbetragsadresse."

NO
```

```
        <source>Unable to open %s for writing</source>
        <translation>Konnte %s nicht zum Schreiben zu öffnen</translation>
    
YES: The German translation uses "zu öffnen" which is an infinitive construction. The English source uses "to open" as part of a larger phrase. The correct translation should be "Konnte %s nicht zum Schreiben öffnen".
Konnte %s nicht zum Schreiben öffnen
```


<details><summary>pl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bpl%5D%20low%20quality)


```
        <source>Encrypt wallet</source>
        <translation>Zaszyfruj portfel </translation>
    
YES: The translation has an extra space at the end of the translated string.
Correct translation: Zaszyfruj portfel
```

```
        <source>Change passphrase</source>
        <translation>Zmień hasło </translation>
    
YES, The translation has an extra space at the end of the translated text.
Zmień hasło
```

```
        <source>Wallet encrypted</source>
        <translation>Portfel zaszyfrowany </translation>
    
YES: The translation has an extra space at the end.
Correct translation: Portfel zaszyfrowany
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>Wystąpił krytyczny błąd. Upewnij się, że plik ustawień można nadpisać lub uruchom klienta z parametrem -nosettings.</translation>
    
YES - The Polish translation uses "nadpisać" (overwrite) which is not the correct term for "writable" (do zapisu, z możliwością zapisu). The correct translation for "writable" in this context is "do zapisu" or "z możliwością zapisu".

Wystąpił krytyczny błąd. Upewnij się, że plik ustawień jest do zapisu, lub uruchom klienta z parametrem -nosettings.
```

```
        <source>Open a bitcoin: URI</source>
        <translation>Otwórz URI</translation>
    
YES, The translation is missing the word "bitcoin". The correct translation should be "Otwórz URI bitcoin:".
```

```
        <source>Are you sure you wish to close all wallets?</source>
        <translation>Na pewno zamknąć wszystkie portfe?</translation>
    
YES - The Polish translation is missing a proper word for "wallets" in this context. The word "portfele" should be used instead of "portfe".
Na pewno zamknąć wszystkie portfele?
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Co najmniej %1 GB danych, zostanie zapisane w tym katalogu, dane te będą przyrastały w czasie.</translation>
    
YES, The Polish translation is grammatically incorrect. The comma after %1 GB danych is misplaced and creates an awkward sentence structure. The phrase "dane te będą przyrastały w czasie" is also a bit clunky. A more natural phrasing would be "dane będą przyrastać w czasie" or "ich rozmiar będzie rósł w czasie".

Here's a corrected translation:

Co najmniej %1 GB danych zostanie zapisane w tym katalogu, a ich rozmiar będzie rósł w czasie.
```

```
        <source>Maximum database cache size. Make sure you have enough RAM. A larger cache can contribute to faster sync, after which the benefit is less pronounced for most use cases. Lowering the cache size will reduce memory usage. Unused mempool memory is shared for this cache.</source>
        <extracomment>Tooltip text for Options window setting that sets the size of the database cache. Explains the corresponding effects of increasing/decreasing this value.</extracomment>
        <translation>Maksymalna wielkość pamięci podręcznej dla bazy danych osiągnięta. Upewnij się, że masz odpowiednią ilość pamięci RAM. Większa ilość pamięci podręcznej może przyśpieszyć synchronizację, z mniejszym wpływem w większości przypadków. Zmniejszenie wielkości tej pamięci zredukuje użycie pamięci. Nieużywana pamięć mempool jest współdzielona z cache.</translation>
    
YES: The phrase "osiągnięta" (achieved) is inappropriate in this context. It should be removed to convey the intended meaning of "maximum size".
Maksymalna wielkość pamięci podręcznej dla bazy danych. Upewnij się, że masz odpowiednią ilość pamięci RAM. Większa ilość pamięci podręcznej może przyśpieszyć synchronizację, z mniejszym wpływem w większości przypadków. Zmniejszenie wielkości tej pamięci zredukuje użycie pamięci. Nieużywana pamięć mempool jest współdzielona z cache.
```

```
        <source>(But this wallet does not have the right keys.)</source>
        <translation>(Ale ten portfel nie posiada wlaściwych kluczy.)</translation>
    
YES - The translation contains a spelling error. The Polish word for "proper" or "right" should be "właściwych", not "wlaściwych".
(Ale ten portfel nie posiada właściwych kluczy.)
```

```
        <source>Ban for</source>
        <translation>Zbanuj na</translation>
    
YES, The translation is problematic. The Polish translation "Zbanuj na" literally means "Banned on" or "Ban on". In the context of Bitcoin, the English "Ban for" likely refers to the reason for a ban. A more accurate translation would be "Ban za" which translates to "Ban for" or "Ban because of".

Zbanuj na
```

```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>Opcjonalna kwota by zażądać. Zostaw puste lub zero by nie zażądać konkretnej kwoty.</translation>
    
YES - The grammar in the translation is incorrect. "by zażądać" should be "do zażądania" or "o zażądanie".
Opcjonalna kwota do zażądania. Zostaw puste lub zero, aby nie zażądać konkretnej kwoty.
```

```
        <source>Custom change address</source>
        <translation>Niestandardowe zmiany adresu</translation>
    
YES, The translation is problematic because it is inaccurate and nonsensical. In the context of Bitcoin, "change address" refers to an address used to return unspent amounts from a transaction. The provided Polish translation "Niestandardowe zmiany adresu" literally translates to "Custom changes of address," which does not convey the intended meaning.

NO
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Korzystanie z opłaty domyślnej (fallbackfree) może skutkować wysłaniem transakcji, która potwierdzi się w kilka godzin lub dni (lub nigdy). Rozważ wybranie opłaty ręcznie lub poczekaj, aż sprawdzisz poprawność całego łańcucha.</translation>
    
YES: The translation contains a typo ("fallbackfree" instead of "fallbackfee").
Correct translation: Korzystanie z opłaty domyślnej (fallbackfee) może skutkować wysłaniem transakcji, która potwierdzi się w kilka godzin lub dni (lub nigdy). Rozważ wybranie opłaty ręcznie lub poczekaj, aż sprawdzisz poprawność całego łańcucha.
```

```
        <source>Copy bytes</source>
        <translation>Kopiuj ilość bajtów</translation>
    
YES, The translation is inaccurate. "Bytes" in this context refers to raw data, not a quantity. The correct translation should reflect copying the byte data itself.
Kopiuj bajty
```

```
        <source>You can increase the fee later (signals Replace-By-Fee, BIP-125).</source>
        <translation>Możesz później zwiększyć opłatę (sygnalizuje podmień-przez-opłatę (RBF), BIP-125).</translation>
    
YES, the translation incorrectly renders the hyphen within "Replace-By-Fee" as a Polish word. The correct translation should use an English phrase or a more natural Polish equivalent if one exists and is commonly understood in the Bitcoin context.

NO
```

```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Duplikat adres-u znaleziony: adresy powinny zostać użyte tylko raz.</translation>
    
YES, The Polish translation incorrectly uses "adres-u" instead of "adresu". The correct translation is "Duplikat adresu znaleziony: adresy powinny zostać użyte tylko raz."
```

```
        <source>0/unconfirmed, not in memory pool</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that is not in the memory pool.</extracomment>
        <translation>0/niepotwierdzone, nie wysłane do kolejki w pamięci</translation>
    
YES: The translation contains a factual error. "nie wysłane do kolejki w pamięci" translates to "not sent to the memory pool queue", while the original English "not in memory pool" means that the transaction is not present in the memory pool. The correct translation should reflect that the transaction is not in the memory pool itself.

0/niepotwierdzone, nie w puli pamięci
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/niepotwierdzone</translation>
    
YES: The Polish translation for "unconfirmed" is incorrect. The correct translation is "niepotwierdzone".
%1/niepotwierdzone
```

```
        <source>No wallet has been loaded.
Go to File &gt; Open Wallet to load a wallet.
- OR -</source>
        <translation>Portfel nie został wybrany.
Przejdź do Plik &gt; Otwórz Portfel aby wgrać portfel.</translation>
    
YES - The translation is missing the " - OR -" part of the source text.
Correct translation: Portfel nie został wybrany. Przejdź do Plik &gt; Otwórz Portfel aby wgrać portfel. - LUB -
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>PSBT musi być mniejsze niż 100MiB</translation>
    
YES: The Polish translation uses the masculine gender for "PSBT" ("musi być mniejsze"), implying it's a masculine noun. However, "PSBT" is an acronym, and acronyms often default to neuter gender in Polish, or the gender of the underlying noun if it's known. Without specific context on how "PSBT" is treated in Polish Bitcoin communities, it's safer to use a gender-neutral or neuter form if possible, or a more standard masculine form if that's the established convention. However, the provided translation's grammar isn't strictly incorrect if "PSBT" is considered masculine. A more natural phrasing might be desired.

Corrected translation based on common Polish grammar for acronyms (often treated as neuter or masculine based on the implied noun, but "mniejsze" is often acceptable for acronyms):

PSBT musi być mniejsze niż 100 MiB
```

```
        <source>Warning: This may pay the additional fee by reducing change outputs or adding inputs, when necessary. It may add a new change output if one does not already exist. These changes may potentially leak privacy.</source>
        <translation>Ostrzeżenie: Może to spowodować uiszczenie dodatkowej opłaty poprzez zmniejszenie zmian wyjść lub dodanie danych wejściowych, jeśli jest to konieczne. Może dodać nowe wyjście zmiany, jeśli jeszcze nie istnieje. Te zmiany mogą potencjalnie spowodować utratę prywatności.</translation>
    
YES: The phrase "reducing change outputs or adding inputs" was translated as "zmniejszenie zmian wyjść lub dodanie danych wejściowych". While "danych wejściowych" is a correct translation for "inputs", in the context of Bitcoin transactions, the more appropriate term is "przesunięć" or "dodanie przesunięć". The original English text implies adding inputs to cover the fee by using unspent transaction outputs (UTXOs) from the wallet, which are referred to as "przesunięcia" in Polish Bitcoin jargon.

Corrected translation: Ostrzeżenie: Może to spowodować uiszczenie dodatkowej opłaty poprzez zmniejszenie ilości zwracanej reszty lub dodanie przesunięć, jeśli jest to konieczne. Może dodać nowe wyjście reszty, jeśli jeszcze nie istnieje. Te zmiany mogą potencjalnie spowodować utratę prywatności.
```

```
        <source>Cannot downgrade wallet from version %i to version %i. Wallet version unchanged.</source>
        <translation>Nie można zmienić wersji portfela z wersji %ina wersje %i. Wersja portfela pozostaje niezmieniona.</translation>
    
YES, The format specifier '%i' in the source text is incorrectly translated as '%ina' in the target text. The correct translation should be "Nie można zmienić wersji portfela z wersji %i na wersję %i. Wersja portfela pozostaje niezmieniona.".
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>Nie można zaktualizować portfela dzielonego innego niż HD z wersji 1%i do wersji 1%i bez aktualizacji w celu obsługi wstępnie podzielonej puli kluczy. Użyj wersji 1%i lub nie określono wersji.</translation>
    
YES: The translation erroneously adds "1" before the format specifiers (%i). This is incorrect and likely due to a misunderstanding of the format specifiers or a copy-paste error.

Correct translation: Nie można zaktualizować portfela dzielonego innego niż HD z wersji %i do wersji %i bez aktualizacji w celu obsługi wstępnie podzielonej puli kluczy. Użyj wersji %i lub nie określono wersji.
```

```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Błąd: wersja pliku zrzutu nie jest obsługiwana. Ta wersja bitcoin-wallet obsługuje tylko pliki zrzutów w wersji 1. Mam plik zrzutu w wersji 1%s</translation>
    
YES - The translation incorrectly places the format specifier '%s' at the end of the sentence. It should be placed where the version number is mentioned in the original English text.
Błąd: wersja pliku zrzutu nie jest obsługiwana. Ta wersja bitcoin-wallet obsługuje tylko pliki zrzutów w wersji 1. Mam plik zrzutu w wersji %s
```

```
        <source>Error: Unable to produce descriptors for this legacy wallet. Make sure to provide the wallet's passphrase if it is encrypted.</source>
        <translation>Błąd: Nie można wygenerować deskryptorów dla tego starego portfela. Upewnij się najpierw, że portfel jest odblokowany.</translation>
    
YES - The Polish translation is incorrect and does not accurately convey the original English meaning. The original English mentions providing a passphrase if the wallet is encrypted, while the Polish translation states to ensure the wallet is unlocked.

Correct translation: Błąd: Nie można wygenerować deskryptorów dla tego starego portfela. Upewnij się najpierw, że podajesz hasło do portfela, jeśli jest zaszyfrowany.
```

```
        <source>Prune mode is incompatible with -reindex-chainstate. Use full -reindex instead.</source>
        <translation>Tryb przycięty jest niekompatybilny z -reindex-chainstate. Użyj pełnego  -reindex.</translation>
    
YES, The translation is problematic because of an extra space between "pełnego" and "-reindex".
Tryb przycięty jest niekompatybilny z -reindex-chainstate. Użyj pełnego -reindex.
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Nieobsługiwany poziom logowania specyficzny dla kategorii %1$s=%2$s. Oczekiwano %1$s=&lt;category&gt;:&lt;loglevel&gt;. Poprawne kategorie %3$s. Poprawne poziomy logowania: %4 $s.</translation>
    
YES - There is a space before the format specifier %4$s, which should not be there.
The correct translation is: Nieobsługiwany poziom logowania specyficzny dla kategorii %1$s=%2$s. Oczekiwano %1$s=&lt;category&gt;:&lt;loglevel&gt;. Poprawne kategorie %3$s. Poprawne poziomy logowania: %4$s.
```

```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on enormous cluster of unconfirmed transactions.</source>
        <translation>Nie udało się obliczyć opłat za uderzenia, ponieważ niepotwierdzone UTXO zależą od ogromnego skupiska niepotwierdzonych transakcji.</translation>
    
YES - The word "uderzenia" translates to "strikes" or "hits", which is not the correct term for "bump fees" in the context of Bitcoin. The correct term would be "opłat za zwiększenie" or "opłat za podniesienie".

Correct translation: Nie udało się obliczyć opłat za zwiększenie, ponieważ niepotwierdzone UTXO zależą od ogromnego skupiska niepotwierdzonych transakcji.
```

```
        <source>Specified -blockmaxweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Podany -blockmaxweight (%d) przekracza przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)</translation>
    
YES: The translation contains a repeated word "przekracza".
Podany -blockmaxweight (%d) przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)
```

```
        <source>Specified -blockreservedweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Podany -blockreservedweight (%d) przekracza przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)</translation>
    
YES - The Polish translation contains a double word "przekracza przekracza".
The correct translation is: Podany -blockreservedweight (%d) przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)
```

```
        <source>Error: Got key that was not hex: %s</source>
        <translation>Błąd: Otrzymana wartość nie jest szestnastkowa%s</translation>
    
YES: The translation is missing a space before the format specifier %s.
Błąd: Otrzymana wartość nie jest szesnastkowa %s
```

```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Błąd: Otrzymana wartość nie jest szestnastkowa%s</translation>
    
YES, The translation is missing a space before the format specifier %s.
Błąd: Otrzymana wartość nie jest szesnastkowa %s
```

```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>Błąd: Pula kluczy jest pusta, odwołaj się do puli kluczy.</translation>
    
YES, The translation is inaccurate and does not convey the meaning of the source text. The phrase "odwołaj się do puli kluczy" is a literal and incorrect translation of "call keypoolrefill". It should mean "call keypoolrefill function first" or "call keypoolrefill before doing anything else".

Here's a more accurate translation:
Błąd: Pula kluczy jest pusta, najpierw wywołaj funkcję keypoolrefill.
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>Portfel będzie unikał płacenia mniejszej niż przekazana opłaty.</translation>
    
YES: The translation is inaccurate and does not convey the intended meaning of the original English text. It incorrectly translates "minimum relay fee" as "przekazana opłaty" which is nonsensical in this context.

Correct translation: Portfel będzie unikał płacenia niższej niż minimalna opłata za przekazanie.
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>Kwota transakcji musi być dodatnia</translation>
    
YES - The translation is inaccurate. The original English text states that transaction amounts "must not be negative," meaning they can be zero or positive. The Polish translation states that the transaction amount "must be positive," excluding zero.

Correct translation: Kwota transakcji nie może być ujemna
```

```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Zbyt mało dostępnych deskryptorów plików. %d dostępnych, %d wymaganych. </translation>
    
YES - There is an extra space at the end of the translation.
Zbyt mało dostępnych deskryptorów plików. %d dostępnych, %d wymaganych.
```
