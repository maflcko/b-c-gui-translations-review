# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>uz@Cyrl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Buz@Cyrl%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation>Манзил ёки ёрлиқни таҳрирлаш учун икки марта босинг</translation>
    
YES, The translation is inaccurate. The English text says "Right-click to edit address or label" but the translation says "double-click to edit address or label".

Манзил ёки ёрлиқни таҳрирлаш учун ўнг тугмани босинг
```

```
        <source>Copy Label</source>
        <translation>Нусха олиш ва ёрлиқ</translation>
    
YES, The translation is problematic as it incorrectly translates "Copy Label" into "Copy and Label" instead of "Copy the label". The word "and" is incorrectly inserted.

Correct translation: Нусха олиш ёрлиғи
```

```
        <source>Wallet encryption failed due to an internal error. Your wallet was not encrypted.</source>
        <translation>Ҳамённи кодлаш ташқи хато туфайли амалга ошмади. Ҳамёнингиз кодланмади.</translation>
    
YES, The translation is problematic because it incorrectly translates "internal error" as "external error" ("ташқи хато" means "external error" in Uzbek, while "ички хато" means "internal error").

Ҳамённи кодлаш ички хато туфайли амалга ошмади. Ҳамёнингиз кодланмади.
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Hamyon shifrini ochish uchun parol iborasi noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas). Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating.
</translation>
    
YES - The translation has an accuracy issue. The phrase "up to — but not including — the first null character" is incorrectly translated as "faqat birinchi null belgigacha bo'lgan qurilmalar bilan" which translates to "only with the devices up to the first null character". The word "qurilmalar" (devices) is not appropriate in this context.

Correct translation: Hamyon shifrini ochish uchun kiritilgan parol noto'g'ri. U null belgisini (ya'ni - nol bayt) o'z ichiga oladi. Agar parol 25.0 dan oldingi ushbu dastur versiyasi bilan o'rnatilgan bo'lsa, iltimos, birinchi null belgidan oldingi belgilar bilan qayta urinib ko'ring. Agar bu muvaffaqiyatli bo'lsa, kelajakda bu muammoni oldini olish uchun yangi parol o'rnating.
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Hamyon shifrini ochish uchun yordam eski parol noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas).</translation>
    
YES - The translation incorrectly translates "characters" as "qurilmalar" (devices) instead of "belgilar" (characters). Additionally, it mistranslates "up to — but not including —" as "gacha bo'lgan ... (lekin shu narsa emas)" which is awkward and not precise.

The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.
Hamyon shifrini ochish uchun kiritilgan eski parol noto'g'ri. U null belgisini o'z ichiga oladi (ya'ni - nol bayt). Agar parol ushbu dasturning 25.0 dan oldingi versiyasi bilan o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgidan oldingi belgilarni kiritib qayta urinib ko'ring.
```

```
        <source>Banned Until</source>
        <translation>gacha kirish taqiqlanadi</translation>
    
YES, The translation for "Banned Until" is incorrect. It translates to "entry is prohibited until" which is not the intended meaning. The correct translation should convey that an action is banned for a specific period.
Correct translation: Taqiqlangan vaqtgacha
```

```
        <source>Runaway exception</source>
        <translation>qo'shimcha istisno</translation>
    
YES
The translation of "Runaway exception" to "qo'shimcha istisno" (additional exception) is not accurate. In the context of Bitcoin, a "runaway exception" likely refers to an unexpected or uncontrolled error. A more appropriate translation would convey the sense of an uncontrolled or uncaught error.

qo'shimcha istisno
```

```
        <source>Quit application</source>
        <translation>Иловадан чиқиш</translation>
    
YES
The translation is inaccurate. The Uzbek Cyrillic phrase "Иловадан чиқиш" translates to "Exit from the application" or "Exit from the addition". The correct translation for "Quit application" in Uzbek Cyrillic should be "Иловадан чиқиш" or "Дастурдан чиқиш".

Correct translation: Иловадан чиқиш
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Паролни ўзгартириш ҳамённи кодлашда фойдаланилади</translation>
    
YES, The translation is grammatically incorrect and doesn't accurately convey the meaning of the source text. The word "ўзгартириш" (change) is used as a noun instead of a verb.

Correct translation: Ҳамённи кодлашда фойдаланиладиган паролни ўзгартиринг
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>Nusxalanganlar dan PSBT ni yuklash</translation>
    
YES, The translation contains an erroneous word. The word "Nusxalanganlar" means "copied ones" or "copied people" and is not appropriate here. The correct word for clipboard is "clipboar", which is a loanword.

NO, Nusxalanganlar dan PSBT ni yuklash
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Nusxalanganlar qisman signlangan Bitkoin tranzaksiyalarini yuklash</translation>
    
YES - The translation is grammatically incorrect and uses an awkward phrasing. The term "Nusxalanganlar" (those who are copied) is not appropriate in this context. A more accurate and natural translation would be "Nusxadan qisman imzolangan Bitkoin tranzaksiyasini yuklang".

NO
```

```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
YES, The translation is factually incorrect and nonsensical in the context of Bitcoin. The Uzbek phrase translates to "migrate pork fat".
Correct translation: Hamyonni ko'chirish
```

```
        <source>Ctrl+M</source>
        <translation>Abzatsga chek qo'ying.(Ctrl+M)</translation>
    
YES, The translation incorrectly translates "Ctrl+M" as "Abzatsga chek qo'ying.(Ctrl+M)". The correct translation should be just "Ctrl+M".

NO
```

```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini cheklash</translation>
    
YES, The translation incorrectly translates "network" to "ijtimoiy tarmoq" which means "social network". The correct translation for "network" in this context would be "tarmoq".
Correct translation: Tarmoq faoliyatini cheklash
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini yoqish</translation>
    
YES - The translation is inaccurate and suggests enabling "social network activity" instead of "network activity."

Correct translation: Tarmoq faoliyatini yoqish
```

```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
YES, The translation is factually incorrect and nonsensical in the context of Bitcoin. The Uzbek phrase translates to "migrate pork fat".
Correct translation: Hamyonni ko'chirish
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Watchonly skriptlari nomli yangi hamyonga ko'chirildi%1</translation>
    
YES - The translation incorrectly placed the format specifier '%1' at the end of the sentence instead of after the wallet name.
Watchonly skriptlari '%1' nomli yangi hamyonga ko'chirildi.
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>Agar 'pruning' funksiyasi o'chirilgan bo'lsa, hamyondan uzoq vaqt foydalanmaslik butun zanjirnni qayta sinxronlashga olib kelishi mumkin.</translation>
    
YES, The translation states that "pruning" is disabled when the source text says "if pruning is enabled". The correct translation should be:

Agar 'pruning' funksiyasi yoqilgan bo'lsa, hamyondan uzoq vaqt foydalanmaslik butun zanjirni qayta sinxronlashga olib kelishi mumkin.
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Ushbu hamyon uchun maxfiy kalitlarni o'chirish. Maxfiy kalitsiz hamyonlar maxfiy kalitlar yoki import qilingan maxfiy kalitlar, shuningdek, HD seedlarga ega bo'la olmaydi.</translation>
    
YES. The translation is inaccurate and omits important information from the source text. Specifically, it fails to convey that wallets with private keys disabled "cannot have an HD seed".

Ushbu hamyon uchun maxfiy kalitlarni o'chiring. Maxfiy kalitlari o'chirilgan hamyonlarda maxfiy kalitlar bo'lmaydi va HD seed yoki import qilingan maxfiy kalitlarga ega bo'la olmaydi. Bu faqat kuzatuv hamyonlari uchun idealdir.
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Tashqi signing yordamisiz tuzilgan (tashqi signing uchun zarur)</translation>
    
YES - The translation uses an English word "signing" instead of a translated Uzbek word.
Tashqi imzolash qoʻllab-quvvatlamasdan tuzilgan (tashqi imzolash uchun zarur)
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Yuboruvchi(%1manzil) va  qabul qiluvchi(%2manzil) bir xil bo'lishi mumkin emas</translation>
    
YES - The translation is inaccurate and does not convey the meaning of the source text. The source text states that an address already exists as a receiving address with a label and cannot be added as a sending address. The translation states that a sender and receiver cannot be the same, which is a different concept. Additionally, the format specifiers (%1 and %2) are incorrectly placed within the text.

Correct translation: "\“%1\” manzili allaqachon\“%2\” yorlig‘i bilan qabul qiluvchi manzil sifatida mavjud va shu sababli yuboruvchi manzil sifatida qo‘shib bo‘lmaydi."
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>OK ni bosganingizda, %1to'liq blok zanjirini (%2GB) yuklab olish%4 va qayta ishlash boshlanadi, %3birinchi boshlangan%4 tranzaksiyalardan boshlab.</translation>
    
YES - The translation is problematic due to incorrect word order and missing information. The phrase "to'liq blok zanjirini (%2GB) yuklab olish%4 va qayta ishlash" is awkward and "birinchi boshlangan%4 tranzaksiyalardan boshlab" is grammatically incorrect. The format specifier %4 is also misplaced.

Correct translation: OK ni bosganingizda, %1 eng qadimgi tranzaksiyalardan boshlab %3-da %4 birinchi marta ishga tushirilganda to'liq %4 blok zanjirini (%2 GB) yuklab olish va qayta ishlashni boshlaydi.
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Noma'lum. Sarlavhalarni oldindan sinxronlash (, %1%2%)…</translation>
    
YES. The translation is problematic due to incorrect placement of format specifiers. The second format specifier "%2" is missing from the translation, and the first format specifier "%1" is directly followed by "%2%" without any space or separator, which is incorrect.

Correct translation: Noma'lum. Sarlavhalarni oldindan sinxronlash (%1, %2%)…
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi. Barcha bloklar hali ham to'liq tasdiqlangan. Bu sozlamani qaytarish butun blok zanjirini qayta yuklab olishni talab qiladi.</translation>
    
YES, The translation incorrectly uses the word "Do'kon" which means "shop" or "store" instead of "disk". The correct translation should refer to disk space.
Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi. Barcha bloklar hali ham to'liq tasdiqlangan. Bu sozlamani qaytarish butun blok zanjirini qayta yuklab olishni talab qiladi.
Disk tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi. Barcha bloklar hali ham to'liq tasdiqlangan. Bu sozlamani qaytarish butun blok zanjirini qayta yuklab olishni talab qiladi.
```

```
        <source>Number of script verification threads</source>
        <translation>Мавзуларни тўғрилаш скрипти миқдори</translation>
    
YES
The translation "Мавзуларни тўғрилаш скрипти миқдори" is inaccurate. The English phrase "Number of script verification threads" refers to the quantity of threads used for verifying scripts, not "script correction threads".

The correct translation should be: "Скриптларни текшириш потоклари сони".
```

```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>Skriptni tekshirish ip lari sonini belgilang. </translation>
    
YES
The translation is incomplete. It misses the explanation about negative values.
Skriptni tekshirish ip lari sonini belgilang. Salbiy qiymatlar tizim uchun qoldirmoqchi bo'lgan yadrolar soniga to'g'ri keladi.
```

```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>Chegirma to'lovini standart qilib belgilash kerakmi yoki yo'qmi?</translation>
    
YES - The translation is inaccurate. The original text says "subtract fee from amount as default", but the translation says "set discount fee as default". The correct translation should be "To'lovni miqdordan chegirib tashlashni standart qilib belgilash kerakmi yoki yo'qmi?".

NO - Chegirma to'lovini standart qilib belgilash kerakmi yoki yo'qmi?
YES - To'lovni miqdordan chegirib tashlashni standart qilib belgilash kerakmi yoki yo'qmi?
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>Манзиллар панели ўрнига трэйни йиғиш</translation>
    
YES. The translation is inaccurate and uses the wrong terminology. "Address" in the context of Bitcoin refers to a wallet address, not "manzil" (address/location) in a general sense. "Tray" is translated as "трэйни" which is a transliteration and sounds awkward. A more appropriate translation for "tray" in this context would be "тармоғи" or "тизимчи". The word "minimize" is also translated poorly as "йиғиш" (gather/collect), which doesn't convey the meaning of minimizing a window.

A more accurate translation would be: "Вазифалар панели ўрнига тизимчага йиғинди қилиш" or "Вазифалар панели ўрнига тизимчага минимал қилиш".

However, given the constraint that the output must be in uz@Cyrl, and the original phrasing might be idiomatic in certain software contexts, let's consider a more direct, albeit still not perfect, correction.

The core issue is "address" being translated as "manzil" and "minimize" as "yiğish".

"Minimize to the tray" is a common UI instruction. In Uzbek, "minimize" is often translated as "кичрайтириш" or "йўқотиш" (to lose/disappear, in the sense of the window vanishing from view). "Tray" is often "тизим дастаги" or "тизимча". "Taskbar" is "вазифалар панели" or "ишлар панели".

Let's refine the translation to better reflect the UI context:

"Minimize to the tray instead of the taskbar"

Corrected translation:
<translation>Вазифалар панели ўрнига тизимчага кичрайтириш</translation>
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Tashqi signing yordamisiz tuzilgan (tashqi signing uchun zarur)</translation>
    
YES - The translation uses an English word "signing" instead of a translated Uzbek word.
Tashqi imzolash qoʻllab-quvvatlamasdan tuzilgan (tashqi imzolash uchun zarur)
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Жами ўтказмалар ҳозиргача тасдиқланган ва сафланадиган баланс томонга ҳали ҳам ҳисобланмади</translation>
    
YES - The translation is inaccurate and grammatically incorrect. It incorrectly translates "yet to be confirmed" as "ҳозиргача тасдиқланган" (already confirmed) and "do not yet count toward the spendable balance" as "сафланадиган баланс томонга ҳали ҳам ҳисобланмади" (not yet counted towards the spendable balance).

Correct translation: Тасдиқланмаган ўтказмаларнинг умумий миқдори, улар сарфланадиган балансга ҳали қўшилмайди.
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarni qaytarish uchun Sozlamalar-&gt;Qiymatlar.</translation>
    
YES, The translation is missing the final part of the English sentence. The phrase "to unmask values" is not fully translated, and the instruction to uncheck the setting is incomplete.
"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarni ochish uchun Sozlamalar-&gt;Qiymatlarni yashirish tanlovini bekor qiling.
```

```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>Hamyon maʼlumotlarga imzo qoʻyib boʻlmaydi.</translation>
    
YES - The translation is missing the context of "inputs" which is crucial for understanding why the signing is not possible. The word "maʼlumotlarga" (data) is too general.
Correct translation: Hamyon qulflangan holatda kiruvchilarga imzo qoʻyib boʻlmaydi.
```

```
        <source>URI handling</source>
        <translation>URI осилиб қолмоқда</translation>
    
YES, The translation is inaccurate. The source text "URI handling" refers to the process of managing or dealing with URIs, not that the URI is hanging or stuck.
URI -ни бошқариш
```

```
        <source>Client version</source>
        <translation>Мижоз номи</translation>
    
YES, The translation is inaccurate. "Client version" refers to the version number of a software client, not its name. The provided translation "Мижоз номи" means "Client name".
Мижоз версияси
```

```
        <source>Open</source>
        <translation>Очиш</translation>
    
YES, The translation is incorrect. The word "Open" in the context of Bitcoin typically refers to opening a wallet or a connection. The provided translation "Очиш" means "cleaning" or "to clean" in Uzbek.

The correct translation for "Open" in this context should be "Очиш" or "Очилиши".

- **Open (verb):** Очилмоқ (Ochilmoq) or Очиш (Ochish)
- **Open (adjective):** Очиқ (Ochiq)

Given the context of Bitcoin and potentially opening a wallet or connection, "Очилмоқ" (to open) or "Очиш" (opening) is more appropriate.

Correct Translation: Очилмоқ
```

```
        <source>Insufficient funds!</source>
        <translation>Кам миқдор</translation>
    
YES - The translation is incomplete. The correct translation should be "Маблағ етarli emas!".
```

```
        <source>Custom change address</source>
        <translation>Бошқа ўзгартирилган манзил</translation>
    
YES, The translation is inaccurate and misleading. "Ўзгартирилган" means "modified" or "altered," which is not the correct meaning of "change" in the context of Bitcoin transactions (referring to leftover funds). A more appropriate translation for "change address" would be "қайтарма манзил" (return address) or "қолдиқ манзил" (remaining/change address).

The correct translation should be: Бошқа қайтарма манзил
```

```
        <source>true</source>
        <translation>рост</translation>
    
YES, The translation of "true" to "рост" (growth) is incorrect in the context of Bitcoin. In Bitcoin, "true" often refers to a boolean value, and a more appropriate translation would be "ҳақиқат" or "тўғри".
The correct translation is: ҳақиқат
```

```
        <source>Received from</source>
        <translation>Дан қабул қилиш</translation>
    
YES. The translation is inaccurate and doesn't convey the intended meaning in the context of Bitcoin. "Received from" implies an origin or sender, while "Дан қабул қилиш" translates to "Accepting data," which is irrelevant.

NO
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES, The translation is inaccurate. The word "Жўнатиш" (Zhunatish) means "to send" or "to transmit" in Uzbek. However, in the context of Bitcoin, "Sent to" typically refers to the recipient of a transaction, so the appropriate translation would be "Юборилган" (Yuborilgan) which means "Sent".

Correct Translation: Юборилган
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES, The translation is inaccurate. "Фойда" translates to "profit" or "gain" in English, which is not the correct translation for "Mined" in the context of Bitcoin mining. The correct translation for "Mined" in this context would be "Қазған" or "Комиссия", depending on whether it refers to the act of mining or the reward for mining. However, given the context of Bitcoin, "Қазған" is the more appropriate translation for the act of mining.
CORRECT TRANSLATION: Қазған
```

```
        <source>Last month</source>
        <translation>Ўтган хафта</translation>
    
YES, The translation is incorrect. "Last month" translates to "Ўтган ой" in Uzbek Cyrillic, not "Ўтган хафта" which means "Last week".
Ўтган ой
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES, The translation is inaccurate. The word "Жўнатиш" (Zhunatish) means "to send" or "to transmit" in Uzbek. However, in the context of Bitcoin, "Sent to" typically refers to the recipient of a transaction, so the appropriate translation would be "Юборилган" (Yuborilgan) which means "Sent".

Correct Translation: Юборилган
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES, The translation is inaccurate. "Фойда" translates to "profit" or "gain" in English, which is not the correct translation for "Mined" in the context of Bitcoin mining. The correct translation for "Mined" in this context would be "Қазған" or "Комиссия", depending on whether it refers to the act of mining or the reward for mining. However, given the context of Bitcoin, "Қазған" is the more appropriate translation for the act of mining.
CORRECT TRANSLATION: Қазған
```
</details>
