# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bzh%5D%20request)



<details><summary>zh</summary>


<!-- cache_translation_check_zh_18cb2eafe9476d601cad613709995b7bd26eaa6f870c23a048355f97ee533bd6 -->
```
        <source>%1 GB</source>
        <translation>%1 GB (十億位元組)</translation>
    
ERR
The translation adds an explanatory note "(十億位元組)" ("(gigabyte)") that is not present in the original source text and is unnecessary in this context. It should preserve the format specifier and keep the translation literal.

Correct translation:
%1 GB
```

<!-- cache_translation_check_zh_4d7048e3223a6608542d9e88f361c2e18678e6e32a584bc5ae95f8b3d9d13941 -->
```
        <source>Copy &amp;amount</source>
        <translation>複製金額 &amp;amount</translation>
    
ERR
The translation incorrectly retains the English word "amount" alongside the Chinese translation. The shortcut key indicator '&' should be placed before the corresponding Chinese character or the English word should be removed.

Correct translation:
複製金額(&;A)
```

<!-- cache_translation_check_zh_f568c8e4ca957eadfdf7e283377c5fc85d3009fddd6ffff42a1e15c5865ca108 -->
```
        <source>&amp;Unlock unspent</source>
        <translation>解鎖未花費的</translation>
    
ERR
The translation is missing the shortcut key indicator '&' which was present in the source text.

Correct translation:
解鎖未花費的(&U) or &解鎖未花費的
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

<!-- cache_translation_check_zh_4d7048e3223a6608542d9e88f361c2e18678e6e32a584bc5ae95f8b3d9d13941 -->
```
        <source>Copy &amp;amount</source>
        <translation>複製金額 &amp;amount</translation>
    
ERR
The translation incorrectly retains the English word "amount" alongside the Chinese translation. The shortcut key indicator '&' should be placed before the corresponding Chinese character or the English word should be removed.

Correct translation:
複製金額(&;A)
```

<!-- cache_translation_check_zh_6b6c6afbece467e2f128637730075f08ff6aa1ca33439b5a4828df89267fe6bc -->
```
        <source>Copy &amp;raw transaction</source>
        <translation>複製交易(原始)</translation>
    
ERR
The ampersand (&amp;) indicating the shortcut key is missing in the translation, but it should exist exactly once according to the rules. Also, the suggested shortcut key should be present.

Correct translation:
复制(&R)交易原始数据

Or, if you want to stick closer to the original placement:

复制原始(&R)交易

Or, if the shortcut key can be anywhere as per context:

复制原始交易(&R)

Explanation: The shortcut key (usually specified with & plus a letter, corresponding to a keyboard accelerator) must be preserved exactly once in the translation. The provided translation omits it.
```

<!-- cache_translation_check_zh_ad835176286ec5001b2d46ca1cecbac97741bc5c25c342e04972405d7b6424e8 -->
```
        <source>&amp;Show transaction details</source>
        <translation>顯示交易明細</translation>
    
ERR
The translation is missing the '&' which indicates the shortcut key in the source. It should appear exactly once in the translation.

Correct translation:
&顯示交易明細
```

<!-- cache_translation_check_zh_e21c2f6290c8559f0fc42bb3c784a6a516fa3fe5c8b77d55fb3a33fc91446925 -->
```
        <source>Increase transaction &amp;fee</source>
        <translation>增加礦工費(&amp;fee)</translation>
    
ERR
The ampersand (&) should exist exactly once and is used to indicate the shortcut key. In Chinese translations, it is usual to place it before the shortcut character in the translation, not to include the English word 'fee' in parentheses. Also, "矿工费" is the standard for "transaction fee". The proper translation should be:

增加交易手续费(&F)
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

<!-- cache_translation_check_zh_90fda8f6932228d174e380ed1c7df7be7ae98d00ff1e42c56766226c0f6bb80a -->
```
        <source>Option '-checkpoints' is set but checkpoints were removed. This option has no effect.</source>
        <translation>选项“-checkpoints”已设置，但检查点已被移除。该选项不再生效。 </translation>
    
ERR
The translation is accurate, but there is an extra trailing space at the end. Also keep punctuation as-is. 

Corrected translation (remove trailing space):
选项“-checkpoints”已设置，但检查点已被移除。该选项不再生效。
```

<!-- cache_translation_check_zh_fc44b6029c7dbac45686cc79b705b8c897f4c829f9f3f5057b0a8d2f641e4b4e -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>修剪：上次钱包同步超出了已修剪的数据范围。您需要执行“-reindex”（对于已修剪节点，需要重新下载整个区块链）。 </translation>
    
ERR
The translation is accurate and appropriate, but there is a minor formatting issue: an extra space before the closing tag (trailing whitespace). Remove the trailing space.

Corrected translation:
修剪：上次钱包同步超出了已修剪的数据范围。您需要执行“-reindex”（对于已修剪节点，需要重新下载整个区块链）。
```

<!-- cache_translation_check_zh_212c3af68e90ae4a89c435e0fc3e60da04c4a65ab354a77723b7b670db8e3821 -->
```
        <source>Can't spend unconfirmed version %d pre-selected input with a version 3 tx</source>
        <translation>无法使用版本3交易花费未确认版本1%d的预选输入。</translation>
    
ERR
The translation includes an extra "1" before the format specifier "%d" that is not present in the source text. In the context of Bitcoin Core, the "%d" likely represents the version number, so "版本1%d" is redundant or incorrect.

Correct translation:
无法使用版本 3 交易花费版本 %d 的未确认预选输入。
```

<!-- cache_translation_check_zh_f9b38ca6e6771122f4b6e345f173a375d4a3ec7c96cf90ece271263bcdc608a8 -->
```
        <source>Can't spend unconfirmed version 3 pre-selected input with a version %d tx</source>
        <translation>无法使用版本1%d交易花费未确认版本3的预选输入。</translation>
    
ERR
The translation incorrectly translates "version %d" as "版本1%d". The "1" is an extraneous character added before the format specifier, which changes the meaning and corrupts the format string.

Correct translation:
无法使用版本 %d 交易花费未确认的版本 3 预选输入。
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

<!-- cache_translation_check_zh_48efbd247f46f842be8b3a32001673fdef3721daddd55e336de8f3c35111412b -->
```
        <source>Failed to acquire rescan reserver during wallet initialization</source>
        <translation>在钱包初始化期间未能获取重扫预留器</translation>
    
ERR
The Chinese is understandable but uses an awkward/unnatural term "重扫预留器". Also missing a comma improves readability.

Suggested correction:
在钱包初始化期间，无法获取重扫保留锁

Alternative if you prefer "reserver" as an agent:
在钱包初始化期间，无法获取重扫保留者
```

<!-- cache_translation_check_zh_e3222f6658880630ea81b0a0cd483e7c2b2346ce99656d5b087dfe9f4559eb98 -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>加载 %s时出错：钱包为传统钱包。请使用迁移工具（migratewallet RPC）迁移到描述符钱包。</translation>
    
ERR
Minor formatting issue: there is no space between the %s placeholder and the following Chinese character "时". Also wording is acceptable but I recommend adding the space for readability.

Correct translation:
加载 %s 时出错：钱包为传统钱包。请使用迁移工具（migratewallet RPC）迁移到描述符钱包。
```

<!-- cache_translation_check_zh_fb9c57de56fb521dfdc9b8cd4124ea9b1e9e4d83d4064c6624a1a81414b0eed7 -->
```
        <source>Error: Dumpfile specifies an unsupported database format (%s). Only sqlite database dumps are supported</source>
        <translation>错误：转储文件指定了不受支持的数据库格式 %s。仅支持 sqlite 数据库转储。</translation>
    
ERR
The translation is mostly correct in meaning, but it mishandles the original parentheses around the format specifier and introduces an extra space before %s (Chinese text should not have that space). Also use of Chinese punctuation is preferable.

Correct translation:
错误：转储文件指定了不受支持的数据库格式（%s）。仅支持 sqlite 数据库转储。
```

<!-- cache_translation_check_zh_7ac1efa37e812c3d7101f033238c56c685efb44247b49ad8368f92f5497fdb8a -->
```
        <source>Unrecognized descriptor found. Loading wallet %s

The wallet might have been created on a newer version.
Please try running the latest software version.
</source>
        <translation>发现无法识别的描述符。正在加载钱包 %s 

该钱包可能是在较新版本中创建的。 
请尝试运行最新的软件版本。
</translation>
    
ERR
Translation is accurate, and the format specifier %s is preserved, but there are stray trailing spaces at line ends (extra spaces after "%s" and at ends of lines). Remove those to avoid whitespace issues.

Correct translation:
发现无法识别的描述符。正在加载钱包 %s

该钱包可能是在较新版本中创建的。
请尝试运行最新的软件版本。
```
</details>

Number of issues: 20.
