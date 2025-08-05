# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>de</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bde%5D%20low%20quality)


```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Die Zahlungsadresse der Überweisung</translation>
    
YES  
The translation "Die Zahlungsadresse der Überweisung" is inaccurate and somewhat unclear in the Bitcoin context. It literally means "the payment address of the transfer," which is ambiguous and could confuse users. The original English clearly states "The Bitcoin address to send the payment to," so the translation should explicitly mention Bitcoin and the act of sending payment to that address.  

Correct translation:  
Die Bitcoin-Adresse, an die die Zahlung gesendet wird
```

```
        <source>Generated coins must mature %1 blocks before they can be spent. When you generated this block, it was broadcast to the network to be added to the block chain. If it fails to get into the chain, its state will change to "not accepted" and it won't be spendable. This may occasionally happen if another node generates a block within a few seconds of yours.</source>
        <translation>Erzeugte Bitcoins müssen %1 Blöcke lang reifen, bevor sie ausgegeben werden können. Als Sie diesen Block erzeugten, wurde er an das Netzwerk übertragen, um ihn der Blockchain hinzuzufügen. Falls dies fehlschlägt wird der Status in "nicht angenommen" geändert und Sie werden keine Bitcoins gutgeschrieben bekommen. Das kann gelegentlich passieren, wenn ein anderer Knoten einen Block fast zeitgleich erzeugt.</translation>
    
YES
The translation is mostly accurate but there are minor issues and improvements for clarity and correctness:

1. "Erzeugte Bitcoins" is more specific than the original "Generated coins," but given the Bitcoin context, this is acceptable.
2. Missing a comma before "wird der Status" in the third sentence.
3. The phrase "werden keine Bitcoins gutgeschrieben bekommen" is awkward and less natural in German; a better phrasing is "werden nicht ausgegeben können" or "werden nicht ausgegeben werden können" to directly reflect "won't be spendable."
4. The last sentence uses "fast zeitgleich," which is OK but "innerhalb weniger Sekunden" as in the source is clearer and more literal.

Corrected translation:

Erzeugte Bitcoins müssen %1 Blöcke lang reifen, bevor sie ausgegeben werden können. Als Sie diesen Block erzeugten, wurde er an das Netzwerk übertragen, um ihn der Blockchain hinzuzufügen. Falls dies fehlschlägt, wird der Status in „nicht angenommen“ geändert und sie können nicht ausgegeben werden. Das kann gelegentlich passieren, wenn ein anderer Knoten innerhalb weniger Sekunden einen Block erzeugt.
```

```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Fehler: Dumpdatei Format Eintrag ist ungültig. Habe "%s" bekommen, aber "format" erwartet.</translation>
    
YES
The translation is understandable but awkward and partially incorrect in phrasing and word order. In German, "Dumpdatei Format Eintrag" should be combined more naturally, e.g., "Das Format des Dumpdatei-Eintrags". Also, "Habe ... bekommen, aber ... erwartet" is informal and not precise enough for error messages. The English phrase "format record" implies a specific technical term and should be translated accordingly.

Correct translation:
Fehler: Der Datensatz im Dumpdatei-Format ist inkorrekt. Erhielt "%s", erwartet "format".
```

```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Fehler: Die Version %sder Dumpdatei wird nicht unterstützt. Diese Version von bitcoin-wallet unterstützt nur Dumpdateien der Version 1.</translation>
    
YES
The translation incorrectly places the format specifier %s immediately after "Version" without a space, causing formatting issues. Additionally, the original sentence mentions receiving a dumpfile with version %s, which is missing in the translation.

Correct translation:
Fehler: Die Version %s der Dumpdatei wird nicht unterstützt. Diese Version von bitcoin-wallet unterstützt nur Dumpdateien der Version 1. Got dumpfile with version %s

However, the exact phrase "Got dumpfile with version %s" should be translated as well for completeness:

Fehler: Die Version %s der Dumpdatei wird nicht unterstützt. Diese Version von bitcoin-wallet unterstützt nur Dumpdateien der Version 1. Dumpdatei mit Version %s erhalten. 

Alternatively, for better style, you could merge into one sentence:

Fehler: Die Dumpdatei-Version %s wird nicht unterstützt. Diese Version von bitcoin-wallet unterstützt nur Dumpdateien der Version 1.

But to stay close to the source, the minimal fix is inserting a space after %s and adding the missing part:

Fehler: Die Version %s der Dumpdatei wird nicht unterstützt. Diese Version von bitcoin-wallet unterstützt nur Dumpdateien der Version 1. Dumpdatei mit Version %s erhalten.
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is explicitly forbidden: -onion=0</source>
        <translation>Ausgehende Verbindungen sind eingeschränkt auf Tor (-onlynet=onion), aber der Proxy, um das Tor-Netzwerk zu erreichen ist nicht ausdrücklich verboten (-onion=0)</translation>
    
YES  
The original English states that the proxy is "explicitly forbidden," which means it is clearly disallowed. The German translation says "ist nicht ausdrücklich verboten," which means "is not explicitly forbidden," which reverses the meaning. Also, there is a missing comma before "ist" for correct punctuation.

Correct translation:  
Ausgehende Verbindungen sind eingeschränkt auf Tor (-onlynet=onion), aber der Proxy, um das Tor-Netzwerk zu erreichen, ist ausdrücklich verboten: -onion=0
```
</details>
