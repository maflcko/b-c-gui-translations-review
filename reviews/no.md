# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. To report LLM shortcomings for a specific language, please file an issue. It may be possible to re-run with a stronger model. Check the git metadata of this file for the creation date.



<details><summary>no</summary>

[If the result is outdated or of low quality, please file an issue to request and updated run for this language.](../../issues/new?title=%5Bno%5D%20request)


<!-- cache_translation_check_no_76461d55fc131915b265f954c6229c5a02b75f8cb0c7835a984a1582064984e4 -->
```
        <source>C&amp;lose</source>
        <translation>C&amp;Tap</translation>
    
ERR
Translation is incorrect. "C&Tap" is not a Norwegian rendering of "Close" ("tap" means "loss" or "to lose" in Norwegian). The ampersand shortcut exists exactly once, which is fine, but the word is wrong.

Correct translation (with accelerator):
&Lukk
```

<!-- cache_translation_check_no_12b4d392c0ff6dec60959848dbd90cae6d6c4828e6a09d37ad7a6280b9d8dbf6 -->
```
        <source>Delete the currently selected address from the list</source>
        <translation>Slett den valgte adressen fra listen </translation>
    
ERR
The Norwegian translation is correct in meaning but contains an extra trailing space before the closing tag. Remove the stray whitespace.

Correct translation:
Slett den valgte adressen fra listen
```

<!-- cache_translation_check_no_91a670e733feab6da6edd881c05c7127f544716707d7872c2a5f479265ea7ba6 -->
```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Dette er Bitcoin-adressene dine for å motta betalinger. Bruk knappen ‘Opprett ny mottaksadresse’ i mottaksfanen for å opprette nye adresser.Signering er kun mulig med adresser av typen ‘legacy’.</translation>
    
ERR
There is a whitespace formatting issue: there is no space between the two sentences "opprette nye adresser." and "Signering er kun mulig...".

Correct translation:
Dette er Bitcoin-adressene dine for å motta betalinger. Bruk knappen ‘Opprett ny mottaksadresse’ i mottaksfanen for å opprette nye adresser. Signering er kun mulig med adresser av typen ‘legacy’.
```

<!-- cache_translation_check_no_29723c697dc60fad6b7e3100626605918ff4b3edb69b12b092e8c81fbaffb3f6 -->
```
        <source>Sending addresses - %1</source>
        <translation>Sender adresser - %1</translation>
    
ERR
The Norwegian translation is awkward/incorrect. "Sender adresser" is a literal word-for-word rendering; the correct Norwegian term for "sending addresses" (i.e. addresses used for sending) is typically a single compound or different word.

Correct translation:
Avsenderadresser - %1
```

<!-- cache_translation_check_no_0388fd06d80d57ecaa9a81820f8b91aef8dd2f6f321d7b32097b458cbcca8b70 -->
```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Advarsel: Hvis du krypterer lommeboken din og mister passordet, vil du 1 MISTE ALLE BITCOINENE DINE 1 !</translation>
    
ERR
The translation is problematic. The HTML bold tags (&lt;b&gt;...&lt;/b&gt;) from the source are not retained, and "1" is incorrectly included in place of the bold tags. Additionally, "passordet" is technically "password"; "passphrase" is better translated as "passordfrase" or "passfrase". There is also an extra space before the exclamation mark.

Correct translation:
Advarsel: Hvis du krypterer lommeboken din og mister passordfrasen, vil du &lt;b&gt;MISTE ALLE BITCOINENE DINE&lt;/b&gt;!
```

<!-- cache_translation_check_no_51b22ea5c919428e5f92ec636b05c3d2da681980833b3d03617552182febea4a -->
```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Skriv inn det nye passordet for lommeboken. 1 Vennligst bruk et passord med 2 ti eller flere tilfeldige tegn 2, eller 3 åtte eller flere ord 3.</translation>
    
ERR  
The Norwegian translation contains several issues:
- It introduces numbers ("1", "2", "3") that are not present in the source; these resemble placeholder errors.
- The translation uses "passord" ("password") instead of "passphrase" ("passordfrase" or "frasepassord"), which is particularly important in Bitcoin context.
- The HTML tags (&lt;br/&gt;, &lt;b&gt;) are lost.
- There's some awkward wording; e.g., "med 2 ti" is not correct Norwegian.

Correct translation:
Skriv inn den nye passordfrasen for lommeboken.&lt;br/&gt;Vennligst bruk en passordfrase med &lt;b&gt;ti eller flere tilfeldige tegn&lt;/b&gt;, eller &lt;b&gt;åtte eller flere ord&lt;/b&gt;.
```

<!-- cache_translation_check_no_47eabd6d4f2f2f48ba5c1cd381a8515dc141a13db9b421237db82aa6db89df7e -->
```
        <source>&amp;Options…</source>
        <translation>&amp;Alternativer…</translation>
    
ERR
The translation of "&amp;Options…" into Norwegian as "&amp;Alternativer…" is not ideal. The standard and more accurate Norwegian translation for "Options" in a software context is "Innstillinger" rather than "Alternativer", which more closely translates to "Alternatives". Additionally, the format and ampersand usage are correct, with no extra whitespace or format problems.

Correct translation:
&Innstillinger…
```

<!-- cache_translation_check_no_6a80c2cf86390b719e5466cb0e815fc2da38e1bc51739389416e80a4712d5605 -->
```
        <source>&amp;Change Passphrase…</source>
        <translation>&amp;Endre Passord…</translation>
    
ERR
The translation uses "Passord" (Password) instead of "Passphrase". In Bitcoin context, "passphrase" refers to a longer, more secure string than a simple password. The Norwegian term "passordfrase" or "frasepassord" is more accurate.

Correct translation:
&Endre passordfrase…
```

<!-- cache_translation_check_no_6bd453783be518ec1cef7ec8c7567fa7a20c84b45762a866c7ff6eeaba52d865 -->
```
        <source>&amp;Sending addresses</source>
        <translation>Åpne node-feilsøkings- og diagnostikkonsoll</translation>
    
SPAM
The translation does not match the source text and refers to opening a debugging and diagnostics console, which is unrelated. The correct Norwegian translation for "&amp;Sending addresses" is:

Sendingsadresser &amp;
```

<!-- cache_translation_check_no_f5eef8aea8cef3b364912ad5a4cef2e3c1bcb7a45375b0c5da077ba6836deaae -->
```
        <source>Change:</source>
        <translation>Veksel</translation>
    
ERR
The translation "Veksel" is not accurate in the context of Bitcoin. In Norwegian, "veksel" typically means currency exchange or a bill of exchange, which does not reflect the concept of "change" as the returned amount in a transaction. The correct term is "Vekselbeløp" or "Vekslepenger", but the most commonly used and contextually correct term in Norwegian Bitcoin wallets is "Vekslepenger".

Correct translation:
Vekslepenger:
```

<!-- cache_translation_check_no_944ea8a2105774e247c258193c022d594c92353287682b228e67eb5fae70463b -->
```
        <source>&amp;Copy address</source>
        <translation>Kopier adresse</translation>
    
ERR
The translation omits the ampersand (&) which is intended to indicate a shortcut key in the menu option. The ampersand must appear exactly once in the translation, somewhere in the phrase.

Correct translation:
&Kopier adresse
```

<!-- cache_translation_check_no_a145366e2f83650015490a51da906dde7d3d3cc28ee7e2663accf23cd2c35df2 -->
```
        <source>Address</source>
        <extracomment>Title of Peers Table column which contains the IP/Onion/I2P address of the connected peer.</extracomment>
        <translation>Adresse </translation>
    
ERR
The Norwegian translation is correct ("Adresse") but contains a stray trailing space. Remove the extra whitespace.

Correct translation:
<translation>Adresse</translation>
```

<!-- cache_translation_check_no_9a0f579032e4499bc3d54ab4c5cbb168a9790bf3942551b6ccd5a356a9ed6907 -->
```
        <source>&amp;Copy address</source>
        <extracomment>Context menu action to copy the address of a peer.</extracomment>
        <translation>Kopier adresse</translation>
    
ERR
The translation omits the ampersand (&), which is required once in both the source and the translation to indicate a shortcut key.

Correct translation:
&Kopier adresse
```

<!-- cache_translation_check_no_944ea8a2105774e247c258193c022d594c92353287682b228e67eb5fae70463b -->
```
        <source>&amp;Copy address</source>
        <translation>Kopier adresse</translation>
    
ERR
The translation omits the ampersand (&) which is intended to indicate a shortcut key in the menu option. The ampersand must appear exactly once in the translation, somewhere in the phrase.

Correct translation:
&Kopier adresse
```

<!-- cache_translation_check_no_f5eef8aea8cef3b364912ad5a4cef2e3c1bcb7a45375b0c5da077ba6836deaae -->
```
        <source>Change:</source>
        <translation>Veksel</translation>
    
ERR
The translation "Veksel" is not accurate in the context of Bitcoin. In Norwegian, "veksel" typically means currency exchange or a bill of exchange, which does not reflect the concept of "change" as the returned amount in a transaction. The correct term is "Vekselbeløp" or "Vekslepenger", but the most commonly used and contextually correct term in Norwegian Bitcoin wallets is "Vekslepenger".

Correct translation:
Vekslepenger:
```

<!-- cache_translation_check_no_944ea8a2105774e247c258193c022d594c92353287682b228e67eb5fae70463b -->
```
        <source>&amp;Copy address</source>
        <translation>Kopier adresse</translation>
    
ERR
The translation omits the ampersand (&) which is intended to indicate a shortcut key in the menu option. The ampersand must appear exactly once in the translation, somewhere in the phrase.

Correct translation:
&Kopier adresse
```

<!-- cache_translation_check_no_d3d49f9afeb1d33f68850e75abe2d40b6062ee7ec07d994bf7bbed5b7bc12aed -->
```
        <source>Address</source>
        <translation>Adresse </translation>
    
ERR
The translation contains a trailing space that is not present in the source text.

Correct translation:
Adresse
```

<!-- cache_translation_check_no_d189cf5f7d8cfdeafe939efa7443dea22ea78b0c81e669c0207bf24f486bbe78 -->
```
        <source>Exporting Failed</source>
        <translation>Eksportering feilet </translation>
    
ERR
There is an unnecessary trailing space in the translation.

Correct translation:
Eksportering feilet
```
</details>

Number of issues: 18.
