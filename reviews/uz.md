# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>uz</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Buz%5D%20low%20quality)


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

<!-- cache_translation_check_uz_ae0b96cf49348fdc55f9a198a3ff27e4c811f3ff042a7e5043772cd909d0711f -->
```
        <source>Ctrl+Q</source>
        <translation>formatini olib tashlash(Ctrl+Q)</translation>
    
ERR
The translation is inaccurate. "Ctrl+Q" is a keyboard shortcut and should be left untranslated or, if explained, should reflect its function, which is typically "exit" or "quit" in many applications. The provided translation means "remove format (Ctrl+Q)", which is incorrect and adds unintended meaning.

Correct translation:
Ctrl+Q
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

<!-- cache_translation_check_uz_37182631947619c7631bf26ff2e81dd44a04537083ce502d7869d0486527640e -->
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
The translation has several issues:
1. "watchonly scripts" is translated as "faqat tomosha skriptlari", which should be "faqat kuzatuv (watchonly) skriptlari" or "kuzatuv skriptlari".
2. The phrase “Agar bu hamyonda faqat tomosha skriptlari mavjud bo'lsa…” is mistranslated. The source means "If this wallet contains any watchonly scripts", not "only watchonly scripts".
3. The use of "1-2.legacy.bak" as a backup filename is incorrect. The source specifies "&lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak", which should be rendered in Uzbek without hardcoding a filename.
4. The translation omits clarity and changes meaning in places, such as “solvable but not watched scripts” which is rendered inaccurately.
5. The translation of "Restore Wallet" should be in quotes as in the original.

Correct translation:
Hamyonni ko‘chirish natijasida u bir yoki bir nechta deskriptorli hamyonga aylantiriladi. Yangi hamyon zaxira nusxasini yaratish kerak bo‘ladi.
Agar ushbu hamyonda kuzatuv (watchonly) skriptlari mavjud bo‘lsa, ushbu kuzatuv skriptlarini o‘z ichiga olgan yangi hamyon yaratiladi.
Agar hamyonda echilishi mumkin bo‘lgan, lekin kuzatuv qilinmaydigan (watchonly bo‘lmagan) skriptlar mavjud bo‘lsa, ularni o‘z ichiga olgan boshqa yangi hamyon yaratiladi.

Migratsiya jarayonidan avval hamyonning zaxira nusxasi yaratiladi. Ushbu zaxira fayli &lt;hamyon nomi&gt;-&lt;vaqt tamg‘asi&gt;.legacy.bak deb nomlanadi va ushbu hamyon katalogida bo‘ladi. Notog‘ri migratsiya yuz bergan taqdirda, zaxira nusxasini “Hamyonni tiklash” funksiyasi yordamida tiklash mumkin.
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

<!-- cache_translation_check_uz_f6880955ec667ea50cb4e4bfef71c9453a6bb921663e3e0e0b7739eadefd382a -->
```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Wallet tiklanmoqda&lt;b&gt;%1&lt;/b&gt;</translation>
    
ERR
The translation omits the ellipsis (…) at the end, which is present in the source. Also, the word order could be improved for clarity in Uzbek.

Correct translation:
Hamyon tiklanmoqda &lt;b&gt;%1&lt;/b&gt;…
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

<!-- cache_translation_check_uz_e264875aa2d0181d8435998524cf18031b88fdaa0b06cae8efcf9381e1e30baf -->
```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi. Barcha bloklar hali ham to'liq tasdiqlangan. Bu sozlamani qaytarish butun blok zanjirini qayta yuklab olishni talab qiladi.</translation>
    
ERR
There is a significant issue with the first sentence of the translation: "Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi." The phrase "Do'kon tranzaksiyalari" appears to be a mistranslation—"do'kon" means "shop," which is not related to "transactions" in the Bitcoin context. Also, the grammar and clarity could be improved. The translation should not introduce new concepts ("shop transactions") not present in the source.

Correct translation:
Tranzaksiyalarni saqlash uchun zarur bo‘lgan disk xotirasi hajmini sezilarli darajada kamaytirish uchun pruning funksiyasini yoqish mumkin. Barcha bloklar hanuz to‘liq tekshiriladi. Ushbu sozlamani qayta o‘zgartirish blokcheynni butunlay qayta yuklab olishni talab qiladi.
```

<!-- cache_translation_check_uz_d85c024a002eb435ff08a1d8f0b08a11f3e6dbc43bb0a8c8429472d83c0cfb6f -->
```
        <source>Subtract fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Standart bo'yicha chegirma belgilash</translation>
    
ERR  
The current translation "Standart bo'yicha chegirma belgilash" is inaccurate and does not convey the meaning of "Subtract fee from amount by default" in the Bitcoin context. It does not mention "fee" (commission) or "amount", and "chegirma" is typically "discount," which is not the correct financial term here.

Correct translation:  
"Toʻlovni miqdordan avtomatik tarzda ayirish"
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

<!-- cache_translation_check_uz_36b1d0dcce200b2c5680f98033f8db5ce69517b039f790be59de1bbb9edd4c1f -->
```
        <source>Show tray icon</source>
        <translation> belgisini ko'rsatish</translation>
    
ERR  
There is a leading whitespace in the translation, and the translation is incomplete as it does not specify "Tray" or its equivalent in Uzbek. "Tray icon" should be translated more clearly; e.g., "Tray belgisi" or "Trey belgisi".

Correct translation:
Tray belgisini ko'rsatish
```

<!-- cache_translation_check_uz_16103a0d9552f757d16dafd70f1d65457d880fa4d135d2c2f6d95ed23ba86c1b -->
```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>Манзиллар панели ўрнига трэйни йиғиш</translation>
    
ERR  
The translation is problematic. The source says, "Minimize to the tray instead of the taskbar." The translation says, "Манзиллар панели ўрнига трэйни йиғиш," which literally translates as "Collect the tray instead of the address panel." This is incorrect: "taskbar" is not "манзиллар панели" (address panel).

Correct translation:  
Топшириқлар панели ўрнига трейга қисқартириш
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

<!-- cache_translation_check_uz_e311c9f62880c155218af6be6a14f82d7f0a663490913d46b53dd2e0a3aeb857 -->
```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>Хоҳланган миқдор сўрови. Кўрсатилган миқдорни сўраш учун буни бўш ёки ноль қолдиринг.</translation>
    
ERR
There is a semantic inaccuracy. The original says: "Leave this empty or zero to not request a specific amount," but the translation reverses the meaning and says, "to request the indicated amount." 

Correct translation:
Ихтиёрий сўраладиган миқдор. Аниқ миқдор талаб қилинмаслиги учун буни бўш ёки ноль ҳолатда қолдиринг.
```

<!-- cache_translation_check_uz_ac380b3eb983dca817b1b0df634691123748e7d2555a5dd064830e9bf6b80ec7 -->
```
        <source>Copy Address</source>
        <translation>Нусҳалаш  Манзил</translation>
    
ERR
There is an unnecessary extra space between "Нусҳалаш" and "Манзил". Also, "Нусҳалаш" is in Cyrillic script; both words should be consistently in the same script, and the standard Uzbek translation is more commonly written as "Manzilni nusxalash" (in Latin script) or "Манзилни нусҳалаш" (in Cyrillic).

Correct translation:
Manzilni nusxalash

or, if using Cyrillic:
Манзилни нусҳалаш
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

Number of issues: 52.
