# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>cmn</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bcmn%5D%20low%20quality)


```
        <source>Delete</source>
        <translation>刪除 D</translation>
    
YES, The translation includes an unnecessary letter "D" at the end of the translated word, which is not present in the source text.
Correct translation: 刪除
```

```
        <source>Runaway exception</source>
        <translation>未捕获的异常</translation>
    
YES, The translation is not accurate. The original English phrase "Runaway exception" refers to an uncaught exception that occurs and is not handled. The provided Chinese translation "未捕获的异常" translates to "uncaught exception".

The correct translation should reflect the "runaway" aspect, implying an exception that is not being controlled or handled. A more fitting translation would be "失控的异常" or "失控异常".

Correct translation: 失控异常
```

```
        <source>Inbound</source>
        <extracomment>An inbound connection from a peer. An inbound connection is a connection initiated by a peer.</extracomment>
        <translation>進來</translation>
    
UNK_LANG
```

```
        <source>%1 and %2</source>
        <translation>%1又 %2</translation>
    
YES - The translation is missing a comma between %1 and %2, which is necessary for proper grammar. The correct translation should include a comma.
%1 and %2
```

```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
YES. The translation contains an extraneous character "(S)" which is not present in the source text. This could be an artifact from the translation process or an unintended addition.

Correct translation: 付款地址
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES, The translation is inaccurate. "Close wallet" means to close the Bitcoin wallet, while "卸载钱包" means to uninstall the wallet.
Correct translation: 关闭钱包
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES: The translation is incorrect. It translates "Enable network activity" to "Close network activity". The correct translation should be "啟用網路活動".
NO
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>錢包&lt;b&gt;已加密&lt;/b&gt;並且&lt;b&gt;解鎖中&lt;/b&gt;</translation>
    
YES, The translation "錢包&lt;b&gt;已加密&lt;/b&gt;並且&lt;b&gt;解鎖中&lt;/b&gt;" translates to "Wallet &lt;b&gt;is encrypted&lt;/b&gt; and &lt;b&gt;is unlocking&lt;/b&gt;". The original English states that the wallet is "unlocked", not "unlocking".

The correct translation should be:
錢包&lt;b&gt;已加密&lt;/b&gt;並且&lt;b&gt;已解鎖&lt;/b&gt;
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning. The Chinese phrase "复制和数量" translates to "Copy and quantity," which is not what "Copy amount" means in the context of Bitcoin transactions.

The correct translation should be "复制金额" which means "Copy amount".

NO
```

```
        <source>Copy after fee</source>
        <translation>複製計費後金額</translation>
    
YES, The translation is inaccurate. The English text "Copy after fee" implies copying the amount remaining after a fee has been deducted. The Chinese translation "複製計費後金額" (fùzhì jìfèi hòu jīn'é) literally means "copy amount after billing", which is not quite the same. In the context of Bitcoin, "fee" refers to a transaction fee. A more accurate translation would be "複製手續費後金額" (fùzhì shǒuxùfèi hòu jīn'é), meaning "copy amount after transaction fee".

NO
```

```
        <source>Create wallet failed</source>
        <translation>創建錢包失敗&lt;br&gt;</translation>
    
YES, The translation includes an unnecessary HTML line break tag "&lt;br&gt;".
Correct translation: 創建錢包失敗
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES, The translation is inaccurate. "Close wallet" means to close the Bitcoin wallet, while "卸载钱包" means to uninstall the wallet.
Correct translation: 关闭钱包
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>启用修剪时，如果一个钱包被卸载太久，就必须重新同步整条区块链才能再次加载它。</translation>
    
YES - The translation incorrectly translates "Closing the wallet for too long" as "if a wallet is unloaded for too long". The original text suggests that the wallet application itself is closed, not that the wallet files are unloaded.

"启用修剪时，如果钱包长时间未关闭，则可能需要重新同步整个链。"
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>地址“%1”為已登記存在“%2”的地址，因此無法新增為發送地址。</translation>
    
YES, The translation is problematic because it incorrectly translates "receiving address" to "登記存在" (registered existence). The correct translation should reflect that the address is already in use as a receiving address.
The correct translation is: 地址“%1”已作為標籤為“%2”的收款地址存在，因此無法新增為發送地址。
```

```
        <source>Directory already exists. Add %1 if you intend to create a new directory here.</source>
        <translation>已經有這個目錄了。如果你要在裡面造出新的目錄的話，請加上 %1.</translation>
    
YES. The translation is problematic because it uses a colloquial and informal phrasing ("造出新的目錄的話") that is not suitable for the technical context of Bitcoin. It also misinterprets the purpose of "%1". In the source text, "%1" is meant to be appended to the directory name, not used in the conditional clause.

The correct translation should be:
"目錄已經存在。如果你打算在此建立新目錄，請附加 %1。"
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
YES
The translation is missing a part of the original sentence and has a grammatical error.

Correct translation:
當你點擊「確認」，%1會開始下載並處裡整個%4區塊鏈(大小:%2 GB)，從%3年%4剛推出時的最早交易開始。
```

```
        <source>Form</source>
        <translation>窗体</translation>
    
UNK_LANG
```

```
        <source>Start %1 on system login</source>
        <translation>系统登入时启动 %1 (S)</translation>
    
YES, the translation is problematic. The trailing "(S)" is unnecessary and doesn't align with the source text.

Correct translation: 系统登入时启动 %1
```

```
        <source>Prune block storage to</source>
        <translation>将区块存储修剪至(B)</translation>
    
YES, The translation is problematic. The parenthetical "(B)" at the end of the translation is not present in the source text and seems out of place for the given context.

NO
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>警告:还原此设置需要重新下载整个区块链。</translation>
    
YES - The translation contains an unnecessary "警告:" (Warning:). The word "Reverting" is also translated to "还原此设置" (reverting this setting), which is a bit redundant in this context.

A more accurate and concise translation would be:
"重新下载整个区块链需要还原此设置。"
```

```
        <source>This allows you or a third party tool to communicate with the node through command-line and JSON-RPC commands.</source>
        <extracomment>Tooltip text for Options window setting that enables the RPC server.</extracomment>
        <translation>这允许作为用户的你或第三方工具通过命令行和JSON-RPC命令行与节点通信。</translation>
    
YES, The word "命令行" is repeated unnecessarily. The correct translation is: "这允许作为用户的你或第三方工具通过命令行和JSON-RPC命令与节点通信。"
```

```
        <source>Spend unconfirmed change</source>
        <translation>动用尚未确认的找零资金(S)</translation>
    
YES, The translation is problematic because the character '(' appears at the end of the translation. This character should not appear there. The correct translation should be: 动用尚未确认的找零资金
```

```
        <source>External signer script path</source>
        <translation>外部签名器脚本路径(E)</translation>
    
YES, The translation of "External signer script path" to "外部签名器脚本路径(E)" is problematic because the "(E)" at the end is not part of the original English text and seems like an extraneous annotation.

NO
```

```
        <source>Form</source>
        <translation>窗体</translation>
    
UNK_LANG
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES. The translation contains redundant wording ("watch-only addresses" translated as "仅观察观察地址").

NO. 您当前在仅观察地址中的余额
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>仅观察地址中尚未成熟的挖矿收入余额:</translation>
    
YES, The translation is problematic. The original English text does not end with a colon, but the translation does.

NO
仅观察地址中尚未成熟的挖矿收入余额
```

```
        <source>Save…</source>
        <translation>拯救...</translation>
    
YES, The translation is problematic. The English word "Save" in the context of a user interface typically means to store or preserve data. The Chinese translation "拯救" (zhěngjiù) means "to save" in the sense of rescuing someone or something from danger or harm. This is an incorrect and potentially alarming translation for a "Save" button in a Bitcoin context.

The correct translation for "Save…" in this context should be "保存…" (bǎocún…).

Correct translation: 保存…
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>无法启动 bitcoin: 协议的“一键支付”处理程序</translation>
    
YES
The translation is problematic because it uses a literal translation of "click-to-pay handler" that sounds unnatural and doesn't accurately convey the intended meaning in the context of Bitcoin. A more appropriate translation would refer to the payment protocol handler.

Correct translation: 无法启动 bitcoin：一键支付协议处理程序
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES, the translation is problematic because it incorrectly translates "Peers" as "其他人" (other people). In the context of Bitcoin, "Peers" refers to other nodes on the network, not just other individuals.

A more accurate translation would be:

隐藏节点详情
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>來自這個節點上次成功驗證新交易進入內存池已經過的時間</translation>
    
YES - The translation incorrectly states "successfully verified new transaction". The original text simply says "novel transaction accepted into our mempool". The correct translation should reflect this.
來自這個節點上次進入內存池的新交易的經過時間
```

```
        <source>Clear console</source>
        <translation>清主控台</translation>
    
YES
The translation is not idiomatic and sounds unnatural. "清主控台" literally translates to "Clear main console", which is a bit awkward. A more natural translation would be "清空控制台".

清空控制台
```

```
        <source>Outbound Manual: added using RPC %1 or %2/%3 configuration options</source>
        <extracomment>Explanatory text for an outbound peer connection that was established manually through one of several methods. The numbered arguments are stand-ins for the methods available to establish manual connections.</extracomment>
        <translation>出站手动: 加入使用RPC %1 或 %2/%3 配置选项</translation>
    
YES: The translation uses "加入" (jiārù), which means "join" or "add," implying the user is joining a group or adding something to a list. In the context of Bitcoin, the intended meaning is likely "established" or "created," as in establishing a peer connection. A more appropriate translation would be "建立" (jiànlì), meaning "establish" or "build."

出站手动: 使用RPC %1 或 %2/%3 配置选项建立
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
YES, The translation is problematic because it contains extraneous words and the meaning is altered. The phrase "short-lived, for soliciting addresses" was translated as "用於短暫，暫時 測試地址" which means "for short, temporary test addresses". This changes the meaning from "soliciting addresses" to "testing addresses".

The correct translation should be: "Outbound 地址取得: 短暫，用於獲取地址"
```

```
        <source>Ban for</source>
        <translation>禁止連線</translation>
    
YES - The translation "禁止連線" means "ban connection" or "forbidden connection", which is not an accurate translation of "Ban for". The source text is incomplete and likely expects a noun or phrase to follow "Ban for". A more appropriate translation would depend on what is being banned. If it is a ban on a specific user or action, the translation should reflect that. For example, if it were "Ban for invalid address", a possible translation could be "因地址無效而封鎖".
The original translation doesn't accurately convey the meaning of "Ban for".
"Ban for" is an incomplete phrase.
A more contextually appropriate translation would be "禁止原因" which means "reason for ban".
However, without further context to complete the phrase, it is difficult to provide a perfect translation.
If the intent was to state the reason for the ban, then "禁止原因" would be suitable.
If the intent was to ban a specific entity, then the translation would need to be adjusted accordingly.
For example, "Ban for invalid address" could be translated as "因無效地址而封鎖".
Given the context of Bitcoin, it is possible that "Ban for" might be followed by something like "invalid address" or "suspicious activity".
Without more information, it's hard to give a definitive corrected translation.
However, the current translation of "禁止連線" is definitely not a direct or accurate translation of "Ban for".

Let's assume the phrase is meant to indicate the reason for a ban, and a generic placeholder is needed. In that case, "禁止原因" (reason for ban) would be a better fit.

Correct translation: 禁止原因
```

```
        <source>An optional amount to request. Leave this empty or zero to not request a specific amount.</source>
        <translation>要求付款的金額，可以不填。不確定金額時可以留白或是填零。</translation>
    
YES, The translation is problematic as it is an incomplete and inaccurate translation of the source text. The source text specifies that the amount is optional and can be left empty or zero to not request a specific amount. The translation states that the amount can be left blank or filled with zero, which is partially correct, but it also includes information that is not present in the source text, such as "不確定金額時可以留白或是填零" (When unsure of the amount, you can leave it blank or fill in zero).

NO
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning. The Chinese phrase "复制和数量" translates to "Copy and quantity," which is not what "Copy amount" means in the context of Bitcoin transactions.

The correct translation should be "复制金额" which means "Copy amount".

NO
```

```
        <source>Copy Address</source>
        <translation>複製 地址</translation>
    
YES - The translation contains an extra space between "複製" and "地址".
Correct translation: 複製地址
```

```
        <source>Copy after fee</source>
        <translation>複製計費後金額</translation>
    
YES, The translation is inaccurate. The English text "Copy after fee" implies copying the amount remaining after a fee has been deducted. The Chinese translation "複製計費後金額" (fùzhì jìfèi hòu jīn'é) literally means "copy amount after billing", which is not quite the same. In the context of Bitcoin, "fee" refers to a transaction fee. A more accurate translation would be "複製手續費後金額" (fùzhì shǒuxùfèi hòu jīn'é), meaning "copy amount after transaction fee".

NO
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES: The translation is problematic because it is grammatically incorrect and lacks clarity in the latter part of the sentence. Specifically, "然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。" is awkward and doesn't properly convey the intended meaning of signing with a specific type of wallet.

Correct translation: 請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用離線 %1 錢包或與 PSBT 相容的硬體錢包進行簽名。
```

```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>没有打上BIP-125手续费追加的标记。</translation>
    
YES, The translation is grammatically correct and accurately conveys the meaning of the source text. However, it is slightly awkward. A more natural translation would be:

"没有标记Replace-By-Fee, BIP-125。"
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
YES, The translation is grammatically incorrect and unnatural in Chinese.
The correct translation is: "將支付發送到的比特幣地址" or "發送支付到此比特幣地址".
```

```
        <source>Subtract fee from amount</source>
        <translation>從付款金額減去手續費(U)</translation>
    
YES, The translation is problematic because it is missing a format specifier. The "(U)" at the end of the translation is not present in the source text and is an extraneous addition.
Correct translation: 從付款金額減去手續費
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning. The Chinese phrase "复制和数量" translates to "Copy and quantity," which is not what "Copy amount" means in the context of Bitcoin transactions.

The correct translation should be "复制金额" which means "Copy amount".

NO
```

```
        <source>Increase transaction fee</source>
        <translation>增加矿工费(F)</translation>
    
YES - The translation is problematic because it includes the letter "F" which is not present in the original English text. This could be an erroneous inclusion or a misplaced abbreviation.
Correct translation: 增加交易费
```

```
        <source>Error starting/committing db txn for wallet transactions removal process</source>
        <translation>错误：启动/提交数据库事务时出错，导致钱包交易移除过程失败。</translation>
    
YES - The translation contains an unnecessary "错误：" prefix and an added clause "导致钱包交易移除过程失败。" which is not present in the original source text.

NO - Error starting/committing db txn for wallet transactions removal process
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
YES, The translation is problematic because it omits the colon after "獲得" and the closing quotation mark for the first "%s", and it also omits the closing quotation mark for the second "%s". It also adds an unnecessary newline.

The correct translation is:
錯誤：轉存檔案識別記錄不正確。獲得 "%s"，預期 "%s"。
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES - The translation incorrectly translates "onion bind address" as "TOR路由綁定位址". A more accurate translation for "onion bind address" in the context of Bitcoin and Tor would be "onion 綁定位址".

Correct translation: 提供了多個 onion 綁定位址。正在為自動建立的 Tor onion 服務使用 %s。
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>這是您支付的最高交易手續費（除了正常手續費外），優先於避免部分花費而不是定期選取幣。</translation>
    
YES
The translation is awkward and does not accurately convey the meaning of "prioritize partial spend avoidance over regular coin selection." The phrase "定期選取幣" (regular coin selection) is not idiomatic in this context.

A better translation would be:
這是您支付的最高交易手續費（除了正常手續費外），用於優先避免部分花費，而非採用常規的選幣策略。
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>找零低于当前粉尘阈值时会被舍弃，并计入手续费，这些交易手续费就是在这种情况下产生的。</translation>
    
YES, the translation is inaccurate and conveys a meaning different from the original English sentence. The original sentence states that the transaction fee can be discarded if the change is smaller than dust at a certain level. The translation, however, states that if the change is smaller than the dust threshold, it will be discarded and included in the transaction fee. This is a misinterpretation of the relationship between transaction fees and change.

NO
```

```
        <source>-maxmempool must be at least %d MB</source>
        <translation>參數 -maxmempool 至少要給 %d 百萬位元組(MB)</translation>
    
YES - The translation uses "百萬位元組" which is a literal translation of "megabytes" but in the context of Bitcoin, "MB" is the standard and most understood unit. Also, the phrasing can be improved for naturalness in Chinese.

NO - The translation is problematic. While technically understandable, "百萬位元組" is not the standard way to refer to MB in Chinese computing contexts, and the phrasing could be more natural.

Correct translation: -maxmempool 至少要是 %d MB
```

```
        <source>Cannot resolve -%s address: '%s'</source>
        <translation>沒辦法解析 -%s 參數指定的地址: '%s'</translation>
    
YES - The translation incorrectly interprets "-%s" as a parameter instead of part of the address string.
沒辦法解析位址 -%s: '%s'
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>出站连接被限制为仅使用 Tor (-onlynet=onion)，但是未提供到达 Tor 网络的代理：没有提供 -proxy=, -onion= 或 -listenonion 参数</translation>
    
YES - The translation is missing the equals signs after the proxy parameters.
出站连接被限制为仅使用 Tor (-onlynet=onion)，但是未提供到达 Tor 网络的代理：没有提供 -proxy=, -onion= 或 -listenonion 参数
```

```
        <source>Unrecognized descriptor found. Loading wallet %s

The wallet might had been created on a newer version.
Please try running the latest software version.
</source>
        <translation>找到无法识别的输出描述符。加载钱包%s

钱包可能由新版软件创建，
请尝试运行最新的软件版本。
</translation>
    
YES - The translation includes an extraneous phrase "输出" (output). The correct translation should directly translate "descriptor" as "描述符" (descriptor) without adding "output".

Correct translation:
找到无法识别的描述符。加载钱包%s

钱包可能由新版软件创建，
请尝试运行最新的软件版本。
```

```
        <source>Error loading %s: Private keys can only be disabled during creation</source>
        <translation>載入 %s 時發生錯誤: 只有在造新錢包時能夠指定不允許私鑰</translation>
    
YES: The translation uses "錢包" (qiánbāo - wallet) which implies a Bitcoin wallet address. However, the source text uses "%s" which is a format specifier that can be used for various types of inputs. Without further context or if the "%s" refers to a Bitcoin network address, the translation is misleading. The phrase "指定不允許私鑰" (zhǐdìng bù yǔnxǔ sī yào - specify not allowed private keys) is awkward and doesn't accurately convey the meaning of "disabled during creation".

A more accurate and neutral translation would be:

載入 %s 時發生錯誤：私鑰僅能在創建時禁用
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
YES: The format specifier "%s" appears twice in the source text, but only once in the translation. The translation also omits the word "expected" and does not translate the second "%s" placeholder.

Correct translation: 錯誤：轉存檔案的校驗和不匹配。計算得%s，預期為%s
```

```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
YES, the translation contains a spelling error. The English word "uint32_t" is a type in programming, and it should not be translated. The correct translation should be: 错误：无法把版本号%u作为uint32_t解析
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES: The format specifier %s is incorrectly placed. It should follow the word "wallet".
错误：无法将数据写入钱包 %s 的磁盘。
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES, The translation is incorrect and the format specifier is misplaced. The correct translation should be:
%s 删除交易失败
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES, the translation incorrectly uses "maximum" (最大) instead of "minimum" (最低). The format specifiers are correctly transferred.
NO
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s'</source>
        <translation>%s=&lt;amount&gt;: '%s' 中指定了非法的金额</translation>
    
YES, The Chinese translation should be "无效的金额 %s=&lt;amount&gt;: '%s'". The original translation uses a word order that is not natural in Chinese and translates "Invalid amount" to "非法的金额" which is not accurate.

NO, Invalid amount for %s=&lt;amount&gt;: '%s'
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES, The translation has a grammatical error. The word "不" is repeated.
交易金额不可为负数
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES - The translation "交易尋找零輸出項超出範圍" seems to be attempting to convey "Transaction zero output index out of range". The English source text is "Transaction change output index out of range". The word "change" has been mistranslated as "零" (zero).

The correct translation for "Transaction change output index out of range" in cmn, considering the context of Bitcoin, is:
交易變更輸出索引超出範圍
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES, The translation is problematic. The format specifier '%s' has been incorrectly translated to '1%s'. The correct translation should retain the original format specifier.
Wallet file creation failed: %s
```
</details>
