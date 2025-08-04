# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>sk</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Bsk%5D%20low%20quality)


```
        <source>Receiving addresses - %1</source>
        <translation>Prijímajúce adresy -%1</translation>
    
YES
The translation has an incorrect spacing between the hyphen and the format specifier.
Prijímajúce adresy - %1
```

```
        <source>IP/Netmask</source>
        <translation>IP/Maska stiete</translation>
    
YES: The translation is incorrect. "stiete" is not a valid Slovak word. The correct translation for "IP/Netmask" in a networking context is "IP/Maska podsiete".
IP/Maska podsiete
```

```
        <source>%1 and %2</source>
        <translation>%1 a  %2</translation>
    
YES, The translation has an extra space between "%1" and "%2".
%1 a %2
```

```
        <source>Proxy is &lt;b&gt;enabled&lt;/b&gt;: %1</source>
        <translation>Proxy sú &lt;b&gt;zapnuté&lt;/b&gt;: %1</translation>
    
YES. The translation uses the plural form of the verb "sú" (are) and the adjective "zapnuté" (enabled), while the English source text uses the singular form "is" and "enabled". The correct translation should use the singular form.

NO. Proxy je &lt;b&gt;zapnutý&lt;/b&gt;: %1
```

```
        <source>Verify messages to ensure they were signed with specified Bitcoin addresses</source>
        <translation>Overiť, či boli správy podpísané uvedenou Bitcoin adresou</translation>
    
YES - The translation is missing the word "addresses" (plural).
Correct translation: Overiť, či boli správy podpísané uvedenými Bitcoin adresami
```

```
        <source>Show the %1 help message to get a list with possible Bitcoin command-line options</source>
        <translation>Ukáž %1 zoznam možných nastavení Bitcoinu pomocou príkazového riadku</translation>
    
YES: The translation is inaccurate and confusing. It mistranslates "help message" as "zoznam možných nastavení" (list of possible settings) and "command-line options" as "pomocou príkazového riadku" (using the command line), which is grammatically awkward and loses the meaning of "options".

Correct translation: Ukáž pomocnú správu %1 so zoznamom možných príkazov príkazového riadka Bitcoinu
```

```
        <source>Sent transaction</source>
        <translation>Odoslané transakcie</translation>
    
YES, The translation is incorrect. The source text is singular "transaction", while the translation is plural "transakcie".
Odoslaná transakcia
```

```
        <source>The entered address "%1" is not a valid Bitcoin address.</source>
        <translation>Vložená adresa "%1" nieje platnou adresou Bitcoin.</translation>
    
YES, the translation has a grammatical error. The word "nieje" should be "nie je".
Vložená adresa "%1" nie je platnou adresou Bitcoin.
```

```
        <source>Address "%1" already exists as a receiving address with label "%2" and so cannot be added as a sending address.</source>
        <translation>Adresa "%1" už existuje ako prijímacia adresa s označením "%2" .Nemôže tak byť pridaná ako odosielacia adresa.</translation>
    
YES. The translation has an extraneous space before the period and incorrectly capitalizes "Nemôže".

Adresa "%1" už existuje ako prijímacia adresa s označením "%2", a preto nemôže byť pridaná ako odosielacia adresa.
```

```
        <source>Spend unconfirmed change</source>
        <translation>Minúť nepotvrdený výdavok</translation>
    
YES. The translation is problematic because "výdavok" means "expense" or "spending" rather than "change" in the context of Bitcoin transactions. The correct term for "change" in this context is "vydavok".

Minúť nepotvrdený výdavok
```

```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Zvoľte ako deliť bitcoin pri zobrazovaní pri platbách a užívateľskom rozhraní.</translation>
    
YES - The translation is inaccurate and misleading. The original text talks about choosing a "subdivision unit" for displaying Bitcoin amounts, not how to "divide Bitcoin when displaying for payments and the user interface".

Correct translation: Zvoľte si predvolenú podjednotku na zobrazovanie v rozhraní a pri posielaní bitcoinov.
```

```
        <source>Whether we relay addresses to this peer.</source>
        <extracomment>Tooltip text for the Address Relay field in the peer details area, which displays whether we relay addresses to this peer (Yes/No).</extracomment>
        <translation>Postupovanie adries tomuto partnerovi.</translation>
    
YES
The translation is not accurate and does not convey the meaning of the source text. It also fails to capture the nuance of "whether we relay".

Correct translation: Či preposielame adresy tomuto partnerovi.
```

```
        <source>In:</source>
        <translation>Dnu:</translation>
    
YES: The translation is incorrect. "Dnu:" is not a valid Slovak word in this context. The correct translation for "In:" in this context is "Do:".
Do:
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Použitie núdzového poplatku („fallbackfee“) môže vyústiť v transakciu, ktoré bude trvat hodiny nebo dny (prípadne večnosť), kým bude potvrdená. Zvážte preto ručné nastaveníe poplatku, prípadne počkajte, až sa Vám kompletne zvaliduje reťazec blokov.</translation>
    
YES, the translation has a grammatical error. The word "nastaveníe" should be "nastavenie".
Použitie núdzového poplatku („fallbackfee“) môže vyústiť v transakciu, ktoré bude trvat hodiny nebo dny (prípadne večnosť), kým bude potvrdená. Zvážte preto ručné nastavenie poplatku, prípadne počkajte, až sa Vám kompletne zvaliduje reťazec blokov.
```

```
        <source>Confirm custom change address</source>
        <translation>Potvrďte vlastnú výdavkovú adresu</translation>
    
YES
The translation uses "výdavkovú adresu" which translates to "spending address" or "disbursement address". In the context of Bitcoin transactions, "change" refers to the coins returned to the sender after an overpayment, not a spending address. Therefore, the translation is inaccurate and misleading.

A more accurate translation for "change address" in the context of Bitcoin is "adresu pre zvyšné mince" or "adresu na zvyšné mince".

Correct translation: Potvrďte vlastnú adresu pre zvyšné mince
```

```
        <source>The Bitcoin address to send the payment to</source>
        <translation>Zvoľte adresu kam poslať platbu</translation>
    
YES: The translation is inaccurate and does not convey the meaning of the original English text. The English text refers to a specific Bitcoin address, while the translation instructs the user to choose an address.

Correct translation: Adresa Bitcoin na odoslanie platby
```

```
        <source>The Bitcoin address to sign the message with</source>
        <translation>Bitcoin adresa pre podpísanie správy s</translation>
    
YES. The translation is awkward and grammatically incorrect. The preposition "s" at the end is misplaced and makes the sentence nonsensical in Slovak.

NO. The Bitcoin address to sign the message with
```

```
        <source>Verify the message to ensure it was signed with the specified Bitcoin address</source>
        <translation>Overím správy sa uistiť že bola podpísaná označenou Bitcoin adresou</translation>
    
YES: The translation uses incorrect verb conjugation and grammar. The correct translation should be "Overte správu, aby ste sa uistili, že bola podpísaná uvedenou Bitcoinovou adresou".
        Overte správu, aby ste sa uistili, že bola podpísaná uvedenou Bitcoinovou adresou
```

```
        <source>The entered address does not refer to a legacy (P2PKH) key. Message signing for SegWit and other non-P2PKH address types is not supported in this version of %1. Please check the address and try again.</source>
        <translation>Zadaná adresa neobsahuje zastaralý (P2PKH) kľúč. Podpisovanie správ pre SegWit a iné nie-P2PKH typy adries nie je v tejto verzii %1 podporované. Prosím skontrolujte adresu a skúste znovu.</translation>
    
YES, The translation incorrectly states "neobsahuje zastaralý (P2PKH) kľúč" which translates to "does not contain a legacy (P2PKH) key". The original English text states "does not refer to a legacy (P2PKH) key". The correct translation should be "neodkazuje na zastaralý (P2PKH) kľúč".

NO
```

```
        <source>Private key for the entered address is not available.</source>
        <translation>Súkromný kľúč pre zadanú adresu nieje k dispozícii.</translation>
    
YES: The translation contains a grammatical error. The correct spelling is "nie je".
Súkromný kľúč pre zadanú adresu nie je k dispozícii.
```

```
        <source>Merchant</source>
        <translation>Kupec</translation>
    
YES
The translation is incorrect. "Merchant" means "obchodník" in Slovak, not "kupec".
Obchodník
```

```
        <source>Whether or not a watch-only address is involved in this transaction.</source>
        <translation>Či je v tejto transakcii adresy iba na sledovanie.</translation>
    
YES: The translation is grammatically incorrect. The verb "is" should agree with the subject "address," and the possessive pronoun "this" should be plural to agree with "transaction." A more accurate translation would be: "Či je adresa iba na sledovanie zapojená do tejto transakcie."
```

```
        <source>Enter address, transaction id, or label to search</source>
        <translation>Pre vyhľadávanie vložte adresu, id transakcie, alebo popis.</translation>
    
YES - The translation uses the word "Pre" which means "before" or "for the purpose of" and does not fit the context. It should be "Na" which means "to" or "for" in this context. The word "popis" can be used as a label, but "štítok" is a more direct translation of "label" in the context of Bitcoin.

NO - Enter address, transaction id, or label to search
YES - Na vyhľadávanie vložte adresu, id transakcie, alebo štítok.
```

```
        <source>Edit address label</source>
        <translation>Upraviť popis transakcie</translation>
    
YES, The translation uses the word "transakcie" (transaction) which is incorrect in this context. The English source text "Edit address label" clearly refers to editing a label associated with a Bitcoin address, not a transaction.
Upraviť názov adresy
```

```
        <source>The transaction history was successfully saved to %1.</source>
        <translation>História transakciá bola úspešne uložená do %1.</translation>
    
YES. The translation uses a Czech word ("transakciá") instead of the correct Slovak word ("transakcií").
História transakcií bola úspešne uložená do %1.
```

```
        <source>Could not commit transaction</source>
        <translation>Nemôzeme uložiť transakciu do peňaženky</translation>
    
YES, The translation is inaccurate. The original sentence is a generic error message stating that the transaction could not be committed. The translation, however, implies that the transaction cannot be saved to the wallet, which is not necessarily the case and adds information that is not present in the source.

The correct translation should be: Nemohli sme odoslať transakciu
```

```
        <source>Cannot upgrade a non HD split wallet from version %i to version %i without upgrading to support pre-split keypool. Please use version %i or no version specified.</source>
        <translation>Nie je možné vylepšiť peňaženku bez rozdelenia HD z verzie %i na verziu %i bez upgradovania na podporu kľúčov pred rozdelením. Prosím použite verziu %i alebo nezadávajte verziu.</translation>
    
YES, The translation incorrectly translates "non HD split wallet" as "peňaženku bez rozdelenia HD" which translates to "wallet without HD split" instead of "non HD split wallet". The word "non" is not translated, and the order of the words is changed.
The correct translation is: Nie je možné vylepšiť non HD split wallet z verzie %i na verziu %i bez upgradovania na podporu kľúčov pred rozdelením. Prosím, použite verziu %i alebo nezadávajte žiadnu verziu.
```

```
        <source>The transaction amount is too small to send after the fee has been deducted</source>
        <translation>Suma je príliš malá pre odoslanie transakcie</translation>
    
YES: The translation is missing the important part about the fee being deducted, making it inaccurate in the context of Bitcoin transactions.

Correct translation: "Suma transakcie je príliš malá na odoslanie po odpočítaní poplatku."
```

```
        <source>Invalid amount for %s=&lt;amount&gt;: '%s' (must be at least the minrelay fee of %s to prevent stuck transactions)</source>
        <translation>Neplatné množstvo pre %s=&lt;amount&gt;: '%s' (musí byť aspoň  vo výške poplatku "minrelay" pre %s, aby sa zabránilo zaseknutým transakciám)</translation>
    
YES: The translation incorrectly uses the format specifier '%s' within the phrase "poplatku "minrelay" pre %s". The context suggests that the second '%s' should represent a currency or value, not be part of the description of the fee itself. The first '%s' correctly represents the amount type.

Correct translation: Neplatné množstvo pre %s=&lt;amount&gt;: '%s' (musí byť aspoň vo výške minimálneho poplatku pre %s, aby sa zabránilo zaseknutým transakciám)
```

```
        <source>Maximum transaction weight is too low, can not accommodate change output</source>
        <translation>Maximálna veľkosť transakcie je príliš nízka, nebudú sa do nej zmestiť výstupy </translation>
    
YES, the translation is missing the word "change" (zmena). The translation should be "Maximálna veľkosť transakcie je príliš nízka, nebudú sa do nej zmestiť výstupy zmeny."
```

```
        <source>Error: Got value that was not hex: %s</source>
        <translation>Chyba: Obdržaná hodnota nebola v hex tvare: : %s</translation>
    
YES: The translation has an extra colon before the format specifier.
Chyba: Obdržaná hodnota nebola v hex tvare: %s
```

```
        <source>Error: Unable to write solvable wallet best block locator record</source>
        <translation>Chyba: Nepodarilo sa zapísať záznam o umiestnení najlepšieho bloku do peňaženky "solvable"</translation>
    
YES: The translation incorrectly interprets "solvable wallet" as a wallet named "solvable". The original English text means "best block locator record for the solvable wallet". The word "solvable" is an adjective describing the wallet.

Chyba: Nepodarilo sa zapísať záznam o umiestnení najlepšieho bloku do riešiteľnej peňaženky
```

```
        <source>SQLiteDatabase: Unexpected application id. Expected %u, got %u</source>
        <translation>SQLiteDatabase: Neočakávané ID aplikácie: %u. Očakávané:  %u</translation>
    
YES: The translation has an extra space before the second '%u'.
SQLiteDatabase: Neočakávané ID aplikácie: %u. Očakávané: %u
```

```
        <source>Signing transaction failed</source>
        <translation>Podpísanie správy zlyhalo</translation>
    
YES, The word "správy" means "message" in Slovak, while the English source text is "transaction". The correct translation of "transaction" in Slovak is "transakcie".
Podpísanie transakcie zlyhalo
```

```
        <source>System error while loading external block file: %s</source>
        <translation>Systémov chyba pri čítaní externého súboru blokov: %s</translation>
    
YES - The word "Systémov" should be "Systému".
Systému chyba pri čítaní externého súboru blokov: %s
```
</details>
