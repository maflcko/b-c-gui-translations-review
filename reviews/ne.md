# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ne</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bne%5D%20low%20quality)


```
        <source>New</source>
        <translation>amp;नयाँ</translation>
    
YES, the translation contains an erroneous character. The '&' symbol should not be present.
The correct translation is:
नयाँ
```

```
        <source>Copy</source>
        <translation>amp;कपी गर्नुहोस्</translation>
    
YES, The translation is problematic because it includes an HTML entity `&amp;` which should not be present in the translated text. The correct translation should be "कपी गर्नुहोस्".
YES, amp;कपी गर्नुहोस् is not a correct translation. The correct translation is कपी गर्नुहोस्.
```

```
        <source>Close</source>
        <translation>छनौट गर्नुहोस्</translation>
    
YES, The translation is problematic because "छनौट गर्नुहोस्" means "Select" or "Choose", not "Close".
Close - बन्द गर्नुहोस्
```

```
        <source>Export</source>
        <translation>amp;निर्यात गर्नुहोस्</translation>
    
YES, The translation is problematic because it contains an extraneous ampersand (&) at the beginning.
The correct translation should be: निर्यात गर्नुहोस्
```

```
        <source>Delete</source>
        <translation>amp;मेटाउनुहोस्</translation>
    
YES: The translation "amp;मेटाउनुहोस्" is incorrect and appears to be malformed. It is missing a space before the verb and the "amp;" is likely a remnant of an encoding error. The correct translation for "Delete" in this context would be "मेटाउनुहोस्".

NO
```

```
        <source>Warning: The Caps Lock key is on!</source>
        <translation>चेतावनी: क्याप्स लक कीप्याड अन छ!</translation>
    
YES, The translation uses the word "कीप्याड" which is an English loanword in Nepali. The correct Nepali word for "keypad" is "किप्याड" or "कुञ्जीपाटी" but "किप्याड" is more common. The translation also doesn't make sense as it says "caps lock keypad is on". The correct translation should be "Caps Lock key is on".
Correct translation: चेतावनी: क्याप्स लक कुंजी चालू छ!
```

```
        <source>Transactions</source>
        <translation>amp;कारोबार</translation>
    
YES, The translation is problematic due to incorrect characters and formatting. The "&amp;" is an HTML entity that should not be present in the translation. The correct word for "Transactions" in Hindi is "लेन-देन" or "लेनदेन".

Correct translation: लेनदेन
```

```
        <source>About %1</source>
        <translation>amp;बारेमा %1</translation>
    
YES, The translation is problematic because the Nepali word for "About" is "बारेमा" (barema), but the translation uses "amp;बारेमा" which is incorrect. The correct translation is "बारेमा %1".

NO
```

```
        <source>About Qt</source>
        <translation>amp;Qt</translation>
    
YES, The translation is incorrect. The correct translation should be "Qt बद्दल" which means "About Qt" in Nepali.
The translation ";Qt" appears to be a partial translation or a corrupted version of the original text. It does not convey any meaningful information in Nepali.

Correct translation: Qt बद्दल
```

```
        <source>Backup Wallet…</source>
        <translation>सहायता वालेट</translation>
    
YES, The translation of "Backup Wallet…" to "सहायता वालेट" is incorrect. "सहायता" means "help" or "assistance," not "backup." The correct translation for "Backup Wallet…" in Nepali would be "वालेटको जगेडा…" or "वालेट जगेडा…".

NO
```

```
        <source>Wallet Name</source>
        <translation>वालेट को नाम</translation>
    
YES, The translation is problematic as it is grammatically incorrect and does not convey the intended meaning accurately in Hindi. The word "को" is used incorrectly here.

The correct translation should be:
वालेट का नाम
```

```
        <source>Edit Address</source>
        <translation>ठेगाना जाँच गर्नुहोस्</translation>
    
YES
The Nepali translation "ठेगाना जाँच गर्नुहोस्" means "Check address" or "Verify address", which is not an accurate translation of "Edit Address". The correct translation for "Edit Address" should convey the meaning of modifying or changing an address.

Correct translation: ठेगाना सम्पादन गर्नुहोस्
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>%1 अनुकूल स्क्रिप्टको पूर्ण पथ (उदाहरणका लागि, C:\Downloads\hwi.exe वा /Users/you/Downloads/hwi.py) प्रविष्ट गर्नुहोस्। सावधान : मालवेयरले तपाईंका सिक्काहरू चोरी गर्न सक्छ!</translation>
    
YES: The translation is problematic because it includes an erroneous word. The word "प्रविष्ट गर्नुहोस्" (pravist garnu hos) which means "enter" or "input" is not present in the source text.
The correct translation is: %1 अनुकूल स्क्रिप्टको पूर्ण पथ (उदाहरणका लागि, C:\Downloads\hwi.exe वा /Users/you/Downloads/hwi.py)। सावधान : मालवेयरले तपाईंका सिक्काहरू चोरी गर्न सक्छ!
```

```
        <source>Type</source>
        <extracomment>Title of Peers Table column which describes the type of peer connection. The "type" describes why the connection exists.</extracomment>
        <translation>टाइप गर्नुहोस्</translation>
    
YES, the translation is incorrect. The English word "Type" in this context refers to a category or kind, not to the act of typing. The Nepali translation "टाइप गर्नुहोस्" means "Please type".

The correct translation should be:

<translation>प्रकार</translation>
```

```
        <source>A message that was attached to the bitcoin: URI which will be stored with the transaction for your reference. Note: This message will not be sent over the Bitcoin network.</source>
        <translation>बिटकोइनमा संलग्न गरिएको सन्देश: तपाईंको मध्यस्थको लागि कारोबारको साथमा भण्डारण गरिने URI । नोट: यो सन्देश बिटकोइन नेटवर्क मार्फत पठाइने छैन ।</translation>
    
YES - The translation incorrectly translates "reference" as "मध्यस्थ" (mediator/intermediary) instead of "सन्दर्भ" (reference).
Correct translation: बिटकोइनमा संलग्न गरिएको सन्देश: तपाईंको सन्दर्भको लागि कारोबारको साथमा भण्डारण गरिने बिटकोइन: URI । नोट: यो सन्देश बिटकोइन नेटवर्क मार्फत पठाइने छैन ।
```

```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>सन्देश प्रमाणित गर्न, तल दिइएको स्थानमा प्राप्तकर्ता ठेगाना, सन्देश (लाइन ब्रेक, स्पेस, ट्याब, आदि उस्तै गरी कपी गर्ने कुरा सुनिश्चित गर्नुहोस्) र हस्ताक्षर apos;s प्रविष्ट गर्नुहोस् । बीचमा-मानिसको-आक्रमणबाट बच्न हस्ताक्षर पढ्दा हस्ताक्षर गरिएको सन्देशमा जे छ त्यो भन्दा धेरै कुरामा ध्यान नदिनुहोस् । यो कार्यले हस्ताक्षर गर्ने पक्षले मात्र यो ठेगानाले प्राप्त गर्छ भन्ने कुरा प्रमाणित गर्छ, यसले कुनै पनि कारोबारको प्रेषककर्तालाई प्रमाणित गर्न सक्दैन भन्ने कुरा याद गर्नुहोस्!</translation>
    
YES: The translation contains an English word "apos's" which is not translated to Nepali. The correct translation should be:

सन्देश प्रमाणित गर्न, तल दिइएको स्थानमा प्राप्तकर्ता ठेगाना, सन्देश (लाइन ब्रेक, स्पेस, ट्याब, आदि उस्तै गरी कपी गर्ने कुरा सुनिश्चित गर्नुहोस्) र हस्ताक्षर प्रविष्ट गर्नुहोस् । बीचमा-मानिसको-आक्रमणबाट बच्न हस्ताक्षर पढ्दा हस्ताक्षर गरिएको सन्देशमा जे छ त्यो भन्दा धेरै कुरामा ध्यान नदिनुहोस् । यो कार्यले हस्ताक्षर गर्ने पक्षले मात्र यो ठेगानाले प्राप्त गर्छ भन्ने कुरा प्रमाणित गर्छ, यसले कुनै पनि कारोबारको प्रेषककर्तालाई प्रमाणित गर्न सक्दैन भन्ने कुरा याद गर्नुहोस्!
```

```
        <source>Type</source>
        <translation>टाइप गर्नुहोस्</translation>
    
YES, The translation is problematic. The English word "Type" in this context refers to a category or kind of something, not an action. The Nepali translation "टाइप गर्नुहोस्" means "Please type" or "Type it," which is an imperative verb.

Correct translation: प्रकार
```

```
        <source>Type</source>
        <translation>टाइप गर्नुहोस्</translation>
    
YES, The translation is problematic. The English word "Type" in this context refers to a category or kind of something, not an action. The Nepali translation "टाइप गर्नुहोस्" means "Please type" or "Type it," which is an imperative verb.

Correct translation: प्रकार
```

```
        <source>Export</source>
        <translation>amp;निर्यात गर्नुहोस्</translation>
    
YES, The translation is problematic because it contains an extraneous ampersand (&) at the beginning.
The correct translation should be: निर्यात गर्नुहोस्
```

```
        <source>Cannot resolve -%s address: '%s'</source>
        <translation>-%s ठेगाना: apos;%sapos; निश्चय गर्न सकिँदैन</translation>
    
YES - The translation uses incorrect Nepali words for "address" and "resolve" and also incorrectly translates the single quotes around the second %s. The formatting of the %s specifiers is also broken.

Correct translation: %s ठेगानालाई समाधान गर्न सकिँदैन: '%s'
```

```
        <source>Corrupted block database detected</source>
        <translation>क्षति पुगेको ब्लक डाटाबेस फेला पर</translation>
    
YES, the translation is problematic. The verb is in an incomplete form and the sentence structure is unnatural.
Correct translation: Corrupted block database detected
क्षति पुगेको ब्लक डाटाबेस पत्ता लाग्यो
```

```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>प्रयोगकर्ता एजेन्टको टिप्पणी (%s) मा असुरक्षित अक्षरहरू छन् ।</translation>
    
YES, The translation is problematic due to extra whitespace at the end of the sentence.
The correct translation is: प्रयोगकर्ता एजेन्टको टिप्पणी (%s) मा असुरक्षित अक्षरहरू छन्।
```
</details>
