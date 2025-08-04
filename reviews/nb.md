# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>nb</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bnb%5D%20low%20quality)


```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Signer meldingene med Bitcoin adresse for å bevise at diu eier dem</translation>
    
YES
The translation contains a spelling error ("diu" should be "du").
Signer meldingene med Bitcoin-adressen din for å bevise at du eier dem.
```

```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Klikk for å deaktivere nettverksaktivitet</translation>
    
YES, The provided translation is problematic. It is adding extra words that are not present in the original English text. The original text is a menu item, and the translation turns it into a clickable instruction, which is not appropriate for a menu item.

Correct translation:
Slå av nettverksaktivitet
```

```
        <source>Change:</source>
        <translation>Veksel:</translation>
    
YES, The Norwegian word "Veksel" translates to "bill of exchange" or "exchange" in English, which is not the correct term for "change" in the context of Bitcoin transactions. In Bitcoin, "change" refers to the unspent transaction output (UTXO) that is returned to the sender after a transaction. The correct Norwegian term for this is "veksel" is a financial term and not suitable here. A more appropriate term would be "rest" or "tilbakebetaling" for change in this context.

The correct translation should be:
<translation>Rest:</translation>
```

```
        <source>Creating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the create wallet progress window which indicates to the user which wallet is currently being created.</extracomment>
        <translation>Lager lommebok &lt;b&gt;%1&lt;b&gt;...</translation>
    
YES, The translation is problematic due to a syntax error in the HTML tag. The closing tag for bold should be `</b>` instead of `</b>`.
Lager lommebok &lt;b&gt;%1&lt;/b&gt;...
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Deaktiver private nøkler for denne lommeboken. Lommebøker med private nøkler er deaktivert vil ikke ha noen private nøkler og kan ikke ha en HD seed eller importerte private nøkler. Dette er ideelt for loomebøker som kun er klokker.</translation>
    
YES - The word "loomebøker" is a misspelling of "lommebøker". The word "klokker" is also a misspelling of "klokke".
Deaktiver private nøkler for denne lommeboken. Lommebøker med private nøkler deaktivert vil ikke ha noen private nøkler og kan ikke ha en HD seed eller importerte private nøkler. Dette er ideelt for lommebøker som kun er klokke.
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain. It is faster to download the full chain first and prune it later. Disables some advanced features.</source>
        <translation>Gjenoppretting av denne innstillingen krever at du laster ned hele blockchain på nytt. Det er raskere å laste ned hele kjeden først og beskjære den senere Deaktiver noen avanserte funksjoner.</translation>
    
YES - The translation has a grammatical error. The sentence "Det er raskere å laste ned hele kjeden først og beskjære den senere Deaktiver noen avanserte funksjoner." should be two separate sentences. The second sentence "Deaktiver noen avanserte funksjoner." is a command, but it's placed directly after the first sentence without proper punctuation.

Correct translation: Gjenoppretting av denne innstillingen krever at du laster ned hele blockchain på nytt. Det er raskere å laste ned hele kjeden først og beskjære den senere. Deaktiverer noen avanserte funksjoner.
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Ukjent.Synkroniser blokkhoder (%1,%2%)...</translation>
    
YES, The translation is missing a space after "Ukjent." and before "Synkroniser". It also has a missing space after the comma before "%2".
Ukjent. Synkroniser blokkhoder (%1, %2%)...
```

```
        <source>Prune block storage to</source>
        <translation>Beskjær og blokker lagring til</translation>
    
YES, The translation is incorrect. The word "Prune" means to trim or cut back, and in the context of Bitcoin, it refers to reducing the size of the blockchain. The Norwegian translation "Beskjær og blokker lagring til" translates to "Prune and block storage to", which introduces the word "and" and changes the meaning.

The correct translation should be:
Beskjær blokklagring til
```

```
        <source>Ctrl+=</source>
        <extracomment>Secondary shortcut to increase the RPC console font size.</extracomment>
        <translation>Cltr+=</translation>
    
YES, The translation contains a typographical error in the word "Ctrl". It is misspelled as "Cltr".
Ctrl+=
```

```
        <source>Change:</source>
        <translation>Veksel:</translation>
    
YES, The Norwegian word "Veksel" translates to "bill of exchange" or "exchange" in English, which is not the correct term for "change" in the context of Bitcoin transactions. In Bitcoin, "change" refers to the unspent transaction output (UTXO) that is returned to the sender after a transaction. The correct Norwegian term for this is "veksel" is a financial term and not suitable here. A more appropriate term would be "rest" or "tilbakebetaling" for change in this context.

The correct translation should be:
<translation>Rest:</translation>
```

```
        <source>Create Unsigned</source>
        <translation>Cr  eate Usignert</translation>
    
YES, there are spelling errors in the translation. The word "Create" is misspelled as "Cr eate" and "Unsigned" is misspelled as "Usignert".
Create Unsigned
```

```
        <source>The amount to send in the selected unit</source>
        <translation>beløpet som skal sendes inn den valgte enheten.</translation>
    
YES: The preposition "in" is incorrectly translated as "inn". "i" is the correct translation for "in". The trailing period is also an issue.
The amount to send in the selected unit
beløpet som skal sendes i den valgte enheten.
```

```
        <source>The signed message to verify</source>
        <translation>Den signerte meldingen for å bekfrefte</translation>
    
YES, the translation contains a misspelling. The word "bekfrefte" should be "bekrefte".
The signed message to verify
Den signerte meldingen for å bekrefte
```

```
        <source>The signature did not match the message digest.</source>
        <translation>Signaturen samsvarer ikke med meldingsporteføljen.</translation>
    
YES, the translation has an erroneous word choice. "Meldingsporteføljen" translates to "message portfolio" which is not the intended meaning. The correct translation for "message digest" in this context is "meldingssammendrag".

NO
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>Avgiftsrate (%s) er lavere enn den minimume avgiftsrate innstillingen (%s)</translation>
    
YES - The translation uses "avgiftsrate" instead of the more appropriate "gebyrsats" when referring to Bitcoin transaction fees. Additionally, it uses "innstillingen" which is not the correct grammatical form in this context. The correct translation should use "gebyrsats" and "innstillingen" should be "innstilling".
NO - Fee rate (%s) is lower than the minimum fee rate setting (%s)
```

```
        <source>Unknown -blockfilterindex value %s.</source>
        <translation>Ukjent -blokkfilterindex-verdi 1 %s.</translation>
    
YES - The translation incorrectly includes the number "1" before the format specifier "%s". This is not present in the source text.

Correct translation: Ukjent -blockfilterindex-verdi %s.
```
</details>
