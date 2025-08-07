# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>eo</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Beo%5D%20low%20quality)


```
        <source>Close</source>
        <translation>Caleb Payne Phd</translation>
    
SPAM
The provided translation is not in Esperanto ('eo'). It is an unrelated personal name, which constitutes spam.

Correct translation:
Fermi
```

```
        <source>Choose the address to receive coins with</source>
        <translation>Elekti la adreson ricevi monerojn kun</translation>
    
YES
The Esperanto translation is understandable but ungrammatical. The infinitive "elekti" is used instead of the imperative or direct instruction "Choose". The prepositional phrase is also not natural. 

Correct translation:
Elektu la adreson, per kiu ricevi monerojn
```

```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Jen viaj bitmonaj adresoj por ricevi pagojn. Estas konsilinde uzi apartan ricevan adreson por ĉiu transakcio.</translation>
    
YES
The translation is incomplete and omits the information about the 'Create new receiving address' button and about signing being only possible with 'legacy' addresses. The original text also mentions specifics about how to create new addresses, which is not mentioned in the translation.

Correct translation:
Jen viaj Bitcoin-adresoj por ricevi pagojn. Uzu la butonon ‘Krei novan ricevan adreson’ en la riceva langeto por krei novajn adresojn.
Subskribi eblas nur kun adresoj de la tipo ‘legacy’.
```

```
        <source>Change passphrase</source>
        <translation>Ŝanĝi la pasfrazon</translation>
    
YES
The translation is problematic. The text "Ŝanĝi la pasfrazon" is not correct in Esperanto. The correct translation for "Change passphrase" should be:

Ŝanĝi la pasfrazon

The incorrect use of 'Ŝ' (with a circumflex above the capital S, but incorrectly encoded as 'Ŝ' instead of the standard Esperanto 'Ŝ'), and the word 'Ŝanĝi' does not represent the correct Esperanto term. The translation has a character encoding/orthographic error and possibly a spelling mistake.
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Atentu! Se vi ĉifras vian monujon kaj perdas la pasfrazon, vi &lt;b&gt;PERDOS LA TUTON DE VIA BITMONO&lt;b&gt;!</translation>
    
YES
There are two issues: (1) The closing </b> tag is missing in the Esperanto translation, so bold formatting would not be correctly applied. (2) The Esperanto character "ĉ" is incorrectly written as "ĉ" (with^^), which is a workaround but should use "ĉ" if Unicode is available.

Correct translation:
Atentu! Se vi ĉifras vian monujon kaj perdas la pasfrazon, vi &lt;b&gt;PERDOS LA TUTON DE VIA BITMONO&lt;/b&gt;!
```

```
        <source>Wallet encryption failed</source>
        <translation>Ĉifrado de la monujo fiaskis</translation>
    
YES
The translation contains a non-standard character: "Ĉ" (C with circumflex) instead of the correct Esperanto "Ĉ" (uppercase C with circumflex). Otherwise, the translation is correct.

Correct translation:
Ĉifrado de la monujo fiaskis
```

```
        <source>Warning: The Caps Lock key is on!</source>
        <translation>Atentu: la majuskla baskulo estas ŝaltita!</translation>
    
YES
The translation uses "majuskla baskulo" for "Caps Lock key," which is nonstandard and may confuse Esperanto speakers. The commonly used term is "Majuskla Ŝlosilo" or "Majuskliga ŝlosilo." 

Also, "ŝaltita" should use the proper Esperanto character: "ŝaltita."

Correct translation:
Atentu: la majuskliga ŝlosilo estas ŝaltita!
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Ŝanĝi la pasfrazon por ĉifri la monujon</translation>
    
YES
There are multiple issues:
- The translation uses incorrect Esperanto diacritics: "Ŝanĝi" and "ĉifri" should be "Ŝanĝi" and "ĉifri".
- "Ŝanĝi la pasfrazon" ("to change the passphrase") is good, but "por ĉifri la monujon" may misleadingly suggest that a passphrase is being set (to encrypt), not changed. The English text explicitly refers to changing the passphrase of an already-encrypted wallet.

A better translation would be:
Ŝanĝi la pasfrazon uzatan por ĉifrado de la monujo

or more simply:
Ŝanĝi la pasfrazon uzatan por ĉifri la monujon
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>Ĉifri la privatajn ŝlosilojn de via monujo</translation>
    
YES
The translation contains erroneous characters: "Ĉifri" and "ŝlosilojn" use a caret (^) instead of the correct Esperanto circumflex (ĝ, ĉ, ŝ, etc.). The proper spelling should use "Ĉ" and "ŝ": "Ĉifri" and "ŝlosilojn".

Correct translation:
Ĉifri la privatajn ŝlosilojn de via monujo
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Kontroli mesaĝojn por kontroli ĉu ili estas subskribitaj per specifaj Bitmon-adresoj</translation>
    
YES
The translation is mostly accurate, but the repetition of "kontroli" (to check/verify) is redundant, and "mesaĝojn" should be "mesaĝojn" (the proper Esperanto spelling). Additionally, "Bitmon-adresoj" is a neologism; although "Bitmono" is sometimes used for Bitcoin in Esperanto, "Bitkoino" is more common. 

Correct translation:
Kontrolu mesaĝojn por certigi, ke ili estis subskribitaj per specifaj Bitkoin-adresoj
```

```
        <source>%1 behind</source>
        <translation>mankas %1</translation>
    
YES
The translation "mankas %1" is not an accurate representation of "%1 behind" in the Bitcoin context, where it typically means how many blocks the client is behind the blockchain tip (e.g., "5 behind" = 5 blocks to catch up). "mankas" means "missing," but that does not clearly convey the meaning of being "behind" by a certain number.

Correct translation:
%1 malantaŭ
```

```
        <source>Transactions after this will not yet be visible.</source>
        <translation>Transakcioj por tio ankoraŭ ne videblas.</translation>
    
YES
The translation deviates from the source in meaning. The English "Transactions after this will not yet be visible." suggests "transactions following this point/event/time," but the translation "Transakcioj por tio ankoraŭ ne videblas." literally means "Transactions for this are not yet visible," which misinterprets "after this."

Correct translation:
Transakcioj post tio ankoraŭ ne estos videblaj.
or
Transakcioj post tio ankoraŭ ne videblas.
```

```
        <source>Coin Selection</source>
        <translation>Monero-Elektaĵo</translation>
    
YES
The translation "Monero-Elektaĵo" is problematic because "Monero" in Esperanto means "coin" but is also the name of another cryptocurrency, which can cause confusion in the context of Bitcoin. The word "Elektaĵo" is also an unnecessarily complex or literary form; "elekto" or "elektado" is more natural.

Correct translation:
Monero-elekto
```

```
        <source>(change)</source>
        <translation>(restmono)</translation>
    
YES
The translation "(restmono)" is incorrect and uncommon for "change" in the context of Bitcoin transactions in Esperanto. The usual and understandable translation is "(ŝanĝmono)".

Correct translation:
(ŝanĝmono)
```

```
        <source>Open wallet warning</source>
        <translation>Malfermi monujon averto</translation>
    
YES
The translation "Malfermi monujon averto" is not grammatically correct in Esperanto. It reads as three separate words ("Open wallet warning") without proper phrasing. In Esperanto, a better translation would be:

Correct translation:
Averto pri malfermo de monujo

Alternatively:
Averto dum malfermo de monujo

Either of these is more natural and clear in Esperanto.
```

```
        <source>Open bitcoin URI</source>
        <translation>Malfermi na la URI de bitmono</translation>
    
YES
The translation has issues: "na la" is incorrect Esperanto; "na" is not typically used this way in Esperanto (it's a preposition used in some pidgin dialects, not Esperanto), and the article usage is off. The correct translation should be more idiomatic Esperanto and preserve the sense of opening a Bitcoin URI.

Correct translation:
Malfermu la Bitcoin-URI-n
```

```
        <source>Automatically start %1 after logging in to the system.</source>
        <translation>Aŭtomate komenci na %1 post ensalutis en la sistemon.</translation>
    
YES
The translation is slightly problematic. The use of "na" is incorrect in Esperanto, and the past tense "ensalutis" should be infinitive or present participle. The phrase should read "post ensaluto en la sistemon" (after login to the system) or "post ensaluti en la sistemon" (after logging in to the system).

Correct translation:
Aŭtomate komenci %1 post ensaluto en la sistemon.
```

```
        <source>Number of script verification threads</source>
        <translation>Kvanto da skriptaj kaj kontroleraraj fadenoj</translation>
    
YES
The translation adds "kaj kontroleraraj" ("and verification"), but "kontroleraraj" is not a proper Esperanto term and the original English only refers to "script verification" (not "script and verification" or similar). The translation unnecessarily expands the meaning and contains a word ("kontroleraraj") that is not standard Esperanto.

Correct translation:
Kvanto de fadenoj por kontrolado de skriptoj
```

```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Elekti la defaŭltan manieron por montri bitmonajn sumojn en la interfaco, kaj kiam vi sendos bitmonon.</translation>
    
YES
The translation has some issues:
- "defaŭltan" should be "defaŭltan", missing the proper Esperanto character.
- "manieron" (way, manner) is not an accurate translation for "subdivision unit" (should be something like "subunuon" or "subdividaĵon").
- "bitmonajn sumojn" (Bitcoin sums/amounts) is not exactly "subdivision unit", which refers specifically to the smaller units (e.g. BTC, mBTC, satoshi) shown in the interface and when sending.
- "bitmonon" (Bitcoin, singular) at the end is not coherent with "monerojn" or "bitmonojn" and is not explicit about units.
- The translation introduces "vi" ("you will send") which is not as close to the English as possible.

Correct translation:
Elektu la defaŭltan subdividan unuo por montri en la interfaco kaj kiam oni sendas monerojn.
```

```
        <source>Whether to show coin control features or not.</source>
        <translation>Ĉu montri detalan adres-regilon, aŭ ne.</translation>
    
YES
The translation introduces "detalan adres-regilon" ("detailed address controller"), which is not an accurate translation of "coin control features". The original refers specifically to controls for selecting which coins/UTXOs to spend in a transaction, not address management.

Correct translation:
Ĉu montri monero-regilajn funkciojn aŭ ne.
```

```
        <source>default</source>
        <translation>defaŭlta</translation>
    
YES
The translation "defaŭlta" contains an erroneous character: "ŭ" (u with breve) is not part of the Esperanto alphabet and appears to be a mistaken attempt at representing the English word "default". In practice, Esperanto often uses direct borrowings for technical terms, especially those like "default", but the correct spelling would be "defaŭlto", using "ŭ" (u with breve) as per the Esperanto alphabet.

Correct translation:
defaŭlto
```

```
        <source>Enter the message you want to sign here</source>
        <translation>Tajpu la mesaĝon, kiun vi volas sendi, cîi tie</translation>
    
YES  
The translation is problematic. The English text is "Enter the message you want to sign here", but the translation says "Type the message you want to send here" in Esperanto ("Tajpu la mesaĝon, kiun vi volas sendi, ĉi tie"). This changes the meaning from "sign" (cryptographically sign a message) to "send".

Correct translation:  
Enigu la mesaĝon, kiun vi volas subskribi, ĉi tie
```

```
        <source>Transaction status. Hover over this field to show number of confirmations.</source>
        <translation>Transakcia stato. Ŝvebi super tiu ĉi kampo por montri la nombron de konfirmoj.</translation>
    
YES
The translation uses some incorrect Esperanto: "Transakcia stato" should be used rather than "Transakcia stato" (the accusative is misapplied as "Transakcia stato" instead of "Transakcio stato"). Also, "Ŝvebi" and "ĉi" are using the circumflex in a non-standard encoding (should be "ŝ" and "ĉ"), and should be corrected for proper Esperanto Unicode letters.

Correct translation:
Transakcia stato. Movu la muson super ĉi tiun kampon por montri la nombron de konfirmoj.
```

```
        <source>This month</source>
        <translation>Ĉi-monate</translation>
    
YES
The translation contains an error: the Esperanto circumflex 'Ĉ' is incorrectly written as 'Ĉ', using 'C' with a combining circumflex instead of the correct precomposed character. Also, in proper Esperanto, "this month" is best translated as "Ĉi tiu monato" or the shorter "Ĉimonate" (as an adverbial form, though rare), but "Ĉi-monate" is not standard.

Correct translation:
Ĉi tiu monato
```

```
        <source>Error initializing block database</source>
        <translation>Eraro dum pravalorizado de blokdatumbazo</translation>
    
YES
The translation is problematic due to the incorrect use of "pravalorizado" which is not a proper Esperanto word. The Esperanto word for "initializing" should be "pravalorizado" or "inicialigado," but actually, "inicialigi" is the correct term for "to initialize," and "blokdatumbazo" is correct for "block database." Also, "Eraro dum" is acceptable for "Error during," but the word "pravalorizado" is simply not Esperanto.

Correct translation:
Eraro dum inicialigado de blokdatumbazo
```

```
        <source>Error initializing wallet database environment %s!</source>
        <translation>Eraro dum pravalorizado de monuj-datumbaza ĉirkaŭaĵo %s!</translation>
    
YES
There are a few issues:
1. The translation uses "pravalorizado" which is not a correct or standard word in Esperanto; the standard word for "initializing" is "pravalorizi" or better "pravalorigo" or simply "pravigo" or "ekfunkciigo" depending on context, but "pravalorizi" is rare and nonstandard.
2. "monuj-datumbaza ĉirkaŭaĵo" has unnecessary hyphenation and uses circumflexes in ASCII form (should be ĉirkaŭaĵo).
3. The ASCII circumflexes ('^', 'ŭ') are not standard and should be actual Esperanto letters.

Correct translation:
Eraro dum pravalorigo de monujdatumbaza ĉirkaŭaĵo %s!
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>Geneza bloko aŭ netrovita aŭ neĝusta. Ĉu eble la datadir de la reto malĝustas?</translation>
    
YES
There are minor issues with diacritics: Esperanto circumflexed letters have been replaced by characters with circumflexes after the letter (e.g., 'bloko aŭ' instead of 'bloko aŭ', 'neĝusta' instead of 'neĝusta', 'malĝustas' instead of 'malĝustas'), likely due to encoding or input problems. The translation is otherwise accurate, but those are considered formatting/orthography errors.

Correct translation:
Geneza bloko aŭ ne trovita aŭ neĝusta. Ĉu eble la datadir de la reto malĝustas?
```
</details>

Number of issues: 27.
