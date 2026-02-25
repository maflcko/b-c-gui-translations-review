# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>si</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../../issues/new?title=%5Bsi%5D%20request)


<!-- cache_translation_check_si_de74b282c89179c860aff941b83312cec0d0c13b719f92beaee2120be5691561 -->
```
        <source>&amp;New</source>
        <translation>නව</translation>
    
ERR
The source contains a shortcut marker '&' which must appear exactly once in the translation. The provided translation "නව" omits the '&'.

Correct translation:
&නව
```

<!-- cache_translation_check_si_0b9dde780dfb629b02e7c2af33a0051a1f87b9e944e34a5c1b05a0adc2b8fa7e -->
```
        <source>&amp;Export</source>
        <translation>නිර්යාතය</translation>
    
ERR
The translation is missing the required shortcut marker '&' from the source. The source contains a single '&' and the translation must also include exactly one '&'.

Correct translation:
&නිර්යාතය
```

<!-- cache_translation_check_si_17e6fbdf123f03f3e097dc836d89416d6516b06ab5af2727c5d65c5047f678be -->
```
        <source>&amp;Delete</source>
        <translation>මකන්න</translation>
    
ERR
The Sinhala translation means "Delete" (මකන්න) but it omits the required shortcut ampersand (&) from the source. The source has a single & which must be carried into the translation exactly once.

Correct translation:
&මකන්න
```

<!-- cache_translation_check_si_fa1647406adce563e1f1b5c275eaf1bd4c546e80d28d8c7687d0e28d3f040918 -->
```
        <source>C&amp;hoose</source>
        <translation>තෝරන්න</translation>
    
ERR
The source contains a single '&' indicating a keyboard shortcut (C&amp;hoose). The Sinhala translation "තෝරන්න" is correct for "Choose" but is missing the '&' shortcut marker. Add a single '&' in the translation (no extra spaces).

Correct translation:
&තෝරන්න
```

<!-- cache_translation_check_si_e4f17db632a5fc606e1ef99b70af6a83b49919a8156734617918e72846e7347b -->
```
        <source>&amp;Copy Address</source>
        <translation>ලිපිනයේ පිටපතක්</translation>
    
ERR
The translation is missing the required shortcut ampersand (&) that appears in the source. No format specifiers are present, and there are no obvious extra whitespace issues, but the & must be present exactly once.

Suggested correct translation (with & included, imperative form appropriate for a menu action):
&ලිපිනය පිටපත් කරන්න
```

<!-- cache_translation_check_si_ddff5e7394695114cb12fa822715b97db11038f49148bab469ed1903ac723ee0 -->
```
        <source>Copy &amp;Label</source>
        <translation>නම්පතේ පිටපතක්</translation>
    
ERR
The translation is missing the shortcut ampersand (&) and has a minor orthography/style issue. The source "Copy &Label" expects a Sinhala translation that includes a single & indicating the keyboard shortcut and a natural verb form for "Copy Label".

Correct translation (with one &):
&ලේබලය පිටපත් කරන්න
```

<!-- cache_translation_check_si_138f2fa8c58b2ba04c4f0e308824bbdaa301ad62d9bacc5ed3a2511ad168a2ee -->
```
        <source>&amp;Edit</source>
        <translation>සංස්කරණය</translation>
    
ERR
The translation is missing the required shortcut ampersand '&' from the source. Also the Sinhala word provided is a noun ("editing"); a verb form may be preferable for a menu item.

Correct translations (include a single ampersand):
- &සංස්කරණය
or (more imperative)
- &සකස් කරන්න
```

<!-- cache_translation_check_si_84bf187d8230e9a0d5322e2147d406178186c4e42cec1c2524c41ffa940394b4 -->
```
        <source>&amp;Minimize</source>
        <translation>&amp;හකුළන්න</translation>
    
ERR
The Sinhala word "හකුළන්න" is not a natural/standard translation for "Minimize" in a GUI context. The ampersand shortcut is correctly preserved once, and there are no spacing issues.

Suggested correct translation:
&amp;අඩු කරන්න
```

<!-- cache_translation_check_si_138978d9ab7fee13ac0d472fbfca35032d230253d8ac760ccc52b506cd146330 -->
```
        <source>&amp;Backup Wallet…</source>
        <translation>&amp;පසුම්බිය උපස්ථකරන්න…</translation>
    
ERR
The Sinhala translation uses incorrect/odd wording ("පසුම්බිය උපස්ථකරන්න" is not a correct rendering of "Backup Wallet"). The ampersand and ellipsis are present, but the verb and noun are wrong.

Suggested correct translation:
&වැලට් පිටපතක් ගබඩා කරන්න…
```

<!-- cache_translation_check_si_52b76e003b4372c220a11927a3c1b034140fc8911fc5f7e49e4df4f6db2cca7d -->
```
        <source>Create Wallet…</source>
        <translation>පසුම්බිය වසන්න…</translation>
    
ERR
The translation is incorrect. The English source "Create Wallet…" means to create a new wallet, but the Sinhala translation "පසුම්බිය වසන්න…" means "Close the wallet…" which is an entirely different action.

Correct translation:
පසුම්බියක් සාදන්න…
```

<!-- cache_translation_check_si_cf3e249bcf9528ddcbae248e440c7daf41b589c22060b33e84ab098a97298804 -->
```
        <source>&amp;Copy address</source>
        <translation>&amp;ලිපිනයෙහි පිටපතක්</translation>
    
ERR
The Sinhala string reads more like "a copy of the address" (noun) rather than the imperative UI action "Copy address". Also ensure the shortcut marker (&) appears exactly once (it's present, which is fine). Suggested correction to convey the imperative action:

Correct translation:
&ලිපිනය පිටපත් කරන්න
```

<!-- cache_translation_check_si_8a25108a400c7f06e2a814e2ce375550e7d0a7a3ece07f393a6c8d3f0f54050a -->
```
        <source>Open Wallet</source>
        <extracomment>Title of window indicating the progress of opening of a wallet.</extracomment>
        <translation>පසුම්බිය විවෘත කරන්න</translation>
    
ERR
The translation uses an imperative form ("පසුම්බිය විවෘත කරන්න" = "Open the wallet") but the source is a window title indicating the progress of opening a wallet — it should be a noun/gerund like "Opening Wallet" rather than a command. 

Correct translation:
පසුම්බිය විවෘත කිරීම
```

<!-- cache_translation_check_si_3e41bdfc5ba4666fc17d2ef5688e1abaaec684e2347860bdf0dbf79d693cf98c -->
```
        <source>Form</source>
        <translation>වෙතින්</translation>
    
ERR
The translation is incorrect. "වෙතින්" means "from" in Sinhala, which does not correspond to "Form". 

Correct translation:
ෆෝර්ම
```

<!-- cache_translation_check_si_3ef61628869a72a6395522b1638dd3403759e0e7899fa7bd95840aaca2440778 -->
```
        <source>Size of &amp;database cache</source>
        <translation>දත්තසමුදා නිහිතයේ ප්‍රමාණය</translation>
    
ERR
Problems:
- The ampersand (&) marking the shortcut is missing in the translation; it must appear exactly once.
- There's a missing space between "දත්ත" and "සමුදා" (should be two words).
- Slight grammatical spelling: "නිහිතයේ" is incorrect; use "නිහිතයේ" or a more natural phrasing.

Suggested correct translation (with & included once):
&දත්ත සමුදා කෑෂ් ප්‍රමාණය
```

<!-- cache_translation_check_si_6711815f94b4e2c839288dded72d1254d22b01b70bcb229f9c9baa8c60725d58 -->
```
        <source>&amp;Reset Options</source>
        <translation>&amp;නැවත සැකසීමේ විකල්ප</translation>
    
ERR
The Sinhala translation has awkward/misspelled wording and incorrect word order ("නැවත සැකසීමේ විකල්ප" is unnatural and "සැකසීමේ" is misspelled). The ampersand is present once (good), and there are no format specifiers, but the phrasing should be corrected.

Suggested correct translation (imperative UI label):
&විකල්ප නැවත සකස් කරන්න
```

<!-- cache_translation_check_si_70e0f7373f776c86f21e49ac07988786d448a483e2bb9a1e925c80cde5753983 -->
```
        <source>W&amp;allet</source>
        <translation>ප&amp;සුම්බිය</translation>
    
UNK_LANG, not familiar with the Sinhala language 'si'.
```

<!-- cache_translation_check_si_3ef1d8bfa2ba4792958e29386502895d19308ed0bc9bf6ec477197bb955c0957 -->
```
        <source>Enable coin &amp;control features</source>
        <translation>කාසි පාලන විශේෂාංග සබලකරන්න</translation>
    
ERR
The translation is missing the ampersand (&) used for the shortcut key from the source. Also adjust spelling/spacing and a more natural verb. 

Correct translation:
කාසි &පාලන විශේෂාංග සක්‍රිය කරන්න
```

<!-- cache_translation_check_si_0700e73cb08d783c6e998255f8deeb754002bfe303362cff4dcd89e98d68a1ce -->
```
        <source>User Interface &amp;language:</source>
        <translation>අතරු මුහුණතේ &amp;භාෂාව:</translation>
    
ERR
The Sinhala translation has a typo: "අතරු" is incorrect. The correct word for "interface" is "අතුරුමුහුණත" (or "අතුරු මුහුණත"). The ampersand is used correctly (exactly one) and spacing is fine.

Correct translation:
අතුරු මුහුණතේ &භාෂාව:
```

<!-- cache_translation_check_si_3e41bdfc5ba4666fc17d2ef5688e1abaaec684e2347860bdf0dbf79d693cf98c -->
```
        <source>Form</source>
        <translation>වෙතින්</translation>
    
ERR
The translation is incorrect. "වෙතින්" means "from" in Sinhala, which does not correspond to "Form". 

Correct translation:
ෆෝර්ම
```

<!-- cache_translation_check_si_c6ec37b85de735722eca983fbeaae3382136e8c738fdfab254a235c2a3bfbfec -->
```
        <source>&amp;Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>&amp;ලිපිනයෙහි පිටපතක්</translation>
    
ERR
The Sinhala translation is grammatically incorrect for a menu action. "ලිපිනයෙහි පිටපතක්" means "a copy of the address" (noun phrase) rather than an imperative action "Copy address". The shortcut ampersand is present once, which is fine.

Correct translation (imperative/menu action):
&ලිපිනය පිටපත් කරන්න
```

<!-- cache_translation_check_si_cf3e249bcf9528ddcbae248e440c7daf41b589c22060b33e84ab098a97298804 -->
```
        <source>&amp;Copy address</source>
        <translation>&amp;ලිපිනයෙහි පිටපතක්</translation>
    
ERR
The Sinhala string reads more like "a copy of the address" (noun) rather than the imperative UI action "Copy address". Also ensure the shortcut marker (&) appears exactly once (it's present, which is fine). Suggested correction to convey the imperative action:

Correct translation:
&ලිපිනය පිටපත් කරන්න
```

<!-- cache_translation_check_si_9aa8d5613e21f00978196abbc4484eb6789435c3dd2ff23b1b1c917589f733a9 -->
```
        <source>Sign failed</source>
        <translation>ඇතුල් වීමට අසමත්</translation>
    
ERR
The translation is incorrect. "ඇතුල් වීමට අසමත්" means "Failed to log in" or "Failed to enter", which is unrelated to "Sign failed" in the context of digital signatures in Bitcoin.

Correct translation:
අත්සන් කිරීම අසාර්ථක විය
```

<!-- cache_translation_check_si_cf3e249bcf9528ddcbae248e440c7daf41b589c22060b33e84ab098a97298804 -->
```
        <source>&amp;Copy address</source>
        <translation>&amp;ලිපිනයෙහි පිටපතක්</translation>
    
ERR
The Sinhala string reads more like "a copy of the address" (noun) rather than the imperative UI action "Copy address". Also ensure the shortcut marker (&) appears exactly once (it's present, which is fine). Suggested correction to convey the imperative action:

Correct translation:
&ලිපිනය පිටපත් කරන්න
```

<!-- cache_translation_check_si_06c84402aa431068bffe82e026d3bac1bfb118c5d3a69ae2fbc585206556063a -->
```
        <source>Copy transaction &amp;ID</source>
        <translation>ගනුදෙනු &amp;හැඳු. පිටපත්</translation>
    
ERR
The Sinhala is awkward and contains an unnecessary abbreviation/period ("හැඳු.") and incorrect word order. The & shortcut appears once but is placed in the middle of an abbreviation. A clearer, grammatically correct translation (with a single & for the shortcut) is:

Correct translation:
ගනුදෙනු හැඳුනුම්පත &පිටපත් කරන්න
```

<!-- cache_translation_check_si_0b9dde780dfb629b02e7c2af33a0051a1f87b9e944e34a5c1b05a0adc2b8fa7e -->
```
        <source>&amp;Export</source>
        <translation>නිර්යාතය</translation>
    
ERR
The translation is missing the required shortcut marker '&' from the source. The source contains a single '&' and the translation must also include exactly one '&'.

Correct translation:
&නිර්යාතය
```

<!-- cache_translation_check_si_c9c0f6588dead8ceb6f4a2ec319ab7024bd40f6f8372e15a7681b786f684543d -->
```
        <source>Error: Unable to make a backup of your wallet</source>
        <translation>දෝෂය: ඔබගේ පසුම්බිය ප්‍රතිස්ථාපනය කල නොහැකි විය.</translation>
    
ERR
The translation is inaccurate. The English "Unable to make a backup of your wallet" means a backup could not be created, but the Sinhala translation says "ප්‍රතිස්ථාපනය කල නොහැකි විය", which means "could not restore", not "could not back up".

Correct translation:
දෝෂය: ඔබගේ පසුම්බිය බැකප් ලබාගැනීමට නොහැකි විය.
```
</details>

Number of issues: 26.
