# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>sa</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bsa%5D%20request)


<!-- cache_translation_check_sa_10de729e4f7574296639d6d60e8f74083c40f7b7f54dcf9e682efac442c673dd -->
```
        <source>&amp;New</source>
        <translation>नवम्</translation>
    
ERR
The English source includes a single '&' to indicate a shortcut key, but the Sanskrit translation 'नवम्' omits it. The '&' should be preserved somewhere in the translation to support shortcut access.

Correct translation:
&नवम्
or
नवम् (&)
or any placement of a single '&', as Sanskrit UI conventions permit.
```

<!-- cache_translation_check_sa_eda94e413741d8fb77541c43751dae3c868acbe0156879c0c52424bc9285c916 -->
```
        <source>&amp;Copy</source>
        <translation>प्रतिलिप्य</translation>
    
ERR
The translation omits the '&' shortcut key marker present in the source. This marker should appear exactly once in the translation.

Correct translation:
&प्रतिलिप्य
```

<!-- cache_translation_check_sa_7e6d4d509aa94ca1289bd4c081ab0e57961993b0f9bad34d89afbc71f5214adf -->
```
        <source>C&amp;lose</source>
        <translation>समापयतु</translation>
    
ERR
The translation "समापयतु" is a formal/imperative singular verb in Sanskrit meaning "Let (him/her/it) close", but it does not include the '&' shortcut marker present in the source ("C&amp;lose"). The translation should also place the ampersand before an appropriate character (commonly, before the first letter), which is important for shortcut keys in UI contexts.

Correct translation:
&समापयतु

Or, for Sanskrit decisively using a proper noun:
समापय&तु

But, typically, & should precede the shortcut key, depending on UI implementation. Choose either, ensuring & appears exactly once.
```

<!-- cache_translation_check_sa_251bf61b6c23c9aefc60e54d0dd1072dd32f3ff092056862367114287cf7679f -->
```
        <source>&amp;Export</source>
        <translation>निर्यातय</translation>
    
ERR
The translation does not include the '&' shortcut marker, which should be present exactly once as in the source.

Correct translation:
&निर्यातय
```

<!-- cache_translation_check_sa_5d7bf1f5188d4f0e7e1c1e4a328ef1566a0171ba3b65a2d193136086af979b90 -->
```
        <source>&amp;Delete</source>
        <translation>हन्तव्यं</translation>
    
ERR
The translation is missing the '&' symbol, which is used for shortcut keys. It must appear exactly once in both source and translation.

Correct translation:
&हन्तव्यं
```

<!-- cache_translation_check_sa_6fc6b706f9e60ee088543fe75941a99ebc952ff1142b1c6f84e51e90205228d6 -->
```
        <source>C&amp;hoose</source>
        <translation>चयनय</translation>
    
ERR
The translation omits the required '&' which is used for the shortcut key in the source. The word "चयनय" is also not correct morphologically; a better translation would be the imperative form "चुनोत" or a similar command form suited for buttons. The whitespace is otherwise fine.

Correct translation:
&चुनोत

Or:
चु&नोत

(But the important part is that the single '&' must be present, correctly placed for a shortcut key.)
```

<!-- cache_translation_check_sa_8d8cadb6aa3575948ed0b784646ce9d9363e95984559aaf21622baa8c39249ae -->
```
        <source>&amp;Edit</source>
        <translation>संपादय</translation>
    
ERR
The translation is missing the "&" shortcut indicator, which should appear exactly once somewhere in the translation to match the source's keyboard accelerator functionality.

Correct translation:
&संपादय

OR

संपा&दय

(Placement of "&" may vary for optimal mnemonic key selection in Sanskrit-script interfaces.)
```

<!-- cache_translation_check_sa_2289274c0eadb348ff27eb135f440f80635a110a5d18d4ff9131c9ae80297829 -->
```
        <source>Sending addresses - %1</source>
        <translation>पताक्षेत्राणि प्रेषणं कुर्वन्ति - %1</translation>
    
ERR
The translation is inaccurate. The English "Sending addresses" refers to the list of Bitcoin wallet addresses from which transactions are sent. The Sanskrit translation "पताक्षेत्राणि प्रेषणं कुर्वन्ति" is awkward and unidiomatic—it literally means "addresses do the sending", which is not a natural way to express a list or category title in Sanskrit. It also misuses verb forms and pluralization.

Correct translation:
प्रेषण-पताः - %1

Here, "प्रेषण-पताः" (sending addresses) preserves the compound noun structure, is concise, and fits the likely use in a UI.
```

<!-- cache_translation_check_sa_ad29004dd141d4f1d69341380af799d936cd7984abbb058d50f18014acb62486 -->
```
        <source>Receiving addresses - %1</source>
        <translation>पताक्षेत्राणि प्राप्तिं कुर्वन्ति - %1</translation>
    
ERR
The Sanskrit translation is awkward/incorrect and not a natural rendering of the UI label. "पताक्षेत्राणि प्राप्तिं कुर्वन्ति - %1" reads as a (grammatically odd) sentence "flags/areas do receiving - %1" rather than a concise label "Receiving addresses - %1".

A better, more natural UI rendering in Sanskrit would be concise and use terms for "receiving" (स्वीकारण / प्राप्ति) and "addresses" (पत्तयः / पतेः). Suggested correction:

प्राप्ति-पत्तयः - %1

(Alternatively)
स्वीकारणपत्तयः - %1
```

<!-- cache_translation_check_sa_251bf61b6c23c9aefc60e54d0dd1072dd32f3ff092056862367114287cf7679f -->
```
        <source>&amp;Export</source>
        <translation>निर्यातय</translation>
    
ERR
The translation does not include the '&' shortcut marker, which should be present exactly once as in the source.

Correct translation:
&निर्यातय
```
</details>

Number of issues: 10.
