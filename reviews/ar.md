# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bar%5D%20request)



<details><summary>ar</summary>


<!-- cache_translation_check_ar_acd2d60576ab14a19d03963efa11e1988ce22fa2fbf42f485fe63877de4de84e -->
```
        <source>&amp;New</source>
        <translation> &amp;جديد</translation>
    
ERR
There is an extra space at the beginning of the translation string before "&amp;جديد", which introduces a formatting issue. The translation itself is accurate, and the shortcut marker is present, but remove the stray leading space.

Correct translation:
&amp;جديد
```

<!-- cache_translation_check_ar_4e503aeb3045014e622f5924857f9ac96da283690b2bd93e0f66fffe19311a60 -->
```
        <source>Enter address or label to search</source>
        <translation>أدخل عنوانا أو مذكرة للبحث</translation>
    
ERR
"مذكرة" تعني "ملاحظة" وليست "label". الأنسب استخدام "تسمية" أو "تصنيف".

Correct translation:
أدخل عنوانًا أو تسمية للبحث
```

<!-- cache_translation_check_ar_2e87ff2c1744878ce1997efa95bb3131051535165cf434d02b1ed6ba16f061c9 -->
```
        <source>Copy the currently selected address to the clipboard</source>
        <translation>آدرس انتخاب شده فعلی را در کلیپ بورد کپی کنید</translation>
    
SPAM
The provided text is in Persian (Farsi), not Arabic.

Correct translation:
انسخ العنوان المحدد حاليًا إلى الحافظة
```

<!-- cache_translation_check_ar_d46494b3566d148f2738acd52d5217c6dbb45f2411e9efee6021a65fc44221ce -->
```
        <source>&amp;Export</source>
        <translation>&amp; يصدّر</translation>
    
ERR
There is an unnecessary space after the '&' shortcut key indicator. Also, in Arabic software interfaces, the noun "تصدير" is the standard translation for the "Export" action, whereas "يصدّر" is a verb meaning "he exports".

Correct translation:
&تصدير
```

<!-- cache_translation_check_ar_7c97b2a962531ef2d373b1d7043759b1329b4dbb33442b831cf28ec7e7513192 -->
```
        <source>&amp;Delete</source>
        <translation>حذف</translation>
    
ERR
The translation is missing the shortcut marker '&' that exists in the source and should appear exactly once in the translation.

Correct translation:
&حذف
```

<!-- cache_translation_check_ar_77225fd64429b52d34d2c650057ee52b59e6605ac6d1ab98a247dd2cc3fe91b0 -->
```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>هذه هي العناوين الخاصة بها بك. استخدم زر "إنشاء عنوان استقبال جديد" في علامة استلام البريد الإلكتروني عناوين جديدة.التوقيع ممكن فقط مع عناوين نوع "إرث" .</translation>
    
ERR
The Arabic text contains multiple issues: incorrect pronouns ("بها بك"), missing mention of Bitcoin and receiving payments, incorrect reference to "email," missing verb ("لإنشاء"), spacing errors, and an unsuitable translation of "legacy." 

Correct translation:
هذه هي عناوين البيتكوين الخاصة بك لتلقي المدفوعات. استخدم زر «إنشاء عنوان استلام جديد» في تبويب الاستلام لإنشاء عناوين جديدة.
لا يمكن التوقيع إلا باستخدام العناوين من النوع «Legacy».
```

<!-- cache_translation_check_ar_4fa3b370d87f6fd1099a8705e6eebfad895ff775e85af3296c34f579c2c1822a -->
```
        <source>Unlock wallet</source>
        <translation>Active </translation>
    
SPAM
The translation is in English ("Active") instead of Arabic, has the wrong meaning, and includes a trailing space.
Correct translation:
إلغاء قفل المحفظة
```

<!-- cache_translation_check_ar_da342c09df94d95a3eadf3dcdf8687ebf5e6ba8d5fc07b564eabd7ea71756f79 -->
```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>‫موصل طابق‬</translation>
    
ERR
The translation "موصل طابق" is incorrect and does not convey the meaning of "Block Relay" in the context of Bitcoin. "موصل" could mean "connector," and "طابق" means "floor," which is unrelated. The correct translation should convey the function of relaying blocks in a network.

Correct translation:
ترحيل الكتل
```

<!-- cache_translation_check_ar_d5a73cca1b4510941a75890091f651bccb8d99399d501ab9ccddfc567449264b -->
```
        <source>E&amp;xit</source>
        <translation>خروج</translation>
    
ERR
The translation omits the '&' shortcut indicator present in the source. For Arabic, a common way to represent a menu shortcut is to add '&' before the relevant letter, e.g., '&خروج' or 'خ&روج', where the position determines the access key.

Correct translation:
&خروج

Alternatively (if the shortcut should be on the second letter, which is less common in Arabic, but possible):
خ&روج
```

<!-- cache_translation_check_ar_67ca78ddd25c4e2c3e22b4e52c3493dc49f9e731fc0bca0c4a49595127863185 -->
```
        <source>&amp;About %1</source>
        <translation>حوالي %1</translation>
    
ERR
The shortcut key indicator '&' is missing in the Arabic translation. It must appear exactly once, as in the source.

Correct translation:
&حول %1
```

<!-- cache_translation_check_ar_f33b545d1cfc67d573995e25a93dc6fdf24582d625b5cc76e1c1c9b689a7dddb -->
```
        <source>Show information about Qt</source>
        <translation>اظهر المعلومات</translation>
    
ERR
The translation "اظهر المعلومات" means "Show the information" but omits any reference to "Qt". The translation should include "Qt" to match the source meaning.

Correct translation:
اعرض معلومات حول Qt
```

<!-- cache_translation_check_ar_bb2ebd1a5a0c2d47e1827afb35464995efdc6b83667c128bac6f60bf2dec1a22 -->
```
        <source>Modify configuration options for %1</source>
        <translation>تغيير خيارات الإعداد لأساس ل%1</translation>
    
ERR
The translation contains an error in phrasing and word choice. "لأساس ل%1" is incorrect Arabic and doesn't make sense in this context. The correct translation should maintain the intended structure and clarity.

Correct translation:
تعديل خيارات التكوين لـ %1
```

<!-- cache_translation_check_ar_99e3797d217e5853ca59445a64553151be578550131083fcf49cb4c77d7cacf3 -->
```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>%1 اتصال نشط بشبكة البيتكوين</translation>
    
ERR
The Arabic translation does not accurately reflect the source text. The source states "Proxy is <b>enabled</b>: %1", but the translation says "%1 اتصال نشط بشبكة البيتكوين", which translates back as "%1 active connection to the Bitcoin network", which is a different meaning.

Correct translation:
الوكيل <b>مفعل</b>: ‏%1
```

<!-- cache_translation_check_ar_99f59890f9f3bfaad974ed0fb1e7a7530d9eb69618f271d178ac1bbc5bec61f8 -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation>&amp; تشفير المحفظة</translation>
    
ERR
There is an unnecessary space after the ampersand (&) in the Arabic translation, and the ellipsis (…) is missing. The ampersand (&) should directly precede the letter designating the shortcut, with no extra space, and the ellipsis should be included.

Correct translation:
&تشفير المحفظة…
```

<!-- cache_translation_check_ar_1403b25869cc651ec4588bf2e79be6e9f896e71853a3c802a2b3cb146a692337 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>&amp; محفظة احتياطية</translation>
    
ERR
There is an extra space after the ampersand in the Arabic translation ("& محفظة احتياطية"). The ampersand should directly precede the shortcut key (which should be an Arabic letter corresponding to the shortcut). Also, "محفظة احتياطية" translates to "Backup Wallet" as a noun ("a backup wallet"), rather than the imperative "Backup Wallet..." (the action to back up the wallet). A better translation for the menu action would be "نسخ احتياطي للمحفظة..." or "النسخ الاحتياطي للمحفظة...". The ellipsis (…) is also missing in the translation.

Correct translation:
&نسخ احتياطي للمحفظة…
```

<!-- cache_translation_check_ar_983e61f8022d364bd354d11ad77cd54147a1cf4ed16e754e62f97570793a47de -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>وتغيير العبارات...</translation>
    
ERR
The translation is incorrect for several reasons:
- The ampersand (&) indicating the shortcut key is missing.
- The wording does not correctly reflect "Change Passphrase"; it says "and change the phrases..." instead of "Change passphrase".
- No need to add "وتغيير"; it should start directly.
- The correct translation for "Change Passphrase…" is: "تغيير كلمة المرور..." or "تغيير عبارة المرور...". 
- The shortcut key "&" must also appear, for example: "&تغيير عبارة المرور..."

Correct translation:
&تغيير عبارة المرور...
```

<!-- cache_translation_check_ar_cfd9cab9b35e705ef8a0966ac5772c977513bdf998d403d984aa94eec3c79a43 -->
```
        <source>Sign &amp;message…</source>
        <translation>علامة ورسالة...</translation>
    
ERR
The Arabic translation is inaccurate. "علامة" means "sign" as in a physical sign or symbol, not "to sign (digitally)". Additionally, the ampersand (&) indicating a shortcut is missing from the Arabic translation. An accurate translation for "Sign &message…" in the context of Bitcoin should be "وقّع &الرسالة...".

Correct translation:
وقّع &الرسالة...
```

<!-- cache_translation_check_ar_562228a9ccfcbcc228c898e9fe0ad3f9fdc5374213d59600c00b222816dacff3 -->
```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>وقَع الرسائل بواسطة ال: Bitcoin الخاص بك لإثبات امتلاكك لهم</translation>
    
ERR
The translation has several issues:
- "Bitcoin" should be translated as "عناوين البيتكوين" ("your Bitcoin addresses"), not left in English, to match the context.
- The phrase structure is awkward and not idiomatic Arabic.
- The usage of "ال:" and "لهم" (which means "them", masculine plural) does not match the subject ("addresses").
- The verb "وقَع" should use the imperative "وقّع".
- There is an unnecessary colon and spacing issue.

Correct translation:
وقّع الرسائل بواسطة عناوين البيتكوين الخاصة بك لإثبات ملكيتك لها
```

<!-- cache_translation_check_ar_829ee959565521c306a384dc376cfd84b636474e1c0d2b8d79eb043a8f5fe491 -->
```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>تحقق من الرسائل للتأكد من أنَها وُقعت برسائل Bitcoin محدَدة</translation>
    
ERR
The translation is incorrect. It says "...that they were signed with specified Bitcoin messages" instead of "specified Bitcoin addresses". The word "رسائل" (messages) is used instead of "عناوين" (addresses).

Correct translation:
تحقق من الرسائل للتأكد من أنها وُقعت باستخدام عناوين بيتكوين محددة
```

<!-- cache_translation_check_ar_73df0568a679a4c34f4cb2c9741f5ce1c7480556db6638ab08f23f5b9529e9e8 -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>وتحميل PSBT من ملف...</translation>
    
ERR
The ampersand (&) indicating the shortcut key is missing in the Arabic translation, and the ellipsis should use Arabic-friendly formatting (… instead of ...).

Correct translation:
&amp;تحميل PSBT من ملف…
```

<!-- cache_translation_check_ar_1a2b6dfaadd85ade8ba2828e7e79b6f1cef9fab753440c19f51062bdc8649148 -->
```
        <source>Open &amp;URI…</source>
        <translation>فتح ورابط...</translation>
    
ERR
The translation omits the "&" keyboard shortcut marker, so the shortcut functionality is lost. Also, "ورابط" should be "رابط" (removing the "و" for "and"), as the original English does not use "and". The ellipsis "…" is also replaced by three periods "...", which is less correct.

Correct translation:
افتح &رابط…
```

<!-- cache_translation_check_ar_14ca9bea9b43e756a7b14057a2f7abf6fc6e055bee5cfebffcd910b94330b39f -->
```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>أطلب دفعات (يولد كودات الرمز المربع وبيت كوين: العناوين المعطاة)</translation>
    
ERR
The Arabic translation is unnatural and contains some inaccuracies. "كودات الرمز المربع" is a literal and clunky way to describe QR codes, and "العناوين المعطاة" (given addresses) is an incorrect translation for "URIs". In the context of Bitcoin, "bitcoin: URIs" should be kept as "روابط bitcoin:".

Correct translation:
طلب مدفوعات (يولد رموز استجابة سريعة "QR" وروابط bitcoin:)
```

<!-- cache_translation_check_ar_89f172e2f6a63a087cb90c0de2ec6404af348be645b23bd077bd508aae61d312 -->
```
        <source>Catching up…</source>
        <translation>يمسك…</translation>
    
ERR
The translation "يمسك…" is a literal translation of "catching" in the sense of physically grabbing something. In the context of software or Bitcoin syncing, "Catching up" refers to the process of synchronized data updating.

Correct translation:
جاري التحديث…
```

<!-- cache_translation_check_ar_9f2cb69e286a3e417ae73e6ec1dd0d0dcb24b4e04162c927dfd99cebc4309cf4 -->
```
        <source>Transactions after this will not yet be visible.</source>
        <translation>المعاملات بعد ذلك لن تكون مريئة بعد.</translation>
    
ERR
The translation contains a spelling error in the word "مرئية" (visible). The word used in the translation is "مريئة", which is incorrect in this context.

Correct translation:
المعاملات بعد ذلك لن تكون مرئية بعد.
```

<!-- cache_translation_check_ar_430ec446175a775969ed0971f5cfdff6117be4414232838159e0088428ba7214 -->
```
        <source>Date: %1
</source>
        <translation>التاريخ %1
</translation>
    
ERR
The translation is missing the colon (:) present in the source text. In Arabic, a colon is used similarly to English to separate a label from its value.

Correct translation:
التاريخ: %1
```

<!-- cache_translation_check_ar_161b139e36599f28dd87a2bb03920871f170730b2639c2c09c3d5b25bd447d83 -->
```
        <source>Amount: %1
</source>
        <translation>القيمة %1
</translation>
    
ERR
The translation is missing the colon (:) that is present in the source text. For UI consistency, punctuation should be preserved. Additionally, "المبلغ" is often a more specific term for a monetary "Amount" in Arabic Bitcoin contexts.

Correct translation:
القيمة: %1
(or)
المبلغ: %1
```

<!-- cache_translation_check_ar_2bbce8068728d9c5aff99b1d59b8dd944948a9fd12d704e0a23952ab79b34ce8 -->
```
        <source>Wallet: %1
</source>
        <translation>المحفظة:  %1
</translation>
    
ERR
The translation contains a double space after the colon, whereas the source text only has a single space.

Correct translation:
المحفظة: %1
```

<!-- cache_translation_check_ar_110fdb2d8f0a24b7c4e0d57dbd831ffd9691c71d59e8dff15946209f58f4261f -->
```
        <source>Type: %1
</source>
        <translation>النوع %1
</translation>
    
ERR
The translation is missing the colon (:) present in the source text. In technical strings, punctuation such as colons should be preserved for consistency.

Correct translation:
النوع: %1
```

<!-- cache_translation_check_ar_213f2524a26a29755cb5f954a3255eb0c46eb9577e4d517b7d7523f77cb5da49 -->
```
        <source>Address: %1
</source>
        <translation>العنوان %1
</translation>
    
ERR
The translation is missing the colon (:) present in the source text. In technical strings, punctuation should be preserved for consistency.

Correct translation:
العنوان: %1
```

<!-- cache_translation_check_ar_310f1fc87a8f9007f493c7404461eae7d35069619eb50fe5a8026112e0f4e095 -->
```
        <source>Sent transaction</source>
        <translation>‫العمليات المرسلة‬</translation>
    
ERR
The translation is in the plural form ("Sent transactions"), while the source text is in the singular form ("Sent transaction").

Correct translation:
عملية مرسلة
```

<!-- cache_translation_check_ar_0ee7b23767eea891d2674cdbe45bdd1b38ea46abb5e470cb3957b21edfa0516c -->
```
        <source>Incoming transaction</source>
        <translation>‫العمليات الواردة‬</translation>
    
ERR
The translation is in the plural form ("Incoming transactions"), while the source text is singular ("Incoming transaction").

Correct translation:
عملية واردة
```

<!-- cache_translation_check_ar_864c32a78e4280763e9ff7200571c264b559a9c5750d1c178ffd9e41de12a283 -->
```
        <source>Change:</source>
        <translation>تعديل:</translation>
    
ERR
The translation of "Change:" as "تعديل:" is incorrect. In the context of Bitcoin, "Change" refers to the "change amount", not "modification".

Correct translation:
الباقي:
```

<!-- cache_translation_check_ar_130b1027c4b260d2b229d8c4600d823c3709bbf9a403c45ad79ff56c3e4117b0 -->
```
        <source>Received with label</source>
        <translation>‫استُلم وله مذكرة‬</translation>
    
ERR
The Arabic translation "استُلم وله مذكرة" is inaccurate. "مذكرة" means "note" or "memo," while "label" in the context of Bitcoin addresses refers to a "label" or "اسم" used to identify the address. The translation should use a term meaning "label" rather than "memo."

Correct translation:
استلم مع تسمية
```

<!-- cache_translation_check_ar_c048c0acbd1de655661fc15981fb21a45afc73867424bbbd5731ad14b99b3be6 -->
```
        <source>Copy &amp;label</source>
        <translation>‫نسخ &amp;مذكرة‬</translation>
    
ERR
The word "label" should be translated as "تسمية" in Arabic, not "مذكرة" which means "note" or "memo." The ampersand (&amp;) is present correctly.

Correct translation:
‫نسخ &amp;تسمية‬
```

<!-- cache_translation_check_ar_7d9877f1fe48898281786c2f68cafdb14d061cddf3fd1fda9076d86ea5855693 -->
```
        <source>L&amp;ock unspent</source>
        <translation>قفل غير منفق</translation>
    
ERR
The ampersand (&) is used in the source to indicate a shortcut key. It is missing in the Arabic translation. The ampersand (&) should appear exactly once in the translation, at an appropriate character for a shortcut.

Correct translation:
&قفل غير منفق

Or, if a different character is chosen for the shortcut:
قفل &غير منفق
```

<!-- cache_translation_check_ar_d48b0a5e8dff9531b0135327efc1f5a6ae7866ba35a1a82964c8935dacc701da -->
```
        <source>&amp;Unlock unspent</source>
        <translation>&amp; إفتح غير المنفق</translation>
    
ERR
There is an unnecessary space after the ampersand (&amp;), resulting in a formatting issue. In Arabic UI, there should be no space between "&amp;" and the beginning of the translation, to ensure the shortcut key works correctly.

Correct translation:
&إفتح غير المنفق
```

<!-- cache_translation_check_ar_9628dcface294799c793232dcf1b3a8a88d12d2f00fde25a11b91114f75a048d -->
```
        <source>Copy change</source>
        <translation>نسخ التعديل</translation>
    
ERR
"التعديل" means "modification," not "change" in the Bitcoin sense (returned remainder of a transaction). The correct term is "الباقي".

Correct translation:
نسخ الباقي
```

<!-- cache_translation_check_ar_260c1ea6e09e3f82d2be31fbc5ce411226cf8cca85a5d27f594b11f1f1982763 -->
```
        <source>(change)</source>
        <translation>(تغير)</translation>
    
ERR
The Arabic word "تغير" translates to "change" as in transformation or alteration, which is not the correct meaning in the context of Bitcoin transactions. The correct term is "الباقي" or "الفكة" (which refers to the "change" amount returned in a transaction).

Correct translation:
(الباقي)
or
(الفكة)
```

<!-- cache_translation_check_ar_a4d7ae7b92cdd368a527ad08ca0ee0b9dcdb859e9e61c993adf012435dca79a4 -->
```
        <source>Open Wallet</source>
        <extracomment>Title of window indicating the progress of opening of a wallet.</extracomment>
        <translation>افتح المحفظة</translation>
    
ERR
The translation uses the imperative form "افتح المحفظة" ("Open the wallet"), which is inappropriate for a progress window title. It should be a verbal noun indicating an ongoing action.

Correct translation:
فتح المحفظة
```

<!-- cache_translation_check_ar_4e9274d0557972702526e7c1756247833ce9b05fef37bb5ea0cfb34c5ead1063 -->
```
        <source>Wallet Name</source>
        <translation>إسم المحفظة</translation>
    
ERR
The Arabic word for "name" should be written without hamza: "اسم", not "إسم".

Correct translation:
اسم المحفظة
```

<!-- cache_translation_check_ar_ac6bb9e2dd49c6dbcb4e2f87722e2ad27dfca75b1cd211fbfd7cb89330c096f3 -->
```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>العنوان المرتبط بقائمة العناوين المدخلة. و التي يمكن تعديلها فقط بواسطة ارسال العناوين</translation>
    
ERR
The translation of the second sentence is inaccurate. "بواسطة ارسال العناوين" translates to "by sending the addresses" or "via sending addresses," whereas the source text "for sending addresses" refers to the category of addresses used for sending.

Correct translation:
العنوان المرتبط بمدخل قائمة العناوين هذا. يمكن تعديل هذا فقط لعناوين الإرسال.
```

<!-- cache_translation_check_ar_7089d941f5e8ed855014522086bc4c6e06a5c35bc6f4ff4207390c43f6f83592 -->
```
        <source>Edit receiving address</source>
        <translation>تعديل عنوان الأستلام</translation>
    
ERR
The word "الأستلام" contains an orthographic error. The initial Alif in "استلام" is a Hamzat Wasl (همزة وصل) and should not have a Hamza (ء) written on it.

Correct translation:
تعديل عنوان الاستلام
```

<!-- cache_translation_check_ar_d5a2000163396481eb776c52a76d4db0a584f21bf334ac03e9094621e098708c -->
```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>العنوان المدخل  "%1" موجود بالفعل في سجل العناوين تحت مسمى " "%2".</translation>
    
ERR
The translation contains a double space after "المدخل" and a stray double quotation mark before "%2".

Correct translation:
العنوان المدخل "%1" موجود بالفعل في سجل العناوين تحت مسمى "%2".
```

<!-- cache_translation_check_ar_0eb2e17f8d6f1e01d994a831729a6d58f0fb6d772e34b7a97d662cff736b51e9 -->
```
        <source>Could not unlock wallet.</source>
        <translation> يمكن فتح المحفظة.</translation>
    
ERR
The translation provides the opposite meaning of the source text. The Arabic text "يمكن فتح المحفظة" translates to "The wallet can be opened," whereas the source text "Could not unlock wallet" indicates a failure to unlock it.

Correct translation:
تعذر إلغاء قفل المحفظة.
```

<!-- cache_translation_check_ar_5250b2819c7542e4cdb2a0a4a938db4b528ba7531cd1b8134eac196aa06ca893 -->
```
        <source>Prune &amp;block storage to</source>
        <translation>‫اختصار &amp;تخزين الطابق</translation>
    
ERR
The translation of "block" as "الطابق" is incorrect; "الطابق" means "floor" in Arabic, not "block". In the context of Bitcoin, "block" is best translated as "كتلة". Also, the phrase structure is awkward.

Correct translation:
‫اختصار &amp;تخزين الكتلة إلى‬
```

<!-- cache_translation_check_ar_495319ba1a424742a2bbae2b412fb71aa4c99abc713209d973a05446bcdd4dec -->
```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>‫العودة الى هذا الاعداد تتطلب إعادة تنزيل الطوابق المتتالية بالكامل.‬</translation>
    
ERR
The translation is problematic. The phrase "الطوابق المتتالية" translates to "sequential floors", which is incorrect in the context of blockchain. The correct translation for "blockchain" is "سلسلة الكتل". Also, "Reverting" should be better reflected.

Correct translation:
تتطلب إعادة هذا الإعداد إعادة تحميل سلسلة الكتل بالكامل.
```

<!-- cache_translation_check_ar_f6b8646fb7da1d160423aa3720a0fabe945baefe747826ad57728752e85c3b3e -->
```
        <source>MiB</source>
        <translation>‫ميجابايت‬</translation>
    
ERR
"MiB" stands for mebibyte (2^20 bytes), but the translation says "ميجابايت" (megabyte, MB). This is inaccurate.

Correct translation:
ميبيبايت
```

<!-- cache_translation_check_ar_b151013fd091e3bc3b1ecb9dd2c976cc61861d3fc7af287e9825f76f650ae963 -->
```
        <source>(0 = auto, &lt;0 = leave that many cores free)</source>
        <translation>‫(0 = تلقائي, &lt;0 = لترك أنوية حرة بقدر الرقم السالب)‬</translation>
    
ERR
The translation includes extraneous directional control characters and the phrasing is slightly awkward. Also, using the Arabic comma improves readability.

Correct translation:
(0 = تلقائي، <0 = ترك هذا العدد من الأنوية حرة)
```

<!-- cache_translation_check_ar_0b3c44a6dbb86df3b677e6e68026dfcd5a368b5cf7d802d69e770a8220121418 -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>‫اخصم &amp;الرسوم من القيمة بشكل افتراضي‬</translation>
    
ERR
The translation includes hidden directional marks and uses "القيمة" instead of the more accurate "المبلغ" for "amount." Also, a neutral label (not imperative) fits checkbox text better.

Correct translation:
خصم &الرسوم من المبلغ افتراضيًا
```

<!-- cache_translation_check_ar_57e07e1469d82dde40bdadf9e3dace9ba916731d2f1025157c2fb1df81ed74bd -->
```
        <source>Expert</source>
        <translation>‫خبير‬</translation>
    
ERR
The Arabic translation contains invisible bidirectional formatting marks (e.g., RLE/PDF), which can cause rendering or layout issues. The correct, clean translation is:
خبير
```

<!-- cache_translation_check_ar_47659c42c0a1c976686e6ad93c4f2804260dacaf3eb0f5061b82021e7ce9f5ca -->
```
        <source>If you disable the spending of unconfirmed change, the change from a transaction cannot be used until that transaction has at least one confirmation. This also affects how your balance is computed.</source>
        <translation>‫اذا قمت بتعطيل خيار الانفاق من الفكة الغير مؤكدة، لن يكون بمقدورك التحكم بتلك الفكة حتى تنْفُذ العملية وتحصل على تأكيد واحد على الأقل. هذا أيضا يؤثر على كيفية حساب رصيدك.‬</translation>
    
ERR
- Uses colloquial "الفكة" and ungrammatical "الغير مؤكدة" (should be "غير المؤكدة").
- Adds inaccurate condition "حتى تنفذ العملية" not present in the source.
- Contains stray RTL embedding marks.

Correct translation:
إذا عطّلت إنفاق التغيير غير المؤكَّد، فلن يمكن استخدام مبلغ التغيير من معاملة ما حتى تحصل تلك المعاملة على تأكيد واحد على الأقل. يؤثر هذا أيضًا في كيفية احتساب رصيدك.
```

<!-- cache_translation_check_ar_f74729c9b24affb2a3aba73b5e92739027ef3e6314469856d6a34a1ee0155468 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>‫&amp;دفع الفكة غير المؤكدة‬</translation>
    
ERR
The translation is too colloquial ("الفكة") and uses "دفع" (pay) instead of the more accurate "إنفاق" (spend). It also includes directional control characters that are unnecessary and may cause formatting issues.

Correct translation:
&إنفاق الباقي غير المؤكد
```

<!-- cache_translation_check_ar_3efb5e03c5f32c26869f908c7a6aac60e33fce2ab77c6adc1c3b4c711f08bdfb -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>‫تفعيل التحكم ب &amp;المعاملات الموقعة جزئيا‬</translation>
    
ERR
Issues:
- Replaced the PSBT acronym with a descriptive phrase; better to keep the standard term "PSBT".
- Incorrect spacing: "ب &المعاملات" separates the preposition from the word.
- Singular "التحكم" used instead of the common UI term "عناصر تحكم" for "controls".
- Contains an unnecessary directional mark at the start.

Correct translation:
تفعيل عناصر تحكم &PSBT
```

<!-- cache_translation_check_ar_6d461f26c543594a04a26631f34282e608fa3e07041a1fdcc629ba1bed078c5f -->
```
        <source>External Signer (e.g. hardware wallet)</source>
        <translation>‫جهاز التوقيع الخارجي (مثل المحفظة الخارجية)‬</translation>
    
ERR
"hardware wallet" was mistranslated as "المحفظة الخارجية" (external wallet), which changes the meaning. Also, unnecessary bidi/formatting marks appear. 

Correct translation:
موقّع خارجي (مثل محفظة أجهزة)
```

<!-- cache_translation_check_ar_c47cc1da315134a13bdef1730bf4676053ebcf75e7014f7313c6bfe5fbc184de -->
```
        <source>&amp;External signer script path</source>
        <translation>&amp; مسار البرنامج النصي للموقّع الخارجي</translation>
    
ERR
The accelerator marker '&' is followed by a space, which breaks the shortcut and constitutes a whitespace issue. It should directly precede a character.

Correct translation:
&مسار البرنامج النصي للموقّع الخارجي
```

<!-- cache_translation_check_ar_efab53f2de1b63321fec53d3f8c82b03764a012a2c32cb187b81987cb7a8a459 -->
```
        <source>&amp;Connect through SOCKS5 proxy (default proxy):</source>
        <translation>الاتصال من خلال وكيل SOCKS5 (الوكيل الافتراضي):</translation>
    
ERR
The translation is missing the shortcut marker (&) that exists exactly once in the source. This is required for UI consistency and accessibility.

Correct translation:
&amp;الاتصال من خلال وكيل SOCKS5 (الوكيل الافتراضي):
```

<!-- cache_translation_check_ar_738f48c716933bcb53cc846e4d5f0304645eb4130edb07ff7eefd1df60847f15 -->
```
        <source>&amp;Unit to show amounts in:</source>
        <translation>‫وحدة لعرض القيم:‬</translation>
    
ERR
The ampersand (&), which indicates a shortcut key, is missing in the Arabic translation. It must appear exactly once. Also, the literal translation for "Unit to show amounts in:" is correct, but keeping the ampersand is necessary for UI consistency.

Correct translation:
‫وحدة لعرض القيم (&):‬
```

<!-- cache_translation_check_ar_7e071688e9eece38a3076d6a6f6da1d3530587de61c588e0b85b5bc40de0c4ec -->
```
        <source>Third-party URLs (e.g. a block explorer) that appear in the transactions tab as context menu items. %s in the URL is replaced by transaction hash. Multiple URLs are separated by vertical bar |.</source>
        <translation>‫عناوين أطراف أخرى (مثل: مستكشف الطوابق) تظهر في النافذة المبوبة للعمليات كخيار في القائمة المنبثقة. %s في الرابط تُستبدل بمعرف التجزئة. سيتم فصل العناوين بخط أفقي |.‬</translation>
    
ERR
There are a few issues:
- "block explorer" should be translated as "مستكشف الكتل" rather than "مستكشف الطوابق".
- "context menu items" is better translated as "عناصر قائمة السياق".
- "transactions tab" should be "علامة تبويب المعاملات".
- "vertical bar" is preferably "شريط عمودي" or simply "الرمز |".
- "العمليات" is not as precise as "المعاملات" for "transactions".
- The translation uses "خط أفقي" for "vertical bar", which is incorrect; it should be "شريط عمودي" or just indicate the symbol.

Correct translation:
عناوين الأطراف الثالثة (مثل: مستكشف الكتل) التي تظهر في علامة تبويب المعاملات كعناصر في قائمة السياق. يُستبدل %s في الرابط بمعرّف تجزئة المعاملة. تُفصل العناوين المتعددة بالرمز العمودي |.
```

<!-- cache_translation_check_ar_330d65cddc3559ca2f0d629224b2278c407c801864933e6c29011136463e657d -->
```
        <source>&amp;Cancel</source>
        <translation>الغاء</translation>
    
ERR
The translation omits the '&' character, which is used for the shortcut key and must appear exactly once in both source and translation.

Correct translation:
&إلغاء
```

<!-- cache_translation_check_ar_cd24994f23395b088e44741784ca73fc97cb348ec00dcf7fad444d36980d1095 -->
```
        <source>Current settings will be backed up at "%1".</source>
        <extracomment>Text explaining to the user that the client's current settings will be backed up at a specific location. %1 is a stand-in argument for the backup location's path.</extracomment>
        <translation>‫سيتم النسخ الاحتياطي للاعدادات على “%1”.‬".</translation>
    
ERR
The translation has an extra stray double quote at the end, and there is a preference for using "في" (at/in) rather than "على" (on) when referring to a location in Arabic. Also, the sentence starts with an LTR quote and ends with an RTL quote, which can be visually inconsistent.

Correct translation:
سيتم نسخ الإعدادات الحالية احتياطيًا في "%1".
```

<!-- cache_translation_check_ar_cd5ebd9c12ed9ff66e2a0f11e9b876ccaec141ebd7261cfb6ab2bf601e091400 -->
```
        <source>own address</source>
        <translation>عنوانه</translation>
    
ERR
The translation "عنوانه" means "his address," which is incorrect and gendered. The correct Arabic translation for "own address" is "عنوانك" if addressing singular "you," or "عنوانك الخاص" for a more general "your own address." If the context refers to "your own address" in the UI, then "عنوانك" or "عنوانك الخاص" is best.

Correct translation:
عنوانك
or
عنوانك الخاص
```

<!-- cache_translation_check_ar_a6dca1005a4fa9c4178cdfbaab9b59e910c033044f2f38de32d88a535d9985be -->
```
        <source>Copy &amp;label</source>
        <translation>‫نسخ &amp;اضافة مذكرة‬</translation>
    
ERR
The Arabic translation changes the meaning: "إضافة مذكرة" means "add note," not "label." It also contains bidi control characters. The shortcut ampersand is fine but should be kept with the correct term.

Correct translation:
نسخ &التسمية
```

<!-- cache_translation_check_ar_864c32a78e4280763e9ff7200571c264b559a9c5750d1c178ffd9e41de12a283 -->
```
        <source>Change:</source>
        <translation>تعديل:</translation>
    
ERR
The translation of "Change:" as "تعديل:" is incorrect. In the context of Bitcoin, "Change" refers to the "change amount", not "modification".

Correct translation:
الباقي:
```

<!-- cache_translation_check_ar_9628dcface294799c793232dcf1b3a8a88d12d2f00fde25a11b91114f75a048d -->
```
        <source>Copy change</source>
        <translation>نسخ التعديل</translation>
    
ERR
"التعديل" means "modification," not "change" in the Bitcoin sense (returned remainder of a transaction). The correct term is "الباقي".

Correct translation:
نسخ الباقي
```

<!-- cache_translation_check_ar_fe281b0e70f54b478dbc517d374ee0d761f4f320a18ae76938470a80eb0bd229 -->
```
        <source>Copy the current signature to the clipboard</source>
        <translation>امضای فعلی را در کلیپ بورد کپی کنید</translation>
    
SPAM
The translation is in Persian (Farsi), not Arabic.

Correct translation:
انسخ التوقيع الحالي إلى الحافظة
```

<!-- cache_translation_check_ar_cd5ebd9c12ed9ff66e2a0f11e9b876ccaec141ebd7261cfb6ab2bf601e091400 -->
```
        <source>own address</source>
        <translation>عنوانه</translation>
    
ERR
The translation "عنوانه" means "his address," which is incorrect and gendered. The correct Arabic translation for "own address" is "عنوانك" if addressing singular "you," or "عنوانك الخاص" for a more general "your own address." If the context refers to "your own address" in the UI, then "عنوانك" or "عنوانك الخاص" is best.

Correct translation:
عنوانك
or
عنوانك الخاص
```

<!-- cache_translation_check_ar_459dfaa8aeddf4f6c7aedb4b5823f19a9beaa2586821423f96d790b199c451d1 -->
```
        <source>Invalid value detected for '-wallet' or '-nowallet'. '-wallet' requires a string value, while '-nowallet' accepts only '1' to disable all wallets</source>
        <translation>قيمة غير صالحة تم اكتشافها لـ "-wallet" أو "-Nowallet". يتطلب "-wallet" قيمة سلسلة ، في حين أن "-Nowallet" تقبل فقط "1" لتعطيل جميع المحافظ</translation>
    
ERR
There are a few issues:
- Arabic translation should preserve the case-sensitivity of wallet options ('-wallet', '-nowallet'); the translation uses '-Nowallet' (with an uppercase 'N') instead of '-nowallet'.
- Minor style issue: there is a space before the comma (،). In Arabic, this is less problematic, but it is better style to use the comma directly after the word.
- The translation uses a space before "،" which is not standard.
- The English source uses double quotes ("-wallet"), while it is more typical to use the same or appropriate quotation marks; however, this may be acceptable.

Correct translation:
قيمة غير صالحة تم اكتشافها للخياريْن "-wallet" أو "-nowallet". يتطلب "-wallet" قيمة نصية، بينما يقبل "-nowallet" فقط "1" لتعطيل جميع المحافظ
```

<!-- cache_translation_check_ar_981f3d80238e760c5ec450df2b10712551a68e61c842edd7498587135ab4e9e7 -->
```
        <source>Cannot obtain a lock on directory %s. %s is probably already running.</source>
        <translation>نمی‌توان قفلی روی دایرکتوری %s ایجاد کرد. احتمالاً %s از قبل در حال اجرا است</translation>
    
SPAM
The translation is in Persian (Farsi), not Arabic as requested.

Correct translation:
لا يمكن الحصول على قفل على الدليل %s. من المحتمل أن %s يعمل بالفعل.
```

<!-- cache_translation_check_ar_f8e7b6cfa5e7e8c34169e6d35a73bd2516529d2718a441498d4157852d82679d -->
```
        <source>Option '-checkpoints' is set but checkpoints were removed. This option has no effect.</source>
        <translation>گزینه «-checkpoints» تنظیم شده است اما Checkpointها حذف شده‌اند. این گزینه هیچ تاثیری ندارد.</translation>
    
SPAM
The provided text is in Persian (Farsi), not Arabic.

Correct translation:
تم تعيين الخيار '-checkpoints' ولكن تم إزالة نقاط التحقق. هذا الخيار ليس له أي تأثير.
```

<!-- cache_translation_check_ar_6f0a3cdde1884b0b257ee7a178a9cf4753ea16843a7cae381c4d4c8cadecd63f -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>الو: آخرینکیف پولهمگام‌سازی فراتر از هر استداده‌هاتو باید -فهرست‌بندی مجدد(دانلودکلبلاکچیندوباره در هرس شدن)</translation>
    
SPAM
The provided text is mostly in Persian with garbled words, not Arabic, and is unreadable.

Correct translation:
التقليم: آخر مزامنة للمحفظة تتجاوز البيانات المُقلَّمة. تحتاج إلى تنفيذ -reindex (إعادة تنزيل سلسلة الكتل كاملةً في حالة العقدة المُقلَّمة)
```

<!-- cache_translation_check_ar_daac836af7ca2ef2148a1c6997acfcc4583e169fc6b133a0b31675e92ca670fb -->
```
        <source>Disk space is too low!</source>
        <translation>‫تحذير: مساحة التخزين منخفضة!‬</translation>
    
ERR
The translation adds "تحذير:" which is not in the source, uses "مساحة التخزين" instead of "مساحة القرص", and includes extraneous directional marks. 

Correct translation:
مساحة القرص منخفضة للغاية!
```

<!-- cache_translation_check_ar_bd3e3e25dd9d168e42193139c244e1c01559781e2adf604c2d81219107471cf0 -->
```
        <source>Error reading from database, shutting down.</source>
        <translation>‫خطأ في القراءة من قاعدة البيانات ، يجري التوقف.‬</translation>
    
ERR
The translation contains formatting issues: an unnecessary RTL control mark and an extra space before the Arabic comma. The phrasing "يجري التوقف" is also awkward.

Correct translation:
خطأ في القراءة من قاعدة البيانات، جارٍ إيقاف التشغيل.
```

<!-- cache_translation_check_ar_9b3be64ef25a45b160a4db1f4eb6d38f436c4169331a8249a9dba9269d53dd04 -->
```
        <source>Error reading next record from wallet database</source>
        <translation>خطأ قراءة السجل التالي من قاعدة بيانات المحفظة</translation>
    
ERR
The Arabic phrasing is slightly ungrammatical; it should include a preposition. 

Correct translation:
حدث خطأ أثناء قراءة السجل التالي من قاعدة بيانات المحفظة
```

<!-- cache_translation_check_ar_e3c19eba027b01bf785b9b032399f2b1736affccacfa1fe503d05408cf8b2e00 -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>حدث خطأ أثناء التحميل %s : المحفظة قديمة. يُرجى الانتقال إلى محفظة وصفية باستخدام أداة الترحيل (محفظة الهجرة RPC).</translation>
    
ERR
The translation of "migratewallet RPC" is incorrect. In the context of Bitcoin Core command-line or RPC interfaces, the command name "migratewallet" should remain in English as it is a specific technical command. Translating it to "محفظة الهجرة" (migration wallet) makes the instruction unusable for the user. Additionally, there is a minor spacing issue before the colon.

Correct translation:
حدث خطأ أثناء تحميل %s: المحفظة من النوع القديم (legacy). يرجى الترحيل إلى محفظة وصفية (descriptor wallet) باستخدام أداة الترحيل (migratewallet RPC).
```

<!-- cache_translation_check_ar_a5dd9f0ae36b6ea1ee163eefc1c93f516dc6bc059946dd9eb6ea3dbc9a8d3bed -->
```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on an enormous cluster of unconfirmed transactions.</source>
        <translation>فشل في حساب رسوم الصدمة، لأن UTXOs غير المؤكدة تعتمد على مجموعة ضخمة من المعاملات غير المؤكدة.</translation>
    
ERR
The translation of "bump fees" as "رسوم الصدمة" is incorrect. In the context of Bitcoin, "bump" refers to increasing or raising the transaction fee (e.g., Replace-By-Fee), not a physical "shock" or "bump" (صدمة). 

Correct translation:
فشل في حساب زيادة الرسوم، لأن مخرجات المعاملات غير المنفقة (UTXOs) غير المؤكدة تعتمد على مجموعة ضخمة من المعاملات غير المؤكدة.
```

<!-- cache_translation_check_ar_f2b328352717ee3d508404e15a2bbab6e7678dc23afe51563d0c4b340db3db31 -->
```
        <source>Invalid -proxy address or hostname, ends with '=': '%s'</source>
        <translation>عنوان الوكيل أو اسم المضيف غير صالح، وينتهي بـ '=':  %s'</translation>
    
ERR
There is a double space before the format specifier '%s' and a missing opening single quote before it, resulting in a trailing single quote.

Correct translation:
عنوان الوكيل أو اسم المضيف غير صالح، وينتهي بـ '=': '%s'
```

<!-- cache_translation_check_ar_96dddb418a0ada1970be7ea86b4dd2d6f72b0cd7fc7c5a9fb225000da32e61d8 -->
```
        <source>Unrecognized network in -proxy='%s': '%s'</source>
        <translation>شبكة غير معروفة في - الوكيل='%s': '%s'</translation>
    
ERR
The translation introduces an unnecessary space between the hyphen and the word "proxy" (translated as الوكيل), which breaks the command-line flag format. The command-line flag `-proxy` should remain untranslated and without spaces to ensure technical accuracy.

Correct translation:
شبكة غير معروفة في -proxy='%s': '%s'
```
</details>

Number of issues: 77.
