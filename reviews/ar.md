# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ar</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bar%5D%20low%20quality)


```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>‫موصل طابق‬</translation>
    
YES
The translation "موصل طابق" is incorrect and does not convey the meaning of "Block Relay" in the context of Bitcoin. "موصل" could mean "connector," and "طابق" means "floor," which is unrelated. The correct translation should convey the function of relaying blocks in a network.

Correct translation:
ترحيل الكتل
```

```
        <source>Show information about Qt</source>
        <translation>اظهر المعلومات</translation>
    
YES
The translation "اظهر المعلومات" means "Show the information" but omits any reference to "Qt". The translation should include "Qt" to match the source meaning.

Correct translation:
اعرض معلومات حول Qt
```

```
        <source>Modify configuration options for %1</source>
        <translation>تغيير خيارات الإعداد لأساس ل%1</translation>
    
YES
The translation contains an error in phrasing and word choice. "لأساس ل%1" is incorrect Arabic and doesn't make sense in this context. The correct translation should maintain the intended structure and clarity.

Correct translation:
تعديل خيارات التكوين لـ %1
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>%1 اتصال نشط بشبكة البيتكوين</translation>
    
YES
The Arabic translation does not accurately reflect the source text. The source states "Proxy is <b>enabled</b>: %1", but the translation says "%1 اتصال نشط بشبكة البيتكوين", which translates back as "%1 active connection to the Bitcoin network", which is a different meaning.

Correct translation:
الوكيل <b>مفعل</b>: ‏%1
```

```
        <source>Change Passphrase…</source>
        <translation>وتغيير العبارات...</translation>
    
YES
The translation is inaccurate. "وتغيير العبارات..." means "and changing the phrases...", which is not correct. The correct translation for "Change Passphrase…" is:

تغيير العبارة السرية…
```

```
        <source>Sign message…</source>
        <translation>علامة ورسالة...</translation>
    
YES
The translation is incorrect. "علامة ورسالة..." means "a sign and a message...", which does not match the source meaning ("Sign message…" as in "Sign a message" cryptographically). The correct translation should convey the action of signing a message.

Correct translation:
وقّع الرسالة…
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>وقَع الرسائل بواسطة ال: Bitcoin الخاص بك لإثبات امتلاكك لهم</translation>
    
YES
The translation has several issues:
- "Bitcoin" should be translated as "عناوين البيتكوين" ("your Bitcoin addresses"), not left in English, to match the context.
- The phrase structure is awkward and not idiomatic Arabic.
- The usage of "ال:" and "لهم" (which means "them", masculine plural) does not match the subject ("addresses").
- The verb "وقَع" should use the imperative "وقّع".
- There is an unnecessary colon and spacing issue.

Correct translation:
وقّع الرسائل بواسطة عناوين البيتكوين الخاصة بك لإثبات ملكيتك لها
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>تحقق من الرسائل للتأكد من أنَها وُقعت برسائل Bitcoin محدَدة</translation>
    
YES
The translation is incorrect. It says "...that they were signed with specified Bitcoin messages" instead of "specified Bitcoin addresses". The word "رسائل" (messages) is used instead of "عناوين" (addresses).

Correct translation:
تحقق من الرسائل للتأكد من أنها وُقعت باستخدام عناوين بيتكوين محددة
```

```
        <source>Open URI…</source>
        <translation>فتح ورابط...</translation>
    
YES
The translation is inaccurate. "ورابط" translates to "and link", which is incorrect. The proper translation for "URI" should be "معرّف الموارد الموحد" or "رابط". The ellipsis should use the Arabic ellipsis "…" if possible.

Correct translation:
فتح رابط…
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>‫أطلب مدفوعات (أنشئ رموز استجابة (QR Codes) وعناوين بتكوين)‬</translation>
    
YES
The translation is mostly accurate but could be improved for clarity and format consistency. "أنشئ" (generate) should be in the same imperative form as "أطلب" (request), but since the English uses the third person "generates" as an explanation, not as a command, the Arabic should better reflect that.

Additionally, "bitcoin: URIs" is not specifically mentioned; "عناوين بتكوين" is ambiguous, as "address" (عنوان) can be confused with general address, not a URI format.

Correct translation:
‫طلب المدفوعات (ينشئ رموز QR وروابط bitcoin:)‬
```

```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>‫عرض قائمة العناوين المستلمة والمذكرات (المستخدمة سابقا)‬</translation>
    
YES
The translation is somewhat inaccurate. The original mentions "used receiving addresses and labels," but the translation says "عرض قائمة العناوين المستلمة والمذكرات (المستخدمة سابقا)," which means "Show the list of received addresses and notes (used earlier)." The term "labels" was incorrectly translated as "المذكرات" (notes/memos), which is inaccurate. Also, "receiving" ("العناوين المستلمة") implies addresses that have received funds, while the English source means "receiving addresses" in general. Additionally, the phrase "(المستخدمة سابقا)" (used previously) is placed ambiguously and not directly tied to both "addresses and labels" as in the source.

Correct translation:
عرض قائمة عناوين الاستلام والملصقات المستخدمة

Or, longer and clearer:
عرض قائمة عناوين الاستلام والملصقات التي تم استخدامها
```

```
        <source>Last received block was generated %1 ago.</source>
        <translation>‫آخر طابق مستلم تم بناءه قبل %1.</translation>
    
YES
The Arabic translation incorrectly uses "طابق" (which means "floor" as in a building), instead of "كتلة" for "block" in the Bitcoin context. There is no unwanted or spam content, but the meaning is wrong.

Correct translation:
‫آخر كتلة تم استلامها تم إنشاؤها قبل %1.‬
```

```
        <source>Change:</source>
        <translation>تعديل:</translation>
    
YES
The translation of "Change:" as "تعديل:" is incorrect. In the context of Bitcoin, "Change" refers to the "change amount", not "modification".

Correct translation:
الباقي:
```

```
        <source>Received with label</source>
        <translation>‫استُلم وله مذكرة‬</translation>
    
YES
The Arabic translation "استُلم وله مذكرة" is inaccurate. "مذكرة" means "note" or "memo," while "label" in the context of Bitcoin addresses refers to a "label" or "اسم" used to identify the address. The translation should use a term meaning "label" rather than "memo."

Correct translation:
استلم مع تسمية
```

```
        <source>(change)</source>
        <translation>(تغير)</translation>
    
YES
The Arabic word "تغير" translates to "change" as in transformation or alteration, which is not the correct meaning in the context of Bitcoin transactions. The correct term is "الباقي" or "الفكة" (which refers to the "change" amount returned in a transaction).

Correct translation:
(الباقي)
or
(الفكة)
```

```
        <source>Prune block storage to</source>
        <translation>‫اختصار تخزين الطابق</translation>
    
YES
The Arabic translation is inaccurate and contains a significant error. "الطابق" means "floor" (like a building floor), which is incorrect here. The term "block storage" in Bitcoin refers to where blockchain blocks are stored. Also, the word "Prune" (اختصار) could be better translated as "تقليص" or "تقليم". The translation misses "block" altogether.

Correct translation:
تقليص تخزين الكتل إلى
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>‫العودة الى هذا الاعداد تتطلب إعادة تنزيل الطوابق المتتالية بالكامل.‬</translation>
    
YES
The translation is problematic. The phrase "الطوابق المتتالية" translates to "sequential floors", which is incorrect in the context of blockchain. The correct translation for "blockchain" is "سلسلة الكتل". Also, "Reverting" should be better reflected.

Correct translation:
تتطلب إعادة هذا الإعداد إعادة تحميل سلسلة الكتل بالكامل.
```

```
        <source>Third-party URLs (e.g. a block explorer) that appear in the transactions tab as context menu items. %s in the URL is replaced by transaction hash. Multiple URLs are separated by vertical bar |.</source>
        <translation>‫عناوين أطراف أخرى (مثل: مستكشف الطوابق) تظهر في النافذة المبوبة للعمليات كخيار في القائمة المنبثقة. %s في الرابط تُستبدل بمعرف التجزئة. سيتم فصل العناوين بخط أفقي |.‬</translation>
    
YES
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

```
        <source>Current settings will be backed up at "%1".</source>
        <extracomment>Text explaining to the user that the client's current settings will be backed up at a specific location. %1 is a stand-in argument for the backup location's path.</extracomment>
        <translation>‫سيتم النسخ الاحتياطي للاعدادات على “%1”.‬".</translation>
    
YES
The translation has an extra stray double quote at the end, and there is a preference for using "في" (at/in) rather than "على" (on) when referring to a location in Arabic. Also, the sentence starts with an LTR quote and ends with an RTL quote, which can be visually inconsistent.

Correct translation:
سيتم نسخ الإعدادات الحالية احتياطيًا في "%1".
```

```
        <source>own address</source>
        <translation>عنوانه</translation>
    
YES
The translation "عنوانه" means "his address," which is incorrect and gendered. The correct Arabic translation for "own address" is "عنوانك" if addressing singular "you," or "عنوانك الخاص" for a more general "your own address." If the context refers to "your own address" in the UI, then "عنوانك" or "عنوانك الخاص" is best.

Correct translation:
عنوانك
or
عنوانك الخاص
```

```
        <source>Change:</source>
        <translation>تعديل:</translation>
    
YES
The translation of "Change:" as "تعديل:" is incorrect. In the context of Bitcoin, "Change" refers to the "change amount", not "modification".

Correct translation:
الباقي:
```

```
        <source>own address</source>
        <translation>عنوانه</translation>
    
YES
The translation "عنوانه" means "his address," which is incorrect and gendered. The correct Arabic translation for "own address" is "عنوانك" if addressing singular "you," or "عنوانك الخاص" for a more general "your own address." If the context refers to "your own address" in the UI, then "عنوانك" or "عنوانك الخاص" is best.

Correct translation:
عنوانك
or
عنوانك الخاص
```

```
        <source>Export</source>
        <translation>و إستخرج</translation>
    
YES
There is an unnecessary space before the word "إستخرج" and the conjunction "و" ("and") is not present in the source. The translation should be a single-word imperative matching the English "Export".

Correct translation:
تصدير
```

```
        <source>Invalid value detected for '-wallet' or '-nowallet'. '-wallet' requires a string value, while '-nowallet' accepts only '1' to disable all wallets</source>
        <translation>قيمة غير صالحة تم اكتشافها لـ "-wallet" أو "-Nowallet". يتطلب "-wallet" قيمة سلسلة ، في حين أن "-Nowallet" تقبل فقط "1" لتعطيل جميع المحافظ</translation>
    
YES
There are a few issues:
- Arabic translation should preserve the case-sensitivity of wallet options ('-wallet', '-nowallet'); the translation uses '-Nowallet' (with an uppercase 'N') instead of '-nowallet'.
- Minor style issue: there is a space before the comma (،). In Arabic, this is less problematic, but it is better style to use the comma directly after the word.
- The translation uses a space before "،" which is not standard.
- The English source uses double quotes ("-wallet"), while it is more typical to use the same or appropriate quotation marks; however, this may be acceptable.

Correct translation:
قيمة غير صالحة تم اكتشافها للخياريْن "-wallet" أو "-nowallet". يتطلب "-wallet" قيمة نصية، بينما يقبل "-nowallet" فقط "1" لتعطيل جميع المحافظ
```
</details>

Number of issues: 24.
