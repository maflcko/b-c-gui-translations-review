# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>cmn</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bcmn%5D%20request)


<!-- cache_translation_check_cmn_b8e3c443228cffa967a07ac27cf811742669784cf54541470bf150181540b9fb -->
```
        <source>&amp;Export</source>
        <translation> 导出(&amp;E)</translation>
    
ERR
Leading whitespace before the text. Remove it.

Correct translation:
导出(&amp;E)
```

<!-- cache_translation_check_cmn_39d1e41b3f145999fc961e8a43f666df401f56223041b177f975aa4b235d0f68 -->
```
        <source>&amp;Edit</source>
        <translation> 编辑(&amp;E)</translation>
    
ERR
Leading whitespace before the translation is unintended formatting. Remove the initial space.

Correct translation:
编辑(&E)
```

<!-- cache_translation_check_cmn_0467b0276d62fd95ce9b8af3bd4c3e87347f98def98ee4a26f32868c51c98725 -->
```
        <source>%1 and %2</source>
        <translation>%1又 %2</translation>
    
ERR
There is an unwanted whitespace format issue: there should not be a space between "又" and "%2".

Correct translation:
%1又%2
```

<!-- cache_translation_check_cmn_a7c351c427df6d7b486104f1939aef897d1cfa92e831eea41d659421963ae8ce -->
```
        <source>&amp;Minimize</source>
        <translation>最小化</translation>
    
ERR
The translation is missing the '&' which is used for the shortcut key in the interface and should appear exactly once.

Correct translation:
&最小化
```

<!-- cache_translation_check_cmn_8805d81be15da11902e68e1a4f034a336df1d660d01d4122ff333a49a3a519f5 -->
```
        <source>&amp;Options…</source>
        <translation>&amp;選項...</translation>
    
ERR
Ellipsis should match the source’s single-character ellipsis (…); the translation used three dots (...).

Correct translation:
&選項…
```

<!-- cache_translation_check_cmn_65f1ede3a79d328c9143d790f44f4c9577f4191be8c35c67a613d2142266700b -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation> 加密钱包(&amp;E)</translation>
    
ERR
Leading stray space and missing ellipsis. The source has an ellipsis (…) that should be preserved, and there should be no leading whitespace.

Correct translation:
加密钱包(&E)…
```

<!-- cache_translation_check_cmn_03c5cf45ae9c8378ce91dc74c1eefa379bec8fa054728eebd461f2603e1208a8 -->
```
        <source>Close All Wallets…</source>
        <translation> 关所有钱包...</translation>
    
ERR
The translation is missing the verb “关闭”, contains an unwanted leading space, and uses three dots instead of the ellipsis character.

Correct translation:
关闭所有钱包…
```

<!-- cache_translation_check_cmn_42a695c10a15cebe8935b1a9013c83e954e990e2627b810a54a4e13beb932376 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>從剪貼簿載入PSBT</translation>
    
ERR
The '&' from the source (used for shortcut key indication) is missing in the translation. It should appear exactly once, in a normal position in Chinese UI convention.

Correct translation:
從剪貼簿(&amp;)載入PSBT…
```

<!-- cache_translation_check_cmn_07b24e731acfde530620e37ba80e4dd4623efd6c803f490116295af92f3094db -->
```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
ERR
The translation "卸载钱包" means "uninstall wallet," which is not the same as "Close wallet." The latter simply means to shut or exit the wallet without uninstalling it.

Correct translation:
关闭钱包
```

<!-- cache_translation_check_cmn_950cb28cc0f57eebf6fb6e99e761a355724df12da7463d87aeda770e4eaacc26 -->
```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
ERR
The translation is incorrect. "關閉網路紀錄" means "Close network record" or "Disable network logging", which is the opposite of "Enable network activity".

Correct translation:
啟用網路活動
```

<!-- cache_translation_check_cmn_a6e9d6abcc4431799e73f806331c34124d5e3cf2ac80d23af4c298249010502b -->
```
        <source>Copy &amp;amount</source>
        <translation>复制和数量</translation>
    
ERR
The translation "复制和数量" is inaccurate. The "&amp;" in the source indicates a shortcut key, not the word "and". In 'cmn' (Mandarin Chinese), the correct translation should retain the shortcut function. A common approach is to place the shortcut before the main word using an underlined character, but since "&" can appear anywhere, using it at the start is fine.

Correct translation:
复制金额(&A)
```

<!-- cache_translation_check_cmn_f568c8e4ca957eadfdf7e283377c5fc85d3009fddd6ffff42a1e15c5865ca108 -->
```
        <source>&amp;Unlock unspent</source>
        <translation>解鎖未花費的</translation>
    
ERR
The translation is missing the shortcut key indicator '&' which was present in the source text. In the context of Bitcoin software (like Bitcoin Core), "unspent" usually refers to "unspent outputs" (UTXOs). While the provided translation is semantically okay, it should include the '&' and ideally sound more natural for a UI element.

Correct translation:
&解鎖未花費的
```

<!-- cache_translation_check_cmn_5ace09bb0cf15a835e9c7cf2d5e3473d50f6fa76d17319aec8e6fd38b6f1c1dc -->
```
        <source>(change)</source>
        <translation> (零钱)</translation>
    
ERR
The translation includes a stray leading space and uses less accurate terminology for Bitcoin context. "零钱" means small cash, while "找零" is the proper term for transaction change.

Correct translation:
(找零)
```

<!-- cache_translation_check_cmn_39f8fd7fcf43b82d6213e666e6289334dc525e42ff2102d6b2e7aca11cb82165 -->
```
        <source>Create wallet failed</source>
        <translation>創建錢包失敗&lt;br&gt;</translation>
    
ERR
There is an erroneous inclusion of "&lt;br&gt;" (HTML line break tag in escaped form) at the end of the translation, which is not present in the original source. This is unnecessary and may cause formatting issues.

Correct translation:
創建錢包失敗
```

<!-- cache_translation_check_cmn_9e2dce0cc7395f2a8bde80a4d48463efe39601d2b3d5a8f7b444b72744f59450 -->
```
        <source>Load Wallets</source>
        <extracomment>Title of progress window which is displayed when wallets are being loaded.</extracomment>
        <translation> 加载钱包</translation>
    
ERR
The translation contains a stray leading non-breaking space, which is a whitespace formatting issue. The wording itself is fine.

Correct translation:
加载钱包
```

<!-- cache_translation_check_cmn_f358e27c2374e039b702204bb417d9ca6c7aec3f3eb46f9b815071a1f568a76a -->
```
        <source>Loading wallets…</source>
        <extracomment>Descriptive text of the load wallets progress window which indicates to the user that wallets are currently being loaded.</extracomment>
        <translation> 載入錢包中...</translation>
    
ERR
The translation contains an unwanted leading non-breaking space and uses three dots instead of the ellipsis character used in the source.

Correct translation:
正在載入錢包…
```

<!-- cache_translation_check_cmn_6ccbcdcc6a5c647e054268560bf2d5033d8c129a0ccc4ae94dffc4deefea4412 -->
```
        <source>Opening Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the open wallet progress window which indicates to the user which wallet is currently being opened.</extracomment>
        <translation>打开钱包&lt;b&gt;%1&lt;/b&gt;...</translation>
    
ERR
The translation is accurate, but it uses three dots "..." instead of the single ellipsis character "…", which is used in the source and preferred for consistency.

Correct translation:
打开钱包<b>%1</b>…
```

<!-- cache_translation_check_cmn_07b24e731acfde530620e37ba80e4dd4623efd6c803f490116295af92f3094db -->
```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
ERR
The translation "卸载钱包" means "uninstall wallet," which is not the same as "Close wallet." The latter simply means to shut or exit the wallet without uninstalling it.

Correct translation:
关闭钱包
```

<!-- cache_translation_check_cmn_ede40189b4cca918ec555b08ca9cb5a3d9f8b3ed3852ea2add55e099292651bd -->
```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
ERR
There are some issues in the translation:

1. "處裡" should be "處理" (correct character for 'process').
2. The placement/order of elements does not match the original; the translation skips or muddles "starting with the earliest transactions in %3 when %4 initially launched."
3. The translation uses the incorrect format for punctuation with Chinese (such as space after colons and parentheses).
4. The translation omits "when %4 initially launched" (但省略了"%4最初啟動時").
5. The phrase "點擊「確認」" may be better as "點擊確定" for consistency with common UI language.

Correct translation:
當你點擊確定後，%1 將開始下載並處理完整的 %4 區塊鏈（%2 GB），從 %4 最初於 %3 啟動時的最早交易開始。
```

<!-- cache_translation_check_cmn_5ce60f1169385d2d3210dc1d475c5b695a1b7c16537f480bdcad64d137f55af0 -->
```
        <source>Size of &amp;database cache</source>
        <translation>資料庫快取的大小 </translation>
    
ERR
The translation is missing the '&' character which indicates the shortcut key and should appear exactly once as in the source text.

Correct translation:
資料庫快取(&amp;)的大小
```

<!-- cache_translation_check_cmn_62164728b6a7c177c1d04a3a116d70629560c46f15c563b6acbb30bb130c7c74 -->
```
        <source>Save…</source>
        <translation>拯救...</translation>
    
ERR
The translation of "Save…" as "拯救..." is incorrect in Chinese (cmn). "拯救" means "to rescue" rather than "to save" in the sense of saving a file. The correct term is "保存…".

Correct translation:
保存…
```

<!-- cache_translation_check_cmn_3f36d050ff17a707a586960e2695f55721a2fe19f9f0e9bb7cef3488d83ee57a -->
```
        <source>Transaction broadcast successfully! Transaction ID: %1</source>
        <translation>交易成功廣播！交易 ID：％1</translation>
    
ERR
The Chinese full-width character "％" is used instead of the ASCII percent sign "%", which can cause issues with format specifiers.

Correct translation:
交易成功广播！交易 ID: %1
```

<!-- cache_translation_check_cmn_488a31aac260773afaaa52303dc65dcf6d65dc211e76753ff912703f6143a292 -->
```
        <source>Transaction has %1 unsigned inputs.</source>
        <translation>交易有％1個未簽名的inputs。</translation>
    
ERR
The translation is mostly accurate but contains two issues:
1. The percent sign is a full-width '％' rather than the ASCII '%', which could break placeholder substitution.
2. The English word "inputs" is not translated or transliterated; in Chinese Bitcoin: "输入" or "输入项" is commonly used.

Correct translation:
交易有%1个未签名的输入。
```

<!-- cache_translation_check_cmn_0c2f3b1ca9da511a52168e61c92498723b5b95d121bdf4b2cf14fd3c7c628264 -->
```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
ERR
The translation "隐藏其他人的详细信息" means "Hide other people's detailed information," which is inaccurate. "Peers" in the context of Bitcoin refers to network peers (other nodes), not "other people" in a general sense.

Correct translation:
隐藏节点详细信息
```

<!-- cache_translation_check_cmn_a1ba9805a5286411483f33f0326173d0b46b69ffd46746e19023aef7c1ce69a7 -->
```
        <source>Clear console</source>
        <translation>清主控台</translation>
    
ERR
The translation "清主控台" is not idiomatic in Mandarin Chinese. The correct term for "console" in the computing context is 控制台, and "Clear" should be translated as 清除.

Correct translation:
清除控制台
```

<!-- cache_translation_check_cmn_294a6b69c8397bcbe46ef5b4e5f1d3feee9e2d9c3a4b4f1ce25d159ee9c964cc -->
```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
ERR
The translation is inaccurate and awkward. "暫時 測試地址" means "temporarily test addresses," which misrepresents "for soliciting addresses" (i.e., for requesting/gathering addresses). Also, "用於短暫" is awkward.

Correct translation:
Outbound 地址获取：短暂用于请求地址
```

<!-- cache_translation_check_cmn_8b5955a6a1e135aae44745f02687277c90bd3df0dd2fd8b7f3f4e99139bb5b6a -->
```
        <source>1 d&amp;ay</source>
        <translation>一天</translation>
    
ERR
The translation is missing the shortcut key indicator '&'. It should appear exactly once, as in the source. Also, while "一天" is semantically correct, it does not represent the ampersand shortcut.

Correct translation:
1 &天
```

<!-- cache_translation_check_cmn_0b3b3af4650d33e99b1d342a24ed4dc6f10b1492d6bddc9b83ce8b4485e94a60 -->
```
        <source>Ban for</source>
        <translation>禁止連線</translation>
    
ERR
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

<!-- cache_translation_check_cmn_a6e9d6abcc4431799e73f806331c34124d5e3cf2ac80d23af4c298249010502b -->
```
        <source>Copy &amp;amount</source>
        <translation>复制和数量</translation>
    
ERR
The translation "复制和数量" is inaccurate. The "&amp;" in the source indicates a shortcut key, not the word "and". In 'cmn' (Mandarin Chinese), the correct translation should retain the shortcut function. A common approach is to place the shortcut before the main word using an underlined character, but since "&" can appear anywhere, using it at the start is fine.

Correct translation:
复制金额(&A)
```

<!-- cache_translation_check_cmn_070c587fbb4ed6d06fe006cbce66dae59f8480ae60cbd56f50e09c90fb4e8ad5 -->
```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
ERR
There is an issue with the sentence structure and punctuation in the translation. Specifically, "然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。" is incorrect and awkward, as the period splits what should be a continuous phrase. It should mention "sign [it] with an offline %1 wallet or a PSBT-compatible hardware wallet," not "use sign. offline wallet...".

Correct translation:
請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用例如離線%1錢包或支援PSBT的硬體錢包簽名。

Explanation:
- The sentence is now continuous and grammatically correct.
- The meaning and structure are faithful to the original.
- "%1" is preserved correctly in the right position.
- No unwanted content or spam detected.
```

<!-- cache_translation_check_cmn_28469b6bdd232ba1dcfd58e7d6028a052f194701749fcdb0f461d138b0475935 -->
```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
ERR
The word order is awkward and "給" at the end is unnecessary and incorrect in this context. A natural Mandarin translation would be:
用於接收支付的比特幣地址
or
要發送支付的比特幣地址

Correct translation:
要將付款發送到的比特幣地址
```

<!-- cache_translation_check_cmn_a6e9d6abcc4431799e73f806331c34124d5e3cf2ac80d23af4c298249010502b -->
```
        <source>Copy &amp;amount</source>
        <translation>复制和数量</translation>
    
ERR
The translation "复制和数量" is inaccurate. The "&amp;" in the source indicates a shortcut key, not the word "and". In 'cmn' (Mandarin Chinese), the correct translation should retain the shortcut function. A common approach is to place the shortcut before the main word using an underlined character, but since "&" can appear anywhere, using it at the start is fine.

Correct translation:
复制金额(&A)
```

<!-- cache_translation_check_cmn_ad835176286ec5001b2d46ca1cecbac97741bc5c25c342e04972405d7b6424e8 -->
```
        <source>&amp;Show transaction details</source>
        <translation>顯示交易明細</translation>
    
ERR
The translation is missing the '&' which indicates the shortcut key. It must appear exactly once in the translation, placed appropriately for Chinese users.

Correct translation:
&顯示交易明細
```

<!-- cache_translation_check_cmn_b8e3c443228cffa967a07ac27cf811742669784cf54541470bf150181540b9fb -->
```
        <source>&amp;Export</source>
        <translation> 导出(&amp;E)</translation>
    
ERR
Leading whitespace before the text. Remove it.

Correct translation:
导出(&amp;E)
```

<!-- cache_translation_check_cmn_c7322b733fb6e07eeb0c5a4f89faf9d956509351ec4b36c6ad2b25b6f1a6acf6 -->
```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
ERR
This translation has formatting issues:
1. There are unnecessary line breaks before the translation starts and in the middle, which should not exist.
2. The wording "獲得%s" is awkward; "收到" or "得到" are more natural.
3. The spacing before "%s" is inconsistent.
4. The full-width punctuation is correct for Chinese, but attention to consistency is recommended.

Correct translation:
錯誤：轉存檔案識別記錄不正確。收到「%s」，預期「%s」。
```

<!-- cache_translation_check_cmn_78a3727db7b2c58049bfbe79faf011a77473fd002f75700a072bffc43d41b2bc -->
```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
ERR
The translation has issues:
1. "多數" is awkward and incorrect for "more than one". A proper expression would be "多于一个" or "多个".
2. "TOR路由綁定位址" is an unnatural way to refer to "onion bind address". A more standard term is "onion绑定地址" or "Onion绑定地址".
3. "對自動建立的Tor服務用%s" has unnatural grammar. Should use "将使用%s" and clarify the object.
4. There is inconsistent use of casing for "TOR" vs "Tor", and spacing before "對".

Correct translation:
提供了多个Onion绑定地址。将为自动创建的Tor onion服务使用%s。
```

<!-- cache_translation_check_cmn_90fda8f6932228d174e380ed1c7df7be7ae98d00ff1e42c56766226c0f6bb80a -->
```
        <source>Option '-checkpoints' is set but checkpoints were removed. This option has no effect.</source>
        <translation>选项“-checkpoints”已设置，但检查点已被移除。该选项不再生效。 </translation>
    
ERR
Trailing whitespace at the end of the translation.

Correct translation:
选项“-checkpoints”已设置，但检查点已被移除。该选项不再生效。
```

<!-- cache_translation_check_cmn_fc44b6029c7dbac45686cc79b705b8c897f4c829f9f3f5057b0a8d2f641e4b4e -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>修剪：上次钱包同步超出了已修剪的数据范围。您需要执行“-reindex”（对于已修剪节点，需要重新下载整个区块链）。 </translation>
    
ERR
The translation contains a trailing space at the end, which is a whitespace formatting issue. Also, quoting -reindex is unnecessary.

Correct translation:
修剪：上次钱包同步超出了已修剪的数据范围。您需要执行 -reindex（对于已修剪节点，需要重新下载整个区块链）。
```

<!-- cache_translation_check_cmn_eb968025b9240f22a7d27bd23c989a8fc00fef0ee8185f551adcffb7a2452904 -->
```
        <source>-paytxfee is deprecated and will be fully removed in v31.0.</source>
        <translation>“-paytxfee”已弃用，并将在 v31.0 中完全移除。 </translation>
    
ERR
There is an unnecessary trailing space at the end of the translation.

Correct translation:
“-paytxfee”已弃用，并将在 v31.0 中完全移除。
```

<!-- cache_translation_check_cmn_212c3af68e90ae4a89c435e0fc3e60da04c4a65ab354a77723b7b670db8e3821 -->
```
        <source>Can't spend unconfirmed version %d pre-selected input with a version 3 tx</source>
        <translation>无法使用版本3交易花费未确认版本1%d的预选输入。</translation>
    
ERR
The translation adds the number "1" before the format specifier "%d" which is not present in the source text. In technical strings, format specifiers should typically be kept exactly as they appear in the source unless they need to be reordered.

Correct translation:
无法使用版本 3 交易花费版本为 %d 的未确认预选输入。
```

<!-- cache_translation_check_cmn_f9b38ca6e6771122f4b6e345f173a375d4a3ec7c96cf90ece271263bcdc608a8 -->
```
        <source>Can't spend unconfirmed version 3 pre-selected input with a version %d tx</source>
        <translation>无法使用版本1%d交易花费未确认版本3的预选输入。</translation>
    
ERR
The format specifier `%d` is preceded by an incorrect character '1' in the translation, which is not present in the source and changes the meaning.

Correct translation:
无法使用版本 %d 交易花费未确认的版本 3 预选输入。
```

<!-- cache_translation_check_cmn_1d81021bd0f5e08586ea41fd27117444164eb2a4027d5da2c4780a799bdfbce5 -->
```
        <source>Could not top up scriptPubKeys</source>
        <translation>无法补充脚本公钥</translation>
    
ERR
The term “脚本公钥” is nonstandard and potentially misleading; the commonly accepted translation for scriptPubKey is “公钥脚本”.

Correct translation:
无法补充公钥脚本
```

<!-- cache_translation_check_cmn_ba4b31fafa76b68ee6fefc8e8b4a7ed3d6fda25fd4bbf4dacf08fa9950112849 -->
```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
ERR
The translation is missing the part "expected %s", and the wording is a bit awkward. Also, spacing between %s and surrounding text is unclear and may cause formatting issues.

Correct translation:
錯誤：轉存檔案的校驗和不匹配。計算值為 %s，預期為 %s
```

<!-- cache_translation_check_cmn_e99dedaf3bcb0124644a867cc5bf8c595facdc7958e168c4eb407adc3aacf17b -->
```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
ERR
There is a typo in the translation: "unit32_t" should be "uint32_t". Also, there should be a space between "版本号" and "%u" to match formatting conventions, since "%u" is a standalone variable.

Correct translation:
错误：无法把版本号 %u 作为uint32_t解析
```

<!-- cache_translation_check_cmn_bfba5479a7879ceb3a8fe1594b0469d71773b62d6ea3df387a6f180158c2e8e0 -->
```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
ERR
There are two issues: 
1. The format specifier %s is misplaced at the beginning, while in the source it appears at the end.
2. A colon is retained at the end whereas it was at the end of the English sentence, only after %s; it introduces unnecessary punctuation after the sentence.

Correct translation:
删除交易失败：%s
```

<!-- cache_translation_check_cmn_91b2d94152681a78c404c8e9dae514187a2b035ef69c33dc78b90f18caf7825f -->
```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
ERR
The translation is inaccurate. The source says "lower than the minimum fee rate setting", but the translation says "lower than the maximum fee rate setting" (最大 means maximum). It should be "最低" for minimum.

Correct translation:
手续费率 (%s) 低于最小手续费率设置 (%s)
```

<!-- cache_translation_check_cmn_31858be505051e38dd1b91b7fd358da6a776adc9de7310a3806b5d3ab32c3a70 -->
```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
ERR
The translation contains a double negative: "不不可为负数", which is incorrect in Chinese. It should be "交易金额不可为负数" or "交易金额不能为负数".

Correct translation:
交易金额不可为负数
```

<!-- cache_translation_check_cmn_3d9320bea10d5e3e022a19cfd842e427af4d3ea041c7f0b8f6e7b309e8193b04 -->
```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
ERR
The translation is inaccurate. The English phrase "change output" in the context of Bitcoin refers specifically to the transaction's "找零輸出" (change output), not "尋找零輸出" which literally means "searching for zero output". The word "尋找" (search) is incorrect here.

Correct translation:
交易找零输出项超出范围
```

<!-- cache_translation_check_cmn_76b1bd6861e77279c4c3f4a191a4d295d0696f1f0ea13e7ad0a7140d44da079c -->
```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
ERR
The translation incorrectly introduces an extra '1' before the format specifier '%s', which is not present in the original source. This is likely a typographical error. The rest of the translation is accurate, but the format specifier should match exactly.

Correct translation:
钱包文件创建失败：%s
```

<!-- cache_translation_check_cmn_e3222f6658880630ea81b0a0cd483e7c2b2346ce99656d5b087dfe9f4559eb98 -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>加载 %s时出错：钱包为传统钱包。请使用迁移工具（migratewallet RPC）迁移到描述符钱包。</translation>
    
ERR
Missing space around the format specifier causes a minor whitespace issue. It should be "加载 %s 时出错".

Correct translation:
加载 %s 时出错：钱包为传统钱包。请使用迁移工具（migratewallet RPC）迁移到描述符钱包。
```

<!-- cache_translation_check_cmn_7ac1efa37e812c3d7101f033238c56c685efb44247b49ad8368f92f5497fdb8a -->
```
        <source>Unrecognized descriptor found. Loading wallet %s

The wallet might have been created on a newer version.
Please try running the latest software version.
</source>
        <translation>发现无法识别的描述符。正在加载钱包 %s 

该钱包可能是在较新版本中创建的。 
请尝试运行最新的软件版本。
</translation>
    
ERR
There are trailing spaces after "%s" and after "创建的。" which are unnecessary whitespace issues.

Correct translation:
发现无法识别的描述符。正在加载钱包 %s

该钱包可能是在较新版本中创建的。
请尝试运行最新的软件版本。
```

<!-- cache_translation_check_cmn_3893aa5cc96d3a3e6fda580d5592a8e0694e08745e5bb4cb9823521e2db3de13 -->
```
        <source>Invalid -proxy address or hostname, ends with '=': '%s'</source>
        <translation>无效的 -proxy 地址或主机名，以“=”结尾：“%s”。</translation>
    
ERR
The translation adds an extra full stop at the end that is not present in the source, which can cause inconsistencies in UI strings.

Correct translation:
无效的 -proxy 地址或主机名，以“=”结尾：“%s”
```
</details>

Number of issues: 52.
