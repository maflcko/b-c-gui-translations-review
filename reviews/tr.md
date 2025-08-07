# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>tr</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Btr%5D%20low%20quality)


```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>Bu işlemi yapabilmek için cüzdan parolanızı girmeniz gerekmektedir
Cüzdan kilidini aç.</translation>
    
YES
The Turkish translation is problematic for two reasons:
1. It is split into two sentences with a line break, adding an extra instructional style ("Cüzdan kilidini aç.") which is not present in the source.
2. The source text is a single explanatory sentence, not an imperative or instructional phrase.

Correct translation:
Bu işlemi gerçekleştirmek için cüzdan parolanızı girerek cüzdanın kilidini açmanız gerekir.
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Cüzdan parolasının kaldırılması için girilen parola yanlış.</translation>
    
YES
The translation is not accurate. The source sentence is about the decryption of the wallet, not the removal of the password. The Turkish translation misrepresents the action as "removal of the wallet password".

Correct translation:
Cüzdanın şifresini çözmek için girilen parola yanlıştı.
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future</translation>
    
SPAM
The translation is not in Turkish ('tr') but instead repeats the English source text verbatim.

Correct translation:
Cüzdanın şifresini çözmek için girilen parola yanlış. Parola bir null karakter (yani sıfır bayt) içeriyor. Eğer parola bu yazılımın 25.0'dan önceki bir sürümüyle ayarlandıysa, lütfen yeniden yalnızca ilk null karaktere kadar olan (ilk null karakter dahil olmadan) karakterlerle deneyin. Eğer başarılı olursa, gelecekte bu sorunun tekrar yaşanmaması için lütfen yeni bir parola belirleyin.
```

```
        <source>Runaway exception</source>
        <translation>Sızıntı istisnası</translation>
    
YES
The translation of "Runaway exception" as "Sızıntı istisnası" is incorrect. The term "runaway" in this context refers to something uncontrolled or out of bounds, not a "leak" ("sızıntı"). A better translation would be:

Kontrolden çıkan istisna

Correct translation:
Kontrolden çıkan istisna
```

```
        <source>Amount</source>
        <translation>Mitar</translation>
    
YES
The Turkish translation "Mitar" is incorrect and appears to be a misspelling or unrelated word. The correct translation for "Amount" is "Tutar".

Correct translation:
Tutar
```

```
        <source>Outbound</source>
        <extracomment>An outbound connection to a peer. An outbound connection is a connection initiated by us.</extracomment>
        <translation>yurt dışı</translation>
    
YES
The translation "yurt dışı" means "abroad" or "foreign country" in Turkish, which is incorrect in this context. The correct translation for "Outbound" (as in an outbound connection) should be "Giden" or "Dışa giden".

Correct translation:
Giden
```

```
        <source>%1 d</source>
        <translation>%1 g</translation>
    
YES
The source uses 'd' (most likely meaning 'day' in English), but the translation uses 'g' (which is incorrect; the correct abbreviation for 'gün' in Turkish is 'gün' or 'g'). However, 'g' is ambiguous and not standard. It would be clearer and more accurate to use 'gün', as 'g' could be confused with 'gram' or is not commonly used as an abbreviation for 'gün' in UI context.

Correct translation:
%1 gün
```

```
        <source>%1 m</source>
        <translation>%1 d</translation>
    
YES
The translation is incorrect because "m" in the source likely refers to "minutes" (dakika in Turkish), but the translation uses "d" which is not an abbreviation for "dakika" in Turkish. The correct abbreviation is "dk".

Correct translation:
%1 dk
```

```
        <source>Browse transaction history</source>
        <translation>İşlem geçişini görüntüle</translation>
    
YES
The translation "İşlem geçişini görüntüle" is inaccurate. "İşlem geçişi" does not correctly represent "transaction history." The correct term is "işlem geçmişi." Additionally, "Browse" should be translated as "Gözat" or "İncele" instead of "görüntüle" (which is "view").

Correct translation:
İşlem geçmişine göz at
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Proxy &lt;b&gt;etkinleştirildi&lt;/b&gt;: %1 </translation>
    
YES
There is an extra space at the end of the translation, which causes a whitespace format issue.

Correct translation:
Proxy &lt;b&gt;etkinleştirildi&lt;/b&gt;: %1
```

```
        <source>Open URI…</source>
        <translation>URI 'ı Aç...</translation>
    
YES
There is a whitespace format issue. In Turkish, the correct formatting would be "URI'yi Aç..." without the extra space between "URI" and the apostrophe, and using the correct accusative suffix.

Correct translation:
URI'yi Aç...
```

```
        <source>Sending addresses</source>
        <translation> Adresleri gönderme</translation>
    
YES
There is a whitespace issue (leading space) and the translation reverses the order of words, making it sound like "sending the addresses" rather than "addresses for sending." The correct translation should use the noun form to match the menu context (as in "Gönderim adresleri").

Correct translation:
Gönderim adresleri
```

```
        <source>Open a bitcoin: URI</source>
        <translation>Bitcoin’i aç.</translation>
    
YES
The translation "Bitcoin’i aç." is inaccurate. The phrase "Open a bitcoin: URI" refers specifically to opening a bitcoin URI (Uniform Resource Identifier), not just "open Bitcoin". The translation omits "URI", which could be important for user clarity.

Correct translation:
Bir bitcoin: URI’si aç
```

```
        <source>HD key generation is &lt;b&gt;enabled&lt;/b&gt;</source>
        <translation>HD anahtar üreticiler &lt;b&gt;kullanilabilir&lt;/b&gt;</translation>
    
YES
The translation is not accurate. "HD anahtar üreticiler" is incorrect; it means "HD key generators", which is not the intended meaning. Also, "kullanilabilir" is a misspelling; it should be "kullanılabilir". However, more accurately, "enabled" in this context is best translated as "etkin".

Correct translation:
HD anahtar oluşturma &lt;b&gt;etkin&lt;/b&gt;
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>HD anahtar üreticiler &lt;b&gt;kullanılamaz&lt;/b&gt;</translation>
    
YES
The translation is inaccurate. "Üreticiler" means "producers" or "generators," which is not correct in this context. Also, the wording is awkward and does not convey "HD key generation is disabled" clearly.

Correct translation:
HD anahtar üretimi &lt;b&gt;devre dışı&lt;/b&gt;
```

```
        <source>Private key &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>Gizli anahtar oluşturma &lt;b&gt;devre dışı&lt;/b&gt;</translation>
    
YES
The translation is inaccurate. The source says "Private key <b>disabled</b>", which should just state that the private key is disabled, but the translation says "Gizli anahtar oluşturma <b>devre dışı</b>", which means "Private key creation <b>disabled</b>". The phrase "oluşturma" (creation) is not in the source.

Correct translation:
Gizli anahtar &lt;b&gt;devre dışı&lt;/b&gt;
```

```
        <source>Change:</source>
        <translation>Değiştir</translation>
    
YES
The translation is inaccurate. In the context of Bitcoin, "Change:" refers to the leftover amount (change output) in a transaction, not the verb "Değiştir" ("Change" as in "Modify"). The correct Turkish translation for "Change:" (as in the noun for Bitcoin transaction change) is "Para Üstü:" or "Para üstü:".

Correct translation:
Para Üstü:
```

```
        <source>(un)select all</source>
        <translation>tümünü seçmek</translation>
    
YES
The translation "tümünü seçmek" means "to select all" in Turkish, but it does not properly represent the toggling implied by "(un)select all" (i.e., select all or deselect all).

Correct translation:
Tümünü (seç/deseç)
or, more commonly:
Tümünü seç / seçimi kaldır
```

```
        <source>Amount</source>
        <translation>Mitar</translation>
    
YES
The Turkish translation "Mitar" is incorrect and appears to be a misspelling or unrelated word. The correct translation for "Amount" is "Tutar".

Correct translation:
Tutar
```

```
        <source>Copy transaction ID and output index</source>
        <translation>İşlem ID ve çıktı içeriğini kopyala</translation>
    
YES
The translation is inaccurate. "output index" is translated incorrectly as "çıktı içeriği" which means "output content". The correct translation for "output index" in the Bitcoin context is "çıktı indeksi".

Correct translation:
İşlem kimliğini ve çıktı indeksini kopyala
```

```
        <source>(change)</source>
        <translation>(değiştir)</translation>
    
YES
The word "change" in the Bitcoin context usually refers to the remaining balance returned to the sender in a transaction, not the verb "to change." The translation as "(değiştir)" is incorrect, as it means "(change [command/verb])" in Turkish.

Correct translation:
(değişim)
```

```
        <source>Disable Private Keys</source>
        <translation>Özel Kilidi (Private Key) kaldır</translation>
    
YES
The translation is inaccurate. "Disable Private Keys" should be translated as "Özel Anahtarları Devre Dışı Bırak" instead of "Özel Kilidi (Private Key) kaldır", which literally means "Remove Private Lock (Private Key)" and is both misleading and incorrect.

Correct translation:
Özel Anahtarları Devre Dışı Bırak
```

```
        <source>Welcome</source>
        <translation>Hoş geldiniz </translation>
    
YES
There is an unnecessary trailing whitespace at the end of the translation.

Correct translation:
Hoş geldiniz
```

```
        <source>Prune block storage to</source>
        <translation>Depolamayı küçültmek engellemek için </translation>
    
YES
The translation is inaccurate and introduces an incorrect meaning. The English source means "reduce/prune the block storage to [a certain size]," and the Turkish translation suggests both "shrinking" and "blocking" in a nonsensical way. Additionally, the translation omits to translate "block" as in "blockchain block". 

Correct translation:
Blok depolamasını şuna küçült:
or
Blok depolamasını şu boyuta küçült:
(if followed by a size indication)
```

```
        <source>Spend unconfirmed change</source>
        <translation> Onaylanmamış bozuk parayı harcayın</translation>
    
YES
There is a formatting issue: there is an unnecessary leading space before the translation, and "bozuk para" is not the most appropriate term for "change" in a Bitcoin context. "Change" refers to the leftover amount from a transaction, not "coins" or "small change." A better translation would be "onaylanmamış bakiyeyi" or "onaylanmamış para üstünü".

Correct translation:
Onaylanmamış para üstünü harcayın
```

```
        <source>Mined balance that has not yet matured</source>
        <translation>ödenilmemiş miktar</translation>
    
YES
The translation is inaccurate and problematic. "ödenilmemiş miktar" means "unpaid amount", which does not communicate the intended meaning of "Mined balance that has not yet matured" — i.e., newly mined coins that cannot yet be spent due to not reaching maturity.

Correct translation:
Henüz olgunlaşmamış kazılmış bakiye
```

```
        <source>Sends %1 to %2</source>
        <translation>Gönderiler %1 ile %2</translation>
    
YES
The translation is incorrect. The English source means "Sends %1 to %2," indicating an action where %1 (usually an amount) is sent to %2 (usually an address or recipient). The current translation means "Shipments with %1 and %2" or "The shipments with %1 by %2", which is not accurate.

Correct translation:
%1, %2'ye gönderiyor
or
%1, %2 adresine gönderiliyor
```

```
        <source>Outbound</source>
        <extracomment>An Outbound Connection to a Peer.</extracomment>
        <translation>yurt dışı</translation>
    
YES
The translation "yurt dışı" means "abroad" in Turkish, which is incorrect in the context of Bitcoin networking. The term "Outbound" here refers to "dışa giden" or "giden" (i.e., connections initiated from the user's side). 

Correct translation:
Giden
```

```
        <source>Change:</source>
        <translation>Değiştir</translation>
    
YES
The translation is inaccurate. In the context of Bitcoin, "Change:" refers to the leftover amount (change output) in a transaction, not the verb "Değiştir" ("Change" as in "Modify"). The correct Turkish translation for "Change:" (as in the noun for Bitcoin transaction change) is "Para Üstü:" or "Para üstü:".

Correct translation:
Para Üstü:
```

```
        <source>Signatures - Sign / Verify a Message</source>
        <translation>İmzalar - Giri‭s / Mesaji Onayla</translation>
    
YES
There are several issues:
1. "Giri‭s" should be "İmzala" for "Sign".
2. "Mesaji" should have proper Turkish capitalization and diacritics, i.e., "Mesajı".
3. The slash formatting should match the source and should not have irregular spacing or invisible characters.

Correct translation:
İmzalar - İmzala / Mesajı Doğrula
```

```
        <source>The entered address does not refer to a legacy (P2PKH) key. Message signing for SegWit and other non-P2PKH address types is not supported in this version of %1. Please check the address and try again.</source>
        <translation>Girilen adres, eski (P2PKH) bir anahtarı belirtmiyor. Bu sürümde SegWit ve diğer P2PKH olmayan %1 versiyon adres türleri için mesajla imzalama desteklenmiyor. Lütfen adresi kontrol edin ve tekrar deneyin.</translation>
    
YES
The translation is mostly accurate but has an awkward and partially incorrect phrase: "diğer P2PKH olmayan %1 versiyon adres türleri" which misplaces "%1", making it reference the 'address types' rather than the application version, as intended. Also, "%1" should appear exactly as in the original, preserving its position.

Correct translation:
Girilen adres, eski (P2PKH) bir anahtara karşılık gelmiyor. Bu %1 sürümünde SegWit ve diğer P2PKH olmayan adres türleri için mesaj imzalama desteklenmiyor. Lütfen adresi kontrol edin ve tekrar deneyin.
```

```
        <source>Amount</source>
        <translation>Mitar</translation>
    
YES
The Turkish translation "Mitar" is incorrect and appears to be a misspelling or unrelated word. The correct translation for "Amount" is "Tutar".

Correct translation:
Tutar
```

```
        <source>The transaction amount is too small to send after the fee has been deducted</source>
        <translation>Bu işlem, tutar düşüldükten sonra göndermek için çok düşük</translation>
    
YES
The translation does not accurately convey the meaning of the source sentence. The original states that the transaction amount is too small to send after the fee has been deducted, but the translation incorrectly says "after the amount has been deducted," and also lacks proper grammar.

Correct translation:
İşlem tutarı, ücret düşüldükten sonra göndermek için çok küçük.
```

```
        <source>Maximum transaction weight is less than transaction weight without inputs</source>
        <translation>Maksimum işlem ağırlığı, işlem girdi ağırlığından daha küçük olmalıdır.</translation>
    
YES
The translation does not accurately reflect the original English meaning. The English says the "maximum transaction weight is less than transaction weight without inputs," which indicates an error state (i.e., maximum is less than a minimum required baseline, which is not permitted). The Turkish translation incorrectly adds "olmalıdır" (must be), making it a recommendation rather than an error.

Correct translation:
Maksimum işlem ağırlığı, girdiler hariç işlem ağırlığından daha küçük.
```

```
        <source>Error: Unable to read wallet's best block locator record</source>
        <translation>Hata: Cüzdan okunamadı en iyi blok bulucu kaydı </translation>
    
YES
The translation distorts the sentence structure, leading to unnatural wording and a loss of meaning. The phrase "Cüzdan okunamadı en iyi blok bulucu kaydı" is both unclear and grammatically incorrect. It translates back as "Wallet could not be read best block locator record," which does not accurately convey the original error.

Correct translation:
Hata: Cüzdanın en iyi blok bulucu kaydı okunamadı
```

```
        <source>Error: Unable to write solvable wallet best block locator record</source>
        <translation>Hata: Cüzdana yazılamadı en iyi blok bulucu kaydı </translation>
    
YES
The Turkish translation is grammatically awkward and does not clearly convey the meaning of the original sentence. The phrase "Cüzdana yazılamadı en iyi blok bulucu kaydı" is confusing and the word order is incorrect. The format specifier is preserved, but the meaning is not accurately conveyed.

Correct translation:
Hata: Çözülebilir cüzdan için en iyi blok bulucu kaydı yazılamıyor
```

```
        <source>Error: database transaction cannot be executed for wallet %s</source>
        <translation>Hata: %sCüzdan için veri tabanında işlem yapılamaz</translation>
    
YES
There is a spacing issue between "%s" and "Cüzdan"—they should be separated by a space. Also, "veri tabanında" should be "veritabanı" for proper usage in Turkish. 

Correct translation:
Hata: %s cüzdanı için veritabanı işlemi gerçekleştirilemiyor
```

```
        <source>Failure removing transaction: %s</source>
        <translation>işlemi: %s silme başarısız oldu.</translation>
    
YES
The translation introduces a word order issue that makes it sound unnatural in Turkish. The source message starts with "Failure removing", but the Turkish version puts "işlemi" (the transaction) first, which breaks clarity. Also, the proper format specifier (%s) is used correctly. A more accurate and natural translation would be:

İşlem silinirken hata oluştu: %s

Or, alternatively:

İşlemi silme başarısız oldu: %s

But if matching closer to the source:

İşlem silinirken başarısız olundu: %s

Therefore, the translation is problematic due to awkward sentence construction.

Correct translation:
İşlem silinirken hata oluştu: %s
```

```
        <source>Signer did not echo address</source>
        <translation>İmzalayıcı adresi belirtilmedi.</translation>
    
YES
The translation is incorrect. The original English means that the signer did not return (echo) the address, but the translation says "The signer's address was not specified", which is a different meaning.

Correct translation:
İmzalayıcı adresi yinelemedi.
```

```
        <source>Signer echoed unexpected address %s</source>
        <translation>İstenmeyen %s adrese imzalama yapıldı.</translation>
    
YES
The translation reverses the agent and context. The original means the signer *returned* an unexpected address, not that signing was performed to an unwanted address. "Echoed" should be translated as "yansıttı" or "geri verdi", meaning the signer *responded with* the address.

Correct translation:
İmzalayıcı beklenmeyen bir adres (%s) geri verdi.
```

```
        <source>Signer returned error: %s</source>
        <translation>%s İmzayıcı hatası tekrarı.</translation>
    
YES
The translation is incorrect. "%s İmzayıcı hatası tekrarı." does not accurately convey "Signer returned error: %s" and the word "tekrarı" (repetition) is inappropriate here. The format specifier "%s" should also be retained in the correct position.

Correct translation:
İmzacı hata döndürdü: %s
```

```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>-paytxfee çok yüksek bir değere ayarlanmış! Bu, işlemi gönderirseniz ödeyeceğiniz işlem ücretidir.</translation>
    
YES
The Turkish translation adds information ("-paytxfee çok yüksek bir değere ayarlanmış!") that is not in the original English string, making it inaccurate. The translation should only render the given sentence.

Correct translation:
Bu, bir işlem gönderirseniz ödeyeceğiniz işlem ücretidir.
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Hata: Sadece izleme %s cüzdanı. tx izleme cüzdanına eklenemedi</translation>
    
YES
The Turkish translation is problematic. It is not grammatically correct, and the structure is unclear. The phrase "Sadece izleme %s cüzdanı. tx izleme cüzdanına eklenemedi" is not natural in Turkish and does not reflect the source content accurately. Additionally, the format specifier %s is placed awkwardly.

Correct translation:
Hata: Sadece izlenen tx %s, sadece izlenen cüzdana eklenemedi
```
</details>

Number of issues: 43.
