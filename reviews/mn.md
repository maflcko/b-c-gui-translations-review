# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>mn</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bmn%5D%20request)


<!-- cache_translation_check_mn_ebab824879244ab8bef84ccb09ac840073e61ca3d81013bc34f1b1f7306bbdcc -->
```
        <source>&amp;Export</source>
        <translation>&amp;Экспорт</translation>
    
SPAM
The translation is in Russian, not Mongolian ('mn').

Correct translation:
&Экспорт should be &Экспортлох (assuming Mongolian context, the usual term for "Export" is "Экспортлох" in Mongolian Cyrillic; or "Экспорт" is sometimes used colloquially, but the proper suffix "-лох" turns the noun into a verb which is more natural for a button/action in UI Mongolia).

Correct translation:
&Экспортлох
</reply>
```

<!-- cache_translation_check_mn_8b6f1d94653dbd55ca716b020b61ce18018258bc8ab3ac434e78e5def7c80c9f -->
```
        <source>Sending addresses - %1</source>
        <translation>хаягуудииг Илгээж байна - %1</translation>
    
ERR
The Mongolian translation has a grammatical error and an unnatural word order. The term "хаягуудииг Илгээж байна" is awkward; it reads as "Addresses are being sent," which is a misinterpretation. "Sending addresses" should refer to "addresses you are sending from" (like a label). Also, "хаягуудииг" uses an incorrect spelling; the correct accusative is "хаягуудыг" but that is not necessary here.

Correct translation:
Илгээх хаягууд - %1
```

<!-- cache_translation_check_mn_bc3f9c351f9d172dcf6614049eba0318ad2dcb702b5f2d756166d836aa26969d -->
```
        <source>Wallet passphrase was successfully changed.</source>
        <translation>Түрүйвчийн нууц үг амжилттай ѳѳр</translation>
    
ERR
The translation is incomplete; the word 'ѳѳр' (meaning 'other' or 'different') does not complete the meaning of 'changed'. The correct translation should be:

Түрийвчийн нууц үг амжилттай өөрчлөгдлөө.
```

<!-- cache_translation_check_mn_75e7bddfa0a6c009577eb9c73650300ee2d9d424e85af866832b6450b227919b -->
```
        <source>&amp;Transactions</source>
        <translation>Гүйлгээнүүд</translation>
    
ERR
The '&' character, which serves as a shortcut key indicator in GUI text, is missing in the Mongolian translation. It should appear exactly once, ideally at the same or a logical position in the target language.

Correct translation:
&Гүйлгээнүүд
```

<!-- cache_translation_check_mn_d11265506dbf27e9bc9a1d0e6f936c9bd930e26bc4b6a338739c722b52e53b2d -->
```
        <source>E&amp;xit</source>
        <translation>Гарах</translation>
    
ERR
The translation omits the shortcut key indicator "&", which should appear exactly once somewhere in the translation.

Correct translation:
&Гарах
```

<!-- cache_translation_check_mn_3b614119df3bcd1e435394f76ba0e6ae1a1a84cfc9e153fafed2635137fe9320 -->
```
        <source>About &amp;Qt</source>
        <translation>&amp;Клиентийн тухай</translation>
    
ERR
The translation uses "Клиентийн тухай" which means "About the client," not "About Qt." The correct translation should refer to "Qt," since "&Qt" is the subject.

Correct translation:
Qt-ийн тухай &amp;

or

&amp;Qt-ийн тухай

Either form places the shortcut key (&) and maintains the meaning, but must not replace "Qt" with "Клиент".
```

<!-- cache_translation_check_mn_c8e259d3339002c9143423b7baea87fb5b33bea9ad65c5b59a297a05ff48725f -->
```
        <source>&amp;Send</source>
        <translation>&amp;Илгээх
 </translation>
    
ERR
There is a problematic whitespace at the end of the translation line (an extra space or possibly a non-breaking space after 'Илгээх'). This should be removed to prevent formatting issues.

Correct translation:
&Илгээх
```

<!-- cache_translation_check_mn_cb778ab913bf148c69d54aa67f5a8281c20292a3f645eb3e28abffbc751ba36a -->
```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Түрүйвч &lt;b&gt;цоожтой&lt;/b&gt; ба одоогоор цоож &lt;b&gt;хаалттай&lt;/b&gt; байна</translation>
    
ERR
The provided translation is inaccurate. The source states "Wallet is <b>encrypted</b> and currently <b>locked</b>," but the translation omits "encrypted" and redundantly uses "locked" and "closed," which could be confusing.

Correct translation:
Түрийвч &lt;b&gt;шифрлэгдсэн&lt;/b&gt; бөгөөд одоогоор &lt;b&gt;цоожтой&lt;/b&gt; байна
```

<!-- cache_translation_check_mn_41e7a172a6f2cd47bee9502754ea0fe567483368a75e176ed5aeacc15b3a8ee9 -->
```
        <source>Copy change</source>
        <translation>Ѳѳрчлѳлтийг санах</translation>
    
ERR
The Mongolian translation is incorrect. "Ѳѳрчлѳлтийг санах" means "Remember the change," not "Copy change." The correct translation for "Copy change" (in the context of Bitcoin, namely, the 'change amount') should closely translate the word 'copy' as in 'to make a copy' or 'to copy to clipboard'. A more accurate translation would be:

"Хариултыг хуулбарлах"

This uses "хариулт" for 'change' in the context of returning money (as in 'change' from a transaction), which is the term used in Mongolian for Bitcoin 'change'.
```

<!-- cache_translation_check_mn_4fe7ce44973c58c3ec4738fa5c0ccdff082d56e5b95b497e7e5e303d965402c3 -->
```
        <source>&amp;Network</source>
        <translation>Сүлжээ</translation>
    
ERR
The translation is missing the '&' shortcut key indicator, which should exist exactly once as in the source.

Correct translation:
&Сүлжээ
```

<!-- cache_translation_check_mn_af62c41ee998d49651acfb573a8dfcf82c2cd19e39f4b0bd714662445ed269f6 -->
```
        <source>W&amp;allet</source>
        <translation>Түрүйвч</translation>
    
ERR
The translation omits the '&' shortcut marker from the source. It should exist exactly once in the translation as in the original.

Correct translation:
&Түрүйвч
or
Түрүйвч&

(The placement may vary, but '&' must be present exactly once.)
```

<!-- cache_translation_check_mn_3f2758c27fcd9bb3d935a49b5be26d6c4270afe5044fc75576c36e5c933a55d1 -->
```
        <source>Client restart required to activate changes.</source>
        <extracomment>Text explaining that the settings changed will not come into effect until the client is restarted.</extracomment>
        <translation>Ѳѳрчлѳлтүүдийг идэвхижүүлхийн тулд клиентийг ахин эхлүүлэх шаардлагтай</translation>
    
ERR
There are spelling mistakes and minor grammar issues in the Mongolian translation. The correct word is "ѳѳрчлѳлтүүдийг" → "Өөрчлөлтүүдийг". Also, "идэвхижүүлэхийн", not "идэвхижүүлхийн", and "шаардлагтай" should be "шаардлагатай". The letter "ѳ" is also a Cyrillic letter, but the Mongolian "Ө" is preferable for standard Mongolian orthography.

Correct translation:
Өөрчлөлтүүдийг идэвхжүүлэхийн тулд клиентийг дахин эхлүүлэх шаардлагатай.
```

<!-- cache_translation_check_mn_26668fd2c3981a5bf0916b0f30d8e6def29261d9d7b414c0965f185bedfdd4f7 -->
```
        <source>This change would require a client restart.</source>
        <translation>Энэ ѳѳрчлѳлтийг оруулахын тулд кли1нт програмыг ахин эхлүүлэх шаардлагтай</translation>
    
ERR
There is a typographical error in "кли1нт" – the digit "1" is used instead of the Cyrillic letter "и". There is also a missing space at the end of the sentence, and "шаардлагтай" should be "шаардлагатай" for correctness.

Correct translation:
Энэ өөрчлөлтийг оруулахын тулд клиент програмыг ахин эхлүүлэх шаардлагатай.
```

<!-- cache_translation_check_mn_ec834932d0f918f1c1ecd06911d60d5aad3c65cd84fad7a2506553fbede90009 -->
```
        <source>&amp;Amount:</source>
        <translation>Хэмжээ:</translation>
    
ERR
The '&' in the source indicates a shortcut key and should be preserved exactly once in the translation. It is missing in the translation.

Correct translation:
&Хэмжээ:
```

<!-- cache_translation_check_mn_cd73b7c41e342a057593cf2e9a74e351584aad5689bc65ad0ca8fcd9f437bed7 -->
```
        <source>&amp;Message:</source>
        <translation>Зурвас:</translation>
    
ERR
The ampersand (&) indicating the shortcut key is missing in the Mongolian translation. The translation should preserve it, placing it anywhere in the translated phrase, but exactly once.

Correct translation:
&Зурвас:
or
Зурвас(&):
```

<!-- cache_translation_check_mn_41e7a172a6f2cd47bee9502754ea0fe567483368a75e176ed5aeacc15b3a8ee9 -->
```
        <source>Copy change</source>
        <translation>Ѳѳрчлѳлтийг санах</translation>
    
ERR
The Mongolian translation is incorrect. "Ѳѳрчлѳлтийг санах" means "Remember the change," not "Copy change." The correct translation for "Copy change" (in the context of Bitcoin, namely, the 'change amount') should closely translate the word 'copy' as in 'to make a copy' or 'to copy to clipboard'. A more accurate translation would be:

"Хариултыг хуулбарлах"

This uses "хариулт" for 'change' in the context of returning money (as in 'change' from a transaction), which is the term used in Mongolian for Bitcoin 'change'.
```

<!-- cache_translation_check_mn_7b247de2b20cac08d804878efc51c39516e2874905934f5d20d8f63ce7591068 -->
```
        <source>A&amp;mount:</source>
        <translation>Дүн:</translation>
    
ERR
The translation did not preserve the ampersand (&) which indicates the keyboard shortcut in the source (“A&amp;mount:”). The ampersand (&) should be present exactly once somewhere in the translation to allow for a shortcut key, as in the source.

Correct translation:
&Дүн:
```

<!-- cache_translation_check_mn_c4f2403fbe8a48d15283267fc5fcef0827d1c8a72337b93a57043af9a4f2c8b4 -->
```
        <source>Transaction ID</source>
        <translation>Тодорхойлолт</translation>
    
ERR
The translation is incorrect. "Тодорхойлолт" means "Description," not "Transaction ID." The correct translation for "Transaction ID" in Mongolian is:

Гүйлгээний дугаар
```

<!-- cache_translation_check_mn_ebab824879244ab8bef84ccb09ac840073e61ca3d81013bc34f1b1f7306bbdcc -->
```
        <source>&amp;Export</source>
        <translation>&amp;Экспорт</translation>
    
SPAM
The translation is in Russian, not Mongolian ('mn').

Correct translation:
&Экспорт should be &Экспортлох (assuming Mongolian context, the usual term for "Export" is "Экспортлох" in Mongolian Cyrillic; or "Экспорт" is sometimes used colloquially, but the proper suffix "-лох" turns the noun into a verb which is more natural for a button/action in UI Mongolia).

Correct translation:
&Экспортлох
</reply>
```
</details>

Number of issues: 19.
