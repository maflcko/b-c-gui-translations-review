# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Baz@latin%5D%20request)



<details><summary>az@latin</summary>


<!-- cache_translation_check_az@latin_c713146aaa10d6b6cff8ca2611acc059e9017d626ab316f35d4323644c849bb1 -->
```
        <source>C&amp;lose</source>
        <translation>Bağla</translation>
    
ERR
The translation omits the '&' character, which in the source marks a keyboard shortcut (Alt+letter). It should appear exactly once in the translation as well, anywhere appropriate within "Bağla".

Correct translation:
&Bağla
or
Bağ&la
(both are acceptable if the shortcut does not conflict with others)
```

<!-- cache_translation_check_az@latin_42b12ab4470a52e925fcced76dca24c8640a51c07f1ad19f421bdb56a7d8b91d -->
```
        <source>Copy &amp;Label</source>
        <translation>Etiketi kopyala</translation>
    
ERR
The translation omits the shortcut marker "&" from the original text. In interface strings, "&" should appear exactly once to indicate the keyboard shortcut.

Correct translation:
&Etiketi kopyala
or
Etiketi &kopyala
(Note: Placing "&" before "E" or "k" is acceptable as long as it is present and matches shortcut conventions.)
```

<!-- cache_translation_check_az@latin_d872a157aba55ac38944dbf269b4cb332e81d4151e75158110e734f8cda6704f -->
```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>Pulqabınızı şifrədən çıxarmaq istədiyinizə əminsiniz?</translation>
    
ERR
The translation is incorrect. The English source asks about encrypting (locking/protecting) the wallet, but the translation means "Are you sure you wish to decrypt your wallet?" which is the opposite.

Correct translation:
Cüzdanınızı şifrələmək istədiyinizə əminsiniz?
```

<!-- cache_translation_check_az@latin_d97ea162fb8a2d41ee0a3a43fa0bf26b06e0e64c7961a1305fa8a5db34d7bed1 -->
```
        <source>&amp;Minimize</source>
        <translation>&amp;Yığın</translation>
    
ERR
The translation of "&Minimize" as "&Yığın" is incorrect. "Yığın" means "stack" or "pile" in Azerbaijani, which does not match the intended meaning of "Minimize" as in minimizing a window or application. The correct translation should be "&Minimize et" or simply "&Minimizə et" if loaned directly, but native usage would prefer "&Minimizə et".

Correct translation:
&Minimizə et
```

<!-- cache_translation_check_az@latin_6ee17510e6a9605f1964f905f7feeea872b7354e361e63f089ea34fa653c8915 -->
```
        <source>Network activity disabled.</source>
        <extracomment>A substring of the tooltip.</extracomment>
        <translation>İnternet bağlantısı söndürülüb.</translation>
    
ERR
The translation "İnternet bağlantısı söndürülüb." inaccurately translates "Network activity disabled." The word "İnternet bağlantısı" specifically refers to "Internet connection," not "network activity" in general, and "söndürülüb" is not a standard Azerbaijani word (it should be "söndürülüb" or better, "deaktiv edilib / söndürülüb"). There is also a slight typographical issue with the verb ending.

Correct translation:
Şəbəkə fəaliyyəti deaktiv edilib.
```

<!-- cache_translation_check_az@latin_2b4e3d99852f3a1e0ac8ec9a8e17ef930a5723eeb428eff0548a498deb35c496 -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>&amp;Şifrəli sözü dəyişin...</translation>
    
ERR
The translation "Şifrəli sözü dəyişin..." is incorrect for "Change Passphrase…". "Şifrəli söz" means "encrypted word", which does not accurately convey the meaning of "passphrase" in this context (which means "parol" or "şifrə" more commonly in Azerbaijani for "password/passphrase"). Also, the translation is in the formal imperative mood ("deyişin"), conforming to the polite form, which is acceptable for UI, but may be further improved. The shortcut key (&) is present, which is good.

Correct translation:
&Parolu dəyişin...
```

<!-- cache_translation_check_az@latin_6a176c6d92d38c09a45bb842bf814564c10c1682e506665af52ed41a539335b1 -->
```
        <source>&amp;Verify message…</source>
        <translation>&amp;İsmarıcı doğrulayın...</translation>
    
ERR
The word "İsmarıcı" is incorrect in this context; it is not the correct Azerbaijani term for "message". The correct word is "mesajı". Otherwise, the translation preserves the shortcut indicator, and the ellipsis style is okay.

Correct translation:
&Mesajı doğrulayın...
```

<!-- cache_translation_check_az@latin_45b61952c7d282f3ea58a80edf6ea474e4ab07b7f9784147bf6c0191a0f86c78 -->
```
        <source>Up to date</source>
        <translation>Eyniləşdirildi</translation>
    
ERR
The translation "Eyniləşdirildi" means "Synchronized" or "Updated" in Azerbaijani, but "Up to date" is better translated as "Güncəldir" or "Son vəziyyətdədir". "Eyniləşdirildi" implies a completed action rather than a current state.

Correct translation:
Güncəldir
```

<!-- cache_translation_check_az@latin_ddffd55bab3a7750cf4f0fa6735997743181b9a80a9df14e7917db181e103a4a -->
```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Qismən imzalanmış Bitcoin köçürmələrini yükləyin</translation>
    
ERR
The translation has a subtle inaccuracy. The English source refers to loading "a" (singular) "Partially Signed Bitcoin Transaction" (PSBT), but the translation uses the plural "köçürmələrini" (transactions).

Correct translation:
Qismən imzalanmış Bitcoin köçürməsini yükləyin
```

<!-- cache_translation_check_az@latin_9d17165a7d1a7fe7e4aa15d9a05ac56049813c9254891b9bd5617676d0572a4f -->
```
        <source>Open a bitcoin: URI</source>
        <translation>Bitcoin açın: URI</translation>
    
ERR
The translation does not accurately reflect the original English meaning. "Bitcoin açın: URI" is not idiomatic in Azerbaijani and is unclear; also, "açın" is imperative "open!" and does not match the infinitive/noun phrase structure. Additionally, the format differs: the placement of "bitcoin:" should be preserved as part of the URI scheme, not translated as "Bitcoin".

Correct translation:
Bitcoin: URI-ni açın
```

<!-- cache_translation_check_az@latin_2c7a0bcbfe7b6cb712d932c77eb0aa509985381f488fe1b35448e9bf2d016ca9 -->
```
        <source>(un)select all</source>
        <translation>seçim</translation>
    
ERR
The translation is incorrect and does not capture the meaning of "(un)select all". "seçim" simply means "selection" and does not convey the instruction to select or deselect all.

Correct translation:
Hamısını seç/deselect et
```

<!-- cache_translation_check_az@latin_3006794acdda32c57213b4e030278ea83bcc7ab25ccb7b9b98ca3d896c847501 -->
```
        <source>GB</source>
        <translation>QB</translation>
    
ERR
The translation is problematic. 'GB' stands for 'gigabyte', and in Azerbaijani (Latin), it is also rendered as 'GB'. 'QB' is incorrect and does not represent 'gigabyte'.

Correct translation:
GB
```
</details>

Number of issues: 12.
