# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>yue</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Byue%5D%20low%20quality)


```
        <source>New</source>
        <translation>新增 N</translation>
    
YES  
The translation adds an extraneous "N" after "新增," which is not present in the source and is unnecessary. The word "新增" alone correctly translates "New" in this context.

Correct translation:  
新增
```

```
        <source>Delete</source>
        <translation>刪除 D</translation>
    
YES
The translation contains an extraneous "D" which is not part of the original English text and appears to be an error or typo.

Correct translation:
刪除
```

```
        <source>Passphrase change failed</source>
        <translation>修改密码失败</translation>
    
YES  
The translation "修改密码失败" is in Simplified Chinese, not in Cantonese (yue). Additionally, it translates to "Password change failed," while the source refers to "Passphrase change failed." In Bitcoin context, "passphrase" is more specific and usually not just "password." A more accurate Cantonese (written in traditional characters) translation would be:

密碼短語更改失敗
```

```
        <source>Runaway exception</source>
        <translation>未捕获的异常</translation>
    
YES  
The translation is in Simplified Chinese ("未捕获的异常") rather than Cantonese (Yue). It means "uncaught exception" instead of "runaway exception". A more accurate Cantonese translation for "Runaway exception" could be:  
「失控嘅異常」
```

```
        <source>%1 MB</source>
        <translation>%1 MB (百萬位元組)</translation>
    
YES  
The addition "(百萬位元組)" is unnecessary and was not present in the source. It adds extra explanatory text that changes the format of the translation. Since "%1 MB" is a standard unit expression and the source only includes "%1 MB", the translation should match exactly without additional parentheses or explanations.

Correct translation:  
%1 MB
```

```
        <source>About %1</source>
        <translation>关于 %1 (A)</translation>
    
YES
The translation mixes simplified Chinese "关于" instead of using Cantonese (yue) language, which should use traditional characters and more natural Cantonese phrasing. Also, the added " (A)" is unnecessary and was not present in the source.

Correct translation:
關於 %1
```

```
        <source>Change Passphrase…</source>
        <translation>修改密码(C)</translation>
    
YES
The translation "修改密码(C)" means "Change Password (C)" in Mandarin rather than Cantonese (yue), and it translates "Passphrase" as "密码" which usually means "password" in a general sense, not specifically a passphrase. Also, the added "(C)" is not present in the source and appears to be out of context.

A better Cantonese translation for "Change Passphrase…" would be:
更改通行碼…
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES  
The translation "卸载钱包" means "uninstall wallet," which is incorrect for "Close wallet." The correct translation should reflect the action of closing or shutting the wallet, not uninstalling it.

Correct translation:  
"關閉錢包"
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES
The translation "關閉網路紀錄" means "Disable network logging," which is opposite to the source text "Enable network activity." 

Correct translation:  
啟用網絡活動
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation "复制和数量" means "copy and amount," which adds an incorrect conjunction "和" (and) that is not present in the original phrase "Copy amount." The correct translation should be concise and reflect only the command to copy the amount.

Correct translation:
复制数量
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES  
The translation "卸载钱包" means "uninstall wallet," which is incorrect for "Close wallet." The correct translation should reflect the action of closing or shutting the wallet, not uninstalling it.

Correct translation:  
"關閉錢包"
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
YES  
The translation is mostly understandable but contains minor issues in fluency and formatting:

1. "點擊「確認」" is acceptable but "點擊「OK」" would be a more accurate match of "click OK".  
2. The comma after "下載" is unnecessary in Cantonese and breaks the flow.  
3. The phrase "並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)" is awkward. The English says the download and processing start from the earliest transactions in %3 (probably a date/time), but the translation reads like "start from the earliest transactions in the year %3" - it would be better to separate the notions properly.  
4. There's a spacing issue: no space before the open parenthesis, and no space after the colon inside the parentheses. In Cantonese it is common to not add unnecessary spaces, but in English source and in typical translations the colon and the number GB should have a space after colon or be consistent with original.

A better translation could be:

當你點擊「OK」，%1會開始下載及處理完整嘅%4區塊鏈（大小：%2 GB），由%4首次啟動時嘅最早交易（%3）開始。

This preserves the intended meaning while clarifying the order and improving naturalness. Note also the use of full-width parentheses and spacing that is typical in Chinese text.

Final corrected translation:  
當你點擊「OK」，%1會開始下載及處理完整嘅%4區塊鏈（大小：%2 GB），由%4首次啟動時嘅最早交易（%3）開始。
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>与%1兼容的脚本文件路径（例如 C:\Downloads\hwi.exe 或者 /Users/you/Downloads/hwi.py ）。注意：恶意软件可以偷币！</translation>
    
YES  
The translation is in Simplified Chinese, not in Yue (Cantonese). Additionally, in the translation there is an unnecessary space before the closing parenthesis. The format specifier %1 is handled correctly. The style is simplified Chinese, while yue should be a Cantonese phrasing which differs significantly.  

Correct translation in Yue (Cantonese) could be:  
與 %1 兼容嘅腳本文件全路徑（例如 C:\Downloads\hwi.exe 或 /Users/you/Downloads/hwi.py）。小心：惡意軟件會偷你嘅錢！
```

```
        <source>Spend unconfirmed change</source>
        <translation>动用尚未确认的找零资金(S)</translation>
    
YES  
The translation mixes simplified Chinese characters with a parenthetical "(S)", which appears to be an artifact or misplaced. The original English phrase is short and direct: "Spend unconfirmed change." The translation should be in Cantonese (Yue), using appropriate characters and phrasing without extraneous symbols. Also, the simplified Chinese character "动用" is more common in Mandarin; the Cantonese equivalent would better use traditional characters and phrasing.

Correct translation:  
花未確認嘅找續
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES  
The translation is repetitive and slightly awkward ("仅观察观察地址", meaning "watch-only watch addresses"). Also, it uses formal Mandarin ("您当前") rather than Yue (Cantonese) phrasing. A more natural and accurate Yue translation for "Your current balance in watch-only addresses" would be:

您喺只可觀察嘅地址入面嘅現有餘額
```

```
        <source>Save…</source>
        <translation>拯救...</translation>
    
YES
The translation is incorrect. "Save…" in the context of a computer interface usually means "save a file" or "save changes," and should be translated as "儲存…" in Cantonese (yue), not "拯救...," which means "to rescue" or "to save someone" literally.

Correct translation: 儲存…
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>无法启动 bitcoin: 协议的“一键支付”处理程序</translation>
    
YES  
The translation is in Simplified Chinese, not Cantonese (yue). Also, the original English uses the phrase "click-to-pay handler" which is translated as "协议的‘一键支付’处理程序" meaning "protocol's 'one-click payment' handler," which adds but changes the meaning slightly. The original does not mention "protocol" and is more limited. Additionally, the original says "Cannot start bitcoin: click-to-pay handler" suggesting an inability to start that handler, but the translation lacks the negative modal "cannot" in a proper Cantonese expression.

Correct translation in Cantonese (yue) could be:  
「無法啟動 bitcoin: click-to-pay 處理程序」  
or more colloquial:  
「無法啟動 bitcoin：click-to-pay 處理器」
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES
The translation is in Simplified Chinese ("隐藏其他人的详细信息"), not in Cantonese (yue). A proper Cantonese (yue) translation should be in traditional characters and reflect the phrasing typical to the language.

Correct translation:
隱藏節點詳情
```

```
        <source>The transport layer version: %1</source>
        <translation>传输层版本: %1</translation>
    
YES
The translation uses Simplified Chinese ("传输层版本: %1"), but the target language "yue" refers to Cantonese, which is typically written in Traditional Chinese characters and uses different phrasing.

Correct translation:
傳輸層版本：%1
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
YES
The translation is somewhat unclear and includes unnecessary words that might confuse the meaning. The original phrase refers to a short-lived outbound connection used specifically to request or solicit addresses. The translation "用於短暫，暫時 測試地址" translates to "used for short-lived, temporarily testing addresses," which deviates from the intended meaning.

A more accurate translation would be:
"Outbound 地址取得：短暫嘅，用嚟索取地址"

This preserves the idea of "short-lived" and "for soliciting addresses" appropriately in Cantonese.
```

```
        <source>1 hour</source>
        <translation>1 小时(H)</translation>
    
YES  
The translation uses "小时(H)" which is Simplified Chinese and includes an unnecessary "(H)". In Cantonese (yue), a more natural and appropriate translation for "1 hour" is "1 小時" without parentheses or additional letters. Also, it should use traditional characters as is customary in Cantonese.

Correct translation:  
1 小時
```

```
        <source>Ban for</source>
        <translation>禁止連線</translation>
    
YES  
The English source "Ban for" is typically followed by a duration (e.g., "Ban for 24 hours"), so the phrase should reflect this incomplete phrase. The translation "禁止連線" means "ban connection" or "block connection," which is a complete action and does not correspond to the incomplete phrase "Ban for."  
A better translation preserving the context and leaving the phrase open for a duration could be:  
"封鎖 %1" or  
"封禁 %1"  
where %1 would be the duration appended later. If the "%1" or similar format specifier is missing in the source, the phrase should remain incomplete similarly, e.g., "封鎖 " or "封禁 " (with a trailing space).  

Correct translation:  
"封鎖 "
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation "复制和数量" means "copy and amount," which adds an incorrect conjunction "和" (and) that is not present in the original phrase "Copy amount." The correct translation should be concise and reflect only the command to copy the amount.

Correct translation:
复制数量
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES
The translation is incomplete and awkward in phrasing. The original sentence explains that the user can save or copy the PSBT and then sign it with an offline %1 wallet or a PSBT-compatible hardware wallet. The current translation ends abruptly after "使用簽名" (using signature), missing the clear connection to "e.g. an offline %1 wallet" and "or a PSBT-compatible hardware wallet."

Correct translation:
請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用例如離線的%1錢包或相容PSBT的硬體錢包來簽署。
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
YES  
The translation "將支付發送到的比特幣地址給" is awkward and ungrammatical in Cantonese. It literally translates back to something like "the Bitcoin address to which the payment is sent" but the phrasing is unnatural and incomplete.

A more natural and accurate Cantonese translation would be:  
"發送支付嘅比特幣地址"  
or more explicitly:  
"用嚟發送支付嘅比特幣地址"  

This conveys clearly that it is the Bitcoin address used to send the payment to.
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1 次/未確認</translation>
    
YES
The translation "%1 次/未確認" uses "次" which usually means "times" or "occurrences" and is not appropriate for representing a fraction or ratio in this context (e.g., "confirmed/unconfirmed" count).

Correct translation:
%1/未確認
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation "复制和数量" means "copy and amount," which adds an incorrect conjunction "和" (and) that is not present in the original phrase "Copy amount." The correct translation should be concise and reflect only the command to copy the amount.

Correct translation:
复制数量
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
YES
The translation has formatting and spacing issues. The placeholders %s should remain adjacent to the text without line breaks or extra spaces. Also, the punctuation and spacing in Chinese (Cantonese) should be consistent, and the placeholders should be in quotes as in the source.

Correct translation:
錯誤：轉存檔案識別記錄不正確。獲得「%s」，預期「%s」。
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES
The translation is missing some parts and has extra spacing issues. It should fully convey the original meaning and keep the format specifier in place without extra spaces. The phrase "More than one onion bind address is provided." should be translated more clearly, and "Using %s for the automatically created Tor onion service." should also be complete and natural.

Correct translation:
提供多於一個 Onion 綁定地址。自動建立嘅 Tor Onion 服務會用 %s。
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>這是您支付的最高交易手續費（除了正常手續費外），優先於避免部分花費而不是定期選取幣。</translation>
    
YES  
The translation is mostly understandable but contains minor inaccuracies and awkward phrasing. The phrase "partial spend avoidance over regular coin selection" is rendered somewhat unclearly as "優先於避免部分花費而不是定期選取幣," which could be interpreted as "prioritize avoiding partial spend instead of regular coin selection" but the wording "定期選取幣" (regular coin selection) is less idiomatic in Yue.

A clearer and more natural translation would be:  
這係你支付嘅最高交易手續費（除咗正常手續費之外），用嚟優先避免部分消費，而唔係普通揀選貨幣。

This better captures "prioritize partial spend avoidance over regular coin selection" in the correct context.
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>找零低于当前粉尘阈值时会被舍弃，并计入手续费，这些交易手续费就是在这种情况下产生的。</translation>
    
YES  
The provided translation is in Simplified Chinese, not in Cantonese (yue), and thus does not match the requested language code. Additionally, the translation expands on the meaning and changes the sentence structure, which might alter the nuance. The original English sentence is:

"This is the transaction fee you may discard if change is smaller than dust at this level"

A more direct and accurate Cantonese (yue) translation would be:  
"呢個係交易費，如果找零細過呢個層級嘅塵埃，可以拎走唔理佢。"
```

```
        <source>Error loading %s: Private keys can only be disabled during creation</source>
        <translation>載入 %s 時發生錯誤: 只有在造新錢包時能夠指定不允許私鑰</translation>
    
YES
The translation omits the explicit term "disable" and doesn't clearly convey that private keys can only be disabled during creation. A more accurate translation would be:

載入 %s 時發生錯誤：私鑰只可以喺造新錢包嗰陣先至可以禁用
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
YES  
The translation is incomplete and does not properly convey the full meaning of the source text. It also has formatting issues around the %s specifiers and lacks the "expected %s" part. The correct translation should preserve both computed and expected values clearly:

錯誤：轉存檔案的校驗和不匹配。計算值為 %s，預期為 %s
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES  
The translation has an incorrect word order and a missing space before the colon. Also, the placement of %s should match the source, which comes after the colon. The proper structure in Yue (Cantonese) would be closer to "删除交易失败: %s" or "移除交易失敗: %s" to align with the source meaning "Failure removing transaction: %s".  

Correct translation:  
移除交易失敗: %s
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES
The translation incorrectly renders "lower than the minimum fee rate setting (%s)" as "低于最大手续费率设置 (%s)", which means "lower than the maximum fee rate setting (%s)". It should say "低于最小手续费率设置 (%s)" to match the original meaning.

Correct translation:
手续费率 (%s) 低于最小手续费率设置 (%s)
```

```
        <source>Not found pre-selected input %s</source>
        <translation>找不到预先选择输入%s</translation>
    
YES  
The translation is entirely in Simplified Chinese ("找不到预先选择输入%s") rather than Cantonese (Yue), which typically uses traditional characters and distinct grammar and vocabulary. It also lacks appropriate spacing before the format specifier %s. A more accurate Yue translation in traditional characters and natural phrasing would be:  
"搵唔到預先揀定嘅輸入%s"
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES  
The translation contains a double negation ("不不可"), which is incorrect and unnatural in Yue (Cantonese) as well as in written Chinese. The original English sentence states that transaction amounts must not be negative, which should be translated without using double negation.

Correct translation:  
交易金额唔可以係负数
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES
The translation "交易尋找零輸出項超出範圍" inaccurately conveys the original meaning. The original phrase means "Transaction change output index out of range," referring to an index related to the change output in a Bitcoin transaction being outside the valid range. The word "尋找" means "to search" and "零輸出項" literally means "zero output item," which deviates from the intended technical meaning.

A more accurate translation in Yue (Cantonese) would be:
"交易嘅找零輸出索引超出範圍"

This keeps the technical terms clear:
- "交易" (transaction)
- "找零" (change, i.e., the change output)
- "輸出索引" (output index)
- "超出範圍" (out of range)
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES  
The translation contains an erroneous '1' before the format specifier '%s', which is incorrect and not present in the source. Also, the use of simplified Chinese (钱包文件创建失败) is not consistent with 'yue' (Yue Chinese/Cantonese), which typically uses traditional Chinese characters.

A more appropriate translation in 'yue' (Cantonese) with traditional characters would be:  
錢包檔案建立失敗：%s
```
</details>
