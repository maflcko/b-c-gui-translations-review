# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ja</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bja%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation> 
右クリックしてアドレスまたはラベルを編集します。</translation>
    
YES  
The translation has an unnecessary leading whitespace character before the text. Also, the translation uses a polite form "編集します" (will edit), which is somewhat unnatural in instructional contexts. A more appropriate and concise imperative form would be better.

Correct translation:  
右クリックしてアドレスまたはラベルを編集する
```

```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>これらは、あなたが知っている送信先の Bitcoin アドレスです。コインを送る前に必ず、金額と受取用アドレスを確認してください。</translation>
    
YES  
The translation is somewhat inaccurate and could be misleading in the Bitcoin context. The source says: "These are your Bitcoin addresses for sending payments," which means the addresses belong to the user (their own Bitcoin addresses used to send payments). However, the Japanese translation says "これらは、あなたが知っている送信先の Bitcoin アドレスです," which translates back to "These are Bitcoin addresses of the destinations you know," implying these are recipients' addresses, not the user's own addresses.

A more accurate translation would preserve that these are *your own* Bitcoin addresses used to send payments, not just addresses you know or target addresses.

Correct translation:  
これらは、支払い送信用のあなたの Bitcoin アドレスです。コインを送る前に必ず、金額と受取先のアドレスを確認してください。
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>取引履歴を %1 へ保存する際にエラーが発生しました。再試行してください。</translation>
    
YES
The original English text refers specifically to "the address list," but the Japanese translation says "取引履歴" (transaction history), which is incorrect and changes the meaning. The translation should reference the address list instead.

Correct translation:
アドレス一覧を %1 に保存しようとしたときにエラーが発生しました。再度お試しください。
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>内部エラーが発生。 %1 は安全な継続をトライ中。これは予期せぬバグであり、次に説明するようにリポートできます。</translation>
    
YES  
The translation has minor spacing issues around the placeholder (%1) and could be more natural in Japanese. Specifically, there should be no space before %1, and "安全な継続をトライ中" sounds unnatural; a better phrasing would be "安全に続行しようとします" which directly reflects "will attempt to continue safely." Also, "リポート" is a loanword but "報告" is more common in formal contexts.

Correct translation:  
内部エラーが発生しました。%1 は安全に続行しようとします。これは予期せぬバグであり、以下に示す方法で報告できます。
```

```
        <source>Minimize</source>
        <translation>最小化 M</translation>
    
YES  
The translation "最小化 M" includes an unnecessary "M" at the end, which is not present in the source text "Minimize" and could confuse users. The correct Japanese translation for "Minimize" in the context of UI buttons is simply:  
最小化
```

```
        <source>Received with label</source>
        <translation>対応するラベル</translation>
    
YES  
The translation "対応するラベル" means "corresponding label," which does not convey the same meaning as "Received with label." The source phrase indicates an action or status related to receiving something associated with a label, likely referring to a transaction or payment received that has a label attached. A more accurate translation would clearly express this context.

Correct translation:  
ラベル付きで受信
```

```
        <source>Received with address</source>
        <translation>対応するアドレス</translation>
    
YES  
The translation "対応するアドレス" means "corresponding address" or "associated address," which does not convey the meaning of "Received with address." The original English phrase likely implies "Received [funds/messages] with the address," indicating an action or status involving receipt associated with a specific address. A more accurate translation would be:  
受信したアドレスで
```

```
        <source>Lock unspent</source>
        <translation>コインをロック(o)</translation>
    
YES  
The translation "コインをロック(o)" includes an extraneous "(o)" which is not present in the source and appears to be an error or leftover artifact. Also, "Lock unspent" specifically refers to locking unspent outputs (UTXOs) rather than just "coins," so a more accurate and natural translation would be:

未使用の出力をロックする

Or, more concisely:

未使用分をロック

If brevity is preferred and "unspent" is understood in context, "未使用分をロック" is acceptable. The key is removing "(o)" and ensuring clarity regarding the "unspent" term.
```

```
        <source>Unlock unspent</source>
        <translation>コインをアンロック(U)</translation>
    
YES  
The source text "Unlock unspent" refers to unlocking unspent transaction outputs, not simply "coin". The translation "コインをアンロック(U)" literally means "Unlock coin (U)", which is inaccurate and introduces unnecessary English within parentheses. A better translation that respects the Bitcoin context and omits extraneous characters would be:

未使用の出力をロック解除
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>外部署名のサポート(外部署名に必要)なしでコンパイルされています </translation>
    
YES  
The translation contains extra trailing whitespace and the wording can be improved for clarity and naturalness. The phrase "外部署名のサポート" is understandable but "外部署名" is more natural. Also, the phrase in parentheses is slightly unclear and should be more precise like "外部署名に必要な". The trailing space at the end should be removed.

Correct translation:  
外部署名のサポート（外部署名に必要）なしでコンパイルされています
```

```
        <source>Limit block chain storage to</source>
        <translation>ブロックチェーンのストレージを次に限定する: </translation>
    
YES  
The translation includes unnecessary trailing whitespace before the colon, which is inconsistent with typical Japanese punctuation spacing (no space before a colon). Also, the phrase "次に限定する" is somewhat unnatural and overly literal for this context. A more natural translation would be without the trailing space and with a clearer phrasing:

Correct translation:  
ブロックチェーンのストレージを次のサイズに制限する:
```

```
        <source>Prune block storage to</source>
        <translation>ブロックの保存容量を次の値までに剪定する(b): </translation>
    
YES
The translation unnecessarily includes "(b): " at the end, which does not appear in the source text and looks like extraneous content that could confuse users. Additionally, the phrase is slightly awkward and could be more concise.

Correct translation:
ブロックの保存容量を次の値までに削減する
```

```
        <source>External signer script path</source>
        <translation>HWIのパス(E)</translation>
    
YES
The translation does not accurately reflect the original English text. The source text "External signer script path" refers to the file path of an external signing script, whereas the translation "HWIのパス(E)" specifically refers to "Path of HWI (E)", which is a particular tool (Hardware Wallet Interface) and adds an unexplained "(E)". This is too narrow and adds unclear information.

A better translation is:
外部署名者スクリプトのパス
```

```
        <source>Connect through SOCKS5 proxy (default proxy):</source>
        <translation>SOCKS5 プロキシ経由で接続する（デフォルトプロキシ）(C):</translation>
    
YES  
The translation incorrectly includes "(C)" at the end, which is not present in the source and seems extraneous. Also, "（デフォルトプロキシ）" should ideally include "（デフォルトのプロキシ）" to sound more natural in Japanese.  

Correct translation:  
SOCKS5 プロキシ経由で接続する（デフォルトのプロキシ）：
```

```
        <source>Use separate SOCKS5 proxy to reach peers via Tor onion services:</source>
        <translation>Tor onion serviceを介してピアに到達するために別のSOCKS5プロキシを使用する(5):</translation>
    
YES  
The translation has an erroneous "(5)" at the end, which does not correspond to anything in the source and looks like a typo or misplaced character. Also, "onion service" is better translated as "オニオンサービス" or kept as "onionサービス" for clarity in the Japanese Bitcoin context. The phrase can be improved for naturalness and clarity.  

Correct translation:  
Torオニオンサービスを介してピアに接続するために、別のSOCKS5プロキシを使用する:
```

```
        <source>1 day</source>
        <translation>1 日(a)</translation>
    
YES  
The translation includes an extraneous "(a)" which is not present in the source and is unnecessary. The correct and natural Japanese translation for "1 day" is simply "1日". The extra characters could confuse users.

Correct translation:  
1日
```

```
        <source>1 week</source>
        <translation>1 週間(w)</translation>
    
YES  
The translation contains an unnecessary space between the number and the unit and includes an unexplained "(w)" which is not present in the source. The correct translation should simply be:

1週間
```

```
        <source>1 year</source>
        <translation>1 年(y)</translation>
    
YES  
The translation adds an unnecessary "(y)" which does not appear in the source and is uncommon in Japanese date expressions. The correct Japanese simply uses "1年" without parenthetical notation.  

Correct translation:  
1年
```

```
        <source>From</source>
        <translation>内向き</translation>
    
YES  
The English word "From" in the context of Bitcoin transactions typically refers to the source or origin of funds or addresses. The given Japanese translation "内向き" literally means "inward-facing" or "inward," which is not an appropriate or natural translation for "From" in this context. A more accurate and commonly used translation for "From" (e.g., as in "From address") in Bitcoin or transaction contexts would be simply "差出人" (sender), "送信元" (sending source), or just "送信元" to denote "From."

Correct translation:  
送信元
```

```
        <source>Set external signer script path in Options -&gt; Wallet</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>設定-&gt;オプション-&gt;ウォレット タブにHWIのパスを設定してください</translation>
    
YES  
The translation shifts the order and meaning compared to the source. The source is "Set external signer script path in Options -> Wallet", indicating navigation to the "Options" menu, then the "Wallet" tab, to set the external signer script path. The translation rearranges the navigation as "設定 -> オプション -> ウォレット" and specifically says "タブにHWIのパスを設定してください" ("Please set the HWI path in the tab"), which adds the specific "HWI" (Hardware Wallet Interface) and "please" that are not present in the source. "External signer script path" is translated as "HWIのパス" which is more specific and not necessarily correct.

A more accurate translation would preserve the original structure and terminology:

Correct translation:  
設定 -> オプション -> ウォレット で外部署名者のスクリプトパスを設定してください

Alternatively, if the imperative "設定してください" is too strong or unnecessary (because the English is a command or an instruction), one could say:

設定 -> オプション -> ウォレット で外部署名者のスクリプトパスを設定する

But typically in UI instructions, "してください" is acceptable.

Also, the order in the original is "Options -> Wallet", whereas the translation says "設定 -> オプション -> ウォレット", adding an extra "設定" layer.

If "設定" corresponds to "Settings" and "Options" is "オプション", then the navigation in the original might mean "Options" menu, then "Wallet" tab. Adding "設定" could be redundant or confusing.

Hence, the minimal correction is:

オプション -> ウォレット で外部署名者のスクリプトパスを設定してください

If the top menu is "Options" (オプション) and inside that is a "Wallet" tab (ウォレット), this matches the source.

Therefore, the final corrected translation:

オプション -> ウォレット で外部署名者のスクリプトパスを設定してください
```

```
        <source>%1 to %2</source>
        <translation>%1 送金先: %2</translation>
    
YES  
The source text "%1 to %2" is a neutral expression typically indicating a connection or a range, for example, "from %1 to %2". The translation "%1 送金先: %2" adds extra meaning by explicitly saying "sending destination" (送金先), which is not present in the source and may be misleading or too specific.

A more accurate and neutral translation should preserve the simplicity and placeholder structure without adding extra terms:

Correct translation:  
%1 から %2 へ
```

```
        <source>External signer failure</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>HWIのエラー</translation>
    
YES  
The translation "HWIのエラー" specifically refers to an error involving HWI (Hardware Wallet Interface), which is a specific external signer tool, but the source text "External signer failure" is more general and not limited to HWI. It means any external signing device or mechanism, such as various hardware wallets or signing tools, not just HWI.

A more accurate and general translation would be:  
外部署名者の失敗

Or to maintain a natural expression:  
外部署名機のエラー

Both convey a failure related to an external signing device without limiting to HWI specifically.
```

```
        <source>abandoned</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an abandoned transaction.</extracomment>
        <translation>取消しされました</translation>
    
YES  
The translation "取消しされました" is grammatically incorrect and unnatural in Japanese. The proper form for "abandoned" in the context of a transaction status would be "破棄されました" or simply "放棄されました," both meaning "has been abandoned" or "discarded."  

Correct translation:  
破棄されました
```

```
        <source>Generated</source>
        <translation>採掘</translation>
    
YES
The English word "Generated" in the context of Bitcoin typically refers to blocks or coins that have been created, not specifically "mined" in a direct translation sense. The Japanese translation "採掘" means "mining" (literally "mining" or "excavation") and is more specific to the act of mining rather than the broader or passive sense of "generated." A more accurate and neutral translation for "Generated" would be "生成済み" or simply "生成," which means "generated" or "created."

Correct translation:
生成
```

```
        <source>From</source>
        <translation>内向き</translation>
    
YES  
The English word "From" in the context of Bitcoin transactions typically refers to the source or origin of funds or addresses. The given Japanese translation "内向き" literally means "inward-facing" or "inward," which is not an appropriate or natural translation for "From" in this context. A more accurate and commonly used translation for "From" (e.g., as in "From address") in Bitcoin or transaction contexts would be simply "差出人" (sender), "送信元" (sending source), or just "送信元" to denote "From."

Correct translation:  
送信元
```

```
        <source>Received with</source>
        <translation>受取(通常)</translation>
    
YES  
The English source "Received with" is an incomplete phrase generally used as a prefix followed by a payment method or address label in the context of Bitcoin. The provided translation "受取(通常)" translates back roughly as "Receipt (normal)" which adds a qualifier "normal" (通常) not present in the source, thus altering the meaning inaccurately. Moreover, the phrase "Received with" should be simply translated to something like "～で受取" or "受取済み" depending on context.

A more neutral and accurate translation would be:  
"～で受取" (if used as a prefix before the payment method)  
or simply  
"受取"  

If more context is known, for example, if it's "Received with label", then "～で受取" is suitable.

Correct translation:  
受取済み   (Received)  
or  
～で受取   (Received with ～)  

Since the original phrase likely expects a following label, "受取済み" or "～で受取" fits better than the provided translation.
```

```
        <source>Received from</source>
        <translation>受取(その他)</translation>
    
YES  
The translation "受取(その他)" means "Received (others)" which adds "(others)" not present in the source "Received from". The source is likely a phrase used to indicate the sender or origin (e.g., "Received from [someone]"). A more accurate and natural translation would be "から受信" or "受取元" depending on context. Since "受取元" is a common phrase meaning "sender" or "origin of receipt," it fits well.

Correct translation:  
受取元
```

```
        <source>Received with</source>
        <translation>受取(通常)</translation>
    
YES  
The English source "Received with" is an incomplete phrase generally used as a prefix followed by a payment method or address label in the context of Bitcoin. The provided translation "受取(通常)" translates back roughly as "Receipt (normal)" which adds a qualifier "normal" (通常) not present in the source, thus altering the meaning inaccurately. Moreover, the phrase "Received with" should be simply translated to something like "～で受取" or "受取済み" depending on context.

A more neutral and accurate translation would be:  
"～で受取" (if used as a prefix before the payment method)  
or simply  
"受取"  

If more context is known, for example, if it's "Received with label", then "～で受取" is suitable.

Correct translation:  
受取済み   (Received)  
or  
～で受取   (Received with ～)  

Since the original phrase likely expects a following label, "受取済み" or "～で受取" fits better than the provided translation.
```

```
        <source>Increase transaction fee</source>
        <translation>取引手数料を追加(f)</translation>
    
YES  
The Japanese translation "取引手数料を追加(f)" is problematic. The "(f)" at the end is likely unintended or wrongly included and does not make sense in Japanese. Additionally, "追加" means "add" or "additionally," which may be understandable but is less natural in this context. A more precise and natural translation for "Increase transaction fee" would be:

取引手数料を増やす
```

```
        <source>Prune mode is incompatible with -reindex-chainstate. Use full -reindex instead.</source>
        <translation>剪定モードは -reindex-chainstate と互換性がありません。代わりに完全な再インデックス -reindex を使用してください。</translation>
    
YES
The translation contains an unnecessary and incorrect Chinese word "剪定" at the start, which is not Japanese. The correct Japanese term for "prune mode" in this context would be "プルーンモード" or simply "pruneモード" as used commonly in Bitcoin Japanese documentation.

Correct translation:
プルーンモードは -reindex-chainstate と互換性がありません。代わりに完全な再インデックス -reindex を使用してください。
```

```
        <source>Wallet loaded successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future. Legacy wallets can be migrated to a descriptor wallet with migratewallet.</source>
        <translation>ウォレットが正常にロードされました。 レガシーウォレットタイプは非推奨となり、レガシーウォレットの作成と使用のサポートは将来削除される予定です。 レガシーウォレットは、「mergewallet」を使用してディスクリプターウォレットに移行できます。</translation>
    
YES
The translation incorrectly uses "mergewallet" instead of "migratewallet," which is the correct command/tool name from the source. Also, there is a leading space after each sentence period that should be removed for proper spacing.

Correct translation:
ウォレットが正常にロードされました。レガシーウォレットタイプは非推奨となり、レガシーウォレットの作成と使用のサポートは将来削除される予定です。レガシーウォレットは、「migratewallet」を使用してディスクリプターウォレットに移行できます。
```

```
        <source>Maximum transaction weight is less than transaction weight without inputs</source>
        <translation>最大トランザクションweightがインプットのないトランザクションweightよりも小さい</translation>
    
YES  
The translation uses the English word "weight" instead of the appropriate Japanese word, which is inconsistent and less natural for Japanese readers. Also, "インプット" is better replaced with the commonly used Japanese term "入力". Finally, the sentence lacks proper particles and a natural Japanese sentence flow.

Correct translation:  
最大トランザクションの重みは、入力のないトランザクションの重みよりも小さい
```

```
        <source>Maximum transaction weight must be between %d and %d</source>
        <translation>最大トランザクションweightは%dから%dの間でなければなりません。</translation>
    
YES  
The word "weight" should be translated into Japanese for consistency and clarity, rather than left in English. A natural and clear translation would be:

最大トランザクションの重みは%dから%dの間でなければなりません。
```

```
        <source>Unknown change type '%s'</source>
        <translation>不明なお釣りのアドレス形式 '%s' </translation>
    
YES  
The translation incorrectly interprets "change type" as "お釣りのアドレス形式" ("change address format"), which is too specific and changes the meaning. The original refers to an unknown *type* of change (typically the change in a Bitcoin transaction), not specifically an "address format." Also, there is an unnecessary trailing space before the closing quotation mark in Japanese.

Correct translation:  
不明なお釣りの種類 '%s'
```
</details>
