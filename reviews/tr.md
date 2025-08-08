# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>tr</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Btr%5D%20low%20quality)


<!-- cache_translation_check_tr_9b4cf03f8fb6d12adc2e198e1346649693846e8454a7c143143339ba61d223e1 -->
```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>Bu işlemi yapabilmek için cüzdan parolanızı girmeniz gerekmektedir
Cüzdan kilidini aç.</translation>
    
ERR
The Turkish translation is problematic for two reasons:
1. It is split into two sentences with a line break, adding an extra instructional style ("Cüzdan kilidini aç.") which is not present in the source.
2. The source text is a single explanatory sentence, not an imperative or instructional phrase.

Correct translation:
Bu işlemi gerçekleştirmek için cüzdan parolanızı girerek cüzdanın kilidini açmanız gerekir.
```

<!-- cache_translation_check_tr_2efc0b72ff5b3b1e3005375b90ca300ccf5efa5fb545699fedf1368ec6b27554 -->
```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Cüzdan parolasının kaldırılması için girilen parola yanlış.</translation>
    
ERR
The translation is not accurate. The source sentence is about the decryption of the wallet, not the removal of the password. The Turkish translation misrepresents the action as "removal of the wallet password".

Correct translation:
Cüzdanın şifresini çözmek için girilen parola yanlıştı.
```

<!-- cache_translation_check_tr_10d4cfe4c6b38a0014e17ca0ceca1defffc2cf183e3ee5f12817665435302b69 -->
```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future</translation>
    
SPAM
The translation is not in Turkish ('tr') but instead repeats the English source text verbatim.

Correct translation:
Cüzdanın şifresini çözmek için girilen parola yanlış. Parola bir null karakter (yani sıfır bayt) içeriyor. Eğer parola bu yazılımın 25.0'dan önceki bir sürümüyle ayarlandıysa, lütfen yeniden yalnızca ilk null karaktere kadar olan (ilk null karakter dahil olmadan) karakterlerle deneyin. Eğer başarılı olursa, gelecekte bu sorunun tekrar yaşanmaması için lütfen yeni bir parola belirleyin.
```

<!-- cache_translation_check_tr_aa6d0105b1cd0024713b070f0219cbdd28e024461f357f665e91c55800660681 -->
```
        <source>Runaway exception</source>
        <translation>Sızıntı istisnası</translation>
    
ERR
The translation of "Runaway exception" as "Sızıntı istisnası" is incorrect. The term "runaway" in this context refers to something uncontrolled or out of bounds, not a "leak" ("sızıntı"). A better translation would be:

Kontrolden çıkan istisna

Correct translation:
Kontrolden çıkan istisna
```

<!-- cache_translation_check_tr_49e6a94f85dd8f94424cf75e54c5e5761b4f381c2d71d88a7af141f0a6d2f2fe -->
```
        <source>Amount</source>
        <translation>Mitar</translation>
    
ERR
The Turkish translation "Mitar" is incorrect and appears to be a misspelling or unrelated word. The correct translation for "Amount" is "Tutar".

Correct translation:
Tutar
```

<!-- cache_translation_check_tr_158eeea95e6598390d7f78a44fef6cfef59b216f8d987e0a1a7790db60dd8b78 -->
```
        <source>Outbound</source>
        <extracomment>An outbound connection to a peer. An outbound connection is a connection initiated by us.</extracomment>
        <translation>yurt dışı</translation>
    
ERR
The translation "yurt dışı" means "abroad" or "foreign country" in Turkish, which is incorrect in this context. The correct translation for "Outbound" (as in an outbound connection) should be "Giden" or "Dışa giden".

Correct translation:
Giden
```

<!-- cache_translation_check_tr_ef91c24149e35661c639c886d5c205418a9816844def6b36d25eb8d3afd25c3b -->
```
        <source>%1 d</source>
        <translation>%1 g</translation>
    
ERR
The source uses 'd' (most likely meaning 'day' in English), but the translation uses 'g' (which is incorrect; the correct abbreviation for 'gün' in Turkish is 'gün' or 'g'). However, 'g' is ambiguous and not standard. It would be clearer and more accurate to use 'gün', as 'g' could be confused with 'gram' or is not commonly used as an abbreviation for 'gün' in UI context.

Correct translation:
%1 gün
```

<!-- cache_translation_check_tr_5d44777950e59c389c5729868a15f6aff3409d209108cbd55aefe3f5e5a4c240 -->
```
        <source>%1 m</source>
        <translation>%1 d</translation>
    
ERR
The translation is incorrect because "m" in the source likely refers to "minutes" (dakika in Turkish), but the translation uses "d" which is not an abbreviation for "dakika" in Turkish. The correct abbreviation is "dk".

Correct translation:
%1 dk
```

<!-- cache_translation_check_tr_7263bd8a54179d54b6d7ffeee9fd503527e386a731442e6080f151f33bf18b4b -->
```
        <source>Browse transaction history</source>
        <translation>İşlem geçişini görüntüle</translation>
    
ERR
The translation "İşlem geçişini görüntüle" is inaccurate. "İşlem geçişi" does not correctly represent "transaction history." The correct term is "işlem geçmişi." Additionally, "Browse" should be translated as "Gözat" or "İncele" instead of "görüntüle" (which is "view").

Correct translation:
İşlem geçmişine göz at
```

<!-- cache_translation_check_tr_7e3fd637efb2ffcb2e88fb86d6da24d19e6ddf1f26a186d9393944cf316758b6 -->
```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Proxy &lt;b&gt;etkinleştirildi&lt;/b&gt;: %1 </translation>
    
ERR
There is an extra space at the end of the translation, which causes a whitespace format issue.

Correct translation:
Proxy &lt;b&gt;etkinleştirildi&lt;/b&gt;: %1
```

<!-- cache_translation_check_tr_6307d2e3a0f26e546d365df9850304bdbe15a24a42fd18e9daed6472b0279f7c -->
```
        <source>Open URI…</source>
        <translation>URI 'ı Aç...</translation>
    
ERR
There is a whitespace format issue. In Turkish, the correct formatting would be "URI'yi Aç..." without the extra space between "URI" and the apostrophe, and using the correct accusative suffix.

Correct translation:
URI'yi Aç...
```

<!-- cache_translation_check_tr_be7a36a50ab1837406e875d010040e66c7c723742441c999c10d646d73cc62e2 -->
```
        <source>Sending addresses</source>
        <translation> Adresleri gönderme</translation>
    
ERR
There is a whitespace issue (leading space) and the translation reverses the order of words, making it sound like "sending the addresses" rather than "addresses for sending." The correct translation should use the noun form to match the menu context (as in "Gönderim adresleri").

Correct translation:
Gönderim adresleri
```

<!-- cache_translation_check_tr_669f58009789627b370a7ae2d8b5276a9e69b06b48dc14ff7e342ff7fa6a9e1c -->
```
        <source>Open a bitcoin: URI</source>
        <translation>Bitcoin’i aç.</translation>
    
ERR
The translation "Bitcoin’i aç." is inaccurate. The phrase "Open a bitcoin: URI" refers specifically to opening a bitcoin URI (Uniform Resource Identifier), not just "open Bitcoin". The translation omits "URI", which could be important for user clarity.

Correct translation:
Bir bitcoin: URI’si aç
```

<!-- cache_translation_check_tr_16eed746fa720c3cd6eadbd65169b6e558bcc627c2e770d399eff5dbfb255317 -->
```
        <source>HD key generation is &lt;b&gt;enabled&lt;/b&gt;</source>
        <translation>HD anahtar üreticiler &lt;b&gt;kullanilabilir&lt;/b&gt;</translation>
    
ERR
The translation is not accurate. "HD anahtar üreticiler" is incorrect; it means "HD key generators", which is not the intended meaning. Also, "kullanilabilir" is a misspelling; it should be "kullanılabilir". However, more accurately, "enabled" in this context is best translated as "etkin".

Correct translation:
HD anahtar oluşturma &lt;b&gt;etkin&lt;/b&gt;
```

<!-- cache_translation_check_tr_43a218c3cf4b015006524d3e32e7a42c07b7c8130f455b79086a4226a3c2f760 -->
```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>HD anahtar üreticiler &lt;b&gt;kullanılamaz&lt;/b&gt;</translation>
    
ERR
The translation is inaccurate. "Üreticiler" means "producers" or "generators," which is not correct in this context. Also, the wording is awkward and does not convey "HD key generation is disabled" clearly.

Correct translation:
HD anahtar üretimi &lt;b&gt;devre dışı&lt;/b&gt;
```

<!-- cache_translation_check_tr_debd23a2e6ff64565b77c9724492bd527faa0476dce40999498a31a09432b631 -->
```
        <source>Private key &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>Gizli anahtar oluşturma &lt;b&gt;devre dışı&lt;/b&gt;</translation>
    
ERR
The translation is inaccurate. The source says "Private key <b>disabled</b>", which should just state that the private key is disabled, but the translation says "Gizli anahtar oluşturma <b>devre dışı</b>", which means "Private key creation <b>disabled</b>". The phrase "oluşturma" (creation) is not in the source.

Correct translation:
Gizli anahtar &lt;b&gt;devre dışı&lt;/b&gt;
```

<!-- cache_translation_check_tr_e02d583d703d5a069a3ab66fc19bed2cfc897efd1ba41cd39810d692af24e01f -->
```
        <source>Change:</source>
        <translation>Değiştir</translation>
    
ERR
The translation is inaccurate. In the context of Bitcoin, "Change:" refers to the leftover amount (change output) in a transaction, not the verb "Değiştir" ("Change" as in "Modify"). The correct Turkish translation for "Change:" (as in the noun for Bitcoin transaction change) is "Para Üstü:" or "Para üstü:".

Correct translation:
Para Üstü:
```

<!-- cache_translation_check_tr_e77875930821322791c375b95631cdfa621621f625e4996c06e4835280b737eb -->
```
        <source>(un)select all</source>
        <translation>tümünü seçmek</translation>
    
ERR
The translation "tümünü seçmek" means "to select all" in Turkish, but it does not properly represent the toggling implied by "(un)select all" (i.e., select all or deselect all).

Correct translation:
Tümünü (seç/deseç)
or, more commonly:
Tümünü seç / seçimi kaldır
```

<!-- cache_translation_check_tr_49e6a94f85dd8f94424cf75e54c5e5761b4f381c2d71d88a7af141f0a6d2f2fe -->
```
        <source>Amount</source>
        <translation>Mitar</translation>
    
ERR
The Turkish translation "Mitar" is incorrect and appears to be a misspelling or unrelated word. The correct translation for "Amount" is "Tutar".

Correct translation:
Tutar
```

<!-- cache_translation_check_tr_fc1cca30cd7bcf524bde397a014e5b82df53aa2ad0e8f2f1a45d89c4a68ee4f8 -->
```
        <source>Copy transaction ID and output index</source>
        <translation>İşlem ID ve çıktı içeriğini kopyala</translation>
    
ERR
The translation is inaccurate. "output index" is translated incorrectly as "çıktı içeriği" which means "output content". The correct translation for "output index" in the Bitcoin context is "çıktı indeksi".

Correct translation:
İşlem kimliğini ve çıktı indeksini kopyala
```

<!-- cache_translation_check_tr_9f5b13b25fee711cf155c2696130a18e798bfd1de08e73008a773e9e6ce52edc -->
```
        <source>(change)</source>
        <translation>(değiştir)</translation>
    
ERR
The word "change" in the Bitcoin context usually refers to the remaining balance returned to the sender in a transaction, not the verb "to change." The translation as "(değiştir)" is incorrect, as it means "(change [command/verb])" in Turkish.

Correct translation:
(değişim)
```

<!-- cache_translation_check_tr_fcfe3bc61f2735d38954d1ed7bb63e84d40b8f156c9d4d88f79491954cc78557 -->
```
        <source>Disable Private Keys</source>
        <translation>Özel Kilidi (Private Key) kaldır</translation>
    
ERR
The translation is inaccurate. "Disable Private Keys" should be translated as "Özel Anahtarları Devre Dışı Bırak" instead of "Özel Kilidi (Private Key) kaldır", which literally means "Remove Private Lock (Private Key)" and is both misleading and incorrect.

Correct translation:
Özel Anahtarları Devre Dışı Bırak
```

<!-- cache_translation_check_tr_9620dae1f1d39b706ac1d51a676bbc379648fdd39ca7ae3f06ab679bd3ee2416 -->
```
        <source>Welcome</source>
        <translation>Hoş geldiniz </translation>
    
ERR
There is an unnecessary trailing whitespace at the end of the translation.

Correct translation:
Hoş geldiniz
```

<!-- cache_translation_check_tr_71f6885203d2296913ea876e3cf840759905daab22307ddd400d93ec6c0b3484 -->
```
        <source>Prune block storage to</source>
        <translation>Depolamayı küçültmek engellemek için </translation>
    
ERR
The translation is inaccurate and introduces an incorrect meaning. The English source means "reduce/prune the block storage to [a certain size]," and the Turkish translation suggests both "shrinking" and "blocking" in a nonsensical way. Additionally, the translation omits to translate "block" as in "blockchain block". 

Correct translation:
Blok depolamasını şuna küçült:
or
Blok depolamasını şu boyuta küçült:
(if followed by a size indication)
```

<!-- cache_translation_check_tr_217efc225dcd89261022130ef5b8c39d81bbfec238c361e31d7996aa2e8c6f6c -->
```
        <source>Spend unconfirmed change</source>
        <translation> Onaylanmamış bozuk parayı harcayın</translation>
    
ERR
There is a formatting issue: there is an unnecessary leading space before the translation, and "bozuk para" is not the most appropriate term for "change" in a Bitcoin context. "Change" refers to the leftover amount from a transaction, not "coins" or "small change." A better translation would be "onaylanmamış bakiyeyi" or "onaylanmamış para üstünü".

Correct translation:
Onaylanmamış para üstünü harcayın
```

<!-- cache_translation_check_tr_87b24410a89751da24eca78a69d0bcfaa6312af9bb8e3281a6bcaac2f2abbacf -->
```
        <source>Mined balance that has not yet matured</source>
        <translation>ödenilmemiş miktar</translation>
    
ERR
The translation is inaccurate and problematic. "ödenilmemiş miktar" means "unpaid amount", which does not communicate the intended meaning of "Mined balance that has not yet matured" — i.e., newly mined coins that cannot yet be spent due to not reaching maturity.

Correct translation:
Henüz olgunlaşmamış kazılmış bakiye
```

<!-- cache_translation_check_tr_73a29a505f2be1766ad07e7924574097ed92fa79953f66ddf42e7b0aa9bf6126 -->
```
        <source>Sends %1 to %2</source>
        <translation>Gönderiler %1 ile %2</translation>
    
ERR
The translation is incorrect. The English source means "Sends %1 to %2," indicating an action where %1 (usually an amount) is sent to %2 (usually an address or recipient). The current translation means "Shipments with %1 and %2" or "The shipments with %1 by %2", which is not accurate.

Correct translation:
%1, %2'ye gönderiyor
or
%1, %2 adresine gönderiliyor
```

<!-- cache_translation_check_tr_0316934ac8aee6398276bddb648ad84224d90d5f4f6cdfece04255dc19feea07 -->
```
        <source>Outbound</source>
        <extracomment>An Outbound Connection to a Peer.</extracomment>
        <translation>yurt dışı</translation>
    
ERR
The translation "yurt dışı" means "abroad" in Turkish, which is incorrect in the context of Bitcoin networking. The term "Outbound" here refers to "dışa giden" or "giden" (i.e., connections initiated from the user's side). 

Correct translation:
Giden
```

<!-- cache_translation_check_tr_e02d583d703d5a069a3ab66fc19bed2cfc897efd1ba41cd39810d692af24e01f -->
```
        <source>Change:</source>
        <translation>Değiştir</translation>
    
ERR
The translation is inaccurate. In the context of Bitcoin, "Change:" refers to the leftover amount (change output) in a transaction, not the verb "Değiştir" ("Change" as in "Modify"). The correct Turkish translation for "Change:" (as in the noun for Bitcoin transaction change) is "Para Üstü:" or "Para üstü:".

Correct translation:
Para Üstü:
```

<!-- cache_translation_check_tr_759cc0d68105973c830b0e81dde4bdc3e1bc179b5bd21f332b9ceffaeac52c9a -->
```
        <source>Signatures - Sign / Verify a Message</source>
        <translation>İmzalar - Giri‭s / Mesaji Onayla</translation>
    
ERR
There are several issues:
1. "Giri‭s" should be "İmzala" for "Sign".
2. "Mesaji" should have proper Turkish capitalization and diacritics, i.e., "Mesajı".
3. The slash formatting should match the source and should not have irregular spacing or invisible characters.

Correct translation:
İmzalar - İmzala / Mesajı Doğrula
```

<!-- cache_translation_check_tr_26d876d348a720a6cc993f803fbf486f49b511e3fd4db8b13aeaebed65f94c63 -->
```
        <source>The entered address does not refer to a legacy (P2PKH) key. Message signing for SegWit and other non-P2PKH address types is not supported in this version of %1. Please check the address and try again.</source>
        <translation>Girilen adres, eski (P2PKH) bir anahtarı belirtmiyor. Bu sürümde SegWit ve diğer P2PKH olmayan %1 versiyon adres türleri için mesajla imzalama desteklenmiyor. Lütfen adresi kontrol edin ve tekrar deneyin.</translation>
    
ERR
The translation is mostly accurate but has an awkward and partially incorrect phrase: "diğer P2PKH olmayan %1 versiyon adres türleri" which misplaces "%1", making it reference the 'address types' rather than the application version, as intended. Also, "%1" should appear exactly as in the original, preserving its position.

Correct translation:
Girilen adres, eski (P2PKH) bir anahtara karşılık gelmiyor. Bu %1 sürümünde SegWit ve diğer P2PKH olmayan adres türleri için mesaj imzalama desteklenmiyor. Lütfen adresi kontrol edin ve tekrar deneyin.
```

<!-- cache_translation_check_tr_49e6a94f85dd8f94424cf75e54c5e5761b4f381c2d71d88a7af141f0a6d2f2fe -->
```
        <source>Amount</source>
        <translation>Mitar</translation>
    
ERR
The Turkish translation "Mitar" is incorrect and appears to be a misspelling or unrelated word. The correct translation for "Amount" is "Tutar".

Correct translation:
Tutar
```

<!-- cache_translation_check_tr_1f30f880215170fdde6e880511efa6e3a35336e5fbd1eac5046fe3a1542daa22 -->
```
        <source>The transaction amount is too small to send after the fee has been deducted</source>
        <translation>Bu işlem, tutar düşüldükten sonra göndermek için çok düşük</translation>
    
ERR
The translation does not accurately convey the meaning of the source sentence. The original states that the transaction amount is too small to send after the fee has been deducted, but the translation incorrectly says "after the amount has been deducted," and also lacks proper grammar.

Correct translation:
İşlem tutarı, ücret düşüldükten sonra göndermek için çok küçük.
```

<!-- cache_translation_check_tr_b7ae4ff63df6ce7949259989bf87a72b5de77c8462ed66ad53b81690804d7daa -->
```
        <source>Maximum transaction weight is less than transaction weight without inputs</source>
        <translation>Maksimum işlem ağırlığı, işlem girdi ağırlığından daha küçük olmalıdır.</translation>
    
ERR
The translation does not accurately reflect the original English meaning. The English says the "maximum transaction weight is less than transaction weight without inputs," which indicates an error state (i.e., maximum is less than a minimum required baseline, which is not permitted). The Turkish translation incorrectly adds "olmalıdır" (must be), making it a recommendation rather than an error.

Correct translation:
Maksimum işlem ağırlığı, girdiler hariç işlem ağırlığından daha küçük.
```

<!-- cache_translation_check_tr_cbe0b9498d606899d6c7149057c5e7be1efd9a1274b7a4220f0e0178006fcd8d -->
```
        <source>Error: Unable to read wallet's best block locator record</source>
        <translation>Hata: Cüzdan okunamadı en iyi blok bulucu kaydı </translation>
    
ERR
The translation distorts the sentence structure, leading to unnatural wording and a loss of meaning. The phrase "Cüzdan okunamadı en iyi blok bulucu kaydı" is both unclear and grammatically incorrect. It translates back as "Wallet could not be read best block locator record," which does not accurately convey the original error.

Correct translation:
Hata: Cüzdanın en iyi blok bulucu kaydı okunamadı
```

<!-- cache_translation_check_tr_6cabb124ab8caca6fd7d95f1a630817567f5ec1acd93d83781ce306de2ed82fa -->
```
        <source>Error: Unable to write solvable wallet best block locator record</source>
        <translation>Hata: Cüzdana yazılamadı en iyi blok bulucu kaydı </translation>
    
ERR
The Turkish translation is grammatically awkward and does not clearly convey the meaning of the original sentence. The phrase "Cüzdana yazılamadı en iyi blok bulucu kaydı" is confusing and the word order is incorrect. The format specifier is preserved, but the meaning is not accurately conveyed.

Correct translation:
Hata: Çözülebilir cüzdan için en iyi blok bulucu kaydı yazılamıyor
```

<!-- cache_translation_check_tr_6caddf7f8e313f33df3cacb55ba98c2e4d0d99d112453513752b584b3fc2868d -->
```
        <source>Error: database transaction cannot be executed for wallet %s</source>
        <translation>Hata: %sCüzdan için veri tabanında işlem yapılamaz</translation>
    
ERR
There is a spacing issue between "%s" and "Cüzdan"—they should be separated by a space. Also, "veri tabanında" should be "veritabanı" for proper usage in Turkish. 

Correct translation:
Hata: %s cüzdanı için veritabanı işlemi gerçekleştirilemiyor
```

<!-- cache_translation_check_tr_1a348702aa703f3b2a96e2d60aaf3808a9f554fa67038ca3853e49330f009540 -->
```
        <source>Failure removing transaction: %s</source>
        <translation>işlemi: %s silme başarısız oldu.</translation>
    
ERR
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

<!-- cache_translation_check_tr_55ea2807017c4f582341e2d5b95b64414d627fa279a72af96d1ea1b1f249891d -->
```
        <source>Signer did not echo address</source>
        <translation>İmzalayıcı adresi belirtilmedi.</translation>
    
ERR
The translation is incorrect. The original English means that the signer did not return (echo) the address, but the translation says "The signer's address was not specified", which is a different meaning.

Correct translation:
İmzalayıcı adresi yinelemedi.
```

<!-- cache_translation_check_tr_9f587d4358422fbeaa0a501e65c93693c158ab6765573575b64b657f3ff89d38 -->
```
        <source>Signer echoed unexpected address %s</source>
        <translation>İstenmeyen %s adrese imzalama yapıldı.</translation>
    
ERR
The translation reverses the agent and context. The original means the signer *returned* an unexpected address, not that signing was performed to an unwanted address. "Echoed" should be translated as "yansıttı" or "geri verdi", meaning the signer *responded with* the address.

Correct translation:
İmzalayıcı beklenmeyen bir adres (%s) geri verdi.
```

<!-- cache_translation_check_tr_e1cc01b7891262db7e20e900bbc71c0d4ac766bd4e437833561c1c22f68eeacf -->
```
        <source>Signer returned error: %s</source>
        <translation>%s İmzayıcı hatası tekrarı.</translation>
    
ERR
The translation is incorrect. "%s İmzayıcı hatası tekrarı." does not accurately convey "Signer returned error: %s" and the word "tekrarı" (repetition) is inappropriate here. The format specifier "%s" should also be retained in the correct position.

Correct translation:
İmzacı hata döndürdü: %s
```

<!-- cache_translation_check_tr_739128e43d61a262385b9fa99177599317e47144f7c016489c56e4fdce760d73 -->
```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>-paytxfee çok yüksek bir değere ayarlanmış! Bu, işlemi gönderirseniz ödeyeceğiniz işlem ücretidir.</translation>
    
ERR
The Turkish translation adds information ("-paytxfee çok yüksek bir değere ayarlanmış!") that is not in the original English string, making it inaccurate. The translation should only render the given sentence.

Correct translation:
Bu, bir işlem gönderirseniz ödeyeceğiniz işlem ücretidir.
```

<!-- cache_translation_check_tr_e2b2c7b611623f1d72ad968d185680fbac21a6d45d0cc9e8850d3af9bf64b720 -->
```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Hata: Sadece izleme %s cüzdanı. tx izleme cüzdanına eklenemedi</translation>
    
ERR
The Turkish translation is problematic. It is not grammatically correct, and the structure is unclear. The phrase "Sadece izleme %s cüzdanı. tx izleme cüzdanına eklenemedi" is not natural in Turkish and does not reflect the source content accurately. Additionally, the format specifier %s is placed awkwardly.

Correct translation:
Hata: Sadece izlenen tx %s, sadece izlenen cüzdana eklenemedi
```
</details>

Number of issues: 43.
