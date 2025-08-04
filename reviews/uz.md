# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>uz</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Buz%5D%20low%20quality)


```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Noto'g'ri maxfiy so'z kiritildi</translation>
    
YES, The translation is missing the word "wallet" and the word "entered" from the original sentence. It also does not include the '%' format specifier, which is present in the original sentence.

Correct translation: <translation>Hamyonni dekriptlash uchun kiritilgan maxfiy so'z noto'g'ri.</translation>
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Hamyon shifrini ochish uchun parol iborasi noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas). Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating.
</translation>
    
YES, The translation has an accuracy issue. The phrase "up to — but not including — the first null character" was incorrectly translated as "faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas)", which translates to "please try again with only the devices up to the first null character (but not that thing)". The correct translation for this phrase would be "faqat birinchi null belgiga qadar bo'lgan belgilar bilan qayta urinib ko'ring". Additionally, "If this is successful, please set a new passphrase to avoid this issue in the future." was translated as "Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating.", which roughly translates to "If this happens, set a new password to get this problem." This also deviates from the original meaning. A more accurate translation would be "Agar bu muvaffaqiyatli bo'lsa, kelajakda bu muammoni oldini olish uchun yangi parol o'rnating."

Hamyon shifrini ochish uchun kiritilgan parol noto'g'ri. U null belgisini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgiga qadar bo'lgan belgilar bilan qayta urinib ko'ring (lekin shu belgini o'z ichiga olmagan holda). Agar bu muvaffaqiyatli bo'lsa, kelajakda bu muammoni oldini olish uchun yangi parol o'rnating.
```

```
        <source>Wallet passphrase was successfully changed.</source>
        <translation>Ҳамён пароли муваффақиятли алмаштирилди.</translation>
    
UNK_LANG
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Hamyon shifrini ochish uchun yordam eski parol noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas).</translation>
    
YES: The translation is problematic because the phrase "qurilmalar bilan qayta urinib ko'ring" translates to "try again with devices" which is not semantically correct in this context. The original English text refers to characters, not devices.

NO
```

```
        <source>Banned Until</source>
        <translation>gacha kirish taqiqlanadi</translation>
    
YES, The translation is inaccurate and doesn't convey the intended meaning of "Banned Until". The Uzbek translation translates to "Entrance is banned until", which is grammatically incorrect and doesn't make sense in the context of Bitcoin. A more appropriate translation would be "Ta'qiqlangan sanaguncha" or "Qo'yilgan muddatgacha taqiqlangan".

Correct Translation: Ta'qiqlangan sanaguncha
```

```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>Fatal xatolik yuz berdi. %1 xavfsiz ravishda davom eta olmaydi va tizimni tark etadi. </translation>
    
YES, The translation is problematic because the phrase "tizimni tark etadi" which translates to "will leave the system" is not a natural way to express that a program or process will quit in Uzbek. A more appropriate phrase would be "chiqib ketadi" which means "will exit" or "will quit".

NO
```

```
        <source>%1 m</source>
        <translation>%1 д</translation>
    
YES
The translation is incorrect and nonsensical. "%1 m" likely refers to a quantity of Bitcoin in millibits. The translation "%1 д" does not convey this meaning.

Correct translation: %1 m
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Паролни ўзгартириш ҳамённи кодлашда фойдаланилади</translation>
    
YES. The translation is inaccurate and grammatically incorrect. It translates to "Change the password that is used in wallet coding", which is a bit awkward. A more natural and accurate translation would be:

"hamyonni kodlash uchun ishlatiladigan parolni o'zgartiring"

This translates to "Change the password used for wallet encryption".
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>To'lovlarni so'rash(QR kolar va bitkoin yaratish: URL manzillar)</translation>
    
YES: The word order and conjunction are unnatural in the Uzbek translation. The format specifier "%" is missing and "QR kolar" is a misspelling of "QR kodlar". The term "bitkoin yaratish" is also awkward and doesn't accurately convey the meaning of generating Bitcoin URIs.

To'lovlarni so'rang (QR kodlar va bitkoin: URL manzilini hosil qiladi)
```

```
        <source>Ctrl+Q</source>
        <translation>formatini olib tashlash(Ctrl+Q)</translation>
    
YES, The translation is problematic as it incorrectly translates "Ctrl+Q" into a phrase that includes an action ("formatini olib tashlash") that is not present in the source text. The source text is a keyboard shortcut. The translation should ideally remain as the shortcut itself, or be translated as a shortcut if there's a commonly understood Uzbek equivalent for the action.

NO, formatini olib tashlash(Ctrl+Q)
```

```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
YES - The translation is completely nonsensical and irrelevant to the context of Bitcoin. It translates to "migrate pig fat" in Uzbek.
Correct translation: Hamyonni ko'chirish
```

```
        <source>Ctrl+M</source>
        <translation>Abzatsga chek qo'ying.(Ctrl+M)</translation>
    
YES, The translation is problematic because it misinterprets the source text. The source text is a keyboard shortcut "Ctrl+M". The translation explains what this shortcut does ("Abzatsga chek qo'ying." means "Insert checkmark to paragraph.") which is not the intended meaning. The translation should be a direct transliteration of the shortcut.
Abzatsga chek qo'ying.(Ctrl+M) -> Ctrl+M
```

```
        <source>Click for more actions.</source>
        <extracomment>A substring of the tooltip. "More actions" are available via the context menu.</extracomment>
        <translation>Ko'proq sozlamalar uchun bosing.</translation>
    
YES - The translation uses "sozlamalar" (settings) instead of "harkatlar" (actions). The correct translation should be "Ko'proq harakatlar uchun bosing.".
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Pirlar oynasini ko'rsatish</translation>
    
YES - The translation is incorrect. "Pirlar" does not translate to "Peers" in the context of Bitcoin. The correct translation should be "Tarp" or "Hamkorlar".
Tarp oynasini ko'rsatish
```

```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini cheklash</translation>
    
YES: The translation is inaccurate. The source text "Disable network activity" refers to disabling network communication, while the translation "Ijtimoiy tarmoq faoliyatini cheklash" means "Restrict social media activity". This is a misinterpretation of the context, which is about Bitcoin network activity.
Correct translation: Tarmoq faoliyatini o'chirib qo'yish
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini yoqish</translation>
    
YES: The translation appears to have misunderstood the meaning of "network activity" in the context of Bitcoin and has translated it as "social network activity" (Ijtimoiy tarmoq faoliyati). In the context of Bitcoin, "network activity" refers to the activity on the Bitcoin network itself, not social media.

Correct translation: Tarmoq faoliyatini yoqish
```

```
        <source>Copy fee</source>
        <translation>Narxni nusxalash</translation>
    
YES: The translation is inaccurate. "Copy fee" refers to copying a transaction fee, not copying the price.
Correct translation: To'lovni nusxalash
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
    
YES, The phrase "&lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak" was translated as "1-2.legacy.bak". The correct translation should be "&lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak".

Hamyonni ko'chirish ushbu hamyonni bir yoki bir nechta deskriptor hamyonga aylantiradi. Hamyonning yangi zaxira nusxasini yaratish kerak bo'ladi.
Agar bu hamyonda faqat tomosha skriptlari mavjud bo'lsa, yangi hamyon yaratiladi, unda faqat tomosha qilish uchun skriptlar mavjud.
Agar bu hamyonda echilishi mumkin bo'lgan, lekin tomosha qilinmagan skriptlar bo'lsa, ushbu skriptlarni o'z ichiga olgan boshqa va yangi hamyon yaratiladi.

Migratsiya jarayoni ko'chirishdan oldin hamyonning zaxira nusxasini yaratadi. Ushbu zaxira fayli &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak deb nomlanadi va uni ushbu hamyon katalogida topish mumkin. Noto'g'ri migratsiya bo'lsa, zaxira nusxasini "Hamyonni tiklash" funksiyasi bilan tiklash mumkin.
```

```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
YES - The translation is completely nonsensical and irrelevant to the context of Bitcoin. It translates to "migrate pig fat" in Uzbek.
Correct translation: Hamyonni ko'chirish
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Watchonly skriptlari nomli yangi hamyonga ko'chirildi%1</translation>
    
YES: The format specifier '%1' is misplaced in the translation.
Watchonly skriptlari "%1" nomli yangi hamyonga ko'chirildi.
```

```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Yechish mumkin bo'lgan, lekin ko'rilmagan skriptlar nomli yangi hamyonga o'tkazildi%1</translation>
    
YES - The translation is missing a period at the end of the sentence and has an extraneous space before "%1".
The correct translation is: "Yechish mumkin bo'lgan, lekin ko'rilmagan skriptlar nomli yangi hamyonga o'tkazildi %1."
```

```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Wallet tiklanmoqda&lt;b&gt;%1&lt;/b&gt;</translation>
    
YES, The translation is inaccurate. The Uzbek word "tiklanmoqda" means "being restored" or "recovering", but the context implies the wallet is being *restored* from a backup. The correct Uzbek word for "restoring" in this context is "tiklash" or "qayta tiklash". Also, "Wallet" should be translated as "Hamyon" or "Vestok".

Correct translation: Hamyonni tiklash&lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>Agar 'pruning' funksiyasi o'chirilgan bo'lsa, hamyondan uzoq vaqt foydalanmaslik butun zanjirnni qayta sinxronlashga olib kelishi mumkin.</translation>
    
YES, The translation contains an error in the conditional clause. The source states "if pruning is enabled", but the translation states "if pruning is disabled". The phrase "o'chirilgan bo'lsa" means "if disabled". The correct translation for "if pruning is enabled" is "agar 'pruning' funksiyasi yoqilgan bo'lsa".

NO
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Ushbu hamyon uchun maxfiy kalitlarni o'chirish. Maxfiy kalitsiz hamyonlar maxfiy kalitlar yoki import qilingan maxfiy kalitlar, shuningdek, HD seedlarga ega bo'la olmaydi.</translation>
    
YES, The translation is problematic because it incorrectly states that wallets with disabled private keys cannot have an HD seed or imported private keys. The original English text implies that disabling private keys is *ideal* for watch-only wallets, which typically do not need or have private keys, but it doesn't explicitly say that other wallets *cannot* have them. The translation also omits the phrase "or imported private keys" from the first part of the sentence.

Here's a more accurate translation:

Ushbu hamyon uchun maxfiy kalitlarni oʻchiring. Maxfiy kalitlari oʻchirilgan hamyonlarda maxfiy kalitlar boʻlmaydi va ular HD seed yoki import qilingan maxfiy kalitlarga ega boʻla olmaydi. Bu faqat kuzatuv uchun moʻljallangan hamyonlar uchun idealdir.
```

```
        <source>Make a blank wallet. Blank wallets do not initially have private keys or scripts. Private keys and addresses can be imported, or an HD seed can be set, at a later time.</source>
        <translation>Bo'sh hamyon yaratish. Bo'sh hamyonlarga keyinchalik maxfiy kalitlar yoki manzillar import qilinishi mumkin, yana HD seedlar ham o'rnatilishi mumkin.</translation>
    
YES: The translation uses "manzillar" (addresses) instead of the more specific term for Bitcoin addresses, "kripto manzillar" or "hissalarning manzillari", and it also omits the mention of "scripts". Additionally, the phrase "keyinchalik" (later) should be placed before "import qilinishi mumkin" (can be imported).

Bo'sh hamyon yaratish. Bo'sh hamyonlarda boshida maxfiy kalitlar yoki skriptlar mavjud emas. Maxfiy kalitlar va kripto manzillar keyinchalik import qilinishi mumkin, yoki HD urugʻi oʻrnatilishi mumkin.
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Yuboruvchi(%1manzil) va  qabul qiluvchi(%2manzil) bir xil bo'lishi mumkin emas</translation>
    
YES, The translation incorrectly identifies the roles of the two placeholders and their associated labels. The source text clearly states that address "%1" is a receiving address with label "%2", and it cannot be added as a *sending* address. The translation, however, implies that the "sender" and "receiver" addresses cannot be the same, which is a different statement. The word "manzil" (address) is also used incorrectly with the placeholders.

Correct translation:
"%1 manzil "%2" yorlig'i bilan qabul qiluvchi manzil sifatida allaqachon mavjud, shuning uchun u yuboruvchi manzil sifatida qo'shilmaydi."
```

```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>Kiritilgan %1manzil allaqachon %2yorlig'i bilan manzillar kitobida</translation>
    
YES, The translation has a word order issue and lacks proper punctuation.
Kiritilgan "%1" manzili allaqachon "%2" yorlig'i bilan manzillar kitobida mavjud.
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>OK ni bosganingizda, %1to'liq blok zanjirini (%2GB) yuklab olish%4 va qayta ishlash boshlanadi, %3birinchi boshlangan%4 tranzaksiyalardan boshlab.</translation>
    
YES: The translation is missing the word "block chain" in the second part of the sentence. Also, the word order is a bit unnatural.
OK ni bosganingizda, %1 to'liq %4 blok zanjirini (%2 GB) yuklab olish va qayta ishlashni boshlaydi, %3 %4 dastlab ishga tushirilganda eng qadimgi tranzaksiyalardan boshlab.
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Noma'lum. Sarlavhalarni oldindan sinxronlash (, %1%2%)…</translation>
    
YES, The translation erroneously places the "%1" format specifier after the comma, whereas it should be before it. The "%2" format specifier is also incorrectly placed.
Noma'lum. Sarlavhalarni oldindan sinxronlash (%1, %2%)…
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Manzilni qo'shib qo'yish</translation>
    
YES: The translation is too literal and doesn't convey the intended meaning of pasting an address from the clipboard. The current translation "Manzilni qo'shib qo'yish" means "Add address" which is not the same as pasting from the clipboard.

Correct translation: "Qo'shilgan manzilni joylashtirish"
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi. Barcha bloklar hali ham to'liq tasdiqlangan. Bu sozlamani qaytarish butun blok zanjirini qayta yuklab olishni talab qiladi.</translation>
    
YES: The word "Do'kon" translates to "shop" or "store" in English, which is not relevant to the context of Bitcoin. The correct translation should focus on the concept of storage space.
Correct translation: Pruning-ni yoqish tranzaksiyalarni saqlash uchun zarur bo'lgan disk maydonini sezilarli darajada kamaytiradi. Barcha bloklar hali ham to'liq tasdiqlangan. Bu sozlamani qaytarish butun blok zanjirini qayta yuklab olishni talab qiladi.
```

```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>Chegirma to'lovini standart qilib belgilash kerakmi yoki yo'qmi?</translation>
    
YES - The translation uses "Chegirma" which means "discount" or "rebate" in Uzbek. The English word "fee" in the context of Bitcoin transactions refers to the transaction fee. Therefore, the translation is inaccurate. The correct translation should reflect the concept of a fee being subtracted from the amount.

NO
```

```
        <source>Subtract fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Standart bo'yicha chegirma belgilash</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning of the source text. The source text refers to "subtracting the fee from the amount by default," whereas the translation "Standart bo'yicha chegirma belgilash" means "Set discount by default." The term "chegirma" (discount) is incorrect in this context, and the verb "belgilash" (to set) does not accurately reflect "subtract."

Here's the correct translation:

Standart bo'yicha miqdordan to'lovni ayirib tashlash
```

```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>Прокси порти (e.g. 9050)</translation>
    
YES - The Uzbek translation uses a plural form "pport" instead of a singular form. The correct translation should be "Прокси порти (e.g. 9050)".
```

```
        <source>Show tray icon</source>
        <translation> belgisini ko'rsatish</translation>
    
YES: The translation is missing a word. It should be "tray belgisini ko'rsatish".
tray belgisini ko'rsatish
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>Манзиллар панели ўрнига трэйни йиғиш</translation>
    
YES. The translation is problematic. The English source text is about minimizing a window to the system tray, not about "addresses" or a "tray" in the sense of the taskbar. The word "Manzil" (address) is a mistranslation and makes the sentence nonsensical in the given context.

Correct translation: Трэйга эмас, иш столининг ўнг пастки бурчагига йиғиш.
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Жами ўтказмалар ҳозиргача тасдиқланган ва сафланадиган баланс томонга ҳали ҳам ҳисобланмади</translation>
    
YES: The translation is inaccurate and grammatically incorrect. The phrase "сафланадиган баланс томонга ҳали ҳам ҳисобланмади" translates to "have not yet been counted towards the balance", which is the opposite of what the source text conveys.

Correct translation: Жами тасдиқланмаган транзакциялар, улар ҳали сарфланадиган балансга киритилмаган.
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarni qaytarish uchun Sozlamalar-&gt;Qiymatlar.</translation>
    
YES. The translation is missing the final part of the instruction in the source text, which is "Mask values". This makes the instruction incomplete and potentially confusing for the user.

"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarni qaytarish uchun Sozlamalar-&gt;Qiymatlarni yashirishni bekor qiling.
```

```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>Hamyon maʼlumotlarga imzo qoʻyib boʻlmaydi.</translation>
    
YES
The translation is inaccurate and omits crucial information. The English sentence indicates that signing inputs is impossible *because* the wallet is locked. The Uzbek translation only states that signing inputs is impossible without providing the reason. Additionally, the phrase "maʼlumotlarga" (to data) is too general and doesn't convey the specific meaning of "inputs" in the context of Bitcoin transactions.

Correct translation:
<translation>Hamyon qulflangan holda kiritmalar imzolana olmadi.</translation>
```

```
        <source>URI handling</source>
        <translation>URI осилиб қолмоқда</translation>
    
YES, The translation is grammatically incorrect and does not convey the intended meaning. The phrase "URI осилиб қолмоқда" translates to "The URI is hanging/stuck". The correct translation should be "URI bilan ishlash" which means "Handling URI".

Correct translation: URI bilan ishlash
```

```
        <source>Client version</source>
        <translation>Мижоз номи</translation>
    
YES - The translation of "Client version" to "Мижоз номи" (Client name) is incorrect. The correct translation for "Client version" in Uzbek is "Mijoz versiyasi".
Mijoz versiyasi
```

```
        <source>Open</source>
        <translation>Очиш</translation>
    
YES, The translation is incorrect and does not convey the meaning of "Open" in the context of Bitcoin. The provided Uzbek word "Очиш" means "to open" or "to clean", which is not appropriate here. The correct translation for "Open" in this context would be "Ochish" which means "to open".

NO
```

```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>Хоҳланган миқдор сўрови. Кўрсатилган миқдорни сўраш учун буни бўш ёки ноль қолдиринг.</translation>
    
YES, The translation is inaccurate and doesn't convey the intended meaning. The Uzbek translation uses "Хоҳланган миқдор сўрови" which translates to "Requested amount request", which is redundant. Additionally, "Кўрсатилган миқдорни сўраш учун буни бўш ёки ноль қолдиринг" translates to "Leave this empty or zero to request the specified amount", which is also not the correct meaning of the source text "Leave this empty or zero to not request a specific amount."

NO, The translation is unproblematic.
```

```
        <source>Copy Address</source>
        <translation>Нусҳалаш  Манзил</translation>
    
YES, The provided translation is problematic because it contains an unnecessary space between "Нусҳалаш" and "Манзил".

Correct translation: Нусҳалаш Манзил
```

```
        <source>Request payment to %1</source>
        <translation> %1 дан Тўловни сўраш</translation>
    
YES, The word order in the Uzbek translation is incorrect. The correct translation should place "Тўловни сўраш" (Request payment) at the end of the sentence.
%1 дан Тўловни сўраш
```

```
        <source>Insufficient funds!</source>
        <translation>Кам миқдор</translation>
    
YES, The translation is inaccurate and incomplete. The English phrase "Insufficient funds!" implies a lack of money, while the Uzbek translation "Кам миқдор" literally means "small amount" or "little amount". A more accurate translation would convey the idea of not having enough funds.

Correct translation: Pul mablag'i yetarli emas!
```

```
        <source>Custom change address</source>
        <translation>Бошқа ўзгартирилган манзил</translation>
    
YES, The translation is inaccurate. The source text "Custom change address" refers to a Bitcoin address that is specifically designated for receiving the "change" amount from a Bitcoin transaction. The provided Uzbek translation "Бошқа ўзгартирилган манзил" is a literal translation of "Another changed address" and does not convey the correct meaning in the context of Bitcoin.

A more accurate translation would be:
Custom change address = Maxsus o'zgaruvchan manzil
```

```
        <source>Copy fee</source>
        <translation>Narxni nusxalash</translation>
    
YES: The translation is inaccurate. "Copy fee" refers to copying a transaction fee, not copying the price.
Correct translation: To'lovni nusxalash
```

```
        <source>Warning: Unknown change address</source>
        <translation>Диққат: Номаълум ўзгариш манзили</translation>
    
YES, The translation is problematic because it uses "manzil" which is a general word for address, but in the context of Bitcoin, it should be more specific to wallet address or transaction address. Also, "o'zgarish" means change in a general sense, not specifically "change amount" in a Bitcoin transaction.

The correct translation should be:
"Diqqat: Nomа'lum o'zgarish manzili" (Warning: Unknown change address)
```

```
        <source>Paste address from clipboard</source>
        <translation>Manzilni qo'shib qo'yish</translation>
    
YES, The translation is inaccurate and problematic because it conveys the wrong meaning. The source text "Paste address from clipboard" means to insert an address from the clipboard. The translation "Manzilni qo'shib qo'yish" means "Adding the address", which is not the intended meaning.

NO
```

```
        <source>Paste address from clipboard</source>
        <translation>Manzilni qo'shib qo'yish</translation>
    
YES, The translation is inaccurate and problematic because it conveys the wrong meaning. The source text "Paste address from clipboard" means to insert an address from the clipboard. The translation "Manzilni qo'shib qo'yish" means "Adding the address", which is not the intended meaning.

NO
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/тасдиқланмади</translation>
    
YES, The Uzbek translation for "unconfirmed" is incorrect. The provided translation "tasdiqlanmadi" means "not confirmed" which is not the correct context for the status of a Bitcoin transaction. The correct translation should be "kutilmoqda" or "tasdiqlanmoqda" which means "pending" or "confirming".

NO
```

```
        <source>Credit</source>
        <translation>Кредит (қарз)</translation>
    
YES, The translation is problematic because it is too literal and doesn't accurately convey the meaning of "Credit" in the context of Bitcoin transactions. In Bitcoin, "credit" typically refers to receiving funds, not taking a loan. The Uzbek translation provided ("Кредит (қарз)") directly translates to "Credit (loan)", which is misleading. A more appropriate translation would reflect the act of receiving funds.

Correct translation: Ҳисобга кирим
```

```
        <source>true</source>
        <translation>рост</translation>
    
YES
The translation of "true" to "рост" (growth) is incorrect in the context of Bitcoin. "True" in a Bitcoin context typically refers to a boolean value indicating a condition is met. The correct translation would be "ҳақиқат" or a similar term for truth.

ҳақиқат
```

```
        <source>Received with</source>
        <translation>Ёрдамида қабул қилиш</translation>
    
YES: The translation is inaccurate and unnatural. The phrase "Received with" in the context of Bitcoin typically refers to receiving funds through a specific method or channel, not just receiving with "help" or "aid".

Correct translation: "Bilans qabul qilindi" or "Qabul qilindi" (if the "with" implies a method not explicitly stated). Given the context of Bitcoin, a more specific translation might be needed depending on what "with" refers to. However, the provided translation is definitely incorrect.

NO
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES, The translation is incorrect and does not convey the intended meaning of "Sent to". The Uzbek word "Жўнатиш" means "to send" or "sending" (gerund/infinitive), not a recipient.

The correct translation should indicate the recipient of the Bitcoin. A more appropriate translation in this context would be:

<translation>Юборилган манзил</translation>
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES
The translation is incorrect and misleading in the context of Bitcoin mining. "Mined" in Bitcoin refers to the process of creating new blocks and earning rewards, not "profit."

Correct translation: Kon qazib olindi
```

```
        <source>Last month</source>
        <translation>Ўтган хафта</translation>
    
YES: The translation incorrectly states "last week" instead of "last month".
Correct translation: Ўтган ой
```

```
        <source>Received with</source>
        <translation>Ёрдамида қабул қилиш</translation>
    
YES: The translation is inaccurate and unnatural. The phrase "Received with" in the context of Bitcoin typically refers to receiving funds through a specific method or channel, not just receiving with "help" or "aid".

Correct translation: "Bilans qabul qilindi" or "Qabul qilindi" (if the "with" implies a method not explicitly stated). Given the context of Bitcoin, a more specific translation might be needed depending on what "with" refers to. However, the provided translation is definitely incorrect.

NO
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES, The translation is incorrect and does not convey the intended meaning of "Sent to". The Uzbek word "Жўнатиш" means "to send" or "sending" (gerund/infinitive), not a recipient.

The correct translation should indicate the recipient of the Bitcoin. A more appropriate translation in this context would be:

<translation>Юборилган манзил</translation>
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES
The translation is incorrect and misleading in the context of Bitcoin mining. "Mined" in Bitcoin refers to the process of creating new blocks and earning rewards, not "profit."

Correct translation: Kon qazib olindi
```

```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Hamyonni qayta yozish kerak: bajarish uchun 1%s ni qayta ishga tushiring</translation>
    
YES: The format specifier "%s" was incorrectly translated to "1%s".
Hamyonni qayta yozish kerak: bajarish uchun %s ni qayta ishga tushiring
```
</details>
