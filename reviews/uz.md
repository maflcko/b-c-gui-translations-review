# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>uz</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Buz%5D%20low%20quality)


```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Hamyon shifrini ochish uchun parol iborasi noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas). Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating.
</translation>
    
YES  
The translation contains multiple issues:  
- "Hamyon shifrini ochish uchun parol iborasi noto'g'ri." is understandable but can be better phrased as "Hamyonni shifrlashni ochish uchun kiritilgan parol noto‘g‘ri."  
- The term "null belgini" is acceptable, but "birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring" is incorrect and confusing. "Qurilmalar" means "devices" which is wrong here; it should refer to "characters" or "simvol" (belgilar).  
- The phrase "(lekin shu narsa emas)" is ambiguous and unnatural; the source means "but not including" the first null character, which should be translated clearly.  
- "Agar bu voqea bo'lsa" is incorrect; it should be close to "agar bu muvaffaqiyatli bo‘lsa".  
- "bu muammoni olish uchun yangi parol o'rnating" is wrong and confusing; literally "set a new password to get this problem" which contradicts the meaning. It should be "bu muammoni kelgusida oldini olish uchun yangi parol belgilang."  

Correct translation:  
Hamyonni shifrlashni ochish uchun kiritilgan parol noto‘g‘ri. U null belgini o‘z ichiga oladi (ya’ni, nol bayt). Agar parol ushbu dasturiy ta’minotning 25.0 oldingi versiyasida o‘rnatilgan bo‘lsa, iltimos, birinchi null belgigacha bo‘lgan belgilar bilan (birinchi null belgini o‘z ichiga olmay) qayta urinib ko‘ring. Agar bu muvaffaqiyatli bo‘lsa, iltimos, kelgusida ushbu muammoning oldini olish uchun yangi parol belgilang.
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Hamyon shifrini ochish uchun yordam eski parol noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas).</translation>
    
YES  
The translation contains several mistakes and awkward phrasing that affect clarity and correctness:

1. "Hamyon shifrini ochish uchun yordam eski parol noto'g'ri."  
   - This phrase is grammatically incorrect and unclear. It should convey: "The old passphrase entered for wallet decryption is incorrect." The current wording is confusing and missing proper structure.

2. "U null belgini o'z ichiga oladi (ya'ni - nol bayt)."  
   - "null belgini" is acceptable, but it should be singular and better phrased as "null belgisi".

3. "Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa..."  
   - This part is mostly ok but could be clearer and smoother.

4. "iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas)."  
   - "qurilmalar" means "devices" and is incorrect here; the source means "characters". So it should be "faqat birinchi null belgigacha bo‘lgan belgilar bilan qayta urinib ko‘ring (lekin shu belgini o‘zini kiritmay)."

Correct translation suggestion:

Hamyonni shifrlash uchun kiritilgan eski parol noto‘g‘ri. U null belgini (ya’ni — nol bayt) o‘z ichiga oladi. Agar parol iborasi ushbu dasturiy ta’minotning 25.0 versiyasidan oldin sozlangan bo‘lsa, iltimos, faqat birinchi null belgigacha bo‘lgan belgilar bilan (null belgini o‘zini kiritmay) qayta urinib ko‘ring.
```

```
        <source>Banned Until</source>
        <translation>gacha kirish taqiqlanadi</translation>
    
YES  
The translation "gacha kirish taqiqlanadi" literally means "access is banned until," but it is incomplete and does not explicitly convey the "Until" time aspect as a standalone phrase "Banned Until" would. The source phrase is typically used as a label indicating a time or date until which a ban applies. A more accurate and natural Uzbek translation should clearly indicate the temporal limit, such as:

Correct translation:  
"Taqiqlangan muddatgacha"  
or  
"Taqiqlangan vaqtgacha"
```

```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>Fatal xatolik yuz berdi. %1 xavfsiz ravishda davom eta olmaydi va tizimni tark etadi. </translation>
    
YES  
The translation is mostly accurate but contains a minor issue with an extra trailing space before the closing tag, which should be removed to avoid formatting problems. Also, the phrase "tizimni tark etadi" literally means "will quit the system," which may be misleading. A better phrase would be "dasturni to'xtatadi" (will quit the program) or "dasturdan chiqadi" (will exit the program), which aligns better with the context of a software error.

Correct translation:  
Fatal xatolik yuz berdi. %1 xavfsiz ravishda davom eta olmaydi va dasturni to'xtatadi.
```

```
        <source>%1 m</source>
        <translation>%1 д</translation>
    
YES
The English source "%1 m" likely means "%1 meters" where "m" stands for meters. The translation "%1 д" uses a Cyrillic letter "д", which does not correspond to "meters" in Uzbek. Uzbek typically uses the Latin script and "m" for meters as well. If using Cyrillic, the letter for meters would still be "м" (Cyrillic 'm'), not "д" (which corresponds to "d"). Therefore, the translated unit is incorrect.

Correct translation:
%1 m
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Паролни ўзгартириш ҳамённи кодлашда фойдаланилади</translation>
    
YES  
The translation is incorrect and somewhat confusing. The source means "Change the passphrase used for wallet encryption," instructing the user to change the passphrase. The given translation says roughly "The password change is used in wallet encryption," which does not convey the meaning accurately.  

Correct translation:  
"Ҳамённи кодлашда фойдаланиладиган паролни ўзгартириш"
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>To'lovlarni so'rash(QR kolar va bitkoin yaratish: URL manzillar)</translation>
    
YES  
The translation contains spacing issues and incorrect terminology. "QR codes" is mistranslated as "QR kolar" instead of "QR kodlari." Also, "bitcoin: URIs" is incorrectly translated as "bitkoin yaratish: URL manzillar," which means "bitcoin creation: URL addresses" instead of "bitcoin: URIs." The correct part should use "bitcoin: URI" as is or translated appropriately.

Correct translation:  
To‘lovlarni so‘rash (QR kodlari va bitcoin: URI lar yaratadi)
```

```
        <source>Ctrl+Q</source>
        <translation>formatini olib tashlash(Ctrl+Q)</translation>
    
YES  
The English source "Ctrl+Q" is a keyboard shortcut and should be translated as is or with an equivalent Uzbek keyboard shortcut notation, but not with an explanatory phrase like "formatini olib tashlash(Ctrl+Q)". The translation adds unnecessary explanation and changes the content entirely.

Correct translation:  
Ctrl+Q
```

```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
YES  
The translation is incorrect and irrelevant. "dudlangan cho'chqa go'shti koʻchirish" means "migrate smoked pork," which is unrelated to "Migrate Wallet" in a Bitcoin context.

Correct translation:  
Hamyonni koʻchirish
```

```
        <source>Ctrl+M</source>
        <translation>Abzatsga chek qo'ying.(Ctrl+M)</translation>
    
YES  
The source text "Ctrl+M" is a keyboard shortcut and should be translated literally or kept as is. The translation "Abzatsga chek qo'ying.(Ctrl+M)" means "Place a paragraph mark (Ctrl+M)" which adds extra meaning not present in the source. It also includes an unnecessary parenthetical with the shortcut. The translation does not match the source.

Correct translation:  
Ctrl+M
```

```
        <source>Click for more actions.</source>
        <extracomment>A substring of the tooltip. "More actions" are available via the context menu.</extracomment>
        <translation>Ko'proq sozlamalar uchun bosing.</translation>
    
YES
The translation uses "sozlamalar" which means "settings" rather than "actions." The correct word for "actions" in this context is "harakatlar."

Correct translation:
Ko‘proq harakatlar uchun bosing.
```

```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini cheklash</translation>
    
YES  
The original phrase "Disable network activity" refers to disabling all network operations related to Bitcoin, not specifically "social network" activity. The Uzbek translation "Ijtimoiy tarmoq faoliyatini cheklash" means "Restrict social network activity," which is inaccurate and misleading.

Correct translation:  
"Tarmoq faoliyatini o‘chirish"  
or more literally:  
"Tarmoq faoliyatini o‘chirib qo‘yish"
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini yoqish</translation>
    
YES  
The translation "Ijtimoiy tarmoq faoliyatini yoqish" means "Enable social network activity," which is incorrect in the Bitcoin context. The source refers to network activity in the sense of P2P or Bitcoin network, not social networks.

Correct translation:  
"Tarmoqlik faoliyatini yoqish"  
or more explicitly  
"Tarmoq faoliyatini yoqish"
```

```
        <source>Copy fee</source>
        <translation>Narxni nusxalash</translation>
    
YES  
The translation "Narxni nusxalash" literally means "Copy the price," which is incorrect in this Bitcoin context. "Fee" in this context refers to a transaction fee or commission, not just a "price." A more accurate translation would be "To'lovni nusxalash" or "Komissiyani nusxalash," meaning "Copy fee" as copying the fee amount.

Correct translation:  
To'lovni nusxalash
```

```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>Hamyonni ko'chirish ushbu hamyonni bir yoki bir nechta deskriptor hamyonga aylantiradi. Hamyonning yangi zaxira nusxasini yaratish kerak bo'ladi.
Agar bu hamyonda faqat tomosha skriptlari mavjud bo'lsa, yangi hamyon yaratiladi, unda faqat tomosha qilish uchun skriptlar mavjud.
Agar bu hamyonda echilishi mumkin bo'lgan, lekin tomosha qilinmagan skriptlar bo'lsa, ushbu skriptlarni o'z ichiga olgan boshqa va yangi hamyon yaratiladi.

Migratsiya jarayoni ko'chirishdan oldin hamyonning zaxira nusxasini yaratadi. Ushbu zaxira fayli 1-2.legacy.bak deb nomlanadi va uni ushbu hamyon katalogida topish mumkin. Noto'g'ri migratsiya bo'lsa, zaxira nusxasini "Hamyonni tiklash" funksiyasi bilan tiklash mumkin.</translation>
    
YES
The translation is mostly accurate but has two main issues:

1. The placeholder "%1" or "<wallet name>-<timestamp>" from the source is replaced incorrectly with a fixed "1-2.legacy.bak" filename in the translation. The translation should keep the placeholder or a generic representation corresponding to the source to indicate the dynamic filename.

2. Minor phrasing could be improved for clarity, especially the second sentence in the second paragraph could more naturally specify "faqat tomosha skriptlarini o'z ichiga olgan yangi hamyon yaratiladi" rather than "undа faqat tomosha qilish uchun skriptlar mavjud."

Suggested corrected translation:

Hamyonni ko'chirish ushbu hamyonni bir yoki bir nechta deskriptor hamyonga aylantiradi. Hamyonning yangi zaxira nusxasini yaratish kerak bo'ladi.  
Agar bu hamyonda faqat tomosha skriptlari mavjud bo'lsa, ularni o'z ichiga olgan yangi hamyon yaratiladi.  
Agar bu hamyonda echilishi mumkin bo'lgan, lekin tomosha qilinmagan skriptlar mavjud bo'lsa, ushbu skriptlarni o'z ichiga olgan boshqa va yangi hamyon yaratiladi.

Migratsiya jarayoni ko'chirishdan oldin hamyonning zaxira nusxasini yaratadi. Ushbu zaxira fayli &lt;hamyon nomi&gt;-&lt;vaqt tamg'asi&gt;.legacy.bak deb nomlanadi va uni ushbu hamyon katalogida topish mumkin. Noto'g'ri migratsiya bo'lsa, zaxira nusxasini "Hamyonni tiklash" funksiyasi bilan tiklash mumkin.
```

```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
YES  
The translation is incorrect and irrelevant. "dudlangan cho'chqa go'shti koʻchirish" means "migrate smoked pork," which is unrelated to "Migrate Wallet" in a Bitcoin context.

Correct translation:  
Hamyonni koʻchirish
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Watchonly skriptlari nomli yangi hamyonga ko'chirildi%1</translation>
    
YES  
The translation is missing a connecting particle and has formatting issues. The placement of %1 is incorrect (it should be inside the sentence with appropriate spacing), and "Watchonly" should be transliterated or translated. Moreover, "skriptlari" should be plural in the context (scripts), and there should be the equivalent of "have been migrated to" expressed clearly in Uzbek.

Correct translation:  
"Watchonly skriptlari '%1' nomli yangi hamyonga ko'chirildi."
```

```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Yechish mumkin bo'lgan, lekin ko'rilmagan skriptlar nomli yangi hamyonga o'tkazildi%1</translation>
    
YES  
The translation has formatting issues and is missing a space before the placeholder %1, which should be separated and inside quotes properly to match the source. Also, the phrase "nomli yangi hamyonga" ("to a new wallet named") is awkwardly placed and needs reordering for clarity and naturalness. The correct translation would be:  

Yechilishi mumkin, lekin kuzatilmagan skriptlar '%1' nomli yangi hamyonga ko'chirildi.
```

```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Wallet tiklanmoqda&lt;b&gt;%1&lt;/b&gt;</translation>
    
YES
The translation misses the ellipsis "…" that is present in the source and there is no space before the bold tag, making it less natural. Also, "Wallet" should preferably be translated or consistently transliterated, and "tiklanmoqda" literally means "is being restored," which is correct, but a small spacing fix is needed.

Correct translation:
"Wallet &lt;b&gt;%1&lt;/b&gt; tiklanmoqda…"
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>Agar 'pruning' funksiyasi o'chirilgan bo'lsa, hamyondan uzoq vaqt foydalanmaslik butun zanjirnni qayta sinxronlashga olib kelishi mumkin.</translation>
    
YES  
The translation incorrectly states that the wallet resyncing issue happens if pruning is disabled ("o'chirilgan bo'lsa"), while the source says it happens if pruning is enabled. Also, there is a typo in "zanjirnni" (should be "zanjirni"). The phrase "Closing the wallet for too long" is not fully conveyed by "hamyondan uzoq vaqt foydalanmaslik" (not using the wallet for a long time), which could be improved for clarity.

Correct translation:  
Agar pruning funksiyasi yoqilgan bo'lsa, hamyonni juda uzoq vaqt yopib qo'yish butun zanjirni qayta sinxronlashga olib kelishi mumkin.
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Ushbu hamyon uchun maxfiy kalitlarni o'chirish. Maxfiy kalitsiz hamyonlar maxfiy kalitlar yoki import qilingan maxfiy kalitlar, shuningdek, HD seedlarga ega bo'la olmaydi.</translation>
    
YES  
The translation omits the part explaining that wallets with private keys disabled cannot have an HD seed, which is important. It also misses the concluding sentence about this being ideal for watch-only wallets. Additionally, "Uchirish" ("disable") is better as "o‘chirib qo‘yish" or "faolligini o‘chirib qo‘yish" in this context, to better convey "disable."

Correct translation:  
Ushbu hamyon uchun maxfiy kalitlarni o‘chirib qo‘yish. Maxfiy kalitlari o‘chirib qo‘yilgan hamyonlarda maxfiy kalitlar bo‘lmaydi va ular HD seed yoki import qilingan maxfiy kalitlarga ega bo‘la olmaydi. Bu faqat kuzatuv uchun mo‘ljallangan hamyonlar uchun ideal hisoblanadi.
```

```
        <source>Make a blank wallet. Blank wallets do not initially have private keys or scripts. Private keys and addresses can be imported, or an HD seed can be set, at a later time.</source>
        <translation>Bo'sh hamyon yaratish. Bo'sh hamyonlarga keyinchalik maxfiy kalitlar yoki manzillar import qilinishi mumkin, yana HD seedlar ham o'rnatilishi mumkin.</translation>
    
YES  
The translation is incomplete and does not fully convey the original meaning. The English source says that blank wallets initially do not have private keys or scripts, and that private keys, addresses, or an HD seed can be imported or set later. The Uzbek translation omits the part about scripts and addresses at the start, and the sentence structure is less precise. Also, "HD seedlar" could be better expressed using Uzbek plurals consistently.

Correct translation:  
Bo'sh hamyon yarating. Bo'sh hamyonlarda dastlab hech qanday maxfiy kalitlar yoki skriptlar mavjud emas. Maxfiy kalitlar, manzillar import qilinishi yoki HD seed keyinchalik o'rnatilishi mumkin.
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Yuboruvchi(%1manzil) va  qabul qiluvchi(%2manzil) bir xil bo'lishi mumkin emas</translation>
    
YES  
The translation is incomplete and does not accurately reflect the source content. The source states that the address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address. The translation only says "Yuboruvchi(%1manzil) va  qabul qiluvchi(%2manzil) bir xil bo'lishi mumkin emas" which means "Sender (%1 address) and receiver (%2 address) cannot be the same," which changes the meaning and omits important details.

Correct translation:  
Manzil "%1" allaqachon "%2" yorlig'i bilan qabul qiluvchi manzili sifatida mavjud va shuning uchun yuboruvchi manzili sifatida qo'shilishi mumkin emas.
```

```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>Kiritilgan %1manzil allaqachon %2yorlig'i bilan manzillar kitobida</translation>
    
YES  
The Uzbek translation is grammatically incorrect and lacks necessary spacing and punctuation. The placeholders %1 and %2 should be enclosed with quotes like in the source, and the sentence should maintain proper word order and spacing. Also, the translation misses the equivalent of "address book" properly ("manzillar kitobi" is correct, not "manzillar kitobida" without prepositions or context). A better translation would be:

Kiritilgan "%1" manzil allaqachon "%2" yorlig'i bilan manzillar kitobida mavjud.
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>OK ni bosganingizda, %1to'liq blok zanjirini (%2GB) yuklab olish%4 va qayta ishlash boshlanadi, %3birinchi boshlangan%4 tranzaksiyalardan boshlab.</translation>
    
YES  
The translation has several issues:  
- Missing spaces in "%1to'liq", "%2GB", "yuklab olish%4", "%3birinchi", and "%4 tranzaksiyalardan", causing words and format specifiers to run together.  
- Incorrect word order and phrasing that makes the sentence awkward and unclear.  
- The position of %4 is inconsistent and confusing; in English it refers to the "block chain" and the phrase "starting with the earliest transactions in %3 when %4 initially launched" needs to be properly conveyed.

Correct translation:  
OK ni bosganingizda, %1 %4 blok zanjirining to‘liq nusxasini (%2 GB) yuklab olib, %4 dastlab ishga tushganida %3 dagi eng eski tranzaksiyalardan boshlab qayta ishlashni boshlaydi.
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Noma'lum. Sarlavhalarni oldindan sinxronlash (, %1%2%)…</translation>
    
YES  
The translation incorrectly places the format specifiers (%1, %2%) inside parentheses and merges them without proper order or spacing. Also, the word "Noma'lum" should be "Noma’lum" with a proper apostrophe. The correct translation should preserve the order and formatting of %1 and %2%, as in the source.

Correct translation:  
Noma’lum. Sarlavhalarni oldindan sinxronlash (%1, %2%)…
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Manzilni qo'shib qo'yish</translation>
    
YES
The translation "Manzilni qo'shib qo'yish" means "to add the address," which does not accurately reflect the source phrase "Paste address from clipboard." The correct translation should convey the action of pasting (i.e., inserting from the clipboard) an address.

Correct translation:
"Manzilni clipboarddan joylashtirish" or more naturally "Manzilni clipboarddan yopishtirish"
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi. Barcha bloklar hali ham to'liq tasdiqlangan. Bu sozlamani qaytarish butun blok zanjirini qayta yuklab olishni talab qiladi.</translation>
    
YES  
The translation contains some inaccuracies and awkward phrasing:

1. "Do'kon tranzaksiyalari katta xotira talab qilgani tufayli" incorrectly translates as "Because shop transactions require large memory," which does not reflect the meaning of the English source. The original talks about disk space required to store transactions, not "shop transactions."

2. "pruning ni" should be written as "pruningni" (no space before the suffix).

3. "xotirada joy kamayishiga olib keladi" ("leads to a decrease of space in memory") is slightly off; "disk space" is more precisely "diskdagi joy".

4. The phrase "sezilarli darajada xotirada joy kamayishiga olib keladi" is a bit awkward; better phrasing would be "diskda joy talabini sezilarli darajada kamaytiradi" ("significantly reduces disk space requirements").

5. "Barcha bloklar hali ham to'liq tasdiqlangan" - better to say "Barcha bloklar hamon to‘liq tekshiriladi" or "tasdiqlanadi" (validated); "hali ham" is a bit less natural than "hamon".

6. "Bu sozlamani qaytarish" is not very clear. Better: "Ushbu sozlamani bekor qilish" ("reverting this setting").

7. "butun blok zanjirini" - more standard is "butun blokcheynni" or "butun blok zanjirini" (both used, but "blok zanjiri" is common).

8. "qayta yuklab olishni talab qiladi" is okay.

Corrected translation:

"Pruningni yoqish tranzaksiyalarni saqlash uchun kerak bo‘lgan diskdagi joyni sezilarli darajada kamaytiradi. Barcha bloklar hamon to‘liq tekshiriladi. Ushbu sozlamani bekor qilish butun blokcheynni qayta yuklab olishni talab qiladi."

Final output:

YES  
The translation has inaccuracies such as misinterpretation of "pruning," awkward phrasing regarding disk space, and spacing issues in "pruning ni." It can be improved for clarity and correctness.

Correct translation:  
Pruningni yoqish tranzaksiyalarni saqlash uchun kerak bo‘lgan diskdagi joyni sezilarli darajada kamaytiradi. Barcha bloklar hamon to‘liq tekshiriladi. Ushbu sozlamani bekor qilish butun blokcheynni qayta yuklab olishni talab qiladi.
```

```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>Chegirma to'lovini standart qilib belgilash kerakmi yoki yo'qmi?</translation>
    
YES  
The translation "Chegirma to'lovini standart qilib belgilash kerakmi yoki yo'qmi?" is incorrect because "Chegirma" means "discount," which is not appropriate for "subtract fee." The original sentence refers to subtracting the transaction fee from the amount, not applying a discount.

Correct translation:  
"To'lovni summadan ayirishni standart qilib belgilash kerakmi yoki yo'qmi?"
```

```
        <source>Subtract fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Standart bo'yicha chegirma belgilash</translation>
    
YES  
The translation "Standart bo'yicha chegirma belgilash" incorrectly translates the original sentence "Subtract fee from amount by default." The phrase "chegirma" means "discount," which is not accurate here. The source refers to subtracting a transaction fee from the amount by default, not applying a discount. Also, the original phrase mentions "fee" (to'lov/komissiya) and "subtract" (ayirish).

Correct translation:  
"Standart bo'yicha to'lovni summadan ayirish"
```

```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>Прокси порти (e.g. 9050)</translation>
    
YES  
The translation uses Cyrillic script ("Прокси порти") which is acceptable in Uzbek but the English abbreviation "e.g." is left untranslated, which is inconsistent and not typical for Uzbek text. It should be translated or omitted for clarity.

Correct translation:  
Proksi porti (masalan, 9050)
```

```
        <source>Show tray icon</source>
        <translation> belgisini ko'rsatish</translation>
    
YES
The translation is missing the subject or the noun that "belgisini" (its icon) refers to, making it incomplete and unclear. Also, there is an unnecessary leading space before the text. A more accurate translation of "Show tray icon" would be:

"Bildirishnoma oynasi belgisini ko‘rsatish" 

(if "tray icon" refers to a notification tray icon) or simply

"Tray belgisini ko‘rsatish" 

if "tray" is kept untranslated or explained otherwise. If "tray icon" is a specific term, it should be clarified, but at minimum, the leading space must be removed.
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>Манзиллар панели ўрнига трэйни йиғиш</translation>
    
YES  
The translation is incorrect and partially unrelated. "Манзиллар панели" means "address panel," which is a mistranslation of "taskbar." The correct translation of "taskbar" in Uzbek is "везифалар панели" or simply "таскбар." Also, "трэйнй йиғиниш" is acceptable for "minimize to the tray," but better phrasing is possible.

Correct translation:  
"Везифалар панели ўрнига трэйга кичрайтиш"  
or  
"Таскбар ўрнига трэйга кичрайтиш"
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Жами ўтказмалар ҳозиргача тасдиқланган ва сафланадиган баланс томонга ҳали ҳам ҳисобланмади</translation>
    
YES  
The translation is inaccurate and contains errors. The source says "transactions that have yet to be confirmed" and "do not yet count toward the spendable balance." The Uzbek translation says "confirmed" (тасдиқланган), which is opposite in meaning. Also, "с афланадиган баланс томонга" is awkward and unclear.

Correct translation:  
"Ҳозиргача тасдиқланмаган, шунингдек, сарфланиши мумкин бўлган балансга ҳали қўшилмаган ўтказмалар жами"
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarni qaytarish uchun Sozlamalar-&gt;Qiymatlar.</translation>
    
YES  
The translation is incomplete and somewhat inaccurate. It does not convey the full meaning of the original sentence, specifically the phrase "uncheck Settings->Mask values" is mistranslated as "Sozlamalar->Qiymatlar," missing the action of unchecking and the word "Mask."  

Correct translation:  
"«Umumiy ko‘rinish» yorlig‘i uchun maxfiylik rejimi faollashtirildi. Qiymatlarni ko‘rsatish uchun Sozlamalar → Qiymatlarni yashirish belgisini o‘chiring."
```

```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>Hamyon maʼlumotlarga imzo qoʻyib boʻlmaydi.</translation>
    
YES  
The translation "Hamyon maʼlumotlarga imzo qoʻyib boʻlmaydi." means "Cannot sign the wallet data," which changes the original meaning. The original English says "Cannot sign inputs while wallet is locked," indicating that signing inputs is impossible when the wallet is locked, not that wallet data cannot be signed in general.

A more accurate translation would explicitly mention the wallet is locked and that signing inputs is not possible, for example:  
"Hamyon qulflanganda kiritmalarni imzolab boʻlmaydi."
```

```
        <source>URI handling</source>
        <translation>URI осилиб қолмоқда</translation>
    
YES  
The translation "URI осилиб қолмоқда" means "URI is hanging" or "URI is freezing," which is inaccurate for "URI handling." The source phrase refers to managing or processing URIs, not describing a state of freezing or hanging.

Correct translation:  
"URI ни бошқариш"  
or simply  
"URI ишлов бериш"
```

```
        <source>Client version</source>
        <translation>Мижоз номи</translation>
    
YES  
The translation is incorrect. "Client version" refers to the version number of a software client, but "Мижоз номи" means "Client name" in Uzbek. The correct translation should reflect "version," not "name."

Correct translation:  
Клиент версияси
```

```
        <source>Open</source>
        <translation>Очиш</translation>
    
YES  
The Uzbek word "Очиш" is incorrect for the English "Open." The correct translation should be "Очиқ" (meaning "open" as an adjective) or "Очиш" is a verb meaning "to open," but it usually appears as "Очиш" is the infinitive form "to open." However, the proper way to say "Open" as a command or label (e.g., button label) is "Очиқ" (adjective) or "Очиш" may be understood, but more common and correct in UI context is "Очиқ".  

Correct translation:  
Очиқ
```

```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>Хоҳланган миқдор сўрови. Кўрсатилган миқдорни сўраш учун буни бўш ёки ноль қолдиринг.</translation>
    
YES  
The translation is in Cyrillic script and appears to be in Uzbek, but it uses a mix of Russian loanwords and phrasing that is unnatural and possibly incorrect in standard Uzbek. Also, the original English meaning is slightly altered. A clearer and more natural Uzbek translation would be:  

"Ixtiyoriy so‘rov summasi. Belgilangan summani so‘ramaslik uchun bu qatorni bo‘sh yoki nol qoldiring."
```

```
        <source>Copy Address</source>
        <translation>Нусҳалаш  Манзил</translation>
    
YES  
The translation contains an extra space between "Нусҳалаш" and "Манзил". In Uzbek written in Cyrillic, this phrase should be "Нусҳалаш манзил" with only one space. Also, it is preferable to use lowercase "манзил" unless at the start of a sentence or for stylistic reasons.

Correct translation:  
Нусҳалаш манзил
```

```
        <source>Request payment to %1</source>
        <translation> %1 дан Тўловни сўраш</translation>
    
YES  
There is an extra leading space before "%1" in the translation, which is unnecessary and inconsistent with the source. The phrase is also slightly awkward in Uzbek. A more natural translation would be without the leading space and adjusted word order:

Correct translation:  
%1 га тўлов сўраш
```

```
        <source>Insufficient funds!</source>
        <translation>Кам миқдор</translation>
    
YES  
The translation "Кам миқдор" means "Low amount" or "Small quantity," which is not a complete or accurate translation of "Insufficient funds!" The source expresses a lack of enough money/funds, usually in an exclamation form indicating an error or warning, whereas the translation is more neutral and incomplete.

A more accurate translation would be:  
"Маблағ етарли эмас!"
```

```
        <source>Custom change address</source>
        <translation>Бошқа ўзгартирилган манзил</translation>
    
YES  
The provided translation uses Cyrillic script which is typical for Uzbek, but the translation is inaccurate and somewhat unclear. The English phrase "Custom change address" refers to a Bitcoin wallet address designated for the change amount in a transaction and "custom" implies user-defined. The given translation "Бошқа ўзгартирилган манзил" literally means "Another changed address," which is not accurate.

A better translation would be:  
"Махсус ўзгартириш манзили"  
or  
"Фарқли ўзгартириш манзили"  

Both suggest a "custom/particular change address" more accurately in Uzbek.  
Hence the corrected translation could be:

<translation>Махсус ўзгартириш манзили</translation>
```

```
        <source>Copy fee</source>
        <translation>Narxni nusxalash</translation>
    
YES  
The translation "Narxni nusxalash" literally means "Copy the price," which is incorrect in this Bitcoin context. "Fee" in this context refers to a transaction fee or commission, not just a "price." A more accurate translation would be "To'lovni nusxalash" or "Komissiyani nusxalash," meaning "Copy fee" as copying the fee amount.

Correct translation:  
To'lovni nusxalash
```

```
        <source>Warning: Unknown change address</source>
        <translation>Диққат: Номаълум ўзгариш манзили</translation>
    
YES  
The translation is in Cyrillic script, which is used by some Uzbek speakers, but modern Uzbek is more commonly written in Latin script. More importantly, the phrase "Номаълум ўзгариш манзили" translates literally to "Unknown change address," but "ўзгариш" (change) here may be confusing or less appropriate; in the Bitcoin context, "change" refers to the leftover amount from a transaction, and "ўзгариш манзили" might be unclear.

A more precise and clear translation in Uzbek (Latin script) would be:  
"Ogohlantirish: noma'lum o'zgartirish manzili"

If you want to keep Cyrillic script, it should be:  
"Диққат: номаълум ўзгартириш манзили"

Depending on preferred script, either version works. Also, the initial word "Warning:" is best translated as "Диққат:" (Cyrillic) or "Ogohlantirish:" (Latin).

Correct translation (Latin script):  
<translation>Ogohlantirish: noma'lum o'zgartirish manzili</translation>

Correct translation (Cyrillic script):  
<translation>Диққат: номаълум ўзгартириш манзили</translation>
```

```
        <source>Paste address from clipboard</source>
        <translation>Manzilni qo'shib qo'yish</translation>
    
YES  
The translation "Manzilni qo'shib qo'yish" means "Add address" or "Attach address," which does not correctly convey the instruction to "Paste address from clipboard." The accurate translation should imply pasting (inserting) content from the clipboard.

Correct translation:  
"Manzilni clipboarddan joylashtirish"  
or more naturally in Uzbek:  
"Manzilni vaqtinchalik xotiradan joylashtirish"  
or simply:  
"Manzilni clipboarddan joylashtirish"

A clearer and more commonly used phrase would be:  
"Manzilni clipboarddan yapishtirish"  
("yapishtirish" means "to paste").  

Hence, the best correction is:  
"Manzilni clipboarddan yapishtirish"
```

```
        <source>Paste address from clipboard</source>
        <translation>Manzilni qo'shib qo'yish</translation>
    
YES  
The translation "Manzilni qo'shib qo'yish" means "Add address" or "Attach address," which does not correctly convey the instruction to "Paste address from clipboard." The accurate translation should imply pasting (inserting) content from the clipboard.

Correct translation:  
"Manzilni clipboarddan joylashtirish"  
or more naturally in Uzbek:  
"Manzilni vaqtinchalik xotiradan joylashtirish"  
or simply:  
"Manzilni clipboarddan joylashtirish"

A clearer and more commonly used phrase would be:  
"Manzilni clipboarddan yapishtirish"  
("yapishtirish" means "to paste").  

Hence, the best correction is:  
"Manzilni clipboarddan yapishtirish"
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/тасдиқланмади</translation>
    
YES  
The translation uses Cyrillic script ("тасдиқланмади"), which corresponds more to Tajik or Russian-influenced Uzbek. Modern Uzbek in Latin script is the official standard and widely used. Also, "тасдиқланмади" means "not confirmed," but the English source is "%1/unconfirmed," where "%1" is a placeholder, and "unconfirmed" is the text after the slash.

The slash should be kept as is, and spacing must be consistent. The translation should match "%1/unconfirmed" with "%1/ tasdiqlanmagan" in Latin Uzbek, accurately reflecting "unconfirmed." There should be no extra spacing around the slash.

Correct translation:  
%1/tasdiqlanmagan
```

```
        <source>Credit</source>
        <translation>Кредит (қарз)</translation>
    
YES  
The translation uses the Cyrillic script, which is acceptable for Uzbek but somewhat less common in modern contexts where Latin script is preferred. However, the main issue is the addition of "(қарз)" which means "(debt)" — this is misleading because "Credit" in the Bitcoin/financial context usually means an incoming amount or a positive transaction, not necessarily a loan or debt.

A more accurate and concise translation would be simply:  
Кредит

Alternatively, using Latin script which is officially used for Uzbek:  
Kredit

If Cyrillic is preferred, just "Кредит" without the parenthetical explanation is cleaner and less confusing.
```

```
        <source>true</source>
        <translation>рост</translation>
    
YES  
The translation is incorrect. The English word "true" should be translated to "haqiqiy" or "to'g'ri" in Uzbek, meaning "true" or "correct." The provided word "рост" is Russian and means "growth," which is unrelated and incorrect in this context.

Correct translation:  
<translation>haqiqiy</translation>
```

```
        <source>Received with</source>
        <translation>Ёрдамида қабул қилиш</translation>
    
YES  
The translation "Ёрдамида қабул қилиш" is not an accurate or natural translation of "Received with." The phrase "Received with" in the Bitcoin context usually implies something like "qabul qilindi" (received) paired with a method or source, so the preposition "with" should be translated as "bilan" or "orqali," not "ёмдамида," which is also misspelled (correct is "ярдамида"). Additionally, the phrase structure is awkward and incomplete in Uzbek.

Correct translation:  
"Bilan qabul qilindi"  
or more naturally:  
"Qabul qilindi (bilan)" if context allows parentheses.  
If space is limited and context clear, "Qabul qilindi" might suffice on its own.
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES
The translation "Жўнатиш" means "to send" (the infinitive form) in Uzbek, which does not accurately convey the past participle or passive sense implied by "Sent to." A more accurate translation for "Sent to" in this context would be "Жўнатилди" or "Жўнатилган," which better fit the past tense or passive voice suited for indicating something was sent to a recipient.

Correct translation:
Жўнатилди
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES  
The English word "Mined" in the context of Bitcoin refers to the process of creating new coins through mining, not "profit" or "gain". The provided translation "Фойда" means "profit" or "benefit", which is inaccurate here. A correct Uzbek translation for "Mined" in the Bitcoin context would be " qazilgan " (қазилган) or " qazish natijasida olingan ".  

Correct translation:  
<translation>Қазилган</translation>
```

```
        <source>Last month</source>
        <translation>Ўтган хафта</translation>
    
YES  
The translation "Ўтган хафта" means "Last week," which is incorrect for the source text "Last month." The correct translation should be:

Ўтган ой
```

```
        <source>Received with</source>
        <translation>Ёрдамида қабул қилиш</translation>
    
YES  
The translation "Ёрдамида қабул қилиш" is not an accurate or natural translation of "Received with." The phrase "Received with" in the Bitcoin context usually implies something like "qabul qilindi" (received) paired with a method or source, so the preposition "with" should be translated as "bilan" or "orqali," not "ёмдамида," which is also misspelled (correct is "ярдамида"). Additionally, the phrase structure is awkward and incomplete in Uzbek.

Correct translation:  
"Bilan qabul qilindi"  
or more naturally:  
"Qabul qilindi (bilan)" if context allows parentheses.  
If space is limited and context clear, "Qabul qilindi" might suffice on its own.
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES
The translation "Жўнатиш" means "to send" (the infinitive form) in Uzbek, which does not accurately convey the past participle or passive sense implied by "Sent to." A more accurate translation for "Sent to" in this context would be "Жўнатилди" or "Жўнатилган," which better fit the past tense or passive voice suited for indicating something was sent to a recipient.

Correct translation:
Жўнатилди
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES  
The English word "Mined" in the context of Bitcoin refers to the process of creating new coins through mining, not "profit" or "gain". The provided translation "Фойда" means "profit" or "benefit", which is inaccurate here. A correct Uzbek translation for "Mined" in the Bitcoin context would be " qazilgan " (қазилган) or " qazish natijasida olingan ".  

Correct translation:  
<translation>Қазилган</translation>
```

```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Hamyonni qayta yozish kerak: bajarish uchun 1%s ni qayta ishga tushiring</translation>
    
YES  
The translation incorrectly places the format specifier "1%s" instead of "%s" and the phrase "bajarish uchun" ("for execution") is not the best choice for "to complete" in this context. A more natural and accurate translation would be:  

Correct translation:  
Hamyonni qayta yozish kerak: jarayonni tugatish uchun %s ni qayta ishga tushiring
```
</details>
