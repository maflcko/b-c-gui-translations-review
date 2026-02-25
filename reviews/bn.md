# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>bn</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bbn%5D%20request)


<!-- cache_translation_check_bn_0dd82b171679d261cb464b6a935f14d900c9065f1dfc2706afe5ab578758da26 -->
```
        <source>C&amp;lose</source>
        <translation>বন্ধ করুন</translation>
    
ERR
The shortcut marker '&' from the source is missing. It must appear exactly once in the translation.

Correct translation:
&বন্ধ করুন
```

<!-- cache_translation_check_bn_77770e62eb5f1b815419031896d5e01dea25fd56395139f250b13e9a88c99550 -->
```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>পেমেন্ট পাওয়ার জন্য এটি আপনার বিটকয়েন ঠিকানা। নতুন ঠিকানা তৈরী করতে "নতুন গ্রহণের ঠিকানা তৈরী করুন" বোতাম ব্যবহার করুন।
সাইন ইন করা শুধুমাত্র "উত্তরাধিকার" ঠিকানার মাধ্যমেই সম্ভব।</translation>
    
ERR
Issues:
- Plural lost: “These are … addresses” translated as singular.
- “receive tab” omitted.
- “Signing” mistranslated as “সাইন ইন” (login). Should be “স্বাক্ষর/সাইন”.
- “legacy” should not be translated as “উত্তরাধিকার”; keep “legacy”.
- Spelling: “তৈরী” should be “তৈরি”.

Correct translation:
এগুলো আপনার পেমেন্ট গ্রহণের জন্য বিটকয়েন ঠিকানাগুলি। নতুন ঠিকানা তৈরি করতে রিসিভ ট্যাবে থাকা ‘নতুন গ্রহণের ঠিকানা তৈরি করুন’ বোতামটি ব্যবহার করুন।
স্বাক্ষর করা কেবল ‘legacy’ ধরনের ঠিকানার সঙ্গে সম্ভব।
```

<!-- cache_translation_check_bn_0cc03b6d71bac850e47b7edeae399d30310ef85ac569447bfac182e55acebcc1 -->
```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>%1 সেটিংস ফাইল টি সম্ভবত নষ্ট বা করাপ্ট</translation>
    
ERR
The translation is incomplete and has a minor grammar issue. "করাপ্ট" is an incorrect transliteration; a more natural Bengali word is "দূষিত" or an established transliteration like "করাপ্টেড". The translation also omits "invalid" entirely, and the structure can be improved for clarity.

Correct translation:
%1 সেটিংস ফাইলটি সম্ভবত নষ্ট বা অবৈধ।
```

<!-- cache_translation_check_bn_b1a23a108db505191a1d1ff206c8652c828728832741a410cbad4d5fddd29811 -->
```
        <source>&amp;Minimize</source>
        <translation>ছোট করুন</translation>
    
ERR
The '&' symbol indicating a shortcut key is missing in the Bengali translation. It should appear exactly once, but does not appear at all.

Correct translation:
&ছোট করুন
</reply>
```

<!-- cache_translation_check_bn_e83ea5916082f22e1e9998127e468dcf9750a82daa4607e8abd276cd6a869fe4 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>ব্যাকআপ ওয়ালেট…</translation>
    
ERR
The ampersand (&) indicating the shortcut key is missing from the Bengali translation. It must appear exactly once, anywhere in the translation.

Correct translation:
&ব্যাকআপ ওয়ালেট…
```

<!-- cache_translation_check_bn_6cc3cca3821175afb76ac8bfd63d7ec8020f1c9d4afd661697ce926545a6334b -->
```
        <source>Sign &amp;message…</source>
        <translation>সাইন এবং বার্তা...</translation>
    
ERR
The English text uses "&amp;message" to indicate a shortcut key (the ampersand), but in the Bengali translation "সাইন এবং বার্তা...", there is no ampersand (or its equivalent, which is uncommon in Bengali UI but still should be preserved for shortcut purposes). Additionally, the literal translation of "Sign &amp;message" into "সাইন এবং বার্তা..." is misleading: "Sign message" actually refers to digitally signing a message in the context of Bitcoin, not to a conjunction. The ellipsis (...) is also present, as in the source, which is correct.

Correct translation:
বার্তায় & সাইন করুন ...
or
বার্তা &amp; সাইন করুন...
or (in more natural Bengali UI, keeping the ampersand for the shortcut)
বার্তা (&M) স্বাক্ষর করুন...

Depending on the context specifics for menu/key shortcuts in Bengali UIs, but the literal "এবং" ("and") is not correct in technical/software context. The ampersand (&) is required somewhere as a shortcut indicator.
```

<!-- cache_translation_check_bn_c14c42bf3d25699e4b35817c29013f2990d6169dde5560735cfc4e13454c8fd0 -->
```
        <source>&amp;Verify message…</source>
        <translation>বার্তা যাচাই করুন...</translation>
    
ERR
The ampersand (&) indicating the shortcut key from the source text (&Verify message…) is missing in the translation. According to the rule, there should be exactly one ampersand in the translation.

Correct translation:
&বার্তা যাচাই করুন...
```

<!-- cache_translation_check_bn_89fab0ea7623a650fb33e9a713e2b2697445d5dfcafb2b8891b446e3d60f8b21 -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>ফাইল থেকে PSBT লোড করুন...</translation>
    
ERR
The ampersand (&) indicating the shortcut key in the source (&Load PSBT from file…) is missing in the translation. It should appear exactly once in the translation as well.

Correct translation:
&amp;ফাইল থেকে PSBT লোড করুন...
```

<!-- cache_translation_check_bn_84b93addd89263bceaeb2d6ad1c56922e968756bd6112f0558edf48a763d1ce3 -->
```
        <source>Open &amp;URI…</source>
        <translation>URI খুলুন...</translation>
    
ERR
The translation is missing the shortcut indicator '&' which must appear exactly once to correspond with the English text.

Correct translation:
&URI খুলুন…
```

<!-- cache_translation_check_bn_04e9ffe85031983b86a63b52fa2347290443c0aaf5445158f06be9e81d1a8426 -->
```
        <source>Catching up…</source>
        <translation>ধরা…</translation>
    
ERR
The translation is inaccurate. "ধরা…" means "to catch…" but doesn't convey the ongoing process of "Catching up…" as in synchronizing or becoming up to date. A better translation conveying the intended Bitcoin context would be:

Correct translation:
আপডেট হচ্ছে…
```

<!-- cache_translation_check_bn_d58e149b6318d857257760ee78d077ec1732ba7fd1854c0fdd57a8d224b0ae3f -->
```
        <source>Open Wallet</source>
        <translation>ওয়ালেট খুলুন </translation>
    
ERR
Trailing whitespace detected in the translation.

Correct translation:
ওয়ালেট খুলুন
```

<!-- cache_translation_check_bn_842ec5854d16e8ea783bccade7282f79c38513e89e15de2133f7555b71425169 -->
```
        <source>&amp;Mask values</source>
        <translation>অক্ষরগুলি আড়াল করুন </translation>
    
ERR
The translation does not include the '&' character, which is used as a shortcut key indicator and must appear exactly once in both the source and translation. Additionally, the translation for "values" is missing. The translation should also not have trailing whitespace.

Correct translation:
&মান আড়াল করুন
</reply>
```

<!-- cache_translation_check_bn_9e9b70d3e5da6e55713cb53165cfa9f6c2976f6db9e52fd047e6160eaacb408a -->
```
        <source>Zoom</source>
        <translation>zoom</translation>
    
ERR
The translation is not in Bengali; it simply repeats the English word in lowercase. It should be translated/transliterated into Bengali.

Correct translation:
জুম
```

<!-- cache_translation_check_bn_18847446785423eabc6b3f628fb8cc6c99d260eda1d0465cd8c4682dbf38f6b5 -->
```
        <source>S&amp;how</source>
        <translation>S&amp;কিভাবে</translation>
    
ERR
The translation "S&কিভাবে" is incorrect because "কিভাবে" means "how" in Bengali, which does not convey the meaning of "Show". Also, the ampersand (&) is present, but it should be attached to the correctly translated word.

Correct translation:
&দেখান
</reply>
```

<!-- cache_translation_check_bn_55cbc127801296bd8c63495880093469b0a6f13e01a00e4c9b42df754e511bc9 -->
```
        <source>&amp;Copy address</source>
        <translation>ঠিকানা কপি করুন</translation>
    
ERR
The '&' indicating the shortcut key from the source text is missing in the Bengali translation. It should appear exactly once in the translation.

Correct translation:
&ঠিকানা কপি করুন
```

<!-- cache_translation_check_bn_36a7168b79362233d9426fc37a1e2953a789a7e3529023d6d0c77a08634a110a -->
```
        <source>Copy &amp;label</source>
        <translation>কপি লেবেল</translation>
    
ERR
The translation "কপি লেবেল" is missing the ampersand (&) character, which denotes the shortcut key in the original English string. The ampersand should be present exactly once in the translation.

Correct translation:
কপি &লেবেল
or
&কপি লেবেল

Either placement is allowed as per shortcut conventions, but the ampersand must appear exactly once.
```

<!-- cache_translation_check_bn_6285b845fcc2bc8d8455413f9e44dc9ce825833e0ba97df87f048941c57d55de -->
```
        <source>Copy &amp;amount</source>
        <translation>কপি পরিমাণ</translation>
    
ERR
The ampersand (&) indicating the shortcut key from the source ("Copy &amp;amount") is missing in the translation. The correct translation should include it exactly once, consistent with shortcut conventions. 

Correct translation:
&amp;পরিমাণ কপি করুন
```

<!-- cache_translation_check_bn_b36c6509f19a0b1d2095c2e4c2ed15d71dfff8ffc84f91cd34d862d912cc3479 -->
```
        <source>L&amp;ock unspent</source>
        <translation>L&amp;ock অব্যয়</translation>
    
ERR
The translation is incorrect because it retains the English word "Lock" instead of translating it to Bengali, and "অব্যয়" alone is not a commonly used term for "unspent" in the context of Bitcoin. The correct Bengali for "Lock unspent" (meaning "Lock an unspent output") should be:

Correct translation:
অব্যবহৃত লক করুন (&amp;L)
```

<!-- cache_translation_check_bn_9fe0b462d1fc7206942d8864bb374e6314e859c3c6e7bbde52a056b3dc1338fe -->
```
        <source>&amp;Unlock unspent</source>
        <translation>&amp;অব্যয়িত খোলা</translation>
    
ERR
The translation of "&amp;Unlock unspent" as "&amp;অব্যয়িত খোলা" is incorrect. "অব্যয়িত" means "unspent", and "খোলা" means "open", not "unlock". The correct translation for "Unlock" is "আনলক" or "লক খুলুন", so the phrase should be more accurately rendered as "অব্যয়িত আনলক করুন" or "&amp;অব্যয়িত আনলক করুন".

Correct translation:
&amp;অব্যয়িত আনলক করুন
```

<!-- cache_translation_check_bn_da58da0e9712a69c80d888d8f008d7549657a7557dfa931c23de2288185e17f5 -->
```
        <source>Creating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the create wallet progress window which indicates to the user which wallet is currently being created.</extracomment>
        <translation>ওয়ালেট তৈরি করা হচ্ছে</translation>
    
ERR
The translation omits the placeholder %1 and does not specify which wallet is being created, which is important information from the source sentence.

Correct translation:
ওয়ালেট &lt;b&gt;%1&lt;/b&gt; তৈরি করা হচ্ছে…
```

<!-- cache_translation_check_bn_a3525f0a9e5e5b15e9da8b7cd057efe9af462eb528910f30dedef4c13f499380 -->
```
        <source>Migrate wallet</source>
        <translation>মাইচগ্রেট ওয়ালেট </translation>
    
ERR
The transliteration "মাইচগ্রেট" is not an accurate Bengali translation; it is a phonetic misspelling of the English word "Migrate". The standard practice is to use the Bengali word for "Migrate".

Correct translation:
ওয়ালেট স্থানান্তর করুন
```

<!-- cache_translation_check_bn_e511adf508c583c4ff3fa818f5cfc4e81b6d9594b2fbc12307d2b84049bfb6f0 -->
```
        <source>Are you sure you wish to migrate the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>আপনি কি ওয়ালেট1 %1 1 স্থানান্তর করার বিষয়ে নিশ্চিত?</translation>
    
ERR
The translation is inaccurate and awkward. It has duplicate and extraneous characters (e.g., "ওয়ালেট1" and "1 স্থানান্তর") which are erroneous. The format specifier %1 is not placed correctly, and "স্থানান্তর" is a valid translation for "migrate," but the overall sentence structure is poor.

Correct translation:
আপনি কি নিশ্চিতভাবে ওয়ালেট <i>%1</i> স্থানান্তর করতে চান?
```

<!-- cache_translation_check_bn_e8cbd0352b0c5402f47159be4b104755f4c057885c75c4c22d4d44d213c3cc23 -->
```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>ওয়ালেট স্থানান্তরিত করা এই ওয়ালেটটিকে এক বা একাধিক বর্ণনাকারী ওয়ালেটে রূপান্তর করবে৷ একটি নতুন ওয়ালেট ব্যাকআপ তৈরি করতে হবে।
যদি এই ওয়ালেটটিতে কোনো ওয়াচঅনলি স্ক্রিপ্ট থাকে, তাহলে একটি নতুন ওয়ালেট তৈরি করা হবে যাতে সেই ওয়াচঅনলি স্ক্রিপ্টগুলি রয়েছে৷
যদি এই ওয়ালেটে কোনো সমাধানযোগ্য কিন্তু দেখা না হওয়া স্ক্রিপ্ট থাকে, তাহলে একটি ভিন্ন এবং নতুন ওয়ালেট তৈরি করা হবে যাতে সেই স্ক্রিপ্টগুলি রয়েছে৷

মাইগ্রেশন প্রক্রিয়া মাইগ্রেশন করার আগে ওয়ালেটের একটি ব্যাকআপ তৈরি করবে। এই ব্যাকআপ ফাইলটির নাম হবে -.legacy.bak এবং এই ওয়ালেটের জন্য ডিরেক্টরিতে পাওয়া যাবে। একটি ভুল মাইগ্রেশনের ক্ষেত্রে, "ওয়ালেট পুনরুদ্ধার করুন" কার্যকারিতা দিয়ে ব্যাকআপ পুনরুদ্ধার করা যেতে পারে।</translation>
    
ERR
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

<!-- cache_translation_check_bn_5cc75ffec232b6320dbf3c12f2b13f8911cd3ac273d0f92bb2ff0d4ac4a5ed28 -->
```
        <source>Open Wallet</source>
        <extracomment>Title of window indicating the progress of opening of a wallet.</extracomment>
        <translation>ওয়ালেট খুলুন </translation>
    
ERR
The translation uses the imperative ("ওয়ালেট খুলুন") rather than indicating progress, and it contains a trailing space.

Correct translation:
ওয়ালেট খোলা হচ্ছে
```

<!-- cache_translation_check_bn_1c218480bf9da859abb8acd05db94633fb5871582e57a6e348bad4368bbba32c -->
```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>দেখাতে হবে কিনা PSBT কন্ট্রোল </translation>
    
ERR
The translation is not fully accurate and omits the end punctuation present in the English source. "দেখাতে হবে কিনা PSBT কন্ট্রোল" is more of a statement, not an option/setting description, and feels incomplete. A more accurate and fluent translation would be:

Correct translation:
PSBT কন্ট্রোল দেখানো হবে কিনা।
```

<!-- cache_translation_check_bn_255012906758618ddc10c169df2538b1a9b3f02c8f68e2874ce530cb536e161c -->
```
        <source>&amp;Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>ঠিকানা কপি করুন</translation>
    
ERR
The translation is missing the '&' character, which is used to indicate the shortcut key in the menu. It should appear exactly once somewhere in the translation.

Correct translation:
&ঠিকানা কপি করুন
or
ঠিকানা &কপি করুন
```

<!-- cache_translation_check_bn_087c788748bb88c6e86967f73d9234b423f3dfebf6eb28af87760a2e2be0de3b -->
```
        <source>&amp;Copy IP/Netmask</source>
        <extracomment>Context menu action to copy the IP/Netmask of a banned peer. IP/Netmask is the combination of a peer's IP address and its Netmask. For IP address, see: https://en.wikipedia.org/wiki/IP_address.</extracomment>
        <translation>&amp;copy আইপি/নেটমাস্ক
(IP/Netmask)</translation>
    
ERR
The translation unnecessarily includes both an inconsistent case for "copy" (should be in Bengali script and capitalisation is not as in English shortcut conventions), and adds a redundant parenthetical "(IP/Netmask)" which is not in the source. The & shortcut is also not properly integrated into the translation.

Correct translation:
&কপি আইপি/নেটমাস্ক

Explanation: "কপি" is the standard Bengali transliteration for "copy", and the shortcut ampersand is kept before it, maintaining consistency with the original. No extra parentheses or English text is needed.
```

<!-- cache_translation_check_bn_96a37554d20e206b5c4be6e25a908bbeb71d1268c3909de47e81faabcaa70d4d -->
```
        <source>Ctrl+I</source>
        <translation>Ctrl+l</translation>
    
ERR
The translation is problematic. The letter "I" (uppercase i) was replaced with "l" (lowercase L), which is incorrect and could confuse users regarding the intended keyboard shortcut.

Correct translation:
Ctrl+I
If transliteration is required for Bengali context, keep the shortcut unchanged as these are standard keys:
Ctrl+I
```

<!-- cache_translation_check_bn_704c05ed88d695a93c718b0a23a765e49c76decda944ad92a5206010e14813a6 -->
```
        <source>No</source>
        <translation>না </translation>
    
ERR
There is an unwanted whitespace at the end of the translation “না ”. It should not have trailing spaces.

Correct translation:
না
```

<!-- cache_translation_check_bn_55cbc127801296bd8c63495880093469b0a6f13e01a00e4c9b42df754e511bc9 -->
```
        <source>&amp;Copy address</source>
        <translation>ঠিকানা কপি করুন</translation>
    
ERR
The '&' indicating the shortcut key from the source text is missing in the Bengali translation. It should appear exactly once in the translation.

Correct translation:
&ঠিকানা কপি করুন
```

<!-- cache_translation_check_bn_6285b845fcc2bc8d8455413f9e44dc9ce825833e0ba97df87f048941c57d55de -->
```
        <source>Copy &amp;amount</source>
        <translation>কপি পরিমাণ</translation>
    
ERR
The ampersand (&) indicating the shortcut key from the source ("Copy &amp;amount") is missing in the translation. The correct translation should include it exactly once, consistent with shortcut conventions. 

Correct translation:
&amp;পরিমাণ কপি করুন
```

<!-- cache_translation_check_bn_cbeafd180baa2c6221dff3a7952e17bc2dff88f198ef17222d658e664dc9916e -->
```
        <source>Label</source>
        <translation>টিকেট</translation>
    
ERR
The translation is incorrect. "Label" should be translated as "লেবেল" or "চিহ্ন", not "টিকেট" (which means "ticket" in Bengali).

Correct translation:
লেবেল
```

<!-- cache_translation_check_bn_55cbc127801296bd8c63495880093469b0a6f13e01a00e4c9b42df754e511bc9 -->
```
        <source>&amp;Copy address</source>
        <translation>ঠিকানা কপি করুন</translation>
    
ERR
The '&' indicating the shortcut key from the source text is missing in the Bengali translation. It should appear exactly once in the translation.

Correct translation:
&ঠিকানা কপি করুন
```

<!-- cache_translation_check_bn_36a7168b79362233d9426fc37a1e2953a789a7e3529023d6d0c77a08634a110a -->
```
        <source>Copy &amp;label</source>
        <translation>কপি লেবেল</translation>
    
ERR
The translation "কপি লেবেল" is missing the ampersand (&) character, which denotes the shortcut key in the original English string. The ampersand should be present exactly once in the translation.

Correct translation:
কপি &লেবেল
or
&কপি লেবেল

Either placement is allowed as per shortcut conventions, but the ampersand must appear exactly once.
```

<!-- cache_translation_check_bn_6285b845fcc2bc8d8455413f9e44dc9ce825833e0ba97df87f048941c57d55de -->
```
        <source>Copy &amp;amount</source>
        <translation>কপি পরিমাণ</translation>
    
ERR
The ampersand (&) indicating the shortcut key from the source ("Copy &amp;amount") is missing in the translation. The correct translation should include it exactly once, consistent with shortcut conventions. 

Correct translation:
&amp;পরিমাণ কপি করুন
```

<!-- cache_translation_check_bn_32290be196f3d5c6942b0ba5047a253a85f6f37b647a110e67453eec56cd20fa -->
```
        <source>Settings file could not be read</source>
        <translation>Settingsসেটিংস ফাইল পড়া যাবে না।fileসেটিংস ফাইল পড়া যাবে না।couldসেটিংস ফাইল পড়া যাবে না।notসেটিংস ফাইল পড়া যাবে না।beসেটিংস ফাইল পড়া যাবে না।read</translation>
    
ERR
The translation is problematic. It includes repeated segments in both English and Bengali, making it incoherent and incorrect. The correct Bengali translation should be concise and fully translated:

Correct translation:
সেটিংস ফাইল পড়া যাবে না।
```
</details>

Number of issues: 36.
