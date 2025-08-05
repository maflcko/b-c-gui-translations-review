# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>cy</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bcy%5D%20low%20quality)


```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Rhybudd: Os ydych yn amgryptio'r waled ag yn colli'r cyfrinair, byddwch yn &lt;b&gt; COLLI EICH BITCOINS I GYD &lt;b&gt; !</translation>
    
YES  
The translation has spacing issues and an incorrect closing tag. The closing bold tag should be </b>, not &lt;b&gt;. Also, spacing around the bold tags is incorrect (there should be no space immediately inside the tags), and "Os ydych" can be better translated as "Os ydych yn" (correct as is), but the phrase "ag yn colli'r cyfrinair" is wrong: "ag" should be "a" ("and" in Welsh). Additionally, "COLLI EICH BITCOINS I GYD" is not idiomatic Welsh—"lose all of your bitcoins" would be better as "COLLI CHI'R HOLL BITCOINS CYMERYD" or more naturally "COLLI'R HOLL BITCOINS".  

A better translation:  
Rhybudd: Os ydych yn amgryptio'ch waled a byddwch yn colli'ch cyfrinair, byddwch yn &lt;b&gt;COLLI'R HOLL BITCOINS CYMERYD&lt;/b&gt;!  

Or more simply:  
Rhybudd: Os ydych yn amgryptio'ch waled a byddwch yn colli'ch cyfrinair, byddwch yn &lt;b&gt;COLLI'R HOLL BITCOINS&lt;/b&gt;!  

Summary of corrections:  
- Replace "ag" with "a"  
- Remove spaces inside bold tags  
- Close bold tag properly with &lt;/b&gt;  
- Fix phrasing for "lose all your bitcoins" to a natural Welsh expression  

Correct translation:  
Rhybudd: Os ydych yn amgryptio'ch waled a byddwch yn colli'ch cyfrinair, byddwch yn &lt;b&gt;COLLI'R HOLL BITCOINS&lt;/b&gt;!
```

```
        <source>Your wallet is about to be encrypted. </source>
        <translation>Mae eich waled ar fin cael ei chrypto.</translation>
    
YES  
The Welsh word for "wallet" in the Bitcoin context is more appropriately "poced" or "walet" rather than "waled," which appears to be an incorrect or non-standard form. Also, "cael ei chrypto" is not idiomatic Welsh; a better translation would use a proper verb form such as "wedi'i hamgryptio" (meaning "to be encrypted"). The trailing space in the source is not preserved, but that is minor.

Correct translation:  
Mae eich walet ar fin cael ei hamgryptio.
```

```
        <source>Your wallet is now encrypted. </source>
        <translation>Mae eich waled nawr wedi'i chrypto.</translation>
    
YES  
The translation is problematic. The word "chrypto" is not a correct Welsh word for "encrypted." The phrase "wedi'i chrypto" is an inaccurate calque from English rather than a proper Welsh expression. A better translation would use "wedi'i amgryptio," which is the correct past participle form for "encrypted."

Correct translation:  
Mae eich waled nawr wedi'i amgryptio.
```

```
        <source>Wallet passphrase was successfully changed.</source>
        <translation>Newid cyfrinair waled yn llwyddiannus.</translation>
    
YES  
The translation erroneously mixes Welsh and English and uses "waled" (English "wallet" phonetically), which is not correct Welsh. Also, "passphrase" is translated as "cyfrinair" (password), which is acceptable but ideally should be "cyfres allweddi" or "brawddeg gyfrinach" if strictly "passphrase" is needed. The verb form should agree with the sentence subject, and the sentence can be more complete.

Correct translation:  
"Newidiodd brawddeg gyfrinach y waled yn llwyddiannus."  
or more simply:  
"Newidiodd cyfrinair y waled yn llwyddiannus."
```

```
        <source>Passphrase change failed</source>
        <translation>Method newid geiriau pas wedi methu</translation>
    
YES
The translation is incorrect because it literally translates "Passphrase change failed" as "Method newid geiriau pas wedi methu," which means "Method change of password words failed," mixing English and Welsh with incorrect word order and unnecessary words. The correct Welsh translation for "Passphrase change failed" is:

Newid y cyfrinair methwyd
```

```
        <source>Banned Until</source>
        <translation>Gwaharddwyd Nes</translation>
    
YES  
The Welsh translation misses the preposition "tan" (meaning "until"), which is necessary for the phrase to be correct and natural. "Nes" is more suitable for "until" in terms of temporal conjunction but generally used in conjunction with "tan" in this context. The translation should properly reflect the phrase "Banned Until" as a heading or label indicating a time limit.

Correct translation:  
Gwaharddwyd Tan
```

```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>Digwyddodd gwall angheuol.%1ni all barhau'n ddiogel mwyach a bydd yn cau.</translation>
    
YES  
There are spacing issues in the translation. There should be a space after the period and before "%1", and a space after "%1" as well. Also, the sentence is generally correct but needs spacing correction.

Correct translation:  
"Digwyddodd gwall angheuol. %1 ni all barhau'n ddiogel mwyach a bydd yn cau."
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>Digwyddodd gwall mewnol.%1bydd yn ceisio parhau'n ddiogel.Mae hwn yn fwydyn annisgwyl y gellir ei adrodd fel y disgrifir isod.</translation>
    
YES  
The translation is missing spaces after the periods and between words, causing it to be hard to read and incorrect formatting. The phrase "Mae hwn yn fwydyn annisgwyl" contains a typo: "fwydyn" should be "bwydyn" ("bug").

Correct translation:  
"Digwyddodd gwall mewnol. %1 bydd yn ceisio parhau'n ddiogel. Mae hwn yn fwydyn annisgwyl y gellir ei adrodd fel y disgrifir isod."
```

```
        <source>Do you want to reset settings to default values, or to abort without making changes?</source>
        <extracomment>Explanatory text shown on startup when the settings file cannot be read. Prompts user to make a choice between resetting or aborting.</extracomment>
        <translation>A ydych chi eisiau adfer gosodiadau i'r gwerthoedd diffinio, neu beidio â gwneud newidiadau a stopio?</translation>
    
YES  
The translation uses "gwerthoedd diffinio" which is incorrect for "default values." The correct term is "gwerthoedd diofyn." Also, "neu beidio â gwneud newidiadau a stopio?" is a bit awkward; a clearer translation would be "neu beidio â gwneud newidiadau a rhoi'r gorau iddi?" or simply "neu beidio â gwneud newidiadau a rhoi'r gorau i'r weithred?"  

Correct translation:  
A ydych chi eisiau adfer gosodiadau i'r gwerthoedd diofyn, neu beidio â gwneud newidiadau a rhoi'r gorau iddi?
```

```
        <source>%1 didn't yet exit safely…</source>
        <translation>%1ni wnaeth fynd allan yn ddiogel eto…</translation>
    
YES
There is a missing space after "%1" in the translation. It should be "%1 ni wnaeth fynd allan yn ddiogel eto…".

Correct translation:
%1 ni wnaeth fynd allan yn ddiogel eto…
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Mae'r procsï yw&lt;b&gt;wedi'i alluog&lt;/b&gt;i:%1</translation>
    
YES  
There are spacing errors around the HTML tags and before the placeholder %1. Proper spacing and punctuation improve readability in Welsh.

Correct translation:  
Mae'r procsï yw &lt;b&gt;wedi'i alluogi&lt;/b&gt;: %1
```

```
        <source>Encrypt Wallet…</source>
        <translation>Crypto Waled…</translation>
    
YES  
The translation is incorrect. "Encrypt Wallet…" should be translated to Welsh as "Amgryptio'r Waled…" or "Amgryptio'r Arianfa…", using the proper Welsh verb for "Encrypt" ("Amgryptio") and the correct Welsh word for "Wallet" ("Waled"). Also, "Crypto Waled" is partly English and misspelled ("Waled" instead of "Waled"), and does not convey the intended meaning. The ellipsis (…) should be preserved.  
  
Correct translation:  
Amgryptio'r Waled…
```

```
        <source>Backup Wallet…</source>
        <translation>Bendith Waled…</translation>
    
YES  
The Welsh word for "Wallet" is "Ariannwr" or "Poced," not "Waled." Additionally, "Backup" is best translated as "Copïo wrth gefn." The ellipsis character (…) is correctly used and spacing is appropriate.

Correct translation:  
Bendith Ariannwr…
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Dangos y%1neges gymorth i gael rhestr gyda'r opsiynau llinell-gorchymyn Bitcoin posibl</translation>
    
YES  
There is a formatting error with the placeholder "%1" in the translation: it appears as "y%1neges" instead of "y %1 neges". Also, the phrase could be made smoother and clearer in Welsh by adding appropriate spacing and a clearer structure.

Correct translation:  
Dangos y neges gymorth %1 i gael rhestr gyda'r opsiynau llinell-gorchymyn Bitcoin posibl
```

```
        <source>Wallet Data</source>
        <extracomment>Name of the wallet data file format.</extracomment>
        <translation>Data Waled</translation>
    
YES
The word "Wallet" is incorrectly translated as "Waled," which is not a valid Welsh word. The correct Welsh term for "Wallet" is "Poced" or "Wallet" (commonly 'Wallet' is kept in English in technical contexts, but "Poced" is the Welsh for wallet). The word "Data" should remain as "Data," as it is commonly used. 

Correct translation:
Data Poced
```

```
        <source>Zoom</source>
        <translation>Mwydo</translation>
    
YES  
The Welsh translation "Mwydo" means "to feed" or "feeding," which is incorrect for the English word "Zoom." In the context of Bitcoin software UI, "Zoom" likely refers to adjusting the view scale. The correct Welsh translation would be "Chwyddo."  

Correct translation:  
<translation>Chwyddo</translation>
```

```
        <source>Main Window</source>
        <translation>Ffenestr Brydferth</translation>
    
YES
The Welsh translation "Ffenestr Brydferth" means "Beautiful Window," which is incorrect for "Main Window." The correct translation for "Main Window" in Welsh is "Prif Ffenestr."
```

```
        <source>%1 client</source>
        <translation>%1cwsmer</translation>
    
YES  
The Welsh translation is incorrect. The word "client" should be translated as "cleient," and there is a spacing issue with "%1" and the word. They should be separated by a space.

Correct translation:  
%1 cleient
```

```
        <source>Copy transaction ID and output index</source>
        <translation>Copïo ID trafodiad a chyfryngau allbwn</translation>
    
YES  
The translation contains a non-Welsh word "Copïo" with an incorrect diaeresis (ï) and also uses the incorrect word "trafodiad" spelled as "trafodiad" instead of the correct "trafodiad" (correct spelling is "trafodiad," but it was correctly spelled here; actually the issue is the word copying roughly as "Copïo" which is an adaptation from English but the Welsh word is "Copïo" (with ï). However, the diaeresis on ï is used in Welsh to indicate that the vowel is pronounced separately, so "Copïo" is actually an acceptable Welsh word for "copy" (pronounced co-pee-o), so that part is acceptable.

Next, "ID trafodiad" is correct for "transaction ID".

Then the rest "a chyfryngau allbwn" is wrong.

"chyfryngau" means "media" or "channels" or "means", it shouldn't be used here.

The English phrase is "Copy transaction ID and output index".

"output index" in context of Bitcoin is typically translated into Welsh as "mynegai allbwn".

Hence, "a chyfryngau allbwn" is totally wrong. It should be "a mynegai allbwn".

Correct translation should be:

"Copïo ID trafodiad a mynegai allbwn"

Therefore, the sentence contains erroneous content.

Correct translation:

Copïo ID trafodiad a mynegai allbwn
```

```
        <source>Lock unspent</source>
        <translation>Lloi newid nad yw wedi'i wario</translation>
    
YES  
The translation is incorrect. "Lock unspent" in the Bitcoin context means to "lock" the "unspent" (outputs/coins), not "change." The provided translation "Lloi newid nad yw wedi'i wario" translates back as "Lock change that is not spent," which is misleading because "newid" means "change" as in change from a transaction, not the generic "unspent." The correct translation for "Lock unspent" should focus on locking "unspent outputs" or "unspent coins," which is correctly rendered as:

"Lloi'r heb ei wario"
```

```
        <source>(%1 locked)</source>
        <translation>(%1caeedig</translation>
    
YES  
The translation is incomplete and missing the closing parenthesis. Also, "caeedig" does not appear to be a correct Welsh word. The correct Welsh translation for "(%1 locked)" would be "(%1 wedi'i gloi)".  

Correct translation:  
(%1 wedi'i gloi)
```

```
        <source>Can vary +/- %1 satoshi(s) per input.</source>
        <translation>Gall amrywio +/-%1satoshi(s) y tu mewn.</translation>
    
YES  
There is a missing space after the "+/-" and before "%1", and also missing space before "satoshi(s)". The original spacing around "%1" and "satoshi(s)" should be preserved. Also, "y tu mewn" correctly means "per input" or "at each input," so it is acceptable.

Correct translation:  
Gall amrywio +/- %1 satoshi(s) y tu mewn.
```

```
        <source>change from %1 (%2)</source>
        <translation>newid o%1(%2)</translation>
    
YES  
There is a spacing issue in the Welsh translation. There should be a space after the preposition "o" and before the first placeholder %1, as in the English source. Also, a space is needed between %1 and the opening bracket.  

Correct translation:  
newid o %1 (%2)
```

```
        <source>The wallet '%1' was migrated successfully.</source>
        <translation>Y waled'%1' ymfudodd yn llwyddiannus.</translation>
    
YES  
There is a spacing issue and a typo in the translation. "waled" should be "wallet" (or better translated into Welsh as "waled"), and there should be a space after "Y" and before the wallet name placeholder '%1'. Also, the Welsh word for "wallet" is "waled".  

Correct translation:  
Y waled '%1' ymfudodd yn llwyddiannus.
```

```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Y cyfeiriad a roddwyd "%1Nid yw " yn gyfeiriad Bitcoin dilys.</translation>
    
YES  
The translation is missing spacing and the word order is incorrect. There is no space after "%1" and before "Nid yw". The sentence is scrambled.

Correct translation:  
Y cyfeiriad a roddwyd "%1" nid yw'n gyfeiriad Bitcoin dilys.
```

```
        <source>Could not unlock wallet.</source>
        <translation>Methodd ddatgloi'r waled.</translation>
    
YES  
The Welsh translation contains errors: "Methodd ddatgloi'r waled." is incorrect. The English sentence means "Could not unlock wallet." A proper Welsh translation would be:  
"Ni allwyd ddatgloi'r waled."
```

```
        <source>New key generation failed.</source>
        <translation>Methodd gynhyrchu allwedd newydd.</translation>
    
YES  
The translation "Methodd gynhyrchu allwedd newydd." is incorrect. It translates back as "Method of generating a new key." The original English text indicates a failure ("New key generation failed."), but the Welsh translation omits the failure aspect.

Correct translation:  
"Methodd creu allwedd newydd."
```

```
        <source>Directory already exists. Add %1 if you intend to create a new directory here.</source>
        <translation>Mae'r cyfeiriadur eisoes yn bodoli. Ychwanegu%1os ydych yn bwriadu creu cyfeiriadur newydd yma.</translation>
    
YES  
The Welsh translation contains spacing errors and incorrect word forms. There should be a space between "Ychwanegu" and "%1". Also, "Ychwanegu" (Add) should be in the correct verb form to fit the conditional structure; "Ychwanegwch" (imperative) or a phrasing like "Ychwanegwch %1 os..." would be more appropriate. Also, the phrase "os ydych yn bwriadu" is correct but normally in Welsh the verb "os ydych" combines as "os ydych chi" or "os ydych". The existing sentence also merges words incorrectly ("Ychwanegu%1os").  

A better translation would be:  
"Mae'r cyfeiriadur eisoes yn bodoli. Ychwanegwch %1 os ydych yn bwriadu creu cyfeiriadur newydd yma."
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>O leiaf%1Bydd GB o ddata yn cael ei storio yn y cyfeiriadur hwn, a bydd yn tyfu dros amser.</translation>
    
YES  
The translation has spacing issues and incorrect word ordering. In Welsh, "O leiaf" should be followed by a space before the number placeholder %1, and "Bydd GB o ddata" should not be concatenated directly with the previous phrase. Also, the placeholder %1 should maintain its position and spacing correctly.

Correct translation:  
O leiaf %1 GB o ddata yn cael ei storio yn y cyfeiriadur hwn, a bydd yn tyfu dros amser.
```

```
        <source>Approximately %1 GB of data will be stored in this directory.</source>
        <translation>Oddeutu%1Bydd GB o ddata yn cael ei storio yn y cyfeiriadur hwn.</translation>
    
YES  
The translation lacks proper spacing, and "Oddeutu" ("Approximately") and "%1" need a space between them. Also, a space is needed between "%1" and "Bydd". The corrected translation is:  
"Oddeutu %1 Bydd GB o ddata yn cael ei storio yn y cyfeiriadur hwn."
```

```
        <source>Automatically start %1 after logging in to the system.</source>
        <translation>Cychwyn yn awtomatig%1ar ôl mewngofnodi i'r system.</translation>
    
YES  
There are spacing issues in the translation. The phrase "awtomatig%1ar" should have spaces around %1: "awtomatig %1 ar".  

Correct translation:  
Cychwyn yn awtomatig %1 ar ôl mewngofnodi i'r system.
```

```
        <source>Start %1 on system login</source>
        <translation>Cychwyn%1ar mewngofnodi i'r system</translation>
    
YES
There is missing spacing around the format specifier and words in the translation. It should have spaces after "Cychwyn" and before "ar" to be properly readable and match the source.

Correct translation:
Cychwyn %1 ar mewngofnodi i'r system
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Mae galluogi torri'n sylweddol yn lleihau'r gofod disg sydd ei angen i storio trafodion. Mae pob bloc yn parhau i gael ei ddilysu'n llawn. Bydd adfer y gosodiad hwn yn gofyn am ailosodlawr y blwch cyfan.</translation>
    
YES  
The translation has an issue with the phrase "ailosodlawr y blwch cyfan," which is incorrect and confusing. The correct phrase should translate "re-downloading the entire blockchain." In Welsh, "re-downloading" can be rendered as "ail lawrlwytho," and "blockchain" as "cadwyn bloc" or "blockchain" (often untranslated).

Correct translation:  
"Mae galluogi torri'n sylweddol yn lleihau'r gofod disg sydd ei angen i storio trafodion. Mae pob bloc yn parhau i gael ei ddilysu'n llawn. Bydd adfer y gosodiad hwn yn gofyn am ail lawrlwytho'r cadwyn bloc gyfan."
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>Llwybr llawn i%1sgript gymhwysol (e.e. C:\Downloads\hwi.exe neu /Users/you/Downloads/hwi.py). Rhowch sylw: gall malware ddwyn eich ceiniogau!</translation>
    
YES  
There are spacing issues in the translation around the "%1" specifier and the word "sgript". Also, the word "malware" is left untranslated, which is acceptable if it's commonly used, but in Welsh "malware" is often left as is or sometimes translated as "meddalwedd niweidiol". The key problem is the missing spaces before and after "%1" and before "sgript".

Correct translation:  
Llwybr llawn i %1 sgript gymhwysol (e.e. C:\Downloads\hwi.exe neu /Users/you/Downloads/hwi.py). Rhowch sylw: gall malware ddwyn eich ceiniogau!
```

```
        <source>Open the %1 configuration file from the working directory.</source>
        <translation>Agor y%1ffilet gosodiad o'r directory gweithio.</translation>
    
YES  
The translation contains multiple issues:  
- "Agor y%1ffilet" has incorrect spacing and concatenates the format specifier %1 with surrounding words incorrectly. There should be a space after "y" and before "%1", and "ffilet" seems to be a misspelling of "ffile" (file).  
- The English word "directory" is untranslated and should be translated to "cyfeiriadur" in Welsh.  
- "working directory" should be translated as "cyfeiriadur gwaith" or "cyfeiriadur gweithio".  

A corrected Welsh translation would be:  
"Agor y ffeil gosodiad %1 o'r cyfeiriadur gwaith."
```

```
        <source>Prune block storage to</source>
        <translation>Torri storfa bloc i</translation>
    
YES
The translation is incorrect as it is in Welsh ('cy' is the Welsh language code), but the given translation is actually in Breton or a similar Celtic language, not Welsh. Also, the translation does not convey the correct meaning. The English phrase "Prune block storage to" refers to reducing or trimming the block storage size to a certain level, which should be reflected in Welsh.

Correct Welsh translation:
"Torri storfa bloc i" should be:
"Torri storfa bloc i" (if 'torri' is used for 'prune'), but more accurate would be:  
"Lleihau storfa bloc i"  
or  
"Lleihau storfa bloc i" 

A recommended translation:
"Torri storfa bloc i"  
But since "torri" literally means "cut," a more natural translation for "prune" (in the technical sense of reducing) is "lleihau" (reduce). So the best translation is:

"Lleihau storfa bloc i"
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>Bydd ailosod y gosodiad hwn yn gofyn am ailosodlawr y gadwyn floc gyfan.</translation>
    
YES  
The translation contains an unclear and incorrect term "ailosodlawr" which is not a correct Welsh word. The English phrase "re-downloading" should be translated to something like "ail-lawrlwytho" or "lawrlwytho eto" to correctly convey the meaning of downloading again. Also, "blockchain" is commonly translated as "cadwyn flociau" in Welsh, not "gadwyn floc" (missing the plural suffix "iau").

Correct translation:  
Bydd ailosod y gosodiad hwn yn gofyn am ail-lawrlwytho'r holl gadwyn flociau.
```

```
        <source>Used for reaching peers via:</source>
        <translation>Defnyddir ar gyfer cyrraedd cyd-fyfyrwyr trwy:</translation>
    
YES  
The Welsh translation uses "cyd-fyfyrwyr," which means "fellow students" or "classmates," rather than "peers" in the context of peers on a network. The correct translation for "peers" in this Bitcoin/network context would be "cygwon" or "cynghreiriaid."

Correct translation:  
Defnyddir ar gyfer cyrraedd cygwon trwy:
```

```
        <source>Could not unlock wallet.</source>
        <translation>Methodd ddatgloi'r waled.</translation>
    
YES  
The Welsh translation contains errors: "Methodd ddatgloi'r waled." is incorrect. The English sentence means "Could not unlock wallet." A proper Welsh translation would be:  
"Ni allwyd ddatgloi'r waled."
```

```
        <source>Wallet Data</source>
        <extracomment>Name of the wallet data file format.</extracomment>
        <translation>Data Waled</translation>
    
YES
The word "Wallet" is incorrectly translated as "Waled," which is not a valid Welsh word. The correct Welsh term for "Wallet" is "Poced" or "Wallet" (commonly 'Wallet' is kept in English in technical contexts, but "Poced" is the Welsh for wallet). The word "Data" should remain as "Data," as it is commonly used. 

Correct translation:
Data Poced
```

```
        <source>Unable to bind to %s on this computer. %s is probably already running.</source>
        <translation>Methu cysylltu â%sar y cyfrifiadur hwn.%syn debyg eisoes yn rhedeg.</translation>
    
YES  
There are spacing issues around the format specifiers and missing spaces between words in the Welsh translation. The corrected translation should have spaces properly placed before and after the format specifiers %s.

Correct translation:  
Methu cysylltu â %s ar y cyfrifiadur hwn. %s yn debyg eisoes yn rhedeg.
```

```
        <source>Unable to create the PID file '%s': %s</source>
        <translation>Methu creu'r ffeil PID '%s':%s</translation>
    
YES  
The translation contains a typo: "creu'r" should be "creu'r" but the space before the colon is missing. In Welsh, there should be a space before the colon or at least consistent spacing as in the source. The source has a space before and after the colon ("%s': %s"). The translation currently lacks a space after the colon ("%s':%s"). Also, "Methu" is correct for "Unable", and "creu'r ffeil PID" is a correct phrase for "create the PID file".  

Correct translation:  
Methu creu'r ffeil PID '%s': %s
```

```
        <source>Unable to open %s for writing</source>
        <translation>Methu agor%sar gyfer ysgrifennu</translation>
    
YES  
The translation has formatting and spacing issues. The placeholder "%s" is concatenated directly to the preceding word "agor" without a space, which is incorrect. There should be a space before "%s" to match the source format specifier. Also, "Meth" is a typo or incorrect form; the correct Welsh (cy) word for "Unable" here is "Methu".  

Correct translation:  
Methu agor %s ar gyfer ysgrifennu
```

```
        <source>Unknown address type '%s'</source>
        <translation>Math cyfeiriad anhysbys '%s'</translation>
    
YES
The Welsh word "Math" means "type" but in Welsh, adjectives typically follow the noun, so the phrase should be "Math anhysbys o gyfeiriad '%s'" or better "Math anhysbys o gyfeiriad '%s'" to be more natural. Also, the word order in the provided translation is incorrect.

Correct translation:
Math anhysbys o gyfeiriad '%s'
```

```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>Reolau newydd anhysbys wedi'u gweithredu (versionbit%i)</translation>
    
YES  
There is a missing space between "versionbit" and "%i" in the translation. Also, "versionbit" is a technical term that should remain untranslated but separated properly by a space for readability and format consistency.

Correct translation:  
Reolau newydd anhysbys wedi'u gweithredu (versionbit %i)
```

```
        <source>Unrecognised option "%s" provided in -test=&lt;option&gt;.</source>
        <translation>Opcsiwn annasarnhaol "%s "a ddarparwyd yn -test=&lt;option&gt;.</translation>
    
YES  
The Welsh translation contains errors in the word choice and spacing. "Opcsiwn" is incorrect; the correct Welsh word for "option" is "Opsiwn". "annasarnhaol" is not a valid Welsh word; the correct term should be "anghywir" (incorrect/unrecognised). Additionally, there is an extra space before the closing quote after "%s ".

Correct translation:  
Opsiwn anghywir "%s" a ddarparwyd yn -test=&lt;option&gt;.
```

```
        <source>Unsupported global logging level %s=%s. Valid values: %s.</source>
        <translation>Llefel logio global nad yw'n cael ei gefnogi%s=%s.Gwerthoedd dilys:%s.</translation>
    
YES
There are spacing issues and slight grammatical awkwardness in the Welsh translation. Spaces are missing after punctuation marks, and the phrase should read more naturally.

Correct translation:
Llefel logio cenedlaethol nad yw’n cael ei gefnogi %s=%s. Gwerthoedd dilys: %s.
```

```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>nid yw acceptstalefeeestimates yn cael ei gefnogi ar%scadwyn.</translation>
    
YES  
There are spacing issues in the translation, and the technical term 'acceptstalefeeestimates' should not be translated. Also, a space is missing between "ar" and "%s" and between "%s" and "cadwyn."  

Correct translation:  
nid yw acceptstalefeeestimates yn cael ei gefnogi ar %s cadwyn.
```

```
        <source>Unsupported logging category %s=%s.</source>
        <translation>Categori logio nad yw'n cael ei gefnogi%s=%s.</translation>
    
YES  
There is a missing space before the format specifiers ("%s=%s") in the Welsh translation, which causes incorrect formatting. The phrase "Categori logio nad yw'n cael ei gefnogi" means "Logging category that is not supported," which is correct in meaning, but the specifiers must be properly spaced.

Correct translation:  
Categori logio nad yw'n cael ei gefnogi %s=%s.
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>Gwall: Ni allwyd ychwanegu tx gwylio'n unig%si waled gwylio'n unig</translation>
    
YES  
The translation is problematic because it is grammatically incorrect and missing spaces before the format specifier %s. The phrase "Nid allwyd ychwanegu" should be used instead of "Ni allwyd ychwanegu". Also, the phrase "gwylio'n unig" is repeated unnecessarily and should only appear once. Correct translation:  
Gwall: Nid allwyd ychwanegu tx gwylio'n unig %s i waled gwylio'n unig
```

```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>Sylw Agent Defnyddiwr (%s) yn cynnwys cymeriadau anghyson.</translation>
    
YES  
The Welsh word "anghyson" means "inconsistent" rather than "unsafe." The correct translation for "unsafe characters" in this context should be "cymeriadau anniogel."

Correct translation:  
Sylw Agent Defnyddiwr (%s) yn cynnwys cymeriadau anniogel.
```

```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Roedd angen ailosod y waled:%si gwblhau</translation>
    
YES  
There is a missing space after the colon and before the format specifier %s. Also, "ailosod" is more accurately "ailysgrifennu" for "rewritten" in this context. The correct version should have proper spacing and wording:

Correct translation:  
Roedd angen ailddysgu'r waled: ailgychwyn %s i gwblhau
```
</details>
