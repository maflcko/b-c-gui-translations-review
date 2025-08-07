# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh-Hant</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh-Hant%5D%20low%20quality)


```
        <source>New</source>
        <translation>新增 N</translation>
    
YES
The translation is problematic. It includes an extraneous "N" after "新增", which is not correct and may have been mistakenly appended. The correct translation for "New" in Traditional Chinese ('zh-Hant') should simply be:

新增

So, the correct translation is:
<translation>新增</translation>
```

```
        <source>Delete</source>
        <translation>刪除 D</translation>
    
YES
The translation "刪除 D" includes an unnecessary "D" at the end, which is not present in the source and could confuse users. 

Correct translation:
刪除
```

```
        <source>Custom…</source>
        <translation>自定义...</translation>
    
YES
The translation uses Simplified Chinese ("自定义") and ellipsis as three periods ("...") instead of the typographically correct ellipsis symbol (“…”). In Traditional Chinese, "自定義" should be used for "Custom".

Correct translation:
自定義…
```

```
        <source>About %1</source>
        <translation>关于 %1 (A)</translation>
    
YES
The translation uses simplified Chinese "关于" instead of the traditional Chinese "關於". Also, "(A)" is not present in the source and is unnecessary.

Correct translation:
關於 %1
```

```
        <source>Send</source>
        <translation>发送(S)</translation>
    
YES
The translation uses Simplified Chinese characters ("发送") instead of Traditional Chinese characters required for 'zh-Hant'. The correct Traditional Chinese translation would be:

發送(S)
```

```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
YES
The translation "付款地址(S)" is problematic:
1. The addition of "(S)" in the Chinese translation is unnecessary and is a direct carryover from the English pluralization, which is not used in Chinese. 
2. "付款地址" accurately translates "Sending addresses", but the "(S)" should be removed for correct Chinese usage.

Correct translation:
付款地址
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES
The translation "卸载钱包" means "uninstall wallet," which is incorrect for "Close wallet." The correct translation should be "關閉錢包".

Correct translation:
關閉錢包
```

```
        <source>Hide</source>
        <translation>躲</translation>
    
YES
The translation "躲" means "to evade" or "to dodge," which is not a suitable translation for the command "Hide" in a software or UI context. The appropriate term in Traditional Chinese (zh-Hant) for "Hide" in this context is "隱藏".

Correct translation:
隱藏
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES
The translation is incorrect. The English source, "Enable network activity," means to turn on or allow network activity. The current translation, "關閉網路紀錄," actually means "Disable network logging" or "Turn off network logging," which has the opposite meaning.

Correct translation:
啟用網路活動
```

```
        <source>Coin Selection</source>
        <translation>手动选币</translation>
    
YES
The translation "手动选币" literally means "manually select coins," which adds the meaning of "manual" ("手动") not present in the original source. The English phrase "Coin Selection" does not specify whether it is manual or automatic.

Correct translation:
選擇硬幣
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation is incorrect. "复制和数量" means "Copy and amount", which is not accurate. The correct translation should be "複製金額", which directly translates to "Copy amount" in Traditional Chinese.

Correct translation:
複製金額
```

```
        <source>Lock unspent</source>
        <translation>锁定未花费(O)</translation>
    
YES
The translation is mostly correct, but includes an extra "(O)" which is not present in the source and may represent a keyboard shortcut that is not specified in the English text. In zh-Hant, "锁定未花费" is a good translation, but should use the traditional character "鎖" instead of the simplified "锁".

Correct translation:
鎖定未花費
```

```
        <source>Create wallet failed</source>
        <translation>創建錢包失敗&lt;br&gt;</translation>
    
YES
There is an unwanted HTML line break tag "&lt;br&gt;" at the end of the translation that is not present in the source. This introduces unwanted formatting and is not part of the original message. Additionally, the translation itself is otherwise correct.

Correct translation:
創建錢包失敗
```

```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>迁移钱包 &lt;b&gt;%1&lt;/b&gt;...</translation>
    
YES
The translation uses simplified Chinese "迁移钱包" instead of traditional Chinese. Also, the ellipsis "..." should be replaced by the traditional full-width ellipsis "…" to match the style.

Correct translation:
遷移錢包 &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES
The translation "卸载钱包" means "uninstall wallet," which is incorrect for "Close wallet." The correct translation should be "關閉錢包".

Correct translation:
關閉錢包
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>启用修剪时，如果一个钱包被卸载太久，就必须重新同步整条区块链才能再次加载它。</translation>
    
YES
The translation is mostly accurate in meaning but contains two issues:

1. The phrase "卸载" means "unload," which is not congruent with the original term "closing." "卸载" tends to refer to explicitly unloading (detaching) the wallet rather than simply "closing" it in the normal sense of ending the application or closing the wallet file.
2. The translation refers to "必须重新同步整条区块链才能再次加载它," which adds the concept of "loading it again" ("才能再次加载它"), not present in the original text.

Correct translation:
啟用修剪時，如果錢包關閉時間過長，可能需要重新同步整條區塊鏈。

Explanation:
- "關閉" is more faithful than "卸載" for "closing."
- The ending about "loading again" is omitted as it is not in the source.
- The logical conditional structure and meaning are preserved.
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
YES
There are several issues with the translation:
1. "處裡" should be "處理" ("處裡" is a typo; correct is "處理" for "process").
2. The sentence structure in Chinese does not clearly express "starting with the earliest transactions in %3 when %4 initially launched."
3. There is missing punctuation/formatting - in Chinese, a space is typically added between a number and "GB".
4. "%4 block chain" should be "%4 區塊鏈", and "%4" appears only once in the translation, not twice as in the source.
5. "OK" is usually translated as "確定" rather than "確認" (less common for UI buttons in Traditional Chinese).
6. Some meaning about "will begin to download and process" is overly compressed into "下載，並...處理", which is not smooth.

Correct translation:
當你點擊「確定」時，%1 會開始下載並處理完整的 %4 區塊鏈（%2 GB），從 %4 剛剛推出的 %3 年最早的交易開始。

Explanation of correction:
- Used 「確定」 as OK.
- Kept the ordering and meaning as in the English.
- Corrected "處理".
- Split the meaning correctly, made punctuation clearer and formulas consistent as in source.
```

```
        <source>Prune block storage to</source>
        <translation>将区块存储修剪至(B)</translation>
    
YES
The translation is in Simplified Chinese ('区块存储修剪至'), not Traditional Chinese ('zh-Hant'). Additionally, the format "(B)" is added, which is not in the source and is not necessary.

Correct translation:
將區塊存儲修剪至
```

```
        <source>This allows you or a third party tool to communicate with the node through command-line and JSON-RPC commands.</source>
        <extracomment>Tooltip text for Options window setting that enables the RPC server.</extracomment>
        <translation>这允许作为用户的你或第三方工具通过命令行和JSON-RPC命令行与节点通信。</translation>
    
YES
The translation is in Simplified Chinese ('这允许作为用户的你或第三方工具通过命令行和JSON-RPC命令行与节点通信。'), not Traditional Chinese as required for 'zh-Hant'. Also, "JSON-RPC命令行" is a mistranslation; it should be "JSON-RPC命令" (commands), not "命令行" (command line). There is also redundant wording ("作为用户的你" is awkward; simply use "你" or "您"). The translation should be:

Correct translation:
這允許你或第三方工具通過命令列和 JSON-RPC 指令與節點通訊。
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES
The translation is problematic. There is redundancy ("观察观察地址") and the phrasing is not idiomatic in Traditional Chinese ('zh-Hant'). Additionally, "当前" should be "目前" in zh-Hant, and the overall sentence structure should be improved.

Correct translation:
您目前在僅觀察地址中的餘額
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>“概况”标签页已启用隐私模式。要明文显示数值，请在设置中取消勾选“不明文显示数值”。</translation>
    
YES
The translation is mostly accurate, but it uses simplified Chinese characters ("启用", "数值", "勾选", "设置") instead of traditional Chinese, which should be used for 'zh-Hant'. Also, the translation of "Mask values" is unclear—"不明文显示数值" is confusing due to the double negative. The translation should adopt standard traditional forms, preserve clarity, and properly translate UI elements.

Correct translation:
「概覽」標籤頁已啟用隱私模式。若要顯示數值，請取消選取「設定」→「隱藏數值」。
```

```
        <source>Save…</source>
        <translation>拯救...</translation>
    
YES
The translation is problematic. The source "Save…" refers to saving a file or data, but "拯救..." means "rescue" or "save (from danger)" in Chinese, which is incorrect in a software context. Also, the ellipsis "…" is three dots in the translation but a single Unicode ellipsis in the source.

Correct translation:
儲存…
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES
The translation is problematic. The original text "Hide Peers Detail" should be translated as "隱藏節點詳細資訊" or "隱藏對等節點詳細資訊" in Traditional Chinese. The provided translation "隐藏其他人的详细信息" means "Hide other people's detailed information", which is inaccurate and uses Simplified Chinese characters ("隐藏" and "详细信息" should be "隱藏" and "詳細資訊" in Traditional Chinese).

Correct translation:
隱藏節點詳細資訊
or
隱藏對等節點詳細資訊
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
YES
The translation is problematic: 
1. "Outbound 地址取得" is somewhat unnatural; a clearer translation is needed.
2. "用於短暫，暫時 測試地址" is misleading—"測試地址" means "testing address", which is incorrect. The source says it's for soliciting addresses, not testing.
3. Whitespace issue: unnecessary space before "測試地址" (which also should not be used).
4. "短暫" can be better translated as "短期" or something similar, but "短暫使用" is more natural.

Correct translation:
Outbound 地址取得：短暫用於向對方請求地址
```

```
        <source>1 year</source>
        <translation>1 年(Y)</translation>
    
YES
The translation adds “(Y)” (presumably to indicate "year") which is not present in the source. Additionally, the space between the numeral and the character 年 is slightly unusual, though it is sometimes used in Chinese UI; however, best practice is to match the original as closely as possible.

Correct translation:
1 年
```

```
        <source>Ban for</source>
        <translation>禁止連線</translation>
    
YES
The translation "禁止連線" means "forbid connection," which is not an accurate translation of "Ban for." The phrase "Ban for" typically expects to be followed by a duration (e.g., "Ban for 1 hour"). The translation should reflect that the action is to ban for a certain period.

Correct translation:
封鎖時間
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation is incorrect. "复制和数量" means "Copy and amount", which is not accurate. The correct translation should be "複製金額", which directly translates to "Copy amount" in Traditional Chinese.

Correct translation:
複製金額
```

```
        <source>Send</source>
        <translation>发送(E)</translation>
    
YES
The translation uses the simplified Chinese character "发送" instead of the traditional Chinese "傳送". Also, the letter "(E)" is likely carried from a menu accelerator and should match the expected localization if one exists. In traditional Chinese, "送出" or "傳送" are commonly used for "Send".

Correct translation:
傳送(E)
or
送出(E)
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES  
The translation splits the sentence incorrectly, resulting in unnatural phrasing and a grammatical error. The phrase "然後使用簽名。離線%1錢包" should instead be "然後用例如離線的%1錢包，或可支援PSBT的硬體錢包來簽名". The full sentence should flow naturally without strange breaks.

Correct translation:  
請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以將其儲存或複製，然後用例如離線的%1錢包或支援PSBT的硬體錢包來簽名。
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
YES
The translation is awkward and contains an extra "給" at the end, which is not needed and makes the sentence grammatically incorrect. The phrase should flow naturally.

Correct translation:
要發送付款到的比特幣地址
```

```
        <source>Verify Message</source>
        <translation>验证消息签名(M)</translation>
    
YES
The translation uses Simplified Chinese "验证消息签名(M)" instead of Traditional Chinese. Also, "Verify Message" should be literally translated, not "Verify Message Signature". The translation also adds "(M)", which may be used as a shortcut key indicator, but it's not present in the source.

Correct translation:
驗證訊息
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation is incorrect. "复制和数量" means "Copy and amount", which is not accurate. The correct translation should be "複製金額", which directly translates to "Copy amount" in Traditional Chinese.

Correct translation:
複製金額
```

```
        <source>Increase transaction fee</source>
        <translation>增加矿工费(F)</translation>
    
YES
The translation "增加矿工费(F)" translates to "Increase miner's fee (F)", which is not the most accurate or standard rendering for "transaction fee" in the context of Bitcoin. The correct term should be "交易手續費" for "transaction fee". Also, the "(F)" is not present in the source and should not be included.

Correct translation:
增加交易手續費
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
YES
There are issues with the formatting and phrasing:
1. Line breaks are added inappropriately which may cause layout issues.
2. "%s" should be enclosed in quotation marks as in the source.
3. The term "獲得" is unusual in this context; "收到" or "實際為" is more idiomatic.

Correct translation:
錯誤：轉存檔案識別記錄不正確。實際為「%s」，預期為「%s」。
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES
The translation is understandable but has several issues:
1. "多數" means "the majority" or "most", which is incorrect. It should be "多個" for "more than one".
2. Whitespace issue: There is an unnecessary space after the period.
3. The translation of "onion bind address" should be clear; "綁定位址" is close but can be more precise.
4. "對自動建立的Tor服務用%s" is not natural Chinese. It would be clearer to say "自動建立的 Tor onion 服務將使用 %s。"

Correct translation:
提供多個 onion 綁定位址。自動建立的 Tor onion 服務將使用 %s。
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>找零低于当前粉尘阈值时会被舍弃，并计入手续费，这些交易手续费就是在这种情况下产生的。</translation>
    
YES
The translation is essentially accurate in meaning, but it is written in Simplified Chinese instead of Traditional Chinese (zh-Hant). Additionally, the structure can be improved for clarity and conciseness. 

Correct translation:
如果找零小於粉塵閾值，則會被丟棄並計入交易手續費；這就是在此情況下可能產生的手續費。

Alternatively, for brevity:
當找零小於此層級的粉塵時，將會被捨棄並計入交易手續費。
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES
The translation is mostly accurate but has a minor issue with the position of "磁盘" (disk), making it a bit awkward/nonnative in Chinese. It should emphasize that it's unable to write data to disk, for wallet %s (not "wallet's disk %s"). Additionally, the term "错误" should use the traditional form "錯誤" in zh-Hant, and the period should be a Chinese full stop "。", though this is not a strict requirement.

Correct translation:
錯誤：無法將數據寫入錢包 %s 的磁碟。
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES
The translation has an incorrect word order and formatting. The %s placeholder should be placed correctly as in the English source. There is also an extra colon at the end of the translated sentence that does not match the source.

Correct translation:
移除交易時失敗：%s

Or, if you want to preserve the %s at the start (which is less natural in Chinese, but possible), at least move the colon appropriately:
%s：刪除交易時失敗

The recommended translation is:
移除交易時失敗：%s
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES
The translation incorrectly translates "minimum fee rate setting" as "最大手续费率设置" ("maximum fee rate setting") instead of "最低手续费率设置" ("minimum fee rate setting").

Correct translation:
手續費率 (%s) 低於最低手續費率設定 (%s)
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>无效的 -onion 地址: '%s'</translation>
    
YES
The translation uses Simplified Chinese ('无效的'), but 'zh-Hant' should be in Traditional Chinese. Also, "hostname" is omitted in the translation. It should be included.

Correct translation:
無效的 -onion 位址或主機名稱：「%s」
```

```
        <source>Not found pre-selected input %s</source>
        <translation>找不到预先选择输入%s</translation>
    
YES
The translation uses simplified Chinese characters ("预先选择输入") instead of traditional Chinese, which 'zh-Hant' requires. The spacing for the format specifier %s is correct, but the characters should be traditional.

Correct translation:
找不到預先選擇的輸入 %s
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES
There is a redundancy in the translation: "不不可" is an error (double negative). It should be "不可為負數" (must not be negative).

Correct translation:
交易金額不可為負數
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES
The translation is problematic. The phrase "尋找零輸出項" is an incorrect and confusing representation of "change output." The proper translation for "change" in the context of Bitcoin transactions is "找零," and "output index" should be rendered as "輸出項索引."

Correct translation:
交易找零輸出項索引超出範圍
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES
The translation incorrectly includes "1" before the %s placeholder, which is not present in the source. This appears to be an error and could cause confusion in display. The rest of the translation is correct.

Correct translation:
錢包文件創建失敗：%s
```
</details>

Number of issues: 44.
