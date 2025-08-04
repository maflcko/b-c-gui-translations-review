# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>et</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bet%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Need on sinu Bitcoin aadressid makse vastuvõtuks.Kasuta ‘Loo uus vastuvõttu aadress’ nuppu vastuvõtmise vahekaardis, et luua uus aadress. Allkirjastamine on võimalik ainult 'pärand' tüüpi aadressidega.</translation>
    
YES - The translation incorrectly uses the word "Need" at the beginning. It should be "These". Also, there is a space before the parenthesis which needs to be removed.
NO Need on sinu Bitcoin aadressid makse vastuvõtuks. Kasuta ‘Loo uus vastuvõttu aadress’ nuppu vastuvõtmise vahekaardis, et luua uus aadress. Allkirjastamine on võimalik ainult 'pärand' tüüpi aadressidega.
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Sisesta rahakotile uus salafraas.&lt;br/&gt;Kasuta salafraasi millles on&lt;b&gt;kümme või rohkem juhuslikku sümbolit&lt;b&gt;,või&lt;b&gt;kaheksa või rohkem sõna&lt;b/&gt;.</translation>
    
YES - The translation incorrectly repeats the closing bold tag `<b>` multiple times. The correct translation should have the closing tags properly paired.
Sisesta rahakotile uus salafraas.&lt;br/&gt;Kasuta salafraasi millles on&lt;b&gt;kümme või rohkem juhuslikku sümbolit&lt;/b&gt;,või&lt;b&gt;kaheksa või rohkem sõna&lt;/b&gt;.
```

```
        <source>Your wallet is now encrypted. </source>
        <translation>Rahakott krüpteeritud.</translation>
    
YES
The translation is missing the verb "is" and the possessive "Your".
Your wallet is now encrypted. -> Teie rahakott on nüüd krüpteeritud.
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Omandi tõestamiseks allkirjasta sõnumid oma Bitcoini aadressiga</translation>
    
YES, the translation is problematic. The Estonian translation uses the singular form "aadressiga" (with the address) when the English source text uses the plural "addresses". It should use the plural form.

NO
```

```
        <source>Close all wallets</source>
        <translation>Sulge rkõik rahakotid</translation>
    
YES, the translation is problematic. The word "rkõik" is not a valid Estonian word. The correct translation should use "kõik".

NO
```

```
        <source>Main Window</source>
        <translation>Pea Aken</translation>
    
YES, The translation is incorrect and nonsensical. The correct translation for "Main Window" in Estonian, in the context of a graphical user interface, is "Peamine aken".

Pea Aken means "Head Window" which is not appropriate for this context.

Peamine aken
```

```
        <source>Close all wallets</source>
        <translation>Sulge rkõik rahakotid</translation>
    
YES, the translation is problematic. The word "rkõik" is not a valid Estonian word. The correct translation should use "kõik".

NO
```

```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>Proxi port (nt 9050)</translation>
    
YES: The translation contains an erroneous character 'nt' before the example port number.
Proxi port (nt 9050)
Correct translation: Proksi port (nt 9050)
```

```
        <source>Show only a tray icon after minimizing the window.</source>
        <translation>Minimeeri systray alale.</translation>
    
YES, the translation is inaccurate and uses an incorrect word. The source text "Show only a tray icon after minimizing the window" means that when the window is minimized, only the tray icon should be visible. The provided translation "Minimeeri systray alale" literally means "Minimize to the systray area", which is a command to minimize to the systray, not a description of what happens after minimizing.

Correct translation: Kuvake vain ilmoitusvalikon kuvake pienentämisen jälkeen.
```

```
        <source>Unit to show amounts in:</source>
        <translation>Summade kuvamise Unit:</translation>
    
YES, The translation is incorrect. The word "Summade" means "Sum" and not "amounts". The correct translation would be "Summa kuvamise Unit".
Summade kuvamise Unit: Summa kuvamise Unit
```

```
        <source>Pending:</source>
        <translation>Ootel:</translation>
    
YES - The translation is incorrect. "Ootel" does not mean "Pending" in Estonian. The correct translation for "Pending" in this context is "Ootel".
        <source>Pending:</source>
        <translation>Ootel:</translation>
```

```
        <source>Address</source>
        <extracomment>Title of Peers Table column which contains the IP/Onion/I2P address of the connected peer.</extracomment>
        <translation>Aadress</translation>
    
YES: The translation has a typographical error. The correct translation for "Address" in Estonian is "Aadress".
Aadress
```

```
        <source>Resulting URI too long, try to reduce the text for label / message.</source>
        <translation>URI liiga pikk, proovi vähendada märke / sõnumi pikkust.</translation>
    
YES - The translation incorrectly uses "märgi" which means "sign" or "symbol" instead of "text" or "content". The correct translation for "text" in this context would be "tekst". Additionally, the phrase "vähendada märke / sõnumi pikkust" is slightly awkward. A more natural phrasing would be "vähendada teksti pikkust märgile / sõnumile" or more simply "vähendada märgise / sõnumi pikkust".

Correct translation: URI liiga pikk, proovi vähendada märgise / sõnumi pikkust.
```

```
        <source>Insufficient funds!</source>
        <translation>Liiga suur summa</translation>
    
YES: The translation is inaccurate and does not convey the intended meaning of "Insufficient funds!". "Liiga suur summa" translates to "Too large amount", which is not the same as not having enough money. The correct translation should indicate a lack of funds.

NO
```

```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>%1 kinnitust</translation>
    
YES, the translation is problematic because it uses an incorrect grammatical form for the word "kinnitus" (confirmation). The correct form for a plural noun following a number is "%1 kinnitust".
NO
```

```
        <source>Debug information</source>
        <translation>Debug'imise info</translation>
    
YES - The translation uses an apostrophe in a way that is not grammatically correct in English. The correct translation should be "Debugi teave".
Debugi teave
```

```
        <source>Insufficient funds</source>
        <translation>Liiga suur summa</translation>
    
YES, The Estonian translation "Liiga suur summa" translates to "Too large an amount" which is not an accurate translation of "Insufficient funds". The correct translation should convey that there are not enough funds.
The correct translation is: "Ebapiisavad vahendid".
```
</details>
