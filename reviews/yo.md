# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Byo%5D%20request)



<details><summary>yo</summary>


<!-- cache_translation_check_yo_d9288b7b59917831dea01900fde8afc5b51e44b514f296cfe13868edd23ccc66 -->
```
        <source>Create a new address</source>
        <translation>si adireesi tuntun</translation>
    
ERR
The translation is not accurate. "si adireesi tuntun" literally means "do new address" or "make new address", but the imperative verb "Create" in Yoruba should be "Ṣẹda" or "Ṣẹda adirẹsi tuntun".

Correct translation:
Ṣẹda adirẹsi tuntun
```

<!-- cache_translation_check_yo_f3dbced73b555ac22731dff9b97ff0c9ba9eea803ccc04d5ecbab304dba3a53e -->
```
        <source>&amp;New</source>
        <translation>&amp;ati tuntun</translation>
    
ERR
The Yoruba translation is incorrect. "ati tuntun" means "and new" — the conjunction "ati" is wrong here. The source "&New" should be a single-word label (e.g. "New" -> "Tuntun" or "Titun") and must contain exactly one ampersand.

Correct translation:
&Tuntun
```

<!-- cache_translation_check_yo_d356dc0a6425c7e3f029429cc5c9edfacd273899a7ead8bb74df18680f536451 -->
```
        <source>&amp;Copy</source>
        <translation>daako</translation>
    
ERR
Problems:
- The source contains a single ampersand (&) indicating a keyboard shortcut; the translation omits it. The translation must include exactly one &.
- The Yoruba word should reflect the correct form; common rendering is "Daakọ" (or "Daako" if diacritics are not used).

Correct translations (choose one depending on diacritic support):
- With diacritic: &Daakọ
- Without diacritic: &Daako
```

<!-- cache_translation_check_yo_0722a1013c5718fa8097b816750734265cd0786964d53ab1c4f34aca96298381 -->
```
        <source>C&amp;lose</source>
        <translation>paade</translation>
    
ERR
Problems:
- The translation is missing the required ampersand (&) that marks the shortcut key (the source contains exactly one '&').
- Casing: UI labels typically capitalize the first letter; "paade" is all lowercase.
- The Yoruba word used is questionable/unclear for the intended UI action "Close".

Suggested correction:
- Use a short, clear Yoruba label with exactly one '&'. For example:
&Pa

(Here "Pa" is the Yoruba verb for "close" and the '&' supplies the keyboard shortcut.)
```

<!-- cache_translation_check_yo_b26d4ca9b0c3e25fd70b10f7a36a59100587165233a2b9a4f621ef20559727ba -->
```
        <source>&amp;Export</source>
        <translation>ìkójáde</translation>
    
ERR
The translation is missing the required ampersand (&) shortcut marker present in the source. Also ensure the ampersand appears exactly once and there are no extra spaces.

Correct translation suggestion:
&amp;ìkójáde
```

<!-- cache_translation_check_yo_646e01d507f95cb5442c6d5c4d6b0d6db2c26fcddf0bf2aa4496c6fee13a4513 -->
```
        <source>&amp;Delete</source>
        <translation>Pàrẹẹ</translation>
    
ERR
The translation is missing the required shortcut marker "&" (present in the source as "&Delete"). Also "Pàrẹẹ" is unusual in Yoruba for a UI label.

Suggested correction (with single &):
&Pa
```

<!-- cache_translation_check_yo_31c32dbd3198283ce552b8a92b340d3ae427c7c033f0b9fd0c3303b49023bb72 -->
```
        <source>Choose the address to receive coins with</source>
        <translation>Yan àdírẹ́sì láti gba owó àpólà</translation>
    
ERR
"owó àpólà" is questionable/unnatural in Yoruba; it doesn't clearly convey "coins" in this Bitcoin context. A clearer translation would explicitly indicate choosing the address you'll use to receive coins.

Correct translations:
- Yan àdírẹ́sì tí o máa fi gba owó
- Yan àdírẹ́sì láti gba owó (concise)
```

<!-- cache_translation_check_yo_afd8e24b8c372c917f278240c572fd2053eb19acf5074cb52d7d44c9deb2f520 -->
```
        <source>C&amp;hoose</source>
        <translation>yan</translation>
    
ERR
The translation is missing the required mnemonic ampersand from the source (C&amp;hoose). Also capitalization may be adjusted. Correct translation should include exactly one '&'.

Suggested correction:
<translation>&yan</translation>
```

<!-- cache_translation_check_yo_b1c4d6768f27b92872ec93d18e16f8a2b6fa1bd7ba6cb15c3c664954fac4aa3f -->
```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Àwọn àdírẹ́sì Bitcoin rẹ fún gbigba owó àpólà ni wọ̀nyí. Lo bọ́tìnì ‘Ṣẹ̀dá àdírẹ́sì agbàwọlé tuntun’ nínú taabu gbigba láti ṣẹ̀dá àwọn àdírẹ́sì tuntun
Fífọwọ́sowọ́pọ̀ jẹ́ ẹni pé ó ṣeé ṣe pẹ̀lú àwọn àdírẹ́sì irú ‘legacy’ nìkan</translation>
    
ERR
Minor grammatical/format issues and missing punctuation. The second sentence is slightly awkward in Yoruba and the first sentence lacks a terminating punctuation mark. Also put a period or newline consistently.

Suggested correction:
Àwọn àdírẹ́sì Bitcoin rẹ fún gbigba owó ni wọ̀nyí. Lo bọtìnì “Ṣẹ̀dá àdírẹ́sì agbàwọlé tuntun” nínú taabu Gbigba láti ṣẹ̀dá àwọn àdírẹ́sì tuntun.
Fífọwọ́sowọ́pọ̀ ṣeé ṣe nikan pẹlu àwọn àdírẹ́sì tí ìrú wọn jẹ́ “legacy”.
```

<!-- cache_translation_check_yo_f421d140ca6cae3a3e2dda346dff994088271d25c058d151a47d2b281c4ee49e -->
```
        <source>&amp;Copy Address</source>
        <translation>Ṣàfọwọ́kọ Àdírẹ́sì</translation>
    
ERR
Problems:
- The translation uses "Ṣàfọwọ́kọ Àdírẹ́sì", which in Yoruba more closely relates to "sign" or "to sign an address" rather than "copy". The correct verb for "copy" is typically "Daakọ" (or "Ṣe ẹda").
- The source contains a single & to mark a keyboard shortcut (&Copy Address). The translation must also include exactly one & but the provided translation has none.

Correct translation suggestion (with a single & for the shortcut):
&Daakọ Àdírẹ́sì
```

<!-- cache_translation_check_yo_3817a73934a4f4c997b2c3b0cfd35b2718843ee4152aeaea97adf099b263cfc1 -->
```
        <source>Copy &amp;Label</source>
        <translation>Ṣàfọwọ́kọ Àkọlé</translation>
    
ERR
The translation is missing the required shortcut ampersand and the verb choice is questionable. Also Yoruba for "Copy" is better rendered as "Daakọ".

Correct translation:
Daakọ &Àkọlé
```

<!-- cache_translation_check_yo_18962dec4ab7716bf21b4d78739dc3e2934c6c5f23222da9225c0105f34108a6 -->
```
        <source>&amp;Edit</source>
        <translation>Ṣàtúnṣe</translation>
    
ERR
The source contains an accelerator indicator "&" which must be carried into the translation exactly once. The Yoruba translation is correct linguistically but is missing the "&". 

Correct translation:
&amp;Ṣàtúnṣe
```

<!-- cache_translation_check_yo_aa3ef41558154092627e6327caafa2a96887a58fea28118f8d1ba323cc1bea66 -->
```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Àṣìṣe kan wáyé nígbà tí a ń gbìyànjú láti fipamọ́ àtòjọ àdírẹ́sì sí %1. Jọ̀wọ́, gbìyànjú lẹ́ẹ̀kansi</translation>
    
ERR
The translation is accurate and preserves the placeholder %1, but it is missing the final punctuation (period) present in the source. Add the period at the end to match punctuation.

Correct translation:
Àṣìṣe kan wáyé nígbà tí a ń gbìyànjú láti fipamọ́ àtòjọ àdírẹ́sì sí %1. Jọ̀wọ́, gbìyànjú lẹ́ẹ̀kansi.
```

<!-- cache_translation_check_yo_ba8a6aed15099134246af2d8d2aa87d1a7e267d86555d99ce3c720199a2b8637 -->
```
        <source>Sending addresses - %1</source>
        <translation>fífi àwọn àdírẹ́sì ránṣẹ́-%1</translation>
    
ERR
The translation mostly conveys the meaning but has formatting and style issues: there's no space before the dash (source has spaces around the dash), and capitalization/word choice could be improved for natural Yoruba.

Corrected translation:
Fífí àwọn àdírẹ́sì ránṣẹ́ - %1
```

<!-- cache_translation_check_yo_96ca6fc92ebd4efc9439cd46d3f6351fddb61710ab2c8d1fb6f802f0231e2508 -->
```
        <source>Passphrase Dialog</source>
        <translation>Férèsé Ọ̀rọ̀-ìfàṣẹsí</translation>
    
ERR
The Yoruba translation looks awkward and likely incorrect: "Férèsé Ọ̀rọ̀-ìfàṣẹsí" is a nonstandard transliteration and "ọ̀rọ̀-ìfàṣẹsí" is not a natural rendering of "passphrase" or "dialog". 

Suggested correct translation:
Àpótí ìbánisọ̀rọ̀ Ọ̀rọ̀-ìwọlé

(Alternative shorter option: "Àpótí Ọ̀rọ̀-ìwọlé")
```

<!-- cache_translation_check_yo_849e3e5e50e1a64a0a27a3f8a2eba1f90229429ddacdcc57bbe4339967f61768 -->
```
        <source>New passphrase</source>
        <translation>ọ̀rọ̀-ìfàṣẹsí tuntun</translation>
    
ERR
The given Yoruba term "ọ̀rọ̀-ìfàṣẹsí tuntun" is questionable: "ìfàṣẹsí" is not the usual word for passphrase/password and the hyphenation is atypical. No format specifiers or spacing issues were present.

Suggested correct translation (natural Yoruba for "New passphrase"):
Ọ̀rọ̀ ìgbaniwọlé tuntun

Alternatively, you can use:
Ọ̀rọ̀ aṣínà tuntun
```

<!-- cache_translation_check_yo_63f7ff11ff88514059799575db7b1ec9ef74f7200306b178bacd017598ec9c3a -->
```
        <source>Encrypt wallet</source>
        <translation>Ṣìfúná apò-owó</translation>
    
ERR
"Ṣìfúná apò-owó" is not a natural or correct Yoruba rendering of "Encrypt wallet". There are no format specifiers to preserve, and no whitespace issues, but the verb choice is incorrect.

Suggested correct translation:
Fi apò-owó sí ìkọkọ́

(literal: "Put the wallet into secrecy" — appropriate for "Encrypt wallet")
```

<!-- cache_translation_check_yo_cebb727084829e140555a75c20efafa609bb4a0389eed288d3aac016902f74e0 -->
```
        <source>Change passphrase</source>
        <translation>Ṣàtúnṣe ọ̀rọ̀-ìfàṣẹsí</translation>
    
ERR
The Yoruba phrase "Ṣàtúnṣe ọ̀rọ̀-ìfàṣẹsí" is awkward/unidiomatic—the compound "ọ̀rọ̀-ìfàṣẹsí" is not a standard word for "passphrase/password" in Yoruba. No format specifiers or spacing issues.

Correct translation suggestions:
- Ṣàtúnṣe ọrọ igbaniwọlé
or more literally
- Yi ọrọ igbaniwọlé pada
```

<!-- cache_translation_check_yo_f0bb7ba281de937d5f985a36b1fbb1d0f46ff2ee2aecdedda2ee96f16018f4a4 -->
```
        <source>Confirm wallet encryption</source>
        <translation>Ṣàfihàn ìdánimọ̀ ìṣìfúná apò-owó</translation>
    
ERR
The translation is inaccurate. "Ṣàfihàn" means "show/display" and "ìdánimọ̀" means "identification", so the phrase reads more like "Show the identification of the wallet encryption" rather than the intended command/title "Confirm wallet encryption".

Corrected translation (Yoruba):
Jẹ́risi ìfídí ìṣìfúná apò-owó múlẹ̀

(Note: there are no format specifiers in the source; none are needed in the translation.)
```

<!-- cache_translation_check_yo_7ae40bed0ead948f30db72a884671945d3ac4256235efcb0e6b890038b6e41c9 -->
```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Ìkìlọ̀: Bí o bá ṣìfúná apò-owó rẹ tí o sì pàdánù ọ̀rọ̀-ìfàṣẹsí rẹ, ìwọ yóò&lt;b&gt;ìwọ yóò sọnù gbogbo àwọn Bitcoin rẹ&lt;/b&gt;!</translation>
    
ERR
The translation has a duplicated phrase ("ìwọ yóò" appears twice) and slightly awkward wording for "encrypt your wallet". Also the HTML bold tags must be preserved correctly.

Corrected translation:
Ìkìlọ̀: Bí o bá ṣìfún apò-owó rẹ tí o sì pàdánù ọ̀rọ̀-ìfàṣẹ́ rẹ, &lt;b&gt;ìwọ yóò pàdánù GBOGBO BITCOIN RẸ&lt;/b&gt;!
```

<!-- cache_translation_check_yo_f77c862baaeae04faa14bc918b48e59f97306f684500e223f3dab4d62484fd6e -->
```
        <source>Are you sure you wish to encrypt your wallet?</source>
        <translation>Ṣé o dájú pé o fẹ́ ṣìfúná apò-owó rẹ?</translation>
    
ERR
The verb "ṣìfúná" is nonstandard/unusual for "encrypt" in Yoruba. No format specifiers or spacing issues, but the phrasing should use a clearer verb for "encrypt."

Correct translation suggestion:
Ṣé o dájú pé o fẹ́ fi apò-owó rẹ sínú ìpamọ́?
```

<!-- cache_translation_check_yo_ecc75d86578e3ab328cacac409dca5de5415362351663b89dd2c2c4111424f78 -->
```
        <source>Wallet encrypted</source>
        <translation>Apò-owó ti ṣìfúná</translation>
    
ERR
The Yoruba translation "Apò-owó ti ṣìfúná" is awkward/unidiomatic and likely incorrect for "Wallet encrypted". No format specifiers are involved.

Suggested correction (more natural Yoruba):
Apò-owó ti fipamọ́ pẹ̀lú ìkọ́kọ́
```

<!-- cache_translation_check_yo_e5219e340550d693dba092f808feee5e3807be78f90fd3159d4ad7b52d5154e5 -->
```
        <source>Wallet to be encrypted</source>
        <translation>Apò-owó tí yóò ṣìfúná</translation>
    
ERR
The Yoruba verb "ṣìfúná" is nonstandard/unclear for "to be encrypted." A clearer natural translation is:

Correct translation:
Apò-owó tí a ó fi ìkọ́kọ́ pamọ́
```

<!-- cache_translation_check_yo_261034b3fb6872fd458148d61c0d24fdf55ed1b8d3eac8236d3e82c51a7c1452 -->
```
        <source>Your wallet is about to be encrypted. </source>
        <translation>Apò-owó rẹ̀ ti máa ṣìfúná lọ́jọ́gbọ̀n.</translation>
    
ERR
The Yoruba sentence is awkward/incorrect: "ṣìfúná lọ́jọ́gbọ̀n" is not a proper rendering of "be encrypted" and reads oddly. No format specifiers issues.

Suggested correct translation:
Apò-owó rẹ̀ yóò di ìfipamọ́.

(Alternative more explicit option: "Apò-owó rẹ̀ máa di ìkọ̀kọ̀/ìfipamọ́." )
```

<!-- cache_translation_check_yo_9437a9206b442a7903faf296fab970fc0b15df3a482123ee2c1ec0e2354d7bc1 -->
```
        <source>Your wallet is now encrypted. </source>
        <translation>Apò-owó rẹ̀ ti ṣìfúná báyìí.</translation>
    
ERR
The Yoruba phrasing "Apò-owó rẹ̀ ti ṣìfúná báyìí." is awkward/unnatural for "Your wallet is now encrypted." The verb "ṣìfúná" is not the common way to express "encrypted" in Yoruba, and "Apò-owó" is usually written "Apamọwọ" or "Apò owó". Also the source had a trailing space — ensure no unintended spacing.

Suggested correction:
Apamọwọ rẹ̀ ti di ìkọ̀kọ̀ báyìí.
```

<!-- cache_translation_check_yo_9c243e187dbdfc96336460ed941c14137247833ff4be96c906891f132ba66fa6 -->
```
        <source>Wallet encryption failed due to an internal error. Your wallet was not encrypted.</source>
        <translation>Ìṣìfúná apò-owó ṣìṣe kò ṣàṣeyọrí nítorí àṣìṣe inú eto. Apò-owó rẹ kò tíì jẹ́ kí o ṣìfúná</translation>
    
ERR
The Yoruba translation is understandable but has grammatical issues and a slightly incorrect second sentence that changes the meaning (it reads more like "your wallet didn't let you encrypt it"). Also some word choices/word order are awkward.

Suggested correct translation:
Ìfipamọ́ (ìṣífúnà) apò-owó kọ́ ṣàṣeyọrí nítorí àṣìṣe inú eto. Apò-owó rẹ kò tíì ṣífúnà.
```

<!-- cache_translation_check_yo_8123ae25adc6926eb27ffd61c05468ede4979a77b2a846806d26ac5de3a87dea -->
```
        <source>Passphrase change failed</source>
        <translation>Ìyípadà ọ̀rọ̀-ìfàṣẹsí kò ṣàṣeyọrí</translation>
    
ERR
The translation is mostly understandable but the term "ọ̀rọ̀-ìfàṣẹsí" is uncommon for "passphrase" in Yoruba. Better to use "ọrọigbaniwọle" or "ọrọ aṣínà" for passphrase/password. No format specifiers or spacing issues.

Suggested correction:
Ìyípadà ọrọigbaniwọle kò ṣàṣeyọrí
```

<!-- cache_translation_check_yo_e1b5d37d282494f1991497ef0563baad9b6af3be0a08843efeac7bb7360b5530 -->
```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Fáìlì ìṣètò%1lè ti bàjẹ́ tàbí kò tọ́́</translation>
    
ERR
The translation has spacing issues around the format specifier %1 (no space between "ìṣètò" and "%1" and none after %1), and the Yoruba phraseing can be improved.

Correct translation:
Fáìlì ìṣètò %1 lè ti bàjẹ́ tàbí kò tọ́.
```

<!-- cache_translation_check_yo_3a296568143b5f95c4d2073cd51eb326725ff3ab07ba96c782825f73d1b24e69 -->
```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>Àṣìṣe pàtàkì kan wáyé. %1 Kò lè tẹ̀síwájú láìsí ewu mọ́, a ó sì dá ìṣèjọba dúró.</translation>
    
ERR
The translation mostly conveys the meaning, but it uses "ìṣèjọba" (government), which is incorrect in this context; the source means the program will quit, not stop a government. Also adjust wording for more natural Yoruba.

Correct translation:
Àṣìṣe pàtàkì kan wáyé. %1 kò lè tẹ̀síwájú ní ààbò mọ́, yóò sì dá iṣẹ́ dúró.
```

<!-- cache_translation_check_yo_90da0a967bb3648ea3d7ccf01163f7753e9e891c70a398df4d5949de41f543f9 -->
```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>Àṣìṣe inú eto kan wáyé.%1 A máa gbìyànjú láti tẹ̀síwájú láìsí ewu. Èyí jẹ́ kokoro àìmọ̀tótó tí ó lè jẹ́ pé a lè rọ́pọ̀ rẹ gẹ́gẹ́ bí a ṣe ṣàlàyé ní isalẹ.</translation>
    
ERR
Problems:
- Missing space before the %1 placeholder: "wáyé.%1" should be "wáyé. %1".
- The phrase "a lè rọ́pọ̀ rẹ" is incorrect for "can be reported" (it reads like "can be replaced"); the correct idea is "can be reported" (ròyìn).

Corrected translation:
Àṣìṣe inú eto kan wáyé. %1 yóò gbìyànjú láti tẹ̀síwájú láìsí ewu. Èyí jẹ́ kokoro àìmọ̀tótó tí a lè ròyìn gẹ́gẹ́ bí a ṣe ṣàlàyé ní isalẹ.
```

<!-- cache_translation_check_yo_7403efcdf38edba6271c670e51d15d69e10acbb150f2f840af8103c7650daf5b -->
```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>Àṣìṣe pàtàkì kan wáyé. Ṣàyẹ̀wò pé fáìlì ìṣètò lè kọ́wé, tàbí gbìyànjú láti ṣiṣẹ́ pẹ̀lú - Kò sí ìṣètò.</translation>
    
ERR
The command-line option "-nosettings" was translated into Yoruba ("- Kò sí ìṣètò") and a space was added after the hyphen. CLI flags must be kept exactly as in the source (no translation, no extra spaces). Otherwise the Yoruba is acceptable.

Correct translation:
Àṣìṣe pàtàkì kan wáyé. Ṣàyẹ̀wò pé a lè kọ́ sí fáìlì ìṣètò, tàbí gbìyànjú láti ṣiṣẹ́ pẹ̀lú -nosettings.
```

<!-- cache_translation_check_yo_7767bad4ae97ff8e454f22e1bbacb80713bab222a7588422bef4665f2efd544a -->
```
        <source>%1 didn't yet exit safely…</source>
        <translation>%1 Kò tíì jáde láìsí ààbò…</translation>
    
ERR
The Yoruba translation is misleading. "Kò tíì jáde láìsí ààbò…" literally says "has not yet exited without safety" (i.e. negating "without safety"), which is confusing and likely the opposite of the intended meaning ("hasn't yet exited safely" / "didn't yet exit safely"). Also adjust capitalization to match original tone.

Correct translation:
%1 kò tíì jáde ní ààbò…
```

<!-- cache_translation_check_yo_0c31b571566ab5ab6dee76c3f3b73a973c989a134e13fb10705dfd207f66d2b0 -->
```
        <source>&amp;Overview</source>
        <translation>Àkótán</translation>
    
ERR
The Yoruba translation is correct meaning-wise ("Àkótán" = "Overview") but it omits the required shortcut ampersand from the source. Include a single & in the translation (no extra spaces).

Correct translation:
&amp;Àkótán
```

<!-- cache_translation_check_yo_e4e0f09bc081971813149198ed9d2951071fb99f5bc1ed492d9b7d6d72f4b9ba -->
```
        <source>Show general overview of wallet</source>
        <translation>Fihàn àkótán gbogbogbò ti apò-owó</translation>
    
ERR
Minor spelling error in Yoruba: "gbogbogbò" is incorrect. Also prefer "àkótán gbogbogbo" for "general overview".

Correct translation:
Fihàn àkótán gbogbogbo ti apò-owó
```

<!-- cache_translation_check_yo_942900a030d5ba298df0fbc2d8bf0e443ef24c26e922851a11b0eab51f80bfac -->
```
        <source>&amp;Transactions</source>
        <translation>Àwọn ìṣàkóso owó</translation>
    
ERR
Problems:
- The translation "Àwọn ìṣàkóso owó" means something like "money controls" rather than "Transactions".
- The source contains a single & (menu shortcut) which must also appear exactly once in the translation; the provided translation has no &.

Corrected translation (include one & for the shortcut):
&Àwọn ìṣowó
```

<!-- cache_translation_check_yo_9e729fc145f3ec65ab23f80894d6ee713c2caf8fa6286803cc1c3e9a858cff27 -->
```
        <source>Browse transaction history</source>
        <translation>Ṣàwárí ìtàn ìṣàkóso owó</translation>
    
ERR
The Yoruba phrase given ("Ṣàwárí ìtàn ìṣàkóso owó") reads as "Browse history of money management/control," which is slightly off: it implies managing money rather than browsing transaction/payment history. No format-specifier or whitespace issues.

Suggested better translation:
Ṣàwárí ìtàn àwọn ìsanwó
```

<!-- cache_translation_check_yo_c1a68c6a6f70e648063a6b96e4fbb2022419483458c769cbc620ac75ed07e307 -->
```
        <source>E&amp;xit</source>
        <translation>Jáde</translation>
    
ERR
The translation is correct Yoruba for "Exit" ("Jáde"), but it is missing the shortcut marker (&). The source has a single & for the mnemonic and the translation must include exactly one & as well.

Correct translation (with mnemonic on J):
    <translation>&amp;Jáde</translation>
```

<!-- cache_translation_check_yo_6fb331185952481253a32ca977aece6dcdf5d07c8748ad053658d312ff83f7c1 -->
```
        <source>Quit application</source>
        <translation>Dákẹ́ àpèsè náà</translation>
    
ERR
The Yoruba translation "Dákẹ́ àpèsè náà" literally means "silence/mute the device" and does not convey "quit the application." No format specifiers are involved.

Correct translation:
Pa ohun elo náà
```

<!-- cache_translation_check_yo_3f1b950d4ff3045ba00e973b4b5489d57e53d8ad773b9e0935dffc33eec86731 -->
```
        <source>&amp;About %1</source>
        <translation>Nípa %1</translation>
    
ERR
The translation is missing the shortcut indicator (&) present in the source. The format specifier %1 is correct. 

Correct translation:
&amp;Nípa %1
```

<!-- cache_translation_check_yo_bb08d03e19f15e9cf7c747b7cb7bfad0c5a13cafd1be7dfb0718a6b32c442480 -->
```
        <source>About &amp;Qt</source>
        <translation>Nípa Qt</translation>
    
ERR
The translation is missing the shortcut key indicator '&' which is present in the source text. In Yoruba, the shortcut indicator should be preserved.

Correct translation:
Nípa &Qt
```

<!-- cache_translation_check_yo_e8bc4107fcad507f57f05a2701e4167b3ac84644c86e2d1d85305d032eb21a04 -->
```
        <source>&amp;Minimize</source>
        <translation>Dín kékè</translation>
    
ERR
The translation is missing the shortcut indicator "&" that appears in the source. Also ensure the ampersand appears exactly once.

Correct translation:
&amp;Dín kékè
```

<!-- cache_translation_check_yo_8a00a405aa96e0e401d36f7fcf763a1d91349e28b8a9d4d3763bbd60d518a554 -->
```
        <source>&amp;Send</source>
        <translation>Gba</translation>
    
ERR
The translation "Gba" means "Receive" or "Accept" in Yoruba, which is the opposite of the source text "Send". Additionally, the shortcut key indicator '&' is missing from the translation.

Correct translation:
&Fi ránṣẹ
```

<!-- cache_translation_check_yo_bfe41e92522a849e5e20d191d398148dd7fe51b1d427a235c9fc8b17ddc11db2 -->
```
        <source>&amp;Receive</source>
        <translation>Fifun ni</translation>
    
ERR
The translation is incorrect and missing the required shortcut key marker. "Fifun ni" means "to give" or "giving" in Yoruba, which is the opposite of "receive". Additionally, the '&' shortcut key marker from the source is missing.

Correct translation:
&Gbà
```

<!-- cache_translation_check_yo_4979d04a30781cee4be4d011e089a92c8f8288d08f8fddcb205f6bcac93f95a7 -->
```
        <source>&amp;Options…</source>
        <translation>Àwọn àṣàyàn</translation>
    
ERR
The translation is missing the shortcut key indicator '&' and the ellipsis '…' from the source text. According to the instructions, the '&' symbol must exist exactly once in the translation.

Correct translation:
&Àwọn àṣàyàn…
```

<!-- cache_translation_check_yo_5c491ebade22c3f8a2656e39c9e524ae55bf0c0a9e16fbca4a1ae626b982f83e -->
```
        <source>&amp;Verify message…</source>
        <translation>Ṣàyẹ̀wò ìfiranṣẹ</translation>
    
ERR
The translation is missing the required shortcut key indicator '&' and the ellipsis '…' (or '...') from the source text.

Correct translation:
Ṣ&àyẹ̀wò ìfiranṣẹ…
```

<!-- cache_translation_check_yo_bbd25b095a5c8dd3bfca552d5bbe85a229d2ee2e42286b0c66e3e67a2d40aeba -->
```
        <source>Open &amp;URI…</source>
        <translation>Sí URL</translation>
    
ERR
The translation is missing the required shortcut key indicator (&amp;) and the ellipsis (…). Additionally, "URI" was changed to "URL", and "Sí" is a preposition in Yoruba; the verb for "Open" is "Ṣí".

Correct translation:
Ṣí &amp;URI…
```

<!-- cache_translation_check_yo_e0e28d5c1fc01ba46512bd5ebb2c988dc5b327d3c1c14fc2e8b059fb56e6201f -->
```
        <source>Close Wallet…</source>
        <translation>Sí àpò ìpamọ́</translation>
    
ERR
The translation is incorrect. "Sí" in Yoruba means "to open", but the English source word is "Close". The correct word for "close" in this context is "Tì".

Correct translation:
Tì àpò ìpamọ́…
```

<!-- cache_translation_check_yo_169a4744d5c7ff1e8ffa19f4a465297cae234984ce715e30e7636899a028f3e6 -->
```
        <source>Create Wallet…</source>
        <translation>Sí àpò ìpamọ́</translation>
    
ERR
The translation means "Open wallet" rather than "Create Wallet". The verb "Sí" means "Open", whereas "Create" should be translated as "Dá" or "Ṣẹ̀dá". Additionally, the ellipsis (…) is missing.

Correct translation:
Dá àpò ìpamọ́…
```

<!-- cache_translation_check_yo_50b34740a91b47e89adfc6a01ef103c5e0faa382a6e34d493f6fb33bdd57fc5a -->
```
        <source>Close All Wallets…</source>
        <translation>Pa gbogbo àpò ìpamọ́ de</translation>
    
UNK_LANG, not familiar with the Yoruba language 'yo'.
```

<!-- cache_translation_check_yo_15e37df56fb15fabd49b231daece69e63971c71357d08536eaf2110c669e7dda -->
```
        <source>&amp;File</source>
        <translation>Fáìlì</translation>
    
ERR
The translation is missing the ampersand (&) used to indicate the shortcut key.

Correct translation:
&Fáìlì
```

<!-- cache_translation_check_yo_ce2ab7bfbfe550fed0dd6a9f45553d3dcd2b715d3e10528f24bf0416f0c90d9b -->
```
        <source>&amp;Settings</source>
        <translation>Àwọn ètò</translation>
    
ERR
The translation is missing the shortcut key indicator '&' which was present in the source text. In the context of the provided instructions, the '&' must exist exactly once in the translation.

Correct translation:
&Àwọn ètò
```

<!-- cache_translation_check_yo_da14711050610aec3a737be1029d94c1236ae12695ddaea0414f08d0db1b1355 -->
```
        <source>&amp;Help</source>
        <translation>Ìrànlọ́wọ́</translation>
    
ERR
The translation is missing the shortcut key indicator '&' which was present in the source text. In the context of the Yoruba language 'yo', the translation for "Help" is correct, but the format specifier must be preserved.

Correct translation:
&Ìrànlọ́wọ́
```

<!-- cache_translation_check_yo_8b77b4e8bd7471b9330a44fb9a6daf4c9125ba0e1317762f579c247086973a31 -->
```
        <source>&amp;OK</source>
        <translation>&amp;o da</translation>
    
ERR
Problems:
- Extra space: the translation uses "&o da" with a space between "o" and "da".
- Casing and diacritics: Yoruba would typically use "Ó" or "Dára" (with diacritic) rather than plain "o da".
- GUI shortcut convention: the ampersand should appear exactly once and ideally directly before the letter used as the shortcut (no stray spaces).

Suggested corrections (choose one):
- Keep the common UI label: &OK
- Yoruba localized: &Dára

Either option must have no extra spaces and the ampersand exactly once.
```

<!-- cache_translation_check_yo_41370c01d52f9c977db399b87bd15fd1fd396c23803ccd6b6fe04de275489bf5 -->
```
        <source>1 &amp;year</source>
        <translation>okan ati &amp;odun</translation>
    
ERR
The Yoruba translation adds an extra word ("okan ati" = "one and") which is not in the source and changes the meaning. The source uses the numeral "1" and places a single accelerator (&) before "year". The translation should likewise use "1" and place the & once before "odun" (Yoruba "ọdún").

Correct translation:
1 &ọdún

(If you must avoid diacritics: use "1 &odun")
```

<!-- cache_translation_check_yo_b26d4ca9b0c3e25fd70b10f7a36a59100587165233a2b9a4f621ef20559727ba -->
```
        <source>&amp;Export</source>
        <translation>ìkójáde</translation>
    
ERR
The translation is missing the required ampersand (&) shortcut marker present in the source. Also ensure the ampersand appears exactly once and there are no extra spaces.

Correct translation suggestion:
&amp;ìkójáde
```
</details>

Number of issues: 55.
