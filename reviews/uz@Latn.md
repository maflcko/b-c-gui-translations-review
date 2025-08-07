# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>uz@Latn</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Buz@Latn%5D%20low%20quality)


```
        <source>Copy Address</source>
        <translation>Manzillarni nusxalash</translation>
    
YES
The translation "Manzillarni nusxalash" means "Copy addresses" (plural), while the source text is singular: "Copy Address".

Correct translation:
Manzilni nusxalash
```

```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>MUHIM: Hamyon faylingizning oldingi nusxalari yangi fayl, shifrlangan hamyoni bilan almashtirilishi kerak. masalalik nuqtai nazaridan, shifrlanmagan hamyon faylining oldingi nusxalari yangi, shifrlangan hamyondan yuklashning yangilanishi bilanoq foydasiz bo'ladi.</translation>
    
YES  
The translation is problematic due to grammar errors, awkward wording, and partial mistranslation. Specifically:
- "masalalik nuqtai nazaridan" should be "Xavfsizlik nuqtai nazaridan" (For security reasons).
- The first sentence structure is awkward and not fully accurate.
- The phrase "yangi, shifrlangan hamyondan yuklashning yangilanishi bilanoq" is confusing and incorrect.
- The overall flow and accuracy suffers as meaning is only partially preserved.

Correct translation:  
MUHIM: Hamyon faylingizning oldingi zaxira nusxalarini yangi yaratilgan, shifrlangan hamyon fayli bilan almashtirishingiz kerak. Xavfsizlik nuqtai nazaridan, shifrlanmagan hamyon faylining oldingi zaxira nusxalari yangi, shifrlangan hamyondan foydalana boshlaganingiz zahoti befoyda bo‘ladi.
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Noto'g'ri maxfiy so'z kiritildi</translation>
    
YES
The translation omits "for the wallet decryption" from the source, making it less specific. Additionally, the word "maxfiy so'z" means "secret word" or "passphrase," but the full context is not preserved.

Correct translation:
Hamyonni shifrlashni ochish uchun kiritilgan maxfiy so‘z noto‘g‘ri edi.
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Hamyon shifrini ochish uchun parol iborasi noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas). Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating.
</translation>
    
YES
There are several problems with the translation:
1. "qurilmalar" means "devices", which doesn't make sense in context; it should be "belgilar" ("characters").
2. The phrase "(lekin shu narsa emas)" is an unnatural translation of "but not including".
3. The translation for "If this is successful, please set a new passphrase to avoid this issue in the future." is inaccurate; "Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating" is both awkward and incorrect ("olish" means "to get", not "to avoid").
4. There are some awkward phrasings and minor spacing inconsistencies.

Correct translation:
Hamyonning shifrlanishini ochish uchun kiritilgan parol iborasi noto‘g‘ri. U o‘z ichiga null belgisini (ya’ni — nol bayt) oladi. Agar parol iborasi ushbu dasturiy ta’minotning 25.0 versiyasidan oldingi versiyada o‘rnatilgan bo‘lsa, iltimos, faqat birinchi null belgigacha bo‘lgan — lekin uni o‘z ichiga olmagan — belgilar bilan qayta urinib ko‘ring. Agar muvaffaqiyatli bo‘lsa, kelajakda ushbu muammo takrorlanmasligi uchun yangi parol o‘rnating.
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Hamyon shifrini ochish uchun yordam eski parol noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas).</translation>
    
YES
The translation is mostly understandable but contains several inaccuracies and ambiguous phrasing:

1. "yordam eski parol noto'g'ri" — "yordam" ("help") is unnecessary and incorrect here; it should be simply "eski parol noto'g'ri kiritilgan" ("the old passphrase entered is incorrect").
2. "qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas)" — The word "qurilmalar" means "devices," which is not related to the intent here; the original refers to characters. The phrase "(lekin shu narsa emas)" ("but not that thing") is unclear and does not correctly convey "but not including."
3. The tone and specificity need improvement for accuracy and clarity.

Correct translation:
Hamyonni shifrdan chiqarish uchun kiritilgan eski parol noto'g'ri. U null belgi (ya'ni, nol bayt) ni o‘z ichiga oladi. Agar parol iborasi ushbu dasturiy ta'minotning 25.0 versiyasidan oldinroq o‘rnatilgan bo‘lsa, iltimos, faqat birinchi null belgigacha bo‘lgan belgilarni (birinchi null belgi o‘zini emas) kiriting va qayta urinib ko‘ring.
```

```
        <source>Banned Until</source>
        <translation>gacha kirish taqiqlanadi</translation>
    
YES
The translation is incorrect and does not preserve the intended meaning or capitalization. "Banned Until" should specify the time until which the ban applies. "gacha kirish taqiqlanadi" is unnatural, literally meaning "access is prohibited until", but lacks context and is not a noun phrase as in the source.

Correct translation:
"Taqiqlangan vaqti" or "Taqiqlangan muddat" or "Taqiqlash muddati" 

A full, more literal translation:
"Taqiqlangan vaqti"
```

```
        <source>Runaway exception</source>
        <translation>qo'shimcha istisno</translation>
    
YES
The translation "qo'shimcha istisno" means "additional exception", which doesn't correctly capture the meaning of "Runaway exception" (an unhandled or uncontrolled exception/error). 

Correct translation:
Nazorat qilinmaydigan istisno
```

```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>Fatal xatolik yuz berdi. %1 xavfsiz ravishda davom eta olmaydi va tizimni tark etadi. </translation>
    
YES
There is a slight issue with clarity and accuracy. "Tizimni tark etadi" is awkward and can be confusing; also, there is an unnecessary space at the end. A more accurate and natural translation would be:

Correct translation:
Fatal xatolik yuz berdi. %1 endi xavfsiz davom eta olmaydi va yopiladi.
```

```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>Bitcoin манзилини киритинг (масалан.  %1)</translation>
    
YES
The translation uses Cyrillic script characters (e.g., "манзилини киритинг") instead of the required Latin script for 'uz@Latn'. Also, there is an unnecessary extra space after the period and before "%1".

Correct translation:
Bitcoin manzilini kiriting (masalan, %1)
```

```
        <source>%1 m</source>
        <translation>%1 д</translation>
    
SPAM
The translation is in Cyrillic script ('д') instead of the required Latin script for 'uz@Latn'. The correct translation for "m" (meters or minutes, context-dependent) in Uzbek Latin script could either stay as "m" if it refers to "meters" or "daq" for "daqiqa" (minute). Most likely, for general "m", it should be left as is:

Correct translation:
%1 m
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Паролни ўзгартириш ҳамённи кодлашда фойдаланилади</translation>
    
YES
The translation is in Cyrillic script, not the required Latin script for 'uz@Latn'. Also, it inaccurately changes the sentence from an instruction ("Change the passphrase ...") to a description ("Changing the passphrase is used for wallet encryption"), which is misleading.

Correct translation:
Hamyonni shifrlash uchun ishlatiladigan maxfiy so‘zni o‘zgartiring
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>To'lovlarni so'rash(QR kolar va bitkoin yaratish: URL manzillar)</translation>
    
YES
- There are a few issues:
    1. "QR kolar" should be "QR kodlar".
    2. "bitkoin yaratish: URL manzillar" does not accurately represent "bitcoin: URIs"; it should be "va bitcoin: URI larini yaratadi".
    3. Missing space after the opening parenthesis.
    4. Should retain the meaning "generates QR codes and bitcoin: URIs".

Correct translation:
To‘lovlarni so‘rash (QR kodlar va bitcoin: URI larini yaratadi)
```

```
        <source>Ctrl+Q</source>
        <translation>formatini olib tashlash(Ctrl+Q)</translation>
    
YES
The translation is problematic. The English source "Ctrl+Q" refers to a keyboard shortcut and should not be translated or appended with a functional description unless present in the source. The added text "formatini olib tashlash" ("remove formatting") is erroneous and not in the original.

Correct translation:
Ctrl+Q
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Nusxalanganlar qisman signlangan Bitkoin tranzaksiyalarini yuklash</translation>
    
YES
The translation is inaccurate. The English phrase "Load Partially Signed Bitcoin Transaction from clipboard" means loading a single partially signed Bitcoin transaction from the clipboard. The given translation implies "load partially signed Bitcoin transactions that have been copied" and uses plural and a misleading construction.

Correct translation:
Buferdan qisman imzolangan Bitkoin tranzaksiyasini yuklash
```

```
        <source>%1 client</source>
        <translation>%1 mijoz </translation>
    
YES
There is an unwanted trailing space at the end of the translation ("mijoz "). This may cause formatting issues.

Correct translation:
%1 mijoz
```

```
        <source>Click for more actions.</source>
        <extracomment>A substring of the tooltip. "More actions" are available via the context menu.</extracomment>
        <translation>Ko'proq sozlamalar uchun bosing.</translation>
    
YES
The translation of "actions" as "sozlamalar" is incorrect. "Sozlamalar" means "settings" in Uzbek, but "actions" refers to actions or deeds, not settings. The correct word should be "harakatlar" or "amallar".

Correct translation:
Ko'proq harakatlar uchun bosing.
```

```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini cheklash</translation>
    
YES
The translation "Ijtimoiy tarmoq faoliyatini cheklash" means "Limit social network activity," which is inaccurate in the context of Bitcoin network activity. "Ijtimoiy tarmoq" refers to social networks, whereas the correct phrase should be about the network in general.

Correct translation:
Tarmoq faoliyatini o‘chirish
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini yoqish</translation>
    
YES
The translation "Ijtimoiy tarmoq faoliyatini yoqish" incorrectly translates "network" as "ijtimoiy tarmoq," which means "social network" in Uzbek. In the context of Bitcoin, "network" refers to the computer/data network, not a social network.

Correct translation:
Tarmoq faoliyatini yoqish
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>HD kalit yaratish &lt;b&gt;imkonsiz&lt;/b&gt;</translation>
    
YES
The word "imkonsiz" means "impossible," which may convey that HD key generation is not possible, rather than it being "disabled." The correct translation for "disabled" is "faol emas" or "o‘chirib qo‘yilgan."

Correct translation:
HD kalit yaratish &lt;b&gt;o‘chirib qo‘yilgan&lt;/b&gt;
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

```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
SPAM
The translation "dudlangan cho'chqa go'shti koʻchirish" means "smoked pork transfer," which is completely unrelated and nonsensical in the Bitcoin context. The correct translation of "Migrate Wallet" in 'uz@Latn' should be:

Hamyonni koʻchirish
```

```
        <source>The wallet '%1' was migrated successfully.</source>
        <translation>hamyon '%1' muvaffaqiyatli ko'chirildi.</translation>
    
YES
The translation is understandable but not fully accurate. The phrase "migrated successfully" in the context of software (e.g., Bitcoin wallet) should be translated as "muvaffaqiyatli migratsiya qilindi" or "muvaffaqiyatli o'tkazildi", not "ko'chirildi", which means "moved" and may be misleading in this context.

Correct translation:
Hamyon '%1' muvaffaqiyatli migratsiya qilindi.
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Watchonly skriptlari nomli yangi hamyonga ko'chirildi%1</translation>
    
YES
The translation is inaccurate and has formatting issues:
- The phrase "Watchonly skriptlari nomli yangi hamyonga ko'chirildi%1" is missing proper separation and does not reflect the possessive relationship or the correct structure.
- The variable '%1' should appear inside single quotes and at the same position as in the source.
- "Watchonly scripts" should be "Faqat kuzatiladigan skriptlar" in Uzbek.
- Should say "yangi '%1' nomli hamyonga ko'chirildi" (migrated to a new wallet named '%1').

Correct translation:
Faqat kuzatiladigan skriptlar yangi '%1' nomli hamyonga ko‘chirildi.
```

```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Yechish mumkin bo'lgan, lekin ko'rilmagan skriptlar nomli yangi hamyonga o'tkazildi%1</translation>
    
YES
There are a few issues:
1. The format specifier '%1' is not preceded by a space, causing a formatting problem.
2. The translation omits the meaning of "named '%1'" (i.e., that the new wallet has the name '%1').
3. The wording is a bit unclear/awkward in Uzbek. The phrase "nomli yangi hamyonga" should refer to the new wallet, not the scripts.

Correct translation:
Yechilishi mumkin, lekin kuzatilmaydigan skriptlar '%1' deb nomlangan yangi hamyonga ko'chirildi.
```

```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Wallet tiklanmoqda&lt;b&gt;%1&lt;/b&gt;</translation>
    
YES
There is a spacing issue: there should be a space after the ellipsis ("tiklanmoqda") and before the HTML tag. The original also ends with an ellipsis (…), but the translation omits it. 

Correct translation:
Wallet tiklanmoqda &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Ushbu hamyon uchun maxfiy kalitlarni o'chirish. Maxfiy kalitsiz hamyonlar maxfiy kalitlar yoki import qilingan maxfiy kalitlar, shuningdek, HD seedlarga ega bo'la olmaydi.</translation>
    
YES
The translation omits the explanation: "This is ideal for watch-only wallets." Additionally, some meaning is lost by not clarifying that wallets with private keys disabled will not have *any* private keys and cannot *have an HD seed*.

Correct translation:
Ushbu hamyon uchun maxfiy kalitlarni o‘chiring. Maxfiy kalitlari o‘chirilgan hamyonlarda maxfiy kalitlar bo‘lmaydi hamda ular HD urug‘ (seed) yoki import qilingan maxfiy kalitlarga ega bo‘la olmaydi. Bu kuzatish uchun mo‘ljallangan (“faqat o‘qish uchun”) hamyonlar uchun ideal.
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Yuboruvchi(%1manzil) va  qabul qiluvchi(%2manzil) bir xil bo'lishi mumkin emas</translation>
    
YES
The provided translation is inaccurate and omits important information. It condenses the message and does not accurately convey that the address "%1" already exists as a receiving address with label "%2" and, as a result, cannot be added as a sending address. It also incorrectly places 'manzil' after the label numbers, which doesn't match the intended placeholders.

Correct translation:
Manzil "%1" "%2" yorlig'i bilan qabul qiluvchi manzil sifatida allaqachon mavjud, shu sababli uni yuboruvchi manzil sifatida qo'shib bo'lmaydi.
```

```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>Kiritilgan %1manzil allaqachon %2yorlig'i bilan manzillar kitobida</translation>
    
YES
There are format and clarity issues in the translation:
- The variable placeholders (%1 and %2) are joined to the adjacent words without necessary spaces, which makes the translation unclear and hard to read.
- The sentence is incomplete and lacks a verb at the end.

Correct translation:
Kiritilgan "%1" manzili allaqachon manzillar kitobida "%2" yorlig‘i bilan mavjud.
```

```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Bu katalogda %1  GB ma'lumot saqlanadi</translation>
    
YES
There is an extra space between "%1" and "GB" in the translation which is not present in the source. Also, the sentence is missing a period at the end to match the source. Additionally, the word "Approximately" ("Taxminan" in Uzbek) is omitted, which affects the meaning.

Correct translation:
Bu katalogda taxminan %1 GB ma'lumot saqlanadi.
```

```
        <source>%1 will download and store a copy of the Bitcoin block chain.</source>
        <translation> Bitcoin blok zanjirining%1 nusxasini yuklab oladi va saqlaydi</translation>
    
YES
There is a formatting issue: there should not be a space before "Bitcoin", and the variable %1 should directly correspond in placement to the source text, not moved after "blok zanjirining". Also, "Bitcoin block chain" is better translated as "Bitcoin blok zanjiri". The translation more literally reads: "the copy of the Bitcoin block chain %1 will download and store", which is syntactically awkward. Lastly, the position of %1 is wrong.

Correct translation:
%1 Bitcoin blok zanjirining nusxasini yuklab oladi va saqlaydi.
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>OK ni bosganingizda, %1to'liq blok zanjirini (%2GB) yuklab olish%4 va qayta ishlash boshlanadi, %3birinchi boshlangan%4 tranzaksiyalardan boshlab.</translation>
    
YES
The translation has several issues:
- The translation is not grammatically correct (e.g. "OK ni bosganingizda, %1to'liq blok zanjirini" should be "OK ni bosganingizda, %1 to'liq %4 blok zanjirini").
- Words are jammed together without spaces ("%1to'liq" instead of "%1 to'liq", "%2GB" instead of "%2 GB", "%3birinchi bosh" instead of "%3 birinchi...").
- The order of clauses is confusing and does not retain the clear structure of the original.
- The translation of "begin to download and process" is not accurate ("yuklab olish%4 va qayta ishlash boshlanadi" is awkward and unclear).
- Format specifiers are misplaced regarding their context.

Correct translation:
OK ni bosganingizda, %1 %4 blok zanjirining to‘liq nusxasini (%2 GB) yuklab olish va qayta ishlashni boshlaydi. Bunda %4 dastlab ishga tushirilganida, %3 da amalga oshirilgan eng dastlabki tranzaksiyalardan boshlanadi.
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Noma'lum. Sarlavhalarni oldindan sinxronlash (, %1%2%)…</translation>
    
YES
The format specifiers are not copied over correctly. In the translation, the order and placement of %1 and %2 are wrong—they should be in the same place as in the source: (%1, %2%). Additionally, the translation has superfluous commas and percentage signs.

Correct translation:
Noma'lum. Sarlavhalar oldindan sinxronlanmoqda (%1, %2%)…
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Manzilni qo'shib qo'yish</translation>
    
YES
The translation is inaccurate. "Manzilni qo'shib qo'yish" means "Add the address" or "Insert address", not "Paste address from clipboard". The original instruction refers specifically to pasting from the clipboard, which is not reflected here.

Correct translation:
Manzilni buferdan joylashtirish
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi. Barcha bloklar hali ham to'liq tasdiqlangan. Bu sozlamani qaytarish butun blok zanjirini qayta yuklab olishni talab qiladi.</translation>
    
YES
There are some issues in the translation:
- The phrase "Do'kon tranzaksiyalari katta xotira talab qilgani tufayli" is an inaccurate rendering of the source. "Do'kon" means shop/store, which is incorrect here.
- The overall structure is not faithful to the original. The first sentence should communicate "Enabling pruning reduces disk space", not provide an explanation related to "shop transactions".
- The phrase "blok zanjiri" is acceptable for "blockchain", but "xotirada joy kamayishiga olib keladi" literally means "leads to a decrease in memory space", which is less precise than "reduces disk space".
- "%1" and format specifiers, if present, should be preserved, but there are none here.
- Otherwise, there are no stray spaces or double spaces.

Correct translation:
Pruning funksiyasini yoqish tranzaksiyalarni saqlash uchun zarur bo‘lgan disk xotirasini sezilarli darajada kamaytiradi. Barcha bloklar hamon to‘liq tekshiriladi. Ushbu sozlamani qaytarish butun blokcheynni qayta yuklab olishni talab qiladi.
```

```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>Skriptni tekshirish ip lari sonini belgilang. </translation>
    
YES
The translation is incomplete and omits important explanatory content from the original, especially the explanation about negative values corresponding to the number of cores to leave free. Additionally, there is an incorrect space in "ip lari" (should be "iplari").

Correct translation:
Skriptni tekshirish iplari sonini belgilang. Manfiy qiymatlar — tizimda bo‘sh qolishi kerak bo‘lgan yadrolar soni.
```

```
        <source>Subtract fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Standart bo'yicha chegirma belgilash</translation>
    
YES
The translation is inaccurate. The original sentence means "By default, subtract the fee from the amount," referring specifically to transaction fees being deducted from the sent amount. The translation "Standart bo'yicha chegirma belgilash" means "Set discount by default," which misrepresents the meaning—"fee" is rendered as "chegirma" (usually "discount"), which is incorrect.

Correct translation:
"Odatda komissiya summadan ayiriladi"
```

```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>Прокси порти (e.g. 9050)</translation>
    
YES
The translation is partially in Cyrillic script ("Прокси порти"), whereas 'uz@Latn' requires Latin script. Additionally, "e.g." should be translated as "masalan" or localized properly, not kept in English. The correct translation should be fully in Latin Uzbek.

Correct translation:
Proksi porti (masalan, 9050)
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>Манзиллар панели ўрнига трэйни йиғиш</translation>
    
YES
The translation is problematic for multiple reasons: 
1. The word "Манзиллар панели" means "Address panel", which is not correct here. The correct term for "taskbar" in Uzbek is "vazifa paneli".
2. The translation uses Cyrillic script instead of Latin ('@Latn' requires Uzbek in Latin script).
3. There are unnecessary words and incorrect phrasing.

Correct translation:
Lavhalar paneli o'rniga trayga minimallashtirish
```

```
        <source>none</source>
        <translation>йўқ</translation>
    
YES
The translation "йўқ" is in Cyrillic script, but 'uz@Latn' denotes Uzbek in Latin script. The correct translation in Latin script should be "yo‘q".

Correct translation:
yo‘q
```

```
        <source>This change would require a client restart.</source>
        <translation>Ушбу ўзгариш мижозни қайтадан ишга туширишни талаб қилади.</translation>
    
YES
The translation is in Uzbek but it uses the Cyrillic alphabet, while 'uz@Latn' specifies the Latin alphabet. Additionally, the meaning is otherwise accurate.

Correct translation:
Ushbu o‘zgarish mijozni qaytadan ishga tushirishni talab qiladi.
```

```
        <source>Watch-only:</source>
        <translation>Фақат кўришга</translation>
    
YES
The translation is in Cyrillic script ('Фақат кўришга'). However, 'uz@Latn' specifies the Uzbek Latin alphabet should be used. Additionally, the translation should be a bit more natural in Latin script.

Correct translation:
Faqat ko‘rishga
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Жами ўтказмалар ҳозиргача тасдиқланган ва сафланадиган баланс томонга ҳали ҳам ҳисобланмади</translation>
    
YES
The translation is incorrect because it mixes Cyrillic script (should be Latin for 'uz@Latn') and is also not accurate to the source meaning. It introduces unnecessary complexity and some semantic errors, and uses a passive construction that confuses the intent.

Correct translation:
Tasdiqlanmagan va sarflanadigan balansga hali kiritilmagan tranzaksiyalarning jami
```

```
        <source>Immature:</source>
        <translation>Тайёр эмас:</translation>
    
YES
The translation is in Uzbek Cyrillic script (Тайёр эмас), but 'uz@Latn' requires Latin script. It should use Latin, not Cyrillic letters.

Correct translation:
Tayyor emas:
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarni qaytarish uchun Sozlamalar-&gt;Qiymatlar.</translation>
    
YES
The translation omits part of the instruction about "unmasking" values (i.e., "uncheck" is not explicitly translated) and does not accurately reflect the actionable step for the user. The word "qaytarish" (to return) is misleading in this context, and "Settings->Mask values" is not correctly translated or explained.

Correct translation:
"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirildi. Qiymatlarni ko‘rsatish uchun Sozlamalar->Qiymatlarni yashirish belgisini olib tashlang.
```

```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>Hamyon maʼlumotlarga imzo qoʻyib boʻlmaydi.</translation>
    
YES
The translation omits the crucial information that signatures cannot be applied to "inputs" while the wallet is locked. It simply states that it's not possible to sign "wallet data", which is inaccurate. It also omits the mention of the wallet being locked.

Correct translation:
Hamyon qulflanganida kirishlarga imzo qoʻyib boʻlmaydi.
```

```
        <source>URI handling</source>
        <translation>URI осилиб қолмоқда</translation>
    
YES
The translation is problematic. The original English "URI handling" refers to the process of handling (processing, managing) URIs, but the Uzbek translation "URI осилиб қолмоқда" (note: this is written partly in Cyrillic, not Latin; it also literally means "URI is hanging/crashing/failing") does not match the meaning, and is also written in the wrong script.

Correct translation:
URI bilan ishlash
```

```
        <source>Type</source>
        <extracomment>Title of Peers Table column which describes the type of peer connection. The "type" describes why the connection exists.</extracomment>
        <translation>Тури</translation>
    
YES
The translation uses Cyrillic script ("Тури"). However, 'uz@Latn' specifies Uzbek in Latin script. The translation should use the Latin script.

Correct translation:
Turi
```

```
        <source>Inbound</source>
        <extracomment>An Inbound Connection from a Peer.</extracomment>
        <translation>Ички йўналиш</translation>
    
YES
The translation is in Cyrillic script ('Ички йўналиш'), but 'uz@Latn' should be in the Latin script. Furthermore, "Ички йўналиш" literally means "internal direction"—a more accurate translation for "Inbound" in the context of network connections would be "Kiruvchi".

Correct translation:
Kiruvchi
```

```
        <source>Client version</source>
        <translation>Мижоз номи</translation>
    
YES
The translation "Мижоз номи" is not correct for "Client version." It translates as "client name" and also uses Cyrillic script instead of Latin. The correct translation in Latin script would be:

Correct translation:
Mijoz versiyasi
```

```
        <source>Open</source>
        <translation>Очиш</translation>
    
YES
The translation is in Cyrillic script ("Очиш"), but 'uz@Latn' specifies the Uzbek language in the Latin script. It should use the Latin alphabet.

Correct translation:
Ochish
```

```
        <source>Clear console</source>
        <translation>Терминални тозалаш</translation>
    
YES
The translation is in Cyrillic script, not the requested Latin script ('uz@Latn'). The correct translation in Latin Uzbek would be:

Konsolni tozalash

Correct translation:
<translation>Konsolni tozalash</translation>
```

```
        <source>In:</source>
        <translation>Ичига:</translation>
    
YES
The translation is in Cyrillic script ("Ичига:"), but 'uz@Latn' requires Latin script. Additionally, "Ichiga:" is not the most accurate translation for "In:" in this context. In Bitcoin transaction contexts, "In:" usually refers to transaction inputs.

Correct translation:
Kirish:
```

```
        <source>To</source>
        <translation>Га</translation>
    
YES
The translation uses Cyrillic script ("Га"), but the 'uz@Latn' language code specifies the use of Latin script only. The translation should be in Uzbek Latin script.

Correct translation:
To = "Ga"
So, the correct translation in Latin script is:
Ga
```

```
        <source>From</source>
        <translation>Дан</translation>
    
YES
The translation "Дан" is in Cyrillic script, whereas 'uz@Latn' requires the Latin script for Uzbek. The correct Latin script translation for "From" is "Kimdan" or "Dan" (depending on context, but "Kimdan" is safer for clarity).

Correct translation:
Kimdan
```

```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>Хоҳланган миқдор сўрови. Кўрсатилган миқдорни сўраш учун буни бўш ёки ноль қолдиринг.</translation>
    
YES
The translation is in Cyrillic script, whereas 'uz@Latn' specifies the Latin alphabet. Additionally, the wording is inaccurate and omits the "optional" nature of the amount and the instruction to "not request a specific amount."

Correct translation:
So‘raladigan ixtiyoriy miqdor. Aniq bir miqdorni so‘ramaslik uchun buni bo‘sh yoki nol qoldiring.
```

```
        <source>Copy Address</source>
        <translation>Нусҳалаш  Манзил</translation>
    
YES
The translation uses Cyrillic script instead of Latin (should be Latin script for 'uz@Latn') and contains an erroneous double space.

Correct translation:
Manzilni nusxalash
```

```
        <source>Request payment to %1</source>
        <translation> %1 дан Тўловни сўраш</translation>
    
YES
There is a whitespace issue: an extra space at the beginning of the translation sentence, and also inconsistent usage of the apostrophe (should use proper Latin 'o' and 'o‘' where needed). Also, "Тўловни" uses Cyrillic script, while 'uz@Latn' must be Latin. Additionally, 'dan' means 'from,' whereas "to %1" should be rendered as "ga" or "uchun" ("for").

Correct translation:
%1 uchun to‘lov so‘rash
```

```
        <source>Send Coins</source>
        <translation>Тангаларни жунат</translation>
    
YES
The translation is written in Cyrillic script, whereas 'uz@Latn' specifies Uzbek in Latin script. Additionally, the word "ju'nat" should be "yuborish" or "yuboring" depending on context.

Correct translation:
Tangalarni yuborish
```

```
        <source>Insufficient funds!</source>
        <translation>Кам миқдор</translation>
    
YES
The translation "Кам миқдор" is in Cyrillic script, whereas 'uz@Latn' requires Latin script. Additionally, the phrase is incomplete and does not fully convey "Insufficient funds!" (which means "Not enough money!" or "Yetarli mablag' yo'q!").

Correct translation:
Yetarli mablag' yo'q!
```

```
        <source>If this is activated, but the change address is empty or invalid, change will be sent to a newly generated address.</source>
        <translation>Агар бу фаоллаштирилса, аммо ўзгартирилган манзил бўл ёки нотўғри бўлса, ўзгариш янги яратилган манзилга жўнатилади.</translation>
    
YES
The translation is in Cyrillic script, but the requested language is 'uz@Latn' (Uzbek in Latin script). Also, "ўзгартирилган манзил" more literally means 'the changed address,' which is a bit off. "Change" in Bitcoin should be translated as "qaytim" or "o'zgarish" (less common for the Bitcoin term).

Correct translation:
Agar bu yoqilgan bo‘lsa, lekin qaytim manzili bo‘sh yoki noto‘g‘ri bo‘lsa, qaytim yangi yaratilgan manzilga yuboriladi.
```

```
        <source>Custom change address</source>
        <translation>Бошқа ўзгартирилган манзил</translation>
    
YES
The translation is problematic. The provided 'uz@Latn' translation uses Cyrillic script and is also inaccurate. 'uz@Latn' requires the Latin script, and the meaning should be closer to "Maxsus qaytim manzili" (i.e., a custom Bitcoin change address).

Correct translation:
Maxsus qaytim manzili
```

```
        <source>per kilobyte</source>
        <translation>Хар килобайтига</translation>
    
YES
The translation is in Cyrillic script ('uz' in Cyrillic), but the target is 'uz@Latn' (Uzbek Latin script). Also, the letter capitalization is not consistent with typical usage.

Correct translation:
har kilobaytiga
```

```
        <source>Send</source>
        <translation>Жўнатиш</translation>
    
YES
The translation uses Cyrillic script ('Жўнатиш') instead of the required Latin script for 'uz@Latn'. The correct translation in Uzbek Latin script is 'Yuborish'.

Correct translation:
Yuborish
```

```
        <source>The amount to pay must be larger than 0.</source>
        <translation>Тўлов миқдори 0. дан катта бўлиши керак. </translation>
    
YES
The translation is written in Cyrillic script, but 'uz@Latn' specifies the Latin script for Uzbek. Additionally, there is an extra space at the end.

Correct translation:
To'lov miqdori 0 dan katta bo'lishi kerak.
```

```
        <source>Paste address from clipboard</source>
        <translation>Manzilni qo'shib qo'yish</translation>
    
YES
The translation "Manzilni qo'shib qo'yish" means "to add the address" rather than "Paste address from clipboard". It does not convey the action of pasting from the clipboard.

Correct translation:
Manzilni xotira (buf) dan qo'yish
or
Manzilni buferdan qo'yish
```

```
        <source>Paste address from clipboard</source>
        <translation>Manzilni qo'shib qo'yish</translation>
    
YES
The translation "Manzilni qo'shib qo'yish" means "to add the address" rather than "Paste address from clipboard". It does not convey the action of pasting from the clipboard.

Correct translation:
Manzilni xotira (buf) dan qo'yish
or
Manzilni buferdan qo'yish
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/тасдиқланмади</translation>
    
YES
The translation '%1/тасдиқланмади' uses Cyrillic script ('тасдиқланмади') instead of the requested Latin script for 'uz@Latn'. Also, the translation for "unconfirmed" in Uzbek Latin script is "tasdiqlanmagan". 

Correct translation:
%1/tasdiqlanmagan
```

```
        <source>From</source>
        <translation>Дан</translation>
    
YES
The translation "Дан" is in Cyrillic script, whereas 'uz@Latn' requires the Latin script for Uzbek. The correct Latin script translation for "From" is "Kimdan" or "Dan" (depending on context, but "Kimdan" is safer for clarity).

Correct translation:
Kimdan
```

```
        <source>To</source>
        <translation>Га</translation>
    
YES
The translation uses Cyrillic script ("Га"), but the 'uz@Latn' language code specifies the use of Latin script only. The translation should be in Uzbek Latin script.

Correct translation:
To = "Ga"
So, the correct translation in Latin script is:
Ga
```

```
        <source>Credit</source>
        <translation>Кредит (қарз)</translation>
    
YES
The translation is in Cyrillic script (Кредит (қарз)), while 'uz@Latn' specifies the Latin script for Uzbek. Also, the word "Credit" as used in financial/transactional contexts in Bitcoin is better translated as "Kredit" (or possibly "Kredit (qarz)", though "qarz" means debt/loan and may not be equivalent). 

Correct translation:
Kredit
```

```
        <source>not accepted</source>
        <translation>қабул қилинмади</translation>
    
YES
The translation uses Cyrillic script (қабул қилинмади) instead of Latin script as required by 'uz@Latn'. The content itself is accurate, but the script must be Latin.

Correct translation:
qabul qilinmadi
```

```
        <source>Transaction ID</source>
        <translation>ID</translation>
    
YES
The translation is incomplete. "Transaction ID" should be fully translated to Uzbek in Latin script. Only "ID" is not enough and omits the key term "transaction".

Correct translation:
Tranzaksiya identifikatori
```

```
        <source>Merchant</source>
        <translation>Савдо</translation>
    
YES
The translation "Савдо" is written in Cyrillic, but 'uz@Latn' requires the Latin script. Additionally, "Savdo" means "trade" or "commerce" in Uzbek, while "merchant" is better translated as "Savdogar" (a person who is a trader or merchant).

Correct translation:
Savdogar
```

```
        <source>true</source>
        <translation>рост</translation>
    
SPAM
The translation 'рост' is in Cyrillic script, and is the Russian word for "growth", not the correct transliteration or translation for "true". The correct 'uz@Latn' translation (Uzbek in Latin script) would be "rost" or "to'g'ri".

Correct translation:
rost
```

```
        <source>Confirmed (%1 confirmations)</source>
        <translation>Тасдиқланди (%1 та тасдиқ)</translation>
    
YES
The translation is in Cyrillic script ("Тасдиқланди (%1 та тасдиқ)"), but 'uz@Latn' requires the Latin script for Uzbek. Additionally, for more natural Uzbek, "та тасдиқ" could more accurately be "ta tasdiq" or "ta tasdiqlash", but "tasdiq" is acceptable in meaning.

Correct translation:
Tasdiqlandi (%1 ta tasdiq)
```

```
        <source>Received from</source>
        <translation>Дан қабул қилиш</translation>
    
YES
The translation is incorrect and in the wrong script. The text "Дан қабул қилиш" is in Cyrillic script, not Latin ('uz@Latn'). Additionally, it means "Receive from" but with awkward phrasing.

Correct translation:
Qabul qilindi kimdan
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES
The translation is problematic. The original English "Sent to" means that something has been sent to a specific address or recipient. The provided translation "Жўнатиш" is in Cyrillic script and means "Send" (the verb, not the phrase), not "Sent to". Additionally, the translation should be in Latin script as specified by 'uz@Latn'.

Correct translation:
Yuborildi (ga)
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES
The translation "Фойда" means "profit" in Uzbek written in Cyrillic, whereas "Mined" refers to coins that have been obtained through mining. The correct translation should be in Latin script as specified by 'uz@Latn', and more accurately represent the term "mined".

Correct translation:
Qazib olingan
```

```
        <source>This month</source>
        <translation>Шу ой</translation>
    
YES
The translation "Шу ой" is in Cyrillic script, but 'uz@Latn' requires the Latin script. Correct translation in Uzbek Latin script should be:

Bu oy
```

```
        <source>Last month</source>
        <translation>Ўтган хафта</translation>
    
YES
The translation is incorrect. "Ўтган хафта" means "last week" in Uzbek, not "last month".

Correct translation:
O‘tgan oy
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES
The translation is problematic. The original English "Sent to" means that something has been sent to a specific address or recipient. The provided translation "Жўнатиш" is in Cyrillic script and means "Send" (the verb, not the phrase), not "Sent to". Additionally, the translation should be in Latin script as specified by 'uz@Latn'.

Correct translation:
Yuborildi (ga)
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES
The translation "Фойда" means "profit" in Uzbek written in Cyrillic, whereas "Mined" refers to coins that have been obtained through mining. The correct translation should be in Latin script as specified by 'uz@Latn', and more accurately represent the term "mined".

Correct translation:
Qazib olingan
```

```
        <source>Min amount</source>
        <translation>Мин қиймат</translation>
    
YES
The translation is mostly correct, but it uses Cyrillic script (Мин қиймат) instead of the Latin script as required for 'uz@Latn'. It should be in Uzbek Latin.

Correct translation:
Eng kam qiymat
```

```
        <source>Watch-only</source>
        <translation>Фақат кўришга</translation>
    
YES
The translation "Фақат кўришга" is in Uzbek but written in Cyrillic script, while 'uz@Latn' requires Latin script. Additionally, a more natural translation would be "Faqat ko‘rish uchun" or "Faqat ko‘rish". 

Correct translation:
Faqat ko‘rish
```

```
        <source>to</source>
        <translation>Кимга</translation>
    
YES
The translation "Кимга" is in Cyrillic script, not Latin ('uz@Latn' demands the Latin script). Furthermore, "Кимга" means "to whom", which is more specific than the preposition "to".

Correct translation:
ga

So, the translation should be just "ga", or, if more context is needed, "Kimga" (in Latin script). However, for the preposition "to", simply "ga" is most accurate.
```

```
        <source>Send Coins</source>
        <translation>Тангаларни жунат</translation>
    
YES
The translation is written in Cyrillic script, whereas 'uz@Latn' specifies Uzbek in Latin script. Additionally, the word "ju'nat" should be "yuborish" or "yuboring" depending on context.

Correct translation:
Tangalarni yuborish
```

```
        <source>Insufficient funds</source>
        <translation>Кам миқдор</translation>
    
YES
The translation is in Cyrillic script (Кам миқдор), whereas 'uz@Latn' specifies the use of Latin script. Additionally, the phrase more literally means 'small amount' rather than 'Insufficient funds', which would be better translated as "Yetarli mablag‘ yo‘q" or "Mablag‘ yetarli emas".

Correct translation:
Yetarli mablag‘ yo‘q
```

```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Hamyonni qayta yozish kerak: bajarish uchun 1%s ni qayta ishga tushiring</translation>
    
YES
The translation introduces an error with "1%s" instead of the correct format specifier "%s". This could cause display or runtime issues. The rest of the translation is otherwise correct, but the format specifier must be copied exactly.

Correct translation:
Hamyonni qayta yozish kerak: bajarilishini yakunlash uchun %s ni qayta ishga tushiring
```
</details>

Number of issues: 88.
