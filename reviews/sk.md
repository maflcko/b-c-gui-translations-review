# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sk</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsk%5D%20low%20quality)


```
        <source>Receiving addresses - %1</source>
        <translation>Prijímajúce adresy -%1</translation>
    
YES  
There is a missing space before the format specifier %1 in the translation. The source text has a space before the dash and then the placeholder, so the translation should preserve spacing similarly.

Correct translation:  
Prijímajúce adresy - %1
```

```
        <source>IP/Netmask</source>
        <translation>IP/Maska stiete</translation>
    
YES  
The Slovak word "stiete" is incorrect in this context. The correct translation for "Netmask" in Slovak is "maska siete" (network mask), where "siete" means "of network." Also, note the spacing around the slash should be consistent; in the source, there is no space, so the translation should also not have space around the slash.

Correct translation:  
IP/Maska siete
```

```
        <source>%1 and %2</source>
        <translation>%1 a  %2</translation>
    
YES
There is an extra space before %2 in the translation. In Slovak, the conjunction "a" should not have double spaces around it—only single spaces.

Correct translation:
%1 a %2
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Proxy sú &lt;b&gt;zapnuté&lt;/b&gt;: %1</translation>
    
YES  
The adjective "zapnuté" is plural neuter or plural inanimate, but "Proxy" is singular masculine in Slovak, so it should be "zapnutý" (singular masculine) to agree with "Proxy".  

Correct translation:  
Proxy je &lt;b&gt;zapnutý&lt;/b&gt;: %1
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Ukáž %1 zoznam možných nastavení Bitcoinu pomocou príkazového riadku</translation>
    
YES  
The translation is incomplete and does not fully convey the original meaning. The source asks to show the %1 help message to get a list of possible Bitcoin command-line options. The Slovak translation says "Show %1 list of possible Bitcoin settings using the command line," which omits the concept of the help message and the purpose of obtaining the list.

Correct translation:  
Ukáž %1 pomocnú správu, aby si získal zoznam možných príkazov príkazového riadku Bitcoinu
```

```
        <source>Sent transaction</source>
        <translation>Odoslané transakcie</translation>
    
YES
The English source "Sent transaction" is singular, but the Slovak translation "Odoslané transakcie" is plural ("transactions"). The translation should be singular to match the source.

Correct translation:
Odoslaná transakcia
```

```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Vložená adresa "%1" nieje platnou adresou Bitcoin.</translation>
    
YES  
The word "nieje" is incorrect; the correct form is the two-word phrase "nie je" (with a space). Also, "Bitcoin" here should be in the genitive case as "Bitcoinu" to properly fit Slovak grammar.

Correct translation:  
Vložená adresa „%1“ nie je platnou adresou Bitcoinu.
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Adresa "%1" už existuje ako prijímacia adresa s označením "%2" .Nemôže tak byť pridaná ako odosielacia adresa.</translation>
    
YES  
There is an issue with spacing in the translation. There should be a space after the period following "%2" and before "Nemôže". Also, the translation is slightly less natural due to word order and punctuation.

Correct translation:  
Adresa „%1“ už existuje ako prijímacia adresa s označením „%2“ a preto nemôže byť pridaná ako odosielacia adresa.
```

```
        <source>Spend unconfirmed change</source>
        <translation>Minúť nepotvrdený výdavok</translation>
    
YES  
The translation uses "výdavok" which means "expenditure" or "expense" and is not the correct term for "change" in the Bitcoin context. The correct translation for "change" (as in the leftover amount in a transaction) should be "zmenu". Also, the source phrase is a noun phrase or an option label ("Spend unconfirmed change"), so it should be translated in a noun or imperative form without unnecessary words.

Correct translation:  
Minúť nepotvrdenú zmenu
```

```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Zvoľte ako deliť bitcoin pri zobrazovaní pri platbách a užívateľskom rozhraní.</translation>
    
YES  
The translation does not accurately convey the meaning of "Choose the default subdivision unit to show in the interface and when sending coins." The original sentence refers to selecting a default unit of subdivision (e.g., BTC, mBTC, satoshi), but the translation says "Choose how to divide bitcoin when displaying at payments and user interface," which is vague and not precise. It also omits the idea of a "unit" and "default" setting and simplifies the context incorrectly.

Correct translation:  
"Zvoľte predvolenú jednotku delenia, ktorá sa zobrazí v rozhraní a pri odosielaní mincí."
```

```
        <source>Whether we relay addresses to this peer.</source>
        <extracomment>Tooltip text for the Address Relay field in the peer details area, which displays whether we relay addresses to this peer (Yes/No).</extracomment>
        <translation>Postupovanie adries tomuto partnerovi.</translation>
    
YES
The translation "Postupovanie adries tomuto partnerovi." is incomplete and somewhat unclear. It literally means "Forwarding addresses to this partner," but it lacks the conditional or interrogative nuance of "Whether we relay addresses to this peer." The original English implies a yes/no state (whether or not we relay the addresses), which is important, especially given the context as a tooltip. 

A better translation would convey the idea of whether or not addresses are relayed:

"Či adresy posielame tomuto partnerovi." 

This translates to "Whether we send addresses to this peer," better matching the original meaning and context.
```

```
        <source>In:</source>
        <translation>Dnu:</translation>
    
YES  
The Slovak word "Dnu:" means "inside" or "inwards," which is not appropriate in this Bitcoin transaction context. The source "In:" likely refers to an input (of a transaction) or "incoming," for which the correct Slovak translation is "Vstup:" or "Príjem:" depending on context. Usually, "Vstup:" is used for "In:" when referring to transaction inputs.

Correct translation:  
Vstup:
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Použitie núdzového poplatku („fallbackfee“) môže vyústiť v transakciu, ktoré bude trvat hodiny nebo dny (prípadne večnosť), kým bude potvrdená. Zvážte preto ručné nastaveníe poplatku, prípadne počkajte, až sa Vám kompletne zvaliduje reťazec blokov.</translation>
    
YES  
There are several errors in the Slovak translation:

1. "ktoré bude trvat" should be "ktorá bude trvať" because "transakciu" (transaction) is feminine singular, so the relative pronoun and verb must agree.
2. "nebo dny" mixes Czech ("nebo") and Slovak ("dni"). In Slovak, it should be "alebo dni".
3. Typo in "nastaveníe" - should be "nastavenie".
4. "zvaliduje" is a borrowed English term that is not commonly used in Slovak. A better verb would be "overíte" (validate, verify) or "potvrdíte".
5. "kompletne" in Slovak usually is "kompletnú" (accusative feminine to match "reťazec blokov" is masculine, so adjective should be masculine accusative: "kompletný reťazec", but since "reťazec" is masculine, "kompletný" is appropriate).
6. The phrase "kompletne zvaliduje reťazec blokov" is awkward. A better phrasing would be: "až overíte (alebo potvrdíte) kompletný reťazec blokov."

Correct translation:

Použitie núdzového poplatku („fallbackfee“) môže vyústiť v transakciu, ktorá bude trvať hodiny alebo dni (prípadne večnosť), kým bude potvrdená. Zvážte preto ručné nastavenie poplatku, prípadne počkajte, až overíte kompletný reťazec blokov.
```

```
        <source>Confirm custom change address</source>
        <translation>Potvrďte vlastnú výdavkovú adresu</translation>
    
YES  
The Slovak translation uses "výdavkovú adresu," which literally translates to "expense address." In the Bitcoin context, "change" refers to the leftover amount returned in a transaction, not expenses. The correct term for "change address" in Slovak Bitcoin terminology is "adresu na zvyšok" or "adresu na zmenu." A better translation is:  
Potvrďte vlastnú adresu na zmenu
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Zvoľte adresu kam poslať platbu</translation>
    
YES  
The source text is a neutral noun phrase "The Bitcoin address to send the payment to," describing what the address represents, not an imperative sentence. The translation says "Choose the address where to send the payment," which changes the meaning by adding an instruction to choose. A more accurate translation would be:

Bitcoinová adresa, na ktorú sa má poslať platba
```

```
        <source>The Bitcoin address to sign the message with</source>
        <translation>Bitcoin adresa pre podpísanie správy s</translation>
    
YES  
The Slovak translation is awkward and grammatically incorrect. The preposition "s" ("with") should precede "Bitcoin adresa" or be integrated properly. Also, the phrase should clearly convey "The Bitcoin address with which to sign the message."

Correct translation:  
Bitcoinová adresa, ktorou sa podpíše správa
```

```
        <source>Verify the message to ensure it was signed with the specified Bitcoin address</source>
        <translation>Overím správy sa uistiť že bola podpísaná označenou Bitcoin adresou</translation>
    
YES  
The translation contains grammatical errors and awkward phrasing. The verb "Overím" should be "Overiť" (infinitive form) to match "sa uistiť" and the sentence structure. Also, the phrase "sa uistiť že" needs a comma before "že". A clearer and more natural translation would be:

Correct translation:  
Overiť správu, aby ste sa uistili, že bola podpísaná uvedenou bitcoinovou adresou
```

```
        <source>Private key for the entered address is not available.</source>
        <translation>Súkromný kľúč pre zadanú adresu nieje k dispozícii.</translation>
    
YES  
There is a minor grammatical issue in Slovak: "nieje" should be written as two words "nie je".  

Correct translation:  
Súkromný kľúč pre zadanú adresu nie je k dispozícii.
```

```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Či je v tejto transakcii adresy iba na sledovanie.</translation>
    
YES  
The Slovak translation is incorrect and incomplete. The English sentence is conditional ("Whether or not a watch-only address is involved in this transaction."), but the Slovak version lacks a verb and proper structure. Also, "adresy iba na sledovanie" is grammatically incorrect (plural noun with "je," singular verb form missing, and meaning is unclear). The correct translation should express the condition clearly and maintain the original meaning.

Correct translation:  
"Či je v tejto transakcii zapojená iba adresa na sledovanie."
```

```
        <source>Edit address label</source>
        <translation>Upraviť popis transakcie</translation>
    
YES  
The English source text "Edit address label" refers to editing a label associated with a Bitcoin address, not a transaction. The Slovak translation "Upraviť popis transakcie" means "Edit transaction description," which is incorrect and changes the meaning entirely.

Correct translation:  
Upraviť označenie adresy
```

```
        <source>Could not commit transaction</source>
        <translation>Nemôzeme uložiť transakciu do peňaženky</translation>
    
YES  
The original English text "Could not commit transaction" is a more general error meaning the transaction could not be finalized/committed (to the blockchain or mempool), not necessarily related to saving in a wallet. The Slovak translation "Nemôzeme uložiť transakciu do peňaženky" means "We cannot save the transaction to the wallet," which is more specific and changes the meaning. A better translation keeping the original meaning would be:

"Nie je možné potvrdiť transakciu"  
or  
"Nie je možné vykonať transakciu"
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>Neplatné množstvo pre %s=&lt;amount&gt;: '%s' (musí byť aspoň  vo výške poplatku "minrelay" pre %s, aby sa zabránilo zaseknutým transakciám)</translation>
    
YES  
The translation contains a whitespace formatting issue: there is an extra space after "aspoň". Also, the phrase "vo výške poplatku "minrelay" pre %s" is somewhat awkward and unnecessarily complicated. A clearer and more natural Slovak translation would be:

Correct translation:  
Neplatné množstvo pre %s=&lt;amount&gt;: '%s' (musí byť aspoň poplatok minrelay vo výške %s, aby sa zabránilo zaseknutým transakciám)
```

```
        <source>Maximum transaction weight is too low, can not accommodate change output</source>
        <translation>Maximálna veľkosť transakcie je príliš nízka, nebudú sa do nej zmestiť výstupy </translation>
    
YES  
The translation has a trailing space at the end and the term "weight" is inaccurately translated as "veľkosť" (size), which is incorrect in this Bitcoin context where "weight" is a specific technical term ("váha"). Also, "výstupy" (outputs) is plural, but the source says "change output" singular. The translation does not convey that it specifically cannot accommodate the "change output."  

Correct translation:  
Maximálna hmotnosť transakcie je príliš nízka, neumožňuje zahrnúť výstup pre zmenu
```

```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Chyba: Obdržaná hodnota nebola v hex tvare: : %s</translation>
    
YES
There is an extra colon before the format specifier "%s" in the translation that does not appear in the source. The double colon ": :" should be corrected to a single colon ":" or removed if not needed.

Correct translation:
Chyba: Obdržaná hodnota nebola v hex tvare: %s
```

```
        <source>Error: Unable to write solvable wallet best block locator record</source>
        <translation>Chyba: Nepodarilo sa zapísať záznam o umiestnení najlepšieho bloku do peňaženky "solvable"</translation>
    
YES
The translation adds the English word "solvable" untranslated and includes unnecessary quotation marks, which is inconsistent with the source. Also, the source phrase "solvable wallet best block locator record" should be translated more literally to reflect the technical context accurately.

Correct translation:  
Chyba: Nepodarilo sa zapísať záznam o najlepšom lokalizátore bloku riešiteľnej peňaženky
```

```
        <source>SQLiteDatabase: Unexpected application id. Expected %u, got %u</source>
        <translation>SQLiteDatabase: Neočakávané ID aplikácie: %u. Očakávané:  %u</translation>
    
YES
The translation omits the part "got %u" ("dostal %u") which is present in the source and is crucial for the message to be complete. Also, there is an extra space before the second %u in the translation.

Correct translation:
SQLiteDatabase: Neočakávané ID aplikácie. Očakávané: %u, získané: %u
```

```
        <source>Signing transaction failed</source>
        <translation>Podpísanie správy zlyhalo</translation>
    
YES  
The English source says "Signing transaction failed," which refers to a failure in signing a Bitcoin transaction. The Slovak translation "Podpísanie správy zlyhalo" means "Signing the message failed," which is incorrect in this context. The correct word should be "transakcie" (transaction) instead of "správy" (message).

Correct translation:  
Podpísanie transakcie zlyhalo
```

```
        <source>System error while loading external block file: %s</source>
        <translation>Systémov chyba pri čítaní externého súboru blokov: %s</translation>
    
YES  
There is a typo in the Slovak word "Systémov". The correct word should be "Systémová" (feminine adjective agreeing with "chyba"). Also, "pri čítaní" means "while reading," which differs from "while loading" in the source. A more accurate Slovak translation of "while loading" would be "pri načítaní".

Correct translation:  
Systémová chyba pri načítaní externého súboru blokov: %s
```
</details>
