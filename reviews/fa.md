# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>fa</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bfa%5D%20low%20quality)


```
        <source>Copy</source>
        <translation>ذخیره</translation>
    
YES  
The English word "Copy" means to duplicate or replicate something, often for use elsewhere. The Persian translation "ذخیره" means "Save" or "Store," which is incorrect in this context. The correct translation of "Copy" in Persian is "کپی" or "رونوشت."  

Correct translation:  
کپی
```

```
        <source>Unroutable</source>
        <translation>غیرقابل برنامه ریزی</translation>
    
YES
The translation "غیرقابل برنامه ریزی" means "unprogrammable" or "not programmable," which does not capture the intended meaning of "Unroutable" in the Bitcoin context, where it refers to something that cannot be routed (i.e., sent through the network).

Correct translation:
"غیرقابل مسیریابی"
```

```
        <source>Onion</source>
        <comment>network name</comment>
        <extracomment>Name of Tor network in peer info</extracomment>
        <translation>persian</translation>
    
YES  
The translation is incorrect. "Onion" here refers to the Tor network's term and should be transliterated or translated appropriately, not as "persian" which is unrelated and incorrect.  

Correct translation:  
پیاز
```

```
        <source>%1 m</source>
        <translation>%1 دقیقه قبل</translation>
    
YES  
The source text "%1 m" likely refers to "%1 minutes" or "%1 meters" depending on context, but it is abbreviated. The translation "%1 دقیقه قبل" means "%1 minutes ago," which adds "ago" ("قبل") not present in the source and changes the meaning. Also, it spells out "minutes" rather than keeping the abbreviated form "m".

Correct translation:  
"%1 م"  

Or if it is a time duration like minutes, and "m" is an abbreviation, the accurate approach is to keep the format close to the source, without adding "ago":  
"%1 د" (where "د" is an abbreviation for "دقیقه")  

If the intended meaning is exactly "%1 m" as an abbreviation, it should be kept as such or translated with abbreviation equivalence, but not adding extra words.
```

```
        <source>default wallet</source>
        <translation>کیف پول پیش فرض
 </translation>
    
YES
The translation "کیف پول پیش فرض" is correct for "default wallet," but there is an extra whitespace character (a non-breaking space or similar) after the text on a new line, which is unnecessary and may cause formatting issues.

Correct translation:
کیف پول پیش فرض
```

```
        <source>Show general overview of wallet</source>
        <translation>نمایش کلی کیف پول
 </translation>
    
YES
There is an unnecessary trailing whitespace (non-breaking space) after "نمایش کلی کیف پول" in the translation.

Correct translation:
نمایش کلی کیف پول
```

```
        <source>Quit application</source>
        <translation>از "درخواست نامه"/ application خارج شو</translation>
    
YES
The translation is problematic because it mixes English and Persian unnaturally and introduces unnecessary and incorrect terms. The English word "application" is transliterated but unnecessary, and the phrase '"درخواست نامه"' means "letter of request" which is irrelevant here. A correct and natural Persian translation for "Quit application" is:

خروج از برنامه
```

```
        <source>Create a new wallet</source>
        <translation>کیف پول جدیدی ایجاد کنید
 </translation>
    
YES  
There is an unwanted trailing whitespace (a non-breaking space or similar) after the translated text which should be removed. Otherwise, the translation is accurate.

Correct translation:  
کیف پول جدیدی ایجاد کنید
```

```
        <source>Backup wallet to another location</source>
        <translation>پشتیبان گیری از کیف پول به مکان دیگر
 </translation>
    
YES  
There is an unnecessary trailing whitespace (non-breaking space) after the translation text. Also, the translation is accurate but can be made slightly more concise without changing the meaning.

Correct translation:  
پشتیبان‌گیری کیف پول به مکان دیگر
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>کلیدهای خصوصی متعلق به کیف پول شما را رمزگذاری کنید
 </translation>
    
YES  
The translation is mostly accurate but has a trailing whitespace character at the end, which is a format issue. Also, for better flow and clarity in Persian, it might be preferable to rephrase slightly as:  
"کلیدهای خصوصی متعلق به کیف پول شما را رمزگذاری کنید" (without the trailing space or newline).  

Correct translation:  
کلیدهای خصوصی متعلق به کیف پول شما را رمزگذاری کنید
```

```
        <source>Open URI…</source>
        <translation>تکثیر نشانی</translation>
    
YES  
The translation "تکثیر نشانی" means "Duplicate address" or "Copy address," which is incorrect for the source text "Open URI…".  
A correct translation would be:  
"باز کردن URI…"
```

```
        <source>%1 behind</source>
        <translation>%1 قبل</translation>
    
YES  
The translation "%1 قبل" literally means "%1 before," which does not correctly convey the meaning of "%1 behind" in the Bitcoin context (indicating the number of blocks or time the node is behind the blockchain). In Persian, "behind" in this context is better translated as "%1 عقب" or "%1 عقب مانده".

Correct translation:  
%1 عقب
```

```
        <source>Catching up…</source>
        <translation>در حال گرفتن..</translation>
    
YES  
The translation "در حال گرفتن.." is not an accurate or natural translation of "Catching up…". In this Bitcoin context, "Catching up…" refers to synchronizing or updating, not literally "grabbing" or "taking". The ellipsis in English is three dots, but here there are only two dots, which is incorrect.

A more accurate and natural translation would be:  
"در حال به‌روز شدن…" or "در حال همگام‌سازی…"  
Both convey the idea of catching up/synchronizing properly, and the ellipsis should be three dots.

Correct translation:  
در حال به‌روز شدن…
```

```
        <source>Receiving addresses</source>
        <translation>ادرس درسافت</translation>
    
YES  
The translation contains spelling errors. The correct translation should be:  
آدرس‌های دریافت کننده
```

```
        <source>Open a bitcoin: URI</source>
        <translation>بارک کردن یک بیت‌کوین: URI</translation>
    
YES  
The translation uses the word "بارک کردن" which is incorrect and does not convey the meaning of "Open." The proper verb for "open" in this context should be "باز کردن".  

Correct translation:  
باز کردن یک بیت‌کوین: URI
```

```
        <source>Open Wallet</source>
        <translation>کیف پول را باز کنید
 </translation>
    
YES
There is an unnecessary trailing whitespace (a non-breaking space U+00A0) after the translation text. Also, the translation is correct but should not have extra spaces.

Correct translation:
کیف پول را باز کنید
```

```
        <source>Open a wallet</source>
        <translation>کیف پول را باز کنید
 </translation>
    
YES  
There is an extra whitespace character (a non-breaking space or similar) at the end of the translation after "باز کنید" which should be removed to avoid formatting issues.  
Correct translation:  
کیف پول را باز کنید
```

```
        <source>Create Wallet</source>
        <extracomment>Title of window indicating the progress of creation of a new wallet.</extracomment>
        <translation>ایجاد کیف پول
 </translation>
    
YES  
The translation "ایجاد کیف پول" is correct, meaning "Create Wallet." However, there is an extra trailing whitespace character (a non-breaking space) after the text, which is a formatting issue and should be removed.

Correct translation:  
ایجاد کیف پول
```

```
        <source>Create wallet failed</source>
        <translation>کیف پول "ایجاد" نشد
 </translation>
    
YES  
The translation is awkward and unclear. The phrase "کیف پول 'ایجاد' نشد" literally means "Wallet 'create' did not happen," which is not a natural way to express "Create wallet failed" in Persian. Also, there is an unnecessary quotation mark around "ایجاد" and a trailing whitespace issue (a non-breaking space at the end).

A better translation would be concise and straightforward:

"ایجاد کیف پول شکست خورد"

or

"ایجاد کیف پول ناموفق بود"

Both correctly convey that the wallet creation process failed. Also, the trailing space should be removed.

Correct translation:  
ایجاد کیف پول شکست خورد
```

```
        <source>Create wallet warning</source>
        <translation>هشدار کیف پول ایجاد کنید
 </translation>
    
YES  
The translation "هشدار کیف پول ایجاد کنید" literally means "Create wallet warning" but uses a command form "create" (ایجاد کنید), which sounds like an imperative ("create the wallet warning"). The English phrase is a noun phrase (a title or label), so the translation should maintain the noun form without a verb command. A more accurate and natural translation would be:  
"هشدار ایجاد کیف پول"  
or simply  
"هشدار ایجاد کیف‌پول" (without the verb form).  

Also, there is a trailing whitespace character after the translation which should be removed.  

Correct translation:  
هشدار ایجاد کیف پول
```

```
        <source>Reset all client options to default.</source>
        <translation>تمام گزینه های مشتری را به طور پیش فرض بازنشانی کنید.
 </translation>
    
YES  
The translation is mostly accurate, but there is an unnecessary trailing whitespace (a non-breaking space or extra space) at the end after the period. Also, the phrase "مشتری" (moshtari) typically means "customer" rather than "client" in the context of software. In Persian Bitcoin context, "کلاینت" (client) or "نرم‌افزار" (software) or "کاربر" (user) might be more appropriate. A better and more natural translation would be:

تمام گزینه‌های کلاینت را به تنظیمات پیش‌فرض بازنشانی کنید.
```

```
        <source>Allow incoming connections</source>
        <translation>اجازه ورود و اتصالات</translation>
    
YES  
The translation "اجازه ورود و اتصالات" literally means "Allow entry and connections," which is somewhat incomplete and unnatural in Persian (Farsi) for the phrase "Allow incoming connections." The original English implies permitting connections that are incoming (i.e., arriving from outside). The word "incoming" should relate directly to "connections."

A better translation would be:  
"اجازه‌ی اتصال‌های ورودی"  
or more naturally:  
"اجازه اتصال‌های ورودی"  
or  
"اجازه اتصال‌های دریافتی"  

These phrases clearly convey "Allow incoming connections" in proper Persian.
```

```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>بندر پروکسی (به عنوان مثال 9050)
 </translation>
    
YES
The Persian translation includes an unnecessary trailing whitespace character (non-breaking space) after the number "9050". Additionally, the phrase "به عنوان مثال" is correct but less concise compared to the more common equivalent "مثلا". Also, there is no period at the end in the source, so punctuation is fine without it.

Correct translation:
بندر پروکسی (مثلا 9050)
```

```
        <source>Used for reaching peers via:</source>
        <translation>برای دسترسی به همسالان از طریق:
 </translation>
    
YES  
The word "همسالان" in Persian usually means "peers" in the context of age or social group, not network peers in Bitcoin or P2P context. The correct technical term for "peers" (network nodes) in this context is "همتایان". Also, there is an unnecessary trailing whitespace character after the colon.

Correct translation:  
برای دسترسی به همتایان از طریق:
```

```
        <source>Whether to show coin control features or not.</source>
        <translation>آیا ویژگی های کنترل سکه را نشان می دهد یا خیر.
 </translation>
    
YES
The translation has a trailing whitespace and an unnecessary newline at the end. Also, it literally translates as "Whether the coin control features show or not," which is somewhat awkward in Persian. A clearer and more natural translation would be:

آیا ویژگی‌های کنترل سکه نمایش داده شود یا خیر؟
```

```
        <source>Confirm options reset</source>
        <extracomment>Window title text of pop-up window shown when the user has chosen to reset options.</extracomment>
        <translation>باز نشانی گزینه ها را تأیید کنید
  </translation>
    
YES  
The translation includes an extra trailing whitespace (a non-breaking space) at the end, which should be removed to avoid formatting issues. Additionally, "باز نشانی" is less common in this technical context; a more standard term for "reset" in user interfaces is "تنظیم مجدد".  

Correct translation:  
بازنشانی گزینه‌ها را تأیید کنید
```

```
        <source>Client will be shut down. Do you want to proceed?</source>
        <extracomment>Text asking the user to confirm if they would like to proceed with a client shutdown.</extracomment>
        <translation>کلاینت خاموش خواهد شد.آیا میخواهید ادامه دهید؟</translation>
    
YES  
There is a whitespace issue: there should be a space after the period. Also, in Persian, it is more natural to use "خاموش می‌شود" with the proper spacing and verb conjugation. Additionally, "میخواهید" is better written as "می‌خواهید" with a half-space (zero-width non-joiner). The phrase "آیا می‌خواهید ادامه دهید؟" is correct in meaning but could be slightly more polite as "آیا مایلید ادامه دهید؟" but that is optional.

Correct translation:  
کلاینت خاموش خواهد شد. آیا می‌خواهید ادامه دهید؟
```

```
        <source>The configuration file is used to specify advanced user options which override GUI settings. Additionally, any command-line options will override this configuration file.</source>
        <extracomment>Explanatory text about the priority order of instructions considered by client. The order from high to low being: command-line, configuration file, GUI settings.</extracomment>
        <translation>از پرونده پیکربندی برای انتخاب گزینه های کاربر پیشرفته استفاده می شود که تنظیمات ونک را نادیده می شود. بعلاوه ، هر گزینه خط فرمان این پرونده پیکربندی را لغو می کند. 

 </translation>
    
YES  
The translation contains errors and awkward phrasing:

1. "گزینه های کاربر پیشرفته" is acceptable, but the phrase "که تنظیمات ونک را نادیده می شود" is incorrect. "ونک" appears to be a typo or nonsense word, probably intended as "رابط کاربری" or "رابط گرافیکی" ("GUI").
2. The verb "نادیده می شود" is singular for "options" (which is plural), should be fixed.
3. The phrase "هر گزینه خط فرمان این پرونده پیکربندی را لغو می کند" is incorrect because "گزینه" (option) cannot directly "لغو کردن" (cancel) "this configuration file." The intended meaning is "command-line options override this configuration file."
4. Unnecessary whitespace and a line break at the end.
5. More natural and clear Persian wording for "override" would be "بر تنظیمات ... اولویت دارند" or "برتری دارند" or "جایگزین می‌کنند."

Correct translation:  
از فایل پیکربندی برای مشخص کردن گزینه‌های پیشرفته کاربر استفاده می‌شود که تنظیمات رابط گرافیکی را نادیده می‌گیرند. علاوه بر این، هر گزینه خط فرمان بر این فایل پیکربندی اولویت دارد.
```

```
        <source>This change would require a client restart.</source>
        <translation>تغییرات منوط به ریست کاربر است.</translation>
    
YES  
The translation is not accurate and a bit unclear. The source says "This change would require a client restart." which means a single change necessitates restarting the client software. The word "تغییرات" is plural ("changes") but source is singular "This change". Also, "منوط به" means "conditional on" which is less direct than "would require". The word "کاربر" means "user", but the source refers to "client" (in software context) which is better translated as "کلاینت" or "نرم‌افزار کلاینت".

Correct translation:  
این تغییر نیازمند راه‌اندازی مجدد کلاینت است.
```

```
        <source>Your current spendable balance</source>
        <translation>موجودی قابل خرج در الان</translation>
    
YES
The phrase "در الان" is incorrect and unnatural in Persian. The correct phrasing for "Your current spendable balance" would be:

موجودی قابل خرج فعلی شما
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>موجودی شما در همین لحظه در آدرس های Watch only Addresses</translation>
    
YES  
The translation incorrectly mixes English and Farsi by leaving "Watch only Addresses" untranslated and uses redundant wording "در همین لحظه" which means "at this moment", not "current" in this context. Also, "watch-only addresses" should be translated properly into Persian.

Correct translation:  
موجودی فعلی شما در آدرس‌های فقط‌مشاهده‌ای
```

```
        <source>Transaction has %1 unsigned inputs.</source>
        <translation>%1Transaction has  unsigned inputs.</translation>
    
YES  
The translation contains the original English text mixed with a misplaced placeholder %1 and extra spaces, which makes it incorrect and not translated at all. Also, the placeholder %1 should appear in the correct position within the sentence in Persian script.  

Correct translation:  
معامله دارای %1 ورودی امضا نشده است.
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>نمی توان بیت کوین را شروع کرد: کنترل کننده کلیک برای پرداخت
 </translation>
    
YES  
There is an unnecessary trailing whitespace character (a non-breaking space) at the end of the translation. Also, a more concise and natural translation would use "عامل" instead of "کنترل کننده" for "handler" in this technical context.

Correct translation:  
نمی‌توان بیت‌کوین را شروع کرد: عامل کلیک برای پرداخت
```

```
        <source>Create a new wallet</source>
        <translation>کیف پول جدیدی ایجاد کنید
 </translation>
    
YES  
There is an unwanted trailing whitespace (a non-breaking space or similar) after the translated text which should be removed. Otherwise, the translation is accurate.

Correct translation:  
کیف پول جدیدی ایجاد کنید
```

```
        <source>Error: database transaction cannot be executed for wallet %s</source>
        <translation>خطا: تراکنش پایگاه داده را نمی توان برای کیف پول اجرا کرد %s</translation>
    
YES  
The placeholder %s should appear directly after "کیف پول" without a space before it, and the sentence structure is slightly awkward in Persian. A more natural and clearer translation would place %s immediately after "کیف پول" and clarify the phrase:

Correct translation:  
خطا: تراکنش پایگاه داده را نمی‌توان برای کیف پول %s اجرا کرد
```
</details>
