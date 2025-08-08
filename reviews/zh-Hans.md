# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh-Hans</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh-Hans%5D%20low%20quality)


<!-- cache_translation_check_zh-Hans_ecfdcee8f26fba226de388e636d63fbc273ac52f229613766e3b986270c44492 -->
```
        <source>Close</source>
        <translation>关闭(L)</translation>
    
ERR
The translation "关闭(L)" includes the letter "(L)", which suggests a keyboard shortcut, but the original source "Close" does not indicate any shortcut. Normally, translations should not add or assume shortcuts unless specified in the source.

Correct translation:
关闭
```

<!-- cache_translation_check_zh-Hans_f708450832f61a3d57848e7c02f081974c57bb8f890231c278cbd91d8b43da2c -->
```
        <source>Export</source>
        <translation>导出(E)</translation>
    
ERR
The translation adds "(E)" which is not present in the original source. Unless part of a UI convention to show keyboard shortcuts (which should match the source), this is inaccurate.

Correct translation:
导出
```

<!-- cache_translation_check_zh-Hans_521b000b1c65ac70f7da315a0414f9daaace273dc244a28b594051447f2b7749 -->
```
        <source>Banned Until</source>
        <translation>在此之前保持封禁:</translation>
    
ERR
The translation "在此之前保持封禁:" is not accurate. It would be better translated as "封禁到" or "封禁截止到". The given translation also adds an unnecessary colon and implies a continuous state rather than a deadline.

Correct translation:
封禁到
```

<!-- cache_translation_check_zh-Hans_9c91a6e0f22c0f66106351529b3184636e78a2ce5111ac0342fa469aae364d01 -->
```
        <source>About %1</source>
        <translation>关于 %1 (A)</translation>
    
ERR
The translation adds "(A)" at the end, which is not present in the source and is unnecessary. This alters the intended meaning.

Correct translation:
关于 %1
```

<!-- cache_translation_check_zh-Hans_5c7840abeba6556e11fcdde91d6a364012ddf607e15a9ec0a789da607f0bd3a2 -->
```
        <source>Load PSBT from file…</source>
        <translation>从文件加载PSBT(L)...</translation>
    
ERR
The translation is mostly accurate but has a minor issue. The source uses an ellipsis ("…"), whereas the translation adds "(L)" which may be intended as a shortcut/hotkey indicator but isn't present in the source, and can cause user interface inconsistency if the original software does not assign "L" as a shortcut. Additionally, the order is better as "加载PSBT文件…" for naturalness.

Correct translation:
从文件加载PSBT…
```

<!-- cache_translation_check_zh-Hans_7745057d32350475f1ec694cf69e195ddf6cfb84bb04f51218c9d13dc9d572ab -->
```
        <source>Command-line options</source>
        <translation>命令行选项(C)</translation>
    
ERR
The translation adds an unnecessary "(C)" at the end, which is not present in the source and could confuse users. In Chinese UI translation, such letter-in-parentheses are only used for access keys (快捷键) and should match the source. Here, there is no reason for "(C)".

Correct translation:
命令行选项
```

<!-- cache_translation_check_zh-Hans_d284805f67cfb74ef268f8a0424b8ea6a8bdf48a2564319293c8acd3126c5ced -->
```
        <source>Load PSBT from clipboard…</source>
        <translation>从剪贴板加载PSBT(C)...</translation>
    
ERR
The translation adds "(C)" which is not present in the original source and changes the ellipsis from "…" (Unicode ellipsis) to "...". This introduces unnecessary content and alters the intended format.

Correct translation:
从剪贴板加载PSBT…
```

<!-- cache_translation_check_zh-Hans_2883e00d0d8a42685d37e2a343e075eb9ff8db424f4ef6119b847c9edd193c89 -->
```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
ERR
The translation "付款地址(S)" is problematic. The addition of "(S)" is unnecessary and incorrect in Chinese; plurals are generally not represented this way in Chinese. The correct translation should be:

Correct translation:
发送地址
```

<!-- cache_translation_check_zh-Hans_07b24e731acfde530620e37ba80e4dd4623efd6c803f490116295af92f3094db -->
```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
ERR
The translation "卸载钱包" means "uninstall wallet", which is incorrect for "Close wallet". The correct translation should be "关闭钱包".

Correct translation:
关闭钱包
```

<!-- cache_translation_check_zh-Hans_07b24e731acfde530620e37ba80e4dd4623efd6c803f490116295af92f3094db -->
```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
ERR
The translation "卸载钱包" means "uninstall wallet", which is incorrect for "Close wallet". The correct translation should be "关闭钱包".

Correct translation:
关闭钱包
```

<!-- cache_translation_check_zh-Hans_ebf157016d03f8cbc797681d1a7de19ebe3e16b021718e7691622dff5d7bc280 -->
```
        <source>Address</source>
        <translation>地址(A)</translation>
    
ERR
The translation includes an extra "(A)" that is not in the original English text and is not standard for 'zh-Hans' translations of "Address." "(A)" might be used as an access key label in some UI systems, but unless clearly specified for this context, it should not be added.

Correct translation:
地址
```

<!-- cache_translation_check_zh-Hans_118374777043bdfbf2292ba4dd536c2371a7c61bbb44d64088d487d5948685d5 -->
```
        <source>Wallet</source>
        <translation>钱包(A)</translation>
    
ERR
The translation adds "(A)" after 钱包, which is not present in the source and could cause confusion unless "A" is justified by a context (such as a shortcut key in menus, but this is not clear from the source). This addition is unnecessary and erroneous if not required.

Correct translation:
钱包
```

<!-- cache_translation_check_zh-Hans_9b65abaf920620fc868a778cd7be0087871830690dcf29132076e2e0e8ca49ff -->
```
        <source>Third-party transaction URLs</source>
        <translation>第三方交易网址(T)</translation>
    
ERR
The translation adds an extra "(T)" at the end, which is not present in the source and may confuse users. Also, "网址" (website URL) may be less appropriate than "链接" (link) or keeping it literal with "URL", depending on the technical context, but "网址" is generally acceptable.

Correct translation:
第三方交易网址
```

<!-- cache_translation_check_zh-Hans_56b8225dec67e3fc39f92c0309eebb7e8c80b10b7e006ad5546daaaf877a2190 -->
```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
ERR
There is a redundancy in the translation: "仅观察观察地址" repeats the word "观察" (watch). The correct phrase should be "仅观察地址" for "watch-only addresses."

Correct translation:
您当前在仅观察地址中的余额
```

<!-- cache_translation_check_zh-Hans_9aaea724e35cabcbf2ac07c832c25a252ef22ee5c468bb68b8255db455a0cef6 -->
```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>“概况”标签页已启用隐私模式。要明文显示数值，请在设置中取消勾选“不明文显示数值”。</translation>
    
ERR
The translation is inaccurate in the second sentence. The phrase "不明文显示数值" means "Do not display values in plaintext", which is not what the setting in the English source ("Mask values") specifies. The translation also reverses the meaning. Additionally, "Mask values" should be translated literally (e.g., “隐藏数值” or “遮罩数值”).

Correct translation:
“概况”标签页已启用隐私模式。要显示被隐藏的数值，请取消勾选“设置”->“隐藏数值”。
```

<!-- cache_translation_check_zh-Hans_82c88a5991bcbe0a2d98ada356aaaf1a9a158d43b1c0c7fa13c2a9fc8985d70d -->
```
        <source>Peers</source>
        <translation>节点(P)</translation>
    
ERR
The translation "节点(P)" is problematic. "Peers" in the context of Bitcoin should be translated as "节点" or "对等节点". The addition of "(P)" is unnecessary and could be confusing as it does not convey any meaning in the context of Chinese or Bitcoin.

Correct translation:
节点
```

<!-- cache_translation_check_zh-Hans_0c2f3b1ca9da511a52168e61c92498723b5b95d121bdf4b2cf14fd3c7c628264 -->
```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
ERR
The translation "隐藏其他人的详细信息" means "Hide other people's detailed information," which does not accurately render "Peers" in the context of Bitcoin (where Peers refer to network nodes or connections, not "other people"). The correct translation should use “节点" (nodes) or “对等节点" (peers):

Correct translation:
隐藏节点详细信息
or
隐藏对等节点的详细信息
```

<!-- cache_translation_check_zh-Hans_a5a2d08ba1b59e25757d4bd8798a6efa1b0236c2331ae5048aae04c30fd89c29 -->
```
        <source>Network Traffic</source>
        <translation>网络流量(N)</translation>
    
ERR
Including "(N)" in the translation is unnecessary and does not exist in the source text. It may confuse users or suggest the presence of a keyboard shortcut that does not exist in the original source.

Correct translation:
网络流量
```

<!-- cache_translation_check_zh-Hans_9a4c8dafd958c88129fd1d3d8be4c60c05611a92fbb7c7c5b5e576942beb73c0 -->
```
        <source>1 hour</source>
        <translation>1 小时(H)</translation>
    
ERR
The translation "1 小时(H)" unnecessarily adds "(H)" after "1 小时", which is not standard or needed in Chinese. The original simply says "1 hour", so the translation should match without the extra notation.

Correct translation:
1 小时
```

<!-- cache_translation_check_zh-Hans_a27ba6a54d60583ba93321d63927938724cdf2467e34553427524f9f65250183 -->
```
        <source>1 day</source>
        <translation>1 天(A)</translation>
    
ERR
The translation includes an erroneous "(A)" after "1 天", which is not present in the original English source. This is an unnecessary addition and may confuse users.

Correct translation:
1 天
```

<!-- cache_translation_check_zh-Hans_5db66af152c1f6604a3f430fe028602fdfceee2647ad884898000f324368cefa -->
```
        <source>1 year</source>
        <translation>1 年(Y)</translation>
    
ERR
The translation adds "(Y)" which is unnecessary and not present in the original English source. This could confuse users, as "年" already means "year" in Chinese.

Correct translation:
1 年
```

<!-- cache_translation_check_zh-Hans_4fff14ad015f82e56d3436fdd0ab906136cd6758220165307813e8f36af882e4 -->
```
        <source>The Bitcoin address to send the payment to</source>
        <translation>付款目的地址</translation>
    
ERR
The translation "付款目的地址" is acceptable in some contexts, but it lacks specificity and does not explicitly mention "Bitcoin" nor is it a direct translation of the source. For clarity and accuracy, especially in a technical/Bitcoin context, it is better to specify "比特币地址" as in the source.

Correct translation:
比特币付款接收地址
```

<!-- cache_translation_check_zh-Hans_5682213c7071df73f2e9fc213f559a81292b1a0a139c5d644681abb371ee0353 -->
```
        <source>Subtract fee from amount</source>
        <translation>从金额中减去交易费(U)</translation>
    
ERR
The translation adds the "(U)" at the end, which is not present in the source and could be erroneous, as it may confuse users. Everything else is accurate.

Correct translation:
从金额中减去交易费
```

<!-- cache_translation_check_zh-Hans_2ea05109177ce8020f20f6b98269d46d59db377354fe582cfb486ece3aaf5567 -->
```
        <source>Verify Message</source>
        <translation>验证消息签名(M)</translation>
    
ERR
The translation adds "签名" (signature) and "(M)" (possibly a shortcut), which are not present in the original English text "Verify Message". This introduces erroneous content.

Correct translation:
验证消息
```

<!-- cache_translation_check_zh-Hans_41d8960375f641d7d2c1a3aac4479960b60310418eda9a625db7ee33754c0baa -->
```
        <source>Generated</source>
        <translation>挖矿生成</translation>
    
ERR
The translation "挖矿生成" (mined/generated from mining) is too specific and adds information ("挖矿"/mining) not present in the source. The English word "Generated" could refer to more than just mined coins and should be translated more neutrally unless context absolutely requires otherwise.

Correct translation:
已生成
```

<!-- cache_translation_check_zh-Hans_955fd7a15375cc6c8411ffedd6d43fb1b505224a67077ed1aa3bbbdd36d2cefb -->
```
        <source>Increase transaction fee</source>
        <translation>增加矿工费(F)</translation>
    
ERR
The translation "增加矿工费(F)" is problematic. The term "矿工费" is a colloquial Chinese term for "miner's fee," which is understandable but not technically accurate for "transaction fee," which should be "交易手续费" or simply "手续费". The addition of "(F)" is unexplained and not present in the source, which introduces unnecessary content.

Correct translation:
增加交易手续费
```

<!-- cache_translation_check_zh-Hans_f708450832f61a3d57848e7c02f081974c57bb8f890231c278cbd91d8b43da2c -->
```
        <source>Export</source>
        <translation>导出(E)</translation>
    
ERR
The translation adds "(E)" which is not present in the original source. Unless part of a UI convention to show keyboard shortcuts (which should match the source), this is inaccurate.

Correct translation:
导出
```

<!-- cache_translation_check_zh-Hans_fce52dee3da05626ba2ebf9fd77975cdb4fa8987c3cbcee2d3d0115e38d5c878 -->
```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多个洋葱路由绑定地址。对自动创建的洋葱服务用%s</translation>
    
ERR
The translation is mostly accurate but has minor issues:
1. The sentence ending is abrupt and missing a proper period.
2. The phrase "洋葱服务" is understandable but "Tor 洋葱服务" would be clearer for Chinese readers.
3. The structure “对自动创建的洋葱服务用%s” is a bit awkward; it’s better as “将使用 %s 作为自动创建的 Tor 洋葱服务的绑定地址。”
4. Ensure there is a space before the %s as in the English original.

Correct translation:
提供了多个洋葱路由绑定地址。将使用 %s 作为自动创建的 Tor 洋葱服务的绑定地址。
```

<!-- cache_translation_check_zh-Hans_1c749520d427b91fe4d334af919bbbbd32ac6b6e105007f840d1c61c7ee7105d -->
```
        <source>The block database contains a block which appears to be from the future. This may be due to your computer's date and time being set incorrectly. Only rebuild the block database if you are sure that your computer's date and time are correct</source>
        <translation>区块数据库包含未来的交易，这可能是由本机的日期时间错误引起。若确认本机日期时间正确，请重新建立区块数据库。</translation>
    
ERR
The translation is problematic. The source says "contains a block which appears to be from the future", but the translation says "包含未来的交易" ("contains a transaction from the future"), which changes "block" to "transaction", which is inaccurate. Also, the translation misses the nuance about rebuilding only if you're sure the date/time is correct; the condition is reversed and less clear.

Correct translation:
区块数据库包含一个看似来自未来的区块，这可能是由于您的计算机日期和时间设置不正确所致。只有在确信您的计算机日期和时间正确时，才应重建区块数据库。
```

<!-- cache_translation_check_zh-Hans_fb0823c1e335cab3c139e0073166fec5250bf5eb78a2f8b358bf651517b0544c -->
```
        <source>Error: Missing checksum</source>
        <translation>错误：跳过检查检验和</translation>
    
ERR  
The translation is problematic. The source means "Missing checksum", but the Chinese sentence means "Skipped checking the checksum", which is inaccurate.

Correct translation:  
错误：缺少校验和
```

<!-- cache_translation_check_zh-Hans_e99dedaf3bcb0124644a867cc5bf8c595facdc7958e168c4eb407adc3aacf17b -->
```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
ERR
There is a typo in the translation: "unit32_t" should be "uint32_t". Additionally, there should be a space between "版本号" and "%u" to match conventions, though this is optional in Chinese.

Correct translation:
错误：无法将版本号 %u 解析为 uint32_t
```

<!-- cache_translation_check_zh-Hans_91b2d94152681a78c404c8e9dae514187a2b035ef69c33dc78b90f18caf7825f -->
```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
ERR  
The translation is inaccurate. The source says "lower than the minimum fee rate setting," but the translation says "低于最大手续费率设置," which means "lower than the maximum fee rate setting." The word "最大" means "maximum" and is incorrect here; it should be "最小," meaning "minimum."

Correct translation:  
手续费率 (%s) 低于最小手续费率设置 (%s)
```

<!-- cache_translation_check_zh-Hans_31858be505051e38dd1b91b7fd358da6a776adc9de7310a3806b5d3ab32c3a70 -->
```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
ERR
The translation contains a redundancy: "不不可为负数" means "must not not be negative", with a double negation ("不不可" instead of "不可").
 
Correct translation:
交易金额不可为负数
```
</details>

Number of issues: 33.
