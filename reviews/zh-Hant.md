# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh-Hant</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh-Hant%5D%20low%20quality)


```
        <source>New</source>
        <translation>新增 N</translation>
    
YES, The translation of "New" to "新增 N" is incorrect. The letter "N" appears to be an artifact or error. The correct translation for "New" in the context of Bitcoin would be "新增" or "新的".
The correct translation is:
<translation>新增</translation>
```

```
        <source>Delete</source>
        <translation>刪除 D</translation>
    
YES, The format specifier "D" is not a valid format specifier in the target language and seems to be an unintended addition. The correct translation for "Delete" is 刪除.
YES: 刪除
```

```
        <source>Custom…</source>
        <translation>自定义...</translation>
    
YES, the translation is problematic because it uses simplified Chinese characters instead of traditional Chinese characters.
Correct translation: 自訂…
```

```
        <source>About %1</source>
        <translation>关于 %1 (A)</translation>
    
YES, The translation contains an extraneous character "(A)". The correct translation is "关于 %1".
Regarding %1
```

```
        <source>Send</source>
        <translation>发送(S)</translation>
    
YES, the translation is problematic because it includes an English letter "S" in parentheses, which is not a standard practice in Traditional Chinese and might be confusing to users. The "S" likely originates from an accelerator key indicated by the "(S)" in the source text, which should not be translated directly. A more appropriate translation would simply be the Chinese word for "Send".

NO
```

```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
YES
The translation is problematic as it adds an unnecessary "(S)" which is likely a misplaced formatting character or an accidental inclusion. It also translates "Sending addresses" as "付款地址(S)" which literally means "payment addresses (S)". While understandable, it's not the most natural or accurate translation for "sending addresses" in the context of Bitcoin transactions. A better translation would refer to the origin of the funds.

Correct translation: 發送地址
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES, The translation is problematic. "Close wallet" in the context of Bitcoin usually means to simply close the application or the wallet interface, not to uninstall it. The Chinese translation "卸载钱包" means "uninstall wallet", which is a much more drastic action and not equivalent to "close wallet".

NO
```

```
        <source>Hide</source>
        <translation>躲</translation>
    
YES
The translation is inaccurate and inappropriate for the context of Bitcoin. "躲" means "to hide" or "to dodge," which does not fit the intended meaning of "Hide" in a user interface element for Bitcoin-related software, where it likely refers to hiding something from view, like a transaction or an address.

A more appropriate translation would be "隱藏" (yǐncáng), which means "to hide" or "conceal" in a general sense and is commonly used in software interfaces.

<source>Hide</source>
<translation>隱藏</translation>
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES
The translation is inaccurate and conveys the opposite meaning of the source text. The source text "Enable network activity" means to turn on network activity, while the translation "關閉網路紀錄" means "Close network records."

Correct translation: 啟用網路活動
```

```
        <source>Coin Selection</source>
        <translation>手动选币</translation>
    
YES - The translation "手动选币" (Manual Coin Selection) is a valid translation for "Coin Selection", but the context provided states that this term often refers to the process of selecting unspent transaction outputs (UTXOs) to fund a Bitcoin transaction. "Coin Selection" in this context is a technical term. "手动选币" implies a manual intervention which might not be the case if the software automatically selects coins. A more neutral and accurate translation that encompasses both automatic and manual selection in the context of Bitcoin would be "选币" (Coin Selection).

Correct translation: 选币
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES, The translation is inaccurate. "Copy amount" means to copy the quantity or value. The current translation "复制和数量" translates to "Copy and quantity", which is not correct.
A more accurate translation would be "复制金额" or "複製金額" (if we want to be more specific about monetary value). Since the context is Bitcoin, it's likely referring to an amount of Bitcoin.

Corrected translation: 複製金額
```

```
        <source>Lock unspent</source>
        <translation>锁定未花费(O)</translation>
    
YES, The Chinese translation uses an extraneous character "(O)" at the end of the phrase. The correct translation should be "鎖定未花費".
```

```
        <source>Create wallet failed</source>
        <translation>創建錢包失敗&lt;br&gt;</translation>
    
YES, The translation contains an unnecessary HTML break tag `&lt;br&gt;`.
Correct translation: 創建錢包失敗
```

```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>迁移钱包 &lt;b&gt;%1&lt;/b&gt;...</translation>
    
YES, The translation uses simplified Chinese characters instead of traditional Chinese characters.
Migrating Wallet &lt;b&gt;%1&lt;/b&gt;… -> 遷移錢包 &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES, The translation is problematic. "Close wallet" in the context of Bitcoin usually means to simply close the application or the wallet interface, not to uninstall it. The Chinese translation "卸载钱包" means "uninstall wallet", which is a much more drastic action and not equivalent to "close wallet".

NO
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>启用修剪时，如果一个钱包被卸载太久，就必须重新同步整条区块链才能再次加载它。</translation>
    
YES, the translation is problematic as it mistranslates "closing the wallet" as "卸载" (uninstall/unload) instead of "關閉" (close). This fundamentally changes the meaning of the sentence in the context of Bitcoin wallets.

NO
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>地址“%1”為已登記存在“%2”的地址，因此無法新增為發送地址。</translation>
    
YES, The translation uses "為已登記存在" which is a bit redundant. A more concise and natural phrasing would be "已登記為" or simply "是". Also, the original English says "already exists as a receiving address", which implies a specific type of address (receiving). The translation implies that the address is registered in general, not specifically as a receiving address. The phrase "so cannot be added as a sending address" is also slightly awkward.

A better translation would be:
地址「%1」已登記為接收地址，標籤為「%2」，因此無法新增為發送地址。
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
YES - The translation is missing the word "process" and has a grammatical error. It also doesn't correctly translate the "full %4 block chain" part.

Correct translation: 當您點擊「確認」後，%1 將開始下載並處理完整的 %4 區塊鏈（%2 GB），從 %4 最初推出時，即 %3 年最早的交易開始。
```

```
        <source>Start %1 on system login</source>
        <translation>系统登入时启动 %1 (S)</translation>
    
YES - The translation is missing the space before the parenthesis. It should be: 系统登入时启动 %1 (S)
```

```
        <source>Prune block storage to</source>
        <translation>将区块存储修剪至(B)</translation>
    
YES, The translation is inaccurate and uses a misleading character. The term "prune" in the context of Bitcoin refers to removing unnecessary data from the blockchain to save space, not to "trim" or "cut" the storage itself in a way that the current translation implies. Also, the character "(B)" at the end is not part of the original English text and is therefore erroneous.

A more accurate translation would be:

将区块存储修剪至
將區塊儲存修剪至
```

```
        <source>This allows you or a third party tool to communicate with the node through command-line and JSON-RPC commands.</source>
        <extracomment>Tooltip text for Options window setting that enables the RPC server.</extracomment>
        <translation>这允许作为用户的你或第三方工具通过命令行和JSON-RPC命令行与节点通信。</translation>
    
YES - The translation incorrectly uses "命令行" (command-line) twice. The second instance should refer to JSON-RPC commands.
Correct translation: 这允许作为用户的你或第三方工具通过命令行和 JSON-RPC 命令与节点通信。
```

```
        <source>Subtract fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>默认从金额中减去交易手续费(F)</translation>
    
YES - The translation is problematic because it includes an unnecessary English character "(F)" at the end of the sentence, which is not present in the source text.

Correct translation: 默认从金额中减去交易手续费
```

```
        <source>Spend unconfirmed change</source>
        <translation>动用尚未确认的找零资金(S)</translation>
    
YES, the translation is problematic. The character 'S' at the end of the translation is extraneous and doesn't correspond to anything in the source text.

NO
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES
The translation is redundant, as "watch-only addresses" is translated as "僅觀察觀察地址" (jǐn guānchá guānchá dìzhǐ), which repeats the word "observe" (觀察).

A more accurate and concise translation would be:

您在僅觀察地址中的目前餘額
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>“概况”标签页已启用隐私模式。要明文显示数值，请在设置中取消勾选“不明文显示数值”。</translation>
    
YES - The translation is problematic because it incorrectly translates "Mask values" as "不明文显示数值" (do not show values clearly) instead of "明文显示数值" (show values clearly) when it should be the opposite.

The correct translation is:
“概况”标签页已启用隐私模式。要明文显示数值，请在设置中取消勾选“隐藏数值”。
```

```
        <source>Save…</source>
        <translation>拯救...</translation>
    
YES: The translation of "Save…" to "拯救..." is incorrect in this context. "拯救" means "to save" in the sense of rescuing or salvaging. In the context of Bitcoin, "Save…" would likely refer to saving a file, an address, or a setting. The correct translation for "Save…" in this context is "儲存…".
儲存…
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES, The translation is problematic because "其他人的" (others' people) does not accurately convey the meaning of "Peers" in the context of Bitcoin. "Peers" in this context refers to the nodes on the Bitcoin network that your node is connected to. A more accurate translation would be "節點" (nodes) or "對等節點" (peer nodes).

NO, The translation is problematic. The word "Peers" in the context of Bitcoin refers to the nodes on the Bitcoin network that your node is connected to. The translation "隐藏其他人的详细信息" (Hide others' people's details) is too general and does not accurately reflect the technical meaning.

Correct translation: 隐藏节点详情
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
YES - The translation contains erroneous content. The phrase "暫時 測試地址" (temporarily test addresses) does not accurately convey the meaning of "soliciting addresses" (asking for addresses).

Correct translation: Outbound 地址取得: 短暫，用於徵求地址
```

```
        <source>1 year</source>
        <translation>1 年(Y)</translation>
    
YES - The format specifier "(Y)" is unnecessary and potentially confusing for the target audience. The translation should simply be "1 年".
1 年
```

```
        <source>Ban for</source>
        <translation>禁止連線</translation>
    
YES, The translation is problematic. The phrase "Ban for" in the context of Bitcoin usually implies a reason for a ban, such as a banned IP address or a banned user. "禁止連線" translates to "Prohibit connection" or "Ban connection," which is too general and doesn't capture the nuance of "Ban for." A more accurate translation would be "禁止原因" which translates to "Reason for ban."

Correct translation: 禁止原因
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES, The translation is inaccurate. "Copy amount" means to copy the quantity or value. The current translation "复制和数量" translates to "Copy and quantity", which is not correct.
A more accurate translation would be "复制金额" or "複製金額" (if we want to be more specific about monetary value). Since the context is Bitcoin, it's likely referring to an amount of Bitcoin.

Corrected translation: 複製金額
```

```
        <source>Request payment to %1</source>
        <translation>付款給 %1 的要求</translation>
    
YES, The translation is a bit awkward. It literally translates to "Payment to %1's request" which doesn't sound natural in Chinese. A more idiomatic translation would be "要求付款給 %1".
要求付款給 %1
```

```
        <source>Send</source>
        <translation>发送(E)</translation>
    
YES
The translation is inaccurate and uses an incorrect character for the English word "Send".
Correct translation: 傳送(E)
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES, the translation incorrectly conveys that the PSBT itself is signed, rather than the PSBT being signed *with* a wallet. The phrase "然後使用簽名" is ambiguous and grammatically incorrect in this context. It should specify signing the PSBT *using* something.

NO
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
YES. The translation is grammatically incorrect and awkward. The phrase "地址給" is not standard Chinese.

A more natural and accurate translation would be:

將支付發送到的比特幣地址
```

```
        <source>Subtract fee from amount</source>
        <translation>從付款金額減去手續費(U)</translation>
    
YES, the translation contains an extraneous character "(U)" that is not present in the source text and does not contribute to the meaning.

The correct translation should be:
從付款金額減去手續費
```

```
        <source>Verify Message</source>
        <translation>验证消息签名(M)</translation>
    
YES, The translation is inaccurate and misleading. In the context of Bitcoin, "Verify Message" refers to verifying a signature of a message using a Bitcoin private key, not verifying a message signature. The "M" in the translation seems to be an arbitrary addition.

Correct translation: 驗證訊息
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1 次/未確認</translation>
    
YES, The translation is inaccurate and uses an incorrect character. The word "次" means "times" or "occurrences" and is not appropriate here. The context implies a number of confirmations, not a count of occurrences. The correct translation should use a character that signifies "confirmations".

NO
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES, The translation is inaccurate. "Copy amount" means to copy the quantity or value. The current translation "复制和数量" translates to "Copy and quantity", which is not correct.
A more accurate translation would be "复制金额" or "複製金額" (if we want to be more specific about monetary value). Since the context is Bitcoin, it's likely referring to an amount of Bitcoin.

Corrected translation: 複製金額
```

```
        <source>Increase transaction fee</source>
        <translation>增加矿工费(F)</translation>
    
YES, The translation uses "矿工费" which means "miner fee". While this is related to Bitcoin transactions, the source text "transaction fee" is more general and can also refer to other types of transaction fees. A more direct and accurate translation would be "交易費".

The format specifier "(F)" is not present in the source text. If it is meant to be a placeholder or an annotation, it should be included in the source. Assuming it's not intended, it should be removed.

NO
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
YES: The translation is missing the opening quotation mark for the first "%s" placeholder and the closing quotation mark for the second "%s" placeholder, which are present in the source text.

Correct translation: 錯誤：轉存檔案識別記錄不正確。獲得"%s"，預期"%s"。
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES: The translation contains an error. "路由綁定位址" means "routed bind address", but the original text specifies "onion bind address". The corrected translation should use "洋蔥綁定位址" for "onion bind address".

More than one onion bind address is provided. Using %s for the automatically created Tor onion service.
提供多於一個洋蔥綁定位址。 將使用 %s 作為自動建立的 Tor 洋蔥服務。
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>這是您支付的最高交易手續費（除了正常手續費外），優先於避免部分花費而不是定期選取幣。</translation>
    
YES - The translation of "prioritize partial spend avoidance over regular coin selection" is awkward and doesn't accurately convey the intended meaning. It seems to imply prioritizing avoidance of spending parts of coins rather than general coin selection. The correct meaning in the context of Bitcoin transactions is prioritizing avoiding creating dust outputs (small, unusable amounts of Bitcoin) by allowing a higher fee for more efficient coin selection.

Correct translation: 這是您支付的最高交易手續費（除了正常手續費外），用於優先生成避免產生最小化支付額（dust outputs）的需求，而非一般的幣選取。
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>找零低于当前粉尘阈值时会被舍弃，并计入手续费，这些交易手续费就是在这种情况下产生的。</translation>
    
YES, The translation is inaccurate and does not convey the original meaning. The original sentence explains that the transaction fee might be discarded if the change is smaller than a dust amount. The provided translation, however, suggests that the transaction fee is generated when the change is discarded due to being smaller than the dust threshold, which is a misinterpretation.

Correct translation: 如果找零小于此阈值的粉尘，则可以忽略此交易费用。
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>%s=&lt;amount&gt;: '%s' 中指定了非法的金额 (手续费必须至少达到最小转发费率(minrelay fee) %s 以避免交易卡着发不出去)</translation>
    
YES - The translation is missing a format specifier. The source text has '%s=&lt;amount&gt;' but the translation only has '%s=&lt;amount&gt;'. It should be '%s=&lt;amount&gt;'.
The corrected translation is: "%s=&lt;amount&gt;: '%s' 中指定了非法的金额 (手续费必须至少达到最小转发费率(minrelay fee) %s 以避免交易卡着发不出去)"
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>出站连接被限制为仅使用 Tor (-onlynet=onion)，但是未提供到达 Tor 网络的代理：没有提供 -proxy=, -onion= 或 -listenonion 参数</translation>
    
YES, The translation is problematic because it incorrectly translates the format specifiers. The source uses "-proxy", "-onion", and "-listenonion" as argument names, but the translation translates them as "-proxy=", "-onion=", and "-listenonion=".

Here's the corrected translation:
NO
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES: The Chinese translation of the source text is missing the "%s" format specifier, which is crucial for the correct functioning of the sentence.

Correct translation: 錯誤：無法將數據寫入錢包磁碟 %s。
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES - The word order is incorrect and the translation is missing the format specifier. The correct translation should be: "刪除交易失敗：%s"
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES, The translation incorrectly uses "maximum fee rate" (最大手续费率) instead of "minimum fee rate" (最低手续费率). The original English specifies that the provided fee rate is *lower than* the minimum, implying the minimum is the threshold.
Correct translation: 手续费率 (%s) 低于最低手续费率设置 (%s)
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>无效的 -onion 地址: '%s'</translation>
    
YES - The translation is missing the word "hostname" from the original English sentence.

Correct translation: 無效的 -onion 位址或主機名稱: '%s'
```

```
        <source>Not found pre-selected input %s</source>
        <translation>找不到预先选择输入%s</translation>
    
YES - The translation is missing a space between "选择" and "输入". It should be "找不到预先选择的输入%s".
NO
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES, the translation contains a grammatical error. The word "不不可" is redundant.
Transaction amounts must not be negative
交易金额不得为负数
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES, The translation of "change output index" as "尋找零輸出項" is inaccurate and misleading in the context of Bitcoin transactions. In Bitcoin, "change" refers to the leftover amount of Bitcoin that is returned to the sender after a transaction. The term "output index" refers to the position of an output within a transaction. A more accurate translation would be "找零輸出索引" or "找零輸出項索引".

NO. The provided translation is **NO**.

Explanation: The term "change" in the context of Bitcoin transactions refers to the "change" amount returned to the sender, not "finding zero output". "Output index" refers to the index of an output within a transaction. Therefore, "transaction change output index" should be translated to something that reflects the concept of the index of the change output.

Correct translation: 交易找零輸出索引超出範圍
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES, The format specifier %s has been incorrectly translated as 1%s.
Wallet file creation failed: %s
```
</details>
