# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>id</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bid%5D%20low%20quality)


```
        <source>default wallet</source>
        <translation>wallet default</translation>
    
YES
The translation does not follow the Indonesian grammatical structure. In Indonesian, the correct word order is "default" (as an adjective or descriptor) should follow the noun if kept in English, but "wallet" itself should ideally be translated. The accepted term for "wallet" in Indonesian is "dompet", and "default" can be left as-is for technical context, or translated to "bawaan" or "standar":

Correct translation:
dompet default

Alternatively, if full localization is preferred:
dompet bawaan

Either "dompet default" or "dompet bawaan" would be more appropriate than "wallet default".
```

```
        <source>Sign message…</source>
        <translation>Tanda tangani dan kirim pessan...</translation>
    
YES
The translation contains an error: "pessan" should be "pesan." Also, "dan kirim" means "and send," but the original only says "Sign message…", not "Sign and send message…". So, the translation is inaccurate.

Correct translation:
Tandatangani pesan...
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Muat transaksi Bitcoin yang ditandatangani seperapat</translation>
    
YES
The phrase "ditandatangani seperapat" is incorrect. "Seperapat" means "a quarter," not "partially." The correct translation for "Partially Signed Bitcoin Transaction" is "Transaksi Bitcoin yang Ditandatangani Sebagian".

Correct translation:
Muat Transaksi Bitcoin yang Ditandatangani Sebagian
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Muat transaksi Bitcoin yang ditandatangani seperapat dari clipboard</translation>
    
YES
The translation is inaccurate. "Ditandatangani seperapat" is incorrect; "Partially Signed" should be translated as "yang ditandatangani sebagian," not "seperapat" (which means "a quarter").

Correct translation:
Muat transaksi Bitcoin yang ditandatangani sebagian dari clipboard
```

```
        <source>Load Wallets</source>
        <extracomment>Title of progress window which is displayed when wallets are being loaded.</extracomment>
        <translation>Tampilkan Dompet</translation>
    
YES
The translation is inaccurate. "Load Wallets" should be translated as "Muat Dompet" or "Memuat Dompet", not "Tampilkan Dompet" which means "Show Wallets". "Tampilkan" is not appropriate in the context of loading or initializing data.

Correct translation:
Muat Dompet
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
There are several issues in the translation:

1. The phrase "skrip yang hanya bisa dilihat" for "watchonly scripts" is an awkward and inaccurate translation. The standard is "skrip hanya-baca".
2. "skrip yang dapat dipecahkan tetapi tidak dapat ditonton" for "solvable but not watched scripts" is also awkward. It should be "skrip yang dapat dipecahkan tetapi tidak diawasi".
3. The file name "<wallet name>-<timestamp>.legacy.bak" was omitted and replaced with "-.legacy.bak", which is an error.
4. The term "fail cadangan" mixes Indonesian and Malay; "fail" should be "file".
5. The translation "gagal pemindahan" for "incorrect migration" is inaccurate. Should be "migrasi yang salah" or "migrasi yang tidak benar".
6. There is an unnecessary line-wrapping in the translation, but this may be acceptable in UI contexts, though keeping the structure similar is preferred.

Correct translation:
Memigrasikan dompet akan mengonversi dompet ini menjadi satu atau beberapa dompet deskriptor. Cadangan dompet baru perlu dibuat.
Jika dompet ini berisi skrip hanya-baca, dompet baru akan dibuat yang berisi skrip hanya-baca tersebut.
Jika dompet ini berisi skrip yang dapat dipecahkan tetapi tidak diawasi, dompet baru yang berbeda akan dibuat yang berisi skrip tersebut.

Proses migrasi akan membuat cadangan dompet sebelum melakukan migrasi. File cadangan ini akan dinamai &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak dan dapat ditemukan di direktori untuk dompet ini. Jika terjadi migrasi yang salah, cadangan dapat dipulihkan dengan fungsi "Pulihkan Dompet".
```

```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Skrip hanya lihat telah diimigrasikan ke dompet baru yang bernama '%1'.</translation>
    
YES
The translation is inaccurate. The phrase "Solvable but not watched scripts" is mistranslated as "Skrip hanya lihat", which means "watch-only scripts". The idea of "solvable" (those we can sign/spend) but "not watched" (not in watch-only list) is lost.

Correct translation:
Skrip yang dapat diselesaikan tetapi tidak dipantau telah dipindahkan ke dompet baru bernama '%1'.
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Perlihatkan apabila proxy SOCKS5 default digunakan untuk berhungan dengan orang lain lewat tipe jaringan ini.</translation>
    
YES
The translation contains a typo ("berhungan" should be "berhubungan"), and "orang lain" is better translated as "peer" in Bitcoin contexts, e.g., "rekan" or simply "peer." The translation should also maintain the phrase "supplied default SOCKS5 proxy" accurately, and "shows" should be "Menunjukkan" rather than "Perlihatkan" (which is more an imperative form). 

Correct translation:
Menunjukkan apakah proxy SOCKS5 default yang diberikan digunakan untuk menghubungi peer melalui tipe jaringan ini.
```

```
        <source>Minimize instead of exit the application when the window is closed. When this option is enabled, the application will be closed only after selecting Exit in the menu.</source>
        <translation>Minimalisasi aplikasi ketika jendela ditutup. Ketika pilihan ini dipilih, aplikasi akan menutup seluruhnya jika anda memilih Keluar di menu yang tersedia.</translation>
    
YES
The translation does not accurately reflect the original meaning. The English source explains that when this option is enabled, closing the window minimizes the app instead of exiting; the app is only fully closed when Exit is picked from the menu. The Indonesian translation suggests that the app will fully close when "Keluar" is chosen, but does not specify that, with this option, closing the window will only minimize the app.

Correct translation:
Minimalkan aplikasi alih-alih keluar ketika jendela ditutup. Ketika opsi ini diaktifkan, aplikasi hanya akan ditutup sepenuhnya setelah memilih Keluar di menu.
```

```
        <source>Options set in this dialog are overridden by the command line:</source>
        <translation>Set opsi pengaturan pada jendela dialog ini tertutup oleh baris perintah:</translation>
    
YES
The translation is slightly inaccurate and awkward. The phrase "tertutup oleh baris perintah" does not correctly convey the meaning of "overridden by the command line." The correct translation should use "digantikan oleh baris perintah" or "diabaikan karena baris perintah".

Correct translation:
Opsi yang diatur di dialog ini akan digantikan oleh baris perintah:
```

```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>Set nomor thread script verifikasi. Nilai negatif sesuai dengan core yang tidak ingin digunakan di dalam system.</translation>
    
YES
The translation is understandable but not fully accurate, and the English grammar was not well adapted to Indonesian. Also, "Set" should be "Atur," and "nomor thread script verifikasi" should be "jumlah thread verifikasi skrip." "System" should be "sistem." The explanation about negative values is imprecise—"core yang tidak ingin digunakan" is not clear enough. It should reflect "the number of cores you want to leave free to the system" (i.e., "jumlah inti yang ingin Anda biarkan bebas untuk sistem").

Correct translation:
Atur jumlah thread verifikasi skrip. Nilai negatif menunjukkan jumlah inti yang ingin Anda biarkan bebas untuk sistem.
```

```
        <source>Spend unconfirmed change</source>
        <translation>Perubahan saldo untuk transaksi yang belum dikonfirmasi</translation>
    
YES
The translation is inaccurate and somewhat verbose. The English "Spend unconfirmed change" refers specifically to the option of allowing the use of unconfirmed "change" (the leftover output from previous transactions) as input in a new transaction. The given translation refers to "Perubahan saldo untuk transaksi yang belum dikonfirmasi" which means "Change in balance for transactions that have not been confirmed," which is misleading.

Correct translation:
Gunakan kembalian yang belum dikonfirmasi
```

```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>PSBT berbayar disalin ke clipboard</translation>
    
YES
The translation is inaccurate. "Fee-bump" refers to increasing the transaction fee, not just "berbayar" (which means "paid" or "with fee"). The phrase "PSBT berbayar" does not convey the meaning of a PSBT (Partially Signed Bitcoin Transaction) that has been modified to bump the fee.

Correct translation:
PSBT dengan peningkatan biaya disalin ke clipboard
```

```
        <source>Error loading wallet. Wallet requires blocks to be downloaded, and software does not currently support loading wallets while blocks are being downloaded out of order when using assumeutxo snapshots. Wallet should be able to load successfully after node sync reaches height %s</source>
        <translation>Eror saat membuka dompet. Dompet memerlukan blok untuk diunduh, dan piranti lunak saat ini tidak mendukung membuka dompet saat blok yang diunduh tidak tersedia saat memakai snapshot utxo yang diasumsikan. Dompet seharusnya dapat berhasil dibuka sesudah sinkronisasi node mencapai ketinggian %s</translation>
    
YES
The translation contains some inaccuracies:
- "Error loading wallet" should be "Galat saat memuat dompet" or "Kesalahan saat memuat dompet" instead of "Eror saat membuka dompet" (which uses 'Eror', an irregular spelling, and "membuka" means "open" rather than "load").
- "Blocks are being downloaded out of order" is mistranslated as "blok yang diunduh tidak tersedia" ("blocks downloaded are not available") instead of "blok sedang diunduh tidak berurutan" ("blocks are being downloaded out of order").
- The phrase "piranti lunak saat ini tidak mendukung membuka dompet" has spacing issues ("piranti lunak" is a correct alternative for "perangkat lunak", but "perangkat lunak" is the more common term).
- There is a missing format specifier check for %s which is present and correctly retained.

Correct translation:
Kesalahan saat memuat dompet. Dompet memerlukan blok-blok untuk diunduh, dan perangkat lunak saat ini tidak mendukung memuat dompet ketika blok-blok diunduh secara tidak berurutan saat menggunakan snapshot assumeutxo. Dompet seharusnya dapat dimuat setelah node tersinkronisasi hingga ketinggian %s.
```

```
        <source>Specified -blockmaxweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Detailnya - nilai block maksimal ( %d ) melebihi nilai awal maksimal block ( %d )</translation>
    
YES
The translation is incorrect and inaccurate. It does not properly reflect the technical terms and consensus specificity from the source, and changes the meaning. It also adds unnecessary words ("Detailnya") and does not preserve the format and structure (e.g., "-blockmaxweight (%d)" is not carried over accurately).

Correct translation:
Opsi -blockmaxweight yang ditentukan (%d) melebihi batas maksimum bobot blok menurut konsensus (%d)
```

```
        <source>
Unable to restore backup of wallet.</source>
        <translation>
Tidak dapat memulihkan cadangan dompet..</translation>
    
YES
There is a double period ("..") at the end of the Indonesian translation, which is an error. Also, spacing before the sentence is unnecessary.

Correct translation:
Tidak dapat memulihkan cadangan dompet.
```

```
        <source>Unsupported global logging level %s=%s. Valid values: %s.</source>
        <translation>Tingkat penebangan global yang tidak didukung %s = %s. Nilai yang valid: %s.</translation>
    
YES
The word "penebangan" is incorrect; it means "logging" in the context of woodcutting, not logging as in system logs. The correct term is "logging" or "log" in IT contexts, which is usually left untranslated or referred to as "logging sistem" or "tingkat pencatatan".

Correct translation:
Tingkat logging global yang tidak didukung %s=%s. Nilai yang valid: %s.
```

```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>menerima estimasi biaya basi tidak didukung pada %s rantai.</translation>
    
YES
The translation is inaccurate and unnatural in Indonesian. "acceptstalefeeestimates" is a technical parameter and should remain untranslated (as in English) or, if translated, should be clearly identified as a parameter. "rantai" for "chain" is odd; "jaringan" or mentioning "blockchain" may be better, but "chain" is usually left untranslated in technical contexts. The sentence also lacks correct capitalization and flow.

Correct translation:
"Parameter 'acceptstalefeeestimates' tidak didukung pada chain %s."
or
"'acceptstalefeeestimates' tidak didukung di jaringan %s."
```
</details>

Number of issues: 18.
