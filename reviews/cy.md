# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>cy</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bcy%5D%20request)


<!-- cache_translation_check_cy_e73b235c39ca06478e60e913dcdea36f33470f19a408004272b74b99ae3bd108 -->
```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Rhybudd: Os ydych yn amgryptio'r waled ag yn colli'r cyfrinair, byddwch yn &lt;b&gt; COLLI EICH BITCOINS I GYD &lt;b&gt; !</translation>
    
ERR
There are formatting errors and minor Welsh language inaccuracies:
- The HTML bold tag is not correctly closed at the end: '&lt;b&gt;' should be '&lt;/b&gt;'.
- The spacing inside the bold tags is inconsistent with the source; there are extra spaces.
- The phrase "ag yn" should be "ac yn" for correct Welsh.
- "cyfrinair" is the correct Welsh term for "passphrase," but "cyfrinair" more commonly means "password"; contextually, "cyfrinair" is acceptable, but some prefer "ymadrodd cyfrin" for "passphrase".
- The translation for "ALL OF YOUR BITCOINS" is correct as "EICH BITCOINS I GYD".

Correct translation:
Rhybudd: Os ydych yn amgryptio'r waled ac yn colli'r cyfrinair, byddwch yn &lt;b&gt;COLLI EICH BITCOINS I GYD&lt;/b&gt;!
```

<!-- cache_translation_check_cy_f3df48d5ac26bd2637dea7318d7991fce7e6848333887d4bb7baa3d25043479c -->
```
        <source>Passphrase change failed</source>
        <translation>Method newid geiriau pas wedi methu</translation>
    
ERR
The translation is problematic. The phrase "Method newid geiriau pas wedi methu" mistranslates "Passphrase change failed". "Method newid" ("method of changing") is unnecessary, and "geiriau pas" is an incorrect or awkward way to say "passphrase". The more idiomatic Welsh would be:

Correct translation:
Methodd newid cyfrinair llwyddo

Or more literally:
Methodd newid ymadrodd cyfrin (for "passphrase" if you want to be precise)
```

<!-- cache_translation_check_cy_2c06bb5a1198570a2ae3e48e5caaa87f58ccba9cbb2f8c82109f4d0a6cdaf4a3 -->
```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>Digwyddodd gwall angheuol.%1ni all barhau'n ddiogel mwyach a bydd yn cau.</translation>
    
ERR
There is a missing space after the period between "angheuol." and "%1", causing formatting issues.

Correct translation:
Digwyddodd gwall angheuol. Ni all %1 barhau'n ddiogel mwyach a bydd yn cau.
```

<!-- cache_translation_check_cy_fca697af0b7a5f5c33b45f982b84cfe1fc8139f6c02a1222b4a9a970d597f243 -->
```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>Digwyddodd gwall mewnol.%1bydd yn ceisio parhau'n ddiogel.Mae hwn yn fwydyn annisgwyl y gellir ei adrodd fel y disgrifir isod.</translation>
    
ERR
There are missing spaces after periods, making the sentences run together. The translation should have spaces after each full stop. Here is the corrected translation:

Digwyddodd gwall mewnol. Bydd %1 yn ceisio parhau'n ddiogel. Mae hwn yn fwydyn annisgwyl y gellir ei adrodd fel y disgrifir isod.
```

<!-- cache_translation_check_cy_aebeb8f891ff109e4553755639f36f9ee6213585922e7d475f5c76d5d57df6e3 -->
```
        <source>%1 didn't yet exit safely…</source>
        <translation>%1ni wnaeth fynd allan yn ddiogel eto…</translation>
    
ERR
The translation is understandable but contains a small grammatical error. In Welsh, "ni wnaeth" should have a space before, and "%1 ni wnaeth fynd allan yn ddiogel eto…" is more natural. Also, a thin space is used around the ellipsis, which is acceptable in Welsh, but ensuring no attached characters is important.

Correct translation:
%1 ni wnaeth fynd allan yn ddiogel eto…
```

<!-- cache_translation_check_cy_f27093b39cbdd394b1a35bf7f43fe6356c290d33e4964b6fac360f808ad49465 -->
```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Mae'r procsï yw&lt;b&gt;wedi'i alluog&lt;/b&gt;i:%1</translation>
    
ERR
The Welsh translation is inaccurate and has formatting issues. "procsï" is incorrect (should be "dirprwy" for proxy), and there are spacing issues (lack of space before ": %1"). Additionally, the structure should better match the English original.

Correct translation:
Mae'r dirprwy wedi'i alluogi: &lt;b&gt;%1&lt;/b&gt;
```

<!-- cache_translation_check_cy_682f9861b2a0a3cff78a06fc6a339ac4fca1247fd854651b243be94e9fc6e2f1 -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation>&amp;Crypto Waled…</translation>
    
ERR
The translation uses "Crypto Waled", which is an incorrect Welsh translation and appears to be a mix of English and pseudo-Welsh. The correct translation for "Encrypt Wallet" in Welsh should be "Amgryptio Waled".

Correct translation:
&Amgryptio Waled…
```

<!-- cache_translation_check_cy_5d749ec304ea810a6a576a6872d15b9fa9e5b96a517bc5265278f5cfded8ea54 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>&amp;Bendith Waled…</translation>
    
ERR
The Welsh word "Bendith" means "Blessing," which is not correct for the term "Backup" in the context of software or wallets. The correct Welsh term for "Backup Wallet" is "Copia wrth gefn Waled" or simply "Gwneud copi wrth gefn o’r waled".

Correct translation:
&Gwneud copi wrth gefn o’r waled…
or
&Copi wrth gefn Waled…
```

<!-- cache_translation_check_cy_19696b827c00482c77bb60bbb1cd62ca09a687296625e514a7ae8c22c426869a -->
```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Dangos y%1neges gymorth i gael rhestr gyda'r opsiynau llinell-gorchymyn Bitcoin posibl</translation>
    
ERR
There are formatting issues in the translation:

- There should be a space after "y" and before "%1", and also after "%1" and before "neges" (the translation currently has "y%1neges" combined, which is incorrect).
- The phrase "neges gymorth" should be separated, and "y neges gymorth" is more natural in Welsh ("the help message").
- The rest of the translation is otherwise accurate.

Correct translation:
Dangos y neges gymorth %1 i gael rhestr o'r opsiynau llinell-gorchymyn Bitcoin posibl
```

<!-- cache_translation_check_cy_e6a1f495e1fc6dc530ef6e368e42b80907b450baa936a68b9d5d3f38fef83fc7 -->
```
        <source>Wallet Data</source>
        <extracomment>Name of the wallet data file format.</extracomment>
        <translation>Data Waled</translation>
    
ERR
The translation is incorrect because "Data" in Welsh means "date" rather than "data" as in information. The correct Welsh word for "Data" (information) is "Data" (as a loanword), but the word order should match English: "Wallet Data" should be "Data Waled". The translation provided is already correct, so it's not problematic.

NO
```

<!-- cache_translation_check_cy_bdae56d53f9428b2a0105f0709259cc6a6b8112ffc3856f45763b601b324f7b2 -->
```
        <source>Main Window</source>
        <translation>Ffenestr Brydferth</translation>
    
ERR
The Welsh word "Brydferth" means "beautiful", not "main". The translation "Ffenestr Brydferth" means "Beautiful Window", which is incorrect.

Correct translation:
Ffenestr Brif
```

<!-- cache_translation_check_cy_6d71f4c29a832b4611d45a4808af1813286a49ceb174a421ead53595988d6e2e -->
```
        <source>%1 client</source>
        <translation>%1cwsmer</translation>
    
ERR
The Welsh translation incorrectly joins "%1" and "cwsmer" without a space, resulting in "%1cwsmer" instead of "%1 cwsmer". "Cwsmer" is also closer to "customer" than "client" in the context of software. The standard Welsh term for a software "client" is "cleient".

Correct translation:
%1 cleient
```

<!-- cache_translation_check_cy_102990129df590fbc0b572e1ebfc3ccbdf365218a4cadb0465453f87659f3f8a -->
```
        <source>S&amp;how</source>
        <translation>Dangos</translation>
    
ERR
The shortcut marker '&' is missing in the Welsh translation. There should be exactly one '&' to match the source, which indicates a keyboard shortcut.

Correct translation:
&Dangos
or
D&angos

(Either placement is acceptable, as long as there is a single '&' marking the shortcut.)
```

<!-- cache_translation_check_cy_b1d7e2cbce1dca382ec2a39293329956681176264651bfdd2817d3f31bd69ed3 -->
```
        <source>Copy transaction &amp;ID and output index</source>
        <translation>Copïo &amp;ID trafodiad a chyfryngau allbwn</translation>
    
ERR
The Welsh translation "Copïo &ID trafodiad a chyfryngau allbwn" is problematic because "chyfryngau allbwn" translates to "output media" instead of "output index". The correct terminology should be "mynegai allbwn" for "output index". Also, the placement of "&ID" is accurate if considering menu shortcuts.

Correct translation:
Copïo ID &trafodiad a mynegai allbwn
```

<!-- cache_translation_check_cy_a61e8567b5f20b28593f4cdb56695a848da599b8dba5609b5144d7c20cec8e9c -->
```
        <source>L&amp;ock unspent</source>
        <translation>L&amp;loi newid nad yw wedi'i wario</translation>
    
ERR
The translation "L&loi newid nad yw wedi'i wario" adds "newid" ("change") which is not in the original English ("Lock unspent"). This could confuse users, as it implies "change" is involved, whereas the English text means to lock unspent (UTXOs—unspent transaction outputs, not specifically change).

Correct translation:
L&loi heb eu gwario

This directly translates to "Lock unspent". The shortcut key (&) is preserved.
```

<!-- cache_translation_check_cy_fb764678bfd5950fc4c9444073189a9f8eadab58e836f5abd65f0f1c7eda0e54 -->
```
        <source>&amp;Unlock unspent</source>
        <translation>&amp;Agor newid nad yw wedi'i wario</translation>
    
ERR
The translation "&amp;Agor newid nad yw wedi'i wario" translates back as "&amp;Open change that has not been spent" (or "Unlock change that has not been spent"). The English "unspent" here refers to "unspent outputs" in general, not just "change". The translation narrows the meaning to "change" specifically, which is incorrect.

Correct translation:
&amp;Datgloi heb eu gwario

Explanation: "Datgloi" means "unlock", "heb eu gwario" means "unspent". This translation retains the broader meaning of "unspent", not just "change".
```

<!-- cache_translation_check_cy_1e1ffa1fc2a774d8e1563d8b57187945bb393ae7f67bd1e0ee700782fe6fc732 -->
```
        <source>(%1 locked)</source>
        <translation>(%1caeedig</translation>
    
ERR
The Welsh translation is missing the closing parenthesis and a space after '%1', and "caeedig" (locked) should come after the space. The correct translation should be:

Correct translation:
(%1 caeedig)
```

<!-- cache_translation_check_cy_22950959c100953c8988eed8f42028aaf196e22ba8711fc65876f27ddfedabf5 -->
```
        <source>Can vary +/- %1 satoshi(s) per input.</source>
        <translation>Gall amrywio +/-%1satoshi(s) y tu mewn.</translation>
    
ERR
The translation has several issues:
1. In Welsh, "satoshi(s)" should be translated or left as "satoshi", not with "(s)", and a space is missing before "satoshi".
2. "y tu mewn" is not a suitable equivalent for "per input" in this context. The phrase should be more like "fesul mewnbwn" ("per input").
3. There should be a space between "%1" and "satoshi".

Correct translation:
Gall amrywio +/- %1 satoshi fesul mewnbwn.
```

<!-- cache_translation_check_cy_dc56784a59c75c6e0fb832af4a340d5c88f9a742d6eae426d7ca8855965fa02a -->
```
        <source>change from %1 (%2)</source>
        <translation>newid o%1(%2)</translation>
    
ERR
There is a formatting issue: there should be a space after "o" and before "%1", and also after "%1" and before the parenthesis. The correct translation should be:
newid o %1 (%2)
Also, it would be a bit more natural in Welsh to reverse the order: "newid o %1 (%2)", but the primary issue is spacing.

Correct translation:
newid o %1 (%2)
```

<!-- cache_translation_check_cy_b7f7a2d3d072c220bd4d829ddbb41948a7dc2b258c25a4d2ba6b46cc9d2fb552 -->
```
        <source>The wallet '%1' was migrated successfully.</source>
        <translation>Y waled'%1' ymfudodd yn llwyddiannus.</translation>
    
ERR
There is a formatting issue: in Welsh, a space should be included between "waled" and "'%1'". Also, the translation could be improved for clarity and idiomatic Welsh.

Correct translation:
Llwyddodd ymfudo’r waled '%1'.
```

<!-- cache_translation_check_cy_c5a7c2d644237068359fa8c2ddd4e3f8073b97305bd6d9445b0b400f8cb5267b -->
```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Y cyfeiriad a roddwyd "%1Nid yw " yn gyfeiriad Bitcoin dilys.</translation>
    
ERR
There is a formatting issue in the translation: the position of the quotation marks and %1 is incorrect, resulting in: "%1Nid yw ". The correct format should ensure that %1 is placed within the quotation marks, as in the original English.

Correct translation:
Nid yw'r cyfeiriad a roddwyd "%1" yn gyfeiriad Bitcoin dilys.
```

<!-- cache_translation_check_cy_2aab033c6041b4f84a919f62726e91e2d55676d02c397903349ec809ab0a8a13 -->
```
        <source>Directory already exists. Add %1 if you intend to create a new directory here.</source>
        <translation>Mae'r cyfeiriadur eisoes yn bodoli. Ychwanegu%1os ydych yn bwriadu creu cyfeiriadur newydd yma.</translation>
    
ERR
There are spacing errors in the Welsh translation: there should be spaces after "Ychwanegu" and before "os" and before "%1".

Correct translation:
Mae'r cyfeiriadur eisoes yn bodoli. Ychwanegwch %1 os ydych yn bwriadu creu cyfeiriadur newydd yma.
```

<!-- cache_translation_check_cy_980d131a88a08183766869b3bf80a43c81e735e4bba4a5421b092b2d9bdac6c4 -->
```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>O leiaf%1Bydd GB o ddata yn cael ei storio yn y cyfeiriadur hwn, a bydd yn tyfu dros amser.</translation>
    
ERR
There are whitespace issues in the translation. There should be a space between "O leiaf" and "%1", and between "%1" and "Bydd". Also, the sentence can be made more natural in Welsh.

Correct translation:
O leiaf %1 GB o ddata fydd yn cael ei storio yn y cyfeiriadur hwn, a bydd yn tyfu dros amser.
```

<!-- cache_translation_check_cy_b9a91e0787c052fd02a5c54818621762e2cb835fb4fe0f1bb4a3f424c29aaa75 -->
```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Oddeutu%1Bydd GB o ddata yn cael ei storio yn y cyfeiriadur hwn.</translation>
    
ERR
There are issues with whitespace formatting. In Welsh, 'Oddeutu' should be followed by a space, and there should be a space between '%1' and 'Bydd'. Also, 'Bydd' should not be present; the correct sentence structure would place 'GB' after '%1', and 'Bydd' (meaning 'will be') is not idiomatic here as the passive construction is already implied.

Correct translation:
Oddeutu %1 GB o ddata fydd yn cael ei storio yn y cyfeiriadur hwn.
```

<!-- cache_translation_check_cy_c9dd03a1c2f3c8f3e604580f9531072b715dc2f056411e55fc13231b7e4a99c4 -->
```
        <source>Automatically start %1 after logging in to the system.</source>
        <translation>Cychwyn yn awtomatig%1ar ôl mewngofnodi i'r system.</translation>
    
ERR
There are spacing issues in the translation. The Welsh wording lacks spaces before and after "%1", resulting in "awtomatig%1ar ôl" instead of "awtomatig %1 ar ôl".

Correct translation:
Cychwyn %1 yn awtomatig ar ôl mewngofnodi i'r system.
```

<!-- cache_translation_check_cy_49a50157dea265d4889f66be118cbc99cf683fa69b3078b59d2345efd7306d6d -->
```
        <source>&amp;Start %1 on system login</source>
        <translation>&amp;Cychwyn%1ar mewngofnodi i'r system</translation>
    
ERR
There are missing spaces in the translation: "Cychwyn%1ar" should be "Cychwyn %1 ar". The spacing between "%1" and "ar" is required for correct formatting and readability.

Correct translation:
&Cychwyn %1 ar mewngofnodi i'r system
```

<!-- cache_translation_check_cy_df69ae428a7c991fab5e42d2554dcbf787af94f559ee47a92a52255a18248f70 -->
```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Mae galluogi torri'n sylweddol yn lleihau'r gofod disg sydd ei angen i storio trafodion. Mae pob bloc yn parhau i gael ei ddilysu'n llawn. Bydd adfer y gosodiad hwn yn gofyn am ailosodlawr y blwch cyfan.</translation>
    
ERR
There is an error in the translation: "ailosodlawr y blwch cyfan" is incorrect and does not accurately translate "re-downloading the entire blockchain." It roughly translates to "re-installer of the whole box," which is confusing and not relevant.

Correct translation:
Mae galluogi torri'n sylweddol yn lleihau'r gofod disg sydd ei angen i storio trafodion. Mae pob bloc yn dal i gael eu dilysu'n llawn. Mae adfer y gosodiad hwn yn golygu bod rhaid ail-lwytho'r gadwyn bloc gyfan.
```

<!-- cache_translation_check_cy_4a46b6f650dae455a5571cdb203775b3e4d700bc883455e17ae35379de682d1d -->
```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>Llwybr llawn i%1sgript gymhwysol (e.e. C:\Downloads\hwi.exe neu /Users/you/Downloads/hwi.py). Rhowch sylw: gall malware ddwyn eich ceiniogau!</translation>
    
ERR
There are spacing issues after "i%1sgript", which should be "i %1 sgript" to reflect "to a %1 compatible script". Also, "sgript gymhwysol" is not quite natural; "sgript sy’n gydnaws â %1" is clearer for "a %1 compatible script." The rest is acceptable.

Correct translation:
Llwybr llawn at sgript sy’n gydnaws â %1 (e.e. C:\Downloads\hwi.exe neu /Users/you/Downloads/hwi.py). Rhybudd: gall meddalwedd faleisus ddwyn eich ceiniogau!
```

<!-- cache_translation_check_cy_ea29df7298f9b8e1eab19bab6482be0a5a2928ff6dd14d58a86e207ed0a8402c -->
```
        <source>Open the %1 configuration file from the working directory.</source>
        <translation>Agor y%1ffilet gosodiad o'r directory gweithio.</translation>
    
ERR
The Welsh translation contains several errors:
- There is no space between "y" and "%1ffilet", and the word "ffilet" is a misspelling of "ffilen" (file).
- "gosodiad" is a noun meaning "setting" or "installation", but "ffilen ffurfweddiad" ("configuration file") is correct.
- "directory gweithio" should be "cyfeiriadur gwaith" for "working directory".

Correct translation:
Agor y ffeil ffurfweddiad %1 o'r cyfeiriadur gwaith.
```

<!-- cache_translation_check_cy_7d1d8063963bf55681f45ee801db01a6bd4f9675658f0f5d1a0e9e9a05123fc7 -->
```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Bydd ailosod y gosodiad hwn yn gofyn am ailosodlawr y gadwyn floc gyfan.</translation>
    
ERR
The translation is inaccurate. "Ailosod" means "reset," not "revert." Furthermore, "ailosodlawr" seems erroneous; it should be "ail-lawrlwytho" for "re-download." The correct Welsh translation should be:

Bydd newid y gosodiad hwn yn gofyn am ail-lawrlwytho’r gadwyn floc gyfan.
```

<!-- cache_translation_check_cy_07e67c533e6cdbc21115bff9190b72636b01ed30bd030950b623040332b7169b -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>Caniatáu cysylltiadau sy'n dod i mewn</translation>
    
ERR
The translation omits the ampersand shortcut marker (&), which should appear somewhere in the Welsh translation as it does in the source. It is necessary for keyboard accessibility.

Correct translation:
Caniatáu cysylltiadau sy'n dod i mewn (&)
```

<!-- cache_translation_check_cy_d2d4dc9f6285dec40a2f6cb2c4f9c1c10630cc0dce1430037295522f93f54dcb -->
```
        <source>&amp;Information</source>
        <translation>Gwybodaeth</translation>
    
ERR
The translation omits the ampersand (&), which is used to define a shortcut key in menu labels. The Welsh translation should also have a single ampersand.

Correct translation:
& Gwybodaeth
```

<!-- cache_translation_check_cy_e6a1f495e1fc6dc530ef6e368e42b80907b450baa936a68b9d5d3f38fef83fc7 -->
```
        <source>Wallet Data</source>
        <extracomment>Name of the wallet data file format.</extracomment>
        <translation>Data Waled</translation>
    
ERR
The translation is incorrect because "Data" in Welsh means "date" rather than "data" as in information. The correct Welsh word for "Data" (information) is "Data" (as a loanword), but the word order should match English: "Wallet Data" should be "Data Waled". The translation provided is already correct, so it's not problematic.

NO
```

<!-- cache_translation_check_cy_86a6e3705559cc220a544271daa0b5e78a58ff2c6dc74784f996e3739af503e9 -->
```
        <source>Unable to bind to %s on this computer. %s is probably already running.</source>
        <translation>Methu cysylltu â%sar y cyfrifiadur hwn.%syn debyg eisoes yn rhedeg.</translation>
    
ERR
There are several issues in the Welsh translation:
1. There is no space after â and before %s, and after hwn. and before %s, making the format specifiers merge with the surrounding words.
2. The sentence structure is awkward, and the meaning is not fully preserved.
3. The translation misuses "cysylltu" (connect), while "bind" should be "rhwymo" or "ymglymu".
4. "Mae'n debyg" is the usual way to say "probably".

Correct translation:
Methu rhwymo i %s ar y cyfrifiadur hwn. Mae'n debyg bod %s eisoes yn rhedeg.
```

<!-- cache_translation_check_cy_f0cfde9f8e897f62ecf053dddef859b59ca70cb6c5cc6bdc7bf09000e762a3b2 -->
```
        <source>Unable to open %s for writing</source>
        <translation>Methu agor%sar gyfer ysgrifennu</translation>
    
ERR
There is a missing space between '%s' and 'ar gyfer'. The correct translation should read: "Methu agor %s ar gyfer ysgrifennu" (note the space after %s).

Correct translation:
Methu agor %s ar gyfer ysgrifennu
```

<!-- cache_translation_check_cy_ba4ab422f985790620f96e99b8dd551d98f5b88598ebbed276289bc81150f44e -->
```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>Reolau newydd anhysbys wedi'u gweithredu (versionbit%i)</translation>
    
ERR
There is a formatting issue: there is no space between "versionbit" and "%i" in the translation, making it harder to read. The English source has a space: "versionbit %i".

Correct translation:
Reolau newydd anhysbys wedi'u gweithredu (versionbit %i)
```

<!-- cache_translation_check_cy_578d67cfc67d33ab43c5dd78b85e3e15dded8a7e79d44449a2d95258ade86557 -->
```
        <source>Unrecognised option "%s" provided in -test=&lt;option&gt;.</source>
        <translation>Opcsiwn annasarnhaol "%s "a ddarparwyd yn -test=&lt;option&gt;.</translation>
    
ERR
There is a minor typo and spacing issue in the Welsh translation:
- "annasarnhaol" is not a correct Welsh word; the correct word is "anhysbys" (unknown) or "anghysbys" (unrecognised), depending on context.
- There is an extra space before the closing quote in "%s ".
- "a ddarparwyd" means "that was provided", which matches the source, but the more concise "wedi'i ddarparu" is commonly used. However, "a ddarparwyd" is not incorrect.
- The translation of "option" as "opsiwn" is correct.
- Final translation should flow naturally in Welsh.

Correct translation:
Opsiwn anghyfarwydd "%s" a ddarparwyd yn -test=&lt;option&gt;.

Or, if "unrecognised" specifically:
Opsiwn anhysbys "%s" a ddarparwyd yn -test=&lt;option&gt;.
```

<!-- cache_translation_check_cy_9ced601b88bcb5453a8fa6af6ba1c55f9a50a89d63d360a212612eee494785fd -->
```
        <source>Unsupported global logging level %s=%s. Valid values: %s.</source>
        <translation>Llefel logio global nad yw'n cael ei gefnogi%s=%s.Gwerthoedd dilys:%s.</translation>
    
ERR
There are whitespace formatting errors: missing spaces after 'cefnogi' and after '%s.', also after the colon in 'Gwerthoedd dilys:'. The translation otherwise appears understandable and uses the correct format specifiers.

Correct translation:
Llefel logio byd-eang nad yw’n cael ei gefnogi %s=%s. Gwerthoedd dilys: %s.
```

<!-- cache_translation_check_cy_b37cf0d0e1c147a6755c09e4f255c7d470f5e2dd9a0eda7303055af1554ce361 -->
```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>nid yw acceptstalefeeestimates yn cael ei gefnogi ar%scadwyn.</translation>
    
ERR
There are two issues:
1. In Welsh, "ar%scadwyn" should have a space after "ar": "ar %s gadwyn."
2. For clarity and idiom, it would be better to translate "%s chain" as "gadwyn %s".

Correct translation:
nid yw acceptstalefeeestimates yn cael ei gefnogi ar gadwyn %s.
```

<!-- cache_translation_check_cy_eab97a265276ee7dd843198d020e2764fb7b9c7d994f373832df11a583047cbd -->
```
        <source>Unsupported logging category %s=%s.</source>
        <translation>Categori logio nad yw'n cael ei gefnogi%s=%s.</translation>
    
ERR
There is a missing space before the format specifiers "%s=%s" in the translation, which would make the output look incorrect. Additionally, the definite article is missing; a more natural translation would be:

Correct translation:
Nid yw'r categori logio %s=%s yn cael ei gefnogi.
```

<!-- cache_translation_check_cy_cc6931455745b6fdede9c49625b048843bd1d070e9d37ba4e3ccbe3321222c77 -->
```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Gwall: Ni allwyd ychwanegu tx gwylio'n unig%si waled gwylio'n unig</translation>
    
ERR
There are errors in word order, translation of technical terms, and spacing. Specifically:
- "tx gwylio'n unig%si waled gwylio'n unig" combines the abbreviation "tx" with the Welsh for "watch-only", but with no space before %s and awkward word order.
- "tx" (for "transaction") is not translated or explained, which could be acceptable for technical contexts, but it should be separated clearly from the Welsh phrase.
- The translation should keep a space between "tx" and "%s".
- There is no word for "to" ("i" in Welsh) before "waled gwylio'n unig" ("watch-only wallet").

Correct translation:
Gwall: Methu ychwanegu tx gwylio'n unig %s i'r waled gwylio'n unig
```

<!-- cache_translation_check_cy_a34bbd771743e49573f7e9691e448b3a0bcd7f9ff5c1c7de8c9b8cb0857cbd0b -->
```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>Sylw Agent Defnyddiwr (%s) yn cynnwys cymeriadau anghyson.</translation>
    
ERR
The translation of "unsafe characters" as "cymeriadau anghyson" is inaccurate. "Anghyson" means "inconsistent," which does not convey the security implication of "unsafe." The correct translation should use "anniogel" for "unsafe."

Correct translation:
Sylw’r Asiant Defnyddiwr (%s) yn cynnwys cymeriadau anniogel.
```

<!-- cache_translation_check_cy_9ac5e8614d90d7600ebefeac7c72ca60883a6155c287c41c0216e44512c6ed5d -->
```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Roedd angen ailosod y waled:%si gwblhau</translation>
    
ERR
There is a spacing issue after the colon; there should be a space before '%s'. Also, "ailosod" means "to reinstall/reset", whereas "ailysgrifennu" is the correct term for "to rewrite" in this context (referring to a wallet being re-written, not reset). The phrase "i gwblhau" ("to complete") is okay. Corrected translation:

Roedd angen ailysgrifennu'r waled: ailgychwynnwch %s i gwblhau
```
</details>

Number of issues: 43.
