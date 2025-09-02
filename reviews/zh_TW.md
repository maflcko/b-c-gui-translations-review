# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>zh_TW</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bzh_TW%5D%20request)


<!-- cache_translation_check_zh_TW_0612e8aef0b85cca15b3d2220e063d00d5e249fa27727fd2ab0830cdcc07978c -->
```
        <source>Copy the currently selected address to the clipboard</source>
        <translation>复制当前选中的地址到剪贴板。</translation>
    
ERR
The translation is in Simplified/ mainland Chinese wording and uses Mainland terms (当前选中、地址、剪贴板) rather than Taiwan Traditional Chinese. No format specifiers are involved and there are no whitespace issues, but it should be localized for zh_TW.

Correct translation (Traditional Chinese for Taiwan):
將目前選取的位址複製到剪貼簿。
```

<!-- cache_translation_check_zh_TW_7c7f338158c3f1abf79195aa2bdd1bc72adf40da318e41363523d70d2d9112e5 -->
```
        <source>C&amp;hoose</source>
        <translation>選擇 (&amp;h)</translation>
    
ERR
The translation renders "Choose" as "選擇", but the shortcut key (&amp;h) is not appropriate in Chinese UI because "h" does not correspond to any character in the Chinese word "選擇". In zh_TW, it is customary to either assign the shortcut to the first letter of the Chinese word by using an English character that matches, or simply use (&amp;C) for "Choose". It is most common to translate it as "選擇(&amp;C)" to match the shortcut.

Correct translation:
選擇(&amp;C)
```

<!-- cache_translation_check_zh_TW_f2534126929c7c679fc576151c3679254c23ba66cf242be674778ed4239bd99c -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>輸入錢包的新密碼短語。&lt;br/&gt;請使用&lt;b&gt;個或10個以上隨機字符&lt;/b&gt;或&lt;b&gt;個8個以上單詞&lt;/b&gt;的密碼。</translation>
    
ERR
The translation is problematic. The order and structure of the message are garbled, and the numbers (ten/eight) are transposed and inserted incorrectly. The measure words “個” are placed before numbers, making it awkward. The instruction about using 'ten or more random characters' or 'eight or more words' is not clear.

Correct translation:
輸入錢包的新密碼短語。&lt;br/&gt;請使用&lt;b&gt;十個以上的隨機字符&lt;/b&gt;，或&lt;b&gt;八個以上的單字&lt;/b&gt;作為密碼。
```

<!-- cache_translation_check_zh_TW_b39ffd6ed8b0a57369b123e846dd701dedf0036d45125cb34ee0551a90405b8f -->
```
        <source>Error: %1</source>
        <translation>错误：%1</translation>
    
ERR
The translation uses simplified Chinese "错误" instead of the traditional Chinese "錯誤" used in 'zh_TW'.

Correct translation:
錯誤：%1
```

<!-- cache_translation_check_zh_TW_1d4d50356a6d37e9a65eefe4248ceecc505b510a4abaf25a6225631750fcc415 -->
```
        <source>Custom…</source>
        <translation>自定义...</translation>
    
ERR
The translation uses the simplified Chinese term "自定义" instead of the Traditional Chinese term. Also, the ellipsis should be the full-width "…" as in the source, not three periods.

Correct translation:
自訂…
```

<!-- cache_translation_check_zh_TW_e427676210b15c2c8c8f6757544cf04cd06b47f42ad86dc1d8ab3bc5a6ebc237 -->
```
        <source>Inbound</source>
        <extracomment>An inbound connection from a peer. An inbound connection is a connection initiated by a peer.</extracomment>
        <translation>進來</translation>
    
ERR
The translation "進來" is colloquial and less appropriate for UI/technical context. A more natural and accurate Traditional Chinese (zh_TW) translation for an inbound connection is "傳入" (or "入站" / "傳入連線" if you want to be explicit).

Correct translation:
傳入
```

<!-- cache_translation_check_zh_TW_7a8e276b020331cbd40ab2b4dd4087ab1f4a092776cab1e6b1566f64742f3384 -->
```
        <source>Outbound</source>
        <extracomment>An outbound connection to a peer. An outbound connection is a connection initiated by us.</extracomment>
        <translation>出去</translation>
    
ERR
"出去" is literal and colloquial ("to go out") and is not appropriate in this technical/networking context. It does not convey "outbound connection" as used for network/Bitcoin peers.

Suggested translations:
- For a short label: 出站
- For more explicit wording: 出站連線 or 外向連線

No format specifiers or whitespace issues present.
```

<!-- cache_translation_check_zh_TW_041cb38e17e738a0781533f7e303bf1eb85a9c693cc930dde0e655a77dccd313 -->
```
        <source>Block Relay</source>
        <extracomment>Peer connection type that relays network information about blocks and not transactions or addresses.</extracomment>
        <translation>区块转发</translation>
    
ERR
The translation uses Simplified Chinese characters ("区块转发") rather than Traditional Chinese expected for zh_TW, and the wording could be improved for Bitcoin terminology. A more natural Traditional Chinese translation is:

Correct translation:
區塊中繼
```

<!-- cache_translation_check_zh_TW_fbb5b09a9f86969a7421fdabda6ed901818486bf04c04a5630a2da5f0460fe4c -->
```
        <source>Manual</source>
        <extracomment>Peer connection type established manually through one of several methods.</extracomment>
        <translation>手册</translation>
    
ERR
"手册" means a handbook/manual (noun) in Chinese, which is incorrect in this context. The source "Manual" here is an adjective describing a peer connection type set up by hand.

Correct translation:
手動
```

<!-- cache_translation_check_zh_TW_a7c351c427df6d7b486104f1939aef897d1cfa92e831eea41d659421963ae8ce -->
```
        <source>&amp;Minimize</source>
        <translation>最小化</translation>
    
ERR
The translation is missing the ampersand (&), which denotes the shortcut key. It should appear exactly once.

Correct translation:
&最小化
```

<!-- cache_translation_check_zh_TW_6a48bd30fe4e7cd2269014687f421baac1199561d91f0c02a5850a77330d53b2 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>备份钱包(&amp;B)</translation>
    
ERR
The translation is in Simplified Chinese ("备份钱包") rather than Traditional Chinese as required for 'zh_TW'. In Traditional Chinese, "备份" should be "備份". Also, the shortcut key (&B) is retained correctly, but it's common in zh_TW to put the ampersand before the character or in parentheses after.

Correct translation:
備份錢包(&amp;B)
```

<!-- cache_translation_check_zh_TW_6c856fbf154faf315ca0802bc632798d0930e79b9382d4d4ad524e02e3ae18ee -->
```
        <source>&amp;Load PSBT from file…</source>
        <translation>从文件加载PSBT(&amp;L)...</translation>
    
ERR
The translation uses Simplified Chinese ("从文件加载PSBT") and the punctuation is the Simplified ellipsis (...), not Traditional Chinese ("…"). In Traditional Chinese for Taiwan, it should be "從檔案載入 PSBT(&amp;L)…"

Correct translation:
從檔案載入 PSBT(&amp;L)…
```

<!-- cache_translation_check_zh_TW_b35c98ce1dd8be15f452fdee42e555768e022373c29e11100b4cd066a00846c1 -->
```
        <source>Open &amp;URI…</source>
        <translation>打开&amp;URI...</translation>
    
ERR
The translation uses simplified Chinese ("打开") instead of traditional Chinese used in 'zh_TW' locale. Also, the ellipsis should be the proper full-width character ("…") for better traditional Chinese style.

Correct translation:
開啟 &amp;URI…
```

<!-- cache_translation_check_zh_TW_959c16ffaca69fc3d6fbf70a5b759e74557ee0b24442f52a5d2b5845646674c7 -->
```
        <source>Close Wallet…</source>
        <translation>关闭钱包...</translation>
    
ERR
The translation is in Simplified Chinese ("关闭钱包..."), not Traditional Chinese as used in 'zh_TW'. Also, the ellipsis should use the correct Chinese or Unicode style, and in Traditional Chinese, "關閉" is used instead of "关闭".

Correct translation:
關閉錢包…
```

<!-- cache_translation_check_zh_TW_af3e16b29457207e5532a4fd697c8df1f8f0ea0737e20ed17d82e75835bbef81 -->
```
        <source>Create Wallet…</source>
        <translation>创建钱包...</translation>
    
ERR
The translation uses Simplified Chinese ("创建钱包...") instead of Traditional Chinese, and the ellipsis is represented with three dots ("...") instead of the single ideographic ellipsis character or three dots as commonly used in Traditional Chinese.

Correct translation:
建立錢包…
```

<!-- cache_translation_check_zh_TW_fcfbfeb4e0bb7910c6581552c56704953953e497f3e229a94f1b8d793fd35fd9 -->
```
        <source>Processing blocks on disk…</source>
        <translation>处理磁盘上的区块...</translation>
    
ERR
The translation uses Simplified Chinese characters ("处理" and "磁盘") instead of Traditional Chinese characters appropriate for 'zh_TW'. Also, the ellipsis "..." should preferably be the full-width "…" for consistency with the source.

Correct translation:
處理磁碟上的區塊…
```

<!-- cache_translation_check_zh_TW_cbdfafde82c20bee4d6cb962d929ad72ef61410f95f7fe59c3d21a19fe8df12b -->
```
        <source>Connecting to peers…</source>
        <translation>连到同行...</translation>
    
ERR
The translation uses Simplified Chinese characters ("连" and "同行") instead of Traditional Chinese as required for 'zh_TW'. Additionally, the ellipsis character "..." is used rather than the more typographically correct "…" as in the source.

Correct translation:
連接到節點…
```

<!-- cache_translation_check_zh_TW_42a695c10a15cebe8935b1a9013c83e954e990e2627b810a54a4e13beb932376 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>從剪貼簿載入PSBT</translation>
    
ERR
The translation omits the shortcut key indicator '&' present in the source text. In traditional Chinese for 'zh_TW', '剪貼簿' is correct for 'clipboard', but the translation should preserve the '&' to indicate the shortcut key.

Correct translation:
從剪貼簿(&amp;C)載入PSBT…
```

<!-- cache_translation_check_zh_TW_ae17b6175a78bca240cb993bcbd06359e31a190184b2b55fe900a701a310a123 -->
```
        <source>Open a wallet</source>
        <translation>打開一個錢包檔</translation>
    
ERR
The translation uses "錢包檔" which translates to "wallet file", but the original English phrase is "Open a wallet", which refers to opening a wallet in general, not specifically a wallet file. The word "檔" (file) is added unnecessarily.

Correct translation:
打開錢包
```

<!-- cache_translation_check_zh_TW_76ae68398510bc24accf5342e8331d844f340c319439d86f2a3463a8c6de557c -->
```
        <source>&amp;Mask values</source>
        <translation>＆遮罩值</translation>
    
ERR
The translation uses a full-width '＆' character instead of the correct half-width '&' for the shortcut key indication. In zh_TW translations for Qt, the standard is to retain the ASCII '&'. Also, '&' should appear exactly once to indicate the shortcut.

Correct translation:
&遮罩值
```

<!-- cache_translation_check_zh_TW_288aac83bf952b4faa778bc98603999a0a404648c87babfb9f60f83f1c86ac95 -->
```
        <source>&amp;Hide</source>
        <translation>&amp;躲</translation>
    
ERR
The translation uses “躲” which is a verb meaning “to hide” (as in physically hiding oneself), but in UI context, the more appropriate term is “隱藏” (to hide a window, element, etc.). Additionally, the ampersand is present and correctly used.

Correct translation:
&隱藏
```

<!-- cache_translation_check_zh_TW_950cb28cc0f57eebf6fb6e99e761a355724df12da7463d87aeda770e4eaacc26 -->
```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
ERR  
The translation is incorrect. "Enable network activity" means to allow network operations, but the provided translation "關閉網路紀錄" means "Turn off network record/log," which has the opposite meaning.  

Correct translation:  
啟用網路活動
```

<!-- cache_translation_check_zh_TW_b39ffd6ed8b0a57369b123e846dd701dedf0036d45125cb34ee0551a90405b8f -->
```
        <source>Error: %1</source>
        <translation>错误：%1</translation>
    
ERR
The translation uses simplified Chinese "错误" instead of the traditional Chinese "錯誤" used in 'zh_TW'.

Correct translation:
錯誤：%1
```

<!-- cache_translation_check_zh_TW_d51e10172e5552a6df01db975d91a170ab02d5a679a13098943b9ac6cc9acd0d -->
```
        <source>&amp;Copy address</source>
        <translation>&amp;复制地址</translation>
    
ERR
The translation uses Simplified Chinese ("复制地址") instead of Traditional Chinese as required for 'zh_TW'. The correct Traditional Chinese translation is "複製地址".

Correct translation:
&複製地址
```

<!-- cache_translation_check_zh_TW_bf899019c3cac9970e49f67237f343336436f382f43ab4037fab2d1ab4f801dd -->
```
        <source>Copy &amp;label</source>
        <translation>复制和标签</translation>
    
ERR
The translation is incorrect for 'zh_TW'. It uses simplified characters ("复制") instead of traditional ("複製"), and "和" ("and") is not the correct way to indicate the shortcut. The ampersand (&amp;) should appear exactly once to define the shortcut key.

Correct translation:
複製標籤(&L)
```

<!-- cache_translation_check_zh_TW_a6e9d6abcc4431799e73f806331c34124d5e3cf2ac80d23af4c298249010502b -->
```
        <source>Copy &amp;amount</source>
        <translation>复制和数量</translation>
    
ERR
The translation is inaccurate. The original intends for "&amp;amount" to mean "Copy amount" with the ampersand indicating the shortcut key. In zh_TW, the word "复制" means "copy," but "和数量" means "and quantity," which is a mistranslation. Also, the shortcut marker (&) should be preserved as a single & in the appropriate place.

Correct translation:
複製數量(&A)
```

<!-- cache_translation_check_zh_TW_6006ab99d8d206cb4b883fe4118546c89833a2f28e1fde4e30e6964adcec3460 -->
```
        <source>L&amp;ock unspent</source>
        <translation>鎖定未消費金額額</translation>
    
ERR
The translation is problematic. There is a duplicated character "額" at the end, which is likely a typo. The correct translation should be:

鎖定未花費 (&amp;L)
```

<!-- cache_translation_check_zh_TW_577d2fa8655462b96c0755878408f171c5787cc54c803443e8ed450a1d4ea35e -->
```
        <source>&amp;Unlock unspent</source>
        <translation>解鎖未花費金額</translation>
    
ERR
The translation omits the '&' ampersand, which is used for a keyboard shortcut in the UI, and should appear exactly once in the translation. Also, "金額" literally means "amount", but "unspent" in the context of Bitcoin is usually translated as "未花費" (referring to outputs or coins rather than amounts). A common translation for "Unlock unspent" would retain the ampersand and typically use "未花費" as a noun ("outputs" or "coins" implied).

Correct translation:
&解鎖未花費
```

<!-- cache_translation_check_zh_TW_39f8fd7fcf43b82d6213e666e6289334dc525e42ff2102d6b2e7aca11cb82165 -->
```
        <source>Create wallet failed</source>
        <translation>創建錢包失敗&lt;br&gt;</translation>
    
ERR
The translation adds an unnecessary "<br>" HTML line break tag at the end, which is not present in the source text. This could result in formatting issues in the UI.

Correct translation:
創建錢包失敗
```

<!-- cache_translation_check_zh_TW_1d0a785d1fee9fdf6a0719f357c0ef28ee33c94fae22adc01856988e79a24a5c -->
```
        <source>Watchonly scripts have been migrated to a new wallet named '%1'.</source>
        <translation>仅观察脚本已经被迁移到被命名为“%1”的新钱包中。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN), not Traditional Chinese (zh_TW), and uses the wrong character for "watch-only" ("仅观察" is Simplified; in Traditional it should be "僅觀察" or more commonly "僅觀察用"). Quotation marks also use straight quotes instead of the full-width or Chinese style gulled quotes. 

Correct translation:
僅觀察腳本已經被遷移到名為「%1」的新錢包中。
```

<!-- cache_translation_check_zh_TW_83b2d2b3062f18b42ef6fc88813791bae47fca08b606bd8622a537ac662e2044 -->
```
        <source>Are you sure you wish to close the wallet &lt;i&gt;%1&lt;/i&gt;?</source>
        <translation>您確定要關閉錢包 &lt;i&gt;%1&lt;/i&gt; 嗎？</translation>
    
ERR
The translation is correct in meaning and the format specifier %1 is preserved, but it includes unnecessary spaces around the <i>...</i> tag and before the question mark, which is not appropriate for Chinese typography.

Correct translation (remove the extra spaces):
您確定要關閉錢包<i>%1</i>嗎？
```

<!-- cache_translation_check_zh_TW_a07c6118a8d1e499f76e7c6670dd539d040212da28ec25d3a813231e56e9b6cf -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>軟體未編譯外接簽證功能所需的軟體庫(外接簽證必須有此功能)</translation>
    
ERR  
The translation is inaccurate. "簽證" refers more to "visa" in Chinese, which is not appropriate for "signing" in the context of cryptocurrencies. The message is also somewhat convoluted compared to the English source. "外接簽署" or "外部簽署" is the more proper term for "external signing" in this context.

Correct translation:
未編譯外部簽署支援（外部簽署需要此支援）
```

<!-- cache_translation_check_zh_TW_ede40189b4cca918ec555b08ca9cb5a3d9f8b3ed3852ea2add55e099292651bd -->
```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
ERR  
There are several issues in the translation:

1. "處裡" should be corrected to "處理".
2. "%4" block chain is missing the "%4" in the translated "%4區塊鏈".
3. The original sentence is more explicit about the process starting with the earliest transactions when %4 was launched, but this is not fully conveyed.
4. There is an unnecessary colon in "(大小:%2GB)".
5. There should be proper spacing around units: "%2 GB" instead of "%2GB".
6. There is some loss in sequence (the order in which information is presented).

Correct translation:
當你點擊「確認」時，%1 會開始下載並處理完整的 %4 區塊鏈（%2 GB），從 %3 年 %4 剛啟動時的最早交易開始。
```

<!-- cache_translation_check_zh_TW_4d4b509fc3e7878f360e1612d04397beb9716f2cb456587ef04d4d9fd76b89ed -->
```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>%1 當前正在同步。它將從peers下載區塊頭和區塊，並對其進行驗證，直到到達區塊鏈的頂為止。</translation>
    
ERR
Problems:
- The English word "peers" is left untranslated; in zh_TW it should be translated (e.g., 節點/對等節點).
- "區塊頭" is more commonly written as "區塊標頭" or "區塊標頭/區塊頭" — use "區塊標頭" for clarity.
- "直到到達區塊鏈的頂為止" is awkward; better phrased as "直到追上區塊鏈的最新區塊" or "直到到達區塊鏈的最新區段".
- Minor wording/flow issues (use more natural Chinese word order).

Corrected translation (zh_TW):
%1 當前正在同步。它將從節點下載區塊標頭與區塊，並驗證它們，直到追上區塊鏈的最新區塊。
```

<!-- cache_translation_check_zh_TW_0b9834d400a60bb990f28a778ea6cc4f10773247e6eff97c6877cf04602ec287 -->
```
        <source>Map port using PCP or NA&amp;T-PMP</source>
        <translation>通过PCP或NA&amp;T-PMP映射端口。</translation>
    
ERR
The translation uses Simplified Chinese wording ("通过" instead of the Traditional Chinese "透過"). It also appends a period ("。") which is not present in the source. This does not follow proper 'zh_TW' norms.

Correct translation:
透過PCP或NA&amp;T-PMP映射埠口

or

透過PCP或NA&amp;T-PMP對映埠口
```

<!-- cache_translation_check_zh_TW_57ef1d26d7e9066350b441fb94a842621b52e44ffb8991516ee52967d861c49e -->
```
        <source>Prune &amp;block storage to</source>
        <translation>修剪區塊資料大小到</translation>
    
ERR
The translation omits the '&' character that marks the shortcut key in the original source ('&block'). The '&' should appear exactly once in the translation to preserve the shortcut functionality. Additionally, the word "storage" is not translated, which can cause confusion.

Correct translation:
修剪區塊&amp;儲存空間到
```

<!-- cache_translation_check_zh_TW_5bc352a607ec688484e3dacc1242ae192550a2ffa3cbafe32bfc5bf82e0e04c9 -->
```
        <source>&amp;Connect through SOCKS5 proxy (default proxy):</source>
        <translation>透過 SOCKS5 代理伺服器連線(預設代理伺服器 &amp;C):</translation>
    
ERR
The position of "&amp;" is not consistent with the source. The English source uses "&amp;" before "Connect" to indicate the shortcut key should be on 'C'. In the translation, "&amp;" is appended after "預設代理伺服器" with a "C", which is not correct and does not provide a valid shortcut in Chinese.

Correct translation:
透過 SOCKS5 代理伺服器(&amp;C)連線（預設代理伺服器）:
```

<!-- cache_translation_check_zh_TW_722ebb7c4c0dd489ffdda2da43e0ca4cbfaa2f989881657c00dac582cfd523de -->
```
        <source>&amp;Show tray icon</source>
        <translation>显示通知区域图标(&amp;S)</translation>
    
ERR
The translation is in Simplified Chinese ('显示通知区域图标') instead of Traditional Chinese as indicated by 'zh_TW'. Additionally, "tray icon" is more accurately "系統列圖示" or "通知區域圖示" in Traditional Chinese for Taiwan. The format specifier "&" is handled correctly.

Correct translation:
顯示系統列圖示(&amp;S)
or
顯示通知區域圖示(&amp;S)
```

<!-- cache_translation_check_zh_TW_c707573f6c0576ae0ef62a64c1b9c9488cf4adc3abc3ab30fb8e39cbd38cf757 -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>使用個別的SOCKS＆5代理介由Tor onion服務到達peers：</translation>
    
ERR
The translation uses a full-width "＆" instead of the standard ampersand "&" for the shortcut key, which might break shortcut functionality. Additionally, "peers" should be translated to "節點" or "對等節點" for clarity in the Bitcoin context, and "到達" is awkward here. Also, "SOCKS5" should not have a space or different characters. 

Correct translation:
使用個別的 SOCKS&5 代理透過 Tor onion 服務連接節點：
```

<!-- cache_translation_check_zh_TW_a07c6118a8d1e499f76e7c6670dd539d040212da28ec25d3a813231e56e9b6cf -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>軟體未編譯外接簽證功能所需的軟體庫(外接簽證必須有此功能)</translation>
    
ERR  
The translation is inaccurate. "簽證" refers more to "visa" in Chinese, which is not appropriate for "signing" in the context of cryptocurrencies. The message is also somewhat convoluted compared to the English source. "外接簽署" or "外部簽署" is the more proper term for "external signing" in this context.

Correct translation:
未編譯外部簽署支援（外部簽署需要此支援）
```

<!-- cache_translation_check_zh_TW_62164728b6a7c177c1d04a3a116d70629560c46f15c563b6acbb30bb130c7c74 -->
```
        <source>Save…</source>
        <translation>拯救...</translation>
    
ERR
The translation "拯救..." is incorrect: "拯救" means "rescue/save (someone)" rather than the UI action "Save". Also the source uses a single ellipsis character (…) not three periods. 

Correct translation:
儲存…
(or 保存… )
```

<!-- cache_translation_check_zh_TW_143c5bf15c6f6513c0f3979a13df178f72adab6725067ce4573e1feb1ce7ed5a -->
```
        <source>Cannot sign inputs while wallet is locked.</source>
        <translation>钱包已锁定，无法签名交易输入项。</translation>
    
ERR
The provided translation is in Simplified Chinese, but the target locale is zh_TW (Traditional Chinese). Also a more natural phrasing in Traditional Chinese is slightly different.

Correct translation (Traditional Chinese):
錢包已鎖定，無法為交易輸入簽名。
```

<!-- cache_translation_check_zh_TW_1bb330048d59ad858b6ab445a9403ff587124bcf4f330492a641e4a78b32faa5 -->
```
        <source>Could not sign any more inputs.</source>
        <translation>無法再簽名 input</translation>
    
ERR  
The translation is inaccurate and partially untranslated. The word "input" should be translated to Chinese, and the full sentence should maintain the clarity of the original.

Correct translation:  
無法再對任何輸入進行簽名。
```

<!-- cache_translation_check_zh_TW_8c6a6353aabc352572d5bbb1cf3882bbf358755e8790581aeb96ef7a841b3c2b -->
```
        <source>Transaction broadcast successfully! Transaction ID: %1</source>
        <translation>交易成功廣播！交易 ID：%1</translation>
    
ERR
The translation is understandable but slightly unnatural in Traditional Chinese (missing the aspect marker "已"). Also "交易 ID" is acceptable but "交易編號" is more natural. The format specifier %1 is preserved.

Suggested correction:
交易已成功廣播！交易 ID：%1
```

<!-- cache_translation_check_zh_TW_e563c47c5574373f46c25eceafcff5b99884b1da712030987cbc6a9af3e38783 -->
```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>部分签名交易(二进制)</translation>
    
ERR
The translation uses Simplified Chinese characters ("签") and ASCII parentheses instead of Traditional Chinese. For zh_TW it should use Traditional characters and full-width punctuation.

Correct translation:
部分簽名交易（二進制）
```

<!-- cache_translation_check_zh_TW_495a3eb750ce02dd828c7147c55991c02cdd2f57f609c6e40b0d3e41fc6f8d30 -->
```
        <source>Peer</source>
        <extracomment>Title of Peers Table column which contains a unique number used to identify a connection.</extracomment>
        <translation>同行</translation>
    
ERR
"同行" in Chinese (Traditional) usually means "people in the same profession" or "colleague" and is ambiguous in this context. For a Peers table column that contains a unique number identifying a connection, a clearer translation would be "節點" or "節點編號" (or "對等節點" if you want to be literal).

Correct translation suggestions:
節點
or
節點編號
```

<!-- cache_translation_check_zh_TW_37a2963be23a7645451da4cfcf75f7b0601648e58f991ce411f3fcb1d2ece7ad -->
```
        <source>Age</source>
        <extracomment>Title of Peers Table column which indicates the duration (length of time) since the peer connection started.</extracomment>
        <translation>连接时间</translation>
    
ERR
The translation uses simplified Chinese characters ("连接时间" with 时间) rather than traditional Chinese as expected for zh_TW. Also in Taiwanese usage "connection" for a peer is better as "連線" than "連接".

Correct translation:
連線時間
```

<!-- cache_translation_check_zh_TW_e5cdceea29a99d3a6b4b668f54766d5ff7906cd206769253639daf8533964833 -->
```
        <source>Inbound</source>
        <extracomment>An Inbound Connection from a Peer.</extracomment>
        <translation>進來</translation>
    
ERR
The translation "進來" is colloquial and reads like a verb/imperative ("come in") rather than the noun/adjective used in this context (an inbound connection). No format specifiers are present, but the phrasing is inappropriate for technical UI text.

Better translations (zh_TW):
- If a short label: "傳入"
- If more explicit: "傳入連線" or "入站連線"
```

<!-- cache_translation_check_zh_TW_ded61863e23742eeaf06cf85d0d014f6af12827016ab9e5d2b92068fb52ad9ae -->
```
        <source>Outbound</source>
        <extracomment>An Outbound Connection to a Peer.</extracomment>
        <translation>出去</translation>
    
ERR
"出去" is colloquial and verb-like (meaning "go out"); it doesn't suit the technical label for an outbound connection. Also it doesn't convey "connection". Better translations for the context:
- Single-label: "出站"
- More explicit: "出站連線" or "傳出連線"
```

<!-- cache_translation_check_zh_TW_0c2f3b1ca9da511a52168e61c92498723b5b95d121bdf4b2cf14fd3c7c628264 -->
```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
ERR
The translation is problematic because it uses Simplified Chinese ("隐藏" instead of Traditional "隱藏") and translates "Peers" as "其他人" (other people), which is inaccurate in the context of Bitcoin where "Peers" refers specifically to network peers/connected nodes. Also, "Peers Detail" should be "對等節點詳細資訊" or similar, not "详细信息" (Simplified; Traditional would be "詳細資訊").

Correct translation:
隱藏對等節點詳細資訊
```

<!-- cache_translation_check_zh_TW_a1ba9805a5286411483f33f0326173d0b46b69ffd46746e19023aef7c1ce69a7 -->
```
        <source>Clear console</source>
        <translation>清主控台</translation>
    
ERR
The translation "清主控台" is inaccurate and omits a key component. The term "主控台" is occasionally used, but the standard translation for "console" in computing contexts in Traditional Chinese is "控制台". More importantly, the translation is missing the verb "clear" or "清除" (to clear or remove).

Correct translation:
清除控制台
```

<!-- cache_translation_check_zh_TW_1ca8ed8a2e47dc5a6d18b065ef33944f8035f511e427fcc7b734bb5d9951176a -->
```
        <source>Outbound Feeler: short-lived, for testing addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to test the aliveness of known addresses.</extracomment>
        <translation>Outbound Feeler: 用於短暫，暫時 測試地址</translation>
    
ERR  
The translation has several issues:
1. It retains "Outbound Feeler" in English instead of localizing.
2. The word order is unnatural; "用於短暫，暫時 測試地址" is awkward.
3. The spacing is inconsistent, with an unnecessary space between "暫時" and "測試地址".
4. "for testing addresses" is not clearly rendered.

Correct translation:  
外部探測連線：短暫建立，用於測試地址是否可用
```

<!-- cache_translation_check_zh_TW_294a6b69c8397bcbe46ef5b4e5f1d3feee9e2d9c3a4b4f1ce25d159ee9c964cc -->
```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
ERR
The translation is inaccurate. The phrase "Outbound 地址取得: 用於短暫，暫時 測試地址" introduces "測試地址" (test address) which is not present in the original. It also awkwardly redundantly states "短暫，暫時". The original means the connection is short-lived and is for soliciting (requesting) addresses.

Correct translation:
Outbound 地址擷取：短暫用於請求地址
```

<!-- cache_translation_check_zh_TW_943c7089a193923d037dd60dc1d4094137809d182c485eaeaf55e07687f2050e -->
```
        <source>1 d&amp;ay</source>
        <translation>1 天&amp;</translation>
    
ERR
The ampersand (&) is misplaced in the translation. In the English source, it is used for the shortcut key on the letter "a" in "day". In the Traditional Chinese translation, the shortcut key should ideally be associated with a Chinese character or omitted if not applicable, but if included, it typically appears before or within the word the shortcut is associated with. Placing "&" at the end is not appropriate.

Correct translation:
1 天(&A)
```

<!-- cache_translation_check_zh_TW_ef486879fe3e9c5acfc8fc430627f1ae4187677f7ff0d4ebe02eaca74129ff6d -->
```
        <source>Node window - [%1]</source>
        <translation>节点窗口 - [%1]</translation>
    
ERR
The translation uses the simplified Chinese character "节点" instead of the traditional Chinese "節點" for 'zh_TW'. 

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
There are minor issues with spacing and style:

1. In "使用%3 和 %4 以增加或減少字體大小。", there's a missing space before "%3" (should be "使用 %3 和 %4 以增加或減少字體大小。").
2. The original intentionally keeps %7 and %8 not space-separated from the warning, but in the translation, a space is added after %7 and before "警告：" (should not have a space: "%7警告：...%8").
3. The English says "stealing their wallet contents", but the translation says "清空錢包" which means "emptying the wallet". While related, "steal the wallet contents" is closer to "竊取他們錢包中的資產".
4. There's a space before the last sentence: "不要在不完全了解一個命令的後果的情況下使用此控制台。", which in the translation is written as: " 不要在不完全了解一個命令的後果的情況下使用此控制台。" (the space before is unnecessary due to wrong wrapping).

Correct translation:
歡迎來到 %1 RPC 控制台。
使用上與下箭頭以進行歷史導航，%2 以清除螢幕。
使用 %3 和 %4 以增加或減少字體大小。
輸入 %5 以顯示可用命令的概覽。
查看更多關於此控制台的資訊，輸入 %6。

%7警告：騙子已經行動，誘導用戶在此輸入命令，竊取他們錢包中的資產。不要在未完全了解命令後果的情況下使用此控制台。%8
```

<!-- cache_translation_check_zh_TW_a6e9d6abcc4431799e73f806331c34124d5e3cf2ac80d23af4c298249010502b -->
```
        <source>Copy &amp;amount</source>
        <translation>复制和数量</translation>
    
ERR
The translation is inaccurate. The original intends for "&amp;amount" to mean "Copy amount" with the ampersand indicating the shortcut key. In zh_TW, the word "复制" means "copy," but "和数量" means "and quantity," which is a mistranslation. Also, the shortcut marker (&) should be preserved as a single & in the appropriate place.

Correct translation:
複製數量(&A)
```

<!-- cache_translation_check_zh_TW_f055bdc888c085b59867e54c8f5c51f0963e6a2eca3356fe585a48549a987172 -->
```
        <source>Generates a native segwit address (BIP-173). Some old wallets don't support it.</source>
        <translation>產生一個原生隔離見證Segwit 位址 (BIP-173) 。 被部分舊版錢包不支援。</translation>
    
ERR
The translation introduces spacing and punctuation issues, and could be rephrased for clarity and smoothness. Specifically:
- "Segwit" should not have a space before "位址".
- The sentence "被部分舊版錢包不支援。" lacks a subject and is not smooth in Chinese.
- The period placement is incorrect (there is a space before it).
- For 'zh_TW', "地址" is also more common than "位址", though both are used.

Correct translation:
產生一個原生隔離見證地址（BIP-173）。部分舊版錢包不支援此地址。
```

<!-- cache_translation_check_zh_TW_0b3c2d4282c1375625b4d354071e361cd11a7aa624ddb9f68e2aa130e26c0a3c -->
```
        <source>Cr&amp;eate Unsigned</source>
        <translation>Cr＆eate未簽名</translation>
    
ERR
The translation is problematic for several reasons:
1. The English word "Cr&eate" is not properly translated into Chinese. Only "未簽名" (unsigned) is localized, but "Create" remains in English.
2. The ampersand (&) for the shortcut key is incorrectly replaced by the full-width "＆", which should not be used. The standard half-width ampersand (&) must be used.
3. There is a missing space or separator. In Chinese, options are usually translated fully, not half English/half Chinese.

Correct translation:
建立未簽名(&C)
```

<!-- cache_translation_check_zh_TW_070c587fbb4ed6d06fe006cbce66dae59f8480ae60cbd56f50e09c90fb4e8ad5 -->
```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
ERR
The translation is problematic. The phrase "然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。" is not smooth and splits the clause inappropriately, making the instructions unclear. The period after "簽名" incorrectly breaks the sentence. The expression "使用簽名" is also inaccurate; it should specify "用...簽名".

Correct translation:
請檢查您的交易提案。這將產生一筆部分簽名的比特幣交易（PSBT），您可以將其儲存或複製，然後使用例如離線的 %1 錢包或支援 PSBT 的硬體錢包來簽名。
```

<!-- cache_translation_check_zh_TW_28469b6bdd232ba1dcfd58e7d6028a052f194701749fcdb0f461d138b0475935 -->
```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
ERR
The translation is awkward and contains an unnecessary "給" at the end, which makes the sentence ungrammatical in Chinese. The "給" suggests "to" but its placement is wrong.

Correct translation:
要將付款發送到的比特幣地址
```

<!-- cache_translation_check_zh_TW_c4afd5664afb878d2cb259f540d2d2512ea08d6ae681bbfd11a5ae6412d4ad3b -->
```
        <source>Send</source>
        <translation>發</translation>
    
ERR
The translation "發" is incomplete and incorrect. The English word "Send" in the context of Bitcoin typically means "to send funds" or "to make a payment", and should be translated as "發送" or "發送資金" in Traditional Chinese (zh_TW). The single character "發" is insufficient and may be confusing.

Correct translation:
發送
```

<!-- cache_translation_check_zh_TW_7122d22b42a374647712e18883ce57d0104df59b111d6a92097fde2a0828eaba -->
```
        <source>Copy the current signature to the clipboard</source>
        <translation>复制当前签名至剪贴板</translation>
    
ERR
The translation uses Simplified Chinese characters (e.g., 复制, 当前, 签名, 剪贴板) but the target locale is zh_TW (Traditional Chinese). No format specifiers are involved.

Correct translation (Traditional Chinese):
將目前的簽名複製到剪貼簿
```

<!-- cache_translation_check_zh_TW_3d126a78589dc7f62fd207a4bd0d3bcc8585630d77ddf615b918ee2d22169413 -->
```
        <source>Range…</source>
        <translation>范围...</translation>
    
ERR
The translation uses simplified Chinese characters '范围' instead of traditional Chinese characters used in 'zh_TW'. The ellipsis is also three dots instead of the proper ellipsis character (…).

Correct translation:
範圍…
```

<!-- cache_translation_check_zh_TW_a6e9d6abcc4431799e73f806331c34124d5e3cf2ac80d23af4c298249010502b -->
```
        <source>Copy &amp;amount</source>
        <translation>复制和数量</translation>
    
ERR
The translation is inaccurate. The original intends for "&amp;amount" to mean "Copy amount" with the ampersand indicating the shortcut key. In zh_TW, the word "复制" means "copy," but "和数量" means "and quantity," which is a mistranslation. Also, the shortcut marker (&) should be preserved as a single & in the appropriate place.

Correct translation:
複製數量(&A)
```

<!-- cache_translation_check_zh_TW_6b6c6afbece467e2f128637730075f08ff6aa1ca33439b5a4828df89267fe6bc -->
```
        <source>Copy &amp;raw transaction</source>
        <translation>複製交易(原始)</translation>
    
ERR
The '&amp;' (shortcut key indicator) from the source is missing in the translation. According to UI conventions, the '&' should be present exactly once in the translation, ideally before the shortcut character.

Correct translation:
複製(&R)原始交易
```

<!-- cache_translation_check_zh_TW_ad178d236f7dfa4296cb4b108c9b445b440409cbd25c6a94f7a622b8b998490f -->
```
        <source>Copy full transaction &amp;details</source>
        <translation>複製完整交易明細</translation>
    
ERR
The ampersand (&) indicating the shortcut key in the source ("&details") is missing in the translation. The translation should include a single ampersand (&) somewhere in the phrase.

Correct translation:
複製完整交易明細(&D)
```

<!-- cache_translation_check_zh_TW_ad835176286ec5001b2d46ca1cecbac97741bc5c25c342e04972405d7b6424e8 -->
```
        <source>&amp;Show transaction details</source>
        <translation>顯示交易明細</translation>
    
ERR
The translation omits the '&' which is used to indicate the shortcut key in the English source string. The translation should include exactly one '&' character to preserve shortcut functionality.

Correct translation:
&顯示交易明細
```

<!-- cache_translation_check_zh_TW_e21c2f6290c8559f0fc42bb3c784a6a516fa3fe5c8b77d55fb3a33fc91446925 -->
```
        <source>Increase transaction &amp;fee</source>
        <translation>增加礦工費(&amp;fee)</translation>
    
ERR
The shortcut key (&amp;) is supposed to mark a shortcut letter in the translation, as in the source, but in the translation it is not attached to a suitable letter. Also, "fee" is untranslated, which is not standard in 'zh_TW'. The correct translation should use a Chinese translation and put (&amp;f) after an appropriate character.

Correct translation:
增加交易手續費(&amp;f)
```

<!-- cache_translation_check_zh_TW_3ba16199c9006d7b84ce0bc3f0c7a21c031e3fe1481b67a88fc397bdc40c9ba1 -->
```
        <source>Disk space for %s may not accommodate the block files. Approximately %u GB of data will be stored in this directory.</source>
        <translation>%s的硬碟空間可能無法容納區塊文件。 大約要在這個目錄中儲存 %uGB的數據。</translation>
    
ERR
There is a spacing issue: there should be a space between "%u" and "GB" in the Chinese text (" %uGB" should be " %u GB"), and there should not be a space at the start of the second sentence. Also, "數據" is more common in Mainland China; "資料" is the more standard term for 'data' in Taiwanese usage.

Correct translation:
%s 的硬碟空間可能無法容納區塊檔案。大約有 %u GB 的資料會儲存在此目錄中。
```

<!-- cache_translation_check_zh_TW_78a3727db7b2c58049bfbe79faf011a77473fd002f75700a072bffc43d41b2bc -->
```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
ERR
The translation is inaccurate, contains errors, and shows some spacing issues. The phrase "多數TOR路由綁定位址" is not a natural or correct way to say "more than one onion bind address" in Traditional Chinese. Also, the use of "多數" suggests "the majority" instead of "more than one". "TOR路由綁定" is awkward, and "Tor onion service" should be translated more precisely. There is also an irregular space before "對".

Correct translation:
提供了多個 Onioin 綁定位址。將使用 %s 作為自動建立的 Tor onion 服務。
```

<!-- cache_translation_check_zh_TW_b2748d507d3501efcb27a9dc3c017f4e3942a47e29cf9d49883d558fecf50b5d -->
```
        <source>Prune mode is incompatible with -reindex-chainstate. Use full -reindex instead.</source>
        <translation>修剪模式与 -reindex-chainstate 不兼容。请进行一次完整的 -reindex 。</translation>
    
ERR
The translation is accurate in meaning but has minor whitespace and style issues (extra space before the final punctuation; use Traditional Chinese phrasing). 

Correct translation:
修剪模式與 -reindex-chainstate 不相容。請改用完整的 -reindex。
```

<!-- cache_translation_check_zh_TW_7140ea7634469e28eacd06c1fc8c673aa2b49a550ea3f45f918edc40e2d81243 -->
```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>這是您支付的最高交易手續費（除了正常手續費外），優先於避免部分花費而不是定期選取幣。</translation>
    
ERR
The translation is inaccurate and unclear, especially regarding "prioritize partial spend avoidance over regular coin selection." The translated phrase "優先於避免部分花費而不是定期選取幣" is grammatically incorrect and does not convey the intended meaning.

Correct translation:
這是您為了優先避免部分花費（而不是常規的找零選擇）所支付的最高額外交易手續費（除了正常手續費之外）。
```

<!-- cache_translation_check_zh_TW_06fc7719f8288b3c700585e6609d703acdefc824d1a9c8c92dfd029efe4a88c6 -->
```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>不支援的類別限定日誌等級 %1$s=%2$s 。 预期参数 %1$s=&lt;category&gt;:&lt;loglevel&gt;。 有效的類別: %3$s 。有效的日誌等級: %4$s 。</translation>
    
ERR
The translation mixes Simplified and Traditional Chinese: "预期参数" is Simplified; in Traditional Chinese, it should be "預期參數". Also, there are inconsistent spaces before periods and after punctuation, which is not standard in Chinese typographic conventions.
The % format specifiers are correctly carried over, but punctuation and character set need correction.

Correct translation:
不支援的類別限定日誌等級 %1$s=%2$s。預期參數 %1$s=&lt;category&gt;:&lt;loglevel&gt;。有效的類別：%3$s。有效的日誌等級：%4$s。
```

<!-- cache_translation_check_zh_TW_0a696b724672f20400c4c96f18eb4f655927bcc2a16d6d28ffa35cccdc7d8939 -->
```
        <source>Incompatible options: -dnsseed=1 was explicitly specified, but -onlynet forbids connections to IPv4/IPv6</source>
        <translation>互不兼容的选项：-dnsseed=1 已被显式指定，但 -onlynet 禁止了IPv4/IPv6 连接</translation>
    
ERR
The translation uses Simplified Chinese wording ("兼容", "显式指定", "连接") and has a minor spacing issue before "连接". The target locale zh_TW requires Traditional Chinese.

Correct translation (Traditional Chinese, no extra spaces, preserving option names):
不相容的選項：-dnsseed=1 已明確指定，但 -onlynet 禁止連線到 IPv4/IPv6
```

<!-- cache_translation_check_zh_TW_90fda8f6932228d174e380ed1c7df7be7ae98d00ff1e42c56766226c0f6bb80a -->
```
        <source>Option '-checkpoints' is set but checkpoints were removed. This option has no effect.</source>
        <translation>选项“-checkpoints”已设置，但检查点已被移除。该选项不再生效。 </translation>
    
ERR
The translation is in Simplified Chinese (e.g., "选项", "检查点", "该选项") and contains a trailing space before the closing tag. For zh_TW it should use Traditional Chinese characters and no extra whitespace.

Correct translation:
選項「-checkpoints」已設定，但檢查點已被移除。該選項不再生效。
```

<!-- cache_translation_check_zh_TW_d98c1c5ff4f9281f53e84a4630bcb6846485c6649d59a458ddb76aab8f1f87d3 -->
```
        <source>Option '-maxorphantx' is set but no longer has any effect (see release notes). Please remove it from your configuration.</source>
        <translation>选项“-maxorphantx”已设置，但已不再生效（参见发行说明）。请从您的配置中移除该选项。 </translation>
    
ERR
The provided translation is in Simplified Chinese (zh_CN) rather than Traditional Chinese (zh_TW). There's also an extra trailing space before the closing tag. 

Correct Traditional Chinese (zh_TW) translation:
選項「-maxorphantx」已設定，但已不再生效（請參閱發行說明）。請從您的設定中移除該選項。
```

<!-- cache_translation_check_zh_TW_bf17affb0acd6713b9f6b2167f99961dbd921c30426c9f4b5f40c6272c0fa297 -->
```
        <source>Options '-datacarrier' or '-datacarriersize' are set but are marked as deprecated. They will be removed in a future version.</source>
        <translation>选项“-datacarrier”或“-datacarriersize”已设置，但已标记为弃用。它们将在未来版本中移除。 </translation>
    
ERR
The translation is in Simplified Chinese (uses 选项, 设置 etc.) but the target locale is zh_TW (Traditional Chinese). There's also a trailing space before the closing tag.

Correct Traditional Chinese translation:
選項「-datacarrier」或「-datacarriersize」已設定，但已被標記為棄用。它們將在未來版本中移除。
```

<!-- cache_translation_check_zh_TW_fc44b6029c7dbac45686cc79b705b8c897f4c829f9f3f5057b0a8d2f641e4b4e -->
```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of a pruned node)</source>
        <translation>修剪：上次钱包同步超出了已修剪的数据范围。您需要执行“-reindex”（对于已修剪节点，需要重新下载整个区块链）。 </translation>
    
ERR
The translation is accurate in meaning but uses Simplified Chinese wording (e.g., 钱包, 下载, 执行) and thus is not appropriate for zh_TW (Traditional Chinese). Also there's an extra trailing space before the end of the string.

Correct Traditional Chinese translation:
修剪：上次錢包同步超出了已修剪的資料範圍。您需要執行“-reindex”（對於已修剪的節點，需重新下載整個區塊鏈）。
```

<!-- cache_translation_check_zh_TW_eb968025b9240f22a7d27bd23c989a8fc00fef0ee8185f551adcffb7a2452904 -->
```
        <source>-paytxfee is deprecated and will be fully removed in v31.0.</source>
        <translation>“-paytxfee”已弃用，并将在 v31.0 中完全移除。 </translation>
    
ERR
This is mostly correct in meaning, but the text uses a Simplified Chinese character ("弃用") instead of the Traditional Chinese form expected for zh_TW. There's also an extra trailing space at the end.

Correct translation (Traditional Chinese, no trailing space):
“-paytxfee” 已棄用，並將在 v31.0 中完全移除。
```

<!-- cache_translation_check_zh_TW_a83d5bb13328c9c6bb05b9d617458f5b2f83d05560a3710195dfb9a046cf5907 -->
```
        <source>Cannot add WalletDescriptor to a non-descriptor wallet</source>
        <translation>无法将钱包描述符添加到非描述符钱包。</translation>
    
ERR
The translation uses Simplified Chinese characters ("无法", "钱包") but the target locale is zh_TW (Traditional Chinese). Also a slightly more natural phrasing in Traditional Chinese is recommended.

Correct translation:
無法將錢包描述符新增到非描述符錢包。
```

<!-- cache_translation_check_zh_TW_7fabb939c240330d61596107c938b130818e021e55701b8aa2132a1ecc76b3c8 -->
```
        <source>Could not generate scriptPubKeys (cache is empty)</source>
        <translation>无法生成脚本公钥（缓存为空）</translation>
    
ERR
The translation is in Simplified Chinese ("无法生成脚本公钥（缓存为空）"). For zh_TW (Traditional Chinese used in Taiwan), characters/terms should be in Traditional script and some localized terms adjusted.

Correct translation (Traditional Chinese, zh_TW):
無法生成 scriptPubKeys（快取為空）
```

<!-- cache_translation_check_zh_TW_1d81021bd0f5e08586ea41fd27117444164eb2a4027d5da2c4780a799bdfbce5 -->
```
        <source>Could not top up scriptPubKeys</source>
        <translation>无法补充脚本公钥</translation>
    
ERR
The translation uses Simplified Chinese characters ("无法补充脚本公钥") but the target locale is zh_TW (Traditional Chinese). Also consider keeping the technical term "scriptPubKeys" as-is or make it clear; the given wording is otherwise acceptable.

Correct translation (Traditional Chinese):
無法補充腳本公鑰
```

<!-- cache_translation_check_zh_TW_93b18ed6dfa8e0974d7760da9f746c5542c32230f9b0d191edc4bd4a05153ead -->
```
        <source>Error loading %s: Private keys can only be disabled during creation</source>
        <translation>載入 %s 時發生錯誤: 只有在造新錢包時能夠指定不允許私鑰</translation>
    
ERR
The translation is understandable but inaccurate and contains awkward phrasing. Specifically, "造新錢包" is less common than "新建錢包" or "建立錢包", and "指定不允許私鑰" is unclear—it should directly convey "can only disable private keys during creation".

Correct translation:
載入 %s 時發生錯誤：只有在建立錢包時才能停用私鑰
```

<!-- cache_translation_check_zh_TW_ba4b31fafa76b68ee6fefc8e8b4a7ed3d6fda25fd4bbf4dacf08fa9950112849 -->
```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
ERR
The translation omits "expected %s" and mistranslates the format. It also lacks proper punctuation and ordering for clarity.

Correct translation:
錯誤：轉存檔案的校驗和不符。計算值為 %s，預期為 %s
```

<!-- cache_translation_check_zh_TW_8ee0dfeba4ed3cda8cac10a98de3f474eb3de760eb406eae940799fc9fe863d3 -->
```
        <source>Error: Not all address book records were migrated</source>
        <translation>错误：并非所有地址簿记录都已迁移</translation>
    
ERR
The translation uses Simplified Chinese characters (e.g., "错误", "并非", "迁移") but the target locale is zh_TW (Traditional Chinese). No format specifiers to worry about and spacing is fine.

Correct Traditional Chinese translation:
錯誤：並非所有地址簿記錄都已遷移
```

<!-- cache_translation_check_zh_TW_dcfdd6315d1b3193dbb4dc6ce9abd68a96a5907b5b641337cb01c5fe62fb1489 -->
```
        <source>Error: Not all transaction records were migrated</source>
        <translation>错误：并非所有交易记录都已迁移</translation>
    
ERR
The translation uses Simplified Chinese characters (e.g., 错误、并非、记录、迁移) but the target locale is zh_TW (Traditional Chinese). No format specifiers are involved.

Correct Traditional Chinese translation:
錯誤：並非所有交易記錄都已遷移
```

<!-- cache_translation_check_zh_TW_8b1135fb065982e6c8ee05d3643b9ebb06cd5f98d94108205cfa2556397adb94 -->
```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
ERR
The translation uses simplified Chinese ("错误：无法将数据写入钱包的磁盘%s。"). For 'zh_TW', traditional Chinese characters should be used. Also, the phrasing is a bit awkward.

Correct translation:
錯誤：無法將資料寫入錢包 %s 的磁碟。
```

<!-- cache_translation_check_zh_TW_e4666fa4991fa511c3e025c7f0fca4b1e5628abb54946150622583f10c2a5101 -->
```
        <source>Failed to close block undo file.</source>
        <translation>关闭区块撤销文件失败。</translation>
    
ERR
The translation uses Simplified Chinese characters ("关闭区块撤销文件失败。") but the target locale is Traditional Chinese (zh_TW). No format specifiers are involved and spacing is fine.

Correct translation (Traditional Chinese, zh_TW):
關閉區塊撤銷檔案失敗。
```

<!-- cache_translation_check_zh_TW_961038e6cbaa1ae82ba5e46b0198703ac89711bf28a9d48eccde01cc70f549ac -->
```
        <source>Failed to close file when writing block.</source>
        <translation>写入区块时关闭文件失败。</translation>
    
ERR
The translation uses Simplified Chinese characters (e.g., 写入, 区块, 失败) but the target is zh_TW (Traditional Chinese). No format specifiers are present.

Correct Traditional Chinese translation:
寫入區塊時關閉檔案失敗。
```

<!-- cache_translation_check_zh_TW_bfba5479a7879ceb3a8fe1594b0469d71773b62d6ea3df387a6f180158c2e8e0 -->
```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
ERR
There are two issues:
1. The translation is missing the variable placeholder at the end: The format specifier "%s" is at the beginning in the translation, but in the source, it is at the end as ": %s".
2. The Chinese punctuation and word order are not idiomatic – the colon should be at the end, not left over in the translation.

Correct translation:
移除交易失敗：%s
```

<!-- cache_translation_check_zh_TW_c025a301b5f2476f25e2f437cfe19ca7bf860e73726d12cea62e2ba39df91298 -->
```
        <source>The wallet will avoid paying less than the minimum relay fee.</source>
        <translation>錢包軟體會付多於最小轉發費用的手續費。</translation>
    
ERR
The translation is inaccurate. The original English states the wallet will avoid paying less than the minimum relay fee, i.e., it will not pay a fee below that minimum. The translation reverses the meaning, suggesting the wallet will pay more than the minimum relay fee.

Correct translation:
錢包將避免支付低於最低轉發手續費的費用。
```

<!-- cache_translation_check_zh_TW_3d9320bea10d5e3e022a19cfd842e427af4d3ea041c7f0b8f6e7b309e8193b04 -->
```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
ERR
The translation is inaccurate. The English phrase "Transaction change output index out of range" refers to the index of the "change output" in a Bitcoin transaction being out of range. The provided translation, "交易尋找零輸出項超出範圍", mistranslates "change" as "尋找零" ("find zero") and does not accurately reflect the technical meaning.

Correct translation:
交易找零輸出索引超出範圍
```

<!-- cache_translation_check_zh_TW_8e865d9628d79836fa5dd7fd0b04804d638987eb236d0e8001360df73a8f73b1 -->
```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation>未知的交易已經有新規則激活 (versionbit %i)</translation>
    
ERR  
The translation is inaccurate. The English source refers to "Unknown new rules activated," but the translation says "未知的交易已經有新規則激活," which translates back to "Unknown transactions already have new rules activated." The word "交易" (transactions) is not in the source. The meaning is distorted.

Correct translation:
未知的新規則已被啟用（versionbit %i）
```

<!-- cache_translation_check_zh_TW_76b1bd6861e77279c4c3f4a191a4d295d0696f1f0ea13e7ad0a7140d44da079c -->
```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
ERR
There is an error in the translation: "1%s" incorrectly inserts a "1" before the format specifier, which should not be present. The correct translation would be:
錢包檔案建立失敗：%s
```

<!-- cache_translation_check_zh_TW_e3222f6658880630ea81b0a0cd483e7c2b2346ce99656d5b087dfe9f4559eb98 -->
```
        <source>Error loading %s: Wallet is a legacy wallet. Please migrate to a descriptor wallet using the migration tool (migratewallet RPC).</source>
        <translation>加载 %s时出错：钱包为传统钱包。请使用迁移工具（migratewallet RPC）迁移到描述符钱包。</translation>
    
ERR
The translation is in Simplified Chinese and not in Traditional Chinese as expected for 'zh_TW'. Also minor wording can be improved for natural Traditional Chinese.

Correct translation (Traditional Chinese, preserving the %s specifier):
載入 %s 時發生錯誤：錢包為舊式錢包。請使用遷移工具（migratewallet RPC）遷移至描述符錢包。
```

<!-- cache_translation_check_zh_TW_fb9c57de56fb521dfdc9b8cd4124ea9b1e9e4d83d4064c6624a1a81414b0eed7 -->
```
        <source>Error: Dumpfile specifies an unsupported database format (%s). Only sqlite database dumps are supported</source>
        <translation>错误：转储文件指定了不受支持的数据库格式 %s。仅支持 sqlite 数据库转储。</translation>
    
ERR
The translation is in Simplified Chinese (zh_CN) rather than Traditional Chinese (zh_TW), and it also changed the parentheses around the format specifier (%s) and spacing. The original contains '(%s)' which should be preserved.

Correct translation (Traditional Chinese, preserving (%s)):

錯誤：轉儲檔指定了不支援的資料庫格式 (%s)。僅支援 sqlite 資料庫轉儲。
```

<!-- cache_translation_check_zh_TW_2961cb13b7a86f1acc8115f9b7069881ec27d28d4cd7f3b72bc26f1e0634645b -->
```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on an enormous cluster of unconfirmed transactions.</source>
        <translation>由于未确认的 UTXO 依赖于庞大的未确认交易集群，无法计算提高手续费。</translation>
    
ERR
The translation is accurate in meaning but uses Simplified Chinese characters rather than Traditional Chinese (zh_TW). Also "由于/因为" should be the Traditional form "由於/因為" for zh_TW.

Correct Traditional Chinese (zh_TW) translation:
由於未確認的 UTXO 依賴於龐大的未確認交易集群，無法計算提高手續費。
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
The translation uses Simplified Chinese wording/characters (e.g., "发现", "该", "运行") instead of Traditional Chinese for zh_TW. The %s specifier is preserved correctly. There are minor extra spaces/newlines in the translation as well.

Suggested zh_TW translation (Traditional Chinese, cleaned spacing):
發現無法識別的描述符。正在載入錢包 %s

該錢包可能是在更新的版本中建立的。
請嘗試執行最新的軟體版本。
```

<!-- cache_translation_check_zh_TW_668168e51bf31783026bc50f64db78d6428f6b7ca953deeb14f11a4beaa350f9 -->
```
        <source>Error: Could not add watchonly tx %s to watchonly wallet</source>
        <translation>错误：无法添加仅观察交易%s到仅观察钱包</translation>
    
ERR
The translation uses simplified Chinese ("错误", "无法", "仅观察"), but 'zh_TW' should use traditional Chinese characters. Additionally, spacing is inconsistent; there should be a space between "交易" and "%s". 

Correct translation:
錯誤：無法將僅觀察交易 %s 新增到僅觀察錢包
```

<!-- cache_translation_check_zh_TW_3893aa5cc96d3a3e6fda580d5592a8e0694e08745e5bb4cb9823521e2db3de13 -->
```
        <source>Invalid -proxy address or hostname, ends with '=': '%s'</source>
        <translation>无效的 -proxy 地址或主机名，以“=”结尾：“%s”。</translation>
    
ERR
The translation uses Simplified Chinese ("无效的", "主机名") instead of Traditional Chinese for zh_TW. The format specifier %s is preserved, but punctuation/quotes can be made consistent for Traditional Chinese.

Correct translation (Traditional Chinese):
無效的 -proxy 位址或主機名稱，以「=」結尾：'%s'
```

<!-- cache_translation_check_zh_TW_8a65190ca204502b79b6c300f73c685661424c04e29136c9be3e8dc44a9de4b3 -->
```
        <source>Unrecognized network in -proxy='%s': '%s'</source>
        <translation>无法识别 -proxy=“%s” 中的网络：“%s”。</translation>
    
ERR
The translation uses Simplified Chinese characters ("无法识别", "网络") but target is zh_TW (Traditional Chinese). Also prefer matching quotes/spacing to the source.

Correct Traditional Chinese translation:
無法識別 -proxy='%s' 中的網路：'%s'。
```
</details>

Number of issues: 102.
