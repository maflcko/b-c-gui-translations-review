# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh-Hans</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh-Hans%5D%20low%20quality)


```
        <source>Close</source>
        <translation>关闭(L)</translation>
    
YES: The translation is problematic because it adds an extra "(L)" after the translated word "关闭". This is not present in the source text and is likely an unintended artifact from a translation system. The correct translation should be "关闭" without any additional characters.

Correct Translation: 关闭
```

```
        <source>Export</source>
        <translation>导出(E)</translation>
    
YES, The translation includes an unnecessary English parenthetical "(E)" which is likely a leftover from a UI element and not appropriate for the meaning of "Export" in this context.

Correct translation: 导出
```

```
        <source>Banned Until</source>
        <translation>在此之前保持封禁:</translation>
    
YES, The translation is inaccurate. The source text "Banned Until" refers to a specific point in time when a ban will end, not a state of being kept banned until a certain point. The Chinese translation conveys the latter meaning.

Correct translation: 封禁至
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>发生了一个内部错误。%1将会尝试安全地继续运行。关于这个未知的错误我们有以下的描述信息用于参考。</translation>
    
YES, The translation is problematic. The phrase "This is an unexpected bug which can be reported as described below." was translated to "关于这个未知的错误我们有以下的描述信息用于参考。" which does not accurately convey the meaning. The original text implies that the bug can be reported and provides a way to do so, whereas the translation states that there is descriptive information for reference.

Correct translation: 发生了一个内部错误。%1将会尝试安全地继续运行。这是一个意外的错误，可以按照下文所述进行报告。
```

```
        <source>About %1</source>
        <translation>关于 %1 (A)</translation>
    
YES, the translation is problematic because it includes an unnecessary and potentially confusing parenthetical "(A)". In the context of Bitcoin, this doesn't add clarity and could be misinterpreted.

The correct translation should simply be:
关于 %1
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>用比特币地址关联的私钥为消息签名，以证明您拥有这个比特币地址</translation>
    
YES - The translation is overly specific and implies that signing a message directly proves ownership of the *address* itself, rather than the *private key* associated with the address. The phrase "比特币地址关联的私钥" (the private key associated with the Bitcoin address) is too long and cumbersome for a concise translation. A more accurate and natural translation would be to say you prove ownership of the *private key* that controls the address.

Correct translation: 用您的比特币地址签名消息，以证明您拥有对应的私钥。
```

```
        <source>Load PSBT from file…</source>
        <translation>从文件加载PSBT(L)...</translation>
    
YES, The translation is problematic because it adds an extra parenthesis "L" at the end of PSBT which is not present in the source text.

NO, from file...
```

```
        <source>Command-line options</source>
        <translation>命令行选项(C)</translation>
    
YES, The Chinese translation contains an extra character 'C)' that is not present in the original English text and is also not a format specifier.
Command-line options
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>从剪贴板加载PSBT(C)...</translation>
    
YES: The translation is problematic as it adds an extra "(C)" which is not present in the source text and serves no clear purpose in this context. The presence of this extra character could be confusing to the user.

Correct translation: 从剪贴板加载PSBT...
```

```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
YES
The translation is not accurate and uses a non-standard format for the "(S)". In Bitcoin context, "Sending addresses" would typically refer to the addresses from which the funds are being sent. A more accurate and common translation would be "发送地址".

Correct translation: 发送地址
```

```
        <source>Open a bitcoin: URI</source>
        <translation>打开bitcoin:开头的URI</translation>
    
YES
The translation is overly literal and doesn't convey the intended meaning of opening a Bitcoin URI. "Bitcoin:开头的URI" literally means "URI starting with bitcoin:". A better translation would be "打开比特币 URI" or "打开 Bitcoin URI".

Correct translation: 打开比特币:URI
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES, The translation of "Close wallet" to "卸载钱包" is incorrect. "卸载钱包" means "uninstall wallet". The correct translation for "Close wallet" in the context of Bitcoin is "关闭钱包".
NO
```

```
        <source>Show</source>
        <translation>显示(H)</translation>
    
YES: The translation adds an English letter "(H)" to the Chinese text "显示", which is not part of the original English text "Show". This is likely an error. The correct translation should be "显示".

Correct Translation: 显示
```

```
        <source>After Fee:</source>
        <translation>加上交易费用后:</translation>
    
YES: The translation is inaccurate. "After Fee" means "in the amount remaining after the fee is deducted", not "adding the transaction fee".

Correct translation: 扣除费用后:
```

```
        <source>Lock unspent</source>
        <translation>锁定未花费(O)</translation>
    
YES
The translation uses non-standard characters and punctuation that might cause issues in a technical context. The parenthetical "(O)" is also unclear and unnecessary.

Correct translation: 锁定未花费UTXO
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES, The translation of "Close wallet" to "卸载钱包" is incorrect. "卸载钱包" means "uninstall wallet". The correct translation for "Close wallet" in the context of Bitcoin is "关闭钱包".
NO
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>启用修剪时，如果一个钱包被卸载太久，就必须重新同步整条区块链才能再次加载它。</translation>
    
YES: The translation uses "卸载" (unloaded/uninstalled) which is not the correct term in the context of a Bitcoin wallet. The source implies closing the wallet application, not uninstalling it. A more accurate translation would be "关闭" (closed) or "闲置" (idle).

Correct translation: 启用修剪时，如果一个钱包闲置太久，就必须重新同步整条区块链才能再次加载它。
```

```
        <source>Address</source>
        <translation>地址(A)</translation>
    
YES - The translation is inaccurate because it includes an unnecessary parenthetical "(A)" which is not present in the source text and could be confusing in the context of Bitcoin addresses. The correct translation should be simply "地址".
地址
```

```
        <source>Number of script verification threads</source>
        <translation>脚本验证线程数(V)</translation>
    
YES, The translation is problematic. The "(V)" appended to the translation is extraneous and does not appear in the source text. It's also unclear what "(V)" signifies in this context, as it's not a standard notation in Bitcoin terminology for script verification threads.

NO
```

```
        <source>This allows you or a third party tool to communicate with the node through command-line and JSON-RPC commands.</source>
        <extracomment>Tooltip text for Options window setting that enables the RPC server.</extracomment>
        <translation>这允许作为用户的你或第三方工具通过命令行和JSON-RPC命令行与节点通信。</translation>
    
YES: The translation uses "命令行" (command-line) twice, making the sentence redundant and awkward. It also incorrectly uses "命令行" (command-line) to modify "JSON-RPC", which is a protocol, not a command-line interface. A more accurate and natural translation would be:
"这允许你或第三方工具通过命令行和JSON-RPC命令与节点通信。"
```

```
        <source>Wallet</source>
        <translation>钱包(A)</translation>
    
YES: The translation is inaccurate as it includes an unnecessary character "(A)" which does not appear in the source text. The correct translation should be "钱包".
```

```
        <source>Spend unconfirmed change</source>
        <translation>动用尚未确认的找零资金(S)</translation>
    
YES: The translation is a bit too literal and doesn't flow naturally in Chinese. The "(S)" at the end is also unnecessary.

Corrected translation:  动用未确认的找零
```

```
        <source>External signer script path</source>
        <translation>外部签名器脚本路径(E)</translation>
    
YES, the translation is problematic because it adds "(E)" at the end of the translated text. This appears to be an artifact or an unintended addition.

Correct translation: 外部签名器脚本路径
```

```
        <source>Third-party transaction URLs</source>
        <translation>第三方交易网址(T)</translation>
    
YES, The translation is problematic. The "(T)" at the end of the translation is an unexplained abbreviation and is likely an error or noise.

Correct translation: 第三方交易网址
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES - The translation is redundant. "watch-only addresses" is translated as "仅观察观察地址", which repeats the word "observe" (观察). The correct translation should be "您当前在仅观察地址中的余额".
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>仅观察地址中尚未成熟的挖矿收入余额:</translation>
    
YES, The translation incorrectly adds a colon at the end of the sentence, which is not present in the source text. The phrase "挖矿收入" (mining income) is also a more specific interpretation than "mined balance" and may not be entirely accurate depending on the exact context of "mined balance." However, the primary issue is the extraneous colon.

NO, Mined balance in watch-only addresses that has not yet matured
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>“概况”标签页已启用隐私模式。要明文显示数值，请在设置中取消勾选“不明文显示数值”。</translation>
    
YES - The translation contains a contradiction in the phrase "不明文显示数值" (do not display in clear text) which negates the user's action of unchecking the setting.

Correct translation: “概况”标签页已启用隐私模式。要明文显示数值，请在设置中取消勾选“隐藏数值”。
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>无法启动 bitcoin: 协议的“一键支付”处理程序</translation>
    
YES, The translation is problematic because it adds an extra unnecessary word "协议的" (protocol's) before "一键支付" (click-to-pay). This makes the translation less direct and slightly awkward in the context of Bitcoin.

The correct translation should be: 无法启动 bitcoin: “一键支付”处理程序
```

```
        <source>Peers</source>
        <translation>节点(P)</translation>
    
YES - The translation is not accurate and is problematic. The original English word "Peers" in the context of Bitcoin refers to other nodes in the network that a user's node is connected to. The provided Chinese translation "节点(P)" literally translates to "Node (P)". While "节点" means "node," the "(P)" part is unclear and doesn't accurately convey the meaning of "peers" in this context. A more appropriate translation for "Peers" in Bitcoin would be "节点" or "网络节点" (network nodes).

Correct translation: 节点
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES, The translation is not accurate. "Peers" refers to connected nodes in the Bitcoin network, not other people.

Correct translation: 隐藏节点详细信息
```

```
        <source>Network Traffic</source>
        <translation>网络流量(N)</translation>
    
YES
The translation is inaccurate because the "(N)" is an unnecessary addition that is not present in the source text.
network traffic
```

```
        <source>Outbound Manual: added using RPC %1 or %2/%3 configuration options</source>
        <extracomment>Explanatory text for an outbound peer connection that was established manually through one of several methods. The numbered arguments are stand-ins for the methods available to establish manual connections.</extracomment>
        <translation>出站手动: 加入使用RPC %1 或 %2/%3 配置选项</translation>
    
YES - The word "加入" (jiārù) translates to "join" or "add to", which is not the correct verb for establishing a connection. The intended meaning is "added" or "established". A more accurate translation would be "添加" (tiānjiā) or "建立" (jiànlì).

Correct translation: 出站手动: 使用 RPC %1 或 %2/%3 配置选项添加
```

```
        <source>1 hour</source>
        <translation>1 小时(H)</translation>
    
YES - The translation is problematic due to the inclusion of "(H)" which is not present in the source text and is unnecessary.

Correct translation: 1 小时
```

```
        <source>1 day</source>
        <translation>1 天(A)</translation>
    
YES: The translation adds an extra character "(A)" that is not present in the source text.
Correct translation: 1 天
```

```
        <source>1 year</source>
        <translation>1 年(Y)</translation>
    
YES, The translation is problematic because it incorrectly adds "(Y)" after the year. This is likely a misunderstanding of how to format dates in Chinese or an artifact from a translation tool. The correct translation should simply be "1 年".

1 年
```

```
        <source>After Fee:</source>
        <translation>加上交易费用后:</translation>
    
YES: The translation is inaccurate. "After Fee" means "in the amount remaining after the fee is deducted", not "adding the transaction fee".

Correct translation: 扣除费用后:
```

```
        <source>Specify a custom fee per kB (1,000 bytes) of the transaction's virtual size.

Note:  Since the fee is calculated on a per-byte basis, a fee rate of "100 satoshis per kvB" for a transaction size of 500 virtual bytes (half of 1 kvB) would ultimately yield a fee of only 50 satoshis.</source>
        <translation>指定交易虚拟大小的每kB (1,000字节) 自定义费率。

附注：因为矿工费是按字节计费的，所以如果费率是“每kvB支付100聪”，那么对于一笔500虚拟字节 (1kvB的一半) 的交易，最终将只会产生50聪的矿工费。（译注：这里就是提醒单位是字节，而不是千字节，如果搞错的话，矿工费会过低，导致交易长时间无法确认，或者压根无法发出）</translation>
    
YES, The translation is problematic because the explanation in parentheses "(译注：这里就是提醒单位是字节，而不是千字节，如果搞错的话，矿工费会过低，导致交易长时间无法确认，或者压根无法发出)" is an added explanation that is not present in the source text.

NO
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>付款目的地址</translation>
    
YES, The translation is missing the context of "Bitcoin address". A more accurate translation would be "发送付款的比特币地址".
```

```
        <source>Subtract fee from amount</source>
        <translation>从金额中减去交易费(U)</translation>
    
YES, The translation includes an extraneous character "(U)" which is not present in the source text and is likely an error or spam.

Correct translation: 从金额中减去交易费
```

```
        <source>Verify Message</source>
        <translation>验证消息签名(M)</translation>
    
YES - The translation is problematic because it adds an unnecessary "(M)" at the end of the phrase. The source text "Verify Message" does not contain this.
The correct translation should be "验证消息签名".
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/未确认</translation>
    
YES - The translation is incorrect. The English text "%1/unconfirmed" refers to a transaction that has been confirmed in at least one block but less than six blocks. The Chinese translation "%1/未确认" means "%1/unconfirmed" or "%1/not confirmed", which is inaccurate.
%1/已确认 (至少一个区块)</translation>
```

```
        <source>Generated</source>
        <translation>挖矿生成</translation>
    
YES: The translation is inaccurate. "Generated" in the context of Bitcoin typically refers to the creation of new blocks through mining, or the generation of new Bitcoin addresses. "挖矿生成" specifically translates to "mining generated," which is too narrow. The more appropriate translation for "Generated" in a general Bitcoin context would be "生成" (shēngchéng), meaning "generated" or "created."
Correct translation: 生成
```

```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>确认中 (推荐 %2个确认，已经有 %1个确认)</translation>
    
YES. The translation incorrectly swaps the order of the numbers in the confirmation count. The source text indicates "%1 of %2 recommended confirmations", meaning the current number of confirmations is the first number and the recommended number is the second. The translation states "%2个确认，已经有 %1个确认", which implies there are %2 confirmations and %1 is the current count, reversing the intended meaning.

NO.
The translation is correct.
The source text is "Confirming (%1 of %2 recommended confirmations)".
The translation is "确认中 (推荐 %2个确认，已经有 %1个确认)".
This translates to "Confirming (Recommended %2 confirmations, currently has %1 confirmations)".
This accurately conveys the meaning of the original sentence, with %1 representing the current number of confirmations and %2 representing the recommended number of confirmations. The format specifiers are also correctly placed.
```

```
        <source>Show transaction details</source>
        <translation>显示交易详情(S)</translation>
    
YES: The translation includes an unnecessary English letter in parentheses.
Correct translation: 显示交易详情
```

```
        <source>Increase transaction fee</source>
        <translation>增加矿工费(F)</translation>
    
YES - The translation uses "矿工费" which translates to "miner fee". While Bitcoin transactions do pay a fee to miners, the more common and accurate term for the fee paid by a user to facilitate a transaction is "交易费" (transaction fee) or "手续费" (handling fee). "矿工费" can be technically correct in that the fee goes to miners, but it's less direct and less commonly used in user-facing contexts for the fee a user pays. The '(F)' is also an unclear addition.

Correct translation: 增加交易费
```

```
        <source>Export</source>
        <translation>导出(E)</translation>
    
YES, The translation includes an unnecessary English parenthetical "(E)" which is likely a leftover from a UI element and not appropriate for the meaning of "Export" in this context.

Correct translation: 导出
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>无法在不支持“拆分前的密钥池”（pre split keypool）的情况下把“非拆分HD钱包”（non HD split wallet）从版本%i升级到%i。请使用版本号%i，或者压根不要指定版本号。</translation>
    
YES, The translation is problematic because it incorrectly translates "non HD split wallet" and "pre-split keypool". The context of Bitcoin suggests these are technical terms that should be translated more accurately.

Correct translation:
无法在不支持预拆分密钥池的情况下，将非HD拆分钱包从版本%i升级到版本%i。请使用版本%i，或不指定版本。
```

```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>错误: 转储文件格式不正确。得到是"%s"，而预期本应得到的是 "format"。</translation>
    
YES: The translation is grammatically awkward and uses overly literal phrasing. A more natural and accurate translation is provided.
错误：转储文件格式不正确。收到 "%s"，但预期格式为 "format"。
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多个洋葱路由绑定地址。对自动创建的洋葱服务用%s</translation>
    
YES, the translation is problematic because it is incomplete and grammatically incorrect in Chinese. The phrase "用%s" at the end of the sentence is not a complete thought and doesn't make sense in this context.

Here's a corrected translation:

More than one onion bind address is provided. Using %s for the automatically created Tor onion service.
provided more than one onion bind address, the automatically created Tor onion service will use %s.

Corrected translation:
提供了多个 Onion 绑定地址。将使用 %s 作为自动创建的 Tor Onion 服务。
```

```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of pruned node)</source>
        <translation>修剪:上次同步钱包的位置已经超出（落后于）现有修剪后数据的范围。你需要进行-reindex（对于已经启用修剪节点，就需要重新下载整个区块链）</translation>
    
YES: The translation contains a grammatical error and is unnatural. The phrase "已经超出（落后于）现有修剪后数据的范围" is awkward. A more natural and accurate translation would be "上次钱包同步的位置已超出修剪后的数据范围". Also, the parenthetical explanation for `-reindex` could be clearer.

Corrected translation: 修剪: 上次钱包同步的位置已超出修剪后的数据范围。你需要运行 -reindex（对于已启用修剪的节点，这会重新下载整个区块链）。
```

```
        <source>The block database contains a block which appears to be from the future. This may be due to your computer's date and time being set incorrectly. Only rebuild the block database if you are sure that your computer's date and time are correct</source>
        <translation>区块数据库包含未来的交易，这可能是由本机的日期时间错误引起。若确认本机日期时间正确，请重新建立区块数据库。</translation>
    
YES, The translation is problematic because it mistranslates "block" to "transaction".
The correct translation should be: "区块数据库包含一个未来的区块，这可能是由本机的日期时间错误引起。若确认本机日期时间正确，请重新建立区块数据库。"
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>找零低于当前粉尘阈值时会被舍弃，并计入手续费，这些交易手续费就是在这种情况下产生的。</translation>
    
YES, The translation is grammatically incorrect and does not accurately convey the meaning of the original English sentence. The Chinese sentence is also longer and more complex than necessary.

Correct translation: 找零低于此阈值时，这些交易手续费会被舍弃。
```

```
        <source>Cannot provide specific connections and have addrman find outgoing connections at the same time.</source>
        <translation>在使用地址管理器(addrman)寻找出站连接时，无法同时提供特定的连接。</translation>
    
YES, The translation is problematic because it misses the meaning of "specific connections". The correct translation should be "无法在寻找出站连接时同时提供指定连接。", which means "Cannot provide specific connections and have addrman find outgoing connections at the same time.".
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>出站连接被限制为仅使用 Tor (-onlynet=onion)，但是未提供到达 Tor 网络的代理：没有提供 -proxy=, -onion= 或 -listenonion 参数</translation>
    
YES, The translation is problematic because it is missing the equals sign after the parameters in the latter part of the sentence.
Correct translation: 出站连接被限制为仅使用 Tor (-onlynet=onion)，但是未提供到达 Tor 网络的代理：没有提供 -proxy=, -onion= 或 -listenonion 参数。
```

```
        <source>Error loading %s: Wallet requires newer version of %s</source>
        <translation>%s 加载错误:请升级到最新版 %s</translation>
    
YES, The translation is grammatically incorrect. The original sentence implies that the wallet requires a newer version of the specified software, but the translation states that the user should upgrade to the latest version of the software to load the content. A more accurate translation would be:

%s 加载错误: 钱包需要新版本的 %s
```

```
        <source>Error: Missing checksum</source>
        <translation>错误：跳过检查检验和</translation>
    
YES, The translation is problematic because it does not accurately convey the meaning of the source text. "跳过检查检验和" translates to "skip check checksum", which is not the same as "missing checksum".

The correct translation should be:
错误：缺少校验和
```

```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
YES: The translation incorrectly uses "unit32_t" instead of "uint32_t".
错误：无法把版本号%u作为uint32_t解析
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES, The format specifier "%s" is misplaced in the translation. It should be placed at the end of the string to correctly represent the wallet address.
The correct translation is: 错误：无法将数据写入钱包磁盘 %s。
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES. The translation incorrectly uses "maximum" instead of "minimum". The correct translation should reflect that the fee rate is lower than the *minimum* fee rate setting.

NO
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>无效的 -onion 地址: '%s'</translation>
    
YES - The translation misses the "or hostname" part of the original English sentence. The correct translation should include "或主机名" (or hostname).

NO
```

```
        <source>Not solvable pre-selected input %s</source>
        <translation>无法求解的预先选择输入%s</translation>
    
YES, The translation is inaccurate. The phrase "pre-selected input" should be translated as "预选输入" or "预先选择的输入" rather than "预先选择输入".
The correct translation is: 无法求解的预选输入%s
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES, The translation has a grammatical error. The character "不" is repeated unnecessarily.
The correct translation should be: "交易金额不可为负数".
```

```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>不明的交易规则已经激活 (versionbit %i)</translation>
    
YES, the word "交易" (transaction) is not present in the source text. The correct translation should be:

"NO"
"不明的新规则已激活 (versionbit %i)"
```
</details>
