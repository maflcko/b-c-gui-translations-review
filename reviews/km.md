# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>km</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bkm%5D%20low%20quality)


```
        <source>Close</source>
        <translation>បិទ(l)</translation>
    
YES
The inclusion of "(l)" after "បិទ" is incorrect unless it is meant to indicate a keyboard accelerator, which is not clear from the source. The English source does not include any such indication.

Correct translation:
បិទ
```

```
        <source>Choose</source>
        <translation>ជ្រើសរើស(h)</translation>
    
YES
The translation "ជ្រើសរើស(h)" incorrectly adds "(h)" at the end, which is not present in the source text and is unwarranted. The correct translation should be:

Correct translation:
ជ្រើសរើស
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comma បំបែកឯកសារ</translation>
    
YES
The translation is inaccurate. "Comma បំបែកឯកសារ" literally means "Comma split file", but it's not how "Comma separated file" or "CSV file" is referred to in Khmer. It should properly use the Khmer wording that corresponds to 'comma-separated values' or explicitly reference the CSV format.

Correct translation:
ឯកសារ​ដែល​បំបែក​ដោយ​សញ្ញា​ក្បៀស (CSV)
```

```
        <source>Sending addresses - %1</source>
        <translation>កំពុងផ្ញើអាសយដ្ឋាន%1</translation>
    
YES
There is a missing space between the word "អាសយដ្ឋាន" and "%1" in the translation. In Khmer, as in English, there should be a space to separate the word and the format specifier.

Correct translation:
កំពុងផ្ញើអាសយដ្ឋាន %1
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>បញ្ចូលឃ្លាសម្ងាត់សំរាប់កាបូប។ &lt;br/&gt;សូមប្រើឃ្លាសម្ងាត់ពី&lt;b&gt;១០ តួ&lt;/b&gt;ឬ&lt;b&gt;ច្រើនជាងនេះ, ៨ពាក្យឬច្រើនជាងនេះ&lt;/b&gt;។.</translation>
    
YES
The translation is inaccurate and awkward. It combines numbers and words requirement in a confusing way and does not accurately render the structure of the English phrase. There's also an unnecessary period at the end. The HTML formatting is preserved, but the clarity is lost.

Correct translation:
បញ្ជូលពាក្យសម្ងាត់ថ្មីសម្រាប់កាបូប។ &lt;br/&gt;សូមប្រើពាក្យសម្ងាត់មាន&lt;b&gt;១០ តួអក្សរឬច្រើនជាងនេះដែលចៃដន្យ&lt;/b&gt; ឬ&lt;b&gt;៨ពាក្យឬច្រើនជាងនេះ&lt;/b&gt;។
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>បំលែងលេខសំម្ងាត់សម្រាប់កាបូបអេឡិចត្រូនិច របស់អ្នកឲ្យទៅជាភាសាកុំព្យូទ័រ </translation>
    
YES
The translation is inaccurate. The English source means "Encrypt the private keys that belong to your wallet", but the Khmer translation says "Convert the password for your electronic wallet into computer language", which is not correct.

Correct translation:
អ៊ិនគ្រិបកូនសោឯកជនដែលជាផ្នែកមួយនៃកាបូបរបស់អ្នក
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>ធ្វើការបញ្ចាក់សារ ដើម្បីធានាថាសារទាំំងនោះបានចុះហត្ថលេខា ជាមួយអាសយដ្ខានប៊ីតខញ</translation>
    
YES
There are some issues:
1. There's a typo in "ទាំំង" — it should be "ទាំង".
2. There is a spacing issue: extra space after "ធ្វើការបញ្ចាក់សារ".
3. The translation of "ប៊ីតខញ" is incorrect for "Bitcoin" (correct spelling is "ប៊ីតខញ" or more commonly "Bitcoin" itself in Khmer script).
4. The translation omits "the specified Bitcoin addresses" nuance; it should clarify "the specified" (បានចុះហត្ថលេខាជាមួយអាសយដ្ឋាន Bitcoin ដែលបានបញ្ជាក់).

Correct translation:
ធ្វើការបញ្ជាក់សារ ដើម្បីធានាថាសារទាំងនោះបានចុះហត្ថលេខាជាមួយអាសយដ្ឋាន Bitcoin ដែលបានបញ្ជាក់
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>បង្ហាញប្រត្តិបត្តិការប៊ីតខញដែលបានចុះហត្ថលេខាដោយផ្នែក</translation>
    
YES
The translation uses the word "បង្ហាញ" which means "Show" or "Display" instead of "Load", which is "ផ្ទុក" in Khmer. Also, there is a typo in "ប្រត្តិបត្តិការ" (should be "ប្រតិបត្តិការ" – only one ត).

Correct translation:
ផ្ទុកប្រតិបត្តិការប៊ីតខញដែលបានចុះហត្ថលេខាដោយផ្នែក
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>បង្ហាញប្រត្តិបត្តិការប៊ីតខញដែលបានចុះហត្ថលេខាដោយផ្នែកពីក្ដារតម្រៀប</translation>
    
YES
The translation inaccurately uses "បង្ហាញ" ("show") instead of "ផ្ទុក" ("load"), mistranslates "clipboard" as "ពីក្ដារតម្រៀប" ("from the arrangement board" or "from layout board", which is incorrect for "clipboard"), and "ប្រត្តិបត្តិការប៊ីតខញ" contains a typo: "ប៊ីតខញ" should be "ប៊ីតខញ" (but even this is not commonly used for "Bitcoin" in Khmer; "ប៊ីតខញ" or "ប៊ីតកូអ៊ីន" could be used). The translation does not accurately render the source meaning.

Correct translation:
ផ្ទុកប្រតិបត្តិការ Bitcoin ដែលបានចុះហត្ថលេខាដោយផ្នែកពីកន្លែងចម្លង (clipboard)
```

```
        <source>Open a bitcoin: URI</source>
        <translation>បើកប៊ីតខញមួយៈ URl</translation>
    
YES
The translation incorrectly renders "bitcoin" as "ប៊ីតខញ" (probably a typo; should be "ប៊ីតខញ" or, more commonly, "ប៊ីតកូអ៊ីន" for "Bitcoin" in Khmer) and "URI" as "URl" (typo; should be "URI" in Latin script, not "URl"). The format of the colon is also incorrect.

Correct translation:
បើក URI របស់ bitcoin
or, if rendering in Khmer:
បើក URI របស់ប៊ីតកូអ៊ីន

Alternatively, maintaining the original order:
បើក bitcoin: URI
```

```
        <source>Migrate Wallet</source>
        <translation>កាបូបMigrate</translation>
    
YES
The translation is problematic as it does not translate "Migrate Wallet" into Khmer, instead leaving "Migrate" in English attached to the Khmer for "Wallet" (កាបូប). This is not idiomatic and can be confusing for Khmer speakers.

Correct translation:
បោះប្ដូរកាបូប
or
ផ្លាស់ប្ដូរកាបូប

Either are acceptable for "Migrate Wallet".
```

```
        <source>Show</source>
        <translation>របៀប(S)</translation>
    
YES
The translation "របៀប(S)" is inaccurate. "របៀប" means "method" or "procedure" and does not convey the meaning of "Show". The inclusion of "(S)" is also not standard in Khmer UI translations and appears erroneous.

Correct translation:
បង្ហាញ
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>កាបូបអេឡិចត្រូនិចគឺ&lt;b&gt;ត្រូវបានបំលែងជាកូដ&lt;/b&gt;និងបច្ចុប្បន្ន&lt;b&gt;ត្រូវបានចាក់សោរ&lt;/b&gt;</translation>
    
YES
The translation is inaccurate. The English source states that the wallet is "encrypted" and "currently unlocked", but the Khmer translation says it is "encrypted" and "currently locked" ("ត្រូវបានចាក់សោរ" means "locked", not "unlocked").

Correct translation:
កាបូបអេឡិចត្រូនិចនេះបាន&lt;b&gt;បំលែងជាកូដ&lt;/b&gt; និង​បច្ចុប្បន្ន&lt;b&gt;បានបើកសោ&lt;/b&gt;
```

```
        <source>Can vary +/- %1 satoshi(s) per input.</source>
        <translation>អាច +/- %1 satoshi(s)ច្រើនក្នុងការបញ្ជូលមួយ។</translation>
    
YES
The translation is understandable but has some issues:
- The format specifier (%1) is correctly copied over.
- There should be a space before "satashi(s)" for clarity.
- The word "ច្រើន" means "many", which adds unintended meaning—it's not in the source.
- The translation doesn't accurately reflect "per input" ("ក្នុងការបញ្ជូលមួយ" is wordy and unclear).
- "satashi(s)" is transliterated in Latin script while Khmer users might use either, but consistency is best (សាតូស៊ី is common in Khmer).

Correct translation:
អាចផ្លាស់ប្តូរ +/- %1 សាតូស៊ី ក្នុងមួយការបញ្ចូល។
```

```
        <source>Migrate Wallet</source>
        <translation>កាបូបMigrate</translation>
    
YES
The translation is problematic as it does not translate "Migrate Wallet" into Khmer, instead leaving "Migrate" in English attached to the Khmer for "Wallet" (កាបូប). This is not idiomatic and can be confusing for Khmer speakers.

Correct translation:
បោះប្ដូរកាបូប
or
ផ្លាស់ប្ដូរកាបូប

Either are acceptable for "Migrate Wallet".
```

```
        <source>Open wallet failed</source>
        <translation>បើកកាបូបអេឡិចត្រូនិច មិនជៅគជ័យ</translation>
    
YES
The translation contains a typo and the meaning is slightly off. The word "មិនជូវគជ័យ" is a misspelling; it should be "មិនជោគជ័យ" to mean "failed". Also, adding "អេឡិចត្រូនិច" unnecessarily makes it more specific ("electronic"), though "កាបូប" is the accurate word for "wallet" in the Bitcoin context.

Correct translation:
បើកកាបូបមិនជោគជ័យ
```

```
        <source>Opening Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the open wallet progress window which indicates to the user which wallet is currently being opened.</extracomment>
        <translation>កាបូបការបើកកាបូប&lt;b&gt;%1&lt;/b&gt;...</translation>
    
YES
The translation redundantly repeats the word "កាបូប" (wallet) two times: "កាបូបការបើកកាបូប", which is erroneous. The correct phrasing should be less redundant and more natural in Khmer. Also, the ellipsis should ideally be the Khmer/Unicode ellipsis (…), matching the source.

Correct translation:
កំពុងបើកកាបូប &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Encrypt Wallet</source>
        <translation>បំលែងកាបូបអេឡិចត្រនិចទៅជាកូដ</translation>
    
YES
The translation is problematic. The source "Encrypt Wallet" should be translated in a way that conveys "to encrypt (make secure by encryption) the wallet," not "convert the wallet into code" (which is what the current translation suggests).

Correct translation:
អ៊ិនគ្រិបកាបូប (or: អ៊ិនគ្រិបកាបូបអេឡិចត្រូនិក)

Alternatively, a more formal translation:
អ៊ិនគ្រិបទៅលើកាបូប

The term "បំលែង...ទៅជាកូដ" means "convert...into code," which is not accurate for "encrypt."
```

```
        <source>Address</source>
        <translation>អាសយដ្ឋានបញ្ចូនថ្មី</translation>
    
YES
The translation "អាសយដ្ឋានបញ្ចូនថ្មី" means "new receiving address," which introduces additional meaning ("new receiving") not present in the original single word "Address." This is therefore not an accurate translation and could be misleading in the context.

Correct translation:
អាសយដ្ឋាន
```

```
        <source>Last block time</source>
        <translation>ពេវេលាប្លុកជុងក្រោយ</translation>
    
YES
There is a typo: "ពេវេលា" should be "ពេលវេលា" (correct spelling for "time" in Khmer). Also, the translation "ប្លុកជុងក្រោយ" misses the standard spelling: "ចុងក្រោយ" is correct for "last". The format should also be clean without stray spacing.

Correct translation:
ពេលវេលាប្លុកចុងក្រោយ
```

```
        <source>Open bitcoin URI</source>
        <translation>បើកប៊ីតខញ​URl</translation>
    
YES
The translation has several issues: "URl" should be "URI" (uppercase 'I'), and the translation for "bitcoin" is phonetically rendered as "ប៊ីតខញ", but it should ideally be "ប៊ីតកូអ៊ីន" to better represent "Bitcoin" in Khmer. There is also an unnecessary Khmer diacritic/space between "ប៊ីតខញ" and "URI".

Correct translation:
បើក URI របស់ប៊ីតកូអ៊ីន
```

```
        <source>URI:</source>
        <translation>URl:</translation>
    
YES
The translation is incorrect: "URl" contains a lowercase "l" instead of an uppercase "I", and this is not a proper Khmer translation; it just transliterates the abbreviation without converting to Khmer script. Also, in the Khmer language, the English "URI" is either kept as-is, or can be optionally explained further, but at minimum, it should accurately preserve "URI".

Correct translation:
URI៖
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>ថតចម្លងអាសយដ្ឋាណពីក្ដារតម្រៀប</translation>
    
YES
The translation reverses the intended action. "Paste address from clipboard" means to insert or paste, not copy. The translation "ថតចម្លងអាសយដ្ឋាណពីក្ដារតម្រៀប" means "Copy address from clipboard," which is incorrect.

Correct translation:
បិទភ្ជាប់អាសយដ្ឋានពីក្ដារតម្រៀប
```

```
        <source>Start %1 on system login</source>
        <translation>ចាប់ផ្តើម %1 ទៅលើការចូលប្រព័ន្ធ(S)</translation>
    
YES
The translation is understandable but contains issues: 
- "(S)" is not appropriate or necessary in Khmer; it appears to be a stray character or a mis-translation.
- The preposition "ទៅលើ" (to/on) is awkward in this context; "នៅពេលចូលប្រព័ន្ធ" (when logging into the system) is clearer.
- There is an unnecessary space before "(S)".

Correct translation:
ចាប់ផ្តើម %1 នៅពេលចូលប្រព័ន្ធ
```

```
        <source>Number of script verification threads</source>
        <translation>ចំនួនscript  threadsផ្ទៀងផ្ទាត់</translation>
    
YES
The translation is problematic for several reasons:
1. "script" and "threads" are left untranslated, which may confuse users not familiar with English or technical terms.
2. The order of words is awkward and not natural in Khmer.
3. There's no space between "script" and "threads," making it visually confusing.
4. The translation does not clearly convey the meaning of "Number of script verification threads."

Correct translation:
ចំនួនខ្សែស្រឡាយ (threads) សម្រាប់ផ្ទៀងផ្ទាត់ស្គ្រីប

This version translates "Number of script verification threads" accurately and in natural Khmer, keeping the technical term "threads" in parentheses for clarity since it's a technical Bitcoin context.
```

```
        <source>Port:</source>
        <translation>រុនដោត</translation>
    
YES
The translation "រុនដោត" is incorrect. It is a phonetic misspelling and has no meaning in Khmer, nor does it convey the meaning of "Port" in the context of network or communication ports.

Correct translation:
ផត:

Alternatively, you can use:
ច្រក:

("ផត" is the Khmer transliteration for the English "Port", commonly used in technical contexts. "ច្រក" means passage or port, and sometimes is used in technical translations as well.)
```

```
        <source>Third-party URLs (e.g. a block explorer) that appear in the transactions tab as context menu items. %s in the URL is replaced by transaction hash. Multiple URLs are separated by vertical bar |.</source>
        <translation>URL ភាគីទីបី (ឧ. ប្លុករុករក) ដែលបង្ហាញក្នុងផ្ទាំងប្រតិបត្តិការជាធាតុម៉ឺនុយបរិបទ។ %sនៅក្នុង URL ត្រូវបានជំនួសដោយhashប្រតិបត្តិការ។ URLs ច្រើនត្រូវបានបំបែកដោយរបារបញ្ឈរ |។</translation>
    
YES
There are minor issues with spacing and loanword usage. Specifically:
- There is no space between "%s" and "នៅក្នុង" (should be "%s នៅក្នុង URL …").
- "hashប្រតិបត្តិការ" should be written as "hash ប្រតិបត្តិការ" for clarity.
- More natural Khmer phrasing can be used for "block explorer" ("ប្លុករុករក" is a literal, possibly understandable, but a more standard Khmer rendering for technical documentation may exist).

Correct translation:
URL ភាគីទីបី (ឧ. កម្មវិធីស្វែងរកប្លុក) ដែលបង្ហាញក្នុងផ្ទាំងប្រតិបត្តិការជាធាតុម៉ឺនុយបរិបទ។ %s នៅក្នុង URL នឹងត្រូវបានជំនួសដោយ hash ប្រតិបត្តិការ។ URLs ច្រើនត្រូវបានបំបែកដោយរបារបញ្ឈរ |។
```

```
        <source>The configuration file is used to specify advanced user options which override GUI settings. Additionally, any command-line options will override this configuration file.</source>
        <extracomment>Explanatory text about the priority order of instructions considered by client. The order from high to low being: command-line, configuration file, GUI settings.</extracomment>
        <translation>ការរៀបចំរចនាសម្ពន្ធ័ឯកសារ ត្រូវបានប្រើសម្រាប់អ្នកដែលមានបទពិសោធន៏ ក្នុងរៀបចំកែប្រែផ្នែកក្រាហ្វិកខាងមុននៃសុសវែ។ បន្ថែ​មលើនេះទៀត  កាសរសេរបន្ថែមកូដ វានឹងធ្វើឲ្យមានការកែប្រែឯការសារនេះ។</translation>
    
YES
The Khmer translation is inaccurate and contains multiple issues:

- It mistranslates "configuration file" as "ការរៀបចំរចនាសម្ពន្ធ័ឯកសារ", which is wordy and unnatural.
- It introduces unrelated concepts ("for experienced users," "GUI as 'សុសវែ'", which seems a faulty transliteration).
- The structure and intended meaning (about override priority: command-line > config file > GUI) is lost.
- Also, there is a spelling/formatting error with "បន្ថែ​មលើនេះទៀត" (odd extra space and misspelling).

Correct translation:
ឯកសារកំណត់រចនាសម្ព័ន្ធត្រូវបានប្រើសម្រាប់បញ្ជាក់ជម្រើសដើម្បីជំនួសការកំណត់នៅក្នុងកម្មវិធីផ្ទាល់។ លើសពីនេះទៅទៀត ជម្រើសបញ្ជា command-line មួយណាក៏បាននឹងជំនួសការកំណត់នៅក្នុងឯកសារកំណត់រចនាសម្ព័ន្ធនេះ។
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>សរុបប្រត្តឹបត្តិការដែលមិនទាន់បានបញ្ចាក់ និង រាប់ចំពោះសមតុល្យដែលមានទឹកប្រាក់សម្រាប់សំណាយ</translation>
    
YES
There are spelling errors and inaccuracies in the Khmer translation. For instance, "ប្រត្តឹបត្តិការ" is incorrect; it should be "ប្រតិបត្តិការ". The phrase "រាប់ចំពោះសមតុល្យដែលមានទឹកប្រាក់សម្រាប់សំណាយ" is awkward and doesn't accurately convey the English meaning; it should indicate that the transactions are not yet included in the spendable balance.

Correct translation:
សរុបប្រតិបត្តការដែលមិនទាន់ត្រូវបានបញ្ជាក់ ហើយមិនទាន់រាប់បញ្ចូលក្នុងសមតុល្យដែលអាចចំណាយបានទេ
```

```
        <source>Unknown error processing transaction.</source>
        <translation> ពុំស្គាល់ប្រត្តិបត្តិការកំពុងដំណើរការជួបបញ្ហា។</translation>
    
YES
There is an unnecessary leading whitespace in the translation. Also, the translation could be more faithful to the original meaning, which is "Unknown error processing transaction" (an error of unknown type occurred while processing the transaction). The translation "ពុំស្គាល់ប្រត្តិបត្តិការ..." reads as "Unknown transaction is encountering problems", which shifts the meaning.

Correct translation:
មិនស្គាល់កំហុសក្នុងការដំណើរការប្រាក់ប្រតិបត្តិការ។
```

```
        <source>(But no wallet is loaded.)</source>
        <translation>(ប៉ុន្តែគ្មានកាបូបត្រូវបានទាញទេ។ )</translation>
    
YES
There is an unnecessary space before the closing parenthesis in the translation.

Correct translation:
(ប៉ុន្តែគ្មានកាបូបត្រូវបានទាញទេ។)
```

```
        <source>Current number of transactions</source>
        <translation>បច្ចុប្បន្នភាពចំនួនប្រត្តិបត្តិការ</translation>
    
YES
The translation is inaccurate. The source "Current number of transactions" refers specifically to the "number" (count) of transactions at the current time. However, the Khmer translation "បច្ចុប្បន្នភាពចំនួនប្រត្តិបត្តិការ" means "the current status of the number of transactions," which is unnecessarily wordy and shifts the meaning to "current status" or "update" instead of just "current number".

Correct translation:
ចំនួនប្រតិបត្តិការបច្ចុប្បន្ន

Explanation: This means "current number of transactions" directly and is clear and concise.
```

```
        <source>Last block time</source>
        <translation>ពេវេលាប្លុកជុងក្រោយ</translation>
    
YES
There is a typo: "ពេវេលា" should be "ពេលវេលា" (correct spelling for "time" in Khmer). Also, the translation "ប្លុកជុងក្រោយ" misses the standard spelling: "ចុងក្រោយ" is correct for "last". The format should also be clean without stray spacing.

Correct translation:
ពេលវេលាប្លុកចុងក្រោយ
```

```
        <source>1 day</source>
        <translation>1 ថ្ងៃ(a)</translation>
    
YES
The translation "1 ថ្ងៃ(a)" erroneously adds "(a)" after the Khmer word for day ("ថ្ងៃ"), making it incorrect and unnatural. The correct translation should be simply: "1 ថ្ងៃ"

Correct translation:
1 ថ្ងៃ
```

```
        <source>Ctrl+N</source>
        <translation>Ctrl+T</translation>
    
YES
The translation is incorrect. The source "Ctrl+N" indicates the keyboard shortcut using the "N" key, while the translation changes it to "Ctrl+T". This alters the meaning, which could confuse users.

Correct translation:
Ctrl+N
```

```
        <source>Executing command using "%1" wallet</source>
        <translation>ប្រត្តិបត្តិបញ្ចារដោយប្រើ​  ៉​%1​​  ៉ កាបូបអេឡិចត្រូនិច</translation>
    
YES
There are multiple issues with the translation:
1. There are unnecessary stray and double spaces before and after the %1 placeholder.
2. The use of "៉​" (KHMER SIGN MUUSIKATOAN) around %1 is incorrect and should not be present.
3. The translation for "wallet" is acceptable as "កាបូបអេឡិចត្រូនិច", but "Executing command" is mistranslated as "ប្រត្តិបត្តិបញ្ចា" (which is also a typo; likely meant "បញ្ជា"=command) and does not cleanly capture "executing".

Correct translation:
ប្រតិបត្តិបញ្ជា​ដោយប្រើកាបូបអេឡិចត្រូនិច "%1"
```

```
        <source>Copy URI</source>
        <translation>ថតចម្លង RUl</translation>
    
YES
The translation incorrectly copies "RUl" instead of "URI", and the Khmer phrase for 'Copy' is also awkward. In Khmer, "Copy URI" should be:

Correct translation:
ថតចម្លង URI
```

```
        <source>Copy URI</source>
        <translation>ថតចម្លង RUl</translation>
    
YES
The translation incorrectly copies "RUl" instead of "URI", and the Khmer phrase for 'Copy' is also awkward. In Khmer, "Copy URI" should be:

Correct translation:
ថតចម្លង URI
```

```
        <source>Copy Address</source>
        <translation>ថតចម្លង និង អាសយដ្ឋាន</translation>
    
YES
The translation "ថតចម្លង និង អាសយដ្ឋាន" means "Copy and address," which is incorrect. The original English phrase is "Copy Address" (as in, copy the address), not "Copy and address." The conjunction "និង" ("and") should not be present.

Correct translation:
ថតចម្លងអាសយដ្ឋាន
```

```
        <source>Custom change address</source>
        <translation>ជ្រើសរើសផ្លាស់ប្តូរអាសយដ្ឋាន</translation>
    
YES
The translation reverses the meaning. "Custom change address" refers to a user-specified Bitcoin change address, but the translation means "Select change address" instead.

Correct translation:
អាសយដ្ឋានប្តូរដែលកំណត់ដោយផ្ទាល់ខ្លួន
```

```
        <source>You can increase the fee later (signals Replace-By-Fee, BIP-125).</source>
        <translation>អ្នកអាចបង្កើនកម្រៃពេលក្រោយ( សញ្ញា ជំនួសដោយកម្រៃ BIP-125)។</translation>
    
YES
There are spacing issues in the translation. There should not be a space before the parenthesis, and "សញ្ញាជំនួសដោយកម្រៃ BIP-125" should be inside the parentheses, with proper spacing. The translation is otherwise accurate.

Correct translation:
អ្នកអាចបង្កើនកម្រៃពេលក្រោយ (សញ្ញាជំនួសដោយកម្រៃ BIP-125)។
```

```
        <source>Confirm send coins</source>
        <translation>បញ្ចាក់​ ក្នុងការបញ្ចូនកាក់</translation>
    
YES
There is a minor spacing issue: there is an unnecessary space after "បញ្ចាក់​" (the Khmer word for "confirm"), which should be removed for correct formatting.

Correct translation:
បញ្ចាក់ក្នុងការបញ្ចូនកាក់
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>អាសយដ្ឋានប៊ីតខញក្នុងការបញ្ចូនការទូរទាត់ប្រាក់ទៅកាន់</translation>
    
YES
The translation contains a typographical error: "ប៊ីតខញ" should be "ប៊ីតខញ" is likely a misspelling of "ប៊ីតកុយន៍" (Bitcoin in Khmer). There is also some awkward phrasing and the translation may be more natural by restructuring the sentence.

Correct translation:
អាសយដ្ឋានប៊ីតកុយន៍សម្រាប់បញ្ចូនការទូទាត់ប្រាក់ទៅ

Explanation:
- Correctly spells "Bitcoin" as "ប៊ីតកុយន៍"
- More concise and natural phrasing
- No unnecessary whitespace
```

```
        <source>Enter the message you want to sign here</source>
        <translation>សូមបញ្ចូលពាក្យដែលអ្នកចង់បញ្ចូលនៅទីនេះ</translation>
    
YES
The translation does not accurately convey the meaning of "sign" in the context of Bitcoin (i.e., to digitally sign a message with a cryptographic key). The Khmer translation instead says "Please enter the word you want to enter here," which omits the crucial meaning of "to sign."

Correct translation:
សូមបញ្ចូលសារ​ដែល​អ្នកចង់ចុះហត្ថលេខា​នៅ​ទីនេះ

This version correctly communicates "sign" (ចុះហត្ថលេខា) in the context of digitally signing a message.
```

```
        <source>Reset all sign message fields</source>
        <translation>កែសម្រួលឡើងវិញគ្រប់សារហត្ថលេខាទាំងអស់ឡើងវិញ</translation>
    
YES
The translation is inaccurate. "កែសម្រួលឡើងវិញ" means "edit again" or "revise", and "សារហត្ថលេខា" refers to "signed message", but the order and repetition of "ឡើងវិញ" ("again") is awkward and redundant. The source means "reset" (to its initial/empty state), not "edit".

Correct translation:
កំណត់សារហត្ថលេខាទាំងអស់ឡើងវិញ
```

```
        <source>Click "Sign Message" to generate signature</source>
        <translation>ចុច ៉ហត្ថលេខា​ លើសារ​ ​ ៉​ដើម្បីបង្កើតហត្ថលេខា</translation>
    
YES
There are several issues:
1. The translation misuses quotation marks and repeats "signature" (ហត្ថលេខា) unnecessarily.
2. It incorrectly puts the word "signature" before "message" and does not clearly say to click the button "Sign Message".
3. There is inconsistent and stray spacing.

Correct translation:
ចុច "ផ្ទៀងផ្ទាត់សារ" ដើម្បីបង្កើតហត្ថលេខា

Alternatively, if the UI button label is "Sign Message", to ensure clarity:
ចុច "ហត្ថលេខាសារ" ដើម្បីបង្កើតហត្ថលេខា
```

```
        <source>The signature could not be decoded.</source>
        <translation>ការចុះហត្ថលេខានេះមិនគួរត្រូវបានបម្លែងទៅជាភាសាកុំព្យូទ័រទេ។</translation>
    
YES
The translation is inaccurate. The original English means "The signature could not be decoded." The Khmer translation states, "This signature should not be converted into computer language," which does not convey the same meaning.

Correct translation:
មិនអាចបកប្រែហត្ថលេខានេះបានទេ។
or
មិនអាចបកស្រង់ហត្ថលេខានេះបានទេ។
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comma បំបែកឯកសារ</translation>
    
YES
The translation is inaccurate. "Comma បំបែកឯកសារ" literally means "Comma split file", but it's not how "Comma separated file" or "CSV file" is referred to in Khmer. It should properly use the Khmer wording that corresponds to 'comma-separated values' or explicitly reference the CSV format.

Correct translation:
ឯកសារ​ដែល​បំបែក​ដោយ​សញ្ញា​ក្បៀស (CSV)
```

```
        <source>The transaction history was successfully saved to %1.</source>
        <translation>ប្រវត្តប្រត្តិបត្តិការបានទទួលជោគជ័យ និង​បានរក្សាទុក %1។</translation>
    
YES
The translation has a slight issue. The English says "The transaction history was successfully saved to %1." The Khmer translation says "ប្រវត្តប្រត្តិបត្តិការបានទទួលជោគជ័យ និង​បានរក្សាទុក %1។", which more literally means "The transaction history succeeded and was saved to %1." The addition of "បានទទួលជោគជ័យ" (succeeded) and "និង" (and) does not match the nuance of the original; it's unnecessarily splitting the meaning.

Correct translation:
ប្រវត្តិប្រតិបត្តិការបានរក្សាទុកដោយជោគជ័យនៅ %1។
```

```
        <source>Could not commit transaction</source>
        <translation>មិនបានធ្វើប្រត្តិបត្តិការ</translation>
    
YES
The translation does not accurately preserve the meaning of the original text. The original English "Could not commit transaction" implies an attempt was made to commit a transaction, but it failed. The Khmer translation "មិនបានធ្វើប្រត្តិបត្តិការ" translates to "did not perform transaction," which does not convey the sense of a failed attempt at committing. 

Correct translation:
មិនអាចប្តូរប្រតិបត្តិការ​បានទេ
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>សេចក្តីប្រកាសអាសន្នៈ​ លេខសំម្ងាត់ត្រូវបានស្វែងរកឃើញនៅក្នុងកាបូបអេឡិចត្រូនិច​ {%s} ជាមួយនិងលេខសំម្ងាត់ត្រូវបានដាក់ឲ្យលែងប្រើលែងកើត</translation>
    
YES
The translation is problematic for several reasons:
- "សេចក្តីប្រកាសអាសន្នៈ​" is more like "Emergency announcement" rather than "Warning" ("ការព្រមាន" would be more appropriate for "Warning").
- "លេខសំម្ងាត់" means "password", not "private key". The correct term for "private key" in Khmer should be "កូនសោផ្ទាល់ខ្លួន" or "សោឯកជន".
- The phrase "ជាមួយនិងលេខសំម្ងាត់ត្រូវបានដាក់ឲ្យលែងប្រើលែងកើត" is awkward, does not accurately convey "with disabled private keys", and is confusing.

Correct translation:
ការព្រមាន៖ រកឃើញកូនសោផ្ទាល់ខ្លួននៅក្នុងកាបូប{%s} ដែលបានបិទការប្រើកូនសោផ្ទាល់ខ្លួន
```

```
        <source>The preselected coins total amount does not cover the transaction target. Please allow other inputs to be automatically selected or include more coins manually</source>
        <translation>ចំនួនសរុបនៃកាក់ដែលបានជ្រើសរើសជាមុនមិនគ្របដណ្តប់លើគោលដៅប្រតិបត្តិការទេ។ សូមអនុញ្ញាតឱ្យធាតុបញ្ចូលផ្សេងទៀតត្រូវបានជ្រើសរើសដោយស្វ័យប្រវត្តិ ឬបញ្ចូលកាក់បន្ថែមទៀតដោយហត្ថកម្</translation>
    
YES  
The translation is incomplete: the word "ដោយហត្ថកម្" is cut off and unfinished at the end. This results in missing content and presents a potential issue for user understanding. The rest of the translation accurately reflects the source.

Correct translation:
ចំនួនសរុបនៃកាក់ដែលបានជ្រើសរើសជាមុនមិនគ្របដណ្តប់លើគោលដៅប្រតិបត្តិការទេ។ សូមអនុញ្ញាតឲ្យធាតុបញ្ចូលផ្សេងទៀតត្រូវបានជ្រើសរើសដោយស្វ័យប្រវត្តិ ឬបញ្ចូលកាក់បន្ថែមដោយដៃ
```

```
        <source>Done loading</source>
        <translation>បានធ្វើរួចរាល់ហើយ កំពុងបង្ហាញ</translation>
    
YES
The translation is inaccurate. The English "Done loading" means that the loading process is finished. The current Khmer translation "បានធ្វើរួចរាល់ហើយ កំពុងបង្ហាញ" translates back as "Already done, displaying" or "Done, showing," which incorrectly implies another action is happening ("displaying"). 

Correct translation:
បានផ្ទុករួចរាល់
```

```
        <source>Signing transaction failed</source>
        <translation>ប្រត្តិបត្តការចូល មិនជោគជ័យ</translation>
    
YES
The translation is inaccurate. "ប្រត្តិបត្តការចូល មិនជោគជ័យ" means "Login operation failed" or "Execution of entry failed," which does not correctly convey "Signing transaction failed". The term "Signing transaction" should refer to digitally signing a transaction, important in Bitcoin.

Correct translation:
ការចុះហត្ថលេខាលើប្រតិបត្តិការ បានបរាជ័យ
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>ប្រត្តិបត្តិការមានខ្សែចង្វាក់រងចាំដើម្បីធ្វើការផ្ទៀងផ្ទាត់វែង</translation>
    
YES
The translation is inaccurate and doesn't convey the intended meaning of the source. The source states that the wallet will avoid paying less than the minimum relay fee, but the translation is about transactions with chains waiting for confirmation.

Correct translation:
កាបូបនេះនឹងជៀសវាងការទូទាត់ថ្លៃសេវាដែលតិចជាងថ្លៃសេវាអប្បបរមាដែលអាចបញ្ជូនបន្តបាន។
```
</details>

Number of issues: 55.
