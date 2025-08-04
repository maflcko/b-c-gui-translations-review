# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>mt</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bmt%5D%20low%20quality)


```
        <source>Copy Label</source>
        <translation>Kopja  Tikketta</translation>
    
YES, there is an extraneous space before "Tikketta".
Kopja Tikketta
```

```
        <source>Passphrase Dialog</source>
        <translation>Passphrase Djalogu</translation>
    
YES, The translation is problematic. The Maltese word for "dialog" is "djalogu", but it should be "djalogu" (singular). The translation uses the plural form.

NO
```

```
        <source>Repeat new passphrase</source>
        <translation>Irrepeti passphrase ġdida</translation>
    
YES, The translation is inaccurate. The word "Irrepeti" means "repeat" in Maltese, which is the opposite of what is intended. The correct translation should be "Ikkonferma passphrase ġdida" which means "Confirm new passphrase".
Irrepeti passphrase ġdida
```

```
        <source>Show passphrase</source>
        <translation>Uri passphrase</translation>
    
YES - The translation is incorrect. "Uri" in Maltese translates to "show" or "display". The correct translation for "Show passphrase" would be "Uri ċ-ċifratura" or "Uri l-passphrase".
Uri ċ-ċifratura
```

```
        <source>Wallet encrypted</source>
        <translation>Kartiera encrypted</translation>
    
YES, The translation is inaccurate and grammatically incorrect. The word "Kartiera" is not a valid Maltese word.
Correct translation: Kartiera mħaddma
```

```
        <source>The supplied passphrases do not match.</source>
        <translation>Il-passphrases fornuti ma jaqblux.</translation>
    
YES, The word "ma" is a conjunction meaning "but", it should be "ma'x" meaning "not".
Il-passphrases fornuti ma'x jaqblux.
```

```
        <source>Banned Until</source>
        <translation>Ipprojbit Sa</translation>
    
YES
The provided translation for "Banned Until" into Maltese is inaccurate. "Ipprojbit Sa" translates to "Prohibited Until" or "Forbidden Until," which is not the correct translation for "Banned Until."

The correct translation for "Banned Until" in Maltese is "Miskreditat Sa" or "Eskluż Sa."

Correct translation:
<source>Banned Until</source>
<translation>Miskreditat Sa</translation>
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Il-fajl tas-settings %1jista' jkun korrott jew invalidu.</translation>
    
YES, The translation is problematic because of an extra space after the format specifier %1.
Il-fajl tas-settings %1 jista' jkun korrott jew invalidu.
```

```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>Sar żball fatali. %1ma tistax tkompli b'mod sigur u se tieqaf.</translation>
    
YES, The translation is problematic because there is a missing space after the format specifier %1.
The correct translation is: Sar żball fatali. %1 ma tistax tkompli b'mod sigur u se tieqaf.
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>Sar żball intern. %1se jipprova jkompli mingħajr periklu. Dan huwa bug mhux mistenni li jista 'jiġi rrappurtat kif deskritt hawn taħt.</translation>
    
YES - The translation uses "mingħajr periklu" which is a literal translation of "safely". However, in this context, it should be "bla periklu" or "b'mod sikur" to convey the meaning of continuing in a safe manner.

Corrected Translation: Sar żball intern. %1 se jipprova jkompli bla periklu. Dan huwa bug mhux mistenni li jista' jiġi rrappurtat kif deskritt hawn taħt.
```

```
        <source>Show general overview of wallet</source>
        <translation>Uri ħarsa ġenerali ġenerali tal-kartiera</translation>
    
YES
The translation is problematic due to redundancy. The word "ġenerali" appears twice, which is unnecessary and makes the translation unnatural.

Correct translation: Uri ħarsa ġenerali tal-kartiera
```

```
        <source>About %1</source>
        <translation>Dwar%1</translation>
    
YES, The translation is missing a space between "Dwar" and "%1".
Correct translation: Dwar %1
```

```
        <source>Show information about %1</source>
        <translation>Uri informazzjoni dwar%1</translation>
    
YES, The translation incorrectly omits the space after the '%' format specifier, which is a common whitespace issue. The word 'dwar' also needs to be followed by a space before the format specifier.
Show information about %1
Uri informazzjoni dwar %1
```

```
        <source>Modify configuration options for %1</source>
        <translation>Immodifika l-għażliet tal-konfigurazzjoni għal%1</translation>
    
YES, The translation is problematic because of a missing space between %1 and the translation of the word "for".
The correct translation is: Immodifika l-għażliet tal-konfigurazzjoni għal %1
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Iffirma messaġġi bl-indirizzi Bitcoin tiegħek biex tipprova li inti stess</translation>
    
YES: The translation incorrectly uses "stess" (self) instead of a word that means "own" or "possess" in the context of proving ownership.

Correct translation: Iffirma messaġġi bl-indirizzi Bitcoin tiegħek biex tipprova li inti sidhom
```

```
        <source>%1 behind</source>
        <translation>%1wara</translation>
    
YES. The format specifier is incorrect.
%1wara
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Uri %1l-messaġġ ta 'għajnuna biex tikseb lista b'għażliet possibbli tal-linja tal-kmand Bitcoin</translation>
    
YES, The translation is problematic because it does not accurately translate the English phrase "Show the %1 help message to get a list with possible Bitcoin command-line options". The Maltese translation "Uri %1l-messaġġ ta 'għajnuna biex tikseb lista b'għażliet possibbli tal-linja tal-kmand Bitcoin" translates to "Show the %1 help message to get a list with possible Bitcoin command-line options" which has a few errors:

1. "Uri" should be "Uri" (Show)
2. "%1l-messaġġ" should be "%1l-messaġġ" (%1 help message)
3. "ta 'għajnuna" should be "ta' għajnuna" (of help)
4. "possibbli tal-linja tal-kmand Bitcoin" should be "possibbli tal-linja tal-kmand tal-Bitcoin" (possible Bitcoin command-line options)

Correct translation: Uri l-messaġġ ta' għajnuna %1 biex tikseb lista b'għażliet possibbli tal-linja tal-kmand tal-Bitcoin
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Uri tab Peers</translation>
    
YES, The translation is inaccurate and grammatically incorrect. The correct translation for "Show Peers tab" in Maltese, considering the context of Bitcoin, would be "Uri t-tab tal-Peers".

NO
```

```
        <source>Amount: %1
</source>
        <translation>Ammont:%1
</translation>
    
YES, the translation contains a spelling error. The word "Ammont" should be "Ammont".
Ammont: %1
```

```
        <source>Type: %1
</source>
        <translation>Tip:%1
</translation>
    
YES, The translation of 'Type' to 'Tip' is incorrect in the context of Bitcoin. In Bitcoin, the correct term for 'Type' in a transaction or address context is 'Tip'.
Correct translation: Tip:%1
```

```
        <source>Label: %1
</source>
        <translation>Tikketta:%1
</translation>
    
YES, the translation uses an incorrect word for "Label".
Correct translation: Tikketta: %1
```

```
        <source>Address: %1
</source>
        <translation>Indirizz:%1
</translation>
    
YES, The translation contains an erroneous word. The word 'Indirizz' should be 'Indirizz'.
The English text is "Address: %1".
The Maltese translation of "Address" is "Indirizz".
The translation provided is "Indirizz:%1".
The erroneous word is 'Indirizz'. The correct word should be 'Indirizz'.
Correct translation: Indirizz: %1
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>HD key ġenerazzjoni hija&lt;b&gt;b'diżabilità&lt;/b&gt;</translation>
    
YES, the translation is problematic. The Maltese word for "disabled" is "mitfija" or "żliġa", not "b'diżabilità". The phrase "HD key generation" is also not translated correctly; it should be "ġenerazzjoni ta' ċwievet HD".

Correct translation: HD key generation is &lt;b&gt;disabled&lt;/b&gt; -> Il-ġenerazzjoni ta' ċwievet HD hija &lt;b&gt;mitfija&lt;/b&gt;
```

```
        <source>Private key &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>Ċavetta privata&lt;b&gt;b'diżabilità&lt;/b&gt;</translation>
    
YES, the translation is erroneous. The Maltese word 'b'diżabilità' is a noun meaning 'disability', whereas the English 'disabled' is an adjective meaning 'no longer able to work or be used'. The correct translation should be 'mitlufa' or 'mejta'.

NO
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Kartiera hija&lt;b&gt;encrypted&lt;/b&gt;u bħalissa&lt;b&gt;jinfetaħ&lt;/b&gt;</translation>
    
YES, The translation is problematic because the words "encrypted" and "unlocked" are not translated into Maltese. They are left in English.

Correct translation:
Kartiera hija &lt;b&gt;imkriptata&lt;/b&gt; u bħalissa &lt;b&gt;miftuħa&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Kartiera hija&lt;b&gt;encrypted&lt;/b&gt;u bħalissa&lt;b&gt;msakkra&lt;/b&gt;</translation>
    
YES, The translation is problematic because "encrypted" and "locked" were not translated into Maltese.
Kartiera hija &lt;b&gt;imħallsa&lt;/b&gt; u bħalissa &lt;b&gt;msakkra&lt;/b&gt;
```

```
        <source>Unit to show amounts in. Click to select another unit.</source>
        <translation>Unità biex turi l-ammonti pulzieri Ikklikkja biex tagħżel unità oħra.</translation>
    
YES. The translation contains the word "pulzieri" which means "inches" in Maltese and is completely out of context for Bitcoin amounts. The rest of the translation is accurate.

NO. Unit to show amounts in. Click to select another unit.
```
</details>
