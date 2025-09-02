# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>pl</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bpl%5D%20request)


<!-- cache_translation_check_pl_d3639efde246a57548bc63f0bdd3945990f6815603292f51f7e5dcb98d83f73b -->
```
        <source>Right-click to edit address or label</source>
        <translation>Kliknij prawy przycisk myszy, aby edytować adres lub etykietę</translation>
    
ERR
The Polish phrasing is understandable but slightly ungrammatical. Use the instrumental case for the mouse button.

Correct translation:
Kliknij prawym przyciskiem myszy, aby edytować adres lub etykietę
```

<!-- cache_translation_check_pl_9a7b6b6510aeff2bfaa110854cdfeb85ba8f9befc0425afb6842a873786c7738 -->
```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>Wychodzące połączenie testowe: krótkotrwałe, do testowania adresów</translation>
    
ERR
The source is a short label ("Feeler"). The Polish translation is a long descriptive phrase with a colon ("Wychodzące połączenie testowe: krótkotrwałe, do testowania adresów"), which is inconsistent with the brevity of the source and may not fit UI label contexts.

Suggested concise translations:
- Połączenie testowe
or, if keeping the original term:
- Połączenie typu „feeler”
```

<!-- cache_translation_check_pl_d2b7642de902be63ffe1c85cba4f3abb86e526cbb9fcef0b95a90b35c8e03320 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>Utwórz kopię zapasową portfela…</translation>
    
ERR
The translation is correct Polish but it is missing the keyboard shortcut marker (&) that exists in the source. There are no format specifiers to check and no whitespace issues.

Correct translation (with & included). You can place & before an appropriate letter (commonly the first word) — for example:

&Utwórz kopię zapasową portfela…

Or an alternative shorter label:

&Kopia zapasowa portfela…
```

<!-- cache_translation_check_pl_d2ed0b5228ae324983b3c8633de6663a18f60b18e5ce32915565c1fc3e5a0829 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>Wczytaj PSBT ze schowka…</translation>
    
ERR
The translation is missing the shortcut marker "&" (it must appear exactly once like in the source). Also ensure the ellipsis character is preserved.

Correct translation:
Wczytaj PSBT ze &schowka…
```

<!-- cache_translation_check_pl_c83e151e8a2dc3a758f85728275dce53b5c87c363813e58d2b06f7e18fa14023 -->
```
        <source>(un)select all</source>
        <translation>zaznacz/odznacz wszytsko</translation>
    
ERR
The Polish translation has a typo: "wszytsko" should be "wszystko".

Correct translation:
zaznacz/odznacz wszystko
```

<!-- cache_translation_check_pl_c266b7c48273891d7b82c3bdbae92f8e028c7e47984c26241e0f4ecafdc1f1c9 -->
```
        <source>Confirmed</source>
        <translation>Potwerdzone</translation>
    
ERR
The Polish word is misspelled. "Potwerdzone" is incorrect.

Correct translation:
Potwierdzone
```

<!-- cache_translation_check_pl_757afc81564ce8db7f7c5b0a81278ddab66a74958e0f9b0af4d96fbd310e5d05 -->
```
        <source>Copy amount</source>
        <translation>Kopiuj kwote</translation>
    
ERR
Polish spelling error: "kwote" is missing the diacritic. Correct translation:
Kopiuj kwotę
```

<!-- cache_translation_check_pl_c9b0d7be83a1973305a1a0a8301d39b7d169fa439c4df5c2acee90e78a568cbf -->
```
        <source>&amp;Copy address</source>
        <translation>Kopiuj adres</translation>
    
ERR
The translation is missing the shortcut marker (&) present in the source. The source has a single '&' indicating a keyboard mnemonic and the translation must include exactly one '&'.

Correct translation:
&Kopiuj adres
```

<!-- cache_translation_check_pl_5d465186f4c1b9416f4809df08adbbed22e5bfe18d24720fddbe4cad4b1c2f14 -->
```
        <source>Copy &amp;label</source>
        <translation>Kopiuj etykietę</translation>
    
ERR
The translation is missing the shortcut marker (&) that appears in the source ("Copy &label"). The ampersand must appear exactly once in the translation to indicate the mnemonic.

Correct translation:
Kopiuj &etykietę
```

<!-- cache_translation_check_pl_2aab17c96a5a3f1e2898aee8ff5002a1e01db1b07aa09c61a24933b72c149d4a -->
```
        <source>Copy &amp;amount</source>
        <translation>Kopiuj kwotę</translation>
    
ERR
The translation omits the shortcut marker '&' present in the source. The source uses "Copy &amp;amount" (one '&' before "amount"); the translation should include a single '&' to mark the mnemonic.

Correct translation:
Kopiuj &kwotę
```

<!-- cache_translation_check_pl_92fd13b1ebf240dad7cf13642f985b03145e67053c4fa157a236416688afc458 -->
```
        <source>Copy bytes</source>
        <translation>Skopiuj ilość bajtów</translation>
    
ERR
The Polish translation "Skopiuj ilość bajtów" reads as "Copy the number/amount of bytes", which changes the meaning (it implies copying the count rather than the bytes themselves). No format specifiers or spacing issues.

Correct translation:
Skopiuj bajty
```

<!-- cache_translation_check_pl_3c1b7477465e517aa29b8945d31a10706d4adaaaaf0f96028e2e318eadefdbd9 -->
```
        <source>Are you sure you wish to close all wallets?</source>
        <translation>Na pewno zamknąć wszystkie portfele?</translation>
    
ERR
The translation is understandable but lacks the proper Polish structure and politeness marker often expected in confirmations. The direct translation "Na pewno zamknąć wszystkie portfele?" sounds clipped; it is better to use a more formal and natural structure.

Correct translation:
Czy na pewno chcesz zamknąć wszystkie portfele?
```

<!-- cache_translation_check_pl_b454ed03f79eb3c9200a984e656fa5f93280391a850d17739b165f19cb2026a8 -->
```
        <source>Signed transaction successfully. Transaction is ready to broadcast.</source>
        <translation>transakcja</translation>
    
ERR
The Polish translation is incorrect and incomplete ("transakcja" = "transaction" only). It does not convey the source meaning.

Correct translation:
Transakcja została pomyślnie podpisana. Jest gotowa do wysłania.
```

<!-- cache_translation_check_pl_ef515d4ebaafcb94544472786cf6bcef772c952f88a4f382d485067eefaccf72 -->
```
        <source>S&amp;ubtract fee from amount</source>
        <translation>Odejmij opłatę od kwoty</translation>
    
ERR
Missing shortcut marker '&' in the translation. The source has "S&amp;ubtract..." indicating a single '&' must appear in the translation as well.

Correct translation:
&Odejmij opłatę od kwoty
```

<!-- cache_translation_check_pl_f431407ec4e4cd6eb0e90547b4936b462f80c82023fc95829dd3a1812278ef84 -->
```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Wpisz adres, wiadomość oraz sygnaturę (podpis) odbiorcy (upewnij się, że dokładnie skopiujesz wszystkie zakończenia linii, spacje, tabulacje itp.). Uważaj by nie dodać więcej do podpisu niż do samej podpisywanej wiadomości by uniknąć ataku man-in-the-middle. 
Zwróć uwagę, że poprawnie zweryfikowana wiadomość potwierdza to, że nadawca posiada klucz do adresu, natomiast nie potwierdza to, że poprawne wysłanie jakiejkolwiek transakcji!</translation>
    
ERR
The translation is mostly understandable but has stylistic and clarity issues, an unnecessary line break, and slightly awkward phrasing that could change nuance (e.g., "nie dodać więcej do podpisu" and "poprawne wysłanie jakiejkolwiek transakcji"). Also remove the stray newline so it stays one paragraph.

Suggested correct translation:
Wpisz poniżej adres odbiorcy, wiadomość (upewnij się, że dokładnie skopiujesz wszystkie znaki końca linii, spacje, tabulatory itp.) oraz sygnaturę, aby zweryfikować wiadomość. Uważaj, aby nie przypisywać podpisowi więcej niż zawiera podpisana wiadomość, aby nie paść ofiarą ataku typu man-in-the-middle. Zauważ, że to jedynie potwierdza, iż strona podpisująca kontroluje dany adres; nie dowodzi, że wysłała jakąkolwiek transakcję!
```

<!-- cache_translation_check_pl_a302e810cf03a27895ee29f99ca40c1426af5f5012630d36712c27c08d3d2f16 -->
```
        <source>Copy &amp;raw transaction</source>
        <translation>Kopiuj &amp;raw transakcję</translation>
    
ERR
The translation mixes English and Polish ("raw transakcję") and uses incorrect word order/inflection. In Polish it should use "surową transakcję" (or keep "raw" fully in English consistently). The ampersand (&) is present exactly once — that's fine — but it should be placed in the translated label.

Correct translation:
Kopiuj &surową transakcję

(Or, if you prefer to keep "raw" in English:
Kopiuj &raw transakcję — though this is less natural in Polish.)
```

<!-- cache_translation_check_pl_aa42a489fc30774dea27a1d4cb729d80fe2fd4ee4c7a480bf96bf0c3486f8534 -->
```
        <source>&amp;Edit address label</source>
        <translation>Wy&amp;edytuj etykietę adresu</translation>
    
ERR
"Wyedytuj" is uncommon/unnatural in Polish here; the usual imperative is "Edytuj etykietę adresu". Also ensure the shortcut marker (&) is present once. 

Correct translation:
&Edytuj etykietę adresu
```

<!-- cache_translation_check_pl_c266b7c48273891d7b82c3bdbae92f8e028c7e47984c26241e0f4ecafdc1f1c9 -->
```
        <source>Confirmed</source>
        <translation>Potwerdzone</translation>
    
ERR
The Polish word is misspelled. "Potwerdzone" is incorrect.

Correct translation:
Potwierdzone
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

<!-- cache_translation_check_pl_49af3b53b5603f8086dfa87cbe689124ecdf8fba6da77ca453d683a4232c971c -->
```
        <source>Option '-maxorphantx' is set but no longer has any effect (see release notes). Please remove it from your configuration.</source>
        <translation>Opcja "-maxorphantx" jest zaznaczona, ale nie ma już żadnych efektów (zobacz informacje o wydaniu). Prosimy o usunięcie jej z twojej konfiguracji.</translation>
    
ERR
The Polish is understandable but has minor stylistic/grammatical issues: "jest zaznaczona" is better as "jest ustawiona", "nie ma już żadnych efektów" should be singular ("żadnego efektu") or better "nie ma już żadnego wpływu/znaczenia", and "informacje o wydaniu" is less natural than "uwagi do wydania" or "notatki do wydania". Also the final sentence can be phrased more naturally.

Suggested correction:
Opcja "-maxorphantx" jest ustawiona, ale nie ma już żadnego efektu (zobacz uwagi do wydania). Usuń ją ze swojej konfiguracji.
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

Number of issues: 22.
