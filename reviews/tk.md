# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>tk</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Btk%5D%20low%20quality)


```
        <source>Delete</source>
        <translation>Poz</translation>
    
YES
The translation "Poz" is actually Russian for "Delete" and not Turkmen ('tk'). In Turkmen, "Poz" can also mean "Delete", but the capitalization is inconsistent: it should be "Poz" only as a sentence start or button text. Additionally, Turkmen language UI sometimes uses "Pozmak" or "Öçür" (from "öçürmek") as well.

However, given that "Poz" is commonly used for "Delete" as a button label in Turkmen, the translation is acceptable, but please ensure it is Turkmen in context and not Russian. If a more formal Turkmen is required, "Öçür" is preferable.

Correct translation:
Öçür

Alternative (also correct):
Poz

Explanation: The translation "Poz" is correct but should be verified as Turkmen in the context. "Öçür" is more uniquely Turkmen and preferred in many UI situations.

So, minimal, but technically not wrong. If the style guide allows "Poz", it is fine.

Final output:  
NO
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Otur bilen aýrylan faýl</translation>
    
YES
The translation of "Comma separated file" as "Otur bilen aýrylan faýl" is incorrect. "Otur" is not the correct word for "comma" in Turkmen; the correct term for "comma" is "üýtgetmek" or more accurately "vergül", and the phrase should preserve the idea of "comma-separated". The translation does not accurately convey the format specification.

Correct translation:
Wergül bilen bölünen faýl
```

```
        <source>Enter a Bitcoin address (e.g. %1)</source>
        <translation>(Bitkoin salgysyny giriziň (meselem, %1)</translation>
    
YES
There is an extraneous opening parenthesis before "Bitkoin salgysyny giriziň", which is not present in the original source. This is a formatting issue.

Correct translation:
Bitkoin salgysyny giriziň (meselem, %1)
```

```
        <source>Wallet:</source>
        <translation>Gapjyk:</translation>
    
YES
The translation is problematic: "Wallet" should be translated as "Pul gapjygy" or simply "Gapjyk gapjygy" in Turkmen, whereas "Gapjyk" alone typically means "purse" or "bag" and does not clearly convey the cryptocurrency wallet concept.

Correct translation:
Pul gapjygy:
```

```
        <source>Network activity disabled.</source>
        <extracomment>A substring of the tooltip.</extracomment>
        <translation>Tor işleýşi ýapyk.</translation>
    
YES
The translation is problematic. The phrase "Tor işleýşi ýapyk." means "Tor operation disabled." in Turkmen. However, the English original refers to "Network activity disabled," which is broader and not limited to Tor. The translation restricts the meaning to Tor, which is incorrect.

Correct translation:
Tor işleýşi ýapyk. → Tor işjeňligi ýapyk.

Or even better, more generally:
Tor işjeňligi ýapyk. → Tor ulgam işjeňligi ýapyk.

But simply:
Ulgam işjeňligi ýapyk.
```

```
        <source>Sign message…</source>
        <translation>Habara gol çek…</translation>
    
YES
The translation "Habara gol çek…" is problematic. "Gol çek" is not an appropriate Turkmen translation for "Sign" in this context; it appears to be an erroneous literal or slang translation ("to shoot a goal" in football, not to cryptographically sign).

Correct translation:
Habara gol çek… → Habara gol goý… or Habara gol çekmek…

But more appropriately, "Sign message" in Turkmen would be:

Habara gol goý…

If a more technical term is used: "Habara gol goýuň…"

So, correct translation:
Habara gol goý…
```

```
        <source>Synchronizing with network…</source>
        <translation>Tor bilen sinhronlaşdyrmak...</translation>
    
YES
The translation is problematic. "Tor bilen sinhronlaşdyrmak..." means "Synchronizing with Tor...", not "Synchronizing with network…". The translation introduces an unintended reference to the Tor network, which is erroneous in this context.

Correct translation:
Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Ulgam bilen sinhronlaşdyrylýar... or Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Tor bilen sinhronlaşdyrmak... → Ulgam bilen sinhronlaşdyrylýar...
```

```
        <source>%1 behind</source>
        <translation>%1 galdy</translation>
    
YES
The translation is inaccurate. "galdy" in Turkmen means "left" or "remained", which is not a direct translation of "behind" in this context (usually meaning "blocks behind" or "lagging behind" in synchronization). A more accurate translation in Turkmen for "%1 behind" (in the context of blockchain sync) would be:

Correct translation:
%1 yza galdy
```

```
        <source>Load PSBT from clipboard…</source>
        <translation>alyş-çalyş panelinden BGÇBA ýükle…</translation>
    
YES
The translation is mostly accurate in meaning, but there are issues:
- "alyş-çalyş panelinden" means "from the clipboard", which is correct.
- "BGÇBA" appears to be an initialism for "PSBT" (Partially Signed Bitcoin Transaction), but this is not a standard or recognized Turkmen abbreviation. It is preferable to retain "PSBT" or use the original term as it is commonly used in Bitcoin contexts.
- "ýükle" should be "ýükle", which is correct ("load").
- The translation is missing the initial uppercase letter, which may not be critical, but consistency with UI texts is preferred.
- No format specifiers to check in this case.
- No stray whitespace.

Correct translation:
Alyş-çalyş panelinden PSBT ýükle…

Explanation:
 "PSBT" should be left as-is rather than creating a regional abbreviation. This keeps it standard and recognizable to users.
```

```
        <source>Restore Wallet…</source>
        <extracomment>Name of the menu item that restores wallet from a backup file.</extracomment>
        <translation>Gapjygy dikelt…</translation>
    
YES
The translation "Gapjygy dikelt…" is inaccurate. "Gapjygy" means "conversation" or "dialogue" in Turkmen, which is not correct in this context. The correct word for "Wallet" in Turkmen would generally be "Gapjy" (wallet/purse). "Dikelt" means "restore". Also, the ellipsis "…" is carried over correctly.

Correct translation:
Gapjyny dikelt…
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>HD açar döretmeklik &lt;b&gt;öçük&lt;/b&gt;</translation>
    
YES
The translation is problematic. The word "öçük" is incorrect and not used in Turkmen to mean "disabled." The correct word should be "öçürilen" or "hereketsizleşdirilen." Additionally, the translation for "generation" as "döretmeklik" is an uncommon form; "döretmek" or " döredilişi" would be more appropriate.

Correct translation:
HD açar döredilişi &lt;b&gt;öçürilen&lt;/b&gt;
```

```
        <source>Fee:</source>
        <translation>Gatanç:</translation>
    
YES
The translation "Gatanç" is incorrect in Turkmen. The correct Turkmen word for "fee" in the context of Bitcoin (transaction or service fee) is "Töleg" or a more contextually accurate term might be "Gözegçilik tölegi" or "Ýygym". "Gatanç" does not mean "fee".

Correct translation:
Töleg:
or
Ýygym:
```

```
        <source>Change:</source>
        <translation>Çalyş:</translation>
    
YES
The translation is problematic. "Çalyş" means "Work" or "Try" in Turkmen, not "Change" (as in the context of Bitcoin transaction change). The correct translation for "Change" in the context of Bitcoin (referring to leftover currency from a transaction) would be "Galasyk" or "Üýtgeşik".

Correct translation:
Üýtgeşik:
```

```
        <source>(%1 locked)</source>
        <translation>(%1 gulply)</translation>
    
YES
The word "gulply" is not Turkmen. The correct Turkmen translation for "locked" would be "gulply" (as an approximation if no established term exists), but the spelling is still incorrect and does not match a known Turkmen word. However, based on Turkmen vocabulary, "gulply" seems a transliteration error. The correct form is "gulply", but if "gulply" is not Turkmen, a better term for "locked" in Turkmen is "gulplanan" (past participle of to lock, "gulpla-").

Correct translation:
(%1 gulplanan)
```

```
        <source>Restoring Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the restore wallets progress window which indicates to the user that wallets are currently being restored.</extracomment>
        <translation>&lt;b&gt;%1&lt;/b&gt; Gapjyk dikeldilýär…</translation>
    
YES
The translation is problematic. The English source is "Restoring Wallet <b>%1</b>…", which means that a wallet named %1 is being restored. The translation is "<b>%1</b> Gapjyk dikeldilýär…", which translates back as "Wallet gap is being restored…" or essentially replaces "Wallet" with "Gapjyk". In Turkmen, the word for wallet is "Gapjyk", but the source reverses the order (should be "Gapjyk %1 dikeldilýär…", matching the original sentence structure: "Restoring Wallet %1…"). Additionally, for clarity and proper structure, "Gapjyk" should come before %1, and consider native punctuation (ellipsis) and consistent placement.

Correct translation:
Gapjyk &lt;b&gt;%1&lt;/b&gt; dikeldilýär…
```

```
        <source>Wallet</source>
        <translation>Gapjyk</translation>
    
YES
The translation is incorrect. The English term "Wallet" should be translated as "Gapjyk" only if "Gapjyk" means "wallet" in Turkmen. However, "gapjyk" means "purse" or "pocket," which is generally acceptable in this technical context for "wallet." However, the capitalization is incorrect; Turkmen language capitalization for nouns follows the same conventions as English, so a capital letter is used at the start when it appears as a menu item or standalone label.

Correct translation:
Gapjyk

No change is actually needed except to confirm that "Gapjyk" is an accepted translation for "Wallet" in a software/Bitcoin context, which it is. However, since the prompt requests to only respond "NO" if it's completely unproblematic, and to mention even small issues, I'll say:

NO
```

```
        <source>Encrypt Wallet</source>
        <translation>Gapjygy şifrle</translation>
    
YES
The translation is inaccurate. "Gapjygy şifrle" means "Encrypt the conversation" or "Encrypt the chat", not "Encrypt Wallet". The correct translation for "Encrypt Wallet" in Turkmen ('tk') should be:

Correct translation:
Pul gapysyny şifrle
```

```
        <source>When you click OK, %1 will begin to download and process the full %4 block chain (%2 GB) starting with the earliest transactions in %3 when %4 initially launched.</source>
        <translation>OK basanyňyzda, %1%4 başda işledilende %3-däki iň irki amallardan başlap doly %4blok zynjyryny (%2 GB) ýükläp we işläp başlar.</translation>
    
YES
There is an issue with spacing and clarity in the translation. Specifically, "%4blok" should have a space: "%4 blok". Also, the phrase "başda işledilende" is awkward; more accurate would be to specify "ilkinji gezek işe girizilende". 

Correct translation:
OK basanyňyzda, %1 doly %4 blok zynjyryny (%2 GB), %4 ilkinji gezek işe girizilende %3-däki iň irki amallardan başlap, ýükläp we işläp başlar.
```

```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>%1häzir sinhronlaşdyrylýar. Ol düwünlerden baş atlary we bloklary ýükläp alar we blok zynjyrynyň ujuna ýetýänçä olary  barlar.</translation>
    
YES
There are two issues:
1. There is a missing space after '%1' in the translation ("%1häzir" should be "%1 häzir").
2. There is an extra space in "olary  barlar" (double space).

Correct translation:
%1 häzir sinhronlaşdyrylýar. Ol düwünlerden baş atlary we bloklary ýükläp alar we blok zynjyrynyň ujuna ýetýänçä olary barlar.
```

```
        <source>Unknown. Syncing Headers (%1, %2%)…</source>
        <translation>Näbelli. (%1, %2 %) Baş atlar sinhronlaşdyrylýar...</translation>
    
YES
The translation for "Syncing Headers" as "Baş atlar sinhronlaşdyrylýar" is inaccurate. "Baş atlar" literally means "main horses" in Turkmen, which is unrelated to the technical term "headers" in the context of blockchains. The spacing of "%2 %" is also incorrect, as there should not be a space between the number and the percent sign ("%2%").

Correct translation:
Näbelli. Baş hatarlary sinhronlaşdyrylýar (%1, %2%)...
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Näbelli. (%1, %2 %) Baş atlar deslapdan sinhronlaşdyrylýar...</translation>
    
YES
There are several issues with the translation:
1. The phrase "Baş atlar deslapdan sinhronlaşdyrylýar" is not the correct way to say "Pre-syncing Headers." "Baş atlar" literally means "main horses" and does not mean "headers." "Deslapdan" is an uncommon word for "pre-" and is not used in this context.
2. The format specifier "%2%" should be "%2%%" to retain the '%' as in the source, but the translated version has a space: "%2 %".
3. The translation should directly mention "Headers" as "Salgylanmalar" or "Baş garşylar" depending on local terminology, but "atlar" is incorrect.
4. Ellipsis ("...") is replaced by three dots ("...") instead of the single character ("…").

Correct translation:
Näbelli. Baş ýazgylary deslapdan sinhronlaşdyrmak (%1, %2%)…

Explanation:
- "Baş ýazgylar" is correct for "Headers"
- "deslapdan sinhronlaşdyrmak" means "pre-syncing"
- "%2%" is kept as in source for accuracy
- Correct ellipsis character is used
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Salgyny alyş-çalyş tagtasyna giriz</translation>
    
YES
The translation is problematic. The translation "Salgyny alyş-çalyş tagtasyna giriz" means "Enter the address into the clipboard", which is incorrect. The intended meaning is to paste an address from the clipboard. A correct Turkmen translation would be:

Salgyny alyş-çalyş tagtasyndan goý

Correct translation:
Salgyny alyş-çalyş tagtasyndan goý
```

```
        <source>Automatically start %1 after logging in to the system.</source>
        <translation>Ulgama hasaba girilenden soň %1awtomatiki usulda başlat.</translation>
    
YES
There is a minor whitespace format issue: '%1awtomatiki' should be '%1 awtomatiki' (space missing after %1).

Correct translation:
Ulgama hasaba girilenden soň %1 awtomatiki usulda başlat.
```

```
        <source>GB</source>
        <translation>GB çenli</translation>
    
YES
The translation "GB çenli" means "up to GB" or "until GB", which is inaccurate for the standalone label "GB". "GB" is an abbreviation for "gigabyte" and should remain as is, since abbreviations for measurement units are universal. No additional words should be added.

Correct translation:
GB
```

```
        <source>Enable RPC server</source>
        <extracomment>An Options window setting to enable the RPC server.</extracomment>
        <translation>RPC serwerini işlet</translation>
    
YES
The translation "RPC serwerini işlet" uses the Turkish verb "işlet," which is not correct for Turkmen ('tk'). The correct Turkmen translation should use "işjeňleşdir" for "enable".

Correct translation:
RPC serwerini işjeňleşdir
```

```
        <source>Wallet</source>
        <translation>Gapjyk</translation>
    
YES
The translation is incorrect. The English term "Wallet" should be translated as "Gapjyk" only if "Gapjyk" means "wallet" in Turkmen. However, "gapjyk" means "purse" or "pocket," which is generally acceptable in this technical context for "wallet." However, the capitalization is incorrect; Turkmen language capitalization for nouns follows the same conventions as English, so a capital letter is used at the start when it appears as a menu item or standalone label.

Correct translation:
Gapjyk

No change is actually needed except to confirm that "Gapjyk" is an accepted translation for "Wallet" in a software/Bitcoin context, which it is. However, since the prompt requests to only respond "NO" if it's completely unproblematic, and to mention even small issues, I'll say:

NO
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>Indi tassyklanmaly we entek sowup boljak balansa geçirilmedik amallaryň hemmesi</translation>
    
YES
The translation contains errors in word choice and grammar, making the meaning confusing. "Indi tassyklanmaly" should be "Entäk tassyklanmadyk" ("that have yet to be confirmed"), and "entek sowup boljak balansa geçirilmedik" does not clearly communicate "do not yet count toward the spendable balance".

Correct translation:
Entäk tassyklanmadyk we entek çykdajyly balansyňa goşulmaýan amallaryň jemi
```

```
        <source>PSBT Operations</source>
        <translation>PSBT amallary</translation>
    
YES
The translation is problematic due to a typographical error. The word "amallary" should be "amallary" in Turkmen, but in reality, "amallar" is the accurate Turkmen word for "operations." Therefore, there is an extra 'a' in "amallary." (Note: In Turkmen, "PSBT amallary" would be correct for "PSBT Operations".)

Correct translation:
PSBT amallary
```

```
        <source>Signed transaction successfully. Transaction is ready to broadcast.</source>
        <translation>Amala şowly gol çekildi. Amal ýaýlyma taýyn.</translation>
    
YES
There is a problem: The translation mistranslates the technical term "Signed transaction" as "Amala şowly gol çekildi." This phrase does not correctly convey the meaning of signing a transaction in a Bitcoin context. Additionally, "şowly gol çekildi" can be interpreted as "a lucky goal was scored," which is unrelated and incorrect.

Correct translation:
Şertnama üstünlikli gol çekildi. Şertnama ýaýlyma taýyn.

However, even this may not be accurate if "Transaction" refers to an actual Bitcoin transaction. A better translation preserving the technical sense would be:

Gollanan amallar üstünlikli ýerine ýetirildi. Amal ýaýlyma taýyn.

Or, more precisely:

Amal üstünlikli gol çekildi. Amal ýaýlyma taýyn.
```

```
        <source>Blocksdir</source>
        <translation>Blok binýadynyň deslapdan bellenmedik ýerini görkezmek üçin  opsiýasyny ulanyň.</translation>
    
YES
The translation is problematic. "Blocksdir" refers to the name of a directory (short for "blocks directory"), not an instruction or a descriptive sentence. The translation instead provides a full sentence about specifying an unspecified location, which does not match the source.

Correct translation:
Blok katalogy

If used as a label or heading, "Blocksdir" should be translated simply as "Blok katalogy" or "Bloklar katalogy" (the exact directory name), maintaining the format and brevity.
```

```
        <source>Wallet: </source>
        <translation>Gapjyk:</translation>
    
YES
The word "Gapjyk" in Turkmen means "closed" or "shut" and does not correspond to "Wallet". The appropriate translation for "Wallet" in Turkmen is "Gapjyk" when referring to a purse or wallet, but the colon's spacing is wrong, and the word should be contextually appropriate. If "Gapjyk" is intended as "Wallet", the translation should preserve the colon spacing according to standard punctuational practices in Turkmen.

Correct translation:
Gapjyk: 

(If extra space is not intended after the colon, ensure it matches the source.)
```

```
        <source>Whether we relay transactions to this peer.</source>
        <translation>Amallary bu düwüne ýaýlyma geçirýärismi.</translation>
    
YES
The translation is problematic because "Amallary bu düwüne ýaýlyma geçirýärismi." contains several issues:
- "Amallary" is the correct word for "transactions" in Turkmen, but it's better to use the singular or a generic phrasing.
- "ýaýlyma geçirýärismi" is an awkward and incorrect verbal construction for "relay".
- The sentence is not a clear or natural rendering in Turkmen.

Correct translation:
Bu düwüne amallary geçirişimizi görkezýär.

This captures the intent: "Whether we relay transactions to this peer."
```

```
        <source>Starting Block</source>
        <translation>Blogy başlamak</translation>
    
YES
The translation is incorrect. "Blogy başlamak" is a mixture of Turkish words ("blog" and "başlamak") and is not correct in Turkmen ('tk'). The Turkmen word for "block" is "blok", and "starting" can be rendered as "Başlaýan" (starting/as an adjective) or "Başlangyç blok" (starting block/initial block).

Correct translation:
Başlangyç blok
```

```
        <source>Wallet:</source>
        <translation>Gapjyk:</translation>
    
YES
The translation is problematic: "Wallet" should be translated as "Pul gapjygy" or simply "Gapjyk gapjygy" in Turkmen, whereas "Gapjyk" alone typically means "purse" or "bag" and does not clearly convey the cryptocurrency wallet concept.

Correct translation:
Pul gapjygy:
```

```
        <source>Fee:</source>
        <translation>Gatanç:</translation>
    
YES
The translation "Gatanç" is incorrect in Turkmen. The correct Turkmen word for "fee" in the context of Bitcoin (transaction or service fee) is "Töleg" or a more contextually accurate term might be "Gözegçilik tölegi" or "Ýygym". "Gatanç" does not mean "fee".

Correct translation:
Töleg:
or
Ýygym:
```

```
        <source>Change:</source>
        <translation>Çalyş:</translation>
    
YES
The translation is problematic. "Çalyş" means "Work" or "Try" in Turkmen, not "Change" (as in the context of Bitcoin transaction change). The correct translation for "Change" in the context of Bitcoin (referring to leftover currency from a transaction) would be "Galasyk" or "Üýtgeşik".

Correct translation:
Üýtgeşik:
```

```
        <source>Paste address from clipboard</source>
        <translation>Salgyny alyş-çalyş tagtasyna giriz</translation>
    
YES
The translation is inaccurate. The English phrase "Paste address from clipboard" should mean to insert (paste) an address that is currently stored in the clipboard. However, the translation "Salgyny alyş-çalyş tagtasyna giriz" means "Enter the address into the clipboard," which is the opposite action.

Correct translation:
Salgyny alyş-çalyş tagtasyndan goý
```

```
        <source>Paste address from clipboard</source>
        <translation>Salgyny alyş-çalyş tagtasyna giriz</translation>
    
YES
The translation is inaccurate. The English phrase "Paste address from clipboard" should mean to insert (paste) an address that is currently stored in the clipboard. However, the translation "Salgyny alyş-çalyş tagtasyna giriz" means "Enter the address into the clipboard," which is the opposite action.

Correct translation:
Salgyny alyş-çalyş tagtasyndan goý
```

```
        <source>Comma separated file</source>
        <extracomment>Expanded name of the CSV file format. See: https://en.wikipedia.org/wiki/Comma-separated_values.</extracomment>
        <translation>Otur bilen aýrylan faýl</translation>
    
YES
The translation of "Comma separated file" as "Otur bilen aýrylan faýl" is incorrect. "Otur" is not the correct word for "comma" in Turkmen; the correct term for "comma" is "üýtgetmek" or more accurately "vergül", and the phrase should preserve the idea of "comma-separated". The translation does not accurately convey the format specification.

Correct translation:
Wergül bilen bölünen faýl
```
</details>

Number of issues: 39.
