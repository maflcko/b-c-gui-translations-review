# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh_HK</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh_HK%5D%20low%20quality)


```
        <source>New</source>
        <translation>新增 N</translation>
    
YES  
The translation includes an extraneous "N" which is not present in the source text and is unnecessary. The correct translation should simply be:  
新增
```

```
        <source>Copy</source>
        <translation>複製 C</translation>
    
YES
The translation includes an unnecessary and incorrect trailing " C" which does not appear in the source text. The correct translation should simply be:

複製
```

```
        <source>Close</source>
        <translation>關閉 l</translation>
    
YES
The translation contains an extraneous character "l" at the end, which is not part of the correct translation. The correct translation for "Close" is simply "關閉".

Correct translation:
關閉
```

```
        <source>Export</source>
        <translation>匯出 E</translation>
    
YES  
The translation "匯出 E" is problematic because the English word "Export" should be fully translated without adding extraneous characters like "E". The character "E" appears to be mistakenly included and is not appropriate in this context.

Correct translation:  
匯出
```

```
        <source>Delete</source>
        <translation>刪除 D</translation>
    
YES  
The translation contains an extraneous " D" at the end, which is not in the source text and appears to be a mistake or leftover from some editing process. The correct translation for "Delete" in traditional Chinese (Hong Kong) is simply:  
刪除
```

```
        <source>Choose</source>
        <translation>選擇 h</translation>
    
YES
The translation contains an extraneous "h" character which is not part of the original text and likely a typo.

Correct translation:
選擇
```

```
        <source>Copy Address</source>
        <translation>複製地址 C</translation>
    
YES
The translation includes an extraneous " C" at the end which is not present in the source text. This is likely a typographical error.

Correct translation:
複製地址
```

```
        <source>Copy Label</source>
        <translation>複製標記 L</translation>
    
YES  
The translation contains an extraneous "L" at the end which is not in the source text, making it inaccurate. Also, "Label" in this context (Bitcoin or UI) is usually translated as "標籤" rather than "標記". "複製標籤" is the more common and accurate translation for "Copy Label."

Correct translation:  
複製標籤
```

```
        <source>Edit</source>
        <translation>編輯 E</translation>
    
YES
The translation contains an unnecessary and incorrect trailing " E" which is not present in the source and likely erroneous.

Correct translation:
編輯
```

```
        <source>Continue</source>
        <translation>继续</translation>
    
YES
The translation uses Simplified Chinese ("继续"), while 'zh_HK' typically requires Traditional Chinese characters. The correct Traditional Chinese translation should be "繼續".
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>發生了內部錯誤%1 將嘗試安全地繼續。 這是一個意外錯誤，可以按如下所述進行報告。</translation>
    
YES  
The translation has spacing issues: there should be a space after "錯誤" before "%1" and no extra spaces after the period before "這是一個意外錯誤". Also, "意外錯誤" is slightly less natural than "意外錯誤" (acceptable), but "意外錯誤" is okay. The phrase "按如下所述進行報告" is acceptable but could be more natural as "按照以下說明報告".

Correct translation:  
發生了內部錯誤。%1 將嘗試安全地繼續。這是一個意外漏洞，可以按照以下說明進行報告。
```

```
        <source>Custom…</source>
        <translation>自定义...</translation>
    
YES
The translation uses simplified Chinese characters "自定义", which is more common in Simplified Chinese (zh_CN). The requested language variant is zh_HK (Traditional Chinese used in Hong Kong), so the phrase should be translated using Traditional Chinese characters. Additionally, the English ellipsis "…" should be preserved as the single character ellipsis (U+2026), not three periods "..." to maintain formatting consistency.

Correct translation:
自訂…
```

```
        <source>Manual</source>
        <extracomment>Peer connection type established manually through one of several methods.</extracomment>
        <translation>手册</translation>
    
YES  
The translation "手册" is more commonly used in Simplified Chinese and refers to a "manual" as a booklet or guide. In Traditional Chinese used in Hong Kong, "Manual" in the context of a peer connection type established manually should be translated as "手動" which means "manual" (done by hand or manually).  

Correct translation:  
手動
```

```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>触须</translation>
    
YES  
The translation "触须" literally means "tentacle" or "feelers" used in a biological sense, which may be confusing in the context of Bitcoin peer connections. A better translation should convey the idea of a short, testing connection, such as "探测连接" (probe connection) or "测试连接" (test connection).

Correct translation:  
探测连接
```

```
        <source>Overview</source>
        <translation>總覽 O</translation>
    
YES
The translation contains an extraneous character " O" after the correct word "總覽". This appears to be a typo or accidental insertion.

Correct translation:
總覽
```

```
        <source>Transactions</source>
        <translation>交易 T</translation>
    
YES
The translation contains an extraneous "T" character, which is not present in the source and is unnecessary.

Correct translation:
交易
```

```
        <source>Exit</source>
        <translation>結束 x</translation>
    
YES
The translation includes an extraneous " x" which is not present in the source and is unnecessary. The correct translation should simply be:

結束
```

```
        <source>About %1</source>
        <translation>關於 %1 A</translation>
    
YES  
The translation contains an erroneous extra character "A" at the end, which is not present in the source text and is unnecessary.

Correct translation:  
關於 %1
```

```
        <source>About Qt</source>
        <translation>關於 Qt Q</translation>
    
YES  
There is an erroneous extra "Q" at the end of the translation which is not in the source text and should be removed.

Correct translation:  
關於 Qt
```

```
        <source>Send</source>
        <translation>付款 S</translation>
    
YES  
The English source "Send" is translated as "付款 S", which is problematic because it includes an extraneous "S" at the end that should not be there. The correct translation for "Send" in this context (usually a button or command in a Bitcoin wallet) is simply "付款".  

Correct translation:  
付款
```

```
        <source>Receive</source>
        <translation>收款 R</translation>
    
YES
The translation "收款 R" includes an extraneous "R" which is not present in the source and is out of place. The correct and concise translation for "Receive" in the context of Bitcoin (e.g., receiving funds) is simply "收款".

Correct translation:
收款
```

```
        <source>Backup Wallet…</source>
        <translation>备份钱包(B)</translation>
    
YES  
The translation "备份钱包(B)" is problematic for Hong Kong Chinese (zh_HK) because it uses Simplified Chinese characters ("备份") rather than Traditional Chinese characters, which are standard in Hong Kong. Additionally, the "(B)" is unnecessary unless it relates to a mnemonic or shortcut that was present in the original source, which it is not — the source text is simply "Backup Wallet…", without any shortcut hint.

Correct translation:  
備份錢包…
```

```
        <source>Change Passphrase…</source>
        <translation>修改密码(C)</translation>
    
YES  
The English source "Change Passphrase…" is translated as "修改密码(C)". There are issues here:  
1. The ellipsis "…" is missing in the translation, which indicates that clicking this option would open a dialog or further steps. It should be kept or properly represented.  
2. The "(C)" looks like an access key or mnemonic indicator for keyboard shortcut, but it's not explained or standard in the original. If it's intentional, the English source should have a corresponding indication. Otherwise, it should be removed.  
3. The term "密码" (password) is a less accurate translation of "Passphrase" in the Bitcoin context, where "Passphrase" is often a longer or more complex security string, and may be better translated as "口令" or "密码短语". However, "密码" is commonly accepted as well. This is acceptable but could be improved.  

Suggested correct translation:  
"修改口令…" or "更改口令…"  

If the "(C)" is intended as shortcut it should be clarified in source or else removed. Also ensure the ellipsis is kept.  

Correct translation:  
修改口令…
```

```
        <source>Load PSBT from file…</source>
        <translation>从文件加载PSBT(L)...</translation>
    
YES
The ellipsis in the source "…" is a single Unicode character (U+2026), but the translation uses "(L)..." which is not appropriate and adds an unnecessary "(L)". The proper translation should maintain the ellipsis character and not add extra letters.

Correct translation:  
从文件加载PSBT…
```

```
        <source>Open URI…</source>
        <translation>打开URI...</translation>
    
YES
The ellipsis character in the source is a single Unicode ellipsis (…) which should be preserved in the translation for consistency and proper formatting. The translation uses three periods (...) instead, which is a formatting issue.

Correct translation:
打开URI…
```

```
        <source>Close Wallet…</source>
        <translation>关闭钱包...</translation>
    
YES
The translation uses simplified Chinese "关闭钱包..." rather than traditional Chinese, which is standard for 'zh_HK'. Also, the ellipsis in the source is the single-character horizontal ellipsis (…) U+2026, while the translation uses three dots "...", which is less correct in formal writing.

Correct translation:
關閉錢包…
```

```
        <source>Create Wallet…</source>
        <translation>创建钱包...</translation>
    
YES
The original English uses an ellipsis character (…) which is a single Unicode character (U+2026), but the translation uses three periods (...). Also, the ellipsis is better preserved for consistency and professional appearance.

Correct translation:
创建钱包…
```

```
        <source>File</source>
        <translation>檔案 F</translation>
    
YES
The translation contains a problematic addition of " F" which is not present in the source text and is unnecessary. The correct translation for "File" in Traditional Chinese (Hong Kong) is simply "檔案".

Correct translation:
檔案
```

```
        <source>Settings</source>
        <translation>設定 S</translation>
    
YES
The translation contains an extra character "S" which is unnecessary and incorrect.

Correct translation:
設定
```

```
        <source>Help</source>
        <translation>說明 H</translation>
    
YES
The translation includes an extra character "H" that is not present in the source text and is unnecessary. The correct translation for "Help" in traditional Chinese, suitable for Hong Kong, is simply:

說明
```

```
        <source>Connecting to peers…</source>
        <translation>连接到节点...</translation>
    
YES
The original English text uses an ellipsis character (…) (U+2026) to indicate an ongoing process, which is stylistically more appropriate than three ASCII dots. Also, the term "peers" in the Bitcoin context usually refers to other nodes or participants in the P2P network, and "节点" (nodes) is commonly used in traditional Chinese blockchain terminology.

However, the translation uses three ASCII periods "..." instead of the ellipsis character "…".

Correct translation:
连接到节点…
```

```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
YES  
The translation "付款地址(S)" is problematic. The original English text "Sending addresses" likely refers to addresses involved in sending Bitcoin, i.e., addresses from which Bitcoin is sent, not specifically "payment addresses". The addition of "(S)" is unexplained and out of place in the Chinese translation.

A more accurate translation would be:  
"發送地址"  

This directly translates "Sending addresses" without adding unnecessary parts or losing meaning.
```

```
        <source>Open a bitcoin: URI</source>
        <translation>打开bitcoin:开头的URI</translation>
    
YES  
The translation uses simplified Chinese characters ("打开") which are more common in mainland China (zh_CN), whereas 'zh_HK' translations typically use traditional Chinese characters. Also, "bitcoin" should be capitalized as "Bitcoin" to match proper noun usage in Chinese. A more standard and natural translation in Hong Kong traditional Chinese would be:  
**打開 Bitcoin: 開頭的 URI**
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES  
The translation "卸载钱包" means "uninstall wallet," which is not accurate for "Close wallet." The correct translation should convey simply closing or exiting the wallet, without implying removal or uninstallation.

Correct translation:  
关闭钱包
```

```
        <source>Migrate a wallet</source>
        <translation>迁移一个钱包</translation>
    
YES  
The provided translation "迁移一个钱包" is in Simplified Chinese, which is mainly used in Mainland China. The requested language is 'zh_HK' which refers to Traditional Chinese as used in Hong Kong. Additionally, it is better to avoid using the numeral "一个" explicitly unless necessary in this context. A more natural and accurate translation in Traditional Chinese (Hong Kong) for "Migrate a wallet" is:

錢包遷移
```

```
        <source>Hide</source>
        <translation>躲</translation>
    
YES  
The translation "躲" means "to hide" in the sense of physically hiding oneself or avoiding something, which is somewhat informal or casual. In UI contexts, "Hide" is more commonly translated as "隱藏" in traditional Chinese (Hong Kong), which clearly conveys the action of hiding a UI element or information.  

Correct translation:  
隱藏
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES  
The English source means to "Enable network activity," but the translation says "關閉網路紀錄," which means "Disable network logging," not enabling network activity. The translation is incorrect and misleading.

Correct translation:  
啟用網絡活動
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation "复制和数量" means "copy and amount," which is inaccurate given the source text "Copy amount." The correct translation should be concise and clearly convey the action "copy" related to "amount."

Correct translation:
复制金额
```

```
        <source>Lock unspent</source>
        <translation>锁定未花费(O)</translation>
    
YES  
The translation "锁定未花费(O)" mixes Simplified Chinese characters ("锁定") with an unclear "(O)" suffix, which is not explained and does not appear in the source text. In traditional Chinese used in Hong Kong, "锁定" should be written as "鎖定". The "(O)" is inappropriate here and likely a leftover or a typo.

Correct translation:  
鎖定未花費
```

```
        <source>Migrate wallet</source>
        <translation>迁移钱包</translation>
    
YES  
The translation "迁移钱包" is in Simplified Chinese, whereas 'zh_HK' is expected to use Traditional Chinese used in Hong Kong. The proper Traditional Chinese translation should be "遷移錢包".  

Correct translation:  
遷移錢包
```

```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>迁移钱包 &lt;b&gt;%1&lt;/b&gt;...</translation>
    
YES
The translation uses simplified Chinese characters ("迁移钱包") which is not appropriate for the zh_HK locale that typically uses Traditional Chinese characters. Also, the ellipsis used is three dots "..." instead of the proper Chinese ellipsis "…".

Correct translation:
遷移錢包 &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES  
The translation "卸载钱包" means "uninstall wallet," which is not accurate for "Close wallet." The correct translation should convey simply closing or exiting the wallet, without implying removal or uninstallation.

Correct translation:  
关闭钱包
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>启用修剪时，如果一个钱包被卸载太久，就必须重新同步整条区块链才能再次加载它。</translation>
    
YES  
The original English says "Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled." The translation uses "卸载" which means "uninstall," which is incorrect here. It should refer to "closing" or "shutting" the wallet, not uninstalling it. Also, the phrase "必须重新同步整条区块链才能再次加载它" is a bit verbose and adds the concept of "loading it again" which is not explicitly in the original.

A more accurate translation would be:  
“启用修剪功能时，钱包关闭时间过长可能需要重新同步整个区块链。”

This keeps the meaning accurate and concise.
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
YES  
The translation has minor issues:  
1. "確認" is acceptable but "確定" is more commonly used in Traditional Chinese UI for "OK".  
2. There should be a space after punctuation marks for readability, especially before the parenthesis.  
3. The phrase "處裡" is a typo; it should be "處理".  
4. The source text specifically says "starting with the earliest transactions in %3 **when %4 initially launched**," but the translation only says "從%3年最早的交易" ("from the earliest transactions in year %3") without mentioning the "initial launch" context for %4. This subtle nuance is important and should be included for accuracy.  

Correct translation:  
當你點擊「確定」後，%1會開始下載並處理完整的%4區塊鏈（大小：%2 GB），從%4首次啟動時%3的最早交易開始。
```

```
        <source>About %1</source>
        <translation>关于 %1</translation>
    
YES
The translation uses Simplified Chinese ("关于") instead of Traditional Chinese, which is the standard in the Hong Kong locale (zh_HK). The correct Traditional Chinese term for "About" in this context should be "關於".

Correct translation:
關於 %1
```

```
        <source>Start %1 on system login</source>
        <translation>系统登入时启动 %1 (S)</translation>
    
YES
The phrase "系统登入时启动 %1 (S)" includes an unnecessary "(S)" which does not appear in the source text and causes confusion. Also, the word order and terminology should better reflect natural and clear Traditional Chinese (Hong Kong) usage.

Correct translation:
系統登入時啟動 %1
```

```
        <source>Network</source>
        <translation>网络(N)</translation>
    
YES
The Chinese translation uses simplified Chinese characters "网络" which is more appropriate for Mainland China (zh_CN), not Hong Kong (zh_HK). In Hong Kong, Traditional Chinese characters should be used. The correct Traditional Chinese translation for "Network" is "網絡" without the "(N)" which appears unnecessary and not typically used as a mnemonic clue in HK usage.

Correct translation:
網絡
```

```
        <source>This allows you or a third party tool to communicate with the node through command-line and JSON-RPC commands.</source>
        <extracomment>Tooltip text for Options window setting that enables the RPC server.</extracomment>
        <translation>这允许作为用户的你或第三方工具通过命令行和JSON-RPC命令行与节点通信。</translation>
    
YES
The translation has a redundancy issue with "命令行和JSON-RPC命令行" which repeats "命令行" twice unnecessarily. The source mentions "command-line and JSON-RPC commands," so it should be "命令行和JSON-RPC命令" without repeating "命令行."

Correct translation:
這允許你或第三方工具通過命令行和JSON-RPC命令與節點通信。
```

```
        <source>Spend unconfirmed change</source>
        <translation>动用尚未确认的找零资金(S)</translation>
    
YES  
The translation adds "(S)" at the end, which does not appear in the source text and could confuse users. The phrase "找零资金" is fine but could be simplified to "找零" as commonly used in Hong Kong for "change" in Bitcoin contexts. Also, "动用" is a Mainland Chinese term; in Hong Kong, "使用" or "花费" is more common.  

Correct translation:  
使用未確認的找零
```

```
        <source>Allow incoming connections</source>
        <translation>允许传入连接(G)</translation>
    
YES
The translation "允许传入连接(G)" is in Simplified Chinese, while 'zh_HK' translation should be in Traditional Chinese. Also, the source text does not include the "(G)" at the end, which seems incorrect and unrelated. The correct Traditional Chinese translation for "Allow incoming connections" is:

允許傳入連線
```

```
        <source>Connect through SOCKS5 proxy (default proxy):</source>
        <translation>通过 SOCKS5 代理连接(默认代理):</translation>
    
YES
The translation uses simplified Chinese characters ("通过", "代理", "默认代理"), but 'zh_HK' typically uses traditional Chinese characters. Additionally, the punctuation should follow traditional Chinese usage, using full-width parentheses and colon.

Correct translation:  
透過 SOCKS5 代理連線（預設代理）：
```

```
        <source>Continue</source>
        <translation>继续</translation>
    
YES
The translation uses Simplified Chinese ("继续"), while 'zh_HK' typically requires Traditional Chinese characters. The correct Traditional Chinese translation should be "繼續".
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES
The translation contains a redundancy with "仅观察观察地址" ("watch-only watch address"), repeating "观察" twice, and the phrasing is unnatural. A proper translation would be:

您当前在仅观察地址中的余额
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>仅观察地址中尚未成熟的挖矿收入余额:</translation>
    
YES  
The translation includes a colon (:) at the end which is not present in the source text, adding unnecessary punctuation. Additionally, "仅观察地址" could be more naturally expressed as "僅監控地址" in Traditional Chinese used in Hong Kong. The phrase "挖矿收入余额" can be simplified to "挖礦餘額" to better fit the context.

Correct translation:  
僅監控地址中尚未成熟的挖礦餘額
```

```
        <source>Current total balance in watch-only addresses</source>
        <translation>仅观察地址中的当前总余额</translation>
    
YES  
The translation uses Simplified Chinese ("仅观察地址中的当前总余额") instead of Traditional Chinese typically used in the 'zh_HK' locale. Also, "watch-only addresses" should be translated as "僅監視地址" or "僅觀察地址" in Traditional Chinese, but "仅" is Simplified Chinese. The phrasing can also be made more natural.

Correct translation:  
"監視地址中的當前總餘額"
```

```
        <source>Save…</source>
        <translation>拯救...</translation>
    
YES
The translation "拯救..." means "rescue/save (a person in distress)" in a context unrelated to saving a file or data. The correct translation for "Save…" in the context of saving a file or data should be "儲存…".  
Correct translation: 儲存…
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>无法启动 bitcoin: 协议的“一键支付”处理程序</translation>
    
YES
The translation's meaning is somewhat altered and less natural. The source states that Bitcoin's "click-to-pay handler" cannot be started, but the translation reads as "Cannot start bitcoin: protocol's 'one-click payment' handler," which changes the nuance and adds "protocol" not present in the source.

A more accurate and natural translation would be:
無法啟動 bitcoin︰一鍵支付處理器
```

```
        <source>Copy Image</source>
        <translation>复制图像(C)</translation>
    
YES
The translation uses Simplified Chinese characters "复制图像" instead of Traditional Chinese characters, which are standard in Hong Kong. Also, the "(C)" shortcut hint is not localized or confirmed as correct in the context of zh_HK. Typically, shortcuts are either preserved as Latin letters or adapted meaningfully, but "(C)" may confuse users. A better translation in Traditional Chinese would be:

複製影像
```

```
        <source>Information</source>
        <translation>資訊 I</translation>
    
YES  
The translated text contains unnecessary and incorrect content. "資訊" alone is sufficient and correct for "Information" in Traditional Chinese used in Hong Kong. The added " I" is extraneous and likely a typo.

Correct translation:  
資訊
```

```
        <source>Memory Pool</source>
        <translation>内存池</translation>
    
YES
The translation uses Simplified Chinese characters "内存池," while for 'zh_HK' (Hong Kong), Traditional Chinese characters should be used. The correct Traditional Chinese translation is:

記憶池
```

```
        <source>(none)</source>
        <translation>(无)</translation>
    
YES
The translation uses simplified Chinese character "无" which is typical for Mainland China (zh_CN), whereas Hong Kong (zh_HK) typically uses traditional Chinese characters. The correct traditional Chinese translation for "(none)" is "(無)".

Correct translation:
(無)
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES
The translation "隐藏其他人的详细信息" literally means "Hide other people's detailed information," which introduces an unintended meaning. The source phrase "Hide Peers Detail" in the Bitcoin context likely refers to hiding the details about connected peers (nodes), not specifically "other people." 

A more accurate and context-appropriate translation would be:
"隐藏节点详情" or "隐藏节点详细信息"  

This preserves the technical meaning without implying "people."
```

```
        <source>Decrease font size</source>
        <translation>缩小字体大小</translation>
    
YES  
The translation "缩小字体大小" is in Simplified Chinese, which is generally used in Mainland China (zh_CN), not Traditional Chinese as used in Hong Kong (zh_HK). The appropriate translation in Traditional Chinese (zh_HK) should use Traditional characters and phrasing more common in Hong Kong.

Correct translation:  
縮小字體大小
```

```
        <source>Open</source>
        <translation>打开(O)</translation>
    
YES  
The translation uses Simplified Chinese characters "打开" instead of Traditional Chinese characters, which are standard in Hong Kong. Also, the "(O)" is inconsistent with typical Hong Kong software localization, where mnemonic hints are usually indicated without parentheses or by underlining the character directly.  

Correct translation:  
打開
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
YES  
The phrase "Outbound 地址取得: 用於短暫，暫時 測試地址" is awkward and inaccurate. The original English refers to a short-lived outbound connection used for soliciting (requesting) addresses from a peer, not "testing addresses." The Chinese translation also has spacing issues with an unnecessary full-width space after the comma.

A better translation would be:  
"Outbound 地址獲取：短暫， 用於向節點索取地址"  

This conveys the idea of a short-lived outbound operation for requesting addresses. Also note the use of a colon with proper spacing and removing redundant words.
```

```
        <source>Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>复制地址(C)</translation>
    
YES
The translation includes an unnecessary keyboard shortcut indicator "(C)" which is not present in the source text and may confuse users. The correct translation should simply be:

复制地址
```

```
        <source>Disconnect</source>
        <translation>断开(D)</translation>
    
YES  
The translation "断开(D)" is simplified Chinese and does not reflect the traditional Chinese characters typically used in the 'zh_HK' locale. Moreover, the inclusion of "(D)" is unclear and not standard for Hong Kong Chinese translations. Also, "断开" means "disconnect," but a more natural and commonly used term in traditional Chinese for "Disconnect" in a technical or networking context is "斷線" or "斷開連線."  

Correct translation:  
斷線
```

```
        <source>1 hour</source>
        <translation>1 小时(H)</translation>
    
YES  
The translation mixes Simplified Chinese "小时" (hour) with English "(H)" and is not typical for Traditional Chinese used in Hong Kong. The phrase in 'zh_HK' should use Traditional Chinese characters and avoid unnecessary English letters unless contextually required. Also, there is an unnecessary space between the number and the unit.

Correct translation:  
1 小時
```

```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>欢迎来到 %1 RPC 控制台。
使用上与下箭头以进行历史导航，%2 以清除屏幕。
使用%3 和 %4 以增加或减小字体大小。
输入 %5 以显示可用命令的概览。
查看更多关于此控制台的信息，输入 %6。

%7 警告：骗子们很活跃，告诉用户在这里输入命令，偷走他们钱包中的内容。不要在不完全了解一个命令的后果的情况下使用此控制台。%8</translation>
    
YES
The translation is mostly accurate, but there are a few minor issues:

1. The space after the style tag %7 before "警告" should be removed to match the source where %7 is directly attached without space.
2. The phrase "骗子们很活跃" is understandable but "骗子活动频繁" is a more natural way to say "Scammers have been active" in Traditional Chinese.
3. The phrase "告诉用户在这里输入命令" literally means "telling users to input commands here," which is slightly ambiguous. A more precise wording is "欺骗用户在此处输入命令" ("scamming users into typing commands here").
4. The usage of punctuation and overall structure are fine.

Corrected translation:

欢迎来到 %1 RPC 控制台。
使用上与下箭头以进行历史导航，%2 以清除屏幕。
使用%3 和 %4 以增加或减小字体大小。
输入 %5 以显示可用命令的概览。
查看更多关于此控制台的信息，输入 %6。

%7警告：骗子活动频繁，欺骗用户在此处输入命令，偷走他们钱包中的内容。不要在不完全了解一个命令的后果的情况下使用此控制台。%8
```

```
        <source>Copy message</source>
        <translation>复制消息(M)</translation>
    
YES
The translation "复制消息(M)" includes an unnecessary "(M)" which is not present in the source and may confuse the user. Also, there is no need for any letter in parentheses unless it is a shortcut key indicated in the source, which it is not.

Correct translation:
复制消息
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation "复制和数量" means "copy and amount," which is inaccurate given the source text "Copy amount." The correct translation should be concise and clearly convey the action "copy" related to "amount."

Correct translation:
复制金额
```

```
        <source>Custom change address</source>
        <translation>自定义找零地址</translation>
    
YES
The translation uses simplified Chinese characters "自定义找零地址," which is more appropriate for Mainland China (zh_CN). For Hong Kong (zh_HK), traditional Chinese characters should be used.

Correct translation:
自訂找零地址
```

```
        <source>Choose…</source>
        <translation>选择...</translation>
    
YES
The translation uses simplified Chinese "选择..." instead of traditional Chinese characters appropriate for 'zh_HK'. Also, the ellipsis character "…" should be preserved as in the source.

Correct translation:
選擇…
```

```
        <source>Enable Replace-By-Fee</source>
        <translation>启用手续费追加</translation>
    
YES  
The translation "启用手续费追加" is incorrect for "Enable Replace-By-Fee". It translates to "Enable additional fee" or "Enable fee increase", which does not accurately convey the Bitcoin Replace-By-Fee concept (the ability to replace an unconfirmed transaction by another with a higher fee).  

A better translation in traditional Chinese Hong Kong style would be:  
「啟用交易費率替換」  
or  
「啟用 Replace-By-Fee 功能」 (keeping the technical term)  

Preferred corrected translation:  
<translation>啟用交易費率替換</translation>
```

```
        <source>Send</source>
        <translation>发送(E)</translation>
    
YES  
The translation uses simplified Chinese characters (发送) instead of traditional Chinese characters expected in 'zh_HK'. Also, the addition of "(E)" is unexplained and possibly unnecessary or incorrect in this context, as there is no indication in the source for such a label or accelerator key.

Correct translation:  
傳送
```

```
        <source>Sign on device</source>
        <extracomment>"device" usually means a hardware wallet.</extracomment>
        <translation>在設備上簽證</translation>
    
YES
The translation "在設備上簽證" is problematic because "簽證" means "visa" (for travel), not "sign" in the context of digitally signing a transaction. The correct translation should use a term that reflects digital signing, such as "簽署".

Correct translation:
在設備上簽署
```

```
        <source>Create Unsigned</source>
        <translation>创建未签名交易(E)</translation>
    
YES
The translation adds "(E)" which is not present in the source and could confuse users. Also, "创建未签名交易" means "Create unsigned transaction," which is a more specific phrase than just "Create Unsigned." If the context only requires "Create Unsigned," the translation should be more literal.

Correct translation:
创建未签名
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES
The translation has formatting and grammatical issues. The phrase "然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。" is incomplete and awkward. The original English says: "... then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet." The translated sentence should clearly indicate the signing action is done with an offline %1 wallet or a PSBT-compatible hardware wallet.

Correct translation:
請檢查您的交易提案。這將產生部分簽名比特幣交易（PSBT），您可以儲存或複製該交易，然後使用例如離線%1錢包或與PSBT相容的硬體錢包進行簽名。
```

```
        <source>Confirm send coins</source>
        <translation>确认发币</translation>
    
YES  
The term "发币" implies "issuing coins," which is misleading in the Bitcoin context. The correct meaning is to "confirm sending coins/amount." A better translation should use language that clearly means "confirm sending coins" or "confirm sending Bitcoin."

Correct translation:  
确认发送币款
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
YES  
The translation is awkward and unnatural in Cantonese (Traditional Chinese as used in Hong Kong). The phrase "將支付發送到的比特幣地址給" is not fluent and feels incomplete or incorrectly ordered.

A more natural and accurate translation would be:  
"用作接收付款的比特幣地址"  
or  
"用於接收付款的比特幣地址"

These versions clearly convey "The Bitcoin address to send the payment to" in a way that is idiomatic for zh_HK.
```

```
        <source>Subtract fee from amount</source>
        <translation>從付款金額減去手續費(U)</translation>
    
YES
The translation "從付款金額減去手續費(U)" introduces "(U)" which is not present in the source text and appears to be extraneous or an error. Additionally, "付款金額" means "payment amount," which might be less accurate here than simply "金額" (amount), as the source is generic "amount" without specifying payment. A more natural and accurate translation in Traditional Chinese (Hong Kong) for "Subtract fee from amount" would be:

從金額中扣除手續費
```

```
        <source>Send</source>
        <translation>发送</translation>
    
YES  
The translation uses Simplified Chinese ("发送"), while the target language 'zh_HK' (Hong Kong Cantonese-based Traditional Chinese) generally uses Traditional Chinese characters. The correct Traditional Chinese translation for "Send" in this context should be "發送".  

Correct translation:  
<translation>發送</translation>
```

```
        <source>Verify Message</source>
        <translation>验证消息签名(M)</translation>
    
YES  
The translated text "验证消息签名(M)" means "Verify message signature (M)" rather than simply "Verify Message." The original source does not include "(M)" or specify "signature," so it adds extra and potentially confusing information which is inaccurate. Also, the translation uses Simplified Chinese characters ("验证"), while traditional Chinese should be used for Hong Kong ("驗證").

Correct translation:  
驗證訊息
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1 次/未確認</translation>
    
YES  
The translation "%1 次/未確認" is problematic because the English source "%1/unconfirmed" refers to a status showing the number of confirmations, where "%1" represents the count of confirmations (e.g., "0/unconfirmed" or "3/unconfirmed"). In the translation, the character "次" typically means "times" or "occurrences," which is redundant and misleading in this context because the source already uses "%1" as a count. The slash "/" is used in English to denote "x out of unconfirmed" or "x/unconfirmed" as a status.

A more accurate and natural translation would be "%1/未確認" without the "次" character, keeping the format specifier intact and consistent with Bitcoin terminology in traditional Chinese used in Hong Kong.

Correct translation:  
%1/未確認
```

```
        <source>Sent to</source>
        <translation>发送到</translation>
    
YES  
The translation "发送到" is simplified Chinese and more commonly used in Mainland China (zh_CN). For Hong Kong (zh_HK), the traditional Chinese form should be used. The appropriate traditional Chinese translation is "發送到".
```

```
        <source>Sent to</source>
        <translation>发送到</translation>
    
YES  
The translation "发送到" is simplified Chinese and more commonly used in Mainland China (zh_CN). For Hong Kong (zh_HK), the traditional Chinese form should be used. The appropriate traditional Chinese translation is "發送到".
```

```
        <source>Range…</source>
        <translation>范围...</translation>
    
YES  
The ellipsis in Chinese should use the proper Chinese ellipsis character '…' (six dots) instead of three periods '...'. Also, the translation uses simplified Chinese characters ("范围") instead of traditional Chinese characters used in Hong Kong.

Correct translation:  
範圍…
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation "复制和数量" means "copy and amount," which is inaccurate given the source text "Copy amount." The correct translation should be concise and clearly convey the action "copy" related to "amount."

Correct translation:
复制金额
```

```
        <source>Increase transaction fee</source>
        <translation>增加矿工费(F)</translation>
    
YES  
The translation "增加矿工费(F)" is in Simplified Chinese ("矿工费") rather than Traditional Chinese used in Hong Kong, where "礦工費" should be used. Also, "(F)" seems like a mnemonic or shortcut key hint in parentheses, which is present in the translation but not in the source text, so it should be removed unless originally present.  

Correct translation:  
增加交易手續費
```

```
        <source>Unable to decode PSBT from clipboard (invalid base64)</source>
        <translation>无法从剪贴板解码PSBT(Base64值无效)</translation>
    
YES
The translation uses simplified Chinese characters ("无法" and "剪贴板") instead of traditional Chinese characters commonly used in Hong Kong. It should use traditional characters and spacing should be adjusted for better readability.

Correct translation:
無法從剪貼板解碼 PSBT（Base64 值無效）
```

```
        <source>Export</source>
        <translation>匯出 E</translation>
    
YES  
The translation "匯出 E" is problematic because the English word "Export" should be fully translated without adding extraneous characters like "E". The character "E" appears to be mistakenly included and is not appropriate in this context.

Correct translation:  
匯出
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
YES  
The translation introduces unnecessary line breaks around the %s format specifiers causing formatting and readability issues. Also, the quotation marks around the format specifiers from the source are missing in the translation, which changes the meaning. Additionally, the whitespace before the translation should be removed.

Correct translation:  
錯誤：轉存檔案識別記錄不正確。獲得「%s」，預期「%s」。
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES  
The translation has issues with spacing and wording clarity. The original English means "More than one onion bind address is provided. Using %s for the automatically created Tor onion service." The translation separated the sentence awkwardly and missed connecting the clauses smoothly. Also, there's a stray space before the second part, and "TOR路由綁定位址" is somewhat unclear.

A better translation would be:  
"提供了多於一個洋蔥綁定位址。將使用 %s 作為自動建立的 Tor 洋蔥服務位址。"
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>這是您支付的最高交易手續費（除了正常手續費外），優先於避免部分花費而不是定期選取幣。</translation>
    
YES  
The translation is inaccurate and somewhat confusing, especially the phrase "優先於避免部分花費而不是定期選取幣" which does not clearly convey the meaning of prioritizing partial spend avoidance over regular coin selection. Also, "定期選取幣" is not a suitable translation for "regular coin selection."

Correct translation:  
這是您額外支付的最高交易手續費（除正常手續費外），用以優先避免部分花費，而非採用常規幣選擇。
```

```
        <source>%s is set very high! Fees this large could be paid on a single transaction.</source>
        <translation>%s被设置得很高! 这可是一次交易就有可能付出的手续费。</translation>
    
YES  
The translation is mostly understandable but uses simplified Chinese characters ("设置", "交易", "手续费") rather than traditional Chinese characters, which are standard in Hong Kong ('zh_HK'). Also, the spacing and punctuation do not reflect typical Hong Kong format (should use full-width punctuation or spacing consistent with traditional Chinese style). Furthermore, the translation slightly shifts the meaning: the source says "Fees this large could be paid on a single transaction," implying a warning about the fee amount, but the translation sounds more like a statement about possibly paying such a fee.

Correct translation in traditional Chinese for Hong Kong context:  
%s 設得太高！如此高額的手續費可能會用於單一交易。
```

```
        <source>Error: Duplicate descriptors created during migration. Your wallet may be corrupted.</source>
        <translation>错误：迁移过程中创建了重复的输出描述符。你的钱包可能已损坏。</translation>
    
YES  
The translation is in Simplified Chinese (简体中文), while 'zh_HK' should use Traditional Chinese appropriate for Hong Kong. Also, "错误" is Simplified Chinese, and "输出描述符" is a direct translation of "descriptors" but "描述符" is a somewhat technical term; however, it is commonly used and acceptable. The main issue is the script.

Correct translation (Traditional Chinese for zh_HK):  
錯誤：遷移過程中產生了重複的描述子。你的錢包可能已損壞。
```

```
        <source>Disk space is too low!</source>
        <translation>磁盘空间太低!</translation>
    
YES
The translation uses Simplified Chinese characters ("磁盘"), whereas the target language 'zh_HK' (Hong Kong) typically uses Traditional Chinese characters. The correct Traditional Chinese translation should be:
磁碟空間太低!
```

```
        <source>Error: Couldn't create cursor into database</source>
        <translation>错误: 无法在数据库中创建指针</translation>
    
YES
The translation uses Simplified Chinese ("错误" and "数据库") instead of Traditional Chinese, which is standard for 'zh_HK'. Also, "cursor" in database contexts is better translated as "游標" rather than "指针" (which typically means pointer in programming). 

Correct translation:
錯誤：無法在資料庫中建立游標
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
YES
The translation is incomplete and does not correctly convey the entire original message. The source states two checksum values: "Computed %s, expected %s", but the translation only mentions "%s計算得%s" which is unclear and incomplete.

Correct translation:
錯誤：轉存檔案的校驗和不匹配。計算值為 %s，預期值為 %s
```

```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
YES
The translation has a typo and minor spacing issues. "unit32_t" should be "uint32_t," and a space is recommended after the colon and before the version number specifier to improve readability.

Correct translation:
错误：无法把版本号 %u 解析为 uint32_t
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES  
The translation misplaces the format specifier %s and renders the sentence with incorrect word order and unnecessary characters, which affects clarity and correctness. The %s should directly follow "钱包" (wallet) to indicate which wallet caused the error, not "磁盘" (disk). Also, "磁盘的" is awkward; it should simply say writing data to disk, related to that wallet.

Correct translation:  
错误：无法将数据写入钱包 %s 的磁盘。
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES
The placement of the format specifier %s is incorrect, and there is an unnecessary colon and space at the end in the translation. The original English phrase indicates "Failure removing transaction: %s" where %s is the transaction identifier. The correct translation should maintain the same order and placement of %s immediately after "移除交易失败" without any trailing colon or extra space.

Correct translation:
移除交易失败: %s
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES
The translation incorrectly states "最大手续费率" (maximum fee rate) instead of "minimum fee rate." The source clearly mentions "minimum fee rate setting." 

Correct translation:
手续费率 (%s) 低于最低手续费率设置 (%s)
```

```
        <source>Not found pre-selected input %s</source>
        <translation>找不到预先选择输入%s</translation>
    
YES  
The translation uses Simplified Chinese characters ("预先选择") instead of Traditional Chinese, which is the correct script for 'zh_HK'. Also, a space is recommended before the format specifier "%s" for better readability in Chinese.

Correct translation:  
找不到預先選擇輸入 %s
```

```
        <source>Not solvable pre-selected input %s</source>
        <translation>无法求解的预先选择输入%s</translation>
    
YES
The translation uses Simplified Chinese characters ("无法求解的预先选择输入%s") instead of Traditional Chinese characters, which are standard for Hong Kong ("zh_HK"). Also, a minor spacing issue exists: there should be a space before the format specifier %s for readability.

Correct translation:
無法求解的預先選擇輸入 %s
```

```
        <source>Pruning blockstore…</source>
        <translation>修剪区块存储...</translation>
    
YES
The translation uses simplified Chinese characters (区块存储) instead of traditional Chinese characters used in Hong Kong. Also, the ellipsis in Chinese text is preferably the proper full-width character "…" instead of three periods.

Correct translation:
修剪區塊存儲…
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES  
The translation contains a double negative ("不不可"), which is incorrect and confusing in Chinese. The correct translation should be concise and clear without double negatives.

Correct translation:  
交易金额不得为负数
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES
The translation is slightly inaccurate and unclear. The phrase "transaction change output index out of range" refers to the index of the transaction's change output being out of the valid range. The current translation "交易尋找零輸出項超出範圍" translates roughly to "transaction search zero output item out of range," which is not accurate and introduces the word "尋找" (search) that does not exist in the source.

A more accurate translation would be:
交易找零輸出索引超出範圍
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES
The translation incorrectly adds a digit "1" before the format specifier "%s", which does not exist in the source text and will cause formatting errors.

Correct translation:
钱包文件创建失败：%s
```
</details>
