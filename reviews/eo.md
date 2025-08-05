# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>eo</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Beo%5D%20low%20quality)


```
        <source>Close</source>
        <translation>Caleb Payne Phd</translation>
    
YES  
The translation is incorrect and unrelated to the source text. The source term "Close" should be translated into Esperanto as "Fermi" (if it means to close a window or door) or "Proksimiĝi" (if it means near/close in distance). Since this is likely a UI label, "Fermi" is appropriate.

Correct translation:  
Fermi
```

```
        <source>Choose the address to receive coins with</source>
        <translation>Elekti la adreson ricevi monerojn kun</translation>
    
YES  
The translation is incomplete and awkward in Esperanto. The phrase "ricevi monerojn kun" literally means "receive coins with" but lacks an object or a correct grammatical structure to convey "Choose the address to receive coins with." Also, "monerojn" should be "monerojn" (coins), but the phrase should be more naturally phrased.

A better translation would be:  
"Elektu la adreson, per kiu vi ricevos monerojn"  
or  
"Elektu la adreson por ricevi monerojn"  

The most straightforward:  
Elektu la adreson por ricevi monerojn
```

```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Jen viaj bitmonaj adresoj por ricevi pagojn. Estas konsilinde uzi apartan ricevan adreson por ĉiu transakcio.</translation>
    
YES  
The translation is incomplete and does not accurately convey the full meaning of the source text. It omits the instructions about the 'Create new receiving address' button and the note about signing being possible only with 'legacy' addresses.

Correct translation:  
Jen viaj Bitcoin-adresoj por ricevi pagojn. Uzu la butonon 'Krei novan ricevan adreson' en la riceva langeto por krei novajn adresojn. Subskribi eblas nur kun adresoj de la tipo 'legacy'.
```

```
        <source>Change passphrase</source>
        <translation>Ŝanĝi la pasfrazon</translation>
    
YES
The translation contains invalid characters ("Ŝanĝi") that do not exist in Esperanto orthography. The correct translation of "Change passphrase" in Esperanto should be:

Ŝanĝi la pasfrazo
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Atentu! Se vi ĉifras vian monujon kaj perdas la pasfrazon, vi &lt;b&gt;PERDOS LA TUTON DE VIA BITMONO&lt;b&gt;!</translation>
    
YES  
There are a couple of issues:  
1. The opening tag "&lt;b&gt;" is correctly used, but the closing tag is written as "&lt;b&gt;" again; it should be "&lt;/b&gt;".  
2. The original English uses a colon after "Warning", while the translation uses an exclamation mark. While not strictly wrong, it's better to mirror the punctuation for consistency.  
3. "Bitmono" is a reasonable attempt at "bitcoin" but typically "Bitcoin" is kept as is or translated as "bitmono" with capital B if needed; consistency matters. However, "bitmono" is acceptable, but "BITMONO" in all caps seems a bit odd; generally "BITCOINS" is rendered as "BITCOINS" or "bitcoin-oj" (bitcoins in plural). The phrase "LA TUTON DE VIA BITMONO" should be "ĈIUJN VIAJN BITMONOJN" or "LA ĈIAJN VIAJN BITMONOJN" for naturalness.  
An improved version:  
Atento: Se vi ĉifras vian monujon kaj perdas la pasvorton, vi &lt;b&gt;PERDOS ĈIUJN VIAJN BITMONOJN&lt;/b&gt;!  

Alternatively, keeping closer to original structure:  
Atento: Se vi ĉifras vian monujon kaj perdas la pasfrazon, vi &lt;b&gt;PERDOS ĈIUJN VIAJN BITMONOJN&lt;/b&gt;!  

Corrected translation:  
Atento: Se vi ĉifras vian monujon kaj perdas la pasfrazon, vi &lt;b&gt;PERDOS ĈIUJN VIAJN BITMONOJN&lt;/b&gt;!
```

```
        <source>Your wallet is about to be encrypted. </source>
        <translation>Via monujo estas ĉifriĝota.</translation>
    
YES  
The translation "Via monujo estas ĉifriĝota." is incorrect. "Via" means "your" in the possessive form and is correct, "monujo" means "wallet," which is accurate. However, "estas ĉifriĝota" is problematic — the verb "ĉifriĝi" is a reflexive form meaning "to become encrypted" or "to encrypt itself," but "ĉifriĝota" is a future passive participle, which sounds odd and unnatural here. The original English phrase "Your wallet is about to be encrypted." implies that an external action will encrypt the wallet soon.

A better translation would use a future or periphrastic construction indicating that the wallet will soon be encrypted, e.g., "Via monujo baldaŭ estos ĉifrita." (Your wallet will soon be encrypted.)

Correct translation:  
Via monujo baldaŭ estos ĉifrita.
```

```
        <source>Wallet encryption failed</source>
        <translation>Ĉifrado de la monujo fiaskis</translation>
    
YES  
The translation uses the Spanish word "Ĉifrado" instead of Esperanto. Also, the article "de la" is Spanish, and incorrect for Esperanto. The correct Esperanto translation for "Wallet encryption failed" is:  
"Ĉifrado de la monujo malsukcesis"
```

```
        <source>Warning: The Caps Lock key is on!</source>
        <translation>Atentu: la majuskla baskulo estas ŝaltita!</translation>
    
YES  
The Esperanto translation contains some errors:  
- "Atentu" means "pay attention" or "be careful" instead of "Warning". The correct word for "Warning" in this context is "Averto".  
- "majuskla baskulo" is incorrect and awkward. The correct term for "Caps Lock key" in Esperanto is "Caps Lock-klavo" or "Shift-loko" (less common). The term "baskulo" does not mean key.  
- The letter "ŝ" should be written correctly instead of "ŝ".  
- "estas ŝaltita" means "is switched on", which is fine idiomatically.

Correct translation:  
Averto: la Caps Lock-klavo estas ŝaltita!
```

```
        <source>Send coins to a Bitcoin address</source>
        <translation>Sendi monon al Bitmon-adreso</translation>
    
YES  
The Esperanto translation contains errors: "Sendi" is misspelled as "Sendi" instead of "Sendi" (which is actually correct infinitive), but "monon" (coins) is used incorrectly in plural; "monon" is singular accusative. The word "Bitmon-adreso" is incorrect; the correct term for Bitcoin is "Bitcoin", and the Esperanto for "Bitcoin address" is commonly "Bitkina adreso" or "Bitcoin-adreso". Also, "Sendi monon al Bitcoin-adreso" is more appropriate, as "monon" is singular accusative of "mono" (money, coin) so it's better to use plural accusative "monerojn" (coins), or generic "monon" (money). However, since in Bitcoin context "coins" is often translated as "moneroj" (coins), it's better to use "monerojn" in accusative plural.

Correct translation:  
Sendi monerojn al Bitcoin-adreso
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Ŝanĝi la pasfrazon por ĉifri la monujon</translation>
    
YES  
The translation contains multiple errors and unnatural forms in Esperanto:  
- "Ŝanĝi" should be "Ŝanĝi" (unicode ĉapelo used properly).  
- "la pasfrazon" should be "la pasfrazo" (no accusative ending needed here because it's the object), or more commonly "pasfrazo" itself is a noun; however, since "change" is a verb acting on the object "passphrase," the accusative ending "-n" is correct here ("la pasfrazon").  
- "ĉifri" should be "ĉifri" (correct diacritic).  
- "la monujon" is correct as "the wallet" in accusative case (if it is the object of the phrase), but in this sentence "used for wallet encryption" is a characteristic, so "por ĉifri la monujon" is fine.

A better, more natural and correct translation:  
"Ŝanĝi la pasfrazon uzatan por ĉifri la monujon"  

It captures "Change the passphrase used for wallet encryption" correctly, with proper spelling and grammar.

Final corrected translation:  
Ŝanĝi la pasfrazon uzatan por ĉifri la monujon
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>Ĉifri la privatajn ŝlosilojn de via monujo</translation>
    
YES  
The translation contains incorrect and non-standard Esperanto characters: "Ĉ" and "ŝ" are not valid Esperanto letters. The correct Esperanto letters are ĉ (c circumflex) and ŝ (s circumflex), but these should be encoded correctly, not as "Ĉ" or "ŝ". Also, the words should have correct accents: "Ĉifri la privatajn ŝlosilojn de via monujo".  

Correct translation:  
Ĉifri la privatajn ŝlosilojn de via monujo
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Kontroli mesaĝojn por kontroli ĉu ili estas subskribitaj per specifaj Bitmon-adresoj</translation>
    
YES  
The translation has a minor redundancy in the phrase "Kontroli mesaĝojn por kontroli," which repeats "verify/check" unnecessarily. Also, "Bitmon-adresoj" should be "Bitcoin-adresoj" since "Bitcoin" is commonly left as is or adapted without changing to "Bitmon". Additionally, the phrase "signed with specified Bitcoin addresses" is better rendered as "subskribitaj per la specifitaj Bitcoin-adresoj" for clarity and agreement.

Correct translation:  
Kontrolu mesaĝojn por certigi, ke ili estas subskribitaj per la specifitaj Bitcoin-adresoj
```

```
        <source>%1 behind</source>
        <translation>mankas %1</translation>
    
YES  
The translation "mankas %1" is incorrect and does not convey the intended meaning of "%1 behind" in Esperanto. The English phrase "%1 behind" (in the context of blockchain synchronization) means that the node is behind by %1 blocks or some measure. A correct Esperanto translation would reflect being "malantaŭ" (behind) or "post" and include the placeholder "%1" properly.

Correct translation:  
%1 malantaŭ
```

```
        <source>Transactions after this will not yet be visible.</source>
        <translation>Transakcioj por tio ankoraŭ ne videblas.</translation>
    
YES
The Esperanto translation has a spacing issue and a minor grammatical problem: "ankoraŭ" should be written as "ankoraŭ" (with the accented u), and the phrase "por tio" is incorrect in this context. The correct preposition would be "post ĉi tio" to convey "after this." Also, the verb form should reflect "will not yet be visible," which is best expressed as "ankoraŭ ne estos videblaj." Since "transakcioj" is plural, the adjective and verb must agree in number.

Correct translation:
Transakcioj post ĉi tio ankoraŭ ne estos videblaj.
```

```
        <source>Coin Selection</source>
        <translation>Monero-Elektaĵo</translation>
    
YES  
The translation incorrectly uses "Monero," which is a different cryptocurrency, not "Bitcoin." The English "Coin Selection" refers generally to choosing coins (UTXOs) in Bitcoin, so it should not specify Monero. A correct Esperanto translation would be:  
"Monero-Elektaĵo" → "Monero Election" (incorrect)  
Correct translation:  
"Monero-Elektaĵo" → "Elektado de Monero" (if it were Monero, but here it is Bitcoin)  
Since it's Bitcoin context, "Monero" must be replaced with "Mono" (coin) or left as "Monero" only if meant to refer to Monero cryptocurrency, but that is not the case here.  

Correct translation:  
"Monero-Elektaĵo" → "Monero" should be replaced by "Monero" → no  
So the correct is:  
"Coin Selection" → "Monero-Elektaĵo" (wrong)  
Better: "Elektado de moneroj" or simply "Elektado de moneroj" (Coins selection)  

Thus, proposed correct translation:  
Elektado de moneroj  

Or even shorter:  
Moneroelekto  

But standard usage in Esperanto is "Elektado de moneroj" for coin selection.  

Therefore:  
YES  
The translation uses "Monero," which is a different cryptocurrency and incorrect here. "Coin Selection" should be translated as "Elektado de moneroj."
```

```
        <source>Copy after fee</source>
        <translation>Kopii post krompago</translation>
    
YES  
The Esperanto word for "copy" is "kopii" (with double 'i') as a verb or "kopio" as a noun. "Kopii" is the verb form "to copy," and "kopio" is the noun "copy." Since the English phrase is a noun phrase ("Copy after fee"), the correct translation should use the noun form "kopio."  

Also, "post krompago" is fine and means "after fee."  

Correct translation:  
Kopio post krompago
```

```
        <source>change from %1 (%2)</source>
        <translation>restmono de %1 (%2)</translation>
    
YES  
The Esperanto word for "change" (referring to Bitcoin transaction change) should be "troŝanĝo" or "monŝanĝo," not "restmono," which is a non-standard or incorrect coinage. Also, "from" should be translated as "de." The correct translation is:  
restmono de %1 (%2) → troŝanĝo de %1 (%2)
```

```
        <source>(change)</source>
        <translation>(restmono)</translation>
    
YES  
The English word "change" in the Bitcoin context usually refers to "restmono" in Esperanto, which is correct. However, the official Esperanto term for "change" in a financial or transaction context is generally "restmono," but it is typically not enclosed in parentheses unless preserving the original format.

The source includes parentheses: "(change)", so the translation should preserve these parentheses exactly.

Correction:  
(restmono)
```

```
        <source>Open wallet warning</source>
        <translation>Malfermi monujon averto</translation>
    
YES  
The Esperanto translation has grammatical and lexical issues. "Malfermi" is an infinitive verb form meaning "to open," which is inappropriate here. "Monujon" is the accusative singular of "monujo" (wallet), but since this phrase is a noun phrase or title ("Open wallet warning"), the nominative "monujo" should be used. Also, "averto" is a valid Esperanto word for "warning," but a more common and better fitted translation for a warning or alert would be "averto" or "avizo," "averto" is acceptable. Furthermore, the word order should be natural: "Averto pri malfermo de monujo" (Warning about opening wallet) or a concise phrase like "Averto pri malfermo de monujo". However, considering the original phrase is short and likely a UI title, a concise and idiomatic translation is:  

"Malfermaĵa averto pri monujo" — although "malfermaĵa" is awkward.  

Better and simpler is:  
"Averto malfermi monujon" or simply "Averto pri malfermo de monujo".  

Given standard practice in software translations, the most direct and conventional translation would be:  
"Averto pri malfermo de monujo"  

Correct translation:  
<Averto pri malfermo de monujo>
```

```
        <source>Open Wallet</source>
        <extracomment>Title of window indicating the progress of opening of a wallet.</extracomment>
        <translation>Malfermi la Monujon</translation>
    
YES
The Esperanto translation uses "Malfermi" (the infinitive "to open") instead of the imperative or appropriate form. Also, "Monujon" is the accusative form, but here the phrase is a title or button label and should use the nominative.

A better translation is:
"Malfermu la monujon" (imperative: "Open the wallet")

Alternatively, simply:
"Malfermu monujon"

But since the English is a title/button label "Open Wallet," imperative "Malfermu la monujon" is the most accurate and natural translation.
```

```
        <source>Open bitcoin URI</source>
        <translation>Malfermi na la URI de bitmono</translation>
    
YES
The translation is not idiomatic and contains unnecessary words. "Malfermi na la URI de bitmono" is awkward and incorrect in Esperanto. The English phrase "Open bitcoin URI" should be translated more directly and naturally.

Correct translation:
Malfermi bitcoin-URI-n
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Alglui adreson de tondejo</translation>
    
YES
The word "Alglui" is incorrect in Esperanto. The correct infinitive form of the verb "to paste" is "Algluti" or "Alglui" is a malformed form. The correct imperative/command form should be "Algluu" or better "Algluu adreson de la tondejo" (paste address from the clipboard).

Also, "adreson" should be preceded by the article "la" for clarity ("la adreson").

"tondejo" is acceptable for "clipboard," but usually "tondejo" is not a common Esperanto term for clipboard. A more common term would be "tondejo" or "poŝtabulo," but "tondejo" is sometimes used.

The phrase "de tondejo" should be "de la tondejo" (of the clipboard) - articles are often necessary.

Correct translation:
Algluu la adreson de la tondejo
```

```
        <source>Automatically start %1 after logging in to the system.</source>
        <translation>Aŭtomate komenci na %1 post ensalutis en la sistemon.</translation>
    
YES  
The translation contains errors in grammar and word choice.  
- "na %1" is incorrect; it should simply be "%1" without the preposition "na".  
- "post ensalutis en la sistemon" is ungrammatical; the verb should agree with an implied subject and be in the infinitive or another correct form. A better phrasing is "post ensaluti en la sistemon" (after logging in to the system).  

Correct translation:  
Aŭtomate komenci %1 post ensaluti en la sistemon.
```

```
        <source>Number of script verification threads</source>
        <translation>Kvanto da skriptaj kaj kontroleraraj fadenoj</translation>
    
YES  
The translation contains errors with word choices and structure. The English phrase "Number of script verification threads" should be translated as "Kvanto da fadenoj por skripta validigo" or "Kvanto da fadenoj por skripta kontrolo." The given "skriptaj kaj kontroleraraj fadenoj" is incorrect: "kaj" means "and," which is wrong here; also, "kontroleraraj" is not a proper Esperanto word.

Correct translation:  
Kvanto da fadenoj por skripta validigo
```

```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Elekti la defaŭltan manieron por montri bitmonajn sumojn en la interfaco, kaj kiam vi sendos bitmonon.</translation>
    
YES  
The translation contains errors and is not fully accurate. Specifically:  
- "defaŭltan" should be "defaŭltan" (the diacritic on "ŭ" is incorrect).  
- "manieron" ("method" or "manner") is incorrect here; the source means "subdivision unit" (i.e., a unit of currency), so "subunuo" or "subdivida unuo" is more appropriate.  
- "bitmonajn sumojn" ("bitmonaj sums") is awkward and inaccurate; the source refers to a subdivision unit, not sums.  
- "kiam vi sendos bitmonon" means "when you will send bitcoin," but it should be "when sending coins" (a general instruction), so the infinitive "sendi" ("sending") fits better.  
- "bitmono" should probably be "bitmono" (bitcoin) or just "bitmonoj" in plural, but better to remain consistent; the source text uses "coins" (plural), so "bitmonojn."

Correct translation:  
Elektu la defaŭltan subdividan unuon por montri en la interfaco kaj kiam oni sendas bitmonojn.
```

```
        <source>Whether to show coin control features or not.</source>
        <translation>Ĉu montri detalan adres-regilon, aŭ ne.</translation>
    
YES  
The translation "Ĉu montri detalan adres-regilon, aŭ ne." translates back as "Whether to show a detailed address controller, or not." This is inaccurate because the source refers generally to "coin control features," not specifically an "address controller." Also, "adres-regilon" (address controller) is not a proper or common translation for coin control in Bitcoin context. The phrase should remain general about coin control features.

Correct translation:  
"Ĉu montri monkontrolajn funkciojn aŭ ne."
```

```
        <source>default</source>
        <translation>defaŭlta</translation>
    
YES
The Esperanto translation "defaŭlta" is incorrect and not proper Esperanto. The correct translation for "default" in the Bitcoin context (usually meaning standard or preset) is "defaŭlta" with a proper Esperanto circumflex over the "u". Using "aŭ" is an attempt to represent the accented letter 'ŭ' but should be written properly using the Unicode character.

Correct translation:
defaŭlta
```

```
        <source>Your current spendable balance</source>
        <translation>via aktuala elspezebla saldo</translation>
    
YES  
There is a typo in the translation. The word "via" should be capitalized as "Via" if it is the first word or corrected to "Via" is incorrect here—actually, "via" is incorrect; it should be "Via" if it's a name, but in this context, the correct Esperanto word for "your" is "via" (all lowercase), so "via" is fine.

However, the adjective "aktuala" should be "aktuala" (correct), and "elspezebla" is correct for "spendable", and "saldo" (balance) is correct.

The problem is with the whitespace at the start: there is a leading space before "via" ("via aktuala elspezebla saldo"), possibly a stray space.

Also, in Esperanto, phrase order and correctness is generally acceptable here, but the phrase could be improved for smoother or more natural style.

"via aktuala elspezebla saldo" literally means "your current spendable balance" and is syntactically correct.

No format specifiers exist in the source.

Conclusion: only a leading space seems problematic.

Correct translation without leading space:

via aktuala elspezebla saldo

The provided translation has a leading space before "via", so it should be removed.

Hence:

YES  
There is an extra leading space before "via". The corrected translation is:  
via aktuala elspezebla saldo
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>la sumo de transakcioj ankoraŭ ne konfirmitaj, kiuj ankoraŭ ne elspezeblas</translation>
    
YES
The Esperanto translation contains errors and some awkward phrasing:
- "la sumo" should be "la sumo" without "la" if referring to the total as a concept, or better "la sumo" is acceptable, but the word "suma" or "suma kvanto" might be smoother.
- "transakcioj" should be plural accusative if directly linked as the object, but here it acts as a subject, so nominative plural is correct.
- The phrase is missing clear structure and is ambiguous.
- "ankoraŭ ne konfirmeitaj" is better as "ankoraŭ nekonfirmitaj".
- "ankoraŭ ne elspezeblas" is grammatically incorrect; "ankoraŭ ne kalkuliĝas en la elspezebla saldo" or similar is needed to convey "do not yet count toward the spendable balance".

A better translation would be:

"La totalo de transakcioj ankoraŭ nekonfirmitaj, kiuj ankoraŭ ne kalkuliĝas en la elspezebla saldo"

or more fluidly:

"Sumo de transakcioj, kiuj ankoraŭ ne estas konfirmitaj kaj ankoraŭ ne kalkulas al la elspezebla saldo"

Final correction:

<translation>Sumo de transakcioj, kiuj ankoraŭ ne estas konfirmitaj kaj ankoraŭ ne kalkulas al la elspezebla saldo</translation>
```

```
        <source>Send Coins</source>
        <translation>Sendi Bitmonon</translation>
    
YES  
The Esperanto translation is inaccurate. "Sendi Bitmonon" is an incorrect formulation. The verb "sendi" means "to send," but "Sendi" as such is a verb, while the source text uses a noun phrase "Send Coins," which is an imperative or command, or possibly a button label telling the user to "Send Coins."

In Esperanto, "Send Coins" as a command or button text would simply be "Sendi Monerojn" or "Sendi Bitmonojn" if referring to Bitcoin coins. The word "Bitmonon" is singular accusative, but in this context, the plural should be used (coins, plural). Also, the word "Bitmono" is a neologism for Bitcoin coin and not universally accepted; "Bitmono" is acceptable in some circles, but "bitmonon" presumes singular accusative.

Therefore, better translations could be:

- Sendu Monerojn (imperative: Send coins)  
- Sendi bitmonojn (infinitive phrase: to send bitcoins)  
- Sendi Monerojn  

Given the source text context indicating a button or command, the imperative form is preferable.

Correct translation:  
Sendu Bitmonojn
```

```
        <source>Transaction Fee:</source>
        <translation>Krompago:</translation>
    
YES  
The Esperanto translation "Krompago:" is incorrect for "Transaction Fee:". The correct term should be "Transakcia kotizo:" or simply "Transakcia puno:".  
Correct translation:  
Transakcia kotizo:
```

```
        <source>Copy after fee</source>
        <translation>Kopii post krompago</translation>
    
YES  
The Esperanto word for "copy" is "kopii" (with double 'i') as a verb or "kopio" as a noun. "Kopii" is the verb form "to copy," and "kopio" is the noun "copy." Since the English phrase is a noun phrase ("Copy after fee"), the correct translation should use the noun form "kopio."  

Also, "post krompago" is fine and means "after fee."  

Correct translation:  
Kopio post krompago
```

```
        <source>Transaction fee</source>
        <translation>Krompago</translation>
    
YES  
The Esperanto translation "Krompago" is incorrect here. The correct term for "Transaction fee" in Esperanto is "Transakcia kotizo" or simply "Transakcia pago". "Krompago" means "additional payment" or "extra pay," which is not accurate in this context.

Correct translation:  
Transakcia kotizo
```

```
        <source>Confirm send coins</source>
        <translation>Konfirmi sendon de bitmono</translation>
    
YES  
The translated phrase mixes Esperanto ("Konfirmi") with an English word ("sendon") and a non-Esperanto term ("bitmono"). The correct Esperanto translation should use consistent Esperanto vocabulary. "Sendi" is the verb "to send," and the accusative of "bitmono" (bitcoin coin) is "bitmonon."

Correct translation:  
Konfirmu sendi bitmonojn
```

```
        <source>Paste address from clipboard</source>
        <translation>Alglui adreson de tondejo</translation>
    
YES  
The Esperanto translation contains an error in the noun form. "Adreson" should be the accusative form of "adreso," which is correct here since it is the object of the verb "alglui" (paste). However, "alglui" literally means "to stick on" or "to glue," which is not an appropriate verb for pasting text from the clipboard in the context of computer usage. The correct verb in this context is "alglui" rarely used in computing, instead "alglui" might be understood but is not idiomatic. The more appropriate verb for pasting text is "enmeti" (insert) or "glui" (to paste) is also sometimes used, but better would be the verb "glui" (to paste) which is normally the infinitive.

But here "Alglui" is a typo or incorrect form; should be "Alglui" or "Glui"?

In computer context, "alglui" can be acceptable but better is "Alglui adreson de la tondejo" (the "la" is missing before "tondejo").

Moreover, "tondejo" (clipboard) in Esperanto is "tondejo," but better is "büfrobordo" or "bubfrobordo," but "tondejo" is acceptable neologism.

The main problem is missing the article "la" before "tondejo," it should be:

"Alglui adreson de la tondejo"

Additional note: the verb "Alglui" can be changed to "Alglui" or more common slang equivalent "Alglui," or better "Alglui."

So the corrected translation is:

"Alglui adreson de la tondejo"

Or better:

"Alglui la adreson el la tondejo"

("Paste the address from the clipboard")

But since the original source is "Paste address from clipboard" (imperative, no article), the simplest correct translation is:

"Alglui adreson de la tondejo"

So the error is the missing "la" before "tondejo."

Correct translation:

"Alglui adreson de la tondejo"

---

Alternatively, if we want to be more natural:

"Alglui adreson el la tondejo"

("Paste address from the clipboard")

Using "el" (from) instead of "de" is more natural here.

Hence final corrected translation:

"Alglui adreson el la tondejo"

Therefore, original translation is problematic due to missing definite article "la" before "tondejo" and more natural preposition is "el" rather than "de."

---

Final answer:  
YES  
The translation is missing the definite article "la" before "tondejo," and the preposition "de" should be replaced by "el" for naturalness.

Correct translation:  
"Alglui adreson el la tondejo"
```

```
        <source>Paste address from clipboard</source>
        <translation>Alglui adreson de tondejo</translation>
    
YES  
The Esperanto translation contains an error in the noun form. "Adreson" should be the accusative form of "adreso," which is correct here since it is the object of the verb "alglui" (paste). However, "alglui" literally means "to stick on" or "to glue," which is not an appropriate verb for pasting text from the clipboard in the context of computer usage. The correct verb in this context is "alglui" rarely used in computing, instead "alglui" might be understood but is not idiomatic. The more appropriate verb for pasting text is "enmeti" (insert) or "glui" (to paste) is also sometimes used, but better would be the verb "glui" (to paste) which is normally the infinitive.

But here "Alglui" is a typo or incorrect form; should be "Alglui" or "Glui"?

In computer context, "alglui" can be acceptable but better is "Alglui adreson de la tondejo" (the "la" is missing before "tondejo").

Moreover, "tondejo" (clipboard) in Esperanto is "tondejo," but better is "büfrobordo" or "bubfrobordo," but "tondejo" is acceptable neologism.

The main problem is missing the article "la" before "tondejo," it should be:

"Alglui adreson de la tondejo"

Additional note: the verb "Alglui" can be changed to "Alglui" or more common slang equivalent "Alglui," or better "Alglui."

So the corrected translation is:

"Alglui adreson de la tondejo"

Or better:

"Alglui la adreson el la tondejo"

("Paste the address from the clipboard")

But since the original source is "Paste address from clipboard" (imperative, no article), the simplest correct translation is:

"Alglui adreson de la tondejo"

So the error is the missing "la" before "tondejo."

Correct translation:

"Alglui adreson de la tondejo"

---

Alternatively, if we want to be more natural:

"Alglui adreson el la tondejo"

("Paste address from the clipboard")

Using "el" (from) instead of "de" is more natural here.

Hence final corrected translation:

"Alglui adreson el la tondejo"

Therefore, original translation is problematic due to missing definite article "la" before "tondejo" and more natural preposition is "el" rather than "de."

---

Final answer:  
YES  
The translation is missing the definite article "la" before "tondejo," and the preposition "de" should be replaced by "el" for naturalness.

Correct translation:  
"Alglui adreson el la tondejo"
```

```
        <source>Enter the message you want to sign here</source>
        <translation>Tajpu la mesaĝon, kiun vi volas sendi, cîi tie</translation>
    
YES  
The English source says "Enter the message you want to sign here," but the Esperanto translation says "Type the message you want to send here," which changes the meaning from "sign" to "send." The word "sign" in this Bitcoin context refers to cryptographic signing.

Correct translation:  
Enmetu la mesaĝon, kiun vi volas subskribi ĉi tie
```

```
        <source>Verify the message to ensure it was signed with the specified Bitcoin address</source>
        <translation>Kontroli la mesaĝon por pravigi, ke ĝi ja estas subskribita per la specifa Bitmon-adreso</translation>
    
YES  
The translation contains minor issues:
- "mesaĝon" should be spelled "mesaĝon" with a regular "ĝ" instead of a superscript circumflex "^".
- "pravigi" is less appropriate here; "certigi" or "konfirmi" fit better for "ensure".
- "Bitmon-adreso" is a misspelling of "Bitcoin-adreso".
- The phrase "ke ĝi ja estas subskribita" is slightly awkward; better is "ke ĝi estis subskribita" ("that it was signed").
- Also, space before commas and punctuation in Esperanto has standard spacing rules; here it's fine.
- The meaning can be better conveyed and closer to the source meaning.

Correct translation:
Kontrolu la mesaĝon por certigi, ke ĝi estis subskribita per la specifa Bitcoin-adreso
```

```
        <source>Transaction fee</source>
        <translation>Krompago</translation>
    
YES  
The Esperanto translation "Krompago" is incorrect here. The correct term for "Transaction fee" in Esperanto is "Transakcia kotizo" or simply "Transakcia pago". "Krompago" means "additional payment" or "extra pay," which is not accurate in this context.

Correct translation:  
Transakcia kotizo
```

```
        <source>Transaction status. Hover over this field to show number of confirmations.</source>
        <translation>Transakcia stato. Ŝvebi super tiu ĉi kampo por montri la nombron de konfirmoj.</translation>
    
YES  
The translation contains errors in Esperanto:  
- "Transakcia" should be "Transakcia" not "Transakcia", but more proper Esperanto is "Transakcia stato" or "Situacio de transakcio". "Transakcia stato" is acceptable if "stato" is Esperanto "state", but "stato" is a word in Esperanto (meaning state), so acceptable.  
- The word "Ŝvebi" is incorrectly spelled with the circumflex on "S", but in Esperanto, the letter 'ŝ' is correct, but it should be rendered as "ŝ" not "ŝ". The letter is ŝ (U+015D), not ŝ (s + combining circumflex).  
- Also, it would be better to keep the correct spelling: "Ŝvebi super ĉi tiun kampon por montri la nombron de konfirmoj."  
- "tiu ĉi kampo" should be written as "ĉi tiu kampo" (correct Esperanto word order).  
- "kampo" is fine for "field".  
- No format specifiers to check here.  
- There is an issue with spacing: "Ŝvebi super tiu ĉi kampo" vs "Ŝvebi super ĉi tiu kampo".

Correct translation:  
"Transakcia stato. Ŝvebu super ĉi tiu kampo por montri la nombron de konfirmoj."
```

```
        <source>This month</source>
        <translation>Ĉi-monate</translation>
    
YES
The translation uses an incorrect character 'Ĉ' and a hyphenated form that is not standard in Esperanto. The correct translation for "This month" in Esperanto is:

Ĉi tiu monato
```

```
        <source>Send Coins</source>
        <translation>Sendi Bitmonon</translation>
    
YES  
The Esperanto translation is inaccurate. "Sendi Bitmonon" is an incorrect formulation. The verb "sendi" means "to send," but "Sendi" as such is a verb, while the source text uses a noun phrase "Send Coins," which is an imperative or command, or possibly a button label telling the user to "Send Coins."

In Esperanto, "Send Coins" as a command or button text would simply be "Sendi Monerojn" or "Sendi Bitmonojn" if referring to Bitcoin coins. The word "Bitmonon" is singular accusative, but in this context, the plural should be used (coins, plural). Also, the word "Bitmono" is a neologism for Bitcoin coin and not universally accepted; "Bitmono" is acceptable in some circles, but "bitmonon" presumes singular accusative.

Therefore, better translations could be:

- Sendu Monerojn (imperative: Send coins)  
- Sendi bitmonojn (infinitive phrase: to send bitcoins)  
- Sendi Monerojn  

Given the source text context indicating a button or command, the imperative form is preferable.

Correct translation:  
Sendu Bitmonojn
```

```
        <source>Error initializing block database</source>
        <translation>Eraro dum pravalorizado de blokdatumbazo</translation>
    
YES  
The word "pravalorizado" is incorrect in Esperanto; it is not a proper Esperanto term. The verb "initializing" should be translated as "komencado," "inicialigado," or "inicializo." A correct translation would be:

Eraro dum inicializado de blokdatumbazo
```

```
        <source>Error initializing wallet database environment %s!</source>
        <translation>Eraro dum pravalorizado de monuj-datumbaza ĉirkaŭaĵo %s!</translation>
    
YES  
The translation contains several errors:  
- "pravalorizado" is not a correct Esperanto word; it seems to be a mistranslation or a coined term. The correct verb for "initializing" is "inicializado" or better "komencigo" or "komencanta".  
- "monuj-datumbaza" should be "monuj-datumbazo" (the suffix "-o" for nouns, and the adjective "datumbaza" correctly before the noun) but better is "monuj-datumbazo" without the hyphen or with a hyphen but "ĉirkaŭaĵo" is incorrect.  
- "ĉirkaŭaĵo" seems to be a mangled word. The correct translation of "environment" in this context is "medio" or "ĉirkaŭaĵo" (environment). However, "ĉirkaŭaĵo" is a noun meaning surroundings, environment, or surroundings, but "environment" in programming is usually translated as "medio" or "medio de funkciado". "Ĉirkaŭaĵo" is acceptable but must be written correctly with Esperanto characters and proper grammar ("ĉirkaŭaĵo", not with strange diacritics or notations).

A better translation is:  
"Eraro dum inicializado de la monuj-datumbaza medio %s!"

or for clarity:  
"Eraro dum inicializado de la medio de la monuj-datumbazo %s!"

So a corrected version:

Eraro dum inicializado de la monuj-datumbaza medio %s!

No extra spaces or format errors.

Hence:

YES  
The Esperanto translation contains non-existent words and incorrect spelling. A correct translation would be:  
Eraro dum inicializado de la monuj-datumbaza medio %s!
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>Geneza bloko aŭ netrovita aŭ neĝusta. Ĉu eble la datadir de la reto malĝustas?</translation>
    
YES
The translation contains several errors and unfamiliar or incorrect Esperanto forms; for example, "aŭ" should be "aŭ" (using the proper Esperanto diacritic), "netrovita" and "neĝusta" are wrongly formed and misspelled (should be "netrovita" for "not found" is acceptable but better as "ne troviĝis", and "neĝusta" for "wrong"), and "datadir" is not adapted but left as is, which is acceptable for technical terms but could be italicized or marked. The particle "Ĉu eble" is awkward; simply "Ĉu eble" or better "ĉu eble la datadir por la reto malĝustas?" is more idiomatic.

A better translation would be:
"Neĝusta aŭ neniu geneza bloko estis trovita. Ĉu eble la datendirektilo por la reto malĝustas?"

Notes:
- "genesis block" = "geneza bloko"
- "no" = "neniu"
- "found" = "trovita" or "estis trovita"
- "Wrong" = "neĝusta"
- "datadir" = "datendirektilo" or kept as "datadir" but ideally adapted.
- "network" = "reto"
- The question: "Wrong datadir for network?" is translated as a question with "Ĉu eble ... malĝustas?"

Final corrected translation:
"Neĝusta aŭ neniu geneza bloko estis trovita. Ĉu eble la datendirektilo por la reto malĝustas?"
```
</details>
