# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>ja</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bja%5D%20request)


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

<!-- cache_translation_check_ja_39e85626c534fb5f9a7d9a237c685f42466895cf1e41f87cf3f27a5cbe5af3df -->
```
        <source>&amp;Minimize</source>
        <translation>最小化 &amp;M</translation>
    
ERR
The '&' used for shortcut keys should be placed directly before the corresponding letter in the Japanese translation or on a Latin character, but in Japanese contexts, it is best either appended to the Japanese or the original Latin label, or the letter may be omitted/placed at the beginning. In this translation, "&M" at the end creates confusion, since Japanese UIs often format shortcuts as "(&M)" appended at the end, or insert '&' before a Latin character.

Correct translation:
最小化(&M)
```

<!-- cache_translation_check_ja_a9394585749c18caa827bd7616b9d132be7d1a12dd74e789c5a8c0f545e9c9f4 -->
```
        <source>Load PSBT from &amp;clipboard…</source>
        <translation>PSBTをクリップボードから読む…</translation>
    
ERR
The translation omits the shortcut key indicator (&). The ellipsis should be the Japanese "…" (used correctly here). The translation is otherwise accurate, but to preserve the shortcut key access, & must appear exactly once.

Correct translation:
&amp;PSBTをクリップボードから読む…
```

<!-- cache_translation_check_ja_d64d61fdd30d3e16007074e2efcff2669ad59056da32795ca66280e954fbf843 -->
```
        <source>Restore Wallet</source>
        <extracomment>Title of pop-up window shown when the user is attempting to restore a wallet.</extracomment>
        <translation>ウォレットを復</translation>
    
ERR
The translation is incomplete and cut off. The Japanese word for "Restore" in this context should be "復元" (fukugen), but only the first character "復" is present.

Correct translation:
ウォレットを復元
```

<!-- cache_translation_check_ja_1f58d3f8a81110c8c089583fdb1bf9d1e43309bf20c1948fbae5c0d9cc60ecfa -->
```
        <source>&amp;Hide</source>
        <translation>隠す</translation>
    
ERR
The ampersand (&) used in the source text to indicate a shortcut key is missing in the Japanese translation. The translation should contain & exactly once.

Correct translation:
&隠す
```

<!-- cache_translation_check_ja_c614bfcf045836810ee061c684c9bde88c719c93909c10c86c57897d958b1e3a -->
```
        <source>S&amp;how</source>
        <translation>表示</translation>
    
ERR
The translation omits the '&' character, which is required to indicate a shortcut key in the menu. It should be included exactly once somewhere in the translation.

Correct translation:
&表示
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

<!-- cache_translation_check_ja_5221ff16cd7bde63d8f8556d1439f11fc30965bfe9353bd4e9dbb269c4746e73 -->
```
        <source>Restoring the wallet will copy the backup file to the wallets directory and place it in the standard wallet directory layout. The original file will not be modified.

Migrating the wallet will convert the restored wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>ウォレットの復元では、バックアップファイルをウォレットディレクトリにコピーし、標準のウォレットディレクトリレイアウトに配置します。元のファイルは変更されません。

ウォレットの移行では、復元されたウォレットを１つ以上のディスクリプターウォレットに変換します。新しいウォレットバックアップを作成する必要があります。
このウォレットに監視専用スクリプトが含まれている場合、それらの監視専用スクリプトを含む新しいウォレットが作成されます。
このウォレットに解決可能だが非監視スクリプトが含まれている場合、それらのスクリプトを含む別の新しいウォレットが作成されます。

移行プロセスでは、移行前にウォレットのバックアップが作成されます。このバックアップファイルの名前は&lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bakで、このウォレット用のディレクトリ内に保存されます。間違った移行が行われた場合、「ウォレットの復元」機能をしよいうしてバックアップを復元できます。</translation>
    
ERR
The translation contains a typo in the last sentence. "しよいうして" (shiyouishite) should be "使用して" (shiyoushite) or "しよ­う­して". Also, the punctuation and spacing around the placeholder names could be improved for better readability.

Correct translation:
ウォレットの復元では、バックアップファイルをウォレットディレクトリにコピーし、標準のウォレットディレクトリレイアウトに配置します。元のファイルは変更されません。

ウォレットの移行では、復元されたウォレットを1つ以上のディスクリプターウォレットに変換します。新しいウォレットバックアップを作成する必要があります。
このウォレットに監視専用スクリプトが含まれている場合、それらの監視専用スクリプトを含む新しいウォレットが作成されます。
このウォレットに解決可能だが監視されていないスクリプトが含まれている場合、それらのスクリプトを含む別の新しいウォレットが作成されます。

移行プロセスでは、移行前にウォレットのバックアップが作成されます。このバックアップファイルの名前は <wallet name>-<timestamp>.legacy.bak で、このウォレット用のディレクトリ内に保存されます。移行に失敗した場合、「ウォレットの復元」機能を使用してバックアップを復元できます。
```

<!-- cache_translation_check_ja_0914854e51cf3f4915d58aa5ea7d953c57325769a45ab8ceb0af9b0ec57fd3e1 -->
```
        <source>W&amp;allet</source>
        <translation>ウォレット(&amp;a)</translation>
    
ERR
The ampersand (&) in the original marks the shortcut key, and should precede the shortcut character in the Japanese translation. It appears here as (&amp;a), which means "a" is set as the shortcut key, but there is no "a" in the Japanese word "ウォレット", making the shortcut meaningless in the Japanese context. Furthermore, "ウォレット" is correct for "wallet", but typically in Japanese translations for menus, a single katakana character or a meaningful Roman letter (e.g. ウォレット(&amp;W)) is chosen for the shortcut, matching the English.

Correct translation:
ウォレット(&amp;W)
```

<!-- cache_translation_check_ja_d2f355c1e5d891d384985a13b4f876f82999e3d849d0327a84dffd96a65dd573 -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>デフォルトで金額からfeeを差し引く(&amp;f)</translation>
    
ERR
The English "&amp;fee" is a label indicating that "fee" is the hotkey (shortcut), not meant to be translated or shown literally as "fee". In Japanese UI, typically the word "手数料" is used for "fee", and the ampersand (&amp;) should be placed before the character corresponding to the keyboard shortcut, often the first letter of the label in katakana or an appropriate Latin character.

Correct translation:
デフォルトで金額から手数料を差し引く(&amp;F)

This way, "fee" is properly localized as "手数料", and the access key (&amp;F) is preserved.
```

<!-- cache_translation_check_ja_9ee687c3476a5308bebc4d9650678053a42cf99917b58f74b0bdd2c0ae668834 -->
```
        <source>&amp;External signer script path</source>
        <translation>HWIのパス(&amp;E)</translation>
    
ERR
The translation is inaccurate. "External signer script path" refers to the file path for the external signer's script, not specifically "HWI" (which is a specific hardware wallet interface, not generic). The translation should be more general and reflect the concept of "external signer script path". The position of &amp; as a shortcut key indicator is acceptable, but it's currently placed at E, which matches "External" in English but doesn't correspond to any Japanese character.

Correct translation:
外部署名者スクリプトのパス(&amp;E)
```

<!-- cache_translation_check_ja_655d74b7ea475acf43f071f5eea86bf70e010d0f745e424718f97f394bb51e44 -->
```
        <source>Use separate SOCKS&amp;5 proxy to reach peers via Tor onion services:</source>
        <translation>Tor onion serviceを介してピアに到達するために別のSOCKS&amp;5プロキシを使用する(&amp;5):</translation>
    
ERR
There are two issues:
1. The English text uses "&" as a shortcut marker before the "5" in "SOCKS&5", but in Japanese the "&5" is preserved at the wrong place and results in displaying as (&5), which is misleading.
2. The translation is awkward; "を介してピアに到達するために" is a literal translation, but more natural would be "Tor onion service経由でピアに接続するために、別のSOCKS&5プロキシを使用する" and the shortcut key marker (&) should be attached to a suitable character, but Japanese UIs often do not use mnemonic keys in translations. If required, it can be on 'S' or any meaningful word, but duplicating "&" as "&5" is wrong.

Correct translation:
Tor onion service経由でピアに接続するために、別のSOCKS&5プロキシを使用する

If a shortcut/mnemonic is required for localization, it would depend on the application; otherwise, omit explicit placement.
```

<!-- cache_translation_check_ja_c7c3949c3b9192a5e53a007c03f41165729972787821db0522763d5c89fc9972 -->
```
        <source>Private broadcast: short-lived, for broadcasting privacy-sensitive transactions</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to broadcast privacy-sensitive data (like our transactions).</extracomment>
        <translation>プライベートブロードキャスト: プライバシーに配慮した取引をブロードキャストするためもので、短命</translation>
    
ERR
The translation contains a grammatical error and a minor omission. The particle "の" is missing after "ため" (should be "ためのもの"), and the phrasing "短命" at the end is awkward for an explanatory sentence.

Correct translation:
プライベートブロードキャスト: プライバシーに配慮した取引をブロードキャストするためのもので、短期間のみ有効です。
```

<!-- cache_translation_check_ja_f780c2f0dd26b87896fd739ffc9a17f05bdb876b3ad2220b680e1caebed73299 -->
```
        <source>1 d&amp;ay</source>
        <translation>1 日(&amp;a)</translation>
    
ERR
The shortcut key (&amp;a) does not match the original English usage, which is &amp;a for 'a' in 'day'. In Japanese, mnemonics are usually matched to the Katakana or Hiragana character that would make sense, but if none fits, it can be omitted or sometimes assigned to a logical character. Here, '日' is read as 'にち' ('nichi'), and typically no English mnemonic is used. If it must exist, &amp;a can be retained but it doesn't match any Japanese character. The rest of the translation is fine.

Correct translation:
1日(&amp;a)
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

<!-- cache_translation_check_ja_948e80d930847d17760dd27aa5148bc69391caa2c855d53f637d36b68615b39a -->
```
        <source>Copy &amp;raw transaction</source>
        <translation>取引のRAWデータをコピー(r)</translation>
    
ERR
The translation changes the word order and does not keep the ampersand (&) used for the shortcut key as in the original. In Japanese UI, the shortcut key (here indicated as (r)) should match user expectations, but the ampersand (&) should appear exactly once as instructed.

Correct translation:
RAW取引をコピー(&r)
or
&RAW取引をコピー

Either form is acceptable in Japanese localization, but the ampersand should precede the shortcut letter, which usually matches the (r) in the English. The provided translation uses (r) in parentheses, which is somewhat common but not as standard or explicit in shortcut use as using &. It is not a serious error, but it does not match the source's use of &; thus, a correction is warranted.
```

<!-- cache_translation_check_ja_05e2fb65317fd324769ae519f309f00332976592caa6d460828d0656f9660c99 -->
```
        <source>Copy full transaction &amp;details</source>
        <translation>取引の詳細をコピー(d)</translation>
    
ERR
The translation does not account for the shortcut key indicator represented by '&' in the source string. In Japanese UI translations, the shortcut key should typically be indicated by an '&' before the appropriate roman letter (e.g. '&d' or '(D)'), but instead the translation includes "(d)" in parentheses after the translated text, which is not standard and does not match the source usage of '&'. Also, the translation omits "full" (完全な or 全体の), which is present in the source.

Correct translation:
完全な取引の詳細をコピー(&d)
```

<!-- cache_translation_check_ja_dc36730eb72725f34c42df96ad4402fb46ce43bd2a16e07f526ffbaa950035bc -->
```
        <source>A&amp;bandon transaction</source>
        <translation>取引を取消す(b)</translation>
    
ERR
The shortcut key indicator "&" is missing in the Japanese translation. It should appear exactly once, though its location may differ. Also, the translation "取消す" is colloquial; "中止" or "放棄" may be more accurate for "Abandon".

Correct translation:
取引を&放棄する or &取引を放棄する (shortcut key on the first character after &)

Or, if the shortcut key is to remain 'b':
取引を放棄する(&b)
```

<!-- cache_translation_check_ja_dba2b83506d7d6fbd3d00c9e7c5c4a5bda37f775b1b2ed764104d7920db48c61 -->
```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>%s=&lt;amount&gt; オプションに対する不正な設定: '%s' （取引の停滞防止のため、最小中継手数料の %s より大きい必要があります）</translation>
    
ERR
Placeholders (%s and &lt;amount&gt;) are preserved correctly, but the Japanese wording is slightly off: "不正な設定" is awkward for "Invalid amount" and "より大きい必要があります" implies strictly greater than, while the source means "at least" (≥). Also remove the extra space before the parenthesis for natural Japanese.

Correct translation:
%s=&lt;amount&gt; に指定された金額が無効です: '%s'（取引の停滞を防ぐため、最小中継手数料 %s 以上である必要があります）
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

<!-- cache_translation_check_ja_284d8fab6339bdf8ccf724bbd238a59a93cd5a130d80fc6f1796f6f9717da60b -->
```
        <source>Specified -blockreservedweight (%d) is lower than minimum safety value of (%d)</source>
        <translation>指定された -blockreservedweight (%d) は最小安全値 (%d) より低いです</translation>
    
ERR
The translation is understandable and preserves format specifiers, but it has minor spacing issues (unnecessary spaces before the option name and before the particle) and a slightly unnatural phrasing.

Corrected translation:
指定された-blockreservedweight (%d) は最小安全値 (%d) 未満です
```

<!-- cache_translation_check_ja_01e6b475f6e8678070def2f0c66613952151426ab5a7b9c85f09ec549c8c6854 -->
```
        <source>Can't spend unconfirmed version %d pre-selected input with a version 3 tx</source>
        <translation>バージョン3のtxで、未確認バージョン1%dの事前選択されたインプットを使うことはできません</translation>
    
ERR
The translation includes an extra "1" before the format specifier "%d", which is not present in the source text and alters the meaning.

Correct translation:
バージョン3のtxで、未確認バージョン%dの事前選択されたインプットを使うことはできません
```

<!-- cache_translation_check_ja_580c79730e824c6ba4b47a62d1a119ea1d436740ad8183a1c6d98e633039cd5d -->
```
        <source>Can't spend unconfirmed version 3 pre-selected input with a version %d tx</source>
        <translation>バージョン1%dのtxで、未確認バージョン3の事前選択されたインプットを使うことはできません</translation>
    
ERR
The format specifier from the source `%d` has been incorrectly modified to `%1%d` in the translation. This will likely cause a formatting error in the application.

Correct translation:
バージョン %d の tx で、未確認バージョン 3 の事前選択されたインプットを使うことはできません
```

<!-- cache_translation_check_ja_a9579629663a4b6cb2a0394fe2e5e5757db2e7f524f8571eb882df36b237cc85 -->
```
        <source>Failed to acquire rescan reserver during wallet initialization</source>
        <translation>初期化中に再スキャンの予約の入手に失敗しました</translation>
    
ERR
The Japanese is understandable but slightly unnatural. "rescan reserver" in this context is better rendered as "再スキャン用の予約" or "再スキャン用のリザーバ" and include "ウォレット" to mirror "wallet initialization".

Suggested translation:
ウォレットの初期化中に再スキャン用の予約の取得に失敗しました
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

<!-- cache_translation_check_ja_c31f12481038bf53e9ea8408ddf324e2779bd966839f59497c56ce9464d97678 -->
```
        <source>Failed to calculate bump fees, because unconfirmed UTXOs depend on an enormous cluster of unconfirmed transactions.</source>
        <translation>未承認 のUTXO は膨大な数の未承認取引に依存しているため、手数料の引き上げの計算に失敗しました。</translation>
    
ERR
The translation has an extra space ("未承認 のUTXO") which is unnatural in Japanese. Also the sentence order is acceptable but can be slightly more natural.

Correct translation:
未承認のUTXOが膨大な数の未承認トランザクションに依存しているため、手数料の引き上げの計算に失敗しました。
```

<!-- cache_translation_check_ja_f2be15d8fc51129c7c04c08387c254e46778baed3104c0c30a197269cd5912f7 -->
```
        <source>Transaction requires one destination of non-zero value, a non-zero feerate, or a pre-selected input</source>
        <translation>取引には、0 でない送金額の宛先、0 でない手数料率、あるいは事前に選択された入力が必要です</translation>
    
ERR
Minor issues: spaces appear around the numeral "0" ("0 でない") which is non-idiomatic in Japanese; also the sentence would read more naturally if phrased to indicate "one of the following is required" (いずれかが必要です).

Correct translation:
取引には、ゼロでない金額の宛先、ゼロでない手数料率、または事前に選択された入力のいずれかが必要です

(Alternatively, using numerals without spaces:
取引には、0でない金額の宛先、0でない手数料率、または事前に選択された入力のいずれかが必要です)
```

<!-- cache_translation_check_ja_003389b46ab6138e6f8651dc4231320717da5efdeaad1637ef967c4f867a1fac -->
```
        <source>Unrecognized descriptor found. Loading wallet %s

The wallet might have been created on a newer version.
Please try running the latest software version.
</source>
        <translation>認識できないディスクリプターが見つかりました。ウォレット %s を読み込んでいます

ウォレットが新しいバージョンで作成された可能性があります。
最新のソフトウェア バージョンを実行してみてください。
</translation>
    
ERR
Overall translation is understandable and preserves %s and line breaks, but has minor issues:
- Slightly unnatural/varied terminology for "descriptor" (common Japanese Bitcoin translations use ディスクリプタ or 記述子).
- Extraneous space in "ソフトウェア バージョン" (Japanese normally omits that space).
- A more natural phrasing for the last sentence would use a direct request rather than "を実行してみてください" (which is polite but less direct).

Suggested correction (keeps %s and blank line formatting):

認識できないディスクリプタが見つかりました。ウォレット %s を読み込んでいます

ウォレットは新しいバージョンで作成された可能性があります。
最新のソフトウェアバージョンを実行してください。
```

<!-- cache_translation_check_ja_fde0293c563a7ee4ea89cf35885555ddd6591141963ab1acf5c6c49cb235438e -->
```
        <source>Invalid -proxy address or hostname, ends with '=': '%s'</source>
        <translation>'=': '%s'で終わる無効な -proxy アドレスまたはホスト名</translation>
    
ERR
The translation is understandable but the word order and punctuation are unnatural in Japanese. The format specifier '%s' and the '=' are preserved, which is good, but a more natural rendering would clarify that the given value ends with '='.

Correct translation:
無効な -proxy アドレスまたはホスト名です。'%s' は '=' で終わっています。
```

<!-- cache_translation_check_ja_ae07428c60b1ec58061ddc64f080792e8e76a4859bac0d814cb238f111e752d8 -->
```
        <source>Unrecognized network in -proxy='%s': '%s'</source>
        <translation>-proxy='%s': '%s'内に認識されないネットワーク</translation>
    
ERR
The Japanese is awkward/ungrammatical. Word order and particles are incorrect; it reads unnatural as "-proxy='%s': '%s'内に認識されないネットワーク". The % specifiers are preserved, but the phrasing should say the network '%s' in -proxy='%s' is unrecognized.

Suggested correction:
-proxy='%s': '%s' のネットワークは認識されません。
```
</details>

Number of issues: 44.
