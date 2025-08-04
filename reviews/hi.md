# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>hi</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bhi%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation>पते या लेबल में बदलाव करने के लिए राइट-क्लिक करें</translation>
    
YES, The translation incorrectly uses the word "बदलाव" (badlav), which means "change" or "alteration", instead of "संपादित" (sampadit) which means "edit". This makes the translation inaccurate in the context of editing an address or label.
Correct translation: पते या लेबल को संपादित करने के लिए राइट-क्लिक करें
```

```
        <source>New</source>
        <translation>नया </translation>
    
YES
The translation contains trailing whitespace.
<source>New</source>
<translation>नया</translation>
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>पता सूची को %1यहां सहेजने का प्रयास करते समय एक त्रुटि हुई . कृपया पुन: प्रयास करें।</translation>
    
YES, The Hindi translation is incorrect and includes extraneous words. The word "यहां" (here) is not present in the source text and makes the translation nonsensical. The spacing around "%1" is also incorrect.

NO, There was an error trying to save the address list to %1. Please try again.
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>चेतावनी: यदि आप अपना वॉलेट एन्क्रिप्ट करते हैं और अपना पासफ़्रेज़ खो देते हैं, तो आपअपने सभी बिटकॉइन &lt;b&gt; खो देंगे&lt;/b&gt; !</translation>
    
YES, The translation has a spacing error. There should be a space between "आप" and "अपने".
Correct translation: चेतावनी: यदि आप अपना वॉलेट एन्क्रिप्ट करते हैं और अपना पासफ़्रेज़ खो देते हैं, तो आप अपने सभी बिटकॉइन &lt;b&gt; खो देंगे&lt;/b&gt; !
```

```
        <source>Banned Until</source>
        <translation>तक प्रतिबंधित</translation>
    
YES, The translation is missing the word "Banned" which is important in this context.
Correct translation: <translation>तब तक प्रतिबंधित</translation>
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>एक आंतरिक त्रुटि हुई। %1सुरक्षित रूप से जारी रखने का प्रयास करेगा। यह एक अप्रत्याशित बग है जिसे नीचे वर्णित के रूप में रिपोर्ट किया जा सकता है।</translation>
    
YES - The format specifier %1 is incorrectly placed in the translation. It should be placed immediately after the word "प्रयास करेगा" to correctly reflect the English source.

एक आंतरिक त्रुटि हुई। %1 सुरक्षित रूप से जारी रखने का प्रयास करेगा। यह एक अप्रत्याशित बग है जिसे नीचे वर्णित के रूप में रिपोर्ट किया जा सकता है।
```

```
        <source>Quit application</source>
        <translation> एप्लिकेशन छोड़ें |</translation>
    
YES. The translation contains extraneous characters and lacks proper word separation.
एप्लिकेशन छोड़ें
```

```
        <source>Modify configuration options for %1</source>
        <translation>%1 के लिए विन्यास विकल्प संशोधित करें |</translation>
    
YES, The translation contains an extra pipe character at the end.
%1 के लिए विन्यास विकल्प संशोधित करें
```

```
        <source>Minimize</source>
        <translation>मिनीमाइज़</translation>
    
YES, The translation is problematic as it is a direct transliteration of the English word "Minimize" into Devanagari script and does not convey the intended meaning in Hindi. In the context of Bitcoin, "Minimize" would likely refer to reducing something or making it smaller, for which there are appropriate Hindi words.

Correct translation: कम करें (Kam Karen)
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>प्रॉक्सी &lt;b&gt;अक्षम&lt;/b&gt; है: %1</translation>
    
YES, The translation is incorrect and uses the wrong word for "enabled". The word "अक्षम" means "disabled" instead of "enabled".
The correct translation is: प्रॉक्सी &lt;b&gt;सक्षम&lt;/b&gt; है: %1
```

```
        <source>Backup wallet to another location</source>
        <translation>किसी अन्य स्थान पर वॉलेट  बैकअप करे |</translation>
    
YES: The translation uses a pipe symbol (|) at the end of the sentence which is not present in the source text. The word "बैकअप" is also an English word that is not translated to Hindi.

Correct translation: किसी अन्य स्थान पर वॉलेट का बैकअप लें
```

```
        <source>Options…</source>
        <translation>विकल्प
 </translation>
    
YES, The translation has a stray space at the end.
विकल्प…
```

```
        <source>Sends %1 to %2</source>
        <translation>%1 को %2 के पास भेजता है </translation>
    
YES, The translation is problematic because of extra space before "के पास".
%1 को %2 के पास भेजता है
```

```
        <source>The BIP324 session ID string in hex.</source>
        <translation>Hex में BIP324 सत्र आई.डी. स्ट्रिंग |</translation>
    
YES - The "|" at the end of the translation is an extraneous character.
Hex में BIP324 सत्र आई.डी. स्ट्रिंग
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>हमारे मेमपूल में स्वीकार किए गए एक उपन्यास लेनदेन के बाद से इस सहकर्मी से प्राप्त हुआ समय बीत चुका है।</translation>
    
YES - The Hindi translation is grammatically incorrect and awkward. It should be: "हमारे मेमपूल में स्वीकार किए गए एक नए लेनदेन के इस सहकर्मी से प्राप्त होने के बाद से बीता हुआ समय।"
```

```
        <source>Open</source>
        <translation>खुला हुआ</translation>
    
YES, The translation is not accurate. "Open" as a verb should be translated as "खोलें" or "खोलना" in Hindi, whereas "खुला हुआ" translates to "opened" or "is open", which is the past participle or adjective form.

खुला हुआ
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>आउटबाउंड एड्रेस फ़ेच: अल्पकालिक, याचना पतों के लिए</translation>
    
YES: The word "याचना" (yachana) which means "pleading" or "begging" is an inappropriate translation for "soliciting" in this context. "Soliciting" here refers to requesting or asking for addresses.

Correct translation: आउटबाउंड एड्रेस फ़ेच: अल्पकालिक, पते मांगने के लिए
```

```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>%1 आरपीसी कंसोल में आपका स्वागत है।
इतिहास नेविगेट करने के लिए ऊपर और नीचे तीरों का उपयोग करें, और स्क्रीन को साफ़ करने के लिए %2 का उपयोग करें।
फॉन्ट साइज बढ़ाने या घटाने के लिए %3 और %4 का प्रयोग करें।
उपलब्ध कमांड के ओवरव्यू के लिए %5 टाइप करें।
इस कंसोल का उपयोग करने के बारे में अधिक जानकारी के लिए %6 टाइप करें।

%7 चेतावनी: स्कैमर्स सक्रिय हैं, उपयोगकर्ताओं को यहां कमांड टाइप करने के लिए कह रहे हैं, उनके वॉलेट सामग्री को चुरा रहे हैं। कमांड के प्रभाव को पूरी तरह समझे बिना इस कंसोल का उपयोग न करें। %8</translation>
    
YES: The Hindi translation has a grammatical error in the second sentence. The word "इतिहास" (history) should be followed by the postposition "में" (in) for correct grammar. Additionally, the phrase "नेविगेट करने के लिए" (to navigate) is a direct translation and could be more naturally phrased. A more natural phrasing for the entire sentence would be: "इतिहास में नेविगेट करने के लिए ऊपर और नीचे तीरों का प्रयोग करें, और स्क्रीन साफ़ करने के लिए %2 का प्रयोग करें।"

%1 आरपीसी कंसोल में आपका स्वागत है।
इतिहास में नेविगेट करने के लिए ऊपर और नीचे तीरों का प्रयोग करें, और स्क्रीन साफ़ करने के लिए %2 का प्रयोग करें।
फॉन्ट साइज बढ़ाने या घटाने के लिए %3 और %4 का प्रयोग करें।
उपलब्ध कमांड के ओवरव्यू के लिए %5 टाइप करें।
इस कंसोल का उपयोग करने के बारे में अधिक जानकारी के लिए %6 टाइप करें।

%7 चेतावनी: स्कैमर्स सक्रिय हैं, उपयोगकर्ताओं को यहां कमांड टाइप करने के लिए कह रहे हैं, उनके वॉलेट सामग्री को चुरा रहे हैं। कमांड के प्रभाव को पूरी तरह समझे बिना इस कंसोल का उपयोग न करें। %8
```

```
        <source>Clear</source>
        <translation>क्लिअर </translation>
    
YES
The translation has an extra space at the end of the word "क्लिअर".
क्लिअर
```

```
        <source>Could not generate new %1 address</source>
        <translation>नया पता उत्पन्न नहीं कर सका %1 </translation>
    
YES, The translation incorrectly places the format specifier "%1" at the end of the sentence.
Correct translation: नया %1 पता उत्पन्न नहीं कर सका
```

```
        <source>Copy Address</source>
        <translation>कॉपी  अड्रेस</translation>
    
YES
The translation contains an unnecessary space before "अड्रेस".
Correct translation: कॉपी अड्रेस
```

```
        <source>Verify this address on e.g. a hardware wallet screen</source>
        <translation>इस पते को वेरीफाय करें उदा.  एक हार्डवेयर वॉलेट स्क्रीन</translation>
    
YES - The translation is missing the word "on" and the word "e.g." is not translated properly.
The correct translation is "इस पते को हार्डवेयर वॉलेट स्क्रीन जैसी चीज़ पर वेरीफाई करें".
```

```
        <source>Add Recipient</source>
        <translation>अड रिसिपिएंट</translation>
    
YES
The translation is a transliteration and not a translation. The correct translation for "Add Recipient" in Hindi is "प्राप्तकर्ता जोड़ें".
प्राप्तकर्ता जोड़ें
```

```
        <source>Creates a Partially Signed Bitcoin Transaction (PSBT) for use with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <translation>उदाहरण के लिए उपयोग के लिए आंशिक रूप से हस्ताक्षरित बिटकॉइन लेनदेन (PSBT) बनाता है। एक ऑफ़लाइन% 1 %1  वॉलेट, या एक PSBT-संगत हार्डवेयर वॉलेट।</translation>
    
YES. The translation is grammatically incorrect and has duplicate placeholders.
Correct translation: ऑफ़लाइन %1 वॉलेट, या PSBT-संगत हार्डवेयर वॉलेट जैसे उपयोग के लिए आंशिक रूप से हस्ताक्षरित बिटकॉइन लेनदेन (PSBT) बनाता है।
```

```
        <source>%1 to '%2'</source>
        <translation>%1टु '%2'</translation>
    
YES, The Hindi translation is incorrect. The word "टु" is not a valid Hindi word and does not make sense in this context. It seems like an attempt to transliterate "to" but it's done incorrectly.

Correct translation: %1 से '%2'
```

```
        <source>PSBT saved</source>
        <extracomment>Popup message when a PSBT has been saved to a file</extracomment>
        <translation>पीएसबीटी सहेजा गया
 </translation>
    
YES, The trailing whitespace is not correctly handled.
PSBT सहेजा गया
```

```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>रिप्लेसमेंट-बाय-फी, बीआईपी-125 सिग्नलिंग नहीं।</translation>
    
YES, The translation is not grammatically correct. The sentence structure is reversed.

Correct translation: रिप्लेस-बाय-फी, बीआईपी-125 सिग्नलिंग नहीं कर रहा है।
```

```
        <source>Unsigned Transaction</source>
        <comment>PSBT copied</comment>
        <extracomment>Caption of "PSBT has been copied" messagebox</extracomment>
        <translation>अहस्ताक्षरित लेनदेन
 </translation>
    
YES
The translation includes an extra space at the end of the text.
Correct translation: अहस्ताक्षरित लेनदेन
```

```
        <source>The total exceeds your balance when the %1 transaction fee is included.</source>
        <translation> %1 जब लेन-देन शुल्क शामिल किया जाता है, तो कुल आपकी शेष राशि से अधिक हो जाती है।</translation>
    
YES: The translation is problematic because the format specifier %1 is placed incorrectly. It should be placed at the beginning of the sentence as in the source text.
%1 लेन-देन शुल्क सहित, कुल राशि आपकी शेष राशि से अधिक है।
```

```
        <source>Alt+A</source>
        <translation>Alt+A </translation>
    
YES
The translation contains an extraneous space at the end.
Alt+A
```

```
        <source>Alt+P</source>
        <translation>Alt+P </translation>
    
YES, The translation has an extra space at the end.
Alt+P
```

```
        <source>Alt+A</source>
        <translation>Alt+A </translation>
    
YES
The translation contains an extraneous space at the end.
Alt+A
```

```
        <source>Alt+P</source>
        <translation>Alt+P </translation>
    
YES, The translation has an extra space at the end.
Alt+P
```

```
        <source>Verify Message</source>
        <translation>सत्यापित करें और संदेश</translation>
    
YES
The translation is inaccurate and does not convey the intended meaning of "Verify Message". It seems to have translated "Verify" and "Message" separately and combined them incorrectly.

Correct translation: संदेश सत्यापित करें
```

```
        <source>The entered address does not refer to a legacy (P2PKH) key. Message signing for SegWit and other non-P2PKH address types is not supported in this version of %1. Please check the address and try again.</source>
        <translation>दर्ज किया गया पता किसी लीगेसी (P2PKH) कुंजी को संदर्भित नहीं करता है। SegWit और अन्य गैर-P2PKH पता प्रकारों के लिए संदेश हस्ताक्षर %1 के इस संस्करण में समर्थित नहीं है | कृपया पते की जांच करें और पुनः प्रयास करें।</translation>
    
YES: The translation incorrectly uses a pipe symbol "|" instead of a period "." at the end of the sentence.
दर्ज किया गया पता किसी लीगेसी (P2PKH) कुंजी को संदर्भित नहीं करता है। SegWit और अन्य गैर-P2PKH पता प्रकारों के लिए संदेश हस्ताक्षर %1 के इस संस्करण में समर्थित नहीं है। कृपया पते की जांच करें और पुनः प्रयास करें।
```

```
        <source>kB/s</source>
        <translation>kB/s </translation>
    
YES
The translation has an extra space at the end.
Correct translation: kB/s
```

```
        <source>conflicted with a transaction with %1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that conflicts with a confirmed transaction.</extracomment>
        <translation> %1 पुष्टिकरण के साथ लेन-देन के साथ विरोधाभासी</translation>
    
YES
The translation uses an incorrect word for "conflicted". The correct word in Hindi would be "टकराव" (takrav) or "विरोधाभासी" (virodhabhasi).

%1 पुष्टि के साथ लेन-देन से टकराव
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/अपुष्ट</translation>
    
YES
The Hindi translation is incorrect. The source text "%1/unconfirmed" indicates a transaction that has been confirmed in at least one block but less than six blocks. The provided translation "%1/अपुष्ट" translates to "%1/unconfirmed" in a general sense but doesn't specifically convey the nuances of Bitcoin transaction confirmations.

A more accurate translation for this specific context would be:
%1/अपुष्ट
```

```
        <source>Source</source>
        <translation>सॉSस</translation>
    
YES
The translation is nonsensical and appears to be a phonetic misspelling of "Source".
Correct translation: स्रोत
```

```
        <source>Debit</source>
        <translation>जमा</translation>
    
YES, The translation is incorrect. "Debit" in the context of financial transactions means withdrawing money, while the translation "जमा" means "credit" or "deposit". The correct translation for "Debit" in Hindi is "डेबिट" or "नाम".

Correct translation: डेबिट
```

```
        <source>Abandoned</source>
        <translation>छोड़ दिया </translation>
    
YES, The translation is problematic. There is an extra space at the end of the translation.
Correct translation: छोड़ दिया
```

```
        <source>Confirmed (%1 confirmations)</source>
        <translation>की पुष्टि की (%1 पुष्टिकरण)</translation>
    
YES, the translation is problematic. The word "की" (ki) is a feminine possessive marker and is used incorrectly here. It should be removed.

NO
```

```
        <source>Conflicted</source>
        <translation>एक दूसरे के विरोध में</translation>
    
YES
The translation "एक दूसरे के विरोध में" (ek doosre ke virodh mein) means "in opposition to each other". In the context of Bitcoin, "Conflicted" refers to a transaction that has been double-spent or is in a state of conflict on the blockchain. A more appropriate translation would be "टकराव" (takrav), which means conflict or collision.
Correct translation: टकराव
```

```
        <source>Signer error</source>
        <translation>Signer error/हस्ताक्षरकर्ता त्रुटि</translation>
    
YES
The translation includes an English phrase "Signer error/" which should not be present in the Hindi translation. The correct translation is:
हस्ताक्षरकर्ता त्रुटि
```

```
        <source>%s failed to validate the -assumeutxo snapshot state. This indicates a hardware problem, or a bug in the software, or a bad software modification that allowed an invalid snapshot to be loaded. As a result of this, the node will shut down and stop using any state that was built on the snapshot, resetting the chain height from %d to %d. On the next restart, the node will resume syncing from %d without using any snapshot data. Please report this incident to %s, including how you obtained the snapshot. The invalid snapshot chainstate will be left on disk in case it is helpful in diagnosing the issue that caused this error.</source>
        <translation>-assumeutxo snapshot state को सत्यापित करने में %sविफल रहा |  यह हार्डवेयर समस्या, या सॉफ्टवेयर में बग, या खराब सॉफ्टवेयर संशोधन को इंगित करता है जिसके कारण अमान्य स्नैपशॉट लोड हो गया। इसके परिणामस्वरूप, नोड बंद हो जाएगा और स्नैपशॉट पर निर्मित किसी भी स्थिति का उपयोग करना बंद कर देगा, जिससे चेन की ऊंचाई %d से %d पर रीसेट हो जाएगी। अगली बार पुनः आरंभ करने पर, नोड किसी भी स्नैपशॉट डेटा का उपयोग किए बिना %d से सिंक करना फिर से शुरू कर देगा। कृपया इस घटना की रिपोर्ट %s को करें, जिसमें यह भी शामिल है कि आपने स्नैपशॉट कैसे प्राप्त किया। अमान्य स्नैपशॉट चेनस्टेट को डिस्क पर छोड़ दिया जाएगा, ताकि यह उस समस्या का निदान करने में सहायक हो, जिसके कारण यह त्रुटि हुई।</translation>
    
YES
The format specifier %s is missing a space after it.
-assumeutxo snapshot state को सत्यापित करने में %s विफल रहा | यह हार्डवेयर समस्या, या सॉफ्टवेयर में बग, या खराब सॉफ्टवेयर संशोधन को इंगित करता है जिसके कारण अमान्य स्नैपशॉट लोड हो गया। इसके परिणामस्वरूप, नोड बंद हो जाएगा और स्नैपशॉट पर निर्मित किसी भी स्थिति का उपयोग करना बंद कर देगा, जिससे चेन की ऊंचाई %d से %d पर रीसेट हो जाएगी। अगली बार पुनः आरंभ करने पर, नोड किसी भी स्नैपशॉट डेटा का उपयोग किए बिना %d से सिंक करना फिर से शुरू कर देगा। कृपया इस घटना की रिपोर्ट %s को करें, जिसमें यह भी शामिल है कि आपने स्नैपशॉट कैसे प्राप्त किया। अमान्य स्नैपशॉट चेनस्टेट को डिस्क पर छोड़ दिया जाएगा, ताकि यह उस समस्या का निदान करने में सहायक हो, जिसके कारण यह त्रुटि हुई।
```

```
        <source>Error loading wallet. Wallet requires blocks to be downloaded, and software does not currently support loading wallets while blocks are being downloaded out of order when using assumeutxo snapshots. Wallet should be able to load successfully after node sync reaches height %s</source>
        <translation>बटुआ लोड करने में त्रुटि. वॉलेट को डाउनलोड करने के लिए ब्लॉक की आवश्यकता होती है, और सॉफ्टवेयर वर्तमान में लोडिंग वॉलेट का समर्थन नहीं करता है, जबकि ब्लॉक्स को ऑर्डर से बाहर डाउनलोड किया जा रहा है, जब ग्रहणुत्सो स्नैपशॉट का उपयोग किया जाता है। नोड सिंक के %s ऊंचाई तक पहुंचने के बाद वॉलेट को सफलतापूर्वक लोड करने में सक्षम होना चाहिए</translation>
    
YES, The word "ग्रहणुत्सो" is not a valid Hindi word. It seems to be a misspelling or misinterpretation of "assumeutxo". The correct translation should replace it with an appropriate Hindi term or a transliteration if no direct equivalent exists.

Correct translation:
बटुआ लोड करने में त्रुटि. वॉलेट को डाउनलोड करने के लिए ब्लॉक की आवश्यकता होती है, और सॉफ्टवेयर वर्तमान में लोडिंग वॉलेट का समर्थन नहीं करता है, जबकि ब्लॉक्स को ऑर्डर से बाहर डाउनलोड किया जा रहा है, जब assumeutxo स्नैपशॉट का उपयोग किया जाता है। नोड सिंक के %s ऊंचाई तक पहुंचने के बाद वॉलेट को सफलतापूर्वक लोड करने में सक्षम होना चाहिए
```

```
        <source>Maximum transaction weight is too low, can not accommodate change output</source>
        <translation>अधिकतम लेनदेन भार बहुत कम है, change output को समायोजित नहीं कर सकता</translation>
    
YES, The translation uses the English word "change" instead of translating it to Hindi. The word "change" in the context of Bitcoin transactions refers to the leftover amount of Bitcoin after a transaction.

Correct translation: अधिकतम लेनदेन भार बहुत कम है, शेष राशि आउटपुट को समायोजित नहीं कर सकता
```

```
        <source>Unexpected legacy entry in descriptor wallet found. Loading wallet %s

The wallet might have been tampered with or created with malicious intent.
</source>
        <translation>डिस्क्रिप्टर वॉलेट में अप्रत्याशित विरासत प्रविष्टि मिली। %s बटुआ लोड हो रहा है

हो सकता है कि वॉलेट से छेड़छाड़ की गई हो या दुर्भावनापूर्ण इरादे से बनाया गया हो।
</translation>
    
YES - The translation incorrectly translates "descriptor wallet" as "डिस्क्रिप्टर वॉलेट" when it should be "विवरणक वॉलेट" for better accuracy in the context of Bitcoin. Also, "wallet" is repeated in the second sentence of the translation, which is redundant.

Correct translation: विवरणक वॉलेट में अप्रत्याशित विरासत प्रविष्टि मिली। %s वॉलेट लोड हो रहा है। हो सकता है कि वॉलेट से छेड़छाड़ की गई हो या दुर्भावनापूर्ण इरादे से बनाया गया हो।
```

```
        <source>Block verification was interrupted</source>
        <translation>ब्लॉक verification अन्तरायित हुआ</translation>
    
YES - The translation uses an English word "verification" which should have been translated into Hindi. The correct translation is: ब्लॉक सत्यापन बाधित हुआ।
```

```
        <source>Elliptic curve cryptography sanity check failure. %s is shutting down.</source>
        <translation>Elliptic curve cryptography sanity check विफलता | %sबंद हो रही है |</translation>
    
YES. The translation is problematic. The Hindi text contains a mix of English and incorrectly translated Hindi, along with extraneous characters.

Correct translation:
Elliptic curve cryptography sanity check विफलता। %s बंद हो रहा है।
```

```
        <source>Failed to connect best block (%s).</source>
        <translation>best ब्लॉक (%s) से कनेक्ट करने में विफल |</translation>
    
YES. The Hindi translation contains an extra pipe symbol at the end, which is not present in the source text.

best ब्लॉक (%s) से कनेक्ट करने में विफल।
```

```
        <source>Failed to read block.</source>
        <translation>ब्लॉक पढ़ने में विफल |</translation>
    
YES - The translation contains an extraneous vertical bar at the end.
Correct translation: ब्लॉक पढ़ने में विफल।
```

```
        <source>Failed to write to block index database.</source>
        <translation>ब्लॉक इंडेक्स डेटाबेस में लिखने में विफल |</translation>
    
YES - The translation has an extraneous pipe character at the end.
<source>Failed to write to block index database.</source>
<translation>ब्लॉक इंडेक्स डेटाबेस में लिखने में विफल।</translation>
```

```
        <source>Invalid port specified in %s: '%s'</source>
        <translation>में निर्दिष्ट अमान्य पोर्ट %s:'%s'</translation>
    
YES: The Hindi translation is grammatically incorrect and does not convey the intended meaning. The word "में" (in) should not precede "specified" (निर्दिष्ट) and the order of the arguments is also incorrect.

Correct translation: %s में निर्दिष्ट अमान्य पोर्ट: '%s'
```

```
        <source>Signer did not echo address</source>
        <translation>Signer ने पता की echo नहीं की</translation>
    
YES, The Hindi translation is grammatically incorrect. The correct translation should be "Signer ने पता echo नहीं किया" which correctly uses the masculine verb form.

NO
```

```
        <source>Specified data directory "%s" does not exist.</source>
        <translation>निर्दिष्ट डेटा निर्देशिका "%s" मौजूद नहीं है |</translation>
    
YES: The translation uses a pipe symbol "|" at the end of the sentence, which is not appropriate in Hindi. It should be a full stop.
निर्दिष्ट डेटा निर्देशिका "%s" मौजूद नहीं है।
```

```
        <source>System error while saving block to disk: %s</source>
        <translation>ब्लॉक को डिस्क पर सहेजते समय सिस्टम error: %s</translation>
    
YES: The word "error" has been incorrectly translated as "error". It should be translated to "त्रुटि".
ब्लॉक को डिस्क पर सहेजते समय सिस्टम त्रुटि: %s
```

```
        <source>Error: cannot remove legacy wallet records</source>
        <translation>Error: leagcy वॉलेट रिकॉर्ड को हटाया नहीं जा सकता है</translation>
    
YES, The translation contains a spelling error. The word "legacy" is misspelled as "leagcy". The correct translation is:
Error: legacy वॉलेट रिकॉर्ड को हटाया नहीं जा सकता है
```

```
        <source>Settings file could not be read</source>
        <translation>सेटिंग्स फ़ाइल को पढ़ा नहीं जा सका |</translation>
    
YES - The translation has an unnecessary pipe symbol at the end.
Correct translation: सेटिंग्स फ़ाइल को पढ़ा नहीं जा सका
```

```
        <source>Settings file could not be written</source>
        <translation>सेटिंग्स फ़ाइल नहीं लिखी जा सकी |</translation>
    
YES: The translation includes an extraneous vertical bar "|", which is not present in the source text.
Settings file could not be written
```
</details>
