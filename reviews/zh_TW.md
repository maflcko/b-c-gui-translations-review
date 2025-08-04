# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh_TW</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh_TW%5D%20low%20quality)


```
        <source>Choose</source>
        <translation>選擇 (h)</translation>
    
YES, The translation is problematic because it adds an unnecessary parenthetical character "(h)" to the word "選擇". This looks like an incomplete or erroneous annotation. The correct translation should be "選擇".

YES, 翻譯有問題，因為它在「選擇」一詞中添加了一個不必要的括號字符「(h)」。這看起來像是一個不完整或錯誤的註釋。正確的翻譯應該是「選擇」。
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>輸入錢包的新密碼短語。&lt;br/&gt;請使用&lt;b&gt;個或10個以上隨機字符&lt;/b&gt;或&lt;b&gt;個8個以上單詞&lt;/b&gt;的密碼。</translation>
    
YES, The translation is problematic because it is missing numbers in the sentence. The source text specifies "ten or more random characters" and "eight or more words", but the translation incorrectly states "個或10個以上隨機字符" (characters or 10 or more random characters) and "個8個以上單詞" (words or 8 or more words).

NO
```

```
        <source>Error: %1</source>
        <translation>错误：%1</translation>
    
YES - The translation of "Error" is incorrect for Traditional Chinese. The correct translation is "錯誤".
Error: %1
```

```
        <source>Custom…</source>
        <translation>自定义...</translation>
    
YES, the translation uses simplified Chinese characters ("自定义") instead of traditional Chinese characters ("自訂").

YES, 自訂…
```

```
        <source>Manual</source>
        <extracomment>Peer connection type established manually through one of several methods.</extracomment>
        <translation>手冊</translation>
    
YES: The translation "手冊" (manual) is too literal and doesn't accurately convey the meaning of "Manual" in the context of Bitcoin peer connection. In this context, "manual" refers to a manual setup or configuration, not a physical manual.

Correct translation: 手動
```

```
        <source>Backup Wallet…</source>
        <translation>备份钱包(B)</translation>
    
YES - The character `b` in parentheses `(B)` is not a valid Chinese input method shortcut and should be removed. Also, the Chinese characters for "backup wallet" are incorrect.
Backup Wallet… - 備份錢包…
```

```
        <source>Change Passphrase…</source>
        <translation>修改密码(C)</translation>
    
YES, The translation is problematic because it uses Simplified Chinese characters ("修改密码") instead of Traditional Chinese characters. The correct Traditional Chinese characters are "更改密碼". Additionally, the format specifier "(C)" is included in the translation, which is likely intended to be a shortcut key indicator.

NO
```

```
        <source>Load PSBT from file…</source>
        <translation>从文件加载PSBT(L)...</translation>
    
YES, The translation is problematic because the character "从" is simplified Chinese, not traditional Chinese. Additionally, the trailing "(L)" is not present in the source text and seems to be an artifact or unnecessary addition.

NO, 从文件加载PSBT...
```

```
        <source>Close Wallet…</source>
        <translation>关闭钱包...</translation>
    
YES, The translation is incorrect. "关闭钱包..." is Mandarin Chinese. The correct Traditional Chinese translation is "關閉錢包...".
NO
```

```
        <source>Create Wallet…</source>
        <translation>创建钱包...</translation>
    
YES, The translation uses simplified Chinese characters ('创建') instead of traditional Chinese characters ('建立' or '創建').
建立錢包...
```

```
        <source>Processing blocks on disk…</source>
        <translation>处理磁盘上的区块...</translation>
    
YES - The translation uses Simplified Chinese characters, not Traditional Chinese characters. The correct translation for Traditional Chinese (zh_TW) is: 處理磁碟上的區塊...
```

```
        <source>Connecting to peers…</source>
        <translation>连到同行...</translation>
    
YES, The translation uses Simplified Chinese characters ("连") instead of the required Traditional Chinese ("連"). Furthermore, the term "同行" means "people in the same profession" and is an incorrect translation for "peers" in a P2P network context. The correct term would be "節點" (nodes) or "對等節點" (peer nodes).

Correct translation: 正在連接節點…
```

```
        <source>Open a wallet</source>
        <translation>打開一個錢包檔</translation>
    
YES, The translation "打開一個錢包檔" means "Open a wallet file". The original English text "Open a wallet" is more general and does not necessarily imply opening a file. In the context of Bitcoin, "Open a wallet" usually refers to accessing or loading a Bitcoin wallet, not specifically opening a file.

A more accurate translation would be "開啟錢包" or "打開錢包".

Correct translation: 開啟錢包
```

```
        <source>Hide</source>
        <translation>躲</translation>
    
YES, the translation is incorrect in the context of Bitcoin. "Hide" in this context refers to hiding an element on a user interface, not the verb "to hide" in the sense of concealment.

The correct translation should be:
<translation>隱藏</translation>
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES, The translation is incorrect and conveys the opposite meaning of the source text. The source text "Enable network activity" means to turn on network activity, but the translation "關閉網路紀錄" means "Close network activity".
NO, Enable network activity
```

```
        <source>Error: %1</source>
        <translation>错误：%1</translation>
    
YES - The translation of "Error" is incorrect for Traditional Chinese. The correct translation is "錯誤".
Error: %1
```

```
        <source>Copy label</source>
        <translation>复制和标签</translation>
    
YES, The translation is incorrect. The source text means to copy a label, not to copy and then label something.
The correct translation should be 複製標籤.
NO
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES, the translation is incorrect. The English phrase "Copy amount" translates to "複製金額" in Traditional Chinese, not "复制和数量" which means "copy and quantity".
NO
```

```
        <source>Create wallet failed</source>
        <translation>創建錢包失敗&lt;br&gt;</translation>
    
YES, The translation includes an unnecessary HTML line break tag.
創建錢包失敗
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>仅观察脚本已经被迁移到被命名为“%1”的新钱包中。</translation>
    
YES: The translation uses simplified Chinese characters ("仅", "被", "为") instead of traditional Chinese characters ("僅", "被", "為"). The translation is also unnatural and awkward.
The correct translation should be: 僅觀察腳本已遷移至名為「%1」的新錢包。
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
YES, The translation is missing the phrase "starting with the earliest transactions in %3". It also incorrectly parses the sentence structure, placing "%3" before "%4". The correct translation is:

當你點擊「確認」，%1會開始下載並處裡整個%4區塊鏈(大小:%2GB)，從%4剛推出時%3年的最早交易開始。
```

```
        <source>Map port using PCP or NAT-PMP</source>
        <translation>通过PCP或NAT-PMP映射端口。</translation>
    
YES
The translation is in Simplified Chinese, not Traditional Chinese as specified by 'zh_TW'.

Correct translation:
使用PCP或NAT-PMP映射連接埠
```

```
        <source>Connect through SOCKS5 proxy (default proxy):</source>
        <translation>透過 SOCKS5 代理伺服器連線(預設代理伺服器 C):</translation>
    
YES: The translation has an extraneous "C" at the end of "(預設代理伺服器 C)". It should be removed.
Correct translation: 透過 SOCKS5 代理伺服器連線(預設代理伺服器):
```

```
        <source>Proxy IP:</source>
        <translation>代理位址(I):</translation>
    
YES - The translation is problematic because "位址" means "address" and the "I" in parentheses is not part of the original source text and serves no purpose in the translation. The correct translation should be "代理 IP:".
代理 IP:
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>縮到最小到通知區而不是工作列(M)</translation>
    
YES - The translation contains an English letter "(M)" at the end of the sentence which is not present in the source text. This should be removed.
Minimize to the tray instead of the taskbar
縮小到通知區而不是工作列
```

```
        <source>Use separate SOCKS5 proxy to reach peers via Tor onion services:</source>
        <translation>使用個別的SOCKS＆5代理介由Tor onion服務到達peers：</translation>
    
YES, The translation has a formatting error. The number '5' after 'SOCKS' should not have an ampersand before it.
Using separate SOCKS5 proxy to reach peers via Tor onion services:
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>軟體未編譯外接簽證功能所需的軟體庫(外接簽證必須有此功能)</translation>
    
YES, The translation is problematic because it incorrectly translates "external signing support" and the overall sentence structure is awkward and grammatically incorrect in Traditional Chinese. The phrase "compiled without external signing support" means that the software was built without the capability for external signing. The current translation implies that the software libraries are missing, which is a different meaning.

A more accurate and natural translation would be:

Compiled without external signing support (required for external signing)
軟體未編譯支援外部簽名（外部簽名需要此功能）
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>所有只能看的地址還沒已熟成的挖出餘額</translation>
    
YES, The translation is problematic due to incorrect word order and unnatural phrasing.
Correct translation: 只能觀察的地址中尚未成熟的挖礦餘額
```

```
        <source>Could not sign any more inputs.</source>
        <translation>無法再簽名 input</translation>
    
YES, The translation is problematic because it is incomplete. The English word "inputs" should be translated to "inputs" in Chinese.
Could not sign any more inputs.
無法再簽名任何其他 inputs。
```

```
        <source>Peers</source>
        <translation>節點(P)</translation>
    
YES
The translation adds an extraneous "(P)" which is not present in the source text and is not a standard or necessary addition in the context of Bitcoin peers in Traditional Chinese.

Correct translation:
節點
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES, The translation is not accurate and contains erroneous content. The source text "Hide Peers Detail" refers to hiding the details of peers on the Bitcoin network. The translation "隐藏其他人的详细信息" means "Hide other people's details," which is too general and does not specifically relate to the Bitcoin context of peers.

NO
```

```
        <source>Clear console</source>
        <translation>清主控台</translation>
    
YES, the translation has an error. The correct translation for "Clear console" in Traditional Chinese is "清除主控台".

The original translation "清主控台" is grammatically awkward and doesn't convey the intended meaning as clearly as the correct translation.

NO
```

```
        <source>Outbound Feeler: short-lived, for testing addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to test the aliveness of known addresses.</extracomment>
        <translation>Outbound Feeler: 用於短暫，暫時 測試地址</translation>
    
YES: The translation uses a possessive "用於短暫，暫時 測試地址" which is grammatically incorrect in Chinese. It should be "Outbound Feeler: 短暫、用於測試地址".

Outbound Feeler: 短暫、用於測試地址
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
YES - The translation is not accurate and uses "測試地址" (test address) which is not appropriate. The original text indicates "soliciting addresses" which means requesting addresses.
Outbound 地址取得: 短暫，用於索取地址
```

```
        <source>1 hour</source>
        <translation>1 小時(H)</translation>
    
YES: The "(H)" appended to "小時" is not a standard or necessary addition in Traditional Chinese for this context and can be considered erroneous. It's likely an artifact of automated translation or a misunderstanding of formatting.

Correct translation: 1 小時
```

```
        <source>1 year</source>
        <translation>1 年(Y)</translation>
    
YES - The translation incorrectly adds "(Y)" which is not present in the source text.
1 年
```

```
        <source>Node window - [%1]</source>
        <translation>节点窗口 - [%1]</translation>
    
YES - The translation uses simplified Chinese characters, but the target language is traditional Chinese (zh_TW).

Node window - [%1]
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
    
YES, the translation of "Scammers have been active, telling users to type commands here, stealing their wallet contents." is inaccurate and sounds unnatural. The phrase "騙子們很狡猾" (scammers are cunning) is not the best way to convey "scammers have been active". Also, "清空錢包" (emptying wallets) is too direct and the sentence structure is a bit awkward.

A more accurate and natural translation would be:
"警告：詐騙者活躍，指示用戶在此處輸入指令，以竊取其錢包內容。"

Here's the corrected translation:

歡迎來到 %1 RPC 控制台。
使用上與下箭頭以進行歷史導航，%2 以清除螢幕。
使用%3 和 %4 以增加或減少字體大小。
輸入 %5 以顯示可用命令的概覽。
查看更多關於此控制台的信息，輸入 %6。

%7警告：詐騙者活躍，指示用戶在此處輸入指令，以竊取其錢包內容。%8
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES, the translation is incorrect. The English phrase "Copy amount" translates to "複製金額" in Traditional Chinese, not "复制和数量" which means "copy and quantity".
NO
```

```
        <source>Generates a native segwit address (BIP-173). Some old wallets don't support it.</source>
        <translation>產生一個原生隔離見證Segwit 位址 (BIP-173) 。 被部分舊版錢包不支援。</translation>
    
YES, The translation is grammatically incorrect and awkward.
Correct translation: 產生一個原生隔離見證位址 (BIP-173)。部分舊版錢包可能不支援。
```

```
        <source>Send</source>
        <translation>付款(E)</translation>
    
YES - The translation is problematic because "付款(E)" includes an extraneous English letter "(E)" which is not present in the source text and is likely a remnant of an incorrect shortcut key translation.
The correct translation should be "付款".
```

```
        <source>Create Unsigned</source>
        <translation>Cr＆eate未簽名</translation>
    
YES: The translation uses incorrect characters. It should be "建立未簽名".
Cr＆eate未簽名
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES: The translation is grammatically incorrect and the phrasing "使用簽名。離線%1錢包或與PSBT相容的硬體錢包" is awkward. It also misses the "e.g." from the source.

請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用例如離線的 %1 錢包或支援 PSBT 的硬體錢包進行簽名。
```

```
        <source>Unsigned Transaction</source>
        <comment>PSBT copied</comment>
        <extracomment>Caption of "PSBT has been copied" messagebox</extracomment>
        <translation>未被簽名交易</translation>
    
YES, The translation is incorrect and misleading. "Unsigned Transaction" should be translated to "未簽署交易" or "未簽名交易" to accurately convey that the transaction has not yet been signed. The provided translation "未被簽名交易" implies that the transaction has been prevented from being signed, which is not the intended meaning.

Unsigned Transaction: 未簽署交易
PSBT copied: PSBT已複製
Caption of "PSBT has been copied" messagebox: 「PSBT已複製」訊息框的標題
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
YES, The Chinese translation is grammatically incorrect and awkward. The phrase "地址給" at the end is redundant and doesn't make sense in this context. A more natural and accurate translation would be:

將支付發送到此比特幣地址
```

```
        <source>Send</source>
        <translation>發</translation>
    
YES, The translation of "Send" to "發" is too brief and could be misinterpreted. In the context of Bitcoin transactions, a more appropriate translation would be "發送" or "傳送".

NO
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1 次/未確認</translation>
    
YES: The translation implies that "%1" is the number of confirmations, but the English source "%1/unconfirmed" means that "%1" is the number of confirmations and it is *not* yet confirmed. The word "unconfirmed" should be part of the translation. The correct translation should be "%1/未確認".
%1/未確認
```

```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>確認中(已經 %1 次，建議至少 %2 次)</translation>
    
YES, the translation is problematic because it incorrectly translates the English phrase "Confirming (%1 of %2 recommended confirmations)". The translated phrase "確認中(已經 %1 次，建議至少 %2 次)" implies that the process has already reached %1 confirmations and recommends at least %2 confirmations, which is a mistranslation of the original meaning.

A more accurate translation would be:
"確認中（%1 / %2 次建議確認）"
```

```
        <source>Range…</source>
        <translation>范围...</translation>
    
YES, The translation uses simplified Chinese characters instead of traditional Chinese characters. The correct translation using traditional Chinese characters is:
范围...
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES, the translation is incorrect. The English phrase "Copy amount" translates to "複製金額" in Traditional Chinese, not "复制和数量" which means "copy and quantity".
NO
```

```
        <source>Disk space for %s may not accommodate the block files. Approximately %u GB of data will be stored in this directory.</source>
        <translation>%s的硬碟空間可能無法容納區塊文件。 大約要在這個目錄中儲存 %uGB的數據。</translation>
    
YES - The translation for "block files" as "區塊文件" is not ideal. While understandable, a more common and accurate term in the context of Bitcoin would be "區塊資料" or "區塊資料檔". Additionally, there is a space between "%u" and "GB" in the translation which should not be there.

Corrected translation: "%s 的磁碟空間可能無法容納區塊資料。大約要在這個目錄中儲存 %u GB 的資料。"
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES, The translation is problematic because of the phrasing and word choice. "多數" should be "多個" and "TOR路由綁定位址" should be "onion 綁定位址". Also, "對自動建立的Tor服務用%s" is grammatically incorrect.

More than one onion bind address is provided. Using %s for the automatically created Tor onion service.
提供多個 onion 綁定位址。正在使用 %s 建立自動 Tor onion 服務。
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>這是您支付的最高交易手續費（除了正常手續費外），優先於避免部分花費而不是定期選取幣。</translation>
    
YES, The translation contains erroneous content. "avoid partial spend" and "regular coin selection" are translated incorrectly. "Avoid partial spend" should be translated as "避免找零" (avoiding change). "Regular coin selection" should be translated as "常規的幣組合選擇" (regular coin selection).

Correct translation:
這是您支付的最高交易手續費（除了正常手續費外），優先於避免找零而不是常規的幣組合選擇。
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>在該交易手續費率下，找零的零錢會因為少於零散錢的金額，而自動棄掉變成手續費</translation>
    
YES, The translation is problematic because it misinterprets the meaning of "dust" in the context of Bitcoin. In Bitcoin, "dust" refers to an amount of Bitcoin so small that it's not worth processing as a transaction. The provided translation incorrectly equates "dust" to "零散錢的金額" (the amount of loose change), which is not the intended meaning.

The correct translation should convey that if the change amount is smaller than a certain minimal value (dust limit), it can be discarded and added to the transaction fee.

Correct translation:
<translation>在該交易手續費率下，如果找零金額小於粉塵（極小量），您可以選擇棄掉找零，該金額將會被計入交易手續費。</translation>
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>不支援的類別限定日誌等級 %1$s=%2$s 。 预期参数 %1$s=&lt;category&gt;:&lt;loglevel&gt;。 有效的類別: %3$s 。有效的日誌等級: %4$s 。</translation>
    
YES, The word "预期参数" (expected parameters) is used incorrectly in the context of a logging level. It should refer to the expected format of the category and loglevel.

不支援的類別特定記錄層級 %1$s=%2$s。預期格式為 %1$s=&lt;category&gt;:&lt;loglevel&gt;。有效類別：%3$s。有效記錄層級：%4$s。
```

```
        <source>Warning: Private keys detected in wallet {%s} with disabled private keys</source>
        <translation>警告: 在不允許私鑰的錢包 {%s} 中發現有私鑰</translation>
    
YES, The translation is problematic because the Chinese phrasing is awkward and doesn't convey the intended meaning clearly. It sounds like it's saying that private keys are found *with* the disabled private keys, rather than *in* the wallet where private keys are supposed to be disabled.

A more accurate and natural translation would be:
警告：在已停用私鑰的錢包 {%s} 中偵測到私鑰
```

```
        <source>Error loading %s: Private keys can only be disabled during creation</source>
        <translation>載入 %s 時發生錯誤: 只有在造新錢包時能夠指定不允許私鑰</translation>
    
YES: The translation is problematic. The original English text states that private keys can only be disabled *during creation*. The Chinese translation says they can only be specified *when creating a new wallet*, which is not exactly the same and may lead to confusion. The phrase "不允許私鑰" (disallow private keys) is also a bit awkward. A more accurate translation would be:

載入 %s 時發生錯誤：私鑰只能在建立時停用
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
YES: The format specifier "%s" appears only once in the translation, while it appears twice in the source. The translation is also missing a placeholder for the "expected" checksum value.
Correct translation: 錯誤：轉存檔案的校驗和不匹配。計算得到 %s，預期得到 %s
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES, The translation is problematic because the format specifier '%s' is placed at the end of the sentence instead of after "wallet". This can lead to a grammatically incorrect or nonsensical output when the actual wallet name is inserted.

The correct translation should be:
"错误：无法将数据写入钱包 %s 的磁盘。"
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES, The translation has swapped the position of the format specifier and the trailing punctuation. The format specifier should be at the beginning of the sentence and the punctuation at the end.
%s移除交易时失败
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>%s=&lt;amount&gt;: '%s' 中指定了非法的金额 (必须至少达到 %s)</translation>
    
YES, the translation is problematic due to incorrect phrasing and word choice in Traditional Chinese. The phrase "非法的金额" (illegal amount) is not the most appropriate term here. A more accurate and natural translation would be "無效的金額" (invalid amount). Additionally, the structure feels a bit clunky.

Here's a breakdown and correction:

*   **" Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)"**
*   **Original Translation:** "%s=&lt;amount&gt;: '%s' 中指定了非法的金额 (必须至少达到 %s)"
*   **Problem:** "非法的金额" is less accurate than "無效的金額". The phrase "必须至少达到" is also a bit literal and could be more natural.
*   **Correct Translation:** "%s=&lt;amount&gt;: '%s' 中的金額無效 (必須至少為 %s)"

Therefore, the output should be:
YES, %s=&lt;amount&gt;: '%s' 中的金額無效 (必須至少為 %s)
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>錢包軟體會付多於最小轉發費用的手續費。</translation>
    
YES, The translation is problematic because it says "pay more than the minimum relay fee", which is the opposite of the source text. The correct translation should be "The wallet will avoid paying less than the minimum relay fee." which translates to "錢包軟體將避免支付少於最低轉發費用的手續費。"
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES: The translation uses "尋找零輸出項" which means "finding zero output item", whereas the source text means "transaction change output index". The correct translation for "transaction change output index" would be "交易找零輸出索引".
交易找零輸出索引超出範圍
```

```
        <source>Unknown change type '%s'</source>
        <translation>不明的找零位址類型 '%s'</translation>
    
YES, The translation incorrectly uses "找零位址" (change address) instead of "找零類型" (change type).
The correct translation is: 不明的找零類型 '%s'
```

```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>未知的交易已經有新規則激活 (versionbit %i)</translation>
    
YES, The translation contains erroneous content. The word "transaction" was added to the translation which is not present in the source text.

Correct translation: 未知的規則已啟用 (versionbit %i)
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES, The translation incorrectly adds a digit "1" before the format specifier "%s".
Correct translation: 钱包文件创建失败：%s
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>错误：无法添加仅观察交易%s到仅观察钱包</translation>
    
YES: The translation uses "错误" (cuòwù) for "Error" which is correct. However, it incorrectly translates "watchonly tx" to "仅观察交易" (jǐn guānchá jiāoyì) and "watchonly wallet" to "仅观察钱包" (jǐn guānchá qiánbāo). In the context of Bitcoin, "watchonly" refers to a wallet that can monitor transactions but cannot spend funds. A more accurate translation would be "仅监控" (jǐn jiānkòng) for "watchonly".

Corrected translation: 錯誤：無法將僅監控交易 %s 添加到僅監控錢包
```
</details>
