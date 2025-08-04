# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>hak</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bhak%5D%20low%20quality)


```
        <source>Copy the currently selected address to the system clipboard</source>
        <translation>把目前选择的地址复制到系统粘贴板中</translation>
    
UNK_LANG
```

```
        <source>Delete</source>
        <translation>刪除 D</translation>
    
YES, The 'hak' translation contains superfluous characters (" D") that are not present in the source English text. The correct translation should only be "刪除".
YES, 刪除
```

```
        <source>Choose the address to receive coins with</source>
        <translation>选择接收比特币地址</translation>
    
YES, The translation is problematic. The translation is missing the word "coins". It translates to "Select the Bitcoin address to receive" instead of "Choose the address to receive coins with".

NO
```

```
        <source>Choose</source>
        <translation>选择(H)</translation>
    
YES, The translation is problematic. The “(H)” suffix is likely intended to be a keyboard shortcut indicator in English, but it does not translate correctly into the target language and makes the translation nonsensical.

NO
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>钱包解密输入的密码不正确。</translation>
    
UNK_LANG
```

```
        <source>Runaway exception</source>
        <translation>未捕获的异常</translation>
    
YES
The translation is incorrect and does not convey the meaning of "Runaway exception". In the context of Bitcoin, an exception usually refers to an error or an unusual condition that disrupts normal program flow. "Runaway exception" suggests an exception that is not handled or is occurring repeatedly. The provided translation "未捕获的异常" means "uncaught exception" which is a plausible interpretation but "runaway" implies a more severe or uncontrolled situation. A more appropriate translation would capture the sense of an unhandled or persistent exception.

A better translation would be:
未处理的异常
or
失控异常
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>發生了內部錯誤%1 將嘗試安全地繼續。 這是一個意外錯誤，可以按如下所述進行報告。</translation>
    
YES
The Chinese translation failed to translate the word "address" and the phrase "as described below".
發生了內部錯誤。%1 將嘗試安全地繼續。這是一個意外錯誤，可以按如下所述進行報告。
```

```
        <source>Do you want to reset settings to default values, or to abort without making changes?</source>
        <extracomment>Explanatory text shown on startup when the settings file cannot be read. Prompts user to make a choice between resetting or aborting.</extracomment>
        <translation>要将设置重置为默认值，还是不做任何更改就中止?</translation>
    
YES, The translation uses Chinese characters, not the 'hak' language.
UNK_LANG
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>出现致命错误。请检查设置文件是否可写，或者尝试带 -nosettings 参数运行。</translation>
    
YES
The translation is problematic because the provided target language is 'hak' but the translation is in Chinese.
UNK_LANG
```

```
        <source>%1 and %2</source>
        <translation>%1又 %2</translation>
    
YES, The translation is incorrect and does not convey the meaning of the source text. The Chinese word "又" (yòu) means "again" or "also," which is not equivalent to the English conjunction "and". The correct translation should use the Chinese conjunction "和" (hé) to connect the two elements.

NO
```

```
        <source>%1 B</source>
        <translation>%1 B (位元組)</translation>
    
YES, The translation includes extraneous information "(位元組)" which is not present in the source text.

NO
```

```
        <source>%1 MB</source>
        <translation>%1 MB (百萬位元組)</translation>
    
YES, The translation is problematic because it adds an explanatory phrase in parentheses that was not present in the source text.
Correct translation: %1 MB
```

```
        <source>%1 GB</source>
        <translation>%1 GB (十億位元組)</translation>
    
YES
The translation for "%1 GB" is "%1 GB (十億位元組)", which means "%1 Gigabytes (billion bytes)". While Gigabytes can be interpreted as billion bytes, this translation is not a direct and common equivalent in Chinese for simply "GB". The most common and direct translation of "GB" in Chinese is "GB". Adding "(十億位元組)" is redundant and can be confusing.

NO
%1 GB
```

```
        <source>About %1</source>
        <translation>关于 %1 (A)</translation>
    
YES, The translation is problematic. The phrase "(A)" at the end of the translation is unnecessary and does not convey any meaningful information within the context of Bitcoin. It is likely an extraneous addition.

Correct translation:
<translation>关于 %1</translation>
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>更改钱包密码</translation>
    
YES
The translation is missing the word "passphrase".
Correct translation: 更改用于钱包加密的密码短语
```

```
        <source>Change Passphrase…</source>
        <translation>修改密码(C)</translation>
    
YES, The translation is problematic because the "C" in parentheses is likely an intended mnemonic accelerator that is not present in the English source. The correct translation should not include this.

NO
```

```
        <source>Load PSBT from file…</source>
        <translation>从文件加载PSBT(L)...</translation>
    
YES
The translation uses characters that are not typically used in 'hak' for the abbreviation "PSBT". The ellipsis "…" is also not correctly translated.
From file load PSBT...
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>從剪貼簿載入PSBT</translation>
    
YES - The translation is missing the ellipsis ("...") at the end, which is present in the source text. This omission changes the tone and completeness of the message.
Correct translation: 從剪貼簿載入PSBT…
```

```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
YES, The translation for "Sending addresses" into "付款地址(S)" is problematic because it includes an extraneous "(S)" which is not present in the source text. Additionally, it's a literal translation and not the most idiomatic way to refer to sending addresses in the context of Bitcoin. A more appropriate translation would be "发送地址" which directly translates to "sending addresses" and is commonly used in financial and cryptocurrency contexts.

Correct translation: 发送地址
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES
The translation is problematic. The Hak translation "卸载钱包" means "uninstall wallet", which is not an accurate translation of "Close wallet". Closing a wallet typically means to shut down the wallet application, not to uninstall it.

The correct translation should be something like "关闭钱包".

Correct Translation: 关闭钱包
```

```
        <source>Mask the values in the Overview tab</source>
        <translation>在“概况”标签页中不明文显示数值、只显示掩码</translation>
    
UNK_LANG
```

```
        <source>Hide</source>
        <translation>躲</translation>
    
YES
The translation is incorrect. In the context of Bitcoin, "Hide" would typically refer to hiding an address or transaction, for which the appropriate translation in Chinese would be "隐藏" (yǐncáng). "躲" (duǒ) means to dodge or hide from someone or something, which is not the intended meaning here.

The correct translation is:
        <translation>隐藏</translation>
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES - The translation is the opposite of the source. The source is "Enable network activity" which means to turn it on, but the translation "關閉網路紀錄" means "Close network record" or "Turn off network record". The correct translation should be "開啟網路紀錄".

YES - 關閉網路紀錄
```

```
        <source>Cannot create new wallet, the software was compiled without sqlite support (required for descriptor wallets)</source>
        <translation>无法创建新钱包，软件编译时未启用SQLite支持（输出描述符钱包需要它）</translation>
    
YES - The translation is mostly accurate but uses an awkward phrasing for "descriptor wallets". "Output descriptor wallets" is also a bit clunky.

Correct translation: 无法创建新钱包，软件编译时未启用SQLite支持（descriptor wallets 需要它）
```

```
        <source>HD key generation is &lt;b&gt;enabled&lt;/b&gt;</source>
        <translation>產生 HD 金鑰&lt;b&gt;已經啟用&lt;/b&gt;</translation>
    
UNK_LANG
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>錢包&lt;b&gt;已加密&lt;/b&gt;並且&lt;b&gt;解鎖中&lt;/b&gt;</translation>
    
YES, The translation of "unlocked" as "解鎖中" which means "unlocking" or "in the process of unlocking" is incorrect. The English text states that the wallet is "unlocked" meaning it is already in an unlocked state, not that it is currently undergoing the process of unlocking. The correct translation for "unlocked" in this context would be "解鎖" or "已解鎖".
錢包&lt;b&gt;已加密&lt;/b&gt;並且&lt;b&gt;已解鎖&lt;/b&gt;
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES, the translation is problematic. The Chinese translation "复制和数量" literally means "copy and quantity", which is not the intended meaning of "Copy amount". The correct translation should be "复制金额" which means "copy amount".

NO
```

```
        <source>Copy after fee</source>
        <translation>複製計費後金額</translation>
    
YES, The translation is problematic. The phrase "Copy after fee" in the context of Bitcoin transactions usually refers to copying the transaction amount *excluding* the fee. The current translation "複製計費後金額" (Copy amount after billing) implies copying the amount *including* the fee, which is the opposite of the intended meaning.

A more accurate translation would be:
"複製扣除手續費後金額" (Copy amount after deducting fee) or "複製扣費後金額" (Copy amount after deducting cost).
```

```
        <source>Creating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the create wallet progress window which indicates to the user which wallet is currently being created.</extracomment>
        <translation>正在創建錢包&lt;b&gt;%1&lt;/b&gt;...</translation>
    
UNK_LANG
```

```
        <source>Create wallet failed</source>
        <translation>創建錢包失敗&lt;br&gt;</translation>
    
YES, the translation is problematic. The format specifier "&lt;br&gt;" is incorrectly translated. It should be "<br>" to represent a line break.
The correct translation is: 創建錢包失敗<br>
```

```
        <source>Can't list signers</source>
        <translation>無法列出簽名器</translation>
    
UNK_LANG
```

```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>迁移钱包 &lt;b&gt;%1&lt;/b&gt;...</translation>
    
YES, The translation is problematic because the target language is specified as 'hak' but the provided translation is in Chinese. Therefore, the language is unrecognized.
UNK_LANG
```

```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>正在恢復錢包&lt;b&gt;%1&lt;/b&gt;...</translation>
    
UNK_LANG
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES
The translation is problematic. The Hak translation "卸载钱包" means "uninstall wallet", which is not an accurate translation of "Close wallet". Closing a wallet typically means to shut down the wallet application, not to uninstall it.

The correct translation should be something like "关闭钱包".

Correct Translation: 关闭钱包
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>启用修剪时，如果一个钱包被卸载太久，就必须重新同步整条区块链才能再次加载它。</translation>
    
YES, The translation is problematic because it mistranslates the meaning of "closing the wallet for too long". The English sentence implies that leaving the Bitcoin client inactive for an extended period can lead to a resynchronization of the blockchain if pruning is enabled. However, the 'hak' translation suggests that the wallet itself is "unloaded" (卸载) which is not the intended meaning.

The correct translation should convey the idea of the wallet being inactive or closed for too long, not being uninstalled or unloaded.

Corrected translation: 启用修剪时，如果一个钱包长时间关闭，则可能需要重新同步整个链。
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>跟這個地址清單關聯的地址。只有發送地址能被修改。</translation>
    
YES, The translation is not problematic but the format specifier "%" is not present in the source text. The translation uses the correct format specifier and it has been checked for unwanted content, erroneous content, or spam.
NO
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>地址“%1”為已登記存在“%2”的地址，因此無法新增為發送地址。</translation>
    
YES, The translation is problematic because it misinterprets the English sentence. The original English sentence states that the address already exists as a "receiving address" with a label and cannot be added as a "sending address". The current Chinese translation incorrectly states that the address is "already registered" as "an address" and cannot be added as a "sending address". The translation should specify that the address is already a receiving address and not a sending address.

Correct translation: 地址「%1」已作為標籤為「%2」的接收地址存在，因此無法新增為發送地址。
```

```
        <source>The wallet will also be stored in this directory.</source>
        <translation>钱包也会被保存在这个目录中。</translation>
    
UNK_LANG
```

```
        <source>Welcome to %1.</source>
        <translation>歡迎來到  %1。</translation>
    
YES - There is an extra space before "%1". The correct translation should be: "歡迎來到 %1。"
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain. It is faster to download the full chain first and prune it later. Disables some advanced features.</source>
        <translation>恢復此設定需要重新下載整個區塊鏈。 先下載完整鏈然後再修剪它的速度更快。 禁用一些高級功能。</translation>
    
UNK_LANG
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
YES
The translation is missing the final part of the sentence in the source text.
When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.
當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)，在%4最初推出時。
```

```
        <source>Form</source>
        <translation>窗体</translation>
    
YES, The translation is incorrect. "Form" in the context of Bitcoin usually refers to a user interface element or a document/template. The Chinese translation "窗体" means "window" or "form" in the sense of a window pane, which is not the intended meaning.
Correct translation: 表单
```

```
        <source>Estimated time left until synced</source>
        <translation>預計完成同步所需時間</translation>
    
UNK_LANG
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>從剪貼簿粘貼錢包位址</translation>
    
YES
The translation is problematic because it uses Chinese characters while the target language is specified as 'hak'. The correct language is likely Chinese, and the translation itself appears accurate for the provided English source text.

NO
NO
```

```
        <source>Main</source>
        <translation>主要(Main)</translation>
    
YES, The translation is problematic because it translates "Main" to "主要(Main)" which is redundant. The source text is "Main" and the translation should be the equivalent of "Main" in Hak. The correct translation is "主要".
YES, The translation is problematic because it translates "Main" to "主要(Main)" which is redundant. The source text is "Main" and the translation should be the equivalent of "Main" in Hak. The correct translation is "主要".
```

```
        <source>Start %1 on system login</source>
        <translation>系统登入时启动 %1 (S)</translation>
    
YES, The Chinese translation uses non-standard characters that are not relevant to the translation. The characters '(S)' should be removed.
The correct translation is: 系统登入时启动 %1
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>与%1兼容的脚本文件路径（例如 C:\Downloads\hwi.exe 或者 /Users/you/Downloads/hwi.py ）。注意：恶意软件可以偷币！</translation>
    
UNK_LANG
```

```
        <source>Map port using PCP or NAT-PMP</source>
        <translation>通过PCP或NAT-PMP映射端口。</translation>
    
UNK_LANG
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>显示默认的SOCKS5代理是否被用于在该类型的网络下连接同伴。</translation>
    
UNK_LANG
```

```
        <source>Prune block storage to</source>
        <translation>将区块存储修剪至(B)</translation>
    
YES
The translation is problematic because it is not in the 'hak' language. The provided translation appears to be in Chinese.
UNK_LANG
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>警告:还原此设置需要重新下载整个区块链。</translation>
    
YES: The translation adds the word "警告" (warning) which is not present in the original English text. This changes the meaning of the sentence and could be considered erroneous.
Correct translation: 还原此设置需要重新下载整个区块链。
```

```
        <source>Subtract fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>默认从金额中减去交易手续费(F)</translation>
    
YES
The translation incorrectly includes the letter "F" at the end of the sentence. This is likely a leftover from a previous translation or a mistake.

NO
Subtract fee from amount by default
```

```
        <source>Spend unconfirmed change</source>
        <translation>动用尚未确认的找零资金(S)</translation>
    
YES, The translation is problematic because it uses Chinese characters which are not part of the 'hak' language. It also seems to have an extra character at the end of the translation.
The correct translation should be: Spend unconfirmed change
```

```
        <source>Allow incoming connections</source>
        <translation>允许传入连接(G)</translation>
    
YES - The translation of "Allow incoming connections" to "允许传入连接(G)" is problematic. The character "(G)" is not part of the original English text and appears to be an unintended addition.
Correct translation: 允许传入连接
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>最小化到托盘(M)</translation>
    
UNK_LANG
```

```
        <source>Minimize on close</source>
        <translation>单击关闭按钮时最小化(I)</translation>
    
YES - The translation is grammatically incorrect and unnatural in Chinese. The intended meaning is to minimize the window when the close button is clicked.
Minimize on close -> 点击关闭按钮时最小化
```

```
        <source>User Interface language:</source>
        <translation>使用界面語言(L):</translation>
    
YES
The translation is problematic because it uses Chinese characters and includes an unnecessary "(L)" suffix. The original English is straightforward.

NO
```

```
        <source>Connect to the Bitcoin network through a separate SOCKS5 proxy for Tor onion services.</source>
        <translation>连接比特币网络时专门为Tor onion服务使用另一个 SOCKS5 代理。</translation>
    
YES - The translation is awkward and grammatically incorrect in Chinese. A more natural translation would be: “通过另一个 SOCKS5 代理连接到比特币网络，专门用于 Tor onion 服务。”
```

```
        <source>OK</source>
        <translation>确定(O)</translation>
    
YES, The translation is problematic. The Chinese translation of "OK" is "确定(O)", which contains a Chinese character "确" and an English letter "O" in parentheses. This is not a direct translation of "OK" and could be confusing. The correct translation for "OK" in this context would be "好的".
好的
```

```
        <source>Client will be shut down. Do you want to proceed?</source>
        <extracomment>Text asking the user to confirm if they would like to proceed with a client shutdown.</extracomment>
        <translation>客戶端軟體就要關掉了。繼續做下去嗎？</translation>
    
YES - The translation uses "客戶端軟體" which translates to "client software" in English. The source text only mentions "Client" which is usually a short form for "client application" or "client program". While "client software" is not entirely incorrect, it sounds a bit awkward and less natural in this context. A more accurate and natural translation would be "客戶端程式" or "客戶端應用程式". Additionally, "繼續做下去嗎？" translates to "Do you want to continue doing it?", which is a bit verbose. A more concise and direct translation would be "繼續嗎？" or "確定繼續嗎？".

Correct translation: 客戶端程式就要關閉了。確定繼續嗎？
```

```
        <source>The configuration file is used to specify advanced user options which override GUI settings. Additionally, any command-line options will override this configuration file.</source>
        <extracomment>Explanatory text about the priority order of instructions considered by client. The order from high to low being: command-line, configuration file, GUI settings.</extracomment>
        <translation>配置文件可以用来设置高级选项。配置文件会覆盖设置界面窗口中的选项。此外，命令行会覆盖配置文件指定的选项。</translation>
    
YES - The translation of "The configuration file is used to specify advanced user options which override GUI settings." to "配置文件可以用来设置高级选项。配置文件会覆盖设置界面窗口中的选项。" is incorrect. The source text is saying the configuration file overrides GUI settings, but the translation is saying the configuration file *can be used to set* advanced options and then *overrides* GUI settings. It is a little confusing but not completely wrong. The translation should be "配置文件用于指定高级用户选项，这些选项会覆盖GUI设置。此外，任何命令行选项都将覆盖此配置文件。"
```

```
        <source>Form</source>
        <translation>窗体</translation>
    
YES, The translation is incorrect. "Form" in the context of Bitcoin usually refers to a user interface element or a document/template. The Chinese translation "窗体" means "window" or "form" in the sense of a window pane, which is not the intended meaning.
Correct translation: 表单
```

```
        <source>Immature:</source>
        <translation>未成熟金額:</translation>
    
YES, The translation is problematic. The word "Immature" in this context refers to the maturity of a Bitcoin transaction (how many blocks have passed since it was included in a block), not an amount. The current translation "未成熟金額" translates to "immature amount," which is incorrect. A more appropriate translation would be "未成熟" (immature).

NO
```

```
        <source>Your current total balance</source>
        <translation>您当前的总余额</translation>
    
UNK_LANG
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES, The translation is problematic. The phrase "仅观察观察地址" is redundant and grammatically incorrect. A more accurate translation would be "仅观察地址".

NO
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>仅观察地址中尚未成熟的挖矿收入余额:</translation>
    
YES: The translation is inaccurate and uses an incorrect word for "balance". The term "挖矿收入" translates to "mining income", not "balance". The punctuation at the end is also unnecessary and does not match the source.

NO
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>“概况”标签页已启用隐私模式。要明文显示数值，请在设置中取消勾选“不明文显示数值”。</translation>
    
YES, The translation is problematic. The phrase "不明文显示数值" literally translates to "do not display values in clear text" which is the opposite of what the source text intends to convey. The source text wants to "unmask the values" or show them in clear text. The current translation is confusing and misleading.

Correct translation: “概况”标签页已启用隐私模式。要显示数值，请在设置中取消勾选“隐藏数值”。
```

```
        <source>Save…</source>
        <translation>拯救...</translation>
    
YES, The translation is problematic because the meaning is not relevant to Bitcoin. The word "save" in this context means to store a Bitcoin address, not to rescue or save someone or something. The correct translation should be "保存".
保存...
```

```
        <source>Could not sign any more inputs.</source>
        <translation>没有交易输入项可供签名了。</translation>
    
YES. The translation is not accurate and the format specifiers are not correct.

The source text mentions "inputs" but the translation uses "交易输入项" which is a bit redundant. It also incorrectly translates "sign any more inputs" to "没有交易输入项可供签名了" which means "There are no more transaction input items available for signing".

A more accurate translation would be:
"无法再签名任何输入项。"
```

```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>部分签名交易(二进制)</translation>
    
UNK_LANG
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>无法启动 bitcoin: 协议的“一键支付”处理程序</translation>
    
YES - The translation is problematic because it uses a Chinese phrase that means "protocol" when the English source text simply says "click-to-pay handler". The word "handler" is missing from the translation.
Correct translation: 无法启动 bitcoin：点击支付处理程序
```

```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>字首為 bitcoin:// 不是有效的 URI，請改用 bitcoin: 開頭。</translation>
    
YES. The translation uses Chinese characters for the English text, which is not the expected 'hak' language. The translation itself is also not accurate to the meaning of the English text. The English text is stating that the URI scheme "bitcoin://" is invalid and that "bitcoin:" should be used instead. The translation provided means "The prefix bitcoin:// is not a valid URI, please use bitcoin: instead." which is a literal translation but does not accurately convey the technical meaning in the context of Bitcoin.

UNK_LANG
```

```
        <source>Inbound</source>
        <extracomment>An Inbound Connection from a Peer.</extracomment>
        <translation>進來</translation>
    
YES
The translation of "Inbound" to "進來" is too general and does not accurately convey the meaning of an inbound connection in the context of Bitcoin. In the context of Bitcoin, "inbound" usually refers to incoming traffic or connections. A more appropriate translation would be "入站" which specifically means "inbound" or "incoming" in a networking context.

Correct translation: 入站
```

```
        <source>Error encoding URI into QR Code.</source>
        <translation>把 URI 编码成二维码时发生错误。</translation>
    
YES, The translation is problematic because the target language is specified as 'hak' but the translation provided is in Chinese.
UNK_LANG
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES, The translation is problematic. The source text "Hide Peers Detail" implies hiding details about specific peers on the Bitcoin network, likely to maintain privacy. The translation "隐藏其他人的详细信息" translates to "Hide other people's details," which is too broad and not specific enough to the context of Bitcoin peers.

The correct translation should reflect the hiding of peer details.

Correct translation: 隐藏节点详情
```

```
        <source>The network protocol this peer is connected through: IPv4, IPv6, Onion, I2P, or CJDNS.</source>
        <translation>这个节点是通过这种网络协议连接到的: IPv4, IPv6, Onion, I2P, 或 CJDNS.</translation>
    
UNK_LANG
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>來自這個節點上次成功驗證新交易進入內存池已經過的時間</translation>
    
YES, The translation is problematic because it does not accurately convey the meaning of the source text. The source text talks about the elapsed time since a transaction was received from a peer, not since the transaction was validated and entered the mempool.

Correct translation: 來自這個節點上次收到新交易進入內存池經過的時間
```

```
        <source>Out:</source>
        <translation>去:</translation>
    
YES
The translation is inaccurate and misleading in the context of Bitcoin. In Bitcoin transactions, "Out" typically refers to funds being sent out from a wallet, not a destination. The provided translation "去:" (qù:) in Chinese means "to go" or "away from", which is a very poor and inaccurate representation of the intended meaning. A more appropriate translation would reflect the idea of outgoing funds or an output.

Correct translation:
<translation>支出:</translation>
```

```
        <source>Outbound Manual: added using RPC %1 or %2/%3 configuration options</source>
        <extracomment>Explanatory text for an outbound peer connection that was established manually through one of several methods. The numbered arguments are stand-ins for the methods available to establish manual connections.</extracomment>
        <translation>出站手动: 加入使用RPC %1 或 %2/%3 配置选项</translation>
    
YES - The translation uses "加入" (jiārù - join) which is not appropriate in this context. The English "added" implies that the connection was established or initiated, not that it joined something.
Correct translation: 出站手动: 通过RPC %1 或 %2/%3 配置选项添加
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
YES
The translation is problematic because it does not accurately convey the meaning of the original English text. The phrase "short-lived, for soliciting addresses" implies a temporary connection for the purpose of requesting addresses. The 'hak' translation "用於短暫，暫時 測試地址" translates to "for short-lived, temporary testing of addresses", which changes the meaning from soliciting addresses to testing them.

A more accurate translation would be:
<translation>Outbound 地址取得: 短暫，用於徵求地址</translation>
```

```
        <source>v1: unencrypted, plaintext transport protocol</source>
        <extracomment>Explanatory text for v1 transport type.</extracomment>
        <translation>v1: 未加密，明文传输协议</translation>
    
YES - The translation is not in the 'hak' language. The provided translation is in Chinese. UNK_LANG
```

```
        <source>1 year</source>
        <translation>1 年(Y)</translation>
    
YES, The translation is problematic because it includes an extraneous parenthetical character "(Y)" which is not present in the source text. The correct translation should be "1 年".
NO
```

```
        <source>(peer: %1)</source>
        <translation>(同儕:%1)</translation>
    
YES, The translation is problematic because the word '同儕' (tóngshì péi) which means 'peers' in Chinese, does not appropriately translate 'peer' in the context of Bitcoin. In Bitcoin, 'peer' refers to a node on the Bitcoin network, and the term '同儕' is more often used in contexts like social groups or academic communities. A more fitting translation in this context would be '节点' (jiédiǎn), meaning 'node'. The translation also includes an unnecessary space before '%1'.

Correct translation: (节点:%1)
```

```
        <source>Ban for</source>
        <translation>禁止連線</translation>
    
YES, the translation is problematic. The source text "Ban for" is a general phrase that could refer to banning someone from something. The translation "禁止連線" specifically means "ban connection" or "disconnect". In the context of Bitcoin, "ban" usually refers to banning an IP address. Therefore, a more accurate translation would be "禁止 IP" or "封鎖 IP".

The correct translation is:
禁止 IP
```

```
        <source>Amount:</source>
        <translation>金额(A):</translation>
    
YES, The translation is incorrect and potentially misleading. The Chinese characters "金额" mean "amount", but the appended "(A)" does not have a clear or standard meaning in this context, especially within Bitcoin terminology. It's likely a mistranslation or an unnecessary addition.

Correct translation: 金额:
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES, the translation is problematic. The Chinese translation "复制和数量" literally means "copy and quantity", which is not the intended meaning of "Copy amount". The correct translation should be "复制金额" which means "copy amount".

NO
```

```
        <source>Verify this address on e.g. a hardware wallet screen</source>
        <translation>在例如硬體錢包螢幕上驗證這個地址</translation>
    
UNK_LANG
```

```
        <source>Send Coins</source>
        <translation>付款</translation>
    
YES
The translation "付款" (fùkuǎn) means "payment" in Chinese, which is not an accurate translation for "Send Coins" in the context of Bitcoin. A more appropriate translation would convey the action of sending cryptocurrency.

Correct translation:
Sending coins: 寄出硬币
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>以備用手續費金額(fallbackfee)來付手續費可能會造成交易確認時間長達數小時、數天、或是永遠不會確認。請考慮自行指定金額，或是等到完全驗證區塊鏈後，再進行交易。</translation>
    
YES - The translation is not in the 'hak' language. The provided translation is in Traditional Chinese. UNK_LANG
```

```
        <source>Specify a custom fee per kB (1,000 bytes) of the transaction's virtual size.

Note:  Since the fee is calculated on a per-byte basis, a fee rate of "100 satoshis per kvB" for a transaction size of 500 virtual bytes (half of 1 kvB) would ultimately yield a fee of only 50 satoshis.</source>
        <translation>指定每千字節（1,000字節）交易虛擬大小的自訂手續費。

注意：由於手續費是按每字節計算的，對於虛擬大小為500字節（半千字節）的交易，手續費率為「每千字節100聰」，最終將只收取50聰的手續費。</translation>
    
UNK_LANG
```

```
        <source>(Smart fee not initialized yet. This usually takes a few blocks…)</source>
        <translation>(手續費智慧演算法還沒準備好。通常都要等幾個區塊才行...)</translation>
    
YES, The translation uses characters not found in the hak language.
(Smart fee not initialized yet. This usually takes a few blocks…)
```

```
        <source>With Replace-By-Fee (BIP-125) you can increase a transaction's fee after it is sent. Without this, a higher fee may be recommended to compensate for increased transaction delay risk.</source>
        <translation>手续费追加（Replace-By-Fee，BIP-125）可以让你在送出交易后继续追加手续费。不用这个功能的话，建议付比较高的手续费来降低交易延迟的风险。</translation>
    
UNK_LANG
```

```
        <source>Copy after fee</source>
        <translation>複製計費後金額</translation>
    
YES, The translation is problematic. The phrase "Copy after fee" in the context of Bitcoin transactions usually refers to copying the transaction amount *excluding* the fee. The current translation "複製計費後金額" (Copy amount after billing) implies copying the amount *including* the fee, which is the opposite of the intended meaning.

A more accurate translation would be:
"複製扣除手續費後金額" (Copy amount after deducting fee) or "複製扣費後金額" (Copy amount after deducting cost).
```

```
        <source>Set external signer script path in Options -&gt; Wallet</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>在 選項 -&gt; 錢包 中設定外部簽名器腳本路徑 </translation>
    
UNK_LANG
```

```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>部分签名交易(二进制)</translation>
    
UNK_LANG
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES - The translation is incomplete and omits crucial information. The phrase "sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet" is not fully translated, and the phrase "then sign with e.g." is missing entirely.

Correct translation: 請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用例如離線%1錢包或與PSBT相容的硬體錢包進行簽名。
```

```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>没有打上BIP-125手续费追加的标记。</translation>
    
YES, The translation uses the wrong word for "signalling". The correct word is "信号".

NO, The translation is unproblematic.
```

```
        <source>A fee higher than %1 is considered an absurdly high fee.</source>
        <translation>超过 %1 的手续费被视为高得离谱。</translation>
    
YES, The translation is problematic because the language specified is Chinese, not 'hak'.
UNK_LANG
```

```
        <source>Amount:</source>
        <translation>金额(M)</translation>
    
YES, The translation is problematic because "金额(M)" is not a correct translation of "Amount:". The correct translation should be "金额：".
NO
```

```
        <source>Pay To:</source>
        <translation>付給(T):</translation>
    
YES, The translation is problematic because it is not in the 'hak' language. The translated text "付給(T):" is in Chinese.
UNK_LANG
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
YES
The translation is grammatically incorrect and awkward in Hak. The phrase "地址給" at the end is redundant and doesn't fit the context of specifying a destination.

Correct translation: 將支付發送到的比特幣地址
```

```
        <source>Subtract fee from amount</source>
        <translation>從付款金額減去手續費(U)</translation>
    
YES - The translation is problematic because it includes the character "(U)" at the end, which is not present in the source text. This could be a remnant from a previous translation or an accidental inclusion. The correct translation should not have this extra character.
Correct translation: 從付款金額減去手續費
```

```
        <source>Signatures - Sign / Verify a Message</source>
        <translation>签名 - 为消息签名/验证签名消息</translation>
    
UNK_LANG
```

```
        <source>kB/s</source>
        <translation>千字節/秒</translation>
    
YES
The translation is incorrect and uses Chinese characters for "kilobyte per second" instead of the correct 'hak' word.
NO
千字節/秒
```

```
        <source>conflicted with a transaction with %1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that conflicts with a confirmed transaction.</extracomment>
        <translation>跟一個目前確認 %1 次的交易互相衝突</translation>
    
YES, The translation is problematic because it implies that the transaction has %1 confirmations, while the original English text states that it conflicts with a transaction that has %1 confirmations. The correct translation should reflect this distinction.

YES, 跟一個有 %1 次確認的交易發生衝突
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1 次/未確認</translation>
    
YES, The translation is problematic because it is not accurate and does not convey the intended meaning. The original English text "%1/unconfirmed" refers to a number of confirmations a Bitcoin transaction has. The provided translation "%1 次/未確認" is not a standard way to express this in Chinese and would be confusing for users.

The correct translation should reflect the number of confirmations clearly.

Correct translation: %1 次确认/未确认
```

```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>确认中 (推荐 %2个确认，已经有 %1个确认)</translation>
    
YES, The translation has swapped the order of the confirmation counts. The source text specifies "%1 of %2 recommended confirmations" which means the current number of confirmations out of the total recommended number. The translation states "%2 recommended confirmations, already have %1 confirmations", which reverses this order and implies that the total recommended is %2 and the current is %1. The correct translation should reflect the original order.
Correct translation: 确认中 (推荐 %2个确认，有 %1个确认)
```

```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>未成熟 (%1 个确认，将在 %2 个后可用)</translation>
    
YES, The translation uses Chinese characters and is therefore not in 'hak'.
UNK_LANG
```

```
        <source>Received with</source>
        <translation>收款</translation>
    
YES: The translation is too literal and doesn't convey the intended meaning in the context of Bitcoin. "Received with" in Bitcoin typically refers to the method of receiving funds, like "Received with thanks" or "Received with confirmation." The translation "收款" simply means "received payment" and lacks the nuance of the original phrase.

A more appropriate translation would be:

<translation>收款自</translation>
```

```
        <source>Received with</source>
        <translation>收款</translation>
    
YES: The translation is too literal and doesn't convey the intended meaning in the context of Bitcoin. "Received with" in Bitcoin typically refers to the method of receiving funds, like "Received with thanks" or "Received with confirmation." The translation "收款" simply means "received payment" and lacks the nuance of the original phrase.

A more appropriate translation would be:

<translation>收款自</translation>
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES, the translation is problematic. The Chinese translation "复制和数量" literally means "copy and quantity", which is not the intended meaning of "Copy amount". The correct translation should be "复制金额" which means "copy amount".

NO
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>PSBT文件必须小于100MiB</translation>
    
UNK_LANG
```

```
        <source>Send Coins</source>
        <translation>付款</translation>
    
YES
The translation "付款" (fùkuǎn) means "payment" in Chinese, which is not an accurate translation for "Send Coins" in the context of Bitcoin. A more appropriate translation would convey the action of sending cryptocurrency.

Correct translation:
Sending coins: 寄出硬币
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>无法在不支持“拆分前的密钥池”（pre split keypool）的情况下把“非拆分HD钱包”（non HD split wallet）从版本%i升级到%i。请使用版本号%i，或者压根不要指定版本号。</translation>
    
YES, The translation incorrectly omits the format specifier %i.
Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.
```

```
        <source>Error starting/committing db txn for wallet transactions removal process</source>
        <translation>错误：启动/提交数据库事务时出错，导致钱包交易移除过程失败。</translation>
    
YES, the translation is problematic. The `hak` language code is not a recognized language. Assuming the intended language was Chinese (zh), the translation is accurate and unproblematic.

NO
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
YES, The format specifiers are not correctly translated.
The original format specifiers are "%s", but in the translation they are "%s".
The translation should be:
錯誤：轉存檔案識別記錄不正確。獲得 "%s"，預期 "%s"。
```

```
        <source>Invalid or corrupt peers.dat (%s). If you believe this is a bug, please report it to %s. As a workaround, you can move the file (%s) out of the way (rename, move, or delete) to have a new one created on the next start.</source>
        <translation>无效或损坏的peers.dat (%s)。如果你确信这是一个bug，请反馈到%s。作为变通办法，你可以把现有文件 (%s) 移开(重命名、移动或删除)，这样就可以在下次启动时创建一个新文件了。</translation>
    
UNK_LANG
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES, The translation is problematic because it incorrectly translates "bind address" as "路由綁定位址" which does not accurately convey the meaning of an IP address or a network address that a service binds to. It also incorrectly translates "onion service" as "Tor服務" which is not specific enough and loses the nuance of it being an onion service.

The correct translation should be:
提供多個 Onion 綁定位址。 將使用 %s 作為自動建立的 Tor Onion 服務。
```

```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of pruned node)</source>
        <translation>修剪:上次同步钱包的位置已经超出（落后于）现有修剪后数据的范围。你需要进行-reindex（对于已经启用修剪节点，就需要重新下载整个区块链）</translation>
    
YES
The translation is problematic because the phrase "落后于" (lagging behind) is not accurately conveyed. The source text "goes beyond" implies that the synchronization point is *ahead* of the pruned data, not behind it.

修剪: 上次同步钱包的位置已经超出已修剪数据的范围。你需要 -reindex (对于已修剪的节点，需要重新下载整个区块链)
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>這是您支付的最高交易手續費（除了正常手續費外），優先於避免部分花費而不是定期選取幣。</translation>
    
YES, The translation is problematic because it conveys a meaning that is the opposite of the original English text. The original text states that the fee is paid to "prioritize partial spend avoidance over regular coin selection", while the translation implies that the fee is paid to avoid partial spending *instead of* regular coin selection.

Correct translation: 這是您支付的最高交易手續費（除了正常手續費外），以優先避免部分花費，而非一般性的幣種選擇。
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>找零低于当前粉尘阈值时会被舍弃，并计入手续费，这些交易手续费就是在这种情况下产生的。</translation>
    
YES. The translation is problematic because it fundamentally misinterprets the source text. The source states that the transaction fee *may be discarded* if the change is smaller than dust. The translation says that the change *will be discarded* and *counted as part of the transaction fee*. This is a complete inversion of the meaning.

The translation also appears to be in Chinese (zh), not the specified 'hak'.

UNK_LANG. The translation is in Chinese (zh), not the requested 'hak'.
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>不支持的类别限定日志等级 %1$s=%2$s 。 预期参数 %1$s=&lt;category&gt;:&lt;loglevel&gt;。 有效的类别: %3$s 。有效的日志等级: %4$s 。</translation>
    
YES
The translation is problematic because it uses simplified Chinese characters instead of the requested 'hak' language.

UNK_LANG
```

```
        <source>Wallet loaded successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future. Legacy wallets can be migrated to a descriptor wallet with migratewallet.</source>
        <translation>钱包加载成功。旧式钱包已被弃用，未来将不再支持创建或打开旧式钱包。可以使用 migratewallet 命令将旧式钱包迁移至输出描述符钱包。</translation>
    
YES: The translation uses "旧式钱包" which translates to "old style wallet" or "legacy wallet" instead of "descriptor wallet". The correct translation for "descriptor wallet" is "描述符钱包". Additionally, the translation uses "输出描述符钱包" which means "output descriptor wallet" instead of "descriptor wallet".
The correct translation is: 钱包加载成功。旧式钱包类型已被弃用，未来将移除创建和打开旧式钱包的支持。可以使用 migratewallet 命令将旧式钱包迁移到描述符钱包。
```

```
        <source>You need to rebuild the database using -reindex to go back to unpruned mode.  This will redownload the entire blockchain</source>
        <translation>回到非修剪的模式需要用 -reindex 參數來重建資料庫。這會導致重新下載整個區塊鏈。</translation>
    
YES - The translation is problematic because it uses Chinese characters which are not the 'hak' language. The translation also contains an extra space before the period at the end.
NO - You need to rebuild the database using -reindex to go back to unpruned mode. This will redownload the entire blockchain
```

```
        <source>-maxmempool must be at least %d MB</source>
        <translation>參數 -maxmempool 至少要給 %d 百萬位元組(MB)</translation>
    
YES - The translation uses "百萬位元組(MB)" which is a verbose and unnatural way to say "MB". A more direct translation would be "MB".
-maxmempool 至少要給 %d MB
```

```
        <source>Cannot resolve -%s address: '%s'</source>
        <translation>沒辦法解析 -%s 參數指定的地址: '%s'</translation>
    
YES - The translation is problematic because it mistranslates "address" as "參數指定的地址" (parameter specified address) when it should be a Bitcoin address. The term "parameter" is not present in the original English text.

Correct translation: 無法解析 -%s 地址:'%s'
```

```
        <source>Cannot set -peerblockfilters without -blockfilterindex.</source>
        <translation>在沒有設定-blockfilterindex 則無法使用 -peerblockfilters</translation>
    
YES - The translation uses a literal translation of "without", which is grammatically incorrect in this context in Chinese.
Correct translation: 無法在未設定-blockfilterindex的情況下啟用-peerblockfilters。
```

```
        <source>%s is set very high! Fees this large could be paid on a single transaction.</source>
        <translation>%s被设置得很高! 这可是一次交易就有可能付出的手续费。</translation>
    
YES, the translation is problematic because it misinterprets the meaning of "fees this large". The original English states that the fees themselves are large, implying a high fee rate, not that such large fees could be paid on a single transaction. The Chinese translation incorrectly implies that large fees are paid *on* a single transaction.

Correct translation:
%s设置得很高！这么高的费用可能是在单笔交易中支付的。
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>%s=&lt;amount&gt;: '%s' 中指定了非法的金额 (手续费必须至少达到最小转发费率(minrelay fee) %s 以避免交易卡着发不出去)</translation>
    
YES
The translation is problematic as it omits the initial "Invalid amount for" phrase, which is crucial for conveying the error message accurately. Additionally, the translation of "minrelay fee" is a bit verbose and could be more concise.

Correct translation:
%s=&lt;amount&gt;: '%s' 的金额无效 (必须至少为 %s 的最小转发费率，以防止交易卡住)
```

```
        <source>Outbound connections restricted to CJDNS (-onlynet=cjdns) but -cjdnsreachable is not provided</source>
        <translation>传出连接被限制为仅使用CJDNS (-onlynet=cjdns) ，但却未提供 -cjdnsreachable 参数。</translation>
    
UNK_LANG
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>出站连接被限制为仅使用 Tor (-onlynet=onion)，但是未提供到达 Tor 网络的代理：没有提供 -proxy=, -onion= 或 -listenonion 参数</translation>
    
YES - The translation is problematic because it incorrectly translates "-onlynet=onion" as "仅使用 Tor (-onlynet=onion)". The original English specifies a restriction to Tor, which is accurately conveyed by "仅使用 Tor", but the inclusion of "(-onlynet=onion)" in the translated text is unnecessary and adds redundancy. Additionally, the translation of the latter part of the sentence, "but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given", is slightly awkward and could be more concise.

Correct translation: 出站连接被限制为仅使用 Tor (-onlynet=onion)，但未提供到达 Tor 网络的代理：未指定 -proxy、-onion 或 -listenonion 参数。
```

```
        <source>Outbound connections restricted to i2p (-onlynet=i2p) but -i2psam is not provided</source>
        <translation>传出连接被限制为仅使用I2P (-onlynet=i2p) ，但却未提供 -i2psam 参数。</translation>
    
UNK_LANG
```

```
        <source>The preselected coins total amount does not cover the transaction target. Please allow other inputs to be automatically selected or include more coins manually</source>
        <translation>预先选择的币总金额不能覆盖交易目标。请允许自动选择其他输入，或者手动加入更多的币</translation>
    
YES
The translation is problematic because it uses a literal translation of "preselected coins" which sounds unnatural in the context of Bitcoin. In Bitcoin transactions, "unspent transaction outputs" (UTXOs) are selected, not "coins" in a literal sense. The phrase "preselected coins" is also ambiguous and could be misunderstood. A more accurate and natural translation would refer to the selected inputs.

Correct translation:
<translation>选中的输入总金额不覆盖交易目标。请允许自动选择其他输入，或手动添加更多输入</translation>
```

```
        <source>Unexpected legacy entry in descriptor wallet found. Loading wallet %s

The wallet might have been tampered with or created with malicious intent.
</source>
        <translation>在描述符钱包中意料之外地找到了旧式条目。加载钱包%s

钱包可能被篡改过，或者是出于恶意而被构建的。
</translation>
    
YES
The translation is problematic. The original English text has an unexpected tone and wording.

The translation incorrectly uses "意料之外地" (unexpectedly) in a way that sounds unnatural in the context of a technical error message. The sentence "钱包可能被篡改过，或者是出于恶意而被构建的" (The wallet might have been tampered with, or it was constructed out of malicious intent) is also a bit verbose and could be more concise.

A more appropriate and natural translation would be:

<translation>在描述符钱包中发现意外的旧式条目。正在加载钱包 %s

钱包可能已被篡改或有意创建为恶意用途。
</translation>
```

```
        <source>Disk space is too low!</source>
        <translation>磁盘空间太低!</translation>
    
YES: The translation is not in the specified language 'hak'. The provided translation is in Chinese.
UNK_LANG
```

```
        <source>Dump file %s does not exist.</source>
        <translation>转储文件 %s 不存在</translation>
    
YES, The translation uses Chinese characters instead of the specified 'hak' language. Assuming 'hak' refers to a specific dialect or language not commonly encountered, the output should reflect this unfamiliarity. If 'hak' was intended to be a placeholder for a different language, clarification would be needed.

UNK_LANG
```

```
        <source>Error loading %s: Private keys can only be disabled during creation</source>
        <translation>載入 %s 時發生錯誤: 只有在造新錢包時能夠指定不允許私鑰</translation>
    
YES, the translation is problematic. The original English text states that private keys can only be disabled *during creation*. The Hak translation implies that private keys can only be *specified as not allowed* during creation, which is a misrepresentation of the original meaning. The correct translation should convey the disabling of private keys.

NO
```

```
        <source>Error loading %s: Wallet requires newer version of %s</source>
        <translation>載入檔案 %s 時發生錯誤: 這個錢包需要新版的 %s</translation>
    
YES, The translation missed the format specifier '%s'.
Error loading %s: Wallet requires newer version of %s
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
YES, The translation is problematic as the format specifiers are not correctly transferred and the sentence structure is awkward.
The correct translation should be:
錯誤：Dumpfile 校驗和不符。計算值 %s，預期值 %s
```

```
        <source>Error: Got key that was not hex: %s</source>
        <translation>錯誤：獲得的鍵不是十六進制：%s</translation>
    
YES - The translation contains an incorrect character. The character '錯' (cuò) means 'wrong' or 'error' in Chinese, but it is not the correct character to use in this context. It should be '錯' (cuò) which means 'mistake' or 'error'. The correct translation is:
錯誤：獲得的鍵不是十六進制：%s
```

```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>錯誤：keypool已用完，請先重新呼叫keypoolrefill</translation>
    
YES, The term "keypoolrefill" is not translated to Hak. The translation should be:

錯誤：keypool已用完，請先重新呼叫keypoolrefill
```

```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
YES, The word "unit32_t" is not translated correctly. It should be "uint32_t".
错误：无法把版本号%u作为uint32_t解析
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES, The "%s" format specifier is misplaced in the translation. The correct translation should have the format specifier at the end.
错误：无法将数据写入磁盘以用于钱包%s。
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES
The translation is problematic because the order of the `%s` placeholder and the rest of the text is reversed. The correct translation should maintain the original structure where the placeholder appears at the beginning.

%s删除交易时失败:
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES, the translation is problematic. The English source text states "lower than the minimum fee rate setting", but the Chinese translation uses "低于最大手续费率设置" which means "lower than the maximum fee rate setting". This is a factual error.

NO
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>无效的 -onion 地址: '%s'</translation>
    
YES - The translation is missing the word "hostname" from the original English phrase. The correct translation should include both "address" and "hostname".
无效的 -onion 地址或主机名: '%s'
```

```
        <source>Invalid -proxy address or hostname: '%s'</source>
        <translation>無效的 -proxy 地址或主機名稱: '%s'</translation>
    
YES - The translation uses Chinese characters which are not supported by the 'hak' language. The source text uses English.
UNK_LANG
```

```
        <source>Invalid P2P permission: '%s'</source>
        <translation>无效的 P2P 权限：'%s'</translation>
    
YES
The provided translation is in Chinese (zh), not Hak.
UNK_LANG
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>%s=&lt;amount&gt;: '%s' 中指定了非法的金额 (必须至少达到 %s)</translation>
    
YES. The translation is problematic because it is not in the 'hak' language as requested. The provided translation is in Chinese.

UNK_LANG
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s'</source>
        <translation>%s=&lt;amount&gt;: '%s' 中指定了非法的金额</translation>
    
YES, The translation is problematic because it reverses the order of the error message and the provided value, making it difficult to understand. Additionally, the phrase "指定了非法的金额" (specified an illegal amount) is slightly awkward in this context. A more natural translation would be to indicate that the provided value is an invalid amount.

Correct translation: %s=&lt;amount&gt;: '%s' 的金额无效
```

```
        <source>Not found pre-selected input %s</source>
        <translation>找不到预先选择输入%s</translation>
    
YES, the translation is problematic because it fails to correctly handle the format specifier '%s'. The English source uses '%s' to indicate a placeholder for a string, but the translation omits it.

The correct translation should be:
找不到预先选择的输入%s
```

```
        <source>Not solvable pre-selected input %s</source>
        <translation>无法求解的预先选择输入%s</translation>
    
YES
The translation is too literal and doesn't convey the intended meaning in the context of Bitcoin. In Bitcoin, "solvable" refers to whether the inputs of a transaction can be spent, meaning they are valid and can be processed. The translation uses "无法求解的" which means "unsolvable" or "unanswerable" in a general sense, but not in the technical Bitcoin context.

A more accurate translation would be:
"无法花费的预选输入%s"
```

```
        <source>Prune mode is incompatible with -txindex.</source>
        <translation>修剪模式和 -txindex 參數不相容。</translation>
    
UNK_LANG
```

```
        <source>Specified -walletdir "%s" is a relative path</source>
        <translation>以 -walletdir 指定的路徑 "%s" 是相對路徑</translation>
    
YES - The translation is grammatically incorrect and awkward in 'hak'. The structure should be more direct.

Correct translation: 以 -walletdir 設定的 "%s" 是相對路徑
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES, The translation is problematic. The second character of the translation is an extra character that should not be there.
NO, 交易金额不可为负数
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES - The translation is incorrect and does not convey the meaning of the source text. The source text refers to the "index" of a "change output" in a Bitcoin transaction being out of the valid range. The translation "交易尋找零輸出項超出範圍" can be interpreted as "Transaction search for zero output item out of range," which is not related to the original meaning.

Correct translation: 交易找零輸出索引超出範圍
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>交易需要一个找零地址，但是我们无法生成它。</translation>
    
YES. The translation uses Chinese characters for the English word "change" without translating the rest of the sentence. The context of Bitcoin suggests that "change" refers to the change address in a transaction.

Transaction needs a change address, but we can't generate it.
交易需要一个找零地址，但我们无法生成。
```

```
        <source>Unable to create the PID file '%s': %s</source>
        <translation>無法創建PID文件'%s': %s</translation>
    
YES, The translation is problematic. The target language is specified as 'hak', but the translation provided is in Chinese.
UNK_LANG
```

```
        <source>Unknown -blockfilterindex value %s.</source>
        <translation>未知的 -blockfilterindex 数值 %s。</translation>
    
YES, The translation is problematic. The language code 'hak' is incorrect. The provided translation is in Chinese. The correct language code for Chinese is 'zh'. The translation itself is also inaccurate. The term "blockfilterindex" is not translated correctly. It should be translated as "blockfilterindex" in English or a more appropriate technical term if available in Chinese.
UNK_LANG
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES, The format specifier '%s' is incorrectly translated to '1%s'.
Wallet file creation failed: %s
```

```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>用户代理备注(%s)包含不安全的字符。</translation>
    
YES, The translation is grammatically incorrect and unnatural in Chinese. The correct translation should be: 用户代理评论(%s)包含不安全字符。
```

```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>錢包需要重寫: 請重新啓動 %s 來完成</translation>
    
YES - The translation uses Chinese characters for "Wallet needed to be rewritten: restart %s to complete". The language specified is 'hak', which is not a recognized language. Assuming 'hak' is a typo and the intended language is Chinese (zh-CN), the translation is accurate. However, since the provided language code is incorrect, the system cannot confirm the translation.

Correct Translation (assuming Chinese): 錢包需要重寫: 請重新啟動 %s 以完成
```
</details>
