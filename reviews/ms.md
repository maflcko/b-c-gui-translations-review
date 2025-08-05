# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ms</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bms%5D%20low%20quality)


```
        <source>Enter address or label to search</source>
        <translation>Masukkan alamat atau label untuk memulakan pencarian
</translation>
    
YES  
The translation changes the meaning of "to search" to "to start a search" ("untuk memulakan pencarian"), which is not accurate. The original simply instructs to enter an address or label to search, not to start or initiate searching explicitly. Also, there is an unnecessary trailing newline at the end.  

Correct translation:  
Masukkan alamat atau label untuk mencari
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>Alihkan fail data ke dalam tab semasa</translation>
    
YES  
The translation is inaccurate. The source means to export the data from the current tab to a file, but the translation says "Transfer the data file into the current tab," which reverses the meaning. A correct translation would be:  
Eksport data dalam tab semasa ke fail
```

```
        <source>These are your Bitcoin addresses for sending payments. Always check the amount and the receiving address before sending coins.</source>
        <translation>Ini adalah alamat Bitcoin anda untuk pembayaran. Periksa jumlah dan alamat penerima sebelum membuat penghantaran koin sentiasa.</translation>
    
YES  
The translation has misplaced the adverb "sentiasa" (always) at the end, which sounds awkward and changes the intended meaning. The original English instructs to "always check" before sending, so "sentiasa" should modify "periksa" (check) and appear earlier in the sentence for natural flow. Also, "membuat penghantaran koin" is less natural than "menghantar syiling" for "sending coins."

Correct translation:  
Ini adalah alamat Bitcoin anda untuk membuat pembayaran. Sentiasa periksa jumlah dan alamat penerima sebelum menghantar syiling.
```

```
        <source>Copy Address</source>
        <translation>Salin Aamat</translation>
    
YES
The Malay word for "address" in the Bitcoin context should be "Alamat," not "Aamat." The correct translation for "Copy Address" is "Salin Alamat."
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Amaran: Jika anda enkripkan dompet anda dan hilangkan frasa laluan, anda akan &lt;b&gt;ANDA AKAN HILANGKAN SEMUA BITCOIN ANDA&lt;/b&gt;!</translation>
    
YES  
The translation contains redundancy with "anda akan" (you will) being repeated twice, which is unnecessary and incorrect. The phrase should directly translate the warning without repeating the subject "anda". A better translation would be:

Correct translation:  
Amaran: Jika anda enkripkan dompet anda dan hilangkan frasa laluan, anda akan &lt;b&gt;HILANGKAN SEMUA BITCOIN ANDA&lt;/b&gt;!
```

```
        <source>About %1</source>
        <translation>Mengenai%1</translation>
    
YES
There is a whitespace issue between "Mengenai" and "%1". In Malay, there should be a space separating the word and the placeholder.

Correct translation:
Mengenai %1
```

```
        <source>Show information about %1</source>
        <translation>Menunjuk informasi mengenai%1</translation>
    
YES  
There is a spacing issue before the format specifier %1 in the translation. In Malay, a space should be present before %1. Also, "Menunjuk" is less appropriate in this context; "Tunjukkan" (imperative form of "show") is more commonly used for UI actions.

Correct translation:  
Tunjukkan informasi mengenai %1
```

```
        <source>Show information about Qt</source>
        <translation>Menunjuk informasi megenai Qt</translation>
    
YES  
The Malay word "Menunjuk" is incorrect in this context; it means "point to" or "show by pointing," which is not proper for "Show information about Qt." The correct verb should be "Tunjukkan," which means "Show" in commands or instructions. Also, "megenai" is misspelled; the correct word is "mengenai."

Correct translation:  
Tunjukkan maklumat mengenai Qt
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>sulitkan kata laluan milik peribadi anda</translation>
    
YES  
The translation is inaccurate and partially incorrect. The source talks about "Encrypt the private keys that belong to your wallet," but the translation says "sulitkan kata laluan milik peribadi anda" which means "make your personal password confidential," which is not the same.

Correct translation:  
Enkripsikan kekunci peribadi yang dimiliki oleh dompet anda
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>sahkan mesej bersama alamat bitcoin anda untuk menunjukkan alamat ini anda punya</translation>
    
YES
The translation contains several issues:
1. The first word "sahkan" should be capitalized as it begins the sentence.
2. "sahkan mesej bersama alamat bitcoin anda" is an unnatural phrase and not a good translation for "Sign messages with your Bitcoin addresses".
3. The phrase "untuk menunjukkan alamat ini anda punya" is awkward and not a natural way to say "to prove you own them" in Malay. Also, "alamat ini" ("this address") is singular and not plural to match "addresses".
4. "Bitcoin" should be capitalized.

A better translation would be:
"Tandatangani mesej dengan alamat Bitcoin anda untuk membuktikan anda memilikinya"
```

```
        <source>File</source>
        <translation>fail</translation>
    
YES  
In Malay, "file" when referring to a computer file or data file should be capitalized as "Fail" because it is a noun and typically capitalized in UI contexts. The lowercase "fail" might cause confusion as it means "fail" (verb) in English transliteration or resembles the English word "fail" meaning unsuccessful.

Correct translation:  
Fail
```

```
        <source>Show the list of used sending addresses and labels</source>
        <translation>Tunjukkan senarai alamat dan label yang digunakan
</translation>
    
YES  
The translation omits the mention of "sending" in "sending addresses," which is important in the Bitcoin context to distinguish from other types of addresses (e.g., receiving addresses). The full meaning should be preserved.

Correct translation:  
Tunjukkan senarai alamat penghantaran dan label yang digunakan
```

```
        <source>Hide</source>
        <translation>Sorok</translation>
    
YES
The Malay word for "Hide" is "Sembunyi" or "Sorokkan" depending on context. "Sorok" is informal and may be considered less appropriate in formal contexts like software UI.

Correct translation:  
Sembunyi
```

```
        <source>Pre-syncing Headers (%1%)…</source>
        <translation>Pra-laras tajuk (%1%)...</translation>
    
YES  
The translation uses "Pra-laras tajuk," which is incorrect in Malay. "Pre-syncing" should be translated as "Pra-penyegerakan" or "Sedang pra-penyegerakan." Additionally, "tajuk" is not the correct term for "headers" in the Bitcoin/blockchain context; "kepala blok" or simply "header" (transliterated) is more appropriate. The ellipsis in Malay is typically three dots "...", matching the source format, but it's represented differently here as "...". The spacing is correct.

Correct translation:  
Pra-penyegerakan header (%1%)...
```

```
        <source>Cannot create new wallet, the software was compiled without sqlite support (required for descriptor wallets)</source>
        <translation>Dompet baru tidak boleh dicipta, perisian disusun tanpa sokongan sqlite (diperlukan untuk dinyahskrip dompet)</translation>
    
YES
The translation inaccurately translates "descriptor wallets" as "dinyahskrip dompet," which means "decoded wallets," not "descriptor wallets." The term "descriptor wallets" should be kept as is or properly translated to maintain the original meaning, as it is a technical term in Bitcoin context.

Correct translation:
Dompet baru tidak boleh dicipta, perisian disusun tanpa sokongan sqlite (diperlukan untuk descriptor wallets)
```

```
        <source>Copy transaction ID and output index</source>
        <translation>Salin ID transakksi dan indek keluaran </translation>
    
YES  
There is a typo in the word "transakksi" which should be "transaksi". Also, there is a trailing space at the end of the translation which should be removed.

Correct translation:  
Salin ID transaksi dan indeks keluaran
```

```
        <source>Unlock unspent</source>
        <translation>Unlock tak dibelanjakan</translation>
    
YES
The translation mixes English and Malay improperly. "Unlock tak dibelanjakan" is incorrect; "tak" is informal and "dibelanjakan" means "spent." The correct phrase should translate "Unlock unspent" as "Buka kunci yang tidak dibelanjakan" or more succinctly "Buka kunci belum dibelanjakan."

Correct translation:
Buka kunci belum dibelanjakan
```

```
        <source>Can't list signers</source>
        <translation>Penandatangan tidak boleh disenaraikan</translation>
    
YES  
The translation "Penandatangan tidak boleh disenaraikan" means "Signers are not allowed to be listed," which changes the meaning of "Can't list signers." The source expresses an inability or failure to list signers, not a prohibition. A more accurate Malay translation would be:  
"Tak dapat menyenaraikan penandatangan" or "Tidak dapat menyenaraikan penandatangan"
```

```
        <source>Edit Address</source>
        <translation>Alamat</translation>
    
YES
The translation "Alamat" means "Address" but the source text "Edit Address" implies an action to modify the address. The correct translation should convey this action, for example:

Edit Address = "Sunting Alamat"
```

```
        <source>Export the data in the current tab to a file</source>
        <translation>Alihkan fail data ke dalam tab semasa</translation>
    
YES  
The translation is inaccurate. The source means to export the data from the current tab to a file, but the translation says "Transfer the data file into the current tab," which reverses the meaning. A correct translation would be:  
Eksport data dalam tab semasa ke fail
```
</details>
