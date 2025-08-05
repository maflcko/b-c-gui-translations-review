# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>et</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bet%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Need on sinu Bitcoin aadressid makse vastuvõtuks.Kasuta ‘Loo uus vastuvõttu aadress’ nuppu vastuvõtmise vahekaardis, et luua uus aadress. Allkirjastamine on võimalik ainult 'pärand' tüüpi aadressidega.</translation>
    
YES  
There are spacing issues around punctuation marks, and some phrases can be more naturally phrased in Estonian. Also, the phrase "‘Loo uus vastuvõttu aadress’" contains a typo: "vastuvõttu" should be "vastuvõtu".  

Correct translation:  
Need on sinu Bitcoin'i aadressid maksete vastuvõtuks. Kasuta 'Loo uus vastuvõtu aadress' nuppu vastuvõtmise vahekaardil, et luua uusi aadresse. Allkirjastamine on võimalik ainult 'pärand' tüüpi aadressidega.
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Sisesta rahakotile uus salafraas.&lt;br/&gt;Kasuta salafraasi millles on&lt;b&gt;kümme või rohkem juhuslikku sümbolit&lt;b&gt;,või&lt;b&gt;kaheksa või rohkem sõna&lt;b/&gt;.</translation>
    
YES
The Estonian translation has multiple issues:
- Missing spaces after punctuation and before or after tags (e.g., "&lt;b&gt;" tags are not properly spaced or closed).
- The last &lt;b&gt; tag is not correctly closed ("&lt;b/&gt;" should be "&lt;/b&gt;").
- The phrasing is somewhat awkward and does not match the source precisely.
- The source says "ten or more random characters" and "eight or more words", which should be reflected clearly.
- The translation does not take over the structure correctly, especially around HTML tags.

Corrected translation:
Sisesta rahakoti uus salasõna.&lt;br/&gt;Palun kasuta salasõna, mis sisaldab &lt;b&gt;kümmet või rohkem juhuslikku märki&lt;/b&gt; või &lt;b&gt;kaht või rohkem sõna&lt;/b&gt;.

Note: "salafraas" can also be translated as "salasõna" or "salafraas". "Salasõna" is more common for "passphrase".  
Also, "kaht või rohkem sõna" should be "kaheksa või rohkem sõna" following the source number exactly. So:

Sisesta rahakoti uus salasõna.&lt;br/&gt;Palun kasuta salasõna, mis sisaldab &lt;b&gt;kümmet või rohkem juhuslikku märki&lt;/b&gt; või &lt;b&gt;kaheksat või rohkem sõna&lt;/b&gt;.

Final recommended correction:

Sisesta rahakoti uus salasõna.&lt;br/&gt;Palun kasuta salasõna, mis sisaldab &lt;b&gt;kümmet või rohkem juhuslikku märki&lt;/b&gt; või &lt;b&gt;kaheksat või rohkem sõna&lt;/b&gt;.
```

```
        <source>Your wallet is now encrypted. </source>
        <translation>Rahakott krüpteeritud.</translation>
    
YES  
The translation "Rahakott krüpteeritud." does not include the possessive "Your" ("Sinu" in Estonian) and omits the verb "is now" ("on nüüd"), which are important for preserving the meaning of the source sentence. Also, there is an extra space at the end of the source sentence not carried over (which is fine), but the translation should be a complete sentence in Estonian.

Correct translation:  
Sinu rahakott on nüüd krüpteeritud.
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Omandi tõestamiseks allkirjasta sõnumid oma Bitcoini aadressiga</translation>
    
YES  
The translation contains a typo in "Omandi" which should be "Omandi" → "Omandi" is not incorrect, but the phrase "Omandi tõestamiseks" is a bit awkward in Estonian. A more accurate and idiomatic translation would fully reflect the English meaning: "Sign messages with your Bitcoin addresses to prove you own them." The original phrase does not fully capture the plural possessive aspect ("Bitcoin addresses") nor clearly state "prove you own them" in a natural way.

Correct translation:  
Allkirjasta sõnumid oma Bitcoini aadressidega, et tõestada, et need kuuluvad sulle
```

```
        <source>Close all wallets</source>
        <translation>Sulge rkõik rahakotid</translation>
    
YES  
The translation is problematic because "rkõik" is not a valid Estonian word. The correct word for "all" in Estonian is "kõik". The rest of the translation is correct, as "Sulge kõik rahakotid" means "Close all wallets" in Estonian. Also, there is an unnecessary space after "Sulge".

Correct translation:  
Sulge kõik rahakotid
```

```
        <source>Main Window</source>
        <translation>Pea Aken</translation>
    
YES  
The Estonian translation is incorrect. "Peaaken" (one word) is the correct translation for "Main Window" in the context of a software application.

Correct translation:  
Peaaken
```

```
        <source>Close all wallets</source>
        <translation>Sulge rkõik rahakotid</translation>
    
YES  
The translation is problematic because "rkõik" is not a valid Estonian word. The correct word for "all" in Estonian is "kõik". The rest of the translation is correct, as "Sulge kõik rahakotid" means "Close all wallets" in Estonian. Also, there is an unnecessary space after "Sulge".

Correct translation:  
Sulge kõik rahakotid
```

```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>Proxi port (nt 9050)</translation>
    
YES
The Estonian translation uses "Proxi port", which is a direct borrowing and does not follow typical Estonian word order or spelling. Also, "nt" is an abbreviation for "näiteks" ("for example"), but it is better to use the full form or maintain the parentheses similar to the source for clarity. The English "proxy" is usually translated as "proksü" or "proksi" in Estonian. Also, "port" is commonly left as "port".

Correct translation:
Proksi port (nt 9050)
```

```
        <source>Show only a tray icon after minimizing the window.</source>
        <translation>Minimeeri systray alale.</translation>
    
YES  
The translation mixes Estonian ("Minimeeri") and English ("systray alale"), and "systray alale" is not proper Estonian. The term "systray" should be translated or adapted appropriately, and the phrase should convey "Show only a tray icon after minimizing the window."  

Correct translation:  
"Kuva pärast akna minimeerimist ainult süsteemsalve ikoon."
```

```
        <source>Unit to show amounts in:</source>
        <translation>Summade kuvamise Unit:</translation>
    
YES  
The translation mixes Estonian and English incorrectly. "Unit" should be fully translated or integrated correctly. "Summade kuvamise" means "of amount display," but the phrase is awkward and incomplete without a proper noun or descriptor. The correct Estonian translation should be:

"Ühik summade kuvamiseks:"
```

```
        <source>Insufficient funds!</source>
        <translation>Liiga suur summa</translation>
    
YES  
The Estonian translation "Liiga suur summa" means "Too large amount," which does not correspond to the English source "Insufficient funds!" The correct translation should convey that there are not enough funds available.

Correct translation:  
"Puuduvad vahendid!" or "Kontol pole piisavalt raha!"
```

```
        <source>Debug information</source>
        <translation>Debug'imise info</translation>
    
YES  
The translation "Debug'imise info" uses an incorrect and unnatural form. In Estonian, the English loanword "debug information" would typically be translated as "Silumisinfo" or "Silumise info" without unnecessary apostrophes or anglicized abbreviations.

Correct translation:  
Silumisinfo
```

```
        <source>Insufficient funds</source>
        <translation>Liiga suur summa</translation>
    
YES  
The translation "Liiga suur summa" means "Too large amount" in Estonian, which does not correctly convey the original English phrase "Insufficient funds." The correct translation should indicate a lack of funds.

Correct translation:  
Puuduvad vahendid
```
</details>
