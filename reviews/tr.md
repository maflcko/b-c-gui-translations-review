# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>tr</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Btr%5D%20low%20quality)


```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>Bu işlemi yapabilmek için cüzdan parolanızı girmeniz gerekmektedir
Cüzdan kilidini aç.</translation>
    
YES, The translation is split into two sentences and the second sentence is incomplete.
Bu işlemi yapabilmek için cüzdan parolanızı girmeniz gerekmektedir.
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Cüzdan parolasının kaldırılması için girilen parola yanlış.</translation>
    
YES: The translation incorrectly uses "kaldırılması için" which translates to "for removal". The intended meaning is "decryption", which translates to "şifre çözme".
The correct translation is: Cüzdan şifresinin çözülmesi için girilen parola yanlış.
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future</translation>
    
UNK_LANG
```

```
        <source>Runaway exception</source>
        <translation>Sızıntı istisnası</translation>
    
YES, "runaway" has been translated as "sızan" which means "leaking" or "seeping." In the context of Bitcoin, "runaway exception" likely refers to an exception that is not being handled or contained properly. A more accurate translation would be "Kontrolsüz istisna" or "Geri dönülmez istisna."

"Sızıntı istisnası" might be acceptable if the exception is causing a data leak, but without further context, it's not the most direct translation.

NO
```

```
        <source>%1 didn't yet exit safely…</source>
        <translation>%1  henüz güvenli bir şekilde çıkış yapmadı...</translation>
    
YES, The translation contains an extra space between "%1" and "henüz". The correct translation is: %1 henüz güvenli bir şekilde çıkış yapmadı...
```

```
        <source>Amount</source>
        <translation>Mitar</translation>
    
YES, The translation is incorrect. "Amount" in the context of Bitcoin refers to the quantity of Bitcoin, which translates to "Tutar" in Turkish.
NO
```

```
        <source>Onion</source>
        <comment>network name</comment>
        <extracomment>Name of Tor network in peer info</extracomment>
        <translation>Soğan</translation>
    
YES
The translation is too literal and doesn't convey the intended meaning in the context of the Tor network. "Soğan" means "onion" in Turkish, but in this context, it should refer to the Tor network's onion routing. A more appropriate translation would be "Tor Ağı".

Correct translation: Tor Ağı
```

```
        <source>Outbound</source>
        <extracomment>An outbound connection to a peer. An outbound connection is a connection initiated by us.</extracomment>
        <translation>yurt dışı</translation>
    
YES, The translation "yurt dışı" means "abroad" or "international" which is not the correct translation for "Outbound" in the context of Bitcoin peer connections. The correct translation should refer to a connection originating from the user's node.
Correct translation: Dışa giden
```

```
        <source>%1 d</source>
        <translation>%1 g</translation>
    
YES, The format specifier %1 is not translated correctly. The translation should be "%1 g".
```

```
        <source>%1 h</source>
        <translation>%1 sa</translation>
    
YES: The translation incorrectly uses "sa" which is likely a typo or an incomplete translation for "saat" (hour in Turkish). The format specifier %1 is correctly transferred.
Correct translation: %1 s
```

```
        <source>%1 m</source>
        <translation>%1 d</translation>
    
YES, the translation is incorrect. The source text "%1 m" likely refers to "%1 million" or "%1 months" in a Bitcoin context. The translation "%1 d" means "%1 days" in Turkish, which is a different unit of time and significantly alters the meaning.

NO
```

```
        <source>Browse transaction history</source>
        <translation>İşlem geçişini görüntüle</translation>
    
YES: The translation "İşlem geçişini görüntüle" is awkward and unnatural in Turkish for this context. "Geçiş" typically refers to a transition or passage, not a history or browsing of transactions. A more accurate and natural translation would be "İşlem geçmişine göz atın".
İşlem geçmişine göz atın
```

```
        <source>Receive</source>
        <translation>Al</translation>
    
YES
The translation of "Receive" to "Al" is incorrect in the context of Bitcoin transactions. In Turkish, "Al" means "Take" or "Get". The correct translation for "Receive" in this context would be "Alın" (as a command) or "Almak" (as a verb).

Alın
```

```
        <source>Open URI…</source>
        <translation>URI 'ı Aç...</translation>
    
YES, The translation is problematic. The possessive suffix 'ı' is incorrectly attached to the word "URI". It should be "URI'yi Aç..."
The correct translation is: URI'yi Aç...
```

```
        <source>Sending addresses</source>
        <translation> Adresleri gönderme</translation>
    
YES, The translation is problematic. The source text "Sending addresses" is translated as " Adresleri gönderme" which literally means "Sending the addresses". The article "the" is not present in the source text. The correct translation for "Sending addresses" in Turkish would be "Gönderen adresler". There is also an unnecessary space before "Adresleri".
NO
```

```
        <source>Open a bitcoin: URI</source>
        <translation>Bitcoin’i aç.</translation>
    
YES, The translation is inaccurate and problematic. The source text "Open a bitcoin: URI" is translated to "Bitcoin’i aç." which means "Open Bitcoin." in Turkish. This is a very general translation and does not convey the specific meaning of opening a Bitcoin URI. A more accurate translation would be something like "Bitcoin URI'si aç" or "Bitcoin adresini aç." to reflect the source text's intent of opening a specific Bitcoin Uniform Resource Identifier.

Bitcoin URI'si aç.
```

```
        <source>Window</source>
        <translation>Pencere</translation>
    
UNK_LANG
```

```
        <source>HD key generation is &lt;b&gt;enabled&lt;/b&gt;</source>
        <translation>HD anahtar üreticiler &lt;b&gt;kullanilabilir&lt;/b&gt;</translation>
    
YES - The translation uses "anahtar üreticiler" which translates to "key generators" (plural). The source text states "HD key generation is enabled" which is singular and refers to the process of generating keys, not the generators themselves. A more accurate translation would be "HD anahtar üretimi etkinleştirildi".
NO - HD anahtar üretimi etkinleştirildi
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>HD anahtar üreticiler &lt;b&gt;kullanılamaz&lt;/b&gt;</translation>
    
YES: The translation uses the word "üreticiler" (producers) which is incorrect in this context. The correct translation should refer to the generation of keys.
HD anahtar üretimi &lt;b&gt;devre dışı&lt;/b&gt;dır
```

```
        <source>Private key &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>Gizli anahtar oluşturma &lt;b&gt;devre dışı&lt;/b&gt;</translation>
    
YES, The translation is not accurate. The English text refers to a "private key" being disabled, while the Turkish translation implies "private key generation" is disabled.

Correct translation: Gizli anahtar &lt;b&gt;devre dışı&lt;/b&gt;
```

```
        <source>Change:</source>
        <translation>Değiştir</translation>
    
YES, The translation is problematic. The English word "Change" in the context of Bitcoin transactions refers to the remaining amount of Bitcoin that is returned to the sender after a transaction. The Turkish translation "Değiştir" means "to change" or "to alter," which does not convey the correct meaning. A more appropriate translation would be "Para Üstü" which means "change" in the sense of leftover money or change from a purchase.

NO
```

```
        <source>(un)select all</source>
        <translation>tümünü seçmek</translation>
    
YES, The translation is not accurate. The phrase "(un)select all" means to select or deselect all items, which the current translation "tümünü seçmek" (to select all) does not fully capture. It also misses the "un" part of the selection.

The correct translation should convey the meaning of both selecting and deselecting.

Correct translation: tümünü seç/seçimi kaldır
```

```
        <source>Amount</source>
        <translation>Mitar</translation>
    
YES, The translation is incorrect. "Amount" in the context of Bitcoin refers to the quantity of Bitcoin, which translates to "Tutar" in Turkish.
NO
```

```
        <source>Copy transaction ID and output index</source>
        <translation>İşlem ID ve çıktı içeriğini kopyala</translation>
    
YES, "çıktı içeriğini" should be "çıktı indeksini" to accurately translate "output index" in the context of Bitcoin transactions.

Correct translation: İşlem ID ve çıktı indeksini kopyala
```

```
        <source>(change)</source>
        <translation>(değiştir)</translation>
    
YES, The translation is incorrect. In the context of Bitcoin, "change" refers to the leftover amount of Bitcoin after a transaction, not the act of changing something. The correct translation for "change" in this context is "para üstü".

(para üstü)
```

```
        <source>Disable Private Keys</source>
        <translation>Özel Kilidi (Private Key) kaldır</translation>
    
YES, the translation uses the singular "Özel Kilidi" while the source text is plural "Private Keys". The correct translation should use the plural form of "Özel Anahtar" or "Özel Parola".

Correct translation: Özel Anahtarları (Private Keys) devre dışı bırak
```

```
        <source>Welcome</source>
        <translation>Hoş geldiniz </translation>
    
YES, The translation has a trailing space which is not present in the source text.
Hoş geldiniz
```

```
        <source>Minimize instead of exit the application when the window is closed. When this option is enabled, the application will be closed only after selecting Exit in the menu.</source>
        <translation>Pencere kapatıldığında uygulamadan çıkmak yerine uygulamayı küçültür. Bu seçenek etkinleştirildiğinde, uygulama sadece menüden çıkış seçildiğinde kapanacaktır.</translation>
    
UNK_LANG
```

```
        <source>Prune block storage to</source>
        <translation>Depolamayı küçültmek engellemek için </translation>
    
YES, The translation is inaccurate and misleading. The Turkish phrase "Depolamayı küçültmek engellemek için" translates to "To reduce storage to prevent," which does not accurately convey the meaning of "Prune block storage to." The original English phrase implies reducing the size of block storage, likely for efficiency.

The correct translation should be closer to "Blok depolamayı budamak için".

NO
```

```
        <source>Spend unconfirmed change</source>
        <translation> Onaylanmamış bozuk parayı harcayın</translation>
    
YES, The translation of "unconfirmed change" as "onaylanmamış bozuk parayı" is inaccurate in the context of Bitcoin. "Bozuk para" translates to "coins" or "loose change" in a general sense, not specifically the concept of unconfirmed Bitcoin change.

A more accurate translation would be:

YES, Onaylanmamış değişikliği harcayın
```

```
        <source>Window</source>
        <translation>Pencere</translation>
    
UNK_LANG
```

```
        <source>Mined balance that has not yet matured</source>
        <translation>ödenilmemiş miktar</translation>
    
YES, The translation is inaccurate and misleading. "Mined balance that has not yet matured" refers to Bitcoin mined by a miner that is still subject to maturation rules, which means it cannot be spent yet. The provided translation "ödenilmemiş miktar" translates to "unpaid amount" or "amount not yet paid". This is not related to Bitcoin mining maturation.

Correct translation: Henüz olgunlaşmamış madencilik bakiyesi
```

```
        <source>Balances</source>
        <translation>Hesaplar</translation>
    
YES, the translation is problematic because "Hesaplar" in Turkish means "Accounts" or "Accounts" in a broader sense, not "Balances". In the context of Bitcoin, "Balances" refers to the amounts of cryptocurrency held in a wallet or account. A more accurate translation would be "Bakiyeler".

The correct translation is:

Hesaplar -> Bakiyeler
```

```
        <source>Sends %1 to %2</source>
        <translation>Gönderiler %1 ile %2</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning. The phrase "Gönderiler %1 ile %2" translates to "Shipments %1 with %2", which is not appropriate for the context of sending Bitcoin. The correct translation should reflect sending an amount to an address.

Correct translation: "%1'i %2'ye gönder"
```

```
        <source>Outbound</source>
        <extracomment>An Outbound Connection to a Peer.</extracomment>
        <translation>yurt dışı</translation>
    
YES - The Turkish word "yurt dışı" translates to "abroad" or "international" in English, which is not an accurate translation for "Outbound" in the context of Bitcoin connections. The correct translation would be "Giden".
Giden
```

```
        <source>An optional label to associate with the new receiving address.</source>
        <translation>Yeni alım adresi ile ilişkili, seçiminize dayalı etiket.</translation>
    
YES, The translation is inaccurate and contains erroneous content. The word "seçiminize" (based on your choice) is not an accurate translation of "optional". It implies a user choice rather than an optional field.

Correct translation: Yeni alım adresiyle ilişkilendirilecek isteğe bağlı bir etiket.
```

```
        <source>Change:</source>
        <translation>Değiştir</translation>
    
YES, The translation is problematic. The English word "Change" in the context of Bitcoin transactions refers to the remaining amount of Bitcoin that is returned to the sender after a transaction. The Turkish translation "Değiştir" means "to change" or "to alter," which does not convey the correct meaning. A more appropriate translation would be "Para Üstü" which means "change" in the sense of leftover money or change from a purchase.

NO
```

```
        <source>%1 from wallet '%2'</source>
        <translation>%1 Cüzdandan '%2'</translation>
    
YES, The translation incorrectly translates "from wallet" to "Cüzdandan". The correct translation should be "%1, '%2' cüzdanından".
YES, %1, '%2' cüzdanından
```

```
        <source>Signatures - Sign / Verify a Message</source>
        <translation>İmzalar - Giri‭s / Mesaji Onayla</translation>
    
YES - The translation is inaccurate and contains erroneous content. The word "Giri‭s" (which appears to be a typo for "Giriş") means "Entrance" or "Login" in Turkish, which is not the intended meaning of "Sign" in the context of signing a message. The correct translation for "Sign" in this context would be "İmzal" or "İmzala".

Correct translation: İmzalar - İmzal / Mesajı Doğrula
```

```
        <source>The entered address does not refer to a legacy (P2PKH) key. Message signing for SegWit and other non-P2PKH address types is not supported in this version of %1. Please check the address and try again.</source>
        <translation>Girilen adres, eski (P2PKH) bir anahtarı belirtmiyor. Bu sürümde SegWit ve diğer P2PKH olmayan %1 versiyon adres türleri için mesajla imzalama desteklenmiyor. Lütfen adresi kontrol edin ve tekrar deneyin.</translation>
    
YES, The translation contains an error in translating the format specifier %1. The original text has "%1" which refers to a variable but the translation has "%1 versiyon" which means "%1 version".

Correct translation: Girilen adres, eski (P2PKH) bir anahtarı belirtmiyor. Bu sürümde SegWit ve diğer P2PKH olmayan adres türleri için mesajla imzalama desteklenmiyor. Lütfen adresi kontrol edin ve tekrar deneyin.
```

```
        <source>Amount</source>
        <translation>Mitar</translation>
    
YES, The translation is incorrect. "Amount" in the context of Bitcoin refers to the quantity of Bitcoin, which translates to "Tutar" in Turkish.
NO
```

```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>Doğrulanıyor (%1 kere doğrulandı, önerilen doğrulama sayısı %2)</translation>
    
YES
The translation does not accurately convey the meaning of the source text. The source text is indicating the number of confirmations needed for a Bitcoin transaction, whereas the translation suggests the number of times something has been confirmed.

Correct translation: Doğrulanıyor (%1 / %2 önerilen onay)</translation>
```

```
        <source>The transaction amount is too small to send after the fee has been deducted</source>
        <translation>Bu işlem, tutar düşüldükten sonra göndermek için çok düşük</translation>
    
YES. The translation is inaccurate and grammatically incorrect.

Correct translation:
İşlem tutarı, işlem ücreti düşüldükten sonra gönderilemeyecek kadar küçüktür.
```

```
        <source>Maximum transaction weight is less than transaction weight without inputs</source>
        <translation>Maksimum işlem ağırlığı, işlem girdi ağırlığından daha küçük olmalıdır.</translation>
    
YES, The translation is inaccurate. The English sentence states that the maximum transaction weight is *less than* the transaction weight without inputs, but the Turkish translation implies it *should be less than* (olmalıdır) which is a prescriptive statement rather than a descriptive one. The phrase "işlem girdi ağırlığından" also seems to be an interpretation that is not directly in the source.

Correct translation: Maksimum işlem ağırlığı, girdisiz işlem ağırlığından düşüktür.
```

```
        <source>Error: Unable to read wallet's best block locator record</source>
        <translation>Hata: Cüzdan okunamadı en iyi blok bulucu kaydı </translation>
    
YES, The translation is grammatically incorrect and unnatural in Turkish. The word order is wrong.
Hata: Cüzdanın en iyi blok bulucu kaydı okunamadı.
```

```
        <source>Error: Unable to write solvable wallet best block locator record</source>
        <translation>Hata: Cüzdana yazılamadı en iyi blok bulucu kaydı </translation>
    
YES: The translation is missing the word "solvable" and "wallet", and has an incorrect word order for "best block locator record".
Hata: Çözülebilir cüzdana en iyi blok bulucu kaydı yazılamadı
```

```
        <source>Error: database transaction cannot be executed for wallet %s</source>
        <translation>Hata: %sCüzdan için veri tabanında işlem yapılamaz</translation>
    
YES, The translation has an issue with the placement of the format specifier. The `%s` should be placed before the word "Cüzdan" for proper sentence structure.
Hata: %s cüzdan için veri tabanında işlem yapılamaz
```

```
        <source>Failure removing transaction: %s</source>
        <translation>işlemi: %s silme başarısız oldu.</translation>
    
YES, The translation is grammatically incorrect and does not convey the intended meaning. The word order is unnatural in Turkish.

Correct translation: İşlemi kaldırma hatası: %s
```

```
        <source>Only direction was set, no permissions: '%s'</source>
        <translation>'%s' için izin yok. Sadece hedef ayarlandı.</translation>
    
YES, The translation is problematic. The meaning of "direction" and "permissions" is swapped. In the context of Bitcoin, the source sentence likely means that an action or operation has been defined with a direction (e.g., sending or receiving), but the necessary permissions for that action have not been granted. The translation suggests that permissions are absent, and only the "target" (which is a misinterpretation of "direction") has been set.

A more accurate translation would be:

'Kullanım izni yok, sadece yön ayarlandı: '%s''
```

```
        <source>Signer did not echo address</source>
        <translation>İmzalayıcı adresi belirtilmedi.</translation>
    
YES - The translation is factually incorrect and misinterprets the meaning of "echo" in this context. In Bitcoin, "echo" refers to the signer returning the address to confirm it, not simply stating or specifying it. The Turkish translation implies the address was not provided or specified.

Correct translation: İmzalayıcı adresi yinelemedi.
```

```
        <source>Signer echoed unexpected address %s</source>
        <translation>İstenmeyen %s adrese imzalama yapıldı.</translation>
    
YES, The translation is problematic because it misinterprets the meaning of "Signer echoed unexpected address %s". The source text indicates that the signer (likely a software or hardware wallet) returned an address that was not anticipated or expected, implying a potential issue or anomaly. The Turkish translation, "İstenmeyen %s adrese imzalama yapıldı" translates to "Signing was done to an unwanted %s address." This suggests that the *user* wanted to sign to an unwanted address, which is the opposite of the original meaning.

A more accurate translation would convey that the address provided by the signer was unexpected.

Correct translation: İmzalayıcı beklenmeyen %s adresini yansıttı.
```

```
        <source>Signer returned error: %s</source>
        <translation>%s İmzayıcı hatası tekrarı.</translation>
    
YES - The translation is inaccurate and uses an unnatural phrasing. The correct translation should convey that the signer returned an error.
%s İmzacı hata döndürdü.
```

```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>-paytxfee çok yüksek bir değere ayarlanmış! Bu, işlemi gönderirseniz ödeyeceğiniz işlem ücretidir.</translation>
    
YES. The translation contains extraneous information not present in the source text ("-paytxfee çok yüksek bir değere ayarlanmış!"). The translated sentence is also awkwardly phrased.

NO. Bu, işlemi gönderirseniz ödeyeceğiniz işlem ücretidir.
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Hata: Sadece izleme %s cüzdanı. tx izleme cüzdanına eklenemedi</translation>
    
YES, The translation contains erroneous content. The word order and grammar are incorrect. The correct translation should be "Hata: İzlenen işlem %s, sadece izlenen cüzdanınıza eklenemedi".

NO
```
</details>
