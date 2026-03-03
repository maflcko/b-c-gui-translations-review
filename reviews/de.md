# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bde%5D%20request)



<details><summary>de</summary>


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

<!-- cache_translation_check_de_3c52bef835a0cf78d9931e9650618fb99427c43d6b266cab969ebb81fab9c8e1 -->
```
        <source>Copy transaction &amp;ID</source>
        <translation>Transaktions-$ID kopieren</translation>
    
ERR
The shortcut key marker '&amp;' has been replaced with '$', and the placement has changed. In the context of this software translation, the '&amp;' must be preserved exactly once to indicate the keyboard shortcut.

Correct translation:
Transaktions-&amp;ID kopieren
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
</details>

Number of issues: 4.
