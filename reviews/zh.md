# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh%5D%20low%20quality)


<!-- cache_translation_check_zh_128a0eb8353ea0b427c1f7fe543990e202b1544ea7a5ae22206b7f512fa24959 -->
```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>注意: 如果你忘记了你的钱包，你将会丢失你的&lt;b&gt;密码，并且会丢失你的&lt;/b&gt;比特币。</translation>
    
ERR
The translation is inaccurate and distorts the original meaning. The message should warn that if you lose your passphrase after encrypting your wallet, you will lose all your bitcoins. The current translation mistakenly says "if you forget your wallet" and reverses the emphasis within the <b> tags.

Correct translation:
注意：如果你加密了你的钱包并且忘记了密码，你将&lt;b&gt;丢失所有比特币&lt;/b&gt;！
```

<!-- cache_translation_check_zh_18cb2eafe9476d601cad613709995b7bd26eaa6f870c23a048355f97ee533bd6 -->
```
        <source>%1 GB</source>
        <translation>%1 GB (十億位元組)</translation>
    
ERR
The translation adds an explanatory note "(十億位元組)" ("(gigabyte)") that is not present in the original source text and is unnecessary in this context. It should preserve the format specifier and keep the translation literal.

Correct translation:
%1 GB
```

<!-- cache_translation_check_zh_05d277eecc64fb269e173be1d6818a6df68b8933aa0c02d9d12812631ca8f1c9 -->
```
        <source>Hide</source>
        <translation>躲</translation>
    
ERR
The translation "躲" means "to hide (oneself)" or "to dodge/evade," which is not the correct meaning in this UI context. The correct term for a UI control to "Hide" something is "隐藏".

Correct translation:
隐藏
```

<!-- cache_translation_check_zh_950cb28cc0f57eebf6fb6e99e761a355724df12da7463d87aeda770e4eaacc26 -->
```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
ERR
The translation is incorrect. The source says "Enable network activity," but the translation means "Disable network logging." It should instead indicate enabling, not disabling, network activity.

Correct translation:
啟用網絡活動
```

<!-- cache_translation_check_zh_708501aa83c3ed6c47c422f83102d8e9be25b9847079d344191965e14b243720 -->
```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
ERR
The translation "复制和数量" means "Copy and amount", which is incorrect. The word "和" ("and") is not present in the source and should not be in the translation. The format specifier is correctly omitted since there is none.

Correct translation:
复制金额
```

<!-- cache_translation_check_zh_1c4c30ec9f3a26f8d29357f182c97fe1209f83f2be6aaaebc67e5cd2859a0ede -->
```
        <source>External signer script path</source>
        <translation>外接簽證設備執行檔路徑(E)</translation>
    
ERR
The translation is problematic. The source text "External signer script path" refers to the path of a "script" used by an external signer (device or application), not an "executable file" nor specifically a "hardware signer" as implied. Also, the use of "簽證" (generally "visa") is incorrect, and there is an unnecessary "(E)" which isn't in the original.

Correct translation:
外部签名器脚本路径
```

<!-- cache_translation_check_zh_a07c6118a8d1e499f76e7c6670dd539d040212da28ec25d3a813231e56e9b6cf -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>軟體未編譯外接簽證功能所需的軟體庫(外接簽證必須有此功能)</translation>
    
ERR
The translation is inaccurate and awkward. The term "外接簽證" is not standard for "external signing" in this context—it may cause confusion. Also, the structure does not convey that the program was compiled without external signing support, and the parenthetical clarification is not natural.

Correct translation:
未编译外部签名支持（进行外部签名需要此支持）

Or, if using traditional Chinese:
未編譯外部簽名支援（需要此支援才能進行外部簽名）
```

<!-- cache_translation_check_zh_56b8225dec67e3fc39f92c0309eebb7e8c80b10b7e006ad5546daaaf877a2190 -->
```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
ERR
The translation is awkward and contains a duplicated word "观察" ("watch"). The phrase "仅观察地址" can be better rendered as "仅观察地址" or "仅用于观察的地址". Also, the word order could be improved for fluency.

Correct translation:
您在仅观察地址中的当前余额
```

<!-- cache_translation_check_zh_1ca8ed8a2e47dc5a6d18b065ef33944f8035f511e427fcc7b734bb5d9951176a -->
```
        <source>Outbound Feeler: short-lived, for testing addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to test the aliveness of known addresses.</extracomment>
        <translation>Outbound Feeler: 用於短暫，暫時 測試地址</translation>
    
ERR
The translation is unnatural, has spacing issues, and mixes English with Chinese unnecessarily. The phrase "暫時 測試地址" has incorrect spacing, and "用於短暫，暫時" is redundant and unclear. Also, "Outbound Feeler" should be translated or at least explained rather than left in English.

Correct translation:
短暂连接探测：用于测试已知地址是否可用
```

<!-- cache_translation_check_zh_294a6b69c8397bcbe46ef5b4e5f1d3feee9e2d9c3a4b4f1ce25d159ee9c964cc -->
```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
ERR
The translation is inaccurate and unclear. The English means a temporary outbound connection used to request addresses from a peer, but the translation mentions "temporarily testing addresses" which is not the same.

Correct translation:
外部地址获取：短时建立，用于请求地址
```

<!-- cache_translation_check_zh_708501aa83c3ed6c47c422f83102d8e9be25b9847079d344191965e14b243720 -->
```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
ERR
The translation "复制和数量" means "Copy and amount", which is incorrect. The word "和" ("and") is not present in the source and should not be in the translation. The format specifier is correctly omitted since there is none.

Correct translation:
复制金额
```

<!-- cache_translation_check_zh_070c587fbb4ed6d06fe006cbce66dae59f8480ae60cbd56f50e09c90fb4e8ad5 -->
```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
ERR  
The translation is understandable but the sentence structure is awkward, and "使用簽名。" is not correct; it looks like a translation error due to a misplaced period creating a fragment. The phrase "sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet" wasn't smoothly rendered. For clarity and fluency, "與PSBT相容的硬體錢包" is fine, but the connection and the action of "signing" is lost due to sentence break. Also, there should not be a period after "複製該交易".

Correct translation:  
請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後用例如離線的 %1 錢包或與 PSBT 相容的硬體錢包進行簽名。
```

<!-- cache_translation_check_zh_5682213c7071df73f2e9fc213f559a81292b1a0a139c5d644681abb371ee0353 -->
```
        <source>Subtract fee from amount</source>
        <translation>从金额中减去交易费(U)</translation>
    
ERR
The translation adds "(U)" at the end, which is not present in the original English source and could confuse users. Everything else is correct, but the extra "(U)" is unnecessary and potentially problematic.

Correct translation:
从金额中减去交易费
```

<!-- cache_translation_check_zh_708501aa83c3ed6c47c422f83102d8e9be25b9847079d344191965e14b243720 -->
```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
ERR
The translation "复制和数量" means "Copy and amount", which is incorrect. The word "和" ("and") is not present in the source and should not be in the translation. The format specifier is correctly omitted since there is none.

Correct translation:
复制金额
```

<!-- cache_translation_check_zh_c7322b733fb6e07eeb0c5a4f89faf9d956509351ec4b36c6ad2b25b6f1a6acf6 -->
```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
ERR
There are minor issues:
1. Inconsistent handling of the format specifiers "%s": in Chinese, there should be no space or line break before them, and the phrasing isn't very natural.
2. Unnecessary line break and whitespace in the translation.
3. "獲得" is less common for 'got' in this context; "实际为" is more idiomatic.

Correct translation:
錯誤：轉存檔案識別記錄不正確。實際為「%s」，預期為「%s」。
```

<!-- cache_translation_check_zh_78a3727db7b2c58049bfbe79faf011a77473fd002f75700a072bffc43d41b2bc -->
```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
ERR
There are several issues: 
1. The translation does not accurately reflect the original meaning; "多數" is awkward, and "路由綁定" is a literal translation not commonly used in this context.
2. The flow and specificity (e.g., "onion service") are lost.
3. There is inconsistent spacing (a space after the period).
4. "TOR" should be "Tor" for consistency.

Correct translation:
提供了多个Onion绑定地址。将使用%s作为自动创建的Tor onion服务。
```

<!-- cache_translation_check_zh_ba4b31fafa76b68ee6fefc8e8b4a7ed3d6fda25fd4bbf4dacf08fa9950112849 -->
```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
ERR
The translation omits part of the original meaning—specifically, it does not clearly translate "expected %s". Also, it lacks spacing for the format specifiers, which may make it less readable. The correct translation should be:

錯誤：轉存檔案的校驗和不匹配。計算得 %s，預期為 %s
```

<!-- cache_translation_check_zh_8b1135fb065982e6c8ee05d3643b9ebb06cd5f98d94108205cfa2556397adb94 -->
```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
ERR
There is a minor issue with the translation: "钱包的磁盘%s" is awkward and potentially ambiguous. The original English means writing to disk for wallet %s, not "the disk of wallet %s". Also, the format specifier %s should not be split from what it is associated with. 

Correct translation:
错误：无法将数据写入钱包 %s 的磁盘。
or even more naturally,
错误：无法将数据写入钱包 %s 的磁盘中。
```

<!-- cache_translation_check_zh_bfba5479a7879ceb3a8fe1594b0469d71773b62d6ea3df387a6f180158c2e8e0 -->
```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
ERR
The translation has two issues: 1) The format specifier %s is incorrectly placed at the beginning, which does not reflect the meaning of the English source. 2) There is a misplaced colon at the end, which does not exist in the source, and may be considered a formatting issue.

Correct translation:
移除交易失败: %s

Or, to match the English order literally:
移除交易时失败：%s
```

<!-- cache_translation_check_zh_3d9320bea10d5e3e022a19cfd842e427af4d3ea041c7f0b8f6e7b309e8193b04 -->
```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
ERR
The translation is inaccurate. The English phrase "change output" specifically refers to the "找零输出" (the output that returns change) in a Bitcoin transaction. The current translation incorrectly uses "尋找零輸出項" (which reads as "search for zero output item"), which distorts the meaning.

Correct translation:
交易找零输出索引超出范围
```

<!-- cache_translation_check_zh_76b1bd6861e77279c4c3f4a191a4d295d0696f1f0ea13e7ad0a7140d44da079c -->
```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
ERR
The translation introduces an erroneous "1" before "%s", which is not present in the original English source. This is likely a typo and could cause format specifier errors.

Correct translation:
钱包文件创建失败：%s
```
</details>

Number of issues: 21.
