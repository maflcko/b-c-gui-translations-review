# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>hr</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bhr%5D%20low%20quality)


```
        <source>Create a new address</source>
        <translation>Stvoriti  novu adresu</translation>
    
YES
There is an unnecessary space between "Stvoriti" and "novu", and the verb form should be imperative ("Stvori") instead of infinitive ("Stvoriti") to match the context.

Correct translation:
Stvori novu adresu
```

```
        <source>Show information about %1</source>
        <translation>Prikažite informacije o programu %1</translation>
    
YES
The translation adds "programu" ("program"), which is not present in the source text. The original talks about showing information about %1, which could refer to more than just a program (for example, a network or transaction).

Correct translation:
Prikaži informacije o %1
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Provjerite poruku da je potpisana s navedenom Bitcoin adresom</translation>
    
YES
The translation is inaccurate: the source refers to "messages" (plural), but the translation uses the singular "poruku". Also, "to ensure they were signed" is not precisely captured; the translation says "that it is signed", missing the verification aspect. For greater accuracy and correct pluralization:

Correct translation:
Provjerite poruke kako biste bili sigurni da su potpisane s navedenim Bitcoin adresama
```

```
        <source>Show Peers tab</source>
        <extracomment>A context menu item. The "Peers tab" is an element of the "Node window".</extracomment>
        <translation>Pokaži Peers tab </translation>
    
YES
The translation leaves "Peers tab" untranslated, which is not idiomatic in Croatian. "Peers" can be translated as "Čvorovi" or "Sudionici", and "tab" as "kartica". It also has a stray space at the end.

Correct translation:
Pokaži karticu Čvorovi
```

```
        <source>Copy bytes</source>
        <translation>Kopirajte količinu bajtova</translation>
    
YES
The translation is misleading. The English "Copy bytes" refers to copying the actual bytes (data), but the Croatian translation "Kopirajte količinu bajtova" means "Copy the amount of bytes," which wrongly suggests copying a number or quantity rather than the data itself.

Correct translation:
Kopiraj bajtove
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Kompajlirano bez mogućnosti vanjskog potpisivanje (potrebno za vanjsko potpisivanje)</translation>
    
YES
There is a grammatical error: "vanjskog potpisivanje" should be "vanjskog potpisivanja" (genitive case consistency). Also, for clarity, "mogućnosti vanjskog potpisivanja" could be better as "podrške za vanjsko potpisivanje".

Correct translation:
Kompajlirano bez podrške za vanjsko potpisivanje (potrebno za vanjsko potpisivanje)
```

```
        <source>%1 is shutting down…</source>
        <translation>%1 do zatvaranja...</translation>
    
YES
The translation "do zatvaranja..." implies "until closing..." rather than "[is] shutting down." Also, the ellipsis uses three periods instead of the correct Unicode ellipsis (as in the source, "…"). The translation should accurately reflect the continuous action.

Correct translation:
%1 se gasi…
```

```
        <source>Expert</source>
        <translation>Stručne postavke</translation>
    
YES
The translation "Stručne postavke" means "Brief settings" and does not correspond to the English term "Expert". The correct Croatian translation for "Expert" would be "Stručnjak" or, if it refers to an "Expert" mode or setting, "Napredno" or "Ekspert".

Correct translation:
Ekspert

(or if used as a label for a mode: "Napredno" or "Ekspertni način" depending on context)
```

```
        <source>Enable coin control features</source>
        <translation>Uključite postavke kontroliranja inputa</translation>
    
YES
The translation is understandable but not entirely accurate and can be improved. "Coin control" in Bitcoin context refers specifically to selecting which "coins" (unspent outputs, ili UTXOs) to spend in a transaction, not just "input control." The term "kontrola novčića" or "upravljanje novčićima" is more idiomatic in Bitcoin communities. Also, "postavke" means "settings", but the source refers to enabling features, not settings.

Correct translation:
Omogući mogućnosti kontrole novčića
```

```
        <source>Enable PSBT controls</source>
        <extracomment>An options window setting to enable PSBT controls.</extracomment>
        <translation>Uključi  PBST opcije za upravljanje</translation>
    
YES
There is a typographical error in the translation: "PBST" should be "PSBT" to accurately reflect the original term. Additionally, there is an unnecessary extra space between "Uključi" and "PBST".

Correct translation:
Uključi PSBT opcije za upravljanje
```

```
        <source>Whether to show PSBT controls.</source>
        <extracomment>Tooltip text for options window setting that enables PSBT controls.</extracomment>
        <translation>Za prikazivanje PSBT opcija za upravaljanje. </translation>
    
YES
There is a typo in the word "upravljanje" (written as "upravaljanje"). Also, the translation could be more concise and natural. The extra space before the period should be removed.

Correct translation:
Za prikazivanje PSBT kontrola.
```

```
        <source>Used for reaching peers via:</source>
        <translation>Korišten za dohvaćanje klijenata preko:</translation>
    
YES
The word "peers" in the Bitcoin context means "čvorovi" or "peerovi" (nodes/peers) rather than "klijenati" (clients), which is a misinterpretation in Bitcoin networking.

Correct translation:
Korišten za dohvaćanje čvorova preko:
```

```
        <source>Compiled without external signing support (required for external signing)</source>
        <extracomment>"External signing" means using devices such as hardware wallets.</extracomment>
        <translation>Kompajlirano bez mogućnosti vanjskog potpisivanje (potrebno za vanjsko potpisivanje)</translation>
    
YES
There is a grammatical error: "vanjskog potpisivanje" should be "vanjskog potpisivanja" (genitive case consistency). Also, for clarity, "mogućnosti vanjskog potpisivanja" could be better as "podrške za vanjsko potpisivanje".

Correct translation:
Kompajlirano bez podrške za vanjsko potpisivanje (potrebno za vanjsko potpisivanje)
```

```
        <source>Select a peer to view detailed information.</source>
        <translation>Odaberite klijent kako biste vidjeli detaljne informacije.</translation>
    
YES
The translation uses "klijent" (client) instead of "peer". In the Bitcoin context, "peer" should be translated as "peer" or "čvor" (node), not "klijent". Also, "kako biste" can simply be "za prikaz".

Correct translation:
Odaberite peer za prikaz detaljnih informacija.
or
Odaberite čvor za prikaz detaljnih informacija.
```

```
        <source>Outbound Manual: added using RPC %1 or %2/%3 configuration options</source>
        <extracomment>Explanatory text for an outbound peer connection that was established manually through one of several methods. The numbered arguments are stand-ins for the methods available to establish manual connections.</extracomment>
        <translation>Priručnik za izlazeće (?): dodano koristeći RPC %1 ili %2/%3 konfiguracijske opcije</translation>
    
YES
The translation is inaccurate and awkward. "Priručnik za izlazeće (?)" incorrectly renders "Outbound Manual"—it suggests something like "Manual for outgoing (?),” which does not fit the context. The correct translation should capture the notion that the outbound connection was manually added, not refer to a manual (booklet).

Correct translation:
Izlazna veza (ručno): dodano korištenjem RPC %1 ili %2/%3 konfiguracijskih opcija
```

```
        <source>no high bandwidth relay selected</source>
        <translation>brzopodatkovni prijenos nije odabran</translation>
    
YES
The translation is inaccurate. "brzopodatkovni prijenos nije odabran" means "high data transfer is not selected," which does not reflect the original context regarding selecting a high bandwidth relay. 

Correct translation:
"Nije odabran relej s velikom propusnošću"
```

```
        <source>Ban for</source>
        <translation>Zabranite za</translation>
    
YES
The translation "Zabranite za" is not idiomatic and does not accurately convey "Ban for" in Croatian. It should use a form that matches context, e.g., "Zabrana na" (if referring to duration, e.g., "Ban for 24 hours" → "Zabrana na 24 sata").

Correct translation:
Zabrana na
```

```
        <source>Custom change address</source>
        <translation>Zadana adresa u koju će ostatak biti poslan</translation>
    
YES
The translation is understandable, but it is not accurate. The English phrase "Custom change address" refers specifically to a user-specified "change address" in the context of Bitcoin. The provided translation ("Zadana adresa u koju će ostatak biti poslan") expands the meaning and does not explicitly mention that it's a change address, which could confuse users familiar with the term.

Correct translation:
Prilagođena adresa za ostatak
```

```
        <source>Send to multiple recipients at once</source>
        <translation>Pošalji novce većem broju primatelja u jednoj transakciji</translation>
    
YES
The translation adds extra information ("u jednoj transakciji" meaning "in one transaction") that is not present in the source. Also, "novce" ("money") is implied but not explicit in the source.

Correct translation:
Pošalji više primatelja odjednom
```

```
        <source>Copy bytes</source>
        <translation>Kopirajte količinu bajtova</translation>
    
YES
The translation is misleading. The English "Copy bytes" refers to copying the actual bytes (data), but the Croatian translation "Kopirajte količinu bajtova" means "Copy the amount of bytes," which wrongly suggests copying a number or quantity rather than the data itself.

Correct translation:
Kopiraj bajtove
```

```
        <source>Create Unsigned</source>
        <translation>Create nije potpisan</translation>
    
YES
The translation is incorrect. "Create nije potpisan" is a literal mix of English and Croatian and does not make sense in Croatian. The correct translation should be: 

Kreiraj nepotpisano

Or if a noun is expected (e.g., "Unsigned"), it could be:

Kreiraj nepotpisani

But "Kreiraj nepotpisano" is usually the most appropriate for this context.
```

```
        <source>Please, review your transaction proposal. This will produce a Partially Signed Bitcoin Transaction (PSBT) which you can save or copy and then sign with e.g. an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can only create a PSBT. This string is displayed when private keys are disabled and an external signer is not available.</extracomment>
        <translation>Molimo pregledajte svoj prijedlog transakcije. Ovo će stvoriti djelomično potpisanu Bitcoin transakciju (PBST) koju možete spremiti ili kopirati i zatim potpisati sa npr. novčanikom %1 koji nije povezan s mrežom ili sa PSBT kompatibilnim hardverskim novčanikom.</translation>
    
YES
There is a typographical error: "PBST" should be "PSBT". Additionally, "sa npr." would be better as "npr. s". The phrase "novčanikom %1 koji nije povezan s mrežom" translates to "a %1 wallet that is not connected to the network", which is a correct interpretation of "an offline %1 wallet", but a more faithful translation would be "offline novčanikom %1". Also, PSBT-compatible should include a hyphen: "PSBT-kompatibilnim".

Correct translation:
Molimo, pregledajte svoj prijedlog transakcije. Ovo će stvoriti djelomično potpisanu Bitcoin transakciju (PSBT) koju možete spremiti ili kopirati, a zatim potpisati npr. offline novčanikom %1 ili PSBT-kompatibilnim hardverskim novčanikom.
```

```
        <source>Please, review your transaction. You can create and send this transaction or create a Partially Signed Bitcoin Transaction (PSBT), which you can save or copy and then sign with, e.g., an offline %1 wallet, or a PSBT-compatible hardware wallet.</source>
        <extracomment>Text to inform a user attempting to create a transaction of their current options. At this stage, a user can send their transaction or create a PSBT. This string is displayed when both private keys and PSBT controls are enabled.</extracomment>
        <translation>Molimo pregledajte svoju transakciju. Možete kreirarti i poslati ovu transakciju ili kreirati djelomično potpisanu Bitcoin transakciju (PBST) koju možete spremiti ili kopirati i zatim potpisati sa npr. novčanikom %1 koji nije povezan s mrežom ili sa PSBT kompatibilnim hardverskim novčanikom.</translation>
    
YES
There are a few issues:
1. Typo: "kreirarti" should be "kreirati".
2. Abbreviation error: should be "PSBT", not "PBST" — the original uses "PSBT".
3. Style: "sa npr. novčanikom %1 koji nije povezan s mrežom" is fine, but "offline novčanikom %1" is clearer for "offline %1 wallet".
4. "sa PSBT kompatibilnim hardverskim novčanikom" should be "PSBT-kompatibilnim hardverskim novčanikom".

Correct translation:
Molimo pregledajte svoju transakciju. Možete kreirati i poslati ovu transakciju ili kreirati djelomično potpisanu Bitcoin transakciju (PSBT), koju možete spremiti ili kopirati i zatim potpisati, npr. s offline novčanikom %1 ili s PSBT-kompatibilnim hardverskim novčanikom.
```

```
        <source>Transaction creation failed!</source>
        <translation>Neuspješno stvorenje transakcije!</translation>
    
YES
The translation is understandable but is not idiomatic Croatian. "Neuspješno stvorenje" is awkward and not correct; the noun "stvorenje" means "creature". A more natural translation would be:

Transakcija nije uspjela!
or
Stvaranje transakcije nije uspjelo!

Correct translation:
Stvaranje transakcije nije uspjelo!
```

```
        <source>conflicted with a transaction with %1 confirmations</source>
        <extracomment>Text explaining the current status of a transaction, shown in the status field of the details window for this transaction. This status represents an unconfirmed transaction that conflicts with a confirmed transaction.</extracomment>
        <translation>subokljen s transakcijom broja potvrde %1</translation>
    
YES
The translation is problematic. The word "subokljen" is incorrect in Croatian; likely a typo of "sukobljen" (conflicted). Additionally, "broja potvrde %1" is an incorrect structure; it should reflect "with %1 confirmations." A correct and natural translation would be:

Correct translation:
Sukobljen s transakcijom koja ima %1 potvrda
```

```
        <source>Transaction status. Hover over this field to show number of confirmations.</source>
        <translation>Status transakcije</translation>
    
YES
The translation is incomplete; it only translates "Transaction status" and omits "Hover over this field to show number of confirmations." The user would miss important information.

Correct translation:
Status transakcije. Zadržite pokazivač miša iznad ovog polja kako biste prikazali broj potvrda.
```

```
        <source>No wallet has been loaded.
Go to File &gt; Open Wallet to load a wallet.
- OR -</source>
        <translation>Nijedan novčanik nije učitan.
Idi na Datoteka &gt;  Otvori novčanik za učitanje novčanika.
- ILI -</translation>
    
YES
There is an unnecessary double space after "&gt;" and the phrase "za učitanje novčanika" is awkward; "kako biste učitali novčanik" would be more natural. Also, "ILI" is a valid alternative for "- OR -" in Croatian.

Correct translation:
Nijedan novčanik nije učitan.
Idi na Datoteka &gt; Otvori novčanik kako biste učitali novčanik.
- ILI -
```

```
        <source>%s corrupt. Try using the wallet tool bitcoin-wallet to salvage or restoring a backup.</source>
        <translation>%s korumpirano. Pokušajte koristiti bitcoin-wallet alat za novčanike kako biste ga spasili ili pokrenuti sigurnosnu kopiju.</translation>
    
YES  
The translation has some issues:
1. The phrase "spasili ili pokrenuti sigurnosnu kopiju" is incorrect. "Pokrenuti sigurnosnu kopiju" doesn't make sense in Croatian; the intended meaning is to restore from a backup, not to start a backup.
2. "bitcoin-wallet alat za novčanike" is a confusing expression. It would be clearer as simply "alat bitcoin-wallet" or "alat bitcoin-wallet za oporavak novčanika".
3. The format specifier "%s" is carried over correctly.

Correct translation:  
%s je oštećen. Pokušajte koristiti alat bitcoin-wallet za spašavanje ili vratite iz sigurnosne kopije.
```

```
        <source>File %s already exists. If you are sure this is what you want, move it out of the way first.</source>
        <translation>Datoteka %s već postoji. Ako ste sigurni da ovo želite, prvo ju maknite, </translation>
    
YES
The translation is incomplete and ends with a comma, leaving the sentence unfinished. Additionally, the pronoun "ju" is correct for "datoteka" (feminine), but the sentence should not end with a comma.

Correct translation:
Datoteka %s već postoji. Ako ste sigurni da je to ono što želite, najprije je premjestite.
```

```
        <source>No dump file provided. To use createfromdump, -dumpfile=&lt;filename&gt; must be provided.</source>
        <translation>Dump datoteka nije automatski dostupna. Kako biste koristili createfromdump, -dumpfile=&lt;filename&gt; mora biti osiguran. </translation>
    
YES
The translation is understandable but has issues:
1. The English "No dump file provided." is translated as "Dump datoteka nije automatski dostupna," which changes the meaning; it should directly state that no dump file was provided, not that it's "not automatically available."
2. The English "must be provided" is translated as "mora biti osiguran," which is less idiomatic than "mora biti naveden."
3. There is an unnecessary space before the closing tag.

Correct translation:
Nije navedena dump datoteka. Da biste koristili createfromdump, morate navesti -dumpfile=&lt;filename&gt;.
```

```
        <source>No wallet file format provided. To use createfromdump, -format=&lt;format&gt; must be provided.</source>
        <translation>Format datoteke novčanika nije dostupan. Kako biste koristili reatefromdump, -format=&lt;format&gt; mora biti osiguran.</translation>
    
YES
There are two issues:
1. There is a typo: "reatefromdump" should be "createfromdump".
2. The word "osiguran" is not the best choice; "naveden" (provided/specified) would be more appropriate.

Correct translation:
Format datoteke novčanika nije naveden. Da biste koristili createfromdump, morate navesti -format=&lt;format&gt;.
```

```
        <source>Error: Couldn't create cursor into database</source>
        <translation>Greška: Nije moguće kreirati cursor u batu podataka</translation>
    
YES
There is an error in the translation: "cursor" is left untranslated, and "batu podataka" is incorrect—it should be "baz u podataka". The correct translation of "cursor" would be "kursor" or "pokazivač".

Correct translation:
Greška: Nije moguće kreirati kursor u bazi podataka
```

```
        <source>Pruning blockstore…</source>
        <translation>Pruning blockstore-a...</translation>
    
YES
The translation uses an English loanword ("Pruning") instead of the correct Croatian term, and the ellipsis should be three dots (as in original), but using the Croatian ellipsis character (…) is also acceptable. However, "blockstore-a" is somewhat awkward; a better translation would Croatianize both terms or at least "pruning".

Correct translation:
Smanjujem spremište blokova...
or more literally,
Obrezujem spremište blokova...
or, if you want to be more technical,
Prerađujem spremište blokova...

Any of the above would be clearer and better localized than retaining English terms.
```

```
        <source>The transaction amount is too small to pay the fee</source>
        <translation>Transakcijiski iznos je premalen da plati naknadu</translation>
    
YES
The word "Transakcijiski" is incorrect; the correct adjective form in Croatian is "Transakcijski". Furthermore, "da plati naknadu" sounds awkward. A more natural phrasing would be "za plaćanje naknade".

Correct translation:
Transakcijski iznos je premalen za plaćanje naknade
```

```
        <source>Transaction needs a change address, but we can't generate it.</source>
        <translation>Transakciji je potrebna change adresa, ali ju ne možemo generirati.</translation>
    
YES
The term "change adresa" uses the English word "change" instead of its proper Croatian equivalent. The correct translation for "change address" in the Bitcoin context is "adresa za ostatak" or "adresa za povrat ostatka".

Correct translation:
Transakciji je potrebna adresa za ostatak, ali ju ne možemo generirati.
```

```
        <source>Unknown new rules activated (versionbit %i)</source>
        <translation> Nepoznata nova pravila aktivirana (versionbit %i)</translation>
    
YES
There is an unwanted leading space before the translation and an unnecessary trailing space at the end. Otherwise, the translation is accurate and correct.

Correct translation:
Nepoznata nova pravila aktivirana (versionbit %i)
```

```
        <source>Wallet needed to be rewritten: restart %s to complete</source>
        <translation>Novčanik je trebao prepravak: ponovo pokrenite %s</translation>
    
YES
The translation omits the "to complete" part of the source, which indicates that the restart is needed to finish the rewriting process.

Correct translation:
Novčanik je trebao biti prepravljen: za dovršetak ponovo pokrenite %s
```

```
        <source>Settings file could not be written</source>
        <translation>Datoteka postavke se ne može mijenjati</translation>
    
YES
The translation is inaccurate. The source says the "settings file could not be written," meaning the file could not be saved or written to. The translation "Datoteka postavke se ne može mijenjati" means "Settings file cannot be changed," which is not precise and omits the concept of a failed write operation.

Correct translation:
Datoteku s postavkama nije moguće zapisati
```
</details>

Number of issues: 38.
