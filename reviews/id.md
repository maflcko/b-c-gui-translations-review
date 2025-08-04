# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>id</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bid%5D%20low%20quality)


```
        <source>default wallet</source>
        <translation>wallet default</translation>
    
YES, The word order is unnatural in Indonesian. The correct translation is "wallet bawaan".
```

```
        <source>Sign message…</source>
        <translation>Tanda tangani dan kirim pessan...</translation>
    
YES, The translation is problematic. The source text "Sign message…" translates to "Tanda tangani pesan…" in Indonesian. The provided translation "Tanda tangani dan kirim pessan..." adds "dan kirim" which means "and send", and also misspells "pesan" as "pessan".

Tanda tangani pesan…
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Muat transaksi Bitcoin yang ditandatangani seperapat</translation>
    
YES - The word "seperapat" means "a quarter". The correct translation for "partially signed" in this context is "ditandatangani sebagian".

Muat transaksi Bitcoin yang ditandatangani sebagian
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Muat transaksi Bitcoin yang ditandatangani seperapat dari clipboard</translation>
    
YES: The Indonesian word "seperapat" means "a quarter" or "one-fourth", which is not the correct translation for "partially". The correct translation for "partially signed" in this context would be "ditandatangani sebagian".

Muat transaksi Bitcoin yang ditandatangani sebagian dari clipboard
```

```
        <source>Load Wallets</source>
        <extracomment>Title of progress window which is displayed when wallets are being loaded.</extracomment>
        <translation>Tampilkan Dompet</translation>
    
YES - The translation "Tampilkan Dompet" means "Show Wallets" which is not accurate for the context of loading wallets. The correct translation should convey the action of loading.
Load Wallets
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
The translation of "<wallet name>" and "<timestamp>" into Indonesian is missing. The correct translation should include these placeholders.
Memindahkan dompet akan mengubah dompet ini menjadi satu atau beberapa dompet deskriptor. Cadangan dompet baru perlu dibuat.
Jika dompet ini berisi skrip yang hanya bisa dilihat, dompet baru akan dibuat yang berisi skrip tersebut.
Jika dompet ini berisi skrip yang dapat dipecahkan tetapi tidak dapat ditonton, dompet yang berbeda dan baru akan dibuat yang berisi skrip tersebut.

Proses migrasi akan mencadangkan dompet sebelum melakukan pemindahan. Fail cadangan ini akan diberi nama &lt;nama dompet&gt;-&lt;cap waktu&gt;.legacy.bak dan dapat ditemukan di direktori untuk dompet ini. Jika terjadi gagal pemindahan, cadangan dapat dipulihkan dengan fungsi "Pulihkan Dompet".
```

```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Skrip hanya lihat telah diimigrasikan ke dompet baru yang bernama '%1'.</translation>
    
YES: The translation incorrectly states that "solvable but not watched scripts" were migrated. The English source text states that "solvable but not watched scripts" were migrated. The correct translation should reflect this.

Skrip yang dapat dipecahkan tetapi tidak diawasi telah dimigrasikan ke dompet baru bernama '%1'.
```

```
        <source>Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!</source>
        <translation>Alamat lengkap untuk script kompatibel %1 (Contoh C:\Downloads\hwi.exe atau /Users/you/Downloads/hwi.py). HATI-HATI: piranti lunak jahat dapat mencuri koin Anda!</translation>
    
YES: The Indonesian word "Alamat" translates to "address" in English. However, in the context of Bitcoin, "address" refers to a Bitcoin wallet address, not a file path. The source text specifies a file path, making the translation inaccurate.

Full path to a %1 compatible script (e.g. C:\Downloads\hwi.exe or /Users/you/Downloads/hwi.py). Beware: malware can steal your coins!
Jalur lengkap ke script yang kompatibel dengan %1 (Contoh: C:\Downloads\hwi.exe atau /Users/you/Downloads/hwi.py). PERHATIAN: malware dapat mencuri koin Anda!
```

```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Perlihatkan apabila proxy SOCKS5 default digunakan untuk berhungan dengan orang lain lewat tipe jaringan ini.</translation>
    
YES: The translation uses "orang lain" (other people) which is not accurate in this context. In Bitcoin, "peers" refers to other nodes or participants on the network, not just any other people.
Correct translation: Perlihatkan apabila proxy SOCKS5 default digunakan untuk berhungan dengan rekan lewat tipe jaringan ini.
```

```
        <source>Minimize instead of exit the application when the window is closed. When this option is enabled, the application will be closed only after selecting Exit in the menu.</source>
        <translation>Minimalisasi aplikasi ketika jendela ditutup. Ketika pilihan ini dipilih, aplikasi akan menutup seluruhnya jika anda memilih Keluar di menu yang tersedia.</translation>
    
YES: The translation is problematic as it does not accurately convey the meaning of the source text. The source text states that the application will be closed *only* after selecting "Exit" in the menu, implying that minimizing is the default behavior when the window is closed. The translation, however, states that the application will close *entirely* if you select "Exit" in the menu, which is redundant and doesn't capture the intended contrast.

Correct translation: "Minimalisasi aplikasi alih-alih keluar saat jendela ditutup. Ketika opsi ini diaktifkan, aplikasi hanya akan ditutup setelah memilih Keluar di menu."
```

```
        <source>Options set in this dialog are overridden by the command line:</source>
        <translation>Set opsi pengaturan pada jendela dialog ini tertutup oleh baris perintah:</translation>
    
YES, The translation is problematic. The phrase "tertutup oleh" translates to "closed by" which does not accurately convey the meaning of "overridden by". A more accurate translation would be "ditimpa oleh" or "dikesampingkan oleh".

Correct translation: Set opsi pengaturan pada jendela dialog ini ditimpa oleh baris perintah:
```

```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>Set nomor thread script verifikasi. Nilai negatif sesuai dengan core yang tidak ingin digunakan di dalam system.</translation>
    
YES - The translation is inaccurate. "Nilai negatif sesuai dengan core yang tidak ingin digunakan di dalam system" translates to "Negative values correspond to the cores that do not want to be used within the system." This is not the intended meaning. The original text means that negative values correspond to the number of cores you *want to leave free*.

Correct translation: "Atur jumlah thread verifikasi skrip. Nilai negatif sesuai dengan jumlah inti yang ingin Anda bebaskan untuk sistem."
```

```
        <source>Spend unconfirmed change</source>
        <translation>Perubahan saldo untuk transaksi yang belum dikonfirmasi</translation>
    
YES, The translation is problematic as it does not accurately reflect the meaning of "unconfirmed change" in the context of Bitcoin transactions. "Change" in Bitcoin refers to the leftover amount of Bitcoin returned to the sender after a transaction, not "change in balance".

Correct translation:
NO
```

```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>PSBT berbayar disalin ke clipboard</translation>
    
YES: The translation is inaccurate and misleading. "Fee-bump" refers to increasing the transaction fee, not to a paid PSBT.

Correct translation: PSBT fee-bump disalin ke clipboard
```

```
        <source>Error loading wallet. Wallet requires blocks to be downloaded, and software does not currently support loading wallets while blocks are being downloaded out of order when using assumeutxo snapshots. Wallet should be able to load successfully after node sync reaches height %s</source>
        <translation>Eror saat membuka dompet. Dompet memerlukan blok untuk diunduh, dan piranti lunak saat ini tidak mendukung membuka dompet saat blok yang diunduh tidak tersedia saat memakai snapshot utxo yang diasumsikan. Dompet seharusnya dapat berhasil dibuka sesudah sinkronisasi node mencapai ketinggian %s</translation>
    
YES, The word "Eror" is misspelled. It should be "Error". The Indonesian word for "out of order" is translated as "tidak tersedia" which means "unavailable". A more accurate translation would be "tidak berurutan".

Error loading wallet. Wallet requires blocks to be downloaded, and software does not currently support loading wallets while blocks are being downloaded out of order when using assumeutxo snapshots. Wallet should be able to load successfully after node sync reaches height %s
Eror saat membuka dompet. Dompet memerlukan blok untuk diunduh, dan piranti lunak saat ini tidak mendukung membuka dompet saat blok yang diunduh tidak berurutan saat memakai snapshot utxo yang diasumsikan. Dompet seharusnya dapat berhasil dibuka sesudah sinkronisasi node mencapai ketinggian %s
```

```
        <source>Specified -blockmaxweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Detailnya - nilai block maksimal ( %d ) melebihi nilai awal maksimal block ( %d )</translation>
    
YES
The translation is inaccurate and confusing. The Indonesian translation uses "Detailnya" which means "The details" or "Specifically", but it does not accurately convey the meaning of "Specified". Additionally, "nilai awal maksimal block" translates to "initial maximum block value", which is not the intended meaning of "consensus maximum block weight". The correct translation should reflect that the specified value exceeds the consensus maximum.

The correct translation is:
-blockmaxweight (%d) yang ditentukan melebihi bobot blok maksimum konsensus (%d)
```

```
        <source>Unexpected legacy entry in descriptor wallet found. Loading wallet %s

The wallet might have been tampered with or created with malicious intent.
</source>
        <translation>Masukan yang tidak diharapkan dalam deskriptor dompet legasi telah ditemukan. Memuat dompet %s

Dompet kemungkinan telah dibobol dengan atau dibuat dengan tujuan jahat.
</translation>
    
YES: The translation is mostly accurate but "dibobol" (broken into/burgled) might be too strong for "tampered with". A more appropriate translation would be "dimanipulasi" (manipulated).

The wallet might have been tampered with or created with malicious intent.
Masukan yang tidak diharapkan dalam deskriptor dompet legasi telah ditemukan. Memuat dompet %s

Dompet kemungkinan telah dimanipulasi atau dibuat dengan tujuan jahat.
```

```
        <source>
Unable to restore backup of wallet.</source>
        <translation>
Tidak dapat memulihkan cadangan dompet..</translation>
    
YES, The translation contains a trailing double space.
Unable to restore backup of wallet.
Tidak dapat memulihkan cadangan dompet.
```

```
        <source>Unsupported global logging level %s=%s. Valid values: %s.</source>
        <translation>Tingkat penebangan global yang tidak didukung %s = %s. Nilai yang valid: %s.</translation>
    
YES - The translation uses "penebangan" which means "logging" in Indonesian, but it is more commonly translated as "log" or "pencatatan". Additionally, the word order feels unnatural. A more accurate and natural translation would be "Tingkat log global tidak didukung %s=%s. Nilai yang valid: %s.".
Tingkat log global tidak didukung %s=%s. Nilai yang valid: %s.
```

```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>menerima estimasi biaya basi tidak didukung pada %s rantai.</translation>
    
YES, The translation is not accurate. "stalefeeestimates" should be translated as "perkiraan biaya basi" or "estimasi biaya basi", not "estimasi biaya basi".
Correct translation: menerima perkiraan biaya basi tidak didukung pada %s rantai.
```
</details>
