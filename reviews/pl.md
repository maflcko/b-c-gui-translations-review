# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>pl</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bpl%5D%20request)


<!-- cache_translation_check_pl_a03c0f55fc06ac461fcf1fe7a0fe9097121be159e5d4f2de37a3698cd438873a -->
```
        <source>Inbound</source>
        <extracomment>An inbound connection from a peer. An inbound connection is a connection initiated by a peer.</extracomment>
        <translation>Przychodzący</translation>
    
ERR
The form "Przychodzący" is grammatically mismatched for this UI label. The standard label in Polish for "Inbound" (as in connection) is "Przychodzące".

Correct translation:
Przychodzące
```

<!-- cache_translation_check_pl_d836efbd908e5138d209ab28b7a0690b0b436f8cd1e25035b8616e568d36738f -->
```
        <source>Outbound</source>
        <extracomment>An outbound connection to a peer. An outbound connection is a connection initiated by us.</extracomment>
        <translation>Wychodzący</translation>
    
ERR
Grammatical gender mismatch; as a standalone label for a connection, it should be neuter.
Correct translation:
Wychodzące
```

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

<!-- cache_translation_check_pl_9a7b6b6510aeff2bfaa110854cdfeb85ba8f9befc0425afb6842a873786c7738 -->
```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>Wychodzące połączenie testowe: krótkotrwałe, do testowania adresów</translation>
    
ERR
The translation is overly verbose and introduces "wychodzące" (outbound), which is not stated in the source. This label should be concise.
Correct translation:
Sonda
```

<!-- cache_translation_check_pl_a31cc1b1a4058e01e72f0a53a379008923989af4e819c4746c6639097d7cf090 -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Skompilowano bez obsługi zewnętrznego podpisania (wymaganej do zewnętrznego podpisania)</translation>
    
ERR
The Polish translation uses the noun form "podpisania" (signing/the act of having signed), which sounds unnatural in this technical context. In Polish software translation, "podpisywanie" (the ongoing process/feature of signing) is the standard term for "signing" in this context.

Correct translation:
Skompilowano bez obsługi zewnętrznego podpisywania (wymaganego do zewnętrznego podpisywania)
```

<!-- cache_translation_check_pl_a31cc1b1a4058e01e72f0a53a379008923989af4e819c4746c6639097d7cf090 -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Skompilowano bez obsługi zewnętrznego podpisania (wymaganej do zewnętrznego podpisania)</translation>
    
ERR
The Polish translation uses the noun form "podpisania" (signing/the act of having signed), which sounds unnatural in this technical context. In Polish software translation, "podpisywanie" (the ongoing process/feature of signing) is the standard term for "signing" in this context.

Correct translation:
Skompilowano bez obsługi zewnętrznego podpisywania (wymaganego do zewnętrznego podpisywania)
```

<!-- cache_translation_check_pl_707964f18bcef2a0a3f6a31ac40f311461b0d4ce56472f72f51329be65d66200 -->
```
        <source>Inbound</source>
        <extracomment>An Inbound Connection from a Peer.</extracomment>
        <translation>Przychodzący</translation>
    
ERR
The Polish adjective should agree with the implied noun "połączenie" (neuter). "Przychodzący" (masculine) is grammatically off in this context.

Correct translation:
Przychodzące
```

<!-- cache_translation_check_pl_b5272f4e0924567c9db94d5795ab7422227543831d3c7fca0f0317961159d908 -->
```
        <source>Outbound</source>
        <extracomment>An Outbound Connection to a Peer.</extracomment>
        <translation>Wychodzący</translation>
    
ERR
The Polish term should match the common UI label for connection direction. "Wychodzące" is the natural form used for categories like connections or messages. "Wychodzący" sounds like an adjective modifying a masculine noun and is less appropriate as a standalone label.

Correct translation:
Wychodzące
```

<!-- cache_translation_check_pl_fe0929c0872c4efaf9f19ff2af6f1f9cc323a51ebc6403591aa3a9dab5db4d26 -->
```
        <source>Totals</source>
        <translation>Łączna ilość</translation>
    
ERR
"Łączna ilość" is singular and implies "quantity," which is not ideal for a general totals label. A more natural Polish UI label is:
Razem
```

<!-- cache_translation_check_pl_bfa3a06d33b01007b837ad6568182f874ff788c07351d9ccbf7a9ad4e997971e -->
```
        <source>Inbound: initiated by peer</source>
        <extracomment>Explanatory text for an inbound peer connection.</extracomment>
        <translation>Przychodzący: zainicjowane przez węzeł zdalny</translation>
    
ERR
Grammatical agreement is off and the noun is missing; it should specify "połączenie" (connection).
Correct translation:
Połączenie przychodzące: zainicjowane przez węzeł zdalny
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

<!-- cache_translation_check_pl_24b56163fb69849279f7f3cf3178706c9ff4d60d47593cfd7f96fa6c51335cd1 -->
```
        <source>Total credit</source>
        <translation>Uznania ogółem</translation>
    
ERR
The Polish phrasing "Uznania ogółem" is understandable but unnatural in UI/accounting context. A more standard translation is:
Suma uznań
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

<!-- cache_translation_check_pl_5d465186f4c1b9416f4809df08adbbed22e5bfe18d24720fddbe4cad4b1c2f14 -->
```
        <source>Copy &amp;label</source>
        <translation>Kopiuj etykietę</translation>
    
ERR
Missing ampersand for the shortcut key. There must be exactly one '&' in the translation.

Correct translation:
Kopiuj &etykietę
```

<!-- cache_translation_check_pl_2aab17c96a5a3f1e2898aee8ff5002a1e01db1b07aa09c61a24933b72c149d4a -->
```
        <source>Copy &amp;amount</source>
        <translation>Kopiuj kwotę</translation>
    
ERR
The accelerator indicator '&' from the source is missing. It must appear exactly once in the translation.

Correct translation:
Kopiuj &kwotę
```

<!-- cache_translation_check_pl_7a07067d9c0f494e5657d746e06d39f5c68ad35a572aa1f08397064b1c34bd97 -->
```
        <source>Copy transaction &amp;ID</source>
        <translation>transakcjaSkopiuj &amp;ID transakcji</translation>
    
ERR
The translation includes the word "transakcja" prepended to the beginning of the string, which appears to be a duplication or a concatenation error.

Correct translation:
Skopiuj &amp;ID transakcji
```

<!-- cache_translation_check_pl_5dc6865c04ed76a03f04799a0a9a0e4d1beb894d672ae7a3b8c5c0e89eacfa83 -->
```
        <source>Copy &amp;raw transaction</source>
        <translation>Kopiuj &amp;raw transakcje</translation>
    
ERR
The word 'raw' has not been translated into Polish. In the context of Bitcoin, 'raw transaction' is typically translated as 'surową transakcję'.

Correct translation:
Kopiuj &amp;surową transakcję
```

<!-- cache_translation_check_pl_548c189961f358da26b026d09873cf6f232a768e59133f7de47c538e165ca5a4 -->
```
        <source>Increase transaction &amp;fee</source>
        <translation>Zwiększ opłatę transakcji</translation>
    
ERR
Missing accelerator '&' in the Polish translation. It must appear exactly once.

Correct translation:
Zwiększ &opłatę transakcji
```

<!-- cache_translation_check_pl_9de7308b0048e0ec6268cce16032c1f333ee804452ff4a100c890fa6b6f765e5 -->
```
        <source>A&amp;bandon transaction</source>
        <translation>Porzuć transakcję</translation>
    
ERR
Missing ampersand for the shortcut key; it must appear exactly once in the translation.

Correct translation:
&Porzuć transakcję
```

<!-- cache_translation_check_pl_d8b0d3bd9a066a593291836d59aa7cab347fa8b68b024c17dc7e821e0127bdfa -->
```
        <source>&amp;Edit address label</source>
        <translation>Wy&amp;edytuj adres etykiety</translation>
    
ERR
The translation is logically incorrect. "Edit address label" means to edit the label of an address, whereas the Polish translation "Wy&edytuj adres etykiety" means "Edit the address of the label".

Correct translation:
&Edytuj etykietę adresu
```

<!-- cache_translation_check_pl_c266b7c48273891d7b82c3bdbae92f8e028c7e47984c26241e0f4ecafdc1f1c9 -->
```
        <source>Confirmed</source>
        <translation>Potwerdzone</translation>
    
ERR
The Polish word is misspelled. It should be "Potwierdzone".

Correct translation:
Potwierdzone
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

<!-- cache_translation_check_pl_b7086f122e31c4287269e9652a5bd997114885e97430a15a92445208fe92e20b -->
```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>Błąd: rekord identyfikatora pliku zrzutu jest nieprawidłowy. Otrzymano „1%s”, oczekiwano „1%s”.</translation>
    
ERR
The translation contains incorrect format specifiers. The source uses "%s", but the translation contains "1%s", which is likely a typo or an incorrect attempt at positional indexing.

Correct translation:
Błąd: rekord identyfikatora pliku zrzutu jest nieprawidłowy. Otrzymano "%s", oczekiwano "%s".
```

<!-- cache_translation_check_pl_9c6b407b27e68140f8e6f4b08118ca4f3407f3048eaa0b453fbe6016f2d2cb3d -->
```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>Błąd: wersja pliku zrzutu nie jest obsługiwana. Ta wersja bitcoin-wallet obsługuje tylko pliki zrzutów w wersji 1. Mam plik zrzutu w wersji 1%s</translation>
    
ERR
The translation incorrectly adds the digit '1' before the format specifier '%s'. This will result in the software reporting an incorrect version number (e.g., if the version is 2, it would display as "12"). Additionally, "Mam" is a bit too informal/literal for "Got"; "Otrzymano" or "Wczytano" is more appropriate in a technical context.

Correct translation:
Błąd: wersja pliku zrzutu nie jest obsługiwana. Ta wersja bitcoin-wallet obsługuje tylko pliki zrzutu w wersji 1. Otrzymano plik zrzutu w wersji %s
```

<!-- cache_translation_check_pl_7534c8ef38e8fdd4ce63e251985c3bdb9507ea157a2768f2645370daaf21a041 -->
```
        <source>No dump file provided. To use createfromdump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>Nie dostarczono pliku zrzutu. Aby użyć funkcji createfromdump, należy podać -dumpfile=1.</translation>
    
ERR
The translation incorrectly replaces the placeholder/format specifier `<filename>` with the number `1`. In technical documentation or command-line instructions, placeholders should be preserved or translated in a way that indicates a variable, not a literal value.

Correct translation:
Nie dostarczono pliku zrzutu. Aby użyć createfromdump, należy podać -dumpfile=<filename>.
```

<!-- cache_translation_check_pl_e12db3e7150ff3521b36daeed4b3e5382c2be4fd38a35d28f3fecce0877d2a24 -->
```
        <source>No dump file provided. To use dump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>Nie dostarczono pliku zrzutu. Aby użyć funkcji createfromdump, należy podać -dumpfile=1.</translation>
    
ERR
The translation incorrectly translates the command-line argument and introduces a command name not present in the source. Specifically, it changes "-dumpfile=<filename>" to "-dumpfile=1" and adds the word "createfromdump", which alters the meaning of the technical instruction.

Correct translation:
Nie dostarczono pliku zrzutu. Aby użyć zrzutu, należy podać -dumpfile=<filename>.
```

<!-- cache_translation_check_pl_85bf9e3013323b2afc0ad722e4005f8d17ba7de9fe82ac2d2446c4c77f5c3e07 -->
```
        <source>
Unable to restore backup of wallet.</source>
        <translation>Nie można przywrócić kopii zapasowej portfela</translation>
    
ERR
The translation is missing the leading newline and the trailing period present in the source text.

Correct translation:

Nie można przywrócić kopii zapasowej portfela.
```
</details>

Number of issues: 27.
