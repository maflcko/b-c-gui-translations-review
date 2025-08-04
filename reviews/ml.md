# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ml</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bml%5D%20low%20quality)


```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>കോമയാൽ വേർതിരിച്ച ഫയൽ (* .csv)</translation>
    
YES, The translation is incorrect and does not convey the meaning of "Comma separated file". The Malayalam translation is "Comma separated file (*.csv)", which is redundant and grammatically incorrect. The correct translation should simply be "കോമ വേർതിരിച്ച ഫയൽ" or "CSV ഫയൽ".

Correct Translation: കോമ വേർതിരിച്ച ഫയൽ
```

```
        <source>Sending addresses - %1</source>
        <translation>സ്വീകരിക്കുന്ന വിലാസങ്ങൾ - %1</translation>
    
YES - The translation is inaccurate. The source text "Sending addresses" translates to "അയയ്ക്കുന്ന വിലാസങ്ങൾ" in Malayalam, but the provided translation is "സ്വീകരിക്കുന്ന വിലാസങ്ങൾ" which means "Receiving addresses".
Correct translation: അയയ്ക്കുന്ന വിലാസങ്ങൾ - %1
```

```
        <source>Passphrase Dialog</source>
        <translation>രഹസ്യപദ  സൂചന </translation>
    
YES
The translation is inaccurate and doesn't convey the intended meaning of "Passphrase Dialog" in the context of Bitcoin. "രഹസ്യപദ സൂചന" translates to "passphrase hint," which is not the same as a dialog box for entering a passphrase.

Correct translation: പാസ്‌ഫ്രേസ് സംഭാഷണ പെട്ടി
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>വാലറ്റിൽ പുതിയ രഹസ്യവാക്യം നൽകുക.  പത്തോ അതിലധികമോ അക്ഷരങ്ങൾ  അല്ലെങ്കിൽ  എട്ടോ  കൂടുതലോ വാക്കുകൾ </translation>
    
YES: The translation is missing a crucial part of the original sentence, specifically the emphasis on "random characters" and the specific quantity of characters and words. Additionally, it lacks the proper formatting (bolding) present in the source text.

Here's the corrected translation:

വാലറ്റിൽ പുതിയ പാസ്‌ഫ്രേസ് നൽകുക. ദയവായി **പത്തോ അതിലധികമോ റാൻഡം അക്ഷരങ്ങൾ** അല്ലെങ്കിൽ **എട്ടോ അതിലധികമോ വാക്കുകൾ** ഉപയോഗിക്കുക.
```

```
        <source>Wallet encryption failed</source>
        <translation>വാലറ്റ് എന്ക്രിപ്റ് പരാജയപെട്ടു  .</translation>
    
YES: The translation contains extra spaces before the period and the word "എന്ക്രിപ്റ്" is not the correct Malayalam word for "encrypt".
Correct translation: വാലറ്റ് എൻക്രിപ്ഷൻ പരാജയപ്പെട്ടു.
```

```
        <source>The passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character. If this is successful, please set a new passphrase to avoid this issue in the future.</source>
        <translation>വാലറ്റ് ഡീക്രിപ്ഷനായി നൽകിയ പാസ്ഫ്രെയ്സ് തെറ്റാണ്. അതിൽ ഒരു ശൂന്യ പ്രതീകം അടങ്ങിയിരിക്കുന്നു (അതായത് - ഒരു സീറോ ബൈറ്റ്). 25.0-ന് മുമ്പ് ഈ സോഫ്‌റ്റ്‌വെയറിൻ്റെ ഒരു പതിപ്പ് ഉപയോഗിച്ചാണ് പാസ്‌ഫ്രെയ്‌സ് സജ്ജീകരിച്ചതെങ്കിൽ, ആദ്യത്തെ അസാധുവായ പ്രതീകം വരെയുള്ള - എന്നാൽ ഉൾപ്പെടുത്താതെയുള്ള പ്രതീകങ്ങൾ മാത്രം ഉപയോഗിച്ച് വീണ്ടും ശ്രമിക്കുക. ഇത് വിജയകരമാണെങ്കിൽ, ഭാവിയിൽ ഈ പ്രശ്‌നം ഒഴിവാക്കുന്നതിന് ദയവായി ഒരു പുതിയ പാസ്‌ഫ്രെയ്‌സ് സജ്ജീകരിക്കുക.</translation>
    
YES - The phrase "അസാധുവായ പ്രതീകം" (invalid character) is used instead of "null character" or "zero byte". The correct translation for "null character" or "zero byte" would be "ശൂന്യമായ പ്രതീകം" or "സീറോ ബൈറ്റ്".

NO
```

```
        <source>Internal error</source>
        <translation>ആന്തരിക പിശക്
 </translation>
    
YES: The translation is problematic because there is an extra space at the end of the translated text, which is not present in the source text.
Correct translation: ആന്തരിക പിശക്
```

```
        <source>Error: %1</source>
        <translation>തെറ്റ് : %1 </translation>
    
YES - The translation has an extra space before the format specifier.
തെറ്റ്: %1
```

```
        <source>Minimize</source>
        <translation> ഒപ്പം ചെറുതാക്കുക</translation>
    
YES - The translation "ഒപ്പം ചെറുതാക്കുക" is incorrect. "Minimize" in the context of Bitcoin would likely refer to reducing something, for example, minimizing fees or minimizing the size of a transaction. "ഒപ്പം ചെറുതാക്കുക" translates to "and make small," which is not the intended meaning of minimize. A more accurate translation for "minimize" in this context would be "കുറയ്ക്കുക" (kuraykkuka) or "ചെറിയതാക്കുക" (cheriyathakkuka).
Correct translation: കുറയ്ക്കുക
```

```
        <source>Backup Wallet…</source>
        <translation> ബാക്കപ്പ് വാലറ്റും…</translation>
    
YES - The translation is problematic because it adds an unnecessary word "വാലറ്റും" (valattum) which means "wallet also" or "and wallet". The source text "Backup Wallet…" simply means "Backup Wallet…". The correct translation should be "ബാക്കപ്പ് വാലറ്റ്…" (Backup valatt…).
NO
```

```
        <source>Sign message…</source>
        <translation>ഒപ്പിടുക, സന്ദേശം നൽകുക</translation>
    
YES: The translation is not accurate for the context provided. "Sign message…" in the context of Bitcoin implies signing a message with a private key associated with a Bitcoin address. The provided Malayalam translation "ഒപ്പിടുക, സന്ദേശം നൽകുക" which translates to "Sign, provide message" is too generic and doesn't capture the Bitcoin-specific action.

A more accurate translation would be:
<translation>സന്ദേശത്തിൽ ഒപ്പിടുക...</translation>
```

```
        <source>Load PSBT from file…</source>
        <translation> തുറന്ന് URL</translation>
    
YES
The translation is completely inaccurate and does not reflect the meaning of the source text. The source text "Load PSBT from file…" means to load a Partially Signed Bitcoin Transaction from a file. The translation "തുറന്ന് URL" means "Open URL", which is unrelated to the source text.

NO
The translation is problematic. The Malayalam translation "തുറന്ന് URL" (meaning "Open URL") is completely inaccurate and unrelated to the English source text "Load PSBT from file…". The correct translation should be something like "ഫയലിൽ നിന്ന് PSBT ലോഡ് ചെയ്യുക…" (Load PSBT from file...).
```

```
        <source>Connecting to peers…</source>
        <translation>സമപ്രായക്കാരുമായി ബന്ധിപ്പിക്കുന്നു...</translation>
    
UNK_LANG
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>പേയ്‌മെന്റുകൾ അഭ്യർത്ഥിക്കുക (QR കോഡുകളും ബിറ്റ്കോയിനും സൃഷ്ടിക്കുന്നു: URI- കൾ)</translation>
    
YES, the translation contains erroneous content. The phrase "ബിറ്റ്കോയിനും സൃഷ്ടിക്കുന്നു" translates to "creates bitcoin also", which is not an accurate translation of "generates QR codes and bitcoin: URIs". The corrected translation should reflect the generation of both QR codes and bitcoin: URIs.

NO
```

```
        <source>Receiving addresses</source>
        <translation>വിലാസങ്ങൾ അയയ്ക്കുന്നു</translation>
    
YES, The translation is incorrect. The source text "Receiving addresses" translates to "വിലാസങ്ങൾ സ്വീകരിക്കുന്നു" in Malayalam. The provided translation "വിലാസങ്ങൾ അയയ്ക്കുന്നു" means "Sending addresses".
Correct translation: വിലാസങ്ങൾ സ്വീകരിക്കുന്നു
```

```
        <source>Cannot create new wallet, the software was compiled without sqlite support (required for descriptor wallets)</source>
        <translation>പുതിയ വാലറ്റ് സൃഷ്ടിക്കാൻ കഴിയില്ല, സ്‌ക്ലൈറ്റ്
പിന്തുണയില്ലാതെ സോഫ്‌റ്റ്‌വെയർ കംപൈൽ ചെയ്‌തു (ഡിസ്‌ക്രിപ്‌റ്റർ വാലറ്റുകൾക്ക് ആവശ്യമാണ്)</translation>
    
YES, The translation contains an extra newline character between "സ്‌ക്ലൈറ്റ്" and "പിന്തുണയില്ലാതെ".
Correct translation: പുതിയ വാലറ്റ് സൃഷ്ടിക്കാൻ കഴിയില്ല, സ്‌ക്ലൈറ്റ് പിന്തുണയില്ലാതെ സോഫ്‌റ്റ്‌വെയർ കംപൈൽ ചെയ്‌തു (ഡിസ്‌ക്രിപ്‌റ്റർ വാലറ്റുകൾക്ക് ആവശ്യമാണ്)
```

```
        <source>Error: %1</source>
        <translation>തെറ്റ് : %1 </translation>
    
YES - The translation has an extra space before the format specifier.
തെറ്റ്: %1
```

```
        <source>Type: %1
</source>
        <translation>തരങ്ങൾ: %1
</translation>
    
YES
The translation uses the plural form "തരങ്ങൾ" (types) instead of the singular form "തരം" (type) as indicated by the source text "Type".
Correct translation: തരം: %1
```

```
        <source>Address: %1
</source>
        <translation>മേൽവിലാസം : %1 
</translation>
    
YES, The translation has an extra space before the colon and a space after the colon. The correct translation should be:
മേൽവിലാസം: %1
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Wallet &lt;b&gt;എൻ‌ക്രിപ്റ്റ് ചെയ്തു&lt;/b&gt;നിലവിൽ&lt;b&gt;അൺലോക്കുചെയ്‌തു&lt;/b&gt;</translation>
    
YES, The translation is grammatically incorrect and awkward. The words "encrypted" and "unlocked" are not translated properly.
Wallet &lt;b&gt;എൻ‌ക്രിപ്റ്റ് ചെയ്‌തതാണ്&lt;/b&gt; കൂടാതെ നിലവിൽ &lt;b&gt;അൺലോക്ക് ചെയ്‌തതുമാണ്&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Wallet &lt;b&gt;എൻ‌ക്രിപ്റ്റ് ചെയ്തു&lt;/b&gt;നിലവിൽ&lt;b&gt;പൂട്ടി&lt;/b&gt;</translation>
    
YES, The translation is problematic because it uses words in English instead of Malayalam.
Wallet <b > <b>എൻ‌ക്രിപ്റ്റ് ചെയ്തു</b></b> നിലവിൽ <b > <b>പൂട്ടി</b></b>
```

```
        <source>Bytes:</source>
        <translation>ബൈറ്റ്സ്:</translation>
    
YES, The translation is in Korean not Malayalam.
UNK_LANG
```

```
        <source>(un)select all</source>
        <translation>എല്ലാം തിരഞ്ഞു (എടുക്കുക /എടുക്കാതിരിക്കുക)</translation>
    
YES - The translation "എല്ലാം തിരഞ്ഞു (എടുക്കുക /എടുക്കാതിരിക്കുക)" is problematic. "തിരഞ്ഞു" means "searched" or "looked for", which is incorrect in this context. The intended meaning of "(un)select all" is to select or deselect all items. The correct translation should convey this selection action.

Correct translation: എല്ലാം തിരഞ്ഞെടുക്കുക / തിരഞ്ഞെടുക്കാതിരിക്കുക
```

```
        <source>Copy after fee</source>
        <translation>ശേഷമുള്ള ഫീ പകർത്തു</translation>
    
YES, The translation uses 'പകർത്തു' which means 'copy' in English, but it is used as a verb instead of a noun. The correct translation for 'Copy after fee' should be 'ഫീക്ക് ശേഷം പകർപ്പ്'.

The correct translation is:
<translation>ഫീക്ക് ശേഷം പകർപ്പ്</translation>
```

```
        <source>Copy bytes</source>
        <translation>ബൈറ്റ്സ് പകർത്തു</translation>
    
YES
The translation is incorrect. The source text is "Copy bytes", which means to copy the bytes. The Malayalam translation provided is "ബൈറ്റ്സ് പകർത്തു", which contains Korean characters and does not accurately convey the meaning. The correct translation should be "ബൈറ്റ്സ് പകർത്തു".

Correct translation: ബൈറ്റ്സ് പകർത്തു
```

```
        <source>Encrypt the wallet. The wallet will be encrypted with a passphrase of your choice.</source>
        <translation>എൻ‌ക്രിപ്റ്റ് വാലറ്റ്</translation>
    
YES. The translation is incomplete and does not convey the full meaning of the source text. It also lacks the second sentence of the source text entirely.

The correct translation should be:
"നിങ്ങളുടെ ഇഷ്ടത്തിനനുസരിച്ചുള്ള പാസ്‌വേഡ് ഉപയോഗിച്ച് വാലറ്റ് എൻ‌ക്രിപ്റ്റ് ചെയ്യുക."
```

```
        <source>Recent transactions</source>
        <translation>സമീപ കാല ഇടപാടുകൾ</translation>
    
UNK_LANG
```

```
        <source>Sent</source>
        <translation>അയക്കുക </translation>
    
YES. The translation is grammatically incorrect and does not convey the intended meaning of "Sent" in the context of Bitcoin transactions. The word "അയക്കുക" (ayikkuka) means "to send" in its infinitive form and is not appropriate here.

The correct translation for "Sent" in this context would be "അയച്ചു" (ayachu), which is the past tense of the verb "to send".

Correct translation:
<translation>അയച്ചു</translation>
```

```
        <source>Permissions</source>
        <translation>അനുവാത്തംനൽകൾ</translation>
    
YES. The translation for "Permissions" is incorrect. The correct translation is "അനുമതികൾ". The provided translation "അനുവാത്തംനൽകൾ" appears to be a nonsensical combination of letters.
NO.
```

```
        <source>Bytes:</source>
        <translation>ബൈറ്റ്സ്:</translation>
    
YES, The translation is in Korean not Malayalam.
UNK_LANG
```

```
        <source>Copy after fee</source>
        <translation>ശേഷമുള്ള ഫീ പകർത്തു</translation>
    
YES, The translation uses 'പകർത്തു' which means 'copy' in English, but it is used as a verb instead of a noun. The correct translation for 'Copy after fee' should be 'ഫീക്ക് ശേഷം പകർപ്പ്'.

The correct translation is:
<translation>ഫീക്ക് ശേഷം പകർപ്പ്</translation>
```

```
        <source>Copy bytes</source>
        <translation>ബൈറ്റ്സ് പകർത്തു</translation>
    
YES
The translation is incorrect. The source text is "Copy bytes", which means to copy the bytes. The Malayalam translation provided is "ബൈറ്റ്സ് പകർത്തു", which contains Korean characters and does not accurately convey the meaning. The correct translation should be "ബൈറ്റ്സ് പകർത്തു".

Correct translation: ബൈറ്റ്സ് പകർത്തു
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>കോമയാൽ വേർതിരിച്ച ഫയൽ (* .csv)</translation>
    
YES, The translation is incorrect and does not convey the meaning of "Comma separated file". The Malayalam translation is "Comma separated file (*.csv)", which is redundant and grammatically incorrect. The correct translation should simply be "കോമ വേർതിരിച്ച ഫയൽ" or "CSV ഫയൽ".

Correct Translation: കോമ വേർതിരിച്ച ഫയൽ
```

```
        <source>Invalid netmask specified in -whitelist: '%s'</source>
        <translation>-whitelist: '%s' ൽ രേഖപ്പെടുത്തിയിരിക്കുന്ന netmask തെറ്റാണ് </translation>
    
YES, The translation contains a grammatical error. The word "തെറ്റാണ്" should be placed after "netmask".

-whitelist: '%s' ൽ രേഖപ്പെടുത്തിയിരിക്കുന്ന netmask തെറ്റാണ്
```

```
        <source>Need to specify a port with -whitebind: '%s'</source>
        <translation>-whitebind: '%s' നൊടൊപ്പം ഒരു പോർട്ട് കൂടി നിർദ്ദേശിക്കേണ്ടതുണ്ട് </translation>
    
YES: The translation is grammatically incorrect and awkward. The word order is unnatural for Malayalam.

-whitebind: '%s' എന്നതിനോടൊപ്പം ഒരു പോർട്ട് നിർദ്ദേശിക്കേണ്ടതുണ്ട്
```

```
        <source>Section [%s] is not recognized.</source>
        <translation>Section [%s]  തിരിച്ചറിഞ്ഞില്ല.</translation>
    
YES: The translation has an extra space before the Malayalam word.
Section [%s] തിരിച്ചറിഞ്ഞില്ല.
```
</details>
