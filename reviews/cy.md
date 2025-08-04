# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>cy</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bcy%5D%20low%20quality)


```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>Mae'r weithred hon angen eich cyfrinair waled i ddatgloi'r waled.</translation>
    
YES - The word order is incorrect, and the preposition "i" should not be used in this context. The correct translation is: Mae'r weithred hon angen eich cyfrinair waled i ddatgloi'r waled.
```

```
        <source>Change passphrase</source>
        <translation>Newid cyfrinair</translation>
    
YES, The translation is problematic because "Newid cyfrinair" translates to "Change password" in English. In the context of Bitcoin, "passphrase" is a more specific term than "password" and often refers to a mnemonic phrase used to recover a wallet. A more accurate translation would be "Newid ymadrodd allweddol" or "Newid ymadrodd cyfrinair".

Newid ymadrodd allweddol
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Rhybudd: Os ydych yn amgryptio'r waled ag yn colli'r cyfrinair, byddwch yn &lt;b&gt; COLLI EICH BITCOINS I GYD &lt;b&gt; !</translation>
    
YES: The translation uses "&lt;b&gt;" twice for the opening tag and omits the closing tag for the second instance. It should only be used once. The Welsh word "ag" is also grammatically incorrect and should be "a".

Correct translation: Rhybudd: Os ydych yn amgryptio'r waled a cholli'r cyfrinair, byddwch yn &lt;b&gt;COLLI EICH BITCOINS I GYD&lt;/b&gt;!
```

```
        <source>Your wallet is about to be encrypted. </source>
        <translation>Mae eich waled ar fin cael ei chrypto.</translation>
    
YES
The translation incorrectly uses "crypto" instead of "encrypted".

Mae eich waled ar fin cael ei amgryptio.
```

```
        <source>Your wallet is now encrypted. </source>
        <translation>Mae eich waled nawr wedi'i chrypto.</translation>
    
YES, the translation incorrectly uses "crypto" as a verb in Welsh. The correct translation should convey that the wallet is encrypted.
NO
```

```
        <source>Wallet passphrase was successfully changed.</source>
        <translation>Newid cyfrinair waled yn llwyddiannus.</translation>
    
YES, the translation is problematic. The word "Newid" means "change" or "to change" but it is used as an adjective or noun here which doesn't make sense in the context. The word "wallet" has also been omitted.

The correct translation should be:
Newid cyfrinair waled yn llwyddiannus.
```

```
        <source>Passphrase change failed</source>
        <translation>Method newid geiriau pas wedi methu</translation>
    
YES, The translation is problematic. The phrase "Method newid geiriau pas" is an incorrect and nonsensical translation of "Passphrase change". The word "Method" and "newid" do not fit the context of changing a passphrase. The correct translation for "Passphrase change" would be "Newid cyfrinair".

Method newid geiriau pas wedi methu -> Newid cyfrinair wedi methu
```

```
        <source>Banned Until</source>
        <translation>Gwaharddwyd Nes</translation>
    
YES, The translation is problematic because it is grammatically incorrect and unnatural in Welsh. The word order should be changed to make it grammatically correct and sound more natural.
Gwaharddwyd tan
        <source>Banned Until</source>
        <translation>Gwaharddwyd tan</translation>
```

```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>Digwyddodd gwall angheuol.%1ni all barhau'n ddiogel mwyach a bydd yn cau.</translation>
    
YES, the translation contains an erroneous space after the format specifier.
A fatal error occurred. %1 can no longer continue safely and will quit.
Digwyddodd gwall angheuol. %1 ni all barhau'n ddiogel mwyach a bydd yn cau.
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>Digwyddodd gwall mewnol.%1bydd yn ceisio parhau'n ddiogel.Mae hwn yn fwydyn annisgwyl y gellir ei adrodd fel y disgrifir isod.</translation>
    
YES - The translation has a spacing issue. The "%1" format specifier is not separated from the following word "bydd". The correct translation should have a space after "%1".
Correct translation: Digwyddodd gwall mewnol. %1 bydd yn ceisio parhau'n ddiogel. Mae hwn yn fwydyn annisgwyl y gellir ei adrodd fel y disgrifir isod.
```

```
        <source>Do you want to reset settings to default values, or to abort without making changes?</source>
        <extracomment>Explanatory text shown on startup when the settings file cannot be read. Prompts user to make a choice between resetting or aborting.</extracomment>
        <translation>A ydych chi eisiau adfer gosodiadau i'r gwerthoedd diffinio, neu beidio â gwneud newidiadau a stopio?</translation>
    
YES: The translation uses "peidio â gwneud newidiadau a stopio" which means "to not make changes and stop". The English phrase "abort without making changes" translates to "peidio â gwneud newidiadau". The word "abort" also means to "stop". Therefore, repeating "stop" is redundant.

Correct translation: A ydych chi eisiau adfer gosodiadau i'r gwerthoedd diffinio, neu ohirio heb wneud newidiadau?
```

```
        <source>%1 didn't yet exit safely…</source>
        <translation>%1ni wnaeth fynd allan yn ddiogel eto…</translation>
    
YES: The translation is a literal and somewhat awkward translation of the English phrase. In Welsh, "exit safely" would more naturally be translated as "ymneilltuo'n ddiogel" or "gadael yn ddiogel". Also, the use of "ni wnaeth fynd allan" is grammatically incorrect. A more natural translation would be "%1 hasn't exited safely yet...".
%1 ni allodd ymadael yn ddiogel eto…
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Mae'r procsï yw&lt;b&gt;wedi'i alluog&lt;/b&gt;i:%1</translation>
    
YES - The translation has a spelling error in "Mae'r procsï" which should be "Mae'r prosiect". Additionally, the sentence structure is awkward and could be improved.

Correct translation: Mae'r prosiect wedi'i alluogi: %1
```

```
        <source>Encrypt Wallet…</source>
        <translation>Crypto Waled…</translation>
    
YES, The translation contains a spelling error. "Wallet" is misspelled as "Waled".
Crypto Wallet…
```

```
        <source>Backup Wallet…</source>
        <translation>Bendith Waled…</translation>
    
YES, the translation is problematic because it is inaccurate and uses an inappropriate word. "Bendith" means "blessing" in Welsh, which is not a suitable translation for "Backup Wallet". A more accurate translation would be "Cadwraeth Waled".

NO
```

```
        <source>Change Passphrase…</source>
        <translation>Newid Geiriau Pas…</translation>
    
YES - The translation of "Change Passphrase" is incorrect. The correct Welsh translation for "Change Passphrase" is "Newid Cyfrinair". The provided translation uses "Newid Geiriau Pas", which is a literal translation of "Change Words Pass" and does not convey the intended meaning.

Newid Cyfrinair…
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Dangos y%1neges gymorth i gael rhestr gyda'r opsiynau llinell-gorchymyn Bitcoin posibl</translation>
    
YES - The translation has a spacing issue with the format specifier. It should be "%1" and not "y%1".

Correct translation: Dangos y neges gymorth %1 i gael rhestr gyda'r opsiynau llinell-gorchymyn Bitcoin posibl
```

```
        <source>Wallet Data</source>
        <extracomment>Name of the wallet data file format.</extracomment>
        <translation>Data Waled</translation>
    
YES: The Welsh translation for "Wallet Data" is incorrect. The correct translation should be "Data Waledd".
NO
```

```
        <source>Zoom</source>
        <translation>Mwydo</translation>
    
UNK_LANG
```

```
        <source>Main Window</source>
        <translation>Ffenestr Brydferth</translation>
    
YES, The translation is incorrect. "Main Window" translates to "Prif Ffenestr" in Welsh. The translation provided, "Ffenestr Brydferth", means "Beautiful Window".
Prif Ffenestr
```

```
        <source>%1 client</source>
        <translation>%1cwsmer</translation>
    
YES, The translation is problematic due to a spelling error. The correct translation should be "%1 cwsmer".
YES, %1 cwsmer
```

```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Analluogi gweithgaredd rhwydwaith</translation>
    
YES - The Welsh translation "Analluogi gweithgaredd rhwydwaith" appears to be an attempt to translate "Disable network activity" but uses an incorrect verb. "Analluogi" translates to "disactivate" or "deactivate," which is not the correct meaning of "disable" in this context. The correct translation for "disable" in this context would be "Analluogi" or "Diffodd." The provided translation incorrectly conjugates "analluogi" to "analluogi" which is not a valid form. A more accurate translation would be "Analluogi gweithgaredd rhwydwaith" or "Diffodd gweithgaredd rhwydwaith".

The provided translation is incorrect. The verb "analluogi" is not a valid Welsh verb form. The correct verb for "disable" in this context is "analluogi" or "diffodd".

Correct translation: Analluogi gweithgaredd rhwydwaith
```

```
        <source>Type: %1
</source>
        <translation>Math: %1
</translation>
    
YES, The translation is incorrect and doesn't make sense in the context of Bitcoin. The word "Type" has been translated to "Math" which is not related to Bitcoin terminology.
Correct translation: Math: %1
```

```
        <source>Change:</source>
        <translation>Newid:</translation>
    
YES, The translation is incorrect. "Newid" does not translate to "Change" in the context of Bitcoin. The correct translation for "Change" in this context is "Newid".
        <source>Change:</source>
        <translation>Newid:</translation>
```

```
        <source>Copy transaction ID and output index</source>
        <translation>Copïo ID trafodiad a chyfryngau allbwn</translation>
    
YES: The Welsh word "cyfryngau" translates to "media" or "communications," not "index." The correct Welsh word for "index" in this context is "mynegai."

Copy transaction ID and output index: Copïo ID trafodiad a mynegai allbwn
```

```
        <source>Lock unspent</source>
        <translation>Lloi newid nad yw wedi'i wario</translation>
    
YES, the translation is problematic because it misunderstands the term "unspent". In the context of Bitcoin, "unspent" refers to an output that has not yet been used in a transaction. The Welsh translation "nad yw wedi'i wario" means "that has not been spent" in a general sense, which is not precise enough for the technical context of Bitcoin. A more accurate translation would use a term that specifically relates to unspent transaction outputs.

Correct translation: Lloi heb ei wario
```

```
        <source>(%1 locked)</source>
        <translation>(%1caeedig</translation>
    
YES: The translation is incomplete and nonsensical. The format specifier %1 is followed by random characters instead of the expected numeric value.
(wedi'i gloi %1)
```

```
        <source>Can vary +/- %1 satoshi(s) per input.</source>
        <translation>Gall amrywio +/-%1satoshi(s) y tu mewn.</translation>
    
YES, The translation is problematic because the word "satoshi(s)" is not translated into Welsh. The correct translation for "satoshi(s)" would be "satoshi(s)". The translation also contains a grammatical error, as the word "tu mewn" should be "mewnbwn" to mean "per input".

Here's the corrected translation:
Gall amrywio +/- %1 satoshi(s) y fewnbwn.
```

```
        <source>change from %1 (%2)</source>
        <translation>newid o%1(%2)</translation>
    
YES. The translation is incorrect. "%1" and "%2" are format specifiers that need to be preserved. The word "newid" is not a recognized term in the context of Bitcoin in Welsh, and the preposition "o" (from) is misplaced and grammatically incorrect.

Correct translation: newid o %1 (%2)
Corrected translation: newid o %1 (%2)
```

```
        <source>(change)</source>
        <translation>(newid)</translation>
    
YES, The Welsh translation provided is incorrect. The English word "change" in the context of Bitcoin refers to a returned amount of cryptocurrency. "(newid)" is not a suitable translation for this meaning. A more accurate translation would be "(newid)".

(newid)
```

```
        <source>The wallet '%1' was migrated successfully.</source>
        <translation>Y waled'%1' ymfudodd yn llwyddiannus.</translation>
    
YES, The translation for "wallet" is incorrect and "migrated" is also not the best translation.
The wallet '%1' was migrated successfully.
Y waled '%1' ymfudodd yn llwyddiannus.
The correct translation would be:
Y waled '%1' a symudwyd yn llwyddiannus.
```

```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Y cyfeiriad a roddwyd "%1Nid yw " yn gyfeiriad Bitcoin dilys.</translation>
    
YES - The translation has a syntax error and a missing space. The "%1" format specifier is also incorrectly placed and has an extra "Nid yw".
The entered address "%1" is not a valid Bitcoin address.
```

```
        <source>Could not unlock wallet.</source>
        <translation>Methodd ddatgloi'r waled.</translation>
    
YES - The translation is incorrect. The correct translation of "Could not unlock wallet." to Welsh is "Methodd ddatgloi'r waled.". There seems to be a typo in the original translation.
Methodd ddatgloi'r waled.
```

```
        <source>New key generation failed.</source>
        <translation>Methodd gynhyrchu allwedd newydd.</translation>
    
YES, The translation is inaccurate. The English phrase "New key generation failed" indicates a failure in the process. The Welsh translation "Methodd gynhyrchu allwedd newydd" translates to "Method of new key generation" which does not convey the failure. The correct translation should reflect that the generation did not succeed.

NO
```

```
        <source>Directory already exists. Add %1 if you intend to create a new directory here.</source>
        <translation>Mae'r cyfeiriadur eisoes yn bodoli. Ychwanegu%1os ydych yn bwriadu creu cyfeiriadur newydd yma.</translation>
    
YES, The Welsh translation for "%1" is missing a space between the number and the letter. The correct translation should include a space.

Correct translation: Mae'r cyfeiriadur eisoes yn bodoli. Ychwanegu %1 os ydych yn bwriadu creu cyfeiriadur newydd yma.
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>O leiaf%1Bydd GB o ddata yn cael ei storio yn y cyfeiriadur hwn, a bydd yn tyfu dros amser.</translation>
    
YES, The translation is problematic because of spacing issues with the format specifier %1 and the unit GB. The format specifier should have a space after it, and the unit GB should have a space before it.
The correct translation is: O leiaf %1 GB o ddata yn cael ei storio yn y cyfeiriadur hwn, a bydd yn tyfu dros amser.
```

```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Oddeutu%1Bydd GB o ddata yn cael ei storio yn y cyfeiriadur hwn.</translation>
    
YES: The space between "Oddeutu" and "%1" is incorrect. The correct translation should be "Oddeutu %1 GB o ddata fydd yn cael ei storio yn y cyfeiriadur hwn.".
```

```
        <source>Automatically start %1 after logging in to the system.</source>
        <translation>Cychwyn yn awtomatig%1ar ôl mewngofnodi i'r system.</translation>
    
YES: The translation is missing a space after the format specifier %1.
Correct translation: Cychwyn yn awtomatig %1 ar ôl mewngofnodi i'r system.
```

```
        <source>Start %1 on system login</source>
        <translation>Cychwyn%1ar mewngofnodi i'r system</translation>
    
YES, The word "mewngofnodi i'r system" is grammatically incorrect. The correct translation is "mewngofnodi system".

Corrected translation: Cychwyn%1ar mewngofnodi system
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Mae galluogi torri'n sylweddol yn lleihau'r gofod disg sydd ei angen i storio trafodion. Mae pob bloc yn parhau i gael ei ddilysu'n llawn. Bydd adfer y gosodiad hwn yn gofyn am ailosodlawr y blwch cyfan.</translation>
    
YES - The Welsh translation for "re-downloading" is incorrect. It should be "ail-lwytho" instead of "ailosodlawr".

NO
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>Llwybr llawn i%1sgript gymhwysol (e.e. C:\Downloads\hwi.exe neu /Users/you/Downloads/hwi.py). Rhowch sylw: gall malware ddwyn eich ceiniogau!</translation>
    
YES - The format specifier `%1` is not correctly transferred from the source to the translation. It should be `%1`. Also, the word 'sgript' should be separated from '%1'.

Llwybr llawn i %1 sgript cymhwysol (e.e. C:\Downloads\hwi.exe neu /Users/you/Downloads/hwi.py). Rhowch sylw: gall malware ddwyn eich ceiniogau!
```

```
        <source>Minimize instead of exit the application when the window is closed. When this option is enabled, the application will be closed only after selecting Exit in the menu.</source>
        <translation>Mewnosod yn lle cau'r cymhwysiad pan fydd y ffenestr yn cael ei chau. Pan fydd y dewis hwn yn cael ei alluogi, caiff y cymhwysiad ei gau dim ond ar ôl dewis Cau yn y ddewislen.</translation>
    
YES - The translation incorrectly uses "Mewnosod" (insert/embed) instead of "Minimize" (Minimize). The correct translation for "Minimize" in this context is "Cyn lleied â phosibl".

The translation also incorrectly uses "cau" (close) for "exit". The correct translation for "exit" in this context is "allan".

Here's the corrected translation:

Minimize instead of exit the application when the window is closed. When this option is enabled, the application will be closed only after selecting Exit in the menu.
Cyn lleied â phosibl yn lle gadael yr ymgehwysiad pan fydd y ffenestr yn cael ei chau. Pan fydd y dewisiad hwn yn cael ei alluogi, caiff yr ymgehwysiad ei gau dim ond ar ôl dewis Gadael yn y ddewislen.
```

```
        <source>Open the %1 configuration file from the working directory.</source>
        <translation>Agor y%1ffilet gosodiad o'r directory gweithio.</translation>
    
YES, The translation incorrectly places the "%1" format specifier immediately after the word "y" without a space. Additionally, "gosodiad" is not the standard term for configuration in this context, and "directory gweithio" is a direct transliteration that could be improved.

Correct translation: Agorwch y ffeil cyfluniad %1 o'r cyfeiriadur gweithio.
```

```
        <source>Prune block storage to</source>
        <translation>Torri storfa bloc i</translation>
    
YES - The translation is inaccurate. The Welsh word "storfa" means "storage" or "archive" but the context implies a database or file system rather than an archive. Also, "bloc" is not a standard Welsh word for "block".

Correct translation: Torri storfa blociau i
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Bydd ailosod y gosodiad hwn yn gofyn am ailosodlawr y gadwyn floc gyfan.</translation>
    
YES, The translation is problematic because the word "ailosodlawr" is not a valid Welsh word. It seems to be a misspelling or an incorrect combination of words. The correct translation should convey "re-downloading".

The correct translation is:
        <translation>Bydd ailosod y gosodiad hwn yn gofyn am lawrlwytho'r gadwyn floc gyfan eto.</translation>
```

```
        <source>Used for reaching peers via:</source>
        <translation>Defnyddir ar gyfer cyrraedd cyd-fyfyrwyr trwy:</translation>
    
UNK_LANG
```

```
        <source>Type</source>
        <extracomment>Title of Peers Table column which describes the type of peer connection. The "type" describes why the connection exists.</extracomment>
        <translation>Math</translation>
    
YES, The translation is inaccurate and nonsensical in the given context. The English word "Type" refers to the category or kind of peer connection, not "Math".
Math
```

```
        <source>Could not unlock wallet.</source>
        <translation>Methodd ddatgloi'r waled.</translation>
    
YES - The translation is incorrect. The correct translation of "Could not unlock wallet." to Welsh is "Methodd ddatgloi'r waled.". There seems to be a typo in the original translation.
Methodd ddatgloi'r waled.
```

```
        <source>Change:</source>
        <translation>Newid:</translation>
    
YES, The translation is incorrect. "Newid" does not translate to "Change" in the context of Bitcoin. The correct translation for "Change" in this context is "Newid".
        <source>Change:</source>
        <translation>Newid:</translation>
```

```
        <source>Type</source>
        <translation>Math</translation>
    
YES, The translation is inaccurate. "Type" in the context of Bitcoin usually refers to the type of transaction or output. "Math" is not a relevant term in this context.
A more appropriate translation would be "Math".

**Correct Translation:**
<translation>Math</translation>
```

```
        <source>Type</source>
        <translation>Math</translation>
    
YES, The translation is inaccurate. "Type" in the context of Bitcoin usually refers to the type of transaction or output. "Math" is not a relevant term in this context.
A more appropriate translation would be "Math".

**Correct Translation:**
<translation>Math</translation>
```

```
        <source>Wallet Data</source>
        <extracomment>Name of the wallet data file format.</extracomment>
        <translation>Data Waled</translation>
    
YES: The Welsh translation for "Wallet Data" is incorrect. The correct translation should be "Data Waledd".
NO
```

```
        <source>Unable to bind to %s on this computer. %s is probably already running.</source>
        <translation>Methu cysylltu â%sar y cyfrifiadur hwn.%syn debyg eisoes yn rhedeg.</translation>
    
YES - The translation is missing spaces after the format specifiers %s.
Methu cysylltu â %s ar y cyfrifiadur hwn. %s syn debyg eisoes yn rhedeg.
```

```
        <source>Unable to create the PID file '%s': %s</source>
        <translation>Methu creu'r ffeil PID '%s':%s</translation>
    
YES
The translation contains a spacing error. The colon after the first '%s' is directly followed by the second '%s' which is incorrect. There should be a space between them.

Correct translation:
Methu creu'r ffeil PID '%s': %s
```

```
        <source>Unable to open %s for writing</source>
        <translation>Methu agor%sar gyfer ysgrifennu</translation>
    
YES
The translation has a spacing issue. The "%s" format specifier should be separated from "agor" by a space.

Methu agor %s ar gyfer ysgrifennu
```

```
        <source>Unknown address type '%s'</source>
        <translation>Math cyfeiriad anhysbys '%s'</translation>
    
YES, Math cyfeiriad anhysbys '%s' is not a correct translation for "Unknown address type '%s'". The word "Math" means "type" in Welsh, but it seems to be used here as a proper noun or as a prefix without a proper context.

The correct translation should be:

Math cyfeiriad anhysbys '%s' -> Type of unknown address '%s'

NO
```

```
        <source>Unknown change type '%s'</source>
        <translation>Math newid anhysbys '%s'</translation>
    
YES - The Welsh translation is incorrect and nonsensical. The word "Math" means "Type" or "Kind" in Welsh, and "newid" means "change". However, "newid" is used incorrectly here, and the phrase "Math newid" is not a standard or understandable Welsh expression in this context.

A more appropriate translation for "Unknown change type '%s'" in the context of Bitcoin would be:

"Math adfer anhysbys '%s'"

Here's the breakdown:
*   **Math:** Correctly translates to "Type".
*   **adfer:** This word means "return" or "change" in the sense of a refund or returning something, which fits the context of Bitcoin change.
*   **anhysbys:** Correctly translates to "unknown".
*   **'%s'**: The format specifier is correctly carried over.

Corrected Translation:
<translation>Math adfer anhysbys '%s'</translation>
```

```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>Reolau newydd anhysbys wedi'u gweithredu (versionbit%i)</translation>
    
YES, The translation incorrectly handles the format specifier. There should be a space between "versionbit" and "%i".

Correct translation: Reolau newydd anhysbys wedi'u gweithredu (versionbit %i)
```

```
        <source>Unrecognised option "%s" provided in -test=&lt;option&gt;.</source>
        <translation>Opcsiwn annasarnhaol "%s "a ddarparwyd yn -test=&lt;option&gt;.</translation>
    
YES: The translation contains a stray space after the format specifier "%s".
Correct translation: Opcsiwn annasarnhaol "%s" a ddarparwyd yn -test=&lt;option&gt;.
```

```
        <source>Unsupported global logging level %s=%s. Valid values: %s.</source>
        <translation>Llefel logio global nad yw'n cael ei gefnogi%s=%s.Gwerthoedd dilys:%s.</translation>
    
YES. The translation is problematic due to incorrect spacing. The space between "%s=%s." and "Gwerthoedd" is missing, and there is an unnecessary space between "dilys" and "%s.".

Corrected translation: Llefel logio global nad yw'n cael ei gefnogi %s=%s. Gwerthoedd dilys: %s.
```

```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>nid yw acceptstalefeeestimates yn cael ei gefnogi ar%scadwyn.</translation>
    
YES, The space before %s in the translation is missing.
nid yw acceptstalefeeestimates yn cael ei gefnogi ar %s cadwyn.
```

```
        <source>Unsupported logging category %s=%s.</source>
        <translation>Categori logio nad yw'n cael ei gefnogi%s=%s.</translation>
    
YES - The translation is missing a space between "nad" and "yw", and also between "cael" and "ei". The correct translation should be "Categori logio nad yw'n cael ei gefnogi %s=%s."
Categori logio nad yw'n cael ei gefnogi %s=%s.
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Gwall: Ni allwyd ychwanegu tx gwylio'n unig%si waled gwylio'n unig</translation>
    
YES: The Welsh translation incorrectly attaches the format specifier "%s" to the word "unig" instead of leaving it as a separate element after the word it modifies. The word order also feels slightly unnatural.

Gwall: Ni allwyd ychwanegu tx gwylio'n unig %s i waled gwylio'n unig
```

```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>Sylw Agent Defnyddiwr (%s) yn cynnwys cymeriadau anghyson.</translation>
    
YES: The word "anghyson" in the translation means "inconsistent" or "discordant," which is not the correct translation for "unsafe" in this context. The correct translation for "unsafe" in relation to characters would be "annigonol" or "peryglus".

Correct translation: Sylw Agent Defnyddiwr (%s) yn cynnwys cymeriadau anniogus.
```

```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Roedd angen ailosod y waled:%si gwblhau</translation>
    
YES, The translation is problematic because it is grammatically incorrect and nonsensical in Welsh. The original English text "Wallet needed to be rewritten: restart %s to complete" translates to "Roedd angen ailosod y waled:%si gwblhau". This translates back to English as "The wallet needed to be reset:%s to complete", which is not the intended meaning.

A more accurate translation would be:

"Roedd angen ailysgrifennu'r waled: ailgychwyn %s i orffen."
```
</details>
