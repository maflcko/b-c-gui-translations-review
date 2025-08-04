# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>km</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bkm%5D%20low%20quality)


```
        <source>Create a new address</source>
        <translation>បង្កើតអាសយដ្ឋានថ្មី</translation>
    
YES, the translation contains an erroneous character. The character 'អា' is not a valid Khmer character.
NO
```

```
        <source>New</source>
        <translation>ថ្មី(N)</translation>
    
YES - The translation "ថ្មី(N)" is incorrect. "New" in this context should be translated as "ថ្មី". The "(N)" appears to be an unnecessary addition or a misplaced formatting specifier.
Correct translation: ថ្មី
```

```
        <source>Close</source>
        <translation>បិទ(l)</translation>
    
YES: The 'l' in parentheses is an unnecessary and potentially confusing addition to the translation. The correct translation of "Close" is simply "បិទ".
បិទ
```

```
        <source>Choose the address to receive coins with</source>
        <translation>ជ្រើសរើសអាសយដ្ឋានដើម្បីទទួលយកកាក់ជាមួយ</translation>
    
YES: The Khmer translation is grammatically incorrect and unnatural. It uses "ជ្រើសរើស" which means "select" or "choose", but the rest of the sentence structure is awkward.

Correct translation: ជ្រើសរើសអាសយដ្ឋានដើម្បីទទួលកាក់
(Chhœ̄r-rôeuk âs'yéâ-théan pœ̄ b'nœ̄t kaak)

Explanation: The phrase "to receive coins with" is better translated as "to receive coins" in Khmer. The word "ជាមួយ" (with) is unnecessary and makes the sentence sound unnatural in this context.
```

```
        <source>Choose</source>
        <translation>ជ្រើសរើស(h)</translation>
    
YES. The Khmer translation contains an extra character 'h' at the end of the word 'ជ្រើសរើស', which is not present in the English source text. This makes the translation erroneous.

The correct translation should be:
ជ្រើសរើស
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comma បំបែកឯកសារ</translation>
    
YES. The translation is problematic as it is not a correct Khmer translation for "Comma separated file".

Correct translation:
<translation>ឯកសារបំបែកដោយសញ្ញាក្បៀស</translation>
```

```
        <source>Sending addresses - %1</source>
        <translation>កំពុងផ្ញើអាសយដ្ឋាន%1</translation>
    
YES - The translation is missing the word "address" in Khmer. The correct translation should be "កំពុងផ្ញើអាសយដ្ឋាន %1".
```

```
        <source>Receiving addresses - %1</source>
        <translation>ទទួលអាសយដ្ឋាន - %1</translation>
    
UNK_LANG
```

```
        <source>(no label)</source>
        <translation>(គ្មាន​ស្លាក​)</translation>
    
YES: The translation uses a character that is not a standard Chinese character. The correct translation should be (無標籤).
(無標籤)
```

```
        <source>This operation needs your wallet passphrase to unlock the wallet.</source>
        <translation>ប្រតិបត្តិការនេះ ត្រូវការឃ្លាសម្ងាត់កាបូបចល័តរបស់អ្នក ដើម្បីដោះសោរកាបូបចល័ត។</translation>
    
YES - The translation uses "កាបូបចល័ត" which means "mobile wallet". While a Bitcoin wallet can be on a mobile device, the original text simply says "wallet", and does not specify mobile. The correct translation should be more general.

Correct translation:ប្រតិបត្តិការនេះ ត្រូវការឃ្លាសម្ងាត់កាបូបរបស់អ្នក ដើម្បីដោះសោរកាបូប។
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>ការព្រមាន៖ ប្រសិនបើអ្នកអ៊ិនគ្រីបកាបូបចល័តរបស់អ្នក ហើយអ្នកភ្លេចបាត់ឃ្លាសម្ងាត់ នោះអ្នកនិង &lt;b&gt;បាត់បង់ BITCOINS របស់អ្នកទាំងអស់&lt;/b&gt;!</translation>
    
YES: The translation contains Chinese characters ("នោះអ្នកនិង", "របស់អ្នកទាំងអស់"). The correct translation should use Khmer characters only.

Correct Translation: ការព្រមាន៖ ប្រសិនបើអ្នកអ៊ិនគ្រីបកាបូបចល័តរបស់អ្នក ហើយអ្នកភ្លេចបាត់ឃ្លាសម្ងាត់ អ្នកនឹង &lt;b&gt;បាត់បង់ Bitcoins ទាំងអស់&lt;/b&gt;!
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>បញ្ចូលឃ្លាសម្ងាត់សំរាប់កាបូប។ &lt;br/&gt;សូមប្រើឃ្លាសម្ងាត់ពី&lt;b&gt;១០ តួ&lt;/b&gt;ឬ&lt;b&gt;ច្រើនជាងនេះ, ៨ពាក្យឬច្រើនជាងនេះ&lt;/b&gt;។.</translation>
    
YES. The translation is problematic because it doesn't accurately convey the meaning of the English sentence regarding the required length of the passphrase. The original English specifies "ten or more random characters" and "eight or more words", while the Khmer translation states "10 characters or more" and "8 words or more" without the "random" or "words" qualifiers.

Correct translation:
បញ្ចូលឃ្លាសម្ងាត់ថ្មីសម្រាប់កាបូប។ &lt;br/&gt; សូមប្រើឃ្លាសម្ងាត់ដែលមាន&lt;b&gt;តួអក្សរចៃដន្យចំនួន១០ ឬច្រើនជាងនេះ&lt;/b&gt; ឬ&lt;b&gt;ពាក្យចំនួន៨ ឬច្រើនជាងនេះ&lt;/b&gt;។
```

```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>វាយបញ្ចូលឃ្លាសម្ងាត់ចាស់ និងឃ្លាសសម្លាត់ថ្មី សម្រាប់កាបូបចល័តរបស់អ្នក។</translation>
    
YES - The word "ចល័ត" (cholat) means "mobile" or "portable". While a Bitcoin wallet can be mobile, the source text simply says "wallet" and doesn't specify it's a mobile wallet. The translation should be more direct.

The correct translation should be:
វាយបញ្ចូលឃ្លាសម្ងាត់ចាស់ និងឃ្លាសម្ងាត់ថ្មី សម្រាប់កាបូប។
```

```
        <source>Wallet to be encrypted</source>
        <translation>កាបូបចល័ត ដែលត្រូវបានអ៊ិនគ្រីប</translation>
    
YES, The translation is problematic because it implies the wallet is already encrypted, whereas the English source text states it *is to be* encrypted.

Correct translation: កាបូបចល័តដែលត្រូវអ៊ិនគ្រីប
```

```
        <source>The supplied passphrases do not match.</source>
        <translation>ឃ្លាសម្ងាត់ ដែលបានផ្គត់ផ្គង់មិនត្រូវគ្នាទេ។</translation>
    
YES, the translation is problematic. The word "ឃ្លាសម្ងាត់" is a literal translation of "secret phrase" but in the context of Bitcoin passphrases, it should be "ពាក្យសម្ងាត់" (password) or "ឃ្លា​សម្ងាត់" (passphrase).

NO, the translation is problematic. The word "ឃ្លាសម្ងាត់" is a literal translation of "secret phrase" but in the context of Bitcoin passphrases, it should be "ពាក្យសម្ងាត់" (password) or "ឃ្លា​សម្ងាត់" (passphrase).

Here's the corrected translation:
<translation>ពាក្យសម្ងាត់ដែលបានផ្គត់ផ្គង់មិនត្រូវគ្នាទេ។</translation>
```

```
        <source>Wallet unlock failed</source>
        <translation>បរាជ័យដោះសោរកាបូបចល័ត</translation>
    
YES - The translation is problematic as it incorrectly translates "Wallet unlock failed" to "បរាជ័យដោះសោរកាបូបចល័ត" which means "Mobile wallet unlock failed". The English text does not specify that the wallet is mobile.

A more accurate translation would be: "ការដោះសោរធ្វើកាបូបមិនបានសម្រេច"
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>ឃ្លាសម្ងាត់ ដែលបានបញ្ចូលសម្រាប់ការអ៊ិនគ្រីបកាបូបចល័តគឺមិនត្រឹមត្រូវទេ។</translation>
    
YES, The word "ចល័ត" means mobile, which is not present in the original text. The correct translation should be: ឃ្លាសម្ងាត់ ដែលបានបញ្ចូលសម្រាប់ការអ៊ិនគ្រីបកាបូបគឺមិនត្រឹមត្រូវទេ។
```

```
        <source>Runaway exception</source>
        <translation>ករណីលើកលែងដែលរត់គេចខ្លួន</translation>
    
YES
The translation is overly literal and doesn't accurately convey the meaning of "Runaway exception" in a Bitcoin context. In Bitcoin, this likely refers to an exception that is unrecoverable or cannot be handled by the system.

Correct translation: ការលើកលែងដែលមិនអាចគ្រប់គ្រងបាន
```

```
        <source>Internal error</source>
        <translation>ខាងក្នុងបញ្ហា</translation>
    
YES, The translation is problematic. The target language is Khmer (km), but the translation provided is in Thai.

UNK_LANG
```

```
        <source>Show information about %1</source>
        <translation>បង្ហាញព័ត៍មានអំពី %1</translation>
    
UNK_LANG
```

```
        <source>Create a new wallet</source>
        <translation>បង្កើតកាបូបចល័តថ្មីមួយ</translation>
    
YES, The translation is problematic as it uses Chinese characters rather than Khmer. The correct translation should be "បង្កើតកាបូបចល័តថ្មីមួយ".
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>ផ្លាស់ប្ដូរឃ្លាសម្ងាត់ ដែលបានប្រើសម្រាប់ការអ៊ិនគ្រីបកាបូបចល័ត</translation>
    
YES: The translation uses "កាបូបចល័ត" which means "mobile wallet", but the source text is more general and refers to "wallet encryption" without specifying it as mobile.

Correct translation: ផ្លាស់ប្ដូរឃ្លាសម្ងាត់ដែលបានប្រើសម្រាប់ការអ៊ិនគ្រីបកាបូប
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>បំលែងលេខសំម្ងាត់សម្រាប់កាបូបអេឡិចត្រូនិច របស់អ្នកឲ្យទៅជាភាសាកុំព្យូទ័រ </translation>
    
YES, The translation uses the wrong verb "បំលែង" (to convert) instead of "អ៊ិនគ្រីប" (to encrypt). The phrase "ឲ្យទៅជាភាសាកុំព្យូទ័រ" (to computer language) is also unnecessary and does not accurately reflect the meaning of "encrypt".

Correct translation: អ៊ិនគ្រីប​លេខ​សម្ងាត់​ដែល​ជា​កម្មសិទ្ធិ​របស់​កាបូប​របស់​អ្នក
Or: អ៊ិនគ្រីប​លេខ​សម្ងាត់​របស់​កាបូប​របស់​អ្នក
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>ចុះហត្ថលេខាលើសារ អាសយដ្ឋានប៊ីតខញរបស់អ្នក ដើម្បីបញ្ចាក់ថាអ្នកជាម្ចាស់</translation>
    
YES: The translation is missing the word "with" and the possessive "your".
Correct translation: ចុះហត្ថលេខាលើសារដោយប្រើអាសយដ្ឋាន Bitcoin របស់អ្នក ដើម្បីបញ្ជាក់ថាអ្នកជាម្ចាស់។
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>ធ្វើការបញ្ចាក់សារ ដើម្បីធានាថាសារទាំំងនោះបានចុះហត្ថលេខា ជាមួយអាសយដ្ខានប៊ីតខញ</translation>
    
YES - The translation is problematic due to incorrect Khmer characters. The word "បញ្ចាក់" should be "បញ្ជាក់" and "ធានាថាសារទាំំងនោះ" should be "ធានាថាសារទាំងនោះ". Additionally, "អាសយដ្ខាន" should be "អាសយដ្ឋាន".

Correct translation: ធ្វើការបញ្ជាក់សារ ដើម្បីធានាថាសារទាំងនោះបានចុះហត្ថលេខា ជាមួយអាសយដ្ឋានប៊ីតខាញ
```

```
        <source>Help</source>
        <translation>ជំនួយ</translation>
    
YES, the translation of "Help" to "ជំនួយ" is incorrect. "ជំនួយ" means "assistance" or "aid", but in the context of Bitcoin or software interfaces, "Help" is usually translated as "ជំនួយ" or "ប្រឹក្សា". A more appropriate translation for "Help" in this context would be "ជំនួយ".

Corrected translation:
<translation>ជំនួយ</translation>
```

```
        <source>Indexing blocks on disk…</source>
        <translation>កំពុងធ្វើលិបិក្រមប្លុកនៅលើថាស...</translation>
    
UNK_LANG
```

```
        <source>Processing blocks on disk…</source>
        <translation>កំពុងដំណើរការប្លុកនៅលើថាស...</translation>
    
YES, The translation appears to be in Thai script, not Khmer (km). The provided translation also contains English words.
UNK_LANG
```

```
        <source>Connecting to peers…</source>
        <translation>កំពុងភ្ជាប់ទៅមិត្តភក្ដិ...</translation>
    
YES, the translation is problematic. The Khmer translation uses Thai script ("កំពុងភ្ជាប់ទៅមិត្តភក្ដិ..."). The correct Khmer script is "កំពុងតភ្ជាប់ទៅមិត្តភក្តិ..." or "កំពុងភ្ជាប់ទៅមិត្តភក្តិ..." (depending on preferred spelling of "connected"). However, the current translation contains Thai characters.

NO
```

```
        <source>Show the list of used sending addresses and labels</source>
        <translation>បង្ហាញបញ្ចីរអាសយដ្ឋាន និង ស្លាកសញ្ញាបញ្ចូនបានប្រើប្រាស់</translation>
    
YES, The translation is problematic because it contains non-Khmer characters. It should be: បង្ហាញបញ្ជីអាសយដ្ឋាន និងស្លាកសញ្ញាដែលបានប្រើប្រាស់។
```

```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>បង្ហាញបញ្ចីរអាសយដ្ឋាន និង ស្លាកសញ្ញាទទួល បានប្រើប្រាស់</translation>
    
YES, The translation of "Show the list of used receiving addresses and labels" to Khmer is "បង្ហាញបញ្ចីរអាសយដ្ឋាន និង ស្លាកសញ្ញាទទួល បានប្រើប្រាស់". However, the word "បញ្ចីរ" should be "បញ្ជី". Also, the sentence structure is a bit unnatural and could be improved.

Here's a more natural and accurate translation:
Showing the list of used receiving addresses and labels.

Here's the corrected Khmer translation:
បង្ហាញបញ្ជីអាសយដ្ឋាន និងស្លាកសញ្ញាដែលបានប្រើប្រាស់

Here's a breakdown of the corrections:
* "បញ្ចីរ" corrected to "បញ្ជី" (list)
* Rephrased the sentence for better flow in Khmer.

Corrected translation:
បង្ហាញបញ្ជីអាសយដ្ឋាន និងស្លាកសញ្ញាដែលបានប្រើប្រាស់
```

```
        <source>Transactions after this will not yet be visible.</source>
        <translation>ប្រត្តិបត្តិការបន្ទាប់ពីនេះ នឹងមិនអាចទាន់មើលឃើញនៅឡើយទេ។</translation>
    
YES: The translation uses Chinese characters (នឹង) which are not part of the Khmer language.
Correct translation: ប្រតិបត្តិការបន្ទាប់ពីនេះ នឹងមិនអាចមើលឃើញនៅឡើយទេ។
```

```
        <source>Up to date</source>
        <translation>ទាន់ពេល និង ទាន់សម័យ</translation>
    
YES, The translation is problematic. The English source "Up to date" means current or modern. The Khmer translation "ទាន់ពេល និង ទាន់សម័យ" translates to "on time and up to date". The word "on time" is not present in the original English meaning.

NO
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>បង្ហាញប្រត្តិបត្តិការប៊ីតខញដែលបានចុះហត្ថលេខាដោយផ្នែក</translation>
    
YES - The translation is inaccurate. It translates "Load Partially Signed Bitcoin Transaction" to "Display partially signed Bitcoin transaction". The verb "Load" is not equivalent to "Display". Also, the word "transaction" is translated as "operation", which is not the most accurate term in this context.

Here's the corrected translation:
Load Partially Signed Bitcoin Transaction -> បើក​ប្រតិបត្តិការ Bitcoin ដែល​បាន​ចុះហត្ថលេខា​ដោយ​ផ្នែក
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>បង្ហាញប្រត្តិបត្តិការប៊ីតខញដែលបានចុះហត្ថលេខាដោយផ្នែកពីក្ដារតម្រៀប</translation>
    
YES: The translation is problematic because it uses "បង្ហាញ" (display) instead of a word that means "load" or "import". The use of "ប្រត្តិបត្តិការ" for transaction is also not standard.

Correct translation: បញ្ចូលប្រតិបត្តិការ Bitcoin ដែលបានចុះហត្ថលេខាដោយផ្នែកពីក្ដារតម្រៀប
```

```
        <source>Open a bitcoin: URI</source>
        <translation>បើកប៊ីតខញមួយៈ URl</translation>
    
YES, The word "bitcoin" in the source text is written in English, but in the translation it is written as "ប៊ីតខញ" which is a transliteration of the word. The source text has a colon after "bitcoin" and it is not present in the translation.

Open a bitcoin: URI
បើក bitcoin: URI
```

```
        <source>Migrate Wallet</source>
        <translation>កាបូបMigrate</translation>
    
YES, the translation is problematic. The word "Migrate" has been appended to "Wallet" without translation, and the order is unnatural. The correct translation for "Migrate Wallet" should be "ផ្ទេរ</source><translation>កាបូប</translation>".

NO
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>បង្ហាញសារជំនួយ%1ដើម្បីទទួលបានបញ្ជីជាមួយនឹងជម្រើសបន្ទាត់ពាក្យបញ្ជា Bitcoin ដែលអាចធ្វើទៅបាន</translation>
    
YES: The translation uses Khmer script ("បង្ហាញសារជំនួយ%1 để nhận danh sách các tùy chọn dòng lệnh Bitcoin có thể có"), which is not the target language 'km'. The target language should be Khmer.

NO
```

```
        <source>Show</source>
        <translation>របៀប(S)</translation>
    
YES, the translation is problematic. The Khmer word "របៀប" means "manner" or "way," which is not an accurate translation for "Show" in the context of Bitcoin. The "(S)" at the end also seems out of place and doesn't correspond to any expected formatting specifier or common practice in Khmer UI translations.

A more appropriate translation for "Show" in this context would be "បង្ហាញ" (beng-hâi), which means "display" or "show."

NO
```

```
        <source>HD key generation is &lt;b&gt;enabled&lt;/b&gt;</source>
        <translation>លេខសម្ងាត់ HD គឺ&lt;b&gt;ត្រូវបាន​បើក&lt;/b&gt;</translation>
    
YES: The translation is grammatically incorrect and unnatural in Khmer. "លេខសម្ងាត់ HD គឺ" translates to "HD secret is" which is not the intended meaning. The phrase "ត្រូវបាន​បើក" means "is opened" but the context suggests "is enabled".

Correct translation: ការបង្កើតកូនសោ HD គឺ&lt;b&gt;បើក​ហើយ&lt;/b&gt;
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>លេខសម្ងាត់ HD គឺ&lt;b&gt;ត្រូវបានបិទ&lt;/b&gt;</translation>
    
YES - The translation is grammatically incorrect and unnatural in Khmer. The word "លេខសម្ងាត់" (lek somboat) translates to "password" or "secret number," which is not the correct term for "key generation." The phrase "ត្រូវបានបិទ" (toban bapit) means "is closed" or "is shut," which is also not the best translation for "disabled" in this context.

Correct translation: ការបង្កើតកូនសោ HD ត្រូវបានបិទ
Reasoning:
- "ការបង្កើត" (kar bot-baet) means "generation" or "creation."
- "កូនសោ" (kon sae) means "key."
- "HD" remains the same as it's a technical term.
- "ត្រូវបានបិទ" (toban bapit) is a suitable translation for "is disabled" in a technical context.
```

```
        <source>Private key &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>លេខសម្ងាត់ &lt;b&gt;ត្រូវបានបិទ&lt;/b&gt;</translation>
    
YES. The translation is problematic. The Khmer word for "private key" is "លេខ​សម្ងាត់​ផ្ទាល់​ខ្លួន" (lek somnat pteah dou) or "កូនសោ​ឯកជន" (koun sao ekajon). The provided translation uses "លេខសម្ងាត់" (lek somnat) which means "password" or "secret number".

The correct translation should be:
លេខ​សម្ងាត់​ផ្ទាល់​ខ្លួន &lt;b&gt;ត្រូវបានបិទ&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>កាបូបអេឡិចត្រូនិចគឺ&lt;b&gt;ត្រូវបានបំលែងជាកូដ&lt;/b&gt;និងបច្ចុប្បន្ន&lt;b&gt;ត្រូវបានចាក់សោរ&lt;/b&gt;</translation>
    
YES: The translation incorrectly translates "unlocked" as "locked".
Correct translation: កាបូបអេឡិចត្រូនិចគឺ&lt;b&gt;ត្រូវបានបំលែងជាកូដ&lt;/b&gt;និងបច្ចុប្បន្ន&lt;b&gt;ត្រូវបានដោះសោរ&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>កាបូបអេឡិចត្រនិច&lt;b&gt;ត្រូវបានបំលែងជាកូដ&lt;/b&gt;និងបច្ចុប្បន្ន&lt;b&gt;ត្រូវបានចាក់សោរ&lt;/b&gt;</translation>
    
YES: The Khmer translation incorrectly translates "encrypted" and "locked". The word "encrypted" should be translated as "បាន​អ៊ិនគ្រីប" and "locked" should be translated as "ចាក់សោ".

កាបូបអេឡិចត្រនិច&lt;b&gt;បាន​អ៊ិនគ្រីប&lt;/b&gt;និងបច្ចុប្បន្ន&lt;b&gt;បានចាក់សោរ&lt;/b&gt;
```

```
        <source>Unit to show amounts in. Click to select another unit.</source>
        <translation>ឯកតា​ដើម្បី​បង្ហាញ​ចំនួន​ចូល។ ចុច​ដើម្បី​ជ្រើសរើស​ឯកតា​ផ្សេងទៀត។</translation>
    
YES: The Khmer translation is incorrect. "ចូល" (choul) means "enter" or "come in," which is not the intended meaning of "amounts" in this context. The word for amounts should be "ចំនួនទឹកប្រាក់" (cham-naun-tiek-brak) or "ទឹកប្រាក់" (tiek-brak).

Corrected translation: ឯកតា​ដើម្បី​បង្ហាញ​ចំនួនទឹកប្រាក់។ ចុច​ដើម្បី​ជ្រើសរើស​ឯកតា​ផ្សេងទៀត។
```

```
        <source>Can vary +/- %1 satoshi(s) per input.</source>
        <translation>អាច +/- %1 satoshi(s)ច្រើនក្នុងការបញ្ជូលមួយ។</translation>
    
YES, The Khmer translation uses the Thai word "បញ្ជូល" which means "insert" or "enter" rather than the appropriate Khmer word for "input." Additionally, the sentence structure is slightly awkward.
A more accurate and natural translation would be: អាចប្រែប្រួល +/- %1 satoshi(s) ក្នុងមួយការបញ្ចូល។
```

```
        <source>(no label)</source>
        <translation>(គ្មាន​ស្លាក​)</translation>
    
YES: The translation uses a character that is not a standard Chinese character. The correct translation should be (無標籤).
(無標籤)
```

```
        <source>(change)</source>
        <translation>(ផ្លាស់ប្តូរ)</translation>
    
YES: The translation of "(change)" to "(ផ្លាស់ប្តូរ)" is incorrect in the context of Bitcoin. "ផ្លាស់ប្តូរ" means "change" in the general sense of alteration or exchange. In Bitcoin, "change" refers to the unspent output of a transaction that is returned to the sender. The correct Khmer translation for this would be related to "money returned" or "change received".

Correct translation: (សាច់ប្រាក់ដែលនៅសល់)
```

```
        <source>Migrate Wallet</source>
        <translation>កាបូបMigrate</translation>
    
YES, the translation is problematic. The word "Migrate" has been appended to "Wallet" without translation, and the order is unnatural. The correct translation for "Migrate Wallet" should be "ផ្ទេរ</source><translation>កាបូប</translation>".

NO
```

```
        <source>Open wallet failed</source>
        <translation>បើកកាបូបអេឡិចត្រូនិច មិនជៅគជ័យ</translation>
    
YES - The translation uses an incorrect word for "failed". The correct word should be "បរាជ័យ" (borachey).

Correct translation: បើកកាបូបអេឡិចត្រូនិចបរាជ័យ
```

```
        <source>Opening Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the open wallet progress window which indicates to the user which wallet is currently being opened.</extracomment>
        <translation>កាបូបការបើកកាបូប&lt;b&gt;%1&lt;/b&gt;...</translation>
    
YES - The translation is redundant and contains a grammatical error. "កាបូបការបើកកាបូប" translates to "Wallet opening wallet". The correct translation should be "បើកកាបូប %1..." which means "Opening wallet %1...".
បើកកាបូប &lt;b&gt;%1&lt;/b&gt;...
```

```
        <source>Are you sure you wish to close all wallets?</source>
        <translation>តើអ្នកច្បាស់ថាអ្នកចង់បិទកាបូបអេឡិចត្រូនិចទាំងអស់?</translation>
    
YES: The translation contains an erroneous character ("), which is not part of the Khmer script. The word "ទាំងអស់" is also in Chinese.
តើអ្នកច្បាស់ថាអ្នកចង់បិទកាបូបអេឡិចត្រូនិចទាំងអស់ទេ?
```

```
        <source>Encrypt the wallet. The wallet will be encrypted with a passphrase of your choice.</source>
        <translation>បំលែងកាបូបអេឡិចត្រូនិចជាកូដ។ កាបំលែងនេះ រួមជាមួយនឹងឃ្លាសម្ងាត់ដែលអ្នកអាចជ្រើសរើសបាន។</translation>
    
YES, the translation is problematic because it uses an incorrect verb ("បំលែង" - to transform/convert) which does not accurately convey the meaning of "encrypt". The phrase "The wallet will be encrypted with a passphrase of your choice" should be translated to accurately reflect encryption. Additionally, the translation seems to have misinterpreted "passphrase" and "of your choice" in the latter part of the sentence.

Correct translation: បញ្ចូល​លេខ​សម្ងាត់​ទៅ​កាបូប​អេឡិចត្រូនិច​។ កាបូប​អេឡិចត្រូនិច​នឹង​ត្រូវ​បាន​បញ្ចូល​លេខ​សម្ងាត់​តាម​ឃ្លា​សម្ងាត់​ដែល​អ្នក​ជ្រើសរើស​។
```

```
        <source>Encrypt Wallet</source>
        <translation>បំលែងកាបូបអេឡិចត្រនិចទៅជាកូដ</translation>
    
YES, The translation is problematic. The Khmer translation is a literal and incorrect translation of "Encrypt Wallet". "បំលែងកាបូបអេឡិចត្រនិចទៅជាកូដ" means "Convert electronic wallet to code", which does not convey the intended meaning of encrypting a wallet.

The correct translation should be "លាក់កាបូបអេឡិចត្រូនិក" or "អ៊ិនគ្រីបកាបូបអេឡិចត្រូនិក".

Correct translation: លាក់កាបូបអេឡិចត្រូនិក
```

```
        <source>The label associated with this address list entry</source>
        <translation>ស្លាកសញ្ញានេះជាប់ទាក់ទងទៅនឹងការបញ្ចូលបញ្ចីរអាសយដ្ឋាន</translation>
    
YES: The translation is grammatically incorrect and uses an awkward phrasing. The word "ស្លាកសញ្ញានេះ" which translates to "this label" is redundant as the sentence already refers to "this address list entry". The phrase "ជាប់ទាក់ទងទៅនឹង" which translates to "is associated with" is also too literal and not natural in Khmer.

A more natural and accurate translation would be: "ស្លាកដែលទាក់ទងនឹងបញ្ជីអាសយដ្ឋាននេះ" which translates to "The label related to this address list".
```

```
        <source>Address</source>
        <translation>អាសយដ្ឋានបញ្ចូនថ្មី</translation>
    
YES, The translation is problematic because it adds extra information ("បញ្ចូនថ្មី" which means "new sending") not present in the source text. The correct translation for "Address" in this context should be a direct equivalent.

NO
Address
```

```
        <source>New key generation failed.</source>
        <translation>បង្កើតលេខសំម្ងាត់ថ្មីមិនជោគជ័យ។</translation>
    
YES. The translation incorrectly uses "លេខសំម្ងាត់" which means "password" or "secret code" instead of "key". The context of Bitcoin suggests that a "key" refers to a cryptographic key used for wallet management or transaction signing.

NO
```

```
        <source>Path already exists, and is not a directory.</source>
        <translation>ផ្លូវទៅកាន់ទិន្នន័យមានរួចរាល់​ និង​ មិនមែនជាទីតាំង។</translation>
    
YES - The translation is inaccurate and confusing. In the context of Bitcoin and file paths, "path" refers to a location or route within a file system, not a destination. "ផ្លូវទៅកាន់ទិន្នន័យ" translates to "path to data", which is not the intended meaning. The second part "និង​ មិនមែនជាទីតាំង" translates to "and is not a location", which is also incorrect. The original English phrase implies that a file path already exists and it is not a directory. A more accurate translation would be:

"ផ្លូវ​នេះ​មាន​រួច​ហើយ​ និង​ មិនមែនជា​ថតឯកសារ​។"
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>នៅពេលអ្នកចុចយល់ព្រម %1វានឹងចាប់ផ្តើមទាញយក និងដំណើរការខ្សែសង្វាក់ប្លុក%4ពេញលេញ (%2GB) ដោយចាប់ផ្តើមជាមួយនឹងប្រតិបត្តិការដំបូងបំផុតនៅ%3ពេល%4ចាប់ផ្តើមដំបូង។</translation>
    
YES, The translation is problematic because the word "blockchain" in English is translated to "%4" which is a placeholder. This should be translated to "ខ្សែសង្វាក់ប្លុក" to reflect the context of Bitcoin.

NO, If the translation is unproblematic, output: "NO".
YES, The translation is problematic, followed by a brief explanation and the correct translation.
UNK_LANG, If you are unfamiliar with the language specified by 'km', output: "UNK_LANG".

YES, The translation is problematic because "%4" is used as a placeholder for the word "blockchain", which should be translated to "ខ្សែសង្វាក់ប្លុក" in Khmer.
Correct translation: នៅពេលអ្នកចុចយល់ព្រម %1 វានឹងចាប់ផ្តើមទាញយក និងដំណើរការខ្សែសង្វាក់ប្លុក %4 ពេញលេញ (%2 GB) ដោយចាប់ផ្តើមជាមួយនឹងប្រតិបត្តិការដំបូងបំផុតនៅ %3 ពេល %4 បើកដំណើរការដំបូង។
```

```
        <source>version</source>
        <translation>ជំនាន់</translation>
    
YES
The provided translation is problematic as it uses Chinese characters instead of Khmer (km) characters. The correct Khmer translation for "version" is "កំណែ".

UNK_LANG
```

```
        <source>Do not shut down the computer until this window disappears.</source>
        <translation>សូមកុំទាន់បិទកុំព្យូទ័រនេះ រហូលទាល់តែវិនដូរនេះលុបបាត់។</translation>
    
YES, The translation is problematic. The word "disappears" is translated as "លុបបាត់" (delete/remove) which is incorrect. It should be translated as "បាត់" (disappear/vanish).

NO
```

```
        <source>Recent transactions may not yet be visible, and therefore your wallet's balance might be incorrect. This information will be correct once your wallet has finished synchronizing with the bitcoin network, as detailed below.</source>
        <translation>ប្រត្តិបត្តិការថ្មីៗនេះប្រហែលជាមិនអាចមើលឃើញ ហេតុដូច្នេះសមតុល្យនៅក្នងកាបូបអេឡិចត្រូនិចរបស់អ្នកប្រហែលជាមិនត្រឹមត្រូវ។ ព័ត៌មានត្រឹមត្រូវនៅពេលដែលកាបូបអេឡិចត្រូនិចរបស់អ្នកបានធ្វើសមកាលកម្មជាមួយបណ្តាញប៊ឺតខញ  សូមពិនិត្យព័ត៌មានលំម្អិតខាងក្រោម។</translation>
    
YES - The translation contains several grammatical and vocabulary errors, making it difficult to understand and potentially misleading. It also uses a literal translation for "bitcoin" which is not the standard Khmer transliteration.

Here's a breakdown of the issues and the corrected translation:

**Issues:**

*   **"ប្រត្តិបត្តិការថ្មីៗនេះប្រហែលជាមិនអាចមើលឃើញ"**: "ប្រត្តិបត្តិការ" is a plural noun, but the context suggests a singular or general concept of transactions. "មិនអាចមើលឃើញ" is a bit literal for "not yet visible."
*   **"ហេតុដូច្នេះសមតុល្យនៅក្នងកាបូបអេឡិចត្រូនិចរបស់អ្នកប្រហែលជាមិនត្រឹមត្រូវ"**:
    *   "ហេតុដូច្នេះ" is an unusual conjunction in this context.
    *   "ក្នង" should be "ក្នុង" (inside).
    *   "កាបូបអេឡិចត្រូនិច" is a correct translation for e-wallet, but the context of Bitcoin might allow for a slightly more specific term if available, though this is acceptable.
    *   "ប្រហែលជាមិនត្រឹមត្រូវ" is a bit clunky.
*   **"ព័ត៌មានត្រឹមត្រូវនៅពេលដែលកាបូបអេឡិចត្រូនិចរបស់អ្នកបានធ្វើសមកាលកម្មជាមួយបណ្តាញប៊ឺតខញ"**:
    *   "ព័ត៌មានត្រឹមត្រូវ" (correct information) is misplaced. It should follow the action that makes it correct.
    *   "បានធ្វើសមកាលកម្ម" is a literal translation of "synchronized" which is understandable but could be more natural.
    *   "បណ្តាញប៊ឺតខញ" is an incorrect transliteration of "bitcoin network." The common transliteration is "ប៊ីតខយន៍" (Bit Coin) or "ប៊ីតកាក់" (Bit Coin/Coin).

**Correct Translation:**

<translation>ប្រតិបត្តិការថ្មីៗនេះប្រហែលជាមិនទាន់បង្ហាញទេ ហើយសមតុល្យកាបូបរបស់អ្នកអាចនឹងមិនត្រឹមត្រូវ។ ព័ត៌មាននឹងត្រឹមត្រូវនៅពេលដែលកាបូបរបស់អ្នកធ្វើសមកាលកម្មជាមួយបណ្តាញ Bitcoin រួចរាល់ ដែលមានការពន្យល់លម្អិតខាងក្រោម។</translation>

**Explanation of Corrections:**

*   **"ប្រតិបត្តិការថ្មីៗនេះប្រហែលជាមិនទាន់បង្ហាញទេ"**: "ប្រតិបត្តិការ" is used in a more general sense here. "មិនទាន់បង្ហាញទេ" is a more natural way to say "not yet visible."
*   **"ហើយសមតុល្យកាបូបរបស់អ្នកអាចនឹងមិនត្រឹមត្រូវ"**: "ហើយ" is a common conjunction. "សមតុល្យកាបូបរបស់អ្នក" is more concise. "អាចនឹងមិនត្រឹមត្រូវ" is a more natural phrasing for "might be incorrect."
*   **"ព័ត៌មាននឹងត្រឹមត្រូវនៅពេលដែលកាបូបរបស់អ្នកធ្វើសមកាលកម្មជាមួយបណ្តាញ Bitcoin រួចរាល់"**:
    *   "ព័ត៌មាននឹងត្រឹមត្រូវ" is placed correctly.
    *   "ធ្វើសមកាលកម្ម" is still used, but "រួចរាល់" (completed) clarifies the state.
    *   "បណ្តាញ Bitcoin" uses the standard Khmer transliteration for Bitcoin.
*   **"ដែលមានការពន្យល់លម្អិតខាងក្រោម"**: "ដែលមានការពន្យល់លម្អិតខាងក្រោម" is a more fluent way to say "as detailed below."
```

```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>ព្យាយាមក្នុងការចំណាយប៊ីតខញដែលទទួលរងឥទ្ឋិពលពីប្រត្តិបត្តិការមិនទាន់ធ្វើការបង្ហាញ នឹងមិនត្រូវទទួលស្គាល់ពីបណ្តាញ។</translation>
    
YES. The translation has a minor issue with word choice that could be slightly improved for clarity within the Bitcoin context.

The word "ចំណាយ" (chom-naai) translates to "spend" or "cost". While technically correct, in the context of cryptocurrency, "ចំណាយ" can sometimes imply a more general expense rather than the specific action of sending cryptocurrency. A slightly more precise term for "spending" in this context would be "ផ្ញើ" (ph’nyoe), which means "to send".

Corrected translation:
ព្យាយាមក្នុងការផ្ញើប៊ីតខញដែលទទួលរងឥទ្ឋិពលពីប្រត្តិបត្តិការមិនទាន់ធ្វើការបង្ហាញ នឹងមិនត្រូវទទួលស្គាល់ពីបណ្តាញ។
```

```
        <source>Last block time</source>
        <translation>ពេវេលាប្លុកជុងក្រោយ</translation>
    
UNK_LANG
```

```
        <source>Progress</source>
        <translation>កំពុងដំណើរការ</translation>
    
YES, The provided Khmer translation for "Progress" is incorrect. The word "កំពុងដំណើរការ" translates to "in progress" or "processing" which is not a direct translation for "Progress". A more accurate translation for "Progress" in the context of Bitcoin would be "វឌ្ឍនភាព" or "លទ្ធផល".

The correct translation is:
<source>Progress</source>
<translation>វឌ្ឍនភាព</translation>
```

```
        <source>Estimated time left until synced</source>
        <translation>ពេលវេលាដែលរំពឹងទុកនៅសល់រហូតដល់បានធ្វើសមកាលកម្ម</translation>
    
YES. The translation contains a Chinese character "時" (shí), which means "time" in Chinese. This is not part of the Khmer language. The correct Khmer translation for "Estimated time left until synced" is "រយៈពេលដែលរំពឹងទុកនៅសល់រហូតដល់បានធ្វើសមកាលកម្ម".

NO
```

```
        <source>Unknown. Syncing Headers (%1, %2%)…</source>
        <translation>មិនស្គាល់។ Syncing Headers (%1, %2%)…</translation>
    
YES, The translation contains English words "Syncing Headers" which should be translated into Khmer.
NO, UNK_LANG
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>មិនស្គាល់។ Pre-syncing Headers (%1, %2%)…</translation>
    
YES. The translation of "Unknown." is incorrect. It should be translated as "មិនស្គាល់" instead of "Unknown.".

NO
```

```
        <source>Open bitcoin URI</source>
        <translation>បើកប៊ីតខញ​URl</translation>
    
YES - The translation is problematic because the Khmer spelling of "Bitcoin" is incorrect. The correct Khmer spelling should be "ប៊ីតខាញ" or "ប៊ីតកាញ". The URL format specifier is also missing the correct representation for the format specifier.

Here's the corrected translation:

<source>Open bitcoin URI</source>
<translation>បើក​ URI bitcoin</translation>
```

```
        <source>URI:</source>
        <translation>URl:</translation>
    
YES: The translation of "URI" to "URl" is a misspelling. The correct translation should be "URI".
URI:
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>ថតចម្លងអាសយដ្ឋាណពីក្ដារតម្រៀប</translation>
    
YES, The translation is incorrect. The Khmer word "ថតចម្លង" (thot chamlong) means "to copy", while the English source text "Paste" means "to paste". The correct Khmer word for "paste" is "បិទភ្ជាប់" (beit phachom).

NO
```

```
        <source>Start %1 on system login</source>
        <translation>ចាប់ផ្តើម %1 ទៅលើការចូលប្រព័ន្ធ(S)</translation>
    
YES
The translation is problematic as "ទៅលើការចូលប្រព័ន្ធ(S)" translates to "to the system login(S)" which is not a natural way to express "on system login" in Khmer. Additionally, the '(S)' appears to be an artefact that should not be there.

A more natural and accurate translation would be:
ចាប់ផ្តើម %1 ពេលចូលប្រព័ន្ធ
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>ការបើកដំណើរការកាត់ចេញយ៉ាងសំខាន់កាត់បន្ថយទំហំថាសដែលត្រូវការដើម្បីរក្សាទុកប្រតិបត្តិការ។ ប្លុកទាំងអស់នៅតែផ្ទៀងផ្ទាត់ពេញលេញ។ ការត្រឡប់ការកំណត់នេះទាមទារការទាញយក blockchain ទាំងស្រុងឡើងវិញ។</translation>
    
YES: The translation incorrectly translates "blocks" to "ប្លុកទាំងអស់" (all blocks) instead of "blocks" which would be "ប្លុក". It also incorrectly translates "Reverting this setting" to "ការត្រឡប់ការកំណត់នេះ" which is a direct translation, but in this context "ការផ្លាស់ប្តូរការកំណត់នេះ" would be more appropriate.

Correct translation: ការបើកដំណើរការកាត់ចេញយ៉ាងសំខាន់កាត់បន្ថយទំហំថាសដែលត្រូវការដើម្បីរក្សាទុកប្រតិបត្តិការ។ ប្លុកទាំងអស់នៅតែផ្ទៀងផ្ទាត់ពេញលេញ។ ការផ្លាស់ប្តូរការកំណត់នេះទាមទារការទាញយក blockchain ទាំងស្រុងឡើងវិញ។
```

```
        <source>Number of script verification threads</source>
        <translation>ចំនួនscript  threadsផ្ទៀងផ្ទាត់</translation>
    
YES - The translation contains an English word "script" and a word "threads" that looks like it might be English. The word "ផ្ទៀងផ្ទាត់" is misspelled.
Correct translation: ចំនួនខ្សែស្រឡាយផ្ទៀងផ្ទាត់ស្គ្រីប
```

```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>កំណត់ចំនួនខ្សែស្រឡាយផ្ទៀងផ្ទាត់script ។ តម្លៃអវិជ្ជមានត្រូវគ្នាទៅនឹងចំនួនស្នូលដែលអ្នកចង់ចាកចេញពីប្រព័ន្ធដោយឥតគិតថ្លៃ។</translation>
    
YES - The translation uses Thai characters and Khmer words, making it a mix of languages. The correct translation should be in Khmer.
កំណត់ចំនួនខ្សែស្រឡាយផ្ទៀងផ្ទាត់script ។ តម្លៃអវិជ្ជមានត្រូវគ្នាទៅនឹងចំនួនស្នូលដែលអ្នកចង់ចាកចេញពីប្រព័ន្ធដោយឥតគិតថ្លៃ។
```

```
        <source>This allows you or a third party tool to communicate with the node through command-line and JSON-RPC commands.</source>
        <extracomment>Tooltip text for Options window setting that enables the RPC server.</extracomment>
        <translation>នេះអនុញ្ញាតឱ្យអ្នក ឬឧបករណ៍ភាគីទីបីទាក់ទងជាមួយណូដតាមរយៈបន្ទាត់ពាក្យបញ្ជា និងពាក្យបញ្ជា JSON-RPC ។</translation>
    
YES
The translation uses Lao characters instead of Khmer.
Correct translation: នេះអនុញ្ញាតឱ្យអ្នក ឬឧបករណ៍ភាគីទីបីទាក់ទងជាមួយណូដតាមរយៈបន្ទាត់ពាក្យបញ្ជា និងពាក្យបញ្ជា JSON-RPC ។
```

```
        <source>Enable PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>បើកដំណើរការការត្រួតពិនិត្យ PSBT</translation>
    
YES - The translation is in Khmer, but the content is in Vietnamese. The correct translation should be "បើកដំណើរការការត្រួតពិនិត្យ PSBT".
```

```
        <source>Connect to the Bitcoin network through a SOCKS5 proxy.</source>
        <translation>ភ្ជាប់ទៅកាន់បណ្តាញប៊ឺតខញតាមរយៈ​ SOCKS5 proxy។</translation>
    
YES - The translation uses Khmer script for "bitcoin" and "network", but uses Latin script for "connect", "through", "a", "SOCKS5", and "proxy". The translation should be entirely in Khmer script.

Connect to the Bitcoin network through a SOCKS5 proxy.
ភ្ជាប់ទៅកាន់បណ្តាញ Bitcoin តាមរយៈ SOCKS5 proxy។
```

```
        <source>Port:</source>
        <translation>រុនដោត</translation>
    
YES, the translation is problematic because the Khmer word "រុនដោត" does not mean "Port" in the context of Bitcoin or networking. The correct translation for "Port" in this context is "ច្រក".

YES, រុនដោត
Correct translation: ច្រក
```

```
        <source>Third-party URLs (e.g. a block explorer) that appear in the transactions tab as context menu items. %s in the URL is replaced by transaction hash. Multiple URLs are separated by vertical bar |.</source>
        <translation>URL ភាគីទីបី (ឧ. ប្លុករុករក) ដែលបង្ហាញក្នុងផ្ទាំងប្រតិបត្តិការជាធាតុម៉ឺនុយបរិបទ។ %sនៅក្នុង URL ត្រូវបានជំនួសដោយhashប្រតិបត្តិការ។ URLs ច្រើនត្រូវបានបំបែកដោយរបារបញ្ឈរ |។</translation>
    
YES: The translation uses a mix of Khmer and Thai characters and words, which makes it difficult to understand and incorrect.

URL ភាគីទីបី (ឧ. ប្លុករុករក) ដែលបង្ហាញក្នុងផ្ទាំងប្រតិបត្តិការជាធាតុម៉ឺនុយបរិបទ។ %s នៅក្នុង URL ត្រូវបានជំនួសដោយ hash ប្រតិបត្តិការ។ URLs ច្រើនត្រូវបានបំបែកដោយរបារបញ្ឈរ |។
```

```
        <source>Client will be shut down. Do you want to proceed?</source>
        <extracomment>Text asking the user to confirm if they would like to proceed with a client shutdown.</extracomment>
        <translation>ផ្ទាំងអតិថិជននិងត្រូវបិទ។ តើអ្នកចង់បន្តទៀតឫទេ?</translation>
    
YES: The translation is mostly accurate but includes an extra "and" character (និង) which makes the sentence grammatically incorrect. The phrase "ផ្ទាំងអតិថិជន" is also a bit awkward; "អតិថិជន" alone or "កម្មវិធី" (program) would be more appropriate.
Correct translation: អតិថិជននឹងត្រូវបិទ។ តើអ្នកចង់បន្តទៀតទេ?
```

```
        <source>Configuration options</source>
        <extracomment>Window title text of pop-up box that allows opening up of configuration file.</extracomment>
        <translation>ជម្រើសក្នុងការរៀបចំរចនាសម្ព័ន្ធ</translation>
    
YES: The translation is grammatically incorrect. The correct translation is "ជម្រើស​កំណត់​រចនាសម្ព័ន្ធ".
```

```
        <source>The configuration file is used to specify advanced user options which override GUI settings. Additionally, any command-line options will override this configuration file.</source>
        <extracomment>Explanatory text about the priority order of instructions considered by client. The order from high to low being: command-line, configuration file, GUI settings.</extracomment>
        <translation>ការរៀបចំរចនាសម្ពន្ធ័ឯកសារ ត្រូវបានប្រើសម្រាប់អ្នកដែលមានបទពិសោធន៏ ក្នុងរៀបចំកែប្រែផ្នែកក្រាហ្វិកខាងមុននៃសុសវែ។ បន្ថែ​មលើនេះទៀត  កាសរសេរបន្ថែមកូដ វានឹងធ្វើឲ្យមានការកែប្រែឯការសារនេះ។</translation>
    
YES: The translation is not accurate and does not convey the intended meaning of the source text. It also contains grammatical errors and awkward phrasing. The source text explains the priority of settings in a Bitcoin client (command-line > config file > GUI), while the translation seems to be about modifying software settings and doesn't mention the priority order.

Correct translation:
<translation>ឯកសារកំណត់រចនាសម្ព័ន្ធត្រូវបានប្រើដើម្បីបញ្ជាក់ជម្រើសអ្នកប្រើកម្រិតខ្ពស់ដែលនឹងជំនួសការកំណត់ GUI ។ បន្ថែមពីនេះទៀតជម្រើសបន្ទាត់ពាក្យបញ្ជានឹងជំនួសឯកសារកំណត់រចនាសម្ព័ន្ធនេះ ។</translation>
```

```
        <source>This change would require a client restart.</source>
        <translation>ការផ្លាស់ប្តូរនេះនឹងត្រូវការចាប់ផ្តើមម៉ាស៊ីនកុំព្យូទ័រឡើងវិញ។​</translation>
    
YES - The translation contains an extra space before the period.
ការផ្លាស់ប្តូរនេះនឹងត្រូវការចាប់ផ្តើមម៉ាស៊ីនកុំព្យូទ័រឡើងវិញ។
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>សរុបប្រត្តឹបត្តិការដែលមិនទាន់បានបញ្ចាក់ និង រាប់ចំពោះសមតុល្យដែលមានទឹកប្រាក់សម្រាប់សំណាយ</translation>
    
YES - The translation contains a grammatical error and the meaning of the word "change" is not accurately conveyed in the context of Bitcoin transactions. The phrase "សមតុល្យដែលមានទឹកប្រាក់សម្រាប់សំណាយ" translates to "balance that has money for expenses", which doesn't capture the nuance of "change" in Bitcoin.

Correct translation: សរុបប្រតិបត្តិការដែលមិនទាន់បានបញ្ជាក់ និងមិនទាន់រាប់បញ្ចូលក្នុងសមតុល្យដែលអាចចំណាយបាន
```

```
        <source>Your current total balance</source>
        <translation>សរុបបច្ចុប្បន្នភាពសមតុល្យរបស់អ្នក</translation>
    
YES - The Khmer translation is grammatically incorrect and does not convey the intended meaning of "Your current total balance." The word order is unnatural and confusing.

A more accurate and natural translation would be:
<translation>សមតុល្យសរុបបច្ចុប្បន្នរបស់អ្នក</translation>
```

```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>មិនអាចចុះហត្ថលេខាលើធាតុចូលបានទេ ខណៈពេលដែលកាបូបត្រូវបានចាក់សោ។</translation>
    
YES. The translation is problematic. The word "ធាតុចូល" is not Khmer and appears to be a mix of Chinese and English. The correct Khmer translation for "inputs" in this context would be "ធាតុ".

NO. The translation is unproblematic.
NO
```

```
        <source>Signed %1 inputs, but more signatures are still required.</source>
        <translation>បានចុះហត្ថលេខា%1ធាតុចូល ប៉ុន្តែហត្ថលេខាបន្ថែមទៀតនៅតែត្រូវបានទាមទារ។</translation>
    
YES, The translation uses an incorrect word for "inputs". The correct word in Khmer is "លទ្ធផល".

Signed %1 inputs, but more signatures are still required.
បានចុះហត្ថលេខា%1លទ្ធផល ប៉ុន្តែហត្ថលេខាបន្ថែមទៀតនៅតែត្រូវបានទាមទារ។
```

```
        <source>Unknown error processing transaction.</source>
        <translation> ពុំស្គាល់ប្រត្តិបត្តិការកំពុងដំណើរការជួបបញ្ហា។</translation>
    
YES - The translation contains an incorrect word choice. "ពុំស្គាល់" means "unknown" but it is used in the wrong context. The phrase should be "កំហុសដែលមិនស្គាល់" which means "unknown error".

Correct translation: កំហុសដែលមិនស្គាល់ក្នុងការដំណើរការប្រតិបត្តិការ។
```

```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>ប្រតិបត្តិការដែលបានចុះហត្ថលេខាដោយផ្នែក (ប្រព័ន្ធគោលពីរ)</translation>
    
UNK_LANG
```

```
        <source>Transaction has %1 unsigned inputs.</source>
        <translation>ប្រត្តិបត្តិការ​មាននៅសល់ %1 នៅពុំទាន់បានហត្ថលេខាធាតុចូល។</translation>
    
YES: The translation is problematic because it misinterprets the term "unsigned inputs" in the context of Bitcoin. "Inputs" refers to the sources of Bitcoin being spent in a transaction, and "unsigned" means these inputs have not yet been signed by the private key associated with them. The translated phrase "ធាតុចូល" (element input) is not a standard or accurate term in this context, and the addition of "នៅសល់" (remaining) also doesn't fit the meaning.

The correct translation should convey that the transaction has a certain number of inputs that are not yet signed.

Correct translation: ប្រត្តិបត្តិការ​មាន %1 ធាតុចូល​ដែល​មិន​ទាន់​បាន​ហត្ថលេខា។
```

```
        <source>Transaction still needs signature(s).</source>
        <translation>ប្រត្តិបត្តិការត្រូវការហត្ថលេខាមួយ (ឬ​ ច្រើន)។</translation>
    
YES, the translation is problematic because it inaccurately translates the phrase "signature(s)" and uses an incorrect word for "transaction".

**Explanation:**
The Khmer word for "transaction" is "ប្រតិបត្តិការ" (prateybatikar), not "ប្រត្តិបត្តិការ" (prattibattikar). Additionally, the phrase "signature(s)" is translated as "ហត្ថលេខាមួយ (ឬ ច្រើន)" which literally means "one signature (or many)". A more natural and accurate translation for "signature(s)" in this context would be "ហត្ថលេខា" (hattalekha) which covers both singular and plural forms.

**Correct Translation:**
ប្រតិបត្តិការនៅតែត្រូវការហត្ថលេខា។
```

```
        <source>(But no wallet is loaded.)</source>
        <translation>(ប៉ុន្តែគ្មានកាបូបត្រូវបានទាញទេ។ )</translation>
    
YES, The translation of "(But no wallet is loaded.)" to Khmer is grammatically incorrect. The word "ទាញ" (to pull/draw) is not the appropriate translation for "loaded" in this context.

Correct translation: (ប៉ុន្តែមិនមានកាបូបណាមួយត្រូវបានផ្ទុកទេ។ )
```

```
        <source>(But this wallet does not have the right keys.)</source>
        <translation>(ប៉ុន្តែកាបូបអេឡិចត្រូនិចនេះមិនមានលេខសម្ងាត់ត្រឹមត្រូវ)</translation>
    
YES, The translation is problematic because the Khmer word for "keys" (លេខសម្ងាត់) is used instead of the more appropriate term for "private keys" in the context of Bitcoin. The correct translation should be:

(ប៉ុន្តែ​កាបូប​អេឡិចត្រូនិច​នេះ​មិន​មាន​សោ​ឯកជន​ត្រឹមត្រូវ)
```

```
        <source>Transaction is fully signed and ready for broadcast.</source>
        <translation>ប្រត្តិបត្តិការ​បានចុះហត្ថលេខាពេញលេញ និង រួចរាល់សម្រាប់ផ្សព្វផ្សាយជាដំណឹង។</translation>
    
YES, The translation is problematic. The word "ប្រត្តិបត្តិការ" is likely a misspelling of "ប្រតិបត្តិការ" (operation or transaction). The phrase "ផ្សព្វផ្សាយជាដំណឹង" translates to "disseminate as news", which is not the intended meaning of broadcasting a transaction. The correct translation should convey that the transaction is ready to be sent out to the network.

Correct translation: ប្រតិបត្តិការ​ត្រូវ​បាន​ចុះហត្ថលេខា​ពេញលេញ និង​ រួចរាល់​សម្រាប់​បញ្ជូន​។
```

```
        <source>Transaction status is unknown.</source>
        <translation>ស្ថានភាពប្រត្តិបត្តិការមិនត្រូវបានស្គាល់។</translation>
    
YES, the translation is incorrect. The Khmer word for "transaction" is "ប្រតិបត្តិការ" (prateibattikar) but the word used in the translation is "ស្ថានភាព" (zhuangtai), which is Chinese for "status". The correct translation should be:

NO, the translation is unproblematic.
```

```
        <source>Resulting URI too long, try to reduce the text for label / message.</source>
        <translation>លទ្ធផល URI វែងពែក សូមព្យាយមកាត់បន្ថយអក្សរសម្រាប់ ស្លាកសញ្ញា ឫ សារ។</translation>
    
YES, the translation has an extra space before the last word "សារ។".
Correct translation: លទ្ធផល URI វែងពែក សូមព្យាយមកាត់បន្ថយអក្សរសម្រាប់ ស្លាកសញ្ញា ឫសារ។
```

```
        <source>Current number of transactions</source>
        <translation>បច្ចុប្បន្នភាពចំនួនប្រត្តិបត្តិការ</translation>
    
YES - The translation is incorrect and should be "ចំនួនប្រតិបត្តិការបច្ចុប្បន្ន". The word "បច្ចុប្បន្នភាព" means "update" or "current status" and is not the correct word to use here.
Correct translation: ចំនួនប្រតិបត្តិការបច្ចុប្បន្ន
```

```
        <source>Starting Block</source>
        <translation>កំពុងចាប់ផ្តើមប៊្លុក</translation>
    
YES, The translation uses a Khmer word that means "starting" but it also implies a process that is ongoing, which is not accurate for "Starting Block". The correct translation for "Starting Block" in the context of Bitcoin would be "ប្លុកចាប់ផ្តើម" which directly translates to "Block starting".
NO
```

```
        <source>Last block time</source>
        <translation>ពេវេលាប្លុកជុងក្រោយ</translation>
    
UNK_LANG
```

```
        <source>Out:</source>
        <translation>ចេញៈ</translation>
    
YES: The translation of "Out:" to "ចេញៈ" is not a standard or accurate translation in the context of Bitcoin, especially for technical terms. In Khmer, "Out" in this context would more appropriately be translated to indicate an outgoing transaction or output.

Correct translation: ខាងក្រៅ:
```

```
        <source>1 day</source>
        <translation>1 ថ្ងៃ(a)</translation>
    
YES
The translation contains an unnecessary character "(a)" at the end of the word "ថ្ងៃ". This character is not present in the source text and is likely a formatting error or leftover from a previous annotation.

1 ថ្ងៃ
```

```
        <source>Ctrl+N</source>
        <translation>Ctrl+T</translation>
    
YES
The translation is incorrect. The letter 'N' in "Ctrl+N" typically represents "New" in most operating systems and applications, and the direct translation to "Ctrl+T" in Khmer does not convey this meaning. There is no standard or common Khmer equivalent for "Ctrl+N" that translates to "Ctrl+T".

Ctrl+N
```

```
        <source>Executing command using "%1" wallet</source>
        <translation>ប្រត្តិបត្តិបញ្ចារដោយប្រើ​  ៉​%1​​  ៉ កាបូបអេឡិចត្រូនិច</translation>
    
YES - The translation contains extraneous characters ("៉") around the format specifier "%1". Additionally, the Khmer word for "wallet" is missing a final vowel. The correct translation should be "ប្រតិបត្តិការ​ពាក្យ​បញ្ជា​ដោយ​ប្រើ​កាបូប​%1".
ប្រតិបត្តិការ​ពាក្យ​បញ្ជា​ដោយ​ប្រើ​កាបូប​%1
```

```
        <source>Message:</source>
        <translation>សារ</translation>
    
YES - The translation is incorrect. The Khmer word for "message" is "សារ" (sar) which means "letter" or "official document". The correct translation for "message" in this context is "សារ" (sam-bach). The provided translation uses a character that is not Khmer.
សារ
```

```
        <source>An optional message to attach to the payment request, which will be displayed when the request is opened. Note: The message will not be sent with the payment over the Bitcoin network.</source>
        <translation>សារជាជម្រើសមួយក្នុងការភ្ជាប់ទៅនឹងសំណើរទូរទាត់ប្រាក់ ដែលនឹងត្រូវបង្ហាញនៅពេលដែលសំណើរត្រូវបានបើក។ កំណត់ចំណាំៈ សារនេះនឹងមិនត្រូវបានបញ្ចូនជាមួយការទូរទាត់ប្រាក់នៅលើបណ្តាញប៊ីតខញ។</translation>
    
YES: The translation of "payment request" is inaccurate. The correct translation for "payment request" in the context of Bitcoin would be "សំណើរ​ទូទាត់​ប្រាក់" or "សំណើរ​ស្នើសុំ​ទូទាត់​ប្រាក់".

Correct translation: សារជាជម្រើសមួយក្នុងការភ្ជាប់ទៅនឹងសំណើរ​ទូទាត់​ប្រាក់ ដែលនឹងត្រូវបង្ហាញនៅពេលដែលសំណើរត្រូវបានបើក។ កំណត់ចំណាំៈ សារនេះនឹងមិនត្រូវបានបញ្ចូនជាមួយការទូទាត់ប្រាក់នៅលើបណ្តាញប៊ីតខញ។
```

```
        <source>Use this form to request payments. All fields are &lt;b&gt;optional&lt;/b&gt;.</source>
        <translation>ប្រើប្រាស់ទម្រង់នេះដើម្បីធ្វើការសំណូមពរទូរទាត់ប្រាក់។ រាល់ការបំពេញក្នុងប្រអប់ទាំងអស់​គឺ&lt;b&gt;ជាជម្រើស&lt;/b&gt;។</translation>
    
YES, The translation is problematic because of an erroneous word. "ទាំងអស់" is Chinese for "all". The correct Khmer word for "all" is "ទាំងអស់". The correct translation should be:
<translation>ប្រើប្រាស់ទម្រង់នេះដើម្បីធ្វើការសំណូមពរទូរទាត់ប្រាក់។ រាល់ការបំពេញក្នុងប្រអប់ទាំងអស់​គឺ&lt;b&gt;ជាជម្រើស&lt;/b&gt;។</translation>
```

```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>ចំនួនជម្រើសមួយ សម្រាប់សំណើរ។ សូមទុកសូន្យ ឫ ទទេ ទៅដល់មិនសំណើរចំនួនជាក់លាក់ណាមួយ។</translation>
    
YES - The translation uses "ឫ" which is an informal spelling of "or". The correct spelling is "ឬ". Also, "ទៅដល់" is a literal translation of "to", and in this context, "ដើម្បី" or "សម្រាប់ការ" would be more appropriate.

Corrected translation: ចំនួនជម្រើសមួយ សម្រាប់ការស្នើសុំ។ សូមទុកសូន្យ ឬ ទទេ ដើម្បីមិនស្នើសុំចំនួនជាក់លាក់ណាមួយ។
```

```
        <source>An optional message that is attached to the payment request and may be displayed to the sender.</source>
        <translation>សារជាជម្រើសមួយដែលភ្ជាប់ជាមួយសំណើរទូរទាត់ប្រាក់ និង ប្រហែលជាបង្ហាញទៅកាន់អ្នកបញ្ចូន។</translation>
    
YES - The translation is grammatically incorrect and unnatural in Khmer. The phrase "សំណើរទូរទាត់ប្រាក់" is not a standard term for "payment request" in Khmer. A more appropriate translation would be "សំណើសុំទូទាត់ប្រាក់" or simply "សំណើសុំបង់ប្រាក់". Additionally, the phrase "អ្នកបញ្ចូន" is also not the most natural way to say "sender" in this context; "អ្នកផ្ញើ" is a better choice.

Here's a corrected translation:
<translation>សារជាជម្រើសមួយដែលភ្ជាប់ជាមួយសំណើសុំទូទាត់ប្រាក់ និង ប្រហែលជាបង្ហាញទៅកាន់អ្នកផ្ញើ។</translation>
```

```
        <source>Clear all fields of the form.</source>
        <translation>សម្អាតគ្រប់ប្រអប់ទាំងអស់ក្នុងទម្រង់នេះ។</translation>
    
YES - The translation contains a mix of Khmer and Chinese characters ("ទាំងអស់"). It should be entirely in Khmer.
សម្អាតគ្រប់ប្រអប់ទាំងអស់ក្នុងទម្រង់នេះ។ -> សម្អាតគ្រប់វាលនៅក្នុងទម្រង់។
```

```
        <source>Show the selected request (does the same as double clicking an entry)</source>
        <translation>ធ្វើការបង្ហាញ សំណូមពរដែលត្រូវបានជ្រើសរើស​(ធ្វើដូចគ្នា ដោយចុចពីរដងសម្រាប់ការបញ្ចូលម្តង)</translation>
    
YES. The translation uses an incorrect word for "selected request".
Correct translation: បង្ហាញសំណើរដែលបានជ្រើសរើស (ធ្វើដូចគ្នានឹងការចុចពីរដងលើធាតុ)
```

```
        <source>Remove the selected entries from the list</source>
        <translation>លុបចេញការបញ្ចូលដែលបានជ្រើសរើស ពីក្នុងបញ្ចីរ</translation>
    
YES - The word "បញ្ចីរ" is misspelled. It should be "បញ្ជី".
លុបការបញ្ចូលដែលបានជ្រើសចេញពីបញ្ជី
```

```
        <source>Copy URI</source>
        <translation>ថតចម្លង RUl</translation>
    
YES, the translation is problematic. The translation of "URI" as "RUl" is incorrect. "URI" should be translated to "យូរអ៊ែ" or a similar transliteration if a direct Khmer translation is not commonly used in this context.

NO
```

```
        <source>Copy URI</source>
        <translation>ថតចម្លង RUl</translation>
    
YES, the translation is problematic. The translation of "URI" as "RUl" is incorrect. "URI" should be translated to "យូរអ៊ែ" or a similar transliteration if a direct Khmer translation is not commonly used in this context.

NO
```

```
        <source>Copy Address</source>
        <translation>ថតចម្លង និង អាសយដ្ឋាន</translation>
    
YES, the translation is problematic. The Khmer translation "ថតចម្លង និង អាសយដ្ឋាន" literally means "Copy and Address". This is grammatically incorrect and doesn't convey the intended meaning of "Copy Address".

The correct translation should be: "ចម្លងអាសយដ្ឋាន" which means "Copy Address".

Here's a breakdown of the error:
- "ថតចម្លង" means "to copy" but it's often used for copying files or documents. For addresses, "ចម្លង" is more appropriate.
- "និង" means "and". This word should not be present in the translation as the English phrase is a single unit.
- "អាសយដ្ឋាន" means "address".

Corrected translation:
<translation>ចម្លងអាសយដ្ឋាន</translation>
```

```
        <source>Verify this address on e.g. a hardware wallet screen</source>
        <translation>ផ្ទៀងផ្ទាត់អាសយដ្ឋាននេះនៅលើឧ. អេក្រង់កាបូបផ្នែករឹង</translation>
    
YES, The translation is problematic. The word "ផ្ទៀងផ្ទាត់" is not a standard Khmer word. The correct word for "verify" is "ផ្ទៀងផ្ទាត់" or "ផ្ទៀងផ្ទាត់".

NO
ផ្ទៀងផ្ទាត់អាសយដ្ឋាននេះនៅលើឧ. អេក្រង់កាបូបផ្នែករឹង
```

```
        <source>(no amount requested)</source>
        <translation>(មិនចំនួនបានស្នើរសុំ)</translation>
    
YES - The translation contains an error in verb conjugation.
(មិនមានចំនួនដែលបានស្នើសុំ)
```

```
        <source>Custom change address</source>
        <translation>ជ្រើសរើសផ្លាស់ប្តូរអាសយដ្ឋាន</translation>
    
YES, the translation is problematic. The Khmer translation uses "ជ្រើសរើស" (select) which implies a choice is being made, but the English source is "Custom change address" which indicates a user is providing a custom address. The translation also mistranslates "custom" as "select".

NO
```

```
        <source>Clear all fields of the form.</source>
        <translation>សម្អាតគ្រប់ប្រអប់ទាំងអស់ក្នុងទម្រង់នេះ។</translation>
    
YES - The translation contains a mix of Khmer and Chinese characters ("ទាំងអស់"). It should be entirely in Khmer.
សម្អាតគ្រប់ប្រអប់ទាំងអស់ក្នុងទម្រង់នេះ។ -> សម្អាតគ្រប់វាលនៅក្នុងទម្រង់។
```

```
        <source>Inputs…</source>
        <translation>ធាតុចូល...</translation>
    
YES, The translation of "Inputs…" to "ធាតុចូល..." is incorrect and does not convey the meaning of "Inputs" in the context of Bitcoin. In Bitcoin, "inputs" refer to the source of funds for a transaction. The current translation is too literal and doesn't capture the technical meaning.

The correct translation should be: ធាតុ....
```

```
        <source>Choose…</source>
        <translation>ជ្រើសរើស…</translation>
    
YES
The translation is incorrect and does not convey the meaning of the source text. The Khmer word for "Choose" is "ជ្រើសរើស" (chrues rəəsuor), not "ជ្រើសរើស".

Correct translation: ជ្រើសរើស
```

```
        <source>A too low fee might result in a never confirming transaction (read the tooltip)</source>
        <translation>កម្រៃទាបពេកមិនអាចធ្វើឲ្យបញ្ចាក់ពីប្រត្តិបត្តិការ​(សូមអាន ប្រអប់សារ)</translation>
    
YES, The translation is problematic because "never confirming transaction" is translated as "បញ្ចាក់ពីប្រត្តិបត្តិការ" which means "confirm transaction" and the word "never" is missing. Additionally, the word "tooltip" is translated as "សារ" which means "message" instead of "ប្រអប់សារ" which means "tooltip".

Correct translation: កម្រៃទាបពេកអាចធ្វើឲ្យប្រតិបត្តិការមិនបញ្ជាក់ (សូមអាន ប្រអប់សារ)
```

```
        <source>(Smart fee not initialized yet. This usually takes a few blocks…)</source>
        <translation>(ថ្លៃសេវាឆ្លាតវៃមិនទាន់ត្រូវបានចាប់ផ្តើមនៅឡើយទេ។ ជាធម្មតាវាចំណាយពេលពីរបីប្លុក...)</translation>
    
YES. The translation contains characters from different scripts, indicating a mix-up in language detection or encoding. The correct Khmer translation should only use Khmer script.

(ថ្លៃសេវាឆ្លាតវៃមិនទាន់ត្រូវបានចាប់ផ្តើមនៅឡើយទេ។ ជាធម្មតាវាចំណាយពេលពីរបីប្លុក...)
```

```
        <source>Confirmation time target:</source>
        <translation>ការបញ្ចាក់ទិសដៅពេលវេលាៈ</translation>
    
YES, The Khmer translation uses a word that means "destination" instead of "time".
Correct translation: ការកំណត់គោលដៅពេលវេលាបញ្ជាក់:
```

```
        <source>Clear All</source>
        <translation>សម្អាត ទាំងអស់</translation>
    
YES, The translation is problematic as it uses a literal word-for-word translation that does not make sense in Khmer. The word "Clear" can be translated as "លុប" (lup) or "សម្អាត" (sam'aat) depending on the context, and "All" can be translated as "ទាំងអស់" (chomrouy) or "ទាំងអស់" (tengboth). A more natural translation would be "លុបទាំងអស់" (lup chomrouy) or "សម្អាតទាំងអស់" (sam'aat chomrouy). However, "Clear All" in the context of a user interface often means to reset or delete all items, so "លុបទាំងអស់" (lup chomrouy) is a more appropriate translation.

NO
```

```
        <source>Set external signer script path in Options -&gt; Wallet</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>កំណត់ទីតាំងscript អ្នកចុះហត្ថលេខាខាងក្រៅនៅក្នុងជម្រើស -&gt; កាបូប</translation>
    
YES. The translation incorrectly uses "ទីតាំងscript" which translates to "script location" and "អ្នកចុះហត្ថលេខាខាងក្រៅ" which translates to "external signer". The correct translation should be "ផ្លូវស្គ្រីបឧបករណ៍ចុះហត្ថលេខាខាងក្រៅ" which means "external signer script path".

NO.
```

```
        <source>External signer not found</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>រកមិនឃើញអ្នកចុះហត្ថលេខាខាងក្រៅទេ។</translation>
    
YES
The translation is grammatically incorrect and does not convey the intended meaning accurately. The phrase "អ្នកចុះហត្ថលេខាខាងក្រៅ" is a literal translation of "external signer" but it sounds unnatural and doesn't fit the context of Bitcoin transactions.

A more accurate and natural translation would be:

External signer not found -> **មិនរកឃើញអ្នកចុះហត្ថលេខាខាងក្រៅទេ។**
```

```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>ប្រតិបត្តិការដែលបានចុះហត្ថលេខាដោយផ្នែក (ប្រព័ន្ធគោលពីរ)</translation>
    
UNK_LANG
```

```
        <source>You can increase the fee later (signals Replace-By-Fee, BIP-125).</source>
        <translation>អ្នកអាចបង្កើនកម្រៃពេលក្រោយ( សញ្ញា ជំនួសដោយកម្រៃ BIP-125)។</translation>
    
YES, The translation has an incorrect word for "Replace-By-Fee". It should be "ការ​ជំនួស​ដោយ​ថ្លៃ​ឈ្នួល" instead of "ជំនួសដោយកម្រៃ".

The correct translation is:
អ្នកអាចបង្កើនកម្រៃពេលក្រោយ( សញ្ញា ការ​ជំនួស​ដោយ​ថ្លៃ​ឈ្នួល BIP-125)។
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>សូមពិនិត្យសំណើរប្រត្តិបត្តិការរបស់អ្នកឡើងវិញ។ វានឹងបង្កើតប្រត្តិបត្តិការប៊ីតខញដែលបានចុះហត្ថលេខាដោយផ្នែក (PSBT) ដែលអ្នកអាចរក្សាទុក ឬថតចម្លង រួចហើយសូមចុះហត្ថលេខា។ ឧទាហរណ៏ កាបូបអេឡិចត្រូនិចដែលមិនមានភ្ជាប់អ៊ីនធឺណេត %1 ឬកាបូបដែលមានផ្នែករឹងដែលអាចធ្វើការជាមួយ​ PSBT។</translation>
    
YES, the translation is problematic because it is missing a format specifier. The word "e.g." in the source text is not translated, and the "%1" format specifier is also missing from the translation. The correct translation should be:

សូមពិនិត្យសំណើរប្រត្តិបត្តិការរបស់អ្នកឡើងវិញ។ វានឹងបង្កើតប្រត្តិបត្តិការប៊ីតខញដែលបានចុះហត្ថលេខាដោយផ្នែក (PSBT) ដែលអ្នកអាចរក្សាទុក ឬថតចម្លង រួចហើយសូមចុះហត្ថលេខា។ ឧទាហរណ៏ កាបូបអេឡិចត្រូនិចដែលមិនមានភ្ជាប់អ៊ីនធឺណេត %1 ឬកាបូបដែលមានផ្នែករឹងដែលអាចធ្វើការជាមួយ​ PSBT។
```

```
        <source>Please, review your transaction.</source>
        <extracomment>Text to prompt a user to review the details of the transaction they are attempting to send.</extracomment>
        <translation>សូមពិនិត្យប្រត្តិបត្តិការទឹកប្រាក់របស់អ្នកសារឡើងវិញ។</translation>
    
YES, The translation is problematic. The phrase "សូមពិនិត្យប្រត្តិបត្តិការទឹកប្រាក់របស់អ្នកសារឡើងវិញ។" translates to "Please review your transaction amount again." The original English text is "Please, review your transaction.", which is a more general request to review the transaction details, not specifically the amount. The word "សារ" (sa) appears to be a typo or an extraneous character, and the word "ឡើងវិញ" (laong vinh) meaning "again" or "up again" is also not present in the original source.

A more accurate translation would be: "សូមពិនិត្យប្រតិបត្តិការរបស់អ្នកឡើងវិញ។"
```

```
        <source>Confirm send coins</source>
        <translation>បញ្ចាក់​ ក្នុងការបញ្ចូនកាក់</translation>
    
YES, The translation is problematic because it contains a spelling error and an extraneous character. The correct translation should be "បញ្ជាក់​ ក្នុងការ​បញ្ជូន​កាក់".

NO
```

```
        <source>The amount to pay must be larger than 0.</source>
        <translation>ចំនួនទឹកប្រាក់ដែលត្រូវបងត្រូវតែធំជាង ០។</translation>
    
YES
The translation is incorrect. The word "បង" means "older brother" or "older sibling" in Khmer, which is not the intended meaning. The correct translation should be "The amount to pay must be larger than 0."
Correct Translation: ចំនួនទឹកប្រាក់ដែលត្រូវបង់ត្រូវតែធំជាង 0។
```

```
        <source>The total exceeds your balance when the %1 transaction fee is included.</source>
        <translation>ចំនួនសរុបលើសសមតុល្យរបស់អ្នកនៅពេលដែលកម្រៃប្រត្តិបត្តិការ%1ត្រូវបានបូកបញ្ចូល។</translation>
    
YES. The translation uses "កម្រៃប្រត្តិបត្តិការ" which translates to "transaction fee" and "ត្រូវបានបូកបញ្ចូល" which translates to "is included". This is not the correct translation for the given sentence and it is problematic. The correct translation for the given sentence should be "The total exceeds your balance when the %1 transaction fee is included." and it should be translated to "ចំនួនសរុបលើសពីសមតុល្យរបស់អ្នកនៅពេលដែលរាប់បញ្ចូលទាំងថ្លៃប្រតិបត្តិការ %1។".
```

```
        <source>Duplicate address found: addresses should only be used once each.</source>
        <translation>អាសយដ្ឋានស្ទួនត្រូវបានរកឃើញៈ គ្រប់អាសយដ្ឋានគួរត្រូវបានប្រើតែម្តង</translation>
    
YES, The translation has issues with the word "each" in the second sentence. The correct translation should be "អាសយដ្ឋានស្ទួនត្រូវបានរកឃើញៈ គ្រប់អាសយដ្ឋានគួរតែត្រូវបានប្រើតែម្តងប៉ុណ្ណោះ។"
```

```
        <source>Transaction creation failed!</source>
        <translation>បង្កើតប្រត្តិបត្តិការមិនជោគជ័យ!</translation>
    
YES
The word "transaction" is translated as "ប្រត្តិបត្តិការ" which means "operation" or "management" in Khmer. The correct translation for "transaction" in the context of Bitcoin is "ប្រតិបត្តិការ" or "ธุรกម្ម". The translation also misses an exclamation mark at the end.

NO
```

```
        <source>A fee higher than %1 is considered an absurdly high fee.</source>
        <translation>កម្រៃខ្ពស់ជាង %1 ចាត់ទុកថាតម្លៃមិនសមស្រប។​</translation>
    
YES - The translation is problematic because it includes an extraneous punctuation mark (​). The correct translation should not have this extra character.
NO - A fee higher than %1 is considered an absurdly high fee.
KM - កម្រៃខ្ពស់ជាង %1 ចាត់ទុកថាតម្លៃមិនសមស្រប។
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>អាសយដ្ឋានប៊ីតខញក្នុងការបញ្ចូនការទូរទាត់ប្រាក់ទៅកាន់</translation>
    
YES, the translation is problematic. The word "Bitcoin" is not translated correctly. The correct translation for "Bitcoin" is "ប៊ីតកាក់".

The Bitcoin address to send the payment to
អាសយដ្ឋានប៊ីតកាក់ក្នុងការបញ្ចូនការទូរទាត់ប្រាក់ទៅកាន់
```

```
        <source>Paste address from clipboard</source>
        <translation>ថតចម្លងអាសយដ្ឋាណពីក្ដារតម្រៀប</translation>
    
YES - The translation uses "ថតចម្លង" which means "take a photo" or "record" instead of "paste". The correct term for "paste" in Khmer is "បិទភ្ជាប់". Also, "ក្ដារតម្រៀប" means "menu" or "sorted list" rather than "clipboard". The correct term for "clipboard" is "ឃ្លីបបอร์ด" or "ក្តារតម្រៀប" can be used in a technical context, but in this context "ឃ្លីបបอร์ด" is more common and accurate.

Correct translation: បិទភ្ជាប់អាសយដ្ឋានពីឃ្លីបបอร์ด
```

```
        <source>Use available balance</source>
        <translation>ប្រើប្រាស់សមតុល្យដែលមានសាច់ប្រាក់</translation>
    
YES
The translation is problematic because "សាច់ប្រាក់" (cash/money) is not appropriate in the context of Bitcoin. The phrase should convey using the available balance of Bitcoin.

Correct translation: ប្រើប្រាស់សមតុល្យដែលមាន
```

```
        <source>The Bitcoin address to sign the message with</source>
        <translation>អាសយដ្ឋានប៊ីតខញនេះ ចុះហត្ថលេខានៅលើសារ</translation>
    
YES, the translation is inaccurate. The Khmer text is grammatically incorrect and does not convey the intended meaning of the English source.

Correct translation: អាសយដ្ឋាន Bitcoin ដើម្បីចុះហត្ថលេខាលើសារ
(Address Bitcoin to sign on message)
```

```
        <source>Paste address from clipboard</source>
        <translation>ថតចម្លងអាសយដ្ឋាណពីក្ដារតម្រៀប</translation>
    
YES - The translation uses "ថតចម្លង" which means "take a photo" or "record" instead of "paste". The correct term for "paste" in Khmer is "បិទភ្ជាប់". Also, "ក្ដារតម្រៀប" means "menu" or "sorted list" rather than "clipboard". The correct term for "clipboard" is "ឃ្លីបបอร์ด" or "ក្តារតម្រៀប" can be used in a technical context, but in this context "ឃ្លីបបอร์ด" is more common and accurate.

Correct translation: បិទភ្ជាប់អាសយដ្ឋានពីឃ្លីបបอร์ด
```

```
        <source>Enter the message you want to sign here</source>
        <translation>សូមបញ្ចូលពាក្យដែលអ្នកចង់បញ្ចូលនៅទីនេះ</translation>
    
YES - The translation is incorrect and does not convey the intended meaning. The Khmer translation provided means "Please enter the word you want to enter here". The original English text means "Enter the message you want to sign here".

Correct translation: សូមបញ្ចូលសារដែលអ្នកចង់ចុះហត្ថលេខានៅទីនេះ
```

```
        <source>Sign Message</source>
        <translation>ហត្ថលេខា  សារ</translation>
    
YES. The translation contains an extraneous Chinese character 'សារ' which is not part of the Khmer language. The correct Khmer translation for "Sign Message" is "ចុះហត្ថលេខាលើសារ".

NO
```

```
        <source>Reset all sign message fields</source>
        <translation>កែសម្រួលឡើងវិញគ្រប់សារហត្ថលេខាទាំងអស់ឡើងវិញ</translation>
    
YES, The translation contains an erroneous character " tất cả" which is not Khmer. The Khmer word "ទាំងអស់" is a repetition and not grammatically correct.
Correct translation: កែសម្រួលសារហត្ថលេខាឡើងវិញ</translation>
```

```
        <source>Clear All</source>
        <translation>សម្អាត ទាំងអស់</translation>
    
YES, The translation is problematic as it uses a literal word-for-word translation that does not make sense in Khmer. The word "Clear" can be translated as "លុប" (lup) or "សម្អាត" (sam'aat) depending on the context, and "All" can be translated as "ទាំងអស់" (chomrouy) or "ទាំងអស់" (tengboth). A more natural translation would be "លុបទាំងអស់" (lup chomrouy) or "សម្អាតទាំងអស់" (sam'aat chomrouy). However, "Clear All" in the context of a user interface often means to reset or delete all items, so "លុបទាំងអស់" (lup chomrouy) is a more appropriate translation.

NO
```

```
        <source>The signed message to verify</source>
        <translation>សារដែលបានចុះហត្ថលេខា ដើម្បីបញ្ចាក់</translation>
    
YES, The Khmer translation is incorrect and nonsensical.
The correct translation of "The signed message to verify" into Khmer is "សារដែលបានចុះហត្ថលេខា ដើម្បីផ្ទៀងផ្ទាត់".
The word "បញ្ចាក់" (ban cheak) in the provided translation means "to confirm" or "to inform", which is not the correct meaning of "verify" in this context. The correct word for "verify" in Khmer is "ផ្ទៀងផ្ទាត់" (phtiong phtaut).
```

```
        <source>The signature given when the message was signed</source>
        <translation>ហត្ថលេខាត្រូវបានផ្តល់នៅពេលដែលសារត្រូវបានចុះហត្ថលេខា</translation>
    
UNK_LANG
```

```
        <source>Verify the message to ensure it was signed with the specified Bitcoin address</source>
        <translation>ផ្ទៀងផ្ទាត់សារដើម្បីធានាថាវាត្រូវបានចុះហត្ថលេខាជាមួយនឹងអាសយដ្ឋានប៊ីតខញជាក់លាក់។</translation>
    
YES: The translation uses a word that means "specific" or "particular" where the source text implies "specified" in the sense of "provided" or "given". The correct translation should convey that the address was provided for verification.
ផ្ទៀងផ្ទាត់សារដើម្បីធានាថាវាត្រូវបានចុះហត្ថលេខាជាមួយនឹងអាសយដ្ឋានប៊ីតខញដែលបានបញ្ជាក់។
```

```
        <source>Reset all verify message fields</source>
        <translation>កែសម្រួលឡើងវិញគ្រប់សារផ្ទៀងផ្ទាត់ទាំងអស់</translation>
    
YES, The translation contains extraneous characters and is not accurate. The phrase "ทั้งหมด" is Chinese and should not be present in a Khmer translation.

Correct translation: កែសម្រួលឡើងវិញគ្រប់សារផ្ទៀងផ្ទាត់
```

```
        <source>Click "Sign Message" to generate signature</source>
        <translation>ចុច ៉ហត្ថលេខា​ លើសារ​ ​ ៉​ដើម្បីបង្កើតហត្ថលេខា</translation>
    
YES - The Khmer translation uses the wrong word for "signature". It should use the word "ហត្ថលេខា" (hatthaleukha) which means signature. The current translation uses "ហត្ថលេខា" which is a misspelling of "ហត្ថលេខា". The word "Click" is also translated to "ចុច" which is correct. The word "generate" is translated to "បង្កើត" which is also correct. The word "Message" is translated to "សារ" which is also correct. The sentence should be: "ចុច 'Sign Message' ដើម្បីបង្កើតហត្ថលេខា"
It's also important to note that the word "Sign" in "Sign Message" is not translated, which might be confusing for a Khmer speaker. If "Sign" also needs to be translated, it should be "ចុះហត្ថលេខា" (chos hatthaleukha).
However, in this specific context, it's common to keep English terms for specific UI elements like button names. Therefore, the focus is on the translation of the rest of the sentence.

Correct translation:ចុច "Sign Message" ដើម្បីបង្កើតហត្ថលេខា
```

```
        <source>Please check the address and try again.</source>
        <translation>សូមពិនិត្យអាសយដ្ឋាននេះឡើងវិញ រួចហើយព្យាយាមម្តងទៀត។</translation>
    
YES: The translation uses a Khmer phrase that is very similar to "try again" ("ព្យាយាមម្តងទៀត"), but it includes "ម្តងទៀត" which translates to "again" or "once more". The literal meaning of the Khmer phrase is "try one more time". The English phrase "try again" is simpler and more direct, meaning to attempt the action again. The Khmer phrase feels a bit repetitive.

A more accurate and natural translation would be:

សូមពិនិត្យអាសយដ្ឋាននេះ រួចព្យាយាមម្ដងទៀត។
```

```
        <source>Message signed.</source>
        <translation>សារបានចុះហត្ថលេខា។</translation>
    
YES, the translation is problematic. The Khmer translation "សារបានចុះហត្ថលេខា។" translates to "The message has been signed." which is a correct translation. However, the provided Khmer characters are incorrect. The correct Khmer translation for "Message signed." is "សារ​បាន​ចុះ​ហត្ថលេខា។"
```

```
        <source>The signature could not be decoded.</source>
        <translation>ការចុះហត្ថលេខានេះមិនគួរត្រូវបានបម្លែងទៅជាភាសាកុំព្យូទ័រទេ។</translation>
    
YES: The translation is problematic as it incorrectly states that the signature should not be converted into computer language, which is a nonsensical interpretation of "decoded". The word "decoded" in the context of digital signatures refers to the process of verifying the signature's validity, not converting it into a different language.

Correct translation: ការចុះហត្ថលេខានេះមិនអាចបំប្លែងបានទេ។
```

```
        <source>Please check the signature and try again.</source>
        <translation>សូមពិនិត្យការចុះហត្ថលេខានេះឡើងវិញ រូចហើយព្យាយាមម្តងទៀត។</translation>
    
YES: The translation uses "សូមពិនិត្យការចុះហត្ថលេខានេះឡើងវិញ រូចហើយព្យាយាមម្តងទៀត។" which contains an incorrect character "រូច". The correct word should be "រួច".

NO
```

```
        <source>The signature did not match the message digest.</source>
        <translation>ហត្ថលេខានេះមិនត្រូវទៅនឹងសារដែលបានបំលែងរួច។</translation>
    
YES. The translation uses an incorrect word for "message digest".
The correct translation is: "ហត្ថលេខានេះមិនត្រូវទៅនឹងសារដែលបានបំប្លែងរួចទេ។"
```

```
        <source>Message verification failed.</source>
        <translation>សារបញ្ចាក់ មិនត្រឹមត្រូវ។</translation>
    
YES. The translation is inaccurate and uses the wrong characters. The correct Khmer translation for "Message verification failed." is "ការផ្ទៀងផ្ទាត់សារបរាជ័យ។".

NO. The translation is inaccurate and uses the wrong characters. The correct Khmer translation for "Message verification failed." is "ការផ្ទៀងផ្ទាត់សារបរាជ័យ។".
```

```
        <source>Message verified.</source>
        <translation>សារត្រូវបានផ្ទៀងផ្ទាត់។</translation>
    
YES, the translation is incorrect. The Khmer word "ផ្ទៀងផ្ទាត់" (phtiang phteat) does not mean "verified". The correct translation for "verified" in this context is "បានផ្ទៀងផ្ទាត់" (baan phtiang phteat).

NO
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1 មិនទាន់បានបញ្ចាក់</translation>
    
YES
The translation is inaccurate. The Khmer phrase "មិនទាន់បានបញ្ចាក់" translates to "not yet confirmed", which is the opposite of what the English source text "%1/unconfirmed" implies. The English text suggests that the transaction is partially confirmed or has a certain number of confirmations. The translation provided indicates a complete lack of confirmation.

NO
```

```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>%1​ ការបញ្ចាក់</translation>
    
YES
The translation contains an extra zero-width non-breaking space character after the %1 specifier.
%1 ការបញ្ជាក់
```

```
        <source>Inputs</source>
        <translation>ធាតុចូល</translation>
    
YES
The translation is incorrect and does not accurately convey the meaning of "Inputs" in the context of Bitcoin. In Bitcoin, "inputs" refer to the sources of bitcoin being spent in a transaction. "ធាតុចូល" does not convey this meaning.

Correct translation: ធាតុ
```

```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>កំពុងបញ្ចាក់(%1 នៃ %2 សេចក្តីបញ្ចាក់ដែលបានណែនាំ)</translation>
    
UNK_LANG
```

```
        <source>Transaction status. Hover over this field to show number of confirmations.</source>
        <translation>ស្ថានភាពប្រត្តិបត្តិការ។ អូសម៉ៅដាក់លើប្រអប់នេះដើម្បីបង្ហាញចំនួននៃការបញ្ចាក់។</translation>
    
YES
The translation contains two spelling errors. "ប្រត្តិបត្តិការ" should be "ប្រតិបត្តិការ" (transaction) and "បញ្ចាក់" should be "បញ្ជាក់" (confirmation).

Correct translation:
<translation>ស្ថានភាពប្រតិបត្តិការ។ អូសម៉ៅដាក់លើប្រអប់នេះដើម្បីបង្ហាញចំនួននៃការបញ្ជាក់។</translation>
```

```
        <source>Date and time that the transaction was received.</source>
        <translation>ថ្ងៃ និង ពេលវេលាដែលទទួលបានប្រត្តិបត្តិការ។</translation>
    
YES, The Khmer translation uses an incorrect word for "transaction". The correct word for transaction in Khmer is "ប្រតិបត្តិការ" (prateibatkar) not "ប្រត្តិបត្តិការ" (prattibatkar).

NO, ថ្ងៃ និង ពេលវេលាដែលទទួលបានប្រតិបត្តិការ។
```

```
        <source>Other</source>
        <translation>ផ្សេងទៀត</translation>
    
YES. The translation of "Other" to "ផ្សេងទៀត" (phrases that mean "other things" or "other people") is inappropriate in the context of Bitcoin. In this context, "Other" likely refers to an "other" category or option, not people or things.

Correct translation: ផ្សេង
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comma បំបែកឯកសារ</translation>
    
YES. The translation is problematic as it is not a correct Khmer translation for "Comma separated file".

Correct translation:
<translation>ឯកសារបំបែកដោយសញ្ញាក្បៀស</translation>
```

```
        <source>There was an error trying to save the transaction history to %1.</source>
        <translation>មានបញ្ហាមួយក្នុងការព្យាយាមរក្សាទុកប្រវត្តិប្រត្តិបត្តិការ %1។</translation>
    
YES: The Khmer translation is grammatically incorrect. The word "ប្រត្តិបត្តិការ" is a misspelling of "ប្រតិបត្តិការ" which means "transaction". Also, the word "ប្រត្តិបត្តិការ" is used twice which is redundant. The corrected translation is: "មានកំហុសមួយក្នុងការរក្សាទុកប្រវត្តិប្រតិបត្តិការទៅកាន់ %1។"
```

```
        <source>Exporting Successful</source>
        <translation>កំពុងនាំចេញដោយជោគជ័យ</translation>
    
YES
The translation uses the wrong word for "Exporting". It should be "ការនាំចេញ" instead of "កំពុងនាំចេញ". The word "កំពុង" indicates an action in progress, which is not conveyed in the original English text.

Correct translation: ការនាំចេញដោយជោគជ័យ
```

```
        <source>The transaction history was successfully saved to %1.</source>
        <translation>ប្រវត្តប្រត្តិបត្តិការបានទទួលជោគជ័យ និង​បានរក្សាទុក %1។</translation>
    
YES. The translation uses "and was saved to %1" instead of "was successfully saved to %1".
The correct translation is: ប្រវត្តប្រត្តិបត្តិការបានទទួលជោគជ័យ និង​រក្សាទុក %1។
```

```
        <source>No wallet has been loaded.
Go to File &gt; Open Wallet to load a wallet.
- OR -</source>
        <translation>មិនមានកាបូបអេឡិចត្រូនិចបង្ហាញ។
ចូលឯកសារ‍»បើកកាបូបអេឡិចត្រូនិចដើម្បីបង្ហាញកាបូបមួយ
ឬ</translation>
    
YES. The translation uses Khmer script ("កាបូបអេឡិចត្រូនិច") for "wallet" in the first sentence but then switches to a mix of Chinese characters ("ចូល", "ឯកសារ", "បើក") and Khmer script ("កាបូបអេឡិចត្រូនិច", "បង្ហាញ", "មួយ") in the second sentence. This is inconsistent and uses non-Khmer characters where Khmer should be used.

The correct translation should be:
<translation>មិនមានកាបូបអេឡិចត្រូនិចត្រូវបានផ្ទុកទេ។
ចូលទៅឯកសារ > បើកកាបូបអេឡិចត្រូនិច ដើម្បីផ្ទុកកាបូបមួយ
- ឬ -</translation>
```

```
        <source>Create a new wallet</source>
        <translation>បង្កើតកាបូបចល័តថ្មីមួយ</translation>
    
YES, The translation is problematic as it uses Chinese characters rather than Khmer. The correct translation should be "បង្កើតកាបូបចល័តថ្មីមួយ".
```

```
        <source>Could not commit transaction</source>
        <translation>មិនបានធ្វើប្រត្តិបត្តិការ</translation>
    
YES - The translation is missing the word "transaction". The correct translation should be: មិនអាចធ្វើប្រតិបត្តិការបានទេ។
```

```
        <source>The wallet data was successfully saved to %1.</source>
        <translation>ទិន្ន័យកាបូបអេឡិចត្រូនិច ត្រូវបានរក្សាទុកដោយជោគជ័យ %1។</translation>
    
YES: The preposition "to" is missing in the translation.
Correct translation: ទិន្ន័យកាបូបអេឡិចត្រូនិច ត្រូវបានរក្សាទុកដោយជោគជ័យទៅ %1។
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>នេះជាកម្រៃប្រត្តិបត្តិការតូចបំផុត ដែលអ្នកទូរទាត់ (បន្ថែមទៅលើកម្រៃធម្មតា)​​  ដើម្បីផ្តល់អាទិភាពលើការជៀសវៀងការចំណាយដោយផ្នែក សម្រាប់ការជ្រើសរើសកាក់ដោយទៀងទាត់។</translation>
    
YES, The word "smallest" was mistranslated as "តូចបំផុត" (smallest) instead of "maximum". The correct translation should be "ធំបំផុត".
YES, នេះជាកម្រៃប្រតិបត្តិការធំបំផុតដែលអ្នកទូរទាត់ (បន្ថែមទៅលើកម្រៃធម្មតា) ដើម្បីផ្តល់អាទិភាពលើការជៀសវៀងការចំណាយដោយផ្នែក សម្រាប់ការជ្រើសរើសកាក់ដោយទៀងទាត់។
```

```
        <source>This is the transaction fee you may pay when fee estimates are not available.</source>
        <translation> អ្នកនឹងទូរទាត់ កម្រៃប្រត្តិបត្តិការនេះ នៅពេលណាដែល ទឹកប្រាក់នៃការប៉ាន់ស្មាន មិនទាន់មាន។</translation>
    
YES - The translation is grammatically incorrect and does not accurately convey the meaning of the source text. The phrase "អ្នកនឹងទូរទាត់ កម្រៃប្រត្តិបត្តិការនេះ" translates to "You will pay this transaction fee," which is not what the source text implies. The source text states that this is the fee that *may be paid*, not that it *will* be paid. Additionally, "នៅពេលណាដែល ទឹកប្រាក់នៃការប៉ាន់ស្មាន មិនទាន់មាន" translates to "when the estimated amount is not yet available," which is also not accurate.

A more accurate translation would be: "នេះគឺជាកម្រៃជើងសារប្រតិបត្តិការដែលអ្នកអាចនឹងបង់ នៅពេលដែលការប៉ាន់ស្មានកម្រៃមិនមានទេ។"
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>សេចក្តីប្រកាសអាសន្នៈ​ លេខសំម្ងាត់ត្រូវបានស្វែងរកឃើញនៅក្នុងកាបូបអេឡិចត្រូនិច​ {%s} ជាមួយនិងលេខសំម្ងាត់ត្រូវបានដាក់ឲ្យលែងប្រើលែងកើត</translation>
    
YES - The translation is problematic because the Khmer phrase "លេខសំម្ងាត់ត្រូវបានដាក់ឲ្យលែងប្រើលែងកើត" is redundant and awkward. A more natural and accurate translation would be "លេខសំងាត់ត្រូវបានបិទ".

Here's the corrected translation:

<translation>សេចក្តីប្រកាសអាសន្នៈ​ លេខសំងាត់ត្រូវបានស្វែងរកឃើញនៅក្នុងកាបូបអេឡិចត្រូនិច​ {%s} ជាមួយនិងលេខសំងាត់ត្រូវបានបិទ</translation>
```

```
        <source>%s is set very high!</source>
        <translation>%s ត្រូវបានកំណត់យ៉ាងខ្ពស់</translation>
    
YES, the translation uses a Chinese character ('被'). The correct translation should be: %s ត្រូវបានកំណត់ខ្ពស់ណាស់!
```

```
        <source>The preselected coins total amount does not cover the transaction target. Please allow other inputs to be automatically selected or include more coins manually</source>
        <translation>ចំនួនសរុបនៃកាក់ដែលបានជ្រើសរើសជាមុនមិនគ្របដណ្តប់លើគោលដៅប្រតិបត្តិការទេ។ សូមអនុញ្ញាតឱ្យធាតុបញ្ចូលផ្សេងទៀតត្រូវបានជ្រើសរើសដោយស្វ័យប្រវត្តិ ឬបញ្ចូលកាក់បន្ថែមទៀតដោយហត្ថកម្</translation>
    
YES: The translation is problematic because the last word "ហត្ថកម្" is incomplete and appears to be a truncation of the intended word. The correct translation should complete the word.
ចំនួនសរុបនៃកាក់ដែលបានជ្រើសរើសជាមុនមិនគ្របដណ្តប់លើគោលដៅប្រតិបត្តិការទេ។ សូមអនុញ្ញាតឱ្យធាតុបញ្ចូលផ្សេងទៀតត្រូវបានជ្រើសរើសដោយស្វ័យប្រវត្តិ ឬបញ្ចូលកាក់បន្ថែមទៀតដោយហត្ថកម្ម
```

```
        <source>Done loading</source>
        <translation>បានធ្វើរួចរាល់ហើយ កំពុងបង្ហាញ</translation>
    
YES, The translation is inaccurate. The original English phrase "Done loading" means that a process has finished loading. The Khmer translation "បានធ្វើរួចរាល់ហើយ កំពុងបង្ហាញ" means "Done already, showing." This is not the correct meaning and is grammatically awkward. The term "loading" is not represented in the translation.

NO
```

```
        <source>Failed to verify database</source>
        <translation>មិនបានជោគជ័យក្នុងការបញ្ចាក់ មូលដ្ឋានទិន្នន័យ</translation>
    
YES, The translation is problematic because it uses "unsuccessful" instead of "failed" which changes the meaning of the sentence. The correct translation should be:
<translation>បរាជ័យក្នុងការបញ្ជាក់មូលដ្ឋានទិន្នន័យ</translation>
```

```
        <source>Insufficient funds</source>
        <translation>មូលនិធិមិនគ្រប់គ្រាន់</translation>
    
YES - The translation is incorrect and nonsensical in the context of Bitcoin. The word "មូលនិធិ" translates to "foundation capital" or "initial capital" in English, which is not relevant to Bitcoin transactions. The correct translation for "Insufficient funds" in the context of Bitcoin would be related to the balance or the amount of cryptocurrency.

Correct translation: ទឹកប្រាក់មិនគ្រប់គ្រាន់
```

```
        <source>Signing transaction failed</source>
        <translation>ប្រត្តិបត្តការចូល មិនជោគជ័យ</translation>
    
YES - The translation is too literal and does not accurately convey the meaning of the original English phrase. "Signing transaction failed" refers to an error in the process of signing a Bitcoin transaction. The provided Khmer translation "ប្រត្តិបត្តការចូល មិនជោគជ័យ" literally means "Login operation failed," which is a different context.

Correct translation: ការចុះហត្ថលេខាលើប្រតិបត្តិការបានបរាជ័យ
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>ប្រត្តិបត្តិការមានខ្សែចង្វាក់រងចាំដើម្បីធ្វើការផ្ទៀងផ្ទាត់វែង</translation>
    
YES. The translation is completely inaccurate and does not convey the meaning of the original English text. The original text talks about a wallet avoiding paying a minimum relay fee, whereas the translation talks about a "chain of operations waiting for a long verification."

NO.
```
</details>
