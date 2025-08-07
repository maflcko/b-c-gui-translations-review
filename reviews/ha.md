# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ha</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bha%5D%20low%20quality)


```
        <source>Copy the currently selected address to the system clipboard</source>
        <translation>Kwafi adireshin da aka zaɓa a halin yanzu domin yin amfani dashi</translation>
    
YES
The translation omits the explicit mention of "system clipboard" and instead says "for use" (domin yin amfani dashi), which does not convey copying to the clipboard. It is not accurate in a technical context.

Correct translation:
Kwafi adireshin da aka zaɓa a halin yanzu zuwa allo na kwamfuta (clipboard)
```

```
        <source>Close</source>
        <translation>Cɓatar</translation>
    
YES
The translation "Cɓatar" is problematic because the correct Hausa word for "Close" in the context of closing a window, dialog, or application is "Rufe". "Cɓatar" is not a standard or recognized word in Hausa and appears to be erroneous.

Correct translation:
Rufe
```

```
        <source>Delete the currently selected address from the list</source>
        <translation>Share adireshin da aka zaɓa a halin yanzu daga jerin </translation>
    
YES
The translation is inaccurate. "Share" means "to share" in English, and does not correspond to "Delete". The correct translation for "Delete the currently selected address from the list" in Hausa should be:

Goge adireshin da aka zaɓa a halin yanzu daga jerin

Additionally, there is a stray space at the end of the translation.
```

```
        <source>Export</source>
        <translation> Fitarwa</translation>
    
YES
There is an unwanted leading space in the translation, which introduces a formatting issue.

Correct translation:
Fitarwa
```

```
        <source>Delete</source>
        <translation>Sharewa</translation>
    
YES
The translation of "Delete" as "Sharewa" in Hausa is incorrect. "Sharewa" means "to sweep" or "to clean", and is not the standard term used for "Delete" in software or computer contexts. The standard Hausa word for "Delete" in a computer context is "Goge".

Correct translation:
Goge
```

```
        <source>Choose the address to receive coins with</source>
        <translation>Zaɓi adireshin don karɓar kuɗi internet da shi</translation>
    
YES
The translation is mostly accurate but problematic due to the addition of "internet" ("intanet"), which is not present in the source and not relevant in this context. Also, the phrase "da shi" at the end is awkward and not commonly used for this instruction. The translation should be concise and faithful to the source.

Correct translation:
Zaɓi adireshin da za a karɓi kuɗi da shi
```

```
        <source>Choose</source>
        <translation>czaɓi</translation>
    
YES
The translation "czaɓi" is incorrect and appears to use non-standard or erroneous transliteration. The correct translation for "Choose" in Hausa is "Zaɓi".

Correct translation:
Zaɓi
```

```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>Waɗannan adiresoshin Bitcoin ne don tura kuɗi bitcoin . ka tabbatar da cewa adreshin daidai ne kamin ka tura abua a ciki</translation>
    
YES
There are several issues:
- "adiresoshin" is misspelled; the plural of "adireshi" is "adiresoshin" in Hausa, but the rest of the translation is awkward and contains informal/spoken usages ("abua a ciki" translates as "something inside," which is not clear or appropriate here). 
- The translation omits "Always check the amount" (it does not mention the amount).
- "Ka tabbatar da cewa adreshin daidai ne kamin ka tura abua a ciki" is not a faithful or clear rendering of "Always check the amount and the receiving address before sending coins."
- "bitcoin" should not be repeated after "kuɗi".

Correct translation:
Waɗannan su ne adireshin Bitcoin ɗinka don aika kuɗi. Koyaushe tabbatar da adadin da adireshin mai karɓa kafin ka tura kuɗi.
```

```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Waɗannan adiresoshin Bitcoin ne don karɓar kuɗi. Yi amfani da maɓallin 'Ƙirƙiri sabon adireshin karɓa' a cikin shafin karɓa don ƙirƙirar sababbin adireshi.
zaka iya shiga ne kawai da adiresoshin 'na musamman' kawai.</translation>
    
YES  
The translation has several issues:
- The term "signing" (probably means cryptographic signing) is not directly rendered; "zaka iya shiga" rather means "you can log in," which is incorrect.  
- The phrase "addresses of the type 'legacy'" is mistranslated as "adiresoshin 'na musamman'" meaning "special addresses," which is not accurate for "legacy."
- There is inconsistency in technical vocabulary.
- "adiresoshin" used in plural, but in one sentence "adireshi" (singular) is used, which should be consistent.

Correct translation:
Waɗannan su ne adiresoshin Bitcoin ɗinka na karɓar kuɗi. Yi amfani da maɓallin 'Ƙirƙiri sabon adireshin karɓa' a shafin karɓa don ƙirƙirar sababbin adiresoshi.  
Ana iya yin sa hannu kawai da adiresoshin nau'in 'legacy' kawai.
```

```
        <source>Copy Label</source>
        <translation>Kwafi  Lakabi</translation>
    
YES
There is an extra space between "Kwafi" and "Lakabi", resulting in "Kwafi  Lakabi" instead of "Kwafi Lakabi". This is a whitespace formatting issue.

Correct translation:
Kwafi Lakabi
```

```
        <source>Encrypt wallet</source>
        <translation>sakaye walet</translation>
    
YES
The translation is understandable but not ideal. In Hausa, capitalization should match the source, and "encrypt" is better translated as "Kulle" or "Shiga lambobi" rather than the borrowed "sakaye", which means "to hide" and does not specifically imply encryption. "Walet" is a loanword, but commonly used.

Correct translation:
Kulle walet
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>abunda ake son yi na buƙatan laƙabin sirri domin buɗe walet</translation>
    
YES
The translation is missing some key details from the source text. It does not specify "your wallet passphrase" (instead it just generically says "laƙabin sirri" = passphrase), and it omits subjects/context, making it less formal/accurate.

Correct translation:
Wannan aiki na buƙatar kalmar sirrin walat ɗinka don buɗe walat ɗinka.
```

```
        <source>Confirm wallet encryption</source>
        <translation>tabbar da an sakaye walet</translation>
    
YES
The translation is not fully accurate. "Tabbar da an sakaye walet" literally translates to "confirm that wallet is hidden", which confuses "encryption" (which is about security, i.e., encryption, not just hiding). The correct way to render "Confirm wallet encryption" is:

Correct translation:
Tabbatar da kulle walet ɗin da kalmar sirri

Alternatively, using the common technical term:
Tabbatar da ɓoye walet ɗin

But "kulle da kalmar sirri" or "ɓoye" is closer to the real meaning than "sakaye" (simply hidden).
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Jan kunne: idan aka sakaye walet kuma aka manta laƙabin sirri, za a Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt; RASA DUKKAN BITCOINS&lt;/b&gt;!</translation>
    
YES
The translation is problematic for several reasons:
- The translation mixes Hausa ("idan aka sakaye walet kuma aka manta laƙabin sirri, za a") with redundant English text ("Warning: If you encrypt your wallet and lose your passphrase, you will").
- It introduces "Jan kunne" which is a correct way to say "Warning", but then redundantly includes the English "Warning" again.
- The structure is erratic, and the phrase "za a Warning" is not correct.
- The critical warning part ("LOSE ALL OF YOUR BITCOINS") is only partially translated.

Correct translation:
Jan kunne: Idan ka kulle walet ɗinka kuma ka manta kalmar sirri, za ka &lt;b&gt;RASA DUKKAN BITCOINS ɗIN KA&lt;/b&gt;!
```

```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>ka tabbata kana son sakaye walet?</translation>
    
YES
The translation has capitalization and politeness issues. In Hausa, sentence-initial capitalization is needed and the verb form should match the formal question. Also, "ka tabbata..." is more like "make sure..." rather than "Are you sure...". The correct translation should be:

Ka tabbata kana so ka ƙirƙiri sirri a walet ɗinka? 

or more simply:

Kana tabbatar kana so ka ɓoye walet ɗinka?
```

```
        <source>Wallet encrypted</source>
        <translation>an yi nasarar sakaye walet</translation>
    
YES
The translation "an yi nasarar sakaye walet" is not accurate and is somewhat awkward. The phrase "Wallet encrypted" should translate simply as "An sakaye walet" or "Walet an sakaye" in Hausa, which means "The wallet is encrypted." The word "nasarar" means "success," which is not present in the original English text and makes the translation inaccurate.

Correct translation:
An sakaye walet
```

```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>shigar da tsoho da sabon laƙabin sirrin walet din</translation>
    
YES
The translation omits "Enter" as an imperative verb and is missing the instruction to enter both the old and new passphrases; it also omits the explicit mention of "passphrase" twice (old and new), and is not a full sentence (missing capitalization and finalizing period).

Correct translation:
Shigar da tsohuwar kalmar sirri da sabuwar kalmar sirri don walet ɗin.
```

```
        <source>Wallet to be encrypted</source>
        <translation>walet din da ake buƙatan sakayewa</translation>
    
YES
The translation is inaccurate and contains a slight error in meaning and capitalization. "Walet din da ake buƙatan sakayewa" translates roughly to "the wallet that needs to be encrypted," while the source says "Wallet to be encrypted," which should best be translated as "Wallet da za a ƙara wa ƙyamar kalmar shiga" or more simply "Wallet da za a kulle" or "Walet da za a ɓoye" to be precise. Also, "walet" should be capitalized to match the source.

Correct translation:
Walet da za a kulle
```

```
        <source>Your wallet is about to be encrypted. </source>
        <translation>ana daf da sakaye walet</translation>
    
YES
The translation is inaccurate and ungrammatical in Hausa. "ana daf da sakaye walet" is not correct; it is a literal, awkward construction. The correct translation in Hausa should clearly state that the wallet is about to be encrypted (not just "hidden" or "stored away").

Correct translation:
Ana shirin ɓoye walet ɗinka da kalmar sirri.
```

```
        <source>Your wallet is now encrypted. </source>
        <translation>ka yi nasarar sakaye walet dinka</translation>
    
YES
The translation is not accurate and does not match the tone of the original. The English sentence is a plain statement, while the translation adds "ka yi nasarar" (you have succeeded in), which implies an action by the user and changes the tone.

Correct translation:
An sakaye walet ɗinka yanzu.
```

```
        <source>Wallet encryption failed</source>
        <translation>ba ayi nasarar sakaye walet ba</translation>
    
YES
The translation is understandable but contains grammatical errors and unnecessary repetition of "ba" (meaning "not" or "no" in Hausa) at the start and end, making it unidiomatic and awkward.

Correct translation:
Sakawa walet lamba ya kasa
```

```
        <source>Export</source>
        <translation> Fitarwa</translation>
    
YES
There is an unwanted leading space in the translation, which introduces a formatting issue.

Correct translation:
Fitarwa
```
</details>

Number of issues: 22.
