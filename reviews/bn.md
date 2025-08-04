# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>bn</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bbn%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>পেমেন্ট পাওয়ার জন্য এটি আপনার বিটকয়েন ঠিকানা। নতুন ঠিকানা তৈরী করতে "নতুন গ্রহণের ঠিকানা তৈরী করুন" বোতাম ব্যবহার করুন। সাইন ইন করা শুধুমাত্র "উত্তরাধিকার" ঠিকানার মাধ্যমেই সম্ভব।</translation>
    
YES - The translation of "legacy" as "উত্তরাধিকার" (inheritance) is contextually inaccurate. In the context of Bitcoin addresses, "legacy" refers to an older address format. A more appropriate translation would be "পুরানো" (old) or "ঐতিহ্যবাহী" (traditional).

Correct translation: পেমেন্ট পাওয়ার জন্য এটি আপনার বিটকয়েন ঠিকানা। নতুন ঠিকানা তৈরী করতে "নতুন গ্রহণের ঠিকানা তৈরী করুন" বোতাম ব্যবহার করুন। সাইন ইন করা শুধুমাত্র "পুরানো" ঠিকানার মাধ্যমেই সম্ভব।
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>%1 সেটিংস ফাইল টি সম্ভবত নষ্ট বা করাপ্ট</translation>
    
YES: The translation is missing the word "invalid" which was present in the source text.
Correct translation: Settings file %1 might be corrupt or invalid.
%1 সেটিংস ফাইল টি সম্ভবত নষ্ট বা অবৈধ।
```

```
        <source>Sign message…</source>
        <translation>সাইন এবং বার্তা...</translation>
    
YES
The translation "সাইন এবং বার্তা..." means "Sign and message...". The original English text "Sign message…" means "Sign message...". The word "and" is incorrectly added to the translation.
The correct translation is "বার্তাটিতে স্বাক্ষর করুন…".
```

```
        <source>Catching up…</source>
        <translation>ধরা…</translation>
    
YES, The translation for "Catching up…" is not contextually appropriate for Bitcoin. In the context of Bitcoin, "Catching up…" usually refers to a node synchronizing with the blockchain. A more accurate translation would be something that implies synchronization or updating.

Correct translation: সিঙ্ক্রোনাইজ করা হচ্ছে…
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>ক্লিপবোর্ড থেকে আংশিক স্বাক্ষরিত বিটকয়েন লেনদেন আনুন</translation>
    
YES: The translation is too literal and doesn't accurately reflect the meaning of "PSBT" in the context of Bitcoin. "আংশিক স্বাক্ষরিত বিটকয়েন লেনদেন" (partially signed Bitcoin transaction) is a correct translation of PSBT, but it is too verbose for a UI element. A more concise and common translation for "PSBT" in a Bitcoin context would be "PSBT".

Corrected translation: ক্লিপবোর্ড থেকে PSBT আনুন…
```

```
        <source>Mask values</source>
        <translation>অক্ষরগুলি আড়াল করুন </translation>
    
YES - The translation is inaccurate and doesn't convey the intended meaning of "Mask values" in the context of Bitcoin. "Mask values" typically refers to a way of obscuring or filtering certain data points. The provided Bengali translation translates to "Hide letters" which is not related to the technical context.

Correct translation: মানগুলি মাস্ক করুন
```

```
        <source>Show</source>
        <translation>Sকিভাবে</translation>
    
YES
The translation is inaccurate. The Bengali word "Sকিভাবে" means "how" or "in what way". The English word "Show" means "to display" or "to present".

The correct translation for "Show" in Bengali is "দেখাও" or "প্রদর্শন কর".

Correct translation: দেখাও
```

```
        <source>Lock unspent</source>
        <translation>Lock অব্যয়</translation>
    
YES
The translation of "unspent" to "অব্যয়" (obyoy) is incorrect. "অব্যয়" means indeclinable or immutable, which doesn't fit the context of unspent Bitcoin. The correct translation should reflect something that has not been spent.

NO
```

```
        <source>Migrate wallet</source>
        <translation>মাইচগ্রেট ওয়ালেট </translation>
    
YES: The Bengali translation "মাইচগ্রেট ওয়ালেট " contains a transliterated English word "Migrate" which is misspelled as "মাইচগ্রেট" instead of the correct transliteration "মাইগ্রেট". Additionally, there is an unnecessary trailing space.
Correct translation: মাইগ্রেট ওয়ালেট
```

```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>আপনি কি ওয়ালেট1 %1 1 স্থানান্তর করার বিষয়ে নিশ্চিত?</translation>
    
YES - The Bengali translation incorrectly translates "wallet" to "ওয়ালেট1" and also includes an extra "1" after "ওয়ালেট". It also misses the italic formatting for "%1". The correct translation should be "আপনি কি <i>%1</i> ওয়ালেট স্থানান্তর করার বিষয়ে নিশ্চিত?".
NO
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
    
YES: The placeholder for the wallet name and timestamp is missing in the translation.
<translation>ওয়ালেট স্থানান্তরিত করা এই ওয়ালেটটিকে এক বা একাধিক বর্ণনাকারী ওয়ালেটে রূপান্তর করবে৷ একটি নতুন ওয়ালেট ব্যাকআপ তৈরি করতে হবে।
যদি এই ওয়ালেটটিতে কোনো ওয়াচঅনলি স্ক্রিপ্ট থাকে, তাহলে একটি নতুন ওয়ালেট তৈরি করা হবে যাতে সেই ওয়াচঅনলি স্ক্রিপ্টগুলি রয়েছে৷
যদি এই ওয়ালেটে কোনো সমাধানযোগ্য কিন্তু দেখা না হওয়া স্ক্রিপ্ট থাকে, তাহলে একটি ভিন্ন এবং নতুন ওয়ালেট তৈরি করা হবে যাতে সেই স্ক্রিপ্টগুলি রয়েছে৷

মাইগ্রেশন প্রক্রিয়া মাইগ্রেশন করার আগে ওয়ালেটের একটি ব্যাকআপ তৈরি করবে। এই ব্যাকআপ ফাইলটির নাম হবে &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak এবং এই ওয়ালেটের জন্য ডিরেক্টরিতে পাওয়া যাবে। একটি ভুল মাইগ্রেশনের ক্ষেত্রে, "ওয়ালেট পুনরুদ্ধার করুন" কার্যকারিতা দিয়ে ব্যাকআপ পুনরুদ্ধার করা যেতে পারে।</translation>
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>ওয়ালেটটি অনেকক্ষণ বন্ধ করার ফলে পুনঃসুসংগত করতে পুরো চেইনটি পুনরায় সিঙ্ক করতে হতে পারে।</translation>
    
YES: The translation is inaccurate and grammatically incorrect. The phrase "ওয়ালেটটি অনেকক্ষণ বন্ধ করার ফলে" (Wallet being closed for a long time) is a literal translation of "Closing the wallet for too long" which is grammatically incorrect in Bengali. It should be "Too long closing the wallet". The phrase "পুনঃসুসংগত করতে পুরো চেইনটি পুনরায় সিঙ্ক করতে হতে পারে" (to resynchronize the entire chain may have to resync) is also redundant.

Correct Translation: ওয়ালেট অনেকক্ষণ বন্ধ রাখলে, প্রুনিং চালু থাকলে পুরো চেইনটি আবার সিঙ্ক করতে হতে পারে।
```

```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>দেখাতে হবে কিনা PSBT কন্ট্রোল </translation>
    
YES: The word "PSBT" is not translated into Bengali, and the Bengali sentence structure is a bit awkward.
The correct translation should be: "PSBT নিয়ন্ত্রণ দেখানো হবে কিনা।"
```

```
        <source>Ctrl+I</source>
        <translation>Ctrl+l</translation>
    
YES
The 'I' in the source text has been mistranslated as a lowercase 'l' in the translation, which is incorrect.
Ctrl+I
```

```
        <source>No</source>
        <translation>না </translation>
    
YES: The translation includes an unnecessary trailing space.
Correct translation: না
```

```
        <source>Label</source>
        <translation>টিকেট</translation>
    
YES: The translation is incorrect and does not convey the meaning of "Label" in the context of Bitcoin. In Bitcoin, a "label" is typically used to identify or categorize transactions or addresses. "টিকেট" translates to "ticket" which is not relevant.

Correct translation: লেবেল
```

```
        <source>Label</source>
        <translation>টিকেট</translation>
    
YES: The translation is incorrect and does not convey the meaning of "Label" in the context of Bitcoin. In Bitcoin, a "label" is typically used to identify or categorize transactions or addresses. "টিকেট" translates to "ticket" which is not relevant.

Correct translation: লেবেল
```

```
        <source>Label</source>
        <translation>টিকেট</translation>
    
YES: The translation is incorrect and does not convey the meaning of "Label" in the context of Bitcoin. In Bitcoin, a "label" is typically used to identify or categorize transactions or addresses. "টিকেট" translates to "ticket" which is not relevant.

Correct translation: লেবেল
```

```
        <source>Settings file could not be read</source>
        <translation>Settingsসেটিংস ফাইল পড়া যাবে না।fileসেটিংস ফাইল পড়া যাবে না।couldসেটিংস ফাইল পড়া যাবে না।notসেটিংস ফাইল পড়া যাবে না।beসেটিংস ফাইল পড়া যাবে না।read</translation>
    
YES - The translation is nonsensical and appears to have duplicated and garbled the original English phrase within the Bengali text. The original English phrase is "Settings file could not be read". The Bengali translation should be "সেটিংস ফাইল পড়া যাচ্ছে না।"

NO - Settings file could not be read
```
</details>
