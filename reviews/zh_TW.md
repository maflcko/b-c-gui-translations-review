# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh_TW</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh_TW%5D%20low%20quality)


```
        <source>Choose</source>
        <translation>選擇 (h)</translation>
    
YES
The translation adds "(h)", which is not present in the English source. This is erroneous and may confuse users unless "(h)" is a required accelerator/hotkey explicitly stated elsewhere. If there is no contextual justification, this is unwanted content.

Correct translation:
選擇
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>輸入錢包的新密碼短語。&lt;br/&gt;請使用&lt;b&gt;個或10個以上隨機字符&lt;/b&gt;或&lt;b&gt;個8個以上單詞&lt;/b&gt;的密碼。</translation>
    
YES
The translation is problematic. The order and structure of the message are garbled, and the numbers (ten/eight) are transposed and inserted incorrectly. The measure words “個” are placed before numbers, making it awkward. The instruction about using 'ten or more random characters' or 'eight or more words' is not clear.

Correct translation:
輸入錢包的新密碼短語。&lt;br/&gt;請使用&lt;b&gt;十個以上的隨機字符&lt;/b&gt;，或&lt;b&gt;八個以上的單字&lt;/b&gt;作為密碼。
```

```
        <source>Error: %1</source>
        <translation>错误：%1</translation>
    
YES
The translation uses simplified Chinese "错误" instead of the traditional Chinese "錯誤" used in 'zh_TW'.

Correct translation:
錯誤：%1
```

```
        <source>Custom…</source>
        <translation>自定义...</translation>
    
YES
The translation uses the simplified Chinese term "自定义" instead of the Traditional Chinese term. Also, the ellipsis should be the full-width "…" as in the source, not three periods.

Correct translation:
自訂…
```

```
        <source>Backup Wallet…</source>
        <translation>备份钱包(B)</translation>
    
YES
The translation is problematic:
1. It uses Simplified Chinese characters ("备份钱包") instead of Traditional Chinese ("備份錢包").
2. The "(B)" is an unnecessary shortcut indicator that does not appear in the original string.
3. The ellipsis in the source is the Unicode character U+2026, but it is missing in the translation.

Correct translation:
備份錢包…
```

```
        <source>Change Passphrase…</source>
        <translation>修改密码(C)</translation>
    
YES
The translation uses "密码", which is the simplified Chinese term for "password". The traditional Chinese term should be "密碼". Also, the original source is "Change Passphrase…", which should be translated accurately as "更改密語…" or "更改通行密語…". "修改密碼(C)" is neither a faithful translation nor is the hotkey indicator "(C)" present in the original.

Correct translation:
更改密語…
```

```
        <source>Load PSBT from file…</source>
        <translation>从文件加载PSBT(L)...</translation>
    
YES
The translation uses Simplified Chinese ('从文件加载PSBT(L)...') rather than Traditional Chinese as used in 'zh_TW'. Also, the '(L)' is not present in the source, nor is it standard in such translations. The ellipsis character is correct, but spacing and stylistic conventions should align with Traditional Chinese UI.

Correct translation:
從檔案載入 PSBT…
```

```
        <source>Close Wallet…</source>
        <translation>关闭钱包...</translation>
    
YES
The translation is in Simplified Chinese ("关闭钱包..."), not Traditional Chinese as used in 'zh_TW'. Also, the ellipsis should use the correct Chinese or Unicode style, and in Traditional Chinese, "關閉" is used instead of "关闭".

Correct translation:
關閉錢包…
```

```
        <source>Create Wallet…</source>
        <translation>创建钱包...</translation>
    
YES
The translation uses Simplified Chinese ("创建钱包...") instead of Traditional Chinese, and the ellipsis is represented with three dots ("...") instead of the single ideographic ellipsis character or three dots as commonly used in Traditional Chinese.

Correct translation:
建立錢包…
```

```
        <source>Processing blocks on disk…</source>
        <translation>处理磁盘上的区块...</translation>
    
YES
The translation uses Simplified Chinese characters ("处理" and "磁盘") instead of Traditional Chinese characters appropriate for 'zh_TW'. Also, the ellipsis "..." should preferably be the full-width "…" for consistency with the source.

Correct translation:
處理磁碟上的區塊…
```

```
        <source>Connecting to peers…</source>
        <translation>连到同行...</translation>
    
YES
The translation uses Simplified Chinese characters ("连" and "同行") instead of Traditional Chinese as required for 'zh_TW'. Additionally, the ellipsis character "..." is used rather than the more typographically correct "…" as in the source.

Correct translation:
連接到節點…
```

```
        <source>Open a wallet</source>
        <translation>打開一個錢包檔</translation>
    
YES
The translation uses "錢包檔" which translates to "wallet file", but the original English phrase is "Open a wallet", which refers to opening a wallet in general, not specifically a wallet file. The word "檔" (file) is added unnecessarily.

Correct translation:
打開錢包
```

```
        <source>Hide</source>
        <translation>躲</translation>
    
YES
The translation "躲" means "to hide" in the sense of "to physically hide oneself", not in the sense of "hide" as a user interface action (e.g., hiding a window or element). The correct translation for the UI action "Hide" in Traditional Chinese is "隱藏".

Correct translation:
隱藏
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES  
The translation is incorrect. "Enable network activity" means to allow network operations, but the provided translation "關閉網路紀錄" means "Turn off network record/log," which has the opposite meaning.  

Correct translation:  
啟用網路活動
```

```
        <source>Error: %1</source>
        <translation>错误：%1</translation>
    
YES
The translation uses simplified Chinese "错误" instead of the traditional Chinese "錯誤" used in 'zh_TW'.

Correct translation:
錯誤：%1
```

```
        <source>Copy label</source>
        <translation>复制和标签</translation>
    
YES
The translation is problematic. The Chinese phrase "复制和标签" means "Copy and label," which incorrectly adds the conjunction "and" and changes the meaning.

Correct translation:
複製標籤
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation is incorrect. "复制和数量" means "copy and amount," which does not convey the intended action of "Copy amount." The correct translation should reflect the action of copying the amount value.

Correct translation:
複製金額
```

```
        <source>Create wallet failed</source>
        <translation>創建錢包失敗&lt;br&gt;</translation>
    
YES
The translation adds an unnecessary "<br>" HTML line break tag at the end, which is not present in the source text. This could result in formatting issues in the UI.

Correct translation:
創建錢包失敗
```

```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>仅观察脚本已经被迁移到被命名为“%1”的新钱包中。</translation>
    
YES
The translation is in Simplified Chinese (zh_CN), not Traditional Chinese (zh_TW), and uses the wrong character for "watch-only" ("仅观察" is Simplified; in Traditional it should be "僅觀察" or more commonly "僅觀察用"). Quotation marks also use straight quotes instead of the full-width or Chinese style gulled quotes. 

Correct translation:
僅觀察腳本已經被遷移到名為「%1」的新錢包中。
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
YES  
There are several issues in the translation:

1. "處裡" should be corrected to "處理".
2. "%4" block chain is missing the "%4" in the translated "%4區塊鏈".
3. The original sentence is more explicit about the process starting with the earliest transactions when %4 was launched, but this is not fully conveyed.
4. There is an unnecessary colon in "(大小:%2GB)".
5. There should be proper spacing around units: "%2 GB" instead of "%2GB".
6. There is some loss in sequence (the order in which information is presented).

Correct translation:
當你點擊「確認」時，%1 會開始下載並處理完整的 %4 區塊鏈（%2 GB），從 %3 年 %4 剛啟動時的最早交易開始。
```

```
        <source>Connect through SOCKS5 proxy (default proxy):</source>
        <translation>透過 SOCKS5 代理伺服器連線(預設代理伺服器 C):</translation>
    
YES
There is an error in the translation: "預設代理伺服器 C" erroneously adds an extra "C" at the end, which is not present in the source and is likely a typographical error.

Correct translation:
透過 SOCKS5 代理伺服器連線（預設代理伺服器）：
```

```
        <source>Proxy IP:</source>
        <translation>代理位址(I):</translation>
    
YES
The translation "代理位址(I):" is problematic. The original English does not include "(I)" and the letter "I" is not a typical hotkey or menu accelerator in this context for traditional Chinese. Such notations are not standard unless used in UI elements with keyboard shortcuts, and it can confuse users.

Correct translation:
代理位址：
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>縮到最小到通知區而不是工作列(M)</translation>
    
YES
The translation is mostly understandable, but it contains a slightly awkward structure and an unnecessary "(M)". The phrase "縮到最小到通知區而不是工作列" is redundant ("縮到最小到" is not idiomatic) and the "(M)" does not belong unless it is a designated accelerator key, which is not specified here.

Correct translation:
最小化到通知區，而非工作列
```

```
        <source>Use separate SOCKS5 proxy to reach peers via Tor onion services:</source>
        <translation>使用個別的SOCKS＆5代理介由Tor onion服務到達peers：</translation>
    
YES
There are several issues with the translation:
- "SOCKS＆5" uses a full-width ampersand ("＆") instead of the correct "SOCKS5" or "SOCKS5代理".
- "peers" is left untranslated. In zh_TW context, it should be translated as "節點" or "對等端".
- There is a slight unnaturalness and awkward grammatical structure.
- "介由Tor onion服務" is understandable but can be improved in fluency.

Correct translation:
使用獨立的 SOCKS5 代理來經由 Tor onion 服務連接至其他節點：
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>軟體未編譯外接簽證功能所需的軟體庫(外接簽證必須有此功能)</translation>
    
YES  
The translation is inaccurate. "簽證" refers more to "visa" in Chinese, which is not appropriate for "signing" in the context of cryptocurrencies. The message is also somewhat convoluted compared to the English source. "外接簽署" or "外部簽署" is the more proper term for "external signing" in this context.

Correct translation:
未編譯外部簽署支援（外部簽署需要此支援）
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>所有只能看的地址還沒已熟成的挖出餘額</translation>
    
YES
The translation is somewhat understandable but contains awkward phrasing and a redundancy ("還沒已熟成"). Also, "只能看的地址" is not the standard way to say "watch-only addresses" in Taiwanese Mandarin; "僅限觀察的地址" or "僅觀察位址" is better. "尚未成熟" is the standard phrase for "has not yet matured".

Correct translation:
觀察地址中尚未成熟的挖礦餘額
```

```
        <source>Could not sign any more inputs.</source>
        <translation>無法再簽名 input</translation>
    
YES  
The translation is inaccurate and partially untranslated. The word "input" should be translated to Chinese, and the full sentence should maintain the clarity of the original.

Correct translation:  
無法再對任何輸入進行簽名。
```

```
        <source>Peers</source>
        <translation>節點(P)</translation>
    
YES  
The translation "節點(P)" is problematic.  
1. "Peers" in the context of Bitcoin network typically refers to other nodes/participants in the network, and is best translated as "節點" or "對等節點".  
2. The inclusion of "(P)" is unwarranted unless it reflects an accelerator/hotkey in the original user interface, which is not indicated by the given source.  
3. No format specifiers or whitespace issues present.  

Correct translation:  
節點
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES
The translation is problematic because it uses Simplified Chinese ("隐藏" instead of Traditional "隱藏") and translates "Peers" as "其他人" (other people), which is inaccurate in the context of Bitcoin where "Peers" refers specifically to network peers/connected nodes. Also, "Peers Detail" should be "對等節點詳細資訊" or similar, not "详细信息" (Simplified; Traditional would be "詳細資訊").

Correct translation:
隱藏對等節點詳細資訊
```

```
        <source>Clear console</source>
        <translation>清主控台</translation>
    
YES
The translation "清主控台" is inaccurate and omits a key component. The term "主控台" is occasionally used, but the standard translation for "console" in computing contexts in Traditional Chinese is "控制台". More importantly, the translation is missing the verb "clear" or "清除" (to clear or remove).

Correct translation:
清除控制台
```

```
        <source>Outbound Feeler: short-lived, for testing addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to test the aliveness of known addresses.</extracomment>
        <translation>Outbound Feeler: 用於短暫，暫時 測試地址</translation>
    
YES  
The translation has several issues:
1. It retains "Outbound Feeler" in English instead of localizing.
2. The word order is unnatural; "用於短暫，暫時 測試地址" is awkward.
3. The spacing is inconsistent, with an unnecessary space between "暫時" and "測試地址".
4. "for testing addresses" is not clearly rendered.

Correct translation:  
外部探測連線：短暫建立，用於測試地址是否可用
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
YES
The translation is inaccurate. The phrase "Outbound 地址取得: 用於短暫，暫時 測試地址" introduces "測試地址" (test address) which is not present in the original. It also awkwardly redundantly states "短暫，暫時". The original means the connection is short-lived and is for soliciting (requesting) addresses.

Correct translation:
Outbound 地址擷取：短暫用於請求地址
```

```
        <source>1 hour</source>
        <translation>1 小時(H)</translation>
    
YES
The translation appends an unnecessary "(H)" which is not present in the source and is not standard in 'zh_TW'. It may introduce confusion and is considered erroneous content.

Correct translation:
1 小時
```

```
        <source>1 year</source>
        <translation>1 年(Y)</translation>
    
YES
The translation adds "(Y)", which is unnecessary and inconsistent with common zh_TW usage. It should simply be "1 年" without the "(Y)".

Correct translation:
1 年
```

```
        <source>Node window - [%1]</source>
        <translation>节点窗口 - [%1]</translation>
    
YES
The translation uses the simplified Chinese character "节点" instead of the traditional Chinese "節點" for 'zh_TW'. 

Correct translation:
節點視窗 - [%1]
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
There are minor issues with spacing and style:

1. In "使用%3 和 %4 以增加或減少字體大小。", there's a missing space before "%3" (should be "使用 %3 和 %4 以增加或減少字體大小。").
2. The original intentionally keeps %7 and %8 not space-separated from the warning, but in the translation, a space is added after %7 and before "警告：" (should not have a space: "%7警告：...%8").
3. The English says "stealing their wallet contents", but the translation says "清空錢包" which means "emptying the wallet". While related, "steal the wallet contents" is closer to "竊取他們錢包中的資產".
4. There's a space before the last sentence: "不要在不完全了解一個命令的後果的情況下使用此控制台。", which in the translation is written as: " 不要在不完全了解一個命令的後果的情況下使用此控制台。" (the space before is unnecessary due to wrong wrapping).

Correct translation:
歡迎來到 %1 RPC 控制台。
使用上與下箭頭以進行歷史導航，%2 以清除螢幕。
使用 %3 和 %4 以增加或減少字體大小。
輸入 %5 以顯示可用命令的概覽。
查看更多關於此控制台的資訊，輸入 %6。

%7警告：騙子已經行動，誘導用戶在此輸入命令，竊取他們錢包中的資產。不要在未完全了解命令後果的情況下使用此控制台。%8
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation is incorrect. "复制和数量" means "copy and amount," which does not convey the intended action of "Copy amount." The correct translation should reflect the action of copying the amount value.

Correct translation:
複製金額
```

```
        <source>Generates a native segwit address (BIP-173). Some old wallets don't support it.</source>
        <translation>產生一個原生隔離見證Segwit 位址 (BIP-173) 。 被部分舊版錢包不支援。</translation>
    
YES
The translation introduces spacing and punctuation issues, and could be rephrased for clarity and smoothness. Specifically:
- "Segwit" should not have a space before "位址".
- The sentence "被部分舊版錢包不支援。" lacks a subject and is not smooth in Chinese.
- The period placement is incorrect (there is a space before it).
- For 'zh_TW', "地址" is also more common than "位址", though both are used.

Correct translation:
產生一個原生隔離見證地址（BIP-173）。部分舊版錢包不支援此地址。
```

```
        <source>Send</source>
        <translation>付款(E)</translation>
    
YES
The translation '付款(E)' translates to 'Make Payment (E)', which adds a hotkey '(E)' not present in the source and specifies '付款' (make payment), introducing details not in the simple word "Send".

Correct translation:
發送
```

```
        <source>Create Unsigned</source>
        <translation>Cr＆eate未簽名</translation>
    
YES
The translation is problematic. The translation mixes English and Chinese inappropriately ("Cr＆eate未簽名"), and includes a stray symbol "＆". The word "Create" should be properly translated into Chinese.

Correct translation:
建立未簽名
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES
The translation is problematic. The phrase "然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。" is not smooth and splits the clause inappropriately, making the instructions unclear. The period after "簽名" incorrectly breaks the sentence. The expression "使用簽名" is also inaccurate; it should specify "用...簽名".

Correct translation:
請檢查您的交易提案。這將產生一筆部分簽名的比特幣交易（PSBT），您可以將其儲存或複製，然後使用例如離線的 %1 錢包或支援 PSBT 的硬體錢包來簽名。
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
YES
The translation is awkward and contains an unnecessary "給" at the end, which makes the sentence ungrammatical in Chinese. The "給" suggests "to" but its placement is wrong.

Correct translation:
要將付款發送到的比特幣地址
```

```
        <source>Send</source>
        <translation>發</translation>
    
YES
The translation "發" is incomplete and incorrect. The English word "Send" in the context of Bitcoin typically means "to send funds" or "to make a payment", and should be translated as "發送" or "發送資金" in Traditional Chinese (zh_TW). The single character "發" is insufficient and may be confusing.

Correct translation:
發送
```

```
        <source>Range…</source>
        <translation>范围...</translation>
    
YES
The translation uses simplified Chinese characters '范围' instead of traditional Chinese characters used in 'zh_TW'. The ellipsis is also three dots instead of the proper ellipsis character (…).

Correct translation:
範圍…
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation is incorrect. "复制和数量" means "copy and amount," which does not convey the intended action of "Copy amount." The correct translation should reflect the action of copying the amount value.

Correct translation:
複製金額
```

```
        <source>Disk space for %s may not accommodate the block files. Approximately %u GB of data will be stored in this directory.</source>
        <translation>%s的硬碟空間可能無法容納區塊文件。 大約要在這個目錄中儲存 %uGB的數據。</translation>
    
YES
There is a spacing issue: there should be a space between "%u" and "GB" in the Chinese text (" %uGB" should be " %u GB"), and there should not be a space at the start of the second sentence. Also, "數據" is more common in Mainland China; "資料" is the more standard term for 'data' in Taiwanese usage.

Correct translation:
%s 的硬碟空間可能無法容納區塊檔案。大約有 %u GB 的資料會儲存在此目錄中。
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES
The translation is inaccurate, contains errors, and shows some spacing issues. The phrase "多數TOR路由綁定位址" is not a natural or correct way to say "more than one onion bind address" in Traditional Chinese. Also, the use of "多數" suggests "the majority" instead of "more than one". "TOR路由綁定" is awkward, and "Tor onion service" should be translated more precisely. There is also an irregular space before "對".

Correct translation:
提供了多個 Onioin 綁定位址。將使用 %s 作為自動建立的 Tor onion 服務。
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>這是您支付的最高交易手續費（除了正常手續費外），優先於避免部分花費而不是定期選取幣。</translation>
    
YES
The translation is inaccurate and unclear, especially regarding "prioritize partial spend avoidance over regular coin selection." The translated phrase "優先於避免部分花費而不是定期選取幣" is grammatically incorrect and does not convey the intended meaning.

Correct translation:
這是您為了優先避免部分花費（而不是常規的找零選擇）所支付的最高額外交易手續費（除了正常手續費之外）。
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>不支援的類別限定日誌等級 %1$s=%2$s 。 预期参数 %1$s=&lt;category&gt;:&lt;loglevel&gt;。 有效的類別: %3$s 。有效的日誌等級: %4$s 。</translation>
    
YES
The translation mixes Simplified and Traditional Chinese: "预期参数" is Simplified; in Traditional Chinese, it should be "預期參數". Also, there are inconsistent spaces before periods and after punctuation, which is not standard in Chinese typographic conventions.
The % format specifiers are correctly carried over, but punctuation and character set need correction.

Correct translation:
不支援的類別限定日誌等級 %1$s=%2$s。預期參數 %1$s=&lt;category&gt;:&lt;loglevel&gt;。有效的類別：%3$s。有效的日誌等級：%4$s。
```

```
        <source>Error loading %s: Private keys can only be disabled during creation</source>
        <translation>載入 %s 時發生錯誤: 只有在造新錢包時能夠指定不允許私鑰</translation>
    
YES
The translation is understandable but inaccurate and contains awkward phrasing. Specifically, "造新錢包" is less common than "新建錢包" or "建立錢包", and "指定不允許私鑰" is unclear—it should directly convey "can only disable private keys during creation".

Correct translation:
載入 %s 時發生錯誤：只有在建立錢包時才能停用私鑰
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
YES
The translation omits "expected %s" and mistranslates the format. It also lacks proper punctuation and ordering for clarity.

Correct translation:
錯誤：轉存檔案的校驗和不符。計算值為 %s，預期為 %s
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES
The translation uses simplified Chinese ("错误：无法将数据写入钱包的磁盘%s。"). For 'zh_TW', traditional Chinese characters should be used. Also, the phrasing is a bit awkward.

Correct translation:
錯誤：無法將資料寫入錢包 %s 的磁碟。
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES
There are two issues:
1. The translation is missing the variable placeholder at the end: The format specifier "%s" is at the beginning in the translation, but in the source, it is at the end as ": %s".
2. The Chinese punctuation and word order are not idiomatic – the colon should be at the end, not left over in the translation.

Correct translation:
移除交易失敗：%s
```

```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>錢包軟體會付多於最小轉發費用的手續費。</translation>
    
YES
The translation is inaccurate. The original English states the wallet will avoid paying less than the minimum relay fee, i.e., it will not pay a fee below that minimum. The translation reverses the meaning, suggesting the wallet will pay more than the minimum relay fee.

Correct translation:
錢包將避免支付低於最低轉發手續費的費用。
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES
The translation is inaccurate. The English phrase "Transaction change output index out of range" refers to the index of the "change output" in a Bitcoin transaction being out of range. The provided translation, "交易尋找零輸出項超出範圍", mistranslates "change" as "尋找零" ("find zero") and does not accurately reflect the technical meaning.

Correct translation:
交易找零輸出索引超出範圍
```

```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>未知的交易已經有新規則激活 (versionbit %i)</translation>
    
YES  
The translation is inaccurate. The English source refers to "Unknown new rules activated," but the translation says "未知的交易已經有新規則激活," which translates back to "Unknown transactions already have new rules activated." The word "交易" (transactions) is not in the source. The meaning is distorted.

Correct translation:
未知的新規則已被啟用（versionbit %i）
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES
There is an error in the translation: "1%s" incorrectly inserts a "1" before the format specifier, which should not be present. The correct translation would be:
錢包檔案建立失敗：%s
```

```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>错误：无法添加仅观察交易%s到仅观察钱包</translation>
    
YES
The translation uses simplified Chinese ("错误", "无法", "仅观察"), but 'zh_TW' should use traditional Chinese characters. Additionally, spacing is inconsistent; there should be a space between "交易" and "%s". 

Correct translation:
錯誤：無法將僅觀察交易 %s 新增到僅觀察錢包
```
</details>

Number of issues: 58.
