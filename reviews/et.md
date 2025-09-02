# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>et</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bet%5D%20request)


<!-- cache_translation_check_et_8717e7a8c54b127d2b5423130e396c377ffebf1190b6caf10d8df53934738c5c -->
```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Need on sinu Bitcoin aadressid makse vastuvõtuks.Kasuta ‘Loo uus vastuvõttu aadress’ nuppu vastuvõtmise vahekaardis, et luua uus aadress. Allkirjastamine on võimalik ainult 'pärand' tüüpi aadressidega.</translation>
    
ERR
There are several issues with this Estonian translation:

1. There is a missing space after the first period: "makse vastuvõtuks.Kasuta" should be "makse vastuvõtuks. Kasuta".
2. The expression "'Create new receiving address'" is inaccurately translated as "Loo uus vastuvõttu aadress"—the correct grammatical form is "Loo uus vastuvõtmise aadress".
3. The word "aaring" (for 'legacy') should be rendered in Estonian as "pärandtüüp" or simply "legacy", not "'pärand' tüüpi".
4. General phrasing and punctuation should be improved for clarity and naturalness.

Correct translation:
Need on sinu Bitcoini aadressid maksete vastuvõtmiseks. Uute aadresside loomiseks kasuta vastuvõtuvahekaardil nuppu „Loo uus vastuvõtuaadress“. Allkirjastamine on võimalik ainult 'legacy' tüüpi aadressidega.
```

<!-- cache_translation_check_et_300566cb65e809e0d8bf14edc4ba1a24dc7970a6481b9f5ef4026a3f7a02aae0 -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Sisesta rahakotile uus salafraas.&lt;br/&gt;Kasuta salafraasi millles on&lt;b&gt;kümme või rohkem juhuslikku sümbolit&lt;b&gt;,või&lt;b&gt;kaheksa või rohkem sõna&lt;b/&gt;.</translation>
    
ERR
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

<!-- cache_translation_check_et_4a0c379366d7696fded7f5ebf59fad222e8a0fa54776b7cf015b36a3565431fa -->
```
        <source>Your wallet is now encrypted. </source>
        <translation>Rahakott krüpteeritud.</translation>
    
ERR
The translation is missing the word "now" ("nüüd") and the verb "on" ("is"), which are important for accurate meaning.

Correct translation:
Teie rahakott on nüüd krüpteeritud.
```

<!-- cache_translation_check_et_5b728c44f9fa26cc69e36c5249cbc2846a09c77634d342b5c7eea80bf1f88779 -->
```
        <source>Main Window</source>
        <translation>Pea Aken</translation>
    
ERR
The translation is incorrect. "Pea Aken" is not Estonian; "Pea" is not used in this context in Estonian, and "Aken" means "window". The correct translation should be "Peaaken", which is the compound noun for "Main Window" in Estonian (no space).

Correct translation:
Peaaken
```

<!-- cache_translation_check_et_9b979711f9a3319b2a4f2527f8b3719fce127a9df1442a9e3264a3812331384d -->
```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>Proxi port (nt 9050)</translation>
    
ERR
There are issues with the translation:
1. "Proxi" should be "Puhverserveri" (the Estonian term for "proxy").
2. The format inside parentheses should use "nt." (abbreviation for "näiteks") instead of "nt".

Correct translation:
Puhverserveri port (nt. 9050)
```

<!-- cache_translation_check_et_3037d6818376045847842f618e7166e973c476128eb8e63bf7435a8a1a5a8b3b -->
```
        <source>Show only a tray icon after minimizing the window.</source>
        <translation>Minimeeri systray alale.</translation>
    
ERR  
The translation is inaccurate and uses a mix of Estonian and a loanword ("systray"), which is not appropriate Standard Estonian usage. It also loses the detail that only a tray icon is shown after minimizing. 

Correct translation:  
Kuva akna minimeerimisel ainult tegumiriba ikoon.
```

<!-- cache_translation_check_et_a6ad2f748cd7e14bc1a41609d5305b35e24f4f3d9ba5c6eb1cd5abb25eb941b2 -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>&amp;Minimeeri systray alale</translation>
    
ERR
The Estonian translation introduces an English loanword "systray" and uses "alale" incorrectly. The standard Estonian terminology would be "süsteemisalv" for "system tray", and the translation should preserve the meaning and shortcut key (&).

Correct translation:
&Minimeeri tegumiriba asemel süsteemisalve
```

<!-- cache_translation_check_et_859722661b0cde1188b7d69efc58554b18266cb805a9fb0fd041da56d286ad6c -->
```
        <source>&amp;Unit to show amounts in:</source>
        <translation>Summade kuvamise &amp;Unit:</translation>
    
ERR
The translation incorrectly includes the English word "Unit" instead of translating it. The correct Estonian translation would also rephrase for clarity and maintain the placement of "&" for the shortcut key.

Correct translation:
&amp;Ühik, milles summasid kuvada:
```

<!-- cache_translation_check_et_839ccc46e48fde7cff7d6c50086ff08c1598c8f42cbf322639add39d688c10dd -->
```
        <source>Insufficient funds!</source>
        <translation>Liiga suur summa</translation>
    
ERR
The translation "Liiga suur summa" means "Amount too large" in Estonian, which does not accurately capture the meaning of "Insufficient funds!" The correct translation should convey that there is not enough money/funds.

Correct translation:
Pole piisavalt vahendeid!
```

<!-- cache_translation_check_et_fdef3883ccf8dad248dfe38081c8723dfadad073de6f78f09c0d958d9ad33558 -->
```
        <source>S&amp;end</source>
        <translation>S&amp;aada</translation>
    
ERR
The translation "Saada" is correct Estonian for "Send", and the shortcut key (&) is preserved. However, it is placed in the wrong position: it should be "S&aa" to match the shortcut placement in English (on the 'e'). The current translation sets the shortcut on 'a' instead.

Correct translation:
S&aa

OR

Depending on Estonian conventions, if "Saada" is already well-understood with its shortcut key on 'a', it may be acceptable, but the aim is to align shortcut placement if possible. Thus, prefer:

S&aa
```

<!-- cache_translation_check_et_095f3708a9b75727ae469164d9f7de797cae5f8272467462b71eca38f944b350 -->
```
        <source>Pay &amp;To:</source>
        <translation>Maksa &amp;:</translation>
    
ERR
The translation omits the word "To" ("Saaja" or "Aadressile" in Estonian), making the meaning incomplete.

Correct translation:
Maksa &amp;saajale:
```

<!-- cache_translation_check_et_847573815dfafebe42012cf3042905a4e174c6c55c453d5af605adcb53dccddd -->
```
        <source>&amp;Sign Message</source>
        <translation>&amp;Allkirjastamise teade</translation>
    
ERR
The translation is inaccurate. The English source means "Sign Message" (for example, as a button label to sign a message cryptographically). The Estonian translation given, "&Allkirjastamise teade," translates back as "Message of signing" or "Signing message" (noun phrase) rather than the verb command/invitation.

Correct translation:
"&Allkirjasta sõnum"
```

<!-- cache_translation_check_et_84d39d2108137bc602bc1350074d7c453e697b9030c6ca55aab202a929d62c6e -->
```
        <source>Debug information</source>
        <translation>Debug'imise info</translation>
    
ERR
The translation is understandable but somewhat informal/unnatural. The term "Debug'imise info" uses an inconsistent mix of Estonian and English, and the placement of the apostrophe is not standard. The Estonian word "silumis" is more appropriate for "debug". Also, "teave" or "info" is fine, but "teave" is more formal.

Correct translation:
Silumise teave
```

<!-- cache_translation_check_et_67743b19113518c45cd04b663f80cff0642d14bc049d8a7c40a71227c0bb2e92 -->
```
        <source>Insufficient funds</source>
        <translation>Liiga suur summa</translation>
    
ERR
The translation is incorrect. "Liiga suur summa" means "Amount too large," which does not accurately convey "Insufficient funds."

Correct translation:
Ebapiisavad vahendid
```
</details>

Number of issues: 14.
