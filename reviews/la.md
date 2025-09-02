# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>la</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bla%5D%20request)


<!-- cache_translation_check_la_36c6dd0c74e09ebde783fac46264152980e0762f3f96acecaddee12c35cbc687 -->
```
        <source>Right-click to edit address or label</source>
        <translation>Dextro preme ut inscriptionem vel titulum emendes</translation>
    
ERR
The Latin has awkward word order and grammar for an instruction. "Dextro preme" is unnatural (word order and case); "ut ... emendes" is a subjunctive clause that reads odd for a UI imperative. Also "inscriptionem" is acceptable but "inscriptio/inscriptionem" would be clearer.

Suggested correction:
Preme dextram ut inscriptionem vel titulum emendes
```

<!-- cache_translation_check_la_e79ac15d05ee25ab683e7a4e3719f3d81f83b758984242205ef2095d831b7116 -->
```
        <source>Create a new address</source>
        <translation>Novam inscriptionem
 
 
 
 
 
 </translation>
    
ERR
The translation has extraneous blank lines/whitespace after the text and is not an idiomatic/complete UI string for Latin. Also "Novam inscriptionem" alone is just an accusative phrase; a UI command should use an infinitive or imperative.

Correct translation (no extra whitespace):
Crea novam inscriptionem

(Alternative using infinitive form often used in UI contexts:
Creare novam inscriptionem)
```

<!-- cache_translation_check_la_4daa423f828a87c84f31e9e2adc2c492dac79fd335e91c96cfc4a3aa15282dee -->
```
        <source>&amp;Copy</source>
        <translation>&amp;Transcribe</translation>
    
SPAM
The translation "&Transcribe" is English, not Latin, so it does not match the requested language 'la'.

Correct translation (Latin):
&amp;Copia
```

<!-- cache_translation_check_la_7c4bebfe7933b413b3fd15fbbf15d80b2214951698c548d706ea5c778dab43dc -->
```
        <source>Delete the currently selected address from the list</source>
        <translation>Dele active selectam inscriptionem ex enumeratione</translation>
    
ERR
The translation mixes English ("active"), uses incorrect Latin words/forms ("active", "enumeratione") and awkward word order. A clearer Latin rendering:

Delē hanc nunc selectam inscriptionem ex indice.

This keeps the imperative "Delete" (Delē), expresses "currently selected" as "hanc nunc selectam", uses "inscriptio/inscriptionem" for "address", and "ex indice" for "from the list."
```

<!-- cache_translation_check_la_9d6b3930f1cf9fe6b1fcb929b7960bd51314c589215188b7542df65cef037cb0 -->
```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Muta tesseram utam pro cassidilis cifrando</translation>
    
ERR
The Latin translation is problematic. The terms used are not accurate or classical for "change", "passphrase", "wallet", and "encryption". "Muta" is more "move" than "change", "tessera" is a suitable word for "password", but "utam" is ungrammatical, and "cassidilis" is not correct Latin for "wallet". "Cifrando" is an attempt at a modern loan for "encryption", but should be rendered more accurately.

Correct translation:
Mutare tesseram usitatam ad cassidilem cifrandam

Explanation:
- "Mutare" is an accurate infinitive for "change".
- "tesseram" for "passphrase."
- "usitatam" for "used".
- "ad cassidilem cifrandam" for "for encrypting the wallet", using a gerundive construction.
- If "cassidilem" is not attested, "sacculum" may work for "wallet" ("sacculum nummarium" for "coin purse"/wallet). 

Alternative:
Mutare tesseram ad sacculum cifrandum adhibitam

Either is more accurate and grammatical Latin.
```

<!-- cache_translation_check_la_7c792641c0444b36d0ccc90a8f44f89d8bea73675a9eafaca6fd34ca044b5ffd -->
```
        <source>&amp;Send</source>
        <translation>&amp;Mitte</translation>
    
SPAM
The translation is in German ("Mitte" means "send" in German), not Latin ('la'). The Latin verb for "to send" is "Mittere" or "Mitte" for the imperative, but with the ampersand for indicating a shortcut, it would best be rendered as "&Mitte" if following the same paradigm, but Latin is not commonly used for software localization and the usage here reflects a German translation.

Correct translation:
&Mittĕ  (using the Latin imperative with a macron, if Unicode allows; otherwise simply "&Mitte" as a best effort if Latin is intended.)
```

<!-- cache_translation_check_la_c161c51e1fecacd6c5de0eee245631d9ad0e011a3419e3b861ca362d9e6535e3 -->
```
        <source>W&amp;allet</source>
        <translation>Cassidile</translation>
    
ERR
The translation is incorrect and missing the shortcut marker (&). "Cassidile" is not a proper Latin rendering for "Wallet", and the source contains a single & which must be preserved in the translation (exactly once).

Suggested correction (one appropriate Latin option):
&Marsupium

Other valid alternatives:
&Saccus
&Bursa
```

<!-- cache_translation_check_la_563255e8a79ece1bcf915c506e6af75deab3836cec69b8ec6ca81e69d6f12c6e -->
```
        <source>&amp;Display</source>
        <translation>&amp;UI</translation>
    
ERR
The translation "&amp;UI" is problematic because "UI" is an English abbreviation for "User Interface" and not a Latin translation of "Display". The ampersand is correctly present once, but the translated string should reflect the meaning of "Display".

Correct translation:
&amp;Exhibitio
```

<!-- cache_translation_check_la_610f7a1247ef6a3e3649b128ffaa4849f615765f581e2258575c68fb319c78ad -->
```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Selige praedefinitam unitam subdivisionis monstrare in interfacie et quando nummos mittere</translation>
    
ERR
The translation has grammatical errors and awkward phrasing in Latin. "Selige" (imperative for 'choose'), "praedefinitam unitam subdivisionis" (should more accurately mean 'default subdivision unit'), "monstrare" (an infinitive, mismatched with the sentence imperative), and "et quando nummos mittere" (not well-formed).

Correct translation:
Selige praedefinitam unitatem subdivisionis quae in interfacie et ad nummos mittendos ostendatur.
```

<!-- cache_translation_check_la_e7b0805d5b0953f3676dd660e5ca6702c54cb422edaebaebdedb0b9d2e72881e -->
```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Bitcoin incipere non potest: cliccare-ad-pensandum handler</translation>
    
ERR
The translation is problematic. The Latin translation retains the English word "cliccare" (to click) and "handler" unaltered, which are not Latin. Furthermore, "pensandum" is an awkward neologism and the phrase does not conform to Latin norms.

Correct translation:
Bitcoin incipere non potest: curator solutionis per strepitum

Explanation: "curator" is a suitable Latin word for "handler", "solutionis" means "of payment", "per strepitum" (by clicking). If more precision is desired for "click-to-pay", one could use "ad solvendum strepitu" (to pay by click). Optional refinement depending on style.
```
</details>

Number of issues: 10.
