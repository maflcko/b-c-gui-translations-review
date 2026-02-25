# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>hi</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bhi%5D%20request)


<!-- cache_translation_check_hi_de52c986d77bb8e5e465245ef81cc19e38c931d538ba0ece1b78e6e746ea2dcd -->
```
        <source>&amp;New</source>
        <translation>नया </translation>
    
ERR
The '&' indicating the shortcut key from the source is missing in the translation, and an extra space exists after "नया".

Correct translation:
&नया
```

<!-- cache_translation_check_hi_e9f7409228e3561fa1746eba8217718aa66ca5afb920f710b32c2793fa78ecd6 -->
```
        <source>&amp;Copy</source>
        <translation>कॉपी</translation>
    
ERR
The shortcut key indicator (&) is missing in the translation. The '&' should appear exactly once to indicate the shortcut key.

Correct translation:
&कॉपी
```

<!-- cache_translation_check_hi_f5c73f0d2a35b1a960f88e8e19c24b33e31593158559293ff32405753018f7be -->
```
        <source>C&amp;lose</source>
        <translation>बंद करें</translation>
    
ERR
The translation omits the '&' shortcut key indicator that exists in the source ("C&amp;lose"), which should appear exactly once in the translation as well. 

Correct translation:
&बंद करें

(Alternatively, it can be placed anywhere in the translated string, e.g., "बं&द करें", as long as it appears once.)
```

<!-- cache_translation_check_hi_49ad723bbe3b5e9e3b65ceea52ad65d514d9e3df3ce0b50cfac035c1a8d852f8 -->
```
        <source>&amp;Export</source>
        <translation>निर्यात</translation>
    
ERR
The translation for '&Export' misses the '&' character, which is used for shortcut keys. The '&' should be present exactly once in the Hindi translation, at any position.

Correct translation:
&निर्यात
or
निर्यात (&amp;E)
or
निर्यात (&amp;N)

However, the most common and direct is:
&निर्यात
```

<!-- cache_translation_check_hi_41890e4c9e929f4c49ad85a2f488a7796faa89ab071ff2a27909d9ed4a7cf519 -->
```
        <source>&amp;Delete</source>
        <translation>डिलीट करें</translation>
    
ERR
The translation omits the '&' which is used in the source to indicate the shortcut key. It must appear exactly once in the translation. 

Correct translation:
&डिलीट करें
```

<!-- cache_translation_check_hi_3d4152702f01a6fd62f6ce35add806d17a6e5a60726f87e31233e3956af26f81 -->
```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>पता सूची को %1यहां सहेजने का प्रयास करते समय एक त्रुटि हुई . कृपया पुन: प्रयास करें।</translation>
    
ERR
There are spacing and punctuation issues. The phrase "%1यहां" incorrectly combines the format specifier "%1" with "यहां" (here), which is neither present in the source nor required. There should be a space between "%1" and the rest of the text, and "यहां" should not be present.

Correct translation:
पता सूची को %1 में सहेजने का प्रयास करते समय एक त्रुटि हुई। कृपया पुनः प्रयास करें।
```

<!-- cache_translation_check_hi_596ff767fbc7f8215cc8436583d3160db794a234656d41fb13098a6c715f1e25 -->
```
        <source>Receiving addresses - %1</source>
        <translation> रिसीवर के पते</translation>
    
ERR
The translation is problematic for two reasons:
1. The format specifier `%1` is missing from the translation.
2. There is an unnecessary leading space at the beginning of the translation.

Correct translation:
प्राप्त करने वाले पते - %1
```

<!-- cache_translation_check_hi_7abea39230fa69741ecb5531b853760dd661ee0542017cee519506d4b6d0f158 -->
```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>चेतावनी: यदि आप अपना वॉलेट एन्क्रिप्ट करते हैं और अपना पासफ़्रेज़ खो देते हैं, तो आपअपने सभी बिटकॉइन &lt;b&gt; खो देंगे&lt;/b&gt; !</translation>
    
ERR
There is a formatting error: "आपअपने" should be "आप अपने" (missing space). Also, the placement of the bold tags differs from the English sentence, which emphasizes "LOSE ALL OF YOUR BITCOINS". The Hindi translation has the bold tag only around "खो देंगे", not "अपने सभी बिटकॉइन खो देंगे" as in the original. The exclamation mark and spacing also show a stray space.

Correct translation:
चेतावनी: यदि आप अपना वॉलेट एन्क्रिप्ट करते हैं और अपना पासफ़्रेज़ खो देते हैं, तो आप &lt;b&gt;अपने सभी बिटकॉइन खो देंगे&lt;/b&gt;!
```

<!-- cache_translation_check_hi_21555da73b50bd83c86e532b654cca1bd3aa48c84af061b61896125022187f49 -->
```
        <source>Banned Until</source>
        <translation>तक प्रतिबंधित</translation>
    
ERR
The Hindi translation reverses the word order, resulting in an incomplete and unnatural phrase. "तक प्रतिबंधित" means "banned until", but leaves out the subject or context and is not commonly used standalone. A more accurate and natural translation would be:

Correct translation:
प्रतिबंधित होने की अवधि
or 
प्रतिबंधित तिथि (if referring to the date)
or
प्रतिबंधित किया गया समय (if referring to the banned-until time)
```

<!-- cache_translation_check_hi_b0754327607fb567272250407a1db8d30aad3429a57e687fc9b1a91292f9f0a2 -->
```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>एक आंतरिक त्रुटि हुई। %1सुरक्षित रूप से जारी रखने का प्रयास करेगा। यह एक अप्रत्याशित बग है जिसे नीचे वर्णित के रूप में रिपोर्ट किया जा सकता है।</translation>
    
ERR
There is a missing space after "%1", resulting in "%1सुरक्षित" instead of "%1 सुरक्षित".

Correct translation:
एक आंतरिक त्रुटि हुई। %1 सुरक्षित रूप से जारी रखने का प्रयास करेगा। यह एक अप्रत्याशित बग है जिसे नीचे वर्णित के रूप में रिपोर्ट किया जा सकता है।
```

<!-- cache_translation_check_hi_c1211d78314b63b9d7fe1e5339fe67ede5772c403aae92bf13f24bef8eef0011 -->
```
        <source>I2P</source>
        <comment>network name</comment>
        <extracomment>Name of I2P network in peer info</extracomment>
        <translation>आई 2 पी</translation>
    
ERR
The translation inserts Devanagari letters and extra spaces ("आई 2 पी") for the network name. Network names should be left as-is (or, if transliterated, without added spaces). Also ensure no stray spaces around the "2".

Correct translation:
I2P
```

<!-- cache_translation_check_hi_850ee0d0a600ae558885d3fffb0f043db2f914806925319cc89146dd4b1523bc -->
```
        <source>&amp;Overview</source>
        <translation>&amp;ओवरवीउ</translation>
    
ERR
The word "ओवरवीउ" is not a standard Hindi word and is an incorrect transliteration of "Overview." The correct transliteration in Hindi is "ओवरव्यू". Additionally, ensure the ampersand (&) is present exactly once for shortcut functionality, which this translation does.

Correct translation:
&ओवरव्यू
```

<!-- cache_translation_check_hi_69df3381aae0eaab237bd2a154649285e9188718ad5d50e042183806df538ae7 -->
```
        <source>E&amp;xit</source>
        <translation>&amp;एक्ज़िट</translation>
    
ERR
The translation "&एक्ज़िट" uses a transliteration of "Exit", which is unnecessary in Hindi. The proper word is "बाहर जाएँ" or "निकास". Also, the ampersand (&) for the shortcut exists, which is correct, but the Hindi translation should use native terms rather than English transliteration, unless commonly used (which is not the case here).

Correct translation:
&बाहर जाएँ
```

<!-- cache_translation_check_hi_704e40c758a9a42ba62f7b2d22eb480a1f82a295910154981ab1dadf2ba56c30 -->
```
        <source>Quit application</source>
        <translation> एप्लिकेशन छोड़ें |</translation>
    
ERR  
There is an unnecessary space at the beginning and the pipe symbol ('|') at the end, which are both formatting errors. The translation itself is otherwise accurate.

Correct translation:  
एप्लिकेशन छोड़ें
```

<!-- cache_translation_check_hi_422c24a04ed94fed228cb4058d565ca8ea6c402f23ed69af3a444de50b8d84c7 -->
```
        <source>&amp;About %1</source>
        <translation>&amp;अबाउट %1</translation>
    
ERR
The translation incorrectly leaves the English word "About" (अबाउट) in Devanagari script rather than using the proper Hindi equivalent. This is not idiomatic or natural in Hindi.

Correct translation:
%1 के &amp;बारे में
```

<!-- cache_translation_check_hi_40f79f813340977d93414bc6197398b43416a5fcd0a2520ee04b75360dede0da -->
```
        <source>About &amp;Qt</source>
        <translation>अबाउट &amp;क्यूटी</translation>
    
ERR
The translation unnecessarily uses the English word "अबाउट" (about) and "क्यूटी" (Qt) in Devanagari script, rather than using the standard localized form. For Hindi, a better translation would provide a natural Hindi equivalent for "About".

Correct translation:
क्यूटी &amp;के बारे में
```

<!-- cache_translation_check_hi_9dc40e5282a6b8556f2357b02cf9a8bba35c247fbe1e925f70d5f8878c74d48e -->
```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>प्रॉक्सी &lt;b&gt;अक्षम&lt;/b&gt; है: %1</translation>
    
ERR
The translation is incorrect. The English says "Proxy is enabled", but the Hindi translation says "Proxy is disabled" ("अक्षम" means "disabled", it should be "सक्रिय" or "सक्षम").

Correct translation:
प्रॉक्सी &lt;b&gt;सक्षम&lt;/b&gt; है: %1
```

<!-- cache_translation_check_hi_b44ddeb82f2c85980803f3040b9456ee76cef4d22a61cac16cc98bf6cc74619b -->
```
        <source>Sign &amp;message…</source>
        <translation>हस्ताक्षर &amp;संदेश</translation>
    
ERR
The translation is missing the ellipsis (…) present in the source text. Additionally, the phrasing "हस्ताक्षर संदेश" translates to "Signature Message" rather than the imperative "Sign message".

Correct translation:
&संदेश पर हस्ताक्षर करें…
```

<!-- cache_translation_check_hi_20a2a3357e722e3717ef28dfd320f86b4aabf12e5d0f63d6c00bac93fe110ad6 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>क्लिपबोर्ड से PSBT लोड करें…</translation>
    
ERR
The translation is missing the shortcut key indicator (&amp;). According to the instructions, the &amp; must exist exactly once in the translation if it is present in the source.

Correct translation:
&amp;क्लिपबोर्ड से PSBT लोड करें…
```

<!-- cache_translation_check_hi_5180f4a954ef278339f73ad8d8bb541239d9bccdffa9f5904d0d25b6bac96444 -->
```
        <source>Copy &amp;label</source>
        <translation>कॉपी  &amp;लेबल</translation>
    
ERR
There is an extra space between "कॉपी" and "&लेबल". The correct translation should not have double spaces.

Correct translation:
कॉपी &लेबल
```

<!-- cache_translation_check_hi_1de1929d3979d6b8231c99ee6720c2a28fdb72faba9abc38a4305e89adc0490f -->
```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>क्या आपको यकीन है कि आप इस बटवे का स्थानांतरण करना चाहते है?</translation>
    
ERR
The translation is missing the format specifier `%1` and the HTML tags `<i>` and `</i>` present in the source text.

Correct translation:
क्या आप वाकई वॉलेट <i>%1</i> को स्थानांतरित करना चाहते हैं?
```

<!-- cache_translation_check_hi_45851c162a9c3275808b9c7d36bf94e2c3992ba6805c77cce04ce5f497c46a7b -->
```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>बटवा स्थानांतरित हो रहा है</translation>
    
ERR
The translation omits the placeholder `%1`, the HTML formatting tags `<b></b>`, and the ellipsis `…`. The placeholder is essential to identify which wallet is being migrated.

Correct translation:
वॉलेट <b>%1</b> माइग्रेट किया जा रहा है…
```

<!-- cache_translation_check_hi_9e09aad17f6530836c193ba52a0a9ba67b76cf4fe98a9832ad69160f77d54ea8 -->
```
        <source>The wallet '%1' was migrated successfully.</source>
        <translation>बटवा स्थानांतरित कर दिया गया है</translation>
    
ERR
The format specifier '%1' is missing in the translation. Additionally, the word "successfully" (सफलतापूर्वक) has been omitted.

Correct translation:
वॉलेट '%1' सफलतापूर्वक माइग्रेट कर दिया गया है।
```

<!-- cache_translation_check_hi_960abb337764c254bc0264dfa10ed9396dfabdc2d60a0657c4ddeb3a4b5988fc -->
```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>हल करने योग्य लेकिन निगरानी में न लाई जा सकने वाली स्क्रिप्टों को नामक नए वॉलेट में स्थानांतरित कर दिया गया है।</translation>
    
ERR
The translation is missing the format specifier '%1' which represents the name of the new wallet.

Correct translation:
हल करने योग्य लेकिन निगरानी में न रखी गई स्क्रिप्टों को '%1' नामक नए वॉलेट में स्थानांतरित कर दिया गया है।
```

<!-- cache_translation_check_hi_44ea80b856552f42a7ab4203160945237be748c762c8803f95d933e7fa1038aa -->
```
        <source>Sends %1 to %2</source>
        <translation>%1 को %2 के पास भेजता है </translation>
    
ERR
There is an unwanted extra space at the end of the translation. Also, "के पास" implies "to the vicinity of" rather than "to", which can be less direct; "को भेजता है" is more accurate for a transaction context.

Correct translation:
%1 को %2 को भेजता है
```

<!-- cache_translation_check_hi_acf73b5c9d35ec56a9b6e529bbc90f466845f9d3a4a7d2e1f16a56b6304a093f -->
```
        <source>&amp;Reset</source>
        <translation>रीसेट</translation>
    
ERR
The translation is missing the '&' which denotes the shortcut key in both source and translation. It should appear exactly once in the translation as well.

Correct translation:
&रीसेट
```

<!-- cache_translation_check_hi_a75381cb5bd2897c21ac38ba6fe1ffe590a55e8d46277cbe603c92c258a2d565 -->
```
        <source>&amp;Peers</source>
        <translation>समकक्ष लोग</translation>
    
ERR
The translation "समकक्ष लोग" omits the shortcut key ampersand (&) that must be present exactly once in the translation (anywhere). Additionally, "समकक्ष" is sufficient for "Peers" in the context of Bitcoin; "लोग" (people) is unnecessary and may not be specific. 

Correct translation:
&समकक्ष
or
समकक्ष &

Either placement is acceptable as long as & is present exactly once.
```

<!-- cache_translation_check_hi_36bd945d7893ecdd7819fd2d44be418e628cf5ce4427bdd9359d592cb8d04ced -->
```
        <source>The transport layer version: %1</source>
        <translation>परिवहन परत संस्करण: %1</translation>
    
ERR
The Hindi is understandable but slightly ungrammatical/awkward: it misses the possessive particle "का" and "परत" is less common than "स्तर" or the English loan "लेयर". The format specifier %1 is correct and spacing is fine.

Correct translations:
- परिवहन परत का संस्करण: %1
or
- परिवहन स्तर का संस्करण: %1
or (more literal with English term)
- ट्रांसपोर्ट लेयर का संस्करण: %1
```

<!-- cache_translation_check_hi_c5064bd028a5c2fc20819f83583f4f49984d573a698be81bdf6f0320c1bd8d40 -->
```
        <source>The BIP324 session ID string in hex.</source>
        <translation>Hex में BIP324 सत्र आई.डी. स्ट्रिंग |</translation>
    
ERR
The translation is mostly correct but uses a vertical bar '|' instead of a period (।) at the end, which is uncommon in precise technical translations and may be considered an erroneous format. Also, "Hex में" is informal; it is better to use "हेक्स" instead of "Hex".

Correct translation:
हेक्स में BIP324 सत्र आईडी स्ट्रिंग।
```

<!-- cache_translation_check_hi_d9d7f9f34e5e0298c8c334289ecf5f7f6f70035b0427720252318278f283d6e3 -->
```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>हमारे मेमपूल में स्वीकार किए गए एक उपन्यास लेनदेन के बाद से इस सहकर्मी से प्राप्त हुआ समय बीत चुका है।</translation>
    
ERR
The term "उपन्यास लेनदेन" incorrectly translates "novel transaction" as "novel" meaning "book" (उपन्यास) in Hindi, which is a mistranslation. In this context, "novel" means "new" or "recent" transaction. The overall sentence structure is also a bit awkward and could be clarified.

Correct translation:
हमारे मेमपूल में किसी नए लेनदेन के इस सहकर्मी से प्राप्त होने के बाद से बीता हुआ समय।
```

<!-- cache_translation_check_hi_cdcadbba5f7fa4a2b95c1c94dc7dbb5bdd7ec25dbfedea7387fe91f88904885f -->
```
        <source>&amp;Open</source>
        <translation>खुला हुआ</translation>
    
ERR
The translation omits the ampersand (&), which is used to indicate a shortcut key in the source. Additionally, "खुला हुआ" means "opened" rather than the imperative "Open", which should be "खोलें" or similar.

Correct translation:
&खोलें
</reply>
```

<!-- cache_translation_check_hi_a9b88dac1b2daaffb4afa8d517b6ad4d731471d3c0b76e111df1288dd62d1f65 -->
```
        <source>&amp;Console</source>
        <translation>कंसोल</translation>
    
ERR
The translation is missing the ampersand (&), which usually indicates a shortcut key in menu items. The & should appear exactly once in the translation.

Correct translation:
&कंसोल
or
क&ंसोल

Either placement is acceptable as long as the & appears exactly once.
```

<!-- cache_translation_check_hi_211735ebfe13ae0ede7ed4421bdb142d3f0e20f3ea4d9cf1e8196ad3c74d35ec -->
```
        <source>&amp;Network Traffic</source>
        <translation>&amp;प्रसार यातायात</translation>
    
ERR
The translation "&amp;प्रसार यातायात" is inaccurate. The English phrase "Network Traffic" in the context of Bitcoin refers to data traffic over a computer network. "प्रसार" is closer to "broadcasting" or "dissemination", which is not the standard term for "network" in technical Hindi. The correct translation should use "नेटवर्क" for "Network" and "ट्रैफिक" or "आवागमन" for "Traffic". 

Correct translation:
&amp;नेटवर्क ट्रैफिक
```

<!-- cache_translation_check_hi_87acad392a767ec316e08801bab64ae765817d269a8329daf620a249e0fc1db5 -->
```
        <source>1 &amp;hour</source>
        <translation>1 घंटा</translation>
    
ERR
The ampersand (&) denoting the shortcut key is missing from the Hindi translation. It must appear exactly once.

Correct translation:
1 &amp;घंटा
</reply>
```

<!-- cache_translation_check_hi_8ef1d3eb041bd15bd4e57a5faea9491e233dde48008c1a13e372b78cdd38efa6 -->
```
        <source>1 d&amp;ay</source>
        <translation>1 दिन</translation>
    
ERR
The ampersand (&), which is usually used to indicate a shortcut key, is missing in the Hindi translation. It should appear exactly once, anywhere in the translation.

Correct translation:
1 &दिन
or 
1 द&िन
(placing & before any letter, as appropriate for intended shortcut key)
```

<!-- cache_translation_check_hi_5e5ce97ff87816521f2a879c2434d7501428f8d762b0c413e150c8266869e51d -->
```
        <source>1 &amp;week</source>
        <translation>1 सप्ताह</translation>
    
ERR
The translation for "1 &amp;week" is missing the ampersand which is used for shortcut keys. The ampersand must appear exactly once in the translation.

Correct translation:
1 &amp;सप्ताह
```

<!-- cache_translation_check_hi_c2183f1175ab425df363c17c60ef2bf7e7ad5ec4f5d6f15cf5b49f9494b65dba -->
```
        <source>1 &amp;year</source>
        <translation>1 साल</translation>
    
ERR
The translation omits the ampersand (&), which is intended to mark the shortcut key. In Hindi, it should also appear exactly once.

Correct translation:
1 &साल
```

<!-- cache_translation_check_hi_8feadeb00b0127d61b94f847022dfd86ac49354fe01ca2dab9631b3d31b8d694 -->
```
        <source>Clear</source>
        <translation>क्लिअर </translation>
    
ERR
The translation "क्लिअर " uses a transliteration of "Clear" rather than a proper Hindi equivalent, and it also has a stray space at the end. The correct and more proper translation is:

साफ़ करें

If the UI convention is to use single words, then "साफ़ करें" or simply "साफ़" would be correct. However, the transliterated "क्लिअर" is not standard.

Correct translation:
साफ़ करें
```

<!-- cache_translation_check_hi_190ae0748f9379f324e70eb6fab8b6587f544ca63563f72d82c885f769569720 -->
```
        <source>Copy &amp;message</source>
        <translation>कॉपी  &amp;मेसेज</translation>
    
ERR
There is a double space between "कॉपी" and "&amp;मेसेज". Only a single space should exist.

Correct translation:
कॉपी &amp;मेसेज
```

<!-- cache_translation_check_hi_1f67b802483ea03ae818c77f821cd1333006984fa98caca36a1bc64e2c767c15 -->
```
        <source>Could not generate new %1 address</source>
        <translation>नया पता उत्पन्न नहीं कर सका %1 </translation>
    
ERR
The order of words is incorrect in the Hindi translation, and the format specifier %1 is wrongly placed. It should directly precede पता to match the source text structure and retain clarity.

Correct translation:
नया %1 पता उत्पन्न नहीं कर सका
```

<!-- cache_translation_check_hi_84420d0910459792b84c76c217d405d23a70be606892294dd39a9d7f000de6a1 -->
```
        <source>Copy &amp;Address</source>
        <translation>कॉपी  &amp;अड्रेस</translation>
    
ERR
There is an unwanted double space between "कॉपी" and "&amp;अड्रेस" in the translation. There should be only a single space.

Correct translation:
कॉपी &amp;अड्रेस
```

<!-- cache_translation_check_hi_e5231365c4f9b9039ac0462695ba86ce3b31f5f1eaaf8e05c71b06a14ec9a61b -->
```
        <source>&amp;Verify</source>
        <translation>&amp;वेरीफाय</translation>
    
ERR
The translation uses the transliterated English word "वेरीफाय" instead of the correct Hindi equivalent. This may not be easily understood by native Hindi speakers. The correct Hindi translation for "Verify" would be "सत्यापित करें".

Correct translation:
&सत्यापित करें
```

<!-- cache_translation_check_hi_2c4dfd25dab8a7a3982446b7a72768956a556b7e1fd6f64e62aced089dc85496 -->
```
        <source>Verify this address on e.g. a hardware wallet screen</source>
        <translation>इस पते को वेरीफाय करें उदा.  एक हार्डवेयर वॉलेट स्क्रीन</translation>
    
ERR
The abbreviation "उदा." for "e.g." (for example) is not commonly used or recommended in formal Hindi. It should be replaced with "जैसे कि" to provide better clarity. There is also an unnecessary space after "उदा.".

Correct translation:
इस पते को, जैसे कि एक हार्डवेयर वॉलेट स्क्रीन पर, सत्यापित करें
```

<!-- cache_translation_check_hi_28a77482dbacc154c30d471cc592d9eb829e854e0085e317d7d4cb6671980dd9 -->
```
        <source>Add &amp;Recipient</source>
        <translation>अड &amp;रिसिपिएंट</translation>
    
ERR
The translation simply transcribes the English words "Add" and "Recipient" into Devanagari script, which is not proper Hindi. Also, "अड" is not a Hindi word.

Correct translation:
प्राप्तकर्ता &amp;जोड़ें
```

<!-- cache_translation_check_hi_00fb8ea9e47e6f0a853859ed7a2f17251110b352f1a3dfe93a69be3d1c84cb48 -->
```
        <source>S&amp;end</source>
        <translation>सेन्ड&amp;</translation>
    
ERR
The translation is incorrect because "सेन्ड" is a transliteration of "Send" rather than a proper Hindi translation. The correct Hindi translation for "Send" is "भेजें". The ampersand (&) is present exactly once, which is correct.

Correct translation:
भेजें&amp;
```

<!-- cache_translation_check_hi_27dfd905e7f8fbe25731bff03a9d9b6083887f28fd6cf6abc934a589a14265f8 -->
```
        <source>Creates a Partially Signed Bitcoin Transaction (PSBT) for use with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <translation>उदाहरण के लिए उपयोग के लिए आंशिक रूप से हस्ताक्षरित बिटकॉइन लेनदेन (PSBT) बनाता है। एक ऑफ़लाइन% 1 %1  वॉलेट, या एक PSBT-संगत हार्डवेयर वॉलेट।</translation>
    
ERR
The translation introduces format and spacing errors:
- The English sentence structure is disrupted. "e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet" is split awkwardly.
- %1 appears twice, and with incorrect/spaced formatting: "ऑफ़लाइन% 1 %1  वॉलेट" is incorrect. There should be just one %1, and it should not have inappropriate spacing.
- Preferably, "for use with..." should be translated as a natural connective rather than as two fragments.

Correct translation:
उदाहरण के लिए, ऑफ़लाइन %1 वॉलेट या PSBT-संगत हार्डवेयर वॉलेट के साथ उपयोग के लिए आंशिक रूप से हस्ताक्षरित बिटकॉइन लेनदेन (PSBT) बनाता है।
```

<!-- cache_translation_check_hi_fc3cb211db86086adceadb5437292206a9ee068d9b26fd0196e58d1185947bf7 -->
```
        <source>%1 to '%2'</source>
        <translation>%1टु '%2'</translation>
    
ERR
There is a spacing issue between '%1' and 'टु'. Also, 'टु' is a transliteration of 'to', which is not correct Hindi. The correct Hindi translation for 'to' in this context (showing movement or transfer) would be "से" (from) or "को" (to), depending on the context; here "को" is appropriate.

Correct translation:
%1 को '%2'
```

<!-- cache_translation_check_hi_56f411f8ece0a2021c16fee53e308d6d8d64848b78ddd017a60601640944b127 -->
```
        <source>PSBT saved</source>
        <extracomment>Popup message when a PSBT has been saved to a file</extracomment>
        <translation>पीएसबीटी सहेजा गया
 </translation>
    
ERR
There is an unwanted whitespace character (possibly a newline or non-breaking space) at the end of the translation. The translation itself is otherwise correct.

Correct translation:
पीएसबीटी सहेजा गया
```

<!-- cache_translation_check_hi_b99ea6b244615cbaa17c91456e2198f01c6e54ca0949055ca17192d383cbd041 -->
```
        <source>Unsigned Transaction</source>
        <comment>PSBT copied</comment>
        <extracomment>Caption of "PSBT has been copied" messagebox</extracomment>
        <translation>अहस्ताक्षरित लेनदेन
 </translation>
    
ERR
There is a formatting issue: there is an unnecessary newline and a non-breaking space at the end of the translation. This causes extra spacing or layout issues.

Correct translation:
अहस्ताक्षरित लेनदेन
```

<!-- cache_translation_check_hi_9f2459f6c5d1bd8f0db5273fb58cf93b36d5612e012255ef1450cceb20a4c1d9 -->
```
        <source>A&amp;mount:</source>
        <translation>&amp;अमौंट</translation>
    
ERR
The translation "&amp;अमौंट" is problematic because "अमौंट" is an incorrect transliteration of "amount" in Hindi. The proper term in Hindi is "राशि". Also, the ampersand (&amp;) shortcut is present, which is fine, and spacing is correct. The correct translation should use the proper Hindi word.

Correct translation:
&राशि:
```

<!-- cache_translation_check_hi_883b540f00142d1c657e1a363c1d1037cbb64bf3d5cd7ac8c8e68624882b312a -->
```
        <source>Pay &amp;To:</source>
        <translation>पें &amp;टु:</translation>
    
ERR
The translation is incorrect. The English phrase "Pay &To:" should be translated into Hindi as "भुगतान &To:". The word 'पें' is not standard Hindi for 'Pay', and '&To:' is not translated. Ideally, 'To' should also be translated to 'को', resulting in "भुगतान &को:" or "&को भुगतान:", ensuring the '&' shortcut key is included once. 

Correct translation:
भुगतान &को:
```

<!-- cache_translation_check_hi_519201e0cf5bb78f3337bf4c5c4b90bcc5defde9e7e2b4428e3900a8c06a1465 -->
```
        <source>Verify &amp;Message</source>
        <translation>सत्यापित करें और संदेश</translation>
    
ERR
The Hindi translation is incorrect. The '&' character, which is used to denote a keyboard shortcut in the source ("&Message"), is missing in the translation. Additionally, the translation "सत्यापित करें और संदेश" means "Verify and message," which is not an accurate translation of "Verify &Message." It should read as "संदेश सत्यापित करें" or "संदेश &सत्यापित करें", but the ampersand should precede the shortcut key in the Hindi word, typically the one to which the shortcut will be assigned (here, "संदेश").

Correct translation:
&संदेश सत्यापित करें
```

<!-- cache_translation_check_hi_15fcb93e0b7799bb1a4d7b16bbba8012dbb0d57dd8164776f6c09463317a3ab9 -->
```
        <source>kB/s</source>
        <translation>kB/s </translation>
    
ERR
There is an extra space at the end of the translation ("kB/s "). The translation should match the source exactly without additional spaces.

Correct translation:
kB/s
```

<!-- cache_translation_check_hi_686670211a28e6fa515b72fed28fa9feda6840a162a0800955a1f6b18ef908e7 -->
```
        <source>Source</source>
        <translation>सॉSस</translation>
    
ERR
The translation "सॉSस" is incorrect and unreadable in Hindi; it appears to be gibberish. The correct translation for "Source" in Hindi is "स्रोत".

Correct translation:
स्रोत
```

<!-- cache_translation_check_hi_887aa3ef401238105b47b202a5a43c0be1ba4e5fb44e3e3dab987c79c7f39448 -->
```
        <source>Debit</source>
        <translation>जमा</translation>
    
ERR
The translation is incorrect. "Debit" should be translated as "डेबिट" or "जमा राशि की निकासी" in Hindi, while "जमा" means "Credit" or "Deposit", which is the opposite.

Correct translation:
डेबिट
```

<!-- cache_translation_check_hi_a95663fd1e88c3e6fec1ece60645d1ca7811d7cfb7b0266377d48cf7d5f0c3ad -->
```
        <source>Confirmed (%1 confirmations)</source>
        <translation>की पुष्टि की (%1 पुष्टिकरण)</translation>
    
ERR
The translation is incorrect and contains a redundancy. "की पुष्टि की" translates as "has been confirmed", but it is not idiomatic and "की" is repeated. Also, the placeholder %1 is correctly carried over, but "पुष्टिकरण" is singular while it should be plural.

Correct translation:
पुष्टि हुई (%1 पुष्टि‌करण)
OR (more idiomatic)
पुष्टि हो गई (%1 पुष्टिकरण)
```

<!-- cache_translation_check_hi_69f2df753fcd588f55edb8930f4a66072131f2d993a587f84d460837d1bc42df -->
```
        <source>Conflicted</source>
        <translation>एक दूसरे के विरोध में</translation>
    
ERR
The translation "एक दूसरे के विरोध में" literally means "in opposition to each other" and is a phrase, not a succinct status label suitable for a technical context like Bitcoin. The English term "Conflicted" is typically translated in this UI context as a single word that matches the style of other transaction statuses.

Correct translation:
विरोधाभासी
```

<!-- cache_translation_check_hi_5180f4a954ef278339f73ad8d8bb541239d9bccdffa9f5904d0d25b6bac96444 -->
```
        <source>Copy &amp;label</source>
        <translation>कॉपी  &amp;लेबल</translation>
    
ERR
There is an extra space between "कॉपी" and "&लेबल". The correct translation should not have double spaces.

Correct translation:
कॉपी &लेबल
```

<!-- cache_translation_check_hi_d8d5666caad9cb7fab78076343fac8869cfbb56141b580f5dbc3f6544e3a54f7 -->
```
        <source>Signer error</source>
        <translation>Signer error/हस्ताक्षरकर्ता त्रुटि</translation>
    
ERR
The translation is problematic because it provides both the English phrase and the Hindi translation separated by a slash, which is not standard practice. The correct translation should only include the Hindi equivalent.

Correct translation:
हस्ताक्षरकर्ता त्रुटि
```

<!-- cache_translation_check_hi_49ad723bbe3b5e9e3b65ceea52ad65d514d9e3df3ce0b50cfac035c1a8d852f8 -->
```
        <source>&amp;Export</source>
        <translation>निर्यात</translation>
    
ERR
The translation for '&Export' misses the '&' character, which is used for shortcut keys. The '&' should be present exactly once in the Hindi translation, at any position.

Correct translation:
&निर्यात
or
निर्यात (&amp;E)
or
निर्यात (&amp;N)

However, the most common and direct is:
&निर्यात
```

<!-- cache_translation_check_hi_15ca5a08aa63d6c0316738e0f451ce1df952172dc0ac9b4b339df3f7d179eed9 -->
```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>-assumeutxo snapshot state को सत्यापित करने में %sविफल रहा |  यह हार्डवेयर समस्या, या सॉफ्टवेयर में बग, या खराब सॉफ्टवेयर संशोधन को इंगित करता है जिसके कारण अमान्य स्नैपशॉट लोड हो गया। इसके परिणामस्वरूप, नोड बंद हो जाएगा और स्नैपशॉट पर निर्मित किसी भी स्थिति का उपयोग करना बंद कर देगा, जिससे चेन की ऊंचाई %d से %d पर रीसेट हो जाएगी। अगली बार restart करने पर, नोड किसी भी स्नैपशॉट डेटा का उपयोग किए बिना %d से सिंक करना फिर से शुरू कर देगा। कृपया इस घटना की रिपोर्ट %s को करें, जिसमें यह भी शामिल है कि आपने स्नैपशॉट कैसे प्राप्त किया। अमान्य स्नैपशॉट चेनस्टेट को डिस्क पर छोड़ दिया जाएगा, ताकि यह उस समस्या का निदान करने में सहायक हो, जिसके कारण यह त्रुटि हुई।</translation>
    
ERR
Problems:
- Missing space between "%s" and "विफल" ("%sविफल" → "%s विफल").
- Uses '|' after first sentence instead of Hindi punctuation "।".
- English word "restart" left untranslated.
- Minor wording improvements for natural Hindi.

Correct translation:
-assumeutxo snapshot state को सत्यापित करने में %s विफल रहा। यह हार्डवेयर समस्या, सॉफ़्टवेयर में बग, या ऐसा खराब सॉफ़्टवेयर संशोधन है जिसने एक अमान्य स्नैपशॉट लोड होने की अनुमति दी। इसके परिणामस्वरूप, नोड बंद हो जाएगा और स्नैपशॉट पर निर्मित किसी भी स्थिति का उपयोग करना बंद कर देगा, जिससे चेन की ऊँचाई %d से %d पर रीसेट हो जाएगी। अगले पुनरारंभ पर, नोड किसी भी स्नैपशॉट डेटा का उपयोग किए बिना %d से सिंक करना फिर से शुरू कर देगा। कृपया यह घटना %s को रिपोर्ट करें, तथा यह भी बताएं कि आपने स्नैपशॉट कैसे प्राप्त किया। अमान्य स्नैपशॉट चेनस्टेट को डिस्क पर छोड़ दिया जाएगा, ताकि यह उस समस्या के निदान में सहायक रहे जिसने यह त्रुटि उत्पन्न की।
```

<!-- cache_translation_check_hi_be4aa1c17b20c699bb5e0c1b36135871fb3392158f985ee1eb70d5367013fe64 -->
```
        <source>%s request to listen on port %u. This port is considered "bad" and thus it is unlikely that any peer will connect to it. See doc/p2p-bad-ports.md for details and a full list.</source>
        <translation>%u पोर्ट पर सुनने का %s अनुरोध. इस बंदरगाह को "खराब" माना जाता है और इस प्रकार यह संभावना नहीं है कि कोई भी सहकर्मी इससे जुड़ेगा। विवरण और पूरी सूची के लिए doc/p2p-bad-ports.md देखें।</translation>
    
ERR
The translation for "port" as "बंदरगाह" (bandargāh) is incorrect in a technical context. While it means a maritime port (harbor), in computing, "पोर्ट" (port) should be transliterated. Additionally, the word order in the first sentence is slightly unnatural.

Correct translation:
पोर्ट %u पर सुनने का %s अनुरोध। इस पोर्ट को "खराब" माना जाता है और इसलिए इसकी संभावना कम है कि कोई पीयर (peer) इससे जुड़ेगा। विवरण और पूरी सूची के लिए doc/p2p-bad-ports.md देखें।
```

<!-- cache_translation_check_hi_d8c2b4e6293bee98726f7dbb5011ac8a42b9fdd4d5e4379416486ea3e4540cad -->
```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>असमर्थित श्रेणी-विशिष्ट लॉगिंग स्तर%1$s=%2$s.अपेक्षित%1$s=&lt;category&gt;:&lt;loglevel&gt;.मान्य श्रेणियां:%3$s.मान्य लॉग स्तर:%4$s</translation>
    
ERR
The translation contains whitespace formatting issues. There are missing spaces before and after the format specifiers and punctuation marks, which makes the text difficult to read and deviates from the source's spacing. Specifically, there should be spaces before `%1$s`, after the first sentence's period, and after the colons. Additionally, the final period from the source is missing.

Correct translation:
असमर्थित श्रेणी-विशिष्ट लॉगिंग स्तर %1$s=%2$s। अपेक्षित %1$s=&lt;category&gt;:&lt;loglevel&gt;। मान्य श्रेणियां: %3$s। मान्य लॉग स्तर: %4$s।
```

<!-- cache_translation_check_hi_0b5282e50817be9e217eb76cc39641729a43f3f334c97010f65de73a8520620d -->
```
        <source>%s is set very high! Fees this large could be paid on a single transaction.</source>
        <translation>%sबहुत अधिक निर्धारित है! इतनी बड़ी फीस एक ही लेनदेन पर चुकाई जा सकती है।</translation>
    
ERR
There is a missing space between the format specifier '%s' and 'बहुत', which causes a formatting issue. Otherwise, the translation is accurate.

Correct translation:
%s बहुत अधिक निर्धारित है! इतनी बड़ी फीस एक ही लेनदेन पर चुकाई जा सकती है।
```

<!-- cache_translation_check_hi_f65c92a8906ed0ec7a06ee7de59cb0ae24550b0d6dcec5af176c3c087c8d93ff -->
```
        <source>Failed to remove snapshot chainstate dir (%s). Manually remove it before restarting.
</source>
        <translation>स्नैपशॉट चेनस्टेट डायरेक्टरी (%s) को हटाने में विफल। Restart करने से पहले इसे मैन्युअल रूप से हटाएँ।
</translation>
    
ERR
The translation mixes Hindi and English ("Restart") and could use a more natural Hindi phrasing. The format specifier (%s) is preserved correctly.

Correct translation:
स्नैपशॉट चेनस्टेट डायरेक्टरी (%s) को हटाने में विफल रहा। पुनःप्रारंभ करने से पहले इसे मैन्युअल रूप से हटा दें।
```

<!-- cache_translation_check_hi_6ddc88a32c50249490db19403d09f4f560c70c0a210c52a7166e319f7ab12a70 -->
```
        <source>UTXO snapshot failed to validate. Restart to resume normal initial block download, or try loading a different snapshot.</source>
        <translation>UTXO स्नैपशॉट मान्य करने में विफल रहा। सामान्य आरंभिक ब्लॉक डाउनलोड को फिर से शुरू करने के लिए restart करें, या कोई भिन्न स्नैपशॉट लोड करने का प्रयास करें।</translation>
    
ERR
The translation is mostly understandable but has issues: it mixes English ("restart") instead of a Hindi verb and uses slightly awkward phrasing ("सामान्य आरंभिक ब्लॉक डाउनलोड"). No format specifiers are involved and there are no whitespace problems.

Suggested correct translation:
UTXO स्नैपशॉट मान्य करने में विफल रहा। सामान्य प्रारंभिक ब्लॉक डाउनलोड को पुनः आरंभ करने के लिए सिस्टम/प्रोग्राम को पुनः चालू करें, या कोई भिन्न स्नैपशॉट लोड करने का प्रयास करें।
```

<!-- cache_translation_check_hi_0669532d02a7676a09fad3f9e84e6f485129704364ea2201b7937695094ba56a -->
```
        <source>Your computer's date and time appear to be more than %d minutes out of sync with the network, this may lead to consensus failure. After you've confirmed your computer's clock, this message should no longer appear when you restart your node. Without a restart, it should stop showing automatically after you've connected to a sufficient number of new outbound peers, which may take some time. You can inspect the `timeoffset` field of the `getpeerinfo` and `getnetworkinfo` RPC methods to get more info.</source>
        <translation>आपके कंप्यूटर की तिथि और समय नेटवर्क के साथ %d मिनट से अधिक समय तक सिंक से बाहर प्रतीत है, इससे सहमति विफलता हो सकती है। आपके द्वारा अपने कंप्यूटर की घड़ी की पुष्टि करने के बाद, जब आप अपना नोड restart करेंगे तो यह संदेश दिखाई नहीं देना चाहिए। Restart किए बिना, जब आप पर्याप्त संख्या में नए outbound peers से कनेक्ट हो जाते हैं, तो यह स्वचालित रूप से दिखना बंद हो जाना चाहिए, जिसमें कुछ समय लग सकता है। अधिक जानकारी प्राप्त करने के लिए आप `getpeerinfo` और `getnetworkinfo` RPC विधियों के `timeoffset` फ़ील्ड का निरीक्षण कर सकते हैं।</translation>
    
ERR
Issues:
- Several English words left untranslated or inconsistently used: "restart", "outbound peers" — better to translate these for clarity.
- Minor stylistic improvements for natural Hindi (e.g., "सिंक से बाहर प्रतीत है" → "सिंक से बाहर दिख रहा/दिखती है", "सहमति विफलता" → "सम्मति विफलता" is fine but "सहमति" less common; use "सम्मति" or "कंसेंसस" consistently).
- Keep format specifier %d and code-style backticks unchanged (they are correct).

Suggested corrected translation:
आपके कंप्यूटर की तिथि और समय नेटवर्क के साथ %d मिनट से अधिक सिंक से बाहर दिख रहे हैं, जिससे सम्मति (consensus) विफल हो सकती है। अपने कंप्यूटर की घड़ी की पुष्टि करने के बाद, जब आप अपना नोड पुनःआरंभ (restart) करेंगे तो यह संदेश दिखाई देना बंद हो जाना चाहिए। बिना पुनःआरंभ के, जब आप पर्याप्त संख्या के नए आउटबाउंड पीयर/कनेक्शनों से जुड़ जाते हैं तो यह स्वतः ही बंद हो जाएगा, जिसमें कुछ समय लग सकता है। अधिक जानकारी के लिए आप `getpeerinfo` और `getnetworkinfo` RPC विधियों के `timeoffset` फ़ील्ड का निरीक्षण कर सकते हैं।
```

<!-- cache_translation_check_hi_338f769ea49416f95a9fc011c95607a790a01bf15402e0b49b5ebe19a01b6ca8 -->
```
        <source>Block verification was interrupted</source>
        <translation>ब्लॉक verification अन्तरायित हुआ</translation>
    
ERR
The translation contains an untranslated English word "verification" and a non-standard translation for "interrupted" ("अन्तरायित" is uncommon; "रोका गया" or "रोक दिया गया" would be better). Also, the wording lacks natural flow.

Correct translation:
ब्लॉक सत्यापन रोका गया था
```

<!-- cache_translation_check_hi_5ff4333d61e127c487b262d94605dad715242e104327c9166619219ddbd0610b -->
```
        <source>Elliptic curve cryptography sanity check failure. %s is shutting down.</source>
        <translation>Elliptic curve cryptography sanity check विफलता | %sबंद हो रही है |</translation>
    
ERR
There are issues with punctuation and spacing. In Hindi, a vertical bar '|' is not standard for separating sentences; use a full stop or '।' (Hindi danda). There is no space between '%s' and 'बंद हो रही है', which can cause readability issues. Also, more natural phrasing would be: 'Elliptic curve cryptography सत्यापन विफल हुआ है। %s बंद हो रही है।'

Correct translation:
Elliptic curve cryptography सत्यापन जांच विफल हुई है। %s बंद हो रही है।
```

<!-- cache_translation_check_hi_2f596529af946a16fa25ad528b619faaeb811d8c618bf4df593d97c2459dfa11 -->
```
        <source>Error: Unable to read wallet's best block locator record</source>
        <translation>Error: वॉलेट का best ब्लॉक लोकेटर रिकॉर्ड पढ़ने में असमर्थ</translation>
    
ERR
The translation mixes English and Hindi inconsistently ("best ब्लॉक लोकेटर रिकॉर्ड") and is slightly awkward ("वॉलेट का ... पढ़ने में असमर्थ" is understandable but not natural). No format specifiers or whitespace issues.

Suggested correction:
त्रुटि: वॉलेट के बेस्ट ब्लॉक-लोकेटर रिकॉर्ड को पढ़ने में असमर्थ
```

<!-- cache_translation_check_hi_47d223656fced25979a86d4b23606efef9ba113d1efc35d68fbc0a32f2d8b703 -->
```
        <source>Error: Unable to write solvable wallet best block locator record</source>
        <translation>Error: सॉल्वेबल वॉलेट best ब्लॉक लोकेटर रिकॉर्ड लिखने में असमर्थ</translation>
    
ERR
The translation mixes English and Hindi but is grammatically incorrect — it lacks the possessive marker and uses "best" in English. No format specifiers are involved.

Suggested correct translation:
त्रुटि: सॉल्वेबल वॉलेट का सर्वोत्तम ब्लॉक लोकेटर रिकॉर्ड लिखने में असमर्थ
```

<!-- cache_translation_check_hi_4dba9e7aff2a1a0c6716c2168b941274a78e4a082d5013c284e4990770d3a1ee -->
```
        <source>Error: Unable to write watchonly wallet best block locator record</source>
        <translation>Error: watchonly वॉलेट best  ब्लॉक लोकेटर रिकॉर्ड लिखने में असमर्थ</translation>
    
ERR
The translation mixes English and Hindi awkwardly, has a stray double space ("best  ब्लॉक"), and uses "Error:" instead of a Hindi equivalent. Also the genitive relation is unclear. A clearer Hindi translation:

Correct translation:
त्रुटि: watch-only वॉलेट का best ब्लॉक लोकेटर रिकॉर्ड लिखने में असमर्थ

(Or fully Hindi:
त्रुटि: वॉचलॉनली वॉलेट का सर्वश्रेष्ठ ब्लॉक लोकेटर रिकॉर्ड लिखने में असमर्थ)
```

<!-- cache_translation_check_hi_ba4f53048b06f8ebeeac8f8eb3a4153ade1d31cd971c4a0d342b609b1d5d8512 -->
```
        <source>Failed to disconnect block.</source>
        <translation>ब्लॉक को डिस्कनेक्ट करने में विफल |</translation>
    
ERR
The Hindi text uses an ASCII vertical bar (" |") as sentence terminator and has an extra space before it. Also it's better to use proper Hindi punctuation and/or a more natural phrasing.

Correct translation:
ब्लॉक को डिसकनेक्ट करने में विफल।
```

<!-- cache_translation_check_hi_8d2ce1838818f1d2ca87f37cdde86e9890f99d1f6faa12ac4ed825ab5b6d1df1 -->
```
        <source>Failed to write block.</source>
        <translation>ब्लॉक लिखने में विफल |</translation>
    
ERR
Translation is understandable Hindi but uses an incorrect punctuation character (" |") and has an extra space before it. Better to use the Devanagari danda or a period and remove the stray space.

Correct translation:
ब्लॉक लिखने में विफल।
```

<!-- cache_translation_check_hi_dada3e4106f89a2b2c5bc4860c421544d9d86850c3eed513ac25790002936290 -->
```
        <source>Invalid port specified in %s: '%s'</source>
        <translation>में निर्दिष्ट अमान्य पोर्ट %s:'%s'</translation>
    
ERR
The translation is awkward and does not follow natural Hindi sentence structure. The phrase "में निर्दिष्ट अमान्य पोर्ट" is an incorrect rearrangement and lacks clarity. Also, proper spacing after format specifiers is missing.

Correct translation:
%s में निर्दिष्ट पोर्ट अमान्य है: '%s'
```

<!-- cache_translation_check_hi_4819706aece16177d7fdf008507f4f1b40a8c5366dd27e2de145261c9c6bf41a -->
```
        <source>Specified data directory "%s" does not exist.</source>
        <translation>निर्दिष्ट डेटा निर्देशिका "%s" मौजूद नहीं है |</translation>
    
ERR
The translation is understandable, but the closing punctuation mark is the wrong character ("|") instead of the appropriate Hindi/Devanagari full stop ("।") or simply a period ("."). Also, stylistically, it is better to end the sentence with a period to match the source.

Correct translation:
निर्दिष्ट डेटा निर्देशिका "%s" मौजूद नहीं है।
```

<!-- cache_translation_check_hi_3b206675595790c9067bdc0cffcdb3dcebd50ceb404bba00a967782759020eea -->
```
        <source>System error while flushing: %s</source>
        <translation>फ्लशिंग करते समय सिस्टम error: %s</translation>
    
ERR
The translation mixes English and Hindi ("फ्लशिंग" and "सिस्टम error") and uses the English word "error" instead of a Hindi equivalent. The format specifier "%s" is preserved correctly and there are no whitespace issues.

Correct translation suggestions:
फ्लश करते समय सिस्टम त्रुटि: %s
or
फ्लशिंग करते समय सिस्टम त्रुटि: %s
```

<!-- cache_translation_check_hi_ae903439a742e13979eeef6fef4c5bbff2dc6ada3ae299a84a5008f21702ba9f -->
```
        <source>System error while saving block to disk: %s</source>
        <translation>ब्लॉक को डिस्क पर सहेजते समय सिस्टम error: %s</translation>
    
ERR
The translation unnecessarily retains the English word "error" instead of translating it into Hindi. It should also not have awkward spacing. The format specifier %s is correctly retained.

Correct translation:
डिस्क पर ब्लॉक सहेजते समय सिस्टम त्रुटि: %s
```

<!-- cache_translation_check_hi_d042a1cc87d0fa733c8f83685421834482398e07219ee67fe45176e5317d32ab -->
```
        <source>Error: cannot remove legacy wallet records</source>
        <translation>Error: leagcy वॉलेट रिकॉर्ड को हटाया नहीं जा सकता है</translation>
    
ERR
There are several problems:
- The word "Error" is untranslated.
- "leagcy" is a misspelling; correct is "legacy".
- "हटाया नहीं जा सकता है" is a literal passivation, but more natural Hindi would be "हटाए नहीं जा सकते" to match plural "records", or "हटाया नहीं जा सकता" for singular.

Correct translation:
त्रुटि: पुराने वॉलेट रिकॉर्ड को हटाया नहीं जा सकता है
```
</details>

Number of issues: 79.
