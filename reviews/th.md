# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>th</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bth%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>นี่คือลิงก์ที่อยู่ Bitcoin ของคุณสำหรับการส่งการชำระเงิน ควรตรวจสอบจำนวนเงินและที่อยู่ผู้รับก่อนการส่งเหรียญ</translation>
    
YES  
The translation is mostly accurate but uses the word "ลิงก์ที่อยู่" which means "link address," which is unusual and incorrect in this context. The correct word should be just "ที่อยู่" (address). Also, adding a period or appropriate punctuation after the first sentence improves readability.  

Correct translation:  
นี่คือที่อยู่ Bitcoin ของคุณสำหรับการส่งการชำระเงิน ควรตรวจสอบจำนวนเงินและที่อยู่ผู้รับก่อนส่งเหรียญ
```

```
        <source>Copy Address</source>
        <translation>ที่อยู่</translation>
    
YES  
The translation "ที่อยู่" means "address" but does not convey the command "Copy Address." The phrase should instruct the user to copy the address, not just display the word "address."

Correct translation:  
คัดลอกที่อยู่
```

```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
YES
The translation "การส่งออกล้มเหลว" means "Export failed," which does not correspond to the source text "Label." 

Correct translation:
ป้ายชื่อ
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>ป้อนวลีรหัสใหม่สำหรับกระเป๋าสตางค์. 1.กรุณาใช้วลีรหัสผ่านของ 2.สิบตัวอักษรสุ่มหรือมากกว่า 2,หรือ 3แปดคำหรือมากกว่านั้น3</translation>
    
YES
The translation is problematic because it contains extraneous numbering (1., 2., 2,, 3, 3) that does not appear in the source and disrupts readability. It also improperly uses a period after "กระเป๋าสตางค์" instead of a line break or appropriate punctuation. The HTML tags (<br/>, <b>) from the source are omitted or not properly represented, which may affect formatting in the application.

Corrected translation:
ป้อนวลีรหัสใหม่สำหรับกระเป๋าสตางค์&lt;br/&gt;กรุณาใช้วลีรหัสผ่านที่มี&lt;b&gt;สิบตัวอักษรสุ่มหรือมากกว่า&lt;/b&gt; หรือ&lt;b&gt;แปดคำหรือมากกว่านั้น&lt;/b&gt;
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>เกิดข้อผิดพลาดร้ายแรง กรุณาตรวจสอบว่าไฟล์การตั้งค่าสามารถเขียนได้หรือไม่ หรือลองรันด้วยคำสั่ง</translation>
    
YES
The translation is incomplete and cuts off abruptly after "ลองรันด้วยคำสั่ง" ("try running with command"). It should include the "-nosettings" flag as in the source to fully convey the meaning.

Correct translation:
เกิดข้อผิดพลาดร้ายแรง กรุณาตรวจสอบว่าไฟล์การตั้งค่าสามารถเขียนได้หรือไม่ หรือลองรันด้วยคำสั่ง -nosettings
```

```
        <source>CJDNS</source>
        <comment>network name</comment>
        <extracomment>Name of CJDNS network in peer info</extracomment>
        <translation>CJDNS (แปลงชื่อย่อ)</translation>
    
YES  
The original source "CJDNS" is a proper noun and a network name and should remain unchanged. The addition "(แปลงชื่อย่อ)" means "(abbreviation translation)" or "(acronym translation)" which is unnecessary and misleading. It is not part of the original text nor common in translations of network names.  

Correct translation:  
CJDNS
```

```
        <source>Outbound</source>
        <extracomment>An outbound connection to a peer. An outbound connection is a connection initiated by us.</extracomment>
        <translation>ออกเดินทาง (òk dern thāng)</translation>
    
YES  
The translation "ออกเดินทาง (òk dern thāng)" literally means "to depart" or "to set out on a journey," which is not accurate in this technical context. "Outbound" here refers to a connection initiated by us, not the act of leaving or traveling. A more precise translation related to networking would be "ขาออก" (khaa òk), which is commonly used in IT contexts to mean "outbound."

Correct translation:  
ขาออก
```

```
        <source>Full Relay</source>
        <extracomment>Peer connection type that relays all network information.</extracomment>
        <translation>การแข่งขันรีเลย์เต็มรูปแบบ</translation>
    
YES  
The translation "การแข่งขันรีเลย์เต็มรูปแบบ" means "full relay competition," which is incorrect and adds an unnecessary word "การแข่งขัน" (competition). The correct translation for "Full Relay" in this Bitcoin network context (relaying all network information) should be concise and not include "competition."

Correct translation:  
รีเลย์เต็มรูปแบบ
```

```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>การวิ่งผลัดบล็อก</translation>
    
YES  
The translation "การวิ่งผลัดบล็อก" literally means "block relay race," which is incorrect and misleading in this technical context. The term "Block Relay" refers to relaying blockchain information, not running a race.

Correct translation:  
"การส่งต่อบล็อก"
```

```
        <source>Sign message…</source>
        <translation>ป้าย  ข้อความ…</translation>
    
YES  
The translation "ป้าย  ข้อความ…" is incorrect and unnatural in Thai. The English phrase "Sign message…" in the context of Bitcoin refers to the action of signing a message, not "putting a label on a message." The correct translation should convey the action "sign" (as in digitally signing) a message.

Correct translation:  
เซ็นข้อความ…
```

```
        <source>Receiving addresses</source>
        <translation>ตัวเลือกคำสั่งในบรรทัดคำสั่ง</translation>
    
YES  
The translation "ตัวเลือกคำสั่งในบรรทัดคำสั่ง" means "command line options," which is incorrect for "Receiving addresses." The correct translation should be:  
"ที่อยู่สำหรับรับ"
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation> การสร้างคีย์ HD คือ&lt;b&gt;พิการ&lt;/b&gt;</translation>
    
YES  
The word "พิการ" in Thai means "disabled" in the context of a physical disability or impairment, which is inappropriate here. The correct translation should convey "disabled" in the sense of "turned off" or "deactivated."

Correct translation:  
การสร้างคีย์ HD&lt;b&gt;ถูกปิดใช้งาน&lt;/b&gt;
```

```
        <source>Private key &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>กุญแจส่วนตัว &lt;b&gt;พิการ&lt;/b&gt;</translation>
    
YES  
The translation uses the word "พิการ" which means "disabled" in the context of a physical disability, which is inappropriate and misleading here. In technical contexts, such as a private key being disabled, a better term would be "ถูกปิดใช้งาน" (disabled/inactivated) or "ไม่สามารถใช้งานได้" (cannot be used).  

Correct translation:  
กุญแจส่วนตัว &lt;b&gt;ถูกปิดใช้งาน&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>กระเป๋าเงินคือ &lt;b&gt;เข้ารหัส&lt;/b&gt; และปัจจุบัน &lt;b&gt;ปลดล็อก&lt;/b&gt;</translation>
    
YES
The phrase "กระเป๋าเงินคือ" is unnatural in Thai. "คือ" (is) is unnecessary here. A better translation would be more concise and natural:

Correct translation:  
กระเป๋าเงิน&lt;b&gt;เข้ารหัส&lt;/b&gt; และปัจจุบัน&lt;b&gt;ปลดล็อก&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>กระเป๋าสตางค์คือ &lt;b&gt;เข้ารหัส&lt;/b&gt; และปัจจุบัน &lt;b&gt;ล็อค&lt;/b&gt;</translation>
    
YES
The phrase "กระเป๋าสตางค์คือ" is awkward and unnatural in Thai. A more natural and clear translation would be:
กระเป๋าสตางค์ &lt;b&gt;ถูกเข้ารหัส&lt;/b&gt; และขณะนี้ &lt;b&gt;ถูกล็อค&lt;/b&gt;
```

```
        <source>Copy address</source>
        <translation>ที่อยู่ Copy</translation>
    
YES  
The translation incorrectly places the English word "Copy" after "ที่อยู่" (address), which is unnatural in Thai. The correct translation should convey the command "Copy address" in a natural and clear way, such as "คัดลอกที่อยู่".  

Correct translation:  
คัดลอกที่อยู่
```

```
        <source>Copy label</source>
        <translation>คัดลอก  ป้าย</translation>
    
YES
There is an extra space between "คัดลอก" and "ป้าย" in the translation. The correct translation should have only one space:

คัดลอก ป้าย
```

```
        <source>Copy change</source>
        <translation>การเปลี่ยนแปลงข้อความ</translation>
    
YES  
The English phrase "Copy change" in the context of Bitcoin typically means copying the amount of "change" (the leftover amount after a transaction). The translation "การเปลี่ยนแปลงข้อความ" means "text change" or "change of message," which is inaccurate and unrelated to the Bitcoin context.  

A better translation would be:  
คัดลอกทอนเงิน
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
The translation is incomplete and omits the entire last paragraph about the migration process creating a backup file and instructions on restoring it. Additionally, some parts could be more naturally phrased in Thai.

Correct translation:

การย้ายกระเป๋าจะทำให้กระเป๋านี้กลายเป็นกระเป๋าแบบคำอธิบายหนึ่งหรือมากกว่านั้น (descriptor wallets) ซึ่งจะต้องสร้างสำรองกระเป๋าใหม่ขึ้น  
ถ้ากระเป๋านี้มีสคริปต์ที่ดูได้เท่านั้น (watchonly scripts) จะมีการสร้างกระเป๋าใหม่ที่มีสคริปต์เหล่านั้น  
ถ้ากระเป๋านี้มีสคริปต์ที่แก้ไขได้แต่ไม่ได้ติดตาม (solvable but not watched scripts) จะมีการสร้างกระเป๋าใหม่ที่แตกต่างออกไปซึ่งมีสคริปต์เหล่านั้น  

กระบวนการย้ายจะสร้างสำรองกระเป๋าก่อนทำการย้าย ชื่อไฟล์สำรองจะเป็น &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak และจะอยู่ในโฟลเดอร์ของกระเป๋านี้ หากเกิดการย้ายผิดพลาด สามารถกู้คืนไฟล์สำรองได้โดยใช้ฟังก์ชัน "กู้คืนกระเป๋า" (Restore Wallet)
```

```
        <source>Form</source>
        <translation>จาก</translation>
    
YES  
The English word "Form" is incorrectly translated as "จาก" which means "from" in Thai. The correct translation for "Form" (as in a document or template) in Thai is "แบบฟอร์ม".

Correct translation:  
แบบฟอร์ม
```

```
        <source>Number of script verification threads</source>
        <translation>จำนวนของสคริปต์และเธรดการตรวจสอบ</translation>
    
YES  
The translation introduces an incorrect conjunction "และ" (and) which is not present in the source. The phrase "Number of script verification threads" refers to a count (number) of threads responsible for script verification, not "number of scripts and verification threads." The correct translation should convey just the number of threads for script verification.

Correct translation:  
จำนวนเธรดสำหรับการตรวจสอบสคริปต์
```

```
        <source>Network</source>
        <translation>และเครือข่าย</translation>
    
YES
The translation "และเครือข่าย" means "and network," which is inaccurate and adds an unnecessary conjunction "and" that is not present in the source. The correct translation should simply be:

เครือข่าย
```

```
        <source>Prune block storage to</source>
        <translation>ตัดทอนและบล็อกที่เก็บข้อมูลไปที่</translation>
    
YES  
The translation is somewhat awkward and contains an erroneous phrase. The phrase "ตัดทอนและบล็อกที่เก็บข้อมูลไปที่" literally means "cut/prune and block that store data to," which is confusing and incorrect in this context. The source phrase "Prune block storage to" means to reduce the size of the block storage (usually to a certain size limit).

A better translation would focus on "prune" referring to reducing or trimming storage, especially in a technical setting like Bitcoin.

Correct translation:  
"ตัดแต่งการเก็บข้อมูลบล็อกให้เหลือที่"
```

```
        <source>Form</source>
        <translation>จาก</translation>
    
YES  
The English word "Form" is incorrectly translated as "จาก" which means "from" in Thai. The correct translation for "Form" (as in a document or template) in Thai is "แบบฟอร์ม".

Correct translation:  
แบบฟอร์ม
```

```
        <source>Could not sign any more inputs.</source>
        <translation>ไม่สามารถลงนามการป้อนข้อมูลเพิ่มเติมได้ (Mai samart long nam kan phon khomooht permum dai).</translation>
    
YES  
The translation contains transliterated Thai within parentheses, which is unnecessary and inappropriate for a standard translation. The transliteration should be removed. The Thai translation is otherwise clear and accurate.

Correct translation:  
ไม่สามารถลงนามการป้อนข้อมูลเพิ่มเติมได้
```

```
        <source>Outbound</source>
        <extracomment>An Outbound Connection to a Peer.</extracomment>
        <translation>ออกเดินทาง (òk dern thāng)</translation>
    
YES  
The translation "ออกเดินทาง (òk dern thāng)" literally means "depart" or "to go out," which is not appropriate for the context of an "Outbound Connection" in Bitcoin networking. The term "Outbound" here refers to a connection initiated outwardly to a peer, so a more accurate translation would be "ขาออก" which is commonly used in networking to mean "outbound."

Correct translation:  
ขาออก
```

```
        <source>Whether we relay transactions to this peer.</source>
        <translation>ไม่ว่าความเราจะส่งการทำธุรกรรมไปยังเพื่อนนี้หรือไม่</translation>
    
YES  
The translation contains a typo and awkward phrasing. The word "ความเราจะ" is incorrect and should be "เราจะ" (we will). Also, "เพื่อนนี้" is too informal for "this peer" in the context of Bitcoin networking; a better term would be "เพียร์นี้" or "โหนดนี้". The phrase "Whether we relay transactions to this peer." is a query or a statement about the condition of relaying transactions, so the translation should reflect that condition better.

Correct translation:  
"เราจะส่งธุรกรรมไปยังเพียร์นี้หรือไม่"  
or more formally:  
"จะส่งธุรกรรมไปยังเพียร์นี้หรือไม่"
```

```
        <source>Last Transaction</source>
        <translation>ธุรกรรมล่าสุด (Thurakam lasut)</translation>
    
YES
The translation includes an unnecessary transliteration "(Thurakam lasut)" which is not standard or needed. The Thai phrase "ธุรกรรมล่าสุด" correctly means "Last Transaction" and should be used alone without extra phonetic spelling.

Correct translation:
ธุรกรรมล่าสุด
```

```
        <source>Last Send</source>
        <translation>ส่งสุดท้าย (Song Soot Thai)</translation>
    
YES  
The translation includes an unnecessary transliteration "(Song Soot Thai)" in parentheses, which is not appropriate in this context. The correct translation should be concise and clear without the transliteration.

Correct translation:  
ส่งสุดท้าย
```

```
        <source>Inbound: initiated by peer</source>
        <extracomment>Explanatory text for an inbound peer connection.</extracomment>
        <translation>ขาเข้า: เริ่มต้นโดยปัสสาวะ</translation>
    
YES  
The translation mistakenly uses the word "ปัสสาวะ" which means "urinate," making the phrase nonsensical and inappropriate. The correct term should denote "peer," which in this context is a network peer, not a biological action.

Correct translation:  
ขาเข้า: เริ่มต้นโดยเพื่อนร่วมเครือข่าย
```

```
        <source>Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>ที่อยู่ Copy</translation>
    
YES
The translation incorrectly mixes Thai and English by placing the English word "Copy" after "ที่อยู่" (address). The correct translation should use the proper Thai verb for "copy" before "ที่อยู่" or simply translate the phrase as "คัดลอกที่อยู่".

Correct translation:
คัดลอกที่อยู่
```

```
        <source>Copy address</source>
        <translation>ที่อยู่ Copy</translation>
    
YES  
The translation incorrectly places the English word "Copy" after "ที่อยู่" (address), which is unnatural in Thai. The correct translation should convey the command "Copy address" in a natural and clear way, such as "คัดลอกที่อยู่".  

Correct translation:  
คัดลอกที่อยู่
```

```
        <source>Copy label</source>
        <translation>คัดลอก  ป้าย</translation>
    
YES
There is an extra space between "คัดลอก" and "ป้าย" in the translation. The correct translation should have only one space:

คัดลอก ป้าย
```

```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
YES
The translation "การส่งออกล้มเหลว" means "Export failed," which does not correspond to the source text "Label." 

Correct translation:
ป้ายชื่อ
```

```
        <source>Copy fee</source>
        <translation>ค่าลอกสำเนา (kâa lók sàm-náo)</translation>
    
YES  
The translation "ค่าลอกสำเนา (kâa lók sàm-náo)" means "copying fee" or "fee for photocopying," which is not appropriate in the Bitcoin context for "Copy fee." Here, "Copy fee" likely refers to the action of copying the fee amount or fee data, not a literal payment for making a copy.

A more accurate translation for "Copy fee" related to copying a fee value (e.g., in a UI button) would be simply:

"คัดลอกค่าธรรมเนียม"  

This means "copy fee" in the sense of copying the fee amount. Also, the transliteration in parentheses is unnecessary in UI text.

Correct translation:  
คัดลอกค่าธรรมเนียม
```

```
        <source>Copy change</source>
        <translation>การเปลี่ยนแปลงข้อความ</translation>
    
YES  
The English phrase "Copy change" in the context of Bitcoin typically means copying the amount of "change" (the leftover amount after a transaction). The translation "การเปลี่ยนแปลงข้อความ" means "text change" or "change of message," which is inaccurate and unrelated to the Bitcoin context.  

A better translation would be:  
คัดลอกทอนเงิน
```

```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
YES
The translation "การส่งออกล้มเหลว" means "Export failed," which does not correspond to the source text "Label." 

Correct translation:
ป้ายชื่อ
```

```
        <source>Copy address</source>
        <translation>ที่อยู่ Copy</translation>
    
YES  
The translation incorrectly places the English word "Copy" after "ที่อยู่" (address), which is unnatural in Thai. The correct translation should convey the command "Copy address" in a natural and clear way, such as "คัดลอกที่อยู่".  

Correct translation:  
คัดลอกที่อยู่
```

```
        <source>Copy label</source>
        <translation>คัดลอก  ป้าย</translation>
    
YES
There is an extra space between "คัดลอก" and "ป้าย" in the translation. The correct translation should have only one space:

คัดลอก ป้าย
```

```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
YES
The translation "การส่งออกล้มเหลว" means "Export failed," which does not correspond to the source text "Label." 

Correct translation:
ป้ายชื่อ
```
</details>
