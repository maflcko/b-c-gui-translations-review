# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>uz</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Buz%5D%20request)


<!-- cache_translation_check_uz_d4b49b220f1f388b03d449a60b03a715301c61719864932de15bb489ddb0509c -->
```
        <source>&amp;Delete</source>
        <translation>o'chirish</translation>
    
ERR
The translation is missing the required shortcut ampersand (&) and should include it exactly once. Also UI labels are typically capitalized.

Correct translation:
<translation>&O'chirish</translation>
```

<!-- cache_translation_check_uz_f815a9e95209023dd70d851d95a253979c87f2a3f609920f3807ab3f7dcbe2d3 -->
```
        <source>C&amp;hoose</source>
        <translation>tanlamoq</translation>
    
ERR
Problems:
- The translation "tanlamoq" is the infinitive verb (to choose) and not an appropriate concise UI label. It should be a short imperative/command like "Tanla".
- The source contains a single ampersand (&) indicating a keyboard shortcut; the translation must include exactly one &. The provided translation has none.

Suggested correct translation (includes one & and a suitable label):
T&anla
```

<!-- cache_translation_check_uz_e62cbc55bdef0a7c569fec5a182fcb42dcc92f4cc83818761190dfa43b407589 -->
```
        <source>Copy &amp;Label</source>
        <translation>Nusxalash &amp;Yorliq</translation>
    
ERR
The translation "Nusxalash &Yorliq" is understandable but has awkward word order for Uzbek UI text. The original is "Copy &Label" (verb+object); a more natural Uzbek phrasing is "Yorliqni nusxalash" with the shortcut marker placed once. Correct translation (with shortcut on "Yorliq"):

&Yorliqni nusxalash
```

<!-- cache_translation_check_uz_4f0bf1845ad95484d25c82d6b8f7c1d7746143e21bfc5d6f900f96a7855446e6 -->
```
        <source>&amp;Edit</source>
        <translation>O'zgartirmoq</translation>
    
ERR
Problems:
- The translation "O'zgartirmoq" is the infinitive verb "to edit" and is not the usual UI label for "Edit".
- The source contains a single '&' indicating a keyboard shortcut; the translation is missing the '&' and must include it exactly once.

Suggested correction (include & for the shortcut):
&amp;O'zgartirish
```

<!-- cache_translation_check_uz_c28ef394ad6044621a41c9b41fbe2ba981368c89c0b4a61ee1d9d5e52d6a1c76 -->
```
        <source>Sending addresses - %1</source>
        <translation>Manzillarni yuborish%1</translation>
    
ERR
The translation removes the separator and the required space before %1 ("Manzillarni yuborish%1") and the phrasing is slightly unnatural. The format specifier %1 must be kept with proper spacing/punctuation.

Suggested correction:
Yuborish manzillari - %1
```

<!-- cache_translation_check_uz_88f1e80173e21e83830081e31c5e0c2b9fd28ef191582b67fa793832204ba7e4 -->
```
        <source>Receiving addresses - %1</source>
        <translation>Qabul qilish manzillari-%1</translation>
    
ERR
The translation incorrectly omits spaces around the dash and the phrasing can be made more natural in Uzbek. Also ensure the %1 specifier is preserved with proper spacing.

Suggested correction:
Qabul qiluvchi manzillar - %1
```

<!-- cache_translation_check_uz_73062f30966c6156c0858b5b56081c4c11a42eb4e97e4268b5f169f6a61786be -->
```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Hamyon shifrini ochish uchun parol iborasi noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas). Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating.
</translation>
    
ERR
The translation has several issues:
- "qurilmalar bilan" should be "belgilar bilan" to denote "characters".
- "lekin shu narsa emas" is awkward; it should be "lekin birinchi null belgini o'z ichiga olmaydi".
- "Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating." is awkward and unclear; it should be "Agar bu muvaffaqiyatli bo'lsa, kelajakda bu muammo yuzaga kelmasligi uchun yangi parol iborasini o'rnating."

Correct translation:
Hamyonni shifrdan yechish uchun kiritilgan parol iborasi noto'g'ri. U null belgini (ya'ni - nol bayt) o'z ichiga oladi. Agar parol iborasi ushbu dasturning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan belgilar bilan urinib ko'ring (lekin birinchi null belgini o'z ichiga olmaydi). Agar bu muvaffaqiyatli bo'lsa, kelajakda bu muammo yuzaga kelmasligi uchun yangi parol iborasini o'rnating.
```

<!-- cache_translation_check_uz_2918ff4aee68e2055c1a85af021e51d3926cf0fb029abde3c5db3a4dd5066751 -->
```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Hamyon shifrini ochish uchun yordam eski parol noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas).</translation>
    
ERR
The Uzbek translation is somewhat inaccurate and partially unclear. Specifically:
- "yordam" means "help" and should not be there in "yordam eski parol noto'g'ri".
- "qurilmalar" means "devices", which is incorrect. It should refer to the "characters" up to but not including the first null character.
- The part in parentheses is not rendered as clearly as in the original and slightly changes the meaning.
- The final part "(lekin shu narsa emas)" is awkward and does not clearly translate "but not including".

Correct translation:
Hamyonni shifrdan chiqarish uchun kiritilgan eski parol noto'g'ri. U null belgisini (ya'ni, nol bayt) o'z ichiga oladi. Agar parol iborasi ushbu dasturiy ta'minotning 25.0 versiyasidan oldingi versiyalarda o'rnatilgan bo'lsa, iltimos, birinchi null belgigacha bo‘lgan belgilar bilan (lekin null belgini o‘ziga kiritmasdan) yana urinib ko‘ring.
```

<!-- cache_translation_check_uz_5cc120eff65239f3f03c07ebe850f7e2dc20d4d270ac1981b6bb6bfc0e5f8315 -->
```
        <source>Banned Until</source>
        <translation>gacha kirish taqiqlanadi</translation>
    
ERR
The translation reverses the meaning; it says "Access is banned until" instead of specifying the actual 'until' time.

Correct translation:
Taqiqlangan vaqti (yoki: Qachongacha taqiqlangan)
```

<!-- cache_translation_check_uz_7dc940b4b5f60571ec1dd5d98804adb937eb9c7fc66351de2e17ddc77644f8d6 -->
```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>Fatal xatolik yuz berdi. %1 xavfsiz ravishda davom eta olmaydi va tizimni tark etadi. </translation>
    
ERR
The translation contains minor issues:
1. "tizimni tark etadi" literally means "will leave the system", which is less natural and not an accurate reflection of "will quit" (meaning the application will exit/close).
2. There is an extra space at the end of the translation.
3. "Fatal xatolik" is a calque; "Jiddiy xatolik" or "Halokatli xatolik" is more idiomatic, but "Fatal xatolik" is also sometimes used in technical language.

Correct translation:
Jiddiy xatolik yuz berdi. %1 endi xavfsiz davom eta olmaydi va yopiladi.
```

<!-- cache_translation_check_uz_fe5b13e10a3c6716704c9f42ceed83e808b30e9db968dc3e856ff7d2ace06b7a -->
```
        <source>%1 m</source>
        <translation>%1 д</translation>
    
ERR
The translation is problematic because '%1 m' in the source refers to 'meters' (with 'm' as the abbreviation for meter in English), but the translation '%1 д' uses 'д', which is not the Uzbek abbreviation for meters.

The correct Uzbek abbreviation for 'meter' is 'm', same as in English. The translation should retain '%1 m'.

Correct translation:
%1 m
```

<!-- cache_translation_check_uz_0aa3a34bc3751b0feeba39deb0736f33d9d2078e277c8189e652102493356917 -->
```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Паролни ўзгартириш ҳамённи кодлашда фойдаланилади</translation>
    
ERR
The Uzbek translation is not accurate and is a bit confusing. The source means "Change the passphrase that is used for wallet encryption," but the Uzbek text reads as "Changing the password is used for wallet encryption," which is incorrect.

Correct translation:
Ҳамённи шифрлаш учун фойдаланиладиган паролни ўзгартириш
```

<!-- cache_translation_check_uz_089ddbd9180f7f228b2267c44e0c5eb58a08453e6252a1f83d67b18c444e9025 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>&amp;Hamyon nusxasi...</translation>
    
ERR
The translation "&Hamyon nusxasi..." literally reads "wallet copy..." and is not a proper imperative/label for the action "Backup Wallet…". Also the source uses a single-character ellipsis (…), while the translation uses three dots; not critical but better to match style.

Correct translations (keep the & for the shortcut exactly once):
&Hamyonni zaxiralash…
or
&Hamyonni zaxira qilish…
```

<!-- cache_translation_check_uz_dbdc3990c2b1b8fa8dde4337dea36a096b374374a8d34f7ceb7b9a0616c2f53a -->
```
        <source>Sign &amp;message…</source>
        <translation>Xabarni &amp;signlash...</translation>
    
ERR
The translation mixes English ("signlash") with Uzbek and uses three ASCII dots instead of an ellipsis character. Use the Uzbek verb "imzolash" for "sign" and keep the & shortcut exactly once. Correct translation:

<translation>Xabarni &imzolash…</translation>
```

<!-- cache_translation_check_uz_d01bffcf29fdf70c77c2e73c5905f697296116ab8eb11d0255e392208374e5b5 -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>&amp;PSBT ni fayldan yuklash...</translation>
    
ERR
The Uzbek suffix "-ni" is incorrectly separated by a space ("PSBT ni"); in Uzbek it should attach directly ("PSBTni"). Also prefer using the same ellipsis character. Correct translation:

&PSBTni fayldan yuklash…
```

<!-- cache_translation_check_uz_eea3ab9fd2ad9e14d92bd212c29b0e879403a0b4ae9ebfb04152e8787f3fef09 -->
```
        <source>Open &amp;URI…</source>
        <translation>&amp;URL manzilni ochish</translation>
    
ERR
Problems:
- The source uses "URI" but the translation changed it to "URL" — should keep the same term "URI".
- The source includes an ellipsis (…) which is missing in the translation.
- Minor Uzbek phrasing: use "manzilni" as the accusative of "manzil".

Correct translation:
&URI manzilni ochish…
```

<!-- cache_translation_check_uz_13ad48aca877381998ab5a421b6e9f1b91ce91eb035e7e54d744123a188aa791 -->
```
        <source>&amp;File</source>
        <translation>&amp;Файл</translation>
    
ERR
The translation uses the Cyrillic Russian word "Файл" rather than Uzbek. Uzbek (uz) should use the Uzbek word in Latin script (official) — "Fayl". The ampersand (&) is present and placed correctly.

Correct translation:
&amp;Fayl
```

<!-- cache_translation_check_uz_ea7ee41489272cd603ea929b3b857c5998073c18ca99fc68b21a93da0a7dce18 -->
```
        <source>&amp;Settings</source>
        <translation>&amp; Созламалар</translation>
    
ERR
Problems:
- There's an extra space after the ampersand entity ("&amp; Созламалар"). The accelerator marker should be adjacent to the label (no stray leading space).
- Additionally, Uzbek typically uses the Latin script; using Cyrillic ("Созламалар") may be unexpected for 'uz' locale. Prefer the Latin form.

Correct translations (choose one depending on script preference):
- Latin script: &amp;Sozlamalar
- Cyrillic script (if deliberately using Cyrillic): &amp;Созламалар
```

<!-- cache_translation_check_uz_7c293b039b3b3e7b0789ae952347b995b48c8ae2f311630ec31b6d11ce3e50db -->
```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>To'lovlarni so'rash(QR kolar va bitkoin yaratish: URL manzillar)</translation>
    
ERR
There are several issues:
1. "kolar" is a typo, should be "kodlar".
2. The parentheses are not spaced as in the source: a space should be before the parenthesis.
3. "bitcoin: URIs" should be "bitcoin: URI larini" or at least reflect that "bitcoin: URIs" is a technical term.
4. The translation for "Request payments" could be improved to "To'lovlarni so'rash" (which is fine), but the rest is not precise.

Correct translation:
To'lovlarni so'rash (QR kodlar va bitcoin: URI larini yaratadi)
```

<!-- cache_translation_check_uz_1991927842119249addbe4ffb62b8fd709004e24adb55bc96ff72d514a22c28c -->
```
        <source>&amp;Command-line options</source>
        <translation>&amp;Command-line sozlamalari</translation>
    
ERR
The translation mixes English and Uzbek ("Command-line" left in English). The ampersand is used correctly and there are no format specifiers or whitespace issues, but the phrase should be fully in Uzbek.

Suggested correction:
&Buyruq satri sozlamalari
```

<!-- cache_translation_check_uz_ae0b96cf49348fdc55f9a198a3ff27e4c811f3ff042a7e5043772cd909d0711f -->
```
        <source>Ctrl+Q</source>
        <translation>formatini olib tashlash(Ctrl+Q)</translation>
    
ERR
The translation is inaccurate. "Ctrl+Q" is a keyboard shortcut and should be left untranslated or, if explained, should reflect its function, which is typically "exit" or "quit" in many applications. The provided translation means "remove format (Ctrl+Q)", which is incorrect and adds unintended meaning.

Correct translation:
Ctrl+Q
```

<!-- cache_translation_check_uz_034a3b663750f19d590686c6a884c3c69eae99168fa588dd85945f57fb09a532 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>&amp;Nusxalanganlar dan PSBT ni yuklash</translation>
    
ERR
Issues:
- Word choice/grammar: "Nusxalanganlar dan" is incorrect Uzbek. It should be "nusxadan" (from clipboard) rather than the plural "nusxalanganlar dan".
- Spacing: there should not be a space between the stem and the postposition in "nusxadan" (no separate "dan").
- Ellipsis: the source ends with an ellipsis (…) which is missing in the translation.
- Shortcut ampersand: the & exists once in the translation (good), but it should be placed before the correct word.

Correct translation suggestion:
<translation>PSBT ni &nusxadan yuklash…</translation>
```

<!-- cache_translation_check_uz_297cc566c94a50d56fa5ef52884509c7ed463e913844f62c5f2c49269e2d1ff3 -->
```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
ERR
The translation is highly erroneous and completely unrelated. "dudlangan cho'chqa go'shti koʻchirish" translates as "smoked pork transfer," which has nothing to do with "Migrate Wallet." 

Correct translation:
Hamyonni ko‘chirish
```

<!-- cache_translation_check_uz_3a6d7eb6a8ac2c5db3c0576f1178460568316bfa9d1a0d6ed5af39348462042d -->
```
        <source>Ctrl+M</source>
        <translation>Abzatsga chek qo'ying.(Ctrl+M)</translation>
    
ERR
The translation is incorrect. "Ctrl+M" is a keyboard shortcut and should usually remain unchanged or simply be transliterated. The current translation, "Abzatsga chek qo'ying.(Ctrl+M)", means "Add a tick to the paragraph. (Ctrl+M)" which is erroneous and adds unwanted instruction.

Correct translation:
Ctrl+M
```

<!-- cache_translation_check_uz_7d512b598b1ed9bdf8d5c5f6467f2867f2265c06b7de842f2f526e3ba35cec6a -->
```
        <source>Click for more actions.</source>
        <extracomment>A substring of the tooltip. "More actions" are available via the context menu.</extracomment>
        <translation>Ko'proq sozlamalar uchun bosing.</translation>
    
ERR
The translation "Ko'proq sozlamalar uchun bosing." translates as "Click for more settings." The English word "actions" is better translated as "harakatlar" or "amallar" in this context, not "sozlamalar" (which means "settings"). "Sozlamalar" changes the meaning.

Correct translation:
Ko'proq harakatlar uchun bosing.
```

<!-- cache_translation_check_uz_dac0647848b90704e4df6dacc855e8a92d7cdbeb9f4311a5117ccd090c5fdcf4 -->
```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini cheklash</translation>
    
ERR
The translation of "Disable network activity" as "Ijtimoiy tarmoq faoliyatini cheklash" is inaccurate. "Ijtimoiy tarmoq" means "social network", which is not the same as "network" in the context of Bitcoin (which refers generally to the computer/data network).

A correct translation would be:
Tarmoq faoliyatini o‘chirish
```

<!-- cache_translation_check_uz_9ebea8d02c4cdc38ebc78557edf4a5362306747a6e739e41e31ba410b24b595e -->
```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini yoqish</translation>
    
ERR
The translation "Ijtimoiy tarmoq faoliyatini yoqish" translates to "Enable social network activity," which is incorrect. "Network activity" in the context of Bitcoin refers to general network (internet) connectivity, not social networks.

Correct translation:
Tarmoq faoliyatini yoqish
```

<!-- cache_translation_check_uz_0b2c6f1d6655f19c9050749b99ad56bcf72d66a0b07574eecae1257320be6c85 -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>Tranzaksiya &amp;IDsi ni va chiquvchi indeksni nusxalash</translation>
    
ERR
The translation has incorrect spacing and a small grammatical issue: the possessive + accusative suffix for "ID" should be attached without a space ("IDsini" not "IDsi ni"). Also "chiquvchi indeksni" is acceptable but "chiqish indeksini" reads more naturally.

Correct translation:
Tranzaksiya &IDsini va chiqish indeksini nusxalash
```

<!-- cache_translation_check_uz_b091013308c7c571bca7fb23b1c008bf87eae9c6f0dc0d2fd62fc8cf2c650b42 -->
```
        <source>&amp;Unlock unspent</source>
        <translation>Sarflanmaqan tranzaksiyalarni &amp;qulfdan chiqarish</translation>
    
ERR
Uzbek has a small spelling error: "Sarflanmaqan" should be "Sarflanmagan". The ampersand (&) is present exactly once (good). No format specifiers or whitespace issues.

Correct translation:
Sarflanmagan tranzaksiyalarni &qulfdan chiqarish
```

<!-- cache_translation_check_uz_5ecb47d9f9e90bed2dcafc92afe94bc082df53f30b0a74c6c36f9c0e22a8c497 -->
```
        <source>Copy after fee</source>
        <translation>'To'lovdan keyin' ni nusxalash</translation>
    
ERR
The translation has incorrect punctuation and spacing (unnecessary single quotes and a space before the postposition "ni"), and the phrasing is awkward. There are no format specifiers to preserve.

Correct translation:
To'lovdan keyingisini nusxalash

(Alternative more explicit: "To'lovdan keyingi qiymatni nusxalash")
```

<!-- cache_translation_check_uz_b79753252a76edb9988270135bb0acf0077e8cfaabf0665750d5f6631eddd0ca -->
```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>Hamyonni ko'chirmoqchi ekanligingizga ishonchingiz komilmi?&lt;i&gt;%1&lt;/i&gt;</translation>
    
ERR
The wallet name placeholder %1 and the italic tags were moved out of the phrase and placed after the question mark; they must remain where the wallet is referenced. Also ensure spacing around the tag is correct.

Correct translation:
Hamyon &lt;i&gt;%1&lt;/i&gt;ni ko'chirmoqchi ekanligingizga ishonchingiz komilmi?
```

<!-- cache_translation_check_uz_429a3b3af4edad58132fca4b091e3d82f803e64f7380316e19343291b73c79c6 -->
```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>Hamyonni ko'chirish ushbu hamyonni bir yoki bir nechta deskriptor hamyonga aylantiradi. Hamyonning yangi zaxira nusxasini yaratish kerak bo'ladi.
Agar bu hamyonda faqat tomosha skriptlari mavjud bo'lsa, yangi hamyon yaratiladi, unda faqat tomosha qilish uchun skriptlar mavjud.
Agar bu hamyonda echilishi mumkin bo'lgan, lekin tomosha qilinmagan skriptlar bo'lsa, ushbu skriptlarni o'z ichiga olgan boshqa va yangi hamyon yaratiladi.

Migratsiya jarayoni ko'chirishdan oldin hamyonning zaxira nusxasini yaratadi. Ushbu zaxira fayli &lt;wallet name&gt;- &lt;timestamp&gt; deb nomlanadi va uni ushbu hamyon katalogida topish mumkin. Noto'g'ri migratsiya bo'lsa, zaxira nusxasini "Hamyonni tiklash" funksiyasi bilan tiklash mumkin.</translation>
    
ERR
Problems:
- The backup filename in the source (&lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak) was mangled: the translation omitted ".legacy.bak" and added spaces around the hyphen (&lt;wallet name&gt;- &lt;timestamp&gt;). The exact filename must be preserved without extra spaces.
- Minor stylistic clarity: "watchonly scripts" and "solvable but not watched scripts" are better rendered as "watchonly (faqat kuzatuv uchun) skriptlari" and "echilishi mumkin, lekin kuzatilmaydigan skriptlar" to match the source meaning.

Suggested correct translation:
Hamyonni ko'chirish ushbu hamyonni bir yoki bir nechta deskriptor hamyonga aylantiradi. Hamyonning yangi zaxira nusxasini yaratish kerak bo'ladi.
Agar bu hamyonda watchonly (faqat kuzatuv uchun) skriptlar mavjud bo'lsa, ularni o'z ichiga olgan yangi hamyon yaratiladi.
Agar bu hamyonda echilishi mumkin, lekin kuzatilmaydigan skriptlar mavjud bo'lsa, ushbu skriptlarni o'z ichiga olgan boshqa va yangi hamyon yaratiladi.

Migratsiya jarayoni ko'chirishdan oldin hamyonning zaxira nusxasini yaratadi. Ushbu zaxira fayli &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak deb nomlanadi va uni ushbu hamyon katalogida topish mumkin. Noto'g'ri migratsiya yuz berganda, zaxira nusxasini "Hamyonni tiklash" funksiyasi yordamida tiklash mumkin.
```

<!-- cache_translation_check_uz_297cc566c94a50d56fa5ef52884509c7ed463e913844f62c5f2c49269e2d1ff3 -->
```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
ERR
The translation is highly erroneous and completely unrelated. "dudlangan cho'chqa go'shti koʻchirish" translates as "smoked pork transfer," which has nothing to do with "Migrate Wallet." 

Correct translation:
Hamyonni ko‘chirish
```

<!-- cache_translation_check_uz_5473bbbbf7aaef717b9ccb2a13f16fd4de3e90f07472aa6f57ca6dc1289984d8 -->
```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Watchonly skriptlari nomli yangi hamyonga ko'chirildi%1</translation>
    
ERR
The translation contains a grammar issue: the word order is incorrect and a space is missing between "ko'chirildi" and "%1". Also, "Watchonly skriptlari" should be "faqat kuzatuvchi skriptlar" or "faqat ko‘rish uchun skriptlar" to be more accurate for Uzbek speakers.

Correct translation:
"Faqat ko‘rish uchun skriptlar '%1' nomli yangi hamyonga ko‘chirildi."
```

<!-- cache_translation_check_uz_4d3fdd2b28ea9f5f57457e50c3c1712bcdd30c56410a33857d3129c4eaee50dd -->
```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Yechish mumkin bo'lgan, lekin ko'rilmagan skriptlar nomli yangi hamyonga o'tkazildi%1</translation>
    
ERR
There are several issues:
1. The format specifier "%1" should be placed within the quotation marks, after the word 'nomli'.
2. There should be a space before "%1" if "%1" is part of the wallet name.
3. The sentence structure is awkward and omits parts of the meaning—the sense of migration and what is migrated is not precise.
4. The translation does not clearly mention "watched" (which refers to 'observed' or 'monitoring' in wallet context).
5. There's a missing period at the end in Uzbek.

Correct translation:
"Yechish mumkin bo‘lgan, biroq kuzatilmayotgan skriptlar '%1' nomli yangi hamyonga ko‘chirildi."
```

<!-- cache_translation_check_uz_c47c8c35977570e2680c36440f4758ee90c26d0a11c9d59e42725011ba520828 -->
```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Hamyon tiklanmoqda&lt;b&gt;%1&lt;/b&gt;</translation>
    
ERR
Issues:
- Missing the trailing ellipsis (…) from the source.
- No space before the <b> tag; the source has a space before &lt;b&gt;.
- Word order in Uzbek is more natural as "Hamyon <b>%1</b> tiklanmoqda…" (emphasised wallet name between).

Correct translation:
Hamyon <b>%1</b> tiklanmoqda…
```

<!-- cache_translation_check_uz_0a5b602624e9e468f3d5fde7996d52803be53fdfd2c21e9ae095e98a7e744b0d -->
```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>Agar 'pruning' funksiyasi o'chirilgan bo'lsa, hamyondan uzoq vaqt foydalanmaslik butun zanjirnni qayta sinxronlashga olib kelishi mumkin.</translation>
    
ERR
The translation is problematic. The source indicates that resyncing the entire chain happens if pruning is enabled, but the translation says it happens if pruning is disabled ("o'chirilgan"). Additionally, there is a typo in "zanjirnni" (should be "zanjirni").

Correct translation:
Agar 'pruning' funksiyasi yoqilgan bo'lsa, hamyon uzoq vaqt yopiq qolsa, butun zanjirni qayta sinxronlashtirishga to'g'ri kelishi mumkin.
```

<!-- cache_translation_check_uz_39bffa859bede978a407d2d7194a7cd3b1def2df9e2279c402dae209a2353b4e -->
```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Ushbu hamyon uchun maxfiy kalitlarni o'chirish. Maxfiy kalitsiz hamyonlar maxfiy kalitlar yoki import qilingan maxfiy kalitlar, shuningdek, HD seedlarga ega bo'la olmaydi.</translation>
    
ERR
The translation misses the final explanatory sentence "This is ideal for watch-only wallets." and partially modifies the meaning of the original. Also, "HD seedlar" should be singular or adapted for Uzbek.
Correct translation:
Ushbu hamyon uchun maxfiy kalitlarni o‘chiring. Maxfiy kalitlar o‘chirilgan hamyonlarda maxfiy kalitlar, HD urug‘i yoki import qilingan maxfiy kalitlar bo‘lmaydi. Bu faqat kuzatuvchi (watch-only) hamyonlar uchun idealdir.
```

<!-- cache_translation_check_uz_b86d92e8c1d02a024c0fbe58195f7f4c8bc49d24aaa1cf21dbf1920390a57a05 -->
```
        <source>Make a blank wallet. Blank wallets do not initially have private keys or scripts. Private keys and addresses can be imported, or an HD seed can be set, at a later time.</source>
        <translation>Bo'sh hamyon yaratish. Bo'sh hamyonlarga keyinchalik maxfiy kalitlar yoki manzillar import qilinishi mumkin, yana HD seedlar ham o'rnatilishi mumkin.</translation>
    
ERR
The translation omits important details from the source. The original specifies that blank wallets do not initially have private keys or scripts, and that private keys, addresses, or an HD seed can be set or imported later. The translation does not mention "scripts," and "addresses" are not clearly mentioned at the stage described in the source. The causality and options are not as clear as in the source text.

Correct translation:
Bo'sh hamyon yarating. Bo'sh hamyonlar dastlab maxfiy kalitlarga yoki skriptlarga ega bo‘lmaydi. Keyinchalik maxfiy kalitlar va manzillar import qilinishi yoki HD urug‘i o‘rnatilishi mumkin.
```

<!-- cache_translation_check_uz_3b87db80994dc838fb12b6f3b2ff58a3f70ccc7d1881af14ccc499ca63f84775 -->
```
        <source>&amp;Label</source>
        <translation>&amp;Ёрлик</translation>
    
ERR
The translation uses Cyrillic "Ёрлик", which is either misspelled for Uzbek (uses "қ" not "к") and Uzbek locale normally uses the Latin script. Also ensure the ampersand is present exactly once (it is).

Correct translation (Latin script, preferred for 'uz'):
&amp;Yorliq

Alternatively, in Uzbek Cyrillic (if Cyrillic is required):
&amp;Ёрлиқ
```

<!-- cache_translation_check_uz_a773a2fb9c1c29d18c7e480879c8f2269ebb18a6ac024266c97e7f2ec888f640 -->
```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Yuboruvchi(%1manzil) va  qabul qiluvchi(%2manzil) bir xil bo'lishi mumkin emas</translation>
    
ERR
The translation is incorrect and omits important details from the source. The original source explains that the address with label "%2" is already present as a receiving address and cannot be added as a sending address. The translation only states that the sender and receiver addresses cannot be the same and does not accurately convey the information about labels, nor does it preserve the format specifiers.

Correct translation:
"%1" manzili "%2" yorlig‘i bilan qabul qiluvchi manzili sifatida allaqachon mavjud va shu sababli yuboruvchi manzili sifatida qo‘shib bo‘lmaydi.
```

<!-- cache_translation_check_uz_c8c1ef80f21cf191ef166a64aa8d80046da817483d9e3dd4da206c04fdd2fc8b -->
```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>Kiritilgan %1manzil allaqachon %2yorlig'i bilan manzillar kitobida</translation>
    
ERR
The translation misses proper spacing between variables and words, resulting in "%1manzil" and "%2yorlig'i" instead of "%1 manzil" and "%2 yorlig'i". This could lead to readability issues and format specifier errors. Additionally, the sentence is incomplete; it does not finish the sentence logically ("in the address book with label" is left unresolved in Uzbek).

Correct translation:
Kiritilgan "%1" manzil allaqachon "%2" yorlig'i bilan manzillar kitobida mavjud.
```

<!-- cache_translation_check_uz_520508b7de677dc7b3047a2030d5be455288823033089e489a3325cc22a5d639 -->
```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>OK ni bosganingizda, %1to'liq blok zanjirini (%2GB) yuklab olish%4 va qayta ishlash boshlanadi, %3birinchi boshlangan%4 tranzaksiyalardan boshlab.</translation>
    
ERR
There are several issues in the translation:
- Missing spaces around variables (%1, %2, %3, %4).
- Word order and clarity are off; it does not clearly represent the original English sentence.
- The translation is somewhat confusing and omits essential conjunctions and connectors.
- The Uzbek equivalent of "block chain" ("blok zanjiri") should be used. Also, the time-ordering is not clearly translated.

Correct translation:
OK ni bosganingizda, %1 dasturi %4 dasturi ilk bor %3 da ishga tushirilganidanoq eng qadimgi tranzaksiyalardan boshlab, to'liq %4 blok zanjirini (%2 GB) yuklab olish va qayta ishlashni boshlaydi.
```

<!-- cache_translation_check_uz_cb673f65f58cc336ca4940911f502929cf0f1bae65712ded6965d300948c4a24 -->
```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Noma'lum. Sarlavhalarni oldindan sinxronlash (, %1%2%)…</translation>
    
ERR
The format specifiers are misplaced in the translation. The original English uses (%1, %2%), but the Uzbek translation has (, %1%2%), omitting %2's comma placement and not respecting the same structure. Also, “Noma'lum” is correct for "Unknown", and the rest is generally accurate, but a better, more accurate structure would be:

Correct translation:
Noma'lum. Sarlavhalar oldindan sinxronlanmoqda (%1, %2%)…

Explanation:
- Correct placement of format specifiers.
- "Sarlavhalarni oldindan sinxronlash" is grammatically less natural than "Sarlavhalar oldindan sinxronlanmoqda" for this context.
- Ellipsis must be the three dots (…) like the source.
```

<!-- cache_translation_check_uz_7f0e86460d7a30ae9deece9352530f2b6c0b943fe0321c72c37707497f7b940b -->
```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Manzilni qo'shib qo'yish</translation>
    
ERR
The translation "Manzilni qo'shib qo'yish" means "Add the address" or "To add an address", which is inaccurate. The correct translation for "Paste address from clipboard" should be closer to "Manzilni buferdan joylashtirish" or "Manzilni buferdan qo'yish".

Correct translation:
Manzilni buferdan qo'yish
```

<!-- cache_translation_check_uz_582ea3461ff481264a1373b04cdce959bb530158cabe386c309d54e9210ecbe1 -->
```
        <source>&amp;Start %1 on system login</source>
        <translation>%1 ni sistemaga kirish paytida &amp;ishga tushirish</translation>
    
ERR
Problems:
- In Uzbek the accusative suffix "-ni" should be attached to the preceding token (no space) as "%1-ni", not "%1 ni".
- The ampersand appears once (good) but ensure it is placed before the shortcut word; kept as &ishga is acceptable.

Correct translation:
%1-ni sistemaga kirish paytida &ishga tushirish
```

<!-- cache_translation_check_uz_e264875aa2d0181d8435998524cf18031b88fdaa0b06cae8efcf9381e1e30baf -->
```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi. Barcha bloklar hali ham to'liq tasdiqlangan. Bu sozlamani qaytarish butun blok zanjirini qayta yuklab olishni talab qiladi.</translation>
    
ERR
There is a significant issue with the first sentence of the translation: "Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi." The phrase "Do'kon tranzaksiyalari" appears to be a mistranslation—"do'kon" means "shop," which is not related to "transactions" in the Bitcoin context. Also, the grammar and clarity could be improved. The translation should not introduce new concepts ("shop transactions") not present in the source.

Correct translation:
Tranzaksiyalarni saqlash uchun zarur bo‘lgan disk xotirasi hajmini sezilarli darajada kamaytirish uchun pruning funksiyasini yoqish mumkin. Barcha bloklar hanuz to‘liq tekshiriladi. Ushbu sozlamani qayta o‘zgartirish blokcheynni butunlay qayta yuklab olishni talab qiladi.
```

<!-- cache_translation_check_uz_3deb161f2d4a1731b172cc3e0a1696bfca101ce25f291841c72284224197c8f1 -->
```
        <source>Size of &amp;database cache</source>
        <translation>&amp;Ma'lumotlar bazasi hajmi</translation>
    
ERR
Translation omits "cache" — it currently reads "Size of database" instead of "Size of database cache". Also keep the & exactly once (it's present). 

Suggested correct translation:
&Ma'lumotlar bazasi keshining hajmi
```

<!-- cache_translation_check_uz_bccdd656ff63aeb54d6ec0e8bc33f9b397ceed04bf188f720e33d34bbedfe0f2 -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>Skriptni &amp;tekshirish thread lari soni</translation>
    
ERR
Issues:
- Mixes English and Uzbek ("thread lari") and has a spacing error ("thread lari" should not be separated).
- Grammar is awkward in Uzbek.

Corrected translation (keeps single & before the word corresponding to "verification"):
Skriptni &tekshirish iplarining soni
```

<!-- cache_translation_check_uz_dff130823229f5844efc5539a4f524656cf366d555f0d934697c2d55a730caff -->
```
        <source>&amp;Network</source>
        <translation>&amp;Internet tarmog'i</translation>
    
ERR
The translation is understandable but slightly off: "Network" in this UI/menu context is better rendered as "Tarmoq" rather than "Internet tarmog'i" (which explicitly says "Internet network"). Keep the ampersand exactly once and no extra spaces.

Suggested corrections:
&Tarmoq

Or if you want to keep the Internet qualifier:
&Internet tarmog‘i

(Ensure the apostrophe character is consistent: use the Uzbek right single quote ’ or ASCII "'" as used elsewhere.)
```

<!-- cache_translation_check_uz_acc770a04a274fddb912f9a3aff63a29e610d5e7c3f76f217cc445b99f968a27 -->
```
        <source>Prune &amp;block storage to</source>
        <translation>&amp;Blok xotirasini bunga kesish:</translation>
    
ERR
Problems:
- Unnecessary colon at end (source has no colon).
- Uzbek phrasing "bunga kesish" is awkward; a more natural phrasing uses "gacha qisqartirish" or "gacha siqish" for "prune ... to".
- Ensure the shortcut ampersand appears exactly once (keep as & or &amp; in XML).

Suggested correct translation:
&amp;Blok xotirasini gacha qisqartirish
```

<!-- cache_translation_check_uz_0101022453d88b3baa7d30d27580774b9f7897570038d7697bc0a120a624f6b9 -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Standart bo'yicha chegirma belgilash</translation>
    
ERR
Problems:
- The translation changes meaning: "chegirma" means "discount", not "fee"; the source refers to subtracting the fee (to'lov/komissiya) from the amount.
- The translation omits the shortcut ampersand (&) which must appear exactly once.
- The wording is not a natural UX label for this option.

Suggested correct translation (with single & for shortcut):
Standart bo'yicha miqdordan &to'lovni ayirish
```

<!-- cache_translation_check_uz_449ddecc2e34f530426e7800cc8ea912099c2f092c6ca77e38ec8231c02e0e11 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>Tasdiqlanmagan oʻzgarishlarni &amp;sarflash</translation>
    
ERR
The Uzbek term "oʻzgarishlarni" ("changes") is not the correct technical term for Bitcoin "change" (the leftover amount). Use "qoldiq" or "qaytim" for "change". Also adjust number/case to match the verb.

Correct translation:
Tasdiqlanmagan qoldiqni &sarflash
```

<!-- cache_translation_check_uz_241540e72bcb494d2c8851b95c5ad2ea06d96538c2bf102d6c8d761242432aec -->
```
        <source>&amp;External signer script path</source>
        <translation>&amp;Tashqi signer skripti yo'li</translation>
    
ERR
The translation is understandable but mixes English and Uzbek ("signer" left in English). Prefer fully Uzbek technical wording.

Correct translation:
&amp;Tashqi imzolovchi skripti yo'li
```

<!-- cache_translation_check_uz_51dae1c4c9d5307ed7b84ce5bc2a33dbcbf2d99118d963b06520eac20425248b -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Kiruvchi va kirish ulanishlariga ruxsat bering</translation>
    
ERR
The translation adds an extra word ("va kirish" = "and entry") that is not in the source and changes meaning, and it omits the single & shortcut marker from the source. Also the source intended "incoming connections" (one item), not two items joined by "va".

Correct translation:
&Kiruvchi ulanishlarga ruxsat bering
```

<!-- cache_translation_check_uz_0fb48d2f7cf1429e96ef0d02b5a165bbb186e0b3fda91bee264ef425cc3876bf -->
```
        <source>&amp;Connect through SOCKS5 proxy (default proxy):</source>
        <translation>SOCKS5 proksi-server orqali ulaning (standart proksi-server):</translation>
    
ERR
The translation is mostly correct Uzbek but it omits the required shortcut ampersand (&). Also wording can be slightly improved and avoid repeating "proksi-server". 

Correct translation (with a single &):
&SOCKS5 orqali proksiga ulaning (standart proksi):
```

<!-- cache_translation_check_uz_9a8118ab8740931db10ca061033c731b58c5ac146f9a34ecd2011d695d080da0 -->
```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>Прокси порти (e.g. 9050)</translation>
    
ERR
The translation is mostly correct but contains a minor language inconsistency:
- "e.g." should be translated to Uzbek, typically as "масалан" or "например" (with "масалан" being the 'uz' (Cyrillic) equivalent).
- The rest is good.

Correct translation:
Прокси порти (масалан, 9050)
```

<!-- cache_translation_check_uz_7ebfc5a3196cf1ee1f347a3ab5b5d56ed5e0ea7f00dc37f8f034fbee070c1565 -->
```
        <source>&amp;Show tray icon</source>
        <translation> belgisini ko'rsatish</translation>
    
ERR
The translation has problems: it has a leading space, it's missing the required single '&' shortcut marker, and the phrase is incomplete/unclear ("belgisini ko'rsatish" alone means "show the icon" but doesn't specify "tray"). 

Correct translation (no leading space, includes one '&', clearer meaning):
& Tizim paneli belgisini ko'rsatish

Better without space after ampersand (common form):
&Tizim paneli belgisini ko'rsatish
```

<!-- cache_translation_check_uz_81976e189b79778b052c13f35c3d762daa60a1279e08258b289bba46ad15a7b5 -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>Манзиллар панели ўрнига трэйни &amp;йиғиш</translation>
    
ERR
The translation is incorrect. "Манзиллар панели" means "addresses panel" (manzillar = addresses), which does not match "taskbar". The rest is understandable but uses the wrong word for taskbar.

Suggested correct translation (Cyrillic Uzbek):
Таскбар ўрнига трейга &минималлаштириш
```

<!-- cache_translation_check_uz_65d7dd83131b153850001f2356a993d4290b9022a62b034c27c93adaa8871bf4 -->
```
        <source>M&amp;inimize on close</source>
        <translation>Ёпишда й&amp;иғиш</translation>
    
ERR
The Uzbek phrasing is awkward and uses an incorrect verb ("йиғиш" isn't a natural translation for "minimize") and the grammatical form "Ёпишда" is less natural than "Ёпилганда" for "on close". Also ensure the & accelerator appears exactly once.

Correct translation:
Ёпилганда &кичрайтириш
```

<!-- cache_translation_check_uz_0e3ca61ef9b4b3d222e835e420dadd119cd2a055958ea7dcce6cad35adaf389e -->
```
        <source>&amp;Unit to show amounts in:</source>
        <translation>Миқдорларни кўрсатиш учун &amp;қисм:</translation>
    
ERR
The Uzbek word "қисм" means "part" and is not the right choice for "Unit". Also the phrasing is awkward. The ampersand (&) is present exactly once, which is fine.

Better translation:
<translation>&Қайси бирликда миқдорларни кўрсатиш:</translation>
```

<!-- cache_translation_check_uz_c32cd0ba982faa29ddde042e81219974897f9e371d8c7da996e751c22464e60b -->
```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Жами ўтказмалар ҳозиргача тасдиқланган ва сафланадиган баланс томонга ҳали ҳам ҳисобланмади</translation>
    
ERR
The translation is inaccurate and somewhat awkward; it does not correctly express the original meaning. "Жами ўтказмалар ҳозиргача тасдиқланган ва сафланадиган баланс томонга ҳали ҳам ҳисобланмади" is misleading and grammatically incorrect.

Correct translation:
Тасдиқланмаган ва ҳали сарфлаш мумкин бўлган балансга қўшилмаган барча транзакциялар умумий сони
```

<!-- cache_translation_check_uz_d1a781ed64e043bfde41b29f13f270376ccf23d892abd89573657eea3202979f -->
```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarni qaytarish uchun Sozlamalar-&gt;Qiymatlar.</translation>
    
ERR
The translation omits the instruction "uncheck" (i.e., the action to unmask values) and does not fully translate "Mask values" clearly and appropriately for the context. The phrase "Qiymatlarni qaytarish uchun Sozlamalar->Qiymatlar." is unclear and incomplete as an instruction.

Correct translation:
"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirildi. Qiymatlarni ochish uchun Sozlamalar-&gt;Qiymatlarni yashirish bandidagi belgi olib tashlansin.
```

<!-- cache_translation_check_uz_51e0e582a0a1eb654dd898fd98c00e02e811efa7c2af9dacb1d777a1fa98db43 -->
```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>Hamyon maʼlumotlarga imzo qoʻyib boʻlmaydi.</translation>
    
ERR
The translation omits the nuance of the source, which clearly states that signing inputs is not possible while the wallet is locked. The translation instead makes a generic statement about not being able to sign data, and does not mention that the wallet is locked or that it's about "inputs".

Correct translation:
Hamyon qulfda ekan, kiruvchi maʼlumotlarga imzo qoʻyib boʻlmaydi.
```

<!-- cache_translation_check_uz_c6a0843bc324a45401dd945cdb67a42f3d1d669af03338b375ccedd3dff49178 -->
```
        <source>URI handling</source>
        <translation>URI осилиб қолмоқда</translation>
    
ERR
The translation "URI осилиб қолмоқда" means "URI is being handled" or can be interpreted as "URI is being processed," but it is not a direct or neutral translation of "URI handling." The word "осилиб қолмоқда" itself is a somewhat informal or awkward phrasing in this context.

A more accurate translation would be:
URI билан ишлаш
```

<!-- cache_translation_check_uz_ef91a7eaf88d2be145131d8332eca6b62c115c709639b593331f51700a4b25e2 -->
```
        <source>Client version</source>
        <translation>Мижоз номи</translation>
    
ERR
The translation "Мижоз номи" means "Client name" in Uzbek, not "Client version". The correct translation should be "Мижоз версияси" or "Клиент версияси".

Correct translation:
Мижоз версияси
```

<!-- cache_translation_check_uz_803398c68a3af7e959ef140dd81d6b165b6f273578b6cb107c9eb20e62a14ea4 -->
```
        <source>&amp;Peers</source>
        <translation>&amp;Уламлар</translation>
    
ERR
The translation uses the word "Уламлар" which is incorrect for "Peers" in Uzbek. The ampersand is preserved correctly, but the term should be "Tengdoshlar" (Latin script) or "Тенгдошлар" (Cyrillic) depending on script convention.

Correct translation:
&Tengdoshlar
```

<!-- cache_translation_check_uz_19b3ca6911125e93c8b0f704d508cba2bf2734b74b7ac4e2c1dcf74a3ff1c145 -->
```
        <source>&amp;Console</source>
        <translation>&amp;Терминал</translation>
    
ERR
The translation uses Cyrillic "Терминал", which is Russian-style and not the preferred Uzbek (uz) form. Also "Терминал" is less common than the Uzbek loanword for "Console". Keep the & shortcut exactly once.

Suggested correct translation (Uzbek, Latin script):
&amp;Konsol
```

<!-- cache_translation_check_uz_e311c9f62880c155218af6be6a14f82d7f0a663490913d46b53dd2e0a3aeb857 -->
```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>Хоҳланган миқдор сўрови. Кўрсатилган миқдорни сўраш учун буни бўш ёки ноль қолдиринг.</translation>
    
ERR
There is a semantic inaccuracy. The original says: "Leave this empty or zero to not request a specific amount," but the translation reverses the meaning and says, "to request the indicated amount." 

Correct translation:
Ихтиёрий сўраладиган миқдор. Аниқ миқдор талаб қилинмаслиги учун буни бўш ёки ноль ҳолатда қолдиринг.
```

<!-- cache_translation_check_uz_fa8dcf46e73efd34860d56026abcbad60c4fb6e08301cfbe63fae53676b7b0b2 -->
```
        <source>Copy &amp;Address</source>
        <translation>Нусҳалаш &amp; Манзил</translation>
    
ERR
Problems:
- The Uzbek word uses the wrong Cyrillic letter: "Нусҳалаш" should be "Нусхалаш".
- Word order/grammar is awkward; a more natural rendering is "Манзилни нусхалаш" (copy the address).
- The & (accelerator) is separated by spaces (" &amp; Манзил"), which would place the accelerator on a space — the & should be immediately before the letter it marks and appear exactly once.

Correct translation examples (with a single &):
- Манзилни &нусхалаш
or, if you prefer the ampersand before the first word:
- &Манзилни нусхалаш
```

<!-- cache_translation_check_uz_4d438591a26c7b83ac63cb4bb1032c7fceb3a75e9bab0879e7eece58ad0a426f -->
```
        <source>Request payment to %1</source>
        <translation> %1 дан Тўловни сўраш</translation>
    
ERR
There is an unnecessary space at the beginning of the translation. Also, Uzbek uses 'to‘lov' with an apostrophe for the letter 'ў', and the word order could be improved for naturalness. The current translation is understandable but not optimal.

Correct translation:
%1 га тўловни сўраш
```

<!-- cache_translation_check_uz_b2b33d8d8fe78b0d3b275c304b4d314449b62091d2bc0e75ab23274d19696e45 -->
```
        <source>Insufficient funds!</source>
        <translation>Кам миқдор</translation>
    
ERR
The translation is incomplete and does not fully convey the meaning of the English text "Insufficient funds!". The provided Uzbek translation "Кам миқдор" literally means "Low amount", which does not explicitly mention "funds" (money/balance), nor does it have an exclamation.

Correct translation:
Маблағ етарли эмас!
```

<!-- cache_translation_check_uz_69cfe6ac949fe030edf56b124b5263d0a68c3ff17ca4d1bf842900766bb5d8bc -->
```
        <source>Custom change address</source>
        <translation>Бошқа ўзгартирилган манзил</translation>
    
ERR
The translation "Бошқа ўзгартирилган манзил" literally means "another modified address," which does not accurately reflect the original meaning of "Custom change address." In Bitcoin context, "change address" refers to an address where change from a transaction is sent, and "custom" means user-specified.

Correct translation:
Махсус қайтарим манзили

Explanation: "Махсус" means "custom," "қайтарим" refers to "change (returned amount)," and "манзили" is "address." This translation accurately reflects the term in the context of Bitcoin.
```

<!-- cache_translation_check_uz_ea13dc9434a8577a7d395c09faf8822edacc4e9b73818e40bed115b23c233d20 -->
```
        <source>Clear &amp;All</source>
        <translation>Барчасини &amp; Тозалаш</translation>
    
ERR
The translation has formatting issues: the ampersand is separated from the word by a space ("& Тозалаш") and the word order/capitalization is inconsistent. The ampersand should appear exactly once and be attached to the letter that marks the shortcut. Also remove the extra space.

Correct translation:
Барчасини &тозалаш
```

<!-- cache_translation_check_uz_2fd748ca8d39279c301e627721bdd8fdfecefdc8445502ec3e144320869a8d98 -->
```
        <source>Paste address from clipboard</source>
        <translation>Manzilni qo'shib qo'yish</translation>
    
ERR
The translation is not accurate. The English phrase "Paste address from clipboard" means to insert (paste) the address that is currently copied to the clipboard, not to "add" (qo'shib qo'yish). The correct translation should be:

"Manzilni buferdan qo'ying" or "Manzilni xotiradan joylashtirish"

Most standard is:
"Manzilni buferdan joylashtirish"
```

<!-- cache_translation_check_uz_2fd748ca8d39279c301e627721bdd8fdfecefdc8445502ec3e144320869a8d98 -->
```
        <source>Paste address from clipboard</source>
        <translation>Manzilni qo'shib qo'yish</translation>
    
ERR
The translation is not accurate. The English phrase "Paste address from clipboard" means to insert (paste) the address that is currently copied to the clipboard, not to "add" (qo'shib qo'yish). The correct translation should be:

"Manzilni buferdan qo'ying" or "Manzilni xotiradan joylashtirish"

Most standard is:
"Manzilni buferdan joylashtirish"
```

<!-- cache_translation_check_uz_ea13dc9434a8577a7d395c09faf8822edacc4e9b73818e40bed115b23c233d20 -->
```
        <source>Clear &amp;All</source>
        <translation>Барчасини &amp; Тозалаш</translation>
    
ERR
The translation has formatting issues: the ampersand is separated from the word by a space ("& Тозалаш") and the word order/capitalization is inconsistent. The ampersand should appear exactly once and be attached to the letter that marks the shortcut. Also remove the extra space.

Correct translation:
Барчасини &тозалаш
```

<!-- cache_translation_check_uz_6cdc4967baaf4f2ceb59370bf2a92f7f257bf568c9e105d320fc624789d13a62 -->
```
        <source>true</source>
        <translation>рост</translation>
    
ERR
The translation is incorrect. "рост" is a Russian word meaning "growth" and does not correspond to "true". The correct Uzbek translation for "true" is "to‘g‘ri" or "haqiqat" or simply "ha".

Correct translation:
to‘g‘ri
```

<!-- cache_translation_check_uz_c006ff4a124dc0fb12581867ff42ec3998425ec6ad98a5486f83537f9f5988d0 -->
```
        <source>Received with</source>
        <translation>Ёрдамида қабул қилиш</translation>
    
ERR
The translation "Ёрдамида қабул қилиш" literally means "to receive with the help of", which is an awkward and inaccurate translation for "Received with" in the Bitcoin context. The more contextually appropriate translation would be "Қабул қилинган" ("Received with") or if indicating the method/source, a more natural "Қаердан қабул қилинган" can be used.

Correct translation:
Қабул қилинган

If emphasizing "received with [address/account]", then:
Қабул қилган манзил
```

<!-- cache_translation_check_uz_6d71982060e7b380b3e784bbf9bd45229f16d9f1b8524cf8d3864d410b038b76 -->
```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
ERR
The translation "Жўнатиш" means "to send" or "sending", which is a verb, while the source "Sent to" is a phrase used in transaction histories to indicate the recipient. The translation should reflect the past participle or result, not the action.

Correct translation:
"Юборилди (кому:)" or "Қуйидаги манзилга юборилди" 

A more concise correct equivalent: "Юборилди"
```

<!-- cache_translation_check_uz_12ff85ecf961641f2a58858a345acd5ac1338f0f8ed3b417d3213f908c601ebb -->
```
        <source>Mined</source>
        <translation>Фойда</translation>
    
ERR  
"Фойда" means "profit" or "benefit" in Uzbek, which does not accurately translate "Mined" in the context of Bitcoin, where "mined" refers to coins obtained through the mining process. The correct translation should be related to mining.

Correct translation:
<translation>Qazib olingan</translation>
```

<!-- cache_translation_check_uz_8fa63031947fc50136b2540c73602ef8ea9fc2801ca8c4d8b29b9207c5677172 -->
```
        <source>Last month</source>
        <translation>Ўтган хафта</translation>
    
ERR
The translation is incorrect. "Last month" means "ўтган ой" in Uzbek, but the translation uses "Ўтган хафта", which means "last week".

Correct translation:
Ўтган ой
```

<!-- cache_translation_check_uz_c006ff4a124dc0fb12581867ff42ec3998425ec6ad98a5486f83537f9f5988d0 -->
```
        <source>Received with</source>
        <translation>Ёрдамида қабул қилиш</translation>
    
ERR
The translation "Ёрдамида қабул қилиш" literally means "to receive with the help of", which is an awkward and inaccurate translation for "Received with" in the Bitcoin context. The more contextually appropriate translation would be "Қабул қилинган" ("Received with") or if indicating the method/source, a more natural "Қаердан қабул қилинган" can be used.

Correct translation:
Қабул қилинган

If emphasizing "received with [address/account]", then:
Қабул қилган манзил
```

<!-- cache_translation_check_uz_6d71982060e7b380b3e784bbf9bd45229f16d9f1b8524cf8d3864d410b038b76 -->
```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
ERR
The translation "Жўнатиш" means "to send" or "sending", which is a verb, while the source "Sent to" is a phrase used in transaction histories to indicate the recipient. The translation should reflect the past participle or result, not the action.

Correct translation:
"Юборилди (кому:)" or "Қуйидаги манзилга юборилди" 

A more concise correct equivalent: "Юборилди"
```

<!-- cache_translation_check_uz_12ff85ecf961641f2a58858a345acd5ac1338f0f8ed3b417d3213f908c601ebb -->
```
        <source>Mined</source>
        <translation>Фойда</translation>
    
ERR  
"Фойда" means "profit" or "benefit" in Uzbek, which does not accurately translate "Mined" in the context of Bitcoin, where "mined" refers to coins obtained through the mining process. The correct translation should be related to mining.

Correct translation:
<translation>Qazib olingan</translation>
```

<!-- cache_translation_check_uz_daa959aa0f45a3f88ff738abe10efdc116429f327b9ec6b446d3845696655ac3 -->
```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Hamyonni qayta yozish kerak: bajarish uchun 1%s ni qayta ishga tushiring</translation>
    
ERR
There is an error with the translation of "%s". The translation says "1%s", but in the original source there is only "%s". The number "1" is not present in the source and is erroneous. Otherwise, the translation is generally accurate.

Correct translation:
Hamyonni qayta yozish kerak: bajarishni yakunlash uchun %s ni qayta ishga tushiring
```
</details>

Number of issues: 86.
