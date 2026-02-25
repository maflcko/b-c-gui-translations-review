# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bzh_TW%5D%20request)



<details><summary>zh_TW</summary>


<!-- cache_translation_check_zh_TW_0612e8aef0b85cca15b3d2220e063d00d5e249fa27727fd2ab0830cdcc07978c -->
```
        <source>Copy the currently selected address to the clipboard</source>
        <translation>复制当前选中的地址到剪贴板。</translation>
    
ERR
The translation uses Simplified Chinese characters (SC) instead of Traditional Chinese characters (TC) as requested for the language code 'zh_TW'. Additionally, it includes a trailing period which is not present in the source text.

Correct translation:
複製目前選取的地址至剪貼簿
```

<!-- cache_translation_check_zh_TW_a5ec2339e35ef405ab65eaf0e56ac471a04688c0d0a27174d3764505ac1525dd -->
```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>逗號分隔文件</translation>
    
ERR
The term '文件' (wénjiàn) is more commonly used in Mainland China (zh_CN). In Taiwan (zh_TW), '檔案' (dàng'àn) is the standard term for a computer "file".

Correct translation:
逗號分隔檔案
```

<!-- cache_translation_check_zh_TW_ed8c8da5fc967e39bead4f02d66e09dcf786bdebb57759a15b41984a40b4fcbf -->
```
        <source>Label</source>
        <translation>標記:</translation>
    
ERR
The translation includes a trailing colon ':' which is not present in the source text. In Bitcoin software UI contexts, "Label" is typically translated without the colon unless the source includes it.

Correct translation:
標記
```

<!-- cache_translation_check_zh_TW_f2534126929c7c679fc576151c3679254c23ba66cf242be674778ed4239bd99c -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>輸入錢包的新密碼短語。&lt;br/&gt;請使用&lt;b&gt;個或10個以上隨機字符&lt;/b&gt;或&lt;b&gt;個8個以上單詞&lt;/b&gt;的密碼。</translation>
    
ERR
The translation contains grammatical errors and incorrect terminology for the 'zh_TW' (Taiwan) locale. The phrases "個或10個以上" and "個8個以上" are ungrammatical. Additionally, "字符" is a Simplified Chinese term; "字元" is the standard term in Traditional Chinese for "character".

Correct translation:
輸入錢包的新密碼短語。<br/>請使用包含 <b>10 個或更多隨機字元</b>，或 <b>8 個或更多單詞</b>的密碼短語。
```

<!-- cache_translation_check_zh_TW_23d6fefa4b3fcbb0ee0f7fdc2b7b5ff16a37f43bc1631f0c44051481c5a884f7 -->
```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>輸入錢包的密碼短語和新密碼短語。</translation>
    
ERR
The translation misses the word "old" (舊的) and repeats "passphrase" without clarifying the sequence clearly. The term "密碼短語" is a bit literal; in Bitcoin Core context for zh_TW, "密碼" or "密碼短語" is used, but the source specifically asks for the "old" and "new" ones.

Correct translation:
輸入錢包的舊密碼短語與新密碼短語。
```

<!-- cache_translation_check_zh_TW_f1f875bc7ab1697adecfc05c04bc4f3f85d2531cb22511a87c9fa7dbac1a3e32 -->
```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>請記得, 即使將錢包加密, 也不能完全防止因惡意軟體入侵, 而導致位元幣被偷.</translation>
    
ERR
The translation contains unnecessary punctuation (stray commas) and uses some terms that are less standard in Traditional Chinese (Taiwan). Specifically, there is a space after the first comma, and the commas break the sentence flow unnaturally.

Correct translation:
請記住，加密您的錢包並不能完全防止您的位元幣被感染電腦的惡意軟體偷走。
```

<!-- cache_translation_check_zh_TW_a32fbf66116af9abe3c93c4afef478da058b06c908b1ff3a2cce7c02fdcdea38 -->
```
        <source>Your wallet is about to be encrypted. </source>
        <translation>你的錢包將被加密</translation>
    
ERR
The translation is missing the trailing space present in the source text and ends without the period, making it slightly inconsistent with the source formatting.

Correct translation:
你的錢包即將被加密。
```

<!-- cache_translation_check_zh_TW_7c6b76b3211ce95b89838a14d38391216d4277fd44671c9f571aae1f53b03363 -->
```
        <source>Your wallet is now encrypted. </source>
        <translation>你的錢包現已被加密</translation>
    
ERR
The translation is missing the trailing space and the period that are present in the source text.

Correct translation:
你的錢包現已被加密。
```

<!-- cache_translation_check_zh_TW_5183f85114780d89ddc6879e54f121427b74a0aa47faac8d83f9f1671d9e3333 -->
```
        <source>Wallet passphrase was successfully changed.</source>
        <translation>錢包密碼改成功了。</translation>
    
ERR
The translation is too informal/colloquial for a software interface. The phrase "改成功了" (changed successfully) is common in speech but "已成功變更" is more standard for professional software contexts in Traditional Chinese (Taiwan).

Correct translation:
錢包密碼已成功變更。
```

<!-- cache_translation_check_zh_TW_e0e8968e5dce6fcd564119c063e35d7a19cef418bb79beefadfe2cac7f516762 -->
```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>設定檔%1可能已經失效或無效</translation>
    
ERR
The translation is missing the period at the end and uses slightly redundant phrasing for "corrupt or invalid". In traditional Chinese (zh_TW) technical contexts, "corrupt" is typically translated as "損毀".

Correct translation:
設定檔 %1 可能已損毀或無效。
```

<!-- cache_translation_check_zh_TW_857e23e7e1973f04063bfe63ea5f0211c4d81243fda8f4321ee9945b833e9a2c -->
```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>發生了內部錯誤%1 將嘗試安全地繼續。 這是一個意外錯誤，可以按如下所述進行報告。</translation>
    
ERR
There is a missing space between the internal error description and the format specifier %1, and an extra space after the first full stop.

Correct translation:
發生了內部錯誤。%1 將嘗試安全地繼續。這是一個意外錯誤，可以按如下所述進行報告。
```

<!-- cache_translation_check_zh_TW_3f90e8c27d44543ea7b499bfa7e4416c7e241a52f1d707de42e81f32d21e999e -->
```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>發生致命錯誤。檢查設置文件是否可寫入，或嘗試運行 -nosettings</translation>
    
ERR
The translation uses terminology more common in Mainland China ('設置' for settings, '文件' for file) and is missing the 'with' context for the command-line argument. In Traditional Chinese (Taiwan), '設定' and '檔案' are the standard terms.

Correct translation:
發生嚴重錯誤。請檢查設定檔是否可寫入，或是嘗試加上 -nosettings 參數執行。
```

<!-- cache_translation_check_zh_TW_b39ffd6ed8b0a57369b123e846dd701dedf0036d45125cb34ee0551a90405b8f -->
```
        <source>Error: %1</source>
        <translation>错误：%1</translation>
    
ERR
The translation uses Simplified Chinese characters instead of Traditional Chinese characters as required for 'zh_TW'. Specifically, "错误" (Simplified) should be "錯誤" (Traditional).

Correct translation:
錯誤：%1
```

<!-- cache_translation_check_zh_TW_4019e632310dea73c1c3a67edafd1040922f6f4274400d29927db1e1936014bd -->
```
        <source>Default system font "%1"</source>
        <translation>默认系统字体 "%1"</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) rather than Traditional Chinese (zh_TW). In Traditional Chinese, "默认" is typically expressed as "預設", and "字体" is written as "字型" or "字體".

Correct translation:
預設系統字型 "%1"
```

<!-- cache_translation_check_zh_TW_1d4d50356a6d37e9a65eefe4248ceecc505b510a4abaf25a6225631750fcc415 -->
```
        <source>Custom…</source>
        <translation>自定义...</translation>
    
ERR
The translation uses Simplified Chinese characters ('自定义') instead of Traditional Chinese characters ('自訂') which is appropriate for the 'zh_TW' (Taiwan) locale. Additionally, it uses three periods instead of the standard horizontal ellipsis character '…' or the Traditional Chinese ellipsis.

Correct translation:
自訂…
```

<!-- cache_translation_check_zh_TW_aa3f0385b6120be97df4f1a0311fb028830f25141c71517fcb98e8f399675f57 -->
```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>輸入 比特幣地址 (比如說 %1)</translation>
    
ERR
The translation contains an unnecessary space between the verb "輸入" (Enter) and the noun phrase "比特幣地址" (Bitcoin address), which is not standard in Chinese typography.

Correct translation:
輸入比特幣地址 (例如 %1)
```

<!-- cache_translation_check_zh_TW_cb0ebfa20467e46f7f2203a0dd2233affdd7e3504b99baa30cbbb4cb76b8988a -->
```
        <source>Full Relay</source>
        <extracomment>Peer connection type that relays all network information.</extracomment>
        <translation>完整转发</translation>
    
ERR
The translation uses Simplified Chinese characters ('转发') instead of Traditional Chinese characters ('轉發') as required for the 'zh_TW' (Taiwan) locale.

Correct translation:
完整轉發
```

<!-- cache_translation_check_zh_TW_dc1c5fed46500f4b661b01393d4b9e1239f27a028a5b204d5f7ef785ef5259a9 -->
```
        <source>Manual</source>
        <extracomment>Peer connection type established manually through one of several methods.</extracomment>
        <translation>手冊</translation>
    
ERR
In the context of Bitcoin peer connections (as indicated by the extracommment), "Manual" refers to a connection type established by the user manually, not a physical "manual" or "handbook". The translation "手冊" means "handbook/manual". The correct term for a manual action or connection type in this context is "手動".

Correct translation:
手動
```

<!-- cache_translation_check_zh_TW_d2cf2d9bca1241bf5206001a5592594151e99cc89df7aa0410d98324aa896d56 -->
```
        <source>Feeler</source>
        <extracomment>Short-lived peer connection type that tests the aliveness of known addresses.</extracomment>
        <translation>触须</translation>
    
SPAM
The translation provided ("触须") uses Simplified Chinese characters, which are used in Mainland China ('zh_CN'), rather than Traditional Chinese characters used in Taiwan ('zh_TW'). Additionally, in the context of Bitcoin Core, "Feeler" (a connection type to test node aliveness) is typically translated as "探測器" or "探測" in Traditional Chinese.

Correct translation:
探測器
```

<!-- cache_translation_check_zh_TW_0467b0276d62fd95ce9b8af3bd4c3e87347f98def98ee4a26f32868c51c98725 -->
```
        <source>%1 and %2</source>
        <translation>%1又 %2</translation>
    
ERR
There is a stray space after the word "又". In traditional Chinese (zh_TW), spaces are typically not used between characters and format specifiers in this context.

Correct translation:
%1又%2
```

<!-- cache_translation_check_zh_TW_b15a93ea58ca7043cb82eb05fbafa2f8fc0720bc3913e8b99ad82cd30fcb4ae0 -->
```
        <source>default wallet</source>
        <translation>默认钱包</translation>
    
ERR
The translation uses Simplified Chinese characters and terminology ("默认") instead of Traditional Chinese characters and terminology ("預設") as used in Taiwan (zh_TW).

Correct translation:
預設錢包
```

<!-- cache_translation_check_zh_TW_a7c351c427df6d7b486104f1939aef897d1cfa92e831eea41d659421963ae8ce -->
```
        <source>&amp;Minimize</source>
        <translation>最小化</translation>
    
ERR
The translation is missing the shortcut key indicator '&' which was present in the source text.

Correct translation:
最小化(&M)
```

<!-- cache_translation_check_zh_TW_6a48bd30fe4e7cd2269014687f421baac1199561d91f0c02a5850a77330d53b2 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>备份钱包(&amp;B)</translation>
    
ERR
The translation uses Simplified Chinese characters ("备份") instead of Traditional Chinese characters ("備份") which are used in the 'zh_TW' (Taiwan) locale.

Correct translation:
備份錢包(&B)
```

<!-- cache_translation_check_zh_TW_54eba313b1f7705aba04afbe18023343277ec9a90b81ddf9082862e28be58fc8 -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>修改密码(&amp;C)</translation>
    
ERR
The translation is in Simplified Chinese characters (密码) instead of Traditional Chinese characters (密碼) as required by the 'zh_TW' locale. Additionally, "修改" is commonly used, but "變更" is more standard in this specific software context for Traditional Chinese.

Correct translation:
變更密碼(&amp;C)…
```

<!-- cache_translation_check_zh_TW_50c13beebc23be4c5fec21866f35ebd53ff4586cd71628fbe1c3dc8e0e5a3c61 -->
```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>驗證訊息是用來確定訊息是用指定的比特幣地址簽名的</translation>
    
ERR
The translation is wordy and grammatically awkward. It translates "Verify messages to ensure..." as "Verifying messages is used to determine that...", which changes the tone from an action/feature description to a definition.

Correct translation:
驗證訊息以確認它們是用指定的比特幣地址簽署的
```

<!-- cache_translation_check_zh_TW_6c856fbf154faf315ca0802bc632798d0930e79b9382d4d4ad524e02e3ae18ee -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>从文件加载PSBT(&amp;L)...</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) rather than Traditional Chinese (zh_TW) as requested. In Traditional Chinese, "从" should be "從", and "文件" is typically translated as "檔案". Additionally, the source uses an ellipsis character "…" instead of three dots "...".

Correct translation:
從檔案載入 PSBT(&amp;L)…
```

<!-- cache_translation_check_zh_TW_b35c98ce1dd8be15f452fdee42e555768e022373c29e11100b4cd066a00846c1 -->
```
        <source>Open &amp;URI…</source>
        <translation>打开&amp;URI...</translation>
    
ERR
The translation uses a Simplified Chinese character ("开") instead of the Traditional Chinese character ("開") required for the 'zh_TW' locale. Furthermore, "開啟" is the standard terminology for "Open" in software contexts in Taiwan, whereas "打开" is more common in Mainland China. Additionally, the source uses a single ellipsis character (…), but the translation uses three periods (...).

Correct translation:
開啟 &amp;URI…
```

<!-- cache_translation_check_zh_TW_959c16ffaca69fc3d6fbf70a5b759e74557ee0b24442f52a5d2b5845646674c7 -->
```
        <source>Close Wallet…</source>
        <translation>关闭钱包...</translation>
    
ERR
The translation uses Simplified Chinese characters ('关闭钱包') instead of Traditional Chinese characters as required for the 'zh_TW' (Taiwan) locale. Additionally, it uses three standard periods instead of the horizontal ellipsis character.

Correct translation:
關閉錢包...
```

<!-- cache_translation_check_zh_TW_af3e16b29457207e5532a4fd697c8df1f8f0ea0737e20ed17d82e75835bbef81 -->
```
        <source>Create Wallet…</source>
        <translation>创建钱包...</translation>
    
ERR
The translation uses Simplified Chinese characters instead of Traditional Chinese characters as required by the 'zh_TW' language code. Additionally, it uses three periods instead of the ellipsis character.

Correct translation:
建立錢包…
```

<!-- cache_translation_check_zh_TW_acd82d01dd14b04dc1a835c30e7022782e0ef028e62202d78b7874fe7559f145 -->
```
        <source>Indexing blocks on disk…</source>
        <translation>对磁盘上的区块进行索引...</translation>
    
ERR
The translation is written in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested. Specifically, "对" (Simplified) should be "對", and "磁盘" (Simplified) should be "磁碟".

Correct translation:
正在對磁碟上的區塊建立索引...
```

<!-- cache_translation_check_zh_TW_fcfbfeb4e0bb7910c6581552c56704953953e497f3e229a94f1b8d793fd35fd9 -->
```
        <source>Processing blocks on disk…</source>
        <translation>处理磁盘上的区块...</translation>
    
ERR
The translation uses Simplified Chinese characters ('处理', '磁盘') instead of Traditional Chinese characters ('處理', '磁碟') as required by the 'zh_TW' (Taiwan) locale. Additionally, it uses a standard triple period '...' instead of the horizontal ellipsis '…' used in the source.

Correct translation:
處理磁碟上的區塊…
```

<!-- cache_translation_check_zh_TW_26e0c71fd928bd3aa7426bf4de0df4b27ddf93b9ff59141b69edfbec78d4f391 -->
```
        <source>Catching up…</source>
        <translation>正在追上进度...</translation>
    
ERR
The translation uses Simplified Chinese characters and terminology ("进度") instead of Traditional Chinese (zh_TW) characters and terminology. In zh_TW, "進度" is used, and "正在追上..." or "同步中..." is more common in this context.

Correct translation:
正在追上進度...
```

<!-- cache_translation_check_zh_TW_ef6b2c94c98dd02f5b270c9851d19a705c8c650c4d366e9b8aed5e74588e886c -->
```
        <source>Last received block was generated %1 ago.</source>
        <translation>最近收到的區塊是在 %1 以前生出來的。</translation>
    
ERR
The word "生出來" (born/given birth to) is too colloquial and inappropriate for a technical context. In software localization, "產生" or "生成" is the standard translation for "generated".

Correct translation:
最近收到的區塊是在 %1 以前產生的。
```

<!-- cache_translation_check_zh_TW_42a695c10a15cebe8935b1a9013c83e954e990e2627b810a54a4e13beb932376 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>從剪貼簿載入PSBT</translation>
    
ERR
The translation is missing the shortcut key indicator '&' and the ellipsis '…' which were present in the source text.

Correct translation:
從剪貼簿載入 &PSBT…
```

<!-- cache_translation_check_zh_TW_76ae68398510bc24accf5342e8331d844f340c319439d86f2a3463a8c6de557c -->
```
        <source>&amp;Mask values</source>
        <translation>＆遮罩值</translation>
    
ERR
The translation uses a full-width ampersand '＆' (U+FF06) instead of the standard half-width ampersand '&' (U+0026) used for shortcut keys. Additionally, the spacing between the shortcut key marker and the text is inconsistent with standard UI translations.

Correct translation:
&遮罩值
```

<!-- cache_translation_check_zh_TW_a5fd8141329b1c85bfb33f313577cfe31d0c647903b969c0ff7a165cea19f4c5 -->
```
        <source>Mask the values in the Overview tab</source>
        <translation>遮蔽“概述”選項卡中的值</translation>
    
ERR
The translation uses terminology specific to Mainland China (zh_CN) but written in Traditional Chinese characters. In Taiwan (zh_TW), "Overview" is typically translated as "總覽" (instead of "概述") and "Tab" is "索引標籤" or "分頁" (instead of "選項卡"). Additionally, Traditional Chinese typically uses corner brackets 「 」 for UI elements.

Correct translation:
遮蔽「總覽」索引標籤中的數值
```

<!-- cache_translation_check_zh_TW_28a47257f2b40104a504b4e453c458ddfafe248571bc4081e7c04cdd24180868 -->
```
        <source>No wallets available</source>
        <translation>没有可用的钱包</translation>
    
ERR
The translation uses Simplified Chinese characters instead of Traditional Chinese characters as required by the 'zh_TW' locale.

Correct translation:
沒有可用的錢包
```

<!-- cache_translation_check_zh_TW_9c7ce63ffa1c45ef52e62f8abe6bdf1bc07c9180eaba62997cf3707c87dc16fc -->
```
        <source>Zoom</source>
        <translation>缩放</translation>
    
ERR
The translation provided is in Simplified Chinese ('zh_CN') instead of Traditional Chinese ('zh_TW') as requested. The character '缩' is simplified; the traditional equivalent is '縮'.

Correct translation:
縮放
```

<!-- cache_translation_check_zh_TW_03758936259b45b7ffed8c430a8978923644f27dd84a322c325ebdfc7083fa63 -->
```
        <source>Main Window</source>
        <translation>主窗口</translation>
    
ERR
The translation uses terminology from Mainland China ("窗口") rather than the standard terminology used in Taiwan ("視窗") for the language code 'zh_TW'.

Correct translation:
主視窗
```

<!-- cache_translation_check_zh_TW_288aac83bf952b4faa778bc98603999a0a404648c87babfb9f60f83f1c86ac95 -->
```
        <source>&amp;Hide</source>
        <translation>&amp;躲</translation>
    
ERR
The translation for "Hide" as "躲" (duǒ) is semantically awkward in a software UI context. "躲" usually implies "to hide oneself" or "to dodge". In a computer interface, the standard term for "Hide" (as in hiding a window or a UI element) is "隱藏".

Correct translation:
&隱藏
```

<!-- cache_translation_check_zh_TW_33bca437f3f31507a299a1badfb077ce2405c67a7ac37fa75a16364db159d1f5 -->
```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>顯示節點選項卡</translation>
    
ERR
The translation uses "選項卡" (tab), which is more common in Mainland China (zh_CN). In Taiwan (zh_TW), "分頁" or "標籤" is the standard terminology. Additionally, "Peers" refers to the specific peer-to-peer connections, often translated as "節點" (nodes) or "端點", but within the Bitcoin Core interface for zh_TW, "節點" is usually used for the "Node" window, and "節點" is also used for peers. However, the term "選項卡" is definitely not standard zh_TW.

Correct translation:
顯示節點分頁
```

<!-- cache_translation_check_zh_TW_f98978340b3dee7dea853d55b610cf3ef92e0cdc4f6fc9be06b4f2b7dc3d54dc -->
```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>關閉網路紀錄</translation>
    
ERR
The translation is inaccurate. "Network activity" refers to active network communication/traffic, but the translation "網路紀錄" means "network records" or "network logs". The correct term for activity in this context is "活動".

Correct translation:
關閉網路活動
```

<!-- cache_translation_check_zh_TW_950cb28cc0f57eebf6fb6e99e761a355724df12da7463d87aeda770e4eaacc26 -->
```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
ERR
The translation is the opposite of the source text. "Enable network activity" means to turn on the network function, but "關閉網路紀錄" means "Disable network logs".

Correct translation:
啟用網路活動
```

<!-- cache_translation_check_zh_TW_b39ffd6ed8b0a57369b123e846dd701dedf0036d45125cb34ee0551a90405b8f -->
```
        <source>Error: %1</source>
        <translation>错误：%1</translation>
    
ERR
The translation uses Simplified Chinese characters instead of Traditional Chinese characters as required for 'zh_TW'. Specifically, "错误" (Simplified) should be "錯誤" (Traditional).

Correct translation:
錯誤：%1
```

<!-- cache_translation_check_zh_TW_7fa49cb5a1a0ebac82592a47ee80961c6b096ed7ac1abbc6022f50b07d8c2721 -->
```
        <source>(un)select all</source>
        <translation>(un)全選</translation>
    
ERR
The translation is incomplete and unnatural. The English prefix "(un)" was left untranslated, which is not standard practice in Chinese localization. It should be fully translated to reflect the toggle action.

Correct translation:
全選或不選
```

<!-- cache_translation_check_zh_TW_5b45a2e3e197cab3a78cc3c4fa7c3b5a00240cf7134223037418ba1be2ef487d -->
```
        <source>Copy &amp;label</source>
        <translation>複製 &amp;label</translation>
    
ERR
The English word 'label' was not translated into Traditional Chinese.

Correct translation:
複製標籤(&L)
```

<!-- cache_translation_check_zh_TW_4d7048e3223a6608542d9e88f361c2e18678e6e32a584bc5ae95f8b3d9d13941 -->
```
        <source>Copy &amp;amount</source>
        <translation>複製金額 &amp;amount</translation>
    
ERR
The translation incorrectly includes the English word 'amount' after the Chinese translation. The shortcut key '&' should be placed before the corresponding character in the translated text.

Correct translation:
複製金額(&amp;A)
```

<!-- cache_translation_check_zh_TW_6006ab99d8d206cb4b883fe4118546c89833a2f28e1fde4e30e6964adcec3460 -->
```
        <source>L&amp;ock unspent</source>
        <translation>鎖定未消費金額額</translation>
    
ERR
The translation contains a redundant character "額" at the end and is missing the shortcut key indicator '&'.

Correct translation:
鎖定未花費(&O)
```

<!-- cache_translation_check_zh_TW_577d2fa8655462b96c0755878408f171c5787cc54c803443e8ed450a1d4ea35e -->
```
        <source>&amp;Unlock unspent</source>
        <translation>解鎖未花費金額</translation>
    
ERR
The translation is missing the shortcut key indicator '&' which is present in the source text.

Correct translation:
解鎖未花費金額(&U)
```

<!-- cache_translation_check_zh_TW_39f8fd7fcf43b82d6213e666e6289334dc525e42ff2102d6b2e7aca11cb82165 -->
```
        <source>Create wallet failed</source>
        <translation>創建錢包失敗&lt;br&gt;</translation>
    
ERR
The translation includes an unnecessary HTML break tag `<br>` at the end, which is not present in the source text.

Correct translation:
創建錢包失敗
```

<!-- cache_translation_check_zh_TW_91bd450109a71539c669aeb178788c78adb1ae6a861ceddfaba06ac966e74dfb -->
```
        <source>Create wallet warning</source>
        <translation>產生錢包警告:</translation>
    
ERR
The translation adds a colon at the end of the string which is not present in the source text. Additionally, "Create" is better translated as "建立" in this context.

Correct translation:
建立錢包警告
```

<!-- cache_translation_check_zh_TW_1d0a785d1fee9fdf6a0719f357c0ef28ee33c94fae22adc01856988e79a24a5c -->
```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>仅观察脚本已经被迁移到被命名为“%1”的新钱包中。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters and terminology, rather than Traditional Chinese (zh_TW) as requested. In Traditional Chinese, "仅" should be "僅", "观察" should be "觀察", and "被命名为" is less natural than "名為".

Correct translation:
僅觀察腳本已被遷移到名為「%1」的新錢包中。
```

<!-- cache_translation_check_zh_TW_4f050daa43432233793ea3633b3b1836c5e26f5dfa7bb6add44eaffb3970f760 -->
```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>可解决但未被观察到的脚本已经被迁移到被命名为“%1”的新钱包。</translation>
    
ERR
The translation uses Simplified Chinese characters and terminology (e.g., “解决”, “观察”, “迁移”, “命名”) instead of Traditional Chinese characters and terminology used in Taiwan (zh_TW). Additionally, "Solvable" in the context of Bitcoin descriptors/scripts is typically translated as "可解的".

Correct translation:
可解但非監視中的指令碼已遷移至名為「%1」的新錢包。
```

<!-- cache_translation_check_zh_TW_c4a2faeb3d7857a37a70bc9ee17648c3ec1af372bf069550999cfd66c32192fa -->
```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>輸入的地址 %1 並不是有效的比特幣地址。</translation>
    
ERR
The format specifier "%1" in the source text is missing its double quotes in the translation. In Bitcoin software interfaces, these quotes are typically preserved to highlight the specific address being referenced.

Correct translation:
輸入的地址 "%1" 並不是有效的比特幣地址。
```

<!-- cache_translation_check_zh_TW_e1369cc1c24f009c97e7112554fb638110affa5775dbca361aa99206dc0469cc -->
```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>輸入的地址 %1 已經在地址簿中了，標籤為 "%2"。</translation>
    
ERR
The translation is inconsistent with the source formatting. The double quotes around the first placeholder "%1" were removed, while they were kept for the second placeholder "%2". In software localization, it is important to maintain the delimiters used in the source text unless there is a specific linguistic reason to change them.

Correct translation:
輸入的地址 "%1" 已經在地址簿中了，標籤為 "%2"。
```

<!-- cache_translation_check_zh_TW_b47728db378378963b17d36b42f05bac982dc5bc71697c7d85cd3080d8d21567 -->
```
        <source>%1 is shutting down…</source>
        <translation>%1正在關閉..</translation>
    
ERR
The translation uses two standard periods (..) instead of an ellipsis (…) or the Chinese equivalent (…), and it lacks a space between the format specifier and the Chinese characters for better readability.

Correct translation:
%1 正在關閉…
```

<!-- cache_translation_check_zh_TW_ede40189b4cca918ec555b08ca9cb5a3d9f8b3ed3852ea2add55e099292651bd -->
```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
ERR
The translation contains a typo and is missing a part of the original sentence. "處裡" should be "處理" (to process). Additionally, the phrase "when %4 initially launched" and the second instance of the %4 format specifier are missing.

Correct translation:
當你點擊「確認」後，%1 將會開始下載並處理完整的 %4 區塊鏈 (%2 GB)，從 %3 年 %4 最初啟動時的最早交易開始。
```

<!-- cache_translation_check_zh_TW_6a9cb334c68e77c87a51c15ec678074e1c255ca7029ce73f44dea48b1d0bf660 -->
```
        <source>If you have chosen to limit block chain storage (pruning), the historical data must still be downloaded and processed, but will be deleted afterward to keep your disk usage low.</source>
        <translation>如果你選擇要限制區塊鏈儲存空間的大小(修剪模式)，還是需要下載和處理過去的歷史資料被，但是之後就會把它刪掉來節省磁碟使用量。</translation>
    
ERR
The Chinese translation contains a grammatical error: the character '被' (indicating passive voice) is placed incorrectly at the end of the clause "歷史資料被". Additionally, the phrasing can be slightly improved for better flow.

Correct translation:
如果你選擇限制區塊鏈儲存空間 (修剪模式)，還是需要下載並處理歷史資料，但之後會將其刪除以節省磁碟使用量。
```

<!-- cache_translation_check_zh_TW_f84f294b683b95b42ad955a6bf62174f068f75b9a03f91fa49c6a6d5bd1b9511 -->
```
        <source>Choose data directory</source>
        <translation>指定數據質料目錄</translation>
    
ERR
The translation uses the word "質料" (material/texture), which is incorrect in this context. The correct word for "data" in Traditional Chinese (zh_TW) is "資料". Additionally, "Choose" is more commonly translated as "選擇" in software interfaces.

Correct translation:
選擇資料目錄
```

<!-- cache_translation_check_zh_TW_131c421570f6c62bf3141903567ee92de27a319bfcf7ee4c34e05ec6a6a068eb -->
```
        <source>Error: Specified data directory "%1" cannot be created.</source>
        <translation>錯誤: 無法新增指定的資料目錄: %1</translation>
    
ERR
The translation changes the sentence structure and omits the double quotes around the placeholder %1, which were present in the source text to denote the directory path. Additionally, "建立" is a more standard translation for "created" than "新增" in this context.

Correct translation:
錯誤: 無法建立指定的資料目錄 "%1"。
```

<!-- cache_translation_check_zh_TW_0d2f970b5001d6e6c9152dd0dc3000f80ca626d9410b4a2c8bb72dd0bd0e8557 -->
```
        <source>Attempting to spend bitcoins that are affected by not-yet-displayed transactions will not be accepted by the network.</source>
        <translation>使用還沒顯示出來的交易所影響到的 bitcoin 可能會不被網路所接受。</translation>
    
ERR
The translation changes the meaning from a definite "will not be accepted" to a probabilistic "might not be accepted" (可能會). Additionally, "bitcoins" is usually translated as "比特幣" in Traditional Chinese.

Correct translation:
嘗試花費受到尚未顯示的交易影響之比特幣，將不被網路接受。
```

<!-- cache_translation_check_zh_TW_4d4b509fc3e7878f360e1612d04397beb9716f2cb456587ef04d4d9fd76b89ed -->
```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>%1 當前正在同步。它將從peers下載區塊頭和區塊，並對其進行驗證，直到到達區塊鏈的頂為止。</translation>
    
ERR
The translation contains untranslated English terms ("peers") and uses terminology that is not standard in Traditional Chinese Bitcoin contexts. Specifically, "peers" should be translated as "節點" or "同行節點", and "到達區塊鏈的頂" is a literal but awkward translation of "reaching the tip of the block chain".

Correct translation:
%1 目前正在同步。它會從節點下載區塊標頭和區塊，並進行驗證，直到達到區塊鏈的末端為止。
```

<!-- cache_translation_check_zh_TW_52b768606b5e610dade68eeef3f1d1ccbcbb57d4f7a9c4d73d4c63e737636da2 -->
```
        <source>Maximum database cache size. Make sure you have enough RAM. A larger cache can contribute to faster sync, after which the benefit is less pronounced for most use cases. Lowering the cache size will reduce memory usage. Unused mempool memory is shared for this cache.</source>
        <extracomment>Tooltip text for Options window setting that sets the size of the database cache. Explains the corresponding effects of increasing/decreasing this value.</extracomment>
        <translation>最大数据库缓存大小。确保您的系统有足够的RAM。较大的缓存可以帮助加快同步速度，但在大多数使用场景中，同步完成后其优势不再显著。减少缓存大小将降低内存使用。未使用的内存池内存将共享给此缓存。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) instead of Traditional Chinese (zh_TW). It uses Simplified characters (e.g., "数据库", "缓存", "显著", "内存") and terms common in Mainland China rather than Taiwan.

Correct translation:
最大資料庫快取大小。請確保您有足夠的 RAM。較大的快取有助於加快同步速度，在此之後，對大多數使用情境來說，其效益就不那麼明顯。降低快取大小將減少記憶體使用量。未使用的記憶體池 (mempool) 記憶體會與此快取共享。
```

<!-- cache_translation_check_zh_TW_9189cf2ad6bd98c66f206b7f3bf32e6d673c83f1334939fdb07255e3bdf6d6be -->
```
        <source>Automatically open the Bitcoin client port on the router. This only works when your router supports PCP or NAT-PMP and it is enabled. The external port could be random.</source>
        <translation>自动在路由器上打开比特币客户端端口。仅当您的路由器支持PCP或NAT-PMP并且已启用时才有效。外部端口可能是随机的。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) instead of Traditional Chinese (zh_TW) as requested.

Correct translation:
自動在路由器上開啟比特幣用戶端埠。這只有在您的路由器支援並已啟用 PCP 或 NAT-PMP 時才有效。外部埠號可能是隨機的。
```

<!-- cache_translation_check_zh_TW_0b9834d400a60bb990f28a778ea6cc4f10773247e6eff97c6877cf04602ec287 -->
```
        <source>Map port using PCP or NA&amp;T-PMP</source>
        <translation>通过PCP或NA&amp;T-PMP映射端口。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) instead of Traditional Chinese (zh_TW) as requested. Additionally, it includes an unnecessary trailing period that is not present in the source text.

Correct translation:
使用 PCP 或 NA&amp;T-PMP 對應通訊埠
```

<!-- cache_translation_check_zh_TW_123eee98ab4057466f7e1db163f3fc94a002dece86c3becc93a4cd52f07b1f9f -->
```
        <source>Font in the Overview tab: </source>
        <translation>在概览标签页的字体:</translation>
    
ERR
The translation uses Simplified Chinese characters ("概览", "标签页") instead of Traditional Chinese characters as used in Taiwan ('zh_TW'). In Taiwan, "Overview" is typically translated as "總覽" and "tab" as "分頁". Additionally, there is a missing space at the end of the translation to match the source.

Correct translation:
在總覽分頁的字體:
```

<!-- cache_translation_check_zh_TW_57ef1d26d7e9066350b441fb94a842621b52e44ffb8991516ee52967d861c49e -->
```
        <source>Prune &amp;block storage to</source>
        <translation>修剪區塊資料大小到</translation>
    
ERR
The translation is missing the shortcut key indicator '&' which was present in the source text.

Correct translation:
修剪區塊資料大小到(&B)
```

<!-- cache_translation_check_zh_TW_80e7f71ed5b519e5aff06fe423c3ffc4a34ed5228ab5e01b86d51120a255ca95 -->
```
        <source>This allows you or a third party tool to communicate with the node through command-line and JSON-RPC commands.</source>
        <extracomment>Tooltip text for Options window setting that enables the RPC server.</extracomment>
        <translation>這允許作為使用者的你或第三方工具透過命令列和JSON-RPC命令列與節點通訊。</translation>
    
ERR
The translation contains a redundant word "命令列" (command-line) at the end of the phrase "JSON-RPC命令列", which makes the sentence awkward and repetitive as "命令列" was already mentioned earlier in the same sentence. "JSON-RPC" is a protocol, not a command line itself.

Correct translation:
這允許您或第三方工具透過命令列和 JSON-RPC 指令與節點通訊。
```

<!-- cache_translation_check_zh_TW_e018e4225e4b11dbb99d3880f179525986df6b926e209d302dbb39c08cbb6412 -->
```
        <source>Whether to set subtract fee from amount as default or not.</source>
        <extracomment>Tooltip text for Options window setting that sets subtracting the fee from a sending amount as default.</extracomment>
        <translation>是否金額中減去手續費當為預設行為</translation>
    
ERR
The translation is missing the word "將" or "把" to make the sentence grammatically complete, and "當為" is slightly awkward in this context. A more natural phrasing would include "從" to indicate "subtract from".

Correct translation:
是否將「從金額中扣除手續費」設定為預設值。
```

<!-- cache_translation_check_zh_TW_3371c9f6672e03da06e2bf89a021409bf7f46d0701d9f4e717ce377f97c15935 -->
```
        <source>Show the icon in the system tray.</source>
        <translation>在通知区域显示图标。</translation>
    
ERR
The translation uses Simplified Chinese (zh_CN) terminology and characters instead of Traditional Chinese (zh_TW). Specifically, "通知区域" is more common in zh_CN, and "显示" and "图标" are used here in their simplified form characters (though they are identical in some contexts, the overall phrasing and character usage style lean towards zh_CN). In zh_TW (Taiwan), "系統匣" or "通知區域" is used, and "顯示" and "圖示" are the correct traditional characters.

Correct translation:
在系統匣顯示圖示。
```

<!-- cache_translation_check_zh_TW_722ebb7c4c0dd489ffdda2da43e0ca4cbfaa2f989881657c00dac582cfd523de -->
```
        <source>&amp;Show tray icon</source>
        <translation>显示通知区域图标(&amp;S)</translation>
    
ERR
The translation is in Simplified Chinese ('zh_CN') instead of Traditional Chinese ('zh_TW') as requested. In Traditional Chinese, "Show" is typically translated as "顯示" and "Tray icon" as "系統匣圖示" or "通知區域圖示".

Correct translation:
顯示系統匣圖示(&amp;S)
```

<!-- cache_translation_check_zh_TW_c707573f6c0576ae0ef62a64c1b9c9488cf4adc3abc3ab30fb8e39cbd38cf757 -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>使用個別的SOCKS＆5代理介由Tor onion服務到達peers：</translation>
    
ERR
The translation contains several issues:
1. The shortcut key marker '&amp;' has been replaced with a full-width '＆'. It must remain a standard half-width '&'.
2. "peers" and "Tor onion" are left untranslated or poorly phrased. In Bitcoin context, "peers" is typically translated as "節點" (nodes) or "同行".
3. "介由" is a typo/less common variant of "藉由" or "透過".
4. "到達" (reach) is more naturally translated as "連線至" (connect to) in a networking context.

Correct translation:
使用個別的 SOCKS&5 代理伺服器透過 Tor onion 服務連線至節點：
```

<!-- cache_translation_check_zh_TW_60c60a825056570eae169c829fc296dfa738ad5a5bd3513fddfc45685c1df7ad -->
```
        <source>Client restart required to activate changes.</source>
        <extracomment>Text explaining that the settings changed will not come into effect until the client is restarted.</extracomment>
        <translation>需要重新開始客戶端軟體來讓改變生效。</translation>
    
ERR
The translation uses "重新開始" (to start over/begin again), which is less appropriate for a software application than "重新啟動" (to restart/reboot). Additionally, "改變" (change) is a bit literal; "設定" (settings/adjustments) or "變更" (changes) is more natural in this context.

Correct translation:
需要重新啟動用戶端軟體以使變更生效。
```

<!-- cache_translation_check_zh_TW_8419704713d350da82e6ee885ed7cf6ea4631c1aa08747dd73a5cd93c901edc6 -->
```
        <source>This change would require a client restart.</source>
        <translation>這個變更請求重新開始客戶端軟體。</translation>
    
ERR
The translation for "require" as "請求" (request) is incorrect in this context; it should be "需要" (needs/requires). Additionally, "重新啟動" is the standard technical term for "restart" in software contexts in Traditional Chinese, rather than "重新開始".

Correct translation:
這個變更需要重新啟動用戶端。
```

<!-- cache_translation_check_zh_TW_2615f975446f92b1dcc34086adbc30d66395e733f7d8a9ec400c163b1318951f -->
```
        <source>Failed to load transaction: %1</source>
        <translation>無法載入交易：％1</translation>
    
ERR
The format specifier '%1' has been replaced with a full-width character '％1'. In many programming contexts, format specifiers must use the standard half-width '%' character to be recognized correctly by the software.

Correct translation:
無法載入交易：%1
```

<!-- cache_translation_check_zh_TW_4d8316c6943e8eb902be085bfb0974776b037a98feb038d84a3afb37bf050a30 -->
```
        <source>Failed to sign transaction: %1</source>
        <translation>無法簽名交易：％1</translation>
    
ERR
The translation uses a full-width percent sign '％' instead of the standard half-width '%' used in the format specifier. This will prevent the software from correctly replacing the placeholder with the intended variable.

Correct translation:
無法簽名交易：%1
```

<!-- cache_translation_check_zh_TW_1bb330048d59ad858b6ab445a9403ff587124bcf4f330492a641e4a78b32faa5 -->
```
        <source>Could not sign any more inputs.</source>
        <translation>無法再簽名 input</translation>
    
ERR
The translation uses the English word "input" instead of the standard Chinese (Taiwan) technical term for Bitcoin transactions. In the context of Bitcoin development and localization for zh_TW, "input" should be translated.

Correct translation:
無法再簽署任何輸入。
```

<!-- cache_translation_check_zh_TW_3f36d050ff17a707a586960e2695f55721a2fe19f9f0e9bb7cef3488d83ee57a -->
```
        <source>Transaction broadcast successfully! Transaction ID: %1</source>
        <translation>交易成功廣播！交易 ID：％1</translation>
    
ERR
The format specifier in the translation uses a full-width percent sign '％' instead of the standard half-width '%' used in the source. This will prevent the software from correctly substituting the transaction ID.

Correct translation:
交易成功廣播！交易 ID：%1
```

<!-- cache_translation_check_zh_TW_d9968a0ce01d53e7de66a6c2c0c9bc4e79b336fac482a1a72c41266f3c24d01f -->
```
        <source>Transaction broadcast failed: %1</source>
        <translation>交易廣播失敗：％1</translation>
    
ERR
The translation uses a full-width percent sign '％' instead of the standard half-width format specifier '%'. Format specifiers like '%1' must be preserved exactly as they appear in the source to ensure they are correctly processed by the software.

Correct translation:
交易廣播失敗：%1
```

<!-- cache_translation_check_zh_TW_7738e3a0543017321794c6d8cd3ea74f4805131d2cce7e918c90fc5e9ddea40e -->
```
        <source>PSBT copied to clipboard.</source>
        <translation>PSBT已復製到剪貼簿</translation>
    
ERR
The character '製' (meaning "to manufacture") is used instead of '制' (meaning "to control/copy") in the word for "copy". In Traditional Chinese (zh_TW), "copy" is correctly written as "複製". Additionally, the source sentence ends with a period, which is missing in the translation.

Correct translation:
PSBT 已複製到剪貼簿。
```

<!-- cache_translation_check_zh_TW_42e2827078990da5a13c7ad8e4551c3ab5e079ff07ca080350038d2ff1c09894 -->
```
        <source>Sends %1 to %2</source>
        <translation>将“%1”发送到“%2”</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested. Specifically, "将" (Simplified) should be "將" (Traditional).

Correct translation:
將 %1 發送到 %2
```

<!-- cache_translation_check_zh_TW_4852090d0476ca8406146954bff73520e90fa29ed91fb3c478deab30209245cc -->
```
        <source>Pays transaction fee: </source>
        <translation>支付交易手續費:</translation>
    
ERR
The translation is missing the trailing space present in the source text. In UI strings, trailing spaces are often used for padding between a label and its value. Additionally, in Traditional Chinese (zh_TW), it is standard to use a full-width colon.

Correct translation:
支付交易手續費： ⚖️ Or if sticking to half-width: 支付交易手續費:  (with trailing space)
```

<!-- cache_translation_check_zh_TW_8a63fdf6414c850dcdb072ad3b132cb72113474b8e84348bf40eb9053720a3fb -->
```
        <source>(But no wallet is loaded.)</source>
        <translation>(但没有加载钱包。)</translation>
    
ERR
The translation uses Simplified Chinese characters ('没有', '加载') instead of Traditional Chinese characters as required by the 'zh_TW' (Taiwan) locale. In Traditional Chinese, '加载' (load) is typically translated as '載入' or '載入中'.

Correct translation:
(但未載入錢包。)
```

<!-- cache_translation_check_zh_TW_fd8e796f836df963ffad6a80f465759fc26986d13b5c3c7cb4e9a695a3abc2a6 -->
```
        <source>Ping</source>
        <extracomment>Title of Peers Table column which indicates the current latency of the connection with the peer.</extracomment>
        <translation>Ping  時間</translation>
    
ERR
The translation contains a double space between "Ping" and "時間", which violates the requirement to ensure no whitespace format issues exist. Additionally, while "Ping 時間" is descriptive, "Ping" or "連線延遲" is more standard for a column header.

Correct translation:
Ping 時間
```

<!-- cache_translation_check_zh_TW_a0a6a6a4a75decd8772f23fd537aad31df0bb7e8eaafaf449db6d5f6497728a2 -->
```
        <source>Error encoding URI into QR Code.</source>
        <translation>把 URI 编码成二维码时发生错误。</translation>
    
ERR
The translation uses Simplified Chinese terminology and characters instead of Traditional Chinese (Taiwan), which is required for the 'zh_TW' language code. Specifically, '编码' (encoding) should be '編碼', and '二维码' (QR code) is a term used in Mainland China; in Taiwan, 'QR Code' or '行動條碼' is more common.

Correct translation:
將 URI 編碼成 QR Code 時發生錯誤。
```

<!-- cache_translation_check_zh_TW_f5bfdcdcb7ee7e82f1e845aed94c229b05723e922b38d8a0edc45d2010103688 -->
```
        <source>General</source>
        <translation>普通</translation>
    
ERR
In software interfaces, the "General" settings tab or category is standardly translated as "一般" in Traditional Chinese. "普通" translates more accurately to "ordinary," "average," or "plain" and is not the appropriate term for this context.

Correct translation:
一般
```

<!-- cache_translation_check_zh_TW_0bd4a40aef77c420785b3db7adca923bff2905285f7e473a5e6d8b171a4d1d84 -->
```
        <source>Network addresses that your Bitcoin node is currently using to communicate with other nodes.</source>
        <translation>您的比特币节点正在使用网络地址与其他节点联系。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested. Additionally, it is a statement rather than a noun phrase, missing the relative clause structure of the source.

Correct translation:
您的 Bitcoin 節點目前正用來與其他節點聯繫的網路位址。
```

<!-- cache_translation_check_zh_TW_0c2f3b1ca9da511a52168e61c92498723b5b95d121bdf4b2cf14fd3c7c628264 -->
```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
ERR
The translation uses Simplified Chinese characters instead of Traditional Chinese characters, which is required for the language code 'zh_TW'. Additionally, "Peers" in the context of Bitcoin is more accurately translated as "節點".

Correct translation:
隱藏節點詳細資訊
```

<!-- cache_translation_check_zh_TW_1f8069cee4f3b89629d071c520f4e51582d9a7623ba28bf86b7526b980f1832d -->
```
        <source>The total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</source>
        <extracomment>Tooltip text for the Addresses Rate-Limited field in the peer details area, which displays the total number of addresses received from this peer that were dropped (not processed) due to rate-limiting.</extracomment>
        <translation>從這個節點接收後又因頻次限製而丟棄（未被處理）的位址總數。</translation>
    
ERR
The translation uses the Simplified Chinese character '制' (in '限製') instead of the Traditional Chinese character '制' (in '限制'), though in this specific context '製' is technically a different character and '限制' is the standard term. More importantly, the translation uses '頻次' which is more common in Mainland China; '頻率' or simply '限流' is more common in Taiwan. Additionally, the character '位址' is correct for 'address' in Taiwan, but '限製' is a common typo/error for '限制'.

Correct translation:
從這個節點接收後，因流量限制而被丟棄 (未處理) 的位址總數。
```

<!-- cache_translation_check_zh_TW_935080d9ab81f21a7e9f1966afee42fd1d058fd8fdff31b381ad877437b03082 -->
```
        <source>Permissions</source>
        <translation>允許</translation>
    
ERR
The translation for "Permissions" as "允許" (Allow/Permit) is incorrect for a noun. In software contexts, "Permissions" refers to the set of rights or access levels.

Correct translation:
權限
```

<!-- cache_translation_check_zh_TW_27dead6436a543a561d3c729b71de1d46bdfefe1a6f6aec3487a75b710fff08b -->
```
        <source>The BIP324 session ID string in hex.</source>
        <translation>十六进制格式的BIP324会话ID。</translation>
    
ERR
The translation uses Simplified Chinese characters and terminology ("十六进制", "会话") instead of Traditional Chinese as used in Taiwan (zh_TW). In Traditional Chinese, "hex" is typically translated as "十六進位" and "session" as "工作階段" or "連線階段".

Correct translation:
以十六進位表示的 BIP324 工作階段 ID 字串。
```

<!-- cache_translation_check_zh_TW_70403f1a05ff1b72eafed4b6b99d7fb14569a54ec845acc165aaf3b4b42e3238 -->
```
        <source>High bandwidth BIP152 compact block relay: %1</source>
        <translation>高頻寬BIP152密集區塊轉發: %1</translation>
    
ERR
The term "compact block" in the context of Bitcoin BIP152 is standardly translated as "緊湊區塊" in Traditional Chinese. "密集區塊" (dense block) is inaccurate for this technical term.

Correct translation:
高頻寬 BIP152 緊湊區塊轉發: %1
```

<!-- cache_translation_check_zh_TW_a1ba9805a5286411483f33f0326173d0b46b69ffd46746e19023aef7c1ce69a7 -->
```
        <source>Clear console</source>
        <translation>清主控台</translation>
    
ERR
The translation is overly abbreviated and sounds informal. In Traditional Chinese software interfaces, "清除" or "清空" is the standard verb for "Clear". "清主控台" should be expanded for better clarity and professionalism.

Correct translation:
清除主控台
```

<!-- cache_translation_check_zh_TW_1ca8ed8a2e47dc5a6d18b065ef33944f8035f511e427fcc7b734bb5d9951176a -->
```
        <source>Outbound Feeler: short-lived, for testing addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to test the aliveness of known addresses.</extracomment>
        <translation>Outbound Feeler: 用於短暫，暫時 測試地址</translation>
    
ERR
The translation is grammatically awkward and redundant ("短暫" and "暫時" both mean short-lived/temporary, and their placement is disjointed). In the context of Bitcoin Core networking, "Feeler" and "Outbound" are often kept as technical terms or translated more precisely.

Correct translation:
Outbound Feeler: 存續時間短，用於測試位址的可用性
```

<!-- cache_translation_check_zh_TW_294a6b69c8397bcbe46ef5b4e5f1d3feee9e2d9c3a4b4f1ce25d159ee9c964cc -->
```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
ERR
The translation is inaccurate and includes unnecessary punctuation. The phrase "用來索取位址" (used to solicit addresses) is more accurate than "暫時 測試地址" (temporarily test addresses). In a Bitcoin context, "Address" is typically translated as "位址" in Traditional Chinese (zh_TW) rather than "地址".

Correct translation:
出向位址獲取：短暫，用於索取位址
```

<!-- cache_translation_check_zh_TW_943c7089a193923d037dd60dc1d4094137809d182c485eaeaf55e07687f2050e -->
```
        <source>1 d&amp;ay</source>
        <translation>1 天&amp;</translation>
    
ERR
The shortcut key marker '&' is placed after the character '天' rather than before it. In Chinese translations, the convention for keyboard shortcuts is to place the '&' followed by the letter/character in parentheses, or simply before the character if it's an English letter. However, in this specific case, the original text "1 d&ay" suggests the shortcut is 'a'. Following standard UI translation practices for Chinese, the shortcut should be preserved.

Correct translation:
1 天(&A)
```

<!-- cache_translation_check_zh_TW_ef486879fe3e9c5acfc8fc430627f1ae4187677f7ff0d4ebe02eaca74129ff6d -->
```
        <source>Node window - [%1]</source>
        <translation>节点窗口 - [%1]</translation>
    
ERR
The translation uses Simplified Chinese characters ("节") and terminology ("窗口") instead of Traditional Chinese characters ("節") and terminology ("視窗") as requested by the 'zh_TW' code.

Correct translation:
節點視窗 - [%1]
```

<!-- cache_translation_check_zh_TW_82290a9ceef1fac681d38c698a87367859cc1ae7e3ad7cba19643645d101c7f6 -->
```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>歡迎來到 %1 RPC 控制台。
使用上與下箭頭以進行歷史導航，%2 以清除螢幕。
使用%3 和 %4 以增加或減少字體大小。
輸入 %5 以顯示可用命令的概覽。
查看更多關於此控制台的信息，輸入 %6。

%7 警告：騙子們很狡猾，告訴用戶在這裡輸入命令，清空錢包。 不要在不完全了解一個命令的後果的情況下使用此控制台。%8</translation>
    
ERR
There are whitespace and punctuation issues in the translation. Specifically:
1. In the third line, there is a missing space before "%3".
2. In the last paragraph, a space was inserted after "%7", but the instructions/extracomment explicitly state that placeholders %7 and %8 should not be space-separated from the content.
3. The translation for "stealing their wallet contents" as "清空錢包" (emptying the wallet) is acceptable but "竊取錢包內容物" is more accurate.

Correct translation:
歡迎來到 %1 RPC 控制台。
使用上與下箭頭來瀏覽歷史紀錄，%2 以清除螢幕。
使用 %3 與 %4 來增加或減少字型大小。
輸入 %5 以取得可用指令的概覽。
若要取得更多關於使用此控制台的資訊，輸入 %6。

%7警告：詐騙者一直很活躍，要求使用者在這裡輸入指令以竊取其錢包內容。在沒有完全了解指令後果的情況下，請勿使用此控制台。%8
```

<!-- cache_translation_check_zh_TW_0b3b3af4650d33e99b1d342a24ed4dc6f10b1492d6bddc9b83ce8b4485e94a60 -->
```
        <source>Ban for</source>
        <translation>禁止連線</translation>
    
ERR
The translation "禁止連線" means "Prohibit connection" or "Ban connection", which describes the action but omits the meaning of the word "for" in this context. In the Bitcoin software UI, "Ban for" is typically a label followed by a duration (e.g., 1 day, 1 week), so the translation should reflect that it refers to the duration or period of the ban. Additionally, "封鎖" is the more standard term for "Ban" in Traditional Chinese (zh_TW) software contexts.

Correct translation:
封鎖期限
```

<!-- cache_translation_check_zh_TW_b7c46f518ad07d6443947bf54a0fa27051c29152fb5a6e894080099cb691e625 -->
```
        <source>An optional label to associate with the new receiving address (used by you to identify an invoice).  It is also attached to the payment request.</source>
        <translation>與新的接收地址相關聯的可選的標籤（您用於標識收據）。它也附在支付支付請求上。</translation>
    
ERR
The translation contains a redundant repetition of the word "支付" (payment) and uses slightly unnatural phrasing for "optional label".

Correct translation:
一個可選的標籤，用來與新的接收地址關聯（您用來識別收據）。它也會附加在支付請求上。
```

<!-- cache_translation_check_zh_TW_bf899019c3cac9970e49f67237f343336436f382f43ab4037fab2d1ab4f801dd -->
```
        <source>Copy &amp;label</source>
        <translation>复制和标签</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) instead of Traditional Chinese (zh_TW) as requested. Furthermore, the translation of "label" is literal and incorrect in this context; "和" (and) was used instead of treating the ampersand as a shortcut key indicator.

Correct translation:
複製標籤(&L)
```

<!-- cache_translation_check_zh_TW_a6e9d6abcc4431799e73f806331c34124d5e3cf2ac80d23af4c298249010502b -->
```
        <source>Copy &amp;amount</source>
        <translation>复制和数量</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) instead of Traditional Chinese (zh_TW), and it incorrectly translates the shortcut indicator '&' as the word "and" (和). In UI translations, the '&' symbol should be preserved to indicate the keyboard shortcut.

Correct translation:
複製金額(&A)
```

<!-- cache_translation_check_zh_TW_f055bdc888c085b59867e54c8f5c51f0963e6a2eca3356fe585a48549a987172 -->
```
        <source>Generates a native segwit address (BIP-173). Some old wallets don't support it.</source>
        <translation>產生一個原生隔離見證Segwit 位址 (BIP-173) 。 被部分舊版錢包不支援。</translation>
    
ERR
The translation contains unnecessary spaces and is grammatically awkward. In Traditional Chinese, "Segwit" is redundant when "隔離見證" is used, or should at least be formatted correctly. Additionally, the phrase "被部分舊版錢包不支援" is an unnatural passive construction; "部分舊型錢包並不支援" is more idiomatic.

Correct translation:
產生一個原生隔離見證 (BIP-173) 位址。部分舊型錢包不支援。
```

<!-- cache_translation_check_zh_TW_ed8c8da5fc967e39bead4f02d66e09dcf786bdebb57759a15b41984a40b4fcbf -->
```
        <source>Label</source>
        <translation>標記:</translation>
    
ERR
The translation includes a trailing colon ':' which is not present in the source text. In Bitcoin software UI contexts, "Label" is typically translated without the colon unless the source includes it.

Correct translation:
標記
```

<!-- cache_translation_check_zh_TW_d9eaf452f5098134eac180fcda99670d36ea9b71c31246c9916e3e8db8a640d7 -->
```
        <source>Requested</source>
        <translation>要求金額</translation>
    
ERR
The translation adds the word "amount" (金額), which is not present in the source text. In the context of Bitcoin software (like Bitcoin Core), "Requested" often refers to a status or a timestamp in a list of payment requests, not necessarily just the amount.

Correct translation:
已要求
```

<!-- cache_translation_check_zh_TW_8008045d2be96efd5a50ccd73d062d66454cbcc90ab69aaa6eaa40553d8b0c34 -->
```
        <source>Insufficient funds!</source>
        <translation>累計金額不足！</translation>
    
ERR
The translation "累計金額不足！" (Accumulated amount insufficient) is not the standard or most accurate translation for "Insufficient funds!" in the context of a Bitcoin wallet. The more common and natural translation is "餘額不足！" (Balance insufficient) or "資金不足！".

Correct translation:
餘額不足！
```

<!-- cache_translation_check_zh_TW_e4079e28ced2a31c5cd45858ad968288f613986dd93679a9d3f83cef844e9a62 -->
```
        <source>Sign on device</source>
        <extracomment>"device" usually means a hardware wallet.</extracomment>
        <translation>在設備上簽證</translation>
    
ERR
The translation uses "簽證", which means "visa" (travel document), instead of the correct term for cryptographic signing. In Traditional Chinese (Taiwan), "sign" in a technical context should be "簽署" or "簽名". Additionally, "裝置" is the more common term for "device" in Taiwan than "設備".

Correct translation:
在裝置上簽署
```

<!-- cache_translation_check_zh_TW_49122c9fa18f92ecade88f4641cb8c2e638774b22649cfdec91372f079cf5be8 -->
```
        <source>Set external signer script path in Options -&gt; Wallet</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>在 選項 -&gt; 錢包 中設定外部簽名器腳本路徑 </translation>
    
ERR
There is a trailing space at the end of the translation string.

Correct translation:
在 選項 -> 錢包 中設定外部簽名器腳本路徑
```

<!-- cache_translation_check_zh_TW_0b3c2d4282c1375625b4d354071e361cd11a7aa624ddb9f68e2aa130e26c0a3c -->
```
        <source>Cr&amp;eate Unsigned</source>
        <translation>Cr＆eate未簽名</translation>
    
ERR
The translation is problematic because it partially keeps the English word "Create" in a broken format and uses a full-width ampersand (＆) instead of the standard shortcut key indicator (&). In Traditional Chinese UI translations, it is standard to translate the verb and place the shortcut key in parentheses.

Correct translation:
建立未簽名(&E)
```

<!-- cache_translation_check_zh_TW_2ba198594139744adfea286781bcfa1736b3054646249ed8be686620ff5660d8 -->
```
        <source>To review recipient list click "Show Details…"</source>
        <translation>要查看收件人列表，請單擊"顯示詳細訊息..."</translation>
    
ERR
The translation uses terminology more common in Mainland China ("單擊" for click, "訊息" for details/message in this context, and "列表" is acceptable but "清單" is more common in Taiwan). In traditional Chinese for Taiwan (zh_TW), "點擊" or "按一下" is preferred over "單擊", and "詳細資料" is the standard translation for "Details". Also, the punctuation should use full-width characters in a Chinese context.

Correct translation:
要查看收件人清單，請點擊「顯示詳細資料...」
```

<!-- cache_translation_check_zh_TW_e563c47c5574373f46c25eceafcff5b99884b1da712030987cbc6a9af3e38783 -->
```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>部分签名交易(二进制)</translation>
    
ERR
The translation uses Simplified Chinese characters instead of Traditional Chinese characters as required for 'zh_TW'. Also, the parentheses and the content inside them are in a different style/spacing convention than typical Traditional Chinese localization.

Correct translation:
部分簽名交易 (二進制)
```

<!-- cache_translation_check_zh_TW_04b15e5241764dd8906de7cd8013a454ad83b6697ca7493c5157d5c504a9b8f2 -->
```
        <source>You can increase the fee later (signals Replace-By-Fee, BIP-125).</source>
        <translation>你可以之後再提高手續費(有 BIP-125 手續費追加的標記)</translation>
    
ERR
The translation is missing the trailing period at the end of the sentence. Additionally, while descriptive, "手續費追加" (fee addition) is a less standard translation for the technical term "Replace-By-Fee" compared to "以手續費取代".

Correct translation:
你可以之後再提高手續費 (標記 Replace-By-Fee，BIP-125)。
```

<!-- cache_translation_check_zh_TW_070c587fbb4ed6d06fe006cbce66dae59f8480ae60cbd56f50e09c90fb4e8ad5 -->
```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
ERR
The translation contains grammatical errors and punctuation issues in the second half. "然後使用簽名。離線%1錢包..." translates to "then use signature. Offline %1 wallet...", which breaks the sentence incorrectly and loses the meaning of "sign with [a wallet]".

Correct translation:
請檢查您的交易提案。這將產生一個部分簽名的比特幣交易 (PSBT)，您可以儲存或複製它，然後使用例如離線 %1 錢包或與 PSBT 相容的硬體錢包進行簽名。
```

<!-- cache_translation_check_zh_TW_b1ac6bc39f0962b4024cdcd1410b09d2fdbdf0128b71f2c4dcef033d056a9676 -->
```
        <source>%1 from wallet '%2'</source>
        <translation>%1 来自钱包 “%2”</translation>
    
ERR
The translation uses Simplified Chinese characters instead of Traditional Chinese characters as required by the 'zh_TW' language code.

Correct translation:
%1 來自錢包 '%2'
```

<!-- cache_translation_check_zh_TW_e513ff6da4a6c494fdfbe8cef69deed099580f7bf2638afba55c72da97de2383 -->
```
        <source>Please, review your transaction. You can create and send this transaction or create a Partially Signed Bitcoin Transaction (PSBT), which you can save or copy and then sign with, e.g., an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can send their transaction or create a PSBT. This string is displayed when both private keys and PSBT controls are enabled.</extracomment>
        <translation>請務必仔細檢查您的交易。 你可以創建並發送這筆交易；也可以創建一個“部分簽名比特幣交易(PSBT)”，它可以被保存下來或被複製出去，然後就可以對它進行簽名，比如用離線%1錢包，或 是用相容PSBT的硬體錢包。</translation>
    
ERR
The translation contains punctuation and spacing issues. Specifically, it uses a mix of full-width and half-width punctuation (the semicolon and parentheses), and contains an unnecessary space in "或 是". Furthermore, while "你可以" is understandable, "您可" or "您可以" would be more consistent with the initial "您的".

Correct translation:
請檢查您的交易。您可以建立並傳送這筆交易，或是建立一個部分簽名比特幣交易 (PSBT)；您可以儲存或複製 PSBT，然後使用例如離線 %1 錢包或相容 PSBT 的硬體錢包進行簽名。
```

<!-- cache_translation_check_zh_TW_62837073dca4122d75552208aa4f894ecc9c81a1f0218c440e793f077727c62a -->
```
        <source>Transaction creation failed!</source>
        <translation>製造交易失敗了！</translation>
    
ERR
The translation uses "製造" (zhì zào), which typically means "to manufacture" or "to fabricate" (often used for physical goods). In the context of software and Bitcoin, "建立" (jiàn lì) or "產生" (chǎn shēng) is much more natural for "creation."

Correct translation:
交易建立失敗！
```

<!-- cache_translation_check_zh_TW_0c83d0e3ac570516673187fcb2f821365ccd2825fa6a52f7f2ebd8d49f1e4e40 -->
```
        <source>A fee higher than %1 is considered an absurdly high fee.</source>
        <translation>高於 %1 的手續費會被認為是不合理。</translation>
    
ERR
The translation is incomplete and slightly awkward. It misses the emphasis on "high fee" at the end of the sentence, making it sound unfinished ("considered unreasonable" instead of "considered an absurdly high fee").

Correct translation:
高於 %1 的手續費被認為是不合理的高額手續費。
```

<!-- cache_translation_check_zh_TW_28469b6bdd232ba1dcfd58e7d6028a052f194701749fcdb0f461d138b0475935 -->
```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
ERR
The Chinese grammar is incorrect. The word '給' (to/give) at the end of the sentence is redundant and makes the sentence grammatically unnatural in this context.

Correct translation:
將支付發送到的比特幣位址
```

<!-- cache_translation_check_zh_TW_c4afd5664afb878d2cb259f540d2d2512ea08d6ae681bbfd11a5ae6412d4ad3b -->
```
        <source>Send</source>
        <translation>發</translation>
    
ERR
The translation "發" is incomplete for the context of a "Send" button or action in software. While it means "send" or "emit", the standard and more professional term used in Bitcoin software and general user interfaces for "Send" is "發送".

Correct translation:
發送
```

<!-- cache_translation_check_zh_TW_551764811c890c1f7afde6c6311cd85cecbefb3b68aca53dc43106596e412b74 -->
```
        <source>The Bitcoin address to sign the message with</source>
        <translation>用來簽名訊息的 比特幣地址</translation>
    
ERR
There is an unnecessary space between "用來簽名訊息的" and "比特幣地址". Additionally, "簽署" is more commonly used than "簽名" for signing messages in a technical context in Traditional Chinese.

Correct translation:
用來簽署訊息的比特幣地址
```

<!-- cache_translation_check_zh_TW_7122d22b42a374647712e18883ce57d0104df59b111d6a92097fde2a0828eaba -->
```
        <source>Copy the current signature to the clipboard</source>
        <translation>复制当前签名至剪贴板</translation>
    
ERR
The translation uses Simplified Chinese characters (SC) instead of Traditional Chinese characters (TC) as required for the language code 'zh_TW'. 

Correct translation:
複製目前的簽名至剪貼簿
```

<!-- cache_translation_check_zh_TW_5db40eb74599aaee862e1ef41129b5fbe6bf17b55d9f6572cd0d19a29526bc29 -->
```
        <source>The signed message to verify</source>
        <translation>簽名訊息進行驗證</translation>
    
ERR
The translation is slightly unnatural and lacks a preposition or verb structure to properly convey "to verify". It reads more like "Signed message perform verification".

Correct translation:
要驗證的已簽署訊息
```

<!-- cache_translation_check_zh_TW_e08733906b74b87d0f37164b5c83b001c904df8444c61ce85a5b30b98bef9cec -->
```
        <source>kB/s</source>
        <translation>千字節/秒</translation>
    
ERR
In the context of computing and Bitcoin, "kB/s" is typically translated in Traditional Chinese (zh_TW) using the standard unit "千位元組" or simply kept as "kB/s". The term "字節" is a Simplified Chinese (zh_CN) usage; the Traditional Chinese equivalent is "位元組".

Correct translation:
千位元組/秒
```

<!-- cache_translation_check_zh_TW_79df02c35cb72a0a6a5c02236a59eea522d8bd6bf66ccfd7751b5be26dd82b1e -->
```
        <source>0/unconfirmed, in memory pool</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that is in the memory pool.</extracomment>
        <translation>0/未確認，在內存池中</translation>
    
ERR
The term "內存池" is a technical term primarily used in Mainland China (Simplified Chinese). In Taiwan (Traditional Chinese 'zh_TW'), "memory" is typically translated as "記憶體".

Correct translation:
0/未確認，在記憶體池中
```

<!-- cache_translation_check_zh_TW_1939d9c49a90d943fd4c1fe6b5e45ffde3f69cf119118846f21052e46c382dde -->
```
        <source>0/unconfirmed, not in memory pool</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that is not in the memory pool.</extracomment>
        <translation>0/未確認，不在內存池中</translation>
    
ERR
The term "內存池" is a technical term used in Mainland China (Simplified Chinese). In Traditional Chinese (Taiwan, zh_TW), the term for "memory" is "記憶體". Therefore, "memory pool" should be translated as "記憶體池".

Correct translation:
0/未確認，不在記憶體池中
```

<!-- cache_translation_check_zh_TW_77be0d2ef14500f3374d2c2be526108990e6eab6457a3e56aa9ea27af6f71e26 -->
```
        <source>Generated</source>
        <translation>生產出來</translation>
    
ERR
The translation "生產出來" is somewhat colloquial and sounds more like "manufactured". In the context of software and Bitcoin, "Generated" is more appropriately translated as "已生成".

Correct translation:
已生成
```

<!-- cache_translation_check_zh_TW_904016abd6d3f4276d44be85f11cb9f6157287fe81bb63f00492a369ea299dd1 -->
```
        <source>Transaction virtual size</source>
        <translation>交易擬真大小</translation>
    
ERR
The term "virtual size" in the context of Bitcoin (vsize) is standardly translated as "虛擬大小" in Traditional Chinese (zh_TW). The word "擬真" (meaning "realistic" or "simulated") is incorrect in this technical context.

Correct translation:
交易虛擬大小
```

<!-- cache_translation_check_zh_TW_b50997900caf9bbfcecf9870dda45a80859793bfc118b53c3ef91cfb61b11801 -->
```
        <source>%1 (Certificate was not verified)</source>
        <translation>%1（证书未被验证）</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested. Specifically, "证书" (zh_CN) should be "憑證" (zh_TW), and "验证" (zh_CN) should be "驗證" (zh_TW).

Correct translation:
%1 (憑證未經驗證)
```

<!-- cache_translation_check_zh_TW_ed8c8da5fc967e39bead4f02d66e09dcf786bdebb57759a15b41984a40b4fcbf -->
```
        <source>Label</source>
        <translation>標記:</translation>
    
ERR
The translation includes a trailing colon ':' which is not present in the source text. In Bitcoin software UI contexts, "Label" is typically translated without the colon unless the source includes it.

Correct translation:
標記
```

<!-- cache_translation_check_zh_TW_b2f97fca712a6c1ca75a0a28daaed261161c64f5e2a059b06da7259ebc54acfd -->
```
        <source>Sent to</source>
        <translation>付款</translation>
    
ERR
The translation "付款" means "payment" or "to pay", which does not accurately reflect the source "Sent to" (meaning the recipient or destination of a transaction). In the context of Bitcoin software, "Sent to" is typically translated to indicate the destination of the funds.

Correct translation:
發送到
```

<!-- cache_translation_check_zh_TW_b2f97fca712a6c1ca75a0a28daaed261161c64f5e2a059b06da7259ebc54acfd -->
```
        <source>Sent to</source>
        <translation>付款</translation>
    
ERR
The translation "付款" means "payment" or "to pay", which does not accurately reflect the source "Sent to" (meaning the recipient or destination of a transaction). In the context of Bitcoin software, "Sent to" is typically translated to indicate the destination of the funds.

Correct translation:
發送到
```

<!-- cache_translation_check_zh_TW_3d126a78589dc7f62fd207a4bd0d3bcc8585630d77ddf615b918ee2d22169413 -->
```
        <source>Range…</source>
        <translation>范围...</translation>
    
ERR
The translation uses Simplified Chinese characters instead of the Traditional Chinese characters required for the 'zh_TW' (Taiwan) locale. The ellipsis character used is also standard period marks rather than the single character ellipsis.

Correct translation:
範圍…
```

<!-- cache_translation_check_zh_TW_5b45a2e3e197cab3a78cc3c4fa7c3b5a00240cf7134223037418ba1be2ef487d -->
```
        <source>Copy &amp;label</source>
        <translation>複製 &amp;label</translation>
    
ERR
The English word 'label' was not translated into Traditional Chinese.

Correct translation:
複製標籤(&L)
```

<!-- cache_translation_check_zh_TW_4d7048e3223a6608542d9e88f361c2e18678e6e32a584bc5ae95f8b3d9d13941 -->
```
        <source>Copy &amp;amount</source>
        <translation>複製金額 &amp;amount</translation>
    
ERR
The translation incorrectly includes the English word 'amount' after the Chinese translation. The shortcut key '&' should be placed before the corresponding character in the translated text.

Correct translation:
複製金額(&amp;A)
```

<!-- cache_translation_check_zh_TW_6b6c6afbece467e2f128637730075f08ff6aa1ca33439b5a4828df89267fe6bc -->
```
        <source>Copy &amp;raw transaction</source>
        <translation>複製交易(原始)</translation>
    
ERR
The translation is missing the shortcut key indicator '&' which was present in the source text. In 'zh_TW' localizations for Bitcoin software, the convention for shortcut keys is usually to place it before the opening parenthesis of the suffix.

Correct translation:
複製原始交易(&R)
```

<!-- cache_translation_check_zh_TW_ad178d236f7dfa4296cb4b108c9b445b440409cbd25c6a94f7a622b8b998490f -->
```
        <source>Copy full transaction &amp;details</source>
        <translation>複製完整交易明細</translation>
    
ERR
The translation is missing the shortcut key indicator '&' which was present in the source text.

Correct translation:
複製完整交易明細(&D)
```

<!-- cache_translation_check_zh_TW_ad835176286ec5001b2d46ca1cecbac97741bc5c25c342e04972405d7b6424e8 -->
```
        <source>&amp;Show transaction details</source>
        <translation>顯示交易明細</translation>
    
ERR
The shortcut key indicator '&' is missing in the translation. The instructions require that if '&' exists in the source, it must exist exactly once in the translation.

Correct translation:
顯示交易明細(&S)
```

<!-- cache_translation_check_zh_TW_a5ec2339e35ef405ab65eaf0e56ac471a04688c0d0a27174d3764505ac1525dd -->
```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>逗號分隔文件</translation>
    
ERR
The term '文件' (wénjiàn) is more commonly used in Mainland China (zh_CN). In Taiwan (zh_TW), '檔案' (dàng'àn) is the standard term for a computer "file".

Correct translation:
逗號分隔檔案
```

<!-- cache_translation_check_zh_TW_ed8c8da5fc967e39bead4f02d66e09dcf786bdebb57759a15b41984a40b4fcbf -->
```
        <source>Label</source>
        <translation>標記:</translation>
    
ERR
The translation includes a trailing colon ':' which is not present in the source text. In Bitcoin software UI contexts, "Label" is typically translated without the colon unless the source includes it.

Correct translation:
標記
```

<!-- cache_translation_check_zh_TW_30b4181a3cd5022074eb9506368bc4298f7bd816239839219642081fddd49c74 -->
```
        <source>No wallet has been loaded.
Go to File &gt; Open Wallet to load a wallet.
- OR -</source>
        <translation>尚未載入任何錢包。
轉到檔案 &gt; 開啟錢包以載入錢包.
- OR -</translation>
    
ERR
The translation contains a few issues: it uses an inconsistent full-width period/half-width period at the end of the second line, and the "OR" is left in English instead of using the traditional Chinese equivalent which is standard in localized interfaces.

Correct translation:
尚未載入任何錢包。
前往 檔案 > 開啟錢包 以載入錢包。
- 或 -
```

<!-- cache_translation_check_zh_TW_f461dcb502dd79cd08cf8598633282a35a89ba25b5a4daad8cbe342e7f57bf0d -->
```
        <source>Partially Signed Transaction (*.psbt)</source>
        <translation>簽名部分的交易（* .psbt）</translation>
    
ERR
The translation is slightly inaccurate and contains an unnecessary space in the file extension. In the context of Bitcoin, "Partially Signed Transaction" is standardly translated as "部分簽名的交易". Additionally, there should not be a space between the asterisk and the period in "(*.psbt)".

Correct translation:
部分簽名的交易 (*.psbt)
```

<!-- cache_translation_check_zh_TW_3ba16199c9006d7b84ce0bc3f0c7a21c031e3fe1481b67a88fc397bdc40c9ba1 -->
```
        <source>Disk space for %s may not accommodate the block files. Approximately %u GB of data will be stored in this directory.</source>
        <translation>%s的硬碟空間可能無法容納區塊文件。 大約要在這個目錄中儲存 %uGB的數據。</translation>
    
ERR
The translation contains minor punctuation and spacing issues. Specifically, there is an unnecessary space after the first period, and the space between the format specifier '%u' and the unit 'GB' from the source is missing.

Correct translation:
%s 的磁碟空間可能無法容納區塊檔案。大約 %u GB 的資料將儲存在此目錄中。
```

<!-- cache_translation_check_zh_TW_fdc91619f65bba2b959fc0e46d543492ef1a01eaf79962f4d04cb024f360b160 -->
```
        <source>Error starting/committing db txn for wallet transactions removal process</source>
        <translation>错误：启动/提交数据库事务时出错，导致钱包交易移除过程失败。</translation>
    
ERR
The translation uses Simplified Chinese characters instead of Traditional Chinese characters as required by the 'zh_TW' (Taiwan) language code.

Correct translation:
啟動/提交資料庫事務時出錯，導致錢包交易移除程序失敗。
```

<!-- cache_translation_check_zh_TW_14761333ca91564245e396d5a8ed31f646798edfef712e2aa397e59c210d9963 -->
```
        <source>Error: Dumpfile format record is incorrect. Got "%s", expected "format".</source>
        <translation>錯誤: 轉儲文件格式不正確。 得到是"%s"，而預期本應得到的是 "format"。</translation>
    
ERR
The translation uses terminology and grammar more common in Mainland China (zh_CN) rather than Taiwan (zh_TW). In zh_TW, "Dumpfile" is typically translated as "傾印檔案" rather than "轉儲文件". Additionally, there is an unnecessary space after the full-width period, and the phrase "得到是" is grammatically incomplete.

Correct translation:
錯誤：傾印檔案格式記錄不正確。取得的是 "%s"，而預期應為 "format"。
```

<!-- cache_translation_check_zh_TW_8e752781b507e8a51aa82bff6a96c6edd256069c9129e09494df4341598316ef -->
```
        <source>Error: Dumpfile version is not supported. This version of bitcoin-wallet only supports version 1 dumpfiles. Got dumpfile with version %s</source>
        <translation>錯誤: 轉儲文件版本不支援。 這個版本的 bitcoin-wallet 只支援版本為 1 的轉儲檔案。 得到的轉儲文件版本是%s</translation>
    
ERR
The translation uses the term "轉儲文件" (zhuǎn chǔ wén jiàn), which is more commonly used in Mainland China (Simplified Chinese). In Taiwan (Traditional Chinese 'zh_TW'), the term "傾印檔案" is more standard for "dumpfile". Additionally, there is an inconsistent use of "文件" and "檔案" within the same sentence, and a missing space before the format specifier "%s".

Correct translation:
錯誤：不支援傾印檔案版本。此版本的 bitcoin-wallet 僅支援版本 1 的傾印檔案。得到的傾印檔案版本為 %s
```

<!-- cache_translation_check_zh_TW_8e9a6473e784e1ad5d08a655b55e0c5bb2defe673a3a86edd6688a2951f2f3ef -->
```
        <source>Invalid value detected for '-wallet' or '-nowallet'. '-wallet' requires a string value, while '-nowallet' accepts only '1' to disable all wallets</source>
        <translation>检测到‘-wallet’或‘-nowallet’的无效值。‘-wallet’需要一个字符串值，而‘-nowallet’只能接受‘1’来禁用所有钱包。</translation>
    
ERR
The translation uses Simplified Chinese characters and terminology instead of Traditional Chinese as required by the 'zh_TW' language code.

Correct translation:
偵測到 '-wallet' 或 '-nowallet' 的無效值。'-wallet' 需要字串值，而 '-nowallet' 只接受 '1' 以停用所有錢包。
```

<!-- cache_translation_check_zh_TW_78a3727db7b2c58049bfbe79faf011a77473fd002f75700a072bffc43d41b2bc -->
```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
ERR
The translation uses "onion" and "TOR路由" interchangeably and has some grammatical and terminology issues. "Onion" in this context refers to the Tor onion service addresses, and "onion bind address" specifically refers to the binding addresses for these services. Also, there is a stray space at the beginning of the second sentence.

Correct translation:
提供超過一個 onion 綁定位址。自動建立的 Tor onion 服務將使用 %s。
```

<!-- cache_translation_check_zh_TW_af6d8ea2c42eb2eaca6f799fa1ac860a91de9c51d4abc78633c0346d6afe0eac -->
```
        <source>No dump file provided. To use createfromdump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>沒有提供轉儲文件。 要使用 createfromdump ，必須提供 -dumpfile=&lt;filename&gt;。</translation>
    
ERR
The translation uses "轉儲文件" for "dump file", which is a term more commonly used in Mainland China (Simplified Chinese). In Traditional Chinese (Taiwan, zh_TW), "dump file" is usually translated as "傾印檔案". Additionally, there is an extra space before the second sentence and around "createfromdump".

Correct translation:
未提供傾印檔案。若要使用 createfromdump，必須提供 -dumpfile=<filename>。
```

<!-- cache_translation_check_zh_TW_6155a5986ac8a1a1fed35026a9693a6e15b9d6a74cc2fb148881f321a2785133 -->
```
        <source>No dump file provided. To use dump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>沒有提供轉儲文件。 要使用 dump ，必須提供 -dumpfile=&lt;filename&gt;。</translation>
    
ERR
The translation uses the term '轉儲文件', which is common in Mainland China (Simplified Chinese), but '傾印檔案' is the standard terminology for "dump file" in Taiwan (Traditional Chinese). Additionally, there is an unnecessary space after the first period and around the word 'dump'.

Correct translation:
沒有提供傾印檔案。要使用傾印功能，必須提供 -dumpfile=<filename>。
```

<!-- cache_translation_check_zh_TW_b2748d507d3501efcb27a9dc3c017f4e3942a47e29cf9d49883d558fecf50b5d -->
```
        <source>Prune mode is incompatible with -reindex-chainstate. Use full -reindex instead.</source>
        <translation>修剪模式与 -reindex-chainstate 不兼容。请进行一次完整的 -reindex 。</translation>
    
ERR
The translation uses Simplified Chinese characters ("与", "为", "进") instead of the Traditional Chinese characters ("與", "為", "進") expected for the 'zh_TW' (Taiwan) locale.

Correct translation:
修剪模式與 -reindex-chainstate 不相容。請改用完整的 -reindex。
```

<!-- cache_translation_check_zh_TW_7140ea7634469e28eacd06c1fc8c673aa2b49a550ea3f45f918edc40e2d81243 -->
```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>這是您支付的最高交易手續費（除了正常手續費外），優先於避免部分花費而不是定期選取幣。</translation>
    
ERR
The translation of "regular" as "定期" (meaning periodic/scheduled) is incorrect in this context. It should be "一般" or "常規" (meaning standard/normal). Additionally, the sentence structure for "prioritize... over..." is awkward and slightly confusing in the provided translation.

Correct translation:
這是您支付的最高交易手續費（除了正常手續費外），用以優先考慮避免部分花費，而非一般選幣方式。
```

<!-- cache_translation_check_zh_TW_06fc7719f8288b3c700585e6609d703acdefc824d1a9c8c92dfd029efe4a88c6 -->
```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>不支援的類別限定日誌等級 %1$s=%2$s 。 预期参数 %1$s=&lt;category&gt;:&lt;loglevel&gt;。 有效的類別: %3$s 。有效的日誌等級: %4$s 。</translation>
    
ERR
The translation uses Simplified Chinese characters ("预期参数") instead of Traditional Chinese characters ("預期參數") which is required for 'zh_TW'. There are also unnecessary spaces before the full-width periods.

Correct translation:
不支援的類別特定日誌等級 %1$s=%2$s。預期格式為 %1$s=<category>:<loglevel>。有效的類別: %3$s。有效的日誌等級: %4$s。
```

<!-- cache_translation_check_zh_TW_1aaa2f64fba83ca48f62837460d7e21eea338533c94b097a950571d174685bc2 -->
```
        <source>Cannot obtain a lock on directory %s. %s is probably already running.</source>
        <translation>无法锁定目录 %s。%s 可能已经在运行。</translation>
    
ERR
The translation is in Simplified Chinese ('zh_CN') instead of Traditional Chinese ('zh_TW') as requested. In Traditional Chinese, "无法" is usually "無法", and "目录" is usually "目錄".

Correct translation:
無法鎖定目錄 %s。%s 可能正在執行。
```

<!-- cache_translation_check_zh_TW_75371fd2333ab3596958acbdb51fd0420a00af5cce47b7b6249e5115cab5d530 -->
```
        <source>Cannot set -peerblockfilters without -blockfilterindex.</source>
        <translation>在沒有設定-blockfilterindex 則無法使用 -peerblockfilters</translation>
    
ERR
The translation has a missing space between the English parameter and the Chinese text, and the sentence structure is slightly awkward. It translates "without" as "if not setting... then cannot use", but it misses the explicit connection between the two parameters as stated in the source.

Correct translation:
若未設定 -blockfilterindex，則無法設定 -peerblockfilters。
```

<!-- cache_translation_check_zh_TW_4fe7d564140fa26b7e7edb29027aeb23622240f0cabc5b33e40f3db4f0e7df7a -->
```
        <source>Cannot provide specific connections and have addrman find outgoing connections at the same time.</source>
        <translation>在使用地址管理器(addrman)寻找出站连接时，无法同时提供特定的连接。</translation>
    
ERR
The translation uses Simplified Chinese characters instead of Traditional Chinese characters, which is incorrect for the 'zh_TW' (Taiwan) locale. Additionally, the phrasing could be more natural for the target locale.

Correct translation:
在使用位址管理員 (addrman) 尋找外連連線時，無法同時提供特定的連線。
```

<!-- cache_translation_check_zh_TW_950f471d722746c530b4412304810c79fa7a40eaa5576bf40389d5e75ca78f4a -->
```
        <source>Error loading %s: External signer wallet being loaded without external signer support compiled</source>
        <translation>加载%s时出错: 编译时未启用外部签名器支持，却仍然试图加载外部签名器钱包</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested. Additionally, the spacing around the colon differs from standard Chinese typography.

Correct translation:
載入 %s 時出錯：在未編譯外部簽署器支援的情況下，正在載入外部簽署器錢包
```

<!-- cache_translation_check_zh_TW_8c4d3c546718fda322b2d16d35344c98b08f02e7a8fffb2c1be4d49896ad1977 -->
```
        <source>Error: Address book data in wallet cannot be identified to belong to migrated wallets</source>
        <translation>错误：钱包中的地址簿数据无法被识别为属于迁移后的钱包</translation>
    
ERR
The translation uses Simplified Chinese (zh_CN) characters instead of Traditional Chinese (zh_TW) characters as requested. Specifically, "错误" (Simplified) should be "錯誤" (Traditional), and "识别" (Simplified) should be "識別" (Traditional).

Correct translation:
錯誤：錢包中的位址簿資料無法被識別為屬於遷移後的錢包
```

<!-- cache_translation_check_zh_TW_18bade23e7020ac53d848de22998bef5b810b09241ad945718f1ae969a10591e -->
```
        <source>Error: Duplicate descriptors created during migration. Your wallet may be corrupted.</source>
        <translation>错误：迁移过程中创建了重复的输出描述符。你的钱包可能已损坏。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested. Additionally, "输出描述符" is more commonly referred to simply as "描述符" in this context.

Correct translation:
錯誤：遷移過程中建立了重複的描述符。您的錢包可能已損壞。
```

<!-- cache_translation_check_zh_TW_81d3ee86dab133bc19e307ca2ceaa079b3d561abc22124f2687788334cc794ad -->
```
        <source>Error: Transaction %s in wallet cannot be identified to belong to migrated wallets</source>
        <translation>错误：钱包中的交易%s无法被识别为属于迁移后的钱包</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested.

Correct translation:
錯誤：錢包中的交易 %s 無法被識別為屬於遷移後的錢包
```

<!-- cache_translation_check_zh_TW_0a696b724672f20400c4c96f18eb4f655927bcc2a16d6d28ffa35cccdc7d8939 -->
```
        <source>Incompatible options: -dnsseed=1 was explicitly specified, but -onlynet forbids connections to IPv4/IPv6</source>
        <translation>互不兼容的选项：-dnsseed=1 已被显式指定，但 -onlynet 禁止了IPv4/IPv6 连接</translation>
    
ERR
The translation uses Simplified Chinese characters ("选项", "显式") instead of Traditional Chinese characters ("選項", "顯式") which are used in 'zh_TW' (Taiwan).

Correct translation:
互不相容的選項：-dnsseed=1 已被明確指定，但 -onlynet 禁止 IPv4/IPv6 連線
```

<!-- cache_translation_check_zh_TW_b78f949e8f4c077f96e73a5649ef8b5a8efddac2710a731d10f9d1cb66eb2844 -->
```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>%s=&lt;amount&gt;: '%s' 中指定了非法的金额 (手续费必须至少达到最小转发费率(minrelay fee) %s 以避免交易卡着发不出去)</translation>
    
ERR
The translation is provided in Simplified Chinese (zh_CN) characters instead of Traditional Chinese (zh_TW) characters as requested. Additionally, the phrasing "卡着发不出去" is quite colloquial.

Correct translation:
%s=<amount> 的金額無效: '%s' (金額必須至少為最小轉發手續費 (minrelay fee) %s 以避免交易卡住)
```

<!-- cache_translation_check_zh_TW_90fda8f6932228d174e380ed1c7df7be7ae98d00ff1e42c56766226c0f6bb80a -->
```
        <source>Option '-checkpoints' is set but checkpoints were removed. This option has no effect.</source>
        <translation>选项“-checkpoints”已设置，但检查点已被移除。该选项不再生效。 </translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) rather than Traditional Chinese (zh_TW) as requested. Additionally, there is a trailing space at the end of the translation.

Correct translation:
選項「-checkpoints」已設定，但檢查點已被移除。此選項不再生效。
```

<!-- cache_translation_check_zh_TW_fc44b6029c7dbac45686cc79b705b8c897f4c829f9f3f5057b0a8d2f641e4b4e -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>修剪：上次钱包同步超出了已修剪的数据范围。您需要执行“-reindex”（对于已修剪节点，需要重新下载整个区块链）。 </translation>
    
ERR
The translation provided is in Simplified Chinese (zh_CN) instead of the requested Traditional Chinese (zh_TW).

Correct translation:
修剪：上次錢包同步超過了已修剪的資料範圍。您需要執行 -reindex (若是修剪節點，請重新下載整個區塊鏈)
```

<!-- cache_translation_check_zh_TW_b15a93ea58ca7043cb82eb05fbafa2f8fc0720bc3913e8b99ad82cd30fcb4ae0 -->
```
        <source>default wallet</source>
        <translation>默认钱包</translation>
    
ERR
The translation uses Simplified Chinese characters and terminology ("默认") instead of Traditional Chinese characters and terminology ("預設") as used in Taiwan (zh_TW).

Correct translation:
預設錢包
```

<!-- cache_translation_check_zh_TW_212c3af68e90ae4a89c435e0fc3e60da04c4a65ab354a77723b7b670db8e3821 -->
```
        <source>Can't spend unconfirmed version %d pre-selected input with a version 3 tx</source>
        <translation>无法使用版本3交易花费未确认版本1%d的预选输入。</translation>
    
ERR
The translation is in Simplified Chinese ('zh_CN') rather than the requested Traditional Chinese ('zh_TW'). Additionally, it incorrectly inserts a '1' before the format specifier '%d' which is not present in the source.

Correct translation:
無法使用版本 3 交易花費未確認版本 %d 的預選輸入。
```

<!-- cache_translation_check_zh_TW_f9b38ca6e6771122f4b6e345f173a375d4a3ec7c96cf90ece271263bcdc608a8 -->
```
        <source>Can't spend unconfirmed version 3 pre-selected input with a version %d tx</source>
        <translation>无法使用版本1%d交易花费未确认版本3的预选输入。</translation>
    
ERR
The translation is written in Simplified Chinese (zh_CN) characters ("无法", "版本") instead of Traditional Chinese (zh_TW) characters as requested. Additionally, there is a formatting error where the digit '1' was incorrectly inserted before the format specifier '%d'.

Correct translation:
無法使用版本 %d 交易花費未確認版本 3 的預選輸入。
```

<!-- cache_translation_check_zh_TW_94a8b7b7502ca8cc475caa0d0d503726e24fc4812a1c375d621d2b45922344a0 -->
```
        <source>Cannot write to directory '%s'; check permissions.</source>
        <translation>无法写入目录“%s”；请检查权限。</translation>
    
ERR
The translation uses Simplified Chinese characters (SC) instead of Traditional Chinese characters (TC), which is required for the 'zh_TW' (Taiwan) locale.

Correct translation:
無法寫入目錄「%s」；請檢查權限。
```

<!-- cache_translation_check_zh_TW_7fabb939c240330d61596107c938b130818e021e55701b8aa2132a1ecc76b3c8 -->
```
        <source>Could not generate scriptPubKeys (cache is empty)</source>
        <translation>无法生成脚本公钥（缓存为空）</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested.

Correct translation:
無法產生 scriptPubKeys (快取是空的)
```

<!-- cache_translation_check_zh_TW_1d81021bd0f5e08586ea41fd27117444164eb2a4027d5da2c4780a799bdfbce5 -->
```
        <source>Could not top up scriptPubKeys</source>
        <translation>无法补充脚本公钥</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested.

Correct translation:
無法補充 scriptPubKeys
```

<!-- cache_translation_check_zh_TW_f0b9bb5dcf51f041fbcba14071a232e06aeee74ed85128d9ab3e9c4d93a26fe2 -->
```
        <source>Dump file %s does not exist.</source>
        <translation>轉儲文件 %s 不存在</translation>
    
ERR
The translation uses the term '文件' (wénjiàn) for 'file', which is primarily used in Mainland China. In Taiwan (zh_TW), the term '檔案' (dàng'àn) is used. Additionally, '轉儲' (zhuǎnchǔ) is more common in Mainland China; '傾印' (qīngyìn) is the standard technical term for 'dump' in Taiwan. The translation is also missing the closing period.

Correct translation:
傾印檔案 %s 不存在。
```

<!-- cache_translation_check_zh_TW_3352505d7671689baa1f3ff34eedf3092dc10ac4dc30fae01524ce79e58e35cf -->
```
        <source>Error loading databases</source>
        <translation>错误：加载数据库失败。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) instead of Traditional Chinese (zh_TW), and it uses Simplified Chinese terminology (数据库 vs 資料庫). It also adds extra punctuation and words not present in the source.

Correct translation:
載入資料庫錯誤
```

<!-- cache_translation_check_zh_TW_a05575fc97b4296db52f0218f4446bc7139e226cab3017e2ad64fd9bcc6f0bda -->
```
        <source>Error opening coins database</source>
        <translation>错误：打开币数据库失败。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested. Additionally, it adds extra words ("Error:" and "failed") not present in the source.

Correct translation:
開啟錢幣資料庫發生錯誤
```

<!-- cache_translation_check_zh_TW_ba4b31fafa76b68ee6fefc8e8b4a7ed3d6fda25fd4bbf4dacf08fa9950112849 -->
```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
ERR
The translation is problematic because it omits the "expected %s" part of the source string and merges the two format specifiers into a single, confusing clause.

Correct translation:
錯誤：傾印檔案的檢查碼不符。計算結果為 %s，預期為 %s
```

<!-- cache_translation_check_zh_TW_8ee0dfeba4ed3cda8cac10a98de3f474eb3de760eb406eae940799fc9fe863d3 -->
```
        <source>Error: Not all address book records were migrated</source>
        <translation>错误：并非所有地址簿记录都已迁移</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than the requested Traditional Chinese (zh_TW) characters. "错误" should be "錯誤", and "记录" should be "紀錄".

Correct translation:
錯誤：並非所有地址簿紀錄都已遷移
```

<!-- cache_translation_check_zh_TW_dcfdd6315d1b3193dbb4dc6ce9abd68a96a5907b5b641337cb01c5fe62fb1489 -->
```
        <source>Error: Not all transaction records were migrated</source>
        <translation>错误：并非所有交易记录都已迁移</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) instead of Traditional Chinese (zh_TW) as requested.

Correct translation:
錯誤：並非所有交易紀錄都已遷移
```

<!-- cache_translation_check_zh_TW_55242a60b9c1938480d68ca5ded2a646abc15c529bbf163c6d3f2d51bbc31950 -->
```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>錯誤：無法把版本號%u作為unit32_t解析</translation>
    
ERR
The translation contains a typo in the technical term. "uint32_t" was incorrectly translated as "unit32_t".

Correct translation:
錯誤：無法將版本 %u 解析為 uint32_t
```

<!-- cache_translation_check_zh_TW_7519d82763161a4e9f5856bc7955a1cf0ba6c75e681dda7f212097c467801157 -->
```
        <source>Error: Unable to read wallet's best block locator record</source>
        <translation>错误：无法读取钱包最佳区块定位器记录</translation>
    
ERR
The translation uses Simplified Chinese characters, but the target language is 'zh_TW' (Traditional Chinese).

Correct translation:
錯誤：無法讀取錢包的最佳區塊定位器記錄
```

<!-- cache_translation_check_zh_TW_8b1135fb065982e6c8ee05d3643b9ebb06cd5f98d94108205cfa2556397adb94 -->
```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
ERR
The translation is provided in Simplified Chinese (zh_CN) instead of the requested Traditional Chinese (zh_TW). Additionally, the placement of the format specifier %s makes it refer to the disk rather than the wallet.

Correct translation:
錯誤：無法將資料寫入錢包 %s 的磁碟
```

<!-- cache_translation_check_zh_TW_915745b544568d9b0ec0143b2d6175d6d367b19a8f0b8d23df7fe48bd9228a56 -->
```
        <source>Error: Unable to write solvable wallet best block locator record</source>
        <translation>错误：无法写入可解决钱包最佳区块定位器记录</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested.

Correct translation:
錯誤：無法寫入可解決錢包最佳區塊定位器記錄
```

<!-- cache_translation_check_zh_TW_9f948faec4086a6cd0645e4bb56175f5aedec2afc77809a9971139b6eb940ed9 -->
```
        <source>Error: Unable to write watchonly wallet best block locator record</source>
        <translation>错误：无法写入仅观察钱包最佳区块定位器记录</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) instead of Traditional Chinese (zh_TW) as requested. In Traditional Chinese, "Error" is "錯誤" and "Record" is "紀錄" or "記錄" (though "記錄" is common, the characters used in the provided translation are simplified script).

Correct translation:
錯誤：無法寫入僅觀察錢包的最佳區塊定位器記錄
```

<!-- cache_translation_check_zh_TW_5c92d3563974500bc4a24e1a9c20c494818762b145cb46f35cb99d04c22103a1 -->
```
        <source>Error: database transaction cannot be executed for wallet %s</source>
        <translation>错误: 钱包%s的数据库事务无法被执行</translation>
    
ERR
The translation is in Simplified Chinese ('zh_CN') instead of Traditional Chinese ('zh_TW') as requested. In Traditional Chinese, "错误" should be "錯誤", "钱包" should be "錢包", and "数据库" should be "資料庫".

Correct translation:
錯誤: 無法為錢包 %s 執行資料庫事務
```

<!-- cache_translation_check_zh_TW_48efbd247f46f842be8b3a32001673fdef3721daddd55e336de8f3c35111412b -->
```
        <source>Failed to acquire rescan reserver during wallet initialization</source>
        <translation>在钱包初始化期间未能获取重扫预留器</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested.

Correct translation:
在錢包初始化期間未能獲取重掃預留器
```

<!-- cache_translation_check_zh_TW_e4666fa4991fa511c3e025c7f0fca4b1e5628abb54946150622583f10c2a5101 -->
```
        <source>Failed to close block undo file.</source>
        <translation>关闭区块撤销文件失败。</translation>
    
ERR
The translation is in Simplified Chinese ('zh_CN') rather than Traditional Chinese ('zh_TW') as requested.

Correct translation:
無法關閉區塊撤銷檔案。
```

<!-- cache_translation_check_zh_TW_961038e6cbaa1ae82ba5e46b0198703ac89711bf28a9d48eccde01cc70f549ac -->
```
        <source>Failed to close file when writing block.</source>
        <translation>写入区块时关闭文件失败。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested.

Correct translation:
寫入區塊時關閉檔案失敗。
```

<!-- cache_translation_check_zh_TW_bfba5479a7879ceb3a8fe1594b0469d71773b62d6ea3df387a6f180158c2e8e0 -->
```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
ERR
The translation has several issues:
1. The format specifier `%s` is placed at the beginning of the sentence instead of the end, which changes the meaning or context of the error message.
2. It uses Simplified Chinese characters (删除) instead of Traditional Chinese characters (刪除) which is expected for 'zh_TW'.
3. There is a trailing colon and space that is not present in the source.

Correct translation:
刪除交易失敗: %s
```

<!-- cache_translation_check_zh_TW_ed2eb33e96418eb0376387d631fbd7cc1dbd71ec80a2980082bb9f3bda0e614c -->
```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手續費費率(%s) 低於最低費率設置（%s)</translation>
    
ERR
There is an inconsistency in the punctuation used and a stray space. The source uses standard parentheses, while the translation uses a mix of half-width and full-width parentheses with an extra space before the first parenthesis. Additionally, "設置" is often translated as "設定" in the context of software settings in Traditional Chinese (Taiwan).

Correct translation:
手續費費率 (%s) 低於最低手續費費率設定 (%s)
```

<!-- cache_translation_check_zh_TW_936e72abeba60a871ed4b8f26db261b38f7f39aad240878ceb7181520fd67c70 -->
```
        <source>Insufficient dbcache for block verification</source>
        <translation>dbcache不足以用于区块验证</translation>
    
ERR
The translation uses Simplified Chinese characters ('用于', '区块', '验证') instead of Traditional Chinese characters which are standard for 'zh_TW'.

Correct translation:
dbcache 不足以進行區塊驗證
```

<!-- cache_translation_check_zh_TW_48aff5b850be06ddc3e7e590e48f32f8cc0796953033a29eca3e5b5d58f246fd -->
```
        <source>Insufficient funds</source>
        <translation>累積金額不足</translation>
    
ERR
The translation "累積金額不足" means "accumulated amount is insufficient," which is not the standard way to express "insufficient funds" in a financial or Bitcoin context. The correct term for "funds" in this context is usually "balance" (餘額) or "funds" (資金).

Correct translation:
餘額不足
```

<!-- cache_translation_check_zh_TW_92ee0fb980dfaf224c7e11d8555c7a2c017af1570663009dfe6da510406321ab -->
```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s'</source>
        <translation>%s=&lt;amount&gt;: '%s' 中指定了非法的金额</translation>
    
ERR
The translation uses Simplified Chinese characters ("金额") instead of Traditional Chinese characters ("金額") as required by the 'zh_TW' language code. Additionally, "無效" is a more standard translation for "Invalid" in a software context than "非法" (illegal).

Correct translation:
%s=<amount>: '%s' 中指定了無效的金額
```

<!-- cache_translation_check_zh_TW_ee10186268f4d00e96ba575ab85bdfb7c31fe20c255fa91faf09661cd6c5d007 -->
```
        <source>Invalid amount for -%s=&lt;amount&gt;: '%s'</source>
        <translation>無效金額給 -%s=&lt;amount&gt;:'%s'</translation>
    
ERR
The translation is grammatically clunky and contains a whitespace formatting error. The word "給" is a literal translation of "for" that is not natural in this technical context. Additionally, the space after the colon in the source text is missing in the translation.

Correct translation:
-%s=<amount> 的金額無效: '%s'
```

<!-- cache_translation_check_zh_TW_90bbb0546d18b16de289698ea64fd4a0079b8114ac27ce41b1efa2b87038186f -->
```
        <source>The %s path uses exFAT, which is known to have intermittent corruption problems on macOS. Move this directory to a different filesystem to avoid data loss.</source>
        <translation>%s路径使用exFAT，该格式在macOS上已知会出现间歇性损坏问题。请将此目录移动到其他文件系统以避免数据丢失。</translation>
    
ERR
The translation is in Simplified Chinese ('zh_CN') instead of Traditional Chinese ('zh_TW') as requested. In Traditional Chinese, "path" is "路徑", "file system" is "檔案系統", and "move" is "移動".

Correct translation:
%s 路徑使用 exFAT，這在 macOS 上已知會有間歇性的損壞問題。請將此目錄移動到不同的檔案系統以避免資料遺失。
```

<!-- cache_translation_check_zh_TW_59764626a756ddda6ff3cccbf5da4fa3eed6f1f2e78d46373f63145700145fc0 -->
```
        <source>The transactions removal process can only be executed within a db txn</source>
        <translation>交易移除过程只能在数据库事务内执行。</translation>
    
ERR
The translation uses Simplified Chinese characters ("过程", "数据库", "事务") and terminology common in Mainland China, rather than Traditional Chinese ("過程", "資料庫", "交易/事務") used in Taiwan (zh_TW).

Correct translation:
交易移除過程只能在資料庫交易 (db txn) 內執行。
```

<!-- cache_translation_check_zh_TW_9f2ada0936bf31f8f2755a0274b1be1b9172036ba98f3a74ed8e86baa1c93b3e -->
```
        <source>Transaction %s does not belong to this wallet</source>
        <translation>交易%s不属于这个钱包</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) instead of Traditional Chinese (zh_TW) as requested. In Traditional Chinese, "属于" should be "屬於".

Correct translation:
交易 %s 不屬於這個錢包
```

<!-- cache_translation_check_zh_TW_3d9320bea10d5e3e022a19cfd842e427af4d3ea041c7f0b8f6e7b309e8193b04 -->
```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
ERR
The translation of "change output" is incorrect. In the context of Bitcoin, "change" refers to the money sent back to the sender (找零), not "searching" (尋找). The word "尋找" (to search/find) is a mistranslation of "change" in this context.

Correct translation:
交易找零輸出索引超出範圍
```

<!-- cache_translation_check_zh_TW_5e28eae1247ba7028c21dfd8b692208c87424c5ef20a728bd58402600cbb3c8d -->
```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>需要交易一個找零地址，但是我們無法生成它。</translation>
    
ERR
The translation is grammatically awkward and slightly mistranslates the relationship between the transaction and the address. "需要交易一個找零地址" (Transaction needs a change address) literally translates back to "Needs to trade a change address." In a Bitcoin context, it should state that the transaction itself requires a change address.

Correct translation:
交易需要找零位址，但我們無法產生。
```

<!-- cache_translation_check_zh_TW_8e865d9628d79836fa5dd7fd0b04804d638987eb236d0e8001360df73a8f73b1 -->
```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>未知的交易已經有新規則激活 (versionbit %i)</translation>
    
ERR
The translation incorrectly adds the word "交易" (transaction), which is not present in the source text. The phrase "Unknown new rules" refers to the protocol rules themselves, not transactions.

Correct translation:
未知的新規則已啟用 (versionbit %i)
```

<!-- cache_translation_check_zh_TW_97005e0c6d3b199bdfa808814013d5d64da45a41cebbba444988eb6c0b1e498a -->
```
        <source>Unsupported global logging level %s=%s. Valid values: %s.</source>
        <translation>不支持的全局日志等级 %s=%s。有效数值: %s.</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) rather than Traditional Chinese (zh_TW). Additionally, the word "global" is translated as "全局" (more common in zh_CN) instead of "全域" (more common in zh_TW), and "logging level" is translated as "日志等级" (zh_CN) instead of "日誌層級" (zh_TW).

Correct translation:
不支援的全域日誌層級 %s=%s。有效值：%s。
```

<!-- cache_translation_check_zh_TW_76b1bd6861e77279c4c3f4a191a4d295d0696f1f0ea13e7ad0a7140d44da079c -->
```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) as requested. Additionally, there is a typo in the format specifier: "1%s" instead of "%s".

Correct translation:
錢包檔案建立失敗：%s
```

<!-- cache_translation_check_zh_TW_be3ffe6b6d0516a5ca218203dcff6527bff681149823164977cdc46d1f96713a -->
```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>%s链上acceptstalefeeestimates 不受支持。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested. Specifically, "链" should be "鏈" and "受支持" is more commonly expressed as "支援" in Taiwan. Also, there is a stray space before the command name in the translation.

Correct translation:
%s 鏈上不支援 acceptstalefeeestimates。
```

<!-- cache_translation_check_zh_TW_e3222f6658880630ea81b0a0cd483e7c2b2346ce99656d5b087dfe9f4559eb98 -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>加载 %s时出错：钱包为传统钱包。请使用迁移工具（migratewallet RPC）迁移到描述符钱包。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) rather than Traditional Chinese (zh_TW), as indicated by the characters "加载" (Simplified) instead of "載入" (Traditional), and "错误" would typically be "出錯" or "錯誤".

Correct translation:
載入 %s 時出錯：錢包為傳統錢包。請使用遷移工具 (migratewallet RPC) 遷移到描述符錢包。
```

<!-- cache_translation_check_zh_TW_fb9c57de56fb521dfdc9b8cd4124ea9b1e9e4d83d4064c6624a1a81414b0eed7 -->
```
        <source>Error: Dumpfile specifies an unsupported database format (%s). Only sqlite database dumps are supported</source>
        <translation>错误：转储文件指定了不受支持的数据库格式 %s。仅支持 sqlite 数据库转储。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) instead of the requested Traditional Chinese (zh_TW). Additionally, the format specifier parentheses from the source are missing in the translation.

Correct translation:
錯誤：傾印檔案指定了不支援的資料庫格式 (%s)。僅支援 sqlite 資料庫傾印。
```

<!-- cache_translation_check_zh_TW_2961cb13b7a86f1acc8115f9b7069881ec27d28d4cd7f3b72bc26f1e0634645b -->
```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on an enormous cluster of unconfirmed transactions.</source>
        <translation>由于未确认的 UTXO 依赖于庞大的未确认交易集群，无法计算提高手续费。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) rather than Traditional Chinese (zh_TW) as requested. For example, "由于" (zh_CN) is used instead of "由於" (zh_TW), and "手续费" (zh_CN) instead of "手續費" (zh_TW).

Correct translation:
由於未確認的 UTXO 依賴於龐大的未確認交易集群，無法計算提高手續費。
```

<!-- cache_translation_check_zh_TW_8b55b394728eedb61271a1a6a5e595bcdfd17b62667645e79819597cc138275c -->
```
        <source>Transaction requires one destination of non-zero value, a non-zero feerate, or a pre-selected input</source>
        <translation>交易需要至少满足以下之一：一个非零金额的收款地址、非零费率，或预先选择的输入。</translation>
    
ERR
The translation is provided in Simplified Chinese (zh_CN) instead of Traditional Chinese (zh_TW) as requested.

Correct translation:
交易需要至少滿足以下之一：一個非零金額的收款位址、非零費率，或預先選取的輸入。
```

<!-- cache_translation_check_zh_TW_7ac1efa37e812c3d7101f033238c56c685efb44247b49ad8368f92f5497fdb8a -->
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
The translation is provided in Simplified Chinese (zh_CN) instead of Traditional Chinese (zh_TW) as requested. It also contains unnecessary trailing spaces and uses terminology specific to mainland China (e.g., "软件" instead of "軟體").

Correct translation:
發現無法識別的描述符。正在載入錢包 %s

該錢包可能是在較新版本中建立的。
請嘗試執行最新的軟體版本。
```

<!-- cache_translation_check_zh_TW_668168e51bf31783026bc50f64db78d6428f6b7ca953deeb14f11a4beaa350f9 -->
```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>错误：无法添加仅观察交易%s到仅观察钱包</translation>
    
ERR
The translation uses Simplified Chinese characters instead of Traditional Chinese characters as required by the 'zh_TW' (Taiwan) locale. Additionally, there is a lack of proper spacing commonly used in Traditional Chinese technical contexts for better readability.

Correct translation:
錯誤：無法將僅限觀察交易 %s 新增至僅限觀察錢包
```

<!-- cache_translation_check_zh_TW_8f8b9912dd19fcf6794d3e745f92b1f10a125f86e129ec7ad5b76cd99ca07c71 -->
```
        <source>Error: Wallet does not exist</source>
        <translation>錯誤：錢包不存˙在。</translation>
    
ERR
The translation contains a stray character/typo "˙" between "存" and "在", and adds an unnecessary period at the end which is not present in the source.

Correct translation:
錯誤：錢包不存在
```

<!-- cache_translation_check_zh_TW_6dd13fad9934f3be9a39e0fbb05e22890fadeadd86a28c391482dccd41c5a042 -->
```
        <source>Error: cannot remove legacy wallet records</source>
        <translation>错误：无法删除遗留钱包的记录。</translation>
    
ERR
The translation uses Simplified Chinese characters instead of Traditional Chinese characters, which is required for the 'zh_TW' (Taiwan) locale. Additionally, the translation includes a full-width period at the end which is not present in the source text.

Correct translation:
錯誤：無法移除舊式錢包紀錄
```

<!-- cache_translation_check_zh_TW_5ba898a8fa4f257290a83a80d886d905097a84541cf1159ac1fa2c13a3e5a715 -->
```
        <source>Failed to start indexes, shutting down…</source>
        <translation>索引启动失败，正在关闭……</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested.

Correct translation:
索引啟動失敗，正在關閉……
```

<!-- cache_translation_check_zh_TW_3893aa5cc96d3a3e6fda580d5592a8e0694e08745e5bb4cb9823521e2db3de13 -->
```
        <source>Invalid -proxy address or hostname, ends with '=': '%s'</source>
        <translation>无效的 -proxy 地址或主机名，以“=”结尾：“%s”。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) instead of Traditional Chinese (zh_TW) as requested. In Traditional Chinese, "無效" is used instead of "无效", and "位址" is more commonly used for "address" in this context.

Correct translation:
無效的 -proxy 位址或主機名稱，以 '=' 結尾: '%s'
```

<!-- cache_translation_check_zh_TW_2dca275a8f045cf55835cc2aca16df4eb2420a49c7d06979a2528f2a2d7cd7c2 -->
```
        <source>Not enough file descriptors available. %d available, %d required.</source>
        <translation>没有足够的文件描述符可用。%d可用，%d需要。</translation>
    
ERR
The translation uses Simplified Chinese (zh_CN) characters and terminology instead of Traditional Chinese (zh_TW) as requested. In Taiwan, "文件描述符" is typically referred to as "檔案描述項" or "檔案描述子".

Correct translation:
沒有足夠的檔案描述項。可用 %d，需要 %d。
```

<!-- cache_translation_check_zh_TW_8a65190ca204502b79b6c300f73c685661424c04e29136c9be3e8dc44a9de4b3 -->
```
        <source>Unrecognized network in -proxy='%s': '%s'</source>
        <translation>无法识别 -proxy=“%s” 中的网络：“%s”。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) characters rather than Traditional Chinese (zh_TW) characters as requested. Additionally, it uses Chinese-style quotation marks (“”) which might not be desired depending on the specific UI guidelines, but the primary issue is the script type.

Correct translation:
無法識別 -proxy='%s' 中的網路：'%s'
```
</details>

Number of issues: 211.
