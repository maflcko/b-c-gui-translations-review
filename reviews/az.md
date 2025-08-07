# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>az</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Baz%5D%20low%20quality)


```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>Pulqabınızı şifrədən çıxarmaq istədiyinizə əminsiniz?</translation>
    
YES
The translation incorrectly says "Are you sure you want to DECRYPT your wallet?" ("şifrədən çıxarmaq" means "to decrypt") instead of "encrypt". The correct translation should use "şifrələmək", which means "to encrypt".

Correct translation:
Pulqabınızı şifrələmək istədiyinizə əminsiniz?
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>Ciddi xəta baş verdi. Ayarlar faylının yazılabilən olduğunu yoxlayın və ya -nonsettings (ayarlarsız) parametri ilə işə salın.</translation>
    
YES
There is an error in the translation:
- "-nonsettings" is incorrect, it should be "-nosettings" as in the original text.
- Instead of "və ya", it should be "və ya ... ilə işə salın" to match "or try running with -nosettings".
- The rest of the translation is accurate and clean.

Correct translation:
Ciddi xəta baş verdi. Ayarlar faylının yazıla bilən olduğunu yoxlayın və ya -nosettings parametri ilə işə salın.
```

```
        <source>Minimize</source>
        <translation>Yığın</translation>
    
YES
The translation is incorrect. "Yığın" means "Stack" or "Heap" in Azerbaijani, not "Minimize". The correct translation for "Minimize" is "Minimallaşdır".

Correct translation:
Minimallaşdır
```

```
        <source>Network activity disabled.</source>
        <extracomment>A substring of the tooltip.</extracomment>
        <translation>İnternet bağlantısı söndürülüb.</translation>
    
YES
The translation "İnternet bağlantısı söndürülüb." means "Internet connection has been turned off." The original "Network activity disabled." is broader and does not specifically refer to the internet; it refers to all network activity, which can include local networks or P2P networking as well.

Correct translation:
Şəbəkə fəaliyyəti deaktiv edilib.
```

```
        <source>Up to date</source>
        <translation>Eyniləşdirildi</translation>
    
YES
The translation "Eyniləşdirildi" more accurately means "Updated" or "Synchronized". The correct translation for "Up to date" in the context of Bitcoin (meaning the blockchain is fully synchronized and current) should be "Aktualdır" or "Güncəldir".

Correct translation:
Aktualdır
or
Güncəldir
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Qismən imzalanmış Bitcoin köçürmələrini yükləyin</translation>
    
YES
The translation incorrectly uses the plural form "köçürmələrini" (transactions) instead of the singular "köçürmə" (transaction), and "yükləyin" is imperative ("load [you]"), while the source is a neutral title/caption.

Correct translation:
Qismən imzalanmış Bitcoin köçürməsini yüklə
```

```
        <source>(un)select all</source>
        <translation>seçim</translation>
    
YES
The translation "seçim" means "selection" and does not convey the meaning of "(un)select all". It also omits the function of toggling the selection.

Correct translation:
Hamısını seç / seçimdən çıxar
```

```
        <source>Copy bytes</source>
        <translation>Baytları koyalayın</translation>
    
YES
The translation is inaccurate. The correct translation of "Copy bytes" into Azerbaijani is "Baytları kopyalayın". The word "koyalayın" is incorrect and does not exist in Azerbaijani; it appears to be a typo or error for "kopyalayın".

Correct translation:
Baytları kopyalayın
```

```
        <source> GB</source>
        <translation>QB</translation>
    
YES
The translation of " GB" as "QB" is erroneous. "GB" stands for "gigabayt" in Azerbaijani, and the abbreviation remains "GB" (not "QB"). The translation should preserve the format and capitalization, only translating the unit if there is a standard local abbreviation (which there is not in this case).

Correct translation:
 GB
```

```
        <source>GB</source>
        <translation>QB</translation>
    
YES
The translation is erroneous. "GB" stands for "Gigabyte" and in Azerbaijani should also be "GB", not "QB". The correct translation would be to keep "GB" unchanged.

Correct translation:
GB
```

```
        <source>Copy bytes</source>
        <translation>Baytları koyalayın</translation>
    
YES
The translation is inaccurate. The correct translation of "Copy bytes" into Azerbaijani is "Baytları kopyalayın". The word "koyalayın" is incorrect and does not exist in Azerbaijani; it appears to be a typo or error for "kopyalayın".

Correct translation:
Baytları kopyalayın
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Xəbərdarlıq: Gizli açarlar, sıradan çıxarılmış gizli açarlar ilə {%s} pulqabısında aşkarlandı.</translation>
    
YES
The translation is problematic because it is not clear in Azerbaijani. The phrase "sıradan çıxarılmış gizli açarlar" is an incorrect expression for "with disabled private keys". It could be misunderstood, and the sentence is a bit convoluted. The format specifier {%s} is taken over correctly.

Correct translation:
Xəbərdarlıq: Gizli açarlar gizli açarlar deaktiv edilmiş {%s} pulqabısında aşkarlandı.
```
</details>

Number of issues: 12.
