# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ms</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bms%5D%20low%20quality)


```
        <source>Enter address or label to search</source>
        <translation>Masukkan alamat atau label untuk memulakan pencarian
</translation>
    
YES - The translation includes an extra newline character at the end of the sentence.
Masukkan alamat atau label untuk memulakan pencarian
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>Alihkan fail data ke dalam tab semasa</translation>
    
YES, The translation is problematic. It incorrectly translates "Export the data in the current tab to a file" as "Alihkan fail data ke dalam tab semasa" which means "Switch the data file into the current tab". The correct translation should be "Eksportkan data dalam tab semasa ke fail".

Correct translation: Eksportkan data dalam tab semasa ke fail
```

```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>Ini adalah alamat Bitcoin anda untuk pembayaran. Periksa jumlah dan alamat penerima sebelum membuat penghantaran koin sentiasa.</translation>
    
YES. The word order in the translation is awkward and unnatural in Malay. The phrase "sentiasa" (always) is misplaced at the end of the sentence.

Correct translation: Ini adalah alamat Bitcoin anda untuk pembayaran. Sentiasa periksa jumlah dan alamat penerima sebelum membuat penghantaran koin.
```

```
        <source>Copy Address</source>
        <translation>Salin Aamat</translation>
    
YES
The translation contains a spelling error. The correct spelling for "address" in Malay is "Alamat", not "Aamat".
Salin Alamat
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Amaran: Jika anda enkripkan dompet anda dan hilangkan frasa laluan, anda akan &lt;b&gt;ANDA AKAN HILANGKAN SEMUA BITCOIN ANDA&lt;/b&gt;!</translation>
    
YES, the translation is problematic because it repeats the phrase "ANDA AKAN" which is redundant and grammatically incorrect.

The correct translation is:
Amaran: Jika anda enkripkan dompet anda dan hilangkan frasa laluan, anda akan &lt;b&gt;HILANGKAN SEMUA BITCOIN ANDA&lt;/b&gt;!
```

```
        <source>The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.</source>
        <translation>Frasa-laluan lama yang dimasukkan untuk dinyahsulitkan dompet tidak tepat. Ia mengandungi karakter nul (ie- byte kosong). Jika frasa-laluan disetkan dengan versi perisian sebelum ini hingga ke 25.0, sila cuba lagi hanya dengan karakter hingga ke — tapi tak termasuk — karakter nul pertama.</translation>
    
YES - The translation uses "hingga ke 25.0" which translates to "up to 25.0" but the source says "prior to 25.0". The correct translation should be "sebelum 25.0".

The old passphrase entered for the wallet decryption is incorrect. It contains a null character (ie - a zero byte). If the passphrase was set with a version of this software prior to 25.0, please try again with only the characters up to — but not including — the first null character.
Frasa-laluan lama yang dimasukkan untuk dinyahsulitkan dompet tidak tepat. Ia mengandungi karakter nul (ie- byte kosong). Jika frasa-laluan disetkan dengan versi perisian sebelum ini **sebelum** 25.0, sila cuba lagi hanya dengan karakter hingga ke — tapi tak termasuk — karakter nul pertama.
```

```
        <source>default wallet</source>
        <translation>dompet lalai
</translation>
    
YES, The translation contains a trailing space.
The correct translation is: dompet lalai
```

```
        <source>About %1</source>
        <translation>Mengenai%1</translation>
    
YES, The translation is missing a space after the '%' symbol.
About %1
```

```
        <source>Show information about %1</source>
        <translation>Menunjuk informasi mengenai%1</translation>
    
YES, The translation is problematic. The word "Menunjuk" means "pointing" or "indicating", which is not the correct translation for "Show". The correct translation for "Show" in this context would be "Tunjukkan". Also, there is a missing space between "mengenai" and "%1".

The correct translation is:
Tunjukkan maklumat mengenai %1
```

```
        <source>Show information about Qt</source>
        <translation>Menunjuk informasi megenai Qt</translation>
    
YES
The translation contains a spelling error. "megenai" should be "mengenai".
Menunjukkan informasi mengenai Qt
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>sulitkan kata laluan milik peribadi anda</translation>
    
YES - The translation incorrectly translates "private keys" as "password". The correct translation should be "kunci peribadi".
sulitkan kunci peribadi yang dimiliki dompet anda
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>sahkan mesej bersama alamat bitcoin anda untuk menunjukkan alamat ini anda punya</translation>
    
YES - The translation is grammatically incorrect and unnatural in Malay. The phrase "alamat ini anda punya" is awkward. A more natural translation would be "untuk membuktikan anda memiliki alamat tersebut" or "untuk membuktikan kepemilikan alamat tersebut".

Correct translation: Sahkan mesej dengan alamat Bitcoin anda untuk membuktikan anda memilikinya.
```

```
        <source>File</source>
        <translation>fail</translation>
    
YES
The translation is incorrect. The correct translation of "File" in Malay is "Fail".
<source>File</source>
<translation>Fail</translation>
```

```
        <source>Show the list of used sending addresses and labels</source>
        <translation>Tunjukkan senarai alamat dan label yang digunakan
</translation>
    
YES - The translation is missing the word "sending". The context implies "sending addresses".
Tunjukkan senarai alamat menghantar dan label yang digunakan
```

```
        <source>Hide</source>
        <translation>Sorok</translation>
    
YES, The translation is incorrect. The Malay word for "Hide" is "Sembunyikan" or "Copot". "Sorok" is a Sundanese word meaning "hide".
        <translation>Sembunyikan</translation>
```

```
        <source>Pre-syncing Headers (%1%)…</source>
        <translation>Pra-laras tajuk (%1%)...</translation>
    
YES
The word "Pra-laras" is not a standard Malay word and seems to be a mistranslation of "Pre-syncing". "Tajuk" is correct for "Headers". The "…" should be retained.

Correct translation: Pra-sinkronisasi pengepala (%1%)…
```

```
        <source>Cannot create new wallet, the software was compiled without sqlite support (required for descriptor wallets)</source>
        <translation>Dompet baru tidak boleh dicipta, perisian disusun tanpa sokongan sqlite (diperlukan untuk dinyahskrip dompet)</translation>
    
YES - The translation uses "dinyahskrip dompet" which directly translates to "descripted wallets" instead of "descriptor wallets". The term "descriptor wallets" is a technical term within Bitcoin and should ideally be kept as is or translated using a more appropriate technical equivalent if one exists in Malay.

NO
```

```
        <source>Copy transaction ID and output index</source>
        <translation>Salin ID transakksi dan indek keluaran </translation>
    
YES, The word "transakksi" is a typo, it should be "transaksi".
Salin ID transaksi dan indeks keluaran
```

```
        <source>Unlock unspent</source>
        <translation>Unlock tak dibelanjakan</translation>
    
YES, The translation is inaccurate and does not convey the intended meaning in the context of Bitcoin. The term "tak dibelanjakan" is not a standard or meaningful term in Malay for unspent in this context. The correct translation should refer to unspent outputs.

Correct translation: Buka kunci output yang belum dibelanjakan
```

```
        <source>Can't list signers</source>
        <translation>Penandatangan tidak boleh disenaraikan</translation>
    
YES, The translation is problematic as it has a slightly different meaning than the source text. The source text means that the system is unable to list the signers, whereas the translation implies that signers are not allowed to be listed.

Correct translation: Tidak dapat menyenaraikan penandatangan
```

```
        <source>Edit Address</source>
        <translation>Alamat</translation>
    
YES: The translation is incomplete. The English text "Edit Address" implies an action of modification or editing, which is not captured by the single word "Alamat" (Address).

Correct translation: Edit Alamat
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>Alihkan fail data ke dalam tab semasa</translation>
    
YES, The translation is problematic. It incorrectly translates "Export the data in the current tab to a file" as "Alihkan fail data ke dalam tab semasa" which means "Switch the data file into the current tab". The correct translation should be "Eksportkan data dalam tab semasa ke fail".

Correct translation: Eksportkan data dalam tab semasa ke fail
```
</details>
