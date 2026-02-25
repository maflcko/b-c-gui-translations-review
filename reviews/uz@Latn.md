# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>uz@Latn</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Buz@Latn%5D%20request)


<!-- cache_translation_check_uz@Latn_38b701719f502392bed26773a24618abcafe30af31e089bc87014e004658a846 -->
```
        <source>&amp;Copy Address</source>
        <translation>&amp;Manzillarni nusxalash</translation>
    
ERR
The translation uses the plural form "Manzillarni" (addresses) but the source is singular "Address". Correct Uzbek (Latin) translation should use the singular:

Correct translation:
&Manzilni nusxalash
```

<!-- cache_translation_check_uz@Latn_e62cbc55bdef0a7c569fec5a182fcb42dcc92f4cc83818761190dfa43b407589 -->
```
        <source>Copy &amp;Label</source>
        <translation>Nusxalash &amp;Yorliq</translation>
    
ERR
Word order is unnatural in Uzbek. "Nusxalash &Yorliq" literally reads "Copy Label" but with the verb before the noun it's better to use the object–verb phrase. Also ensure the ampersand appears exactly once.

Suggested correction:
&Yorliqni nusxalash
```

<!-- cache_translation_check_uz@Latn_af51441b4a8f6c94fe8e843cae0435437a9d83d22addc6aba8195b316d4b8860 -->
```
        <source>Sending addresses - %1</source>
        <translation>Manzil yuborilmoqda</translation>
    
ERR
The translation is incorrect and incomplete. The English source "Sending addresses - %1" refers to a title or label for a list of addresses used for sending, including a placeholder %1. The Uzbek translation "Manzil yuborilmoqda" means "Address is being sent" and misses the placeholder.

Correct translation:
Jo'natish manzillari - %1
```

<!-- cache_translation_check_uz@Latn_7b3fa41b56d3b32b438ab63351c5d8d8c3136dfac855457306ca67cb46999aa4 -->
```
        <source>Receiving addresses - %1</source>
        <translation>Qabul qilish manzillari</translation>
    
ERR
The format specifier '%1' is missing in the translation. In this context, it usually represents the wallet name or a specific identifier that should be included.

Correct translation:
Qabul qilish manzillari - %1
```

<!-- cache_translation_check_uz@Latn_b6b006571f42e71027cb725efbc9547b8e83ec661e67ce85273f9ce42665f67a -->
```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>MUHIM: Hamyon faylingizning oldingi nusxalari yangi fayl, shifrlangan hamyoni bilan almashtirilishi kerak. masalalik nuqtai nazaridan, shifrlanmagan hamyon faylining oldingi nusxalari yangi, shifrlangan hamyondan yuklashning yangilanishi bilanoq foydasiz bo'ladi.</translation>
    
ERR  
The translation is problematic due to grammar errors, awkward wording, and partial mistranslation. Specifically:
- "masalalik nuqtai nazaridan" should be "Xavfsizlik nuqtai nazaridan" (For security reasons).
- The first sentence structure is awkward and not fully accurate.
- The phrase "yangi, shifrlangan hamyondan yuklashning yangilanishi bilanoq" is confusing and incorrect.
- The overall flow and accuracy suffers as meaning is only partially preserved.

Correct translation:  
MUHIM: Hamyon faylingizning oldingi zaxira nusxalarini yangi yaratilgan, shifrlangan hamyon fayli bilan almashtirishingiz kerak. Xavfsizlik nuqtai nazaridan, shifrlanmagan hamyon faylining oldingi zaxira nusxalari yangi, shifrlangan hamyondan foydalana boshlaganingiz zahoti befoyda bo‘ladi.
```

<!-- cache_translation_check_uz@Latn_b33f607f116492a3ae1cfeb8ad910e15a23a4fd5eb86ae87c3ba622a539814d8 -->
```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Noto'g'ri maxfiy so'z kiritildi</translation>
    
ERR
The translation omits "for the wallet decryption" from the source, making it less specific. Additionally, the word "maxfiy so'z" means "secret word" or "passphrase," but the full context is not preserved.

Correct translation:
Hamyonni shifrlashni ochish uchun kiritilgan maxfiy so‘z noto‘g‘ri edi.
```

<!-- cache_translation_check_uz@Latn_73062f30966c6156c0858b5b56081c4c11a42eb4e97e4268b5f169f6a61786be -->
```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Hamyon shifrini ochish uchun parol iborasi noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas). Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating.
</translation>
    
ERR
There are several problems with the translation:
1. "qurilmalar" means "devices", which doesn't make sense in context; it should be "belgilar" ("characters").
2. The phrase "(lekin shu narsa emas)" is an unnatural translation of "but not including".
3. The translation for "If this is successful, please set a new passphrase to avoid this issue in the future." is inaccurate; "Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating" is both awkward and incorrect ("olish" means "to get", not "to avoid").
4. There are some awkward phrasings and minor spacing inconsistencies.

Correct translation:
Hamyonning shifrlanishini ochish uchun kiritilgan parol iborasi noto‘g‘ri. U o‘z ichiga null belgisini (ya’ni — nol bayt) oladi. Agar parol iborasi ushbu dasturiy ta’minotning 25.0 versiyasidan oldingi versiyada o‘rnatilgan bo‘lsa, iltimos, faqat birinchi null belgigacha bo‘lgan — lekin uni o‘z ichiga olmagan — belgilar bilan qayta urinib ko‘ring. Agar muvaffaqiyatli bo‘lsa, kelajakda ushbu muammo takrorlanmasligi uchun yangi parol o‘rnating.
```

<!-- cache_translation_check_uz@Latn_2918ff4aee68e2055c1a85af021e51d3926cf0fb029abde3c5db3a4dd5066751 -->
```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Hamyon shifrini ochish uchun yordam eski parol noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas).</translation>
    
ERR
The translation is mostly understandable but contains several inaccuracies and ambiguous phrasing:

1. "yordam eski parol noto'g'ri" — "yordam" ("help") is unnecessary and incorrect here; it should be simply "eski parol noto'g'ri kiritilgan" ("the old passphrase entered is incorrect").
2. "qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas)" — The word "qurilmalar" means "devices," which is not related to the intent here; the original refers to characters. The phrase "(lekin shu narsa emas)" ("but not that thing") is unclear and does not correctly convey "but not including."
3. The tone and specificity need improvement for accuracy and clarity.

Correct translation:
Hamyonni shifrdan chiqarish uchun kiritilgan eski parol noto'g'ri. U null belgi (ya'ni, nol bayt) ni o‘z ichiga oladi. Agar parol iborasi ushbu dasturiy ta'minotning 25.0 versiyasidan oldinroq o‘rnatilgan bo‘lsa, iltimos, faqat birinchi null belgigacha bo‘lgan belgilarni (birinchi null belgi o‘zini emas) kiriting va qayta urinib ko‘ring.
```

<!-- cache_translation_check_uz@Latn_5cc120eff65239f3f03c07ebe850f7e2dc20d4d270ac1981b6bb6bfc0e5f8315 -->
```
        <source>Banned Until</source>
        <translation>gacha kirish taqiqlanadi</translation>
    
ERR
The translation is incorrect and does not preserve the intended meaning or capitalization. "Banned Until" should specify the time until which the ban applies. "gacha kirish taqiqlanadi" is unnatural, literally meaning "access is prohibited until", but lacks context and is not a noun phrase as in the source.

Correct translation:
"Taqiqlangan vaqti" or "Taqiqlangan muddat" or "Taqiqlash muddati" 

A full, more literal translation:
"Taqiqlangan vaqti"
```

<!-- cache_translation_check_uz@Latn_c410acb758314b160d6a38a7a7ed516964df2d5437a5f1438df8e258778b39b6 -->
```
        <source>Runaway exception</source>
        <translation>qo'shimcha istisno</translation>
    
ERR
The translation "qo'shimcha istisno" means "additional exception", which doesn't correctly capture the meaning of "Runaway exception" (an unhandled or uncontrolled exception/error). 

Correct translation:
Nazorat qilinmaydigan istisno
```

<!-- cache_translation_check_uz@Latn_7dc940b4b5f60571ec1dd5d98804adb937eb9c7fc66351de2e17ddc77644f8d6 -->
```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>Fatal xatolik yuz berdi. %1 xavfsiz ravishda davom eta olmaydi va tizimni tark etadi. </translation>
    
ERR
There is a slight issue with clarity and accuracy. "Tizimni tark etadi" is awkward and can be confusing; also, there is an unnecessary space at the end. A more accurate and natural translation would be:

Correct translation:
Fatal xatolik yuz berdi. %1 endi xavfsiz davom eta olmaydi va yopiladi.
```

<!-- cache_translation_check_uz@Latn_e37c985c293792512512bb2401d5b24c75900564c2540170fecd7c4f70838939 -->
```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>Bitcoin манзилини киритинг (масалан.  %1)</translation>
    
ERR
The translation uses Cyrillic script characters (e.g., "манзилини киритинг") instead of the required Latin script for 'uz@Latn'. Also, there is an unnecessary extra space after the period and before "%1".

Correct translation:
Bitcoin manzilini kiriting (masalan, %1)
```

<!-- cache_translation_check_uz@Latn_fe5b13e10a3c6716704c9f42ceed83e808b30e9db968dc3e856ff7d2ace06b7a -->
```
        <source>%1 m</source>
        <translation>%1 д</translation>
    
SPAM
The translation is in Cyrillic script ('д') instead of the required Latin script for 'uz@Latn'. The correct translation for "m" (meters or minutes, context-dependent) in Uzbek Latin script could either stay as "m" if it refers to "meters" or "daq" for "daqiqa" (minute). Most likely, for general "m", it should be left as is:

Correct translation:
%1 m
```

<!-- cache_translation_check_uz@Latn_0aa3a34bc3751b0feeba39deb0736f33d9d2078e277c8189e652102493356917 -->
```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Паролни ўзгартириш ҳамённи кодлашда фойдаланилади</translation>
    
ERR
The translation is in Cyrillic script, not the required Latin script for 'uz@Latn'. Also, it inaccurately changes the sentence from an instruction ("Change the passphrase ...") to a description ("Changing the passphrase is used for wallet encryption"), which is misleading.

Correct translation:
Hamyonni shifrlash uchun ishlatiladigan maxfiy so‘zni o‘zgartiring
```

<!-- cache_translation_check_uz@Latn_089ddbd9180f7f228b2267c44e0c5eb58a08453e6252a1f83d67b18c444e9025 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>&amp;Hamyon nusxasi...</translation>
    
ERR
The translation "&Hamyon nusxasi..." is understandable but slightly ungrammatical/ambiguous for an action menu item. A clearer Uzbek translation for the command "Backup Wallet…" would be an infinitive/imperative phrase such as:

Correct translation examples:
&Hamyonni zaxiralash…
or
&Hamyon nusxasini yaratish…

(Each includes the single & shortcut and an ellipsis.)
```

<!-- cache_translation_check_uz@Latn_dbdc3990c2b1b8fa8dde4337dea36a096b374374a8d34f7ceb7b9a0616c2f53a -->
```
        <source>Sign &amp;message…</source>
        <translation>Xabarni &amp;signlash...</translation>
    
ERR
The translation uses an English-derived verb "signlash" instead of natural Uzbek ("imzolash"). Also prefer the single ellipsis character to match source. The ampersand exists exactly once (OK).

Correct translation:
Xabarni &imzolash…
```

<!-- cache_translation_check_uz@Latn_d01bffcf29fdf70c77c2e73c5905f697296116ab8eb11d0255e392208374e5b5 -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>&amp;PSBT ni fayldan yuklash...</translation>
    
ERR
There's an unwanted space between the acronym and the Uzbek suffix: "PSBT ni" should be "PSBTni" (no space). Also use the same ellipsis character as the source for consistency.

Correct translation:
&PSBTni fayldan yuklash…
```

<!-- cache_translation_check_uz@Latn_eea3ab9fd2ad9e14d92bd212c29b0e879403a0b4ae9ebfb04152e8787f3fef09 -->
```
        <source>Open &amp;URI…</source>
        <translation>&amp;URL manzilni ochish</translation>
    
ERR
Problems:
- The source uses "URI" but the translation uses "URL" (should preserve the same term unless intentionally changed).
- The source includes an ellipsis (…) that is missing in the translation.
- Minor stylistic: place of & is fine, but object case is better written as "manzilni".

Correct translation suggestion:
&URI manzilni ochish…
```

<!-- cache_translation_check_uz@Latn_13ad48aca877381998ab5a421b6e9f1b91ce91eb035e7e54d744123a188aa791 -->
```
        <source>&amp;File</source>
        <translation>&amp;Файл</translation>
    
SPAM
The translation is in Cyrillic (Russian "Файл"), not Uzbek in Latin script (uz@Latn). 

Correct translation:
&amp;Fayl
```

<!-- cache_translation_check_uz@Latn_ea7ee41489272cd603ea929b3b857c5998073c18ca99fc68b21a93da0a7dce18 -->
```
        <source>&amp;Settings</source>
        <translation>&amp; Созламалар</translation>
    
ERR
The translation is incorrect for the requested 'uz@Latn' (Uzbek Latin) locale: it uses Cyrillic script ("Созламалар") and contains a space after the ampersand entity. The ampersand should appear exactly once and the Uzbek text should be in Latin script.

Correct translation:
&Sozlamalar
```

<!-- cache_translation_check_uz@Latn_0b32b9034e2c7af9a8040fb27f199b0142d062771057b18491b64d48fd0b25d6 -->
```
        <source>&amp;Help</source>
        <translation>&amp;Ёрдам</translation>
    
ERR
The translation uses Cyrillic script ("Ёрдам") but the target locale 'uz@Latn' requires Latin script. Also keep the single & for the shortcut.

Correct translation:
&amp;Yordam
```

<!-- cache_translation_check_uz@Latn_c046697554241814382edf0e3da7f67ed475be8dde67e83a1983f103cfaae0ec -->
```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>Тўловлар (QR кодлари ва bitcoin ёрдамида яратишлар: URI’лар) сўраш</translation>
    
SPAM
The translation is in the Uzbek Cyrillic script (uz@Cyrl), not the requested Uzbek Latin script (uz@Latn).

Correct translation:
To‘lovlarni so‘rash (QR kodlar va bitcoin: URI’lar yaratadi)
```

<!-- cache_translation_check_uz@Latn_f9edbd28c2e8e4f3afea8e5331c30c9b7a7a312887aac3fc1464c1eb9194b59f -->
```
        <source>Show the list of used sending addresses and labels</source>
        <translation>Фойдаланилган жўнатилган манзиллар ва ёрлиқлар рўйхатини кўрсатиш</translation>
    
SPAM
The translation is in the Uzbek Cyrillic script (uz-Cyrl), while the language code 'uz@Latn' specifically requires the Uzbek Latin script.

Correct translation:
Foydalanilgan jo‘natish manzillari va yorliqlari ro‘yxatini ko‘rsatish
```

<!-- cache_translation_check_uz@Latn_1fab0ff46fa07f47df721507051eae4088a13a66b878cfce07e5d1fe838e3f83 -->
```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>Фойдаланилган қабул қилинган манзиллар ва ёрлиқлар рўйхатини кўрсатиш</translation>
    
SPAM
The translation is written in the Cyrillic script (uz@Cyrl), but the requested language code is 'uz@Latn' (Uzbek Latin).

Correct translation:
Foydalanilgan qabul qilingan manzillar va yorliqlar roʻyxatini koʻrsatish
```

<!-- cache_translation_check_uz@Latn_3562a0f4559474943fb35669c58aa061f571f27b20ce3ea9b36f028b9759a2e5 -->
```
        <source>&amp;Command-line options</source>
        <translation>&amp;Буйруқлар сатри мосламалари</translation>
    
SPAM
The translation is in the Uzbek Cyrillic script (uz@Cyrl), not the requested Uzbek Latin script (uz@Latn).

Correct translation:
&Buyruqlar satri moslamalari
```

<!-- cache_translation_check_uz@Latn_5e53923b82a15b5fc470e1f944749b4c886e3d53531a1b395ed3c186a4e1fdb8 -->
```
        <source>%1 behind</source>
        <translation>%1 орқада</translation>
    
SPAM
The translation is in the Uzbek Cyrillic script (uz-Cyrl), not the Uzbek Latin script (uz-Latn) as requested.

Correct translation:
%1 orqada
```

<!-- cache_translation_check_uz@Latn_caf8e1497be30ad8da79cf8bcd9ed179c520727628fad95368a36e5ff2011a13 -->
```
        <source>Last received block was generated %1 ago.</source>
        <translation>Сўнги қабул қилинган блок %1 олдин яратилган.</translation>
    
SPAM
The translation is written in the Cyrillic script (uz@Cyrl), but the requested language code is 'uz@Latn' (Uzbek Latin).

Correct translation:
Soʻnggi qabul qilingan blok %1 oldin yaratilgan.
```

<!-- cache_translation_check_uz@Latn_ad5c5da71c0efc75c3e3c7c021159d7b2d5d5bc27964d36852b5a43ccd9115dd -->
```
        <source>Transactions after this will not yet be visible.</source>
        <translation>Бундан кейинги пул ўтказмалари кўринмайдиган бўлади.</translation>
    
SPAM
The translation is written in the Cyrillic script (uz@Cyrl), but the requested language code is 'uz@Latn', which requires the Latin script.

Correct translation:
Bundan keyingi oʻtkazmalar hali koʻrinmaydi.
```

<!-- cache_translation_check_uz@Latn_696d027d65a6305cb1740a8c3350042ad0be59d91dfcc30b38bbb0f4b42f174b -->
```
        <source>Warning</source>
        <translation>Диққат</translation>
    
SPAM
The translation is provided in the Cyrillic script (Диққат), but the requested language code is 'uz@Latn', which specifies the Latin script.

Correct translation:
Diqqat
```

<!-- cache_translation_check_uz@Latn_deca15a81462eb6fa48ff03939863fed5974c113dafeca689ce8bff527bb8243 -->
```
        <source>Up to date</source>
        <translation>Янгиланган</translation>
    
SPAM
The translation is in the Cyrillic script (uz@Cyrl), but the requested language code is 'uz@Latn', which requires the Latin script.

Correct translation:
Yangilangan
```

<!-- cache_translation_check_uz@Latn_ae0b96cf49348fdc55f9a198a3ff27e4c811f3ff042a7e5043772cd909d0711f -->
```
        <source>Ctrl+Q</source>
        <translation>formatini olib tashlash(Ctrl+Q)</translation>
    
ERR
The translation is problematic. The English source "Ctrl+Q" refers to a keyboard shortcut and should not be translated or appended with a functional description unless present in the source. The added text "formatini olib tashlash" ("remove formatting") is erroneous and not in the original.

Correct translation:
Ctrl+Q
```

<!-- cache_translation_check_uz@Latn_034a3b663750f19d590686c6a884c3c69eae99168fa588dd85945f57fb09a532 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>&amp;Nusxalanganlar dan PSBT ni yuklash</translation>
    
ERR
Problems:
- The translation misses the trailing ellipsis (…) present in the source.
- Word formation/spacing is awkward: "Nusxalanganlar dan" should be one word or a more natural phrase (e.g., "nusxa taxtasidan" or "clipboarddan").
- The shortcut marker & appears once (good), but placement and the phrase should be more natural Uzbek.

Correct translation (suggested):
&Nusxa taxtasidan PSBT-ni yuklash…
```

<!-- cache_translation_check_uz@Latn_0faeb35a0c716ff0340069377b29c8af678b9c13f3b9f95b721f11388d60c89e -->
```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Nusxalanganlar qisman signlangan Bitkoin tranzaksiyalarini yuklash</translation>
    
ERR
The translation is inaccurate. The English phrase "Load Partially Signed Bitcoin Transaction from clipboard" means loading a single partially signed Bitcoin transaction from the clipboard. The given translation implies "load partially signed Bitcoin transactions that have been copied" and uses plural and a misleading construction.

Correct translation:
Buferdan qisman imzolangan Bitkoin tranzaksiyasini yuklash
```

<!-- cache_translation_check_uz@Latn_f2293a2136ac1d6b2997d99bc4cc0cd4fdf3036331a35e006af35aa15b8c986f -->
```
        <source>%1 client</source>
        <translation>%1 mijoz </translation>
    
ERR
There is an unwanted trailing space at the end of the translation ("mijoz "). This may cause formatting issues.

Correct translation:
%1 mijoz
```

<!-- cache_translation_check_uz@Latn_7d512b598b1ed9bdf8d5c5f6467f2867f2265c06b7de842f2f526e3ba35cec6a -->
```
        <source>Click for more actions.</source>
        <extracomment>A substring of the tooltip. "More actions" are available via the context menu.</extracomment>
        <translation>Ko'proq sozlamalar uchun bosing.</translation>
    
ERR
The translation of "actions" as "sozlamalar" is incorrect. "Sozlamalar" means "settings" in Uzbek, but "actions" refers to actions or deeds, not settings. The correct word should be "harakatlar" or "amallar".

Correct translation:
Ko'proq harakatlar uchun bosing.
```

<!-- cache_translation_check_uz@Latn_dac0647848b90704e4df6dacc855e8a92d7cdbeb9f4311a5117ccd090c5fdcf4 -->
```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini cheklash</translation>
    
ERR
The translation "Ijtimoiy tarmoq faoliyatini cheklash" means "Limit social network activity," which is inaccurate in the context of Bitcoin network activity. "Ijtimoiy tarmoq" refers to social networks, whereas the correct phrase should be about the network in general.

Correct translation:
Tarmoq faoliyatini o‘chirish
```

<!-- cache_translation_check_uz@Latn_9ebea8d02c4cdc38ebc78557edf4a5362306747a6e739e41e31ba410b24b595e -->
```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini yoqish</translation>
    
ERR
The translation "Ijtimoiy tarmoq faoliyatini yoqish" incorrectly translates "network" as "ijtimoiy tarmoq," which means "social network" in Uzbek. In the context of Bitcoin, "network" refers to the computer/data network, not a social network.

Correct translation:
Tarmoq faoliyatini yoqish
```

<!-- cache_translation_check_uz@Latn_da1eb4f33995465d44e000a09b07267dcd5c11ac999407fc7c9955f9cc8a8aad -->
```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>HD kalit yaratish &lt;b&gt;imkonsiz&lt;/b&gt;</translation>
    
ERR
The word "imkonsiz" means "impossible," which may convey that HD key generation is not possible, rather than it being "disabled." The correct translation for "disabled" is "faol emas" or "o‘chirib qo‘yilgan."

Correct translation:
HD kalit yaratish &lt;b&gt;o‘chirib qo‘yilgan&lt;/b&gt;
```

<!-- cache_translation_check_uz@Latn_0b2c6f1d6655f19c9050749b99ad56bcf72d66a0b07574eecae1257320be6c85 -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>Tranzaksiya &amp;IDsi ni va chiquvchi indeksni nusxalash</translation>
    
ERR
The translation has a spacing/affix error: "IDsi ni" incorrectly separates the possessive and accusative suffixes (there should be no space). Also word order/inflection should match the original objects.

Correct translation:
Tranzaksiya &IDsini va chiquvchi indeksni nusxalash
```

<!-- cache_translation_check_uz@Latn_b091013308c7c571bca7fb23b1c008bf87eae9c6f0dc0d2fd62fc8cf2c650b42 -->
```
        <source>&amp;Unlock unspent</source>
        <translation>Sarflanmaqan tranzaksiyalarni &amp;qulfdan chiqarish</translation>
    
ERR
Spelling/orthography error in Uzbek Latin: "Sarflanmaqan" is incorrect; correct form is "Sarflanmagan". Suggestion keeps the & once.

Correct translation:
Sarflanmagan tranzaksiyalarni &qulfdan chiqarish
```

<!-- cache_translation_check_uz@Latn_89e6e1727df638f168b9629de72e639d99b59a48691e81240d038937d608cb97 -->
```
        <source>Copy change</source>
        <translation>Нусха қайтими</translation>
    
ERR
The translation is in Uzbek Cyrillic ("Нусха қайтими") but the target requested is Uzbek in Latin script (uz@Latn). Also the phrasing is slightly awkward. A better Uzbek (Latin) translation:

Suggested translations:
- "Qaytimni nusxalash" 
- or more explicitly: "Qaytimni nusxa olish"

Use one of these depending on UI style (imperative/verb form).
```

<!-- cache_translation_check_uz@Latn_b10d204a51507f5b1840b4938e528c58776e96693d84d397079d9b67df53c0c3 -->
```
        <source>(%1 locked)</source>
        <translation>(%1 қулфланган)</translation>
    
ERR
The translation uses Cyrillic script ("қулфланган") but the target locale is 'uz@Latn' (Uzbek in Latin script). The format specifier %1 is preserved correctly and there are no extra spaces.

Correct translation (Latin Uzbek):
(%1 qulflangan)
```

<!-- cache_translation_check_uz@Latn_b79753252a76edb9988270135bb0acf0077e8cfaabf0665750d5f6631eddd0ca -->
```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>Hamyonni ko'chirmoqchi ekanligingizga ishonchingiz komilmi?&lt;i&gt;%1&lt;/i&gt;</translation>
    
ERR
The translation places the format specifier and HTML tags `<i1>%1</i>` at the end of the sentence, whereas in the source, it represents the name of the wallet being migrated and should be integrated into the sentence structure for better clarity. Additionally, the spacing around the tags is missing.

Correct translation:
<i>%1</i> hamyonini ko'chirmoqchi ekanligingizga ishonchingiz komilmi?
```

<!-- cache_translation_check_uz@Latn_37182631947619c7631bf26ff2e81dd44a04537083ce502d7869d0486527640e -->
```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>Hamyonni ko'chirish ushbu hamyonni bir yoki bir nechta deskriptor hamyonga aylantiradi. Hamyonning yangi zaxira nusxasini yaratish kerak bo'ladi.
Agar bu hamyonda faqat tomosha skriptlari mavjud bo'lsa, yangi hamyon yaratiladi, unda faqat tomosha qilish uchun skriptlar mavjud.
Agar bu hamyonda echilishi mumkin bo'lgan, lekin tomosha qilinmagan skriptlar bo'lsa, ushbu skriptlarni o'z ichiga olgan boshqa va yangi hamyon yaratiladi.

Migratsiya jarayoni ko'chirishdan oldin hamyonning zaxira nusxasini yaratadi. Ushbu zaxira fayli 1-2.legacy.bak deb nomlanadi va uni ushbu hamyon katalogida topish mumkin. Noto'g'ri migratsiya bo'lsa, zaxira nusxasini "Hamyonni tiklash" funksiyasi bilan tiklash mumkin.</translation>
    
ERR
There are several issues with the translation:
- "faqat tomosha skriptlari mavjud bo'lsa" mistakenly adds "faqat" (only), which is not present in the source. The original intent is "any watchonly scripts", not necessarily "only watchonly".
- The file name template "<wallet name>-<timestamp>.legacy.bak" is mistranslated as "1-2.legacy.bak", which removes the dynamic nature of the filename and could mislead users.
- The translation for "solvable but not watched scripts" is a bit unclear; "echilishi mumkin bo'lgan, lekin tomosha qilinmagan skriptlar" is passable, but could be more clearly rendered.
- Some loss of original detail and some awkward/unidiomatic phrases.

Correct translation:
Hamyonni migratsiya qilish ushbu hamyonni bir yoki bir nechta deskriptorli hamyonga aylantiradi. Yangi hamyon zaxira nusxasini yaratish zarur bo'ladi.
Agar bu hamyonda watchonly (faqat kuzatiladigan) skriptlar mavjud bo'lsa, ushbu watchonly skriptlarni o'z ichiga olgan yangi hamyon yaratiladi.
Agar bu hamyonda yechib bo'ladigan, ammo kuzatilmaydigan skriptlar mavjud bo'lsa, ularni o'z ichiga olgan yana boshqacha va yangi hamyon yaratiladi.

Migratsiya jarayoni hamyon ko'chirilishidan oldin uni zaxiralaydi. Zaxira fayli &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak nomi bilan, hamyon uchun katalogda saqlanadi. Notog‘ri migratsiya yuz bergan holatda, ushbu zaxira nusxasini "Hamyonni tiklash" funksiyasi yordamida qayta tiklash mumkin.
```

<!-- cache_translation_check_uz@Latn_7dfb2e0f4dd755f2794a9ee1604b8feb8e01c1e28c5bbf1d94e7e8bc051454dd -->
```
        <source>The wallet '%1' was migrated successfully.</source>
        <translation>hamyon '%1' muvaffaqiyatli ko'chirildi.</translation>
    
ERR
The translation is understandable but not fully accurate. The phrase "migrated successfully" in the context of software (e.g., Bitcoin wallet) should be translated as "muvaffaqiyatli migratsiya qilindi" or "muvaffaqiyatli o'tkazildi", not "ko'chirildi", which means "moved" and may be misleading in this context.

Correct translation:
Hamyon '%1' muvaffaqiyatli migratsiya qilindi.
```

<!-- cache_translation_check_uz@Latn_5473bbbbf7aaef717b9ccb2a13f16fd4de3e90f07472aa6f57ca6dc1289984d8 -->
```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Watchonly skriptlari nomli yangi hamyonga ko'chirildi%1</translation>
    
ERR
The translation is inaccurate and has formatting issues:
- The phrase "Watchonly skriptlari nomli yangi hamyonga ko'chirildi%1" is missing proper separation and does not reflect the possessive relationship or the correct structure.
- The variable '%1' should appear inside single quotes and at the same position as in the source.
- "Watchonly scripts" should be "Faqat kuzatiladigan skriptlar" in Uzbek.
- Should say "yangi '%1' nomli hamyonga ko'chirildi" (migrated to a new wallet named '%1').

Correct translation:
Faqat kuzatiladigan skriptlar yangi '%1' nomli hamyonga ko‘chirildi.
```

<!-- cache_translation_check_uz@Latn_4d3fdd2b28ea9f5f57457e50c3c1712bcdd30c56410a33857d3129c4eaee50dd -->
```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Yechish mumkin bo'lgan, lekin ko'rilmagan skriptlar nomli yangi hamyonga o'tkazildi%1</translation>
    
ERR
There are a few issues:
1. The format specifier '%1' is not preceded by a space, causing a formatting problem.
2. The translation omits the meaning of "named '%1'" (i.e., that the new wallet has the name '%1').
3. The wording is a bit unclear/awkward in Uzbek. The phrase "nomli yangi hamyonga" should refer to the new wallet, not the scripts.

Correct translation:
Yechilishi mumkin, lekin kuzatilmaydigan skriptlar '%1' deb nomlangan yangi hamyonga ko'chirildi.
```

<!-- cache_translation_check_uz@Latn_f6880955ec667ea50cb4e4bfef71c9453a6bb921663e3e0e0b7739eadefd382a -->
```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Wallet tiklanmoqda&lt;b&gt;%1&lt;/b&gt;</translation>
    
ERR
There is a spacing issue: there should be a space after the ellipsis ("tiklanmoqda") and before the HTML tag. The original also ends with an ellipsis (…), but the translation omits it. 

Correct translation:
Wallet tiklanmoqda &lt;b&gt;%1&lt;/b&gt;…
```

<!-- cache_translation_check_uz@Latn_f6880955ec667ea50cb4e4bfef71c9453a6bb921663e3e0e0b7739eadefd382a -->
```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Wallet tiklanmoqda&lt;b&gt;%1&lt;/b&gt;</translation>
    
ERR
There is a spacing issue: there should be a space after the ellipsis ("tiklanmoqda") and before the HTML tag. The original also ends with an ellipsis (…), but the translation omits it. 

Correct translation:
Wallet tiklanmoqda &lt;b&gt;%1&lt;/b&gt;…
```

<!-- cache_translation_check_uz@Latn_39bffa859bede978a407d2d7194a7cd3b1def2df9e2279c402dae209a2353b4e -->
```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Ushbu hamyon uchun maxfiy kalitlarni o'chirish. Maxfiy kalitsiz hamyonlar maxfiy kalitlar yoki import qilingan maxfiy kalitlar, shuningdek, HD seedlarga ega bo'la olmaydi.</translation>
    
ERR
The translation omits the explanation: "This is ideal for watch-only wallets." Additionally, some meaning is lost by not clarifying that wallets with private keys disabled will not have *any* private keys and cannot *have an HD seed*.

Correct translation:
Ushbu hamyon uchun maxfiy kalitlarni o‘chiring. Maxfiy kalitlari o‘chirilgan hamyonlarda maxfiy kalitlar bo‘lmaydi hamda ular HD urug‘ (seed) yoki import qilingan maxfiy kalitlarga ega bo‘la olmaydi. Bu kuzatish uchun mo‘ljallangan (“faqat o‘qish uchun”) hamyonlar uchun ideal.
```

<!-- cache_translation_check_uz@Latn_3b87db80994dc838fb12b6f3b2ff58a3f70ccc7d1881af14ccc499ca63f84775 -->
```
        <source>&amp;Label</source>
        <translation>&amp;Ёрлик</translation>
    
ERR
The translation uses Cyrillic script ("Ёрлик") but the language tag is uz@Latn (Uzbek in Latin script). Also the ampersand shortcut exists exactly once which is correct, but the script mismatch is wrong.

Correct translation (Uzbek Latin):
&amp;Yorliq
```

<!-- cache_translation_check_uz@Latn_56ee94421797df392214c907d00171950efdcb8d1e39619037670ed52bf359b5 -->
```
        <source>&amp;Address</source>
        <translation>&amp;Манзил</translation>
    
ERR
The translation is in Uzbek Cyrillic ("Манзил") but the target locale is uz@Latn (Uzbek in Latin script). Also keep the single & for the shortcut.

Correct translation:
&Manzil
```

<!-- cache_translation_check_uz@Latn_a773a2fb9c1c29d18c7e480879c8f2269ebb18a6ac024266c97e7f2ec888f640 -->
```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Yuboruvchi(%1manzil) va  qabul qiluvchi(%2manzil) bir xil bo'lishi mumkin emas</translation>
    
ERR
The provided translation is inaccurate and omits important information. It condenses the message and does not accurately convey that the address "%1" already exists as a receiving address with label "%2" and, as a result, cannot be added as a sending address. It also incorrectly places 'manzil' after the label numbers, which doesn't match the intended placeholders.

Correct translation:
Manzil "%1" "%2" yorlig'i bilan qabul qiluvchi manzil sifatida allaqachon mavjud, shu sababli uni yuboruvchi manzil sifatida qo'shib bo'lmaydi.
```

<!-- cache_translation_check_uz@Latn_c8c1ef80f21cf191ef166a64aa8d80046da817483d9e3dd4da206c04fdd2fc8b -->
```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>Kiritilgan %1manzil allaqachon %2yorlig'i bilan manzillar kitobida</translation>
    
ERR
There are format and clarity issues in the translation:
- The variable placeholders (%1 and %2) are joined to the adjacent words without necessary spaces, which makes the translation unclear and hard to read.
- The sentence is incomplete and lacks a verb at the end.

Correct translation:
Kiritilgan "%1" manzili allaqachon manzillar kitobida "%2" yorlig‘i bilan mavjud.
```

<!-- cache_translation_check_uz@Latn_520508b7de677dc7b3047a2030d5be455288823033089e489a3325cc22a5d639 -->
```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>OK ni bosganingizda, %1to'liq blok zanjirini (%2GB) yuklab olish%4 va qayta ishlash boshlanadi, %3birinchi boshlangan%4 tranzaksiyalardan boshlab.</translation>
    
ERR
The translation has several issues:
- The translation is not grammatically correct (e.g. "OK ni bosganingizda, %1to'liq blok zanjirini" should be "OK ni bosganingizda, %1 to'liq %4 blok zanjirini").
- Words are jammed together without spaces ("%1to'liq" instead of "%1 to'liq", "%2GB" instead of "%2 GB", "%3birinchi bosh" instead of "%3 birinchi...").
- The order of clauses is confusing and does not retain the clear structure of the original.
- The translation of "begin to download and process" is not accurate ("yuklab olish%4 va qayta ishlash boshlanadi" is awkward and unclear).
- Format specifiers are misplaced regarding their context.

Correct translation:
OK ni bosganingizda, %1 %4 blok zanjirining to‘liq nusxasini (%2 GB) yuklab olish va qayta ishlashni boshlaydi. Bunda %4 dastlab ishga tushirilganida, %3 da amalga oshirilgan eng dastlabki tranzaksiyalardan boshlanadi.
```

<!-- cache_translation_check_uz@Latn_2ccf611d76febf8266bdf63d05047fd8b28da4f2bc27b7aba334d7079f2b1d82 -->
```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Bu katalogda %1  GB ma'lumot saqlanadi</translation>
    
ERR
There is an extra space between "%1" and "GB" in the translation which is not present in the source. Also, the sentence is missing a period at the end to match the source. Additionally, the word "Approximately" ("Taxminan" in Uzbek) is omitted, which affects the meaning.

Correct translation:
Bu katalogda taxminan %1 GB ma'lumot saqlanadi.
```

<!-- cache_translation_check_uz@Latn_c758852d15986f203bf3206d7c988e09390436ad4b393a8b90dac6b1b12fe53a -->
```
        <source>%1 will download and store a copy of the Bitcoin block chain.</source>
        <translation> Bitcoin blok zanjirining%1 nusxasini yuklab oladi va saqlaydi</translation>
    
ERR
There is a formatting issue: there should not be a space before "Bitcoin", and the variable %1 should directly correspond in placement to the source text, not moved after "blok zanjirining". Also, "Bitcoin block chain" is better translated as "Bitcoin blok zanjiri". The translation more literally reads: "the copy of the Bitcoin block chain %1 will download and store", which is syntactically awkward. Lastly, the position of %1 is wrong.

Correct translation:
%1 Bitcoin blok zanjirining nusxasini yuklab oladi va saqlaydi.
```

<!-- cache_translation_check_uz@Latn_cb673f65f58cc336ca4940911f502929cf0f1bae65712ded6965d300948c4a24 -->
```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Noma'lum. Sarlavhalarni oldindan sinxronlash (, %1%2%)…</translation>
    
ERR
The format specifiers are not copied over correctly. In the translation, the order and placement of %1 and %2 are wrong—they should be in the same place as in the source: (%1, %2%). Additionally, the translation has superfluous commas and percentage signs.

Correct translation:
Noma'lum. Sarlavhalar oldindan sinxronlanmoqda (%1, %2%)…
```

<!-- cache_translation_check_uz@Latn_7f0e86460d7a30ae9deece9352530f2b6c0b943fe0321c72c37707497f7b940b -->
```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Manzilni qo'shib qo'yish</translation>
    
ERR
The translation is inaccurate. "Manzilni qo'shib qo'yish" means "Add the address" or "Insert address", not "Paste address from clipboard". The original instruction refers specifically to pasting from the clipboard, which is not reflected here.

Correct translation:
Manzilni buferdan joylashtirish
```

<!-- cache_translation_check_uz@Latn_582ea3461ff481264a1373b04cdce959bb530158cabe386c309d54e9210ecbe1 -->
```
        <source>&amp;Start %1 on system login</source>
        <translation>%1 ni sistemaga kirish paytida &amp;ishga tushirish</translation>
    
ERR
The translation is mostly correct, but there's a spacing error: in Uzbek the accusative suffix "-ni" should be attached to the word (no space) so "%1 ni" is wrong. Also a more natural word order is to put the time phrase first.

Correct translation:
Sistemaga kirish paytida %1ni &ishga tushirish
```

<!-- cache_translation_check_uz@Latn_e264875aa2d0181d8435998524cf18031b88fdaa0b06cae8efcf9381e1e30baf -->
```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi. Barcha bloklar hali ham to'liq tasdiqlangan. Bu sozlamani qaytarish butun blok zanjirini qayta yuklab olishni talab qiladi.</translation>
    
ERR
There are some issues in the translation:
- The phrase "Do'kon tranzaksiyalari katta xotira talab qilgani tufayli" is an inaccurate rendering of the source. "Do'kon" means shop/store, which is incorrect here.
- The overall structure is not faithful to the original. The first sentence should communicate "Enabling pruning reduces disk space", not provide an explanation related to "shop transactions".
- The phrase "blok zanjiri" is acceptable for "blockchain", but "xotirada joy kamayishiga olib keladi" literally means "leads to a decrease in memory space", which is less precise than "reduces disk space".
- "%1" and format specifiers, if present, should be preserved, but there are none here.
- Otherwise, there are no stray spaces or double spaces.

Correct translation:
Pruning funksiyasini yoqish tranzaksiyalarni saqlash uchun zarur bo‘lgan disk xotirasini sezilarli darajada kamaytiradi. Barcha bloklar hamon to‘liq tekshiriladi. Ushbu sozlamani qaytarish butun blokcheynni qayta yuklab olishni talab qiladi.
```

<!-- cache_translation_check_uz@Latn_3deb161f2d4a1731b172cc3e0a1696bfca101ce25f291841c72284224197c8f1 -->
```
        <source>Size of &amp;database cache</source>
        <translation>&amp;Ma'lumotlar bazasi hajmi</translation>
    
ERR
The translation omits the word "cache" — it reads "database size" instead of "size of database cache". Also ensure the & shortcut remains exactly once.

Correct translation:
&Ma'lumotlar bazasi kesh hajmi
```

<!-- cache_translation_check_uz@Latn_bccdd656ff63aeb54d6ec0e8bc33f9b397ceed04bf188f720e33d34bbedfe0f2 -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>Skriptni &amp;tekshirish thread lari soni</translation>
    
ERR
Problems:
- The translation mixes English "thread" with Uzbek and incorrectly separates the plural suffix ("thread lari" should be one word).
- Word order and spacing are awkward.
- Shortcut marker "&" is present once (good), but placement is fine only if the shortcut should be on "t" of "tekshirish".

Suggested corrections (two options):

1) Closer to original with "thread" preserved:
Skriptni &tekshirish threadlari soni

2) Fully Uzbek-localized (preferred):
Skriptni &tekshirish ish oqimlari soni
```

<!-- cache_translation_check_uz@Latn_dff130823229f5844efc5539a4f524656cf366d555f0d934697c2d55a730caff -->
```
        <source>&amp;Network</source>
        <translation>&amp;Internet tarmog'i</translation>
    
ERR
Translation is understandable but slightly awkward/redundant: "Internet tarmog'i" literally "Internet network". The source is a single menu label "Network" and should be translated more concisely as "Tarmoq". The shortcut marker (&) is present exactly once — keep it.

Correct translation:
&amp;Tarmoq
```

<!-- cache_translation_check_uz@Latn_acc770a04a274fddb912f9a3aff63a29e610d5e7c3f76f217cc445b99f968a27 -->
```
        <source>Prune &amp;block storage to</source>
        <translation>&amp;Blok xotirasini bunga kesish:</translation>
    
ERR
The translation is slightly unnatural and adds a colon. "kesish" (to cut) is suboptimal for "prune" in this context; Uzbek commonly uses "qisqartirish" or "saqlashni ...gacha qisqartirish". Also remove the trailing colon to match the source.

Suggested correction:
&Blok xotirasini ...gacha qisqartirish
```

<!-- cache_translation_check_uz@Latn_6ad88ee4d8fdc63e07b5e6939b98b4c12c99e1c3c77745c622921ab88163e7bb -->
```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>Skriptni tekshirish ip lari sonini belgilang. </translation>
    
ERR
The translation is incomplete and omits important explanatory content from the original, especially the explanation about negative values corresponding to the number of cores to leave free. Additionally, there is an incorrect space in "ip lari" (should be "iplari").

Correct translation:
Skriptni tekshirish iplari sonini belgilang. Manfiy qiymatlar — tizimda bo‘sh qolishi kerak bo‘lgan yadrolar soni.
```

<!-- cache_translation_check_uz@Latn_0101022453d88b3baa7d30d27580774b9f7897570038d7697bc0a120a624f6b9 -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Standart bo'yicha chegirma belgilash</translation>
    
ERR
The translation is inaccurate and incomplete. "Standart bo'yicha chegirma belgilash" means roughly "Set a discount by default" and does not mention "fee" (to'lov/komissiya) or the action of subtracting it from the amount. It also omits the required single & shortcut marker.

Correct translation (with a single & for the shortcut):
Sukut bo'yicha &to'lovni miqdordan ayirish
```

<!-- cache_translation_check_uz@Latn_449ddecc2e34f530426e7800cc8ea912099c2f092c6ca77e38ec8231c02e0e11 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>Tasdiqlanmagan oʻzgarishlarni &amp;sarflash</translation>
    
ERR
The Uzbek translation uses "oʻzgarish" which means a general "change/alteration" and is not appropriate for Bitcoin "change" (the leftover amount). Also word choice/number could be improved.

Suggested correct translations (keep the & for the shortcut exactly once):
- Singular: Tasdiqlanmagan qaytimni &sarflash
- Plural: Tasdiqlanmagan qaytimlarni &sarflash
```

<!-- cache_translation_check_uz@Latn_becaac9b2d42913c31b712a7f2ea5aa66d63507bedbaed983b2aeda41b21ec04 -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>&amp;PSBT nazoratini yoqish</translation>
    
ERR
The Uzbek (Latin) translation uses the singular form "nazoratini" while the source refers to "controls" (plural). Keep the & shortcut exactly once before PSBT.

Correct translation:
&amp;PSBT nazoratlarini yoqish
```

<!-- cache_translation_check_uz@Latn_51dae1c4c9d5307ed7b84ce5bc2a33dbcbf2d99118d963b06520eac20425248b -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Kiruvchi va kirish ulanishlariga ruxsat bering</translation>
    
ERR
Problems:
- The translation adds an extra phrase "va kirish" making it redundant/awkward ("Kiruvchi va kirish ulanishlariga" ≈ "incoming and entry connections").
- The original contains a single '&' indicating a shortcut key (incomin&g). The translation omits the '&' entirely. The translation must include exactly one '&'.

Correct translation suggestions (include one & for the shortcut):
- &Kiruvchi ulanishlarga ruxsat bering

(Alternatively, if you prefer the verb-first form)
- &Kiruvchi ulanishlarga ruxsat bering
```

<!-- cache_translation_check_uz@Latn_0fb48d2f7cf1429e96ef0d02b5a165bbb186e0b3fda91bee264ef425cc3876bf -->
```
        <source>&amp;Connect through SOCKS5 proxy (default proxy):</source>
        <translation>SOCKS5 proksi-server orqali ulaning (standart proksi-server):</translation>
    
ERR
The translation is fine otherwise, but it omits the required '&' shortcut marker present in the source. Add exactly one '&' in the translation.

Correct translation:
&SOCKS5 proksi-server orqali ulaning (standart proksi-server):
```

<!-- cache_translation_check_uz@Latn_2148df0654702cc051d7fdb71da8fd99bbea97db965eeaa00f671da7917b7dd7 -->
```
        <source>Proxy &amp;IP:</source>
        <translation>Прокси &amp;IP рақами:</translation>
    
ERR
The translation uses Uzbek in Cyrillic script ("Прокси &amp;IP рақами:") but the target locale 'uz@Latn' requires Latin script. Otherwise the meaning and the & shortcut are preserved.

Correct translation in Uzbek (Latin script):
Proksi &IP-raqami:
```

<!-- cache_translation_check_uz@Latn_42c29c9d25e766b1f2f83649bbd1c55870893df8d6f66506b5e7fb354a146a2f -->
```
        <source>&amp;Port:</source>
        <translation>&amp;Порт:</translation>
    
ERR
The translation uses Cyrillic script ("Порт") but the target language variant is Uzbek Latin (uz@Latn). The ampersand is present exactly once, and there are no format specifiers or spacing issues, but the script is incorrect.

Correct translation:
&amp;Port:
```

<!-- cache_translation_check_uz@Latn_9a8118ab8740931db10ca061033c731b58c5ac146f9a34ecd2011d695d080da0 -->
```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>Прокси порти (e.g. 9050)</translation>
    
ERR
The translation is partially in Cyrillic script ("Прокси порти"), whereas 'uz@Latn' requires Latin script. Additionally, "e.g." should be translated as "masalan" or localized properly, not kept in English. The correct translation should be fully in Latin Uzbek.

Correct translation:
Proksi porti (masalan, 9050)
```

<!-- cache_translation_check_uz@Latn_7ebfc5a3196cf1ee1f347a3ab5b5d56ed5e0ea7f00dc37f8f034fbee070c1565 -->
```
        <source>&amp;Show tray icon</source>
        <translation> belgisini ko'rsatish</translation>
    
ERR
Problems:
- Missing ampersand (&) that marks the shortcut key — the source has one and the translation must include exactly one.
- Leading stray space at the start of the translation.
- The word "tray" is untranslated/unclear; better to use "tizim tepsisi" or simply "tepsi" to convey "system tray".

Correct translation suggestions (no leading spaces, exactly one &):
&Tepsi belgisini ko'rsatish
or more explicit:
&Tizim tepsisidagi belgisini ko'rsatish
```

<!-- cache_translation_check_uz@Latn_81976e189b79778b052c13f35c3d762daa60a1279e08258b289bba46ad15a7b5 -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>Манзиллар панели ўрнига трэйни &amp;йиғиш</translation>
    
ERR
The translation is in Uzbek Cyrillic script rather than the requested Latin (uz@Latn) script. Also phrasing can be improved to match UI terminology. The ampersand must appear exactly once (it currently does, but overall script is wrong).

Correct translation (uz@Latn):
Vazifa paneli o'rniga bildirishnoma maydoniga &kichraytirish
```

<!-- cache_translation_check_uz@Latn_65d7dd83131b153850001f2356a993d4290b9022a62b034c27c93adaa8871bf4 -->
```
        <source>M&amp;inimize on close</source>
        <translation>Ёпишда й&amp;иғиш</translation>
    
ERR
The translation is in Uzbek Cyrillic, but the requested locale is uz@Latn (Uzbek in Latin script). Also the phrasing is awkward. The source has no format specifiers but does include a single & for the shortcut; the translation must also include exactly one &.

Correct translation (Uzbek Latin):
Yopilganda &kichraytirish
```

<!-- cache_translation_check_uz@Latn_b8d286c558d788b033022441628fac590d23aaff6ef1871ed35e16fed053de4c -->
```
        <source>&amp;Display</source>
        <translation>&amp;Кўрсатиш</translation>
    
ERR
The translation is in Cyrillic (Кўрсатиш) but the target locale is uz@Latn (Uzbek in Latin script). The ampersand for the shortcut is present exactly once which is fine, but the script is wrong.

Correct translation (Latin Uzbek), keeping the shortcut marker:
<translation>&amp;Ko'rsatish</translation>
```

<!-- cache_translation_check_uz@Latn_d4f5abbeb0fab4d441281827de91559607309a492225fc6c38a267a96862d6ff -->
```
        <source>User Interface &amp;language:</source>
        <translation>Фойдаланувчи интерфейси &amp;тили:</translation>
    
ERR
The translation is written in Uzbek Cyrillic script, but the requested locale 'uz@Latn' requires Uzbek in Latin script. The ampersand is present once and placement is acceptable.

Correct translation (Uzbek, Latin script):
Foydalanuvchi interfeysi &tili:
```

<!-- cache_translation_check_uz@Latn_0e3ca61ef9b4b3d222e835e420dadd119cd2a055958ea7dcce6cad35adaf389e -->
```
        <source>&amp;Unit to show amounts in:</source>
        <translation>Миқдорларни кўрсатиш учун &amp;қисм:</translation>
    
ERR
The translation is in Uzbek Cyrillic, but the requested locale is Uzbek Latin (uz@Latn). Also "қисм" (qism) is "part" — a better word for "unit" is "birlik". Keep the single & for the shortcut.

Correct translation (Uzbek, Latin script):
Miqdorlarni ko'rsatish uchun &birlik:
```

<!-- cache_translation_check_uz@Latn_86b649f142caa18573376e215968af6cf000f0ff7b0ae86be73e0297ea61e94c -->
```
        <source>&amp;Cancel</source>
        <translation>&amp;Бекор қилиш</translation>
    
ERR
The translation uses Cyrillic script ("Бекор қилиш") while the requested locale 'uz@Latn' requires Uzbek in Latin script. No format specifiers or extra whitespace issues, and the ampersand is present exactly once, but the script is incorrect.

Correct translation (Latin script):
&amp;Bekor qilish
```

<!-- cache_translation_check_uz@Latn_064134c16d306cdb8f37034df911050f9953c8bfaa27d8f88aa0f2a7d840b659 -->
```
        <source>none</source>
        <translation>йўқ</translation>
    
ERR
The translation "йўқ" is in Cyrillic script, but 'uz@Latn' denotes Uzbek in Latin script. The correct translation in Latin script should be "yo‘q".

Correct translation:
yo‘q
```

<!-- cache_translation_check_uz@Latn_1a0d00f66e929dce26744209aad3c59299a3851dd0771b9a00821e7bf5b2f381 -->
```
        <source>This change would require a client restart.</source>
        <translation>Ушбу ўзгариш мижозни қайтадан ишга туширишни талаб қилади.</translation>
    
ERR
The translation is in Uzbek but it uses the Cyrillic alphabet, while 'uz@Latn' specifies the Latin alphabet. Additionally, the meaning is otherwise accurate.

Correct translation:
Ushbu o‘zgarish mijozni qaytadan ishga tushirishni talab qiladi.
```

<!-- cache_translation_check_uz@Latn_c32cd0ba982faa29ddde042e81219974897f9e371d8c7da996e751c22464e60b -->
```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Жами ўтказмалар ҳозиргача тасдиқланган ва сафланадиган баланс томонга ҳали ҳам ҳисобланмади</translation>
    
ERR
The translation is incorrect because it mixes Cyrillic script (should be Latin for 'uz@Latn') and is also not accurate to the source meaning. It introduces unnecessary complexity and some semantic errors, and uses a passive construction that confuses the intent.

Correct translation:
Tasdiqlanmagan va sarflanadigan balansga hali kiritilmagan tranzaksiyalarning jami
```

<!-- cache_translation_check_uz@Latn_499f8443893148a2e862c75471dea81c3fd83e4a877de1c7d4ea27d92645a6c4 -->
```
        <source>Immature:</source>
        <translation>Тайёр эмас:</translation>
    
ERR
The translation is in Uzbek Cyrillic script (Тайёр эмас), but 'uz@Latn' requires Latin script. It should use Latin, not Cyrillic letters.

Correct translation:
Tayyor emas:
```

<!-- cache_translation_check_uz@Latn_d1a781ed64e043bfde41b29f13f270376ccf23d892abd89573657eea3202979f -->
```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarni qaytarish uchun Sozlamalar-&gt;Qiymatlar.</translation>
    
ERR
The translation omits part of the instruction about "unmasking" values (i.e., "uncheck" is not explicitly translated) and does not accurately reflect the actionable step for the user. The word "qaytarish" (to return) is misleading in this context, and "Settings->Mask values" is not correctly translated or explained.

Correct translation:
"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirildi. Qiymatlarni ko‘rsatish uchun Sozlamalar->Qiymatlarni yashirish belgisini olib tashlang.
```

<!-- cache_translation_check_uz@Latn_d514c77bc0d72c968bb7e1f06c63aaa21e669cfb6fc07ca4aa148d24cb14a2fa -->
```
        <source>Failed to load transaction: %1</source>
        <translation>Tranzaksiyani yuklab bo'lmadi</translation>
    
ERR
The translation is missing the format specifier '%1' which is present in the source text.

Correct translation:
Tranzaksiyani yuklab bo'lmadi: %1
```

<!-- cache_translation_check_uz@Latn_51e0e582a0a1eb654dd898fd98c00e02e811efa7c2af9dacb1d777a1fa98db43 -->
```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>Hamyon maʼlumotlarga imzo qoʻyib boʻlmaydi.</translation>
    
ERR
The translation omits the crucial information that signatures cannot be applied to "inputs" while the wallet is locked. It simply states that it's not possible to sign "wallet data", which is inaccurate. It also omits the mention of the wallet being locked.

Correct translation:
Hamyon qulflanganida kirishlarga imzo qoʻyib boʻlmaydi.
```

<!-- cache_translation_check_uz@Latn_c6a0843bc324a45401dd945cdb67a42f3d1d669af03338b375ccedd3dff49178 -->
```
        <source>URI handling</source>
        <translation>URI осилиб қолмоқда</translation>
    
ERR
The translation is problematic. The original English "URI handling" refers to the process of handling (processing, managing) URIs, but the Uzbek translation "URI осилиб қолмоқда" (note: this is written partly in Cyrillic, not Latin; it also literally means "URI is hanging/crashing/failing") does not match the meaning, and is also written in the wrong script.

Correct translation:
URI bilan ishlash
```

<!-- cache_translation_check_uz@Latn_4f37b6285df7118abe6955c3aacd980c137896983c67eae5f9794882fe5f8591 -->
```
        <source>Type</source>
        <extracomment>Title of Peers Table column which describes the type of peer connection. The "type" describes why the connection exists.</extracomment>
        <translation>Тури</translation>
    
ERR
The translation uses Cyrillic script ("Тури"). However, 'uz@Latn' specifies Uzbek in Latin script. The translation should use the Latin script.

Correct translation:
Turi
```

<!-- cache_translation_check_uz@Latn_f67d81578f577eb2d26f2bb8209396f84c7f1c714b509a30df5b6ef89566b425 -->
```
        <source>Inbound</source>
        <extracomment>An Inbound Connection from a Peer.</extracomment>
        <translation>Ички йўналиш</translation>
    
ERR
The translation is in Cyrillic script ('Ички йўналиш'), but 'uz@Latn' should be in the Latin script. Furthermore, "Ички йўналиш" literally means "internal direction"—a more accurate translation for "Inbound" in the context of network connections would be "Kiruvchi".

Correct translation:
Kiruvchi
```

<!-- cache_translation_check_uz@Latn_5f4688ddc3ed0689e37ec9cd0c4dbf74e8bc70837ee28b6b856a4b381a662da7 -->
```
        <source>&amp;Copy Image</source>
        <translation>Расмдан &amp;нусха олиш</translation>
    
ERR
The translation is in Cyrillic script ("Расмдан &нусха олиш") but the target locale 'uz@Latn' requires Uzbek in Latin script. The ampersand is present exactly once, which is fine, but the script must be Latin.

Correct translation (Uzbek, Latin script):
Rasmni &nusxa olish
```

<!-- cache_translation_check_uz@Latn_ef91a7eaf88d2be145131d8332eca6b62c115c709639b593331f51700a4b25e2 -->
```
        <source>Client version</source>
        <translation>Мижоз номи</translation>
    
ERR
The translation "Мижоз номи" is not correct for "Client version." It translates as "client name" and also uses Cyrillic script instead of Latin. The correct translation in Latin script would be:

Correct translation:
Mijoz versiyasi
```

<!-- cache_translation_check_uz@Latn_5f3796557815a27466975faa34a0b704d2b5bf9554d39990bc0a4309bb106d06 -->
```
        <source>&amp;Information</source>
        <translation>&amp;Маълумот</translation>
    
ERR
The translation is in Uzbek Cyrillic (Маълумот) but the locale requested is uz@Latn (Uzbek in Latin script). The ampersand is present exactly once which is correct.

Correct translation in Latin script:
&Ma'lumot
```

<!-- cache_translation_check_uz@Latn_803398c68a3af7e959ef140dd81d6b165b6f273578b6cb107c9eb20e62a14ea4 -->
```
        <source>&amp;Peers</source>
        <translation>&amp;Уламлар</translation>
    
ERR
The translation uses Cyrillic characters (Уламлар) but the requested locale is Uzbek in Latin script (uz@Latn). Also "Уламлар" is uncommon; a clearer Uzbek Latin translation for "Peers" is "Tengdoshlar". The ampersand should remain exactly once.

Correct translation:
&amp;Tengdoshlar
```

<!-- cache_translation_check_uz@Latn_97bcd8ab5f7e0ba27c66dac59846aab8a6820e720b41c8da32716ca6e7826282 -->
```
        <source>&amp;Open</source>
        <translation>&amp;Очиш</translation>
    
ERR
The translation is in Cyrillic script ("&Очиш") but the target locale 'uz@Latn' requires Uzbek in Latin script. Also ensure the ampersand is present exactly once.

Correct translation (Latin-script Uzbek):
&amp;Ochish
```

<!-- cache_translation_check_uz@Latn_19b3ca6911125e93c8b0f704d508cba2bf2734b74b7ac4e2c1dcf74a3ff1c145 -->
```
        <source>&amp;Console</source>
        <translation>&amp;Терминал</translation>
    
ERR
The translation uses Cyrillic script ("Терминал") but the target language variant is Uzbek in Latin script (uz@Latn). Also UI convention expects Latin letters. The ampersand is present exactly once, which is fine.

Correct translation (in Uzbek Latin):
&amp;Konsol
```

<!-- cache_translation_check_uz@Latn_28a156fa257b28f2b499662ab300c50d2141d521f3c73178504d923491e666c6 -->
```
        <source>&amp;Network Traffic</source>
        <translation>&amp;Тармоқ трафиги</translation>
    
ERR
The translation is in Uzbek Cyrillic script, but the requested language variant is 'uz@Latn' (Uzbek in Latin script). Also ensure the ampersand is retained exactly once.

Correct translation (Latin script):
&amp;Tarmoq trafigi
```

<!-- cache_translation_check_uz@Latn_3011e6d9d5f791a0966f5d71ba288d25b859e6846982d5a6fd2eeab2dad04afb -->
```
        <source>Clear console</source>
        <translation>Терминални тозалаш</translation>
    
ERR
The translation is in Cyrillic script, not the requested Latin script ('uz@Latn'). The correct translation in Latin Uzbek would be:

Konsolni tozalash

Correct translation:
<translation>Konsolni tozalash</translation>
```

<!-- cache_translation_check_uz@Latn_c5b568440de9e39da9e967d3cc5b6175bf888d223698987adcb21ba4ebd62cee -->
```
        <source>In:</source>
        <translation>Ичига:</translation>
    
ERR
The translation is in Cyrillic script ("Ичига:"), but 'uz@Latn' requires Latin script. Additionally, "Ichiga:" is not the most accurate translation for "In:" in this context. In Bitcoin transaction contexts, "In:" usually refers to transaction inputs.

Correct translation:
Kirish:
```

<!-- cache_translation_check_uz@Latn_23495be8d19e28cfb68935ae81b9e2804fa148083905fb0e2214871ca88a1c55 -->
```
        <source>To</source>
        <translation>Га</translation>
    
ERR
The translation uses Cyrillic script ("Га"), but the 'uz@Latn' language code specifies the use of Latin script only. The translation should be in Uzbek Latin script.

Correct translation:
To = "Ga"
So, the correct translation in Latin script is:
Ga
```

<!-- cache_translation_check_uz@Latn_4ba8deff5d5a15b470a633ad46be786fa715e6388f05538a64a2764ac409c161 -->
```
        <source>From</source>
        <translation>Дан</translation>
    
ERR
The translation "Дан" is in Cyrillic script, whereas 'uz@Latn' requires the Latin script for Uzbek. The correct Latin script translation for "From" is "Kimdan" or "Dan" (depending on context, but "Kimdan" is safer for clarity).

Correct translation:
Kimdan
```

<!-- cache_translation_check_uz@Latn_51fa06fb0f72cfe0575f287d2a0ac520f59e817b7fefbc47c3a7791ee3e5386e -->
```
        <source>&amp;Amount:</source>
        <translation>&amp;Миқдор:</translation>
    
ERR
The translation uses Cyrillic script ("Миқдор") but the target locale 'uz@Latn' requires Latin script. No format specifiers present and the ampersand is used exactly once, but the script is wrong.

Correct translation:
&amp;Miqdor:
```

<!-- cache_translation_check_uz@Latn_ede49ca0b9b5ea4b6fa98f9961c06bc578b1a73c6462123462ad9a9eb4a86293 -->
```
        <source>&amp;Label:</source>
        <translation>&amp;Ёрлиқ:</translation>
    
ERR
The translation uses Cyrillic script ("&amp;Ёрлиқ:") but the target language tag is uz@Latn (Uzbek in Latin script). Use the Latin-script Uzbek word.

Correct translation:
&amp;Yorliq:
```

<!-- cache_translation_check_uz@Latn_c6c1527c1dbff46699b1e9488b8137361710fcf68676fc7f0459ea27c5d36e31 -->
```
        <source>&amp;Message:</source>
        <translation>&amp;Хабар:</translation>
    
ERR
The translation uses Cyrillic script ("Хабар") but the target language tag is uz@Latn (Uzbek in Latin script). The ampersand and colon are correct, but the word should be in Latin letters.

Correct translation:
&amp;Xabar:
```

<!-- cache_translation_check_uz@Latn_e311c9f62880c155218af6be6a14f82d7f0a663490913d46b53dd2e0a3aeb857 -->
```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>Хоҳланган миқдор сўрови. Кўрсатилган миқдорни сўраш учун буни бўш ёки ноль қолдиринг.</translation>
    
ERR
The translation is in Cyrillic script, whereas 'uz@Latn' specifies the Latin alphabet. Additionally, the wording is inaccurate and omits the "optional" nature of the amount and the instruction to "not request a specific amount."

Correct translation:
So‘raladigan ixtiyoriy miqdor. Aniq bir miqdorni so‘ramaslik uchun buni bo‘sh yoki nol qoldiring.
```

<!-- cache_translation_check_uz@Latn_fa8dcf46e73efd34860d56026abcbad60c4fb6e08301cfbe63fae53676b7b0b2 -->
```
        <source>Copy &amp;Address</source>
        <translation>Нусҳалаш &amp; Манзил</translation>
    
ERR
The translation uses Cyrillic script (Нусҳалаш &amp; Манзил) but the requested language variant is uz@Latn (Latin script). Also there is an extra space after the ampersand. The ampersand must appear exactly once and the string should be in Latin.

Correct translation (Latin-script, single & and no stray space):
&Manzilni nusxalash
```

<!-- cache_translation_check_uz@Latn_4d438591a26c7b83ac63cb4bb1032c7fceb3a75e9bab0879e7eece58ad0a426f -->
```
        <source>Request payment to %1</source>
        <translation> %1 дан Тўловни сўраш</translation>
    
ERR
There is a whitespace issue: an extra space at the beginning of the translation sentence, and also inconsistent usage of the apostrophe (should use proper Latin 'o' and 'o‘' where needed). Also, "Тўловни" uses Cyrillic script, while 'uz@Latn' must be Latin. Additionally, 'dan' means 'from,' whereas "to %1" should be rendered as "ga" or "uchun" ("for").

Correct translation:
%1 uchun to‘lov so‘rash
```

<!-- cache_translation_check_uz@Latn_ca518a41786a4513c1f6f38345406a509dbc8bbe80e84fa2f5997d8e979f74ee -->
```
        <source>Send Coins</source>
        <translation>Тангаларни жунат</translation>
    
ERR
The translation is written in Cyrillic script, whereas 'uz@Latn' specifies Uzbek in Latin script. Additionally, the word "ju'nat" should be "yuborish" or "yuboring" depending on context.

Correct translation:
Tangalarni yuborish
```

<!-- cache_translation_check_uz@Latn_b2b33d8d8fe78b0d3b275c304b4d314449b62091d2bc0e75ab23274d19696e45 -->
```
        <source>Insufficient funds!</source>
        <translation>Кам миқдор</translation>
    
ERR
The translation "Кам миқдор" is in Cyrillic script, whereas 'uz@Latn' requires Latin script. Additionally, the phrase is incomplete and does not fully convey "Insufficient funds!" (which means "Not enough money!" or "Yetarli mablag' yo'q!").

Correct translation:
Yetarli mablag' yo'q!
```

<!-- cache_translation_check_uz@Latn_da2daa234d8737d92841fc921fed26eb284448fd4abb5e2144d90262eb6a594d -->
```
        <source>If this is activated, but the change address is empty or invalid, change will be sent to a newly generated address.</source>
        <translation>Агар бу фаоллаштирилса, аммо ўзгартирилган манзил бўл ёки нотўғри бўлса, ўзгариш янги яратилган манзилга жўнатилади.</translation>
    
ERR
The translation is in Cyrillic script, but the requested language is 'uz@Latn' (Uzbek in Latin script). Also, "ўзгартирилган манзил" more literally means 'the changed address,' which is a bit off. "Change" in Bitcoin should be translated as "qaytim" or "o'zgarish" (less common for the Bitcoin term).

Correct translation:
Agar bu yoqilgan bo‘lsa, lekin qaytim manzili bo‘sh yoki noto‘g‘ri bo‘lsa, qaytim yangi yaratilgan manzilga yuboriladi.
```

<!-- cache_translation_check_uz@Latn_69cfe6ac949fe030edf56b124b5263d0a68c3ff17ca4d1bf842900766bb5d8bc -->
```
        <source>Custom change address</source>
        <translation>Бошқа ўзгартирилган манзил</translation>
    
ERR
The translation is problematic. The provided 'uz@Latn' translation uses Cyrillic script and is also inaccurate. 'uz@Latn' requires the Latin script, and the meaning should be closer to "Maxsus qaytim manzili" (i.e., a custom Bitcoin change address).

Correct translation:
Maxsus qaytim manzili
```

<!-- cache_translation_check_uz@Latn_c9c405f742329d23cd36353988ba6f0056a8c05b80d589193539dd5af647be8f -->
```
        <source>per kilobyte</source>
        <translation>Хар килобайтига</translation>
    
ERR
The translation is in Cyrillic script ('uz' in Cyrillic), but the target is 'uz@Latn' (Uzbek Latin script). Also, the letter capitalization is not consistent with typical usage.

Correct translation:
har kilobaytiga
```

<!-- cache_translation_check_uz@Latn_ea13dc9434a8577a7d395c09faf8822edacc4e9b73818e40bed115b23c233d20 -->
```
        <source>Clear &amp;All</source>
        <translation>Барчасини &amp; Тозалаш</translation>
    
ERR
The translation is in Cyrillic script (Узбек in Cyrillic) instead of the requested Uzbek Latin (uz@Latn). It also uses an HTML entity (&amp;) and includes an extra space around the ampersand. The source has a single & before "All" to mark the shortcut; the translation must include exactly one & (not &amp;) and avoid stray spaces.

Correct translation (Uzbek Latin, single & used, no extra spaces):
Barchasini &tozalash
```

<!-- cache_translation_check_uz@Latn_1394ff5c5959afc03ffa13e87ee0b92607bacbce20ce1bcfa6a9028d9dcf263c -->
```
        <source>S&amp;end</source>
        <translation>Жў&amp;натиш</translation>
    
ERR
The translation uses Cyrillic script ("Жўнатиш") but the requested locale 'uz@Latn' requires Uzbek in Latin script. The ampersand is present exactly once (good), and there are no percent/placeholders to worry about.

Correct translation in Uzbek (Latin):
<translation>J&amp;o'natish</translation>
```

<!-- cache_translation_check_uz@Latn_89e6e1727df638f168b9629de72e639d99b59a48691e81240d038937d608cb97 -->
```
        <source>Copy change</source>
        <translation>Нусха қайтими</translation>
    
ERR
The translation is in Uzbek Cyrillic ("Нусха қайтими") but the target requested is Uzbek in Latin script (uz@Latn). Also the phrasing is slightly awkward. A better Uzbek (Latin) translation:

Suggested translations:
- "Qaytimni nusxalash" 
- or more explicitly: "Qaytimni nusxa olish"

Use one of these depending on UI style (imperative/verb form).
```

<!-- cache_translation_check_uz@Latn_7a8bf72086d351ef96eddb02dd6680d0b86fc658732a8b14a2237fc53809635f -->
```
        <source>The amount to pay must be larger than 0.</source>
        <translation>Тўлов миқдори 0. дан катта бўлиши керак. </translation>
    
ERR
The translation is written in Cyrillic script, but 'uz@Latn' specifies the Latin script for Uzbek. Additionally, there is an extra space at the end.

Correct translation:
To'lov miqdori 0 dan katta bo'lishi kerak.
```

<!-- cache_translation_check_uz@Latn_35fdbfdac7d4dbc8538bdb52e5ce59e95ac65fc61f99e8ffda78c248ba791af1 -->
```
        <source>A&amp;mount:</source>
        <translation>&amp;Миқдори:</translation>
    
ERR
The translation uses Cyrillic letters ("Миқдори:") but the requested language/variant is uz@Latn (Uzbek in Latin script). The ampersand shortcut exists exactly once, which is fine, and there are no whitespace or format-specifier issues.

Correct translation (Latin script):
&Miqdori:
```

<!-- cache_translation_check_uz@Latn_3c0cf66b402c70b23a2585289ee79d829ac396f1f38f36472c7267c19722396e -->
```
        <source>Pay &amp;To:</source>
        <translation>&amp;Тўлов олувчи:</translation>
    
ERR
The translation is in Uzbek Cyrillic (Тўлов олувчи) but the target locale 'uz@Latn' requires Uzbek in Latin script. Also ensure the shortcut ampersand appears exactly once.

Correct translation (Uzbek, Latin script):
&amp;To'lov oluvchi:
```

<!-- cache_translation_check_uz@Latn_ede49ca0b9b5ea4b6fa98f9961c06bc578b1a73c6462123462ad9a9eb4a86293 -->
```
        <source>&amp;Label:</source>
        <translation>&amp;Ёрлиқ:</translation>
    
ERR
The translation uses Cyrillic script ("&amp;Ёрлиқ:") but the target language tag is uz@Latn (Uzbek in Latin script). Use the Latin-script Uzbek word.

Correct translation:
&amp;Yorliq:
```

<!-- cache_translation_check_uz@Latn_2fd748ca8d39279c301e627721bdd8fdfecefdc8445502ec3e144320869a8d98 -->
```
        <source>Paste address from clipboard</source>
        <translation>Manzilni qo'shib qo'yish</translation>
    
ERR
The translation "Manzilni qo'shib qo'yish" means "to add the address" rather than "Paste address from clipboard". It does not convey the action of pasting from the clipboard.

Correct translation:
Manzilni xotira (buf) dan qo'yish
or
Manzilni buferdan qo'yish
```

<!-- cache_translation_check_uz@Latn_2fd748ca8d39279c301e627721bdd8fdfecefdc8445502ec3e144320869a8d98 -->
```
        <source>Paste address from clipboard</source>
        <translation>Manzilni qo'shib qo'yish</translation>
    
ERR
The translation "Manzilni qo'shib qo'yish" means "to add the address" rather than "Paste address from clipboard". It does not convey the action of pasting from the clipboard.

Correct translation:
Manzilni xotira (buf) dan qo'yish
or
Manzilni buferdan qo'yish
```

<!-- cache_translation_check_uz@Latn_ea13dc9434a8577a7d395c09faf8822edacc4e9b73818e40bed115b23c233d20 -->
```
        <source>Clear &amp;All</source>
        <translation>Барчасини &amp; Тозалаш</translation>
    
ERR
The translation is in Cyrillic script (Узбек in Cyrillic) instead of the requested Uzbek Latin (uz@Latn). It also uses an HTML entity (&amp;) and includes an extra space around the ampersand. The source has a single & before "All" to mark the shortcut; the translation must include exactly one & (not &amp;) and avoid stray spaces.

Correct translation (Uzbek Latin, single & used, no extra spaces):
Barchasini &tozalash
```

<!-- cache_translation_check_uz@Latn_194c94993cf4689bc46afcffa02c75c79423e109cb88dfa1918b2fe575eee48b -->
```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/тасдиқланмади</translation>
    
ERR
The translation '%1/тасдиқланмади' uses Cyrillic script ('тасдиқланмади') instead of the requested Latin script for 'uz@Latn'. Also, the translation for "unconfirmed" in Uzbek Latin script is "tasdiqlanmagan". 

Correct translation:
%1/tasdiqlanmagan
```

<!-- cache_translation_check_uz@Latn_4ba8deff5d5a15b470a633ad46be786fa715e6388f05538a64a2764ac409c161 -->
```
        <source>From</source>
        <translation>Дан</translation>
    
ERR
The translation "Дан" is in Cyrillic script, whereas 'uz@Latn' requires the Latin script for Uzbek. The correct Latin script translation for "From" is "Kimdan" or "Dan" (depending on context, but "Kimdan" is safer for clarity).

Correct translation:
Kimdan
```

<!-- cache_translation_check_uz@Latn_23495be8d19e28cfb68935ae81b9e2804fa148083905fb0e2214871ca88a1c55 -->
```
        <source>To</source>
        <translation>Га</translation>
    
ERR
The translation uses Cyrillic script ("Га"), but the 'uz@Latn' language code specifies the use of Latin script only. The translation should be in Uzbek Latin script.

Correct translation:
To = "Ga"
So, the correct translation in Latin script is:
Ga
```

<!-- cache_translation_check_uz@Latn_5e960163237dc10bd984c894a4f22df23f0d6e7ab6df8a503169c9782f5e9dc0 -->
```
        <source>Credit</source>
        <translation>Кредит (қарз)</translation>
    
ERR
The translation is in Cyrillic script (Кредит (қарз)), while 'uz@Latn' specifies the Latin script for Uzbek. Also, the word "Credit" as used in financial/transactional contexts in Bitcoin is better translated as "Kredit" (or possibly "Kredit (qarz)", though "qarz" means debt/loan and may not be equivalent). 

Correct translation:
Kredit
```

<!-- cache_translation_check_uz@Latn_9a3c0ff1dc6794af6213895b3b7e802f474319ed0638fccf5f616724b4e0e900 -->
```
        <source>not accepted</source>
        <translation>қабул қилинмади</translation>
    
ERR
The translation uses Cyrillic script (қабул қилинмади) instead of Latin script as required by 'uz@Latn'. The content itself is accurate, but the script must be Latin.

Correct translation:
qabul qilinmadi
```

<!-- cache_translation_check_uz@Latn_6736ed11c8e393e1f0d67e5b0ca2360504ffc7ee46276255c5f3faf47810655e -->
```
        <source>Transaction ID</source>
        <translation>ID</translation>
    
ERR
The translation is incomplete. "Transaction ID" should be fully translated to Uzbek in Latin script. Only "ID" is not enough and omits the key term "transaction".

Correct translation:
Tranzaksiya identifikatori
```

<!-- cache_translation_check_uz@Latn_f9dfcdbd22f00db9d069bf8864bec4df503098b7fc6c32038403296987917818 -->
```
        <source>Merchant</source>
        <translation>Савдо</translation>
    
ERR
The translation "Савдо" is written in Cyrillic, but 'uz@Latn' requires the Latin script. Additionally, "Savdo" means "trade" or "commerce" in Uzbek, while "merchant" is better translated as "Savdogar" (a person who is a trader or merchant).

Correct translation:
Savdogar
```

<!-- cache_translation_check_uz@Latn_6cdc4967baaf4f2ceb59370bf2a92f7f257bf568c9e105d320fc624789d13a62 -->
```
        <source>true</source>
        <translation>рост</translation>
    
SPAM
The translation 'рост' is in Cyrillic script, and is the Russian word for "growth", not the correct transliteration or translation for "true". The correct 'uz@Latn' translation (Uzbek in Latin script) would be "rost" or "to'g'ri".

Correct translation:
rost
```

<!-- cache_translation_check_uz@Latn_c8af3aebaa375a68e77062241bd0a0e438c3a705d904714ea83cc15aaa0d3a57 -->
```
        <source>Confirmed (%1 confirmations)</source>
        <translation>Тасдиқланди (%1 та тасдиқ)</translation>
    
ERR
The translation is in Cyrillic script ("Тасдиқланди (%1 та тасдиқ)"), but 'uz@Latn' requires the Latin script for Uzbek. Additionally, for more natural Uzbek, "та тасдиқ" could more accurately be "ta tasdiq" or "ta tasdiqlash", but "tasdiq" is acceptable in meaning.

Correct translation:
Tasdiqlandi (%1 ta tasdiq)
```

<!-- cache_translation_check_uz@Latn_220ad3b5b35cc67f7264dd800ad6f48a3f1b3d2bee30f5a8e38bedc26f9ff137 -->
```
        <source>Received from</source>
        <translation>Дан қабул қилиш</translation>
    
ERR
The translation is incorrect and in the wrong script. The text "Дан қабул қилиш" is in Cyrillic script, not Latin ('uz@Latn'). Additionally, it means "Receive from" but with awkward phrasing.

Correct translation:
Qabul qilindi kimdan
```

<!-- cache_translation_check_uz@Latn_6d71982060e7b380b3e784bbf9bd45229f16d9f1b8524cf8d3864d410b038b76 -->
```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
ERR
The translation is problematic. The original English "Sent to" means that something has been sent to a specific address or recipient. The provided translation "Жўнатиш" is in Cyrillic script and means "Send" (the verb, not the phrase), not "Sent to". Additionally, the translation should be in Latin script as specified by 'uz@Latn'.

Correct translation:
Yuborildi (ga)
```

<!-- cache_translation_check_uz@Latn_12ff85ecf961641f2a58858a345acd5ac1338f0f8ed3b417d3213f908c601ebb -->
```
        <source>Mined</source>
        <translation>Фойда</translation>
    
ERR
The translation "Фойда" means "profit" in Uzbek written in Cyrillic, whereas "Mined" refers to coins that have been obtained through mining. The correct translation should be in Latin script as specified by 'uz@Latn', and more accurately represent the term "mined".

Correct translation:
Qazib olingan
```

<!-- cache_translation_check_uz@Latn_f5a4b93d6d535b43191c7da1b1db4d42de84229c834e931158d58353e12ba1b6 -->
```
        <source>This month</source>
        <translation>Шу ой</translation>
    
ERR
The translation "Шу ой" is in Cyrillic script, but 'uz@Latn' requires the Latin script. Correct translation in Uzbek Latin script should be:

Bu oy
```

<!-- cache_translation_check_uz@Latn_8fa63031947fc50136b2540c73602ef8ea9fc2801ca8c4d8b29b9207c5677172 -->
```
        <source>Last month</source>
        <translation>Ўтган хафта</translation>
    
ERR
The translation is incorrect. "Ўтган хафта" means "last week" in Uzbek, not "last month".

Correct translation:
O‘tgan oy
```

<!-- cache_translation_check_uz@Latn_6d71982060e7b380b3e784bbf9bd45229f16d9f1b8524cf8d3864d410b038b76 -->
```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
ERR
The translation is problematic. The original English "Sent to" means that something has been sent to a specific address or recipient. The provided translation "Жўнатиш" is in Cyrillic script and means "Send" (the verb, not the phrase), not "Sent to". Additionally, the translation should be in Latin script as specified by 'uz@Latn'.

Correct translation:
Yuborildi (ga)
```

<!-- cache_translation_check_uz@Latn_12ff85ecf961641f2a58858a345acd5ac1338f0f8ed3b417d3213f908c601ebb -->
```
        <source>Mined</source>
        <translation>Фойда</translation>
    
ERR
The translation "Фойда" means "profit" in Uzbek written in Cyrillic, whereas "Mined" refers to coins that have been obtained through mining. The correct translation should be in Latin script as specified by 'uz@Latn', and more accurately represent the term "mined".

Correct translation:
Qazib olingan
```

<!-- cache_translation_check_uz@Latn_f6a46ce6228858e12a8cee782e150387b2f39d9e0e57dfdefe9d10d344daa632 -->
```
        <source>Min amount</source>
        <translation>Мин қиймат</translation>
    
ERR
The translation is mostly correct, but it uses Cyrillic script (Мин қиймат) instead of the Latin script as required for 'uz@Latn'. It should be in Uzbek Latin.

Correct translation:
Eng kam qiymat
```

<!-- cache_translation_check_uz@Latn_7f160f986a5e4c48ba9159556dd231e8aa041a54e214fec58505a8d54e4c7311 -->
```
        <source>to</source>
        <translation>Кимга</translation>
    
ERR
The translation "Кимга" is in Cyrillic script, not Latin ('uz@Latn' demands the Latin script). Furthermore, "Кимга" means "to whom", which is more specific than the preposition "to".

Correct translation:
ga

So, the translation should be just "ga", or, if more context is needed, "Kimga" (in Latin script). However, for the preposition "to", simply "ga" is most accurate.
```

<!-- cache_translation_check_uz@Latn_ca518a41786a4513c1f6f38345406a509dbc8bbe80e84fa2f5997d8e979f74ee -->
```
        <source>Send Coins</source>
        <translation>Тангаларни жунат</translation>
    
ERR
The translation is written in Cyrillic script, whereas 'uz@Latn' specifies Uzbek in Latin script. Additionally, the word "ju'nat" should be "yuborish" or "yuboring" depending on context.

Correct translation:
Tangalarni yuborish
```

<!-- cache_translation_check_uz@Latn_a31be81d7a73b6a6dad1e3996de7c87a2aa6c030d0257785ee36b852b097aeaf -->
```
        <source>Insufficient funds</source>
        <translation>Кам миқдор</translation>
    
ERR
The translation is in Cyrillic script (Кам миқдор), whereas 'uz@Latn' specifies the use of Latin script. Additionally, the phrase more literally means 'small amount' rather than 'Insufficient funds', which would be better translated as "Yetarli mablag‘ yo‘q" or "Mablag‘ yetarli emas".

Correct translation:
Yetarli mablag‘ yo‘q
```

<!-- cache_translation_check_uz@Latn_daa959aa0f45a3f88ff738abe10efdc116429f327b9ec6b446d3845696655ac3 -->
```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Hamyonni qayta yozish kerak: bajarish uchun 1%s ni qayta ishga tushiring</translation>
    
ERR
The translation introduces an error with "1%s" instead of the correct format specifier "%s". This could cause display or runtime issues. The rest of the translation is otherwise correct, but the format specifier must be copied exactly.

Correct translation:
Hamyonni qayta yozish kerak: bajarilishini yakunlash uchun %s ni qayta ishga tushiring
```
</details>

Number of issues: 144.
