# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>th</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bth%5D%20low%20quality)


<!-- cache_translation_check_th_8aff7c93af644f5e8d212ee89c2ec7df72290c6eaf5bdcbb5f032f0689bf4273 -->
```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>นี่คือลิงก์ที่อยู่ Bitcoin ของคุณสำหรับการส่งการชำระเงิน ควรตรวจสอบจำนวนเงินและที่อยู่ผู้รับก่อนการส่งเหรียญ</translation>
    
ERR
The translation introduces the word "ลิงก์" (link), which is not present in the English source and changes the meaning. The source talks about "Bitcoin addresses", not links. The rest is mostly fine, but "ส่งการชำระเงิน" is somewhat redundant ('ส่ง' already implies sending).

Correct translation:
นี่คือที่อยู่ Bitcoin ของคุณสำหรับการส่งการชำระเงิน กรุณาตรวจสอบจำนวนเงินและที่อยู่ผู้รับทุกครั้งก่อนส่งเหรียญ
```

<!-- cache_translation_check_th_d236f960863c54503f7fbe3cf37fc7faff06046ec72a9e9020f34668bf23e39d -->
```
        <source>Copy Address</source>
        <translation>ที่อยู่</translation>
    
ERR
The translation is incomplete. "ที่อยู่" means "address" but does not include the verb "copy". The action "Copy Address" should be fully translated.

Correct translation:
คัดลอกที่อยู่
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

<!-- cache_translation_check_th_6709d13e20b7a5519ba55d28b250727cca29368c4fa654c15cc331b960d61510 -->
```
        <source>Sign message…</source>
        <translation>ป้าย  ข้อความ…</translation>
    
ERR
The translation "ป้าย ข้อความ…" is incorrect. "ป้าย" means "sign" as in a physical sign, which does not match the intended meaning of "Sign" as in "cryptographically sign" a message. Also, there is unnecessary extra space.

Correct translation:
เซ็นชื่อข้อความ…
```

<!-- cache_translation_check_th_9a6e285d673c101bc2b60b9140508a20ef747d1372f633fd302c7cca9d9b7e9d -->
```
        <source>Receiving addresses</source>
        <translation>ตัวเลือกคำสั่งในบรรทัดคำสั่ง</translation>
    
ERR  
The translation is incorrect. The English source "Receiving addresses" refers to addresses where Bitcoin can be received (i.e., wallet receiving addresses). The provided Thai translation "ตัวเลือกคำสั่งในบรรทัดคำสั่ง" means "command line options", which is unrelated and erroneous.

Correct translation:
ที่อยู่สำหรับรับเงิน
```

<!-- cache_translation_check_th_0f31d728676d17b57e77543a2b510ac2ef7ae7f273545c2d363bf3d3329e3ef3 -->
```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation> การสร้างคีย์ HD คือ&lt;b&gt;พิการ&lt;/b&gt;</translation>
    
ERR
The translation of "disabled" as "พิการ" is incorrect and inappropriate, since "พิการ" means "disabled" in the context of physical disability, which is not suitable here. There is also a stray leading space in the translated string.

Correct translation:
การสร้างคีย์ HD ถูก&lt;b&gt;ปิดใช้งาน&lt;/b&gt;
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

<!-- cache_translation_check_th_36b1620204cc0e733f6aa8f8555e7c1e5fda8bdcb6d82a5d951e4f2fa75b143e -->
```
        <source>Copy address</source>
        <translation>ที่อยู่ Copy</translation>
    
ERR
The order of words is incorrect; "ที่อยู่ Copy" reads awkwardly in Thai. The term "Copy" should be in a verb position, and Thai commonly uses "คัดลอก" for "Copy". The correct translation should be:

คัดลอกที่อยู่
```

<!-- cache_translation_check_th_a1203d9d3d87a83988f9cb697d2a985567998b5affd9a4f723b98eab7ca131ca -->
```
        <source>Copy label</source>
        <translation>คัดลอก  ป้าย</translation>
    
ERR
There is an extra space between "คัดลอก" and "ป้าย" which is a formatting issue. In Thai, there should be no extra space.

Correct translation:
คัดลอกป้าย
```

<!-- cache_translation_check_th_162b033d672bcc82108a7b550d4bf8236db32c8661b9bfaee1d0a03e6aaabfb4 -->
```
        <source>Copy change</source>
        <translation>การเปลี่ยนแปลงข้อความ</translation>
    
ERR
The translation is inaccurate. "Copy change" in the Bitcoin context refers to copying the "change" amount or address from a transaction – not "copying text changes." The provided Thai translation, "การเปลี่ยนแปลงข้อความ," means "change of message/text," which is incorrect.

Correct translation:
คัดลอกเงินทอน
```

<!-- cache_translation_check_th_5a1aa87441c7908eb775e5f910c8908afb3a648c7965d769e2ca91fe0202533d -->
```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>การย้ายกระเป๋าจะทำให้กระเป๋านี้กลายเป็นกระเป๋าหรือหลายๆ กระเป๋าที่มีคำอธิบาย (descriptor wallets) กระเป๋าสำรองใหม่จะต้องถูกสร้างขึ้น
หากกระเป๋านี้มีสคริปต์ที่ดูได้เท่านั้น (watchonly scripts) จะมีกระเป๋าใหม่ที่สร้างขึ้นซึ่งมีสคริปต์เหล่านั้น
หากกระเป๋านี้มีสคริปต์ที่แก้ไขได้แต่ไม่ได้ติดตาม (solvable but not watched scripts) จะมีกระเป๋าใหม่ที่แตกต่างออกไปซึ่งมีสคริปต์เหล่านั้น</translation>
    
ERR
The Thai translation omits the last paragraph regarding the creation and location of the backup file and the restore process. This is a significant omission as it contains important information for the user. Additionally, the translation is missing the newline format present in the original, and there is a slight awkwardness in some Thai phrases, especially for technical terms—though this is less significant than the outright omission.

Correct translation:
การย้ายกระเป๋าสตางค์จะเปลี่ยนกระเป๋านี้เป็นกระเป๋าสตางค์แบบ descriptor หนึ่งใบหรือมากกว่า คุณจะต้องสร้างข้อมูลสำรอง (backup) ของกระเป๋าใหม่
หากกระเป๋านี้มี script ที่ดูได้เท่านั้น (watchonly scripts) จะมีการสร้างกระเป๋าสตางค์ใหม่ซึ่งมี script เหล่านั้นอยู่ด้วย
หากกระเป๋านี้มี script ที่สามารถแก้ไขได้แต่ไม่ได้ติดตาม (solvable but not watched scripts) จะมีการสร้างกระเป๋าสตางค์ใหม่ต่างหากสำหรับ script เหล่านั้น

กระบวนการย้ายกระเป๋าจะสร้างไฟล์สำรองของกระเป๋าสตางค์ก่อนที่จะย้าย ไฟล์สำรองนี้จะถูกตั้งชื่อเป็น &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak และสามารถพบได้ในไดเรกทอรีของกระเป๋านี้ หากการย้ายเกิดข้อผิดพลาด คุณสามารถเรียกคืนข้อมูลจากไฟล์สำรองโดยใช้ฟังก์ชัน "กู้คืนกระเป๋าสตางค์" ได้
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

<!-- cache_translation_check_th_da7cd9b9f3bbce71451fe34a673783d4d9c557fdafa93de6111aea4dcbb9b190 -->
```
        <source>Number of script verification threads</source>
        <translation>จำนวนของสคริปต์และเธรดการตรวจสอบ</translation>
    
ERR
The translation adds "และ" ("and") which is not present in the source and changes the meaning. The original phrase "Number of script verification threads" specifically refers to the number of threads used for script verification, not separate counts for scripts and threads.

Correct translation:
จำนวนเธรดตรวจสอบสคริปต์

OR more literally:
จำนวนเธรดสำหรับการตรวจสอบสคริปต์
```

<!-- cache_translation_check_th_73bdc4a7df0fb4d620990432a2d2e987cf818156494125138a174edb9ca09557 -->
```
        <source>Network</source>
        <translation>และเครือข่าย</translation>
    
ERR
The translation "และเครือข่าย" means "and network" or "and the network", which adds the conjunction "และ" ("and") not present in the source. The correct translation should be simply "เครือข่าย".

Correct translation:
เครือข่าย
```

<!-- cache_translation_check_th_42bbd79bc3f3f880a11e2d507280aacb9f5baae1425ae74cf3499b743b39848b -->
```
        <source>Prune block storage to</source>
        <translation>ตัดทอนและบล็อกที่เก็บข้อมูลไปที่</translation>
    
ERR
The translation is slightly inaccurate and could cause confusion. The correct translation should be more concise and clear, directly relating "prune" to "ลดขนาด" (reduce size) or "ลบข้อมูลที่เก็บบล็อก" (delete block storage data), and the phrase "to" refers to a value/limit. The current translation is awkward and does not preserve the structure.

Correct translation:
ปรับลดขนาดการเก็บข้อมูลบล็อกเหลือ

Or, more literally:
ลดขนาดที่เก็บข้อมูลบล็อกเหลือ
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

<!-- cache_translation_check_th_40e7539c1287ef2a1c3a89622d0f9e82df8c4fa4d141cf7189d5c1dbbd62644a -->
```
        <source>Last Send</source>
        <translation>ส่งสุดท้าย (Song Soot Thai)</translation>
    
ERR
The parenthetical transliteration "(Song Soot Thai)" is unnecessary and not standard for a native 'th' translation. The Thai script alone suffices.

Correct translation:
ส่งล่าสุด
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

<!-- cache_translation_check_th_a77eef0b8ccf5f7dc82eaf792141a27a592a79174dee5074beb11665874b0c2b -->
```
        <source>Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>ที่อยู่ Copy</translation>
    
ERR
The translation is incorrect and awkward. "ที่อยู่ Copy" combines Thai and English in an unnatural way and reverses the order of the wording. The correct translation should have "Copy" in Thai and match the context, which is an action.

Correct translation:
คัดลอกที่อยู่
```

<!-- cache_translation_check_th_36b1620204cc0e733f6aa8f8555e7c1e5fda8bdcb6d82a5d951e4f2fa75b143e -->
```
        <source>Copy address</source>
        <translation>ที่อยู่ Copy</translation>
    
ERR
The order of words is incorrect; "ที่อยู่ Copy" reads awkwardly in Thai. The term "Copy" should be in a verb position, and Thai commonly uses "คัดลอก" for "Copy". The correct translation should be:

คัดลอกที่อยู่
```

<!-- cache_translation_check_th_a1203d9d3d87a83988f9cb697d2a985567998b5affd9a4f723b98eab7ca131ca -->
```
        <source>Copy label</source>
        <translation>คัดลอก  ป้าย</translation>
    
ERR
There is an extra space between "คัดลอก" and "ป้าย" which is a formatting issue. In Thai, there should be no extra space.

Correct translation:
คัดลอกป้าย
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

<!-- cache_translation_check_th_e039940e034eabdbf06410eada0544277921449d3f08ced44391ff0e4c325435 -->
```
        <source>Copy fee</source>
        <translation>ค่าลอกสำเนา (kâa lók sàm-náo)</translation>
    
ERR
The translation "ค่าลอกสำเนา (kâa lók sàm-náo)" is inaccurate and problematic. "ค่าลอกสำเนา" literally translates to "copying fee" or "fee for duplicating a copy," which is a misunderstanding of the context. In Bitcoin applications, "Copy fee" typically refers to the action of "copying (the value of) the fee" to the clipboard, not a fee for making a copy.

Correct translation:
คัดลอกค่าธรรมเนียม

This means "Copy (the) fee," which matches the user-interface context. No need for transliteration in parentheses.
```

<!-- cache_translation_check_th_162b033d672bcc82108a7b550d4bf8236db32c8661b9bfaee1d0a03e6aaabfb4 -->
```
        <source>Copy change</source>
        <translation>การเปลี่ยนแปลงข้อความ</translation>
    
ERR
The translation is inaccurate. "Copy change" in the Bitcoin context refers to copying the "change" amount or address from a transaction – not "copying text changes." The provided Thai translation, "การเปลี่ยนแปลงข้อความ," means "change of message/text," which is incorrect.

Correct translation:
คัดลอกเงินทอน
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

<!-- cache_translation_check_th_36b1620204cc0e733f6aa8f8555e7c1e5fda8bdcb6d82a5d951e4f2fa75b143e -->
```
        <source>Copy address</source>
        <translation>ที่อยู่ Copy</translation>
    
ERR
The order of words is incorrect; "ที่อยู่ Copy" reads awkwardly in Thai. The term "Copy" should be in a verb position, and Thai commonly uses "คัดลอก" for "Copy". The correct translation should be:

คัดลอกที่อยู่
```

<!-- cache_translation_check_th_a1203d9d3d87a83988f9cb697d2a985567998b5affd9a4f723b98eab7ca131ca -->
```
        <source>Copy label</source>
        <translation>คัดลอก  ป้าย</translation>
    
ERR
There is an extra space between "คัดลอก" and "ป้าย" which is a formatting issue. In Thai, there should be no extra space.

Correct translation:
คัดลอกป้าย
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

Number of issues: 38.
