# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>nb</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bnb%5D%20low%20quality)


<!-- cache_translation_check_nb_e78f3de983078ba41ccabcec197d66cc7b7c9081274b9dcf7fa03a4652ad4d97 -->
```
        <source>Sign messages with your Bitcoin addresses to prove you own them</source>
        <translation>Signer meldingene med Bitcoin adresse for å bevise at diu eier dem</translation>
    
ERR
There are several issues:
- "Signer" should be "Signer" is not a Norwegian word; it should be "Signer" (Imperative), but the common form is "Signer" or "Signer".
- "meldingene" is plural ("the messages"). This is accurate.
- "med Bitcoin adresse" omits the possessive ("your"). It should be "Bitcoin-adressene dine".
- "diu" is a typo; should be "du".
- Native phrasing in Norwegian would use "for å bevise at du eier dem".

Correct translation:
Signer meldinger med dine Bitcoin-adresser for å bevise at du eier dem
```

<!-- cache_translation_check_nb_90e2053fef93dd407ff7485799ce5af0d7b62dd4a95a7d26e6609b7e4dba8a12 -->
```
        <source>Disable network activity</source>
        <extracomment>A context menu item.</extracomment>
        <translation>Klikk for å deaktivere nettverksaktivitet</translation>
    
ERR
The translation adds "Klikk for å" ("Click to") which is not present in the source text. The translation should be a direct translation of "Disable network activity".

Correct translation:
Deaktiver nettverksaktivitet
```

<!-- cache_translation_check_nb_b6e23f6fba625a7bd483a2d3229d8eb5467f3ed19fad0d62752b8c2239a6c555 -->
```
        <source>Creating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the create wallet progress window which indicates to the user which wallet is currently being created.</extracomment>
        <translation>Lager lommebok &lt;b&gt;%1&lt;b&gt;...</translation>
    
ERR
The translation does not properly close the HTML bold tag; it should be &lt;/b&gt;, not &lt;b&gt; (missing slash). Also, an ellipsis should ideally be an ellipsis character (…) rather than three dots (...), to match the source text.

Correct translation:
Lager lommebok &lt;b&gt;%1&lt;/b&gt;…
```

<!-- cache_translation_check_nb_c37cfeac619357d38519c464be687ffbb5db38eede8edf6d58799b7c3780287e -->
```
        <source>Disable private keys for this wallet. Wallets with private keys disabled will have no private keys and cannot have an HD seed or imported private keys. This is ideal for watch-only wallets.</source>
        <translation>Deaktiver private nøkler for denne lommeboken. Lommebøker med private nøkler er deaktivert vil ikke ha noen private nøkler og kan ikke ha en HD seed eller importerte private nøkler. Dette er ideelt for loomebøker som kun er klokker.</translation>
    
ERR  
There are a couple of issues with this translation:  
1. Typo: "loomebøker" should be "lommebøker".  
2. Awkward/incorrect expression: "lommebøker som kun er klokker" is a nonsensical phrase. The correct term for "watch-only wallets" in Norwegian is "lommebøker kun for overvåking" or "kun for visning".

Correct translation:  
Deaktiver private nøkler for denne lommeboken. Lommebøker med deaktiverte private nøkler vil ikke ha noen private nøkler og kan ikke ha en HD-seed eller importerte private nøkler. Dette er ideelt for lommebøker kun for overvåking.
```

<!-- cache_translation_check_nb_8584d77964ae5356767f1cebf493a2fbbaac7c227fb6ee5324358ce3c4d6c238 -->
```
        <source>Reverting this setting requires re-downloading the entire blockchain. It is faster to download the full chain first and prune it later. Disables some advanced features.</source>
        <translation>Gjenoppretting av denne innstillingen krever at du laster ned hele blockchain på nytt. Det er raskere å laste ned hele kjeden først og beskjære den senere Deaktiver noen avanserte funksjoner.</translation>
    
ERR
There are two issues:
1. Minor translation error: "Reverting" should be more precisely translated as "Tilbakestilling" rather than "Gjenoppretting", which means "recovery". 
2. Missing period/comma: After "senere" there should be a period, but it's missing, so the sentences run together.
3. "blockchain" should be "blokkjeden" in Norwegian, for consistency.

Correct translation:
Tilbakestilling av denne innstillingen krever at du laster ned hele blokkjeden på nytt. Det er raskere å laste ned hele kjeden først og beskjære den senere. Deaktiverer noen avanserte funksjoner.
```

<!-- cache_translation_check_nb_e2be4a52fbcae1320faa14e8e0d7da9337c254857cfd47014e3318eca0becaca -->
```
        <source>Unknown. Pre-syncing Headers (%1, %2%)…</source>
        <translation>Ukjent.Synkroniser blokkhoder (%1,%2%)...</translation>
    
ERR
There are a few issues:
1. Missing space after the period in "Ukjent.Synkroniser".
2. The word "Pre-syncing" (for "Pre-syncing Headers") is omitted; "Synkroniser" means "Synchronize", which is not the same as "Presynkroniserer" ("Pre-synchronizing") or "Forhåndssynkroniserer".
3. The translation omits "Headers" ("blokkhoder") as the direct object, but does not specify the "Pre-syncing" aspect.
4. The space after %1 and %2% is missing, but that's minor.

Correct translation:
Ukjent. Forhåndssynkroniserer blokkhoder (%1, %2%)...
```

<!-- cache_translation_check_nb_7bc9253ec9b59e81d7975f0395d4a5e0fd25344e972cfee4896b685dab03e86b -->
```
        <source>Prune block storage to</source>
        <translation>Beskjær og blokker lagring til</translation>
    
ERR
The translation "Beskjær og blokker lagring til" is incorrect. The English "Prune block storage to" refers to limiting the size of the block storage (pruning means removing old data), not "pruning and blocking storage to".

Correct translation:
Beskjær blokk-lagring til
```

<!-- cache_translation_check_nb_32c84f09c2dcda470bada10e32897ea1586c79c8f8d20a7eb6a1455f43860138 -->
```
        <source>Ctrl+=</source>
        <extracomment>Secondary shortcut to increase the RPC console font size.</extracomment>
        <translation>Cltr+=</translation>
    
ERR
The translation has a typo: "Cltr+=" should be "Ctrl+=", matching the source. "Cltr" is incorrect in Norwegian and likely a typo.

Correct translation:
Ctrl+=
```

<!-- cache_translation_check_nb_b58928d1afab77ea89376deb5f67d53ca13badd8694ae586b4c1eb41bad749cf -->
```
        <source>Create Unsigned</source>
        <translation>Cr  eate Usignert</translation>
    
ERR
There are several issues:
1. The translation is not in Norwegian Bokmål ('nb'), but rather an erroneous version of the English phrase with typos and a stray space ("Cr  eate Usignert").
2. The correct translation in Norwegian Bokmål should be "Opprett usignert".

Correct translation:
Opprett usignert
```

<!-- cache_translation_check_nb_21846f9b0e7b4ee7e9cdad08e748ead01245d9da754394dbe3bf24c9aac98226 -->
```
        <source>The amount to send in the selected unit</source>
        <translation>beløpet som skal sendes inn den valgte enheten.</translation>
    
ERR
The translation contains a minor error: "inn" should be "i" to correctly express "in the selected unit" in Norwegian. Also, the translation should begin with a capital letter and omit the period at the end to match the source capitalization and punctuation.

Correct translation:
Beløpet som skal sendes i den valgte enheten
```

<!-- cache_translation_check_nb_284930b4e1e70cda70034f4793e793ff4e41a086bdb2bfe42da6e075d52590cd -->
```
        <source>The signed message to verify</source>
        <translation>Den signerte meldingen for å bekfrefte</translation>
    
ERR
There is a typographical error in the word "bekfrefte" which should be "bekrefte". The correct Norwegian translation is:

Den signerte meldingen for å bekrefte
```

<!-- cache_translation_check_nb_1a84771f4f2ad98b28d96473efbb8e4d0cfe5ea301923cac88fa46014d9f74ba -->
```
        <source>The signature did not match the message digest.</source>
        <translation>Signaturen samsvarer ikke med meldingsporteføljen.</translation>
    
ERR
The translation is incorrect. The word "meldingsporteføljen" means "the message portfolio", which is not appropriate in this context. The English term "message digest" should be translated as "meldingsdigest" or "meldingssamendrag" in Norwegian Bokmål.

Correct translation:
Signaturen samsvarte ikke med meldingsdigesten.
or
Signaturen samsvarte ikke med meldingssamendraget.
```

<!-- cache_translation_check_nb_b13c1a3aa86f25be9678068d5254036450b33d13ad196e81196f0473c98b760e -->
```
        <source>Fee rate (%s) is lower than the minimum fee rate setting (%s)</source>
        <translation>Avgiftsrate (%s) er lavere enn den minimume avgiftsrate innstillingen (%s)</translation>
    
ERR
There is a spelling error in the translation: "minimume" should be "minimale", and "avgiftsrate innstillingen" should be written as "innstillingen for avgiftsrate" for more natural Norwegian. Also, "avgiftsrate innstillingen" is an incorrect compound.

Correct translation:
Avgiftsraten (%s) er lavere enn den minste avgiftsrate-innstillingen (%s)
```

<!-- cache_translation_check_nb_9a3d3e9aacb3f2414e913dcce9365f3fc73b5c5e9bddfd6d289be43504a5a617 -->
```
        <source>Unknown -blockfilterindex value %s.</source>
        <translation>Ukjent -blokkfilterindex-verdi 1 %s.</translation>
    
ERR
The translation introduces "1" ("1 %s") which does not exist in the source, and adds an extra hyphenation ("-blokkfilterindex-verdi 1 %s.") not matching the original style. The correct Norwegian Bokmål translation should be:

Korrekt oversettelse:
Ukjent -blockfilterindex-verdi %s.
```
</details>

Number of issues: 14.
