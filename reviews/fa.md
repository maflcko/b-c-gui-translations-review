# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>fa</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bfa%5D%20low%20quality)


```
        <source>Copy</source>
        <translation>ذخیره</translation>
    
YES
The translation of "Copy" as "ذخیره" is incorrect. "ذخیره" means "Save" in Persian, not "Copy".

Correct translation:
کپی
```

```
        <source>Unroutable</source>
        <translation>غیرقابل برنامه ریزی</translation>
    
YES
The translation of "Unroutable" as "غیرقابل برنامه ریزی" is incorrect. "غیرقابل برنامه ریزی" means "unprogrammable," which does not convey the correct meaning.

Correct translation:
غیرقابل مسیر‌یابی
```

```
        <source>Onion</source>
        <comment>network name</comment>
        <extracomment>Name of Tor network in peer info</extracomment>
        <translation>persian</translation>
    
YES
The translation is incorrect. "Onion" refers to the Tor network, and the translation "persian" is both inaccurate and unrelated.

Correct translation:
آنیون

Or, in some contexts, "تور" (Tor) or "شبکه آنیون" (Onion Network) may be used for clarity, but the best direct translation reflecting the original is:
آنیون
```

```
        <source>%1 m</source>
        <translation>%1 دقیقه قبل</translation>
    
YES
The translation is problematic because "%1 m" in the context likely stands for "%1 minutes" (simply a quantifier with unit: e.g., "5 m" = "5 minutes"), but the translation "%1 دقیقه قبل" means "%1 minutes ago", adding "قبل" ("ago"), which adds an unintended temporal context not present in the source.

Correct translation:
‏%1 دقیقه‏

Or, if space formatting from the source is critical:
%1 دقیقه
```

```
        <source>default wallet</source>
        <translation>کیف پول پیش فرض
 </translation>
    
YES
There is an unwanted trailing whitespace character at the end of the translation. Otherwise, the translation is accurate.

Correct translation:
کیف پول پیش‌فرض
```

```
        <source>Show general overview of wallet</source>
        <translation>نمایش کلی کیف پول
 </translation>
    
YES
There is an unwanted newline and possibly a non-breaking space at the end of the translation, which may lead to display/formatting issues. The translation itself is accurate.

Correct translation:
نمایش کلی کیف پول
```

```
        <source>Quit application</source>
        <translation>از "درخواست نامه"/ application خارج شو</translation>
    
YES
The translation "از 'درخواست نامه'/ application خارج شو" is problematic for several reasons:
- Mixing Persian ("درخواست نامه") and English ("application") is unnecessary and inaccurate.
- "درخواست نامه" does not accurately convey the meaning of "application" in the context of software; the proper Persian term is "برنامه".
- The structure is inconsistent and includes stray slashes and quotes.
- "خارج شو" is an imperative; a more neutral and standard translation would be appropriate for UI strings.

Correct translation:
از برنامه خارج شوید
```

```
        <source>Create a new wallet</source>
        <translation>کیف پول جدیدی ایجاد کنید
 </translation>
    
YES
There is an unnecessary newline and a stray whitespace character at the end of the translation. Also, the translation uses the imperative form ("ایجاد کنید") which may be less appropriate if the English is intended as a label (not a command).

Correct translation:
یک کیف پول جدید ایجاد کنید

Or, for a label/button:
ایجاد کیف پول جدید

Make sure there is no extra space or newline.
```

```
        <source>Backup wallet to another location</source>
        <translation>پشتیبان گیری از کیف پول به مکان دیگر
 </translation>
    
YES
There is an unwanted newline and a stray whitespace at the end of the translation. The translation otherwise accurately conveys the original meaning.

Correct translation:
پشتیبان‌گیری از کیف پول به مکان دیگر
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>کلیدهای خصوصی متعلق به کیف پول شما را رمزگذاری کنید
 </translation>
    
YES
There is a problematic whitespace issue: there is an unnecessary newline and a stray non-breaking space at the end of the translation. This causes formatting inconsistency.

Correct translation:
کلیدهای خصوصی متعلق به کیف پول خود را رمزگذاری کنید
```

```
        <source>Open URI…</source>
        <translation>تکثیر نشانی</translation>
    
YES
The translation is inaccurate. "تکثیر نشانی" means "Copy address", not "Open URI…". Additionally, "URI" should be kept transliterated or replaced meaningfully.

Correct translation:
باز کردن نشانی...
```

```
        <source>%1 behind</source>
        <translation>%1 قبل</translation>
    
YES
The translation "%1 قبل" is not accurate in Persian for "%1 behind". In the context of blockchains, "%1 behind" usually refers to being behind by a number of blocks or time units. The Persian phrase "%1 قبل" means "%1 ago", which does not convey the same meaning.

Correct translation:
%1 عقب

So the correct translation should be:
%1 عقب
```

```
        <source>Catching up…</source>
        <translation>در حال گرفتن..</translation>
    
YES
The translation "در حال گرفتن.." is not accurate. The English phrase "Catching up…" in the context of syncing generally refers to "در حال همگام‌سازی…" or "در حال بروزرسانی…". Additionally, the ellipsis should use three dots (…) not two periods (..).

Correct translation:
در حال همگام‌سازی…
```

```
        <source>Receiving addresses</source>
        <translation>ادرس درسافت</translation>
    
YES
There are spelling mistakes in the Persian translation and the translation is incomplete. The correct translation for "Receiving addresses" in Persian is:

آدرس‌های دریافت

Correct translation:
آدرس‌های دریافت
```

```
        <source>Open a bitcoin: URI</source>
        <translation>بارک کردن یک بیت‌کوین: URI</translation>
    
YES
The translation contains an error: "بارک کردن" is nonsensical and incorrect in Persian. The correct term for "Open" would be "باز کردن". The rest of the translation is reasonably accurate, though it is customary to maintain the URI and colon as in the original.

Correct translation:
باز کردن یک bitcoin: URI
```

```
        <source>Open Wallet</source>
        <translation>کیف پول را باز کنید
 </translation>
    
YES
There is an unwanted newline and extra whitespace at the end of the translation. The translation itself is accurate, but the formatting is problematic.

Correct translation:
کیف پول را باز کنید
```

```
        <source>Open a wallet</source>
        <translation>کیف پول را باز کنید
 </translation>
    
YES
There is an unwanted whitespace/line break at the end of the translation, which introduces formatting issues. The translation itself is accurate, but the extra whitespace should be removed.

Correct translation:
کیف پول را باز کنید
```

```
        <source>Create Wallet</source>
        <extracomment>Title of window indicating the progress of creation of a new wallet.</extracomment>
        <translation>ایجاد کیف پول
 </translation>
    
YES
There is an unwanted trailing newline and a non-breaking space character after the translation, causing format issues. The translation itself is accurate, but the extra whitespace should be removed.

Correct translation:
ایجاد کیف پول
```

```
        <source>Create wallet failed</source>
        <translation>کیف پول "ایجاد" نشد
 </translation>
    
YES
There are issues with the translation:
- The Persian translation uses quotation marks around "ایجاد" which is unnecessary and incorrect.
- The translation says '"ایجاد" نشد' (was not "created"), but the English is "Create wallet failed", which is better rendered as a direct equivalent to "Failed to create wallet".
- There is a stray whitespace/blank character at the end.

Correct translation:
ایجاد کیف پول انجام نشد
Or alternatively:
ایجاد کیف پول با شکست مواجه شد
```

```
        <source>Create wallet warning</source>
        <translation>هشدار کیف پول ایجاد کنید
 </translation>
    
YES
The translation incorrectly means "Create a wallet warning!" with the verb "ایجاد کنید" (imperative "create"), instead of the noun phrase "Create wallet warning" (as a warning title). Also, there is a stray whitespace character at the end.

Correct translation:
هشدار ایجاد کیف پول
```

```
        <source>Reset all client options to default.</source>
        <translation>تمام گزینه های مشتری را به طور پیش فرض بازنشانی کنید.
 </translation>
    
YES
There is an unnecessary newline or whitespace at the end of the translation. Also, a more accurate translation for "client" in the context of Bitcoin software is "کلاینت" instead of "مشتری". The phrase "به طور پیش فرض" should ideally be moved to before "بازنشانی کنید", making it more natural.

Correct translation:
تمام گزینه‌های کلاینت را به حالت پیش‌فرض بازنشانی کنید.
```

```
        <source>Allow incoming connections</source>
        <translation>اجازه ورود و اتصالات</translation>
    
YES
The translation is inaccurate and awkward. The Persian phrase "اجازه ورود و اتصالات" literally means "permission of entry and connections" and does not accurately convey "Allow incoming connections." The word "اتصالات" (connections) is correct, but the phrase should translate as "اجازه دادن به اتصالات ورودی" or more naturally, "اجازه به اتصالات ورودی بدهید".

Correct translation:
اجازه به اتصالات ورودی بدهید
```

```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>بندر پروکسی (به عنوان مثال 9050)
 </translation>
    
YES
There is a translation issue: "بندر" incorrectly means "port" as in "harbor", not as in "network port". The correct term in computer/network context is "پورت". There is also an unnecessary whitespace/line break at the end.

Correct translation:
پورت پروکسی (برای مثال ۹۰۵۰)
```

```
        <source>Used for reaching peers via:</source>
        <translation>برای دسترسی به همسالان از طریق:
 </translation>
    
YES
There is an unnecessary newline and non-breaking space at the end of the translation, causing formatting issues. The translation itself is correct, but the whitespace must be fixed.

Correct translation:
برای دسترسی به همسالان از طریق:
```

```
        <source>Whether to show coin control features or not.</source>
        <translation>آیا ویژگی های کنترل سکه را نشان می دهد یا خیر.
 </translation>
    
YES  
There is an extra space character at the end of the translation, and the translation is not entirely faithful—it's more of a question ("Does it show... or not?") than a neutral description matching the source ("Whether to show..."). The format specifiers are not present, but none are needed here.

Correct translation:
آیا ویژگی‌های کنترل سکه نمایش داده شود یا نه.

Or, for a closer rendering:
اینکه آیا ویژگی‌های کنترل سکه نمایش داده شوند یا خیر.
```

```
        <source>Confirm options reset</source>
        <extracomment>Window title text of pop-up window shown when the user has chosen to reset options.</extracomment>
        <translation>باز نشانی گزینه ها را تأیید کنید
  </translation>
    
YES
There is an unwanted whitespace character at the end of the translation line (a non-breaking space is present). Additionally, using the verb form may be better as "تأیید بازنشانی گزینه‌ها" for conciseness, but the current version is understandable. The whitespace needs to be removed.

Correct translation:
بازنشانی گزینه‌ها را تأیید کنید
```

```
        <source>Client will be shut down. Do you want to proceed?</source>
        <extracomment>Text asking the user to confirm if they would like to proceed with a client shutdown.</extracomment>
        <translation>کلاینت خاموش خواهد شد.آیا میخواهید ادامه دهید؟</translation>
    
YES
There is a missing space after the period. It should be "خواهد شد. آیا". Also, for better readability, "می‌خواهید" is more correct with a ZWNJ (zero-width non-joiner) between "می" and "خواهید".

Correct translation:
کلاینت خاموش خواهد شد. آیا می‌خواهید ادامه دهید؟
```

```
        <source>The configuration file is used to specify advanced user options which override GUI settings. Additionally, any command-line options will override this configuration file.</source>
        <extracomment>Explanatory text about the priority order of instructions considered by client. The order from high to low being: command-line, configuration file, GUI settings.</extracomment>
        <translation>از پرونده پیکربندی برای انتخاب گزینه های کاربر پیشرفته استفاده می شود که تنظیمات ونک را نادیده می شود. بعلاوه ، هر گزینه خط فرمان این پرونده پیکربندی را لغو می کند. 

 </translation>
    
YES
There are several problems in the translation:
1. "تنظیمات ونک" is likely a typographical error for "تنظیمات واسط کاربری" (GUI settings).
2. Whitespace issues: There is an extra space before and after the translation text, as well as an unnecessary line break at the end.
3. Some awkward phrasing: "نقض می‌شود" or "لغو می‌کند" is better than "نادیده می‌شود" in this context for "override".
4. Pluralization: "گزینه‌های کاربری پیشرفته" would read more natural.

Correct translation:
از پروندهٔ پیکربندی برای تعیین گزینه‌های پیشرفتهٔ کاربر استفاده می‌شود که تنظیمات واسط کاربری را نادیده می‌گیرد. همچنین هر گزینهٔ خط فرمان، این پروندهٔ پیکربندی را نادیده می‌گیرد.
```

```
        <source>This change would require a client restart.</source>
        <translation>تغییرات منوط به ریست کاربر است.</translation>
    
YES
The Persian translation is inaccurate and misleading. The source says "This change would require a client restart," but the translation implies "The changes depend on the user resetting (something)," which is not the intended meaning. Also, "ریست کاربر" translates to "user reset," not "client restart."

Correct translation:
این تغییر نیازمند راه‌اندازی مجدد برنامه است.
```

```
        <source>Your current spendable balance</source>
        <translation>موجودی قابل خرج در الان</translation>
    
YES
The translation is understandable but not natural or idiomatic in Persian and contains a minor grammatical issue. "در الان" is awkward and ungrammatical. A more appropriate translation would be:
موجودی فعلی قابل خرج شما

Correct translation:
موجودی فعلی قابل خرج شما
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>موجودی شما در همین لحظه در آدرس های Watch only Addresses</translation>
    
YES
The translation is problematic for two main reasons:
1. The English phrase "watch-only addresses" is mistranslated by mixing Persian and English. Using "آدرس‌های فقط قابل مشاهده" or "آدرس‌های صرفاً قابل مشاهده" would be clearer.
2. The phrase "در همین لحظه" ("at this very moment") adds meaning not present in the original.

Correct translation:
موجودی فعلی شما در آدرس‌های فقط قابل مشاهده
```

```
        <source>Transaction has %1 unsigned inputs.</source>
        <translation>%1Transaction has  unsigned inputs.</translation>
    
YES
The translation is incorrect. It is not in Persian ('fa') and mainly repeats the English text, which is a clear error.

Correct translation:
تراکنش دارای %1 ورودی امضا نشده است.
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>نمی توان بیت کوین را شروع کرد: کنترل کننده کلیک برای پرداخت
 </translation>
    
YES
There is an unnecessary whitespace and line break at the end of the translation. The translation is otherwise accurate, but should not contain the stray space and line break.

Correct translation:
نمی‌توان بیت‌کوین را شروع کرد: کنترل‌کننده کلیک برای پرداخت
```

```
        <source>Create a new wallet</source>
        <translation>کیف پول جدیدی ایجاد کنید
 </translation>
    
YES
There is an unnecessary newline and a stray whitespace character at the end of the translation. Also, the translation uses the imperative form ("ایجاد کنید") which may be less appropriate if the English is intended as a label (not a command).

Correct translation:
یک کیف پول جدید ایجاد کنید

Or, for a label/button:
ایجاد کیف پول جدید

Make sure there is no extra space or newline.
```

```
        <source>Error: database transaction cannot be executed for wallet %s</source>
        <translation>خطا: تراکنش پایگاه داده را نمی توان برای کیف پول اجرا کرد %s</translation>
    
YES
The word order in the Persian translation does not correctly preserve the format specifier '%s' position, which should appear after "کیف پول" as in the source ("wallet %s"). The current translation places "%s" at the end, which is incorrect and may cause confusion.

Correct translation:
خطا: تراکنش پایگاه داده را نمی‌توان برای کیف پول %s اجرا کرد
```
</details>

Number of issues: 35.
