# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>tr</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Btr%5D%20low%20quality)


```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>Bu işlemi yapabilmek için cüzdan parolanızı girmeniz gerekmektedir
Cüzdan kilidini aç.</translation>
    
YES  
The translation is problematic because it includes two sentences instead of one, and the second sentence "Cüzdan kilidini aç." ("Unlock the wallet.") is unnecessary and not present in the source. Also, there is a missing period at the end of the first sentence, and the overall translation does not exactly correspond to the original sentence.

Correct translation:  
Bu işlemi yapabilmek için cüzdanınızın şifresini girerek cüzdan kilidini açmanız gerekmektedir.
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Cüzdan parolasının kaldırılması için girilen parola yanlış.</translation>
    
YES  
The translation is somewhat inaccurate and could be clearer. The phrase "wallet decryption" is translated as "kaldırılması," which means "removal" rather than "decryption." The correct term should be "şifre çözme" or "şifre çözme işlemi" for decryption. Also, "girilen parola" is fine, but specifying "girilmiş" or "girilen" is okay.

Correct translation:  
Cüzdan şifresinin çözülmesi için girilen parola yanlış.
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future</translation>
    
YES
The translation is not actually translated into Turkish ('tr') but instead is a copy of the English source text. This means it fails to provide the necessary localization.

Correct translation:
"Cüzdan şifre çözme için girilen parolası yanlış. İçinde null karakter (yani sıfır bayt) bulunmaktadır. Parola, bu yazılımın 25.0 öncesi bir sürümünde ayarlandıysa, lütfen sadece ilk null karaktere kadar olan karakterlerle (ilk null karakter dahil değil) tekrar deneyin. Eğer başarılı olursa, gelecekte bu sorunun önüne geçmek için lütfen yeni bir parola belirleyin."
```

```
        <source>Runaway exception</source>
        <translation>Sızıntı istisnası</translation>
    
YES  
The term "Runaway exception" in a programming or Bitcoin context usually means an exception (error) that has escaped normal handling or control, often translated as "kontrolden çıkan istisna" or "kaçan istisna." The provided translation "Sızıntı istisnası" literally means "leak exception," which is incorrect and misleading.

Correct translation:  
"Kontrolden çıkan istisna"  
or  
"Kaçan istisna"
```

```
        <source>Amount</source>
        <translation>Mitar</translation>
    
YES  
The Turkish translation "Mitar" is incorrect. The correct translation for "Amount" in this Bitcoin context is "Tutar" or "Miktar".  

Correct translation:  
Tutar
```

```
        <source>Outbound</source>
        <extracomment>An outbound connection to a peer. An outbound connection is a connection initiated by us.</extracomment>
        <translation>yurt dışı</translation>
    
YES  
The translation "yurt dışı" means "abroad" or "foreign country," which is incorrect in the context of an outbound network connection. A more accurate translation for "Outbound" (as in "outbound connection") would be "giden" or "giden bağlantı."

Correct translation:  
giden
```

```
        <source>%1 d</source>
        <translation>%1 g</translation>
    
YES  
The source uses "d" which commonly stands for "days," while "g" in Turkish is typically an abbreviation for "gram." This is incorrect in the context. The correct abbreviation for "days" in Turkish should be "gün" or "g" but as an abbreviation in technical contexts "d" is usually kept or replaced appropriately but not with "g". Since the source uses "%1 d" (likely meaning "%1 days"), the correct translation should keep the meaning consistent. The best is to use "%1 gün".

Correct translation:  
%1 gün
```

```
        <source>%1 m</source>
        <translation>%1 d</translation>
    
YES  
The source "%1 m" likely stands for "%1 meters" or minutes depending on context, but the translation replaced "m" with "d", which is not equivalent in Turkish. If "m" stands for meters, it should remain "m" because the abbreviation for meters in Turkish is also "m". If it means minutes, the abbreviation in Turkish is "dk" or spelled out as "dakika". However, since the source uses "m", typically "m" (meters) is standard and should be preserved.

Correct translation:  
%1 m
```

```
        <source>Browse transaction history</source>
        <translation>İşlem geçişini görüntüle</translation>
    
YES  
The Turkish translation is slightly inaccurate. "Transaction history" should be translated as "işlem geçmişi" rather than "işlem geçişi" (the latter means "transaction transition" or "passing of transaction," which is incorrect in this context). A more natural and accurate translation would be:

Correct translation:  
İşlem geçmişini görüntüle
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Proxy &lt;b&gt;etkinleştirildi&lt;/b&gt;: %1 </translation>
    
YES
There is a trailing space after the format specifier %1 which is unnecessary and inconsistent with the source. The translation is otherwise accurate.

Correct translation:
Proxy &lt;b&gt;etkinleştirildi&lt;/b&gt;: %1
```

```
        <source>Open URI…</source>
        <translation>URI 'ı Aç...</translation>
    
YES  
The translation incorrectly uses an apostrophe in "URI 'ı" which is not correct in Turkish. The correct suffix for the accusative case of "URI" is "-yı" (because "URI" ends with a vowel, the buffer consonant 'y' is added to avoid vowel clash). Also, the ellipsis character should be consistent; the source uses a single ellipsis (…), so the translation should do the same.

Correct translation:  
URI’yı Aç…
```

```
        <source>Sending addresses</source>
        <translation> Adresleri gönderme</translation>
    
YES
There is a leading space before "Adresleri" which is a formatting issue. Also, the translation is accurate but should not have any leading whitespace.

Correct translation:
Adresleri gönderme
```

```
        <source>Open a bitcoin: URI</source>
        <translation>Bitcoin’i aç.</translation>
    
YES  
The translation "Bitcoin’i aç." means "Open the Bitcoin" or "Open bitcoin" but does not convey that it is a URI (Uniform Resource Identifier) that should be opened. The source explicitly says "Open a bitcoin: URI," so the translation should mention "URI" as well for clarity and accuracy. Also, the apostrophe ’ after "Bitcoin" is incorrect in Turkish and not needed.

Correct translation:  
"bitcoin URI'sini aç"  
or  
"bitcoin: URI'sini aç"
```

```
        <source>HD key generation is &lt;b&gt;enabled&lt;/b&gt;</source>
        <translation>HD anahtar üreticiler &lt;b&gt;kullanilabilir&lt;/b&gt;</translation>
    
YES  
The translation is inaccurate and slightly misleading. The source text states "HD key generation is enabled," which means the process of generating HD keys is active or turned on. The translation "HD anahtar üreticiler kullanılabilir" means "HD key generators are available," which changes the meaning. Also, "kullanilabilir" should have Turkish-specific characters as "kullanılabilir."  

Correct translation:  
HD anahtar oluşturma &lt;b&gt;etkinleştirildi&lt;/b&gt;
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>HD anahtar üreticiler &lt;b&gt;kullanılamaz&lt;/b&gt;</translation>
    
YES
The translation is inaccurate and misleading. The source means "HD key generation is disabled," implying the feature is turned off. The current translation "HD anahtar üreticiler kullanılmaz" translates to "HD key generators are unusable," which changes the meaning and is grammatically incorrect (the word "üreticiler" is plural "generators," but the source refers to "generation"). 

Correct translation:
HD anahtar üretimi &lt;b&gt;devre dışı&lt;/b&gt;
```

```
        <source>Private key &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>Gizli anahtar oluşturma &lt;b&gt;devre dışı&lt;/b&gt;</translation>
    
YES  
The source text "Private key <b>disabled</b>" indicates that the private key is disabled, but the translation "Gizli anahtar oluşturma <b>devre dışı</b>" means "Private key creation disabled," which adds the meaning of "creation" that is not present in the source. The correct translation should reflect that the private key itself is disabled, not the creation process.

Correct translation:  
Gizli anahtar &lt;b&gt;devre dışı&lt;/b&gt;
```

```
        <source>Change:</source>
        <translation>Değiştir</translation>
    
YES  
The English term "Change:" in the Bitcoin context refers to the remaining amount returned to the sender after a transaction, not the verb "Change" as in "to change something." The translation "Değiştir" is the imperative verb "Change" (command form), which is incorrect here. The correct translation should be a noun indicating "change" as in monetary change or remaining balance.

Correct translation:  
"Değişim:" or better, the commonly used term in Turkish Bitcoin context: "Kalan:" or "Artan:"  
However, the most accurate and widely used translation for "Change:" in Bitcoin wallets is "Para Üstü:" or simply "Change:" left untranslated but typically "Para Üstü:" is used in common Turkish wallets.

Hence, the best translation here is:  
"Para Üstü:"
```

```
        <source>(un)select all</source>
        <translation>tümünü seçmek</translation>
    
YES  
The English phrase "(un)select all" implies toggling the selection state, i.e., selecting all if none are selected or unselecting all if all are selected. The Turkish translation "tümünü seçmek" only means "select all" and does not convey the toggle or unselect meaning.

Correct translation:  
"(tümünü) seç / seçimi kaldır"  
or simply  
"Tümünü seç / seçimi kaldır"  
to express the toggle action clearly.
```

```
        <source>Amount</source>
        <translation>Mitar</translation>
    
YES  
The Turkish translation "Mitar" is incorrect. The correct translation for "Amount" in this Bitcoin context is "Tutar" or "Miktar".  

Correct translation:  
Tutar
```

```
        <source>Copy transaction ID and output index</source>
        <translation>İşlem ID ve çıktı içeriğini kopyala</translation>
    
YES  
The translation has a minor inaccuracy. The phrase "output index" refers to an index number, not "output content" ("çıktı içeriği"). The correct translation should use "çıktı indeksini" instead of "çıktı içeriğini."

Correct translation:  
İşlem ID ve çıktı indeksini kopyala
```

```
        <source>(change)</source>
        <translation>(değiştir)</translation>
    
YES  
The English word "(change)" in the Bitcoin context refers to the "change amount" returned in a transaction, not the verb "to change" or "replace." The correct Turkish translation in this context is "(değişiklik)" or "(para üstü)" rather than "(değiştir)" which is the imperative verb "change!" or "replace!" and does not fit here.

Correct translation:  
(change)  
(değişiklik) or (para üstü)
```

```
        <source>Disable Private Keys</source>
        <translation>Özel Kilidi (Private Key) kaldır</translation>
    
YES  
The translation is inaccurate and somewhat misleading. "Disable Private Keys" means to deactivate or turn off private keys functionality. The provided Turkish translation "Özel Kilidi (Private Key) kaldır" implies "Remove/remove the Private Lock," which is not the correct meaning. Also, it mixes Turkish and English ("Private Key") unnecessarily.

A better translation would be:  
"Özel Anahtarları Devre Dışı Bırak"
```

```
        <source>Welcome</source>
        <translation>Hoş geldiniz </translation>
    
YES
There is unnecessary trailing whitespace after "Hoş geldiniz".

Correct translation:
Hoş geldiniz
```

```
        <source>Prune block storage to</source>
        <translation>Depolamayı küçültmek engellemek için </translation>
    
YES  
The Turkish translation does not accurately reflect the original English phrase. The phrase "Prune block storage to" in the Bitcoin context means to reduce the amount of block data stored, typically indicating "pruning" or trimming the blockchain data to save space. The current translation "Depolamayı küçültmek engellemek için" translates back roughly as "To prevent reducing the storage," which is incorrect and confusing.

A more accurate and concise translation would be:  
"Blok depolamayı şu seviyeye kırp" or simply  
"Blok depolamayı kırp"  

If the original phrase is a prefix to a size or value to follow, the literal translation could be:  
"Blok depolamayı şu kadara kırp"  

So a better suggestion:  
"Blok depolamayı küçült"  
or  
"Blok depolamayı kırp"
```

```
        <source>Spend unconfirmed change</source>
        <translation> Onaylanmamış bozuk parayı harcayın</translation>
    
YES
There is an unnecessary leading space in the translation before "Onaylanmamış". Also, "bozuk para" as "change" in the Bitcoin context is better translated as "para üstü" or "değişim" to reflect "change" from a transaction. The most appropriate translation would be:

Onaylanmamış para üstünü harcayın
```

```
        <source>Mined balance that has not yet matured</source>
        <translation>ödenilmemiş miktar</translation>
    
YES  
The translation "ödenilmemiş miktar" means "unpaid amount," which is not an accurate translation of "Mined balance that has not yet matured." The correct translation should reflect the idea of a mined balance that is still immature or not yet spendable.

Correct translation:  
"Henüz olgunlaşmamış madencilik bakiyesi"
```

```
        <source>Sends %1 to %2</source>
        <translation>Gönderiler %1 ile %2</translation>
    
YES  
The translation is inaccurate and awkward. "Gönderiler" means "shipments" or "sendings" (plural noun), which is incorrect here. The correct translation should convey the verb "Sends %1 to %2" properly as an action. The correct translation would be:  
"%1'i %2'ye gönderir"
```

```
        <source>Outbound</source>
        <extracomment>An Outbound Connection to a Peer.</extracomment>
        <translation>yurt dışı</translation>
    
YES  
The translation "yurt dışı" means "abroad" or "overseas," which is incorrect in this technical context. The source "Outbound" here refers to an outgoing connection or direction in a network context, not geographical location. A better translation would be:  

Correct translation:  
"Giden"
```

```
        <source>Change:</source>
        <translation>Değiştir</translation>
    
YES  
The English term "Change:" in the Bitcoin context refers to the remaining amount returned to the sender after a transaction, not the verb "Change" as in "to change something." The translation "Değiştir" is the imperative verb "Change" (command form), which is incorrect here. The correct translation should be a noun indicating "change" as in monetary change or remaining balance.

Correct translation:  
"Değişim:" or better, the commonly used term in Turkish Bitcoin context: "Kalan:" or "Artan:"  
However, the most accurate and widely used translation for "Change:" in Bitcoin wallets is "Para Üstü:" or simply "Change:" left untranslated but typically "Para Üstü:" is used in common Turkish wallets.

Hence, the best translation here is:  
"Para Üstü:"
```

```
        <source>Signatures - Sign / Verify a Message</source>
        <translation>İmzalar - Giri‭s / Mesaji Onayla</translation>
    
YES  
There are two issues in the translation:  
1. The word "Giri‭s" contains a hidden right-to-left mark (U+202C) which breaks the text display and should be removed. It should be "Giriş".  
2. The phrase "Mesaji Onayla" is missing the correct Turkish characters. The correct spelling is "Mesajı Onayla".  

Correct translation:  
İmzalar - Giriş / Mesajı Onayla
```

```
        <source>The entered address does not refer to a legacy (P2PKH) key. Message signing for SegWit and other non-P2PKH address types is not supported in this version of %1. Please check the address and try again.</source>
        <translation>Girilen adres, eski (P2PKH) bir anahtarı belirtmiyor. Bu sürümde SegWit ve diğer P2PKH olmayan %1 versiyon adres türleri için mesajla imzalama desteklenmiyor. Lütfen adresi kontrol edin ve tekrar deneyin.</translation>
    
YES
The Turkish translation has a misplaced phrase order and unclear phrasing. Specifically, "diğer P2PKH olmayan %1 versiyon adres türleri" is awkward and misleading. It incorrectly places "%1 versiyon" before "adres türleri," which causes confusion. The source means "address types that are SegWit and other non-P2PKH types," and "%1" refers to the software version.

Correct translation:
Girilen adres, eski (P2PKH) bir anahtara ait değildir. Bu %1 sürümünde SegWit ve diğer P2PKH olmayan adres türleri için mesaj imzalama desteklenmemektedir. Lütfen adresi kontrol edin ve tekrar deneyin.
```

```
        <source>Amount</source>
        <translation>Mitar</translation>
    
YES  
The Turkish translation "Mitar" is incorrect. The correct translation for "Amount" in this Bitcoin context is "Tutar" or "Miktar".  

Correct translation:  
Tutar
```

```
        <source>The transaction amount is too small to send after the fee has been deducted</source>
        <translation>Bu işlem, tutar düşüldükten sonra göndermek için çok düşük</translation>
    
YES  
The translation is not entirely accurate and is somewhat unclear. The original English means "The transaction amount is too small to send after the fee has been deducted," but the Turkish translation says "This transaction is too low for sending after the amount has been deducted," which is confusing. The order and wording should be improved for clarity and correctness.

Correct translation:  
"Ücret düşüldükten sonra gönderilecek işlem tutarı çok küçük"
```

```
        <source>Maximum transaction weight is less than transaction weight without inputs</source>
        <translation>Maksimum işlem ağırlığı, işlem girdi ağırlığından daha küçük olmalıdır.</translation>
    
YES
The translation adds "olmalıdır" ("must be"), which is not present in the original source and changes the meaning. The source states a factual comparison ("Maximum transaction weight is less than transaction weight without inputs") without implying a requirement.

Correct translation:
Maksimum işlem ağırlığı, girişler olmadan işlem ağırlığından daha azdır.
```

```
        <source>Error: Unable to read wallet's best block locator record</source>
        <translation>Hata: Cüzdan okunamadı en iyi blok bulucu kaydı </translation>
    
YES
The translation is awkward and incomplete, and there is a spacing issue before the final word. Also, the phrase "wallet's best block locator record" is not accurately conveyed. A better translation would be:

Hata: Cüzdanın en iyi blok bulucu kaydı okunamadı
```

```
        <source>Error: Unable to write solvable wallet best block locator record</source>
        <translation>Hata: Cüzdana yazılamadı en iyi blok bulucu kaydı </translation>
    
YES
The Turkish translation is inaccurate and awkward. It omits that the error relates to writing a "solvable wallet best block locator record" and does not preserve the technical meaning clearly. Also, spacing is problematic: a trailing space exists before closing the tag.

Correct translation:
Hata: Çözülebilir cüzdanın en iyi blok bulucu kaydı yazılamadı
```

```
        <source>Error: database transaction cannot be executed for wallet %s</source>
        <translation>Hata: %sCüzdan için veri tabanında işlem yapılamaz</translation>
    
YES  
The translation has spacing issues and an incorrect word order. The placeholder %s should be separated by a space from the rest of the sentence, and the sentence should flow naturally in Turkish. Also, "veri tabanı" should be two words. A better translation would be:

Hata: %s için veri tabanı işlemi gerçekleştirilemiyor
```

```
        <source>Failure removing transaction: %s</source>
        <translation>işlemi: %s silme başarısız oldu.</translation>
    
YES  
The translation has a lowercase initial letter, while the source starts with an uppercase letter, which is inconsistent. Also, the phrase can be made more natural in Turkish by reordering.

Correct translation:  
İşlem %s silme başarısında hata oluştu.
```

```
        <source>Signer did not echo address</source>
        <translation>İmzalayıcı adresi belirtilmedi.</translation>
    
YES  
The English text "Signer did not echo address" means that the signer failed to repeat or confirm the address, implying an action that was not performed. The provided Turkish translation "İmzalayıcı adresi belirtilmedi." translates to "The signer’s address was not specified," which changes the meaning and does not convey the original intent.

Correct translation:  
"İmzalayıcı adresi geri yansıtmadı."  
or more contextually natural:  
"İmzalayıcı adresi tekrar etmedi."
```

```
        <source>Signer echoed unexpected address %s</source>
        <translation>İstenmeyen %s adrese imzalama yapıldı.</translation>
    
YES
The Turkish translation does not accurately reflect the original meaning. The source means that the signer returned or echoed back an unexpected address (address %s). The translation implies "an unwanted address was signed," which alters the meaning and introduces confusion.

Correct translation:
İmzacı beklenmeyen adres %s'i geri gönderdi.
```

```
        <source>Signer returned error: %s</source>
        <translation>%s İmzayıcı hatası tekrarı.</translation>
    
YES  
The translation incorrectly places the format specifier %s at the start, which should correspond to the error message in the source. Also, the phrase "İmzayıcı hatası tekrarı." is ungrammatical and unnatural in Turkish. A more accurate and natural translation would be:  
"İmzayıcı hata döndürdü: %s"
```

```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>-paytxfee çok yüksek bir değere ayarlanmış! Bu, işlemi gönderirseniz ödeyeceğiniz işlem ücretidir.</translation>
    
YES  
The translation adds extra information not present in the source ("-paytxfee çok yüksek bir değere ayarlanmış!"), which could confuse the user. Also, the source is a single neutral sentence, but the translation includes an exclamation and a warning not in the original text. Furthermore, the sentence structure could be smoother.

Correct translation:  
"Bu, bir işlem gönderirseniz ödeyeceğiniz işlem ücretidir."
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Hata: Sadece izleme %s cüzdanı. tx izleme cüzdanına eklenemedi</translation>
    
YES  
The translation is awkward and partially incorrect. It breaks the phrase unnaturally and mistranslates parts of it. The original means "Error: Could not add watch-only transaction %s to watch-only wallet." A correct and fluent Turkish translation would be:  
"Hata: İzleme işlemi %s, sadece izleme cüzdanına eklenemedi."
```
</details>
