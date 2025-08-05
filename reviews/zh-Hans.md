# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh-Hans</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh-Hans%5D%20low%20quality)


```
        <source>Close</source>
        <translation>关闭(L)</translation>
    
YES  
The addition of "(L)" in the translation is not present in the source and seems out of place in Chinese UI terminology. It may confuse users as it is likely intended to indicate a shortcut key in English but is not localized or explained.

Correct translation:  
关闭
```

```
        <source>Export</source>
        <translation>导出(E)</translation>
    
YES
The "(E)" is unnecessary and non-standard in Simplified Chinese UI translations, as keyboard shortcuts are typically not indicated in parentheses like this. The correct translation should simply be:

导出
```

```
        <source>Banned Until</source>
        <translation>在此之前保持封禁:</translation>
    
YES
The translation "在此之前保持封禁:" is awkward and overly literal. It can be improved to better convey "Banned Until" in the context of a ban expiration time.

Correct translation:
封禁至
```

```
        <source>About %1</source>
        <translation>关于 %1 (A)</translation>
    
YES  
The translation contains an unnecessary and unclear "(A)" which is not present in the source and may confuse users. Also, there is an extra space after "关于" before %1, which is not needed in Chinese formatting.

Correct translation:  
关于%1
```

```
        <source>Load PSBT from file…</source>
        <translation>从文件加载PSBT(L)...</translation>
    
YES  
The ellipsis character in the source is the Unicode ellipsis (…) but the translation uses "(L)...", which is incorrect and adds an unnecessary "(L)". The correct translation should simply end with an ellipsis character and no additional letters.

Correct translation:  
从文件加载PSBT…
```

```
        <source>Command-line options</source>
        <translation>命令行选项(C)</translation>
    
YES  
The translation adds an unnecessary "(C)" which is not present in the source text and may cause confusion. The translation should strictly reflect the source meaning without extra characters.  

Correct translation:  
命令行选项
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>从剪贴板加载PSBT(C)...</translation>
    
YES  
The translation uses "(C)" which is incorrect and adds extra characters not present in the source text. The ellipsis "…" should be preserved as is, not replaced by "(C)". Also, the original text uses an ellipsis (…) which is a single Unicode character, but the translation replaces it with "(C)", which is wrong.

Correct translation:  
从剪贴板加载PSBT…
```

```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
YES  
The original English source "Sending addresses" likely refers to the addresses that are set as sending (i.e., the addresses from which bitcoins are sent). The provided translation "付款地址(S)" means "payment address(es)" followed by an "(S)", which is unclear and unnecessary. Also, the "(S)" likely comes from a misinterpretation of a keyboard shortcut or mnemonic and should not be included in the translation unless explicitly specified.

A more accurate translation would be simply "发送地址" which directly corresponds to "sending addresses."

Correct translation:  
发送地址
```

```
        <source>Open a bitcoin: URI</source>
        <translation>打开bitcoin:开头的URI</translation>
    
YES  
The translation mixes English and Chinese and does not fully localize "bitcoin" into Chinese, which is commonly translated as "比特币". Also, "bitcoin:" is a scheme prefix and should be clearly indicated. A more natural and accurate translation would be:

打开以 bitcoin: 开头的 URI

or fully localized:

打开以比特币（bitcoin:）开头的 URI
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES  
The translation "卸载钱包" means "Uninstall wallet," which is incorrect in this context. The English phrase "Close wallet" refers to closing or shutting the wallet application or interface, not uninstalling it. The correct translation should be "关闭钱包."
```

```
        <source>Show</source>
        <translation>显示(H)</translation>
    
YES
The source text "Show" is a simple imperative or label and does not include additional characters. The translation "显示(H)" adds "(H)", which is not present in the source and may confuse users unless "(H)" is intended as a shortcut key or mnemonic. Such additional notation should only appear if it corresponds to the source or established UI conventions, and in that case, the source would have indicated it.

Correct translation:
显示
```

```
        <source>Lock unspent</source>
        <translation>锁定未花费(O)</translation>
    
YES  
The "(O)" in the translation seems out of place and unnecessary, as it does not appear in the source text. There should be no extra characters or parentheses in the translation. Also, there is no format specifier to consider here.  

Correct translation:  
锁定未花费
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES  
The translation "卸载钱包" means "Uninstall wallet," which is incorrect in this context. The English phrase "Close wallet" refers to closing or shutting the wallet application or interface, not uninstalling it. The correct translation should be "关闭钱包."
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>启用修剪时，如果一个钱包被卸载太久，就必须重新同步整条区块链才能再次加载它。</translation>
    
YES  
The translation is somewhat inaccurate and changes the meaning. The source says "closing the wallet for too long can result in having to resync the entire chain if pruning is enabled." The translation implies the wallet is "unloaded" (卸载) for too long, which is not the same as "closing" and might confuse readers to think of uninstalling or removing the wallet software. Also, "才能再次加载它" ("in order to load it again") is an added explanation not present in the source and slightly changes the meaning.

A better translation would be more literal and keep the focus on "closing the wallet" and the resulting need to resync.

Correct translation:  
启用修剪时，长时间关闭钱包可能导致需要重新同步整条区块链。
```

```
        <source>Address</source>
        <translation>地址(A)</translation>
    
YES  
The translation adds "(A)" which is not present in the source and is generally unnecessary unless it has a specific contextual meaning, which is not indicated here. The correct translation should simply be:  
地址
```

```
        <source>Wallet</source>
        <translation>钱包(A)</translation>
    
YES
The translation adds "(A)" which is not present in the source and is unnecessary. The correct translation should simply be:

钱包
```

```
        <source>Spend unconfirmed change</source>
        <translation>动用尚未确认的找零资金(S)</translation>
    
YES
The translation includes an unnecessary "(S)" at the end, which is not present in the source and could cause confusion. Also, "动用" is understandable but less commonly used in Bitcoin context. A more standard translation would be:

尚未确认的找零资金可用

Or more simply:

使用尚未确认的找零金额

Correct translation:
使用尚未确认的找零金额
```

```
        <source>External signer script path</source>
        <translation>外部签名器脚本路径(E)</translation>
    
YES  
The translation includes an unnecessary "(E)" which does not appear in the source text and may confuse users. It should simply translate the phrase without additional characters.

Correct translation:  
外部签名器脚本路径
```

```
        <source>Third-party transaction URLs</source>
        <translation>第三方交易网址(T)</translation>
    
YES  
The translation incorrectly includes "(T)", which is not present in the source text and seems unrelated. Also, "网址" means "website URLs," but in the context of Bitcoin, "transaction URLs" usually refers to URLs related to transactions, so "交易链接" (transaction links) could be more appropriate and natural.  

Correct translation:  
第三方交易链接
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES  
The translation contains a redundancy with "仅观察观察地址" ("watch-only watch addresses"). This is repetitive and incorrect. The correct translation should be concise and clear. The phrase "watch-only addresses" should be translated as "仅观察地址".

Correct translation:  
您当前仅观察地址中的余额
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>仅观察地址中尚未成熟的挖矿收入余额:</translation>
    
YES  
The translation introduces an unnecessary colon (:) at the end, which is not present in the source and may cause formatting issues. Also, "观察地址" is not the standard term for "watch-only addresses" in Bitcoin context. The commonly accepted term is "仅观察地址" or "仅观看地址" but "仅观察地址" is acceptable. The phrase "挖矿收入余额" is somewhat understandable but "挖矿余额" or "已挖余额" might be better; however, this is minor.

Correct translation:  
仅观察地址中尚未成熟的挖矿余额
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>“概况”标签页已启用隐私模式。要明文显示数值，请在设置中取消勾选“不明文显示数值”。</translation>
    
YES
The translation is mostly correct, but "不明文显示数值" is not a natural or standard way to say "Mask values." A better term would be "掩码数值" or "隐藏数值" to align with "Mask values."

Correct translation:
“概况”标签页已启用隐私模式。要显示数值，请在设置中取消勾选“掩码数值”。
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>无法启动 bitcoin: 协议的“一键支付”处理程序</translation>
    
YES  
The translation adds "协议的" (“protocol’s”) which is not present in the source and alters the meaning slightly. Also, "bitcoin" should be capitalized as "Bitcoin" to follow the original styling, and the term "click-to-pay" is better translated as "点击支付" or kept as "click-to-pay" for clarity, rather than "一键支付" which means "one-click payment" and could convey a different idea. A more accurate translation would be concise and faithful to the source.

Correct translation:  
无法启动 Bitcoin: click-to-pay 处理程序
```

```
        <source>Peers</source>
        <translation>节点(P)</translation>
    
YES  
The translation "节点(P)" includes an unnecessary "(P)" which does not appear in the source and could confuse users. The source text "Peers" in the context of Bitcoin usually refers to network nodes or peers, which can be simply translated as "节点". There is no need to add "(P)".

Correct translation:  
节点
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES  
The translation "隐藏其他人的详细信息" literally means "Hide other people's detailed information," which changes the meaning. The English "Peers" here refers to network peers or nodes, not "other people" in a general sense. A more accurate translation would preserve the technical meaning with a focus on peers (节点 or 对等节点).

Correct translation:  
隐藏节点详情
```

```
        <source>Network Traffic</source>
        <translation>网络流量(N)</translation>
    
YES  
The translation "网络流量(N)" includes an unnecessary and unexplained "(N)" at the end, which is not present in the source text and may confuse users. The term "网络流量" correctly translates "Network Traffic" and is sufficient on its own.

Correct translation:  
网络流量
```

```
        <source>1 hour</source>
        <translation>1 小时(H)</translation>
    
YES
The translation adds "(H)" which is not present in the source and is unnecessary. The source "1 hour" is simply "1小时" in Simplified Chinese without parentheses or extra letters.

Correct translation:  
1小时
```

```
        <source>1 day</source>
        <translation>1 天(A)</translation>
    
YES  
The translation contains an unnecessary and unexplained "(A)" which is not present in the source text and makes the translation look erroneous or confusing.  
Correct translation:  
1 天
```

```
        <source>1 year</source>
        <translation>1 年(Y)</translation>
    
YES  
The translation includes an unnecessary and unclear suffix "(Y)" which is not present in the source text and may confuse users. The source simply states "1 year," which should be translated straightforwardly without extra characters.  

Correct translation:  
1 年
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>付款目的地址</translation>
    
YES  
The translation "付款目的地址" literally means "the payment destination address," which is understandable but less precise. A more accurate and commonly used translation for "The Bitcoin address to send the payment to" is:  
"接收付款的比特币地址"  
This explicitly mentions "Bitcoin address" and clarifies that it is the address to receive the payment.
```

```
        <source>Subtract fee from amount</source>
        <translation>从金额中减去交易费(U)</translation>
    
YES  
The added "(U)" in the Chinese translation is unnecessary and does not appear in the source text. It may confuse users. The translation should be concise and faithful to the source. A better translation is:  
从金额中减去手续费
```

```
        <source>Verify Message</source>
        <translation>验证消息签名(M)</translation>
    
YES  
The source text "Verify Message" is translated as "验证消息签名(M)". The translation adds "签名" (signature) and the shortcut key "(M)", which are not present in the source. The translation should be a direct rendering of "Verify Message" without extra terms or shortcut keys unless explicitly present in the source.

Correct translation:  
验证消息
```

```
        <source>Generated</source>
        <translation>挖矿生成</translation>
    
YES  
The English word "Generated" is general and can refer to anything produced or created. However, the translation "挖矿生成" specifically means "mined and generated," which is more specific to mining in a cryptocurrency context. If the original term is used broadly (e.g., "Generated" as in generated transaction, generated key, or generated data), this translation is too narrow and potentially misleading.  

Correct translation:  
生成
```

```
        <source>Show transaction details</source>
        <translation>显示交易详情(S)</translation>
    
YES  
The source text "Show transaction details" is a neutral command or label without any additional letters. The translation includes an extraneous "(S)" at the end, which is not present in the source and could confuse users. This "(S)" likely suggests a shortcut key or mnemonic in English, but in Chinese translations, such hints are typically not included or should match the source.

Correct translation:  
显示交易详情
```

```
        <source>Increase transaction fee</source>
        <translation>增加矿工费(F)</translation>
    
YES  
The source text "Increase transaction fee" does not specify "miner fee" explicitly; it refers generally to the transaction fee. The translation adds "矿工费(F)" which means "miner fee (F)", and the "(F)" is unexplained and unnecessary, possibly confusing. Moreover, the source does not mention "(F)" or any shortcut key.

A more accurate and neutral translation is:  
增加交易费用
```

```
        <source>Export</source>
        <translation>导出(E)</translation>
    
YES
The "(E)" is unnecessary and non-standard in Simplified Chinese UI translations, as keyboard shortcuts are typically not indicated in parentheses like this. The correct translation should simply be:

导出
```

```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>错误: 转储文件格式不正确。得到是"%s"，而预期本应得到的是 "format"。</translation>
    
YES  
The phrase "得到是"%s"" is awkward and unnatural in Chinese. A better translation would be more concise and clearer. Also, the whitespace around the colon ":" and before the quotes should be standardized.

Correct translation:  
错误：转储文件格式记录不正确。得到 "%s"，预期应为 "format"。
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多个洋葱路由绑定地址。对自动创建的洋葱服务用%s</translation>
    
YES  
The translation is incomplete and sounds unnatural. It misses a verb after "用%s" and lacks clarity. A more accurate and natural translation would be:  
"提供了多个洋葱绑定地址。自动创建的 Tor 洋葱服务将使用 %s。"
```

```
        <source>The block database contains a block which appears to be from the future. This may be due to your computer's date and time being set incorrectly. Only rebuild the block database if you are sure that your computer's date and time are correct</source>
        <translation>区块数据库包含未来的交易，这可能是由本机的日期时间错误引起。若确认本机日期时间正确，请重新建立区块数据库。</translation>
    
YES  
The word "交易" (transaction) is incorrect in this context; the source mentions a "block," not a "transaction." The correct term should be "区块" (block). Also, the translation slightly condenses the original and omits the conditional "Only rebuild the block database if you are sure..." as a conditional instruction; this reduces clarity. A more faithful translation preserving the original meaning would be:

区块数据库包含一个看似来自未来的区块。这可能是由于您的计算机日期和时间设置不正确所致。只有当您确定计算机的日期和时间是正确的，才重新构建区块数据库。
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>找零低于当前粉尘阈值时会被舍弃，并计入手续费，这些交易手续费就是在这种情况下产生的。</translation>
    
YES  
The translation adds explanatory content not present in the source and changes the original meaning. The source sentence states that "this is the transaction fee you may discard if change is smaller than dust at this level," which implies the fee applies if the change is discarded because it's dust-sized. The translation implies a different causal relationship and introduces phrases like "这些交易手续费就是在这种情况下产生的" ("these transaction fees are generated in such cases"), which is not in the original. Also, the source indicates "this is the transaction fee you may discard," but the translation says the change "will be discarded and counted into the fee," which slightly changes the meaning.

A more accurate and concise translation would be:  
找零金额若小于此层级的尘埃阈值，则可将该交易费用舍弃。
```

```
        <source>Error loading %s: Wallet requires newer version of %s</source>
        <translation>%s 加载错误:请升级到最新版 %s</translation>
    
YES  
The translation does not correctly reflect the structure and meaning of the source. The source says "Error loading %s: Wallet requires newer version of %s", meaning the first %s failed to load, and specifically because the wallet needs a newer version of the second %s.

The translation "%s 加载错误:请升级到最新版 %s" translates back as "%s loading error: please upgrade to the latest version of %s," which omits the connection to the wallet and changes the meaning from a specific error related to the wallet requiring a newer version.

A more accurate translation would be:  
"%s 加载错误：钱包需要较新版的 %s"
```

```
        <source>Error: Missing checksum</source>
        <translation>错误：跳过检查检验和</translation>
    
YES  
The translation "错误：跳过检查检验和" means "Error: skip checksum verification," which changes the meaning and is inaccurate. The source phrase "Error: Missing checksum" indicates a missing checksum, not skipping it.

Correct translation:  
错误：缺少校验和
```

```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
YES
The translation has a typo in "unit32_t" which should be "uint32_t". Also, it is more natural to say "解析为" rather than "作为…解析".

Correct translation:
错误：无法将版本号%u解析为uint32_t
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES  
The placement of "%s" is incorrect in the translation. It should directly follow "钱包" indicating the wallet name or identifier, not after "磁盘". Also, the extra "的" before "磁盘" is unnatural. The correct translation should clearly indicate that the data cannot be written to the disk for the specified wallet.

Correct translation:  
错误：无法将数据写入钱包 %s 的磁盘。
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES  
The translation incorrectly renders "minimum fee rate" as "最大手续费率" which means "maximum fee rate." The correct translation should refer to the minimum fee rate setting.

Correct translation:  
手续费率 (%s) 低于最小手续费率设置 (%s)
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>无效的 -onion 地址: '%s'</translation>
    
YES  
The original source mentions "Invalid -onion address or hostname: '%s'", but the translation only covers "无效的 -onion 地址: '%s'" ("Invalid -onion address: '%s'") and omits "hostname" (主机名). This omission reduces accuracy and completeness.

Correct translation:  
无效的 -onion 地址或主机名：'%s'
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES  
The translation contains a double negation "不不可," which is incorrect and confusing. The correct translation should be concise and clear:  
交易金额不得为负数
```
</details>
