# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>id</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bid%5D%20low%20quality)


```
        <source>default wallet</source>
        <translation>wallet default</translation>
    
YES
The translation has the word order reversed. In Indonesian, the adjective typically comes before the noun, so "default wallet" should be translated as "dompet default" rather than "wallet default". Also, the term "wallet" can be translated as "dompet" in the Bitcoin context.

Correct translation:
dompet default
```

```
        <source>Sign message…</source>
        <translation>Tanda tangani dan kirim pessan...</translation>
    
YES  
The translation inaccurately adds "dan kirim" (and send), which is not present in the source text "Sign message…". Also, "pessan" is a misspelling; the correct word is "pesan". Additionally, the ellipsis in the source uses a single Unicode character (…) but the translation uses three dots (...). It is better to keep the same ellipsis character.  

Correct translation:  
Tanda tangani pesan…
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Muat transaksi Bitcoin yang ditandatangani seperapat</translation>
    
YES  
The phrase "seperapat" is incorrect in this context. "Partially signed" should be translated as "yang ditandatangani sebagian" or "yang ditandatangani parsial" to accurately convey the meaning of a partially signed transaction in Bitcoin terminology.

Correct translation:  
Muat transaksi Bitcoin yang ditandatangani sebagian
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Muat transaksi Bitcoin yang ditandatangani seperapat dari clipboard</translation>
    
YES  
There is a typo in the translation: "seperapat" should be "sebagian" or "parsial" to correctly translate "Partially". "Seperapat" literally means "a quarter", which is incorrect in this context.

Correct translation:  
Muat transaksi Bitcoin yang ditandatangani sebagian dari clipboard
```

```
        <source>Load Wallets</source>
        <extracomment>Title of progress window which is displayed when wallets are being loaded.</extracomment>
        <translation>Tampilkan Dompet</translation>
    
YES  
The English source "Load Wallets" refers to the action of loading or opening wallets, whereas the Indonesian translation "Tampilkan Dompet" means "Show Wallets," which changes the meaning. A better translation that captures the sense of loading wallets (i.e., initializing or opening them) would be:

"Muat Dompet"
```

```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>Memindahkan dompet akan mengubah dompet ini menjadi satu atau beberapa dompet deskriptor. Cadangan dompet baru perlu dibuat.
Jika dompet ini berisi skrip yang hanya bisa dilihat, dompet baru akan dibuat yang berisi skrip tersebut.
Jika dompet ini berisi skrip yang dapat dipecahkan tetapi tidak dapat ditonton, dompet yang berbeda dan baru akan dibuat yang berisi skrip tersebut.

Proses migrasi akan mencadangkan dompet sebelum melakukan pemindahan. Fail cadangan ini akan diberi nama -.legacy.bak dan dapat ditemukan di direktori untuk dompet ini. Jika terjadi gagal pemindahan, cadangan dapat dipulihkan dengan fungsi "Pulihkan Dompet".</translation>
    
YES
The translation has multiple issues:
1. The word "descriptor" is misspelled as "deskriptor" (should be "deskriptor" is acceptable in Bahasa Indonesia, but it is more common to use "deskriptor" or "deskriptor dompet" is acceptable; however, it would be better to keep "deskriptor" since it is a technical term).
2. The phrase "watchonly scripts" was translated literally as "skrip yang hanya bisa dilihat," which is not a standard or clear term in Indonesian Bitcoin terminology. "Watch-only" is usually kept as "watch-only" or translated as "skrip watch-only" to keep clarity.
3. In the sentence about "solvable but not watched scripts," the phrase "tidak dapat ditonton" is inappropriate because "ditonton" literally means "watched" in the sense of viewing a video. It should be "tidak dipantau" or better "tidak diawasi" or keeping "skrip yang dapat dipecahkan tapi tidak dipantau".
4. The backup file name part is incomplete: the translation shows "Fail cadangan ini akan diberi nama -.legacy.bak" missing the placeholders <wallet name> and <timestamp>. The placeholders must be included exactly as in the source.
5. The word "file" should be "file" or "berkas," but "file" is common.
6. "Jika terjadi gagal pemindahan" is awkward; better phrasing: "Jika terjadi migrasi yang salah" or "Jika migrasi berjalan tidak benar."
7. "Fungsi" usually is "fitur" or "fungsi," but "fungsi" is acceptable.

Correct translation:

Memigrasikan dompet akan mengubah dompet ini menjadi satu atau beberapa dompet deskriptor. Cadangan dompet baru perlu dibuat.  
Jika dompet ini berisi skrip watch-only, dompet baru akan dibuat yang berisi skrip watch-only tersebut.  
Jika dompet ini berisi skrip yang dapat dipecahkan tetapi tidak dipantau, dompet baru yang berbeda akan dibuat yang berisi skrip tersebut.  

Proses migrasi akan membuat cadangan dompet sebelum migrasi. File cadangan ini akan dinamai &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak dan dapat ditemukan di direktori dompet ini. Jika terjadi migrasi yang salah, cadangan dapat dipulihkan dengan fitur "Pulihkan Dompet".

---

Final corrected translation:

<translation>Memigrasikan dompet akan mengubah dompet ini menjadi satu atau beberapa dompet deskriptor. Cadangan dompet baru perlu dibuat.  
Jika dompet ini berisi skrip watch-only, dompet baru akan dibuat yang berisi skrip watch-only tersebut.  
Jika dompet ini berisi skrip yang dapat dipecahkan tetapi tidak dipantau, dompet baru yang berbeda akan dibuat yang berisi skrip tersebut.  

Proses migrasi akan membuat cadangan dompet sebelum migrasi. File cadangan ini akan dinamai &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak dan dapat ditemukan di direktori dompet ini. Jika terjadi migrasi yang salah, cadangan dapat dipulihkan dengan fitur "Pulihkan Dompet".</translation>
```

```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Skrip hanya lihat telah diimigrasikan ke dompet baru yang bernama '%1'.</translation>
    
YES  
The translation is incomplete and inaccurate. The source refers to "Solvable but not watched scripts" which means scripts that can be solved but are not under watch, while the translation "Skrip hanya lihat" means "scripts just watched" or "scripts only watching," missing the "solvable but not watched" meaning. Also, the phrase "telah diimigrasikan ke dompet baru yang bernama '%1'" is correct and corresponds well to the latter part.

Correct translation:  
"Skrip yang dapat diselesaikan tetapi tidak dipantau telah dipindahkan ke dompet baru yang bernama '%1'."
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Perlihatkan apabila proxy SOCKS5 default digunakan untuk berhungan dengan orang lain lewat tipe jaringan ini.</translation>
    
YES  
There is a typo in the word "berhungan" which should be "berhubungan."  
Also, "Perlihatkan" is a command ("Show"), but the English sentence is descriptive ("Shows if..."), so a better translation uses indicative mood like "Menampilkan" or "Menunjukkan."  
Correct translation:  
Menunjukkan apabila proxy SOCKS5 default digunakan untuk berhubungan dengan peer melalui tipe jaringan ini.
```

```
        <source>Minimize instead of exit the application when the window is closed. When this option is enabled, the application will be closed only after selecting Exit in the menu.</source>
        <translation>Minimalisasi aplikasi ketika jendela ditutup. Ketika pilihan ini dipilih, aplikasi akan menutup seluruhnya jika anda memilih Keluar di menu yang tersedia.</translation>
    
YES
The translation does not accurately reflect the meaning of the source text. The source implies that the app minimizes (to tray) instead of exiting when the window is closed, and only exits when explicitly selecting Exit. The translation wrongly says "Minimize the application when the window is closed" (correct) but then incorrectly states "the application will close completely if you select Exit", which is fine, but it fails to clarify that it does NOT exit on window close (which is the key point).

Also, in the source: "Minimize instead of exit the application when the window is closed." vs translation: "Minimalisasi aplikasi ketika jendela ditutup." (Minimize the application when the window is closed) - this is okay.

Next sentence in source: "When this option is enabled, the application will be closed only after selecting Exit in the menu." vs translation: "Ketika pilihan ini dipilih, aplikasi akan menutup seluruhnya jika anda memilih Keluar di menu yang tersedia." (When this option is selected, the application will close completely if you select Exit in the available menu) – kind of okay but the original says "will be closed ONLY after selecting Exit," emphasizing that closing the window does NOT exit the app, but the translation does not clearly place this contrast.

A clearer and more natural translation might be:

"Minimalisasi aplikasi alih-alih keluar saat jendela ditutup. Ketika opsi ini diaktifkan, aplikasi hanya akan benar-benar keluar setelah memilih Keluar di menu."

This preserves the "instead of exit" meaning.

Additionally, "Minimalisasi aplikasi" is understandable but "perkecil" or "sembunyikan" might sound more natural than "minimalisasi" which is a direct calque of "minimize". However, "minimalisasi" is widely used in Indonesian IT contexts.

Therefore, the correction is primarily clarifying the "instead of exit" part and the timing of app exit.

Correct translation:  
Minimalisasi alih-alih keluar aplikasi saat jendela ditutup. Ketika opsi ini diaktifkan, aplikasi hanya akan benar-benar keluar setelah memilih Keluar di menu.
```

```
        <source>Options set in this dialog are overridden by the command line:</source>
        <translation>Set opsi pengaturan pada jendela dialog ini tertutup oleh baris perintah:</translation>
    
YES  
The phrase "tertutup oleh" is incorrect and does not convey the meaning of "overridden by" in this context. A more accurate translation would use "dianulir oleh" or "digantikan oleh" to indicate overriding.

Correct translation:  
Opsi yang diatur dalam dialog ini dianulir oleh baris perintah:
```

```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>Set nomor thread script verifikasi. Nilai negatif sesuai dengan core yang tidak ingin digunakan di dalam system.</translation>
    
YES  
The translation has some issues:

1. The term "Set" is untranslated, it should be translated to "Atur" or "Tetapkan" for natural Indonesian.  
2. "nomor thread script verifikasi" is awkward; a more natural phrasing is "jumlah thread verifikasi skrip".  
3. "Nilai negatif sesuai dengan core yang tidak ingin digunakan di dalam system." is not precise. The original means that negative values specify how many cores you want to leave free for the system, not just "cores not used". It should clearly convey that negative values indicate how many cores to leave available for the system.  
4. "system" should be "sistem" (correct Indonesian spelling).  
5. The sentence should be a complete instruction, possibly two sentences for clarity.

Correct translation:  
"Atur jumlah thread verifikasi skrip. Nilai negatif menunjukkan jumlah core yang ingin Anda sisakan agar tetap bebas untuk sistem."
```

```
        <source>Spend unconfirmed change</source>
        <translation>Perubahan saldo untuk transaksi yang belum dikonfirmasi</translation>
    
YES  
The translation is inaccurate and too verbose. The source "Spend unconfirmed change" literally means using the unconfirmed change in a Bitcoin transaction. The given translation "Perubahan saldo untuk transaksi yang belum dikonfirmasi" translates back as "Balance changes for transactions that are not yet confirmed," which changes the meaning and adds unnecessary words.

A better translation would be more direct and concise, for example:  
"Gunakan perubahan belum dikonfirmasi"  
or  
"Belanjakan kembalian belum dikonfirmasi"  
(assuming "change" refers to "kembalian" in the Bitcoin transaction context).

Correct translation:  
<translation>Belanjakan kembalian belum dikonfirmasi</translation>
```

```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>PSBT berbayar disalin ke clipboard</translation>
    
YES  
The phrase "Fee-bump PSBT copied to clipboard" indicates that a PSBT (Partially Signed Bitcoin Transaction) with an increased fee has been copied to the clipboard. The translation "PSBT berbayar disalin ke clipboard" translates back as "paid PSBT copied to clipboard," which loses the nuance of "fee-bump" (meaning increasing the fee, not just any paid fee).

A better translation would keep the concept of fee bump, for example:  
"PSBT dengan kenaikan biaya disalin ke clipboard"  
or  
"PSBT fee-bump disalin ke clipboard" (loanword acceptable if no concise term exists).  

Correct translation:  
PSBT dengan kenaikan biaya disalin ke clipboard
```

```
        <source>Error loading wallet. Wallet requires blocks to be downloaded, and software does not currently support loading wallets while blocks are being downloaded out of order when using assumeutxo snapshots. Wallet should be able to load successfully after node sync reaches height %s</source>
        <translation>Eror saat membuka dompet. Dompet memerlukan blok untuk diunduh, dan piranti lunak saat ini tidak mendukung membuka dompet saat blok yang diunduh tidak tersedia saat memakai snapshot utxo yang diasumsikan. Dompet seharusnya dapat berhasil dibuka sesudah sinkronisasi node mencapai ketinggian %s</translation>
    
YES  
The translation contains some inaccurate and unnatural phrases and minor errors:

- "Eror" should be spelled "Error" or preferably "Kesalahan" in Indonesian.
- "Blok yang diunduh tidak tersedia" is misleading; the source says "blocks being downloaded out of order," which means blocks are downloaded in the wrong sequence. It should be translated as "blok diunduh tidak berurutan."
- "Piranti lunak" is acceptable but "perangkat lunak" is more standard.
- The phrase "saat memakai snapshot utxo yang diasumsikan" is unclear. A better translation for "when using assumeutxo snapshots" is "ketika menggunakan snapshot assumeutxo."
- "ketinggian" is a literal translation of "height" but in blockchain context, "tinggi blok" is better understood.
- The sentence overall is overly literal and can be improved for natural flow and clarity.

Correct translation:  
"Kesalahan saat memuat dompet. Dompet membutuhkan blok untuk diunduh, dan perangkat lunak saat ini tidak mendukung memuat dompet saat blok sedang diunduh tidak berurutan ketika menggunakan snapshot assumeutxo. Dompet seharusnya dapat berhasil dimuat setelah sinkronisasi node mencapai tinggi blok %s."
```

```
        <source>Specified -blockmaxweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Detailnya - nilai block maksimal ( %d ) melebihi nilai awal maksimal block ( %d )</translation>
    
YES
The translation is inaccurate and contains unnecessary spaces around format specifiers %d, which should be preserved without added spaces. Also, the terms should convey the technical meaning more precisely:

- "Specified -blockmaxweight (%d)" should be translated as "Blokmaxweight yang ditentukan (%d)"
- "consensus maximum block weight (%d)" should be "berat maksimal blok konsensus (%d)"
- The current translation uses "nilai awal maksimal block," which inaccurately translates "consensus maximum block weight."

Correct translation:
"Blokmaxweight yang ditentukan (%d) melebihi berat maksimal blok konsensus (%d)"
```

```
        <source>
Unable to restore backup of wallet.</source>
        <translation>
Tidak dapat memulihkan cadangan dompet..</translation>
    
YES  
The translation contains an extra period at the end ("dompet..") which is a formatting issue. Additionally, the leading newline in the <source> and <translation> should be removed for consistency and cleanliness.

Correct translation:  
Tidak dapat memulihkan cadangan dompet.
```

```
        <source>Unsupported global logging level %s=%s. Valid values: %s.</source>
        <translation>Tingkat penebangan global yang tidak didukung %s = %s. Nilai yang valid: %s.</translation>
    
YES  
There are spacing issues around the equal sign. In the source, "%s=%s" has no spaces around '=' but the translation has spaces ("%s = %s"). The format specifiers are correctly copied, but the spacing should match the source for consistency and correctness. Also, "penebangan" is a literal translation of "logging" meaning "logging trees," which is incorrect in this context. The proper term in Indonesian for software logging is "pencatatan" or "logging" (used as is).

Correct translation:  
Tingkat pencatatan global yang tidak didukung %s=%s. Nilai yang valid: %s.
```

```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>menerima estimasi biaya basi tidak didukung pada %s rantai.</translation>
    
YES  
The translation is somewhat literal and awkward in Indonesian. "acceptstalefeeestimates" is likely a technical term and might be left as-is or capitalized. Also, "biaya basi" is an odd phrase; a better term would be "biaya sudah kedaluwarsa" or "biaya kadaluarsa," but since it's a technical term "stalefeeestimates," it might be better to keep it untranslated or as "estimasi biaya usang." Moreover, the sentence structure should be more natural: "tidak didukung di rantai %s" is better word order in Indonesian than "pada %s rantai."

A better translation would be:  
"acceptstalefeeestimates tidak didukung di rantai %s."

If "acceptstalefeeestimates" is to be translated, then:  
"acceptstalefeeestimates tidak didukung pada rantai %s."

But usually, command or option names are left untranslated.

Correct translation:  
acceptstalefeeestimates tidak didukung di rantai %s.
```
</details>
