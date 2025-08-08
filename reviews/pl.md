# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>pl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bpl%5D%20low%20quality)


<!-- cache_translation_check_pl_3c1b7477465e517aa29b8945d31a10706d4adaaaaf0f96028e2e318eadefdbd9 -->
```
        <source>Are you sure you wish to close all wallets?</source>
        <translation>Na pewno zamknąć wszystkie portfele?</translation>
    
ERR
The translation is understandable but lacks the proper Polish structure and politeness marker often expected in confirmations. The direct translation "Na pewno zamknąć wszystkie portfele?" sounds clipped; it is better to use a more formal and natural structure.

Correct translation:
Czy na pewno chcesz zamknąć wszystkie portfele?
```

<!-- cache_translation_check_pl_472eea97cf769785e7ff71e8f95562fd75cb42ac8cea3eacfa8d74ea16aeb80a -->
```
        <source>Error: Unable to produce descriptors for this legacy wallet. Make sure to provide the wallet's passphrase if it is encrypted.</source>
        <translation>Błąd: Nie można wygenerować deskryptorów dla tego starego portfela. Upewnij się najpierw, że portfel jest zaszyfrowany.</translation>
    
ERR
The translation is problematic. It mistranslates the instruction: in the source, the user is told to "make sure to provide the wallet's passphrase if it is encrypted," but in the translation, it says "Upewnij się najpierw, że portfel jest zaszyfrowany," which means "Make sure first that the wallet is encrypted," which is not the same.

Correct translation:
Błąd: Nie można wygenerować deskryptorów dla tego starego portfela. Jeśli portfel jest zaszyfrowany, upewnij się, że podano hasło do portfela.
```

<!-- cache_translation_check_pl_4ed0dbfb6d8c520d4cc9a1ae40117489eff79ad2071a2fa5f898b85b30e094c1 -->
```
        <source>Error: Got key that was not hex: %s</source>
        <translation>Błąd: Otrzymano klucz, który nie jest szestnastkowy %s</translation>
    
ERR
There is a typographical error in the Polish word for "hexadecimal". It should be "szesnastkowy", not "szestnastkowy". Additionally, a colon or separator before the format specifier %s would improve clarity.

Correct translation:
Błąd: Otrzymano klucz, który nie jest szesnastkowy: %s
```

<!-- cache_translation_check_pl_09126b35292a24ad9da18ad86ce2de6d9036abae4d5abecc2bfab04c665d349f -->
```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Błąd: Otrzymano wartość, która nie jest szestnastkowa %s</translation>
    
ERR
There is a typographical error in the translation: "szestnastkowa" should be "szesnastkowa". Also, there should be a comma before the "%s" to better match the structure of the original sentence. A corrected translation is:

Błąd: Otrzymano wartość, która nie jest szesnastkowa: %s
```
</details>

Number of issues: 4.
