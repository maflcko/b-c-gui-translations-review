# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>vi</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bvi%5D%20low%20quality)


```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>Các địa chỉ này là các địa chỉ Bitcoin dùng để thanh toán.Luôn luôn kiểm tra số dư và địa chỉ nhận trước khi gởi chuyển tiền ảo. </translation>
    
YES, The translation is problematic because it incorrectly translates "amount" as "số dư" (balance) instead of "số tiền" (amount). It also incorrectly translates "coins" as "chuyển tiền ảo" (virtual money transfer) instead of "tiền ảo" (virtual currency/coins).
The correct translation should be: "Các địa chỉ này là các địa chỉ Bitcoin dùng để gửi thanh toán. Luôn luôn kiểm tra số tiền và địa chỉ nhận trước khi gửi tiền ảo."
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Proxy là &lt;b&gt; cho phép &lt;/b&gt;: %1</translation>
    
YES, The translation is grammatically incorrect and unnatural in Vietnamese. The phrase "cho phép" is typically used as a verb meaning "to allow" or "to permit." In this context, it's trying to convey the state of being "enabled," which would be better translated as "đã bật" (turned on) or "được kích hoạt" (activated).

Proxy là &lt;b&gt;đã bật&lt;/b&gt;: %1
```

```
        <source>Backup wallet to another location</source>
        <translation>Backup ví đến một địa chỉ khác</translation>
    
YES, The translation uses "địa chỉ" (address) where it should use "vị trí" (location) to accurately reflect the English source text. The context of backing up a wallet implies copying it to a different *place* or *location*, not necessarily a different network or wallet *address*.
Correct translation: Backup ví đến một vị trí khác
```

```
        <source>Change Passphrase…</source>
        <translation>Thay dổi Passphrase…</translation>
    
YES, The translation is problematic due to incorrect word usage. The word "dổi" in Vietnamese means "to change" in the sense of "to exchange" or "to convert," which is not the intended meaning of "change passphrase." The correct word to use here is "đổi."

Correct translation:
Thay đổi Passphrase…
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Đăng ký lời nhắn với địa chỉ Bitcoin của bạn để chứng minh quyền sở hữu chúng</translation>
    
YES - The Vietnamese word "Đăng ký" translates to "register" or "sign up" in English, which is not the intended meaning of "sign" in this context. The correct translation for "sign messages" in this context would be "Ký tin nhắn". Additionally, the pronoun "chúng" is used to refer to "addresses", which is grammatically incorrect as "addresses" is plural. The correct translation should be "chúng" (them) to refer to the addresses.

Correct translation: Ký tin nhắn với địa chỉ Bitcoin của bạn để chứng minh quyền sở hữu chúng.
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Kết nối với mạng Bitcoin thông qua một proxy SOCKS5 riêng cho các dịch vụ Tor hành.</translation>
    
YES, The translation is completely inaccurate and does not reflect the meaning of the source text. It describes connecting to the Bitcoin network via a proxy, which is unrelated to loading a partially signed transaction.

Correct translation: Tải Giao dịch Bitcoin Đã ký một phần
```

```
        <source>Open Wallet</source>
        <translation>Mớ ví</translation>
    
YES, the translation is incorrect. The Vietnamese word "Mớ" translates to "mess" or "clutter", which is not appropriate in this context. The correct translation for "Open Wallet" in Vietnamese should be "Mở Ví".

NO
```

```
        <source>Close wallet</source>
        <translation>Đông ví</translation>
    
YES, The translation is inaccurate. "Đông ví" means "freeze wallet", not "close wallet". The correct translation should be "Đóng ví".
Đóng ví
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Hiển thị %1 tin nhắn hỗ trợ để nhận được danh sách Bitcoin command-line khả dụng</translation>
    
YES: The translation uses "tin nhắn hỗ trợ" (support message) which is not the most natural way to refer to a help message in this context. A more appropriate translation would be "thông điệp trợ giúp" or simply "trợ giúp".

Corrected translation: Hiển thị thông điệp trợ giúp %1 để nhận được danh sách các tùy chọn dòng lệnh Bitcoin khả dụng.
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Ví thì &lt;b&gt;được mã hóa &lt;/b&gt; và hiện tại &lt;b&gt;đã khóa&lt;/b&gt;</translation>
    
YES, The translation incorrectly states that the wallet is "locked" when the source text indicates it is "unlocked". The Vietnamese word for "unlocked" is "đã mở khóa".

Ví thì &lt;b&gt;được mã hóa &lt;/b&gt; và hiện tại &lt;b&gt;đã mở khóa&lt;/b&gt;
```

```
        <source>Open Wallet</source>
        <extracomment>Title of window indicating the progress of opening of a wallet.</extracomment>
        <translation>Mớ ví</translation>
    
YES - The translation "Mớ ví" is incorrect and does not accurately convey the meaning of "Open Wallet". "Mở ví" would be the correct translation for opening a wallet in Vietnamese.
Mở ví
```

```
        <source>Close wallet</source>
        <translation>Đông ví</translation>
    
YES, The translation is inaccurate. "Đông ví" means "freeze wallet", not "close wallet". The correct translation should be "Đóng ví".
Đóng ví
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Không xác định. Tiền đồng bộ hóa Headers (%1, %2%)...</translation>
    
YES. The translation uses "tiền đồng bộ hóa" which translates to "money synchronization" or "pre-synchronization money". This is not accurate for the intended meaning of "pre-syncing Headers" in the context of Bitcoin. The correct translation should convey the idea of synchronizing headers *before* the main synchronization process.

NO. Unknown. Pre-syncing Headers (%1, %2%)…
```

```
        <source>Number of script verification threads</source>
        <translation>Số lượng tập lệnh và chuỗi xác minh</translation>
    
YES, The translation is inaccurate and adds an unintended meaning. The original English phrase "Number of script verification threads" refers to the number of threads used for verifying scripts in Bitcoin. The translation "Số lượng tập lệnh và chuỗi xác minh" translates to "Number of scripts and verification threads," which suggests that both scripts and threads are being counted or verified, rather than the threads being used for script verification.

A more accurate translation would be:
"Số lượng chuỗi xác minh tập lệnh"
```

```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>Có đặt trừ phí khỏi số tiền làm mặc định hay không.</translation>
    
YES - The provided translation uses the Vietnamese word "mặc định" which means "default" in English. However, the provided translation is in Indonesian, not Vietnamese.

Correct translation:
<translation>Có đặt trừ phí khỏi số tiền làm mặc định hay không.</translation>
```

```
        <source>Enable coin control features</source>
        <translation>Bật tính năng kiểm soát và tiền xu</translation>
    
YES, the translation is problematic. The phrase "kiểm soát và tiền xu" literally translates to "control and coins," which is an awkward and incorrect way to express "coin control" in the context of Bitcoin. The term "coin control" in Bitcoin refers to the ability to select specific unspent transaction outputs (UTXOs) when making a transaction.

A more accurate and natural translation would be:

YES, The translation is problematic. The phrase "kiểm soát và tiền xu" literally translates to "control and coins," which is an awkward and incorrect way to express "coin control" in the context of Bitcoin. The term "coin control" in Bitcoin refers to the ability to select specific unspent transaction outputs (UTXOs) when making a transaction.

A more accurate and natural translation would be:

Bật tính năng kiểm soát đồng xu
```

```
        <source>0/unconfirmed, in memory pool</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that is in the memory pool.</extracomment>
        <translation>0/xác nhận, ở trong bể bộ nhớ - memory pool</translation>
    
YES: The translation incorrectly translates "unconfirmed" and includes English text in the translation.
0/chưa xác nhận, trong mempool
```

```
        <source>0/unconfirmed, not in memory pool</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that is not in the memory pool.</extracomment>
        <translation>0/xác nhận, không ở trong bể bộ nhớ - memory pool</translation>
    
YES, The translation incorrectly translates "unconfirmed" to "xác nhận" which means "confirmed". The format specifier % is missing.
0/chưa xác nhận, không ở trong bể bộ nhớ
```

```
        <source>Error reading %s! Transaction data may be missing or incorrect. Rescanning wallet.</source>
        <translation>Lỗi khi đọc%s! Dữ liệu giao dịch có thể bị thiếu hoặc không chính xác. Đang quét lại ví.</translation>
    
YES - The translation has a spacing issue: there is no space between "đọc" and "%s". The correct translation is "Lỗi khi đọc %s! Dữ liệu giao dịch có thể bị thiếu hoặc không chính xác. Đang quét lại ví.".
```

```
        <source>Listening for incoming connections failed (listen returned error %s)</source>
        <translation>Lắng nghe những kết nối thất bại sắp xảy ra (lắng nghe lỗi được trả về %s)</translation>
    
YES - The translation is grammatically awkward and doesn't accurately convey the original meaning. "sắp xảy ra" (about to happen) is not appropriate here.

Correct translation: Lắng nghe các kết nối đến thất bại (listen trả về lỗi %s)
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>Giao dịch cần thay đổi địa chỉ, nhưng chúng tôi không thể tạo địa chỉ đó.</translation>
    
YES, the translation incorrectly uses "thay đổi địa chỉ" (change address) in the sense of an address that needs to be changed, rather than a Bitcoin change address. In the context of Bitcoin, a "change address" is a specific term for a Bitcoin address where unspent transaction outputs are returned to the sender.

The correct translation should reflect this specific meaning of "change address".

NO
```

```
        <source>Unable to parse -maxuploadtarget: '%s'</source>
        <translation>Không thể parse -maxuploadtarget '%s</translation>
    
YES - The closing single quote (') is missing in the translated string.
Không thể parse -maxuploadtarget: '%s'
```
</details>
