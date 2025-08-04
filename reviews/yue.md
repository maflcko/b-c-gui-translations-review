# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>yue</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Byue%5D%20low%20quality)


```
        <source>New</source>
        <translation>新增 N</translation>
    
YES, The translation contains a stray character 'N' which is not present in the source text.
New
新增
```

```
        <source>Delete</source>
        <translation>刪除 D</translation>
    
YES: The translation includes an extraneous " D" at the end, which is not present in the source text and appears to be a formatting error or remnant. The correct translation should be simply "刪除".

刪除
```

```
        <source>Passphrase change failed</source>
        <translation>修改密码失败</translation>
    
YES, The translation is incorrect and misleading. "Passphrase" in the context of Bitcoin typically refers to a recovery phrase (also known as a seed phrase or mnemonic phrase) used to access a wallet, not a password for an account. The Cantonese translation provided means "change password failed".

The correct translation should be:
<translation>更改助记词失败</translation>
```

```
        <source>Runaway exception</source>
        <translation>未捕获的异常</translation>
    
YES, The translation for 'Runaway exception' is not accurate. It should be translated to '失控的异常'.
'未捕获的异常' means 'Uncaught exception'.
'失控的异常' means 'Runaway exception'.
The correct translation is:
<translation>失控的异常</translation>
```

```
        <source>%1 MB</source>
        <translation>%1 MB (百萬位元組)</translation>
    
YES, The translation incorrectly adds an explanation of "MB" in Cantonese, which is not present in the source text and is therefore erroneous content. The correct translation should maintain the original format.
NO, %1 MB
```

```
        <source>About %1</source>
        <translation>关于 %1 (A)</translation>
    
YES, The translation is not accurate. The "(A)" suffix is extraneous and not present in the source text.
About %1
```

```
        <source>Change Passphrase…</source>
        <translation>修改密码(C)</translation>
    
YES, The translation uses a Chinese character '密码' (mì mǎ) which means password or passcode, but it should be '口令' (kǒu lìng) or '通行码' (tōng xíng mǎ) which means passphrase. Also, the English word "Passphrase" should be in English. The correct translation should be "Change Passphrase(C)".

NO
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES, The translation is problematic. The Cantonese translation "卸载钱包" means "uninstall wallet", which is not the same as "close wallet". The correct translation for "close wallet" in Cantonese is "关闭钱包".

NO
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES - The translation means "Turn off network logging" which is the opposite of the source text "Enable network activity".
Correct translation: 啟用網路活動
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES, The translation is incorrect. "Copy amount" in the context of Bitcoin should be translated to "复制金额" or "复制数额". The provided translation "复制和数量" means "copy and quantity".
NO, NO
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES, The translation is problematic. The Cantonese translation "卸载钱包" means "uninstall wallet", which is not the same as "close wallet". The correct translation for "close wallet" in Cantonese is "关闭钱包".

NO
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
YES: The translation is missing the final portion of the source text, specifically "when %4 initially launched.".

Correct translation: 當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)，在%4剛推出時。
```

```
        <source>Spend unconfirmed change</source>
        <translation>动用尚未确认的找零资金(S)</translation>
    
YES, The translation uses a character "(S)" at the end of the sentence which is not present in the source text. The intended meaning can be conveyed without it.
动用未确认的找零
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES, The translation is problematic because "watch-only addresses" is translated as "仅观察观察地址" which is redundant. The correct translation should be "仅观察地址".

Your current balance in watch-only addresses
您当前在仅观察地址中的余额
```

```
        <source>Save…</source>
        <translation>拯救...</translation>
    
YES - The translation is inaccurate. "Save" in this context refers to saving a file or data, not "saving a life" or "rescuing."
The correct translation should be "儲存..." or "保存...".
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>无法启动 bitcoin: 协议的“一键支付”处理程序</translation>
    
YES, The translation is problematic because it uses the English word "bitcoin" instead of translating it to Cantonese. The phrase "protocol's click-to-pay handler" also sounds a bit unnatural. A more natural translation would be:

无法启动 Bitcoin：点击支付处理程序
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES, The translation uses "其他人的" (others') which is too general. In the context of Bitcoin, it should refer to "peers" specifically. The correct translation would be "隐藏同行详细信息".
```

```
        <source>The transport layer version: %1</source>
        <translation>传输层版本: %1</translation>
    
UNK_LANG
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>來自這個節點上次成功驗證新交易進入內存池已經過的時間</translation>
    
YES - The translation is not accurate and misses a significant part of the source text. The source text says "Elapsed time since a novel transaction accepted into our mempool was received from this peer." The translation, "來自這個節點上次成功驗證新交易進入內存池已經過的時間", translates to "The time elapsed since the last successful validation of a new transaction entering the mempool from this peer." This implies the transaction has been validated, which is not stated in the source. The source only states that the transaction was "accepted into our mempool". Also, the word "novel" is not translated.

A more accurate translation would be: "呢個節點收到的新交易進入我哋嘅內存池所經過嘅時間。"
```

```
        <source>Outbound Manual: added using RPC %1 or %2/%3 configuration options</source>
        <extracomment>Explanatory text for an outbound peer connection that was established manually through one of several methods. The numbered arguments are stand-ins for the methods available to establish manual connections.</extracomment>
        <translation>出站手动: 加入使用RPC %1 或 %2/%3 配置选项</translation>
    
YES: The translation of "added using" to "加入使用" is inaccurate in this context. It should convey that the connection was established or configured using the specified options, not that it was "joined" using them.

出站手动: 使用RPC %1 或 %2/%3 配置选项添加
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
YES - The translation is inaccurate and does not convey the original meaning. The phrase "soliciting addresses" implies requesting addresses, whereas the translation "暫時 測試地址" translates to "temporarily test addresses".
Outbound 地址取得: 用於短暫，請求地址
```

```
        <source>1 hour</source>
        <translation>1 小时(H)</translation>
    
YES, The translation has an unnecessary character '(H)' which is not present in the source.
Correct translation: 1 小时
```

```
        <source>1 year</source>
        <translation>1 年(Y)</translation>
    
YES, The translation is problematic. The '(Y)' is unnecessary and not standard in Cantonese.
1 年
```

```
        <source>Ban for</source>
        <translation>禁止連線</translation>
    
YES. The translation is inaccurate and does not convey the intended meaning of "Ban for". In the context of Bitcoin, "ban for" would likely refer to an action taken against a user or entity. "禁止連線" (prohibit connection) is too specific and may not encompass the broader concept of a ban.

A more accurate translation would depend on the specific context of what the ban is *for*. However, a general translation for "Ban for" could be:

"禁止交易" (prohibit transaction) or "封鎖帳戶" (block account).

Without further context, a direct translation might be:

<source>Ban for</source>
<translation>封鎖原因</translation>
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES, The translation is incorrect. "Copy amount" in the context of Bitcoin should be translated to "复制金额" or "复制数额". The provided translation "复制和数量" means "copy and quantity".
NO, NO
```

```
        <source>Request payment to %1</source>
        <translation>付款給 %1 的要求</translation>
    
YES, The translation is inaccurate. The Cantonese translation "付款給 %1 的要求" means "Request for payment to %1", which is the opposite of the original English meaning. The correct translation should be "要求付款給 %1".
NO, 要求付款給 %1
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES: The translation is missing the part "sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet." which should be translated to "簽名，例如使用離線%1錢包或與PSBT兼容的硬件錢包". The translation also incorrectly ends with "然後使用簽名。"

NO
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
YES, The translation is grammatically incorrect and unnatural in Cantonese. The phrase "地址給" at the end is awkward. The correct translation should be "將支付發送到的比特幣地址".

NO
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1 次/未確認</translation>
    
YES, The translation is problematic because it does not convey the correct meaning of "unconfirmed" in the context of Bitcoin. The provided translation "%1 次/未確認" literally translates to "%1 times/unconfirmed," which is nonsensical. In Bitcoin, "unconfirmed" means that a transaction has not yet been added to the blockchain. A more accurate translation would be "%1 次 / 待定".

%1 次 / 待定
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES, The translation is incorrect. "Copy amount" in the context of Bitcoin should be translated to "复制金额" or "复制数额". The provided translation "复制和数量" means "copy and quantity".
NO, NO
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
YES: The formatting specifiers %s are not correctly transferred. There is also a stray newline.
錯誤：轉存檔案識別記錄不正確。獲得 "%s"，預期 "%s"。
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES - The translation is grammatically incorrect and awkward. The phrase "提供多數TOR路由綁定位址" should be "提供了多個 Tor 綁定位址". Also, "對自動建立的Tor服務用%s" should be "將使用 %s 為自動創建的 Tor onion 服務".

More than one onion bind address is provided. Using %s for the automatically created Tor onion service. -> 提供了多個 Tor 綁定位址。將使用 %s 為自動創建的 Tor onion 服務。
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>這是您支付的最高交易手續費（除了正常手續費外），優先於避免部分花費而不是定期選取幣。</translation>
    
YES - The translation for "regular coin selection" is incorrect. It should be "regular coin selection".
NO
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>找零低于当前粉尘阈值时会被舍弃，并计入手续费，这些交易手续费就是在这种情况下产生的。</translation>
    
YES, The translation is inaccurate and misleading. The original English states that the transaction fee can be discarded IF the change is smaller than dust. The translation states that if the change is smaller than dust, it will be discarded and added to the transaction fee, and these transaction fees are generated in this situation. This completely flips the meaning. The original text is also poorly phrased and could be interpreted differently. A better translation would be:

<translation>若找零低于粉尘数额，可免除此交易手续费。</translation>
```

```
        <source>Error loading %s: Private keys can only be disabled during creation</source>
        <translation>載入 %s 時發生錯誤: 只有在造新錢包時能夠指定不允許私鑰</translation>
    
YES, The translation contains a mistranslation. The original English states that private keys can only be disabled during creation. The Cantonese translation implies that private keys cannot be disabled at all, which is an incorrect interpretation.

Correct translation: 載入 %s 時發生錯誤：私鑰僅可在創建時停用
NO
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
YES: The translation incorrectly positions the format specifiers. The computed value should precede the expected value, as indicated by the English source text.

Correct translation: 錯誤：轉存檔案的校驗和不匹配。計算得出%s，預期%s
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES, The translation is inaccurate and the format specifier is misplaced. The Chinese characters are also placed incorrectly.
%s 移除交易失败
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES: The translation incorrectly states "maximum fee rate" instead of "minimum fee rate".
The correct translation is: 手续费率 (%s) 低于最小手续费率设置 (%s)
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s'</source>
        <translation>%s=&lt;amount&gt;: '%s' 中指定了非法的金额</translation>
    
YES - The translation is grammatically incorrect and word order is unnatural in Cantonese.

Correct translation: %s=&lt;amount&gt;: '%s' 提供的金额无效
```

```
        <source>Not found pre-selected input %s</source>
        <translation>找不到预先选择输入%s</translation>
    
YES - The provided translation contains extraneous characters. The correct translation is: 找不到预先选择的输入%s
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES - The translation has a grammatical error: "不不可" means "not not". The correct translation should be "交易金额不可为负数" or "交易金额不能是负数".

交易金额不可为负数
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES, The translation uses "零輸出項" (zero output item) which is not the correct term for "output index". The correct term for "output index" in the context of Bitcoin transactions is "輸出索引".

NO
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES, The translation has an erroneous format specifier. The source contains "%s" which is correctly translated to "%s" in Chinese, but the translation wrongly includes a "1" before the format specifier.
钱包文件创建失败：%s
```
</details>
