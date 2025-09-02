# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model.



<details><summary>kn</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bkn%5D%20request)


<!-- cache_translation_check_kn_bad98e3ac33e5c6239c7b14c25c030aaa0402d054fc3f386621f3d89ab4737a4 -->
```
        <source>C&amp;lose</source>
        <translation>ಮುಚ್ಚು</translation>
    
ERR
The source contains a single shortcut marker (&) which must be preserved exactly once in the translation. The Kannada translation "ಮುಚ್ಚು" is correct for "Close" semantically, but it omits the & shortcut marker.

Correct translation (with one &):
&amp;ಮುಚ್ಚು
```

<!-- cache_translation_check_kn_4076afe6904cc7627651bb177caa242128b98257af2c2f3844eb4ae3a6b49e0d -->
```
        <source>C&amp;hoose</source>
        <translation>&amp;ಕೆಳಗೆ</translation>
    
ERR
The translation is incorrect. The English text "Choose" should be translated as "ಆಯ್ಕೆಮಾಡಿ" in Kannada, and the ampersand should mark the shortcut key correspondingly.

Correct translation:
ಆ&amp;ಯ್ಕೆಮಾಡಿ
```

<!-- cache_translation_check_kn_5193d5801bcd38f5a9623bd5d7573a8fe46cfca38a4afe4a6f84e05b6814d769 -->
```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>ನೀವು ನಿಮ್ಮ ವ್ಯಾಲೆಟ್ ಅನ್ನು ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡಿದರೆ ಮತ್ತು ನಿಮ್ಮ ಪಾಸ್‌ಫ್ರೇಸ್ ಅನ್ನು ಕಳೆದುಕೊಂಡರೆ&lt;b&gt;, ನಿಮ್ಮ ಎಲ್ಲಾ &lt;/b&gt;ಬಿಟ್‌ಕಾಯಿನ್‌ಗಳನ್ನು ನೀವು ಕಳೆದುಕೊಳ್ಳುತ್ತೀರಿ 
 !</translation>
    
ERR
There are two issues with this translation:
1. The placement of the <b> HTML tags is incorrect. In the original, the entire phrase "LOSE ALL OF YOUR BITCOINS" is bolded, but in the translation, only "ನಿಮ್ಮ ಎಲ್ಲಾ" is inside the bold tags, and "ಬಿಟ್‌ಕಾಯಿನ್‌ಗಳನ್ನು" is outside. This breaks the intended formatting.
2. There is an unnecessary space and newline before the exclamation mark at the end.

Correct translation:
ಚೆತವನೆ: ನೀವು ನಿಮ್ಮ ವ್ಯಾಲೆಟ್ ಅನ್ನು ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡಿ ನಿಮ್ಮ ಪಾಸ್‌ಫ್ರೇಸ್ ಅನ್ನು ಕಳೆದುಕೊಂಡರೆ, ನೀವು &lt;b&gt;ನಿಮ್ಮ ಎಲ್ಲಾ ಬಿಟ್‌ಕಾಯಿನ್‌ಗಳನ್ನು ಕಳೆದುಕೊಳ್ಳುತ್ತೀರಿ&lt;/b&gt;!
```

<!-- cache_translation_check_kn_1d6c9ec3a92b548d756f466c63d2d28de91a921fd403f425ba069c993cc04fb8 -->
```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>ನಿಮ್ಮ ವಾಲೆಟ್ ಎನ್ಕ್ರಿಪ್ಟ್ ಮಾಡುವುದರಿಂದ ನಿಮ್ಮ ಕಂಪ್ಯೂಟರ್ ಸೋಕಿದ ಮಲ್ವೇರ್ ನೋಂದಣಿಗೆ ಬಲಗೊಳಿಸುವ ಕಾದಂಬರಿಗೆ ನಿಮ್ಮ ಬಿಟ್‌ಕಾಯಿನ್ ಪೂರ್ತಿಯಾಗಿ ಸುರಕ್ಷಿತವಾಗುವುದಿಲ್ಲವೆಂದು ನೆನಪಿಡಿ.</translation>
    
ERR
The Kannada translation has grammatical errors, awkward phrasing, and a mistranslation of some terms. For example, "ಮಲ್ವೇರ್ ನೋಂದಣಿಗೆ ಬಲಗೊಳಿಸುವ ಕಾದಂಬರಿಗೆ" does not accurately convey the idea of malware stealing bitcoins. "ಕಾದಂಬರಿ" means 'novel' in Kannada, which is incorrect here.

Correct translation:
ನಿಮ್ಮ ವಾಲೆಟ್ ಎನ್ಕ್ರಿಪ್ಟ್ ಮಾಡಿದರೂ ಅದು ನಿಮ್ಮ ಕಂಪ್ಯೂಟರ್‌ಗೆ ಮಲ್ವೇರ್ ಸೋಂಕು ಹೇರಿದರೆ ನಿಮ್ಮ ಬಿಟ್‌ಕಾಯಿನ್‌ಗಳನ್ನು ಸಂಪೂರ್ಣವಾಗಿ ರಕ್ಷಿಸಲು ಸಾಧ್ಯವಿಲ್ಲವೆಂಬುದನ್ನು ನೆನಪಿಟ್ಟುಕೊಳ್ಳಿ.
```

<!-- cache_translation_check_kn_9086fc92256fb10bea51df259b84a5eeec6f4584168797f0169c602c76e6fb9b -->
```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>ಪ್ರಮುಖ: ನೀವು ಹಿಂದಿನದನ್ನು ತಯಾರಿಸಿದ ವಾಲೆಟ್ ಫೈಲ್‌ನ ಯಾವುದೇ ಹಿಂದಿನ ಬ್ಯಾಕಪ್‌ಗಳನ್ನು ಹೊಂದಿದ್ದರೆ ಅವುಗಳನ್ನು ಹೊಸದಾಗಿ ತಯಾರಿಸಲಿಕ್ಕೆ ಬದಲಾಯಿಸಬೇಕು. ಭದ್ರತೆ ಕಾರಣಕ್ಕಾಗಿ, ಅನ್ನುವಂತಹ ವಾಲೆಟ್ ಫೈಲ್‌ನ ಹಿಂದಿನ ಬ್ಯಾಕಪ್‌ಗಳು ಹೊಸದಾದ ಎನ್ಕ್ರಿಪ್ಟ್ ವಾಲೆಟ್ ಬಳಸುವಂತೆ ಆಗ ಹೇಗೆ ಪಾರುಮಾಡಲು ಅಸಮರ್ಥವಾಗುತ್ತವೆ.</translation>
    
ERR
The translation is incomplete and contains several inaccurate or awkward phrases. The sentence structure is convoluted, and it does not fully or clearly convey all the details of the original English text, especially the explanation on why previous unencrypted backups become useless.

Correct translation:
ಪ್ರಮುಖ: ನೀವು ನಿಮ್ಮ ವಾಲೆಟ್ ಫೈಲ್‌ನ ಹಿಂದಿನ ಯಾವುದೇ ಬ್ಯಾಕಪ್‌ಗಳನ್ನು ಮಾಡಿದಿದ್ದರೆ, ಅವುಗಳನ್ನು ಹೊಸದಾಗಿ ರಚಿಸಲಾದ, ಎನ್ಕ್ರಿಪ್ಟ್ ಮಾಡಲಾದ ವಾಲೆಟ್ ಫೈಲ್‌ನೊಂದಿಗೆ ಬದಲಾಯಿಸಬೇಕು. ಭದ್ರತಾ ಕಾರಣಗಳಿಗೆ, ನೀವು ಹೊಸ ಎನ್ಕ್ರಿಪ್ಟ್ ಮಾಡಲಾದ ವಾಲೆಟ್ ಅನ್ನು ಬಳಸಿ ಪ್ರಾರಂಭಿಸುವ ಸಂದರ್ಭದಲ್ಲಿ ಎನ್ಕ್ರಿಪ್ಟ್ ಮಾಡದ ವಾಲೆಟ್ ಫೈಲ್‌ನ ಹಿಂದಿನ ಬ್ಯಾಕಪ್‌ಗಳು ಅನಾವಶ್ಯಕವಾಗುತ್ತವೆ.
```

<!-- cache_translation_check_kn_54f0cf1be57332e4dc85471818984b5b7658316aef35eab5011b63bdaedc8ae5 -->
```
        <source>About &amp;Qt</source>
        <translation> ಕುರಿತು &amp; ಕ್ಯೂಟಿ</translation>
    
ERR
There is an unnecessary space at the beginning of the translation (" ಕುರಿತು ..."). The translation should not start with a stray space.

Correct translation:
&amp;Qt ಕುರಿತು
```

<!-- cache_translation_check_kn_8be325fea8c30e94028ef35416d02203876cf5063bc9408b0bb9431cca546cd0 -->
```
        <source>&amp;Encrypt Wallet…</source>
        <translation>ವಾಲೆಟ್ ಎನ್‌ಕ್ರಿಪ್ಟ್ (ಗೂಢಲಿಪೀಕರಣ) ಮಾಡಿ</translation>
    
ERR
The translation is missing the shortcut key indicator (&) present in the source. The ampersand should appear exactly once in the translation to allow menu shortcuts.

Correct translation:
ವಾಲೆಟ್ ಅನ್ನು &ಎನ್‌ಕ್ರಿಪ್ಟ್ (ಗೂಢಲಿಪೀಕರಣ) ಮಾಡಿ
```

<!-- cache_translation_check_kn_668206c32665bdfbaf7a9c49f0846807509dbb855ebf7c109e6559422d7068ee -->
```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>ನೀವು ಸಾಮಾನ್ಯ ಫೀ ಬಗ್ಗೆ ಹೆಚ್ಚಿನ ಲಾಗಿನ ಸಂದರ್ಶನಕ್ಕಿಂತ ಪಾಂಡ್ರಹಿಸುವುದಕ್ಕಿಂತ ಭಾಗಶಃ ಖರೀದಿ ಟ್ರಾನ್ಸ್ಯಾಕ್ಷನ್ ಆಯ್ಕೆಯನ್ನು ಆಯ್ಕೆಮಾಡುವುದರ ಮೇಲೆ ಪ್ರಾಥಮಿಕತೆಯನ್ನು ಕೊಡುವುದಕ್ಕಾಗಿ ನೀವು ಅಧಿಕವಾದ ಟ್ರಾನ್ಸ್ಯಾಕ್ಷನ್ ಫೀ ಪಾವತಿಸುತ್ತೀರಿ.</translation>
    
ERR
The translation is problematic due to several reasons:
- The sentence is convoluted and unclear.
- It introduces awkward or incorrect Kannada wordings such as "ಬಹುಶಃ ಖರೀದಿ ಟ್ರಾನ್ಸ್ಯಾಕ್ಷನ್ ಆಯ್ಕೆಯನ್ನು ಆಯ್ಕೆಮಾಡುವುದರ ಮೇಲೆ" which does not precisely convey "partial spend avoidance".
- The technical terms are mistranslated; for example "partial spend avoidance" is not clearly conveyed.
- The format and clarity need improvement.

Correct translation:
ಇದು ನೀವು ಭಾಗಶಃ ವೆಚ್ಚ ತಪ್ಪಿಸಲು ಸಾಮಾನ್ಯ ನಾಣ್ಯ ಆಯ್ವೆಗೆ ಬದಲು ಆದ್ಯತೆ ನೀಡಲು (ಸಾಮಾನ್ಯ ಶುಲ್ಕಕ್ಕೆ ಜೊತೆಗೆ) ಪಾವತಿಸುವ ಗರಿಷ್ಠ ವ್ಯವಹಾರ ಶುಲ್ಕವಾಗಿದೆ.
```

<!-- cache_translation_check_kn_c190fbc90d54e9f97703b4f14006e62be733de11b8fa80a56637bce1767ee3ff -->
```
        <source>Unsupported chainstate database format found. Please restart with -reindex-chainstate. This will rebuild the chainstate database.</source>
        <translation>ಬೆಂಬಲಿಗೆಯ ತರಬೇತಿ ಡೇಟಾಬೇಸ್ ಸ್ವರೂಪ ಅಸಮರ್ಥಿತವಾಗಿದೆ. ದಯವಿಟ್ಟು -reindex-chainstate ನೊಂದಿಗೆ ಮರುಪ್ರಾರಂಭಿಸಿ. ಇದು ಬೆಂಬಲಿಗೆಯ ತರಬೇತಿ ಡೇಟಾಬೇಸ್ ಪೂರ್ತಿಯಾಗಿ ಮರುಸ್ಥಾಪಿಸುತ್ತದೆ.</translation>
    
ERR
The translation is problematic. The term "chainstate" specific to Bitcoin has been incorrectly translated as "ಬೆಂಬಲಿಗೆಯ ತರಬೇತಿ ಡೇಟಾಬೇಸ್" which means "supporter training database". The translation misunderstands both "chainstate" and "unsupported" terms.

Correct translation:
ಅನುಪ ಮೇಲಂಬಡಿಸಲಾದ ಚೈನ್ಸ್ಟೇಟ್ ಡೇಟಾಬೇಸ್ ಸ್ವರೂಪ ಕಂಡುಬಂದಿದೆ. ದಯವಿಟ್ಟು -reindex-chainstate ನೊಂದಿಗೆ ಮರುಪ್ರಾರಂಭಿಸಿ. ಇದರಿಂದ ಚೈನ್ಸ್ಟೇಟ್ ಡೇಟಾಬೇಸ್ ಮರು ನಿರ್ಮಿಸಲಾಗುತ್ತದೆ.
```

<!-- cache_translation_check_kn_8f3615c9565492adbd9a30bcad880e49b286dd2a6afb8779568a53048ff27167 -->
```
        <source>Error: Duplicate descriptors created during migration. Your wallet may be corrupted.</source>
        <translation>ದೋಷ: ವರ್ಣನೆಗಳ ಪುನರ್ವಿನಿಮಯದ ಸಮಯದಲ್ಲಿ ನಕಲಿ ವರ್ಣನೆಗಳು ರಚಿಸಲಾಗಿವೆ. ನಿಮ್ಮ ಬಟ್ಟೆ ಹಾಕಿದ ಕಾರ್ಟೆಜ್ ಹಾಳಾಗಿರಬಹುದು.</translation>
    
ERR
The translation contains several inaccuracies:
1. "ವರ್ಣನೆಗಳು ಪುನರ್ವಿನಿಮಯದ ಸಮಯದಲ್ಲಿ" translates roughly to "during the time of exchanging descriptions," which is not an accurate rendering of "Duplicate descriptors created during migration."
2. "ನಿಮ್ಮ ಬಟ್ಟೆ ಹಾಕಿದ ಕಾರ್ಟೆಜ್ ಹಾಳಾಗಿರಬಹುದು." is incorrect. "ಬಟ್ಟೆ ಹಾಕಿದ ಕಾರ್ಟೆಜ್" does not mean "your wallet" – this appears to be a mistranslation or gibberish.

Correct translation:
ದೋಷ: ಮਿਗ್ರೇಷನ್ ಸಮಯದಲ್ಲಿ ನಕಲಿ ವರ್ಣನಗಳ (ಡಿಸ್‌ಕ್ರಿಪ್ಟರ್‌) ಗಳನ್ನು ರಚಿಸಲಾಗಿದೆ. ನಿಮ್ಮ ವಾಲೆಟ್ ಹಾಳಾಗಿರಬಹುದು.
```

<!-- cache_translation_check_kn_9d73d3dce57f97f1d1f2355c214cec83f0cf6e496648db5e372e26398fe7c3be -->
```
        <source>Failed to rename invalid peers.dat file. Please move or delete it and try again.</source>
        <translation>ಅಮಾನ್ಯ ಸಹಾಯಕ ಫೈಲ್ peers.dat ಅನ್ನು ಹೆಸರು ಬದಲಾಯಿಸಲು ವಿಫಲವಾಗಿದೆ. ದಯವಿಟ್ಟು ಅದನ್ನು ತೆಗೆದುಹಾಕಿ ಅಥವಾ ಅದನ್ನು ಹೆಸರು ಬದಲಾಯಿಸಿ ಮತ್ತೆ ಪ್ರಯತ್ನಿಸಿ.</translation>
    
ERR
The translation is inaccurate. The term "ಅಮಾನ್ಯ ಸಹಾಯಕ ಫೈಲ್ peers.dat" translates as "invalid assistant file peers.dat," which misrepresents the meaning of "invalid peers.dat file." Additionally, the translation says either delete or rename, while the original says move or delete.

Correct translation:
ಅಮಾನ್ಯ peers.dat ಫೈಲ್ ಅನ್ನು ಹೆಸರು ಬದಲಾಯಿಸುವಲ್ಲಿ ವಿಫಲವಾಗಿದೆ. ದಯವಿಟ್ಟು ಅದನ್ನು ಸ್ಥಳಾಂತರಿಸಿ ಅಥವಾ ಅಳಿಸಿ ನಂತರ ಪುನಃ ಪ್ರಯತ್ನಿಸಿ.
```

<!-- cache_translation_check_kn_d4778526c3cb7bacd81496b149d595e844e53ead8a22bdd5bd46f67ec8b9c525 -->
```
        <source>Incompatible options: -dnsseed=1 was explicitly specified, but -onlynet forbids connections to IPv4/IPv6</source>
        <translation>ಅಸಮರ್ಥ ಆಯ್ಕೆಗಳು: -dnsseed=1 ದೃಷ್ಟಿಯಲ್ಲಿದ್ದರೂ, -onlynet ದ್ವಾರಾ IPv4/IPv6 ಸಂಪರ್ಕಗಳನ್ನು ನಿಷೇಧಿಸುತ್ತದೆ.
 
 </translation>
    
ERR
There are issues with clarity and formatting:
- The translation "ದೃಷ್ಟಿಯಲ್ಲಿದ್ದರೂ" means "even though considered," which is not the intended meaning in this technical context. "Explicitly specified" should be translated as "ಸ್ಪಷ್ಟವಾಗಿ ಸೂಚಿಸಲಾಗಿದೆ."
- There is unwanted extra whitespace/linebreaks in the translation.
- The sentence construction could be improved for clarity and precision in technical Kannada.

Correct translation:
ಅನುಕೂಲವಲ್ಲದ ಆಯ್ಕೆಗಳು: -dnsseed=1 ಅನ್ನು ಸ್ಪಷ್ಟವಾಗಿ ಸೂಚಿಸಲಾಗಿದೆ, ಆದರೆ -onlynet ಗೆ IPv4/IPv6 ಸಂಪರ್ಕಗಳನ್ನು ನಿಷೇಧಿಸುತ್ತದೆ.
```

<!-- cache_translation_check_kn_109b52a31934efbca038fdcc56e232dc7951f1e1d2e4585c9208da49bf9ada0f -->
```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>ನೀವು ಟ್ರಾನ್ಸ್ಯಾಕ್ಷನ್ ಕಳುಹಿಸುವಾಗ ನೀವು ಪಾವತಿ ವಿಧಾನದ ಮೂಲಕ ಪಾವತಿ ಶುಲ್ಕವನ್ನು ಪಾವತಿ ಕಳುಹಿಸುವಾಗ ನೀವು ಕೊಡಬೇಕಾದ ಶುಲ್ಕ.</translation>
    
ERR
The translation is verbose, repetitive, and awkward. The sentence repeats "ನೀವು ಪಾವತಿ ಕಳುಹಿಸುವಾಗ" ("when you send payment") and generally adds unnecessary complexity and redundancy. The original sentence is simple and direct.

Correct translation:
ನೀವು ಟ್ರಾನ್ಸ್‌್ಯಾಕ್ಷನ್ ಕಳುಹಿಸಿದರೆ ನೀಡಬೇಕಾದ ಶುಲ್ಕ ಇದು.
```

<!-- cache_translation_check_kn_3e71143bcba8c0af358748e40dab95d7907442e2e7ad7bc8d19d65904db46f62 -->
```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>ಲೆಕ್ಕಾಚಾರದಲ್ಲಿ ಬದಲಾವಣೆ ವಿನಂತಿಯನ್ನು ಹೊಂದಿರುವ ಟ್ರಾನ್ಸ್ಯಾಕ್ಷನ್ ಕೆಲವು ಬದಲಾವಣೆ ವಿನಂತಿಗಳನ್ನು ಹೊಂದಿದೆ, ಆದರೆ ಅದನ್ನು ಉಂಟುಮಾಡಲು ಆಗದಿದೆ.</translation>
    
ERR
The Kannada translation is inaccurate and redundant. It repeats "ಬದಲಾವಣೆ ವಿನಂತಿಯನ್ನು ಹೊಂದಿದೆ" (has change request) and does not correctly convey the meaning of "change address." The correct translation should mention "ಬದಲಾವಣೆಯ ವಿಳಾಸವನ್ನು" (change address) rather than a change request.

Correct translation:
ಟ್ರಾನ್ಸ್ಯಾಕ್ಷನ್‌ಗೆ ಬದಲಾವಣೆಯ ವಿಳಾಸ ಬೇಕಿದೆ, ಆದರೆ ಅದನ್ನು ನಾವು ಸೃಜಿಸದೆ ಸಾಧ್ಯವಾಗುತ್ತಿಲ್ಲ.
```
</details>

Number of issues: 14.
