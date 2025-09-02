# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>zh_CN</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bzh_CN%5D%20request)


<!-- cache_translation_check_zh_CN_8c019d308baf1e9a7a513c7130b64e965bf42ca5f456cad8d84e632fbd324fa2 -->
```
        <source>&amp;Options…</source>
        <translation>选项(&amp;O)</translation>
    
ERR
The translation is mostly correct, but it omits the ellipsis (…) present in the source. Also ensure the accelerator marker (&) appears exactly once — that's OK here.

Correct translation:
选项(&amp;O)…
```

<!-- cache_translation_check_zh_CN_01e4df2271ad65cb2c9b41ee46ce77f24cb6b15f15b978ac3d5ca51532ebb2c8 -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation>加密钱包(&amp;E)</translation>
    
ERR
The translation is mostly correct but it omits the ellipsis (…) present in the source. The source has a trailing ellipsis indicating a dialog/action, so the translation should include it. Also ensure the & accelerator appears exactly once (it does), and there are no extra spaces.

Correct translation:
加密钱包(&amp;E)…
```

<!-- cache_translation_check_zh_CN_6a48bd30fe4e7cd2269014687f421baac1199561d91f0c02a5850a77330d53b2 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>备份钱包(&amp;B)</translation>
    
ERR
The translation omitted the ellipsis (…) present in the source. Also ensure the accelerator marker exists exactly once (it does here as (&B)), and there are no extra spaces.

Correct translation:
备份钱包…(&B)
```

<!-- cache_translation_check_zh_CN_54eba313b1f7705aba04afbe18023343277ec9a90b81ddf9082862e28be58fc8 -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>修改密码(&amp;C)</translation>
    
ERR
The translation is missing the trailing ellipsis (…) from the source. The accelerator (&) appears exactly once which is fine, but the translated label should include the ellipsis to match the source.

Correct translation:
<translation>修改密码(&amp;C)…</translation>
```

<!-- cache_translation_check_zh_CN_b9b8898b9bce2996b37b7c697d4d22299a77ad3b4bbd732257950b022f50d3f1 -->
```
        <source>Sign &amp;message…</source>
        <translation>签名消息(&amp;M)</translation>
    
ERR
The translation omits the trailing ellipsis (…) present in the source. The accelerator (&) is fine inside the parentheses. 

Correct translation:
签名消息(&M)…
```

<!-- cache_translation_check_zh_CN_dc28192dfd100f9a34d99016904dc9b0ee727b55bb4c562c352952eb737c1948 -->
```
        <source>&amp;Verify message…</source>
        <translation>验证消息(&amp;V)</translation>
    
ERR
The translation is missing the ellipsis (…) that appears in the source. Also the XML & must be escaped as &amp;.

Correct translation:
<translation>验证消息…(&amp;V)</translation>
```

<!-- cache_translation_check_zh_CN_4c782e7df9e5c8cf4f5e4722e25ef1e9559efc2b4ab702bc93f6c38d4e31cb58 -->
```
        <source>&amp;Sending addresses</source>
        <translation>付款地址(&amp;S)</translation>
    
ERR
Issues:
- The Chinese wording "付款地址" is ambiguous here; the UI context "Sending addresses" (address book tab for addresses you send to) is better translated as "发送地址".
- Shortcut format is acceptable but it's more natural in Chinese UIs to put the shortcut in parentheses after the label: use "发送地址(&S)". Ensure there is exactly one '&'.

Correct translation:
发送地址(&S)
```

<!-- cache_translation_check_zh_CN_07b24e731acfde530620e37ba80e4dd4623efd6c803f490116295af92f3094db -->
```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
ERR
The translation of "Close wallet" as "卸载钱包" is incorrect. "卸载钱包" means "uninstall wallet," which is not the same as "close wallet." The correct translation should be:

关闭钱包
```

<!-- cache_translation_check_zh_CN_9e586e108f9d3563d40685e78f9629fbe6059295b42274a8e24a3834e2de57f7 -->
```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>显示节点标签</translation>
    
ERR
The translation "显示节点标签" means "Show node label/tab", but "Peers tab" specifically refers to the tab for "Peers" (connected peers), not the node in general. "节点" means "node", while "Peers" should be translated as "节点" (peers/connected nodes) or more commonly "连接节点" or just "节点" in the context of Bitcoin, but to be accurate and consistent, it's often translated as "节点" but "Peers" specifically is usually "连接" or "连接节点" or simply "节点" when used as a tab name.

However, to distinguish clearly, the correct translation for "Show Peers tab" should be:
显示“节点”标签页

or, if the software calls the tab literally "Peers" instead of "节点":
显示“Peers”标签页

So the translation is misleading and should be improved.

Correct translation:
显示“节点”标签页
```

<!-- cache_translation_check_zh_CN_07b24e731acfde530620e37ba80e4dd4623efd6c803f490116295af92f3094db -->
```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
ERR
The translation of "Close wallet" as "卸载钱包" is incorrect. "卸载钱包" means "uninstall wallet," which is not the same as "close wallet." The correct translation should be:

关闭钱包
```

<!-- cache_translation_check_zh_CN_0be61d8326fcbba3a30366fc7835bd71f9690c1871fb05a7fe537359726db58d -->
```
        <source>&amp;Start %1 on system login</source>
        <translation>系统登入时启动 %1 (&amp;S)</translation>
    
ERR
Problems:
- Uses "登入" (more common in Traditional Chinese); Mainland Chinese should use "登录".
- Unnecessary space before the accelerator label; Chinese text normally does not have a space before parentheses.
- Accelerator placement is unconventional (showing "(&S)"); it's acceptable but better to keep formatting consistent.

Corrected translation suggestions:
系统登录时启动 %1(&amp;S)
or
在系统登录时启动 %1(&amp;S)
```

<!-- cache_translation_check_zh_CN_8370181d29a40be415ae5a5ca698caaa09b34b012c97a937b607bd8ca507a60a -->
```
        <source>Prune &amp;block storage to</source>
        <translation>将区块存储修剪至(&amp;B)</translation>
    
ERR
Issues:
- The shortcut marker is placed as "(&B)" which is acceptable but inconsistent with typical placement; it's better to integrate the shortcut naturally in the string. 
- Wording order is slightly unnatural in Chinese — "将区块存储修剪至" is understandable but a more fluent phrasing is "修剪区块存储至".
- Ensure exactly one & exists (it does) and no extra spaces (none present).

Suggested correction:
修剪区块存储至(&B)
```

<!-- cache_translation_check_zh_CN_27b85d8376af07e1605c63f231aa4e3e85709c6523af0f7bb5c4f42047f84dbb -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>默认从金额中减去交易手续费(&amp;F)</translation>
    
ERR
Problems:
- The translation is understandable but a bit wordy and uses "交易手续费", which is ok but slightly long. More importantly, the typical Chinese UI phrasing is shorter (e.g. 扣除/减去 手续费) and the shortcut marker is usually shown as (&F) — that's acceptable, but keep the ampersand exactly once.  
- Recommend a more natural, concise phrasing.

Correct translation:
默认从金额中减去手续费(&F)
```

<!-- cache_translation_check_zh_CN_1f11081981527618f6101a454a730d8840b7d7e8c390e3b90b558361e8362627 -->
```
        <source>&amp;Connect through SOCKS5 proxy (default proxy):</source>
        <translation>通过 SO&amp;CKS5 代理连接(默认代理):</translation>
    
ERR
Problems:
- The ampersand exists once (good) but it splits the ASCII token "SOCKS5" in the provided translation (SO&amp;CKS5), which is awkward. It's better to place the & before a Chinese word/character or before the ASCII token as a whole.
- Punctuation and spacing: Chinese text should use fullwidth punctuation (Chinese parentheses and colon) and avoid awkward spaces. The translation uses ASCII parentheses and colon and has unnecessary spaces.

Suggested correct translation (ampersand placed before the first Chinese word; keeps SOCKS5 intact and uses Chinese punctuation):

&通过 SOCKS5 代理连接（默认代理）：
```

<!-- cache_translation_check_zh_CN_d28571e64d8eb9358bd0eeb06b3a55fcd385ec2b29f0c7a2faacb27a2a65c592 -->
```
        <source>&amp;Minimize to the tray instead of the taskbar</source>
        <translation>最小化到托盘(&amp;M)</translation>
    
ERR
The translation omits the "instead of the taskbar" part, so it doesn't preserve the full meaning of the source. The accelerator is fine, but the text should explicitly mention the taskbar.

Correct translation:
最小化到托盘而不是任务栏(&M)
```

<!-- cache_translation_check_zh_CN_d5b7f50fbccf0a2d8611f9433bfc9db677127483cccdfd4cf1ff4b35c96a762c -->
```
        <source>&amp;Save Image…</source>
        <translation>保存图像(&amp;S)...</translation>
    
ERR
Problems:
- The source uses a single Unicode ellipsis "…" (U+2026). The translation uses three ASCII dots "..." which is inconsistent.
- Prefer keeping the escaped ampersand exactly once; currently it's present as (&amp;S) which is acceptable, but keep formatting consistent with the source punctuation.

Correct translation:
保存图像(&amp;S)…
```

<!-- cache_translation_check_zh_CN_0c2f3b1ca9da511a52168e61c92498723b5b95d121bdf4b2cf14fd3c7c628264 -->
```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
ERR
The Chinese translation "隐藏其他人的详细信息" means "Hide other people's detailed information," which is incorrect. The correct translation for "Hide Peers Detail" in the context of Bitcoin (referring to peer nodes) should be:

隐藏节点详细信息

This translates back as "Hide node detail/information," which is in line with the intended meaning regarding network peers.
```

<!-- cache_translation_check_zh_CN_d5b7f50fbccf0a2d8611f9433bfc9db677127483cccdfd4cf1ff4b35c96a762c -->
```
        <source>&amp;Save Image…</source>
        <translation>保存图像(&amp;S)...</translation>
    
ERR
Problems:
- The source uses a single Unicode ellipsis "…" (U+2026). The translation uses three ASCII dots "..." which is inconsistent.
- Prefer keeping the escaped ampersand exactly once; currently it's present as (&amp;S) which is acceptable, but keep formatting consistent with the source punctuation.

Correct translation:
保存图像(&amp;S)…
```

<!-- cache_translation_check_zh_CN_57b06c321041a6108564eb44adad256c4a9f7406ae0664700e636bccc4c56f28 -->
```
        <source>A&amp;mount:</source>
        <translation>金额(&amp;M)</translation>
    
ERR
The source includes a trailing colon ":" which should be preserved. The translation currently omits the colon. Also ensure the accelerator ampersand appears exactly once (it does), but keep the punctuation consistent.

Correct translation:
金额(&M):
```

<!-- cache_translation_check_zh_CN_567a23f7b8e16d3a0a0cea0c6ed87c6ae54ddecd7152515566906bf4299da38d -->
```
        <source>Copy transaction &amp;ID</source>
        <translation>复制交易 &amp;ID</translation>
    
ERR
The translation is accurate, and the ampersand is present exactly once, but there is an unnecessary space before the shortcut marker. In Chinese UI text, avoid the stray space before '&'.

Correct translation:
<translation>复制交易&amp;ID</translation>
```

<!-- cache_translation_check_zh_CN_90fda8f6932228d174e380ed1c7df7be7ae98d00ff1e42c56766226c0f6bb80a -->
```
        <source>Option '-checkpoints' is set but checkpoints were removed. This option has no effect.</source>
        <translation>选项“-checkpoints”已设置，但检查点已被移除。该选项不再生效。 </translation>
    
ERR
Translation is accurate in meaning, but contains a trailing space at the end and uses Chinese punctuation correctly. Remove the extra whitespace.

Correct translation:
选项“-checkpoints”已设置，但检查点已被移除。该选项不再生效。
```

<!-- cache_translation_check_zh_CN_d98c1c5ff4f9281f53e84a4630bcb6846485c6649d59a458ddb76aab8f1f87d3 -->
```
        <source>Option '-maxorphantx' is set but no longer has any effect (see release notes). Please remove it from your configuration.</source>
        <translation>选项“-maxorphantx”已设置，但已不再生效（参见发行说明）。请从您的配置中移除该选项。 </translation>
    
ERR
Translation is accurate in meaning, but there is a trailing space before the closing tag which is a whitespace issue.

Correct translation (remove trailing space):
选项“-maxorphantx”已设置，但已不再生效（参见发行说明）。请从您的配置中移除该选项。
```

<!-- cache_translation_check_zh_CN_bf17affb0acd6713b9f6b2167f99961dbd921c30426c9f4b5f40c6272c0fa297 -->
```
        <source>Options '-datacarrier' or '-datacarriersize' are set but are marked as deprecated. They will be removed in a future version.</source>
        <translation>选项“-datacarrier”或“-datacarriersize”已设置，但已标记为弃用。它们将在未来版本中移除。 </translation>
    
ERR
The translation is accurate in meaning, and there are no format specifiers to check. However there is an extra trailing space before the closing tag. Provide the corrected translation without the stray space:

Correct translation:
选项“-datacarrier”或“-datacarriersize”已设置，但已标记为弃用。它们将在未来版本中移除。
```

<!-- cache_translation_check_zh_CN_eb968025b9240f22a7d27bd23c989a8fc00fef0ee8185f551adcffb7a2452904 -->
```
        <source>-paytxfee is deprecated and will be fully removed in v31.0.</source>
        <translation>“-paytxfee”已弃用，并将在 v31.0 中完全移除。 </translation>
    
ERR
Translation is accurate in meaning, but has minor formatting issues: unwanted spaces (a trailing space at the end, and an extra space between "v31.0" and "中"). Also Chinese punctuation/spacing conventions prefer no space between "v31.0" and following Chinese characters.

Correct translation:
“-paytxfee”已弃用，并将在v31.0中完全移除。
```

<!-- cache_translation_check_zh_CN_fb0823c1e335cab3c139e0073166fec5250bf5eb78a2f8b358bf651517b0544c -->
```
        <source>Error: Missing checksum</source>
        <translation>错误：跳过检查检验和</translation>
    
ERR  
The translation is problematic. The source says "Error: Missing checksum" (meaning the checksum is not present), but the translation says "错误：跳过检查检验和" ("Error: skipped checksum"), which means the checksum was intentionally skipped. This changes the meaning.

Correct translation:  
错误：缺少校验和
```

<!-- cache_translation_check_zh_CN_e99dedaf3bcb0124644a867cc5bf8c595facdc7958e168c4eb407adc3aacf17b -->
```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
ERR
There is a typo in "unit32_t"; it should be "uint32_t" (the 'i' and 'n' are inverse). Also, there should be a space between the Chinese text and the format specifier for better readability.

Correct translation:
错误：无法将版本号 %u 解析为 uint32_t
```

<!-- cache_translation_check_zh_CN_8b1135fb065982e6c8ee05d3643b9ebb06cd5f98d94108205cfa2556397adb94 -->
```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
ERR
There is a slight word order issue. The phrase "写入钱包的磁盘%s" translates to "write to the wallet's disk %s", which can be misleading because %s is a placeholder for the wallet's name, not a particular disk. Also, the period should match the style (no period in the English).

Correct translation:
错误：无法将数据写入钱包 %s 的磁盘
```

<!-- cache_translation_check_zh_CN_bfba5479a7879ceb3a8fe1594b0469d71773b62d6ea3df387a6f180158c2e8e0 -->
```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
ERR
The placement of %s is incorrect. In the English source, "%s" is at the end of the sentence, serving as extra information (usually an error message). In the Chinese translation, "%s" is at the beginning, which is unidiomatic and may confuse users. Also, the colon at the end is not necessary unless more content follows.

Correct translation:
删除交易时失败: %s
```

<!-- cache_translation_check_zh_CN_91b2d94152681a78c404c8e9dae514187a2b035ef69c33dc78b90f18caf7825f -->
```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
ERR
The translation incorrectly states "低于最大手续费率设置" ("lower than the maximum fee rate setting") instead of "低于最小手续费率设置" ("lower than the minimum fee rate setting"). The word "最大" means "maximum", but "minimum" should be "最小".

Correct translation:
手续费率（%s）低于最小手续费率设置（%s）
```

<!-- cache_translation_check_zh_CN_31858be505051e38dd1b91b7fd358da6a776adc9de7310a3806b5d3ab32c3a70 -->
```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
ERR
The translation contains a double negative "不不可", which is erroneous. It should be "交易金额不可为负数" or "交易金额不得为负数".

Correct translation:
交易金额不可为负数
```

<!-- cache_translation_check_zh_CN_76b1bd6861e77279c4c3f4a191a4d295d0696f1f0ea13e7ad0a7140d44da079c -->
```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
ERR  
The translation incorrectly includes "1" before %s in "钱包文件创建失败：1%s", which appears to be an erroneous character. It should be "钱包文件创建失败：%s" with the %s format specifier directly following the colon.

Correct translation:
钱包文件创建失败：%s
```

<!-- cache_translation_check_zh_CN_fb9c57de56fb521dfdc9b8cd4124ea9b1e9e4d83d4064c6624a1a81414b0eed7 -->
```
        <source>Error: Dumpfile specifies an unsupported database format (%s). Only sqlite database dumps are supported</source>
        <translation>错误：转储文件指定了不受支持的数据库格式 %s。仅支持 sqlite 数据库转储。</translation>
    
ERR
The format specifier (%s) in the source is inside parentheses, but the translation removed the parentheses and added a space before %s. Keep the specifier and surrounding punctuation as in the source.

Correct translation:
错误：转储文件指定了不受支持的数据库格式（%s）。仅支持 sqlite 数据库转储。
```

<!-- cache_translation_check_zh_CN_8a65190ca204502b79b6c300f73c685661424c04e29136c9be3e8dc44a9de4b3 -->
```
        <source>Unrecognized network in -proxy='%s': '%s'</source>
        <translation>无法识别 -proxy=“%s” 中的网络：“%s”。</translation>
    
ERR
The translation is mostly correct but has formatting issues: it uses different quotation marks and includes an extra space before "中的网络", which is nonstandard in Chinese. The original has two '%s' specifiers and they must be preserved exactly.

Correct translation:
无法识别 -proxy='%s'中的网络：'%s'。
```
</details>

Number of issues: 33.
