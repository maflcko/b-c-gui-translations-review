# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>sq</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bsq%5D%20request)


<!-- cache_translation_check_sq_6dfda18e74bb22642c82f27fe9287c1569df19c57b4567433a830d88d7af90f5 -->
```
        <source>C&amp;lose</source>
        <translation>afër</translation>
    
ERR
The translation "afër" means "near" or "close (in proximity)" in Albanian, but the context here is a UI command meaning "Close" (as in "close the window"). Also, the shortcut indicator (&) is missing in the translation.

Correct translation:
&Mbyll
```

<!-- cache_translation_check_sq_215d8a1c12ff640adfdadb8b2cfdc2f7d5a20aa890db16ad75a5e866358b7e6f -->
```
        <source>Wallet encryption failed due to an internal error. Your wallet was not encrypted.</source>
        <translation>Enkriptimi i portofolit dështoi për shkak të një gabimi të brëndshëm. portofoli juaj nuk u enkriptua.</translation>
    
ERR
There is a minor spelling error: "brëndshëm" should be "brendshëm". Also, the sentence capitalization should be consistent; "portofoli juaj" should start with a capital letter.

Correct translation:
Enkriptimi i portofolit dështoi për shkak të një gabimi të brendshëm. Portofoli juaj nuk u enkriptua.
```

<!-- cache_translation_check_sq_fa07aa5b4a2707013b2936608ce157ebaaabe2af858081c5a6d1435d17f8e660 -->
```
        <source>Tabs toolbar</source>
        <translation>Shiriti i mjeteve</translation>
    
ERR
The translation omits the word "Tabs" ("Skedat" in Albanian), so it only means "Toolbar", not "Tabs toolbar".

Correct translation:
Shiriti i skedave
```

<!-- cache_translation_check_sq_35da138b5c022a40d00e9611ba3b3306326befc108b46018d9c88e2777caa5a1 -->
```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Portofoli po &lt;b&gt; enkriptohet&lt;/b&gt; dhe është &lt;b&gt; i ç'kyçur&lt;/b&gt;</translation>
    
ERR
The translation is inaccurate. The English "Wallet is encrypted and currently unlocked" means that the wallet, which is already encrypted, is now unlocked (open for use). The Albanian translation given conveys that "the wallet is being encrypted and is unlocked," which is incorrect.

Correct translation:
Portofoli është &lt;b&gt; i enkriptuar&lt;/b&gt; dhe aktualisht &lt;b&gt; i ç'kyçur&lt;/b&gt;
```

<!-- cache_translation_check_sq_ee38efdb31a8b759b11eca3d84ecf095a3c0048005377e79736abc993b024534 -->
```
        <source>W&amp;allet</source>
        <translation>Portofol</translation>
    
ERR
The translation omits the '&' (ampersand) that is present in the source string and should be included to indicate the keyboard shortcut. It should appear exactly once in the translation, as in the source.

Correct translation:
&Portofol
Alternatively, "Portofol&" is also acceptable if the shortcut is to be on another character, but including '&' somewhere is required.
```

<!-- cache_translation_check_sq_f640ba1e3b6a1ffd2931b64bde3c37e066c50cdb88ac215a8551284f5813bc12 -->
```
        <source>&amp;Information</source>
        <translation>Informacion</translation>
    
ERR
The translation omits the '&' symbol which is used to denote a keyboard shortcut. It should be preserved in the translation, appearing exactly once.

Correct translation:
&Informacion
or
Informacion&

(both are acceptable as long as the '&' is present exactly once)
```

<!-- cache_translation_check_sq_37c4dc5635e7db0950a665aeb831b4f2cfc96d0e938e1e7db5bdb4405552949d -->
```
        <source>&amp;Amount:</source>
        <translation>Shuma:</translation>
    
ERR
The ampersand "&" (used for keyboard shortcut hints) is missing in the Albanian translation. It should appear once (usually before the shortcut letter).

Correct translation:
&Shuma:
```

<!-- cache_translation_check_sq_8b9679a919e9f04a3329b69f8eb06f5f46bb76bfe6166584cdee76932d9f132f -->
```
        <source>Paste address from clipboard</source>
        <translation>Ngjit nga memorja e sistemit</translation>
    
ERR
The translation omits the word "address" ("adresë" in Albanian), which changes the meaning. The correct translation should specify that an address is being pasted, not just anything from the clipboard.

Correct translation:
Ngjit adresën nga memorja e sistemit
```

<!-- cache_translation_check_sq_8b9679a919e9f04a3329b69f8eb06f5f46bb76bfe6166584cdee76932d9f132f -->
```
        <source>Paste address from clipboard</source>
        <translation>Ngjit nga memorja e sistemit</translation>
    
ERR
The translation omits the word "address" ("adresë" in Albanian), which changes the meaning. The correct translation should specify that an address is being pasted, not just anything from the clipboard.

Correct translation:
Ngjit adresën nga memorja e sistemit
```

<!-- cache_translation_check_sq_787a83b49ef3ac375aeebfdef2cf54d6aa6c94208abd2ff4f3f62072add5dfd9 -->
```
        <source>Confirmed (%1 confirmations)</source>
        <translation>I/E konfirmuar(%1 konfirmime)</translation>
    
ERR
There is a formatting issue: missing space after the slash and before the parenthesis. The correct translation should also be consistent with the term "Confirmed". In Albanian, "I/E konfirmuar" is acceptable for gender neutrality, but the slash should have a space on both sides, and there should be a space before the parenthesis.

Correct translation:
I/E konfirmuar (%1 konfirmime)
```
</details>

Number of issues: 10.
