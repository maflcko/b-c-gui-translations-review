# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>az</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Baz%5D%20low%20quality)


```
        <source>Close</source>
        <translation>Bağla</translation>
    
YES, The translation is problematic because "Bağla" means "Connect" or "Tie" in Turkish, not "Close" which is "Qapat" or "Bagla" in Azeri. 
Qapat
```

```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>Pulqabınızı şifrədən çıxarmaq istədiyinizə əminsiniz?</translation>
    
YES: The translation contains an error. The source text asks if the user wants to *encrypt* their wallet, but the translation asks if the user wants to *decrypt* their wallet.

Pulqabınızı şifrələmək istədiyinizə əminsiniz?
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Ola bilsin ki, %1 faylı zədələnib və ya yararsızdır.</translation>
    
YES, The translation is problematic because it uses an informal and inappropriate opening "Ola bilsin ki" (meaning "Let it be known that" or "It might be that") in a technical context. The word "zədələnib" (meaning "damaged") is also not the most accurate translation for "corrupt" in a technical sense. A more appropriate translation would use "korrupt" or a similar technical term.

Correct translation: Ayarlar faylı %1 korrupt və ya etibarsız ola bilər.
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>Ciddi xəta baş verdi. Ayarlar faylının yazılabilən olduğunu yoxlayın və ya -nonsettings (ayarlarsız) parametri ilə işə salın.</translation>
    
YES, The translation is problematic. The phrase "try running with -nosettings." was incorrectly translated as "-nonsettings (ayarlarsız) parametri ilə işə salın." The correct translation should be "-nosettings parametri ilə işə salın.".
Ciddi xəta baş verdi. Ayarlar faylının yazılabilən olduğunu yoxlayın və ya -nosettings parametri ilə işə salın.
```

```
        <source>Minimize</source>
        <translation>Yığın</translation>
    
YES, The translation is incorrect. The English word "Minimize" translates to "Azaltmaq" or "Minimuma endirmək" in Azerbaijani, not "Yığın".
The correct translation should be:
Azaltmaq
```

```
        <source>Network activity disabled.</source>
        <extracomment>A substring of the tooltip.</extracomment>
        <translation>İnternet bağlantısı söndürülüb.</translation>
    
YES: The translation is inaccurate. The source text states that "network activity" is disabled, which refers to the Bitcoin network. The translation, however, states that "internet connection" is disabled. The correct translation should refer to the network itself.

Correct translation: Şəbəkə fəaliyyəti söndürülüb.
```

```
        <source>Close Wallet…</source>
        <translation>Cüzdanı bağlayın...</translation>
    
YES, The translation is problematic because "bağlayın" means "connect" or "attach" not "close". The correct translation should be "Cüzdanı kapatın..." which means "Close Wallet...".
Cüzdanı kapatın...
```

```
        <source>Close All Wallets…</source>
        <translation>Bütün cüzdanları bağlayın...</translation>
    
YES, The translation is problematic because it uses the wrong verb. "Bağlayın" means "connect" or "tie", while "açın" or "qapayın" would be more appropriate for "close".
Bütün cüzdanları açın...
```

```
        <source>Up to date</source>
        <translation>Eyniləşdirildi</translation>
    
YES, The translation is not accurate. "Eyniləşdirildi" means "standardized" or "unified", which is not the meaning of "Up to date". The correct translation for "Up to date" in this context would be "Aktual" or "Yenilənmiş".
YES, The translation is not accurate. "Eyniləşdirildi" means "standardized" or "unified", which is not the meaning of "Up to date". The correct translation for "Up to date" in this context would be "Aktual" or "Yenilənmiş".
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Qismən imzalanmış Bitcoin köçürmələrini yükləyin</translation>
    
YES: The translation uses the word "köçürmələrini" which translates to "transfers" or "remittances". However, in the context of Bitcoin, "transaction" is more appropriate. The correct translation should use the word "əməliyyatlarını".

Qismən imzalanmış Bitcoin əməliyyatlarını yükləyin
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>PSBT-i mübadilə yaddaşından yükləyin...</translation>
    
YES, The translation uses an incorrect term for "clipboard". "Mübadilə yaddaşı" translates to "exchange memory" or "buffer", not clipboard.
PSBT-ni panə əlavə etdən yükləyin...
```

```
        <source>Close wallet</source>
        <translation>Cüzdanı bağlayın</translation>
    
YES, The translation is inaccurate. "Close wallet" means to shut down or exit the wallet application, while "Cüzdanı bağlayın" means "Connect the wallet". The correct translation should be "Cüzdanı kapatın".

Cüzdanı kapatın
```

```
        <source>Restore Wallet…</source>
        <extracomment>Name of the menu item that restores wallet from a backup file.</extracomment>
        <translation>Cüzdanı bərpa edin...</translation>
    
YES, The translation is problematic due to the use of the Azerbaijani word "bərpa" which is incorrect in this context. The correct Azerbaijani word for "restore" in the context of a wallet would be "bərpa etmək". Additionally, the ellipsis is missing. The correct translation should be "Cüzdanı bərpa edin...".
```

```
        <source>Close all wallets</source>
        <translation>Bütün cüzdanları bağlayın</translation>
    
YES, The translation is incorrect. "Bağlayın" means "connect" or "attach" in Azerbaijani, while the source text "Close all wallets" translates to "Bütün cüzdanları kapatın".
Bütün cüzdanları kapatın
```

```
        <source>Original message:</source>
        <translation>Orijinal ismarıc:</translation>
    
YES: The translation of "message" to "ismarık" is incorrect. "İsmarıc" means "pimp" in Azerbaijani. The correct translation for "message" is "mesaj" or "mətn".
Orijinal mesaj:
```

```
        <source>(un)select all</source>
        <translation>seçim</translation>
    
YES, The translation is problematic as it only translates "select" and omits "unselect". Also, the word "seçim" means "election" or "choice" in Turkish, not "select". The correct translation for "(un)select all" in the context of Bitcoin would be "hamısını (seç/seçmə)" or "hamısını seç/seçilmə".
The correct translation is: hamısını seç/seçilmə
```

```
        <source>Copy bytes</source>
        <translation>Baytları koyalayın</translation>
    
YES, The translation is incorrect. "Copy bytes" should be translated as "Baytları kopyalayın" in Azerbaijani.
Baytları kopyalayın
```

```
        <source>Close wallet</source>
        <translation>Pulqabını bağlayın</translation>
    
YES, The translation is not accurate. The source text "Close wallet" means to close a Bitcoin wallet. The provided translation "Pulqabını bağlayın" means "Connect your wallet" in Azerbaijani.

The correct translation should be "Pulunu bağla" or "Vəsaitini bağla". However, considering the context of a wallet, "Pul qutusunu bağla" might be more appropriate.

NO
```

```
        <source>Close all wallets</source>
        <translation>Bütün cüzdanları bağlayın</translation>
    
YES, The translation is incorrect. "Bağlayın" means "connect" or "attach" in Azerbaijani, while the source text "Close all wallets" translates to "Bütün cüzdanları kapatın".
Bütün cüzdanları kapatın
```

```
        <source>Make a blank wallet. Blank wallets do not initially have private keys or scripts. Private keys and addresses can be imported, or an HD seed can be set, at a later time.</source>
        <translation>Boş pulqabı yaradın. Boş pulqabında ilkin olaraq açarlar və skriptlər yoxdur. Sonra məxfi açarlar və ünvanlar idxal edilə bilər və ya HD məxfi açarlar təyin edilə bilər.</translation>
    
YES: The translation uses the phrase "məxfi açarlar" which translates to "confidential keys". While Bitcoin uses private keys, the term "confidential keys" is not standard and can be misleading. The correct translation for "private keys" in this context is "şəxsi açarlar".

Boş pulqabı yaradın. Boş pulqabında ilkin olaraq şəxsi açarlar və skriptlər yoxdur. Sonra şəxsi açarlar və ünvanlar idxal edilə bilər və ya HD toxumu təyin edilə bilər.
```

```
        <source> GB</source>
        <translation>QB</translation>
    
YES, The translation is incorrect and meaningless. The English text "GB" likely refers to gigabytes, a unit of data storage. The translated text "QB" is not a recognized unit in this context and is likely an error.

Correct translation: GB
```

```
        <source>GB</source>
        <translation>QB</translation>
    
YES, The translation is incorrect. The ISO 3166-1 alpha-2 code for Great Britain is GB, not QB.
The correct translation is:
"GB"
```

```
        <source>Close</source>
        <translation>Bağla</translation>
    
YES, The translation is problematic because "Bağla" means "Connect" or "Tie" in Turkish, not "Close" which is "Qapat" or "Bagla" in Azeri. 
Qapat
```

```
        <source>Copy bytes</source>
        <translation>Baytları koyalayın</translation>
    
YES, The translation is incorrect. "Copy bytes" should be translated as "Baytları kopyalayın" in Azerbaijani.
Baytları kopyalayın
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Xəbərdarlıq: Gizli açarlar, sıradan çıxarılmış gizli açarlar ilə {%s} pulqabısında aşkarlandı.</translation>
    
YES - The translation of "disabled" is incorrect in this context. It should be "şəxsi açarların istifadəsi qadağan edilmişdir" which means "private keys have been disabled".

Xəbərdarlıq: Şəxsi açarlar, şəxsi açarların istifadəsi qadağan edilmişdir olan {%s} pulqabısında aşkarlandı.
```
</details>
