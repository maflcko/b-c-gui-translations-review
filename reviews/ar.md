# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ar</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bar%5D%20low%20quality)


```
        <source>%1 didn't yet exit safely…</source>
        <translation>‫%1 لم يغلق بامان بعد…‬</translation>
    
YES, The translation is problematic. The Arabic word "يغلق" (yaghliq) which means "to close" is not the correct translation for "exit" in this context. The sentence implies that a process or application is not safely shutting down, not that it's not closing safely.

The correct translation should use a verb that conveys the meaning of safely leaving or exiting a state.

Correct translation: ‫%1 لم يخرج بأمان بعد…‬
```

```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>‫موصل طابق‬</translation>
    
YES
The translation is incorrect. "Block Relay" refers to relaying information about blocks, not a "floor connector". The Arabic word "طابق" means "floor" or "level".

NO
```

```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>‫تفقدي‬</translation>
    
YES: The translation is too literal and doesn't capture the technical meaning of "feeler" in the context of Bitcoin P2P network connections. A "feeler" is a type of probe or test connection.

Correct translation: ‫مستطلع‬
```

```
        <source>Show information about Qt</source>
        <translation>اظهر المعلومات</translation>
    
YES - The translation is incomplete. It omits the word "Qt".
Correct translation: اظهر معلومات عن Qt
```

```
        <source>Modify configuration options for %1</source>
        <translation>تغيير خيارات الإعداد لأساس ل%1</translation>
    
YES
The Arabic translation incorrectly includes the word "أساس" which means "foundation" or "basis" and is not relevant to the context of modifying configuration options.
Correct translation: تعديل خيارات الإعداد لـ %1
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>%1 اتصال نشط بشبكة البيتكوين</translation>
    
YES: The Arabic translation is inaccurate and does not convey the original meaning. The English text states that a proxy is enabled and provides a value '%1'. The Arabic translation says '%1 is connected to the Bitcoin network', which is a misinterpretation.

Correct translation: الوكيل &lt;b&gt;مُمَكَّن&lt;/b&gt;: %1
```

```
        <source>Change Passphrase…</source>
        <translation>وتغيير العبارات...</translation>
    
YES, The translation is problematic. The word "Passphrase" has been translated to "العبارات" which means "phrases" or "statements" and is not an accurate translation in the context of Bitcoin security. The correct translation should reflect the meaning of a "passphrase" used to protect a Bitcoin wallet or private key.

The correct translation for "Change Passphrase…" in the context of Bitcoin is:
تغيير عبارة المرور...
```

```
        <source>Sign message…</source>
        <translation>علامة ورسالة...</translation>
    
YES
The translation is inaccurate and uses an incorrect word order. The English phrase "Sign message…" means to sign a message, not to mark and message.
Correct translation: رسالة التوقيع...
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>وقَع الرسائل بواسطة ال: Bitcoin الخاص بك لإثبات امتلاكك لهم</translation>
    
YES - The Arabic translation is grammatically incorrect and omits the word "addresses". The colon after "ال" is also misplaced.

Correct translation: وقّع الرسائل باستخدام عناوين البيتكوين الخاصة بك لإثبات ملكيتك لها
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>تحقق من الرسائل للتأكد من أنَها وُقعت برسائل Bitcoin محدَدة</translation>
    
YES - The translation is inaccurate and problematic. The Arabic word "رسائل" (rasa'il) which means "messages" is repeated unnecessarily and incorrectly in the translation. The phrase "specified Bitcoin addresses" should be translated as "عناوين بيتكوين محددة" (anawin Bitcoin muhaddadah).

Correct translation: تحقق من الرسائل للتأكد من أنها وُقعت بعناوين بيتكوين محددة
```

```
        <source>Open URI…</source>
        <translation>فتح ورابط...</translation>
    
YES
The translation is inaccurate and grammatically incorrect. It translates "Open URI…" to "Open and links..." which does not convey the intended meaning.
Correct translation: فتح URI...
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>‫أطلب مدفوعات (أنشئ رموز استجابة (QR Codes) وعناوين بتكوين)‬</translation>
    
YES: The translation is problematic because it incorrectly translates "bitcoin: URIs" as "عناوين بتكوين" (Bitcoin addresses). The original text refers to URIs (Uniform Resource Identifiers) which are a type of web address, not Bitcoin addresses themselves. The correct translation should reflect the concept of "bitcoin URIs".

Correct translation: ‫أطلب مدفوعات (أنشئ رموز استجابة (QR Codes) و URIs بتكوين)‬
```

```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>‫عرض قائمة العناوين المستلمة والمذكرات (المستخدمة سابقا)‬</translation>
    
YES: The translation incorrectly translates "used" as "used before" and omits the word "labels" from the translation. The word "labels" is present in the source text but missing from the translation.

The correct translation should be: ‫عرض قائمة العناوين المستلمة والتسميات (المستخدمة)‬
```

```
        <source>%1 behind</source>
        <translation>‫متأخر‬ %1</translation>
    
YES - The translation is inaccurate and problematic. The Arabic translation does not convey the intended meaning of "%1 behind" in the context of Bitcoin. It translates to "behind %1" which is grammatically incorrect and nonsensical.

Correct translation: %1 خلف
```

```
        <source>Last received block was generated %1 ago.</source>
        <translation>‫آخر طابق مستلم تم بناءه قبل %1.</translation>
    
YES: The translation uses "طابق" which means "floor" or "level" instead of "block". The correct translation should use "كتلة" for block.

The English text is: "Last received block was generated %1 ago."
The Arabic text is: "آخر طابق مستلم تم بناءه قبل %1."

The problematic word is "طابق" which means "floor". The correct word for "block" in this context is "كتلة".

Corrected translation:
‫آخر كتلة مستلمة تم إنشاؤها قبل %1.</translation>
```

```
        <source>Change:</source>
        <translation>تعديل:</translation>
    
YES, The translation is incorrect. "Change:" in the context of Bitcoin refers to the remaining amount after a transaction, not an edit or modification.
The correct translation is:
تغيير:
```

```
        <source>Received with label</source>
        <translation>‫استُلم وله مذكرة‬</translation>
    
YES: The translation "استُلم وله مذكرة" (received and it has a note) is grammatically incorrect and unnatural for the context of receiving Bitcoin with a label. A more accurate and natural translation would be "تم الاستلام مع تسمية" (received with a label).
The correct translation is: ‫تم الاستلام مع تسمية‬
```

```
        <source>(change)</source>
        <translation>(تغير)</translation>
    
YES - The translation of "(change)" to "(تغير)" is a literal translation and does not accurately reflect the Bitcoin context. In Bitcoin, "change" refers to the remaining unspent transaction output (UTXO) that is returned to the sender. The Arabic word "تغير" means "change" in a general sense (like a change in state or a coin), but it does not convey the specific technical meaning of Bitcoin change. The correct translation should reflect the concept of "Baqaya" or "Al-Baqaaya" which refers to the remaining amount or change in transactions.

(الباقي)
```

```
        <source>Options set in this dialog are overridden by the command line:</source>
        <translation>‫التفضيلات المعينة عن طريق سطر الأوامر لها أولوية أكبر وتتجاوز التفضيلات المختارة هنا:‬</translation>
    
YES: The translation conveys the meaning of the original English sentence but uses a more verbose and less direct phrasing. The phrase "لها أولوية أكبر وتتجاوز" (has greater priority and overrides) is a bit redundant. A more concise and direct translation would be better.

Correct translation: ‫تُستخدم خيارات سطر الأوامر لتجاوز الخيارات المعينة في هذا الحوار:‬
```

```
        <source>Prune block storage to</source>
        <translation>‫اختصار تخزين الطابق</translation>
    
YES
The translation is erroneous. The Arabic word for "block" is "كتلة" and the Arabic word for "storage" is "تخزين". "طابق" means "floor".

The correct translation is:
‫تقليم تخزين الكتلة إلى‬
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>‫العودة الى هذا الاعداد تتطلب إعادة تنزيل الطوابق المتتالية بالكامل.‬</translation>
    
YES: The Arabic translation incorrectly uses "الطوابق المتتالية" (consecutive floors) which is not a valid translation for "blockchain" in the context of Bitcoin. The correct term is "سلسلة الكتل".

The Arabic translation should be:
العودة إلى هذا الإعداد تتطلب إعادة تنزيل سلسلة الكتل بأكملها.
```

```
        <source>Show tray icon</source>
        <translation>‫اعرض الأيقونة في الزاوية‬</translation>
    
YES, The translation is too literal and doesn't convey the intended meaning of "tray icon" in a user interface context. In Arabic, a more appropriate translation would be "Show tray icon" which means "أظهر أيقونة شريط المهام".
The correct translation is: ‫أظهر أيقونة شريط المهام‬
```

```
        <source>Third-party URLs (e.g. a block explorer) that appear in the transactions tab as context menu items. %s in the URL is replaced by transaction hash. Multiple URLs are separated by vertical bar |.</source>
        <translation>‫عناوين أطراف أخرى (مثل: مستكشف الطوابق) تظهر في النافذة المبوبة للعمليات كخيار في القائمة المنبثقة. %s في الرابط تُستبدل بمعرف التجزئة. سيتم فصل العناوين بخط أفقي |.‬</translation>
    
YES: The translation incorrectly translates "block explorer" as "مستكشف الطوابق" (floor explorer) instead of "مستكشف الكتل" (block explorer). Additionally, "transaction hash" is translated as "معرف التجزئة" which is acceptable, but "معرف المعاملة" is more contextually appropriate for Bitcoin transactions.

Corrected translation:
‫عناوين أطراف أخرى (مثل: مستكشف الكتل) تظهر في النافذة المبوبة للمعاملات كخيار في القائمة المنبثقة. %s في الرابط تُستبدل بمعرف المعاملة. سيتم فصل العناوين بخط أفقي |.‬
```

```
        <source>Whether to show coin control features or not.</source>
        <translation>‫ما اذا أردت إظهار ميزات التحكم في وحدات البتكوين أم لا.‬</translation>
    
YES - The translation uses the word "وحدات" which means "units" and is not the correct translation for Bitcoin. It should be "بيتكوين" instead of "وحدات البتكوين".

The correct translation is: ‫ما اذا أردت إظهار ميزات التحكم في بيتكوين أم لا.‬
```

```
        <source>Current settings will be backed up at "%1".</source>
        <extracomment>Text explaining to the user that the client's current settings will be backed up at a specific location. %1 is a stand-in argument for the backup location's path.</extracomment>
        <translation>‫سيتم النسخ الاحتياطي للاعدادات على “%1”.‬".</translation>
    
YES: The translation includes an unnecessary quotation mark at the end.
‫سيتم النسخ الاحتياطي للإعدادات على "%1".‬
```

```
        <source>Could not read setting "%1", %2.</source>
        <translation>‫لا يمكن قراءة الاعدادات “%1”, %2.‬</translation>
    
YES: The Arabic translation incorrectly uses the plural form of "setting" ("الاعدادات") when the English source uses the singular form ("setting").

Correct translation: ‫لا يمكن قراءة الإعداد "%1", %2.‬
```

```
        <source>Signed %1 inputs, but more signatures are still required.</source>
        <translation>‫تم توقيع %1 مدخلات، مطلوب توقيعات اضافية.‬</translation>
    
YES. The translation is problematic because it uses the wrong Arabic word for "inputs". The correct word is "مدخلات" and not "مدخل".

Signed %1 inputs, but more signatures are still required.
تم توقيع %1 مدخلات، مطلوب توقيعات إضافية.
```

```
        <source>PSBT saved to disk.</source>
        <translation>‫تم حفظ المعاملة الموقعة جزئيا على وحدة التخزين.‬</translation>
    
YES: The translation uses "المعاملة الموقعة جزئيا" which directly translates to "partially signed transaction". While a PSBT is a partially signed transaction, in the context of Bitcoin, it's generally referred to as a "PSBT" or "transaction builder". The current translation is a bit too literal and not the most common terminology.

A more accurate and contextually appropriate translation would be:
"تم حفظ PSBT على القرص."
```

```
        <source>own address</source>
        <translation>عنوانه</translation>
    
YES, the translation is problematic. The Arabic word "عنوانه" translates to "his address", which is not an accurate or complete translation of "own address". The possessive pronoun "his" is not implied in the English source.

A more accurate translation would be "عنوان خاص بك" which means "your own address" or "العنوان الخاص" meaning "the own address".

NO
```

```
        <source>URI handling</source>
        <translation>التعامل مع العنوان</translation>
    
YES
The Arabic translation "التعامل مع العنوان" which translates to "Handling the Address" is not the most accurate translation for "URI handling" in the context of Bitcoin. "URI handling" refers to how the system manages Uniform Resource Identifiers, which can include Bitcoin payment URIs. A more appropriate translation would be "معالجة عنوان URI" or "التعامل مع معرفات URI".

معالجة عنوان URI
```

```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>'bitcoin://' هو ليس عنوان URL صالح. استعمل 'bitcoin:' بدلا من ذلك.</translation>
    
YES. The translation uses the word "عنوان URL" which translates to "URL address". While technically correct, it is redundant as URL itself implies an address. A more concise and natural translation would be "عنوان" which translates to "address".

'bitcoin://' هو ليس عنوان URL صالح. استعمل 'bitcoin:' بدلا من ذلك.
'bitcoin://' ليس عنوانًا صالحًا. استخدم 'bitcoin:' بدلاً من ذلك.
```

```
        <source>Cannot process payment request because BIP70 is not supported.
Due to widespread security flaws in BIP70 it's strongly recommended that any merchant instructions to switch wallets be ignored.
If you are receiving this error you should request the merchant provide a BIP21 compatible URI.</source>
        <translation>‫لا يمكن معالجة طلب الدفع لأن BIP70 غير مدعوم.
‬‫‫‫نظرًا لوجود عيوب أمنية كبيرة في ‫BIP70 يوصى بشدة بتجاهل أي تعليمات من المستلمين لتبديل المحافظ.
‬‫‫‫إذا كنت تتلقى هذا الخطأ ، يجب أن تطلب من المستلم تقديم عنوان URI متوافق مع BIP21.‬</translation>
    
YES: The translation mistakenly translates "merchant" as "المستلمين" (recipients) instead of "التاجر" (merchant). Additionally, the phrase "switch wallets" is translated as "تبديل المحافظ" which can be ambiguous and less precise than "تغيير المحافظ" (changing wallets) or "الانتقال إلى محافظ أخرى" (switching to other wallets) in this context.

The correct translation should be:
‫لا يمكن معالجة طلب الدفع لأن BIP70 غير مدعوم.
‫‫‫نظرًا لوجود عيوب أمنية كبيرة في ‫BIP70 يوصى بشدة بتجاهل أي تعليمات من التاجر لتبديل المحافظ.
‫‫‫إذا كنت تتلقى هذا الخطأ ، يجب أن تطلب من التاجر تقديم عنوان URI متوافق مع BIP21.
```

```
        <source>URI cannot be parsed! This can be caused by an invalid Bitcoin address or malformed URI parameters.</source>
        <translation>‫لا يمكن تحليل العنوان (URI)! يمكن أن يحدث هذا بسبب عنوان بتكوين غير صالح أو محددات عنوان غير صحيحة.‬</translation>
    
YES, The word "address" is translated as "العنوان" which is a general term. In the context of Bitcoin, "address" can mean a Bitcoin wallet address. However, the source text refers to a URI, which is a Uniform Resource Identifier. The word "URI" is used in the source text, but it is translated as "العنوان" in the target text. It would be better to keep "URI" as it is or translate it more accurately to avoid confusion.

Here's a more accurate translation:
YES, The word "address" is translated as "العنوان" which is a general term. In the context of Bitcoin, "address" can mean a Bitcoin wallet address. However, the source text refers to a URI, which is a Uniform Resource Identifier. The word "URI" is used in the source text, but it is translated as "العنوان" in the target text. It would be better to keep "URI" as it is or translate it more accurately to avoid confusion.

Correct translation: ‫تعذر تحليل معرف الموارد الموحد (URI)! يمكن أن يحدث هذا بسبب عنوان بيتكوين غير صالح أو معلمات URI غير صحيحة.‬
```

```
        <source>Change:</source>
        <translation>تعديل:</translation>
    
YES, The translation is incorrect. "Change:" in the context of Bitcoin refers to the remaining amount after a transaction, not an edit or modification.
The correct translation is:
تغيير:
```

```
        <source>own address</source>
        <translation>عنوانه</translation>
    
YES, the translation is problematic. The Arabic word "عنوانه" translates to "his address", which is not an accurate or complete translation of "own address". The possessive pronoun "his" is not implied in the English source.

A more accurate translation would be "عنوان خاص بك" which means "your own address" or "العنوان الخاص" meaning "the own address".

NO
```

```
        <source>Export</source>
        <translation>و إستخرج</translation>
    
YES: The word order is unnatural in Arabic. "Export" as a command should be translated to "صدّر" or "استخرج".
صدّر
```

```
        <source>Error starting/committing db txn for wallet transactions removal process</source>
        <translation>خطأ بدء/ارتكاب DB TXN لعملية إزالة معاملات المحفظة</translation>
    
YES - The translation is problematic because the word "committing" is mistranslated as "ارتكاب" which means "committing a crime". The correct translation should be "تثبيت" which means "committing" in the context of a database transaction.

Correct Translation: خطأ بدء/تثبيت DB TXN لعملية إزالة معاملات المحفظة
```

```
        <source>Invalid value detected for '-wallet' or '-nowallet'. '-wallet' requires a string value, while '-nowallet' accepts only '1' to disable all wallets</source>
        <translation>قيمة غير صالحة تم اكتشافها لـ "-wallet" أو "-Nowallet". يتطلب "-wallet" قيمة سلسلة ، في حين أن "-Nowallet" تقبل فقط "1" لتعطيل جميع المحافظ</translation>
    
YES
The translation of '-nowallet' to '-Nowallet' is incorrect as it capitalizes the 'n', which is not present in the source text.

-wallet" أو "-nowallet". يتطلب "-wallet" قيمة سلسلة ، في حين أن "-nowallet" تقبل فقط "1" لتعطيل جميع المحافظ
```
</details>
