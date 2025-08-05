# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ar</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bar%5D%20low%20quality)


```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>‫موصل طابق‬</translation>
    
YES  
The translation "‫موصل طابق‬" is incorrect and does not convey the meaning of "Block Relay." "موصل" means "connector" and "طابق" means "floor" or "level," which is unrelated to the Bitcoin context. The correct translation for "Block Relay" in the context of relaying block data should be "توصيل الكتل" or "إعادة توصيل الكتل."

Correct translation:  
توصيل الكتل
```

```
        <source>Show information about Qt</source>
        <translation>اظهر المعلومات</translation>
    
YES  
The translation is incomplete and does not accurately convey the full meaning of the source text. The source requests showing information "about Qt," but the translation simply says "Show the information" without specifying "about Qt." The keyword "Qt" should be included to maintain context.

Correct translation:  
اظهر المعلومات عن Qt
```

```
        <source>Modify configuration options for %1</source>
        <translation>تغيير خيارات الإعداد لأساس ل%1</translation>
    
YES  
The translation contains an erroneous phrase "لأساس ل%1" which does not make sense in Arabic. The phrase "for %1" should be correctly translated as "لـ%1" without the extra words. The correct translation is:  
تغيير خيارات الإعداد لـ%1
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>%1 اتصال نشط بشبكة البيتكوين</translation>
    
YES
The translation does not accurately reflect the original text. The source means "Proxy is <b>enabled</b>: %1", indicating that the proxy is enabled and then shows the proxy info (%1). The given translation means "%1 active connection to the Bitcoin network," which changes the meaning and omits the information about the proxy being enabled.

Correct translation:
"الوكيل &lt;b&gt;مفعل&lt;/b&gt;: %1"
```

```
        <source>Change Passphrase…</source>
        <translation>وتغيير العبارات...</translation>
    
YES  
The translation is incomplete and inaccurate. The source "Change Passphrase…" means "تغيير عبارة المرور…" or "تغيير كلمة المرور…". The current translation "وتغيير العبارات..." starts with a conjunction "و" (and) which is unnecessary and incorrect here, and "العبارات" (phrases) is plural and doesn't fit well. Also, the ellipsis in Arabic should be the proper Unicode character (…).

Correct translation:  
تغيير عبارة المرور…
```

```
        <source>Sign message…</source>
        <translation>علامة ورسالة...</translation>
    
YES  
The translation "علامة ورسالة..." is incorrect. It translates back as "Sign and message..." which does not convey the intended meaning of "Sign message…". The correct translation should convey the imperative or action of signing a message, such as:

وقع الرسالة…
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>وقَع الرسائل بواسطة ال: Bitcoin الخاص بك لإثبات امتلاكك لهم</translation>
    
YES  
The translation contains unnecessary spacing and an incorrect article usage before "Bitcoin". The colon after "ال" is incorrect and "Bitcoin" should not be separated with colons or spaces. Additionally, "ال" should not be used before "Bitcoin" here; it is better to say "عناوين البيتكوين الخاصة بك" for "your Bitcoin addresses". Also, "امتلاكك لهم" should refer to "عناوين" which is feminine plural, so "امتلاكك لها" is preferred.  

Correct translation:  
وقّع الرسائل بعناوين البيتكوين الخاصة بك لإثبات امتلاكك لها
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>تحقق من الرسائل للتأكد من أنَها وُقعت برسائل Bitcoin محدَدة</translation>
    
YES  
The translation contains an error in the last phrase: "وُقعت برسائل Bitcoin محدَدة" literally means "signed with specified Bitcoin messages," which is incorrect. It should say "signed with specified Bitcoin addresses" to match the source. The word "addresses" is "عناوين" in Arabic.  

Correct translation:  
تحقق من الرسائل للتأكد من أنها وُقعت بعناوين Bitcoin محددة
```

```
        <source>Open URI…</source>
        <translation>فتح ورابط...</translation>
    
YES  
The translation is incorrect. The word "ورابط" is not suitable here and seems to be a typo or misinterpretation. The English "Open URI…" should be translated as "فتح عنوان URI…" or simply "فتح URI…" because URI (Uniform Resource Identifier) is often transliterated or left as is. The ellipsis character … should also be the correct single character, not three dots or mixed characters.

Correct translation:  
فتح URI…
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>‫أطلب مدفوعات (أنشئ رموز استجابة (QR Codes) وعناوين بتكوين)‬</translation>
    
YES
The translation inaccurately translates "Request payments" as "أطلب مدفوعات" which feels like an imperative ("Order payments") rather than the noun phrase "Request payments" referring to a feature or command label in the software. Also, "QR Codes" should consistently be in Arabic or clear with "رموز QR" rather than mixing English and Arabic parentheses. The phrase "bitcoin: URIs" is translated as "عناوين بتكوين" which means "Bitcoin addresses," but it should refer to "bitcoin: URIs" indicating URI links, not just addresses.

A more accurate translation preserving the meaning and technical terms would be:

‫طلب المدفوعات (يُنشئ رموز QR وروابط bitcoin:)‬

This uses the noun phrase "طلب المدفوعات" and translates "generates" properly with "يُنشئ"، "QR codes" as "رموز QR" and keeps "bitcoin:" as is to reflect the URI scheme.

Correct translation:
‫طلب المدفوعات (يُنشئ رموز QR وروابط bitcoin:)‬
```

```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>‫عرض قائمة العناوين المستلمة والمذكرات (المستخدمة سابقا)‬</translation>
    
YES  
The Arabic translation contains an unnecessary use of parentheses and a slight awkwardness in phrasing. The source mentions "used receiving addresses and labels," so "used" should clearly refer to both addresses and labels, not be an afterthought. Also, "مذكرات" means "notes" or "memoranda," which is not equivalent to "labels" in the Bitcoin context. A better translation for "labels" in Bitcoin context is "تسميات".

Correct translation:  
‫عرض قائمة العناوين المستلمة والتسميات المستخدمة‬
```

```
        <source>Last received block was generated %1 ago.</source>
        <translation>‫آخر طابق مستلم تم بناءه قبل %1.</translation>
    
YES  
The Arabic word "طابق" means "floor" (as in building floors), which is incorrect in this context. The correct word should be "كتلة" meaning "block" (in the blockchain context). Also, the phrase "قبل %1" is awkward here; a better phrasing is "منذ %1" to mean "ago %1." Additionally, the formatting and spacing should be fixed.

Correct translation:  
‫آخر كتلة مستلمة تم إنشاؤها منذ %1.
```

```
        <source>Change:</source>
        <translation>تعديل:</translation>
    
YES  
The English term "Change" in the Bitcoin context refers to the amount of leftover bitcoins returned to the sender after a transaction, not a general term like "تعديل" which means "edit" or "modification."  
A more accurate translation would be:  
"الباقي:" or "المتبقي:" or simply "المبلغ المتبقي:" depending on the preferred terminology in Bitcoin Arabic translations.  
Recommended correction:  
<translation>المتبقي:</translation>
```

```
        <source>Received with label</source>
        <translation>‫استُلم وله مذكرة‬</translation>
    
YES  
The translation "‫استُلم وله مذكرة‬" is somewhat awkward and inaccurate. The phrase "Received with label" in the Bitcoin context usually means something like "Received [payment] with a label," where "label" refers to a tag or identifier for the transaction or address.

The word "وله" here is incorrect; it means "and he has" or "for him," which does not fit. "مذكرة" means "note" or "memo," but the better term in this context is "تسمية" (label) or "وصف" (description).

A more accurate and natural translation would be:

"مُستلم مع التسمية"  
or  
"تم الاستلام مع التسمية"

Either is acceptable, but the first is more concise.

Correct translation:  
مُستلم مع التسمية
```

```
        <source>(change)</source>
        <translation>(تغير)</translation>
    
YES  
The English word "change" in the context of Bitcoin transactions typically refers to "الباقي" or "المبلغ الباقي" (the leftover amount returned to the sender), not the general term "تغير" which means "change" as in alteration or transformation.  

Correct translation:  
(الباقي)
```

```
        <source>Prune block storage to</source>
        <translation>‫اختصار تخزين الطابق</translation>
    
YES
The Arabic translation of "Prune block storage to" is incorrect and does not convey the intended meaning. The term "اختصار" means "shortcut" rather than "prune" or "reduce," and "الطابق" means "floor" rather than "block." In the context of Bitcoin, "block" refers to a data block, not a physical floor.

A more accurate translation would be:
"تقليص تخزين الكتل إلى"
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>‫العودة الى هذا الاعداد تتطلب إعادة تنزيل الطوابق المتتالية بالكامل.‬</translation>
    
YES  
The translation contains an error in the term "الطوابق المتتالية", which literally means "consecutive floors" instead of "blockchain". The correct translation for "blockchain" in Arabic is "سلسلة الكتل". Also, "العودة الى" should be written as "العودة إلى" with the correct hamza and preposition spacing.

Correct translation:  
‫العودة إلى هذا الإعداد تتطلب إعادة تنزيل سلسلة الكتل بالكامل.‬
```

```
        <source>Third-party URLs (e.g. a block explorer) that appear in the transactions tab as context menu items. %s in the URL is replaced by transaction hash. Multiple URLs are separated by vertical bar |.</source>
        <translation>‫عناوين أطراف أخرى (مثل: مستكشف الطوابق) تظهر في النافذة المبوبة للعمليات كخيار في القائمة المنبثقة. %s في الرابط تُستبدل بمعرف التجزئة. سيتم فصل العناوين بخط أفقي |.‬</translation>
    
YES  
The term "مستكشف الطوابق" is incorrect; it translates to "floor explorer" instead of "block explorer." The correct term for "block explorer" in the Bitcoin context is "مستكشف الكتل." Also, "خط أفقي" literally means "horizontal line," but the source says "vertical bar," which should be translated as "علامة عمودية" or "الشريط العمودي." Additionally, "في الرابط" is acceptable but "في عنوان URL" would be more precise for "in the URL."

Correct translation:  
‫عناوين أطراف أخرى (مثل: مستكشف الكتل) تظهر في علامة التبويب العمليات كخيار في القائمة السياقية. %s في عنوان URL تُستبدل بمعرف التجزئة. يتم فصل العناوين بعلامة عمودية |.‬
```

```
        <source>Current settings will be backed up at "%1".</source>
        <extracomment>Text explaining to the user that the client's current settings will be backed up at a specific location. %1 is a stand-in argument for the backup location's path.</extracomment>
        <translation>‫سيتم النسخ الاحتياطي للاعدادات على “%1”.‬".</translation>
    
YES
There is an extra closing quotation mark and period at the end of the Arabic translation causing a formatting error. Also, a more natural phrasing in Arabic would be:

Correct translation:
‫سيتم نسخ الإعدادات الحالية احتياطيًا في “%1”.‬
```

```
        <source>own address</source>
        <translation>عنوانه</translation>
    
YES  
The translation "عنوانه" literally means "his address," which is incorrect in this context. The source "own address" refers to "address owned by oneself" or "العنوان الخاص بي." A more appropriate translation would be:  
"العنوان الخاص"  
or simply  
"العنوان الخاص بي"  
if more explicit.
```

```
        <source>URI handling</source>
        <translation>التعامل مع العنوان</translation>
    
YES  
The original English "URI handling" refers to managing or processing "Uniform Resource Identifiers," which are similar to URLs or addresses. The Arabic translation "التعامل مع العنوان" means "handling the address," which is less precise and may confuse users because "العنوان" usually means "address" in general, not specifically a URI.

A more accurate translation would be:  
"معالجة URI"  
or  
"إدارة URI"  
if you want to keep "URI" as is, which is common in technical contexts. Alternatively, you could write:  
"التعامل مع معرّف الموارد الموحد (URI)"  
but that may be too long.  

Correct translation suggestion:  
<translation>معالجة URI</translation>
```

```
        <source>URI cannot be parsed! This can be caused by an invalid Bitcoin address or malformed URI parameters.</source>
        <translation>‫لا يمكن تحليل العنوان (URI)! يمكن أن يحدث هذا بسبب عنوان بتكوين غير صالح أو محددات عنوان غير صحيحة.‬</translation>
    
YES  
The translation incorrectly translates "URI parameters" as "محددات عنوان" which means "address parameters" instead of "URI parameters". Also, the Arabic word "بتكوين" should be "بتكوين" without unnecessary spaces, although this is minor. The original English emphasizes "URI parameters" (parameters of the URI), not "address parameters". A more accurate translation would be:  

‫لا يمكن تحليل URI! قد يكون السبب عنوان بيتكوين غير صالح أو معلمات URI غير صحيحة.‬
```

```
        <source>Change:</source>
        <translation>تعديل:</translation>
    
YES  
The English term "Change" in the Bitcoin context refers to the amount of leftover bitcoins returned to the sender after a transaction, not a general term like "تعديل" which means "edit" or "modification."  
A more accurate translation would be:  
"الباقي:" or "المتبقي:" or simply "المبلغ المتبقي:" depending on the preferred terminology in Bitcoin Arabic translations.  
Recommended correction:  
<translation>المتبقي:</translation>
```

```
        <source>own address</source>
        <translation>عنوانه</translation>
    
YES  
The translation "عنوانه" literally means "his address," which is incorrect in this context. The source "own address" refers to "address owned by oneself" or "العنوان الخاص بي." A more appropriate translation would be:  
"العنوان الخاص"  
or simply  
"العنوان الخاص بي"  
if more explicit.
```

```
        <source>Export</source>
        <translation>و إستخرج</translation>
    
YES  
The translation "و إستخرج" is incorrect for the single English word "Export." The word starts with the conjunction "و" meaning "and," which is unnecessary and incorrect here, and the verb form "إستخرج" means "extract" rather than the noun or command "Export." A better translation would be either:  
- "تصدير" (the noun for "Export")  
- or "تصدير" if used as a button label or command.

Correct translation:  
تصدير
```

```
        <source>Invalid value detected for '-wallet' or '-nowallet'. '-wallet' requires a string value, while '-nowallet' accepts only '1' to disable all wallets</source>
        <translation>قيمة غير صالحة تم اكتشافها لـ "-wallet" أو "-Nowallet". يتطلب "-wallet" قيمة سلسلة ، في حين أن "-Nowallet" تقبل فقط "1" لتعطيل جميع المحافظ</translation>
    
YES  
The translation has inconsistent casing for "-nowallet" (written as "-Nowallet" in Arabic text) and uses a space before the comma which is not typical in Arabic punctuation. Also, the phrase "قيمة سلسلة" is not idiomatic; "قيمة نصية" or "قيمة من نوع نص" is better for "string value".  
Correct translation:  
قيمة غير صالحة تم اكتشافها لـ "-wallet" أو "-nowallet". يتطلب "-wallet" قيمة نصية، في حين أن "-nowallet" تقبل فقط "1" لتعطيل جميع المحافظ
```
</details>
