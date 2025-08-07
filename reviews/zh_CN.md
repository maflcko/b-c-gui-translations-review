# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh_CN</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh_CN%5D%20low%20quality)


```
        <source>About %1</source>
        <translation>关于 %1 (A)</translation>
    
YES
The translation adds "(A)" which is not present in the English source text, making it inaccurate. This is unnecessary and could be confusing.

Correct translation:
关于 %1
```

```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
YES
The translation adds "(S)" which is not present in the source, and which could be confusing or nonstandard in Chinese translations. The standard translation should be straightforward and without extra characters.

Correct translation:
发送地址
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES
The translation of "Close wallet" as "卸载钱包" is incorrect. "卸载钱包" means "uninstall wallet," which is not the same as "close wallet." The correct translation should be:

关闭钱包
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>显示节点标签</translation>
    
YES
The translation "显示节点标签" means "Show node label/tab", but "Peers tab" specifically refers to the tab for "Peers" (connected peers), not the node in general. "节点" means "node", while "Peers" should be translated as "节点" (peers/connected nodes) or more commonly "连接节点" or just "节点" in the context of Bitcoin, but to be accurate and consistent, it's often translated as "节点" but "Peers" specifically is usually "连接" or "连接节点" or simply "节点" when used as a tab name.

However, to distinguish clearly, the correct translation for "Show Peers tab" should be:
显示“节点”标签页

or, if the software calls the tab literally "Peers" instead of "节点":
显示“Peers”标签页

So the translation is misleading and should be improved.

Correct translation:
显示“节点”标签页
```

```
        <source>Lock unspent</source>
        <translation>锁定未花费(O)</translation>
    
YES
The translation adds "(O)" at the end, which is not present in the source. This "(O)" is likely a mistaken mnemonic/shortcut key, not indicated in the English source. Otherwise, the translation "锁定未花费" is accurate.

Correct translation:
锁定未花费
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES
The translation of "Close wallet" as "卸载钱包" is incorrect. "卸载钱包" means "uninstall wallet," which is not the same as "close wallet." The correct translation should be:

关闭钱包
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES
There is a redundancy in the phrase "仅观察观察地址" ("watch-only watch address") and awkward wording. The correct and natural translation should be:

Correct translation:
您当前在仅观察地址中的余额
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES
The Chinese translation "隐藏其他人的详细信息" means "Hide other people's detailed information," which is incorrect. The correct translation for "Hide Peers Detail" in the context of Bitcoin (referring to peer nodes) should be:

隐藏节点详细信息

This translates back as "Hide node detail/information," which is in line with the intended meaning regarding network peers.
```

```
        <source>1 day</source>
        <translation>1 天(A)</translation>
    
YES
The translation "1 天(A)" contains an unnecessary "(A)", which is not present in the original English source and appears to be erroneous. There is also no whitespace format issue.

Correct translation:
1 天
```

```
        <source>Subtract fee from amount</source>
        <translation>从金额中减去交易费(U)</translation>
    
YES
The translation adds "(U)", which is not present in the original text and could confuse users. The rest of the translation is otherwise accurate.

Correct translation:
从金额中减去交易费
```

```
        <source>Error: Missing checksum</source>
        <translation>错误：跳过检查检验和</translation>
    
YES  
The translation is problematic. The source says "Error: Missing checksum" (meaning the checksum is not present), but the translation says "错误：跳过检查检验和" ("Error: skipped checksum"), which means the checksum was intentionally skipped. This changes the meaning.

Correct translation:  
错误：缺少校验和
```

```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
YES
There is a typo in "unit32_t"; it should be "uint32_t" (the 'i' and 'n' are inverse). Also, there should be a space between the Chinese text and the format specifier for better readability.

Correct translation:
错误：无法将版本号 %u 解析为 uint32_t
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES
There is a slight word order issue. The phrase "写入钱包的磁盘%s" translates to "write to the wallet's disk %s", which can be misleading because %s is a placeholder for the wallet's name, not a particular disk. Also, the period should match the style (no period in the English).

Correct translation:
错误：无法将数据写入钱包 %s 的磁盘
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES
The placement of %s is incorrect. In the English source, "%s" is at the end of the sentence, serving as extra information (usually an error message). In the Chinese translation, "%s" is at the beginning, which is unidiomatic and may confuse users. Also, the colon at the end is not necessary unless more content follows.

Correct translation:
删除交易时失败: %s
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES
The translation incorrectly states "低于最大手续费率设置" ("lower than the maximum fee rate setting") instead of "低于最小手续费率设置" ("lower than the minimum fee rate setting"). The word "最大" means "maximum", but "minimum" should be "最小".

Correct translation:
手续费率（%s）低于最小手续费率设置（%s）
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES
The translation contains a double negative "不不可", which is erroneous. It should be "交易金额不可为负数" or "交易金额不得为负数".

Correct translation:
交易金额不可为负数
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES  
The translation incorrectly includes "1" before %s in "钱包文件创建失败：1%s", which appears to be an erroneous character. It should be "钱包文件创建失败：%s" with the %s format specifier directly following the colon.

Correct translation:
钱包文件创建失败：%s
```
</details>

Number of issues: 17.
