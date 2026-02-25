# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>tr</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Btr%5D%20request)


<!-- cache_translation_check_tr_42b12ab4470a52e925fcced76dca24c8640a51c07f1ad19f421bdb56a7d8b91d -->
```
        <source>Copy &amp;Label</source>
        <translation>Etiketi kopyala</translation>
    
ERR
The translation is correct Turkish for "Copy label" but it omits the required shortcut marker (&) from the source. The ampersand must appear exactly once in the translation.

Correct translation (with ampersand):
Etiketi &kopyala
```

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

<!-- cache_translation_check_tr_7a8299027bcc1a438707b486125ca2f72ffc665743b15fdcc0b14f68937fea94 -->
```
        <source>&amp;Overview</source>
        <translation>Genel durum</translation>
    
ERR
The translation is missing the shortcut marker (&) present in the source. Also UI wording/casing can be improved.

Correct translation (with shortcut):
&Genel Durum

Alternative more common UI wording:
&Genel Bakış
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

<!-- cache_translation_check_tr_88c8c4aa73535844a5edc3f7bb1d86597cb56382f1b485024b0e1fab555775a2 -->
```
        <source>Sign &amp;message…</source>
        <translation>&amp;Mesajı imzala...</translation>
    
ERR
Translation is correct in meaning and the ampersand shortcut is present exactly once, but the ellipsis character differs (source uses single Unicode ellipsis … whereas translation uses three dots ...). For consistency use the same ellipsis character and no extra spaces.

Correct translation:
&Mesajı imzala…
```

<!-- cache_translation_check_tr_b548db3ffa68fbb15d8dc4ea86d8277285a8778a518b7df785b4fb593ba7fe16 -->
```
        <source>Open &amp;URI…</source>
        <translation>&amp;URI 'ı Aç...</translation>
    
ERR
Issues:
- There is an incorrect space between "URI" and the apostrophe + suffix ("URI 'ı"), it should be attached: "URI'yi".
- The accusative suffix is wrong: use "'yi" (not "'ı") for "URI" -> "URI'yi".
- The ellipsis should be the single character … (or at least no extra space), and avoid three separate dots if source uses single ellipsis.
- Ensure the ampersand shortcut appears exactly once (kept before U).

Correct translation:
&URI'yi Aç…
```

<!-- cache_translation_check_tr_97ae355cbf4e3ea580ce5ccaa249948835bcddfcdb2b1a968ab8ee884c1a5651 -->
```
        <source>%1 behind</source>
        <translation>arkasında</translation>
    
ERR
The translation is missing the format specifier '%1' which is required to show the time or number of blocks behind.

Correct translation:
%1 geride
```

<!-- cache_translation_check_tr_f5e0528619ddd1120287ccf5d52b1f4daca7bcdd91a307701dde1d5c0fb1b43b -->
```
        <source>&amp;Sending addresses</source>
        <translation>&amp; Adresleri gönderme</translation>
    
ERR
Problems:
- The ampersand is written as "&amp;" (XML-escaped) but there's an extra space after it. The shortcut marker (&) must appear exactly once and should be placed immediately before the shortcut letter, not before a space.
- Word order is awkward in Turkish. Better is "&Gönderme adresleri" or "&Gönderilen adresler" depending on intended meaning.

Correct translation (recommended):
&Gönderme adresleri
```

<!-- cache_translation_check_tr_14fa8b443442975a2a314159359867a21c1892811564085cf7a62c21f521a039 -->
```
        <source>&amp;Receiving addresses</source>
        <translation>&amp; Adresler alınıyor</translation>
    
ERR
Problems:
- There's an extra space after the ampersand ("& Adresler..."); the & should be adjacent to the character it marks.
- The Turkish phrase "Adresler alınıyor" literally means "addresses are being received" (progressive), which is unnatural for the UI label meaning "Receiving addresses" (addresses for receiving funds).

Correct translation:
&Alıcı adresler
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

<!-- cache_translation_check_tr_df6d4b68215dfb1c0803c726c433fceb8cc8710f6c9529a6ca63a513b75d7ab7 -->
```
        <source>&amp;Mask values</source>
        <translation>&amp; Değerleri maskele</translation>
    
ERR
There is an extra space after the ampersand (&) which breaks the shortcut marker. Also the ampersand should appear immediately before the shortcut letter. 

Correct translation:
&Değerleri maskele
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

<!-- cache_translation_check_tr_7d4ff5c2e390f8e53e4ff5fac8d552fb7ba3d46ec5f44dae4ce5b8ced0c0a86e -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>İşlem &amp;ID ve çıktı içeriğini kopyala</translation>
    
ERR
The Turkish is understandable but awkward/incorrect: "çıktı içeriğini" means "output content" instead of "output index", and the phrase lacks proper possessive/accusative forms for "ID". The ampersand (&) is present exactly once (good).

Correct translation:
İşlem &ID'sini ve çıktı indeksini kopyala
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

<!-- cache_translation_check_tr_68e1053005c534198e8635f9040750affea0afb91f16b468faa5b5235753f507 -->
```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>Girilen "%1" adresi zaten adres defterinde ''%2" etiketli olarak bulunuyor.</translation>
    
ERR
The translation contains a typographical error in the punctuation surrounding the second format specifier. It uses two single quotes (''%2") instead of one double quote ("%2") or a consistent set of quotation marks.

Correct translation:
Girilen "%1" adresi zaten adres defterinde "%2" etiketiyle bulunuyor.
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

<!-- cache_translation_check_tr_6eb92534572060165ed8216267d561c147f10fbd8bc1120765b771ab1aecca6a -->
```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>%1 şu anda senkronize ediliyor. Eşlerden başlıkları ve blokları indirecek ve blok zincirinin ucuna ulaşıncaya kadar bunları doğrulayacaktır.</translation>
    
ERR
The Turkish is understandable but slightly awkward/unnatural (passive phrasing and word order). Also "tip of the block chain" is better rendered as "blok zincirinin sonu". The format specifier %1 is preserved correctly.

Suggested corrected translation:
%1 şu anda senkronize oluyor. Eşlerden blok başlıklarını ve blokları indirip blok zincirinin sonuna ulaşana kadar bunları doğrulayacak.
```

<!-- cache_translation_check_tr_f65def0273a3066a6ab70bc077913d002a31c0181b68d53333e8836dce4b1cac -->
```
        <source>&amp;Start %1 on system login</source>
        <translation>&amp;Açılışta %1 açılsın</translation>
    
ERR
The Turkish is understandable but awkward and not the most natural phrasing. The source means "Start %1 on system login" (i.e. start the application %1 when the user logs into the system). The translation "Açılışta %1 açılsın" is clumsy (repeats the root "aç" and is not typical Turkish UI phrasing).

Keep the %1 and the single & for the accelerator. Better translations:
- "&Sisteme girişte %1'i başlat"
or
- "&Oturum açıldığında %1'i başlat"

Either preserves %1, uses natural Turkish, and includes a single '&'.
```

<!-- cache_translation_check_tr_8cbeea2ded7c78180537de09fd03c82aac9fe63cc9262bd2a097640bd121f639 -->
```
        <source>Prune &amp;block storage to</source>
        <translation>Depolamayı küçültmek &amp;engellemek için </translation>
    
ERR
The Turkish translation is incorrect and slightly malformed. "Depolamayı küçültmek &engellemek için " changes the meaning (it reads like "to reduce storage to prevent/block"), uses the wrong verb "engellemek" (to prevent/block), and leaves a trailing space. The ampersand exists once (OK) but the translation itself is wrong.

Correct translation (preserving a single &):
Blok depolamayı &şu kadar kırp

(or more explicit:)
Blok depolamayı &şu boyuta kadar kırp

Both use the ampersand exactly once and convey the intended meaning "Prune block storage to".
```

<!-- cache_translation_check_tr_cb9e8143d79d50b28037bab3740460b37a5fc81860c422a4b11301c9efcb0aad -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Varsayılan olarak ücreti tutardan düş</translation>
    
ERR
The translation is missing the shortcut ampersand (&) present in the source and the verb form is awkward ("düş" is incomplete). Also ensure the ampersand appears exactly once.

Suggested correction (with & placed before "ücreti"):
Varsayılan olarak tutardan &ücreti düşür
```

<!-- cache_translation_check_tr_736a3c948c45771ee155a0adeb9ff33a08644be4dabb8025435da5341ebef239 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>&amp; Onaylanmamış bozuk parayı harcayın</translation>
    
ERR
Issues:
- There's an extra space after the ampersand ("& Onay..."), which breaks the shortcut key (the & must appear exactly once and directly before the shortcut letter).
- The wording "bozuk para" is literal ("coins/change") and sounds awkward in this Bitcoin UI context. "Değişiklik" or "bakiye/para üstü" is better; common UI wording is "onaylanmamış değişikliği" or "onaylanmamış bakiyeyi".

Suggested corrections (choose one appropriate to your UI style):
&Onaylanmamış değişikliği harcayın
or
&Onaylanmamış bakiyeyi harcayın
```

<!-- cache_translation_check_tr_8f5b7fa7c94b799c8fb9f9914d2363b425ccfa2811c77df623934a0707217f74 -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>PSBT kontrollerini etkinleştir</translation>
    
ERR
The translation is missing the shortcut ampersand (&) from the source. No format specifiers present; otherwise Turkish phrasing is acceptable.

Correct translation (include & exactly once, mirroring source):
&PSBT kontrollerini etkinleştir
```

<!-- cache_translation_check_tr_50cdd93c731a58fa97a3e81d2a80d3a24bb53373519d18688f8fffe7342827a0 -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Gelen bağlantılara izin ver</translation>
    
ERR
The translation is missing the shortcut ampersand (&) present in the source (it must appear exactly once in the translation). Also ensure the ampersand is placed immediately before the chosen shortcut letter with no extra spaces.

Correct translation (with ampersand added), for example:
Gelen bağlantılara &izin ver
```

<!-- cache_translation_check_tr_39f1e1599a188a0c8a7ecc7f14048e38bb3ef822e6ef862161c098efe76871ea -->
```
        <source>&amp;Show tray icon</source>
        <translation>Simgeyi &amp;Göster </translation>
    
ERR
Problems:
- Trailing space after the translation ("Simgeyi &Göster ").
- Word order/casing is a bit odd for Turkish UI conventions. Typically the shortcut ampersand is placed before the word to be used as shortcut and the verb is lowercase.

Suggested correct translations (choose one):
- "&Simgeyi göster"
- "&Tepsi simgesini göster"

Both contain the ampersand exactly once, have no extra whitespace, and are natural Turkish UI strings.
```

<!-- cache_translation_check_tr_69f1e1c35cfc87a2806370dcaf37a58260a693637ec7243f772bcca0bd267efd -->
```
        <source>&amp;Unit to show amounts in:</source>
        <translation>Tutarı göstermek için &amp;birim:</translation>
    
ERR
"tutarı" is singular; source uses plural "amounts". More natural Turkish is plural "Tutarları göstermek için &birim:".

Correct translation:
Tutarları göstermek için &birim:
```

<!-- cache_translation_check_tr_0a10534a4380cf38db314b0d3c275044ca883183d736f7bd3ed64db8029b1367 -->
```
        <source>&amp;Third-party transaction URLs</source>
        <translation>&amp;Üçüncü parti işlem URL'leri</translation>
    
ERR
"Üçüncü parti" is understandable but not the most natural Turkish; "üçüncü taraf" is the preferred term. The ampersand is present exactly once (good) and the apostrophe in "URL'leri" is fine.

Correct translation:
&Üçüncü taraf işlem URL'leri
```

<!-- cache_translation_check_tr_efda40867b61d8d88cb941cdbd114bd66ad0994a6cebceb70155b20575502203 -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Tor onion hizmetleri aracılığıyla eşlere ulaşmak için ayrı SOCKS&amp;5 proxy kullanın: </translation>
    
ERR
Translation is accurate and natural, and the &amp; accelerator is preserved exactly once. However, there is an extra trailing space before the closing punctuation.

Correct translation without the trailing space:
Tor onion hizmetleri aracılığıyla eşlere ulaşmak için ayrı SOCKS&amp;5 proxy kullanın:
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

<!-- cache_translation_check_tr_20edda8e4e478dc6fa0f8373f3e2b23508501557b3a75e2ec4642fdfb8c4ed86 -->
```
        <source>Total Amount</source>
        <translation>Toplam Tutar %1</translation>
    
ERR
The translation includes a format specifier (%1) that is not present in the source text. Adding format specifiers where they don't exist in the source can cause errors in the software.

Correct translation:
Toplam Tutar
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

<!-- cache_translation_check_tr_d992f8f2a404263f4580453e4808b07173e4b6baf8b66cbd035f31e6ae43ec7b -->
```
        <source>&amp;Copy IP/Netmask</source>
        <extracomment>Context menu action to copy the IP/Netmask of a banned peer. IP/Netmask is the combination of a peer's IP address and its Netmask. For IP address, see: https://en.wikipedia.org/wiki/IP_address.</extracomment>
        <translation>IP/Ağ Maskesini Kopyala</translation>
    
ERR
The translation is missing the shortcut ampersand (&) that appears in the source. The source has a single & indicating the mnemonic; the translation must include exactly one &. 

Correct translation (with a single &):
&IP/Ağ Maskesini Kopyala
```

<!-- cache_translation_check_tr_b689f131f694f90e3b76af3f36119c8be1f58e2adb5aea17809588cd3552f374 -->
```
        <source>&amp;Amount:</source>
        <translation>miktar</translation>
    
ERR
The translation is missing the shortcut ampersand and the trailing colon from the source, and it doesn't match the source punctuation/case. It should include exactly one '&' and the colon.

Correct translation:
&amp;Miktar:
```

<!-- cache_translation_check_tr_01a2eca24c46f6dc6a77ed4ae634ab79d3321d96427eddea4f23a697f2789980 -->
```
        <source>&amp;Create new receiving address</source>
        <translation>Yeni alıcı adresi oluştur</translation>
    
ERR
The translation is accurate Turkish but it omits the shortcut marker (&) from the source. The source contains one '&' which should appear exactly once in the translation.

Correct translation:
&amp;Yeni alıcı adresi oluştur
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

<!-- cache_translation_check_tr_df1127dd54d7d2cd58802345e6fbe1d381a60d304b43239750f9fe9956d8f921 -->
```
        <source>S&amp;ubtract fee from amount</source>
        <translation>Ücreti tutardan düş</translation>
    
ERR
Problems:
- The translation is missing the accelerator marker (&). The source contains a single & and the translation must also include exactly one.
- Minor grammatical issue: "from amount" is better rendered as "tutarından" in Turkish.

Correct translation:
<&>Ücreti tutarından düş

(Place the & exactly once; for example:
&Ücreti tutarından düş )
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

<!-- cache_translation_check_tr_dd1513dfa30f7b4e4a46268e013988dbb9e8f2c75f42340fd69113055d64649e -->
```
        <source>Cannot obtain a lock on directory %s. %s is probably already running.</source>
        <translation>%sDizin kilitlenemiyor. %s muhtemelen halihazırda çalışıyor.</translation>
    
ERR
The translation contains a spacing issue. There should be a space after the first format specifier '%s' to separate it from the following word 'Dizin'.

Correct translation:
%s dizini kilitlenemiyor. %s muhtemelen halihazırda çalışıyor.
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

<!-- cache_translation_check_tr_6e321ebe4b4c10dc37754657101876bb82e2700638b3afd11059ced9c1803828 -->
```
        <source>Specified -blockreservedweight (%d) is lower than minimum safety value of (%d)</source>
        <translation>Belirtilen -blockreservedweight (%d), minimum güvenlik değeri olan (%d)' dan daha düşük.</translation>
    
ERR
The translation contains an unnecessary space before the apostrophe for the suffix attached to the format specifier. In Turkish, when appending suffixes to numbers or variables represented by format specifiers, there should not be a space before the apostrophe.

Correct translation:
Belirtilen -blockreservedweight (%d), minimum güvenlik değeri olan (%d)'dan daha düşük.
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

Number of issues: 65.
