# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh-Hans</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh-Hans%5D%20low%20quality)


```
        <source>Close</source>
        <translation>关闭(L)</translation>
    
YES
The translation "关闭(L)" includes the letter "(L)", which suggests a keyboard shortcut, but the original source "Close" does not indicate any shortcut. Normally, translations should not add or assume shortcuts unless specified in the source.

Correct translation:
关闭
```

```
        <source>Export</source>
        <translation>导出(E)</translation>
    
YES
The translation adds "(E)" which is not present in the original source. Unless part of a UI convention to show keyboard shortcuts (which should match the source), this is inaccurate.

Correct translation:
导出
```

```
        <source>Banned Until</source>
        <translation>在此之前保持封禁:</translation>
    
YES
The translation "在此之前保持封禁:" is not accurate. It would be better translated as "封禁到" or "封禁截止到". The given translation also adds an unnecessary colon and implies a continuous state rather than a deadline.

Correct translation:
封禁到
```

```
        <source>About %1</source>
        <translation>关于 %1 (A)</translation>
    
YES
The translation adds "(A)" at the end, which is not present in the source and is unnecessary. This alters the intended meaning.

Correct translation:
关于 %1
```

```
        <source>Load PSBT from file…</source>
        <translation>从文件加载PSBT(L)...</translation>
    
YES
The translation is mostly accurate but has a minor issue. The source uses an ellipsis ("…"), whereas the translation adds "(L)" which may be intended as a shortcut/hotkey indicator but isn't present in the source, and can cause user interface inconsistency if the original software does not assign "L" as a shortcut. Additionally, the order is better as "加载PSBT文件…" for naturalness.

Correct translation:
从文件加载PSBT…
```

```
        <source>Command-line options</source>
        <translation>命令行选项(C)</translation>
    
YES
The translation adds an unnecessary "(C)" at the end, which is not present in the source and could confuse users. In Chinese UI translation, such letter-in-parentheses are only used for access keys (快捷键) and should match the source. Here, there is no reason for "(C)".

Correct translation:
命令行选项
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>从剪贴板加载PSBT(C)...</translation>
    
YES
The translation adds "(C)" which is not present in the original source and changes the ellipsis from "…" (Unicode ellipsis) to "...". This introduces unnecessary content and alters the intended format.

Correct translation:
从剪贴板加载PSBT…
```

```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
YES
The translation "付款地址(S)" is problematic. The addition of "(S)" is unnecessary and incorrect in Chinese; plurals are generally not represented this way in Chinese. The correct translation should be:

Correct translation:
发送地址
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES
The translation "卸载钱包" means "uninstall wallet", which is incorrect for "Close wallet". The correct translation should be "关闭钱包".

Correct translation:
关闭钱包
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES
The translation "卸载钱包" means "uninstall wallet", which is incorrect for "Close wallet". The correct translation should be "关闭钱包".

Correct translation:
关闭钱包
```

```
        <source>Address</source>
        <translation>地址(A)</translation>
    
YES
The translation includes an extra "(A)" that is not in the original English text and is not standard for 'zh-Hans' translations of "Address." "(A)" might be used as an access key label in some UI systems, but unless clearly specified for this context, it should not be added.

Correct translation:
地址
```

```
        <source>Wallet</source>
        <translation>钱包(A)</translation>
    
YES
The translation adds "(A)" after 钱包, which is not present in the source and could cause confusion unless "A" is justified by a context (such as a shortcut key in menus, but this is not clear from the source). This addition is unnecessary and erroneous if not required.

Correct translation:
钱包
```

```
        <source>Third-party transaction URLs</source>
        <translation>第三方交易网址(T)</translation>
    
YES
The translation adds an extra "(T)" at the end, which is not present in the source and may confuse users. Also, "网址" (website URL) may be less appropriate than "链接" (link) or keeping it literal with "URL", depending on the technical context, but "网址" is generally acceptable.

Correct translation:
第三方交易网址
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES
There is a redundancy in the translation: "仅观察观察地址" repeats the word "观察" (watch). The correct phrase should be "仅观察地址" for "watch-only addresses."

Correct translation:
您当前在仅观察地址中的余额
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>“概况”标签页已启用隐私模式。要明文显示数值，请在设置中取消勾选“不明文显示数值”。</translation>
    
YES
The translation is inaccurate in the second sentence. The phrase "不明文显示数值" means "Do not display values in plaintext", which is not what the setting in the English source ("Mask values") specifies. The translation also reverses the meaning. Additionally, "Mask values" should be translated literally (e.g., “隐藏数值” or “遮罩数值”).

Correct translation:
“概况”标签页已启用隐私模式。要显示被隐藏的数值，请取消勾选“设置”->“隐藏数值”。
```

```
        <source>Peers</source>
        <translation>节点(P)</translation>
    
YES
The translation "节点(P)" is problematic. "Peers" in the context of Bitcoin should be translated as "节点" or "对等节点". The addition of "(P)" is unnecessary and could be confusing as it does not convey any meaning in the context of Chinese or Bitcoin.

Correct translation:
节点
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES
The translation "隐藏其他人的详细信息" means "Hide other people's detailed information," which does not accurately render "Peers" in the context of Bitcoin (where Peers refer to network nodes or connections, not "other people"). The correct translation should use “节点" (nodes) or “对等节点" (peers):

Correct translation:
隐藏节点详细信息
or
隐藏对等节点的详细信息
```

```
        <source>Network Traffic</source>
        <translation>网络流量(N)</translation>
    
YES
Including "(N)" in the translation is unnecessary and does not exist in the source text. It may confuse users or suggest the presence of a keyboard shortcut that does not exist in the original source.

Correct translation:
网络流量
```

```
        <source>1 hour</source>
        <translation>1 小时(H)</translation>
    
YES
The translation "1 小时(H)" unnecessarily adds "(H)" after "1 小时", which is not standard or needed in Chinese. The original simply says "1 hour", so the translation should match without the extra notation.

Correct translation:
1 小时
```

```
        <source>1 day</source>
        <translation>1 天(A)</translation>
    
YES
The translation includes an erroneous "(A)" after "1 天", which is not present in the original English source. This is an unnecessary addition and may confuse users.

Correct translation:
1 天
```

```
        <source>1 year</source>
        <translation>1 年(Y)</translation>
    
YES
The translation adds "(Y)" which is unnecessary and not present in the original English source. This could confuse users, as "年" already means "year" in Chinese.

Correct translation:
1 年
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>付款目的地址</translation>
    
YES
The translation "付款目的地址" is acceptable in some contexts, but it lacks specificity and does not explicitly mention "Bitcoin" nor is it a direct translation of the source. For clarity and accuracy, especially in a technical/Bitcoin context, it is better to specify "比特币地址" as in the source.

Correct translation:
比特币付款接收地址
```

```
        <source>Subtract fee from amount</source>
        <translation>从金额中减去交易费(U)</translation>
    
YES
The translation adds the "(U)" at the end, which is not present in the source and could be erroneous, as it may confuse users. Everything else is accurate.

Correct translation:
从金额中减去交易费
```

```
        <source>Verify Message</source>
        <translation>验证消息签名(M)</translation>
    
YES
The translation adds "签名" (signature) and "(M)" (possibly a shortcut), which are not present in the original English text "Verify Message". This introduces erroneous content.

Correct translation:
验证消息
```

```
        <source>Generated</source>
        <translation>挖矿生成</translation>
    
YES
The translation "挖矿生成" (mined/generated from mining) is too specific and adds information ("挖矿"/mining) not present in the source. The English word "Generated" could refer to more than just mined coins and should be translated more neutrally unless context absolutely requires otherwise.

Correct translation:
已生成
```

```
        <source>Increase transaction fee</source>
        <translation>增加矿工费(F)</translation>
    
YES
The translation "增加矿工费(F)" is problematic. The term "矿工费" is a colloquial Chinese term for "miner's fee," which is understandable but not technically accurate for "transaction fee," which should be "交易手续费" or simply "手续费". The addition of "(F)" is unexplained and not present in the source, which introduces unnecessary content.

Correct translation:
增加交易手续费
```

```
        <source>Export</source>
        <translation>导出(E)</translation>
    
YES
The translation adds "(E)" which is not present in the original source. Unless part of a UI convention to show keyboard shortcuts (which should match the source), this is inaccurate.

Correct translation:
导出
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多个洋葱路由绑定地址。对自动创建的洋葱服务用%s</translation>
    
YES
The translation is mostly accurate but has minor issues:
1. The sentence ending is abrupt and missing a proper period.
2. The phrase "洋葱服务" is understandable but "Tor 洋葱服务" would be clearer for Chinese readers.
3. The structure “对自动创建的洋葱服务用%s” is a bit awkward; it’s better as “将使用 %s 作为自动创建的 Tor 洋葱服务的绑定地址。”
4. Ensure there is a space before the %s as in the English original.

Correct translation:
提供了多个洋葱路由绑定地址。将使用 %s 作为自动创建的 Tor 洋葱服务的绑定地址。
```

```
        <source>The block database contains a block which appears to be from the future. This may be due to your computer's date and time being set incorrectly. Only rebuild the block database if you are sure that your computer's date and time are correct</source>
        <translation>区块数据库包含未来的交易，这可能是由本机的日期时间错误引起。若确认本机日期时间正确，请重新建立区块数据库。</translation>
    
YES
The translation is problematic. The source says "contains a block which appears to be from the future", but the translation says "包含未来的交易" ("contains a transaction from the future"), which changes "block" to "transaction", which is inaccurate. Also, the translation misses the nuance about rebuilding only if you're sure the date/time is correct; the condition is reversed and less clear.

Correct translation:
区块数据库包含一个看似来自未来的区块，这可能是由于您的计算机日期和时间设置不正确所致。只有在确信您的计算机日期和时间正确时，才应重建区块数据库。
```

```
        <source>Error: Missing checksum</source>
        <translation>错误：跳过检查检验和</translation>
    
YES  
The translation is problematic. The source means "Missing checksum", but the Chinese sentence means "Skipped checking the checksum", which is inaccurate.

Correct translation:  
错误：缺少校验和
```

```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
YES
There is a typo in the translation: "unit32_t" should be "uint32_t". Additionally, there should be a space between "版本号" and "%u" to match conventions, though this is optional in Chinese.

Correct translation:
错误：无法将版本号 %u 解析为 uint32_t
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES  
The translation is inaccurate. The source says "lower than the minimum fee rate setting," but the translation says "低于最大手续费率设置," which means "lower than the maximum fee rate setting." The word "最大" means "maximum" and is incorrect here; it should be "最小," meaning "minimum."

Correct translation:  
手续费率 (%s) 低于最小手续费率设置 (%s)
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES
The translation contains a redundancy: "不不可为负数" means "must not not be negative", with a double negation ("不不可" instead of "不可").
 
Correct translation:
交易金额不可为负数
```
</details>

Number of issues: 33.
