# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>uz@Cyrl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Buz@Cyrl%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation>Манзил ёки ёрлиқни таҳрирлаш учун икки марта босинг</translation>
    
YES
The translation is incorrect. The English phrase "Right-click to edit address or label" specifies using the right mouse button, whereas the translation says "Double-click to edit address or label" ("икки марта босинг" means "double-click"), which is an action with the left mouse button.

Correct translation:
Манзил ёки ёрлиқни таҳрирлаш учун ўнг тугмани босинг
```

```
        <source>Copy Label</source>
        <translation>Нусха олиш ва ёрлиқ</translation>
    
YES
The translation is incorrect. "Нусха олиш ва ёрлиқ" means "Copy and label" instead of "Copy Label". The correct translation should be:

Ёрлиқни нусха олиш
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Hamyon shifrini ochish uchun parol iborasi noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas). Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating.
</translation>
    
YES
There are several problems with the translation:
- "birinchi null belgigacha bo'lgan qurilmalar bilan" is a mistranslation; "qurilmalar" means "devices", which is incorrect here.
- "lekin shu narsa emas" is vague and confusing.
- "Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating." is ungrammatical and unclear.
- The original meaning about "up to — but not including — the first null character" is lost.

Correct translation:
Hamyonni shifrdan chiqarish uchun kiritilgan parol iborasi noto‘g‘ri. Unda null belgisi (ya’ni, nol bayt) mavjud. Agar parol iborasi ushbu dasturiy ta’minotning 25.0 versiyasidan oldinroq o‘rnatilgan bo‘lsa, iltimos, faqat birinchi null belgisigacha bo‘lgan belgilarni (lekin null belgisining o‘zini emas) kiriting va yana urinib ko‘ring. Agar muvaffaqiyatli bo‘lsa, kelajakda bu muammoga duch kelmaslik uchun yangi parol iborasini o‘rnating.
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Hamyon shifrini ochish uchun yordam eski parol noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas).</translation>
    
YES
There are several issues with the translation:
- The translation uses 'yordam' unnecessary ("yordam eski parol noto'g'ri" should be "kirtilgan eski parol noto'g'ri").
- "faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas)" is incorrect and confusing. "qurilmalar" means "devices" which is wrong; it should refer to the "characters" up to the first null character, not "devices".
- "lekin shu narsa emas" does not reflect "but not including".
- Overall, the text is somewhat unnatural and hard to follow in Uzbek Cyrillic.

Correct translation:
Ҳамённи декрипция қилиш учун киритилган эски парол нотўғри. У нол символини (яъни — нол байт) ўз ичига олади. Агар парол ибораси ушбу дастурий таъминотнинг 25.0 версиясидан олдинги версиясида ўрнатилган бўлса, илтимос, фақат биринчи нол белгигача бўлган (биринчи нол белгисини ҳисобга олмаган ҳолда) белгиларни киритиб қайта уриниб кўринг.
```

```
        <source>Banned Until</source>
        <translation>gacha kirish taqiqlanadi</translation>
    
YES
The translation is inaccurate and awkward. "gacha kirish taqiqlanadi" translates back as "entry is prohibited until," which omits the noun "Banned" and can be unclear without context.

Correct translation:
Таъқиқланган сана

Alternatively, for clarity in the Bitcoin context:
Таъқиқланган муддат

Either is preferable.
```

```
        <source>Runaway exception</source>
        <translation>qo'shimcha istisno</translation>
    
YES
The translation is inaccurate. "qo'shimcha istisno" means "additional exception" rather than "runaway exception". The intended meaning of "runaway exception" is an unhandled or unexpected exception that escapes control.

Correct translation:
Назоратдан чиққaн истиснo
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Паролни ўзгартириш ҳамённи кодлашда фойдаланилади</translation>
    
YES
The translation does not accurately reflect the source. The Uzbek translation says "Changing the passphrase is used in encrypting the wallet," which is not the same as the instruction to "Change the passphrase used for wallet encryption." 

Correct translation:
Ҳамённи шифрлаш учун ишлатиладиган паролни ўзгартиринг
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>Nusxalanganlar dan PSBT ni yuklash</translation>
    
YES
The translation is inaccurate and contains a small whitespace issue. "Nusxalanganlar dan" should be "буфердан" or "ҳотиридан" to accurately reflect "from clipboard", and there should be no space between "PSBT" and "ни". Also, "ни" must be in the appropriate case.

Correct translation:
Буфердан PSBT’ни юклаш
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Nusxalanganlar qisman signlangan Bitkoin tranzaksiyalarini yuklash</translation>
    
YES
The translation is inaccurate. The phrase "Nusxalanganlar" means "copied items", but the source refers to loading a partially signed Bitcoin transaction from the clipboard. It should more precisely mention "buferdan" for "from the clipboard" and "qisman imzolangan Bitkoin tranzaktsiyasini" for singular "transaction".

Correct translation:
Буфердан қисман имзоланган Биткоин транзакциясини юклаш
```

```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
SPAM
The translation "dudlangan cho'chqa go'shti koʻchirish" means "smoked pork transfer" which is nonsensical and unrelated to the original source "Migrate Wallet". It is neither accurate nor in the correct context for a Bitcoin wallet.

Correct translation:
Ҳамённи кўчириш
```

```
        <source>Ctrl+M</source>
        <translation>Abzatsga chek qo'ying.(Ctrl+M)</translation>
    
YES
The translation "Abzatsga chek qo'ying.(Ctrl+M)" is incorrect. "Ctrl+M" is a keyboard shortcut and should not be localized or changed semantically. The translation adds unwanted content not present in the source ("Abzatsga chek qo'ying." means "Insert a check in the paragraph."), which misleads the user.

Correct translation:
Ctrl+M
```

```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini cheklash</translation>
    
YES
The translation "Ijtimoiy tarmoq faoliyatini cheklash" translates to "Restrict social network activity," which is inaccurate. "Network" here refers to the Bitcoin network, not a social network. The translation should be more generic:

Correct translation:
Тармоқ фаолиятини ўчириш
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini yoqish</translation>
    
YES
The translation incorrectly translates "network activity" as "Ijtimoiy tarmoq faoliyati", which means "social network activity". In the context of Bitcoin, "network" refers to the peer-to-peer/Bitcoin network, not social networks.

Correct translation:
Тармоқ фаолиятини ёқиш
```

```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
SPAM
The translation "dudlangan cho'chqa go'shti koʻchirish" means "smoked pork transfer" which is nonsensical and unrelated to the original source "Migrate Wallet". It is neither accurate nor in the correct context for a Bitcoin wallet.

Correct translation:
Ҳамённи кўчириш
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Watchonly skriptlari nomli yangi hamyonga ko'chirildi%1</translation>
    
YES
The translation is inaccurate and has formatting issues. The placement of '%1' is incorrect, and the possessive meaning ("a new wallet named '%1'") is not conveyed. There should also be a space after "ko'chirildi".

Correct translation:
Watchonly skriptlar '%1' deb nomlangan yangi hamyonga ko‘chirildi.
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>Agar 'pruning' funksiyasi o'chirilgan bo'lsa, hamyondan uzoq vaqt foydalanmaslik butun zanjirnni qayta sinxronlashga olib kelishi mumkin.</translation>
    
YES
The translation has an important error: it reverses the meaning of "if pruning is enabled" by translating it as "agar 'pruning' funksiyasi o'chirilgan bo'lsa" ("if the pruning function is disabled"). The source sentence means "if pruning is enabled" (yoqilgan, not o'chirilgan). There is also a small typo: "zanjirnni" should be "zanjirni".

Correct translation:
Agar 'pruning' funksiyasi yoqilgan bo'lsa, hamyonni juda uzoq vaqtga yopish butun zanjirni qayta sinxronlashtirishga olib kelishi mumkin.
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Ushbu hamyon uchun maxfiy kalitlarni o'chirish. Maxfiy kalitsiz hamyonlar maxfiy kalitlar yoki import qilingan maxfiy kalitlar, shuningdek, HD seedlarga ega bo'la olmaydi.</translation>
    
YES
The translation omits the part about being ideal for watch-only wallets. It also alters sentence structure and does not clearly convey that such wallets have no private keys and cannot have an HD seed or imported private keys. "HD seed" should be in quotes or explained, but it is acceptable to leave as-is if standard in local usage. The phrase "Maxfiy kalitsiz hamyonlar maxfiy kalitlar yoki import qilingan maxfiy kalitlar, shuningdek, HD seedlarga ega bo'la olmaydi." is a bit redundant.

Correct translation:
Ушбу ҳамён учун махфий калитларни ўчириб қўйиш. Махфий калитлари ўчирилган ҳамёнларда махфий калитлар, HD уруғ ёки импорт қилинган махфий калитлар бўлмайди. Бу фақат ўқув режимидаги (watch-only) ҳамёнлар учун идеал.
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Tashqi signing yordamisiz tuzilgan (tashqi signing uchun zarur)</translation>
    
YES
The translation uses the English term "signing" instead of its proper Uzbek equivalent, and partial phrases are untranslated. Also, "Tashqi signing yordamisiz tuzilgan" is not natural or proper Uzbek in Cyrillic script.

Correct translation:
Ташқи имзо ёрдамисиз компиляция қилинган (ташқи имзолаш учун талаб қилинади)
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Yuboruvchi(%1manzil) va  qabul qiluvchi(%2manzil) bir xil bo'lishi mumkin emas</translation>
    
YES  
The translation is inaccurate and omits essential information from the source. The original specifies that the address "%1" already exists as a receiving address with label "%2" and therefore cannot be added as a sending address. The translation instead roughly says: "Sender (%1 address) and receiver (%2 address) cannot be the same," which is not the same as the original sentence and loses important context.

Correct translation:
Манзил "%1" аллақачон "%2" ёрлиғи билан қабул қилиш манзили сифатида мавжуд, шунинг учун уни юбориш манзили сифатида қўшиб бўлмайди.
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>OK ni bosganingizda, %1to'liq blok zanjirini (%2GB) yuklab olish%4 va qayta ishlash boshlanadi, %3birinchi boshlangan%4 tranzaksiyalardan boshlab.</translation>
    
YES
The translation has several issues:

1. Incorrect order and placement of format specifiers (%1, %2, %3, %4).
2. Missing spaces between words and after format specifiers (e.g., '%1to\'liq', '%2GB').
3. The structure does not match the source, leading to confusion.
4. The sentence is not very clear and partially omits meaning.

Correct translation:
OK тугмасини босганингизда, %1 %3 да %4 илк марта ишга тушган пайтдаги энг эрта транзакциялардан бошлаб, тўлиқ %4 блокчейнини (%2 ГБ) юклаб олиш ва қайта ишлашни бошлайди.
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Noma'lum. Sarlavhalarni oldindan sinxronlash (, %1%2%)…</translation>
    
YES
The word order of the format specifiers (%1, %2%) is incorrect, as they are together in the translation (,%1%2%), and the comma is misplaced. Also, "%2%" should be "%2%" (the percent sign is attached), but in the source, the comma and percent are not unified. The translation omits "Unknown" and the rest is literal.

Correct translation:
Номаълум. Сарлавҳаларни олдиндан синхронлаш (%1, %2%)…
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi. Barcha bloklar hali ham to'liq tasdiqlangan. Bu sozlamani qaytarish butun blok zanjirini qayta yuklab olishni talab qiladi.</translation>
    
YES
The translation is mostly accurate but contains issues:
- "Do'kon tranzaksiyalari katta xotira talab qilgani tufayli" translates as "Due to store transactions requiring large memory," which is not a correct or natural way to express the original English sentence. The sentence is not clear and appears to mistranslate the purpose of pruning.
- "store transactions" should be translated as to "store transactions data" or "saqlash uchun" but the current translation inserts "do'kon" which means "store" as in a shop, not "to store".
- The subject is misrepresented: the pruning option reduces the disk space needed to store the blockchain, not because of "do'kon tranzaksiyalari".

Correct translation:
Транзакциялар тарихини сақлаш учун талаб қилинадиган диск ҳажмини кескин камайтириш учун pruning (кесиш) функциясини ёқиш тавсия этилади. Барча блоклар ҳамон тўлиқ тасдиқланади. Бу настройкани бекор қилиш бутун блокчейнни қайта ёзиб олишни талаб қилади.
```

```
        <source>Number of script verification threads</source>
        <translation>Мавзуларни тўғрилаш скрипти миқдори</translation>
    
YES
The translation is not accurate. The English phrase refers to the "number of threads used for script verification," likely in a software context, where "thread" means a processing thread, not a forum topic (мавзу). The translation mistakenly uses "мавзу" (topic/subject), which is incorrect. Also, word order is awkward.

Correct translation:
Скриптни текшириш учун оқимлар сони
```

```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>Skriptni tekshirish ip lari sonini belgilang. </translation>
    
YES
The translation is incomplete and omits the explanation about negative values. Additionally, "ip lari" should be "ipлари" in proper Cyrillic Uzbek, and "belgilang." (set) is appropriate, but the sentence must be fully translated.

Correct translation:
Скриптни текшириш иплари сонини белгиланг. Манфий қийматлар тизимга бўш қолдирмоқчи бўлган ядролар сонига тўғри келади.
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>Манзиллар панели ўрнига трэйни йиғиш</translation>
    
YES
The translation is inaccurate. The original means minimizing the application to the system tray (notification area) instead of minimizing it to the taskbar, but the translation incorrectly refers to "address panel" (манзиллар панели), which is unrelated to the system tray or taskbar.

Correct translation:
Вазифалар панели ўрнига дастурни трэйга қисқартириш
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Tashqi signing yordamisiz tuzilgan (tashqi signing uchun zarur)</translation>
    
YES
The translation uses the English term "signing" instead of its proper Uzbek equivalent, and partial phrases are untranslated. Also, "Tashqi signing yordamisiz tuzilgan" is not natural or proper Uzbek in Cyrillic script.

Correct translation:
Ташқи имзо ёрдамисиз компиляция қилинган (ташқи имзолаш учун талаб қилинади)
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Жами ўтказмалар ҳозиргача тасдиқланган ва сафланадиган баланс томонга ҳали ҳам ҳисобланмади</translation>
    
YES
The translation misrepresents the original meaning. The source refers to transactions that are "unconfirmed" and not yet included in the spendable balance. However, the translation roughly says, "Total transactions have been confirmed so far and have not yet been counted toward the spendable balance," which is inaccurate.

Correct translation:
Тасдиқланмаган ва ҳали сарфланадиган балансга қўшилмаган ўтказмаларнинг умумий сони
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarni qaytarish uchun Sozlamalar-&gt;Qiymatlar.</translation>
    
YES
The translation is missing the instruction to "uncheck" (i.e., to remove the check from) "Settings-&gt;Mask values." The phrase "Qiymatlarni qaytarish uchun Sozlamalar-&gt;Qiymatlar." is incomplete and unclear. Also, quotation marks style is inconsistent.

Correct translation:
"Умумий кўриниш" ёрлиғи учун махфийлик режими фаоллаштирилди. Қийматларни кўриш учун "Созламалар-&gt;Қийматларни ниқоблаш" танловидан белгини олиб ташланг.
```

```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>Hamyon maʼlumotlarga imzo qoʻyib boʻlmaydi.</translation>
    
YES
The translation is inaccurate and omits key information. The source says that inputs cannot be signed while the wallet is locked, but the translation merely says "Cannot sign wallet data" and does not mention the wallet being locked or that it's the "inputs" that cannot be signed.

Correct translation:
Hamyon qulflanganida kirish maʼlumotlariga imzo qoʻyib boʻlmaydi.
```

```
        <source>URI handling</source>
        <translation>URI осилиб қолмоқда</translation>
    
YES
The translation is problematic. "URI осилиб қолмоқда" translates as "URI is being processed" or "URI is being handled (right now)", which does not accurately represent "URI handling" as a general concept, menu, or feature title. "Осилиш" also can be awkward in this context.

Correct translation:
URIни қўллаш  
or
URI билан ишлаш

Either of these translations captures the intended meaning of "URI handling" as the name of a function or procedure.
```

```
        <source>Client version</source>
        <translation>Мижоз номи</translation>
    
YES
The translation "Мижоз номи" means "Client name" in Uzbek Cyrillic, which does not accurately reflect "Client version". The correct translation should be "Мижоз версияси".

Correct translation:
Мижоз версияси
```

```
        <source>Insufficient funds!</source>
        <translation>Кам миқдор</translation>
    
YES
The translation "Кам миқдор" ("Low amount") is inaccurate. The original English "Insufficient funds!" should reflect that there is not enough money, not just a "low amount." Also, the exclamation mark is missing.

Correct translation:
Етарли маблағ йўқ!
```

```
        <source>Custom change address</source>
        <translation>Бошқа ўзгартирилган манзил</translation>
    
YES
The translation "Бошқа ўзгартирилган манзил" is problematic. "Custom change address" in the Bitcoin context refers to an address specified by the user to receive the change from a transaction, not just any "other changed address". The word "change" here is technical and means "қайтим" (return/change in money). Also, "Бошқа" means "other" rather than "custom".

Correct translation:
Махсус қайтим манзили
```

```
        <source>true</source>
        <translation>рост</translation>
    
YES
The translation is problematic. 'рост' means 'growth' in Russian, and is not correct for 'true'. The correct 'uz@Cyrl' translation for 'true' is 'тўғри' or 'рост' could also be intended in Uzbek, but this word is more likely perceived as the Russian 'growth'. The more standard and clear translation is 'тўғри'.

Correct translation:
тўғри
```

```
        <source>Received from</source>
        <translation>Дан қабул қилиш</translation>
    
YES
The translation "Дан қабул қилиш" literally means "to receive from", but in this context it is incorrect. "Received from" typically would refer to showing the sender/source, e.g., "Received from [address]". The correct 'uz@Cyrl' translation should be more like "Кимдан қабул қилинди" or "Қабул қилинган манба". "Дан қабул қилиш" sounds like an infinitive verb, not the noun phrase needed for interface text.

Correct translation:
Кимдан қабул қилинди
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES
The translation "Жўнатиш" means "to send" (infinitive) in Uzbek Cyrillic, not "Sent to", which implies an action completed and usually specifies the recipient. A more accurate translation would be "Жўнатилди" (sent) or "Қуйидагига жўнатилди" (sent to [recipient]).

Correct translation:
Жўнатилди
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES
The translation is inaccurate. "Мined" refers to "Казиб олинган" or "Қазиб олинган" (mined), whereas "Фойда" means "profit", which is incorrect in this context.

Correct translation:
Қазиб олинган
```

```
        <source>Last month</source>
        <translation>Ўтган хафта</translation>
    
YES
The translation is incorrect. The source says "Last month" ("ўтган ой" in Uzbek Cyrillic), but the translation says "Ўтган хафта", which means "Last week".

Correct translation:
Ўтган ой
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES
The translation "Жўнатиш" means "to send" (infinitive) in Uzbek Cyrillic, not "Sent to", which implies an action completed and usually specifies the recipient. A more accurate translation would be "Жўнатилди" (sent) or "Қуйидагига жўнатилди" (sent to [recipient]).

Correct translation:
Жўнатилди
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES
The translation is inaccurate. "Мined" refers to "Казиб олинган" or "Қазиб олинган" (mined), whereas "Фойда" means "profit", which is incorrect in this context.

Correct translation:
Қазиб олинган
```
</details>

Number of issues: 40.
