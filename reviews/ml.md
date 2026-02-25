# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bml%5D%20request)



<details><summary>ml</summary>


<!-- cache_translation_check_ml_5bd5edd2310f378b826f5d834f6a60821818cf2776f9be2f08b2f872b7b002c4 -->
```
        <source>&amp;New</source>
        <translation>പുതിയത്</translation>
    
ERR
The translation has omitted the '&' used for shortcut key indication, which should appear exactly once in the translation as well.

Correct translation:
&പുതിയത്
```

<!-- cache_translation_check_ml_bfe41f52f225631a684e2e00cc6156f44a7a0538a54b1be8c54b495c9ed5467f -->
```
        <source>C&amp;lose</source>
        <translation>അടയ്ക്കുക</translation>
    
ERR
The translation omits the '&' used for the shortcut key in the source. In Malayalam ('ml'), the shortcut key indicator (&) should also be included exactly once, regardless of its position. 

Correct translation:
&അടയ്ക്കുക or അടയ്ക്കു&ക (but commonly &അടയ്ക്കുക is used)
```

<!-- cache_translation_check_ml_4fbe8ccf47b53a67e6d8c3eb2f6c7d6bee6096e652ae3c013f4bfedec3165baa -->
```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>കോമയാൽ വേർതിരിച്ച ഫയൽ (* .csv)</translation>
    
ERR
There is a minor spelling error and spacing issue in the translation. "കോമയാൽ" should be "കോമയ്സയൂം", but the usual Malayalam translation is "കൊമയാൽ വേർതിരിച്ച മൂല്യങ്ങളുള്ള ഫയൽ". The parenthesis "* .csv" has an unnecessary space; it should be "(*.csv)".

Correct translation:
കൊമയാൽ വേർതിരിച്ച മൂല്യങ്ങളുള്ള ഫയൽ (*.csv)
```

<!-- cache_translation_check_ml_37e52440854166659a4efdc843a6693d94cfba81f140c9a86c446135f3f5ba6c -->
```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>ലേക്ക് വിലാസങ്ങൾ സേവ് ചെയ്യുന്നതിൽ ഒരു പിശകുണ്ടായിരുന്നു. ദയവായി വീണ്ടും ശ്രമിക്കുക.</translation>
    
ERR
The format specifier '%1' is missing from the translation. In Malayalam, the postposition '-ലേക്ക്' (to) should follow the placeholder.

Correct translation:
%1-ലേക്ക് വിലാസങ്ങൾ സേവ് ചെയ്യുന്നതിൽ ഒരു പിശകുണ്ടായിരുന്നു. ദയവായി വീണ്ടും ശ്രമിക്കുക.
```

<!-- cache_translation_check_ml_e667454020e768cd06fc3105a8ef34bb6f82401d08f6c556122c7852bddbf6f5 -->
```
        <source>Sending addresses - %1</source>
        <translation>സ്വീകരിക്കുന്ന വിലാസങ്ങൾ - %1</translation>
    
ERR
The translation is incorrect. The English text refers to "Sending addresses," but the Malayalam translation means "Receiving addresses." The correct translation should match the context of sending.

Correct translation:
അയക്കുന്ന വിലാസങ്ങൾ - %1
```

<!-- cache_translation_check_ml_d8440152d85de1df4367eb6cd555fe83b343869aeb15d5259cbc5381a7d11d89 -->
```
        <source>Passphrase Dialog</source>
        <translation>രഹസ്യപദ  സൂചന </translation>
    
ERR
There is an unnecessary extra space between "രഹസ്യപദ" and "സൂചന", and "Dialog" would be better rendered as "ഡയലോഗ്" or "സംവാദം". Also, "സൂചന" means "hint" or "cue", which is not accurate for "Dialog".

Correct translation:
രഹസ്യപദ ഡയലോഗ്
```

<!-- cache_translation_check_ml_269e2e45d0a3b0bc366d500d544c435b038ce36f7ce484f181d658b94b01df69 -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>വാലറ്റിൽ പുതിയ രഹസ്യവാക്യം നൽകുക.  പത്തോ അതിലധികമോ അക്ഷരങ്ങൾ  അല്ലെങ്കിൽ  എട്ടോ  കൂടുതലോ വാക്കുകൾ </translation>
    
ERR
The translation is incomplete and omits some important instructions such as the use of random characters and bold formatting. Also, there is a stray space before the full stop.

Correct translation:
വാലറ്റിന് പുതിയ പാസ്‌ഫ്രേസ് നൽകുക.&lt;br/&gt; ദയവായി &lt;b&gt;പത്തോ അതിലധികം ബഹിരാകാന്യമായ അക്കങ്ങൾ&lt;/b&gt; അല്ലെങ്കിൽ &lt;b&gt>എട്ടോ അതിലധികം വാക്കുകൾ&lt;/b&gt; റഹസ്യവാക്യമായി ഉപയോഗിക്കുക.
```

<!-- cache_translation_check_ml_dfc8589fcde8820433623a62e05fb08c6def0e430783f8b19a8ec5dff7ac6e7f -->
```
        <source>Wallet encryption failed</source>
        <translation>വാലറ്റ് എന്ക്രിപ്റ് പരാജയപെട്ടു  .</translation>
    
ERR
There is a spacing issue before the period, and the Malayalam word for 'encryption' can be better rendered.

Correct translation:
വാലറ്റ് എൻക്രിപ്ഷൻ പരാജയപ്പെട്ടു.
```

<!-- cache_translation_check_ml_c3ae51b56e4d1cab2880d889dcf76e92a8fcf3e40caa8af3eecd83c46a119b8a -->
```
        <source>Internal error</source>
        <translation>ആന്തരിക പിശക്
 </translation>
    
ERR
There is an unwanted trailing whitespace and an unnecessary newline at the end of the translation, which could cause formatting issues.

Correct translation:
ആന്തരിക പിശക്
```

<!-- cache_translation_check_ml_e0ac0fc0d6c2e0f4fa9b27ad491fc64b68de1a21edb6426fe8e456b293261392 -->
```
        <source>Error: %1</source>
        <translation>തെറ്റ് : %1 </translation>
    
ERR
There are whitespace formatting issues. There is an unnecessary space before the colon and an extra space after %1. Malayalam does not typically have a space before a colon in such contexts.

Correct translation:
തെറ്റ്: %1
```

<!-- cache_translation_check_ml_345f6572dc29805b49299cfaeba45242e39f0b0c1374beb4dea608a50b6d44f8 -->
```
        <source>E&amp;xit</source>
        <translation>പുറത്ത്</translation>
    
ERR
The translation is missing the shortcut key indicator (&). The English source uses '&' to indicate the shortcut. It must be preserved exactly once in the translation. Also, a more conventional translation for "Exit" in menu contexts is "പുറത്തുകടക്ക്" or "പുറത്ത് പോകുക".

Correct translation:
പുറത്ത് &പോക്കൂ
```

<!-- cache_translation_check_ml_6a0db1cd49ed775734a58fd0dc97acf156c36ec158a64d8e8918bb38c91e4619 -->
```
        <source>&amp;About %1</source>
        <translation>&amp; ഏകദേശം%1</translation>
    
ERR
There is a minor formatting issue: there should be a space between "ഏകദേശം" and "%1". Also, the translation for "About" as "ഏകദേശം" is not ideal; "ഏകദേശം" means "approximately" in Malayalam, whereas for "About" (in the context of a software "About" dialog), "കുറിച്ച്" is appropriate. The & is preserved correctly.

Correct translation:
&%1യെക്കുറിച്ച്
```

<!-- cache_translation_check_ml_0e2644c0fa75345660e2320209f15a2cb4a2d9997dd045387e68a861b88982d3 -->
```
        <source>&amp;Minimize</source>
        <translation> ഒപ്പം ചെറുതാക്കുക</translation>
    
ERR
The translation is missing the ampersand (&) which is needed to indicate the shortcut key. Also, "ഒപ്പം" means "and/with", which is not suitable for "Minimize". The translation should use the Malayalam equivalent for "Minimize".

Correct translation:
&amp;ചെറുതാക്കുക
```

<!-- cache_translation_check_ml_96911aaeda9d8298a3a4a654cce3a719c5a2ce633535b379e338a8be0877ef58 -->
```
        <source>&amp;Options…</source>
        <translation>ഇഷ്‌ടമുള്ളത്‌ തിരഞ്ഞെടുക്കല്‍</translation>
    
ERR
The translation does not appropriately convey the meaning of "&Options...". The Malayalam translation provided means "preferred selection", which is not the correct translation for "Options". Furthermore, the shortcut key indicator '&' is missing in the translation.

Correct translation:
&ഓപ്ഷനുകള്‍…
```

<!-- cache_translation_check_ml_6d85fecc45c3b78f9803cf8e73d113b3415a32b33266cc96b802e084e77c5313 -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation>വാലറ്റ് എൻക്രിപ്റ്റ് ചെയ്യുക…</translation>
    
ERR
The '&' symbol indicating the shortcut key from the source is missing in the Malayalam translation. It should be present exactly once in the translation, in an appropriate position.

Correct translation:
&വാലറ്റ് എൻക്രിപ്റ്റ് ചെയ്യുക…
```

<!-- cache_translation_check_ml_50f6eaf74610657ff6f61250bcc83b67eccc0422f82254af7d988c695e24e67a -->
```
        <source>&amp;Backup Wallet…</source>
        <translation> ബാക്കപ്പ് വാലറ്റും…</translation>
    
ERR
There is a leading space in the translation, which is a formatting issue. Additionally, the shortcut key indicator (&) is missing in the translation; it should be present exactly once. The Malayalam word "വാലറ്റും" translates to "and wallet", which is incorrect. The correct translation for "wallet" is "വാലറ്റ്". The translation should be:

Correct translation:
&ബാക്കപ്പ് വാലറ്റ്…
```

<!-- cache_translation_check_ml_ef68fe50e61ee92fa9a6865fba7527c300eb35a0d70014145dbbbf222b4ead7c -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>പാസ്ഫ്രെയ്സ് മാറ്റുക</translation>
    
ERR
The translation omits the '&' character, which is important for designating shortcut keys in menu items. It should appear exactly once in the translation.

Correct translation:
&പാസ്ഫ്രെയ്സ് മാറ്റുക
```

<!-- cache_translation_check_ml_cde229732fa180728f88bd715833c725faac4291c11c22a7eb633ebd890eb132 -->
```
        <source>Sign &amp;message…</source>
        <translation>ഒപ്പിടുക, സന്ദേശം നൽകുക</translation>
    
ERR
The translation does not properly convey the meaning of "Sign &message…". The correct Malayalam translation should preserve the shortcut key (&) and match the function, which is to sign a message (for example, digitally with a Bitcoin address), not to "provide a message". Additionally, the shortcut key (&) is missing in the translation.

Correct translation:
സന്ദേശം (&) ഒപ്പിടുക…
```

<!-- cache_translation_check_ml_c13f35122dc9d94a8afe3c02eaca3e676b52611f34bc3ccef5d9ebfd46582a43 -->
```
        <source>&amp;Verify message…</source>
        <translation>സന്ദേശം പരിശോധിക്കുക...</translation>
    
ERR
The translation is missing the '&' that signifies the shortcut key in the menu item. It should be present exactly once.

Correct translation:
&സന്ദേശം പരിശോധിക്കുക...
```

<!-- cache_translation_check_ml_aafee2c6dd65976fd17e67ef9b225d8c023eeb268ac9fad4ffab967886528a97 -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation> തുറന്ന് URL</translation>
    
ERR
The translation is incorrect and incomplete. The English text is "&Load PSBT from file…", but the Malayalam translation "തുറന്ന് URL" means "Open URL", which is unrelated and omits the PSBT, file, and the shortcut key (&).

Correct translation:
ഫയലിൽ നിന്ന് PSBT &ചുമതലക്കൊള്ളൂ…
```

<!-- cache_translation_check_ml_a2438e9b4b7bc51a43189f3b35956be1f9f17451f0c4b9aad01713d451f92653 -->
```
        <source>Connecting to peers…</source>
        <translation>നിങ്ങളെപ്പോലുള്ള ഉപയോക്താക്കളുമായി കണക്റ്റുചെയ്യുന്നു....</translation>
    
ERR
The translation changes the meaning: "നിങ്ങളെപ്പോലുള്ള ഉപയോക്താക്കളുമായി കണക്റ്റുചെയ്യുന്നു...." reads as "Connecting to users like you...." which is incorrect for Bitcoin peers (network nodes). It also uses four ASCII dots instead of a single ellipsis character and a colloquial transliteration of "connect".

Suggested correct translation:
പീർസുമായി ബന്ധം സ്ഥാപിക്കുന്നു…

(Alternatively: "പീയേഴ്സുമായി ബന്ധിപ്പിക്കുന്നു…")
```

<!-- cache_translation_check_ml_d7e50fb2db15be2c84b2368ff8a2cca61c2a5d6b6a126700f441c9f3ac531e63 -->
```
        <source>%1 behind</source>
        <translation>1 % പുറകിൽ</translation>
    
ERR
The format specifier '%1' has been modified to '1 %'. Format specifiers must be taken over exactly as they appear in the source text to ensure the software can correctly inject the variable.

Correct translation:
%1 പുറകിൽ
```

<!-- cache_translation_check_ml_b013b88a2fa08694affbac4d438afa76bc15a9fd17432c5b8cf7091e63192080 -->
```
        <source>&amp;Receiving addresses</source>
        <translation>&amp;വിലാസങ്ങൾ അയയ്ക്കുന്നു</translation>
    
ERR
The translation reverses the meaning. "Receiving addresses" refers to the addresses used to receive funds, but the Malayalam translation "&amp;വിലാസങ്ങൾ അയയ്ക്കുന്നു" means "Sending addresses" (literally "Addresses are sending" or "Sending addresses"). Also, "addresses" should be plural and "receiving" should be reflected.

Correct translation:
&﻿amp;സ്വീകരിക്കുന്ന വിലാസങ്ങൾ
```

<!-- cache_translation_check_ml_e0ac0fc0d6c2e0f4fa9b27ad491fc64b68de1a21edb6426fe8e456b293261392 -->
```
        <source>Error: %1</source>
        <translation>തെറ്റ് : %1 </translation>
    
ERR
There are whitespace formatting issues. There is an unnecessary space before the colon and an extra space after %1. Malayalam does not typically have a space before a colon in such contexts.

Correct translation:
തെറ്റ്: %1
```

<!-- cache_translation_check_ml_25b84513ece3ea2490e9f361719a96c136dbc09b861865145287e4e4612a4e1e -->
```
        <source>Type: %1
</source>
        <translation>തരങ്ങൾ: %1
</translation>
    
ERR
The word "തരങ്ങൾ" means "types" (plural), whereas the English source text "Type" is singular. Furthermore, "തരങ്ങൾ" is not generally used for "type" in technical contexts in Malayalam; "തരം" is more appropriate.

Correct translation:
തരം: %1
```

<!-- cache_translation_check_ml_24260de08c0e8d3a4b823459bc0ae23c396e3d8b33e9128c7bfb64331718e3b7 -->
```
        <source>Address: %1
</source>
        <translation>മേൽവിലാസം : %1 
</translation>
    
ERR  
There is an issue with extra spaces in the Malayalam translation:  
- There is an unnecessary space before the colon (should be "മേൽവിലാസം: %1" instead of "മേൽവിലാസം : %1").
- There is also an extra space after %1 before the line break.

Correct translation:
മേൽവിലാസം: %1
```

<!-- cache_translation_check_ml_d1b7d2663aa8d847df6bb683d5b716a75c3e380f98f53c0c368f333cea40b751 -->
```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Wallet &lt;b&gt;എൻ‌ക്രിപ്റ്റ് ചെയ്തു&lt;/b&gt;നിലവിൽ&lt;b&gt;അൺലോക്കുചെയ്‌തു&lt;/b&gt;</translation>
    
ERR
There are minor spacing issues in the Malayalam translation; there should be spaces around the bold tags to match the original source, improving readability and preserving the consistency with the English.

Correct translation:
Wallet &lt;b&gt;എൻ‌ക്രിപ്റ്റ് ചെയ്തു&lt;/b&gt; കൂടാതെ നിലവിൽ &lt;b&gt;അൺലോക്ക് ചെയ്തിരിക്കുന്നു&lt;/b&gt;

Alternatively, keeping the structure close to the source:
Wallet &lt;b&gt;എൻ‌ക്രിപ്റ്റ് ചെയ്തു&lt;/b&gt; ആയും നിലവിൽ &lt;b&gt;അൺലോക്ക് ചെയ്തിരിക്കുന്നു&lt;/b&gt;
```

<!-- cache_translation_check_ml_578ca98a16cd34d18dbeefc57d21814aca78509c70fd4611669c495e3b3a7005 -->
```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Wallet &lt;b&gt;എൻ‌ക്രിപ്റ്റ് ചെയ്തു&lt;/b&gt;നിലവിൽ&lt;b&gt;പൂട്ടി&lt;/b&gt;</translation>
    
ERR
The translation is understandable but has issues with spacing. There should be a space before and after the inline HTML tags to match the emphasis and phrasing of the English sentence. Also, the passive 'എൻ‌ക്രിപ്റ്റ് ചെയ്തു' is not as clear as 'എൻ‌ക്രിപ്റ്റ് ചെയ്തിട്ടുണ്ട്' for "is encrypted". Similarly, 'പൂട്ടി' would be clearer as 'പൂട്ടിയതാണ്' or 'പൂട്ടിയിരിക്കുന്നു'.

Correct translation:
Wallet &lt;b&gt;എൻ‌ക്രിപ്റ്റ് ചെയ്തിട്ടുണ്ട്&lt;/b&gt; കൂടാതെ നിലവിൽ &lt;b&gt;പൂട്ടിയിരിക്കുന്നു&lt;/b&gt;
```

<!-- cache_translation_check_ml_0aedb38829e54d3b1c31baaeda944010f8bcb2a1133e811b86f9eb8215fb5ee4 -->
```
        <source>(un)select all</source>
        <translation>എല്ലാം തിരഞ്ഞു (എടുക്കുക /എടുക്കാതിരിക്കുക)</translation>
    
ERR
The translation is slightly awkward and wordy. "(un)select all" in Malayalam for a UI context is better as "എല്ലാം തിരഞ്ഞെടുക്കുക/തിരഞ്ഞെടുക്കാതിരിക്കുക" or "എല്ലാം തെരഞ്ഞെടുക്കുക" depending on context. The current translation "എല്ലാം തിരഞ്ഞു (എടുക്കുക /എടുക്കാതിരിക്കുക)" is confusing and uses an odd construction by combining "തിരഞ്ഞു" (past tense of "select") with explanatory text in brackets.

Correct translation:
എല്ലാം തിരഞ്ഞെടുക്കുക/തിരഞ്ഞെടുക്കാതിരിക്കുക
```

<!-- cache_translation_check_ml_0d51c8f8db54c095fc52f369627ddb39e850566224e141bac08b0f52c5410c63 -->
```
        <source>Encrypt the wallet. The wallet will be encrypted with a passphrase of your choice.</source>
        <translation>എൻ‌ക്രിപ്റ്റ് വാലറ്റ്</translation>
    
ERR
The translation is incomplete. The English source says, "Encrypt the wallet. The wallet will be encrypted with a passphrase of your choice." whereas the Malayalam translation only says "എൻ‌ക്രിപ്റ്റ് വാലറ്റ്" ("Encrypt wallet").

Correct translation:
വാലറ്റ് എൻ‌ക്രിപ്റ്റ് ചെയ്യുക. നിങ്ങളുടെ തെരഞ്ഞെടുപ്പായ പാസ്ഫ്രേസുമായി വാലറ്റ് എൻ‌ക്രിപ്റ്റ് ചെയ്യപ്പെടുന്നതായിരിക്കും.
```

<!-- cache_translation_check_ml_61d568f5d588432db01e066d7ee646b8bbbce872fa67b6f180f17a11a8d37871 -->
```
        <source>W&amp;allet</source>
        <translation>വാലറ്റ്</translation>
    
ERR
The translation does not include the '&' (shortcut key indicator) anywhere, which must be present exactly once as in the source. 

Correct translation:
&വാലറ്റ്

or

വാ&ലറ്റ്

(Any position is acceptable, as long as there is exactly one '&'.)
```

<!-- cache_translation_check_ml_dac6f6e3822d352dd2939b5ca72161106b444d6b5bcd5106525676de1bca4009 -->
```
        <source>&amp;Save Image…</source>
        <translation>ചിത്രം സൂക്ഷിക്കുക</translation>
    
ERR
The translation 'ചിത്രം സൂക്ഷിക്കുക' accurately means 'Save Image', but it is missing the '&' which denotes the shortcut key in the original English source. The '&' should appear exactly once in the translation, at an appropriate location in the Malayalam text.

Correct translation:
&amp;ചിത്രം സൂക്ഷിക്കുക

Alternatively, you can place the '&' before any letter in the Malayalam translation to indicate the shortcut, for example:
ചിത്രം &amp;സൂക്ഷിക്കുക
```

<!-- cache_translation_check_ml_960ad8c17dfbdced2bcf27674e95dcbc2f3f4f4fb9171f94f3eed49153020413 -->
```
        <source>&amp;Copy Image</source>
        <translation>ചിത്രം പകര്‍ത്തുക</translation>
    
ERR
The translation omits the '&' which is used to indicate the shortcut key in the original English. There should be exactly one '&' in the translation.

Correct translation:
&ചിത്രം പകര്‍ത്തുക
```

<!-- cache_translation_check_ml_1c04b2e4d1b0c385aeb607ca6e044af92f55558f92b1552a2560946bbf25b4b2 -->
```
        <source>&amp;Information</source>
        <translation>അറിയിപ്പ്</translation>
    
ERR
The translation omits the '&' which is required for the shortcut key and should be present exactly once, as in the source.

Correct translation:
&അറിയിപ്പ്
```

<!-- cache_translation_check_ml_952d14881d140589d79212c3db7552a12358cca2d2920656bfc62af3f5837d0c -->
```
        <source>Sent</source>
        <translation>അയക്കുക </translation>
    
ERR
The translation "അയക്കുക" is the infinitive form "to send", which is incorrect for "Sent" (the past participle). The correct translation should be "അയച്ചു" (means "Sent").

Correct translation:
അയച്ചു
```

<!-- cache_translation_check_ml_dafe76d98c813aacee4417208f1dcf443a527d9c47b39f713e5456e7662ccfa2 -->
```
        <source>Permissions</source>
        <translation>അനുവാത്തംനൽകൾ</translation>
    
ERR  
The translation "അനുവാത്തംനൽകൾ" is incorrect and also contains a spelling mistake. The correct Malayalam translation for "Permissions" is "അനുമതികൾ".

Correct translation:
അനുമതികൾ
```

<!-- cache_translation_check_ml_dac6f6e3822d352dd2939b5ca72161106b444d6b5bcd5106525676de1bca4009 -->
```
        <source>&amp;Save Image…</source>
        <translation>ചിത്രം സൂക്ഷിക്കുക</translation>
    
ERR
The translation 'ചിത്രം സൂക്ഷിക്കുക' accurately means 'Save Image', but it is missing the '&' which denotes the shortcut key in the original English source. The '&' should appear exactly once in the translation, at an appropriate location in the Malayalam text.

Correct translation:
&amp;ചിത്രം സൂക്ഷിക്കുക

Alternatively, you can place the '&' before any letter in the Malayalam translation to indicate the shortcut, for example:
ചിത്രം &amp;സൂക്ഷിക്കുക
```

<!-- cache_translation_check_ml_4fbe8ccf47b53a67e6d8c3eb2f6c7d6bee6096e652ae3c013f4bfedec3165baa -->
```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>കോമയാൽ വേർതിരിച്ച ഫയൽ (* .csv)</translation>
    
ERR
There is a minor spelling error and spacing issue in the translation. "കോമയാൽ" should be "കോമയ്സയൂം", but the usual Malayalam translation is "കൊമയാൽ വേർതിരിച്ച മൂല്യങ്ങളുള്ള ഫയൽ". The parenthesis "* .csv" has an unnecessary space; it should be "(*.csv)".

Correct translation:
കൊമയാൽ വേർതിരിച്ച മൂല്യങ്ങളുള്ള ഫയൽ (*.csv)
```
</details>

Number of issues: 38.
