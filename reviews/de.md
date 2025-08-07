# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>de</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bde%5D%20low%20quality)


```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Die Zahlungsadresse der Überweisung</translation>
    
YES
The German translation does not accurately reflect the source. "Die Zahlungsadresse der Überweisung" is ambiguous and does not specify that it pertains to a Bitcoin address, nor does it clarify that it is the address to which payment is to be sent.

Correct translation:
Die Bitcoin-Adresse, an die die Zahlung gesendet werden soll
```

```
        <source>Generated coins must mature %1 blocks before they can be spent. When you generated this block, it was broadcast to the network to be added to the block chain. If it fails to get into the chain, its state will change to "not accepted" and it won't be spendable. This may occasionally happen if another node generates a block within a few seconds of yours.</source>
        <translation>Erzeugte Bitcoins müssen %1 Blöcke lang reifen, bevor sie ausgegeben werden können. Als Sie diesen Block erzeugten, wurde er an das Netzwerk übertragen, um ihn der Blockchain hinzuzufügen. Falls dies fehlschlägt wird der Status in "nicht angenommen" geändert und Sie werden keine Bitcoins gutgeschrieben bekommen. Das kann gelegentlich passieren, wenn ein anderer Knoten einen Block fast zeitgleich erzeugt.</translation>
    
YES
Explanation:
- "Bitcoins" is used instead of "coins" ("Münzen" or "Coins"). The English source is more general ("Generated coins"), as Bitcoin supports multiple asset types in recent contexts.
- The sentence "Sie werden keine Bitcoins gutgeschrieben bekommen" does not match the intent of "it won't be spendable". The original says the coins can't be spent, not that you won't receive credit for them.
- Format specifier "%1" is correctly preserved.
- The rest of the translation is mostly accurate, but "goodgeschrieben bekommen" changes the meaning.

Correct translation:
Erzeugte Coins müssen %1 Blöcke lang reifen, bevor sie ausgegeben werden können. Als Sie diesen Block erzeugten, wurde er an das Netzwerk übertragen, um zur Blockchain hinzugefügt zu werden. Falls der Block nicht in die Kette aufgenommen wird, ändert sich sein Status in „nicht angenommen“ und er kann nicht ausgegeben werden. Das kann gelegentlich passieren, wenn ein anderer Knoten einen Block innerhalb weniger Sekunden nach Ihrem erzeugt.
```

```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Fehler: Dumpdatei Format Eintrag ist ungültig. Habe "%s" bekommen, aber "format" erwartet.</translation>
    
YES
The German translation is understandable but the sentence structure is unnatural and the capitalization is incorrect. "Dumpdatei Format Eintrag" should be "Dumpdatei-Format-Eintrag" or "Format-Eintrag der Dumpdatei". Also, in German, "bekommen" is less formal/appropriate here; "erhalten" is preferred in technical contexts. "Fehler" message style prefers "Erhalten" over "Habe ... bekommen".

Correct translation:
Fehler: Der Format-Eintrag der Dumpdatei ist ungültig. "%s" erhalten, aber "format" erwartet.
```

```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Fehler: Die Version %sder Dumpdatei wird nicht unterstützt. Diese Version von bitcoin-wallet unterstützt nur Dumpdateien der Version 1.</translation>
    
YES
There is a formatting issue: In the translated string, "%s" is directly attached to "der" ("Version %sder"), resulting in a missing space between the placeholder and the following word. In addition, the last part of the original source ("Got dumpfile with version %s") is omitted from the translation.

Correct translation:
Fehler: Die Version %s der Dumpdatei wird nicht unterstützt. Diese Version von bitcoin-wallet unterstützt nur Dumpdateien der Version 1. Es wurde eine Dumpdatei mit Version %s gefunden.
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is explicitly forbidden: -onion=0</source>
        <translation>Ausgehende Verbindungen sind eingeschränkt auf Tor (-onlynet=onion), aber der Proxy, um das Tor-Netzwerk zu erreichen ist nicht ausdrücklich verboten (-onion=0)</translation>
    
YES
The translation inaccurately conveys the meaning of "explicitly forbidden". The German translation says "ist nicht ausdrücklich verboten" ("is not explicitly forbidden") which is the opposite of the original message ("is explicitly forbidden"). 

Correct translation:
Ausgehende Verbindungen sind auf Tor (-onlynet=onion) beschränkt, aber der Proxy zum Erreichen des Tor-Netzwerks ist ausdrücklich verboten: -onion=0
```
</details>

Number of issues: 5.
