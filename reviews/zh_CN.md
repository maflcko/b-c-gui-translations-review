# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh_CN</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh_CN%5D%20low%20quality)


```
        <source>About %1</source>
        <translation>关于 %1 (A)</translation>
    
YES
The translation includes an extraneous " (A)" at the end, which is not present in the source and could cause confusion or formatting issues.

Correct translation:
关于 %1
```

```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
YES  
The source text "Sending addresses" refers to addresses used for sending Bitcoin, typically meaning "发出地址" or "发送地址" (addresses from which payments are sent). The translation "付款地址(S)" means "payment address(es)" and adds "(S)" which is not present in the source and appears as an unwanted extraneous character. Also, "付款地址" usually means addresses for payment (receiving payment), which may not capture the nuance of "Sending addresses."

Correct translation:  
发送地址
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES  
The translation "卸载钱包" means "uninstall wallet," which is incorrect in this context. The source text "Close wallet" means to close or shut the wallet application or interface, not to uninstall it. A more accurate translation would be:  
关闭钱包
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>显示节点标签</translation>
    
YES  
The translation "显示节点标签" literally means "Show node label/tab," but a more accurate and idiomatic translation for "Show Peers tab" should use "对等节点" (peers) and "标签页" for tab. Also, "标签" alone is ambiguous and less common for UI tabs; "标签页" or "选项卡" is more standard.

Correct translation:  
显示对等节点标签页
```

```
        <source>Lock unspent</source>
        <translation>锁定未花费(O)</translation>
    
YES  
The "(O)" at the end of the translation is extraneous and does not appear in the source text. It should be removed to match the source accurately.  

Correct translation:  
锁定未花费
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES  
The translation "卸载钱包" means "uninstall wallet," which is incorrect in this context. The source text "Close wallet" means to close or shut the wallet application or interface, not to uninstall it. A more accurate translation would be:  
关闭钱包
```

```
        <source>Spend unconfirmed change</source>
        <translation>动用尚未确认的找零资金(S)</translation>
    
YES  
The translation adds an extraneous "(S)" at the end, which is not present in the source and may confuse users. Also, "动用" is acceptable, but the more common and clearer translation for "Spend" in this Bitcoin context might be "使用". The rest is accurate and clear.

Correct translation:  
动用尚未确认的找零资金
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES  
The translation contains a redundant repetition of "观察" ("watch") and is somewhat unnatural. The phrase "仅观察观察地址" should be "仅观察地址" to correctly mean "watch-only addresses."

Correct translation:  
您当前在仅观察地址中的余额
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES
The translation "隐藏其他人的详细信息" means "Hide other people's detailed information," which introduces an unintended meaning. The source "Hide Peers Detail" likely refers to hiding the details of network peers or nodes, not necessarily "other people." A more accurate translation would be:

隐藏节点详细信息
```

```
        <source>1 day</source>
        <translation>1 天(A)</translation>
    
YES  
The translation includes an unnecessary "(A)" which is not present in the source text and is not appropriate here. The correct translation should simply be:  
1 天
```

```
        <source>Subtract fee from amount</source>
        <translation>从金额中减去交易费(U)</translation>
    
YES  
The extra "(U)" in the translation is unnecessary and does not appear in the source. It should be removed to maintain accuracy and clarity. The correct translation is:  
从金额中减去交易费
```

```
        <source>Error: Missing checksum</source>
        <translation>错误：跳过检查检验和</translation>
    
YES  
The translation is inaccurate and misleading. The English source indicates a missing checksum error, but the Chinese translation means "Error: skip checksum verification," which is incorrect.

Correct translation:  
错误：缺少校验和
```

```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
YES  
The translation contains a typo in "unit32_t" which should be "uint32_t". Also, typically in Chinese technical translations, there should be a space before and after the format specifier %u for better readability, but it's optional. The phrase "把版本号" is acceptable but can be more concise.

Correct translation:  
错误：无法将版本号 %u 解析为 uint32_t
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES  
The placement of %s is incorrect. The %s placeholder is meant for the wallet identifier and should appear immediately after "钱包", not after "磁盘". The phrase "钱包的磁盘%s" is awkward and misleading. Also, the original English does not imply the disk belongs to the wallet but that the data cannot be written to disk for that wallet.

Correct translation:  
错误：无法将数据写入钱包 %s 的磁盘。
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES
The word order and punctuation in the translation are incorrect. The source means a failure occurred while removing the transaction identified by %s, so %s should be placed after "删除交易" and before "失败", without the colon at the end. Also, the space before the colon is unnecessary and incorrect.

Correct translation:
删除交易 %s 失败
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES  
The translation incorrectly renders "minimum fee rate" as "最大手续费率" which means "maximum fee rate." The correct translation should reflect "minimum" instead of "maximum."  

Correct translation:  
手续费率 (%s) 低于最小手续费率设置 (%s)
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES  
The translation contains a double negative ("不不可"), which is incorrect and confusing. The correct translation should be simple and clear:  
交易金额不得为负数
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES  
The translation adds an extraneous '1' before the format specifier %s, which is not present in the source and is incorrect. The format specifier %s must be copied exactly, without any extra characters preceding it.

Correct translation:  
钱包文件创建失败：%s
```
</details>
