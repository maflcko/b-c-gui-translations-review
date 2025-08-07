# Translations Review by LLM (✨ experimental)

The review quality depends on the LLM and the language. Currently, a fast LLM without rate limits is used. If you are interested in better quality for a specific language, please file an issue to ask for it to be re-run with a stronger model.



<details><summary>lt</summary>

[If the result is of low quality, please file an issue to find a better LLM for this language.](../../issues/new?title=%5Blt%5D%20low%20quality)


```
        <source>There was an error trying to save the address list to %1. Please try again.</source>
        <extracomment>An error message. %1 is a stand-in argument for the name of the file we attempted to save to.</extracomment>
        <translation>Bandant išsaugoti adresų sąrašą - įvyko klaida keliant į %1. Prašome bandyti dar kartą.</translation>
    
YES
The translation is mostly correct in meaning, but the structure is awkward and adds unnecessary wording ("keliant į", which means "uploading to", instead of "saving to"). The dash after "adresų sąrašą" is also unnecessary. The format specifier %1 is correctly transferred.

Correct translation:
Įvyko klaida bandant išsaugoti adresų sąrašą į %1. Prašome bandyti dar kartą.
```

```
        <source>Enter the old passphrase and new passphrase for the wallet.</source>
        <translation>Įveskite seną ir naują slaptažodį.</translation>
    
YES
The translation omits "for the wallet" ("piniginės" in Lithuanian), which could clarify which passphrases are meant. Also, the structure loses the explicit separation between old and new passphrase.

Correct translation:
Įveskite seną ir naują piniginės slaptažodį.
```

```
        <source>Remember that encrypting your wallet cannot fully protect your bitcoins from being stolen by malware infecting your computer.</source>
        <translation>Atminkite kad piniginės užšifravimas neužtrikrina kad jūsų bitkoinai negali būti pavogti dėl kenkėjiškų programų užkrėtusių jūsų kompiuterį.</translation>
    
YES
The Lithuanian translation contains several issues:
- "neu��trikrina" is a typo and should be "neužtikrina".
- There are missing commas for proper sentence structure.
- The sentence structure could be improved for clarity and flow.
- The negative construction "kad jūsų bitkoinai negali būti pavogti" translates as "that your bitcoins cannot be stolen", but the original merely says encryption cannot fully protect them from being stolen.
- The translation of "malware infecting your computer" as "kenkėjiškų programų užkrėtusių jūsų kompiuterį" is awkward and the participle is not well-placed.

Correct translation:
Atminkite, kad piniginės užšifravimas negali visiškai apsaugoti jūsų bitkoinų nuo vagystės, jei jūsų kompiuterį užkrečia kenkėjiška programa.
```

```
        <source>Load Partially Signed Bitcoin Transaction from clipboard</source>
        <translation>Užkraukite dalinai pasirašytas Bitcoin transakcijas iš iškarpinės...</translation>
    
YES
There are several issues:
1. "Užkraukite" is an unusual word in this context; "Įkelkite" is more appropriate for 'Load' when referring to data.
2. The English text is singular ("Transaction"), the translation uses plural ("transakcijas").
3. The ellipsis ("...") is not present in the source and should be omitted for consistency.

Correct translation:
Įkelkite dalinai pasirašytą Bitcoin transakciją iš iškarpinės
```

```
        <source>Type: %1
</source>
        <translation>Spausti: %1
</translation>
    
YES
The Lithuanian word "Spausti" means "Press" or "Click", which is incorrect for "Type". The correct translation for "Type" in this context is "Tipas".

Correct translation:
Tipas: %1
```

```
        <source>Label: %1
</source>
        <translation>Antraštė: %1
</translation>
    
YES
The translation of "Label" as "Antraštė" is incorrect in this context. "Antraštė" means "headline" or "title," not "label." The correct Lithuanian word for "label" (particularly in the Bitcoin UI context) is "Etiketė."

Correct translation:
Etiketė: %1
```

```
        <source>Copy change</source>
        <translation>Kopijuoti keisti</translation>
    
YES
The translation "Kopijuoti keisti" is inaccurate in Lithuanian. The English term "change" in the Bitcoin context means "likutis" or "grąža" (the returned amount in a transaction), not "keisti" (which means "to change" as a verb).

Correct translation:
Kopijuoti grąžą
```

```
        <source>change from %1 (%2)</source>
        <translation>pakeisti nuo %1 (%2)</translation>
    
YES
The Lithuanian translation "pakeisti nuo %1 (%2)" means "to change from %1 (%2)", which misinterprets "change" in the context of Bitcoin transactions. Here, "change" refers to the remainder (change amount) returned in a transaction, not the verb "to change." 

Correct translation:
grąža iš %1 (%2)
```

```
        <source>Number of script verification threads</source>
        <translation>Patvirtinimų skaičius</translation>
    
YES
The translation is inaccurate. "Patvirtinimų skaičius" translates to "Number of confirmations," which is not the same as "Number of script verification threads." The correct Lithuanian translation should reflect the "script verification threads" (i.e., threads/processes used to verify scripts).

Correct translation:
Skriptų tikrinimo gijų skaičius
```

```
        <source>Prune block storage to</source>
        <translation>blokuokite saugyklą į</translation>
    
YES
The translation is problematic. The English phrase "Prune block storage to" in the context of Bitcoin typically means to reduce the disk usage of block storage to a specified size. The Lithuanian translation "blokuokite saugyklą į" means "block the storage to", which is incorrect and misleading.

Correct translation:
Apkarpykite blokų saugyklą iki

This preserves the technical meaning ("prune" as in "trim" or "reduce", not "block") and matches the intent in the Bitcoin context.
```

```
        <source>Minimize to the tray instead of the taskbar</source>
        <translation>M sumažinti langą bet ne užduočių juostą</translation>
    
YES
The translation is incorrect and ungrammatical in Lithuanian. "M sumažinti" is not a meaningful phrase; likely "Minimizuoti į sistemos dėklą, o ne užduočių juostą" is intended. The format specifiers are not an issue here.

Correct translation:
Minimizuoti į sistemos dėklą, o ne į užduočių juostą
```

```
        <source>Choose the default subdivision unit to show in the interface and when sending coins.</source>
        <translation>Rodomų ir siunčiamų monetų kiekio matavimo vienetai</translation>
    
YES  
The Lithuanian translation does not accurately capture the meaning of the source text, which is about "choosing" the default subdivision unit; the translation simply describes "units for displaying and sending coins". Also, the imperative or instruction "Choose" is missing.

Correct translation:  
Pasirinkite numatytąjį monetų padalijimo vienetą, kuris bus rodomas sąsajoje ir siunčiant monetas.
```

```
        <source>Your current balance in watch-only addresses</source>
        <translation>Jūsų dabartinis balansas tik stebimų adresų</translation>
    
YES
The Lithuanian translation is ungrammatical. The prepositional phrase "tik stebimų adresų" is awkward and incorrect; it should be in the correct genitive structure and more clearly modified to match "watch-only addresses".

Correct translation:
Jūsų dabartinis balansas tik stebimuose adresuose
```

```
        <source>Cannot start bitcoin: click-to-pay handler</source>
        <translation>Negalima paleisti bitcoin: paspauskite sumokėti tvarkytojui</translation>
    
YES
The phrase "paspauskite sumokėti tvarkytojui" is a literal translation and does not convey the intended technical meaning of "click-to-pay handler" (i.e., a software handler for click-to-pay functionality). Also, "bitcoin" should be capitalized ("Bitcoin") in Lithuanian, following naming conventions. The translation should convey that the "click-to-pay handler" component of Bitcoin could not be started.

Correct translation:
Negalima paleisti Bitcoin: nepavyksta paleisti „click-to-pay“ tvarkyklės
```

```
        <source>'bitcoin://' is not a valid URI. Use 'bitcoin:' instead.</source>
        <translation>„bitcoin: //“ nėra galiojantis URI. Vietoj to naudokite „bitcoin:“.</translation>
    
YES
There is an erroneous space in "bitcoin: //" – it should be "bitcoin://", without the space. Also, Lithuanian quotation marks („...“) are correctly used, but the space inside the quotes is problematic.

Correct translation:
„bitcoin://“ nėra galiojantis URI. Vietoj to naudokite „bitcoin:“.
```

```
        <source>Custom change address</source>
        <translation>Pakeisti adresą</translation>
    
YES
The translation "Pakeisti adresą" means "Change address" (as in "to change the address"), not "Custom change address". It misses both the "custom" aspect and the nuance that this is a special type of address in Bitcoin ("change address" is a technical term).

Correct translation:
Individualus grąžos adresas
```

```
        <source>Using the fallbackfee can result in sending a transaction that will take several hours or days (or never) to confirm. Consider choosing your fee manually or wait until you have validated the complete chain.</source>
        <translation>Naudojant backbackfee gali būti siunčiamas sandoris, kuris užtruks kelias valandas ar dienas (arba niekada), kad patvirtintų. Apsvarstykite galimybę pasirinkti mokestį rankiniu būdu arba palaukite, kol patvirtinsite visą grandinę.</translation>
    
YES
There are multiple issues in the translation:
1. Typo: "backbackfee" should be "fallbackfee" or a correct Lithuanian equivalent. The original term should be kept ("fallbackfee", as there is no standard Lithuanian equivalent).
2. The phrase "kad patvirtintų" is grammatically awkward in this sentence and does not accurately render "to confirm". Better: "kad būtų patvirtintas" (so that the transaction is confirmed), or "kad būtų patvirtinta" referring to the action.
3. The sentence about waiting until validating the complete chain should be improved for clarity in Lithuanian.

Correct translation:
Naudojant fallbackfee gali būti išsiųsta transakcija, kurios patvirtinimas gali užtrukti kelias valandas, dienas ar net niekada neįvykti. Apsvarstykite galimybę pasirinkti mokestį rankiniu būdu arba palaukite, kol patvirtinsite visą blokų grandinę.
```

```
        <source>Add Recipient</source>
        <translation>A Pridėti gavėją</translation>
    
YES
There is an erroneous "A" at the beginning of the translation which does not belong there. The correct translation into Lithuanian is:

Pridėti gavėją
```

```
        <source>Enable Replace-By-Fee</source>
        <translation>Įgalinti keitimąsi mokesčiu</translation>
    
YES
The translation "Įgalinti keitimąsi mokesčiu" is not accurate. In the context of Bitcoin, "Replace-By-Fee" refers to a feature that allows transactions to be replaced with another transaction that pays a higher fee. The term "keitimąsi mokesčiu" suggests "exchange with fee" rather than enabling the Replace-By-Fee option.

Correct translation:
Įgalinti pakaitą pagal mokestį
```

```
        <source>With Replace-By-Fee (BIP-125) you can increase a transaction's fee after it is sent. Without this, a higher fee may be recommended to compensate for increased transaction delay risk.</source>
        <translation>Naudojant Replace-by-Fend (BIP-125) galite išsiųsti sandorio mokestį vėliau. Be jo, gali būti rekomenduojamas didesnis mokestis, kad būtų kompensuota padidėjusi sandorio vėlavimo rizika.</translation>
    
YES
There is an error in the translation:

1. "Replace-by-Fend" is incorrect. It should be "Replace-by-Fee".
2. The phrase "galite išsiųsti sandorio mokestį vėliau" mistranslates the meaning. It should convey the idea of increasing the fee after sending the transaction, not sending the fee later.
3. The rest of the translation is acceptable, but to increase accuracy and maintain the original meaning, the sentence structure should be revised.

Correct translation:
Naudodami Replace-by-Fee (BIP-125) galite padidinti sandorio mokestį po jo išsiuntimo. Be šios galimybės gali būti rekomenduojamas didesnis mokestis, kad būtų kompensuota padidėjusi sandorio vėlavimo rizika.
```

```
        <source>Copy change</source>
        <translation>Kopijuoti keisti</translation>
    
YES
The translation "Kopijuoti keisti" is inaccurate in Lithuanian. The English term "change" in the Bitcoin context means "likutis" or "grąža" (the returned amount in a transaction), not "keisti" (which means "to change" as a verb).

Correct translation:
Kopijuoti grąžą
```

```
        <source>Paste address from clipboard</source>
        <translation>Įvesti adresą iš mainų atminties</translation>
    
YES
The Lithuanian translation "Įvesti adresą iš mainų atminties" means "Enter address from clipboard". The verb "Įvesti" is "enter" or "input," whereas "Paste" should be translated as "Įklijuoti." The remainder of the translation is correct.

Correct translation:
Įklijuoti adresą iš mainų atminties
```

```
        <source>The Bitcoin address to sign the message with</source>
        <translation>Bitcoin adresas, kuriuo bus pasirašytas pranešimas su</translation>
    
YES
The Lithuanian translation "Bitcoin adresas, kuriuo bus pasirašytas pranešimas su" is grammatically incorrect; the word "su" ("with") is redundant at the end and makes the sentence ungrammatical. Correct translation should be:

Bitcoin adresas, kuriuo bus pasirašytas pranešimas
```

```
        <source>Paste address from clipboard</source>
        <translation>Įvesti adresą iš mainų atminties</translation>
    
YES
The Lithuanian translation "Įvesti adresą iš mainų atminties" means "Enter address from clipboard". The verb "Įvesti" is "enter" or "input," whereas "Paste" should be translated as "Įklijuoti." The remainder of the translation is correct.

Correct translation:
Įklijuoti adresą iš mainų atminties
```

```
        <source>Sign the message to prove you own this Bitcoin address</source>
        <translation>Registruotis žinute įrodymuii, kad turite šį adresą</translation>
    
YES
The translation is inaccurate. "Registruotis žinute" does not correctly convey "Sign the message" (should be "Pasirašykite žinutę"). "įrodymuii" is a typo and not correct. Also, it omits "Bitcoin" and "adresas/adresą", making it inaccurate for the Bitcoin context.

Correct translation:
Pasirašykite žinutę, kad įrodytumėte, jog valdote šį Bitcoin adresą
```

```
        <source>The signature did not match the message digest.</source>
        <translation>Parašas neatitinka žinutės.</translation>
    
YES
The translation is inaccurate. The source refers specifically to the message digest (a cryptographic hash of the message), but the translation omits "digest" and only refers to the "message" ("žinutės"), which reduces clarity regarding cryptographic context.

Correct translation:
Parašas neatitinka žinutės santraukos.
```

```
        <source>This pane shows a detailed description of the transaction</source>
        <translation>Šis langas sandorio detalų aprašymą</translation>
    
YES  
The Lithuanian translation is missing a verb and is grammatically incorrect. It should read as a full sentence.

Correct translation:  
Šiame lange rodomas išsamus sandorio aprašymas
```

```
        <source>Confirming (%1 of %2 recommended confirmations)</source>
        <translation>Patvirtinima (%1 iš rekomenduojamų patvirtinimų %2)</translation>
    
YES
The word "Patvirtinima" is incorrectly rendered and should be "Patvirtinama". The structure of the translation is unnatural, and the order of elements does not match the source. The correct translation should preserve the format specifiers and accurately reflect the original structure.

Correct translation:
Patvirtinama (%1 iš %2 rekomenduojamų patvirtinimų)
```

```
        <source>Confirmed (%1 confirmations)</source>
        <translation>Patvirtinta (%1 patvirtinimas)</translation>
    
YES
The translation does not correctly reflect the plural form "confirmations." The Lithuanian translation uses the singular "patvirtinimas," but it should be plural to match the English source.

Correct translation:
Patvirtinta (%1 patvirtinimai)
```

```
        <source>Enter address, transaction id, or label to search</source>
        <translation>Įveskite adresą ar žymę į paiešką</translation>
    
YES
The translation omits "transaction id" (sandorio ID) from the source, making it incomplete. The English "or" ("ar") should also consistently separate all options.

Correct translation:
Įveskite adresą, sandorio ID arba žymę paieškai
```

```
        <source>Error loading %s: Wallet requires newer version of %s</source>
        <translation>Klaida įkeliant %s: Piniginei reikia naujesnės%s versijos</translation>
    
YES
There is a spacing error in the translation: "naujesnės%s versijos" should be "naujesnės %s versijos" (a space is missing before %s). Additionally, the word order is a bit awkward; a clearer translation would be:

Correct translation:
Klaida įkeliant %s: piniginei reikia naujesnės %s versijos
```
</details>

Number of issues: 31.
