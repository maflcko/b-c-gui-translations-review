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
</details>


<details><summary>pl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bpl%5D%20low%20quality)


```
        <source>Encrypt wallet</source>
        <translation>Zaszyfruj portfel </translation>
    
YES
The translation has a trailing whitespace.
Correct translation: Zaszyfruj portfel
```

```
        <source>Change passphrase</source>
        <translation>Zmień hasło </translation>
    
YES
The translation contains a trailing space.
Correct translation: Zmień hasło
```

```
        <source>Wallet encrypted</source>
        <translation>Portfel zaszyfrowany </translation>
    
YES. The translation has a trailing space.
Correct translation: Portfel zaszyfrowany
```

```
        <source>Open a bitcoin: URI</source>
        <translation>Otwórz URI</translation>
    
YES The translation is incomplete. It omits the "bitcoin:" part, which specifies the type of URI.

Correct translation: Otwórz URI bitcoin:
```

```
        <source>Are you sure you wish to close all wallets?</source>
        <translation>Na pewno zamknąć wszystkie portfe?</translation>
    
YES
The word "portfe" is a grammatical error. The correct plural form of "portfel" (wallet) is "portfele".

Correct translation:
Na pewno zamknąć wszystkie portfele?
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Co najmniej %1 GB danych, zostanie zapisane w tym katalogu, dane te będą przyrastały w czasie.</translation>
    
YES, The translation contains a grammatical error: an unnecessary comma after "danych", which incorrectly separates the subject from the verb. The overall sentence structure is also slightly unnatural.

Correct translation:
Co najmniej %1 GB danych zostanie zapisanych w tym katalogu, a ich ilość będzie z czasem rosła.
```

```
        <source>Maximum database cache size. Make sure you have enough RAM. A larger cache can contribute to faster sync, after which the benefit is less pronounced for most use cases. Lowering the cache size will reduce memory usage. Unused mempool memory is shared for this cache.</source>
        <extracomment>Tooltip text for Options window setting that sets the size of the database cache. Explains the corresponding effects of increasing/decreasing this value.</extracomment>
        <translation>Maksymalna wielkość pamięci podręcznej dla bazy danych osiągnięta. Upewnij się, że masz odpowiednią ilość pamięci RAM. Większa ilość pamięci podręcznej może przyśpieszyć synchronizację, z mniejszym wpływem w większości przypadków. Zmniejszenie wielkości tej pamięci zredukuje użycie pamięci. Nieużywana pamięć mempool jest współdzielona z cache.</translation>
    
YES, The first sentence incorrectly translates the setting's title "Maximum database cache size" as a status message "Maksymalna wielkość ... osiągnięta" (Maximum size ... reached). Additionally, the translation of "after which the benefit is less pronounced" is imprecise, losing the sequential meaning.

Maksymalny rozmiar pamięci podręcznej bazy danych. Upewnij się, że masz wystarczająco dużo pamięci RAM. Większa pamięć podręczna może przyczynić się do szybszej synchronizacji, po której korzyść jest mniej odczuwalna w większości przypadków. Zmniejszenie rozmiaru pamięci podręcznej zredukuje zużycie pamięci. Nieużywana pamięć puli pamięci (mempool) jest współdzielona na potrzeby tej pamięci podręcznej.
```

```
        <source>(But this wallet does not have the right keys.)</source>
        <translation>(Ale ten portfel nie posiada wlaściwych kluczy.)</translation>
    
YES, The word "wlaściwych" is misspelled. It should be "właściwych".
(Ale ten portfel nie posiada właściwych kluczy.)
```

```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>Opcjonalna kwota by zażądać. Zostaw puste lub zero by nie zażądać konkretnej kwoty.</translation>
    
YES, The first part of the translation, "Opcjonalna kwota by zażądać", is grammatically awkward and unnatural. The construction "by + infinitive" is incorrect in this context. A proper way to express this would be using a noun phrase or a "do + gerund" structure.

Correct translation:
Opcjonalna kwota do zażądania. Pozostaw to pole puste lub wpisz zero, aby nie żądać określonej kwoty.
```

```
        <source>Custom change address</source>
        <translation>Niestandardowe zmiany adresu</translation>
    
YES, The translation is incorrect. The word "change" in the context of a transaction means the remainder ("reszta" in Polish), not an alteration ("zmiana"). The current translation "Niestandardowe zmiany adresu" means "Non-standard changes of an address", which is wrong. The correct translation should refer to a custom address for the transaction change.

Correct translation:
Niestandardowy adres reszty
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Korzystanie z opłaty domyślnej (fallbackfree) może skutkować wysłaniem transakcji, która potwierdzi się w kilka godzin lub dni (lub nigdy). Rozważ wybranie opłaty ręcznie lub poczekaj, aż sprawdzisz poprawność całego łańcucha.</translation>
    
YES
The translation contains a typo. The English term "fallbackfee" has been misspelled as "fallbackfree" in the Polish translation.

Correct translation:
Korzystanie z opłaty domyślnej (fallbackfee) może skutkować wysłaniem transakcji, która potwierdzi się w kilka godzin lub dni (lub nigdy). Rozważ wybranie opłaty ręcznie lub poczekaj, aż sprawdzisz poprawność całego łańcucha.
```

```
        <source>Copy bytes</source>
        <translation>Kopiuj ilość bajtów</translation>
    
YES. The translation adds the word "ilość" (amount/quantity), which changes the meaning. "Copy bytes" implies copying the actual byte data, while "Kopiuj ilość bajtów" means "Copy the amount/number of bytes".

Kopiuj bajty
```

```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>Duplikat adres-u znaleziony: adresy powinny zostać użyte tylko raz.</translation>
    
YES
The word "adres-u" is grammatically incorrect due to the hyphen. The correct genitive form is "adresu". Additionally, the word order in the first part is unnatural.
Correct translation: Znaleziono duplikat adresu: adresy powinny zostać użyte tylko raz.
```

```
        <source>0/unconfirmed, not in memory pool</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that is not in the memory pool.</extracomment>
        <translation>0/niepotwierdzone, nie wysłane do kolejki w pamięci</translation>
    
YES, The translation interprets the state rather than translating it directly, which can be misleading.

"nie wysłane do kolejki w pamięci" translates to "not sent to the queue in memory". The original English "not in memory pool" is a statement of the transaction's current state. It might not be in the memory pool for reasons other than not being sent (e.g., it was rejected by nodes). A more accurate and standard translation for "not in memory pool" in Polish Bitcoin terminology is "nie w puli pamięci".

Correct translation:
<translation>0/niepotwierdzone, nie w puli pamięci</translation>
```

```
        <source>No wallet has been loaded.
Go to File &gt; Open Wallet to load a wallet.
- OR -</source>
        <translation>Portfel nie został wybrany.
Przejdź do Plik &gt; Otwórz Portfel aby wgrać portfel.</translation>
    
YES, The translation is problematic. It is incomplete and uses suboptimal wording.

The phrase "- OR -" is completely missing from the translation. Additionally, the verb "to load" is translated first as "wybrany" (selected) and then "wgrać" (to upload), while a more accurate and consistent term would be "wczytać" (to load).

A corrected translation would be:
Nie wczytano portfela.
Przejdź do Plik &gt; Otwórz Portfel, aby wczytać portfel.
- LUB -
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>PSBT musi być mniejsze niż 100MiB</translation>
    
YES
The translation omits the word "file" ("plik") from the source text. It also has a whitespace issue, as there should be a space between the number and the unit (100 MiB). A more accurate translation would also adjust the adjective's gender to match "plik" (masculine).

Correct translation:
Plik PSBT musi być mniejszy niż 100 MiB
```

```
        <source>Warning: This may pay the additional fee by reducing change outputs or adding inputs, when necessary. It may add a new change output if one does not already exist. These changes may potentially leak privacy.</source>
        <translation>Ostrzeżenie: Może to spowodować uiszczenie dodatkowej opłaty poprzez zmniejszenie zmian wyjść lub dodanie danych wejściowych, jeśli jest to konieczne. Może dodać nowe wyjście zmiany, jeśli jeszcze nie istnieje. Te zmiany mogą potencjalnie spowodować utratę prywatności.</translation>
    
YES, The translation incorrectly translates the Bitcoin-specific term "change" (as in leftover funds from a transaction). It uses the word "zmiana" (which means 'a modification' or 'a shift'), while the correct Polish term in this context is "reszta". This makes the translation confusing and technically incorrect.

Corrected translation:
Ostrzeżenie: Może to spowodować uiszczenie dodatkowej opłaty poprzez zmniejszenie wyjść reszty lub dodanie wejść, gdy jest to konieczne. Może zostać dodane nowe wyjście reszty, jeśli jeszcze nie istnieje. Te zmiany mogą potencjalnie naruszyć prywatność.
```

```
        <source>Cannot downgrade wallet from version %i to version %i. Wallet version unchanged.</source>
        <translation>Nie można zmienić wersji portfela z wersji %ina wersje %i. Wersja portfela pozostaje niezmieniona.</translation>
    
YES, W słowie „%ina” brakuje spacji między specyfikatorem formatu a słowem „na”. Dodatkowo, słowo „zmienić” jest mniej precyzyjne niż „obniżyć” w kontekście „downgrade”, a forma „wersje” jest niepoprawna gramatycznie – powinna być „wersję”.

Correct translation:
Nie można obniżyć wersji portfela z %i do %i. Wersja portfela pozostaje niezmieniona.
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>Nie można zaktualizować portfela dzielonego innego niż HD z wersji 1%i do wersji 1%i bez aktualizacji w celu obsługi wstępnie podzielonej puli kluczy. Użyj wersji 1%i lub nie określono wersji.</translation>
    
YES
The format specifiers `%i` are incorrectly written as `1%i` in the translation. This will cause the application to display incorrect version numbers. Additionally, the phrasing "innego niż HD" is slightly awkward, and the final clause "lub nie określono wersji" is grammatically inconsistent with the preceding imperative "Użyj".

Correct translation:
Nie można zaktualizować portfela dzielonego nie-HD z wersji %i do wersji %i bez aktualizacji w celu obsługi wstępnie podzielonej puli kluczy. Użyj wersji %i lub nie określaj wersji.
```

```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Błąd: wersja pliku zrzutu nie jest obsługiwana. Ta wersja bitcoin-wallet obsługuje tylko pliki zrzutów w wersji 1. Mam plik zrzutu w wersji 1%s</translation>
    
YES
The last part of the sentence is translated incorrectly. The phrase "Got dumpfile with version %s" was translated to "Mam plik zrzutu w wersji 1%s", which is wrong. It should be "Otrzymano plik zrzutu w wersji %s" or "Znaleziono plik zrzutu w wersji %s". The translator mistakenly added the number "1" before the format specifier `%s`.

Correct translation:
Błąd: wersja pliku zrzutu nie jest obsługiwana. Ta wersja bitcoin-wallet obsługuje tylko pliki zrzutów w wersji 1. Otrzymano plik zrzutu w wersji %s
```

```
        <source>Error: Unable to produce descriptors for this legacy wallet. Make sure to provide the wallet's passphrase if it is encrypted.</source>
        <translation>Błąd: Nie można wygenerować deskryptorów dla tego starego portfela. Upewnij się najpierw, że portfel jest odblokowany.</translation>
    
YES
The translation of the second sentence is inaccurate. It changes the specific instruction "Make sure to provide the wallet's passphrase if it is encrypted" to a more general and less helpful "Make sure first that the wallet is unlocked". This omits the key information about the passphrase and the condition of the wallet being encrypted.

Correct translation:
Błąd: Nie można wygenerować deskryptorów dla tego starego portfela. Upewnij się, że podajesz hasło do portfela, jeśli jest on zaszyfrowany.
```

```
        <source>Prune mode is incompatible with -reindex-chainstate. Use full -reindex instead.</source>
        <translation>Tryb przycięty jest niekompatybilny z -reindex-chainstate. Użyj pełnego  -reindex.</translation>
    
YES
There is a double space before "-reindex".
Correct translation: Tryb przycięty jest niekompatybilny z -reindex-chainstate. Użyj pełnego -reindex.
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>Nieobsługiwany poziom logowania specyficzny dla kategorii %1$s=%2$s. Oczekiwano %1$s=&lt;category&gt;:&lt;loglevel&gt;. Poprawne kategorie %3$s. Poprawne poziomy logowania: %4 $s.</translation>
    
YES, The format specifier `%4 $s` contains an extra space before `$s`. Additionally, a colon is missing after "kategorie" for better consistency.

Correct translation:
Nieobsługiwany poziom logowania specyficzny dla kategorii %1$s=%2$s. Oczekiwano %1$s=&lt;category&gt;:&lt;loglevel&gt;. Poprawne kategorie: %3$s. Poprawne poziomy logowania: %4$s.
```

```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on enormous cluster of unconfirmed transactions.</source>
        <translation>Nie udało się obliczyć opłat za uderzenia, ponieważ niepotwierdzone UTXO zależą od ogromnego skupiska niepotwierdzonych transakcji.</translation>
    
YES, "opłat za uderzenia" is an incorrect, literal translation of "bump fees". In Polish, "uderzenia" means "strikes" or "hits", which is nonsensical in this context. The correct term for fee bumping is "podbicie opłaty" or "zwiększenie opłaty".

Correct translation:
Nie udało się obliczyć opłat za podbicie, ponieważ niepotwierdzone UTXO zależą od ogromnego skupiska niepotwierdzonych transakcji.
```

```
        <source>Specified -blockmaxweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Podany -blockmaxweight (%d) przekracza przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)</translation>
    
YES, the word "przekracza" is duplicated.

Podany -blockmaxweight (%d) przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)
```

```
        <source>Specified -blockreservedweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Podany -blockreservedweight (%d) przekracza przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)</translation>
    
YES
The word "przekracza" is duplicated.
Correct translation: Podany -blockreservedweight (%d) przekracza maksymalną wagę bloku dopuszczoną przez konsensus (%d)
```

```
        <source>Error: Got key that was not hex: %s</source>
        <translation>Błąd: Otrzymana wartość nie jest szestnastkowa%s</translation>
    
YES, The translation is missing a colon and a space before the format specifier. The word "wartość" (value) is used instead of the more direct "klucz" (key).

Correct translation:
Błąd: Otrzymany klucz nie jest szesnastkowy: %s
```

```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Błąd: Otrzymana wartość nie jest szestnastkowa%s</translation>
    
YES
The translation is missing a colon and a space before the %s format specifier. Additionally, there is a typo in the word "szesnastkowa".
Correct translation: Błąd: Otrzymana wartość nie jest szesnastkowa: %s
```

```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>Błąd: Pula kluczy jest pusta, odwołaj się do puli kluczy.</translation>
    
YES, The translation incorrectly translates the instruction "please call keypoolrefill first". "Odwołaj się do puli kluczy" means "refer to the keypool", which is a vague and incorrect instruction. It omits the specific function name `keypoolrefill` and uses the wrong verb for invoking a function.

Correct translation:
Błąd: Pula kluczy została wyczerpana, najpierw wywołaj keypoolrefill.
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>Portfel będzie unikał płacenia mniejszej niż przekazana opłaty.</translation>
    
YES
The translation is inaccurate. It omits the word "minimum" and translates "relay fee" incorrectly as "przekazana opłata" (the relayed/transferred fee), which changes the meaning of the sentence. The correct translation should specify the "minimum relay fee".

Correct translation:
Portfel będzie unikał płacenia opłaty niższej niż minimalna opłata za przekazanie.
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>Kwota transakcji musi być dodatnia</translation>
    
YES
The translation is not precise. The source "must not be negative" means the value can be zero or positive. The translation "musi być dodatnia" means "must be positive", which excludes zero.

Correct translation: Kwoty transakcji nie mogą być ujemne.
```

```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>Zbyt mało dostępnych deskryptorów plików. %d dostępnych, %d wymaganych. </translation>
    
YES The translation has a trailing space at the end.
Zbyt mało dostępnych deskryptorów plików. %d dostępnych, %d wymaganych.
```
</details>
