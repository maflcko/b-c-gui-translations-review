# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>hi</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bhi%5D%20low%20quality)


```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>पता सूची को %1यहां सहेजने का प्रयास करते समय एक त्रुटि हुई . कृपया पुन: प्रयास करें।</translation>
    
YES
There are spacing and punctuation issues. The phrase "%1यहां" incorrectly combines the format specifier "%1" with "यहां" (here), which is neither present in the source nor required. There should be a space between "%1" and the rest of the text, and "यहां" should not be present.

Correct translation:
पता सूची को %1 में सहेजने का प्रयास करते समय एक त्रुटि हुई। कृपया पुनः प्रयास करें।
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>चेतावनी: यदि आप अपना वॉलेट एन्क्रिप्ट करते हैं और अपना पासफ़्रेज़ खो देते हैं, तो आपअपने सभी बिटकॉइन &lt;b&gt; खो देंगे&lt;/b&gt; !</translation>
    
YES
There is a formatting error: "आपअपने" should be "आप अपने" (missing space). Also, the placement of the bold tags differs from the English sentence, which emphasizes "LOSE ALL OF YOUR BITCOINS". The Hindi translation has the bold tag only around "खो देंगे", not "अपने सभी बिटकॉइन खो देंगे" as in the original. The exclamation mark and spacing also show a stray space.

Correct translation:
चेतावनी: यदि आप अपना वॉलेट एन्क्रिप्ट करते हैं और अपना पासफ़्रेज़ खो देते हैं, तो आप &lt;b&gt;अपने सभी बिटकॉइन खो देंगे&lt;/b&gt;!
```

```
        <source>Banned Until</source>
        <translation>तक प्रतिबंधित</translation>
    
YES
The Hindi translation reverses the word order, resulting in an incomplete and unnatural phrase. "तक प्रतिबंधित" means "banned until", but leaves out the subject or context and is not commonly used standalone. A more accurate and natural translation would be:

Correct translation:
प्रतिबंधित होने की अवधि
or 
प्रतिबंधित तिथि (if referring to the date)
or
प्रतिबंधित किया गया समय (if referring to the banned-until time)
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>एक आंतरिक त्रुटि हुई। %1सुरक्षित रूप से जारी रखने का प्रयास करेगा। यह एक अप्रत्याशित बग है जिसे नीचे वर्णित के रूप में रिपोर्ट किया जा सकता है।</translation>
    
YES
There is a missing space after "%1", resulting in "%1सुरक्षित" instead of "%1 सुरक्षित".

Correct translation:
एक आंतरिक त्रुटि हुई। %1 सुरक्षित रूप से जारी रखने का प्रयास करेगा। यह एक अप्रत्याशित बग है जिसे नीचे वर्णित के रूप में रिपोर्ट किया जा सकता है।
```

```
        <source>Quit application</source>
        <translation> एप्लिकेशन छोड़ें |</translation>
    
YES  
There is an unnecessary space at the beginning and the pipe symbol ('|') at the end, which are both formatting errors. The translation itself is otherwise accurate.

Correct translation:  
एप्लिकेशन छोड़ें
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>प्रॉक्सी &lt;b&gt;अक्षम&lt;/b&gt; है: %1</translation>
    
YES
The translation is incorrect. The English says "Proxy is enabled", but the Hindi translation says "Proxy is disabled" ("अक्षम" means "disabled", it should be "सक्रिय" or "सक्षम").

Correct translation:
प्रॉक्सी &lt;b&gt;सक्षम&lt;/b&gt; है: %1
```

```
        <source>Backup wallet to another location</source>
        <translation>किसी अन्य स्थान पर वॉलेट  बैकअप करे |</translation>
    
YES
There is a spacing issue in the phrase "वॉलेट  बैकअप" (double space), an unnecessary space before the pipe symbol (|), and the imperative verb should be "बनाएँ" to be polite and correct in Hindi. Also, the pipe symbol should not be used; a full stop is better suited for Hindi sentences.

Correct translation:
किसी अन्य स्थान पर वॉलेट का बैकअप बनाएं।
```

```
        <source>Options…</source>
        <translation>विकल्प
 </translation>
    
YES
The translation is mostly correct in meaning ("विकल्प" means "Options"), but it introduces an unwanted line break and a stray whitespace character after "विकल्प", which is a formatting issue.

Correct translation:
विकल्प…
```

```
        <source>Sends %1 to %2</source>
        <translation>%1 को %2 के पास भेजता है </translation>
    
YES
There is an unwanted extra space at the end of the translation. Also, "के पास" implies "to the vicinity of" rather than "to", which can be less direct; "को भेजता है" is more accurate for a transaction context.

Correct translation:
%1 को %2 को भेजता है
```

```
        <source>The BIP324 session ID string in hex.</source>
        <translation>Hex में BIP324 सत्र आई.डी. स्ट्रिंग |</translation>
    
YES
The translation is mostly correct but uses a vertical bar '|' instead of a period (।) at the end, which is uncommon in precise technical translations and may be considered an erroneous format. Also, "Hex में" is informal; it is better to use "हेक्स" instead of "Hex".

Correct translation:
हेक्स में BIP324 सत्र आईडी स्ट्रिंग।
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>हमारे मेमपूल में स्वीकार किए गए एक उपन्यास लेनदेन के बाद से इस सहकर्मी से प्राप्त हुआ समय बीत चुका है।</translation>
    
YES
The term "उपन्यास लेनदेन" incorrectly translates "novel transaction" as "novel" meaning "book" (उपन्यास) in Hindi, which is a mistranslation. In this context, "novel" means "new" or "recent" transaction. The overall sentence structure is also a bit awkward and could be clarified.

Correct translation:
हमारे मेमपूल में किसी नए लेनदेन के इस सहकर्मी से प्राप्त होने के बाद से बीता हुआ समय।
```

```
        <source>Open</source>
        <translation>खुला हुआ</translation>
    
YES
The translation "खुला हुआ" means "opened" or "in an open state," which describes something that is already open, not the imperative "Open" (as in a button or command to open something). The correct Hindi translation for the command "Open" is:

संपन्न अनुवाद:
खोलें
```

```
        <source>Clear</source>
        <translation>क्लिअर </translation>
    
YES
The translation "क्लिअर " uses a transliteration of "Clear" rather than a proper Hindi equivalent, and it also has a stray space at the end. The correct and more proper translation is:

साफ़ करें

If the UI convention is to use single words, then "साफ़ करें" or simply "साफ़" would be correct. However, the transliterated "क्लिअर" is not standard.

Correct translation:
साफ़ करें
```

```
        <source>Could not generate new %1 address</source>
        <translation>नया पता उत्पन्न नहीं कर सका %1 </translation>
    
YES
The order of words is incorrect in the Hindi translation, and the format specifier %1 is wrongly placed. It should directly precede पता to match the source text structure and retain clarity.

Correct translation:
नया %1 पता उत्पन्न नहीं कर सका
```

```
        <source>Copy Address</source>
        <translation>कॉपी  अड्रेस</translation>
    
YES
There is an issue with the translation: there is an unnecessary double space between "कॉपी" and "अड्रेस". Also, "अड्रेस" is a transliteration of "address", but the more standard Hindi term is "पता". However, using "अड्रेस" is common in technical contexts. For clarity, the spacing must be fixed.

Correct translation:
कॉपी अड्रेस

Or if you prefer the more natural Hindi:
पता कॉपी करें
```

```
        <source>Verify this address on e.g. a hardware wallet screen</source>
        <translation>इस पते को वेरीफाय करें उदा.  एक हार्डवेयर वॉलेट स्क्रीन</translation>
    
YES
The abbreviation "उदा." for "e.g." (for example) is not commonly used or recommended in formal Hindi. It should be replaced with "जैसे कि" to provide better clarity. There is also an unnecessary space after "उदा.".

Correct translation:
इस पते को, जैसे कि एक हार्डवेयर वॉलेट स्क्रीन पर, सत्यापित करें
```

```
        <source>Add Recipient</source>
        <translation>अड रिसिपिएंट</translation>
    
YES
The translation is incorrect. "अड रिसिपिएंट" is a transliteration, not an actual Hindi translation, and "अड" is an inaccurate rendering of "Add". The correct Hindi translation should be:

प्राप्तकर्ता जोड़ें

Correct translation:
प्राप्तकर्ता जोड़ें
```

```
        <source>Creates a Partially Signed Bitcoin Transaction (PSBT) for use with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <translation>उदाहरण के लिए उपयोग के लिए आंशिक रूप से हस्ताक्षरित बिटकॉइन लेनदेन (PSBT) बनाता है। एक ऑफ़लाइन% 1 %1  वॉलेट, या एक PSBT-संगत हार्डवेयर वॉलेट।</translation>
    
YES
The translation introduces format and spacing errors:
- The English sentence structure is disrupted. "e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet" is split awkwardly.
- %1 appears twice, and with incorrect/spaced formatting: "ऑफ़लाइन% 1 %1  वॉलेट" is incorrect. There should be just one %1, and it should not have inappropriate spacing.
- Preferably, "for use with..." should be translated as a natural connective rather than as two fragments.

Correct translation:
उदाहरण के लिए, ऑफ़लाइन %1 वॉलेट या PSBT-संगत हार्डवेयर वॉलेट के साथ उपयोग के लिए आंशिक रूप से हस्ताक्षरित बिटकॉइन लेनदेन (PSBT) बनाता है।
```

```
        <source>%1 to '%2'</source>
        <translation>%1टु '%2'</translation>
    
YES
There is a spacing issue between '%1' and 'टु'. Also, 'टु' is a transliteration of 'to', which is not correct Hindi. The correct Hindi translation for 'to' in this context (showing movement or transfer) would be "से" (from) or "को" (to), depending on the context; here "को" is appropriate.

Correct translation:
%1 को '%2'
```

```
        <source>PSBT saved</source>
        <extracomment>Popup message when a PSBT has been saved to a file</extracomment>
        <translation>पीएसबीटी सहेजा गया
 </translation>
    
YES
There is an unwanted whitespace character (possibly a newline or non-breaking space) at the end of the translation. The translation itself is otherwise correct.

Correct translation:
पीएसबीटी सहेजा गया
```

```
        <source>Unsigned Transaction</source>
        <comment>PSBT copied</comment>
        <extracomment>Caption of "PSBT has been copied" messagebox</extracomment>
        <translation>अहस्ताक्षरित लेनदेन
 </translation>
    
YES
There is a formatting issue: there is an unnecessary newline and a non-breaking space at the end of the translation. This causes extra spacing or layout issues.

Correct translation:
अहस्ताक्षरित लेनदेन
```

```
        <source>Verify Message</source>
        <translation>सत्यापित करें और संदेश</translation>
    
YES
The translation "सत्यापित करें और संदेश" is inaccurate. It translates to "Verify and message" instead of "Verify Message". The "और" ("and") is erroneous.

Correct translation:
संदेश सत्यापित करें
```

```
        <source>kB/s</source>
        <translation>kB/s </translation>
    
YES
There is an extra space at the end of the translation ("kB/s "). The translation should match the source exactly without additional spaces.

Correct translation:
kB/s
```

```
        <source>Source</source>
        <translation>सॉSस</translation>
    
YES
The translation "सॉSस" is incorrect and unreadable in Hindi; it appears to be gibberish. The correct translation for "Source" in Hindi is "स्रोत".

Correct translation:
स्रोत
```

```
        <source>Debit</source>
        <translation>जमा</translation>
    
YES
The translation is incorrect. "Debit" should be translated as "डेबिट" or "जमा राशि की निकासी" in Hindi, while "जमा" means "Credit" or "Deposit", which is the opposite.

Correct translation:
डेबिट
```

```
        <source>Confirmed (%1 confirmations)</source>
        <translation>की पुष्टि की (%1 पुष्टिकरण)</translation>
    
YES
The translation is incorrect and contains a redundancy. "की पुष्टि की" translates as "has been confirmed", but it is not idiomatic and "की" is repeated. Also, the placeholder %1 is correctly carried over, but "पुष्टिकरण" is singular while it should be plural.

Correct translation:
पुष्टि हुई (%1 पुष्टि‌करण)
OR (more idiomatic)
पुष्टि हो गई (%1 पुष्टिकरण)
```

```
        <source>Conflicted</source>
        <translation>एक दूसरे के विरोध में</translation>
    
YES
The translation "एक दूसरे के विरोध में" literally means "in opposition to each other" and is a phrase, not a succinct status label suitable for a technical context like Bitcoin. The English term "Conflicted" is typically translated in this UI context as a single word that matches the style of other transaction statuses.

Correct translation:
विरोधाभासी
```

```
        <source>Signer error</source>
        <translation>Signer error/हस्ताक्षरकर्ता त्रुटि</translation>
    
YES
The translation is problematic because it provides both the English phrase and the Hindi translation separated by a slash, which is not standard practice. The correct translation should only include the Hindi equivalent.

Correct translation:
हस्ताक्षरकर्ता त्रुटि
```

```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>-assumeutxo snapshot state को सत्यापित करने में %sविफल रहा |  यह हार्डवेयर समस्या, या सॉफ्टवेयर में बग, या खराब सॉफ्टवेयर संशोधन को इंगित करता है जिसके कारण अमान्य स्नैपशॉट लोड हो गया। इसके परिणामस्वरूप, नोड बंद हो जाएगा और स्नैपशॉट पर निर्मित किसी भी स्थिति का उपयोग करना बंद कर देगा, जिससे चेन की ऊंचाई %d से %d पर रीसेट हो जाएगी। अगली बार पुनः आरंभ करने पर, नोड किसी भी स्नैपशॉट डेटा का उपयोग किए बिना %d से सिंक करना फिर से शुरू कर देगा। कृपया इस घटना की रिपोर्ट %s को करें, जिसमें यह भी शामिल है कि आपने स्नैपशॉट कैसे प्राप्त किया। अमान्य स्नैपशॉट चेनस्टेट को डिस्क पर छोड़ दिया जाएगा, ताकि यह उस समस्या का निदान करने में सहायक हो, जिसके कारण यह त्रुटि हुई।</translation>
    
YES
The translation is mostly accurate but has spacing and formatting errors relating to format specifiers. Specifically, there should be a space after "%s" in the first sentence ("%sविफल रहा" should be "%s विफल रहा"), and the format specifiers (%s, %d) should be preserved exactly as in the source text, matching spacing conventions.

Correct translation:
-assumeutxo snapshot state को सत्यापित करने में %s विफल रहा। यह हार्डवेयर समस्या, या सॉफ्टवेयर में बग, या खराब सॉफ्टवेयर संशोधन को इंगित करता है जिसके कारण अमान्य स्नैपशॉट लोड हो गया। इसके परिणामस्वरूप, नोड बंद हो जाएगा और स्नैपशॉट पर निर्मित किसी भी स्थिति का उपयोग करना बंद कर देगा, जिससे चेन की ऊंचाई %d से %d पर रीसेट हो जाएगी। अगली बार पुनः आरंभ करने पर, नोड किसी भी स्नैपशॉट डेटा का उपयोग किए बिना %d से सिंक करना फिर से शुरू कर देगा। कृपया इस घटना की रिपोर्ट %s को करें, जिसमें यह भी शामिल है कि आपने स्नैपशॉट कैसे प्राप्त किया। अमान्य स्नैपशॉट चेनस्टेट को डिस्क पर छोड़ दिया जाएगा, जिससे यह उस समस्या का निदान करने में सहायक हो सकता है, जिसके कारण यह त्रुटि हुई।
```

```
        <source>%s request to listen on port %u. This port is considered "bad" and thus it is unlikely that any peer will connect to it. See doc/p2p-bad-ports.md for details and a full list.</source>
        <translation>%s अनुरोध %u पोर्ट पर सुनने का. इस बंदरगाह को "खराब" माना जाता है और इस प्रकार यह संभावना नहीं है कि कोई भी सहकर्मी इससे जुड़ेगा। विवरण और पूरी सूची के लिए doc/p2p-bad-ports.md देखें।</translation>
    
YES
There are issues with the translation:
1. The translation of "port" as "बंदरगाह" is inaccurate in this context. In computing, "port" should be translated as "पोर्ट".
2. The sentence structure is somewhat awkward with "अनुरोध %u पोर्ट पर सुनने का". It should follow the original sentence structure.
3. The format specifiers %s and %u are preserved but the sentence is not smooth in Hindi and is missing the correct auxiliary verbs.

Correct translation:
%s ने पोर्ट %u पर सुनने का अनुरोध किया है। इस पोर्ट को "खराब" माना जाता है, इसलिए शायद ही कोई पीयर इससे जुड़ेगा। विवरण और पूरी सूची के लिए doc/p2p-bad-ports.md देखें।
```

```
        <source>%s is set very high! Fees this large could be paid on a single transaction.</source>
        <translation>%sबहुत अधिक निर्धारित है! इतनी बड़ी फीस एक ही लेनदेन पर चुकाई जा सकती है।</translation>
    
YES
There is a missing space between the format specifier '%s' and 'बहुत', which causes a formatting issue. Otherwise, the translation is accurate.

Correct translation:
%s बहुत अधिक निर्धारित है! इतनी बड़ी फीस एक ही लेनदेन पर चुकाई जा सकती है।
```

```
        <source>Block verification was interrupted</source>
        <translation>ब्लॉक verification अन्तरायित हुआ</translation>
    
YES
The translation contains an untranslated English word "verification" and a non-standard translation for "interrupted" ("अन्तरायित" is uncommon; "रोका गया" or "रोक दिया गया" would be better). Also, the wording lacks natural flow.

Correct translation:
ब्लॉक सत्यापन रोका गया था
```

```
        <source>Elliptic curve cryptography sanity check failure. %s is shutting down.</source>
        <translation>Elliptic curve cryptography sanity check विफलता | %sबंद हो रही है |</translation>
    
YES
There are issues with punctuation and spacing. In Hindi, a vertical bar '|' is not standard for separating sentences; use a full stop or '।' (Hindi danda). There is no space between '%s' and 'बंद हो रही है', which can cause readability issues. Also, more natural phrasing would be: 'Elliptic curve cryptography सत्यापन विफल हुआ है। %s बंद हो रही है।'

Correct translation:
Elliptic curve cryptography सत्यापन जांच विफल हुई है। %s बंद हो रही है।
```

```
        <source>Failed to connect best block (%s).</source>
        <translation>best ब्लॉक (%s) से कनेक्ट करने में विफल |</translation>
    
YES  
The translation unnecessarily uses the English word "best" instead of its Hindi equivalent, which should be avoided for clarity and localization. Also, the sentence ends with a pipe (|) instead of the correct Hindi full stop (।). Otherwise, the format specifier is correctly carried over.

Correct translation:  
%s से सर्वश्रेष्ठ ब्लॉक कनेक्ट करने में विफल रहा।
```

```
        <source>Failed to write to block index database.</source>
        <translation>ब्लॉक इंडेक्स डेटाबेस में लिखने में विफल |</translation>
    
YES
The translation is mostly accurate but contains a minor punctuation issue. The Hindi translation uses a vertical bar "|" at the end, which is not standard; the proper sentence terminator in Hindi is the "।" (Danda) or a period (".").

Correct translation:
ब्लॉक इंडेक्स डेटाबेस में लिखने में विफल।
```

```
        <source>Invalid port specified in %s: '%s'</source>
        <translation>में निर्दिष्ट अमान्य पोर्ट %s:'%s'</translation>
    
YES
The translation is awkward and does not follow natural Hindi sentence structure. The phrase "में निर्दिष्ट अमान्य पोर्ट" is an incorrect rearrangement and lacks clarity. Also, proper spacing after format specifiers is missing.

Correct translation:
%s में निर्दिष्ट पोर्ट अमान्य है: '%s'
```

```
        <source>Specified data directory "%s" does not exist.</source>
        <translation>निर्दिष्ट डेटा निर्देशिका "%s" मौजूद नहीं है |</translation>
    
YES
The translation is understandable, but the closing punctuation mark is the wrong character ("|") instead of the appropriate Hindi/Devanagari full stop ("।") or simply a period ("."). Also, stylistically, it is better to end the sentence with a period to match the source.

Correct translation:
निर्दिष्ट डेटा निर्देशिका "%s" मौजूद नहीं है।
```

```
        <source>System error while saving block to disk: %s</source>
        <translation>ब्लॉक को डिस्क पर सहेजते समय सिस्टम error: %s</translation>
    
YES
The translation unnecessarily retains the English word "error" instead of translating it into Hindi. It should also not have awkward spacing. The format specifier %s is correctly retained.

Correct translation:
डिस्क पर ब्लॉक सहेजते समय सिस्टम त्रुटि: %s
```

```
        <source>Error: cannot remove legacy wallet records</source>
        <translation>Error: leagcy वॉलेट रिकॉर्ड को हटाया नहीं जा सकता है</translation>
    
YES
There are several problems:
- The word "Error" is untranslated.
- "leagcy" is a misspelling; correct is "legacy".
- "हटाया नहीं जा सकता है" is a literal passivation, but more natural Hindi would be "हटाए नहीं जा सकते" to match plural "records", or "हटाया नहीं जा सकता" for singular.

Correct translation:
त्रुटि: पुराने वॉलेट रिकॉर्ड को हटाया नहीं जा सकता है
```
</details>

Number of issues: 39.
