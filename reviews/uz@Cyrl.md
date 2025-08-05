# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>uz@Cyrl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Buz@Cyrl%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation>Манзил ёки ёрлиқни таҳрирлаш учун икки марта босинг</translation>
    
YES  
The translation means "Click twice to edit address or label," which is incorrect because the original says "Right-click" (i.e., use the right mouse button, not double click). The correct translation should specify "Ўнг кнопка билан босинг" (right-click).

Correct translation:  
Манзил ёки ёрлиқни таҳрирлаш учун ўнг тугмани босинг
```

```
        <source>Copy Label</source>
        <translation>Нусха олиш ва ёрлиқ</translation>
    
YES  
The translation "Нусха олиш ва ёрлиқ" literally means "Copy and label", which is incorrect as the source text is simply "Copy Label". The word "ва" (and) is unnecessary and changes the meaning. The correct translation should be "Ёрлиқни нусха олиш", which properly means "Copy Label" where "Ёрлиқ" is "Label" and "нусха олиш" means "Copy".
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Hamyon shifrini ochish uchun parol iborasi noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas). Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating.
</translation>
    
YES  
The translation has several issues:  
- It contains some untranslated or incorrect words (e.g., "Hamyon" should be in Cyrillic script as "Ҳамён").  
- The phrase "parol iborasi" should be consistent and idiomatic in Uzbek Cyrillic.  
- "false character" should be translated consistently as "null character" (null символ).  
- "characters" is mistranslated as "qurilmalar" (devices), which is incorrect; the correct word is "belgilar" (characters).  
- The sentence structure and clarity are poor and confusing.  
- The em dash "— but not including —" is translated incorrectly and awkwardly.  
- The closing sentence is unclear and inaccurately translated.

Correct translation:

Ҳамённи декодлаш учун киритилган парол нотўғри. У null белгини ўз ичига олади (яъни - нол байт). Агар парол ушбу дастурий таъминотнинг 25.0 дан аввалги версиясида ўрнатилган бўлса, илтимос, биринчи null белгидан олдингина бўлган белгилар билан қайта уриниб кўринг (биринчи null белгини ўз ичига олмай). Агар бу муваффақиятли бўлса, келажакда бундай муаммоларни олдини олиш учун янги парол ўрнатинг.
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Hamyon shifrini ochish uchun yordam eski parol noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas).</translation>
    
YES
The translation contains several issues:
1. The phrase "Hamyon shifrini ochish uchun yordam eski parol noto'g'ri." is awkward and ungrammatical. It seems to be a mistranslation of "The old passphrase entered for the wallet decryption is incorrect."
2. The word "qurilmalar" (which means "devices") is incorrect in context; the source refers to "characters" (belgilar).
3. The phrase "lekin shu narsa emas" is not a proper equivalent of "— but not including —".
4. The translation mixes Uzbek Latin script ("Hamyon...") instead of Uzbek Cyrillic as required for 'uz@Cyrl'.

Correct translation in Uzbek Cyrillic:

Сумкани декодлаш учун киритилган эски парол нотўғри. У null белгини ўз ичига олади (яъни - нол байт). Агар парол ибораси ушбу дастурий таъминотнинг 25.0 дан олдинги версиясида ўрнатилган бўлса, илтимос, биринчи null белгигача бўлган белгилар билан яна уриниб кўринг (бироқ биринчи null белгини ўз ичига олмай).
```

```
        <source>Banned Until</source>
        <translation>gacha kirish taqiqlanadi</translation>
    
YES  
The translation does not match the original phrase "Banned Until," which suggests a time or date until which a ban is effective. The provided translation "gacha kirish taqiqlanadi" means "access is banned until," but lacks the necessary time or date expression and is phrased as a full sentence rather than a label or short phrase.  

A more accurate and concise translation would be:  
"Ta'qiqlangangacha" or "Ta'qiqlash muddati" (meaning "Banned until [time]").  

Correct translation:  
Ta'qiqlangangacha
```

```
        <source>Runaway exception</source>
        <translation>qo'shimcha istisno</translation>
    
YES  
The translation is in Latin script ("qo'shimcha istisno") rather than Cyrillic script as required by 'uz@Cyrl'. Additionally, the phrase "qo'shimcha istisno" means "additional exception," which does not correspond to the meaning of "Runaway exception." A more accurate translation in Uzbek Cyrillic script for "Runaway exception" (an unhandled or unexpected exception) would be:

"Назоратдан чиқиб кетган истисно"
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Паролни ўзгартириш ҳамённи кодлашда фойдаланилади</translation>
    
YES  
The translation is inaccurate and misleading. The English source means "Change the passphrase used for wallet encryption," i.e., an instruction or option to change the passphrase. The translation means something like "The password change is used in wallet encryption," which changes the meaning and is grammatically incorrect.

Correct translation:  
"Ҳамённи шифрлашда фойдаланиладиган паролни ўзгартириш"
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>Nusxalanganlar dan PSBT ni yuklash</translation>
    
YES  
The translation contains spacing and grammar issues. In Uzbek (Cyrillic), "clipboard" can be translated as "буфер алмашиш" or "клипборд." The phrase "Nusxalanganlar dan PSBT ni yuklash" has extra spacing around "dan" and "ni," and doesn't accurately capture the meaning of "Load PSBT from clipboard…" with the correct case endings.

Correct translation:  
"PSBT ни клипборддан юклаш…"  
or  
"Клипборддан PSBT ни юклаш…"
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Nusxalanganlar qisman signlangan Bitkoin tranzaksiyalarini yuklash</translation>
    
YES  
The translation uses Latin script and Uzbek language terms ("Nusxalanganlar", "qisman", "signlangan", "Bitkoin", "tranzaksiyalarini"), but the specified target is 'uz@Cyrl', which means Uzbek language in Cyrillic script. Also, the translation is plural ("tranzaksiyalarini" - transactions) while the source is singular ("Transaction"). Moreover, the source phrase "from clipboard" is missing in the translation, making it incomplete.  

Correct translation in Uzbek Cyrillic script would be:  
"Буфер ёдловчисидан қисман имзоланган Биткоин транзакциясини юклаш"
```

```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
YES  
The translation "dudlangan cho'chqa go'shti koʻchirish" means "migrate smoked pork," which is irrelevant and incorrect in the Bitcoin wallet context. The correct translation for "Migrate Wallet" should relate to moving or transferring the wallet data, not any kind of meat.

Correct translation:  
"Hamyonni ko'chirish"
```

```
        <source>Ctrl+M</source>
        <translation>Abzatsga chek qo'ying.(Ctrl+M)</translation>
    
YES  
The source text "Ctrl+M" is a key combination and should be translated literally as "Ctrl+M" or its equivalent in Uzbek Cyrillic script without adding any extra explanation or text. The translation "Abzatsga chek qo'ying.(Ctrl+M)" means "Put a paragraph indent.(Ctrl+M)" which is not a correct or appropriate translation of the source.

Correct translation:  
Ctrl+M
```

```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini cheklash</translation>
    
YES  
The translation "Ijtimoiy tarmoq faoliyatini cheklash" means "Restrict social network activity," which is incorrect in this Bitcoin context. The English source "Disable network activity" refers to disabling (turning off) all network activity, not limiting social network activity.

Correct translation:  
"Тармоқ фаолиятини ўчириш"
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini yoqish</translation>
    
YES
The translation "Ijtimoiy tarmoq faoliyatini yoqish" means "Enable social network activity," which is incorrect in the context of Bitcoin where "network activity" refers to the network (tarmoqlar) connectivity or data exchange, not social networks. 

Correct translation:
"Tarmoq faoliyatini yoqish"
```

```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
YES  
The translation "dudlangan cho'chqa go'shti koʻchirish" means "migrate smoked pork," which is irrelevant and incorrect in the Bitcoin wallet context. The correct translation for "Migrate Wallet" should relate to moving or transferring the wallet data, not any kind of meat.

Correct translation:  
"Hamyonni ko'chirish"
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Watchonly skriptlari nomli yangi hamyonga ko'chirildi%1</translation>
    
YES  
The translation has format specifier %1 misplaced and no space before or after it, causing incorrect formatting. Also, the term "Watchonly" should be transliterated consistently or translated with explanation in Uzbek Cyrillic, and "skriptlari" should be adapted as "скриптлари" for Cyrillic. The phrase also lacks clarity on the wallet name. A clearer and more accurate translation would be:

"Watchonly скриптлари '%1' номли янги ҳамёнга кўчирилди."
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>Agar 'pruning' funksiyasi o'chirilgan bo'lsa, hamyondan uzoq vaqt foydalanmaslik butun zanjirnni qayta sinxronlashga olib kelishi mumkin.</translation>
    
YES  
The translation contains an error in meaning and a typo:

1. The source says "if pruning is enabled," but the translation says "if pruning is disabled" ("o'chirilgan" means "turned off"/"disabled"), which reverses the meaning. It should say "faollashtirilgan" (enabled/activated).
2. There is a typographical error: "zanjirnni" should be "zanjirni" (extra 'n').

Correct translation:  
Agar 'pruning' funksiyasi faollashtirilgan bo'lsa, hamyondan uzoq vaqt foydalanmaslik butun zanjirni qayta sinxronlashga olib kelishi mumkin.
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Ushbu hamyon uchun maxfiy kalitlarni o'chirish. Maxfiy kalitsiz hamyonlar maxfiy kalitlar yoki import qilingan maxfiy kalitlar, shuningdek, HD seedlarga ega bo'la olmaydi.</translation>
    
YES
The translation is in Uzbek but uses Latin script, while the specified language code is 'uz@Cyrl', which indicates the Cyrillic script should be used. Additionally, the translation omits parts of the original meaning, such as "cannot have an HD seed" and "This is ideal for watch-only wallets."

Correct translation in Uzbek Cyrillic script should be something like:

Ушбу ҳамён учун махфий калитларни ўчириш. Махфий калитлари ўчирилган ҳамёнларда махфий калитлар бўлмайди ва HD сид ёки импорт қилинган махфий калитларга эга бўлиши мумкин эмас. Бу фақат кузатиш учун мўлжалланган ҳамёнлар учун идеалдир.
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Tashqi signing yordamisiz tuzilgan (tashqi signing uchun zarur)</translation>
    
YES  
The translation is partially in the Latin alphabet ("Tashqi signing yordamisiz tuzilgan") rather than fully in the Cyrillic script as expected for 'uz@Cyrl'. Also, the English loanword "signing" is left untranslated and in Latin script, which is inconsistent with the Cyrillic requirement. The rest of the phrase is understandable but should be fully in Cyrillic.

Correct translation:  
"Ташқи имзолаш ёрдамисиз тузилган (ташқи имзолаш учун зарур)"
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Yuboruvchi(%1manzil) va  qabul qiluvchi(%2manzil) bir xil bo'lishi mumkin emas</translation>
    
YES  
The translation is inaccurate and incomplete. It does not convey the meaning that the address "%1" already exists as a receiving address with label "%2" and therefore cannot be added as a sending address. Instead, it states "Sender (%1 address) and receiver (%2 address) cannot be the same," which is an oversimplification and misses the key detail about existing labels and the restriction on adding the address.

Correct translation:  
"%1" manzili "%2" yorlig‘i bilan qabul qilish manzili sifatida allaqachon mavjud, shuning uchun uni yuborish manzili sifatida qo‘shish mumkin emas.
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>OK ni bosganingizda, %1to'liq blok zanjirini (%2GB) yuklab olish%4 va qayta ishlash boshlanadi, %3birinchi boshlangan%4 tranzaksiyalardan boshlab.</translation>
    
YES  
The translation is problematic due to incorrect word order, missing spaces, and misplaced format specifiers (%1, %4, etc.). The placeholders (%1, %2, %3, %4) must appear in the correct places and separated properly by spaces. Here is a correct version preserving the meaning and format specifiers appropriately spaced:

OK ni bosganingizda, %1 %4 blok zanjirining to‘liq nusxasini (%2 GB) %3 da %4 dastlab ishga tushirilgan paytdagi eng dastlabki tranzaksiyalardan boshlab yuklab olish va qayta ishlashni boshlaydi.
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Noma'lum. Sarlavhalarni oldindan sinxronlash (, %1%2%)…</translation>
    
YES  
The translation contains some issues:
1. "Noma'lum" is written using Latin script with an apostrophe, but the requested language code is 'uz@Cyrl', meaning Uzbek in Cyrillic script. It should be in Cyrillic script instead.
2. The order and placement of format specifiers "%1, %2%" are incorrect and misplaced inside parentheses and comma.
3. The English phrase "Pre-syncing Headers (%1, %2%)…" should be translated clearly and the format specifiers preserved properly as in: "Сарчеваларни олдиндан синхронлаш (%1, %2%)…"

Correct translation (in Cyrillic Uzbek):  
Номаълум. Сарчеваларни олдиндан синхронлаш (%1, %2%)…
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi. Barcha bloklar hali ham to'liq tasdiqlangan. Bu sozlamani qaytarish butun blok zanjirini qayta yuklab olishni talab qiladi.</translation>
    
YES
The translation is in Latin script (with some apostrophes and Latin characters), while the requested language is 'uz@Cyrl', which means Uzbek written in Cyrillic script. This is a script mismatch.
Also, minor issues:
- "Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi." does not accurately convey the meaning. The source says "Enabling pruning significantly reduces the disk space required to store transactions," whereas the translation implies pruning is enabled because storing transactions requires lots of memory (which is a reversed causality and the term "pruning" is untranslated).
- The phrase "pruning ni yoqish" should use a better integrated term or translated term for "pruning."
- "xotira" means memory (RAM), but the source refers to disk space (disq joyi).
- Whitespace issue: "pruning ni" should be "pruning-ni" with a hyphen as a suffix.

A better Cyrillic Uzbek translation would be:

"Pruning-ни yoqish tranzaksiyalarni saqlash uchun kerak bo‘lgan disk joyini sezilarli darajada kamaytiradi. Barcha bloklar hali ham to‘liq tasdiqlanadi. Ushbu sozlamani bekor qilish butun blok zanjirini qayta yuklab olishni talab qiladi."

Corrected translation in Cyrillic Uzbek:

"Pruning-ни ёқиш транзакцияларни сақлаш учун керак бўлган диск жойини сезиларли даражада камайтиради. Барча блоклар ҳали ҳам тўлиқ тасдиқланади. Ушбу созламани бекор қилиш бутун блок занжирини қайта юклаб олишни талаб қилади."
```

```
        <source>Number of script verification threads</source>
        <translation>Мавзуларни тўғрилаш скрипти миқдори</translation>
    
YES
The translation is inaccurate and awkward in Uzbek Cyrillic. The phrase "Number of script verification threads" should refer to "the number of threads that verify scripts," i.e., "Скриптни текшириш учун маҳсус мўлжалланган иш жараёнлари сони" or a shorter, clearer version.

Current translation "Мавзуларни тўғрилаш скрипти миқдори" literally means "Quantity of script for correcting topics," which is incorrect and misleading.

Correct translation:
Скриптни текшириш иш юритувчи жараёнлар сони
```

```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>Skriptni tekshirish ip lari sonini belgilang. </translation>
    
YES  
The translation is incomplete and does not convey the full meaning of the source text. The source explains that negative values correspond to the number of cores to leave free to the system, which is missing in the translation.

Correct translation:  
"Skriptni tekshirish iplarining sonini belgilang. Manfiy qiymatlar tizimga bo‘sh qoldirmoqchi bo‘lgan yadrolar soniga teng."
```

```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>Chegirma to'lovini standart qilib belgilash kerakmi yoki yo'qmi?</translation>
    
YES  
The translation uses Latin script ('to'lovini') instead of Cyrillic script as required for 'uz@Cyrl'. Moreover, the original sentence is a neutral technical description ("Whether to set subtract fee from amount as default or not.") and the translation is phrased as a question ("...kerakmi yoki yo'qmi?") which is stylistically less appropriate for a tooltip or option description. Also, the term "fee" is translated as "chegirma to'lovi" ("discount payment"), which is semantically incorrect; in Bitcoin context, "fee" would be better translated as "тўлов" (payment) or "комиссия" (commission/fee).

Correct translation in Cyrillic script should be more neutral and accurate, for example:

"Ҳа, тўловни миқдордан чиқаришни стандарт қилиб белгилаш ёки белгиламаслик."

Or slightly more natural:

"Тўловни миқдордан айириб ташлашни стандарт бўйича белгилаш ёки белгиламаслик."

This maintains the original meaning and is in Cyrillic Uzbek as requested.
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>Манзиллар панели ўрнига трэйни йиғиш</translation>
    
YES  
The translation is incorrect and somewhat unclear. The English source "Minimize to the tray instead of the taskbar" refers to minimizing the application window to the system tray rather than to the taskbar. The word "Манзиллар панели" means "address panel," which is unrelated and contextually wrong here. Also, "трэйни йиғиш" is a literal and unnatural phrasing for "minimize to tray."

Correct translation:  
"Таскбар ўрнига трэйга кичрайтириш"  
or  
"Вазифалар панели ўрнига систем трэйига кичрайтириш"  

Both convey minimizing to the tray instead of the taskbar/system tray correctly and naturally in Uzbek (Cyrillic).
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Tashqi signing yordamisiz tuzilgan (tashqi signing uchun zarur)</translation>
    
YES  
The translation is partially in the Latin alphabet ("Tashqi signing yordamisiz tuzilgan") rather than fully in the Cyrillic script as expected for 'uz@Cyrl'. Also, the English loanword "signing" is left untranslated and in Latin script, which is inconsistent with the Cyrillic requirement. The rest of the phrase is understandable but should be fully in Cyrillic.

Correct translation:  
"Ташқи имзолаш ёрдамисиз тузилган (ташқи имзолаш учун зарур)"
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Жами ўтказмалар ҳозиргача тасдиқланган ва сафланадиган баланс томонга ҳали ҳам ҳисобланмади</translation>
    
YES  
The translation is inaccurate and confusing. It incorrectly states that transactions have already been confirmed ("тасдиқланган"), whereas the source says they haven't been confirmed yet ("yet to be confirmed"). Also, the phrase "сафланадиган баланс томонга ҳали ҳам ҳисобланмади" is awkward and unclear.  

Correct translation:  
Жами ҳали тасдиқланмаган ва исроф қилиниши мумкин бўлган балансга ҳали амал қилмайдиган ўтказмалар суммаси
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarni qaytarish uchun Sozlamalar-&gt;Qiymatlar.</translation>
    
YES  
The translation is incomplete and does not convey the full meaning of the source. The phrase "uncheck Settings->Mask values" is missing the instruction to uncheck (i.e., it just says "Settings->Values").

Correct translation:  
"“Umumiy ko‘rinish” yorlig‘i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarning ko‘rinishini tiklash uchun Sozlamalar->Qiymatlarni yashirish bandining belgisini olib tashlang."
```

```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>Hamyon maʼlumotlarga imzo qoʻyib boʻlmaydi.</translation>
    
YES  
The translation is incomplete and inaccurate. The original sentence means "Cannot sign inputs while wallet is locked," indicating that signing transaction inputs is not possible during the wallet lock state. The current 'uz@Cyrl' translation "Hamyon maʼlumotlarga imzo qoʻyib boʻlmaydi." translates roughly as "Cannot sign data to the wallet," which loses the meaning of "while wallet is locked" and "inputs."

Correct translation:  
"Hamyon qulflanganda kirishlarga imzo qo‘yib boʻlmaydi."
```

```
        <source>URI handling</source>
        <translation>URI осилиб қолмоқда</translation>
    
YES  
The provided translation "URI осилиб қолмоқда" literally means "URI is being hung" or "URI is stuck," which does not accurately convey the intended meaning of "URI handling." The source phrase refers to the process or functionality of managing or processing URIs, not that something is stuck or frozen.

A more accurate translation for "URI handling" in Uzbek Cyrillic would be:  
"URI ни ишлаш" or "URI билан ишлаш" (meaning "working with URI" or "handling URI").  

Correct translation:  
URI билан ишлаш
```

```
        <source>Client version</source>
        <translation>Мижоз номи</translation>
    
YES  
The translation "Мижоз номи" means "Client name" in Uzbek Cyrillic, which is incorrect for the source text "Client version." The correct translation should convey "version" instead of "name."

Correct translation:  
"Клиент версияси"
```

```
        <source>Open</source>
        <translation>Очиш</translation>
    
YES
The translated word "Очиш" is incorrect and does not convey the meaning of "Open" in Uzbek (Cyrillic script). The correct translation should be "Очинг" (imperative form of "open") or "Очиқ" depending on context, but generally for a command or button label "Очинг" is appropriate.

Correct translation:
Очинг
```

```
        <source>Insufficient funds!</source>
        <translation>Кам миқдор</translation>
    
YES  
The translation "Кам миқдор" means "Low amount" or "Small quantity," which does not fully capture the urgency and meaning of "Insufficient funds!" in a financial or Bitcoin transaction context.  
A better translation would be:  
"Етарсиз маблағлар!"
```

```
        <source>Custom change address</source>
        <translation>Бошқа ўзгартирилган манзил</translation>
    
YES  
The translation "Бошқа ўзгартирилган манзил" means "Another changed address," which is not accurate. The English phrase "Custom change address" refers to a user-defined (custom) Bitcoin transaction change address, not "another changed address." A more accurate translation would explicitly convey "Custom" and "change address" in the Bitcoin transaction context.

Correct translation:  
"Мослаштирилган ўзгартириш манзили"
```

```
        <source>true</source>
        <translation>рост</translation>
    
YES  
The translation is incorrect. The English word "true" (meaning correct or true in a logical or boolean sense) should be translated to "ҳақиқий" or "рост" in Uzbek. However, "рост" is actually a Russian word written in Cyrillic and means "growth" in Russian; it does not mean "true" in Uzbek. The correct Uzbek translation for "true" in this context is "ҳақиқий" or "тоғри".

Correct translation:  
<translation>ҳақиқий</translation>
```

```
        <source>Received from</source>
        <translation>Дан қабул қилиш</translation>
    
YES  
The translation "Дан қабул қилиш" literally means "to receive from" in infinitive form, but the English phrase "Received from" is a past participle phrase used as a label or description, not an infinitive verb form. A more accurate and natural translation would be "Қабул қилинди" (Received) or "Кимдан олдинди" (Received from [someone]), depending on context. Since "Received from" is likely used as a label indicating the sender, the better translation would be:  

Correct translation:  
Қабул қилинган (Received)  
or if specifying "from" explicitly as a label:  
Қабул қилинган манба (Received from [source])  

If brevity and context favor, simply:  
Қабул қилинди  

Given the provided short source "Received from", a recommended concise and accurate translation is:  
Қабул қилинги (Received from)
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES  
The English phrase "Sent to" is a past passive form indicating something was sent to someone or somewhere. The given translation "Жўнатиш" is a noun or verbal noun meaning "Sending" or the infinitive "to send," which does not convey the past passive meaning properly.  

Correct translation:  
"Жўнатилган" (meaning "Sent to") or "Юборилган" depending on regional usage, but "Жўнатилган" is appropriate here.
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES  
The English source "Mined" in the context of Bitcoin typically refers to coins or blocks that have been successfully mined, implying the action or status of mining. The translation "Фойда" means "profit" or "gain," which is not a correct equivalent here. The correct translation for "Mined" in Uzbek Cyrillic should be related to the mining process, such as "Қазиб олинган" or simply "Қазиб олинди."  

Correct translation:  
Қазиб олинган
```

```
        <source>Last month</source>
        <translation>Ўтган хафта</translation>
    
YES  
The source text "Last month" means the previous month, but the translation "Ўтган хафта" means "Last week" in Uzbek (Cyrillic). The translation is therefore incorrect.

Correct translation:  
Ўтган ой
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES  
The English phrase "Sent to" is a past passive form indicating something was sent to someone or somewhere. The given translation "Жўнатиш" is a noun or verbal noun meaning "Sending" or the infinitive "to send," which does not convey the past passive meaning properly.  

Correct translation:  
"Жўнатилган" (meaning "Sent to") or "Юборилган" depending on regional usage, but "Жўнатилган" is appropriate here.
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES  
The English source "Mined" in the context of Bitcoin typically refers to coins or blocks that have been successfully mined, implying the action or status of mining. The translation "Фойда" means "profit" or "gain," which is not a correct equivalent here. The correct translation for "Mined" in Uzbek Cyrillic should be related to the mining process, such as "Қазиб олинган" or simply "Қазиб олинди."  

Correct translation:  
Қазиб олинган
```
</details>
