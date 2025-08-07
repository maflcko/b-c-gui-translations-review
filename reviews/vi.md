# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>vi</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bvi%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>Các địa chỉ này là các địa chỉ Bitcoin dùng để thanh toán.Luôn luôn kiểm tra số dư và địa chỉ nhận trước khi gởi chuyển tiền ảo. </translation>
    
YES
There are several issues with the translation:
1. The Vietnamese translation introduces spacing issues: there is no space after the full stop that ends the first sentence ("thanh toán.Luôn").
2. The meaning deviates: the source says "sending payments", but the translation simply says "dùng để thanh toán" (used for payments), omitting "for sending".
3. "Số dư" means "balance", not "amount", so this is a mistranslation of "amount". The source instructs to check "the amount and the receiving address", but the translation says "số dư và địa chỉ nhận".
4. "Gởi chuyển tiền ảo" (sending virtual money) is not accurate. "Coin" refers specifically to Bitcoin, not generic virtual currency.
5. Some word choices are awkward ("gởi chuyển tiền ảo" is not idiomatic).

Correct translation:
Đây là các địa chỉ Bitcoin của bạn để gửi thanh toán. Luôn kiểm tra số tiền và địa chỉ nhận trước khi gửi coin.
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Proxy là &lt;b&gt; cho phép &lt;/b&gt;: %1</translation>
    
YES
There is a spacing issue within the <b> tags, and the phrase order is slightly awkward. The phrase "Proxy là cho phép" is unnatural in Vietnamese. A better translation (more natural and accurate) would be:

Proxy được <b>bật</b>: %1

Correct translation:
<translation>Proxy được &lt;b&gt;bật&lt;/b&gt;: %1</translation>
```

```
        <source>Backup wallet to another location</source>
        <translation>Backup ví đến một địa chỉ khác</translation>
    
YES
The translation incorrectly translates "another location" as "một địa chỉ khác" which means "another address". "Location" should be "vị trí" or "địa điểm" in this context. Also, "Backup" should be replaced with the Vietnamese equivalent "Sao lưu".

Correct translation:
Sao lưu ví vào một vị trí khác
```

```
        <source>Change Passphrase…</source>
        <translation>Thay dổi Passphrase…</translation>
    
YES
There is a spelling error in the word "dổi" (should be "đổi"). Additionally, "Passphrase" could be translated as "cụm mật khẩu" for better localization, though it is sometimes kept in English. Furthermore, ensure that the ellipsis character (…) matches the source, which it does.

Correct translation:
Thay đổi Passphrase…
or
Thay đổi cụm mật khẩu…
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Đăng ký lời nhắn với địa chỉ Bitcoin của bạn để chứng minh quyền sở hữu chúng</translation>
    
YES
The translation is inaccurate. "Sign messages" is incorrectly translated as "Đăng ký lời nhắn", which means "register a message". The correct translation should use "Ký" (to sign). Additionally, "sign messages with your Bitcoin addresses" is better as "Ký các tin nhắn bằng địa chỉ Bitcoin của bạn".

Correct translation:
Ký các tin nhắn bằng địa chỉ Bitcoin của bạn để chứng minh bạn sở hữu chúng
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Kết nối với mạng Bitcoin thông qua một proxy SOCKS5 riêng cho các dịch vụ Tor hành.</translation>
    
YES
The translation does not correspond to the source English text. The source refers to "Load Partially Signed Bitcoin Transaction", but the translation incorrectly talks about connecting to the Bitcoin network via a SOCKS5 proxy for Tor services.

Correct translation:
Tải giao dịch Bitcoin đã ký một phần
```

```
        <source>Open Wallet</source>
        <translation>Mớ ví</translation>
    
YES
There is a typo in the translation: "Mớ ví" should be "Mở ví".

Correct translation:
Mở ví
```

```
        <source>Close wallet</source>
        <translation>Đông ví</translation>
    
YES
The word "Đông" is a typographical or typographical error; the correct word in Vietnamese should be "Đóng" which means "close" in this context. "Đông ví" is meaningless, while "Đóng ví" is the natural and correct phrase.

Correct translation:
Đóng ví
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Hiển thị %1 tin nhắn hỗ trợ để nhận được danh sách Bitcoin command-line khả dụng</translation>
    
YES
The translation is not entirely accurate and sounds unnatural in Vietnamese. Specifically, "tin nhắn hỗ trợ" is an incorrect translation for "help message," and "Bitcoin command-line khả dụng" is awkward. It does not clearly convey "possible Bitcoin command-line options." Additionally, the order of words can be improved for clarity and naturalness.

Correct translation:
Hiển thị thông báo trợ giúp %1 để xem danh sách các tùy chọn dòng lệnh Bitcoin có thể sử dụng
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Ví thì &lt;b&gt;được mã hóa &lt;/b&gt; và hiện tại &lt;b&gt;đã khóa&lt;/b&gt;</translation>
    
YES
The translation is inaccurate: "unlocked" was translated as "đã khóa" ("locked"), which is the opposite meaning. Also, the placement of spaces within the <b> tags is inconsistent between source and translation.

Correct translation:
Ví &lt;b&gt;được mã hóa&lt;/b&gt; và hiện tại &lt;b&gt;được mở khóa&lt;/b&gt;
```

```
        <source>Open Wallet</source>
        <extracomment>Title of window indicating the progress of opening of a wallet.</extracomment>
        <translation>Mớ ví</translation>
    
YES
There is a typo in the translation: "Mớ ví" should be "Mở ví". The word "mớ" is incorrect; "mở" means "open" in Vietnamese.

Correct translation:
Mở ví
```

```
        <source>Close wallet</source>
        <translation>Đông ví</translation>
    
YES
The word "Đông" is a typographical or typographical error; the correct word in Vietnamese should be "Đóng" which means "close" in this context. "Đông ví" is meaningless, while "Đóng ví" is the natural and correct phrase.

Correct translation:
Đóng ví
```

```
        <source>Number of script verification threads</source>
        <translation>Số lượng tập lệnh và chuỗi xác minh</translation>
    
YES
The translation is inaccurate. The English phrase refers to the number of threads (i.e., processing threads or worker processes), not the number of scripts and verification chains. The correct translation should focus on "threads" related to the verification of scripts.

Correct translation:
Số lượng luồng xác minh tập lệnh
```

```
        <source>Enable coin control features</source>
        <translation>Bật tính năng kiểm soát và tiền xu</translation>
    
YES
There is a translation error: "và tiền xu" means "and coins," which adds an unintended conjunction "and" and is not natural in Vietnamese. The phrase "coin control" is usually translated as "kiểm soát đồng tiền" or more specifically "kiểm soát đầu ra" or kept as "coin control" in context.

Correct translation:
Bật tính năng kiểm soát đồng tiền
```

```
        <source>0/unconfirmed, in memory pool</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that is in the memory pool.</extracomment>
        <translation>0/xác nhận, ở trong bể bộ nhớ - memory pool</translation>
    
YES
The translation incorrectly adds "memory pool" in English after the Vietnamese phrase, which is unnecessary if the application is localized. Also, it uses "bể bộ nhớ", which is less common; "bộ nhớ tạm thời" or simply "bộ nhớ" are more natural in Vietnamese Bitcoin contexts. There is a stray space before the hyphen.

Correct translation:
0/chưa được xác nhận, trong bộ nhớ tạm thời
```

```
        <source>0/unconfirmed, not in memory pool</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that is not in the memory pool.</extracomment>
        <translation>0/xác nhận, không ở trong bể bộ nhớ - memory pool</translation>
    
YES
The translation "0/xác nhận, không ở trong bể bộ nhớ - memory pool" is problematic for a few reasons:
1. The slash in "0/xác nhận" is unusual and not idiomatic in Vietnamese. It should be "0 xác nhận".
2. The phrase "bể bộ nhớ - memory pool" is awkward; either keep "memory pool" in parentheses or translate it. The English technical term "memory pool" is often kept as-is, but should be clearly separated, e.g. in brackets.
3. There is an unnecessary hyphen and inconsistent formatting.
4. No extra spaces or doubling, but improved phrasing is needed.

Correct translation:
0 xác nhận, không ở trong memory pool
```

```
        <source>Error reading %s! Transaction data may be missing or incorrect. Rescanning wallet.</source>
        <translation>Lỗi khi đọc%s! Dữ liệu giao dịch có thể bị thiếu hoặc không chính xác. Đang quét lại ví.</translation>
    
YES
There is a spacing issue: there should be a space between "đọc" and "%s" to match the original.

Correct translation:
Lỗi khi đọc %s! Dữ liệu giao dịch có thể bị thiếu hoặc không chính xác. Đang quét lại ví.
```

```
        <source>Listening for incoming connections failed (listen returned error %s)</source>
        <translation>Lắng nghe những kết nối thất bại sắp xảy ra (lắng nghe lỗi được trả về %s)</translation>
    
YES
The translation has both accuracy and grammar issues. The phrase "Lắng nghe những kết nối thất bại sắp xảy ra" is unnatural and misrepresents the meaning. The translation should convey that the application failed to listen for incoming connections, not that it listened to failed connections about to happen. Also, the format specifier %s was carried over, which is correct.

Correct translation:
Không thể lắng nghe các kết nối đến (listen trả về lỗi %s)
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>Giao dịch cần thay đổi địa chỉ, nhưng chúng tôi không thể tạo địa chỉ đó.</translation>
    
YES
The translation "Giao dịch cần thay đổi địa chỉ, nhưng chúng tôi không thể tạo địa chỉ đó." makes it sound as if "change" is a verb ("to change the address") rather than a noun indicating a "change address" (i.e., a specific technical term in Bitcoin referring to the address where transaction change is sent).

Correct translation:
"Giao dịch cần một địa chỉ tiền thừa, nhưng chúng tôi không thể tạo ra nó."
```

```
        <source>Unable to parse -maxuploadtarget: '%s'</source>
        <translation>Không thể parse -maxuploadtarget '%s</translation>
    
YES
The translation uses the English word "parse" instead of a Vietnamese equivalent, and missing the closing quote after %s. For clarity, "parse" should be translated, and punctuation should match the source.

Correct translation:
Không thể phân tích cú pháp -maxuploadtarget: '%s'
```
</details>

Number of issues: 20.
