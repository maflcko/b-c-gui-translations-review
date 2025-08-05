# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ha</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bha%5D%20low%20quality)


```
        <source>Copy the currently selected address to the system clipboard</source>
        <translation>Kwafi adireshin da aka zaɓa a halin yanzu domin yin amfani dashi</translation>
    
YES
The translation, while understandable, does not accurately convey the meaning of copying to the system clipboard. "Domin yin amfani dashi" means "for using it", but it omits the notion of the "system clipboard".

Correct translation:
Kwafi adireshin da aka zaɓa a halin yanzu zuwa allo mai ajiya na tsarin (system clipboard)
```

```
        <source>Close</source>
        <translation>Cɓatar</translation>
    
YES
The translation "Cɓatar" is erroneous and contains a character ('ɓ') that does not belong in the standard Hausa spelling for this context. The correct word for "Close" in Hausa in the context of an application or window is "Rufe".

Correct translation:
Rufe
```

```
        <source>Delete the currently selected address from the list</source>
        <translation>Share adireshin da aka zaɓa a halin yanzu daga jerin </translation>
    
YES  
The translation is problematic. The word "Share" means "to share" in English, which is incorrect in this context. The correct term for "Delete" in Hausa is "Goge" or "Share" can sometimes mean "to sweep" (as in physical cleaning), but not "to delete" in a computerized context. For digital deletion, "Goge" is more appropriate. Additionally, there is a space at the end of the translation that should be removed.

Correct translation:  
Goge adireshin da aka zaɓa a halin yanzu daga jerin
```

```
        <source>Export</source>
        <translation> Fitarwa</translation>
    
YES
There is an unwanted leading whitespace in the translation (" Fitarwa") which may cause formatting issues. It should match the source formatting without extra spaces.

Correct translation:
<translation>Fitarwa</translation>
```

```
        <source>Delete</source>
        <translation>Sharewa</translation>
    
YES
The translation "Sharewa" is incorrect. In Hausa, "Delete" should be translated as "Goge".

Correct translation:
<translation>Goge</translation>
```

```
        <source>Choose the address to receive coins with</source>
        <translation>Zaɓi adireshin don karɓar kuɗi internet da shi</translation>
    
YES  
The translation is problematic for the following reasons:
- "kuɗi internet" is an incorrect term for "coins" in the context of Bitcoin; "kuɗi" means "money", and "internet" is unnecessary and confusing here.
- The phrase "da shi" is an awkward construction in this context.  
- The translation should more closely match the original meaning: "Choose the address to receive coins with".

Correct translation:
Zaɓi adireshin da za a karɓi ƙofofi (ko 'tsabar kudi') da shi

However, a more natural translation in Hausa would be:
Zaɓi adireshin da za ka karɓi tsabar kuɗi da shi
```

```
        <source>Choose</source>
        <translation>czaɓi</translation>
    
YES
The translation "czaɓi" is erroneous. The correct Hausa translation for "Choose" is "Zaɓi". Additionally, the initial "c" should be "z", and there is an extraneous "c" at the start and the letter "z" should not be followed by a "c".

Correct translation:
Zaɓi
```

```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>Waɗannan adiresoshin Bitcoin ne don tura kuɗi bitcoin . ka tabbatar da cewa adreshin daidai ne kamin ka tura abua a ciki</translation>
    
YES
There are several issues with the translation:
- The word "adiresoshin" is a transliteration of "addresses", but the correct plural is "adirasoshin" in Hausa, though even better would be to use "adireso" as singular and "adiresoshin" as plural.
- The translation does not reflect the entire meaning, especially "Always check the amount", which is omitted.
- "tura kuɗi bitcoin" unnecessarily repeats "bitcoin", as the context already specifies "Bitcoin addresses".
- There are some grammatical errors, such as "abua a ciki" which is unclear.
- There's a typographical issue with an extra space before the period.

Correct translation:
Waɗannan su ne adiresoshin Bitcoin ɗinka don aikawa da kuɗi. Ka tabbatar ka duba adadin da za a aika da kuma adiresoshin da za a tura kuɗin kafin aikawa.
```

```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Waɗannan adiresoshin Bitcoin ne don karɓar kuɗi. Yi amfani da maɓallin 'Ƙirƙiri sabon adireshin karɓa' a cikin shafin karɓa don ƙirƙirar sababbin adireshi.
zaka iya shiga ne kawai da adiresoshin 'na musamman' kawai.</translation>
    
YES
There are several issues:

1. The translation of "Signing is only possible with addresses of the type 'legacy'." is incorrect. The text "zaka iya shiga" translates as "you can log in" or "you can enter", which does not reflect the meaning of "signing" in the context of Bitcoin (where it refers to cryptographic signing).
2. The phrase "'na musamman'" means "special", but the word used in the source is 'legacy', a particular Bitcoin address type. It should be left untranslated or properly explained in the context.
3. There is some inconsistency in number/pluralization ("adireshoshin").
4. "kawai" is repeated, which is redundant.

Correct translation:
Waɗannan su ne adiresoshin Bitcoin ɗinka don karɓar kuɗi. Yi amfani da maɓallin ‘Ƙirƙiri sabon adireshin karɓa’ a shafin karɓa don ƙirƙirar sababbin adireshi.
Ana iya sa hannu ne kawai da adiresoshin nau'in 'legacy' kawai.
```

```
        <source>Copy Label</source>
        <translation>Kwafi  Lakabi</translation>
    
YES
There is an extra space between "Kwafi" and "Lakabi", which is a whitespace formatting issue. The translation should not have a double space.

Correct translation:
Kwafi Lakabi
```

```
        <source>Show passphrase</source>
        <translation>nuna kalmar sirri</translation>
    
YES
The translation "nuna kalmar sirri" should have the first letter capitalized to match the source style. Also, "Show passphrase" can be more accurately translated as "Nuna kalmar sirri" or "Nuna kalmar shigarwa" (with "kalmar sirri" being commonly used). The original translation is understandable but has a formatting (capitalization) issue.

Correct translation:
Nuna kalmar sirri
```

```
        <source>Encrypt wallet</source>
        <translation>sakaye walet</translation>
    
YES
The translation is inaccurate. "sakaye walet" is a transliteration rather than a proper translation. In Hausa, "Encrypt wallet" should be something like "ɓoye walet da kalmar sirri" or "ƙulla walet da kalmar sirri" to convey "encrypt" (protect with a password/encryption).

Correct translation:
Ɓoye walet da kalmar sirri
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>abunda ake son yi na buƙatan laƙabin sirri domin buɗe walet</translation>
    
YES
The translation is understandable but is not sufficiently accurate, omitting important nuances. The phrase "passphrase" should not be translated as "laƙabi" (which means "alias" or "nickname"), and "to unlock the wallet" should be clearer. Also, it should refer explicitly to "wallet".

Correct translation:
Wannan aikin na buƙatar kalmar sirrin walat ɗinka don buɗe walat ɗin.
```

```
        <source>Confirm wallet encryption</source>
        <translation>tabbar da an sakaye walet</translation>
    
YES
The translation is understandable but not entirely accurate or natural in Hausa. "Tabbar da an sakaye walet" directly translates as "Confirm that the wallet has been hidden," which is incorrect in this context. "Encrypt" is better rendered as "ƙwafi" or "ladafta" (to encrypt or secure), and "confirm" as "tabbatar da."

Correct translation:
Tabbatar da ɓoyayyen walet
or
Tabbatar da an ƙwafi walet
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Jan kunne: idan aka sakaye walet kuma aka manta laƙabin sirri, za a Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt; RASA DUKKAN BITCOINS&lt;/b&gt;!</translation>
    
YES  
The translation contains erroneous content. The translation mixes English and Hausa ("Jan kunne" is Hausa for "Warning", then the rest includes the English sentence), and the output is not a proper translation. Additionally, "walet" and "laƙabin sirri" are reasonable for "wallet" and "passphrase" respectively, but the bulk of the sentence is untranslated. There is also stray spacing and the word "Warning" occurs twice.

Correct translation:
Jan kunne: Idan ka ɓoye walat ɗinka kuma ka manta kalmar sirri, za ka &lt;b&gt;RASA DUKKAN BITCOIN ɗinka&lt;/b&gt;!
```

```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>ka tabbata kana son sakaye walet?</translation>
    
YES
The translation has several issues:
1. The translation should start with a capital letter, matching the source format.
2. "ka tabbata" should be "Ka tabbata" or more formally "Kana tabbata".
3. "kana son" is less formal. "ka na son" or "kana son" is understood, but better is "kana so" (without 'n').
4. The word "sakaye" is understandable, but "ƙulle gidan ajiyar kuɗi na lantarki" or simply "ƙulle walet ɗinka" is better.
5. The tone is more direct in the translation; it should reflect the polite/confirming question of the original.
6. "Walet" should ideally keep the possessive "your" explicitly: "walet ɗinka".

Correct translation:
Ka tabbata kana so ka ƙulle walet ɗinka?
```

```
        <source>Wallet encrypted</source>
        <translation>an yi nasarar sakaye walet</translation>
    
YES
The translation "an yi nasarar sakaye walet" is problematic. "an yi nasarar" means "success has been achieved" or "it was successful," which is not a direct or accurate translation of "Wallet encrypted." The correct translation should straightforwardly convey that the wallet has been encrypted, not that the encryption was successful.

Correct translation:
An kulle walet da boye-boye (or simply) An sakaye walet

(Preferably: "An sakaye walet" meaning "Wallet encrypted.")
```

```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>shigar da tsoho da sabon laƙabin sirrin walet din</translation>
    
YES
The translation omits "Enter" (should be imperative), and "passphrase" is rendered as "laƙabin sirri," which could be clearer as "kalmar sirri" or "jimlar kalmomin sirri". The structure is also incomplete; it should ensure both old and new passphrases for the wallet are referenced explicitly.

Correct translation:
Shigar da tsohuwar kalmar sirri da sabuwar kalmar sirri don walet ɗin.
```

```
        <source>Wallet to be encrypted</source>
        <translation>walet din da ake buƙatan sakayewa</translation>
    
YES
The translation has some issues:
- "walet din da ake buƙatan sakayewa" literally means "the wallet that needs to be sent" (saka in "sakawa" is to send/insert/put, and "sakayewa" can be read as a nominalization of that), which is inaccurate. 
- The English source is about encryption ("to be encrypted"), not sending/transmitting.
- The correct term for "encrypt" in Hausa is "ƙuntatawa" or "lakantawa" or directly describing "yi wa walet ɗin kati" (to lock/protect the wallet).

Correct translation:
"Aka tsara a ƙuntata walet ɗin" or "Aka za a ƙuntata walet ɗin" or, more clearly: "Walet ɗin da za a ɓoye/ƙuntata"

Best natural alternative:
Walet ɗin da za a ɓoye ta hanyar ƙuntatawa
```

```
        <source>Your wallet is about to be encrypted. </source>
        <translation>ana daf da sakaye walet</translation>
    
YES
The translation "ana daf da sakaye walet" is incorrect and ungrammatical in Hausa. The phrase does not convey the intended meaning of "Your wallet is about to be encrypted." Additionally, "walet" is a transliteration that could be replaced with "walet ɗinka" to indicate possession ("your wallet"), and the concept of "to be encrypted" should be clearly stated.

Correct translation:
Ana shirin ɓoye walet ɗinka da lamba sirri.
```

```
        <source>Your wallet is now encrypted. </source>
        <translation>ka yi nasarar sakaye walet dinka</translation>
    
YES
The translation is inaccurate and ungrammatical. The phrase "ka yi nasarar sakaye walet dinka" translates back roughly as "you have succeeded in hiding your wallet," which does not correctly convey "Your wallet is now encrypted." It also has capitalization issues (should start with a capital letter), and "sakaye" is more "to hide" than "to encrypt".

Correct translation:
An saka wurin ajiya (wallet) naka cikin lambar sirri yanzu. 

Or a simpler, more direct option:
Wallet ɗinka yana yanzu a kulle da lamba.

Either option is more accurate and natural.
```

```
        <source>Wallet encryption failed</source>
        <translation>ba ayi nasarar sakaye walet ba</translation>
    
YES
The translation is problematic. The phrase "ba ayi nasarar sakaye walet ba" is grammatically incorrect in Hausa and unnaturally structured. The usage of "ba...ba" is redundant and confusing. 

Correct translation:
Ba a iya kulle walet ba
or
Kulle walet ya kasa
```

```
        <source>Export</source>
        <translation> Fitarwa</translation>
    
YES
There is an unwanted leading whitespace in the translation (" Fitarwa") which may cause formatting issues. It should match the source formatting without extra spaces.

Correct translation:
<translation>Fitarwa</translation>
```
</details>
