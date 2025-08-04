# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>zh</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bzh%5D%20low%20quality)


```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>注意: 如果你忘记了你的钱包，你将会丢失你的&lt;b&gt;密码，并且会丢失你的&lt;/b&gt;比特币。</translation>
    
YES. The translation has a grammatical error and is confusing. It places "lose your passphrase" after the bold tag which makes it sound like you will lose your bitcoins because you lose your password. The correct translation should be:

<translation>注意：如果您加密您的钱包但忘记了密码，您将&lt;b&gt;丢失所有的比特币&lt;/b&gt;！</translation>
```

```
        <source>%1 GB</source>
        <translation>%1 GB (十億位元組)</translation>
    
YES
The translation erroneously includes a parenthetical explanation of "GB" which is not present in the source text. The source text is a simple unit of data storage.

%1 GB
```

```
        <source>Show the list of used receiving addresses and labels</source>
        <translation>显示使用接收的地址或标签的列表</translation>
    
YES: The translation does not accurately convey the meaning of the source text. The phrase "used receiving addresses and labels" implies a list of addresses that have been used for receiving, along with their associated labels. The current translation "显示使用接收的地址或标签的列表" can be interpreted as "Show the list of addresses or labels that use receiving" which is unclear and grammatically incorrect. A more accurate translation would be "显示已使用的接收地址及其标签的列表".

显示已使用的接收地址及其标签的列表
```

```
        <source>Mask the values in the Overview tab</source>
        <translation>在“概况”标签页中不明文显示数值、只显示掩码</translation>
    
YES - The translation is too literal and doesn't accurately convey the meaning of masking values. "不明文显示数值、只显示掩码" literally translates to "do not display values in plain text, only display masks," which is redundant and awkward. The intended meaning is to obscure or hide the actual values.

Correct translation: 在“概况”标签页中隐藏数值
```

```
        <source>Hide</source>
        <translation>躲</translation>
    
YES: The translation is too literal and doesn't fit the context of Bitcoin. In a Bitcoin context, "Hide" usually means to conceal or remove something from view, rather than to physically hide.
Correct translation: 隐藏
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES
The translation is incorrect and conveys the opposite meaning of the source text. The source text "Enable network activity" means to turn on network activity, while the translation "關閉網路紀錄" means "Disable network logging" or "Turn off network recording".

The correct translation should be:
<translation>啟用網路活動</translation>
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation is inaccurate and misleading. The English phrase "Copy amount" means to copy the numerical value of an amount. The Chinese translation "复制和数量" literally means "copy and quantity", which does not convey the intended meaning.

A more accurate translation would be "复制金额" (fùzhì jīn'é), which means "copy amount" or "copy the amount".

Correct translation: 复制金额
```

```
        <source>Copy after fee</source>
        <translation>複製計費後金額</translation>
    
YES, the translation is inaccurate. The English phrase "Copy after fee" likely refers to copying an amount of Bitcoin *after* a fee has been deducted, or copying the transaction details including the fee. The Chinese translation "複製計費後金額" literally means "Copy the amount after billing," which is not the intended meaning in the context of Bitcoin transactions.

A more accurate translation would be:

<translation>費用後複製</translation>
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>启用修剪时，如果一个钱包被卸载太久，就必须重新同步整条区块链才能再次加载它。</translation>
    
YES - The translation uses "卸载" (uninstall/unload) which is not an accurate translation of "Closing the wallet" in the context of Bitcoin. The original English implies simply closing the application, not removing or uninstalling it.

Correct translation: 启用修剪时，如果钱包长时间未打开，则可能需要重新同步整个链。
```

```
        <source>Start %1 on system login</source>
        <translation>系统登入时启动 %1 (S)</translation>
    
YES
The translation is overly literal and sounds unnatural. The "S" at the end is also unnecessary and confusing.
Correct translation: 系统登录时启动 %1
```

```
        <source>External signer script path</source>
        <translation>外接簽證設備執行檔路徑(E)</translation>
    
YES, The translation uses a literal translation for "signer" as "簽證設備" (visa equipment) which is not the intended meaning in the context of Bitcoin. The correct term for a Bitcoin signer is usually "簽名者" (signer). The addition of "(E)" at the end is also an unnecessary character.

NO
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>軟體未編譯外接簽證功能所需的軟體庫(外接簽證必須有此功能)</translation>
    
YES - The translation is inaccurate and doesn't convey the intended meaning. It misinterprets "external signing" as "external visa" or "external signing support" as "software library required for external visa." The correct translation should focus on the concept of using external devices for signing transactions, not visas or software libraries in this context.

Correct translation: 外部簽名功能未編譯 (需要外部簽名)
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES, The translation is problematic because it contains redundant wording ("watch-only addresses" translated as "仅观察观察地址"). It should be "您当前在观察地址中的余额".
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>仅观察地址中尚未成熟的挖矿收入余额:</translation>
    
YES - The translation is problematic because it adds an extra colon at the end, which is not present in the source text.
Correct translation: 仅观察地址中尚未成熟的挖矿收入余额
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>无法启动 bitcoin: 协议的“一键支付”处理程序</translation>
    
YES, The translation is problematic because it incorrectly translates "click-to-pay handler" as "协议的“一键支付”处理程序". The correct translation should be "click-to-pay handler" which means "点击支付处理程序".

Correct translation: 无法启动 bitcoin: 点击支付处理程序
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES: The translation is inaccurate and misleading in the context of Bitcoin. "Peers" in this context refers to other nodes on the Bitcoin network, not "other people".
Correct translation: 隐藏节点详情
```

```
        <source>Outbound Feeler: short-lived, for testing addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to test the aliveness of known addresses.</extracomment>
        <translation>Outbound Feeler: 用於短暫，暫時 測試地址</translation>
    
YES
The translation has extraneous spacing and is slightly awkward.

Correct translation: Outbound Feeler: 用於測試地址
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Outbound 地址取得: 用於短暫，暫時 測試地址</translation>
    
YES, the translation is inaccurate and does not convey the intended meaning of the source text. The phrase "soliciting addresses" implies requesting or asking for addresses, not testing them.

Here's a breakdown of the issues:

*   **"short-lived, for soliciting addresses"**: The translation "用於短暫，暫時 測試地址" (yòng yú duǎnzàn, zànshí cèshì dìzhǐ) translates to "for brief, temporary testing of addresses". This is a misinterpretation of "soliciting addresses". "Soliciting" means to ask for or try to obtain something. In the context of Bitcoin peer connections, it means asking other nodes for their known peer addresses.

**Correct Translation:**

A more accurate translation would be:

Outbound 地址获取：用于短暂地请求地址

Here's the breakdown of the corrected Chinese phrase:

*   **Outbound 地址获取 (Outbound dìzhǐ huòqǔ)**: "Outbound Address Fetch" is translated accurately.
*   **用于短暂地 (yòng yú duǎnzàn de)**: "for short-lived" is translated correctly as "for brief" or "for short-lived".
*   **请求地址 (qǐngqiú dìzhǐ)**: This translates to "requesting addresses", which accurately captures the meaning of "soliciting addresses" in this context.
```

```
        <source>1 year</source>
        <translation>1 年(Y)</translation>
    
YES, The translation is problematic because the format specifier "(Y)" is not present in the source text.
1 year
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation is inaccurate and misleading. The English phrase "Copy amount" means to copy the numerical value of an amount. The Chinese translation "复制和数量" literally means "copy and quantity", which does not convey the intended meaning.

A more accurate translation would be "复制金额" (fùzhì jīn'é), which means "copy amount" or "copy the amount".

Correct translation: 复制金额
```

```
        <source>Copy after fee</source>
        <translation>複製計費後金額</translation>
    
YES, the translation is inaccurate. The English phrase "Copy after fee" likely refers to copying an amount of Bitcoin *after* a fee has been deducted, or copying the transaction details including the fee. The Chinese translation "複製計費後金額" literally means "Copy the amount after billing," which is not the intended meaning in the context of Bitcoin transactions.

A more accurate translation would be:

<translation>費用後複製</translation>
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES: The translation is missing the explanation of how the signing will happen. It's unclear what "使用簽名" refers to. The English text indicates that the PSBT can be signed *with* an offline wallet or a hardware wallet. The current translation implies "signing with signing".

Correct translation: 請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用離線%1錢包或與PSBT相容的硬體錢包進行簽名。
```

```
        <source>The address you selected for change is not part of this wallet. Any or all funds in your wallet may be sent to this address. Are you sure?</source>
        <translation>你选择的找零地址未被包含在本钱包中，你钱包中的部分或全部金额将被发送至该地址。你确定要这样做吗？</translation>
    
YES, The translation contains an error. The Chinese translation "未被包含在本钱包中" means "is not included in this wallet", which is not accurate in the context of Bitcoin. The correct translation should indicate that the address is not recognized or associated with the wallet.

Correct translation: 你选择的找零地址与本钱包无关。你钱包中的部分或全部金额可能会被发送到该地址。你确定要这样做吗？
```

```
        <source>Subtract fee from amount</source>
        <translation>从金额中减去交易费(U)</translation>
    
YES, The translation is problematic due to the addition of "(U)" which is not present in the source text and does not have a clear meaning in this context. It's also a mistranslation of "fee".

Correct translation: 从金额中减去费用
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES
The translation is inaccurate and misleading. The English phrase "Copy amount" means to copy the numerical value of an amount. The Chinese translation "复制和数量" literally means "copy and quantity", which does not convey the intended meaning.

A more accurate translation would be "复制金额" (fùzhì jīn'é), which means "copy amount" or "copy the amount".

Correct translation: 复制金额
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>無法在不支援「分割前的金鑰池」（pre split keypool）的情況下把「非分割HD錢包」（non HD split wallet）從版本%i升级到%i。請使用版本號%i，或壓根不要指定版本號。</translation>
    
YES: The translation is problematic because it uses overly literal and awkward phrasing for technical terms. The English terms "non HD split wallet" and "pre-split keypool" are translated into descriptive but cumbersome Chinese phrases ("非分割HD錢包" and "分割前的金鑰池"). While understandable, it's not idiomatic for technical contexts. A more natural and common phrasing would be to keep "HD" and clarify "split wallet" as a type of wallet that has been split. Similarly, "pre-split keypool" can be made more concise.

Corrected translation: 无法在不支持预分割密钥池的情况下，将非HD钱包从版本 %i 升级到版本 %i。请使用版本 %i 或不指定版本。
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
YES: The translation is missing a comma after the first "%s" and before the second "%s", which is present in the English source text. This leads to a grammatical error in Chinese.

Correct translation: 錯誤：轉存檔案識別記錄不正確。獲得 "%s"，預期 "%s"。
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES: The translation is not entirely accurate and uses awkward phrasing.
Correct translation: 提供了多个 onion 绑定地址。将使用 %s 来创建 Tor onion 服务。
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>找零低于当前粉尘阈值时会被舍弃，并计入手续费，这些交易手续费就是在这种情况下产生的。</translation>
    
YES - The translation is inaccurate and misleading. It incorrectly states that the transaction fee is generated when the change is discarded. The original English text implies that the fee might be discarded if it's smaller than the dust amount, and the change itself is being discussed in relation to dust.

Correct translation: 找零低于该级别粉尘阈值时，您可以舍弃此交易费用。
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>出站连接被限制为仅使用 Tor (-onlynet=onion)，但是未提供到达 Tor 网络的代理：没有提供 -proxy=, -onion= 或 -listenonion 参数</translation>
    
YES, The translation is problematic because the Chinese translation of the options "-proxy", "-onion", and "-listenonion" is incorrect. In the context of command-line arguments, these options should not be translated. The translation should be:
出站连接被限制为仅使用 Tor (-onlynet=onion)，但是未提供到达 Tor 网络的代理：没有提供 -proxy, -onion 或 -listenonion 参数
```

```
        <source>Unrecognized descriptor found. Loading wallet %s

The wallet might had been created on a newer version.
Please try running the latest software version.
</source>
        <translation>找到无法识别的输出描述符。加载钱包%s

钱包可能由新版软件创建，
请尝试运行最新的软件版本。
</translation>
    
YES: The term "descriptor" is directly translated as "输出描述符" (output descriptor), which might be too specific and not general enough in this context. "Descriptor" in Bitcoin usually refers to a way to derive addresses, and "输出描述符" typically refers to the output script in a transaction. A more general and accurate translation for "descriptor" in this context would be "描述符" (descriptor) itself.

Correct translation: 找到无法识别的描述符。加载钱包%s

钱包可能由新版软件创建，
请尝试运行最新的软件版本。
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
YES: The translation incorrectly translates "computed" as part of the second placeholder. The correct translation should have the placeholders in the correct order.
錯誤：轉存檔案的校驗和不匹配。計算得到 %s，預期 %s
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES: The format specifier '%s' is incorrectly placed at the end of the sentence in the translation. It should be placed directly after "wallet" to correctly refer to the wallet name.
错误：无法将数据写入钱包%s的磁盘。
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES, The translation is problematic. The format specifier %s is placed at the beginning of the translated string instead of the end. The phrase "失败:" should also be placed at the end of the sentence.
%s删除交易时失败:
Correct translation: 删除交易时失败: %s
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>%s=&lt;amount&gt;: '%s' 中指定了非法的金额 (必须至少达到 %s)</translation>
    
YES: The translation incorrectly places the format specifiers. The correct translation should be:
%s=&lt;amount&gt;: '%s' (必须至少达到 %s)
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES
The translation is inaccurate. The Chinese phrase "交易尋找零輸出項超出範圍" translates to "Transaction finding zero output index out of range", which is not what the English source text means.

The English source "Transaction change output index out of range" refers to an index for an output that is specifically designated as "change" in a Bitcoin transaction.

A more accurate translation would be:

交易找零輸出索引超出範圍
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES - The format specifier `%s` in the source text has been incorrectly translated to `1%s` in the target text. The correct translation should be `钱包文件创建失败：%s`.
```
</details>
