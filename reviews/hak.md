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
    
YES
The translation includes an extraneous " D" after the main translation "刪除", which is unnecessary and incorrect. The correct translation should be simply:

刪除
```

```
        <source>Choose the address to receive coins with</source>
        <translation>选择接收比特币地址</translation>
    
YES  
The translation is in Chinese, not in the 'hak' language. Additionally, it omits the part "to receive coins with" and is a shortened version that might lose nuance. The correct translation in the Hakka language should reflect the entire phrase and use Hakka vocabulary and structure.

Correct translation (in Hakka, romanized):  
"揀擇用嚟接收錢銀个地址"  

(Note: As 'hak' refers to Hakka, the most appropriate translation would be in Hakka; the provided text is Chinese.)
```

```
        <source>Choose</source>
        <translation>选择(H)</translation>
    
YES
The translation includes Chinese characters "选择(H)" which means "Choose (H)" but this is not in Hakka language ('hak'). The translation also unnecessarily includes "(H)" which is not present in the source text. The correct translation in Hakka should be a proper Hakka word for "Choose" without additional characters.

Correct translation:
擇 (if using Hakka Chinese characters) or a proper Hakka romanization equivalent, for example "chhak" (depending on the dialect). However, the best is to just keep it simple as "擇" without the "(H)".
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>钱包解密输入的密码不正确。</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Runaway exception</source>
        <translation>未捕获的异常</translation>
    
YES  
The translation "未捕获的异常" is in Chinese (Simplified), not in Hakka ('hak'). This is problematic because the language code requires a Hakka translation, which is distinct from standard Chinese.  

Correct translation in Hakka is not provided here due to lack of exact knowledge, but the current translation should be replaced with a proper Hakka rendering of "Runaway exception."  

(If no Hakka version is available, it should be marked as needing proper translation rather than a Chinese simplification.)
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>發生了內部錯誤%1 將嘗試安全地繼續。 這是一個意外錯誤，可以按如下所述進行報告。</translation>
    
YES  
The translation is mostly accurate but has formatting issues with spacing around the format specifier %1 and some spacing inconsistencies. In the source, the sentences are separated properly with spaces. In the translation, there is no space before %1 and an extra space after the full stop before the second sentence.

Correct translation:  
發生了內部錯誤。%1 將嘗試安全地繼續。這是一個意外錯誤，可以按如下所述進行報告。
```

```
        <source>Do you want to reset settings to default values, or to abort without making changes?</source>
        <extracomment>Explanatory text shown on startup when the settings file cannot be read. Prompts user to make a choice between resetting or aborting.</extracomment>
        <translation>要将设置重置为默认值，还是不做任何更改就中止?</translation>
    
YES  
The translation provided is in Simplified Chinese, not in Hakka ('hak'). The language code 'hak' refers specifically to the Hakka language, which is distinct from Mandarin Chinese. Therefore, this translation is not appropriate for 'hak'.

Correct translation in Hakka (using Romanized Hakka, for example Meixian dialect transliteration, or if a Hakka script is required):

「你愛愛重設設定做預設值，定係毋使改就結束？」 

(Note: Hakka translations can vary by dialect and script. This is an example in Romanized Hakka.)
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>出现致命错误。请检查设置文件是否可写，或者尝试带 -nosettings 参数运行。</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>%1 B</source>
        <translation>%1 B (位元組)</translation>
    
YES
The source text "%1 B" simply denotes a size in bytes, where "B" stands for bytes; adding "(位元組)" in the translation is redundant and inconsistent with the concise source format. The translation should directly replicate the source for clarity and format consistency.

Correct translation:
%1 B
```

```
        <source>%1 MB</source>
        <translation>%1 MB (百萬位元組)</translation>
    
YES  
The addition of "(百萬位元組)" in the translation is unnecessary and inconsistent, as the source only shows "%1 MB" without any extra explanation or parentheses. The translation should directly mirror the source text with the format specifier and unit intact, without added explanations.

Correct translation:  
%1 MB
```

```
        <source>%1 GB</source>
        <translation>%1 GB (十億位元組)</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>About %1</source>
        <translation>关于 %1 (A)</translation>
    
YES  
The source text "About %1" is likely meant as a simple phrase indicating "About [something]", such as an About dialog or information section. The translated text "关于 %1 (A)" contains Chinese characters ("关于") which means "About," but this is not in Hakka (hak) script or language. The suffix "(A)" is extraneous and does not correspond to the source text.

Correct translation in Hakka (using Latin script as commonly used for Hakka) might be:  
"Guàng yit %1" or simply "Gong yit %1" depending on dialect.

However, without a standardized Hakka writing norm or script in the source, and given that the provided translation is Chinese plus an unexplained "(A)", the translation is problematic.  

A better attempt would be to avoid Chinese characters and the unexplained suffix, or to provide a proper Hakka translation.

Correct translation (example in Hakka romanization):  
About %1  
-> "Gong yit %1"  

If strict Hakka is unavailable, a transliteration without Chinese characters would be preferable.  

Hence:  
YES  
The translation uses Chinese characters and an extraneous "(A)" suffix, which is inappropriate for a Hakka translation. The source is a short phrase "About %1" and should be translated properly into Hakka or at least not contain Chinese characters and extraneous text.

Correct translation:  
<translation>Gong yit %1</translation>
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>更改钱包密码</translation>
    
YES  
The translation "更改钱包密码" means "Change wallet password," which omits the "passphrase" aspect and does not explicitly mention "used for wallet encryption." It is less precise and not fully capturing the original meaning related to encryption.  

Correct translation (to better reflect the original meaning):  
更改用于钱包加密的密码短语
```

```
        <source>Change Passphrase…</source>
        <translation>修改密码(C)</translation>
    
YES  
The translation "修改密码(C)" means "Change password (C)" in Chinese, which is neither in the 'hak' language nor an accurate translation of "Change Passphrase…". Also, the "(C)" is not present in the source and may be an unrelated leftover. The original English refers to changing a passphrase, which is typically "改密碼" or a similar phrase in Hakka ('hak') language. However, since the provided translation is in Chinese (likely Mandarin) and not Hakka, it is problematic.

Correct translation in Hakka should be a proper rendering of "Change Passphrase…", such as (assuming Hakka with Chinese characters):

"更改密碼…"  

(if Hakka uses Chinese characters similarly)

If Latin script is used in Hakka, then an appropriate transliteration or phrase would be needed, but without further dialect information, the best fix is to translate properly in Hakka or remove unrelated notations.

Therefore, the provided translation is incorrect and not in Hakka.
```

```
        <source>Load PSBT from file…</source>
        <translation>从文件加载PSBT(L)...</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>從剪貼簿載入PSBT</translation>
    
UNK_LANG
```

```
        <source>Sending addresses</source>
        <translation>付款地址(S)</translation>
    
YES  
The translation "付款地址(S)" is primarily in Chinese, not in Hakka (hak), and includes a parenthetical "(S)" which does not appear in the source text. Additionally, the original English term "Sending addresses" implies addresses used for sending transactions, which would be more accurately translated in Hakka without mixing Chinese or adding extraneous characters.

Correct translation (in Hakka):  
"送出地址"
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES
The translation "卸载钱包" means "uninstall wallet" which is incorrect for "Close wallet." The correct translation should convey the action of closing or shutting the wallet, not uninstalling it.

Correct translation:
关闭钱包
```

```
        <source>Mask the values in the Overview tab</source>
        <translation>在“概况”标签页中不明文显示数值、只显示掩码</translation>
    
YES  
The provided translation is in Chinese, not in the Hakka language ('hak'). Therefore, it does not correspond to the requested language.

A more appropriate translation in Hakka should be supplied instead. Since I do not have sufficient data to provide an accurate Hakka translation, the correct approach would be to translate the English phrase into Hakka properly. However, this requires expert knowledge of the Hakka language.

For reference, the English source is:  
"Mask the values in the Overview tab"

The Chinese translation roughly means:  
"Do not display the values in clear text on the 'Overview' tab, only show masks"

This is accurate in meaning but not in the correct language.

Correct action: Provide a translation in Hakka or mark as unknown due to improper language used.
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>關閉網路紀錄</translation>
    
YES  
The English source "Enable network activity" means to turn on or allow network activity, whereas the provided 'hak' translation "關閉網路紀錄" means "Close network logging" or "Disable network recording," which is the opposite of the intended meaning.

Correct translation:  
啟用網路活動
```

```
        <source>Cannot create new wallet, the software was compiled without sqlite support (required for descriptor wallets)</source>
        <translation>无法创建新钱包，软件编译时未启用SQLite支持（输出描述符钱包需要它）</translation>
    
UNK_LANG
```

```
        <source>HD key generation is &lt;b&gt;enabled&lt;/b&gt;</source>
        <translation>產生 HD 金鑰&lt;b&gt;已經啟用&lt;/b&gt;</translation>
    
YES
The HTML tags for bold are incorrectly formatted in the translation. The source uses &lt;b&gt; and &lt;/b&gt; (escaped), but the translation has mixed escaped and unescaped tags ("&lt;b&gt;" and "&lt;/b&gt;"). Both should be consistently escaped for XML compatibility. Also, the translation is missing the space before the tag, which affects readability and formatting.

Correct translation:
產生 HD 金鑰 &lt;b&gt;已經啟用&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>錢包&lt;b&gt;已加密&lt;/b&gt;並且&lt;b&gt;解鎖中&lt;/b&gt;</translation>
    
YES  
The translation mixes Chinese characters with 'hak' romanization in a way that seems inconsistent. The provided translation is in Chinese ("錢包已加密並且解鎖中"), which does not correspond to the Hakka language, which is distinct and typically written in Latin script or sometimes Chinese characters with unique pronunciation. Also, the translation lacks spaces or punctuation to separate phrases properly in Latin script.  
If the requirement is for the Hakka language using Latin script, it should look different. However, if the intended script is Chinese characters for Hakka, then it would be different as well.

A basic Hakka (romanized) translation (using the Pha̍k-fa-sṳ Latin transcription system) could be:  
**"Cînbó sît &lt;b&gt;gâ-mi̍t&lt;/b&gt; ng m̀h-dài &lt;b&gt;kài-soh zûng&lt;/b&gt;"**

Note: The exact Hakka translation may vary by dialect, but the given translation is Chinese, not Hakka.  
If Chinese characters are acceptable for Hakka, it should clarify that the text is in Hakka dialect characters.

Hence:  
YES  
The translation is in Chinese, not in Hakka. It must be corrected to Hakka language form or clarified.
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES  
The translation "复制和数量" means "copy and amount," which adds an unnecessary conjunction "和" ("and") not present in the source. The correct translation should simply convey "Copy amount" without "and."  

Correct translation:  
复制数量
```

```
        <source>Copy after fee</source>
        <translation>複製計費後金額</translation>
    
UNK_LANG
```

```
        <source>Creating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the create wallet progress window which indicates to the user which wallet is currently being created.</extracomment>
        <translation>正在創建錢包&lt;b&gt;%1&lt;/b&gt;...</translation>
    
YES  
The provided translation is in Traditional Chinese, not in the Hakka language ('hak'). Since the task is to evaluate a 'hak' translation, this is incorrect.

A correct 'hak' translation would use Hakka vocabulary and grammar, not Mandarin or standard Chinese characters. For example, a possible Hakka translation for "Creating Wallet <b>%1</b>…" could be something like:  
「正喺建立錢包&lt;b&gt;%1&lt;/b&gt;…」  
(or a more accurate local Hakka phrasing depending on dialect).

Correct translation (example in Hakka):  
正喺建立錢包&lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Create wallet failed</source>
        <translation>創建錢包失敗&lt;br&gt;</translation>
    
YES
The translation includes an HTML line break tag "&lt;br&gt;" which is not present in the source text, making the translation inconsistent with the original format. Also, there is no extra whitespace or format specifier issue.

Correct translation:
創建錢包失敗
```

```
        <source>Can't list signers</source>
        <translation>無法列出簽名器</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Migrating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <translation>迁移钱包 &lt;b&gt;%1&lt;/b&gt;...</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>正在恢復錢包&lt;b&gt;%1&lt;/b&gt;...</translation>
    
YES
The translation contains Chinese characters ("正在恢復錢包") rather than text in the Hakka language ('hak'). Also, the ellipsis in the source is a single Unicode character (…), but in the translation it is replaced by three dots (...), which is a formatting inconsistency.

Correct translation in Hakka should be provided, preserving the format specifier and using a proper Hakka translation of "Restoring Wallet <b>%1</b>…". The ellipsis should be the single Unicode character (…).

If a correct Hakka translation is not available, indicate unknown language.
```

```
        <source>Close wallet</source>
        <translation>卸载钱包</translation>
    
YES
The translation "卸载钱包" means "uninstall wallet" which is incorrect for "Close wallet." The correct translation should convey the action of closing or shutting the wallet, not uninstalling it.

Correct translation:
关闭钱包
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>启用修剪时，如果一个钱包被卸载太久，就必须重新同步整条区块链才能再次加载它。</translation>
    
YES
The provided translation is in Chinese, not in Hakka ('hak'). It does not match the requested language code.

Correct translation in Hakka (客家话) could be:  
「當啟用剪枝功能時，錢包關閉時間過長，可能需要重新同步整個區塊鏈。」
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>跟這個地址清單關聯的地址。只有發送地址能被修改。</translation>
    
YES  
The translation provided is in Chinese (likely Hakka or a similar Chinese dialect using Chinese characters), not in the 'hak' language code context expected here. The translation itself matches the meaning accurately for Mandarin Chinese but if intended specifically for the 'hak' language, it is problematic as it uses standard Chinese characters and phrasing rather than Hakka language or transliteration.  

Correct translation would require genuine Hakka language phrasing or at least a disclaimer that Chinese is used. Since 'hak' is the language code for Hakka, the current text does not fulfill that requirement.  

Correct format assuming proper Hakka transliteration or expression is currently unavailable, so the key issue is that the translation is not actually in Hakka.  

Therefore:  
YES  
The translation is in standard Chinese, not in Hakka ('hak'). Please provide a genuine Hakka translation.
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>地址“%1”為已登記存在“%2”的地址，因此無法新增為發送地址。</translation>
    
UNK_LANG
```

```
        <source>The wallet will also be stored in this directory.</source>
        <translation>钱包也会被保存在这个目录中。</translation>
    
UNK_LANG
```

```
        <source>Welcome to %1.</source>
        <translation>歡迎來到  %1。</translation>
    
YES
There is an extra space before %1 in the translation, which should be removed to match the source formatting exactly.

Correct translation:
歡迎來到%1。
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain. It is faster to download the full chain first and prune it later. Disables some advanced features.</source>
        <translation>恢復此設定需要重新下載整個區塊鏈。 先下載完整鏈然後再修剪它的速度更快。 禁用一些高級功能。</translation>
    
YES
The translation contains improper spacing issues, such as an extra space after the first sentence and before the second sentence. Also, the phrasing "先下載完整鏈然後再修剪它的速度更快" is somewhat awkward and could be improved for clarity.

Correct translation:
恢復此設定需要重新下載整個區塊鏈。先下載完整鏈然後再修剪它會更快。禁用一些高級功能。
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>當你點擊「確認」，%1會開始下載，並從%3年最早的交易，處裡整個%4區塊鏈(大小:%2GB)</translation>
    
YES  
The provided translation is mostly accurate but has some issues:  
1. The term "process" is mistranslated as "處裡" where the correct character should be "處理" (meaning "to handle/process").   
2. The original says "%1 will begin to download and process..." but the translation "會開始下載，並從..." omits an explicit "process" verb for the entire blockchain. It should explicitly mention both "下載" and "處理".  
3. The formatting of "%2 GB" has inconsistent spacing in the translation: "大小:%2GB" should have a space between "%2" and "GB" as in the source.  
4. The original mentions "%4 block chain (%2 GB)" but the translation puts "大小:%2GB" inside parentheses but the order in Chinese typically is "整個%4區塊鏈（%2 GB大小）" to mirror the source's meaning.  
5. The punctuation differs slightly: source uses English double quotes (""), translation uses Chinese quotes「」which is acceptable in Chinese but could be kept consistent.  
6. The phrase "starting with the earliest transactions in %3 when %4 initially launched" is translated as "從%3年最早的交易", which is mostly correct but lacks "when %4 initially launched" explicitly. The original implies transaction time linked to %4's launch.  

Suggested correct translation:  
當你點擊「確認」，%1 會開始下載並處理完整的 %4 區塊鏈（%2 GB），從 %4 最初啟動時的 %3 年最早的交易開始。

This keeps all elements, maintains format specifiers and clarifies the original meaning.

Final answer:  

YES  
The translation has a typo in "處裡" (should be "處理"), missing the explicit "process" verb linked to the full blockchain, incorrect spacing with "%2GB", and lacks some nuance of the original sentence.  

Correct translation:  
當你點擊「確認」，%1 會開始下載並處理完整的 %4 區塊鏈（%2 GB），從 %4 最初啟動時的 %3 年最早的交易開始。
```

```
        <source>Form</source>
        <translation>窗体</translation>
    
YES
The translation "窗体" is Chinese (Simplified), not Hakka (hak). The user requested a translation in the 'hak' language, which refers to the Hakka language, distinct from standard Mandarin Chinese. Therefore, this translation is incorrect for the requested language.

Correct translation in Hakka (Romanized example): "Fîm" (depending on dialect and transcription system)  
Note: The exact Hakka representation may vary, but "窗体" is Mandarin Chinese and not Hakka.
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
The translation uses Traditional Chinese characters ("從剪貼簿粘貼錢包位址") rather than the Hakka language ('hak'). Although Hakka may use Chinese characters, this is clearly a Mandarin or standard Chinese translation, not Hakka specifically. Additionally, the source uses the word "address" generically, which could mean Bitcoin address or network address, while the translation specifies "錢包位址" ("wallet address"), which might be more specific than intended.  

A proper Hakka translation should use Hakka vocabulary or appropriate Romanization.

Correct translation (in Hakka Romanization, as an example):  
"從剪貼簿貼上地址"  
or, if using Chinese characters with typical Hakka phrasing, but better to have a native speaker confirm.

Since the provided translation is not in Hakka but rather standard Traditional Chinese, it is incorrect.
```

```
        <source>Main</source>
        <translation>主要(Main)</translation>
    
YES  
The translation mixes Chinese characters "主要" with the English word "Main" in parentheses, which is not correct for a proper 'hak' (Hakka) translation. A proper Hakka translation should use Hakka vocabulary or characters without mixing languages. If the intended Hakka translation for "Main" is "主", "主" can be used, but without the English word in parentheses.

Correct translation:  
<translation>主</translation>
```

```
        <source>Start %1 on system login</source>
        <translation>系统登入时启动 %1 (S)</translation>
    
YES  
The translation contains a mix of Chinese characters "系统登入时启动 %1" and the English letter "(S)", which is inconsistent for the 'hak' language and might be erroneous or not aligned with the expected 'hak' language style. Also, the placement of the placeholder %1 is correct, but adding "(S)" seems out of place and unnecessary.

A corrected translation in hak (Hakka Chinese) for "Start %1 on system login" could be:  
系统登入时启动 %1

If the "(S)" is intended as a note or shortcut indicator, it should be handled separately and not be part of the translation text directly.  

Therefore, the translation without the "(S)" is correct.  

Correct translation:  
系统登入时启动 %1
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>与%1兼容的脚本文件路径（例如 C:\Downloads\hwi.exe 或者 /Users/you/Downloads/hwi.py ）。注意：恶意软件可以偷币！</translation>
    
YES
The translation is provided in Chinese, not in the Hakka language ('hak'). Additionally, there is a minor formatting issue with a stray space before the closing parenthesis and punctuation. 

Correct translation in Chinese (if that was intended):
与%1兼容的脚本文件路径（例如 C:\Downloads\hwi.exe 或 /Users/you/Downloads/hwi.py）。注意：恶意软件可以偷币！

If a correction in the actual 'hak' language is needed, this translation does not fulfill that.
```

```
        <source>Map port using PCP or NAT-PMP</source>
        <translation>通过PCP或NAT-PMP映射端口。</translation>
    
YES
The translation is in Chinese (Simplified), not in Hakka ('hak'). Additionally, the full stop (。) at the end is unnecessary and inconsistent with typical UI string formatting. The translation also loses the original phrasing style, which is commonly kept concise without punctuation.

Correct translation in Hakka (using Latin script) would be something like:  
"Yung PCP mɔ̄ NAT-PMP pǔt khǒi"  
(Note: Since Hakka is a spoken language with multiple writing systems and not widely standardized, a precise standardized translation may vary, but it should not be in simplified Chinese characters.)
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>显示默认的SOCKS5代理是否被用于在该类型的网络下连接同伴。</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Prune block storage to</source>
        <translation>将区块存储修剪至(B)</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>警告:还原此设置需要重新下载整个区块链。</translation>
    
YES  
The provided translation is in Chinese, not in the Hakka language ('hak'). Additionally, the original source text does not contain "警告:" (Warning:), so this is an unnecessary addition and changes the meaning. The translation should be in Hakka and accurately reflect the original sentence without addition or omission.

Correct translation in Hakka (example):  
「恢復此設置需要重新下載整個區塊鏈。」  

(Note: If an accurate Hakka translation is not available, this should be noted.)
```

```
        <source>Subtract fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>默认从金额中减去交易手续费(F)</translation>
    
YES  
The provided translation includes an extraneous "(F)" at the end, which does not appear in the source text and could confuse users. Also, the translation is fully in Chinese rather than in Hakka ('hak'), which is expected here. Since 'hak' is meant to be Hakka language, the translation should be in Hakka rather than Mandarin Chinese.  

Correct translation (in Hakka, approximate):  
「預設從金額中扣除手續費」
```

```
        <source>Spend unconfirmed change</source>
        <translation>动用尚未确认的找零资金(S)</translation>
    
YES  
The translation contains Chinese characters ("动用尚未确认的找零资金") with an appended "(S)" which appears to be an extraneous annotation or placeholder and does not belong to the hak language. Without further context, this is inconsistent with the 'hak' language. Also, the original English phrase is short and concise, while the translation is longer and includes unnecessary parentheses.  

Correct translation in hak should be a proper hak language rendering of "Spend unconfirmed change" without extraneous symbols. However, as I am not familiar with hak language, I can only note that the provided text is actually Chinese with an extraneous "(S)".  

Thus, the translation is problematic due to the wrong language and extraneous characters.
```

```
        <source>Allow incoming connections</source>
        <translation>允许传入连接(G)</translation>
    
YES  
The provided translation is in Simplified Chinese ("允许传入连接(G)"), not in Hakka ('hak'). Also, the source phrase has no "(G)" suffix, which appears unnecessarily in the translation. The translation should be in Hakka language without additional or extraneous characters.

Correct translation (example in Hakka romanization):  
"允許入來連接"  
(Note: Since Hakka has multiple dialects and romanizations, the above is a plausible translation for "Allow incoming connections.")
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>最小化到托盘(M)</translation>
    
UNK_LANG
```

```
        <source>Minimize on close</source>
        <translation>单击关闭按钮时最小化(I)</translation>
    
YES  
The translation is in Simplified Chinese, not in the Hakka language ('hak'). Also, the "(I)" at the end looks like a mnemonic shortcut and might not be appropriate here without context.  

Correct translation in Hakka would be needed, but since the original translation is not in Hakka, it is problematic.  

Correct translation (example) in Hakka (using Latin script for Hakka):  
"封閉時縮小視窗"  
(Note: Actual Hakka translation depends on dialect and script used.)
```

```
        <source>User Interface language:</source>
        <translation>使用界面語言(L):</translation>
    
YES  
The translation contains Chinese characters, which likely correspond to Mandarin rather than Hakka (hak). Additionally, the "(L)" is included in the translation without a space before it, which may be acceptable stylistically but was not present in the source. The translation is not in Hakka.

Correct translation:  
Because I am not familiar enough with Hakka to produce a proper translation, no exact correction can be provided here, but the current translation is not in Hakka.
```

```
        <source>Connect to the Bitcoin network through a separate SOCKS5 proxy for Tor onion services.</source>
        <translation>连接比特币网络时专门为Tor onion服务使用另一个 SOCKS5 代理。</translation>
    
YES  
The translation is in Chinese, not in the Hakka language ('hak'). The output should be in Hakka, not Mandarin Chinese.

Correct translation in Hakka (Romanization example):  
"Tòng Tor onion dịch vụ sṳ-yung su-khí SOCKS5 proxy, lîn-bi ki-pe̍t-pì mùng-lòi Bitcoin wǎng-luò."

(Note: Accurate Hakka translations may vary depending on dialect and transcription system.)
```

```
        <source>OK</source>
        <translation>确定(O)</translation>
    
YES  
The translation is in Chinese ("确定(O)"), not in Hakka ('hak'). The text should be translated into Hakka language.  
Correct translation (Hakka) for "OK" would be simply "好" or "好嘅". If the original text includes the "(O)" as an access key indicator, it should be preserved, e.g., "好(O)".
```

```
        <source>Client will be shut down. Do you want to proceed?</source>
        <extracomment>Text asking the user to confirm if they would like to proceed with a client shutdown.</extracomment>
        <translation>客戶端軟體就要關掉了。繼續做下去嗎？</translation>
    
YES  
The language tag 'hak' refers to Hakka Chinese, which is a distinct Chinese language/dialect with its own vocabulary and grammar, different from Mandarin or Cantonese. The provided translation is in Mandarin Chinese ("客戶端軟體就要關掉了。繼續做下去嗎？"), not Hakka. Therefore, the translation does not match the specified language code.

Correct translation in Hakka (Romanized form):  
**Hin-ke-thôi ngìn-dung hiu yiu guan toi. Ngi yiu zio đến bo?**

(Note: Since Hakka has multiple dialects and no standardized written form, transliterations vary, but this represents a generally understandable form. If a Chinese character form is required, specific Hakka characters or context would need to be used.)
```

```
        <source>The configuration file is used to specify advanced user options which override GUI settings. Additionally, any command-line options will override this configuration file.</source>
        <extracomment>Explanatory text about the priority order of instructions considered by client. The order from high to low being: command-line, configuration file, GUI settings.</extracomment>
        <translation>配置文件可以用来设置高级选项。配置文件会覆盖设置界面窗口中的选项。此外，命令行会覆盖配置文件指定的选项。</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Form</source>
        <translation>窗体</translation>
    
YES
The translation "窗体" is Chinese (Simplified), not Hakka (hak). The user requested a translation in the 'hak' language, which refers to the Hakka language, distinct from standard Mandarin Chinese. Therefore, this translation is incorrect for the requested language.

Correct translation in Hakka (Romanized example): "Fîm" (depending on dialect and transcription system)  
Note: The exact Hakka representation may vary, but "窗体" is Mandarin Chinese and not Hakka.
```

```
        <source>Immature:</source>
        <translation>未成熟金額:</translation>
    
YES  
The provided translation "未成熟金額:" means "immature amount:" rather than just "Immature:". The source text only says "Immature:" as a label and does not specify "amount".  
A more accurate translation keeping the same meaning and form would be simply:  
未成熟:
```

```
        <source>Your current total balance</source>
        <translation>您当前的总余额</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>您当前在仅观察观察地址中的余额</translation>
    
YES  
The translation is redundant and awkward, as it repeats the word "观察" (observe/watch) unnecessarily, resulting in "仅观察观察地址" which is incorrect. Also, it's in Chinese rather than Hakka, and the phrase could be clearer and more concise.

A better translation (in standard Chinese, since 'hak' presumably refers to Hakka Chinese which has no standard written form distinct from Chinese characters) would be:  
您当前在仅观注地址中的余额

Note: "仅观注地址" is the standard term for "watch-only addresses" in many Chinese Bitcoin clients. If strictly in Hakka dialect, transliteration or specific vocabulary would be required, but since no standardized written form is available, this is the closest clear and correct rendering.
```

```
        <source>Mined balance in watch-only addresses that has not yet matured</source>
        <translation>仅观察地址中尚未成熟的挖矿收入余额:</translation>
    
YES
The translation is in Simplified Chinese, not in Hakka ('hak'). Additionally, the source sentence does not end with a colon, but the translation includes one, which is a format issue. The rest of the translation accurately conveys the meaning but should be in the Hakka language as requested.

Correct translation (in Hakka, transliterated approximation):
未成熟个仅观望地址挖矿余额

(Note: Since Hakka language resources are limited and vary regionally, it may be advisable to confirm with a native speaker for precise terminology.)
```

```
        <source>Privacy mode activated for the Overview tab. To unmask the values, uncheck Settings-&gt;Mask values.</source>
        <translation>“概况”标签页已启用隐私模式。要明文显示数值，请在设置中取消勾选“不明文显示数值”。</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Save…</source>
        <translation>拯救...</translation>
    
YES  
The translation "拯救..." means "rescue" or "save (someone's life)," which is not appropriate for the context of "Save…" as in saving a file or data. Also, the ellipsis in the source is the Unicode character U+2026 (…) but the translation uses three periods "...". It is better to use the proper ellipsis character.

Correct translation:  
保存…
```

```
        <source>Could not sign any more inputs.</source>
        <translation>没有交易输入项可供签名了。</translation>
    
UNK_LANG
```

```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>部分签名交易(二进制)</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>无法启动 bitcoin: 协议的“一键支付”处理程序</translation>
    
YES
The provided translation is in simplified Chinese, not in Hakka ('hak'). Additionally, the translation introduces the word "协议的" ("protocol's"), which is not present in the source text. The source simply says "click-to-pay handler," which should be translated as "一键支付处理程序" or similar, without adding "协议的."

Correct translation in Hakka should be provided in Hakka language. Since a precise Hakka translation is not provided here, but the current translation is clearly Chinese, it is problematic.

Correct translation (assuming Hakka written in Chinese characters) might be closer to:  
“無法啟動 bitcoin：一鍵支付處理程序”  
(or a valid Hakka equivalent depending on dialect).

If strictly no Hakka knowledge, simply state it is not Hakka.
```

```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>字首為 bitcoin:// 不是有效的 URI，請改用 bitcoin: 開頭。</translation>
    
UNK_LANG
```

```
        <source>Inbound</source>
        <extracomment>An Inbound Connection from a Peer.</extracomment>
        <translation>進來</translation>
    
YES
The source text "Inbound" refers to an inbound connection, which is a technical term. The provided translation "進來" means "to come in" or "coming in," which is a literal translation but may not be appropriate for technical context in 'hak' (Hakka language). A better choice might be a term that clearly indicates an incoming network connection, if such a term exists in Hakka. However, Hakka technical vocabulary is limited and often uses Mandarin terms.

A more appropriate translation would be adopting a transliteration or a more technical phrase, such as "入站" (rù zhàn) if acceptable in the dialect for "inbound," or retaining "進來" with context clarified. Given the lack of specific technical lexicon in Hakka, and that "進來" is understandable albeit simple, the translation is borderline but can be improved.

Corrected translation suggestion:
進站

(meaning "incoming station" or "inbound" in a network context)

If the translator prefers to keep it simple, '進入' (entering) might be more formal than '進來'.

But since no format specifiers or whitespace issues exist, if this is the accepted customary usage, it might be acceptable.

Therefore, the main issue is that the translation is too informal for a technical context.

Correct translation:
進站
```

```
        <source>Error encoding URI into QR Code.</source>
        <translation>把 URI 编码成二维码时发生错误。</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Hide Peers Detail</source>
        <translation>隐藏其他人的详细信息</translation>
    
YES  
The translation provided is in Simplified Chinese, not in the Hakka language ('hak'). Hence, it is incorrect for the specified language code.

A proper Hakka translation is not provided here, so a correct translation cannot be given.  
If a correct Hakka translation is needed, it should be provided by a qualified Hakka speaker or translator.
```

```
        <source>The network protocol this peer is connected through: IPv4, IPv6, Onion, I2P, or CJDNS.</source>
        <translation>这个节点是通过这种网络协议连接到的: IPv4, IPv6, Onion, I2P, 或 CJDNS.</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Elapsed time since a novel transaction accepted into our mempool was received from this peer.</source>
        <extracomment>Tooltip text for the Last Transaction field in the peer details area.</extracomment>
        <translation>來自這個節點上次成功驗證新交易進入內存池已經過的時間</translation>
    
YES  
The translation is in Chinese (Traditional), not Hakka ('hak'). Therefore, the language is incorrect for this translation. Also, the translation is somewhat condensed and changes the structure, but it captures the original meaning reasonably well.  

However, since the task is for the 'hak' language, this is a mismatch.  

Correct approach: provide the translation in Hakka, or indicate the lack of such. Since I cannot provide a Hakka translation here, the output is:  

UNK_LANG
```

```
        <source>Out:</source>
        <translation>去:</translation>
    
YES  
The translation "去:" means "go" or "to go" in Chinese, which does not accurately convey the meaning of "Out:" in the context of Bitcoin transactions (usually indicating outgoing transactions or outputs). The translation should reflect the concept of outgoing funds or outputs.

A more accurate translation in Hakka could be:  
"出:"  

So the correct translation should be:  
<translation>出:</translation>
```

```
        <source>Outbound Manual: added using RPC %1 or %2/%3 configuration options</source>
        <extracomment>Explanatory text for an outbound peer connection that was established manually through one of several methods. The numbered arguments are stand-ins for the methods available to establish manual connections.</extracomment>
        <translation>出站手动: 加入使用RPC %1 或 %2/%3 配置选项</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>v1: unencrypted, plaintext transport protocol</source>
        <extracomment>Explanatory text for v1 transport type.</extracomment>
        <translation>v1: 未加密，明文传输协议</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>1 year</source>
        <translation>1 年(Y)</translation>
    
YES  
The translation "1 年(Y)" includes the English letter "(Y)" which is unnecessary and inconsistent with the simple source text "1 year." The source simply states a duration without any added annotation. The correct translation in hak (Hakka) should simply be "1 年" without "(Y)".

Correct translation:  
1 年
```

```
        <source>Ban for</source>
        <translation>禁止連線</translation>
    
YES  
The source text "Ban for" is incomplete on its own, typically followed by a duration (e.g., "Ban for 24 hours") or reason, and it is concise. The translation "禁止連線" means "Prohibit connection" or "Ban connection" in a more complete sense but does not preserve the format or leave the phrase open-ended as in the source. Also, the source phrase implies the word "for" as a preposition needing a duration, which is omitted in the translation. 

A better translation retaining the same unfinished structure would be:  
"封鎖時間" or "封鎖於"  
but since "hak" is Hakka, a more natural Hakka phrase that matches "Ban for" (depending on dialect) could be:  
"封鎖多久" (Ban for how long) or leave as "禁止連線" only if the context is fixed.  

Without additional context, a safer, literal translation preserving "Ban for" as a phrase:  
"封鎖時間"  

Therefore:

Correct translation:  
封鎖時間
```

```
        <source>Amount:</source>
        <translation>金额(A):</translation>
    
UNK_LANG
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES  
The translation "复制和数量" means "copy and amount," which adds an unnecessary conjunction "和" ("and") not present in the source. The correct translation should simply convey "Copy amount" without "and."  

Correct translation:  
复制数量
```

```
        <source>Verify this address on e.g. a hardware wallet screen</source>
        <translation>在例如硬體錢包螢幕上驗證這個地址</translation>
    
YES  
The provided translation is in Chinese, not in the Hakka language ('hak'). The text should be translated into Hakka, which differs from standard Chinese.  

Correct translation (in Hakka romanization):  
"Zon yit li e hoh-thé chien-pòi yìn-mìn tî ke ti-tshṳ"  

(Note: Actual Hakka script or proper transliteration may vary depending on the dialect. The current text is definitely not Hakka.)
```

```
        <source>Send Coins</source>
        <translation>付款</translation>
    
YES  
The source text "Send Coins" refers specifically to sending Bitcoin or cryptocurrency coins, which is a technical action within the Bitcoin context. The provided translation "付款" means "make a payment" in Chinese, but "hak" language is a Hakka Chinese dialect, typically written using Chinese characters. However, "付款" is a generic phrase and may miss the nuance of "Send Coins" as in cryptocurrency.

If the intent is to keep it simple and clear for Hakka speakers using Chinese characters, "付款" can be acceptable, but a more precise translation related to sending coins or cryptocurrency might be clearer.

A better Hakka translation to match the technical context might be:  
"發送幣" (send coins) or "寄送金幣"

Since the provided "付款" is commonly understood and doesn't break any formatting or specifier rules, it is mostly acceptable but slightly less precise.

Correct translation suggestion:  
付款 (if a simple payment is intended)  
or  
發送幣 (to emphasize sending coins)
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>以備用手續費金額(fallbackfee)來付手續費可能會造成交易確認時間長達數小時、數天、或是永遠不會確認。請考慮自行指定金額，或是等到完全驗證區塊鏈後，再進行交易。</translation>
    
UNK_LANG
```

```
        <source>Specify a custom fee per kB (1,000 bytes) of the transaction's virtual size.

Note:  Since the fee is calculated on a per-byte basis, a fee rate of "100 satoshis per kvB" for a transaction size of 500 virtual bytes (half of 1 kvB) would ultimately yield a fee of only 50 satoshis.</source>
        <translation>指定每千字節（1,000字節）交易虛擬大小的自訂手續費。

注意：由於手續費是按每字節計算的，對於虛擬大小為500字節（半千字節）的交易，手續費率為「每千字節100聰」，最終將只收取50聰的手續費。</translation>
    
YES
The translation appears to be in Chinese rather than Hakka (hak). This is problematic because the requested language is 'hak', which is a distinct dialect/language, and the translation should be in that language rather than standard Chinese.

Correct translation in Hakka should be provided for the phrase. If unavailable, it should be stated that the translation is not in 'hak'.
```

```
        <source>(Smart fee not initialized yet. This usually takes a few blocks…)</source>
        <translation>(手續費智慧演算法還沒準備好。通常都要等幾個區塊才行...)</translation>
    
YES  
The provided translation is in Traditional Chinese, not in the 'hak' language (Hakka). It should be translated into Hakka instead.

Correct translation in Hakka (example):  
(手續費智能算法尚未初始化。通常需要等待幾個區塊…)
```

```
        <source>With Replace-By-Fee (BIP-125) you can increase a transaction's fee after it is sent. Without this, a higher fee may be recommended to compensate for increased transaction delay risk.</source>
        <translation>手续费追加（Replace-By-Fee，BIP-125）可以让你在送出交易后继续追加手续费。不用这个功能的话，建议付比较高的手续费来降低交易延迟的风险。</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Copy after fee</source>
        <translation>複製計費後金額</translation>
    
UNK_LANG
```

```
        <source>Set external signer script path in Options -&gt; Wallet</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>在 選項 -&gt; 錢包 中設定外部簽名器腳本路徑 </translation>
    
YES
The translation introduces unnecessary spaces before and after "選項 -&gt; 錢包", which is inconsistent with normal formatting and the source text where no spaces exist around the arrow symbol. Also, the translation does not preserve the format specifiers because there are none here, so that's fine.

Correct translation:
在選項 -&gt; 錢包 中設定外部簽名器腳本路徑
```

```
        <source>Partially Signed Transaction (Binary)</source>
        <extracomment>Expanded name of the binary PSBT file format. See: BIP 174.</extracomment>
        <translation>部分签名交易(二进制)</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。</translation>
    
YES
The translation has incomplete and somewhat unclear phrasing. The phrase "然後使用簽名。離線%1錢包或與PSBT相容的硬體錢包。" is awkward and incomplete, missing the object of "使用簽名" (use to sign). The meaning should be that the user can save or copy the PSBT and then sign it with, for example, an offline %1 wallet or a PSBT-compatible hardware wallet.

Correct translation:
請檢查您的交易提案。這將產生部分簽名的比特幣交易（PSBT），您可以儲存或複製該交易，然後使用例如離線%1錢包或與PSBT相容的硬體錢包進行簽名。
```

```
        <source>Not signalling Replace-By-Fee, BIP-125.</source>
        <translation>没有打上BIP-125手续费追加的标记。</translation>
    
YES  
The translation provided is in Chinese, not in the Hakka language ('hak'). Therefore, it is not a valid 'hak' translation.

Correct translation in Hakka is unavailable here; thus, the current text is incorrect for the given language code.
```

```
        <source>A fee higher than %1 is considered an absurdly high fee.</source>
        <translation>超过 %1 的手续费被视为高得离谱。</translation>
    
YES
The translation is in simplified Chinese, not in Hakka ('hak'). The language specified is Hakka, which is distinct from standard Chinese. Additionally, the format specifier "%1" is correctly placed.

Correct translation in Hakka (Romanized) could be:  
"超过 %1 ê 手续费被当作高到离谱个手续费。"

Alternatively, if a Chinese character Hakka variant is preferred:  
"過超 %1 ê 手續費係當作高到離譜个手續費。"

(Note: Since Hakka has variations, the Romanized or character form above would be appropriate.)
```

```
        <source>Amount:</source>
        <translation>金额(M)</translation>
    
YES
The translation mixes Chinese characters ("金额") with "(M)" presumably standing for "Amount." This is problematic because the language code 'hak' refers to the Hakka language, traditionally written using Chinese characters or romanization systems specific to Hakka, not with a mix of simplified Mandarin characters and an English letter in parentheses. Also, the source text simply says "Amount:" which is intended as a label, and should not include extraneous symbols or mixed-language elements.

A more appropriate translation in Hakka would be to use the Hakka term for "amount" in Chinese characters or in a recognized Hakka romanization, depending on the expected script. For example, "金額:" (pronounced "gîn-ngiap" in Hakka) is the appropriate term for "amount."

Correct translation:
金額:
```

```
        <source>Pay To:</source>
        <translation>付給(T):</translation>
    
YES
The translation uses Chinese characters and the English letter "(T)" which may not conform to the 'hak' (Hakka) language script or conventions, especially the letter in parentheses. Also, "付給" is a Mandarin phrase meaning "pay to," but Hakka may have different vocabulary or phrasing.

A more appropriate Hakka translation (written in Chinese characters) could be:
付畀：

This drops the parenthetical letter and uses "付畀" which is commonly used in Hakka to mean "pay to."

Correct translation:
付畀：
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>將支付發送到的比特幣地址給</translation>
    
YES
The translation word order and phrasing in 'hak' (Hakka) is awkward and not natural. The English text "The Bitcoin address to send the payment to" implies the address that will receive the payment. The translation "將支付發送到的比特幣地址給" literally means "the Bitcoin address to which the payment is sent" but ends with "給" (give), which is unnecessary here and makes the phrase incomplete or odd.

A more natural Hakka translation would be:
"支付予的比特幣地址"

This directly means "The Bitcoin address to which the payment is made/sent" without extra trailing words.
```

```
        <source>Subtract fee from amount</source>
        <translation>從付款金額減去手續費(U)</translation>
    
YES  
The translation contains unwanted extra characters "(U)" which do not appear in the source text. Also, "付款金額" implies "payment amount," which is slightly less accurate than "amount" (金額 or 金额). The phrase should be clear and direct without added annotations.

Correct translation:  
從金額中扣除手續費
```

```
        <source>Signatures - Sign / Verify a Message</source>
        <translation>签名 - 为消息签名/验证签名消息</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>kB/s</source>
        <translation>千字節/秒</translation>
    
YES
The language code 'hak' refers to Hakka Chinese, which typically uses Chinese characters consistent with standard Chinese; however, the translation "千字節/秒" uses the term 字節 which is more characteristic of Mandarin; Hakka would often use similar terms, but the correctness depends on the accepted terminology in Hakka. More importantly, the original text is just "kB/s" (kilobytes per second), a unit abbreviation, so it is generally better to keep technical units consistent or use a direct transliteration if there is no standard localized form.

Also, "千字節/秒" literally means "thousand bytes per second," which aligns with "kB/s," but it doesn't reflect the standard practice for units in Chinese locales, which often use "KB/s" or "千字节/秒" (simplified) or "千字節/秒" (traditional). 

Given that Hakka uses Chinese characters, the translation is reasonable but might not be necessary to translate unit abbreviations.

Correct translation:
kB/s
```

```
        <source>conflicted with a transaction with %1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that conflicts with a confirmed transaction.</extracomment>
        <translation>跟一個目前確認 %1 次的交易互相衝突</translation>
    
YES
This translation is in Traditional Chinese, not in Hakka ('hak'). The language code 'hak' refers to Hakka Chinese, which is distinct from standard Mandarin or other Chinese dialects.

Correct Hakka translation (using Latin script for example) could be:
"Túng yit koh kin-nìn %1 chhî sṳ̄-kòi kong-ngîn chhù-tung"

(Note: The exact Hakka romanization can vary; if written in Chinese characters, a suitable Hakka phrase would be required. Without that, the provided text is not in 'hak'.)
```

```
        <source>%1/unconfirmed</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents a transaction confirmed in at least one block, but less than 6 blocks.</extracomment>
        <translation>%1 次/未確認</translation>
    
YES
The provided translation "%1 次/未確認" is problematic. The original English phrase "%1/unconfirmed" likely indicates a status combining a number (%1) with the word "unconfirmed." The Chinese characters "次" typically mean "times" or "occurrences," which is not appropriate here because it's a status label, not a count of times.

Assuming the language 'hak' refers to Hakka, a Chinese language/dialect, the use of "次" is incorrect here. The translation should closely follow the source format without inserting irrelevant terms.

A better Hakka translation would be simply replacing "unconfirmed" with the Hakka equivalent and keeping "%1/" intact.

Correct translation (in Hakka Chinese) might be:

%1/未確認

Without the extra "次".

Thus, the correct translation is:

%1/未確認
```

```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>确认中 (推荐 %2个确认，已经有 %1个确认)</translation>
    
YES  
The translation is in Simplified Chinese, not in the Hakka language ('hak'). It also contains whitespace issues around parentheses, which should be consistent with the source. Additionally, the format specifiers %1 and %2 are used correctly, but the structure is different from the source, which may affect clarity.

Correct translation in Hakka should be provided. Since I cannot produce a proper Hakka translation, I can only point out the issue: the provided translation is not in Hakka.

If a proper Hakka translation is required, a possible literal version (not guaranteed perfect) might be:

确认中（推荐 %2 个确认，已有 %1 个确认）

But this is still Mandarin in Chinese characters, not Hakka.

Therefore:

UNK_LANG
```

```
        <source>Immature (%1 confirmations, will be available after %2)</source>
        <translation>未成熟 (%1 个确认，将在 %2 个后可用)</translation>
    
UNK_LANG
```

```
        <source>Received with</source>
        <translation>收款</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Received with</source>
        <translation>收款</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Copy amount</source>
        <translation>复制和数量</translation>
    
YES  
The translation "复制和数量" means "copy and amount," which adds an unnecessary conjunction "和" ("and") not present in the source. The correct translation should simply convey "Copy amount" without "and."  

Correct translation:  
复制数量
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>PSBT文件必须小于100MiB</translation>
    
YES
The translation is in Simplified Chinese, not in Hakka ('hak'). The language specified is 'hak', but the provided translation is in Chinese (zh_CN). Also, there is no space between "100" and "MiB" in source or translation which is consistent.

Correct translation in Hakka would be needed. Since I do not have verified Hakka translation data for this phrase, it should be translated accordingly in Hakka or marked as missing.
```

```
        <source>Send Coins</source>
        <translation>付款</translation>
    
YES  
The source text "Send Coins" refers specifically to sending Bitcoin or cryptocurrency coins, which is a technical action within the Bitcoin context. The provided translation "付款" means "make a payment" in Chinese, but "hak" language is a Hakka Chinese dialect, typically written using Chinese characters. However, "付款" is a generic phrase and may miss the nuance of "Send Coins" as in cryptocurrency.

If the intent is to keep it simple and clear for Hakka speakers using Chinese characters, "付款" can be acceptable, but a more precise translation related to sending coins or cryptocurrency might be clearer.

A better Hakka translation to match the technical context might be:  
"發送幣" (send coins) or "寄送金幣"

Since the provided "付款" is commonly understood and doesn't break any formatting or specifier rules, it is mostly acceptable but slightly less precise.

Correct translation suggestion:  
付款 (if a simple payment is intended)  
or  
發送幣 (to emphasize sending coins)
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>无法在不支持“拆分前的密钥池”（pre split keypool）的情况下把“非拆分HD钱包”（non HD split wallet）从版本%i升级到%i。请使用版本号%i，或者压根不要指定版本号。</translation>
    
YES
The provided translation is in Chinese, not in the Hakka language ('hak'). Therefore, it is not an appropriate translation for the language code 'hak'.

A correct translation in Hakka would need to be provided instead.
```

```
        <source>Error starting/committing db txn for wallet transactions removal process</source>
        <translation>错误：启动/提交数据库事务时出错，导致钱包交易移除过程失败。</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Error: Dumpfile identifier record is incorrect. Got "%s", expected "%s".</source>
        <translation>
錯誤：轉存檔案識別記錄不正確。獲得%s，預期
%s。</translation>
    
YES
The translation has formatting issues:
1. It contains unnecessary line breaks inside the translation, splitting the sentence awkwardly.
2. The format specifiers %s should be enclosed in quotes as in the source ("%s") to retain clarity, or otherwise clearly separated from the text.
3. There is a missing space after the first %s placeholder.
4. The translation contains extraneous newlines that cause improper rendering.

Correct translation (assuming traditional Chinese is used for 'hak'):
錯誤：轉存檔案識別記錄不正確。獲得「%s」，預期「%s」。
```

```
        <source>Invalid or corrupt peers.dat (%s). If you believe this is a bug, please report it to %s. As a workaround, you can move the file (%s) out of the way (rename, move, or delete) to have a new one created on the next start.</source>
        <translation>无效或损坏的peers.dat (%s)。如果你确信这是一个bug，请反馈到%s。作为变通办法，你可以把现有文件 (%s) 移开(重命名、移动或删除)，这样就可以在下次启动时创建一个新文件了。</translation>
    
YES
The provided translation is in Simplified Chinese, not the 'hak' language (Hakka). It does not correspond to the requested 'hak' language translation.

Correct translation in Hakka (example):
<translation>无效或损坏个peers.dat (%s)。如亲信系一个bug，请向%s报备。做一个变通法，亲可以搬走该档案(%s)（重命名、搬移或删除），下回启动时就会生一个新档案。</translation>
```

```
        <source>More than one onion bind address is provided. Using %s for the automatically created Tor onion service.</source>
        <translation>提供多數TOR路由綁定位址。 對自動建立的Tor服務用%s</translation>
    
YES
The translation contains extra spaces before the second sentence and does not fully capture the source meaning. The original mentions "More than one onion bind address is provided" and "Using %s for the automatically created Tor onion service." The given translation literally says "Providing multiple TOR routing bind addresses. Using %s for the automatically created Tor service," which is partially correct but not precise and the spacing is problematic.

Correct translation:
提供多個洋蔥绑定位址。自動建立的Tor洋蔥服務將使用%s
```

```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of pruned node)</source>
        <translation>修剪:上次同步钱包的位置已经超出（落后于）现有修剪后数据的范围。你需要进行-reindex（对于已经启用修剪节点，就需要重新下载整个区块链）</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>這是您支付的最高交易手續費（除了正常手續費外），優先於避免部分花費而不是定期選取幣。</translation>
    
YES
The translation is in Traditional Chinese and does not appear to be in the 'hak' language (Hakka). Since the language code 'hak' refers to the Hakka language, this translation is not appropriate. Also, the translation slightly changes the meaning: "partial spend avoidance" is rendered as "避免部分花費", which is acceptable, but "regular coin selection" is translated as "定期選取幣" ("regular selection of coins periodically"), which is not accurate; "regular coin selection" refers to the standard coin selection algorithm, not a periodic event.

Correct translation in Hakka is not provided here due to language constraints, but the current translation is definitely Chinese, not Hakka.

Hence, the translation is problematic because it is not in the correct language.
```

```
        <source>This is the transaction fee you may discard if change is smaller than dust at this level</source>
        <translation>找零低于当前粉尘阈值时会被舍弃，并计入手续费，这些交易手续费就是在这种情况下产生的。</translation>
    
YES  
The translation is in Chinese (zh_CN), not in Hakka ('hak'). Additionally, the original sentence states a conditional possibility ("you may discard if..."), but the translation presents this as a definite event ("会被舍弃"), changing the meaning. The format specifiers (none here) are preserved.

Correct translation in Hakka (using Latin script for clarity) should reflect the conditional and mention the transaction fee clearly, e.g.:

"若找零低于此层的粉尘阈值，您可以舍弃此找零，这就是交易手续费的费用来源。"  

(Note: Since I lack full proficiency in Hakka language, I provided a direct Chinese version that better matches the original meaning as a guide.)
```

```
        <source>Unsupported category-specific logging level %1$s=%2$s. Expected %1$s=&lt;category&gt;:&lt;loglevel&gt;. Valid categories: %3$s. Valid loglevels: %4$s.</source>
        <translation>不支持的类别限定日志等级 %1$s=%2$s 。 预期参数 %1$s=&lt;category&gt;:&lt;loglevel&gt;。 有效的类别: %3$s 。有效的日志等级: %4$s 。</translation>
    
YES
The translation contains extra spaces before punctuation marks (e.g., before the full stops "。") which is incorrect formatting. Also, the spaces around the equal signs and punctuation do not match the source style.

Correct translation:
不支持的类别限定日志等级 %1$s=%2$s。预期参数 %1$s=&lt;category&gt;:&lt;loglevel&gt;。有效的类别: %3$s。有效的日志等级: %4$s。
```

```
        <source>Wallet loaded successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future. Legacy wallets can be migrated to a descriptor wallet with migratewallet.</source>
        <translation>钱包加载成功。旧式钱包已被弃用，未来将不再支持创建或打开旧式钱包。可以使用 migratewallet 命令将旧式钱包迁移至输出描述符钱包。</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>You need to rebuild the database using -reindex to go back to unpruned mode.  This will redownload the entire blockchain</source>
        <translation>回到非修剪的模式需要用 -reindex 參數來重建資料庫。這會導致重新下載整個區塊鏈。</translation>
    
UNK_LANG
```

```
        <source>-maxmempool must be at least %d MB</source>
        <translation>參數 -maxmempool 至少要給 %d 百萬位元組(MB)</translation>
    
YES
The translation is in Traditional Chinese, not in 'hak' (Hakka) language. This does not match the requested 'hak' translation.

Correct translation in 'hak' (Hakka) should be something like:
-maxmempool 該最少係 %d MB
```

```
        <source>Cannot resolve -%s address: '%s'</source>
        <translation>沒辦法解析 -%s 參數指定的地址: '%s'</translation>
    
YES  
The translation uses Traditional Chinese characters, which are not appropriate for the 'hak' language code (Hakka). Besides, there is extra spacing around the format specifier '-%s' (" -%s "), which should be consistent with the source ("-%s") without extra spaces. Also, "參數指定的地址" means "address specified by the parameter," which is not an exact match for "address" in the original context, but it is acceptable. However, since the language requested is 'hak' (Hakka), not Chinese, this translation is not correct.

Correct translation:  
(If a correct Hakka translation were available, it should match the source without extra spacing and accurately convey the message. Since Hakka uses many Chinese characters but distinct vocabulary, the current text is definitely not fully appropriate for 'hak.')

If you need a correct rendering for Hakka (assuming it uses Chinese characters common in Hakka, but more accurate), a better translation without extra spacing would be:  
沒辦法解析-%s地址: '%s'

But since the user requested specifically 'hak' language and the sample is clearly in Chinese, the translation is problematic.
```

```
        <source>Cannot set -peerblockfilters without -blockfilterindex.</source>
        <translation>在沒有設定-blockfilterindex 則無法使用 -peerblockfilters</translation>
    
YES
The translation improperly combines Chinese characters and English options without clear separation or consistent formatting, which may cause confusion. Also, there's unnecessary spacing before "-peerblockfilters".

Correct translation:
無法在未設定 -blockfilterindex 的情況下使用 -peerblockfilters。
```

```
        <source>%s is set very high! Fees this large could be paid on a single transaction.</source>
        <translation>%s被设置得很高! 这可是一次交易就有可能付出的手续费。</translation>
    
UNK_LANG
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>%s=&lt;amount&gt;: '%s' 中指定了非法的金额 (手续费必须至少达到最小转发费率(minrelay fee) %s 以避免交易卡着发不出去)</translation>
    
YES
The provided translation is in Chinese, not in the Hakka language ('hak'). Also, it includes spaces and phrase structures typical of Mandarin Chinese rather than Hakka. Therefore, the translation is incorrect for the specified language.

A correct Hakka translation would be necessary, but since I cannot provide an accurate Hakka translation, it is best to flag this as problematic due to wrong language usage.
```

```
        <source>Outbound connections restricted to CJDNS (-onlynet=cjdns) but -cjdnsreachable is not provided</source>
        <translation>传出连接被限制为仅使用CJDNS (-onlynet=cjdns) ，但却未提供 -cjdnsreachable 参数。</translation>
    
UNK_LANG
```

```
        <source>Outbound connections restricted to Tor (-onlynet=onion) but the proxy for reaching the Tor network is not provided: none of -proxy, -onion or -listenonion is given</source>
        <translation>出站连接被限制为仅使用 Tor (-onlynet=onion)，但是未提供到达 Tor 网络的代理：没有提供 -proxy=, -onion= 或 -listenonion 参数</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Outbound connections restricted to i2p (-onlynet=i2p) but -i2psam is not provided</source>
        <translation>传出连接被限制为仅使用I2P (-onlynet=i2p) ，但却未提供 -i2psam 参数。</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>The preselected coins total amount does not cover the transaction target. Please allow other inputs to be automatically selected or include more coins manually</source>
        <translation>预先选择的币总金额不能覆盖交易目标。请允许自动选择其他输入，或者手动加入更多的币</translation>
    
UNK_LANG
```

```
        <source>Unexpected legacy entry in descriptor wallet found. Loading wallet %s

The wallet might have been tampered with or created with malicious intent.
</source>
        <translation>在描述符钱包中意料之外地找到了旧式条目。加载钱包%s

钱包可能被篡改过，或者是出于恶意而被构建的。
</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Disk space is too low!</source>
        <translation>磁盘空间太低!</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Dump file %s does not exist.</source>
        <translation>转储文件 %s 不存在</translation>
    
UNK_LANG
```

```
        <source>Error loading %s: Private keys can only be disabled during creation</source>
        <translation>載入 %s 時發生錯誤: 只有在造新錢包時能夠指定不允許私鑰</translation>
    
UNK_LANG
```

```
        <source>Error loading %s: Wallet requires newer version of %s</source>
        <translation>載入檔案 %s 時發生錯誤: 這個錢包需要新版的 %s</translation>
    
YES  
The provided translation is in Traditional Chinese rather than the Hakka language ('hak'). It does not match the requested language code and thus is erroneous in this context.

Correct translation:  
(Not provided here as the Hakka language translation is not available.)
```

```
        <source>Error: Dumpfile checksum does not match. Computed %s, expected %s</source>
        <translation>錯誤：轉存檔案的校驗和不匹配。%s計算得%s</translation>
    
YES  
The translation is incomplete and omits part of the source text. The source states that the computed checksum and expected checksum are %s and %s respectively, but the translation only says "%s計算得%s" ("%s computed as %s") and misses the expected checksum part. Also, the order and format specifiers should be preserved.

Correct translation:  
錯誤：轉存檔案的校驗和不匹配。計算得%s，預期%s
```

```
        <source>Error: Keypool ran out, please call keypoolrefill first</source>
        <translation>錯誤：keypool已用完，請先重新呼叫keypoolrefill</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Error: Unable to parse version %u as a uint32_t</source>
        <translation>错误：无法把版本号%u作为unit32_t解析</translation>
    
YES
The translation uses Simplified Chinese characters, which does not correspond to the Hakka ('hak') language. Additionally, the technical term "uint32_t" is misspelled as "unit32_t" in the translation. The expected format specifier %u is correctly preserved.

Correct translation (in Hakka would be ideal, but since it's unavailable, a correct Chinese translation is):
错误：无法把版本号%u作为uint32_t解析
```

```
        <source>Error: Unable to write data to disk for wallet %s</source>
        <translation>错误：无法将数据写入钱包的磁盘%s。</translation>
    
YES  
The translation provided is in Simplified Chinese, not in the Hakka language ('hak'). Additionally, the placement of "%s" at the end of the sentence is incorrect; it should replace the wallet placeholder exactly as in the source sentence. The original English sentence:  
"Error: Unable to write data to disk for wallet %s"  
Correct placement of "%s" would be after "wallet" without additional or misplaced characters.

A correct Hakka translation should be provided. Since I do not have a verified Hakka translation, the Chinese correction would be:  
错误：无法将数据写入钱包 %s 的磁盘。  

But since this is supposed to be 'hak' (Hakka) and the provided translation is Chinese, it is incorrect.
```

```
        <source>Failure removing transaction: %s</source>
        <translation>%s删除交易时失败: </translation>
    
YES  
The translation incorrectly positions the placeholder %s and inserts a trailing colon with a space, which differs from the English source. Also, the word order is awkward and does not clearly convey the failure in removing the transaction.

Correct translation:  
交易删除失败: %s
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>手续费率 (%s) 低于最大手续费率设置 (%s)</translation>
    
YES  
The translation incorrectly states "低于最大手续费率设置" which means "lower than the maximum fee rate setting" instead of the "minimum fee rate setting" as in the source text. This is inaccurate and changes the meaning.

Correct translation:  
手续费率 (%s) 低于最小手续费率设置 (%s)
```

```
        <source>Invalid -onion address or hostname: '%s'</source>
        <translation>无效的 -onion 地址: '%s'</translation>
    
YES
The translation omits the "or hostname" part from the source, which is important for accuracy.

Correct translation:
无效的 -onion 地址或主机名: '%s'
```

```
        <source>Invalid -proxy address or hostname: '%s'</source>
        <translation>無效的 -proxy 地址或主機名稱: '%s'</translation>
    
YES  
The translation is in Chinese (Traditional) and not in Hakka. Additionally, the format is correct but the language does not match the requested 'hak'.  

Correct Hakka translation (using Latin script for Hakka):  
"Giam5-ngiem2 e -proxy zie5-zi3 ngit1 sa2: '%s'"  

(Note: If a more precise romanization or script translation is available, that should be used; otherwise, this exposes the mismatch.)
```

```
        <source>Invalid P2P permission: '%s'</source>
        <translation>无效的 P2P 权限：'%s'</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least %s)</source>
        <translation>%s=&lt;amount&gt;: '%s' 中指定了非法的金额 (必须至少达到 %s)</translation>
    
YES
The translation is in Chinese and not in the Hakka language ('hak'). Additionally, the original format specifiers (%s) are not preserved exactly in order and syntax, which could cause issues in string formatting. The whole phrase "Invalid amount for %s=<amount>: '%s' (must be at least %s)" should be translated with all %s specifiers correctly placed.

Correct translation in proper format (assuming Hakka were used, but here is a Chinese example maintaining %s placeholders accurately):

%s=&lt;amount&gt;: '%s' 为非法金额（必须至少为 %s）

However, since this is supposed to be Hakka ('hak') language and this is a Chinese sentence, the translation is incorrect for the language specified.
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s'</source>
        <translation>%s=&lt;amount&gt;: '%s' 中指定了非法的金额</translation>
    
YES
The translation does not correctly mirror the source's structure and is incomplete. The source explicitly states "Invalid amount for %s=<amount>: '%s'", indicating an error with the amount specified for a given parameter. The translation places the parameter and amount at the start but omits the initial context of "Invalid amount for", and changes the syntax and meaning.

Correct translation:
%s=&lt;amount&gt;指定的金额无效：'%s'
```

```
        <source>Not found pre-selected input %s</source>
        <translation>找不到预先选择输入%s</translation>
    
YES  
The provided translation is in Simplified Chinese, not in the Hakka language ('hak').  
Correct Hakka translation (example):  
"毋着預先揀定个輸入%s"
```

```
        <source>Not solvable pre-selected input %s</source>
        <translation>无法求解的预先选择输入%s</translation>
    
YES  
The translation is in simplified Chinese, not in Hakka language (hak).  
Correct translation (Hakka):  
Unable to provide an accurate Hakka translation due to lack of data, but the current translation is definitely not in Hakka.
```

```
        <source>Prune mode is incompatible with -txindex.</source>
        <translation>修剪模式和 -txindex 參數不相容。</translation>
    
YES  
The translation appears to be in Chinese (Traditional) rather than Hakka ('hak'). Therefore, it is language-mismatched.  
Correct Hakka translation (Romanization, using standardized Latin script) would be something like:  
"剪枝模式毋相容 with -txindex。"  
(Note: Since the user did not provide a standard Hakka orthography, this is a best effort based on known Hakka vocabulary.)
```

```
        <source>Specified -walletdir "%s" is a relative path</source>
        <translation>以 -walletdir 指定的路徑 "%s" 是相對路徑</translation>
    
YES
The translation is in Chinese, not in Hakka (hak). Also, it includes unnecessary spaces and does not reflect the Hakka language requested.

A proper Hakka translation should be in the Hakka dialect, which differs significantly from Mandarin or standard Chinese.

Correct translation in Hakka (Romanized) might be:
- -walletdir "%s" 指定个路径是相对路径

Therefore:
<walletdir "%s" 指定个路径是相对路径>

If only Chinese is available, indicate language mismatch.

Since it is not Hakka, the correct response is YES with explanation.
```

```
        <source>Transaction amounts must not be negative</source>
        <translation>交易金额不不可为负数</translation>
    
YES  
The translation contains a double negation "不不可" which is incorrect. The phrase should only have a single negation "不可" or "不得" to convey "must not be".  

Correct translation:  
交易金额不可为负数
```

```
        <source>Transaction change output index out of range</source>
        <translation>交易尋找零輸出項超出範圍</translation>
    
YES  
The translation uses Traditional Chinese characters and phrases ("交易尋找零輸出項超出範圍") rather than Hakka ('hak'). It is not a correct translation into Hakka language. Also, the phrase "尋找零輸出項" ("search zero output item") does not accurately reflect "change output index." The correct Hakka translation should clearly convey:

"Transaction change output index out of range"  
A correct Hakka translation would be (using romanized Hakka and traditional characters):

"交易找返來嘅零用輸出索引超出範圍"

Or in Chinese characters commonly used in Hakka:

"交易找返來的零用輸出索引超出範圍"

This translates to roughly: "Transaction's change output index out of range."

If a pure Hakka script is unavailable, at least the translation should be in Hakka rather than standard Chinese.
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>交易需要一个找零地址，但是我们无法生成它。</translation>
    
YES  
The translation is in Simplified Chinese, not the Hakka language ('hak').  
Correct 'hak' translation (in Romanized Hakka) might be:  
"交易愛一個找零地址，毋過我哋無法產生佢。"
```

```
        <source>Unable to create the PID file '%s': %s</source>
        <translation>無法創建PID文件'%s': %s</translation>
    
YES  
The translation is mostly correct in meaning, but the language used is Traditional Chinese ("無法創建PID文件'%s': %s"), not Hakka ('hak'). Additionally, there is no space after the colon in the translation, consistent with the source, which is acceptable in Chinese punctuation style.

Correct translation in Hakka (Romanized) should be provided if possible, e.g.:  
"無法創建 PID 檔案 '%s': %s" (if in Hakka) or alternatively a proper Hakka phrase (if known).

Since the translation is not in Hakka, it is problematic.

Correct translation in Hakka (example, based on available resources) might be:  
"獨無能力創建 PID 档案 '%s': %s"

But if proper Hakka is unavailable, the translator should provide a correct Hakka translation.

Hence, the current translation is erroneous for the requested language.
```

```
        <source>Unknown -blockfilterindex value %s.</source>
        <translation>未知的 -blockfilterindex 数值 %s。</translation>
    
UNK_LANG, not familiar with the Hakka language 'hak'.
```

```
        <source>Wallet file creation failed: %s</source>
        <translation>钱包文件创建失败：1%s</translation>
    
YES  
The translation incorrectly includes a '1' before the format specifier '%s'. The '1' is not present in the source and should be removed to match the original meaning and formatting.  

Correct translation:  
钱包文件创建失败：%s
```

```
        <source>User Agent comment (%s) contains unsafe characters.</source>
        <translation>用户代理备注(%s)包含不安全的字符。</translation>
    
UNK_LANG
```

```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>錢包需要重寫: 請重新啓動 %s 來完成</translation>
    
YES  
The source language is English and the target language is 'hak' (Hakka). The provided translation is in Traditional Chinese characters, which is not the Hakka language but rather Mandarin Chinese or a related Sinitic language form. This is inaccurate for a 'hak' translation.

Correct 'hak' translation (using Romanized Hakka) could be:  
"Chînpòi sūyiau chhòng sṳ: chhóngfuk %s loi wànchhṳn"  

(Note: The exact orthography can vary due to dialectal forms and romanization standards, but it should not be in standard Chinese characters alone.)
```
</details>
