# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>km</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bkm%5D%20low%20quality)


```
        <source>Close</source>
        <translation>បិទ(l)</translation>
    
YES  
The translation includes an extraneous character "(l)" which is not part of the original English source and is unnecessary. It should simply translate "Close" without additional characters.  

Correct translation:  
បិទ
```

```
        <source>Choose</source>
        <translation>ជ្រើសរើស(h)</translation>
    
YES  
The translation includes an extraneous "(h)" which does not correspond to any part of the English source "Choose" and may confuse users. Also, since no format specifiers exist, they should not be added or changed.

Correct translation:  
ជ្រើសរើស
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comma បំបែកឯកសារ</translation>
    
YES  
The translation is partially in English ("Comma") and does not fully translate the phrase "Comma separated file" into Khmer. The phrase should be fully localized and convey the meaning "Comma separated file" as in the CSV file format.

Correct translation:  
"ឯកសារបំបែកដោយក្បៀស"
```

```
        <source>Sending addresses - %1</source>
        <translation>កំពុងផ្ញើអាសយដ្ឋាន%1</translation>
    
YES  
There should be a space between "អាសយដ្ឋាន" (address) and the format specifier "%1" to correctly match the original spacing and readability.

Correct translation:  
កំពុងផ្ញើអាសយដ្ឋាន %1
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>បញ្ចូលឃ្លាសម្ងាត់សំរាប់កាបូប។ &lt;br/&gt;សូមប្រើឃ្លាសម្ងាត់ពី&lt;b&gt;១០ តួ&lt;/b&gt;ឬ&lt;b&gt;ច្រើនជាងនេះ, ៨ពាក្យឬច្រើនជាងនេះ&lt;/b&gt;។.</translation>
    
YES  
The translation has minor issues in spacing and punctuation, and the structure can be improved for clarity and naturalness. Also, the English source uses “ten or more random characters” and “eight or more words” as two separate hints, but the Khmer translation combines them in a single phrase which lacks clear separation and proper spaces.

Correct translation:  
បញ្ចូលឃ្លាសម្ងាត់ថ្មីសម្រាប់កាបូប។&lt;br/&gt;សូមប្រើឃ្លាសម្ងាត់ដែលមាន&lt;b&gt;តួអក្សរពី១០ តួឡើងទៅ&lt;/b&gt; ឬ&lt;b&gt;ពាក្យពី ៨ ពាក្យឡើងទៅ&lt;/b&gt;។
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>បំលែងលេខសំម្ងាត់សម្រាប់កាបូបអេឡិចត្រូនិច របស់អ្នកឲ្យទៅជាភាសាកុំព្យូទ័រ </translation>
    
YES  
The translation is inaccurate and misleading. The source means "Encrypt the private keys that belong to your wallet," but the translation says "Convert the secret numbers for your electronic wallet into computer language," which implies conversion rather than encryption. It also has unnecessary extra spaces at the end.

Correct translation:  
បំលែងលេខគ្រាប់ផ្សេងៗដែលទាក់ទងនឹងកាបូបរបស់អ្នកឱ្យសុវត្ថិភាព (or) ពាក្យផ្សេងៗដូចជា:  
សូមបង្ហាញអត្ថន័យ "encrypt" មិនមែន "convert" ឬ "translate" ទេ។

A more accurate translation would be:  
បញ្ចូលសោរពុម្ពសម្ងាត់ចូលកញ្ចប់កូនសោឯកជនដែលជាកាបូបរបស់អ្នក  

Or a closer literal translation:  
ចេះបំលែងលេខសំងាត់ឯកជនដែលជាកម្មសិទ្ធិនៃកាបូបរបស់អ្នក  

If a formal technical translation is used:  
រឹតបន្តឹងលេខសំងាត់ឯកជនដែលជាកម្មសិទ្ធិនៃកាបូបរបស់អ្នក

Among these, the following is a good correct translation:  
បង្កើត​ការអ៊ិនគ្រីបលើលេខសំងាត់ឯកជន​ដែលជាកម្មសិទ្ធិនៃកាបូប​របស់អ្នក
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>ធ្វើការបញ្ចាក់សារ ដើម្បីធានាថាសារទាំំងនោះបានចុះហត្ថលេខា ជាមួយអាសយដ្ខានប៊ីតខញ</translation>
    
YES  
The translation contains multiple typographical errors and mistranslations:  
- "សារទាំំងនោះ" contains an extra middle sign "ំ" making it incorrect; it should be "សារទាំងនោះ" (all those messages).  
- "អាសយដ្ខាន" is a misspelling; the correct word for "address" is "អាសយដ្ឋាន".  
- "ប៊ីតខញ" is incorrect transliteration for "Bitcoin." The correct form is "ប៊ីតខន្ទ" or better "ប៊ីតខែន" (Bitcoin is often transliterated as ប៊ីតខែន in Khmer).  

A more accurate translation would be:  
"ធ្វើការបញ្ចាក់សារ ដើម្បីធានាថាសារទាំងនោះបានចុះហត្ថលេខាជាមួយអាសយដ្ឋានប៊ីតខែនដែលបានកំណត់"  

This translates as:  
"Verify messages to ensure those messages were signed with the specified Bitcoin addresses"  

Note: The source mentions "specified Bitcoin addresses," so adding "ដែលបានកំណត់" (that were specified) clarifies this.  

Hence:  
YES  
The translation has spelling mistakes and some mistranslated words. The correct translation is:  
"ធ្វើការបញ្ចាក់សារ ដើម្បីធានាថាសារទាំងនោះបានចុះហត្ថលេខាជាមួយអាសយដ្ឋានប៊ីតខែនដែលបានកំណត់"
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>បង្ហាញប្រត្តិបត្តិការប៊ីតខញដែលបានចុះហត្ថលេខាដោយផ្នែក</translation>
    
YES  
The translation contains a typo: "ប្រត្តិបត្តិការ" should be spelled "ប្រតិបត្តិការ" (the correct Khmer word for "transaction"). Also, "បង្ហាញ" means "display" or "show," but the source "Load" suggests "ផ្ទុក" which better fits loading a transaction. The phrase "Partially Signed Bitcoin Transaction" is translated as "ប្រតិបត្តិការប៊ីតខញដែលបានចុះហត្ថលេខាដោយផ្នែក," which is understandable but could be more natural. A clearer translation would be:

ផ្ទុកប្រតិបត្តិការប៊ីតខញដែលបានចុះហត្ថលេខាផ្នែក
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>បង្ហាញប្រត្តិបត្តិការប៊ីតខញដែលបានចុះហត្ថលេខាដោយផ្នែកពីក្ដារតម្រៀប</translation>
    
YES  
The translation contains spelling errors and a redundancy: "ប្រត្តិបត្តិការប៊ីតខញ" should be "ប្រតិបត្តិការប៊ីតខញ" ("Bitcoin transaction"), correcting the spelling of "ប្រតិបត្តិការ". Also, "ចុះហត្ថលេខា" means "sign," and "ដោយផ្នែក" means "by part," which is okay, but "ពីក្ដារតម្រៀប" is a misinterpretation of "clipboard." The correct term for "clipboard" in Khmer is "ក្តារចម្លង" or "ក្តារតម្រៀប" if used, but "ក្តារចម្លង" is more common.

A better translation would be:  
បញ្ចូលប្រតិបត្តិការប៊ីតខញដែលបានចុះហត្ថលេខាផ្នែក​ពី​ក្តារចម្លង

Note "Load" is better translated as "បញ្ចូល" (load/import) rather than "បង្ហាញ" (show/display).  

Correct translation:  
បញ្ចូលប្រតិបត្តិការប៊ីតខញដែលបានចុះហត្ថលេខាផ្នែក​ពី​ក្តារចម្លង
```

```
        <source>Open a bitcoin: URI</source>
        <translation>បើកប៊ីតខញមួយៈ URl</translation>
    
YES  
The translation contains a misspelling of "bitcoin" as "ប៊ីតខញ" instead of the correct Khmer transliteration "ប៊ីតខോയិន". Also, "URI" should be preserved as uppercase without adding or changing case, and "URl" has a lowercase "l" instead of uppercase "I" at the end.  

Correct translation:  
បើកប៊ីតខോയិនមួយៈ URI
```

```
        <source>Migrate Wallet</source>
        <translation>កាបូបMigrate</translation>
    
YES  
The translation mixes English and Khmer directly without proper translation. "Migrate Wallet" should be fully translated into Khmer with appropriate spacing. The word "Migrate" should be translated to Khmer equivalent ("ផ្លាស់ទី" or "បញ្ជូន") and "Wallet" should be translated as "កាបូប" or "កាបូប பண​ប័ណ្ណ". Also, there should be a space between words.

Correct translation:  
"ផ្លាស់ទីកាបូប"
```

```
        <source>Show</source>
        <translation>របៀប(S)</translation>
    
YES
The translation "របៀប(S)" means "Method" or "Way" followed by "(S)", which does not correspond to the English source "Show". The translation is inaccurate and seems to include an unnecessary format "(S)" that is not present in the source.

Correct translation:
បង្ហាញ
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>លេខសម្ងាត់ HD គឺ&lt;b&gt;ត្រូវបានបិទ&lt;/b&gt;</translation>
    
YES  
The Khmer translation uses "ត្រូវបានបិទ" which means "is turned off" or "is closed," but the source text says "disabled" in the context of key generation, which is better translated as "មិនដំណើរការ" or "មិនដំណើរការ" (not operational/disabled) for clarity. Also, there is no space before and after the HTML tags in the translation, but the translator omitted the spaces after "គឺ" and before "&lt;b&gt;". Adding a space after "គឺ" improves readability.

Correct translation:  
លេខសម្ងាត់ HD គឺ &lt;b&gt;មិនដំណើរការ&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>កាបូបអេឡិចត្រូនិចគឺ&lt;b&gt;ត្រូវបានបំលែងជាកូដ&lt;/b&gt;និងបច្ចុប្បន្ន&lt;b&gt;ត្រូវបានចាក់សោរ&lt;/b&gt;</translation>
    
YES
The translation incorrectly renders the meaning: "Wallet is <b>encrypted</b> and currently <b>unlocked</b>" means the wallet is encrypted and presently unlocked. However, the translation says "កាបូបអេឡិចត្រូនិចគឺ <b>ត្រូវបានបំលែងជាកូដ</b> និង បច្ចុប្បន្ន <b>ត្រូវបានចាក់សោរ</b>", where "ត្រូវបានចាក់សោរ" means "locked" instead of "unlocked."

Correct translation:
កាបូបអេឡិចត្រូនិចគឺ&lt;b&gt;បានបំលែងជាកូដ&lt;/b&gt; និងកំពុង&lt;b&gt;នៅស្ថានភាពបើកសោ&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>កាបូបអេឡិចត្រនិច&lt;b&gt;ត្រូវបានបំលែងជាកូដ&lt;/b&gt;និងបច្ចុប្បន្ន&lt;b&gt;ត្រូវបានចាក់សោរ&lt;/b&gt;</translation>
    
YES  
The translation incorrectly merges format tags with the surrounding text without spaces, making it harder to read and potentially causing rendering issues. Also, the phrase "បំលែងជាកូដ" literally means "converted to code," which is less appropriate than the commonly used "បានបញ្ញબ્ઇីកូដ" (encrypted) in Khmer for encryption context.

Correct translation:  
កាបូបអេឡិចត្រូនិច &lt;b&gt;បានបញ្ញេកូដ&lt;/b&gt; និងបច្ចុប្បន្ន &lt;b&gt;ត្រូវបានចាក់សោរ&lt;/b&gt;
```

```
        <source>Can vary +/- %1 satoshi(s) per input.</source>
        <translation>អាច +/- %1 satoshi(s)ច្រើនក្នុងការបញ្ជូលមួយ។</translation>
    
YES  
The translation has spacing issues and does not clearly convey the meaning. In particular, there should be a space after "satoshi(s)" and before "ច្រើន", and the meaning "vary +/- %1 satoshi(s) per input" is not clearly rendered. A clearer and more natural translation would be:

អាចផ្លាស់ប្តូរ +/- %1 satoshi(s) ក្នុងការបញ្ចូលមួយ។
```

```
        <source>Migrate Wallet</source>
        <translation>កាបូបMigrate</translation>
    
YES  
The translation mixes English and Khmer directly without proper translation. "Migrate Wallet" should be fully translated into Khmer with appropriate spacing. The word "Migrate" should be translated to Khmer equivalent ("ផ្លាស់ទី" or "បញ្ជូន") and "Wallet" should be translated as "កាបូប" or "កាបូប பண​ប័ណ្ណ". Also, there should be a space between words.

Correct translation:  
"ផ្លាស់ទីកាបូប"
```

```
        <source>Open wallet failed</source>
        <translation>បើកកាបូបអេឡិចត្រូនិច មិនជៅគជ័យ</translation>
    
YES  
The Khmer translation contains a misspelling: "មិនជៅគជ័យ" should be "មិនជោគជ័យ" (the correct term for "failed" or "unsuccessful").  
Correct translation:  
បើកកាបូបអេឡិចត្រូនិច មិនជោគជ័យ
```

```
        <source>Opening Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the open wallet progress window which indicates to the user which wallet is currently being opened.</extracomment>
        <translation>កាបូបការបើកកាបូប&lt;b&gt;%1&lt;/b&gt;...</translation>
    
YES
The translation contains redundant words and lacks proper spacing. The phrase "កាបូបការបើកកាបូប" is awkward and repetitive ("wallet opening wallet"). Also, there is no space before the <b> tag, and the ellipsis in Khmer should be the Unicode ellipsis character (…) rather than three dots.

Correct translation:
បើកកាបូប &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Encrypt the wallet. The wallet will be encrypted with a passphrase of your choice.</source>
        <translation>បំលែងកាបូបអេឡិចត្រូនិចជាកូដ។ កាបំលែងនេះ រួមជាមួយនឹងឃ្លាសម្ងាត់ដែលអ្នកអាចជ្រើសរើសបាន។</translation>
    
YES  
The translation contains errors and is not a faithful rendering of the original English. The original says "Encrypt the wallet. The wallet will be encrypted with a passphrase of your choice." but the translation says something closer to "Transform the electronic wallet into code. This transformation together with a passphrase that you can choose." The verb "Encrypt" is inaccurately translated as "transform," and the sentence structure is awkward and unclear.

Correct translation:  
កូដសម្ងាត់កាបូប។ កាបូបនឹងត្រូវបានបំលែងជាកូដសម្ងាត់ដោយប្រើពាក្យសម្ងាត់ដែលអ្នកជ្រើសរើស។
```

```
        <source>Encrypt Wallet</source>
        <translation>បំលែងកាបូបអេឡិចត្រនិចទៅជាកូដ</translation>
    
YES
The translation "បំលែងកាបូបអេឡិចត្រនិចទៅជាកូដ" means "convert electronic wallet to code," which is inaccurate for "Encrypt Wallet." A more precise translation would be:

"បង្ក្រះកាបូប" or "ព្រីបកាបូប" (depending on context)

A good corrected translation is:

"សុវត្ថិភាពកាបូប" or more explicitly,

"បង្កезпечកាបូប" (literally "encrypt wallet").

Correct translation:  
"បង្ក​ប្រសាប់​កាបូប"  
or simply  
"ផ្ទៀងផ្ទាត់កាបូប"  

Depending on established terminology, one common and clear translation would be:  
"បង្កាពុក​កាបូប" (which literally means "encrypt the wallet").
```

```
        <source>Address</source>
        <translation>អាសយដ្ឋានបញ្ចូនថ្មី</translation>
    
YES  
The English source word "Address" is a single, general term which could refer to a Bitcoin address or network address. The Khmer translation "អាសយដ្ឋានបញ្ចូនថ្មី" means "new sending address," which adds additional meaning not present in the original. This is inaccurate if the source is simply "Address."

Correct translation:  
អាសយដ្ឋាន
```

```
        <source>Last block time</source>
        <translation>ពេវេលាប្លុកជុងក្រោយ</translation>
    
YES  
The translation contains a typo: "ពេវេលាប្លុកជុងក្រោយ" should be "ពេលប្លុកចុងក្រោយ". The correct word for "Last" is "ចុង", not "ជុង", and the word "ពេល" (time) is misspelled as "ពេវេលា".

Correct translation:  
ពេលប្លុកចុងក្រោយ
```

```
        <source>Open bitcoin URI</source>
        <translation>បើកប៊ីតខញ​URl</translation>
    
YES  
The translation contains a typo and a formatting issue. "URl" should be correctly spelled as "URI" (matching the source exactly). Also, there is an extra space after "ប៊ីតខញ" (ប៊ីតខញ​ has a non-breaking space character) which is not necessary. The correct Khmer translation should maintain the correct technical term "URI" and avoid extra spacing:

Correct translation:  
បើកប៊ីតខញ URI
```

```
        <source>URI:</source>
        <translation>URl:</translation>
    
YES  
The translation uses a lowercase "l" instead of an uppercase "I" in "URI:". It should be "URI:" (យូអែល:) or simply "URI:" as an acronym. The current translation "URl:" is incorrect and looks like a typo.  

Correct translation:  
URI:
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>ថតចម្លងអាសយដ្ឋាណពីក្ដារតម្រៀប</translation>
    
YES
The Khmer translation uses "ថតចម្លង" which means "copy," not "paste." The correct verb for "paste" is "បិទបញ្ចូល" or simply "បិទ" in this context.

Correct translation:
បិទបញ្ចូលអាសយដ្ឋានពីក្ដារតម្រៀប
```

```
        <source>Start %1 on system login</source>
        <translation>ចាប់ផ្តើម %1 ទៅលើការចូលប្រព័ន្ធ(S)</translation>
    
YES  
There is a minor issue with the translation: the parenthetical "(S)" appears unnecessary and does not correspond to anything in the source text. Additionally, the phrasing "ទៅលើការចូលប្រព័ន្ធ" is awkward for "on system login." A more natural and clear phrasing would be "នៅពេលចូលប្រព័ន្ធ" which means "at the time of system login."

Correct translation:  
ចាប់ផ្តើម %1 នៅពេលចូលប្រព័ន្ធ
```

```
        <source>Number of script verification threads</source>
        <translation>ចំនួនscript  threadsផ្ទៀងផ្ទាត់</translation>
    
YES
The translation improperly mixes Khmer and English without appropriate spacing or Khmer equivalents, making it awkward and potentially confusing. Also, "script" and "threads" are left in English, which may be acceptable if no standard Khmer terms exist, but should be spaced properly. The phrase "verification" is translated as "ផ្ទៀងផ្ទាត់" correctly but is not spaced well from other words.

Correct translation with proper spacing:
ចំនួន script threads ផ្ទៀងផ្ទាត់

Or fully Khmer (if suitable terms exist for "script" and "threads"):
ចំនួនខ្សែប្រតិបត្តិការផ្ទៀងផ្ទាត់

(If "script" and "threads" are technical terms retained in English, at minimum ensure spaces around them.)
```

```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>កំណត់ចំនួនខ្សែស្រឡាយផ្ទៀងផ្ទាត់script ។ តម្លៃអវិជ្ជមានត្រូវគ្នាទៅនឹងចំនួនស្នូលដែលអ្នកចង់ចាកចេញពីប្រព័ន្ធដោយឥតគិតថ្លៃ។</translation>
    
YES
The translation contains some issues:
- The word "script" is untranslated and left in English script, which is inconsistent.
- The phrase "script verification threads" is translated as "ខ្សែស្រឡាយផ្ទៀងផ្ទាត់script", mixing Khmer and English without spacing or clarity.
- The phrase "leave free to the system" is translated as "ចាកចេញពីប្រព័ន្ធដោយឥតគិតថ្លៃ" which literally means "leave the system for free" but is not a natural way to say "leave free" (available) in Khmer.
- There is a spacing issue before the period after "script" (space before dot).

A better translation would be:

កំណត់ចំនួនខ្សែស្រឡាយផ្ទៀងផ្ទាត់ស្គ្រីប។ តម្លៃអវិជ្ជមានបង្ហាញពីចំនួនស្នូលដែលអ្នកចង់ទុកឲ្យប្រព័ន្ធប្រតិបត្តិការមានសេរីភាព។

This uses the transliteration "ស្គ្រីប" for "script" to be consistent and translates "leave free to the system" more naturally as "ទុកឲ្យប្រព័ន្ធប្រតិបត្តិការមានសេរីភាព" (leave for the operating system free).

Corrected translation:

កំណត់ចំនួនខ្សែស្រឡាយផ្ទៀងផ្ទាត់ស្គ្រីប។ តម្លៃអវិជ្ជមានបង្ហាញពីចំនួនស្នូលដែលអ្នកចង់ទុកឲ្យប្រព័ន្ធប្រតិបត្តិការមានសេរីភាព។
```

```
        <source>Port:</source>
        <translation>រុនដោត</translation>
    
YES  
The translation "រុនដោត" does not correctly translate the English word "Port" in this context (likely network port). The correct Khmer translation for "Port:" (as in network or communication port) is "កំពង់ផែ:" or simply "ព័រទ៍:" depending on the technical context. Since "រុនដោត" means "engine" or "motor," it is incorrect here.

Correct translation:  
កំពង់ផែ:
```

```
        <source>Third-party URLs (e.g. a block explorer) that appear in the transactions tab as context menu items. %s in the URL is replaced by transaction hash. Multiple URLs are separated by vertical bar |.</source>
        <translation>URL ភាគីទីបី (ឧ. ប្លុករុករក) ដែលបង្ហាញក្នុងផ្ទាំងប្រតិបត្តិការជាធាតុម៉ឺនុយបរិបទ។ %sនៅក្នុង URL ត្រូវបានជំនួសដោយhashប្រតិបត្តិការ។ URLs ច្រើនត្រូវបានបំបែកដោយរបារបញ្ឈរ |។</translation>
    
YES
There is a missing space between "%s" and "នៅក្នុង" in the translation, which should be corrected for clarity and formatting. Additionally, the English term "hash" is untranslated and could be transliterated or adapted for better understanding in Khmer.

Correct translation:
URL ភាគីទីបី (ឧ. ប្លុករុករក) ដែលបង្ហាញក្នុងផ្ទាំងប្រតិបត្តិការជាធាតុម៉ឺនុយបរិបទ។ %s នៅក្នុង URL ត្រូវបានជំនួសដោយ ហាសប្រតិបត្តិការ។ URL ច្រើនត្រូវបានបំបែកដោយរបារបញ្ឈរ |។
```

```
        <source>The configuration file is used to specify advanced user options which override GUI settings. Additionally, any command-line options will override this configuration file.</source>
        <extracomment>Explanatory text about the priority order of instructions considered by client. The order from high to low being: command-line, configuration file, GUI settings.</extracomment>
        <translation>ការរៀបចំរចនាសម្ពន្ធ័ឯកសារ ត្រូវបានប្រើសម្រាប់អ្នកដែលមានបទពិសោធន៏ ក្នុងរៀបចំកែប្រែផ្នែកក្រាហ្វិកខាងមុននៃសុសវែ។ បន្ថែ​មលើនេះទៀត  កាសរសេរបន្ថែមកូដ វានឹងធ្វើឲ្យមានការកែប្រែឯការសារនេះ។</translation>
    
YES
The translation is problematic because it does not accurately convey the meaning of the original English text. It includes phrases that do not correspond well to the source, such as "អ្នកដែលមានបទពិសោធន៏" ("experienced users") whereas the source refers generally to advanced user options, and the explanation about overriding GUI settings and command-line options is unclear or incorrect.

A more accurate translation would be:
ការ​ឯកសារ​ការរៀបចំ​រចនា​ត្រូវបានប្រើសម្រាប់កំណត់ជម្រើសអ្នកប្រើ​កម្រិតខ្ពស់​ដែលឆ្លើយតបទៅលើការកំណត់ GUI។ បន្ថែមលើនេះ ជម្រើស command-line ណាមួយ នឹងឆ្លើយតបទៅលើឯកសាររៀបចំរចនាសម្ពន្ធនេះ។
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>សរុបប្រត្តឹបត្តិការដែលមិនទាន់បានបញ្ចាក់ និង រាប់ចំពោះសមតុល្យដែលមានទឹកប្រាក់សម្រាប់សំណាយ</translation>
    
YES  
The translation contains spelling errors and awkward phrasing in Khmer. The word "ប្រត្តឹបត្តិការដែល" is incorrect and should be "ប្រត្តិបត្តិការដែល". Also, there is an extra space before "រាប់", and the phrase "រាប់ចំពោះសមតុល្យដែលមានទឹកប្រាក់សម្រាប់សំណាយ" is somewhat unclear and unnatural. A more accurate and natural translation would be:

សរុបនៃប្រតិបត្តិការដែលមិនទាន់បានបញ្ចាក់ និងមិនបានរាប់ចូលក្នុងសមតុល្យដែលអាចប្រើសម្រាប់សំណាយ

This translates back to:  
"Total of transactions that have not yet been confirmed and are not counted toward the spendable balance."
```

```
        <source>Unknown error processing transaction.</source>
        <translation> ពុំស្គាល់ប្រត្តិបត្តិការកំពុងដំណើរការជួបបញ្ហា។</translation>
    
YES  
The translation contains a leading space before the first word, which is a formatting issue. Also, the word "ប្រត្តិបត្តិការ" is misspelled (the second ត and the overall word formation are incorrect). The correct Khmer word for "transaction" is "ប្រតិបត្តិការ". The translation should also be more natural without the trailing full stop if the source uses one consistently. 

Correct translation:  
"ពុំស្គាល់កំហុសនៅពេលដំណើរការប្រតិបត្តិការ។"  

This means: "Unknown error occurred while processing the transaction." which conveys the original meaning more naturally.
```

```
        <source>Transaction has %1 unsigned inputs.</source>
        <translation>ប្រត្តិបត្តិការ​មាននៅសល់ %1 នៅពុំទាន់បានហត្ថលេខាធាតុចូល។</translation>
    
YES  
The Khmer translation has spelling errors and awkward phrasing that affect clarity and correctness. The word "ប្រត្តិបត្តិការ" should be "ប្រតិបត្តិការ" (correct spelling without the extra "្ត់"). The phrase "នៅសល់ %1" (remaining %1) is somewhat redundant when combined with "នៅពុំទាន់បាន" (not yet signed). Also, "ហត្ថលេខាធាតុចូល" is a literal but awkward translation of "unsigned inputs." A more natural phrase would be "ការបញ្ចូល %1 ដែលមិនទាន់បានហត្ថលេខា។" (inputs %1 that are not yet signed).

Correct translation:  
ប្រតិបត្តិការ​មាន %1 ការបញ្ចូល​ដែលមិនទាន់បានហត្ថលេខា។
```

```
        <source>Transaction still needs signature(s).</source>
        <translation>ប្រត្តិបត្តិការត្រូវការហត្ថលេខាមួយ (ឬ​ ច្រើន)។</translation>
    
YES  
There is a typographical error in the Khmer translation. The word "ប្រត្តិបត្តិការត្រូវការ" should be spelled "ប្រតិបត្តិការត្រូវការ" (remove the extra "្ត្" after "ត្រ"). The parentheses and spacing around "ឬ ច្រើន" are also slightly off; there is a non-breaking space character ("​") that should be a normal space.

Correct translation:  
ប្រតិបត្តិការត្រូវការហត្ថលេខា (ឬ ច្រើន)។
```

```
        <source>(But no wallet is loaded.)</source>
        <translation>(ប៉ុន្តែគ្មានកាបូបត្រូវបានទាញទេ។ )</translation>
    
YES
There is an extra space before the closing parenthesis in the translation. In Khmer, the phrase is correct but the spacing should match the source format exactly.

Correct translation:
(ប៉ុន្តែគ្មានកាបូបត្រូវបានទាញទេ។)
```

```
        <source>Current number of transactions</source>
        <translation>បច្ចុប្បន្នភាពចំនួនប្រត្តិបត្តិការ</translation>
    
YES  
The translation has a spelling mistake and a semantic imprecision. The word "ប្រត្តិបត្តិការ" should be "ប្រតិបត្តិការ" (without the extra ត្ character). Also, "បច្ចុប្បន្នភាព" means "current situation" or "update," but the intended meaning is simply "current number." A more accurate translation would be:

បរិមាណប្រតិបត្តិការ​បច្ចុប្បន្ន
```

```
        <source>Last block time</source>
        <translation>ពេវេលាប្លុកជុងក្រោយ</translation>
    
YES  
The translation contains a typo: "ពេវេលាប្លុកជុងក្រោយ" should be "ពេលប្លុកចុងក្រោយ". The correct word for "Last" is "ចុង", not "ជុង", and the word "ពេល" (time) is misspelled as "ពេវេលា".

Correct translation:  
ពេលប្លុកចុងក្រោយ
```

```
        <source>1 day</source>
        <translation>1 ថ្ងៃ(a)</translation>
    
YES
The translation contains an unnecessary and inappropriate "(a)" after "ថ្ងៃ," which is not correct in Khmer. The correct translation should simply be:

1 ថ្ងៃ
```

```
        <source>Ctrl+N</source>
        <translation>Ctrl+T</translation>
    
YES
The translation changes the keyboard shortcut from "Ctrl+N" to "Ctrl+T," which is incorrect because the shortcut should be preserved exactly as in the source.

Correct translation:
Ctrl+N
```

```
        <source>Executing command using "%1" wallet</source>
        <translation>ប្រត្តិបត្តិបញ្ចារដោយប្រើ​  ៉​%1​​  ៉ កាបូបអេឡិចត្រូនិច</translation>
    
YES  
The translation contains extra and misplaced spacing characters (notably double spaces and unusual spacing around "%1") and odd characters near the placeholders. Also, the original word "command" is translated as "បញ្ចារ" which is closer to "instruction" but acceptable; however, the spacing errors make the translation problematic.

Correct translation:  
ប្រតិបត្តិពាក្យបញ្ជាដោយប្រើ "%1" កាបូបអេឡិចត្រូនិច
```

```
        <source>Message:</source>
        <translation>សារ</translation>
    
YES
The translation is missing the colon ":" at the end, which is present in the source text and important for maintaining format and clarity.

Correct translation:
សារ:
```

```
        <source>Copy URI</source>
        <translation>ថតចម្លង RUl</translation>
    
YES  
The English abbreviation "URI" should be transliterated or kept consistent in Khmer script. Here, it is mistakenly written as "RUl" (with a lowercase L at the end), which looks like an error. Also, "URI" is usually pronounced as separate letters and should be transliterated accordingly, e.g., "URI" as "យូចអាយ" or simply "URI" in uppercase Latin letters.  

Correct translation:  
ថតចម្លង URI
```

```
        <source>Copy URI</source>
        <translation>ថតចម្លង RUl</translation>
    
YES  
The English abbreviation "URI" should be transliterated or kept consistent in Khmer script. Here, it is mistakenly written as "RUl" (with a lowercase L at the end), which looks like an error. Also, "URI" is usually pronounced as separate letters and should be transliterated accordingly, e.g., "URI" as "យូចអាយ" or simply "URI" in uppercase Latin letters.  

Correct translation:  
ថតចម្លង URI
```

```
        <source>Copy Address</source>
        <translation>ថតចម្លង និង អាសយដ្ឋាន</translation>
    
YES  
The translation "ថតចម្លង និង អាសយដ្ឋាន" means "Copy and Address," which is not a correct translation of "Copy Address." The conjunction " និង " (and) is incorrectly added. The correct translation should convey "Copy Address" as a single phrase, typically "ចម្លងអាសយដ្ឋាន" without extra spacing issues.

Correct translation:  
ចម្លងអាសយដ្ឋាន
```

```
        <source>Custom change address</source>
        <translation>ជ្រើសរើសផ្លាស់ប្តូរអាសយដ្ឋាន</translation>
    
YES  
The translation "ជ្រើសរើសផ្លាស់ប្តូរអាសយដ្ឋាន" means "Select change address" or "Choose change address" rather than "Custom change address." The English text implies a customized or user-defined change address, not simply selecting one.

A more accurate translation would be:  
អាសយដ្ឋានផ្លាស់ប្តូរតាមបំណង (meaning "Custom change address")
```

```
        <source>Clear All</source>
        <translation>សម្អាត ទាំងអស់</translation>
    
YES  
There is an extra space between the two words in the translation. In Khmer, "Clear All" is best translated as "សម្អាតទាំងអស់" without the space in between.

Correct translation:  
សម្អាតទាំងអស់
```

```
        <source>You can increase the fee later (signals Replace-By-Fee, BIP-125).</source>
        <translation>អ្នកអាចបង្កើនកម្រៃពេលក្រោយ( សញ្ញា ជំនួសដោយកម្រៃ BIP-125)។</translation>
    
YES  
There is a spacing issue: there should be a space before the opening parenthesis, and after the parenthesis closing before the period. Also, the translation for "signals Replace-By-Fee, BIP-125" is a bit literal and may be unclear; "signals" in this context means "indicates" or "supports" the Replace-By-Fee feature.

Correct translation:  
អ្នកអាចបង្កើនកម្រៃពេលក្រោយ (សញ្ញាបង្ហាញ Replace-By-Fee, BIP-125)។
```

```
        <source>Please, review your transaction.</source>
        <extracomment>Text to prompt a user to review the details of the transaction they are attempting to send.</extracomment>
        <translation>សូមពិនិត្យប្រត្តិបត្តិការទឹកប្រាក់របស់អ្នកសារឡើងវិញ។</translation>
    
YES  
The translation contains a typographical error in the word "ប្រត្តិបត្តិការទឹកប្រាក់" which should be "ប្រតិបត្តិការទឹកប្រាក់" (without the extra ត្). Also, the phrase "សារឡើងវិញ" means "re-send" or "repeat" rather than "review". A better translation for "Please, review your transaction." is:

សូមពិនិត្យប្រតិបត្តិការរបស់អ្នកវិញ។
```

```
        <source>Confirm send coins</source>
        <translation>បញ្ចាក់​ ក្នុងការបញ្ចូនកាក់</translation>
    
YES  
The translation has an unnecessary space after the word "បញ្ចាក់" (Confirm). In Khmer, there should not be a space before the preposition "ក្នុងការ" (in the process of / for). Also, a more natural and concise translation for "Confirm send coins" would be:  
បញ្ចាក់ការបញ្ចូនកាក់
```

```
        <source>The amount to pay must be larger than 0.</source>
        <translation>ចំនួនទឹកប្រាក់ដែលត្រូវបងត្រូវតែធំជាង ០។</translation>
    
YES  
The Khmer translation contains an error in the verb choice. "បង" (bong) means "to hug" or "to embrace," which is incorrect in this context. The correct verb for "to pay" in Khmer here should be "បង់" (bang).

Correct translation:  
ចំនួនទឹកប្រាក់ដែលត្រូវបង់ត្រូវតែធំពីលើ ០។
```

```
        <source>A fee higher than %1 is considered an absurdly high fee.</source>
        <translation>កម្រៃខ្ពស់ជាង %1 ចាត់ទុកថាតម្លៃមិនសមស្រប។​</translation>
    
YES  
The translation incorrectly renders "fee" as "តម្លៃ" (price/value) instead of "កម្រៃ" (fee/charge) in the latter part and loses the meaning of "absurdly high fee." The phrase "ចាត់ទុកថាតម្លៃមិនសមស្រប" means "considered inappropriate value," which is vague and does not convey "an absurdly high fee."

A better translation is:  
កម្រៃខ្ពស់ជាង %1 ត្រូវបានចាត់ទុកថាជាកម្រៃខ្ពស់យ៉ាងអស់ស្មារតី។
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>អាសយដ្ឋានប៊ីតខញក្នុងការបញ្ចូនការទូរទាត់ប្រាក់ទៅកាន់</translation>
    
YES  
The translation is incomplete and slightly awkward in Khmer. The English sentence "The Bitcoin address to send the payment to" implies "The Bitcoin address to which the payment will be sent," but the Khmer translation ends abruptly and lacks the full meaning. It reads more like "Bitcoin address in sending payment to" without clearly indicating the recipient or final phrase.

A better translation would be:  
"អាសយដ្ឋានប៊ីតខញសម្រាប់ផ្ញើការទូរទាត់ប្រាក់ទៅ"  
which means "The Bitcoin address for sending the payment to."
```

```
        <source>Enter the message you want to sign here</source>
        <translation>សូមបញ្ចូលពាក្យដែលអ្នកចង់បញ្ចូលនៅទីនេះ</translation>
    
YES  
The translation uses "បញ្ចូល" twice, which means "enter/input," but the English phrase is "Enter the message you want to sign here." The second "បញ្ចូល" should be replaced with a verb equivalent to "sign" (to sign a message), not "enter." A better translation would be:

សូមបញ្ចូលសារដែលអ្នកចង់ហត្ថលេខានៅទីនេះ
```

```
        <source>Reset all sign message fields</source>
        <translation>កែសម្រួលឡើងវិញគ្រប់សារហត្ថលេខាទាំងអស់ឡើងវិញ</translation>
    
YES  
The translation incorrectly repeats the idea of "reset" twice with "ឡើងវិញ" used twice ("កែសម្រួលឡើងវិញ...ឡើងវិញ"). The phrase should be a clear and concise equivalent of "Reset all sign message fields," meaning to clear or restore all signing message fields. A better translation would be:  
កំណត់ឡើងវិញវាលសារហត្ថលេខាទាំងអស់
```

```
        <source>Clear All</source>
        <translation>សម្អាត ទាំងអស់</translation>
    
YES  
There is an extra space between the two words in the translation. In Khmer, "Clear All" is best translated as "សម្អាតទាំងអស់" without the space in between.

Correct translation:  
សម្អាតទាំងអស់
```

```
        <source>Click "Sign Message" to generate signature</source>
        <translation>ចុច ៉ហត្ថលេខា​ លើសារ​ ​ ៉​ដើម្បីបង្កើតហត្ថលេខា</translation>
    
YES
The translation has spacing and incorrect characters before "Signature" and "Message," making it unclear and possibly confusing. The phrase should be a straightforward instruction without stray or malformed characters.

Correct translation:
ចុច "ហត្ថលេខាលើសារ" ដើម្បីបង្កើតហត្ថលេខា
```

```
        <source>The signature could not be decoded.</source>
        <translation>ការចុះហត្ថលេខានេះមិនគួរត្រូវបានបម្លែងទៅជាភាសាកុំព្យូទ័រទេ។</translation>
    
YES  
The translation means "This signature should not be converted into computer language," which is not an accurate rendering of "The signature could not be decoded." The sentence should convey that decoding failed rather than expressing that it should not be decoded.

Correct translation:  
ការចុះហត្ថលេខានេះមិនអាចបម្លែងបានទេ។
```

```
        <source>%1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in 6 or more blocks.</extracomment>
        <translation>%1​ ការបញ្ចាក់</translation>
    
YES  
There is an issue with a zero-width space or an unexpected invisible character between "%1" and "ការបញ្ចាក់". This can cause formatting or display problems. Also, there should be a normal space after "%1" before the word “ការបញ្ចាក់” in Khmer.

Correct translation:  
%1 ការបញ្ចាក់
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Comma បំបែកឯកសារ</translation>
    
YES  
The translation is partially in English ("Comma") and does not fully translate the phrase "Comma separated file" into Khmer. The phrase should be fully localized and convey the meaning "Comma separated file" as in the CSV file format.

Correct translation:  
"ឯកសារបំបែកដោយក្បៀស"
```

```
        <source>The transaction history was successfully saved to %1.</source>
        <translation>ប្រវត្តប្រត្តិបត្តិការបានទទួលជោគជ័យ និង​បានរក្សាទុក %1។</translation>
    
YES  
The translation contains an error and a formatting issue. The phrase "ប្រវត្តប្រត្តិបត្តិការបានទទួលជោគជ័យ" is a misspelling; the correct word for "transaction" is "ប្រត្តិបត្តិការ" (not "ប្រវត្តប្រត្តិបត្តិការ").  
Also, there is an unnecessary underscore before "បានរក្សាទុក" which should be removed to avoid improper spacing.  

Correct translation:  
ប្រត្តិបត្តិការបានទទួលជោគជ័យ និងបានរក្សាទុក %1។
```

```
        <source>Could not commit transaction</source>
        <translation>មិនបានធ្វើប្រត្តិបត្តិការ</translation>
    
YES  
The translation "មិនបានធ្វើប្រត្តិបត្តិការ" is missing the negation of "commit" in the sense of finalizing or confirming the transaction. It literally translates as "did not do the transaction" which is incomplete and not precise in the Bitcoin context. The correct phrase should explicitly convey the inability to commit (finalize) the transaction.

Correct translation:  
"មិនអាចបញ្ជាទិញប្រត្តិបត្តិការ​បាន"  
(or alternatively)  
"មិនអាចបញ្ចប់ប្រត្តិបត្តិការ​បាន"  

Both express "Could not commit transaction" accurately in Khmer.
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>សេចក្តីប្រកាសអាសន្នៈ​ លេខសំម្ងាត់ត្រូវបានស្វែងរកឃើញនៅក្នុងកាបូបអេឡិចត្រូនិច​ {%s} ជាមួយនិងលេខសំម្ងាត់ត្រូវបានដាក់ឲ្យលែងប្រើលែងកើត</translation>
    
YES  
The translation contains redundant and incorrect phrasing, especially "ជាមួយនិងលេខសំម្ងាត់ត្រូវបានដាក់ឲ្យលែងប្រើលែងកើត" which is awkward and repetitive. The phrase "disabled private keys" should be translated clearly as "លេខសំងាត់ផ្ទាល់ខ្លួនដែលបានបិទប្រើ" or similar, meaning "private keys that have been disabled" without redundancy.

Correct translation:  
សេចក្តីប្រកាសអាសន្ន៖ លេខសំងាត់ផ្ទាល់ខ្លួនត្រូវបានរកឃើញនៅក្នុងកាបូបអេឡិចត្រូនិច {%s} ដែលមានលេខសំងាត់ផ្ទាល់ខ្លួនបានបិទប្រើ
```

```
        <source>The preselected coins total amount does not cover the transaction target. Please allow other inputs to be automatically selected or include more coins manually</source>
        <translation>ចំនួនសរុបនៃកាក់ដែលបានជ្រើសរើសជាមុនមិនគ្របដណ្តប់លើគោលដៅប្រតិបត្តិការទេ។ សូមអនុញ្ញាតឱ្យធាតុបញ្ចូលផ្សេងទៀតត្រូវបានជ្រើសរើសដោយស្វ័យប្រវត្តិ ឬបញ្ចូលកាក់បន្ថែមទៀតដោយហត្ថកម្</translation>
    
YES  
The translation is cut off at the end ("ហត្ថកម្"), leaving it incomplete and therefore erroneous. The full sentence should convey allowing other inputs to be automatically selected or manually including more coins.  

Correct translation:  
ចំនួនសរុបនៃកាក់ដែលបានជ្រើសរើសជាមុនមិនគ្របដណ្តប់លើគោលដៅប្រតិបត្តិការទេ។ សូមអនុញ្ញាតឱ្យធាតុបញ្ចូលផ្សេងទៀតត្រូវបានជ្រើសរើសដោយស្វ័យប្រវត្តិ ឬបញ្ចូលកាក់បន្ថែមទៀតដោយដៃ។
```

```
        <source>Done loading</source>
        <translation>បានធ្វើរួចរាល់ហើយ កំពុងបង្ហាញ</translation>
    
YES  
The translation adds "កំពុងបង្ហាញ" which means "currently displaying" or "showing," which is not present in the source text "Done loading." The source text simply means loading is complete, without implying any further action. The correct translation should be concise and match the source meaning exactly.

Correct translation:  
បានដំណើរការជាចប់រួចហើយ
```

```
        <source>Signing transaction failed</source>
        <translation>ប្រត្តិបត្តការចូល មិនជោគជ័យ</translation>
    
YES  
The Khmer translation contains a typo and spacing issue. The word "ប្រត្តិបត្តការ‌" should be "ប្រតិបត្តការ" (correct spelling without the extra "្ត្រ"). Also, there is an unnecessary space between "ប្រតិបត្តការ" and "ចូល". The phrase "Signing transaction failed" in Bitcoin context is best translated as "ការចុះហត្ថលេខាលើប្រតិបត្តិការមានបញ្ហា" or "ការចុះហត្ថលេខាលើប្រតិបត្តិការ​មិនជោគជ័យ។"

Correct translation:  
ការចុះហត្ថលេខាលើប្រតិបត្តិការ​មិនជោគជ័យ
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>ប្រត្តិបត្តិការមានខ្សែចង្វាក់រងចាំដើម្បីធ្វើការផ្ទៀងផ្ទាត់វែង</translation>
    
YES
The translation does not accurately convey the original English meaning. The English text means the wallet avoids paying fees lower than the minimum relay fee, but the Khmer translation talks about a "transaction having a pending circuit to verify length," which is unrelated and incorrect.

Correct translation:
កាបូបលុយ​នឹងជៀសវាងការបង់កម្រៃបញ្ជូនអប្បបរមា​ដែលត្រូវបញ្ជូនបាន។
```
</details>
