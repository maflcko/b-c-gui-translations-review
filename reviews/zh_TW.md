# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh_TW</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh_TW%5D%20low%20quality)


```
        <source>Choose</source>
        <translation>選擇 (h)</translation>
    
YES  
The translation includes an unnecessary "(h)" which is not present in the source text and is inappropriate in this context. The correct translation should be simply:

選擇
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>輸入錢包的新密碼短語。&lt;br/&gt;請使用&lt;b&gt;個或10個以上隨機字符&lt;/b&gt;或&lt;b&gt;個8個以上單詞&lt;/b&gt;的密碼。</translation>
    
YES  
The translation is problematic and unclear, especially the parts "個或10個以上隨機字符" and "個8個以上單詞" are incorrect and awkwardly phrased, with extra or misplaced "個" which makes no sense in context. The original means "ten or more random characters" and "eight or more words". The correct phrasing in Traditional Chinese should clearly indicate the quantity and unit properly without confusing extra characters.

Correct translation:  
輸入錢包的新密碼短語。&lt;br/&gt;請使用&lt;b&gt;十個或以上隨機字符&lt;/b&gt;，或&lt;b&gt;八個或以上單詞&lt;/b&gt;的密碼。
```

```
        <source>Error: %1</source>
        <translation>错误：%1</translation>
    
YES
The translation uses simplified Chinese characters ("错误") instead of traditional Chinese characters expected in zh_TW.

Correct translation:
錯誤：%1
```

```
        <source>Custom…</source>
        <translation>自定义...</translation>
    
YES
The translation uses Simplified Chinese ("自定义") instead of Traditional Chinese. Also, the ellipsis character should be consistent: the source uses the single character ellipsis "…", while the translation uses three periods "...".

Correct translation:
自訂…
```

```
        <source>Backup Wallet…</source>
        <translation>备份钱包(B)</translation>
    
YES
The translation is in Simplified Chinese ("备份钱包"), but the requested language is Traditional Chinese (zh_TW). Also, the original text ends with an ellipsis ("…"), which is missing in the translation, and the extra "(B)" does not appear in the source and is unnecessary.

Correct translation:
備份錢包…
```

```
        <source>Change Passphrase…</source>
        <translation>修改密码(C)</translation>
    
YES  
The original text "Change Passphrase…" implies an action to change the passphrase, and the ellipsis suggests a dialog will follow. The translated text "修改密码(C)" means "Change password (C)" and includes "(C)" which seems to be a keyboard shortcut or an extraneous character not present in the source. Also, "密码" generally means "password," but "密碼" is the traditional Chinese form more appropriate for zh_TW, and "Passphrase" specifically means a sequence of words used as a password which could be translated as "密码短语" or "密碼短語". A better translation that matches the source style and terminology would be:

修改密碼短語…
```

```
        <source>Load PSBT from file…</source>
        <translation>从文件加载PSBT(L)...</translation>
    
YES  
The translation uses simplified Chinese characters ("从文件加载PSBT(L)...") instead of traditional Chinese characters suitable for zh_TW. Also, the English ellipsis "…" is a single character and should be preserved instead of using "(L)...". The "(L)" in the translation appears to be an erroneous addition and is not in the source text. It likely comes from a misunderstanding or a placeholder that should be removed.

Correct translation:  
從文件載入PSBT…
```

```
        <source>Close Wallet…</source>
        <translation>关闭钱包...</translation>
    
YES
The translation uses simplified Chinese characters (关闭钱包) instead of traditional Chinese characters used in zh_TW. Also, the ellipsis in the source is a single Unicode character (…) but the translation uses three periods (...), which although not incorrect, is inconsistent formatting.

Correct translation:
關閉錢包…
```

```
        <source>Create Wallet…</source>
        <translation>创建钱包...</translation>
    
YES  
The translation uses Simplified Chinese characters ("创建钱包") instead of Traditional Chinese ("建立錢包") as typically used in zh_TW. Also, the ellipsis should use the proper character "…" instead of three periods "...".

Correct translation:  
建立錢包…
```

```
        <source>Processing blocks on disk…</source>
        <translation>处理磁盘上的区块...</translation>
    
YES
The translation is in Simplified Chinese (处理磁盘上的区块...) instead of Traditional Chinese as required for 'zh_TW'. Also, the ellipsis should be the proper Unicode character (…) rather than three periods.

Correct translation:
正在處理磁碟上的區塊…
```

```
        <source>Connecting to peers…</source>
        <translation>连到同行...</translation>
    
YES
The translation uses Simplified Chinese characters ("连到同行"), but the target language is Traditional Chinese for Taiwan ("zh_TW"). Additionally, the terminology "同行" (meaning "peers") is somewhat literal but not the most common term used in a Bitcoin context in Traditional Chinese.

A better Traditional Chinese translation would be:
"正在連接節點…"

Here, "節點" (nodes) or "節點對等方" (peer nodes) is commonly used in Bitcoin contexts, and the ellipsis is the correct character "…". Also, notice the spacing: no extra spaces needed.

Correct translation:
正在連接節點…
```

```
        <source>Open a wallet</source>
        <translation>打開一個錢包檔</translation>
    
YES  
The phrase "打開一個錢包檔" is somewhat unnatural in the context of Bitcoin wallets. The word "錢包檔" (wallet file) emphasizes the file rather than the wallet itself, which may confuse users as Bitcoin users generally refer to "錢包" (wallet) rather than a "錢包檔" (wallet file) when opening a wallet through the software interface. A more natural and commonly accepted translation is simply:  

Correct translation:  
打開錢包
```

```
        <source>Hide</source>
        <translation>躲</translation>
    
YES  
The translation "躲" means "to hide oneself" or "to hide from someone" and is generally used in the context of avoiding or hiding oneself physically. It is not an appropriate translation for the English UI term "Hide," which generally means to conceal or make an element not visible. A more appropriate translation for UI contexts is "隱藏."  

Correct translation:  
隱藏
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES  
The source text says "Enable network activity," which means to turn ON or activate network activity. However, the translation "關閉網路紀錄" means "Disable network logging," which is not only inaccurate but also changes the meaning to turning something OFF rather than ON.  
Correct translation:  
啟用網路活動
```

```
        <source>Error: %1</source>
        <translation>错误：%1</translation>
    
YES
The translation uses simplified Chinese characters ("错误") instead of traditional Chinese characters expected in zh_TW.

Correct translation:
錯誤：%1
```

```
        <source>Copy label</source>
        <translation>复制和标签</translation>
    
YES  
The translation "复制和标签" means "Copy and label," which is incorrect and changes the meaning. The correct translation for "Copy label" should be "複製標籤".
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES  
The translation "复制和数量" means "copy and amount" which is incorrect and awkward for the English phrase "Copy amount". The correct translation should be concise and directly express "Copy amount" as a command or label. A proper translation is:  
"复制金额"
```

```
        <source>Create wallet failed</source>
        <translation>創建錢包失敗&lt;br&gt;</translation>
    
YES
The translation contains an unnecessary HTML line break tag "&lt;br&gt;" which is not present in the source text and could cause formatting issues.

Correct translation:
創建錢包失敗
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>仅观察脚本已经被迁移到被命名为“%1”的新钱包中。</translation>
    
YES  
The translation is in Simplified Chinese ("仅观察脚本...迁移到被命名为"), not Traditional Chinese as expected for 'zh_TW'. Additionally, the phrase "仅观察脚本" is unnatural and missing the concept of "watchonly scripts" (watch-only scripts). Also, "被命名为" is somewhat awkward; a better phrasing would be "名為" to suit Traditional Chinese style.

Correct translation:  
Watchonly scripts 已经被迁移到名為「%1」的新錢包中。
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
YES  
The translation has a typo and some formatting issues. The word "處裡" should be "處理" (correct character for "process"). Also, there are spacing inconsistencies: no space before the parenthesis and missing "當%4最初啟動時" at the end to fully reflect the source meaning. The full meaning of "%4 initially launched" is omitted. The translation could be improved for clarity and completeness.

Correct translation:  
當你點擊「確認」，%1會開始下載並處理整個%4區塊鏈（大小：%2 GB），起始於%4最初推出時%3年最早的交易。
```

```
        <source>Connect through SOCKS5 proxy (default proxy):</source>
        <translation>透過 SOCKS5 代理伺服器連線(預設代理伺服器 C):</translation>
    
YES  
The translation incorrectly adds "C" at the end, which does not appear in the source and seems like a typographical error. Also, there should be a space before the parenthesis for correct formatting and natural readability in Traditional Chinese.

Correct translation:  
透過 SOCKS5 代理伺服器連線（預設代理伺服器）：
```

```
        <source>Proxy IP:</source>
        <translation>代理位址(I):</translation>
    
YES  
The translation "代理位址(I):" incorrectly includes "(I)" which does not appear in the source text "Proxy IP:". Also, "位址" is acceptable but the more common traditional Chinese term for IP address is "位址" or "IP 位址" with a space. The "(I)" looks like an erroneous addition, possibly from a misinterpretation of "IP".

Correct translation:  
代理IP:
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>縮到最小到通知區而不是工作列(M)</translation>
    
YES  
The translation adds "(M)" at the end, which does not appear in the source text and may confuse users. Also, "縮到最小到通知區" is slightly awkward; "縮到通知區而非工作列" is smoother.  

Correct translation:  
縮到通知區而非工作列
```

```
        <source>Use separate SOCKS5 proxy to reach peers via Tor onion services:</source>
        <translation>使用個別的SOCKS＆5代理介由Tor onion服務到達peers：</translation>
    
YES  
The translation contains several issues:  
1. "SOCKS＆5" should be "SOCKS5" (the ampersand character is incorrect).  
2. "peers" should be translated into Chinese (like "節點" or "節點(peer)" ) rather than left in English.  
3. The phrase "via Tor onion services" is better rendered as "透過Tor onion服務" rather than "介由Tor onion服務".  
4. The spacing around terms could be improved; there should be no unnecessary spaces.  

Correct translation:  
使用獨立的 SOCKS5 代理來透過 Tor onion 服務連接節點：
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>軟體未編譯外接簽證功能所需的軟體庫(外接簽證必須有此功能)</translation>
    
YES
The translation contains awkward phrasing and an inaccurate choice of words:
- "軟體未編譯外接簽證功能所需的軟體庫" literally means "the software did not compile the libraries required for external signing," which is more technical than the original and adds "libraries" (軟體庫) that are not mentioned in the source.
- "簽證" usually means "visa" (for travel), not "signing." The correct term for "signing" in crypto or digital signature context is "簽名" or "簽署."
- The phrase lacks clarity and fluency compared to the source.

A better translation could be:

「未編譯外部簽名支援功能（外部簽名必須此功能）」

Or for improved clarity and formality:

「編譯時未包含外部簽名支援功能（外部簽名功能需要此支援）」

This preserves the original meaning, avoids introducing new concepts (like "library"), and uses the correct term for "signing."
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>所有只能看的地址還沒已熟成的挖出餘額</translation>
    
YES  
The translation contains grammar issues and awkward phrasing. The phrase "還沒已熟成" is incorrect (mixes "not yet" and "already"). Also, "只能看的地址" is a literal but somewhat unnatural translation of "watch-only addresses." A more natural term is "僅監視地址."  

Correct translation:  
「尚未成熟的僅監視地址中已挖出的餘額」
```

```
        <source>Could not sign any more inputs.</source>
        <translation>無法再簽名 input</translation>
    
YES  
The translation mixes English ("input") with Chinese, which is inconsistent and potentially confusing. The word "inputs" should be translated into Chinese correctly and consistently. A better translation would be:  
無法再簽署任何輸入。
```

```
        <source>Peers</source>
        <translation>節點(P)</translation>
    
YES  
The translation "節點(P)" adds a confusing and unexplained "(P)" which is not present in the source and could mislead the user. "Peers" in the context of Bitcoin network usually translates simply as "節點" or "節點數量" if referring to count. The added "(P)" is unnecessary and incorrect.  

Correct translation:  
節點
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES  
The English source "Hide Peers Detail" is concise and generally means "hide the details about peers." The translation "隐藏其他人的详细信息" translates back to "hide other people's detailed information," which is somewhat ambiguous and more specific than the original. The term "peers" in the Bitcoin context usually refers to network peers, not "other people" in general. Also, the original source uses "Detail" (singular), which might be better reflected by "详细信息" (detail/information) but the phrase "其他人" (other people) is not accurate.

A better translation would be:  
隐藏節點詳情  
or  
隱藏節點詳細信息  

Both mean "Hide Peers Detail" or "Hide Node Details," which is more accurate in this context.
```

```
        <source>Clear console</source>
        <translation>清主控台</translation>
    
YES  
The translation "清主控台" is unnatural and somewhat unclear in Traditional Chinese. The proper translation for "Clear console" in the context of software or Bitcoin UI would be "清除主控台" or simply "清除主控台畫面" to indicate clearing the console screen.

Correct translation:  
清除主控台
```

```
        <source>Outbound Feeler: short-lived, for testing addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to test the aliveness of known addresses.</extracomment>
        <translation>Outbound Feeler: 用於短暫，暫時 測試地址</translation>
    
YES
The translation contains unnecessary spacing and is somewhat awkward in phrasing. The phrase "用於短暫，暫時 測試地址" is redundant ("短暫" and "暫時" mean similar things), and there is an extra space before "測試地址".

A more natural and concise translation is:  
"Outbound Feeler：用於短暫測試地址的連線"

This preserves the meaning clearly and fixes spacing issues.
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
YES  
The translation is somewhat inaccurate and awkward. "Outbound Address Fetch" should be translated as "發送端地址提取" or "出站地址提取" to convey the meaning of outbound network communication. The phrase "short-lived, for soliciting addresses" is mistranslated as "用於短暫，暫時 測試地址," which implies "used for briefly, temporarily testing addresses" instead of "used for a short duration to solicit (request) addresses."

A better translation would be:  
"出站地址提取：短暫連線，用於請求地址"
```

```
        <source>1 hour</source>
        <translation>1 小時(H)</translation>
    
YES  
The original source "1 hour" is simply a duration without any abbreviations. The translation "1 小時(H)" adds an unnecessary "(H)" which is not present in the source and could cause confusion or inconsistency. The correct translation should directly represent the time duration without extra characters:

Correct translation:  
1 小時
```

```
        <source>1 year</source>
        <translation>1 年(Y)</translation>
    
YES  
The translation includes an unnecessary "(Y)" which is not present in the source and can cause confusion. The correct translation should simply be "1 年" without the added "(Y)".

Correct translation:  
1 年
```

```
        <source>Node window - [%1]</source>
        <translation>节点窗口 - [%1]</translation>
    
YES
The translation uses Simplified Chinese characters "节点窗口" instead of Traditional Chinese characters expected in 'zh_TW'.  
Correct translation: 節點視窗 - [%1]
```

```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>歡迎來到 %1 RPC 控制台。
使用上與下箭頭以進行歷史導航，%2 以清除螢幕。
使用%3 和 %4 以增加或減少字體大小。
輸入 %5 以顯示可用命令的概覽。
查看更多關於此控制台的信息，輸入 %6。

%7 警告：騙子們很狡猾，告訴用戶在這裡輸入命令，清空錢包。 不要在不完全了解一個命令的後果的情況下使用此控制台。%8</translation>
    
YES
The translation is mostly accurate, but there are minor issues with spacing and phrasing that affect readability and naturalness in Traditional Chinese:

1. There should be no space after %7 before "警告".
2. The phrase "騙子們很狡猾" is less natural and somewhat informal; "騙子們一直活躍" or "詐騙者一直活躍" is closer to the original.
3. The phrase "清空錢包" is stronger than the original "stealing their wallet contents". Better phrasing is "盜取他們錢包的內容" to reflect theft rather than wiping.
4. The sentence "不要在不完全了解一個命令的後果的情況下使用此控制台。" can be smoothed as "請勿在不了解命令後果的情況下使用此控制台。"
5. The spacing around "使用%3 和 %4" should be consistent with other lines: either no space before and after %, or consistent spacing around characters.

Correct translation:

歡迎來到 %1 RPC 控制台。  
使用上與下箭頭以瀏覽歷史記錄，%2 可清除螢幕。  
使用 %3 和 %4 以增加或減少字體大小。  
輸入 %5 以顯示可用命令的概覽。  
查看更多關於此控制台的資訊，請輸入 %6。  

%7警告：詐騙者一直活躍，誘使用戶在此輸入命令，盜取他們錢包的內容。請勿在不了解命令後果的情況下使用此控制台。%8
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES  
The translation "复制和数量" means "copy and amount" which is incorrect and awkward for the English phrase "Copy amount". The correct translation should be concise and directly express "Copy amount" as a command or label. A proper translation is:  
"复制金额"
```

```
        <source>Generates a native segwit address (BIP-173). Some old wallets don't support it.</source>
        <translation>產生一個原生隔離見證Segwit 位址 (BIP-173) 。 被部分舊版錢包不支援。</translation>
    
YES
The translation has unnecessary spacing before the period and awkward sentence structure in the second sentence. A more natural and grammatically correct translation would be:

產生一個原生隔離見證 Segwit 位址（BIP-173）。部分舊版錢包不支援它。
```

```
        <source>Send</source>
        <translation>付款(E)</translation>
    
YES  
The translation "付款(E)" adds an extraneous "(E)" which is not present in the source and may confuse users. The source word "Send" is best translated simply as "發送" or "送出" in the context of Bitcoin transactions rather than "付款" (which means "pay"). Also, "付款" implies "make a payment" rather than the general action "Send."

Correct translation:  
發送
```

```
        <source>Create Unsigned</source>
        <translation>Cr＆eate未簽名</translation>
    
YES
The translation contains Latin characters "Cr＆eate" mixed with Chinese, which is incorrect and unprofessional. The ampersand is a fullwidth character and should not be there. A proper translation for "Create Unsigned" in Traditional Chinese would be:

建立未簽名
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES
The translation is grammatically incomplete and awkward because the part after "然後使用簽名。" ("then use the signature.") is not properly connected to the previous sentence, and the order of "離線%1錢包或與PSBT相容的硬體錢包" is separated improperly. The original means "then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet," but the translation breaks the flow.

Correct translation:
請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用例如離線%1錢包或與PSBT相容的硬體錢包對交易進行簽名。
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
YES  
The translation is awkward and does not flow naturally in Chinese. It improperly splits the sentence and adds an unnecessary particle "給" at the end, making it sound unnatural. A better and clearer translation would be:  
將支付發送到的比特幣地址 → 收款的比特幣地址  
或者更完整自然些：  
接收付款的比特幣地址  
Correct translation:  
接收付款的比特幣地址
```

```
        <source>Send</source>
        <translation>發</translation>
    
YES  
The translation "發" (which means "send out", "issue", or "emit") is not commonly used alone to represent the action "Send" in the context of Bitcoin transactions or UI buttons in Traditional Chinese (Taiwan). A more accurate and natural translation for "Send" in this context is "發送" or simply "送出".  

Correct translation:  
發送
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1 次/未確認</translation>
    
YES  
The translation "%1 次/未確認" is problematic because the English source "%1/unconfirmed" indicates a status related to confirmation blocks, not a count of times. The character "次" means "times" or "occurrences," which could mislead users to think it is a number of attempts or events rather than confirmation status. The correct translation should preserve "%1" followed by "未確認" (unconfirmed) without "次."

Correct translation:  
%1/未確認
```

```
        <source>Range…</source>
        <translation>范围...</translation>
    
YES
The translation uses Simplified Chinese characters "范围" and an ellipsis represented by three periods "...", which is inconsistent with Traditional Chinese and common typographic norms in 'zh_TW'. In Traditional Chinese, "range" should be translated as "範圍" and the ellipsis should use a proper Unicode ellipsis character "…", not three dots.

Correct translation: 範圍…
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES  
The translation "复制和数量" means "copy and amount" which is incorrect and awkward for the English phrase "Copy amount". The correct translation should be concise and directly express "Copy amount" as a command or label. A proper translation is:  
"复制金额"
```

```
        <source>Disk space for %s may not accommodate the block files. Approximately %u GB of data will be stored in this directory.</source>
        <translation>%s的硬碟空間可能無法容納區塊文件。 大約要在這個目錄中儲存 %uGB的數據。</translation>
    
YES
There is a whitespace formatting issue in the translation. The second sentence has an extra space before "大約" and there should be a space between "%u" and "GB" to match the source style and for better readability.

Correct translation:  
%s的硬碟空間可能無法容納區塊文件。大約要在這個目錄中儲存 %u GB 的數據。
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES  
The translation has issues with clarity and completeness. It does not fully convey the meaning of "More than one onion bind address is provided," and the latter part "Using %s for the automatically created Tor onion service." is incomplete and awkward.

Correct translation:  
提供了多個 onion 綁定位址。已使用 %s 作為自動建立的 Tor onion 服務的位址。
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>這是您支付的最高交易手續費（除了正常手續費外），優先於避免部分花費而不是定期選取幣。</translation>
    
YES  
The translation has some wording issues and unclear phrasing. The phrase "優先於避免部分花費而不是定期選取幣" is confusing and does not correctly convey "to prioritize partial spend avoidance over regular coin selection." The concept of prioritizing avoiding partial spends instead of regular coin selection should be more clearly and accurately expressed.

Correct translation:  
這是您支付的最高交易手續費（在正常手續費之外），用以優先避免部分花費，而非採用常規硬幣選擇。
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>不支援的類別限定日誌等級 %1$s=%2$s 。 预期参数 %1$s=&lt;category&gt;:&lt;loglevel&gt;。 有效的類別: %3$s 。有效的日誌等級: %4$s 。</translation>
    
YES
The translation mixes traditional Chinese ("不支援的類別限定日誌等級") with simplified Chinese ("预期参数"), which is inconsistent for zh_TW, which should use traditional Chinese throughout. Also, there are unnecessary spaces before some full stops and after some colons which break formatting consistency.

Correct translation:
不支援的類別限定日誌等級 %1$s=%2$s。預期 %1$s=&lt;category&gt;:&lt;loglevel&gt;。有效的類別：%3$s。有效的日誌等級：%4$s。
```

```
        <source>Error loading %s: Private keys can only be disabled during creation</source>
        <translation>載入 %s 時發生錯誤: 只有在造新錢包時能夠指定不允許私鑰</translation>
    
YES  
The translation is slightly inaccurate and less literal, which may cause misunderstanding. The original text means "Error loading %s: Private keys can only be disabled during creation," indicating an error with loading something (%s), and clarifying that disabling private keys is only possible during creation. The current translation "載入 %s 時發生錯誤: 只有在造新錢包時能夠指定不允許私鑰" uses "造新錢包" ("create new wallet") which deviates from the source that does not specify "wallet," and phrases "指定不允許私鑰" which is unnatural.

A better translation would be:  
載入 %s 時發生錯誤：私鑰只能在建立時被禁用
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
YES  
The translation is incomplete and does not fully convey the original message. It lacks the "expected %s" part and the sentence structure is awkward. Also, the format specifiers are not correctly positioned and it merges "%s計算得%s" ungrammatically.

Correct translation:  
錯誤：轉存檔案的校驗和不匹配。計算值為 %s，預期值為 %s。
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES  
The translation is inaccurate and awkward. The original English means "Unable to write data to disk for wallet %s", implying the disk belongs to the wallet or the wallet identifier is provided. However, the translation mixes the order and includes an unnecessary possessive "的钱包的磁盘%s" which is unnatural and confusing. The %s should directly follow "wallet" as an identifier. Also, it uses simplified Chinese characters ("错误" and "无法"), but the target language is Traditional Chinese (zh_TW). The translation should be in Traditional Chinese and preserve the format and meaning clearly.

Correct translation:  
錯誤：無法將資料寫入錢包 %s 的磁碟。
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES
The translation places the placeholder %s at the beginning, which differs from the source where %s is at the end of the sentence. Additionally, there is an unnecessary space before the colon and the phrasing is awkward for traditional Chinese. A more natural and accurate translation would be:

交易移除失敗: %s
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>錢包軟體會付多於最小轉發費用的手續費。</translation>
    
YES  
The translation changes the meaning. The source says the wallet will avoid paying *less* than the minimum relay fee, implying it won't pay fees below the minimum threshold. The translation implies the wallet *will pay more* than the minimum fee, which is not exactly the same and introduces a misleading nuance. A more accurate translation would preserve the idea of avoiding fees that are too low.

Correct translation:  
錢包軟體會避免支付低於最小轉發費用的手續費。
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES  
The translation is somewhat inaccurate and unclear. The English source refers to the "change output index" of a transaction being out of range. The translation "交易尋找零輸出項超出範圍" literally means "transaction searching zero output item out of range," which does not convey the meaning of the phrase.

A more accurate translation would be:  
交易找零輸出索引超出範圍
```

```
        <source>Unknown change type '%s'</source>
        <translation>不明的找零位址類型 '%s'</translation>
    
YES
The original English text refers to an "Unknown change type '%s'." The term "change" here means the type of change (amount returned in a Bitcoin transaction), not an "address." However, the translation wrongly includes "找零位址" ("change address"), which is incorrect and misleading.

Correct translation:
未知的找零類型 '%s'
```

```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>未知的交易已經有新規則激活 (versionbit %i)</translation>
    
YES
The phrase "未知的交易已經有新規則激活" incorrectly translates "Unknown new rules activated." It mistakenly refers to "unknown transactions" (未知的交易) instead of "unknown new rules." A more accurate translation would be:

未知的新規則被激活 (versionbit %i)
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES  
The translation contains an erroneous extra character '1' before the format specifier '%s'. The format specifier should be preserved exactly as in the source, without additional characters.

Correct translation:  
錢包文件創建失敗：%s
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>错误：无法添加仅观察交易%s到仅观察钱包</translation>
    
YES  
The translation uses simplified Chinese characters ("错误") instead of traditional Chinese characters which are standard in zh_TW. Also, there should be spaces around the format specifier %s to improve readability, consistent with typical Chinese usage for such technical messages.

Correct translation:  
錯誤：無法將僅觀察交易 %s 添加到僅觀察錢包
```
</details>
