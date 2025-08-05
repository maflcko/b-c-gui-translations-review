# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>vi</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bvi%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>Các địa chỉ này là các địa chỉ Bitcoin dùng để thanh toán.Luôn luôn kiểm tra số dư và địa chỉ nhận trước khi gởi chuyển tiền ảo. </translation>
    
YES  
There are spacing issues in the translation: no space after the period. Also, "số dư" (balance) is incorrect in this context; it should be "số tiền" (amount). "gởi chuyển tiền ảo" is colloquial and awkward; better to use "gửi tiền".  

Correct translation:  
Các địa chỉ này là các địa chỉ Bitcoin dùng để thanh toán. Luôn luôn kiểm tra số tiền và địa chỉ nhận trước khi gửi tiền.
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Proxy là &lt;b&gt; cho phép &lt;/b&gt;: %1</translation>
    
YES  
The translation is inaccurate and awkward. The phrase "Proxy là &lt;b&gt; cho phép &lt;/b&gt;" translates to "Proxy is &lt;b&gt; allowed &lt;/b&gt;", which is not the correct way to say "Proxy is &lt;b&gt;enabled&lt;/b&gt;". The word "enabled" in this context should be translated as "đã bật" or "được bật". Also, there are extra spaces inside the tags which should be removed.

Correct translation:  
Proxy &lt;b&gt;đã bật&lt;/b&gt;: %1
```

```
        <source>Backup wallet to another location</source>
        <translation>Backup ví đến một địa chỉ khác</translation>
    
YES
The translation inaccurately uses "đến một địa chỉ khác" which means "to another address," while the source "to another location" suggests a filesystem location or folder, not an address. Also, using the English word "Backup" is inconsistent with a full Vietnamese translation.

Correct translation:
Sao lưu ví đến một vị trí khác
```

```
        <source>Change Passphrase…</source>
        <translation>Thay dổi Passphrase…</translation>
    
YES  
The Vietnamese translation has a spelling error: "dổi" should be "đổi". Also, the word "Passphrase" can be either kept in English (if commonly used) or translated as "Cụm mật khẩu" or "Mật khẩu". Assuming the term "Passphrase" is acceptable in English, the corrected translation is:

Thay đổi Passphrase…
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Đăng ký lời nhắn với địa chỉ Bitcoin của bạn để chứng minh quyền sở hữu chúng</translation>
    
YES  
The translation uses "Đăng ký" (register/sign up) instead of the correct term for "Sign" in the cryptographic sense. In this context, "Sign messages" refers to digitally signing messages, which should be translated as "Ký" or "Ký điện tử". Using "Đăng ký" changes the meaning to registering messages, which is incorrect.

Correct translation:  
Ký lời nhắn bằng địa chỉ Bitcoin của bạn để chứng minh bạn sở hữu chúng
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Kết nối với mạng Bitcoin thông qua một proxy SOCKS5 riêng cho các dịch vụ Tor hành.</translation>
    
YES  
The provided Vietnamese translation does not match the source text at all. The source text "Load Partially Signed Bitcoin Transaction" should be translated to something related to loading a partially signed Bitcoin transaction, not connecting to the Bitcoin network via a SOCKS5 proxy for Tor services.

Correct translation:  
Tải giao dịch Bitcoin bán ký (PSBT)
```

```
        <source>Open Wallet</source>
        <translation>Mớ ví</translation>
    
YES  
The Vietnamese translation erroneously includes the character "ớ" which is incorrect in this context. The correct term for "Open Wallet" in Vietnamese should be "Mở ví".  

Correct translation:  
Mở ví
```

```
        <source>Close wallet</source>
        <translation>Đông ví</translation>
    
YES  
The translation uses "Đông ví," but the correct Vietnamese verb for "Close" in the context of closing a wallet (software action) is "Đóng." "Đông" means "winter" or "cold," which is incorrect here.

Correct translation:  
Đóng ví
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Hiển thị %1 tin nhắn hỗ trợ để nhận được danh sách Bitcoin command-line khả dụng</translation>
    
YES  
The Vietnamese translation is mostly understandable but can be improved for naturalness and correctness. The phrase "Bitcoin command-line" is left in English, which is acceptable if no Vietnamese equivalent is standard, but "khả dụng" (meaning "available") sounds slightly awkward here; "có thể sử dụng" or "khả thi" may be better. Also, the original English says "help message" which is better translated as "thông báo trợ giúp" or "thông điệp trợ giúp" instead of "tin nhắn hỗ trợ" ("tin nhắn" usually means "message" as in text message, which is less formal).

A more natural and accurate translation would be:  
"Hiển thị thông điệp trợ giúp %1 để nhận danh sách các tùy chọn dòng lệnh Bitcoin khả dụng"  

This keeps the format specifier %1 correctly placed and improves clarity and flow.
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Ví thì &lt;b&gt;được mã hóa &lt;/b&gt; và hiện tại &lt;b&gt;đã khóa&lt;/b&gt;</translation>
    
YES
The translation contradicts the English source by saying the wallet is "đã khóa" (locked) instead of "unlocked" (mở khóa or mở). Also, there is an extra space before the closing &lt;/b&gt; tag in the first bold phrase. It should exactly reflect the source meaning and avoid unnecessary spaces.

Correct translation:
Ví thì &lt;b&gt;được mã hóa&lt;/b&gt; và hiện tại &lt;b&gt;đang mở khóa&lt;/b&gt;
```

```
        <source>Open Wallet</source>
        <extracomment>Title of window indicating the progress of opening of a wallet.</extracomment>
        <translation>Mớ ví</translation>
    
YES  
The Vietnamese translation "Mớ ví" is incorrect and does not convey the intended meaning "Open Wallet". The phrase should use the verb "Mở" (to open) rather than "Mớ", which is a misspelling or a different word.  

Correct translation:  
Mở Ví
```

```
        <source>Close wallet</source>
        <translation>Đông ví</translation>
    
YES  
The translation uses "Đông ví," but the correct Vietnamese verb for "Close" in the context of closing a wallet (software action) is "Đóng." "Đông" means "winter" or "cold," which is incorrect here.

Correct translation:  
Đóng ví
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Không xác định. Tiền đồng bộ hóa Headers (%1, %2%)...</translation>
    
YES  
The translation has minor issues:  
1. "Headers" should be translated to Vietnamese for clarity, e.g., "Tiêu đề".  
2. The ellipsis in source is a single character "…", but in translation it is three periods "...". It's preferable to keep the same single ellipsis character for formatting consistency.  
3. "Pre-syncing" is better translated as "Đang đồng bộ trước" or "Đồng bộ trước" instead of "Tiền đồng bộ hóa" which is unnatural and confusing (literally "money synchronization").  

Correct translation:  
Không xác định. Đồng bộ trước Tiêu đề (%1, %2%)…
```

```
        <source>Number of script verification threads</source>
        <translation>Số lượng tập lệnh và chuỗi xác minh</translation>
    
YES  
The translation introduces the word "và" (and), which is not present in the source and changes the meaning. The source refers to the "number of threads" for script verification, not "script and verification chain."

Correct translation:  
Số lượng luồng xác minh tập lệnh
```

```
        <source>Enable coin control features</source>
        <translation>Bật tính năng kiểm soát và tiền xu</translation>
    
YES  
The translation "Bật tính năng kiểm soát và tiền xu" incorrectly translates "coin control" as "kiểm soát và tiền xu" which means "control and coins" rather than "coin control" as one phrase. The correct phrase should reflect "coin control features" as a single concept referring to granular control over coins in Bitcoin.

Correct translation:  
"Bật tính năng kiểm soát coin"  
or more naturally,  
"Bật tính năng kiểm soát tiền xu"  
to maintain clarity while keeping "coin control" intact as one concept.
```

```
        <source>0/unconfirmed, in memory pool</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that is in the memory pool.</extracomment>
        <translation>0/xác nhận, ở trong bể bộ nhớ - memory pool</translation>
    
YES  
The translation mixes Vietnamese and English untranslated terms inconsistently and does not handle "unconfirmed" correctly. The English source "0/unconfirmed, in memory pool" means the transaction has zero confirmations and is currently in the memory pool.

Correct translation:  
"0/chưa xác nhận, trong bể nhớ (memory pool)"  

Explanation:  
- "unconfirmed" should be translated as "chưa xác nhận"  
- "memory pool" can be kept in parentheses if the term is technical and widely used as is, or fully translated as "bể nhớ"  
- Use commas consistently, avoid hyphens linking phrases indiscriminately.  
- Remove unnecessary spaces around slashes and commas.
```

```
        <source>0/unconfirmed, not in memory pool</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that is not in the memory pool.</extracomment>
        <translation>0/xác nhận, không ở trong bể bộ nhớ - memory pool</translation>
    
YES  
The translation incorrectly uses "xác nhận" which means "confirmed," but the source text says "unconfirmed." Also, the phrase "bể bộ nhớ - memory pool" mixes Vietnamese and English unnecessarily. A better translation would replace "xác nhận" with "chưa xác nhận" and use the Vietnamese term "bể nhớ tạm" or just "bể nhớ" for "memory pool," or keep "memory pool" in English consistently with appropriate formatting.

Correct translation:  
0/chưa xác nhận, không có trong bể nhớ tạm
```

```
        <source>Error reading %s! Transaction data may be missing or incorrect. Rescanning wallet.</source>
        <translation>Lỗi khi đọc%s! Dữ liệu giao dịch có thể bị thiếu hoặc không chính xác. Đang quét lại ví.</translation>
    
YES  
There is a missing space after "đọc" before the format specifier "%s". The correct translation should have a space to match the natural Vietnamese phrasing and ensure readability.

Correct translation:  
Lỗi khi đọc %s! Dữ liệu giao dịch có thể bị thiếu hoặc không chính xác. Đang quét lại ví.
```

```
        <source>Listening for incoming connections failed (listen returned error %s)</source>
        <translation>Lắng nghe những kết nối thất bại sắp xảy ra (lắng nghe lỗi được trả về %s)</translation>
    
YES  
The translation is inaccurate and somewhat awkward in Vietnamese. It incorrectly suggests that "listening" itself failed or that the failure event is "about to happen," which is not the intended meaning. The phrase "thất bại sắp xảy ra" (failure is about to happen) is incorrect. The source means that the attempt to listen for incoming connections failed, and includes an error message.

A better translation would be:  
"Không thể lắng nghe các kết nối đến (lỗi trả về khi lắng nghe: %s)"
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>Giao dịch cần thay đổi địa chỉ, nhưng chúng tôi không thể tạo địa chỉ đó.</translation>
    
YES  
The translation incorrectly renders "change address" as "thay đổi địa chỉ," which literally means "change the address" instead of referring to a "change address" in the Bitcoin context (an address for returning change). The phrase "change address" should be translated as "địa chỉ nhận tiền thối lại" or "địa chỉ thối lại" to correctly convey the meaning. Also, "chúng tôi" is less typical in technical Bitcoin contexts where a neutral or passive tone is preferred.

Correct translation:  
Giao dịch cần một địa chỉ thối lại, nhưng chúng tôi không thể tạo địa chỉ đó.
```

```
        <source>Unable to parse -maxuploadtarget: '%s'</source>
        <translation>Không thể parse -maxuploadtarget '%s</translation>
    
YES  
The translation mixes English and Vietnamese, leaving "parse" untranslated and missing the closing quotation mark after %s. Additionally, the format specifier '%s' should be enclosed in single quotes as in the source, including both opening and closing quotes.

Correct translation:  
Không thể phân tích -maxuploadtarget: '%s'
```
</details>
