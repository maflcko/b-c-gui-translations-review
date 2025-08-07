# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ps</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bps%5D%20low%20quality)


```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>د پتې لیست خوندي کولو کې یوه تېروتنه شوې وه. %1. مهرباني وکړئ بیا هڅه وکړئ..</translation>
    
YES
There is a punctuation/formatting error: A period (".") is placed right after %1, and then an additional double period at the end (".."), which is not correct. The sentence flow is broken.

Correct translation:
د پتې لیست د %1 ته خوندي کولو هڅه کې یوه تېروتنه وشوه. مهرباني وکړئ بیا هڅه وکړئ.

Alternatively:
د پتې لیست د %1 ته خوندي کولو پر مهال یوه تېروتنه وشوه. مهرباني وکړئ بیا هڅه وکړئ.
```

```
        <source>Sending addresses - %1</source>
        <translation>د پته استول. %1</translation>
    
YES
The translation is inaccurate. "د پته استول" literally means "address sending" but is not idiomatic or correct in Pashto. It also uses a period instead of a dash, and the word order is awkward.

Correct translation:
لېږدونکې پتې - %1
```

```
        <source>Receiving addresses - %1</source>
        <translation>د ترلاسه کولو پته%1</translation>
    
YES
There is a spacing issue: in the translation, there should be a space between "پته" and "%1". Currently, it reads "پته%1", which merges the word and the format specifier without spacing, making it incorrect.

Correct translation:
د ترلاسه کولو پته %1
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>خبرتیا: که تاسې خپل والټ کوډ کړئ او خپلپاسفریز، ته به یې. &lt;b&gt;خپل ټول بټ کوینونه له لاسه ورکړئ&lt;/b&gt;!</translation>
    
YES
The translation contains a grammatical error and awkward phrasing, specifically in "خپلپاسفریز، ته به یې." which is not clear or correct in Pashto. The sentence should flow smoothly, and the warning should be unambiguous.

Correct translation:
خبرتیا: که تاسې خپل والټ کوډ کړئ او خپل پاسفریز له لاسه ورکړئ، نو &lt;b&gt;تاسې به خپل ټول بټ کوینونه له لاسه ورکړئ&lt;/b&gt;!
```

```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>یاد ولرئ چې ستاسو د والټ رمز جوړول بشپړ ساتنه نه شي کولای.ستاسو بټ کوینونه د مالویر له لارې د غلا څخه خوندي کول
 ستاسو کمپیوټ</translation>
    
YES
The translation is problematic. The Pashto sentence does not fully and clearly convey the entire message of the source. The translation is incomplete ("ستاسو کمپیوټ" ends abruptly), and the sentence structure does not clearly communicate that encrypting the wallet cannot fully protect bitcoins from malware on the computer. Also, there is a missing space after the period.

Correct translation:
یاد ولرئ چې د خپل والټ رمز بندول نشي کولی ستاسو بټکوینونه د هغه مالویر څخه چې ستاسو کمپیوټر ته ننوزي او غلا یې کړي، بشپړ خوندي کړي.
```

```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>مهم: هر هغه پخوانی بیک اپ چې تاسو د خپل والټ کړی وي file باید د نوي جوړ شوي، کوډ شوي والټ فایل سره ځای پر ځای شي د امنیتي دلایلو لپاره، د مخکېني بیک اپونه د بې رمز والټ فایل به بې ګټې شي لکه څومره چې تاسو نوې استفاده پیل کړئ انکریپټ شوی والیټ</translation>
    
YES
The translation contains several issues:
- There is awkward phrasing, missing conjunctions, and lack of clarity in separating sentences.
- The format specifier "file" is copied as "file" instead of using a Pashto translation (e.g., "فایل").
- There are some grammar mistakes and the structure makes the meaning unclear.
- "Encypted" is translated as "کوډ شوی" which is acceptable, but "انکریپټ شوی" is more standard—it should be consistent.
- Double spaces and run-on sentences reduce readability.

Correct translation:
مهم: د خپل والټ هر هغه مخکېنی بیک اپ چې جوړ کړی مو دی باید د نوي جوړ شوي، انکریپټ شوی والټ فایل سره بدل شي. د امنیتي دلایلو له امله، د غیر انکریپټ شوی والټ فایل مخکېني بیک اپونه به بې ګټې شي لکه چې تاسو له نوي، انکریپټ شوی والټ څخه کار اخیستل پیل کړئ.
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>د والټ د رمز پټولو لپاره داخل شوی پاسفریز ناسم دی.دا یو نال کریکټر لري (یعني - صفر بایټ). که چېرې پاسفریز تنظیم شوی وی که ستاسو سره د دې سافټویر 25.0یوه نسخه مخکې له ۲۵.۰ وي، مهرباني وکړئ هڅه وکړئ بیا یوازې د کرکټرونو سره پورته پر — خو دا نه شاملول — لومړی نال کرکټر. که دا بریالی شو، مهرباني وکړئ یو نوی پاسفریز ټاکئ ترڅو په راتلونکي کې د دې ستونزې مخنیوی وشي. </translation>
    
YES
The translation contains some issues with accuracy, clarity, punctuation, and sentence structure. There are also minor formatting issues, such as missing or incorrect spaces after periods and misplaced commas. Additionally, the phrase "پورته پر — خو دا نه شاملول — لومړی نال کرکټر" is an inaccurate rendering of "up to — but not including — the first null character".

Correct translation:
د والټ د رمز خلاصولو لپاره داخل شوی پاسفریز ناسم دی. دا پاسفریز یو نال کرکټر لري (یعنې - صفر بایټ). که چیرې پاسفریز د دې سافټویر د ۲۵.۰ نسخه نه مخکې تنظیم شوی وي، نو یوازې تر لومړي نال کرکټر پورې کرکټرونه ولیکئ، خو هغه پخپله مه شاملوي، بیا هڅه وکړئ. که بریالي شوئ، نو د همدې ستونزې د مخنیوي لپاره یو نوی پاسفریز وټاکئ.
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>د ترتیبونو فایل %1 کیږي چې فاسد یا ناسم وي.</translation>
    
YES
The translation is understandable but could be improved for clarity and naturalness. The use of "کیږي" (might be/can be/is) is awkward in this context, and the sentence structure is not smooth. An improved translation would be:

د ترتیباتو فایل %1 ښایي فاسد یا نامعتبر وي.

This makes the sentence clearer and more natural in Pashto.
```

```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>یو وژونکی تېروتنه رامنځته شوه %1 نور نه شي ادامه کولیکاننور نه شي کولی په خوندي توګه دوام ورکړي او به ودرېږي</translation>
    
YES
The translation is problematic due to several issues:
- There is a lack of punctuation after "رامنځته شوه", making the sentence unclear.
- The phrase is awkwardly constructed: "%1 نور نه شي ادامه کولیکاننور نه شي کولی..." contains a duplicated section ("نور نه شي ادامه کولی" and "نور نه شي کولی").
- The translation misses a natural break to correspond with the clarity of the source sentence, leading to confusion.

Correct translation:
یو وژونکی تېروتنه رامنځته شوه. %1 نور په خوندي ډول دوام نه شي کولی او به وتړي.
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>یو مرګونی تېروتنه رامنځته شوې. ډاډ ترلاسه کړئ چې د تنظیماتو فایل لیکل کیدی شي، یا هڅه وکړئ چې د</translation>
    
YES
The translation is incomplete; it does not translate the full source sentence. Specifically, it ends abruptly after "یا هڅه وکړئ چې د", which doesn't continue to instruct the user to try running with -nosettings. The translation should also properly reflect the technical instruction about the -nosettings option.

Correct translation:
یو مرګونی تېروتنه رامنځته شوې ده. ډاډ ترلاسه کړئ چې د تنظیماتو فایل لیکل کېدلی شي، یا هڅه وکړئ چې له -nosettings سره یې پرمخ یوسئ.
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>د بټ کوین والټ د کوډ کوډ بدل کړئ</translation>
    
YES
The translation is inaccurate. The phrase "د بټ کوین والټ د کوډ کوډ بدل کړئ" translates to "Change the code of the Bitcoin wallet," which is repetitive and uses "کوډ" (code) twice, and does not properly convey "passphrase" or specify that it is about the passphrase for encryption.

Correct translation:
د والټ د کوډ کولو لپاره کارېدونکې پټ ټکی بدل کړئ
```

```
        <source>Receive</source>
        <translation> ترلاسه کول</translation>
    
YES
There is an extra space at the beginning of the translation (" ترلاسه کول"), which is a whitespace format issue.

Correct translation:
ترلاسه کول
```

```
        <source>Receiving addresses</source>
        <translation>او د ترلاسه کولو پته</translation>
    
YES
The translation is not accurate. The phrase "Receiving addresses" is plural, but the translation "او د ترلاسه کولو پته" ("or da talafah koloo patah") translates to "and the receiving address," which is singular and incorrectly includes "او" meaning "and".

Correct translation:
د ترلاسه کولو پته‌گانې

Alternatively:
د ترلاسه کولو پتې

Either form is accurate for the plural "Receiving addresses".
```

```
        <source>Restore Wallet…</source>
        <extracomment>Name of the menu item that restores wallet from a backup file.</extracomment>
        <translation>والټ بیا راولیږئ..</translation>
    
YES
The translation "والټ بیا راولیږئ.." is problematic. The verb "بیا راولیږئ" literally means "send again" or "resend," which does not accurately communicate "restore" in the context of restoring a wallet from backup. Also, the use of ".." instead of the correct ellipsis "…" can be improved.

Correct translation:
"والټ بیرته راګرځول…"
OR
"والټ له بیک اپ څخه بیا راګرځول…"
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>%1 مرسته پیغام وښایه ترڅو د ممکنه بټ کوین کمانډ لاین اختیارونو سره لیست ترلاسه کړئ"</translation>
    
YES
There is an erroneous closing quotation mark at the end of the translation that does not exist in the source text. Also, the translation could be improved for naturalness and completeness. The meaning is mostly accurate but can be refined for clarity.

Correct translation:
%1 د مرستې پیغام وښایه ترڅو د بټکوین د ممکنه کمانډ لاین اختیارونو لیست ترلاسه کړئ

Note: Removed unnecessary quotation mark and slightly adjusted the wording for fluency.
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation> والیټ دی&lt;b&gt;انکرپټ شوی&lt;/b&gt; او اوسنۍ &lt;b&gt;خلاص&lt;/b&gt;</translation>
    
YES
There is a whitespace error: an unnecessary space at the start of the translation before "والیټ". Also, "اوسنۍ" translates to "current" (feminine), but it's not required; better to use "اوس" for "currently." The phrase "او اوسنۍ خلاص" is unnatural—should be "او اوس&lt;b&gt;خلاص&lt;/b&gt;دی" (and is now unlocked). Also, for clarity and fluency, it's better to be explicit that the wallet is encrypted and currently unlocked.

Correct translation:
والیټ &lt;b&gt;انکریپټ شوی&lt;/b&gt; دی او &lt;b&gt;اوس&lt;/b&gt; خلاص دی
```

```
        <source>Confirmed</source>
        <translation>تایید شو"</translation>
    
YES
The translation "تایید شو"" is problematic for several reasons:
1. The translation is in Persian (Farsi), not Pashto ('ps'), as indicated by the use of "تایید", which is not a Pashto word for "confirmed".
2. The trailing quotation mark (") appears to be an error.
3. The correct translation for "Confirmed" in Pashto should be "تایید شوی" or "تصديق شوی".

Correct translation:
تصدیق شوی
```

```
        <source>Copy transaction ID and output index</source>
        <translation>د معامله او ID کاپي کړئ او د آؤټ پټ انډیکس</translation>
    
YES
The translation is awkward and grammatically incorrect in Pashto. "معامله" means "transaction", and "ID" is used as in English. But the sentence splits "ID" from "معامله", which is unnatural. "د معامله او ID کاپي کړئ او د آؤټ پټ انډیکس" literally says "Copy the transaction and ID and output index", which is confusing.

Correct translation:
د راکړې ورکړې ID او د وتنې شاخص کاپي کړئ

Or more literally:
د راکړې ورکړې پيژند (ID) او د آوټ پټ انډیکس کاپي کړئ
```

```
        <source>change from %1 (%2)</source>
        <translation>له ... نه بدلون %1 (%2)</translation>
    
YES
The translation is problematic. The Pashto translation "له ... نه بدلون %1 (%2)" is awkward, includes ellipsis ("...") which is not present in the source, and does not preserve the intended meaning or word order.

Correct translation:
د %1 (%2) څخه بدلون

Explanation: The phrase should convey "change from %1 (%2)" as in "change coming from", so "د ... څخه بدلون" is idiomatic and direct. The order of %1 and %2 is also preserved, and the ellipsis is removed.
```

```
        <source>(change)</source>
        <translation>(بدلون</translation>
    
YES
The translation is missing the closing parenthesis and contains a minor spelling variant. It should also fully retain the parentheses from the source.

Correct translation:
(بدلون)
```

```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>آیا تاسو ډاډه یاست چې غواړئ والټ انتقال کړئ؟ &lt;i&gt;%1&lt;/i&gt;?</translation>
    
YES
The translation is mostly accurate but the position of the placeholder %1 is moved, and the sentence structure could be improved for better flow. The placeholder should remain in the same relative location as in the source, and the sentence should read more naturally in Pashto.

Correct translation:
آیا تاسو ډاډه یاست چې غواړئ والټ &lt;i&gt;%1&lt;/i&gt; انتقال کړئ؟
```

```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>د والیټ کډوالۍ به دا والیټ یو یا زیات ډیسکرپټر والیټونو ته بدل کړي. یوه نوې والیټ بیک اپ باید جوړ شي."
که چیرې دې بټوالټ کې کوم یوازې کتل کیدونکي سکریپټونه شامل وي، نو یو نوی بټوالټ به جوړ شي چې دغه یوازې کتل کیدونکي سکریپټونه پکې شامل وي
که دې والټ کې کوم حل کیدونکي خو نه کتل شوي سکریپټونه شامل وي، نو یو بل او نوی والټ به جوړ شي چې هغه سکریپټونه پکې شامل وي."
که دې والټ کې کوم حل کیدونکي خو نه کتل شوي سکریپټونه شامل وي، نو یو بل او نوی والټ به جوړ شي چې هغه سکریپټونه پکې شامل وي."
 &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak او دا د دې والټ لپاره په ډایرکټري کې موندل کیدی شي که چیرې مهاجرت ناسم ترسره شي، بیک اپ کولی شي د 'والټ بیا رغولو' فعالیت سره بېرته بحال شي."</translation>
    
YES  
There are several issues with the translation:

1. **Repetitions**: The line "که دې والټ کې کوم حل کیدونکي خو نه کتل شوي سکریپټونه شامل وي، نو یو بل او نوی والټ به جوړ شي چې هغه سکریپټونه پکې شامل وي." is repeated twice without reason.
2. **Inconsistent/nonsensical terms**: The translation oscillates between "والیټ" and "بټوالټ" for "wallet". It introduces "بټوالټ" (mixing "Bitcoin" and "wallet"), which is non-standard and incorrect for a generic "wallet". "والیټ" should be used consistently.  
3. **Missing and inaccurate information**:  
   - The English states, "The migration process will create a backup of the wallet before migrating." There is no explicit mention of "before migrating" in the translation.
   - The formatting of the last sentence and the whole structure is jumbled/fragmented, with one very long incoherent paragraph.
4. **Mistranslation of technical terms**: The term "descriptor wallets" is left as "ډیسکرپټر والیټونو", which is borderline but could be acceptable; however, more explanation or local adaptation is better if established.
5. **Punctuation and formatting**: The translation uses a mixture of periods and quotation marks in the wrong places. Sentences are not clearly delimited.

**Correct translation** (suggested, with proper formatting):

د والټ مهاجرت به دا والټ یو یا څو ډیسکرپټر والټونو ته واړوي. یو نوی د والټ بیک اپ به جوړول پکار وي.  
که چېرې په دې والټ کې داسې سکریپټونه وي چې یوازې کتل کېدای شي، نو یو نوی والټ به جوړ شي چې دغه د څارلو لپاره سکریپټونه پکې وي.  
که چېرې په والټ کې د حل کېدلو وړ خو نه د څارلو شوي سکریپټونه وي، نو یو بل نوی والټ به جوړ شي چې هغه سکریپټونه پکې وي.  

د مهاجرت له پیل مخکې به د والټ بیک اپ جوړ شي. دا بیک اپ به د &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak نوم ولري او د دې والټ په ډایرکټري کې به پیدا شي. که مهاجرت په غلطۍ ترسره شي، بیک اپ د "والټ بیا رغولو" له لارې بېرته راګرځول کېدای شي.
```

```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>د والټ لیږدول" &lt;b&gt;%1&lt;/b&gt;…</translation>
    
YES
There is a misplaced quotation mark (") in the translation, and the verb form can be improved for clarity and native correctness. The translation should accurately carry over the format specifiers and structure.

Correct translation:
د والټ لېږدول &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>فقط کتل کیدونکي سکریپټونه د '%1' په نوم نوي والټ ته انتقال شوي دي."</translation>
    
YES
There are a few issues:
- The translation adds an unnecessary quotation mark at the end.
- "فقط" is a Persian/Urdu borrowing; in standard Pashto, "يوازې" or "واچ اونلي" (as a term) would be better.
- "کتل کیدونکي" is acceptable but a clearer phrase may use "واچ اونلي".
- Whitespace is generally fine, but the extra quote is stray.

Correct translation:
"واچ اونلي سکریپټونه نوي والټ ته چې '%1' نومیږي انتقال شوي دي."
OR
"يوازې د کتو لپاره سکریپټونه نوي والټ ته چې '%1' نومیږي انتقال شوي دي."
```

```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>حل کیدونکي خو نه لیدل شوي سکریپټونه یوې نوې بکسې ته انتقال شوي چې نوم یې '%1' دی."</translation>
    
YES
There are a few issues:
1. The translation uses Arabic script for "solvable" ("حل کیدونکي") which is correct, but the phrase "بکسې" for "wallet" is less standard; "پېسې بکس" or simply "والټ" is more common for "wallet" in Bitcoin context.
2. There is an unnecessary double quote at the end of the translation.
3. The translation is otherwise correct, but an improved phrasing is recommended to better capture the original meaning and appropriate terminology.

Correct translation:
حل کېدونکي خو نه کتل شوي سکریپټونه یوې نوې والټ ته انتقال شوي چې نوم یې '%1' دی.
```

```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>"والټ بیا راګرځول ..&lt;b&gt;%1&lt;/b&gt;…</translation>
    
YES
There are formatting issues in the translation:
- The placement of the quotation mark at the start is unnecessary.
- The order of the HTML tag <b> and %1 is incorrect, as the %1 should be inside the bold tag, following the English structure.
- There is a space before the '..' and the translation for "Restoring Wallet" is not quite idiomatic; "والټ بیا راګرځول" literally means "wallet return again", but "بیا راګرځول" is less clear for "restoring". A more natural translation would be "والټ بیرته رااچول" or "د والټ بیرته راګرځول".

Correct translation:
د والټ بیرته راګرځول &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>د دې والټ لپاره شخصي کیلي غیر فعال کړئ. هغه والټونه چې شخصي کیلي غیر فعال شوي وي، هیڅ شخصي کیلي نه لري او نه کولی شي HD سیډ یا وارد شوي شخصي کیلي ولري.دا یوازې د کتو لپاره والټونو لپاره مناسب دی"</translation>
    
YES
There is a spacing issue: "ولري.دا" should be "ولري. دا" (space missing after the period). Additionally, there is an unnecessary double quotation at the end.

Correct translation:
د دې والټ لپاره شخصي کیلي غیر فعال کړئ. هغه والټونه چې شخصي کیلي غیر فعال شوي وي، هیڅ شخصي کیلي نه لري او نه کولی شي HD سیډ یا وارد شوي شخصي کیلي ولري. دا یوازې د کتو لپاره والټونو لپاره مناسب دی.
```

```
        <source>Address</source>
        <translation>او پته</translation>
    
YES
The Pashto translation "او پته" translates to "and address," where "او" means "and". The correct translation for "Address" alone is "پته" without the conjunction "او".

Correct translation:
پته
```

```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>د داخل شوي پته "%1"دا د بټ کوین صحيح پته نه ده</translation>
    
YES
There is a minor punctuation and spacing issue: no space appears before the quoted address, making the output cramped. Also, a more natural translation would add a period at the end, and possibly clarify the phrase a bit for naturalness.

Correct translation:
دا داخله شوې پته "%1" د بټکوین سم پته نه ده.
```

```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>د داخل شوي پته "%1" لازمه د پته کتاب کې د لیبل سره شتون لري."%2".</translation>
    
YES
The Pashto translation is awkward, slightly ungrammatical, and the placement of the label ("%2") is incorrect. The sentence does not flow well and almost repeats "address" unnecessarily. Here's an improved and accurate translation:

Correct translation:
دا داخله شوې پته "%1" لا له وړاندې د "%2" لیبل سره په د پتو کتاب کې موجوده ده.
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>په دې ډایرکټرۍ کې لږ تر لږه د معلوماتو GB %1 ذخیره شي، او دا به د وخت په تیریدو سره وده وکړي."</translation>
    
YES
The translation has a minor issue—there is an unnecessary closing quotation mark at the end, which is not present in the source text. Also, the order of "%1" is changed to after "GB", which deviates from the English phrasing but is acceptable in Pashto syntax. Otherwise, the meaning is accurate.

Correct translation:
په دې ډایرکټرۍ کې لږ تر لږه %1 GB معلومات ذخیره کېږي، او دا به د وخت په تېرېدو سره وده وکړي.
```

```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>"تقریباً %1 جی بی معلومات به په دې ډایرکټرۍ کې ذخیره شي.</translation>
    
YES
There are two issues: 
1. The translation includes an unnecessary opening quotation mark at the beginning, which is not present in the source.
2. The closing quotation mark is missing at the end.
3. The rest of the translation is accurate and the format specifier %1 is correctly preserved.

Correct translation:
تقریباً %1 جی بی معلومات به په دې ډایرکټرۍ کې ذخیره شي.
```

```
        <source>%1 will download and store a copy of the Bitcoin block chain.</source>
        <translation>به د بیتکوین بلاک چین کاپي ډاونلوډ کړي او ذخیره کړي.%1</translation>
    
YES
The translation does not accurately convey the intended meaning and has formatting issues:
- The placement of "%1" is incorrect; it should appear at the start of the sentence, like the original.
- The verbs "ډاونلوډ کړي او ذخیره کړي" are in imperative form, which does not match the declarative style of the source.
- The sentence structure is cumbersome and unidiomatic for Pashto.

Correct translation:
%1 به د بیتکوین بلاک چین یوه کاپي ډاونلوډ او ذخیره کړي.
```

```
        <source>Welcome to %1.</source>
        <translation>%1ښه راغلاست</translation>
    
YES
There is a missing space between the placeholder %1 and the Pashto phrase "ښه راغلاست", causing an unnatural joining of the app name/variable and the greeting. The correct translation should have a space after %1.

Correct translation:
%1 ته ښه راغلاست
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>کله چې تاسو OK کلیک کړئ, %1 
"به د بشپړ ډاونلوډ او پروسس پیل کړي.%4بلاک چین%2 GB) د لومړیو معاملو سره پیل کول %3 کله %4 په لومړي سر کې پیل شو</translation>
    
YES
There are several problems:
- The translation contains broken sentences and incorrect placement of format specifiers.
- Some format specifiers (%4, %2, etc.) are concatenated incorrectly.
- There is an erroneous line break after '%1', and the wording is awkward.
- Some punctuation and word order do not make sense.

Correct translation:
کله چې تاسو OK کلیک کړئ، %1 به د بشپړې %4 بلاک زنځیر (%2 GB) راښکته او پروسس کول پیل کړي، چې د %3 د لومړیو معاملو څخه به پیل شي کله چې %4 په لومړي ځل پیل شو.
```

```
        <source>Main</source>
        <translation>"اصلي</translation>
    
YES
The translation has unnecessary quotation marks at the start and is missing the closing quotation mark. Also, the correct word for "Main" in Pashto (ps) is "اصلي" without quotes.

Correct translation:
اصلي
```

```
        <source>Prune block storage to</source>
        <translation>پرون او د ذخیره بلاک کول تر</translation>
    
YES
The translation is awkward and does not accurately convey the English source. "پرون او د ذخیره بلاک کول تر" is a direct word-for-word translation and does not make semantic sense in Pashto. The word "Prune" in the context of Bitcoin means to limit or reduce storage usage by deleting old blocks, not just "پرون" which is the past tense of "do/prune".

Correct translation:
د بلاک ذخیره محدود کړئ تر

Or, more clearly:
د بلاک ذخیره تر دې اندازې راکم کړئ
```

```
        <source>Confirmed</source>
        <translation>تایید شو"</translation>
    
YES
The translation "تایید شو"" is problematic for several reasons:
1. The translation is in Persian (Farsi), not Pashto ('ps'), as indicated by the use of "تایید", which is not a Pashto word for "confirmed".
2. The trailing quotation mark (") appears to be an error.
3. The correct translation for "Confirmed" in Pashto should be "تایید شوی" or "تصديق شوی".

Correct translation:
تصدیق شوی
```
</details>

Number of issues: 38.
