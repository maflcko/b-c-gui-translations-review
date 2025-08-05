# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ps</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bps%5D%20low%20quality)


```
        <source>Copy Address</source>
        <translation>او د پته کاپي</translation>
    
YES  
The translation "او د پته کاپي" literally means "and the address copy," which is incorrect and does not convey the imperative "Copy Address." The correct translation should be a simple imperative phrase meaning "Copy Address," such as:

"پته کاپي کړه"
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>د پتې لیست خوندي کولو کې یوه تېروتنه شوې وه. %1. مهرباني وکړئ بیا هڅه وکړئ..</translation>
    
YES  
The translation has punctuation and spacing issues: there is an extra period after "%1" and also two periods at the end. The phrase "مهرباني وکړئ بیا هڅه وکړئ.." should have only one period. The sentence should flow naturally without an isolated "%1." before the request.

Correct translation:  
د پتې لیست %1 ته د خوندي کولو پر مهال تېروتنه وشوه. مهرباني وکړئ بیا هڅه وکړئ.
```

```
        <source>Sending addresses - %1</source>
        <translation>د پته استول. %1</translation>
    
YES  
The translation uses a period (.) instead of a dash (-) as in the source, which breaks formatting consistency. Also, the phrase "د پته استول" (sending of address) lacks the plural form for "addresses," and the structure is awkward.

Correct translation:  
د پتې استول - %1
```

```
        <source>Receiving addresses - %1</source>
        <translation>د ترلاسه کولو پته%1</translation>
    
YES  
The translation misses a space before the placeholder %1, which affects readability and formatting. Also, the phrase should clearly indicate "Receiving addresses" as plural.

Correct translation:  
د ترلاسه کولو پتې - %1
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>خبرتیا: که تاسې خپل والټ کوډ کړئ او خپلپاسفریز، ته به یې. &lt;b&gt;خپل ټول بټ کوینونه له لاسه ورکړئ&lt;/b&gt;!</translation>
    
YES  
The translation has grammar and clarity issues, including an incorrect and incomplete phrase "او خپلپاسفریز، ته به یې." which disrupts the meaning. Also, the emphasis phrase "LOSE ALL OF YOUR BITCOINS" is translated as "خپل ټول بټ کوینونه له لاسه ورکړئ" which reads as a command "lose your bitcoins" rather than a warning about the consequence.

A better translation would be:  
خبرتیا: که خپل والټ کوډ کړئ او خپل پاسفریز له لاسه ورکوئ، نو تاسې به &lt;b&gt;خپل ټول بټ کوینونه له لاسه ورکړئ&lt;/b&gt;!
```

```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>یاد ولرئ چې ستاسو د والټ رمز جوړول بشپړ ساتنه نه شي کولای.ستاسو بټ کوینونه د مالویر له لارې د غلا څخه خوندي کول
 ستاسو کمپیوټ</translation>
    
YES
The translation is fragmented and contains formatting issues, including inappropriate line breaks and incomplete sentence structure. Also, the phrase "ستاسو کمپیوټ" is cut off and incomplete (likely meant to be "ستاسو کمپیوټر" meaning "your computer"). The translation does not accurately convey the full source sentence.

Correct translation:
یاد ولرئ چې ستاسو د والټ کوډ کول نه شي کولی ستاسو بیتکوینونه په بشپړه توګه د هغه مالویر څخه چې ستاسو په کمپیوټر کې نفوذ کوي د غلا کېدو څخه وساتي.
```

```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>مهم: هر هغه پخوانی بیک اپ چې تاسو د خپل والټ کړی وي file باید د نوي جوړ شوي، کوډ شوي والټ فایل سره ځای پر ځای شي د امنیتي دلایلو لپاره، د مخکېني بیک اپونه د بې رمز والټ فایل به بې ګټې شي لکه څومره چې تاسو نوې استفاده پیل کړئ انکریپټ شوی والیټ</translation>
    
YES  
The translation is somewhat unclear and contains grammatical errors and awkward phrasing. It also lacks proper punctuation, causing it to read as one long run-on sentence. Additionally, the English word "file" appears unnecessarily untranslated and in the middle of the sentence, disrupting flow. The two sentences in the source are merged improperly into one, making it confusing.

Correct translation:  
مهم: هر هغه پخوانی بیک اپ چې تاسو د خپل والټ فایل څخه جوړ کړی وي، باید د نوي جوړ شوي، کوډ شوي والټ فایل سره ځای په ځای شي. د امنیتي دلایلو له امله، د بې کوډ شوي والټ فایل پخواني بیک اپونه به بې ګټې شي تر څو چې تاسو د نوي، کوډ شوي والټ کارول پیل کړئ.
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>د والټ د رمز پټولو لپاره داخل شوی پاسفریز ناسم دی.دا یو نال کریکټر لري (یعني - صفر بایټ). که چېرې پاسفریز تنظیم شوی وی که ستاسو سره د دې سافټویر 25.0یوه نسخه مخکې له ۲۵.۰ وي، مهرباني وکړئ هڅه وکړئ بیا یوازې د کرکټرونو سره پورته پر — خو دا نه شاملول — لومړی نال کرکټر. که دا بریالی شو، مهرباني وکړئ یو نوی پاسفریز ټاکئ ترڅو په راتلونکي کې د دې ستونزې مخنیوی وشي. </translation>
    
YES
The translation has several spacing and punctuation issues such as missing space after periods and commas, and the structure is somewhat unclear and slightly awkward in places. The dash hyphen usage is not consistent with Pashto punctuation, and some phrases can be clearer.

Corrected translation:
د والټ د رمز پټولو لپاره داخل شوی پاسفریز ناسم دی. دا یو نال کریکټر لري (یعنې - صفر بایټ). که پاسفریز د دې سافټویر د ۲۵.۰ نسخې څخه مخکې تنظیم شوی وي، مهرباني وکړئ یوازې تر لومړي نال کریکټر پورې (خو لومړی نال کریکټر ونه نیسئ) هڅه وکړئ. که دا بریالی شو، مهرباني وکړئ یو نوی پاسفریز ټاکئ ترڅو په راتلونکي کې د دې ستونزې مخه ونیول شي.
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>د ترتیبونو فایل %1 کیږي چې فاسد یا ناسم وي.</translation>
    
YES  
The translation is awkward and partially incorrect. The phrase "کېږي چې" is not appropriate here, as it implies possibility in a different context. The source means "might be corrupt or invalid," which should be conveyed more directly and naturally.

A better translation would be:  
د تنظیماتو فایل %1 ممکن خراب یا ناسم وي.
```

```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>یو وژونکی تېروتنه رامنځته شوه %1 نور نه شي ادامه کولیکاننور نه شي کولی په خوندي توګه دوام ورکړي او به ودرېږي</translation>
    
YES  
The translation has format specifier issues and spacing problems: "%1" should be separated and properly placed, and extra words seem concatenated (e.g., "کولیکاننور"). The meaning is partly unclear due to these formatting errors.

Correct translation:  
یو وژونکی تېروتنه رامنځته شوه. %1 نور په خوندي توګه دوام نه شي کولی او به ودرېږي.
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>یو مرګونی تېروتنه رامنځته شوې. ډاډ ترلاسه کړئ چې د تنظیماتو فایل لیکل کیدی شي، یا هڅه وکړئ چې د</translation>
    
YES  
The translation is incomplete and ends abruptly after "یا هڅه وکړئ چې د" ("or try to ..."). This leaves the user without clear instructions as in the source text. The full message should include "running with -nosettings" or its equivalent in Pashto.

Correct translation:  
یو مرګونی تېروتنه رامنځته شوه. ډاډ ترلاسه کړئ چې د تنظیماتو فایل لیکل کیدی شي، یا هڅه وکړئ چې د -nosettings سره پروګرام وچلوئ.
```

```
        <source>Modify configuration options for %1</source>
        <translation>د کنفیګوریشن انتخابونه د بدلون لپاره %1</translation>
    
YES  
The translation word order is incorrect and awkward in Pashto. The phrase "د بدلون لپاره %1" literally means "for change %1," which should be placed before or integrated properly with "د کنفیګوریشن انتخابونه". Also, the phrase "د کنفیګوریشن انتخابونه د بدلون لپاره %1" sounds unnatural.  

A better translation would be:  
"%1 لپاره د تنظیماتو انتخابونه بدل کړئ"  
(Literal: "For %1, modify the configuration options")  

This preserves the meaning and correct word order in Pashto.
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>د بټ کوین والټ د کوډ کوډ بدل کړئ</translation>
    
YES  
The translation contains redundancy and an incorrect phrase "د کوډ کوډ" which literally means "code code" (repetition of "code"). It should be "پټ نوم" (passphrase) instead of repeating "code." Also, "بټ کوین" should be "بټکوین" as one word in Pashto, commonly used. The translation should accurately convey "Change the passphrase used for wallet encryption," i.e., changing the secret phrase used to encrypt the wallet.

Correct translation:  
د بټکوین والټ د کوډ پټ نوم بدل کړئ
```

```
        <source>Receive</source>
        <translation> ترلاسه کول</translation>
    
YES  
The translation contains a leading whitespace character before the word "ترلاسه کول". There should be no leading space. Also, the original single word "Receive" is correctly translated as "ترلاسه کول" (meaning "to receive"), so the translation is accurate aside from the extra space.  

Correct translation:  
<translation>ترلاسه کول</translation>
```

```
        <source>Receiving addresses</source>
        <translation>او د ترلاسه کولو پته</translation>
    
YES  
The translation "او د ترلاسه کولو پته" means "and receiving address," which is incorrect and includes an extraneous conjunction "او" ("and"). The English phrase "Receiving addresses" is plural and likely refers to multiple addresses for receiving Bitcoin. The correct translation should be plural and without "and."

Correct translation:  
"د ترلاسه کولو پتې"
```

```
        <source>Restore Wallet…</source>
        <extracomment>Name of the menu item that restores wallet from a backup file.</extracomment>
        <translation>والټ بیا راولیږئ..</translation>
    
YES  
The translation is incorrect and does not convey the intended meaning of "Restore Wallet…". The phrase "والټ بیا راولیږئ" roughly means "Send wallet again," which is not appropriate in this context. Additionally, the ellipsis character should be the correct Unicode ellipsis (…) (U+2026) rather than two periods.  

Correct translation:  
والټ بیا ترلاسه کړئ…
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>%1 مرسته پیغام وښایه ترڅو د ممکنه بټ کوین کمانډ لاین اختیارونو سره لیست ترلاسه کړئ"</translation>
    
YES  
The translation contains an extraneous closing quotation mark (") at the end, which is not present in the source and makes the text look like a typo or formatting error. Also, a more natural phrasing could improve clarity and flow.

Correct translation:  
%1 مرسته پیغام وښیه ترڅو د ممکنه بټ کوین کمانډ لاین اختیارونو لیست ترلاسه کړئ
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation> والیټ دی&lt;b&gt;انکرپټ شوی&lt;/b&gt; او اوسنۍ &lt;b&gt;خلاص&lt;/b&gt;</translation>
    
YES  
The translation is missing a verb phrase indicating the current state "is". The English phrase clearly states "Wallet is encrypted and currently unlocked," but the Pashto translation reads more like "Wallet encrypted and current unlocked" without the linking verb. A more natural, correct translation would explicitly include "دی" (is) after both adjectives to maintain the meaning and clarity.

Correct translation:  
والیټ دی &lt;b&gt;انکرپټ شوی&lt;/b&gt; او اوس &lt;b&gt;خلاص دی&lt;/b&gt;
```

```
        <source>Confirmed</source>
        <translation>تایید شو"</translation>
    
YES  
The translation contains an extraneous quotation mark at the end, which is a formatting error. The quotation mark should be removed.

Correct translation:  
تایید شو
```

```
        <source>Copy transaction ID and output index</source>
        <translation>د معامله او ID کاپي کړئ او د آؤټ پټ انډیکس</translation>
    
YES  
The translation is incomplete and unnatural. The phrase should clearly convey "Copy transaction ID and output index" as a single instruction. The current translation ends abruptly after "output index" without a verb and feels like two separate fragments.

Correct translation:  
د معامله ID او د آوټ پټ انډیکس کاپي کړئ
```

```
        <source>change from %1 (%2)</source>
        <translation>له ... نه بدلون %1 (%2)</translation>
    
YES  
The translation incorrectly places "له ... نه" which means "from ...", but the ellipsis ("...") is inappropriate here and breaks the proper phrasing. The English phrase "change from %1 (%2)" should be translated as "له %1 (%2) بدلون" to reflect the proper word order in Pashto, meaning "change from %1 (%2)".

Correct translation:  
له %1 (%2) بدلون
```

```
        <source>(change)</source>
        <translation>(بدلون</translation>
    
YES  
The translation is missing the closing parenthesis. It should mirror the source's parentheses usage exactly.

Correct translation:  
(بدلون)
```

```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>آیا تاسو ډاډه یاست چې غواړئ والټ انتقال کړئ؟ &lt;i&gt;%1&lt;/i&gt;?</translation>
    
YES  
The placeholder %1 is incorrectly placed outside the formatting tags in the translation. In the source, %1 is inside the &lt;i&gt;&lt;/i&gt; tags, but in the translation, %1 is outside the tags, which may affect the formatting. Also, the question mark appears twice in the translation.

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
The translation contains several issues:  
1. There are unnecessary quotation marks (") inside the translation that do not appear in the source text.  
2. The second-to-last sentence is repeated twice.  
3. The first sentence is not fully translated and ends abruptly before the sentence about "a new wallet backup will need to be made."  
4. The translation omits the explanation that the migration process will create a backup *before* migrating. It only mentions the backup file name and location but not that it is created before migration.  
5. The last part of the translation is awkwardly phrased and fragmented, lacking clarity.

Correct translation suggestion in Pashto (ps):

د والیټ کډوالۍ به دا والیټ یو یا زیات ډیسکرپټر والیټونو ته بدل کړي. یوه نوې والیټ بیک اپ باید جوړ شي.  
که چیرې په دې والیټ کې یوازې د کتو وړ (watchonly) سکریپټونه وي، نو یو نوی والیټ به جوړ شي چې دغه سکریپټونه پکې شامل وي.  
که په دې والیټ کې کوم حل کیدونکي (solvable) خو نه کتل شوي سکریپټونه موجود وي، نو یو بل او نوی والیټ به جوړ شي چې هغه سکریپټونه پکې شامل وي.  

د کډوالۍ پروسه به د کډوالۍ له پیل مخکې د والیټ بیک اپ جوړ کړي. دغه بیک اپ فایل به په نوم &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak په دې والیټ د ډایرکټري کې موندل کېږي. که چیرې کډوالي ناسم ترسره شي، دا بیک اپ د «والټ بیا رغولو» د فعالیت له لارې بېرته رغول کیدی شي.  

This corrected version fixes formatting, removes duplicates and stray punctuation, and faithfully conveys all parts of the source text.
```

```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>د والټ لیږدول" &lt;b&gt;%1&lt;/b&gt;…</translation>
    
YES  
The translation contains an extraneous quotation mark (") after "لیږدول" which is incorrect and disrupts the sentence. Also, the ellipsis (three dots) should be separated from the preceding word by a space in Pashto for readability and consistency, matching the source format.

Correct translation:  
د والټ لیږدول &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>فقط کتل کیدونکي سکریپټونه د '%1' په نوم نوي والټ ته انتقال شوي دي."</translation>
    
YES  
The translation text ends with an unnecessary quotation mark ("). Also, the term "Watchonly" is a technical term and may be better transliterated or clarified. The current translation means "Watch-only scripts have been transferred to a new wallet named '%1'." which is generally accurate, but the stray ending quote mark should be removed.

Correct translation:  
فقط کتل کیدونکي سکریپټونه د '%1' په نوم نوي والټ ته انتقال شوي دي.
```

```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>حل کیدونکي خو نه لیدل شوي سکریپټونه یوې نوې بکسې ته انتقال شوي چې نوم یې '%1' دی."</translation>
    
YES  
The translation has an extraneous quotation mark at the end that does not exist in the source text. Also, "بکسې" (box) is a literal translation for "wallet," but in the Bitcoin context, "wallet" is better translated as "والټ" (wallet) or a recognized term.

Correct translation:  
حل کیدونکي خو نه لیدل شوي سکریپټونه یوې نوې والټ ته انتقال شوي چې نوم یې '%1' دی.
```

```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>"والټ بیا راګرځول ..&lt;b&gt;%1&lt;/b&gt;…</translation>
    
YES
The translation contains an erroneous leading quotation mark (") which should be removed. Also, the order of words is unnatural and missing the %1 placeholder in the correct position relative to "والټ" (wallet). The ellipsis is represented inconsistently with double dots ".." instead of a proper single Unicode ellipsis "…".  

Correct translation:
والټ &lt;b&gt;%1&lt;/b&gt; بیا راګرځول…
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>د دې والټ لپاره شخصي کیلي غیر فعال کړئ. هغه والټونه چې شخصي کیلي غیر فعال شوي وي، هیڅ شخصي کیلي نه لري او نه کولی شي HD سیډ یا وارد شوي شخصي کیلي ولري.دا یوازې د کتو لپاره والټونو لپاره مناسب دی"</translation>
    
YES
There is an extra quotation mark at the end of the translation which is incorrect. Also, a space is missing after the period before "دا یوازې". 

Correct translation:
د دې والټ لپاره شخصي کیلي غیر فعال کړئ. هغه والټونه چې شخصي کیلي غیر فعال شوي وي، هیڅ شخصي کیلي نه لري او نه کولی شي HD سیډ یا وارد شوي شخصي کیلي ولري. دا یوازې د کتو لپاره والټونو لپاره مناسب دی.
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>هغه پته چې د دې پته لیست داخله سره تړلې ده. دا یوازې د لېږلو پتې لپاره تعدیل کیدی شي."</translation>
    
YES  
The translation contains an extraneous quotation mark at the end and slightly awkward phrasing. A more natural translation without the stray quotation mark would be:  
هغه پته چې د دې د پتې لیست د داخلي سره تړلې ده. دا یوازې د لېږلو پتې لپاره بدلېدلی شي.
```

```
        <source>Address</source>
        <translation>او پته</translation>
    
YES
The translation "او پته" literally means "and address" where "او" means "and," which is incorrect here. The correct Pashto translation for "Address" (as in a Bitcoin or network address) is simply "پته".

Correct translation:
پته
```

```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>د داخل شوي پته "%1"دا د بټ کوین صحيح پته نه ده</translation>
    
YES  
The translation has a spacing issue: there is no space between the quotation mark and the following word "دا". It should be "د داخل شوي پته "%1" دا د بټ کوین صحي پته نه ده" with a space after the closing quotation mark. Also, "صحیح" is better spelled "صحي" in Pashto for "valid".

Correct translation:  
د داخل شوي پته "%1" دا د بټ کوین صحي پته نه ده
```

```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>د داخل شوي پته "%1" لازمه د پته کتاب کې د لیبل سره شتون لري."%2".</translation>
    
YES  
The translation contains grammatical errors and awkward phrasing. The phrase "لازمه د پته کتاب کې د لیبل سره شتون لري." is not correct Pashto and the quotation marks are misplaced around "%2". Also, the original meaning "is already in the address book with label" is not properly conveyed.

Correct translation:  
د وارد شوې پته "%1" له مخکې څخه په آدرس کتاب کې د "%2" لیبل سره شتون لري.
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>په دې ډایرکټرۍ کې لږ تر لږه د معلوماتو GB %1 ذخیره شي، او دا به د وخت په تیریدو سره وده وکړي."</translation>
    
YES  
The translation contains a misplaced quotation mark at the end, which should be removed. Also, the phrase "د معلوماتو GB %1" is awkward; "GB %1 د معلوماتو" or "%1 GB د معلوماتو" is more natural. Additionally, the structure can be smoothed to better reflect the original meaning.  

Correct translation:  
په دې ډایرکټرۍ کې لږ تر لږه %1 GB د معلوماتو ذخیره شي، او دا به د وخت په تیریدو سره وده وکړي.
```

```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>"تقریباً %1 جی بی معلومات به په دې ډایرکټرۍ کې ذخیره شي.</translation>
    
YES  
The translation includes an unnecessary opening quotation mark (") at the start, which should be removed. The rest of the translation correctly conveys the meaning, including the format specifier %1. Also, the phrase "جی بی" is a correct transliteration of "GB" in Pashto. There are no extra spaces or format issues.

Correct translation:  
تقریباً %1 جی بی معلومات به په دې ډایرکټرۍ کې ذخیره شي.
```

```
        <source>%1 will download and store a copy of the Bitcoin block chain.</source>
        <translation>به د بیتکوین بلاک چین کاپي ډاونلوډ کړي او ذخیره کړي.%1</translation>
    
YES  
The translation has a formatting issue: the placeholder %1 should appear in the same logical position as the source sentence, typically at the start before the verb phrase. Currently, %1 is placed at the end with no space before it, causing readability and formatting issues. Also, a space is needed after the period, but ideally the period should come at the end of the sentence, not before %1. The sentence structure can be improved for clarity.

Correct translation:  
%1 به د بیتکوین بلاک چین کاپي ډاونلوډ او ذخیره کړي.
```

```
        <source>Welcome to %1.</source>
        <translation>%1ښه راغلاست</translation>
    
YES  
There is no space between "%1" and "ښه راغلاست" in the translation, which makes the sentence appear incorrectly merged. A space is needed after "%1" for proper formatting and readability.

Correct translation:  
%1 ښه راغلاست
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>کله چې تاسو OK کلیک کړئ, %1 
"به د بشپړ ډاونلوډ او پروسس پیل کړي.%4بلاک چین%2 GB) د لومړیو معاملو سره پیل کول %3 کله %4 په لومړي سر کې پیل شو</translation>
    
YES  
The translation is grammatically incorrect and improperly formatted. It contains misplaced punctuation, incorrect word order, missing spaces, and overall lacks clarity. The segment after "%1" is broken and includes stray quotation marks. The parentheses are misplaced and the meaning is not clearly conveyed.

Correct translation:  
کله چې تاسو OK کلیک کړئ، %1 به د بشپړ %4 بلاک چین (%2 GB) له پیل څخه د %3 په لومړیو معاملو کې ډاونلوډ او پروسس پیل کړي کله چې %4 لومړی پیل شو.
```

```
        <source>Main</source>
        <translation>"اصلي</translation>
    
YES  
The translation includes an extraneous opening quotation mark before the Pashto word "اصلي" (which means "Main"). This quotation mark should be removed to avoid formatting issues.

Correct translation:  
اصلي
```

```
        <source>Prune block storage to</source>
        <translation>پرون او د ذخیره بلاک کول تر</translation>
    
YES  
The translation is awkward and not accurate. "Prune" in this context refers to reducing or trimming the block storage size, and "storage" should be connected properly. The phrase "پرون او د ذخیره بلاک کول تر" is not a correct or natural way to say it in Pashto; it translates roughly as "prune and block storage till", which is incomplete and grammatically incorrect.

A better translation would be:  
"د بلاک ذخیره کمول تر"  
which literally means "Reduce block storage to" or "Prune block storage to".
```

```
        <source>Confirmed</source>
        <translation>تایید شو"</translation>
    
YES  
The translation contains an extraneous quotation mark at the end, which is a formatting error. The quotation mark should be removed.

Correct translation:  
تایید شو
```
</details>
