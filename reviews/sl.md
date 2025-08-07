# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sl</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsl%5D%20low%20quality)


```
        <source>Enter the new passphrase for the wallet.&lt;br/&gt;Please use a passphrase of &lt;b&gt;ten or more random characters&lt;/b&gt;, or &lt;b&gt;eight or more words&lt;/b&gt;.</source>
        <translation>Vnesite novo geslo za denarnico. &lt;br/&gt;Prosimo, uporabite geslo z vsaj &lt;b&gt;10 ali več naključnimi simboli&lt;/b&gt; ali vsaj osmimi besedami.&lt;b&gt;</translation>
    
YES
The translation is mostly accurate but contains two issues:
1. The closing <b> tag for "osmemi besedami" is missing, leading to potential formatting issues.
2. There's a small inconsistency in format for "10 ali več" ("ten or more"); for consistency with the rest, it should use "desetimi znaki ali več".

Correct translation:
Vnesite novo geslo za denarnico.&lt;br/&gt;Prosimo, uporabite geslo z &lt;b&gt;desetimi ali več naključnimi znaki&lt;/b&gt; ali z &lt;b&gt;osmimi ali več besedami&lt;/b&gt;.

Explanation:
- Both bold tags should be properly closed.
- Used the spelling out for "ten" as in the original English.
- Used "znaki" for "characters" (more idiomatic), and "besedami" for "words".
```

```
        <source>Verify message…</source>
        <translation>Preveri podpis...</translation>
    
YES
The English source "Verify message…" is translated as "Preveri podpis...", which means "Verify signature..." in Slovenian. The translation is inaccurate; "message" (sporočilo) and "signature" (podpis) are not the same.

Correct translation:
Preveri sporočilo…
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Preverite, če je bilo prejeto sporočilo podpisano z določenim bitcoin-naslovom.</translation>
    
YES
The translation is problematic. The source refers to verifying multiple messages and addresses in general ("messages", "Bitcoin addresses"), but the translation only refers to verifying if a received message was signed with a specific address ("prejeto sporočilo", "določenim bitcoin-naslovom"), which is not fully accurate and is overly specific.

Correct translation:
Preverite sporočila, da se prepričate, ali so bila podpisana z določenimi Bitcoin naslovi.
```

```
        <source>Synchronizing with network…</source>
        <translation>Dohitevam omrežje ...</translation>
    
YES
The Slovenian translation uses three dots and a space (" ...") instead of the ellipsis character ("…") as in the source, and there is an unnecessary space before the dots. It should mirror the source's use of the ellipsis and formatting.

Correct translation:
Sinhronizacija z omrežjem…
```

```
        <source>Quantity:</source>
        <translation>Št. vhodov:</translation>
    
YES
The translation "Št. vhodov:" means "Number of inputs:" and is not an accurate translation of "Quantity:". "Quantity" should be translated as "Količina" or "Število".

Correct translation:
Količina:
or
Število:
```

```
        <source>Received with label</source>
        <translation>Oznaka priliva</translation>
    
YES
The translation "Oznaka priliva" is not accurate. The English phrase "Received with label" refers to the label associated with a received Bitcoin transaction or address. A more accurate Slovenian translation would be "Prejeto z oznako".

Correct translation:
Prejeto z oznako
```

```
        <source>Received with address</source>
        <translation>Naslov priliva</translation>
    
YES
The translation "Naslov priliva" is not an accurate translation of "Received with address" in the context of Bitcoin. "Naslov priliva" literally means "address of inflow" and does not clearly convey that a payment was received using a specific address. The commonly used and accurate translation would be "Prejeto na naslov" or "Prejeto z naslovom," which directly means "Received at address" or "Received with address."

Correct translation:
Prejeto na naslov
```

```
        <source>External signer</source>
        <translation>Zunanji podpisni</translation>
    
YES
The translation is slightly incorrect. The word "podpisni" is not suitable; the correct term should be "podpisnik", which means "signer" in Slovenian.

Correct translation:
Zunanji podpisnik
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Prevedeno brez podpore za zunanje podpisovanje</translation>
    
YES
The translation omits the phrase "(required for external signing)", making it incomplete. The format specifier is not present, but in this source, none exist, so that's not an issue. However, the completeness of content is an issue.

Correct translation:
Prevedeno brez podpore za zunanje podpisovanje (potrebno za zunanje podpisovanje)
```

```
        <source>%1 is currently syncing.  It will download headers and blocks from peers and validate them until reaching the tip of the block chain.</source>
        <translation>%1 trenutno dohiteva omrežje. Od soležnikov bodo preneseni in preverjeni zaglavja in bloki do vrha verige.</translation>
    
YES
The translation omits some meaning and is slightly inaccurate. "trenutno dohiteva omrežje" literally means "is currently catching up the network," which is a bit awkward and could be misinterpreted. "It will download headers and blocks from peers and validate them..." is rendered awkwardly as well. Also, "do vrha verige" means "to the top of the chain" instead of "until reaching the tip of the block chain," which is understandable but could be more precise.

Correct translation:
%1 se trenutno sinhronizira. Prenesel bo zaglavja in bloke od soležnikov ter jih preveril, dokler ne doseže vrha verige blokov.
```

```
        <source>Enable PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Omogoči nastavitve DPBT</translation>
    
YES
The translation is problematic: "DPBT" is not a recognized abbreviation in Slovenian for PSBT (Partially Signed Bitcoin Transaction). The standard use is to keep "PSBT" as is, not to translate or localize the acronym.

Correct translation:
Omogoči kontrolnike PSBT
```

```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Ali naj se prikaže upravljanje z DPBT</translation>
    
YES
There is a typographical error in the translation: "DPBT" instead of "PSBT". Also, the translation could be a bit more explicit to match the original meaning.

Correct translation:
Ali naj se prikaže upravljanje s PSBT.

This keeps the term "PSBT" as in the original, which is a specific technical acronym.
```

```
        <source>Third-party transaction URLs</source>
        <translation>Zunanji URL-ji</translation>
    
YES
The translation "Zunanji URL-ji" merely means "External URLs" and omits the key concepts of "third-party" and "transaction". It is not an accurate translation.

Correct translation:
URL-ji tretjih oseb za transakcije
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Prevedeno brez podpore za zunanje podpisovanje</translation>
    
YES
The translation omits the phrase "(required for external signing)", making it incomplete. The format specifier is not present, but in this source, none exist, so that's not an issue. However, the completeness of content is an issue.

Correct translation:
Prevedeno brez podpore za zunanje podpisovanje (potrebno za zunanje podpisovanje)
```

```
        <source>none</source>
        <translation>jih ni</translation>
    
YES
The translation "jih ni" is informal and incomplete for "none," literally meaning "there are none." A more accurate, context-appropriate Slovenian translation for "none" is "brez," "nič," or "noben." The choice depends on the context, but "brez" (without) or "nič" (nothing/none) are standard.

Correct translation:
nič
```

```
        <source>Client will be shut down. Do you want to proceed?</source>
        <extracomment>Text asking the user to confirm if they would like to proceed with a client shutdown.</extracomment>
        <translation>Program bo zaustavljen. Želite nadaljevati z izhodom?</translation>
    
YES
The translation has a minor issue: "Program bo zaustavljen" means "The program will be stopped/shut down", which is fairly close. However, "Želite nadaljevati z izhodom?" means "Do you want to continue with the exit?", which, while understandable, does not directly mean "Do you want to proceed?". It's acceptable, but it would be clearer to more literally translate "Do you want to proceed?".

Correct translation:
Program bo zaustavljen. Ali želite nadaljevati?
```

```
        <source>own address</source>
        <translation>lasten naslov</translation>
    
YES
The translation "lasten naslov" is incorrect. The correct Slovenian translation for "own address" is "lastni naslov".

Correct translation:
lastni naslov
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Ni mogoče zagnati rokovalca plačilnih povezav tipa bitcoin:.</translation>
    
YES
The translation is mostly accurate in meaning, but the word order and punctuation are slightly awkward. The colon at the end does not correspond to the source. Also, "rokovalca plačilnih povezav tipa bitcoin" might be better phrased for clarity.

Correct translation:
Ni mogoče zagnati rokovalca za click-to-pay (bitcoin).
Or, staying closer to the source:
Ni mogoče zagnati rokovalca za bitcoin: click-to-pay.

Either is valid, but the main issue is the unnecessary colon and slightly awkward phrasing.
```

```
        <source>Outbound Address Fetch: short-lived, for soliciting addresses</source>
        <extracomment>Explanatory text for a short-lived outbound peer connection that is used to request addresses from a peer.</extracomment>
        <translation>Odhodna dostavljalka naslovov: krakoživa, zaproša za naslove</translation>
    
YES
There is a typo in the word "krakoživa", which should be "kratkoživa". The phrase "Odhodna dostavljalka naslovov" is also slightly unnatural; "Odhodna pridobitev naslovov" or "Odhodna povezava za pridobivanje naslovov" would be clearer. Also, "zaproša za naslove" should be "za pridobivanje naslovov" (for obtaining addresses), since it refers to the purpose, not just the act of "soliciting".

Correct translation:
Odhodna povezava za pridobivanje naslovov: kratkoživa, za pridobivanje naslovov
```

```
        <source>no high bandwidth relay selected</source>
        <translation>ni posredovanja na visoki pasovni širini</translation>
    
YES
The translation is inaccurate. The English sentence "no high bandwidth relay selected" should be translated to indicate that no relay with high bandwidth has been chosen/selected. The current translation "ni posredovanja na visoki pasovni širini" means "no relaying on high bandwidth," which does not convey the intended meaning.

Correct translation:
ni izbranega releja z visoko pasovno širino
```

```
        <source>Request payment to …</source>
        <translation>Zahtevaj plačilo prejmeniku ...</translation>
    
YES
The translation is inaccurate. "Prejmeniku" means "to the recipient," which is not present in the source. Also, the ellipsis character in the source is "…" (Unicode), but the translation uses three periods "...", which does not match formatting. The correct translation would simply mirror the original intent and punctuation.

Correct translation:
Zahtevaj plačilo …
```

```
        <source>Quantity:</source>
        <translation>Št. vhodov:</translation>
    
YES
The translation "Št. vhodov:" means "Number of inputs:" and is not an accurate translation of "Quantity:". "Quantity" should be translated as "Količina" or "Število".

Correct translation:
Količina:
or
Število:
```

```
        <source>PSBT saved</source>
        <extracomment>Popup message when a PSBT has been saved to a file</extracomment>
        <translation>DPBT shranjena</translation>
    
YES
The translation is problematic because "DPBT" is not the correct Slovenian abbreviation for "PSBT". "PSBT" (Partially Signed Bitcoin Transaction) is typically not translated or adapted and should remain "PSBT" in the translation. Everything else is correct.

Correct translation:
PSBT shranjena
```

```
        <source>PSBT saved to disk</source>
        <translation>DPBT shranjena na disk</translation>
    
YES
There is an error in the abbreviation: "PSBT" (Partially Signed Bitcoin Transaction) should not be translated or changed in the abbreviation. The translation uses "DPBT", which is incorrect. The rest of the phrase is otherwise accurately translated.

Correct translation:
PSBT shranjena na disk
```

```
        <source>Sign the message to prove you own this Bitcoin address</source>
        <translation>Podpišite sporočilo, da dokažete lastništvo zgornjega naslova.</translation>
    
YES
The translation is inaccurate. The original specifies "this Bitcoin address," but the translation says "lastništvo zgornjega naslova" ("ownership of the above address"), which is ambiguous, and omits "Bitcoin" ("Bitcoin naslov").

Correct translation:
Podpišite sporočilo, da dokažete, da ste lastnik tega Bitcoin naslova.
```

```
        <source>own address</source>
        <translation>lasten naslov</translation>
    
YES
The translation "lasten naslov" is incorrect. The correct Slovenian translation for "own address" is "lastni naslov".

Correct translation:
lastni naslov
```

```
        <source>PSBT file must be smaller than 100 MiB</source>
        <translation>Velikost DPBT ne sme presegati 100 MiB.</translation>
    
YES
The translation has an error: "DPBT" is not the correct Slovene equivalent for "PSBT". The abbreviation "PSBT" (Partially Signed Bitcoin Transaction) is standard and should be kept as "PSBT" in Slovenian as well. Otherwise, the rest of the translation is accurate.

Correct translation:
Velikost PSBT ne sme presegati 100 MiB.
```

```
        <source>Can't draft transaction.</source>
        <translation>Ne morem shraniti osnutka transakcije</translation>
    
YES
The translation changes the meaning of the original message. The English source means "Ni mogoče sestaviti/ustvariti osnutka transakcije," but the provided translation means "I can't save the draft transaction," which is not the same.

Correct translation:
Ni mogoče sestaviti (ali: ustvariti) osnutka transakcije.
```

```
        <source>File %s already exists. If you are sure this is what you want, move it out of the way first.</source>
        <translation>Datoteka %s že obstaja. Če stre prepričani, da to želite, obstoječo datoteko najprej odstranite oz. premaknite.</translation>
    
YES
There is a typo in the translation: "stre prepričani" should be "ste prepričani" ("stre" is incorrect in Slovenian). The phrase could also be made slightly clearer and more idiomatic.

Correct translation:
Datoteka %s že obstaja. Če ste prepričani, da to želite, obstoječo datoteko najprej odstranite ali premaknite.
```

```
        <source>Error loading %s: Wallet corrupted</source>
        <translation>Napaka pri nalaganju %s: Denarnica ovkarjena</translation>
    
YES
There is a typo in the Slovenian word for "corrupted": "ovkarjena" is incorrect. The correct word is "poškodovana".

Correct translation:
Napaka pri nalaganju %s: Denarnica poškodovana
```

```
        <source>Failed to rescan the wallet during initialization</source>
        <translation>Med inicializacijo denarnice ni bilo mogoče preveriti zgodovine (rescan failed).</translation>
    
YES
The translation is not fully accurate. The English sentence says "Failed to rescan the wallet during initialization". The Slovenian translation says "During wallet initialization, it was not possible to check history (rescan failed)." This is not fully faithful, and the addition "(rescan failed)" is unnecessary in Slovenian, and "preveriti zgodovino" does not precisely convey "rescan the wallet".

Correct translation:
Med inicializacijo denarnice ni bilo mogoče ponovno pregledati denarnice.
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s'</source>
        <translation>Neveljaven znesek za %s=&lt;amount&gt;:'%s'</translation>
    
YES
There is a minor spacing issue: there should be a space after the colon, matching the English source.

Correct translation:
Neveljaven znesek za %s=&lt;amount&gt;: '%s'
```

```
        <source>Loading P2P addresses…</source>
        <translation>Nalagam P2P naslove ...</translation>
    
YES
The Slovenian translation uses three periods "..." instead of the correct ellipsis character "…", as in the source. Also, there should be no extra spaces before the ellipsis.

Correct translation:
Nalagam P2P naslove…
```

```
        <source>Pruning blockstore…</source>
        <translation>Obrezujem ...</translation>
    
YES
The translation "Obrezujem ..." is not fully accurate. The term "blockstore" is missing from the translation, and the ellipsis "..." does not follow the source, which uses a single Unicode ellipsis character (…).

Correct translation:
Obrezujem shrambi blokov…
```
</details>

Number of issues: 34.
