# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>uz@Latn</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Buz@Latn%5D%20low%20quality)


```
        <source>Copy Address</source>
        <translation>Manzillarni nusxalash</translation>
    
YES  
The translation "Manzillarni nusxalash" means "Copy the addresses" (plural and in the accusative case), while the source is singular "Copy Address". It should be singular and neutral, as it is likely a button or command referring to copying a single address.  

Correct translation:  
"Manzil nusxalash"
```

```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>MUHIM: Hamyon faylingizning oldingi nusxalari yangi fayl, shifrlangan hamyoni bilan almashtirilishi kerak. masalalik nuqtai nazaridan, shifrlanmagan hamyon faylining oldingi nusxalari yangi, shifrlangan hamyondan yuklashning yangilanishi bilanoq foydasiz bo'ladi.</translation>
    
YES
The translation has punctuation and spacing issues, and some phrasing sounds unnatural or incorrect. For example, "yangi fayl, shifrlangan hamyoni bilan" is awkward; it should specify "yangi, shifrlangan hamyon fayli" to clearly mirror "newly generated, encrypted wallet file." Also, "masalalik nuqtai nazaridan" is incorrect; it should be "xavfsizlik nuqtai nazaridan" ("for security reasons"). The second sentence is also confusing and should be clearer.

Correct translation:
MUHIM: Hamyon faylingizning oldingi nusxalari yangi, shifrlangan hamyon fayli bilan almashtirilishi kerak. Xavfsizlik nuqtai nazaridan, yangi, shifrlangan hamyondan foydalanishni boshlaganingizdan so‘ng, shifrlanmagan hamyon faylining oldingi nusxalari foydasiz bo‘ladi.
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Noto'g'ri maxfiy so'z kiritildi</translation>
    
YES  
The translation omits some information from the source. The source specifies that the passphrase entered was for wallet decryption, whereas the translation only says "An incorrect passphrase was entered" without mentioning the wallet or decryption.

A more accurate translation would be:  
"Noto‘g‘ri maxfiy so‘z hamyonni shifrlashni ochish uchun kiritildi."
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Hamyon shifrini ochish uchun parol iborasi noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas). Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating.
</translation>
    
YES  
The translation contains several errors and awkward phrasings:

1. "Hamyon shifrini ochish uchun parol iborasi noto'g'ri." — better as "Hamyonni shifrlashni ochish uchun kiritilgan parol noto‘g‘ri."
2. "null belgini o'z ichiga oladi (ya'ni - nol bayt)." — should use "null belgini" or "bo‘sh belgi" consistently; "belgi" is okay but better as "null belgisi (ya’ni — nol bayt)".
3. "Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa" — better as "Agar parol ushbu dasturiy ta’minotning 25.0 oldingi versiyasida belgilangan bo‘lsa".
4. "faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas)" — the word "qurilmalar" (which means "devices") is incorrect, it should be "belgilar" (characters). The parenthesis "(lekin shu narsa emas)" is awkward; the source says "but not including".

5. "Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating." — this sentence is unclear and incorrectly translated. It should convey: "If this is successful, set a new passphrase to avoid this issue in the future."

Correct translation:

Hamyonni shifrlashni ochish uchun kiritilgan parol noto‘g‘ri. U null belgisi (ya’ni — nol bayt)ni o‘z ichiga oladi. Agar parol ushbu dasturiy ta’minotning 25.0 oldingi versiyasida belgilangan bo‘lsa, iltimos, faqat birinchi null belgisigacha bo‘lgan belgilar bilan qayta urinib ko‘ring (lekin null belgisini kiritmang). Agar bu muvaffaqiyatli bo‘lsa, kelajakda ushbu muammoning oldini olish uchun yangi parol belgilang.
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Hamyon shifrini ochish uchun yordam eski parol noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas).</translation>
    
YES  
The translation contains several errors and awkward phrasing that affect clarity and correctness:

1. "Hamyon shifrini ochish uchun yordam eski parol noto'g'ri." — This is grammatically incorrect and confusing. It tries to say "The old passphrase entered for the wallet decryption is incorrect," but the wording is wrong. A better phrase would be: "Hamyon shifrlashini yechish uchun kiritilgan eski parol noto‘g‘ri."

2. "U null belgini o'z ichiga oladi (ya'ni - nol bayt)." — Correct, but "belgi" is more natural than "belgini" for "null character" here. However, it's acceptable.

3. "Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas)." — This sentence is confusing and inaccurate:

   - "qurilmalar bilan" means "with devices," which is incorrect here; probably meant "characters" ("belgilar").
   - "(lekin shu narsa emas)" translation of "but not including" is not properly rendered.

A better translation of the whole instruction would be:

"Eski parol (passphrase) hamyon shifrlanishini yechish uchun notoʻgʻri kiritilgan. Unda null belgisi (yaʼni, nol qiymatli bayt) mavjud. Agar parol ushbu dasturiy taʼminot 25.0 versiyasidan oldin o‘rnatilgan bo‘lsa, iltimos, qayta urinib koʻring, faqat birinchi null belgigacha boʻlgan belgilarni kiritib (ammo null belgisini oʻzini kiritmang)."

Corrected full translation:

"Eski parol hamyon shifrlanishini yechish uchun notoʻgʻri kiritilgan. Unda null belgisi (yaʼni, nol qiymatli bayt) mavjud. Agar parol ushbu dasturiy taʼminot 25.0 versiyasidan oldingi versiyasida oʻrnatilgan boʻlsa, iltimos, faqat birinchi null belgigacha boʻlgan belgilarni kiritib (shu belgini oʻzini kiritmasdan) qayta urinib koʻring."

---

Final correct translation:

<translation>Eski parol hamyon shifrlanishini yechish uchun notoʻgʻri kiritilgan. Unda null belgisi (yaʼni, nol qiymatli bayt) mavjud. Agar parol ushbu dasturiy taʼminot 25.0 versiyasidan oldingi versiyasida oʻrnatilgan boʻlsa, iltimos, faqat birinchi null belgigacha boʻlgan belgilarni kiritib (shu belgini oʻzini kiritmasdan) qayta urinib koʻring.</translation>
```

```
        <source>Banned Until</source>
        <translation>gacha kirish taqiqlanadi</translation>
    
YES  
The translation "gacha kirish taqiqlanadi" means "access is banned until" but it does not explicitly convey the phrase "Banned Until" by itself; it is more of a full sentence rather than a phrase or label. Also, "gacha" means "until," but the phrase lacks a clear noun or timestamp (e.g., "until [time]"). A more accurate and suitable translation for this label would be:

"Taqiqlangan vaqtgacha"  
or  
"Taqiqlash muddati"  

Both phrases more clearly represent the concept "Banned Until" as a label indicating the ban duration.
```

```
        <source>Runaway exception</source>
        <translation>qo'shimcha istisno</translation>
    
YES  
The English phrase "Runaway exception" refers to an exception that has occurred and is not being properly handled or "runaway" as a technical term. The translation "qo'shimcha istisno" literally means "additional exception," which changes the meaning and is incorrect in this context.

A more accurate translation would be:  
"nazoratdan chiqqan istisno"  
which conveys "runaway exception" as an exception out of control.
```

```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>Fatal xatolik yuz berdi. %1 xavfsiz ravishda davom eta olmaydi va tizimni tark etadi. </translation>
    
YES
The translation includes an unnecessary trailing space before the closing tag, which is a minor formatting issue. Additionally, "tizimni tark etadi" literally means "will leave the system," which might be better translated as "dasturdan chiqadi" ("will exit the application") to match the English "will quit."

Correct translation:
Fatal xatolik yuz berdi. %1 xavfsiz ravishda davom eta olmaydi va dasturdan chiqadi.
```

```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>Bitcoin манзилини киритинг (масалан.  %1)</translation>
    
YES
The translation mixes Latin script ('uz@Latn') with Cyrillic script ("манзилини киритинг (масалан. %)"), which is inconsistent and problematic for the requested 'uz@Latn' (Uzbek in Latin script). Also, there is an extra space before %1, and a dot after "масалан" should not be preceded by a space.

Correct translation:
Bitcoin manzilini kiriting (masalan %1)
```

```
        <source>%1 m</source>
        <translation>%1 д</translation>
    
YES  
The source uses the Latin letter "m" (likely meaning meters or minutes), but the translation uses the Cyrillic letter "д" which does not correspond to "m" and is inappropriate in 'uz@Latn' (Uzbek Latin script) context. The translation should retain the Latin letter "m" as in the source, since Uzbek Latin script uses Latin letters.

Correct translation:  
%1 m
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Паролни ўзгартириш ҳамённи кодлашда фойдаланилади</translation>
    
YES  
The translation is inaccurate and partially in Cyrillic script rather than Latin script as required by 'uz@Latn'. It roughly translates back as "Changing the password is used in wallet encryption," which is grammatically incorrect and does not convey the command or instruction properly. A correct translation should be in Latin script and clearly express "Change the passphrase used for wallet encryption."

Correct translation:  
"Hamyonni shifrlashda ishlatiladigan parolni o‘zgartiring"
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>To'lovlarni so'rash(QR kolar va bitkoin yaratish: URL manzillar)</translation>
    
YES  
There is a spacing issue after "so'rash" (missing space) and the phrase "QR kolar" is incorrect; the correct term is "QR kodlar". Also, "bitcoin: URIs" should be translated more accurately as "bitcoin: URI manzillari" or "bitcoin: URI'lari". The translation also unnecessarily uses "yaratish" (generate/create), which should be consistent with "generates" in the source but better expressed with "yaratadi".

Correct translation:  
To'lovlarni so'rash (QR kodlar va bitcoin: URI manzillarini yaratadi)
```

```
        <source>Ctrl+Q</source>
        <translation>formatini olib tashlash(Ctrl+Q)</translation>
    
YES  
The translation "formatini olib tashlash(Ctrl+Q)" adds meaning ("remove format") that does not exist in the source "Ctrl+Q". The source is just a key combination and should be left as is or translated simply for clarity as a shortcut label without extra explanation. Also, there is no space before the parenthesis, which is less clear.

Correct translation:  
Ctrl+Q
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Nusxalanganlar qisman signlangan Bitkoin tranzaksiyalarini yuklash</translation>
    
YES  
The translation is somewhat inaccurate and awkward. "Nusxalanganlar" means "the copied ones" and is plural, which does not fit well with the source. Also, "qisman signlangan" is a literal word-for-word translation of "partially signed," but "signlangan" mixes English "sign" with Uzbek suffix, which is not natural Uzbek. "Bitkoin" is acceptable as the transliteration of Bitcoin. The phrase should be more precise and singular to match the English.

A better translation would be:  
"Qisqa imzo qo‘yilgan Bitcoin tranzaksiyasini clipboarddan yuklash"  
or more naturally:  
"Clipboarddan qisman imzolangan Bitcoin tranzaksiyasini yuklash"  

This correctly reflects "Partially Signed Bitcoin Transaction" and the source of loading from the clipboard.
```

```
        <source>%1 client</source>
        <translation>%1 mijoz </translation>
    
YES
There is an extra trailing space after "mijoz" which is not present in the source. Also, "client" in the Bitcoin context is better translated as "klient" or sometimes "mijoz" (which means "customer") but "klient" is more standard in IT terminology.

Correct translation:
%1 klient
```

```
        <source>Click for more actions.</source>
        <extracomment>A substring of the tooltip. "More actions" are available via the context menu.</extracomment>
        <translation>Ko'proq sozlamalar uchun bosing.</translation>
    
YES  
The translation "Ko'proq sozlamalar uchun bosing." means "Click for more settings," which is inaccurate since the source says "Click for more actions." The word "sozlamalar" means "settings," not "actions." A better translation would use the word "harakatlar" for "actions."

Correct translation:  
"Ko'proq harakatlar uchun bosing."
```

```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini cheklash</translation>
    
YES  
The translation "Ijtimoiy tarmoq faoliyatini cheklash" means "Restrict social network activity," which is not an accurate rendering of "Disable network activity" in the context of Bitcoin or computer networking. The correct translation should refer to disabling or turning off network activity rather than restricting social networks.

Correct translation:  
"Tarmoq faoliyatini o‘chirib qo‘yish"
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini yoqish</translation>
    
YES
The translation "Ijtimoiy tarmoq faoliyatini yoqish" means "Enable social network activity," which is incorrect in this Bitcoin context. The correct translation should refer to enabling network activity related to the Bitcoin P2P network, not social networks.

Correct translation:
"Tarmoq faoliyatini yoqish"
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>HD kalit yaratish &lt;b&gt;imkonsiz&lt;/b&gt;</translation>
    
YES
The translation has a meaning issue: "imkonsiz" means "impossible" rather than "disabled." The correct Uzbek word for "disabled" in this context is "faolsiz" or "o‘chirib qo‘yilgan."

Correct translation:
HD kalit yaratish &lt;b&gt;faolsiz&lt;/b&gt;
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
The translation is mostly accurate but has some issues:

1. The placeholder for the backup file name is translated as "1-2.legacy.bak", which seems like a mistaken hardcoded example. It should use the placeholders "<wallet name>-<timestamp>.legacy.bak" as in the source, or the Uzbek equivalent with correct angle brackets.

2. The phrase "bir yoki bir nechta deskriptor hamyonga aylantiradi" is understandable but "deskriptor hamyonga" is better phrased in Uzbek as "deskriptorli hamyonlarga" (descriptor wallets in plural, with proper adjective form).

3. The second sentence: "Agar bu hamyonda faqat tomosha skriptlari mavjud bo'lsa" literally means "If this wallet contains only watch scripts"; the source says "If this wallet contains any watchonly scripts"—so "faqat" (only) is incorrect here and should be removed.

4. The phrase "faqat tomosha qilish uchun skriptlar mavjud" is clumsy. Better would be "unda tomosha qilish uchun skriptlar mavjud bo'ladi" or "unda watchonly skriptlar bo'ladi."

5. The sentence "Agar bu hamyonda echilishi mumkin bo'lgan, lekin tomosha qilinmagan skriptlar bo'lsa" is a bit convoluted. The original: "If this wallet contains any solvable but not watched scripts" — better: "Agar bu hamyonda echilishi mumkin, lekin tomosha qilinmagan skriptlar bo'lsa"

6. The sentence "Migratsiya jarayoni ko'chirishdan oldin hamyonning zaxira nusxasini yaratadi" is awkward; better: "Migratsiya jarayoni ko'chirishdan oldin hamyonning zaxira nusxasini yaratadi" is what is written, but better phrasing would be "Migratsiya jarayoni boshlanishidan oldin hamyonning zaxira nusxasini yaratadi."

7. The phrase "Uni ushbu hamyon katalogida topish mumkin" is correct.

8. The quotation marks around "Hamyonni tiklash" are preserved correctly.

Corrected translation:

Hamyonni ko'chirish ushbu hamyonni bitta yoki bir nechta deskriptorli hamyonlarga aylantiradi. Hamyonning yangi zaxira nusxasini yaratish kerak bo'ladi.
Agar bu hamyonda har qanday watchonly skriptlar mavjud bo'lsa, ularni o'z ichiga olgan yangi hamyon yaratiladi.
Agar bu hamyonda echilishi mumkin, lekin tomosha qilinmagan skriptlar mavjud bo'lsa, ularni o'z ichiga olgan boshqa yangi hamyon yaratiladi.

Migratsiya jarayoni boshlanishidan oldin hamyonning zaxira nusxasini yaratadi. Ushbu zaxira fayli &lt;hamyon nomi&gt;-&lt;vaqt tamg'asi&gt;.legacy.bak deb nomlanadi va uni ushbu hamyon katalogida topish mumkin. Noto'g'ri migratsiya yuzaga kelsa, zaxira nusxasini "Hamyonni tiklash" funksiyasi yordamida tiklash mumkin.
```

```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
YES  
The translation "dudlangan cho'chqa go'shti koʻchirish" means "migrate smoked pork meat," which is unrelated and inappropriate as a translation for "Migrate Wallet." The term refers to moving or transferring a wallet, not food.

Correct translation:  
Hamyonni ko‘chirish
```

```
        <source>The wallet '%1' was migrated successfully.</source>
        <translation>hamyon '%1' muvaffaqiyatli ko'chirildi.</translation>
    
YES
The translation lacks capitalization at the beginning of the sentence; "hamyon" should be capitalized as "Hamyon" for correctness and formality. Also, the phrase "ko'chirildi" literally means "was copied/moved" which may not convey the exact meaning of "migrated" in the Bitcoin context, where the term "ko‘chirildi" is understandable but "muvaffaqiyatli ko‘chirildi" is acceptable. To improve clarity and maintain formality, a better translation would be:

Hamyon '%1' muvaffaqiyatli ko‘chirildi.
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Watchonly skriptlari nomli yangi hamyonga ko'chirildi%1</translation>
    
YES
The translation is missing spacing before the placeholder %1, and the sentence structure is incomplete or unclear. The English sentence means that "Watchonly scripts have been migrated to a new wallet named '%1'." 

Correct translation:
"Watchonly skriptlari '%1' nomli yangi hamyonga ko'chirildi."
```

```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Yechish mumkin bo'lgan, lekin ko'rilmagan skriptlar nomli yangi hamyonga o'tkazildi%1</translation>
    
YES  
The translation has some grammatical and formatting issues. The phrase "nomli yangi hamyonga o'tkazildi%1" places the placeholder %1 at the end but without a space, which is incorrect. Also, the phrase "ko'rilmagan skriptlar nomli yangi hamyonga" is misleading; it implies the scripts are named in the new wallet, but the wallet is named '%1'. The overall sentence structure does not clearly reflect that the solvable but not watched scripts have been migrated to a new wallet named '%1'.

Correct translation:  
Yechish mumkin bo‘lgan, lekin kuzatilmaydigan skriptlar '%1' nomli yangi hamyonga ko‘chirildi.
```

```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>Wallet tiklanmoqda&lt;b&gt;%1&lt;/b&gt;</translation>
    
YES
The translated text is missing the ellipsis ("…") at the end, which is present in the source and indicates an ongoing process. Also, there should be a space between "tiklanmoqda" and the markup "<b>%1</b>" for better readability.

Correct translation:
Wallet tiklanmoqda &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Ushbu hamyon uchun maxfiy kalitlarni o'chirish. Maxfiy kalitsiz hamyonlar maxfiy kalitlar yoki import qilingan maxfiy kalitlar, shuningdek, HD seedlarga ega bo'la olmaydi.</translation>
    
YES
The translation is incomplete and omits part of the meaning, specifically that wallets with private keys disabled cannot have an HD seed, and it does not mention that this setting is ideal for watch-only wallets. Also, the original sentence explains that wallets with private keys disabled have no private keys at all, which is only partly captured. The phrase "Ushbu hamyon uchun maxfiy kalitlarni o'chirish" literally means "Disable private keys for this wallet," but "o'chirish" usually means "turn off" or "delete," which is acceptable here, though "faolligini o‘chirib qo‘yish" might sound clearer.

Correct translation:
Ushbu hamyon uchun maxfiy kalitlarni o‘chirib qo‘yish. Maxfiy kalitlari o‘chirib qo‘yilgan hamyonlarda hech qanday maxfiy kalitlar bo‘lmaydi, shuningdek, HD seed yoki import qilingan maxfiy kalitlarga ega bo‘la olmaydi. Bu faqat kuzatuvchi (watch-only) hamyonlar uchun ideal yechimdir.
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Yuboruvchi(%1manzil) va  qabul qiluvchi(%2manzil) bir xil bo'lishi mumkin emas</translation>
    
YES  
The translation is incomplete and does not accurately convey the original meaning. The source states that the address "%1" already exists as a receiving address with label "%2" and thus cannot be added as a sending address. The translation misses mentioning the address "%1", the labels, and the condition about adding it as a sending address. Also, the placeholders %1 and %2 are missing and the sentence structure is incorrect.

Correct translation:  
`"%1" manzili "%2" yorliq bilan qabul qiluvchi manzil sifatida allaqachon mavjud, shuning uchun uni yuboruvchi manzil sifatida qo'shib bo'lmaydi.`
```

```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>Kiritilgan %1manzil allaqachon %2yorlig'i bilan manzillar kitobida</translation>
    
YES  
The translation has issues with missing and incorrect spacing and word order, which makes it unnatural and unclear. The placeholders %1 and %2 should be kept with proper spacing and punctuation. Also, the phrase should closely follow the source meaning: "The entered address "%1" is already in the address book with label "%2"."

Correct translation:  
Kiritilgan "%1" manzil allaqachon "%2" yorlig'i bilan manzillar kitobida mavjud.
```

```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Bu katalogda %1  GB ma'lumot saqlanadi</translation>
    
YES
There is an extra space before "GB" in the translation. Also, the English sentence is in the future tense and more formal, so adding a word meaning "about" or "approximately" at the start is correct, but the translation misses the word for "approximately." A more accurate and natural translation would be:

"Taxminan %1 GB ma'lumot bu katalogda saqlanadi"
```

```
        <source>%1 will download and store a copy of the Bitcoin block chain.</source>
        <translation> Bitcoin blok zanjirining%1 nusxasini yuklab oladi va saqlaydi</translation>
    
YES
There is a spacing issue in the translation. The placeholder %1 should come immediately after "Bitcoin blok zanjirining" without a space before it, and a space should follow %1 before "nusxasini". Also, the sentence lacks a pronoun or subject before "Bitcoin blok zanjirining %1 nusxasini..." to clarify what will download. Since %1 typically stands for a program or entity, it should come at the start without space. Correct spacing and sequence:

Correct translation:
%1 Bitcoin blok zanjirining nusxasini yuklab oladi va saqlaydi
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>OK ni bosganingizda, %1to'liq blok zanjirini (%2GB) yuklab olish%4 va qayta ishlash boshlanadi, %3birinchi boshlangan%4 tranzaksiyalardan boshlab.</translation>
    
YES  
The translation has issues with word order, spacing, and placement of format specifiers, which creates confusion and disrupts natural flow. Specifically:  
- Missing spaces around format specifiers (%1, %2, %3, %4) and words, e.g., "%1to'liq" should be "%1 to'liq".  
- The sequence of phrases is awkward and unclear.  
- The meaning and structure are not faithfully preserved from the source.

Correct translation:  
OK ni bosganingizda, %1 %4 blok zanjirining to‘liq nusxasini (%2 GB) yuklab olish va qayta ishlashni boshlaydi, bunda %4 dastlab ishga tushganda %3dagi eng eski tranzaksiyalar asos bo‘ladi.
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Noma'lum. Sarlavhalarni oldindan sinxronlash (, %1%2%)…</translation>
    
YES
The translation mishandles the placement and order of the format specifiers. In the source, the placeholders are "%1" and "%2%", but the translation shows "(, %1%2%)" which is incorrect and has a stray comma.

Correct translation:
Noma'lum. Sarlavhalarni oldindan sinxronlash (%1, %2%)…
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Manzilni qo'shib qo'yish</translation>
    
YES  
The translation "Manzilni qo'shib qo'yish" means "Add address" or "Attach address," which is inaccurate. The source means "Paste address from clipboard," so it should explicitly mention pasting, not adding. The correct translation is:  
"Manzilni papanadan joylashtirish"  
(or)  
"Manzilni clipboarddan joylashtirish"  
to clearly convey pasting from the clipboard.
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi. Barcha bloklar hali ham to'liq tasdiqlangan. Bu sozlamani qaytarish butun blok zanjirini qayta yuklab olishni talab qiladi.</translation>
    
YES
The translation has some inaccuracies and awkward phrasing. For example, "Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi." literally means "Because store transactions require large memory, enabling pruning significantly leads to reduced memory space," which is confusing and changes the original meaning. The original English means enabling pruning significantly reduces disk space required to store transactions. In Uzbek, this should be clearer and directly mention disk space reduction.

The corrected translation would be:

"Pruning ni yoqish tranzaksiyalarni saqlash uchun talab qilinadigan disk maydonini sezilarli darajada kamaytiradi. Barcha bloklar hali ham toʻliq tasdiqlanadi. Ushbu sozlamani bekor qilish butun blok zanjirini qayta yuklab olishni talab qiladi."
```

```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>Skriptni tekshirish ip lari sonini belgilang. </translation>
    
YES
The translation is incomplete and does not convey the full meaning of the source text. It only translates the first sentence fragment and omits the explanation about negative values and system cores.

Correct translation:
Skriptni tekshirish iplari sonini belgilang. Manfiy qiymatlar tizimga erkin qoldirmoqchi bo‘lgan yadro soniga mos keladi.
```

```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>Chegirma to'lovini standart qilib belgilash kerakmi yoki yo'qmi?</translation>
    
YES  
The translation "Chegirma to'lovini standart qilib belgilash kerakmi yoki yo'qmi?" is incorrect because "Chegirma to'lovi" means "discount fee," which changes the intended meaning. The source talks about subtracting the fee from the amount by default (fee subtraction in a Bitcoin transaction), not a "discount."

A more accurate translation would be:  
"To'lovni miqdordan avtomatik chegirib qo'yish kerakmi yoki yo'qmi?"  
(This conveys the idea of automatically subtracting the fee from the amount as the default.)
```

```
        <source>Subtract fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Standart bo'yicha chegirma belgilash</translation>
    
YES
The translation is inaccurate and incomplete. The source means "Subtract fee from amount by default," referring to a setting that causes the fee to be deducted from the amount sent. The given translation "Standart bo'yicha chegirma belgilash" means "Set discount by default," which is misleading and does not mention subtracting a fee from the amount.

Correct translation:
"To'lov miqdoridan standart bo'yicha komissiyani ayirish"
```

```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>Прокси порти (e.g. 9050)</translation>
    
YES
The translation uses Cyrillic script (Прокси порти), but the language tag 'uz@Latn' indicates Latin script Uzbek. Also, "e.g." is English and should be translated or replaced with an appropriate Uzbek equivalent such as "masalan". 

Correct translation:
Proxy porti (masalan 9050)
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>Манзиллар панели ўрнига трэйни йиғиш</translation>
    
YES  
The translation uses Cyrillic script instead of the specified Latin script for 'uz@Latn'. Additionally, "Манзиллар панели" translates back as "address panel," which is incorrect in this context. The English phrase refers to minimizing the application to the system tray instead of the taskbar. A correct Latin-script Uzbek translation would be:  

"Vazifa paneli o‘rniga tizim paneliga kichraytirish"
```

```
        <source>none</source>
        <translation>йўқ</translation>
    
YES  
The translation uses Cyrillic script ("йўқ") instead of the requested Latin script for 'uz@Latn'. The correct Latin-script Uzbek translation of "none" is:  
"yo‘q"
```

```
        <source>This change would require a client restart.</source>
        <translation>Ушбу ўзгариш мижозни қайтадан ишга туширишни талаб қилади.</translation>
    
YES
The translation is in Cyrillic script, not in 'uz@Latn' (Latin script Uzbek) as requested. Also, the translation is otherwise accurate but should be rendered in Latin script.

Correct translation:
Ushbu o‘zgarish mijozni qaytadan ishga tushirishni talab qiladi.
```

```
        <source>Watch-only:</source>
        <translation>Фақат кўришга</translation>
    
YES  
The translation is in Cyrillic script, but the requested language is 'uz@Latn' (Uzbek in Latin script). Moreover, "Фақат кўришга" means "For viewing only", but is incomplete and lacks a proper ending (e.g., "only" as an adjective should be "faqat ko‘rish" or "faqat ko‘rish uchun"). A better translation in Latin script would be:

"Faqat ko‘rish:"
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Жами ўтказмалар ҳозиргача тасдиқланган ва сафланадиган баланс томонга ҳали ҳам ҳисобланмади</translation>
    
YES  
The translation is incorrect and not in the Uzbek Latin script as required. The text is in Cyrillic script, and the meaning is somewhat distorted. A correct Uzbek Latin translation would be:  
"Yakunlanmagan va sarflash mumkin bo‘lgan qoldiqka hali qo‘shilmagan jami tranzaksiyalar"
```

```
        <source>Immature:</source>
        <translation>Тайёр эмас:</translation>
    
YES
The translation uses Cyrillic script ("Тайёр эмас:") instead of the expected Latin script for 'uz@Latn'. The translation should be in Latin alphabet.

Correct translation:
Tayyor emas:
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarni qaytarish uchun Sozlamalar-&gt;Qiymatlar.</translation>
    
YES  
The translation is incomplete and misleading. The original English phrase says: "To unmask the values, uncheck Settings->Mask values." The Uzbek translation ends abruptly at "Sozlamalar->Qiymatlar." without communicating the action of unchecking the mask. Also, the phrase 'uncheck Settings->Mask values' is missing.

Correct translation:  
"“Umumiy ko‘rinish” yorlig‘i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarni ko‘rsatish uchun Sozlamalar->Qiymatlarni yashirish katagidan belgisini olib tashlang."
```

```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>Hamyon maʼlumotlarga imzo qoʻyib boʻlmaydi.</translation>
    
YES  
The translation "Hamyon maʼlumotlarga imzo qoʻyib boʻlmaydi." means "Cannot sign data of the wallet," which is not fully accurate. The original means that signing of inputs cannot be done while the wallet is locked, but the phrase "while wallet is locked" is missing in the translation. This information is crucial.

Correct translation:  
"Hamyon bloklangan paytda kirishlarga imzo qo‘yib bo‘lmaydi."
```

```
        <source>URI handling</source>
        <translation>URI осилиб қолмоқда</translation>
    
YES  
The translation contains Cyrillic script ("осилиб қолмоқда"), while the target language variant 'uz@Latn' requires the Latin script. Additionally, the phrase "URI handling" should be translated to Uzbek in Latin script and reflect the concept of managing or processing URIs.  

Correct translation:  
URI bilan ishlash
```

```
        <source>Type</source>
        <extracomment>Title of Peers Table column which describes the type of peer connection. The "type" describes why the connection exists.</extracomment>
        <translation>Тури</translation>
    
YES
The translation uses the Cyrillic script ("Тури") instead of the expected Latin script for 'uz@Latn'. The correct translation in Latin script should be:

Turi
```

```
        <source>Inbound</source>
        <extracomment>An Inbound Connection from a Peer.</extracomment>
        <translation>Ички йўналиш</translation>
    
YES  
The translation uses Cyrillic script ("Ички йўналиш") instead of the expected Latin script for 'uz@Latn'. The translation should be in Latin script as per 'uz@Latn' language code.

Correct translation:  
Ichki yo‘nalish
```

```
        <source>Client version</source>
        <translation>Мижоз номи</translation>
    
YES
The translation "Мижоз номи" is in Cyrillic script, not Latin script as required by 'uz@Latn'. Additionally, "Мижоз номи" means "client name," not "Client version."

Correct translation (in Uzbek Latin script) should be:
"Mijoz versiyasi"
```

```
        <source>Open</source>
        <translation>Очиш</translation>
    
YES  
The translation uses Cyrillic script ("Очиш") instead of Latin script as required by the 'uz@Latn' language code. Uzbek in Latin script should be "Ochish".  

Correct translation:  
Ochish
```

```
        <source>Clear console</source>
        <translation>Терминални тозалаш</translation>
    
YES  
The translation is written in Cyrillic script, but the target language 'uz@Latn' requires Latin script. Also, the translation "Терминални тозалаш" means "Clear the terminal," which is acceptable but should be in Latin letters: "Terminalni tozalash".  

Correct translation:  
Terminalni tozalash
```

```
        <source>In:</source>
        <translation>Ичига:</translation>
    
YES  
The source text is "In:" written in English using Latin script, but the translation "Ичига:" is in Cyrillic script, which does not correspond to the requested 'uz@Latn' language variant (Uzbek in Latin script).  
Correct translation in Uzbek Latin script would be:  
"Ichiga:"
```

```
        <source>To</source>
        <translation>Га</translation>
    
YES  
The translation is problematic because it uses Cyrillic script ("Га") whereas the requested language code 'uz@Latn' specifies Uzbek in Latin script. Also, the word "To" as a preposition or label is typically translated as "ga" in Uzbek Latin script.  

Correct translation:  
<translation>ga</translation>
```

```
        <source>From</source>
        <translation>Дан</translation>
    
YES  
The translation uses Cyrillic script ("Дан") instead of the requested Latin script for Uzbek ('uz@Latn').  
Correct translation in Latin Uzbek:  
Dan
```

```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>Хоҳланган миқдор сўрови. Кўрсатилган миқдорни сўраш учун буни бўш ёки ноль қолдиринг.</translation>
    
YES  
The translation is in Cyrillic script which does not match the required 'uz@Latn' (Uzbek in Latin script). Additionally, the translation has some inaccuracies and the style could be improved for clarity.

Correct translation in Uzbek Latin script:  
"Ixtiyoriy summani so‘rash. Maxsus summani so‘ramaslik uchun bu yerni bo‘sh qoldiring yoki nol kiriting."
```

```
        <source>Copy Address</source>
        <translation>Нусҳалаш  Манзил</translation>
    
YES
The translation contains Cyrillic script ("Нусҳалаш Манзил"), but the requested language variant is 'uz@Latn', which uses the Latin alphabet for Uzbek. Also, there is an extra space between the words ("Нусҳалаш  Манзил") which is incorrect spacing.

Correct translation (in Latin Uzbek):
Nusxalash manzil
```

```
        <source>Request payment to %1</source>
        <translation> %1 дан Тўловни сўраш</translation>
    
YES  
There is an extra leading space before "%1" in the translation, which is a whitespace formatting issue. Also, the word "дан" (from) is inappropriate here; it should be "га" (to) to indicate requesting payment *to* %1.

Correct translation:  
%1 га тўловни сўраш
```

```
        <source>Send Coins</source>
        <translation>Тангаларни жунат</translation>
    
YES  
The translation includes Cyrillic script ("Тангаларни жунат") which does not conform to the 'uz@Latn' (Uzbek in Latin script) requirement. The translation should be in the Latin alphabet.

Correct translation:  
"Tangalarni jo'nat"
```

```
        <source>Insufficient funds!</source>
        <translation>Кам миқдор</translation>
    
YES  
The translation uses Cyrillic script, while the language tag 'uz@Latn' specifies Uzbek in Latin script. Also, the translation is incomplete and does not convey the same urgency or meaning as "Insufficient funds!". A better translation in Uzbek Latin script would be:  
"Kifoya miqdorda mablag‘ yo‘q!"
```

```
        <source>If this is activated, but the change address is empty or invalid, change will be sent to a newly generated address.</source>
        <translation>Агар бу фаоллаштирилса, аммо ўзгартирилган манзил бўл ёки нотўғри бўлса, ўзгариш янги яратилган манзилга жўнатилади.</translation>
    
YES  
The translation is in Cyrillic script (Uzbek in Cyrillic), while the requested language tag 'uz@Latn' specifies the Latin script for Uzbek. Additionally, the word "өзгартирилган" is incorrect in context; it should be "change address" translated as "ўзгартириш манзили" or "ўзгартириш манзил". The phrase "бўл ёки нотўғри бўлса" contains an error and should be "бўш ёки нотўғри бўлса" (empty or invalid).  

Correct translation in Latin script:  
"Agar bu faollashtirilsa, ammo o‘zgartirish manzili bo‘sh yoki noto‘g‘ri bo‘lsa, o‘zgartirish yangi yaratilgan manzilga jo‘natiladi."
```

```
        <source>Custom change address</source>
        <translation>Бошқа ўзгартирилган манзил</translation>
    
YES
The translation is in Cyrillic script instead of the Latin script required by 'uz@Latn'. Additionally, the translation "Бошқа ўзгартирилган манзил" means "Another changed address," which is not an accurate or natural translation for "Custom change address" in the Bitcoin context.

Correct translation in Uzbek Latin script:
"Maxsus o'zgartirish manzili"
```

```
        <source>per kilobyte</source>
        <translation>Хар килобайтига</translation>
    
YES  
The translation uses Cyrillic script ("Хар килобайтига") which is inconsistent with the specified 'uz@Latn' language variant that requires Latin script. The correct translation in Latin script should be:  
"Har kilobaytga"
```

```
        <source>Send to multiple recipients at once</source>
        <translation>Бирданига бир нечта қабул қилувчиларга жўнатиш</translation>
    
YES  
The translation is in the Cyrillic script, while the requested language variant is 'uz@Latn', i.e., Uzbek in Latin script. Additionally, the wording is not fully idiomatic in Uzbek Latin. A better translation in Uzbek Latin would be:  
"Bir vaqtning o‘zida bir nechta qabul qiluvchilarga yuborish"
```

```
        <source>Send</source>
        <translation>Жўнатиш</translation>
    
YES
The translation uses Cyrillic script ("Жўнатиш") instead of the expected Latin script for 'uz@Latn'. The correct translation in Latin script should be:

Jo'natish
```

```
        <source>The amount to pay must be larger than 0.</source>
        <translation>Тўлов миқдори 0. дан катта бўлиши керак. </translation>
    
YES  
The translation uses Cyrillic script instead of Latin script, which is inconsistent with 'uz@Latn' (Uzbek in Latin script). Also, there is an extra space before the period in "0. дан". The correct translation in Latin script without extra spaces is:  
"To‘lov miqdori 0 dan katta bo‘lishi kerak."
```

```
        <source>Paste address from clipboard</source>
        <translation>Manzilni qo'shib qo'yish</translation>
    
YES  
The translation "Manzilni qo'shib qo'yish" means "Add address" or "Attach address," which does not accurately convey the instruction to "Paste address from clipboard."  

A more accurate translation would be:  
"Manzilni bufer xotirasidan joylashtirish"  
or simply:  
"Manzilni buferdan joylashtirish"  
which literally means "Paste address from the buffer (clipboard)."
```

```
        <source>Paste address from clipboard</source>
        <translation>Manzilni qo'shib qo'yish</translation>
    
YES  
The translation "Manzilni qo'shib qo'yish" means "Add address" or "Attach address," which does not accurately convey the instruction to "Paste address from clipboard."  

A more accurate translation would be:  
"Manzilni bufer xotirasidan joylashtirish"  
or simply:  
"Manzilni buferdan joylashtirish"  
which literally means "Paste address from the buffer (clipboard)."
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/тасдиқланмади</translation>
    
YES
The translation contains a mixture of Latin script and Cyrillic script. Since the target language code is 'uz@Latn' (Uzbek in Latin script), the entire translation should be in the Latin alphabet. The word "тасдиқланмади" is in Cyrillic and should be transliterated into Latin script.

Correct translation:  
%1/tasdiqlanmadi
```

```
        <source>From</source>
        <translation>Дан</translation>
    
YES  
The translation uses Cyrillic script ("Дан") instead of the requested Latin script for Uzbek ('uz@Latn').  
Correct translation in Latin Uzbek:  
Dan
```

```
        <source>To</source>
        <translation>Га</translation>
    
YES  
The translation is problematic because it uses Cyrillic script ("Га") whereas the requested language code 'uz@Latn' specifies Uzbek in Latin script. Also, the word "To" as a preposition or label is typically translated as "ga" in Uzbek Latin script.  

Correct translation:  
<translation>ga</translation>
```

```
        <source>Credit</source>
        <translation>Кредит (қарз)</translation>
    
YES  
The translation uses Cyrillic script ("Кредит (қарз)"), which is not consistent with the 'uz@Latn' locale, where Latin script is expected. Also, the parentheses are acceptable, but ideally the translation should be fully in Latin script.

Correct translation:  
Credit
```

```
        <source>not accepted</source>
        <translation>қабул қилинмади</translation>
    
YES
The translation uses Cyrillic script ("қабул қилинмади"), whereas the 'uz@Latn' language tag specifies Uzbek in Latin script. The correct translation in Latin script should be:

qabul qilinmadi
```

```
        <source>Transaction ID</source>
        <translation>ID</translation>
    
YES  
The translation is incomplete and does not convey the full meaning of "Transaction ID". It should explicitly include "Transaction" (Transaksiya or Tranzaksiya) to accurately reflect the original phrase.  

Correct translation:  
Tranzaksiya ID
```

```
        <source>Merchant</source>
        <translation>Савдо</translation>
    
YES  
The translation uses Cyrillic script ("Савдо") instead of Latin script, but the language tag 'uz@Latn' requires the Latin alphabet. Also, "Савдо" means "trade" or "commerce," whereas "Merchant" is better translated as "Savdogar" or "Sotuvchi" in Uzbek Latin script.

Correct translation:  
Savdogar
```

```
        <source>true</source>
        <translation>рост</translation>
    
YES  
The provided translation "рост" is in Cyrillic script and appears to be a Russian word meaning "growth," which is incorrect and unrelated. The source word "true" in Uzbek Latin script should be translated as "haqiqiy" or simply "to'g'ri" depending on context. Since "true" is often translated as "haqiqiy" or "rost" (using Latin script) meaning "true" or "correct," the correct translation should be:

Correct translation: rost
```

```
        <source>Confirmed (%1 confirmations)</source>
        <translation>Тасдиқланди (%1 та тасдиқ)</translation>
    
YES  
The translation uses Cyrillic script ("Тасдиқланди (%1 та тасдиқ)") instead of Latin script which is required for 'uz@Latn'. Also, the formatting and spacing are correct but the script does not match the specified Latin script.

Correct translation:  
Tasdiqlandi (%1 ta tasdiq)
```

```
        <source>Received from</source>
        <translation>Дан қабул қилиш</translation>
    
YES  
The translation contains Cyrillic script ("Дан қабул қилиш") instead of Latin script which is expected for 'uz@Latn'. Also, the phrase "Received from" is more naturally translated as "Qabul qilindi" or "dan olindi" depending on context, but must be in Latin letters.

Correct translation:  
Qabul qilindi (if meant as "Received from" indicating source)  
or more precisely:  
Olingan manba:  
Depending on the exact context, but importantly, it must be Latin script.
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES
The translation uses Cyrillic script ("Жўнатиш") instead of the expected Latin script for 'uz@Latn'. The correct Latin-script translation is:
"Yuborilgan"
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES  
The source English word "Mined" refers to the action or state of having extracted cryptocurrency (Bitcoin) through mining. The provided translation "Фойда" means "profit" or "benefit" in Uzbek (Cyrillic script), which is incorrect in this context. Also, the text is in Cyrillic script, while the target language is 'uz@Latn' (Latin script Uzbek), so the script does not match the requirement.  

Correct translation in Uzbek (Latin script) would be something like:  
"Qazilgan"
```

```
        <source>This month</source>
        <translation>Шу ой</translation>
    
YES  
The translation is written in Cyrillic script, but the language tag 'uz@Latn' indicates the Uzbek language in Latin script. The correct translation in Latin script should be:  
**Shu oy**
```

```
        <source>Last month</source>
        <translation>Ўтган хафта</translation>
    
YES  
The provided translation is incorrect. "Last month" should be translated as "O'tgan oy" in Uzbek (Latin script). The given translation "Ўтган хафта" means "Last week" and is in Cyrillic script, which is inconsistent with the 'uz@Latn' (Uzbek Latin) specification.

Correct translation:  
O'tgan oy
```

```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
YES
The translation uses Cyrillic script ("Жўнатиш") instead of the expected Latin script for 'uz@Latn'. The correct Latin-script translation is:
"Yuborilgan"
```

```
        <source>Mined</source>
        <translation>Фойда</translation>
    
YES  
The source English word "Mined" refers to the action or state of having extracted cryptocurrency (Bitcoin) through mining. The provided translation "Фойда" means "profit" or "benefit" in Uzbek (Cyrillic script), which is incorrect in this context. Also, the text is in Cyrillic script, while the target language is 'uz@Latn' (Latin script Uzbek), so the script does not match the requirement.  

Correct translation in Uzbek (Latin script) would be something like:  
"Qazilgan"
```

```
        <source>Min amount</source>
        <translation>Мин қиймат</translation>
    
YES  
The translation uses Cyrillic script ("Мин қиймат") instead of the Latin script expected for 'uz@Latn'. Also, "қиймат" is the Uzbek word for "value" or "amount", but the correct Latin script transliteration should be used. The phrase "Min amount" would be better translated as "Min miqdor" in Uzbek Latin script.

Correct translation:  
Min miqdor
```

```
        <source>Watch-only</source>
        <translation>Фақат кўришга</translation>
    
YES
The translation is in Cyrillic script, whereas the requested language tag 'uz@Latn' indicates Uzbek in Latin script. Also, the translation "Фақат кўришга" is incomplete and grammatically incorrect. A correct Latin-script Uzbek translation for "Watch-only" (in the Bitcoin context, meaning an address or wallet that can only be watched, not spent from) would be:

Faqat tomosha qilish uchun
```

```
        <source>to</source>
        <translation>Кимга</translation>
    
YES
The translation "Кимга" is in Cyrillic script, while the language code 'uz@Latn' specifies Uzbek in Latin script. Additionally, the source word "to" is very general and likely in the context of an address or direction, which in Uzbek Latin script should be rendered as "Kimga" (meaning "to whom") if that is the intended meaning. 

Correct translation:
Kimga
```

```
        <source>Send Coins</source>
        <translation>Тангаларни жунат</translation>
    
YES  
The translation includes Cyrillic script ("Тангаларни жунат") which does not conform to the 'uz@Latn' (Uzbek in Latin script) requirement. The translation should be in the Latin alphabet.

Correct translation:  
"Tangalarni jo'nat"
```

```
        <source>Insufficient funds</source>
        <translation>Кам миқдор</translation>
    
YES  
The translation is in Cyrillic script, but the requested language code 'uz@Latn' specifies Uzbek in Latin script. The correct translation in Latin script should be:  
Kam miqdor
```

```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Hamyonni qayta yozish kerak: bajarish uchun 1%s ni qayta ishga tushiring</translation>
    
YES  
The translation incorrectly places the format specifier '%s' as "1%s", which is erroneous. Also, the phrase "bajarish uchun" ("to execute") is inaccurate in this context; it should convey "to complete." The source means "restart %s to complete (the rewriting)." The correct translation should be clear and correctly position the format specifier without extra characters.

Correct translation:  
Hamyon qayta yozilishi kerak: yakunlash uchun %s ni qayta ishga tushiring
```
</details>
