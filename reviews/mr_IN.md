# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>mr_IN</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bmr_IN%5D%20low%20quality)


```
        <source>Copy Label</source>
        <translation>शिक्का कॉपी करा</translation>
    
YES
The translation is incorrect. "शिक्का" means "coin" or "seal" in Marathi, not "label." The correct translation for "Label" is "लेबल" or "चिट्ठी," but "लेबल" is more commonly used in this context.

Correct translation:
लेबल कॉपी करा
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>पत्ता सूची  वर जतन करण्याचा प्रयत्न करताना त्रुटी आली. कृपया पुन्हा प्रयत्न करा.%1</translation>
    
YES
The translation has an issue: the format specifier '%1' is not in the correct place within the sentence, and there is an extra space between "सूची" and "वर". The translation should also mention the file (to which the list is being saved). Also, "पत्ता सूची वर" is unnatural and should be "पत्ता सूची %1 वर" or consider rephrasing.

Correct translation:
%1 वर पत्ता सूची जतन करण्याचा प्रयत्न करताना त्रुटी आली. कृपया पुन्हा प्रयत्न करा.
```

```
        <source>Confirm wallet encryption</source>
        <translation>वॉलेट एन्क्रिप्शनची पुष्टी करा
 </translation>
    
YES
There is an unwanted trailing whitespace (likely a non-breaking space or line break) after the translation. Additionally, "पुष्टी करा" is an acceptable translation, but a more common Marathi term for "Confirm" in such contexts is "निश्चित करा" or "सत्यापन करा". However, "पुष्टी करा" is also clear and widely understood.

Corrected translation (removing unwanted whitespace):

<translation>वॉलेट एन्क्रिप्शनची पुष्टी करा</translation>
```

```
        <source>Sign message…</source>
        <translation>स्वाक्षरी आणि संदेश...</translation>
    
YES
The translation is inaccurate. The English "Sign message…" means to sign (a) message, not "sign and message...". The correct translation should directly refer to "message signing".

Correct translation:
संदेशावर स्वाक्षरी करा...
```
</details>
