# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>tl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Btl%5D%20low%20quality)


```
        <source>Right-click to edit address or label</source>
        <translation>pindutin lamang ang kanang pindutan upang i-edit ang address o label.</translation>
    
YES  
The translation uses a conversational phrasing and does not maintain the capital letter at the start. "Pindutin lamang ang kanang pindutan upang i-edit ang address o label." translates more as "Just press the right button to edit the address or label," which adds "lamang/just" and misses the nuance of "right-click" (which refers specifically to clicking the right mouse button, not just pressing it). The translation should adhere more closely to computer terminology.

Correct translation:  
I-right click upang i-edit ang address o label.
```

```
        <source>Create a new address</source>
        <translation>Lumikha ng bagong ♦address♦</translation>
    
YES
The translation incorrectly includes the symbols "♦" around "address", and "address" is not translated into Filipino/Tagalog. It should be translated into proper Filipino, and unnecessary characters should be removed.

Correct translation:
Lumikha ng bagong address
```

```
        <source>Copy the currently selected address to the system clipboard</source>
        <translation>Gayahin ang pinipiling ♦address♦ sa kasalakuyan sa ♦clipboard♦ ng sistem</translation>
    
YES
The translation is inaccurate. The word "address" is unnecessarily enclosed in symbols (♦address♦) instead of being properly translated. "Kasalakuyan" is a misspelling of "kasalukuyan", and "clipboard" is also unnecessarily enclosed in symbols. The sentence contains awkward phrasing and direct transliterations instead of natural Filipino.

Correct translation:
Kopyahin ang kasalukuyang napiling address sa clipboard ng sistema
```

```
        <source>Close</source>
        <translation>(Do you mean: Close?) :isara, sarado </translation>
    
YES
The translation includes unnecessary English text ("(Do you mean: Close?)") and two synonyms ("isara, sarado"), which is awkward and unprofessional. The translation should simply be the Filipino word for "Close".

Correct translation:
Isara
```

```
        <source>Choose the address to send coins to</source>
        <translation>Piliin ang ♦address♦ kung saan ipapadala ang mga barya</translation>
    
YES
The translation uses the placeholder "♦address♦" which is unnecessary and incorrect in Filipino; the word "address" should simply be "address" (as borrowed), or "tirahan" if clarified. Also, "barya" for "coins" is technically correct, but in the Bitcoin context, "mga coin" or even just "Bitcoin" is better for clarity. There are no whitespace issues, but the translation introduces a confusing symbol not present in the original.

Correct translation:
Piliin ang address kung saan ipapadala ang mga coin
```

```
        <source>Choose</source>
        <translation>(do you mean: CHOOSE?) ;Pumili,Piliin.</translation>
    
YES
The translation is problematic for several reasons:
- It contains English meta-commentary ("(do you mean: CHOOSE?) ;") which is not appropriate in production software.
- Multiple translations are listed without context ("Pumili,Piliin."). Only the correct one should be used based on the context.
- There is an unnecessary semicolon and stray punctuation.

Correct translation:
Pumili
```

```
        <source>Copy Address</source>
        <translation>Kopyahin ang ♦Address♦</translation>
    
YES
The translation incorrectly includes the special characters "♦" around the word "Address", which are not present in the source and may confuse users. Also, "Address" should be translated to Filipino as "address" or "adres", unless referring to a specifically untranslated technical term—but in UI translations, "address" is often rendered as "address" for clarity in the Bitcoin context. There is no whitespace or format specifier issue.

Correct translation:
Kopyahin ang Address

Alternatively, if "address" is to be localized:
Kopyahin ang Adres
```

```
        <source>Address</source>
        <translation>♦Address♦</translation>
    
YES
The translation is problematic: the inclusion of "♦" symbols is unnecessary and was not present in the original source. The word "Address" should be translated into Filipino (Tagalog) if an appropriate term exists, or left as is if it's commonly used untranslated in the technical context, but without extraneous symbols.

Correct translation:
Address

Or, if a Filipino translation is appropriate:
Adres
```

```
        <source>Passphrase Dialog</source>
        <translation>♦Passphrase♦ na ♦Dialog♦</translation>
    
YES
The translation is incorrect and contains extraneous symbols (♦), which are not appropriate. The words "Passphrase" and "Dialog" are left untranslated and simply wrapped with these symbols, which is not standard in Filipino (tl) translations.

Correct translation:
Dialog ng Passphrase
```

```
        <source>Enter passphrase</source>
        <translation>Ilagay ang ♦passphrase♦</translation>
    
YES  
The translation uses decorative symbols "♦" around "passphrase," which are not present in the source. This is unnecessary and nonstandard for UI localization. Also, "Ilagay ang passphrase" is otherwise appropriate.

Correct translation:  
Ilagay ang passphrase
```

```
        <source>New passphrase</source>
        <translation>Bagong ♦passphrase♦</translation>
    
YES
The translation adds unnecessary special characters (♦) around "passphrase", which are not present in the source and may confuse users. Also, "passphrase" is often kept untranslated in localizations for technical contexts, but the extra decoration is problematic.

Correct translation:
Bagong passphrase
```

```
        <source>Repeat new passphrase</source>
        <translation>Ulitin ang bagong ♦passphrase♦</translation>
    
YES
The translation introduces unnecessary symbols (♦) around "passphrase", which are not present in the source and could confuse users. Also, "passphrase" is often untranslated in IT contexts, but the extra symbols are problematic.

Correct translation:
Ulitin ang bagong passphrase
```

```
        <source>Change passphrase</source>
        <translation>Palitan ang ♦passphrase♦</translation>
    
YES
The translation uses unnecessary decorative characters (♦) surrounding "passphrase", which is not standard and may confuse users. The correct translation should be:

Correct translation:
Palitan ang passphrase
```

```
        <source>Confirm wallet encryption</source>
        <translation>Kumpirmahin ang ♦encryption♦ ng pitaka</translation>
    
YES
The translation has unnecessary symbols ("♦") around the word "encryption", which are not present in the source text and should not be there. Also, "encryption" should ideally be translated to "pag-e-encrypt" or "pag-encrypt" for clarity in Filipino.

Correct translation:
Kumpirmahin ang pag-encrypt ng pitaka
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Babala: IKung i-encrypt mo ang iyong pitaka at mawawala ang ♦passphrase♦,  &lt;b&gt;MAWAWALA MO ANG LAHAT NG IYONG MGA BITCOIN&lt;/b&gt;!</translation>
    
YES
There are several issues:
- "IKung" should be "Kung" (extraneous "I" at the start).
- The "♦" characters around 'passphrase' are erroneous and unnecessary.
- "pitaka" is correct for "wallet", but contextually "mawawala" should be "mawala" (future tense is better: "mawawala sa iyo"), but "mawawala" as "will lose" is okay.
- "MO ANG LAHAT NG IYONG MGA BITCOIN" is a bit wordy; "ang lahat ng iyong Bitcoin" or "lahat ng iyong Bitcoin" is better.
- Format specifiers are preserved (none), and HTML tags are correctly copied.
- Whitespace before the HTML tag is slightly incorrect (unnecessary space before "&lt;b&gt;").

Correct translation:
Babala: Kung i-encrypt mo ang iyong pitaka at mawalan ka ng passphrase, &lt;b&gt;MAWAWALA LAHAT NG IYONG BITCOIN&lt;/b&gt;!
```

```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Ilagay ang bagong ♦passphrase♦ para sa pitaka.&lt;br/&gt;Pakigamit ang ♦passphrase♦ of &lt;b&gt;sampu o higit pa na mga ♦random♦ na mga karakter&lt;/b&gt;, o &lt;b&gt;walo o higit pang mga salita&lt;/b&gt;.</translation>
    
YES
There are several issues with the translation:
- The word "♦passphrase♦" and "♦random♦" are not proper in Filipino and seem to be placeholders or erroneous insertions.
- The phrase "passphrase of sampu o higit pa na mga random na mga karakter" is not fluent. "Random characters" should be translated to proper Filipino, e.g., "hindi magkakaugnay na mga titik o character".
- "walo o higit pang mga salita" is a correct translation for "eight or more words".

Correct translation:
Ilagay ang bagong passphrase para sa pitaka.&lt;br/&gt;Mangyaring gumamit ng passphrase na &lt;b&gt;sampu o higit pang mga hindi magkakaugnay na karakter&lt;/b&gt;, o &lt;b&gt;walo o higit pang mga salita&lt;/b&gt;.
```

```
        <source>The supplied passphrases do not match.</source>
        <translation>Ang mga ibinigay na mga ♦passphrase♦ ay hindi nagtugma.</translation>
    
YES
The translation uses unnecessary markers "♦" around "passphrase", which are not present in the source. Additionally, "mga" is redundantly used twice with "ibinigay na mga", which can make the phrase sound awkward, and "passphrases" could be better rendered in a more natural way for Filipino users.

Correct translation:
Ang mga ibinigay na passphrase ay hindi magkatugma.
```

```
        <source>The passphrase entered for the wallet decryption was incorrect.</source>
        <translation>Ang ♦passphrase♦ na ipinasok sa ♦decryption♦ sa pitaka ay hindi tama.</translation>
    
YES
The translation contains unnecessary English words "passphrase" and "decryption" that have not been localized, and the use of "♦" is inappropriate and not standard in Filipino ('tl') translations. This could lead to misunderstandings or look unprofessional.

Correct translation:
Ang passphrase na inilagay para sa pag-decrypt ng pitaka ay mali.

Or, for a more natural flow:
Mali ang ipinasok na passphrase para sa pag-decrypt ng pitaka.
```

```
        <source>Warning: The Caps Lock key is on!</source>
        <translation>Babala: Ang ♦Caps Lock Key♦ ay naka-on!</translation>
    
YES
The translation unnecessarily adds "♦" symbols around "Caps Lock Key", which are not present in the original English text. The inclusion of 'Key' is acceptable, but the styling with symbols is not standard and could be considered unwanted formatting.

Correct translation:
Babala: Naka-on ang Caps Lock!
```

```
        <source>Do you want to reset settings to default values, or to abort without making changes?</source>
        <extracomment>Explanatory text shown on startup when the settings file cannot be read. Prompts user to make a choice between resetting or aborting.</extracomment>
        <translation>Gusto mo bang i-reset ang mga ♦setting♦ sa ♦default♦ na mga ♦value♦, o itigil na hindi gumagawa ng mga pagbabago?</translation>
    
YES
The translation uses the English words "setting," "default," and "value," surrounded by unconventional symbols (♦) instead of Filipino equivalents. This is awkward and not in standard Tagalog. The format specifier or wording is not carried over precisely. The translation should use Tagalog terms and avoid unnecessary symbols.

Correct translation:
Gusto mo bang i-reset ang mga setting sa mga default na halaga, o itigil nang hindi gumagawa ng anumang pagbabago?

Alternatively, to localize further (optional):
Nais mo bang i-reset ang mga setting sa mga paunang halaga, o itigil nang hindi nagbabago ng anuman?
```

```
        <source>A fatal error occurred. Check that settings file is writable, or try running with -nosettings.</source>
        <extracomment>Explanatory text shown on startup when the settings file could not be written. Prompts user to check that we have the ability to write to the file. Explains that the user has the option of running without a settings file.</extracomment>
        <translation>Isang malubhang pagkakamali ang naganap. Suriin ang mga ♦setting♦ ng ♦file♦ na ♦writable♦, o subukan na patakbuhin sa ♦-nosettings♦.</translation>
    
YES  
The translation uses the English words "setting", "file", "writable", and "-nosettings" wrapped with ♦, which is incorrect for a proper Filipino (Tagalog) translation. These terms should be translated or at least adapted more naturally into Tagalog. It also inaccurately refers to "mga setting ng file" instead of "settings file" ("file ng mga setting"), and doesn't capture the prompt to check if it's writable—"na maaaring sulatan."

Correct translation:  
Isang malubhang pagkakamali ang naganap. Suriin kung ang file ng mga setting ay maaaring sulatan, o subukang patakbuhin gamit ang -nosettings.
```

```
        <source>default wallet</source>
        <translation>pitaka na ♦default♦</translation>
    
YES  
The translation is problematic. "pitaka na ♦default♦" uses mixed language ("pitaka" is Tagalog for "wallet", but "default" is just kept in English, surrounded by decorative symbols "♦"). This is neither standard nor idiomatic in Filipino. Also, the "na" particle is unnecessary. The correct translation should be:

Correct translation:  
default na pitaka

(Note: In Filipino UI, "default na pitaka" is standard, but sometimes "nakatalagang pitaka" or "pangunahing pitaka" can be used for "default wallet".)
```

```
        <source>Modify configuration options for %1</source>
        <translation>Baguhin ang mga pagpipilian sa ♦configuration♦ para sa %1</translation>
    
YES  
The word "configuration" should be translated to Filipino as "konpigurasyon" or "pagkonpigurasyon". Additionally, the use of the special characters "♦" is unnecessary and problematic.

Correct translation:  
Baguhin ang mga pagpipilian sa konpigurasyon para sa %1
```

```
        <source>Network activity disabled.</source>
        <extracomment>A substring of the tooltip.</extracomment>
        <translation>Na-disable ang aktibidad ng ♦network♦</translation>
    
YES
The translation has two issues:
1. The English term "disabled" should be translated as "Hindi aktibo" or "Hindi pinagana", which more accurately reflects "disabled" rather than using the borrowed "na-disable".
2. The use of "♦network♦" is unusual and not idiomatic; "network" should be translated as "network" if the English term is retained intentionally, or "network" can be "network" or "nag-network" in Tagalog, but best is "network" if the interface uses English terms. However, the ♦ symbols are not natural.

Correct translation:
Hindi aktibo ang aktibidad ng network.
```

```
        <source>Send coins to a Bitcoin address</source>
        <translation>Magpadala ng mga ♦coin♦ sa ♦address♦ ng Bitcoin</translation>
    
YES
The translation incorrectly retains English words with surrounding symbols (♦coin♦, ♦address♦), which is not idiomatic in Filipino ('tl'). The correct approach is to use natural Filipino phrasing, possibly keeping "Bitcoin address" untranslated as it is often the convention, but translating "Send coins" into proper Filipino.

Correct translation:
Magpadala ng mga coin sa Bitcoin address

Or, if "coin" is to be translated:
Magpadala ng mga barya sa Bitcoin address

Note: If "coins" refers specifically to cryptocurrency, it's standard to leave "coin" as is. Remove the special symbols (♦) and avoid unnecessary English unless standard in the context.
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Palitan ang ♦passphrase♦ na ginamit para sa pag-encrypt sa pitaka</translation>
    
YES
The translation is mostly correct, but the use of special characters "♦passphrase♦" is unnecessary and not standard in 'tl'. Also, the preposition should be "ng" instead of "sa" for "pag-encrypt ng pitaka".

Correct translation:
Palitan ang passphrase na ginamit para sa pag-encrypt ng pitaka
```

```
        <source>Change Passphrase…</source>
        <translation>Palitan ang ♦Passphrase♦...</translation>
    
YES
The translation introduces unnecessary symbols ("♦") around "Passphrase" and translates "…" (ellipsis) as "..." (three dots), which may not match interface conventions. Furthermore, "Passphrase" does not need to be surrounded by symbols. The word "Passphrase" is commonly left untranslated, but the translation should be clear and natural.

Correct translation:
Palitan ang Passphrase…
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Tanda na mga mensahe sa mga ♦address♦ ng iyong ♦Bitcoin♦ para patunayan na pagmamay-ari mo sila</translation>
    
YES
The translation contains unnecessary symbols (♦) around "address" and "Bitcoin", which are not present in the source and make the translation problematic and unnatural. Furthermore, "Tanda na mga mensahe" is not a natural way to say "Sign messages" in Tagalog. The correct term for "sign" in this context is "Lagdaan".

Correct translation:
Lagdaan ang mga mensahe gamit ang iyong mga Bitcoin address upang patunayan na ikaw ang may-ari ng mga ito
```

```
        <source>Load PSBT from file…</source>
        <translation>I-load ang PSBT mula sa ♦file♦...</translation>
    
YES
The translation introduces '♦file♦', which is not present in the source. The ellipsis uses three dots '...' instead of the ellipsis character '…' from the source, and the format specifier should be preserved literally as in the source.

Correct translation:
I-load ang PSBT mula sa file…
```

```
        <source>Open URI…</source>
        <translation>Buksan ang ♦URL♦...</translation>
    
YES
The translation introduces the symbols "♦" around "URL" which do not appear in the source and is non-standard. Also, the ellipsis should be the single Unicode character "…" not three dots ("..."). Furthermore, consistency with standard Filipino UI translations should use "Open" as "Buksan" but "URI" is often not localized. If translated, it would be "Buksan ang URI…"

Correct translation:
Buksan ang URI…
```

```
        <source>File</source>
        <translation>♦File♦</translation>
    
YES
The translation is problematic because it simply copies the English word "File" and adds unwanted characters (♦) around it, which is inappropriate and not a valid Filipino (tl) translation. Also, "File" as a menu item would typically be translated to "File" (retained in many UI contexts), or, if localization is needed, "File" in Filipino is "Talaksan".

Correct translation:
Talaksan
```

```
        <source>Settings</source>
        <translation>Mga ♦Setting♦</translation>
    
YES
The translation includes non-standard characters "♦", which are not appropriate and may be considered spammy or erroneous in a UI context. Also, while "Setting" is sometimes left as-is in Filipino, the plural form "Mga Setting" is more appropriate, and the decorative symbols should be removed.

Correct translation:
Mga Setting
```

```
        <source>Syncing Headers (%1%)…</source>
        <translation>♦Syncing Headers♦ (%1%)…</translation>
    
YES
The translation unnecessarily adds "♦" symbols around "Syncing Headers", which are not present in the source and may be considered unwanted content. Additionally, "Syncing Headers" is untranslated and should be in Filipino.

Correct translation:
Sinusynchronize ang mga header (%1%)…
```

```
        <source>Synchronizing with network…</source>
        <translation>Sini-siynchronize sa ♦network♦...</translation>
    
YES
There are several issues:
- The use of "Sini-siynchronize" is not idiomatic Tagalog/Filipino. The correct form is "Sinisynchronize" or better yet, a more natural Filipino translation should be used, like "Sinasabay sa network", "Sumasabay sa network", or "Ipinagsi-synchronize sa network".
- The phrase "♦network♦" is not appropriate; it should just be "network" or "sa network" if retained.
- Ellipsis formatting ("...") in Filipino is usually three dots without extra trailing spaces.
- Unwanted non-standard characters (♦) are present.

Correct translation:
Sinusynchronize sa network...
or
Sinasabay sa network...
or, more formally,
Sinusunod ang takbo ng network...
```

```
        <source>Indexing blocks on disk…</source>
        <translation>Ini-index ang mga bloke sa ♦disk♦...</translation>
    
YES
The translation uses ♦disk♦ which is unusual and nonstandard in Tagalog. It should simply use "disk" or its Filipino equivalent if there is one, but not with special characters. Otherwise, the meaning is clear, but the ellipsis should match the source (use the same number of dots, preferably three).

Correct translation:
Ini-index ang mga bloke sa disk...
```

```
        <source>Processing blocks on disk…</source>
        <translation>Pinoproseso ang mga bloke sa ♦disk♦...</translation>
    
YES
The translation uses "♦disk♦", which is unidiomatic and contains unnecessary symbols. In Filipino ('tl'), "disk" is commonly translated as "disk" or "disco", depending on context. The ellipsis character "..." should be consistent with the source, which uses "…".

Correct translation:
Pinoproseso ang mga bloke sa disk…
```

```
        <source>Connecting to peers…</source>
        <translation>Kumokonekta sa mga ♦peers♦...</translation>
    
YES
The translation contains unnecessary symbols ("♦") around "peers" and did not localize "peers" into Filipino (usually "katambal", "kasamahan", or simply keeping the English "peers" if commonly used in the technical context). The ellipsis formatting ("...") should be aligned with the original, using the single Unicode ellipsis "…" if possible.

Correct translation:
Kumokonekta sa mga peer…
```

```
        <source>Command-line options</source>
        <translation>♦Command-line♦ na mga pagpipilian</translation>
    
YES  
The translation includes extraneous characters ("♦") at the start and around "Command-line", which are not present in the source and are unwanted. The phrase "Command-line" should be translated appropriately to Filipino/Tagalog if possible.

Correct translation:  
Mga pagpipilian sa command-line
```

```
        <source>Load Partially Signed Bitcoin Transaction</source>
        <translation>Ang ♦Load♦ ay Bahagyang Napirmahan na Transaksyon sa ♦Bitcoin♦</translation>
    
YES  
The translation is problematic.  
1. The source phrase is "Load Partially Signed Bitcoin Transaction," which should be a simple imperative or descriptive phrase.
2. The translation includes unnecessary symbols "♦" and an unnatural structure.
3. The "Load" is unnecessarily emphasized and translated as if it were a noun ("Ang Load"), while it should be an imperative or a succinct noun phrase.
4. "na Transaksyon sa Bitcoin" is acceptable, but overall, the phrase is awkward and not natural Filipino.

Correct translation:
I-load ang Bahagyang Napirmahang Transaksyon sa Bitcoin
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Ang ♦Load♦ ay Bahagyang Napirmahan na Transaksyon sa ♦Bitcoin♦ mula sa ♦clipboard♦</translation>
    
YES
The translation introduces unnecessary symbols (♦) and an awkward sentence structure. "Ang Load ay Bahagyang Napirmahan na Transaksyon sa Bitcoin mula sa clipboard" is unnatural in Filipino/Tagalog, and "Load" should be rendered as "I-load" or similar to make it actionable/imperative.

Correct translation:
I-load ang Bahagyang Napirmahang Transaksyong Bitcoin mula sa clipboard
```

```
        <source>Sending addresses</source>
        <translation>Pagpapadalhan na mga ♦address♦</translation>
    
YES
The translation is problematic due to the unnecessary addition of "na" and the use of special symbols ♦ which are not present in the source. The translation should be simple, straightforward, and free of extraneous formatting or words. Also, "address" should usually just be "address," as it is commonly used untranslated in Filipino IT/crypto contexts, or "mga address" if pluralization is preferred.

Correct translation:
Mga address na padadalhan
```

```
        <source>Receiving addresses</source>
        <translation>Pagtatanggapan na mga ♦address♦</translation>
    
YES
The translation uses "Pagtatanggapan na mga ♦address♦", which is awkward and includes untranslated English word "address" with special characters. The proper Filipino word for "addresses" should be used, and "receiving addresses" can be translated more naturally.

Correct translation:
Mga address ng pagtanggap
```

```
        <source>Open a bitcoin: URI</source>
        <translation>Buksan ang ♦bitcoin: URI♦</translation>
    
YES  
The translation incorrectly includes extra symbols "♦" around "bitcoin: URI". This is not present in the source text and may confuse users. The rest of the translation is otherwise correct.

Correct translation:  
Buksan ang bitcoin: URI
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Ipakita ang %1 tumulong sa mensahe na kumuha ng listahan ng posibleng ♦Bitcoin command-line♦ na mga pagpipilian</translation>
    
YES
The translation mixes English and Filipino unnecessarily ("tumulong sa mensahe", "command-line"), contains awkward phrasing, and introduces an extraneous symbol (♦). "tumulong sa mensahe" is not a correct translation for "help message". The format is also confusing.

Correct translation:
Ipakita ang mensahe ng tulong ng %1 upang makakuha ng listahan ng mga posibleng pagpipilian sa command-line ng Bitcoin
```

```
        <source>Main Window</source>
        <translation>Pangunahing ♦Window♦</translation>
    
YES
The translation unnecessarily retains the English word "Window" and adds inappropriate symbols (♦), which is not standard in Filipino translations. "Main Window" should be translated as "Pangunahing Window" (if 'Window' is used as a proper term in Filipino interfaces), or better yet, fully in Filipino as "Pangunahing Bintana".

Correct translation:
Pangunahing Bintana
```

```
        <source>Enable network activity</source>
        <extracomment>A context menu item. The network activity was disabled previously.</extracomment>
        <translation>I-enable ang aktibidad ng ♦network♦</translation>
    
YES
The translated phrase "I-enable ang aktibidad ng ♦network♦" is problematic:
1. The word "network" is not translated into Tagalog ("tl"). It should be "network" (as a loanword) only if no better word is applicable, but the diamond symbols (♦) are inappropriate and not present in the original source.
2. The extra symbols (♦) do not belong and are unwanted content.

Correct translation:
I-enable ang aktibidad ng network

Alternatively, you may use "I-enable ang aktibidad ng network" if "network" as a loanword is acceptable in local Bitcoin context, but DO NOT add decorative symbols.
```

```
        <source>Address: %1
</source>
        <translation>♦Address♦: %1
</translation>
    
YES
The translation inappropriately adds "♦" symbols around "Address", which are not present in the source and are likely unintended. Additionally, the English word "Address" is retained, which may be acceptable if the term is left untranslated in the software, but typically it should be translated to "Address: %1" → "Address: %1" (if left untranslated), or in Filipino, it should be "Address: %1" → "Address: %1" (since "Address" is commonly used in Filipino Bitcoin contexts and may remain untranslated). However, the main issue is the addition of unwanted symbols.

Correct translation:
Address: %1
or, if you prefer a Filipino word,
Tirahan: %1
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>♦HD key generation♦ ay &lt;b&gt;na-disable&lt;/b&gt;</translation>
    
YES
The translation is problematic because:
- The "♦" symbols at the start and around "HD key generation" are unwanted and introduce stray characters.
- "na-disable" is an anglicized and informal term. A more appropriate Filipino translation is "hindi pinagana" or "hindi aktibo".
- "HD key generation" is a technical term that can be left untranslated for the Filipino audience, but without the stray symbols.

Correct translation:
Ang HD key generation ay <b>hindi pinagana</b>
```

```
        <source>Coin Selection</source>
        <translation>Pagpipilian ng ♦coin♦</translation>
    
YES
The translation is problematic because it literally translates "Coin Selection" as "Pagpipilian ng ♦coin♦", where "coin" is not translated to Filipino/Tagalog and unnecessary decorative symbols (♦) are present. The word "coin" should be translated appropriately for the Bitcoin context (e.g., "barya" or simply kept as "coin" if that is standard in local usage, but without symbols). Also, "Pagpipilian ng" is awkward; a better translation would be "Pagpili ng Barya" or "Pagpili ng Coin" depending on standard usage in the Bitcoin community in the Philippines.

Correct translation:
Pagpili ng Barya
```

```
        <source>List mode</source>
        <translation>Listajhan na ♦mode♦</translation>
    
YES
The translation is incorrect and uses "Listajhan" (which is not a valid Tagalog word) and adds symbols ("♦mode♦") that are not present in the source. The correct translation should use proper Tagalog or a near match if a direct translation isn't standard.

Correct translation:
Paraan ng listahan
```

```
        <source>Received with label</source>
        <translation>Natanggap na may kasamang ♦tatak♦</translation>
    
YES
The use of "♦tatak♦" is incorrect and non-standard. The diamonds (♦) are not appropriate and may indicate a placeholder or erroneous characters. The word "tatak" is an acceptable translation for "label," but "kasamang" is awkward in this context. The standard phrase should be directly and neutrally translated.

Correct translation:
Natanggap na may label
```

```
        <source>Received with address</source>
        <translation>Natanggap na may ♦address♦</translation>
    
YES
The translation is problematic because it uses "♦address♦" instead of translating the term or correctly using a format specifier if required. Additionally, "na may" is acceptable but not the standard way to phrase this in Filipino UI.

Correct translation:
Natanggap sa address
```

```
        <source>Copy address</source>
        <translation>Kopyahin ang ♦address♦</translation>
    
YES The translation "Kopyahin ang ♦address♦" is problematic. The word "address" is untranslated, and the use of "♦" is unnecessary and incorrect in this context. 

Correct translation:
Kopyahin ang address

If you want a more natural translation, you can use:
Kopyahin ang address

Or, if you want to translate "address" as "address ng pitaka" ("wallet address"):
Kopyahin ang address

But strictly for "Copy address", the accurate "tl" is:
Kopyahin ang address
```

```
        <source>Copy bytes</source>
        <translation>Kopyahin ang ♦bytes♦</translation>
    
YES
The translation is problematic. The phrase "Kopyahin ang ♦bytes♦" includes unnecessary symbols (♦) around "bytes" that are not present in the source. Furthermore, the English word "bytes" is typically used directly in Filipino technical contexts, but the symbols make the translation erroneous.

Correct translation:
Kopyahin ang bytes
```

```
        <source>Can vary +/- %1 satoshi(s) per input.</source>
        <translation>Maaaring magbago ng +/- %1♦4satoshi(s)♦ kada ♦input♦.</translation>
    
YES
There are issues with stray and incorrect characters (e.g., "♦4", "♦"), and the English word "input" is unnecessarily wrapped with special symbols. The format specifier "%1" is taken over correctly, but the extra "4" and "♦" are errors and "satoshi(s)" could be localized.

Correct translation:
Maaaring magbago ng +/- %1 satoshi kada input.
```

```
        <source>Closing the wallet for too long can result in having to resync the entire chain if pruning is enabled.</source>
        <translation>Ang pagsasarod sa pitaka sa matagal ay maaaring humantong sa pag-resync ng kabuuang ♦chain♦ kung ang pagputol ay na-enable.</translation>
    
YES  
The translation contains the following issues:  
1. The word "pagsasarod" is a typo; it should be "pagsasara".  
2. The phrase "♦chain♦" should be translated or kept in English only if there's no Filipino equivalent, but the use of "♦♦" is unusual and likely unintended.  
3. "Pagputol" is not the preferred translation for "pruning" in the context of Bitcoin; "pruning" is best kept in English in technical context, or else clarified.  
4. The sentence structure and translation for "enabled" is not optimal.  
5. Minor awkward phrasing throughout.

Correct translation:
Ang pagsasara ng pitaka nang matagal ay maaaring magresulta sa kinakailangang i-resync ang buong chain kung naka-enable ang pruning.
```

```
        <source>Encrypt the wallet. The wallet will be encrypted with a passphrase of your choice.</source>
        <translation>I-encrypt ang pitaka. Ang pitaka ay mae-encrypt na may ♦passphrase♦ ng iyong mapipili.</translation>
    
YES
The translation uses "♦passphrase♦", which is an unnecessary decoration and is not standard. It should simply use the word "passphrase" or its equivalent. Otherwise, the translation is generally accurate and does not have spacing or format issues.

Correct translation:
I-encrypt ang pitaka. Ang pitaka ay mae-encrypt gamit ang passphrase na iyong pinili.
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>I-disable ang mga pribadong mga susi para sa pitaka na ito. Ang mga pitaka na may mga pribadong mga susi na na-disable ay mawawalng ng pribadong mga susi at hindi magkakaroon ng ♦HD seed♦ o mga na-import na pribadong mga susi. Ito ay perpekto lamang para sa mga ♦watch-only♦ na mga pitaka.</translation>
    
YES  
There are several issues in the translation:
1. The use of "♦HD seed♦" and "♦watch-only♦" with symbols is unnecessary and not standard in Filipino translations. English terms like "HD seed" and "watch-only" are often retained, but without symbols.
2. "mawawalng" is misspelled; it should be "mawawalan".
3. Excessive repetition of "mga" (plural marker) before "pribadong mga susi". It is more natural to say "mga pribadong susi".

Correct translation:
I-disable ang mga pribadong susi para sa pitakang ito. Ang mga pitakang may disabled na pribadong susi ay mawawalan ng pribadong susi at hindi magkakaroon ng HD seed o na-import na pribadong susi. Ito ay perpekto para sa mga watch-only na pitaka.
```

```
        <source>Use an external signing device such as a hardware wallet. Configure the external signer script in wallet preferences first.</source>
        <translation>Gumamit ng panlabas na pagpirmang ♦device♦ katulad ng ♦hardware♦ na pitaka. I-configure ang panlabas na ♦signer script♦ sa loob ng ♦preferences♦ ng pitaka n listahan. </translation>
    
YES
There are several issues with the translation:
1. The use of "♦device♦", "♦hardware♦", and "♦signer script♦" is inconsistent and uses unnecessary symbols; these terms can be translated directly or appropriately localized.
2. "Preferences" can be translated as "mga kagustuhan," and "wallet preferences" as "mga kagustuhan ng pitaka" rather than "preferences ng pitaka n listahan".
3. The phrase "n listahan" at the end appears to be an erroneous fragment.
4. The use of English fragments is unnecessarily high; certain terms can be better localized.

Correct translation:
Gumamit ng panlabas na kagamitan sa pagpirma tulad ng hardware wallet. I-configure muna ang panlabas na signer script sa mga kagustuhan ng pitaka.
```

```
        <source>External signer</source>
        <translation>Panlabas na ♦signer♦</translation>
    
YES
The word "signer" is not translated and is marked with unusual symbols (♦), which is not standard practice and can be confusing or appear as spam. Additionally, "signer" can be translated for clarity.

Correct translation:
Panlabas na tagapirma
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Pinagsama-sama na walang suporta ng ♦pag-pirma♦ (kailangan para sa panlabasna pagpirma)</translation>
    
YES
The translation is problematic due to:
- Unnecessary use of the symbols "♦" around "pag-pirma", which is incorrect and not present in the source.
- "Panlabasna" should be "panlabas na" (missing space).
- The use of "Pinagsama-sama" is not idiomatic in this context; a better term is "Inipon" or directly using "Na-compile" which is more appropriate in a technical context.

Correct translation:
Na-compile nang walang suporta para sa panlabas na pagpirma (kinakailangan para sa panlabas na pagpirma)
```

```
        <source>Edit Address</source>
        <translation>I-edit ang ♦address♦</translation>
    
YES
The translation "I-edit ang ♦address♦" unnecessarily leaves the word "address" untranslated and adds unwanted symbols (♦), which are not in the source or appropriate. In Tagalog, "address" (especially in the context of Bitcoin) can be translated as "address" (commonly used loan word) or more fully as "adres" if needed, but symbols should not be present.

Correct translation:
I-edit ang address
```

```
        <source>The label associated with this address list entry</source>
        <translation>Ang tatak na nauugnay sa ♦entry♦ ng listahan ng ♦address♦</translation>
    
YES
The translation is problematic for multiple reasons:
- The translation awkwardly maintains the English placeholders "entry" and "address" with ♦, which is not standard practice in Filipino and makes the text sound unnatural.
- "Entry" and "address" are not translated, and should be.
- "Address list entry" should be translated as "entry ng listahan ng address", but "address" could also be natively translated as "address" (Filipino usage does sometimes borrow the English term in technical contexts).

Correct translation:
Ang label na nauugnay sa entry ng listahan ng address na ito
```

```
        <source>The address associated with this address list entry. This can only be modified for sending addresses.</source>
        <translation>Ang ♦address♦ na may kaugnayan sa ipinasok sa listahan ng ♦address♦. Ito ay maaari lamang ng mabago para sa pagpapadalhan na mga ♦address♦.</translation>
    
YES
The translation uses the placeholder "♦address♦" instead of the word "address" translated into Filipino/Tagalog (typically "address" is retained or "adres" is used as a loanword in context). Additionally, the phrase structure is awkward and not entirely natural in Filipino. There are also some grammatical issues such as "ng mabago" (should be "lamang mabago").

Correct translation:
Ang address na kaugnay ng entry na ito sa listahan ng address. Maaari lamang itong baguhin para sa mga address na gagamitin sa pagpapadala.
```

```
        <source>Address</source>
        <translation>♦Address♦</translation>
    
YES
The translation is problematic: the inclusion of "♦" symbols is unnecessary and was not present in the original source. The word "Address" should be translated into Filipino (Tagalog) if an appropriate term exists, or left as is if it's commonly used untranslated in the technical context, but without extraneous symbols.

Correct translation:
Address

Or, if a Filipino translation is appropriate:
Adres
```

```
        <source>New sending address</source>
        <translation>Bagong pagpapadalhan na ♦address♦</translation>
    
YES
The translation is problematic. The use of "♦address♦" is not proper Filipino and seems to include untranslated placeholder text with decorative symbols, which is unnecessary and confusing. The phrase "Bagong pagpapadalhan" is generally understandable, but "address" should be translated as "address" in Filipino contexts ("address" is often used directly, or "adres" can be used). Remove the decorative symbols.

Correct translation:
Bagong address ng padadalhan

Or optionally, using "adres":
Bagong adres ng padadalhan
```

```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Ang naipasok na ♦address♦ "%1" ay hindi wasto na ♦Bitcoin address♦.</translation>
    
YES
The translation contains unnecessary symbols "♦address♦" and "♦Bitcoin address♦", which are not standard or appropriate in Tagalog and do not appear in the original English. Also, the structure could be more idiomatic. 

Correct translation:
Ang ipinasok na address na "%1" ay hindi wastong Bitcoin address.
```

```
        <source>The entered address "%1" is already in the address book with label "%2".</source>
        <translation>Ang naipasok na ♦address♦ "%1" ay nasa aklat na ng ♦address♦ na may tatak "%2".</translation>
    
YES  
The translation incorrectly uses "♦address♦" as placeholders, which is not idiomatic and unnecessary in Filipino ('tl'), and may confuse users. The word "address" should be translated as "address" (since the context of Bitcoin usually keeps the term untranslated), or at least consistently and not surrounded by special characters. The phrase "aklat na ng ♦address♦" is ungrammatical and awkward—"address book" should be translated as "aklat ng mga address" or "address book" (as calque).

Correct translation:  
Ang ipinasok na address na "%1" ay nasa address book na may tatak na "%2".
```

```
        <source>New key generation failed.</source>
        <translation>Ang Bagong susi sa ♦generation♦ ay nabigo.</translation>
    
YES
The translation has several issues:
- The word "generation" is not translated; it appears as "♦generation♦".
- "Bagong" should not be capitalized unless at the start.
- The correct translation of "key generation" is "pagbuo ng susi" or "paggawa ng bagong susi".
- Format specifiers and spacing are not problematic here, but the translation does not accurately convey the source.

Correct translation:
Nabigo ang pagbuo ng bagong susi.
```

```
        <source>A new data directory will be created.</source>
        <translation>May bagong datos na ♦directory♦ ay magagawa.</translation>
    
YES  
The translation is awkward and contains an untranslated word ("directory") boxed by special characters (♦directory♦), which is not standard in Tagalog ('tl'). It should read more naturally and either translate "directory" (e.g., as "direktoryo") or consistently borrow it if it is common in local usage, but without special characters.  
  
Correct translation:  
Lilikha ng isang bagong direktoryo ng datos.  
or  
Isang bagong data directory ang lilikhain.
```

```
        <source>Directory already exists. Add %1 if you intend to create a new directory here.</source>
        <translation>Ang ♦directory♦ ay mayroon na. Magdagdag ng%1kung balak mong gumawa ng bagong ♦directory♦ dito.</translation>
    
YES
There are several issues: 
- "%1" is not spaced properly ("Magdagdag ng%1kung" should be "Magdagdag ng %1 kung").
- The word "directory" is not translated or left as is but wrapped in unusual symbols (♦), which is not standard.
- The tone is slightly awkward in Filipino.

Correct translation:
Umiiral na ang directory. Magdagdag ng %1 kung nais mong gumawa ng bagong directory dito.
```

```
        <source>Cannot create data directory here.</source>
        <translation>Hindi makakagawa ng datos na ♦directory♦ dito.</translation>
    
YES  
The translation is partly problematic. The word "directory" is not translated and is awkwardly surrounded by the characters ♦, which are unnecessary and not standard. In addition, "data directory" should ideally be translated as "directory ng datos" or "folder ng datos," not "datos na directory." A better and more natural translation:

Correct translation:  
Hindi maaaring lumikha ng directory ng datos dito.
```

```
        <source>At least %1 GB of data will be stored in this directory, and it will grow over time.</source>
        <translation>Hindi bababa sa %1 ng ♦GB♦ na dato ay mailalagay sa ♦directory♦, at lalaki sa paglipas ng panahon.</translation>
    
YES
There are several issues with the translation:
- "♦GB♦" and "♦directory♦" should not be wrapped with such symbols; these are not typical in Tagalog translation and are not present in the source.
- "ng GB" is incorrect; should be "%1 GB".
- "dato" should be "data".
- "directory" should be translated as "direktoryo".
- The sentence structure could be improved for naturalness.
- The translation does not preserve the original format specifier "%1" correctly, since it's followed by "ng" without "GB".

Correct translation:
Hindi bababa sa %1 GB ng data ang itatago sa direktoryong ito, at madaragdagan pa ito habang tumatagal.
```

```
        <source>Size of database cache</source>
        <translation>Laki ng ♦database cache♦</translation>
    
YES
The translation "Laki ng ♦database cache♦" is problematic because it inappropriately uses the English phrase "database cache" without translation or explanation. Additionally, the diamond symbols (♦) are not present in the source and are unnecessary.

Correct translation:
Laki ng cache ng database
```

```
        <source>Number of script verification threads</source>
        <translation>Bilang ng ♦script♦ pagpapatunay na mga ♦threads♦</translation>
    
YES
The translation improperly uses English words "script" and "threads" enclosed in symbols (♦), which is not standard and may confuse users. In Filipino ("tl"), technical terms like "script" and "threads" are sometimes borrowed, but not marked with special symbols, and the word order could be improved.

Correct translation:
Bilang ng mga thread para sa pagpapatunay ng script
```

```
        <source>Network</source>
        <translation>♦Network♦</translation>
    
YES
The translation is problematic. The Tagalog ('tl') translation is simply the English word "Network" with decorative characters (♦) added, which are not present in the original source. This addition is unwarranted and constitutes a format issue.

Correct translation:
Network

Alternatively, if you prefer a direct Tagalog translation (though English terms are often used in computing contexts in the Philippines):

Correct translation:
Ugnayan (but "Network" is commonly retained)

So the best choice for software UI is just:
Network
```

```
        <source>Prune block storage to</source>
        <translation>Putulan i-block ang imbakan sa</translation>
    
YES
The translation "Putulan i-block ang imbakan sa" is awkward and not entirely accurate. The verb "putulan" is not the commonly used term for "prune" in this technical context, and the structure is unnatural in Filipino. 

A better, more natural and clear translation would be:
"Putulin ang storage ng block sa"

Correct translation:
Putulin ang storage ng block sa
```

```
        <source>External signer script path</source>
        <translation>Panlabas na ♦signer script♦ na daanan</translation>
    
YES
The translation is somewhat awkward and contains the phrase "♦signer script♦" which appears to be a placeholder or markup rather than a translation. The use of "daanan" for "path" is acceptable but could be improved for clarity.

Correct translation:
Panlabas na landas ng signer script

Or, more fluently:
Landas ng panlabas na signer script
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Pinagsama-sama na walang suporta ng ♦pag-pirma♦ (kailangan para sa panlabasna pagpirma)</translation>
    
YES
The translation is problematic due to:
- Unnecessary use of the symbols "♦" around "pag-pirma", which is incorrect and not present in the source.
- "Panlabasna" should be "panlabas na" (missing space).
- The use of "Pinagsama-sama" is not idiomatic in this context; a better term is "Inipon" or directly using "Na-compile" which is more appropriate in a technical context.

Correct translation:
Na-compile nang walang suporta para sa panlabas na pagpirma (kinakailangan para sa panlabas na pagpirma)
```

```
        <source>Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>Kopyahin ang ♦address♦</translation>
    
YES
The translation "Kopyahin ang ♦address♦" is problematic. The placeholder "♦address♦" is not a proper translation; it should translate "address" as "address" or "adres" in Filipino/Tagalog, but without the special characters. The correct translation is:

Correct translation:
Kopyahin ang address

Alternatively, if "address" should be perfectly localized:  
Kopyahin ang adres

However, "address" is often left untranslated in Filipino tech contexts. The use of special characters is unnecessary and incorrect.
```

```
        <source>Copy address</source>
        <translation>Kopyahin ang ♦address♦</translation>
    
YES The translation "Kopyahin ang ♦address♦" is problematic. The word "address" is untranslated, and the use of "♦" is unnecessary and incorrect in this context. 

Correct translation:
Kopyahin ang address

If you want a more natural translation, you can use:
Kopyahin ang address

Or, if you want to translate "address" as "address ng pitaka" ("wallet address"):
Kopyahin ang address

But strictly for "Copy address", the accurate "tl" is:
Kopyahin ang address
```

```
        <source>Copy bytes</source>
        <translation>Kopyahin ang ♦bytes♦</translation>
    
YES
The translation is problematic. The phrase "Kopyahin ang ♦bytes♦" includes unnecessary symbols (♦) around "bytes" that are not present in the source. Furthermore, the English word "bytes" is typically used directly in Filipino technical contexts, but the symbols make the translation erroneous.

Correct translation:
Kopyahin ang bytes
```

```
        <source>Copy address</source>
        <translation>Kopyahin ang ♦address♦</translation>
    
YES The translation "Kopyahin ang ♦address♦" is problematic. The word "address" is untranslated, and the use of "♦" is unnecessary and incorrect in this context. 

Correct translation:
Kopyahin ang address

If you want a more natural translation, you can use:
Kopyahin ang address

Or, if you want to translate "address" as "address ng pitaka" ("wallet address"):
Kopyahin ang address

But strictly for "Copy address", the accurate "tl" is:
Kopyahin ang address
```

```
        <source>Copy transaction ID</source>
        <translation>Kopyahin ang transaksyon  ng ♦ID♦</translation>
    
YES
The translation is problematic because:
1. The original "transaction ID" should be "ID ng transaksyon" or "transaksyon ID" in Filipino. 
2. There is an unnecessary space before "ng".
3. The use of "♦ID♦" is odd and could be confusing or introduce unwanted content.

Correct translation:
Kopyahin ang ID ng transaksyon
```

```
        <source>Address</source>
        <translation>♦Address♦</translation>
    
YES
The translation is problematic: the inclusion of "♦" symbols is unnecessary and was not present in the original source. The word "Address" should be translated into Filipino (Tagalog) if an appropriate term exists, or left as is if it's commonly used untranslated in the technical context, but without extraneous symbols.

Correct translation:
Address

Or, if a Filipino translation is appropriate:
Adres
```
</details>

Number of issues: 85.
