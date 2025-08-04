# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>th</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bth%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>นี่คือลิงก์ที่อยู่ Bitcoin ของคุณสำหรับการส่งการชำระเงิน ควรตรวจสอบจำนวนเงินและที่อยู่ผู้รับก่อนการส่งเหรียญ</translation>
    
YES, The word "ลิงก์" (link) is not in the original English text and implies that the addresses are links, which is incorrect. The translation should convey that these are simply addresses.

NO
```

```
        <source>Copy Address</source>
        <translation>ที่อยู่</translation>
    
YES. The translation is incomplete and inaccurate. The source text "Copy Address" implies an action to copy a Bitcoin address, but the translation only provides "ที่อยู่" which means "address" in Thai.

Correct translation: คัดลอกที่อยู่
```

```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
YES
The Thai translation "การส่งออกล้มเหลว" means "Export failed". This is not an accurate translation for "Label". There are no format specifiers to check.
NO
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>ป้อนวลีรหัสใหม่สำหรับกระเป๋าสตางค์. 1.กรุณาใช้วลีรหัสผ่านของ 2.สิบตัวอักษรสุ่มหรือมากกว่า 2,หรือ 3แปดคำหรือมากกว่านั้น3</translation>
    
YES. The translation is problematic because it has introduced arbitrary numbers (1, 2, 3) and incorrect spacing. The formatting of the bolded text is also lost, and the meaning is slightly altered due to the nonsensical structure.

Correct translation: ป้อนวลีรหัสใหม่สำหรับกระเป๋าสตางค์.&lt;br/&gt;กรุณาใช้วลีรหัสผ่านที่มี &lt;b&gt;ตัวอักษรสุ่มสิบตัวขึ้นไป&lt;/b&gt; หรือ &lt;b&gt;คำแปดคำขึ้นไป&lt;/b&gt;.
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>เกิดข้อผิดพลาดร้ายแรง กรุณาตรวจสอบว่าไฟล์การตั้งค่าสามารถเขียนได้หรือไม่ หรือลองรันด้วยคำสั่ง</translation>
    
YES: The translation is incomplete and missing the command "-nosettings" which is crucial for the user to understand how to run the application. Additionally, the Thai translation of "settings file" should include the word "settings" to be clearer in the context.
เกิดข้อผิดพลาดร้ายแรง กรุณาตรวจสอบว่าไฟล์การตั้งค่าสามารถเขียนได้หรือไม่ หรือลองรันด้วยคำสั่ง -nosettings
```

```
        <source>Onion</source>
        <comment>network name</comment>
        <extracomment>Name of Tor network in peer info</extracomment>
        <translation>หัวหอม (Hua Khom)</translation>
    
YES. The translation of "Onion" as "หัวหอม (Hua Khom)" which means "onion" in Thai, is a literal translation and does not convey the intended meaning in the context of the Tor network. In Bitcoin and network contexts, "Onion" refers to the onion routing network.

The correct translation should be something that refers to the Tor network, or the onion routing aspect.

Correct translation: เครือข่าย Onion (Kruea Khai Onion) or โทร์ (Tor)
```

```
        <source>CJDNS</source>
        <comment>network name</comment>
        <extracomment>Name of CJDNS network in peer info</extracomment>
        <translation>CJDNS (แปลงชื่อย่อ)</translation>
    
YES, The translation includes an extraneous phrase "(แปลงชื่อย่อ)" which translates to "(abbreviated name conversion)" in English, which is not present in the source text and is thus erroneous content.

The correct translation should be:
CJDNS
```

```
        <source>Outbound</source>
        <extracomment>An outbound connection to a peer. An outbound connection is a connection initiated by us.</extracomment>
        <translation>ออกเดินทาง (òk dern thāng)</translation>
    
YES: The translation "ออกเดินทาง (òk dern thāng)" means "depart" or "set off," which is not accurate for "Outbound" in the context of Bitcoin connections. The correct translation should refer to an outgoing connection.
Correct translation: ขาออก (khā òk)
```

```
        <source>Full Relay</source>
        <extracomment>Peer connection type that relays all network information.</extracomment>
        <translation>การแข่งขันรีเลย์เต็มรูปแบบ</translation>
    
YES
The translation is inaccurate and does not convey the intended meaning of "Full Relay" in the context of Bitcoin. The Thai translation means "Full Relay Competition," which is nonsensical.

Correct translation: การรีเลย์แบบเต็มรูปแบบ
```

```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>การวิ่งผลัดบล็อก</translation>
    
YES - The translation "การวิ่งผลัดบล็อก" (kan wing phlat blok) literally means "block relay race" or "block baton pass". While "relay" is a component, the meaning is not accurate for "Block Relay" in the Bitcoin context. A better translation would be "การส่งต่อบล็อก" (kan song tor blok), which means "block forwarding" or "block transmission".

NO
```

```
        <source>Sign message…</source>
        <translation>ป้าย  ข้อความ…</translation>
    
YES, The translation is problematic as it is a literal translation and does not convey the intended meaning. The word "ป้าย" means "sign" as in a road sign or a label, not "sign" as in to sign a document or message. The intended meaning is to sign a message.
Correct translation: ลงนามข้อความ…
```

```
        <source>Receiving addresses</source>
        <translation>ตัวเลือกคำสั่งในบรรทัดคำสั่ง</translation>
    
YES, The translation is incorrect and nonsensical in the context of Bitcoin. The Thai text "ตัวเลือกคำสั่งในบรรทัดคำสั่ง" translates to "Command-line command options," which is unrelated to receiving addresses.

Correct translation: ที่อยู่สำหรับรับ
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation> การสร้างคีย์ HD คือ&lt;b&gt;พิการ&lt;/b&gt;</translation>
    
YES, The word "พิการ" translates to "disabled" but in Thai, it usually refers to a physical disability. For a software setting like "disabled", the word "ปิดใช้งาน" would be more appropriate.

Correct translation: การสร้างคีย์ HD ถูก&lt;b&gt;ปิดใช้งาน&lt;/b&gt;
```

```
        <source>Private key &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>กุญแจส่วนตัว &lt;b&gt;พิการ&lt;/b&gt;</translation>
    
YES: The Thai word "พิการ" (phí-gaan) directly translates to "disabled" in the sense of a physical disability or impairment. In the context of a Bitcoin private key, it's more appropriate to use a term that conveys being "deactivated," "invalidated," or "turned off." A better translation would be "ปิดใช้งาน" (pìt chái ngaan), which means "disabled" or "deactivated."

Correct translation: กุญแจส่วนตัว &lt;b&gt;ปิดใช้งาน&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>กระเป๋าเงินคือ &lt;b&gt;เข้ารหัส&lt;/b&gt; และปัจจุบัน &lt;b&gt;ปลดล็อก&lt;/b&gt;</translation>
    
YES: The Thai translation for "Wallet is encrypted" is incorrect. The word "คือ" (kue) means "is" but in this context, it is better to use a more direct phrasing.
Correct translation: กระเป๋าเงินถูก &lt;b&gt;เข้ารหัส&lt;/b&gt; และปัจจุบัน &lt;b&gt;ปลดล็อก&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>กระเป๋าสตางค์คือ &lt;b&gt;เข้ารหัส&lt;/b&gt; และปัจจุบัน &lt;b&gt;ล็อค&lt;/b&gt;</translation>
    
YES - The Thai translation is grammatically incorrect and unnatural. The words "เข้ารหัส" (encrypted) and "ล็อค" (locked) are used as adjectives, but they are placed after the verb "คือ" (is) in a way that suggests they are nouns or attributes being listed, rather than describing the state of the wallet. A more natural translation would place them directly after the noun they modify.

Correct translation: กระเป๋าสตางค์ถูก &lt;b&gt;เข้ารหัส&lt;/b&gt; และ &lt;b&gt;ล็อค&lt;/b&gt; อยู่ในขณะนี้
```

```
        <source>Copy address</source>
        <translation>ที่อยู่ Copy</translation>
    
YES, The translation has a word order issue. The verb "Copy" should precede the noun "address".
The correct translation is: คัดลอกที่อยู่
```

```
        <source>Copy label</source>
        <translation>คัดลอก  ป้าย</translation>
    
YES, the translation includes an unnecessary space between "คัดลอก" and "ป้าย".
Correct translation: คัดลอกป้าย
```

```
        <source>Copy change</source>
        <translation>การเปลี่ยนแปลงข้อความ</translation>
    
YES
The translation is inaccurate and does not convey the meaning of "Copy change" in the context of Bitcoin. In Bitcoin, "change" refers to the leftover amount of Bitcoin after a transaction. The translation "การเปลี่ยนแปลงข้อความ" means "message change" which is unrelated.
Correct translation: คัดลอกเงินทอน
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
The translation is incomplete. The last two sentences of the source text are missing in the translation. Additionally, the translation incorrectly states that a new wallet will be created with solvable but not watched scripts. The source text indicates that a *different and new wallet* will be created with those scripts.

Here's the corrected and complete translation:

NO
```

```
        <source>Form</source>
        <translation>จาก</translation>
    
YES
The translation is inaccurate. The Thai word "จาก" means "from", which is not the correct translation for "Form" in the context of Bitcoin, which likely refers to a document or a field to fill out.

Correct translation: แบบฟอร์ม
```

```
        <source>Number of script verification threads</source>
        <translation>จำนวนของสคริปต์และเธรดการตรวจสอบ</translation>
    
YES, the translation is problematic as it incorrectly translates "script verification threads" as "script and verification threads". The word "and" is not present in the source text.

The correct translation should be:
จำนวนเธรดสำหรับการตรวจสอบสคริปต์
```

```
        <source>Network</source>
        <translation>และเครือข่าย</translation>
    
YES, The translation is incorrect and doesn't convey the meaning of "Network". It translates to "And network" which is grammatically incorrect and nonsensical in this context.
Correct translation: เครือข่าย
```

```
        <source>Prune block storage to</source>
        <translation>ตัดทอนและบล็อกที่เก็บข้อมูลไปที่</translation>
    
YES: The translation is grammatically incorrect and does not convey the intended meaning of pruning block storage. The phrase "ตัดทอนและบล็อกที่เก็บข้อมูลไปที่" literally translates to "prune and block storage to", which is awkward and doesn't make sense in the context of Bitcoin.

Correct translation: ตัดทอนการจัดเก็บข้อมูลบล็อกไปที่
```

```
        <source>Form</source>
        <translation>จาก</translation>
    
YES
The translation is inaccurate. The Thai word "จาก" means "from", which is not the correct translation for "Form" in the context of Bitcoin, which likely refers to a document or a field to fill out.

Correct translation: แบบฟอร์ม
```

```
        <source>Could not sign any more inputs.</source>
        <translation>ไม่สามารถลงนามการป้อนข้อมูลเพิ่มเติมได้ (Mai samart long nam kan phon khomooht permum dai).</translation>
    
YES - The translation is problematic because it is an incorrect translation of the English phrase. The correct translation should be "ไม่สามารถลงนามอินพุตได้อีกต่อไป" (Mai samart long nam input dai ik tor pai). The original translation also includes an unnecessary phonetic transcription in parentheses.

ไม่สามารถลงนามอินพุตได้อีกต่อไป
```

```
        <source>Outbound</source>
        <extracomment>An Outbound Connection to a Peer.</extracomment>
        <translation>ออกเดินทาง (òk dern thāng)</translation>
    
YES. The translation is problematic. It translates "Outbound" as "departing" or "going on a journey". While this is a literal translation of "outbound", it doesn't fit the technical context of a Bitcoin peer connection. The correct translation should reflect the direction of the connection.

Correct translation: ขาออก (khǎa òk)
```

```
        <source>Whether we relay transactions to this peer.</source>
        <translation>ไม่ว่าความเราจะส่งการทำธุรกรรมไปยังเพื่อนนี้หรือไม่</translation>
    
YES, The translation is grammatically incorrect and does not convey the intended meaning. The phrase "ความเรา" (khwam rao) is awkward and unnatural in this context. A more accurate translation would be "เรา" (rao) meaning "we".

NO
```

```
        <source>Last Transaction</source>
        <translation>ธุรกรรมล่าสุด (Thurakam lasut)</translation>
    
YES, The translation contains Korean characters which are not part of the Thai language. The correct translation of "Last Transaction" to Thai is "รายการล่าสุด".
ธุรกรรมล่าสุด (Thurakam lasut)
```

```
        <source>Last Send</source>
        <translation>ส่งสุดท้าย (Song Soot Thai)</translation>
    
YES - The Thai translation "ส่งสุดท้าย (Song Soot Thai)" directly translates to "Last Send (Song Soot Thai)" in English. The parenthetical part "Song Soot Thai" is redundant and doesn't add meaning. The correct translation for "Last Send" in Thai would simply be "ส่งครั้งสุดท้าย".

NO
```

```
        <source>Inbound: initiated by peer</source>
        <extracomment>Explanatory text for an inbound peer connection.</extracomment>
        <translation>ขาเข้า: เริ่มต้นโดยปัสสาวะ</translation>
    
YES: The translation uses "ปัสสาวะ" which means "urine" and is completely irrelevant and nonsensical in the context of Bitcoin. The correct translation should reflect that the connection was initiated by a peer.

Correct translation: ขาเข้า: เริ่มต้นโดยเพื่อน
```

```
        <source>Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>ที่อยู่ Copy</translation>
    
YES
The translation is problematic because the word order is incorrect and sounds unnatural in Thai. The word "Copy" should precede "address".

Correct translation: คัดลอกที่อยู่
```

```
        <source>Copy address</source>
        <translation>ที่อยู่ Copy</translation>
    
YES, The translation has a word order issue. The verb "Copy" should precede the noun "address".
The correct translation is: คัดลอกที่อยู่
```

```
        <source>Copy label</source>
        <translation>คัดลอก  ป้าย</translation>
    
YES, the translation includes an unnecessary space between "คัดลอก" and "ป้าย".
Correct translation: คัดลอกป้าย
```

```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
YES
The Thai translation "การส่งออกล้มเหลว" means "Export failed". This is not an accurate translation for "Label". There are no format specifiers to check.
NO
```

```
        <source>Copy fee</source>
        <translation>ค่าลอกสำเนา (kâa lók sàm-náo)</translation>
    
YES: The translation uses "ค่าลอกสำเนา" which translates to "copy fee". While technically correct, it's not the most natural or common way to express this in Thai in the context of Bitcoin fees. A more appropriate translation would be "ค่าธรรมเนียมการคัดลอก" or simply "ค่าธรรมเนียม". The parenthetical pronunciation guide is also not standard for translations.

Correct translation: ค่าธรรมเนียม
```

```
        <source>Copy change</source>
        <translation>การเปลี่ยนแปลงข้อความ</translation>
    
YES
The translation is inaccurate and does not convey the meaning of "Copy change" in the context of Bitcoin. In Bitcoin, "change" refers to the leftover amount of Bitcoin after a transaction. The translation "การเปลี่ยนแปลงข้อความ" means "message change" which is unrelated.
Correct translation: คัดลอกเงินทอน
```

```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
YES
The Thai translation "การส่งออกล้มเหลว" means "Export failed". This is not an accurate translation for "Label". There are no format specifiers to check.
NO
```

```
        <source>Copy address</source>
        <translation>ที่อยู่ Copy</translation>
    
YES, The translation has a word order issue. The verb "Copy" should precede the noun "address".
The correct translation is: คัดลอกที่อยู่
```

```
        <source>Copy label</source>
        <translation>คัดลอก  ป้าย</translation>
    
YES, the translation includes an unnecessary space between "คัดลอก" and "ป้าย".
Correct translation: คัดลอกป้าย
```

```
        <source>Label</source>
        <translation>การส่งออกล้มเหลว</translation>
    
YES
The Thai translation "การส่งออกล้มเหลว" means "Export failed". This is not an accurate translation for "Label". There are no format specifiers to check.
NO
```
</details>
