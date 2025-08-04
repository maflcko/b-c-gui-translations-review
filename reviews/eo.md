# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>eo</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Beo%5D%20low%20quality)


```
        <source>Close</source>
        <translation>Caleb Payne Phd</translation>
    
YES. The translation is completely inaccurate and irrelevant to the source text.
The source text "Close" means to end or shut something. The translation "Caleb Payne Phd" is a person's name and title, which has no relation to "Close".

Correct translation: Fermu
```

```
        <source>Choose the address to receive coins with</source>
        <translation>Elekti la adreson ricevi monerojn kun</translation>
    
YES: The translation is grammatically incorrect. The preposition "kun" should be placed after the noun it modifies.
Elektu la adreson por ricevi monerojn kun
```

```
        <source>These are your Bitcoin addresses for receiving payments. Use the 'Create new receiving address' button in the receive tab to create new addresses.
Signing is only possible with addresses of the type 'legacy'.</source>
        <translation>Jen viaj bitmonaj adresoj por ricevi pagojn. Estas konsilinde uzi apartan ricevan adreson por ĉiu transakcio.</translation>
    
YES - The translation is incomplete and does not include the crucial information that signing is only possible with 'legacy' type addresses. Additionally, it adds extra information ("Estas konsilinde uzi apartan ricevan adreson por ĉiu transakcio.") which was not present in the original English text.
NO - Jen viaj bitmonaj adresoj por ricevi pagojn. La subskribo nur eblas kun adresoj de la tipo 'legacy'.
```

```
        <source>Change passphrase</source>
        <translation>Ŝanĝi la pasfrazon</translation>
    
YES - The translation uses an incorrect character (ŝ) for the letter 's'. The correct translation should be "Ŝanĝi la pasfrazon".
YES - Ŝanĝi la pasfrazon
Ŝanĝi la pasfrazon
```

```
        <source>Warning: If you encrypt your wallet and lose your passphrase, you will &lt;b&gt;LOSE ALL OF YOUR BITCOINS&lt;/b&gt;!</source>
        <translation>Atentu! Se vi ĉifras vian monujon kaj perdas la pasfrazon, vi &lt;b&gt;PERDOS LA TUTON DE VIA BITMONO&lt;b&gt;!</translation>
    
YES: The closing tag for the bold text is incorrect. It should be </b/> instead of </b/>.
Atentu! Se vi ĉifras vian monujon kaj perdas la pasfrazon, vi &lt;b&gt;PERDOS LA TUTON DE VIA BITMONO&lt;/b&gt;!
```

```
        <source>Your wallet is about to be encrypted. </source>
        <translation>Via monujo estas ĉifriĝota.</translation>
    
YES: The translation uses an incorrect verb form. "ĉifriĝota" means "will be encrypted" and implies future action, whereas the source "is about to be encrypted" implies an imminent or ongoing process. The correct translation should reflect this imminence.

NO
```

```
        <source>Wallet encryption failed</source>
        <translation>Ĉifrado de la monujo fiaskis</translation>
    
YES: The translation uses an incorrect word for "wallet". The correct Esperanto word is "monujo" or "monujo".
Ĉifrado de la monujo fiaskis
```

```
        <source>Warning: The Caps Lock key is on!</source>
        <translation>Atentu: la majuskla baskulo estas ŝaltita!</translation>
    
YES: The translation uses the circumflex accent (^) instead of the caron accent (ˇ) for the letter 's' in "ŝaltita", which is incorrect in Esperanto. The correct word is "ŝaltita". Additionally, the word "ŝaltita" should not be capitalized in this context.

NO: Atentu: la majuskla baskulo estas ŝaltita!
```

```
        <source>Send coins to a Bitcoin address</source>
        <translation>Sendi monon al Bitmon-adreso</translation>
    
YES, The translation is problematic. "Monon" is not a recognized word in Esperanto. The correct translation for "coins" in the context of Bitcoin would be "moneroj" or "kriptomoneroj".

NO. The translation is problematic. The word "monon" is not a valid Esperanto word. The context of Bitcoin implies "coins" which is best translated as "moneroj" or more specifically "kriptomoneroj".

Correct translation: Sendi monerojn al Bitmon-adreso
```

```
        <source>Change the passphrase used for wallet encryption</source>
        <translation>Ŝanĝi la pasfrazon por ĉifri la monujon</translation>
    
YES - The translation contains non-standard and likely incorrect characters. The correct Esperanto word for "change" (verb) is "ŝanĝi", and for "wallet" it is "monujo".
ŝanĝi la pasfrazon por ĉifri la monujon
```

```
        <source>Encrypt the private keys that belong to your wallet</source>
        <translation>Ĉifri la privatajn ŝlosilojn de via monujo</translation>
    
YES
The accented letters 'Ĉ' and 'ŝ' are not standard Esperanto characters. The correct Esperanto characters for 'C' and 'S' with the circumflex are 'Ĉ' and 'Ŝ'.

Ĉifri la privatajn ŝlosilojn de via monujo
Correct translation: Ĉifri la privatajn ŝlosilojn de via monujo
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Kontroli mesaĝojn por kontroli ĉu ili estas subskribitaj per specifaj Bitmon-adresoj</translation>
    
YES: The translation uses "ĉu ili estas subskribitaj" which is not the most direct or natural translation for "they were signed". A more accurate and common phrasing would be "ili estas subskribitaj" or "ili estis subskribitaj". Additionally, "Bitmon-adresoj" is not the correct Esperanto term for Bitcoin addresses. The correct term is "Bitcoin-adresoj".

NO: Kontrolu mesaĝojn por certigi, ke ili estas subskribitaj per specifaj Bitcoin-adresoj
```

```
        <source>%1 behind</source>
        <translation>mankas %1</translation>
    
YES
The translation is incorrect. "behind" in this context likely refers to a block height or number of confirmations behind the current network state. "mankas" means "lacks" or "is missing", which doesn't fit the context. A more accurate translation would convey being a certain number of blocks behind.
NO
The provided translation of "%1 behind" to "mankas %1" is incorrect and problematic in the context of Bitcoin.

*   **Accuracy:** "mankas" means "lacks" or "is missing." In the context of Bitcoin, "%1 behind" usually refers to being a certain number of blocks behind the current network tip (e.g., "5 blocks behind"). The translation "mankas %1" would imply that something is *missing* that number of blocks, which is not the intended meaning.
*   **Problematic Content:** It's not unwanted content or spam, but it's factually incorrect for the domain.

**Correct Translation:**

The correct translation should convey the idea of "behind" in terms of blocks or confirmations. Depending on the exact nuance intended, a few options exist:

*   **If it means "N blocks behind the latest":**
    <source>%1 behind</source>
    <translation>malantaŭ %1</translation>
    *(This uses "malantaŭ" which means "behind")*

*   **If it means "N confirmations behind":**
    <source>%1 behind</source>
    <translation>konfirmon mankon %1</translation>
    *(This translates to "confirmation lack %1", which could also be adapted depending on the exact sentence structure.)*

Given the simplicity of the source, "malantaŭ %1" is the most direct and likely accurate translation for being a certain number of blocks behind.

Since the translation is problematic, the output should start with YES.

YES
The translation is inaccurate. "mankas" means "lacks" or "is missing", whereas the source "%1 behind" in a Bitcoin context typically refers to being a certain number of blocks or confirmations behind the current network state.
malantaŭ %1
```

```
        <source>Transactions after this will not yet be visible.</source>
        <translation>Transakcioj por tio ankoraŭ ne videblas.</translation>
    
YES: The translation is inaccurate. The word "post" in "Transactions after this" means "following" or "coming after". The translation uses "por tio" which means "for this", which is not equivalent.

NO: Transakcioj post ĉi tio ankoraŭ ne videblos.
```

```
        <source>Coin Selection</source>
        <translation>Monero-Elektaĵo</translation>
    
YES, The translation is problematic as it mentions "Monero" instead of "Bitcoin". The correct translation should reflect the context of Bitcoin.
Monero-Elektaĵo
```

```
        <source>Copy after fee</source>
        <translation>Kopii post krompago</translation>
    
YES: The translation of "Copy after fee" to "Kopii post krompago" is incorrect. "Krompago" means "discount" or "rebate" in Esperanto, not "fee". The correct translation for "fee" in this context would be "kotizo" or "pago". Therefore, "Kopii post kotizo" or "Kopii post pago" would be more accurate.

Kopii post kotizo
```

```
        <source>change from %1 (%2)</source>
        <translation>restmono de %1 (%2)</translation>
    
YES: The word "restmono" is not a recognized word in Esperanto. The correct translation for "change" in this context is "ŝanĝo".
correct translation: ŝanĝo de %1 (%2)
```

```
        <source>(change)</source>
        <translation>(restmono)</translation>
    
YES: The translation is inaccurate. The Esperanto word for "change" in the context of money or a transaction is "ŝanĝo". "Restmono" means "remaining money" or "change" in the sense of what's left, which is a possible interpretation but not the most direct translation of the word "change" as a noun in this context.
(ŝanĝo)
```

```
        <source>Open wallet warning</source>
        <translation>Malfermi monujon averto</translation>
    
YES: The translation is grammatically incorrect. In Esperanto, adjectives usually precede the noun they modify. The correct translation should place "malfermi" (open) and "averto" (warning) in a more natural order.
Malfermi monujon avertilo
```

```
        <source>Open Wallet</source>
        <extracomment>Title of window indicating the progress of opening of a wallet.</extracomment>
        <translation>Malfermi la Monujon</translation>
    
YES: The translation is inaccurate. "Open Wallet" translates to "Malfermi la Monujon" in Esperanto, which actually means "Close Wallet". The correct translation for "Open Wallet" is "Malfermi la Monujo".
NO Malfermi la Monujo
```

```
        <source>Directory already exists. Add %1 if you intend to create a new directory here.</source>
        <translation>Tiu dosierujo jam ekzistas. Aldonu %1 si vi volas krei novan dosierujon ĉi tie.</translation>
    
YES: The use of "ĉi tie" is grammatically incorrect. The correct translation for "here" in this context is "ĉi tie".

NO
```

```
        <source>Open bitcoin URI</source>
        <translation>Malfermi na la URI de bitmono</translation>
    
YES: The translation is grammatically incorrect. The pronoun "la" (the) before "URI" is unnecessary and creates a awkward phrasing. Also, "na" is a preposition that means "to" or "for" and is also not needed here.

Correct translation: Malfermi URI de bitmono
```

```
        <source>Paste address from clipboard</source>
        <extracomment>Tooltip text for button that allows you to paste an address that is in your clipboard.</extracomment>
        <translation>Alglui adreson de tondejo</translation>
    
YES, The translation is incorrect. The Esperanto word for clipboard is "tondejo". The correct translation is "Alglui adreson de la tondejo".
Alglui adreson de la tondejo
```

```
        <source>Automatically start %1 after logging in to the system.</source>
        <translation>Aŭtomate komenci na %1 post ensalutis en la sistemon.</translation>
    
YES, The word "na" is not correctly translated. It should be "per" or "post". The corrected translation is: Aŭtomate komenci %1 post ensaluti en la sistemon.
```

```
        <source>Number of script verification threads</source>
        <translation>Kvanto da skriptaj kaj kontroleraraj fadenoj</translation>
    
YES: The translation uses "kaj" (and) to connect "skriptaj" (script) and "kontroleraraj" (verification) where the English implies a single attribute of threads related to both scripting and verification. It should be "skriptaj kontroleraj fadenoj" (script verification threads).

NO: Kvanto da skriptaj kontroleraj fadenoj
```

```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Elekti la defaŭltan manieron por montri bitmonajn sumojn en la interfaco, kaj kiam vi sendos bitmonon.</translation>
    
YES - The translation misinterprets "subdivision unit" as "manner" and "sending coins" as "sending bitcoin", which is not accurate enough for the context.

Correct translation: Elekto la defaŭltan subdivizunuon por montri en la interfaco kaj dum sendado de moneroj.
```

```
        <source>Whether to show coin control features or not.</source>
        <translation>Ĉu montri detalan adres-regilon, aŭ ne.</translation>
    
YES: The translation is problematic because "detalan adres-regilon" (detailed address controller) does not accurately convey the meaning of "coin control features". "Coin control" in Bitcoin refers to the ability to select specific unspent transaction outputs (UTXOs) to include in a transaction, rather than letting the wallet software automatically choose them. A more accurate translation would involve terms related to coin selection or management.

Correct translation: Ĉu montri funkciojn pri mon-regilo, aŭ ne.
```

```
        <source>default</source>
        <translation>defaŭlta</translation>
    
YES, the translation is problematic. The Esperanto word for "default" is "defaŭlta". The provided translation uses a diaeresis (¨) over the 'u' instead of a circumflex (^).

defaŭlta
```

```
        <source>Your current spendable balance</source>
        <translation>via aktuala elspezebla saldo</translation>
    
YES - The translation contains an unnecessary word "via", which means "by" or "through". The correct translation should be "via aktuala elspezebla saldo".

NO
```

```
        <source>Total of transactions that have yet to be confirmed, and do not yet count toward the spendable balance</source>
        <translation>la sumo de transakcioj ankoraŭ ne konfirmitaj, kiuj ankoraŭ ne elspezeblas</translation>
    
YES: The translation is grammatically incorrect and does not accurately convey the meaning of the source text. Specifically, the phrase "kiuj ankoraŭ ne elspezeblas" (which are not yet spendable) is a misinterpretation of "do not yet count toward the spendable balance".

Correct translation: La sumo de transakcioj ankoraŭ ne konfirmitaj, kaj kiuj ankoraŭ ne kalkuliĝas kiel elspezinda saldo.
```

```
        <source>Send Coins</source>
        <translation>Sendi Bitmonon</translation>
    
YES: The translation of "Coins" to "Bitmonon" is not accurate. "Monero" is a cryptocurrency, but the context is Bitcoin. The correct translation for "Coins" in this context would be "Moneroj" or "Cifermoneroj".
Send Moneroj
```

```
        <source>Transaction Fee:</source>
        <translation>Krompago:</translation>
    
YES, The translation is incorrect. In the context of Bitcoin, "Transaction Fee" refers to the fee paid to miners for processing a transaction, not the change returned to the sender. The Esperanto word "Krompago" means "overpayment" or "extra payment", which is not the correct term.

A more accurate translation for "Transaction Fee" in this context would be "Transakcia kotizo" or "Kotizo de transakcio".

Correct translation: Transakcia kotizo:
```

```
        <source>Copy after fee</source>
        <translation>Kopii post krompago</translation>
    
YES: The translation of "Copy after fee" to "Kopii post krompago" is incorrect. "Krompago" means "discount" or "rebate" in Esperanto, not "fee". The correct translation for "fee" in this context would be "kotizo" or "pago". Therefore, "Kopii post kotizo" or "Kopii post pago" would be more accurate.

Kopii post kotizo
```

```
        <source>Transaction fee</source>
        <translation>Krompago</translation>
    
YES: The Esperanto word "Krompago" means "overpayment" or "extra payment." In the context of Bitcoin, "Transaction fee" should be translated as "Transakcia kotizo" or "Transakciaj elspezoj."
The correct translation is: Transakcia kotizo
```

```
        <source>Confirm send coins</source>
        <translation>Konfirmi sendon de bitmono</translation>
    
YES, The translation is grammatically incorrect. The verb "sendon" is not a valid Esperanto verb form. It should be "sendi" (to send) or "sendante" (sending). The word "de" (of) is also used incorrectly here. It should be "da" (amount of) or simply omitted.

NO
```

```
        <source>The total exceeds your balance when the %1 transaction fee is included.</source>
        <translation>La sumo kun la %1 krompago estas pli granda ol via saldo.</translation>
    
YES: The translation is grammatically incorrect and does not accurately convey the meaning of the original English sentence. The word "krompago" means "surcharge" or "extra charge", which is not the correct translation for "transaction fee". The correct translation should use the word "transakcikosto". Additionally, the sentence structure is awkward and unnatural in Esperanto.
La sumo inkluzive de la %1 transakcikosto superas vian saldon.
```

```
        <source>Paste address from clipboard</source>
        <translation>Alglui adreson de tondejo</translation>
    
YES: The translation of "clipboard" as "tondejo" is incorrect in this context. In Esperanto, "clipboard" is typically translated as "tondujo" or "tondilo".

Alglui adreson de tondujo
```

```
        <source>Paste address from clipboard</source>
        <translation>Alglui adreson de tondejo</translation>
    
YES: The translation of "clipboard" as "tondejo" is incorrect in this context. In Esperanto, "clipboard" is typically translated as "tondujo" or "tondilo".

Alglui adreson de tondujo
```

```
        <source>Enter the message you want to sign here</source>
        <translation>Tajpu la mesaĝon, kiun vi volas sendi, cîi tie</translation>
    
YES: The translation is inaccurate. The English text "Enter the message you want to sign here" translates to "Tajpu la mesaĝon, kiun vi volas subskribi, cîi tie" in Esperanto.
Tajpu la mesaĝon, kiun vi volas subskribi, cîi tie
```

```
        <source>Verify the message to ensure it was signed with the specified Bitcoin address</source>
        <translation>Kontroli la mesaĝon por pravigi, ke ĝi ja estas subskribita per la specifa Bitmon-adreso</translation>
    
YES: The translation uses "pravigi" which means "to justify" or "to make righteous" instead of "to verify". The correct translation for "verify" in this context would be "kontroli" or "konfirmi".

NO: Kontroli la mesaĝon por konfirmi, ke ĝi ja estas subskribita per la specifa Bitmon-adreso
```

```
        <source>Transaction fee</source>
        <translation>Krompago</translation>
    
YES: The Esperanto word "Krompago" means "overpayment" or "extra payment." In the context of Bitcoin, "Transaction fee" should be translated as "Transakcia kotizo" or "Transakciaj elspezoj."
The correct translation is: Transakcia kotizo
```

```
        <source>Inputs</source>
        <translation>Enigoj</translation>
    
YES: The word "Enigoj" translates to "Mysteries" or "Riddles" in Esperanto. The correct translation for "Inputs" in the context of Bitcoin transactions is "Enigaĵoj".
NO: Enigoj
```

```
        <source>Transaction status. Hover over this field to show number of confirmations.</source>
        <translation>Transakcia stato. Ŝvebi super tiu ĉi kampo por montri la nombron de konfirmoj.</translation>
    
YES, The translation uses archaic Esperanto spelling ("ŝvebi", "ĉi"). The modern spelling is "sferi" and "ĉi". Additionally, "super" is not the correct preposition in this context; it should be "super" or "sur".

NO, Transaction status. Hover over this field to show number of confirmations.
```

```
        <source>This month</source>
        <translation>Ĉi-monate</translation>
    
YES: The translation is not standard Esperanto. The correct translation is "Ĉi-monate".
YES: Ĉi-monate
```

```
        <source>Send Coins</source>
        <translation>Sendi Bitmonon</translation>
    
YES: The translation of "Coins" to "Bitmonon" is not accurate. "Monero" is a cryptocurrency, but the context is Bitcoin. The correct translation for "Coins" in this context would be "Moneroj" or "Cifermoneroj".
Send Moneroj
```

```
        <source>Warning: We do not appear to fully agree with our peers! You may need to upgrade, or other nodes may need to upgrade.</source>
        <translation>Averto: ŝajne ni ne tute konsentas kun niaj samtavolanoj! Eble vi devas ĝisdatigi vian klienton, aŭ eble aliaj nodoj faru same.</translation>
    
YES: The translation of "peers" as "samtavolanoj" is not the most appropriate term in the context of Bitcoin networking. "Samuloj" or "kunuloj" are more commonly used to refer to peers in a decentralized network.
Averto: ŝajne ni ne tute konsentas kun niaj samuloj! Eble vi devas ĝisdatigi vian klienton, aŭ eble aliaj nodoj faru same.
```

```
        <source>Error initializing block database</source>
        <translation>Eraro dum pravalorizado de blokdatumbazo</translation>
    
YES: The translation uses an incorrect word for "initializing". The correct word for initializing in Esperanto is "komencanta" or "prepara". Additionally, "pravalorizado" is not a common word in Esperanto and may not be understood.

Error initializing block database
Eraro dum komencado de blokdatumbazo
```

```
        <source>Error initializing wallet database environment %s!</source>
        <translation>Eraro dum pravalorizado de monuj-datumbaza ĉirkaŭaĵo %s!</translation>
    
YES, The translation is problematic because it uses incorrect Esperanto vocabulary and grammar. The correct translation is "Eraro dum inicializado de la monujo-datumbazo ĉirkaŭaĵo %s!". The word "pravalorizado" means "pre-valued", and "ĉirkaŭaĵo" is an incorrect Esperanto word. The context of "wallet database environment" would translate to "monujo-datumbazo ĉirkaŭaĵo".

NO
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>Geneza bloko aŭ netrovita aŭ neĝusta. Ĉu eble la datadir de la reto malĝustas?</translation>
    
YES: The Esperanto translation contains several grammatical errors and awkward phrasing. The word "aŭ" should be "aŭ". The word "netrovita" is redundant with "neĝusta". The phrase "Ĉu eble la datadir de la reto malĝustas?" is grammatically incorrect and unnatural.

Here's a corrected translation:
"Malfalsiĝas aŭ mankas la geneza bloko. Ĉu la datadirektoro de la reto estas malĝusta?"
```
</details>
