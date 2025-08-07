# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ro</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bro%5D%20low%20quality)


```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>Introduceţi vechea şi noua parolă pentru portofel.
 </translation>
    
YES
There is an unwanted whitespace character at the end of the translation (a non-breaking space). Also, "Introduceţi vechea şi noua parolă pentru portofel." omits "Enter the old passphrase and new passphrase" nuance: ideally, the translation should preserve both the request to enter each passphrase and clarity.

Correct translation:
Introduceți vechea parolă și noua parolă pentru portofel.
```

```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>A apărut o eroare fatală.%1 nu mai poate continua în siguranță și va ieși din program. </translation>
    
YES
There is a missing space between the sentences: "fatală.%1" should be "fatală. %1". Additionally, there is an extra space at the end of the translation.

Correct translation:
A apărut o eroare fatală. %1 nu mai poate continua în siguranță și va ieși din program.
```

```
        <source>Do you want to reset settings to default values, or to abort without making changes?</source>
        <extracomment>Explanatory text shown on startup when the settings file cannot be read. Prompts user to make a choice between resetting or aborting.</extracomment>
        <translation>Vrei să resetezi opțiunile la valorile predeterminate sau sa abordezi fără a face schimbări?</translation>
    
YES
The word "abordezi" is incorrect in this context; it should be "abortezi" or "renunți", as "abordezi" means "to approach", while here it should be "to abort" or "give up".

Correct translation:
Vrei să resetezi opțiunile la valorile implicite sau să renunți fără a face schimbări?
```

```
        <source>%1 d</source>
        <translation>%1 z</translation>
    
YES
The translation uses "z" instead of the correct Romanian abbreviation for "days". The English "d" stands for "days" and should be translated to "zile" or abbreviated as "z" only if that's standard in Romanian. However, in Romanian date abbreviations, "z" is sometimes used for "zi" (day), but for "days" (plural) it's more standard to use "zile" or at least confirm local software conventions. If the application uses "z" consistently, it may be acceptable, but "d" should not be changed to "z" solely on an assumption.

Correct translation (most standard):
%1 z
or alternatively (fully written):
%1 zile

However, if local convention is single-letter, "z" can be accepted, but context should be checked. 

So, briefly:

The translation is potentially problematic because "z" may not be a standard plural abbreviation for "zile" in all contexts. To be fully correct:

Correct translation:
%1 zile
```

```
        <source>Sign message…</source>
        <translation>Semnați și transmiteți un mesaj...</translation>
    
YES
The translation adds "și transmiteți" ("and send"), which is not present in the original English text. The English is only "Sign message", not "Sign and send message". Also, the ellipsis (three dots) in Romanian should be consistent with the ellipsis used in English ("…", a single character, not three periods), though this is a minor issue.

Correct translation:
Semnați mesajul…
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>Cereţi plăţi (generează coduri QR şi bitcoin-uri: URls)</translation>
    
YES
The translation has a few issues:
- "bitcoin: URIs" refers to the URI scheme "bitcoin:", not "bitcoin-uri", and "URls" has a typographical error ("URls" vs "URI-uri" or "URI").
- The plural of "plată" should be "plăți", not "plăţi" (although ț and ţ are both used, the correct character is ț - Unicode U+021B).
- While "Cereți" is acceptable, "Solicită" is a more neutral imperative verb fit for a UI context.

Correct translation:
Solicită plăți (generează coduri QR și URI-uri bitcoin:)
```

```
        <source>Sending addresses</source>
        <translation>Adresele de destinatie</translation>
    
YES
The translation "Adresele de destinatie" means "Destination addresses", which is not the most accurate translation for "Sending addresses" in the context of Bitcoin. "Sending addresses" refers to the addresses from which coins are sent, not the destination.

Correct translation:
Adrese de expediere
```

```
        <source>Open a bitcoin: URI</source>
        <translation>Deschidere bitcoin: o adresa URI sau o cerere de plată</translation>
    
YES
The translation introduces extra content ("sau o cerere de plată" means "or a payment request") that is not present in the source text. Also, "Deschidere" should be "Deschide" to correctly translate "Open" in this context.

Correct translation:
Deschide un bitcoin: URI
```

```
        <source>Restore a wallet from a backup file</source>
        <extracomment>Status tip for Restore Wallet menu item</extracomment>
        <translation>Recupereaza Portofelul din fisierele rezerva</translation>
    
YES
The Romanian translation contains some errors:
- "Recupereaza" should have an accent: "Recuperează"
- "Portofelul" should be lowercase as in the source: "portofel"
- "fisierele rezerva" sounds odd; it should be "fișierul de backup" or "fișier de rezervă"
- The translation shifts from singular (wallet) to plural (files) incorrectly.

Correct translation:
Recuperează un portofel dintr-un fișier de backup
```

```
        <source>(un)select all</source>
        <translation>(de)selectare tot</translation>
    
YES
The translation is incorrect. The English phrase "(un)select all" should be accurately translated into Romanian, but "(de)selectare tot" is awkward and not idiomatic. A correct translation would be:

Selectează/deselectează tot

Alternatively, in concise UI language:

Selectează/deselectează toate

This uses the imperative forms appropriate for buttons or actions.
```

```
        <source>Copy label</source>
        <translation>Copiaza si eticheteaza</translation>
    
YES
The translation is inaccurate. "Copy label" means to copy the label itself, not to copy and label. The correct Romanian translation should be:

Copiază eticheta
```

```
        <source>(change)</source>
        <translation>(rest)</translation>
    
YES
The Romanian translation uses "rest", which, while sometimes used informally in the context of financial transactions to mean "change", it is slightly ambiguous and less formal/clear. In the context of Bitcoin and technical terminology, "schimb" or "monedă de schimb" could be used, but more typically, "rest" is understood by Romanian speakers in this context.

However, if following standard translations in Romanian Bitcoin interfaces, "rest" is widely accepted and not problematic. For clarity and formality, it could be improved to "schimb" or "suma de rest", but strictly speaking, it is not erroneous nor spam.

So, the answer is:

NO
```

```
        <source>Creating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the create wallet progress window which indicates to the user which wallet is currently being created.</extracomment>
        <translation>Creeaza Protofel&lt;b&gt;%1&lt;/b&gt;</translation>
    
YES
There are issues with this translation:
1. "Creeaza" should be "Creează" (diacritic missing).
2. "Protofel" is a typo; the correct word is "Portofel".
3. The ellipsis at the end of the sentence ("…") is missing in the translation.
4. There should be a space between "Portofel" and "<b>".

Correct translation:
Creează portofelul &lt;b&gt;%1&lt;/b&gt;…
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain. It is faster to download the full chain first and prune it later. Disables some advanced features.</source>
        <translation>Revenirea la această setare necesită re-descărcarea întregului blockchain. Este mai rapid să descărcați mai întâi rețeaua complet și să o fragmentați  mai târziu. Dezactivează unele funcții avansate.</translation>
    
YES
There are two issues:
1. "să descărcați mai întâi rețeaua complet" should be "să descărcați mai întâi lanțul complet", as "blockchain" is usually translated as "lanțul de blocuri" or just "lanțul".
2. There is an extra space before "mai târziu" ("fragmentați  mai târziu").

Correct translation:
Revenirea la această setare necesită re-descărcarea întregului blockchain. Este mai rapid să descărcați mai întâi lanțul complet și să îl fragmentați mai târziu. Dezactivează unele funcții avansate.
```

```
        <source>Open bitcoin URI</source>
        <translation>DeschidețI Bitcoin URI</translation>
    
YES
The Romanian translation has an incorrect capitalization of "DeschidețI" (should be "Deschideți") and the phrase "Bitcoin URI" would be more natural as "URI Bitcoin".

Correct translation:
Deschideți un URI Bitcoin
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>A activa "pruning" reduce signifiant spațiul pe disk pentru a stoca tranzacțiile.</translation>
    
YES
The translation omits much of the original content, does not fully convey the meaning, and leaves out important details about full block validation and the need to re-download the blockchain if reverted. Moreover, "A activa 'pruning'" should be phrased more naturally in Romanian.

Correct translation:
Activarea modului de pruning reduce semnificativ spațiul pe disc necesar pentru stocarea tranzacțiilor. Toate blocurile sunt totuși complet validate. Revenirea la această setare necesită re-descărcarea întregului blockchain.
```

```
        <source>Unable to calculate transaction fee or total transaction amount.</source>
        <translation>Nu s-a putut calcula comisionul de tranzactie sau suma totala al tranzactiei.</translation>
    
YES
There are issues with the grammatical agreement in the Romanian translation. "tranzactie" should have the proper diacritics ("tranzacție"), and "suma totala al tranzactiei" should use the correct agreement: "suma totală a tranzacției."

Correct translation:
Nu s-a putut calcula comisionul de tranzacție sau suma totală a tranzacției.
```

```
        <source>Datadir</source>
        <translation>Dirdate</translation>
    
YES
The translation is incorrect. "Datadir" should be translated as "Director de date" or left as "Datadir" if it refers to a technical directory name. "Dirdate" does not have meaning in Romanian.

Correct translation:
Director de date
```

```
        <source>Ctrl+I</source>
        <translation>Ctrl+l</translation>
    
YES
The translation uses a lowercase 'L' (l) instead of the uppercase 'I' (I). In Romanian, shortcut keys should match the source key.

Correct translation:
Ctrl+I
```

```
        <source>Welcome to the %1 RPC console.
Use up and down arrows to navigate history, and %2 to clear screen.
Use %3 and %4 to increase or decrease the font size.
Type %5 for an overview of available commands.
For more information on using this console, type %6.

%7WARNING: Scammers have been active, telling users to type commands here, stealing their wallet contents. Do not use this console without fully understanding the ramifications of a command.%8</source>
        <extracomment>RPC console welcome message. Placeholders %7 and %8 are style tags for the warning content, and they are not space separated from the rest of the text intentionally.</extracomment>
        <translation>Bine ai venit la consola RPC %1 .
Folosește săgețile sus și jos pentru a naviga istoricul, iar %2 pentru a curăța ecranul.
Folosește %3 și %4 pentru a crește sau scădea dimensiunea textului.
Tastează %5pentru o listă a comenzilor disponibile .
Pentru mai multe informații privind folosirea consolei, tastează %6.

%7ATENȚIE: Scammerii au fost activi, cerându-le utilizatorilor să tasteze anumite comenzi, furându-le date din portofel. Nu folosi consola fără a înțelege complet ramificațiile unei comenzi. %8</translation>
    
YES
There are minor formatting and spacing errors, as well as a slight stylistic issue. Specifically:
- In "%1 .", the space should not be before the period.
- In "Tastează %5pentru o listă...", there is no space between '%5' and 'pentru'.
- In "comenzii disponibile .", the space before the period should be removed.
- In the warning text, there is a space before '%8' that should likely not be there, to preserve the intentional formatting.

Correct translation:
Bine ai venit la consola RPC %1.
Folosește săgețile sus și jos pentru a naviga istoricul, iar %2 pentru a curăța ecranul.
Folosește %3 și %4 pentru a crește sau scădea dimensiunea textului.
Tastează %5 pentru o listă a comenzilor disponibile.
Pentru mai multe informații privind folosirea consolei, tastează %6.

%7ATENȚIE: Escrocii au fost activi, cerându-le utilizatorilor să tasteze anumite comenzi, furându-le conținutul portofelului. Nu folosi consola fără a înțelege complet ramificațiile unei comenzi.%8
```

```
        <source>Copy URI</source>
        <translation>Copiază URl</translation>
    
YES
The translation has an incorrect capitalization in "URl": the 'l' should be uppercase 'L' to match 'URI'. There is also a minor terminology issue: "URI" is a technical term and should remain "URI" in Romanian rather than being adapted or partially translated.

Correct translation:
Copiază URI
```

```
        <source>Copy label</source>
        <translation>Copiaza si eticheteaza</translation>
    
YES
The translation is inaccurate. "Copy label" means to copy the label itself, not to copy and label. The correct Romanian translation should be:

Copiază eticheta
```

```
        <source>Copy message</source>
        <translation>Copie și mesaj</translation>
    
YES
The translation is incorrect. "Copie și mesaj" means "Copy and message", which is not accurate.

Correct translation:
Copiază mesajul
```

```
        <source>Copy URI</source>
        <translation>Copiază URl</translation>
    
YES
The translation has an incorrect capitalization in "URl": the 'l' should be uppercase 'L' to match 'URI'. There is also a minor terminology issue: "URI" is a technical term and should remain "URI" in Romanian rather than being adapted or partially translated.

Correct translation:
Copiază URI
```

```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Introduceţi adresa de semnatură, mesajul (asiguraţi-vă că aţi copiat spaţiile, taburile etc. exact) şi semnatura dedesubt pentru a verifica mesajul. Aveţi grijă să nu citiţi mai mult în semnatură decît mesajul în sine, pentru a evita să fiţi păcăliţi de un atac de tip man-in-the-middle. De notat ca aceasta dovedeste doar ca semnatarul primeste odata cu adresa, nu dovedesta insa trimiterea vreunei tranzactii.</translation>
    
YES
There are several issues in the translation:
1. The phrase "adresa de semnatură" is incorrect and should be "adresa destinatarului" ("receiver's address").
2. It omits "line breaks" from the list of what must be copied exactly.
3. "că aţi copiat spaţiile, taburile etc. exact" omits the specificity of including newlines, and does not mirror the English precisely.
4. Double diacritics are missing for Romanian (e.g., "semnatură" → "semnătură", "dedesubt" could be clearer as "mai jos").
5. "semnatura dedesubt" is awkward Romanian; better: "și semnătura mai jos".
6. "dovedeste" should have diacritics ("dovedește"), and "primestre" does not literally exist; it should mention "primește cu adresa".
7. "trimiterea vreunei tranzactii" should be "trimiterea vreunei tranzacții".

Correct translation:
Introduceți mai jos adresa destinatarului, mesajul (asigurați-vă că ați copiat exact toate liniuțele noi, spațiile, taburile etc.) și semnătura pentru a verifica mesajul. Aveți grijă să nu interpretați mai mult în semnătură decât ceea ce se află în mesajul semnat, pentru a evita să fiți păcăliți de un atac de tip man-in-the-middle. Rețineți că acest lucru dovedește doar că partea semnatară primește cu acea adresă, nu poate dovedi trimiterea vreunei tranzacții!
```

```
        <source>The Bitcoin address the message was signed with</source>
        <translation>Introduceţi o adresă Bitcoin</translation>
    
YES
The translation is incorrect. The source refers to "The Bitcoin address the message was signed with," while the translation says "Introduceţi o adresă Bitcoin" ("Enter a Bitcoin address"), which does not convey the original meaning.

Correct translation:
Adresa Bitcoin cu care a fost semnat mesajul
```

```
        <source>Reset all verify message fields</source>
        <translation>Resetează toate cîmpurile mesajelor semnate</translation>
    
YES
The translation changes the meaning. The source refers to "verify message fields", but the translation refers to "fields of signed messages" ("cîmpurile mesajelor semnate"). Furthermore, the correct character in modern Romanian is "î" (not "î" at the beginning, but "â" inside words, so "câmpurilor", not "cîmpurilor").

Correct translation:
Resetează toate câmpurile pentru verificarea mesajului
```

```
        <source>The signature did not match the message digest.</source>
        <translation>Semnatura nu se potriveşte cu mesajul.</translation>
    
YES
The translation is inaccurate. The English source refers to the message digest (i.e., hash of the message), not just the message. The Romanian translation omits this important term.

Correct translation:
Semnătura nu corespunde cu rezumatul (digestul) mesajului.
```

```
        <source>Generated coins must mature %1 blocks before they can be spent. When you generated this block, it was broadcast to the network to be added to the block chain. If it fails to get into the chain, its state will change to "not accepted" and it won't be spendable. This may occasionally happen if another node generates a block within a few seconds of yours.</source>
        <translation>Monedele generate se pot cheltui doar dupa inca %1 blocuri.  După ce a fost generat, s-a propagat în reţea, urmând să fie adăugat in blockchain.  Dacă nu poate fi inclus in lanţ, starea sa va deveni "neacceptat" si nu va putea fi folosit la tranzacţii.  Acest fenomen se întâmplă atunci cand un alt nod a generat un bloc la o diferenţa de câteva secunde.</translation>
    
YES
There are several issues with the translation:
- The number of required blocks to mature ("%1 blocks") should be explicitly mentioned, as in the source, not rendered vaguely as "doar dupa inca %1 blocuri" (only after another %1 blocks).
- Some content is omitted: "When you generated this block" is not translated explicitly; the translation only states "După ce a fost generat" (After it was generated), not making clear the subject "you".
- "it won't be spendable" is rendered as "nu va putea fi folosit la tranzacţii" (cannot be used for transactions), which is acceptable, but a closer equivalent for "spendable" would be better.
- The translation turns explanations into more generic phrases, losing the clarity of cause and effect from the original.
- There's stray double spacing in several places.
- Word choices such as "blockchain" vs "lanţ" should be consistent (choose either "blockchain" or "lanţ de blocuri" for the Romanian context).
- The last sentence omits “your block” (ai tău) for clarity.

Correct translation:
Monedele generate trebuie să se maturizeze timp de %1 blocuri înainte de a putea fi cheltuite. Când ai generat acest bloc, el a fost transmis în rețea pentru a fi adăugat la lanțul de blocuri. Dacă nu reușește să fie inclus în lanț, starea lui va deveni „neacceptat” și nu va putea fi cheltuit. Acest lucru se poate întâmpla uneori dacă un alt nod generează un bloc la câteva secunde după al tău.
```

```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Indiferent dacă sau nu o adresa doar-suăpraveghere este implicată în această tranzacţie.</translation>
    
YES
There are several issues in the translation:
- "adresa" should have the correct definite article and diacritics: "adresă".
- "doar-suăpraveghere" is a misspelling; it should be "doar-pentru-vizualizare" or "doar-supraveghere".
- The sentence structure is awkward: "Indiferent dacă sau nu" is not idiomatic in Romanian.
- "în această tranzacţie" is correct, but "tranzacţie" should have a 'ț' with comma, not a cedilla.

Correct translation:
Fie dacă o adresă doar-pentru-vizualizare este sau nu implicată în această tranzacție.
```

```
        <source>User-defined intent/purpose of the transaction.</source>
        <translation>Intentie/scop al tranzactie definit de user.</translation>
    
YES
There are several issues: "tranzactie" should be "tranzacție" (with diacritics), "user" should be translated to "utilizator", and the article should be correct in context ("o tranzacție"). Also, "intenție" and "scop" should be with proper diacritics.

Correct translation:
Intenție/scop al tranzacției definit de utilizator.
```

```
        <source>Copy label</source>
        <translation>Copiaza si eticheteaza</translation>
    
YES
The translation is inaccurate. "Copy label" means to copy the label itself, not to copy and label. The correct Romanian translation should be:

Copiază eticheta
```

```
        <source>Error reading %s! Transaction data may be missing or incorrect. Rescanning wallet.</source>
        <translation>Error citind %s! Data tranzacțieii poate fi lipsă sau incorectă. Rescanând portofel.</translation>
    
YES
There are minor errors: "Error citind" should be in Romanian ("Eroare la citirea"), "tranzacțieii" has a double "i" and should be "tranzacției", "data" should be capitalized only if it starts the sentence, and "Rescanând portofel." is grammatically incomplete; "Rescanez portofelul" or "Se rescanează portofelul" is correct.

Correct translation:
Eroare la citirea %s! Datele tranzacției pot lipsi sau pot fi incorecte. Se rescanează portofelul.
```

```
        <source>Wallet created successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future.</source>
        <translation>Portofel crreat cu succes. Tipul legacy de portofel va fi deprecat iar suportul pentru crearea și deschiderea portofelelor legacy va fi eliminat în viitor.</translation>
    
YES
There is a typo in the translation: "crreat" should be "creat". 

Correct translation:
Portofel creat cu succes. Tipul legacy de portofel va fi deprecat iar suportul pentru crearea și deschiderea portofelelor legacy va fi eliminat în viitor.
```

```
        <source>Failed to verify database</source>
        <translation>Verificarea datei de baze a eșuat</translation>
    
YES
There is a minor grammatical error in the Romanian translation. "datei de baze" should be "bazei de date". The correct translation is:

Verificarea bazei de date a eșuat
```
</details>

Number of issues: 35.
