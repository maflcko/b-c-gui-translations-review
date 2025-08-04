# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh_CN</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh_CN%5D%20low%20quality)


```
        <source>About %1</source>
        <translation>关于 %1 (A)</translation>
    
YES, The translation is problematic. The English text "About %1" translates to "关于 %1" in Chinese. The addition of "(A)" after the translated text is not present in the source and appears to be extraneous.

Correct translation: 关于 %1
```

```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
YES - The translation adds an unnecessary "(S)" which is not present in the source text.
Correct translation: 付款地址
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES, The translation "卸载钱包" (unload wallet) is not an accurate translation of "Close wallet". A more appropriate translation would be "关闭钱包" (close wallet).
关闭钱包
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>显示节点标签</translation>
    
YES, "标签" (biāoqiān) usually translates to "label" or "tag". While it's sometimes used for UI tabs (as in "标签页"), the more accurate and standard term for a UI "tab" is "选项卡" (xuǎnxiàngkǎ). Using "节点" for "Peers" is acceptable in this context.

Corrected translation:
显示节点选项卡
```

```
        <source>After Fee:</source>
        <translation>加上交易费用后:</translation>
    
YES - The translation is incorrect. The source text "After Fee:" means "in the state of being after the fee has been deducted" or "following the deduction of the fee". The provided translation "加上交易费用后:" which means "After adding the transaction fee:". This is the opposite of the original meaning. The correct translation should be "扣除费用后:" which means "After deducting the fee:".

Correct translation: 扣除费用后:
```

```
        <source>Lock unspent</source>
        <translation>锁定未花费(O)</translation>
    
YES. The translation includes an extraneous character "(O)" which is not present in the source text.

NO.
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES, The translation "卸载钱包" (unload wallet) is not an accurate translation of "Close wallet". A more appropriate translation would be "关闭钱包" (close wallet).
关闭钱包
```

```
        <source>Spend unconfirmed change</source>
        <translation>动用尚未确认的找零资金(S)</translation>
    
YES, The translation is problematic because of the extraneous "(S)" at the end, which is likely a remnant from the English source text and not part of the intended translation.

Correct translation: 动用尚未确认的找零资金
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES: The translation contains a redundancy ("watch-only addresses" translated to "仅观察观察地址").
Correct translation: 您在观察地址中的当前余额
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES, The translation is problematic because it does not accurately convey the meaning of "Peers Detail" in the context of Bitcoin. "Peers Detail" refers to the details of other nodes in the Bitcoin network, not "other people." A more accurate translation would be "隐藏节点详细信息" or "隐藏节点详情".

YES, 隐藏节点详情
```

```
        <source>1 day</source>
        <translation>1 天(A)</translation>
    
YES - The translation "1 天(A)" is incorrect. The "(A)" appears to be an extraneous character that does not belong in the translation of "1 day".
Correct translation: 1 天
```

```
        <source>After Fee:</source>
        <translation>加上交易费用后:</translation>
    
YES - The translation is incorrect. The source text "After Fee:" means "in the state of being after the fee has been deducted" or "following the deduction of the fee". The provided translation "加上交易费用后:" which means "After adding the transaction fee:". This is the opposite of the original meaning. The correct translation should be "扣除费用后:" which means "After deducting the fee:".

Correct translation: 扣除费用后:
```

```
        <source>Subtract fee from amount</source>
        <translation>从金额中减去交易费(U)</translation>
    
YES, The translation uses a placeholder "(U)" which is not present in the source text and is not relevant in the context of Bitcoin. The correct translation should be: 从金额中减去交易费
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1/未确认</translation>
    
YES: The translation incorrectly translates "unconfirmed" to "未确认" (unconfirmed) when the source indicates a transaction confirmed in at least one block but less than six. The correct translation should reflect this partially confirmed status.

Correct translation: %1/部分确认
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>出站连接被限制为仅使用 Tor (-onlynet=onion)，但是未提供到达 Tor 网络的代理：没有提供 -proxy=, -onion= 或 -listenonion 参数</translation>
    
YES - The translation incorrectly omits the equals signs after the parameters in the explanation part.
出站连接被限制为仅使用 Tor (-onlynet=onion)，但是未提供到达 Tor 网络的代理：没有提供 -proxy=, -onion= 或 -listenonion 参数
```

```
        <source>Error: Missing checksum</source>
        <translation>错误：跳过检查检验和</translation>
    
YES, The translation is problematic as it mistranslates "checksum" as "跳过检查检验和" which means "skip check checksum". The correct translation for "checksum" in this context would be "校验和".
错误：缺少校验和
```

```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
YES, The word "unit32_t" in the translation is a typo and should be "uint32_t".
错误：无法把版本号%u作为uint32_t解析
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES: The translation is grammatically incorrect in Chinese. The "of wallet %s" part should be placed before "disk".

Correct translation: 错误：无法将数据写入钱包 %s 的磁盘。
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES, the translation has an incorrect word order. The correct translation should be: %s删除交易失败
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES: The translation incorrectly states "maximum fee rate" instead of "minimum fee rate".
Correct translation: 手续费率 (%s) 低于最低手续费率设置 (%s)
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES, "不不可" is a double negative, which should be "不可".
Transaction amounts must not be negative - 交易金额不可为负数
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES, The format specifier %s was incorrectly translated as 1%s.
Wallet file creation failed: %s
```
</details>
