# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zu</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzu%5D%20low%20quality)


```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>Sekwenzeke iphutha ngaphakathi. %1kuzozama ukuqhubeka ngokuphepha. Leli iphutha ebelingalindelekanga elingabikwa njengoba kuchaziwe ngezansi.</translation>
    
YES, The translation is problematic because the format specifier '%1' is not correctly transferred. It is displayed as '%1kuzozama' in the translated text.

NO, Sekwenzeke iphutha ngaphakathi. %1 izozama ukuqhubeka ngokuphepha. Leli iphutha ebelingalindelekanga elingabikwa njengoba kuchaziwe ngezansi.
```

```
        <source>%1 didn't yet exit safely…</source>
        <translation>%1Ingakatholakali ngokuphepha okwamanje.</translation>
    
YES, The translation is problematic because it does not capture the meaning of the original English sentence. It translates to "%1 has not been found safely yet." which does not make sense in the context of Bitcoin. The correct translation should be "%1 hasn't exited safely yet..."

%1 ayikaphelelwa ngokuphepha okwamanje...
```

```
        <source>Sign message…</source>
        <translation>Sayina umlayezo...</translation>
    
YES, the translation is problematic. The word "sayina" is not a standard Zulu word for "sign" in this context.

Correct translation:
YES, Sign message…
```

```
        <source>Close Wallet…</source>
        <translation>Vala isikhwama semali.</translation>
    
YES, The translation is problematic. The Zulu word "Vala" means "Close" or "Shut", but it is not the correct verb to use for closing a wallet. The word "isikhwama semali" correctly translates to "wallet". A more appropriate translation for "Close Wallet" would be "Vula isikhwama semali" which means "Open wallet" or "Phuma kusikhwama semali" which means "Exit wallet".

The correct translation is:
<translation>Phuma kusikhwama semali.</translation>
```

```
        <source>Click for more actions.</source>
        <extracomment>A substring of the tooltip. "More actions" are available via the context menu.</extracomment>
        <translation>Chofa ukuveza ezinye izenzo.</translation>
    
YES, The translation is not accurate. The phrase "Chofa ukuveza ezinye izenzo" translates to "Click to reveal other actions" which is a literal translation of the source text and doesn't fit the context of Bitcoin. In Bitcoin, "actions" in this context might refer to specific operations or commands related to a Bitcoin address or transaction, not general "actions" in the broader sense.

A more appropriate translation would be:
"Cofa ukuze ubone ezinye izinto zokwenziwa."
```

```
        <source>Peer</source>
        <extracomment>Title of Peers Table column which contains a unique number used to identify a connection.</extracomment>
        <translation>Untanga</translation>
    
YES
The translation "Untanga" is incorrect and does not convey the meaning of "Peer" in the context of Bitcoin. "Peer" in this context refers to another node or participant in the Bitcoin network. The provided translation is likely a mistranslation or nonsensical word in the target language.

Correct translation: **Oruganji**
```

```
        <source>Error: Missing checksum</source>
        <translation>Iphutha: iChecksum engekho</translation>
    
YES: The translation uses "iChecksum" which is a direct transliteration of the English word "checksum". While understandable, it would be more appropriate to translate "checksum" into a more natural isiZulu term.

Correct translation: "Iphutha: ukuhlolwa okungekho"
```
</details>
