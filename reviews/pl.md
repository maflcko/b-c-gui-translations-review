# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bpl%5D%20request)



<details><summary>pl</summary>


<!-- cache_translation_check_pl_2c397a05411f587aa9d9f03962bb1b9da6ce4645833c16747a5f8a1b6a29d729 -->
```
        <source>Manual</source>
        <extracomment>Peer connection type established manually through one of several methods.</extracomment>
        <translation>Ręczne</translation>
    
ERR
The grammatical form is incorrect for "type" (typ), which is masculine; it should be "Ręczny", not "Ręczne".

Correct translation:
Ręczny
```

<!-- cache_translation_check_pl_c262f14104c68dcc0674cfbff14f9f146236c60b96b96171618c93282bdd2e6b -->
```
        <source>S&amp;end</source>
        <translation>Wy&amp;syłka</translation>
    
ERR
"Wysyłka" is a noun and sounds unnatural for a button/menu command; the imperative "Wyślij" is preferred. Keep exactly one accelerator.
Correct translation:
&Wyślij
```

<!-- cache_translation_check_pl_c9b0d7be83a1973305a1a0a8301d39b7d169fa439c4df5c2acee90e78a568cbf -->
```
        <source>&amp;Copy address</source>
        <translation>Kopiuj adres</translation>
    
ERR
Missing shortcut marker '&' in the translation.

Correct translation:
&Kopiuj adres
```

<!-- cache_translation_check_pl_aa28f649bb1a3bb2d63da0edcfdac2a294bbe20caefbb68c101f38b46a726849 -->
```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>Błąd: rekord formatu pliku zrzutu jest nieprawidłowy. Otrzymano „1%s”, oczekiwany „format”.</translation>
    
ERR
The translation contains a typo in the format specifier. The source uses "%s", but the translation contains "1%s", which adds an erroneous '1' before the placeholder. Additionally, the word "oczekiwany" should be "oczekiwano" or "oczekiwany: " to match the sentence structure.

Correct translation:
Błąd: rekord formatu pliku zrzutu jest nieprawidłowy. Otrzymano „%s”, oczekiwano „format”.
```
</details>

Number of issues: 4.
