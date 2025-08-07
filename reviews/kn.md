# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>kn</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bkn%5D%20low%20quality)


```
        <source>Close</source>
        <translation>ನಕಲುಕಳೆದುಕೊಳ್ಳುತ್ತಾರೆ</translation>
    
YES  
The translation "ನಕಲುಕಳೆದುಕೊಳ್ಳುತ್ತಾರೆ" is incorrect for "Close". The correct Kannada translation should be "ಮುಚ್ಚು" or "ಮುಚ್ಚುಕು".  
Correct translation:  
ಮುಚ್ಚು
```

```
        <source>Choose</source>
        <translation>ಕೆಳಗೆ</translation>
    
YES
The translation is incorrect. "ಕೆಳಗೆ" means "down" or "below" in Kannada, not "Choose". The correct translation for "Choose" in Kannada is "ಆಯ್ಕೆಮಾಡಿ".

Correct translation:
ಆಯ್ಕೆಮಾಡಿ
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>ನೀವು ನಿಮ್ಮ ವ್ಯಾಲೆಟ್ ಅನ್ನು ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡಿದರೆ ಮತ್ತು ನಿಮ್ಮ ಪಾಸ್‌ಫ್ರೇಸ್ ಅನ್ನು ಕಳೆದುಕೊಂಡರೆ&lt;b&gt;, ನಿಮ್ಮ ಎಲ್ಲಾ &lt;/b&gt;ಬಿಟ್‌ಕಾಯಿನ್‌ಗಳನ್ನು ನೀವು ಕಳೆದುಕೊಳ್ಳುತ್ತೀರಿ 
 !</translation>
    
YES
There are two issues with this translation:
1. The placement of the <b> HTML tags is incorrect. In the original, the entire phrase "LOSE ALL OF YOUR BITCOINS" is bolded, but in the translation, only "ನಿಮ್ಮ ಎಲ್ಲಾ" is inside the bold tags, and "ಬಿಟ್‌ಕಾಯಿನ್‌ಗಳನ್ನು" is outside. This breaks the intended formatting.
2. There is an unnecessary space and newline before the exclamation mark at the end.

Correct translation:
ಚೆತವನೆ: ನೀವು ನಿಮ್ಮ ವ್ಯಾಲೆಟ್ ಅನ್ನು ಎನ್‌ಕ್ರಿಪ್ಟ್ ಮಾಡಿ ನಿಮ್ಮ ಪಾಸ್‌ಫ್ರೇಸ್ ಅನ್ನು ಕಳೆದುಕೊಂಡರೆ, ನೀವು &lt;b&gt;ನಿಮ್ಮ ಎಲ್ಲಾ ಬಿಟ್‌ಕಾಯಿನ್‌ಗಳನ್ನು ಕಳೆದುಕೊಳ್ಳುತ್ತೀರಿ&lt;/b&gt;!
```

```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>ನಿಮ್ಮ ವಾಲೆಟ್ ಎನ್ಕ್ರಿಪ್ಟ್ ಮಾಡುವುದರಿಂದ ನಿಮ್ಮ ಕಂಪ್ಯೂಟರ್ ಸೋಕಿದ ಮಲ್ವೇರ್ ನೋಂದಣಿಗೆ ಬಲಗೊಳಿಸುವ ಕಾದಂಬರಿಗೆ ನಿಮ್ಮ ಬಿಟ್‌ಕಾಯಿನ್ ಪೂರ್ತಿಯಾಗಿ ಸುರಕ್ಷಿತವಾಗುವುದಿಲ್ಲವೆಂದು ನೆನಪಿಡಿ.</translation>
    
YES
The Kannada translation has grammatical errors, awkward phrasing, and a mistranslation of some terms. For example, "ಮಲ್ವೇರ್ ನೋಂದಣಿಗೆ ಬಲಗೊಳಿಸುವ ಕಾದಂಬರಿಗೆ" does not accurately convey the idea of malware stealing bitcoins. "ಕಾದಂಬರಿ" means 'novel' in Kannada, which is incorrect here.

Correct translation:
ನಿಮ್ಮ ವಾಲೆಟ್ ಎನ್ಕ್ರಿಪ್ಟ್ ಮಾಡಿದರೂ ಅದು ನಿಮ್ಮ ಕಂಪ್ಯೂಟರ್‌ಗೆ ಮಲ್ವೇರ್ ಸೋಂಕು ಹೇರಿದರೆ ನಿಮ್ಮ ಬಿಟ್‌ಕಾಯಿನ್‌ಗಳನ್ನು ಸಂಪೂರ್ಣವಾಗಿ ರಕ್ಷಿಸಲು ಸಾಧ್ಯವಿಲ್ಲವೆಂಬುದನ್ನು ನೆನಪಿಟ್ಟುಕೊಳ್ಳಿ.
```

```
        <source>IMPORTANT: Any previous backups you have made of your wallet file should be replaced with the newly generated, encrypted wallet file. For security reasons, previous backups of the unencrypted wallet file will become useless as soon as you start using the new, encrypted wallet.</source>
        <translation>ಪ್ರಮುಖ: ನೀವು ಹಿಂದಿನದನ್ನು ತಯಾರಿಸಿದ ವಾಲೆಟ್ ಫೈಲ್‌ನ ಯಾವುದೇ ಹಿಂದಿನ ಬ್ಯಾಕಪ್‌ಗಳನ್ನು ಹೊಂದಿದ್ದರೆ ಅವುಗಳನ್ನು ಹೊಸದಾಗಿ ತಯಾರಿಸಲಿಕ್ಕೆ ಬದಲಾಯಿಸಬೇಕು. ಭದ್ರತೆ ಕಾರಣಕ್ಕಾಗಿ, ಅನ್ನುವಂತಹ ವಾಲೆಟ್ ಫೈಲ್‌ನ ಹಿಂದಿನ ಬ್ಯಾಕಪ್‌ಗಳು ಹೊಸದಾದ ಎನ್ಕ್ರಿಪ್ಟ್ ವಾಲೆಟ್ ಬಳಸುವಂತೆ ಆಗ ಹೇಗೆ ಪಾರುಮಾಡಲು ಅಸಮರ್ಥವಾಗುತ್ತವೆ.</translation>
    
YES
The translation is incomplete and contains several inaccurate or awkward phrases. The sentence structure is convoluted, and it does not fully or clearly convey all the details of the original English text, especially the explanation on why previous unencrypted backups become useless.

Correct translation:
ಪ್ರಮುಖ: ನೀವು ನಿಮ್ಮ ವಾಲೆಟ್ ಫೈಲ್‌ನ ಹಿಂದಿನ ಯಾವುದೇ ಬ್ಯಾಕಪ್‌ಗಳನ್ನು ಮಾಡಿದಿದ್ದರೆ, ಅವುಗಳನ್ನು ಹೊಸದಾಗಿ ರಚಿಸಲಾದ, ಎನ್ಕ್ರಿಪ್ಟ್ ಮಾಡಲಾದ ವಾಲೆಟ್ ಫೈಲ್‌ನೊಂದಿಗೆ ಬದಲಾಯಿಸಬೇಕು. ಭದ್ರತಾ ಕಾರಣಗಳಿಗೆ, ನೀವು ಹೊಸ ಎನ್ಕ್ರಿಪ್ಟ್ ಮಾಡಲಾದ ವಾಲೆಟ್ ಅನ್ನು ಬಳಸಿ ಪ್ರಾರಂಭಿಸುವ ಸಂದರ್ಭದಲ್ಲಿ ಎನ್ಕ್ರಿಪ್ಟ್ ಮಾಡದ ವಾಲೆಟ್ ಫೈಲ್‌ನ ಹಿಂದಿನ ಬ್ಯಾಕಪ್‌ಗಳು ಅನಾವಶ್ಯಕವಾಗುತ್ತವೆ.
```

```
        <source>This error could occur if this wallet was not shutdown cleanly and was last loaded using a build with a newer version of Berkeley DB. If so, please use the software that last loaded this wallet</source>
        <translation>ಈ ದೋಷ ಕ್ರಿಯೆಗೆ ಕೊನೆಯಾಗಿದ್ದ ಬರ್ಕ್ಲಿ ಡಿಬಿಯುಂಟುವಿನ ಹೊಸ ಸಂಸ್ಕರಣವನ್ನು ಬಳಸಿದ್ದ ಬದಲಾವಣೆಯ ಸಂಗಡ ಈ ವಾಲೆಟ್ ಕ್ರಿಯೆಯನ್ನು ಶುಚಿಗೊಳಿಸಲು ಕೊನೆಗೆ ಆಯ್ಕೆಮಾಡಿದೆಯೇ ಎಂದಾದರೆ, ದಯವಿಟ್ಟು ಈ ವಾಲೆಟ್ ಸೋಫ್ಟ್‌ವೇರ್ ಬಳಸಿದ ಅಂತಿಮ ಬರ್ಷನ್ ಅನ್ನು ಬಳಸಿ.</translation>
    
YES
The translation is problematic. The Kannada translation is inaccurate, has confusing phrasing, and does not clearly convey the original intent. Additionally, there are minor grammar errors and unnatural sentence structure. For example, the translation confuses "shutdown cleanly" and "build with newer version" concepts.

Correct translation:
ಈ ತಪ್ಪು ಸಂಭವಿಸಬಹುದು, ಈ ವಾಲೆಟ್ ಅನ್ನು ಸರಿಯಾಗಿ ಮುಚ್ಚಲಾಗದಿದ್ದರೆ ಮತ್ತು ಕೊನೆಯ ಬಾರಿ ಇದು ಹೊಸ ಆವೃತ್ತಿಯ Berkeley DB ಬಳಸಿ ಲೋಡ್ ಮಾಡಲಾಗಿದ್ದರೆ. ಅಂಥಹಾಗಿದ್ದರೆ, ದಯವಿಟ್ಟು ಈ ವಾಲೆಟ್ ಅನ್ನು ಕೊನೆಯ ಬಾರಿ ಲೋಡ್ ಮಾಡಿದ ಸಾಫ್ಟ್‌ವೇರ್ ಬಳಸಿ.
```

```
        <source>This is the maximum transaction fee you pay (in addition to the normal fee) to prioritize partial spend avoidance over regular coin selection.</source>
        <translation>ನೀವು ಸಾಮಾನ್ಯ ಫೀ ಬಗ್ಗೆ ಹೆಚ್ಚಿನ ಲಾಗಿನ ಸಂದರ್ಶನಕ್ಕಿಂತ ಪಾಂಡ್ರಹಿಸುವುದಕ್ಕಿಂತ ಭಾಗಶಃ ಖರೀದಿ ಟ್ರಾನ್ಸ್ಯಾಕ್ಷನ್ ಆಯ್ಕೆಯನ್ನು ಆಯ್ಕೆಮಾಡುವುದರ ಮೇಲೆ ಪ್ರಾಥಮಿಕತೆಯನ್ನು ಕೊಡುವುದಕ್ಕಾಗಿ ನೀವು ಅಧಿಕವಾದ ಟ್ರಾನ್ಸ್ಯಾಕ್ಷನ್ ಫೀ ಪಾವತಿಸುತ್ತೀರಿ.</translation>
    
YES
The translation is problematic due to several reasons:
- The sentence is convoluted and unclear.
- It introduces awkward or incorrect Kannada wordings such as "ಬಹುಶಃ ಖರೀದಿ ಟ್ರಾನ್ಸ್ಯಾಕ್ಷನ್ ಆಯ್ಕೆಯನ್ನು ಆಯ್ಕೆಮಾಡುವುದರ ಮೇಲೆ" which does not precisely convey "partial spend avoidance".
- The technical terms are mistranslated; for example "partial spend avoidance" is not clearly conveyed.
- The format and clarity need improvement.

Correct translation:
ಇದು ನೀವು ಭಾಗಶಃ ವೆಚ್ಚ ತಪ್ಪಿಸಲು ಸಾಮಾನ್ಯ ನಾಣ್ಯ ಆಯ್ವೆಗೆ ಬದಲು ಆದ್ಯತೆ ನೀಡಲು (ಸಾಮಾನ್ಯ ಶುಲ್ಕಕ್ಕೆ ಜೊತೆಗೆ) ಪಾವತಿಸುವ ಗರಿಷ್ಠ ವ್ಯವಹಾರ ಶುಲ್ಕವಾಗಿದೆ.
```

```
        <source>Unsupported chainstate database format found. Please restart with -reindex-chainstate. This will rebuild the chainstate database.</source>
        <translation>ಬೆಂಬಲಿಗೆಯ ತರಬೇತಿ ಡೇಟಾಬೇಸ್ ಸ್ವರೂಪ ಅಸಮರ್ಥಿತವಾಗಿದೆ. ದಯವಿಟ್ಟು -reindex-chainstate ನೊಂದಿಗೆ ಮರುಪ್ರಾರಂಭಿಸಿ. ಇದು ಬೆಂಬಲಿಗೆಯ ತರಬೇತಿ ಡೇಟಾಬೇಸ್ ಪೂರ್ತಿಯಾಗಿ ಮರುಸ್ಥಾಪಿಸುತ್ತದೆ.</translation>
    
YES
The translation is problematic. The term "chainstate" specific to Bitcoin has been incorrectly translated as "ಬೆಂಬಲಿಗೆಯ ತರಬೇತಿ ಡೇಟಾಬೇಸ್" which means "supporter training database". The translation misunderstands both "chainstate" and "unsupported" terms.

Correct translation:
ಅನುಪ ಮೇಲಂಬಡಿಸಲಾದ ಚೈನ್ಸ್ಟೇಟ್ ಡೇಟಾಬೇಸ್ ಸ್ವರೂಪ ಕಂಡುಬಂದಿದೆ. ದಯವಿಟ್ಟು -reindex-chainstate ನೊಂದಿಗೆ ಮರುಪ್ರಾರಂಭಿಸಿ. ಇದರಿಂದ ಚೈನ್ಸ್ಟೇಟ್ ಡೇಟಾಬೇಸ್ ಮರು ನಿರ್ಮಿಸಲಾಗುತ್ತದೆ.
```

```
        <source>Error: Duplicate descriptors created during migration. Your wallet may be corrupted.</source>
        <translation>ದೋಷ: ವರ್ಣನೆಗಳ ಪುನರ್ವಿನಿಮಯದ ಸಮಯದಲ್ಲಿ ನಕಲಿ ವರ್ಣನೆಗಳು ರಚಿಸಲಾಗಿವೆ. ನಿಮ್ಮ ಬಟ್ಟೆ ಹಾಕಿದ ಕಾರ್ಟೆಜ್ ಹಾಳಾಗಿರಬಹುದು.</translation>
    
YES
The translation contains several inaccuracies:
1. "ವರ್ಣನೆಗಳು ಪುನರ್ವಿನಿಮಯದ ಸಮಯದಲ್ಲಿ" translates roughly to "during the time of exchanging descriptions," which is not an accurate rendering of "Duplicate descriptors created during migration."
2. "ನಿಮ್ಮ ಬಟ್ಟೆ ಹಾಕಿದ ಕಾರ್ಟೆಜ್ ಹಾಳಾಗಿರಬಹುದು." is incorrect. "ಬಟ್ಟೆ ಹಾಕಿದ ಕಾರ್ಟೆಜ್" does not mean "your wallet" – this appears to be a mistranslation or gibberish.

Correct translation:
ದೋಷ: ಮਿਗ್ರೇಷನ್ ಸಮಯದಲ್ಲಿ ನಕಲಿ ವರ್ಣನಗಳ (ಡಿಸ್‌ಕ್ರಿಪ್ಟರ್‌) ಗಳನ್ನು ರಚಿಸಲಾಗಿದೆ. ನಿಮ್ಮ ವಾಲೆಟ್ ಹಾಳಾಗಿರಬಹುದು.
```

```
        <source>Failed to rename invalid peers.dat file. Please move or delete it and try again.</source>
        <translation>ಅಮಾನ್ಯ ಸಹಾಯಕ ಫೈಲ್ peers.dat ಅನ್ನು ಹೆಸರು ಬದಲಾಯಿಸಲು ವಿಫಲವಾಗಿದೆ. ದಯವಿಟ್ಟು ಅದನ್ನು ತೆಗೆದುಹಾಕಿ ಅಥವಾ ಅದನ್ನು ಹೆಸರು ಬದಲಾಯಿಸಿ ಮತ್ತೆ ಪ್ರಯತ್ನಿಸಿ.</translation>
    
YES
The translation is inaccurate. The term "ಅಮಾನ್ಯ ಸಹಾಯಕ ಫೈಲ್ peers.dat" translates as "invalid assistant file peers.dat," which misrepresents the meaning of "invalid peers.dat file." Additionally, the translation says either delete or rename, while the original says move or delete.

Correct translation:
ಅಮಾನ್ಯ peers.dat ಫೈಲ್ ಅನ್ನು ಹೆಸರು ಬದಲಾಯಿಸುವಲ್ಲಿ ವಿಫಲವಾಗಿದೆ. ದಯವಿಟ್ಟು ಅದನ್ನು ಸ್ಥಳಾಂತರಿಸಿ ಅಥವಾ ಅಳಿಸಿ ನಂತರ ಪುನಃ ಪ್ರಯತ್ನಿಸಿ.
```

```
        <source>Incompatible options: -dnsseed=1 was explicitly specified, but -onlynet forbids connections to IPv4/IPv6</source>
        <translation>ಅಸಮರ್ಥ ಆಯ್ಕೆಗಳು: -dnsseed=1 ದೃಷ್ಟಿಯಲ್ಲಿದ್ದರೂ, -onlynet ದ್ವಾರಾ IPv4/IPv6 ಸಂಪರ್ಕಗಳನ್ನು ನಿಷೇಧಿಸುತ್ತದೆ.
 
 </translation>
    
YES
There are issues with clarity and formatting:
- The translation "ದೃಷ್ಟಿಯಲ್ಲಿದ್ದರೂ" means "even though considered," which is not the intended meaning in this technical context. "Explicitly specified" should be translated as "ಸ್ಪಷ್ಟವಾಗಿ ಸೂಚಿಸಲಾಗಿದೆ."
- There is unwanted extra whitespace/linebreaks in the translation.
- The sentence construction could be improved for clarity and precision in technical Kannada.

Correct translation:
ಅನುಕೂಲವಲ್ಲದ ಆಯ್ಕೆಗಳು: -dnsseed=1 ಅನ್ನು ಸ್ಪಷ್ಟವಾಗಿ ಸೂಚಿಸಲಾಗಿದೆ, ಆದರೆ -onlynet ಗೆ IPv4/IPv6 ಸಂಪರ್ಕಗಳನ್ನು ನಿಷೇಧಿಸುತ್ತದೆ.
```

```
        <source>This is the transaction fee you will pay if you send a transaction.</source>
        <translation>ನೀವು ಟ್ರಾನ್ಸ್ಯಾಕ್ಷನ್ ಕಳುಹಿಸುವಾಗ ನೀವು ಪಾವತಿ ವಿಧಾನದ ಮೂಲಕ ಪಾವತಿ ಶುಲ್ಕವನ್ನು ಪಾವತಿ ಕಳುಹಿಸುವಾಗ ನೀವು ಕೊಡಬೇಕಾದ ಶುಲ್ಕ.</translation>
    
YES
The translation is verbose, repetitive, and awkward. The sentence repeats "ನೀವು ಪಾವತಿ ಕಳುಹಿಸುವಾಗ" ("when you send payment") and generally adds unnecessary complexity and redundancy. The original sentence is simple and direct.

Correct translation:
ನೀವು ಟ್ರಾನ್ಸ್‌್ಯಾಕ್ಷನ್ ಕಳುಹಿಸಿದರೆ ನೀಡಬೇಕಾದ ಶುಲ್ಕ ಇದು.
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>ಲೆಕ್ಕಾಚಾರದಲ್ಲಿ ಬದಲಾವಣೆ ವಿನಂತಿಯನ್ನು ಹೊಂದಿರುವ ಟ್ರಾನ್ಸ್ಯಾಕ್ಷನ್ ಕೆಲವು ಬದಲಾವಣೆ ವಿನಂತಿಗಳನ್ನು ಹೊಂದಿದೆ, ಆದರೆ ಅದನ್ನು ಉಂಟುಮಾಡಲು ಆಗದಿದೆ.</translation>
    
YES
The Kannada translation is inaccurate and redundant. It repeats "ಬದಲಾವಣೆ ವಿನಂತಿಯನ್ನು ಹೊಂದಿದೆ" (has change request) and does not correctly convey the meaning of "change address." The correct translation should mention "ಬದಲಾವಣೆಯ ವಿಳಾಸವನ್ನು" (change address) rather than a change request.

Correct translation:
ಟ್ರಾನ್ಸ್ಯಾಕ್ಷನ್‌ಗೆ ಬದಲಾವಣೆಯ ವಿಳಾಸ ಬೇಕಿದೆ, ಆದರೆ ಅದನ್ನು ನಾವು ಸೃಜಿಸದೆ ಸಾಧ್ಯವಾಗುತ್ತಿಲ್ಲ.
```
</details>

Number of issues: 13.
