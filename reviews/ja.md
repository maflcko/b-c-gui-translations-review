# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ja</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bja%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation> 
右クリックしてアドレスまたはラベルを編集します。</translation>
    
YES, There is a leading space in the translation.
右クリックしてアドレスまたはラベルを編集します。
```

```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>これらは、あなたが知っている送信先の Bitcoin アドレスです。コインを送る前に必ず、金額と受取用アドレスを確認してください。</translation>
    
YES. The translation is problematic because it uses "あなたが知っている" (anata ga shitte iru), which means "that you know" or "that you are aware of." This phrasing is awkward and doesn't accurately convey the meaning of "your" Bitcoin addresses. It implies that the addresses are only known to the user, rather than belonging to them.

Here's a corrected translation:

<source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
<translation>これらは、支払いを送信するためのあなたの Bitcoin アドレスです。コインを送る前に、必ず金額と受取用アドレスを確認してください。</translation>
```

```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>取引履歴を %1 へ保存する際にエラーが発生しました。再試行してください。</translation>
    
YES - The translation incorrectly uses "取引履歴" (transaction history) instead of "アドレスリスト" (address list).
取引履歴を %1 へ保存する際にエラーが発生しました。再試行してください。
Correct translation: アドレスリストを %1 に保存しようとした際にエラーが発生しました。もう一度お試しください。
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>内部エラーが発生。 %1 は安全な継続をトライ中。これは予期せぬバグであり、次に説明するようにリポートできます。</translation>
    
YES, The word "トライ中" is too casual for a formal context like an error message. The word "試行中" would be more appropriate.
内部エラーが発生しました。%1 は安全な継続を試行中です。これは予期せぬバグであり、次に説明するように報告できます。
```

```
        <source>Minimize</source>
        <translation>最小化 M</translation>
    
YES, the translation is problematic. The Japanese translation includes an English letter "M" which is not present in the source text and makes the translation erroneous.

The correct translation should be:
最小化
```

```
        <source>Received with label</source>
        <translation>対応するラベル</translation>
    
YES, the translation is not accurate. The English phrase "Received with label" refers to receiving something that has been associated with a specific label. The Japanese translation "対応するラベル" means "corresponding label," which does not convey the same meaning.

A more accurate translation would be:

<translation>ラベル付きで受信</translation>
```

```
        <source>Received with address</source>
        <translation>対応するアドレス</translation>
    
YES, The translation is not accurate and does not convey the meaning of the source text. The source text "Received with address" implies that something was received at a specific address, whereas the translation "対応するアドレス" which means "corresponding address" does not carry this meaning.

The correct translation should be "アドレスで受信しました" or "アドレス宛に受信しました".

NO
```

```
        <source>Lock unspent</source>
        <translation>コインをロック(o)</translation>
    
YES, The translation is problematic because "コインをロック(o)" is a very literal and awkward translation of "Lock unspent". The "(o)" is also unnecessary and appears to be an artifact of the translation process or a typo. A more natural and accurate translation for "Lock unspent" in the context of Bitcoin would be "未使用トランザクションのロック" (Mishiyō toranzakushon no rokku) which means "Locking unspent transactions".

NO
```

```
        <source>Unlock unspent</source>
        <translation>コインをアンロック(U)</translation>
    
YES, The translation is not accurate. The word "unspent" refers to unspent transaction outputs (UTXOs) in Bitcoin. The translation provided, "コインをアンロック(U)", translates to "Unlock coins(U)" which is too general and doesn't accurately convey the specific Bitcoin terminology.

Correct translation: 未使用コインのアンロック
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>外部署名のサポート(外部署名に必要)なしでコンパイルされています </translation>
    
YES, The translation uses full-width spaces which is not standard in Japanese. It also uses a full-width parenthesis which should be half-width. 
外部署名のサポート（外部署名に必要）なしでコンパイルされています。
```

```
        <source>Limit block chain storage to</source>
        <translation>ブロックチェーンのストレージを次に限定する: </translation>
    
YES, The Japanese translation is unnatural. A more natural translation would be: ブロックチェーンのストレージを～に制限する
```

```
        <source>Prune block storage to</source>
        <translation>ブロックの保存容量を次の値までに剪定する(b): </translation>
    
YES, The translation uses an unnatural phrasing for the English source. The intended meaning of "Prune block storage to" in the context of Bitcoin is to reduce the storage size of the blockchain.

A more natural and accurate translation would be:

ブロックの保存容量を (b) まで削減する
```

```
        <source>External signer script path</source>
        <translation>HWIのパス(E)</translation>
    
YES, The translation is inaccurate. The Japanese translation "HWIのパス(E)" literally translates to "HWI's path (E)". The English source text "External signer script path" refers to the path of a script used by an external signer. "HWI" is likely an abbreviation for "Hardware Wallet Interface" which is a tool used for interacting with hardware wallets. While this might be related to external signing, the translation is not a direct or accurate representation of the original meaning.

A more accurate translation would be:
外部署名スクリプトパス
```

```
        <source>Connect through SOCKS5 proxy (default proxy):</source>
        <translation>SOCKS5 プロキシ経由で接続する（デフォルトプロキシ）(C):</translation>
    
YES
The translation adds an unnecessary "(C)" at the end which is not present in the source text.

SOCKS5 プロキシ経由で接続する（デフォルトプロキシ）:
```

```
        <source>Use separate SOCKS5 proxy to reach peers via Tor onion services:</source>
        <translation>Tor onion serviceを介してピアに到達するために別のSOCKS5プロキシを使用する(5):</translation>
    
YES: The Japanese translation is unnatural and contains an unnecessary numeral at the end.
Correct translation: Tor onion service を介してピアに到達するために別の SOCKS5 プロキシを使用します。
```

```
        <source>1 day</source>
        <translation>1 日(a)</translation>
    
YES, The translation is problematic because the letter 'a' in parentheses is not a standard Japanese notation and is likely an artifact or error. The correct translation should simply be "1 日".

1 日
```

```
        <source>1 week</source>
        <translation>1 週間(w)</translation>
    
YES
The translation adds an unnecessary "(w)" after "週間". In Japanese, "週間" already means "week" and the "(w)" is a redundant English abbreviation that is not typically used in this context.

1 週間
```

```
        <source>1 year</source>
        <translation>1 年(y)</translation>
    
YES
The translation includes an unnecessary "(y)" after "年" which is not present in the source text.
1 年
```

```
        <source>From</source>
        <translation>内向き</translation>
    
YES - The translation is inaccurate and misleading in the context of Bitcoin. "内向き" (uchimuki) means "inward" or "inbound," which doesn't accurately reflect the meaning of "From" in a Bitcoin transaction context. "From" in this context refers to the sender's address or account. A more appropriate translation would be "差出人" (sashidashi-nin) or simply "送金元" (sōkinmoto).

Correct translation: 差出人
```

```
        <source>Set external signer script path in Options -&gt; Wallet</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>設定-&gt;オプション-&gt;ウォレット タブにHWIのパスを設定してください</translation>
    
YES
The translation is inaccurate and does not convey the intended meaning of the source text. The source text instructs the user to set the external signer script path in the Options -> Wallet section. The translation, however, mentions setting the HWI path in the "Options -> Wallet Tab". This is not the correct way to interpret the source text.

Correct translation:
設定 -> ウォレット -> 外部署名スクリプトパス
```

```
        <source>%1 to %2</source>
        <translation>%1 送金先: %2</translation>
    
YES, The translation is problematic because it adds unnecessary and potentially confusing context to the original English phrase "from %1 to %2". In the context of Bitcoin, "from %1 to %2" typically refers to a transaction being sent from one address (or identifier) to another, not a "remittance destination." The addition of "送金先" (remittance destination) implies a specific type of transaction that may not be universally applicable or intended by the source text.

Correct translation:
%1 から %2
```

```
        <source>External signer failure</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>HWIのエラー</translation>
    
YES, The translation is too brief and doesn't convey the meaning of "External signer failure".
HWI stands for Hardware Wallet Interface, which is a part of the original phrase but not the entire meaning.
Correct translation: 外部署名者のエラー
```

```
        <source>abandoned</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an abandoned transaction.</extracomment>
        <translation>取消しされました</translation>
    
YES: The translation "取消しされました" (torikeshi saremashita) means "was canceled" or "has been canceled". In the context of Bitcoin transactions, an "abandoned" transaction implies that the sender has given up on waiting for it to confirm and is no longer actively pursuing it. While cancellation is related, "abandoned" carries a slightly different nuance of being left behind or neglected. A more accurate translation would reflect this sense of abandonment.

Correct translation: 破棄されました (haki saremashita)
```

```
        <source>Generated</source>
        <translation>採掘</translation>
    
YES, the translation is incorrect. "Generated" in the context of Bitcoin typically refers to the creation of new bitcoins through mining, or the generation of new wallet addresses. "採掘" (saikutsu) specifically means "mining". A more accurate translation for "Generated" in this context would be "生成済み" (seisei-zumi) if referring to something that has been created, or "生成" (seisei) for the act of generating.

採掘
```

```
        <source>From</source>
        <translation>内向き</translation>
    
YES - The translation is inaccurate and misleading in the context of Bitcoin. "内向き" (uchimuki) means "inward" or "inbound," which doesn't accurately reflect the meaning of "From" in a Bitcoin transaction context. "From" in this context refers to the sender's address or account. A more appropriate translation would be "差出人" (sashidashi-nin) or simply "送金元" (sōkinmoto).

Correct translation: 差出人
```

```
        <source>Received with</source>
        <translation>受取(通常)</translation>
    
YES. The translation is inaccurate and misses crucial context related to Bitcoin. The phrase "Received with" in a Bitcoin context typically refers to receiving funds with a specific transaction or method, not a general "usual receipt."

Correct translation: 受信しました (Jushin shimashita)
```

```
        <source>Received from</source>
        <translation>受取(その他)</translation>
    
YES, The translation is incorrect and doesn't convey the intended meaning of "Received from". In the context of Bitcoin transactions, "Received from" typically indicates the source of the funds. The provided Japanese translation "受取(その他)" translates to "Receipt (Other)" which is not an accurate or contextually appropriate translation.

NO
```

```
        <source>Received with</source>
        <translation>受取(通常)</translation>
    
YES. The translation is inaccurate and misses crucial context related to Bitcoin. The phrase "Received with" in a Bitcoin context typically refers to receiving funds with a specific transaction or method, not a general "usual receipt."

Correct translation: 受信しました (Jushin shimashita)
```

```
        <source>Increase transaction fee</source>
        <translation>取引手数料を追加(f)</translation>
    
YES, The Japanese translation is inaccurate and does not convey the intended meaning of "Increase transaction fee." The current translation "取引手数料を追加(f)" literally translates to "Add transaction fee (f)" which is not the same as increasing it. Additionally, the "(f)" appears to be an artifact and not a meaningful part of the phrase.

A more accurate translation would be "取引手数料を増やす" which means "Increase transaction fee."

NO
```

```
        <source>Prune mode is incompatible with -reindex-chainstate. Use full -reindex instead.</source>
        <translation>剪定モードは -reindex-chainstate と互換性がありません。代わりに完全な再インデックス -reindex を使用してください。</translation>
    
YES
The translation uses "剪定モード" which means "pruning mode" or "pruning method". However, the word "pruning" in the context of Bitcoin refers to removing old transaction data to save disk space. In Japanese, this is typically referred to as "プルーニング" (purūningu) or "データ削減" (dēta sakugen). While "剪定" can mean pruning in a general sense, it's not the standard technical term used in the Bitcoin community.

The translation also has an issue with the phrase "完全な再インデックス -reindex". The source text uses "-reindex" as a flag or option. The Japanese translation should reflect this by either keeping it as is, or translating it more naturally as a command-line option. "完全な再インデックス" is a correct translation of "full reindex", but the way "-reindex" is appended feels a bit unnatural.

A more appropriate translation would be:

プルーニングモードは -reindex-chainstate と互換性がありません。代わりに完全な再インデックスである -reindex を使用してください。
```

```
        <source>Wallet loaded successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future. Legacy wallets can be migrated to a descriptor wallet with migratewallet.</source>
        <translation>ウォレットが正常にロードされました。 レガシーウォレットタイプは非推奨となり、レガシーウォレットの作成と使用のサポートは将来削除される予定です。 レガシーウォレットは、「mergewallet」を使用してディスクリプターウォレットに移行できます。</translation>
    
YES, The translation incorrectly states "mergewallet" instead of "migratewallet".
ウォレットが正常にロードされました。 レガシーウォレットタイプは非推奨となり、レガシーウォレットの作成と使用のサポートは将来削除される予定です。 レガシーウォレットは、「migratewallet」を使用してディスクリプターウォレットに移行できます。
```

```
        <source>Maximum transaction weight is less than transaction weight without inputs</source>
        <translation>最大トランザクションweightがインプットのないトランザクションweightよりも小さい</translation>
    
YES: The translation uses "weight" in English instead of translating it to Japanese. The correct translation should be: 最大トランザクション重量がインプットのないトランザクション重量より小さい
```

```
        <source>Unconfirmed UTXOs are available, but spending them creates a chain of transactions that will be rejected by the mempool</source>
        <translation>未承認の UTXO は利用可能ですが、それらを使用すると取引の連鎖が形成されるので、メモリプールによって拒否されます。</translation>
    
YES, The translation is grammatically incorrect and unnatural.
The phrase "取引の連鎖が形成されるので" (because a chain of transactions will be formed) is a mistranslation of "creates a chain of transactions". The correct translation should convey that spending unconfirmed UTXOs results in a chain of transactions that will be rejected.

NO
```

```
        <source>Maximum transaction weight must be between %d and %d</source>
        <translation>最大トランザクションweightは%dから%dの間でなければなりません。</translation>
    
YES - The translation uses the English word "weight" instead of a Japanese equivalent. The corrected translation uses 「重み」 (omomi) which means weight.
Maximum transaction weight must be between %d and %d
最大トランザクションの重みは%dから%dの間でなければなりません。
```

```
        <source>Unknown change type '%s'</source>
        <translation>不明なお釣りのアドレス形式 '%s' </translation>
    
YES, The translation of "Unknown change type '%s'" to "不明なお釣りのアドレス形式 '%s'" is problematic because it incorrectly translates "change type" as "お釣りのアドレス形式" (address format for change). In the context of Bitcoin, "change type" likely refers to the type of output used for the change in a transaction, not the address format itself. The format specifier '%s' has been correctly carried over.

The correct translation should be:
Unknown change type '%s' -> 不明な変更タイプ '%s'
```
</details>
