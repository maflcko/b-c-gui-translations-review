# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>nb</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bnb%5D%20low%20quality)


```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Signer meldingene med Bitcoin adresse for å bevise at diu eier dem</translation>
    
YES
There are several issues:
- "Signer" should be "Signer" is not a Norwegian word; it should be "Signer" (Imperative), but the common form is "Signer" or "Signer".
- "meldingene" is plural ("the messages"). This is accurate.
- "med Bitcoin adresse" omits the possessive ("your"). It should be "Bitcoin-adressene dine".
- "diu" is a typo; should be "du".
- Native phrasing in Norwegian would use "for å bevise at du eier dem".

Correct translation:
Signer meldinger med dine Bitcoin-adresser for å bevise at du eier dem
```

```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Klikk for å deaktivere nettverksaktivitet</translation>
    
YES
The translation adds "Klikk for å" ("Click to") which is not present in the source text. The translation should be a direct translation of "Disable network activity".

Correct translation:
Deaktiver nettverksaktivitet
```

```
        <source>Creating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the create wallet progress window which indicates to the user which wallet is currently being created.</extracomment>
        <translation>Lager lommebok &lt;b&gt;%1&lt;b&gt;...</translation>
    
YES
The translation does not properly close the HTML bold tag; it should be &lt;/b&gt;, not &lt;b&gt; (missing slash). Also, an ellipsis should ideally be an ellipsis character (…) rather than three dots (...), to match the source text.

Correct translation:
Lager lommebok &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Deaktiver private nøkler for denne lommeboken. Lommebøker med private nøkler er deaktivert vil ikke ha noen private nøkler og kan ikke ha en HD seed eller importerte private nøkler. Dette er ideelt for loomebøker som kun er klokker.</translation>
    
YES  
There are a couple of issues with this translation:  
1. Typo: "loomebøker" should be "lommebøker".  
2. Awkward/incorrect expression: "lommebøker som kun er klokker" is a nonsensical phrase. The correct term for "watch-only wallets" in Norwegian is "lommebøker kun for overvåking" or "kun for visning".

Correct translation:  
Deaktiver private nøkler for denne lommeboken. Lommebøker med deaktiverte private nøkler vil ikke ha noen private nøkler og kan ikke ha en HD-seed eller importerte private nøkler. Dette er ideelt for lommebøker kun for overvåking.
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain. It is faster to download the full chain first and prune it later. Disables some advanced features.</source>
        <translation>Gjenoppretting av denne innstillingen krever at du laster ned hele blockchain på nytt. Det er raskere å laste ned hele kjeden først og beskjære den senere Deaktiver noen avanserte funksjoner.</translation>
    
YES
There are two issues:
1. Minor translation error: "Reverting" should be more precisely translated as "Tilbakestilling" rather than "Gjenoppretting", which means "recovery". 
2. Missing period/comma: After "senere" there should be a period, but it's missing, so the sentences run together.
3. "blockchain" should be "blokkjeden" in Norwegian, for consistency.

Correct translation:
Tilbakestilling av denne innstillingen krever at du laster ned hele blokkjeden på nytt. Det er raskere å laste ned hele kjeden først og beskjære den senere. Deaktiverer noen avanserte funksjoner.
```

```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Ukjent.Synkroniser blokkhoder (%1,%2%)...</translation>
    
YES
There are a few issues:
1. Missing space after the period in "Ukjent.Synkroniser".
2. The word "Pre-syncing" (for "Pre-syncing Headers") is omitted; "Synkroniser" means "Synchronize", which is not the same as "Presynkroniserer" ("Pre-synchronizing") or "Forhåndssynkroniserer".
3. The translation omits "Headers" ("blokkhoder") as the direct object, but does not specify the "Pre-syncing" aspect.
4. The space after %1 and %2% is missing, but that's minor.

Correct translation:
Ukjent. Forhåndssynkroniserer blokkhoder (%1, %2%)...
```

```
        <source>Prune block storage to</source>
        <translation>Beskjær og blokker lagring til</translation>
    
YES
The translation "Beskjær og blokker lagring til" is incorrect. The English "Prune block storage to" refers to limiting the size of the block storage (pruning means removing old data), not "pruning and blocking storage to".

Correct translation:
Beskjær blokk-lagring til
```

```
        <source>Ctrl+=</source>
        <extracomment>Secondary shortcut to increase the RPC console font size.</extracomment>
        <translation>Cltr+=</translation>
    
YES
The translation has a typo: "Cltr+=" should be "Ctrl+=", matching the source. "Cltr" is incorrect in Norwegian and likely a typo.

Correct translation:
Ctrl+=
```

```
        <source>Create Unsigned</source>
        <translation>Cr  eate Usignert</translation>
    
YES
There are several issues:
1. The translation is not in Norwegian Bokmål ('nb'), but rather an erroneous version of the English phrase with typos and a stray space ("Cr  eate Usignert").
2. The correct translation in Norwegian Bokmål should be "Opprett usignert".

Correct translation:
Opprett usignert
```

```
        <source>The amount to send in the selected unit</source>
        <translation>beløpet som skal sendes inn den valgte enheten.</translation>
    
YES
The translation contains a minor error: "inn" should be "i" to correctly express "in the selected unit" in Norwegian. Also, the translation should begin with a capital letter and omit the period at the end to match the source capitalization and punctuation.

Correct translation:
Beløpet som skal sendes i den valgte enheten
```

```
        <source>The signed message to verify</source>
        <translation>Den signerte meldingen for å bekfrefte</translation>
    
YES
There is a typographical error in the word "bekfrefte" which should be "bekrefte". The correct Norwegian translation is:

Den signerte meldingen for å bekrefte
```

```
        <source>The signature did not match the message digest.</source>
        <translation>Signaturen samsvarer ikke med meldingsporteføljen.</translation>
    
YES
The translation is incorrect. The word "meldingsporteføljen" means "the message portfolio", which is not appropriate in this context. The English term "message digest" should be translated as "meldingsdigest" or "meldingssamendrag" in Norwegian Bokmål.

Correct translation:
Signaturen samsvarte ikke med meldingsdigesten.
or
Signaturen samsvarte ikke med meldingssamendraget.
```

```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>Avgiftsrate (%s) er lavere enn den minimume avgiftsrate innstillingen (%s)</translation>
    
YES
There is a spelling error in the translation: "minimume" should be "minimale", and "avgiftsrate innstillingen" should be written as "innstillingen for avgiftsrate" for more natural Norwegian. Also, "avgiftsrate innstillingen" is an incorrect compound.

Correct translation:
Avgiftsraten (%s) er lavere enn den minste avgiftsrate-innstillingen (%s)
```

```
        <source>Unknown -blockfilterindex value %s.</source>
        <translation>Ukjent -blokkfilterindex-verdi 1 %s.</translation>
    
YES
The translation introduces "1" ("1 %s") which does not exist in the source, and adds an extra hyphenation ("-blokkfilterindex-verdi 1 %s.") not matching the original style. The correct Norwegian Bokmål translation should be:

Korrekt oversettelse:
Ukjent -blockfilterindex-verdi %s.
```
</details>

Number of issues: 14.
