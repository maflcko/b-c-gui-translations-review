# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>hi</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bhi%5D%20low%20quality)


```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>पता सूची को %1यहां सहेजने का प्रयास करते समय एक त्रुटि हुई . कृपया पुन: प्रयास करें।</translation>
    
YES
There are spacing issues in the translation: "%1यहां" should have a space between the placeholder %1 and the following word "यहां". Also, the punctuation spacing is inconsistent; there should be no space before the full stop, and "पुन:" should have the correct spacing around the colon.

Correct translation:
पता सूची को %1 यहां सहेजने का प्रयास करते समय एक त्रुटि हुई। कृपया पुन: प्रयास करें।
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>चेतावनी: यदि आप अपना वॉलेट एन्क्रिप्ट करते हैं और अपना पासफ़्रेज़ खो देते हैं, तो आपअपने सभी बिटकॉइन &lt;b&gt; खो देंगे&lt;/b&gt; !</translation>
    
YES
The translation has spacing issues: "आपअपने" should be "आप अपने" (with a space). Also, the placement of the formatting tags and wording can be improved for clarity and correctness.

Correct translation:
चेतावनी: यदि आप अपना वॉलेट एन्क्रिप्ट करते हैं और अपना पासफ़्रेज़ खो देते हैं, तो आप &lt;b&gt; अपने सभी बिटकॉइन खो देंगे &lt;/b&gt;!
```

```
        <source>Banned Until</source>
        <translation>तक प्रतिबंधित</translation>
    
YES  
The translation is incomplete and inaccurate. "Banned Until" means that the ban lasts until a certain time, so the correct Hindi should reflect the "until" aspect, indicating a time limit. The current translation "तक प्रतिबंधित" is missing the beginning and does not make sense on its own.  

Correct translation:  
"प्रतिबंधित तक" or more naturally, "प्रतिबंधित समाप्ति तक" (meaning "Banned until [time]"). Usually in context, "तक" is placed after the time, so "बैनेड तक" is not very natural without a time attached. A more typical phrasing would be:  
"प्रतिबंध की अवधि" (Ban duration) or "प्रतिबंध समाप्ति" (Ban expiration) if context allows, but to be literal:  
"प्रतिबंधित (यहाँ तक)" or "प्रतिबंधित की अवधि"  

However, the best direct translation of "Banned Until" as a label would be:  
"प्रतिबंधित तक"
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>एक आंतरिक त्रुटि हुई। %1सुरक्षित रूप से जारी रखने का प्रयास करेगा। यह एक अप्रत्याशित बग है जिसे नीचे वर्णित के रूप में रिपोर्ट किया जा सकता है।</translation>
    
YES  
There is a missing space after the format specifier %1 (" %1सुरक्षित" should be "%1 सुरक्षित"). The rest of the translation is accurate and appropriate.

Correct translation:  
एक आंतरिक त्रुटि हुई। %1 सुरक्षित रूप से जारी रखने का प्रयास करेगा। यह एक अप्रत्याशित बग है जिसे नीचे वर्णित के रूप में रिपोर्ट किया जा सकता है।
```

```
        <source>Show general overview of wallet</source>
        <translation>वॉलेट का सामान्य अवलोकन दिखाएं |</translation>
    
YES  
The translation is mostly accurate but has an unnecessary trailing space and a vertical bar (|) at the end, which is not present in the source and is inappropriate as punctuation here. It should be removed to match the source's format and punctuation style.

Correct translation:  
वॉलेट का सामान्य अवलोकन दिखाएं
```

```
        <source>Quit application</source>
        <translation> एप्लिकेशन छोड़ें |</translation>
    
YES  
The translation contains a leading space before "एप्लिकेशन" and an unnecessary trailing vertical bar "|" at the end, both of which are formatting issues. Also, a more natural Hindi translation for "Quit application" would be "एप्लिकेशन बंद करें" or "एप्लिकेशन छोड़ें" without extra punctuation.

Correct translation:  
एप्लिकेशन छोड़ें
```

```
        <source>Modify configuration options for %1</source>
        <translation>%1 के लिए विन्यास विकल्प संशोधित करें |</translation>
    
YES  
The translated sentence is mostly correct but the trailing vertical bar "|" is unnecessary and out of place in Hindi punctuation. Removing it improves the naturalness and correctness of the sentence.

Correct translation:  
%1 के लिए विन्यास विकल्प संशोधित करें
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>प्रॉक्सी &lt;b&gt;अक्षम&lt;/b&gt; है: %1</translation>
    
YES
The translation is incorrect because "अक्षम" means "disabled" or "inactive," which is the opposite of "enabled." The correct Hindi translation for "enabled" in this context is "सक्रिय" or "चालू".

Correct translation:
प्रॉक्सी &lt;b&gt;सक्रिय&lt;/b&gt; है: %1
```

```
        <source>Backup wallet to another location</source>
        <translation>किसी अन्य स्थान पर वॉलेट  बैकअप करे |</translation>
    
YES  
The translation is mostly correct in meaning, but there are two issues:  
1. There is an extra space before "बैकअप".  
2. The use of the vertical bar " | " at the end is unnecessary and not typically used in Hindi sentence endings.  

Correct translation:  
किसी अन्य स्थान पर वॉलेट बैकअप करें
```

```
        <source>Options…</source>
        <translation>विकल्प
 </translation>
    
YES
The translation has an unwanted newline and stray space after the word "विकल्प". The source text "Options…" includes an ellipsis, which should be preserved or appropriately represented in Hindi.

Correct translation:
विकल्प…
```

```
        <source>Sends %1 to %2</source>
        <translation>%1 को %2 के पास भेजता है </translation>
    
YES  
The translation has an unnecessary space before the closing punctuation and could be more natural. Also, "के पास" (near) is not typically used for sending to an address in this context. A better translation would simply use "को" to indicate sending to an address or recipient.

Correct translation:  
%1 को %2 भेजता है
```

```
        <source>The BIP324 session ID string in hex.</source>
        <translation>Hex में BIP324 सत्र आई.डी. स्ट्रिंग |</translation>
    
YES  
The translation has an unnecessary pipe character "|" at the end, which is not present in the source and appears to be stray punctuation. Also, "आई.डी." can be better written as "आईडी" without the dots, as it is commonly used. The phrase "string" can be translated to "स्ट्रिंग" or "स्ट्रिंग" is acceptable in technical context, but to keep consistency, transliteration is fine.

Correct translation:  
Hex में BIP324 सत्र आईडी स्ट्रिंग।
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>हमारे मेमपूल में स्वीकार किए गए एक उपन्यास लेनदेन के बाद से इस सहकर्मी से प्राप्त हुआ समय बीत चुका है।</translation>
    
YES  
The Hindi translation is awkward and incorrect for the context. The phrase "एक उपन्यास लेनदेन" incorrectly translates "a novel transaction" literally, where "novel" here means "new" or "recent," not "a novel" as in literature. Additionally, the sentence structure is unnatural and confusing. A better translation would convey the elapsed time since a new transaction was received from this peer for the mempool.

Correct translation:  
"इस सहकर्मी से हमारे मेमपूल में स्वीकार किए गए एक नए लेनदेन के प्राप्त होने के बाद से बीता हुआ समय।"
```

```
        <source>Open</source>
        <translation>खुला हुआ</translation>
    
YES  
The translation "खुला हुआ" means "open" in the sense of "opened" or "that which has been opened," which is a past participle form and does not suit the context if "Open" is used as a command or a label (e.g., a button or menu item). The correct translation for the imperative or label "Open" in Hindi would be simply:

खोलें
```

```
        <source>Clear</source>
        <translation>क्लिअर </translation>
    
YES  
The translation "क्लिअर " is a transliteration of the English word "Clear" rather than a proper Hindi translation. Also, there is an extra trailing space after the word. The correct Hindi translation should be:

"साफ़ करें"
```

```
        <source>Could not generate new %1 address</source>
        <translation>नया पता उत्पन्न नहीं कर सका %1 </translation>
    
YES  
The position of the format specifier %1 is incorrect and the sentence structure is unnatural in Hindi. The %1 should come before "पता" to correctly indicate "new %1 address". Also, there is an extra space at the end.  

Correct translation:  
"नया %1 पता उत्पन्न नहीं कर सका"
```

```
        <source>Copy Address</source>
        <translation>कॉपी  अड्रेस</translation>
    
YES  
The translation uses a double space between "कॉपी" and "अड्रेस," which is a formatting issue. Additionally, while "अड्रेस" is a transliteration of "address," a more commonly used and semantically accurate Hindi term is "पता" especially in the Bitcoin context.

Correct translation:  
कॉपी पता
```

```
        <source>Verify this address on e.g. a hardware wallet screen</source>
        <translation>इस पते को वेरीफाय करें उदा.  एक हार्डवेयर वॉलेट स्क्रीन</translation>
    
YES  
The translation mixes English ("वेरीफाय", "उदा.") unnecessarily, and lacks proper conjunction or punctuation to connect the parts naturally. The phrase "e.g." should be translated as "जैसे कि" or "उदाहरण के लिए" and the sentence should be more fluent.

Correct translation:  
"इस पते को, जैसे कि हार्डवेयर वॉलेट स्क्रीन पर, सत्यापित करें"
```

```
        <source>Add Recipient</source>
        <translation>अड रिसिपिएंट</translation>
    
YES  
The translation uses English words written in Devanagari script and is not a proper Hindi translation. It should be translated into proper Hindi.  

Correct translation:  
प्राप्तकर्ता जोड़ें
```

```
        <source>Creates a Partially Signed Bitcoin Transaction (PSBT) for use with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <translation>उदाहरण के लिए उपयोग के लिए आंशिक रूप से हस्ताक्षरित बिटकॉइन लेनदेन (PSBT) बनाता है। एक ऑफ़लाइन% 1 %1  वॉलेट, या एक PSBT-संगत हार्डवेयर वॉलेट।</translation>
    
YES  
The translation has multiple issues:  
- Incorrect spacing around the format specifier "%1" (should be without a space, i.e., "ऑफ़लाइन%1" → "ऑफ़लाइन %1")  
- Repetition of "%1" twice is incorrect.  
- The sentence structure is broken and fragmented due to the misplaced period after "बनाता है।" leading to two incomplete sentences.  
- The Hindi translation is not fully coherent and natural.

Correct translation:  
उदाहरण के लिए, ऑफ़लाइन %1 वॉलेट या PSBT-संगत हार्डवेयर वॉलेट के साथ उपयोग के लिए आंशिक रूप से हस्ताक्षरित बिटकॉइन लेनदेन (PSBT) बनाता है।
```

```
        <source>%1 to '%2'</source>
        <translation>%1टु '%2'</translation>
    
YES  
The translation incorrectly transliterates "to" as "टु" which is not appropriate in this context. The correct Hindi preposition for "to" in this phrase is "से" or the word "से" can be omitted if the phrase represents a range or direction and left as "to" in English within quotes is also acceptable if no natural Hindi equivalent fits. Given the context, the proper approach is to use the English word "to" without transliteration or replace it with the Hindi equivalent "से" with proper spacing.

Also, there is no space between %1 and "टु".

Correct translation:  
%1 से '%2'  
OR  
%1 to '%2'  (if preferred to keep "to" in English)
```

```
        <source>PSBT saved</source>
        <extracomment>Popup message when a PSBT has been saved to a file</extracomment>
        <translation>पीएसबीटी सहेजा गया
 </translation>
    
YES  
The translation contains an unnecessary trailing whitespace/newline after "पीएसबीटी सहेजा गया" which could cause formatting issues. Also, a more common and clear Hindi phrasing would be "PSBT सहेजा गया" (keeping "PSBT" as is, since it is an acronym) or "PSBT सुरक्षित किया गया" if a more formal tone is desired. The current translation is comprehensible but can be improved by removing extraneous whitespace and standardizing the script usage.

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
The translation "अहस्ताक्षरित लेनदेन" is correct for "Unsigned Transaction," but there is an unwanted trailing whitespace (a non-breaking space) at the end of the translation after "लेनदेन". This stray space should be removed to maintain formatting consistency.

Correct translation:
अहस्ताक्षरित लेनदेन
```

```
        <source>The total exceeds your balance when the %1 transaction fee is included.</source>
        <translation> %1 जब लेन-देन शुल्क शामिल किया जाता है, तो कुल आपकी शेष राशि से अधिक हो जाती है।</translation>
    
YES  
There is an unwanted leading space before "%1" in the translation, and the sentence structure can be improved for better clarity and natural flow in Hindi. Also, the placement of "%1" is correct but should not have a leading space.

Correct translation:  
"%1 लेन-देन शुल्क शामिल होने पर कुल आपकी शेष राशि से अधिक हो जाता है।"
```

```
        <source>Verify Message</source>
        <translation>सत्यापित करें और संदेश</translation>
    
YES  
The translation "सत्यापित करें और संदेश" means "Verify and message," which is incorrect. The correct translation for "Verify Message" should be "संदेश सत्यापित करें".

Correct translation:  
संदेश सत्यापित करें
```

```
        <source>The entered address does not refer to a legacy (P2PKH) key. Message signing for SegWit and other non-P2PKH address types is not supported in this version of %1. Please check the address and try again.</source>
        <translation>दर्ज किया गया पता किसी लीगेसी (P2PKH) कुंजी को संदर्भित नहीं करता है। SegWit और अन्य गैर-P2PKH पता प्रकारों के लिए संदेश हस्ताक्षर %1 के इस संस्करण में समर्थित नहीं है | कृपया पते की जांच करें और पुनः प्रयास करें।</translation>
    
YES
The translation uses an incorrect symbol "|" instead of a proper sentence-ending punctuation mark. Also, the phrase "संदेश हस्ताक्षर" should be "संदेश पर हस्ताक्षर" for better clarity in Hindi. Here is the corrected translation:

दर्ज किया गया पता किसी लीगेसी (P2PKH) कुंजी को संदर्भित नहीं करता है। SegWit और अन्य गैर-P2PKH पता प्रकारों के लिए संदेश पर हस्ताक्षर %1 के इस संस्करण में समर्थित नहीं हैं। कृपया पते की जांच करें और पुनः प्रयास करें।
```

```
        <source>kB/s</source>
        <translation>kB/s </translation>
    
YES
There is an extra trailing whitespace in the translation ("kB/s ") which should be removed to match the source exactly.

Correct translation:
kB/s
```

```
        <source>conflicted with a transaction with %1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that conflicts with a confirmed transaction.</extracomment>
        <translation> %1 पुष्टिकरण के साथ लेन-देन के साथ विरोधाभासी</translation>
    
YES  
The translated text has an extra space at the beginning which should be removed, and the phrase sounds a bit unnatural in Hindi. A clearer and more natural translation would be:  

Correct translation:  
%1 पुष्टिकरणों के साथ लेन-देन के साथ टकराव हुआ
```

```
        <source>Source</source>
        <translation>सॉSस</translation>
    
YES  
The translation "सॉSस" is incorrect and looks like a mistyped or corrupted form of the word. The correct Hindi translation for "Source" in the Bitcoin context (such as source of funds, or source address) is "स्रोत".  

Correct translation:  
स्रोत
```

```
        <source>Debit</source>
        <translation>जमा</translation>
    
YES  
The English term "Debit" refers to an outgoing amount, such as money spent or deducted, while the Hindi translation "जमा" means "Deposit," which is the opposite meaning. The correct Hindi translation for "Debit" in this context would be "डेबिट" or "निकासी".  

Correct translation:  
डेबिट
```

```
        <source>Abandoned</source>
        <translation>छोड़ दिया </translation>
    
YES  
The translation has an extra trailing space after "छोड़ दिया" which should be removed to avoid whitespace issues. Also, "छोड़ दिया" is an acceptable and common translation for "Abandoned" in this context.

Correct translation:  
छोड़ दिया
```

```
        <source>Confirmed (%1 confirmations)</source>
        <translation>की पुष्टि की (%1 पुष्टिकरण)</translation>
    
YES  
The Hindi translation is incorrect and awkwardly phrased. The phrase "की पुष्टि की" is grammatically wrong and incomplete. A correct and natural translation for "Confirmed (%1 confirmations)" would be:

"पुष्ट (%1 पुष्टिकरण)"
```

```
        <source>Conflicted</source>
        <translation>एक दूसरे के विरोध में</translation>
    
YES
The translation "एक दूसरे के विरोध में" literally means "against each other" or "in opposition to each other," which is too verbose and not appropriate for the context of "Conflicted" in Bitcoin terminology. In this context, "Conflicted" usually refers to a transaction or state that conflicts with another, so a more concise and accurate Hindi term would be "विवादित" or "टकराव."

Correct translation:
विवादित
```

```
        <source>Signer error</source>
        <translation>Signer error/हस्ताक्षरकर्ता त्रुटि</translation>
    
YES
The translation mixes English and Hindi unnecessarily. It should be fully translated into Hindi for clarity and consistency.

Correct translation:
हस्ताक्षרकर्ता त्रुटि
```

```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>-assumeutxo snapshot state को सत्यापित करने में %sविफल रहा |  यह हार्डवेयर समस्या, या सॉफ्टवेयर में बग, या खराब सॉफ्टवेयर संशोधन को इंगित करता है जिसके कारण अमान्य स्नैपशॉट लोड हो गया। इसके परिणामस्वरूप, नोड बंद हो जाएगा और स्नैपशॉट पर निर्मित किसी भी स्थिति का उपयोग करना बंद कर देगा, जिससे चेन की ऊंचाई %d से %d पर रीसेट हो जाएगी। अगली बार पुनः आरंभ करने पर, नोड किसी भी स्नैपशॉट डेटा का उपयोग किए बिना %d से सिंक करना फिर से शुरू कर देगा। कृपया इस घटना की रिपोर्ट %s को करें, जिसमें यह भी शामिल है कि आपने स्नैपशॉट कैसे प्राप्त किया। अमान्य स्नैपशॉट चेनस्टेट को डिस्क पर छोड़ दिया जाएगा, ताकि यह उस समस्या का निदान करने में सहायक हो, जिसके कारण यह त्रुटि हुई।</translation>
    
YES
There are spacing issues around "%s" after "में" ("%sविफल" should be "%s विफल"). Also, a few Hindi stylistic improvements can be made for clarity and consistency:

Correct translation:
-assumeutxo snapshot state को सत्यापित करने में %s विफल रहा। यह हार्डवेयर समस्या, सॉफ़्टवेयर में बग, या कोई खराब सॉफ़्टवेयर संशोधन है जिसके कारण अमान्य स्नैपशॉट लोड हो गया। इसके परिणामस्वरूप, नोड shutdown हो जाएगा और स्नैपशॉट पर निर्मित किसी भी स्थिति का उपयोग करना बंद कर देगा, जिससे चेन की ऊंचाई %d से %d पर रीसेट हो जाएगी। अगली बार पुनः आरंभ करने पर, नोड बिना किसी स्नैपशॉट डेटा के %d से सिंक करना फिर से शुरू करेगा। कृपया इस घटना की रिपोर्ट %s को करें, जिसमें यह भी शामिल हो कि आपने स्नैपशॉट कैसे प्राप्त किया। अमान्य स्नैपशॉट चेनस्टेट डिस्क पर छोड़ दिया जाएगा ताकि यह उस समस्या के निदान में सहायक हो, जिसके कारण यह त्रुटि हुई।
```

```
        <source>%s request to listen on port %u. This port is considered "bad" and thus it is unlikely that any peer will connect to it. See doc/p2p-bad-ports.md for details and a full list.</source>
        <translation>%s अनुरोध %u पोर्ट पर सुनने का. इस बंदरगाह को "खराब" माना जाता है और इस प्रकार यह संभावना नहीं है कि कोई भी सहकर्मी इससे जुड़ेगा। विवरण और पूरी सूची के लिए doc/p2p-bad-ports.md देखें।</translation>
    
YES
The translation incorrectly translates "port" as "बंदरगाह," which typically means a seaport or harbor in Hindi, not a network port. The correct term for a network port in this context is "पोर्ट." Also, the phrase "सुनने का" is incomplete and unnatural; it should be "सुनने का अनुरोध" or "सुनने के लिए अनुरोध." The rest of the translation is mostly accurate but could be made more fluent.

Correct translation:
%s %u पोर्ट पर सुनने के लिए अनुरोध। इस पोर्ट को "खराब" माना जाता है और इसलिए संभावना नहीं है कि कोई भी सहकर्मी इससे जुड़ेगा। विवरण और पूरी सूची के लिए doc/p2p-bad-ports.md देखें।
```

```
        <source>Error loading wallet. Wallet requires blocks to be downloaded, and software does not currently support loading wallets while blocks are being downloaded out of order when using assumeutxo snapshots. Wallet should be able to load successfully after node sync reaches height %s</source>
        <translation>बटुआ लोड करने में त्रुटि. वॉलेट को डाउनलोड करने के लिए ब्लॉक की आवश्यकता होती है, और सॉफ्टवेयर वर्तमान में लोडिंग वॉलेट का समर्थन नहीं करता है, जबकि ब्लॉक्स को ऑर्डर से बाहर डाउनलोड किया जा रहा है, जब ग्रहणुत्सो स्नैपशॉट का उपयोग किया जाता है। नोड सिंक के %s ऊंचाई तक पहुंचने के बाद वॉलेट को सफलतापूर्वक लोड करने में सक्षम होना चाहिए</translation>
    
YES
The translation contains literal and awkward phrases that do not read naturally in Hindi, and some key technical terms are mistransliterated or unclear ("ग्रहणुत्सो" should be "assumeutxo", transliterated accurately). Also, the sentence structure is confusing and the word "वॉलेट" and "बटुआ" are inconsistently used (should stick to one term, preferably "वॉलेट" as it is widely used in cryptocurrency context). The phrase "ब्लॉक्स को ऑर्डर से बाहर डाउनलोड किया जा रहा है" can be improved for clarity.

Correct translation:
बटुआ लोड करने में त्रुटि। वॉलेट को ब्लॉकों को डाउनलोड करने की आवश्यकता है, और सॉफ़्टवेयर वर्तमान में assumeutxo स्नैपशॉट्स का उपयोग करते समय ब्लॉकों को असंकुलित क्रम में डाउनलोड किए जाने पर वॉलेट लोड करने का समर्थन नहीं करता है। नोड सिंक जब %s हाइट तक पहुँच जाएगा, तब वॉलेट सफलतापूर्वक लोड हो जाना चाहिए।
```

```
        <source>%s is set very high! Fees this large could be paid on a single transaction.</source>
        <translation>%sबहुत अधिक निर्धारित है! इतनी बड़ी फीस एक ही लेनदेन पर चुकाई जा सकती है।</translation>
    
YES  
There is a missing space after the format specifier %s, causing it to run into the following word. Also, "फीस" can be better translated as "शुल्क" in this formal context. 

Correct translation:  
%s बहुत अधिक निर्धारित है! इतनी बड़ी शुल्क एक ही लेनदेन पर चुकाई जा सकती है।
```

```
        <source>Maximum transaction weight is too low, can not accommodate change output</source>
        <translation>अधिकतम लेनदेन भार बहुत कम है, change output को समायोजित नहीं कर सकता</translation>
    
YES  
The translation mixes Hindi and English unnecessarily by keeping "change output" in English, which is inconsistent and can confuse the reader. It should be fully translated into Hindi, maintaining technical terms in a way that is commonly used or understood by the target audience. Also, the sentence should be grammatically appropriate and natural in Hindi.

Correct translation:  
अधिकतम लेनदेन भार बहुत कम है, इसलिए छुट देय राशि (चेंज आउटपुट) को समायोजित नहीं किया जा सकता है।
```

```
        <source>Block verification was interrupted</source>
        <translation>ब्लॉक verification अन्तरायित हुआ</translation>
    
YES  
The translation mixes Hindi and English unnecessarily. The word "verification" should be translated into Hindi for consistency and clarity. Also, "interrupted" is better translated as "रुका" or "रोक दिया गया" in this context. A more natural and accurate Hindi translation would be:

ब्लॉक सत्यापन रुक गया
```

```
        <source>Elliptic curve cryptography sanity check failure. %s is shutting down.</source>
        <translation>Elliptic curve cryptography sanity check विफलता | %sबंद हो रही है |</translation>
    
YES  
The Hindi translation mixes English and Hindi inconsistently and uses the wrong punctuation ("|") instead of appropriate Hindi punctuation (e.g., "।"). Also, spacing issues are present between "%s" and surrounding words.

Correct translation:  
Elliptic curve cryptography sanity check विफलता। %s बंद हो रहा है।
```

```
        <source>Error: Unable to write watchonly wallet best block locator record</source>
        <translation>त्रुटि: watchonly वॉलेट best  ब्लॉक लोकेटर रिकॉर्ड लिखने में असमर्थ</translation>
    
YES  
The translation mixes English and Hindi unnecessarily and awkwardly. Terms like "watchonly," "best," and "ब्लॉक लोकेटर रिकॉर्ड" should either be fully translated or transliterated consistently. Also, "watchonly" is a technical term that can be transliterated or explained better. The word "best" should be translated as "श्रेष्ठ" or omitted if it refers to a specific term known in English.

A better translation would be:  
"त्रुटि: watchonly वॉलेट के सर्वश्रेष्ठ ब्लॉक लोकेटर रिकॉर्ड को लिखने में असमर्थ"
```

```
        <source>Failed to connect best block (%s).</source>
        <translation>best ब्लॉक (%s) से कनेक्ट करने में विफल |</translation>
    
YES  
The translation mixes English and Hindi unnaturally by using "best" in English and "ब्लॉक" transliterated, which can be confusing. Also, the vertical bar '|' at the end is unnecessary and not used in the original sentence. A more natural and accurate Hindi translation would fully translate the phrase and follow natural Hindi grammar.

Correct translation:  
"सर्वश्रेष्ठ ब्लॉक (%s) से कनेक्ट करने में विफल।"
```

```
        <source>Failed to read block.</source>
        <translation>ब्लॉक पढ़ने में विफल |</translation>
    
YES  
The translation contains an incorrect punctuation mark. The source sentence ends with a period ('.'), but the translation ends with a vertical bar (|). Also, there is an extra space before the punctuation in Hindi which is not standard.

Correct translation:  
ब्लॉक पढ़ने में विफल।
```

```
        <source>Failed to write to block index database.</source>
        <translation>ब्लॉक इंडेक्स डेटाबेस में लिखने में विफल |</translation>
    
YES  
The translation contains an incorrect trailing pipe symbol "|" which is unnecessary and incorrect punctuation in Hindi. Also, it would be better to use a full stop (।) instead of pipe or no punctuation if the source has a period.

Correct translation:  
ब्लॉक इंडेक्स डेटाबेस में लिखने में विफल।
```

```
        <source>Invalid port specified in %s: '%s'</source>
        <translation>में निर्दिष्ट अमान्य पोर्ट %s:'%s'</translation>
    
YES  
The Hindi translation is incorrect and has incorrect word order, missing some words needed for clarity, and improper placement of format specifiers. The original source states "Invalid port specified in %s: '%s'", meaning "%s" represents a location ("in %s"), so it should appear properly in the sentence.

Correct translation:  
"%s में निर्दिष्ट अमान्य पोर्ट: '%s'"
```

```
        <source>Signer did not echo address</source>
        <translation>Signer ने पता की echo नहीं की</translation>
    
YES  
The Hindi translation mixes English and Hindi improperly and uses "echo" without translation, which is uncommon in Hindi technical translations. A more natural and accurate translation would be:  
"सिग्नर ने पता पुनः नहीं दिखाया"
```

```
        <source>Specified data directory "%s" does not exist.</source>
        <translation>निर्दिष्ट डेटा निर्देशिका "%s" मौजूद नहीं है |</translation>
    
YES  
The Hindi translation uses a vertical bar " | " at the end, which is unnecessary and incorrect punctuation in this context. Also, a period (।) should be used instead of a vertical bar to properly end the sentence.  

Correct translation:  
निर्दिष्ट डेटा निर्देशिका "%s" मौजूद नहीं है।
```

```
        <source>System error while saving block to disk: %s</source>
        <translation>ब्लॉक को डिस्क पर सहेजते समय सिस्टम error: %s</translation>
    
YES  
The translation mixes English and Hindi unnecessarily by using the English word "error" instead of the Hindi equivalent "त्रुटि". The correct and more natural translation would be:  
ब्लॉक को डिस्क पर सहेजते समय सिस्टम त्रुटि: %s
```

```
        <source>Error: cannot remove legacy wallet records</source>
        <translation>Error: leagcy वॉलेट रिकॉर्ड को हटाया नहीं जा सकता है</translation>
    
YES  
The translation contains a typo in the word "legacy" (spelled as "leagcy") and mixes English and Hindi unnecessarily. It is better to fully translate the word "Error" as well for consistency. Also, "wallet" is commonly transliterated as "वॉलेट" which is acceptable, and the rest is correctly translated.

Correct translation:  
त्रुटि: पारंपरिक वॉलेट रिकॉर्ड हटाए नहीं जा सकते हैं
```

```
        <source>Settings file could not be read</source>
        <translation>सेटिंग्स फ़ाइल को पढ़ा नहीं जा सका |</translation>
    
YES  
The translation includes an unnecessary trailing space before the vertical bar (|) and uses a vertical bar improperly at the end, which is not standard punctuation in Hindi. Also, the translation is understandable but could be made more natural by replacing "सेटिंग्स फ़ाइल" with a more Hindi-friendly term or keeping it as is since "सेटिंग्स" is commonly used in software contexts. The vertical bar should be removed.

Correct translation:  
सेटिंग्स फ़ाइल को पढ़ा नहीं जा सका।
```

```
        <source>Settings file could not be written</source>
        <translation>सेटिंग्स फ़ाइल नहीं लिखी जा सकी |</translation>
    
YES  
The translation contains an unnecessary trailing vertical bar "|" which is not present in the source text and is not appropriate here. Also, to improve clarity and fluency, it is better to translate as: "सेटिंग्स फ़ाइल नहीं लिखी जा सकी।" (with a proper Hindi full stop).  

Correct translation:  
सेटिंग्स फ़ाइल नहीं लिखी जा सकी।
```
</details>
