# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh-Hant</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh-Hant%5D%20low%20quality)


```
        <source>New</source>
        <translation>新增 N</translation>
    
YES  
The translation includes an extraneous "N" which is not present in the source and seems incorrect. The English word "New" should be translated simply as "新增".  

Correct translation:  
新增
```

```
        <source>Delete</source>
        <translation>刪除 D</translation>
    
YES  
The translation contains an extraneous " D" character that is not present in the source text. It should simply be "刪除" without the trailing " D".  

Correct translation:  
刪除
```

```
        <source>Custom…</source>
        <translation>自定义...</translation>
    
YES  
The translation uses simplified Chinese characters "自定义" and ellipsis "..." which are not standard in traditional Chinese (zh-Hant) context. The correct traditional Chinese translation should use "自訂" for "custom" and use the proper Unicode ellipsis character "…" instead of three dots.

Correct translation:  
自訂…
```

```
        <source>About %1</source>
        <translation>关于 %1 (A)</translation>
    
YES  
The translation contains Simplified Chinese ("关于") instead of Traditional Chinese, which is expected for 'zh-Hant'. Also, the appended "(A)" is not present in the source and seems unnecessary or erroneous. The spacing before %1 should be consistent with Chinese punctuation style (no space before %1).

Correct translation:  
關於%1
```

```
        <source>Send</source>
        <translation>发送(S)</translation>
    
YES  
The translation mixes Simplified Chinese "发送" with a parenthetical "(S)", which is not a standard approach in Traditional Chinese interfaces. In Traditional Chinese, and especially in the context of Bitcoin software, the term "送出" is more commonly used for "Send". Also, the parenthesis (S) is usually not included in translations, unless it is a reference to a shortcut key, which is uncommon to show in this way in the translation string itself.

Correct translation:  
送出
```

```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
YES  
The translation "付款地址(S)" adds "(S)" unnecessarily, which is not present in the source and may confuse users. Also, "付款地址" specifically means "payment address," but "Sending addresses" in the Bitcoin context typically refers to addresses from which coins are sent, which can be translated as "發送地址" or simply "寄件地址" depending on the context.

Correct translation:  
發送地址
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES  
The translation "卸载钱包" means "uninstall wallet," which is not accurate for "Close wallet." The correct meaning should be about closing the wallet application or window, not uninstalling it. A better translation would be:  
關閉錢包
```

```
        <source>Hide</source>
        <translation>躲</translation>
    
YES  
The translation "躲" is incorrect and unnatural in this context. The English word "Hide" as a UI command typically means to conceal or make something invisible, and the proper translation in Traditional Chinese should be "隱藏" or "隱藏起來".  

Correct translation:  
隱藏
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES
The translation means "Disable network logging," which is not an accurate translation of "Enable network activity." The correct translation should be:

啟用網路活動
```

```
        <source>Coin Selection</source>
        <translation>手动选币</translation>
    
YES  
The translation "手动选币" means "manual coin selection," which adds the word "manual" (手动) not present in the source. The original English text "Coin Selection" is more general and neutral.

Correct translation:  
"選幣" or "幣選擇"
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES  
The translation "复制和数量" means "copy and amount," which is inaccurate. The correct translation for "Copy amount" should be "复制金额" or "複製數量" (using traditional Chinese characters). Since the language tag is zh-Hant (traditional Chinese), the preferable translation is:  
复制金额 -> 複製金額  
Correct translation: 複製金額
```

```
        <source>Lock unspent</source>
        <translation>锁定未花费(O)</translation>
    
YES  
The translation uses simplified Chinese characters "锁定" instead of traditional Chinese "鎖定" which is appropriate for 'zh-Hant'. Also, the "(O)" at the end is not present in the source and appears to be extraneous, possibly a shortcut key indicator that should not be included here. The correct translation should be concise and free of additional unnecessary characters.

Correct translation:  
鎖定未花費
```

```
        <source>Create wallet failed</source>
        <translation>創建錢包失敗&lt;br&gt;</translation>
    
YES  
The translation is mostly correct in meaning, but it contains an unnecessary HTML line break tag "&lt;br&gt;" which is not present in the source and could cause formatting issues or be considered unwanted content.

Correct translation:  
創建錢包失敗
```

```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>迁移钱包 &lt;b&gt;%1&lt;/b&gt;...</translation>
    
YES
The translation uses Simplified Chinese ("迁移钱包") instead of Traditional Chinese, which is expected for 'zh-Hant'. Also, the ellipsis in the source is the single character '…' (U+2026), but the translation uses three periods "...", which is inconsistent with the source punctuation.

Correct translation:
遷移錢包 &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES  
The translation "卸载钱包" means "uninstall wallet," which is not accurate for "Close wallet." The correct meaning should be about closing the wallet application or window, not uninstalling it. A better translation would be:  
關閉錢包
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>启用修剪时，如果一个钱包被卸载太久，就必须重新同步整条区块链才能再次加载它。</translation>
    
YES  
The translation uses simplified Chinese characters ("启用修剪时") instead of traditional Chinese characters expected in 'zh-Hant'. Also, "卸载" (uninstall) is not an appropriate term for "closing" a wallet. A better term would be "關閉" (close). Furthermore, the wording can be more faithful and clearer: the original says "Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled." The translation's wording is somewhat altered and changes "closing" to "uninstall," which does not match the meaning.

Correct translation:  
「如果啟用了修剪功能，錢包關閉時間過長，可能需要重新同步整條區塊鏈。」
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
YES  
The translation is generally understandable but contains minor issues:  
1. The phrase "點擊「確認」" is less natural than "點擊「確定」" for "click OK."  
2. There is a missing space after "%1" and before "會開始."  
3. The punctuation should use full-width parentheses and spacing consistent with Traditional Chinese typography.  
4. The phrase "處裡" is incorrect; the correct word is "處理."  
5. The word order and flow could be smoother for clarity and completeness, especially including "and process the full %4 block chain" fully.  
6. Absence of "starting with" clearly translated as "從…開始."  

Correct translation:  
當你點擊「確定」，%1 會開始下載並處理整個 %4 區塊鏈（大小：%2 GB），從 %4 最初啟動時的 %3 年最早交易開始。
```

```
        <source>Start %1 on system login</source>
        <translation>系统登入时启动 %1 (S)</translation>
    
YES  
The translation mixes Simplified Chinese "系统登入时启动" instead of Traditional Chinese, which would be "系統登入時啟動". Also, the extraneous "(S)" at the end is not present in the source and appears unnecessary/confusing.

Correct translation:  
系統登入時啟動 %1
```

```
        <source>Prune block storage to</source>
        <translation>将区块存储修剪至(B)</translation>
    
YES
The translation is in Simplified Chinese ("将区块存储修剪至(B)"), not Traditional Chinese ('zh-Hant'). Additionally, the "(B)" is not present in the source and might be confusing or incorrect. The source phrase is incomplete but typically the translation should simply adapt the phrase without adding extra characters.

Correct translation:
修剪區塊存儲至
```

```
        <source>This allows you or a third party tool to communicate with the node through command-line and JSON-RPC commands.</source>
        <extracomment>Tooltip text for Options window setting that enables the RPC server.</extracomment>
        <translation>这允许作为用户的你或第三方工具通过命令行和JSON-RPC命令行与节点通信。</translation>
    
YES  
The translation is in Simplified Chinese, not Traditional Chinese ('zh-Hant'). Also, "命令行和JSON-RPC命令行" redundantly repeats "命令行" twice and should be corrected for clarity and formality in Traditional Chinese.

Correct translation:  
這允許您或第三方工具透過命令列及 JSON-RPC 指令與節點進行通訊。
```

```
        <source>Subtract fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>默认从金额中减去交易手续费(F)</translation>
    
YES  
The translation mixes simplified Chinese character "默认" with traditional Chinese context and adds an unnecessary "(F)" at the end, which does not correspond to anything in the source text. The original English is in traditional Chinese context, so "默认" should be "預設" or "預設情況下" to match traditional Chinese usage. Also, no extra characters or letters should be added.

Correct translation:  
預設從金額中扣除手續費
```

```
        <source>Spend unconfirmed change</source>
        <translation>动用尚未确认的找零资金(S)</translation>
    
YES  
The translation uses Simplified Chinese character "动" instead of the Traditional Chinese equivalent "動". Also, the added "(S)" at the end is not present in the source and is unnecessary.

Correct translation:  
動用尚未確認的找零資金
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES  
The translation has redundant wording and slightly awkward phrasing. "仅观察观察地址" repeats "观察" unnecessarily and "当前" is simplified Chinese; the appropriate traditional Chinese word is "當前".

Correct translation:  
您當前在僅觀察地址中的餘額
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>“概况”标签页已启用隐私模式。要明文显示数值，请在设置中取消勾选“不明文显示数值”。</translation>
    
YES  
The translation uses Simplified Chinese characters and phrasing instead of Traditional Chinese (zh-Hant). Also, the phrase "不明文显示数值" is awkward and not a clear translation of "Mask values". In Traditional Chinese, "概况" is more commonly written as "總覽," and "标签页" should be "標籤頁."

Correct translation:  
「總覽」標籤頁已啟用隱私模式。要取消遮蔽數值，請在設定中取消勾選「遮蔽數值」。
```

```
        <source>Save…</source>
        <translation>拯救...</translation>
    
YES  
The translation "拯救..." means "rescue" or "save (a person)" in the sense of saving someone from danger, which is incorrect in the context of a file operation "Save…". The correct translation should reflect saving a file or document.

Correct translation:  
保存…
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES  
The source text is "Hide Peers Detail," which suggests an imperative or command to hide detailed information about peers. The provided translation "隐藏其他人的详细信息" means "Hide other people's detailed information," which is more literal and potentially misleading because "peers" in the Bitcoin context does not simply mean "other people," but rather other nodes or connections. Also, "隐藏" is simplified Chinese; in Traditional Chinese (zh-Hant), the usual term would be "隱藏."

Moreover, "Peers Detail" is singular or collective and should be translated as "節點詳細資料" or "節點詳細資訊," where "節點" means "nodes" or "peers."

Correct translation:  
隱藏節點詳細資料
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
YES  
The translation is problematic. It mistranslates "for soliciting addresses" as "暫時 測試地址" which means "temporarily testing addresses," altering the original meaning. The phrase "short-lived, for soliciting addresses" should convey that the connection is brief and used to request addresses. Also, there is an unnecessary space in "暫時 測試地址".

Correct translation:  
Outbound 地址抓取：短暫的，用於請求地址
```

```
        <source>1 year</source>
        <translation>1 年(Y)</translation>
    
YES
The translation "1 年(Y)" introduces an unnecessary and unclear "(Y)" which is not present in the source text. The source simply states "1 year" without any abbreviation or additional notation.

Correct translation:
1 年
```

```
        <source>Ban for</source>
        <translation>禁止連線</translation>
    
YES  
The English source "Ban for" is incomplete but suggests a phrase like "Ban for [reason/time period]". The translation "禁止連線" means "ban connection" and is more like a command or description rather than a partial phrase. It does not accurately reflect the intent or structure of the source, which likely expects a following specification. A more accurate literal translation for "Ban for" (as a prefix) would be "封鎖時間：" or "禁止連線時間：" indicating "Ban for (a period)" or "Ban for (some reason)".  

Correct translation:  
禁止連線時間：
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES  
The translation "复制和数量" means "copy and amount," which is inaccurate. The correct translation for "Copy amount" should be "复制金额" or "複製數量" (using traditional Chinese characters). Since the language tag is zh-Hant (traditional Chinese), the preferable translation is:  
复制金额 -> 複製金額  
Correct translation: 複製金額
```

```
        <source>Send</source>
        <translation>发送(E)</translation>
    
YES  
The translation is inconsistent with the language variant requested. "发送" is Simplified Chinese (used in 'zh-CN'), whereas the requested language is Traditional Chinese ('zh-Hant'). Also, the appended "(E)" is unclear and not explained in the source; it appears unnecessary and could confuse users. The correct Traditional Chinese translation for "Send" in the Bitcoin context is "發送".

Correct translation:  
發送
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES
The translated sentence is fragmented and awkward. The phrase "然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。" is incomplete and unclear. It should clearly convey that the user can sign the PSBT using, for example, an offline %1 wallet or a PSBT-compatible hardware wallet.

Correct translation:
請檢查您的交易提案。這將產生一個部分簽名的比特幣交易（PSBT），您可以儲存或複製它，然後使用例如離線%1錢包或與PSBT相容的硬體錢包進行簽名。
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
YES  
The translation is awkward and unnatural in Chinese. The phrase "將支付發送到的比特幣地址給" is unclear and redundant. A more natural and accurate translation would be:  
"要發送付款的比特幣地址"
```

```
        <source>Subtract fee from amount</source>
        <translation>從付款金額減去手續費(U)</translation>
    
YES
The added "(U)" in the translation is extraneous and not present in the source text, making the translation problematic. Also, "付款金額" (payment amount) is less precise in the Bitcoin context where "amount" typically refers to the total amount being sent or transacted.

A more accurate translation without extraneous content would be:  
從金額中減去手續費
```

```
        <source>Verify Message</source>
        <translation>验证消息签名(M)</translation>
    
YES
The translation "验证消息签名(M)" is in Simplified Chinese and includes an unexplained "(M)" which does not appear in the source text. The source text simply says "Verify Message," which should be translated into Traditional Chinese without the "(M)".

Correct translation:  
驗證訊息
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1 次/未確認</translation>
    
YES  
The translation "%1 次/未確認" is problematic because the English source "%1/unconfirmed" is describing a transaction status related to the number of confirmations, where "%1" represents the number of confirmations (e.g., 0, 1, 2...) and "unconfirmed" means the transaction has not been confirmed yet. The current translation uses "次" which means "times" and implies frequency or count, but the source is more specifically referring to confirmation count.

A better translation would be "%1 次確認/未確認" or simply "%1 確認/未確認" if "%1" can be zero or the number of confirmations. However, since the source uses "%1/unconfirmed" (with a slash), it likely means "%1 confirmations / unconfirmed". So to keep the meaning clear and consistent with Bitcoin terminology, use:

Correct translation:  
%1 次確認/未確認
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES  
The translation "复制和数量" means "copy and amount," which is inaccurate. The correct translation for "Copy amount" should be "复制金额" or "複製數量" (using traditional Chinese characters). Since the language tag is zh-Hant (traditional Chinese), the preferable translation is:  
复制金额 -> 複製金額  
Correct translation: 複製金額
```

```
        <source>Increase transaction fee</source>
        <translation>增加矿工费(F)</translation>
    
YES  
The translation uses the simplified Chinese term "矿工费" (miner fee) rather than a traditional Chinese or more neutral term, and it includes an unexplained "(F)" which does not appear in the source and may confuse users. Additionally, "transaction fee" can be translated as "交易費用" or "交易手續費" in traditional Chinese. The "(F)" likely refers to a shortcut key label in English and should not be included in the translation unless it's part of a UI convention that is localized accordingly.

Correct translation:  
增加交易手續費
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
YES  
The translation introduces unnecessary line breaks and omits the quotation marks around the %s placeholders. The format specifiers %s should be exactly the same as in the source, including quotation marks and spacing, and the translation should not add stray line breaks.  

Correct translation:  
錯誤：轉存檔案識別記錄不正確。獲得「%s」，預期「%s」。
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES  
The translation is somewhat unclear and incomplete. It does not fully convey the meaning of the original sentence, and the punctuation and spacing are improper. Moreover, "onion bind address" should be translated clearly to reflect the technical term, and "using %s" should be integrated into the sentence naturally.  

Correct translation:  
提供了多於一個 Onion 綁定位址。將使用 %s 作為自動建立的 Tor onion 服務的位址。
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>這是您支付的最高交易手續費（除了正常手續費外），優先於避免部分花費而不是定期選取幣。</translation>
    
YES  
The translation is somewhat unclear and awkward in phrasing. The phrase "優先於避免部分花費而不是定期選取幣" does not accurately convey "to prioritize partial spend avoidance over regular coin selection." Also, "定期選取幣" (literally "regularly select coins") is not a standard term in Bitcoin context; "regular coin selection" usually translates as "常規選幣" or "常規的幣幣選擇."

A more natural and accurate translation would be:  
這是您支付的最高交易手續費（除了正常手續費外），用於優先避免部分花費，而非常規的選幣方式。
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>找零低于当前粉尘阈值时会被舍弃，并计入手续费，这些交易手续费就是在这种情况下产生的。</translation>
    
YES  
The translation adds information not present in the source, making it somewhat interpretative and less direct. The source talks about the transaction fee that may be discarded if the change amount is smaller than dust at this level, but the translation explains that the change below dust will be discarded and included in the fee, with fees generated under such circumstances, which is more detailed than the original.

A clearer, more literal translation that directly follows the source would be:  
找零在此級別低於粉塵值時，您可以放棄這筆交易手續費。
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES
The translation is inaccurate and awkward in Chinese. The placement of `%s` at the end makes the sentence unclear, implying the disk belongs to the wallet, which is not the intended meaning.

Correct translation:
错误：无法将数据写入钱包 %s 所在的磁盘。
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES
The translation has incorrect word order and spacing issues. The placeholder %s should be placed where it corresponds in the sentence. Also, the colon ":" should be immediately after the word "失败" without extra space.

Correct translation:
删除交易失败：%s
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES
The translation incorrectly says "最大手续费率设置" which means "maximum fee rate setting" instead of "minimum fee rate setting."

Correct translation:
手续费率 (%s) 低于最小手续费率设置 (%s)
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>无效的 -onion 地址: '%s'</translation>
    
YES  
The translation is mostly accurate but incomplete. The source text mentions "Invalid -onion address or hostname," while the translation only says "无效的 -onion 地址" ("Invalid -onion address") and omits "或主機名稱" ("or hostname"). To fully correspond to the source text, the translation should include both "地址" and "主機名稱."

Correct translation:  
無效的 -onion 地址或主機名稱：'%s'
```

```
        <source>Not found pre-selected input %s</source>
        <translation>找不到预先选择输入%s</translation>
    
YES  
The translation uses Simplified Chinese characters ("预先选择") rather than Traditional Chinese characters expected in 'zh-Hant'. Also, the spacing before %s should be consistent with source style, ideally with a space before %s for readability. A more natural translation in Traditional Chinese would be:  

找不到預先選擇的輸入 %s
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES  
The translation contains a double negation ("不不可"), which is incorrect and confusing in Chinese. The correct phrasing should simply be "交易金额不可为负数" or "交易金额不能为负数".

Correct translation:  
交易金额不可为负数
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES  
The translation is inaccurate and somewhat unclear. The source means "the index of the change output in the transaction is out of allowable range," but the translation "交易尋找零輸出項超出範圍" literally means "transaction searching for zero output item out of range," which is confusing and not precise.

Correct translation:  
交易中的找零輸出索引超出範圍
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES  
The translation incorrectly includes an extra character "1" before the format specifier "%s". It should be removed to correctly match the source.

Correct translation:  
钱包文件创建失败：%s
```
</details>
