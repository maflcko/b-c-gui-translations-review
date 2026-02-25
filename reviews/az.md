# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>az</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Baz%5D%20request)


<!-- cache_translation_check_az_c713146aaa10d6b6cff8ca2611acc059e9017d626ab316f35d4323644c849bb1 -->
```
        <source>C&amp;lose</source>
        <translation>Bağla</translation>
    
ERR
The translation omits the ampersand (&) used for indicating the keyboard shortcut. In Qt translations, the ampersand should be preserved in the translation, typically placed before a shortcut letter.

Correct translation:
&Bağla
```

<!-- cache_translation_check_az_9da4515776127b2096fb029b7dd6be025053a20b1a94ba3e3061a83cfa859971 -->
```
        <source>C&amp;hoose</source>
        <translation>Seç</translation>
    
ERR
The translation omits the '&' character, which is used to indicate a keyboard shortcut in the UI. This makes the translation inconsistent in functionality with the source.

Correct translation:
&Seç

Or alternatively:
S&eç

(As long as the '&' occurs exactly once and does not introduce formatting issues.)
```

<!-- cache_translation_check_az_42b12ab4470a52e925fcced76dca24c8640a51c07f1ad19f421bdb56a7d8b91d -->
```
        <source>Copy &amp;Label</source>
        <translation>Etiketi kopyala</translation>
    
ERR
The shortcut marker (&) is missing in the Azerbaijani translation. Shortcut keys should be preserved, typically as: "&Etiketi kopyala" or "Etiketi &kopyala" depending on desired keyboard shortcut placement.

Correct translation:
&Etiketi kopyala
</reply>
```

<!-- cache_translation_check_az_d872a157aba55ac38944dbf269b4cb332e81d4151e75158110e734f8cda6704f -->
```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>Pulqabınızı şifrədən çıxarmaq istədiyinizə əminsiniz?</translation>
    
ERR
The translation incorrectly says "Are you sure you want to DECRYPT your wallet?" ("şifrədən çıxarmaq" means "to decrypt") instead of "encrypt". The correct translation should use "şifrələmək", which means "to encrypt".

Correct translation:
Pulqabınızı şifrələmək istədiyinizə əminsiniz?
```

<!-- cache_translation_check_az_1488399e4fd6313d2b928de4402bff9452e664f37df9b94b7a14184fae73b81d -->
```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>Ciddi xəta baş verdi. Ayarlar faylının yazılabilən olduğunu yoxlayın və ya -nonsettings (ayarlarsız) parametri ilə işə salın.</translation>
    
ERR
There is an error in the translation:
- "-nonsettings" is incorrect, it should be "-nosettings" as in the original text.
- Instead of "və ya", it should be "və ya ... ilə işə salın" to match "or try running with -nosettings".
- The rest of the translation is accurate and clean.

Correct translation:
Ciddi xəta baş verdi. Ayarlar faylının yazıla bilən olduğunu yoxlayın və ya -nosettings parametri ilə işə salın.
```

<!-- cache_translation_check_az_d97ea162fb8a2d41ee0a3a43fa0bf26b06e0e64c7961a1305fa8a5db34d7bed1 -->
```
        <source>&amp;Minimize</source>
        <translation>&amp;Yığın</translation>
    
ERR
The word "Yığın" translates to "stack" or "heap" and does not convey the meaning of "Minimize" in the context of minimizing a window. The correct translation for "Minimize" in Azerbaijani is "Minimizə et" or simply "Kiçilt".

Correct translation:
&Kiçilt
```

<!-- cache_translation_check_az_6ee17510e6a9605f1964f905f7feeea872b7354e361e63f089ea34fa653c8915 -->
```
        <source>Network activity disabled.</source>
        <extracomment>A substring of the tooltip.</extracomment>
        <translation>İnternet bağlantısı söndürülüb.</translation>
    
ERR
The translation "İnternet bağlantısı söndürülüb." means "Internet connection has been turned off." The original "Network activity disabled." is broader and does not specifically refer to the internet; it refers to all network activity, which can include local networks or P2P networking as well.

Correct translation:
Şəbəkə fəaliyyəti deaktiv edilib.
```

<!-- cache_translation_check_az_2b4e3d99852f3a1e0ac8ec9a8e17ef930a5723eeb428eff0548a498deb35c496 -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>&amp;Şifrəli sözü dəyişin...</translation>
    
ERR
The translation "Şifrəli sözü dəyişin..." is incorrect. The phrase "passphrase" is typically translated as "parol" or "şifrə" in Azerbaijani, not "şifrəli söz" (which literally means "encrypted word" and is uncommon). Also, it's better to keep elliptical dots consistent with the source: use the ellipsis character (…).

Correct translation:
&Parolu dəyiş…
```

<!-- cache_translation_check_az_6a176c6d92d38c09a45bb842bf814564c10c1682e506665af52ed41a539335b1 -->
```
        <source>&amp;Verify message…</source>
        <translation>&amp;İsmarıcı doğrulayın...</translation>
    
ERR
The word "ismarıcı" is incorrect in Azerbaijani in this context; it does not mean "message". The correct translation for "message" is "isra" or "mesaj". The rest of the translation is appropriate, and the shortcut is preserved.

Correct translation:
&amp;Mesajı doğrulayın...
```

<!-- cache_translation_check_az_45b61952c7d282f3ea58a80edf6ea474e4ab07b7f9784147bf6c0191a0f86c78 -->
```
        <source>Up to date</source>
        <translation>Eyniləşdirildi</translation>
    
ERR
The translation "Eyniləşdirildi" more accurately means "Updated" or "Synchronized". The correct translation for "Up to date" in the context of Bitcoin (meaning the blockchain is fully synchronized and current) should be "Aktualdır" or "Güncəldir".

Correct translation:
Aktualdır
or
Güncəldir
```

<!-- cache_translation_check_az_ddffd55bab3a7750cf4f0fa6735997743181b9a80a9df14e7917db181e103a4a -->
```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Qismən imzalanmış Bitcoin köçürmələrini yükləyin</translation>
    
ERR
The translation incorrectly uses the plural form "köçürmələrini" (transactions) instead of the singular "köçürmə" (transaction), and "yükləyin" is imperative ("load [you]"), while the source is a neutral title/caption.

Correct translation:
Qismən imzalanmış Bitcoin köçürməsini yüklə
```

<!-- cache_translation_check_az_2c7a0bcbfe7b6cb712d932c77eb0aa509985381f488fe1b35448e9bf2d016ca9 -->
```
        <source>(un)select all</source>
        <translation>seçim</translation>
    
ERR
The translation "seçim" means "selection" and does not convey the meaning of "(un)select all". It also omits the function of toggling the selection.

Correct translation:
Hamısını seç / seçimdən çıxar
```

<!-- cache_translation_check_az_3881e3f0dbf22ca2e4f25f37060d5ef56011df2a5b5ffee1ac15a5faf6c814b4 -->
```
        <source>&amp;Unlock unspent</source>
        <translation>Xərclənməmiş qalığı kilidd'n &amp;çıxarın</translation>
    
ERR
There is a typo and unnatural phrasing in the translation. "kilidd'n" is incorrect; it should be "kiliddən". Also, "Xərclənməmiş qalığı" refers to "unspent balance," but in this context, "unspent" more likely refers to an "unspent output" or "unspent transaction". A more natural and accurate translation is:

Correct translation:
Xərclənməmiş kilidi &açı

or

Xərclənməmişi &kiliddən çıxarın

Both preserve the meaning and shortcut key. The ampersand placement can change, but should not be omitted or duplicated.
```

<!-- cache_translation_check_az_e3a98560448ec119856e3f3a85e417fa3e52162eb1cb4e123bbcf65e3899735b -->
```
        <source>Copy bytes</source>
        <translation>Baytları koyalayın</translation>
    
ERR
The translation is inaccurate. The correct translation of "Copy bytes" into Azerbaijani is "Baytları kopyalayın". The word "koyalayın" is incorrect and does not exist in Azerbaijani; it appears to be a typo or error for "kopyalayın".

Correct translation:
Baytları kopyalayın
```

<!-- cache_translation_check_az_eb21fed4cedaa88be0e65a65d30307899db88ab814904c7a85a4c1a13654c48b -->
```
        <source> GB</source>
        <translation>QB</translation>
    
ERR
The translation of " GB" as "QB" is erroneous. "GB" stands for "gigabayt" in Azerbaijani, and the abbreviation remains "GB" (not "QB"). The translation should preserve the format and capitalization, only translating the unit if there is a standard local abbreviation (which there is not in this case).

Correct translation:
 GB
```

<!-- cache_translation_check_az_3006794acdda32c57213b4e030278ea83bcc7ab25ccb7b9b98ca3d896c847501 -->
```
        <source>GB</source>
        <translation>QB</translation>
    
ERR
The translation is erroneous. "GB" stands for "Gigabyte" and in Azerbaijani should also be "GB", not "QB". The correct translation would be to keep "GB" unchanged.

Correct translation:
GB
```

<!-- cache_translation_check_az_e3a98560448ec119856e3f3a85e417fa3e52162eb1cb4e123bbcf65e3899735b -->
```
        <source>Copy bytes</source>
        <translation>Baytları koyalayın</translation>
    
ERR
The translation is inaccurate. The correct translation of "Copy bytes" into Azerbaijani is "Baytları kopyalayın". The word "koyalayın" is incorrect and does not exist in Azerbaijani; it appears to be a typo or error for "kopyalayın".

Correct translation:
Baytları kopyalayın
```

<!-- cache_translation_check_az_e5f5eb7c9a13fe97ad71d2e2ec104b68689f5f8d469c22c5a2bc3082941460ab -->
```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Xəbərdarlıq: Gizli açarlar, sıradan çıxarılmış gizli açarlar ilə {%s} pulqabısında aşkarlandı.</translation>
    
ERR
The translation is problematic because it is not clear in Azerbaijani. The phrase "sıradan çıxarılmış gizli açarlar" is an incorrect expression for "with disabled private keys". It could be misunderstood, and the sentence is a bit convoluted. The format specifier {%s} is taken over correctly.

Correct translation:
Xəbərdarlıq: Gizli açarlar gizli açarlar deaktiv edilmiş {%s} pulqabısında aşkarlandı.
```
</details>

Number of issues: 18.
