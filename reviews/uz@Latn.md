# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>uz@Latn</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Buz@Latn%5D%20low%20quality)


```
        <source>Copy Address</source>
        <translation>Manzillarni nusxalash</translation>
    
YES, The translation is problematic. The word "address" is translated as "Manzillarni" which means "addresses" (plural). The source text is in singular form ("Address").

Manzilni nusxalash
```

```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>MUHIM: Hamyon faylingizning oldingi nusxalari yangi fayl, shifrlangan hamyoni bilan almashtirilishi kerak. masalalik nuqtai nazaridan, shifrlanmagan hamyon faylining oldingi nusxalari yangi, shifrlangan hamyondan yuklashning yangilanishi bilanoq foydasiz bo'ladi.</translation>
    
YES: The translation is grammatically incorrect and contains awkward phrasing. Specifically, "masalalik nuqtai nazaridan" is not a standard Uzbek phrase for "for security reasons," and the latter part of the sentence is convoluted.

MUHIM: Sizning hamyon faylingizning oldingi zaxira nusxalari yangi yaratilgan, shifrlangan hamyon fayli bilan almashtirilishi kerak. Xavfsizlik sabablarga ko'ra, shifrlanmagan hamyon faylining oldingi zaxira nusxalari, yangi shifrlangan hamyondan foydalanishni boshlaganingizdan so'ng foydasiz bo'ladi.
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Noto'g'ri maxfiy so'z kiritildi</translation>
    
YES: The translation is missing the word "wallet" and the word "decryption". It also includes an extra "g" at the end of the word "kiritildi".

Correct translation: Sizning hamyoningizni shifrlash uchun kiritgan parolingiz noto'g'ri.
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Hamyon shifrini ochish uchun parol iborasi noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas). Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating.
</translation>
    
YES: The translation is inaccurate and nonsensical. Specifically, the phrase "hamma belgilargacha bo'lgan qurilmalar bilan" (meaning "with devices up to all characters") is incorrect and does not convey the intended meaning of "characters up to". Additionally, "agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating" (meaning "if this is an event, set a new password to get this problem") is also a mistranslation.

Correct translation: Hamyon shifrini ochish uchun kiritilgan parolda xatolik bor. Unga null belgisi (ya'ni - nol bayt) kirgan. Agar parol ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasi bilan o'rnatilgan bo'lsa, iltimos, birinchi null belgidan oldingi belgilar bilan qayta urinib ko'ring. Agar bu muvaffaqiyatli bo'lsa, kelajakda ushbu muammoni oldini olish uchun yangi parol o'rnating.
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Hamyon shifrini ochish uchun yordam eski parol noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas).</translation>
    
YES - The translation inaccurately states "qurilmalar bilan" which translates to "with devices" instead of "with characters".

Hamyon shifrini ochish uchun kiritilgan eski parol noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol ushbu dasturiy ta'minotning 25.0 versiyasidan oldingi versiyasi bilan o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgidan oldingi belgilarni kiriting.
```

```
        <source>Banned Until</source>
        <translation>gacha kirish taqiqlanadi</translation>
    
YES, the translation is problematic due to accuracy issues. The provided translation "gacha kirish taqiqlanadi" means "entry is prohibited until" which is not an accurate translation of "Banned Until".

A more accurate translation for "Banned Until" in the context of Bitcoin, implying a ban on an account or address, would be:

"gacha taqiqlangan"
```

```
        <source>Runaway exception</source>
        <translation>qo'shimcha istisno</translation>
    
YES, The translation is inaccurate and does not convey the meaning of "Runaway exception" in the context of Bitcoin. The Uzbek translation "qo'shimcha istisno" means "additional exception," which is not related to the concept of an uncontrolled or unexpected exception that can occur in software.

A more appropriate translation would be:

"cheklanmagan istisno" or "nazoratsiz istisno"
```

```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>Fatal xatolik yuz berdi. %1 xavfsiz ravishda davom eta olmaydi va tizimni tark etadi. </translation>
    
YES, The word "tizimni" means "system" in English, which is not present in the source text. The correct translation should be: A fatal error occurred. %1 can no longer continue safely and will quit.

Fatal xatolik yuz berdi. %1 xavfsiz ravishda davom eta olmaydi va chiqadi.
```

```
        <source>%1 m</source>
        <translation>%1 д</translation>
    
YES, The translation is problematic because it is inaccurate and nonsensical. The source text "%1 m" likely refers to "%1 million" in the context of Bitcoin, where "m" is a common abbreviation. The Uzbek translation "%1 д" does not convey this meaning. The character "д" in Uzbek does not represent "million". Furthermore, in Uzbek, the abbreviation for million is "mln" or "m" can be used in specific contexts but not with the Uzbek Cyrillic "д".

A more accurate translation would be:

<source>%1 m</source>
<translation>%1 mln</translation>
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Паролни ўзгартириш ҳамённи кодлашда фойдаланилади</translation>
    
YES
The translation is inaccurate and doesn't convey the original meaning. The word "Change" is translated as "ўзгартириш", which means "change" in the sense of a noun, not a verb. Also, the structure of the sentence is incorrect in Uzbek.

Correct translation: "Hammni kodlashda ishlatiladigan parol o'rnini boshing" or "Hamyonni kodlash uchun ishlatiladigan parolni o'zgartiring".
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>To'lovlarni so'rash(QR kolar va bitkoin yaratish: URL manzillar)</translation>
    
YES: The translation is inaccurate and contains erroneous content. The phrase "bitkoin yaratish: URL manzillar" translates to "create bitcoin: URL addresses," which is grammatically incorrect and doesn't convey the intended meaning of generating Bitcoin URIs. The word "kolar" is also a misspelling of "kodlar" (codes).

Correct translation: To'lovlarni so'rash (QR kodlar va bitcoin: URI manzillarini yaratadi)
```

```
        <source>Ctrl+Q</source>
        <translation>formatini olib tashlash(Ctrl+Q)</translation>
    
YES - The translation is inaccurate and does not convey the intended meaning. The English text "Ctrl+Q" is a keyboard shortcut, whereas the translation suggests a function to remove formatting.

Correct translation: Ctrl+Q
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Nusxalanganlar qisman signlangan Bitkoin tranzaksiyalarini yuklash</translation>
    
YES - The translation is grammatically incorrect and awkward. The word "Nusxalanganlar" means "copied ones" and is out of place here.

Correct translation: Bir qism signallangan Bitcoin operatsiyasini buferdan yuklash
```

```
        <source>%1 client</source>
        <translation>%1 mijoz </translation>
    
YES, The translation contains an extra space before the translated word.
%1 mijoz
```

```
        <source>Click for more actions.</source>
        <extracomment>A substring of the tooltip. "More actions" are available via the context menu.</extracomment>
        <translation>Ko'proq sozlamalar uchun bosing.</translation>
    
YES, The translation is inaccurate and misleading. "Sozlamalar" means "settings" in Uzbek, not "actions". The correct translation for "more actions" in this context would be "ko'proq harakatlar".

NO
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Pirlar oynasini ko'rsatish</translation>
    
YES, The translation contains a misspelling of "Peers" in Uzbek. "Pirlar" should be "Peerlar".

Pirlar oynasini ko'rsatish
```

```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini cheklash</translation>
    
YES: The translation is incorrect. "Ijtimoiy tarmoq" means "social network", not "network" in general. The correct translation for "Disable network activity" in the context of Bitcoin would be "Tarmoq faoliyatini oʻchirish".
Tarmoq faoliyatini oʻchirish
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini yoqish</translation>
    
YES: The translation is incorrect. "network activity" is translated as "social network activity".
Correct translation: Tarmoq faoliyatini yoqish
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>HD kalit yaratish &lt;b&gt;imkonsiz&lt;/b&gt;</translation>
    
YES, The word "imkonsiz" means impossible, but it should be disabled. The correct translation is "yoqilgan" which means disabled.
HD kalit yaratish &lt;b&gt;yoqilgan&lt;/b&gt;
```

```
        <source>change from %1 (%2)</source>
        <translation>%1(%2) dan o'zgartirish</translation>
    
YES, The translation is inaccurate and confusing. The word "o'zgartirish" translates to "change" in the sense of alteration or modification, not as the change amount in a Bitcoin transaction. The correct translation should reflect the financial aspect of "change". Additionally, the placement of "%1(%2)" before "dan" is grammatically awkward.

NO, %1 (%2) dan o'zgartirish
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
    
YES, The translation contains an error in translating the filename format specifier.
Hamyonni ko'chirish ushbu hamyonni bir yoki bir nechta deskriptor hamyonga aylantiradi. Hamyonning yangi zaxira nusxasini yaratish kerak bo'ladi.
Agar bu hamyonda faqat tomosha skriptlari mavjud bo'lsa, yangi hamyon yaratiladi, unda faqat tomosha qilish uchun skriptlar mavjud.
Agar bu hamyonda echilishi mumkin bo'lgan, lekin tomosha qilinmagan skriptlar bo'lsa, ushbu skriptlarni o'z ichiga olgan boshqa va yangi hamyon yaratiladi.

Migratsiya jarayoni ko'chirishdan oldin hamyonning zaxira nusxasini yaratadi. Ushbu zaxira fayli &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak deb nomlanadi va uni ushbu hamyon katalogida topish mumkin. Noto'g'ri migratsiya bo'lsa, zaxira nusxasini "Hamyonni tiklash" funksiyasi bilan tiklash mumkin.
```

```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
YES: The translation is nonsensical and inaccurate. "Migrate Wallet" in the context of Bitcoin refers to moving a wallet to a new location or device. The provided Uzbek translation translates to "migrate pork fat," which is completely unrelated and problematic.

Correct translation: "Hamyonni ko'chirish"
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Watchonly skriptlari nomli yangi hamyonga ko'chirildi%1</translation>
    
YES, The translation is problematic because it is missing a space between "ko'chirildi" and "%1".
Watchonly skriptlari nomli yangi hamyonga ko'chirildi %1
```

```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Yechish mumkin bo'lgan, lekin ko'rilmagan skriptlar nomli yangi hamyonga o'tkazildi%1</translation>
    
YES, The translation is missing the wallet name in the sentence. The %1 placeholder should be at the end of the sentence and contain the wallet name.
Yechish mumkin bo'lgan, lekin ko'rilmagan skriptlar '%1' nomli yangi hamyonga o'tkazildi.
```

```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Wallet tiklanmoqda&lt;b&gt;%1&lt;/b&gt;</translation>
    
YES, The Uzbek translation is inaccurate and does not convey the intended meaning of the English source text. The word "tiklanmoqda" translates to "being clicked" or "being tapped," which is not the correct term for "restoring" a wallet.

Restoring a wallet implies recovering access to funds or wallet data, typically by using a seed phrase or backup.

A more appropriate translation would be:

Walletni tiklash jarayoni davom etmoqda &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Ushbu hamyon uchun maxfiy kalitlarni o'chirish. Maxfiy kalitsiz hamyonlar maxfiy kalitlar yoki import qilingan maxfiy kalitlar, shuningdek, HD seedlarga ega bo'la olmaydi.</translation>
    
YES, The translation is inaccurate and misses a key part of the original meaning. It incorrectly states that "Wallets with private keys disabled will have no private keys" which is redundant and doesn't fully convey the implications for HD seeds and imported private keys. The original states these are *not* possible, not that they "cannot have".

The corrected translation should be: "Ushbu hamyon uchun maxfiy kalitlarni oʻchiring. Maxfiy kalitlari oʻchirilgan hamyonlarda maxfiy kalitlar boʻlmaydi va ular HD seed yoki import qilingan maxfiy kalitlarga ega boʻla olmaydi. Bu faqat kuzatuvchi hamyonlar uchun idealdir."
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Yuboruvchi(%1manzil) va  qabul qiluvchi(%2manzil) bir xil bo'lishi mumkin emas</translation>
    
YES - The translation is inaccurate and nonsensical. It incorrectly states that sending and receiving addresses cannot be the same, which is false. The original English clearly states that an address already exists as a *receiving* address with a label, and therefore cannot be added as a *sending* address. The translation also misinterprets the format specifiers and adds unnecessary formatting.

Correct translation: "Manzil "%1" allaqachon "%2" yorligʻi bilan qabul qiluvchi manzil sifatida mavjud, shuning uchun uni yuboruvchi manzil sifatida qoʻshib boʻlmaydi."
```

```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>Kiritilgan %1manzil allaqachon %2yorlig'i bilan manzillar kitobida</translation>
    
YES, The translation is grammatically incorrect and misses the intended meaning. The phrase "Kiritilgan %1manzil" should be "Kiritilgan %1 manzili" to correctly indicate "The entered address %1". Also, "allaqachon %2yorlig'i bilan manzillar kitobida" should be "allaqachon %2 yorlig'i bilan manzillar kitobida mavjud" to properly convey "is already in the address book with label %2".

Kiritilgan %1 manzili allaqachon %2 yorlig'i bilan manzillar kitobida mavjud.
```

```
        <source>%1 will download and store a copy of the Bitcoin block chain.</source>
        <translation> Bitcoin blok zanjirining%1 nusxasini yuklab oladi va saqlaydi</translation>
    
YES, The word order in the Uzbek translation is incorrect. The correct translation should be: %1 Bitcoin blok zanjirining nusxasini yuklab oladi va saqlaydi.
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>OK ni bosganingizda, %1to'liq blok zanjirini (%2GB) yuklab olish%4 va qayta ishlash boshlanadi, %3birinchi boshlangan%4 tranzaksiyalardan boshlab.</translation>
    
YES: The translation has several errors. The word "to" appears to be a typo or an extra word. The phrase " Yuklab olish%4 va qayta ishlash boshlanadi" seems to be missing some words and the placement of "%4" is incorrect. The phrase " birinchi boshlangan%4 tranzaksiyalardan boshlab" is also grammatically incorrect and misplaced.

Correct translation: OK ni bosganingizda, %1 %4 blok zanjirini (%2 GB) yuklab olish va qayta ishlashni %3 birinchi boshlanganidan %4 dastlab ishga tushirilganda tranzaksiyalardan boshlab boshlaydi.
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Noma'lum. Sarlavhalarni oldindan sinxronlash (, %1%2%)…</translation>
    
YES. The translation is missing a space between %1 and %2%.
Noma'lum. Sarlavhalarni oldindan sinxronlash (%1, %2%)…
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Manzilni qo'shib qo'yish</translation>
    
YES: The translation is inaccurate and does not convey the intended meaning of pasting an address from the clipboard. It translates to "Add address" which is incorrect.

Correct translation: Manzilni joylashtiring
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi. Barcha bloklar hali ham to'liq tasdiqlangan. Bu sozlamani qaytarish butun blok zanjirini qayta yuklab olishni talab qiladi.</translation>
    
YES - The translation incorrectly uses the word "Do'kon" (shop/store) instead of "disk space" or a similar term. The phrase "xotirada joy kamayishiga" (reduction in memory space) is also a bit awkward and could be more direct.

Correct translation: Disk maydonini tejash uchun pruningni yoqish tranzaksiyalarni saqlash uchun zarur bo'lgan disk maydonini sezilarli darajada kamaytiradi. Barcha bloklar hali ham to'liq tasdiqlanadi. Bu sozlamani o'zgartirish butun blok zanjirini qayta yuklab olishni talab qiladi.
```

```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>Skriptni tekshirish ip lari sonini belgilang. </translation>
    
YES - The translation is incomplete and misses a significant part of the original sentence. Additionally, the term "ip" is not appropriate in this context.
Correct translation: Skriptni tekshirish ip lari sonini belgilang. Manfiy qiymatlar tizim uchun bo'sh qoldirmoqchi bo'lgan yadro soniga mos keladi.
```

```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>Chegirma to'lovini standart qilib belgilash kerakmi yoki yo'qmi?</translation>
    
YES - The Uzbek translation is inaccurate and conveys a different meaning than the English source text. The source text is about setting a default option to subtract a fee from an amount. The translation, however, seems to be about setting a discount as a standard.

Correct translation: To'lovni miqdordan chegirib tashlashni standart sifatida belgilash kerakmi yoki yo'qmi.
```

```
        <source>Subtract fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Standart bo'yicha chegirma belgilash</translation>
    
YES - The translation is inaccurate. The source text "Subtract fee from amount by default" implies that the fee will be subtracted from the total amount. The provided translation "Standart bo'yicha chegirma belgilash" translates to "Set discount by default," which is a different meaning.

Correct translation: Standart bo'yicha miqdordan to'lovni chegirib tashlash
```

```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>Прокси порти (e.g. 9050)</translation>
    
YES - The translation has a grammatical error and should be corrected to convey the intended meaning accurately. The word "Proksi" should be in the singular form.

Correct translation: Proksi porti (e.g. 9050)
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>Манзиллар панели ўрнига трэйни йиғиш</translation>
    
YES - The translation uses "Манзиллар панели" which translates to "address bar" or "panel of addresses" and is not contextually appropriate for "taskbar". The correct translation for taskbar in this context would be "вазифалар панели".

NO
```

```
        <source>none</source>
        <translation>йўқ</translation>
    
YES
The translation is incorrect. The Uzbek word "йўқ" means "no" or "none" in a general sense, but in the context of Bitcoin, a more appropriate translation for "none" when referring to an address or change would be "mavjud emas" (not available) or "bo'sh" (empty), depending on the specific context. Without more context, it's difficult to provide a definitive correction, but "йўқ" is not the best fit.

A more contextually appropriate translation would be:
<translation>mavjud emas</translation>
```

```
        <source>This change would require a client restart.</source>
        <translation>Ушбу ўзгариш мижозни қайтадан ишга туширишни талаб қилади.</translation>
    
UNK_LANG
```

```
        <source>Watch-only:</source>
        <translation>Фақат кўришга</translation>
    
YES - The translation is in Cyrillic script, but the target language specified is 'uz@Latn' which indicates Latin script. The translation also uses a word that means "only to see" which is not the standard translation for "watch-only" in the context of Bitcoin.
The correct translation should be: "Faqat koʻrish uchun"
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Жами ўтказмалар ҳозиргача тасдиқланган ва сафланадиган баланс томонга ҳали ҳам ҳисобланмади</translation>
    
YES: The translation uses an incorrect word for "spendable". The word "сафланадиган" means "aligning" or "in a line" which is not related to "spendable". A better translation for "spendable" in this context would be "сарфланиши мумкин бўлган".
NO
```

```
        <source>Immature:</source>
        <translation>Тайёр эмас:</translation>
    
YES. The translation uses Cyrillic script, but the target language is specified as 'uz@Latn', which indicates Latin script. The correct translation should be in Latin script.

YES. Тaйёр эмас: -> Tayyor emas:
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarni qaytarish uchun Sozlamalar-&gt;Qiymatlar.</translation>
    
YES, The translation is missing the word "ni" after "Qiymatlar" which makes the sentence incomplete. The correct translation should be "Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarni qaytarish uchun Sozlamalar-&gt;Qiymatlar ni belgisini olib tashlang.
```

```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>Hamyon maʼlumotlarga imzo qoʻyib boʻlmaydi.</translation>
    
YES: The translation is incomplete. It should include the word "locked" to accurately convey the meaning of the original English sentence.
Correct translation: Hamyon qulflangan vaqtda kirishlarga imzo qoʻyib boʻlmaydi.
```

```
        <source>URI handling</source>
        <translation>URI осилиб қолмоқда</translation>
    
YES, The translation is erroneous. The English source "URI handling" refers to the way Uniform Resource Identifiers are processed or managed. The provided Uzbek translation "URI осилиб қолмоқда" means "The URI is hanging/freezing," which implies a problem with the URI itself rather than the handling of it.

A more accurate translation for "URI handling" in the context of Bitcoin or general computing would be related to how URIs are managed or processed.

Correct translation: URIlarni boshqarish
```

```
        <source>Type</source>
        <extracomment>Title of Peers Table column which describes the type of peer connection. The "type" describes why the connection exists.</extracomment>
        <translation>Тури</translation>
    
YES - The translation is incorrect. The correct translation for "Type" in this context would be "Turi".
NO
```

```
        <source>Inbound</source>
        <extracomment>An Inbound Connection from a Peer.</extracomment>
        <translation>Ички йўналиш</translation>
    
YES: The translation is incorrect. "Ички йўналиш" means "Internal direction" or "Internal route", which is not the correct translation for "Inbound" in the context of Bitcoin peer connections. The correct translation should convey the idea of incoming or arriving.
NO
```

```
        <source>Client version</source>
        <translation>Мижоз номи</translation>
    
YES: The translation is inaccurate. "Client version" should be translated as "Mijoz versiyasi". The current translation "Мижоз номи" means "Client name".
Mijoz versiyasi
```

```
        <source>Open</source>
        <translation>Очиш</translation>
    
YES, The provided translation is incorrect. The source text "Open" should be translated to "Ochish" in Uzbek Latin script.
NO
```

```
        <source>Clear console</source>
        <translation>Терминални тозалаш</translation>
    
UNK_LANG
```

```
        <source>In:</source>
        <translation>Ичига:</translation>
    
YES - The provided translation is incorrect. The Uzbek word for "in" is "kirish" or "ichiga" if referring to something being inside. The provided translation "Ичига:" uses Cyrillic script, not Latin script as specified by 'uz@Latn'. Additionally, the context of Bitcoin suggests "In:" might refer to an input address or transaction. A more appropriate translation for "In:" in this context would be "Kirish:" or "Qabul qilish:" (for receiving).

Correct translation: Kirish:
```

```
        <source>To</source>
        <translation>Га</translation>
    
YES: The translation is incorrect and nonsensical. The Uzbek word for "To" is "Ga" or "gacha".
Ga
```

```
        <source>From</source>
        <translation>Дан</translation>
    
YES: The translation is incorrect. The Uzbek word for "From" is "Dan" or "dan" depending on context. However, the provided translation "Дан" is an archaic spelling. The correct translation is "dan".
From: dan
```

```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>Хоҳланган миқдор сўрови. Кўрсатилган миқдорни сўраш учун буни бўш ёки ноль қолдиринг.</translation>
    
YES - The translation contains Russian words ("Хоҳланган", "миқдор", "сўрови", "Кўрсатилган", "миқдорни", "сўраш", "учун", "буни", "бўш", "ёки", "ноль", "қолдиринг") which are not part of the Uzbek language (uz@Latn).

Correct translation: "So'raladigan ixtiyoriy miqdor. Ma'lum bir miqdorni so'ramoqchi bo'lsangiz, bo'sh yoki nol qoldiring."
```

```
        <source>Copy Address</source>
        <translation>Нусҳалаш  Манзил</translation>
    
YES, The translation contains extra whitespace.
Copy Address
```

```
        <source>Request payment to %1</source>
        <translation> %1 дан Тўловни сўраш</translation>
    
YES: The translation includes an incorrect character ("Т") and the word order is unnatural for the intended meaning.
Request payment to %1 -> %1 ga to'lovni so'rang
```

```
        <source>Send Coins</source>
        <translation>Тангаларни жунат</translation>
    
YES, The translation is problematic. The Uzbek word for "coins" is "tangalar" or "pul birliklari". The word "tangalar" used in the translation is acceptable. However, the word "juvat" is an imperative verb meaning "to send". The correct imperative form for sending coins would be "yuboring" or "jo'nating".

NO
```

```
        <source>Insufficient funds!</source>
        <translation>Кам миқдор</translation>
    
YES: The Uzbek translation is incomplete. The correct translation should be "Mablagʻ yetarli emas!"
Mablagʻ yetarli emas!
```

```
        <source>If this is activated, but the change address is empty or invalid, change will be sent to a newly generated address.</source>
        <translation>Агар бу фаоллаштирилса, аммо ўзгартирилган манзил бўл ёки нотўғри бўлса, ўзгариш янги яратилган манзилга жўнатилади.</translation>
    
YES, The translation uses incorrect terms for "change" and "address". The term " ўзгартирилган" translates to "modified" or "altered" which is not the correct term for "change" in Bitcoin context. The term "манзил" is a general word for "address" and can be used for network addresses or wallet addresses. However, the translation should use a more specific term for Bitcoin wallet address.

The correct translation should be:

NO, The translation is unproblematic.
```

```
        <source>Custom change address</source>
        <translation>Бошқа ўзгартирилган манзил</translation>
    
YES, the translation is erroneous. The word "Custom" is not translated, and "change address" is translated as "bo'shashgan manzil" which means "loose address". The correct translation for "Custom change address" in the context of Bitcoin would be "Maxsus o'zgartirilgan manzili" or "Maxsus qaytarma manzili".

NO
```

```
        <source>per kilobyte</source>
        <translation>Хар килобайтига</translation>
    
YES: The translation uses a Cyrillic script letter 'Х' which is not part of the Latin alphabet used for 'uz@Latn'. Additionally, it seems to have a spacing issue.

The correct translation should be: "Kilobyte uchun"
```

```
        <source>Send to multiple recipients at once</source>
        <translation>Бирданига бир нечта қабул қилувчиларга жўнатиш</translation>
    
YES - The translation is in Cyrillic script, not Latin script.
Correct translation: Bir necha qabul qiluvchilarga bir yoʻla yuboring
```

```
        <source>Send</source>
        <translation>Жўнатиш</translation>
    
YES - The translation is incorrect and does not convey the meaning of "Send" in the context of Bitcoin. The provided translation "Жўнатиш" appears to be in Belarusian or Ukrainian, not Uzbek Latin. The correct translation for "Send" in Uzbek Latin in a Bitcoin context would be "Yuborish".
YES - The translation is incorrect. The word "Жўнатиш" is not Uzbek.
The correct translation is:
<source>Send</source>
<translation>Yuborish</translation>
```

```
        <source>The amount to pay must be larger than 0.</source>
        <translation>Тўлов миқдори 0. дан катта бўлиши керак. </translation>
    
YES, The translation is problematic because the original text is in Latin script and the translation is in Cyrillic script.
Tўlov miqdori 0 dan katta bo'lishi kerak.
```

```
        <source>Paste address from clipboard</source>
        <translation>Manzilni qo'shib qo'yish</translation>
    
YES, The translation is problematic. The Uzbek word "qo'shib qo'yish" means "to add" or "to insert", which is not the correct translation for "Paste". The correct translation for "Paste" in this context would be "Yopishtiring". Additionally, the Uzbek word "Manzilni" means "address" or "the address", but it is missing the word "clipboard". The correct translation for "clipboard" is "tamirlangan", so the full correct translation should be "Manzilni tamirlanganidan yopishtiring".

Manzilni tamirlanganidan yopishtiring
```

```
        <source>Paste address from clipboard</source>
        <translation>Manzilni qo'shib qo'yish</translation>
    
YES, The translation is problematic. The Uzbek word "qo'shib qo'yish" means "to add" or "to insert", which is not the correct translation for "Paste". The correct translation for "Paste" in this context would be "Yopishtiring". Additionally, the Uzbek word "Manzilni" means "address" or "the address", but it is missing the word "clipboard". The correct translation for "clipboard" is "tamirlangan", so the full correct translation should be "Manzilni tamirlanganidan yopishtiring".

Manzilni tamirlanganidan yopishtiring
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/тасдиқланмади</translation>
    
YES. The Uzbek translation for "unconfirmed" is incorrect. The correct term is "tasdiqlanmagan".

NO. The translation is correct.
```

```
        <source>From</source>
        <translation>Дан</translation>
    
YES: The translation is incorrect. The Uzbek word for "From" is "Dan" or "dan" depending on context. However, the provided translation "Дан" is an archaic spelling. The correct translation is "dan".
From: dan
```

```
        <source>To</source>
        <translation>Га</translation>
    
YES: The translation is incorrect and nonsensical. The Uzbek word for "To" is "Ga" or "gacha".
Ga
```

```
        <source>Credit</source>
        <translation>Кредит (қарз)</translation>
    
YES: The translation is inaccurate and uses Cyrillic script. The Latin script is required for uz@Latn. Additionally, the meaning of "credit" in the context of Bitcoin might be better translated as "krediti" or "pul oqimi" (cash flow).
Krediti
```

```
        <source>not accepted</source>
        <translation>қабул қилинмади</translation>
    
YES, The translation is problematic. The provided translation uses Cyrillic script, while the requested Latin script is 'uz@Latn'. The correct translation in Latin script is "qabul qilinmadi".
```

```
        <source>Transaction ID</source>
        <translation>ID</translation>
    
YES: The translation is too brief and lacks context. The correct translation should be "Tranzaksiya ID".
Tranzaksiya ID
```

```
        <source>Merchant</source>
        <translation>Савдо</translation>
    
YES, The translation is problematic because the provided translation is in Cyrillic script, not the requested Latin script. The correct translation should be in Latin script.

NO
```

```
        <source>true</source>
        <translation>рост</translation>
    
YES, the translation is incorrect. The English word "true" translates to "haqiqiy" or "rost" in Uzbek. "O'sish" (growth) is not a correct translation.

Correct translation: rost
```

```
        <source>Confirmed (%1 confirmations)</source>
        <translation>Тасдиқланди (%1 та тасдиқ)</translation>
    
YES, the translation is erroneous. The phrase "та тасдиқ" translates to "confirmations confirmations" which is redundant. The correct translation should be "Tasdiqlangan (%1 tasdiq)".
NO
```

```
        <source>Received from</source>
        <translation>Дан қабул қилиш</translation>
    
YES, The translation "Дан қабул қилиш" is incorrect and does not convey the meaning of "Received from" in the context of Bitcoin. The phrase "Дан қабул қилиш" in Uzbek translates to "Accepting data" or "Receiving data" and is not the appropriate terminology for receiving funds.

The correct translation should be:

<translation>dan oldi</translation>
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning of "Sent to" in the context of Bitcoin. The provided Uzbek translation "Жўнатиш" is an infinitive verb meaning "to send", but the English phrase "Sent to" is a past participle phrase indicating the recipient of something.

A more accurate translation in the context of Bitcoin would be "Yuborilgan", which means "Sent".

Correct translation:
<translation>Yuborilgan</translation>
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES, The translation is incorrect. "Mined" in the context of Bitcoin refers to the process of creating new bitcoins by solving complex mathematical problems. The provided translation "Фойда" means "profit" or "benefit", which is not accurate in this context.

A more accurate translation would be "Qazib olingan" or "Kon qazish".

NO
```

```
        <source>This month</source>
        <translation>Шу ой</translation>
    
YES: The translation uses Cyrillic script, but the target language specified is 'uz@Latn' which requires Latin script.
Shu oy
```

```
        <source>Last month</source>
        <translation>Ўтган хафта</translation>
    
YES
The translation is inaccurate. "Last month" translates to "O'tgan oy" in Uzbek Latin script, while the provided translation "Ўтган хафта" means "Last week".

NO
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning of "Sent to" in the context of Bitcoin. The provided Uzbek translation "Жўнатиш" is an infinitive verb meaning "to send", but the English phrase "Sent to" is a past participle phrase indicating the recipient of something.

A more accurate translation in the context of Bitcoin would be "Yuborilgan", which means "Sent".

Correct translation:
<translation>Yuborilgan</translation>
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES, The translation is incorrect. "Mined" in the context of Bitcoin refers to the process of creating new bitcoins by solving complex mathematical problems. The provided translation "Фойда" means "profit" or "benefit", which is not accurate in this context.

A more accurate translation would be "Qazib olingan" or "Kon qazish".

NO
```

```
        <source>Min amount</source>
        <translation>Мин қиймат</translation>
    
YES - The translation of "Min amount" to "Мин қиймат" is problematic because the word "Мин" is not a standard Latin script word in Uzbek. The correct translation should use Latin script.
NO - Min miqdor
```

```
        <source>Watch-only</source>
        <translation>Фақат кўришга</translation>
    
UNK_LANG
```

```
        <source>to</source>
        <translation>Кимга</translation>
    
YES: The provided translation is incorrect. The correct translation of "to" in the context of Bitcoin, meaning recipient, is "kimga".
Кимга
```

```
        <source>Send Coins</source>
        <translation>Тангаларни жунат</translation>
    
YES, The translation is problematic. The Uzbek word for "coins" is "tangalar" or "pul birliklari". The word "tangalar" used in the translation is acceptable. However, the word "juvat" is an imperative verb meaning "to send". The correct imperative form for sending coins would be "yuboring" or "jo'nating".

NO
```

```
        <source>Insufficient funds</source>
        <translation>Кам миқдор</translation>
    
YES: The translation is inaccurate and uses Cyrillic script instead of Latin script as requested by the target language code 'uz@Latn'.
Correct translation: Kam mablagʻ
```

```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Hamyonni qayta yozish kerak: bajarish uchun 1%s ni qayta ishga tushiring</translation>
    
YES, The translation is problematic because the format specifier %s was incorrectly translated as 1%s.
Hamyonni qayta yozish kerak: bajarish uchun %s ni qayta ishga tushiring
```
</details>
