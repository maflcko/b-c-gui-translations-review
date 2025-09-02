# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>zh_HK</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bzh_HK%5D%20request)


<!-- cache_translation_check_zh_HK_15aa3d118f404841d7ed6fa65e53862bd6fbcbf4a9b5edba73af5477c5091f74 -->
```
        <source>&amp;Copy</source>
        <translation>複製 &amp;C</translation>
    
ERR
The placement of the ampersand (&amp;) is incorrect for zh_HK. In Hong Kong Cantonese localization, accelerators are usually retained just in front of (or after) the relevant character or letter used for shortcuts, not appended with the English shortcut key. The translation "複製 &amp;C" mixes Chinese characters with an English shortcut in a nonstandard way.

Correct translation:
&amp;複製

Or, if you wish to keep the English shortcut (which is less common in zh_HK unless needed for English UI consistency):
複製(&amp;C)
```

<!-- cache_translation_check_zh_HK_5c65c9fa7533424fd3fdbb09ce8ec92f7d139e353d5cff18caf306985536dd2f -->
```
        <source>C&amp;lose</source>
        <translation>關閉 &amp;l</translation>
    
ERR
The translation places the shortcut key (&amp;l) incorrectly after the word, which is non-standard for Chinese (Hong Kong) translations, and the ampersand should precede the letter used as the shortcut (in this case, "l", but Chinese UIs typically use a Chinese character). The original English shortcut is "C", so the Chinese translation should use a relevant character, commonly "關(&C)閉" or just "關閉(&C)", preserving the shortcut.

Correct translation:
關閉(&C)
```

<!-- cache_translation_check_zh_HK_0612e8aef0b85cca15b3d2220e063d00d5e249fa27727fd2ab0830cdcc07978c -->
```
        <source>Copy the currently selected address to the clipboard</source>
        <translation>复制当前选中的地址到剪贴板。</translation>
    
ERR
The translation is in Simplified Chinese ( Mainland style ) rather than Traditional Chinese as expected for zh_HK. No format specifiers are present, and there are no spacing issues, but the characters should be converted to Traditional Chinese and phrasing adjusted for Hong Kong usage.

Correct translation:
將目前所選的地址複製到剪貼簿。
```

<!-- cache_translation_check_zh_HK_2121ef868142997a35319d5921dc03e4c8045f37da8a2f5b0a73dc71658a9a44 -->
```
        <source>&amp;Export</source>
        <translation>匯出 &amp;E</translation>
    
ERR
The ampersand (&) is intended to mark the shortcut key and should appear exactly once, but in the Hong Kong Chinese ('zh_HK') translation, it appears after the word instead of before the shortcut letter. In Cantonese/Hong Kong style, the English shortcut letter is usually retained in parentheses, or at the end with the ampersand correctly placed.

Correct translation:
匯出(&E)
or
&匯出

The placement of "&" before "E" in "匯出 &amp;E" is non-standard and may not correctly display the shortcut key in the UI.
```

<!-- cache_translation_check_zh_HK_7232d230c6dd41a6b9360b9d7485c0714d79bf70de0f7de1808049653af874d6 -->
```
        <source>C&amp;hoose</source>
        <translation>選擇 &amp;h</translation>
    
ERR
The translation places the '&' incorrectly and creates a meaningless shortcut key ("h") that is not intuitive in the Cantonese/Traditional Chinese context for "選擇". The '&' should be placed before the character intended as the shortcut, preferably a character that maps to the English letter used in the original ("C" for "Choose") if possible, but in Traditional Chinese, the shortcut is often placed at the start or left off if not feasible.

Correct translation:
選擇(&amp;C)
```

<!-- cache_translation_check_zh_HK_7b125159c3d54bbd2ce22d7605a81fe39999b13f86a7598cd32b4ff8c895eb2c -->
```
        <source>Continue</source>
        <translation>继续</translation>
    
ERR
The translation "继续" is in Simplified Chinese (zh_CN), not Traditional Chinese as used in Hong Kong (zh_HK). The correct Traditional Chinese translation should be:

繼續
```

<!-- cache_translation_check_zh_HK_857e23e7e1973f04063bfe63ea5f0211c4d81243fda8f4321ee9945b833e9a2c -->
```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>發生了內部錯誤%1 將嘗試安全地繼續。 這是一個意外錯誤，可以按如下所述進行報告。</translation>
    
ERR
There is a missing punctuation mark after "發生了內部錯誤". The English sentence separates the two clauses with a period, but the translation omits it, which can cause confusion. Also, there should be no extra space before "這是一個意外錯誤...".

Correct translation:
發生了內部錯誤。%1 將嘗試安全地繼續。這是一個意外錯誤，可以按如下所述進行報告。
```

<!-- cache_translation_check_zh_HK_1d4d50356a6d37e9a65eefe4248ceecc505b510a4abaf25a6225631750fcc415 -->
```
        <source>Custom…</source>
        <translation>自定义...</translation>
    
ERR
The translation uses simplified Chinese ("自定义...") instead of traditional Chinese as expected for 'zh_HK'. Also, the ellipsis character "…" in the source should be preserved in the translation for typographical accuracy.

Correct translation:
自訂…
```

<!-- cache_translation_check_zh_HK_fbb5b09a9f86969a7421fdabda6ed901818486bf04c04a5630a2da5f0460fe4c -->
```
        <source>Manual</source>
        <extracomment>Peer connection type established manually through one of several methods.</extracomment>
        <translation>手册</translation>
    
ERR
The translation "手册" means "manual" as in a user guide or handbook, not "manual" as in "done by hand/manually" which is the intended meaning in this context (connection type established manually).

Correct translation:
手動
```

<!-- cache_translation_check_zh_HK_fb4012e596b77acb3cd9b0902b4c9f59d43e5e5d3263ebee53d27b50ff27a866 -->
```
        <source>&amp;Overview</source>
        <translation>總覽 &amp;O</translation>
    
ERR
The position of the shortcut key (&) should ideally match its purpose from the source to ensure accessibility/usability consistency. In this translation, "&" is not placed before the shortcut letter (O), so the shortcut key may not function as intended.

Correct translation:
&amp;總覽

Or, if choosing a letter for the shortcut due to interface conventions:
總覽(&amp;O)

But best is:
&amp;總覽
</reply>
```

<!-- cache_translation_check_zh_HK_b3d45990bdaed0c9a29aeab33a9c9d8c0e554cdf31168f43b76cde1271b394f5 -->
```
        <source>&amp;Transactions</source>
        <translation>交易 &amp;T</translation>
    
ERR
The Hong Kong Chinese ('zh_HK') translation "交易 &T" places the ampersand and shortcut key as if it is an English interface, but in Chinese UIs, the ampersand should immediately precede the shortcut character in the Chinese text. Additionally, the shortcut key should correspond to a Chinese character, or match the layout convention of the application. The base translation is accurate, but the shortcut placement is non-standard for zh_HK.

Correct translation:
&交易
Or, if a shortcut letter must be specified after the label (rare and non-standard in zh_HK, but sometimes used):
交易(&T)
```

<!-- cache_translation_check_zh_HK_eea4397bd824529d3ffa6a4353109c5ce81e0da64a6cb71eca9f382ff99fd195 -->
```
        <source>&amp;About %1</source>
        <translation>關於 %1 &amp;A</translation>
    
ERR
The position of the shortcut (&amp;) is incorrect. In zh_HK, the shortcut key should correspond in placement to the English version where possible. The &amp; should be placed once, ideally before the character that will be used as the shortcut. Also, adding an extra 'A' is not standard in Hong Kong Chinese UI. The translation should be:

Correct translation:
關於 %1(&amp;A)
or
(&amp;A)關於 %1

The most common style is: 關於 %1(&amp;A)
```

<!-- cache_translation_check_zh_HK_95a2ed4f156d7842752f11b779d83569ea2a6738da10e89ec4cfdd9042ed1138 -->
```
        <source>About &amp;Qt</source>
        <translation>關於 Qt &amp;Q</translation>
    
ERR
The ampersand (&amp;) is used to indicate a shortcut key. In the source, "&amp;Qt" means the shortcut is "Q" in "Qt". In the translation, "Qt &amp;Q" does not correspond to "Qt" or create a logical shortcut. The correct translation would be to keep the shortcut on the same character in the translation, or as close as possible.

Correct translation:
關於 &amp;Qt
```

<!-- cache_translation_check_zh_HK_a7c351c427df6d7b486104f1939aef897d1cfa92e831eea41d659421963ae8ce -->
```
        <source>&amp;Minimize</source>
        <translation>最小化</translation>
    
ERR
The '&' symbol indicating the shortcut key is missing in the translation. It must appear exactly once.

Correct translation:
&最小化
or
最小化(&M)
```

<!-- cache_translation_check_zh_HK_a8b8d99935bbe4df08129bdc7a29584ff13940d930cd94a6acdf940789757e9a -->
```
        <source>&amp;Send</source>
        <translation>付款 &amp;S</translation>
    
ERR
The translation "付款 &S" is problematic. In Hong Kong Cantonese ('zh_HK'), "&Send" should be translated as "發送(&S)" or "發送 &S" to accurately represent "Send" and maintain the shortcut key. The word "付款" means "Pay", which is not the same as "Send". Also, the placement of "&" is usually within the parentheses after the Chinese text.

Correct translation:
發送(&S)
```

<!-- cache_translation_check_zh_HK_959c16ffaca69fc3d6fbf70a5b759e74557ee0b24442f52a5d2b5845646674c7 -->
```
        <source>Close Wallet…</source>
        <translation>关闭钱包...</translation>
    
ERR
The translation uses Simplified Chinese characters and an ellipsis made of three periods (...), while the target should be in Traditional Chinese for 'zh_HK', and the ellipsis in Chinese is usually "…" (U+2026). Furthermore, "关闭" (close) is Simplified; in Hong Kong Traditional Chinese, "關閉" should be used.

Correct translation:
關閉錢包…
```

<!-- cache_translation_check_zh_HK_af3e16b29457207e5532a4fd697c8df1f8f0ea0737e20ed17d82e75835bbef81 -->
```
        <source>Create Wallet…</source>
        <translation>创建钱包...</translation>
    
ERR
The translation uses Simplified Chinese characters "创建钱包...", which is typical for 'zh_CN', not 'zh_HK'. In Cantonese as used in Hong Kong, Traditional Chinese characters should be used. Also, the ellipsis should be the full-width ellipsis (…).

Correct translation:
建立錢包…
```

<!-- cache_translation_check_zh_HK_17234ce504d56ba92b66f67f13b6813b8b2b8225a87b89603f66537e25681b57 -->
```
        <source>&amp;Settings</source>
        <translation>設定 &amp;S</translation>
    
ERR
The position of the ampersand (&amp;) should match the shortcut key in the translation. In this case, "&amp;" is in front of "S" in the translation, while in the source it is in front of "Settings". In Chinese (Hong Kong), there is no "S" in "設定", so the shortcut key placement is not meaningful and could confuse users. The ampersand should precede the character intended as the shortcut key in the translation, or if no meaningful mapping exists, it should be "&amp;設定".

Correct translation:
&設定
```

<!-- cache_translation_check_zh_HK_9b597fdeceb734048b54fca888e785be4c6a3b290c047827f79b9f1d0cc02a38 -->
```
        <source>Connecting to peers…</source>
        <translation>连接到节点...</translation>
    
ERR
The translation uses Mainland Chinese characters and punctuation ("连接到节点..." with three periods), which is not appropriate for 'zh_HK' (Hong Kong). In zh_HK, it should use traditional Chinese characters and ideally an ellipsis (… or ……), and "节点" is usually rendered as "節點" in traditional Chinese.

Correct translation:
連接到節點…
or
正在連接到節點…
```

<!-- cache_translation_check_zh_HK_42a695c10a15cebe8935b1a9013c83e954e990e2627b810a54a4e13beb932376 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>從剪貼簿載入PSBT</translation>
    
ERR
The translation omits the shortcut key indicator (&amp;), which should appear exactly once somewhere in the translation. Also, the ellipsis ("…") at the end of the source is missing in the translation.

Correct translation:
從剪貼簿載入&amp;PSBT…
```

<!-- cache_translation_check_zh_HK_09d84e2349f8aba8c0d374bcaf3622737197481133c56cc9e0777ddcb4825595 -->
```
        <source>Open a bitcoin: URI</source>
        <translation>打开bitcoin:开头的URI</translation>
    
ERR
The translation is written in simplified Chinese and does not use Hong Kong (traditional) characters or locale. Also, it's a bit literal.

Correct translation:
打開以 bitcoin: 開頭的 URI
```

<!-- cache_translation_check_zh_HK_07b24e731acfde530620e37ba80e4dd4623efd6c803f490116295af92f3094db -->
```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
ERR
The translation "卸载钱包" means "Uninstall wallet," which is incorrect for "Close wallet." The correct translation for "Close wallet" in zh_HK should be "關閉錢包".

Correct translation:
關閉錢包
```

<!-- cache_translation_check_zh_HK_0fca2d1643292f31802c765d917c65bafe45fa8fc7158ce35cf9473cb7c10f0a -->
```
        <source>Migrate a wallet</source>
        <translation>迁移一个钱包</translation>
    
ERR
The translation "迁移一个钱包" uses Simplified Chinese, while 'zh_HK' (Hong Kong Chinese) typically uses Traditional Chinese. Also, the measure word "一个" is more common in Mainland usage; in Hong Kong, "一個" is standard, but can be omitted.

Correct translation:
遷移錢包
```

<!-- cache_translation_check_zh_HK_288aac83bf952b4faa778bc98603999a0a404648c87babfb9f60f83f1c86ac95 -->
```
        <source>&amp;Hide</source>
        <translation>&amp;躲</translation>
    
ERR
The translation uses "躲" which typically means "to dodge" or "to hide (physically, e.g., oneself)," and is not idiomatic in this context for UI elements in Cantonese (Hong Kong). The more appropriate term is "隱藏", which is conventionally used for the "Hide" function in software. The shortcut key indicator "&" is preserved correctly.

Correct translation:
&隱藏
```

<!-- cache_translation_check_zh_HK_950cb28cc0f57eebf6fb6e99e761a355724df12da7463d87aeda770e4eaacc26 -->
```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
ERR
The translation is incorrect. The English "Enable network activity" means to turn network activity back on, but the translation "關閉網路紀錄" means "Disable network record" or "Close network log." This is the opposite action, and also the wording is inaccurate (紀錄 = log/record, not activity).

Correct translation:
啟用網絡活動
```

<!-- cache_translation_check_zh_HK_a6e9d6abcc4431799e73f806331c34124d5e3cf2ac80d23af4c298249010502b -->
```
        <source>Copy &amp;amount</source>
        <translation>复制和数量</translation>
    
ERR
The translation does not preserve the shortcut key (&) from the source, and the phrase "复制和数量" is an incorrect translation for "Copy &amount". The correct translation should be:

正确翻译：
複製金額(&A)
```

<!-- cache_translation_check_zh_HK_90b92531e1ef339bbba4c9ef552afff81ce69fd057cdd1320fd552110d86e714 -->
```
        <source>Copy change</source>
        <translation>复制找零金额</translation>
    
ERR
The translation uses Simplified Chinese characters ("复制找零金额") while zh_HK should use Traditional Chinese. Also prefer the common phrasing for "copy" in Traditional Chinese.

Correct translation:
複製找零金額
```

<!-- cache_translation_check_zh_HK_4ff501518568c9b4d0e0e7618f065a35c12e0101b7e1edcaea00eefb03947c0e -->
```
        <source>Migrate wallet</source>
        <translation>迁移钱包</translation>
    
ERR
The translation uses simplified Chinese characters ("迁移钱包"), which are standard for 'zh_CN', not 'zh_HK'. 'zh_HK' should use traditional Chinese characters and often prefers "移轉" or "遷移" for "migrate".

Correct translation:
遷移錢包
```

<!-- cache_translation_check_zh_HK_bf48e9cfcafbf9faad20e0a4f2f51c9f4896aaad679695662396237cde4e4221 -->
```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>迁移钱包 &lt;b&gt;%1&lt;/b&gt;...</translation>
    
ERR
The translation uses Simplified Chinese characters ("迁移") instead of Traditional Chinese, which is standard for 'zh_HK'. "迁移" should be "遷移" in Traditional Chinese. Also, the ellipsis should use the proper Chinese punctuation "…" (U+2026), matching the source.

Correct translation:
遷移錢包 &lt;b&gt;%1&lt;/b&gt;…
```

<!-- cache_translation_check_zh_HK_07b24e731acfde530620e37ba80e4dd4623efd6c803f490116295af92f3094db -->
```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
ERR
The translation "卸载钱包" means "Uninstall wallet," which is incorrect for "Close wallet." The correct translation for "Close wallet" in zh_HK should be "關閉錢包".

Correct translation:
關閉錢包
```

<!-- cache_translation_check_zh_HK_6ed2c8d64c593e4fb4075278e15d1c3a63bdd23b61a7c66659e67aa889c01a27 -->
```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>启用修剪时，如果一个钱包被卸载太久，就必须重新同步整条区块链才能再次加载它。</translation>
    
ERR
The translation is in Simplified Chinese ('启用修剪时，如果一个钱包被卸载太久，就必须重新同步整条区块链才能再次加载它。') rather than in the zh_HK locale, which uses Traditional Chinese. The terminology should also be localized. 

Correct translation:
啟用修剪功能時，如果錢包長時間關閉，可能需要重新同步整條區塊鏈。
```

<!-- cache_translation_check_zh_HK_e08e0c77aaa94b78b6eff83364bf8779ce9fb559ea6c1d9acae7d0b021cf678e -->
```
        <source>&amp;Label</source>
        <translation>标签(&amp;L)</translation>
    
ERR
The translation uses simplified Chinese "标签" instead of the traditional Chinese used in Hong Kong, which should be "標籤". The shortcut key (&amp;L) is correctly placed.

Correct translation:
標籤(&amp;L)
```

<!-- cache_translation_check_zh_HK_1876c8079f3c75fc90065cff075001f397d4157aaa859561c7d900ceabf127af -->
```
        <source>About %1</source>
        <translation>关于 %1</translation>
    
ERR
The translation uses Simplified Chinese ("关于") rather than Traditional Chinese as used in Hong Kong ('zh_HK'). In Hong Kong, "關於" is standard.

Correct translation:
關於 %1
```

<!-- cache_translation_check_zh_HK_ede40189b4cca918ec555b08ca9cb5a3d9f8b3ed3852ea2add55e099292651bd -->
```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
ERR  
There are issues with accuracy, punctuation, and completeness:
1. The phrase "starting with the earliest transactions in %3 when %4 initially launched" isn't fully and clearly conveyed.
2. The word "處裡" is a common typo; the correct form is "處理".
3. The punctuation and spacing are off: "區塊鏈(大小:%2GB)" should have a space after "區塊鏈" and parentheses should be full-width or match HK norms.
4. The phrase "並從%3年最早的交易" introduces ambiguity and doesn't specify that %3 is a time.
5. Missing full stop at the end.

Correct translation:
當你點擊「確認」，%1 會開始下載和處理整個 %4 區塊鏈（%2 GB），由 %4 最初推出時、%3 年的最早交易開始。

Explanation:
- The translation has been restructured for clarity and smoothness in Cantonese/HK written Chinese.
- All format specifiers (%1, %2, %3, %4) have been preserved and placed appropriately.
- Full-width brackets are used as per HK style, and space issues are fixed.
```

<!-- cache_translation_check_zh_HK_5ce60f1169385d2d3210dc1d475c5b695a1b7c16537f480bdcad64d137f55af0 -->
```
        <source>Size of &amp;database cache</source>
        <translation>資料庫快取的大小 </translation>
    
ERR
The translation is missing the &amp; used for the shortcut key. It should be present exactly once, as in the source. There is also an unnecessary space at the end.

Correct translation:
資料庫快取(&amp;)的大小
```

<!-- cache_translation_check_zh_HK_58b8380db05ec043399ce0849178cf3df715df3eeda4d6c607b8354a3f16b13a -->
```
        <source>Number of script &amp;verification threads</source>
        <translation>腳本和驗證線程數</translation>
    
ERR
The translation omitted the shortcut key indicator (&amp;). The "&amp;" should appear exactly once, as it does in the source, to maintain shortcut key consistency.

Correct translation:
腳本及驗證線程(&amp;)數

Alternatively, depending on UI practice, commonly:
腳本驗證(&amp;)線程數
```

<!-- cache_translation_check_zh_HK_8370181d29a40be415ae5a5ca698caaa09b34b012c97a937b607bd8ca507a60a -->
```
        <source>Prune &amp;block storage to</source>
        <translation>将区块存储修剪至(&amp;B)</translation>
    
ERR
The translation uses simplified Chinese ('将区块存储修剪至') instead of traditional Chinese, which is standard for 'zh_HK'. In Hong Kong, "将" should be "將", and the rest should be in traditional characters. Also, "修剪" is not the most common expression in Hong Kong software context—"修剪" is understandable but "修整" or "裁剪" may also be used.

Correct translation:
將區塊存儲修剪至(&amp;B)
```

<!-- cache_translation_check_zh_HK_d70baaefced8a672bdbcfc5e4f8b68c9837cba6b7c0175944c2d24390c6c41c7 -->
```
        <source>This allows you or a third party tool to communicate with the node through command-line and JSON-RPC commands.</source>
        <extracomment>Tooltip text for Options window setting that enables the RPC server.</extracomment>
        <translation>这允许作为用户的你或第三方工具通过命令行和JSON-RPC命令行与节点通信。</translation>
    
ERR
The translation uses Simplified Chinese ("这允许作为用户的你或第三方工具通过命令行和JSON-RPC命令行与节点通信。"), but 'zh_HK' should use Traditional Chinese characters. Additionally, "JSON-RPC命令行" is awkward; it should be "JSON-RPC 命令" (with a space) and "你作為用戶" would be a better phrasing in Traditional Chinese.

Correct translation:
這允許你或第三方工具通過命令列和 JSON-RPC 命令與節點通訊。
```

<!-- cache_translation_check_zh_HK_f04e0c5cf66fbf1a3c3fe9d7c5e7244bb855d9a1775ccd407ba284c1d99322d8 -->
```
        <source>Enable R&amp;PC server</source>
        <extracomment>An Options window setting to enable the RPC server.</extracomment>
        <translation>启用R&amp;PC服务器</translation>
    
ERR
The translation uses Simplified Chinese ("启用"), but 'zh_HK' requires Traditional Chinese. Additionally, "R&PC" should be "R&PC" and is preserved. For 'zh_HK', use Traditional Chinese characters.

Correct translation:
啟用R&amp;PC伺服器
```

<!-- cache_translation_check_zh_HK_90cb3df5f02c5e05050d32a54e6f07e05f34c59b13ff7f17b2a1c66a8798c940 -->
```
        <source>W&amp;allet</source>
        <translation>钱包(&amp;A)</translation>
    
ERR
The translation uses Simplified Chinese ("钱包") instead of Traditional Chinese used in zh_HK ("錢包"). The shortcut marker (&) is present once which is fine, but the localized text should be Traditional.

Correct translation:
錢包(&amp;A)
```

<!-- cache_translation_check_zh_HK_0ee180c40a35caecb75afcca2e9c2409aecb76a748673a1d9f07f4bcd6649167 -->
```
        <source>Enable &amp;PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>启用&amp;PSBT控件</translation>
    
ERR
The translation uses Simplified Chinese ("启用") instead of Traditional Chinese, which is standard for 'zh_HK'. '控件' is also a Mainland China term; in Hong Kong, "控制項" is more appropriate. The '&' for the shortcut key is in place.

Correct translation:
啟用&amp;PSBT控制項
</reply>
```

<!-- cache_translation_check_zh_HK_722ebb7c4c0dd489ffdda2da43e0ca4cbfaa2f989881657c00dac582cfd523de -->
```
        <source>&amp;Show tray icon</source>
        <translation>显示通知区域图标(&amp;S)</translation>
    
ERR
The translation uses Simplified Chinese ("显示通知区域图标") rather than Traditional Chinese, which is standard for 'zh_HK'. It should be in Traditional Chinese script. The translation is otherwise accurate, and it correctly places the (&amp;S) accelerator.

Correct translation:
顯示通知區圖示(&amp;S)
</assistant
```

<!-- cache_translation_check_zh_HK_7b125159c3d54bbd2ce22d7605a81fe39999b13f86a7598cd32b4ff8c895eb2c -->
```
        <source>Continue</source>
        <translation>继续</translation>
    
ERR
The translation "继续" is in Simplified Chinese (zh_CN), not Traditional Chinese as used in Hong Kong (zh_HK). The correct Traditional Chinese translation should be:

繼續
```

<!-- cache_translation_check_zh_HK_9162393ae596c5e9b46211bd834e8405fe5f5d02f74458808ba7f7d99e0ba735 -->
```
        <source>Sign Tx</source>
        <translation>签名交易</translation>
    
ERR
The translation uses Simplified Chinese character "签" (签名交易) but 'zh_HK' should use Traditional Chinese. Also "Sign Tx" in this Bitcoin context is better rendered as "簽署交易" (or "簽名交易" in Traditional characters).

Correct translation (Traditional, Hong Kong):
簽署交易
```

<!-- cache_translation_check_zh_HK_f105467780ed86558ce8e3654e103ed2c8c0b3ed24d6913c770044a37e0f9c87 -->
```
        <source>Copy to Clipboard</source>
        <translation>复制到剪贴板</translation>
    
ERR
The translation uses Simplified Chinese ("复制到剪贴板") rather than Traditional Chinese typically used for zh_HK. No format specifiers are involved and spacing is fine.

Correct translation (Traditional Chinese, Hong Kong):
複製到剪貼簿

(Alternative also acceptable: 複製到剪貼板)
```

<!-- cache_translation_check_zh_HK_51edd678fb1b28ef4e527ffcec2694e07d840d24ec22fcc06e2267b6fa704485 -->
```
        <source>Save…</source>
        <translation>保存...</translation>
    
ERR
Issues:
- Language/wording: In zh_HK (Traditional Chinese used in Hong Kong), "保存" is acceptable but "儲存" is more commonly used for UI labels like "Save".
- Ellipsis character: The source uses a single Unicode ellipsis (…) but the translation uses three ASCII dots (...). Keep the same ellipsis character.

Correct translation:
儲存…
```

<!-- cache_translation_check_zh_HK_4b980a8e124467dd4f3ab37eff60332cb353274bf73d42481c964a8ce4ab3f49 -->
```
        <source>Close</source>
        <translation>关闭</translation>
    
ERR
The translation uses Simplified Chinese ("关闭"), but zh_HK should use Traditional Chinese characters. No format specifiers or spacing issues present.

Correct translation:
關閉
```

<!-- cache_translation_check_zh_HK_d8e7e6fc6146a3982356a59e9a60d016fdc2003537ad22c23793179be9469f54 -->
```
        <source>Transaction broadcast successfully! Transaction ID: %1</source>
        <translation>已成功广播交易！交易ID: %1</translation>
    
ERR
The translation uses the simplified character "广播" instead of the Traditional Chinese used in zh_HK ("廣播"). Also punctuation for the colon should be the full-width one used in Chinese UI. %1 is preserved correctly.

Correct translation:
已成功廣播交易！交易 ID：%1
```

<!-- cache_translation_check_zh_HK_76733b01d0f71313804c54209973bdcddaa8ba61adad933c2f4c57d186e6e92a -->
```
        <source>Transaction broadcast failed: %1</source>
        <translation>交易广播失败: %1</translation>
    
ERR
The translation uses Simplified characters ("广播", "失败") and ASCII punctuation. For zh_HK (Traditional Chinese), use Traditional characters and proper full-width punctuation. The %1 specifier is preserved correctly.

Correct translation:
交易廣播失敗：%1
```

<!-- cache_translation_check_zh_HK_d5b7f50fbccf0a2d8611f9433bfc9db677127483cccdfd4cf1ff4b35c96a762c -->
```
        <source>&amp;Save Image…</source>
        <translation>保存图像(&amp;S)...</translation>
    
ERR
The translation uses Simplified Chinese "图像" instead of Hong Kong Traditional Chinese "圖像". Also, the ellipsis should be the full-width "…" to match the source, not three dots "...". 

Correct translation:
保存圖像(&amp;S)…
```

<!-- cache_translation_check_zh_HK_9bac5018e15289c39c7a610763092af5ed7a36914cbe467c93c2be6ee318afde -->
```
        <source>&amp;Information</source>
        <translation>資訊 &amp;I</translation>
    
ERR
The placement of the shortcut key (&) is incorrect in zh_HK. In Chinese, the & should directly precede the letter it refers to in the English original, but in zh_HK localization, it's customary to keep the & before the Chinese text or at the end for mnemonic alignment. Placing "&I" at the end does not correspond to any mnemonic in the Chinese text and is confusing to users.

Correct translation:
&資訊

Or, if a shortcut key must be preserved, but since there is no Latin letter in the Chinese text, the & is typically just placed at the start:

&資訊
```

<!-- cache_translation_check_zh_HK_98e5bb91bca6cf87bd593d7e3da0db4e68c3fbc892151fc80f7b67f7985fe4d2 -->
```
        <source>Memory Pool</source>
        <translation>内存池</translation>
    
ERR
The translation uses Simplified Chinese characters ("内存池") instead of Traditional Chinese as standard in Hong Kong ('zh_HK'). 

Correct translation:
記憶池
```

<!-- cache_translation_check_zh_HK_7cff338573a1217ebf8541f2f34144515a9feb75c8799e6c8d50d8681d30fded -->
```
        <source>(none)</source>
        <translation>(无)</translation>
    
ERR
The translation uses Simplified Chinese '(无)' instead of the Traditional Chinese '(無)' appropriate for 'zh_HK' (Hong Kong Chinese). 

Correct translation:
(無)
```

<!-- cache_translation_check_zh_HK_0c2f3b1ca9da511a52168e61c92498723b5b95d121bdf4b2cf14fd3c7c628264 -->
```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
ERR
The translation is using simplified Chinese ("隐藏") instead of the Cantonese (Hong Kong) standard, which should use traditional Chinese characters. Also, "Peers" here refers to "nodes" or "peers" in a network context, not "other people". The translation "其他人的详细信息" is inaccurate; it means "the detailed info of other people".

Correct translation:
隱藏同儕詳情
```

<!-- cache_translation_check_zh_HK_acfc15e6cdcc097420e5b897a9273401debf4fb2a07190ce4e6a81196ff794c6 -->
```
        <source>Decrease font size</source>
        <translation>缩小字体大小</translation>
    
ERR
The translation uses Simplified Chinese ("缩小字体大小") instead of Traditional Chinese, which is preferred for 'zh_HK' (Hong Kong). 

Correct translation:
縮小字體大小
```

<!-- cache_translation_check_zh_HK_6558c9782f226d33010d56f97a7bf13c5151f12add65365f0abf81b8ae9554d1 -->
```
        <source>&amp;Open</source>
        <translation>打开(&amp;O)</translation>
    
ERR
The translation is in Simplified Chinese format ('打开(&amp;O)'), but for 'zh_HK' (Hong Kong Cantonese), the traditional character '開啟' is typically preferred, and the shortcut key position should follow Hong Kong localization standards. Also, in zh_HK, the shortcut letter is usually placed before the parentheses, e.g., '開啟(&amp;O)'.

Correct translation:
開啟(&amp;O)
```

<!-- cache_translation_check_zh_HK_294a6b69c8397bcbe46ef5b4e5f1d3feee9e2d9c3a4b4f1ce25d159ee9c964cc -->
```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
ERR
The translation is inaccurate. "用於短暫，暫時 測試地址" means "used for a short time, temporary test address," which doesn't accurately convey "for soliciting addresses" (i.e., for requesting addresses). Also, there is an unnecessary space before "測試地址", and "Outbound" should be translated properly into Chinese.

Correct translation:
Outbound 地址擷取：短暫使用，用於向對方請求地址
```

<!-- cache_translation_check_zh_HK_3b922fbc637e1d9d4fd21b3656a168f67a4ad2c125c758255ea2914b3e9f2c0b -->
```
        <source>1 &amp;hour</source>
        <translation>1 小时(&amp;H)</translation>
    
ERR
The translation uses Simplified Chinese "小时" and the shortcut key (&H) is based on the English word "hour". For 'zh_HK' (Traditional Chinese for Hong Kong), "小時" should be used, and the shortcut key should preferably match a character in the translation (e.g., "小" or "時"), unless product guidelines require English shortcuts.

Correct translation:
1 小時(&amp;H)
or, better fit for 'zh_HK' locale:
1 小時(&amp;小)
```

<!-- cache_translation_check_zh_HK_8b5955a6a1e135aae44745f02687277c90bd3df0dd2fd8b7f3f4e99139bb5b6a -->
```
        <source>1 d&amp;ay</source>
        <translation>一天</translation>
    
ERR
The translation omits the '&' which is used for indicating a shortcut key and could be important in the UI. Additionally, the translation does not retain the '1' and may confuse users if there are other durations (e.g., 2 days). A more accurate translation would be:

Correct translation:
1 天(&A)
```

<!-- cache_translation_check_zh_HK_951f8deb31a00eafd4104d5e9d37118f531185afb8c75df695e469770db517a2 -->
```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>欢迎来到 %1 RPC 控制台。
使用上与下箭头以进行历史导航，%2 以清除屏幕。
使用%3 和 %4 以增加或减小字体大小。
输入 %5 以显示可用命令的概览。
查看更多关于此控制台的信息，输入 %6。

%7 警告：骗子们很活跃，告诉用户在这里输入命令，偷走他们钱包中的内容。不要在不完全了解一个命令的后果的情况下使用此控制台。%8</translation>
    
ERR
The translation is mostly accurate, but there is a minor issue with the placement of spaces in format specifiers, particularly for "%3 和 %4", where there is a missing space before "%3", which creates inconsistency. Additionally, '%7警告' should not have a space after '%7' to mimic the original formatting, where '%7WARNING:' has no space between '%7' and 'WARNING'. Also, the tone and style are otherwise appropriate.

Correct translation:
歡迎來到 %1 RPC 控制台。
使用上與下箭頭以進行歷史導航，%2 以清除屏幕。
使用 %3 和 %4 以增加或減小字體大小。
輸入 %5 以顯示可用命令的概覽。
查看更多關於此控制台的信息，輸入 %6。

%7警告：騙子活動頻繁，會指示用戶在此輸入指令，竊取他們的錢包資產。未完全了解指令後果前，切勿在此控制台操作。%8

主要修正如下：
- 「%3 和 %4」前後空格統一。
- 「%7警告」去除多餘空格，以符合原文格式。
- 用詞稍作地區化（例如「輸入指令」和「錢包資產」會更貼近港澳地區用法）。

如果需要繁體中文香港用語風格，可以根據具體情境微調詞彙。
```

<!-- cache_translation_check_zh_HK_a6e9d6abcc4431799e73f806331c34124d5e3cf2ac80d23af4c298249010502b -->
```
        <source>Copy &amp;amount</source>
        <translation>复制和数量</translation>
    
ERR
The translation does not preserve the shortcut key (&) from the source, and the phrase "复制和数量" is an incorrect translation for "Copy &amount". The correct translation should be:

正确翻译：
複製金額(&A)
```

<!-- cache_translation_check_zh_HK_d5b7f50fbccf0a2d8611f9433bfc9db677127483cccdfd4cf1ff4b35c96a762c -->
```
        <source>&amp;Save Image…</source>
        <translation>保存图像(&amp;S)...</translation>
    
ERR
The translation uses Simplified Chinese "图像" instead of Hong Kong Traditional Chinese "圖像". Also, the ellipsis should be the full-width "…" to match the source, not three dots "...". 

Correct translation:
保存圖像(&amp;S)…
```

<!-- cache_translation_check_zh_HK_f670d3a58052289b036cc94a1bb6c9c5a9b7fa220a78c7aa163c8c969b4eb7ff -->
```
        <source>Custom change address</source>
        <translation>自定义找零地址</translation>
    
ERR
The translation "自定义找零地址" is in simplified Chinese ('zh_CN'), not in traditional Chinese as needed for 'zh_HK'. While the meaning is clear and correct, the characters should be adapted to traditional Chinese for Hong Kong.

Correct translation:
自訂找贖地址
```

<!-- cache_translation_check_zh_HK_c8e7df6fe27cbbac858e2000b4d432d7ba54a3ceb7e11101b98dda4b813b498c -->
```
        <source>Choose…</source>
        <translation>选择...</translation>
    
ERR
The translation uses simplified Chinese characters ("选择..."), while 'zh_HK' should use traditional Chinese characters consistent with the Hong Kong locale. The ellipsis character is also different (should use "…").

Correct translation:
選擇…
```

<!-- cache_translation_check_zh_HK_184ccd2ce21a92e618dc514e5dd4416c554070deec6cce83d3cf3fb1b2217690 -->
```
        <source>Enable Replace-By-Fee</source>
        <translation>启用手续费追加</translation>
    
ERR
The provided translation uses simplified Chinese ("启用") rather than traditional Chinese as customary in 'zh_HK' (Hong Kong). Additionally, "手续费追加" does not clearly express "Replace-By-Fee” (RBF). A more accurate 'zh_HK' translation matching the context would be:

啟用可替代手續費 (RBF)
```

<!-- cache_translation_check_zh_HK_90b92531e1ef339bbba4c9ef552afff81ce69fd057cdd1320fd552110d86e714 -->
```
        <source>Copy change</source>
        <translation>复制找零金额</translation>
    
ERR
The translation uses Simplified Chinese characters ("复制找零金额") while zh_HK should use Traditional Chinese. Also prefer the common phrasing for "copy" in Traditional Chinese.

Correct translation:
複製找零金額
```

<!-- cache_translation_check_zh_HK_e4079e28ced2a31c5cd45858ad968288f613986dd93679a9d3f83cef844e9a62 -->
```
        <source>Sign on device</source>
        <extracomment>"device" usually means a hardware wallet.</extracomment>
        <translation>在設備上簽證</translation>
    
ERR
The word "簽證" in Chinese means "visa," which is not appropriate in this context. For digital signing, the correct term is "簽名". Also, the phrase is generally correctly translated as "在設備上簽名".

Correct translation:
在設備上簽名
```

<!-- cache_translation_check_zh_HK_070c587fbb4ed6d06fe006cbce66dae59f8480ae60cbd56f50e09c90fb4e8ad5 -->
```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
ERR
The translation is problematic. The sentence structure is awkward and the clause "然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。" introduces a period in the middle of a phrase, which damages clarity. The translation is also missing the connective sense that you can sign with (for example) an offline %1 wallet or a PSBT-compatible hardware wallet.

Correct translation:
請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製，然後使用例如離線的 %1 錢包或支援 PSBT 的硬件錢包進行簽名。
```

<!-- cache_translation_check_zh_HK_bf8ba99f2cc2ec40893412f7c0f6a8121eab5c115f5d23b2c9aa2778e3f7a8ad -->
```
        <source>Confirm send coins</source>
        <translation>确认发币</translation>
    
ERR
The translation uses Simplified Chinese ("确认发币") instead of Hong Kong Cantonese/traditional Chinese with localized phrasing. In a Hong Kong context, "确认發送比特幣" or "確認發送貨幣" would be more appropriate. Also, the term "發幣" is not commonly used in formal Hong Kong interfaces; "發送" (send) is better.

Correct translation:
確認發送比特幣
```

<!-- cache_translation_check_zh_HK_28469b6bdd232ba1dcfd58e7d6028a052f194701749fcdb0f461d138b0475935 -->
```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
ERR
The translation has incorrect word order and an extra character "給" at the end, which is unnecessary and ungrammatical in this context. It should be:

Correct translation:
用來接收付款的比特幣地址

or more literally:
接收付款的比特幣地址
```

<!-- cache_translation_check_zh_HK_ca3390ffc9863c0f4e806158faae1a615527f0e15092c5510c372d12ae31e99b -->
```
        <source>Send</source>
        <translation>发送</translation>
    
ERR
The translation uses the simplified Chinese character "发送", which is appropriate for 'zh_CN' (Mainland China), but 'zh_HK' (Hong Kong) generally uses traditional characters. The correct traditional Chinese translation should be "發送".

Correct translation:
發送
```

<!-- cache_translation_check_zh_HK_7122d22b42a374647712e18883ce57d0104df59b111d6a92097fde2a0828eaba -->
```
        <source>Copy the current signature to the clipboard</source>
        <translation>复制当前签名至剪贴板</translation>
    
ERR
The translation uses Simplified Chinese characters (e.g. "复制", "当前", "剪贴板") but the target locale zh_HK should use Traditional Chinese. No format specifiers are involved and spacing is fine.

Correct translation (Traditional Chinese, Hong Kong style):
複製當前簽名到剪貼簿
```

<!-- cache_translation_check_zh_HK_d7752991ac6a274d159926c5a02c869616ac4deb4e7a549decf62a5341beb1f4 -->
```
        <source>Verify &amp;Message</source>
        <translation>验证消息签名(&amp;M)</translation>
    
ERR
The translation uses Simplified Chinese terminology ("验证消息签名") instead of Hong Kong Traditional Chinese. Also, the translation deviates from the original meaning. The source refers to verifying a "message," not specifically a "message signature." The ampersand shortcut (&) has been moved but exists only once, which is correct.

Correct translation:
驗證訊息(&amp;M)
```

<!-- cache_translation_check_zh_HK_b30b02c9c230b27e6acd4bf63a996edfee94681a53420ab2ebadabc12d8f5f4e -->
```
        <source>Sent to</source>
        <translation>发送到</translation>
    
ERR
The translation "发送到" is in Simplified Chinese ('zh_CN'), not Traditional Chinese as required for 'zh_HK'. In 'zh_HK', the translation should use Traditional Chinese characters and local phrasing.

Correct translation:
發送至
```

<!-- cache_translation_check_zh_HK_b30b02c9c230b27e6acd4bf63a996edfee94681a53420ab2ebadabc12d8f5f4e -->
```
        <source>Sent to</source>
        <translation>发送到</translation>
    
ERR
The translation "发送到" is in Simplified Chinese ('zh_CN'), not Traditional Chinese as required for 'zh_HK'. In 'zh_HK', the translation should use Traditional Chinese characters and local phrasing.

Correct translation:
發送至
```

<!-- cache_translation_check_zh_HK_3d126a78589dc7f62fd207a4bd0d3bcc8585630d77ddf615b918ee2d22169413 -->
```
        <source>Range…</source>
        <translation>范围...</translation>
    
ERR
The translation uses Simplified Chinese ("范围") rather than Traditional Chinese as used in 'zh_HK'. Also, the ellipsis character "…" in the source is replaced with three periods "...", which is inconsistent with the source format.

Correct translation:
範圍…
```

<!-- cache_translation_check_zh_HK_a6e9d6abcc4431799e73f806331c34124d5e3cf2ac80d23af4c298249010502b -->
```
        <source>Copy &amp;amount</source>
        <translation>复制和数量</translation>
    
ERR
The translation does not preserve the shortcut key (&) from the source, and the phrase "复制和数量" is an incorrect translation for "Copy &amount". The correct translation should be:

正确翻译：
複製金額(&A)
```

<!-- cache_translation_check_zh_HK_ad178d236f7dfa4296cb4b108c9b445b440409cbd25c6a94f7a622b8b998490f -->
```
        <source>Copy full transaction &amp;details</source>
        <translation>複製完整交易明細</translation>
    
ERR
The shortcut key indicator (&) from the source is missing in the translation. In zh_HK translations, the & can be added anywhere, but it must appear exactly once to match the source, often in front of a character in the menu label.

Correct translation:
複製完整交易&amp;明細
```

<!-- cache_translation_check_zh_HK_ad835176286ec5001b2d46ca1cecbac97741bc5c25c342e04972405d7b6424e8 -->
```
        <source>&amp;Show transaction details</source>
        <translation>顯示交易明細</translation>
    
ERR
The translation is missing the '&' used for the shortcut key, which should appear exactly once. 

Correct translation:
&顯示交易明細

or 

顯示交易明細(&S) 

Either method is acceptable for shortcut keys in 'zh_HK' Windows software localization.
```

<!-- cache_translation_check_zh_HK_2121ef868142997a35319d5921dc03e4c8045f37da8a2f5b0a73dc71658a9a44 -->
```
        <source>&amp;Export</source>
        <translation>匯出 &amp;E</translation>
    
ERR
The ampersand (&) is intended to mark the shortcut key and should appear exactly once, but in the Hong Kong Chinese ('zh_HK') translation, it appears after the word instead of before the shortcut letter. In Cantonese/Hong Kong style, the English shortcut letter is usually retained in parentheses, or at the end with the ampersand correctly placed.

Correct translation:
匯出(&E)
or
&匯出

The placement of "&" before "E" in "匯出 &amp;E" is non-standard and may not correctly display the shortcut key in the UI.
```

<!-- cache_translation_check_zh_HK_c7322b733fb6e07eeb0c5a4f89faf9d956509351ec4b36c6ad2b25b6f1a6acf6 -->
```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
ERR
There is an unnecessary line break before "%s" in the translated text, causing a formatting issue. Also, "獲得" is less natural than "收到" or "獲得了". For clarity and conformity with the original structure, the sentence should not break across lines, and the wording can be slightly refined.

Correct translation:
錯誤：轉存檔案識別記錄不正確。收到「%s」，預期「%s」。
```

<!-- cache_translation_check_zh_HK_78a3727db7b2c58049bfbe79faf011a77473fd002f75700a072bffc43d41b2bc -->
```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
ERR
1. The Chinese translation uses "多數TOR路由綁定位址", but "onion bind address" should be accurately rendered as "onion 綁定地址" or "onion 綁定位址", not "TOR路由綁定位址".
2. There is a missing space between sentences: "位址。 對自動建立的..." should remove the space after "。".
3. The translation omits "onion service", only saying "Tor服務", which is insufficiently specific.
4. "提供多數" translates to "provide multiple", but "More than one" is better translated as "超過一個".

Correct translation:
提供超過一個 onion 綁定位址。將使用 %s 作為自動建立的 Tor onion 服務。
```

<!-- cache_translation_check_zh_HK_07c08410f35b55ee98ef9afdcfa739ea01556b95cd8af62efa42cf316ef8f3f8 -->
```
        <source>%s is set very high! Fees this large could be paid on a single transaction.</source>
        <translation>%s被设置得很高! 这可是一次交易就有可能付出的手续费。</translation>
    
ERR
The translation is understandable but has minor stylistic and punctuation issues inconsistent with 'zh_HK' (Hong Kong Cantonese) conventions. The exclamation mark should have a space before it according to CJK standards, and the tone is a bit off for HK Cantonese—should be more colloquial. Also, contextually, "这可是一次交易就有可能付出的手续费。" is awkward and doesn't accurately capture the warning tone or the information conveyed in the original.

Correct translation:
%s 設定得非常高！呢個咁大嘅手續費一單交易都可能要畀晒。
```

<!-- cache_translation_check_zh_HK_18bade23e7020ac53d848de22998bef5b810b09241ad945718f1ae969a10591e -->
```
        <source>Error: Duplicate descriptors created during migration. Your wallet may be corrupted.</source>
        <translation>错误：迁移过程中创建了重复的输出描述符。你的钱包可能已损坏。</translation>
    
ERR
The translation uses simplified Chinese ("错误", "迁移", "创建", "描述符", "你的", "已损坏") instead of the expected traditional Chinese appropriate for 'zh_HK'. For Hong Kong ('zh_HK'), the translation should use traditional Chinese characters and local wording.

Correct translation:
錯誤：在遷移過程中建立了重複的描述符。你的錢包可能已損壞。
```

<!-- cache_translation_check_zh_HK_90fda8f6932228d174e380ed1c7df7be7ae98d00ff1e42c56766226c0f6bb80a -->
```
        <source>Option '-checkpoints' is set but checkpoints were removed. This option has no effect.</source>
        <translation>选项“-checkpoints”已设置，但检查点已被移除。该选项不再生效。 </translation>
    
ERR
The translation is in Simplified Chinese and contains a trailing space before the end tag. For zh_HK (Traditional Chinese) it should use Traditional characters and no extra whitespace.

Correct translation:
選項「-checkpoints」已設定，但檢查點已被移除。此選項無效。
```

<!-- cache_translation_check_zh_HK_d98c1c5ff4f9281f53e84a4630bcb6846485c6649d59a458ddb76aab8f1f87d3 -->
```
        <source>Option '-maxorphantx' is set but no longer has any effect (see release notes). Please remove it from your configuration.</source>
        <translation>选项“-maxorphantx”已设置，但已不再生效（参见发行说明）。请从您的配置中移除该选项。 </translation>
    
ERR
The translation is in Simplified Chinese (e.g., "选项", "发行说明") but for zh_HK it should use Traditional Chinese characters. There's also an extra trailing space before the closing tag.

Correct translation (Traditional Chinese for Hong Kong):
選項「-maxorphantx」已設定，但已不再生效（請參閱發行說明）。請從您的設定檔中移除該選項。
```

<!-- cache_translation_check_zh_HK_bf17affb0acd6713b9f6b2167f99961dbd921c30426c9f4b5f40c6272c0fa297 -->
```
        <source>Options '-datacarrier' or '-datacarriersize' are set but are marked as deprecated. They will be removed in a future version.</source>
        <translation>选项“-datacarrier”或“-datacarriersize”已设置，但已标记为弃用。它们将在未来版本中移除。 </translation>
    
ERR
The translation is in Simplified Chinese ( mainland ) rather than Traditional Chinese used for zh_HK, and there's an extra trailing space before the closing tag. No format specifiers issue.

Correct translation (Traditional Chinese for Hong Kong):
選項「-datacarrier」或「-datacarriersize」已設定，但已被標記為棄用。它們將在未來版本中移除。
```

<!-- cache_translation_check_zh_HK_fc44b6029c7dbac45686cc79b705b8c897f4c829f9f3f5057b0a8d2f641e4b4e -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>修剪：上次钱包同步超出了已修剪的数据范围。您需要执行“-reindex”（对于已修剪节点，需要重新下载整个区块链）。 </translation>
    
ERR
The translation is in Simplified Chinese (e.g., "钱包", "您") and contains a trailing space. For zh_HK (Traditional Chinese for Hong Kong) use Traditional characters and Hong Kong phrasing.

Correct translation:
修剪：上次錢包同步已超出已修剪的資料。您需要執行「-reindex」（對於已修剪的節點，需重新下載整個區塊鏈）。
```

<!-- cache_translation_check_zh_HK_eb968025b9240f22a7d27bd23c989a8fc00fef0ee8185f551adcffb7a2452904 -->
```
        <source>-paytxfee is deprecated and will be fully removed in v31.0.</source>
        <translation>“-paytxfee”已弃用，并将在 v31.0 中完全移除。 </translation>
    
ERR
The translation uses Simplified Chinese characters ("弃用", "移除") instead of Traditional Chinese used in zh_HK, and there is an extra trailing space before the closing tag. No format specifiers present.

Correct translation (Traditional Chinese for zh_HK), without trailing space:
“‑paytxfee” 已棄用，並會在 v31.0 完全移除。
```

<!-- cache_translation_check_zh_HK_a83d5bb13328c9c6bb05b9d617458f5b2f83d05560a3710195dfb9a046cf5907 -->
```
        <source>Cannot add WalletDescriptor to a non-descriptor wallet</source>
        <translation>无法将钱包描述符添加到非描述符钱包。</translation>
    
ERR
The translation is in Simplified Chinese ("无法...添加..."), but zh_HK should use Traditional Chinese. No format specifiers present.

Correct translation (Traditional Chinese for zh_HK):
無法將錢包描述符添加到非描述符錢包。
```

<!-- cache_translation_check_zh_HK_7fabb939c240330d61596107c938b130818e021e55701b8aa2132a1ecc76b3c8 -->
```
        <source>Could not generate scriptPubKeys (cache is empty)</source>
        <translation>无法生成脚本公钥（缓存为空）</translation>
    
ERR
The translation is in Simplified Chinese ("无法生成脚本公钥（缓存为空）") but zh_HK should use Traditional Chinese. No format specifiers are involved.

Correct translation (Traditional Chinese for zh_HK):
無法生成 scriptPubKeys（快取為空）
```

<!-- cache_translation_check_zh_HK_1d81021bd0f5e08586ea41fd27117444164eb2a4027d5da2c4780a799bdfbce5 -->
```
        <source>Could not top up scriptPubKeys</source>
        <translation>无法补充脚本公钥</translation>
    
ERR
The provided translation uses Simplified Chinese ("无法补充脚本公钥") but zh_HK should use Traditional Chinese characters. Also consider whether to keep the technical identifier "scriptPubKeys" untranslated — either is acceptable, but use Traditional characters for surrounding words.

Correct translation (Traditional Chinese):
無法補充腳本公鑰

Alternatively, keeping the technical term:
無法補充 scriptPubKeys
```

<!-- cache_translation_check_zh_HK_910e8e45f2245edb0e9a34b0a4cc0b2c7735f3aa67ec70cac9a632712ef55043 -->
```
        <source>Disk space is too low!</source>
        <translation>磁盘空间太低!</translation>
    
ERR
There are two issues:
1. The correct term in Hong Kong Cantonese should be "磁碟空間不足！" instead of "磁盘空间太低!", as "磁盘" and "空间太低" are more typical of Mainland Chinese usage ("磁碟" is used in Cantonese/HK, and "空間不足" is the idiomatic expression for "space is too low"/"insufficient space").
2. The exclamation mark should be a full-width Chinese exclamation mark: ！

Correct translation:
磁碟空間不足！
```

<!-- cache_translation_check_zh_HK_623bc8dd39c47fdc7c4f539266a2aa0efc4b2019c9de1fbb0808800cbfe69616 -->
```
        <source>Error: Couldn't create cursor into database</source>
        <translation>错误: 无法在数据库中创建指针</translation>
    
ERR
The translation uses Simplified Chinese ("错误: 无法在数据库中创建指针") instead of Traditional Chinese as is standard for 'zh_HK'. Additionally, "指针" should more properly be translated as "游標" (cursor) in database contexts for Chinese.

Correct translation:
錯誤：無法在資料庫中建立游標
```

<!-- cache_translation_check_zh_HK_ba4b31fafa76b68ee6fefc8e8b4a7ed3d6fda25fd4bbf4dacf08fa9950112849 -->
```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
ERR
The translation is incomplete and does not convey the "expected %s" part from the source. The sentence is also awkward due to word order.

Correct translation:
錯誤：轉存檔案的校驗和不匹配。計算得 %s，應為 %s
```

<!-- cache_translation_check_zh_HK_8ee0dfeba4ed3cda8cac10a98de3f474eb3de760eb406eae940799fc9fe863d3 -->
```
        <source>Error: Not all address book records were migrated</source>
        <translation>错误：并非所有地址簿记录都已迁移</translation>
    
ERR
The translation is in Simplified Chinese ( mainland 用字 ) rather than Traditional Chinese typically used for zh_HK. No format specifiers or spacing issues, but characters should be converted to Traditional Chinese.

Correct translation (Traditional Chinese for zh_HK):
錯誤：並非所有地址簿記錄已遷移
```

<!-- cache_translation_check_zh_HK_dcfdd6315d1b3193dbb4dc6ce9abd68a96a5907b5b641337cb01c5fe62fb1489 -->
```
        <source>Error: Not all transaction records were migrated</source>
        <translation>错误：并非所有交易记录都已迁移</translation>
    
ERR
The translation is accurate in meaning but uses Simplified Chinese characters, not the Traditional Chinese typically used for zh_HK. No format specifiers or whitespace issues.

Correct translation (Traditional Chinese for Hong Kong):
錯誤：並非所有交易記錄都已遷移
```

<!-- cache_translation_check_zh_HK_e99dedaf3bcb0124644a867cc5bf8c595facdc7958e168c4eb407adc3aacf17b -->
```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
ERR
The translation contains a typo: "unit32_t" should be "uint32_t". Also, in 'zh_HK', it's better to use traditional Chinese and Cantonese writing style.

Correct translation:
錯誤：無法將版本號 %u 解析為 uint32_t
```

<!-- cache_translation_check_zh_HK_8b1135fb065982e6c8ee05d3643b9ebb06cd5f98d94108205cfa2556397adb94 -->
```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
ERR
The translation is understandable but the word order is unnatural in Chinese (Hong Kong), and the placement of "%s" is awkward. The standard wording would place "%s" immediately after "钱包". Also, the term "错误" is simplified Chinese; in Hong Kong (zh_HK), the traditional form "錯誤" is used.

Correct translation:
錯誤：無法將資料寫入錢包 %s 的磁碟。
```

<!-- cache_translation_check_zh_HK_48efbd247f46f842be8b3a32001673fdef3721daddd55e336de8f3c35111412b -->
```
        <source>Failed to acquire rescan reserver during wallet initialization</source>
        <translation>在钱包初始化期间未能获取重扫预留器</translation>
    
ERR
Uses Simplified Chinese vocabulary/characters ("钱包", "期间", "获取") and the term "重扫预留器" is a bit unnatural for zh_HK. No format specifiers issues.

Suggested zh_HK (Traditional) translation:
在錢包初始化期間未能取得重掃預留鎖
```

<!-- cache_translation_check_zh_HK_e4666fa4991fa511c3e025c7f0fca4b1e5628abb54946150622583f10c2a5101 -->
```
        <source>Failed to close block undo file.</source>
        <translation>关闭区块撤销文件失败。</translation>
    
ERR
The translation uses Simplified Chinese characters ("关闭", "文件") but zh_HK should use Traditional Chinese. No format specifiers or spacing issues, but the script is wrong.

Correct translation (Traditional Chinese, Hong Kong):
關閉區塊撤銷檔案失敗。
```

<!-- cache_translation_check_zh_HK_961038e6cbaa1ae82ba5e46b0198703ac89711bf28a9d48eccde01cc70f549ac -->
```
        <source>Failed to close file when writing block.</source>
        <translation>写入区块时关闭文件失败。</translation>
    
ERR
The translation uses Simplified Chinese characters ("写入区块时关闭文件失败。") but 'zh_HK' should use Traditional Chinese and Hong Kong terminology. Also prefer "檔案" over "文件" in Hong Kong usage.

Correct translation:
寫入區塊時無法關閉檔案。
```

<!-- cache_translation_check_zh_HK_bfba5479a7879ceb3a8fe1594b0469d71773b62d6ea3df387a6f180158c2e8e0 -->
```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
ERR
The translation does not follow the correct word order and format specifier placement. The colon appears at the end rather than after the failure message. Also, there is a missing space after the format specifier, and the word order is unnatural in Chinese.

Correct translation:
移除交易時失敗：%s
```

<!-- cache_translation_check_zh_HK_91b2d94152681a78c404c8e9dae514187a2b035ef69c33dc78b90f18caf7825f -->
```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
ERR
The translation has an error: "低于最大手续费率设置" means "lower than the maximum fee rate setting", but the source says "lower than the minimum fee rate setting". The word "最大" (maximum) should be "最低" (minimum).

Correct translation:
手续费率 (%s) 低于最低手续费率设置 (%s)
```

<!-- cache_translation_check_zh_HK_566d0feba5777abb1a5203621ad30e0aa5186da5ceea20cf696e7a20ac6f0fcb -->
```
        <source>Not found pre-selected input %s</source>
        <translation>找不到预先选择输入%s</translation>
    
ERR
The translation uses "预先选择输入" which is Simplified Chinese, not Traditional Chinese as appropriate for 'zh_HK'. In Cantonese or Hong Kong Traditional Chinese, it should be:

找不到預先選取的輸入 %s

Correct translation:
找不到預先選取的輸入 %s
```

<!-- cache_translation_check_zh_HK_d70833bdf605e8be453919d3d34d8544f8da9ac58042a58d440772455a7ab4eb -->
```
        <source>Pruning blockstore…</source>
        <translation>修剪区块存储...</translation>
    
ERR
The translation uses simplified Chinese characters ("修剪区块存储..."), which are not standard for 'zh_HK' (Hong Kong Chinese, which prefers traditional Chinese characters). The ellipsis should also match typographically (…).

Correct translation:
修剪區塊存儲…
```

<!-- cache_translation_check_zh_HK_31858be505051e38dd1b91b7fd358da6a776adc9de7310a3806b5d3ab32c3a70 -->
```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
ERR
There is a redundancy in the phrase "不不可为负数" ("not not allowed to be negative"). The correct expression should be "交易金額不可為負數" in Traditional Chinese used in Hong Kong ('zh_HK').

Correct translation:
交易金額不可為負數
```

<!-- cache_translation_check_zh_HK_3d9320bea10d5e3e022a19cfd842e427af4d3ea041c7f0b8f6e7b309e8193b04 -->
```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
ERR
The translation is inaccurate. The English "Transaction change output index out of range" means that the index of the change output in the transaction is outside the allowable range. However, "交易尋找零輸出項超出範圍" awkwardly translates to "Transaction seeks zero output item out of range", which is incorrect and confusing in the context of Bitcoin.

Correct translation:
交易找零輸出索引超出範圍
```

<!-- cache_translation_check_zh_HK_76b1bd6861e77279c4c3f4a191a4d295d0696f1f0ea13e7ad0a7140d44da079c -->
```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
ERR
The translation has an error: "1%s" is incorrect and introduces an unwanted '1' before the format specifier, which is not in the original string. The proper format specifier should be carried over as "%s".

Correct translation:
錢包文件建立失敗：%s
```

<!-- cache_translation_check_zh_HK_e3222f6658880630ea81b0a0cd483e7c2b2346ce99656d5b087dfe9f4559eb98 -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>加载 %s时出错：钱包为传统钱包。请使用迁移工具（migratewallet RPC）迁移到描述符钱包。</translation>
    
ERR
The provided translation uses Simplified Chinese characters and wording rather than Traditional Chinese for zh_HK.

Correct translation (Traditional Chinese, Hong Kong style):
載入 %s 時出錯：錢包為舊式錢包。請使用遷移工具（migratewallet RPC）遷移至描述符錢包。
```

<!-- cache_translation_check_zh_HK_fb9c57de56fb521dfdc9b8cd4124ea9b1e9e4d83d4064c6624a1a81414b0eed7 -->
```
        <source>Error: Dumpfile specifies an unsupported database format (%s). Only sqlite database dumps are supported</source>
        <translation>错误：转储文件指定了不受支持的数据库格式 %s。仅支持 sqlite 数据库转储。</translation>
    
ERR
The translation uses Simplified Chinese characters (错误，转储，支持) but 'zh_HK' should use Traditional Chinese. It also removed the parentheses around (%s) from the source and added an extra space before %s. Preserve the parentheses and use Traditional characters.

Correct translation (Traditional Chinese for zh_HK):
錯誤：轉存檔指定了不支援的資料庫格式（%s）。僅支援 sqlite 資料庫的轉存。
```

<!-- cache_translation_check_zh_HK_8b55b394728eedb61271a1a6a5e595bcdfd17b62667645e79819597cc138275c -->
```
        <source>Transaction requires one destination of non-zero value, a non-zero feerate, or a pre-selected input</source>
        <translation>交易需要至少满足以下之一：一个非零金额的收款地址、非零费率，或预先选择的输入。</translation>
    
ERR
The translation uses Simplified Chinese wording/characters but the target 'zh_HK' should use Traditional Chinese. Also slightly adjust phrasing to sound natural in Hong Kong usage.

Correct translation (Traditional Chinese for zh_HK):
交易需要符合以下其中一項：一個非零金額的收款地址、非零手續費率，或預先選定的輸入。
```

<!-- cache_translation_check_zh_HK_7ac1efa37e812c3d7101f033238c56c685efb44247b49ad8368f92f5497fdb8a -->
```
        <source>Unrecognized descriptor found. Loading wallet %s

The wallet might have been created on a newer version.
Please try running the latest software version.
</source>
        <translation>发现无法识别的描述符。正在加载钱包 %s 

该钱包可能是在较新版本中创建的。 
请尝试运行最新的软件版本。
</translation>
    
SPAM
The translation is in Simplified Chinese (zh_CN), not Hong Kong Traditional Chinese (zh_HK).

Correct zh_HK (Traditional) translation, keeping %s and line breaks:
發現無法識別的描述符。正在載入錢包 %s

該錢包可能是在較新版本中建立的。
請嘗試執行最新的軟件版本。
```

<!-- cache_translation_check_zh_HK_5ba898a8fa4f257290a83a80d886d905097a84541cf1159ac1fa2c13a3e5a715 -->
```
        <source>Failed to start indexes, shutting down…</source>
        <translation>索引启动失败，正在关闭……</translation>
    
ERR
The translation uses Mainland/Simplified Chinese wording ("启动", "关闭") rather than Traditional characters expected for zh_HK. Also prefer Traditional phrasing for Hong Kong.

Correct translation:
索引啟動失敗，正在關閉…
```

<!-- cache_translation_check_zh_HK_3893aa5cc96d3a3e6fda580d5592a8e0694e08745e5bb4cb9823521e2db3de13 -->
```
        <source>Invalid -proxy address or hostname, ends with '=': '%s'</source>
        <translation>无效的 -proxy 地址或主机名，以“=”结尾：“%s”。</translation>
    
ERR
The translation uses Simplified Chinese ("无效的", "主机名") but zh_HK should use Traditional Chinese and Hong Kong terminology. The format specifier %s is kept correctly, but punctuation/spacing can be normalized.

Correct translation (Traditional zh_HK):
無效的 -proxy 位址或主機名稱，結尾為 '='：'%s'
```

<!-- cache_translation_check_zh_HK_8a65190ca204502b79b6c300f73c685661424c04e29136c9be3e8dc44a9de4b3 -->
```
        <source>Unrecognized network in -proxy='%s': '%s'</source>
        <translation>无法识别 -proxy=“%s” 中的网络：“%s”。</translation>
    
ERR
The translation uses Simplified Chinese ("无法识别", "网络") but 'zh_HK' should use Traditional Chinese. Also prefer to keep the format specifiers and quoting consistent with the source.

Correct translation (Traditional Chinese for Hong Kong):
無法識別 -proxy='%s' 中的網絡：'%s'
```
</details>

Number of issues: 116.
