# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>mt</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bmt%5D%20low%20quality)


```
        <source>Copy Label</source>
        <translation>Kopja  Tikketta</translation>
    
YES
There is an unnecessary extra space between "Kopja" and "Tikketta". The translation should not have a double space. Also, "Kopja" is not the verb form; the correct imperative form is "Kopja" (copy, as a verb) is actually "Ikkopja".

Correct translation:
Ikkopja t-Tikketta
```

```
        <source>Passphrase Dialog</source>
        <translation>Passphrase Djalogu</translation>
    
YES
The translation "Passphrase Djalogu" is problematic as it mixes English ('Passphrase') with a phonetic transliteration of 'Dialog' rather than using a fully Maltese translation or a consistent borrowing.

A more appropriate translation in Maltese would be:
"Djalogu tal-Passphrase"

Correct translation:
Djalogu tal-Passphrase
```

```
        <source>Wallet encrypted</source>
        <translation>Kartiera encrypted</translation>
    
YES
The translation is partially incorrect. The word "encrypted" was not translated into Maltese; the English word was reused. The correct translation would use "enkripptata" or "ikkodifikata" for "encrypted". "Wallet" is often translated as "kartiera". The corrected translation is:

Kartiera enkripptata

So, the correct translation:

<translation>Kartiera enkripptata</translation>
```

```
        <source>Settings file %1 might be corrupt or invalid.</source>
        <translation>Il-fajl tas-settings %1jista' jkun korrott jew invalidu.</translation>
    
YES
There is a missing space between "%1" and "jista'". It should read "%1 jista'". The rest of the translation is correct.

Correct translation:
Il-fajl tas-settings %1 jista' jkun korrott jew invalidu.
```

```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>Sar żball fatali. %1ma tistax tkompli b'mod sigur u se tieqaf.</translation>
    
YES
There is a spacing error: "%1ma" should be "%1 ma" (missing space after %1).

Correct translation:
Sar żball fatali. %1 ma tistax tkompli b'mod sigur u se tieqaf.
```

```
        <source>An internal error occurred. %1 will attempt to continue safely. This is an unexpected bug which can be reported as described below.</source>
        <translation>Sar żball intern. %1se jipprova jkompli mingħajr periklu. Dan huwa bug mhux mistenni li jista 'jiġi rrappurtat kif deskritt hawn taħt.</translation>
    
YES
There are minor spacing issues and a typo:
- "Sar żball intern." should be "Seħħ żball intern."
- There should be a space after "%1" (" %1 se jipprova...").

Correct translation:
Seħħ żball intern. %1 se jipprova jkompli mingħajr periklu. Dan huwa bug mhux mistenni li jista' jiġi rrappurtat kif deskritt hawn taħt.
```

```
        <source>Show general overview of wallet</source>
        <translation>Uri ħarsa ġenerali ġenerali tal-kartiera</translation>
    
YES
The translation repeats the word "ġenerali" (general) twice, which is redundant. Also, "Uri" means "Show", which is correct, but a better way would be "Uri ħarsa ġenerali tal-kartiera" ("Show a general overview of the wallet") without repetition.

Correct translation:
Uri ħarsa ġenerali tal-kartiera
```

```
        <source>About %1</source>
        <translation>Dwar%1</translation>
    
YES
There is a whitespace formatting issue. In Maltese, "Dwar" ("About") should have a space before the placeholder "%1".

Correct translation:
Dwar %1
```

```
        <source>Show information about %1</source>
        <translation>Uri informazzjoni dwar%1</translation>
    
YES
There is a missing space between "dwar" and "%1". The correct translation should be:

Uri informazzjoni dwar %1
```

```
        <source>Modify configuration options for %1</source>
        <translation>Immodifika l-għażliet tal-konfigurazzjoni għal%1</translation>
    
YES
There is a spacing issue: there should be a space between "għal" and "%1". Also, "Immodifika" is fine, but it might be more natural to say "Immodifika l-għażliet tal-konfigurazzjoni għal %1".

Correct translation:
Immodifika l-għażliet tal-konfigurazzjoni għal %1
```

```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Iffirma messaġġi bl-indirizzi Bitcoin tiegħek biex tipprova li inti stess</translation>
    
YES
The translation is incomplete. The English phrase "to prove you own them" is not fully translated; "li inti stess" means "that you yourself" or "that you are" but doesn't finish the thought ("own them"). The object ("them"/"the addresses") is missing in the Maltese translation.

Correct translation:
Iffirma messaġġi bl-indirizzi Bitcoin tiegħek biex tipprova li inti s-sid tagħhom
```

```
        <source>%1 behind</source>
        <translation>%1wara</translation>
    
YES
There is a missing space between "%1" and "wara". It should be "%1 wara".

Correct translation:
%1 wara
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Uri %1l-messaġġ ta 'għajnuna biex tikseb lista b'għażliet possibbli tal-linja tal-kmand Bitcoin</translation>
    
YES
There is a spacing issue: "%1" and "l-messaġġ" are merged ("%1l-messaġġ"), which is incorrect. "%1" should be separated. Also, "Uri %1l-messaġġ ta 'għajnuna" translates as "Show %1the help message", which is ungrammatical.

Correct translation:
Uri l-messaġġ ta’ għajnuna ta’ %1 biex tikseb lista b’għażliet possibbli tal-linja tal-kmand Bitcoin
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Uri tab Peers</translation>
    
YES
The translation "Uri tab Peers" is incorrect. The verb "Uri" means "show" in Maltese, but it should reflect natural Maltese syntax and terminology. Also, "Peers tab" should be properly localized or at least capitalized if being borrowed directly.

Correct translation:
Uri t-tab Peers

Or, more fully localized:
Uri t-tab tal-Pari

Either option is more accurate, but the first is closer to common usage in software contexts in Maltese.
```

```
        <source>Amount: %1
</source>
        <translation>Ammont:%1
</translation>
    
YES
There is a missing space after the colon in the Maltese translation, which creates a whitespace formatting issue. The correct translation should be:

Ammont: %1

Corrected translation:
Ammont: %1
```

```
        <source>Type: %1
</source>
        <translation>Tip:%1
</translation>
    
YES
There is a missing space after the colon in the Maltese translation. It should be "Tip: %1" (with a space).

Correct translation:
Tip: %1
```

```
        <source>Label: %1
</source>
        <translation>Tikketta:%1
</translation>
    
YES
There is a missing space after the colon in the Maltese translation. The correct translation should be:

Tikketta: %1

Corrected translation:
Tikketta: %1
```

```
        <source>Address: %1
</source>
        <translation>Indirizz:%1
</translation>
    
YES
There is a whitespace format issue: there should be a space after the colon to match the source formatting.

Correct translation:
Indirizz: %1
```

```
        <source>HD key generation is &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>HD key ġenerazzjoni hija&lt;b&gt;b'diżabilità&lt;/b&gt;</translation>
    
YES
The Maltese translation is incorrect and does not accurately reflect the English source. The phrase "HD key ġenerazzjoni hija b'diżabilità" is not idiomatic; "b'diżabilità" means "with a disability", which is not the intended meaning. The phrase should use the Maltese equivalent of "disabled", which is "diżattivata".

Correct translation:
Ġenerazzjoni ta' ċwievet HD hija &lt;b&gt;diżattivata&lt;/b&gt;
```

```
        <source>Private key &lt;b&gt;disabled&lt;/b&gt;</source>
        <translation>Ċavetta privata&lt;b&gt;b'diżabilità&lt;/b&gt;</translation>
    
YES
The translation is problematic. The phrase should be "Private key <b>disabled</b>", but the translated "Ċavetta privata<b>b'diżabilità</b>" is incorrect. "b'diżabilità" translates to "with a disability" rather than "disabled". The code formatting &lt;b&gt; should also have a space after the key and before the tag.

Correct translation:
Ċavetta privata &lt;b&gt;diżattivata&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;unlocked&lt;/b&gt;</source>
        <translation>Kartiera hija&lt;b&gt;encrypted&lt;/b&gt;u bħalissa&lt;b&gt;jinfetaħ&lt;/b&gt;</translation>
    
YES
There are spacing issues before and after the HTML tags. Additionally, words "encrypted" and "currently" are untranslated. "Jinfetaħ" is singular ("it opens") and should be "miftuħa" ("unlocked"). The definite article "Il-" before "kartiera" is also missing.

Correct translation:
Il-kartiera hija &lt;b&gt;kkodifikata&lt;/b&gt; u bħalissa &lt;b&gt;miftuħa&lt;/b&gt;
```

```
        <source>Wallet is &lt;b&gt;encrypted&lt;/b&gt; and currently &lt;b&gt;locked&lt;/b&gt;</source>
        <translation>Kartiera hija&lt;b&gt;encrypted&lt;/b&gt;u bħalissa&lt;b&gt;msakkra&lt;/b&gt;</translation>
    
YES
There are spacing issues in the Maltese translation. There should be spaces between the Maltese and the HTML tags. Also, the word "encrypted" is untranslated while "msakkra" is translated as "locked", which is correct. "Kartiera hija" means "The wallet is", which is appropriate.

Correct translation:
Kartiera hija &lt;b&gt;ikkrittata&lt;/b&gt; u bħalissa &lt;b&gt;msakkra&lt;/b&gt;
```

```
        <source>Unit to show amounts in. Click to select another unit.</source>
        <translation>Unità biex turi l-ammonti pulzieri Ikklikkja biex tagħżel unità oħra.</translation>
    
YES
There is a translation error: "pulzieri" means "inches" in Maltese, which is not relevant here. There should also be a period (full stop) separating the two sentences, as in the source.

Correct translation:
Unità biex turi l-ammonti. Ikklikkja biex tagħżel unità oħra.
```
</details>
