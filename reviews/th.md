# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>th</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bth%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>นี่คือลิงก์ที่อยู่ Bitcoin ของคุณสำหรับการส่งการชำระเงิน ควรตรวจสอบจำนวนเงินและที่อยู่ผู้รับก่อนการส่งเหรียญ</translation>
    
YES
The translation introduces the word "ลิงก์" (link), which is not present in the English source and changes the meaning. The source talks about "Bitcoin addresses", not links. The rest is mostly fine, but "ส่งการชำระเงิน" is somewhat redundant ('ส่ง' already implies sending).

Correct translation:
นี่คือที่อยู่ Bitcoin ของคุณสำหรับการส่งการชำระเงิน กรุณาตรวจสอบจำนวนเงินและที่อยู่ผู้รับทุกครั้งก่อนส่งเหรียญ
```

```
        <source>Copy Address</source>
        <translation>ที่อยู่</translation>
    
YES
The translation is incomplete. "ที่อยู่" means "address" but does not include the verb "copy". The action "Copy Address" should be fully translated.

Correct translation:
คัดลอกที่อยู่
```

```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
YES
The translation is incorrect. "การส่งออกล้มเหลว" means "Export failed", which is unrelated to "Label".

Correct translation:
ป้ายกำกับ
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>ป้อนวลีรหัสใหม่สำหรับกระเป๋าสตางค์. 1.กรุณาใช้วลีรหัสผ่านของ 2.สิบตัวอักษรสุ่มหรือมากกว่า 2,หรือ 3แปดคำหรือมากกว่านั้น3</translation>
    
YES
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

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>เกิดข้อผิดพลาดร้ายแรง กรุณาตรวจสอบว่าไฟล์การตั้งค่าสามารถเขียนได้หรือไม่ หรือลองรันด้วยคำสั่ง</translation>
    
YES
The translation is incomplete and omits the part "with -nosettings." from the end of the sentence. This can mislead users who need to know about the -nosettings option. Also, it would be clearer to specify the switch as "-nosettings" in the translation.

Correct translation:
เกิดข้อผิดพลาดร้ายแรง กรุณาตรวจสอบว่าไฟล์การตั้งค่าสามารถเขียนได้หรือไม่ หรือลองรันด้วย -nosettings
```

```
        <source>CJDNS</source>
        <comment>network name</comment>
        <extracomment>Name of CJDNS network in peer info</extracomment>
        <translation>CJDNS (แปลงชื่อย่อ)</translation>
    
YES
The addition "(แปลงชื่อย่อ)" translates as "(acronym translation)", which is unnecessary and potentially confusing since "CJDNS" is a proper name that should not be expanded or explained in this context.

Correct translation:
CJDNS
```

```
        <source>Outbound</source>
        <extracomment>An outbound connection to a peer. An outbound connection is a connection initiated by us.</extracomment>
        <translation>ออกเดินทาง (òk dern thāng)</translation>
    
YES
The translation "ออกเดินทาง (òk dern thāng)" means "to depart" or "departing", which is not accurate in this technical context. Here, "Outbound" refers to a network connection initiated by the user or system, not physical departure.

Correct translation:
ขาออก

This term is standard in networking contexts to indicate "outbound" connections.
```

```
        <source>Full Relay</source>
        <extracomment>Peer connection type that relays all network information.</extracomment>
        <translation>การแข่งขันรีเลย์เต็มรูปแบบ</translation>
    
YES
The translation is inaccurate. "การแข่งขันรีเลย์เต็มรูปแบบ" translates to "Full relay competition," which is incorrect. The term "Full Relay" in the context of Bitcoin peer connection refers to a node that relays all network information, not a competition.

Correct translation:
รีเลย์เต็มรูปแบบ

This directly conveys the technical meaning without adding unintended wording.
```

```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>การวิ่งผลัดบล็อก</translation>
    
YES
The translation "การวิ่งผลัดบล็อก" literally means "block relay" in the context of a relay race, which is not suitable for the technical context of a peer connection type in the Bitcoin network. It should refer to relaying block information across the network, not a physical relay race.

Correct translation:
ถ่ายทอดบล็อก

This translation accurately captures the concept of relaying block information in a network context.
```

```
        <source>Sign message…</source>
        <translation>ป้าย  ข้อความ…</translation>
    
YES
The translation "ป้าย ข้อความ…" is incorrect. "ป้าย" means "sign" as in a physical sign, which does not match the intended meaning of "Sign" as in "cryptographically sign" a message. Also, there is unnecessary extra space.

Correct translation:
เซ็นชื่อข้อความ…
```

```
        <source>Receiving addresses</source>
        <translation>ตัวเลือกคำสั่งในบรรทัดคำสั่ง</translation>
    
YES  
The translation is incorrect. The English source "Receiving addresses" refers to addresses where Bitcoin can be received (i.e., wallet receiving addresses). The provided Thai translation "ตัวเลือกคำสั่งในบรรทัดคำสั่ง" means "command line options", which is unrelated and erroneous.

Correct translation:
ที่อยู่สำหรับรับเงิน
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation> การสร้างคีย์ HD คือ&lt;b&gt;พิการ&lt;/b&gt;</translation>
    
YES
The translation of "disabled" as "พิการ" is incorrect and inappropriate, since "พิการ" means "disabled" in the context of physical disability, which is not suitable here. There is also a stray leading space in the translated string.

Correct translation:
การสร้างคีย์ HD ถูก&lt;b&gt;ปิดใช้งาน&lt;/b&gt;
```

```
        <source>Private key &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>กุญแจส่วนตัว &lt;b&gt;พิการ&lt;/b&gt;</translation>
    
YES
The word "พิการ" in Thai means "disabled" as in "handicapped", which is not appropriate for "disabled" in the sense of "functionality turned off". A more appropriate word is "ถูกปิดใช้งาน" or "ปิดการใช้งาน".

Correct translation:
กุญแจส่วนตัว &lt;b&gt;ถูกปิดใช้งาน&lt;/b&gt;
```

```
        <source>Copy address</source>
        <translation>ที่อยู่ Copy</translation>
    
YES
The order of words is incorrect; "ที่อยู่ Copy" reads awkwardly in Thai. The term "Copy" should be in a verb position, and Thai commonly uses "คัดลอก" for "Copy". The correct translation should be:

คัดลอกที่อยู่
```

```
        <source>Copy label</source>
        <translation>คัดลอก  ป้าย</translation>
    
YES
There is an extra space between "คัดลอก" and "ป้าย" which is a formatting issue. In Thai, there should be no extra space.

Correct translation:
คัดลอกป้าย
```

```
        <source>Copy change</source>
        <translation>การเปลี่ยนแปลงข้อความ</translation>
    
YES
The translation is inaccurate. "Copy change" in the Bitcoin context refers to copying the "change" amount or address from a transaction – not "copying text changes." The provided Thai translation, "การเปลี่ยนแปลงข้อความ," means "change of message/text," which is incorrect.

Correct translation:
คัดลอกเงินทอน
```

```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>การย้ายกระเป๋าจะทำให้กระเป๋านี้กลายเป็นกระเป๋าหรือหลายๆ กระเป๋าที่มีคำอธิบาย (descriptor wallets) กระเป๋าสำรองใหม่จะต้องถูกสร้างขึ้น
หากกระเป๋านี้มีสคริปต์ที่ดูได้เท่านั้น (watchonly scripts) จะมีกระเป๋าใหม่ที่สร้างขึ้นซึ่งมีสคริปต์เหล่านั้น
หากกระเป๋านี้มีสคริปต์ที่แก้ไขได้แต่ไม่ได้ติดตาม (solvable but not watched scripts) จะมีกระเป๋าใหม่ที่แตกต่างออกไปซึ่งมีสคริปต์เหล่านั้น</translation>
    
YES
The Thai translation omits the last paragraph regarding the creation and location of the backup file and the restore process. This is a significant omission as it contains important information for the user. Additionally, the translation is missing the newline format present in the original, and there is a slight awkwardness in some Thai phrases, especially for technical terms—though this is less significant than the outright omission.

Correct translation:
การย้ายกระเป๋าสตางค์จะเปลี่ยนกระเป๋านี้เป็นกระเป๋าสตางค์แบบ descriptor หนึ่งใบหรือมากกว่า คุณจะต้องสร้างข้อมูลสำรอง (backup) ของกระเป๋าใหม่
หากกระเป๋านี้มี script ที่ดูได้เท่านั้น (watchonly scripts) จะมีการสร้างกระเป๋าสตางค์ใหม่ซึ่งมี script เหล่านั้นอยู่ด้วย
หากกระเป๋านี้มี script ที่สามารถแก้ไขได้แต่ไม่ได้ติดตาม (solvable but not watched scripts) จะมีการสร้างกระเป๋าสตางค์ใหม่ต่างหากสำหรับ script เหล่านั้น

กระบวนการย้ายกระเป๋าจะสร้างไฟล์สำรองของกระเป๋าสตางค์ก่อนที่จะย้าย ไฟล์สำรองนี้จะถูกตั้งชื่อเป็น &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak และสามารถพบได้ในไดเรกทอรีของกระเป๋านี้ หากการย้ายเกิดข้อผิดพลาด คุณสามารถเรียกคืนข้อมูลจากไฟล์สำรองโดยใช้ฟังก์ชัน "กู้คืนกระเป๋าสตางค์" ได้
```

```
        <source>Form</source>
        <translation>จาก</translation>
    
YES
The translation is inaccurate. "Form" in English means a document with fields to fill in (like in software), but "จาก" in Thai means "from" (the preposition). The correct translation for "Form" (as in a user or input form) is "ฟอร์ม" or "แบบฟอร์ม".

Correct translation:
ฟอร์ม
or
แบบฟอร์ม
```

```
        <source>Number of script verification threads</source>
        <translation>จำนวนของสคริปต์และเธรดการตรวจสอบ</translation>
    
YES
The translation adds "และ" ("and") which is not present in the source and changes the meaning. The original phrase "Number of script verification threads" specifically refers to the number of threads used for script verification, not separate counts for scripts and threads.

Correct translation:
จำนวนเธรดตรวจสอบสคริปต์

OR more literally:
จำนวนเธรดสำหรับการตรวจสอบสคริปต์
```

```
        <source>Network</source>
        <translation>และเครือข่าย</translation>
    
YES
The translation "และเครือข่าย" means "and network" or "and the network", which adds the conjunction "และ" ("and") not present in the source. The correct translation should be simply "เครือข่าย".

Correct translation:
เครือข่าย
```

```
        <source>Prune block storage to</source>
        <translation>ตัดทอนและบล็อกที่เก็บข้อมูลไปที่</translation>
    
YES
The translation is slightly inaccurate and could cause confusion. The correct translation should be more concise and clear, directly relating "prune" to "ลดขนาด" (reduce size) or "ลบข้อมูลที่เก็บบล็อก" (delete block storage data), and the phrase "to" refers to a value/limit. The current translation is awkward and does not preserve the structure.

Correct translation:
ปรับลดขนาดการเก็บข้อมูลบล็อกเหลือ

Or, more literally:
ลดขนาดที่เก็บข้อมูลบล็อกเหลือ
```

```
        <source>Form</source>
        <translation>จาก</translation>
    
YES
The translation is inaccurate. "Form" in English means a document with fields to fill in (like in software), but "จาก" in Thai means "from" (the preposition). The correct translation for "Form" (as in a user or input form) is "ฟอร์ม" or "แบบฟอร์ม".

Correct translation:
ฟอร์ม
or
แบบฟอร์ม
```

```
        <source>Could not sign any more inputs.</source>
        <translation>ไม่สามารถลงนามการป้อนข้อมูลเพิ่มเติมได้ (Mai samart long nam kan phon khomooht permum dai).</translation>
    
YES
The translation contains a parenthetical transliteration "(Mai samart long nam kan phon khomooht permum dai)", which is not standard for professional UI/localization and is unnecessary. Only the Thai script translation should be provided. 

Correct translation:
ไม่สามารถลงนามการป้อนข้อมูลเพิ่มเติมได้
```

```
        <source>Outbound</source>
        <extracomment>An Outbound Connection to a Peer.</extracomment>
        <translation>ออกเดินทาง (òk dern thāng)</translation>
    
YES
The translation "ออกเดินทาง (òk dern thāng)" means "depart" or "set off", which is incorrect in this context. In the context of network connections, "Outbound" typically means "ขาออก" or "ภายนอก" in Thai.

Correct translation:
ขาออก
```

```
        <source>Whether we relay transactions to this peer.</source>
        <translation>ไม่ว่าความเราจะส่งการทำธุรกรรมไปยังเพื่อนนี้หรือไม่</translation>
    
YES
The Thai translation is awkward and inaccurate. The phrase "ไม่ว่าความเราจะส่งการทำธุรกรรมไปยังเพื่อนนี้หรือไม่" is grammatically incorrect, and "ไม่ว่าความเราจะ..." is confusing. A more natural translation would be:

Correct translation:
เราจะถ่ายทอดธุรกรรมไปยัง peer นี้หรือไม่
```

```
        <source>Last Transaction</source>
        <translation>ธุรกรรมล่าสุด (Thurakam lasut)</translation>
    
YES
The translation is partially correct as "ธุรกรรมล่าสุด" means "Last Transaction". However, the parenthetical "(Thurakam lasut)" is a phonetic transliteration in Latin script, which is unnecessary and not standard practice in Thai UI translation. It could be confusing for users.

Correct translation:
ธุรกรรมล่าสุด
```

```
        <source>Last Send</source>
        <translation>ส่งสุดท้าย (Song Soot Thai)</translation>
    
YES
The parenthetical transliteration "(Song Soot Thai)" is unnecessary and not standard for a native 'th' translation. The Thai script alone suffices.

Correct translation:
ส่งล่าสุด
```

```
        <source>Inbound: initiated by peer</source>
        <extracomment>Explanatory text for an inbound peer connection.</extracomment>
        <translation>ขาเข้า: เริ่มต้นโดยปัสสาวะ</translation>
    
YES
The Thai word "ปัสสาวะ" means "urine," which is a mistranslation of "peer" (which should be a network peer, i.e., "เพียร์" or "เพื่อนร่วมเครือข่าย"). The rest of the translation is otherwise accurate, but this error is significant and makes the translation problematic and incorrect.

Correct translation:
ขาเข้า: เริ่มต้นโดยเพียร์
```

```
        <source>Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>ที่อยู่ Copy</translation>
    
YES
The translation is incorrect and awkward. "ที่อยู่ Copy" combines Thai and English in an unnatural way and reverses the order of the wording. The correct translation should have "Copy" in Thai and match the context, which is an action.

Correct translation:
คัดลอกที่อยู่
```

```
        <source>Copy address</source>
        <translation>ที่อยู่ Copy</translation>
    
YES
The order of words is incorrect; "ที่อยู่ Copy" reads awkwardly in Thai. The term "Copy" should be in a verb position, and Thai commonly uses "คัดลอก" for "Copy". The correct translation should be:

คัดลอกที่อยู่
```

```
        <source>Copy label</source>
        <translation>คัดลอก  ป้าย</translation>
    
YES
There is an extra space between "คัดลอก" and "ป้าย" which is a formatting issue. In Thai, there should be no extra space.

Correct translation:
คัดลอกป้าย
```

```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
YES
The translation is incorrect. "การส่งออกล้มเหลว" means "Export failed", which is unrelated to "Label".

Correct translation:
ป้ายกำกับ
```

```
        <source>Copy fee</source>
        <translation>ค่าลอกสำเนา (kâa lók sàm-náo)</translation>
    
YES
The translation "ค่าลอกสำเนา (kâa lók sàm-náo)" is inaccurate and problematic. "ค่าลอกสำเนา" literally translates to "copying fee" or "fee for duplicating a copy," which is a misunderstanding of the context. In Bitcoin applications, "Copy fee" typically refers to the action of "copying (the value of) the fee" to the clipboard, not a fee for making a copy.

Correct translation:
คัดลอกค่าธรรมเนียม

This means "Copy (the) fee," which matches the user-interface context. No need for transliteration in parentheses.
```

```
        <source>Copy change</source>
        <translation>การเปลี่ยนแปลงข้อความ</translation>
    
YES
The translation is inaccurate. "Copy change" in the Bitcoin context refers to copying the "change" amount or address from a transaction – not "copying text changes." The provided Thai translation, "การเปลี่ยนแปลงข้อความ," means "change of message/text," which is incorrect.

Correct translation:
คัดลอกเงินทอน
```

```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
YES
The translation is incorrect. "การส่งออกล้มเหลว" means "Export failed", which is unrelated to "Label".

Correct translation:
ป้ายกำกับ
```

```
        <source>Copy address</source>
        <translation>ที่อยู่ Copy</translation>
    
YES
The order of words is incorrect; "ที่อยู่ Copy" reads awkwardly in Thai. The term "Copy" should be in a verb position, and Thai commonly uses "คัดลอก" for "Copy". The correct translation should be:

คัดลอกที่อยู่
```

```
        <source>Copy label</source>
        <translation>คัดลอก  ป้าย</translation>
    
YES
There is an extra space between "คัดลอก" and "ป้าย" which is a formatting issue. In Thai, there should be no extra space.

Correct translation:
คัดลอกป้าย
```

```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
YES
The translation is incorrect. "การส่งออกล้มเหลว" means "Export failed", which is unrelated to "Label".

Correct translation:
ป้ายกำกับ
```
</details>

Number of issues: 38.
