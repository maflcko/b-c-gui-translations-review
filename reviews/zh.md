# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh%5D%20low%20quality)


```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>注意: 如果你忘记了你的钱包，你将会丢失你的&lt;b&gt;密码，并且会丢失你的&lt;/b&gt;比特币。</translation>
    
YES
The translation reverses the meaning and confuses key elements: it says "If you forget your wallet, you will lose your password, and lose your bitcoins," which is incorrect. The original means "If you encrypt your wallet and lose your passphrase, you will LOSE ALL YOUR BITCOINS."

Correct translation:
注意：如果你加密了钱包但丢失了密码短语，&lt;b&gt;你将失去所有比特币&lt;/b&gt;！
```

```
        <source>%1 GB</source>
        <translation>%1 GB (十億位元組)</translation>
    
YES  
The translation adds "(十億位元組)" which is an explanation of "GB" (gigabyte) and is not present in the source text. The source is just "%1 GB" without any explanatory text, so the translation should be equally concise and match the source exactly.  

Correct translation:  
%1 GB
```

```
        <source>Hide</source>
        <translation>躲</translation>
    
YES  
The Chinese translation "躲" is not appropriate in this context. "Hide" in UI context is usually translated as "隐藏" which means "to hide or conceal" in a neutral and standard way. "躲" generally means "to hide oneself" or "to avoid," and sounds informal or contextually odd for UI elements.  

Correct translation:  
隐藏
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES  
The source means "Enable network activity," but the translation means "Disable network logging." This is incorrect and opposite in meaning.

Correct translation:  
开启网络活动
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES  
The translation "复制和数量" literally means "copy and amount," which is incorrect. The source phrase "Copy amount" means to copy the amount value, so the translation should be concise and accurate. The correct translation is:  
复制金额
```

```
        <source>Copy after fee</source>
        <translation>複製計費後金額</translation>
    
YES  
The translation "複製計費後金額" literally means "copy the amount after charging the fee," which is somewhat unclear and not idiomatic. In the Bitcoin context, "Copy after fee" typically means "copy the amount after fee deduction" or "copy the value after fee." A more concise and natural Chinese translation would be:

复制手续费后金额

This translates as "copy the amount after the fee." Also, using simplified Chinese characters (复制) is generally preferred unless the context is strictly Traditional Chinese, but since the original translation used traditional (複製), you can keep that as:

複製手續費後金額

This version is clear, accurate, and maintains the intended meaning.
```

```
        <source>Start %1 on system login</source>
        <translation>系统登入时启动 %1 (S)</translation>
    
YES  
The translation adds "(S)" at the end, which does not appear in the source and is unnecessary. Also, "系统登入" can be better expressed as "系统登录" which is more commonly used in simplified Chinese for "system login."

Correct translation:  
系统登录时启动 %1
```

```
        <source>External signer script path</source>
        <translation>外接簽證設備執行檔路徑(E)</translation>
    
YES
The translation "外接簽證設備執行檔路徑(E)" is inaccurate and contains problematic content. It translates back roughly as "external authentication device executable path (E)" which is not a correct rendition of "External signer script path." Specifically, "簽證設備" means "visa device" or "authentication device" and does not fit the context of Bitcoin external signer script.

A better translation would be:
外部签名脚本路径
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>軟體未編譯外接簽證功能所需的軟體庫(外接簽證必須有此功能)</translation>
    
YES  
The translation incorrectly uses "軟體庫" (software library) which is not present in the source text. The source states "Compiled without external signing support," referring to a compilation setting or feature, not software libraries. Also, "簽證" means "visa" in Chinese and is not appropriate here; it should be "簽名" for "signing." The phrase "外接簽證" is misleading and should be "外部簽名" or "外部簽署."

Correct translation:  
未編譯外部簽名功能支持（外部簽名所必需）
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES  
The translation has a redundancy in "仅观察观察地址" ("watch-only watch addresses"). The correct phrase for "watch-only addresses" should be "仅观察地址".  

Correct translation:  
您当前在仅观察地址中的余额
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>仅观察地址中尚未成熟的挖矿收入余额:</translation>
    
YES  
The translation includes an unnecessary colon (:) at the end which is not present in the source. Also, "仅观察地址" is not a natural or complete way to say "in watch-only addresses." A better phrasing would be "仅观察地址中的" or "仅限观察地址的".  
Correct translation:  
仅观察地址中尚未成熟的挖矿余额
```

```
        <source>Outbound Feeler: short-lived, for testing addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to test the aliveness of known addresses.</extracomment>
        <translation>Outbound Feeler: 用於短暫，暫時 測試地址</translation>
    
YES  
The translation is somewhat awkward and contains unnecessary spacing and redundancy. The English phrase is concise and professional, while the translation has a mix of English and Chinese with awkward phrasing ("用於短暫，暫時 測試地址" is redundant—"短暫" and "暫時" mean similar things, and spacing before "測試" is incorrect). Also, "Outbound Feeler" is left untranslated; it might be better to translate it or provide a clearer explanation fully in Chinese for clarity.

A better translation might be:  
"出站探测连接：短暂建立，用于测试地址是否可用"  

This keeps the meaning clear and natural in Chinese.

Correct translation:  
<translation>出站探测连接：短暂建立，用于测试地址是否可用</translation>
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
YES  
The translation has issues with word choice and spacing. The phrase "用於短暫，暫時 測試地址" is awkward and does not accurately convey "short-lived, for soliciting addresses." Also, there is an unnecessary space before "測試地址". The original meaning implies a temporary outbound connection used to request addresses, not "testing addresses."  

Correct translation:  
Outbound 地址获取：短暂，用于请求地址
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES  
The translation "复制和数量" literally means "copy and amount," which is incorrect. The source phrase "Copy amount" means to copy the amount value, so the translation should be concise and accurate. The correct translation is:  
复制金额
```

```
        <source>Copy after fee</source>
        <translation>複製計費後金額</translation>
    
YES  
The translation "複製計費後金額" literally means "copy the amount after charging the fee," which is somewhat unclear and not idiomatic. In the Bitcoin context, "Copy after fee" typically means "copy the amount after fee deduction" or "copy the value after fee." A more concise and natural Chinese translation would be:

复制手续费后金额

This translates as "copy the amount after the fee." Also, using simplified Chinese characters (复制) is generally preferred unless the context is strictly Traditional Chinese, but since the original translation used traditional (複製), you can keep that as:

複製手續費後金額

This version is clear, accurate, and maintains the intended meaning.
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES
The translation is somewhat fragmented and awkward, particularly the phrase "然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。" which roughly translates to "then use the signature. offline %1 wallet or PSBT-compatible hardware wallet." It seems to have an unnatural break and lacks clarity.

Correct translation:
請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用例如離線的 %1 錢包或與 PSBT 相容的硬體錢包進行簽名。
```

```
        <source>Subtract fee from amount</source>
        <translation>从金额中减去交易费(U)</translation>
    
YES  
The translation adds "(U)" at the end, which is not present in the source and appears unnecessary or erroneous. The original source simply states "Subtract fee from amount" without any extra notation. The correct translation should be concise and accurate without added characters.

Correct translation:  
从金额中减去手续费
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES  
The translation "复制和数量" literally means "copy and amount," which is incorrect. The source phrase "Copy amount" means to copy the amount value, so the translation should be concise and accurate. The correct translation is:  
复制金额
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
YES
The translation has unnecessary line breaks and missing quotation marks around the format specifiers "%s". The quotes should be preserved as in the source, and the format specifiers should be inline without whitespace or line breaks.

Correct translation:
錯誤：轉存檔案識別記錄不正確。獲得「%s」，預期「%s」。
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES  
The translation has issues with clarity, completeness, and spacing. It does not fully convey the meaning of the source sentence, which indicates multiple onion bind addresses are provided and that one (%s) will be used for the automatically created Tor onion service. Also, there is an unnecessary space after the full stop.

Correct translation:  
提供了多个洋葱绑定地址。自动创建的 Tor 洋葱服务将使用 %s。
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
YES  
The translation is inaccurate and incomplete. It omits the "expected %s" part and the overall sentence structure is awkward.

Correct translation:  
錯誤：轉存檔案的校驗和不匹配。計算值為 %s，預期值為 %s
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES  
The Chinese translation reverses the intended meaning by implying that the disk belongs to the wallet ("%s" seems to be part of wallet, not disk), and the placement of %s is incorrect. It should clearly state that writing data to the disk associated with the wallet %s failed. Also, the period at the end is unnecessary in this context.

Correct translation:  
错误：无法将数据写入钱包 %s 的磁盘
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES
The translation improperly places the placeholder %s at the beginning and adds a colon and trailing space at the end, which does not match the original sentence structure. The source implies that the failure occurred while removing a transaction identified by %s, so %s should replace "transaction" or be correctly positioned in the sentence.

Correct translation:
删除交易 %s 失败
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES  
The translation "交易尋找零輸出項超出範圍" is inaccurate and somewhat confusing. It literally means "Transaction searching zero output item out of range," which does not correctly convey "Transaction change output index out of range." The correct translation should specifically mention "change output index" (找零輸出索引) and "out of range" (超出範圍).

Correct translation:  
交易找零輸出索引超出範圍
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES
The translation contains an erroneous character '1' before the format specifier '%s', which does not exist in the source text. The correct translation should omit this extraneous character.

Correct translation:
钱包文件创建失败：%s
```
</details>
