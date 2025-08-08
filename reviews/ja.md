# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ja</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bja%5D%20low%20quality)


<!-- cache_translation_check_ja_7c8d85793e337ba00e1be1697530b28d0f6b6194a3dd5c9bba72347c3ee6cb8e -->
```
        <source>Right-click to edit address or label</source>
        <translation> 
右クリックしてアドレスまたはラベルを編集します。</translation>
    
ERR
There is an unwanted leading whitespace in the translation, which can cause formatting issues. The translation itself is accurate, but the whitespace should be removed.

Correct translation:
右クリックしてアドレスまたはラベルを編集します。
```

<!-- cache_translation_check_ja_2465af594a5ddde642466570fc1d661d80efa4a7fe832a19153030c0eedbeed8 -->
```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>これらは、あなたが知っている送信先の Bitcoin アドレスです。コインを送る前に必ず、金額と受取用アドレスを確認してください。</translation>
    
ERR
The translation contains an error in meaning. The English source states "These are your Bitcoin addresses for sending payments," but the Japanese translation says "これらは、あなたが知っている送信先の Bitcoin アドレスです。" ("These are the Bitcoin addresses of recipients you know"), which changes the meaning from "your own addresses" to "known recipient addresses." This is problematic.

Correct translation:
これらは支払いを送るためのあなたのBitcoinアドレスです。コインを送信する前に、必ず金額と受取アドレスを確認してください。
```

<!-- cache_translation_check_ja_57579d83a87e74f7762025e35448ac8e8dce96ebde019b21e8ff55720062e580 -->
```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>取引履歴を %1 へ保存する際にエラーが発生しました。再試行してください。</translation>
    
ERR
The translation is inaccurate. "取引履歴" means "transaction history", not "address list". The source talks about saving the "address list". The rest of the sentence is adequately translated, but the subject is wrong.

Correct translation:
アドレスリストを %1 に保存する際にエラーが発生しました。もう一度お試しください。
```

<!-- cache_translation_check_ja_21b39850e87b3b6b5ba2b589e6c3347d584aed26a806c13d21f976c9eb2476a7 -->
```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>内部エラーが発生。 %1 は安全な継続をトライ中。これは予期せぬバグであり、次に説明するようにリポートできます。</translation>
    
ERR
The translation is understandable but sounds unnatural and uses casual, telegraphic expressions inappropriate for an application error message. The phrase "発生" should be "発生しました" for the correct tense; "トライ中" is an unnatural direct translation for "will attempt" and not standard in Japanese UI messages; likewise, "リポートできます" is less common than "報告できます".

Correct translation:
内部エラーが発生しました。%1 は安全に継続を試みます。これは予期しないバグであり、以下の方法で報告できます。
```

<!-- cache_translation_check_ja_2a727c7e958eed8bb3d575bd342982ea67c338ea65fde996734a424abc314dd4 -->
```
        <source>Minimize</source>
        <translation>最小化 M</translation>
    
ERR
The translation includes an unnecessary "M" character at the end, which is not present in the source text and could be confusing. The correct translation is:

最小化
```

<!-- cache_translation_check_ja_389bfda8a07447e47c9275b2aafcc4c75bb0ae6e21702fe08c6ae4ae862770cb -->
```
        <source>Received with label</source>
        <translation>対応するラベル</translation>
    
ERR  
The translation "対応するラベル" means "corresponding label" or "the applicable label", which does not convey the original meaning of "Received with label" in the context of Bitcoin (i.e., an amount received that is associated with a particular label/tag). The translation omits the notion of "received".

Correct translation:  
ラベル付き受取
```

<!-- cache_translation_check_ja_f3a1e77990686762bf62685b0fa047dae895fd90f13afaf0d3697c8401b405d2 -->
```
        <source>Received with address</source>
        <translation>対応するアドレス</translation>
    
ERR
The translation "対応するアドレス" means "corresponding address" in Japanese, which does not accurately convey "Received with address." The correct translation should communicate that something was received to/with a particular address.

Correct translation:
受取アドレス

Or, if more context is needed:
このアドレスで受信

Either of these better fits the original English meaning.
```

<!-- cache_translation_check_ja_45dcc69ef9be80b9b8a57af6e5c1dd520d2562f12ad01392aaed0a06df180380 -->
```
        <source>Lock unspent</source>
        <translation>コインをロック(o)</translation>
    
ERR
The translation "コインをロック(o)" translates to "Lock coin(s) (o)", which adds an "(o)" suffix not present in the source. Furthermore, "Lock unspent" is more accurately and commonly translated in Bitcoin context as "未使用コインをロック" ("Lock unspent coins"), specifically referring to 'unspent' coins (Unspent Transaction Outputs, or UTXO), not just any coins. The source does not mention a shortcut "(o)", and that should not be included.

Correct translation:
未使用コインをロック
```

<!-- cache_translation_check_ja_4892065c1ddced199e29daf48e1bd6ed00a5b06fc8222caf6d5b68b463df5f28 -->
```
        <source>Unlock unspent</source>
        <translation>コインをアンロック(U)</translation>
    
ERR
The translation adds "コイン" (coin) and includes "アンロック(U)" ("Unlock (U)") as a menu item, which is common in Japanese software UIs, but the source "Unlock unspent" is a technical, Bitcoin-specific phrase. The translation should closely reflect "Unspent" as "未使用" or "未使用コイン", not just "コイン". While "アンロック" works as "Unlock", the translation loses the "unspent" nuance as a technical term for unspent outputs, not just generically "coins".

Correct translation:
未使用の出力をアンロック

Or, if brevity as a menu item is important:
未使用をアンロック
```

<!-- cache_translation_check_ja_ce1f266d53ccc61874dc095c2b360504fbbcaa8e0122403dee34dcdf25de836d -->
```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>外部署名のサポート(外部署名に必要)なしでコンパイルされています </translation>
    
ERR
The translation contains errors in wording and style. "外部署名" is not natural Japanese for "external signing", and "外部" should be used instead. Also, the sentence should be more formal and concise, and there is a stray space at the end.

Correct translation:
外部署名のサポートなしでコンパイルされています（外部署名には必要です）
```

<!-- cache_translation_check_ja_a1cc7201ca92d91e90a12dc176f8b4d5f39719ae84fba76781699506c5679408 -->
```
        <source>Prune block storage to</source>
        <translation>ブロックの保存容量を次の値までに剪定する(b): </translation>
    
ERR
The translation unnecessarily adds "保存容量" (storage capacity) and "(b):", and translates "to" as "までに" (by/within), not indicating the destination/amount clearly. The added "(b):" is also not present in the source.

Correct translation:
ブロックストレージを次の値まで剪定する

Or, if contextually referring to the size:
ブロックストレージを指定サイズまで剪定する

This translation should avoid adding words not present in the original text and should not include unnecessary formatting.
```

<!-- cache_translation_check_ja_eca207f0a41c26574bf6d52a8c63f5e7f8706b07dc908183e8dfe85dddf4e974 -->
```
        <source>External signer script path</source>
        <translation>HWIのパス(E)</translation>
    
ERR
The translation is inaccurate. "External signer script path" refers to the file path of an external script used for signing. "HWIのパス(E)" means "Path of HWI (E)", which is both too specific (only referencing HWI hardware wallet interface) and omits "script," making it misleading. Also, the "(E)" in Japanese UI typically represents an access key, not needed unless consistent within the UI.

Correct translation:
外部署名スクリプトのパス
```

<!-- cache_translation_check_ja_2ef71c17397795c6186e4157bdb265c5fd5f65698538276c858d8ba39b7667ed -->
```
        <source>Use separate SOCKS5 proxy to reach peers via Tor onion services:</source>
        <translation>Tor onion serviceを介してピアに到達するために別のSOCKS5プロキシを使用する(5):</translation>
    
ERR
The translation is mostly accurate but has unnecessary "(5)" at the end and could be slightly more natural in Japanese. The "(5)" seems like a stray character, possibly from the word "SOCKS5". Also, the term "onion service" should ideally be rendered as "オンションサービス" or "Onionサービス" in Japanese for clarity. 

Correct translation:
TorのOnionサービス経由でピアに接続するために、別のSOCKS5プロキシを使用する:
```

<!-- cache_translation_check_ja_02b7997daa5a32b41ceff53e3a2898cab1ce563a9ff923d6a4fdc633fdbd2b79 -->
```
        <source>1 day</source>
        <translation>1 日(a)</translation>
    
ERR
The translation has an erroneous extra "(a)" after "1 日". The correct translation should just be "1日" (with no space and no "(a)"), which is the standard way of writing "1 day" in Japanese.

Correct translation:
1日
```

<!-- cache_translation_check_ja_70ef9c93e5f425cd10bc6db9a849d1e2904d733e29b87349ebc8fe1bdb6dd3ff -->
```
        <source>1 week</source>
        <translation>1 週間(w)</translation>
    
ERR
The translation includes unnecessary "(w)", which is not standard in Japanese and may confuse users. Also, there is an extra space between "1" and "週間". The correct translation should be:

1週間
```

<!-- cache_translation_check_ja_e3e49b17cfc0377773175cc582db6cf8ceeaa332bdd83085576b913d0d55d980 -->
```
        <source>1 year</source>
        <translation>1 年(y)</translation>
    
ERR
The inclusion of "(y)" is unnecessary and does not match standard Japanese usage. "1 年" alone is sufficient and correct.

Correct translation:
1 年
```

<!-- cache_translation_check_ja_2a3ea0ae3c3c0b7eb6f9e3875f020f0fb0e55c1d52552fe01760143426537082 -->
```
        <source>From</source>
        <translation>内向き</translation>
    
ERR  
The translation "内向き" means "inward" or "inbound," which is not a natural or accurate translation for "From" in this context. For transaction lists or email contexts, "From" is usually translated as "差出人" (sender) or "送信元" (source/sender). In the context of Bitcoin transactions, "送信元" is most appropriate.

Correct translation:  
送信元
```

<!-- cache_translation_check_ja_471398f531cdf63e65864fab59f65d8c16f12c9b432b229e2569bd36336928b5 -->
```
        <source>Set external signer script path in Options -&gt; Wallet</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>設定-&gt;オプション-&gt;ウォレット タブにHWIのパスを設定してください</translation>
    
ERR
The translation replaces "external signer script path" with "HWIのパス", which assumes the external signer is specifically HWI (Hardware Wallet Interface). However, "external signer" could refer to other software or devices as well, not just HWI. The translation should remain general and true to the original.

Correct translation:
オプション-&gt;ウォレットで外部署名者スクリプトのパスを設定してください
```

<!-- cache_translation_check_ja_7841ca3846bd60e1e651798e04fcb938d8551500ab0f6f42a4d8305924ab3352 -->
```
        <source>%1 to %2</source>
        <translation>%1 送金先: %2</translation>
    
ERR  
The translation "%1 送金先: %2" changes the meaning of the original text. The English "%1 to %2" is a generic format (e.g., "1 BTC to Alice"). The Japanese translation introduces "送金先:", meaning "destination of remittance," which changes the format and meaning.

Correct translation:  
%1 から %2 へ

This preserves the original structure ("from %1 to %2"). If only "to" should be translated, then:  
%1 から %2 へ

Or, if contextually just "%1 to %2":  
%1 から %2 へ
```

<!-- cache_translation_check_ja_b05062250fb885840b4961afd5654c5228619f2d0707ea024287018ba4a4078f -->
```
        <source>External signer failure</source>
        <extracomment>"External signer" means using devices such as hardware wallets.</extracomment>
        <translation>HWIのエラー</translation>
    
ERR
The translation "HWIのエラー" specifically refers to "HWI" (Hardware Wallet Interface), which may not encompass all types of "external signers" (the English source is broader; it could be any device or method). The translation should convey the general notion of "external signer failure" rather than limit it to HWI.

Correct translation:
外部署名ツールのエラー

Or, more literally:
外部署名者の失敗

Either of the above would be more accurate and inclusive.
```

<!-- cache_translation_check_ja_b473674bffa57d4e1f1392350675231e70f2435d01c05d85e4cdbc17f3deebdc -->
```
        <source>abandoned</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an abandoned transaction.</extracomment>
        <translation>取消しされました</translation>
    
ERR
The translation "取消しされました" is incorrect and unnatural in Japanese. It redundantly combines the noun "取消し" (cancellation) with the passive "-されました" and does not properly convey "abandoned" in the context of a transaction. The correct term used in Japanese Bitcoin wallets for "abandoned" is usually "放棄されました".

Correct translation:
放棄されました
```

<!-- cache_translation_check_ja_f74183f0eaa625d89709879b6233a59130dec08bac775d6e9ace72ec4d4f9b89 -->
```
        <source>Generated</source>
        <translation>採掘</translation>
    
ERR  
The translation is inaccurate. "Generated" in the context of Bitcoin typically refers to coins that have been newly created, usually via mining, but "採掘" means "mining." The correct translation for "Generated" in this context would be "生成済み" or "生成された."

Correct translation:  
生成済み
```

<!-- cache_translation_check_ja_2a3ea0ae3c3c0b7eb6f9e3875f020f0fb0e55c1d52552fe01760143426537082 -->
```
        <source>From</source>
        <translation>内向き</translation>
    
ERR  
The translation "内向き" means "inward" or "inbound," which is not a natural or accurate translation for "From" in this context. For transaction lists or email contexts, "From" is usually translated as "差出人" (sender) or "送信元" (source/sender). In the context of Bitcoin transactions, "送信元" is most appropriate.

Correct translation:  
送信元
```

<!-- cache_translation_check_ja_54d1436effd2c829a4924f59152f5499f274dcd9c6c9365e4ebaddc4bb8a4d36 -->
```
        <source>Received with</source>
        <translation>受取(通常)</translation>
    
ERR
The translation "受取(通常)" is inaccurate. "Received with" in the context of Bitcoin usually appears as a column header and refers to the address, label, or account associated with the received transaction, not the "normal" way of receipt.

Correct translation:
受取先

Explanation:
"受取先" means "recipient" or "received with", which is the common header in Japanese Bitcoin wallets.
```

<!-- cache_translation_check_ja_375ea266346b227d0a13c08e65eb803759f46637e3a7dc03c19d0ff43d6fc173 -->
```
        <source>Received from</source>
        <translation>受取(その他)</translation>
    
ERR
The translation "受取(その他)" means "Received (Other)" and does not accurately convey the meaning of "Received from." The correct Japanese translation should clarify the source, such as by using "受取元" or "送信元".

Correct translation:
受取元
```

<!-- cache_translation_check_ja_54d1436effd2c829a4924f59152f5499f274dcd9c6c9365e4ebaddc4bb8a4d36 -->
```
        <source>Received with</source>
        <translation>受取(通常)</translation>
    
ERR
The translation "受取(通常)" is inaccurate. "Received with" in the context of Bitcoin usually appears as a column header and refers to the address, label, or account associated with the received transaction, not the "normal" way of receipt.

Correct translation:
受取先

Explanation:
"受取先" means "recipient" or "received with", which is the common header in Japanese Bitcoin wallets.
```

<!-- cache_translation_check_ja_5fdff6d99abee912a9be37e90fdbe0f7331bedf2f9f1b2d2a5e71b1468dfb905 -->
```
        <source>Increase transaction fee</source>
        <translation>取引手数料を追加(f)</translation>
    
ERR
The translation is not accurate. "取引手数料を追加(f)" means "Add transaction fee (f)" and the "(f)" is unexplained and not present in the source text. The correct translation should be:

Correct translation:
取引手数料を増やす
```

<!-- cache_translation_check_ja_92427a91cbb93c5e660f2e9054b81fc073e2055b9f8272db81f84aaf1eefe26f -->
```
        <source>Wallet loaded successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future. Legacy wallets can be migrated to a descriptor wallet with migratewallet.</source>
        <translation>ウォレットが正常にロードされました。 レガシーウォレットタイプは非推奨となり、レガシーウォレットの作成と使用のサポートは将来削除される予定です。 レガシーウォレットは、「mergewallet」を使用してディスクリプターウォレットに移行できます。</translation>
    
ERR
There are several issues with the translation:

1. Incorrect command: The source mentions "migratewallet", but the translation says 「mergewallet」, which is a significant error.
2. Some slight nuance issues: "作成と使用のサポート" should rather be "作成およびオープンのサポート" or similar, to match "creating and opening".
3. Unnecessary space after periods: There is a full-width space after "ました。" and "です。", which is not standard in Japanese (should not be there).

Correct translation:
ウォレットが正常にロードされました。レガシーウォレットタイプは非推奨となっており、今後はレガシーウォレットの作成およびオープンのサポートが削除される予定です。レガシーウォレットは、「migratewallet」を使用してディスクリプターウォレットに移行できます。
```

<!-- cache_translation_check_ja_e76bc74181e6867e8a66fd2f6ede48b70e4ed8f61695cd18a37141aac7d79a08 -->
```
        <source>Maximum transaction weight is less than transaction weight without inputs</source>
        <translation>最大トランザクションweightがインプットのないトランザクションweightよりも小さい</translation>
    
ERR
The translation uses the English word "weight" directly in "トランザクションweight" and "トランザクションweight", which is unnatural in Japanese. It's better to translate "weight" as "重量" (jūryō). Also, "インプット" is understandable but "入力" is more standard for "inputs".

Correct translation:
最大トランザクション重量が入力なしのトランザクション重量よりも小さいです
```

<!-- cache_translation_check_ja_6a7635ee6c8e67659c877d95e37be685b87dd06e157bbd28e5928d1aa6a17a78 -->
```
        <source>Maximum transaction weight must be between %d and %d</source>
        <translation>最大トランザクションweightは%dから%dの間でなければなりません。</translation>
    
ERR
There is a minor issue: "weight" is not translated into Japanese, which could be confusing. In Japanese, the term "weight" is often translated as "重量" in technical contexts regarding Bitcoin. Also, the phrase "から...の間でなければなりません" would sound more natural as "の間でなければなりません" without "から".

Correct translation:
最大トランザクション重量は%dから%dの間でなければなりません。
```

<!-- cache_translation_check_ja_3cdb22ee635cff88c98b96e3f865b00bd2221390b3e450c09569767fc7ac7002 -->
```
        <source>Unknown change type '%s'</source>
        <translation>不明なお釣りのアドレス形式 '%s' </translation>
    
ERR
The Japanese translation translates "change type" as "お釣りのアドレス形式", which means "change address format". However, "change type" here likely refers to the type/category of 'change' in a transaction, not specifically an "address format". The translation also adds the word "アドレス" (address) which is not present in the source, and has a stray space before the closing quotation.

Correct translation:
不明な変更タイプ '%s'
or, if specifically referring to Bitcoin change outputs:
不明なお釣りタイプ '%s'
```
</details>

Number of issues: 31.
