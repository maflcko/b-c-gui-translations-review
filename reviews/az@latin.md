# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>az@latin</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Baz@latin%5D%20low%20quality)


```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>Pulqabınızı şifrədən çıxarmaq istədiyinizə əminsiniz?</translation>
    
YES
The translation is incorrect. The English source asks if the user wants to encrypt (şifrələmək) the wallet, but the translation asks if the user wants to decrypt (şifrədən çıxarmaq) it, which is the opposite meaning.

Correct translation:
Pulqabınızı şifrələmək istədiyinizə əminsiniz?
```

```
        <source>Minimize</source>
        <translation>Yığın</translation>
    
YES
The translation is incorrect. "Yığın" means "Stack" or "Heap" in Azerbaijani and does not correspond to "Minimize". The correct translation should be:

"Daxil et" or "Kiçilt" depending on context, but for UI buttons, "Minimize" is best translated as "Kiçilt".

Correct translation:
<translation>Kiçilt</translation>
```

```
        <source>Network activity disabled.</source>
        <extracomment>A substring of the tooltip.</extracomment>
        <translation>İnternet bağlantısı söndürülüb.</translation>
    
YES
The translation is inaccurate. "Network activity" should be translated more precisely as "Şəbəkə fəaliyyəti" rather than "İnternet bağlantısı". The current translation suggests "Internet connection," which is not the intended technical meaning.

Correct translation:
Şəbəkə fəaliyyəti söndürülüb.
```

```
        <source>Up to date</source>
        <translation>Eyniləşdirildi</translation>
    
YES
"Eyniləşdirildi" translates to "Updated," which is not the same as "Up to date." The correct translation for "Up to date" in Azerbaijani (Latin script) would be "Aktualdır" or "Güncəldir."

Correct translation:
Aktualdır
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Qismən imzalanmış Bitcoin köçürmələrini yükləyin</translation>
    
YES
There is a minor issue: The source is singular ("Transaction"), but the translation is plural ("köçürmələrini" = "transactions"). It should match the singular in the original.

Correct translation:
Qismən imzalanmış Bitcoin köçürməsini yükləyin
```

```
        <source>Open a bitcoin: URI</source>
        <translation>Bitcoin açın: URI</translation>
    
YES
The translation has a word order issue. In Azerbaijani, the correct form should be: "Bitcoin URI açın" or "Bir bitcoin URI açın". The given translation "Bitcoin açın: URI" is misleading and ungrammatical.

Correct translation:
Bir bitcoin URI açın
or
Bitcoin URI açın
```

```
        <source>(un)select all</source>
        <translation>seçim</translation>
    
YES
The translation "seçim" does not accurately convey the meaning of "(un)select all". "Seçim" means "selection" in Azerbaijani, but the appropriate translation should reflect the action of selecting or deselecting all items.

Correct translation:
Hamısını seç / seçimdən çıxar
```

```
        <source>GB</source>
        <translation>QB</translation>
    
YES
The abbreviation "GB" stands for "Gigabyte" and is commonly used internationally without translation, even in Azerbaijani (az@latin). "QB" does not have meaning in this context and is incorrect.

Correct translation:
GB
```
</details>
