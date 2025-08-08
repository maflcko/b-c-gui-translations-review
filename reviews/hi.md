# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>hi</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bhi%5D%20low%20quality)


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

<!-- cache_translation_check_hi_704e40c758a9a42ba62f7b2d22eb480a1f82a295910154981ab1dadf2ba56c30 -->
```
        <source>Quit application</source>
        <translation> एप्लिकेशन छोड़ें |</translation>
    
ERR  
There is an unnecessary space at the beginning and the pipe symbol ('|') at the end, which are both formatting errors. The translation itself is otherwise accurate.

Correct translation:  
एप्लिकेशन छोड़ें
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

<!-- cache_translation_check_hi_d7d97beed218d39dd86fd92ef7f79a923c18d84be42dd2f19ec4f44bf6171ca9 -->
```
        <source>Backup wallet to another location</source>
        <translation>किसी अन्य स्थान पर वॉलेट  बैकअप करे |</translation>
    
ERR
There is a spacing issue in the phrase "वॉलेट  बैकअप" (double space), an unnecessary space before the pipe symbol (|), and the imperative verb should be "बनाएँ" to be polite and correct in Hindi. Also, the pipe symbol should not be used; a full stop is better suited for Hindi sentences.

Correct translation:
किसी अन्य स्थान पर वॉलेट का बैकअप बनाएं।
```

<!-- cache_translation_check_hi_23e048941d540b38587785e10b0d0728f2a38fe45cd3a61726f7705da816482b -->
```
        <source>Options…</source>
        <translation>विकल्प
 </translation>
    
ERR
The translation is mostly correct in meaning ("विकल्प" means "Options"), but it introduces an unwanted line break and a stray whitespace character after "विकल्प", which is a formatting issue.

Correct translation:
विकल्प…
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

<!-- cache_translation_check_hi_3cc395fc1cb5a7b5016eb7a820044b1dbf7d8e12fe4591fea74fbea51a178d79 -->
```
        <source>Open</source>
        <translation>खुला हुआ</translation>
    
ERR
The translation "खुला हुआ" means "opened" or "in an open state," which describes something that is already open, not the imperative "Open" (as in a button or command to open something). The correct Hindi translation for the command "Open" is:

संपन्न अनुवाद:
खोलें
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

<!-- cache_translation_check_hi_1f67b802483ea03ae818c77f821cd1333006984fa98caca36a1bc64e2c767c15 -->
```
        <source>Could not generate new %1 address</source>
        <translation>नया पता उत्पन्न नहीं कर सका %1 </translation>
    
ERR
The order of words is incorrect in the Hindi translation, and the format specifier %1 is wrongly placed. It should directly precede पता to match the source text structure and retain clarity.

Correct translation:
नया %1 पता उत्पन्न नहीं कर सका
```

<!-- cache_translation_check_hi_8903e7f119f502c1efabd9be63cb6ca8d9e94674f88b0b6940d937b31fe8dbf4 -->
```
        <source>Copy Address</source>
        <translation>कॉपी  अड्रेस</translation>
    
ERR
There is an issue with the translation: there is an unnecessary double space between "कॉपी" and "अड्रेस". Also, "अड्रेस" is a transliteration of "address", but the more standard Hindi term is "पता". However, using "अड्रेस" is common in technical contexts. For clarity, the spacing must be fixed.

Correct translation:
कॉपी अड्रेस

Or if you prefer the more natural Hindi:
पता कॉपी करें
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

<!-- cache_translation_check_hi_6e7d48aff66ab4c2e9f911eded1ec5e85b754ecc2e334e3814446db9530fac99 -->
```
        <source>Add Recipient</source>
        <translation>अड रिसिपिएंट</translation>
    
ERR
The translation is incorrect. "अड रिसिपिएंट" is a transliteration, not an actual Hindi translation, and "अड" is an inaccurate rendering of "Add". The correct Hindi translation should be:

प्राप्तकर्ता जोड़ें

Correct translation:
प्राप्तकर्ता जोड़ें
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

<!-- cache_translation_check_hi_723883393680388367ff42a3c0d4325cfa9dc1fb41bae2ed6d6ecb3513a500db -->
```
        <source>Verify Message</source>
        <translation>सत्यापित करें और संदेश</translation>
    
ERR
The translation "सत्यापित करें और संदेश" is inaccurate. It translates to "Verify and message" instead of "Verify Message". The "और" ("and") is erroneous.

Correct translation:
संदेश सत्यापित करें
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

<!-- cache_translation_check_hi_d8d5666caad9cb7fab78076343fac8869cfbb56141b580f5dbc3f6544e3a54f7 -->
```
        <source>Signer error</source>
        <translation>Signer error/हस्ताक्षरकर्ता त्रुटि</translation>
    
ERR
The translation is problematic because it provides both the English phrase and the Hindi translation separated by a slash, which is not standard practice. The correct translation should only include the Hindi equivalent.

Correct translation:
हस्ताक्षरकर्ता त्रुटि
```

<!-- cache_translation_check_hi_316e9978187c7f44c84e706c3a27a734fa7de630368e5ae6fecba3c85394484f -->
```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>-assumeutxo snapshot state को सत्यापित करने में %sविफल रहा |  यह हार्डवेयर समस्या, या सॉफ्टवेयर में बग, या खराब सॉफ्टवेयर संशोधन को इंगित करता है जिसके कारण अमान्य स्नैपशॉट लोड हो गया। इसके परिणामस्वरूप, नोड बंद हो जाएगा और स्नैपशॉट पर निर्मित किसी भी स्थिति का उपयोग करना बंद कर देगा, जिससे चेन की ऊंचाई %d से %d पर रीसेट हो जाएगी। अगली बार पुनः आरंभ करने पर, नोड किसी भी स्नैपशॉट डेटा का उपयोग किए बिना %d से सिंक करना फिर से शुरू कर देगा। कृपया इस घटना की रिपोर्ट %s को करें, जिसमें यह भी शामिल है कि आपने स्नैपशॉट कैसे प्राप्त किया। अमान्य स्नैपशॉट चेनस्टेट को डिस्क पर छोड़ दिया जाएगा, ताकि यह उस समस्या का निदान करने में सहायक हो, जिसके कारण यह त्रुटि हुई।</translation>
    
ERR
The translation is mostly accurate but has spacing and formatting errors relating to format specifiers. Specifically, there should be a space after "%s" in the first sentence ("%sविफल रहा" should be "%s विफल रहा"), and the format specifiers (%s, %d) should be preserved exactly as in the source text, matching spacing conventions.

Correct translation:
-assumeutxo snapshot state को सत्यापित करने में %s विफल रहा। यह हार्डवेयर समस्या, या सॉफ्टवेयर में बग, या खराब सॉफ्टवेयर संशोधन को इंगित करता है जिसके कारण अमान्य स्नैपशॉट लोड हो गया। इसके परिणामस्वरूप, नोड बंद हो जाएगा और स्नैपशॉट पर निर्मित किसी भी स्थिति का उपयोग करना बंद कर देगा, जिससे चेन की ऊंचाई %d से %d पर रीसेट हो जाएगी। अगली बार पुनः आरंभ करने पर, नोड किसी भी स्नैपशॉट डेटा का उपयोग किए बिना %d से सिंक करना फिर से शुरू कर देगा। कृपया इस घटना की रिपोर्ट %s को करें, जिसमें यह भी शामिल है कि आपने स्नैपशॉट कैसे प्राप्त किया। अमान्य स्नैपशॉट चेनस्टेट को डिस्क पर छोड़ दिया जाएगा, जिससे यह उस समस्या का निदान करने में सहायक हो सकता है, जिसके कारण यह त्रुटि हुई।
```

<!-- cache_translation_check_hi_10124f311d84454e939d798c66dba60dea5a9baa74812ff479e0b877667fafa8 -->
```
        <source>%s request to listen on port %u. This port is considered "bad" and thus it is unlikely that any peer will connect to it. See doc/p2p-bad-ports.md for details and a full list.</source>
        <translation>%s अनुरोध %u पोर्ट पर सुनने का. इस बंदरगाह को "खराब" माना जाता है और इस प्रकार यह संभावना नहीं है कि कोई भी सहकर्मी इससे जुड़ेगा। विवरण और पूरी सूची के लिए doc/p2p-bad-ports.md देखें।</translation>
    
ERR
There are issues with the translation:
1. The translation of "port" as "बंदरगाह" is inaccurate in this context. In computing, "port" should be translated as "पोर्ट".
2. The sentence structure is somewhat awkward with "अनुरोध %u पोर्ट पर सुनने का". It should follow the original sentence structure.
3. The format specifiers %s and %u are preserved but the sentence is not smooth in Hindi and is missing the correct auxiliary verbs.

Correct translation:
%s ने पोर्ट %u पर सुनने का अनुरोध किया है। इस पोर्ट को "खराब" माना जाता है, इसलिए शायद ही कोई पीयर इससे जुड़ेगा। विवरण और पूरी सूची के लिए doc/p2p-bad-ports.md देखें।
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

<!-- cache_translation_check_hi_959fe14c89ac9d0526c8b7197964f6f08409817c2ccce1a6b71981e48ee0b7db -->
```
        <source>Failed to connect best block (%s).</source>
        <translation>best ब्लॉक (%s) से कनेक्ट करने में विफल |</translation>
    
ERR  
The translation unnecessarily uses the English word "best" instead of its Hindi equivalent, which should be avoided for clarity and localization. Also, the sentence ends with a pipe (|) instead of the correct Hindi full stop (।). Otherwise, the format specifier is correctly carried over.

Correct translation:  
%s से सर्वश्रेष्ठ ब्लॉक कनेक्ट करने में विफल रहा।
```

<!-- cache_translation_check_hi_fdf15477d9670efe36510e6b0589e2c5074aa10763dbc1d621ea657cd5bdcd7d -->
```
        <source>Failed to write to block index database.</source>
        <translation>ब्लॉक इंडेक्स डेटाबेस में लिखने में विफल |</translation>
    
ERR
The translation is mostly accurate but contains a minor punctuation issue. The Hindi translation uses a vertical bar "|" at the end, which is not standard; the proper sentence terminator in Hindi is the "।" (Danda) or a period (".").

Correct translation:
ब्लॉक इंडेक्स डेटाबेस में लिखने में विफल।
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

Number of issues: 39.
