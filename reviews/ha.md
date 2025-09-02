# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>ha</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bha%5D%20request)


<!-- cache_translation_check_ha_5965cdafc4f31fca281d6d4f84bb70f7fafa86c1a1314de739902f73a3ea3fd3 -->
```
        <source>Delete the currently selected address from the list</source>
        <translation>Share adireshin da aka zaɓa a halin yanzu daga jerin </translation>
    
ERR
The translation is inaccurate. "Share" means "to share" in English, and does not correspond to "Delete". The correct translation for "Delete the currently selected address from the list" in Hausa should be:

Goge adireshin da aka zaɓa a halin yanzu daga jerin

Additionally, there is a stray space at the end of the translation.
```

<!-- cache_translation_check_ha_3843d1767944f100a7f98e4f1397dc98430b00e4069ba7f0cc4e6771ca713a68 -->
```
        <source>Choose the address to receive coins with</source>
        <translation>Zaɓi adireshin don karɓar kuɗi internet da shi</translation>
    
ERR
The translation is mostly accurate but problematic due to the addition of "internet" ("intanet"), which is not present in the source and not relevant in this context. Also, the phrase "da shi" at the end is awkward and not commonly used for this instruction. The translation should be concise and faithful to the source.

Correct translation:
Zaɓi adireshin da za a karɓi kuɗi da shi
```

<!-- cache_translation_check_ha_72a6a49235dfb16f2aa4b84cce8abedf991674daa3aea249a30b56d4b36586d3 -->
```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>Waɗannan adiresoshin Bitcoin ne don tura kuɗi bitcoin . ka tabbatar da cewa adreshin daidai ne kamin ka tura abua a ciki</translation>
    
ERR
There are several issues:
- "adiresoshin" is misspelled; the plural of "adireshi" is "adiresoshin" in Hausa, but the rest of the translation is awkward and contains informal/spoken usages ("abua a ciki" translates as "something inside," which is not clear or appropriate here). 
- The translation omits "Always check the amount" (it does not mention the amount).
- "Ka tabbatar da cewa adreshin daidai ne kamin ka tura abua a ciki" is not a faithful or clear rendering of "Always check the amount and the receiving address before sending coins."
- "bitcoin" should not be repeated after "kuɗi".

Correct translation:
Waɗannan su ne adireshin Bitcoin ɗinka don aika kuɗi. Koyaushe tabbatar da adadin da adireshin mai karɓa kafin ka tura kuɗi.
```

<!-- cache_translation_check_ha_19dc30d5df69494ec54b2f2845986314eb8d636efa8ab25b4c60b9cd1a73c4ed -->
```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Waɗannan adiresoshin Bitcoin ne don karɓar kuɗi. Yi amfani da maɓallin 'Ƙirƙiri sabon adireshin karɓa' a cikin shafin karɓa don ƙirƙirar sababbin adireshi.
zaka iya shiga ne kawai da adiresoshin 'na musamman' kawai.</translation>
    
ERR  
The translation has several issues:
- The term "signing" (probably means cryptographic signing) is not directly rendered; "zaka iya shiga" rather means "you can log in," which is incorrect.  
- The phrase "addresses of the type 'legacy'" is mistranslated as "adiresoshin 'na musamman'" meaning "special addresses," which is not accurate for "legacy."
- There is inconsistency in technical vocabulary.
- "adiresoshin" used in plural, but in one sentence "adireshi" (singular) is used, which should be consistent.

Correct translation:
Waɗannan su ne adiresoshin Bitcoin ɗinka na karɓar kuɗi. Yi amfani da maɓallin 'Ƙirƙiri sabon adireshin karɓa' a shafin karɓa don ƙirƙirar sababbin adiresoshi.  
Ana iya yin sa hannu kawai da adiresoshin nau'in 'legacy' kawai.
```

<!-- cache_translation_check_ha_a10e1123c73eb7899c5894d6f07b4f7ffd2ff9333c54d138ef7dff582fa36831 -->
```
        <source>Encrypt wallet</source>
        <translation>sakaye walet</translation>
    
ERR
The translation is understandable but not ideal. In Hausa, capitalization should match the source, and "encrypt" is better translated as "Kulle" or "Shiga lambobi" rather than the borrowed "sakaye", which means "to hide" and does not specifically imply encryption. "Walet" is a loanword, but commonly used.

Correct translation:
Kulle walet
```

<!-- cache_translation_check_ha_5bfe42d443e154a83c0e080d81d004c3fb6c30155ef923c31a018d30c2eb6ad8 -->
```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>abunda ake son yi na buƙatan laƙabin sirri domin buɗe walet</translation>
    
ERR
The translation is missing some key details from the source text. It does not specify "your wallet passphrase" (instead it just generically says "laƙabin sirri" = passphrase), and it omits subjects/context, making it less formal/accurate.

Correct translation:
Wannan aiki na buƙatar kalmar sirrin walat ɗinka don buɗe walat ɗinka.
```

<!-- cache_translation_check_ha_c9f7d5f08a311f9a00437db19e6e8997f71dda7194b1a6f948a77dfc9f70b09b -->
```
        <source>Confirm wallet encryption</source>
        <translation>tabbar da an sakaye walet</translation>
    
ERR
The translation is not fully accurate. "Tabbar da an sakaye walet" literally translates to "confirm that wallet is hidden", which confuses "encryption" (which is about security, i.e., encryption, not just hiding). The correct way to render "Confirm wallet encryption" is:

Correct translation:
Tabbatar da kulle walet ɗin da kalmar sirri

Alternatively, using the common technical term:
Tabbatar da ɓoye walet ɗin

But "kulle da kalmar sirri" or "ɓoye" is closer to the real meaning than "sakaye" (simply hidden).
```

<!-- cache_translation_check_ha_b8d46161ede2bcb2e9e90d4424a27dcbffe43e5adc49ee2c0e2a1c5ce87af52e -->
```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Jan kunne: idan aka sakaye walet kuma aka manta laƙabin sirri, za a Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt; RASA DUKKAN BITCOINS&lt;/b&gt;!</translation>
    
ERR
The translation is problematic for several reasons:
- The translation mixes Hausa ("idan aka sakaye walet kuma aka manta laƙabin sirri, za a") with redundant English text ("Warning: If you encrypt your wallet and lose your passphrase, you will").
- It introduces "Jan kunne" which is a correct way to say "Warning", but then redundantly includes the English "Warning" again.
- The structure is erratic, and the phrase "za a Warning" is not correct.
- The critical warning part ("LOSE ALL OF YOUR BITCOINS") is only partially translated.

Correct translation:
Jan kunne: Idan ka kulle walet ɗinka kuma ka manta kalmar sirri, za ka &lt;b&gt;RASA DUKKAN BITCOINS ɗIN KA&lt;/b&gt;!
```

<!-- cache_translation_check_ha_0a28c50f400eab84df96135efa860b379819a86d4d9da095ac91512b630f8ac9 -->
```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>ka tabbata kana son sakaye walet?</translation>
    
ERR
The translation has capitalization and politeness issues. In Hausa, sentence-initial capitalization is needed and the verb form should match the formal question. Also, "ka tabbata..." is more like "make sure..." rather than "Are you sure...". The correct translation should be:

Ka tabbata kana so ka ƙirƙiri sirri a walet ɗinka? 

or more simply:

Kana tabbatar kana so ka ɓoye walet ɗinka?
```

<!-- cache_translation_check_ha_bba5901403ae9d5eb2f9a9475bb4b5672fe1194017a47b1952dc049e57c9669c -->
```
        <source>Wallet encrypted</source>
        <translation>an yi nasarar sakaye walet</translation>
    
ERR
The translation "an yi nasarar sakaye walet" is not accurate and is somewhat awkward. The phrase "Wallet encrypted" should translate simply as "An sakaye walet" or "Walet an sakaye" in Hausa, which means "The wallet is encrypted." The word "nasarar" means "success," which is not present in the original English text and makes the translation inaccurate.

Correct translation:
An sakaye walet
```

<!-- cache_translation_check_ha_c1bcafde11c7a857d954d3fd3f8c58d833a295ed9a3d0c723df845750e9acf62 -->
```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>shigar da tsoho da sabon laƙabin sirrin walet din</translation>
    
ERR
The translation omits "Enter" as an imperative verb and is missing the instruction to enter both the old and new passphrases; it also omits the explicit mention of "passphrase" twice (old and new), and is not a full sentence (missing capitalization and finalizing period).

Correct translation:
Shigar da tsohuwar kalmar sirri da sabuwar kalmar sirri don walet ɗin.
```

<!-- cache_translation_check_ha_ee93ecd854875c083db76005d8b85d3554271e0d8b02ac0bcebe57ee811b5df1 -->
```
        <source>Wallet to be encrypted</source>
        <translation>walet din da ake buƙatan sakayewa</translation>
    
ERR
The translation is inaccurate and contains a slight error in meaning and capitalization. "Walet din da ake buƙatan sakayewa" translates roughly to "the wallet that needs to be encrypted," while the source says "Wallet to be encrypted," which should best be translated as "Wallet da za a ƙara wa ƙyamar kalmar shiga" or more simply "Wallet da za a kulle" or "Walet da za a ɓoye" to be precise. Also, "walet" should be capitalized to match the source.

Correct translation:
Walet da za a kulle
```

<!-- cache_translation_check_ha_d63c093b4581ff8c04cae1985f95f0d4f9af1632488b617d82b3bf6525ca6d61 -->
```
        <source>Your wallet is about to be encrypted. </source>
        <translation>ana daf da sakaye walet</translation>
    
ERR
The translation is inaccurate and ungrammatical in Hausa. "ana daf da sakaye walet" is not correct; it is a literal, awkward construction. The correct translation in Hausa should clearly state that the wallet is about to be encrypted (not just "hidden" or "stored away").

Correct translation:
Ana shirin ɓoye walet ɗinka da kalmar sirri.
```

<!-- cache_translation_check_ha_83667fc66db09272cec29f68474acfe4c6a43fe41f6dad885a102937787e0d43 -->
```
        <source>Your wallet is now encrypted. </source>
        <translation>ka yi nasarar sakaye walet dinka</translation>
    
ERR
The translation is not accurate and does not match the tone of the original. The English sentence is a plain statement, while the translation adds "ka yi nasarar" (you have succeeded in), which implies an action by the user and changes the tone.

Correct translation:
An sakaye walet ɗinka yanzu.
```

<!-- cache_translation_check_ha_b278aca4e9d196017b4557a425394dc6b3531feb7ddc7ef75545954b4e0b5399 -->
```
        <source>Wallet encryption failed</source>
        <translation>ba ayi nasarar sakaye walet ba</translation>
    
ERR
The translation is understandable but contains grammatical errors and unnecessary repetition of "ba" (meaning "not" or "no" in Hausa) at the start and end, making it unidiomatic and awkward.

Correct translation:
Sakawa walet lamba ya kasa
```
</details>

Number of issues: 15.
