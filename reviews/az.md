# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>az</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Baz%5D%20low%20quality)


```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>Pulqabınızı şifrədən çıxarmaq istədiyinizə əminsiniz?</translation>
    
YES  
The translation is incorrect. The English source asks if the user wants to encrypt the wallet, but the Azerbaijani translation asks if the user wants to decrypt the wallet, which is the opposite meaning.

Correct translation:  
Cüzdanınızı şifrələmək istədiyinizə əminsiniz?
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Ola bilsin ki, %1 faylı zədələnib və ya yararsızdır.</translation>
    
YES
The phrase "Ola bilsin ki," is an informal and unnecessary way to introduce possibility ("maybe") and not typical in technical contexts. The rest of the sentence is accurate, but "Ola bilsin ki" is not idiomatic or appropriate here. Also, "faylı" should be placed right after "%1" without extra spacing, which is correct.

Correct translation:
%1 sənəd faylı zədələnib və ya etibarsızdır.
or
%1 ayar faylı zədələnib və ya yararsızdır.
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>Ciddi xəta baş verdi. Ayarlar faylının yazılabilən olduğunu yoxlayın və ya -nonsettings (ayarlarsız) parametri ilə işə salın.</translation>
    
YES
There is an error in the translation:
1. The source has "-nosettings" but the translation writes "-nonsettings", which is a typographical error.
2. The description "(ayarlarsız)" is added, which is not present in the source. If extra explanations are not allowed, this is problematic.
3. The conjunction "və ya" should reflect "or try running with" (which is "or try to run with").
4. The format "yazılabilən olduğunu yoxlayın" is unnatural; "yazıla bilən olduğunu" (with a space) is correct for Azerbaijani.

Correct translation:
Ciddi xəta baş verdi. Ayarlar faylının yazıla bilən olduğunu yoxlayın və ya -nosettings parametri ilə işə salmağı yoxlayın.
```

```
        <source>Minimize</source>
        <translation>Yığın</translation>
    
YES
The translation is incorrect. "Yığın" means "Stack" or "Pile" in Azerbaijani, not "Minimize". The correct translation for "Minimize" is "Minimallaşdır" or "Kiçilt".

Correct translation:
Minimallaşdır
```

```
        <source>Network activity disabled.</source>
        <extracomment>A substring of the tooltip.</extracomment>
        <translation>İnternet bağlantısı söndürülüb.</translation>
    
YES
The translation of "Network activity disabled." as "İnternet bağlantısı söndürülüb." is problematic. "İnternet bağlantısı" means "internet connection," which is more specific than "network activity," and "söndürülüb" is not commonly used for disabling network activity.

Correct translation:
Şəbəkə aktivliyi deaktiv edilib.
```

```
        <source>Up to date</source>
        <translation>Eyniləşdirildi</translation>
    
YES
The translation "Eyniləşdirildi" means "Updated" or "Has been updated," which does not accurately convey "Up to date." The correct translation for "Up to date" in Azerbaijani is "Güncəldir" or "Aktualdır."

Correct translation:
Güncəldir
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Qismən imzalanmış Bitcoin köçürmələrini yükləyin</translation>
    
YES
There is an error in the translation from singular to plural. The English text refers to a single transaction ("Transaction"), but the translation uses the plural form ("köçürmələrini" = transactions). Also, the format "yükləyin" uses the imperative plural/polite, but the source is neutral/infinitive.

Correct translation:
Qismən imzalanmış Bitcoin köçürməsini yüklə
```

```
        <source>Original message:</source>
        <translation>Orijinal ismarıc:</translation>
    
YES
The translation has a spelling error: "ismarıc" is incorrect in Azerbaijani. The correct spelling is "mesaj" for "message".

Correct translation:
Orijinal mesaj:
```

```
        <source>(un)select all</source>
        <translation>seçim</translation>
    
YES
The translation is incorrect and incomplete. The English phrase "(un)select all" means to either select all or unselect all items, commonly seen as a toggle option. The word "seçim" only means "selection" and does not convey the intended meaning of the source.

Correct translation:
Hamısını seç/burax

Or more commonly in Azerbaijani UI:
Hamısını seç / seçimləri ləğv et
```

```
        <source>Copy bytes</source>
        <translation>Baytları koyalayın</translation>
    
YES
The translation is incorrect. "Koyalayın" is not a proper Azerbaijani word and seems to be a misspelling. The correct verb for "copy" is "kopyalayın".

Correct translation:
Baytları kopyalayın
```

```
        <source>Close wallet</source>
        <translation>Pulqabını bağlayın</translation>
    
YES
The translation "Pulqabını bağlayın" is incorrect because "Pulqabı" is not a standard term for "wallet" in Azerbaijani; the correct term is "Cüzdan" (which is also used for Bitcoin wallet). Additionally, the verb structure is off and not idiomatic.

Correct translation:
Cüzdanı bağlayın
```

```
        <source>Make a blank wallet. Blank wallets do not initially have private keys or scripts. Private keys and addresses can be imported, or an HD seed can be set, at a later time.</source>
        <translation>Boş pulqabı yaradın. Boş pulqabında ilkin olaraq açarlar və skriptlər yoxdur. Sonra məxfi açarlar və ünvanlar idxal edilə bilər və ya HD məxfi açarlar təyin edilə bilər.</translation>
    
YES
There are some inaccuracies in the translation:

1. "Private keys" is translated as just "açarlar" in the second sentence, but it should be "məxfi açarlar".
2. "HD seed" should not be translated as "HD məxfi açarlar", because "seed" is not the same as "private key". It should be "HD toxumu".
3. "scripts" is translated as "skriptlər", which is fine.
4. The sentence about blank wallets not initially having private keys or scripts does not fully specify "private keys" (just "açarlar"), and "scripts" is missing in the translation.
5. Flow and sentence structure can be improved for clarity.

Correct translation:
Boş pulqabı yaradın. Boş pulqabılarda ilkin olaraq məxfi açarlar və skriptlər olmur. Daha sonra məxfi açarlar və ünvanlar idxal edilə bilər və ya HD toxumu təyin oluna bilər.
```

```
        <source> GB</source>
        <translation>QB</translation>
    
YES
The translation is incorrect. "GB" stands for "gigabyte" and should not be translated as "QB". In Azerbaijani, the correct abbreviation for gigabyte is also "GB".

Correct translation:
<translation> GB</translation>
```

```
        <source>GB</source>
        <translation>QB</translation>
    
YES
The abbreviation "GB" stands for "Gigabyte" and should not be translated as "QB". The Azerbaijani language commonly uses "GB" as in English, as this is a standard international abbreviation in computing.

Correct translation:
<translation>GB</translation>
```

```
        <source>Copy bytes</source>
        <translation>Baytları koyalayın</translation>
    
YES
The translation is incorrect. "Koyalayın" is not a proper Azerbaijani word and seems to be a misspelling. The correct verb for "copy" is "kopyalayın".

Correct translation:
Baytları kopyalayın
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>Xəbərdarlıq: Gizli açarlar, sıradan çıxarılmış gizli açarlar ilə {%s} pulqabısında aşkarlandı.</translation>
    
YES
There is a clarity issue: "sıradan çıxarılmış gizli açarlar ilə" is awkward and unclear in Azerbaijani. The phrase is not idiomatic and does not accurately reflect "with disabled private keys". Additionally, a comma after "Gizli açarlar" is unnecessary.

Correct translation:
Xəbərdarlıq: Gizli açarlar, gizli açarları deaktiv edilmiş {%s} pulqabısında aşkar edildi.
```
</details>
