# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>ro</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bro%5D%20low%20quality)


```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>Introduceţi vechea şi noua parolă pentru portofel.
 </translation>
    
YES. The translation contains trailing whitespace.
Introduceţi vechea şi noua parolă pentru portofel.
```

```
        <source>A fatal error occurred. %1 can no longer continue safely and will quit.</source>
        <translation>A apărut o eroare fatală.%1 nu mai poate continua în siguranță și va ieși din program. </translation>
    
YES: The translation includes an unnecessary space before the period at the end of the sentence.
A apărut o eroare fatală. %1 nu mai poate continua în siguranță și va ieși din program.
```

```
        <source>Do you want to reset settings to default values, or to abort without making changes?</source>
        <extracomment>Explanatory text shown on startup when the settings file cannot be read. Prompts user to make a choice between resetting or aborting.</extracomment>
        <translation>Vrei să resetezi opțiunile la valorile predeterminate sau sa abordezi fără a face schimbări?</translation>
    
YES, the translation is problematic due to the use of "sa abordezi" which translates to "to approach" or "to tackle", instead of "to abort". The correct translation for "abort" in this context would be "anulezi". Also, there is a missing space before "fără".

NO, Vrei să resetezi opțiunile la valorile predeterminate sau să anulezi fără a face schimbări?
```

```
        <source>%1 d</source>
        <translation>%1 z</translation>
    
YES: The translation uses 'z' instead of 'd' which is incorrect. The correct translation should be '%1 d'.
```

```
        <source>Sign message…</source>
        <translation>Semnați și transmiteți un mesaj...</translation>
    
YES, the translation is problematic. The source text "Sign message…" is a simple imperative, meaning to sign a message. The translation "Semnați și transmiteți un mesaj..." translates to "Sign and send a message...". The addition of "și transmiteți" (and send) is not present in the original English text and changes the meaning of the action.

NO.
```

```
        <source>Request payments (generates QR codes and bitcoin: URIs)</source>
        <translation>Cereţi plăţi (generează coduri QR şi bitcoin-uri: URls)</translation>
    
YES - The translation incorrectly translates "URIs" to "URls". The "I" should be capitalized.
Cereţi plăţi (generează coduri QR şi bitcoin: URIs)
```

```
        <source>Sending addresses</source>
        <translation>Adresele de destinatie</translation>
    
YES, the translation is problematic because it incorrectly translates "Sending addresses" to "Adresele de destinatie" which means "Destination addresses" in Romanian. The correct translation should be "Adresele de trimitere".

NO
```

```
        <source>Open a bitcoin: URI</source>
        <translation>Deschidere bitcoin: o adresa URI sau o cerere de plată</translation>
    
YES, The translation is inaccurate and misleading. The original text "Open a bitcoin: URI" implies opening a Bitcoin URI, which is a specific format for representing Bitcoin transactions and addresses. The translation "Deschidere bitcoin: o adresa URI sau o cerere de plată" (Open bitcoin: a URI address or a payment request) introduces ambiguity by suggesting it could be "a URI address" or "a payment request," which are not direct equivalents and can be confusing. A more accurate translation would focus on the action of opening a Bitcoin URI.

Correct translation: Deschide o adresă URI Bitcoin
```

```
        <source>Restore a wallet from a backup file</source>
        <extracomment>Status tip for Restore Wallet menu item</extracomment>
        <translation>Recupereaza Portofelul din fisierele rezerva</translation>
    
YES - The translation is grammatically incorrect and uses an incorrect word for "backup".

Correct translation: Recuperați un portofel dintr-un fișier de rezervă
```

```
        <source>(un)select all</source>
        <translation>(de)selectare tot</translation>
    
YES, The translation is problematic because the word "tot" is not a valid Romanian word. It should be "toate" if referring to multiple items, or "totul" if referring to a single item. Given the context of "select all", it's likely referring to multiple items.

(de)selectare toate
```

```
        <source>Copy label</source>
        <translation>Copiaza si eticheteaza</translation>
    
YES, The translation is inaccurate and the original meaning is lost. The word "label" has been translated as "si eticheteaza" which means "and labels". The word "label" in the source text is a noun, but in the translation it is used as a verb. The correct translation should be "Copiază eticheta".
Copiază eticheta
```

```
        <source>(change)</source>
        <translation>(rest)</translation>
    
YES - The translation is incorrect and problematic. In the context of Bitcoin, "change" refers to leftover Bitcoin from a transaction, not "rest" in a general sense. The correct Romanian translation for "change" in this context is "resturi" or "schimb".

(resturi)
```

```
        <source>Creating Wallet &lt;b&gt;%1&lt;/b&gt;…</source>
        <extracomment>Descriptive text of the create wallet progress window which indicates to the user which wallet is currently being created.</extracomment>
        <translation>Creeaza Protofel&lt;b&gt;%1&lt;/b&gt;</translation>
    
YES: The translation uses "Protofel" which is not a standard Romanian word. The correct translation for "Wallet" in this context is "Portofel".
Creează Portofel <b>%1</b>…
```

```
        <source>Reverting this setting requires re-downloading the entire blockchain. It is faster to download the full chain first and prune it later. Disables some advanced features.</source>
        <translation>Revenirea la această setare necesită re-descărcarea întregului blockchain. Este mai rapid să descărcați mai întâi rețeaua complet și să o fragmentați  mai târziu. Dezactivează unele funcții avansate.</translation>
    
YES - The word "fragmentați" translates to "fragment" or "shatter", which is not the correct term for pruning a blockchain. The correct term in Romanian for pruning a blockchain is "a elimina date inutile" or simply "a curăța".

Correct translation: Revenirea la această setare necesită re-descărcarea întregului blockchain. Este mai rapid să descărcați mai întâi rețeaua complet și să o curățați mai târziu. Dezactivează unele funcții avansate.
```

```
        <source>Open bitcoin URI</source>
        <translation>DeschidețI Bitcoin URI</translation>
    
YES - The Romanian translation uses an archaic and overly formal conjugation for "open" ("DeschidețI" instead of "Deschideți"). Additionally, the capitalization of "Bitcoin" is inconsistent with common Romanian usage in this context. The correct translation should be "Deschideți URI Bitcoin".

NO
```

```
        <source>Enabling pruning significantly reduces the disk space required to store transactions. All blocks are still fully validated. Reverting this setting requires re-downloading the entire blockchain.</source>
        <translation>A activa "pruning" reduce signifiant spațiul pe disk pentru a stoca tranzacțiile.</translation>
    
YES - The translation is incomplete. The latter part of the sentence is missing.
A activa "pruning" reduce semnificativ spațiul pe disk necesar pentru stocarea tranzacțiilor. Toate blocurile sunt încă validate complet. Revenirea la această setare necesită descărcarea completă a blockchain-ului.
```

```
        <source>Unable to calculate transaction fee or total transaction amount.</source>
        <translation>Nu s-a putut calcula comisionul de tranzactie sau suma totala al tranzactiei.</translation>
    
YES - The translation uses "al tranzactiei" which is grammatically incorrect. The correct translation would be "a tranzacției".
Nu s-a putut calcula comisionul de tranzacție sau suma totală a tranzacției.
```

```
        <source>Datadir</source>
        <translation>Dirdate</translation>
    
YES, Dirdate is not a real word in Romanian. The correct translation should be "Director de date".
Director de date
```

```
        <source>Ctrl+I</source>
        <translation>Ctrl+l</translation>
    
YES, The translation is problematic. The letter 'I' in the source text has been mistranslated as a lowercase 'l' in the target text. This could cause confusion for users trying to use the keyboard shortcut.

Correct translation: Ctrl+I
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
    
YES: The translation has a missing space before the first placeholder (%1).
Bine ai venit la consola RPC %1.
Folosește săgețile sus și jos pentru a naviga istoricul, iar %2 pentru a curăța ecranul.
Folosește %3 și %4 pentru a crește sau scădea dimensiunea textului.
Tastează %5 pentru o listă a comenzilor disponibile.
Pentru mai multe informații privind folosirea consolei, tastează %6.

%7ATENȚIE: Scammerii au fost activi, cerându-le utilizatorilor să tasteze anumite comenzi, furându-le date din portofel. Nu folosi consola fără a înțelege complet ramificațiile unei comenzi. %8
```

```
        <source>Copy URI</source>
        <translation>Copiază URl</translation>
    
YES - The translation incorrectly uses "URl" instead of "URI". The correct translation is "Copiază URI".
```

```
        <source>Copy label</source>
        <translation>Copiaza si eticheteaza</translation>
    
YES, The translation is inaccurate and the original meaning is lost. The word "label" has been translated as "si eticheteaza" which means "and labels". The word "label" in the source text is a noun, but in the translation it is used as a verb. The correct translation should be "Copiază eticheta".
Copiază eticheta
```

```
        <source>Copy message</source>
        <translation>Copie și mesaj</translation>
    
YES, the translation is incorrect. The English "Copy message" implies copying the message content itself, whereas the Romanian translation "Copie și mesaj" means "Copy and message", which is grammatically incorrect and nonsensical in this context.

NO
```

```
        <source>Copy URI</source>
        <translation>Copiază URl</translation>
    
YES - The translation incorrectly uses "URl" instead of "URI". The correct translation is "Copiază URI".
```

```
        <source>Send</source>
        <translation>Trimis</translation>
    
YES
The translation is incorrect. "Send" is a verb, and the Romanian translation "Trimis" is a past participle of the verb "a trimite" (to send). The correct translation for the verb "Send" in this context would be "Trimite".

Trimite
```

```
        <source>Enter the receiver's address, message (ensure you copy line breaks, spaces, tabs, etc. exactly) and signature below to verify the message. Be careful not to read more into the signature than what is in the signed message itself, to avoid being tricked by a man-in-the-middle attack. Note that this only proves the signing party receives with the address, it cannot prove sendership of any transaction!</source>
        <translation>Introduceţi adresa de semnatură, mesajul (asiguraţi-vă că aţi copiat spaţiile, taburile etc. exact) şi semnatura dedesubt pentru a verifica mesajul. Aveţi grijă să nu citiţi mai mult în semnatură decît mesajul în sine, pentru a evita să fiţi păcăliţi de un atac de tip man-in-the-middle. De notat ca aceasta dovedeste doar ca semnatarul primeste odata cu adresa, nu dovedesta insa trimiterea vreunei tranzactii.</translation>
    
YES, The Romanian translation incorrectly translates "receiver's address" as "adresa de semnatură" (signature address) instead of "adresa destinatarului" (receiver's address). The word "signature" in the source text refers to the digital signature used to verify the message, not the address itself.

Correct translation: Introduceţi adresa destinatarului, mesajul (asiguraţi-vă că aţi copiat spaţiile, taburile etc. exact) şi semnatura dedesubt pentru a verifica mesajul. Aveţi grijă să nu citiţi mai mult în semnatură decît mesajul în sine, pentru a evita să fiţi păcăliţi de un atac de tip man-in-the-middle. De notat ca aceasta dovedeste doar ca semnatarul primeste odata cu adresa, nu dovedesta insa trimiterea vreunei tranzactii.
```

```
        <source>The Bitcoin address the message was signed with</source>
        <translation>Introduceţi o adresă Bitcoin</translation>
    
YES - The translation is incorrect. The English text asks for "The Bitcoin address the message was signed with", while the Romanian translation asks to "Introduceţi o adresă Bitcoin" which means "Enter a Bitcoin address". There is also a formatting issue as the Romanian translation misses the word "address" at the end.

The correct translation should be: "Adresa Bitcoin cu care a fost semnat mesajul"
```

```
        <source>Reset all verify message fields</source>
        <translation>Resetează toate cîmpurile mesajelor semnate</translation>
    
YES - The translation is mostly accurate, but the Romanian word "câmpurile" (fields) is missing the diacritic over the 'a'.

Resetează toate câmpurile mesajelor semnate
```

```
        <source>The signature did not match the message digest.</source>
        <translation>Semnatura nu se potriveşte cu mesajul.</translation>
    
YES, The translation is inaccurate. The word "digest" was translated as "mesajul", which means "the message". The correct translation should be "rezumatul mesajului" or "digestul mesajului".
Semnatura nu s-a potrivit cu rezumatul mesajului.
```

```
        <source>Generated coins must mature %1 blocks before they can be spent. When you generated this block, it was broadcast to the network to be added to the block chain. If it fails to get into the chain, its state will change to "not accepted" and it won't be spendable. This may occasionally happen if another node generates a block within a few seconds of yours.</source>
        <translation>Monedele generate se pot cheltui doar dupa inca %1 blocuri.  După ce a fost generat, s-a propagat în reţea, urmând să fie adăugat in blockchain.  Dacă nu poate fi inclus in lanţ, starea sa va deveni "neacceptat" si nu va putea fi folosit la tranzacţii.  Acest fenomen se întâmplă atunci cand un alt nod a generat un bloc la o diferenţa de câteva secunde.</translation>
    
YES: The translation has a grammatical error in the second sentence. It should be "După ce a fost generat, a fost propagat în reţea, urmând să fie adăugat în blockchain." instead of "După ce a fost generat, s-a propagat în reţea, urmând să fie adăugat in blockchain.".
Monedele generate se pot cheltui doar după încă %1 blocuri. După ce a fost generat, a fost propagat în reţea, urmând să fie adăugat în blockchain. Dacă nu poate fi inclus în lanţ, starea sa va deveni "neacceptat" şi nu va putea fi folosit la tranzacţii. Acest fenomen se întâmplă atunci când un alt nod a generat un bloc la o diferenţă de câteva secunde.
```

```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Indiferent dacă sau nu o adresa doar-suăpraveghere este implicată în această tranzacţie.</translation>
    
YES, the translation contains an erroneous word ("suăpraveghere" should be "supraveghere").
Indiferent dacă o adresă doar de supraveghere este implicată în această tranzacție.
```

```
        <source>User-defined intent/purpose of the transaction.</source>
        <translation>Intentie/scop al tranzactie definit de user.</translation>
    
YES: The Romanian translation uses awkward phrasing and an incorrect grammatical structure. The noun "scop" (purpose) should not be preceded by "al tranzactie" (of the transaction). Instead, it should be "al tranzacției" (of the transaction) or "al acestei tranzacții" (of this transaction). Also, "definit de user" is a direct translation of "defined by user" but sounds unnatural in Romanian. A more natural phrasing would be "definit de către utilizator" or "stabilit de utilizator".

Correct translation: Intenția/scopul tranzacției definit de utilizator.
```

```
        <source>Copy label</source>
        <translation>Copiaza si eticheteaza</translation>
    
YES, The translation is inaccurate and the original meaning is lost. The word "label" has been translated as "si eticheteaza" which means "and labels". The word "label" in the source text is a noun, but in the translation it is used as a verb. The correct translation should be "Copiază eticheta".
Copiază eticheta
```

```
        <source>Error reading %s! Transaction data may be missing or incorrect. Rescanning wallet.</source>
        <translation>Error citind %s! Data tranzacțieii poate fi lipsă sau incorectă. Rescanând portofel.</translation>
    
YES, the translation uses a direct translation of "wallet" as "portofel" which is not the common term used in Romanian Bitcoin community. The correct term is "portofel digital" or "portofel Bitcoin".

Error citind %s! Data tranzacției poate fi lipsă sau incorectă. Rescanând portofelul digital.
```

```
        <source>Prune: last wallet synchronisation goes beyond pruned data. You need to -reindex (download the whole blockchain again in case of pruned node)</source>
        <translation>Reducție: ultima sincronizare merge dincolo de datele reducției. Trebuie să faceți -reindex (să descărcați din nou întregul blockchain în cazul unui nod redus)</translation>
    
YES: The term "reducție" is a literal translation of "prune" but it is not the correct term in the context of Bitcoin. The correct term in Romanian for this context is "pruning" or "eliminare".

NO
```

```
        <source>Wallet created successfully. The legacy wallet type is being deprecated and support for creating and opening legacy wallets will be removed in the future.</source>
        <translation>Portofel crreat cu succes. Tipul legacy de portofel va fi deprecat iar suportul pentru crearea și deschiderea portofelelor legacy va fi eliminat în viitor.</translation>
    
YES, The word "crreat" is misspelled and should be "creat".
Portofel creat cu succes. Tipul legacy de portofel va fi deprecat iar suportul pentru crearea și deschiderea portofelelor legacy va fi eliminat în viitor.
```

```
        <source>Failed to verify database</source>
        <translation>Verificarea datei de baze a eșuat</translation>
    
YES, the translation is problematic because it is inaccurate and nonsensical. The Romanian word "datei" should be "bazei de date". Additionally, the phrase "Verificarea datei de baze a eșuat" is grammatically incorrect and does not convey the intended meaning of "Failed to verify database".

A more accurate and natural translation would be:

"Verificarea bazei de date a eșuat"
```

```
        <source>Incorrect or no genesis block found. Wrong datadir for network?</source>
        <translation>Incorect sau nici un bloc de geneza găsit. Directorul de retea greşit?</translation>
    
YES, The translation contains a spelling error and a grammatical error. The word "Incorect" should be "Incorect" and "directorul de retea greşit" should be "directorul de date al rețelei greșit".

NO
```
</details>
