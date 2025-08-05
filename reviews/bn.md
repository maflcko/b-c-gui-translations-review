# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>bn</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bbn%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>পেমেন্ট পাওয়ার জন্য এটি আপনার বিটকয়েন ঠিকানা। নতুন ঠিকানা তৈরী করতে "নতুন গ্রহণের ঠিকানা তৈরী করুন" বোতাম ব্যবহার করুন। সাইন ইন করা শুধুমাত্র "উত্তরাধিকার" ঠিকানার মাধ্যমেই সম্ভব।</translation>
    
YES
The translation contains some inaccuracies and formatting issues:
1. The source mentions "These are your Bitcoin addresses for receiving payments." but the translation says "এটি আপনার বিটকয়েন ঠিকানা," which means "This is your Bitcoin address" (singular), while the source refers to plural addresses.
2. The phrase "Use the 'Create new receiving address' button in the receive tab to create new addresses." is only partially translated and misses context of the "receive tab".
3. The translation for 'legacy' is given as "উত্তরাধিকার," which literally means "inheritance" or "legacy" in a general sense, but in Bitcoin context, it should be transliterated or left as "লিগ্যাসি" to avoid confusion.
4. The line breaks are missing; the source has two sentences separated by a newline. The translation merges them into one, which could be acceptable but better to keep clarity.
5. Some minor grammar improvements can be made for smoother readability.

Correct translation:

আপনাদের পেমেন্ট গ্রহণের জন্য এগুলো আপনার বিটকয়েন ঠিকানাগুলো। নতুন ঠিকানা তৈরির জন্য “গ্রহণ ট্যাবে ‘নতুন গ্রহণের ঠিকানা তৈরি করুন’ বোতামটি ব্যবহার করুন।  
সাইনিং শুধুমাত্র ‘লিগ্যাসি’ ধরনের ঠিকানাগুলোর মাধ্যমে সম্ভব।

(If formatting is preserved for new lines, add line break after first sentence.)
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>%1 সেটিংস ফাইল টি সম্ভবত নষ্ট বা করাপ্ট</translation>
    
YES  
The translation has formatting and completeness issues. The source sentence is "Settings file %1 might be corrupt or invalid." However, the translation "%1 সেটিংস ফাইল টি সম্ভবত নষ্ট বা করাপ্ট" has an extra space before "টি" (ফাইল টি should be ফাইলটি), and the word "invalid" is missing in the translation. Also, "corrupt" is left as "করাপ্ট", which is a transliteration but understandable. It would be better to fully translate or consistently transliterate both terms.

A more accurate and properly formatted translation would be:  
"%1 সেটিংস ফাইলটি সম্ভবত নষ্ট বা অবৈধ হতে পারে।"  

Here "invalid" is translated as "অবৈধ" (meaning invalid), and "might be" is translated as "হতে পারে", making the sentence complete and fluent. The extra space before "টি" is removed.
```

```
        <source>Sign message…</source>
        <translation>সাইন এবং বার্তা...</translation>
    
YES  
The translation "সাইন এবং বার্তা..." means "Sign and message..." which is incorrect. The original text "Sign message…" means "Sign message" with an ellipsis indicating a process or continuation, not "and." The correct translation should capture the verb "Sign" (as in "to sign") related to a message, without adding "and."

Correct translation:  
"বার্তা স্বাক্ষর করুন…"
```

```
        <source>Catching up…</source>
        <translation>ধরা…</translation>
    
YES  
The translation "ধরা…" means "catch" or "caught" in Bengali, which does not convey the intended meaning of "Catching up…" in the Bitcoin context (synchronizing or updating). A more appropriate translation would be:  
"আপডেট হচ্ছে…" or "সিঙ্ক্রোনাইজ করা হচ্ছে…" or simply "সিঙ্ক হচ্ছে…"  
Correct translation:  
<translation>আপডেট হচ্ছে…</translation>
```

```
        <source>Mask values</source>
        <translation>অক্ষরগুলি আড়াল করুন </translation>
    
YES  
The translation "অক্ষরগুলি আড়াল করুন " literally means "Hide the characters," which is not incorrect but may not be the best equivalent for "Mask values" in a technical/Bitcoin context, where "mask" generally means to obscure or partially hide sensitive data.

Also, there is an extra trailing space at the end of the translation which should be removed.

A more appropriate translation for "Mask values" could be:  
"মান গুলো আড়াল করুন" or simply "মান আড়াল করুন" (meaning "Hide/Mask the values").

Corrected translation:  
অক্ষরগুলি আড়াল করুন
```

```
        <source>Show</source>
        <translation>Sকিভাবে</translation>
    
YES
The translation "Sকিভাবে" is incorrect and does not correspond to the English word "Show." It appears to be a mixture of Latin and Bengali letters and seems to attempt to write "কিভাবে" (meaning "how") with an extra "S".

Correct translation:
দেখান
```

```
        <source>Lock unspent</source>
        <translation>Lock অব্যয়</translation>
    
YES  
The word "Lock" is not translated into Bengali, and "অব্যয়" is an incorrect translation in this context. "Unspent" here refers to unspent transaction outputs (UTXOs) in Bitcoin, which in Bengali is better translated as "অব্যবহৃত" or "অব্যয়" is incorrect in this context (means "expense" or "cost"). A proper translation for "Lock unspent" in Bitcoin context could be: "অব্যবহৃত লক করুন" or "অব্যবহৃত লক".  

Correct translation:  
অব্যবহৃত লক করুন
```

```
        <source>Migrate wallet</source>
        <translation>মাইচগ্রেট ওয়ালেট </translation>
    
YES
The translation uses a transliteration "মাইচগ্রেট" for "Migrate," which is not a common or correct Bengali term for this context. A more appropriate and understandable translation would use Bengali terms or an accurate loanword spelling.

Correct translation:
ওয়ালেট স্থানান্তর করুন
```

```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>আপনি কি ওয়ালেট1 %1 1 স্থানান্তর করার বিষয়ে নিশ্চিত?</translation>
    
YES  
The translation is awkward and has incorrectly placed the placeholder %1 and redundant characters "1". The phrase does not fully convey the original question form, and the markup &lt;i&gt; (italic) is omitted around %1.  

Correct translation:  
আপনি কি ওয়ালেট &lt;i&gt;%1&lt;/i&gt; স্থানান্তর করতে চান?
```

```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>ওয়ালেট স্থানান্তরিত করা এই ওয়ালেটটিকে এক বা একাধিক বর্ণনাকারী ওয়ালেটে রূপান্তর করবে৷ একটি নতুন ওয়ালেট ব্যাকআপ তৈরি করতে হবে।
যদি এই ওয়ালেটটিতে কোনো ওয়াচঅনলি স্ক্রিপ্ট থাকে, তাহলে একটি নতুন ওয়ালেট তৈরি করা হবে যাতে সেই ওয়াচঅনলি স্ক্রিপ্টগুলি রয়েছে৷
যদি এই ওয়ালেটে কোনো সমাধানযোগ্য কিন্তু দেখা না হওয়া স্ক্রিপ্ট থাকে, তাহলে একটি ভিন্ন এবং নতুন ওয়ালেট তৈরি করা হবে যাতে সেই স্ক্রিপ্টগুলি রয়েছে৷

মাইগ্রেশন প্রক্রিয়া মাইগ্রেশন করার আগে ওয়ালেটের একটি ব্যাকআপ তৈরি করবে। এই ব্যাকআপ ফাইলটির নাম হবে -.legacy.bak এবং এই ওয়ালেটের জন্য ডিরেক্টরিতে পাওয়া যাবে। একটি ভুল মাইগ্রেশনের ক্ষেত্রে, "ওয়ালেট পুনরুদ্ধার করুন" কার্যকারিতা দিয়ে ব্যাকআপ পুনরুদ্ধার করা যেতে পারে।</translation>
    
YES  
The translation is mostly accurate but has a significant issue in the sentence about the backup file name:  
The original English states that the backup file will be named `<wallet name>-<timestamp>.legacy.bak`, but the Bengali translation misses the placeholders and only leaves `-.legacy.bak`, losing the important parts `<wallet name>` and `<timestamp>`. These placeholders should be preserved as is or adapted with the same placeholders to maintain clarity and format.

Corrected translation snippet for that part:  
`এই ব্যাকআপ ফাইলটির নাম হবে <wallet name>-<timestamp>.legacy.bak এবং এই ওয়ালেটের জন্য ডিরেক্টরিতে পাওয়া যাবে।`

Full corrected translation:  
```
ওয়ালেট স্থানান্তরিত করা এই ওয়ালেটটিকে এক বা একাধিক বর্ণনাকারী ওয়ালেটে রূপান্তর করবে৷ একটি নতুন ওয়ালেট ব্যাকআপ তৈরি করতে হবে।  
যদি এই ওয়ালেটটিতে কোনো ওয়াচঅনলি স্ক্রিপ্ট থাকে, তাহলে একটি নতুন ওয়ালেট তৈরি করা হবে যাতে সেই ওয়াচঅনলি স্ক্রিপ্টগুলি রয়েছে৷  
যদি এই ওয়ালেটে কোনো সমাধানযোগ্য কিন্তু দেখা না হওয়া স্ক্রিপ্ট থাকে, তাহলে একটি ভিন্ন এবং নতুন ওয়ালেট তৈরি করা হবে যাতে সেই স্ক্রিপ্টগুলি রয়েছে৷  

মাইগ্রেশন প্রক্রিয়া মাইগ্রেশন করার আগে ওয়ালেটের একটি ব্যাকআপ তৈরি করবে। এই ব্যাকআপ ফাইলটির নাম হবে <wallet name>-<timestamp>.legacy.bak এবং এই ওয়ালেটের জন্য ডিরেক্টরিতে পাওয়া যাবে। একটি ভুল মাইগ্রেশনের ক্ষেত্রে, "ওয়ালেট পুনরুদ্ধার করুন" কার্যকারিতা দিয়ে ব্যাকআপ পুনরুদ্ধার করা যেতে পারে।  
```
```

```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>দেখাতে হবে কিনা PSBT কন্ট্রোল </translation>
    
YES  
The translation is missing a concluding punctuation mark, such as a full stop, which is present in the source. Also, the phrase structure is somewhat awkward and incomplete in Bengali. A better, more natural and clear translation would be:  
"PSBT কন্ট্রোল দেখানো হবে কিনা।"
```

```
        <source>Ctrl+I</source>
        <translation>Ctrl+l</translation>
    
YES  
The original shortcut key is "Ctrl+I" where the letter "I" (uppercase i) is used. The translated text uses "Ctrl+l" where the letter "l" (lowercase L) is incorrectly substituted for "I". Shortcut keys are case-sensitive and must match exactly.

Correct translation:  
Ctrl+I
```

```
        <source>No</source>
        <translation>না </translation>
    
YES  
There is an extra trailing space after "না" which is unnecessary and inconsistent with standard formatting. Also, "না" means "No" correctly in Bengali, but it should not have trailing whitespace.  

Correct translation:  
না
```

```
        <source>Label</source>
        <translation>টিকেট</translation>
    
YES  
The English word "Label" is incorrectly translated as "টিকেট" which means "ticket" in Bengali. The correct translation for "Label" in this context (such as a tag or name associated with an address) should be "লেবেল" or "লেবেল" (a common transliteration) or "লেবেল" depending on the context. The most commonly used term in Bitcoin applications is "লেবেল".  

Correct translation:  
<translation>লেবেল</translation>
```

```
        <source>Label</source>
        <translation>টিকেট</translation>
    
YES  
The English word "Label" is incorrectly translated as "টিকেট" which means "ticket" in Bengali. The correct translation for "Label" in this context (such as a tag or name associated with an address) should be "লেবেল" or "লেবেল" (a common transliteration) or "লেবেল" depending on the context. The most commonly used term in Bitcoin applications is "লেবেল".  

Correct translation:  
<translation>লেবেল</translation>
```

```
        <source>Label</source>
        <translation>টিকেট</translation>
    
YES  
The English word "Label" is incorrectly translated as "টিকেট" which means "ticket" in Bengali. The correct translation for "Label" in this context (such as a tag or name associated with an address) should be "লেবেল" or "লেবেল" (a common transliteration) or "লেবেল" depending on the context. The most commonly used term in Bitcoin applications is "লেবেল".  

Correct translation:  
<translation>লেবেল</translation>
```

```
        <source>Settings file could not be read</source>
        <translation>Settingsসেটিংস ফাইল পড়া যাবে না।fileসেটিংস ফাইল পড়া যাবে না।couldসেটিংস ফাইল পড়া যাবে না।notসেটিংস ফাইল পড়া যাবে না।beসেটিংস ফাইল পড়া যাবে না।read</translation>
    
YES  
The translation is incorrect and nonsensical. It repeats fragments mixed with English words and Bengali script without proper structure or meaning. The correct Bengali translation for "Settings file could not be read" is:  
"সেটিংস ফাইল পড়া যায়নি"
```
</details>
