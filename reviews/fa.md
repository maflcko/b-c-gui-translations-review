# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>fa</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bfa%5D%20request)


<!-- cache_translation_check_fa_a7bdf359e7b71f51b1f3a92b665e0b3fcf4816feafcc336de4a56fe9c6a98797 -->
```
        <source>Unroutable</source>
        <translation>غیرقابل برنامه ریزی</translation>
    
ERR
The translation of "Unroutable" as "غیرقابل برنامه ریزی" is incorrect. "غیرقابل برنامه ریزی" means "unprogrammable," which does not convey the correct meaning.

Correct translation:
غیرقابل مسیر‌یابی
```

<!-- cache_translation_check_fa_249f2c693c28656cdfeeffc27e27591f782b3e0451c8e5e24734fbfc3f2c7e4b -->
```
        <source>Onion</source>
        <comment>network name</comment>
        <extracomment>Name of Tor network in peer info</extracomment>
        <translation>persian</translation>
    
ERR
The translation is incorrect. "Onion" refers to the Tor network, and the translation "persian" is both inaccurate and unrelated.

Correct translation:
آنیون

Or, in some contexts, "تور" (Tor) or "شبکه آنیون" (Onion Network) may be used for clarity, but the best direct translation reflecting the original is:
آنیون
```

<!-- cache_translation_check_fa_0e3411f61d8997a8883221ebaa0b62350ce382270565d1b638120415fc43d1e8 -->
```
        <source>%1 m</source>
        <translation>£%1 گیگابایت</translation>
    
ERR
The translation is incorrect for several reasons. First, it includes a pound sterling symbol (£) which is not present in the source. Second, the source unit "m" (which likely stands for minutes or mega) has been incorrectly translated as "گیگابایت" (Gigabyte). Third, the format specifier and characters are poorly ordered.

Correct translation:
%1 دقیقه (if minutes) or %1 m (if shorthand)
```

<!-- cache_translation_check_fa_f6224e493124f5abfc86cf0c520a02f6c24e697c2fa0e274b4026027e8f64b1f -->
```
        <source>default wallet</source>
        <translation>کیف پول پیش فرض
 </translation>
    
ERR
There is an unwanted trailing whitespace character at the end of the translation. Otherwise, the translation is accurate.

Correct translation:
کیف پول پیش‌فرض
```

<!-- cache_translation_check_fa_049e4977e0b9c136a446af2935f8a6c267db8c7e5bb8b03a8e1c8ad62d8424c0 -->
```
        <source>&amp;Overview</source>
        <translation>بازبینی</translation>
    
ERR
The translation omits the ampersand (&) which is used for shortcut keys and must appear exactly once, as in the source.

Correct translation:
&بازبینی
```

<!-- cache_translation_check_fa_defdf72c739d126115a88d33828162d5a74be1229e7ae2bd5bb70a3e00d066ec -->
```
        <source>Show general overview of wallet</source>
        <translation>نمایش کلی کیف پول
 </translation>
    
ERR
There is an unwanted newline and possibly a non-breaking space at the end of the translation, which may lead to display/formatting issues. The translation itself is accurate.

Correct translation:
نمایش کلی کیف پول
```

<!-- cache_translation_check_fa_e1b968a21fd0c1655aee28d6e77e15b2ecaf77335e11a44c7d8e1517bd0b6aa5 -->
```
        <source>&amp;Transactions</source>
        <translation>تراکنش</translation>
    
ERR
The translation omits the ampersand (&) which denotes a shortcut key, and it should also ideally use the plural form for "Transactions." The correct translation:

Correct translation:
&تراکنش‌ها
```

<!-- cache_translation_check_fa_d5a73cca1b4510941a75890091f651bccb8d99399d501ab9ccddfc567449264b -->
```
        <source>E&amp;xit</source>
        <translation>خروج</translation>
    
ERR
The translation omits the '&' which designates the shortcut key in the UI. This should exist exactly once in the translation, wherever most appropriate in the word.

Correct translation:
خرو&ج
```

<!-- cache_translation_check_fa_89bf8bdc428c31c4e92befda1e8a5e029bbd704be17a07c171a4797ff6608fff -->
```
        <source>Quit application</source>
        <translation>از "درخواست نامه"/ application خارج شو</translation>
    
ERR
The translation "از 'درخواست نامه'/ application خارج شو" is problematic for several reasons:
- Mixing Persian ("درخواست نامه") and English ("application") is unnecessary and inaccurate.
- "درخواست نامه" does not accurately convey the meaning of "application" in the context of software; the proper Persian term is "برنامه".
- The structure is inconsistent and includes stray slashes and quotes.
- "خارج شو" is an imperative; a more neutral and standard translation would be appropriate for UI strings.

Correct translation:
از برنامه خارج شوید
```

<!-- cache_translation_check_fa_2be2fb47339483449378e7e843f92cca846f0f9016240873a4634f27bd213904 -->
```
        <source>About &amp;Qt</source>
        <translation>درباره Qt</translation>
    
ERR
The translation omitted the '&' character, which is used for shortcut keys and should appear exactly once in the translation, positioned appropriately.

Correct translation:
درباره &Qt
```

<!-- cache_translation_check_fa_66906f4b9c1777e6f01b75fb1aacc605c368aa5e2f8afb677e2c2009ad27f7c2 -->
```
        <source>Create a new wallet</source>
        <translation>کیف پول جدیدی ایجاد کنید
 </translation>
    
ERR
There is an unnecessary newline and a stray whitespace character at the end of the translation. Also, the translation uses the imperative form ("ایجاد کنید") which may be less appropriate if the English is intended as a label (not a command).

Correct translation:
یک کیف پول جدید ایجاد کنید

Or, for a label/button:
ایجاد کیف پول جدید

Make sure there is no extra space or newline.
```

<!-- cache_translation_check_fa_27b8fface7ad933028fd7c3b6e207b4c92c1204476b6c0216834e333c1fc284a -->
```
        <source>Backup wallet to another location</source>
        <translation>پشتیبان گیری از کیف پول به مکان دیگر
 </translation>
    
ERR
There is an unwanted newline and a stray whitespace at the end of the translation. The translation otherwise accurately conveys the original meaning.

Correct translation:
پشتیبان‌گیری از کیف پول به مکان دیگر
```

<!-- cache_translation_check_fa_04a5e2341951f6604b2a19ade6f0be71ff69021e4eb181fc8debab537db0b9ad -->
```
        <source>&amp;Send</source>
        <translation>ارسال</translation>
    
ERR
The translation is missing the '&' indicating the shortcut key, which should exist exactly once in the translation.

Correct translation:
&ارسال
```

<!-- cache_translation_check_fa_7208f78687c70e3b96d66fc266043247ac2af1cd911e9f5b51b4c3801249ef81 -->
```
        <source>&amp;Receive</source>
        <translation>دریافت</translation>
    
ERR
The translation omits the ampersand (&) which is used to indicate a shortcut key in menus. It should appear exactly once, in any position. 

Correct translation:
&دریافت
```

<!-- cache_translation_check_fa_0142a4b55a33e18d080b38800330945e7b8308323670c2b3d5b33b7633e02a03 -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation>رمزنگاری کیف پول</translation>
    
ERR
The translation is missing the ampersand (&) which is used for the shortcut key in the source string. The ampersand must appear exactly once in the translation.

Correct translation:
&رمزنگاری کیف پول…
```

<!-- cache_translation_check_fa_a5c3379b2b838238864654e31b1a69a65fc35044d60be9f37393ec6f595c29de -->
```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>کلیدهای خصوصی متعلق به کیف پول شما را رمزگذاری کنید
 </translation>
    
ERR
There is a problematic whitespace issue: there is an unnecessary newline and a stray non-breaking space at the end of the translation. This causes formatting inconsistency.

Correct translation:
کلیدهای خصوصی متعلق به کیف پول خود را رمزگذاری کنید
```

<!-- cache_translation_check_fa_06668d9dd49edc9f773e37d9a8e41c155f59e8165f3c17a1246ca4392e71b169 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>نسخه پشتیبان کیف پول</translation>
    
ERR
The translation omits the ampersand (&) which is used to indicate a shortcut key in the UI. It must appear exactly once in the translation. Additionally, the ellipsis (…) at the end of the source text is missing.

Correct translation:
&amp;نسخه پشتیبان کیف پول…
```

<!-- cache_translation_check_fa_0d7a280f03fd85475edf6b4a9e76e4ea7f4236a0721654bd42f065517b4932fb -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>تغییر عبارت عبور</translation>
    
ERR
The translation omits the ampersand (&), which is needed exactly once, as in the source, to indicate a shortcut key. Additionally, the Persian ellipsis "…" from the source is missing in the translation.

Correct translation:
تغییر &عبارت عبور…
```

<!-- cache_translation_check_fa_749baacd3947af2dce20c2f7fc5631a521d4a62b804840531dd17401ff002229 -->
```
        <source>Sign &amp;message…</source>
        <translation>ثبت &amp;پیام</translation>
    
ERR
The translation for "Sign &message…" as "ثبت &پیام" is inaccurate. "ثبت" means "register" or "record," whereas "Sign" should be translated as "امضا," which means "sign" (as in a digital signature). Additionally, the ellipsis (…) at the end of the English source is missing in the translation.

Correct translation:
امضای &پیام…
```

<!-- cache_translation_check_fa_70ed9425ca1abbae795274cbff9217f2320ca016f2680a250c3774dab22703e8 -->
```
        <source>&amp;Verify message…</source>
        <translation>پیام تایید</translation>
    
ERR
The translation does not accurately capture the meaning or the shortcut key (&). "&Verify message…" should be translated as «&تأیید پیام…», preserving the ampersand for the shortcut and the ellipsis.

Correct translation:
&تأیید پیام…
```

<!-- cache_translation_check_fa_e1bdb46722b8824c2d1dcf0590a20a1613fafc5d97aebd4b93fdb89a44adc7ec -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>بارگیری PSBT از پرونده</translation>
    
ERR
The translation omits the ampersand (&) which is used to indicate a shortcut key in the source. The ellipsis (…) is also missing from the translation.

Correct translation:
&amp;بارگیری PSBT از پرونده…
```

<!-- cache_translation_check_fa_b548e2a87bec4707788930745a7386cbdf7d1ba783e372f991b025ecf9fd4c45 -->
```
        <source>Open &amp;URI…</source>
        <translation>تکثیر نشانی</translation>
    
ERR
The translation "تکثیر نشانی" means "Copy address", which is incorrect for "Open &URI…". Additionally, the '&' shortcut key is missing, and the translation does not accurately convey the meaning of opening a URI.

Correct translation:
‏باز کردن &URI…
```

<!-- cache_translation_check_fa_87a3db81e2c41126bbfa96aa03af24d5e0a89bfe51dd6baf887fac351abdfaed -->
```
        <source>&amp;File</source>
        <translation>فایل</translation>
    
ERR
The shortcut indicator '&' is missing in the translation. It must appear exactly once.

Correct translation:
&فایل
```

<!-- cache_translation_check_fa_283812e5028a8d8e92e8254fb6fc8723c41ed54cdac78b4007aaf86aba50e093 -->
```
        <source>&amp;Settings</source>
        <translation>تنظیمات</translation>
    
ERR
The translation omits the '&' which indicates the shortcut key in the source. The ampersand must appear exactly once in the translation, positioned appropriately.

Correct translation:
&amp;تنظیمات
```

<!-- cache_translation_check_fa_c336c72d76324529caffc3a094647f26136e227fcba604a43655ca0697ee49b7 -->
```
        <source>&amp;Help</source>
        <translation>راهنما</translation>
    
ERR
The translation omits the ampersand (&), which indicates the shortcut key. It should appear exactly once in the translation, corresponding to its use in the source.

Correct translation:
&راهنما
```

<!-- cache_translation_check_fa_08c6fb9301d2cb28dff689bc48125485e722b0d44849647f7842f3b64a612cb1 -->
```
        <source>&amp;Command-line options</source>
        <translation>گزینه های خط فرمان</translation>
    
ERR
The translation omits the '&' symbol, which is used to indicate a shortcut key and should appear exactly once in the translation. Also, there should be no extra spaces.

Correct translation:
&گزینه‌های خط فرمان
```

<!-- cache_translation_check_fa_cf8236144d50646befbf9c7b23b363cccc4d834d2467ffb54ba6f337e4ad5706 -->
```
        <source>%1 behind</source>
        <translation>%1 قبل</translation>
    
ERR
The translation "%1 قبل" is not accurate in Persian for "%1 behind". In the context of blockchains, "%1 behind" usually refers to being behind by a number of blocks or time units. The Persian phrase "%1 قبل" means "%1 ago", which does not convey the same meaning.

Correct translation:
%1 عقب

So the correct translation should be:
%1 عقب
```

<!-- cache_translation_check_fa_77f2798f2e0861b5283b6c3ebe8d0c9f8616ba356a0bb11b6fb690e5f6c193c6 -->
```
        <source>Catching up…</source>
        <translation>در حال گرفتن..</translation>
    
ERR
The translation "در حال گرفتن.." is not accurate. The English phrase "Catching up…" in the context of syncing generally refers to "در حال همگام‌سازی…" or "در حال بروزرسانی…". Additionally, the ellipsis should use three dots (…) not two periods (..).

Correct translation:
در حال همگام‌سازی…
```

<!-- cache_translation_check_fa_bd53b7c306c63701b103637d515c79057e3b3e3cf0fcc5231378e5bb2ef6da40 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>بارگیری PSBT از &amp;clipboard…</translation>
    
ERR
The word "clipboard" should be translated into Persian. Additionally, the placement of the &amp; is inconsistent with Persian keyboard shortcuts (if implemented), but the main issue is that "clipboard" is untranslated, which reduces user comprehensibility.

Correct translation:
بارگیری PSBT از &amp;کلیپ‌بورد…
```

<!-- cache_translation_check_fa_f3db1a0a815eba511db4dc1530240bba104d9123e88af75d062fe56cf46fdfcc -->
```
        <source>&amp;Sending addresses</source>
        <translation>ادرس ارسال</translation>
    
ERR
The translation omits the ampersand '&' (shortcut key) and does not include the Persian word for "addresses" in the plural form. The correct translation should also preferably localize "addresses" as "آدرس‌ها" or "نشانی‌ها", and include the shortcut '&'.

Correct translation:
&آدرس‌های ارسال
```

<!-- cache_translation_check_fa_6d2a7e757a11ef15e1a6795b5e99228ace8ccb3224ec66adbfe39ae042a557e9 -->
```
        <source>&amp;Receiving addresses</source>
        <translation>ادرس درسافت</translation>
    
ERR
The translation contains spelling errors ("ادرس" should be "آدرس" and "درسافت" should be "دریافت") and omits the ampersand (&) used for the shortcut key, which should appear exactly once in the translation. The correct translation is:

Correct translation:
&آدرس‌های دریافت
```

<!-- cache_translation_check_fa_06cdf35986fb400e249d18e416c233edb65506a9e220c04d88b93772ad1558ef -->
```
        <source>Open a bitcoin: URI</source>
        <translation>بارک کردن یک بیت‌کوین: URI</translation>
    
ERR
The translation contains an error: "بارک کردن" is nonsensical and incorrect in Persian. The correct term for "Open" would be "باز کردن". The rest of the translation is reasonably accurate, though it is customary to maintain the URI and colon as in the original.

Correct translation:
باز کردن یک bitcoin: URI
```

<!-- cache_translation_check_fa_3517618d67dc76c3f6b4cd9197b3a24ccb92cdbba72bd9e0469f1e1bb30c7e2d -->
```
        <source>Open Wallet</source>
        <translation>کیف پول را باز کنید
 </translation>
    
ERR
There is an unwanted newline and extra whitespace at the end of the translation. The translation itself is accurate, but the formatting is problematic.

Correct translation:
کیف پول را باز کنید
```

<!-- cache_translation_check_fa_130de10a30b2b3874b08b6a90cf34b29b9c8356b2d39cb0e0d84d6a707572bd5 -->
```
        <source>Open a wallet</source>
        <translation>کیف پول را باز کنید
 </translation>
    
ERR
There is an unwanted whitespace/line break at the end of the translation, which introduces formatting issues. The translation itself is accurate, but the extra whitespace should be removed.

Correct translation:
کیف پول را باز کنید
```

<!-- cache_translation_check_fa_e23c332ec97a73673f7384517030e444401ac089205cde6fdb63c9feb316cca0 -->
```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>برای دریافت لیستی از گزینه های خط فرمان بیت کوین ، پیام راهنمایی %1 را نشان دهید</translation>
    
ERR
Issues:
- Minor grammatical/wording problems: "پیام راهنمایی %1" is awkward; "پیام راهنمای %1" is more natural.
- Punctuation/spacing: there's an extra space before the Persian comma and uses a space before "،". Also use of "نشان دهید" is acceptable but "نمایش دهید" or "نمایش دهید" is more natural.
- Prefer "گزینه‌های" (with ezafe/possessive) or "گزینه‌های ممکن" for clarity.

Correct translation:
برای دریافت فهرستی از گزینه‌های خط فرمان بیت‌کوین، پیام راهنمای %1 را نمایش دهید
```

<!-- cache_translation_check_fa_0d17d8b87c9cf4adef9efc58fc4035e74eb3cd736f7833be6cb83c9440701c9f -->
```
        <source>&amp;Window</source>
        <translation>پنجره</translation>
    
ERR
The translation does not include the '&' shortcut marker, which should appear exactly once in the translation to correspond to the original.

Correct translation:
&پنجره
or
پنجره&

Both are acceptable as long as '&' appears exactly once.
```

<!-- cache_translation_check_fa_736d1016d58601a0e12775ee688cea62147d82523c07ee290cec3ea25ddb88c5 -->
```
        <source>&amp;Hide</source>
        <translation>مخفی کن</translation>
    
ERR
The translation omits the '&' which indicates the shortcut key in the source. It should appear exactly once in the translation.

Correct translation:
&مخفی کن
or
مخفی &کن

Either placement is acceptable as long as '&' exists exactly once.
```

<!-- cache_translation_check_fa_a0c3eac4788b7e6677e2b6fc5649dcbb58de055ec4e67f82172b21fe768a4d4f -->
```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>کیف پول است &lt;b&gt; رمزگذاری شده &lt;/b&gt; و در حال حاضر &lt;b&gt; تفسیر شده است &lt;/b&gt;
 </translation>
    
ERR
The translation has several issues:
1. **Incorrect Translation**: The word "unlocked" is translated as "تفسیر شده است", which means "is interpreted" or "is commented". In the context of a Bitcoin wallet, "قفل‌گشایی شده" or "باز" is appropriate.
2. **Grammar and Word Order**: The Persian word order is incorrect. The verb "است" (is) should typically come after the adjective or at the end of the phrase.
3. **Whitespace Issues**: There are unnecessary spaces added inside the `<b>` tags and trailing whitespace/hidden characters at the end of the string.

Correct translation:
کیف پول <b>رمزگذاری شده</b> است و در حال حاضر <b>قفل‌گشایی شده</b> است
```

<!-- cache_translation_check_fa_e2826150cfbd2233a38df923178d63b042ebfdc5e8623e14c539f578d73289f9 -->
```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>کیف پول است &lt;b&gt; رمزگذاری شده &lt;/b&gt; و در حال حاضر &lt;b&gt; تفسیر شده &lt;/b&gt;
 </translation>
    
ERR
The translation is problematic for several reasons. First, the Persian word "تفسیر شده" means "interpreted" or "commentated," which is incorrect; the correct word for "locked" is "قفل‌شده". Second, the word order is awkward; the verb "است" (is) usually comes at the end of the sentence or clause in Persian. Third, there is unnecessary spacing around the HTML tags and a trailing non-breaking space/newline.

Correct translation:
کیف پول **رمزگذاری شده** و در حال حاضر **قفل‌شده** است
```

<!-- cache_translation_check_fa_32c014b01cfd89415f5a00288074e89150943f194fa357e7ad0122deb2f4ade7 -->
```
        <source>&amp;Copy address</source>
        <translation>تکثیر نشانی</translation>
    
ERR
The translation does not include the '&' shortcut indicator, which should appear exactly once, as in the source. Also, the standard translation for "Copy" in this context is "رونوشت برداشتن" or "کپی". "تکثیر" is less idiomatic.

Correct translation:
&کپی نشانی
```

<!-- cache_translation_check_fa_ece9918470acec4dc72c6d7aaa51f72faa62b5dc11271369c167dbd9167e1c47 -->
```
        <source>Copy &amp;label</source>
        <translation>تکثیر برچسب</translation>
    
ERR
The translation omits the '&' which is used for shortcut keys, and uses "تکثیر" which means "reproduction/duplication" rather than the more typical "کپی" ("copy") in software UI. The proper translation for software context should use "کپی" and include the '&'.

Correct translation:
کپی &برچسب
```

<!-- cache_translation_check_fa_2d9a461ee679605e8f5999d0230b0293748e8bdb6b7308b632c0f1eace5f1c48 -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>شناسه و تراکنش و نمایه خروجی را کپی کنید</translation>
    
ERR
The translation misplaces the structure and meaning. It says "Copy the ID and transaction and output index," which is incorrect. It also lacks the '&' to indicate the shortcut key.

Correct translation:
شناسه &amp;تراکنش و شاخص خروجی را کپی کنید
```

<!-- cache_translation_check_fa_b492c1e74d33f47ee6016a55cd8bb8c41a2dcc034d5c81d483faa7982b87f6b4 -->
```
        <source>Can vary +/- %1 satoshi(s) per input.</source>
        <translation>می توانید + / - %1 (ساتوشی) در هر ورودی متفاوت باشد.</translation>
    
ERR
The Persian translation is grammatically incorrect and awkwardly phrased (verb/subject mismatch and unnecessary spaces/parentheses around +/- and "ساتوشی"). The format specifier %1 is preserved but spacing around "+/-" should be normalized.

Correct translation:
می‌تواند به ازای هر ورودی تا +/-%1 ساتوشی نوسان داشته باشد.
```

<!-- cache_translation_check_fa_2258c3973f215157538e50f878228df38aa9032914217e400df89fc7db7c0bb3 -->
```
        <source>Create Wallet</source>
        <extracomment>Title of window indicating the progress of creation of a new wallet.</extracomment>
        <translation>ایجاد کیف پول
 </translation>
    
ERR
There is an unwanted trailing newline and a non-breaking space character after the translation, causing format issues. The translation itself is accurate, but the extra whitespace should be removed.

Correct translation:
ایجاد کیف پول
```

<!-- cache_translation_check_fa_f429223058196570f992619a0d6e080c83ba570773ee9e6eb5475136f33f927a -->
```
        <source>Create wallet failed</source>
        <translation>کیف پول "ایجاد" نشد
 </translation>
    
ERR
There are issues with the translation:
- The Persian translation uses quotation marks around "ایجاد" which is unnecessary and incorrect.
- The translation says '"ایجاد" نشد' (was not "created"), but the English is "Create wallet failed", which is better rendered as a direct equivalent to "Failed to create wallet".
- There is a stray whitespace/blank character at the end.

Correct translation:
ایجاد کیف پول انجام نشد
Or alternatively:
ایجاد کیف پول با شکست مواجه شد
```

<!-- cache_translation_check_fa_3510efb7d9910000f316387e42a1b19b9ddaea646f2cf8ed6c32eb2803b55f5a -->
```
        <source>Create wallet warning</source>
        <translation>هشدار کیف پول ایجاد کنید
 </translation>
    
ERR
The translation incorrectly means "Create a wallet warning!" with the verb "ایجاد کنید" (imperative "create"), instead of the noun phrase "Create wallet warning" (as a warning title). Also, there is a stray whitespace character at the end.

Correct translation:
هشدار ایجاد کیف پول
```

<!-- cache_translation_check_fa_58d389175ecad158f8714dc85ea0958ce7fa0e09f29c892397c4e3463380c291 -->
```
        <source>Open Wallet</source>
        <extracomment>Title of window indicating the progress of opening of a wallet.</extracomment>
        <translation>کیف پول را باز کنید
 </translation>
    
ERR
The Persian translation is correct in meaning but contains stray whitespace/newline (and a trailing NBSP). Also for a window title a shorter noun phrase is more typical.

Correct translations (choose one) without extra whitespace:
- کیف پول را باز کنید
- باز کردن کیف پول
```

<!-- cache_translation_check_fa_97158f4e7f5127d0976ac37d3c803ed9bdbb3581a4710f9c7d389591cfdfc33e -->
```
        <source>Create Wallet</source>
        <translation>ایجاد کیف پول
 </translation>
    
ERR
The Persian translation is correct in meaning ("Create Wallet" → "ایجاد کیف پول"), but it contains extraneous whitespace/newline after the text (a trailing newline and space). Remove the trailing whitespace.

Correct translation:
ایجاد کیف پول
```

<!-- cache_translation_check_fa_63bf19c3c89057a2e1c8df568f73c6932fd2394cf7b6132457c3e00af0d7da4d -->
```
        <source>&amp;Label</source>
        <translation>برچسب</translation>
    
ERR
The shortcut key indicator (&amp;) is missing from the translation. According to the instructions, it must exist exactly once in the translation if it is present in the source.

Correct translation:
&amp;برچسب
```

<!-- cache_translation_check_fa_4861730c791e1d013f0719df0c9a364e6c52343f51d37b5a5f5ccaa5c7ed6b53 -->
```
        <source>The label associated with this address list entry</source>
        <translation>برچسب مرتبط با لیست آدرس ورودی</translation>
    
ERR
The Persian translation "برچسب مرتبط با لیست آدرس ورودی" is slightly inaccurate. It translates to "The label associated with the input address list," which misinterprets "address list entry." The "entry" is the item in the list, not an "input" (ورودی).

Correct translation:
برچسب مرتبط با این ورودیِ لیست آدرس
```

<!-- cache_translation_check_fa_57cfbea7d53fbc8cd2e3880b96bf814e2218141e61d6fc020ffa83ff0a410ee5 -->
```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>برچسب مرتبط با لیست آدرس ورودی می باشد. این می تواند فقط  برای آدرس های ارسالی اصلاح شود.</translation>
    
ERR
The translation is incorrect. The Persian text uses "برچسب" (label) instead of "آدرس" (address) for the first word. Additionally, "لیست آدرس ورودی" (address list entry) is poorly phrased, and there is an unnecessary double space.

Correct translation:
آدرس مرتبط با این ورودی لیست آدرس. این تنها برای آدرس‌های ارسالی قابل تغییر است.
```

<!-- cache_translation_check_fa_8e6fec6828d50d58f0e878f578483ff7f3fc3cddf27de42f7db9c9fa3280cc3a -->
```
        <source>&amp;Address</source>
        <translation>آدرس</translation>
    
ERR
The translation is missing the shortcut key indicator '&', which must appear exactly once as per the instructions.

Correct translation:
&آدرس
```

<!-- cache_translation_check_fa_e92cd1f4acd621d868b56023036f400f9fe4ea3bdf03fa54bc9071f9a5a4fb05 -->
```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>آدرس وارد شده "%1" در حال حاظر در دفترچه آدرس ها موجود است با برچسب "%2" .</translation>
    
ERR
The Persian translation contains a spelling error: "حاظر" should be "حاضر". Additionally, there is a stray space before the final period.

Correct translation:
آدرس وارد شده "%1" در حال حاضر با برچسب "%2" در دفترچه آدرس‌ها موجود است.
```

<!-- cache_translation_check_fa_58f9c95722e9eda8a2c78c07292f54cc20302615592466c8167820400338b09c -->
```
        <source>Reset all client options to default.</source>
        <translation>تمام گزینه های مشتری را به طور پیش فرض بازنشانی کنید.
 </translation>
    
ERR
There is an unnecessary newline or whitespace at the end of the translation. Also, a more accurate translation for "client" in the context of Bitcoin software is "کلاینت" instead of "مشتری". The phrase "به طور پیش فرض" should ideally be moved to before "بازنشانی کنید", making it more natural.

Correct translation:
تمام گزینه‌های کلاینت را به حالت پیش‌فرض بازنشانی کنید.
```

<!-- cache_translation_check_fa_0efcad36eb589738fc073d8e2cacdbf334051d22bab5f02380aef11220d7c544 -->
```
        <source>&amp;Reset Options</source>
        <translation>تنظیم مجدد گزینه ها</translation>
    
ERR
The translation is missing the ampersand '&' which indicates a shortcut key in the source. It should exist exactly once in the translation.

Correct translation:
‏&تنظیم مجدد گزینه‌ها
```

<!-- cache_translation_check_fa_0061321cafcbcb309586151928f1df5968d97cdc7433592efb89b9e1e0cdcbae -->
```
        <source>&amp;Network</source>
        <translation>شبکه</translation>
    
ERR
The ampersand (&) denoting the shortcut key is missing in the translation. It should appear exactly once in the translated text.

Correct translation:
&amp;شبکه
```

<!-- cache_translation_check_fa_bebfb3e038f4092520b6955f381c59c14a61a15ff006379f91c5c67c3276b564 -->
```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>تعداد رشته های تأیید اسکریپت را تنظیم کنید.  مقادیر منفی مربوط به تعداد هسته هایی است که می خواهید برای سیستم آزاد بگذارید.</translation>
    
ERR
The Persian (fa) translation is mostly correct in meaning but has minor formatting and stylistic issues: there is an extra space after the period and some improvements to Persian punctuation/word-joining would make it more natural.

Corrected translation:
تعداد رشته‌های تأیید اسکریپت را تنظیم کنید. مقادیر منفی نشان‌دهندهٔ تعداد هسته‌هایی است که می‌خواهید برای سیستم آزاد بگذارید.
```

<!-- cache_translation_check_fa_06e7957dcc27f7e1aa633ce414d57691b3fd474bbb2075e8bb6b6105d2810a4f -->
```
        <source>W&amp;allet</source>
        <translation>کیف پول</translation>
    
ERR
The Persian translation is missing the shortcut indicator "&" present in the source. The source has a single "&" (W&amp;allet) and the translation must include exactly one "&" as well.

Correct translation:
&کیف پول
```

<!-- cache_translation_check_fa_0cca8d4fa38d291fac6b26254f8ffc1962855e8543f34728192591c09061f5f0 -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>به طور پیش‌فرض از مقدار &amp;کارمزد کم کنید</translation>
    
ERR
Translation is understandable but slightly unnatural in Persian word order and missing the direct object marker "را". Also prefer "مبلغ" over "مقدار" in this Bitcoin context.

Correct translation:
به‌طور پیش‌فرض، &کارمزد را از مبلغ کم کنید
```

<!-- cache_translation_check_fa_0ffd3d72949a9afee4816188d2ea852bee61cea734000141e7ba9f05439c1597 -->
```
        <source>Enable coin &amp;control features</source>
        <translation>فعال کردن قابلیت سکه و کنترل</translation>
    
ERR
The Persian translation is grammatically awkward and it omits the single & shortcut marker from the source. The source places & before "control" (i.e. "&control") and the translation should preserve exactly one ampersand. Also "قابلیت سکه و کنترل" reads as "coin and control capability" rather than "coin control features."

Correct translation:
فعال‌سازی قابلیت‌های &کنترل سکه
```

<!-- cache_translation_check_fa_63384f24902bc4bc92cfb05e33d242d7042f305052f53125b6ada75bcaf2c676 -->
```
        <source>&amp;External signer script path</source>
        <translation>مسیر اسکریپت امضاکنندهٔ جانبی</translation>
    
ERR
The translation is accurate Persian but it omits the required shortcut ampersand (&) present in the source. The source has a single & (indicating a keyboard shortcut) and the translation must include exactly one & as well.

Correct translation (include & once, no extra spaces):
&amp;مسیر اسکریپت امضاکنندهٔ جانبی
```

<!-- cache_translation_check_fa_abe229a8b088530253b5414a2f61b523bdc68433b5ddc291fcee465dd7b512a7 -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>اجازه ورود و اتصالات</translation>
    
ERR
The translation omits the shortcut key (&amp;) and does not accurately convey the original English phrase "Allow incoming connections." The phrase "اجازه ورود و اتصالات" translates roughly to "Allow entry and connections," which is not precise. Also, there is no indication of the shortcut (&amp;), which should appear exactly once.

Correct translation:
اجازه اتصالات &amp;ورودی را بده
```

<!-- cache_translation_check_fa_5a5783dadf1501e4e0671c334642500a59583d3f5e6a43fd13d1d5da81f5ef9b -->
```
        <source>&amp;Port:</source>
        <translation>پورت:</translation>
    
ERR
The translation omits the ampersand (&) which is used to mark the keyboard shortcut. It must be present exactly once in the translation.

Correct translation:
&پورت:
```

<!-- cache_translation_check_fa_773ecd204903583c0522aab4a358bdb579bf22660c7bede7f46573b49b1a021a -->
```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>بندر پروکسی (به عنوان مثال 9050)
 </translation>
    
ERR
There is a translation issue: "بندر" incorrectly means "port" as in "harbor", not as in "network port". The correct term in computer/network context is "پورت". There is also an unnecessary whitespace/line break at the end.

Correct translation:
پورت پروکسی (برای مثال ۹۰۵۰)
```

<!-- cache_translation_check_fa_79e2adb2953c3cb199de0174ebcd5af6288631ef91b648c1376d9e247d41d14e -->
```
        <source>Used for reaching peers via:</source>
        <translation>برای دسترسی به همسالان از طریق:
 </translation>
    
ERR
There is an unnecessary newline and non-breaking space at the end of the translation, causing formatting issues. The translation itself is correct, but the whitespace must be fixed.

Correct translation:
برای دسترسی به همسالان از طریق:
```

<!-- cache_translation_check_fa_0d17d8b87c9cf4adef9efc58fc4035e74eb3cd736f7833be6cb83c9440701c9f -->
```
        <source>&amp;Window</source>
        <translation>پنجره</translation>
    
ERR
The translation does not include the '&' shortcut marker, which should appear exactly once in the translation to correspond to the original.

Correct translation:
&پنجره
or
پنجره&

Both are acceptable as long as '&' appears exactly once.
```

<!-- cache_translation_check_fa_254e5eacf19e1758a6dcc142dab00c2b6084da14101fda001b13775505930340 -->
```
        <source>&amp;Show tray icon</source>
        <translation>نمایش نمادک سینی</translation>
    
ERR
The translation omits the '&' character, which is used to specify a keyboard shortcut in menus. The translation must contain exactly one '&' to match the original's shortcut.

Correct translation:
&نمایش نمادک سینی
```

<!-- cache_translation_check_fa_e1083b032e44cc55d640a276aa6645a90d0dc5c5cc439a2387b5210a996df192 -->
```
        <source>&amp;Display</source>
        <translation>نمایش</translation>
    
ERR
The translation omits the '&' which is used for indicating a shortcut key in the English source. It must appear exactly once in the translation as well.

Correct translation:
&نمایش
```

<!-- cache_translation_check_fa_5a7ac6904230cff9d8fb051263904645c779903848bdb37f8a6ab353bc5ce720 -->
```
        <source>User Interface &amp;language:</source>
        <translation>زبان واسط کاربری:</translation>
    
ERR
The '&' character, which indicates a shortcut key in the UI, is missing in the Persian translation. It should appear exactly once.

Correct translation:
زبان &amp;واسط کاربری:
```

<!-- cache_translation_check_fa_52ac205342774e42f65bafd04986d429618e7997c2fff94ad1a7196934de7092 -->
```
        <source>&amp;Unit to show amounts in:</source>
        <translation>واحد نمایشگر مقادیر:</translation>
    
ERR
The translation does not include the ampersand (&) which is used to denote a shortcut key in the source. It must appear exactly once in the translation.

Correct translation:
واحد & نمایشگر مقادیر:
```

<!-- cache_translation_check_fa_e31736148405cd80373d50ee38429250ac8019ff12bdde15c94719d9347d67d8 -->
```
        <source>&amp;Third-party transaction URLs</source>
        <translation>آدرس‌های اینترنتی تراکنش شخص ثالث</translation>
    
ERR
The translation omits the ampersand (&) which is used to indicate the shortcut key in the source string. The ampersand should appear exactly once, in an appropriate position for a Persian interface.

Correct translation:
&آدرس‌های اینترنتی تراکنش شخص ثالث

or

آدرس‌های اینترنتی &تراکنش شخص ثالث

(The ampersand can be before any suitable word, following local UI conventions, but must be present exactly once.)
```

<!-- cache_translation_check_fa_cbd631d021d7efaa87ae86c4a7c0c84016d785a04fb1dc8d3cae22133a56c658 -->
```
        <source>Whether to show coin control features or not.</source>
        <translation>آیا ویژگی های کنترل سکه را نشان می دهد یا خیر.
 </translation>
    
ERR  
There is an extra space character at the end of the translation, and the translation is not entirely faithful—it's more of a question ("Does it show... or not?") than a neutral description matching the source ("Whether to show..."). The format specifiers are not present, but none are needed here.

Correct translation:
آیا ویژگی‌های کنترل سکه نمایش داده شود یا نه.

Or, for a closer rendering:
اینکه آیا ویژگی‌های کنترل سکه نمایش داده شوند یا خیر.
```

<!-- cache_translation_check_fa_2f46487948c44bc13f8a37b63924a30fab0e1b51dc45908cc00e5c54abd0e02a -->
```
        <source>&amp;OK</source>
        <translation>تایید</translation>
    
ERR
The translation omits the '&' character, which is used to indicate a keyboard shortcut in the interface. The translation should include it exactly once.

Correct translation:
&amp;تایید
```

<!-- cache_translation_check_fa_274ee838ad626a4e0d4b196a3dccc355ecfc83848f4b1a298bee17ac25295d97 -->
```
        <source>&amp;Cancel</source>
        <translation>لغو</translation>
    
ERR
The ampersand (&) indicating a shortcut key is missing in the translation. It must appear exactly once, as in the source.

Correct translation:
&لغو
```

<!-- cache_translation_check_fa_ee11dbf01da2016a8ca37a72786164293c428c5ac4a2341d9d7269522a6cfde9 -->
```
        <source>Confirm options reset</source>
        <extracomment>Window title text of pop-up window shown when the user has chosen to reset options.</extracomment>
        <translation>باز نشانی گزینه ها را تأیید کنید
  </translation>
    
ERR
There is an unwanted whitespace character at the end of the translation line (a non-breaking space is present). Additionally, using the verb form may be better as "تأیید بازنشانی گزینه‌ها" for conciseness, but the current version is understandable. The whitespace needs to be removed.

Correct translation:
بازنشانی گزینه‌ها را تأیید کنید
```

<!-- cache_translation_check_fa_727e847882befeb6b9c523926824facfddf18c7271194ca203b6788cbd78f956 -->
```
        <source>Client will be shut down. Do you want to proceed?</source>
        <extracomment>Text asking the user to confirm if they would like to proceed with a client shutdown.</extracomment>
        <translation>کلاینت خاموش خواهد شد.آیا میخواهید ادامه دهید؟</translation>
    
ERR
There is a missing space after the period. It should be "خواهد شد. آیا". Also, for better readability, "می‌خواهید" is more correct with a ZWNJ (zero-width non-joiner) between "می" and "خواهید".

Correct translation:
کلاینت خاموش خواهد شد. آیا می‌خواهید ادامه دهید؟
```

<!-- cache_translation_check_fa_041a918d5e54825f40ca2a6bffa5dca2660259ed11eae80b11bd64403767df60 -->
```
        <source>The configuration file is used to specify advanced user options which override GUI settings. Additionally, any command-line options will override this configuration file.</source>
        <extracomment>Explanatory text about the priority order of instructions considered by client. The order from high to low being: command-line, configuration file, GUI settings.</extracomment>
        <translation>از پرونده پیکربندی برای انتخاب گزینه های کاربر پیشرفته استفاده می شود که تنظیمات ونک را نادیده می شود. بعلاوه ، هر گزینه خط فرمان این پرونده پیکربندی را لغو می کند. 

 </translation>
    
ERR
There are several problems in the translation:
1. "تنظیمات ونک" is likely a typographical error for "تنظیمات واسط کاربری" (GUI settings).
2. Whitespace issues: There is an extra space before and after the translation text, as well as an unnecessary line break at the end.
3. Some awkward phrasing: "نقض می‌شود" or "لغو می‌کند" is better than "نادیده می‌شود" in this context for "override".
4. Pluralization: "گزینه‌های کاربری پیشرفته" would read more natural.

Correct translation:
از پروندهٔ پیکربندی برای تعیین گزینه‌های پیشرفتهٔ کاربر استفاده می‌شود که تنظیمات واسط کاربری را نادیده می‌گیرد. همچنین هر گزینهٔ خط فرمان، این پروندهٔ پیکربندی را نادیده می‌گیرد.
```

<!-- cache_translation_check_fa_e2d2baf0929b5f7c37b5f81deb7785ded38971d1aaf01ed61d10b521f7ee051a -->
```
        <source>This change would require a client restart.</source>
        <translation>تغییرات منوط به ریست کاربر است.</translation>
    
ERR
The Persian translation is inaccurate and misleading. The source says "This change would require a client restart," but the translation implies "The changes depend on the user resetting (something)," which is not the intended meaning. Also, "ریست کاربر" translates to "user reset," not "client restart."

Correct translation:
این تغییر نیازمند راه‌اندازی مجدد برنامه است.
```

<!-- cache_translation_check_fa_34c8593632d49be5bf43b948c57c44bcbddea86c1c4657282df9fbb6528e1408 -->
```
        <source>Your current spendable balance</source>
        <translation>موجودی قابل خرج در الان</translation>
    
ERR
The translation is understandable but not natural or idiomatic in Persian and contains a minor grammatical issue. "در الان" is awkward and ungrammatical. A more appropriate translation would be:
موجودی فعلی قابل خرج شما

Correct translation:
موجودی فعلی قابل خرج شما
```

<!-- cache_translation_check_fa_b5c3441b98bbff6658cb7361e2f2bd6a81828879e437aa358dde071199354e8b -->
```
        <source>Transaction has %1 unsigned inputs.</source>
        <translation>%1Transaction has  unsigned inputs.</translation>
    
ERR
The translation is incorrect. It is not in Persian ('fa') and mainly repeats the English text, which is a clear error.

Correct translation:
تراکنش دارای %1 ورودی امضا نشده است.
```

<!-- cache_translation_check_fa_ba6149331fa7f8e9b8ce615abbfda52f8154f3d4a69d063e51255a3773794997 -->
```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>نمی توان بیت کوین را شروع کرد: کنترل کننده کلیک برای پرداخت
 </translation>
    
ERR
There is an unnecessary whitespace and line break at the end of the translation. The translation is otherwise accurate, but should not contain the stray space and line break.

Correct translation:
نمی‌توان بیت‌کوین را شروع کرد: کنترل‌کننده کلیک برای پرداخت
```

<!-- cache_translation_check_fa_56fb697740d5fae59224d34e02ca7a89f17c278f51d2d9d35d9f5c597872800b -->
```
        <source>User Agent</source>
        <extracomment>Title of Peers Table column which contains the peer's User Agent string.</extracomment>
        <translation>نماینده کاربر</translation>
    
ERR
"نماینده کاربر" literally means "user representative" and is an uncommon/awkward rendering for the technical term "User Agent". No format specifiers or spacing issues.

Suggested correction (more natural for Persian technical context):
عامل کاربر
```

<!-- cache_translation_check_fa_82913ccad1c7f3670903a68f62342f0baadc51d526bd292a2b8f7f857c5be36f -->
```
        <source>Received</source>
        <extracomment>Title of Peers Table column which indicates the total amount of network information we have received from the peer.</extracomment>
        <translation>دریافت شد</translation>
    
ERR
The translation "دریافت شد" is a verbal past tense ("was received") which is awkward for a column header. Use a noun/adjective form suitable for a table column.

Correct translation (suggestions):
- دریافت‌شده
or
- دریافت
```

<!-- cache_translation_check_fa_07306160f38f85eb810d6fcaf6989cf367bf3c400ee1cdaab2d060689090b4fd -->
```
        <source>&amp;Network Traffic</source>
        <translation>ترافیک شبکه</translation>
    
ERR
The Persian translation omits the '&' which is used to indicate a keyboard shortcut. It must be present exactly once, as in the source.

Correct translation:
&amp;ترافیک شبکه
```

<!-- cache_translation_check_fa_ece9918470acec4dc72c6d7aaa51f72faa62b5dc11271369c167dbd9167e1c47 -->
```
        <source>Copy &amp;label</source>
        <translation>تکثیر برچسب</translation>
    
ERR
The translation omits the '&' which is used for shortcut keys, and uses "تکثیر" which means "reproduction/duplication" rather than the more typical "کپی" ("copy") in software UI. The proper translation for software context should use "کپی" and include the '&'.

Correct translation:
کپی &برچسب
```

<!-- cache_translation_check_fa_ece9918470acec4dc72c6d7aaa51f72faa62b5dc11271369c167dbd9167e1c47 -->
```
        <source>Copy &amp;label</source>
        <translation>تکثیر برچسب</translation>
    
ERR
The translation omits the '&' which is used for shortcut keys, and uses "تکثیر" which means "reproduction/duplication" rather than the more typical "کپی" ("copy") in software UI. The proper translation for software context should use "کپی" and include the '&'.

Correct translation:
کپی &برچسب
```

<!-- cache_translation_check_fa_e04fdba236bb13fe3ad3d3522004f0dde0cb6e0db1a9b4f1a5bb16a861620a16 -->
```
        <source>The inputs size exceeds the maximum weight. Please try sending a smaller amount or manually consolidating your wallet's UTXOs</source>
        <translation>اندازه ورودی از حداکثر مقدار موجودی بیشتر است.  لطفاً مقدار کمتری ارسال کنید یا به صورت دستی مقدار موجودی خرج نشده کیف پول خود را در ارسال تراکنش اعمال کنید. </translation>
    
ERR
The Persian translation contains inaccuracies regarding technical Bitcoin terminology. "maximum weight" is translated as "maximum balance" (حداکثر مقدار موجودی), which is incorrect. Furthermore, the translation of "manually consolidating your wallet's UTXOs" is overly wordy and does not accurately capture the concept of consolidation (combining multiple UTXOs into fewer ones).

Correct translation:
اندازه ورودی‌ها از حداکثر وزن مجاز فراتر رفته است. لطفاً مبلغ کمتری ارسال کنید یا خروجی‌های خرج‌نشده (UTXO) کیف پول خود را به صورت دستی تجمیع کنید.
```

<!-- cache_translation_check_fa_d6e28eefd6934157ea55018093fe5fabc30cc4d449b0391f318d95cf9bfc9480 -->
```
        <source>The preselected coins total amount does not cover the transaction target. Please allow other inputs to be automatically selected or include more coins manually</source>
        <translation>مقدار کل بیتکوینی که از پیش انتخاب کردید کمتر از مبلغ مورد نظر برای انجام تراکنش است .  لطفاً اجازه دهید ورودی های دیگر به طور خودکار انتخاب شوند یا مقدار بیتکوین های بیشتری را به صورت دستی اضافه کنید</translation>
    
ERR
The translation contains unnecessary spaces before the period ('.') and after it. In Persian typography, punctuation marks should follow the preceding word without a space. Additionally, there is a double space after the period.

Correct translation:
مقدار کل کوین‌های از پیش انتخاب شده برای مبلغ تراکنش کافی نیست. لطفاً اجازه دهید ورودی‌های دیگر به طور خودکار انتخاب شوند یا کوین‌های بیشتری را به صورت دستی اضافه کنید.
```

<!-- cache_translation_check_fa_f6224e493124f5abfc86cf0c520a02f6c24e697c2fa0e274b4026027e8f64b1f -->
```
        <source>default wallet</source>
        <translation>کیف پول پیش فرض
 </translation>
    
ERR
There is an unwanted trailing whitespace character at the end of the translation. Otherwise, the translation is accurate.

Correct translation:
کیف پول پیش‌فرض
```

<!-- cache_translation_check_fa_6b572f6b1964b394878a4717087e9db30eebe0e24c138b93274f2a69ebe23609 -->
```
        <source>whitebind may only be used for incoming connections ("out" was passed)</source>
        <translation>پیوندسفید فقط برای اتصال‌های ورودی قابل استفاده است ("out" برای اتصال خروجی ارسال شده)</translation>
    
ERR
The translation largely conveys the meaning but has a formatting/terminology issue: the compound word "پیوندسفید" is written without a space and looks odd. Also it's clearer to keep the option name in Latin (whitebind) or separate the Persian words. A more natural Persian translation:

Correct translation:
گزینه whitebind فقط برای اتصالات ورودی قابل استفاده است ("out" ارسال شده)
```

<!-- cache_translation_check_fa_7a74fc4646ee5df8da34001da7b590b23bcc4daf99f2bba62be69e5db71c45ca -->
```
        <source>Assumeutxo data not found for the given blockhash '%s'.</source>
        <translation>داده‌های فرضی اوت‌کو برای بلاک‌هش ''%s" داده شده یافت نشد.</translation>
    
ERR
The Persian translation has mismatched quotation marks around %s (''%s") and awkward word order ("داده شده" misplaced). Also "Assumeutxo" should be kept as is or consistently transliterated.

Correct translation:
داده‌های Assumeutxo برای بلاک‌هش '%s' یافت نشد.
```

<!-- cache_translation_check_fa_8a80a3677fef49a035bace23e7ef3def4aaaf4647e7a901d80fe86f7293fb57b -->
```
        <source>Error opening coins database</source>
        <translation>خطا در بازکردن پایگاه داده بلاک coins</translation>
    
ERR
The translation includes the extra word "بلاک" (block), which is not present in the source text. In the context of Bitcoin software, "coins database" refers specifically to the chainstate database (UTXO set), not necessarily the block database.

Correct translation:
خطا در بازکردن پایگاه داده سکه‌ها (coins)
```

<!-- cache_translation_check_fa_310dce85f7e0e931bc268a06b3fd06a186ae09299bf88be6577c2d3921321dd0 -->
```
        <source>Error reading from database, shutting down.</source>
        <translation>خواندن از پایگاه داده با خطا مواجه شد,در حال خاموش شدن.</translation>
    
ERR
The Persian translation is understandable but has punctuation/spacing and style issues. It uses an ASCII comma instead of a Persian comma and lacks a space after it; the sentence is also slightly awkward.

Suggested corrections (both are natural):

1) «خطا هنگام خواندن از پایگاه داده رخ داد. در حال خاموش شدن.»
2) «در خواندن از پایگاه داده خطا رخ داد، در حال خاموش شدن.»

Either is acceptable; note the Persian comma «،» and proper spacing.
```

<!-- cache_translation_check_fa_71587e0fa4ee40ec2517ce06fc9adf72fba4c511ab948a16524969116f35125f -->
```
        <source>Error: database transaction cannot be executed for wallet %s</source>
        <translation>خطا: تراکنش پایگاه داده را نمی توان برای کیف پول اجرا کرد %s</translation>
    
ERR
The word order in the Persian translation does not correctly preserve the format specifier '%s' position, which should appear after "کیف پول" as in the source ("wallet %s"). The current translation places "%s" at the end, which is incorrect and may cause confusion.

Correct translation:
خطا: تراکنش پایگاه داده را نمی‌توان برای کیف پول %s اجرا کرد
```

<!-- cache_translation_check_fa_6469a353ea2ac175db9d58350239a6188761df6c331d24889403d4b906bde35e -->
```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>ویژگی‌‌‌نما های فایل کافی نیستند. دردسترس %d، مورد نیاز %d</translation>
    
ERR
The Persian translation contains unnecessary triple spaces (stray spacing) between "ویژگی‌‌‌نما" and "های". Additionally, "ویژگی‌‌‌نما" is not the standard technical term for "file descriptor" in Persian; "توصیف‌گر فایل" is the commonly accepted term in computing.

Correct translation:
توصیف‌گرهای فایل کافی در دسترس نیستند. %d در دسترس، %d مورد نیاز.
```
</details>

Number of issues: 95.
