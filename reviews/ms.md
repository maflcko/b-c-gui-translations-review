# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ms</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bms%5D%20low%20quality)


```
        <source>Enter address or label to search</source>
        <translation>Masukkan alamat atau label untuk memulakan pencarian
</translation>
    
YES
There is a minor issue: an unwanted line break at the end of the translation, which can cause formatting issues. Additionally, "untuk memulakan pencarian" is slightly less natural than "untuk dicari" or "untuk carian". A more accurate and concise translation would be:

Correct translation:
Masukkan alamat atau label untuk dicari
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>Alihkan fail data ke dalam tab semasa</translation>
    
YES
The translation is incorrect. The original English means to export the data from the current tab to a file, but the Malay translation says to "transfer the data file into the current tab." The direction of the action is reversed.

Correct translation:
Eksport data dalam tab semasa ke fail
```

```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>Ini adalah alamat Bitcoin anda untuk pembayaran. Periksa jumlah dan alamat penerima sebelum membuat penghantaran koin sentiasa.</translation>
    
YES
The translation is understandable but the order of the word "sentiasa" (always) is incorrect, and "penghantaran koin" is an awkward phrase. Also, "pembayaran" on its own may not sufficiently convey "sending payments," and "koin" is less standard than "syiling" or "coin" in localized contexts. The tone/order can be improved for naturalness and accuracy.

Correct translation:
Ini ialah alamat Bitcoin anda untuk menghantar pembayaran. Sentiasa semak jumlah dan alamat penerima sebelum menghantar syiling.
```

```
        <source>Copy Address</source>
        <translation>Salin Aamat</translation>
    
YES
There is a spelling error in the Malay word "Aamat". The correct word for "address" in Malay is "Alamat".

Correct translation:
Salin Alamat
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Amaran: Jika anda enkripkan dompet anda dan hilangkan frasa laluan, anda akan &lt;b&gt;ANDA AKAN HILANGKAN SEMUA BITCOIN ANDA&lt;/b&gt;!</translation>
    
YES
The translation contains redundancy in the warning ("anda akan... ANDA AKAN HILANGKAN..."), and is a bit awkward. The phrase should be more concise and match the original meaning. Additionally, "enkripkan" is acceptable, though "menyulitkan" is more standard in Malay.

Correct translation:
Amaran: Jika anda menyulitkan dompet anda dan kehilangan frasa laluan, anda akan &lt;b&gt;KEHILANGAN SEMUA BITCOIN ANDA&lt;/b&gt;!
```

```
        <source>About %1</source>
        <translation>Mengenai%1</translation>
    
YES
There is a whitespace formatting issue. The Malay translation "Mengenai%1" is missing a space between "Mengenai" and the variable "%1".

Correct translation:
Mengenai %1
```

```
        <source>Show information about %1</source>
        <translation>Menunjuk informasi mengenai%1</translation>
    
YES
There is a spacing issue: there should be a space between "mengenai" and "%1". Additionally, "Menunjuk" is less natural than "Tunjukkan", which is the appropriate imperative form for "Show". The word "informasi" is acceptable, but "maklumat" is also a commonly used term in Malay for "information".

Correct translation:
Tunjukkan maklumat mengenai %1
```

```
        <source>Show information about Qt</source>
        <translation>Menunjuk informasi megenai Qt</translation>
    
YES
There is a spelling error in the Malay translation: "menunjuk" should be "tunjuk" or more accurately "Papar", and "informasi" is acceptable but "maklumat" is more standard in Malay. Also, "mengenai" is misspelled as "megenai".

Correct translation:
Papar maklumat mengenai Qt
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>sulitkan kata laluan milik peribadi anda</translation>
    
YES
The translation has multiple issues:
1. The meaning is incorrect: "sulitkan kata laluan milik peribadi anda" translates to "encrypt your personal password," which is not the same as "Encrypt the private keys that belong to your wallet."
2. The term "private keys" is not appropriately translated, and the original sentence is about private keys, not passwords.

Correct translation:
Enkripsikan kunci peribadi yang dimiliki oleh dompet anda
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>sahkan mesej bersama alamat bitcoin anda untuk menunjukkan alamat ini anda punya</translation>
    
YES
The translation is understandable but is not entirely accurate and contains some issues:
- Capitalization should be proper at the beginning of the sentence.
- "Sahkan mesej bersama alamat bitcoin anda" is not a precise translation for "Sign messages with your Bitcoin addresses".
- "untuk menunjukkan alamat ini anda punya" is awkward and not the best way to express "to prove you own them" in Malay.
- The word "Bitcoin" should be capitalized for consistency.

Correct translation:
Tandatangani mesej dengan alamat Bitcoin anda untuk membuktikan bahawa anda memilikinya
```

```
        <source>File</source>
        <translation>fail</translation>
    
YES
The Malay translation should use an uppercase 'F' to match the original capitalization. Also, "fail" is the correct translation for "file" in Malay, but capitalization should be preserved for UI menu labels.

Correct translation:
Fail
```

```
        <source>Show the list of used sending addresses and labels</source>
        <translation>Tunjukkan senarai alamat dan label yang digunakan
</translation>
    
YES
The translation omits "sending" from "used sending addresses", which should be specified to reflect the source accurately. Also, there is an unnecessary newline at the end of the translation.

Correct translation:
Tunjukkan senarai alamat penghantaran dan label yang digunakan
```

```
        <source>Pre-syncing Headers (%1%)…</source>
        <translation>Pra-laras tajuk (%1%)...</translation>
    
YES
The translation "Pra-laras tajuk" is not standard Malay and appears to be machine-generated or directly copied from other languages (e.g., "pra-laras" is not common Malay usage for "pre-syncing"). Also, the ellipsis uses three dots "..." instead of "…", and the %1 format specifier is doubled (%1%) in both source and translation which may be an error, but if this doubling is intentional, it's okay.

A more accurate translation would be:
Pra-menyegerak Tajuk (%1%)…

If the term "Pre-syncing" is to be localized as "pra-menyegerak". Alternatively, "Sedang pra-menyegerakkan tajuk (%1%)…" is more natural.

Correct translation:
Pra-menyegerak tajuk (%1%)…
```

```
        <source>Cannot create new wallet, the software was compiled without sqlite support (required for descriptor wallets)</source>
        <translation>Dompet baru tidak boleh dicipta, perisian disusun tanpa sokongan sqlite (diperlukan untuk dinyahskrip dompet)</translation>
    
YES
The translation has a problematic term: "dinyahskrip dompet" is not a correct or standard translation for "descriptor wallets". Also, "tidak boleh dicipta" is awkward; "tidak dapat dicipta" or "tidak dapat dibuat" is better.

Correct translation:
Dompet baru tidak dapat dicipta, perisian telah disusun tanpa sokongan sqlite (diperlukan untuk dompet deskriptor)
```

```
        <source>Copy transaction ID and output index</source>
        <translation>Salin ID transakksi dan indek keluaran </translation>
    
YES
There is a typo in the Malay word "transakksi" (should be "transaksi") and an unnecessary space at the end of the translation.

Correct translation:
Salin ID transaksi dan indeks keluaran
```

```
        <source>Unlock unspent</source>
        <translation>Unlock tak dibelanjakan</translation>
    
YES
The translation is not fully accurate. "Unlock" should be translated to "Buka kunci" in Malay. The direct translation "Unlock tak dibelanjakan" mixes English and Malay in an unnatural way ("Unlock" is kept in English).

Correct translation:
Buka kunci yang belum dibelanjakan
```

```
        <source>Edit Address</source>
        <translation>Alamat</translation>
    
YES
The translation omits the verb "Edit" and only includes "Alamat", which means "Address". It fails to convey the original meaning.

Correct translation:
Edit Alamat
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>Alihkan fail data ke dalam tab semasa</translation>
    
YES
The translation is incorrect. The original English means to export the data from the current tab to a file, but the Malay translation says to "transfer the data file into the current tab." The direction of the action is reversed.

Correct translation:
Eksport data dalam tab semasa ke fail
```
</details>

Number of issues: 18.
