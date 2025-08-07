# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>et</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bet%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Need on sinu Bitcoin aadressid makse vastuvõtuks.Kasuta ‘Loo uus vastuvõttu aadress’ nuppu vastuvõtmise vahekaardis, et luua uus aadress. Allkirjastamine on võimalik ainult 'pärand' tüüpi aadressidega.</translation>
    
YES
There are several issues with this Estonian translation:

1. There is a missing space after the first period: "makse vastuvõtuks.Kasuta" should be "makse vastuvõtuks. Kasuta".
2. The expression "'Create new receiving address'" is inaccurately translated as "Loo uus vastuvõttu aadress"—the correct grammatical form is "Loo uus vastuvõtmise aadress".
3. The word "aaring" (for 'legacy') should be rendered in Estonian as "pärandtüüp" or simply "legacy", not "'pärand' tüüpi".
4. General phrasing and punctuation should be improved for clarity and naturalness.

Correct translation:
Need on sinu Bitcoini aadressid maksete vastuvõtmiseks. Uute aadresside loomiseks kasuta vastuvõtuvahekaardil nuppu „Loo uus vastuvõtuaadress“. Allkirjastamine on võimalik ainult 'legacy' tüüpi aadressidega.
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Sisesta rahakotile uus salafraas.&lt;br/&gt;Kasuta salafraasi millles on&lt;b&gt;kümme või rohkem juhuslikku sümbolit&lt;b&gt;,või&lt;b&gt;kaheksa või rohkem sõna&lt;b/&gt;.</translation>
    
YES
There are several issues:
1. Incorrect HTML tag closure: The `<b>` tags are not properly closed. The opening `<b>` tag before "kümme või rohkem juhuslikku sümbolit" is not terminated (should be `</b>`), and the one before "kaheksa või rohkem sõna" is closed as `<b/>`, which is incorrect.
2. Typo: "millles" should be "milles".
3. Missing space after periods and commas ("või&lt;b&gt;kaheksa" should be "või &lt;b&gt;kaheksa").
4. The instruction for spacing between sentences and after punctuation is not properly followed.
5. The translation for "Please use a passphrase..." is missing "please" ("Palun kasuta...").
6. Minor stylistic improvements for clarity.

Correct translation:
Sisesta rahakotile uus salasõna.&lt;br/&gt;Palun kasuta salasõna, milles on &lt;b&gt;kümme või rohkem juhuslikku sümbolit&lt;/b&gt; või &lt;b&gt;kaheksa või rohkem sõna&lt;/b&gt;.

Note: "salafraas" and "salasõna" are both valid, but "salasõna" (password) is more common in modern Bitcoin/crypto terminology in Estonian; however, "salafraas" is still acceptable in this context. Adjust as necessary per style guide.
```

```
        <source>Your wallet is now encrypted. </source>
        <translation>Rahakott krüpteeritud.</translation>
    
YES
The translation is missing the word "now" ("nüüd") and the verb "on" ("is"), which are important for accurate meaning.

Correct translation:
Teie rahakott on nüüd krüpteeritud.
```

```
        <source>Close all wallets</source>
        <translation>Sulge rkõik rahakotid</translation>
    
YES
There is a typo in the translation: "Sulge rkõik rahakotid" should be "Sulge kõik rahakotid".

Correct translation:
Sulge kõik rahakotid
```

```
        <source>Main Window</source>
        <translation>Pea Aken</translation>
    
YES
The translation is incorrect. "Pea Aken" is not Estonian; "Pea" is not used in this context in Estonian, and "Aken" means "window". The correct translation should be "Peaaken", which is the compound noun for "Main Window" in Estonian (no space).

Correct translation:
Peaaken
```

```
        <source>Close all wallets</source>
        <translation>Sulge rkõik rahakotid</translation>
    
YES
There is a typo in the translation: "Sulge rkõik rahakotid" should be "Sulge kõik rahakotid".

Correct translation:
Sulge kõik rahakotid
```

```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>Proxi port (nt 9050)</translation>
    
YES
There are issues with the translation:
1. "Proxi" should be "Puhverserveri" (the Estonian term for "proxy").
2. The format inside parentheses should use "nt." (abbreviation for "näiteks") instead of "nt".

Correct translation:
Puhverserveri port (nt. 9050)
```

```
        <source>Show only a tray icon after minimizing the window.</source>
        <translation>Minimeeri systray alale.</translation>
    
YES  
The translation is inaccurate and uses a mix of Estonian and a loanword ("systray"), which is not appropriate Standard Estonian usage. It also loses the detail that only a tray icon is shown after minimizing. 

Correct translation:  
Kuva akna minimeerimisel ainult tegumiriba ikoon.
```

```
        <source>Unit to show amounts in:</source>
        <translation>Summade kuvamise Unit:</translation>
    
YES
The Estonian translation is incorrect and awkward. "Unit" is left untranslated, and the word order is unnatural for Estonian. The proper translation should be:

Koguste kuvamise ühik:

Correct translation:
Kuvamise ühik summadele:
```

```
        <source>Insufficient funds!</source>
        <translation>Liiga suur summa</translation>
    
YES
The translation "Liiga suur summa" means "Amount too large" in Estonian, which does not accurately capture the meaning of "Insufficient funds!" The correct translation should convey that there is not enough money/funds.

Correct translation:
Pole piisavalt vahendeid!
```

```
        <source>Debug information</source>
        <translation>Debug'imise info</translation>
    
YES
The translation is understandable but somewhat informal/unnatural. The term "Debug'imise info" uses an inconsistent mix of Estonian and English, and the placement of the apostrophe is not standard. The Estonian word "silumis" is more appropriate for "debug". Also, "teave" or "info" is fine, but "teave" is more formal.

Correct translation:
Silumise teave
```

```
        <source>Insufficient funds</source>
        <translation>Liiga suur summa</translation>
    
YES
The translation is incorrect. "Liiga suur summa" means "Amount too large," which does not accurately convey "Insufficient funds."

Correct translation:
Ebapiisavad vahendid
```
</details>

Number of issues: 12.
