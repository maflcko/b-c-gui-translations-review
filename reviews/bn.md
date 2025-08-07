# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>bn</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bbn%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>পেমেন্ট পাওয়ার জন্য এটি আপনার বিটকয়েন ঠিকানা। নতুন ঠিকানা তৈরী করতে "নতুন গ্রহণের ঠিকানা তৈরী করুন" বোতাম ব্যবহার করুন। সাইন ইন করা শুধুমাত্র "উত্তরাধিকার" ঠিকানার মাধ্যমেই সম্ভব।</translation>
    
YES
There are several issues:
1. The English source refers to "addresses" (plural), but the translation uses the singular ("ঠিকানা").
2. The instruction to use the button is not fully accurate: "গ্রহণের" is not the best translation for "receiving" tab, and the string “নতুন গ্রহণের ঠিকানা তৈরী করুন” directly translates the button label, but there is slight ambiguity.
3. "Signing" is translated as "সাইন ইন করা", which means "signing in" (like logging in), not "cryptographic signing". The correct Bengali term here would be "স্বাক্ষর" or "স্বাক্ষর করা".

Correct translation:
এগুলো আপনার পেমেন্ট গ্রহণের জন্য বিটকয়েন ঠিকানাগুলি। নতুন ঠিকানা তৈরি করতে রিসিভ ট্যাবে 'নতুন গ্রহণের ঠিকানা তৈরি করুন' বোতামটি ব্যবহার করুন।
স্বাক্ষর কেবলমাত্র 'লেগেসি' ধরনের ঠিকানার সাথে সম্ভব।
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>%1 সেটিংস ফাইল টি সম্ভবত নষ্ট বা করাপ্ট</translation>
    
YES
The translation is incomplete and has a minor grammar issue. "করাপ্ট" is an incorrect transliteration; a more natural Bengali word is "দূষিত" or an established transliteration like "করাপ্টেড". The translation also omits "invalid" entirely, and the structure can be improved for clarity.

Correct translation:
%1 সেটিংস ফাইলটি সম্ভবত নষ্ট বা অবৈধ।
```

```
        <source>Sign message…</source>
        <translation>সাইন এবং বার্তা...</translation>
    
YES
The translation is inaccurate. "সাইন এবং বার্তা..." means "Sign and message...", but the English is "Sign message…" (i.e., "sign a message" or "message signing"). The translation should convey the action of signing a message, not "sign and message".

Correct translation:
বার্তায় স্বাক্ষর করুন…
or
বার্তা স্বাক্ষর করুন…
```

```
        <source>Catching up…</source>
        <translation>ধরা…</translation>
    
YES
The translation is inaccurate. "ধরা…" means "to catch…" but doesn't convey the ongoing process of "Catching up…" as in synchronizing or becoming up to date. A better translation conveying the intended Bitcoin context would be:

Correct translation:
আপডেট হচ্ছে…
```

```
        <source>Mask values</source>
        <translation>অক্ষরগুলি আড়াল করুন </translation>
    
YES
The translation "অক্ষরগুলি আড়াল করুন" means "Hide the characters," which is not a correct translation of "Mask values." "Values" should be translated as "মান" rather than "অক্ষরগুলি" ("characters"). Also, there is a stray space at the end.

Correct translation:
মানগুলো গোপন করুন
```

```
        <source>Show</source>
        <translation>Sকিভাবে</translation>
    
YES
The translation "Sকিভাবে" is incorrect for "Show". It appears to be a combination of an English letter "S" and the Bengali "কিভাবে" (which means "how"), which is erroneous and nonsensical in this context.

Correct translation:
দেখান
```

```
        <source>Lock unspent</source>
        <translation>Lock অব্যয়</translation>
    
YES
The translation is problematic. "Lock অব্যয়" is a partial translation where "Lock" is untranslated, and "অব্যয়" is an uncommon or unclear term in this context. The usual translation for "unspent" in the context of Bitcoin is "অব্যবহৃত". "Lock" should be translated as "লক" or "আটকান", depending on preferred terminology in technical Bengali localization.

Correct translation:
অব্যবহৃত লক করুন

If you want the term order to match English (i.e., for user interfaces), it could be:
লক অব্যবহৃত

But the more explanatory/localized version would be:
অব্যবহৃত অর্থ লক করুন or অব্যবহৃত টোকেন লক করুন

For simply mirroring the English (as in menu items), the first suggestion suffices.
```

```
        <source>Migrate wallet</source>
        <translation>মাইচগ্রেট ওয়ালেট </translation>
    
YES
The transliteration "মাইচগ্রেট" is not an accurate Bengali translation; it is a phonetic misspelling of the English word "Migrate". The standard practice is to use the Bengali word for "Migrate".

Correct translation:
ওয়ালেট স্থানান্তর করুন
```

```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>আপনি কি ওয়ালেট1 %1 1 স্থানান্তর করার বিষয়ে নিশ্চিত?</translation>
    
YES
The translation is inaccurate and awkward. It has duplicate and extraneous characters (e.g., "ওয়ালেট1" and "1 স্থানান্তর") which are erroneous. The format specifier %1 is not placed correctly, and "স্থানান্তর" is a valid translation for "migrate," but the overall sentence structure is poor.

Correct translation:
আপনি কি নিশ্চিতভাবে ওয়ালেট <i>%1</i> স্থানান্তর করতে চান?
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
There are notable issues with the translation:

1. The translation for the backup file name omits "&lt;wallet name&gt;-&lt;timestamp&gt;" and just uses "-.legacy.bak", which is inaccurate. The placeholder should be retained.
2. The translation introduces non-standard wording for "solvable but not watched scripts" as "সমাধানযোগ্য কিন্তু দেখা না হওয়া স্ক্রিপ্ট", which literally means "solvable but not seen script", but the more accurate rendition would be "সমাধানযোগ্য কিন্তু ওয়াচঅনলি নয় এমন স্ক্রিপ্ট".
3. The format and phrasing do not precisely follow the source's technical neutrality; e.g., "মাইগ্রেশন করার আগে" does not exactly capture "before migrating" as per original.

Correct translation:
ওয়ালেট স্থানান্তর করলে এই ওয়ালেটটি এক বা একাধিক ডেসক্রিপ্টর ওয়ালেটে রূপান্তরিত হবে। একটি নতুন ওয়ালেট ব্যাকআপ নিতে হবে।
যদি এই ওয়ালেটে কোনো ওয়াচঅনলি স্ক্রিপ্ট থাকে, তাহলে একটি নতুন ওয়ালেট তৈরি হবে যেখানে সেই ওয়াচঅনলি স্ক্রিপ্টগুলো থাকবে।
যদি এই ওয়ালেটে কোনো সমাধানযোগ্য কিন্তু ওয়াচঅনলি নয় এমন স্ক্রিপ্ট থাকে, তাহলে এগুলোর জন্য একটি আলাদা নতুন ওয়ালেট তৈরি হবে যাতে ঐ স্ক্রিপ্টগুলো থাকবে।

স্থানান্তর প্রক্রিয়া শুরু করার আগে ওয়ালেটের একটি ব্যাকআপ তৈরি করা হবে। এই ব্যাকআপ ফাইলটির নাম হবে &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak এবং এটি এই ওয়ালেটের ডিরেক্টরিতে পাওয়া যাবে। যদি মাইগ্রেশনে কোনো ভুল হয়, তাহলে "ওয়ালেট পুনরুদ্ধার করুন" অপশন ব্যবহার করে ওই ব্যাকআপ থেকে পুনরুদ্ধার করা যাবে।
```

```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>দেখাতে হবে কিনা PSBT কন্ট্রোল </translation>
    
YES
The translation is not fully accurate and omits the end punctuation present in the English source. "দেখাতে হবে কিনা PSBT কন্ট্রোল" is more of a statement, not an option/setting description, and feels incomplete. A more accurate and fluent translation would be:

Correct translation:
PSBT কন্ট্রোল দেখানো হবে কিনা।
```

```
        <source>Ctrl+I</source>
        <translation>Ctrl+l</translation>
    
YES
The translation is problematic. The letter "I" (uppercase i) was replaced with "l" (lowercase L), which is incorrect and could confuse users regarding the intended keyboard shortcut.

Correct translation:
Ctrl+I
If transliteration is required for Bengali context, keep the shortcut unchanged as these are standard keys:
Ctrl+I
```

```
        <source>No</source>
        <translation>না </translation>
    
YES
There is an unwanted whitespace at the end of the translation “না ”. It should not have trailing spaces.

Correct translation:
না
```

```
        <source>Label</source>
        <translation>টিকেট</translation>
    
YES
The translation is incorrect. "Label" should be translated as "লেবেল" or "চিহ্ন", not "টিকেট" (which means "ticket" in Bengali).

Correct translation:
লেবেল
```

```
        <source>Label</source>
        <translation>টিকেট</translation>
    
YES
The translation is incorrect. "Label" should be translated as "লেবেল" or "চিহ্ন", not "টিকেট" (which means "ticket" in Bengali).

Correct translation:
লেবেল
```

```
        <source>Label</source>
        <translation>টিকেট</translation>
    
YES
The translation is incorrect. "Label" should be translated as "লেবেল" or "চিহ্ন", not "টিকেট" (which means "ticket" in Bengali).

Correct translation:
লেবেল
```

```
        <source>Settings file could not be read</source>
        <translation>Settingsসেটিংস ফাইল পড়া যাবে না।fileসেটিংস ফাইল পড়া যাবে না।couldসেটিংস ফাইল পড়া যাবে না।notসেটিংস ফাইল পড়া যাবে না।beসেটিংস ফাইল পড়া যাবে না।read</translation>
    
YES
The translation is problematic. It includes repeated segments in both English and Bengali, making it incoherent and incorrect. The correct Bengali translation should be concise and fully translated:

Correct translation:
সেটিংস ফাইল পড়া যাবে না।
```
</details>

Number of issues: 17.
