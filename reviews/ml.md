# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ml</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bml%5D%20low%20quality)


```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>കോമയാൽ വേർതിരിച്ച ഫയൽ (* .csv)</translation>
    
YES  
There is an incorrect whitespace in the translation: there is an unwanted space between the asterisk (*) and the file extension (.csv), written as "* .csv" instead of "*.csv". Also, the phrase "കോമയാൽ വേർതിരിച്ച ഫയൽ" is a reasonable translation for "Comma separated file", but it can be slightly improved for clarity by explicitly including "CSV ഫയൽ" to align with common usage.

Correct translation:  
കോമയാൽ വേർതിരിച്ച ഫയൽ (*.csv)
```

```
        <source>Sending addresses - %1</source>
        <translation>സ്വീകരിക്കുന്ന വിലാസങ്ങൾ - %1</translation>
    
YES  
The English source "Sending addresses - %1" is translated as "സ്വീകരിക്കുന്ന വിലാസങ്ങൾ - %1" which means "Receiving addresses - %1" in Malayalam. The verb "സ്വീകരിക്കുന്ന" means "receiving," not "sending." This results in an incorrect translation of the key term "Sending."  

Correct translation:  
**അയയ്ക്കുന്ന വിലാസങ്ങൾ - %1**
```

```
        <source>Passphrase Dialog</source>
        <translation>രഹസ്യപദ  സൂചന </translation>
    
YES  
The Malayalam translation "രഹസ്യപദ  സൂചന" is not accurate for "Passphrase Dialog." It translates to "Passphrase Hint" or "Passphrase Suggestion," which is different from a dialog or prompt window. Also, there is an extra space between "പദ" and "സൂചന."  

Correct translation:  
"പാസ്ഫ്രേസ് ഡയലോഗ്"  
or more formally,  
"പാസ്ഫ്രേസ് ഡയലോഗ് বাক്സ്" (Passphrase Dialog Box)  

Since "Dialog" is a technical term often transliterated, the first is acceptable and correct.
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>വാലറ്റിൽ പുതിയ രഹസ്യവാക്യം നൽകുക.  പത്തോ അതിലധികമോ അക്ഷരങ്ങൾ  അല്ലെങ്കിൽ  എട്ടോ  കൂടുതലോ വാക്കുകൾ </translation>
    
YES  
The translation is incomplete and partially inaccurate. It does not properly convey the full original meaning, especially the use of formatting tags (&lt;br/&gt;, &lt;b&gt;) and the instructions about the passphrase requirements are not fully or correctly translated. Also, spacing issues exist (extra spaces).  

Correct translation:  
വാലറ്റിനുള്ള പുതിയ രഹസ്യവാക്യം നൽകുക.&lt;br/&gt;&lt;br/&gt;ദയവായി &lt;b&gt;പത്ത് അല്ലെങ്കിൽ അതിലധികം യാദൃച്ഛിക അക്ഷരങ്ങൾ&lt;/b&gt; ഉപയോഗിക്കുക, അല്ലെങ്കിൽ &lt;b&gt;എട്ട് അല്ലെങ്കിൽ അതിൽ കൂടുതലായ പദങ്ങൾ&lt;/b&gt; ഉപയോഗിക്കുക.
```

```
        <source>Wallet encryption failed</source>
        <translation>വാലറ്റ് എന്ക്രിപ്റ് പരാജയപെട്ടു  .</translation>
    
YES  
The Malayalam translation has a spelling error and an unnecessary space before the punctuation. The word "എന്ക്രിപ്റ്" should be "എൻ‌ക്രിപ്ഷൻ" or a correct transliteration of "encryption". Also, there is an extra space before the period.

Correct translation:  
വാലറ്റ് എൻ‌ക്രിപ്ഷൻ പരാജയപ്പെട്ടു.
```

```
        <source>Internal error</source>
        <translation>ആന്തരിക പിശക്
 </translation>
    
YES  
The translation contains trailing whitespace (a space or non-breaking space character) after the word "പിശക്", which should be removed for proper formatting.

Correct translation:  
ആന്തരിക പിശക്
```

```
        <source>Error: %1</source>
        <translation>തെറ്റ് : %1 </translation>
    
YES  
There is an extra space before and after the colon in the translation, which is inconsistent with the source format. The colon should have no space before it and exactly one space after it, matching the source style.  

Correct translation:  
തെറ്റ്: %1
```

```
        <source>Minimize</source>
        <translation> ഒപ്പം ചെറുതാക്കുക</translation>
    
YES  
The Malayalam translation contains an unnecessary leading space and the word "ഒപ്പം" means "together/with," which is incorrect in this context. The correct translation for "Minimize" in Malayalam is simply "ചെറുതാക്കുക" without any prefix.

Correct translation:  
<translation>ചെറുതാക്കുക</translation>
```

```
        <source>Backup Wallet…</source>
        <translation> ബാക്കപ്പ് വാലറ്റും…</translation>
    
YES  
The Malayalam translation contains an extra and incorrect suffix "ഉം" attached to "വാലറ്റ്" which changes the meaning and is unnatural in this context. Also, there is an extra leading space before the text. The ellipsis character (…) is correctly used.  

Correct translation:  
ബാക്കപ്പ് വാലറ്റ്…
```

```
        <source>Sign message…</source>
        <translation>ഒപ്പിടുക, സന്ദേശം നൽകുക</translation>
    
YES  
The translation "ഒപ്പിടുക, സന്ദേശം നൽകുക" means "Sign, give message," which is inaccurate and unnecessarily combines two verbs separated by a comma. The English source "Sign message…" refers to the action of digitally signing a message, typically used in Bitcoin or other cryptographic contexts. The correct Malayalam translation for "Sign message…" should be concise and reflect the imperative/action, best rendered as:  

"സന്ദേശത്തിന് ഒപ്പ് ഇടുക…"
```

```
        <source>Load PSBT from file…</source>
        <translation> തുറന്ന് URL</translation>
    
YES  
The translation "തുറന്ന് URL" means "open URL," which is incorrect and unrelated to the source text "Load PSBT from file…". It neither conveys loading a PSBT (Partially Signed Bitcoin Transaction) nor mentions loading from a file. Also, there is an extra leading space.

Correct translation:  
ഫയലിൽ നിന്ന് PSBT ലോഡ് ചെയ്യുക...
```

```
        <source>Receiving addresses</source>
        <translation>വിലാസങ്ങൾ അയയ്ക്കുന്നു</translation>
    
YES  
The translation "വിലാസങ്ങൾ അയയ്ക്കുന്നു" means "Sending addresses" rather than "Receiving addresses." The correct Malayalam translation for "Receiving addresses" would be:  
"സ്വീകരിക്കുന്ന വിലാസങ്ങൾ"
```

```
        <source>Cannot create new wallet, the software was compiled without sqlite support (required for descriptor wallets)</source>
        <translation>പുതിയ വാലറ്റ് സൃഷ്ടിക്കാൻ കഴിയില്ല, സ്‌ക്ലൈറ്റ്
പിന്തുണയില്ലാതെ സോഫ്‌റ്റ്‌വെയർ കംപൈൽ ചെയ്‌തു (ഡിസ്‌ക്രിപ്‌റ്റർ വാലറ്റുകൾക്ക് ആവശ്യമാണ്)</translation>
    
YES  
The Malayalam translation has a line break in the middle of "സ്‌ക്ലൈറ്റ്\nപിന്തുണയില്ലാതെ", which is incorrect and disrupts readability. The word "sqlite" is transliterated as "സ്‌ക്ലൈറ്റ്" which is acceptable, but the spacing and line break issue should be fixed. Also, "descriptor" is incorrectly transliterated as "ഡിസ്‌ക്രിപ്‌റ്റർ" instead of "ഡിസ്ക്രിപ്റ്റർ" (closer to English pronunciation).  

Correct translation:  
പുതിയ വാലറ്റ് സൃഷ്ടിക്കാൻ കഴിയില്ല, sqlite പിന്തുണയില്ലാതെ സോഫ്റ്റ്‌വെയർ കംപൈൽ ചെയ്തിരിക്കുന്നു (ഡിസ്ക്രിപ്റ്റർ വാലറ്റുകൾക്ക് ആവശ്യമാണ്)
```

```
        <source>Error: %1</source>
        <translation>തെറ്റ് : %1 </translation>
    
YES  
There is an extra space before and after the colon in the translation, which is inconsistent with the source format. The colon should have no space before it and exactly one space after it, matching the source style.  

Correct translation:  
തെറ്റ്: %1
```

```
        <source>Type: %1
</source>
        <translation>തരങ്ങൾ: %1
</translation>
    
YES  
The English source "Type: %1" translates to "തരം: %1" in Malayalam, where "തരം" means "Type" (singular). The provided translation uses "തരങ്ങൾ" which is plural ("Types"), which changes the meaning. Also, ensure the colon matches and spacing is correct.

Correct translation:  
തരം: %1
```

```
        <source>Address: %1
</source>
        <translation>മേൽവിലാസം : %1 
</translation>
    
YES
There is an extra space before and after the colon in the translation, which is inconsistent with typical Malayalam punctuation conventions and the source formatting. Also, there is an unnecessary trailing space after %1 and before the newline.

Correct translation:
മേൽവിലാസം: %1\n
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Wallet &lt;b&gt;എൻ‌ക്രിപ്റ്റ് ചെയ്തു&lt;/b&gt;നിലവിൽ&lt;b&gt;അൺലോക്കുചെയ്‌തു&lt;/b&gt;</translation>
    
YES
The Malayalam translation merges words without proper spacing and has inconsistent spacing around the HTML tags. It also leaves the English word "Wallet" untranslated, which may be acceptable depending on style, but ideally it should be localized. Correct spacing is required after the HTML tags and between words.

Correct translation:
&lt;b&gt;വാലറ്റ്&lt;/b&gt; &lt;b&gt;എൻ‌ക്രിപ്റ്റ് ചെയ്തു&lt;/b&gt;  നിലവിൽ &lt;b&gt;അൺലോക്കുചെയ്‌തു&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Wallet &lt;b&gt;എൻ‌ക്രിപ്റ്റ് ചെയ്തു&lt;/b&gt;നിലവിൽ&lt;b&gt;പൂട്ടി&lt;/b&gt;</translation>
    
YES  
The Malayalam translation is problematic due to missing spaces around the HTML tags and slight unnatural phrasing. The tags &lt;b&gt; and &lt;/b&gt; should be separated properly from the surrounding words to maintain readability and correct formatting. Also, a more natural phrasing for "encrypted" is "പാതിവര വാങ്ങിയത്" (though encryption is commonly called എൻ‌ക്രിപ്റ്റ് ചെയ്യപ്പെട്ട) and "currently locked" can be better rendered as "ഇപ്പോൾ കണക്കുകൂട്ടിയാണ് പൂട്ടിയിട്ടുള്ളത്" but keeping it simple is fine if spacing is fixed.

Corrected translation with proper spacing and better clarity:  
Wallet &lt;b&gt;എൻ‌ക്രിപ്റ്റ് ചെയ്യപ്പെട്ട&lt;/b&gt;യും നിലവിൽ &lt;b&gt;പൂട്ടിയ&lt;/b&gt;വഴിലാണ്

Or more simply:  
Wallet &lt;b&gt;എൻ‌ക്രിപ്റ്റ് ചെയ്തു&lt;/b&gt;യും നിലവിൽ &lt;b&gt;പൂട്ടിയ&lt;/b&gt;വഴിയാണ്

(The key correction is adding spaces between the elements and using "ചെയ്തു" + "യും" for 'and currently')
```

```
        <source>(un)select all</source>
        <translation>എല്ലാം തിരഞ്ഞു (എടുക്കുക /എടുക്കാതിരിക്കുക)</translation>
    
YES  
The translation is somewhat unclear and does not convey the meaning of "(un)select all" accurately. The phrase "(un)select all" means to either select all items or deselect all items, typically in a toggle action. The Malayalam translation given, "എല്ലാം തിരഞ്ഞു (എടുക്കുക /എടുക്കാതിരിക്കുക)", translates roughly as "Select all (take / not take)", which is confusing and awkward.

A better, clearer translation would be:

എല്ലാം തിരഞ്ഞെടുക്കുക/തിരഞ്ഞെടുക്കാതിരിക്കുക

This conveys "select all / deselect all" clearly and concisely, suitable for UI contexts.

Correct translation:  
എല്ലാം തിരഞ്ഞെടുക്കുക/തിരഞ്ഞെടുക്കാതിരിക്കുക
```

```
        <source>Encrypt the wallet. The wallet will be encrypted with a passphrase of your choice.</source>
        <translation>എൻ‌ക്രിപ്റ്റ് വാലറ്റ്</translation>
    
YES  
The translation "എൻ‌ക്രിപ്റ്റ് വാലറ്റ്" ("Encrypt wallet") is incomplete and does not convey the full meaning of the source text. The source mentions that the wallet will be encrypted with a passphrase of the user's choice, which is missing in the translation.

Correct translation:  
വാലറ്റ് എൻ‌ക്രിപ്റ്റ് ചെയ്യുക. വാലറ്റ് നിങ്ങൾ തിരഞ്ഞെടുക്കുന്ന പാസ്‌ഫ്രേസിനാൽ എൻ‌ക്രിപ്റ്റ് ചെയ്യും.
```

```
        <source>Sent</source>
        <translation>അയക്കുക </translation>
    
YES  
The translation "അയക്കുക" means "to send" (an imperative or infinitive verb form), whereas the English source "Sent" is the past tense or past participle, typically used as an adjective or status indicator. A more accurate Malayalam translation for "Sent" (as in a status label) would be "അയച്ചത്" or "അയച്ചു". Also, there's an extra trailing space after the Malayalam word which should be removed.

Correct translation:  
അയച്ചത്
```

```
        <source>Permissions</source>
        <translation>അനുവാത്തംനൽകൾ</translation>
    
YES  
The provided Malayalam translation "അനുവാത്തംനൽകൾ" is incorrect and unnatural. The correct word for "Permissions" in Malayalam is "അനുമതികൾ".  

Correct translation:  
അനുമതികൾ
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>കോമയാൽ വേർതിരിച്ച ഫയൽ (* .csv)</translation>
    
YES  
There is an incorrect whitespace in the translation: there is an unwanted space between the asterisk (*) and the file extension (.csv), written as "* .csv" instead of "*.csv". Also, the phrase "കോമയാൽ വേർതിരിച്ച ഫയൽ" is a reasonable translation for "Comma separated file", but it can be slightly improved for clarity by explicitly including "CSV ഫയൽ" to align with common usage.

Correct translation:  
കോമയാൽ വേർതിരിച്ച ഫയൽ (*.csv)
```

```
        <source>Section [%s] is not recognized.</source>
        <translation>Section [%s]  തിരിച്ചറിഞ്ഞില്ല.</translation>
    
YES  
There is an extra space after the closing bracket [%s] which is not present in the source text. Also, the word "Section" is untranslated and can be translated to Malayalam as "അദ്ധ്യായം" or "വിഭാഗം" depending on context. Given the context is Bitcoin configuration or section headings, "വിഭാഗം" (meaning "section") is appropriate.

Correct translation:  
<translation>വിഭാഗം [%s] തിരിച്ചറിഞ്ഞില്ല.</translation>
```
</details>
