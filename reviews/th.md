# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>th</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bth%5D%20request)


<!-- cache_translation_check_th_f5c1985b691d1ea2c80502e0c0b00927d33d92ad2b9cc2c3005677a9ce8829e7 -->
```
        <source>C&amp;hoose</source>
        <translation>เลือก</translation>
    
ERR
The translation is missing the required shortcut marker '&' from the source. Also check placement so the shortcut applies to a visible character (avoid putting & in front of the vowel sign).

Correct translation suggestion:
<translation>เ&ลือก</translation>
```

<!-- cache_translation_check_th_8aff7c93af644f5e8d212ee89c2ec7df72290c6eaf5bdcbb5f032f0689bf4273 -->
```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>นี่คือลิงก์ที่อยู่ Bitcoin ของคุณสำหรับการส่งการชำระเงิน ควรตรวจสอบจำนวนเงินและที่อยู่ผู้รับก่อนการส่งเหรียญ</translation>
    
ERR
The translation introduces the word "ลิงก์" (link), which is not present in the English source and changes the meaning. The source talks about "Bitcoin addresses", not links. The rest is mostly fine, but "ส่งการชำระเงิน" is somewhat redundant ('ส่ง' already implies sending).

Correct translation:
นี่คือที่อยู่ Bitcoin ของคุณสำหรับการส่งการชำระเงิน กรุณาตรวจสอบจำนวนเงินและที่อยู่ผู้รับทุกครั้งก่อนส่งเหรียญ
```

<!-- cache_translation_check_th_5bbe70a9b626c6c44d03aacceb29a577132c8b04a8b7706c3cc5724f7b18b0af -->
```
        <source>&amp;Copy Address</source>
        <translation>ที่อยู่</translation>
    
ERR
The translation "ที่อยู่" means just "Address" and omits the verb "Copy" and the required shortcut marker (&). It therefore does not match the source "%&Copy Address".

Correct translation (include exactly one & for the shortcut), for example:
&คัดลอกที่อยู่
```

<!-- cache_translation_check_th_59f9d62bce8a56d6302ba7eb46ec0f32d6afb6ce3ed5d71a54e85c5247923ec0 -->
```
        <source>Copy &amp;Label</source>
        <translation>คัดลอกและติดป้ายกำกับ</translation>
    
ERR
The translation is understandable Thai but it omits the required shortcut ampersand (&) present in the source. The source has "Copy &Label" (one &), so the translation must include exactly one & to indicate the shortcut. No other problems (spacing, wording) besides the missing &.

Suggested correction:
คัดลอก &ป้ายกำกับ
```

<!-- cache_translation_check_th_eb7717d1384ad01fcdd5552b8627200e941816fb988e1ea2f27060bdf60c33e0 -->
```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
ERR
The translation is incorrect. "การส่งออกล้มเหลว" means "Export failed", which is unrelated to "Label".

Correct translation:
ป้ายกำกับ
```

<!-- cache_translation_check_th_ddf8b12aba40177bb9b97f7e81a8564db4f5fad1d18934d69189238362726e5b -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>ป้อนวลีรหัสใหม่สำหรับกระเป๋าสตางค์. 1.กรุณาใช้วลีรหัสผ่านของ 2.สิบตัวอักษรสุ่มหรือมากกว่า 2,หรือ 3แปดคำหรือมากกว่านั้น3</translation>
    
ERR
The Thai translation is inaccurate and contains several issues:
- Stray numbers are inserted (e.g., "1.", "2.", "2,", "3", "3") which do not belong.
- The sentence structure is fragmented and unclear.
- The formatting with <br/> and <b> from the original is missing.
- The numbering ("1.", "2.") is not present in the source.
- It does not fluently convey the meaning of using at least ten random characters or at least eight words.
- The double space after the period.

Correct translation:
กรุณากรอกรหัสผ่านใหม่สำหรับกระเป๋าสตางค์ของคุณ &lt;br/&gt;โปรดใช้รหัสผ่านที่มี &lt;b&gt;อักขระสุ่มสิบตัวขึ้นไป&lt;/b&gt; หรือ &lt;b&gt;อย่างน้อยแปดคำ&lt;/b&gt;
```

<!-- cache_translation_check_th_057e7c30d72f621c6c858fbdab3309cf018e833c9d0130e2af8c6f300dd53e64 -->
```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>เกิดข้อผิดพลาดร้ายแรง กรุณาตรวจสอบว่าไฟล์การตั้งค่าสามารถเขียนได้หรือไม่ หรือลองรันด้วยคำสั่ง</translation>
    
ERR
The translation is incomplete and omits the part "with -nosettings." from the end of the sentence. This can mislead users who need to know about the -nosettings option. Also, it would be clearer to specify the switch as "-nosettings" in the translation.

Correct translation:
เกิดข้อผิดพลาดร้ายแรง กรุณาตรวจสอบว่าไฟล์การตั้งค่าสามารถเขียนได้หรือไม่ หรือลองรันด้วย -nosettings
```

<!-- cache_translation_check_th_d471c81326d47933477f0682c13a63f742019f94818200d3510c69098b72a85c -->
```
        <source>Ctrl+W</source>
        <translation>คีย์ลัด Ctrl+W (pronounced "kee lat Ctrl+W")</translation>
    
ERR
The translation includes an unnecessary phonetic pronunciation guide in English parentheses which is not present in the source and is inappropriate for a shortcut key label. Shortcut labels should be concise.

Correct translation:
Ctrl+W
```

<!-- cache_translation_check_th_94f53fcd1a7167d7e69027a7c82cb05521ffec1dfa762816e0a1296631cac38d -->
```
        <source>CJDNS</source>
        <comment>network name</comment>
        <extracomment>Name of CJDNS network in peer info</extracomment>
        <translation>CJDNS (แปลงชื่อย่อ)</translation>
    
ERR
The addition "(แปลงชื่อย่อ)" translates as "(acronym translation)", which is unnecessary and potentially confusing since "CJDNS" is a proper name that should not be expanded or explained in this context.

Correct translation:
CJDNS
```

<!-- cache_translation_check_th_978894330944ceb0305bf086aab1f1f4e0c2113ea08b645e5d243ff41ced2a36 -->
```
        <source>Outbound</source>
        <extracomment>An outbound connection to a peer. An outbound connection is a connection initiated by us.</extracomment>
        <translation>ออกเดินทาง (òk dern thāng)</translation>
    
ERR
The translation "ออกเดินทาง (òk dern thāng)" means "to depart" or "departing", which is not accurate in this technical context. Here, "Outbound" refers to a network connection initiated by the user or system, not physical departure.

Correct translation:
ขาออก

This term is standard in networking contexts to indicate "outbound" connections.
```

<!-- cache_translation_check_th_e2607314bddd809d81725f421e1cb6e12d2ade831bdbe67f6d7a69ff1c9c8edf -->
```
        <source>Full Relay</source>
        <extracomment>Peer connection type that relays all network information.</extracomment>
        <translation>การแข่งขันรีเลย์เต็มรูปแบบ</translation>
    
ERR
The translation is inaccurate. "การแข่งขันรีเลย์เต็มรูปแบบ" translates to "Full relay competition," which is incorrect. The term "Full Relay" in the context of Bitcoin peer connection refers to a node that relays all network information, not a competition.

Correct translation:
รีเลย์เต็มรูปแบบ

This directly conveys the technical meaning without adding unintended wording.
```

<!-- cache_translation_check_th_e13ccb3fa41ae5fb5064e8f1f809f658e5ca5501773d98914798b6f12926dfe8 -->
```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>การวิ่งผลัดบล็อก</translation>
    
ERR
The translation "การวิ่งผลัดบล็อก" literally means "block relay" in the context of a relay race, which is not suitable for the technical context of a peer connection type in the Bitcoin network. It should refer to relaying block information across the network, not a physical relay race.

Correct translation:
ถ่ายทอดบล็อก

This translation accurately captures the concept of relaying block information in a network context.
```

<!-- cache_translation_check_th_d75926d88016ebe91fc1e6a4f0bbbc7357adf34b9ad4dad12fe3f68b4a683586 -->
```
        <source>%1 GB</source>
        <translation>%1 จิกะไบต์</translation>
    
ERR
The Thai word "จิกะไบต์" is a misspelling. The format specifier "%1" and spacing are fine, but the unit should be written as "กิกะไบต์" (or you can keep the English abbreviation "GB").

Correct translation suggestions:
%1 กิกะไบต์
or
%1 GB
```

<!-- cache_translation_check_th_553ff3db987cf7d5983a9f6348ee14e11bc0f6f10ccc461f19893e95f22ec5d6 -->
```
        <source>&amp;Overview</source>
        <translation> ภาพรวม</translation>
    
ERR
Issues:
- Missing shortcut indicator '&' that exists in source (must appear exactly once).
- Leading extra space before the word.
Correct translation:
&amp;ภาพรวม
```

<!-- cache_translation_check_th_684364758bf176819ac286b2e65320fd2d7ef537e8c960da4271458f6c5fa243 -->
```
        <source>&amp;Transactions</source>
        <translation>ธุรกรรม</translation>
    
ERR
The source includes a single '&' indicating a shortcut key; the translation drops it. Also no other issues with wording — "ธุรกรรม" correctly means "Transactions" in Thai.

Correct translation (include '&' exactly once):
&amp;ธุรกรรม
```

<!-- cache_translation_check_th_8457e6d6dd7b76364cdc11fa96f964a84b0f316057b22d34e040c12ddc94254f -->
```
        <source>E&amp;xit</source>
        <translation> ออก</translation>
    
ERR
Problems:
- The translation has a leading space before the word "ออก".
- It does not include the required single '&' accelerator marker from the source.

Correct translation (ampersand included exactly once, no extra spaces):
&ออก
```

<!-- cache_translation_check_th_746ab8d924ecdda103b58dabecb20d7a13f9d7ff237c4ca9ff3445d74e95ffa7 -->
```
        <source>&amp;About %1</source>
        <translation> เกี่ยวกับ %1</translation>
    
ERR
Problems:
- The translation has a leading stray space before the Thai text.
- The source contains a single '&' indicating a keyboard shortcut; the translation must also include exactly one '&' but it is missing.

Correct translation (include single '&' and remove leading space):
&เกี่ยวกับ %1
```

<!-- cache_translation_check_th_ac3f0a7106c0394004610c6ec40e9136d00bb1f41e5f36c83a5339d94e8aab73 -->
```
        <source>&amp;Minimize</source>
        <translation>ย่อ</translation>
    
ERR
The source contains an ampersand (&) indicating a keyboard shortcut and the translation does not include it. Also there are no other formatting issues.

Correct translation:
&amp;ย่อ
```

<!-- cache_translation_check_th_6ecd3098d3190b1a1214835d381f6a7822be45d9bae4a12e653e9300c19e9337 -->
```
        <source>&amp;Send</source>
        <translation>ส่ง</translation>
    
ERR
The source contains an ampersand (&) marking a keyboard shortcut ("&Send") but the Thai translation "ส่ง" omits it. Add a single & in the translation.

Correct translation:
&amp;ส่ง
```

<!-- cache_translation_check_th_77597f82c4c92ec479071d59874ae448332afa84f86b271ed0680394cee344c3 -->
```
        <source>&amp;Receive</source>
        <translation>รับ</translation>
    
ERR
The source contains a shortcut marker '&' which must appear exactly once in the translation. The Thai translation is missing this marker.

Correct translation:
<translation>&amp;รับ</translation>
```

<!-- cache_translation_check_th_46b02e71ac032a94fea836f0c2a865f4de2d347ac5cabb78ea83cea474c2dda4 -->
```
        <source>&amp;Options…</source>
        <translation>ตัวเลือก</translation>
    
ERR
The translation is missing the shortcut ampersand (&) and the ellipsis (…) present in the source. Also there should be no extra whitespace.

Correct translation:
&amp;ตัวเลือก…
```

<!-- cache_translation_check_th_5aaf7679c6b4cf8312baf0c594229ab19ea5d7253e6e8712a3d0cf010919eb7d -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation>เข้ารหัสกระเป๋าเงิน</translation>
    
ERR
The translation is missing the shortcut indicator (&) and the trailing ellipsis (…) present in the source. Also no extra spaces should be added.

Correct translation:
&amp;เข้ารหัสกระเป๋าเงิน…
```

<!-- cache_translation_check_th_273113e46d27487d6cd3a4e58d9651dd6a9b52de634cb85f6b37223df70560aa -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>สำรองกระเป๋าเงิน</translation>
    
ERR
The translation is missing the shortcut ampersand (&) and the trailing ellipsis (…) from the source. It should include exactly one & to mark the accelerator and keep the ellipsis.

Correct translation:
&สำรองกระเป๋าเงิน…
```

<!-- cache_translation_check_th_d62814bdfc19a7a6eeb4c96d781d295825dabaa0b316405118ee2cc9367bad8f -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>เปลี่ยนรหัสผ่าน...</translation>
    
ERR
The translation is correct Thai for "Change Passphrase…" but it is missing the required shortcut marker (&). The source contains a single '&' to indicate the keyboard shortcut and the translation must include exactly one '&'. Also use the same ellipsis character if desired.

Correct translation:
&amp;เปลี่ยนรหัสผ่าน…
```

<!-- cache_translation_check_th_67f953c89ac90d088a038eaac462aec69f5c544f2a9d567584bf96bbae02fe9c -->
```
        <source>Sign &amp;message…</source>
        <translation>ป้าย &amp; ข้อความ…</translation>
    
ERR
The Thai word "ป้าย" is incorrect in this context — it means "label/sign (as a label)" rather than "sign (a message)". Also there is an extra space around the & marker. The ampersand should remain exactly once and be placed immediately before the shortcut character.

Correct translation:
<translation>ลงนาม &ข้อความ…</translation>
```

<!-- cache_translation_check_th_01eded9f7c68463b6a07573cb50d37ce9fce8e16d1729cce725357da50475c1e -->
```
        <source>&amp;Verify message…</source>
        <translation>ตรวจสอบข้อความ...</translation>
    
ERR
The Thai translation is correct in meaning ("verify message") but it is missing the shortcut ampersand (&) from the source and uses three ASCII dots instead of the single ellipsis character. The & must appear exactly once.

Correct translation:
&amp;ตรวจสอบข้อความ…
```

<!-- cache_translation_check_th_a4ee4ec0f962481dfe739f51e04391edae3978f8efb17d99febfeb611cd18b13 -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation> &amp;โหลด PSBT จากไฟล์…</translation>
    
ERR
There is an extra leading space before the ampersand in the translation (whitespace issue). The translation text otherwise is correct and & is used once. No format specifiers to worry about.

Correct translation (remove leading space):
<translation>&amp;โหลด PSBT จากไฟล์…</translation>
```

<!-- cache_translation_check_th_9e9bec442912b237b6d41da24b90ef24948f6a8d2092617ace24e2c5e167e78d -->
```
        <source>Show the list of used sending addresses and labels</source>
        <translation>แสดงรายการ ที่เก็บเงินที่จะส่ง bitcoin ออก และป้ายชื่อ ที่ใช้ไปแล้ว</translation>
    
ERR
The translation is awkward and contains unnecessary spaces. "ที่เก็บเงินที่จะส่ง bitcoin ออก" is a very verbose and literal way to translate "sending addresses", and the phrasing "ที่ใช้ไปแล้ว" (already used) is placed at the end, making the sentence structure confusing.

Correct translation:
แสดงรายการที่อยู่วิธีการส่งและป้ายชื่อที่ใช้แล้ว
```

<!-- cache_translation_check_th_df892cedffdcf7d3cccfc7411e2e0267a54d78a7e681fc036a29ba30ee59c998 -->
```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>แสดงรายการ ที่เก็บเงินที่จะรับ bitcoin เข้า และป้ายชื่อ ที่ใช้ไปแล้ว</translation>
    
ERR
The translation is awkwardly phrased and contains unnecessary spaces and word choices. The term "ที่เก็บเงินที่จะรับ bitcoin เข้า" (place to keep money to receive bitcoin in) is a very verbose way to translate "receiving addresses". A more standard and concise translation for "receiving addresses" in a Bitcoin context is "ที่อยู่สำหรับรับเงิน".

Correct translation:
แสดงรายการที่อยู่สำหรับรับเงินและป้ายชื่อที่ใช้ไปแล้ว
```

<!-- cache_translation_check_th_ebe9dec8116a4c12752f8444486e5e44c19d7cf0e0866a3f52d21f3b5526338d -->
```
        <source>&amp;Receiving addresses</source>
        <translation>&amp;ตัวเลือกคำสั่งในบรรทัดคำสั่ง</translation>
    
ERR
The translation is incorrect/irrelevant. The source "&Receiving addresses" refers to wallet receiving addresses. The Thai translation "&ตัวเลือกคำสั่งในบรรทัดคำสั่ง" means "&command line options", which is unrelated.

The ampersand (&) is present exactly once in both strings, which is fine, but the content is wrong.

Correct translation suggestions:
&ที่อยู่รับเงิน
or
&ที่อยู่สำหรับรับ
```

<!-- cache_translation_check_th_ff2d839ef397955de499afcb39a41d05911ea57328fec12884c5ccb8310ea3a2 -->
```
        <source>&amp;Mask values</source>
        <translation>&amp;ค่าหน้ากาก</translation>
    
ERR
The Thai text "&ค่าหน้ากาก" is understandable but unnatural: "ค่าหน้ากาก" is a literal "mask value" and not commonly used in Thai UI for the action "Mask values" (hide/obscure values). The ampersand is present exactly once (good) and there are no format-specifier or spacing issues.

Suggested better translations:
- &ซ่อนค่า
or
- &ปิดบังค่า

Both keep the shortcut marker and more naturally convey "Mask values" in Thai.
```

<!-- cache_translation_check_th_ed589ff88ff8741ed351d8f41a4f8a8af3794ba5530f7b506291fe48532c03be -->
```
        <source>&amp;Window</source>
        <translation>หน้าต่าง</translation>
    
ERR
The source contains a shortcut indicator "&" which must be included exactly once in the translation. The Thai translation "หน้าต่าง" is correct for "Window" but omits the "&".

Correct translation:
&amp;หน้าต่าง
```

<!-- cache_translation_check_th_f09f1d1b3c9781d9e67c0c3720753aa14a05d7c825d4db2540ac61c88929d0e8 -->
```
        <source>&amp;Hide</source>
        <translation>ซ่อน</translation>
    
ERR
The translation is missing the required '&' shortcut marker from the source. The source contains "&Hide" (one ampersand) and the translation must include exactly one '&' to indicate the shortcut key.

Correct translation:
&amp;ซ่อน
```

<!-- cache_translation_check_th_c3e838c8defc5399ad4a09ae0819f7dca459e11f91f2656b77a88d767c1ea04c -->
```
        <source>S&amp;how</source>
        <translation>แสดง</translation>
    
ERR
The translation is correct Thai ("แสดง" = "Show") but it is missing the required shortcut ampersand from the source (S&amp;how). Add a single & in the translation.

Correct translation (with ampersand):
แ&สดง
```

<!-- cache_translation_check_th_9f424cf24c9bc7ff525eb1ed8118c9cabe00e97b75c428841d5d7b4f5fb6db75 -->
```
        <source>Private key &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>กุญแจส่วนตัว &lt;b&gt;พิการ&lt;/b&gt;</translation>
    
ERR
The word "พิการ" in Thai means "disabled" as in "handicapped", which is not appropriate for "disabled" in the sense of "functionality turned off". A more appropriate word is "ถูกปิดใช้งาน" or "ปิดการใช้งาน".

Correct translation:
กุญแจส่วนตัว &lt;b&gt;ถูกปิดใช้งาน&lt;/b&gt;
```

<!-- cache_translation_check_th_28456f37398e516340b1c955245921c36eb974ceba65ded3777e5fcfb9871d1a -->
```
        <source>Change:</source>
        <translation>เปลี่ยน:</translation>
    
ERR
The Thai translation "เปลี่ยน:" is a verb meaning "change/modify" (as in to change something) and is misleading in the Bitcoin context where "Change:" refers to transaction change (the amount of money returned). No format specifiers or spacing issues.

Suggested correct translations:
- "เงินทอน:" 
- or more explicit: "จำนวนเงินทอน:"
```

<!-- cache_translation_check_th_139d8575fa4cbddb086ce17b6fe23ffeb7f17cbc2859d7e307a0d6f2d2a00942 -->
```
        <source>(un)select all</source>
        <translation>(un)เลือกทั้งหมด</translation>
    
ERR
The translation mixes English "un" with Thai text, which is inappropriate. It should present both actions in Thai.

Correct translations (choose one appropriate for the UI):
- "เลือก/ยกเลิกทั้งหมด"
- "(ยกเลิก)เลือกทั้งหมด"
```

<!-- cache_translation_check_th_c10898628db7331b7a87d0053a77d4c6475a58ef8d34818ee61ce26a2e552eb8 -->
```
        <source>Tree mode</source>
        <translation>โหมด แบบTree</translation>
    
ERR
The translation mixes Thai and English ("โหมด แบบTree") and has incorrect spacing. A natural Thai translation would be either "โหมดต้นไม้" or "โหมดแบบต้นไม้" (both convey "Tree mode" / "tree view").

Correct translation:
โหมดต้นไม้
```

<!-- cache_translation_check_th_b73eb09132e1261c9fbd55c950fec63f92d2766d82c6320d3e5ec776c93b8a38 -->
```
        <source>List mode</source>
        <translation>โหมด แบบรายการ</translation>
    
ERR
The Thai translation has an extra space and unnatural spacing: "โหมด แบบรายการ". Thai normally doesn't separate those words; it should be combined.

Correct translation:
โหมดรายการ
```

<!-- cache_translation_check_th_0d2b6fd39dd84cc8edd95667788eb78371a32f6906918c4efaa80aeb96e0431c -->
```
        <source>Received with label</source>
        <translation>รับ ด้วย เลเบล</translation>
    
ERR
The Thai is awkward and has incorrect spacing. It uses a transliteration "เลเบล" and places spaces between Thai words ("รับ ด้วย เลเบล"), which is not natural. There are no format specifiers to preserve, but the phrasing should be more natural.

Correct translation:
รับพร้อมป้ายกำกับ
```

<!-- cache_translation_check_th_265581d109384633a7a0a1dc7541fe646d7d4ac59018019985ee30aeaad2b334 -->
```
        <source>Received with address</source>
        <translation>รับ ด้วย แอดเดรส</translation>
    
ERR
The translation mixes Thai and an English loanword ("แอดเดรส") and has unnecessary spaces. Also spacing around words in Thai should be adjusted.

Suggested correction:
รับด้วยที่อยู่
```

<!-- cache_translation_check_th_040530838cf7c20394c394b9760228437e9486354a25aa4877d3f56123da55f6 -->
```
        <source>Confirmations</source>
        <translation>ทำการยืนยัน</translation>
    
ERR
The Thai translation "ทำการยืนยัน" is a verb phrase meaning "to perform/execute confirmation" and doesn't match the noun label "Confirmations" (count/status). Recommend using a noun form.

Correct translation:
การยืนยัน

(If you need to emphasize the count/number of confirmations, use "จำนวนการยืนยัน".)
```

<!-- cache_translation_check_th_54360120e54fd5714bd30aa5649fd4db30f9e73836708bb6228f6325c9ceebd1 -->
```
        <source>Copy bytes</source>
        <translation>คัดลอก bytes</translation>
    
ERR
The translation mixes Thai and English ("bytes") and has an unnecessary space. Better to use the Thai word for bytes and no extra space.

Correct translation:
คัดลอกไบต์
```

<!-- cache_translation_check_th_a32f34aa61f3a9e6f4f8d4be78e43e28f8fbd7a446a1ca1772eb220a44474400 -->
```
        <source>Copy change</source>
        <translation>คัดลอก change</translation>
    
ERR
The translation mixes Thai and English ("คัดลอก change") instead of translating "change". No format specifiers or whitespace issues, but it should be fully translated and context-aware (in Bitcoin "change" usually means the change amount or change address).

Correct translation (if meaning the change address):
คัดลอกที่อยู่เงินทอน

Or, if it means the change amount:
คัดลอกยอดเงินทอน
```

<!-- cache_translation_check_th_6cfe1a123c41bb8d1521d6977e846a3e516ad36bba97f4826e20fd00556f4b38 -->
```
        <source>Form</source>
        <translation>จาก</translation>
    
ERR
The translation is inaccurate. "Form" in English means a document with fields to fill in (like in software), but "จาก" in Thai means "from" (the preposition). The correct translation for "Form" (as in a user or input form) is "ฟอร์ม" or "แบบฟอร์ม".

Correct translation:
ฟอร์ม
or
แบบฟอร์ม
```

<!-- cache_translation_check_th_579ee7dbe84c05de37d741f19044bff79a4ae80b11d1c556d051e129d107841f -->
```
        <source>&amp;Start %1 on system login</source>
        <translation>เริ่ม %1 เมื่อเข้าสู่ระบบ</translation>
    
ERR
The translation is accurate Thai and preserves "%1", but it is missing the required shortcut ampersand (&) from the source. The source contains a single & to indicate a keyboard shortcut and the translation must include exactly one &.

Correct translation:
&เริ่ม %1 เมื่อเข้าสู่ระบบ
```

<!-- cache_translation_check_th_9272e860b73ddc980dfa0f325c31308bc5d14b50c75489e750bd74efc386f885 -->
```
        <source>Size of &amp;database cache</source>
        <translation>ขนาดของแคชฐานข้อมูล</translation>
    
ERR
The translation is correct Thai but it is missing the shortcut ampersand (&) that appears in the source. There are no format specifiers or spacing issues otherwise.

Correct translation (with & included, placed before "ฐาน" to mark the equivalent of "&database"):
<translation>ขนาดของแคช&ฐานข้อมูล</translation>
```

<!-- cache_translation_check_th_97a71466a06d9ee7268a69cdad971da167905d84a6875df5ff9fc680009d6513 -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>จำนวนของสคริปต์และเธรดการตรวจสอบ</translation>
    
ERR
The translation is incorrect because it renders the ampersand shortcut as the Thai word "และ" ("and") instead of keeping a single '&' to mark the shortcut. Also the phrasing is slightly awkward.

Correct translation (with a single '&' for the shortcut):
จำนวนเธรดการ&ตรวจสอบสคริปต์
```

<!-- cache_translation_check_th_de2cc2573714bd220b8e27505d96054a0c4334a02f63f78fc67192b7b952b1c8 -->
```
        <source>&amp;Reset Options</source>
        <translation>ตัวเลือกการรีเซ็ต</translation>
    
ERR
The translation is missing the shortcut marker '&' that appears in the source. Also word order can be more natural.

Correct translation (include & exactly once):
&รีเซ็ตตัวเลือก
```

<!-- cache_translation_check_th_7147333f5479ed96770308d942641421f81f1f169ec3c6d5fdf5372fd7d209cc -->
```
        <source>&amp;Network</source>
        <translation>และเครือข่าย</translation>
    
ERR
The translation uses the Thai word "และ" ("and") instead of the ampersand shortcut marker (&) and so does not preserve the required '&' keyboard mnemonic. Also the source is just "Network" (with &), not "and Network".

Correct translation:
&amp;เครือข่าย
```

<!-- cache_translation_check_th_c2c9b1a2039c35742266e72080d0952db9f60aceaeddec951f101ab1e05005b9 -->
```
        <source>Prune &amp;block storage to</source>
        <translation>ตัดทอนและบล็อกที่เก็บข้อมูลไปที่</translation>
    
ERR
The Thai translation is incorrect and misleading. The source "Prune &block storage to" uses "&" as a UI accelerator before "block" (not the word "and"), and the current translation "ตัดทอนและบล็อกที่เก็บข้อมูลไปที่" incorrectly inserts "และ" (meaning "and") and is awkward/ungrammatical.

Corrected translation (with a single & used for the shortcut, placed before "บล็อก"):
ตัดแต่ง &บล็อกที่เก็บข้อมูลให้เหลือ

This preserves the meaning ("Prune block storage to ...") and uses & exactly once.
```

<!-- cache_translation_check_th_279f5516837ae3aba4a18386b2581b4c9de408e0fd641c84b7f309aa61cb0902 -->
```
        <source>GB</source>
        <translation>กิกะไบต์ (gí-ga-bàyt)</translation>
    
ERR
The translation expands the abbreviation "GB" to the Thai word for gigabyte but adds an unnecessary and nonstandard phonetic "(gí-ga-bàyt)" using diacritics not used in Thai transliteration. If the original intends the abbreviation, keep "GB" or use the Thai term with the standard abbreviation.

Correct translations (choose one depending on context):
- GB
- กิกะไบต์ (GB)
- กิกะไบต์
```

<!-- cache_translation_check_th_4c9da46370d1f6578b659c045cd6e0c1da9ceca4707164a3d22af22031a9f2fe -->
```
        <source>W&amp;allet</source>
        <translation>วอลเล็ท (Wol-let)</translation>
    
ERR
Problems:
- The translation omits the keyboard shortcut marker (&). The source contains one & and the translation must include exactly one.
- The translation includes an unnecessary phonetic "(Wol-let)". UI labels should not include pronunciations.
- Prefer a natural Thai term for "Wallet" (e.g. "วอลเล็ต" or "กระเป๋าเงิน").

Correct translation (example using a single & and a natural Thai label):
วอลเล็ต with &:
&วอลเล็ต

Or using the more literal Thai term:
&กระเป๋าเงิน
```

<!-- cache_translation_check_th_a19cafd035eb1ceedde42cb05fbd628c2d5b8a780135618ad0cbc263c8ce6751 -->
```
        <source>Expert</source>
        <translation>ผู้เชี่ยวชาญ (phoo-chiao-chaan)</translation>
    
ERR
The translation includes an unnecessary romanization in parentheses. The Thai word "ผู้เชี่ยวชาญ" is correct by itself; the phonetic "(phoo-chiao-chaan)" should be removed.

Correct translation:
ผู้เชี่ยวชาญ
```

<!-- cache_translation_check_th_db76e90c19a527e77055def9a0e5578168ce092b459fe21674738c234336fa12 -->
```
        <source>Enable coin &amp;control features</source>
        <translation>เปิดใช้งานคุณสมบัติการควบคุมเหรียญ</translation>
    
ERR
The translation is accurate Thai but it is missing the single '&' used for the shortcut key from the source. The '&' must appear exactly once in the translation.

Correct translation (with & placed before "ควบคุม"):
เปิดใช้งานคุณสมบัติการ&ควบคุมเหรียญ
```

<!-- cache_translation_check_th_6f04d3eef30a2a77ace73700df5d10e59af133d5770ac89739beb840b46ac178 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>ใช้จ่ายเงินทอนที่ยังไม่ได้ยืนยัน</translation>
    
ERR
The translation correctly conveys the meaning but is missing the shortcut marker '&' from the source. The source contains a single '&' and the translation must include exactly one '&' as well.

Correct translation (with ampersand):
&amp;ใช้จ่ายเงินทอนที่ยังไม่ได้ยืนยัน
```

<!-- cache_translation_check_th_30b45c7ad3ac27f112c92fa4a3180bee5b33fc14c1af8ae14d2c8f43995c002c -->
```
        <source>&amp;External signer script path</source>
        <translation>เส้นทางสคริปต์เซ็นชื่อภายนอก</translation>
    
ERR
The translation is correct in meaning but is missing the required shortcut marker '&' from the source (there must be exactly one '&' in the translation). No format specifiers are present.

Correct translation (with '&' added):
&amp;เส้นทางสคริปต์เซ็นชื่อภายนอก
```

<!-- cache_translation_check_th_ac0416c9931b11876d5d5577612f54303cf4cbeb9fdbcb28eb2a2da68893e28b -->
```
        <source>Accept connections from outside.</source>
        <translation>ยอมรับการเชื่อมต่อจากภายนอก (Yom rap kan cheuam tor chak phai nok)</translation>
    
ERR
The Thai translation text is correct, but it improperly includes a parenthetical romanization "(Yom rap ...)" which is unnecessary and should not appear in the translation string.

Correct translation:
ยอมรับการเชื่อมต่อจากภายนอก
```

<!-- cache_translation_check_th_28090b9d71bd53095ae93a4d2ec2b851135fb938b1c190c278cfe9e6b2894ae4 -->
```
        <source>Allow incomin&amp;g connections</source>
        <translation>อนุญาตการเชื่อมต่อที่เข้ามา (Anuyat kan cheuamto thi khaoma)</translation>
    
ERR
Problems:
- The translation includes an unnecessary Latin transliteration in parentheses; UI strings should not contain that.
- The ampersand (&) used for the keyboard shortcut in the source is missing in the translation. Exactly one & must appear.
- No format specifiers here, but the & must be preserved.

Correct translation (Thai, no extraneous transliteration, one & used):
&อนุญาตการเชื่อมต่อขาเข้า
```

<!-- cache_translation_check_th_5ceee0d589ec0ce5819dbbe32fd25d2f1a132722029a22ca2cd2da6bbb71a13e -->
```
        <source>&amp;Connect through SOCKS5 proxy (default proxy):</source>
        <translation>เชื่อมต่อผ่านพร็อกซี่ SOCKS5 (พร็อกซี่เริ่มต้น):</translation>
    
ERR
The source contains a single '&' indicating a shortcut key; the Thai translation is missing the '&'. No other issues.

Correct translation (with '&' added):
&amp;เชื่อมต่อผ่านพร็อกซี่ SOCKS5 (พร็อกซี่เริ่มต้น):
```

<!-- cache_translation_check_th_62bc215580f3af4ee11eba9eb14f1ccf62674ead515d69d8ce5842fbd94aa458 -->
```
        <source>Proxy &amp;IP:</source>
        <translation>พร็อกซี &amp; ไอพี</translation>
    
ERR
Problems:
- The translation is missing the trailing colon ":" from the source.
- It uses an HTML entity "&amp;" and adds a space after it ("&amp; ไอพี"), which is incorrect for the shortcut marker; the source uses a single "&" to mark the shortcut and it should appear exactly once without an extra space.
- Prefer to place the & directly before the shortcut text (no space) and include the colon.

Correct translation:
พร็อกซี &ไอพี:
```

<!-- cache_translation_check_th_16d296120fb7a7266c578133cacbf3e12b370c961d047c5a075964bb9fed292e -->
```
        <source>&amp;Port:</source>
        <translation>ท่าเรือ (thaa ruea)</translation>
    
ERR
The translation is problematic: it omits the required shortcut marker (&), adds an unnecessary Romanization in parentheses, and uses a less common literal "ท่าเรือ" (which usually means a ship port) instead of the common UI term for "Port" (พอร์ต). Also ensure the ampersand appears exactly once.

Correct translation:
&พอร์ต:
```

<!-- cache_translation_check_th_f80dbf2f57a384d7129410a458e556ad0f63a050ca15a88755a72e2f5e05fc19 -->
```
        <source>Port of the proxy (e.g. 9050)</source>
        <translation>พอร์ตของพร็อกซี (เช่น 9050)
 
4o mini</translation>
    
SPAM
The translation includes unrelated/additional text ("4o mini") and stray whitespace/newlines after the correct Thai phrase.

Correct translation:
พอร์ตของพร็อกซี (เช่น 9050)
```

<!-- cache_translation_check_th_ed589ff88ff8741ed351d8f41a4f8a8af3794ba5530f7b506291fe48532c03be -->
```
        <source>&amp;Window</source>
        <translation>หน้าต่าง</translation>
    
ERR
The source contains a shortcut indicator "&" which must be included exactly once in the translation. The Thai translation "หน้าต่าง" is correct for "Window" but omits the "&".

Correct translation:
&amp;หน้าต่าง
```

<!-- cache_translation_check_th_880f1a73571edad0a272ef0e2e39677ab552b1fdd9b6c8171679ea3f5c14fddc -->
```
        <source>&amp;Show tray icon</source>
        <translation>แสดงไอคอนถาด</translation>
    
ERR
The translation is missing the shortcut marker (&). Also a more natural phrasing in Thai would include "ใน" (in) but that's optional.

Suggested corrections (include a single &):
&แสดงไอคอนถาด

Or, more natural:
&แสดงไอคอนในถาด
```

<!-- cache_translation_check_th_d2f545bb0437e5a143a467984946d3940e44aef04f11ce84b0d973f726068784 -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>ย่อไปที่ถาดแทนที่จะเป็นแถบงาน</translation>
    
ERR
The translation is accurate Thai, but it is missing the required single '&' shortcut marker from the source. No other issues found.

Correct translation (with one '&'):
&ย่อไปที่ถาดแทนที่จะเป็นแถบงาน
```

<!-- cache_translation_check_th_7e95d0765e68896b2eb9e6bf844e2c6159a271163677e522bf3364e900dbd63d -->
```
        <source>M&amp;inimize on close</source>
        <translation>ลดขนาดเมื่อปิด (Lòt khānāt muea pìd)</translation>
    
ERR
Problems:
- The translation includes an unnecessary romanization in parentheses ("(Lòt khānāt muea pìd)"), which should not be present.
- The source contains a single ampersand (&) indicating a keyboard shortcut; the translation must include exactly one & as well (it is missing).
- Minor phrasing: a more natural Thai rendering is preferred.

Correct translation (with single & for the shortcut):
&ย่อเมื่อปิด
```

<!-- cache_translation_check_th_292fd5548d081612ce72fbad4b7feea0e0b9d8406fdec09420eee9f30cfebf36 -->
```
        <source>&amp;Display</source>
        <translation>แสดงผล</translation>
    
ERR
The source contains a single & indicating a keyboard shortcut (&Display) but the Thai translation "แสดงผล" omits the &. Add the & exactly once. Correct translation example:

&แสดงผล
```

<!-- cache_translation_check_th_ded8d4aa4fbb221bc3581711c38627834ce3280a5d52ef254cb8d019f8be5e4f -->
```
        <source>User Interface &amp;language:</source>
        <translation>อินเตอร์เฟซผู้ใช้ &amp; ภาษา</translation>
    
ERR
The translation is awkward and misses the trailing colon. It reads "อินเตอร์เฟซผู้ใช้ & ภาษา" ("user interface & language") rather than "User Interface language:", and the colon ":" from the source is omitted. Also prefer placing the accelerator (&) directly before the translated word.

Correct translation:
&amp;ภาษาอินเทอร์เฟซผู้ใช้:
```

<!-- cache_translation_check_th_414b8f8248611f07886dc5e8a620e1a6c2a7377ccf28c5752b727d339f682565 -->
```
        <source>&amp;Unit to show amounts in:</source>
        <translation>หน่วยที่จะแสดงจำนวนใน:</translation>
    
ERR
The translation into Thai is correct in meaning but is missing the required single '&' accelerator present in the source. Also a slightly more natural phrasing is "หน่วยที่ใช้แสดงจำนวน:".

Correct translation (with ampersand for shortcut):
&amp;หน่วยที่ใช้แสดงจำนวน:
```

<!-- cache_translation_check_th_598c24c6ff398efce71d1d72d8b7f37e8c91678f06799b6a80fa81e9cb5d2b58 -->
```
        <source>&amp;Third-party transaction URLs</source>
        <translation>ลิงก์ธุรกรรมของบุคคลที่สาม</translation>
    
ERR
The translation is accurate in meaning, but it omits the required shortcut indicator (&) present in the source. The source has a single '&' which must be carried over exactly once into the translation.

Correct translation (include & once):
&ลิงก์ธุรกรรมของบุคคลที่สาม
```

<!-- cache_translation_check_th_6b7cdfff333a3c1a2a3b091c92b32ea4876e765186909b9d683ac426e6c329f7 -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>ใช้พร็อกซี่ SOCKS5 แยกต่างหากเพื่อเชื่อมต่อกับเพื่อนผ่านบริการ Tor onion</translation>
    
ERR
Problems:
- The source contains a single '&' (as SOCKS&amp;5) indicating a shortcut; the Thai translation omits the '&'. The translation must include exactly one '&'.
- The source ends with a colon ':' but the translation omitted it.
- "peers" is translated as "เพื่อน" (friends), which is ambiguous in this technical/Bitcoin context; use a term like "เพียร์" or "ผู้ร่วมเครือข่าย" to reflect network peers.
- Minor wording: "บริการ Tor onion" is understandable but more natural is "บริการ .onion ของ Tor".

Correct translation:
ใช้พร็อกซี่ SOCKS&5 แยกต่างหากเพื่อเชื่อมต่อกับเพียร์ผ่านบริการ .onion ของ Tor:
```

<!-- cache_translation_check_th_5cb7490369a88bb982c3802cc90ac290e426aee476f901e8f14f3c43d7714a93 -->
```
        <source>&amp;OK</source>
        <translation>โอเค</translation>
    
ERR
The translation is missing the required shortcut indicator "&" from the source. The source has "&OK" (one ampersand), so the translation must include exactly one "&" as well.

Correct translation examples:
&โอเค
or more naturally in Thai:
&ตกลง
```

<!-- cache_translation_check_th_13431f526fa055277394750c44ae5b82b1036c52247852557e085b2bd05e2fcb -->
```
        <source>&amp;Cancel</source>
        <translation>ยกเลิก</translation>
    
ERR
The translation is missing the shortcut marker "&" from the source. The source contains "&Cancel" so the translation must include a single "&" before the chosen shortcut character (commonly the first character).

Correct translation:
<translation>&ยกเลิก</translation>
```

<!-- cache_translation_check_th_6cfe1a123c41bb8d1521d6977e846a3e516ad36bba97f4826e20fd00556f4b38 -->
```
        <source>Form</source>
        <translation>จาก</translation>
    
ERR
The translation is inaccurate. "Form" in English means a document with fields to fill in (like in software), but "จาก" in Thai means "from" (the preposition). The correct translation for "Form" (as in a user or input form) is "ฟอร์ม" or "แบบฟอร์ม".

Correct translation:
ฟอร์ม
or
แบบฟอร์ม
```

<!-- cache_translation_check_th_02574fb72bfbb0cfa7165905554d7364990c35bda753f6a21713fa1e7ebdf136 -->
```
        <source>Could not sign any more inputs.</source>
        <translation>ไม่สามารถลงนามการป้อนข้อมูลเพิ่มเติมได้ (Mai samart long nam kan phon khomooht permum dai).</translation>
    
ERR
The translation contains a parenthetical transliteration "(Mai samart long nam kan phon khomooht permum dai)", which is not standard for professional UI/localization and is unnecessary. Only the Thai script translation should be provided. 

Correct translation:
ไม่สามารถลงนามการป้อนข้อมูลเพิ่มเติมได้
```

<!-- cache_translation_check_th_ca934886c522efc861fcf00e65d7d27a5b76f5126e8de6feb5033385a7499f88 -->
```
        <source>User Agent</source>
        <extracomment>Title of Peers Table column which contains the peer's User Agent string.</extracomment>
        <translation>ตัวแทนผู้ใช้
(Pronounced: Dtua-Thaen Phu-Chai)</translation>
    
ERR
The translation "ตัวแทนผู้ใช้ (Pronounced: Dtua-Thaen Phu-Chai)" is not appropriate. "ตัวแทนผู้ใช้" is a literal/awkward rendering of "User Agent" (meaning "user representative") and the parenthetical pronunciation in Latin letters must not be included in a UI translation string.

Correct translations (choose one depending on preferred style):
- User Agent
- User Agent ของเพียร์
- สตริง User Agent

Recommended replacement:
<translation>User Agent</translation>
```

<!-- cache_translation_check_th_8378a6602a60bf9698e01e4e3fb4676d9bf48207a006cffd6b0b0ba1999606b3 -->
```
        <source>Ping</source>
        <extracomment>Title of Peers Table column which indicates the current latency of the connection with the peer.</extracomment>
        <translation>พิง (pronounced ping)</translation>
    
ERR
The Thai translation is problematic. It uses "พิง" which in Thai means "to lean" and is not an appropriate transliteration for the network term "Ping". It also leaves the English parenthetical "(pronounced ping)" which is unnecessary and inconsistent with typical UI translations.

Correct translations (choose one depending on preferred style):
- Ping
- Ping (ความหน่วง)
- ค่า Ping
```

<!-- cache_translation_check_th_701faa4eec04d88143d245b42167cecb03bab06235926230fb5239376f22eade -->
```
        <source>Network</source>
        <extracomment>Title of Peers Table column which states the network the peer connected through.</extracomment>
        <translation>เครือข่าย (pronounced "kruea-khai")</translation>
    
ERR
The translation includes a pronunciation guide in English, which is unnecessary and inappropriate for a software interface translation. Only the translated term should be provided.

Correct translation:
เครือข่าย
```

<!-- cache_translation_check_th_eb71d49fb6ff585d80d379efdcbeceae0e65b54a7ff17d711c0ce334f575a43a -->
```
        <source>Outbound</source>
        <extracomment>An Outbound Connection to a Peer.</extracomment>
        <translation>ออกเดินทาง (òk dern thāng)</translation>
    
ERR
The translation "ออกเดินทาง (òk dern thāng)" means "depart" or "set off", which is incorrect in this context. In the context of network connections, "Outbound" typically means "ขาออก" or "ภายนอก" in Thai.

Correct translation:
ขาออก
```

<!-- cache_translation_check_th_4db982722b59469280f31d418d6690ffa6ab4edc767dbddd87f457c98518d0c2 -->
```
        <source>&amp;Reset</source>
        <translation>รีเซ็ต</translation>
    
ERR
The source contains an accelerator marker "&" (shortcut key) that must appear exactly once in the translation but is missing.

Correct translation (include the & exactly once, placed before the displayed letter you want as the shortcut):
&amp;รีเซ็ต
```

<!-- cache_translation_check_th_8452811c669ae3d5e0d8dd3295e84f7729f8a44107d44cd0893e81a7c536137d -->
```
        <source>&amp;Peers</source>
        <translation>เพื่อนร่วมงาน</translation>
    
ERR
The translation "เพื่อนร่วมงาน" means "colleague" / "co-worker", which is misleading in the Bitcoin context where "Peers" refers to network peers/nodes. Also the source contains a single '&' (mnemonic/shortcut) which is missing in the translation.

Correct translation (include exactly one &):
&เพื่อนร่วมเครือข่าย
```

<!-- cache_translation_check_th_6586aaac12e6d027151431d700bafb6e332790edd598a165911ebcf6f47067a8 -->
```
        <source>Banned peers</source>
        <translation>เพื่อนที่ถูกแบน</translation>
    
ERR
The Thai translation "เพื่อนที่ถูกแบน" uses "เพื่อน" (friends), which is misleading in a Bitcoin/network context. It should refer to peers/nodes rather than social "friends".

Correct translation suggestions:
- โหนดที่ถูกแบน
- เพียร์ที่ถูกแบน
```

<!-- cache_translation_check_th_9fb40e6924daba8de45e638dd25da00d5e3b016ab9925d22bd2fc170657bb662 -->
```
        <source>Ctrl+X</source>
        <translation>ตัด</translation>
    
ERR
The source is a keyboard shortcut ("Ctrl+X") and should not be translated into the action word "ตัด". Keyboard shortcuts must be kept as-is (or use localized modifier names consistently), otherwise the shortcut won’t work or will confuse users.

Correct translation:
Ctrl+X
```

<!-- cache_translation_check_th_9c457c8c684e4fe56ebc3364dbed5509409f37b493a3d5552f0ac237d73c5e24 -->
```
        <source>Whether we relay transactions to this peer.</source>
        <translation>ไม่ว่าความเราจะส่งการทำธุรกรรมไปยังเพื่อนนี้หรือไม่</translation>
    
ERR
The Thai translation is awkward and inaccurate. The phrase "ไม่ว่าความเราจะส่งการทำธุรกรรมไปยังเพื่อนนี้หรือไม่" is grammatically incorrect, and "ไม่ว่าความเราจะ..." is confusing. A more natural translation would be:

Correct translation:
เราจะถ่ายทอดธุรกรรมไปยัง peer นี้หรือไม่
```

<!-- cache_translation_check_th_dfc61c09af2a8dbd82402782106be17551652d63455e97a8952767a157926e36 -->
```
        <source>Last Transaction</source>
        <translation>ธุรกรรมล่าสุด (Thurakam lasut)</translation>
    
ERR
The translation is partially correct as "ธุรกรรมล่าสุด" means "Last Transaction". However, the parenthetical "(Thurakam lasut)" is a phonetic transliteration in Latin script, which is unnecessary and not standard practice in Thai UI translation. It could be confusing for users.

Correct translation:
ธุรกรรมล่าสุด
```

<!-- cache_translation_check_th_b84091088e25160c01035abe96d2627d85533c4e222656b2528af42e79d3ec9b -->
```
        <source>Mapped AS</source>
        <translation>แมปป์เป็น (pronounced: máp bpen)</translation>
    
ERR
The translation includes an unnecessary phonetic pronunciation guide in parentheses "(pronounced: máp bpen)", which is not present in the source and is inappropriate for a software interface.

Correct translation:
แมป AS หรือ แมป AS แล้ว
```

<!-- cache_translation_check_th_1bb595b7a42fedbeca155be993bcd95ac644e814197dc820640d449411c31802 -->
```
        <source>User Agent</source>
        <translation>ตัวแทนผู้ใช้
(Pronounced: Dtua-Thaen Phu-Chai)</translation>
    
ERR
The translation includes an unnecessary phonetic pronunciation guide in English which is not part of the source text and is inappropriate for a software interface.

Correct translation:
ตัวแทนผู้ใช้
```

<!-- cache_translation_check_th_bf8b7f4e0627a6fe92a6c7b877aa4b25f8ddc21b394be9eb04e1e2651fb9cfc7 -->
```
        <source>High Bandwidth</source>
        <translation>แบนด์วิธสูง (pronounced: baen-wit soong)</translation>
    
ERR
The translation includes an unnecessary phonetic pronunciation guide in parentheses. In a software interface, only the translated term should be present.

Correct translation:
แบนด์วิธสูง
```

<!-- cache_translation_check_th_40e7539c1287ef2a1c3a89622d0f9e82df8c4fa4d141cf7189d5c1dbbd62644a -->
```
        <source>Last Send</source>
        <translation>ส่งสุดท้าย (Song Soot Thai)</translation>
    
ERR
The parenthetical transliteration "(Song Soot Thai)" is unnecessary and not standard for a native 'th' translation. The Thai script alone suffices.

Correct translation:
ส่งล่าสุด
```

<!-- cache_translation_check_th_669b53677a6ecdf157996ec1b4376b2ed25962152be2c9a93ac97ace96b03b88 -->
```
        <source>&amp;Open</source>
        <translation>เปิด</translation>
    
ERR
The source contains a shortcut marker '&' that must be carried into the translation exactly once. The Thai translation "เปิด" is missing the '&'.

Correct translation:
&amp;เปิด
```

<!-- cache_translation_check_th_03719bce742d4dbd00ddf7987d11ad370f7733045c238914ce1fece8f98af5e6 -->
```
        <source>&amp;Network Traffic</source>
        <translation>การรับส่งข้อมูลเครือข่าย</translation>
    
ERR
The source includes an ampersand (&) indicating a keyboard shortcut, but the Thai translation is missing the &. No other issues (no format specifiers or extra whitespace), but the & must appear exactly once.

Correct translation (include & once), for example:
&amp;การรับส่งข้อมูลเครือข่าย
```

<!-- cache_translation_check_th_71dffd371e55df9f7d5f269f970c00309cc4ba97af9ac9ea72d12f9523c1c623 -->
```
        <source>Inbound: initiated by peer</source>
        <extracomment>Explanatory text for an inbound peer connection.</extracomment>
        <translation>ขาเข้า: เริ่มต้นโดยปัสสาวะ</translation>
    
ERR
The Thai word "ปัสสาวะ" means "urine," which is a mistranslation of "peer" (which should be a network peer, i.e., "เพียร์" or "เพื่อนร่วมเครือข่าย"). The rest of the translation is otherwise accurate, but this error is significant and makes the translation problematic and incorrect.

Correct translation:
ขาเข้า: เริ่มต้นโดยเพียร์
```

<!-- cache_translation_check_th_5d903c0a0bfcf3d73351621694041c15bec3af873b6a83f7891d5bc08a870a98 -->
```
        <source>&amp;Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>ที่อยู่ &amp;Copy</translation>
    
ERR
The translation mixes Thai and English ("ที่อยู่ &Copy") and places the ampersand incorrectly relative to natural Thai phrasing. It should be fully in Thai and keep a single & for the shortcut.

Correct translation:
&คัดลอกที่อยู่
```

<!-- cache_translation_check_th_f6f368badf6f14b5e493a7cebaeb6565b8cf59f820fcd0da8690c7f92123e521 -->
```
        <source>&amp;Copy address</source>
        <translation>ที่อยู่ &amp;Copy</translation>
    
ERR
The translation mixes English and Thai ("ที่อยู่ &Copy") and leaves a misplaced space before the ampersand. It should be fully translated into Thai and include the shortcut ampersand exactly once (no extra space).

Correct translation:
<translation>&amp;คัดลอกที่อยู่</translation>
```

<!-- cache_translation_check_th_eb7717d1384ad01fcdd5552b8627200e941816fb988e1ea2f27060bdf60c33e0 -->
```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
ERR
The translation is incorrect. "การส่งออกล้มเหลว" means "Export failed", which is unrelated to "Label".

Correct translation:
ป้ายกำกับ
```

<!-- cache_translation_check_th_28456f37398e516340b1c955245921c36eb974ceba65ded3777e5fcfb9871d1a -->
```
        <source>Change:</source>
        <translation>เปลี่ยน:</translation>
    
ERR
The Thai translation "เปลี่ยน:" is a verb meaning "change/modify" (as in to change something) and is misleading in the Bitcoin context where "Change:" refers to transaction change (the amount of money returned). No format specifiers or spacing issues.

Suggested correct translations:
- "เงินทอน:" 
- or more explicit: "จำนวนเงินทอน:"
```

<!-- cache_translation_check_th_54360120e54fd5714bd30aa5649fd4db30f9e73836708bb6228f6325c9ceebd1 -->
```
        <source>Copy bytes</source>
        <translation>คัดลอก bytes</translation>
    
ERR
The translation mixes Thai and English ("bytes") and has an unnecessary space. Better to use the Thai word for bytes and no extra space.

Correct translation:
คัดลอกไบต์
```

<!-- cache_translation_check_th_a32f34aa61f3a9e6f4f8d4be78e43e28f8fbd7a446a1ca1772eb220a44474400 -->
```
        <source>Copy change</source>
        <translation>คัดลอก change</translation>
    
ERR
The translation mixes Thai and English ("คัดลอก change") instead of translating "change". No format specifiers or whitespace issues, but it should be fully translated and context-aware (in Bitcoin "change" usually means the change amount or change address).

Correct translation (if meaning the change address):
คัดลอกที่อยู่เงินทอน

Or, if it means the change amount:
คัดลอกยอดเงินทอน
```

<!-- cache_translation_check_th_eb7717d1384ad01fcdd5552b8627200e941816fb988e1ea2f27060bdf60c33e0 -->
```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
ERR
The translation is incorrect. "การส่งออกล้มเหลว" means "Export failed", which is unrelated to "Label".

Correct translation:
ป้ายกำกับ
```

<!-- cache_translation_check_th_eb7717d1384ad01fcdd5552b8627200e941816fb988e1ea2f27060bdf60c33e0 -->
```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
ERR
The translation is incorrect. "การส่งออกล้มเหลว" means "Export failed", which is unrelated to "Label".

Correct translation:
ป้ายกำกับ
```
</details>

Number of issues: 101.
