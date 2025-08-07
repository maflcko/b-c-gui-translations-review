# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>hak</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bhak%5D%20low%20quality)


```
        <source>Delete</source>
        <translation>刪除 D</translation>
    
YES
The translation contains an unnecessary "D" character after "刪除", which is both a format and content error. The proper translation should only be "刪除" if that's the correct Hakka term for "Delete". If Hakka uses a different term distinct from Mandarin, that should be used, but "D" at the end is incorrect.

Correct translation:
刪除
```

```
        <source>Choose the address to receive coins with</source>
        <translation>选择接收比特币地址</translation>
    
YES
The translation is in Simplified Chinese ("选择接收比特币地址"), not in the Hakka language ('hak') as requested.

Correct translation (in Hakka, using commonly accepted Hakka Romanization; text may vary based on regional standards, but a possible rendering is):
揀一個地址嚟收錢

(If Chinese characters are preferred: 揀一个地址来收銭)
```

```
        <source>Choose</source>
        <translation>选择(H)</translation>
    
YES
The translation is in Simplified Chinese ("选择(H)"), not in Hakka ('hak'). Hakka uses a different orthography and vocabulary.

Correct translation (in Hakka, using Romanized Pha̍k-fa-sṳ for reference):
Chhû-tshṳ́

If a specific script or preferred orthography is specified, adjust as needed.
```

```
        <source>Runaway exception</source>
        <translation>未捕获的异常</translation>
    
SPAM
The translation is in Simplified Chinese, not in Hakka ('hak'). "未捕获的异常" means "uncaught exception" in Chinese.

Correct translation (example in Hakka, using Latin transcription as commonly done):
Runaway exception: "走失个异常" (zou3 si1 ge3 yi4 co1).

Depending on the script standard, it might differ, but it should not be in Simplified Chinese.
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>出现致命错误。请检查设置文件是否可写，或者尝试带 -nosettings 参数运行。</translation>
    
SPAM
The translation provided is in Chinese, not in the 'hak' language (likely Hakka). It does not meet the requirement for 'hak'.

Correct translation (approximate, in Hakka using Latin script as an example, since standard Hakka written form is not fixed and often uses Mandarin characters with localized pronunciation):

Liau tet bun chhi-hin e loh-chhi. Chhia chhak kio siet-thiet bun siong siong ho tsai-si soi, tsun-to hak-yu -nosettings gin-gi khi-hang.

(Note: For production usage, consult with a native Hakka speaker/writer and consider if Latin script or Han characters are preferred by your user base.)
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>更改钱包密码</translation>
    
YES
The translation "更改钱包密码" is in Chinese, not in Hakka ('hak'). Also, it omits the explicit mention of "encryption" and "passphrase", which may lose some nuance.

Correct translation (in Hakka, written in Latin Hakka, for best coverage):
Siu vui ong ngiau ong-hiun-ki tong-yung e mi-ma.

If native script or conventions are used in your project, adapt accordingly.
```

```
        <source>Change Passphrase…</source>
        <translation>修改密码(C)</translation>
    
YES
The translation is in Simplified Chinese ("修改密码(C)"), not in 'hak' (Hakka). Additionally, the ellipsis (…) has been replaced by "(C)", which is not accurate.

Correct translation (approximate, as Hakka is not standardized in writing, but to show correct intent it could be phonetically represented):  
改善密碼…

Alternatively, if a widely accepted Hakka romanization or character is used for "change passphrase", it should be in Hakka, not standard Chinese.
```

```
        <source>Load PSBT from file…</source>
        <translation>从文件加载PSBT(L)...</translation>
    
SPAM
The translation is in Simplified Chinese rather than 'hak' (Hakka), and includes an extraneous "(L)" which is not in the original. 

Correct translation (if in Hakka, but as I'm not familiar with 'hak', cannot provide a correct version).
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES
The translation "卸载钱包" means "Uninstall wallet" in Chinese, which is incorrect for "Close wallet". The correct translation in Hakka should reflect 'closing' (not uninstalling). If using Hakka written in Chinese characters, a closer translation would be: "关闭钱包" or "閂钱包" (using the Hakka word for 'close').

Correct translation:
关闭钱包
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES
The translation is incorrect in meaning. "Enable network activity" means to turn ON network activity, but the translation "關閉網路紀錄" means "Close/turn off network record". It is the opposite.

Correct translation (in Hakka, based on written Hakka and Han characters commonly used for UI):
開啟網路活動

If "hak" refers to Hakka Chinese, "開啟" (enable) and "網路活動" (network activity) are appropriate.
```

```
        <source>Cannot create new wallet, the software was compiled without sqlite support (required for descriptor wallets)</source>
        <translation>无法创建新钱包，软件编译时未启用SQLite支持（输出描述符钱包需要它）</translation>
    
YES
The translation is in Simplified Chinese, not Hakka ('hak'), and closely matches the zh_CN translation rather than Hakka. Thus, it is incorrect for the 'hak' language tag.

Correct translation:
UNK_LANG, not familiar enough with the Hakka language ('hak') to provide a verified Hakka translation. However, the current translation is clearly not in Hakka.
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
SPAM
The translation is in Chinese ('复制和数量' means 'Copy and amount') rather than in 'hak' (Hakka). 'hak' is the ISO code for Hakka Chinese, which should have distinctive Hakka vocabulary or at least be labeled as such, but the provided text is Mandarin.

Correct translation (in Hakka Latin script):
"Fut-bî mó̤ siû"

(Note: Hakka commonly uses Han characters with regional variants, but the translation should at least differ from standard Mandarin.)
```

```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>迁移钱包 &lt;b&gt;%1&lt;/b&gt;...</translation>
    
UNK_LANG
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES
The translation "卸载钱包" means "Uninstall wallet" in Chinese, which is incorrect for "Close wallet". The correct translation in Hakka should reflect 'closing' (not uninstalling). If using Hakka written in Chinese characters, a closer translation would be: "关闭钱包" or "閂钱包" (using the Hakka word for 'close').

Correct translation:
关闭钱包
```

```
        <source>The wallet will also be stored in this directory.</source>
        <translation>钱包也会被保存在这个目录中。</translation>
    
YES
The translation provided is in Chinese, not in Hakka ('hak'). It uses standard Chinese characters instead of a Hakka transcription or appropriate Hakka orthography.

Correct translation (example in Hakka written in Han characters, as is common for Hakka texts, but with a more Hakka expression):
钱包也会存落在这兜目录里。

Note: The specific Hakka romanization or characters can vary; ensure the translation matches Hakka linguistic usage rather than standard Mandarin.
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain. It is faster to download the full chain first and prune it later. Disables some advanced features.</source>
        <translation>恢復此設定需要重新下載整個區塊鏈。 先下載完整鏈然後再修剪它的速度更快。 禁用一些高級功能。</translation>
    
UNK_LANG

Not familiar with the language 'hak' (Hakka). Unable to assess this translation.
```

```
        <source>Form</source>
        <translation>窗体</translation>
    
SPAM
The translation is in Chinese ('窗体', meaning 'form'), not Hakka ('hak'). The language is not as specified.

Correct translation (Hakka example):
表單 (Pió-thán) 

Note: Actual Hakka orthography may differ based on standardization, but '表單' is commonly used and understood.
```

```
        <source>Start %1 on system login</source>
        <translation>系统登入时启动 %1 (S)</translation>
    
UNK_LANG
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>与%1兼容的脚本文件路径（例如 C:\Downloads\hwi.exe 或者 /Users/you/Downloads/hwi.py ）。注意：恶意软件可以偷币！</translation>
    
SPAM
The translation provided is in Chinese rather than in the 'hak' language (Hakka). 

Correct translation (in Hakka, example approximation):
%1 适用个脚本路径（例如 C:\Downloads\hwi.exe 或 /Users/you/Downloads/hwi.py）。留心：病毒软件会偷你个钱币！

(Note: True Hakka script would use Hakka-specific characters and expressions, and may differ.)
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>显示默认的SOCKS5代理是否被用于在该类型的网络下连接同伴。</translation>
    
SPAM
The translation is in Simplified Chinese (zh_CN), not Hakka ('hak'). It does not provide a Hakka translation.

Correct translation (example in Hakka, though written Hakka is uncommon and may use Chinese characters):  
顯示所提供的預設SOCKS5代理係毋係用來經過這个網絡類型連接夥伴。

(Note: Written Hakka varies and is sometimes not standardized. Above is a best-effort example.)
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>警告:还原此设置需要重新下载整个区块链。</translation>
    
YES
The provided translation is in Chinese (not Hakka 'hak'), and the content adds "警告:" ("Warning:") which is not present in the source. Also, the translation is not specific to 'hak' language.

Correct translation (if in Hakka):  
UNK_LANG (as I am unfamiliar with the Hakka language and cannot provide an accurate translation).  
If standard Mandarin Chinese were correct, it would be:  
还原此设置需要重新下载整个区块链。  
But for 'hak', I cannot verify correctness.
```

```
        <source>Allow incoming connections</source>
        <translation>允许传入连接(G)</translation>
    
YES
The translation is in Chinese, not in 'hak' (Hakka). It provides the simplified Chinese translation: "允许传入连接(G)".

Correct translation (in Hakka, Romanized):
Hóh sîu-chhùn ngìn-fàng lièn-tsip

(Note: Exact Hakka orthography varies; this is a commonly accepted romanization. If Hak script is required, please specify.)
```

```
        <source>Minimize on close</source>
        <translation>单击关闭按钮时最小化(I)</translation>
    
SPAM
The translation is in Chinese (Simplified), not Hakka ('hak'). It translates as "Minimize when you click the close button (I)", which is not in Hakka.

Correct translation (example placeholder, as Hakka is primarily a spoken language and written Hakka can vary, but a more proper Hakka rendering might look like this):
关掉窗口个时候最小化

However, the exact standard for Hakka orthography may vary, and there may not be a widely accepted written Hakka standard for all software phrases.
```

```
        <source>Connect to the Bitcoin network through a separate SOCKS5 proxy for Tor onion services.</source>
        <translation>连接比特币网络时专门为Tor onion服务使用另一个 SOCKS5 代理。</translation>
    
YES
The translation is in Simplified Chinese, not in Hakka ('hak'). While 'hak' is sometimes written in Chinese characters, this appears to be Standard Chinese with no discernible Hakka features.

Correct translation (in actual Hakka, Peng'im romanization for clarity):
Tiong Tor onion fu-mu, chit bun SOCKS5 dailei lai liàng-bit Bitcoin ngie-net.

If characters are required, you may provide the closest-in Hakka characters: 通过Tor onion服务，使用另外一个SOCKS5代理来连接比特币网络。

However, the given translation does not meet the requirement for Hakka language.
```

```
        <source>OK</source>
        <translation>确定(O)</translation>
    
UNK_LANG
```

```
        <source>Form</source>
        <translation>窗体</translation>
    
SPAM
The translation is in Chinese ('窗体', meaning 'form'), not Hakka ('hak'). The language is not as specified.

Correct translation (Hakka example):
表單 (Pió-thán) 

Note: Actual Hakka orthography may differ based on standardization, but '表單' is commonly used and understood.
```

```
        <source>Your current total balance</source>
        <translation>您当前的总余额</translation>
    
YES
The provided translation is in Simplified Chinese, not Hakka ('hak'), even though the languages are related. 

Correct translation (in Hakka, using common romanization):

Ngî zông yèu-ngi zông yùhn-bàk

(Note: Actual written Hakka varies based on character usage and romanization conventions. If aiming for a written Hakka using Chinese characters, a possible variant is: 你當前個總餘額)
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
SPAM
The translation provided is in Chinese, not the requested Hakka ('hak') language.

Correct translation (if Hakka were desired; assuming Hakka is written in Hanzi and similar to some dialectal forms, an approximation might be):

您當前在只讀地址的餘額

But the main issue is that this is not in Hakka.
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>“概况”标签页已启用隐私模式。要明文显示数值，请在设置中取消勾选“不明文显示数值”。</translation>
    
YES
The translation is in Simplified Chinese, not in Hakka ('hak'). Therefore, it is not in the requested language.

Correct translation (in Hakka, using Hakka romanization as a conventional orthography since Hakka has no standardized written form, but a representative version might be):

"‘概况’标签箇已启动隐私模式。欲显明数值，请到‘设置’取消选取‘遮住数值’。"

Note: Please verify with native Hakka speakers as written Hakka conventions vary and localization in Hakka is rare.
```

```
        <source>Save…</source>
        <translation>拯救...</translation>
    
YES
The translation uses the Chinese term "拯救", which means "to rescue" or "to save" as in "to save someone", not "to save" as in "store a file". The correct term in Hakka (hak) for this context is more like "儲存" (to save/store). Also, the ellipsis should use the single Unicode character …, not three dots.

Correct translation:
儲存…
```

```
        <source>Could not sign any more inputs.</source>
        <translation>没有交易输入项可供签名了。</translation>
    
YES
The translation is in Simplified Chinese, not in Hakka ('hak'). Thus, the translation is erroneous.

Correct translation (attempt, since Hakka written form is rare; using romanized Hakka):
M̀ hó sáin cí-kî hóng sṳ̄-thi̍p sṳ̄-jip.

(Note: Accurate written Hakka is uncommon; verify with native speaker for correctness.)
```

```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>部分签名交易(二进制)</translation>
    
YES
The translation is in Simplified Chinese, not in the 'hak' (Hakka) language as specified.

Correct translation (in Hakka, using commonly accepted romanization):
Búfèn qiān mìng giao-yì (èr jìn zhǐ)

(Note: Hakka lacks a unified standard script, and the term may have some regional variations. If Hakka characters are desired, they closely resemble traditional Han characters but should be accompanied by Hakka romanization or annotations for clarity.)
```

```
        <source>Error encoding URI into QR Code.</source>
        <translation>把 URI 编码成二维码时发生错误。</translation>
    
SPAM
The translation is in Chinese, not Hakka ('hak'). 

Correct translation (suggested in Hakka, though Hakka is usually written in Chinese characters; a possible Hakka version using standard Hakka characters):
編碼 URI 變成二維碼時發生錯誤。
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES
The translation is in Simplified Chinese ("隐藏其他人的详细信息") rather than Hakka ('hak'). This is a generic Chinese translation meaning "Hide others' detailed information", which is not specifically Hakka.

Correct translation (in Hakka; if a suitable Hakka translation is not available, a Hakka version should be provided, for example):
"藏起客家话同伴个详细资料"

(Note: Hakka written language conventions may vary; adjust as per localization standards for 'hak'.)
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
SPAM
The translation is in Chinese ('复制和数量' means 'Copy and amount') rather than in 'hak' (Hakka). 'hak' is the ISO code for Hakka Chinese, which should have distinctive Hakka vocabulary or at least be labeled as such, but the provided text is Mandarin.

Correct translation (in Hakka Latin script):
"Fut-bî mó̤ siû"

(Note: Hakka commonly uses Han characters with regional variants, but the translation should at least differ from standard Mandarin.)
```

```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>部分签名交易(二进制)</translation>
    
YES
The translation is in Simplified Chinese, not in the 'hak' (Hakka) language as specified.

Correct translation (in Hakka, using commonly accepted romanization):
Búfèn qiān mìng giao-yì (èr jìn zhǐ)

(Note: Hakka lacks a unified standard script, and the term may have some regional variations. If Hakka characters are desired, they closely resemble traditional Han characters but should be accompanied by Hakka romanization or annotations for clarity.)
```

```
        <source>Amount:</source>
        <translation>金额(M)</translation>
    
YES
The translation is in Chinese (金额), not Hakka ('hak'). '金额' means "amount" in Mandarin Chinese; there is no evidence of Hakka usage or script. Also, the extra '(M)' is unexplained and unnecessary.

Correct translation:
A more appropriate Hakka translation should reflect the Hakka language (which often still uses Chinese characters but has distinct vocabulary or notation). If using Chinese characters as commonly written in Hakka, it might be: 金額：

If Hakka Romanization is required: Kîm-ngiak:

But as per majority convention, just: 金額：
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
YES
The translation is somewhat awkward in Hak (Hakka Chinese), and uses a phrase closer to Mandarin ("將支付發送到的比特幣地址給"), which is grammatically incorrect and possibly unclear.

Correct translation:
發送支付到的比特幣地址

Or, in more natural Hakka:
付款會發送到此比特幣地址

(Note: "付款會發送到此比特幣地址" means "The payment will be sent to this Bitcoin address". This phrasing is more natural and clear.)
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
SPAM
The translation is in Chinese ('复制和数量' means 'Copy and amount') rather than in 'hak' (Hakka). 'hak' is the ISO code for Hakka Chinese, which should have distinctive Hakka vocabulary or at least be labeled as such, but the provided text is Mandarin.

Correct translation (in Hakka Latin script):
"Fut-bî mó̤ siû"

(Note: Hakka commonly uses Han characters with regional variants, but the translation should at least differ from standard Mandarin.)
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>PSBT文件必须小于100MiB</translation>
    
UNK_LANG
```

```
        <source>Error starting/committing db txn for wallet transactions removal process</source>
        <translation>错误：启动/提交数据库事务时出错，导致钱包交易移除过程失败。</translation>
    
SPAM
The translation is in Chinese, not Hakka ('hak'). It simply copies the content in standard written Chinese.

Correct translation (example in Hakka; note: Hakka language is rarely written, and there is no standardized orthography, but here is an approximation using Chinese characters and Hakka-style expressions for educational purposes):
启动/交付数据库事务出错，导致钱包交易移除个过程失败。

If a more authentic Hakka Romanization is preferred:
Choih-tung/kiu-hap tú-sṳ-khò tsṳ-yong chhut-ho, tó-hak ngien-pau tsiòng-ngī chuk-sip sêu-pai.

But the above is generally increased Chinese readability in the absence of a standardized Hakka written form.
```

```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of pruned node)</source>
        <translation>修剪:上次同步钱包的位置已经超出（落后于）现有修剪后数据的范围。你需要进行-reindex（对于已经启用修剪节点，就需要重新下载整个区块链）</translation>
    
YES
The translation provided is in Chinese, not in Hakka ('hak'). It is understandable Mandarin Chinese and not Hakka.

Correct translation (in Hakka; note: as Hakka is primarily a spoken language, standardized written Hakka is uncommon, but using Taiwanese Hakka Romanization as reference):

修剪：最後一次钱包同步超過修剪後个資料。你需要用 -reindex（若係修剪節點，著重新下載完整區塊鏈）

If localized in Hakka Han characters (close to Cantonese/Hakka-influenced written Chinese):

修剪：最後一次錢包同步超過修剪後資料。你需要 -reindex（修剪節點需要重新下載全部區塊鏈）

However, please note that standardized written Hakka is rare and Chinese is most widely used in writing; true Hakka localization would more likely be in Romanized or Han-character Hakka.
```

```
        <source>Wallet loaded successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future. Legacy wallets can be migrated to a descriptor wallet with migratewallet.</source>
        <translation>钱包加载成功。旧式钱包已被弃用，未来将不再支持创建或打开旧式钱包。可以使用 migratewallet 命令将旧式钱包迁移至输出描述符钱包。</translation>
    
SPAM
The translation is in Chinese, not in the Hakka language ('hak') as required.

Correct translation (example in Hakka, approximate as a placeholder as Hakka is not widely standardized in writing—would more likely maintain some Mandarin structure, but adapted, or otherwise labeled as needing localization):

Wallet 成功加载。传统钱包类型即将弃用，将来不再支持创建和打开传统钱包。可用 migratewallet 工具将传统钱包迁移至 descriptor 钱包。

(Note: True Hakka localization would require an actual Hakka-literate translator.)
```

```
        <source>%s is set very high! Fees this large could be paid on a single transaction.</source>
        <translation>%s被设置得很高! 这可是一次交易就有可能付出的手续费。</translation>
    
YES
The translation is in Simplified Chinese, not in the Hakka language ('hak'). Therefore, it is problematic.

Correct translation (in Hakka, one possible rendition using Pha̍k-fa-sṳ romanization):

%s sṳ̀ chí hòn ká! Tǒ ngî sû kiê tsṳ tê tông sṳ phí chú kîa tông yit pîn chông ak.

(Note: Actual orthographic conventions for Hakka may vary. This is a general representation in Pha̍k-fa-sṳ romanization. A native Hakka speaker or a more standardized corpus may result in alternative versions.)
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>%s=&lt;amount&gt;: '%s' 中指定了非法的金额 (手续费必须至少达到最小转发费率(minrelay fee) %s 以避免交易卡着发不出去)</translation>
    
SPAM
The translation given is in Simplified Chinese, not the Hakka (hak) language.

Correct translation is not provided, as I am unfamiliar with Hakka ('hak').
```

```
        <source>Outbound connections restricted to CJDNS (-onlynet=cjdns) but -cjdnsreachable is not provided</source>
        <translation>传出连接被限制为仅使用CJDNS (-onlynet=cjdns) ，但却未提供 -cjdnsreachable 参数。</translation>
    
SPAM
The translation is in Chinese (likely Mandarin), not Hakka ('hak'). 

Correct translation (example in Hakka, though Hakka localization of such technical text is rare; if unavailable, best effort):
外出连线受限于只用CJDNS (-onlynet=cjdns)，但冇提供-cjdnsreachable参数。
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>出站连接被限制为仅使用 Tor (-onlynet=onion)，但是未提供到达 Tor 网络的代理：没有提供 -proxy=, -onion= 或 -listenonion 参数</translation>
    
YES
The provided translation is in Simplified Chinese rather than Hakka ('hak'). Additionally, it copies the Chinese translation from 'zh_CN' rather than providing a Hakka translation.

Correct translation (in Hakka, using Romanization based on conventions used in Hakka computing resources):
Chhut-sṳn liên-kie̍t chhèng-hǔ tor (-onlynet=onion), m̀ kiong cung -proxy, -onion tò -listenonion mông cung hó-khí tor mók-yǔ sít.

(Note: Hakka written form may vary and is less standardized than Mandarin. If a specific Hakka orthography/script is expected, it should be specified.)
```

```
        <source>Outbound connections restricted to i2p (-onlynet=i2p) but -i2psam is not provided</source>
        <translation>传出连接被限制为仅使用I2P (-onlynet=i2p) ，但却未提供 -i2psam 参数。</translation>
    
SPAM
The translation is in Chinese, not Hakka ('hak'). 

Correct translation in Hakka (example; adjust as necessary for authentic Hakka localization):
外送连接限制只用I2P (-onlynet=i2p)，毋过无提供-i2psam参数。
```

```
        <source>The preselected coins total amount does not cover the transaction target. Please allow other inputs to be automatically selected or include more coins manually</source>
        <translation>预先选择的币总金额不能覆盖交易目标。请允许自动选择其他输入，或者手动加入更多的币</translation>
    
YES
The translation is in Simplified Chinese, not in 'hak' (Hakka language). 'hak' refers to the Hakka language, which is distinct from Mandarin Chinese.

Correct translation (in Hakka, written in the commonly used romanization and/or Chinese characters for Hakka, if available):

預先選擇个幣總金額無法覆蓋交易目標。請允許自動選其他輸入，或係手動加多啲幣。

(NOTE: Hakka does not have a universally standardized written form. Above is a common approach using traditional characters and colloquial phrasing. Adjust texture to match your project's standards as needed.)
```

```
        <source>Unexpected legacy entry in descriptor wallet found. Loading wallet %s

The wallet might have been tampered with or created with malicious intent.
</source>
        <translation>在描述符钱包中意料之外地找到了旧式条目。加载钱包%s

钱包可能被篡改过，或者是出于恶意而被构建的。
</translation>
    
YES
The translation is in Simplified Chinese, not in 'hak' (Hakka). 

Correct translation:
UNK_LANG (since I'm unfamiliar with 'hak' and unable to provide a correct translation).
```

```
        <source>Dump file %s does not exist.</source>
        <translation>转储文件 %s 不存在</translation>
    
YES
The translation is in Simplified Chinese, not Hakka ('hak'). It uses Chinese characters and provides a Chinese translation rather than Hakka language.

Correct translation:
UNK_LANG or "SPAM: The translation is in Simplified Chinese, not in Hakka ('hak'). There is currently no standardized orthography for Hakka in Latin script, but the translation should not use Standard Mandarin Chinese characters."  
(A proper Hakka translation in Latin script might be: "Dump file %s mó̤ yit chhṳ́." But standard practice should be consulted for precise orthography.)
```

```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
YES
There is a typo in the type name: "unit32_t" should be "uint32_t". Also, "hak" refers to the Hakka language, but this translation is in Chinese (likely simplified). Therefore, the translation is both in the wrong language and contains a typo.

Correct translation (in Hakka, if available; otherwise, note the main issues):
SPAM
The translation is in simplified Chinese, not Hakka ("hak"), and there is a typo ("unit32_t" should be "uint32_t").

Correct translation (Hakka approximation as Hakka translations for technical terminologies are rare; falling back to orthographically Hakka-rendered technical loanwords or a direct Hakka version):
錯誤：無法將版本號%u解析成uint32_t
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES
The translation is problematic. In the Hak (Hakka) string, the format specifier %s is placed at the beginning, and the colon ":" is at the end, which is inconsistent with the English sentence. The translation is also very close to Chinese, not Hakka, and may not be a proper Hakka localization. There is a possibility that this is simply a Mandarin Chinese translation.

Correct translation (if using Hakka script/romanization, but since there's no standard Hakka writing, a common way is to use Hakka Pinyin or local Hakka expressions; for illustrative purposes, here's a possible romanized version):
移除交易失敗: %s

If correct Hakka script is not available, it is better to clarify with native speakers. The provided translation is not proper Hakka.
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES
The translation incorrectly renders "minimum fee rate setting" as "最大手续费率设置" which literally means "maximum fee rate setting". The correct translation for "minimum" is "最小" in Chinese-origin dialects, not "最大".

Correct translation:
手续费率 (%s) 低于最小手续费率设置 (%s)
```

```
        <source>Invalid -proxy address or hostname: '%s'</source>
        <translation>無效的 -proxy 地址或主機名稱: '%s'</translation>
    
UNK_LANG
```

```
        <source>Invalid P2P permission: '%s'</source>
        <translation>无效的 P2P 权限：'%s'</translation>
    
SPAM
The translation is in Chinese, not Hakka ('hak'). It uses "无效的 P2P 权限：'%s'" which is Mandarin Chinese.

Correct translation (example Hakka transliteration, since Hakka does not have standardized written form, is often rendered in Han characters, but would differ from Mandarin):
無效个 P2P 權限：'%s'

(Note: For projects, Hakka translations often employ characters used in dialectology, and sometimes use Romanization. Please verify with your linguistic resources for standard project usage.)
```

```
        <source>Not found pre-selected input %s</source>
        <translation>找不到预先选择输入%s</translation>
    
UNK_LANG
```

```
        <source>Not solvable pre-selected input %s</source>
        <translation>无法求解的预先选择输入%s</translation>
    
YES
The translation is in Simplified Chinese, not in 'hak' (Hakka). Therefore, it is not the requested language.

Correct translation (if translated into Hakka, based on available resources):
UNK_LANG
Since I am unfamiliar with the 'hak' (Hakka) language sufficiently to provide a correction.
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>交易需要一个找零地址，但是我们无法生成它。</translation>
    
SPAM
The translation is in Chinese, not Hakka ('hak'). It uses standard Mandarin characters and grammar.

Correct translation (example in Hakka written in Chinese characters, for reference. Note: Standardized Hakka written form is not highly established, but a typical rendition may be):
交易需要个找换地址，毋过𠊎们无法生成佢。

(If your Hakka localization uses Romanized Hakka, adjust accordingly, e.g. "ko1-yi5 hi55-iu3 khi3 cau2han3 ti5zhi3, m55-ko1 ngai5 m55fap8 shan1siang1 ki1.")
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES
The translation is mostly correct, but there is an erroneous "1" before the %s specifier. It should not be present as it is not in the source text.

Correct translation:
钱包文件创建失败：%s
```
</details>

Number of issues: 60.
