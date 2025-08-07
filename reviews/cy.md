# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>cy</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bcy%5D%20low%20quality)


```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Rhybudd: Os ydych yn amgryptio'r waled ag yn colli'r cyfrinair, byddwch yn &lt;b&gt; COLLI EICH BITCOINS I GYD &lt;b&gt; !</translation>
    
YES
There are formatting errors and minor Welsh language inaccuracies:
- The HTML bold tag is not correctly closed at the end: '&lt;b&gt;' should be '&lt;/b&gt;'.
- The spacing inside the bold tags is inconsistent with the source; there are extra spaces.
- The phrase "ag yn" should be "ac yn" for correct Welsh.
- "cyfrinair" is the correct Welsh term for "passphrase," but "cyfrinair" more commonly means "password"; contextually, "cyfrinair" is acceptable, but some prefer "ymadrodd cyfrin" for "passphrase".
- The translation for "ALL OF YOUR BITCOINS" is correct as "EICH BITCOINS I GYD".

Correct translation:
Rhybudd: Os ydych yn amgryptio'r waled ac yn colli'r cyfrinair, byddwch yn &lt;b&gt;COLLI EICH BITCOINS I GYD&lt;/b&gt;!
```

```
        <source>Passphrase change failed</source>
        <translation>Method newid geiriau pas wedi methu</translation>
    
YES
The translation is problematic. The phrase "Method newid geiriau pas wedi methu" mistranslates "Passphrase change failed". "Method newid" ("method of changing") is unnecessary, and "geiriau pas" is an incorrect or awkward way to say "passphrase". The more idiomatic Welsh would be:

Correct translation:
Methodd newid cyfrinair llwyddo

Or more literally:
Methodd newid ymadrodd cyfrin (for "passphrase" if you want to be precise)
```

```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>Digwyddodd gwall angheuol.%1ni all barhau'n ddiogel mwyach a bydd yn cau.</translation>
    
YES
There is a missing space after the period between "angheuol." and "%1", causing formatting issues.

Correct translation:
Digwyddodd gwall angheuol. Ni all %1 barhau'n ddiogel mwyach a bydd yn cau.
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>Digwyddodd gwall mewnol.%1bydd yn ceisio parhau'n ddiogel.Mae hwn yn fwydyn annisgwyl y gellir ei adrodd fel y disgrifir isod.</translation>
    
YES
There are missing spaces after periods, making the sentences run together. The translation should have spaces after each full stop. Here is the corrected translation:

Digwyddodd gwall mewnol. Bydd %1 yn ceisio parhau'n ddiogel. Mae hwn yn fwydyn annisgwyl y gellir ei adrodd fel y disgrifir isod.
```

```
        <source>%1 didn't yet exit safely…</source>
        <translation>%1ni wnaeth fynd allan yn ddiogel eto…</translation>
    
YES
The translation is understandable but contains a small grammatical error. In Welsh, "ni wnaeth" should have a space before, and "%1 ni wnaeth fynd allan yn ddiogel eto…" is more natural. Also, a thin space is used around the ellipsis, which is acceptable in Welsh, but ensuring no attached characters is important.

Correct translation:
%1 ni wnaeth fynd allan yn ddiogel eto…
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Mae'r procsï yw&lt;b&gt;wedi'i alluog&lt;/b&gt;i:%1</translation>
    
YES
The Welsh translation is inaccurate and has formatting issues. "procsï" is incorrect (should be "dirprwy" for proxy), and there are spacing issues (lack of space before ": %1"). Additionally, the structure should better match the English original.

Correct translation:
Mae'r dirprwy wedi'i alluogi: &lt;b&gt;%1&lt;/b&gt;
```

```
        <source>Encrypt Wallet…</source>
        <translation>Crypto Waled…</translation>
    
YES
The Welsh word for "Encrypt" is "Amgryptio," not "Crypto" (which is merely borrowed from English and is not correct in this context). Additionally, "Waled" is a correct translation for "Wallet." The ellipsis is transferred correctly.

Correct translation:
Amgryptio'r Waled…
```

```
        <source>Backup Wallet…</source>
        <translation>Bendith Waled…</translation>
    
YES
The translation is erroneous. "Bendith" in Welsh means "blessing", not "backup". The correct term for "Backup" in this context is "Copi wrth gefn". "Wallet" as in a digital/Bitcoin wallet is usually left as "Waled". 

Correct translation:
Copi wrth gefn Waled…
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Dangos y%1neges gymorth i gael rhestr gyda'r opsiynau llinell-gorchymyn Bitcoin posibl</translation>
    
YES
There are formatting issues in the translation:

- There should be a space after "y" and before "%1", and also after "%1" and before "neges" (the translation currently has "y%1neges" combined, which is incorrect).
- The phrase "neges gymorth" should be separated, and "y neges gymorth" is more natural in Welsh ("the help message").
- The rest of the translation is otherwise accurate.

Correct translation:
Dangos y neges gymorth %1 i gael rhestr o'r opsiynau llinell-gorchymyn Bitcoin posibl
```

```
        <source>Wallet Data</source>
        <extracomment>Name of the wallet data file format.</extracomment>
        <translation>Data Waled</translation>
    
YES
The translation is incorrect because "Data" in Welsh means "date" rather than "data" as in information. The correct Welsh word for "Data" (information) is "Data" (as a loanword), but the word order should match English: "Wallet Data" should be "Data Waled". The translation provided is already correct, so it's not problematic.

NO
```

```
        <source>Main Window</source>
        <translation>Ffenestr Brydferth</translation>
    
YES
The Welsh word "Brydferth" means "beautiful", not "main". The translation "Ffenestr Brydferth" means "Beautiful Window", which is incorrect.

Correct translation:
Ffenestr Brif
```

```
        <source>%1 client</source>
        <translation>%1cwsmer</translation>
    
YES
The Welsh translation incorrectly joins "%1" and "cwsmer" without a space, resulting in "%1cwsmer" instead of "%1 cwsmer". "Cwsmer" is also closer to "customer" than "client" in the context of software. The standard Welsh term for a software "client" is "cleient".

Correct translation:
%1 cleient
```

```
        <source>Copy transaction ID and output index</source>
        <translation>Copïo ID trafodiad a chyfryngau allbwn</translation>
    
YES
The phrase "cyfryngau allbwn" is incorrect. "Cyfryngau" means "media", not "index". The correct term for "output index" in Welsh (especially in technical context) would be "mynegai allbwn". Also, "Copïo" is fine, and "ID trafodiad" is acceptable.

Correct translation:
Copïo ID trafodiad a mynegai allbwn
```

```
        <source>Lock unspent</source>
        <translation>Lloi newid nad yw wedi'i wario</translation>
    
YES
The translation is incorrect. The English "Lock unspent" refers to marking unspent transaction outputs as locked (so they can't be spent). The translation given, "Lloi newid nad yw wedi'i wario", means "Type of change that has not been spent", which is wrong and introduces content not in the original.

Correct translation:
Clôddio'r heb ei wario
or, more accurately for Bitcoin context:
Cloi'r heb ei wario
```

```
        <source>(%1 locked)</source>
        <translation>(%1caeedig</translation>
    
YES
The Welsh translation is missing the closing parenthesis and a space after '%1', and "caeedig" (locked) should come after the space. The correct translation should be:

Correct translation:
(%1 caeedig)
```

```
        <source>Can vary +/- %1 satoshi(s) per input.</source>
        <translation>Gall amrywio +/-%1satoshi(s) y tu mewn.</translation>
    
YES
The translation has several issues:
1. In Welsh, "satoshi(s)" should be translated or left as "satoshi", not with "(s)", and a space is missing before "satoshi".
2. "y tu mewn" is not a suitable equivalent for "per input" in this context. The phrase should be more like "fesul mewnbwn" ("per input").
3. There should be a space between "%1" and "satoshi".

Correct translation:
Gall amrywio +/- %1 satoshi fesul mewnbwn.
```

```
        <source>change from %1 (%2)</source>
        <translation>newid o%1(%2)</translation>
    
YES
There is a formatting issue: there should be a space after "o" and before "%1", and also after "%1" and before the parenthesis. The correct translation should be:
newid o %1 (%2)
Also, it would be a bit more natural in Welsh to reverse the order: "newid o %1 (%2)", but the primary issue is spacing.

Correct translation:
newid o %1 (%2)
```

```
        <source>The wallet '%1' was migrated successfully.</source>
        <translation>Y waled'%1' ymfudodd yn llwyddiannus.</translation>
    
YES
There is a formatting issue: in Welsh, a space should be included between "waled" and "'%1'". Also, the translation could be improved for clarity and idiomatic Welsh.

Correct translation:
Llwyddodd ymfudo’r waled '%1'.
```

```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Y cyfeiriad a roddwyd "%1Nid yw " yn gyfeiriad Bitcoin dilys.</translation>
    
YES
There is a formatting issue in the translation: the position of the quotation marks and %1 is incorrect, resulting in: "%1Nid yw ". The correct format should ensure that %1 is placed within the quotation marks, as in the original English.

Correct translation:
Nid yw'r cyfeiriad a roddwyd "%1" yn gyfeiriad Bitcoin dilys.
```

```
        <source>Directory already exists. Add %1 if you intend to create a new directory here.</source>
        <translation>Mae'r cyfeiriadur eisoes yn bodoli. Ychwanegu%1os ydych yn bwriadu creu cyfeiriadur newydd yma.</translation>
    
YES
There are spacing errors in the Welsh translation: there should be spaces after "Ychwanegu" and before "os" and before "%1".

Correct translation:
Mae'r cyfeiriadur eisoes yn bodoli. Ychwanegwch %1 os ydych yn bwriadu creu cyfeiriadur newydd yma.
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>O leiaf%1Bydd GB o ddata yn cael ei storio yn y cyfeiriadur hwn, a bydd yn tyfu dros amser.</translation>
    
YES
There are whitespace issues in the translation. There should be a space between "O leiaf" and "%1", and between "%1" and "Bydd". Also, the sentence can be made more natural in Welsh.

Correct translation:
O leiaf %1 GB o ddata fydd yn cael ei storio yn y cyfeiriadur hwn, a bydd yn tyfu dros amser.
```

```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Oddeutu%1Bydd GB o ddata yn cael ei storio yn y cyfeiriadur hwn.</translation>
    
YES
There are issues with whitespace formatting. In Welsh, 'Oddeutu' should be followed by a space, and there should be a space between '%1' and 'Bydd'. Also, 'Bydd' should not be present; the correct sentence structure would place 'GB' after '%1', and 'Bydd' (meaning 'will be') is not idiomatic here as the passive construction is already implied.

Correct translation:
Oddeutu %1 GB o ddata fydd yn cael ei storio yn y cyfeiriadur hwn.
```

```
        <source>Automatically start %1 after logging in to the system.</source>
        <translation>Cychwyn yn awtomatig%1ar ôl mewngofnodi i'r system.</translation>
    
YES
There are spacing issues in the translation. The Welsh wording lacks spaces before and after "%1", resulting in "awtomatig%1ar ôl" instead of "awtomatig %1 ar ôl".

Correct translation:
Cychwyn %1 yn awtomatig ar ôl mewngofnodi i'r system.
```

```
        <source>Start %1 on system login</source>
        <translation>Cychwyn%1ar mewngofnodi i'r system</translation>
    
YES
There are whitespace formatting issues: There should be a space after "Cychwyn" and after "%1" to correctly render "Cychwyn %1 ar mewngofnodi i'r system".

Correct translation:
Cychwyn %1 ar mewngofnodi i'r system
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Mae galluogi torri'n sylweddol yn lleihau'r gofod disg sydd ei angen i storio trafodion. Mae pob bloc yn parhau i gael ei ddilysu'n llawn. Bydd adfer y gosodiad hwn yn gofyn am ailosodlawr y blwch cyfan.</translation>
    
YES
There is an error in the translation: "ailosodlawr y blwch cyfan" is incorrect and does not accurately translate "re-downloading the entire blockchain." It roughly translates to "re-installer of the whole box," which is confusing and not relevant.

Correct translation:
Mae galluogi torri'n sylweddol yn lleihau'r gofod disg sydd ei angen i storio trafodion. Mae pob bloc yn dal i gael eu dilysu'n llawn. Mae adfer y gosodiad hwn yn golygu bod rhaid ail-lwytho'r gadwyn bloc gyfan.
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>Llwybr llawn i%1sgript gymhwysol (e.e. C:\Downloads\hwi.exe neu /Users/you/Downloads/hwi.py). Rhowch sylw: gall malware ddwyn eich ceiniogau!</translation>
    
YES
There are spacing issues after "i%1sgript", which should be "i %1 sgript" to reflect "to a %1 compatible script". Also, "sgript gymhwysol" is not quite natural; "sgript sy’n gydnaws â %1" is clearer for "a %1 compatible script." The rest is acceptable.

Correct translation:
Llwybr llawn at sgript sy’n gydnaws â %1 (e.e. C:\Downloads\hwi.exe neu /Users/you/Downloads/hwi.py). Rhybudd: gall meddalwedd faleisus ddwyn eich ceiniogau!
```

```
        <source>Open the %1 configuration file from the working directory.</source>
        <translation>Agor y%1ffilet gosodiad o'r directory gweithio.</translation>
    
YES
The Welsh translation contains several errors:
- There is no space between "y" and "%1ffilet", and the word "ffilet" is a misspelling of "ffilen" (file).
- "gosodiad" is a noun meaning "setting" or "installation", but "ffilen ffurfweddiad" ("configuration file") is correct.
- "directory gweithio" should be "cyfeiriadur gwaith" for "working directory".

Correct translation:
Agor y ffeil ffurfweddiad %1 o'r cyfeiriadur gwaith.
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Bydd ailosod y gosodiad hwn yn gofyn am ailosodlawr y gadwyn floc gyfan.</translation>
    
YES
The translation is inaccurate. "Ailosod" means "reset," not "revert." Furthermore, "ailosodlawr" seems erroneous; it should be "ail-lawrlwytho" for "re-download." The correct Welsh translation should be:

Bydd newid y gosodiad hwn yn gofyn am ail-lawrlwytho’r gadwyn floc gyfan.
```

```
        <source>Wallet Data</source>
        <extracomment>Name of the wallet data file format.</extracomment>
        <translation>Data Waled</translation>
    
YES
The translation is incorrect because "Data" in Welsh means "date" rather than "data" as in information. The correct Welsh word for "Data" (information) is "Data" (as a loanword), but the word order should match English: "Wallet Data" should be "Data Waled". The translation provided is already correct, so it's not problematic.

NO
```

```
        <source>Unable to bind to %s on this computer. %s is probably already running.</source>
        <translation>Methu cysylltu â%sar y cyfrifiadur hwn.%syn debyg eisoes yn rhedeg.</translation>
    
YES
There are several issues in the Welsh translation:
1. There is no space after â and before %s, and after hwn. and before %s, making the format specifiers merge with the surrounding words.
2. The sentence structure is awkward, and the meaning is not fully preserved.
3. The translation misuses "cysylltu" (connect), while "bind" should be "rhwymo" or "ymglymu".
4. "Mae'n debyg" is the usual way to say "probably".

Correct translation:
Methu rhwymo i %s ar y cyfrifiadur hwn. Mae'n debyg bod %s eisoes yn rhedeg.
```

```
        <source>Unable to open %s for writing</source>
        <translation>Methu agor%sar gyfer ysgrifennu</translation>
    
YES
There is a missing space between '%s' and 'ar gyfer'. The correct translation should read: "Methu agor %s ar gyfer ysgrifennu" (note the space after %s).

Correct translation:
Methu agor %s ar gyfer ysgrifennu
```

```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>Reolau newydd anhysbys wedi'u gweithredu (versionbit%i)</translation>
    
YES
There is a formatting issue: there is no space between "versionbit" and "%i" in the translation, making it harder to read. The English source has a space: "versionbit %i".

Correct translation:
Reolau newydd anhysbys wedi'u gweithredu (versionbit %i)
```

```
        <source>Unrecognised option "%s" provided in -test=&lt;option&gt;.</source>
        <translation>Opcsiwn annasarnhaol "%s "a ddarparwyd yn -test=&lt;option&gt;.</translation>
    
YES
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

```
        <source>Unsupported global logging level %s=%s. Valid values: %s.</source>
        <translation>Llefel logio global nad yw'n cael ei gefnogi%s=%s.Gwerthoedd dilys:%s.</translation>
    
YES
There are whitespace formatting errors: missing spaces after 'cefnogi' and after '%s.', also after the colon in 'Gwerthoedd dilys:'. The translation otherwise appears understandable and uses the correct format specifiers.

Correct translation:
Llefel logio byd-eang nad yw’n cael ei gefnogi %s=%s. Gwerthoedd dilys: %s.
```

```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>nid yw acceptstalefeeestimates yn cael ei gefnogi ar%scadwyn.</translation>
    
YES
There are two issues:
1. In Welsh, "ar%scadwyn" should have a space after "ar": "ar %s gadwyn."
2. For clarity and idiom, it would be better to translate "%s chain" as "gadwyn %s".

Correct translation:
nid yw acceptstalefeeestimates yn cael ei gefnogi ar gadwyn %s.
```

```
        <source>Unsupported logging category %s=%s.</source>
        <translation>Categori logio nad yw'n cael ei gefnogi%s=%s.</translation>
    
YES
There is a missing space before the format specifiers "%s=%s" in the translation, which would make the output look incorrect. Additionally, the definite article is missing; a more natural translation would be:

Correct translation:
Nid yw'r categori logio %s=%s yn cael ei gefnogi.
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Gwall: Ni allwyd ychwanegu tx gwylio'n unig%si waled gwylio'n unig</translation>
    
YES
There are errors in word order, translation of technical terms, and spacing. Specifically:
- "tx gwylio'n unig%si waled gwylio'n unig" combines the abbreviation "tx" with the Welsh for "watch-only", but with no space before %s and awkward word order.
- "tx" (for "transaction") is not translated or explained, which could be acceptable for technical contexts, but it should be separated clearly from the Welsh phrase.
- The translation should keep a space between "tx" and "%s".
- There is no word for "to" ("i" in Welsh) before "waled gwylio'n unig" ("watch-only wallet").

Correct translation:
Gwall: Methu ychwanegu tx gwylio'n unig %s i'r waled gwylio'n unig
```

```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>Sylw Agent Defnyddiwr (%s) yn cynnwys cymeriadau anghyson.</translation>
    
YES
The translation of "unsafe characters" as "cymeriadau anghyson" is inaccurate. "Anghyson" means "inconsistent," which does not convey the security implication of "unsafe." The correct translation should use "anniogel" for "unsafe."

Correct translation:
Sylw’r Asiant Defnyddiwr (%s) yn cynnwys cymeriadau anniogel.
```

```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Roedd angen ailosod y waled:%si gwblhau</translation>
    
YES
There is a spacing issue after the colon; there should be a space before '%s'. Also, "ailosod" means "to reinstall/reset", whereas "ailysgrifennu" is the correct term for "to rewrite" in this context (referring to a wallet being re-written, not reset). The phrase "i gwblhau" ("to complete") is okay. Corrected translation:

Roedd angen ailysgrifennu'r waled: ailgychwynnwch %s i gwblhau
```
</details>

Number of issues: 39.
