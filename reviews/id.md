# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bid%5D%20request)



<details><summary>id</summary>


<!-- cache_translation_check_id_898848f84b26f81d903dbfe3315a09f8c42c62e752e45f6c784a4ddddaffcb62 -->
```
        <source>default wallet</source>
        <translation>wallet default</translation>
    
ERR
The translation does not follow the Indonesian grammatical structure. In Indonesian, the correct word order is "default" (as an adjective or descriptor) should follow the noun if kept in English, but "wallet" itself should ideally be translated. The accepted term for "wallet" in Indonesian is "dompet", and "default" can be left as-is for technical context, or translated to "bawaan" or "standar":

Correct translation:
dompet default

Alternatively, if full localization is preferred:
dompet bawaan

Either "dompet default" or "dompet bawaan" would be more appropriate than "wallet default".
```

<!-- cache_translation_check_id_e8881d6dbe59434214ce6ff276cf5bb981e55bd4420f0421904abc9620211e2f -->
```
        <source>&amp;About %1</source>
        <translation>&amp;Tentang%1</translation>
    
ERR
There is a missing space between "Tentang" and "%1" in the translation, leading to a format issue. Additionally, the ampersand (&) to indicate a shortcut key is correctly present once.

Correct translation:
&Tentang %1
```

<!-- cache_translation_check_id_faa82317906e351149a64401a0b60dd8f7991c72c55ac911c536d617f3a29a7c -->
```
        <source>Sign &amp;message…</source>
        <translation>Tanda tangani dan kirim pessan...</translation>
    
ERR
The translation contains a typo: "pessan" should be "pesan". Also, the translation "Tanda tangani dan kirim pesan..." adds "dan kirim" ("and send") which is not in the source. Furthermore, the & character for indicating the shortcut key is not present in the translation, violating the rule for shortcut key consistency.

Correct translation:
Tanda tangani &pesan…
```

<!-- cache_translation_check_id_cb92414c27396371e4db930407fc70a5d66cd4ed46401e0c8cee92ee35964df1 -->
```
        <source>&amp;Command-line options</source>
        <translation>&amp;pilihan Command-line</translation>
    
ERR
The translation is partially incorrect due to capitalization and order. In Indonesian, "Command-line options" should be translated as "Opsi baris perintah". The current translation uses "pilihan Command-line", which is a mix of Indonesian and English, and "pilihan" should be capitalized to match the menu convention.

Correct translation:
&Opsi baris perintah
```

<!-- cache_translation_check_id_97be9a3ee353c7691a6fa105be002603d8875f9b1ae7ce7251e229435aa37c9e -->
```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Muat transaksi Bitcoin yang ditandatangani seperapat</translation>
    
ERR
The phrase "ditandatangani seperapat" is incorrect. "Seperapat" means "a quarter," not "partially." The correct translation for "Partially Signed Bitcoin Transaction" is "Transaksi Bitcoin yang Ditandatangani Sebagian".

Correct translation:
Muat Transaksi Bitcoin yang Ditandatangani Sebagian
```

<!-- cache_translation_check_id_5858eba306f16d4dffb94d67b53d98f112ddbd35af98a343f9f9b12af6c5b28f -->
```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Muat transaksi Bitcoin yang ditandatangani seperapat dari clipboard</translation>
    
ERR
The translation is inaccurate. "Ditandatangani seperapat" is incorrect; "Partially Signed" should be translated as "yang ditandatangani sebagian," not "seperapat" (which means "a quarter").

Correct translation:
Muat transaksi Bitcoin yang ditandatangani sebagian dari clipboard
```

<!-- cache_translation_check_id_0ff23f32434624832984bc127c9bc28f085277ef58abed034cb0bdb72a9066fc -->
```
        <source>(un)select all</source>
        <translation>(Tidak)memilih semua</translation>
    
ERR
Spacing and phrasing are slightly off. There should be a space after the opening parenthesis, and the parenthetical form is uncommon in Indonesian. Also no format specifiers are involved.

Correct translations (choose one appropriate for the UI):
- "(Tidak) memilih semua"  (fixed spacing)
- "Pilih semua / Batalkan pilih semua"  (clearer alternative)
```

<!-- cache_translation_check_id_a2ccaf1f4f2751f615ee523670a3599aaa4536ef4193ac8fbce8184854df274e -->
```
        <source>Copy bytes</source>
        <translation>Salin bytes</translation>
    
ERR
The translation mixes Indonesian ("Salin") with the English plural "bytes". While understandable, it's better to use the Indonesian term consistently. No format specifiers or spacing issues present.

Suggested correction:
Salin byte
```

<!-- cache_translation_check_id_8092169ad60f5e782026fa8d43f23ecdd6e52caf987e8d24be956da3d9277345 -->
```
        <source>Load Wallets</source>
        <extracomment>Title of progress window which is displayed when wallets are being loaded.</extracomment>
        <translation>Tampilkan Dompet</translation>
    
ERR
The translation is inaccurate. "Load Wallets" should be translated as "Muat Dompet" or "Memuat Dompet", not "Tampilkan Dompet" which means "Show Wallets". "Tampilkan" is not appropriate in the context of loading or initializing data.

Correct translation:
Muat Dompet
```

<!-- cache_translation_check_id_22a4c4831f4a55e82fdf0a16c72e6b6bc497fbb3ad78df25a9633577c5d0cb36 -->
```
        <source>Migrating the wallet will convert this wallet to one or more descriptor wallets. A new wallet backup will need to be made.
If this wallet contains any watchonly scripts, a new wallet will be created which contains those watchonly scripts.
If this wallet contains any solvable but not watched scripts, a different and new wallet will be created which contains those scripts.

The migration process will create a backup of the wallet before migrating. This backup file will be named &lt;wallet name&gt;-&lt;timestamp&gt;.legacy.bak and can be found in the directory for this wallet. In the event of an incorrect migration, the backup can be restored with the "Restore Wallet" functionality.</source>
        <translation>Memindahkan dompet akan mengubah dompet ini menjadi satu atau beberapa dompet deskriptor. Cadangan dompet baru perlu dibuat.
Jika dompet ini berisi skrip yang hanya bisa dilihat, dompet baru akan dibuat yang berisi skrip tersebut.
Jika dompet ini berisi skrip yang dapat dipecahkan tetapi tidak dapat ditonton, dompet yang berbeda dan baru akan dibuat yang berisi skrip tersebut.

Proses migrasi akan mencadangkan dompet sebelum melakukan pemindahan. Fail cadangan ini akan diberi nama -.legacy.bak dan dapat ditemukan di direktori untuk dompet ini. Jika terjadi gagal pemindahan, cadangan dapat dipulihkan dengan fungsi "Pulihkan Dompet".</translation>
    
ERR
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

<!-- cache_translation_check_id_9e97bff21945f6e921621434c9a387f4db3251fb085267929d6e08e29d682c19 -->
```
        <source>Solvable but not watched scripts have been migrated to a new wallet named '%1'.</source>
        <translation>Skrip hanya lihat telah diimigrasikan ke dompet baru yang bernama '%1'.</translation>
    
ERR
The translation is inaccurate. The phrase "Solvable but not watched scripts" is mistranslated as "Skrip hanya lihat", which means "watch-only scripts". The idea of "solvable" (those we can sign/spend) but "not watched" (not in watch-only list) is lost.

Correct translation:
Skrip yang dapat diselesaikan tetapi tidak dipantau telah dipindahkan ke dompet baru bernama '%1'.
```

<!-- cache_translation_check_id_52083e88bf1b58c8bab6b66e84400fd97124a24d7c2d3973c58a4665fcd8c475 -->
```
        <source>Shows if the supplied default SOCKS5 proxy is used to reach peers via this network type.</source>
        <translation>Perlihatkan apabila proxy SOCKS5 default digunakan untuk berhungan dengan orang lain lewat tipe jaringan ini.</translation>
    
ERR
The translation contains a typo ("berhungan" should be "berhubungan"), and "orang lain" is better translated as "peer" in Bitcoin contexts, e.g., "rekan" or simply "peer." The translation should also maintain the phrase "supplied default SOCKS5 proxy" accurately, and "shows" should be "Menunjukkan" rather than "Perlihatkan" (which is more an imperative form). 

Correct translation:
Menunjukkan apakah proxy SOCKS5 default yang diberikan digunakan untuk menghubungi peer melalui tipe jaringan ini.
```

<!-- cache_translation_check_id_45879fe477903f0cdc1ad0e09781274c20d1edc79dd881c6f55b3cb3e8a76d25 -->
```
        <source>Minimize instead of exit the application when the window is closed. When this option is enabled, the application will be closed only after selecting Exit in the menu.</source>
        <translation>Minimalisasi aplikasi ketika jendela ditutup. Ketika pilihan ini dipilih, aplikasi akan menutup seluruhnya jika anda memilih Keluar di menu yang tersedia.</translation>
    
ERR
The translation does not accurately reflect the original meaning. The English source explains that when this option is enabled, closing the window minimizes the app instead of exiting; the app is only fully closed when Exit is picked from the menu. The Indonesian translation suggests that the app will fully close when "Keluar" is chosen, but does not specify that, with this option, closing the window will only minimize the app.

Correct translation:
Minimalkan aplikasi alih-alih keluar ketika jendela ditutup. Ketika opsi ini diaktifkan, aplikasi hanya akan ditutup sepenuhnya setelah memilih Keluar di menu.
```

<!-- cache_translation_check_id_50537c1ee6ff510f2e1bc88ec6c97d0bd517058410ca418bd1f65630f876316a -->
```
        <source>Options set in this dialog are overridden by the command line:</source>
        <translation>Set opsi pengaturan pada jendela dialog ini tertutup oleh baris perintah:</translation>
    
ERR
The translation is slightly inaccurate and awkward. The phrase "tertutup oleh baris perintah" does not correctly convey the meaning of "overridden by the command line." The correct translation should use "digantikan oleh baris perintah" or "diabaikan karena baris perintah".

Correct translation:
Opsi yang diatur di dialog ini akan digantikan oleh baris perintah:
```

<!-- cache_translation_check_id_efe711ada8e97bac6508c711b8199ab6fffcf62ff451c26f91e148bf44934dee -->
```
        <source>Prune &amp;block storage to</source>
        <translation>Prune &amp;ruang penyimpan block ke</translation>
    
ERR
The translation is not fully accurate. "Prune &block storage to" should be translated as "Pangkas penyimpanan blok ke" or "Pangkas penyimpanan blok hingga". The word "Prune" is not translated, and "ruang penyimpan block" is an unnatural phrase in Indonesian.

Correct translation:
Pangkas &penyimpanan blok hingga
```

<!-- cache_translation_check_id_bc92182e08584ca1728efa04e8985e15cfcc13b95735cd00bf52f8707477e8ef -->
```
        <source>Set the number of script verification threads. Negative values correspond to the number of cores you want to leave free to the system.</source>
        <extracomment>Tooltip text for Options window setting that sets the number of script verification threads. Explains that negative values mean to leave these many cores free to the system.</extracomment>
        <translation>Set nomor thread script verifikasi. Nilai negatif sesuai dengan core yang tidak ingin digunakan di dalam system.</translation>
    
ERR
The translation is understandable but not fully accurate, and the English grammar was not well adapted to Indonesian. Also, "Set" should be "Atur," and "nomor thread script verifikasi" should be "jumlah thread verifikasi skrip." "System" should be "sistem." The explanation about negative values is imprecise—"core yang tidak ingin digunakan" is not clear enough. It should reflect "the number of cores you want to leave free to the system" (i.e., "jumlah inti yang ingin Anda biarkan bebas untuk sistem").

Correct translation:
Atur jumlah thread verifikasi skrip. Nilai negatif menunjukkan jumlah inti yang ingin Anda biarkan bebas untuk sistem.
```

<!-- cache_translation_check_id_218f0c6ee02e0bca85325b11607e5b81ae1eef26006acd208ef28708243ae924 -->
```
        <source>Subtract &amp;fee from amount by default</source>
        <extracomment>An Options window setting to set subtracting the fee from a sending amount as default.</extracomment>
        <translation>Kurangi biaya dari jumlah secara default</translation>
    
ERR
The translation is missing the required shortcut key (&) that is present in the source text, and the phrase "by default" could be better translated as "secara bawaan" to better reflect default settings.

Correct translation:
Kurangi &biaya dari jumlah secara bawaan
```

<!-- cache_translation_check_id_7cc61e653c9c6b702e348530b3f4cae8b40f05b6c8eff754c4d85610e3d02429 -->
```
        <source>&amp;Spend unconfirmed change</source>
        <translation>&amp;Perubahan saldo untuk transaksi yang belum dikonfirmasi</translation>
    
ERR
The translation renders "change" as "perubahan saldo", which is inaccurate in the context of Bitcoin, where "change" refers to the "kembalian" from a transaction, not a change in balance. A more accurate translation would be:

Correct translation:
&Gunakan kembalian yang belum dikonfirmasi
```

<!-- cache_translation_check_id_a2ccaf1f4f2751f615ee523670a3599aaa4536ef4193ac8fbce8184854df274e -->
```
        <source>Copy bytes</source>
        <translation>Salin bytes</translation>
    
ERR
The translation mixes Indonesian ("Salin") with the English plural "bytes". While understandable, it's better to use the Indonesian term consistently. No format specifiers or spacing issues present.

Suggested correction:
Salin byte
```

<!-- cache_translation_check_id_63b0c8c2dfda60813e4d018017934df56e5268e79638e81dbbd129876aa0a137 -->
```
        <source>Save Transaction Data</source>
        <translation>Simpan data Transaksi</translation>
    
ERR
Capitalization is inconsistent for Indonesian. In Indonesian, common nouns should be lowercase. Correct translation:
Simpan data transaksi
```

<!-- cache_translation_check_id_14bdb92844cc1450a3d4f016993b1becc44784f31fc6a90e44563e2449b81b04 -->
```
        <source>Fee-bump PSBT copied to clipboard</source>
        <translation>PSBT berbayar disalin ke clipboard</translation>
    
ERR
The translation is inaccurate. "Fee-bump" refers to increasing the transaction fee, not just "berbayar" (which means "paid" or "with fee"). The phrase "PSBT berbayar" does not convey the meaning of a PSBT (Partially Signed Bitcoin Transaction) that has been modified to bump the fee.

Correct translation:
PSBT dengan peningkatan biaya disalin ke clipboard
```

<!-- cache_translation_check_id_4004e49dd3d4850ce62b99d969db9028be872c6c83947b5d3dbf7cc6c87bf7b2 -->
```
        <source>Error loading wallet. Wallet requires blocks to be downloaded, and software does not currently support loading wallets while blocks are being downloaded out of order when using assumeutxo snapshots. Wallet should be able to load successfully after node sync reaches height %s</source>
        <translation>Eror saat membuka dompet. Dompet memerlukan blok untuk diunduh, dan piranti lunak saat ini tidak mendukung membuka dompet saat blok yang diunduh tidak tersedia saat memakai snapshot utxo yang diasumsikan. Dompet seharusnya dapat berhasil dibuka sesudah sinkronisasi node mencapai ketinggian %s</translation>
    
ERR
The translation contains some inaccuracies:
- "Error loading wallet" should be "Galat saat memuat dompet" or "Kesalahan saat memuat dompet" instead of "Eror saat membuka dompet" (which uses 'Eror', an irregular spelling, and "membuka" means "open" rather than "load").
- "Blocks are being downloaded out of order" is mistranslated as "blok yang diunduh tidak tersedia" ("blocks downloaded are not available") instead of "blok sedang diunduh tidak berurutan" ("blocks are being downloaded out of order").
- The phrase "piranti lunak saat ini tidak mendukung membuka dompet" has spacing issues ("piranti lunak" is a correct alternative for "perangkat lunak", but "perangkat lunak" is the more common term).
- There is a missing format specifier check for %s which is present and correctly retained.

Correct translation:
Kesalahan saat memuat dompet. Dompet memerlukan blok-blok untuk diunduh, dan perangkat lunak saat ini tidak mendukung memuat dompet ketika blok-blok diunduh secara tidak berurutan saat menggunakan snapshot assumeutxo. Dompet seharusnya dapat dimuat setelah node tersinkronisasi hingga ketinggian %s.
```

<!-- cache_translation_check_id_0f54c90a8c2197f99f5af55d77d55853317704aab858ce590d13483ef45a328c -->
```
        <source>Specified -blockmaxweight (%d) exceeds consensus maximum block weight (%d)</source>
        <translation>Detailnya - nilai block maksimal ( %d ) melebihi nilai awal maksimal block ( %d )</translation>
    
ERR
The translation is incorrect and inaccurate. It does not properly reflect the technical terms and consensus specificity from the source, and changes the meaning. It also adds unnecessary words ("Detailnya") and does not preserve the format and structure (e.g., "-blockmaxweight (%d)" is not carried over accurately).

Correct translation:
Opsi -blockmaxweight yang ditentukan (%d) melebihi batas maksimum bobot blok menurut konsensus (%d)
```

<!-- cache_translation_check_id_444e36144dbcda17b32de7e1d0ab4d8d0f3778becc16f378e5b73bcfe75536da -->
```
        <source>
Unable to restore backup of wallet.</source>
        <translation>
Tidak dapat memulihkan cadangan dompet..</translation>
    
ERR
There is a double period ("..") at the end of the Indonesian translation, which is an error. Also, spacing before the sentence is unnecessary.

Correct translation:
Tidak dapat memulihkan cadangan dompet.
```

<!-- cache_translation_check_id_898848f84b26f81d903dbfe3315a09f8c42c62e752e45f6c784a4ddddaffcb62 -->
```
        <source>default wallet</source>
        <translation>wallet default</translation>
    
ERR
The translation does not follow the Indonesian grammatical structure. In Indonesian, the correct word order is "default" (as an adjective or descriptor) should follow the noun if kept in English, but "wallet" itself should ideally be translated. The accepted term for "wallet" in Indonesian is "dompet", and "default" can be left as-is for technical context, or translated to "bawaan" or "standar":

Correct translation:
dompet default

Alternatively, if full localization is preferred:
dompet bawaan

Either "dompet default" or "dompet bawaan" would be more appropriate than "wallet default".
```

<!-- cache_translation_check_id_9b7550fa3a30f9290817f0091038fc5b9eab7626a34370048335990d08c38775 -->
```
        <source>Unsupported global logging level %s=%s. Valid values: %s.</source>
        <translation>Tingkat penebangan global yang tidak didukung %s = %s. Nilai yang valid: %s.</translation>
    
ERR
The word "penebangan" is incorrect; it means "logging" in the context of woodcutting, not logging as in system logs. The correct term is "logging" or "log" in IT contexts, which is usually left untranslated or referred to as "logging sistem" or "tingkat pencatatan".

Correct translation:
Tingkat logging global yang tidak didukung %s=%s. Nilai yang valid: %s.
```

<!-- cache_translation_check_id_99a02109132a5b52f99a12ac75c0ea87241716af34997fe56a72ba4a623de8e0 -->
```
        <source>acceptstalefeeestimates is not supported on %s chain.</source>
        <translation>menerima estimasi biaya basi tidak didukung pada %s rantai.</translation>
    
ERR
The translation is inaccurate and unnatural in Indonesian. "acceptstalefeeestimates" is a technical parameter and should remain untranslated (as in English) or, if translated, should be clearly identified as a parameter. "rantai" for "chain" is odd; "jaringan" or mentioning "blockchain" may be better, but "chain" is usually left untranslated in technical contexts. The sentence also lacks correct capitalization and flow.

Correct translation:
"Parameter 'acceptstalefeeestimates' tidak didukung pada chain %s."
or
"'acceptstalefeeestimates' tidak didukung di jaringan %s."
```
</details>

Number of issues: 27.
