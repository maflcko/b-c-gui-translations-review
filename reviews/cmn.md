# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>cmn</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bcmn%5D%20low%20quality)


```
        <source>Delete</source>
        <translation>刪除 D</translation>
    
YES  
The translation contains an extraneous character "D" which does not belong. The correct simplified Chinese translation for "Delete" is "删除" or traditional Chinese "刪除" without any trailing letters.  

Correct translation:  
<translation>刪除</translation>
```

```
        <source>%1 and %2</source>
        <translation>%1又 %2</translation>
    
YES  
There is a spacing issue around the conjunction. The correct translation should not have extra spaces between %1 and %2 and the character '又' when used as "and" in Chinese. Also, the character "又" here is acceptable but less common as a simple "and" connector between two items; "和" or "与" is more common. However, if "又" is intended, spacing is important.

Correct translation:  
%1又%2
```

```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
YES  
The English phrase "Sending addresses" refers to addresses used for sending Bitcoin, not "付款地址(S)" which means "payment addresses" with an added "(S)" that is unusual and unnecessary in Chinese. Also, the English term is plural "addresses," so the translation should reflect that clearly without extraneous characters.

Correct translation:  
发送地址
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES  
The translation "卸载钱包" means "uninstall wallet," which is incorrect. The correct translation for "Close wallet" should be "关闭钱包."
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES  
The translation "關閉網路紀錄" means "Turn off network logging," which is opposite in meaning to the source text "Enable network activity."  

Correct translation:  
啟用網路活動
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES  
The translation "复制和数量" means "copy and amount," which incorrectly adds the conjunction "and" (和) that is not present in the source. The correct translation should be concise and directly reflect "Copy amount" without adding extra words.

Correct translation:  
复制金额
```

```
        <source>Create wallet failed</source>
        <translation>創建錢包失敗&lt;br&gt;</translation>
    
YES
The translation contains an unnecessary HTML line break tag "&lt;br&gt;" which is not present in the source and causes formatting issues. Also, the translation is accurate but the stray tag should be removed.

Correct translation:
創建錢包失敗
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES  
The translation "卸载钱包" means "uninstall wallet," which is incorrect. The correct translation for "Close wallet" should be "关闭钱包."
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>地址“%1”為已登記存在“%2”的地址，因此無法新增為發送地址。</translation>
    
YES
The translation is somewhat ambiguous and less clear than the source. It implies "address '%1' is already registered as '%2's address," which could confuse the roles of receiving and sending addresses. The original specifies that "%1" already exists as a receiving address with label "%2," so it cannot be added as a sending address.

A clearer and more accurate translation would be:
地址“%1”已作为带标签“%2”的接收地址存在，因此无法添加为发送地址。
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
YES  
The translation is mostly accurate but contains a typo and formatting issues:  
- "處裡" should be "處理" (correct character for "process").  
- Missing explanation of "%4 initially launched" explicitly; it implicitly says "%3年", which is the year, so it's acceptable, but could be clearer.  
- The comma before "並" is unnecessary in Chinese here.  
- Space needed before and after parentheses, or ideally no space inside parentheses (as is usual in Chinese typesetting, no spaces are needed).  
- The original has "%2 GB" (with a space), but the translation shows "%2GB" (no space), which is acceptable in Chinese typesetting (usually no space between number and unit), so this is fine.  

A more natural and corrected version:  
當你點擊「確認」後，%1會開始下載並處理自%4最初啟動時，%3內最早的交易，完整的%4區塊鏈（大小：%2 GB）。

Alternatively, if you want to maintain a closer structure:  
當你點擊「確認」後，%1會開始下載並處理完整的%4區塊鏈（大小：%2 GB），該區塊鏈自%4最初啟動時的%3年最早的交易開始。

---

Corrected translation:  
當你點擊「確認」後，%1會開始下載並處理完整的%4區塊鏈（大小：%2 GB），該區塊鏈自%4最初啟動時的%3年最早的交易開始。
```

```
        <source>Start %1 on system login</source>
        <translation>系统登入时启动 %1 (S)</translation>
    
YES  
The translation introduces extra content "(S)" which does not exist in the source text. This is unnecessary and not correct. Also, the phrase "系统登入时启动 %1" is understandable but "系统登录时启动 %1" is more standard for "login" in Simplified Chinese (cmn).  

Correct translation:  
系统登录时启动 %1
```

```
        <source>Prune block storage to</source>
        <translation>将区块存储修剪至(B)</translation>
    
YES
The English source "Prune block storage to" indicates an incomplete phrase that likely will be followed by a size or similar parameter, so the translation should not add extraneous characters. The translated text "将区块存储修剪至(B)" includes an unexplained "(B)" which is not present in the source and could confuse users. Also, there is no trailing space after "至" to allow a parameter, which may cause formatting issues.

Correct translation:
将区块存储修剪至
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>警告:还原此设置需要重新下载整个区块链。</translation>
    
YES
The source sentence is a neutral statement about reverting the setting requiring re-downloading the entire blockchain. The translation adds "警告:" ("Warning:"), which introduces a tone of alert not present in the source. This is an unnecessary addition and changes the nuance.

Correct translation:
还原此设置需要重新下载整个区块链。
```

```
        <source>Spend unconfirmed change</source>
        <translation>动用尚未确认的找零资金(S)</translation>
    
YES  
The translation adds "(S)" at the end, which is not present in the source text and appears unnecessary or erroneous. The phrase "Spend unconfirmed change" should be translated simply and directly without additional characters or shorthand.  

Correct translation:  
动用尚未确认的找零资金
```

```
        <source>External signer script path</source>
        <translation>外部签名器脚本路径(E)</translation>
    
YES  
The translation adds an unnecessary "(E)" at the end, which does not exist in the source text and may confuse users. The correct translation should directly correspond to "External signer script path" without extra characters.

Correct translation:  
外部签名器脚本路径
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES
The translation contains a duplicated word "观察" ("observe/watch"), making it awkward and redundant. A better translation would be:

您的当前仅观察地址余额
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>仅观察地址中尚未成熟的挖矿收入余额:</translation>
    
YES  
The translation includes an unnecessary colon (:) at the end which is not present in the source text. Also, "观察地址" is less commonly used for "watch-only addresses" compared to the standard term "仅观看地址" or "仅观察地址" depending on convention, but "仅观察地址" is acceptable. The translation is otherwise accurate. Removing the colon aligns exactly with the source.

Correct translation:  
仅观察地址中尚未成熟的挖矿收入余额
```

```
        <source>Save…</source>
        <translation>拯救...</translation>
    
YES  
The Chinese translation "拯救..." means "Save" in the sense of "rescue," which is incorrect in this context of "Save…" (as in saving a file or data). The correct translation should be "保存…" which correctly conveys the meaning of saving a file or data. Also note that the source uses an ellipsis character (U+2026) "…", while the translation uses three periods "...". It is better to use the same ellipsis character.

Correct translation:  
保存…
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES  
The translation "隐藏其他人的详细信息" means "Hide other people's detailed information," which is not an accurate or natural translation of "Hide Peers Detail." Here, "Peers" likely refers to network peers (nodes), not "other people." A better translation would be:  
隐藏节点详情
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>來自這個節點上次成功驗證新交易進入內存池已經過的時間</translation>
    
YES  
The translation is somewhat unclear and literally translated, which may cause confusion. The original English states "Elapsed time since a novel transaction accepted into our mempool was received from this peer," meaning the time elapsed since this peer sent us a new transaction that we accepted into our mempool. However, the translation "來自這個節點上次成功驗證新交易進入內存池已經過的時間" literally means "The elapsed time since this node last successfully verified a new transaction entering the mempool," which implies the node did the verifying, not that the transaction was received from the peer.

A clearer and more accurate translation would be:  
"自從從此節點接收到一筆新交易並被接受進入我們的內存池後經過的時間"
```

```
        <source>Clear console</source>
        <translation>清主控台</translation>
    
YES  
The translation "清主控台" is unnatural and not standard for "Clear console" in Chinese (Mandarin). A more accurate and commonly used translation would be "清除控制台" or simply "清空控制台".  

Correct translation:  
清除控制台
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
YES  
The translation is somewhat inaccurate and unnatural. The phrase "用於短暫，暫時 測試地址" is awkward and "測試地址" (test address) changes the meaning from "for soliciting addresses" (i.e., requesting addresses) to testing addresses, which is incorrect.

A better translation would be:  
"Outbound 地址获取：短暂的，用于请求地址"  

This keeps "Outbound 地址获取" consistent, replaces "取得" with the more standard term "获取," and correctly translates "for soliciting addresses" as "用于请求地址." Also, spacing is fixed (no extra spaces).
```

```
        <source>Ban for</source>
        <translation>禁止連線</translation>
    
YES  
The English phrase "Ban for" is incomplete on its own and typically expects a duration or reason to follow, e.g., "Ban for 24 hours." The provided translation "禁止連線" means "ban connection" or "prohibit connection," which is more of a general statement rather than a phrase expecting additional information. Also, the original phrase "Ban for" implies a prefix before some detail, while the translation is a standalone statement.

A more literal and context-appropriate translation for "Ban for" (as in "Ban for [duration/reason]") would be:  
禁止时间： or 禁止，持续  

If the UI appends additional text after "Ban for," the translation should reflect that prefix nature, e.g.:  
禁止时间：  

Correct translation example:  
禁止时间：
```

```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>要求付款的金額，可以不填。不確定金額時可以留白或是填零。</translation>
    
YES  
The translation is mostly correct but uses Traditional Chinese characters (e.g., "金額", "不確定", "留白") that correspond to zh_TW rather than Simplified Chinese (zh_CN), which is the usual form for 'cmn' (Mandarin Chinese, commonly zh_CN). Additionally, "要求付款的金額" ("the amount of payment requested") is slightly less literal than "An optional amount to request." A more direct translation would be:

"可选的请求金额。留空或填写零以不请求特定金额。"

This uses Simplified characters and is closer in meaning. Also, the punctuation should be full-width Chinese punctuation for consistency.

Correct translation:  
可选的请求金额。留空或填写零以不请求特定金额。
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES  
The translation "复制和数量" means "copy and amount," which incorrectly adds the conjunction "and" (和) that is not present in the source. The correct translation should be concise and directly reflect "Copy amount" without adding extra words.

Correct translation:  
复制金额
```

```
        <source>Copy Address</source>
        <translation>複製 地址</translation>
    
YES
The translation contains a whitespace formatting issue. In Chinese, "复制地址" should be written without a space between the two words.

Correct translation:
复制地址
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES  
The translation is incomplete and partially ungrammatical. The original English states users can save or copy the PSBT, then sign it using an offline %1 wallet or a PSBT-compatible hardware wallet. The Chinese translation ends abruptly after "然後使用簽名" ("then use signature"), missing the connection to "offline %1 wallet or PSBT-compatible hardware wallet."

Correct translation:  
請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用例如離線%1錢包或與PSBT相容的硬體錢包進行簽名。
```

```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>没有打上BIP-125手续费追加的标记。</translation>
    
YES  
The translation is somewhat understandable but not entirely accurate or natural. "没有打上BIP-125手续费追加的标记" literally means "Did not mark the BIP-125 fee bump," which is a bit informal and does not clearly communicate the concept of "Not signalling Replace-By-Fee, BIP-125." The original phrase means that the transaction is not signalling the Replace-By-Fee (RBF) protocol defined in BIP-125.

A more accurate and natural translation would be:  
“不支持 Replace-By-Fee（BIP-125）的信号。”  
or  
“未发出 Replace-By-Fee（BIP-125）信号。”

These translations clearly and formally convey that the Replace-By-Fee signal (BIP-125) is not being signalled.

Correct translation:  
“不支持 Replace-By-Fee（BIP-125）的信号。”
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
YES  
The Chinese translation is awkward and ungrammatical. The phrase "將支付發送到的比特幣地址給" is confusing and does not clearly convey the meaning of the source sentence. A better translation would be:  
"用於接收付款的比特幣地址"  
or  
"用於發送付款的比特幣地址" (depending on whether "send the payment to" means the address that will receive the payment).  

Since the source is "The Bitcoin address to send the payment to," the meaning is the address where the payment is sent (the recipient address). Therefore, the correct translation should be:  
"用於接收付款的比特幣地址"
```

```
        <source>Subtract fee from amount</source>
        <translation>從付款金額減去手續費(U)</translation>
    
YES  
The translation includes an extraneous "(U)" at the end, which is not present in the source and seems unnecessary or a leftover note. Also, the translation "從付款金額減去手續費" literally means "Subtract fee from the payment amount," which changes the wording slightly from "amount" to "payment amount." The more accurate and commonly used translation in Bitcoin context would be "從金額中扣除手續費" or "從金額減去手續費," which aligns better with "Subtract fee from amount."

Correct translation:  
從金額中扣除手續費
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES  
The translation "复制和数量" means "copy and amount," which incorrectly adds the conjunction "and" (和) that is not present in the source. The correct translation should be concise and directly reflect "Copy amount" without adding extra words.

Correct translation:  
复制金额
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
YES
The translation has formatting and spacing issues: there is an unnecessary line break before "錯誤", and the two %s placeholders are separated onto different lines without quotes as in the source. Also, the Chinese translation lacks the quotation marks around the %s placeholders as in the source, which affects clarity.

Correct translation:
錯誤：轉存檔案識別記錄不正確。獲得「%s」，預期「%s」。
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES  
The translation is incomplete and somewhat unclear. It omits some parts of the original sentence and is missing a verb and logical connectors, making it less natural and potentially confusing. Also, there is extra spacing after the first period, and "TOR" should be consistently capitalized as "Tor" to match standard usage. The phrase "%s" is correctly preserved.

A better translation would be:  
"提供了多个洋葱绑定地址。自动创建的Tor洋葱服务将使用 %s。"
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>這是您支付的最高交易手續費（除了正常手續費外），優先於避免部分花費而不是定期選取幣。</translation>
    
YES  
The translation is somewhat unclear and does not accurately convey the original meaning. The phrase "to prioritize partial spend avoidance over regular coin selection" is translated as "優先於避免部分花費而不是定期選取幣," which is ambiguous and may confuse readers.

A better translation would be:  
這是您支付的最高交易手續費（在正常手續費之外），用以優先避免部分花費，而非使用常規幣選擇。
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>找零低于当前粉尘阈值时会被舍弃，并计入手续费，这些交易手续费就是在这种情况下产生的。</translation>
    
YES  
The translation adds information not present in the source and changes the meaning. The source states: "This is the transaction fee you may discard if change is smaller than dust at this level," meaning the transaction fee can be discarded if the change is dust. The translation says that the change is discarded and counted as a fee, and that these fees arise in such cases, which is more explanatory and partially inaccurate as it implies all such fees are generated this way.

Correct translation:  
当找零小于当前的“粉尘”阈值时，您可以将其丢弃，这就是交易手续费。
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>不支持的类别限定日志等级 %1$s=%2$s 。 预期参数 %1$s=&lt;category&gt;:&lt;loglevel&gt;。 有效的类别: %3$s 。有效的日志等级: %4$s 。</translation>
    
YES
There are spacing issues around the punctuation marks (extra spaces before or missing spaces after full stops and colons), which is inconsistent with standard Chinese punctuation formatting. Also, the translation is accurate but the spacing needs correction.

Correct translation:
不支持的类别限定日志等级 %1$s=%2$s。预期参数 %1$s=&lt;category&gt;:&lt;loglevel&gt。有效的类别: %3$s。有效的日志等级: %4$s。
```

```
        <source>Error loading %s: Private keys can only be disabled during creation</source>
        <translation>載入 %s 時發生錯誤: 只有在造新錢包時能夠指定不允許私鑰</translation>
    
YES  
The translation mixes Traditional Chinese characters and phrasing that may not fully match the original meaning. The phrase "只有在造新錢包時能夠指定不允許私鑰" is a bit verbose and somewhat unclear. It should emphasize that private keys can only be disabled during creation (i.e., when creating a wallet), not that only at that time can private keys be disallowed as an option.

A clearer and more natural translation would be:  
載入 %s 時發生錯誤：私鑰只能在創建時被禁用
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
YES
The translation is incomplete and does not accurately convey the full meaning of the source sentence. It is missing the part about "expected %s" and the format specifiers are not correctly integrated. 

Correct translation:
錯誤：轉存檔案的校驗和不匹配。計算值為 %s，預期值為 %s
```

```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
YES
The translation has a typo in the type name "unit32_t" which should be "uint32_t" as in the source. The correct translation is:  
错误：无法把版本号%u作为uint32_t解析
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES
The placement of the format specifier %s is incorrect and the sentence structure is awkward. The %s should immediately follow "钱包" to indicate which wallet, and "写入钱包的磁盘" makes little sense—it's the data written to disk for the wallet, not the wallet's disk. A better translation is:

错误：无法将数据写入钱包 %s 的磁盘。
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES  
The translation has an incorrect word order and misplaced colon. The source phrase "Failure removing transaction: %s" places the transaction identifier after the colon, while the translation places "%s" at the start and then "删除交易时失败" (failure when removing transaction), but the colon is at the end with a trailing space. This is unnatural and confusing in Chinese. The correct translation should keep the colon immediately after the phrase and then place the %s in the equivalent position.

Correct translation:  
删除交易失败：%s
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES  
The translation incorrectly states "最大手续费率设置" (maximum fee rate setting), while the source says "minimum fee rate setting". The correct translation should reflect "minimum" (最小) instead of "maximum" (最大).  

Correct translation:  
手续费率 (%s) 低于最小手续费率设置 (%s)
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s'</source>
        <translation>%s=&lt;amount&gt;: '%s' 中指定了非法的金额</translation>
    
YES  
The translation omits the "Invalid amount for" portion from the source sentence and instead phrases it as "'%s' specifies an illegal amount in %s=<amount>", which slightly changes the structure and clarity. For accuracy and clarity aligned with the source, it is better to maintain the original structure indicating "Invalid amount for %s=<amount>: '%s'".

Correct translation:  
%s=&lt;amount&gt; 的金额无效：'%s'
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES  
The translation contains a double negation with "不不可为负数", which means "must not not be negative", causing confusion and inaccuracy. The correct translation should avoid double negatives.

Correct translation:  
交易金额不得为负数
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES  
The translation "交易尋找零輸出項超出範圍" is inaccurate and somewhat unclear. The phrase "尋找" means "searching for," which does not correspond to "change output index" in the source. The correct meaning is about the "change output index" in a transaction being out of range, not about searching or "zero outputs."

Correct translation:  
交易找零输出索引超出范围
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES  
There is an erroneous '1' before the format specifier %s in the translation, which should not be there.

Correct translation:  
钱包文件创建失败：%s
```
</details>
