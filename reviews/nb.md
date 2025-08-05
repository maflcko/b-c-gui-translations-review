# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>nb</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bnb%5D%20low%20quality)


```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Signer meldingene med Bitcoin adresse for å bevise at diu eier dem</translation>
    
YES  
The Norwegian Bokmål translation contains errors: "Bitcoin adresse" should be plural ("Bitcoin-adresser") to match "messages" and "diu" is incorrect (it should be "du"). Also, "dem" is incorrect and should be "dem" changed to "dem" (although "dem" is the object form of "de" in Norwegian, here "dem" refers to "meldingene" or "adressene", so "dem" is acceptable but "dem" is an old-fashioned or dialectal form—more standard would be "dem"). However, more consistent would be to use "dem" or "dem" depending on style, but in this context, "dem" is acceptable. The phrase should also have a hyphen in "Bitcoin-adresser".

Correct translation:  
Signer meldingene med dine Bitcoin-adresser for å bevise at du eier dem
```

```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Klikk for å deaktivere nettverksaktivitet</translation>
    
YES  
The source text is a simple imperative phrase "Disable network activity," likely a menu item or toggle command. The translation "Klikk for å deaktivere nettverksaktivitet" means "Click to disable network activity," which adds the word "Klikk for" ("Click to"), not present in the source. This addition changes the meaning and is unnecessary. The correct translation should be a direct imperative:

Correct translation:  
Deaktiver nettverksaktivitet
```

```
        <source>Creating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the create wallet progress window which indicates to the user which wallet is currently being created.</extracomment>
        <translation>Lager lommebok &lt;b&gt;%1&lt;b&gt;...</translation>
    
YES
The translation contains an error in the use of the word "Lager," which means "store" or "warehouse," rather than "creating." The correct Norwegian Bokmål verb would be "Oppretter" to mean "Creating." Additionally, the closing HTML tag is incorrect: it uses &lt;b&gt; instead of &lt;/b&gt; to close the bold tag. The ellipsis should be the single character "…" as in the source, not three dots.

Correct translation:
Oppretter lommebok &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Deaktiver private nøkler for denne lommeboken. Lommebøker med private nøkler er deaktivert vil ikke ha noen private nøkler og kan ikke ha en HD seed eller importerte private nøkler. Dette er ideelt for loomebøker som kun er klokker.</translation>
    
YES  
There are several issues in the translation:

1. "Deaktiver private nøkler" should be "Deaktiver private nøkler" but the verb form is incorrect; it should be an imperative or infinitive form consistent with the English "Disable". Normally, "Deaktiver" is the imperative form meaning "Disable," so that is okay.

2. The phrase "Lommebøker med private nøkler er deaktivert" is incorrect grammar; it should be "Lommebøker med deaktiverte private nøkler" or "Lommebøker med private nøkler deaktivert" to convey "Wallets with private keys disabled." The current phrase literally means "Wallets with private keys are disabled," which is wrong.

3. "kan ikke ha en HD seed" – the phrase "seed" should be preceded by the Norwegian equivalent or stay as "seed" but preceded by "en" which is singular indefinite. "HD seed" is accepted terminology but might be italicized or left as is.

4. "loomebøker som kun er klokker" contains a typo - "loomebøker" should be "lommebøker" and "klokker" literally means "clocks," which is incorrect. The intended phrase is "watch-only wallets," which can be translated as "lommebøker som kun kan følges (eller overvåkes)" or "se kun lommebøker." The common accepted translation is "lommebøker som kun kan overvåkes" or "lommebøker kun for overvåkning." Alternatively, "lese-lommebøker" (read-only wallets) might be used. The current translation is inaccurate.

Corrected translation:

Deaktiver private nøkler for denne lommeboken. Lommebøker med deaktiverte private nøkler vil ikke ha noen private nøkler og kan ikke ha en HD-seed eller importerte private nøkler. Dette er ideelt for lommebøker som kun kan overvåkes.

Note: Added a hyphen in "HD-seed" for clarity but "HD seed" may also be acceptable.

Alternatively:

Deaktiver private nøkler for denne lommeboken. Lommebøker med deaktiverte private nøkler vil ikke ha private nøkler og kan verken ha en HD-seed eller importerte private nøkler. Dette er ideelt for overvåkingslommebøker.

Either is acceptable.
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain. It is faster to download the full chain first and prune it later. Disables some advanced features.</source>
        <translation>Gjenoppretting av denne innstillingen krever at du laster ned hele blockchain på nytt. Det er raskere å laste ned hele kjeden først og beskjære den senere Deaktiver noen avanserte funksjoner.</translation>
    
YES  
The translation misses a period (full stop) between the sentences "senere" and "Deaktiver". Also, "blockchain" is left in English, which can be understandable but inconsistent as "blokkjeden" is commonly used in Norwegian Bokmål. The term "beskjære" (to crop) is not the best choice in this context; a better term would be "beskjære" replaced with "beskjære" or "rydde opp i" isn't typical here. A better term is "beskjære" replaced with "beskjære" might be fine but "rydde opp i" is more informal and "kutte" or "beskjære" is commonly used regarding pruning. However, the established Norwegian Bitcoin community term for "prune" in this technical context is "beskjære". 

Corrected translation with punctuation fixed and "blockchain" translated:  
Gjenoppretting av denne innstillingen krever at du laster ned hele blokkjeden på nytt. Det er raskere å laste ned hele kjeden først og beskjære den senere. Deaktiverer noen avanserte funksjoner.
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Ukjent.Synkroniser blokkhoder (%1,%2%)...</translation>
    
YES
There are spacing issues in the translation. There should be a space after "Ukjent." and also after the commas within the parentheses. The ellipsis is typically represented as "…" (single character) and should have a non-breaking space before it or at least a space before to match the source style.

Correct translation:
Ukjent. Pre-synkroniserer blokkhoder (%1, %2%)…
```

```
        <source>Prune block storage to</source>
        <translation>Beskjær og blokker lagring til</translation>
    
YES  
The Norwegian Bokmål translation is incorrect and somewhat confusing. "Beskjær og blokker lagring til" translates back as "Prune and block storage to," which adds an unintended conjunction "og" ("and") and changes the meaning. The English phrase "Prune block storage to" means to reduce or trim the block storage size to a certain amount, not to block it.

Correct translation:  
"Beskjær blokk-lagring til"  
or simply  
"Beskjær blokk-lagringen til"
```

```
        <source>Ctrl+=</source>
        <extracomment>Secondary shortcut to increase the RPC console font size.</extracomment>
        <translation>Cltr+=</translation>
    
YES
The translation contains a typo: "Cltr" should be "Ctrl" to correctly reflect the English shortcut key abbreviation.

Correct translation:
Ctrl+=
```

```
        <source>Create Unsigned</source>
        <translation>Cr  eate Usignert</translation>
    
YES  
The translation is incorrect and contains typographical errors and does not reflect the Norwegian Bokmål language. It appears to be a corrupted or mistyped version of the English source text rather than a proper translation.  

Correct translation:  
Opprett usignert
```

```
        <source>The amount to send in the selected unit</source>
        <translation>beløpet som skal sendes inn den valgte enheten.</translation>
    
YES  
The translation is slightly inaccurate and contains unnecessary whitespace before the last period. The phrase "inn den valgte enheten" suggests "into the selected unit," which is not correct. It should be "i den valgte enheten" meaning "in the selected unit." Also, the initial word should be capitalized as in the source.

Correct translation:  
Beløpet som skal sendes i den valgte enheten.
```

```
        <source>The signed message to verify</source>
        <translation>Den signerte meldingen for å bekfrefte</translation>
    
YES  
There is a typo in the Norwegian Bokmål translation: "bekfrefte" should be "bekrefte".  

Correct translation:  
Den signerte meldingen for å bekrefte
```

```
        <source>The signature did not match the message digest.</source>
        <translation>Signaturen samsvarer ikke med meldingsporteføljen.</translation>
    
YES  
The word "meldingsporteføljen" is incorrect for "message digest." The correct Norwegian Bokmål term for "message digest" in a cryptographic context is "meldingsdigest" or "meldingsoppsummering." Additionally, "Signaturen samsvarer ikke med meldingsdigesten." is more accurate and grammatically correct.

Correct translation:  
Signaturen samsvarer ikke med meldingsdigesten.
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>Avgiftsrate (%s) er lavere enn den minimume avgiftsrate innstillingen (%s)</translation>
    
YES  
The Norwegian Bokmål translation has a few issues:  
1. "Avgiftsrate" is understandable but the correct Norwegian term in the context of Bitcoin transaction fees is "Gebyrrate" or simply "Gebyrsats".  
2. "minimume" is a typo and should be "minimum".  
3. There should be a preposition "for" before "innstillingen" for clarity: "den minimum gebyrrateinnstillingen" or better "den minimale gebyrrateinnstillingen".  
4. The phrase is slightly awkward and could be more natural.

A more natural and correct translation would be:  
"Gebyrsatsen (%s) er lavere enn den minimale gebyrsats-innstillingen (%s)"  

Alternatively:  
"Gebyrsatsen (%s) er lavere enn den minimale gebyrsatsinnstillingen (%s)"  

Complete corrected translation:  
<translation>Gebyrsatsen (%s) er lavere enn den minimale gebyrsatsinnstillingen (%s)</translation>
```

```
        <source>Unknown -blockfilterindex value %s.</source>
        <translation>Ukjent -blokkfilterindex-verdi 1 %s.</translation>
    
YES  
There is an extra "1" before the placeholder "%s" that is not present in the source text, making the translation inaccurate.

Correct translation:  
Ukjent -blokkfilterindex-verdi %s.
```
</details>
