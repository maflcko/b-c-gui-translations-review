# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>cmn</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bcmn%5D%20low%20quality)


```
        <source>Delete</source>
        <translation>刪除 D</translation>
    
YES
The translation incorrectly adds "D" after "刪除", which is not appropriate in Mandarin Chinese ('cmn'). There is also an unnecessary space between "刪除" and "D". 

Correct translation:
刪除
```

```
        <source>%1 and %2</source>
        <translation>%1又 %2</translation>
    
YES
There is an unwanted whitespace format issue: there should not be a space between "又" and "%2".

Correct translation:
%1又%2
```

```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
YES
The translation is mostly correct, but "(S)" is an English suffix and should not be used in a Chinese translation. The plural indication is also unnecessary in Chinese, as plurality is generally inferred from context.

Correct translation:
付款地址
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES
The translation "卸载钱包" means "uninstall wallet," which is not the same as "Close wallet." The latter simply means to shut or exit the wallet without uninstalling it.

Correct translation:
关闭钱包
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES
The translation is incorrect. "關閉網路紀錄" means "Close network record" or "Disable network logging", which is the opposite of "Enable network activity".

Correct translation:
啟用網路活動
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation is inaccurate. The English phrase "Copy amount" means to copy the numerical value/amount, but the translation "复制和数量" means "copy and amount", which is incorrect. The conjunction "和" ("and") is erroneous here.

Correct translation:
复制金额
```

```
        <source>Create wallet failed</source>
        <translation>創建錢包失敗&lt;br&gt;</translation>
    
YES
There is an erroneous inclusion of "&lt;br&gt;" (HTML line break tag in escaped form) at the end of the translation, which is not present in the original source. This is unnecessary and may cause formatting issues.

Correct translation:
創建錢包失敗
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES
The translation "卸载钱包" means "uninstall wallet," which is not the same as "Close wallet." The latter simply means to shut or exit the wallet without uninstalling it.

Correct translation:
关闭钱包
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
YES
There are some issues in the translation:

1. "處裡" should be "處理" (correct character for 'process').
2. The placement/order of elements does not match the original; the translation skips or muddles "starting with the earliest transactions in %3 when %4 initially launched."
3. The translation uses the incorrect format for punctuation with Chinese (such as space after colons and parentheses).
4. The translation omits "when %4 initially launched" (但省略了"%4最初啟動時").
5. The phrase "點擊「確認」" may be better as "點擊確定" for consistency with common UI language.

Correct translation:
當你點擊確定後，%1 將開始下載並處理完整的 %4 區塊鏈（%2 GB），從 %4 最初於 %3 啟動時的最早交易開始。
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES
The translation is repetitive with "观察观察地址" ("watch watch address"), which is erroneous. It should be "仅观察地址" for "watch-only addresses".

Correct translation:
您当前在仅观察地址中的余额
```

```
        <source>Save…</source>
        <translation>拯救...</translation>
    
YES
The translation of "Save…" as "拯救..." is incorrect in Chinese (cmn). "拯救" means "to rescue" rather than "to save" in the sense of saving a file. The correct term is "保存…".

Correct translation:
保存…
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES
The translation "隐藏其他人的详细信息" means "Hide other people's detailed information," which is inaccurate. "Peers" in the context of Bitcoin refers to network peers (other nodes), not "other people" in a general sense.

Correct translation:
隐藏节点详细信息
```

```
        <source>Clear console</source>
        <translation>清主控台</translation>
    
YES
The translation "清主控台" is not idiomatic in Mandarin Chinese. The correct term for "console" in the computing context is 控制台, and "Clear" should be translated as 清除.

Correct translation:
清除控制台
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
YES
The translation is inaccurate and awkward. "暫時 測試地址" means "temporarily test addresses," which misrepresents "for soliciting addresses" (i.e., for requesting/gathering addresses). Also, "用於短暫" is awkward.

Correct translation:
Outbound 地址获取：短暂用于请求地址
```

```
        <source>Ban for</source>
        <translation>禁止連線</translation>
    
YES
The translation "禁止連線" means "prohibit connection," which does not accurately render the English phrase "Ban for," which expects a duration (for example, "Ban for 24 hours"). The translation misses the "for (duration)" aspect.

Correct translation:
禁止（时长）  
or  
禁止（持续时间）  
If it's shown with a duration variable, use:  
禁止%1  
or  
禁止%1时间

Choose format according to context: if a duration is appended, e.g., "Ban for %1", it should be  
禁止%1
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation is inaccurate. The English phrase "Copy amount" means to copy the numerical value/amount, but the translation "复制和数量" means "copy and amount", which is incorrect. The conjunction "和" ("and") is erroneous here.

Correct translation:
复制金额
```

```
        <source>Copy Address</source>
        <translation>複製 地址</translation>
    
YES  
There is an unnecessary space between "複製" and "地址". In Chinese, there should not be a space.

Correct translation:
复制地址
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES
There is an issue with the sentence structure and punctuation in the translation. Specifically, "然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。" is incorrect and awkward, as the period splits what should be a continuous phrase. It should mention "sign [it] with an offline %1 wallet or a PSBT-compatible hardware wallet," not "use sign. offline wallet...".

Correct translation:
請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用例如離線%1錢包或支援PSBT的硬體錢包簽名。

Explanation:
- The sentence is now continuous and grammatically correct.
- The meaning and structure are faithful to the original.
- "%1" is preserved correctly in the right position.
- No unwanted content or spam detected.
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
YES
The word order is awkward and "給" at the end is unnecessary and incorrect in this context. A natural Mandarin translation would be:
用於接收支付的比特幣地址
or
要發送支付的比特幣地址

Correct translation:
要將付款發送到的比特幣地址
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation is inaccurate. The English phrase "Copy amount" means to copy the numerical value/amount, but the translation "复制和数量" means "copy and amount", which is incorrect. The conjunction "和" ("and") is erroneous here.

Correct translation:
复制金额
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
YES
This translation has formatting issues:
1. There are unnecessary line breaks before the translation starts and in the middle, which should not exist.
2. The wording "獲得%s" is awkward; "收到" or "得到" are more natural.
3. The spacing before "%s" is inconsistent.
4. The full-width punctuation is correct for Chinese, but attention to consistency is recommended.

Correct translation:
錯誤：轉存檔案識別記錄不正確。收到「%s」，預期「%s」。
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES
The translation has issues:
1. "多數" is awkward and incorrect for "more than one". A proper expression would be "多于一个" or "多个".
2. "TOR路由綁定位址" is an unnatural way to refer to "onion bind address". A more standard term is "onion绑定地址" or "Onion绑定地址".
3. "對自動建立的Tor服務用%s" has unnatural grammar. Should use "将使用%s" and clarify the object.
4. There is inconsistent use of casing for "TOR" vs "Tor", and spacing before "對".

Correct translation:
提供了多个Onion绑定地址。将为自动创建的Tor onion服务使用%s。
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
YES
The translation is missing the part "expected %s", and the wording is a bit awkward. Also, spacing between %s and surrounding text is unclear and may cause formatting issues.

Correct translation:
錯誤：轉存檔案的校驗和不匹配。計算值為 %s，預期為 %s
```

```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
YES
There is a typo in the translation: "unit32_t" should be "uint32_t". Also, there should be a space between "版本号" and "%u" to match formatting conventions, since "%u" is a standalone variable.

Correct translation:
错误：无法把版本号 %u 作为uint32_t解析
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES
There are two issues: 
1. The format specifier %s is misplaced at the beginning, while in the source it appears at the end.
2. A colon is retained at the end whereas it was at the end of the English sentence, only after %s; it introduces unnecessary punctuation after the sentence.

Correct translation:
删除交易失败：%s
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES
The translation is inaccurate. The source says "lower than the minimum fee rate setting", but the translation says "lower than the maximum fee rate setting" (最大 means maximum). It should be "最低" for minimum.

Correct translation:
手续费率 (%s) 低于最小手续费率设置 (%s)
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES
The translation contains a double negative: "不不可为负数", which is incorrect in Chinese. It should be "交易金额不可为负数" or "交易金额不能为负数".

Correct translation:
交易金额不可为负数
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES
The translation is inaccurate. The English phrase "change output" in the context of Bitcoin refers specifically to the transaction's "找零輸出" (change output), not "尋找零輸出" which literally means "searching for zero output". The word "尋找" (search) is incorrect here.

Correct translation:
交易找零输出项超出范围
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES
The translation incorrectly introduces an extra '1' before the format specifier '%s', which is not present in the original source. This is likely a typographical error. The rest of the translation is accurate, but the format specifier should match exactly.

Correct translation:
钱包文件创建失败：%s
```
</details>

Number of issues: 29.
