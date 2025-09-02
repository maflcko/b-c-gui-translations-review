# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>uz@Cyrl</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Buz@Cyrl%5D%20request)


<!-- cache_translation_check_uz@Cyrl_a7d586a4e606592f1a4f671605d0231af75d7d7bba5de385de5ef5d92ab416a0 -->
```
        <source>Right-click to edit address or label</source>
        <translation>Манзил ёки ёрлиқни таҳрирлаш учун икки марта босинг</translation>
    
ERR
The translation is incorrect. The English phrase "Right-click to edit address or label" specifies using the right mouse button, whereas the translation says "Double-click to edit address or label" ("икки марта босинг" means "double-click"), which is an action with the left mouse button.

Correct translation:
Манзил ёки ёрлиқни таҳрирлаш учун ўнг тугмани босинг
```

<!-- cache_translation_check_uz@Cyrl_1e6c76fa9efccf7da27d515399ceca87c090391b6ec946cd60fcccf0acd3122d -->
```
        <source>Copy &amp;Label</source>
        <translation>Нусха олиш ва ёрлиқ</translation>
    
ERR
The translation is missing the required '&' shortcut marker and slightly misorders the phrase. The source is a single action "Copy &Label" (copy the label), so Uzbek (Cyrillic) should include the ampersand exactly once.

Correct translation (with & included):
Нусха олиш &Ёрлиқ
```

<!-- cache_translation_check_uz@Cyrl_73062f30966c6156c0858b5b56081c4c11a42eb4e97e4268b5f169f6a61786be -->
```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>Hamyon shifrini ochish uchun parol iborasi noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas). Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating.
</translation>
    
ERR
There are several problems with the translation:
- "birinchi null belgigacha bo'lgan qurilmalar bilan" is a mistranslation; "qurilmalar" means "devices", which is incorrect here.
- "lekin shu narsa emas" is vague and confusing.
- "Agar bu voqea bo'lsa, bu muammoni olish uchun yangi parol o'rnating." is ungrammatical and unclear.
- The original meaning about "up to — but not including — the first null character" is lost.

Correct translation:
Hamyonni shifrdan chiqarish uchun kiritilgan parol iborasi noto‘g‘ri. Unda null belgisi (ya’ni, nol bayt) mavjud. Agar parol iborasi ushbu dasturiy ta’minotning 25.0 versiyasidan oldinroq o‘rnatilgan bo‘lsa, iltimos, faqat birinchi null belgisigacha bo‘lgan belgilarni (lekin null belgisining o‘zini emas) kiriting va yana urinib ko‘ring. Agar muvaffaqiyatli bo‘lsa, kelajakda bu muammoga duch kelmaslik uchun yangi parol iborasini o‘rnating.
```

<!-- cache_translation_check_uz@Cyrl_2918ff4aee68e2055c1a85af021e51d3926cf0fb029abde3c5db3a4dd5066751 -->
```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Hamyon shifrini ochish uchun yordam eski parol noto'g'ri. U null belgini o'z ichiga oladi (ya'ni - nol bayt). Agar parol iborasi ushbu dasturiy ta'minotning 25.0 dan oldingi versiyasida o'rnatilgan bo'lsa, iltimos, faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas).</translation>
    
ERR
There are several issues with the translation:
- The translation uses 'yordam' unnecessary ("yordam eski parol noto'g'ri" should be "kirtilgan eski parol noto'g'ri").
- "faqat birinchi null belgigacha bo'lgan qurilmalar bilan qayta urinib ko'ring (lekin shu narsa emas)" is incorrect and confusing. "qurilmalar" means "devices" which is wrong; it should refer to the "characters" up to the first null character, not "devices".
- "lekin shu narsa emas" does not reflect "but not including".
- Overall, the text is somewhat unnatural and hard to follow in Uzbek Cyrillic.

Correct translation:
Ҳамённи декрипция қилиш учун киритилган эски парол нотўғри. У нол символини (яъни — нол байт) ўз ичига олади. Агар парол ибораси ушбу дастурий таъминотнинг 25.0 версиясидан олдинги версиясида ўрнатилган бўлса, илтимос, фақат биринчи нол белгигача бўлган (биринчи нол белгисини ҳисобга олмаган ҳолда) белгиларни киритиб қайта уриниб кўринг.
```

<!-- cache_translation_check_uz@Cyrl_5cc120eff65239f3f03c07ebe850f7e2dc20d4d270ac1981b6bb6bfc0e5f8315 -->
```
        <source>Banned Until</source>
        <translation>gacha kirish taqiqlanadi</translation>
    
ERR
The translation is inaccurate and awkward. "gacha kirish taqiqlanadi" translates back as "entry is prohibited until," which omits the noun "Banned" and can be unclear without context.

Correct translation:
Таъқиқланган сана

Alternatively, for clarity in the Bitcoin context:
Таъқиқланган муддат

Either is preferable.
```

<!-- cache_translation_check_uz@Cyrl_c410acb758314b160d6a38a7a7ed516964df2d5437a5f1438df8e258778b39b6 -->
```
        <source>Runaway exception</source>
        <translation>qo'shimcha istisno</translation>
    
ERR
The translation is inaccurate. "qo'shimcha istisno" means "additional exception" rather than "runaway exception". The intended meaning of "runaway exception" is an unhandled or unexpected exception that escapes control.

Correct translation:
Назоратдан чиққaн истиснo
```

<!-- cache_translation_check_uz@Cyrl_738c194333a9dc9ae7b284dd80e09bccc9cc35916b35dd054846621fc6a49f88 -->
```
        <source>&amp;About %1</source>
        <translation>&amp;%1 haqida</translation>
    
ERR
The translation is in Latin script ("&%1 haqida") but the target language variant is Uzbek in Cyrillic (uz@Cyrl). Also use of the word should be in Cyrillic. The format specifier %1 and the single & are correct.

Correct translation (Cyrillic):
&%1 ҳақида
```

<!-- cache_translation_check_uz@Cyrl_e9289e4e2c5757408854cdc614db2a8c19404e17671789a560426e32f438d3a5 -->
```
        <source>&amp;Minimize</source>
        <translation>&amp;Kichraytirish</translation>
    
ERR
The translation is in Uzbek Latin script, but the target language tag 'uz@Cyrl' requires Uzbek in Cyrillic script.

Correct translation (Uzbek Cyrillic) with the shortcut ampersand preserved:
&Кичрайтириш
```

<!-- cache_translation_check_uz@Cyrl_0aa3a34bc3751b0feeba39deb0736f33d9d2078e277c8189e652102493356917 -->
```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Паролни ўзгартириш ҳамённи кодлашда фойдаланилади</translation>
    
ERR
The translation does not accurately reflect the source. The Uzbek translation says "Changing the passphrase is used in encrypting the wallet," which is not the same as the instruction to "Change the passphrase used for wallet encryption." 

Correct translation:
Ҳамённи шифрлаш учун ишлатиладиган паролни ўзгартиринг
```

<!-- cache_translation_check_uz@Cyrl_953328dfd03b285285253f274bdd673fe31a643af2d38407125755981077e9fc -->
```
        <source>&amp;Options…</source>
        <translation>&amp;Sozlamalar...</translation>
    
ERR
The translation is in Latin script ("Sozlamalar...") but the target language variant is Uzbek Cyrillic (uz@Cyrl). Also the source uses a single Unicode ellipsis character (…) while the translation uses three ASCII dots (...). The ampersand is present correctly.

Correct translation (Cyrillic, with ampersand and Unicode ellipsis):
&Созламалар…
```

<!-- cache_translation_check_uz@Cyrl_37e337d634ecdad1aae4f72f5236c737d6e491544482fa1fc55fa5a54f06e724 -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation>&amp;Hamyonni shifrlash...</translation>
    
ERR
The translation is in Latin script Uzbek, but the requested locale 'uz@Cyrl' requires Cyrillic script. Also the source uses a single Unicode ellipsis (…), while the translation uses three ASCII dots. Maintain the & shortcut exactly once.

Correct translation (Cyrillic, with single ellipsis):
&amp;Ҳамённи шифрлаш…
```

<!-- cache_translation_check_uz@Cyrl_089ddbd9180f7f228b2267c44e0c5eb58a08453e6252a1f83d67b18c444e9025 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>&amp;Hamyon nusxasi...</translation>
    
SPAM
The translation is in Uzbek Latin script, but the requested language is Uzbek in Cyrillic (uz@Cyrl). Also the source uses a single Unicode ellipsis character; prefer matching that. 

Correct translation:
&amp;Ҳамён нусхаси…
```

<!-- cache_translation_check_uz@Cyrl_c95c366bde3c0d1ba896f6bbf76c67733caf00320e6182f9f032cad2f5f535f2 -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>&amp;Maxfiy so'zni o'zgartirish...</translation>
    
ERR
Translation is in Latin script (Uzbek Latin) rather than the requested Cyrillic script for 'uz@Cyrl'. Also it uses three ASCII dots (...) instead of the single Unicode ellipsis (…) and uses Latin-style apostrophes ('). 

Correct translation (Uzbek in Cyrillic), keeping the single & and the Unicode ellipsis:
&Макфий сўзни ўзгартириш…
```

<!-- cache_translation_check_uz@Cyrl_dbdc3990c2b1b8fa8dde4337dea36a096b374374a8d34f7ceb7b9a0616c2f53a -->
```
        <source>Sign &amp;message…</source>
        <translation>Xabarni &amp;signlash...</translation>
    
ERR
The translation uses Latin script and even an English-derived word ("signlash") instead of Uzbek in Cyrillic as required by 'uz@Cyrl'. Also ensure the ampersand (&) for the shortcut appears exactly once and the ellipsis is preserved.

Correct translation (Cyrillic Uzbek), keeping a single &:
Хабарни &имзолаш…
```

<!-- cache_translation_check_uz@Cyrl_d3c947c1f005a7f130f04f6d752f61807c2c57202a277193d0e0e008bba573e6 -->
```
        <source>&amp;Verify message…</source>
        <translation>&amp;Xabarni tasdiqlash...</translation>
    
ERR
The translation is in Latin script (Xabarni tasdiqlash...) but the locale 'uz@Cyrl' requires Cyrillic. Also the source uses a single Unicode ellipsis (…) while the translation uses three dots (...). The ampersand for the shortcut is present exactly once, which is correct.

Correct translation:
&amp;Хабарни тасдиқлаш…
```

<!-- cache_translation_check_uz@Cyrl_d01bffcf29fdf70c77c2e73c5905f697296116ab8eb11d0255e392208374e5b5 -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>&amp;PSBT ni fayldan yuklash...</translation>
    
ERR
The translation is in Uzbek Latin script, but the target locale 'uz@Cyrl' requires Cyrillic script. Also ensure spacing and the ampersand are preserved.

Correct translation (Uzbek, Cyrillic):
&amp;PSBT ни файлдан юклаш…
```

<!-- cache_translation_check_uz@Cyrl_eea3ab9fd2ad9e14d92bd212c29b0e879403a0b4ae9ebfb04152e8787f3fef09 -->
```
        <source>Open &amp;URI…</source>
        <translation>&amp;URL manzilni ochish</translation>
    
ERR
The translation is in Latin script and uses "URL" instead of "URI", and it omits the ellipsis. The target language variant requested is Uzbek in Cyrillic (uz@Cyrl), so the translation must be in Cyrillic script and preserve the & shortcut and the ellipsis.

Correct translation:
&URI манзилини очиш…
```

<!-- cache_translation_check_uz@Cyrl_ea7ee41489272cd603ea929b3b857c5998073c18ca99fc68b21a93da0a7dce18 -->
```
        <source>&amp;Settings</source>
        <translation>&amp; Созламалар</translation>
    
ERR
The translation has an extra space after the ampersand. The shortcut marker '&' must appear exactly once and directly before the label (no stray space). Also use a single ampersand character (not "&amp;" entity in plain text if the file expects '&').

Correct translation:
&Созламалар
```

<!-- cache_translation_check_uz@Cyrl_034a3b663750f19d590686c6a884c3c69eae99168fa588dd85945f57fb09a532 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>&amp;Nusxalanganlar dan PSBT ni yuklash</translation>
    
SPAM
The translation is in Latin script (Uzbek Latin) rather than the requested Cyrillic script (uz@Cyrl). Also the original has an ellipsis and the ampersand should appear exactly once.

Correct translation (Cyrillic Uzbek), preserving & and ellipsis:
&Буфердан PSBT ни юклаш…
```

<!-- cache_translation_check_uz@Cyrl_0faeb35a0c716ff0340069377b29c8af678b9c13f3b9f95b721f11388d60c89e -->
```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Nusxalanganlar qisman signlangan Bitkoin tranzaksiyalarini yuklash</translation>
    
ERR
The translation is inaccurate. The phrase "Nusxalanganlar" means "copied items", but the source refers to loading a partially signed Bitcoin transaction from the clipboard. It should more precisely mention "buferdan" for "from the clipboard" and "qisman imzolangan Bitkoin tranzaktsiyasini" for singular "transaction".

Correct translation:
Буфердан қисман имзоланган Биткоин транзакциясини юклаш
```

<!-- cache_translation_check_uz@Cyrl_db34aeab2308e1f8e29fa939a27860bb76cdac2c4adf387b16e91bf02eea5e4b -->
```
        <source>&amp;Sending addresses</source>
        <translation>&amp;Yuborish manzillari</translation>
    
ERR
The translation is in Latin script Uzbek, but the requested language variant is Uzbek in Cyrillic (uz@Cyrl). Use Cyrillic script. The ampersand is present exactly once, which is correct.

Correct translation:
&Юбориш манзиллари
```

<!-- cache_translation_check_uz@Cyrl_276dc42055f38b4f7db16e23d97ec2a8cb36029927bb29788357c429f5f65da6 -->
```
        <source>&amp;Receiving addresses</source>
        <translation>&amp;Qabul qilish manzillari</translation>
    
ERR
The translation is in Latin script Uzbek, but the requested language tag is Uzbek in Cyrillic (uz@Cyrl). Also ensure the shortcut marker (&) is present exactly once. 

Correct translation (Uzbek Cyrillic):
&amp;Қабул қилиш манзиллари
```

<!-- cache_translation_check_uz@Cyrl_297cc566c94a50d56fa5ef52884509c7ed463e913844f62c5f2c49269e2d1ff3 -->
```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
SPAM
The translation "dudlangan cho'chqa go'shti koʻchirish" means "smoked pork transfer" which is nonsensical and unrelated to the original source "Migrate Wallet". It is neither accurate nor in the correct context for a Bitcoin wallet.

Correct translation:
Ҳамённи кўчириш
```

<!-- cache_translation_check_uz@Cyrl_3a6d7eb6a8ac2c5db3c0576f1178460568316bfa9d1a0d6ed5af39348462042d -->
```
        <source>Ctrl+M</source>
        <translation>Abzatsga chek qo'ying.(Ctrl+M)</translation>
    
ERR
The translation "Abzatsga chek qo'ying.(Ctrl+M)" is incorrect. "Ctrl+M" is a keyboard shortcut and should not be localized or changed semantically. The translation adds unwanted content not present in the source ("Abzatsga chek qo'ying." means "Insert a check in the paragraph."), which misleads the user.

Correct translation:
Ctrl+M
```

<!-- cache_translation_check_uz@Cyrl_6ac76b6cd5780406c7b163304883a61880af8d2028d83d9f677f57fe1b423a7d -->
```
        <source>&amp;Hide</source>
        <translation>&amp;Yashirish</translation>
    
ERR
The translation is in Latin script ("&Yashirish") but the target language tag is Uzbek in Cyrillic (uz@Cyrl). Provide the translation in Cyrillic.

Correct translation:
&amp;Яшириш
```

<!-- cache_translation_check_uz@Cyrl_37d680f33c28d9f9971c59c9d101b7f3da33ea3004f0ec556f19fd9d29e243f4 -->
```
        <source>S&amp;how</source>
        <translation>Ko'&amp;rsatish</translation>
    
ERR
The translation is problematic: it's in Latin script with an apostrophe (Ko'&rsatish) rather than Uzbek Cyrillic as requested (uz@Cyrl). The ampersand exists but the script is wrong. Also the apostrophe form is not appropriate for Cyrillic.

Correct translation (Cyrillic, with one & for the shortcut):
&Кўрсатиш
```

<!-- cache_translation_check_uz@Cyrl_dac0647848b90704e4df6dacc855e8a92d7cdbeb9f4311a5117ccd090c5fdcf4 -->
```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini cheklash</translation>
    
ERR
The translation "Ijtimoiy tarmoq faoliyatini cheklash" translates to "Restrict social network activity," which is inaccurate. "Network" here refers to the Bitcoin network, not a social network. The translation should be more generic:

Correct translation:
Тармоқ фаолиятини ўчириш
```

<!-- cache_translation_check_uz@Cyrl_9ebea8d02c4cdc38ebc78557edf4a5362306747a6e739e41e31ba410b24b595e -->
```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>Ijtimoiy tarmoq faoliyatini yoqish</translation>
    
ERR
The translation incorrectly translates "network activity" as "Ijtimoiy tarmoq faoliyati", which means "social network activity". In the context of Bitcoin, "network" refers to the peer-to-peer/Bitcoin network, not social networks.

Correct translation:
Тармоқ фаолиятини ёқиш
```

<!-- cache_translation_check_uz@Cyrl_f236d60f9dd0daca28511b81631c8304947ae1eb51b0a5b4e586273357583744 -->
```
        <source>&amp;Copy address</source>
        <translation>&amp;Manzilni nusxalash</translation>
    
ERR
The translation is in Uzbek Latin script, but the requested locale is Uzbek in Cyrillic script (uz@Cyrl). Provide the translation in Cyrillic.

Correct translation:
&amp;Манзилни нусхалаш
```

<!-- cache_translation_check_uz@Cyrl_1f8d667e6a680c64c2a726d101e4ea40eb42105693e3bf1179e86a49469e78e7 -->
```
        <source>Copy &amp;label</source>
        <translation>&amp;Yorliqni nusxalash</translation>
    
ERR
The translation is in Latin script ("&Yorliqni nusxalash") but the target locale 'uz@Cyrl' requires Cyrillic. Also ensure the ampersand (&) appears exactly once — that's fine in the original but must be preserved.

Correct translation in Uzbek (Cyrillic), keeping a single &:
&Йорлиқни нусхалаш
```

<!-- cache_translation_check_uz@Cyrl_cc1218e51d4a2f62b9f7568d3bbf58c386966c6d935a2167a742cec933ce6559 -->
```
        <source>Copy &amp;amount</source>
        <translation>&amp;Miqdorni nusxalash</translation>
    
ERR
The translation is in Latin-script Uzbek, but the target language tag 'uz@Cyrl' requires Cyrillic script. Also ensure the ampersand appears exactly once (it does), but the script must be Cyrillic.

Correct translation (Cyrillic Uzbek) example:
&Миқдорни нусхалаш
```

<!-- cache_translation_check_uz@Cyrl_0b2c6f1d6655f19c9050749b99ad56bcf72d66a0b07574eecae1257320be6c85 -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>Tranzaksiya &amp;IDsi ni va chiquvchi indeksni nusxalash</translation>
    
ERR
The translation is in Uzbek Latin script and slightly awkward; the target language tag specifies Uzbek Cyrillic (uz@Cyrl). Also word order/inflection can be improved.

Correct translation in Uzbek (Cyrillic), keeping the single & before ID:
Транзакция &IDси ва чиқиш индексини нусхалаш
```

<!-- cache_translation_check_uz@Cyrl_4ba3d91578f7681a1e64f6c65000837dce852900fda9fb20fc9c662441c5d8b9 -->
```
        <source>L&amp;ock unspent</source>
        <translation>Sarflanmagan miqdorlarni q&amp;ulflash</translation>
    
ERR
The translation is in Latin script Uzbek, but the requested locale 'uz@Cyrl' requires Cyrillic script. Also give the shortcut (&) exactly once — that's fine in the candidate, but the script must be Cyrillic.

Correct translation (Cyrillic), keeping a single & for the shortcut:
Сарфланмаган миқдорларни қ&amp;улфлаш
```

<!-- cache_translation_check_uz@Cyrl_b091013308c7c571bca7fb23b1c008bf87eae9c6f0dc0d2fd62fc8cf2c650b42 -->
```
        <source>&amp;Unlock unspent</source>
        <translation>Sarflanmaqan tranzaksiyalarni &amp;qulfdan chiqarish</translation>
    
ERR
The translation is in Uzbek but written in Latin script; the requested locale 'uz@Cyrl' requires Cyrillic. Also ensure the shortcut marker (&) appears exactly once. 

Correct translation (Cyrillic, with one & as shortcut marker):
&Сарфланмаган транзакцияларни қулфдан чиқариш
```

<!-- cache_translation_check_uz@Cyrl_297cc566c94a50d56fa5ef52884509c7ed463e913844f62c5f2c49269e2d1ff3 -->
```
        <source>Migrate Wallet</source>
        <translation>dudlangan cho'chqa go'shti koʻchirish</translation>
    
SPAM
The translation "dudlangan cho'chqa go'shti koʻchirish" means "smoked pork transfer" which is nonsensical and unrelated to the original source "Migrate Wallet". It is neither accurate nor in the correct context for a Bitcoin wallet.

Correct translation:
Ҳамённи кўчириш
```

<!-- cache_translation_check_uz@Cyrl_5473bbbbf7aaef717b9ccb2a13f16fd4de3e90f07472aa6f57ca6dc1289984d8 -->
```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Watchonly skriptlari nomli yangi hamyonga ko'chirildi%1</translation>
    
ERR
The translation is inaccurate and has formatting issues. The placement of '%1' is incorrect, and the possessive meaning ("a new wallet named '%1'") is not conveyed. There should also be a space after "ko'chirildi".

Correct translation:
Watchonly skriptlar '%1' deb nomlangan yangi hamyonga ko‘chirildi.
```

<!-- cache_translation_check_uz@Cyrl_bfb589e93bc4618b36fbf6b512d4692a0db425dad5d8e9480115970b2491be02 -->
```
        <source>Open Wallet</source>
        <extracomment>Title of window indicating the progress of opening of a wallet.</extracomment>
        <translation>Hamyonni ochish</translation>
    
ERR
The translation is in Uzbek Latin script, but the requested locale is Uzbek Cyrillic (uz@Cyrl). The wording is otherwise correct in meaning.

Correct translation (Cyrillic):
Ҳамённи очиш
```

<!-- cache_translation_check_uz@Cyrl_0a5b602624e9e468f3d5fde7996d52803be53fdfd2c21e9ae095e98a7e744b0d -->
```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>Agar 'pruning' funksiyasi o'chirilgan bo'lsa, hamyondan uzoq vaqt foydalanmaslik butun zanjirnni qayta sinxronlashga olib kelishi mumkin.</translation>
    
ERR
The translation has an important error: it reverses the meaning of "if pruning is enabled" by translating it as "agar 'pruning' funksiyasi o'chirilgan bo'lsa" ("if the pruning function is disabled"). The source sentence means "if pruning is enabled" (yoqilgan, not o'chirilgan). There is also a small typo: "zanjirnni" should be "zanjirni".

Correct translation:
Agar 'pruning' funksiyasi yoqilgan bo'lsa, hamyonni juda uzoq vaqtga yopish butun zanjirni qayta sinxronlashtirishga olib kelishi mumkin.
```

<!-- cache_translation_check_uz@Cyrl_39bffa859bede978a407d2d7194a7cd3b1def2df9e2279c402dae209a2353b4e -->
```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Ushbu hamyon uchun maxfiy kalitlarni o'chirish. Maxfiy kalitsiz hamyonlar maxfiy kalitlar yoki import qilingan maxfiy kalitlar, shuningdek, HD seedlarga ega bo'la olmaydi.</translation>
    
ERR
The translation omits the part about being ideal for watch-only wallets. It also alters sentence structure and does not clearly convey that such wallets have no private keys and cannot have an HD seed or imported private keys. "HD seed" should be in quotes or explained, but it is acceptable to leave as-is if standard in local usage. The phrase "Maxfiy kalitsiz hamyonlar maxfiy kalitlar yoki import qilingan maxfiy kalitlar, shuningdek, HD seedlarga ega bo'la olmaydi." is a bit redundant.

Correct translation:
Ушбу ҳамён учун махфий калитларни ўчириб қўйиш. Махфий калитлари ўчирилган ҳамёнларда махфий калитлар, HD уруғ ёки импорт қилинган махфий калитлар бўлмайди. Бу фақат ўқув режимидаги (watch-only) ҳамёнлар учун идеал.
```

<!-- cache_translation_check_uz@Cyrl_60909a693f8f632d69ca5c9cfbffd4bbecb9867605c89f3d5b6a4811c2ebf389 -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Tashqi signing yordamisiz tuzilgan (tashqi signing uchun zarur)</translation>
    
ERR
The translation uses the English term "signing" instead of its proper Uzbek equivalent, and partial phrases are untranslated. Also, "Tashqi signing yordamisiz tuzilgan" is not natural or proper Uzbek in Cyrillic script.

Correct translation:
Ташқи имзо ёрдамисиз компиляция қилинган (ташқи имзолаш учун талаб қилинади)
```

<!-- cache_translation_check_uz@Cyrl_a773a2fb9c1c29d18c7e480879c8f2269ebb18a6ac024266c97e7f2ec888f640 -->
```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Yuboruvchi(%1manzil) va  qabul qiluvchi(%2manzil) bir xil bo'lishi mumkin emas</translation>
    
ERR  
The translation is inaccurate and omits essential information from the source. The original specifies that the address "%1" already exists as a receiving address with label "%2" and therefore cannot be added as a sending address. The translation instead roughly says: "Sender (%1 address) and receiver (%2 address) cannot be the same," which is not the same as the original sentence and loses important context.

Correct translation:
Манзил "%1" аллақачон "%2" ёрлиғи билан қабул қилиш манзили сифатида мавжуд, шунинг учун уни юбориш манзили сифатида қўшиб бўлмайди.
```

<!-- cache_translation_check_uz@Cyrl_520508b7de677dc7b3047a2030d5be455288823033089e489a3325cc22a5d639 -->
```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>OK ni bosganingizda, %1to'liq blok zanjirini (%2GB) yuklab olish%4 va qayta ishlash boshlanadi, %3birinchi boshlangan%4 tranzaksiyalardan boshlab.</translation>
    
ERR
The translation has several issues:

1. Incorrect order and placement of format specifiers (%1, %2, %3, %4).
2. Missing spaces between words and after format specifiers (e.g., '%1to\'liq', '%2GB').
3. The structure does not match the source, leading to confusion.
4. The sentence is not very clear and partially omits meaning.

Correct translation:
OK тугмасини босганингизда, %1 %3 да %4 илк марта ишга тушган пайтдаги энг эрта транзакциялардан бошлаб, тўлиқ %4 блокчейнини (%2 ГБ) юклаб олиш ва қайта ишлашни бошлайди.
```

<!-- cache_translation_check_uz@Cyrl_cb673f65f58cc336ca4940911f502929cf0f1bae65712ded6965d300948c4a24 -->
```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Noma'lum. Sarlavhalarni oldindan sinxronlash (, %1%2%)…</translation>
    
ERR
The word order of the format specifiers (%1, %2%) is incorrect, as they are together in the translation (,%1%2%), and the comma is misplaced. Also, "%2%" should be "%2%" (the percent sign is attached), but in the source, the comma and percent are not unified. The translation omits "Unknown" and the rest is literal.

Correct translation:
Номаълум. Сарлавҳаларни олдиндан синхронлаш (%1, %2%)…
```

<!-- cache_translation_check_uz@Cyrl_582ea3461ff481264a1373b04cdce959bb530158cabe386c309d54e9210ecbe1 -->
```
        <source>&amp;Start %1 on system login</source>
        <translation>%1 ni sistemaga kirish paytida &amp;ishga tushirish</translation>
    
ERR
The translation is Uzbek but written in Latin script; the requested locale 'uz@Cyrl' requires Cyrillic script. Also ensure the %1 specifier and single & are preserved.

Correct translation in Uzbek (Cyrillic):
%1ни системага кириш пайтида &ишга тушириш
```

<!-- cache_translation_check_uz@Cyrl_e264875aa2d0181d8435998524cf18031b88fdaa0b06cae8efcf9381e1e30baf -->
```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Do'kon tranzaksiyalari katta xotira talab qilgani tufayli pruning ni yoqish sezilarli darajada xotirada joy kamayishiga olib keladi. Barcha bloklar hali ham to'liq tasdiqlangan. Bu sozlamani qaytarish butun blok zanjirini qayta yuklab olishni talab qiladi.</translation>
    
ERR
The translation is mostly accurate but contains issues:
- "Do'kon tranzaksiyalari katta xotira talab qilgani tufayli" translates as "Due to store transactions requiring large memory," which is not a correct or natural way to express the original English sentence. The sentence is not clear and appears to mistranslate the purpose of pruning.
- "store transactions" should be translated as to "store transactions data" or "saqlash uchun" but the current translation inserts "do'kon" which means "store" as in a shop, not "to store".
- The subject is misrepresented: the pruning option reduces the disk space needed to store the blockchain, not because of "do'kon tranzaksiyalari".

Correct translation:
Транзакциялар тарихини сақлаш учун талаб қилинадиган диск ҳажмини кескин камайтириш учун pruning (кесиш) функциясини ёқиш тавсия этилади. Барча блоклар ҳамон тўлиқ тасдиқланади. Бу настройкани бекор қилиш бутун блокчейнни қайта ёзиб олишни талаб қилади.
```

<!-- cache_translation_check_uz@Cyrl_3be5d29cdb249c25f4998099ad3dd7fdad7f3933e3553abd3608a06179fed178 -->
```
        <source>Size of &amp;database cache</source>
        <translation>&amp;Маълумотлар базаси кеши</translation>
    
ERR
The translation omits the notion of "Size of" (ҳажми / ўлчами). The ampersand exists exactly once, which is fine, but the phrase is incomplete.

Correct translation:
&amp;Маълумотлар базаси кеши ҳажми
```

<!-- cache_translation_check_uz@Cyrl_28d0342ade65576d8638bf40d5d550bee5f9929eeadb74f8e201837c45b12b7d -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>Мавзуларни &amp;тўғрилаш скрипти миқдори</translation>
    
ERR
The translation is incorrect and awkward in Uzbek (Cyrillic). "Мавзуларни" means "topics" and the word order/terms are wrong. The source means "Number of script verification threads" (i.e. number of threads used to verify scripts). Also ensure the & shortcut appears exactly once.

Suggested correct translation:
Скрипт &текшириш йўналишлари сони
```

<!-- cache_translation_check_uz@Cyrl_93b6a6b4e1d2b41765cd0dc50b3e0671fbf9c36071c68546f5d7e24a5ae825e2 -->
```
        <source>&amp;Reset Options</source>
        <translation>Sozlamalarni &amp;qayta o'rnatish</translation>
    
ERR
The translation is in Latin-script Uzbek ("Sozlamalarni qayta o'rnatish") rather than Cyrillic as requested for 'uz@Cyrl'. Also it uses an ASCII apostrophe for "o'rnatish" instead of the Cyrillic letter "ў". The shortcut marker (&) must appear exactly once; your translation shows "&amp;" entity but that is acceptable when rendered, however the script mismatch is the main issue.

Correct translation in Uzbek Cyrillic with a single & for the shortcut (placed before the first word):
&Созламаларни қайта ўрнатиш
```

<!-- cache_translation_check_uz@Cyrl_b64883cea4191fdc04f53a50a13defbcbc3bb11df8964f6cd1e477331f33198d -->
```
        <source>&amp;Network</source>
        <translation>Тармоқ</translation>
    
ERR
The source contains a single '&' to mark the shortcut key, but the translation omits it. Also ensure no extra spaces are added.

Correct translation (include '&' exactly once), for example:
&amp;Тармоқ
```

<!-- cache_translation_check_uz@Cyrl_acc770a04a274fddb912f9a3aff63a29e610d5e7c3f76f217cc445b99f968a27 -->
```
        <source>Prune &amp;block storage to</source>
        <translation>&amp;Blok xotirasini bunga kesish:</translation>
    
ERR
The translation is in Latin-script Uzbek ("Blok xotirasini bunga kesish:") while the locale requests Uzbek in Cyrillic (uz@Cyrl). A colon was also added though the source has none.

Correct translation in Uzbek Cyrillic (keep the & shortcut, no extra colon):
&Блок хотирасини чегаралаш
```

<!-- cache_translation_check_uz@Cyrl_6ad88ee4d8fdc63e07b5e6939b98b4c12c99e1c3c77745c622921ab88163e7bb -->
```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>Skriptni tekshirish ip lari sonini belgilang. </translation>
    
ERR
The translation is incomplete and omits the explanation about negative values. Additionally, "ip lari" should be "ipлари" in proper Cyrillic Uzbek, and "belgilang." (set) is appropriate, but the sentence must be fully translated.

Correct translation:
Скриптни текшириш иплари сонини белгиланг. Манфий қийматлар тизимга бўш қолдирмоқчи бўлган ядролар сонига тўғри келади.
```

<!-- cache_translation_check_uz@Cyrl_2590721b103bc9023ade4b23d25a6ab3d4246a5f882db293ce72bd0f4c36e516 -->
```
        <source>Enable R&amp;PC server</source>
        <extracomment>An Options window setting to enable the RPC server.</extracomment>
        <translation>R&amp;PC serverni yoqish</translation>
    
ERR
The translation is in Uzbek but uses Latin script ("R&amp;PC serverni yoqish") while the target language tag is uz@Cyrl (Uzbek Cyrillic). Also the word form should use the Cyrillic case ending and Cyrilic spelling for "enable". Keep the ampersand exactly once.

Correct translation (Uzbek, Cyrillic):
R&amp;PC серверини ёқиш
```

<!-- cache_translation_check_uz@Cyrl_7360ffbd1b1b3c7d75d2ee3da7f031fccedceaa640a4e6222fe7e7452a10492f -->
```
        <source>W&amp;allet</source>
        <translation>Ҳамён</translation>
    
ERR
The translation is correct Uzbek (Cyrillic) for "Wallet" but it omits the shortcut ampersand (&) present in the source. The source contains a single & (W&amp;allet) and the translation must also contain exactly one &.

Correct translation (with one &):
&Ҳамён
```

<!-- cache_translation_check_uz@Cyrl_0101022453d88b3baa7d30d27580774b9f7897570038d7697bc0a120a624f6b9 -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Standart bo'yicha chegirma belgilash</translation>
    
ERR
Problems:
- The translation is in Latin script (uses "Standart bo'yicha...") but the requested locale is uz@Cyrl (Cyrillic).
- The meaning is imprecise: the source says "Subtract &fee from amount by default" (make subtracting the fee from the sent amount the default behavior), while the translation reads more like "set a discount by default".
- The shortcut marker '&' is missing; the source contains "&fee" so the translation must include exactly one '&'.

Suggested correct translation (Cyrillic, includes single & for the shortcut):
Стандарт бўйича &комиссияни суммадан айириш
```

<!-- cache_translation_check_uz@Cyrl_3c7651a3fb05c25597a58598f4ece07d2f3ae710e1c44cf7f3073319940ad058 -->
```
        <source>Enable coin &amp;control features</source>
        <translation>Tangalarni &amp;nazorat qilish funksiyasini yoqish</translation>
    
ERR
The translation is in Uzbek but written in Latin script while the tag 'uz@Cyrl' requires Cyrillic. Also "funksiyasini" is singular; the source says "features" (plural).

Correct translation (Cyrillic, with single & placed once):
Тангаларни &назорат қилиш функцияларини ёқиш
```

<!-- cache_translation_check_uz@Cyrl_449ddecc2e34f530426e7800cc8ea912099c2f092c6ca77e38ec8231c02e0e11 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>Tasdiqlanmagan oʻzgarishlarni &amp;sarflash</translation>
    
ERR
The translation is in Uzbek Latin script (uses "Tasdiqlanmagan oʻzgarishlarni &sarflash") but the requested locale is Uzbek in Cyrillic (uz@Cyrl). Correct translation in Cyrillic:

Тасдиқланмаган ўзгаришларни &сарфлаш
```

<!-- cache_translation_check_uz@Cyrl_becaac9b2d42913c31b712a7f2ea5aa66d63507bedbaed983b2aeda41b21ec04 -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>&amp;PSBT nazoratini yoqish</translation>
    
SPAM
The translation is in Uzbek Latin script, but the target language tag 'uz@Cyrl' requires Uzbek in Cyrillic. Correct translation in Uzbek Cyrillic (keeping the shortcut & once):

&PSBT назоратларини ёқиш
```

<!-- cache_translation_check_uz@Cyrl_241540e72bcb494d2c8851b95c5ad2ea06d96538c2bf102d6c8d761242432aec -->
```
        <source>&amp;External signer script path</source>
        <translation>&amp;Tashqi signer skripti yo'li</translation>
    
ERR
The translation is in Latin-script Uzbek, but the target locale specifies Cyrillic (uz@Cyrl). Also the English word "signer" was left as-is; it's acceptable as a loanword but should be in Cyrillic. Ampersand is present and correct.

Correct translation (Uzbek, Cyrillic):
&amp;Ташқи имзоловчи скрипти йўли
```

<!-- cache_translation_check_uz@Cyrl_51dae1c4c9d5307ed7b84ce5bc2a33dbcbf2d99118d963b06520eac20425248b -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Kiruvchi va kirish ulanishlariga ruxsat bering</translation>
    
ERR
The provided translation is in Latin script, not Uzbek Cyrillic as requested, and it lacks the single & shortcut marker from the source. Also use the correct Cyrillic spelling for "руҳсат".

Correct translation:
&Кирувчи уланишларга руҳсат беринг
```

<!-- cache_translation_check_uz@Cyrl_0fb48d2f7cf1429e96ef0d02b5a165bbb186e0b3fda91bee264ef425cc3876bf -->
```
        <source>&amp;Connect through SOCKS5 proxy (default proxy):</source>
        <translation>SOCKS5 proksi-server orqali ulaning (standart proksi-server):</translation>
    
ERR
Problems:
- The translation is in Latin script, but the target tag 'uz@Cyrl' requires Uzbek in Cyrillic script.
- The ampersand (&) indicating the shortcut is missing; the source has exactly one & and the translation must include it once.
- Minor wording: duplicate "proksi-server" phrasing can be streamlined.

Suggested correct translation (Cyrillic, includes & once):
&amp;SOCKS5 прокси орқали уланг (стандарт прокси):
```

<!-- cache_translation_check_uz@Cyrl_7ebfc5a3196cf1ee1f347a3ab5b5d56ed5e0ea7f00dc37f8f034fbee070c1565 -->
```
        <source>&amp;Show tray icon</source>
        <translation> belgisini ko'rsatish</translation>
    
ERR
Problems:
- The translation is in Latin script, but the target requested is Uzbek in Cyrillic (uz@Cyrl).
- The leading space before the text is stray whitespace.
- The shortcut ampersand (&) from the source is missing; it must appear exactly once.

Correct translation (Uzbek Cyrillic), with & included and no extra spaces:
&amp;Трей иконкасини кўрсатиш
```

<!-- cache_translation_check_uz@Cyrl_81976e189b79778b052c13f35c3d762daa60a1279e08258b289bba46ad15a7b5 -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>Манзиллар панели ўрнига трэйни &amp;йиғиш</translation>
    
ERR
The translation uses "Манзиллар панели" which means "addresses panel" and is incorrect for "taskbar". Also word choice could be improved for natural Uzbek (Cyrillic). The ampersand is present exactly once, which is fine.

Suggested correct translation:
Вазифалар панели ўрнига трэйга &кичрайтириш
```

<!-- cache_translation_check_uz@Cyrl_65d7dd83131b153850001f2356a993d4290b9022a62b034c27c93adaa8871bf4 -->
```
        <source>M&amp;inimize on close</source>
        <translation>Ёпишда й&amp;иғиш</translation>
    
ERR
The translation uses the wrong word ("йиғиш" means "gathering/collecting") and so is inaccurate. Also "Ёпишда" is nonstandard; the common UI phrasing is "Ёпилганда" (when closing) and a more accurate verb for "minimize" is "кичиклаштириш".

Correct translation:
<translation>Ёпилганда &кичиклаштириш</translation>
```

<!-- cache_translation_check_uz@Cyrl_0e3ca61ef9b4b3d222e835e420dadd119cd2a055958ea7dcce6cad35adaf389e -->
```
        <source>&amp;Unit to show amounts in:</source>
        <translation>Миқдорларни кўрсатиш учун &amp;қисм:</translation>
    
ERR
The translation uses "қисм" ("part/section") which is not the correct term for "unit" in this context. It should use "бирлик" (unit). The ampersand is present exactly once, which is fine.

Correct translation:
Миқдорларни кўрсатиш учун &бирлик:
```

<!-- cache_translation_check_uz@Cyrl_f6bcef256d66bb4146ae322885a60a8dd9abe7564173e7a83f301a3f9ffaa847 -->
```
        <source>&amp;Third-party transaction URLs</source>
        <translation>&amp;Uchinchi tomon tranzaksiyalari URL manzillari</translation>
    
ERR
The translation is correct Uzbek but written in Latin script. The requested language tag 'uz@Cyrl' requires Cyrillic script. The ampersand is present exactly once (OK). No format specifiers to check.

Correct translation in Uzbek Cyrillic (with ampersand):
&Учинчи томон транзакциялари URL манзиллари
```

<!-- cache_translation_check_uz@Cyrl_9155fc0281101c62a593fdc88e2abc380c2a0429747180108a443f038607d207 -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Tor onion xizmatlari orqali tengdoshlar bilan bog'lanish uchun alohida SOCKS&amp;5 proksi-serveridan foydalaning:</translation>
    
ERR
The translation is in Uzbek but written in Latin script; the requested locale 'uz@Cyrl' requires Uzbek in Cyrillic script. The content and meaning are otherwise fine and the & (SOCKS&amp;5) is preserved.

Correct translation in Uzbek (Cyrillic):
Tor onion хизматлари орқали тенгдошлар билан боғланиш учун алоҳида SOCKS&amp;5 прокси-серверидан фойдаланинг:
```

<!-- cache_translation_check_uz@Cyrl_60909a693f8f632d69ca5c9cfbffd4bbecb9867605c89f3d5b6a4811c2ebf389 -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Tashqi signing yordamisiz tuzilgan (tashqi signing uchun zarur)</translation>
    
ERR
The translation uses the English term "signing" instead of its proper Uzbek equivalent, and partial phrases are untranslated. Also, "Tashqi signing yordamisiz tuzilgan" is not natural or proper Uzbek in Cyrillic script.

Correct translation:
Ташқи имзо ёрдамисиз компиляция қилинган (ташқи имзолаш учун талаб қилинади)
```

<!-- cache_translation_check_uz@Cyrl_c32cd0ba982faa29ddde042e81219974897f9e371d8c7da996e751c22464e60b -->
```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Жами ўтказмалар ҳозиргача тасдиқланган ва сафланадиган баланс томонга ҳали ҳам ҳисобланмади</translation>
    
ERR
The translation misrepresents the original meaning. The source refers to transactions that are "unconfirmed" and not yet included in the spendable balance. However, the translation roughly says, "Total transactions have been confirmed so far and have not yet been counted toward the spendable balance," which is inaccurate.

Correct translation:
Тасдиқланмаган ва ҳали сарфланадиган балансга қўшилмаган ўтказмаларнинг умумий сони
```

<!-- cache_translation_check_uz@Cyrl_d1a781ed64e043bfde41b29f13f270376ccf23d892abd89573657eea3202979f -->
```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>"Umumiy ko'rinish" yorlig'i uchun maxfiylik rejimi faollashtirilgan. Qiymatlarni qaytarish uchun Sozlamalar-&gt;Qiymatlar.</translation>
    
ERR
The translation is missing the instruction to "uncheck" (i.e., to remove the check from) "Settings-&gt;Mask values." The phrase "Qiymatlarni qaytarish uchun Sozlamalar-&gt;Qiymatlar." is incomplete and unclear. Also, quotation marks style is inconsistent.

Correct translation:
"Умумий кўриниш" ёрлиғи учун махфийлик режими фаоллаштирилди. Қийматларни кўриш учун "Созламалар-&gt;Қийматларни ниқоблаш" танловидан белгини олиб ташланг.
```

<!-- cache_translation_check_uz@Cyrl_51e0e582a0a1eb654dd898fd98c00e02e811efa7c2af9dacb1d777a1fa98db43 -->
```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>Hamyon maʼlumotlarga imzo qoʻyib boʻlmaydi.</translation>
    
ERR
The translation is inaccurate and omits key information. The source says that inputs cannot be signed while the wallet is locked, but the translation merely says "Cannot sign wallet data" and does not mention the wallet being locked or that it's the "inputs" that cannot be signed.

Correct translation:
Hamyon qulflanganida kirish maʼlumotlariga imzo qoʻyib boʻlmaydi.
```

<!-- cache_translation_check_uz@Cyrl_c6a0843bc324a45401dd945cdb67a42f3d1d669af03338b375ccedd3dff49178 -->
```
        <source>URI handling</source>
        <translation>URI осилиб қолмоқда</translation>
    
ERR
The translation is problematic. "URI осилиб қолмоқда" translates as "URI is being processed" or "URI is being handled (right now)", which does not accurately represent "URI handling" as a general concept, menu, or feature title. "Осилиш" also can be awkward in this context.

Correct translation:
URIни қўллаш  
or
URI билан ишлаш

Either of these translations captures the intended meaning of "URI handling" as the name of a function or procedure.
```

<!-- cache_translation_check_uz@Cyrl_ef91a7eaf88d2be145131d8332eca6b62c115c709639b593331f51700a4b25e2 -->
```
        <source>Client version</source>
        <translation>Мижоз номи</translation>
    
ERR
The translation "Мижоз номи" means "Client name" in Uzbek Cyrillic, which does not accurately reflect "Client version". The correct translation should be "Мижоз версияси".

Correct translation:
Мижоз версияси
```

<!-- cache_translation_check_uz@Cyrl_803398c68a3af7e959ef140dd81d6b165b6f273578b6cb107c9eb20e62a14ea4 -->
```
        <source>&amp;Peers</source>
        <translation>&amp;Уламлар</translation>
    
ERR
"Уламлар" is not a correct Uzbek (Cyrillic) rendering for "Peers". The ampersand is present and there are no spacing issues, but the word is erroneous.

Suggested correction:
&Ҳамкасблар
```

<!-- cache_translation_check_uz@Cyrl_a29a79170ef2c3ba79c3582dcf1a5db5b0d24382012e5137f6c7e22a980962d3 -->
```
        <source>&amp;Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>&amp;Manzilni nusxalash</translation>
    
ERR
The translation is in Latin-script Uzbek ("Manzilni nusxalash") but the requested language tag is uz@Cyrl (Uzbek in Cyrillic). Also ensure the ampersand shortcut is present exactly once — it is present but must precede the Cyrillic text.

Correct translation:
&amp;Манзилни нусхалаш
```

<!-- cache_translation_check_uz@Cyrl_f236d60f9dd0daca28511b81631c8304947ae1eb51b0a5b4e586273357583744 -->
```
        <source>&amp;Copy address</source>
        <translation>&amp;Manzilni nusxalash</translation>
    
ERR
The translation is in Uzbek Latin script, but the requested locale is Uzbek in Cyrillic script (uz@Cyrl). Provide the translation in Cyrillic.

Correct translation:
&amp;Манзилни нусхалаш
```

<!-- cache_translation_check_uz@Cyrl_1f8d667e6a680c64c2a726d101e4ea40eb42105693e3bf1179e86a49469e78e7 -->
```
        <source>Copy &amp;label</source>
        <translation>&amp;Yorliqni nusxalash</translation>
    
ERR
The translation is in Latin script ("&Yorliqni nusxalash") but the target locale 'uz@Cyrl' requires Cyrillic. Also ensure the ampersand (&) appears exactly once — that's fine in the original but must be preserved.

Correct translation in Uzbek (Cyrillic), keeping a single &:
&Йорлиқни нусхалаш
```

<!-- cache_translation_check_uz@Cyrl_cc1218e51d4a2f62b9f7568d3bbf58c386966c6d935a2167a742cec933ce6559 -->
```
        <source>Copy &amp;amount</source>
        <translation>&amp;Miqdorni nusxalash</translation>
    
ERR
The translation is in Latin-script Uzbek, but the target language tag 'uz@Cyrl' requires Cyrillic script. Also ensure the ampersand appears exactly once (it does), but the script must be Cyrillic.

Correct translation (Cyrillic Uzbek) example:
&Миқдорни нусхалаш
```

<!-- cache_translation_check_uz@Cyrl_fa8dcf46e73efd34860d56026abcbad60c4fb6e08301cfbe63fae53676b7b0b2 -->
```
        <source>Copy &amp;Address</source>
        <translation>Нусҳалаш &amp; Манзил</translation>
    
ERR
Word order and spacing are awkward. The ampersand should appear exactly once as the shortcut marker and should not have stray spaces around it. Better natural Uzbek (Cyrillic) translations:

Correct translation:
&amp;Манзилни нусҳалаш
```

<!-- cache_translation_check_uz@Cyrl_b2b33d8d8fe78b0d3b275c304b4d314449b62091d2bc0e75ab23274d19696e45 -->
```
        <source>Insufficient funds!</source>
        <translation>Кам миқдор</translation>
    
ERR
The translation "Кам миқдор" ("Low amount") is inaccurate. The original English "Insufficient funds!" should reflect that there is not enough money, not just a "low amount." Also, the exclamation mark is missing.

Correct translation:
Етарли маблағ йўқ!
```

<!-- cache_translation_check_uz@Cyrl_69cfe6ac949fe030edf56b124b5263d0a68c3ff17ca4d1bf842900766bb5d8bc -->
```
        <source>Custom change address</source>
        <translation>Бошқа ўзгартирилган манзил</translation>
    
ERR
The translation "Бошқа ўзгартирилган манзил" is problematic. "Custom change address" in the Bitcoin context refers to an address specified by the user to receive the change from a transaction, not just any "other changed address". The word "change" here is technical and means "қайтим" (return/change in money). Also, "Бошқа" means "other" rather than "custom".

Correct translation:
Махсус қайтим манзили
```

<!-- cache_translation_check_uz@Cyrl_ea13dc9434a8577a7d395c09faf8822edacc4e9b73818e40bed115b23c233d20 -->
```
        <source>Clear &amp;All</source>
        <translation>Барчасини &amp; Тозалаш</translation>
    
ERR
Problems:
- The ampersand (&) is separated from the word by a space ("&amp; Тозалаш"); it should be immediately before the character that becomes the shortcut and appear exactly once.
- Word order/word choice is awkward for Uzbek; "Барчасини тозалаш" or more commonly "Ҳаммасини тозалаш" is better.

Correct translation suggestions (ampersand placed immediately before the first word, encoded as &amp;):
- &amp;Барчасини тозалаш
or
- &amp;Ҳаммасини тозалаш
```

<!-- cache_translation_check_uz@Cyrl_ea13dc9434a8577a7d395c09faf8822edacc4e9b73818e40bed115b23c233d20 -->
```
        <source>Clear &amp;All</source>
        <translation>Барчасини &amp; Тозалаш</translation>
    
ERR
Problems:
- The ampersand (&) is separated from the word by a space ("&amp; Тозалаш"); it should be immediately before the character that becomes the shortcut and appear exactly once.
- Word order/word choice is awkward for Uzbek; "Барчасини тозалаш" or more commonly "Ҳаммасини тозалаш" is better.

Correct translation suggestions (ampersand placed immediately before the first word, encoded as &amp;):
- &amp;Барчасини тозалаш
or
- &amp;Ҳаммасини тозалаш
```

<!-- cache_translation_check_uz@Cyrl_6cdc4967baaf4f2ceb59370bf2a92f7f257bf568c9e105d320fc624789d13a62 -->
```
        <source>true</source>
        <translation>рост</translation>
    
ERR
The translation is problematic. 'рост' means 'growth' in Russian, and is not correct for 'true'. The correct 'uz@Cyrl' translation for 'true' is 'тўғри' or 'рост' could also be intended in Uzbek, but this word is more likely perceived as the Russian 'growth'. The more standard and clear translation is 'тўғри'.

Correct translation:
тўғри
```

<!-- cache_translation_check_uz@Cyrl_220ad3b5b35cc67f7264dd800ad6f48a3f1b3d2bee30f5a8e38bedc26f9ff137 -->
```
        <source>Received from</source>
        <translation>Дан қабул қилиш</translation>
    
ERR
The translation "Дан қабул қилиш" literally means "to receive from", but in this context it is incorrect. "Received from" typically would refer to showing the sender/source, e.g., "Received from [address]". The correct 'uz@Cyrl' translation should be more like "Кимдан қабул қилинди" or "Қабул қилинган манба". "Дан қабул қилиш" sounds like an infinitive verb, not the noun phrase needed for interface text.

Correct translation:
Кимдан қабул қилинди
```

<!-- cache_translation_check_uz@Cyrl_6d71982060e7b380b3e784bbf9bd45229f16d9f1b8524cf8d3864d410b038b76 -->
```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
ERR
The translation "Жўнатиш" means "to send" (infinitive) in Uzbek Cyrillic, not "Sent to", which implies an action completed and usually specifies the recipient. A more accurate translation would be "Жўнатилди" (sent) or "Қуйидагига жўнатилди" (sent to [recipient]).

Correct translation:
Жўнатилди
```

<!-- cache_translation_check_uz@Cyrl_12ff85ecf961641f2a58858a345acd5ac1338f0f8ed3b417d3213f908c601ebb -->
```
        <source>Mined</source>
        <translation>Фойда</translation>
    
ERR
The translation is inaccurate. "Мined" refers to "Казиб олинган" or "Қазиб олинган" (mined), whereas "Фойда" means "profit", which is incorrect in this context.

Correct translation:
Қазиб олинган
```

<!-- cache_translation_check_uz@Cyrl_8fa63031947fc50136b2540c73602ef8ea9fc2801ca8c4d8b29b9207c5677172 -->
```
        <source>Last month</source>
        <translation>Ўтган хафта</translation>
    
ERR
The translation is incorrect. The source says "Last month" ("ўтган ой" in Uzbek Cyrillic), but the translation says "Ўтган хафта", which means "Last week".

Correct translation:
Ўтган ой
```

<!-- cache_translation_check_uz@Cyrl_6d71982060e7b380b3e784bbf9bd45229f16d9f1b8524cf8d3864d410b038b76 -->
```
        <source>Sent to</source>
        <translation>Жўнатиш</translation>
    
ERR
The translation "Жўнатиш" means "to send" (infinitive) in Uzbek Cyrillic, not "Sent to", which implies an action completed and usually specifies the recipient. A more accurate translation would be "Жўнатилди" (sent) or "Қуйидагига жўнатилди" (sent to [recipient]).

Correct translation:
Жўнатилди
```

<!-- cache_translation_check_uz@Cyrl_12ff85ecf961641f2a58858a345acd5ac1338f0f8ed3b417d3213f908c601ebb -->
```
        <source>Mined</source>
        <translation>Фойда</translation>
    
ERR
The translation is inaccurate. "Мined" refers to "Казиб олинган" or "Қазиб олинган" (mined), whereas "Фойда" means "profit", which is incorrect in this context.

Correct translation:
Қазиб олинган
```

<!-- cache_translation_check_uz@Cyrl_f236d60f9dd0daca28511b81631c8304947ae1eb51b0a5b4e586273357583744 -->
```
        <source>&amp;Copy address</source>
        <translation>&amp;Manzilni nusxalash</translation>
    
ERR
The translation is in Uzbek Latin script, but the requested locale is Uzbek in Cyrillic script (uz@Cyrl). Provide the translation in Cyrillic.

Correct translation:
&amp;Манзилни нусхалаш
```

<!-- cache_translation_check_uz@Cyrl_1f8d667e6a680c64c2a726d101e4ea40eb42105693e3bf1179e86a49469e78e7 -->
```
        <source>Copy &amp;label</source>
        <translation>&amp;Yorliqni nusxalash</translation>
    
ERR
The translation is in Latin script ("&Yorliqni nusxalash") but the target locale 'uz@Cyrl' requires Cyrillic. Also ensure the ampersand (&) appears exactly once — that's fine in the original but must be preserved.

Correct translation in Uzbek (Cyrillic), keeping a single &:
&Йорлиқни нусхалаш
```

<!-- cache_translation_check_uz@Cyrl_cc1218e51d4a2f62b9f7568d3bbf58c386966c6d935a2167a742cec933ce6559 -->
```
        <source>Copy &amp;amount</source>
        <translation>&amp;Miqdorni nusxalash</translation>
    
ERR
The translation is in Latin-script Uzbek, but the target language tag 'uz@Cyrl' requires Cyrillic script. Also ensure the ampersand appears exactly once (it does), but the script must be Cyrillic.

Correct translation (Cyrillic Uzbek) example:
&Миқдорни нусхалаш
```
</details>

Number of issues: 92.
